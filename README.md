# Hackintosh-10850k-ASUS-Z490-XII-Hero-6900XT
---

## Description
---

This repository holds my current EFI build that I use for my system. The SSDTs are specifically built for my system, so use with caution. This build also contains my custom SSDT to device-id spoof my GPU, link for the repository is [here](https://github.com/TylerLyczak/Unsupported-6900XT-Hackintosh-Fix).


## Mac Version
---

* Mac OS Sonoma 14.5.0


## Hardware
---

#### Motherboard
* ASUS ROG Maximus XII Hero Z490

#### CPU
* Intel i9 10850k 10-Core

#### GPU
* PowerColor Radeon RX 6900XT Ultimate
    * This card is not supported by Mac OS Monterey 12.0.1 as of writing this
    * If you want to see how to get this to work, look at my [repository](https://github.com/TylerLyczak/Unsupported-6900XT-Hackintosh-Fix) about how to get it to work

#### RAM
* 4 x 8 GBs Corsair Dominator 3200 MHz

#### SSD
* Samsung 970 Pro 500gb (Mac drive)
* Inland Platinum 1TB (Windows drive)
* Inland Platinum 1TB (Linux drive)

#### Wi-Fi Card
* Intel Wi-Fi 6 AX 201 (built-in)

#### Sound
* ROG SupremeFX7.1 Surround Sound High Definition Audio CODEC S1220

#### CPU Cooler
* Corsair H115i

#### Power Supply
* Corsair RM 850x


## Not Working
---
* Going to sleep causes some Wi-Fi issues. It happened sometimes but not all the time.


## Unsure of what not works
---
* Thunderbolt
    * Have no thunderbolt devices to test


## Version List
---

### OpenCore
* OpenCore 1.0.0 RELEASE and DEBUG
    * [Link](https://github.com/acidanthera/OpenCorePkg)

### Kext List
* Airportitlwm 
    * v2.3.0-alpha (Sonomaa version)
    * [Link](https://github.com/OpenIntelWireless/itlwm)
* AppleALC
    * v1.9.0
    * [Link](https://github.com/acidanthera/AppleALC)
* CPUFriend
    * v1.2.7
    * Also has CPUFriendDataProvider for power configs for 10850k
    * [Link](https://github.com/acidanthera/CPUFriend)
* IntelBluetoothFirmware
    * v2.4.0
    * [Link](https://github.com/OpenIntelWireless/IntelBluetoothFirmware)
* ~~IntelBluetoothInjector~~
    * ~~v2.2.0~~
    * ~~[Link](https://github.com/OpenIntelWireless/IntelBluetoothFirmware)~~
* BlueToolFixup
    * v2.6.8
    * [Link](https://github.com/acidanthera/BrcmPatchRAM)
* IntelMausi
    * v1.0.7
    * [Link](https://github.com/acidanthera/IntelMausi)
* Lilu
    * v1.6.7
    * [Link](https://github.com/acidanthera/Lilu)
* NVMeFix
    * v1.1.1
    * [Link](https://github.com/acidanthera/NVMeFix)
* RTCMemoryFixup
    * v1.0.7
    * [Link](https://github.com/acidanthera/RTCMemoryFixup)
* SMCProcessor
    * v1.3.2
    * [Link](https://github.com/acidanthera/VirtualSMC)
* SMCSuperIO
    * v1.3.2
    * [Link](https://github.com/acidanthera/VirtualSMC)
* USBToolBox
    * v1.1.1
    * [Link](https://github.com/USBToolBox/kext)
* UTBMap
    * Mapping of the ports for motherboard
    * [Link](https://github.com/USBToolBox/kext)
* VirtualSMC
    * v1.3.0
    * [Link](https://github.com/acidanthera/VirtualSMC)
* WhateverGreen
    * v1.6.6
    * [Link](https://github.com/acidanthera/WhateverGreen)
* CpuTscSync
    * v1.1.0
    * [Link](https://github.com/acidanthera/CpuTscSync)


## Feedback
---

* If theres any problems with this guide, please open an issue and I'll get to it as soon as possible.

