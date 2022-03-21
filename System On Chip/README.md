Most popular PCI devices in System On Chips
===========================================

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in System On Chips ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Multimedia controller ](#multimedia-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Network and computing encryption device ](#network-and-computing-encryption-device-pci)
   * [ Non-vga unclassified device ](#non-vga-unclassified-device-pci)
   * [ Signal processing controller ](#signal-processing-controller-pci)
   * [ Smbus ](#smbus-pci)
   * [ Sound ](#sound-pci)
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
| 14e4:2711 |           | Broadcom         | BCM2711 PCIe Bridge                  | 636   | pcieport   | [BD24A29894](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/5AF618BB3024/MANJARO-ARM/5.15.24-1-MANJARO-ARM-RPI/AARCH64/BD24A29894>) |
| 10de:0faf | 10de:0000 | Nvidia           | PCI bridge                           | 44    | pcieport   | [904F2D4F21](<System On Chip/Nvidia/Tegra/Tegra/C04445AE216D/UBUNTU-20.04/4.9.253-TEGRA/AARCH64/904F2D4F21>) |
| 10de:0fae | 10de:0000 | Nvidia           | PCI bridge                           | 20    | pcieport   | [B2621747DB](<System On Chip/Nvidia/Tegra/Tegra/52416602189B/UBUNTU-21.04/4.9.253-TEGRA/AARCH64/B2621747DB>) |
| 10de:1ad1 |           | Nvidia           | Tegra PCIe x4/x8 Endpoint/Root Co... | 8     | pcieport   | [077899579F](<System On Chip/Nvidia/Tegra/Tegra/EBC4CC1806ED/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/077899579F>) |
| 10de:1ad0 |           | Nvidia           | Tegra PCIe x8 Endpoint               | 7     | pcieport   | [077899579F](<System On Chip/Nvidia/Tegra/Tegra/EBC4CC1806ED/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/077899579F>) |
| 16c3:abcd |           | Synopsys         | DWC_usb3 / PCIe bridge               | 4     | pcieport   | [FCDAC368CF](<System On Chip/Others/Others/Others/367A728074AC/JINGOS-20.04/4.14.133-202201191758+/AARCH64/FCDAC368CF>) |
| 1d39:8060 |           |                  | PCI bridge                           | 4     | pcieport   | [C34CD190E4](<System On Chip/T-Platforms/TF307/TF307-MB/91D084FEF1CC/ALT-10.0/5.10.93-STD-DEF-ALT1/AARCH64/C34CD190E4>) |
| 1d87:0100 |           | Fuzhou Rockch... | RK3399 PCI Express Root Port         | 4     | pcieport   | [DE559AC6D9](<System On Chip/Rockchip/Others/Others/748AF68BF4FB/UBUNTU-MATE-20.04/4.4.154-113-ROCKCHIP-GDB9DFC2CDD25/AARCH64/DE559AC6D9>) |
| 19e5:a120 | 19e5:371e | Huawei Techno... | HiSilicon PCIe Root Port with Gen4   | 3     | pcieport   | [2A8B1A08BC](<System On Chip/Others/Others/Others/CA52484FDDC1/REDFLAG-11.0/4.19.0-16-ARM64/AARCH64/2A8B1A08BC>) |
| 19e5:a121 |           | Huawei Techno... | HiSilicon PCI-PCI Bridge             | 3     | pcieport   | [2A8B1A08BC](<System On Chip/Others/Others/Others/CA52484FDDC1/REDFLAG-11.0/4.19.0-16-ARM64/AARCH64/2A8B1A08BC>) |
| 10de:1ad2 |           | Nvidia           | Tegra PCIe x1 Root Complex           | 2     | pcieport   | [A1E1FC9259](<System On Chip/Nvidia/Tegra/Tegra/565FBC48D0F2/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/A1E1FC9259>) |
| 144d:a544 |           | Samsung Elect... | Exynos 8890 PCIe Root Complex        | 2     | pcieport   | [8536DC733E](<System On Chip/Others/Others/Others/65321F980813/KALI-2021.3/3.18.140-GF49472F3951A/AARCH64/8536DC733E>) |
| 104c:8232 |           | Texas Instrum... | XIO3130 PCI Express Switch (Upstr... | 1     |            | [DE0E6691CD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/06196A934E36/DEBIAN-11/5.10.63-V8+/AARCH64/DE0E6691CD>) |
| 104c:8233 |           | Texas Instrum... | XIO3130 PCI Express Switch (Downs... | 1     |            | [DE0E6691CD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/06196A934E36/DEBIAN-11/5.10.63-V8+/AARCH64/DE0E6691CD>) |
| 11ab:0110 |           | Marvell Techn... | 88F60x0/88F70x0/88F80x0/CN913x AR... | 1     | pcieport   | [864F7FA430](<System On Chip/SolidRun/CN9132/CN9132 based COM Express type 7/255D758D69A1/UBUNTU-20.04/5.8.0/AARCH64/864F7FA430>) |
| 17cb:0104 |           | Qualcomm         | PCI bridge                           | 1     | pcieport   | [AC382F40E8](<System On Chip/Qualcomm Technologies/Open-Q/Open-Q 820 microsom/F6FEB21E1005/DEBIAN-UNSTABLE/4.14.0-QCOMLT-ARM64/AARCH64/AC382F40E8>) |
| 17cb:010b |           | Qualcomm         | PCI bridge                           | 1     | pci_msm_rc | [3DBF93245C](<System On Chip/Others/Others/Others/B78396A19CB6/UBUNTU-21.04/5.4.0-FAKED/AARCH64/3DBF93245C>) |
| 17cd:dc01 |           | Cadence Desig... | Cadence Design PCI bridge            | 1     | pcieport   | [2B4CD63D88](<System On Chip/HANWEI/FT-208/FT-208-COME-B/7D2A7DE07A62/ATZ-11.2/5.10.0-12-ARM64/AARCH64/2B4CD63D88>) |
| 17cd:dc08 |           | Cadence Desig... | Cadence Design PCI bridge            | 1     | pcieport   | [2B4CD63D88](<System On Chip/HANWEI/FT-208/FT-208-COME-B/7D2A7DE07A62/ATZ-11.2/5.10.0-12-ARM64/AARCH64/2B4CD63D88>) |
| 17cd:dc16 |           | Cadence Desig... | Cadence Design PCI bridge            | 1     | pcieport   | [2B4CD63D88](<System On Chip/HANWEI/FT-208/FT-208-COME-B/7D2A7DE07A62/ATZ-11.2/5.10.0-12-ARM64/AARCH64/2B4CD63D88>) |
| 1b21:1080 |           | ASMedia Techn... | ASM1083/1085 PCIe to PCI Bridge      | 1     |            | [7FD82B33F8](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/9656A1DE9286/RASPBIAN-10/5.10.17-V7L+/ARMV7L/7FD82B33F8>) |
| 8086:1901 | 8086:2015 | Intel            | 6th-10th Gen Core Processor PCIe ... | 1     | pcieport   | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 8086:1905 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 1     | pcieport   | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 8086:1909 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 1     | pcieport   | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 8086:5910 | 8086:2015 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 1     | skl_uncore | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 8086:a118 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | pcieport   | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 8086:a153 | 8086:7270 | Intel            | QM175 Chipset LPC/eSPI Controller    | 1     |            | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a13a | 8086:1999 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | mei_me     | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1002:6611 | 1642:1869 | AMD              | Oland [Radeon HD 8570 / R5 430 OE... | 1     | radeon     | [BD05C84564](<System On Chip/HUAWEI/W510/W510 PGU-WBY0/5583E74879DC/UBUNTU-21.04/5.8.0-36-GENERIC/AARCH64/BD05C84564>) |
| 1002:6611 | 1642:1871 | AMD              | Oland [Radeon HD 8570 / R5 430 OE... | 1     | radeon     | [CBD268B858](<System On Chip/Others/Others/Others/799870895E60/UBUNTU-20.10/5.8.0-31-GENERIC/AARCH64/CBD268B858>) |
| 1002:6779 | 1787:2300 | AMD              | Caicos [Radeon HD 6450/7450/8450 ... | 1     | radeon     | [2B4CD63D88](<System On Chip/HANWEI/FT-208/FT-208-COME-B/7D2A7DE07A62/ATZ-11.2/5.10.0-12-ARM64/AARCH64/2B4CD63D88>) |
| 1002:67ff | 1002:0b04 | AMD              | Baffin [Radeon RX 550 640SP / RX ... | 1     | amdgpu     | [2A8B1A08BC](<System On Chip/Others/Others/Others/CA52484FDDC1/REDFLAG-11.0/4.19.0-16-ARM64/AARCH64/2A8B1A08BC>) |
| 8086:591b | 8086:2015 | Intel            | HD Graphics 630                      | 1     | i915       | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10cf:2049 | 13fe:8701 | Fujitsu Limited. | Fujitsu Multimedia controller        | 1     |            | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 13fe:0059 | 13fe:0059 | Advantech        | Multimedia controller                | 1     |            | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:8168 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 28    | r8168      | [904F2D4F21](<System On Chip/Nvidia/Tegra/Tegra/C04445AE216D/UBUNTU-20.04/4.9.253-TEGRA/AARCH64/904F2D4F21>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 17    | r8168      | [A938BBD87F](<System On Chip/Nvidia/Tegra/Tegra/7A6746DEFE47/UBUNTU-18.04/4.9.201-TEGRA/AARCH64/A938BBD87F>) |
| 19e5:a222 |           | Huawei Techno... | HNS GE/10GE/25GE RDMA Network Con... | 2     | hns3       | [2A8B1A08BC](<System On Chip/Others/Others/Others/CA52484FDDC1/REDFLAG-11.0/4.19.0-16-ARM64/AARCH64/2A8B1A08BC>) |
| 10ec:8161 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | r8168      | [DE0E6691CD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/06196A934E36/DEBIAN-11/5.10.63-V8+/AARCH64/DE0E6691CD>) |
| 19e5:a221 | 19e5:0000 | Huawei Techno... | HNS GE/10GE/25GE Network Controller  | 1     | hclge, ... | [CBD268B858](<System On Chip/Others/Others/Others/799870895E60/UBUNTU-20.10/5.8.0-31-GENERIC/AARCH64/CBD268B858>) |
| 19e5:a222 | 19e5:0000 | Huawei Techno... | HNS GE/10GE/25GE RDMA Network Con... | 1     | hclge, ... | [CBD268B858](<System On Chip/Others/Others/Others/799870895E60/UBUNTU-20.10/5.8.0-31-GENERIC/AARCH64/CBD268B858>) |
| 8086:1572 | 8086:0000 | Intel            | Ethernet Controller X710 for 10Gb... | 1     | i40e       | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 8086:15b7 | 8086:0000 | Intel            | Ethernet Connection (2) I219-LM      | 1     | e1000e     | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:24fd | 8086:1010 | Intel            | Wireless 8265 / 8275                 | 7     | iwlwifi    | [CF8601E4F0](<System On Chip/Nvidia/Tegra/Tegra/2B3775F7B28D/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/CF8601E4F0>) |
| 10ec:c822 | 1a3b:3751 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 6     | rtl8822ce  | [077899579F](<System On Chip/Nvidia/Tegra/Tegra/EBC4CC1806ED/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/077899579F>) |
| 14e4:4415 | 14e4:0751 | Broadcom         | BCM4359 802.11ac Dual-Band Wirele... | 2     | pcieh      | [8536DC733E](<System On Chip/Others/Others/Others/65321F980813/KALI-2021.3/3.18.140-GF49472F3951A/AARCH64/8536DC733E>) |
| 8086:24fd | 8086:0010 | Intel            | Wireless 8265 / 8275                 | 2     | iwlwifi    | [54592EC1A2](<System On Chip/Nvidia/Tegra/Tegra/54129FFCE65C/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/54592EC1A2>) |
| 8086:24fd | 8086:1130 | Intel            | Wireless 8265 / 8275                 | 2     | iwlwifi    | [BE96BBE4F4](<System On Chip/Nvidia/Tegra/Tegra/1F5B34B20D8B/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/BE96BBE4F4>) |
| 10ec:b822 | 103c:831b | Realtek Semic... | RTL8822BE 802.11a/b/g/n/ac WiFi a... | 1     | rtwpci     | [1B215DD48C](<System On Chip/Nvidia/Jetson/Jetson Nano Developer Kit/58DEF6B21363/UBUNTU-20.04/5.5.5/AARCH64/1B215DD48C>) |
| 10ec:c822 | 1a3b:3750 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 1     | rtl8822ce  | [DB3EB249A1](<System On Chip/Nvidia/Tegra/Tegra/A2D34F7D05EB/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/DB3EB249A1>) |
| 168c:002a | 10cf:147c | Qualcomm Atheros | AR928X Wireless Network Adapter (... | 1     | ath9k      | [ECDDEDCFB7](<System On Chip/Nvidia/Tegra/Tegra/E867D231D0C0/UBUNTU-18.04/4.9.201-TEGRA/AARCH64/ECDDEDCFB7>) |
| 168c:003e |           | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 1     | ath10k_pci | [AC382F40E8](<System On Chip/Qualcomm Technologies/Open-Q/Open-Q 820 microsom/F6FEB21E1005/DEBIAN-UNSTABLE/4.14.0-QCOMLT-ARM64/AARCH64/AC382F40E8>) |
| 168c:0042 | 11ad:1806 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 1     | ath10k_pci | [5E682A0733](<System On Chip/Nvidia/Tegra/Tegra/A1DD672248E9/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/5E682A0733>) |
| 168c:0042 | 17aa:0901 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 1     | ath10k_pci | [B2621747DB](<System On Chip/Nvidia/Tegra/Tegra/52416602189B/UBUNTU-21.04/4.9.253-TEGRA/AARCH64/B2621747DB>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 1     | iwlwifi    | [C72F8C76F7](<System On Chip/Nvidia/Tegra/Tegra/B2307FE84F73/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/C72F8C76F7>) |
| 8086:2725 | 8086:0024 | Intel            | Wi-Fi 6 AX210/AX211/AX411 160MHz     | 1     |            | [1CCD6EEE0E](<System On Chip/Nvidia/Jetson/Jetson Nano Developer Kit/6563B51893AF/UBUNTU-21.04/5.12.6-JETSON-NANO/AARCH64/1CCD6EEE0E>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1db3:2355 |           |                  | Network controller                   | 2     | wcn_pcie   | [FCDAC368CF](<System On Chip/Others/Others/Others/367A728074AC/JINGOS-20.04/4.14.133-202201191758+/AARCH64/FCDAC368CF>) |
| 8086:10d3 | 8086:a01f | Intel            | 82574L Gigabit Network Connection    | 1     | e1000e     | [AC382F40E8](<System On Chip/Qualcomm Technologies/Open-Q/Open-Q 820 microsom/F6FEB21E1005/DEBIAN-UNSTABLE/4.14.0-QCOMLT-ARM64/AARCH64/AC382F40E8>) |
| 8086:1531 | 8086:0000 | Intel            | I210 Gigabit Unprogrammed            | 1     | igb        | [D48FD712A5](<System On Chip/Nvidia/Tegra/Tegra/A6096A1A9829/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/D48FD712A5>) |
| 8086:1533 | ffff:0000 | Intel            | I210 Gigabit Network Connection      | 1     | igb        | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Network and computing encryption device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19e5:a255 |           | Huawei Techno... | HiSilicon SEC Engine                 | 1     | hisi_sec2  | [BD05C84564](<System On Chip/HUAWEI/W510/W510 PGU-WBY0/5583E74879DC/UBUNTU-21.04/5.8.0-36-GENERIC/AARCH64/BD05C84564>) |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a124 |           | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a131 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | intel_p... | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a123 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | i2c_i801   | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1002:aab0 | 1642:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 2     | snd_hda... | [BD05C84564](<System On Chip/HUAWEI/W510/W510 PGU-WBY0/5583E74879DC/UBUNTU-21.04/5.8.0-36-GENERIC/AARCH64/BD05C84564>) |
| 1002:aa98 | 1787:aa98 | AMD              | Caicos HDMI Audio [Radeon HD 6450... | 1     | snd_hda... | [2B4CD63D88](<System On Chip/HANWEI/FT-208/FT-208-COME-B/7D2A7DE07A62/ATZ-11.2/5.10.0-12-ARM64/AARCH64/2B4CD63D88>) |
| 1002:aae0 | 1002:aae0 | AMD              | Baffin HDMI/DP Audio [Radeon RX 5... | 1     | snd_hda... | [2A8B1A08BC](<System On Chip/Others/Others/Others/CA52484FDDC1/REDFLAG-11.0/4.19.0-16-ARM64/AARCH64/2A8B1A08BC>) |
| 13f6:0111 | 13f6:0111 | C-Media Elect... | CMI8738/CMI8768 PCI Audio            | 1     |            | [7FD82B33F8](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/9656A1DE9286/RASPBIAN-10/5.10.17-V7L+/ARMV7L/7FD82B33F8>) |
| 8086:a171 | 8086:7270 | Intel            | CM238 HD Audio Controller            | 1     | snd_hda... | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19e5:a235 |           | Huawei Techno... | HiSilicon AHCI HBA                   | 3     | ahci       | [2A8B1A08BC](<System On Chip/Others/Others/Others/CA52484FDDC1/REDFLAG-11.0/4.19.0-16-ARM64/AARCH64/2A8B1A08BC>) |
| 1b4b:9171 | 1b4b:9171 | Marvell Techn... | 88SE9171 SATA 6G Controller          | 2     | ahci       | [A1E1FC9259](<System On Chip/Nvidia/Tegra/Tegra/565FBC48D0F2/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/A1E1FC9259>) |
| 1b4b:9215 | 1b4b:9215 | Marvell Techn... | 88SE9215 PCIe 2.0 x1 4-port SATA ... | 2     | ahci       | [2B4CD63D88](<System On Chip/HANWEI/FT-208/FT-208-COME-B/7D2A7DE07A62/ATZ-11.2/5.10.0-12-ARM64/AARCH64/2B4CD63D88>) |
| 197b:0585 | 197b:0000 | JMicron Techn... | JMB58x AHCI SATA controller          | 1     | ahci       | [33C6248333](<System On Chip/Kobol/Helios/Helios64/D26FB437FFE3/DEBIAN-11/5.10.35-ROCKCHIP64/AARCH64/33C6248333>) |
| 1b4b:9183 | 1b4b:9183 | Marvell Techn... | 88SS9183 PCIe SSD Controller         | 1     |            | [5E07806B7E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi ? Rev 1.0/D8FBFD41D06C/UBUNTU-20.04/5.4.0-1015-RASPI/AARCH64/5E07806B7E>) |
| 1b4b:9230 | 1b4b:9230 | Marvell Techn... | 88SE9230 PCIe 2.0 x2 4-port SATA ... | 1     | ahci       | [4B04BE2436](<System On Chip/Rockchip/Others/Others/F590D4D52D83/UBUNTU-20.04/4.4.154-113-ROCKCHIP-GDB9DFC2CDD25/AARCH64/4B04BE2436>) |
| 8086:a103 | 8086:7270 | Intel            | HM170/QM170 Chipset SATA Controll... | 1     | ahci       | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 197b:2363 | 197b:2363 | JMicron Techn... | JMB363 SATA/IDE Controller           | 1     | ahci       | [7DDF0DB7EC](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/7C8C1F01A3C3/UBUNTU-21.10/5.13.0-1010-RASPI/AARCH64/7DDF0DB7EC>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 5     | nvme       | [C34CD190E4](<System On Chip/T-Platforms/TF307/TF307-MB/91D084FEF1CC/ALT-10.0/5.10.93-STD-DEF-ALT1/AARCH64/C34CD190E4>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT SSD Controller     | 2     | nvme       | [87CF7F053C](<System On Chip/Nvidia/Tegra/Tegra/E271192D27D5/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/87CF7F053C>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 2     | nvme       | [A1512911DF](<System On Chip/Khadas/VIM/VIM3/8E76D129C324/UBUNTU-20.04/4.9.241/AARCH64/A1512911DF>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 1     | nvme       | [DE559AC6D9](<System On Chip/Rockchip/Others/Others/748AF68BF4FB/UBUNTU-MATE-20.04/4.4.154-113-ROCKCHIP-GDB9DFC2CDD25/AARCH64/DE559AC6D9>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 1     | nvme       | [0965D05FE6](<System On Chip/Nvidia/Tegra/Tegra/90823179FECD/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/0965D05FE6>) |
| 15b7:5009 | 15b7:5009 | Sandisk          | WD Blue SN550 NVMe SSD               | 1     | nvme       | [077899579F](<System On Chip/Nvidia/Tegra/Tegra/EBC4CC1806ED/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/077899579F>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013 E13 NVMe Controller           | 1     | nvme       | [14BC5C234D](<System On Chip/Khadas/VIM/VIM3/AD2E7941E7E9/XUBUNTU-20.04/4.9.241/AARCH64/14BC5C234D>) |
| 1c5c:174a | 1c5c:174a | SK Hynix         | Gold P31 SSD                         | 1     | nvme       | [BF8ABDFB09](<System On Chip/Others/Unknown/Unknown Product/4BE11779C833/FEDORA-35/5.14.9-300.FC35.AARCH64/AARCH64/BF8ABDFB09>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 1     | nvme       | [DF2CCD3ED4](<System On Chip/Nvidia/Tegra/Tegra/216EBFEFA071/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/DF2CCD3ED4>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19e5:a25a |           | Huawei Techno... | HiSilicon RDE Engine                 | 3     |            | [2A8B1A08BC](<System On Chip/Others/Others/Others/CA52484FDDC1/REDFLAG-11.0/4.19.0-16-ARM64/AARCH64/2A8B1A08BC>) |

### Storage/sas (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19e5:a230 |           | Huawei Techno... | HiSilicon SAS 3.0 HBA                | 3     | hisi_sa... | [2A8B1A08BC](<System On Chip/Others/Others/Others/CA52484FDDC1/REDFLAG-11.0/4.19.0-16-ARM64/AARCH64/2A8B1A08BC>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19e5:a122 |           | Huawei Techno... | HiSilicon Embedded DMA Engine        | 3     | hisi_dma   | [2A8B1A08BC](<System On Chip/Others/Others/Others/CA52484FDDC1/REDFLAG-11.0/4.19.0-16-ARM64/AARCH64/2A8B1A08BC>) |
| 8086:1911 | 8086:2015 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1106:3483 | 1106:3483 | VIA Technologies | VL805/806 xHCI USB 3.0 Controller    | 631   | xhci_pci   | [BD24A29894](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/5AF618BB3024/MANJARO-ARM/5.15.24-1-MANJARO-ARM-RPI/AARCH64/BD24A29894>) |
| 19e5:a238 |           | Huawei Techno... | HiSilicon USB 3.0 Host Controller    | 3     | xhci_pci   | [2A8B1A08BC](<System On Chip/Others/Others/Others/CA52484FDDC1/REDFLAG-11.0/4.19.0-16-ARM64/AARCH64/2A8B1A08BC>) |
| 19e5:a239 |           | Huawei Techno... | HiSilicon USB 2.0 2-port Host Con... | 3     | ehci_pci   | [2A8B1A08BC](<System On Chip/Others/Others/Others/CA52484FDDC1/REDFLAG-11.0/4.19.0-16-ARM64/AARCH64/2A8B1A08BC>) |
| 19e5:a23b |           | Huawei Techno... | HiSilicon USB 1.1 Host Controller    | 3     | ohci_pci   | [2A8B1A08BC](<System On Chip/Others/Others/Others/CA52484FDDC1/REDFLAG-11.0/4.19.0-16-ARM64/AARCH64/2A8B1A08BC>) |
| 1912:0014 |           | Renesas Techn... | uPD720201 USB 3.0 Host Controller    | 1     | xhci_pci   | [2B4CD63D88](<System On Chip/HANWEI/FT-208/FT-208-COME-B/7D2A7DE07A62/ATZ-11.2/5.10.0-12-ARM64/AARCH64/2B4CD63D88>) |
| 1912:0015 | 19e5:3e22 | Renesas Techn... | uPD720202 USB 3.0 Host Controller    | 1     | xhci_pci   | [BD05C84564](<System On Chip/HUAWEI/W510/W510 PGU-WBY0/5583E74879DC/UBUNTU-21.04/5.8.0-36-GENERIC/AARCH64/BD05C84564>) |
| 8086:a12f | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | xhci_pci   | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 17cb:0306 | 17cb:010c | Qualcomm         |                                      | 1     | mhi        | [3DBF93245C](<System On Chip/Others/Others/Others/B78396A19CB6/UBUNTU-21.04/5.4.0-FAKED/AARCH64/3DBF93245C>) |
| 17cb:1101 | 17cb:0108 | Qualcomm         | QCA6390 Wireless Network Adapter ... | 1     | cnss_pci   | [3DBF93245C](<System On Chip/Others/Others/Others/B78396A19CB6/UBUNTU-21.04/5.4.0-FAKED/AARCH64/3DBF93245C>) |

