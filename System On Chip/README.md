Most popular PCI devices in System On Chips
-------------------------------------------

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in System On Chips ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Iommu ](#iommu-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Multimedia controller ](#multimedia-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Network and computing encryption device ](#network-and-computing-encryption-device-pci)
   * [ Non-essential instrumentation ](#non-essential-instrumentation-pci)
   * [ Non-vga unclassified device ](#non-vga-unclassified-device-pci)
   * [ Serial bus controller ](#serial-bus-controller-pci)
   * [ Serial controller ](#serial-controller-pci)
   * [ Signal processing controller ](#signal-processing-controller-pci)
   * [ Smbus ](#smbus-pci)
   * [ Sound ](#sound-pci)
   * [ Storage ](#storage-pci)
   * [ Storage/ata ](#storageata-pci)
   * [ Storage/ide ](#storageide-pci)
   * [ Storage/nvme ](#storagenvme-pci)
   * [ Storage/raid ](#storageraid-pci)
   * [ Storage/sas ](#storagesas-pci)
   * [ System peripheral ](#system-peripheral-pci)
   * [ Usb controller ](#usb-controller-pci)
   * [ Others ](#others-pci)

PCI Devices
-----------

Count  - number of computers with this device installed,
Driver - driver in use for this device,
Probe  - latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14e4:2711 |           | Broadcom         | BCM2711 PCIe Bridge                  | 1085  | pcieport   | [B5468EBFDC](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/96A8781BC143/DEBIAN-12/6.6.51+RPT-RPI-V8/AARCH64/B5468EBFDC>) |
| 14e4:2712 |           | Broadcom         | BCM2712 PCIe Bridge                  | 93    | pcieport   | [350133D7C8](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 5 Model B Rev 1.0/7584AB09C679/GENTOO-2.17/6.6.47_P20240902-RASPBERRYPI-V8/AARCH64/350133D7C8>) |
| 1d87:3588 |           | Rockchip Elec... | RK3588                               | 76    | pcieport   | [B77549122F](<System On Chip/Others/Orange/Orange Pi 5 Pro/0B82E92470BF/DEBIAN-12/6.1.84-VENDOR-RK35XX/AARCH64/B77549122F>) |
| 10de:0faf | 10de:0000 | Nvidia           | PCI bridge                           | 65    | pcieport   | [4839A778AB](<System On Chip/Others/Others/Others/F2C84D69CC70/KUBUNTU-24.04/4.9.140-L4T/AARCH64/4839A778AB>) |
| 1d87:3566 |           | Rockchip Elec... | RK3568 Remote Signal Processor       | 23    | pcieport   | [73C1114ED7](<System On Chip/Others/Bananapi-R2/Bananapi-R2 Pro DDR4/8275FD3D1E08/DEBIAN-12/6.6.58-CURRENT-ROCKCHIP64/AARCH64/73C1114ED7>) |
| 10de:0fae | 10de:0000 | Nvidia           | PCI bridge                           | 22    | pcieport   | [6CF4A3E280](<System On Chip/Nvidia/Tegra/Tegra/3172D68D4339/UBUNTU-UNITY-18.04/4.9.337-TEGRA/AARCH64/6CF4A3E280>) |
| 1d87:0100 |           | Fuzhou Rockch... | RK3399 PCI Express Root Port         | 16    | pcieport   | [2609D42A42](<System On Chip/Rockchip/RK3399/RK3399 EVB IND LPDDR4 Board edp/464F72013DAF/DEBIAN-11/5.10.209/AARCH64/2609D42A42>) |
| 10de:1ad0 |           | Nvidia           | Tegra PCIe x8 Endpoint               | 13    | pcieport   | [B9B08FD326](<System On Chip/Others/NVIDIA/NVIDIA Jetson Xavier NX for DSBOARD-NX2/31F0467C6876/UBUNTU-20.04/5.10.104-TEGRA/AARCH64/B9B08FD326>) |
| 10de:229c |           | Nvidia           | PCI bridge                           | 12    | pcieport   | [F1E9617968](<System On Chip/Nvidia/Jetson/Jetson Orin Nano Developer Kit/153F1C357DEF/UBUNTU-22.04/5.15.148-TEGRA/AARCH64/F1E9617968>) |
| 1d39:8060 |           | Baikal Electr... | PCI bridge                           | 12    | pcieport   | [817E35C7CF](<System On Chip/Elpitech/ET151/ET151-2/2B6699C86C7D/ROSA-12.6/6.1.89-GENERIC-2ROSA2021.1-ARM64/AARCH64/817E35C7CF>) |
| 10de:1ad1 |           | Nvidia           | Tegra PCIe x4/x8 Endpoint/Root Co... | 11    | pcieport   | [B05FAAC149](<System On Chip/Others/NVIDIA/NVIDIA Jetson Xavier NX Developer Kit/FF85D7E95ADF/UBUNTU-20.04/5.10.104-TEGRA/AARCH64/B05FAAC149>) |
| 16c3:abcd |           | Synopsys         | DWC_usb3 / PCIe bridge               | 10    | pcieport   | [8D3DEA2269](<System On Chip/Others/Others/Others/0C5F3677AC7A/DEBIAN-12/5.15.147-SUN55IW3/AARCH64/8D3DEA2269>) |
| 1556:1111 |           | PLDA             | XpressRich-AXI Ref Design            | 9     | pcieport   | [A9FDC18349](<System On Chip/Others/Others/Others/E8E9F356F43D/ARCH-ROLLING/6.6.32-CWT-5.13.1-1/RISCV64/A9FDC18349>) |
| 10de:229e |           | Nvidia           | PCI bridge                           | 8     | pcieport   | [6B0861A4D4](<System On Chip/Nvidia/Tegra/Tegra/85EE9AF5177B/UBUNTU-20.04/5.10.104-TEGRA/AARCH64/6B0861A4D4>) |
| 17cd:dc01 |           | Cadence Desig... | Cadence Design PCI bridge            | 7     | pcieport   | [42E529E8EE](<System On Chip/GreatWall/GW-001/GW-001M1A-FTF/46777F1DB07E/UOS-20/4.19.260-ATZLINUX-FT9/AARCH64/42E529E8EE>) |
| 17cd:dc08 |           | Cadence Desig... | Cadence Design PCI bridge            | 7     | pcieport   | [42E529E8EE](<System On Chip/GreatWall/GW-001/GW-001M1A-FTF/46777F1DB07E/UOS-20/4.19.260-ATZLINUX-FT9/AARCH64/42E529E8EE>) |
| 17cd:dc16 |           | Cadence Desig... | Cadence Design PCI bridge            | 7     | pcieport   | [42E529E8EE](<System On Chip/GreatWall/GW-001/GW-001M1A-FTF/46777F1DB07E/UOS-20/4.19.260-ATZLINUX-FT9/AARCH64/42E529E8EE>) |
| 1b21:1182 | 1b21:118f | ASMedia Techn... | ASM1182e 2-Port PCIe x1 Gen2 Pack... | 5     | pcieport   | [21951E6105](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 5 Model B Rev 1.0/258066E0B646/DEBIAN-12/6.6.51+RPT-RPI-2712/AARCH64/21951E6105>) |
| 1b21:1184 | 1b21:118f | ASMedia Techn... | ASM1184e 4-Port PCIe x1 Gen2 Pack... | 4     | pcieport   | [32413F9B8D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.1/82EB67E2C71E/RAKPIOS-0.8.0-ARM64/6.1.77-V8-RAK+/AARCH64/32413F9B8D>) |
| 19e5:3690 |           | Huawei Techno... | PCI bridge                           | 3     | pcieport   | [BF1D53AB19](<System On Chip/HUAWEI/W515/W515 PGUV-WBY0/A9F952C22903/KYLIN-V10/4.19.71-30-KR990/AARCH64/BF1D53AB19>) |
| 19e5:3691 |           | Huawei Techno... | PCI bridge                           | 3     | pcieport   | [BF1D53AB19](<System On Chip/HUAWEI/W515/W515 PGUV-WBY0/A9F952C22903/KYLIN-V10/4.19.71-30-KR990/AARCH64/BF1D53AB19>) |
| 19e5:a120 | 19e5:371e | Huawei Techno... | HiSilicon PCIe Root Port with Gen4   | 3     | pcieport   | [9C60527586](<System On Chip/Others/Others/Others/722F349D9F34/UOS-20/4.19.0-ARM64-DESKTOP/AARCH64/9C60527586>) |
| 19e5:a121 |           | Huawei Techno... | HiSilicon PCI-PCI Bridge             | 3     | pcieport   | [9C60527586](<System On Chip/Others/Others/Others/722F349D9F34/UOS-20/4.19.0-ARM64-DESKTOP/AARCH64/9C60527586>) |
| 10de:1ad2 |           | Nvidia           | Tegra PCIe x1 Root Complex           | 2     | pcieport   | [A1E1FC9259](<System On Chip/Nvidia/Tegra/Tegra/565FBC48D0F2/UBUNTU-UNITY-18.04/4.9.140-TEGRA/AARCH64/A1E1FC9259>) |
| 10de:229a |           | Nvidia           | PCI bridge                           | 2     | pcieport   | [868EBC7932](<System On Chip/Others/NVIDIA/NVIDIA Orin NX Developer Kit/7871B6A37044/UBUNTU-20.04/5.10.104-TEGRA/AARCH64/868EBC7932>) |
| 144d:a544 |           | Samsung Elect... | Exynos 8890 PCIe Root Complex        | 2     | pcieport   | [8536DC733E](<System On Chip/Others/Others/Others/65321F980813/KALI-2021.3/3.18.140-GF49472F3951A/AARCH64/8536DC733E>) |
| 17cb:010b |           | Qualcomm         | SM8250 PCIe Root Complex [Snapdra... | 2     | pci_msm_rc | [F3B7AB67BC](<System On Chip/Others/Others/Others/BADA157665F2/KALI-2022.2/4.19.113-23222000/AARCH64/F3B7AB67BC>) |
| 17cb:0110 |           | Qualcomm Tech... | SM8475 PCIe Root Complex [Snapdra... | 2     |            | [848397F66D](<System On Chip/Others/Others/Others/61F83ED24CF2/DEBIAN-11/5.10.223-LXC-ABNOTF-MELT-2.9+/AARCH64/848397F66D>) |
| 1db7:dc01 |           | Phytium Techn... | PCI bridge                           | 2     | pcieport   | [83F3A5DAE1](<System On Chip/GreatWall/\xe4\xb8\x96\xe6\x81\x92D80F3-GWMDDB1EL1T/\xe4\xb8\x96\xe6\x81\x92D80F3-GWMDDB1EL1T, BIOS \xe9\x95\xbf\xe5\x9f\x8eBIOS V3.0 08-01-2024/D3BAC3DE34DC/KYLIN-V10/5.4.18-110-GENERIC/AARCH64/83F3A5DAE1>) |
| 1022:14e8 | 1022:14e8 | AMD              | Phoenix Root Complex                 | 1     |            | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 1022:14ea |           | AMD              | Phoenix Dummy Host Bridge            | 1     |            | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 1022:14eb | 1022:14eb | AMD              | Phoenix Internal GPP Bridge to Bu... | 1     | pcieport   | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 1022:14ed | 1022:1453 | AMD              | Phoenix GPP Bridge                   | 1     | pcieport   | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 1022:14ee | 1022:1453 | AMD              | Phoenix GPP Bridge                   | 1     | pcieport   | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 1022:14f0 |           | AMD              | Phoenix Data Fabric; Function 0      | 1     |            | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 1022:14f1 |           | AMD              | Phoenix Data Fabric; Function 1      | 1     |            | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 1022:14f2 |           | AMD              | Phoenix Data Fabric; Function 2      | 1     |            | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 1022:14f3 |           | AMD              | Phoenix Data Fabric; Function 3      | 1     | k10temp    | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 1022:14f4 |           | AMD              | Phoenix Data Fabric; Function 4      | 1     |            | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 1022:14f5 |           | AMD              | Phoenix Data Fabric; Function 5      | 1     |            | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 1022:14f6 |           | AMD              | Phoenix Data Fabric; Function 6      | 1     |            | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 1022:14f7 |           | AMD              | Phoenix Data Fabric; Function 7      | 1     |            | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 1022:790e | 1022:790e | AMD              | FCH LPC Bridge                       | 1     |            | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 104c:8232 |           | Texas Instrum... | XIO3130 PCI Express Switch (Upstr... | 1     |            | [DE0E6691CD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.0/06196A934E36/DEBIAN-11/5.10.63-V8+/AARCH64/DE0E6691CD>) |
| 104c:8233 |           | Texas Instrum... | XIO3130 PCI Express Switch (Downs... | 1     |            | [DE0E6691CD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.0/06196A934E36/DEBIAN-11/5.10.63-V8+/AARCH64/DE0E6691CD>) |
| 11ab:0110 |           | Marvell Techn... | 88F60x0/88F70x0/88F80x0/CN913x AR... | 1     | pcieport   | [864F7FA430](<System On Chip/SolidRun/CN9132/CN9132 based COM Express type 7/255D758D69A1/UBUNTU-20.04/5.8.0/AARCH64/864F7FA430>) |
| 144d:ecec |           | Samsung Elect... | Exynos 8895 PCIe Root Complex        | 1     | pcieport   | [61D82AF735](<System On Chip/Others/Others/Others/6555EFD46738/KALI-2023.1/5.10.107-ANDROID13-4-00004-G6522BF85D262-AB8935228/AARCH64/61D82AF735>) |
| 144d:eced |           | Samsung Elect... | Electronics PCI bridge               | 1     | pcieport   | [61D82AF735](<System On Chip/Others/Others/Others/6555EFD46738/KALI-2023.1/5.10.107-ANDROID13-4-00004-G6522BF85D262-AB8935228/AARCH64/61D82AF735>) |
| 14c3:7988 |           | MediaTek         | MT7988 PCIe Host Bridge [Filogic ... | 1     | pcieport   | [0CB51A29D7](<System On Chip/Others/Banana/Banana Pi BPI-R4/F5B0101EE831/UBUNTU-24.04/6.8.0-RC7-NEXT-20240306-BPI-R4-DANGO_2/AARCH64/0CB51A29D7>) |
| 14c3:8195 |           | MediaTek         | PCI bridge                           | 1     | pcieport   | [3B258A7433](<System On Chip/Radxa/NIO/NIO 12L/1B55228C661E/UBUNTU-22.04/5.15.0-1029-MTK/AARCH64/3B258A7433>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:5227 | 1028:0616 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 1     | rtsx_pci   | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1e60:2864 | 1e60:2864 | Hailo Technol... | Hailo-8 AI Processor                 | 1     | hailo_pci  | [126AE0AA3E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 5 Model B Rev 1.0/FDE9B565B1C3/DEBIAN-12/6.6.47-V8-16K+/AARCH64/126AE0AA3E>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:06e0 | 1462:12ed | Intel            | Comet Lake HECI Controller           | 1     | mei_me     | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:9c3a | 1028:0616 | Intel            | 8 Series HECI #0                     | 1     | mei_me     | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:a13a | 8086:1999 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | mei_me     | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15c7 | 1022:15c7 | AMD              | Phoenix CCP/PSP 3.0 Device           | 1     | ccp        | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1002:6611 | 1642:1869 | AMD              | Oland [Radeon HD 8570 / R5 430 OE... | 4     | radeon     | [42E529E8EE](<System On Chip/GreatWall/GW-001/GW-001M1A-FTF/46777F1DB07E/UOS-20/4.19.260-ATZLINUX-FT9/AARCH64/42E529E8EE>) |
| 0731:7200 | 0731:7201 | Jingjia Micro... | JM7200 Series GPU                    | 2     | mwv206     | [908F43A2C1](<System On Chip/Inspur/CE520/CE520F/7FB83A1EDF9D/KALI-2023.1/6.1.0-KALI5-ARM64/AARCH64/908F43A2C1>) |
| 0731:9100 | 0731:9101 | Jingjia Micro... | JM9100                               | 1     | jmgpu      | [83F3A5DAE1](<System On Chip/GreatWall/\xe4\xb8\x96\xe6\x81\x92D80F3-GWMDDB1EL1T/\xe4\xb8\x96\xe6\x81\x92D80F3-GWMDDB1EL1T, BIOS \xe9\x95\xbf\xe5\x9f\x8eBIOS V3.0 08-01-2024/D3BAC3DE34DC/KYLIN-V10/5.4.18-110-GENERIC/AARCH64/83F3A5DAE1>) |
| 1002:15bf | 1002:0124 | AMD              | Phoenix1                             | 1     | amdgpu     | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 1002:6611 | 1642:1871 | AMD              | Oland [Radeon HD 8570 / R5 430 OE... | 1     | radeon     | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |
| 1002:6611 | 174b:d340 | AMD              | Oland [Radeon HD 8570 / R5 430 OE... | 1     | radeon     | [B8EA59E9F8](<System On Chip/Inspur/CE520/CE520F/3A556DC2B09D/DEBIAN-11/5.10.0-18-ARM64/AARCH64/B8EA59E9F8>) |
| 1002:6779 | 1787:2300 | AMD              | Caicos [Radeon HD 6450/7450/8450 ... | 1     | radeon     | [2B4CD63D88](<System On Chip/HANWEI/FT-208/FT-208-COME-B/7D2A7DE07A62/ATZ-11.2/5.10.0-12-ARM64/AARCH64/2B4CD63D88>) |
| 1002:6779 | 1b0a:909d | AMD              | Caicos [Radeon HD 6450/7450/8450 ... | 1     | radeon     | [C4D7255808](<System On Chip/EAECIS/DF/DF35/DB296EEDCD8A/AOSC-11.4.2/6.9.7-AOSC-MAIN/AARCH64/C4D7255808>) |
| 1002:67ff | 1849:5037 | AMD              | Baffin [Radeon RX 550 640SP / RX ... | 1     | amdgpu     | [63A5E327FB](<System On Chip/SolidRun/LX2160A/LX2160A Clearfog CX/446971F0A5EC/UBUNTU-20.04/5.10.35-00021-G3CC6354C3606/AARCH64/63A5E327FB>) |
| 1002:699f | 1002:0b04 | AMD              | Lexa PRO [Radeon 540/540X/550/550... | 1     | amdgpu     | [817E35C7CF](<System On Chip/Elpitech/ET151/ET151-2/2B6699C86C7D/ROSA-12.6/6.1.89-GENERIC-2ROSA2021.1-ARM64/AARCH64/817E35C7CF>) |
| 1002:699f | 1642:1865 | AMD              | Lexa PRO [Radeon 540/540X/550/550... | 1     | amdgpu     | [5A3CB266DB](<System On Chip/GreatWall/DF/DF/5813E68F06D1/DEBIAN-11/5.10.0-22-ARM64/AARCH64/5A3CB266DB>) |
| 1002:699f | 1da2:e468 | AMD              | Lexa PRO [Radeon 540/540X/550/550... | 1     | amdgpu     | [3A00156F80](<System On Chip/Elpitech/ET101/ET101-1.1/FAE0EEB87647/ROSA-12.6/6.1.89-GENERIC-2ROSA2021.1-ARM64/AARCH64/3A00156F80>) |
| 10de:249d | 1462:12ed | Nvidia           | GA104M [GeForce RTX 3070 Mobile /... | 1     |            | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 126f:0768 | 126f:0768 | Silicon Motion   | SM768                                | 1     | smifb      | [39AE5B4339](<System On Chip/Others/Others/Others/1B388B1961AD/UBUNTU-20.04/4.9.38-BM1684-V10.5.0-00562-GA6D01E40BC7C-DIRTY/AARCH64/39AE5B4339>) |
| 1cd7:0011 | 0001:0000 | Nanjing Magew... | Electronics Multimedia video cont... | 1     | ProCapture | [868EBC7932](<System On Chip/Others/NVIDIA/NVIDIA Orin NX Developer Kit/7871B6A37044/UBUNTU-20.04/5.10.104-TEGRA/AARCH64/868EBC7932>) |
| 8086:0a16 | 1028:0616 | Intel            | Haswell-ULT Integrated Graphics C... | 1     | i915       | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:591b | 8086:2015 | Intel            | HD Graphics 630                      | 1     | i915       | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 8086:9bc4 | 1462:12ed | Intel            | CometLake-H GT2 [UHD Graphics]       | 1     | i915       | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |

### Iommu (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:14e9 | 1022:14e9 | AMD              | Phoenix IOMMU                        | 1     |            | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ee:7024 | 10ee:0007 | Xilinx           | Memory controller                    | 1     | alphase... | [B565B4082E](<System On Chip/Nvidia/Tegra/Tegra/70C6735F4190/UBUNTU-20.04/4.9.253-TEGRA/AARCH64/B565B4082E>) |
| 8086:06ef | 8086:7270 | Intel            | Comet Lake PCH Shared SRAM           | 1     |            | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15e2 | 1022:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     | snd_pci... | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 10cf:2049 | 13fe:8701 | Fujitsu Limited. | Fujitsu Multimedia controller        | 1     |            | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 13fe:0059 | 13fe:0059 | Advantech        | Multimedia controller                | 1     |            | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 544d:6178 | 6903:0020 | TBS Technologies | DVB Tuner PCIe Card                  | 1     |            | [6E70632A8C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.0/1EAFE8609AE7/RASPBIAN-10/5.10.63-V7L/ARMV7L/6E70632A8C>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1de4:0001 |           | Raspberry Pi     | RP1 PCIe 2.0 South Bridge            | 93    | rp1        | [350133D7C8](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 5 Model B Rev 1.0/7584AB09C679/GENTOO-2.17/6.6.47_P20240902-RASPBERRYPI-V8/AARCH64/350133D7C8>) |
| 10ec:8168 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 50    | r8168      | [F1E9617968](<System On Chip/Nvidia/Jetson/Jetson Orin Nano Developer Kit/153F1C357DEF/UBUNTU-22.04/5.15.148-TEGRA/AARCH64/F1E9617968>) |
| 10ec:8125 | 10ec:8125 | Realtek Semic... | RTL8125 2.5GbE Controller            | 38    | r8125      | [143735C29C](<System On Chip/FriendlyElec/NanoPC-T/NanoPC-T6/D6CF49999EAD/DEBIAN-12/6.1.75-VENDOR-RK35XX/AARCH64/143735C29C>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 22    | r8168      | [868EBC7932](<System On Chip/Others/NVIDIA/NVIDIA Orin NX Developer Kit/7871B6A37044/UBUNTU-20.04/5.10.104-TEGRA/AARCH64/868EBC7932>) |
| 19e5:a222 |           | Huawei Techno... | HNS GE/10GE/25GE RDMA Network Con... | 2     | hclge, ... | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |
| 1f0a:6801 | 2066:9806 | Suzhou Motorc... | YT6801 Gigabit Ethernet Controller   | 2     | yt6801     | [B77549122F](<System On Chip/Others/Orange/Orange Pi 5 Pro/0B82E92470BF/DEBIAN-12/6.1.84-VENDOR-RK35XX/AARCH64/B77549122F>) |
| 1055:7430 | 1055:7430 | Microchip Tec... | LAN7430                              | 1     | lan743x    | [6B0861A4D4](<System On Chip/Nvidia/Tegra/Tegra/85EE9AF5177B/UBUNTU-20.04/5.10.104-TEGRA/AARCH64/6B0861A4D4>) |
| 10ec:8161 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | r8168      | [DE0E6691CD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.0/06196A934E36/DEBIAN-11/5.10.63-V8+/AARCH64/DE0E6691CD>) |
| 10ec:8168 | 1028:0616 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 1     | r8169      | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 14e4-d... |           | Broadcom         | BCM58802 Stingray 50Gb Ethernet SoC  | 1     | bnxt_en    | [7B330403CA](<System On Chip/Broadcom/platform/platform/CE53981A57B8/DEBIAN-10/4.14.76_12/AARCH64/7B330403CA>) |
| 14e4:d802 | 14e4:8021 | Broadcom         | BCM58802 Stingray 50Gb Ethernet SoC  | 1     | bnxt_en    | [7B330403CA](<System On Chip/Broadcom/platform/platform/CE53981A57B8/DEBIAN-10/4.14.76_12/AARCH64/7B330403CA>) |
| 19e5:a221 | 19e5:0000 | Huawei Techno... | HNS GE/10GE/25GE Network Controller  | 1     | hclge, ... | [9C60527586](<System On Chip/Others/Others/Others/722F349D9F34/UOS-20/4.19.0-ARM64-DESKTOP/AARCH64/9C60527586>) |
| 19e5:a222 | 19e5:0000 | Huawei Techno... | HNS GE/10GE/25GE RDMA Network Con... | 1     | hclge, ... | [9C60527586](<System On Chip/Others/Others/Others/722F349D9F34/UOS-20/4.19.0-ARM64-DESKTOP/AARCH64/9C60527586>) |
| 8086:125d | 8086:0000 | Intel            | Ethernet Controller I226-IT          | 1     | igc        | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 8086:1572 | 8086:0000 | Intel            | Ethernet Controller X710 for 10Gb... | 1     | i40e       | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 8086:15b7 | 8086:0000 | Intel            | Ethernet Connection (2) I219-LM      | 1     | e1000e     | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 8086:3101 | 8086:0000 | Intel            | Killer E3100X 2.5 Gigabit Etherne... | 1     | igc        | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:8125 | 10ec:0123 | Realtek Semic... | RTL8125 2.5GbE Controller            | 21    | r8169      | [89B110C42D](<System On Chip/Radxa/ROCK/ROCK 5 Model B/5C546D75693A/FEDORA-41/6.13.0-0.RC3.32.FC41.AARCH64/AARCH64/89B110C42D>) |
| 10ec:b852 | 10ec:b852 | Realtek Semic... | RTL8852BE PCIe 802.11ax Wireless ... | 17    | rtl8852be  | [144DA6EB2B](<System On Chip/Others/RK3588/RK3588 CoolPi CM5 NoteBook/4B36186292AF/UBUNTU-24.04/6.1.75/AARCH64/144DA6EB2B>) |
| 14e4:43ec | 14e4:0000 | Broadcom         | BCM4356 802.11ac Wireless Network... | 10    | brcmfmac   | [4839A778AB](<System On Chip/Others/Others/Others/F2C84D69CC70/KUBUNTU-24.04/4.9.140-L4T/AARCH64/4839A778AB>) |
| 8086:24fd | 8086:1010 | Intel            | Wireless 8265 / 8275                 | 10    | iwlwifi    | [33FB218E9E](<System On Chip/Others/NVIDIA/NVIDIA Jetson Orin NX Engineering Reference Developer Kit/5E8A9F5432FC/UBUNTU-22.04/5.15.122-TEGRA/AARCH64/33FB218E9E>) |
| 10ec:c822 | 1a3b:3751 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 9     | rtl8822ce  | [7179C9D8D1](<System On Chip/Others/NVIDIA/NVIDIA Orin Nano Developer Kit/D01A996455D6/UBUNTU-20.04/5.10.104-TEGRA/AARCH64/7179C9D8D1>) |
| 14e4:449d | 14e4:aae8 | Broadcom         | BCM43752 802.11ax Dual Band Wirel... | 6     | bcmdhd     | [F965330063](<System On Chip/Khadas/Edge/Edge2/4CD4DD51C7D4/UBUNTU-24.04/6.1.43/AARCH64/F965330063>) |
| 8086:2725 | 8086:0024 | Intel            | Wi-Fi 6E(802.11ax) AX210/AX1675* ... | 6     | iwlwifi    | [72FD015C0C](<System On Chip/Xunlong/Orange/Orange Pi 5 Plus/51314DA00EFF/XUBUNTU-24.04/6.10.0-RC4-EDGE-ROCKCHIP-RK3588/AARCH64/72FD015C0C>) |
| 10ec:c822 | 10ec:c822 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 5     | rtw88_8... | [698590CBB5](<System On Chip/Nvidia/Jetson/Jetson Orin NX Engineering Reference Developer Kit/2E238731A989/UBUNTU-22.04/5.15.136-TEGRA/AARCH64/698590CBB5>) |
| 168c:003c |           | Qualcomm Atheros | QCA986x/988x 802.11ac Wireless Ne... | 3     | ath10k_pci | [73C1114ED7](<System On Chip/Others/Bananapi-R2/Bananapi-R2 Pro DDR4/8275FD3D1E08/DEBIAN-12/6.6.58-CURRENT-ROCKCHIP64/AARCH64/73C1114ED7>) |
| 17cb:1103 | 17cb:0108 | Qualcomm         | QCNFA765 Wireless Network Adapter    | 3     | cnss_pci   | [848397F66D](<System On Chip/Others/Others/Others/61F83ED24CF2/DEBIAN-11/5.10.223-LXC-ABNOTF-MELT-2.9+/AARCH64/848397F66D>) |
| 8086:24fd | 8086:0010 | Intel            | Wireless 8265 / 8275                 | 3     | iwlwifi    | [52CE936BA2](<System On Chip/Radxa/ROCK/ROCK 5B/7D2750DF2E7D/UBUNTU-24.04/6.1.0-1020-ROCKCHIP/AARCH64/52CE936BA2>) |
| 8086:2723 | 8086:0084 | Intel            | Wi-Fi 6 AX200                        | 3     | iwlwifi    | [C4D7255808](<System On Chip/EAECIS/DF/DF35/DB296EEDCD8A/AOSC-11.4.2/6.9.7-AOSC-MAIN/AARCH64/C4D7255808>) |
| 10ec:b852 | 1a3b:5470 | Realtek Semic... | RTL8852BE PCIe 802.11ax Wireless ... | 2     | rtl8852be  | [2609D42A42](<System On Chip/Rockchip/RK3399/RK3399 EVB IND LPDDR4 Board edp/464F72013DAF/DEBIAN-11/5.10.209/AARCH64/2609D42A42>) |
| 10ec:c822 | 1a3b:3750 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 2     | rtl8822ce  | [9BD5C753C8](<System On Chip/Nvidia/Jetson/Jetson Orin NX Engineering Reference Developer Kit/FC92A64D6630/UBUNTU-22.04/5.15.136-TEGRA/AARCH64/9BD5C753C8>) |
| 14c3:7961 | 14c3:7961 | MediaTek         | MT7921 802.11ax PCI Express Wirel... | 2     | mt7921e    | [FC68301711](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 5 Model B Rev 1.0/EC914041A64B/DEBIAN-12/6.6.31+RPT-RPI-2712/AARCH64/FC68301711>) |
| 14e4:4415 | 14e4:0751 | Broadcom         | BCM4359 802.11ac Dual-Band Wirele... | 2     | pcieh      | [8536DC733E](<System On Chip/Others/Others/Others/65321F980813/KALI-2021.3/3.18.140-GF49472F3951A/AARCH64/8536DC733E>) |
| 17cb:1101 | 17cb:0108 | Qualcomm         | QCA6390 Wireless Network Adapter     | 2     | cnss_pci   | [F3B7AB67BC](<System On Chip/Others/Others/Others/BADA157665F2/KALI-2022.2/4.19.113-23222000/AARCH64/F3B7AB67BC>) |
| 1b4b:2b42 |           | Marvell Techn... | 88W8997 2.4/5 GHz Dual-Band 2x2 W... | 2     | mwifiex... | [64ABB29282](<System On Chip/Google/Kevin/Kevin/8983C41D92B1/POSTMARKETOS-V23.12/6.2.0/AARCH64/64ABB29282>) |
| 8086:24fd | 8086:1130 | Intel            | Wireless 8265 / 8275                 | 2     | iwlwifi    | [BE96BBE4F4](<System On Chip/Nvidia/Tegra/Tegra/1F5B34B20D8B/UBUNTU-UNITY-18.04/4.9.140-TEGRA/AARCH64/BE96BBE4F4>) |
| 8086:2725 | 8086:e024 | Intel            | Wi-Fi 6E(802.11ax) AX210/AX1675* ... | 2     | iwlwifi    | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 10ec:b822 | 103c:831b | Realtek Semic... | RTL8822BE 802.11a/b/g/n/ac WiFi a... | 1     | rtwpci     | [1B215DD48C](<System On Chip/Nvidia/Jetson/Jetson Nano Developer Kit/58DEF6B21363/UBUNTU-20.04/5.5.5/AARCH64/1B215DD48C>) |
| 10ec:b852 | 17aa:4853 | Realtek Semic... | RTL8852BE PCIe 802.11ax Wireless ... | 1     | rtw89_8... | [45F5EE6292](<System On Chip/Orange Pi/5/5 Plus/293225169675/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.5.6-1-DEFAULT/AARCH64/45F5EE6292>) |
| 10ec:b852 | 1a3b:5480 | Realtek Semic... | RTL8852BE PCIe 802.11ax Wireless ... | 1     | rtw89_8... | [E47AFC9C97](<System On Chip/Radxa/ROCK/ROCK 5B Plus/FDCBC2947B23/UBUNTU-24.04/6.1.0-1025-ROCKCHIP/AARCH64/E47AFC9C97>) |
| 10ec:c821 | 10ec:c821 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 1     | rtw88_8... | [817E35C7CF](<System On Chip/Elpitech/ET151/ET151-2/2B6699C86C7D/ROSA-12.6/6.1.89-GENERIC-2ROSA2021.1-ARM64/AARCH64/817E35C7CF>) |
| 10ec:c822 | 103c:85f7 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 1     | rtw88_8... | [9395029E63](<System On Chip/BananaPi/RK3568-BPI-R2PRO-PC/RK3568-BPI-R2PRO-PC HDMI/56255AD26EC5/DEBIAN-10/5.10.110/AARCH64/9395029E63>) |
| 14c3:0608 | 14c3:0608 | MediaTek         | MT7921K (RZ608) Wi-Fi 6E 80MHz       | 1     |            | [F99CB416DB](<System On Chip/Others/Orange/Orange Pi 5 Plus/CC2FBD550985/DEBIAN-12/5.10.160-LEGACY-RK35XX/AARCH64/F99CB416DB>) |
| 168c:002a | 10cf:147c | Qualcomm Atheros | AR928X Wireless Network Adapter (... | 1     | ath9k      | [ECDDEDCFB7](<System On Chip/Nvidia/Tegra/Tegra/E867D231D0C0/UBUNTU-UNITY-18.04/4.9.201-TEGRA/AARCH64/ECDDEDCFB7>) |
| 168c:002a | 144f:7136 | Qualcomm Atheros | AR928X Wireless Network Adapter (... | 1     |            | [4C20D9DFAB](<System On Chip/Others/NVIDIA/NVIDIA Jetson Orin Nano Developer Kit/F44C759A9E76/UBUNTU-22.04/5.15.122-TEGRA/AARCH64/4C20D9DFAB>) |
| 168c:003e |           | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 1     | ath10k_pci | [AC382F40E8](<System On Chip/Qualcomm Technologies/Open-Q/Open-Q 820 microsom/F6FEB21E1005/DEBIAN-UNSTABLE/4.14.0-QCOMLT-ARM64/AARCH64/AC382F40E8>) |
| 168c:0042 | 11ad:1806 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 1     | ath10k_pci | [5E682A0733](<System On Chip/Nvidia/Tegra/Tegra/A1DD672248E9/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/5E682A0733>) |
| 168c:0042 | 17aa:0901 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 1     | ath10k_pci | [CFEB6FB78F](<System On Chip/Nvidia/Tegra/Tegra/52416602189B/UBUNTU-UNITY-18.04/4.9.253-TEGRA/AARCH64/CFEB6FB78F>) |
| 17cb:1104 | 17cb:1104 | Qualcomm Tech... | QCN6024/9024/9074 Wireless Networ... | 1     | ath11k_pci | [17236B81CF](<System On Chip/Others/Linksys/Linksys MR7500/638F48589FBF/OPENWRT-SNAPSHOT/6.6.68/AARCH64/17236B81CF>) |
| 8086:06f0 | 1a56:1552 | Intel            | Comet Lake PCH CNVi WiFi             | 1     | iwlwifi    | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:08b1 | 8086:4462 | Intel            | Wireless 7260                        | 1     | iwlwifi    | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:08b1 | 8086:5070 | Intel            | Wireless 7260                        | 1     | iwlwifi    | [39AE5B4339](<System On Chip/Others/Others/Others/1B388B1961AD/UBUNTU-20.04/4.9.38-BM1684-V10.5.0-00562-GA6D01E40BC7C-DIRTY/AARCH64/39AE5B4339>) |
| 8086:08b2 | 8086:c262 | Intel            | Wireless 7260                        | 1     | iwlwifi    | [F074596EF6](<System On Chip/Others/Orange/Orange Pi 5 Plus/199D754C0732/UBUNTU-22.04/5.10.160-ROCKCHIP/AARCH64/F074596EF6>) |
| 8086:08b3 | 8086:0070 | Intel            | Wireless 3160                        | 1     |            | [E76C7CF9C8](<System On Chip/Others/MNT/MNT Reform 2/1A8BBDCAD424/DEBIAN-11/5.12.0+/AARCH64/E76C7CF9C8>) |
| 8086:08b3 | 8086:8470 | Intel            | Wireless 3160                        | 1     | iwlwifi    | [E6512BB923](<System On Chip/Rockchip/RK3588/RK3588 OPi 5 Plus/3D7D56BEBE62/KUBUNTU-22.04/6.1.43-ROCKCHIP-RK3588/AARCH64/E6512BB923>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 1     | iwlwifi    | [C72F8C76F7](<System On Chip/Nvidia/Tegra/Tegra/B2307FE84F73/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/C72F8C76F7>) |
| 8086:2526 | 8086:0014 | Intel            | Wi-Fi 5(802.11ac) Wireless-AC 9x6... | 1     | iwlwifi    | [AE61EE56CD](<System On Chip/Nvidia/Tegra/Tegra/963F6586C41C/UBUNTU-20.04/5.10.192-TEGRA/AARCH64/AE61EE56CD>) |
| 8086:2526 | 8086:6014 | Intel            | Wi-Fi 5(802.11ac) Wireless-AC 9x6... | 1     | iwlwifi    | [1D9C2F174E](<System On Chip/Elpitech/ET/ET171/3C15B787A889/ROSA-12.5.1/6.1.89-GENERIC-2ROSA2021.1-ARM64/AARCH64/1D9C2F174E>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1db3:2355 |           | Unisoc Shangh... | Network controller                   | 2     | wcn_pcie   | [FCDAC368CF](<System On Chip/Others/Others/Others/367A728074AC/JINGOS-20.04/4.14.133-202201191758+/AARCH64/FCDAC368CF>) |
| 8086:1533 | ffff:0000 | Intel            | I210 Gigabit Network Connection      | 2     | igb        | [B05FAAC149](<System On Chip/Others/NVIDIA/NVIDIA Jetson Xavier NX Developer Kit/FF85D7E95ADF/UBUNTU-20.04/5.10.104-TEGRA/AARCH64/B05FAAC149>) |
| 14e4:4441 | 14e4:4389 | Broadcom         | Network controller                   | 1     | pcieh      | [61D82AF735](<System On Chip/Others/Others/Others/6555EFD46738/KALI-2023.1/5.10.107-ANDROID13-4-00004-G6522BF85D262-AB8935228/AARCH64/61D82AF735>) |
| 19e5:1103 | 19e5:0000 | Huawei Techno... | Network controller                   | 1     |            | [3F3D475864](<System On Chip/HUAWEI/PGU-WBY/PGU-WBY0/1C58824AF241/DEBIAN-11/5.10.0-18-ARM64/AARCH64/3F3D475864>) |
| 1ec4:0802 |           | Picocom Techn... | Ethernet controller                  | 1     | igb_uio    | [37707A34E6](<System On Chip/Others/LS1046A/LS1046A PSCB/30EAB2636DA2/UBUNTU-20.04/5.10.35-RT39-DIRTY/AARCH64/37707A34E6>) |
| 8086:10d3 | 8086:a01f | Intel            | 82574L Gigabit Network Connection    | 1     | e1000e     | [AC382F40E8](<System On Chip/Qualcomm Technologies/Open-Q/Open-Q 820 microsom/F6FEB21E1005/DEBIAN-UNSTABLE/4.14.0-QCOMLT-ARM64/AARCH64/AC382F40E8>) |
| 8086:1531 | 8086:0000 | Intel            | I210 Gigabit Unprogrammed            | 1     | igb        | [D48FD712A5](<System On Chip/Nvidia/Tegra/Tegra/A6096A1A9829/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/D48FD712A5>) |

### Network and computing encryption device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19e5:a255 |           | Huawei Techno... | HiSilicon SEC Engine                 | 2     | hisi_sec2  | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:14ec | 1022:14ec | AMD              | Phoenix Dummy Function               | 1     |            | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a5a5 |           | Samsung Elect... |                                      | 1     | s51xx      | [61D82AF735](<System On Chip/Others/Others/Others/6555EFD46738/KALI-2023.1/5.10.107-ANDROID13-4-00004-G6522BF85D262-AB8935228/AARCH64/61D82AF735>) |
| 8086:a124 |           | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| e000:684c | be8f:f7f7 | Winbond          |                                      | 1     |            | [4078CF0AE2](<System On Chip/Radxa/ROCK/ROCK 5 Model B/1329F4EC5BDB/FEDORA-41/6.9.0-0.RC5.20240426GITC942A0CD3603.48.FC41.AARCH64/AARCH64/4078CF0AE2>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:06a4 | 1462:12ed | Intel            | Comet Lake PCH SPI Controller        | 1     |            | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:06e8 | 1462:12ed | Intel            | Comet Lake PCH Serial IO I2C Cont... | 1     | intel_l... | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:06ea | 1462:12ed | Intel            | Comet Lake PCH Serial IO I2C Cont... | 1     | intel_l... | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |

### Serial controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14e4:160a | 14e4:8021 | Broadcom         | BCM5761E NetXtreme Desktop/Mobile    | 1     | serial     | [7B330403CA](<System On Chip/Broadcom/platform/platform/CE53981A57B8/DEBIAN-10/4.14.76_12/AARCH64/7B330403CA>) |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1502 | 1022:1502 | AMD              | IPU Device                           | 1     |            | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 1022:164a | 1022:164a | AMD              | Sensor Fusion Hub                    | 1     | amd_sfh    | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 8086:06f9 | 1462:12ed | Intel            | Comet Lake PCH Thermal Controller    | 1     | intel_p... | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:1903 | 1462:12ed | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 1     | process... | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:a131 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | intel_p... | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:790b | 1022:790b | AMD              | FCH SMBus Controller                 | 1     | i2c_piix4  | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 8086:06a3 | 1462:12ed | Intel            | Comet Lake PCH SMBus Controller      | 1     | i2c_i801   | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:9c22 | 1028:0616 | Intel            | 8 Series SMBus Controller            | 1     | i801_smbus | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:a123 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | i2c_i801   | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1002:aab0 | 1642:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 5     | snd_hda... | [42E529E8EE](<System On Chip/GreatWall/GW-001/GW-001M1A-FTF/46777F1DB07E/UOS-20/4.19.260-ATZLINUX-FT9/AARCH64/42E529E8EE>) |
| 1002:1640 | 1002:1640 | AMD              | Rembrandt Radeon High Definition ... | 1     | snd_hda... | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 1002:aa98 | 1787:aa98 | AMD              | Caicos HDMI Audio [Radeon HD 6450... | 1     | snd_hda... | [2B4CD63D88](<System On Chip/HANWEI/FT-208/FT-208-COME-B/7D2A7DE07A62/ATZ-11.2/5.10.0-12-ARM64/AARCH64/2B4CD63D88>) |
| 1002:aa98 | 1b0a:aa98 | AMD              | Caicos HDMI Audio [Radeon HD 6450... | 1     | snd_hda... | [C4D7255808](<System On Chip/EAECIS/DF/DF35/DB296EEDCD8A/AOSC-11.4.2/6.9.7-AOSC-MAIN/AARCH64/C4D7255808>) |
| 1002:aab0 | 174b:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 1     | snd_hda... | [B8EA59E9F8](<System On Chip/Inspur/CE520/CE520F/3A556DC2B09D/DEBIAN-11/5.10.0-18-ARM64/AARCH64/B8EA59E9F8>) |
| 1002:aae0 | 1002:aae0 | AMD              | Baffin HDMI/DP Audio [Radeon RX 5... | 1     | snd_hda... | [817E35C7CF](<System On Chip/Elpitech/ET151/ET151-2/2B6699C86C7D/ROSA-12.6/6.1.89-GENERIC-2ROSA2021.1-ARM64/AARCH64/817E35C7CF>) |
| 1002:aae0 | 1642:aae0 | AMD              | Baffin HDMI/DP Audio [Radeon RX 5... | 1     | snd_hda... | [5A3CB266DB](<System On Chip/GreatWall/DF/DF/5813E68F06D1/DEBIAN-11/5.10.0-22-ARM64/AARCH64/5A3CB266DB>) |
| 1002:aae0 | 1849:aae0 | AMD              | Baffin HDMI/DP Audio [Radeon RX 5... | 1     |            | [63A5E327FB](<System On Chip/SolidRun/LX2160A/LX2160A Clearfog CX/446971F0A5EC/UBUNTU-20.04/5.10.35-00021-G3CC6354C3606/AARCH64/63A5E327FB>) |
| 1002:aae0 | 1da2:aae0 | AMD              | Baffin HDMI/DP Audio [Radeon RX 5... | 1     | snd_hda... | [3A00156F80](<System On Chip/Elpitech/ET101/ET101-1.1/FAE0EEB87647/ROSA-12.6/6.1.89-GENERIC-2ROSA2021.1-ARM64/AARCH64/3A00156F80>) |
| 1022:15e3 | 1022:d595 | AMD              | Family 17h/19h/1ah HD Audio Contr... | 1     | snd_hda... | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 10de:228b | 1462:12ed | Nvidia           | GA104 High Definition Audio Contr... | 1     | snd_hda... | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 13f6:0111 | 13f6:0111 | C-Media Elect... | CMI8738/CMI8768 PCI Audio            | 1     |            | [7FD82B33F8](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.0/9656A1DE9286/RASPBIAN-10/5.10.17-V7L+/ARMV7L/7FD82B33F8>) |
| 8086:06c8 | 1462:12ed | Intel            | Comet Lake PCH cAVS                  | 1     | snd_hda... | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:0a0c | 1028:0616 | Intel            | Haswell-ULT HD Audio Controller      | 1     | snd_hda... | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:9c20 | 1028:0616 | Intel            | 8 Series HD Audio Controller         | 1     | snd_hda... | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:a171 | 8086:7270 | Intel            | CM238 HD Audio Controller            | 1     | snd_hda... | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Storage (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19bf:0014 | ff24:ffff | Unicom Engine... | IPI bus controller                   | 1     |            | [3494B0FDD9](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.1/CD7470FE63DD/DEBIAN-11/5.15.84-V8+/AARCH64/3494B0FDD9>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1b4b:9215 | 1b4b:9215 | Marvell Techn... | 88SE9215 PCIe 2.0 x1 4-port SATA ... | 8     | ahci       | [42E529E8EE](<System On Chip/GreatWall/GW-001/GW-001M1A-FTF/46777F1DB07E/UOS-20/4.19.260-ATZLINUX-FT9/AARCH64/42E529E8EE>) |
| 197b:0585 | 197b:0000 | JMicron Techn... | JMB58x AHCI SATA controller          | 3     | ahci       | [38FF4C1E6C](<System On Chip/Pine Microsystems/Pine64/Pine64 RockPro64 v2.1/AD797CAA5807/UBUNTU-22.04/6.1.63-CURRENT-ROCKCHIP64/AARCH64/38FF4C1E6C>) |
| 19e5:a235 |           | Huawei Techno... | HiSilicon AHCI HBA                   | 3     | ahci       | [9C60527586](<System On Chip/Others/Others/Others/722F349D9F34/UOS-20/4.19.0-ARM64-DESKTOP/AARCH64/9C60527586>) |
| 1b21:1064 | 2116:2116 | ASMedia Techn... | ASM1064 Serial ATA Controller        | 3     | ahci       | [BF1D53AB19](<System On Chip/HUAWEI/W515/W515 PGUV-WBY0/A9F952C22903/KYLIN-V10/4.19.71-30-KR990/AARCH64/BF1D53AB19>) |
| 1b4b:9171 | 1b4b:9171 | Marvell Techn... | 88SE9171 SATA 6G Controller          | 2     | ahci       | [A1E1FC9259](<System On Chip/Nvidia/Tegra/Tegra/565FBC48D0F2/UBUNTU-UNITY-18.04/4.9.140-TEGRA/AARCH64/A1E1FC9259>) |
| 1b21:0612 | 1b21:1060 | ASMedia Techn... | ASM1061/ASM1062 Serial ATA Contro... | 1     |            | [DF2E4C0C56](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.1/31DD7D4F6016/UBUNTU-22.10/5.19.0-1015-RASPI/AARCH64/DF2E4C0C56>) |
| 1b21:1166 | 2116:2116 | ASMedia Techn... | ASM1166 Serial ATA Controller        | 1     | ahci       | [94ADB9264D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 5 Model B Rev 1.0/EEBE0B14A8E6/DEBIAN-12/6.6.20+RPT-RPI-2712/AARCH64/94ADB9264D>) |
| 1b4b:9183 | 1b4b:9183 | Marvell Techn... | 88SS9183 PCIe SSD Controller         | 1     |            | [5E07806B7E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi ? Rev 1.0/D8FBFD41D06C/UBUNTU-20.04/5.4.0-1015-RASPI/AARCH64/5E07806B7E>) |
| 1b4b:9230 | 1b4b:9230 | Marvell Techn... | 88SE9230 PCIe 2.0 x2 4-port SATA ... | 1     | ahci       | [4B04BE2436](<System On Chip/Rockchip/Others/Others/F590D4D52D83/UBUNTU-20.04/4.4.154-113-ROCKCHIP-GDB9DFC2CDD25/AARCH64/4B04BE2436>) |
| 8086:9c03 | 1028:0616 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 1     | ahci       | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:a103 | 8086:7270 | Intel            | HM170/QM170 Chipset SATA Controll... | 1     | ahci       | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1b21:0611 | 1b21:1060 | ASMedia Techn... | ASM1061 Serial ATA Controller        | 3     | ahci       | [9379499EDA](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.1/FDDA7CA6B682/UBUNTU-22.04/5.15.0-1034-RASPI/AARCH64/9379499EDA>) |
| 197b:2363 | 197b:2363 | JMicron Techn... | JMB363 SATA/IDE Controller           | 1     | ahci       | [7DDF0DB7EC](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.0/7C8C1F01A3C3/UBUNTU-21.10/5.13.0-1010-RASPI/AARCH64/7DDF0DB7EC>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT (DRAM-less) NVM... | 14    | nvme       | [58E1D1052C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 5 Model B Rev 1.0/29854CF750EF/DEBIAN-12/6.6.62+RPT-RPI-2712/AARCH64/58E1D1052C>) |
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 14    | nvme       | [A3F513467D](<System On Chip/Radxa/ROCK/ROCK 5B/ED8AF74DB6E0/DEBIAN-12/6.1.75-VENDOR-RK35XX/AARCH64/A3F513467D>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980 (DRAM-less)  | 11    | nvme       | [41F881BE0F](<System On Chip/Others/Orange/Orange Pi 5/040497CB90DF/DEBIAN-12/5.10.160-LEGACY-RK35XX/AARCH64/41F881BE0F>) |
| 1e4b:1202 | 1e4b:1202 | MAXIO Technol... | NVMe SSD Controller MAP1202 (DRAM... | 9     | nvme       | [21951E6105](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 5 Model B Rev 1.0/258066E0B646/DEBIAN-12/6.6.51+RPT-RPI-2712/AARCH64/21951E6105>) |
| c0a9:540a | c0a9:5021 | Micron/Crucia... | P2 [Nick P2] / P3 / P3 Plus NVMe ... | 7     | nvme       | [4078CF0AE2](<System On Chip/Radxa/ROCK/ROCK 5 Model B/1329F4EC5BDB/FEDORA-41/6.9.0-0.RC5.20240426GITC942A0CD3603.48.FC41.AARCH64/AARCH64/4078CF0AE2>) |
| 144d:a80a | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 6     | nvme       | [42B3113792](<System On Chip/Elpitech/ET101/ET101-A1/3FCD932FA77C/ROSA-12.5.1/6.1.89-GENERIC-2ROSA2021.1-ARM64/AARCH64/42B3113792>) |
| 15b7:5009 | 15b7:5009 | SanDisk          | Ultra 3D / WD PC SN530, IX SN530,... | 5     | nvme       | [0CB51A29D7](<System On Chip/Others/Banana/Banana Pi BPI-R4/F5B0101EE831/UBUNTU-24.04/6.8.0-RC7-NEXT-20240306-BPI-R4-DANGO_2/AARCH64/0CB51A29D7>) |
| 15b7:501a | 15b7:501a | SanDisk          | Ultra 3D / WD Blue SN570 NVMe SSD... | 5     | nvme       | [D15665905B](<System On Chip/Orange Pi/5/5/2294BC8ACC77/UBUNTU-22.04/6.2.0-RC1-STATION-M3/AARCH64/D15665905B>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013-E13 PCIe3 NVMe Controller ... | 5     | nvme       | [190740E091](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 5 Model B Rev 1.0/C3F771363149/MX-23/6.6.51+RPT-RPI-V8/AARCH64/190740E091>) |
| 15b7:5006 | 15b7:5006 | SanDisk          | Extreme Pro / WD Black SN750 / PC... | 4     | nvme       | [AEBBBBE570](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 5 Model B Rev 1.0/0D0905B1642A/DEBIAN-12/6.6.47+RPT-RPI-2712/AARCH64/AEBBBBE570>) |
| 1e0f:0009 | 1e0f:0032 | KIOXIA           | NVMe SSD                             | 4     | nvme       | [495284E3D1](<System On Chip/FriendlyElec/NanoPC-T/NanoPC-T6/D5208CB48887/UBUNTU-24.04/6.1.43-VENDOR-RK35XX/AARCH64/495284E3D1>) |
| 2646:5013 | 2646:5013 | Kingston Tech... | KC3000/FURY Renegade NVMe SSD [E18]  | 4     | nvme       | [E47AFC9C97](<System On Chip/Radxa/ROCK/ROCK 5B Plus/FDCBC2947B23/UBUNTU-24.04/6.1.0-1025-ROCKCHIP/AARCH64/E47AFC9C97>) |
| 10ec:5765 | 10ec:5765 | Realtek Semic... | RTS5765DL NVMe SSD Controller (DR... | 3     | nvme       | [7283AC9C12](<System On Chip/Others/RK3588/RK3588 OPi 5 Plus/DFB55752DA48/ARCHARM/5.10.160-1/AARCH64/7283AC9C12>) |
| 1c5c:1d59 | 1c5c:1d59 | SK hynix         | BC901 NVMe Solid State Drive (DRA... | 3     | nvme       | [5326BE3AF7](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 5 Model B Rev 1.0/53CDB21B4CF2/DEBIAN/6.6.62+RPT-RPI-2712/AARCH64/5326BE3AF7>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 3     | nvme       | [AC78B76A30](<System On Chip/Hardkernel/ODROID-M/ODROID-M1/529F410B49D8/UBUNTU-20.04/5.19.0-ODROID-ARM64/AARCH64/AC78B76A30>) |
| 1ed0:2283 | 1ed0:2283 | Hosin Global ... | Patriot P300 NVMe SSD (DRAM-less)    | 3     | nvme       | [C8E7254C28](<System On Chip/Others/Orange/Orange Pi 5 Plus/6C2C48874E16/UBUNTU-24.04/6.1.75-VENDOR-RK35XX/AARCH64/C8E7254C28>) |
| 1344:5416 | 1344:1100 | Micron Techno... | 2550 NVMe SSD (DRAM-less)            | 2     | nvme       | [12F350A2BE](<System On Chip/Others/Others/Others/28AA6142B192/DEBIAN-12/6.10.6-EDGE-ROCKCHIP64/AARCH64/12F350A2BE>) |
| 15b7:5007 | 15b7:5007 | SanDisk          | IX SN530 NVMe SSD (DRAM-less)        | 2     | nvme       | [868EBC7932](<System On Chip/Others/NVIDIA/NVIDIA Orin NX Developer Kit/7871B6A37044/UBUNTU-20.04/5.10.104-TEGRA/AARCH64/868EBC7932>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 2     | nvme       | [A1512911DF](<System On Chip/Khadas/VIM/VIM3/8E76D129C324/UBUNTU-20.04/4.9.241/AARCH64/A1512911DF>) |
| 1c5c:1339 | 1c5c:0000 | SK hynix         | BC511 NVMe SSD                       | 2     | nvme       | [B2279D9F75](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 5 Model B Rev 1.0/ED4D632538E9/KALI-2024.4/6.1.64-V8+/AARCH64/B2279D9F75>) |
| 1cc1:5766 | 1cc1:5766 | ADATA Technology | XPG GAMMIXS1 1L, XPG GAMMIX S5, L... | 2     | nvme       | [B1C2A699A9](<System On Chip/Radxa/ROCK/ROCK 5B/5FDE956C73C1/UBUNTU-22.04/5.10.110-ROCKCHIP-RK3588/AARCH64/B1C2A699A9>) |
| 1f03:1202 | 1f03:1202 | Shenzhen Shic... | MAP1202-Based NVMe SSD (DRAM-less)   | 2     | nvme       | [E400F0C9B6](<System On Chip/GEDU/YourLand/YourLand/43D3DF996E1F/DEBIAN-12/5.10.110-ROCKCHIP-RK3588/AARCH64/E400F0C9B6>) |
| 2646:2263 | 2646:2263 | Kingston Tech... | A2000 NVMe SSD [SM2263EN]            | 2     | nvme       | [0BC6342638](<System On Chip/Rockchip/Orange/Orange Pi 5/7A895A1C1EAC/DEBIAN-11/6.1.43-ROCKCHIP-RK3588/AARCH64/0BC6342638>) |
| 2646:500f | 2646:500f | Kingston Tech... | NV1 NVMe SSD [SM2263XT] (DRAM-less)  | 2     | nvme       | [C6BA3BADCB](<System On Chip/Others/Orange/Orange Pi 5 Plus/0B5AD33FD98E/UBUNTU-22.04/5.10.160-LEGACY-RK35XX/AARCH64/C6BA3BADCB>) |
| 8086:f1a8 | 8086:390d | Intel            | SSD 660P Series                      | 2     | nvme       | [A9FDC18349](<System On Chip/Others/Others/Others/E8E9F356F43D/ARCH-ROLLING/6.6.32-CWT-5.13.1-1/RISCV64/A9FDC18349>) |
| c0a9:540a | c0a9:540a | Micron/Crucia... | P2 [Nick P2] / P3 / P3 Plus NVMe ... | 2     | nvme       | [4AFE74277E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 5 Model B Rev 1.0/2B7371122309/DEBIAN-12/6.6.30-V8+/AARCH64/4AFE74277E>) |
| 1179:011a | 1179:0001 | Toshiba Ameri... | XG6 NVMe SSD Controller              | 1     | nvme       | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |
| 1217:8760 | 1217:0002 | O2 Micro         | FORESEE E2M2 NVMe SSD                | 1     | nvme       | [2D03646368](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 5 Model B Rev 1.0/994320F1FBA4/MX-23/6.6.47+RPT-RPI-2712/AARCH64/2D03646368>) |
| 126f:2263 | 1dee:2263 | Silicon Motion   | SM2263EN/SM2263XT (DRAM-less) NVM... | 1     | nvme       | [C17309EC68](<System On Chip/Khadas/VIM/VIM3/6CB0C4BD1229/UBUNTU-20.04/5.17.0/AARCH64/C17309EC68>) |
| 1344:5405 | 1344:0100 | Micron Techno... | 2300 NVMe SSD [Santana]              | 1     | nvme       | [E0836009F7](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 5 Model B Rev 1.0/FF655341B2C6/DEBIAN-12/6.6.33-V8-16K+/AARCH64/E0836009F7>) |
| 1344:5411 | 1344:0100 | Micron Techno... | 2450 NVMe SSD [HendrixV] (DRAM-less) | 1     | nvme       | [BB10B65F08](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 5 Model B Rev 1.0/6059785671D1/DEBIAN-12/6.6.51+RPT-RPI-2712/AARCH64/BB10B65F08>) |
| 1344:5413 | 1344:1100 | Micron Techno... | 2400 NVMe SSD (DRAM-less)            | 1     | nvme       | [B1EB9CD869](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 5 Model B Rev 1.0/994A36CA8C00/DEBIAN-12/6.1.74-V8-16K+/AARCH64/B1EB9CD869>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 1     | nvme       | [DE559AC6D9](<System On Chip/Rockchip/Others/Others/748AF68BF4FB/UBUNTU-MATE-20.04/4.4.154-113-ROCKCHIP-GDB9DFC2CDD25/AARCH64/DE559AC6D9>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 1     | nvme       | [0965D05FE6](<System On Chip/Nvidia/Tegra/Tegra/90823179FECD/UBUNTU-UNITY-18.04/4.9.140-TEGRA/AARCH64/0965D05FE6>) |
| 144d:a80b | 144d:a80b | Samsung Elect... | NVMe SSD Controller PM9B1 (DRAM-l... | 1     | nvme       | [ECCB316F36](<System On Chip/Radxa/ROCK/ROCK 5 Model B/6CB7369717D7/UBUNTU-22.04/6.8.4-EDGE-ROCKCHIP-RK3588/AARCH64/ECCB316F36>) |
| 144d:a80d | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM9C1a (DRAM-... | 1     | nvme       | [8810771F4F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 5 Model B Rev 1.0/9ECD2EF79DB2/UBUNTU-24.04/6.8.0-1004-RASPI/AARCH64/8810771F4F>) |
| 15b7:5002 | 15b7:5002 | SanDisk          | Extreme Pro / WD Black 2018/SN750... | 1     | nvme       | [89B110C42D](<System On Chip/Radxa/ROCK/ROCK 5 Model B/5C546D75693A/FEDORA-41/6.13.0-0.RC3.32.FC41.AARCH64/AARCH64/89B110C42D>) |
| 15b7:5005 | 15b7:5005 | SanDisk          | PC SN520 x2 M.2 2242 NVMe SSD        | 1     | nvme       | [D7B1178808](<System On Chip/Rockchip/RK3566/RK3566 OPi 3B/5A028AF14393/UBUNTU-22.04/5.10.160-ROCKCHIP-RK356X/AARCH64/D7B1178808>) |
| 15b7:5008 | 15b7:5008 | SanDisk          | PC SN530 NVMe SSD (DRAM-less)        | 1     | nvme       | [A244F3FE98](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 5 Model B Rev 1.0/7907A8638CAB/DEBIAN/6.6.51+RPT-RPI-2712/AARCH64/A244F3FE98>) |
| 15b7:5015 | 15b7:5015 | Sandisk          | PC SN740 NVMe SSD (DRAM-less)        | 1     | nvme       | [9B283B5931](<System On Chip/GreatWall/Others/Others/0D3090C2B112/KYLIN-V10/5.4.18-85-GENERIC/AARCH64/9B283B5931>) |
| 15b7:5017 | 15b7:5017 | SanDisk          | WD Black SN770 / PC SN740 256GB /... | 1     | nvme       | [63A5E327FB](<System On Chip/SolidRun/LX2160A/LX2160A Clearfog CX/446971F0A5EC/UBUNTU-20.04/5.10.35-00021-G3CC6354C3606/AARCH64/63A5E327FB>) |
| 15b7:5041 | 15b7:5041 | Sandisk          | WD Blue SN580 NVMe SSD (DRAM-less)   | 1     | nvme       | [686788FE19](<System On Chip/Others/Edgepoint/Edgepoint Tactical r0.0/66EC4B2933D2/UBUNTU-20.04/5.10.120-TEGRA/AARCH64/686788FE19>) |
| 1c5c:1327 | 1c5c:0000 | SK hynix         | BC501 NVMe Solid State Drive         | 1     | nvme       | [1AD7806DF7](<System On Chip/Rockchip/RK3566/RK3566 OPi 3B/C930EE34A11F/XUBUNTU-22.04/6.6.2-EDGE-ROCKCHIP64/AARCH64/1AD7806DF7>) |
| 1c5c:1639 | 1c5c:1639 | SK hynix         | PC611 NVMe Solid State Drive         | 1     | nvme       | [2793D6EE33](<System On Chip/Pine Microsystems/Pine64/Pine64 RK3566 Quartz64-A/1B3FD4AFF349/MANJARO-ARM-24.03/6.7.9-1-MANJARO-ARM/AARCH64/2793D6EE33>) |
| 1c5c:174a | 1c5c:174a | SK hynix         | Gold P31/BC711/PC711 NVMe Solid S... | 1     | nvme       | [D8CD86DB45](<System On Chip/PINE64/Pinebook/Pinebook Pro/9912F73F6133/FEDORA-37/6.0.7-301.FC37.AARCH64/AARCH64/D8CD86DB45>) |
| 1c5c:1959 | 1c5c:1959 | SK hynix         | Platinum P41/PC801 NVMe Solid Sta... | 1     | nvme       | [C4D7255808](<System On Chip/EAECIS/DF/DF35/DB296EEDCD8A/AOSC-11.4.2/6.9.7-AOSC-MAIN/AARCH64/C4D7255808>) |
| 1cc1:5350 | 1987:5016 | ADATA Technology | XPG GAMMIX S50, S50 Lite NVMe SSD    | 1     | nvme       | [4AA2DF60B0](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 5 Model B Rev 1.0/62B51DA5A982/DEBIAN-12/6.6.28+RPT-RPI-2712/AARCH64/4AA2DF60B0>) |
| 1d79:2263 | 1d79:2263 | Transcend        | NVMe PCIe SSD 110S/112S/120S/MTE3... | 1     | nvme       | [B565B4082E](<System On Chip/Nvidia/Tegra/Tegra/70C6735F4190/UBUNTU-20.04/4.9.253-TEGRA/AARCH64/B565B4082E>) |
| 1d97:5216 | 1d97:5216 | Shenzhen Long... | FORESEE XP1000 / Lexar Profession... | 1     | nvme       | [9B332FB795](<System On Chip/Others/NVIDIA/NVIDIA Orin NX Developer Kit/7484F7AA8E66/UBUNTU-20.04/5.10.120-TEGRA/AARCH64/9B332FB795>) |
| 1d97:5216 | 1dbe:5216 | Shenzhen Long... | FORESEE XP1000 / Lexar Profession... | 1     | nvme       | [6B0861A4D4](<System On Chip/Nvidia/Tegra/Tegra/85EE9AF5177B/UBUNTU-20.04/5.10.104-TEGRA/AARCH64/6B0861A4D4>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19e5:a25a |           | Huawei Techno... | HiSilicon RDE Engine                 | 3     |            | [9C60527586](<System On Chip/Others/Others/Others/722F349D9F34/UOS-20/4.19.0-ARM64-DESKTOP/AARCH64/9C60527586>) |
| 1000:0073 | 1028:1f78 | LSI Logic / S... | MegaRAID SAS 2008 [Falcon]           | 1     | megarai... | [796C7C1066](<System On Chip/Pine Microsystems/Pine64/Pine64 RK3566 Quartz64-A/226FF315B812/MANJARO-ARM-23.02/6.6.7-1-MANJARO-ARM/AARCH64/796C7C1066>) |
| 1000:0079 | 1000:9263 | LSI Logic / S... | MegaRAID SAS 2108 [Liberator]        | 1     |            | [7C60CC0210](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.1/80605C62EBC8/DEBIAN-11/5.15.84-V8-NEUER-SCHEISS-KERNEL+/AARCH64/7C60CC0210>) |
| 8086:282a | 1462:12ed | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |

### Storage/sas (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19e5:a230 |           | Huawei Techno... | HiSilicon SAS 3.0 HBA                | 3     | hisi_sa... | [9C60527586](<System On Chip/Others/Others/Others/722F349D9F34/UOS-20/4.19.0-ARM64-DESKTOP/AARCH64/9C60527586>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19e5:a122 |           | Huawei Techno... | HiSilicon Embedded DMA Engine        | 3     | hisi_dma   | [9C60527586](<System On Chip/Others/Others/Others/722F349D9F34/UOS-20/4.19.0-ARM64-DESKTOP/AARCH64/9C60527586>) |
| 1ac1:089a | 1ac1:089a | Global Unichip   | Coral Edge TPU                       | 1     | apex       | [3EAE2BE077](<System On Chip/Others/Others/Others/38D46EBAF1C2/DEBIAN-TESTING/5.4.3-G050B21F4B394-DIRTY/AARCH64/3EAE2BE077>) |
| 8086:15e8 | 1462:12ed | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 1     | thunder... | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:1911 | 8086:2015 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1106:3483 | 1106:3483 | VIA Technologies | VL805/806 xHCI USB 3.0 Controller    | 1080  | xhci_hcd   | [A9FDC18349](<System On Chip/Others/Others/Others/E8E9F356F43D/ARCH-ROLLING/6.6.32-CWT-5.13.1-1/RISCV64/A9FDC18349>) |
| 1912:0014 |           | Renesas Techn... | uPD720201 USB 3.0 Host Controller    | 6     | xhci_hcd   | [B38B566CCA](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.1/FCBFEE94654A/DEBIAN-12/6.6.51+RPT-RPI-V8/AARCH64/B38B566CCA>) |
| 1912:0014 | ffff:ffff | Renesas Techn... | uPD720201 USB 3.0 Host Controller    | 5     | xhci_hcd   | [83F3A5DAE1](<System On Chip/GreatWall/\xe4\xb8\x96\xe6\x81\x92D80F3-GWMDDB1EL1T/\xe4\xb8\x96\xe6\x81\x92D80F3-GWMDDB1EL1T, BIOS \xe9\x95\xbf\xe5\x9f\x8eBIOS V3.0 08-01-2024/D3BAC3DE34DC/KYLIN-V10/5.4.18-110-GENERIC/AARCH64/83F3A5DAE1>) |
| 1912:0015 |           | Renesas Techn... | uPD720202 USB 3.0 Host Controller    | 3     | xhci_hcd   | [BF1D53AB19](<System On Chip/HUAWEI/W515/W515 PGUV-WBY0/A9F952C22903/KYLIN-V10/4.19.71-30-KR990/AARCH64/BF1D53AB19>) |
| 19e5:a238 |           | Huawei Techno... | HiSilicon USB 3.0 Host Controller    | 3     | xhci_pci   | [9C60527586](<System On Chip/Others/Others/Others/722F349D9F34/UOS-20/4.19.0-ARM64-DESKTOP/AARCH64/9C60527586>) |
| 19e5:a239 |           | Huawei Techno... | HiSilicon USB 2.0 2-port Host Con... | 3     | ehci_hc... | [9C60527586](<System On Chip/Others/Others/Others/722F349D9F34/UOS-20/4.19.0-ARM64-DESKTOP/AARCH64/9C60527586>) |
| 19e5:a23b |           | Huawei Techno... | HiSilicon USB 1.1 Host Controller    | 3     | ohci_hc... | [9C60527586](<System On Chip/Others/Others/Others/722F349D9F34/UOS-20/4.19.0-ARM64-DESKTOP/AARCH64/9C60527586>) |
| 1912:0015 | 19e5:3e22 | Renesas Techn... | uPD720202 USB 3.0 Host Controller    | 2     | xhci_pci   | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |
| 1b21:2142 | 1b21:2142 | ASMedia Techn... | ASM2142/ASM3142 USB 3.1 Host Cont... | 2     | xhci_hcd   | [495109C3A5](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 5 Model B Rev 1.0/C4E1BF3038E6/DEBIAN-12/6.6.51V7L-MY_CUSTOM_KERNEL+/AARCH64/495109C3A5>) |
| 1022:15b9 | 1022:15b9 | AMD              | Family 19h USB XHCI Host Controller  | 1     | xhci_pci   | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 1022:15ba | 1022:15b9 | AMD              | Family 19h USB XHCI Host Controller  | 1     | xhci_pci   | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 1022:15c0 | 1022:15c0 | AMD              | Family 19h USB XHCI Host Controller  | 1     | xhci_pci   | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 1022:15c1 | 1022:15c1 | AMD              | Family 19h USB XHCI Host Controller  | 1     | xhci_pci   | [AB7E5C672F](<System On Chip/SolidRun/Bedrock/Bedrock R7000/BA295334BDF8/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/AB7E5C672F>) |
| 8086:06ed | 1462:12ed | Intel            | Comet Lake USB 3.1 xHCI Host Cont... | 1     | xhci_pci   | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:15e9 | 1462:12ed | Intel            | JHL7540 Thunderbolt 3 USB Control... | 1     | xhci_pci   | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:9c26 | 1028:0616 | Intel            | 8 Series USB EHCI #1                 | 1     | ehci_pci   | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:9c31 | 1028:0616 | Intel            | 8 Series USB xHCI HC                 | 1     | xhci_hcd   | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:a12f | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | xhci_pci   | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 17cb:0306 | 17cb:010c | Qualcomm         | SDX55 [Snapdragon X55 5G]            | 1     | mhi        | [3DBF93245C](<System On Chip/Others/Others/Others/B78396A19CB6/UBUNTU-21.04/5.4.0-FAKED/AARCH64/3DBF93245C>) |

