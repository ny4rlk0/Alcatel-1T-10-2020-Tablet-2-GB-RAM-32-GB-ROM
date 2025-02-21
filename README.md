# Alcatel-1T-10-2020-Tablet-2-GB-RAM-32-GB-ROM
WIFI Fix Location: /mnt/vendor/nvdata/APCFG/APRDEB/
<!--<br>WIFI Fix Location: /data/nvram/APCFG/APRDEB/-->
<br>Warning if you set permission as rw- rw- --- MAC address will rewrited at each reboot. Setting it r-- r-- --- permanently fixes this.
<br>Yellow glowed line is MAC address that you can change inside WIFI and BT_Addr file. Using WinHEX!
<br>File Manager: Total Commander
<br>Root Status: Required! To get first root app, Patch with magisk and flash file with SP flash Tool.
<br>Pick the ones you want and Flash zip files  with [Ex Kernel Manager](https://play.google.com/store/apps/details?id=flar2.exkernelmanager&pli=1)
<br>Firmware: [Download](https://www.needrom.com/download/alcatel-1t10-smart-8092/)
<br>
<br>
## Usage (Follow the Order)
<br>Root the device.
<br>Install Total Commander.
<br>Allow root access for Total Commander.
<br>Turn off Bluetooth and WiFi.
<br>Copy BT_ADDR, WIFI and WIFI_Custom files to /mnt/vendor/nvdata/APCFG/APRDEB/
<br>Set all of the file permisions to User:rw- Group:rw- Everybody:rw-
<br>Turn on Bluetooth and WiFi.
<br>Turn off Bluetooth and WiFi.
<br>Reboot device.
<br>While rebooting device will replace all of these files with correct ones.
<br>Turn on Bluetooth and WiFi.(?)
<br>Turn off Bluetooth and WiFi.(?)
<br>Copy all of the files to computer. (BT_ADDR, WIFI and WIFI_Custom)
<br>Open WIFI and BT_Addr with WinHex.
![alt_text](https://github.com/ny4rlk0/Alcatel-1T-10-2020-Tablet-2-GB-RAM-32-GB-ROM/blob/main/wifi.png)
![alt_text](https://github.com/ny4rlk0/Alcatel-1T-10-2020-Tablet-2-GB-RAM-32-GB-ROM/blob/main/bt.png)
<br>Change the mac address as selected in yellow color on picture to your liking and save files.
<br>Put the files back to /mnt/vendor/nvdata/APCFG/APRDEB/
<br>Set all of the file permisions to User:r-- Group:r-- Everybody:r--
<br>Turn on Bluetooth and WiFi.(?)
<br>Turn off Bluetooth and WiFi.(?)
<br>Reboot.
<br>Now both wifi and bluetooth should be working with correct mac.
