Most popular PCI devices in System On Chips
-------------------------------------------

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in System On Chips ](#pci-devices)
   * [ Bluetooth ](#bluetooth-pci)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Multimedia controller ](#multimedia-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Network and computing encryption device ](#network-and-computing-encryption-device-pci)
   * [ Non-vga unclassified device ](#non-vga-unclassified-device-pci)
   * [ Serial bus controller ](#serial-bus-controller-pci)
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

### Bluetooth (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14c3:8650 | 14c3:8650 | MediaTek         | Bluetooth                            | 1     |            | [5D664BE928](<System On Chip/Others/Others/Others/C58CA0A5CE09/OPENWRT-21.02.3/5.4.188/MIPS/5D664BE928>) |

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14e4:2711 |           | Broadcom         | BCM2711 PCIe Bridge                  | 891   | pcieport   | [F045323C99](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/DFF914D5971F/RASPBIAN-11/6.1.25-V8+/AARCH64/F045323C99>) |
| 10de:0faf | 10de:0000 | Nvidia           | PCI bridge                           | 54    | pcieport   | [1378D303E3](<System On Chip/Nvidia/Tegra/Tegra/E1CEE4DBB7F5/UBUNTU-20.04/4.9.253-TEGRA/AARCH64/1378D303E3>) |
| 10de:0fae | 10de:0000 | Nvidia           | PCI bridge                           | 20    | pcieport   | [CFEB6FB78F](<System On Chip/Nvidia/Tegra/Tegra/52416602189B/UBUNTU-UNITY-18.04/4.9.253-TEGRA/AARCH64/CFEB6FB78F>) |
| 10de:1ad0 |           | Nvidia           | Tegra PCIe x8 Endpoint               | 12    | pcieport   | [68AC87675A](<System On Chip/Nvidia/Tegra/Tegra/DBB28DEA9F16/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/68AC87675A>) |
| 10de:1ad1 |           | Nvidia           | Tegra PCIe x4/x8 Endpoint/Root Co... | 11    | pcieport   | [B05FAAC149](<System On Chip/Others/NVIDIA/NVIDIA Jetson Xavier NX Developer Kit/FF85D7E95ADF/UBUNTU-20.04/5.10.104-TEGRA/AARCH64/B05FAAC149>) |
| 1d87:3588 |           | Rockchip Elec... | RK3588                               | 11    | pcieport   | [EB774628AF](<System On Chip/Rockchip/Orange/Orange Pi 5/AD034DE2F584/UBUNTU-22.04/5.10.110-ROCKCHIP-RK3588/AARCH64/EB774628AF>) |
| 1d87:0100 |           | Fuzhou Rockch... | RK3399 PCI Express Root Port         | 8     | pcieport   | [4382F0CCE7](<System On Chip/Radxa/ROCK/ROCK Pi 4B/57E79905A598/XUBUNTU-22.04/5.15.93-ROCKCHIP64/AARCH64/4382F0CCE7>) |
| 1d87:3566 |           | Rockchip Elec... | RK3568 Remote Signal Processor       | 8     | pcieport   | [E5FF381254](<System On Chip/Others/Others/Others/7493A90DF8F3/DEBIAN-11/6.2.9/AARCH64/E5FF381254>) |
| 16c3:abcd |           | Synopsys         | DWC_usb3 / PCIe bridge               | 7     | pcieport   | [3EAE2BE077](<System On Chip/Others/Others/Others/38D46EBAF1C2/DEBIAN-TESTING/5.4.3-G050B21F4B394-DIRTY/AARCH64/3EAE2BE077>) |
| 1d39:8060 |           | Baikal Electr... | PCI bridge                           | 6     | pcieport   | [018EB0B0BB](<System On Chip/NCI/PC/PC BLICK101/3CFE875BAE08/RED-OS-7.3/5.4.197-1.EL7.AARCH64/AARCH64/018EB0B0BB>) |
| 1556:1111 |           | PLDA             | XpressRich-AXI Ref Design            | 3     | pcieport   | [043C078CAF](<System On Chip/Others/Others/Others/678CF1D282D3/DEBIAN-12/5.15.0-STARFIVE/RISCV64/043C078CAF>) |
| 17cd:dc01 |           | Cadence Desig... | Cadence Design PCI bridge            | 3     | pcieport   | [5A3CB266DB](<System On Chip/GreatWall/DF/DF/5813E68F06D1/DEBIAN-11/5.10.0-22-ARM64/AARCH64/5A3CB266DB>) |
| 17cd:dc08 |           | Cadence Desig... | Cadence Design PCI bridge            | 3     | pcieport   | [5A3CB266DB](<System On Chip/GreatWall/DF/DF/5813E68F06D1/DEBIAN-11/5.10.0-22-ARM64/AARCH64/5A3CB266DB>) |
| 17cd:dc16 |           | Cadence Desig... | Cadence Design PCI bridge            | 3     | pcieport   | [5A3CB266DB](<System On Chip/GreatWall/DF/DF/5813E68F06D1/DEBIAN-11/5.10.0-22-ARM64/AARCH64/5A3CB266DB>) |
| 10de:1ad2 |           | Nvidia           | Tegra PCIe x1 Root Complex           | 2     | pcieport   | [A1E1FC9259](<System On Chip/Nvidia/Tegra/Tegra/565FBC48D0F2/UBUNTU-UNITY-18.04/4.9.140-TEGRA/AARCH64/A1E1FC9259>) |
| 144d:a544 |           | Samsung Elect... | Exynos 8890 PCIe Root Complex        | 2     | pcieport   | [8536DC733E](<System On Chip/Others/Others/Others/65321F980813/KALI-2021.3/3.18.140-GF49472F3951A/AARCH64/8536DC733E>) |
| 17cb:010b |           | Qualcomm         | PCI bridge                           | 2     | pci_msm_rc | [F3B7AB67BC](<System On Chip/Others/Others/Others/BADA157665F2/KALI-2022.2/4.19.113-23222000/AARCH64/F3B7AB67BC>) |
| 19e5:a120 | 19e5:371e | Huawei Techno... | HiSilicon PCIe Root Port with Gen4   | 2     | pcieport   | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |
| 19e5:a121 |           | Huawei Techno... | HiSilicon PCI-PCI Bridge             | 2     | pcieport   | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |
| 104c:8232 |           | Texas Instrum... | XIO3130 PCI Express Switch (Upstr... | 1     |            | [DE0E6691CD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.0/06196A934E36/DEBIAN-11/5.10.63-V8+/AARCH64/DE0E6691CD>) |
| 104c:8233 |           | Texas Instrum... | XIO3130 PCI Express Switch (Downs... | 1     |            | [DE0E6691CD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.0/06196A934E36/DEBIAN-11/5.10.63-V8+/AARCH64/DE0E6691CD>) |
| 10de:229e |           | Nvidia           | PCI bridge                           | 1     | pcieport   | [08B3F5414E](<System On Chip/Nvidia/Tegra/Tegra/3D43A83DC6B6/UBUNTU-20.04/5.10.65-TEGRA/AARCH64/08B3F5414E>) |
| 11ab:0110 |           | Marvell Techn... | 88F60x0/88F70x0/88F80x0/CN913x AR... | 1     | pcieport   | [864F7FA430](<System On Chip/SolidRun/CN9132/CN9132 based COM Express type 7/255D758D69A1/UBUNTU-20.04/5.8.0/AARCH64/864F7FA430>) |
| 144d:ecec |           | Samsung Elect... | Exynos 8895 PCIe Root Complex        | 1     | pcieport   | [61D82AF735](<System On Chip/Others/Others/Others/6555EFD46738/KALI-2023.1/5.10.107-ANDROID13-4-00004-G6522BF85D262-AB8935228/AARCH64/61D82AF735>) |
| 144d:eced |           | Samsung Elect... | Electronics PCI bridge               | 1     | pcieport   | [61D82AF735](<System On Chip/Others/Others/Others/6555EFD46738/KALI-2023.1/5.10.107-ANDROID13-4-00004-G6522BF85D262-AB8935228/AARCH64/61D82AF735>) |
| 17cb:0104 |           | Qualcomm         | PCI bridge                           | 1     | pcieport   | [AC382F40E8](<System On Chip/Qualcomm Technologies/Open-Q/Open-Q 820 microsom/F6FEB21E1005/DEBIAN-UNSTABLE/4.14.0-QCOMLT-ARM64/AARCH64/AC382F40E8>) |
| 1814:0801 |           | Ralink           | PCI bridge                           | 1     |            | [5D664BE928](<System On Chip/Others/Others/Others/C58CA0A5CE09/OPENWRT-21.02.3/5.4.188/MIPS/5D664BE928>) |
| 1957:8d80 |           | Freescale Sem... | Freescale PCI bridge                 | 1     | pcieport   | [63A5E327FB](<System On Chip/SolidRun/LX2160A/LX2160A Clearfog CX/446971F0A5EC/UBUNTU-20.04/5.10.35-00021-G3CC6354C3606/AARCH64/63A5E327FB>) |
| 1b21:1080 |           | ASMedia Techn... | ASM1083/1085 PCIe to PCI Bridge      | 1     |            | [7FD82B33F8](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.0/9656A1DE9286/RASPBIAN-10/5.10.17-V7L+/ARMV7L/7FD82B33F8>) |
| 1b21:1182 | 1b21:118f | ASMedia Techn... | ASM1182e 2-Port PCIe x1 Gen2 Pack... | 1     | pcieport   | [6E70632A8C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.0/1EAFE8609AE7/RASPBIAN-10/5.10.63-V7L/ARMV7L/6E70632A8C>) |
| 1b21:1806 |           | ASMedia Techn... | PCI bridge                           | 1     | pcieport   | [B05FAAC149](<System On Chip/Others/NVIDIA/NVIDIA Jetson Xavier NX Developer Kit/FF85D7E95ADF/UBUNTU-20.04/5.10.104-TEGRA/AARCH64/B05FAAC149>) |
| 8086:068d | 1462:12ed | Intel            | Comet Lake LPC Controller            | 1     |            | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:06b6 | 1462:12ed | Intel            | 400 Series Chipset Family PCIe Po... | 1     | pcieport   | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:06c0 | 1462:12ed | Intel            | Comet Lake PCI Express Root Port #17 | 1     | pcieport   | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:0a04 | 1028:0616 | Intel            | Haswell-ULT DRAM Controller          | 1     | hsw_uncore | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:15e7 | 1462:12ed | Intel            | JHL7540 Thunderbolt 3 Bridge [Tit... | 1     | pcieport   | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:1901 | 1462:12ed | Intel            | 6th-10th Gen Core Processor PCIe ... | 1     | pcieport   | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:1901 | 8086:2015 | Intel            | 6th-10th Gen Core Processor PCIe ... | 1     | pcieport   | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 8086:1905 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 1     | pcieport   | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 8086:1909 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 1     | pcieport   | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 8086:5910 | 8086:2015 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 1     | skl_uncore | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 8086:9b44 | 1462:12ed | Intel            | 10th Gen Core Processor Host Brid... | 1     | skl_uncore | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:9c10 | 1028:0616 | Intel            | 8 Series PCI Express Root Port 1     | 1     | pcieport   | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:9c12 | 1028:0616 | Intel            | 8 Series PCI Express Root Port 2     | 1     | pcieport   | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:9c14 | 1028:0616 | Intel            | 8 Series PCI Express Root Port 3     | 1     | pcieport   | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:9c16 | 1028:0616 | Intel            | 8 Series PCI Express Root Port 4     | 1     | pcieport   | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:9c18 | 1028:0616 | Intel            | 8 Series PCI Express Root Port 5     | 1     | pcieport   | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:9c43 | 1028:0616 | Intel            | 8 Series LPC Controller              | 1     | lpc_ich    | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:a118 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | pcieport   | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 8086:a153 | 8086:7270 | Intel            | QM175 Chipset LPC/eSPI Controller    | 1     |            | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:5227 | 1028:0616 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 1     | rtsx_pci   | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:06e0 | 1462:12ed | Intel            | Comet Lake HECI Controller           | 1     | mei_me     | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:9c3a | 1028:0616 | Intel            | 8 Series HECI #0                     | 1     | mei_me     | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:a13a | 8086:1999 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | mei_me     | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1002:6611 | 1642:1869 | AMD              | Oland [Radeon HD 8570 / R5 430 OE... | 1     | radeon     | [3F3D475864](<System On Chip/HUAWEI/PGU-WBY/PGU-WBY0/1C58824AF241/DEBIAN-11/5.10.0-18-ARM64/AARCH64/3F3D475864>) |
| 1002:6611 | 1642:1871 | AMD              | Oland [Radeon HD 8570 / R5 430 OE... | 1     | radeon     | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |
| 1002:6611 | 174b:d340 | AMD              | Oland [Radeon HD 8570 / R5 430 OE... | 1     | radeon     | [B8EA59E9F8](<System On Chip/Inspur/CE520/CE520F/3A556DC2B09D/DEBIAN-11/5.10.0-18-ARM64/AARCH64/B8EA59E9F8>) |
| 1002:6779 | 1787:2300 | AMD              | Caicos [Radeon HD 6450/7450/8450 ... | 1     | radeon     | [2B4CD63D88](<System On Chip/HANWEI/FT-208/FT-208-COME-B/7D2A7DE07A62/ATZ-11.2/5.10.0-12-ARM64/AARCH64/2B4CD63D88>) |
| 1002:67ff | 1849:5037 | AMD              | Baffin [Radeon RX 550 640SP / RX ... | 1     | amdgpu     | [63A5E327FB](<System On Chip/SolidRun/LX2160A/LX2160A Clearfog CX/446971F0A5EC/UBUNTU-20.04/5.10.35-00021-G3CC6354C3606/AARCH64/63A5E327FB>) |
| 1002:699f | 1642:1865 | AMD              | Lexa PRO [Radeon 540/540X/550/550... | 1     | amdgpu     | [5A3CB266DB](<System On Chip/GreatWall/DF/DF/5813E68F06D1/DEBIAN-11/5.10.0-22-ARM64/AARCH64/5A3CB266DB>) |
| 10de:249d | 1462:12ed | Nvidia           | GA104M [GeForce RTX 3070 Mobile /... | 1     |            | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:0a16 | 1028:0616 | Intel            | Haswell-ULT Integrated Graphics C... | 1     | i915       | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:591b | 8086:2015 | Intel            | HD Graphics 630                      | 1     | i915       | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 8086:9bc4 | 1462:12ed | Intel            | CometLake-H GT2 [UHD Graphics]       | 1     | i915       | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ee:7024 | 10ee:0007 | Xilinx           | Memory controller                    | 1     | alphase... | [B565B4082E](<System On Chip/Nvidia/Tegra/Tegra/70C6735F4190/UBUNTU-20.04/4.9.253-TEGRA/AARCH64/B565B4082E>) |
| 8086:06ef | 8086:7270 | Intel            | Comet Lake PCH Shared SRAM           | 1     |            | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10cf:2049 | 13fe:8701 | Fujitsu Limited. | Fujitsu Multimedia controller        | 1     |            | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 13fe:0059 | 13fe:0059 | Advantech        | Multimedia controller                | 1     |            | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 544d:6178 | 6903:0020 | TBS Technologies | DVB Tuner PCIe Card                  | 1     |            | [6E70632A8C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.0/1EAFE8609AE7/RASPBIAN-10/5.10.63-V7L/ARMV7L/6E70632A8C>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:8168 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 35    | r8168      | [1378D303E3](<System On Chip/Nvidia/Tegra/Tegra/E1CEE4DBB7F5/UBUNTU-20.04/4.9.253-TEGRA/AARCH64/1378D303E3>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 19    | r8168      | [5A3CB266DB](<System On Chip/GreatWall/DF/DF/5813E68F06D1/DEBIAN-11/5.10.0-22-ARM64/AARCH64/5A3CB266DB>) |
| 19e5:a222 |           | Huawei Techno... | HNS GE/10GE/25GE RDMA Network Con... | 2     | hclge, ... | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |
| 10ec:8125 | 10ec:8125 | Realtek Semic... | RTL8125 2.5GbE Controller            | 1     | r8125      | [D864D2A31B](<System On Chip/Radxa/ROCK/ROCK 5B/E26E78D5BB08/KUBUNTU-20.04/5.10.66-27-ROCKCHIP-GEA60D388902D/AARCH64/D864D2A31B>) |
| 10ec:8161 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | r8168      | [DE0E6691CD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.0/06196A934E36/DEBIAN-11/5.10.63-V8+/AARCH64/DE0E6691CD>) |
| 10ec:8168 | 1028:0616 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | r8169      | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:1572 | 8086:0000 | Intel            | Ethernet Controller X710 for 10Gb... | 1     | i40e       | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 8086:15b7 | 8086:0000 | Intel            | Ethernet Connection (2) I219-LM      | 1     | e1000e     | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |
| 8086:3101 | 8086:0000 | Intel            | Killer E3100X 2.5 Gigabit Etherne... | 1     | igc        | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:c822 | 1a3b:3751 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 8     | rtl8822ce  | [08B3F5414E](<System On Chip/Nvidia/Tegra/Tegra/3D43A83DC6B6/UBUNTU-20.04/5.10.65-TEGRA/AARCH64/08B3F5414E>) |
| 8086:24fd | 8086:1010 | Intel            | Wireless 8265 / 8275                 | 8     | iwlwifi    | [4D32910C65](<System On Chip/Nvidia/Tegra/Tegra/CC41B2AA6D5B/UBUNTU-UNITY-18.04/4.9.140-TEGRA/AARCH64/4D32910C65>) |
| 14e4:43ec | 14e4:0000 | Broadcom         | BCM4356 802.11ac Wireless Network... | 2     | brcmfmac   | [6A3439A8E1](<System On Chip/Others/Others/Others/FDF2652907A7/UBUNTU-18.04/4.9.140-L4T/AARCH64/6A3439A8E1>) |
| 14e4:4415 | 14e4:0751 | Broadcom         | BCM4359 802.11ac Dual-Band Wirele... | 2     | pcieh      | [8536DC733E](<System On Chip/Others/Others/Others/65321F980813/KALI-2021.3/3.18.140-GF49472F3951A/AARCH64/8536DC733E>) |
| 8086:24fd | 8086:0010 | Intel            | Wireless 8265 / 8275                 | 2     | iwlwifi    | [54592EC1A2](<System On Chip/Nvidia/Tegra/Tegra/54129FFCE65C/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/54592EC1A2>) |
| 8086:24fd | 8086:1130 | Intel            | Wireless 8265 / 8275                 | 2     | iwlwifi    | [BE96BBE4F4](<System On Chip/Nvidia/Tegra/Tegra/1F5B34B20D8B/UBUNTU-UNITY-18.04/4.9.140-TEGRA/AARCH64/BE96BBE4F4>) |
| 8086:2723 | 8086:0084 | Intel            | Wi-Fi 6 AX200                        | 2     | iwlwifi    | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |
| 8086:2725 | 8086:0024 | Intel            | Wi-Fi 6 AX210/AX211/AX411 160MHz     | 2     | iwlwifi    | [8E2855140C](<System On Chip/Pine Microsystems/Pine64/Pine64 RK3566 Quartz64-A/0B7E187F6FBF/MANJARO-ARM-22.07/5.19.0-RC7-1-MANJARO-ARM-RC/AARCH64/8E2855140C>) |
| 10ec:b822 | 103c:831b | Realtek Semic... | RTL8822BE 802.11a/b/g/n/ac WiFi a... | 1     | rtwpci     | [1B215DD48C](<System On Chip/Nvidia/Jetson/Jetson Nano Developer Kit/58DEF6B21363/UBUNTU-20.04/5.5.5/AARCH64/1B215DD48C>) |
| 10ec:b852 | 10ec:b852 | Realtek Semic... | RTL8852BE PCIe 802.11ax Wireless ... | 1     | 8852be     | [7037D37121](<System On Chip/Radxa/ROCK/ROCK 5B/E01230749C71/REBORNOS-ARM-ROLLING/5.10.110-ROCKCHIP-RK3588/AARCH64/7037D37121>) |
| 10ec:c822 | 1a3b:3750 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 1     | rtl8822ce  | [DB3EB249A1](<System On Chip/Nvidia/Tegra/Tegra/A2D34F7D05EB/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/DB3EB249A1>) |
| 14c3:7650 | 14c3:7650 | MediaTek         | 802.11n Wireless Network Adapter     | 1     | mt76x0e    | [5D664BE928](<System On Chip/Others/Others/Others/C58CA0A5CE09/OPENWRT-21.02.3/5.4.188/MIPS/5D664BE928>) |
| 168c:002a | 10cf:147c | Qualcomm Atheros | AR928X Wireless Network Adapter (... | 1     | ath9k      | [ECDDEDCFB7](<System On Chip/Nvidia/Tegra/Tegra/E867D231D0C0/UBUNTU-UNITY-18.04/4.9.201-TEGRA/AARCH64/ECDDEDCFB7>) |
| 168c:003e |           | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 1     | ath10k_pci | [AC382F40E8](<System On Chip/Qualcomm Technologies/Open-Q/Open-Q 820 microsom/F6FEB21E1005/DEBIAN-UNSTABLE/4.14.0-QCOMLT-ARM64/AARCH64/AC382F40E8>) |
| 168c:0042 | 11ad:1806 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 1     | ath10k_pci | [5E682A0733](<System On Chip/Nvidia/Tegra/Tegra/A1DD672248E9/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/5E682A0733>) |
| 168c:0042 | 17aa:0901 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 1     | ath10k_pci | [CFEB6FB78F](<System On Chip/Nvidia/Tegra/Tegra/52416602189B/UBUNTU-UNITY-18.04/4.9.253-TEGRA/AARCH64/CFEB6FB78F>) |
| 8086:06f0 | 1a56:1552 | Intel            | Comet Lake PCH CNVi WiFi             | 1     | iwlwifi    | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:08b1 | 8086:4462 | Intel            | Wireless 7260                        | 1     | iwlwifi    | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:08b3 | 8086:0070 | Intel            | Wireless 3160                        | 1     |            | [E76C7CF9C8](<System On Chip/Others/MNT/MNT Reform 2/1A8BBDCAD424/DEBIAN-11/5.12.0+/AARCH64/E76C7CF9C8>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 1     | iwlwifi    | [C72F8C76F7](<System On Chip/Nvidia/Tegra/Tegra/B2307FE84F73/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/C72F8C76F7>) |
| 8086:2725 | 8086:e024 | Intel            | Wi-Fi 6 AX210/AX211/AX411 160MHz     | 1     | iwlwifi    | [B05FAAC149](<System On Chip/Others/NVIDIA/NVIDIA Jetson Xavier NX Developer Kit/FF85D7E95ADF/UBUNTU-20.04/5.10.104-TEGRA/AARCH64/B05FAAC149>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:8125 | 10ec:0123 | Realtek Semic... | RTL8125 2.5GbE Controller            | 6     | r8125      | [592FEA8754](<System On Chip/Radxa/ROCK/ROCK 5B/139991BFFDC7/UBUNTU-22.04/5.10.110-ROCKCHIP-RK3588/AARCH64/592FEA8754>) |
| 1db3:2355 |           | Unisoc Shangh... | Network controller                   | 2     | wcn_pcie   | [FCDAC368CF](<System On Chip/Others/Others/Others/367A728074AC/JINGOS-20.04/4.14.133-202201191758+/AARCH64/FCDAC368CF>) |
| 8086:1533 | ffff:0000 | Intel            | I210 Gigabit Network Connection      | 2     | igb        | [B05FAAC149](<System On Chip/Others/NVIDIA/NVIDIA Jetson Xavier NX Developer Kit/FF85D7E95ADF/UBUNTU-20.04/5.10.104-TEGRA/AARCH64/B05FAAC149>) |
| 14e4:4441 | 14e4:4389 | Broadcom         | Network controller                   | 1     | pcieh      | [61D82AF735](<System On Chip/Others/Others/Others/6555EFD46738/KALI-2023.1/5.10.107-ANDROID13-4-00004-G6522BF85D262-AB8935228/AARCH64/61D82AF735>) |
| 19e5:1103 | 19e5:0000 | Huawei Techno... | Network controller                   | 1     |            | [3F3D475864](<System On Chip/HUAWEI/PGU-WBY/PGU-WBY0/1C58824AF241/DEBIAN-11/5.10.0-18-ARM64/AARCH64/3F3D475864>) |
| 8086:10d3 | 8086:a01f | Intel            | 82574L Gigabit Network Connection    | 1     | e1000e     | [AC382F40E8](<System On Chip/Qualcomm Technologies/Open-Q/Open-Q 820 microsom/F6FEB21E1005/DEBIAN-UNSTABLE/4.14.0-QCOMLT-ARM64/AARCH64/AC382F40E8>) |
| 8086:1531 | 8086:0000 | Intel            | I210 Gigabit Unprogrammed            | 1     | igb        | [D48FD712A5](<System On Chip/Nvidia/Tegra/Tegra/A6096A1A9829/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/D48FD712A5>) |

### Network and computing encryption device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19e5:a255 |           | Huawei Techno... | HiSilicon SEC Engine                 | 2     | hisi_sec2  | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a5a5 |           | Samsung Elect... |                                      | 1     | s51xx      | [61D82AF735](<System On Chip/Others/Others/Others/6555EFD46738/KALI-2023.1/5.10.107-ANDROID13-4-00004-G6522BF85D262-AB8935228/AARCH64/61D82AF735>) |
| 8086:a124 |           | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:06a4 | 1462:12ed | Intel            | Comet Lake PCH SPI Controller        | 1     |            | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:06e8 | 1462:12ed | Intel            | Comet Lake PCH Serial IO I2C Cont... | 1     | intel_l... | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:06ea | 1462:12ed | Intel            | Comet Lake PCH Serial IO I2C Cont... | 1     | intel_l... | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:06f9 | 1462:12ed | Intel            | Comet Lake PCH Thermal Controller    | 1     | intel_p... | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:1903 | 1462:12ed | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 1     | process... | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:a131 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | intel_p... | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:06a3 | 1462:12ed | Intel            | Comet Lake PCH SMBus Controller      | 1     | i2c_i801   | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:9c22 | 1028:0616 | Intel            | 8 Series SMBus Controller            | 1     | i801_smbus | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:a123 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | i2c_i801   | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1002:aab0 | 1642:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 2     | snd_hda... | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |
| 1002:aa98 | 1787:aa98 | AMD              | Caicos HDMI Audio [Radeon HD 6450... | 1     | snd_hda... | [2B4CD63D88](<System On Chip/HANWEI/FT-208/FT-208-COME-B/7D2A7DE07A62/ATZ-11.2/5.10.0-12-ARM64/AARCH64/2B4CD63D88>) |
| 1002:aab0 | 174b:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 1     | snd_hda... | [B8EA59E9F8](<System On Chip/Inspur/CE520/CE520F/3A556DC2B09D/DEBIAN-11/5.10.0-18-ARM64/AARCH64/B8EA59E9F8>) |
| 1002:aae0 | 1642:aae0 | AMD              | Baffin HDMI/DP Audio [Radeon RX 5... | 1     | snd_hda... | [5A3CB266DB](<System On Chip/GreatWall/DF/DF/5813E68F06D1/DEBIAN-11/5.10.0-22-ARM64/AARCH64/5A3CB266DB>) |
| 1002:aae0 | 1849:aae0 | AMD              | Baffin HDMI/DP Audio [Radeon RX 5... | 1     |            | [63A5E327FB](<System On Chip/SolidRun/LX2160A/LX2160A Clearfog CX/446971F0A5EC/UBUNTU-20.04/5.10.35-00021-G3CC6354C3606/AARCH64/63A5E327FB>) |
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
| 1b4b:9215 | 1b4b:9215 | Marvell Techn... | 88SE9215 PCIe 2.0 x1 4-port SATA ... | 4     | ahci       | [5A3CB266DB](<System On Chip/GreatWall/DF/DF/5813E68F06D1/DEBIAN-11/5.10.0-22-ARM64/AARCH64/5A3CB266DB>) |
| 197b:0585 | 197b:0000 | JMicron Techn... | JMB58x AHCI SATA controller          | 2     | ahci       | [C885B5DA6C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.1/CD7470FE63DD/UBUNTU-22.04/5.15.0-1026-RASPI/AARCH64/C885B5DA6C>) |
| 19e5:a235 |           | Huawei Techno... | HiSilicon AHCI HBA                   | 2     | ahci       | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |
| 1b4b:9171 | 1b4b:9171 | Marvell Techn... | 88SE9171 SATA 6G Controller          | 2     | ahci       | [A1E1FC9259](<System On Chip/Nvidia/Tegra/Tegra/565FBC48D0F2/UBUNTU-UNITY-18.04/4.9.140-TEGRA/AARCH64/A1E1FC9259>) |
| 1b21:0612 | 1b21:1060 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 1     |            | [DF2E4C0C56](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.1/31DD7D4F6016/UBUNTU-22.10/5.19.0-1015-RASPI/AARCH64/DF2E4C0C56>) |
| 1b4b:9183 | 1b4b:9183 | Marvell Techn... | 88SS9183 PCIe SSD Controller         | 1     |            | [5E07806B7E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi ? Rev 1.0/D8FBFD41D06C/UBUNTU-20.04/5.4.0-1015-RASPI/AARCH64/5E07806B7E>) |
| 1b4b:9230 | 1b4b:9230 | Marvell Techn... | 88SE9230 PCIe 2.0 x2 4-port SATA ... | 1     | ahci       | [4B04BE2436](<System On Chip/Rockchip/Others/Others/F590D4D52D83/UBUNTU-20.04/4.4.154-113-ROCKCHIP-GDB9DFC2CDD25/AARCH64/4B04BE2436>) |
| 8086:9c03 | 1028:0616 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 1     | ahci       | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:a103 | 8086:7270 | Intel            | HM170/QM170 Chipset SATA Controll... | 1     | ahci       | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1b21:0611 | 1b21:1060 | ASMedia Techn... | ASM1061 SATA IDE Controller          | 2     | ahci       | [CA89B451BD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.1/29F683549DD4/UBUNTU-22.10/5.19.0-1015-RASPI/AARCH64/CA89B451BD>) |
| 197b:2363 | 197b:2363 | JMicron Techn... | JMB363 SATA/IDE Controller           | 1     | ahci       | [7DDF0DB7EC](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.0/7C8C1F01A3C3/UBUNTU-21.10/5.13.0-1010-RASPI/AARCH64/7DDF0DB7EC>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 7     | nvme       | [68AC87675A](<System On Chip/Nvidia/Tegra/Tegra/DBB28DEA9F16/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/68AC87675A>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980              | 4     | nvme       | [9B39BC4979](<System On Chip/Rockchip/Orange/Orange Pi 5/5E1E10BA1F21/UBUNTU-22.04/5.10.110-ROCKCHIP-RK3588/AARCH64/9B39BC4979>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT SSD Controller     | 3     | nvme       | [769A23D6D3](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/UBUNTU-20.04/5.10.110-30-ROCKCHIP-G12EE46F17A0C/AARCH64/769A23D6D3>) |
| 15b7:5009 | 15b7:5009 | SanDisk          | WD Blue SN550 NVMe SSD               | 3     | nvme       | [931D20E8AE](<System On Chip/pine64,pinebook-pro/Pinebook/Pinebook Pro/AAAD9C14D968/FEDORA-37/6.0.15-300.FC37.AARCH64/AARCH64/931D20E8AE>) |
| 15b7:501a | 15b7:501a | SanDisk          | WD Blue SN570 NVMe SSD               | 3     | nvme       | [043C078CAF](<System On Chip/Others/Others/Others/678CF1D282D3/DEBIAN-12/5.15.0-STARFIVE/RISCV64/043C078CAF>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 3     | nvme       | [AC78B76A30](<System On Chip/Hardkernel/ODROID-M/ODROID-M1/529F410B49D8/UBUNTU-20.04/5.19.0-ODROID-ARM64/AARCH64/AC78B76A30>) |
| c0a9:540a | c0a9:5021 | Micron/Crucia... | P2 NVMe PCIe SSD                     | 3     | nvme       | [4382F0CCE7](<System On Chip/Radxa/ROCK/ROCK Pi 4B/57E79905A598/XUBUNTU-22.04/5.15.93-ROCKCHIP64/AARCH64/4382F0CCE7>) |
| 15b7:5006 | 15b7:5006 | SanDisk          | WD Black SN750 / PC SN730 NVMe SSD   | 2     | nvme       | [3F3D475864](<System On Chip/HUAWEI/PGU-WBY/PGU-WBY0/1C58824AF241/DEBIAN-11/5.10.0-18-ARM64/AARCH64/3F3D475864>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 2     | nvme       | [A1512911DF](<System On Chip/Khadas/VIM/VIM3/8E76D129C324/UBUNTU-20.04/4.9.241/AARCH64/A1512911DF>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013 E13 NVMe Controller           | 2     | nvme       | [EB774628AF](<System On Chip/Rockchip/Orange/Orange Pi 5/AD034DE2F584/UBUNTU-22.04/5.10.110-ROCKCHIP-RK3588/AARCH64/EB774628AF>) |
| 1179:011a | 1179:0001 | Toshiba Ameri... | XG6 NVMe SSD Controller              | 1     | nvme       | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |
| 126f:2263 | 1dee:2263 | Silicon Motion   | SM2263EN/SM2263XT SSD Controller     | 1     | nvme       | [C17309EC68](<System On Chip/Khadas/VIM/VIM3/6CB0C4BD1229/UBUNTU-20.04/5.17.0/AARCH64/C17309EC68>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 1     | nvme       | [DE559AC6D9](<System On Chip/Rockchip/Others/Others/748AF68BF4FB/UBUNTU-MATE-20.04/4.4.154-113-ROCKCHIP-GDB9DFC2CDD25/AARCH64/DE559AC6D9>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 1     | nvme       | [0965D05FE6](<System On Chip/Nvidia/Tegra/Tegra/90823179FECD/UBUNTU-UNITY-18.04/4.9.140-TEGRA/AARCH64/0965D05FE6>) |
| 144d:a80a | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 1     | nvme       | [592FEA8754](<System On Chip/Radxa/ROCK/ROCK 5B/139991BFFDC7/UBUNTU-22.04/5.10.110-ROCKCHIP-RK3588/AARCH64/592FEA8754>) |
| 15b7:5007 | 15b7:5007 | SanDisk          | Non-Volatile memory controller       | 1     | nvme       | [B05FAAC149](<System On Chip/Others/NVIDIA/NVIDIA Jetson Xavier NX Developer Kit/FF85D7E95ADF/UBUNTU-20.04/5.10.104-TEGRA/AARCH64/B05FAAC149>) |
| 15b7:5017 | 15b7:5017 | SanDisk          | NVMe Controller                      | 1     | nvme       | [63A5E327FB](<System On Chip/SolidRun/LX2160A/LX2160A Clearfog CX/446971F0A5EC/UBUNTU-20.04/5.10.35-00021-G3CC6354C3606/AARCH64/63A5E327FB>) |
| 1c5c:174a | 1c5c:174a | SK hynix         | Gold P31/PC711 NVMe Solid State D... | 1     | nvme       | [D8CD86DB45](<System On Chip/PINE64/Pinebook/Pinebook Pro/9912F73F6133/FEDORA-37/6.0.7-301.FC37.AARCH64/AARCH64/D8CD86DB45>) |
| 1d79:2263 | 1d79:2263 | Transcend        | Non-Volatile memory controller       | 1     | nvme       | [B565B4082E](<System On Chip/Nvidia/Tegra/Tegra/70C6735F4190/UBUNTU-20.04/4.9.253-TEGRA/AARCH64/B565B4082E>) |
| 1e4b:1202 | 1e4b:1202 | MAXIO Technol... | NVMe SSD Controller MAP1202          | 1     | nvme       | [17AC97DC37](<System On Chip/Rockchip/Orange/Orange Pi 5/A6798147E384/UBUNTU-22.04/5.10.110-ROCKCHIP-RK3588/AARCH64/17AC97DC37>) |
| 2646:500d | 2646:500d | Kingston Tech... | OM3PDP3 NVMe SSD                     | 1     | nvme       | [2D767E0513](<System On Chip/Rockchip/Orange/Orange Pi 5/B6466CB0DFF0/DEBIAN-11/5.10.110-ROCKCHIP-RK3588/AARCH64/2D767E0513>) |
| 2646:500e | 2646:500e | Kingston Tech... | SNVS2000G [NV1 NVMe PCIe SSD 2TB]    | 1     | nvme       | [98FF02EBDE](<System On Chip/Hardkernel/ODROID-M/ODROID-M1/31F9E63A8FB9/UBUNTU-20.04/4.19.219-ODROID-ARM64/AARCH64/98FF02EBDE>) |
| 2646:500f | 2646:500f | Kingston Tech... | NVMe Controller                      | 1     | nvme       | [577E49B87C](<System On Chip/Hardkernel/ODROID-M/ODROID-M1/6E1390BCA4FC/UBUNTU-20.04/4.19.219-ODROID-ARM64/AARCH64/577E49B87C>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19e5:a25a |           | Huawei Techno... | HiSilicon RDE Engine                 | 2     |            | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |
| 1000:0079 | 1000:9263 | LSI Logic / S... | MegaRAID SAS 2108 [Liberator]        | 1     |            | [7C60CC0210](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.1/80605C62EBC8/DEBIAN-11/5.15.84-V8-NEUER-SCHEISS-KERNEL+/AARCH64/7C60CC0210>) |
| 8086:282a | 1462:12ed | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |

### Storage/sas (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19e5:a230 |           | Huawei Techno... | HiSilicon SAS 3.0 HBA                | 2     | hisi_sa... | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19e5:a122 |           | Huawei Techno... | HiSilicon Embedded DMA Engine        | 2     | hisi_dma   | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |
| 1ac1:089a | 1ac1:089a | Global Unichip   | Coral Edge TPU                       | 1     | apex       | [3EAE2BE077](<System On Chip/Others/Others/Others/38D46EBAF1C2/DEBIAN-TESTING/5.4.3-G050B21F4B394-DIRTY/AARCH64/3EAE2BE077>) |
| 8086:15e8 | 1462:12ed | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 1     | thunder... | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:1911 | 8086:2015 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1106:3483 | 1106:3483 | VIA Technologies | VL805/806 xHCI USB 3.0 Controller    | 883   | xhci_pci   | [F045323C99](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/DFF914D5971F/RASPBIAN-11/6.1.25-V8+/AARCH64/F045323C99>) |
| 1912:0014 |           | Renesas Techn... | uPD720201 USB 3.0 Host Controller    | 2     | xhci_pci   | [B8EA59E9F8](<System On Chip/Inspur/CE520/CE520F/3A556DC2B09D/DEBIAN-11/5.10.0-18-ARM64/AARCH64/B8EA59E9F8>) |
| 1912:0015 | 19e5:3e22 | Renesas Techn... | uPD720202 USB 3.0 Host Controller    | 2     | xhci_pci   | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |
| 19e5:a238 |           | Huawei Techno... | HiSilicon USB 3.0 Host Controller    | 2     | xhci_pci   | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |
| 19e5:a239 |           | Huawei Techno... | HiSilicon USB 2.0 2-port Host Con... | 2     | ehci_hc... | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |
| 19e5:a23b |           | Huawei Techno... | HiSilicon USB 1.1 Host Controller    | 2     | ohci_hc... | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |
| 1912:0014 | ffff:ffff | Renesas Techn... | uPD720201 USB 3.0 Host Controller    | 1     | xhci_pci   | [5A3CB266DB](<System On Chip/GreatWall/DF/DF/5813E68F06D1/DEBIAN-11/5.10.0-22-ARM64/AARCH64/5A3CB266DB>) |
| 8086:06ed | 1462:12ed | Intel            | Comet Lake USB 3.1 xHCI Host Cont... | 1     | xhci_pci   | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:15e9 | 1462:12ed | Intel            | JHL7540 Thunderbolt 3 USB Control... | 1     | xhci_pci   | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 8086:9c26 | 1028:0616 | Intel            | 8 Series USB EHCI #1                 | 1     | ehci_pci   | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:9c31 | 1028:0616 | Intel            | 8 Series USB xHCI HC                 | 1     | xhci_hcd   | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8086:a12f | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | xhci_pci   | [CFBB1B9F64](<System On Chip/Advantech/VEGA-6301/VEGA-6301M/1201F18EF046/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/CFBB1B9F64>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 17cb:1101 | 17cb:0108 | Qualcomm         | QCA6390 Wireless Network Adapter     | 2     | cnss_pci   | [F3B7AB67BC](<System On Chip/Others/Others/Others/BADA157665F2/KALI-2022.2/4.19.113-23222000/AARCH64/F3B7AB67BC>) |
| 17cb:0306 | 17cb:010c | Qualcomm         | Sierra PCIe SDX55 Wireless Device    | 1     | mhi        | [3DBF93245C](<System On Chip/Others/Others/Others/B78396A19CB6/UBUNTU-21.04/5.4.0-FAKED/AARCH64/3DBF93245C>) |

