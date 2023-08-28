# 映泰B660GTN  黑苹果 OpenCore EFI

![image](https://github.com/hackintosh-efi/BIOSTAR-B660GTN-OpenCore/blob/main/ScreenShot/Motherboard/Motherboard.EN.png)

### OpenCore

[OpenCore 0.9.4](https://github.com/acidanthera/OpenCorePkg)

### 可安装系统

- macOS Monterey 12.x 
- macOS Ventura  13.x 

### 硬件

- 主板: 映泰B660GTN
- Bios版本: B66AY225.BST（2022-02-25）
- 处理器: 英特尔 i5-12490F
- 内存: 金泰克 2x32GB DDR4 3800MHz
- 硬盘: 1.建兴 CV6-8Q128 128G MacOS
- 硬盘: 2.宏碁掠夺者 GM7000 1TB Windows
- 硬盘: 3.希捷酷鱼 ST1000LM048 DATA
- 独显: 蓝宝石 RX6600
- 声卡: 瑞昱 ALC256
- 网卡: 瑞昱 PCle 2.5G网络控制器
- 无线: 英特尔 AX201
- 显示器: PHL275E9
- 电源: 台达 500W 1U
- 机箱: 小喆优品 A1

### Bios 设置

| 名称 | 选项 |
| ----- | --- |
| 高级 → CPU配置 → C6DRAM | 启用 |
| 高级 → CPU配置 →  Intel (VMX) Virtualization Technology | 启用 |
| 高级 → SATA Mode Selection | AHCI |
| 芯片组 → System Agent (SA)配置 → Primary Display | PCH PCI |
| 芯片组 → System Agent (SA)配置 →  VT-d | 禁用 |
| 芯片组 → System Agent (SA)配置 →  Above 4GB MMIO BIOS assignment | 启用 |
| 启动 → 启动配置 → 快速启动 | 禁用 |
| 启动 → 启动配置 → CSM支持 | 禁用 |
| 安全 → 系统模式 → 安全启动 | 禁用 |
| 调节器 → CPU Power Management → CFG Lock | 禁用 |
| 调节器 → GT Power Management → RC6(Render Standby) | 禁用 |


### 注意事项

 - 使用 [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) 生成 SMBIOS

 - 如果你使用12代具有小核心的CPU例如12600KF , 请务必修改Config.plist配置文件

 - Config.plist - Kernel内核设置 - ProvideCurrentCpuInfo - 勾选

![image](https://github.com/hackintosh-efi/BIOSTAR-B660GTN-OpenCore/blob/main/ScreenShot/config.plist.png)

 - Config.plist - Kernel内核设置 - AirportItlwm-Monterey.kext  Monertey 使用

 - Config.plist - Kernel内核设置 - AirportItlwm.kext  Ventura 使用

### 系统截图

- 关于本机

![image](https://github.com/hackintosh-efi/BIOSTAR-B660GTN-OpenCore/blob/main/ScreenShot/about_this_mac.jpg)

- Sensei

![image](https://github.com/hackintosh-efi/BIOSTAR-B660GTN-OpenCore/blob/main/ScreenShot/sensei.jpg)

- Geekbench5 跑分 i5-12490F 

![image](https://github.com/hackintosh-efi/BIOSTAR-B660GTN-OpenCore/blob/main/ScreenShot/Geekbench/CPU.jpg)

- Geekbench5 跑分 蓝宝石 RX6600 Metal 

![image](https://github.com/hackintosh-efi/BIOSTAR-B660GTN-OpenCore/blob/main/ScreenShot/Geekbench/GPUMetal.jpg)

- Geekbench5 跑分 蓝宝石 RX6600 OpenCL

![image](https://github.com/hackintosh-efi/BIOSTAR-B660GTN-OpenCore/blob/main/ScreenShot/Geekbench/GPUOpenCL.jpg)

- 机箱 小喆优品 A1

![image](https://github.com/hackintosh-efi/BIOSTAR-B660GTN-OpenCore/blob/main/ScreenShot/CASE.png)


### 联系我们 

- QQ群: 23304408

![image](ScreenShot/QRCode.png)

