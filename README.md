# acer-S50-51-EFI
acer S50-51 Hackintosh EFI with OpenCore 0.9.8

[中文版简介](https://github.com/Lifebrowser/acer-S50-51-EFI/blob/main/%E7%AE%80%E4%BB%8B.md)

[![OpenCore](https://img.shields.io/badge/OpenCore-0.9.8-lightblue.svg)](https://github.com/acidanthera/OpenCorePkg)
[![macOS-Stable](https://img.shields.io/badge/macOS-14.3.1-orange.svg)](https://www.apple.com/macos/sonoma/)
[![Windows-Stable](https://img.shields.io/badge/Windows-11-blue.svg)](https://www.microsoft.com/en-us/windows)

## Introduction

<summary><strong>Hardware</strong></summary>
<br>

[UEFI]

| Category  | Component                         | Note                                         |
| --------- | --------------------------------- | -------------------------------------------- |
| CPU       | Intel Core i7-10510U              |                                              |
| GPU       | Intel UHD Graphics                |                                              |
| SSD       | SK hynix BC501 512GB              |                                              |
| Memory    | 16GB DDR4 2666Mhz                 |                                              |
| Battery   | Single battery                    |                                              |
| Camera    | 720p Camera                       |                                              |
| Wifi & BT | Intel(R) Wifi6 AX 201 160MHz      |                                              |
| Input     | PS2 Keyboard & ELAN TrackPad      |                                              |

<summary><strong>Main software</strong></summary>
<br>

| Component      | Version        |
| -------------- |  ------------- |
| macOS Sonoma   | 14.3.1(23D60)  |
| Windows 11     | 23H2           |
| OpenCore       | v0.9.8         |

## Before installation

<summary><strong>UEFI settings</strong></summary>
<br>

**Security**

- `Memory Protection -> Execution Prevention` **Enabled**
- `Virtualization -> Intel Virtualization Technology` **Enabled**
- `Virtualization -> Intel VT-d Feature` **Enabled**

**Startup**

- `UEFI/Legacy Boot` **UEFI Only**
- `CSM Support` **No**

## Status

<summary><strong>What's working </strong></summary>

- [x] Battery percentage.
- [ ] CPU power management / performance. CPU always run in hi-speed, I got no idea about that, need help.
- [x] GPU UHD Graphics hardware acceleration / performance.
- [x] HDMI. `Closed and opened lid. With audio`
- [x] iMessage, FaceTime, App Store, iTunes Store. **Make sure to generate your own SMBIOS**
- [ ] Realtek Ethernet port.
- [x] Keyboard. `Volume and brightness hotkeys`
- [x] Realtek® Audio.
- [x] Sleep/Wake.
- [x] TouchPad. `1-5 fingers swipe works. Emulate force touch using longer and more voluminous touch`
- [x] USB Ports. 
- [x] Web camera.
- [x] Wifi. `Intel(R) Wifi6 AX 201 160MHz`
- [x] Bluetooth. `Intel Bluetooth 5.2`
- [x] Windows 11 boot from OC boot menu.

<summary><strong>What's not working </strong></summary>

## References & Special thanks to
- [OpenCore](https://dortania.github.io/OpenCore-Install-Guide/)
- [Acidanthera Mac Drivers](https://github.com/acidanthera)
- [Open Intel Wireless](https://github.com/OpenIntelWireless/itlwm)
- [Opencore Configurator](https://mackie100projects.altervista.org/opencore-configurator/)
