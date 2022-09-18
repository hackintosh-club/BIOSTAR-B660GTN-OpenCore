# BIOSTAR-B660GTN Hackintosh OpenCore EFI

### [简体中文](README.zh_CN.md)

### OpenCore

[OpenCore 0.8.4](https://github.com/acidanthera/OpenCorePkg)

### OS Version Tested

- macOS Monterey 12.x
- macOS Ventura  13.x 

### Hardware

- Motherboard: BIOSTAR B660GTN
- Bios Version: B66AY225.BST（2022-02-25）
- CPU: Intel i5-12490F
- RAM: kimtigo 2x32GB DDR4 3800MHz
- SSD: 1. LITEON CV6-8Q128 128G MacOS
- SSD: 2. Predator SSD GM7000 1TB Windows
- HDD: ST1000LM048-2€7172 DATA 
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
| Tweaker → CPU Power Management → CFG Lock | Disabled |
| Tweaker → GT Power Management → RC6(Render Standby) | Disabled |

### Notes

 - Use [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) build your own SMBIOS
 

### ScreenShot 

- Motherboard

![image](https://github.com/hackintosh-efi/BIOSTAR-B660GTN-OpenCore/blob/main/ScreenShot/Motherboard/Motherboard.EN.png)

- About This Mac

![image](https://github.com/hackintosh-efi/BIOSTAR-B660GTN-OpenCore/blob/main/ScreenShot/aboutthismac.png)

- Geekbench5 Score i5-12490F 

![image](https://github.com/hackintosh-efi/BIOSTAR-B660GTN-OpenCore/blob/main/ScreenShot/Geekbench/CPU.jpg)

- Geekbench5 Score Sapphire RX6600 Metal 

![image](https://github.com/hackintosh-efi/BIOSTAR-B660GTN-OpenCore/blob/main/ScreenShot/Geekbench/GPUMetal.jpg)

- Geekbench5 Score Sapphire RX6600 OpenCL

![image](https://github.com/hackintosh-efi/BIOSTAR-B660GTN-OpenCore/blob/main/ScreenShot/Geekbench/GPUOpenCL.jpg)