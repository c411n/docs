# Activar Windows server Evaluation

##  Para determinar la imagen a la que debe ser actualizado windows usar el siguiente comando
``` bash
DISM.exe /Online /Get-TargetEditions
```

## Para ejecutar la actualización:
```cmd
DISM /online /Set-Edition:ServerDatacenter /ProductKey:xxxxx-xxxxx-xxxxx-xxxxx-xxxxx /AcceptEula
```

## La activación sucede en tres pasos
``` bash
slmgr /ipk XXXXX-XXXXX-XXXXX-XXXXX-XXXXX
slmgr /skms [server]:[port]
slmgr /ato
slmgr /dlv
```
## Los servidores KMS públcos disponibles son

* kms8.msguides.com
* kms.digiboy.ir
* kms.ddns.net
* kms.shuax.com
* kensol263.imwork.net:1688
* kms789.com
* dimanyakms.sytes.net:1688
* kms.03k.org:1688
* 54.223.212.31
* kms.cnlic.com
* hq1.chinancce.com
* kms.chinancce.com
* franklv.ddns.net
* k.zpale.com
* m.zpale.com
* mvg.zpale.com
* xykz.f3322.org

## Las claves de activación son las siguientes

<table>
  <tr><th>Operating System Edition</th><th>KMS Client Product Key</th></tr>
  
  <tr><th colspan="2">🖥️ Windows 10 / 11</th></tr>
  <tr><td>Windows 10/11 Pro</td><td>W269N-WFGWX-YVC9B-4J6C9-T83GX</td></tr>
  <tr><td>Windows 10/11 Pro N</td><td>MH37W-N47XK-V7XM9-C7227-GCQG9</td></tr>
  <tr><td>Windows 10/11 Pro for Workstations</td><td>NRG8B-VKK3Q-CXVCJ-9G2XF-6Q84J</td></tr>
  <tr><td>Windows 10/11 Pro for Workstations N</td><td>9FNHH-K3HBT-3W4TD-6383H-6XYWF</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>

  <tr><td>Windows 10/11 Education</td><td>NW6C2-QMPVW-D7KKK-3GKT6-VCFB2</td></tr>
  <tr><td>Windows 10/11 Education N</td><td>2WH4N-8QGBV-H22JP-CT43Q-MDWWJ</td></tr>
  <tr><td>Windows 10/11 Pro Education</td><td>6TP4R-GNPTD-KYYHQ-7B7DP-J447Y</td></tr>
  <tr><td>Windows 10/11 Pro Education N</td><td>YVWGF-BXNMC-HTQYQ-CPQ99-66QFC</td></tr>  
  <tr><td colspan="2">&nbsp;</td></tr>
  
  <tr><td>Windows 10/11 Enterprise</td><td>NPPR9-FWDCX-D2C8J-H872K-2YT43</td></tr>
  <tr><td>Windows 10/11 Enterprise N</td><td>DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4</td></tr>
  <tr><td>Windows 10/11 Enterprise G</td><td>YYVX9-NTFWV-6MDM3-9PT4T-4M68B</td></tr>
  <tr><td>Windows 10/11 Enterprise G N</td><td>44RPN-FTY23-9VTTB-MP9BX-T84FV</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>
  
  <tr><td>Windows 11 Enterprise LTSC 2024</td><td rowspan="3">M7XTQ-FN8P6-TTKYV-9D4CC-J462D</td></tr>
  <tr><td>Windows 10 Enterprise LTSC 2021</td></tr>
  <tr><td>Windows 10 Enterprise LTSC 2019</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>

  <tr><td>Windows 11 Enterprise N LTSC 2024</td><td rowspan="3">92NFX-8DJQP-P6BBQ-THF9C-7CG2H</td></tr>
  <tr><td>Windows 10 Enterprise N LTSC 2021</td></tr>
  <tr><td>Windows 10 Enterprise N LTSC 2019</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>

  <tr><td>Windows 10 Enterprise LTSB 2016</td><td>DCPHK-NFMTC-H88MJ-PFHPY-QJ4BJ</td></tr>
  <tr><td>Windows 10 Enterprise LTSB 2015</td><td>WNMTR-4C88C-JK8YV-HQ7T2-76DF9</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>

  <tr><td>Windows 10 Enterprise N LTSB 2016</td><td>QFFDN-GRT3P-VKWWX-X7T3R-8B639</td></tr>
  <tr><td>Windows 10 Enterprise N LTSB 2015</td><td>2F77B-TNFGY-69QQF-B8YKP-D69TJ</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>  

  <tr><td>Windows IoT Enterprise LTSC 2024/2021</td><td>KBN8V-HFGQ4-MGXVD-347P6-PDQGT</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>
  
  <tr><th colspan="2">🖥️ Windows 8.1</th></tr>
  <tr><td>Windows 8.1 Pro</td><td>GCRJD-8NW9H-F2CDX-CCM8D-9D6T9</td></tr>
  <tr><td>Windows 8.1 Pro N</td><td>HMCNV-VVBFX-7HMBH-CTY9B-B4FXY</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>
  
  <tr><td>Windows 8.1 Enterprise</td><td>MHF9N-XY6XB-WVXMC-BTDCT-MKKG7</td></tr>
  <tr><td>Windows 8.1 Enterprise N</td><td>TT4HM-HN7YT-62K67-RGRQJ-JFFXW</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>
  
  <tr><th colspan="2">🖥️ Windows 8</th></tr>
  <tr><td>Windows 8 Pro</td><td>NG4HW-VH26C-733KW-K6F98-J8CK4</td></tr>
  <tr><td>Windows 8 Pro N</td><td>XCVCF-2NXM9-723PB-MHCB7-2RYQQ</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>
  
  <tr><td>Windows 8 Enterprise</td><td>32JNW-9KQ84-P47T8-D8GGY-CWCK7</td></tr>
  <tr><td>Windows 8 Enterprise N</td><td>JMNMF-RHW7P-DMY6X-RF3DR-X2BQT</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>

  <tr><th colspan="2">🖥️ Windows 7</th></tr>
  <tr><td>Windows 7 Professional</td><td>FJ82H-XT6CR-J8D7P-XQJJ2-GPDD4</td></tr>
  <tr><td>Windows 7 Professional N</td><td>MRPKT-YTG23-K7D7T-X2JMM-QY7MG</td></tr>
  <tr><td>Windows 7 Professional E</td><td>W82YF-2Q76Y-63HXB-FGJG9-GF7QX</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>
  
  <tr><td>Windows 7 Enterprise</td><td>33PXH-7Y6KF-2VJC9-XBBR8-HVTHH</td></tr>
  <tr><td>Windows 7 Enterprise N</td><td>YDRBP-3D83W-TY26F-D46B2-XCKRJ</td></tr>
  <tr><td>Windows 7 Enterprise E</td><td>C29WB-22CC8-VJ326-GHFJW-H9DH4</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>
  
  <tr><th colspan="2">🖥️ Windows Vista</th></tr>
  <tr><td>Windows Vista Business</td><td>YFKBB-PQJJV-G996G-VWGXY-2V3X8</td></tr>
  <tr><td>Windows Vista Business N</td><td>HMBQG-8H2RH-C77VX-27R82-VMQBT</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>
  
  <tr><td>Windows Vista Enterprise</td><td>VKK3X-68KWM-X2YGT-QR4M6-4BWMV</td></tr>
  <tr><td>Windows Vista Enterprise N</td><td>VTC42-BM838-43QHV-84HX6-XJXKV</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>
  
  <tr><th colspan="2">🗄️ Windows Server 2025</th></tr>
  <tr><td>Windows Server 2025 Standard</td><td>TVRH6-WHNXV-R9WG3-9XRFY-MY832</td></tr>
  <tr><td>Windows Server 2025 Datacenter</td><td>D764K-2NDRG-47T6Q-P8T8W-YP6DF</td></tr>
  <tr><td>Windows Server 2025 Datacenter: Azure Edition</td><td>XGN3F-F394H-FD2MY-PP6FD-8MCRC</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>

  <tr><th colspan="2">🗄️ Windows Server 2022</th></tr>
  <tr><td>Windows Server 2022 Standard</td><td>VDYBN-27WPP-V4HQT-9VMD4-VMK7H</td></tr>
  <tr><td>Windows Server 2022 Datacenter</td><td>WX4NM-KYWYW-QJJR4-XV3QB-6VM33</td></tr>
  <tr><td>Windows Server 2022 Datacenter: Azure Edition</td><td>NTBV8-9K7Q8-V27C6-M2BTV-KHMXV</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>  

  <tr><th colspan="2">🗄️ Windows Server 2019</th></tr>
  <tr><td>Windows Server 2019 Standard</td><td>N69G4-B89J2-4G8F4-WWYCC-J464C</td></tr>
  <tr><td>Windows Server 2019 Datacenter</td><td>WMDGN-G9PQG-XVVXX-R3X43-63DFG</td></tr>
  <tr><td>Windows Server 2019 Essentials</td><td>WVDHN-86M7X-466P6-VHXV7-YY726</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>

  <tr><th colspan="2">🗄️ Windows Server 2016</th></tr>
  <tr><td>Windows Server 2016 Standard</td><td>WC2BQ-8NRM3-FDDYY-2BFGV-KHKQY</td></tr>
  <tr><td>Windows Server 2016 Datacenter</td><td>CB7KF-BWN84-R7R2Y-793K2-8XDDG</td></tr>
  <tr><td>Windows Server 2016 Essentials</td><td>JCKRF-N37P4-C2D82-9YXRT-4M63B</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>

  <tr><th colspan="2">🗄️ Windows Server 2012 R2</th></tr>
  <tr><td>Windows Server 2012 R2 Standard</td><td>D2N9P-3P6X9-2R39C-7RTCD-MDVJX</td></tr>
  <tr><td>Windows Server 2012 R2 Datacenter</td><td>W3GGN-FT8W3-Y4M27-J84CP-Q3VJ9</td></tr>
  <tr><td>Windows Server 2012 R2 Essentials</td><td>KNC87-3J2TX-XB4WP-VCPJV-M4FWM</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>

  <tr><th colspan="2">🗄️ Windows Server 2012</th></tr>
  <tr><td>Windows Server 2012</td><td>BN3D2-R7TKB-3YPBD-8DRP2-27GG4</td></tr>
  <tr><td>Windows Server 2012 N</td><td>8N2M2-HWPGY-7PGT9-HGDD8-GVGGY</td></tr>
  <tr><td>Windows Server 2012 Single Language</td><td>2WN2H-YGCQR-KFX6K-CD6TF-84YXQ</td></tr>
  <tr><td>Windows Server 2012 Country Specific</td><td>4K36P-JN4VD-GDC6V-KDT89-DYFKP</td></tr>
  <tr><td>Windows Server 2012 Standard</td><td>XC9B7-NBPP2-83J2H-RHMBY-92BT4</td></tr>
  <tr><td>Windows Server 2012 MultiPoint Standard</td><td>HM7DN-YVMH3-46JC3-XYTG7-CYQJJ</td></tr>
  <tr><td>Windows Server 2012 MultiPoint Premium</td><td>XNH6W-2V9GX-RGJ4K-Y8X6F-QGJ2G</td></tr>
  <tr><td>Windows Server 2012 Datacenter</td><td>48HP8-DN98B-MYWDG-T2DCC-8W83P</td></tr>
  <tr><td>Windows Server 2012 Essentials</td><td>HTDQM-NBMMG-KGYDT-2DTKT-J2MPV</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>

  <tr><th colspan="2">🗄️ Windows Server 2008 R2</th></tr>
  <tr><td>Windows Server 2008 R2 Web</td><td>6TPJF-RBVHG-WBW2R-86QPH-6RTM4</td></tr>
  <tr><td>Windows Server 2008 R2 HPC edition</td><td>TT8MH-CG224-D3D7Q-498W2-9QCTX</td></tr>
  <tr><td>Windows Server 2008 R2 Standard</td><td>YC6KT-GKW9T-YTKYR-T4X34-R7VHC</td></tr>
  <tr><td>Windows Server 2008 R2 Enterprise</td><td>489J6-VHDMP-X63PK-3K798-CPX3Y</td></tr>
  <tr><td>Windows Server 2008 R2 Datacenter</td><td>74YFP-3QFB3-KQT8W-PMXWJ-7M648</td></tr>
  <tr><td>Windows Server 2008 R2 for Itanium-based Systems</td><td>GT63C-RJFQ3-4GMB6-BRFB9-CB83V</td></tr>
  <tr><td colspan="2">&nbsp;</td></tr>

  <tr><th colspan="2">🗄️ Windows Server 2008</th></tr>
  <tr><td>Windows Server 2008 Web</td><td>WYR28-R7TFJ-3X2YQ-YCY4H-M249D</td></tr>
  <tr><td>Windows Server 2008 Standard</td><td>TM24T-X9RMF-VWXK6-X8JC9-BFGM2</td></tr>
  <tr><td>Windows Server 2008 Standard without Hyper-V</td><td>W7VD6-7JFBR-RX26B-YKQ3Y-6FFFJ</td></tr>
  <tr><td>Windows Server 2008 Enterprise</td><td>YQGMW-MPWTJ-34KDK-48M3W-X4Q6V</td></tr>
  <tr><td>Windows Server 2008 Enterprise without Hyper-V</td><td>39BXF-X8Q23-P2WWT-38T2F-G3FPG</td></tr>
  <tr><td>Windows Server 2008 HPC</td><td>RCTX3-KWVHP-BR6TB-RB6DM-6X7HP</td></tr>
  <tr><td>Windows Server 2008 Datacenter</td><td>7M67G-PC374-GR742-YH8V4-TCBY3</td></tr>
  <tr><td>Windows Server 2008 Datacenter without Hyper-V</td><td>22XQ2-VRXRG-P8D42-K34TD-G3QQC</td></tr>
  <tr><td>Windows Server 2008 for Itanium-Based Systems</td><td>4DWFP-JF3DJ-B7DTH-78FJB-PDRHK</td></tr>
</table>

REFERENCIAS:
* https://gist.github.com/judero01col/4eac6f01f3fe64a48924b229c6427f01
* https://learn.microsoft.com/en-us/windows-server/get-started/kms-client-activation-keys
* https://msguides.com/windows-server
* https://github.com/MicrosoftDocs/windowsserverdocs/blob/main/WindowsServerDocs/get-started/kms-client-activation-keys.md