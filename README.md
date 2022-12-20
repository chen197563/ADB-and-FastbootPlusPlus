<p align="center"><img src="https://i.ibb.co/pj0Pnj7/ADB-and-Fastboot-Plus-Plus.png" width="200"></a>
<h1 align="center"><b>ADB & Fastboot++</b></h1>
<h4 align="center">A small Application for Windows that allows you to install the latest Version of ADB and Fastboot Files on the Computer without installing the entire Android SDK Package + Toolkit & Commands</h4>
<br />

<p align="center">
<a href="https://forum.xda-developers.com/t/tool-windows-adb-fastboot-march-2022.3944288/" alt="XDA Thread"><img src="https://img.shields.io/badge/XDA-Thread-orange.svg"></a>
<a href="" alt="Latest Release"><img src="https://img.shields.io/github/v/release/K3V1991/ADB-and-FastbootPlusPlus?color=blueviolet&label=Latest%20Release"></a>
<a href="" alt="Downloads"><img src="https://img.shields.io/github/downloads/K3V1991/ADB-and-FastbootPlusPlus/total?color=green&label=Downloads"></a>
<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=HW8B98TVDLKWA" alt="Donate-PayPal"><img src="https://img.shields.io/badge/Donate-PayPal-blue"></a>
<a href="https://github.com/K3V1991/Donate-Crypto/blob/main/README.md" alt="Donate-Crypto"><img src="https://img.shields.io/badge/Donate-Crypto-yellow"></a>
</p>
<hr>
<br />
<br />

## NFO:
* Versions: Installer & Portable
* Android Debug Bridge & Fastboot updated to latest v1.0.41 (Version 33.0.3-8952118, August 2022)

## Features:
* Installation Folder chooseable (Installer)
* Desktop & Start Menu Shortcuts (Installer)
* Toolkit
* View Commands, How-To enable Developer Options & USB Debugging
* Add to System Path Environment (Installer)
* Optional Universal ADB Driver Installation (Installer)

## Toolkit Features:
* Uninstall Bloatware without Root Access (They are just being uninstalled for the current User)
* Re-install uninstalled Apps
* Install Kernel (Reboots automatically to Bootloader, Popup Menu)
* Install Recovery (Reboots automatically to Bootloader, Popup Menu)
* Install APKs (Popup Menu)
* Install APK Bundles/Split APKs (Installer: Desktop/ABI Folder, Portable: ABI Folder)
* Push Files (Popup Menu)
* Check Firmware Version
* Check Android Version
* Check Kernel Version 
* Check Firmware Build Date
* Check Kernel Build Date
* Check Security Patch Date
* Check IMEI           
* Check IP Adresses
* Check App Packages   
* Check Process Activity (Real Time)
* Take Screenshots (PNG Format)
* Video recoding - 30, 60, 120 & 180 Seconds (Without Device Sound)
* Reboot the Device
* Reboot to Bootloader
* Exit Bootloader to System
* Reboot to Recovery
* Create Bugreport (Saves on Desktop)
* Create Logcat (Saves on Desktop)
* Exit (adb kill-server & close Toolkit)

## Requirements:
* Windows OS
* USB Driver for your Device or Universal ADB Driver (Included in the Installer)
* PowerShell for the Toolkit

## Enable Developer Options & USB Debugging:
<details>
  <summary>Click to expand</summary>
  
1. Install the USB Driver for your Device or Universal Adb Driver
2. On your Device, go to Settings > About. Find the Build Number and tap on it 7 times to enable Developer Options
3. Now enter System > Developer Options and find "USB debugging" and enable it
4. Plug your Device into the Computer and change it from "Charge only" to "File Transfer" Mode
5. On your Computer, browse to the Directory where you extracted the Portable Version or use Tiny ADB & Fastboot++ Shortcut
6. Launch a Command Prompt with Open CMD.bat or use Tiny ADB & Fastboot++ Shortcut
7. Once you’re in the Command Prompt, enter the following Command:
```
adb devices
```
8. System is starting the ADB Daemon (If this is your first Time running ADB, you will see a Prompt on your Phone asking you to authorize a Connection with the Computer. Click OK.)
9. Succesful enabled USB Debugging
</details>

## Unable to connect to ADB:
<details>
  <summary>Click to expand</summary>
  
1. AMD Bug - [XDA Thread](https://forum.xda-developers.com/t/fix-fastboot-issues-on-ryzen-based-pcs.4186321/)
2. Switch Device from "Charging" to "File Transfer" Mode
3. Install the latest Device Driver or Universal USB Driver
4. Try another USB Cable
5. Use another USB Port (USB 3.0 Port to USB 2.0)
6. Try to execute Fastboot Command without connecting your Device, and once it says "waiting for device" plug in your USB Cable
7. Windows: Click "Change advanced power setting" on your chosen Plan and expand "USB Settings". Under "USB Settings" Section, expand "USB selective suspend setting" and change it to "Disabled" for On Battery and Plugged In
8. Try another PC
</details>
  
## Installer:
1. Download ADB-and-Fastboot++_vXXX.exe
2. Follow the Installers Instructions and select where you would like to install ADB & Fastboot++
3. After the Installation Wizard has completed you can select to start ADB & Fastboot++
4. You should see a Command Window open, now you can use ADB and Fastboot Commands

## Portable:
1. Download ADB-and-Fastboot++_vXXX-Portable.zip
2. Extract the Zip Archive
3. Double click on Open CMD.bat
4. You should see a Command Window open, now you can use ADB and Fastboot Commands
<br />
<br />

## Screenshots:
<img src="https://i.ibb.co/C893W7r/License.png"></a>
<br />

<img src="https://i.ibb.co/DY3J282/Information.png"></a>
<br />

<img src="https://i.ibb.co/bNVRZqW/Tasks.png"></a>
<br />

<img src="https://i.ibb.co/T0jsgrf/Completing.png"></a>
<br />

<img src="https://i.ibb.co/KVQWfvP/Toolkit-Main.png"></a>
<br />

<img src="https://i.ibb.co/swGZZbj/Toolkit-Menu.png"></a>
