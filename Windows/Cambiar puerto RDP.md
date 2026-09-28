# Cambiar puerto RDP

Para cambiar el puerto RDP en Windows puede utilizarse Power shell

### Obtener el puerto RDP actual

````cmd
Get-ItemProperty -Path 'HKLM:\SYSTEM\CurrentControlSet\Control\Terminal Server\WinStations\RDP-Tcp' -name 'PortNumber'
````

### Establecer el nuevo puerto

````cmd
$portValue = '63295'; Set-ItemProperty -Path 'HKLM:\SYSTEM\CurrentControlSet\Control\Terminal Server\WinStations\RDP-Tcp' -name 'PortNumber' -Value $portValue
````

### Crear una nueva regla de firewall

````cmd
New-NetFirewallRule -DisplayName 'RDPPORTLatest-TCP-In' -Profile Public -Direction Inbound -Action Allow -Protocol TCP -LocalPort $portValue
````

````cmd
New-NetFirewallRule -DisplayName 'RDPPORTLatest-UDP-In' -Profile Public -Direction Inbound -Action Allow -Protocol UDP -LocalPort $portValue
````

### Reiniciar Windows

````cmd
Restart-Computer
`````
