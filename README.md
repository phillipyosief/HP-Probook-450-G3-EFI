# HP Probook 450 G3 EFI
Hackintosh EFI based on the EFI from FREEWING-JP

macOS Catalina 10.15.7

#### Specs:
 - Intel Core i3 (Skylake)
 - Intel HD Graphics 520
 - 4GB DDR4 RAM
 - SanDisk 1TB SSD
 - Realtek RTL8168H/8111H

#### SMBIOS
 - MacbookPro13,1
 - Don't forget to change SMBIOS for working iCloud services

## BIOS Setup
#### Bootoptions
 - Fast boot = ON
#### Secure Boot Configuration
 - Disable Legacy-Support and disable Secure Boot
#### System Options
 - Virtualization Technology (VTx) = on
#### Options for integrated devices
 - Graphic memory = 512MB
 - Boost Converter = ON
#### Power Managment Options 
 - Runtime-Batterymanagment = ON
 - Advanced Energiestatus-Settings = ON
 - Wake when Lid is Opened = ON
 - Power Control = ON

## What works
- iMessage
- FaceTime
- Other iCloud services
- Fn keys
- Audio
- HDMI
- VGA
- Keyboard / Mouse
- USB 2.0 / 3.0
- Ethernet
- WiFi / Bluetooth
- Trackpad
- Wake after sleep
- OpenCanopy
- Built-in Webcam
- SD-Card reader
- CD-Drive + burn
- Hand-off
- UEFI Booting

## What not works
 - Battery
 - AirDrop
 - Internet is a bit slow
 - Trackpad gestures
 - Mute speaker button
 - Disable WiFi button

## Not tested
 - Audio port
 - Sidecar
 - HDMI Audio
 - Built-in Mic

### Thanks to:
 - [Dortania OpenCore Guide](https://dortania.github.io/OpenCore-Install-Guide)
 - [null-x/HP-ProBook-450-G3-Hackintosh](https://github.com/null-x/HP-ProBook-450-G3-Hackintosh)
 - [FREEWING-JP/OpenCore_Intel_Skylake_EFI](https://github.com/FREEWING-JP/OpenCore_Intel_Skylake_EFI)
