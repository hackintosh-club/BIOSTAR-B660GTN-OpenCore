# BIOSTAR-B660GTN Hackintosh OpenCore EFI

### [简体中文](README.zh_CN.md)

### OpenCore

[OpenCore 0.8.6](https://github.com/acidanthera/OpenCorePkg)

### OS Version Tested

- macOS Monterey 12.x
- macOS Ventura  13.x 

### Hardware

- Motherboard: BIOSTAR B660GTN
- Bios Version: B66AY225.BST（2022-02-25）
- CPU: Intel i5-12490F
- RAM: kimtigo 2x32GB DDR4 3800MHz
- SSD: 1. LITEON CV6-8Q128 128G MacOS
- SSD: 2. Predator GM7000 1TB Windows
- HDD: Seagate ST1000LM048 DATA 
- GPU: Sapphire RX6600
- Audio: Realtek ALC256
- Ethernet: Realtek PCle 2.5GbE Family Controller
- Wireless: Intel AX201
- Display: PHL275E9
- PSU: Delta 500W 1U
- CASE: XiaoZheYouPin A1

### Bios Setup

| Name | Option |
| ----- | --- |
| Advenced → CPU Configuration →  C6DRAM | Enabled |
| Advenced → CPU Configuration →  Intel (VMX) Virtualization Technology | Enabled |
| Advenced → SATA Mode Selection | AHCI |
| Chipset → System Agent (SA) Configuration → Primary Display | PCH PCI |
| Chipset → System Agent (SA) Configuration →  VT-d | Disabled |
| Chipset → System Agent (SA) Configuration →  Above 4GB MMIO BIOS assignment | Enabled |
| Boot → Boot Configuration → Fast Boot | Disabled |
| Boot → Boot Configuration → CSM Support | Disabled |
| Security → System Mode → Secure Boot | Disabled |
| Tweaker → CPU Power Management → CFG Lock | Disabled |
| Tweaker → GT Power Management → RC6(Render Standby) | Disabled |

### Notes

 - Use [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) build your own SMBIOS
 
 - If you use 12th Gen small core CPU like 12600KF , U must change Config.plist

 - Config.plist - Kernel - ProvideCurrentCpuInfo - Ture

![image](https://github.com/hackintosh-efi/BIOSTAR-B660GTN-OpenCore/blob/main/ScreenShot/config.plist.png)
 
### ScreenShot 

- About This Mac

![image](https://github.com/hackintosh-efi/BIOSTAR-B660GTN-OpenCore/blob/main/ScreenShot/about_this_mac.jpg)

- Motherboard

![image](https://github.com/hackintosh-efi/BIOSTAR-B660GTN-OpenCore/blob/main/ScreenShot/Motherboard/Motherboard.EN.png)

- Sensei

![image](https://github.com/hackintosh-efi/BIOSTAR-B660GTN-OpenCore/blob/main/ScreenShot/sensei.jpg)

- Geekbench5 Score i5-12490F 

![image](https://github.com/hackintosh-efi/BIOSTAR-B660GTN-OpenCore/blob/main/ScreenShot/Geekbench/CPU.jpg)

- Geekbench5 Score Sapphire RX6600 Metal 

![image](https://github.com/hackintosh-efi/BIOSTAR-B660GTN-OpenCore/blob/main/ScreenShot/Geekbench/GPUMetal.jpg)

- Geekbench5 Score Sapphire RX6600 OpenCL

![image](https://github.com/hackintosh-efi/BIOSTAR-B660GTN-OpenCore/blob/main/ScreenShot/Geekbench/GPUOpenCL.jpg)

- CASE XiaoZheYouPin A1

![image](https://github.com/hackintosh-efi/BIOSTAR-B660GTN-OpenCore/blob/main/ScreenShot/CASE.png)