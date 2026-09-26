## Generalizar imagen Windows

Sysprep (System Preparation Tool) es una utilidad incluida en Windows que permite preparar una instalación para su clonación y despliegue en otros equipos, eliminando información específica como el SID y configuraciones únicas del hardware. Esto es esencial para crear imágenes reutilizables en entornos corporativos o de producción.

Funciones clave:

* **Generalizar** la instalación quitando identificadores únicos.
* **Configurar** arranque en modo auditoría o en la experiencia de bienvenida (OOBE).
* **Mantener** controladores si el hardware destino es idéntico, usando PersistAllDeviceInstalls=true en un archivo de respuesta.
**Compatibilidad** con imágenes actualizadas desde Windows 10 versión 1607 en adelante.

## Ejemplo de ejecución desde línea de comandos:

´´´
%WINDIR%\System32\Sysprep\Sysprep.exe /generalize /shutdown /oobe
´´´

* **/generalize:** elimina datos específicos del equipo.
* **/shutdown:** apaga el sistema tras el proceso.
* **/oobe:** configura el arranque en la experiencia de bienvenida.

***Si se trata de un VHD para la misma máquina virtual, añadir /mode:vm.***

### Procedimiento básico:

* **Arrancar en modo auditoría** (desde OOBE o archivo desatendido).
* **Personalizar:** agregar controladores, configurar ajustes, instalar software (evitar apps de Microsoft Store).
* **Ejecutar Sysprep** con las opciones deseadas.
* **Capturar** la imagen con DISM.
* **Implementar** en equipos de destino, que iniciarán en OOBE.


## Limitaciones y consideraciones:

* **Máximo 1001** ejecuciones de Sysprep por imagen en Windows 8.1/Server 2012 o superior (solo 3 en Windows 7/Server 2008 R2).
* No se admite en sistemas ya desplegados sin generalizar previamente.
* No ejecutar en equipos unidos a dominio (Sysprep los eliminará del dominio).
* Evitar cifrado de archivos/carpetas en NTFS antes de generalizar, ya que se perderán datos.
* Actualizaciones de Microsoft Store antes de generalizar provocan errores; usar aprovisionamiento offline.

**Uso con archivo de respuesta:** Para automatizar, en Microsoft-Windows-Deployment | Generalize establecer:

<Mode>OOBE</Mode>
<ForceShutdownNow>true</ForceShutdownNow>

Esto generaliza y apaga automáticamente el equipo tras el proceso.