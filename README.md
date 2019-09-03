Most popular PCI devices
========================

This is a project to identify most popular PCI devices in modern computers and
share detailed lspci reports collected by Linux users at https://linux-hardware.org.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo hw-probe -all -upload

Total reports: 51989.

Contents
--------

1. [ About ](#about)
2. [ PCI Devices ](#pci-devices)
   * [ Bluetooth ](#bluetooth-pci)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Dma controller (eisa dma) ](#dma-controller-eisa-dma-pci)
   * [ Dvb card ](#dvb-card-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Firewire controller ](#firewire-controller-pci)
   * [ Flash memory ](#flash-memory-pci)
   * [ Generic system peripheral ](#generic-system-peripheral-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Input device controller ](#input-device-controller-pci)
   * [ Iommu ](#iommu-pci)
   * [ Ipmi interface (kcs) ](#ipmi-interface-kcs-pci)
   * [ Ipmi smic interface ](#ipmi-smic-interface-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Modem ](#modem-pci)
   * [ Multimedia controller ](#multimedia-controller-pci)
   * [ Multiport serial controller ](#multiport-serial-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Non-essential instrumentation ](#non-essential-instrumentation-pci)
   * [ Non-vga unclassified device ](#non-vga-unclassified-device-pci)
   * [ Parallel controller (ieee1284) ](#parallel-controller-ieee1284-pci)
   * [ Performance counters ](#performance-counters-pci)
   * [ Pic (8259) ](#pic-8259-pci)
   * [ Pic (io(x)-apic) ](#pic-iox-apic-pci)
   * [ Sd host controller ](#sd-host-controller-pci)
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
   * [ System peripheral ](#system-peripheral-pci)
   * [ Tv card ](#tv-card-pci)
   * [ Unclassified device ](#unclassified-device-pci)
   * [ Usb controller ](#usb-controller-pci)
   * [ Others ](#others-pci)

About
-----

The structure of the repository is the following:

    {COMPUTER TYPE}/{VENDOR}/{MODEL PREFIX}/{MODEL}/{HWID}/{OS}/{KERNEL}/{ARCH}/{PROBE ID}

    ( e.g. Notebook/Lenovo/ThinkPad/ThinkPad W540/376C44AF6B85/DEBIAN-9.1/4.9.0-3-AMD64/X86_64/F51B828085 )

You can find appropriate lspci report in this repository by a probe ID as follows:

    find . -name {PROBE ID}

PCI Devices
-----------

Top 100 most popular devices in each category.

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bluetooth (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1814:3298 | 103c:18ec | Ralink     | RT3290 Bluetooth             | 193   | rtbth      | A978F2CA38 |
| 1814:3298 | 105b:e056 | Ralink     | RT3290 Bluetooth             | 55    |            | F71E42FC3C |
| 1814:3298 | 1a3b:2787 | Ralink     | RT3290 Bluetooth             | 9     |            | 4C67B55B77 |
| 1814:3298 | 1a3b:2f87 | Ralink     | RT3290 Bluetooth             | 7     |            | 45F3B356CF |
| 1814:3298 | 1a3b:2987 | Ralink     | RT3290 Bluetooth             | 3     |            | 8D13B8BFE3 |
| 1814:3298 | 103c:191c | Ralink     | RT3290 Bluetooth             | 2     |            | 9B25B9E02E |
| 1814:3298 | 10cf:1772 | Ralink     | RT3290 Bluetooth             | 1     |            | 1135E21142 |
| 1814:3298 | 1814:3298 | Ralink     | RT3290 Bluetooth             | 1     |            | FE9255E7F3 |
| 1814:3298 | 1a3b:210b | Ralink     | RT3290 Bluetooth             | 1     |            | 2333E930AF |

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:4384 |           | AMD        | SBx00 PCI to PCI Bridge      | 2984  | shpchp     | 394C81B911 |
| 1022:1200 |           | AMD        | Family 10h Processor Hype... | 1838  |            | 62E3C9247C |
| 1022:1201 |           | AMD        | Family 10h Processor Addr... | 1838  |            | 62E3C9247C |
| 1022:1202 |           | AMD        | Family 10h Processor DRAM... | 1838  | amd64_e... | 62E3C9247C |
| 1022:1203 |           | AMD        | Family 10h Processor Misc... | 1838  | k10temp    | 62E3C9247C |
| 1022:1204 |           | AMD        | Family 10h Processor Link... | 1838  |            | 62E3C9247C |
| 1022:780f |           | AMD        | FCH PCI Bridge               | 1229  | shpchp     | 8226B90793 |
| 1022:1100 |           | AMD        | K8 [Athlon64/Opteron] Hyp... | 1152  |            | B26ED41AB8 |
| 1022:1101 |           | AMD        | K8 [Athlon64/Opteron] Add... | 1152  |            | B26ED41AB8 |
| 1022:1102 |           | AMD        | K8 [Athlon64/Opteron] DRA... | 1152  | amd64_e... | B26ED41AB8 |
| 1022:1103 |           | AMD        | K8 [Athlon64/Opteron] Mis... | 1152  | k8temp     | B26ED41AB8 |
| 1002:439d | 1002:439d | AMD        | SB7x0/SB8x0/SB9x0 LPC hos... | 910   |            | 394C81B911 |
| 1022:1600 |           | AMD        | Family 15h Processor Func... | 828   |            | 394C81B911 |
| 1022:1601 |           | AMD        | Family 15h Processor Func... | 828   |            | 394C81B911 |
| 1022:1602 |           | AMD        | Family 15h Processor Func... | 828   |            | 394C81B911 |
| 1022:1603 |           | AMD        | Family 15h Processor Func... | 828   | k10temp    | 394C81B911 |
| 1022:1604 |           | AMD        | Family 15h Processor Func... | 828   | fam15h_... | 394C81B911 |
| 1022:1605 |           | AMD        | Family 15h Processor Func... | 828   |            | 394C81B911 |
| 8086:244e | 1458:5000 | Intel      | 82801 PCI Bridge             | 794   |            | B39AC90CA0 |
| 1022:1700 |           | AMD        | Family 12h/14h Processor ... | 793   |            | 8226B90793 |
| 1022:1701 |           | AMD        | Family 12h/14h Processor ... | 793   |            | 8226B90793 |
| 1022:1702 |           | AMD        | Family 12h/14h Processor ... | 793   |            | 8226B90793 |
| 1022:1703 |           | AMD        | Family 12h/14h Processor ... | 793   | k10temp    | 8226B90793 |
| 1022:1704 |           | AMD        | Family 12h/14h Processor ... | 793   |            | 8226B90793 |
| 1022:1716 |           | AMD        | Family 12h/14h Processor ... | 793   |            | 8226B90793 |
| 1022:1718 |           | AMD        | Family 12h/14h Processor ... | 793   |            | 8226B90793 |
| 1022:1719 |           | AMD        | Family 12h/14h Processor ... | 793   |            | 8226B90793 |
| 1002:43a0 | 1002:0000 | AMD        | SB700/SB800/SB900 PCI to ... | 775   | shpchp     | 394C81B911 |
| 8086:244e |           | Intel      | 82801 PCI Bridge             | 665   | shpchp     | 8C4047657D |
| 8086:2d01 | 8086:8086 | Intel      | Core Processor QuickPath ... | 664   |            | 86987CF1ED |
| 8086:2d10 | 8086:8086 | Intel      | Core Processor QPI Link 0    | 664   |            | 86987CF1ED |
| 8086:2d11 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 664   |            | 86987CF1ED |
| 8086:2d12 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 664   |            | 86987CF1ED |
| 8086:2d13 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 664   |            | 86987CF1ED |
| 1022:1400 |           | AMD        | Family 15h (Models 10h-1f... | 613   |            | 32E1C72BAA |
| 1022:1401 |           | AMD        | Family 15h (Models 10h-1f... | 613   |            | 32E1C72BAA |
| 1022:1402 |           | AMD        | Family 15h (Models 10h-1f... | 613   |            | 32E1C72BAA |
| 1022:1403 |           | AMD        | Family 15h (Models 10h-1f... | 613   | k10temp    | 32E1C72BAA |
| 1022:1404 |           | AMD        | Family 15h (Models 10h-1f... | 613   |            | 32E1C72BAA |
| 1022:1405 |           | AMD        | Family 15h (Models 10h-1f... | 613   |            | 32E1C72BAA |
| 8086:244e | 1043:8179 | Intel      | 82801 PCI Bridge             | 570   |            | FAC5E9FEFA |
| 8086:27b8 | 1043:8179 | Intel      | 82801GB/GR (ICH7 Family) ... | 570   | lpc_ich    | FAC5E9FEFA |
| 8086:27d0 | 1043:8179 | Intel      | NM10/ICH7 Family PCI Expr... | 559   | shpchp     | FAC5E9FEFA |
| 1022:43a0 | 1022:0000 | AMD        | Hudson PCI to PCI bridge ... | 553   | shpchp     | 9137FB3859 |
| 1b21:1080 | 1043:8489 | ASMedia... | ASM1083/1085 PCIe to PCI ... | 542   | shpchp     | 99614383EB |
| 1022:1452 |           | AMD        | Family 17h (Models 00h-1f... | 518   |            | D7977A3B0E |
| 8086:2c62 | 8086:8086 | Intel      | Core Processor QuickPath ... | 513   |            | 86987CF1ED |
| 8086:1c10 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 466   | shpchp     | 66A5EA0BE5 |
| 1002:5a14 | 1002:5a14 | AMD        | RD9x0/RX980 Host Bridge      | 455   |            | 394C81B911 |
| 1002:5a16 | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 443   | shpchp     | 394C81B911 |
| 8086:27d2 | 1043:8179 | Intel      | NM10/ICH7 Family PCI Expr... | 430   | shpchp     | FAC5E9FEFA |
| 1002:5a18 | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 426   | shpchp     | 6A60A724F9 |
| 8086:244e | 1849:244e | Intel      | 82801 PCI Bridge             | 418   |            | 5F6E1A3B61 |
| 8086:27b8 | 1458:5001 | Intel      | 82801GB/GR (ICH7 Family) ... | 402   | lpc_ich    | D0D6CD20B1 |
| 8086:0c01 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 390   | shpchp     | F6CCF2BBA6 |
| 8086:0c00 | 1043:8534 | Intel      | 4th Gen Core Processor DR... | 389   | hsw_uncore | F6CCF2BBA6 |
| 1002:43a1 | 1002:0000 | AMD        | SB700/SB800/SB900 PCI to ... | 366   | shpchp     | F9F3745636 |
| 8086:2448 |           | Intel      | 82801 Mobile PCI Bridge      | 354   | shpchp     | E9BD04F647 |
| 8086:0101 | 1043:844d | Intel      | Xeon E3-1200/2nd Generati... | 350   | shpchp     | 66A5EA0BE5 |
| 8086:0100 | 1043:844d | Intel      | 2nd Generation Core Proce... | 349   | snb_uncore | 66A5EA0BE5 |
| 8086:1e10 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 348   | shpchp     | 570B707FFB |
| 8086:244e | 1458:8892 | Intel      | 82801 PCI Bridge             | 343   |            | 8C4047657D |
| 1002:439d | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 LPC hos... | 339   |            | D569843A2D |
| 1022:1414 | 1022:1234 | AMD        | Family 15h (Models 10h-1f... | 330   | shpchp     | 67B0C18725 |
| 10de:03e8 | 10de:0000 | Nvidia     | MCP61 PCI Express bridge     | 327   | shpchp     | 11D0376265 |
| 8086:1c1a | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 325   | shpchp     | 66A5EA0BE5 |
| 1022:1460 |           | AMD        | Family 17h (Models 00h-0f... | 323   |            | 4A2455EAE6 |
| 1022:1461 |           | AMD        | Family 17h (Models 00h-0f... | 323   |            | 4A2455EAE6 |
| 1022:1462 |           | AMD        | Family 17h (Models 00h-0f... | 323   |            | 4A2455EAE6 |
| 1022:1463 |           | AMD        | Family 17h (Models 00h-0f... | 323   | k10temp    | 4A2455EAE6 |
| 1022:1464 |           | AMD        | Family 17h (Models 00h-0f... | 323   |            | 4A2455EAE6 |
| 1022:1465 |           | AMD        | Family 17h (Models 00h-0f... | 323   |            | 4A2455EAE6 |
| 1022:1466 |           | AMD        | Family 17h (Models 00h-0f... | 323   |            | 4A2455EAE6 |
| 1022:1467 |           | AMD        | Family 17h (Models 00h-0f... | 323   |            | 4A2455EAE6 |
| 8086:244e | 1458:5001 | Intel      | 82801 PCI Bridge             | 320   | pcieport   | 8C4047657D |
| 8086:8c10 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 308   | shpchp     | F6CCF2BBA6 |
| 1022:43a1 | 1022:0000 | AMD        | Hudson PCI to PCI bridge ... | 303   | shpchp     | BDB727808F |
| 8086:1c5c | 1043:844d | Intel      | H61 Express Chipset LPC C... | 299   | lpc_ich    | 6CF789DF63 |
| 1002:43a3 | 1002:0000 | AMD        | SB900 PCI to PCI bridge (... | 297   | shpchp     | 4201CDD966 |
| 8086:244e | 1043:84ca | Intel      | 82801 PCI Bridge             | 297   |            | 1434651158 |
| 1022:43b4 | 1b21:3306 | AMD        | 300 Series Chipset PCIe Port | 293   | pcieport   | D084D64BDF |
| 8086:27d0 | 1458:5001 | Intel      | NM10/ICH7 Family PCI Expr... | 293   | shpchp     | DD0FCDE6C7 |
| 8086:1c10 | 1458:5001 | Intel      | 6 Series/C200 Series Chip... | 285   | shpchp     | E4C2A9F4EB |
| 8086:244e | 1043:844d | Intel      | 82801 PCI Bridge             | 282   | pcieport   | 66A5EA0BE5 |
| 1022:1454 | 1022:1454 | AMD        | Family 17h (Models 00h-0f... | 281   | pcieport   | D084D64BDF |
| 1022:1510 | 1022:1510 | AMD        | Family 14h Processor Root... | 277   |            | F9F3745636 |
| 8086:244e | 1043:82d4 | Intel      | 82801 PCI Bridge             | 272   |            | B481805845 |
| 1022:9600 | 1022:9600 | AMD        | RS780 Host Bridge            | 269   |            | 8EAEF3C906 |
| 1002:43a2 | 1002:0000 | AMD        | SB900 PCI to PCI bridge (... | 268   | shpchp     | 85F1B83B30 |
| 1022:43a2 | 1022:0000 | AMD        | Hudson PCI to PCI bridge ... | 267   | shpchp     | 78E822AD79 |
| 8086:1e18 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 266   | shpchp     | 570B707FFB |
| 8086:8c14 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 266   | shpchp     | F6CCF2BBA6 |
| 1022:9600 | 1043:8388 | AMD        | RS780 Host Bridge            | 263   |            | D569843A2D |
| 1022:1439 | 1022:1234 | AMD        | Family 16h Processor Func... | 260   | shpchp     | 1CC2218397 |
| 10de:03e9 | 10de:0000 | Nvidia     | MCP61 PCI Express bridge     | 257   | shpchp     | 11D0376265 |
| 8086:0150 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 255   | ie31200... | 570B707FFB |
| 8086:0151 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 255   | shpchp     | 570B707FFB |
| 8086:1e10 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 253   | shpchp     | 891002E8F2 |
| 1002:5a1c | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 251   | shpchp     | 394C81B911 |
| 1022:1412 | 1022:1234 | AMD        | Family 15h (Models 10h-1f... | 250   | shpchp     | 67B0C18725 |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:5287 | 1043:202f | Realtek... | RTL8411B PCI Express Card... | 87    | rtsx_pci   | DDA26EE2AA |
| 10ec:5286 | 10ec:5286 | Realtek... | RTL8402 Integrated 1-LUN ... | 80    | rtsx_pci   | EFA97B65E3 |
| 10ec:5289 | 1043:202f | Realtek... | RTL8411 PCI Express Card ... | 73    | rtsx_pci   | 0F8CE4DCC0 |
| 10ec:5286 | 1043:202f | Realtek... | RTL8402 Integrated 1-LUN ... | 60    | rtsx_pci   | 5AEE6B7CA7 |
| 10ec:5209 | 1025:0685 | Realtek... | RTS5209 PCI Express Card ... | 40    | rtsx_pci   | BB4B4DE9DD |
| 10ec:5289 | 10ec:5289 | Realtek... | RTL8411 PCI Express Card ... | 36    | rtsx_pci   | E103A76D85 |
| 10ec:5287 | 1025:0866 | Realtek... | RTL8411B PCI Express Card... | 35    | rtsx_pci   | 1C77D7A584 |
| 10ec:5229 | 17aa:3808 | Realtek... | RTS5229 PCI Express Card ... | 33    | rtsx_pci   | EE1CFF7014 |
| 10ec:5227 | 10ec:5227 | Realtek... | RTS5227 PCI Express Card ... | 31    | rtsx_pci   | 2D1845C282 |
| 10ec:5289 | 1043:1587 | Realtek... | RTL8411 PCI Express Card ... | 31    | rtsx_pci   | 469E04E0D5 |
| 10ec:5209 | 1025:0590 | Realtek... | RTS5209 PCI Express Card ... | 29    | rtsx_pci   | D5A624C8FE |
| 10ec:5229 | 10ec:5229 | Realtek... | RTS5229 PCI Express Card ... | 29    | rtsx_pci   | 00C22F3924 |
| 10ec:5209 | 103c:3577 | Realtek... | RTS5209 PCI Express Card ... | 28    | rtsx_pci   | 4201CDD966 |
| 10ec:5287 | 1025:1094 | Realtek... | RTL8411B PCI Express Card... | 28    | rtsx_pci   | E4B342382F |
| 10ec:5229 | 103c:184a | Realtek... | RTS5229 PCI Express Card ... | 27    | rtsx_pci   | 0D67044A36 |
| 10ec:5287 | 1025:1193 | Realtek... | RTL8411B PCI Express Card... | 26    | rtsx_pci   | 141D7917FF |
| 10ec:5209 | 104d:908b | Realtek... | RTS5209 PCI Express Card ... | 25    | rtsx_pci   | 9B5D49431C |
| 10ec:5229 | 1043:202f | Realtek... | RTS5229 PCI Express Card ... | 24    | rtsx_pci   | C53DF5F083 |
| 10ec:5209 | 104d:90ab | Realtek... | RTS5209 PCI Express Card ... | 22    | rtsx_pci   | B56B7F6394 |
| 10ec:5209 | 104d:90b8 | Realtek... | RTS5209 PCI Express Card ... | 22    | rtsx_pci   | 66E469F722 |
| 10ec:5229 | 103c:1818 | Realtek... | RTS5229 PCI Express Card ... | 22    | rtsx_pci   | C865BDB72F |
| 10ec:5229 | 103c:2213 | Realtek... | RTS5229 PCI Express Card ... | 22    | rtsx_pci   | 964E06B446 |
| 10ec:5287 | 1025:1192 | Realtek... | RTL8411B PCI Express Card... | 22    | rtsx_pci   | 0D71E52A34 |
| 10ec:5209 | 103c:1670 | Realtek... | RTS5209 PCI Express Card ... | 20    | rtsx_pci   | FC29696703 |
| 10ec:5209 | 103c:3567 | Realtek... | RTS5209 PCI Express Card ... | 20    | rtsx_pci   | 937DD869FC |
| 10ec:5227 | 17aa:220c | Realtek... | RTS5227 PCI Express Card ... | 20    | rtsx_pci   | 7637F3DE5F |
| 10ec:5229 | 103c:183e | Realtek... | RTS5229 PCI Express Card ... | 20    | rtsx_pci   | 19D5DAD934 |
| 10ec:5229 | 17aa:3800 | Realtek... | RTS5229 PCI Express Card ... | 20    | rtsx_pci   | E3105C7B7A |
| 10ec:5287 | 10ec:5287 | Realtek... | RTL8411B PCI Express Card... | 20    | rtsx_pci   | 37B056E670 |
| 10ec:5209 | 1025:061f | Realtek... | RTS5209 PCI Express Card ... | 18    | rtsx_pci   | 2CD19D38C6 |
| 10ec:5209 | 1025:0781 | Realtek... | RTS5209 PCI Express Card ... | 16    | rtsx_pci   | 6CC64DA5C5 |
| 10ec:5229 | 103c:1854 | Realtek... | RTS5229 PCI Express Card ... | 16    | rtsx_pci   | 69CEE0DC90 |
| 10ec:5229 | 103c:1858 | Realtek... | RTS5229 PCI Express Card ... | 16    | rtsx_pci   | F7D8D4D158 |
| 10ec:5249 | 17aa:3801 | Realtek... | RTS5249 PCI Express Card ... | 16    | rtsx_pci   | 262BB6B100 |
| 10ec:5289 | 1043:1457 | Realtek... | RTL8411 PCI Express Card ... | 16    | rtsx_pci   | 1AC2B8EE74 |
| 10ec:522a | 103c:8079 | Realtek... | RTS522A PCI Express Card ... | 15    | rtsx_pci   | B8392B7335 |
| 10ec:522a | 10ec:522a | Realtek... | RTS522A PCI Express Card ... | 15    | rtsx_pci   | 9104464264 |
| 10ec:5289 | 1025:0724 | Realtek... | RTL8411 PCI Express Card ... | 15    | rtsx_pci   | 68C4019E33 |
| 10ec:5209 | 103c:1672 | Realtek... | RTS5209 PCI Express Card ... | 14    | rtsx_pci   | 05F2682C5B |
| 10ec:525a | 1028:07e6 | Realtek... | RTS525A PCI Express Card ... | 14    | rtsx_pci   | 5D2CB1E1B0 |
| 10ec:5289 | 1558:0240 | Realtek... | RTL8411 PCI Express Card ... | 14    | rtsx_pci   | 598F621727 |
| 10ec:5289 | 1558:1550 | Realtek... | RTL8411 PCI Express Card ... | 14    | rtsx_pci   | 4671F06112 |
| 10ec:5209 | 1025:0696 | Realtek... | RTS5209 PCI Express Card ... | 13    | rtsx_pci   | E7BE897976 |
| 10ec:5209 | 103c:3566 | Realtek... | RTS5209 PCI Express Card ... | 13    | rtsx_pci   | 87235D85B9 |
| 10ec:5209 | 104d:907b | Realtek... | RTS5209 PCI Express Card ... | 13    | rtsx_pci   | 801A0452F8 |
| 10ec:5209 | 17aa:21dd | Realtek... | RTS5209 PCI Express Card ... | 13    | rtsx_pci   | 916FA6F088 |
| 10ec:5227 | 103c:198f | Realtek... | RTS5227 PCI Express Card ... | 13    | rtsx_pci   | DCE9CDAF8E |
| 10ec:5227 | 17aa:220e | Realtek... | RTS5227 PCI Express Card ... | 13    | rtsx_pci   | 364B159B80 |
| 10ec:5227 | 17aa:2214 | Realtek... | RTS5227 PCI Express Card ... | 13    | rtsx_pci   | F03FCA81E0 |
| 10ec:5227 | 17aa:5034 | Realtek... | RTS5227 PCI Express Card ... | 13    | rtsx_pci   | BA450606A3 |
| 10ec:5229 | 103c:1885 | Realtek... | RTS5229 PCI Express Card ... | 13    | rtsx_pci   | 0C02DFD17B |
| 10ec:525a | 1028:07be | Realtek... | RTS525A PCI Express Card ... | 13    | rtsx_pci   | CB9F8EC46D |
| 10ec:5289 | 1297:2041 | Realtek... | RTL8411 PCI Express Card ... | 13    | rtsx_pci   | 0806F6416C |
| 10ec:5209 | 1025:0624 | Realtek... | RTS5209 PCI Express Card ... | 12    | rtsx_pci   | 2901F0F370 |
| 10ec:5227 | 103c:2246 | Realtek... | RTS5227 PCI Express Card ... | 12    | rtsx_pci   | 3E165AC0A4 |
| 10ec:5229 | 103c:188b | Realtek... | RTS5229 PCI Express Card ... | 12    | rtsx_pci   | A91F4FE9DC |
| 10ec:5229 | 1179:f920 | Realtek... | RTS5229 PCI Express Card ... | 12    | rtsx_pci   | 61625F7FA6 |
| 10ec:525a | 1028:087c | Realtek... | RTS525A PCI Express Card ... | 12    | rtsx_pci   | 7A9639F003 |
| 10ec:5289 | 1043:14f7 | Realtek... | RTL8411 PCI Express Card ... | 12    | rtsx_pci   | 908F38EB2A |
| 10ec:5229 | 103c:1849 | Realtek... | RTS5229 PCI Express Card ... | 11    | rtsx_pci   | 8589AD3406 |
| 10ec:5229 | 8086:2068 | Realtek... | RTS5229 PCI Express Card ... | 11    | rtsx_pci   | 64913D4FAA |
| 10ec:5287 | 1558:6504 | Realtek... | RTL8411B PCI Express Card... | 11    | rtsx_pci   | D607079392 |
| 10ec:5289 | 103c:18a7 | Realtek... | RTL8411 PCI Express Card ... | 11    | rtsx_pci   | 00C9DC0C76 |
| 10ec:5289 | 1558:6501 | Realtek... | RTL8411 PCI Express Card ... | 11    | rtsx_pci   | 74E2647236 |
| 10ec:5289 | 1558:6502 | Realtek... | RTL8411 PCI Express Card ... | 11    | rtsx_pci   | 5A5E21619D |
| 10ec:5209 | 103c:1666 | Realtek... | RTS5209 PCI Express Card ... | 10    | rtsx_pci   | A7E86DE30D |
| 10ec:5209 | 103c:3389 | Realtek... | RTS5209 PCI Express Card ... | 10    | sdhci_pci  | D2006E7A87 |
| 10ec:5227 | 1028:0616 | Realtek... | RTS5227 PCI Express Card ... | 10    | rtsx_pci   | 2F330BEE0B |
| 10ec:5229 | 10cf:176b | Realtek... | RTS5229 PCI Express Card ... | 10    | rtsx_pci   | B7F6E1F635 |
| 10ec:5229 | 17aa:3801 | Realtek... | RTS5229 PCI Express Card ... | 10    | rtsx_pci   | 81A189B163 |
| 10ec:522a | 17aa:2233 | Realtek... | RTS522A PCI Express Card ... | 10    | rtsx_pci   | 78932B3C9B |
| 10ec:525a | 1028:0704 | Realtek... | RTS525A PCI Express Card ... | 10    | rtsx_pci   | 159AB17857 |
| 10ec:5286 | 1558:5470 | Realtek... | RTL8402 Integrated 1-LUN ... | 10    | rtsx_pci   | D4EAA0F0C1 |
| 10ec:5287 | 1025:0940 | Realtek... | RTL8411B PCI Express Card... | 10    | rtsx_pci   | 8B3744250A |
| 10ec:5287 | 1025:121e | Realtek... | RTL8411B PCI Express Card... | 10    | rtsx_pci   | 951A7053B0 |
| 10ec:5287 | 1025:1264 | Realtek... | RTL8411B PCI Express Card... | 10    | rtsx_pci   | F3941C8871 |
| 10ec:5289 | 1043:1447 | Realtek... | RTL8411 PCI Express Card ... | 10    | rtsx_pci   | FAC5CEE3E3 |
| 10ec:5209 | 103c:165c | Realtek... | RTS5209 PCI Express Card ... | 9     | rtsx_pci   | 8AB2BC95FD |
| 10ec:5209 | 104d:90ac | Realtek... | RTS5209 PCI Express Card ... | 9     | rtsx_pci   | 8A2F60A60A |
| 10ec:5229 | 1179:f91b | Realtek... | RTS5229 PCI Express Card ... | 9     | rtsx_pci   | 71C7CF2056 |
| 10ec:5229 | 1179:ff1e | Realtek... | RTS5229 PCI Express Card ... | 9     | rtsx_pci   | B295B98723 |
| 10ec:5229 | 17aa:365e | Realtek... | RTS5229 PCI Express Card ... | 9     | rtsx_pci   | BAA91679D8 |
| 10ec:5229 | 17aa:5018 | Realtek... | RTS5229 PCI Express Card ... | 9     | rtsx_pci   | 991CC1AF7C |
| 10ec:522a | 103c:8101 | Realtek... | RTS522A PCI Express Card ... | 9     | rtsx_pci   | B9E21A89DA |
| 10ec:525a | 1028:087d | Realtek... | RTS525A PCI Express Card ... | 9     | rtsx_pci   | 75F82151FF |
| 10ec:5287 | 1558:0945 | Realtek... | RTL8411B PCI Express Card... | 9     | rtsx_pci   | 749E4A0BA1 |
| 1aea:6621 | 1aea:6621 | Alcor M... | Alcor Micro PCIe Card Reader | 9     | alcor_pci  | B4ED65654C |
| 10ec:5209 | 103c:3672 | Realtek... | RTS5209 PCI Express Card ... | 8     | rtsx_pci   | 7306A03690 |
| 10ec:5227 | 10cf:187f | Realtek... | RTS5227 PCI Express Card ... | 8     | rtsx_pci   | 491E66B3D8 |
| 10ec:5229 | 103c:1842 | Realtek... | RTS5229 PCI Express Card ... | 8     | rtsx_pci   | FEF9011BE9 |
| 10ec:5229 | 103c:184c | Realtek... | RTS5229 PCI Express Card ... | 8     | rtsx_pci   | B0D6527F67 |
| 10ec:5229 | 103c:216c | Realtek... | RTS5229 PCI Express Card ... | 8     | rtsx_pci   | 67B0C18725 |
| 10ec:5229 | 17aa:5000 | Realtek... | RTS5229 PCI Express Card ... | 8     | rtsx_pci   | FA98476936 |
| 10ec:522a | 103c:837d | Realtek... | RTS522A PCI Express Card ... | 8     | rtsx_pci   | 9B82C44F0C |
| 10ec:522a | 8086:2074 | Realtek... | RTS522A PCI Express Card ... | 8     | rtsx_pci   | 23DC7C0455 |
| 10ec:525a | 1028:082a | Realtek... | RTS525A PCI Express Card ... | 8     | rtsx_pci   | 174CC02B16 |
| 10ec:525a | 1028:08af | Realtek... | RTS525A PCI Express Card ... | 8     | rtsx_pci   | D4A2D02674 |
| 10ec:5287 | 1025:079b | Realtek... | RTL8411B PCI Express Card... | 8     | rtsx_pci   | 07CD36611F |
| 10ec:5287 | 1025:0865 | Realtek... | RTL8411B PCI Express Card... | 8     | rtsx_pci   | B8D1E63435 |
| 10ec:5287 | 1025:118a | Realtek... | RTL8411B PCI Express Card... | 8     | rtsx_pci   | C80CAABFC9 |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0753 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Co-... | 33    |            | 88719BBDD6 |
| 10de:0aa3 | 10de:cb79 | Nvidia     | MCP79 Co-processor           | 33    | nvidia     | 9F753AC669 |
| 10de:0753 | 1849:0753 | Nvidia     | MCP78S [GeForce 8200] Co-... | 21    |            | AC2555A764 |
| 10de:03f4 | 1462:7309 | Nvidia     | MCP61 SMU                    | 18    |            | C9F702BE07 |
| 10de:0aa3 | 1043:1cf7 | Nvidia     | MCP79 Co-processor           | 18    | nvidia     | F0A1399A3F |
| 10de:0543 | 1025:0126 | Nvidia     | MCP67 Co-processor           | 17    |            | F7695ADD11 |
| 10de:0753 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] Co-... | 15    |            | 265A212FDC |
| 10de:03f4 | 1462:7597 | Nvidia     | MCP61 SMU                    | 14    |            | A0A7F774C4 |
| 10de:0aa3 | 1043:1fa7 | Nvidia     | MCP79 Co-processor           | 13    | nvidia     | C4A5E49D47 |
| 10de:0d7a | 10de:cb89 | Nvidia     | MCP89 Co-Processor           | 13    |            | 80ECBDE76E |
| 10de:0753 | 1043:82e2 | Nvidia     | MCP78S [GeForce 8200] Co-... | 10    |            | 94F06CBF32 |
| 10de:0543 | 103c:30cf | Nvidia     | MCP67 Co-processor           | 9     |            | 1184F5572B |
| 10de:0aa3 | 1043:8402 | Nvidia     | MCP79 Co-processor           | 9     | nvidia     | 353AB385C9 |
| 10de:0aa3 | 1025:0222 | Nvidia     | MCP79 Co-processor           | 8     | nvidia     | 4F99355CFD |
| 10de:0271 | 103c:30b7 | Nvidia     | MCP51 PMU                    | 6     |            | B699788F33 |
| 10de:03f4 | 1043:8234 | Nvidia     | MCP61 SMU                    | 6     |            | 8C4716B30A |
| 10de:0543 | 1849:0543 | Nvidia     | MCP67 Co-processor           | 6     |            | 1C80EA8C25 |
| 10de:03f4 |           | Nvidia     | MCP61 SMU                    | 5     |            | 5343BC19E6 |
| 10de:0543 | 1043:16a7 | Nvidia     | MCP67 Co-processor           | 5     |            | 9227856E4A |
| 10de:0753 | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] Co-... | 5     |            | 4CA7976A88 |
| 10de:0753 | 1565:340b | Nvidia     | MCP78S [GeForce 8200] Co-... | 5     |            | 52B394C153 |
| 10de:0aa3 | 103c:3651 | Nvidia     | MCP79 Co-processor           | 5     | nvidia     | 535E45E25D |
| 10de:0aa3 | 1b0a:0074 | Nvidia     | MCP79 Co-processor           | 5     | nvidia     | 957D335223 |
| 10de:0753 | 1043:82e8 | Nvidia     | MCP78S [GeForce 8200] Co-... | 4     |            | 5AFC22B5E1 |
| 10de:0aa3 | 1025:0160 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | 69DC96A4D0 |
| 10de:0aa3 | 1462:1012 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | FE43B38080 |
| 10de:0aa3 | 1849:0aa3 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | 1CADF5EB87 |
| 10de:0271 | 103c:30e5 | Nvidia     | MCP51 PMU                    | 3     |            | 45FC8F4912 |
| 10de:0447 | 103c:30cf | Nvidia     | MCP65 SMU                    | 3     |            | 084F7E13DA |
| 10de:0753 | 1025:0228 | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | B2D5544528 |
| 10de:07da | 1462:7366 | Nvidia     | MCP73 Co-processor           | 3     |            | 3C83AF8B83 |
| 10de:0aa3 | 1043:1d17 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 14A1FEC4BA |
| 10de:0aa3 | 1043:83e2 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 1452DE25DA |
| 10de:0271 | 103c:30b5 | Nvidia     | MCP51 PMU                    | 2     |            | E964514E68 |
| 10de:0271 | 1043:1367 | Nvidia     | MCP51 PMU                    | 2     |            | D455CC767C |
| 10de:0271 | 1462:3fc1 | Nvidia     | MCP51 PMU                    | 2     |            | 278EF4A255 |
| 10de:03f4 | 1849:03f4 | Nvidia     | MCP61 SMU                    | 2     |            | B7F7A41C71 |
| 10de:0543 | 103c:30d6 | Nvidia     | MCP67 Co-processor           | 2     |            | 3B57385D7E |
| 10de:0543 | 103c:30ea | Nvidia     | MCP67 Co-processor           | 2     |            | 8BC37D1961 |
| 10de:0753 | 1025:0153 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 96600BDB45 |
| 10de:0753 | 1025:0462 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 03A71DD3EB |
| 10de:0753 | 103c:2a81 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 2E29A30FA2 |
| 10de:0753 | 1043:82e7 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 97B83F48DF |
| 10de:0753 | 1462:6720 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | E2CB0B1767 |
| 10de:07da | 10de:07d7 | Nvidia     | MCP73 Co-processor           | 2     |            | 975F642709 |
| 10de:0aa3 | 1025:0168 | Nvidia     | MCP79 Co-processor           | 2     |            | 5443C8EC11 |
| 10de:0aa3 | 1043:1a87 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | C2D93613D4 |
| 10de:0aa3 | 1462:1019 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | 2054B3A4CC |
| 10de:0aa3 | 1462:7621 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | 1BA5C50EAD |
| 10de:0aa3 | 1734:1151 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | 47DF471783 |
| 10de:0aa3 | 17aa:38da | Nvidia     | MCP79 Co-processor           | 2     |            | C38D40E936 |
| 10de:0aa3 | 19da:0ae5 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | BA99DCB426 |
| 10de:0271 | 103c:30bf | Nvidia     | MCP51 PMU                    | 1     |            | 4A6A073320 |
| 10de:0271 | 1043:1322 | Nvidia     | MCP51 PMU                    | 1     |            | 71FE8FB963 |
| 10de:0271 | 1462:373d | Nvidia     | MCP51 PMU                    | 1     |            | F6C1542CAC |
| 10de:0271 | 1734:10d3 | Nvidia     | MCP51 PMU                    | 1     |            | 6172D9B266 |
| 10de:0543 | 1025:0127 | Nvidia     | MCP67 Co-processor           | 1     |            | DB69CCC0BF |
| 10de:0543 | 1043:1697 | Nvidia     | MCP67 Co-processor           | 1     |            | C3296D5344 |
| 10de:0753 | 1019:1b67 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 4765DCDC47 |
| 10de:0753 | 1025:014a | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | F63FFEFC64 |
| 10de:0753 | 1025:0227 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 3CF233B9C4 |
| 10de:0753 | 103c:2a9e | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | DF15AC1D7E |
| 10de:0753 | 1043:8332 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | E527269900 |
| 10de:0753 | 1462:6520 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 12132D4EBD |
| 10de:0753 | 1462:7375 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 2C3B9EAC17 |
| 10de:0753 | 1462:7578 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | AFECB4A1DB |
| 10de:0753 | 1631:e03b | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | E6D16C44AA |
| 10de:07da | 1025:0137 | Nvidia     | MCP73 Co-processor           | 1     |            | 9204CB3BAC |
| 10de:07da | 1462:736b | Nvidia     | MCP73 Co-processor           | 1     |            | 0445B13D43 |
| 10de:07da | 1462:7504 | Nvidia     | MCP73 Co-processor           | 1     |            | 05F36A437A |
| 10de:07da | 1849:07da | Nvidia     | MCP73 Co-processor           | 1     |            | 64E722CEC4 |
| 10de:0aa3 | 1028:0271 | Nvidia     | MCP79 Co-processor           | 1     |            | 0238C91A6C |
| 10de:0aa3 | 103c:2a83 | Nvidia     | MCP79 Co-processor           | 1     | nvidia     | 226AA094E2 |
| 10de:0aa3 | 103c:2aa1 | Nvidia     | MCP79 Co-processor           | 1     |            | DF47C88DB6 |
| 10de:0aa3 | 1043:8356 | Nvidia     | MCP79 Co-processor           | 1     |            | E5CBBA8ADC |
| 10de:0aa3 | 1071:9070 | Nvidia     | MCP79 Co-processor           | 1     |            | 3D0D6AEFBF |
| 10de:0aa3 | 1071:9515 | Nvidia     | MCP79 Co-processor           | 1     | nvidia     | E028F277D4 |
| 10de:0aa3 | 19da:a108 | Nvidia     | MCP79 Co-processor           | 1     |            | 7439F4F707 |
| 10de:0aa3 | 1b0a:000f | Nvidia     | MCP79 Co-processor           | 1     | nvidia     | F298AE57F6 |
| 10de:0aa3 | 1b0a:4203 | Nvidia     | MCP79 Co-processor           | 1     |            | 926753D3C7 |
| 10de:0aa3 | 1b7d:0040 | Nvidia     | MCP79 Co-processor           | 1     |            | 053ACCA095 |
| 10de:0aa3 | a0a0:0802 | Nvidia     | MCP79 Co-processor           | 1     |            | B778A6096A |
| 8086:37c8 | 8086:0000 | Intel      | C62x Chipset QuickAssist ... | 1     |            | F8D0599716 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1c3a | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 463   | mei_me     | 66A5EA0BE5 |
| 8086:1e3a | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 343   | mei_me     | 570B707FFB |
| 8086:8c3a | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 316   | mei_me     | F6CCF2BBA6 |
| 8086:1c3a | 1458:1c3a | Intel      | 6 Series/C200 Series Chip... | 287   | mei_me     | 1984E65634 |
| 8086:1e3a | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 258   | mei_me     | 891002E8F2 |
| 8086:1e3a | 1458:1c3a | Intel      | 7 Series/C216 Chipset Fam... | 235   | mei_me     | 8C4047657D |
| 8086:a13a | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 196   | mei_me     | 99614383EB |
| 8086:8c3a | 1458:1c3a | Intel      | 8 Series/C220 Series Chip... | 182   | mei_me     | DD4DA32934 |
| 8086:1c3a | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 162   | mei_me     | A7618091FB |
| 8086:1c3a | 1849:1c3a | Intel      | 6 Series/C200 Series Chip... | 114   | mei_me     | BDA40E6195 |
| 8086:a13a | 1458:1c3a | Intel      | 100 Series/C230 Series Ch... | 103   | mei_me     | 0BF4CAF942 |
| 8086:9c3a | 17aa:3978 | Intel      | 8 Series HECI #0             | 88    | mei_me     | C0E6FFA24F |
| 8086:3b64 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 85    | mei_me     | 49783F833C |
| 8086:1c3a | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 80    | mei_me     | 6B25B8982D |
| 8086:1e3a | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 80    | mei_me     | F28D18F3E9 |
| 8086:8c3a | 1849:8c3a | Intel      | 8 Series/C220 Series Chip... | 79    | mei_me     | 8AE6B6F651 |
| 8086:3b64 | 17aa:215f | Intel      | 5 Series/3400 Series Chip... | 77    | mei_me     | DA5E944C6C |
| 8086:8cba | 1043:8534 | Intel      | 9 Series Chipset Family M... | 76    | mei_me     | EFA3992D9A |
| 8086:8c3a | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 72    | mei_me     | 7BBCD6F17D |
| 8086:3b64 | 17aa:38a5 | Intel      | 5 Series/3400 Series Chip... | 70    | mei_me     | 62697BF35B |
| 8086:1e3a | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 69    | mei_me     | CE3DDF28FC |
| 8086:8cba | 1458:1c3a | Intel      | 9 Series Chipset Family M... | 66    | mei_me     | 2DDBCF3D21 |
| 8086:1c3a | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 65    | mei_me     | 8579BA1B16 |
| 8086:1e3a | 1849:1e3a | Intel      | 7 Series/C216 Chipset Fam... | 63    | mei_me     | 3D8C4FEBC3 |
| 8086:a2ba | 1458:1c3a | Intel      | 200 Series PCH CSME HECI #1  | 63    | mei_me     | AAD0551E27 |
| 8086:2a44 | 17aa:20e6 | Intel      | Mobile 4 Series Chipset M... | 62    | mei_me     | FDAB3CF92F |
| 8086:1e3a | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 61    | mei_me     | E67DFC255A |
| 8086:1c3a | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 60    | mei_me     | 826F5492EB |
| 8086:1e3a | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 60    | mei_me     | 6478022B75 |
| 8086:1e3a | 1043:124d | Intel      | 7 Series/C216 Chipset Fam... | 59    | mei_me     | 0F8CE4DCC0 |
| 8086:3b64 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 56    | mei_me     | D023F50697 |
| 8086:a2ba | 1043:8694 | Intel      | 200 Series PCH CSME HECI #1  | 54    | mei_me     | 7F1F084A4F |
| 8086:8c3a | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 52    | mei_me     | 262BB6B100 |
| 8086:1e3a | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 49    | mei_me     | 39CA2BE7BB |
| 8086:3b64 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 47    | mei_me     | 9A8E939D8B |
| 8086:1e3a | 17aa:5011 | Intel      | 7 Series/C216 Chipset Fam... | 46    | mei_me     | 65D329A2C6 |
| 8086:1e3a | 1043:14c7 | Intel      | 7 Series/C216 Chipset Fam... | 45    | mei_me     | 9A401175B3 |
| 8086:1c3a | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 44    | mei_me     | EE56C112BB |
| 8086:1c3a | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 43    | mei_me     | EA07B48EB4 |
| 8086:1c3a | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 41    | mei_me     | C0868A2B0C |
| 8086:1c3a | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 41    | mei_me     | 7AF20CDF5A |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 41    | mei_me     | 1579402536 |
| 8086:1d3a | 1043:84ef | Intel      | C600/X79 series chipset M... | 40    | mei_me     | EEE7D322DF |
| 8086:1c3a | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 39    | mei_me     | 561B991E16 |
| 8086:3b64 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 39    | mei_me     | 3C5767E938 |
| 8086:1c3a | 144d:c0b6 | Intel      | 6 Series/C200 Series Chip... | 38    | mei_me     | 616616B60F |
| 8086:3b64 | 1458:3b64 | Intel      | 5 Series/3400 Series Chip... | 38    | mei_me     | 85F57C764C |
| 8086:a13a | 1849:a13a | Intel      | 100 Series/C230 Series Ch... | 37    | mei_me     | BCB3EF58AB |
| 8086:1c3a | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 35    | mei_me     | FBF8462F41 |
| 8086:1e3a | 1462:7758 | Intel      | 7 Series/C216 Chipset Fam... | 34    | mei_me     | 0A593D376A |
| 8086:9c3a | 1025:0866 | Intel      | 8 Series HECI #0             | 34    | mei_me     | 1C77D7A584 |
| 8086:5a9a | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 32    | mei_me     | 0FAD7AC4EB |
| 8086:a360 | 1043:8694 | Intel      | Cannon Lake PCH HECI Cont... | 32    | mei_me     | 68BABB69CB |
| 8086:1e3a | 17aa:21f6 | Intel      | 7 Series/C216 Chipset Fam... | 31    | mei_me     | 7DA7A083D7 |
| 8086:a360 | 1458:1c3a | Intel      | Cannon Lake PCH HECI Cont... | 31    | mei_me     | 0B02A9E571 |
| 8086:1e3a | 1043:1587 | Intel      | 7 Series/C216 Chipset Fam... | 30    | mei_me     | 469E04E0D5 |
| 8086:1e3a | 1179:fb31 | Intel      | 7 Series/C216 Chipset Fam... | 30    | mei_me     | 806B890CCF |
| 8086:1e3a | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 30    | mei_me     | 6D5F1234C2 |
| 8086:9c3a | 1025:0775 | Intel      | 8 Series HECI #0             | 29    | mei_me     | 3BD8AD186F |
| 8086:1c3a | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 28    | mei_me     | CA6EFEBBD7 |
| 8086:1e3a | 1043:1477 | Intel      | 7 Series/C216 Chipset Fam... | 28    | mei_me     | C38728C67C |
| 8086:1e3a | 144d:c652 | Intel      | 7 Series/C216 Chipset Fam... | 28    | mei_me     | A57B555F26 |
| 8086:3b64 | 144d:c581 | Intel      | 5 Series/3400 Series Chip... | 28    | mei_me     | 4B260556B7 |
| 8086:9c3a | 1028:0651 | Intel      | 8 Series HECI #0             | 27    | mei_me     | 1E1FE2154B |
| 8086:9c3a | 1043:131d | Intel      | 8 Series HECI #0             | 27    | mei_me     | 761A86BDC8 |
| 8086:1e3a | 10cf:16ea | Intel      | 7 Series/C216 Chipset Fam... | 26    | mei_me     | B9A4817612 |
| 8086:1e3a | 144d:c0d8 | Intel      | 7 Series/C216 Chipset Fam... | 26    | mei_me     | 0F042024B4 |
| 8086:8d3a | 1043:8600 | Intel      | C610/X99 series chipset M... | 26    | mei_me     | A8F2B39356 |
| 8086:9d3a | 1025:1193 | Intel      | Sunrise Point-LP CSME HEC... | 26    | mei_me     | 141D7917FF |
| 8086:1c3a | 1462:7680 | Intel      | 6 Series/C200 Series Chip... | 25    | mei_me     | CBE52D9E29 |
| 8086:1e3a | 1025:0686 | Intel      | 7 Series/C216 Chipset Fam... | 25    | mei_me     | 29CFE1AD23 |
| 8086:1e3a | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 25    | mei_me     | DB9250D9E0 |
| 8086:1c3a | 104d:908b | Intel      | 6 Series/C200 Series Chip... | 24    | mei_me     | BD70BB63B5 |
| 8086:9c3a | 1043:16cd | Intel      | 8 Series HECI #0             | 24    | mei_me     | FDD61F096B |
| 8086:1c3a | 103c:167c | Intel      | 6 Series/C200 Series Chip... | 23    | mei_me     | 15E5D2BB9D |
| 8086:3b64 | 1025:036d | Intel      | 5 Series/3400 Series Chip... | 23    | mei_me     | 333F038ACE |
| 8086:9d3a | 1025:1085 | Intel      | Sunrise Point-LP CSME HEC... | 23    | mei_me     | AE1CE65D11 |
| 8086:a2ba | 1043:872f | Intel      | 200 Series PCH CSME HECI #1  | 23    | mei_me     | 3B3DC1A093 |
| 8086:a2ba | 1849:a2ba | Intel      | 200 Series PCH CSME HECI #1  | 23    | mei_me     | CACD7C9489 |
| 8086:1c3a | 1025:0511 | Intel      | 6 Series/C200 Series Chip... | 22    | mei_me     | F618F23CD4 |
| 8086:1e3a | 103c:1818 | Intel      | 7 Series/C216 Chipset Fam... | 22    | mei_me     | C865BDB72F |
| 8086:1e3a | 104d:90b8 | Intel      | 7 Series/C216 Chipset Fam... | 22    | mei_me     | 66E469F722 |
| 8086:9d3a | 17aa:3801 | Intel      | Sunrise Point-LP CSME HEC... | 22    | mei_me     | 005771EDFD |
| 8086:1e3a | 1025:0835 | Intel      | 7 Series/C216 Chipset Fam... | 21    | mei_me     | AB33DE8D3B |
| 8086:1e3a | 104d:90ab | Intel      | 7 Series/C216 Chipset Fam... | 21    | mei_me     | B56B7F6394 |
| 8086:3b64 | 10cf:152b | Intel      | 5 Series/3400 Series Chip... | 21    | mei_me     | EEFC712947 |
| 8086:8cba | 1849:8cba | Intel      | 9 Series Chipset Family M... | 21    | mei_me     | 09CC6BAB56 |
| 8086:9cba | 1025:098a | Intel      | Wildcat Point-LP MEI Cont... | 21    | mei_me     | 6D1C781DE0 |
| 8086:9d3a | 1025:115f | Intel      | Sunrise Point-LP CSME HEC... | 21    | mei_me     | E4B342382F |
| 8086:9d3a | 8086:7270 | Intel      | Sunrise Point-LP CSME HEC... | 21    | mei_me     | 329795002B |
| 8086:a13a | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 21    | mei_me     | BD6DC70775 |
| 8086:1c3a | 103c:1670 | Intel      | 6 Series/C200 Series Chip... | 20    | mei_me     | FC29696703 |
| 8086:1c3a | 1179:fc30 | Intel      | 6 Series/C200 Series Chip... | 20    | mei_me     | FE2AB22987 |
| 8086:1c3a | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 20    | mei_me     | 23DAC0F1B6 |
| 8086:1e3a | 103c:183e | Intel      | 7 Series/C216 Chipset Fam... | 20    | mei_me     | 19D5DAD934 |
| 8086:2e14 | 1028:027f | Intel      | 4 Series Chipset HECI Con... | 20    | mei_me     | DFA7361038 |
| 8086:3b64 | 1179:ff1e | Intel      | 5 Series/3400 Series Chip... | 20    | mei_me     | 725958F861 |
| 8086:9c3a | 17aa:220c | Intel      | 8 Series HECI #0             | 20    | mei_me     | 7637F3DE5F |
| 8086:a360 | 1849:a360 | Intel      | Cannon Lake PCH HECI Cont... | 20    | mei_me     | 39C0FBE126 |
| 8086:1c3a | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 19    | mei_me     | 5C380FEC25 |

### Dma controller (eisa dma) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22c0 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 9     | dw_dmac... | 27537B5C01 |
| 8086:9ce0 | 8086:9ce0 | Intel      | Wildcat Point-LP Serial I... | 8     | dw_dmac... | 5515E7AA30 |
| 8086:2286 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 4     | dw_dmac... | 8069B2A3BC |
| 8086:22c0 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 4     | dw_dmac... | 8069B2A3BC |
| 8086:9c60 |           | Intel      | 8 Series Low Power Sub-Sy... | 4     | dw_dmac... | 1D4DA7DE61 |
| 8086:0f40 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 2     | dw_dmac... | 0994A3EEB3 |
| 8086:9c60 | 1025:0a11 | Intel      | 8 Series Low Power Sub-Sy... | 2     | dw_dmac... | F304E3BA6B |
| 8086:0f06 | 8086:0f06 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | A968EF1DD8 |
| 8086:0f06 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | A211982E39 |
| 8086:9c60 | 103c:21ed | Intel      | 8 Series Low Power Sub-Sy... | 1     | dw_dmac... | ED9149D4A2 |

### Dvb card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 13d0:2103 | 13d0:2103 | Techsan... | B2C2 FlexCopII DVB chip /... | 31    | b2c2_fl... | 8BC183FC09 |
| 1131:7146 | 13c2:1018 | Philips... | SAA7146                      | 24    | budget     | 626C138C66 |
| 14f1:8802 | 0070:9002 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     | cx88_dvb   | 8168BA11E3 |
| 1131:7146 | 13c2:0003 | Philips... | SAA7146                      | 2     | dvb_ttpci  | DE8317D2C2 |
| 109e:0878 | 1822:0001 | Brooktree  | Bt878 Audio Capture          | 1     | bt878      | E53C96510D |
| 1131:7146 | 13c2:000e | Philips... | SAA7146                      | 1     | dvb_ttpci  | 2A21A99A38 |
| 1131:7146 | 13c2:1019 | Philips... | SAA7146                      | 1     | budget_ci  | 6AC977EDE4 |
| 1131:7146 | 13c2:101a | Philips... | SAA7146                      | 1     | budget_ci  | D299FE84F3 |
| 14f1:8802 | 17de:08a6 | Conexan... | CX23880/1/2/3 PCI Video a... | 1     | cx88_dv... | FBC32972EA |
| 195d:1105 | 195d:1105 |            | Ethernet controller          | 1     | dm1105     | 531BDFDD32 |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1456 | 1022:1456 | AMD        | Family 17h (Models 00h-0f... | 279   | ccp        | D084D64BDF |
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 127   | mei_txe    | 4414412FCB |
| 1022:1537 | 1022:1537 | AMD        | Kabini/Mullins PSP-Platfo... | 117   | ccp        | 1CC2218397 |
| 1022:15df | 1022:15df | AMD        | Family 17h (Models 10h-1f... | 109   |            | 123447177A |
| 8086:0f18 | 8086:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 55    | mei_txe    | CEAC334581 |
| 8086:0f18 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 54    | mei_txe    | CC7193A7B9 |
| 8086:0f18 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 52    | mei_txe    | 0994A3EEB3 |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 48    |            | 37D7E42722 |
| 1022:1537 | 17aa:3801 | AMD        | Kabini/Mullins PSP-Platfo... | 42    | ccp        | 760B445B08 |
| 1022:1456 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 37    | ccp        | 4A2455EAE6 |
| 8086:0f18 | 17aa:3909 | Intel      | Atom Processor Z36xxx/Z37... | 33    | mei_txe    | EE1CFF7014 |
| 8086:0f18 | 1043:14dd | Intel      | Atom Processor Z36xxx/Z37... | 29    | mei_txe    | 8D51E5FEC5 |
| 1022:1578 | 103c:8330 | AMD        | Carrizo Platform Security... | 27    |            | D32B7275C3 |
| 8086:2298 | 1025:1012 | Intel      | Atom/Celeron/Pentium Proc... | 27    | mei_txe    | 5A7F96289D |
| 8086:0f18 | 1297:2041 | Intel      | Atom Processor Z36xxx/Z37... | 26    | mei_txe    | 100EB984CA |
| 1022:1578 | 1025:1192 | AMD        | Carrizo Platform Security... | 22    |            | 0D71E52A34 |
| 8086:0f18 | 103c:2213 | Intel      | Atom Processor Z36xxx/Z37... | 22    | mei_txe    | 964E06B446 |
| 8086:0f18 | 1043:161d | Intel      | Atom Processor Z36xxx/Z37... | 22    | mei_txe    | BDFF3A60F1 |
| 8086:2298 | 1043:10c0 | Intel      | Atom/Celeron/Pentium Proc... | 22    | mei_txe    | F8FDA4EFC3 |
| 8086:0f18 | 17aa:3986 | Intel      | Atom Processor Z36xxx/Z37... | 20    | mei_txe    | E3105C7B7A |
| 8086:0f18 | 1849:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 18    | mei_txe    | EF6230C726 |
| 1022:1578 | 17aa:3810 | AMD        | Carrizo Platform Security... | 17    |            | C61C9E33F6 |
| 8086:0f18 | 1043:15bd | Intel      | Atom Processor Z36xxx/Z37... | 17    | mei_txe    | CE2184CB68 |
| 1022:1537 | 17aa:3808 | AMD        | Kabini/Mullins PSP-Platfo... | 15    | ccp        | 10DEE916FF |
| 1022:15df | 103c:84ae | AMD        | Family 17h (Models 10h-1f... | 14    |            | E8755C7EF8 |
| 8086:2298 | 17aa:3808 | Intel      | Atom/Celeron/Pentium Proc... | 14    | mei_txe    | 7957C03703 |
| 8086:0f18 | 1458:1c3a | Intel      | Atom Processor Z36xxx/Z37... | 13    | mei_txe    | 2D2468C273 |
| 8086:2298 | 1028:06ac | Intel      | Atom/Celeron/Pentium Proc... | 13    | mei_txe    | CE847DF44A |
| 8086:2298 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 13    | mei_txe    | 001551B002 |
| 1022:1578 | 103c:8331 | AMD        | Carrizo Platform Security... | 12    |            | 9111BD09BB |
| 8086:2298 | 1043:12e0 | Intel      | Atom/Celeron/Pentium Proc... | 12    | mei_txe    | 6458C4F07B |
| 1022:1537 | 1025:104b | AMD        | Kabini/Mullins PSP-Platfo... | 11    | ccp        | 35F6E0CE5F |
| 1022:15df | 1043:876b | AMD        | Family 17h (Models 10h-1f... | 11    |            | 76E2078928 |
| 8086:0f18 | 1025:0845 | Intel      | Atom Processor Z36xxx/Z37... | 10    | mei_txe    | 8981357D7A |
| 8086:0f18 | 1558:5470 | Intel      | Atom Processor Z36xxx/Z37... | 10    | mei_txe    | D4EAA0F0C1 |
| 1022:1578 | 103c:8333 | AMD        | Carrizo Platform Security... | 9     |            | 84687C4322 |
| 1022:15df | 17aa:3809 | AMD        | Family 17h (Models 10h-1f... | 9     |            | F6996F43AE |
| 8086:2298 | 103c:832c | Intel      | Atom/Celeron/Pentium Proc... | 9     | mei_txe    | 54D2AD349B |
| 8086:2298 | 1043:1cbd | Intel      | Atom/Celeron/Pentium Proc... | 9     | mei_txe    | 4FB6C852BB |
| 8086:2298 | 1558:0945 | Intel      | Atom/Celeron/Pentium Proc... | 9     | mei_txe    | 749E4A0BA1 |
| 1022:1537 | 1025:108a | AMD        | Kabini/Mullins PSP-Platfo... | 8     | ccp        | 15AB2F9B58 |
| 1022:1578 | 103c:84ac | AMD        | Carrizo Platform Security... | 8     |            | 44E78B4D3F |
| 8086:0f18 | 1025:0933 | Intel      | Atom Processor Z36xxx/Z37... | 8     | mei_txe    | F08AFAA79D |
| 8086:2298 | 103c:81f1 | Intel      | Atom/Celeron/Pentium Proc... | 8     | mei_txe    | B91750B80C |
| 8086:2298 | 1043:1d5d | Intel      | Atom/Celeron/Pentium Proc... | 8     | mei_txe    | 5AEE6B7CA7 |
| 8086:0f18 |           | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | A154D9D080 |
| 8086:0f18 | 1025:0905 | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | 50FFA5DCEC |
| 8086:0f18 | 103c:2190 | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | E900AD9CFC |
| 8086:0f18 | 103c:21de | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | 4677C67DBA |
| 8086:0f18 | 1043:176d | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | 4E37AD043D |
| 8086:0f18 | 1043:8534 | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | 7F66D8C94D |
| 8086:2298 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 7     | mei_txe    | D91699583D |
| 8086:2298 | 103c:80c5 | Intel      | Atom/Celeron/Pentium Proc... | 7     | mei_txe    | E1B215CA26 |
| 8086:2298 | 1043:10b0 | Intel      | Atom/Celeron/Pentium Proc... | 7     | mei_txe    | AA9F4B66AD |
| 8086:2298 | 1043:191d | Intel      | Atom/Celeron/Pentium Proc... | 7     | mei_txe    | 70DE2F36AE |
| 8086:2298 | 1043:8534 | Intel      | Atom/Celeron/Pentium Proc... | 7     | mei_txe    | 9BB60AEDD5 |
| 8086:2298 | 1458:1000 | Intel      | Atom/Celeron/Pentium Proc... | 7     | mei_txe    | 39694A0489 |
| 1022:1456 | 1462:7a38 | AMD        | Family 17h (Models 00h-0f... | 6     | ccp        | 4B9FC100D8 |
| 1022:15df | 17aa:3804 | AMD        | Family 17h (Models 10h-1f... | 6     |            | 52036BD95B |
| 8086:0f18 | 1025:089d | Intel      | Atom Processor Z36xxx/Z37... | 6     | mei_txe    | 2619209EC5 |
| 8086:0f18 | 1025:0936 | Intel      | Atom Processor Z36xxx/Z37... | 6     | mei_txe    | A1D2E02773 |
| 8086:0f18 | 1025:0939 | Intel      | Atom Processor Z36xxx/Z37... | 6     | mei_txe    | 39B0D513AA |
| 8086:2298 | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 6     | mei_txe    | 838DD8C3AC |
| 1022:1537 | 103c:2269 | AMD        | Kabini/Mullins PSP-Platfo... | 5     | ccp        | 9A3053250C |
| 1022:1578 | 17aa:380b | AMD        | Carrizo Platform Security... | 5     |            | FF3ABD912F |
| 1022:15df | 103c:84d2 | AMD        | Family 17h (Models 10h-1f... | 5     |            | DEFB86D43A |
| 8086:0f18 | 1028:064d | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | C72380C4E8 |
| 8086:0f18 | 103c:220f | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | 6F9FB4A3FD |
| 8086:0f18 | 1043:16dd | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | 7297A28A7F |
| 8086:0f18 | 17aa:368d | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | E04CCB489C |
| 8086:0f18 | 17aa:3807 | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | 5C27867F6E |
| 8086:0f18 | 17aa:3985 | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | 1004F2D148 |
| 8086:2298 | 1025:1010 | Intel      | Atom/Celeron/Pentium Proc... | 5     | mei_txe    | C5CB60A44F |
| 8086:2298 | 1028:0725 | Intel      | Atom/Celeron/Pentium Proc... | 5     | mei_txe    | 94A897D5A7 |
| 8086:2298 | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 5     | mei_txe    | DD16DF4133 |
| 8086:2298 | 103c:82bd | Intel      | Atom/Celeron/Pentium Proc... | 5     | mei_txe    | 8A7389044C |
| 8086:2298 | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 5     | mei_txe    | 1EB4640C84 |
| 8086:2298 | 1297:2063 | Intel      | Atom/Celeron/Pentium Proc... | 5     | mei_txe    | 2D91F64A77 |
| 8086:2298 | 1849:2298 | Intel      | Atom/Celeron/Pentium Proc... | 5     | mei_txe    | 4A3BD3D31E |
| 8086:2298 | 8086:2298 | Intel      | Atom/Celeron/Pentium Proc... | 5     | mei_txe    | 0201253794 |
| 1022:1537 | 103c:226a | AMD        | Kabini/Mullins PSP-Platfo... | 4     | ccp        | 4B70A9D252 |
| 1022:1537 | 103c:226b | AMD        | Kabini/Mullins PSP-Platfo... | 4     | ccp        | 01CBF7482C |
| 1022:1578 | 103c:81f9 | AMD        | Carrizo Platform Security... | 4     |            | 7FAA2ABF56 |
| 1022:1578 | 103c:8345 | AMD        | Carrizo Platform Security... | 4     |            | 7E3B6FA95F |
| 1022:1578 | 17aa:380f | AMD        | Carrizo Platform Security... | 4     |            | C19D82302D |
| 1022:15df | 1025:125c | AMD        | Family 17h (Models 10h-1f... | 4     |            | 6AEFA7E06C |
| 1022:15df | 1462:7c02 | AMD        | Family 17h (Models 10h-1f... | 4     |            | 74440073DF |
| 8086:0f18 | 1025:0860 | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 4086083D68 |
| 8086:0f18 | 1025:0928 | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | C10F5336A8 |
| 8086:0f18 | 1043:14ed | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 492943101C |
| 8086:0f18 | 1179:f91b | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 71C7CF2056 |
| 8086:0f18 | 17aa:390c | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 54908845C3 |
| 8086:0f18 | 8086:2055 | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 4C2CE64AE4 |
| 8086:2298 | 103c:821d | Intel      | Atom/Celeron/Pentium Proc... | 4     | mei_txe    | 46064EAB76 |
| 8086:2298 | 103c:8320 | Intel      | Atom/Celeron/Pentium Proc... | 4     | mei_txe    | E97A9CF2C6 |
| 8086:2298 | 103c:8342 | Intel      | Atom/Celeron/Pentium Proc... | 4     | mei_txe    | F8B5956A65 |
| 8086:2298 | 1458:1c3a | Intel      | Atom/Celeron/Pentium Proc... | 4     | mei_txe    | 5B47EB5CFD |
| 1022:1537 | 1025:0960 | AMD        | Kabini/Mullins PSP-Platfo... | 3     | ccp        | 64956D50FC |
| 1022:1537 | 103c:80b8 | AMD        | Kabini/Mullins PSP-Platfo... | 3     | ccp        | 5048EB8853 |
| 1022:1537 | 103c:82f6 | AMD        | Kabini/Mullins PSP-Platfo... | 3     | ccp        | B09BE0C6DA |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 104c:8024 | 1458:1000 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 353   | firewir... | 8EAEF3C906 |
| 1106:3044 | 1043:81fe | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 331   | firewir... | B481805845 |
| 11c1:5901 | 11c1:5900 | LSI        | FW643 [TrueFire] PCIe 139... | 96    | firewir... | B6D6A0F54D |
| 1106:3044 | 1458:1000 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 94    | firewir... | 394C81B911 |
| 11c1:5811 | 1043:8294 | LSI        | FW322/323 [TrueFire] 1394... | 92    | firewir... | 29B7777E42 |
| 1106:3403 | 1043:8384 | VIA Tec... | VT6315 Series Firewire Co... | 84    | firewir... | AC377EFFFB |
| 1180:0832 | 17aa:20c7 | Ricoh      | R5C832 IEEE 1394 Controller  | 84    | firewir... | A23E000798 |
| 1106:3044 | 1106:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 79    | firewir... | B26ED41AB8 |
| 104c:803a | 1025:011f | Texas I... | PCIxx12 OHCI Compliant IE... | 64    | firewir... | 7387D70AD5 |
| 1102:4001 | 1102:0010 | Creativ... | SB Audigy FireWire Port      | 63    | firewir... | 7A74EB0F6F |
| 104c:8023 | 1043:808b | Texas I... | TSB43AB22A IEEE-1394a-200... | 48    | firewir... | 38155B66BB |
| 104c:803a | 1179:ff00 | Texas I... | PCIxx12 OHCI Compliant IE... | 42    | firewir... | 3CE1664885 |
| 1106:3403 | 1849:3403 | VIA Tec... | VT6315 Series Firewire Co... | 41    | firewir... | 7B99FD4C95 |
| 1180:e832 | 17aa:2136 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 34    | firewir... | DA5E944C6C |
| 11c1:5811 | 11c1:5811 | LSI        | FW322/323 [TrueFire] 1394... | 34    | firewir... | FDEA938323 |
| 1180:0832 | 1028:0233 | Ricoh      | R5C832 IEEE 1394 Controller  | 30    | firewir... | 1F49A84F1F |
| 104c:823f |           | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 29    | firewir... | AA53E34C56 |
| 1180:0832 | 103c:30cc | Ricoh      | R5C832 IEEE 1394 Controller  | 27    | firewir... | 9EDE738BFC |
| 1217:00f7 | 1028:01f9 | O2 Micro   | Firewire (IEEE 1394)         | 27    | firewir... | C331358BBE |
| 1106:3403 | 1043:8374 | VIA Tec... | VT6315 Series Firewire Co... | 26    | firewir... | 054E0BF393 |
| 197b:2380 | 1043:8313 | JMicron... | IEEE 1394 Host Controller    | 26    | firewir... | 6ED85C31F2 |
| 104c:803a | 103c:30a2 | Texas I... | PCIxx12 OHCI Compliant IE... | 22    | firewir... | 531D26CDD8 |
| 1180:0832 | 1025:011e | Ricoh      | R5C832 IEEE 1394 Controller  | 21    | firewir... | ED83D72FBE |
| 1180:0832 | 1028:022f | Ricoh      | R5C832 IEEE 1394 Controller  | 21    | firewir... | 55CD396670 |
| 1180:e832 | 17aa:21f6 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 21    | firewir... | 7DA7A083D7 |
| 104c:8023 | 1043:815b | Texas I... | TSB43AB22A IEEE-1394a-200... | 20    | firewir... | 6932570C80 |
| 1180:e832 | 1028:040a | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 20    | firewir... | D588CD38C2 |
| 1217:00f7 | 1179:ff50 | O2 Micro   | Firewire (IEEE 1394)         | 18    | firewir... | B6017B2145 |
| 1180:0832 | 1025:0121 | Ricoh      | R5C832 IEEE 1394 Controller  | 17    | firewir... | CFBA4082BB |
| 1180:0832 | 1025:0126 | Ricoh      | R5C832 IEEE 1394 Controller  | 17    | firewir... | F7695ADD11 |
| 1180:0832 | 1043:1317 | Ricoh      | R5C832 IEEE 1394 Controller  | 16    | firewir... | B304C61746 |
| 1217:00f7 | 1217:00f7 | O2 Micro   | Firewire (IEEE 1394)         | 16    | firewir... | DE010A6F04 |
| 197b:2380 | 103c:161c | JMicron... | IEEE 1394 Host Controller    | 16    | firewir... | 6F7AAF1391 |
| 104c:803a | 1179:ff10 | Texas I... | PCIxx12 OHCI Compliant IE... | 15    | firewir... | 4FFE571137 |
| 1106:3403 | 103c:2a9c | VIA Tec... | VT6315 Series Firewire Co... | 15    | firewir... | A585EAEF35 |
| 1180:0832 | 103c:7008 | Ricoh      | R5C832 IEEE 1394 Controller  | 15    | firewir... | AB17752168 |
| 1180:0832 | 1043:1877 | Ricoh      | R5C832 IEEE 1394 Controller  | 15    | firewir... | CB27B32040 |
| 1180:0832 | 1043:1897 | Ricoh      | R5C832 IEEE 1394 Controller  | 15    | firewir... | 96E310C22E |
| 197b:2380 | 103c:179b | JMicron... | IEEE 1394 Host Controller    | 15    | firewir... | ED317797F0 |
| 197b:2380 | 103c:3628 | JMicron... | IEEE 1394 Host Controller    | 15    | firewir... | E09686C315 |
| 1180:e832 | 17aa:21cf | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 14    | firewir... | E7A16D4FC1 |
| 1106:3044 | 1043:808a | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 13    | firewir... | A4A45B8A8B |
| 1180:0832 | 1043:14e7 | Ricoh      | R5C832 IEEE 1394 Controller  | 13    | firewir... | D9970BDA58 |
| 11c1:5811 | 103c:2a6f | LSI        | FW322/323 [TrueFire] 1394... | 13    | firewir... | AA83F14B99 |
| 104c:8023 | 8086:514d | Texas I... | TSB43AB22A IEEE-1394a-200... | 12    | firewir... | 9E17250CD3 |
| 1180:0832 | 1028:01bd | Ricoh      | R5C832 IEEE 1394 Controller  | 12    | firewir... | 586A6A9F8A |
| 1180:0832 | 103c:30cf | Ricoh      | R5C832 IEEE 1394 Controller  | 12    | firewir... | 084F7E13DA |
| 1180:0832 | 1043:1767 | Ricoh      | R5C832 IEEE 1394 Controller  | 12    | firewir... | 4137AC8F54 |
| 1180:0832 | 104d:9035 | Ricoh      | R5C832 IEEE 1394 Controller  | 12    | firewir... | A3C4D07088 |
| 1180:0832 | 1179:ff1c | Ricoh      | R5C832 IEEE 1394 Controller  | 12    | firewir... | 588EAD6870 |
| 1180:e832 | 1028:040b | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 12    | firewir... | 80B359DC57 |
| 1180:e832 | 17aa:21ce | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 12    | firewir... | 029641C14A |
| 11c1:5811 | 103c:1589 | LSI        | FW322/323 [TrueFire] 1394... | 12    | firewir... | E14EB74EA5 |
| 197b:2380 | 103c:17ab | JMicron... | IEEE 1394 Host Controller    | 12    | firewir... | 3B64B265CF |
| 197b:2380 | 103c:3603 | JMicron... | IEEE 1394 Host Controller    | 12    | firewir... | 9CE29D0583 |
| 1180:0832 | 1028:024f | Ricoh      | R5C832 IEEE 1394 Controller  | 11    | firewir... | 5A8B3F34A3 |
| 1180:0832 | 1028:029a | Ricoh      | R5C832 IEEE 1394 Controller  | 11    | firewir... | 394D903321 |
| 1180:0832 | 1043:1517 | Ricoh      | R5C832 IEEE 1394 Controller  | 11    | firewir... | FAECBEFA9B |
| 11c1:5811 | 103c:1309 | LSI        | FW322/323 [TrueFire] 1394... | 11    | firewir... | 5A8BAD0B76 |
| 104c:8023 | 8086:5044 | Texas I... | TSB43AB22A IEEE-1394a-200... | 10    | firewir... | 969A371A99 |
| 1217:11f7 | 1028:04a3 | O2 Micro   | OZ600 1394a-2000 Controller  | 10    | firewir... | 19E1CA5871 |
| 197b:2380 | 103c:3659 | JMicron... | IEEE 1394 Host Controller    | 10    | firewir... | AFAAE2AA59 |
| 1106:3044 | 1106:0404 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 9     | firewir... | 5302586F9D |
| 1106:3044 | 1849:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 9     | firewir... | C44B707FC4 |
| 1106:3403 | 1106:3403 | VIA Tec... | VT6315 Series Firewire Co... | 9     | firewir... | D77F80F180 |
| 1180:0832 | 103c:30bb | Ricoh      | R5C832 IEEE 1394 Controller  | 9     | firewir... | FB7F51216E |
| 1180:0832 | 103c:7007 | Ricoh      | R5C832 IEEE 1394 Controller  | 9     | firewir... | 83E800C91C |
| 1180:0832 | 10f7:8338 | Ricoh      | R5C832 IEEE 1394 Controller  | 9     | firewir... | FDCC1DFB81 |
| 11c1:5811 | 103c:30dd | LSI        | FW322/323 [TrueFire] 1394... | 9     | firewir... | 6832A5FE8D |
| 197b:2380 | 103c:30f4 | JMicron... | IEEE 1394 Host Controller    | 9     | firewir... | DDA054B15D |
| 104c:8024 | 1019:8056 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 8     | firewir... | 5647BADC5C |
| 104c:8032 | 103c:099c | Texas I... | OHCI Compliant IEEE 1394 ... | 8     | firewir... | E0DF895DC8 |
| 104c:803a | 1179:0001 | Texas I... | PCIxx12 OHCI Compliant IE... | 8     | firewir... | 3E0ED41BC7 |
| 1106:3044 | 17f2:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 8     | firewir... | 7B106B9427 |
| 1180:0832 | 1028:023a | Ricoh      | R5C832 IEEE 1394 Controller  | 8     | firewir... | 2B5F0594D3 |
| 1180:0832 | 103c:172a | Ricoh      | R5C832 IEEE 1394 Controller  | 8     | firewir... | E2C04796A0 |
| 1180:0832 | 103c:30be | Ricoh      | R5C832 IEEE 1394 Controller  | 8     | firewir... | 2B9B5142AF |
| 1180:0832 | 103c:30c0 | Ricoh      | R5C832 IEEE 1394 Controller  | 8     | firewir... | 21ACEB2150 |
| 1180:0832 | 103c:30db | Ricoh      | R5C832 IEEE 1394 Controller  | 8     | firewir... | 9792924118 |
| 1217:13f7 | 1028:0494 | O2 Micro   | 1394 OHCI Compliant Host ... | 8     | firewir... | A217BF3485 |
| 197b:2380 | 103c:1618 | JMicron... | IEEE 1394 Host Controller    | 8     | firewir... | 7D1AE28E6D |
| 1033:00f2 | 1033:00f2 | NEC Com... | uPD72874 [Firewarden] IEE... | 7     | firewir... | B99C2286C9 |
| 104c:8025 |           | Texas I... | TSB82AA2 IEEE-1394b Link ... | 7     | firewir... | 37E5DABF3C |
| 104c:803a | 104d:902d | Texas I... | PCIxx12 OHCI Compliant IE... | 7     | firewir... | BD8A19714A |
| 1106:3044 | 1025:8010 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 7     | firewir... | A4DA822D7B |
| 1106:3044 | 14c0:0020 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 7     | firewir... | 0351248973 |
| 1180:0552 | 1043:1237 | Ricoh      | R5C552 IEEE 1394 Controller  | 7     | firewir... | C1DA7EE91F |
| 1180:0832 | 1025:011d | Ricoh      | R5C832 IEEE 1394 Controller  | 7     | firewir... | 2BD735CBDF |
| 1180:0832 | 104d:900e | Ricoh      | R5C832 IEEE 1394 Controller  | 7     | firewir... | 3284C77676 |
| 1180:0832 | 1179:ff1e | Ricoh      | R5C832 IEEE 1394 Controller  | 7     | firewir... | CFEBF5C5A2 |
| 1180:0832 | 17aa:3829 | Ricoh      | R5C832 IEEE 1394 Controller  | 7     | firewir... | 74624FF493 |
| 11c1:5811 | 1028:5811 | LSI        | FW322/323 [TrueFire] 1394... | 7     | firewir... | A72C60B73B |
| 1217:13f7 | 1028:049a | O2 Micro   | 1394 OHCI Compliant Host ... | 7     | firewir... | 5D67AE99E3 |
| 104c:8023 | 1849:8023 | Texas I... | TSB43AB22A IEEE-1394a-200... | 6     | firewir... | 34021FD6BD |
| 104c:803a | 103c:30aa | Texas I... | PCIxx12 OHCI Compliant IE... | 6     | firewir... | CF41AB5F1A |
| 104c:803a | 104d:81e6 | Texas I... | PCIxx12 OHCI Compliant IE... | 6     | firewir... | 50E5B9D6CA |
| 104c:803a | 104d:9005 | Texas I... | PCIxx12 OHCI Compliant IE... | 6     | firewir... | 858BD651B7 |
| 104c:803a | 104d:9015 | Texas I... | PCIxx12 OHCI Compliant IE... | 6     | firewir... | 3BEE1DDF68 |
| 104c:823f | 3412:7856 | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 6     | firewir... | 92F011CFCF |
| 1106:3044 | 1043:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 6     | firewir... | F479FA880E |

### Flash memory (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1524:0520 | 1025:0090 | ENE Tec... | FLASH memory: ENE Technol... | 31    |            | 719BE91D02 |
| 1524:0530 | 1025:0090 | ENE Tec... | ENE PCI Memory Stick Card... | 31    |            | 719BE91D02 |
| 1524:0551 | 1025:0090 | ENE Tec... | SD/MMC Card Reader Contro... | 31    | sdhci_pci  | 719BE91D02 |
| 1524:0520 | 1025:009f | ENE Tec... | FLASH memory: ENE Technol... | 23    |            | A28F7B2623 |
| 1524:0530 | 1025:009f | ENE Tec... | ENE PCI Memory Stick Card... | 23    |            | A28F7B2623 |
| 1524:0551 | 1025:009f | ENE Tec... | SD/MMC Card Reader Contro... | 23    | sdhci_pci  | A28F7B2623 |
| 1524:0720 | 1025:012e | ENE Tec... | Memory Stick Card Reader ... | 10    |            | 16BE592F4F |
| 1524:0730 | 1025:012e | ENE Tec... | ENE PCI Memory Stick Card... | 10    |            | 16BE592F4F |
| 1524:0751 | 1025:012e | ENE Tec... | ENE PCI Secure Digital / ... | 10    | sdhci_pci  | 16BE592F4F |
| 1524:0530 | 14c0:0020 | ENE Tec... | ENE PCI Memory Stick Card... | 7     |            | 0351248973 |
| 1524:0551 | 14c0:0020 | ENE Tec... | SD/MMC Card Reader Contro... | 7     | sdhci_pci  | 0351248973 |
| 1524:0520 | 1025:010f | ENE Tec... | FLASH memory: ENE Technol... | 6     |            | 0E64D71097 |
| 1524:0530 | 1025:010f | ENE Tec... | ENE PCI Memory Stick Card... | 6     |            | 0E64D71097 |
| 1524:0551 | 1025:010f | ENE Tec... | SD/MMC Card Reader Contro... | 6     | sdhci_pci  | 0E64D71097 |
| 1524:0530 | 1734:10c1 | ENE Tec... | ENE PCI Memory Stick Card... | 5     |            | AAAB07D2AE |
| 1524:0551 | 1734:10c1 | ENE Tec... | SD/MMC Card Reader Contro... | 5     | sdhci_pci  | AAAB07D2AE |
| 1106:9530 | 17aa:3891 | VIA Tec... | Secure Digital Memory Car... | 2     | via_sdmmc  | CE7524ED3B |
| 1524:0520 | 1179:ff01 | ENE Tec... | FLASH memory: ENE Technol... | 2     |            | C27B4CD3AF |
| 1524:0530 | 1179:ff01 | ENE Tec... | ENE PCI Memory Stick Card... | 2     |            | C27B4CD3AF |
| 1524:0551 | 1179:ff02 | ENE Tec... | SD/MMC Card Reader Contro... | 2     | sdhci_pci  | C27B4CD3AF |
| 1524:0720 | 1462:2fb3 | ENE Tec... | Memory Stick Card Reader ... | 2     |            | D6A996DA64 |
| 1524:0720 | 1462:2fbd | ENE Tec... | Memory Stick Card Reader ... | 2     |            | 6502446C70 |
| 1524:0730 | 1462:2fb3 | ENE Tec... | ENE PCI Memory Stick Card... | 2     |            | D6A996DA64 |
| 1524:0730 | 1462:2fbd | ENE Tec... | ENE PCI Memory Stick Card... | 2     |            | 6502446C70 |
| 1524:0730 | 1558:0669 | ENE Tec... | ENE PCI Memory Stick Card... | 2     |            | 647FD58075 |
| 1524:0751 | 1462:2fb3 | ENE Tec... | ENE PCI Secure Digital / ... | 2     | sdhci_pci  | D6A996DA64 |
| 1524:0751 | 1462:2fbd | ENE Tec... | ENE PCI Secure Digital / ... | 2     | sdhci_pci  | 6502446C70 |
| 1524:0751 | 1558:0669 | ENE Tec... | ENE PCI Secure Digital / ... | 2     | sdhci_pci  | 647FD58075 |
| 1524:0510 | 1524:0510 | ENE Tec... | CB710 Memory Card Reader ... | 1     | cb710      | 10AFC2AC6A |
| 1524:0520 | 1025:007a | ENE Tec... | FLASH memory: ENE Technol... | 1     |            | E4219525B9 |
| 1524:0530 | 1025:007a | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | E4219525B9 |
| 1524:0530 | 1734:10d7 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | CA3AC06D30 |
| 1524:0530 | 17aa:2079 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | EDAE63A429 |
| 1524:0551 | 1025:007a | ENE Tec... | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | E4219525B9 |
| 1524:0551 | 1734:10d7 | ENE Tec... | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | CA3AC06D30 |
| 1524:0551 | 17aa:2078 | ENE Tec... | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | EDAE63A429 |
| 1524:0720 | 1025:011b | ENE Tec... | Memory Stick Card Reader ... | 1     |            | B614684231 |
| 1524:0720 | 1025:012a | ENE Tec... | Memory Stick Card Reader ... | 1     |            | C95503E7D2 |
| 1524:0730 | 1025:011b | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | B614684231 |
| 1524:0730 | 1025:012a | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | C95503E7D2 |
| 1524:0730 | 1558:0664 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | 51E2E84C28 |
| 1524:0730 | 1558:0668 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | 41C9811E8B |
| 1524:0730 | 1558:0801 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | A28F10A223 |
| 1524:0751 | 1025:011b | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | B614684231 |
| 1524:0751 | 1025:012a | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | C95503E7D2 |
| 1524:0751 | 1558:0664 | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | 51E2E84C28 |
| 1524:0751 | 1558:0668 | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | 41C9811E8B |
| 1524:0751 | 1558:0801 | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | A28F10A223 |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1451 | 1022:1451 | AMD        | Family 17h (Models 00h-0f... | 190   |            | D084D64BDF |
| 1002:5a23 | 1002:5a23 | AMD        | RD890S/RD990 I/O Memory M... | 122   |            | B77180A9F5 |
| 1022:1419 | 1022:1419 | AMD        | Family 15h (Models 10h-1f... | 107   |            | 32E1C72BAA |
| 1022:1577 | 1022:1577 | AMD        | Family 15h (Models 60h-6f... | 64    |            | C61C9E33F6 |
| 1002:5a23 | 1462:7693 | AMD        | RD890S/RD990 I/O Memory M... | 47    |            | FEAA959521 |
| 1022:1423 | 1022:1423 | AMD        | Family 15h (Models 30h-3f... | 21    |            | 33CFE3D019 |
| 1022:1419 | 1462:7721 | AMD        | Family 15h (Models 10h-1f... | 19    |            | B801DD3F7D |
| 1022:1423 | 1462:7721 | AMD        | Family 15h (Models 30h-3f... | 19    |            | BA5B7B57D6 |
| 1022:1577 | 103c:8331 | AMD        | Family 15h (Models 60h-6f... | 12    |            | 9111BD09BB |
| 1022:1423 | 1043:85cb | AMD        | Family 15h (Models 30h-3f... | 11    |            | BE7AE862C6 |
| 1022:1419 | 1462:7895 | AMD        | Family 15h (Models 10h-1f... | 8     |            | FD55D656A8 |
| 1002:5a23 | 1462:7640 | AMD        | RD890S/RD990 I/O Memory M... | 6     |            | 23ACB95370 |
| 1002:5a23 | 1458:5000 | AMD        | RD890S/RD990 I/O Memory M... | 5     |            | 792BC1DD6F |
| 1002:5a23 | 1462:7974 | AMD        | RD890S/RD990 I/O Memory M... | 5     |            | 83FB735308 |
| 1022:1423 | 1462:7895 | AMD        | Family 15h (Models 30h-3f... | 5     |            | E1D561ABB4 |
| 1022:1419 | 1019:7c8d | AMD        | Family 15h (Models 10h-1f... | 3     |            | 8A37732F55 |
| 1022:1577 | 103c:81fa | AMD        | Family 15h (Models 60h-6f... | 3     |            | BAEB555043 |
| 1022:1419 | 1025:070b | AMD        | Family 15h (Models 10h-1f... | 2     |            | F083D73A9E |
| 1022:1419 | 1043:8526 | AMD        | Family 15h (Models 10h-1f... | 2     |            | 7EFEC12422 |
| 1022:1423 | 103c:812f | AMD        | Family 15h (Models 30h-3f... | 2     |            | FDB3CCB899 |
| 1022:1577 | 103c:80b5 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 2D0E845055 |
| 1022:1577 | 103c:80b6 | AMD        | Family 15h (Models 60h-6f... | 2     |            | BEA3C73273 |
| 1022:1577 | 103c:8355 | AMD        | Family 15h (Models 60h-6f... | 2     |            | D6F5348EC7 |
| 1022:1419 | 1462:7900 | AMD        | Family 15h (Models 10h-1f... | 1     |            | 985C8F6BB3 |
| 1022:1419 | 17aa:36a0 | AMD        | Family 15h (Models 10h-1f... | 1     |            | BA1A484E84 |
| 1022:1423 | 1462:7793 | AMD        | Family 15h (Models 30h-3f... | 1     |            | 54040FA02B |
| 1022:1423 | 17aa:368f | AMD        | Family 15h (Models 30h-3f... | 1     |            | 58DDD6F565 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0412 | 1458:d000 | Intel      | Xeon E3-1200 v3/4th Gen C... | 124   | i915       | DD4DA32934 |
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 118   | i915       | 4414412FCB |
| 8086:0102 | 1043:844d | Intel      | 2nd Generation Core Proce... | 96    | i915       | CF410274A0 |
| 8086:0102 | 1458:d000 | Intel      | 2nd Generation Core Proce... | 82    | i915       | A1E970227D |
| 8086:a011 | 1043:83ac | Intel      | Atom Processor D4xx/D5xx/... | 79    | i915       | B658C90327 |
| 8086:a012 | 1043:83ac | Intel      | Atom Processor D4xx/D5xx/... | 79    |            | B658C90327 |
| 8086:0412 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 78    | i915       | B61D174C21 |
| 10de:0a65 |           | Nvidia     | GT218 [GeForce 210]          | 73    | nouveau    | 7267B22360 |
| 10de:0615 |           | Nvidia     | G92 [GeForce GTS 250]        | 71    | nvidia     | 1114B40A02 |
| 10de:0622 |           | Nvidia     | G94 [GeForce 9600 GT]        | 68    | nvidia     | E3128E9139 |
| 10de:0de0 |           | Nvidia     | GF108 [GeForce GT 440]       | 67    | nouveau    | 88E3DD8AEA |
| 10de:0640 |           | Nvidia     | G96C [GeForce 9500 GT]       | 66    | nouveau    | 71B889E4FD |
| 8086:0152 | 1458:d000 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 66    | i915       | 9FF94DE707 |
| 10de:128b | 1462:8c93 | Nvidia     | GK208B [GeForce GT 710]      | 65    | nouveau    | 606AACED27 |
| 8086:0166 | 1025:0647 | Intel      | 3rd Gen Core processor Gr... | 63    | i915       | 6478022B75 |
| 8086:29c2 | 1043:82b0 | Intel      | 82G33/G31 Express Integra... | 63    | i915       | 85261DC7A2 |
| 10de:0614 |           | Nvidia     | G92 [GeForce 9800 GT]        | 60    | nouveau    | 54F8BAB8A3 |
| 10de:1244 |           | Nvidia     | GF116 [GeForce GTX 550 Ti]   | 58    | nouveau    | 0414258B09 |
| 8086:2e32 | 1043:836d | Intel      | 4 Series Chipset Integrat... | 58    | i915       | D81A6BB2A7 |
| 8086:0402 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 57    | i915       | 08D84A1FF9 |
| 10de:0ca3 |           | Nvidia     | GT215 [GeForce GT 240]       | 56    | nvidia     | 20093DA7FB |
| 1002:9616 | 1043:8388 | AMD        | RS780L [Radeon 3000]         | 55    | radeon     | D569843A2D |
| 8086:0106 | 1025:0649 | Intel      | 2nd Generation Core Proce... | 55    | i915       | F28D18F3E9 |
| 8086:2772 | 1043:817a | Intel      | 82945G/GZ Integrated Grap... | 54    | i915       | C701909BC8 |
| 10de:0de1 |           | Nvidia     | GF108 [GeForce GT 430]       | 52    | nouveau    | 4B83E684CA |
| 10de:0f00 | 1569:0f00 | Nvidia     | GF108 [GeForce GT 630]       | 52    | nouveau    | F99AFC78BD |
| 8086:0f31 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 52    | i915       | CC7193A7B9 |
| 10de:0fc6 | 1569:0fc6 | Nvidia     | GK107 [GeForce GTX 650]      | 51    | nvidia     | 230E4F00BA |
| 8086:0046 | 17aa:215a | Intel      | Core Processor Integrated... | 51    | i915       | DA5E944C6C |
| 8086:29c2 | 1849:29c2 | Intel      | 82G33/G31 Express Integra... | 51    | i915       | 42C519E784 |
| 8086:2a02 | 1025:011f | Intel      | Mobile GM965/GL960 Integr... | 51    | i915       | 7387D70AD5 |
| 8086:2a03 | 1025:011f | Intel      | Mobile GM965/GL960 Integr... | 51    |            | 7387D70AD5 |
| 8086:a011 | 1025:0349 | Intel      | Atom Processor D4xx/D5xx/... | 51    | i915       | 8CE41DB531 |
| 8086:a012 | 1025:0349 | Intel      | Atom Processor D4xx/D5xx/... | 51    |            | 8CE41DB531 |
| 8086:0166 | 17aa:5003 | Intel      | 3rd Gen Core processor Gr... | 50    | i915       | CE3DDF28FC |
| 8086:0f31 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 49    | i915       | CEAC334581 |
| 8086:2a42 | 17aa:3a02 | Intel      | Mobile 4 Series Chipset I... | 49    | i915       | 601D53F9EB |
| 8086:2a43 | 17aa:3a02 | Intel      | Mobile 4 Series Chipset I... | 49    |            | 601D53F9EB |
| 8086:0152 | 1043:844d | Intel      | Xeon E3-1200 v2/3rd Gen C... | 48    | i915       | 154C64D953 |
| 8086:0156 | 17aa:3977 | Intel      | 3rd Gen Core processor Gr... | 48    | i915       | 4FAA6112C3 |
| 8086:2a42 | 1043:1862 | Intel      | Mobile 4 Series Chipset I... | 48    | i915       | 38190AD2E1 |
| 8086:2a43 | 1043:1862 | Intel      | Mobile 4 Series Chipset I... | 48    |            | 38190AD2E1 |
| 8086:2a42 | 17aa:20e4 | Intel      | Mobile 4 Series Chipset I... | 47    | i915       | FDAB3CF92F |
| 8086:2a43 | 17aa:20e4 | Intel      | Mobile 4 Series Chipset I... | 47    |            | FDAB3CF92F |
| 8086:0f31 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 46    | i915       | 0994A3EEB3 |
| 8086:0116 | 1025:0504 | Intel      | 2nd Generation Core Proce... | 45    | i915       | 8579BA1B16 |
| 8086:0166 | 17aa:3977 | Intel      | 3rd Gen Core processor Gr... | 44    | i915       | B19B3500F2 |
| 10de:03d6 | 1849:03d6 | Nvidia     | C61 [GeForce 7025 / nForc... | 42    | nouveau    | 88EC731DFB |
| 8086:0166 | 1043:124d | Intel      | 3rd Gen Core processor Gr... | 42    | i915       | 0F8CE4DCC0 |
| 8086:0be1 | 1043:84a9 | Intel      | Atom Processor D2xxx/N2xx... | 42    | gma500_gfx | 6A0513EC8D |
| 8086:2e32 | 1458:d000 | Intel      | 4 Series Chipset Integrat... | 41    | i915       | D0D6CD20B1 |
| 10de:0402 |           | Nvidia     | G84 [GeForce 8600 GT]        | 40    | nouveau    | F2DFFD30F5 |
| 8086:0152 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 40    | i915       | E3C3739395 |
| 8086:0166 | 1025:064b | Intel      | 3rd Gen Core processor Gr... | 40    | i915       | E67DFC255A |
| 8086:29c2 | 1458:d000 | Intel      | 82G33/G31 Express Integra... | 40    | i915       | 22D8D62C57 |
| 8086:0106 | 17aa:3975 | Intel      | 2nd Generation Core Proce... | 39    | i915       | 05D969D697 |
| 8086:1912 | 1043:8694 | Intel      | HD Graphics 530              | 39    | i915       | 99614383EB |
| 1002:68e4 | 17aa:397a | AMD        | Robson CE [Radeon HD 6370... | 38    | radeon     | A7618091FB |
| 1002:9616 | 1458:d000 | AMD        | RS780L [Radeon 3000]         | 37    | radeon     | ED68722348 |
| 8086:2772 | 1458:d000 | Intel      | 82945G/GZ Integrated Grap... | 37    | i915       | 080AE7C292 |
| 8086:5912 | 1043:8694 | Intel      | HD Graphics 630              | 37    | i915       | BD3CFBCE71 |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics                  | 37    | i915       | 1579402536 |
| 10de:0a65 | 1462:8094 | Nvidia     | GT218 [GeForce 210]          | 36    | nvidia     | FA683DF592 |
| 10de:11c0 | 1569:11c0 | Nvidia     | GK106 [GeForce GTX 660]      | 36    | nvidia     | E4A1AC8DFE |
| 8086:0116 | 1043:1682 | Intel      | 2nd Generation Core Proce... | 36    | i915       | FB3C3B769A |
| 8086:041e | 1458:d000 | Intel      | 4th Generation Core Proce... | 35    | i915       | BEBF195E43 |
| 8086:0156 | 17aa:5011 | Intel      | 3rd Gen Core processor Gr... | 34    | i915       | 65D329A2C6 |
| 8086:2a02 | 17aa:20b5 | Intel      | Mobile GM965/GL960 Integr... | 34    | i915       | 037CAC7A3D |
| 8086:2a03 | 17aa:20b5 | Intel      | Mobile GM965/GL960 Integr... | 34    |            | 037CAC7A3D |
| 1002:5a62 | 1043:1402 | AMD        | RC410M [Mobility Radeon X... | 33    | radeon     | 54C92BF69C |
| 1002:68f9 | 174b:e164 | AMD        | Cedar [Radeon HD 5000/600... | 33    | radeon     | EBB5316694 |
| 10de:0641 |           | Nvidia     | G96C [GeForce 9400 GT]       | 33    | nvidia     | 54231260FF |
| 10de:0a20 |           | Nvidia     | GT216 [GeForce GT 220]       | 33    | nouveau    | EF3F0A5B2B |
| 10de:0dc4 |           | Nvidia     | GF106 [GeForce GTS 450]      | 33    | nvidia     | DEB6214FDD |
| 10de:0df5 | 1028:04ca | Nvidia     | GF108M [GeForce GT 525M]     | 33    | nouveau    | C0868A2B0C |
| 8086:0402 | 1458:d000 | Intel      | Xeon E3-1200 v3/4th Gen C... | 33    | i915       | 7B12481536 |
| 8086:041e | 1043:8534 | Intel      | 4th Generation Core Proce... | 33    | i915       | 2656A5F4E6 |
| 8086:0f31 | 17aa:3909 | Intel      | Atom Processor Z36xxx/Z37... | 33    | i915       | EE1CFF7014 |
| 1002:68e0 | 1043:1bf2 | AMD        | Park [Mobility Radeon HD ... | 32    | radeon     | 13D9E84E8D |
| 8086:0a16 | 1025:0866 | Intel      | Haswell-ULT Integrated Gr... | 32    | i915       | 1C77D7A584 |
| 10de:1051 | 144d:c0b6 | Nvidia     | GF119M [GeForce GT 520MX]    | 31    | nouveau    | 616616B60F |
| 10de:1140 | 1025:0691 | Nvidia     | GF117M [GeForce 610M/710M... | 31    | nouveau    | E67DFC255A |
| 10de:1380 | 1043:84bb | Nvidia     | GM107 [GeForce GTX 750 Ti]   | 31    | nvidia     | 32D6CC8A86 |
| 8086:0102 | 1849:0102 | Intel      | 2nd Generation Core Proce... | 31    | i915       | DCC0E8E5F5 |
| 1002:6840 | 144d:c0da | AMD        | Thames [Radeon HD 7500M/7... | 30    | radeon     | A06125BD54 |
| 8086:0116 | 144d:c0b6 | Intel      | 2nd Generation Core Proce... | 30    | i915       | 616616B60F |
| 8086:0152 | 1849:0152 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 30    | i915       | 3D8C4FEBC3 |
| 1002:15dd | 1043:876b | AMD        | Raven Ridge [Radeon Vega ... | 29    | amdgpu     | 76E2078928 |
| 10de:0f00 | 1458:3544 | Nvidia     | GF108 [GeForce GT 630]       | 29    | nouveau    | 9204CB3BAC |
| 10de:0fc1 | 1569:0fc1 | Nvidia     | GK107 [GeForce GT 640]       | 29    | nouveau    | ADD4F52268 |
| 10de:11c0 | 1458:354e | Nvidia     | GK106 [GeForce GTX 660]      | 29    | nouveau    | 0FA01E4D66 |
| 8086:0116 | 1043:1652 | Intel      | 2nd Generation Core Proce... | 29    | i915       | 6B25B8982D |
| 8086:0f31 | 1043:14dd | Intel      | Atom Processor Z36xxx/Z37... | 29    | i915       | 8D51E5FEC5 |
| 8086:a011 | 1025:0590 | Intel      | Atom Processor D4xx/D5xx/... | 29    | i915       | D5A624C8FE |
| 8086:a011 | 144d:c072 | Intel      | Atom Processor D4xx/D5xx/... | 29    | i915       | 3A0FEA4700 |
| 8086:a012 | 1025:0590 | Intel      | Atom Processor D4xx/D5xx/... | 29    |            | D5A624C8FE |
| 8086:a012 | 144d:c072 | Intel      | Atom Processor D4xx/D5xx/... | 29    |            | 3A0FEA4700 |
| 10de:0322 |           | Nvidia     | NV34 [GeForce FX 5200]       | 28    | nouveau    | C3F87286B5 |
| 10de:1051 | 144d:c606 | Nvidia     | GF119M [GeForce GT 520MX]    | 28    | nouveau    | 0BFEB87324 |
| 10de:1058 | 1043:1652 | Nvidia     | GF119M [GeForce 610M]        | 28    | nouveau    | 6B25B8982D |

### Input device controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1102:7002 | 1102:0020 | Creativ... | SB Live! Game Port           | 82    | emu10k1_gp | 6D9668A464 |
| 1102:7003 | 1102:0040 | Creativ... | SB Audigy Game Port          | 52    | emu10k1_gp | C80D56CB77 |
| 1102:7003 | 1102:0060 | Creativ... | SB Audigy Game Port          | 12    | emu10k1_gp | 7A74EB0F6F |
| 1319:0802 | 1319:1319 | Fortemedia | Xwave QS3000A [FM801 game... | 6     | fm801_gp   | 6AB359DC43 |
| 1102:7004 | 1102:1003 | Creativ... | [SB Live! Value] Input de... | 1     | emu10k1_gp | B7C8E17F50 |
| 1102:7005 | 1102:1002 | Creativ... | SB Audigy LS Game Port       | 1     | emu10k1_gp | A8AFE9E221 |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 136   |            | 123447177A |
| 1022:1451 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 113   |            | 4A2455EAE6 |
| 1022:1577 | 103c:8330 | AMD        | Family 15h (Models 60h-6f... | 27    |            | D32B7275C3 |
| 1022:1577 | 1025:1192 | AMD        | Family 15h (Models 60h-6f... | 22    |            | 0D71E52A34 |
| 1022:15d1 | 103c:84ae | AMD        | Raven/Raven2 IOMMU           | 14    |            | E8755C7EF8 |
| 1022:15d1 | 17aa:3804 | AMD        | Raven/Raven2 IOMMU           | 9     |            | F6996F43AE |
| 1022:1577 | 103c:84ac | AMD        | Family 15h (Models 60h-6f... | 8     |            | 44E78B4D3F |
| 1022:1451 | 1462:7a38 | AMD        | Family 17h (Models 00h-0f... | 6     |            | 4B9FC100D8 |
| 1022:15d1 | 17aa:3809 | AMD        | Raven/Raven2 IOMMU           | 6     |            | 52036BD95B |
| 1022:1451 | 1028:07ee | AMD        | Family 17h (Models 00h-0f... | 5     |            | DB32491DFE |
| 1022:15d1 | 103c:84d2 | AMD        | Raven/Raven2 IOMMU           | 5     |            | DEFB86D43A |
| 1022:1577 | 103c:81f9 | AMD        | Family 15h (Models 60h-6f... | 4     |            | 7FAA2ABF56 |
| 1022:1577 | 103c:8345 | AMD        | Family 15h (Models 60h-6f... | 4     |            | 7E3B6FA95F |
| 1022:1577 | 17aa:380e | AMD        | Family 15h (Models 60h-6f... | 4     |            | C19D82302D |
| 1022:1577 | 1025:109f | AMD        | Family 15h (Models 60h-6f... | 3     |            | 41E017C4AE |
| 1022:1577 | 1028:087e | AMD        | Family 15h (Models 60h-6f... | 3     |            | 5DA2258C77 |
| 1022:15d1 | 1025:125c | AMD        | Raven/Raven2 IOMMU           | 3     |            | 7E4C5212D0 |
| 1022:15d1 | 1028:0812 | AMD        | Raven/Raven2 IOMMU           | 3     |            | 2EF740F66D |
| 1022:15d1 | 103c:84e7 | AMD        | Raven/Raven2 IOMMU           | 3     |            | 788CB4019C |
| 1022:15d1 | 103c:85ea | AMD        | Raven/Raven2 IOMMU           | 3     |            | D7977A3B0E |
| 1022:1419 | 1019:7c90 | AMD        | Family 15h (Models 10h-1f... | 2     |            | FFB74FCE84 |
| 1022:1423 | 1025:0904 | AMD        | Family 15h (Models 30h-3f... | 2     |            | 3458AC22F5 |
| 1022:1577 | 1025:1099 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 326E32CFB9 |
| 1022:1577 | 1025:1201 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 1D59285089 |
| 1022:1577 | 1028:0769 | AMD        | Family 15h (Models 60h-6f... | 2     |            | AA9862538A |
| 1022:1577 | 1028:076b | AMD        | Family 15h (Models 60h-6f... | 2     |            | C9DF0EF9CD |
| 1022:1577 | 1028:07e3 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 4EB59BF315 |
| 1022:1577 | 103c:80b0 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 3F7F72D7A2 |
| 1022:1577 | 103c:8324 | AMD        | Family 15h (Models 60h-6f... | 2     |            | FEEB8EA6F8 |
| 1022:1577 | 103c:8333 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 1C1D0D6198 |
| 1022:1577 | 103c:84a0 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 908E49B930 |
| 1022:1577 | 103c:84d0 | AMD        | Family 15h (Models 60h-6f... | 2     |            | C77FA19C2B |
| 1022:1577 | 103c:84d1 | AMD        | Family 15h (Models 60h-6f... | 2     |            | E3FF835EA0 |
| 1022:15d1 | 1025:1233 | AMD        | Raven/Raven2 IOMMU           | 2     |            | 856A212CAA |
| 1022:15d1 | 103c:8496 | AMD        | Raven/Raven2 IOMMU           | 2     |            | F720A735A8 |
| 1002:5a23 | 103c:3324 | AMD        | RD890S/RD990 I/O Memory M... | 1     |            | 7CE46A749E |
| 1002:5a23 | 1462:7893 | AMD        | RD890S/RD990 I/O Memory M... | 1     |            | 837F3B9280 |
| 1022:1419 | 103c:1850 | AMD        | Family 15h (Models 10h-1f... | 1     |            | C6E0706214 |
| 1022:1419 | 103c:2215 | AMD        | Family 15h (Models 10h-1f... | 1     |            | 1B3213CA06 |
| 1022:1419 | 1462:7793 | AMD        | Family 15h (Models 10h-1f... | 1     |            | C3610DBBF7 |
| 1022:1423 | 1019:99d3 | AMD        | Family 15h (Models 30h-3f... | 1     |            | CFCBE45B0D |
| 1022:1423 | 1019:9a62 | AMD        | Family 15h (Models 30h-3f... | 1     |            | 06FB58E8EE |
| 1022:1423 | 1019:9ac9 | AMD        | Family 15h (Models 30h-3f... | 1     |            | BED1921035 |
| 1022:1423 | 103c:2215 | AMD        | Family 15h (Models 30h-3f... | 1     |            | 7CA812503F |
| 1022:1423 | 103c:2263 | AMD        | Family 15h (Models 30h-3f... | 1     |            | A07F8E8315 |
| 1022:1423 | 103c:22a9 | AMD        | Family 15h (Models 30h-3f... | 1     |            | FE059A167E |
| 1022:1423 | 1462:7903 | AMD        | Family 15h (Models 30h-3f... | 1     |            | EADCB61E9F |
| 1022:1451 | 1019:9ce5 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 06776696F3 |
| 1022:1451 | 1028:089a | AMD        | Family 17h (Models 00h-0f... | 1     |            | 451A733603 |
| 1022:1451 | 1462:7a40 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 515A7DFA4F |
| 1022:1451 | 1462:7b85 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 29C3842F1D |
| 1022:1451 | 1462:7b86 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 73F23254C0 |
| 1022:1451 | 1462:7b89 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 63314DCB31 |
| 1022:1481 | 1022:1481 | AMD        | Starship/Matisse IOMMU       | 1     |            | 35B960D525 |
| 1022:1577 | 1025:1087 | AMD        | Family 15h (Models 60h-6f... | 1     |            | 9A0D26C5FB |
| 1022:1577 | 1025:1372 | AMD        | Family 15h (Models 60h-6f... | 1     |            | F7313E11F8 |
| 1022:1577 | 103c:80af | AMD        | Family 15h (Models 60h-6f... | 1     |            | 6186029A96 |
| 1022:1577 | 103c:81aa | AMD        | Family 15h (Models 60h-6f... | 1     |            | D103A0F533 |
| 1022:1577 | 103c:81fd | AMD        | Family 15h (Models 60h-6f... | 1     |            | 7C0F244462 |
| 1022:1577 | 103c:8346 | AMD        | Family 15h (Models 60h-6f... | 1     |            | B53E43FC3C |
| 1022:1577 | 103c:8353 | AMD        | Family 15h (Models 60h-6f... | 1     |            | BB4FD376C4 |
| 1022:1577 | 103c:8354 | AMD        | Family 15h (Models 60h-6f... | 1     |            | C75D45BEC4 |
| 1022:1577 | 103c:8357 | AMD        | Family 15h (Models 60h-6f... | 1     |            | F017BDEDF1 |
| 1022:1577 | 103c:84ad | AMD        | Family 15h (Models 60h-6f... | 1     |            | CB1771B144 |
| 1022:1577 | 103c:84e5 | AMD        | Family 15h (Models 60h-6f... | 1     |            | B92FF40DA0 |
| 1022:1577 | 103c:85bb | AMD        | Family 15h (Models 60h-6f... | 1     |            | A6C908654C |
| 1022:1577 | 1043:8719 | AMD        | Family 15h (Models 60h-6f... | 1     |            | 13D633A029 |
| 1022:1577 | 17aa:3100 | AMD        | Family 15h (Models 60h-6f... | 1     |            | 5BD277D767 |
| 1022:1577 | 17aa:36ec | AMD        | Family 15h (Models 60h-6f... | 1     |            | C586E918F9 |
| 1022:1577 | 17aa:3806 | AMD        | Family 15h (Models 60h-6f... | 1     |            | B9FC5DC357 |
| 1022:15d1 | 1028:08d7 | AMD        | Raven/Raven2 IOMMU           | 1     |            | ADFAD3DD99 |
| 1022:15d1 | 103c:8497 | AMD        | Raven/Raven2 IOMMU           | 1     |            | 314C52C853 |
| 1022:15d1 | 103c:85b3 | AMD        | Raven/Raven2 IOMMU           | 1     |            | 766B0474A3 |
| 1022:15d1 | 103c:8615 | AMD        | Raven/Raven2 IOMMU           | 1     |            | 048229855F |
| 1022:15d1 | 17aa:3802 | AMD        | Raven/Raven2 IOMMU           | 1     |            | 878BBF3E54 |
| 8086:1f16 | 1849:1f16 | Intel      | Atom processor C2000 RCEC    | 1     |            | E398D38584 |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816c | 1019:81ea | Realtek... | Virtual IPMI                 | 1     |            | 06FB58E8EE |
| 10ec:816c | 103c:83da | Realtek... | Virtual IPMI                 | 1     |            | 607DEE6BBB |
| 10ec:816c | 103c:8401 | Realtek... | Virtual IPMI                 | 1     |            | F2F88AAA9D |
| 10ec:816c | 17aa:511f | Realtek... | Virtual IPMI                 | 1     |            | 259A32BE33 |
| 10ec:816c | 17aa:5122 | Realtek... | Virtual IPMI                 | 1     |            | 7CCAC31D71 |
| 10ec:816c | 17aa:5125 | Realtek... | Virtual IPMI                 | 1     |            | 7A1C4A299D |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 103c:3302 | 103c:3305 | Hewlett... | Integrated Lights-Out Sta... | 5     | ipmi_si    | 6806624961 |
| 10ec:816c | 1458:e000 | Realtek... | Virtual IPMI                 | 3     | ipmi_si    | E528F92A7A |
| 10ec:816c | 17aa:3089 | Realtek... | Virtual IPMI                 | 3     | ipmi_si    | D9A1939AB2 |
| 10ec:816c | 1025:078b | Realtek... | Virtual IPMI                 | 1     |            | 087F924E20 |
| 10ec:816c | 10ec:8168 | Realtek... | Virtual IPMI                 | 1     | ipmi_si    | E505745421 |
| 10ec:816c | 1734:1178 | Realtek... | Virtual IPMI                 | 1     |            | 102A89A278 |
| 10ec:816c | 17aa:30b2 | Realtek... | Virtual IPMI                 | 1     | ipmi_si    | 36635F76F9 |
| 8086:108e | 8086:0000 | Intel      | 82573E KCS (Active Manage... | 1     | ipmi_si    | 1960567A11 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a121 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 198   |            | 99614383EB |
| 10de:03f5 | 1849:03eb | Nvidia     | MCP61 Memory Controller      | 194   |            | 816FE60D2D |
| 10de:03e2 | 1849:03e2 | Nvidia     | MCP61 Host Bridge            | 180   |            | 4E526BB85F |
| 8086:a36f | 8086:7270 | Intel      | Cannon Lake PCH Shared SRAM  | 115   |            | D1EC1DAC8F |
| 10de:03f5 | 1458:0c11 | Nvidia     | MCP61 Memory Controller      | 105   |            | BBF6B6F632 |
| 8086:a121 | 1458:5001 | Intel      | 100 Series/C230 Series Ch... | 103   |            | 0BF4CAF942 |
| 10de:03ea | 1043:8234 | Nvidia     | MCP61 Memory Controller      | 72    |            | 2A30939325 |
| 10de:03f5 | 1043:8234 | Nvidia     | MCP61 Memory Controller      | 72    |            | 2A30939325 |
| 10de:03ea | 10de:cb84 | Nvidia     | MCP61 Memory Controller      | 68    |            | 11D0376265 |
| 10de:03e2 | 1043:83a4 | Nvidia     | MCP61 Host Bridge            | 66    |            | 3248DFD987 |
| 10de:03f5 | 1043:83a4 | Nvidia     | MCP61 Memory Controller      | 66    |            | 3248DFD987 |
| 8086:a2a1 | 1458:5001 | Intel      | 200 Series/Z370 Chipset F... | 63    |            | AAD0551E27 |
| 10de:03ea | 1458:5001 | Nvidia     | MCP61 Memory Controller      | 61    |            | D083D84DB1 |
| 8086:a2a1 | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 54    |            | 7F1F084A4F |
| 10de:005e | 1043:815a | Nvidia     | CK804 Memory Controller      | 52    |            | C92DC5D0CF |
| 10de:0a88 |           | Nvidia     | MCP79 Memory Controller      | 45    |            | 9F753AC669 |
| 10de:03e2 | 1458:5001 | Nvidia     | MCP61 Host Bridge            | 44    |            | BBF6B6F632 |
| 10de:03f5 | 1462:7309 | Nvidia     | MCP61 Memory Controller      | 42    |            | 11D0376265 |
| 8086:9d21 | 8086:7270 | Intel      | Sunrise Point-LP PMC         | 42    |            | 44204F310C |
| 10de:0a89 |           | Nvidia     | MCP79 Memory Controller      | 38    |            | 9F753AC669 |
| 10de:0aa4 |           | Nvidia     | MCP79 Memory Controller      | 38    |            | 9F753AC669 |
| 10de:0a88 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 37    |            | C4A5E49D47 |
| 10de:0a89 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 37    |            | C4A5E49D47 |
| 8086:a121 | 1849:a121 | Intel      | 100 Series/C230 Series Ch... | 37    |            | BCB3EF58AB |
| 10de:03f5 | 1565:3407 | Nvidia     | MCP61 Memory Controller      | 36    |            | E327FDD558 |
| 10de:0444 | 1462:7369 | Nvidia     | MCP65 Memory Controller      | 36    |            | C46668413C |
| 10de:0445 | 1462:7369 | Nvidia     | MCP65 Memory Controller      | 36    |            | C46668413C |
| 10de:0a98 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 35    |            | 9F753AC669 |
| 10de:0568 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 33    |            | 88719BBDD6 |
| 10de:0751 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 33    |            | 88719BBDD6 |
| 10de:0754 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 33    |            | 88719BBDD6 |
| 10de:0369 | 1043:8239 | Nvidia     | MCP55 Memory Controller      | 32    |            | 4EA0694850 |
| 8086:a36f | 1043:8694 | Intel      | Cannon Lake PCH Shared SRAM  | 32    |            | 68BABB69CB |
| 10de:0541 | 10de:cb84 | Nvidia     | MCP67 Memory Controller      | 27    |            | F7695ADD11 |
| 8086:9d21 | 1025:1193 | Intel      | Sunrise Point-LP PMC         | 26    | intel_p... | 141D7917FF |
| 10de:03a9 |           | Nvidia     | C55 Memory Controller        | 24    |            | C7934C20A0 |
| 10de:03aa |           | Nvidia     | C55 Memory Controller        | 24    |            | C7934C20A0 |
| 10de:03ab |           | Nvidia     | C55 Memory Controller        | 24    |            | C7934C20A0 |
| 10de:03b4 |           | Nvidia     | C55 Memory Controller        | 24    |            | C7934C20A0 |
| 10de:03bc |           | Nvidia     | C55 Memory Controller        | 24    |            | C7934C20A0 |
| 10de:03a8 |           | Nvidia     | C55 Memory Controller        | 23    |            | C7934C20A0 |
| 10de:03ac |           | Nvidia     | C55 Memory Controller        | 23    |            | C7934C20A0 |
| 10de:03ad |           | Nvidia     | C55 Memory Controller        | 23    |            | C7934C20A0 |
| 10de:03ae |           | Nvidia     | C55 Memory Controller        | 23    |            | C7934C20A0 |
| 10de:03af |           | Nvidia     | C55 Memory Controller        | 23    |            | C7934C20A0 |
| 10de:03b0 |           | Nvidia     | C55 Memory Controller        | 23    |            | C7934C20A0 |
| 10de:03b1 |           | Nvidia     | C55 Memory Controller        | 23    |            | C7934C20A0 |
| 10de:03b2 |           | Nvidia     | C55 Memory Controller        | 23    |            | C7934C20A0 |
| 10de:03b3 |           | Nvidia     | C55 Memory Controller        | 23    |            | C7934C20A0 |
| 10de:03b5 |           | Nvidia     | C55 Memory Controller        | 23    |            | C7934C20A0 |
| 10de:03b6 |           | Nvidia     | C55 Memory Controller        | 23    |            | C7934C20A0 |
| 10de:03ba |           | Nvidia     | C55 Memory Controller        | 23    |            | C7934C20A0 |
| 8086:9d21 | 1025:1085 | Intel      | Sunrise Point-LP PMC         | 23    | intel_p... | AE1CE65D11 |
| 8086:a2a1 | 1043:872f | Intel      | 200 Series/Z370 Chipset F... | 23    |            | 3B3DC1A093 |
| 8086:a2a1 | 1849:a2a1 | Intel      | 200 Series/Z370 Chipset F... | 23    |            | CACD7C9489 |
| 10de:0568 | 1849:0568 | Nvidia     | MCP78S [GeForce 8200] Mem... | 21    |            | AC2555A764 |
| 10de:0751 | 1849:0751 | Nvidia     | MCP78S [GeForce 8200] Mem... | 21    |            | AC2555A764 |
| 10de:0754 | 1849:0754 | Nvidia     | MCP78S [GeForce 8200] Mem... | 21    |            | AC2555A764 |
| 8086:9d21 | 1025:115f | Intel      | Sunrise Point-LP PMC         | 21    | intel_p... | E4B342382F |
| 8086:a121 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 21    |            | BD6DC70775 |
| 8086:9d21 | 17aa:3816 | Intel      | Sunrise Point-LP PMC         | 20    |            | 005771EDFD |
| 8086:a36f | 1849:a36f | Intel      | Cannon Lake PCH Shared SRAM  | 20    |            | 39C0FBE126 |
| 8086:9d21 | 8086:9d21 | Intel      | Sunrise Point-LP PMC         | 19    | intel_p... | 6813C9B2D3 |
| 10de:0369 | 1462:7250 | Nvidia     | MCP55 Memory Controller      | 18    |            | 005023EE9D |
| 10de:0568 |           | Nvidia     | MCP78S [GeForce 8200] Mem... | 18    |            | 96600BDB45 |
| 10de:0751 | 10de:cb84 | Nvidia     | MCP78S [GeForce 8200] Mem... | 18    |            | 96600BDB45 |
| 10de:0aa4 | 1043:1cf7 | Nvidia     | MCP79 Memory Controller      | 18    |            | F0A1399A3F |
| 8086:9d21 | 103c:832a | Intel      | Sunrise Point-LP PMC         | 18    |            | 8B699D7E6C |
| 10de:0270 | 1043:81c0 | Nvidia     | MCP51 Host Bridge            | 17    |            | 15B9CC8D28 |
| 10de:03ea | 1565:3407 | Nvidia     | MCP61 Memory Controller      | 17    |            | C67AE8B7E3 |
| 10de:0547 | 1025:0126 | Nvidia     | MCP67 Memory Controller      | 17    |            | F7695ADD11 |
| 8086:9d21 | 1043:1a00 | Intel      | Sunrise Point-LP PMC         | 17    | intel_p... | BEB89C26D9 |
| 8086:9d21 | 17aa:3872 | Intel      | Sunrise Point-LP PMC         | 17    |            | 240FE2C985 |
| 10de:0754 | 1458:5001 | Nvidia     | MCP78S [GeForce 8200] Mem... | 16    |            | 9D06F70055 |
| 8086:444e | 8086:444e | Intel      | Turbo Memory Controller      | 16    |            | 253B1DAE47 |
| 8086:a121 | 1462:7a15 | Intel      | 100 Series/C230 Series Ch... | 16    |            | 7C7D8F8CB6 |
| 8086:a121 | 17aa:3802 | Intel      | 100 Series/C230 Series Ch... | 16    |            | 9A9BC31C3D |
| 8086:a1a1 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    |            | 4391DFF8D2 |
| 10de:0272 | 1043:81c0 | Nvidia     | MCP51 Memory Controller 0    | 15    |            | 15B9CC8D28 |
| 10de:027e | 1043:81c0 | Nvidia     | C51 Memory Controller 2      | 15    |            | 15B9CC8D28 |
| 10de:027f | 1043:81c0 | Nvidia     | C51 Memory Controller 3      | 15    |            | 15B9CC8D28 |
| 10de:02f0 | 1043:81c0 | Nvidia     | C51 Host Bridge              | 15    |            | 15B9CC8D28 |
| 10de:02f8 | 1043:81c0 | Nvidia     | C51 Memory Controller 5      | 15    |            | 15B9CC8D28 |
| 10de:02f9 | 1043:81c0 | Nvidia     | C51 Memory Controller 4      | 15    |            | 15B9CC8D28 |
| 10de:02fe | 1043:81c0 | Nvidia     | C51 Memory Controller 1      | 15    |            | 15B9CC8D28 |
| 10de:02ff | 1043:81c0 | Nvidia     | C51 Host Bridge              | 15    |            | 15B9CC8D28 |
| 10de:0369 | 1043:cb84 | Nvidia     | MCP55 Memory Controller      | 15    |            | BC336B5882 |
| 10de:0369 | 1458:5001 | Nvidia     | MCP55 Memory Controller      | 15    |            | 0CCA59B833 |
| 10de:0568 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] Mem... | 15    |            | 265A212FDC |
| 10de:0754 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] Mem... | 15    |            | 265A212FDC |
| 8086:9d21 | 103c:8079 | Intel      | Sunrise Point-LP PMC         | 15    |            | B8392B7335 |
| 10de:02fa | 1043:81c0 | Nvidia     | C51 Memory Controller 0      | 14    |            | 15B9CC8D28 |
| 10de:03ea | 103c:2a6c | Nvidia     | MCP61 Memory Controller      | 14    |            | 579C5E3CDC |
| 10de:03ea | 1849:03ea | Nvidia     | MCP61 Memory Controller      | 14    |            | 816FE60D2D |
| 10de:03f5 | 103c:2a6c | Nvidia     | MCP61 Memory Controller      | 14    |            | 579C5E3CDC |
| 10de:03f5 | 1462:7597 | Nvidia     | MCP61 Memory Controller      | 14    |            | A0A7F774C4 |
| 8086:9d21 | 1028:07e6 | Intel      | Sunrise Point-LP PMC         | 14    | intel_p... | 5D2CB1E1B0 |
| 10de:0270 | 1043:81bc | Nvidia     | MCP51 Host Bridge            | 13    |            | C7934C20A0 |
| 10de:027e | 10de:027e | Nvidia     | C51 Memory Controller 2      | 13    |            | D1F4A0FF97 |
| 10de:027f | 10de:027f | Nvidia     | C51 Memory Controller 3      | 13    |            | D1F4A0FF97 |

### Modem (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 11c1:044c | 11c1:044c | LSI        | LT WinModem                  | 12    |            | E75F4538BC |
| 8086:266d | 14f1:5423 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 10    | snd_int... | 23F9D951DE |
| 8086:24c6 | 14f1:5422 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 8     | snd_int... | 0504CC20A9 |
| 8086:266d | 1179:0001 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 8     | snd_int... | D5D7DAB02F |
| 1057:3052 | 1057:3020 | Motorola   | SM56 Data Fax Modem          | 7     |            | D3B45DE297 |
| 1106:3068 |           | VIA Tec... | AC'97 Modem Controller       | 7     | snd_via... | E75F4538BC |
| 8086:266d | 103c:099c | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 6     | snd_int... | E0DF895DC8 |
| 8086:266d | 1025:006a | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 5     | snd_int... | F47019C8BA |
| 8086:1040 | 8086:1000 | Intel      | 536EP Data Fax Modem         | 4     |            | 1263C61735 |
| 8086:266d | 1014:0574 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 4     | snd_int... | 4916E9EC9C |
| 8086:266d | 1025:0066 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 4     | snd_int... | E814DA247A |
| 1002:434d | 144d:2115 | AMD        | SB200 AC97 Modem Controller  | 3     | snd_ati... | 80073ED5E9 |
| 1002:4378 | 1043:1186 | AMD        | IXP SB400 AC'97 Modem Con... | 3     | snd_ati... | 08E7796666 |
| 1039:7013 | 1043:1816 | Silicon... | AC'97 Modem Controller       | 3     | snd_int... | C4EBB5D061 |
| 134d:7892 | 134d:0001 | PCTel      | HSP MicroModem 56            | 3     | serial     | F7D15035EC |
| 8086:24c6 | 1014:055a | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 3     | snd_int... | A538D3F64D |
| 8086:266d | 103c:309d | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 3     | snd_int... | 837230178B |
| 8086:266d | 144d:2115 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 3     | snd_int... | 88BAF3B388 |
| 1002:4378 | 103c:3091 | AMD        | IXP SB400 AC'97 Modem Con... | 2     | snd_ati... | 30D7D605F7 |
| 1002:4378 | 103c:30a4 | AMD        | IXP SB400 AC'97 Modem Con... | 2     | snd_ati... | 817D97FE5A |
| 1002:4378 | 1734:1092 | AMD        | IXP SB400 AC'97 Modem Con... | 2     | snd_ati... | 4D0D913872 |
| 1106:3068 | 1019:0c04 | VIA Tec... | AC'97 Modem Controller       | 2     | snd_via... | 1263C61735 |
| 8086:2486 | 1179:0001 | Intel      | 82801CA/CAM AC'97 Modem C... | 2     | snd_int... | A79789524B |
| 8086:2486 | 134d:4c21 | Intel      | 82801CA/CAM AC'97 Modem C... | 2     |            | 38C172234D |
| 8086:24c6 | 1014:0559 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 2     | snd_int... | 1811B66E00 |
| 8086:24c6 | 10cf:10d1 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 2     | snd_int... | EA732BEA27 |
| 8086:24c6 | 1179:0001 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 2     | snd_int... | 15CFD6C8AF |
| 8086:24c6 | 1179:ff31 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 2     | snd_int... | E9BD04F647 |
| 8086:266d | 1014:0576 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 2     | snd_int... | 9809E004BA |
| 8086:266d | 103c:0934 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 2     |            | 16F00AAE37 |
| 8086:266d | 103c:0944 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 2     | snd_int... | 5DA5847C6D |
| 8086:266d | 103c:3080 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 2     | snd_int... | 0572E8425C |
| 8086:266d | 103c:30c4 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 2     | snd_int... | 87F8EF65AE |
| 1002:434d | 1025:0052 | AMD        | SB200 AC97 Modem Controller  | 1     | snd_ati... | 856DF8910C |
| 1002:4378 | 1025:007e | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | FAC1D78802 |
| 1002:4378 | 1025:0080 | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 00FDC7C100 |
| 1002:4378 | 103c:308b | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 0148BED7F1 |
| 1002:4378 | 103c:309b | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 88BD859F3F |
| 1002:4378 | 1179:0001 | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 184C93E6DD |
| 1002:4378 | 1179:ff31 | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | BA3F405EF7 |
| 1002:4378 | 1462:0131 | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 21B7740691 |
| 1002:4378 | 1734:1098 | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 0328C9BAD3 |
| 1039:7013 | 1025:0083 | Silicon... | AC'97 Modem Controller       | 1     |            | 354B6DE784 |
| 1039:7013 | 104d:8128 | Silicon... | AC'97 Modem Controller       | 1     | snd_int... | 72A578315E |
| 1039:7013 | 104d:814e | Silicon... | AC'97 Modem Controller       | 1     | snd_int... | 88ABDEBE09 |
| 1057:3052 | 1631:3034 | Motorola   | SM56 Data Fax Modem          | 1     |            | B7CEC1644D |
| 10b9:5457 | 103c:0850 | ULi Ele... | M5457 AC'97 Modem Controller | 1     |            | 4E9D284D9C |
| 10de:00d9 | 1043:1856 | Nvidia     | nForce3 Audio                | 1     | snd_int... | 655ACF5FA6 |
| 1106:3068 | 1019:2122 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 25BB71984B |
| 1106:3068 | 1071:8666 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 179169EE59 |
| 1106:3068 | 1071:8889 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | E801E7B52C |
| 1106:3068 | 1734:10ae | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 06ECBD156A |
| 11c1:0440 | 11c1:0440 | LSI        | 56k WinModem                 | 1     |            | 6B2E5020C2 |
| 11c1:0449 | 1468:0410 | LSI        | L56xM+S [Mars-2] WinModem... | 1     |            | A8A13EFBA0 |
| 11c1:044e | 11c1:044e | LSI        | LT WinModem                  | 1     |            | 6203763CC5 |
| 11c1:044e | 1235:044e | LSI        | LT WinModem                  | 1     |            | 3D74179CB7 |
| 11c1:045c | 8086:2205 | LSI        | LT WinModem                  | 1     | serial     | 1B54E25E77 |
| 1543:3052 | 1543:3000 | SILICON... | Intel 537 [Winmodem]         | 1     |            | 75C969D54B |
| 2003:8800 | 16ef:2800 | Smart Link | LM-I56N                      | 1     |            | 8B4AE6CF41 |
| 2003:8800 | 1801:2800 | Smart Link | LM-I56N                      | 1     |            | 413AE4FF4F |
| 8086:1080 | 1028:1000 | Intel      | FA82537EP 56K V.92 Data/F... | 1     | serial     | 0E73DD68E2 |
| 8086:1080 | 8086:1000 | Intel      | FA82537EP 56K V.92 Data/F... | 1     | serial     | 6DF95E6042 |
| 8086:2486 | 1014:0223 | Intel      | 82801CA/CAM AC'97 Modem C... | 1     | snd_int... | 3EA811E273 |
| 8086:2486 | 14c0:0012 | Intel      | 82801CA/CAM AC'97 Modem C... | 1     | snd_int... | A8AF42D6E7 |
| 8086:24c6 | 1014:0524 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | BE49E35FA4 |
| 8086:24c6 | 1025:0071 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | BBE6DD58A1 |
| 8086:24c6 | 103c:08b0 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 316E375A5C |
| 8086:24c6 | 103c:3080 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | 6802B34FDD |
| 8086:24c6 | 1043:1826 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | B5CB46FFBA |
| 8086:24c6 | 104d:818c | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 7274BBB49F |
| 8086:24c6 | 1071:8089 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 8D8F3B4EA4 |
| 8086:24c6 | 1071:a001 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 9D5A19DCF4 |
| 8086:24c6 | 144d:2115 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 529607257E |
| 8086:24c6 | 144d:c00c | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 8BCCDD8350 |
| 8086:24c6 | 14c0:0012 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 8F733593DB |
| 8086:24c6 | 152d:0707 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 81347CD6BB |
| 8086:24c6 | 1734:103c | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | 6F452862B4 |
| 8086:24d6 | 1025:0045 | Intel      | 82801EB/ER (ICH5/ICH5R) A... | 1     |            | 41CC7EB08C |
| 8086:24d6 | 1179:0001 | Intel      | 82801EB/ER (ICH5/ICH5R) A... | 1     |            | A7D4DEEF9E |
| 8086:266d | 1025:007a | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     | snd_int... | E4219525B9 |
| 8086:266d | 103c:3082 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     |            | 91C7AE2180 |
| 8086:266d | 1179:ff31 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     | snd_int... | 8E0AD23326 |
| 8086:266d | 1462:0121 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     | snd_int... | 7A44DA1E2F |
| 8086:266d | 14ff:1013 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     | snd_int... | B6BA04DCE2 |
| 8086:266d | 17aa:207c | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     |            | EDAE63A429 |
| 8086:266d | 17c0:10bb | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     | snd_int... | 0808A2772F |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 99    | intel_a... | 4414412FCB |
| 14e4:1570 | 14e4:1570 | Broadco... | 720p FaceTime HD Camera      | 22    | bdc_pci    | B57A70D35E |
| 8086:1919 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 21    |            | 329795002B |
| 8086:9d32 | 8086:7270 | Intel      | Skylake-U/Y Camera IO Hos... | 19    | ipu3_cio2  | 329795002B |
| 109e:0878 |           | Brooktree  | Bt878 Audio Capture          | 15    |            | BA9CCBD3A5 |
| 1022:15e2 | 103c:84ae | AMD        | Raven/Raven2/FireFlight/R... | 14    | snd_pci... | E8755C7EF8 |
| 8086:5a88 |           | Intel      | Celeron N3350/Pentium N42... | 13    |            | F92E526676 |
| 1022:15e2 | 1022:15e2 | AMD        | Raven/Raven2/FireFlight/R... | 8     | snd_pci... | 048229855F |
| 1131:7231 | 5ace:8000 | Philips... | SAA7231                      | 8     |            | FA070462FC |
| 11bd:bede | 11bd:0022 | Pinnacl... | AV/DV Studio Capture Card    | 8     |            | BC68308D9C |
| 109e:0878 | 1461:0003 | Brooktree  | Bt878 Audio Capture          | 7     | snd_bt87x  | EBF0DCD676 |
| 1131:7160 | 1461:1455 | Philips... | SAA7160                      | 7     |            | C785DD2710 |
| 8086:0f38 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 7     | intel_a... | 0994A3EEB3 |
| 1131:7231 | 1461:2a0f | Philips... | SAA7231                      | 6     |            | 4CA7976A88 |
| 14e4:1615 | 14e4:1615 | Broadco... | BCM70015 Video Decoder [C... | 6     |            | E6CF3D7F11 |
| 8086:0f38 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 6     | atomisp    | CEAC334581 |
| 8086:22b8 | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 6     | intel_a... | 838DD8C3AC |
| 1022:15e2 | 103c:84d2 | AMD        | Raven/Raven2/FireFlight/R... | 5     |            | DEFB86D43A |
| 1022:15e2 | 17aa:380b | AMD        | Raven/Raven2/FireFlight/R... | 5     |            | 52036BD95B |
| 1131:7164 | 0070:8851 | Philips... | SAA7164                      | 5     | saa7164    | 54C8F90B14 |
| 1131:7231 | 1461:1400 | Philips... | SAA7231                      | 5     |            | 4F99536247 |
| 8086:22b8 | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 5     |            | DD16DF4133 |
| 8086:22b8 | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 5     | intel_a... | 1EB4640C84 |
| 8086:22b8 | 1297:2063 | Intel      | Atom/Celeron/Pentium Proc... | 5     | intel_a... | 2D91F64A77 |
| 1002:ac12 | 12ab:0003 | AMD        | Theater HD T507 (DVB-T) T... | 4     |            | EA55AE13AC |
| 109e:0878 | 0070:13eb | Brooktree  | Bt878 Audio Capture          | 4     | snd_bt87x  | AAECFA3E56 |
| 1022:15e2 | 103c:85ea | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | D7977A3B0E |
| 109e:0878 | 107d:6609 | Brooktree  | Bt878 Audio Capture          | 3     |            | 4A6B13BAEA |
| 1131:7160 | 1461:2655 | Philips... | SAA7160                      | 3     |            | A74B989748 |
| 1131:7162 | 11bd:0100 | Philips... | SAA7162                      | 3     |            | EF8A743A1E |
| 1131:7231 | 1461:7983 | Philips... | SAA7231                      | 3     |            | 6186ACA9BB |
| 14e4:1612 | 14e4:2612 | Broadcom   | BCM70012 Video Decoder [C... | 3     |            | 3CBFF8D8F5 |
| 14e4:1615 | 105b:0d77 | Broadcom   | BCM70015 Video Decoder [C... | 3     |            | B036D312E6 |
| 14f1:8804 | 0070:9002 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     |            | 8168BA11E3 |
| 1822:4e35 | 153b:1179 | Twinhan... | Mantis DTV PCI Bridge Con... | 3     | mantis     | C6B223FD61 |
| 1822:4e35 | 1822:0031 | Twinhan... | Mantis DTV PCI Bridge Con... | 3     | mantis     | 24636D8ED6 |
| 8086:1919 | 1028:07a4 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | ipu3_imgu  | 73B87C222F |
| 8086:1919 | 17aa:382f | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     |            | 1DD80D33E5 |
| 8086:22b8 | 103c:813e | Intel      | Atom/Celeron/Pentium Proc... | 3     |            | F91E0FBE6B |
| 8086:22b8 | 17aa:3809 | Intel      | Atom/Celeron/Pentium Proc... | 3     | intel_a... | 31140595BC |
| 8086:9d32 |           | Intel      | Skylake-U/Y Camera IO Hos... | 3     | ipu3_cio2  | D6EFA0F211 |
| 8086:9d32 | 1028:07a4 | Intel      | Skylake-U/Y Camera IO Hos... | 3     | ipu3_cio2  | 73B87C222F |
| 8086:9d32 | 17aa:380c | Intel      | Skylake-U/Y Camera IO Hos... | 3     | ipu3_cio2  | 1DD80D33E5 |
| 1022:15e2 | 1025:1233 | AMD        | Raven/Raven2/FireFlight/R... | 2     |            | 856A212CAA |
| 1022:15e2 | 103c:8433 | AMD        | Raven/Raven2/FireFlight/R... | 2     | snd_pci... | 33A03DF803 |
| 1022:15e2 | 103c:8434 | AMD        | Raven/Raven2/FireFlight/R... | 2     |            | E2E650868B |
| 1022:15e2 | 103c:8496 | AMD        | Raven/Raven2/FireFlight/R... | 2     | snd_pci... | F720A735A8 |
| 109e:0878 | 11bd:0012 | Brooktree  | Bt878 Audio Capture          | 2     | snd_bt87x  | AB36F565A4 |
| 1131:7160 | 1461:0555 | Philips... | SAA7160                      | 2     |            | D400943350 |
| 1131:7160 | 1461:0855 | Philips... | SAA7160                      | 2     |            | BBDA8BED86 |
| 1131:7160 | 1461:0a55 | Philips... | SAA7160                      | 2     |            | 99DDBBF195 |
| 1131:7160 | 1461:1855 | Philips... | SAA7160                      | 2     |            | FA070462FC |
| 1131:7160 | 1ae4:0700 | Philips... | SAA7160                      | 2     |            | E9FCA3B9C8 |
| 1131:7231 | 12ab:0762 | Philips... | SAA7231                      | 2     |            | A72F1BCDE6 |
| 1131:7231 | 12ab:0763 | Philips... | SAA7231                      | 2     |            | 6F6F611F59 |
| 1131:7231 | 1461:0b0f | Philips... | SAA7231                      | 2     |            | 791CA50070 |
| 1131:7231 | 16be:0008 | Philips... | SAA7231                      | 2     |            | 1BA5C50EAD |
| 1131:7231 | 5ace:8150 | Philips... | SAA7231                      | 2     |            | 8603D5BDF5 |
| 1131:7231 | 5ace:8201 | Philips... | SAA7231                      | 2     |            | 3D68E82C9F |
| 11bd:bede | 11bd:0023 | Pinnacl... | AV/DV Studio Capture Card    | 2     |            | EBD8A5801D |
| 14f1:8804 | 1822:0023 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     |            | AB36F565A4 |
| 1822:4e35 | 153b:1178 | Twinhan... | Mantis DTV PCI Bridge Con... | 2     | mantis     | B7812DD3C1 |
| 1822:4e35 | 1ae4:0002 | Twinhan... | Mantis DTV PCI Bridge Con... | 2     | mantis     | CCB302179F |
| 1822:4e35 | 1ae4:0003 | Twinhan... | Mantis DTV PCI Bridge Con... | 2     | mantis     | DA1E5854E0 |
| 8086:1919 | 1025:111e | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     |            | D6EFA0F211 |
| 8086:1919 | 8086:1919 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     |            | 707E0DB074 |
| 8086:22b8 | 17aa:222a | Intel      | Atom/Celeron/Pentium Proc... | 2     | intel_a... | DF76656467 |
| 8086:22b8 | 17aa:38e3 | Intel      | Atom/Celeron/Pentium Proc... | 2     | intel_a... | BD392FF7CD |
| 8086:9d32 | 8086:9d32 | Intel      | Skylake-U/Y Camera IO Hos... | 2     | ipu3_cio2  | 707E0DB074 |
| 0002:8290 | 107d:2609 |            | Multimedia controller        | 1     |            | 95D420F37F |
| 1002:4d51 | 1002:b041 | AMD        | Unified AVStream Driver      | 1     |            | 2CF316774E |
| 1002:ac12 | 1002:b539 | AMD        | Theater HD T507 (DVB-T) T... | 1     |            | DD5E0979B0 |
| 1002:ad18 | 1682:ad18 | AMD        | Multimedia controller        | 1     |            | 3108FE53D3 |
| 1022:15e2 | 103c:85b3 | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | 766B0474A3 |
| 1022:15e2 | 17aa:36f5 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | 7E41940C9C |
| 1022:15e2 | 17aa:3811 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | 878BBF3E54 |
| 1022:15e2 | 17aa:5124 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | 79E53D2DB5 |
| 1022:15e2 | 17aa:5125 | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | 7A1C4A299D |
| 1022:15e2 | 19e5:3e06 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | 2CDCEA8607 |
| 1057:3410 | 1057:ffff | Motorola   | DSP56361 Digital Signal P... | 1     |            | 16A7890585 |
| 1057:3410 | 11af:eed2 | Motorola   | DSP56361 Digital Signal P... | 1     |            | 16A7890585 |
| 1057:3410 | 11af:eee1 | Motorola   | DSP56361 Digital Signal P... | 1     |            | 16A7890585 |
| 109e:0878 | 0070:ff04 | Brooktree  | Bt878 Audio Capture          | 1     |            | 2C877CF870 |
| 109e:0878 | 1047:f331 | Brooktree  | Bt878 Audio Capture          | 1     |            | 444FFBC8A6 |
| 109e:0878 | 1461:0001 | Brooktree  | Bt878 Audio Capture          | 1     |            | E8072B6F3A |
| 109e:0878 | 1461:0002 | Brooktree  | Bt878 Audio Capture          | 1     |            | A22609B54B |
| 109e:0878 | 1461:0004 | Brooktree  | Bt878 Audio Capture          | 1     |            | 660B28DD52 |
| 109e:0878 | 800a:763d | Brooktree  | Bt878 Audio Capture          | 1     |            | 08DCF9AA49 |
| 109e:0878 | 800b:763d | Brooktree  | Bt878 Audio Capture          | 1     |            | 08DCF9AA49 |
| 109e:0878 | 800c:763d | Brooktree  | Bt878 Audio Capture          | 1     |            | 08DCF9AA49 |
| 109e:0878 | 800d:763d | Brooktree  | Bt878 Audio Capture          | 1     |            | 08DCF9AA49 |
| 109e:0878 | bd11:4100 | Brooktree  | Bt878 Audio Capture          | 1     |            | C20B184FC3 |
| 10b5:9056 | 1a0e:0073 | PLX Tec... | PCI9056 32-bit 66MHz PCI ... | 1     | Dta        | A9ADFE83C5 |
| 10cf:202a | 104d:81fa | Fujitsu... | Integrated MPEG Encoder      | 1     |            | 7F0BB0CC92 |
| 10cf:2030 | 104d:9062 | Fujitsu... | Fujitsu Multimedia contro... | 1     |            | 2628EBE1BB |
| 1131:7160 | 1461:0455 | Philips... | SAA7160                      | 1     |            | F85808C04C |
| 1131:7160 | 1461:0955 | Philips... | SAA7160                      | 1     |            | 388696B306 |
| 1131:7160 | 1461:1055 | Philips... | SAA7160                      | 1     |            | 9E921922BA |
| 1131:7160 | 1461:2355 | Philips... | SAA7160                      | 1     |            | B98B8362E0 |
| 1131:7160 | 16be:0034 | Philips... | SAA7160                      | 1     |            | 2B8D93B7EC |

### Multiport serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1fd4:1999 | 1fd4:0002 | SUNIX      | Multiport serial controller  | 3     | serial     | A9E837C9EB |
| 135c:0170 | 135c:0170 | Quatech    | QSCLP-100                    | 1     | serial     | 05DF269988 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8168 | 1458:e000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1927  | r8169      | B39AC90CA0 |
| 10ec:8168 | 1043:8505 | Realtek... | RTL8111/8168/8411 PCI Exp... | 697   | r8169      | 570B707FFB |
| 10ec:8168 | 1849:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 675   | r8169      | EF6230C726 |
| 10ec:8168 | 1043:8432 | Realtek... | RTL8111/8168/8411 PCI Exp... | 562   | r8169      | 6A60A724F9 |
| 10ec:8168 | 1043:200f | Realtek... | RTL8111/8168/8411 PCI Exp... | 442   | r8169      | C53DF5F083 |
| 10ec:8139 | 10ec:8139 | Realtek... | RTL-8100/8101L/8139 PCI F... | 379   | 8139too... | 70E729A005 |
| 10ec:8168 | 1043:8677 | Realtek... | RTL8111/8168/8411 PCI Exp... | 300   | r8169      | 99614383EB |
| 10ec:8168 | 1043:8554 | Realtek... | RTL8111/8168/8411 PCI Exp... | 282   | r8169      | F6CCF2BBA6 |
| 10ec:8168 | 1043:83a3 | Realtek... | RTL8111/8168/8411 PCI Exp... | 245   | r8169      | EB9D0FE3F5 |
| 1969:1048 | 1043:8226 | Qualcom... | Attansic L1 Gigabit Ethernet | 226   | atl1       | 48709E5844 |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 217   | r8169      | 44204F310C |
| 14e4:16b5 | 1025:0647 | Broadco... | NetLink BCM57785 Gigabit ... | 212   | tg3        | E67DFC255A |
| 10ec:8136 | 1043:200f | Realtek... | RTL810xE PCI Express Fast... | 198   | r8169      | F8FDA4EFC3 |
| 1106:3106 | 1186:1405 | VIA Tec... | VT6105/VT6106S [Rhine-III]   | 163   | via_rhine  | 080AE7C292 |
| 10ec:8168 | 1043:859e | Realtek... | RTL8111/8168/8411 PCI Exp... | 147   | r8169      | 3A1BF1D002 |
| 10ec:8168 | 1043:16d5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 138   | r8169      | 527313B5FF |
| 1969:1083 | 1458:e000 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 137   | atl1c      | D3FFE4FDA2 |
| 1969:2062 | 1043:8468 | Attansi... | AR8152 v2.0 Fast Ethernet    | 134   | atl1c      | A84D413088 |
| 10ec:8136 | 1849:8136 | Realtek... | RTL810xE PCI Express Fast... | 133   | r8169      | 42C519E784 |
| 8086:15b8 | 1043:8672 | Intel      | Ethernet Connection (2) I... | 121   | e1000e     | 89F4BB64D7 |
| 10ec:8168 | 17aa:5002 | Realtek... | RTL8111/8168/8411 PCI Exp... | 116   | r8169      | 65D329A2C6 |
| 197b:0250 | 1043:1905 | JMicron... | JMC250 PCI Express Gigabi... | 116   | jme        | F47F34752E |
| 10ec:8168 | 1043:82c6 | Realtek... | RTL8111/8168/8411 PCI Exp... | 112   | r8169      | 42CC2F59E6 |
| 11ab:4364 | 1043:81f8 | Marvell... | 88E8056 PCI-E Gigabit Eth... | 111   | sky2       | B481805845 |
| 1969:1083 | 1043:1851 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 95    | atl1c      | 6B25B8982D |
| 10ec:8136 | 10ec:0123 | Realtek... | RTL810xE PCI Express Fast... | 94    | r8169      | 9137FB3859 |
| 10ec:8169 | 10ec:8169 | Realtek... | RTL8169 PCI Gigabit Ether... | 88    | r8169      | D569843A2D |
| 14e4:16b5 | 1025:0504 | Broadco... | NetLink BCM57785 Gigabit ... | 86    | tg3        | 8579BA1B16 |
| 10ec:8168 | 1043:81aa | Realtek... | RTL8111/8168/8411 PCI Exp... | 84    | r8169      | EB0CDD472F |
| 1969:1026 | 1043:8304 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 84    | atl1e      | 6C7C70F0E2 |
| 1969:1091 | 1458:e000 | Qualcom... | AR8161 Gigabit Ethernet      | 84    | alx        | 8C4047657D |
| 1969:2062 | 17aa:3979 | Qualcom... | AR8152 v2.0 Fast Ethernet    | 84    | atl1c      | A7618091FB |
| 10ec:8168 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 83    | r8169      | 02A2AC15DE |
| 8086:15a1 | 1043:85c4 | Intel      | Ethernet Connection (2) I... | 80    | e1000e     | A8F2B39356 |
| 14e4:1693 | 1025:011c | Broadco... | NetLink BCM5787M Gigabit ... | 79    | tg3        | 7387D70AD5 |
| 10ec:8168 | 7470:3468 | Realtek... | RTL8111/8168/8411 PCI Exp... | 78    | r8169      | AEC91031D4 |
| 14e4:1692 | 1025:036d | Broadco... | NetLink BCM57780 Gigabit ... | 77    | tg3        | D023F50697 |
| 10ec:8136 | 1043:8347 | Realtek... | RTL810xE PCI Express Fast... | 75    | r8169      | 85261DC7A2 |
| 1969:1090 | 17aa:3979 | Qualcom... | AR8162 Fast Ethernet         | 75    | alx        | 891002E8F2 |
| 10ec:8168 | 1462:7817 | Realtek... | RTL8111/8168/8411 PCI Exp... | 72    | r8169      | 7BBCD6F17D |
| 11ab:4320 | 1043:811a | Marvell... | 88E8001 Gigabit Ethernet ... | 72    | skge       | B26ED41AB8 |
| 1969:2048 | 1043:8233 | Qualcom... | Attansic L2 Fast Ethernet    | 71    | atl2       | 7D6812488D |
| 8086:15b8 | 1458:e000 | Intel      | Ethernet Connection (2) I... | 65    | e1000e     | AAD0551E27 |
| 10ec:8136 | 17aa:3975 | Realtek... | RTL810xE PCI Express Fast... | 62    | r8169      | F72A609702 |
| 1969:1063 | 1043:1820 | Qualcom... | AR8131 Gigabit Ethernet      | 61    | atl1c      | 49783F833C |
| 10ec:8168 | 1043:1277 | Realtek... | RTL8111/8168/8411 PCI Exp... | 60    | r8169      | 826F5492EB |
| 1969:1062 | 1043:838a | Qualcom... | AR8132 Fast Ethernet         | 59    | atl1c      | B658C90327 |
| 10ec:8136 | 1179:ff00 | Realtek... | RTL810xE PCI Express Fast... | 56    | r8169      | C5ADBBB2B3 |
| 10ec:8168 | 1043:8367 | Realtek... | RTL8111/8168/8411 PCI Exp... | 55    | r8169      | 699B1F26E0 |
| 10ec:8168 | 1025:8000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 54    | r8169      | 99825EFDBE |
| 10ec:8168 | 17aa:3816 | Realtek... | RTL8111/8168/8411 PCI Exp... | 54    | r8169      | CC7193A7B9 |
| 10ec:8168 | 1043:11f5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 53    | r8169      | FAECBEFA9B |
| 10ec:8168 | 1b0a:20d9 | Realtek... | RTL8111/8168/8411 PCI Exp... | 52    | r8169      | AC77E66D3F |
| 14e4:16b4 | 14e4:16b4 | Broadco... | NetXtreme BCM57765 Gigabi... | 52    | tg3        | 16BDB52C40 |
| 1969:1026 | 1043:14f5 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 52    | atl1e      | 38190AD2E1 |
| 10ec:8168 | 1462:7721 | Realtek... | RTL8111/8168/8411 PCI Exp... | 51    | r8169      | B801DD3F7D |
| 1969:10a0 | 17aa:3802 | Qualcom... | QCA8172 Fast Ethernet        | 51    | alx        | 06603D3DCE |
| 14e4:1698 | 1025:0207 | Broadco... | NetLink BCM5784M Gigabit ... | 50    | tg3        | 47E2374F61 |
| 14e4:16b3 | 1025:0775 | Broadco... | NetXtreme BCM57786 Gigabi... | 50    | tg3        | AB33DE8D3B |
| 10ec:8168 | 144d:c0da | Realtek... | RTL8111/8168/8411 PCI Exp... | 49    | r8169      | 0F042024B4 |
| 10ec:8136 | 10ec:8136 | Realtek... | RTL810xE PCI Express Fast... | 48    | r8169      | A1DD312C27 |
| 10ec:8168 | 17aa:3975 | Realtek... | RTL8111/8168/8411 PCI Exp... | 48    | r8169      | 05D969D697 |
| 1969:1026 | 1043:8226 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 48    | atl1e      | 28DFB478B7 |
| 1969:2062 | 1849:2062 | Qualcom... | AR8152 v2.0 Fast Ethernet    | 48    | atl1c      | 5F6E1A3B61 |
| 8086:153b | 1458:e000 | Intel      | Ethernet Connection I217-V   | 47    | e1000e     | 7875ECD5A5 |
| 10ec:8167 | 1458:e000 | Realtek... | RTL-8110SC/8169SC Gigabit... | 46    | r8169      | 9CD2D7F72B |
| 10ec:8168 | 17aa:3812 | Realtek... | RTL8111/8168/8411 PCI Exp... | 46    | r8169      | 760B445B08 |
| 1969:1063 | 1043:83fe | Qualcom... | AR8131 Gigabit Ethernet      | 46    | atl1c      | E267629A35 |
| 1969:1063 | 1458:e000 | Qualcom... | AR8131 Gigabit Ethernet      | 46    | atl1c      | E73646B8DF |
| 1969:1091 | 1043:14c7 | Qualcom... | AR8161 Gigabit Ethernet      | 46    | alx        | 9A401175B3 |
| 10ec:8136 | 17aa:392e | Realtek... | RTL810xE PCI Express Fast... | 45    | r8169      | 601D53F9EB |
| 10ec:8168 | 1043:8385 | Realtek... | RTL8111/8168/8411 PCI Exp... | 45    | r8169      | EE184BFE51 |
| 1186:4300 | 1186:4300 | D-Link ... | DGE-528T Gigabit Ethernet... | 45    | r8169      | 66A5EA0BE5 |
| 1969:10a1 | 1043:8587 | Qualcom... | QCA8171 Gigabit Ethernet     | 45    | alx        | BF6F67F7A5 |
| 8086:15b8 | 1849:15b8 | Intel      | Ethernet Connection (2) I... | 45    | e1000e     | CACD7C9489 |
| 14e4:1713 | 17aa:3a23 | Broadco... | NetLink BCM5906M Fast Eth... | 44    | tg3        | 370DCD58CC |
| 10ec:8168 | 144d:c606 | Realtek... | RTL8111/8168/8411 PCI Exp... | 43    | r8169      | EE56C112BB |
| 1969:1083 | 1043:13c7 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 43    | atl1c      | EA07B48EB4 |
| 11ab:4362 | 1043:8142 | Marvell... | 88E8053 PCI-E Gigabit Eth... | 42    | sky2       | 2BF9512AD1 |
| 10ec:8136 | 1028:04b0 | Realtek... | RTL810xE PCI Express Fast... | 41    | r8169      | C0868A2B0C |
| 10ec:8139 | 1043:1045 | Realtek... | RTL-8100/8101L/8139 PCI F... | 41    | 8139too... | 1B0893029F |
| 13f0:0200 | 13f0:0201 | Sundanc... | IC Plus IP100A Integrated... | 41    | sundance   | 6ED85C31F2 |
| 14e4:1692 | 1025:033d | Broadco... | NetLink BCM57780 Gigabit ... | 40    | tg3        | CB3BAA60D9 |
| 10ec:8168 | 1462:7693 | Realtek... | RTL8111/8168/8411 PCI Exp... | 39    | r8169      | FEAA959521 |
| 11ab:4381 | 104d:9071 | Marvell... | Yukon Optima 88E8059 [PCI... | 39    | sky2       | 3C5767E938 |
| 1969:1083 | 1849:1083 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 39    | atl1c      | 27E239601B |
| 10ec:8168 | 1019:811e | Realtek... | RTL8111/8168/8411 PCI Exp... | 38    | r8169      | 78E822AD79 |
| 8086:153b | 1043:859f | Intel      | Ethernet Connection I217-V   | 37    | e1000e     | B61D174C21 |
| 1969:1026 | 1043:831c | Qualcom... | AR8121/AR8113/AR8114 Giga... | 36    | atl1e      | 5C690583ED |
| 10ec:8139 | 11f6:8139 | Realtek... | RTL-8100/8101L/8139 PCI F... | 35    | 8139too... | 96FBD72727 |
| 10ec:8168 | 1025:0866 | Realtek... | RTL8111/8168/8411 PCI Exp... | 35    | r8169      | 1C77D7A584 |
| 10ec:8168 | 144d:c0b6 | Realtek... | RTL8111/8168/8411 PCI Exp... | 35    | r8169      | 616616B60F |
| 10ec:8168 | 1462:369c | Realtek... | RTL8111/8168/8411 PCI Exp... | 35    | r8169      | C46668413C |
| 10de:0ab0 | 10de:cb79 | Nvidia     | MCP79 Ethernet               | 33    | forcedeth  | 9F753AC669 |
| 10ec:8136 | 17aa:3830 | Realtek... | RTL810xE PCI Express Fast... | 33    | r8169      | EE1CFF7014 |
| 1969:1062 | 1025:0212 | Qualcom... | AR8132 Fast Ethernet         | 33    | atl1c      | 6029A4A18A |
| 1969:1091 | 1043:8507 | Qualcom... | AR8161 Gigabit Ethernet      | 33    | alx        | 9F6FB489EC |
| 8086:155a | 17aa:2214 | Intel      | Ethernet Connection I218-LM  | 33    | e1000e     | 7637F3DE5F |
| 10ec:8136 | 1179:fb37 | Realtek... | RTL810xE PCI Express Fast... | 32    | r8169      | 806B890CCF |
| 10ec:8168 | 1043:104c | Realtek... | RTL8111/8168/8411 PCI Exp... | 32    | r8169      | 0051F69751 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 168c:002b | 1a3b:1089 | Qualcom... | AR9285 Wireless Network A... | 439   | ath9k      | 07CD36611F |
| 1814:3290 | 103c:18ec | Ralink     | RT3290 Wireless 802.11n 1... | 193   | rt2800pci  | A978F2CA38 |
| 14e4:4365 | 17aa:0611 | Broadco... | BCM43142 802.11b/g/n         | 183   | wl         | 06603D3DCE |
| 168c:0032 | 1a3b:2c97 | Qualcom... | AR9485 Wireless Network A... | 183   | ath9k      | 92AE8C0F3B |
| 168c:002b | 105b:e035 | Qualcom... | AR9285 Wireless Network A... | 182   | ath9k      | D023F50697 |
| 8086:4222 | 8086:1001 | Intel      | PRO/Wireless 3945ABG [Gol... | 181   | iwl3945    | 253B1DAE47 |
| 168c:002b | 17aa:30a1 | Qualcom... | AR9285 Wireless Network A... | 176   | ath9k      | A7618091FB |
| 168c:002b | 1a3b:2c37 | Qualcom... | AR9285 Wireless Network A... | 174   | ath9k      | 6B25B8982D |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 164   | iwlwifi    | C7F97B95C4 |
| 168c:0032 | 144d:4105 | Qualcom... | AR9485 Wireless Network A... | 147   | ath9k      | 53302E45B6 |
| 168c:0034 | 105b:e052 | Qualcom... | AR9462 Wireless Network A... | 140   | ath9k      | DE168F8DCC |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 140   | iwlwifi    | AC96DD45F9 |
| 168c:0036 | 11ad:0642 | Qualcom... | QCA9565 / AR9565 Wireless... | 136   | ath9k      | 50FFA5DCEC |
| 8086:0896 | 8086:5005 | Intel      | Centrino Wireless-N 130      | 131   | iwlwifi    | EE56C112BB |
| 168c:0042 | 11ad:08a6 | Qualcom... | QCA9377 802.11ac Wireless... | 123   | ath10k_pci | 6E04F26B23 |
| 14e4:4727 | 103c:1483 | Broadco... | BCM4313 802.11bgn Wireles... | 117   | wl         | 23E7475693 |
| 168c:001c | 1a3b:1026 | Qualcom... | AR242x / AR542x Wireless ... | 115   | ath5k      | 54C92BF69C |
| 10ec:b723 | 17aa:b736 | Realtek... | RTL8723BE PCIe Wireless N... | 114   | rtl8723be  | 00C22F3924 |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 111   | iwlwifi    | 4C9A2AA59C |
| 168c:001c | 1468:0428 | Qualcom... | AR242x / AR542x Wireless ... | 110   | ath5k      | 6029A4A18A |
| 168c:0036 | 1028:020c | Qualcom... | QCA9565 / AR9565 Wireless... | 110   | ath9k      | 65A9CF6ADE |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 108   | iwlwifi    | CE2A6FB934 |
| 168c:002b | 105b:e025 | Qualcom... | AR9285 Wireless Network A... | 101   | ath9k      | 86987CF1ED |
| 168c:0032 | 11ad:6617 | Qualcom... | AR9485 Wireless Network A... | 101   | ath9k      | 4B260556B7 |
| 8086:4232 | 8086:1201 | Intel      | WiFi Link 5100               | 98    | iwlwifi    | 508F60B315 |
| 8086:0887 | 8086:4062 | Intel      | Centrino Wireless-N 2230     | 96    | iwlwifi    | 606AACED27 |
| 168c:0032 | 103c:1785 | Qualcom... | AR9485 Wireless Network A... | 94    | ath9k      | AB69AA73CD |
| 8086:08ae | 8086:1005 | Intel      | Centrino Wireless-N 100      | 94    | iwlwifi    | 6150CCFA00 |
| 168c:002e | 105b:e034 | Qualcom... | AR9287 Wireless Network A... | 93    | ath9k      | 690FFF1815 |
| 168c:0036 | 1028:020e | Qualcom... | QCA9565 / AR9565 Wireless... | 93    | ath9k      | 3548830389 |
| 8086:4229 | 8086:1101 | Intel      | PRO/Wireless 4965 AG or A... | 93    | iwl4965    | CF3A7AD203 |
| 168c:0036 | 17aa:4026 | Qualcom... | QCA9565 / AR9565 Wireless... | 92    | ath9k      | 4A22031CA8 |
| 14e4:4727 | 14e4:051b | Broadco... | BCM4313 802.11bgn Wireles... | 91    | wl         | F9F3745636 |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 90    | iwlwifi    | C53DF5F083 |
| 14e4:4727 | 103c:1795 | Broadco... | BCM4313 802.11bgn Wireles... | 88    | wl         | 42DF53B120 |
| 8086:4237 | 8086:1211 | Intel      | PRO/Wireless 5100 AGN [Sh... | 85    | iwlwifi    | FDAB3CF92F |
| 168c:002b | 105b:e016 | Qualcom... | AR9285 Wireless Network A... | 83    | ath9k      | 6827DB0C63 |
| 168c:0032 | 168c:3118 | Qualcom... | AR9485 Wireless Network A... | 83    | ath9k      | CDCE9B48F0 |
| 168c:0034 | 11ad:6621 | Qualcom... | AR9462 Wireless Network A... | 81    | ath9k      | 7750967159 |
| 8086:4232 | 8086:1206 | Intel      | WiFi Link 5100               | 81    | iwlwifi    | 77E3B20E26 |
| 10ec:8723 | 10ec:0726 | Realtek... | RTL8723AE PCIe Wireless N... | 78    | rtl8723ae  | 891DE458D7 |
| 168c:0032 | 17aa:3218 | Qualcom... | AR9485 Wireless Network A... | 77    | ath9k      | 35C9173099 |
| 14e4:4727 | 105b:e042 | Broadco... | BCM4313 802.11bgn Wireles... | 76    | wl         | E67DFC255A |
| 168c:0032 | 1a3b:1186 | Qualcom... | AR9485 Wireless Network A... | 76    | ath9k      | 5AEE6B7CA7 |
| 8086:4222 | 103c:135c | Intel      | PRO/Wireless 3945ABG [Gol... | 76    | iwl3945    | 531D26CDD8 |
| 14e4:4727 | 144f:7179 | Broadco... | BCM4313 802.11bgn Wireles... | 74    | wl         | EB58946826 |
| 168c:002b | 144f:7167 | Qualcom... | AR9285 Wireless Network A... | 74    | ath9k      | BC68546696 |
| 14e4:4727 | 14e4:0510 | Broadco... | BCM4313 802.11bgn Wireles... | 72    | wl         | 8E79CDDBDA |
| 14e4:4727 | 185f:051a | Broadco... | BCM4313 802.11bgn Wireles... | 72    | wl         | 82EA1BF753 |
| 8086:a370 | 8086:0034 | Intel      | Wireless-AC 9560 [Jeffers... | 72    | iwlwifi    | 3A4D90A1C3 |
| 10ec:b723 | 11ad:1723 | Realtek... | RTL8723BE PCIe Wireless N... | 71    | rtl8723be  | 8BBDB85BE4 |
| 168c:0042 | 17aa:0901 | Qualcom... | QCA9377 802.11ac Wireless... | 70    | ath10k_pci | DE5FB421D9 |
| 14e4:4315 | 103c:1508 | Broadco... | BCM4312 802.11b/g LP-PHY     | 69    | ssb        | AB17752168 |
| 14e4:4315 | 14e4:04b5 | Broadco... | BCM4312 802.11b/g LP-PHY     | 69    | ssb        | 601D53F9EB |
| 168c:002b | 103c:3040 | Qualcom... | AR9285 Wireless Network A... | 69    | ath9k      | 73E5B46F66 |
| 168c:0032 | 11ad:6627 | Qualcom... | AR9485 Wireless Network A... | 67    | ath9k      | C8D8836613 |
| 10ec:b723 | 10ec:b729 | Realtek... | RTL8723BE PCIe Wireless N... | 66    | rtl8723be  | D607079392 |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 66    | 8821ce     | 4F9294F4B5 |
| 168c:001c | 144f:7131 | Qualcom... | AR242x / AR542x Wireless ... | 66    | ath5k      | FC7D577AB7 |
| 168c:002b | 103c:1461 | Qualcom... | AR9285 Wireless Network A... | 65    | ath9k      | 7306A03690 |
| 10ec:b723 | 103c:2231 | Realtek... | RTL8723BE PCIe Wireless N... | 64    | rtl8723be  | 4B70A9D252 |
| 14e4:4311 | 1028:0007 | Broadco... | BCM4311 802.11b/g WLAN       | 64    | ssb        | 14AC7530E2 |
| 8086:3165 | 8086:4410 | Intel      | Wireless 3165                | 61    | iwlwifi    | 8090C8CC68 |
| 168c:002b | 1028:0205 | Qualcom... | AR9285 Wireless Network A... | 60    | ath9k      | 3ACD13490F |
| 14e4:4358 | 105b:e040 | Broadco... | BCM43227 802.11b/g/n         | 58    | wl         | 8579BA1B16 |
| 168c:002b | 105b:e017 | Qualcom... | AR9285 Wireless Network A... | 58    | ath9k      | 3C5767E938 |
| 168c:002d | 168c:0301 | Qualcom... | AR9227 Wireless Network A... | 58    | ath9k      | BDB727808F |
| 168c:0036 | 1a3b:213a | Qualcom... | QCA9565 / AR9565 Wireless... | 58    | ath9k      | F8FDA4EFC3 |
| 14e4:4315 | 1028:000c | Broadco... | BCM4312 802.11b/g LP-PHY     | 57    | wl         | B7AD02779E |
| 14e4:4727 | 1a3b:2047 | Broadco... | BCM4313 802.11bgn Wireles... | 57    | wl         | 4ADFAB3C4E |
| 168c:002e | 168c:30a4 | Qualcom... | AR9287 Wireless Network A... | 56    | ath9k      | 8B7204FCBA |
| 168c:0042 | 17aa:4035 | Qualcom... | QCA9377 802.11ac Wireless... | 56    | ath10k_pci | 7957C03703 |
| 8086:0084 | 8086:1315 | Intel      | Centrino Wireless-N 1000 ... | 56    | iwlwifi    | 72424367AD |
| 8086:08b1 | 8086:4070 | Intel      | Wireless 7260                | 56    | iwlwifi    | 6D584D5DAB |
| 168c:0032 | 1028:0209 | Qualcom... | AR9485 Wireless Network A... | 55    | ath9k      | F72534E2D2 |
| 168c:003e | 1a56:1535 | Qualcom... | QCA6174 802.11ac Wireless... | 55    | ath10k_pci | 3A71C37AE2 |
| 1814:3290 | 105b:e055 | Ralink     | RT3290 Wireless 802.11n 1... | 55    | rt2800pci  | F71E42FC3C |
| 14e4:4727 | 103c:145c | Broadco... | BCM4313 802.11bgn Wireles... | 53    | wl         | 1FF111737A |
| 10ec:b723 | 103c:81c1 | Realtek... | RTL8723BE PCIe Wireless N... | 52    | rtl8723be  | 1CC2218397 |
| 14e4:4311 | 1468:0422 | Broadco... | BCM4311 802.11b/g WLAN       | 52    | ssb        | 16BE592F4F |
| 168c:0032 | 105b:e044 | Qualcom... | AR9485 Wireless Network A... | 51    | ath9k      | B56B7F6394 |
| 14e4:4365 | 1028:0016 | Broadco... | BCM43142 802.11b/g/n         | 49    | wl         | 67CD98E6C7 |
| 168c:0032 | 1a3b:2126 | Qualcom... | AR9485 Wireless Network A... | 49    | ath9k      | 2D1845C282 |
| 10ec:8723 | 1a3b:2114 | Realtek... | RTL8723AE PCIe Wireless N... | 48    | rtl8723ae  | 86D04818BE |
| 168c:0032 | 105b:e047 | Qualcom... | AR9485 Wireless Network A... | 48    | ath9k      | 11B9C937C9 |
| 168c:0036 | 11ad:0632 | Qualcom... | QCA9565 / AR9565 Wireless... | 48    | ath9k      | 4A1964118D |
| 168c:002d | 168c:0300 | Qualcom... | AR9227 Wireless Network A... | 46    | ath9k      | 8C518D5D23 |
| 168c:0042 | 1028:1810 | Qualcom... | QCA9377 802.11ac Wireless... | 46    | ath10k_pci | 9402076861 |
| 1814:3090 | 103c:1453 | Ralink     | RT3090 Wireless 802.11n 1... | 45    | rt2800pci  | 36FF276D26 |
| 10ec:8179 | 103c:197d | Realtek... | RTL8188EE Wireless Networ... | 44    | rtl8188ee  | 99C1387438 |
| 14e4:4365 | 103c:804a | Broadco... | BCM43142 802.11b/g/n         | 44    | wl         | 2EC22FA87A |
| 14e4:4727 | 144f:7175 | Broadco... | BCM4313 802.11bgn Wireles... | 44    | wl         | BD758B3E12 |
| 168c:0032 | 103c:1838 | Qualcom... | AR9485 Wireless Network A... | 44    | ath9k      | 861B54C65A |
| 168c:0036 | 105b:e07f | Qualcom... | QCA9565 / AR9565 Wireless... | 44    | ath9k      | 1C77D7A584 |
| 8086:24fd | 8086:0110 | Intel      | Wireless 8265 / 8275         | 44    | iwlwifi    | CA74DF306B |
| 168c:001c | 103c:137b | Qualcom... | AR242x / AR542x Wireless ... | 43    | ath5k      | 084F7E13DA |
| 1814:3060 | 1186:3c04 | Ralink     | RT3060 Wireless 802.11n 1... | 43    | rt2800pci  | F79EDA31F9 |
| 168c:0032 | 11ad:6628 | Qualcom... | AR9485 Wireless Network A... | 42    | ath9k      | A1A1F1965A |
| 1814:5390 | 105b:e054 | Ralink     | RT5390 Wireless 802.11n 1... | 42    | rt2800pci  | 923B4CD756 |
| 14e4:4357 | 105b:e021 | Broadco... | BCM43225 802.11b/g/n         | 41    | wl         | 4C990A61B6 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:03ef | 1849:03ef | Nvidia     | MCP61 Ethernet               | 180   | forcedeth  | 816FE60D2D |
| 8086:0085 | 8086:1311 | Intel      | Centrino Advanced-N 6205 ... | 170   | iwlwifi    | 6D5F1234C2 |
| 10ec:d723 | 103c:8319 | Realtek... | RTL8723DE Wireless Networ... | 138   | rtl8723de  | D7977A3B0E |
| 8086:1503 | 1043:849c | Intel      | 82579V Gigabit Network Co... | 138   | e1000e     | AC377EFFFB |
| 8086:088e | 8086:4060 | Intel      | Centrino Advanced-N 6235     | 101   | iwlwifi    | B884A5EAC4 |
| 8086:1539 | 1043:85f0 | Intel      | I211 Gigabit Network Conn... | 101   | igb        | 4A2455EAE6 |
| 8086:1502 | 17aa:21f3 | Intel      | 82579LM Gigabit Network C... | 97    | e1000e     | 6D5F1234C2 |
| 10de:03ef | 1458:e000 | Nvidia     | MCP61 Ethernet               | 94    | forcedeth  | BBF6B6F632 |
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 86    | iwlwifi    | AC77E66D3F |
| 8086:1502 | 17aa:21ce | Intel      | 82579LM Gigabit Network C... | 82    | e1000e     | FBF8462F41 |
| 8086:4239 | 8086:1311 | Intel      | Centrino Advanced-N 6200     | 77    | iwlwifi    | E2C04796A0 |
| 10de:03ef | 1043:8234 | Nvidia     | MCP61 Ethernet               | 67    | forcedeth  | 2A30939325 |
| 8086:10ea | 17aa:2153 | Intel      | 82577LM Gigabit Network C... | 66    | e1000e     | DA5E944C6C |
| 10de:03ef | 1043:83a4 | Nvidia     | MCP61 Ethernet               | 65    | forcedeth  | 3248DFD987 |
| 8086:1539 | 1849:1539 | Intel      | I211 Gigabit Network Conn... | 56    | igb        | 54A49FCBF7 |
| 8086:0082 | 8086:1321 | Intel      | Centrino Advanced-N 6205 ... | 55    | iwlwifi    | CA6EFEBBD7 |
| 8086:422b | 8086:1121 | Intel      | Centrino Ultimate-N 6300     | 54    | iwlwifi    | 8B920A3699 |
| 8086:4238 | 8086:1111 | Intel      | Centrino Ultimate-N 6300     | 51    | iwlwifi    | C99279F977 |
| 8086:10f5 | 17aa:20ee | Intel      | 82567LM Gigabit Network C... | 47    | e1000e     | FDAB3CF92F |
| 8086:0082 | 8086:1301 | Intel      | Centrino Advanced-N 6205 ... | 42    | iwlwifi    | B9A4817612 |
| 10de:03ef | 1462:7309 | Nvidia     | MCP61 Ethernet               | 36    | forcedeth  | 11D0376265 |
| 10de:0057 | 1043:812a | Nvidia     | CK804 Ethernet Controller    | 35    | forcedeth  | C92DC5D0CF |
| 8086:1539 | 1458:e000 | Intel      | I211 Gigabit Network Conn... | 34    | igb        | 2B34A6E94A |
| 8086:10de | 1028:0276 | Intel      | 82567LM-3 Gigabit Network... | 33    | e1000e     | 88DB43EE6F |
| 8086:1521 | 15d9:1521 | Intel      | I350 Gigabit Network Conn... | 32    | igb        | B4C8ABC585 |
| 8086:10f5 | 1028:0233 | Intel      | 82567LM Gigabit Network C... | 30    | e1000e     | 1F49A84F1F |
| 10de:0373 | 1043:8239 | Nvidia     | MCP55 Ethernet               | 29    | forcedeth  | 4EA0694850 |
| 14e4:170c | 1025:0090 | Broadco... | BCM4401-B0 100Base-TX        | 28    | b44        | 719BE91D02 |
| 8086:1049 | 17aa:20b9 | Intel      | 82566MM Gigabit Network C... | 28    | e1000e     | 7F41843359 |
| 8086:10c4 | 103c:30d8 | Intel      | 82562GT 10/100 Network Co... | 28    | e1000e     | 48EE31D6E9 |
| 8086:1502 | 1028:0493 | Intel      | 82579LM Gigabit Network C... | 28    | e1000e     | CA6EFEBBD7 |
| 8086:1502 | 1028:052c | Intel      | 82579LM Gigabit Network C... | 27    | e1000e     | 87DAB1466B |
| 8086:0091 | 8086:5201 | Intel      | Centrino Advanced-N 6230 ... | 26    | iwlwifi    | 4398E73607 |
| 8086:10d3 | 15d9:10d3 | Intel      | 82574L Gigabit Network Co... | 26    | e1000e     | 726EA75DCA |
| 8086:10d3 | 8086:a01f | Intel      | 82574L Gigabit Network Co... | 26    | e1000e     | 01E8F93721 |
| 8086:1502 | 1028:047e | Intel      | 82579LM Gigabit Network C... | 26    | e1000e     | 5C380FEC25 |
| 8086:422c | 8086:1301 | Intel      | Centrino Advanced-N 6200     | 26    | iwlwifi    | EEFC712947 |
| 14e4:4331 | 14e4:4331 | Broadco... | BCM4331 802.11a/b/g/n        | 24    | wl         | 16BDB52C40 |
| 14e4:170c | 103c:30a2 | Broadco... | BCM4401-B0 100Base-TX        | 23    | b44        | 531D26CDD8 |
| 8086:1503 | 1458:e000 | Intel      | 82579V Gigabit Network Co... | 23    | e1000e     | DD20758A89 |
| 14e4:170c | 1028:01f5 | Broadco... | BCM4401-B0 100Base-TX        | 21    | b44        | BFDE36E2F4 |
| 8086:10ea | 1028:040a | Intel      | 82577LM Gigabit Network C... | 21    | e1000e     | D588CD38C2 |
| 10ec:8136 | 103c:3567 | Realtek... | RTL810xE PCI Express Fast... | 19    | r8169      | 937DD869FC |
| 8086:10bd | 1028:0211 | Intel      | 82566DM-2 Gigabit Network... | 19    | e1000e     | 8C1C529BDC |
| 8086:10de | 1028:027f | Intel      | 82567LM-3 Gigabit Network... | 19    | e1000e     | DFA7361038 |
| 8086:10de | 103c:3048 | Intel      | 82567LM-3 Gigabit Network... | 19    | e1000e     | B511052CC4 |
| 8086:422c | 8086:1321 | Intel      | Centrino Advanced-N 6200     | 19    | iwlwifi    | D588CD38C2 |
| 10de:0373 | 1462:7250 | Nvidia     | MCP55 Ethernet               | 18    | forcedeth  | 005023EE9D |
| 10de:03ef | 1565:2505 | Nvidia     | MCP61 Ethernet               | 18    | forcedeth  | E327FDD558 |
| 8086:294c | 8086:0001 | Intel      | 82566DC-2 Gigabit Network... | 18    | e1000e     | 969A371A99 |
| 8086:422b | 8086:1101 | Intel      | Centrino Ultimate-N 6300     | 18    | iwlwifi    | ED317797F0 |
| 8086:088e | 8086:4460 | Intel      | Centrino Advanced-N 6235     | 17    | iwlwifi    | B20F51D9C3 |
| 8086:10bd | 103c:2818 | Intel      | 82566DM-2 Gigabit Network... | 17    | e1000e     | 073E07ECC0 |
| 8086:1502 | 103c:179b | Intel      | 82579LM Gigabit Network C... | 17    | e1000e     | ED317797F0 |
| 10b7:9200 | 10b7:1000 | 3Com       | 3c905C-TX/TX-M [Tornado]     | 16    | 3c59x      | E56205BFC8 |
| 10de:0057 | 1043:8141 | Nvidia     | CK804 Ethernet Controller    | 16    | forcedeth  | 38155B66BB |
| 1106:3065 | 1043:80ed | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 16    | via_rhine  | D9174E33E4 |
| 8086:104b | 8086:0001 | Intel      | 82566DC Gigabit Network C... | 16    | e1000e     | 9E17250CD3 |
| 8086:10bd | 103c:281e | Intel      | 82566DM-2 Gigabit Network... | 16    | e1000e     | D7AB000EA5 |
| 8086:1502 | 103c:161c | Intel      | 82579LM Gigabit Network C... | 16    | e1000e     | 6F7AAF1391 |
| 10de:0269 | 1043:816a | Nvidia     | MCP51 Ethernet Controller    | 15    | forcedeth  | 15B9CC8D28 |
| 10de:0373 | 1458:e000 | Nvidia     | MCP55 Ethernet               | 15    | forcedeth  | 0CCA59B833 |
| 1106:3065 | 1849:3065 | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 15    | via_rhine  | 83CCCBAF1A |
| 8086:104a | 103c:2800 | Intel      | 82566DM Gigabit Network C... | 15    | e1000e     | C6129C8C14 |
| 8086:10ea | 103c:7008 | Intel      | 82577LM Gigabit Network C... | 15    | e1000e     | AB17752168 |
| 8086:150c | 1043:8457 | Intel      | 82583V Gigabit Network Co... | 15    | e1000e     | 927A46266A |
| 8086:0091 | 8086:5221 | Intel      | Centrino Advanced-N 6230 ... | 14    | iwlwifi    | FC0B23D4DC |
| 8086:1502 | 103c:339a | Intel      | 82579LM Gigabit Network C... | 14    | e1000e     | 76F6D2AF22 |
| 8086:1533 | 1043:8557 | Intel      | I210 Gigabit Network Conn... | 14    | igb        | 510AE49DF2 |
| 10de:0373 | 1043:cb84 | Nvidia     | MCP55 Ethernet               | 13    | forcedeth  | BC336B5882 |
| 10de:03ef | 103c:2a6c | Nvidia     | MCP61 Ethernet               | 13    | forcedeth  | 579C5E3CDC |
| 14e4:170c | 1028:01af | Broadco... | BCM4401-B0 100Base-TX        | 13    | b44        | 586A6A9F8A |
| 8086:1049 | 17aa:20de | Intel      | 82566MM Gigabit Network C... | 13    | e1000e     | F5D4852384 |
| 8086:1092 | 1179:ff10 | Intel      | PRO/100 VE Network Connec... | 13    | e100       | 4FFE571137 |
| 8086:10d3 | 1043:8369 | Intel      | 82574L Gigabit Network Co... | 13    | e1000e     | AB7179BE16 |
| 8086:10f0 | 1025:8000 | Intel      | 82578DC Gigabit Network C... | 13    | e1000e     | A4DA822D7B |
| 8086:1502 | 1028:0534 | Intel      | 82579LM Gigabit Network C... | 13    | e1000e     | 8C26DF88EE |
| 8086:1503 | 103c:17ab | Intel      | 82579V Gigabit Network Co... | 13    | e1000e     | 3B64B265CF |
| 8086:1533 | 15d9:1533 | Intel      | I210 Gigabit Network Conn... | 13    | igb        | D05461EFDA |
| 8086:1539 | 8086:0000 | Intel      | I211 Gigabit Network Conn... | 13    | igb        | 55981AF24A |
| 10de:0057 | 1458:e000 | Nvidia     | CK804 Ethernet Controller    | 12    | forcedeth  | 556AE96F13 |
| 10de:03ef | 1565:3407 | Nvidia     | MCP61 Ethernet               | 12    | forcedeth  | 2D17F5BB22 |
| 8086:10bf | 17aa:20ee | Intel      | 82567LF Gigabit Network C... | 12    | e1000e     | AEA2A879A0 |
| 8086:10ea | 1028:040b | Intel      | 82577LM Gigabit Network C... | 12    | e1000e     | 80B359DC57 |
| 8086:1502 | 103c:1589 | Intel      | 82579LM Gigabit Network C... | 12    | e1000e     | E14EB74EA5 |
| 10de:0269 | 1458:e000 | Nvidia     | MCP51 Ethernet Controller    | 11    | forcedeth  | 3C440908D8 |
| 10de:03ef | 103c:2a99 | Nvidia     | MCP61 Ethernet               | 11    | forcedeth  | 4950E6BB13 |
| 8086:0087 | 8086:1306 | Intel      | Centrino Advanced-N + WiM... | 11    | iwlwifi    | 26EAFF6014 |
| 8086:10c0 | 1028:020d | Intel      | 82562V-2 10/100 Network C... | 11    | e1000e     | C80A50B2B4 |
| 8086:10f5 | 1028:024f | Intel      | 82567LM Gigabit Network C... | 11    | e1000e     | 5A8B3F34A3 |
| 8086:1502 | 103c:3397 | Intel      | 82579LM Gigabit Network C... | 11    | e1000e     | 195649904F |
| 8086:0087 | 8086:1301 | Intel      | Centrino Advanced-N + WiM... | 10    | iwlwifi    | 195F0109A8 |
| 8086:10de | 103c:3034 | Intel      | 82567LM-3 Gigabit Network... | 10    | e1000e     | 5DC57BDE0C |
| 8086:10ea | 103c:7007 | Intel      | 82577LM Gigabit Network C... | 10    | e1000e     | 9D71D7ED76 |
| 8086:10f0 | 8086:0036 | Intel      | 82578DC Gigabit Network C... | 10    | e1000e     | F2560038AF |
| 8086:1502 | 1028:0494 | Intel      | 82579LM Gigabit Network C... | 10    | e1000e     | 31F0876A89 |
| 8086:1502 | 1028:04a3 | Intel      | 82579LM Gigabit Network C... | 10    | e1000e     | 19E1CA5871 |
| 8086:1502 | 103c:1497 | Intel      | 82579LM Gigabit Network C... | 10    | e1000e     | 6227F00E30 |
| 8086:1503 | 1025:8000 | Intel      | 82579V Gigabit Network Co... | 10    | e1000e     | CABB268939 |
| 10b7:9055 | 10b7:9055 | 3Com       | 3c905B 100BaseTX [Cyclone]   | 9     | 3c59x      | 0200BA924B |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1455 | 1022:1455 | AMD        | Zeppelin/Renoir PCIe Dumm... | 279   |            | D084D64BDF |
| 1022:145a | 1022:145a | AMD        | Zeppelin/Raven/Raven2 PCI... | 279   |            | D084D64BDF |
| 1022:1455 | 1043:8747 | AMD        | Zeppelin/Renoir PCIe Dumm... | 37    |            | 4A2455EAE6 |
| 1022:145a | 1043:8747 | AMD        | Zeppelin/Raven/Raven2 PCI... | 37    |            | 4A2455EAE6 |
| 8086:9d26 |           | Intel      | Skylake-U/Y Northpeak        | 8     | intel_t... | 1CC0697D7C |
| 1022:1455 | 1462:7a38 | AMD        | Zeppelin/Renoir PCIe Dumm... | 6     |            | 4B9FC100D8 |
| 1022:145a | 1458:d000 | AMD        | Zeppelin/Raven/Raven2 PCI... | 6     |            | A6040FD25F |
| 1022:145a | 1462:7a38 | AMD        | Zeppelin/Raven/Raven2 PCI... | 6     |            | 4B9FC100D8 |
| 1022:145a | 1043:876b | AMD        | Zeppelin/Raven/Raven2 PCI... | 5     |            | E090419355 |
| 1022:145a | 1002:15dd | AMD        | Zeppelin/Raven/Raven2 PCI... | 3     |            | 941367D018 |
| 1022:1455 | 1019:9ce5 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 06776696F3 |
| 1022:1455 | 103c:8399 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 9440F6405B |
| 1022:1455 | 1462:7a40 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 515A7DFA4F |
| 1022:1455 | 1462:7b85 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 29C3842F1D |
| 1022:1455 | 1462:7b86 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 73F23254C0 |
| 1022:1455 | 1462:7b89 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 63314DCB31 |
| 1022:145a | 1019:9ce5 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 06776696F3 |
| 1022:145a | 103c:8399 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 9440F6405B |
| 1022:145a | 1462:7a33 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | D8D0364599 |
| 1022:145a | 1462:7a40 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 515A7DFA4F |
| 1022:145a | 1462:7b84 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 327877AB6E |
| 1022:145a | 1462:7b85 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 29C3842F1D |
| 1022:145a | 1462:7b86 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 73F23254C0 |
| 1022:145a | 1462:7b89 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 63314DCB31 |
| 1022:145a | 17aa:36e8 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 78596220D1 |
| 1022:1485 | 1022:1485 | AMD        | Starship/Matisse Reserved... | 1     |            | 35B960D525 |
| 1022:148a | 1022:148a | AMD        | Starship/Matisse PCIe Dum... | 1     |            | 35B960D525 |
| 8086:a126 |           | Intel      | 100 Series/C230 Series Ch... | 1     | intel_t... | C263278BF1 |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15e6 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Non-S... | 13    | i2c_amd... | 048229855F |
| 8086:9d24 |           | Intel      | Skylake-U/Y SPI Controller   | 8     |            | 3E70A8DFF1 |
| 8086:9d35 | 8086:7270 | Intel      | Sunrise Point-LP Integrat... | 8     | intel_i... | 9D9D8E830B |
| 8086:9d35 | 8086:9d35 | Intel      | Sunrise Point-LP Integrat... | 7     | intel_i... | C3AA237F35 |
| 8086:22d8 | 1043:1400 | Intel      | Integrated Sensor Solution   | 6     | intel_i... | 838DD8C3AC |
| 8086:22d8 | 103c:827c | Intel      | Integrated Sensor Solution   | 5     | intel_i... | DD16DF4133 |
| 8086:22d8 | 1043:13a0 | Intel      | Integrated Sensor Solution   | 5     | intel_i... | 1EB4640C84 |
| 8086:9d35 | 103c:8486 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 7DEF867A41 |
| 8086:9d35 | 103c:8488 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 2F6DFEC51C |
| 1022:15e6 | 103c:85ea | AMD        | Raven/Raven2/Renoir Non-S... | 3     | i2c_amd... | D7977A3B0E |
| 8086:22d8 | 103c:813e | Intel      | Integrated Sensor Solution   | 3     | intel_i... | F91E0FBE6B |
| 8086:9d35 | 1028:07a4 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 73B87C222F |
| 8086:9d35 | 1028:07aa | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | BC69AFD822 |
| 8086:9d35 | 103c:830f | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | C4D6A7BC54 |
| 8086:9d35 | 103c:83b9 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 831911B060 |
| 8086:9d35 | 17aa:3807 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 1DD80D33E5 |
| 8086:a135 | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 3     | intel_i... | 62AF0556D3 |
| 1022:15e4 | 103c:8496 | AMD        | Raven/Raven2/Renoir Senso... | 2     |            | F720A735A8 |
| 104c:9065 |           | Texas I... | TMS320DM642                  | 2     |            | A74B989748 |
| 8086:22d8 | 8086:7270 | Intel      | Integrated Sensor Solution   | 2     | intel_i... | DF76656467 |
| 8086:9d35 | 1025:111e | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | D6EFA0F211 |
| 8086:9d35 | 1028:073b | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 10A11C50C0 |
| 8086:9d35 | 1028:0740 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | F938CE631A |
| 8086:9d35 | 1028:0741 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | D302412809 |
| 8086:9d35 | 1028:07eb | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 7EB57A3809 |
| 8086:9d35 | 1028:0804 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 9D1947C3A7 |
| 8086:9d35 | 103c:827d | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | AE7D79F749 |
| 8086:9d35 | 103c:82c1 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | A9E42C34F6 |
| 8086:9d35 | 103c:8313 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 22FE75A663 |
| 8086:9d35 | 103c:83b2 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 240B48EAA4 |
| 8086:9d35 | 103c:83c4 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 65B956E887 |
| 8086:9d35 | 103c:84d8 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | A9BAF3BF1B |
| 8086:9d35 | 1043:1c90 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 7BBD1AB6FE |
| 8086:9d35 | 17aa:2238 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 01BED504BA |
| 8086:9d35 | 17aa:224e | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 3AC5B5C4AD |
| 8086:a2a4 |           | Intel      | 200 Series/Z370 Chipset F... | 2     |            | 46EA2E591E |
| 0090:0000 | 0090:0000 |            |                              | 1     |            | B562E609ED |
| 1022:15e4 | 103c:8497 | AMD        | Raven/Raven2/Renoir Senso... | 1     |            | 314C52C853 |
| 1274:5882 |           | Ensoniq    |                              | 1     |            | 3F25A03C59 |
| 12f4:5000 |           | Megatel    |                              | 1     |            | F9A4969283 |
| 1a39:0004 | 1a39:e020 |            |                              | 1     |            | 93A39661EC |
| 8086:22d8 | 1028:06ea | Intel      | Integrated Sensor Solution   | 1     | intel_i... | 721C1A7DC3 |
| 8086:22d8 | 1043:1bdd | Intel      | Integrated Sensor Solution   | 1     | intel_i... | E3400F39DF |
| 8086:22d8 | 1043:1c60 | Intel      | Integrated Sensor Solution   | 1     | intel_i... | 23E48DD182 |
| 8086:22d8 | 1071:a126 | Intel      | Integrated Sensor Solution   | 1     | intel_i... | F2981C1775 |
| 8086:9d35 | 1028:06e6 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | C97022A8FC |
| 8086:9d35 | 1028:0744 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | B4A5AF0E65 |
| 8086:9d35 | 1028:077a | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 57D57D82FE |
| 8086:9d35 | 1028:07ba | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 112EB80A9E |
| 8086:9d35 | 1028:0808 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | A06F19936B |
| 8086:9d35 | 103c:8197 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 910D564E8E |
| 8086:9d35 | 103c:81a1 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | C894E5633B |
| 8086:9d35 | 103c:81ad | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 84C8A9779B |
| 8086:9d35 | 103c:8251 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | C77AFE79C3 |
| 8086:9d35 | 103c:827f | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 7E10A5E689 |
| 8086:9d35 | 103c:82cb | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | FDB567A59E |
| 8086:9d35 | 103c:83b3 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | ECE59B9429 |
| 8086:9d35 | 103c:83ba | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 3743010FB5 |
| 8086:9d35 | 103c:8438 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 7F01433E42 |
| 8086:9d35 | 103c:8483 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 8B7A2D2A08 |
| 8086:9d35 | 103c:8487 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | C8C863DB3A |
| 8086:9d35 | 103c:8503 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | EC7FFC8F98 |
| 8086:9d35 | 1043:1c40 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 9565CCD6A2 |
| 8086:9d35 | 144d:c141 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 323C96D0DE |
| 8086:9d35 | 152d:1147 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 7DA5C4A4FA |
| 8086:9d35 | 152d:1182 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 57487D8BF7 |
| 8086:9d35 | 17aa:2241 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 1038A34C39 |
| 8086:9d35 | 17aa:380d | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | D838D80F49 |
| 8086:9d35 | 17aa:3812 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 57EC66B289 |
| 8086:9d35 | 17aa:504c | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 3C1A4327F5 |
| 8086:9d35 | 17aa:506c | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | DBA78E9C22 |
| 8086:9d35 | 17aa:506d | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 0818236221 |
| 8086:9d35 | 19e5:3e00 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 3DD5AAE701 |
| 8086:a135 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 1     |            | BB8832ACBD |
| 8086:a135 | 8086:a135 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 2E35C3E421 |

### Parallel controller (ieee1284) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 9710:9865 | a000:2000 | MosChip... | PCI 9865 Multi-I/O Contro... | 7     | parport_pc | 9EF947B594 |
| 9710:9912 | a000:2000 | MosChip... | PCIe 9912 Multi-I/O Contr... | 6     | parport... | 92F011CFCF |
| ffff:9865 | a000:2000 | Illegal... | Parallel controller          | 3     |            | 8C4716B30A |
| 125b:9100 | a000:2000 | Asix El... | Electronics Parallel cont... | 1     |            | 87DAB1466B |

### Performance counters (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2f30 | 8086:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    | hswep_u... | A8F2B39356 |
| 8086:2f34 | 8086:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    | hswep_u... | A8F2B39356 |
| 8086:2f7d | 8086:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | A8F2B39356 |
| 8086:2f36 | 8086:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 54    | hswep_u... | A8F2B39356 |
| 8086:2f37 | 8086:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 54    | hswep_u... | A8F2B39356 |
| 8086:2015 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 47    |            | 8E73F804F5 |
| 8086:204c | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 47    | skx_uncore | 8E73F804F5 |
| 8086:204d | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 47    | skx_uncore | 8E73F804F5 |
| 8086:2058 | 8086:0000 | Intel      | Sky Lake-E KTI 0             | 27    | skx_uncore | 8E73F804F5 |
| 8086:3c43 | 1043:84ef | Intel      | Xeon E5/Core i7 Ring to P... | 20    | snbep_u... | 1E7C5CF3CF |
| 8086:3c44 | 1043:84ef | Intel      | Xeon E5/Core i7 Ring to Q... | 20    | snbep_u... | 1E7C5CF3CF |
| 8086:3c46 | 1043:84ef | Intel      | Xeon E5/Core i7 Processor... | 20    | snbep_u... | 1E7C5CF3CF |
| 8086:3ce6 | 1043:84ef | Intel      | Xeon E5/Core i7 QuickPath... | 20    |            | 1E7C5CF3CF |
| 8086:0e36 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 18    | ivbep_u... | 84D3F5ED57 |
| 8086:27a3 |           | Intel      | 945GM/GU Chipset Hardware... | 18    |            | FDEA938323 |
| 8086:0e30 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 17    | ivbep_u... | EEE7D322DF |
| 8086:0e34 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 17    | ivbep_u... | EEE7D322DF |
| 8086:0e36 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 17    | ivbep_u... | EEE7D322DF |
| 8086:2088 | 8086:0000 | Intel      | Sky Lake-E DDRIO Registers   | 17    | skx_uncore | 0234D26806 |
| 8086:6f30 | 8086:6f30 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 17    | bdx_uncore | 7F1BE20709 |
| 8086:6f34 | 8086:6f34 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 17    | bdx_uncore | 7F1BE20709 |
| 8086:6f36 | 8086:6f36 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 17    | bdx_uncore | 7F1BE20709 |
| 8086:6f37 | 8086:6f37 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 17    | bdx_uncore | 7F1BE20709 |
| 8086:6f7d | 8086:6f7d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 17    |            | 7F1BE20709 |
| 8086:6f30 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6f34 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6f36 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6f37 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6f7d | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:3c43 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to P... | 15    | snbep_u... | E14EB74EA5 |
| 8086:3c44 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to Q... | 15    | snbep_u... | E14EB74EA5 |
| 8086:3ce6 | 8086:0000 | Intel      | Xeon E5/Core i7 QuickPath... | 15    |            | E14EB74EA5 |
| 8086:6f32 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 15    | bdx_uncore | 17BF7A3CBC |
| 8086:6f33 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 15    | bdx_uncore | 17BF7A3CBC |
| 8086:0e34 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 14    | ivbep_u... | 84D3F5ED57 |
| 8086:3c46 |           | Intel      | Xeon E5/Core i7 Processor... | 13    | snbep_u... | E14EB74EA5 |
| 8086:0e30 |           | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 10    | ivbep_u... | 84D3F5ED57 |
| 8086:2f32 | 8086:2f32 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 9     | hswep_u... | AF9F6ACE3F |
| 8086:3c43 | 1458:3c43 | Intel      | Xeon E5/Core i7 Ring to P... | 8     | snbep_u... | E3CD42A469 |
| 8086:3c44 | 1458:3c44 | Intel      | Xeon E5/Core i7 Ring to Q... | 8     | snbep_u... | E3CD42A469 |
| 8086:3c46 | 1458:3c46 | Intel      | Xeon E5/Core i7 Processor... | 8     | snbep_u... | E3CD42A469 |
| 8086:3ce6 | 1458:3ce6 | Intel      | Xeon E5/Core i7 QuickPath... | 8     |            | E3CD42A469 |
| 8086:2f33 | 8086:2f33 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 6     | hswep_u... | AF9F6ACE3F |
| 8086:3424 |           | Intel      | 7500/5520/5500/X58 Perfor... | 6     |            | 6710749660 |
| 8086:2f38 | 8086:2f38 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 5     | hswep_u... | AF9F6ACE3F |
| 8086:0e30 | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     | ivbep_u... | 7B26B20B57 |
| 8086:0e30 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     | ivbep_u... | ACF28B5D91 |
| 8086:0e34 | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     | ivbep_u... | 7B26B20B57 |
| 8086:2f30 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | C9D389B2A3 |
| 8086:2f34 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | C9D389B2A3 |
| 8086:2f36 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | C9D389B2A3 |
| 8086:2f36 | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | 608FAFB692 |
| 8086:2f37 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | C9D389B2A3 |
| 8086:2f37 | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | 608FAFB692 |
| 8086:2f7d | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | C9D389B2A3 |
| 8086:0e30 | 1458:3c46 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     | ivbep_u... | DD20758A89 |
| 8086:0e30 | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     | ivbep_u... | 100EFA1F4A |
| 8086:0e34 | 1458:3c43 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     | ivbep_u... | DD20758A89 |
| 8086:0e34 | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     | ivbep_u... | 100EFA1F4A |
| 8086:0e36 | 1458:3c44 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     | ivbep_u... | DD20758A89 |
| 8086:0e36 | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     | ivbep_u... | 100EFA1F4A |
| 8086:2f30 | 1849:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     | hswep_u... | 776B559B1F |
| 8086:2f34 | 1849:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     | hswep_u... | 776B559B1F |
| 8086:2f36 | 1849:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     | hswep_u... | 776B559B1F |
| 8086:2f37 | 1849:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     | hswep_u... | 776B559B1F |
| 8086:2f7d | 1849:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     |            | 776B559B1F |
| 8086:6f30 | 1849:6f30 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     | bdx_uncore | 87D6B1C03E |
| 8086:6f32 | 8086:6f32 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     | bdx_uncore | 7658F21E98 |
| 8086:6f33 | 8086:6f33 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     | bdx_uncore | 7658F21E98 |
| 8086:6f34 | 1849:6f34 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     | bdx_uncore | 87D6B1C03E |
| 8086:6f36 | 1849:6f36 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     | bdx_uncore | 87D6B1C03E |
| 8086:6f37 | 1849:6f37 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     | bdx_uncore | 87D6B1C03E |
| 8086:6f7d | 1849:6f7d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     |            | 87D6B1C03E |
| 8086:0e30 | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     | ivbep_u... | 07278BAD4B |
| 8086:0e30 | 1734:11b5 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     | ivbep_u... | 961A7ADB3E |
| 8086:0e34 | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     | ivbep_u... | 07278BAD4B |
| 8086:0e34 | 1734:11b5 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     | ivbep_u... | 961A7ADB3E |
| 8086:0e36 | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     | ivbep_u... | 07278BAD4B |
| 8086:0e36 | 1734:11b5 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     | ivbep_u... | 961A7ADB3E |
| 8086:2f30 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     | hswep_u... | 52D5275C7F |
| 8086:2f34 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     | hswep_u... | 52D5275C7F |
| 8086:2f36 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     | hswep_u... | 52D5275C7F |
| 8086:2f37 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     | hswep_u... | 52D5275C7F |
| 8086:2f38 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     |            | B7B182E812 |
| 8086:2f7d | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     |            | 52D5275C7F |
| 8086:3c43 | 1028:0497 | Intel      | Xeon E5/Core i7 Ring to P... | 2     | snbep_u... | 428006990E |
| 8086:3c43 | 103c:18a8 | Intel      | Xeon E5/Core i7 Ring to P... | 2     | snbep_u... | 4805EBBD1F |
| 8086:3c43 | 1043:84f0 | Intel      | Xeon E5/Core i7 Ring to P... | 2     | snbep_u... | 996F55BB36 |
| 8086:3c43 | 1462:7760 | Intel      | Xeon E5/Core i7 Ring to P... | 2     | snbep_u... | 748D276276 |
| 8086:3c43 | 1849:3c43 | Intel      | Xeon E5/Core i7 Ring to P... | 2     | snbep_u... | FE65462E73 |
| 8086:3c43 | 8086:357e | Intel      | Xeon E5/Core i7 Ring to P... | 2     | snbep_u... | F65EC09250 |
| 8086:3c44 | 1028:0497 | Intel      | Xeon E5/Core i7 Ring to Q... | 2     | snbep_u... | 428006990E |
| 8086:3c44 | 103c:18a8 | Intel      | Xeon E5/Core i7 Ring to Q... | 2     | snbep_u... | 4805EBBD1F |
| 8086:3c44 | 1043:84f0 | Intel      | Xeon E5/Core i7 Ring to Q... | 2     | snbep_u... | 996F55BB36 |
| 8086:3c44 | 1462:7760 | Intel      | Xeon E5/Core i7 Ring to Q... | 2     | snbep_u... | 748D276276 |
| 8086:3c44 | 1849:3c44 | Intel      | Xeon E5/Core i7 Ring to Q... | 2     | snbep_u... | FE65462E73 |
| 8086:3c44 | 8086:357e | Intel      | Xeon E5/Core i7 Ring to Q... | 2     | snbep_u... | F65EC09250 |
| 8086:3c46 | 1028:0497 | Intel      | Xeon E5/Core i7 Processor... | 2     | snbep_u... | 428006990E |
| 8086:3c46 | 103c:18a8 | Intel      | Xeon E5/Core i7 Processor... | 2     | snbep_u... | 4805EBBD1F |
| 8086:3c46 | 1043:84f0 | Intel      | Xeon E5/Core i7 Processor... | 2     | snbep_u... | 996F55BB36 |

### Pic (8259) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:342e |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 201   | i7core_... | B481805845 |
| 8086:3422 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 199   |            | B481805845 |
| 8086:3423 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 199   |            | B481805845 |
| 8086:3438 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 127   | i5500_temp | B481805845 |
| 8086:3425 |           | Intel      | 7500/5520/5500/X58 Physic... | 68    |            | 47FD7AB796 |
| 8086:3426 |           | Intel      | 7500/5520/5500/X58 Routin... | 68    |            | 47FD7AB796 |
| 8086:3427 |           | Intel      | 7500/5520/5500 Physical a... | 62    |            | 47FD7AB796 |
| 8086:3428 |           | Intel      | 7500/5520/5500 Routing & ... | 62    |            | 47FD7AB796 |
| 8086:3422 | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 15    |            | A72C60B73B |
| 8086:3423 | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 15    |            | A72C60B73B |
| 8086:342e | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 15    | i7core_... | A72C60B73B |
| 8086:3422 | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 9     |            | CC88E139CC |
| 8086:3423 | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 9     |            | CC88E139CC |
| 8086:342e | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 9     | i7core_... | CC88E139CC |
| 8086:3422 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     |            | 6806624961 |
| 8086:3423 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     |            | 6806624961 |
| 8086:342e | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     | i7core_... | 6806624961 |
| 8086:3422 | 0086:0022 | Intel      | 7500/5520/5500/X58 I/O Hu... | 6     |            | 29B0070304 |
| 8086:3423 | 0086:0023 | Intel      | 7500/5520/5500/X58 I/O Hu... | 6     |            | 29B0070304 |
| 8086:342e | 0086:002e | Intel      | 7500/5520/5500/X58 I/O Hu... | 6     | i7core_... | 29B0070304 |
| 8086:3422 | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     |            | 138B84322E |
| 8086:3423 | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     |            | 138B84322E |
| 8086:3425 | 0086:00dc | Intel      | 7500/5520/5500/X58 Physic... | 3     |            | 138B84322E |
| 8086:3426 | 0086:00dc | Intel      | 7500/5520/5500/X58 Routin... | 3     |            | 138B84322E |
| 8086:3427 | 0086:00dc | Intel      | 7500/5520/5500 Physical a... | 3     |            | 138B84322E |
| 8086:3428 | 0086:00dc | Intel      | 7500/5520/5500 Routing & ... | 3     |            | 138B84322E |
| 8086:342e | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     | i7core_... | 138B84322E |
| 8086:3438 | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     | i5500_temp | 138B84322E |
| 8086:3422 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     |            | 81C929F40D |
| 8086:3422 | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     |            | DEC98C8F86 |
| 8086:3423 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     |            | 81C929F40D |
| 8086:3423 | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     |            | DEC98C8F86 |
| 8086:3425 | 0043:0063 | Intel      | 7500/5520/5500/X58 Physic... | 2     |            | 81C929F40D |
| 8086:3425 | 0086:00da | Intel      | 7500/5520/5500/X58 Physic... | 2     |            | DEC98C8F86 |
| 8086:3426 | 0043:0063 | Intel      | 7500/5520/5500/X58 Routin... | 2     |            | 81C929F40D |
| 8086:3426 | 0086:00da | Intel      | 7500/5520/5500/X58 Routin... | 2     |            | DEC98C8F86 |
| 8086:3427 | 0043:0063 | Intel      | 7500/5520/5500 Physical a... | 2     |            | 81C929F40D |
| 8086:3427 | 0086:00da | Intel      | 7500/5520/5500 Physical a... | 2     |            | DEC98C8F86 |
| 8086:3428 | 0043:0063 | Intel      | 7500/5520/5500 Routing & ... | 2     |            | 81C929F40D |
| 8086:3428 | 0086:00da | Intel      | 7500/5520/5500 Routing & ... | 2     |            | DEC98C8F86 |
| 8086:342e | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     | i7core_... | 81C929F40D |
| 8086:342e | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     | i7core_... | DEC98C8F86 |
| 8086:3438 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     | i5500_temp | 81C929F40D |
| 8086:3438 | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     | i5500_temp | DEC98C8F86 |
| 8086:3422 | 0034:0027 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | C7E9D74C3D |
| 8086:3422 | 0086:0000 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | CBBE408AAC |
| 8086:3423 | 0034:0027 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | C7E9D74C3D |
| 8086:3423 | 0086:0000 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | CBBE408AAC |
| 8086:3425 | 0034:0027 | Intel      | 7500/5520/5500/X58 Physic... | 1     |            | C7E9D74C3D |
| 8086:3425 | 0086:0000 | Intel      | 7500/5520/5500/X58 Physic... | 1     |            | CBBE408AAC |
| 8086:3426 | 0034:0027 | Intel      | 7500/5520/5500/X58 Routin... | 1     |            | C7E9D74C3D |
| 8086:3426 | 0086:0000 | Intel      | 7500/5520/5500/X58 Routin... | 1     |            | CBBE408AAC |
| 8086:3427 | 0034:0027 | Intel      | 7500/5520/5500 Physical a... | 1     |            | C7E9D74C3D |
| 8086:3427 | 0086:0000 | Intel      | 7500/5520/5500 Physical a... | 1     |            | CBBE408AAC |
| 8086:3428 | 0034:0027 | Intel      | 7500/5520/5500 Routing & ... | 1     |            | C7E9D74C3D |
| 8086:3428 | 0086:0000 | Intel      | 7500/5520/5500 Routing & ... | 1     |            | CBBE408AAC |
| 8086:342e | 0034:0027 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     | i7core_... | C7E9D74C3D |
| 8086:342e | 0086:0000 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     | i7core_... | CBBE408AAC |
| 8086:3438 | 0034:0027 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     | i5500_temp | C7E9D74C3D |
| 8086:3438 | 0086:0000 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     | i5500_temp | CBBE408AAC |

### Pic (io(x)-apic) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:342d |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 64    |            | 726EA75DCA |
| 8086:342f |           | Intel      | 7500/5520/5500/X58 Truste... | 62    |            | 47FD7AB796 |
| 8086:2026 | 8086:2026 | Intel      | Sky Lake-E IOAPIC            | 45    |            | 8E73F804F5 |
| 8086:2036 | 8086:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 45    |            | 8E73F804F5 |
| 8086:2f2c | 8086:0000 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 30    |            | A8F2B39356 |
| 1106:5364 |           | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 29    |            | B3224EB5FC |
| 1106:5327 |           | VIA Tec... | P4M890 I/O APIC Interrupt... | 21    |            | ECBFA57012 |
| 8086:3c2c | 1043:84ef | Intel      | Xeon E5/Core i7 I/O APIC     | 20    |            | 1E7C5CF3CF |
| 8086:0e2c | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 17    |            | EEE7D322DF |
| 8086:3c2c | 8086:3c2c | Intel      | Xeon E5/Core i7 I/O APIC     | 16    |            | E14EB74EA5 |
| 8086:6f2c | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:0e2c | 8086:0e2c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 15    |            | 84D3F5ED57 |
| 8086:6f2c | 8086:0000 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 13    |            | 7F1BE20709 |
| 1106:5336 |           | VIA Tec... | K8M890CE I/O APIC Interru... | 10    |            | FEDA3B155D |
| 8086:2f2c | 1028:0617 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 9     |            | 3B5017848A |
| 8086:3c2c | 1458:5000 | Intel      | Xeon E5/Core i7 I/O APIC     | 8     |            | E3CD42A469 |
| 1106:5308 | 1849:5308 | VIA Tec... | PT894 I/O APIC Interrupt ... | 6     |            | FFD7AFA075 |
| 8086:3c2c | 103c:18a8 | Intel      | Xeon E5/Core i7 I/O APIC     | 6     |            | 4805EBBD1F |
| 1106:5238 |           | VIA Tec... | K8T890 I/O APIC Interrupt... | 4     |            | D9174E33E4 |
| 1106:5364 | 103c:3030 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 4     |            | 7EECEB0DB3 |
| 1106:5364 | 1106:5364 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 4     |            | 95BF887281 |
| 8086:0e2c | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     |            | 7B26B20B57 |
| 8086:2f2c | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | C9D389B2A3 |
| 8086:2f2c | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | 608FAFB692 |
| 8086:3504 |           | Intel      | 6311ESB/6321ESB I/OxAPIC ... | 4     |            | 37E5DABF3C |
| 1106:5351 |           | VIA Tec... | VT3351 I/O APIC Interrupt... | 3     |            | EBF0DCD676 |
| 1106:5364 | 1849:5364 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 3     |            | 78DDA2C16B |
| 8086:0e2c | 1458:5000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     |            | DD20758A89 |
| 8086:0e2c | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     |            | 100EFA1F4A |
| 8086:2026 | 8086:0000 | Intel      | Sky Lake-E IOAPIC            | 3     |            | 0617E49F12 |
| 8086:2036 | 8086:0000 | Intel      | Sky Lake-E IOxAPIC Config... | 3     |            | 0617E49F12 |
| 8086:2f2c | 15d9:0857 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     |            | D05461EFDA |
| 8086:2f2c | 1849:2f2c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     |            | 776B559B1F |
| 8086:342d | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     |            | 138B84322E |
| 8086:342f | 0086:00dc | Intel      | 7500/5520/5500/X58 Truste... | 3     |            | 138B84322E |
| 8086:6f2c | 1849:6f2c | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     |            | 87D6B1C03E |
| 1106:5327 | 1849:5327 | VIA Tec... | P4M890 I/O APIC Interrupt... | 2     |            | DAD584057B |
| 1106:5353 | 17aa:388a | VIA Tec... | VX800/VX820 APIC and Cent... | 2     |            | CE7524ED3B |
| 8086:0326 | 15d9:7980 | Intel      | 6700/6702PXH I/OxAPIC Int... | 2     |            | 8EB1C21341 |
| 8086:0e2c | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | 07278BAD4B |
| 8086:0e2c | 1734:11b5 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | 961A7ADB3E |
| 8086:2f2c | 1028:064c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     |            | E1BABF19AD |
| 8086:2f2c | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     |            | 52D5275C7F |
| 8086:342d | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     |            | DEC98C8F86 |
| 8086:342f | 0086:00da | Intel      | 7500/5520/5500/X58 Truste... | 2     |            | DEC98C8F86 |
| 8086:3c2c | 1028:0497 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | 428006990E |
| 8086:3c2c | 1043:84f0 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | 996F55BB36 |
| 8086:3c2c | 1462:7760 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | 748D276276 |
| 8086:3c2c | 1849:3c2c | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | FE65462E73 |
| 8086:3c2c | 8086:357e | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | F65EC09250 |
| 8086:6f2c | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 140DAF886E |
| 8086:6f2c | 15d9:0824 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 6C96E4A591 |
| 1106:5238 | 1734:1093 | VIA Tec... | K8T890 I/O APIC Interrupt... | 1     |            | E9825FB39A |
| 1106:5327 | 1631:e035 | VIA Tec... | P4M890 I/O APIC Interrupt... | 1     |            | B3494EC9DB |
| 1106:5336 | 1043:8297 | VIA Tec... | K8M890CE I/O APIC Interru... | 1     |            | 9FC75A870D |
| 1106:5351 | 1849:5351 | VIA Tec... | VT3351 I/O APIC Interrupt... | 1     |            | D3A94CD051 |
| 1106:5364 | 1019:2125 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 1     |            | A098C98B04 |
| 8086:0326 |           | Intel      | 6700/6702PXH I/OxAPIC Int... | 1     |            | 219383F559 |
| 8086:0326 | 103c:12f1 | Intel      | 6700/6702PXH I/OxAPIC Int... | 1     |            | 79DDE19254 |
| 8086:0326 | 103c:3208 | Intel      | 6700/6702PXH I/OxAPIC Int... | 1     |            | 2C877CF870 |
| 8086:0326 | 8086:3439 | Intel      | 6700/6702PXH I/OxAPIC Int... | 1     |            | 0F21E859FA |
| 8086:0327 |           | Intel      | 6700PXH I/OxAPIC Interrup... | 1     |            | 219383F559 |
| 8086:0327 | 103c:12f1 | Intel      | 6700PXH I/OxAPIC Interrup... | 1     |            | 79DDE19254 |
| 8086:0327 | 103c:3208 | Intel      | 6700PXH I/OxAPIC Interrup... | 1     |            | 2C877CF870 |
| 8086:0327 | 8086:3439 | Intel      | 6700PXH I/OxAPIC Interrup... | 1     |            | 0F21E859FA |
| 8086:0e2c | 1043:84f0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 90D8E62525 |
| 8086:0e2c | 1462:7737 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 725B24FE69 |
| 8086:0e2c | 15d9:0665 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | CEC82EF5D0 |
| 8086:0e2c | 15d9:070a | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | B4C8ABC585 |
| 8086:0e2c | 17aa:1026 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 5A6C7B0805 |
| 8086:0e2c | 1849:0e2c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 69907BBCE0 |
| 8086:0e2c | 8086:357e | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 018029FB72 |
| 8086:1461 | 1014:1461 | Intel      | 82870P2 P64H2 I/OxAPIC       | 1     |            | D6D105AE70 |
| 8086:2026 | 1590:18a9 | Intel      | Sky Lake-E IOAPIC            | 1     |            | 9E91D0ED19 |
| 8086:2026 | 1734:122f | Intel      | Sky Lake-E IOAPIC            | 1     |            | 14943339B4 |
| 8086:2026 | 17aa:1038 | Intel      | Sky Lake-E IOAPIC            | 1     |            | ED799888EB |
| 8086:2036 | 1590:18a9 | Intel      | Sky Lake-E IOxAPIC Config... | 1     |            | 9E91D0ED19 |
| 8086:2036 | 1734:122f | Intel      | Sky Lake-E IOxAPIC Config... | 1     |            | 14943339B4 |
| 8086:2036 | 17aa:1038 | Intel      | Sky Lake-E IOxAPIC Config... | 1     |            | ED799888EB |
| 8086:25ac |           | Intel      | 6300ESB I/O Advanced Prog... | 1     |            | 21330F2BD7 |
| 8086:2f2c | 1028:0618 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 76B60C0E5F |
| 8086:2f2c | 1028:0619 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | ADB52FAE26 |
| 8086:2f2c | 1462:7882 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 1E0208BF20 |
| 8086:2f2c | 1d49:0a00 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 817865DED6 |
| 8086:2f2c | 8086:35c5 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 08100751B7 |
| 8086:2f2c | 8086:35c9 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 5F9F099F36 |
| 8086:342d | 0086:0000 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | CBBE408AAC |
| 8086:342f | 0034:0027 | Intel      | 7500/5520/5500/X58 Truste... | 1     |            | C7E9D74C3D |
| 8086:342f | 0086:0000 | Intel      | 7500/5520/5500/X58 Truste... | 1     |            | CBBE408AAC |
| 8086:3c2c | 1028:0496 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | 2597040B1B |
| 8086:3c2c | 1734:11b5 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | 077A9B9D45 |
| 8086:3c2c | 17aa:1027 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | 9506CD65EE |
| 8086:3c2c | 8086:4953 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | BD6FF7AA0F |
| 8086:6f2c | 1028:0617 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | 019BFC3983 |
| 8086:6f2c | 1028:064c | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | 961BF8073A |
| 8086:6f2c | 15d9:0834 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | EEE6327556 |
| 8086:6f2c | 15d9:0835 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | 7479576DA8 |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:16bc | 1025:0647 | Broadco... | BCM57765/57785 SDXC/MMC C... | 212   | sdhci_pci  | E67DFC255A |
| 197b:2381 | 1043:1a07 | JMicron... | Standard SD Host Controller  | 116   | sdhci_pci  | F47F34752E |
| 14e4:16bc | 1025:0504 | Broadco... | BCM57765/57785 SDXC/MMC C... | 86    | sdhci_pci  | 8579BA1B16 |
| 1180:0822 | 17aa:20c8 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 65    | sdhci_pci  | A23E000798 |
| 104c:803c | 1025:011f | Texas I... | PCIxx12 SDA Standard Comp... | 64    | sdhci_pci  | 7387D70AD5 |
| 14e4:16bc | 14e4:0000 | Broadco... | BCM57765/57785 SDXC/MMC C... | 64    | sdhci_pci  | 16BDB52C40 |
| 1022:7806 | 1022:7806 | AMD        | FCH SD Flash Controller      | 55    | sdhci_pci  | 2C903F36D0 |
| 14e4:16bc | 1025:0775 | Broadco... | BCM57765/57785 SDXC/MMC C... | 50    | sdhci_pci  | AB33DE8D3B |
| 1022:7813 | 17aa:3801 | AMD        | FCH SD Flash Controller      | 44    | sdhci_pci  | 760B445B08 |
| 1180:e822 | 104d:9071 | Ricoh      | MMC/SD Host Controller       | 39    | sdhci_pci  | 3C5767E938 |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 38    | sdhci_pci  | 1579402536 |
| 8086:9d2d | 8086:9d2d | Intel      | Sunrise Point-LP Secure D... | 32    | sdhci_pci  | B6B40DE397 |
| 1524:0550 | 1025:0090 | ENE Tec... | ENE PCI Secure Digital Ca... | 31    | sdhci_pci  | 719BE91D02 |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 31    | sdhci_pci  | 1579402536 |
| 1180:0822 | 1028:0233 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 30    | sdhci_pci  | 1F49A84F1F |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 30    | sdhci_pci  | 1579402536 |
| 10ec:5209 | 10ec:5209 | Realtek... | RTS5209 PCI Express Card ... | 29    | sdhci_pci  | DE168F8DCC |
| 1217:8221 | 1028:0493 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 28    | sdhci_pci  | CA6EFEBBD7 |
| 1180:0822 | 103c:30cc | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 27    | sdhci_pci  | 9EDE738BFC |
| 197b:2391 | 103c:17f6 | JMicron... | Standard SD Host Controller  | 27    | sdhci_pci  | AB69AA73CD |
| 104c:803c | 1179:ff00 | Texas I... | PCIxx12 SDA Standard Comp... | 23    | sdhci_pci  | 92ACB586D2 |
| 1524:0550 | 1025:009f | ENE Tec... | ENE PCI Secure Digital Ca... | 23    | sdhci_pci  | A28F7B2623 |
| 197b:2391 | 103c:167c | JMicron... | Standard SD Host Controller  | 23    | sdhci_pci  | 15E5D2BB9D |
| 1180:0822 | 1025:011e | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 21    | sdhci_pci  | ED83D72FBE |
| 1180:0822 | 1028:01f5 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 21    | sdhci_pci  | BFDE36E2F4 |
| 1180:0822 | 1028:022f | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 21    | sdhci_pci  | 55CD396670 |
| 1969:3010 | 1025:076b | Qualcom... | Secure Digital Card Reader   | 21    | sdhci_pci  | 6479F7F12B |
| 1180:0843 | 1028:0233 | Ricoh      | R5C843 MMC Host Controller   | 20    | sdhci_pci  | 1F49A84F1F |
| 1180:e822 | 1028:040a | Ricoh      | MMC/SD Host Controller       | 20    | sdhci_pci  | D588CD38C2 |
| 10ec:5209 | 103c:3388 | Realtek... | RTS5209 PCI Express Card ... | 19    | sdhci_pci  | EDC722485A |
| 1022:7806 | 1043:107c | AMD        | FCH SD Flash Controller      | 18    | sdhci_pci  | 6A47875DF8 |
| 1022:7813 | 1025:104b | AMD        | FCH SD Flash Controller      | 18    | sdhci_pci  | C081ADAAE3 |
| 1022:7813 | 17aa:3800 | AMD        | FCH SD Flash Controller      | 18    | sdhci_pci  | 00C22F3924 |
| 1180:0822 | 1043:1627 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 18    | sdhci_pci  | 7E94795F51 |
| 1217:7120 | 1025:013c | O2 Micro   | Integrated MMC/SD Controller | 18    | sdhci_pci  | 77E3B20E26 |
| 1217:7120 | 1179:ff50 | O2 Micro   | Integrated MMC/SD Controller | 18    | sdhci_pci  | B6017B2145 |
| 104c:803c | 1179:ff02 | Texas I... | PCIxx12 SDA Standard Comp... | 17    | sdhci_pci  | 3CE1664885 |
| 1180:0822 | 1025:0121 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 17    | sdhci_pci  | CFBA4082BB |
| 1180:0822 | 1025:0126 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 17    | sdhci_pci  | F7695ADD11 |
| 197b:2391 | 103c:179b | JMicron... | Standard SD Host Controller  | 17    | sdhci_pci  | ED317797F0 |
| 197b:2391 | 17aa:3976 | JMicron... | Standard SD Host Controller  | 17    | sdhci_pci  | DF1A1447C6 |
| 1180:0822 | 1043:1317 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 16    | sdhci_pci  | B304C61746 |
| 1180:0822 | 10f7:8338 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 16    | sdhci_pci  | FDCC1DFB81 |
| 1217:8520 | 17aa:3800 | O2 Micro   | SD/MMC Card Reader Contro... | 16    | sdhci_pci  | 9A9BC31C3D |
| 8086:9d2b | 8086:7270 | Intel      | Skylake-U/Y SCC: eMMC        | 16    | sdhci_pci  | 44204F310C |
| 8086:9d2d | 8086:7270 | Intel      | Sunrise Point-LP Secure D... | 16    | sdhci_pci  | 44204F310C |
| 104c:803c | 1179:ff10 | Texas I... | PCIxx12 SDA Standard Comp... | 15    | sdhci_pci  | 4FFE571137 |
| 1180:0822 | 103c:7008 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 15    | sdhci_pci  | AB17752168 |
| 1180:0822 | 1043:1877 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 15    | sdhci_pci  | CB27B32040 |
| 1180:0822 | 1043:1897 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 15    | sdhci_pci  | 96E310C22E |
| 14e4:16bc | 1025:0605 | Broadco... | BCM57765/57785 SDXC/MMC C... | 15    | sdhci_pci  | 4BBB490EBC |
| 197b:2381 | 103c:3628 | JMicron... | Standard SD Host Controller  | 15    | sdhci_pci  | E09686C315 |
| 197b:2381 | 17aa:212d | JMicron... | Standard SD Host Controller  | 15    | sdhci_pci  | 2AFD83B0D3 |
| 197b:2391 | 103c:161c | JMicron... | Standard SD Host Controller  | 15    | sdhci_pci  | 6AE9888758 |
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 15    | sdhci_pci  | 56A7BF3D18 |
| 1022:7813 | 103c:8137 | AMD        | FCH SD Flash Controller      | 13    | sdhci_pci  | 08C91B5D48 |
| 1180:0822 | 1043:14e7 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 13    | sdhci_pci  | D9970BDA58 |
| 1217:8221 | 1028:0534 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 13    | sdhci_pci  | 8C26DF88EE |
| 197b:2391 | 103c:17ab | JMicron... | Standard SD Host Controller  | 13    | sdhci_pci  | 3B64B265CF |
| 1180:0822 | 1028:01bd | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 12    | sdhci_pci  | 586A6A9F8A |
| 1180:0822 | 103c:30cf | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 12    | sdhci_pci  | 084F7E13DA |
| 1180:0822 | 1043:1767 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 12    | sdhci_pci  | 4137AC8F54 |
| 1180:0822 | 104d:9035 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 12    | sdhci_pci  | A3C4D07088 |
| 1180:0822 | 1179:ff1c | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 12    | sdhci_pci  | 588EAD6870 |
| 1180:e822 | 1028:040b | Ricoh      | MMC/SD Host Controller       | 12    | sdhci_pci  | 80B359DC57 |
| 1217:8221 | 1028:053c | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 12    | sdhci_pci  | 6497328EF1 |
| 197b:2381 | 103c:3603 | JMicron... | Standard SD Host Controller  | 12    | sdhci_pci  | 9CE29D0583 |
| 8086:9d2b | 1025:1085 | Intel      | Skylake-U/Y SCC: eMMC        | 12    | sdhci_pci  | 88BCBB545E |
| 1180:0822 | 1028:024f | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 11    | sdhci_pci  | 5A8B3F34A3 |
| 1180:0822 | 1028:029a | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 11    | sdhci_pci  | 394D903321 |
| 1180:0822 | 103c:7007 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 11    | sdhci_pci  | FE89EA62D2 |
| 1180:0822 | 1043:1517 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 11    | sdhci_pci  | FAECBEFA9B |
| 1180:0822 | 1043:1777 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 11    | sdhci_pci  | 9B7F075594 |
| 1217:8520 | 1028:05be | O2 Micro   | SD/MMC Card Reader Contro... | 11    | sdhci_pci  | 40C9255DE6 |
| 14e4:16bc | 1025:0742 | Broadco... | BCM57765/57785 SDXC/MMC C... | 11    | sdhci_pci  | D3813AFBF5 |
| 1022:7813 | 1043:141d | AMD        | FCH SD Flash Controller      | 10    | sdhci_pci  | A7F7276E3D |
| 104c:803c | 1025:0107 | Texas I... | PCIxx12 SDA Standard Comp... | 10    | sdhci_pci  | D14CE30BB6 |
| 1217:8320 | 1028:04a3 | O2 Micro   | OZ600RJ1/OZ900RJ1 SD/MMC ... | 10    | sdhci_pci  | 19E1CA5871 |
| 1217:8321 | 1028:0494 | O2 Micro   | OZ600RJ0/OZ900RJ0/OZ600RJ... | 10    | sdhci_pci  | 31F0876A89 |
| 1217:8621 | 17aa:5068 | O2 Micro   | SD/MMC Card Reader Contro... | 10    | sdhci_pci  | CE2A6FB934 |
| 1524:0750 | 1025:012e | ENE Tec... | ENE PCI SmartMedia / xD C... | 10    | sdhci_pci  | 16BE592F4F |
| 197b:2381 | 103c:3659 | JMicron... | Standard SD Host Controller  | 10    | sdhci_pci  | AFAAE2AA59 |
| 197b:2391 | 103c:162b | JMicron... | Standard SD Host Controller  | 10    | sdhci_pci  | FAF97CF550 |
| 1022:7806 | 1043:14b7 | AMD        | FCH SD Flash Controller      | 9     | sdhci_pci  | 6C12E2EE00 |
| 1022:7813 | 103c:80cc | AMD        | FCH SD Flash Controller      | 9     | sdhci_pci  | 2EC22FA87A |
| 104c:803c | 1179:0001 | Texas I... | PCIxx12 SDA Standard Comp... | 9     | sdhci_pci  | 3E0ED41BC7 |
| 1180:0822 | 103c:30bb | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 9     | sdhci_pci  | FB7F51216E |
| 1217:8221 | 1028:0532 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 9     | sdhci_pci  | 963D3EBFE9 |
| 1217:8221 | 1028:0535 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 9     | sdhci_pci  | 95A631AAE1 |
| 1217:8520 | 1028:05ca | O2 Micro   | SD/MMC Card Reader Contro... | 9     | sdhci_pci  | CA9C198099 |
| 1217:8520 | 1028:05de | O2 Micro   | SD/MMC Card Reader Contro... | 9     | sdhci_pci  | F40C3D18FB |
| 197b:2381 | 103c:30f4 | JMicron... | Standard SD Host Controller  | 9     | sdhci_pci  | DDA054B15D |
| 8086:2296 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 9     | sdhci_pci  | 27537B5C01 |
| 8086:31d0 | 8086:7270 | Intel      | SD Host Controller           | 9     | sdhci_pci  | 56A7BF3D18 |
| 1022:7813 | 1025:0865 | AMD        | FCH SD Flash Controller      | 8     | sdhci_pci  | B8D1E63435 |
| 1022:7813 | 1025:108a | AMD        | FCH SD Flash Controller      | 8     | sdhci_pci  | 15AB2F9B58 |
| 1022:7813 | 103c:81f5 | AMD        | FCH SD Flash Controller      | 8     | sdhci_pci  | 2043A9B3C9 |
| 1022:7813 | 1043:148d | AMD        | FCH SD Flash Controller      | 8     | sdhci_pci  | 7C8E8CFB76 |
| 1180:0822 | 1028:022a | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 8     | sdhci_pci  | 77649E9A5A |
| 1180:0822 | 1028:023a | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 8     | sdhci_pci  | 2B5F0594D3 |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a324 | 8086:7270 | Intel      | Cannon Lake PCH SPI Contr... | 54    |            | 0B02A9E571 |
| 8086:a324 | 1043:8694 | Intel      | Cannon Lake PCH SPI Contr... | 32    |            | 68BABB69CB |
| 8086:a324 | 1849:a324 | Intel      | Cannon Lake PCH SPI Contr... | 20    |            | 39C0FBE126 |
| 8086:a1a4 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    |            | 4391DFF8D2 |
| 8086:9da4 | 8086:7270 | Intel      | Cannon Point-LP SPI Contr... | 13    |            | EA12327BDD |
| 8086:a324 | 1028:087c | Intel      | Cannon Lake PCH SPI Contr... | 12    |            | 7A9639F003 |
| 8086:a368 | 1028:087c | Intel      | Cannon Lake PCH Serial IO... | 12    | intel_l... | 7A9639F003 |
| 8086:a369 | 1028:087c | Intel      | Cannon Lake PCH Serial IO... | 12    | intel_l... | 7A9639F003 |
| 8086:a32a | 1043:1e40 | Intel      | 300 Series Chipset Device    | 11    | intel_l... | BBAF5C143F |
| 8086:a324 | 1025:1264 | Intel      | Cannon Lake PCH SPI Contr... | 10    |            | F3941C8871 |
| 8086:a368 | 1025:1264 | Intel      | Cannon Lake PCH Serial IO... | 10    | intel_lpss | F3941C8871 |
| 8086:a369 | 1025:1264 | Intel      | Cannon Lake PCH Serial IO... | 10    | intel_lpss | F3941C8871 |
| 8086:22c6 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 9     | i2c_des... | 27537B5C01 |
| 8086:22c7 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 9     | i2c_des... | 27537B5C01 |
| 8086:a324 | 1028:087d | Intel      | Cannon Lake PCH SPI Contr... | 9     |            | 75F82151FF |
| 8086:a368 | 1028:087d | Intel      | Cannon Lake PCH Serial IO... | 9     | intel_l... | 75F82151FF |
| 8086:a369 | 1028:087d | Intel      | Cannon Lake PCH Serial IO... | 9     | intel_l... | 75F82151FF |
| 8086:5ac8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 8     | pwm_lps... | 6F498D9D7D |
| 8086:9ce6 | 8086:9ce6 | Intel      | Wildcat Point-LP Serial I... | 8     | spi_pxa... | 5515E7AA30 |
| 8086:9da4 | 1028:08af | Intel      | Cannon Point-LP SPI Contr... | 8     |            | D4A2D02674 |
| 8086:9da4 | 8086:2074 | Intel      | Cannon Point-LP SPI Contr... | 8     |            | 23DC7C0455 |
| 8086:9de8 | 1028:08af | Intel      | Cannon Point-LP Serial IO... | 8     | intel_l... | D4A2D02674 |
| 8086:9de9 | 1028:08af | Intel      | Cannon Point-LP Serial IO... | 8     | intel_l... | D4A2D02674 |
| 8086:a368 | 1043:1fc0 | Intel      | Cannon Lake PCH Serial IO... | 8     | intel_lpss | BBAF5C143F |
| 8086:a369 | 1043:1fc0 | Intel      | Cannon Lake PCH Serial IO... | 8     | intel_lpss | BBAF5C143F |
| 8086:9da4 | 103c:8532 | Intel      | Cannon Point-LP SPI Contr... | 6     |            | 3839DE934E |
| 8086:a324 | 1028:086f | Intel      | Cannon Lake PCH SPI Contr... | 6     |            | 9402076861 |
| 8086:a368 | 1028:086f | Intel      | Cannon Lake PCH Serial IO... | 6     | intel_l... | 9402076861 |
| 8086:a369 | 1028:086f | Intel      | Cannon Lake PCH Serial IO... | 6     | intel_l... | 9402076861 |
| 8086:9dc5 | 1043:14a1 | Intel      | 8th Gen Intel Core Proces... | 5     | intel_l... | EA12327BDD |
| 8086:9de8 | 1043:14a1 | Intel      | Cannon Point-LP Serial IO... | 5     | intel_l... | EA12327BDD |
| 8086:9de9 | 1043:14a1 | Intel      | Cannon Point-LP Serial IO... | 5     | intel_l... | EA12327BDD |
| 8086:9deb | 1043:14a1 | Intel      | 8th Gen Intel Core Proces... | 5     | intel_l... | EA12327BDD |
| 8086:a1a4 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 5     |            | 8E73F804F5 |
| 8086:a324 | 1025:1238 | Intel      | Cannon Lake PCH SPI Contr... | 5     |            | 1CC81789AC |
| 8086:a324 | 17aa:3802 | Intel      | Cannon Lake PCH SPI Contr... | 5     |            | 1613715663 |
| 8086:a368 | 1043:1fd0 | Intel      | Cannon Lake PCH Serial IO... | 5     | intel_l... | 578F1342D9 |
| 8086:a368 | 17aa:3807 | Intel      | Cannon Lake PCH Serial IO... | 5     | intel_l... | 1613715663 |
| 8086:a369 | 1043:1fd0 | Intel      | Cannon Lake PCH Serial IO... | 5     | intel_l... | 578F1342D9 |
| 8086:a369 | 17aa:3808 | Intel      | Cannon Lake PCH Serial IO... | 5     | intel_l... | 1613715663 |
| 8086:22c1 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 4     | i2c_des... | 8069B2A3BC |
| 8086:9c66 |           | Intel      | 8 Series SPI Controller #1   | 4     |            | 1D4DA7DE61 |
| 8086:9da4 | 1558:1323 | Intel      | Cannon Point-LP SPI Contr... | 4     |            | 5BBFA2B11F |
| 8086:9da4 | 1558:1325 | Intel      | Cannon Point-LP SPI Contr... | 4     |            | CCA2248332 |
| 8086:9daa | 1043:1501 | Intel      | 8th Gen Intel Core Proces... | 4     | intel_lpss | 702F54B654 |
| 8086:9dc5 | 1043:1501 | Intel      | 8th Gen Intel Core Proces... | 4     | intel_lpss | 702F54B654 |
| 8086:9de8 | 1043:1501 | Intel      | Cannon Point-LP Serial IO... | 4     | intel_lpss | 702F54B654 |
| 8086:9de8 | 1558:1325 | Intel      | Cannon Point-LP Serial IO... | 4     | intel_l... | CCA2248332 |
| 8086:9de9 | 1043:1501 | Intel      | Cannon Point-LP Serial IO... | 4     | intel_lpss | 702F54B654 |
| 8086:a324 | 1025:123c | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | AE6F83F149 |
| 8086:a324 | 1028:0825 | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | 75BA2F8829 |
| 8086:a324 | 1028:0831 | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | F72215BFC0 |
| 8086:a324 | 103c:84da | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | A8DE86DAD5 |
| 8086:a324 | 1462:1219 | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | A1D0BDB94B |
| 8086:a324 | 1462:7b33 | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | 45282961F0 |
| 8086:a324 | 1462:7b98 | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | 21F5EEF1AB |
| 8086:a324 | 1558:95e1 | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | EE61927487 |
| 8086:a324 | 17aa:2267 | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | AAB68A3B33 |
| 8086:a324 | 17aa:3801 | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | 8C5783C61B |
| 8086:a368 | 1028:0825 | Intel      | Cannon Lake PCH Serial IO... | 4     | intel_l... | 75BA2F8829 |
| 8086:a368 | 1028:0831 | Intel      | Cannon Lake PCH Serial IO... | 4     | intel_l... | F72215BFC0 |
| 8086:a368 | 17aa:2267 | Intel      | Cannon Lake PCH Serial IO... | 4     | intel_lpss | AAB68A3B33 |
| 8086:a368 | 17aa:3806 | Intel      | Cannon Lake PCH Serial IO... | 4     | intel_l... | 8C5783C61B |
| 8086:a369 | 1028:0825 | Intel      | Cannon Lake PCH Serial IO... | 4     | intel_l... | 75BA2F8829 |
| 8086:a369 | 1028:0831 | Intel      | Cannon Lake PCH Serial IO... | 4     | intel_l... | F72215BFC0 |
| 8086:a369 | 17aa:3809 | Intel      | Cannon Lake PCH Serial IO... | 4     | intel_l... | 8C5783C61B |
| 10de:1adb | 10de:1f08 | Nvidia     | TU106 USB Type-C Port Pol... | 3     |            | 35B960D525 |
| 8086:5ac8 |           | Intel      | Celeron N3350/Pentium N42... | 3     | pwm_lps... | C7F97B95C4 |
| 8086:9da4 | 17aa:5072 | Intel      | Cannon Point-LP SPI Contr... | 3     |            | DA7C2876D3 |
| 8086:a324 | 1028:0870 | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | 8ACE47254A |
| 8086:a324 | 1028:0877 | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | 8B270D4228 |
| 8086:a324 | 103c:8478 | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | AD2AA3B388 |
| 8086:a324 | 1043:10c1 | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | C1EDFCFA1C |
| 8086:a324 | 1558:8555 | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | 6ACA3CA73D |
| 8086:a324 | 1558:95e6 | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | 94C3F1BC72 |
| 8086:a324 | 17aa:36e7 | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | 1B85D8DB4E |
| 8086:a368 | 1028:0870 | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | 8ACE47254A |
| 8086:a368 | 1028:0877 | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | 8B270D4228 |
| 8086:a368 | 1043:10c1 | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | C1EDFCFA1C |
| 8086:a368 | 1558:95e6 | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | 94C3F1BC72 |
| 8086:a368 | 1849:a368 | Intel      | Cannon Lake PCH Serial IO... | 3     |            | B2FAC79AFD |
| 8086:a369 | 1028:0870 | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | 8ACE47254A |
| 8086:a369 | 1558:95e6 | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | 94C3F1BC72 |
| 8086:a369 | 1849:a369 | Intel      | Cannon Lake PCH Serial IO... | 3     |            | B2FAC79AFD |
| 10de:1ad7 | 19da:1503 | Nvidia     | TU102 UCSI Controller        | 2     | i2c_nvi... | F733910E90 |
| 10de:1ad7 | 3842:2382 | Nvidia     | TU102 UCSI Controller        | 2     |            | 52469C6D63 |
| 10de:1ad9 | 1462:3722 | Nvidia     | TU104 RTX 2080 USB Type-C... | 2     | nvidia_gpu | C3052C67D6 |
| 10de:1adb |           | Nvidia     | TU106 USB Type-C Port Pol... | 2     | nvidia_gpu | 3A4D90A1C3 |
| 10de:1adb | 1028:0000 | Nvidia     | TU106 USB Type-C Port Pol... | 2     | nvidia_gpu | AACC137FAA |
| 10de:1adb | 1043:8670 | Nvidia     | TU106 USB Type-C Port Pol... | 2     |            | AF6DA5211E |
| 10de:1adb | 10de:0000 | Nvidia     | TU106 USB Type-C Port Pol... | 2     |            | 087A8F3344 |
| 8086:0f41 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 2     | i2c_des... | 0994A3EEB3 |
| 8086:0f42 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 2     | i2c_des... | 0994A3EEB3 |
| 8086:9c61 | 1025:0a11 | Intel      | 8 Series I2C Controller #0   | 2     | i2c_des... | F304E3BA6B |
| 8086:9c62 | 1025:0a11 | Intel      | 8 Series I2C Controller #1   | 2     | i2c_des... | F304E3BA6B |
| 8086:9da4 | 1025:128d | Intel      | Cannon Point-LP SPI Contr... | 2     |            | 517CAD6069 |
| 8086:9da4 | 1028:089c | Intel      | Cannon Point-LP SPI Contr... | 2     |            | 1E82DEB58E |
| 8086:9da4 | 1028:08c9 | Intel      | Cannon Point-LP SPI Contr... | 2     |            | 6694F62BE3 |
| 8086:9da4 | 103c:8514 | Intel      | Cannon Point-LP SPI Contr... | 2     |            | 74DD313167 |
| 8086:9da4 | 19e5:3e09 | Intel      | Cannon Point-LP SPI Contr... | 2     |            | 87EF40FDD4 |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8c3d | 1458:1c3a | Intel      | 8 Series/C220 Series Chip... | 53    | serial     | 1E5997F695 |
| 8086:2a47 | 17aa:20ec | Intel      | Mobile 4 Series Chipset A... | 34    | serial     | FDAB3CF92F |
| 8086:3b67 | 17aa:2162 | Intel      | 5 Series/3400 Series Chip... | 32    | serial     | DA5E944C6C |
| 8086:1c3d | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 28    | serial     | FBF8462F41 |
| 8086:2e17 | 1028:027f | Intel      | 4 Series Chipset Serial K... | 20    | serial     | DFA7361038 |
| 8086:1e3d | 17aa:21f3 | Intel      | 7 Series/C210 Series Chip... | 19    | serial     | 4D1B987AAC |
| 8086:2e17 | 103c:3048 | Intel      | 4 Series Chipset Serial K... | 19    | serial     | B511052CC4 |
| 8086:29b7 | 1028:0211 | Intel      | 82Q35 Express Serial KT C... | 18    | serial     | 8C1C529BDC |
| 8086:1e3d | 17aa:21f6 | Intel      | 7 Series/C210 Series Chip... | 17    | serial     | C087621D89 |
| 8086:1e3d | 17aa:21fa | Intel      | 7 Series/C210 Series Chip... | 16    | serial     | C9FFBA0281 |
| 8086:3b67 | 8086:0036 | Intel      | 5 Series/3400 Series Chip... | 15    | serial     | 3462CD0CCD |
| 8086:2e17 | 1028:0420 | Intel      | 4 Series Chipset Serial K... | 14    | serial     | 0C9CE69911 |
| 8086:1e3d | 103c:179b | Intel      | 7 Series/C210 Series Chip... | 13    | serial     | 707703A569 |
| 8086:1e3d | 103c:339a | Intel      | 7 Series/C210 Series Chip... | 13    | serial     | 76F6D2AF22 |
| 8086:2e17 | 1734:114c | Intel      | 4 Series Chipset Serial K... | 13    | serial     | D6D2A25AA4 |
| 8086:1c3d | 103c:161c | Intel      | 6 Series/C200 Series Chip... | 12    | serial     | A00C60042E |
| 8086:1c3d | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 11    | serial     | 5C380FEC25 |
| 8086:1d3d | 103c:1589 | Intel      | C600/X79 series chipset K... | 11    | serial     | E14EB74EA5 |
| 8086:1e3d | 103c:3397 | Intel      | 7 Series/C210 Series Chip... | 11    | serial     | 195649904F |
| 8086:8c3d | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 11    | serial     | 475863E34D |
| 8086:9c3d | 17aa:220c | Intel      | 8 Series HECI KT             | 11    | serial     | 7637F3DE5F |
| 9710:9865 | a000:1000 | MosChip... | PCI 9865 Multi-I/O Contro... | 11    | parport_pc | 1D3FD80F42 |
| 8086:29b7 | 103c:2818 | Intel      | 82Q35 Express Serial KT C... | 10    | serial     | 6D02866E6C |
| 8086:2e17 | 103c:3034 | Intel      | 4 Series Chipset Serial K... | 10    | serial     | 5DC57BDE0C |
| 8086:3b67 | 103c:7007 | Intel      | 5 Series/3400 Series Chip... | 10    | serial     | FE89EA62D2 |
| 8086:1c3d | 103c:1497 | Intel      | 6 Series/C200 Series Chip... | 9     | serial     | 6227F00E30 |
| 8086:1c3d | 103c:162b | Intel      | 6 Series/C200 Series Chip... | 9     | serial     | FAF97CF550 |
| 8086:1e3d | 1458:1c3a | Intel      | 7 Series/C210 Series Chip... | 9     | serial     | BD8118E7B8 |
| 8086:29b7 | 1043:8295 | Intel      | 82Q35 Express Serial KT C... | 9     | serial     | 9057FD4986 |
| 8086:8c3d | 1028:05be | Intel      | 8 Series/C220 Series Chip... | 9     | serial     | 54B56F30BA |
| 8086:9c3d | 103c:198f | Intel      | 8 Series HECI KT             | 9     | serial     | DCE9CDAF8E |
| 8086:1c3d | 1028:047e | Intel      | 6 Series/C200 Series Chip... | 8     | serial     | 5C7816B17A |
| 8086:1c3d | 103c:1495 | Intel      | 6 Series/C200 Series Chip... | 8     | serial     | 3D9E77AE8A |
| 8086:1c3d | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 8     | serial     | 9306CAC54C |
| 8086:1c3d | 17aa:21d2 | Intel      | 6 Series/C200 Series Chip... | 8     | serial     | 97E66DDFC9 |
| 8086:1c3d | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 8     | serial     | E8A5C28644 |
| 8086:2e17 | 103c:3646 | Intel      | 4 Series Chipset Serial K... | 8     | serial     | 878673A8E4 |
| 8086:2e17 | 17aa:3048 | Intel      | 4 Series Chipset Serial K... | 8     | serial     | D44E51F592 |
| 8086:3b67 | 103c:7008 | Intel      | 5 Series/3400 Series Chip... | 8     | serial     | B5409A9615 |
| 8086:1c3d | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 7     | serial     | 8C536BE4D8 |
| 8086:1e3d | 1028:0577 | Intel      | 7 Series/C210 Series Chip... | 7     | serial     | 87DAB1466B |
| 8086:2e17 | 1028:0276 | Intel      | 4 Series Chipset Serial K... | 7     | serial     | 888F2F55D8 |
| 8086:3b67 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 7     | serial     | 8978395722 |
| 8086:3b67 | 103c:304b | Intel      | 5 Series/3400 Series Chip... | 7     | serial     | 16C4C7C1C0 |
| 8086:8c3d | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 7     | serial     | 24870345D1 |
| 8086:8c3d | 103c:18e7 | Intel      | 8 Series/C220 Series Chip... | 7     | serial     | D1235890E4 |
| 8086:9d3d | 103c:8079 | Intel      | Sunrise Point-LP Active M... | 7     | serial     | B8392B7335 |
| 4348:3253 | 4348:3253 | WCH.CN     | CH352 PCI Dual Serial Por... | 6     | serial     | A2F40FA9C0 |
| 8086:1c3d | 1028:0494 | Intel      | 6 Series/C200 Series Chip... | 6     | serial     | A217BF3485 |
| 8086:1c3d | 17aa:3077 | Intel      | 6 Series/C200 Series Chip... | 6     | serial     | CB4983BAF6 |
| 8086:3b67 | 1028:040b | Intel      | 5 Series/3400 Series Chip... | 6     | serial     | A9143BEECD |
| 8086:3b67 | 103c:172a | Intel      | 5 Series/3400 Series Chip... | 6     | serial     | E2C04796A0 |
| 8086:8c3d | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 6     | serial     | E412FEBD37 |
| 8086:8c3d | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 6     | serial     | 364B159B80 |
| 8086:8d3d | 1028:0617 | Intel      | C610/X99 series chipset K... | 6     | serial     | 945E8A152D |
| 9710:9912 | a000:1000 | MosChip... | PCIe 9912 Multi-I/O Contr... | 6     | serial     | 92F011CFCF |
| 8086:1c3d | 1028:04a3 | Intel      | 6 Series/C200 Series Chip... | 5     | serial     | 19E1CA5871 |
| 8086:1c3d | 103c:1494 | Intel      | 6 Series/C200 Series Chip... | 5     | serial     | A4BD1F1736 |
| 8086:1c3d | 103c:1618 | Intel      | 6 Series/C200 Series Chip... | 5     | serial     | 7D1AE28E6D |
| 8086:1d3d | 103c:158a | Intel      | C600/X79 series chipset K... | 5     | serial     | 2AB82BCF03 |
| 8086:1e3d | 1028:052c | Intel      | 7 Series/C210 Series Chip... | 5     | serial     | AEA3EEF94B |
| 8086:1e3d | 1028:0534 | Intel      | 7 Series/C210 Series Chip... | 5     | serial     | C8334C6A31 |
| 8086:1e3d | 17aa:21fb | Intel      | 7 Series/C210 Series Chip... | 5     | serial     | 2CA24B0A50 |
| 8086:1e3d | 17aa:3084 | Intel      | 7 Series/C210 Series Chip... | 5     | serial     | 435E64F300 |
| 8086:29b7 | 103c:2819 | Intel      | 82Q35 Express Serial KT C... | 5     | serial     | 073E07ECC0 |
| 8086:29b7 | 17aa:3038 | Intel      | 82Q35 Express Serial KT C... | 5     | serial     | C399CBB5F3 |
| 8086:2a07 | 17aa:20d4 | Intel      | Mobile PM965/GM965 KT Con... | 5     | serial     | 037CAC7A3D |
| 8086:2a47 | 103c:30e7 | Intel      | Mobile 4 Series Chipset A... | 5     | serial     | E05FE6B4AB |
| 8086:3b67 | 103c:304a | Intel      | 5 Series/3400 Series Chip... | 5     | serial     | 99C6F2F320 |
| 8086:3b67 | 10cf:152f | Intel      | 5 Series/3400 Series Chip... | 5     | serial     | 177FE65920 |
| 8086:3b67 | 8086:3b67 | Intel      | 5 Series/3400 Series Chip... | 5     | serial     | 046006226D |
| 1c00:2273 | 1c00:2273 |            | WCH PCI                      | 4     | serial     | 579DE6C00D |
| 8086:1c3d | 103c:1496 | Intel      | 6 Series/C200 Series Chip... | 4     | serial     | 4E44453A25 |
| 8086:1c3d | 1179:0001 | Intel      | 6 Series/C200 Series Chip... | 4     | serial     | 4398E73607 |
| 8086:1c3d | 8086:2008 | Intel      | 6 Series/C200 Series Chip... | 4     | serial     | A44CE70FF7 |
| 8086:1e3d | 103c:17a7 | Intel      | 7 Series/C210 Series Chip... | 4     | serial     | AE6CF1B3CA |
| 8086:1e3d | 103c:18df | Intel      | 7 Series/C210 Series Chip... | 4     | serial     | 4D5087B262 |
| 8086:1e3d | 103c:3396 | Intel      | 7 Series/C210 Series Chip... | 4     | serial     | 59CF4AC8D6 |
| 8086:1e3d | 10cf:16ed | Intel      | 7 Series/C210 Series Chip... | 4     | serial     | B7F6E1F635 |
| 8086:1e3d | 17aa:21f9 | Intel      | 7 Series/C210 Series Chip... | 4     | serial     | DF1FD87B87 |
| 8086:1e3d | 17aa:2203 | Intel      | 7 Series/C210 Series Chip... | 4     | serial     | D06826DB64 |
| 8086:29b7 | 1458:29b7 | Intel      | 82Q35 Express Serial KT C... | 4     | serial     | C9D4B4FC2F |
| 8086:29b7 | 1734:10fc | Intel      | 82Q35 Express Serial KT C... | 4     | serial     | FD6FD654DB |
| 8086:2a07 | 103c:30c5 | Intel      | Mobile PM965/GM965 KT Con... | 4     | serial     | AB3B50FF87 |
| 8086:2e17 | 103c:3035 | Intel      | 4 Series Chipset Serial K... | 4     | serial     | 68675FA918 |
| 8086:2e17 | 103c:3036 | Intel      | 4 Series Chipset Serial K... | 4     | serial     | 628F536295 |
| 8086:2e17 | 17aa:3047 | Intel      | 4 Series Chipset Serial K... | 4     | serial     | B1781FED7E |
| 8086:3b67 | 103c:1520 | Intel      | 5 Series/3400 Series Chip... | 4     | serial     | 5BC72880EA |
| 8086:3b67 | 103c:172b | Intel      | 5 Series/3400 Series Chip... | 4     | serial     | 35E3CAB7FD |
| 8086:8c3d | 10cf:17e0 | Intel      | 8 Series/C220 Series Chip... | 4     | serial     | 491E66B3D8 |
| 8086:9c3d | 1028:05ca | Intel      | 8 Series HECI KT             | 4     | serial     | C0C75EF0DF |
| 8086:9c3d | 1028:05cb | Intel      | 8 Series HECI KT             | 4     | serial     | 613D54A9CE |
| 8086:9c3d | 103c:1991 | Intel      | 8 Series HECI KT             | 4     | serial     | 475A1011AB |
| 8086:9c3d | 17aa:2218 | Intel      | 8 Series HECI KT             | 4     | serial     | B19667D81D |
| 8086:9d3d | 1028:06dc | Intel      | Sunrise Point-LP Active M... | 4     | serial     | 90E9F8DFAD |
| 8086:a13d | 17aa:222e | Intel      | 100 Series/C230 Series Ch... | 4     | serial     | 6F5CF8EFB9 |
| 9710:9835 | 1000:0002 | MosChip... | PCI 9835 Multi-I/O Contro... | 4     | parport... | E04FF14502 |
| 9710:9922 | a000:1000 | MosChip... | MCS9922 PCIe Multi-I/O Co... | 4     | serial     | C59E0D2B42 |
| 10ec:816a | 1458:e000 | Realtek... | Virtual COM1                 | 3     |            | E528F92A7A |
| 10ec:816a | 17aa:3089 | Realtek... | Virtual COM1                 | 3     |            | D9A1939AB2 |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 97    | process... | 6053E60588 |
| 8086:3b32 | 17aa:2190 | Intel      | 5 Series/3400 Series Chip... | 67    | intel_ips  | DA5E944C6C |
| 8086:9d27 | 1043:1d2d | Intel      | Sunrise Point-LP Serial I... | 59    | intel_lpss | B6B40DE397 |
| 8086:3b32 | 17aa:38c0 | Intel      | 5 Series/3400 Series Chip... | 55    | intel_ips  | 62697BF35B |
| 8086:9d29 | 1043:1d2d | Intel      | Sunrise Point-LP Serial I... | 47    | intel_lpss | B6B40DE397 |
| 8086:2932 | 17aa:3a1f | Intel      | 82801I (ICH9 Family) Ther... | 46    |            | 601D53F9EB |
| 8086:22dc | 7270:8086 | Intel      | Atom/Celeron/Pentium Proc... | 45    | process... | 4414412FCB |
| 8086:3b32 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 43    | intel_ips  | D023F50697 |
| 8086:0a03 | 8086:2010 | Intel      | Haswell-ULT Thermal Subsy... | 41    | process... | 8D5390FEAE |
| 8086:3b32 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 40    | intel_ips  | DA7D4E2098 |
| 8086:5a8c |           | Intel      | Dynamic Platform and Ther... | 39    | process... | 1579402536 |
| 8086:9d31 | 8086:7270 | Intel      | Sunrise Point-LP Thermal ... | 38    | intel_p... | 44204F310C |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 37    | intel_l... | 1579402536 |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 37    | intel_l... | 1579402536 |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 37    | intel_l... | 1579402536 |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 37    | intel_l... | 1579402536 |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 37    | intel_l... | 1579402536 |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 37    | intel_l... | 1579402536 |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 37    | intel_l... | 1579402536 |
| 8086:a131 | 1458:8888 | Intel      | 100 Series/C230 Series Ch... | 37    | intel_p... | 85B34D0336 |
| 8086:a131 | 1849:a131 | Intel      | 100 Series/C230 Series Ch... | 37    | intel_p... | BCB3EF58AB |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 36    | intel_l... | 1579402536 |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 36    | intel_l... | 1579402536 |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 36    | intel_l... | 1579402536 |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 36    | intel_l... | 1579402536 |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 35    | intel_l... | 1579402536 |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 35    | intel_l... | 1579402536 |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 35    | intel_l... | 1579402536 |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 34    | intel_l... | 1579402536 |
| 8086:5a8c | 1043:16a0 | Intel      | Dynamic Platform and Ther... | 32    | proc_th... | 0FAD7AC4EB |
| 8086:5aac | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 32    | intel_lpss | 0FAD7AC4EB |
| 8086:5ab4 | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 32    | intel_lpss | 0FAD7AC4EB |
| 8086:a379 | 1458:8888 | Intel      | Cannon Lake PCH Thermal C... | 31    | intel_p... | 0B02A9E571 |
| 8086:0a03 | 1043:131d | Intel      | Haswell-ULT Thermal Subsy... | 30    | process... | FDD61F096B |
| 8086:9c24 | 1043:131d | Intel      | 8 Series Thermal             | 28    | intel_p... | 761A86BDC8 |
| 8086:9d27 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 27    | intel_l... | 44204F310C |
| 8086:9d60 | 1025:1193 | Intel      | Sunrise Point-LP Serial I... | 26    | intel_lpss | 141D7917FF |
| 8086:9d61 | 1025:1193 | Intel      | Sunrise Point-LP Serial I... | 26    | intel_lpss | 141D7917FF |
| 8086:0153 | 1043:1587 | Intel      | 3rd Gen Core Processor Th... | 25    |            | 469E04E0D5 |
| 8086:3b32 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 24    | intel_ips  | 3C5767E938 |
| 8086:9c24 | 1043:16cd | Intel      | 8 Series Thermal             | 24    | intel_p... | FDD61F096B |
| 8086:9d60 | 1025:1085 | Intel      | Sunrise Point-LP Serial I... | 23    | intel_l... | AE1CE65D11 |
| 8086:9d60 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 23    | intel_l... | 44204F310C |
| 8086:9d61 | 1025:1085 | Intel      | Sunrise Point-LP Serial I... | 23    | intel_l... | AE1CE65D11 |
| 8086:a2b1 | 1849:a2b1 | Intel      | 200 Series PCH Thermal Su... | 23    |            | CACD7C9489 |
| 8086:0a03 | 1043:16cd | Intel      | Haswell-ULT Thermal Subsy... | 22    | process... | 2A224752BA |
| 8086:22dc | 1043:10c0 | Intel      | Atom/Celeron/Pentium Proc... | 22    | process... | F8FDA4EFC3 |
| 8086:9d61 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 22    | intel_l... | 44204F310C |
| 8086:3b32 | 144d:c581 | Intel      | 5 Series/3400 Series Chip... | 21    | intel_ips  | 4B260556B7 |
| 8086:9d31 | 1025:115f | Intel      | Sunrise Point-LP Thermal ... | 21    | intel_p... | E4B342382F |
| 8086:9d60 | 1025:115f | Intel      | Sunrise Point-LP Serial I... | 21    | intel_l... | E4B342382F |
| 8086:9d62 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 21    | intel_l... | 44204F310C |
| 8086:a131 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 21    | intel_p... | BD6DC70775 |
| 8086:3b32 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 20    | intel_ips  | D588CD38C2 |
| 8086:3b32 | 10cf:1526 | Intel      | 5 Series/3400 Series Chip... | 20    | intel_ips  | EEFC712947 |
| 8086:9d31 | 17aa:380e | Intel      | Sunrise Point-LP Thermal ... | 20    | intel_p... | 005771EDFD |
| 8086:a379 | 1849:a379 | Intel      | Cannon Lake PCH Thermal C... | 20    | intel_p... | 39C0FBE126 |
| 8086:1903 | 103c:832a | Intel      | Xeon E3-1200 v5/E3-1500 v... | 18    | process... | 8B699D7E6C |
| 8086:1903 | 8086:1903 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 18    | process... | DE5FB421D9 |
| 8086:1903 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 18    | process... | 3E70A8DFF1 |
| 8086:9d31 | 103c:832a | Intel      | Sunrise Point-LP Thermal ... | 18    | intel_p... | 8B699D7E6C |
| 8086:9d31 | 8086:9d31 | Intel      | Sunrise Point-LP Thermal ... | 18    | intel_p... | 6813C9B2D3 |
| 8086:9d63 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 18    | intel_l... | 329795002B |
| 8086:1603 | 1043:10d0 | Intel      | Broadwell-U Processor The... | 17    | process... | B507AA7D6F |
| 8086:1903 | 1043:1a00 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 17    | proc_th... | BEB89C26D9 |
| 8086:9ca4 | 1043:10d0 | Intel      | Wildcat Point-LP Thermal ... | 17    | intel_p... | B507AA7D6F |
| 8086:9d27 | 1043:1a00 | Intel      | Sunrise Point-LP Serial I... | 17    | intel_lpss | BEB89C26D9 |
| 8086:9d29 | 1043:1a00 | Intel      | Sunrise Point-LP Serial I... | 17    | intel_lpss | BEB89C26D9 |
| 8086:9d31 | 1043:1a00 | Intel      | Sunrise Point-LP Thermal ... | 17    | intel_p... | BEB89C26D9 |
| 8086:9d31 | 17aa:3861 | Intel      | Sunrise Point-LP Thermal ... | 17    | intel_p... | 240FE2C985 |
| 8086:9d60 | 1043:1a00 | Intel      | Sunrise Point-LP Serial I... | 17    | intel_lpss | BEB89C26D9 |
| 8086:9d60 | 17aa:3865 | Intel      | Sunrise Point-LP Serial I... | 17    | intel_l... | 240FE2C985 |
| 8086:9d61 | 1043:1a00 | Intel      | Sunrise Point-LP Serial I... | 17    | intel_lpss | BEB89C26D9 |
| 8086:318c | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 16    | proc_th... | AAAC90F58C |
| 8086:31b4 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 16    | intel_lpss | AAAC90F58C |
| 8086:31b6 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 16    | intel_lpss | AAAC90F58C |
| 8086:31bc | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 16    | intel_lpss | AAAC90F58C |
| 8086:31be | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 16    | intel_lpss | AAAC90F58C |
| 8086:31c0 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 16    | intel_lpss | AAAC90F58C |
| 8086:31ee | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 16    | intel_lpss | AAAC90F58C |
| 8086:3b32 | 1025:0601 | Intel      | 5 Series/3400 Series Chip... | 16    | intel_ips  | 1ABB956626 |
| 8086:3b32 | 1043:1f27 | Intel      | 5 Series/3400 Series Chip... | 16    | intel_ips  | A6D13752DA |
| 8086:a131 | 1462:7a15 | Intel      | 100 Series/C230 Series Ch... | 16    | intel_p... | 7C7D8F8CB6 |
| 8086:a1b1 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    |            | 4391DFF8D2 |
| 8086:1603 | 1043:1a6d | Intel      | Broadwell-U Processor The... | 15    | process... | 5919CA05FE |
| 8086:2932 | 103c:3628 | Intel      | 82801I (ICH9 Family) Ther... | 15    |            | E09686C315 |
| 8086:3b32 | 103c:7008 | Intel      | 5 Series/3400 Series Chip... | 15    | intel_ips  | AB17752168 |
| 8086:9ca4 | 1043:1a6d | Intel      | Wildcat Point-LP Thermal ... | 15    | intel_p... | 5919CA05FE |
| 8086:9d31 | 103c:8079 | Intel      | Sunrise Point-LP Thermal ... | 15    | intel_p... | B8392B7335 |
| 8086:9d60 | 103c:8079 | Intel      | Sunrise Point-LP Serial I... | 15    | intel_l... | B8392B7335 |
| 8086:9d61 | 8086:9d61 | Intel      | Sunrise Point-LP Serial I... | 15    | intel_l... | 6813C9B2D3 |
| 8086:1903 | 1028:07e6 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 14    | process... | 5D2CB1E1B0 |
| 8086:3b32 | 144d:c06a | Intel      | 5 Series/3400 Series Chip... | 14    | intel_ips  | 86987CF1ED |
| 8086:3b32 | 8086:0000 | Intel      | 5 Series/3400 Series Chip... | 14    | intel_ips  | 2458B122E5 |
| 8086:9d31 | 1028:07e6 | Intel      | Sunrise Point-LP Thermal ... | 14    | intel_p... | 5D2CB1E1B0 |
| 8086:9d60 | 1028:07e6 | Intel      | Sunrise Point-LP Serial I... | 14    | intel_l... | 5D2CB1E1B0 |
| 8086:9d61 | 1028:07e6 | Intel      | Sunrise Point-LP Serial I... | 14    | intel_l... | 5D2CB1E1B0 |
| 8086:1903 | 1028:07be | Intel      | Xeon E3-1200 v5/E3-1500 v... | 13    | process... | CB9F8EC46D |
| 8086:2932 | 103c:1605 | Intel      | 82801I (ICH9 Family) Ther... | 13    |            | D3AFE1DB4A |
| 8086:5a8c | 1043:1de0 | Intel      | Dynamic Platform and Ther... | 13    | proc_th... | 8633F4E071 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:4385 | 1002:4385 | AMD        | SBx00 SMBus Controller       | 480   | i2c_pii... | 394C81B911 |
| 8086:1c22 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 469   | i2c_i801   | 66A5EA0BE5 |
| 8086:27da | 1043:8179 | Intel      | NM10/ICH7 Family SMBus Co... | 407   | i2c_i801   | FAC5E9FEFA |
| 8086:27da | 1458:5001 | Intel      | NM10/ICH7 Family SMBus Co... | 405   | i2c_i801   | DD0FCDE6C7 |
| 1002:4385 |           | AMD        | SBx00 SMBus Controller       | 359   | i2c_pii... | 33F663A020 |
| 8086:1e22 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 351   | i2c_i801   | 570B707FFB |
| 1002:4385 | 1043:8389 | AMD        | SBx00 SMBus Controller       | 339   | i2c_pii... | D569843A2D |
| 1002:4385 | 1458:4385 | AMD        | SBx00 SMBus Controller       | 326   | i2c_pii... | 8EAEF3C906 |
| 8086:8c22 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 316   | i2c_i801   | F6CCF2BBA6 |
| 8086:1c22 | 1458:5001 | Intel      | 6 Series/C200 Series Chip... | 290   | i2c_i801   | E4C2A9F4EB |
| 8086:3a30 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) SM... | 268   | i2c_i801   | B481805845 |
| 8086:1e22 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 262   | i2c_i801   | 891002E8F2 |
| 8086:27da | 1849:27da | Intel      | NM10/ICH7 Family SMBus Co... | 249   | i2c_i801   | 5F6E1A3B61 |
| 8086:1e22 | 1458:5001 | Intel      | 7 Series/C216 Chipset Fam... | 245   | i2c_i801   | 8C4047657D |
| 1002:4385 | 1849:4385 | AMD        | SBx00 SMBus Controller       | 222   | i2c_pii... | 85F1B83B30 |
| 8086:2930 | 1043:8277 | Intel      | 82801I (ICH9 Family) SMBu... | 211   | i2c_i801   | 29B7777E42 |
| 8086:a123 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 198   | i2c_i801   | 99614383EB |
| 10de:03eb | 1849:03eb | Nvidia     | MCP61 SMBus                  | 194   | i2c_nfo... | 816FE60D2D |
| 8086:8c22 | 1458:5001 | Intel      | 8 Series/C220 Series Chip... | 184   | i2c_i801   | DD4DA32934 |
| 8086:1c22 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 164   | i2c_i801   | A7618091FB |
| 1022:780b | 1022:780b | AMD        | FCH SMBus Controller         | 146   | i2c_piix4  | 9137FB3859 |
| 8086:3a30 | 1458:5001 | Intel      | 82801JI (ICH10 Family) SM... | 142   | i2c_i801   | F655F180AC |
| 1022:790b | 1043:8747 | AMD        | FCH SMBus Controller         | 123   | i2c_piix4  | 4A2455EAE6 |
| 8086:27da | 1043:83ad | Intel      | NM10/ICH7 Family SMBus Co... | 120   | i2c_i801   | 6A0513EC8D |
| 8086:3b30 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 118   | i2c_i801   | 05DC50AA11 |
| 8086:1c22 | 1849:1c22 | Intel      | 6 Series/C200 Series Chip... | 117   | i2c_i801   | BDA40E6195 |
| 1022:780b | 1849:780b | AMD        | FCH SMBus Controller         | 116   | i2c_piix4  | 54FB4AE774 |
| 8086:2930 | 1458:5001 | Intel      | 82801I (ICH9 Family) SMBu... | 107   | i2c_i801   | 54231260FF |
| 10de:03eb | 1458:0c11 | Nvidia     | MCP61 SMBus                  | 105   | i2c_nfo... | BBF6B6F632 |
| 8086:a123 | 1458:5001 | Intel      | 100 Series/C230 Series Ch... | 103   | i2c_i801   | 0BF4CAF942 |
| 8086:9c22 | 17aa:3978 | Intel      | 8 Series SMBus Controller    | 89    | i2c_i801   | AFD92BF265 |
| 1022:790b | 1458:5001 | AMD        | FCH SMBus Controller         | 88    | i2c_piix4  | 0438613602 |
| 8086:3b30 | 1458:5001 | Intel      | 5 Series/3400 Series Chip... | 85    | i2c_i801   | B39AC90CA0 |
| 8086:1c22 | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 80    | i2c_i801   | 6B25B8982D |
| 8086:1e22 | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 80    | i2c_i801   | F28D18F3E9 |
| 8086:8c22 | 1849:8c22 | Intel      | 8 Series/C220 Series Chip... | 79    | i2c_i801   | 8AE6B6F651 |
| 8086:8ca2 | 1043:8534 | Intel      | 9 Series Chipset Family S... | 76    | i2c_i801   | EFA3992D9A |
| 8086:3b30 | 17aa:2167 | Intel      | 5 Series/3400 Series Chip... | 75    | i2c_i801   | DA5E944C6C |
| 8086:3b30 | 17aa:38bf | Intel      | 5 Series/3400 Series Chip... | 75    | i2c_i801   | 62697BF35B |
| 8086:2930 | 17aa:20f9 | Intel      | 82801I (ICH9 Family) SMBu... | 73    | i2c_i801   | FDAB3CF92F |
| 8086:2930 | 17aa:3a1d | Intel      | 82801I (ICH9 Family) SMBu... | 73    | i2c_i801   | 601D53F9EB |
| 10de:03eb | 1043:8234 | Nvidia     | MCP61 SMBus                  | 72    | i2c_nfo... | 2A30939325 |
| 8086:8c22 | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 72    | i2c_i801   | 7BBCD6F17D |
| 8086:8c22 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 72    | i2c_i801   | 262BB6B100 |
| 8086:1e22 | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 69    | i2c_i801   | CE3DDF28FC |
| 8086:8ca2 | 1458:5001 | Intel      | 9 Series Chipset Family S... | 67    | i2c_i801   | 2DDBCF3D21 |
| 10de:03eb | 1043:83a4 | Nvidia     | MCP61 SMBus                  | 66    | i2c_nfo... | 3248DFD987 |
| 1002:4385 | 1043:82ef | AMD        | SBx00 SMBus Controller       | 65    | i2c_pii... | EE184BFE51 |
| 8086:1c22 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 65    | i2c_i801   | 8579BA1B16 |
| 8086:1e22 | 1849:1e22 | Intel      | 7 Series/C216 Chipset Fam... | 65    | i2c_i801   | 3D8C4FEBC3 |
| 8086:283e | 1025:011f | Intel      | 82801H (ICH8 Family) SMBu... | 64    | i2c_i801   | 7387D70AD5 |
| 8086:1e22 | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 63    | i2c_i801   | 6478022B75 |
| 8086:a2a3 | 1458:5001 | Intel      | 200 Series/Z370 Chipset F... | 63    | i2c_i801   | AAD0551E27 |
| 8086:1e22 | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 62    | i2c_i801   | E67DFC255A |
| 8086:283e | 1043:81ec | Intel      | 82801H (ICH8 Family) SMBu... | 62    | i2c_i801   | A4A45B8A8B |
| 8086:1e22 | 1043:124d | Intel      | 7 Series/C216 Chipset Fam... | 61    | i2c_i801   | 0F8CE4DCC0 |
| 8086:1c22 | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 60    | i2c_i801   | 826F5492EB |
| 1022:780b | 1043:85ca | AMD        | FCH SMBus Controller         | 57    | i2c_piix4  | 35160C78AD |
| 8086:27da | 1462:7529 | Intel      | NM10/ICH7 Family SMBus Co... | 56    | i2c_i801   | 95C164BFE9 |
| 8086:3b30 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 56    | i2c_i801   | D023F50697 |
| 10de:0052 | 1043:815a | Nvidia     | CK804 SMBus                  | 54    | i2c_nfo... | C92DC5D0CF |
| 8086:0f12 | 17aa:3905 | Intel      | Atom Processor E3800 Seri... | 54    | i2c_i801   | CC7193A7B9 |
| 8086:a2a3 | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 54    | i2c_i801   | 7F1F084A4F |
| 1022:780b | 1462:7721 | AMD        | FCH SMBus Controller         | 51    | i2c_piix4  | B801DD3F7D |
| 8086:27da | 1025:0349 | Intel      | NM10/ICH7 Family SMBus Co... | 51    | i2c_i801   | 8CE41DB531 |
| 8086:3b30 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 51    | i2c_i801   | 52035C5F01 |
| 8086:1e22 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 50    | i2c_i801   | 39CA2BE7BB |
| 8086:27da | 1462:7592 | Intel      | NM10/ICH7 Family SMBus Co... | 50    | i2c_i801   | B0B570F44B |
| 1002:4385 | 1462:7693 | AMD        | SBx00 SMBus Controller       | 49    | i2c_pii... | FEAA959521 |
| 1022:790b | 1849:790b | AMD        | FCH SMBus Controller         | 49    | i2c_piix4  | 54A49FCBF7 |
| 8086:283e | 17aa:20a9 | Intel      | 82801H (ICH8 Family) SMBu... | 47    | i2c_i801   | 7F41843359 |
| 8086:1e22 | 1043:14c7 | Intel      | 7 Series/C216 Chipset Fam... | 46    | i2c_i801   | 9A401175B3 |
| 8086:1e22 | 17aa:5011 | Intel      | 7 Series/C216 Chipset Fam... | 46    | i2c_i801   | 65D329A2C6 |
| 1022:780b | 17aa:3801 | AMD        | FCH SMBus Controller         | 44    | i2c_piix4  | 760B445B08 |
| 8086:1c22 | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 44    | i2c_i801   | EE56C112BB |
| 8086:1c22 | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 43    | i2c_i801   | EA07B48EB4 |
| 8086:27da | 8086:27da | Intel      | NM10/ICH7 Family SMBus Co... | 43    | i2c_i801   | 2A6F47B09B |
| 10de:03eb | 1462:7309 | Nvidia     | MCP61 SMBus                  | 42    | i2c_nfo... | 11D0376265 |
| 8086:1c22 | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 41    | i2c_i801   | C0868A2B0C |
| 8086:1c22 | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 41    | i2c_i801   | 7AF20CDF5A |
| 8086:1c22 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 41    | i2c_i801   | 561B991E16 |
| 1022:780b | 144d:c0da | AMD        | FCH SMBus Controller         | 40    | i2c_piix4  | A06125BD54 |
| 8086:1d22 | 1043:84ef | Intel      | C600/X79 series chipset S... | 40    | i2c_i801   | EEE7D322DF |
| 8086:3b30 | 1849:3b30 | Intel      | 5 Series/3400 Series Chip... | 40    | i2c_i801   | 6CDC452D68 |
| 1022:780b | 1458:4385 | AMD        | FCH SMBus Controller         | 39    | i2c_piix4  | 8226B90793 |
| 8086:3b30 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 39    | i2c_i801   | 3C5767E938 |
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 39    | i2c_i801   | 1579402536 |
| 8086:1c22 | 144d:c0b6 | Intel      | 6 Series/C200 Series Chip... | 38    | i2c_i801   | 616616B60F |
| 8086:a123 | 1849:a123 | Intel      | 100 Series/C230 Series Ch... | 37    | i2c_i801   | BCB3EF58AB |
| 10de:03eb | 1565:3407 | Nvidia     | MCP61 SMBus                  | 36    | i2c_nfo... | E327FDD558 |
| 10de:0446 | 1462:7369 | Nvidia     | MCP65 SMBus                  | 36    | i2c_nfo... | C46668413C |
| 1022:780b | 1043:8527 | AMD        | FCH SMBus Controller         | 35    | i2c_piix4  | 88E3DD8AEA |
| 8086:1c22 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 35    | i2c_i801   | FBF8462F41 |
| 8086:27da | 1565:3103 | Intel      | NM10/ICH7 Family SMBus Co... | 35    | i2c_i801   | A1DD312C27 |
| 1002:4385 | 1565:3700 | AMD        | SBx00 SMBus Controller       | 34    | i2c_pii... | C9FA6E4826 |
| 1022:790b | 1043:876b | AMD        | FCH SMBus Controller         | 34    | i2c_piix4  | 76E2078928 |
| 8086:1e22 | 1462:7758 | Intel      | 7 Series/C216 Chipset Fam... | 34    | i2c_i801   | 0A593D376A |
| 8086:9c22 | 1025:0866 | Intel      | 8 Series SMBus Controller    | 34    | i2c_i801   | 1C77D7A584 |
| 10de:0752 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] SMBus  | 33    | i2c_nfo... | 88719BBDD6 |
| 10de:0aa2 | 10de:cb79 | Nvidia     | MCP79 SMBus                  | 33    | i2c_nfo... | 9F753AC669 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27d8 | 1458:a002 | Intel      | NM10/ICH7 Family High Def... | 336   | snd_hda... | D0D6CD20B1 |
| 8086:0c0c | 8086:2010 | Intel      | Xeon E3-1200 v3/4th Gen C... | 297   | snd_hda... | DD4DA32934 |
| 1002:4383 | 1458:a002 | AMD        | SBx00 Azalia (Intel HDA)     | 278   | snd_hda... | 8EAEF3C906 |
| 8086:1e20 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 262   | snd_hda... | 891002E8F2 |
| 8086:1c20 | 1458:a002 | Intel      | 6 Series/C200 Series Chip... | 239   | snd_hda... | E4C2A9F4EB |
| 8086:8c20 | 1043:8576 | Intel      | 8 Series/C220 Series Chip... | 239   | snd_hda... | F6CCF2BBA6 |
| 1002:4383 | 1043:8445 | AMD        | SBx00 Azalia (Intel HDA)     | 213   | snd_hda... | C0B50F9AE1 |
| 10de:0bea |           | Nvidia     | GF108 High Definition Aud... | 175   | snd_hda... | 88E3DD8AEA |
| 13f6:0111 | 13f6:0111 | C-Media... | CMI8738/CMI8768 PCI Audio    | 169   | snd_cmipci | F6B9026258 |
| 8086:8c20 | 1458:a002 | Intel      | 8 Series/C220 Series Chip... | 169   | snd_hda... | DD4DA32934 |
| 8086:1c20 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 164   | snd_hda... | A7618091FB |
| 8086:1e20 | 1458:a002 | Intel      | 7 Series/C216 Chipset Fam... | 163   | snd_hda... | A1E970227D |
| 8086:1c20 | 1043:8445 | Intel      | 6 Series/C200 Series Chip... | 159   | snd_hda... | CF410274A0 |
| 1002:aab0 | 174b:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 155   | snd_hda... | 5F6E1A3B61 |
| 1002:aab0 | 1043:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 153   | snd_hda... | 85F1B83B30 |
| 10de:03f0 | 1849:0397 | Nvidia     | MCP61 High Definition Audio  | 152   | snd_hda... | 4E526BB85F |
| 8086:1e20 | 1043:8445 | Intel      | 7 Series/C216 Chipset Fam... | 150   | snd_hda... | 6BF48D4173 |
| 8086:293e | 1043:829f | Intel      | 82801I (ICH9 Family) HD A... | 146   | snd_hda... | 48709E5844 |
| 8086:a170 | 1043:86c7 | Intel      | 100 Series/C230 Series Ch... | 142   | snd_hda... | 99614383EB |
| 8086:27d8 | 1849:3662 | Intel      | NM10/ICH7 Family High Def... | 137   | snd_hda... | 42C519E784 |
| 8086:1c20 | 1043:8415 | Intel      | 6 Series/C200 Series Chip... | 133   | snd_hda... | 6CF789DF63 |
| 1022:780d | 1458:a002 | AMD        | FCH Azalia Controller        | 114   | snd_hda... | 8226B90793 |
| 1002:4383 | 1043:836c | AMD        | SBx00 Azalia (Intel HDA)     | 113   | snd_hda... | D569843A2D |
| 10de:0be3 |           | Nvidia     | High Definition Audio Con... | 102   | snd_hda... | 85F57C764C |
| 1022:780d | 1043:8576 | AMD        | FCH Azalia Controller        | 101   | snd_hda... | 3A1BF1D002 |
| 10de:03f0 | 1458:a002 | Nvidia     | MCP61 High Definition Audio  | 100   | snd_hda... | BBF6B6F632 |
| 8086:3a3e | 1458:a002 | Intel      | 82801JI (ICH10 Family) HD... | 99    | snd_hda... | D77F80F180 |
| 8086:27d8 | 1043:8290 | Intel      | NM10/ICH7 Family High Def... | 98    | snd_hda... | FAC5E9FEFA |
| 8086:0c0c | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 96    | snd_hda... | B61D174C21 |
| 10de:0bee |           | Nvidia     | GF116 High Definition Aud... | 89    | snd_hda... | 0414258B09 |
| 8086:0a0c | 17aa:3978 | Intel      | Haswell-ULT HD Audio Cont... | 89    | snd_hda... | AFD92BF265 |
| 8086:9c20 | 17aa:3978 | Intel      | 8 Series HD Audio Controller | 89    | snd_hda... | AFD92BF265 |
| 8086:293e | 1458:a002 | Intel      | 82801I (ICH9 Family) HD A... | 88    | snd_hda... | 54231260FF |
| 8086:3a3e | 1043:82fe | Intel      | 82801JI (ICH10 Family) HD... | 88    | snd_hda... | 6C7C70F0E2 |
| 8086:a170 | 1458:a182 | Intel      | 100 Series/C230 Series Ch... | 87    | snd_hda... | 0BF4CAF942 |
| 1002:4383 | 1043:8444 | AMD        | SBx00 Azalia (Intel HDA)     | 85    | snd_hda... | BDE522FB15 |
| 1002:4383 | 1458:a102 | AMD        | SBx00 Azalia (Intel HDA)     | 84    | snd_hda... | A450827948 |
| 1002:aab0 | 1458:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 82    | snd_hda... | 35BF9EB2EF |
| 1002:aab0 | 1787:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 80    | snd_hda... | 98FF7EAA07 |
| 8086:1e20 | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 80    | snd_hda... | F28D18F3E9 |
| 1002:aa68 | 1043:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 79    | snd_hda... | 52035C5F01 |
| 8086:293e | 17aa:20f2 | Intel      | 82801I (ICH9 Family) HD A... | 79    | snd_hda... | FDAB3CF92F |
| 8086:27d8 | 1849:0397 | Intel      | NM10/ICH7 Family High Def... | 76    | snd_hda... | 5F6E1A3B61 |
| 8086:3b56 | 17aa:38af | Intel      | 5 Series/3400 Series Chip... | 75    | snd_hda... | 62697BF35B |
| 8086:293e | 17aa:3a0d | Intel      | 82801I (ICH9 Family) HD A... | 74    | snd_hda... | 601D53F9EB |
| 8086:3b56 | 1458:a002 | Intel      | 5 Series/3400 Series Chip... | 74    | snd_hda... | B39AC90CA0 |
| 8086:3b56 | 17aa:215e | Intel      | 5 Series/3400 Series Chip... | 72    | snd_hda... | DA5E944C6C |
| 1002:15de | 1002:15de | AMD        | Raven/Raven2/Fenghuang HD... | 71    | snd_hda... | 7D2B995B44 |
| 10de:0be4 |           | Nvidia     | High Definition Audio Con... | 71    | snd_hda... | 20093DA7FB |
| 8086:1e20 | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 69    | snd_hda... | CE3DDF28FC |
| 1002:4383 | 1849:7892 | AMD        | SBx00 Azalia (Intel HDA)     | 68    | snd_hda... | 4CFBA0B699 |
| 8086:8c20 | 1462:d817 | Intel      | 8 Series/C220 Series Chip... | 68    | snd_hda... | 7BBCD6F17D |
| 1002:aa90 | 174b:aa90 | AMD        | Turks HDMI Audio [Radeon ... | 67    | snd_hda... | A420D17B64 |
| 10de:0e0f | 1462:8c93 | Nvidia     | GK208 HDMI/DP Audio Contr... | 65    | snd_hda... | 606AACED27 |
| 8086:1c20 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 65    | snd_hda... | 8579BA1B16 |
| 1002:4383 | 1458:a182 | AMD        | SBx00 Azalia (Intel HDA)     | 64    | snd_hda... | 8CDD8FFE23 |
| 1002:aab0 | 1462:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 64    | snd_hda... | 46F0ADE589 |
| 8086:284b | 1025:011f | Intel      | 82801H (ICH8 Family) HD A... | 64    | snd_hda... | 7387D70AD5 |
| 1002:aa98 | 1043:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 63    | snd_hda... | EA07B48EB4 |
| 8086:1e20 | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 63    | snd_hda... | 6478022B75 |
| 8086:1e20 | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 62    | snd_hda... | E67DFC255A |
| 8086:27d8 | 1043:8437 | Intel      | NM10/ICH7 Family High Def... | 62    | snd_hda... | 595F2E7155 |
| 8086:27d8 | 1043:817f | Intel      | NM10/ICH7 Family High Def... | 61    | snd_hda... | 0C62C4C191 |
| 8086:284b | 1043:81ec | Intel      | 82801H (ICH8 Family) HD A... | 61    | snd_hda... | A4A45B8A8B |
| 1002:aa38 | 174b:aa38 | AMD        | RV710/730 HDMI Audio [Rad... | 60    | snd_hda... | 7A74EB0F6F |
| 8086:1c20 | 1043:1ac3 | Intel      | 6 Series/C200 Series Chip... | 60    | snd_hda... | 826F5492EB |
| 8086:1e20 | 1458:a014 | Intel      | 7 Series/C216 Chipset Fam... | 60    | snd_hda... | 8C4047657D |
| 1002:aa98 | 174b:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 59    | snd_hda... | 9CD2D7F72B |
| 8086:27d8 | 1043:82ea | Intel      | NM10/ICH7 Family High Def... | 59    | snd_hda... | 9D3DBD169B |
| 1102:0007 | 1102:100a | Creativ... | CA0106/CA0111 [SB Live!/A... | 58    | snd_ca0106 | BDE522FB15 |
| 8086:27d8 | 1043:83a1 | Intel      | NM10/ICH7 Family High Def... | 58    | snd_hda... | 1A62B680D7 |
| 1002:aa58 | 174b:aa58 | AMD        | Juniper HDMI Audio [Radeo... | 57    | snd_hda... | A4DA822D7B |
| 8086:27d8 | 1462:7529 | Intel      | NM10/ICH7 Family High Def... | 56    | snd_hda... | 95C164BFE9 |
| 8086:3b56 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 56    | snd_hda... | D023F50697 |
| 1022:780d | 1849:7662 | AMD        | FCH Azalia Controller        | 55    | snd_hda... | 5AEB4ABFE6 |
| 1002:9902 | 1002:9902 | AMD        | Trinity HDMI Audio Contro... | 54    | snd_hda... | 32E1C72BAA |
| 1002:aa68 | 174b:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 54    | snd_hda... | EBB5316694 |
| 8086:0f04 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 54    | snd_hda... | CC7193A7B9 |
| 8086:293e | 1043:8277 | Intel      | 82801I (ICH9 Family) HD A... | 54    | snd_hda... | 29B7777E42 |
| 8086:0c0c | 17aa:3978 | Intel      | Xeon E3-1200 v3/4th Gen C... | 53    | snd_hda... | 262BB6B100 |
| 8086:8c20 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 53    | snd_hda... | 262BB6B100 |
| 10de:0bea | 1569:0f00 | Nvidia     | GF108 High Definition Aud... | 52    | snd_hda... | F99AFC78BD |
| 1002:4383 | 1849:7662 | AMD        | SBx00 Azalia (Intel HDA)     | 51    | snd_hda... | 98FF7EAA07 |
| 10de:0be2 |           | Nvidia     | GT216 HDMI Audio Controller  | 51    | snd_hda... | 2458B122E5 |
| 10de:0e1b | 1569:0fc6 | Nvidia     | GK107 HDMI Audio Controller  | 51    | snd_hda... | 230E4F00BA |
| 8086:1e20 | 1043:118f | Intel      | 7 Series/C216 Chipset Fam... | 51    | snd_hda... | 0F8CE4DCC0 |
| 8086:27d8 | 1025:0349 | Intel      | NM10/ICH7 Family High Def... | 51    | snd_hda... | 8CE41DB531 |
| 8086:a2f0 | 1458:a182 | Intel      | 200 Series PCH HD Audio      | 51    | snd_hda... | AAD0551E27 |
| 1022:780d | 1462:d721 | AMD        | FCH Azalia Controller        | 50    | snd_hda... | B801DD3F7D |
| 8086:1e20 | 1043:8415 | Intel      | 7 Series/C216 Chipset Fam... | 50    | snd_hda... | F3E244219B |
| 8086:27d8 | 1462:7592 | Intel      | NM10/ICH7 Family High Def... | 50    | snd_hda... | B0B570F44B |
| 1002:aa58 | 1787:aa58 | AMD        | Juniper HDMI Audio [Radeo... | 49    | snd_hda... | 47FD7AB796 |
| 1022:1457 | 1043:86c7 | AMD        | Family 17h (Models 00h-0f... | 49    | snd_hda... | 03B0E6294F |
| 8086:8ca0 | 1458:a182 | Intel      | 9 Series Chipset Family H... | 49    | snd_hda... | 2DDBCF3D21 |
| 1002:1714 | 1002:1714 | AMD        | BeaverCreek HDMI Audio [R... | 48    | snd_hda... | 04E7074682 |
| 8086:1c20 | 1043:8444 | Intel      | 6 Series/C200 Series Chip... | 48    | snd_hda... | 7A74EB0F6F |
| 8086:284b | 17aa:20ac | Intel      | 82801H (ICH8 Family) HD A... | 47    | snd_hda... | 7F41843359 |
| 1002:4383 | 1043:8436 | AMD        | SBx00 Azalia (Intel HDA)     | 46    | snd_hda... | A2F40FA9C0 |
| 1002:4383 | 1462:d693 | AMD        | SBx00 Azalia (Intel HDA)     | 46    | snd_hda... | D9438B26E4 |
| 1002:aa60 | 174b:aa60 | AMD        | Redwood HDMI Audio [Radeo... | 46    | snd_hda... | 42619A6CCA |

### Storage (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 104c:803b | 1025:011f | Texas I... | PCIxx12 Flash Media Contr... | 64    | tifm_7xx1  | 7387D70AD5 |
| 1217:8231 | 1028:0493 | O2 Micro   | O2Micro Integrated MS/MSP... | 28    |            | CA6EFEBBD7 |
| 104c:803b | 1179:ff00 | Texas I... | PCIxx12 Flash Media Contr... | 23    | tifm_7xx1  | 92ACB586D2 |
| 1283:8211 | 1043:8138 | Integra... | ITE 8211F Single Channel ... | 23    | pata_it... | 2BF9512AD1 |
| 1217:7130 | 1025:013c | O2 Micro   | Integrated MS/xD Controller  | 18    |            | 77E3B20E26 |
| 1217:7130 | 1179:ff50 | O2 Micro   | Integrated MS/xD Controller  | 18    |            | B6017B2145 |
| 104c:803b | 1179:ff02 | Texas I... | PCIxx12 Flash Media Contr... | 17    | tifm_7xx1  | 3CE1664885 |
| 104c:803b | 1179:ff10 | Texas I... | PCIxx12 Flash Media Contr... | 15    | tifm_7xx1  | 4FFE571137 |
| 104c:803b | 1025:0110 | Texas I... | PCIxx12 Flash Media Contr... | 12    | tifm_7xx1  | D4A385C83A |
| 1095:3132 | 1043:819f | Silicon... | SiI 3132 Serial ATA Raid ... | 12    | sata_sil24 | 2BF9512AD1 |
| 8086:1d6b | 103c:1589 | Intel      | C602 chipset 4-Port SATA ... | 12    | isci       | E14EB74EA5 |
| 104c:803b | 1025:0107 | Texas I... | PCIxx12 Flash Media Contr... | 10    | tifm_7xx1  | D14CE30BB6 |
| 1217:8330 | 1028:04a3 | O2 Micro   | OZ600 MS/xD Controller       | 10    |            | 19E1CA5871 |
| 1217:8331 | 1028:0494 | O2 Micro   | O2 Flash Memory Card         | 10    |            | 31F0876A89 |
| 1217:8331 | 1028:049a | O2 Micro   | O2 Flash Memory Card         | 8     |            | 5D67AE99E3 |
| 1000:0058 | 1028:1f0e | LSI Log... | SAS1068E PCI-Express Fusi... | 7     | mptsas     | BCA2EBDBAF |
| 104c:803b | 104d:902d | Texas I... | PCIxx12 Flash Media Contr... | 7     | tifm_7xx1  | BD8A19714A |
| 1217:7130 | 10cf:143d | O2 Micro   | Integrated MS/xD Controller  | 7     |            | 6639C529C5 |
| 104c:803b | 104d:81e6 | Texas I... | PCIxx12 Flash Media Contr... | 6     | tifm_7xx1  | 50E5B9D6CA |
| 104c:803b | 104d:9005 | Texas I... | PCIxx12 Flash Media Contr... | 6     | tifm_7xx1  | 858BD651B7 |
| 104c:803b | 104d:9015 | Texas I... | PCIxx12 Flash Media Contr... | 6     | tifm_7xx1  | 3BEE1DDF68 |
| 104c:803b | 1179:0001 | Texas I... | PCIxx12 Flash Media Contr... | 6     | tifm_7xx1  | 3E0ED41BC7 |
| 1217:8331 | 1028:049b | O2 Micro   | O2 Flash Memory Card         | 6     |            | 26DE378A54 |
| 1b85:6018 | 1b85:6018 | OCZ Tec... | RD400/400A SSD               | 6     | nvme       | 19AD634C13 |
| 8086:1d6b | 103c:158a | Intel      | C602 chipset 4-Port SATA ... | 6     | isci       | 2AB82BCF03 |
| 104c:803b | 1025:011c | Texas I... | PCIxx12 Flash Media Contr... | 5     | tifm_7xx1  | 89E46BA6FF |
| 1095:3132 | 1095:3132 | Silicon... | SiI 3132 Serial ATA Raid ... | 5     | sata_sil24 | A0F0B2CB3C |
| 1217:7130 | 10cf:14d6 | O2 Micro   | Integrated MS/xD Controller  | 5     |            | EEFC712947 |
| 1217:8330 | 1028:04a4 | O2 Micro   | OZ600 MS/xD Controller       | 5     |            | 370EF78297 |
| 104c:8033 | 1179:0001 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 4     | tifm_7xx1  | D5D7DAB02F |
| 104c:8033 | 17c0:3007 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 4     | tifm_7xx1  | EFDFFC9FB6 |
| 104c:803b | 103c:30aa | Texas I... | PCIxx12 Flash Media Contr... | 4     | tifm_7xx1  | CF41AB5F1A |
| 104c:803b | 104d:8212 | Texas I... | PCIxx12 Flash Media Contr... | 4     | tifm_7xx1  | 8938DD9A9E |
| 104c:803b | 104d:9016 | Texas I... | PCIxx12 Flash Media Contr... | 4     | tifm_7xx1  | C257EC2DD4 |
| 1217:7130 | 1025:012b | O2 Micro   | Integrated MS/xD Controller  | 4     |            | 21509117BA |
| 1217:7130 | 1028:0273 | O2 Micro   | Integrated MS/xD Controller  | 4     |            | C9D61D9E11 |
| 1217:8130 | 1028:02bc | O2 Micro   | Integrated MS/MSPRO/xD Co... | 4     |            | 20F0F865AE |
| 1217:8130 | 1179:ff50 | O2 Micro   | Integrated MS/MSPRO/xD Co... | 4     |            | 34905CB301 |
| 1283:8212 | 1043:813a | Integra... | IT8212 Dual channel ATA R... | 4     | pata_it... | 87F8B4B22A |
| 1283:8212 | 105b:0cc0 | Integra... | IT8212 Dual channel ATA R... | 4     | pata_it... | 6311678EE1 |
| 9005:8017 | 9005:0045 | Adaptec    | ASC-29320ALP U320            | 4     | aic79xx    | 5C3DF14DAD |
| 1000:0072 | 1000:3020 | LSI Log... | SAS2008 PCI-Express Fusio... | 3     | mpt3sas    | 96AE8D3618 |
| 1000:0072 | 1028:1f1c | LSI Log... | SAS2008 PCI-Express Fusio... | 3     | mpt3sas    | 0EEF21306D |
| 104c:8033 | 1025:0066 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 3     | tifm_7xx1  | E814DA247A |
| 104c:8033 | 103c:0944 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 3     | tifm_7xx1  | 5DA5847C6D |
| 104c:8033 | 103c:3080 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 3     | tifm_7xx1  | 6802B34FDD |
| 104c:8033 | 103c:309d | Texas I... | PCIxx21/PCIxx11 Flash Med... | 3     | tifm_7xx1  | 837230178B |
| 104c:8033 | 1179:ff05 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 3     | tifm_7xx1  | 45B2F7B46A |
| 104c:803b | 1025:0094 | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | 72E2443AE3 |
| 104c:803b | 1025:0130 | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | 840D602BA8 |
| 104c:803b | 103c:309f | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | 5BE41E5F47 |
| 104c:803b | 103c:30ac | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | 3604EF7ED6 |
| 104c:803b | 104d:81ef | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | 8D7F285234 |
| 104c:803b | 104d:9008 | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | AFBC222743 |
| 104c:ac8f | 104d:8190 | Texas I... | PCI7420/7620 SD/MS-Pro Co... | 3     | tifm_7xx1  | C3CFD62BCD |
| 1077:2432 | 1077:0138 | QLogic     | ISP2432-based 4Gb Fibre C... | 3     | qla2xxx    | FB66D16E30 |
| 1095:3531 | 1734:1107 | Silicon... | SiI 3531 [SATALink/SATARa... | 3     | sata_sil24 | 7F4ACC9070 |
| 10df:fe00 | 10df:fe00 | Emulex     | Zephyr-X LightPulse Fibre... | 3     | lpfc       | 6806624961 |
| 1217:7130 | 1462:3ff3 | O2 Micro   | Integrated MS/xD Controller  | 3     |            | E6FCAC8295 |
| 8086:1d6b | 1734:11b6 | Intel      | C602 chipset 4-Port SATA ... | 3     | isci       | 961A7ADB3E |
| 9004:7178 |           | Adaptec    | AIC-7870P/7871 [AHA-2940/... | 3     | aic7xxx    | 87BEA4712A |
| 1000:0001 |           | LSI Log... | 53c810                       | 2     | sym53c8xx  | C433E6081D |
| 1000:0030 | 103c:322a | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 2     | mptspi     | C156F0AB27 |
| 1000:0058 | 1028:1f0f | LSI Log... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | 0F9D97BC71 |
| 1000:0058 | 1028:1f10 | Broadco... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | F3E244219B |
| 1000:0058 | 103c:3229 | LSI Log... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | D082929A57 |
| 1000:0070 | 1000:3010 | LSI Log... | SAS2004 PCI-Express Fusio... | 2     | mpt2sas    | 99E743CA9E |
| 1000:0086 | 103c:158b | Broadco... | SAS2308 PCI-Express Fusio... | 2     | mpt3sas    | E9DB290332 |
| 104c:8033 | 103c:0934 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 2     | tifm_7xx1  | 16F00AAE37 |
| 104c:8033 | 103c:30a4 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 2     | tifm_7xx1  | 817D97FE5A |
| 104c:8033 | 1734:1092 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 2     | tifm_7xx1  | 4D0D913872 |
| 104c:803b | 1025:006c | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 1CE26C391A |
| 104c:803b | 1025:0096 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 070206A279 |
| 104c:803b | 1025:0102 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 5CBBF81362 |
| 104c:803b | 1028:02ef | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 089056D291 |
| 104c:803b | 103c:30b0 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 7FE3257344 |
| 104c:803b | 1179:ff03 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 1A383B7FBD |
| 104c:803b | 152d:0753 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | F57558EF8E |
| 104c:803b | 152d:0763 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | E07AB48C55 |
| 104c:803b | 1558:0661 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 2A6A5EFE01 |
| 104c:803b | 17aa:207c | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 97AECB0406 |
| 104c:803b | 17ff:0590 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 8B79E00851 |
| 1095:3114 | 1043:8136 | Silicon... | SiI 3114 [SATALink/SATARa... | 2     | sata_sil   | 87F8B4B22A |
| 1095:3531 | 1095:3531 | Silicon... | SiI 3531 [SATALink/SATARa... | 2     | sata_sil24 | 7386C9D836 |
| 1217:7130 | 1025:011a | O2 Micro   | Integrated MS/xD Controller  | 2     |            | 69380B60FC |
| 1217:7130 | 1025:0124 | O2 Micro   | Integrated MS/xD Controller  | 2     |            | 5AAFE28787 |
| 1217:7130 | 1028:026f | O2 Micro   | Integrated MS/xD Controller  | 2     |            | D6AAC94E1F |
| 1217:7130 | 1028:0275 | O2 Micro   | Integrated MS/xD Controller  | 2     |            | B0314C0713 |
| 1217:7130 | 1462:3fc1 | O2 Micro   | Integrated MS/xD Controller  | 2     |            | 278EF4A255 |
| 1283:8211 | 1283:8211 | Integra... | ITE 8211F Single Channel ... | 2     | pata_it... | 27A7AB5704 |
| 1b85:1021 | 1b85:1021 | OCZ Tec... | OCZ SCSI storage controller  | 2     | mvsas      | 88092CA377 |
| 1de1:0391 | 1de1:0391 | Tekram ... | TRM-S1040 [DC-315 / DC-39... | 2     | dc395x     | BBFFB3F1D1 |
| 8086:1d6b | 103c:158b | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | E9DB290332 |
| 8086:1d6b | 1043:84ef | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 996F55BB36 |
| 9004:5078 | 9004:7850 | Adaptec    | AIC-7850T/7856T [AVA-2902... | 2     | aic7xxx    | 5A21D12B42 |
| 9004:8178 |           | Adaptec    | AIC-7870P/7881U [AHA-2940... | 2     | aic7xxx    | 2BAC98B043 |
| 1000:0030 | 1000:50c0 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 3F4700F256 |
| 1000:0030 | 1014:026c | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 46973B5B05 |
| 1000:0030 | 1014:1000 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 659D759E6D |
| 1000:0030 | 1028:016e | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 76EF1C8CA9 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:4390 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 323   | ahci       | 804B46A359 |
| 8086:8c02 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 308   | ahci       | F6CCF2BBA6 |
| 1002:4390 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 275   | ahci       | D569843A2D |
| 1002:4391 | 1043:84dd | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 274   | ahci       | 6A60A724F9 |
| 8086:1e02 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 256   | ahci       | 570B707FFB |
| 8086:1c02 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 246   | ahci       | 66A5EA0BE5 |
| 8086:1e03 | 17aa:3977 | Intel      | 7 Series Chipset Family 6... | 241   | ahci       | 891002E8F2 |
| 1002:4391 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 223   | ahci       | 394C81B911 |
| 1b21:0612 | 1043:84b7 | ASMedia... | ASM1062 Serial ATA Contro... | 207   | ahci       | 9876ED8DB9 |
| 8086:a102 | 1043:8694 | Intel      | Q170/Q150/B150/H170/H110/... | 196   | ahci       | 99614383EB |
| 8086:8c02 | 1458:b005 | Intel      | 8 Series/C220 Series Chip... | 168   | ahci       | DD4DA32934 |
| 8086:27c1 | 1043:83ad | Intel      | NM10/ICH7 Family SATA Con... | 154   | ahci       | 6A0513EC8D |
| 8086:1c03 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 149   | ahci       | A7618091FB |
| 1022:43b7 | 1b21:1062 | AMD        | 300 Series Chipset SATA C... | 129   | ahci       | 518A8709C7 |
| 8086:1e02 | 1458:b005 | Intel      | 7 Series/C210 Series Chip... | 125   | ahci       | BD8118E7B8 |
| 1022:7901 | 1043:8747 | AMD        | FCH SATA Controller [AHCI... | 123   | ahci       | 4A2455EAE6 |
| 1002:4391 | 1849:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 121   | ahci       | 85F1B83B30 |
| 1022:43c8 | 1b21:1062 | AMD        | 400 Series Chipset SATA C... | 109   | ahci       | 4A2455EAE6 |
| 8086:1c02 | 1458:b005 | Intel      | 6 Series/C200 Series Chip... | 108   | ahci       | 048F01BE63 |
| 1022:7801 | 1458:b002 | AMD        | FCH SATA Controller [AHCI... | 106   | ahci       | 4C91A0DF19 |
| 8086:a102 | 1458:b005 | Intel      | Q170/Q150/B150/H170/H110/... | 103   | ahci       | 0BF4CAF942 |
| 1002:4390 | 1849:4390 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 102   | ahci       | A41EFF2ADC |
| 1b21:0612 | 1849:0612 | ASMedia... | ASM1062 Serial ATA Contro... | 91    | ahci       | 85F1B83B30 |
| 1022:7801 | 1849:7801 | AMD        | FCH SATA Controller [AHCI... | 89    | ahci       | BF930C8C33 |
| 8086:3a22 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) SA... | 89    | ahci       | EBB5316694 |
| 8086:9c03 | 17aa:3978 | Intel      | 8 Series SATA Controller ... | 89    | ahci       | AFD92BF265 |
| 1022:7901 | 1458:b002 | AMD        | FCH SATA Controller [AHCI... | 86    | ahci       | 0438613602 |
| 197b:2362 | 1043:8460 | JMicron... | JMB362 SATA Controller       | 85    | ahci       | 6A60A724F9 |
| 1022:43b5 | 1b21:1062 | AMD        | X370 Series Chipset SATA ... | 80    | ahci       | D084D64BDF |
| 1022:7800 | 1458:b002 | AMD        | FCH SATA Controller [IDE ... | 80    | ahci       | 8226B90793 |
| 8086:3b29 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 79    | ahci       | 52035C5F01 |
| 1b4b:9172 | 1458:b000 | Marvell... | 88SE9172 SATA 6Gb/s Contr... | 77    | ahci       | 394C81B911 |
| 8086:1e03 | 1025:0649 | Intel      | 7 Series Chipset Family 6... | 77    | ahci       | F28D18F3E9 |
| 8086:1c03 | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 76    | ahci       | 6B25B8982D |
| 8086:8c82 | 1043:8534 | Intel      | 9 Series Chipset Family S... | 72    | ahci       | EFA3992D9A |
| 8086:8c02 | 1849:8c02 | Intel      | 8 Series/C220 Series Chip... | 71    | ahci       | 8AE6B6F651 |
| 8086:3b29 | 17aa:38c1 | Intel      | 5 Series/3400 Series Chip... | 70    | ahci       | 62697BF35B |
| 1002:4391 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 69    | ahci       | 277055C3E7 |
| 8086:2929 | 17aa:20f8 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 69    | ahci       | A23E000798 |
| 8086:8c02 | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 68    | ahci       | 7BBCD6F17D |
| 8086:1e03 | 17aa:5002 | Intel      | 7 Series Chipset Family 6... | 67    | ahci       | CE3DDF28FC |
| 8086:2929 | 17aa:3a1a | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 63    | ahci       | 601D53F9EB |
| 8086:1c02 | 1849:1c02 | Intel      | 6 Series/C200 Series Chip... | 62    | ahci       | BDA40E6195 |
| 8086:1c03 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 62    | ahci       | 8579BA1B16 |
| 8086:1e02 | 1849:1e02 | Intel      | 7 Series/C210 Series Chip... | 62    | ahci       | 3D8C4FEBC3 |
| 8086:8c82 | 1458:b005 | Intel      | 9 Series Chipset Family S... | 62    | ahci       | 2DDBCF3D21 |
| 1002:4390 | 1043:82ef | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 60    | ahci       | EE184BFE51 |
| 8086:1c03 | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 60    | ahci       | 826F5492EB |
| 8086:1e03 | 1025:0647 | Intel      | 7 Series Chipset Family 6... | 60    | ahci       | 6478022B75 |
| 1002:4391 | 1002:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 58    | ahci       | A420D17B64 |
| 8086:a282 | 1458:b005 | Intel      | 200 Series PCH SATA contr... | 58    | ahci       | AAD0551E27 |
| 1002:4390 | 1002:4390 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 57    | ahci       | 33F663A020 |
| 8086:1e03 | 1025:064b | Intel      | 7 Series Chipset Family 6... | 57    | ahci       | E67DFC255A |
| 8086:1e03 | 1043:124d | Intel      | 7 Series Chipset Family 6... | 57    | ahci       | 0F8CE4DCC0 |
| 8086:3b2f | 17aa:2168 | Intel      | 5 Series/3400 Series Chip... | 57    | ahci       | DA5E944C6C |
| 1022:7801 | 1043:85ca | AMD        | FCH SATA Controller [AHCI... | 55    | ahci       | 35160C78AD |
| 1022:7801 | 1462:7721 | AMD        | FCH SATA Controller [AHCI... | 51    | ahci       | B801DD3F7D |
| 8086:3b29 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 51    | ahci       | D023F50697 |
| 8086:0f23 | 17aa:3905 | Intel      | Atom Processor E3800 Seri... | 50    | ahci       | CC7193A7B9 |
| 8086:8c03 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 49    | ahci       | 262BB6B100 |
| 8086:a282 | 1043:8694 | Intel      | 200 Series PCH SATA contr... | 49    | ahci       | C9E6C4517D |
| 1022:7901 | 1849:7901 | AMD        | FCH SATA Controller [AHCI... | 48    | ahci       | 54A49FCBF7 |
| 8086:1e03 | 8086:7270 | Intel      | 7 Series Chipset Family 6... | 48    | ahci       | 39CA2BE7BB |
| 1022:43b8 | 1b21:1062 | AMD        | FCH SATA Controller D        | 47    | ahci       | A0518E949A |
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 47    | ahci       | 35BF9EB2EF |
| 1b21:0612 | 1043:858d | ASMedia... | ASM1062 Serial ATA Contro... | 45    | ahci       | B61D174C21 |
| 8086:1c03 | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 44    | ahci       | EE56C112BB |
| 8086:27c1 | 1025:0349 | Intel      | NM10/ICH7 Family SATA Con... | 44    | ahci       | 8CE41DB531 |
| 1022:7801 | 17aa:3801 | AMD        | FCH SATA Controller [AHCI... | 42    | ahci       | 760B445B08 |
| 8086:1c03 | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 42    | ahci       | EA07B48EB4 |
| 8086:1e03 | 1043:14c7 | Intel      | 7 Series Chipset Family 6... | 42    | ahci       | 9A401175B3 |
| 1b21:0612 | 1b21:1060 | ASMedia... | ASM1062 Serial ATA Contro... | 41    | ahci       | 5AFC22B5E1 |
| 1b4b:9130 | 1043:8438 | Marvell... | 88SE9128 PCIe SATA 6 Gb/s... | 41    | ahci       | AC377EFFFB |
| 8086:1e03 | 17aa:5011 | Intel      | 7 Series Chipset Family 6... | 41    | ahci       | 65D329A2C6 |
| 1002:4391 | 1043:1117 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 40    | ahci       | 527313B5FF |
| 1022:7804 | 144d:c0da | AMD        | FCH SATA Controller [AHCI... | 40    | ahci       | A06125BD54 |
| 8086:1c03 | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 40    | ahci       | C0868A2B0C |
| 8086:3b29 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 39    | ahci       | 3C5767E938 |
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 39    | ahci       | 1579402536 |
| 8086:1c03 | 144d:c0b6 | Intel      | 6 Series/C200 Series Chip... | 38    | ahci       | 616616B60F |
| 8086:3a22 | 1458:b005 | Intel      | 82801JI (ICH10 Family) SA... | 38    | ahci       | F655F180AC |
| 1002:4390 | 1043:8443 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 37    | ahci       | 054E0BF393 |
| 1b4b:9172 | 1043:8477 | Marvell... | 88SE9172 SATA 6Gb/s Contr... | 37    | ahci       | 0EEF21306D |
| 8086:2929 | 1043:1867 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 37    | ahci       | 38190AD2E1 |
| 8086:a102 | 1849:a102 | Intel      | Q170/Q150/B150/H170/H110/... | 37    | ahci       | BCB3EF58AB |
| 8086:2829 | 17aa:20a7 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 36    | ahci       | 7F41843359 |
| 8086:3b22 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 36    | ahci       | 349A68F1F0 |
| 8086:1d02 | 1043:84ef | Intel      | C600/X79 series chipset 6... | 35    | ahci       | 1E7C5CF3CF |
| 1022:7801 | 1043:8527 | AMD        | FCH SATA Controller [AHCI... | 34    | ahci       | 88E3DD8AEA |
| 1022:7901 | 1043:876b | AMD        | FCH SATA Controller [AHCI... | 34    | ahci       | 76E2078928 |
| 8086:9c03 | 1025:0866 | Intel      | 8 Series SATA Controller ... | 34    | ahci       | 1C77D7A584 |
| 8086:0f23 | 17aa:3909 | Intel      | Atom Processor E3800 Seri... | 33    | ahci       | EE1CFF7014 |
| 8086:1c03 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 33    | ahci       | FBF8462F41 |
| 8086:1e02 | 1462:7758 | Intel      | 7 Series/C210 Series Chip... | 33    | ahci       | 0A593D376A |
| 8086:2829 | 1025:011f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 32    | ahci       | 7387D70AD5 |
| 8086:5ae3 | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 32    | ahci       | 0FAD7AC4EB |
| 1002:4391 | 103c:3577 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 31    | ahci       | 4201CDD966 |
| 8086:2929 | 1025:0212 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 31    | ahci       | 6029A4A18A |
| 8086:3b22 | 1458:b005 | Intel      | 5 Series/3400 Series Chip... | 31    | ahci       | B39AC90CA0 |
| 1002:4380 | 1043:81ef | AMD        | SB600 Non-Raid-5 SATA        | 30    | ahci       | B26ED41AB8 |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27df | 1043:8179 | Intel      | 82801G (ICH7 Family) IDE ... | 559   | ata_pii... | FAC5E9FEFA |
| 1002:439c | 1458:5002 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 469   | pata_at... | 8EAEF3C906 |
| 8086:27c0 | 1458:b002 | Intel      | NM10/ICH7 Family SATA Con... | 402   | ata_pii... | D0D6CD20B1 |
| 8086:27c0 | 1043:8179 | Intel      | NM10/ICH7 Family SATA Con... | 393   | ata_pii... | FAC5E9FEFA |
| 1002:439c | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 339   | pata_at... | D569843A2D |
| 8086:27c0 | 1849:27c0 | Intel      | NM10/ICH7 Family SATA Con... | 241   | ata_pii... | 5F6E1A3B61 |
| 8086:27df | 1849:27df | Intel      | 82801G (ICH7 Family) IDE ... | 234   | ata_pii... | 34021FD6BD |
| 8086:1c00 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 226   | ata_pii... | EB9D0FE3F5 |
| 8086:1c08 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 226   | ata_pii... | EB9D0FE3F5 |
| 1002:439c | 1849:439c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 212   | pata_at... | 85F1B83B30 |
| 197b:2363 | 1458:b000 | JMicron... | JMB363 SATA/IDE Controller   | 204   | ahci       | B39AC90CA0 |
| 10de:03f6 | 1849:03f6 | Nvidia     | MCP61 SATA Controller        | 193   | sata_nv... | 816FE60D2D |
| 8086:2926 | 1043:8277 | Intel      | 82801I (ICH9 Family) 2 po... | 189   | ata_pii... | E2D3942D30 |
| 8086:3a20 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) 4 ... | 185   | ata_pii... | B481805845 |
| 8086:3a26 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) 2 ... | 185   | ata_pii... | B481805845 |
| 10de:03ec | 1849:03ec | Nvidia     | MCP61 IDE                    | 184   | pata_am... | 816FE60D2D |
| 8086:1c08 | 1458:b002 | Intel      | 6 Series/C200 Series Chip... | 183   | ata_pii... | E4C2A9F4EB |
| 8086:27c0 | 1043:2601 | Intel      | NM10/ICH7 Family SATA Con... | 173   | ata_pii... | 7D6812488D |
| 197b:2368 | 1458:b000 | JMicron... | JMB368 IDE controller        | 158   | pata_jm... | 54231260FF |
| 197b:2363 | 1043:824f | JMicron... | JMB363 SATA/IDE Controller   | 145   | ahci       | 29B7777E42 |
| 8086:2921 | 1043:8277 | Intel      | 82801IB (ICH9) 2 port SAT... | 127   | ata_pii... | E2D3942D30 |
| 8086:1e00 | 1458:b005 | Intel      | 7 Series/C210 Series Chip... | 110   | ata_pii... | 8C4047657D |
| 8086:1e08 | 1458:b002 | Intel      | 7 Series/C210 Series Chip... | 110   | ata_pii... | 8C4047657D |
| 10de:03f6 | 1458:b002 | Nvidia     | MCP61 SATA Controller        | 105   | sata_nv... | BBF6B6F632 |
| 8086:3a20 | 1458:b002 | Intel      | 82801JI (ICH10 Family) 4 ... | 104   | ata_pii... | 3446957FCC |
| 8086:3a26 | 1458:b002 | Intel      | 82801JI (ICH10 Family) 2 ... | 104   | ata_pii... | 3446957FCC |
| 197b:2363 | 1043:81e4 | JMicron... | JMB363 SATA/IDE Controller   | 98    | ahci       | 6932570C80 |
| 1022:780c | 1458:5002 | AMD        | FCH IDE Controller           | 97    | pata_at... | 8226B90793 |
| 8086:1c00 | 1458:b005 | Intel      | 6 Series/C200 Series Chip... | 93    | ata_pii... | E4C2A9F4EB |
| 8086:1c00 | 1458:b002 | Intel      | 6 Series/C200 Series Chip... | 92    | ata_pii... | CDABCF84B6 |
| 1106:0415 | 1043:838f | VIA Tec... | VT6415 PATA IDE Host Cont... | 91    | pata_vi... | 66A5EA0BE5 |
| 197b:2368 | 1043:827e | JMicron... | JMB368 IDE controller        | 91    | pata_jm... | E2D3942D30 |
| 8086:1e00 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 91    | ata_pii... | 2703EE0766 |
| 8086:1e08 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 91    | ata_pii... | 2703EE0766 |
| 10de:03ec | 1458:5002 | Nvidia     | MCP61 IDE                    | 86    | pata_am... | BBF6B6F632 |
| 8086:27df | 1458:b001 | Intel      | 82801G (ICH7 Family) IDE ... | 86    | ata_pii... | 9CD2D7F72B |
| 8086:2926 | 1458:b002 | Intel      | 82801I (ICH9 Family) 2 po... | 85    | ata_pii... | 54231260FF |
| 8086:3b20 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 81    | ata_pii... | 05DC50AA11 |
| 8086:3b26 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 81    | ata_pii... | 05DC50AA11 |
| 11ab:6101 | 1043:82e0 | Marvell... | 88SE6101/6102 single-port... | 78    | pata_ma... | 54F8BAB8A3 |
| 1022:780c | 1849:780c | AMD        | FCH IDE Controller           | 74    | pata_at... | 33CFE3D019 |
| 10de:03f6 | 1043:8234 | Nvidia     | MCP61 SATA Controller        | 72    | sata_nv... | 2A30939325 |
| 10de:03ec | 1043:8234 | Nvidia     | MCP61 IDE                    | 71    | pata_am... | 2A30939325 |
| 1002:439c | 1002:439c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 67    | pata_at... | 33F663A020 |
| 10de:03f6 | 1043:83a4 | Nvidia     | MCP61 SATA Controller        | 66    | sata_nv... | 3248DFD987 |
| 1002:439c | 1043:82ef | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 65    | pata_at... | EE184BFE51 |
| 10de:03ec | 1043:83a4 | Nvidia     | MCP61 IDE                    | 64    | pata_am... | 3248DFD987 |
| 8086:2850 | 1025:011f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 64    | ata_pii... | 7387D70AD5 |
| 8086:2920 | 1043:8277 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 62    | ata_pii... | 48709E5844 |
| 8086:1c00 | 1849:1c00 | Intel      | 6 Series/C200 Series Chip... | 59    | ata_pii... | EC6555DA94 |
| 8086:1c08 | 1849:1c08 | Intel      | 6 Series/C200 Series Chip... | 58    | ata_pii... | EC6555DA94 |
| 11ab:6101 | 11ab:6101 | Marvell... | 88SE6101/6102 single-port... | 57    | pata_ma... | FE7535550F |
| 11ab:6121 | 1043:82a2 | Marvell... | 88SE6111/6121 SATA II / P... | 56    | pata_ma... | 500CF9D1A0 |
| 8086:27c0 | 1462:7529 | Intel      | NM10/ICH7 Family SATA Con... | 56    | ata_pii... | 95C164BFE9 |
| 10de:0053 | 1043:815a | Nvidia     | CK804 IDE                    | 54    | pata_am... | C92DC5D0CF |
| 10de:0055 | 1043:815a | Nvidia     | CK804 Serial ATA Controller  | 54    | sata_nv... | C92DC5D0CF |
| 8086:27df | 1462:7529 | Intel      | 82801G (ICH7 Family) IDE ... | 54    | ata_pii... | 95C164BFE9 |
| 8086:3b20 | 1458:b002 | Intel      | 5 Series/3400 Series Chip... | 54    | ata_pii... | 85F57C764C |
| 8086:3b26 | 1458:b002 | Intel      | 5 Series/3400 Series Chip... | 54    | ata_pii... | 85F57C764C |
| 10de:0054 | 1043:815a | Nvidia     | CK804 Serial ATA Controller  | 53    | sata_nv... | C92DC5D0CF |
| 8086:2820 | 1043:81ec | Intel      | 82801H (ICH8 Family) 4 po... | 53    | ata_pii... | A4A45B8A8B |
| 8086:2825 | 1043:81ec | Intel      | 82801HR/HO/HH (ICH8R/DO/D... | 53    | ata_pii... | A4A45B8A8B |
| 8086:27c0 | 1462:7592 | Intel      | NM10/ICH7 Family SATA Con... | 50    | ata_pii... | B0B570F44B |
| 8086:2921 | 1458:b002 | Intel      | 82801IB (ICH9) 2 port SAT... | 49    | ata_pii... | 54231260FF |
| 8086:27df | 1462:7592 | Intel      | 82801G (ICH7 Family) IDE ... | 47    | ata_pii... | B0B570F44B |
| 8086:27c0 | 8086:27c0 | Intel      | NM10/ICH7 Family SATA Con... | 46    | ata_pii... | 08DCF9AA49 |
| 10de:03f6 | 1462:7309 | Nvidia     | MCP61 SATA Controller        | 43    | sata_nv... | 11D0376265 |
| 1039:5513 | 1039:5513 | Silicon... | 5513 IDE Controller          | 41    | pata_si... | 6440D5167C |
| 1002:439c | 1043:8443 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 40    | pata_at... | 054E0BF393 |
| 8086:24db | 1043:80a6 | Intel      | 82801EB/ER (ICH5/ICH5R) I... | 38    | ata_pii... | 03602DBEA6 |
| 11ab:6121 | 1043:82e0 | Marvell... | 88SE6111/6121 SATA II / P... | 37    | pata_ma... | 28DFB478B7 |
| 8086:27df | 8086:27df | Intel      | 82801G (ICH7 Family) IDE ... | 37    | ata_pii... | 08DCF9AA49 |
| 10de:03ec | 1565:3407 | Nvidia     | MCP61 IDE                    | 36    | pata_am... | E327FDD558 |
| 10de:03f6 | 1565:5405 | Nvidia     | MCP61 SATA Controller        | 36    | sata_nv... | E327FDD558 |
| 8086:2850 | 17aa:20a6 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 36    | ata_pii... | 7F41843359 |
| 8086:2920 | 1458:b002 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 36    | ata_pii... | 048C1A4F90 |
| 10de:0448 | 1462:7369 | Nvidia     | MCP65 IDE                    | 34    | pata_am... | C46668413C |
| 8086:27c0 | 1565:5202 | Intel      | NM10/ICH7 Family SATA Con... | 34    | ata_pii... | A1DD312C27 |
| 8086:27df | 1565:3103 | Intel      | 82801G (ICH7 Family) IDE ... | 34    | ata_piix   | A1DD312C27 |
| 8086:2828 | 1025:011f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 34    | ata_pii... | C8EDDEAB31 |
| 1002:439c | 1565:3700 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 33    | pata_at... | C9FA6E4826 |
| 10de:045d | 1462:7369 | Nvidia     | MCP65 SATA Controller        | 33    | pata_ac... | C46668413C |
| 1106:0415 | 1849:0415 | VIA Tec... | VT6415 PATA IDE Host Cont... | 33    | pata_vi... | EC6555DA94 |
| 1002:439c | 1043:104c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 32    | pata_at... | 0051F69751 |
| 10de:036e | 1043:8239 | Nvidia     | MCP55 IDE                    | 32    | pata_am... | 4EA0694850 |
| 10de:037f | 1043:8239 | Nvidia     | MCP55 SATA Controller        | 32    | sata_nv... | 4EA0694850 |
| 10de:0759 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] IDE    | 31    | pata_am... | 88719BBDD6 |
| 197b:2368 | 1043:824f | JMicron... | JMB368 IDE controller        | 31    | pata_jm... | 6486BDE550 |
| 10de:0ad0 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] SAT... | 30    | pata_ac... | 2CAE195313 |
| 197b:2363 | 197b:2363 | JMicron... | JMB363 SATA/IDE Controller   | 30    | ahci       | FEAA959521 |
| 8086:1c00 | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 30    | ata_pii... | 7AF20CDF5A |
| 8086:1c08 | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 30    | ata_pii... | 7AF20CDF5A |
| 8086:3b20 | 1849:3b20 | Intel      | 5 Series/3400 Series Chip... | 30    | ata_pii... | 6CDC452D68 |
| 8086:3b26 | 1849:3b26 | Intel      | 5 Series/3400 Series Chip... | 30    | ata_pii... | 6CDC452D68 |
| 1b4b:917a | 1458:b000 | Marvell... | 88SE9172 SATA III 6Gb/s R... | 29    | pata_ac... | 706E1E0BAF |
| 8086:2850 | 1028:01f9 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 29    | ata_pii... | E5DE762918 |
| 197b:2361 | 1043:824f | JMicron... | JMB361 AHCI/IDE              | 28    | ahci       | 33F663A020 |
| 11ab:6121 | 11ab:6121 | Marvell... | 88SE6111/6121 SATA II / P... | 27    | pata_ma... | 150FE724DE |
| 197b:2368 | 197b:2368 | JMicron... | JMB368 IDE controller        | 27    | pata_jm... | 363DBD925B |
| 1b4b:91a3 | 1458:b000 | Marvell... | 88SE91A3 SATA-600 Controller | 27    | pata_ac... | 551193665F |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 229   | nvme       | 3A4D90A1C3 |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 207   | nvme       | 64913D4FAA |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 54    | nvme       | 5F7A70586E |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 53    | nvme       | 537D11B224 |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 39    | nvme       | C9E6C4517D |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/PC SN720 NV... | 28    | nvme       | 89F4BB64D7 |
| 1179:0113 | 1179:0001 | Toshiba... | BG3 NVMe SSD Controller      | 27    | nvme       | 52036BD95B |
| 1c5c:1527 | 1c5c:1527 | SK Hynix   | Non-Volatile memory contr... | 27    | nvme       | 75F82151FF |
| 1179:0115 | 1179:0001 | Toshiba... | XG4 NVMe SSD Controller      | 23    | nvme       | F41BD5BF5B |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 23    | nvme       | DDA26EE2AA |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | Non-Volatile memory contr... | 22    | nvme       | 79E53D2DB5 |
| 2646:5008 | 2646:5008 | Kingsto... | Non-Volatile memory contr... | 20    | nvme       | EA12327BDD |
| 15b7:5003 | 15b7:5003 | Sandisk    | WD Black 2018/PC SN520 NV... | 19    | nvme       | 24A04CA275 |
| 1179:010f | 1179:0001 | Toshiba... | NVMe Controller              | 12    | nvme       | 329795002B |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 12    | nvme       | 7CCAC31D71 |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 12    | nvme       | 123447177A |
| 1987:5007 | 1987:5007 | Phison ... | E7 NVMe Controller           | 11    | nvme       | EA54CD12AB |
| 126f:2263 | 126f:2263 | Silicon... | Non-Volatile memory contr... | 10    | nvme       | D999B85EFE |
| 14a4:2300 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 10    | nvme       | CAFA9C8DA5 |
| 1cc1:8201 | 1cc1:8201 |            | Non-Volatile memory contr... | 10    | nvme       | 21F5EEF1AB |
| 14a4:22f1 | 1b4b:1093 | Lite-On... | M8Pe Series NVMe SSD         | 9     | nvme       | 6707C4A123 |
| 126f:2262 | 126f:2262 | Silicon... | Non-Volatile memory contr... | 7     | nvme       | AAD0551E27 |
| 1987:5008 | 1987:5008 | Phison ... | NVMe Storage Controller      | 7     | nvme       | A6040FD25F |
| 1179:011a | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 5     | nvme       | DBB0FFDB96 |
| 17aa:0004 | 17aa:1004 | Lenovo     | Non-Volatile memory contr... | 5     | nvme       | 4B9BEB25C2 |
| 8086:0953 | 8086:370d | Intel      | PCIe Data Center SSD         | 5     | nvme       | 7D5ADE4D65 |
| c0a9:2263 | c0a9:2263 | Micron/... | Non-Volatile memory contr... | 5     | nvme       | BF4A9DEE07 |
| 10ec:5760 | 5760:10ec | Realtek... | Realtek Non-Volatile memo... | 4     | nvme       | 1EA306CF47 |
| 15b7:5001 | 1b4b:1093 | Sandisk    | WD Black NVMe SSD            | 4     | nvme       | B2B217C7BA |
| 15b7:5005 | 15b7:5005 | Sandisk    | Non-Volatile memory contr... | 4     | nvme       | C537E40686 |
| 10ec:5762 | 10ec:5762 | Realtek... | Realtek Non-Volatile memo... | 3     | nvme       | BC69AFD822 |
| 14a4:23f1 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 3     | nvme       | 05BB755A5A |
| 15b7:5004 | 15b7:5004 | Sandisk    | Non-Volatile memory contr... | 3     | nvme       | 1E82DEB58E |
| 17aa:0005 | 17aa:1005 | Lenovo     | Non-Volatile memory contr... | 3     | nvme       | 444D60D6DA |
| 1c5c:1283 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 3     | nvme       | 1675040CCD |
| 1c5c:1284 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 3     | nvme       | 4CC72409B5 |
| 106b:2001 | 106b:2001 | Apple      | S1X NVMe Controller          | 2     | nvme       | 195DAC413B |
| 144d:a806 | 144d:a801 | Samsung... | Electronics Non-Volatile ... | 2     | nvme       | 9D9D8E830B |
| 14a4:2100 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 2     | nvme       | 0594A8F475 |
| 14a4:2200 | 1b4b:1093 | Lite-On... | Lite-On Non-Volatile memo... | 2     | nvme       | 093C4071FD |
| 17aa:0003 | 17aa:1003 | Lenovo     | Non-Volatile memory contr... | 2     | nvme       | 6F9DCA6953 |
| 1c5c:1285 | 1c5c:0000 | SK Hynix   | Non-Volatile memory contr... | 2     | nvme       | F1ACFE989D |
| 1c5c:1504 | 0100:1093 | SK Hynix   | SC300 512GB M.2 2280 SATA... | 2     | nvme       | B186519684 |
| 2646:2262 | 2646:2262 | Kingsto... | Technology Company Non-Vo... | 2     | nvme       | 44204F310C |
| 8086:2522 | 8086:3806 | Intel      | NVMe SSD Optane Series Co... | 2     | nvme       | BDA8F46AD6 |
| 126f:2260 | 126f:2260 | Silicon... | Non-Volatile memory contr... | 1     | nvme       | A9E837C9EB |
| 14a4:21f1 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 1     | nvme       | BB13C77033 |
| 14a4:5100 | 14a4:5100 | Lite-On... | Non-Volatile memory contr... | 1     | nvme       | 766158C703 |
| 17aa:0006 | 17aa:1006 | Lenovo     | Non-Volatile memory contr... | 1     | nvme       | 8B3F86E523 |
| 1c5c:1627 | 1c5c:1627 | SK Hynix   | Non-Volatile memory contr... | 1     | nvme       | 8FB4429DD6 |
| 1cc4:2260 | 1cc4:2260 | Union M... | Non-Volatile memory contr... | 1     | nvme       | CE03C99485 |
| 1cc4:5008 | 1cc4:5008 | Union M... | Non-Volatile memory contr... | 1     | nvme       | 89D8981E8C |
| 8086:0953 | 8086:00e1 | Intel      | PCIe Data Center SSD         | 1     | nvme       | 019BFC3983 |
| 8086:0953 | 8086:3705 | Intel      | PCIe Data Center SSD         | 1     | nvme       | 3F982F3E86 |
| 8086:0a54 | 8086:4802 | Intel      | NVMe Datacenter SSD [3DNA... | 1     | nvme       | 093C4071FD |
| 8086:2522 | 8086:3802 | Intel      | NVMe SSD Optane Series Co... | 1     | nvme       | 9EE9F662A8 |
| 8086:2522 | 8086:3811 | Intel      | NVMe SSD Optane Series Co... | 1     | nvme       | AEAC4E0E68 |
| 8086:2700 | 8086:3900 | Intel      | Optane SSD 900P Series       | 1     | nvme       | 481A638E26 |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1106:3249 | 1106:3249 | VIA Tec... | VT6421 IDE/SATA Controller   | 33    | sata_via   | 6C7C70F0E2 |
| 8086:282a | 1028:0233 | Intel      | 82801 Mobile SATA Control... | 26    | ahci       | 1F49A84F1F |
| 8086:282a | 103c:1818 | Intel      | 82801 Mobile SATA Control... | 22    | ahci       | C865BDB72F |
| 8086:2822 | 1458:b005 | Intel      | SATA Controller [RAID mode]  | 18    | ahci       | 0BB045504D |
| 1000:005d | 1000:9363 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 16    | megarai... | 57FC9BDF47 |
| 8086:2822 | 1028:0420 | Intel      | SATA Controller [RAID mode]  | 14    | ahci       | 88DB43EE6F |
| 8086:282a | 1028:0493 | Intel      | 82801 Mobile SATA Control... | 14    | ahci       | CA6EFEBBD7 |
| 8086:2822 | 1043:8694 | Intel      | SATA Controller [RAID mode]  | 12    | ahci       | 7F1F084A4F |
| 8086:282a | 103c:84a6 | Intel      | 82801 Mobile SATA Control... | 12    | ahci       | 1A3504B63C |
| 8086:2822 | 103c:2a6f | Intel      | SATA Controller [RAID mode]  | 11    | ahci       | AA83F14B99 |
| 1095:3512 | 1095:6512 | Silicon... | SiI 3512 [SATALink/SATARa... | 10    | sata_sil   | 399101B245 |
| 8086:282a | 1028:0534 | Intel      | 82801 Mobile SATA Control... | 10    | ahci       | 8C26DF88EE |
| 1095:3114 | 1095:7114 | Silicon... | SiI 3114 [SATALink/SATARa... | 9     | sata_sil   | 9FF9E9007D |
| 8086:2822 | 103c:1309 | Intel      | SATA Controller [RAID mode]  | 9     | ahci       | 5A8BAD0B76 |
| 8086:2822 | 1458:b000 | Intel      | SATA Controller [RAID mode]  | 9     | ahci       | DF39CB5EE3 |
| 8086:282a | 1028:024f | Intel      | 82801 Mobile SATA Control... | 9     | ahci       | 5A8B3F34A3 |
| 8086:282a | 1028:040a | Intel      | 82801 Mobile SATA Control... | 9     | ahci       | E8A892A43C |
| 1002:4392 | 1025:0444 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 8     | ahci       | 99825EFDBE |
| 1106:3164 | 1106:3164 | VIA Tec... | VT6410 ATA133 RAID contro... | 8     | pata_vi... | 1012BD5A43 |
| 8086:282a | 1043:1fc0 | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | BBAF5C143F |
| 1000:0079 | 1000:9263 | LSI Log... | MegaRAID SAS 2108 [Libera... | 7     | megarai... | C60718AEF4 |
| 103c:323a | 103c:3245 | Hewlett... | Smart Array G6 controllers   | 7     | hpsa       | 6806624961 |
| 1095:3112 | 1095:6112 | Silicon... | SiI 3112 [SATALink/SATARa... | 7     | sata_sil   | 543960170E |
| 8086:2822 | 103c:2a9c | Intel      | SATA Controller [RAID mode]  | 7     | ahci       | B897AD01AD |
| 8086:282a | 1028:04a3 | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | 19E1CA5871 |
| 8086:282a | 1028:05ca | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | CA9C198099 |
| 8086:282a | 103c:18a5 | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | A978F2CA38 |
| 8086:282a | 17aa:380f | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | F3FC3BB5F8 |
| 1039:0180 | 1043:810e | Silicon... | RAID bus controller 180 S... | 6     | sata_sis   | BF1A9BA973 |
| 1095:3132 | 1095:7132 | Silicon... | SiI 3132 Serial ATA Raid ... | 6     | sata_sil24 | BFE6BFAFC7 |
| 1106:3149 | 1043:80ed | VIA Tec... | VIA VT6420 SATA RAID Cont... | 6     | sata_via   | E75F4538BC |
| 8086:2822 | 1028:0293 | Intel      | SATA Controller [RAID mode]  | 6     | ahci       | A72C60B73B |
| 8086:2822 | 1028:05a4 | Intel      | SATA Controller [RAID mode]  | 6     | ahci       | 24870345D1 |
| 8086:2822 | 1043:8534 | Intel      | SATA Controller [RAID mode]  | 6     | ahci       | 155E4D7633 |
| 8086:282a | 1025:1264 | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | F3941C8871 |
| 8086:282a | 1028:0535 | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | 95A631AAE1 |
| 8086:282a | 1028:05be | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | D8BE8B7344 |
| 8086:282a | 103c:8532 | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | 3839DE934E |
| 8086:282a | 17aa:3810 | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | 3FFC2E920B |
| 8086:282a | 17aa:3814 | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | 287B0F5C3B |
| 1002:4393 | 1043:84df | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 5     | ahci       | 747D9B1FD2 |
| 10b9:5287 | 1043:8056 | ULi Ele... | ULi 5287 SATA                | 5     | sata_uli   | 399101B245 |
| 1283:8212 | 1283:0001 | Integra... | IT8212 Dual channel ATA R... | 5     | pata_it... | 52229B9C49 |
| 8086:2822 | 1025:0389 | Intel      | SATA Controller [RAID mode]  | 5     | ahci       | A4DA822D7B |
| 8086:2822 | 1028:047e | Intel      | SATA Controller [RAID mode]  | 5     | ahci       | 166533E420 |
| 8086:2822 | 103c:130a | Intel      | SATA Controller [RAID mode]  | 5     | ahci       | 1D642553B7 |
| 8086:2822 | 1043:844d | Intel      | SATA Controller [RAID mode]  | 5     | ahci       | 0EEF21306D |
| 8086:2822 | 1043:84ca | Intel      | SATA Controller [RAID mode]  | 5     | ahci       | E85D169088 |
| 8086:2822 | 8086:514d | Intel      | SATA Controller [RAID mode]  | 5     | ahci       | 7409A9492F |
| 8086:2826 | 103c:1589 | Intel      | C600/X79 series chipset S... | 5     | ahci       | 2EEB0DCBEF |
| 8086:282a | 1028:024d | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 59050A5736 |
| 8086:282a | 1028:040b | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 80B359DC57 |
| 8086:282a | 1028:0492 | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 9C07EE4C86 |
| 8086:282a | 1028:053d | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 85B9549CFF |
| 8086:282a | 1028:05aa | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | A1B30D6B32 |
| 8086:282a | 103c:1894 | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 0A6F4AEE88 |
| 8086:282a | 103c:18fd | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | C56EC0A2C5 |
| 1000:005d | 15d9:0809 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 4     | megarai... | 6C96E4A591 |
| 1000:0060 | 1028:1f0c | LSI Log... | MegaRAID SAS 1078            | 4     | megarai... | ABCF5C7050 |
| 1000:0079 | 1028:1f17 | LSI Log... | MegaRAID SAS 2108 [Libera... | 4     | megarai... | F33CE0F316 |
| 1022:43bd | 1b21:1062 | AMD        | FCH RAID Controller          | 4     |            | 2ED5B5AFC5 |
| 103c:3239 | 103c:21c0 | Hewlett... | Smart Array Gen9 Controllers | 4     | hpsa       | C9D389B2A3 |
| 105a:3373 | 1043:80f5 | Promise... | PDC20378 (FastTrak 378/SA... | 4     | sata_pr... | E75F4538BC |
| 1095:0680 | 1095:3680 | Silicon... | PCI0680 Ultra ATA-133 Hos... | 4     | pata_si... | 8168BA11E3 |
| 1095:3114 | 1095:6114 | Silicon... | SiI 3114 [SATALink/SATARa... | 4     | sata_sil   | 34B91208C5 |
| 1283:8212 |           | Integra... | IT8212 Dual channel ATA R... | 4     | pata_it... | 3DD6E989DE |
| 8086:2822 | 1025:0427 | Intel      | SATA Controller [RAID mode]  | 4     | ahci       | AE38CF07EA |
| 8086:2822 | 1028:052c | Intel      | SATA Controller [RAID mode]  | 4     | ahci       | AEA3EEF94B |
| 8086:2822 | 1028:06d9 | Intel      | SATA Controller [RAID mode]  | 4     | ahci       | E96A090545 |
| 8086:282a | 1028:0494 | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 59093842A7 |
| 8086:282a | 1028:04a4 | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | AB60C016E0 |
| 8086:282a | 1028:0532 | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 2EF7F69991 |
| 8086:282a | 1028:053c | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 742C24B024 |
| 8086:282a | 1028:0572 | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | AE081E43AC |
| 8086:282a | 1028:05cb | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 613D54A9CE |
| 8086:282a | 1028:05de | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | F40C3D18FB |
| 8086:282a | 1028:062d | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 4926835893 |
| 8086:282a | 103c:84da | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | A8DE86DAD5 |
| 8086:282a | 1043:1501 | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 702F54B654 |
| 8086:282a | 1043:1b90 | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | C53DF5F083 |
| 1000:005d | 1028:1f47 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 3     | megarai... | D5DD49E570 |
| 1000:0073 | 1028:1f78 | LSI Log... | MegaRAID SAS 2008 [Falcon]   | 3     | megarai... | 4683A284A4 |
| 1002:4393 | 1002:4393 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 3     | ahci       | 04549B5B94 |
| 1002:4393 | 1849:4393 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 3     | ahci       | D2B8C394E0 |
| 1022:7916 | 1022:7901 | AMD        | RS690 PCI to PCI Bridge (... | 3     | ahci       | 2ED5B5AFC5 |
| 1039:0180 | 1458:b003 | Silicon... | RAID bus controller 180 S... | 3     | sata_sis   | DB5DEDA228 |
| 103c:323b | 103c:3354 | Hewlett... | Smart Array Gen8 Controllers | 3     | hpsa       | 07278BAD4B |
| 1095:3124 | 1095:7124 | Silicon... | SiI 3124 PCI-X Serial ATA... | 3     | sata_sil24 | CFC42EAC60 |
| 1106:3149 | 1462:7104 | VIA Tec... | VIA VT6420 SATA RAID Cont... | 3     | sata_vi... | C433E6081D |
| 8086:2682 | 103c:1307 | Intel      | 631xESB/632xESB SATA RAID... | 3     | ahci       | E545027D1D |
| 8086:27c3 | 103c:280c | Intel      | 82801GR/GDH (ICH7R/ICH7DH... | 3     | ahci       | FA9C3D044F |
| 8086:2822 | 1025:024c | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | A2DBF52E17 |
| 8086:2822 | 1025:0589 | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | 838EE46987 |
| 8086:2822 | 1028:01db | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | 7FAC0EC567 |
| 8086:2822 | 1028:026e | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | CC88E139CC |
| 8086:2822 | 1028:05d7 | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | 2272E1FA1D |
| 8086:2822 | 1028:064c | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | E1BABF19AD |
| 8086:2822 | 103c:1308 | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | 1787C13656 |
| 8086:2826 | 1028:0617 | Intel      | C600/X79 series chipset S... | 3     | ahci       | 3B5017848A |
| 8086:2826 | 103c:158a | Intel      | C600/X79 series chipset S... | 3     | ahci       | 2AB82BCF03 |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:16be | 1025:0647 | Broadco... | BCM57765/57785 MS Card Re... | 212   |            | E67DFC255A |
| 14e4:16bf | 1025:0647 | Broadco... | BCM57765/57785 xD-Picture... | 212   |            | E67DFC255A |
| 8086:2576 |           | Intel      | 82865G/PE/P Processor to ... | 157   |            | E3D9D5BAE8 |
| 8086:d150 |           | Intel      | Core Processor QPI Link      | 157   |            | B39AC90CA0 |
| 8086:d151 |           | Intel      | Core Processor QPI Routin... | 157   |            | B39AC90CA0 |
| 8086:d158 |           | Intel      | Core Processor Miscellane... | 145   |            | B39AC90CA0 |
| 197b:2382 | 1043:1a07 | JMicron... | SD/MMC Host Controller       | 116   | sdhci_pci  | F47F34752E |
| 197b:2383 | 1043:1a07 | JMicron... | MS Host Controller           | 98    | jmb38x_ms  | F47F34752E |
| 197b:2384 | 1043:1a07 | JMicron... | xD Host Controller           | 97    |            | F47F34752E |
| 8086:d156 |           | Intel      | Core Processor Semaphore ... | 89    |            | B39AC90CA0 |
| 8086:d155 |           | Intel      | Core Processor System Man... | 88    |            | B39AC90CA0 |
| 8086:d157 |           | Intel      | Core Processor System Con... | 88    |            | B39AC90CA0 |
| 14e4:16be | 1025:0504 | Broadco... | BCM57765/57785 MS Card Re... | 86    |            | 8579BA1B16 |
| 14e4:16bf | 1025:0504 | Broadco... | BCM57765/57785 xD-Picture... | 86    |            | 8579BA1B16 |
| 8086:2f6e |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 68    |            | A8F2B39356 |
| 8086:2f6f |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 68    |            | A8F2B39356 |
| 8086:2f88 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 68    |            | A8F2B39356 |
| 8086:2f8a |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 68    |            | A8F2B39356 |
| 8086:2fae |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 68    |            | A8F2B39356 |
| 8086:2faf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 68    |            | A8F2B39356 |
| 8086:2fb8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 68    |            | A8F2B39356 |
| 8086:2fb9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 68    |            | A8F2B39356 |
| 8086:2fba |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 68    |            | A8F2B39356 |
| 8086:2fbb |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 68    |            | A8F2B39356 |
| 8086:2fbe |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 68    |            | A8F2B39356 |
| 8086:2fbf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 68    |            | A8F2B39356 |
| 8086:2ff8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 68    |            | A8F2B39356 |
| 8086:2ff9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 68    |            | A8F2B39356 |
| 8086:1911 | 1458:5000 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 62    |            | 9A41C725F3 |
| 8086:2f68 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 60    |            | A8F2B39356 |
| 8086:2fd0 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 60    | hswep_u... | A8F2B39356 |
| 8086:2f1d | 8086:2f1d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | A8F2B39356 |
| 8086:2f1e | 8086:2f1e | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | A8F2B39356 |
| 8086:2f1f | 8086:2f1f | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | A8F2B39356 |
| 8086:2f71 | 8086:2f71 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | A8F2B39356 |
| 8086:2f98 | 8086:2f98 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | A8F2B39356 |
| 8086:2f99 | 8086:2f99 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | A8F2B39356 |
| 8086:2f9a | 8086:2f9a | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | A8F2B39356 |
| 8086:2f9c | 8086:2f9c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | A8F2B39356 |
| 8086:2fa0 | 8086:2fa0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    | sb_edac    | A8F2B39356 |
| 8086:2fa8 | 8086:2fa8 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | A8F2B39356 |
| 8086:2faa | 8086:2faa | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | A8F2B39356 |
| 8086:2fab | 8086:2fab | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | A8F2B39356 |
| 8086:2fb0 | 8086:2fb0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    | hswep_u... | A8F2B39356 |
| 8086:2fb1 | 8086:2fb1 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    | hswep_u... | A8F2B39356 |
| 8086:2fb2 | 8086:2fb2 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | A8F2B39356 |
| 8086:2fb3 | 8086:2fb3 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | A8F2B39356 |
| 8086:2fc0 | 8086:2fc0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    | hswep_u... | A8F2B39356 |
| 8086:d155 | 0043:0083 | Intel      | Core Processor System Man... | 57    |            | F048270617 |
| 8086:d156 | 0043:0083 | Intel      | Core Processor Semaphore ... | 57    |            | F048270617 |
| 8086:d157 | 0043:0083 | Intel      | Core Processor System Con... | 57    |            | F048270617 |
| 1180:e822 | 17aa:2133 | Ricoh      | MMC/SD Host Controller       | 55    | sdhci_pci  | DA5E944C6C |
| 8086:2f81 | 8086:2f81 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 54    |            | A8F2B39356 |
| 8086:2fac | 8086:2fac | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 54    |            | A8F2B39356 |
| 8086:2fad | 8086:2fad | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 54    |            | A8F2B39356 |
| 8086:2fb4 | 8086:2fb4 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 54    | hswep_u... | A8F2B39356 |
| 8086:2fb5 | 8086:2fb5 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 54    | hswep_u... | A8F2B39356 |
| 8086:2fb6 | 8086:2fb6 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 54    |            | A8F2B39356 |
| 8086:2fb7 | 8086:2fb7 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 54    |            | A8F2B39356 |
| 8086:2fe0 | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 54    |            | A8F2B39356 |
| 8086:2fe1 | 8086:2fe1 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 54    |            | A8F2B39356 |
| 8086:2fe2 | 8086:2fe2 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 54    |            | A8F2B39356 |
| 8086:2fe3 | 8086:2fe3 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 54    |            | A8F2B39356 |
| 8086:2ffc | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 54    |            | A8F2B39356 |
| 8086:2ffd | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 54    |            | A8F2B39356 |
| 8086:2ffe | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 54    |            | A8F2B39356 |
| 1180:0592 | 17aa:20ca | Ricoh      | R5C592 Memory Stick Bus H... | 51    | r592       | A23E000798 |
| 1180:0852 | 17aa:20cb | Ricoh      | xD-Picture Card Controller   | 51    | r852       | A23E000798 |
| 8086:1513 | 2222:1111 | Intel      | CV82524 Thunderbolt Contr... | 51    | pcieport   | 16BDB52C40 |
| 8086:2016 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 47    |            | 8E73F804F5 |
| 8086:2018 | 8086:0000 | Intel      | Sky Lake-E M2PCI Registers   | 47    |            | 8E73F804F5 |
| 8086:2025 |           | Intel      | Sky Lake-E RAS               | 47    |            | 8E73F804F5 |
| 8086:2035 |           | Intel      | Sky Lake-E RAS Configurat... | 47    |            | 8E73F804F5 |
| 8086:2040 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 47    |            | 8E73F804F5 |
| 8086:2041 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 47    |            | 8E73F804F5 |
| 8086:2042 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 47    | skx_uncore | 8E73F804F5 |
| 8086:2043 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 47    |            | 8E73F804F5 |
| 8086:2044 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 47    |            | 8E73F804F5 |
| 8086:2045 | 8086:0000 | Intel      | Sky Lake-E LM Channel 1      | 47    |            | 8E73F804F5 |
| 8086:2046 | 8086:0000 | Intel      | Sky Lake-E LMS Channel 1     | 47    | skx_uncore | 8E73F804F5 |
| 8086:2047 | 8086:0000 | Intel      | Sky Lake-E LMDP Channel 1    | 47    |            | 8E73F804F5 |
| 8086:2048 | 8086:0000 | Intel      | Sky Lake-E DECS Channel 2    | 47    |            | 8E73F804F5 |
| 8086:2049 | 8086:0000 | Intel      | Sky Lake-E LM Channel 2      | 47    |            | 8E73F804F5 |
| 8086:204a | 8086:0000 | Intel      | Sky Lake-E LMS Channel 2     | 47    | skx_uncore | 8E73F804F5 |
| 8086:204b | 8086:0000 | Intel      | Sky Lake-E LMDP Channel 2    | 47    |            | 8E73F804F5 |
| 8086:204e | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 47    | skx_uncore | 8E73F804F5 |
| 8086:2054 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 47    |            | 8E73F804F5 |
| 8086:2055 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 47    |            | 8E73F804F5 |
| 8086:2056 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 47    |            | 8E73F804F5 |
| 8086:2057 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 47    |            | 8E73F804F5 |
| 8086:2066 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 47    | skx_uncore | 8E73F804F5 |
| 8086:2080 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 47    |            | 8E73F804F5 |
| 8086:2081 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 47    |            | 8E73F804F5 |
| 8086:2082 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 47    |            | 8E73F804F5 |
| 8086:2083 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 47    |            | 8E73F804F5 |
| 8086:2084 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 47    |            | 8E73F804F5 |
| 8086:2085 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 47    |            | 8E73F804F5 |
| 8086:2086 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 47    |            | 8E73F804F5 |
| 8086:208d | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 47    |            | 8E73F804F5 |
| 8086:208e | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 47    |            | 8E73F804F5 |

### Tv card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1131:7130 | 5ace:5050 | Philips... | SAA7130 Video Broadcast D... | 18    | saa7134    | 88E3DD8AEA |
| 1131:7133 | 1461:a11b | Philips... | SAA7131/SAA7133/SAA7135 V... | 17    | saa7134    | 808511C33A |
| 1131:7133 | 5ace:5090 | Philips... | SAA7131/SAA7133/SAA7135 V... | 17    | saa7134    | E1C9E92E22 |
| 109e:036e |           | Brooktree  | Bt878 Video Capture          | 15    | bttv       | BA9CCBD3A5 |
| 1131:7134 | 5ace:5070 | Philips... | SAA7134/SAA7135HL Video B... | 14    | saa7134    | CE5C925F91 |
| 1131:7134 | 1461:9715 | Philips... | SAA7134/SAA7135HL Video B... | 12    | saa7134    | 04D993137A |
| 1131:7134 | 185b:c200 | Philips... | SAA7134/SAA7135HL Video B... | 12    | saa7134    | 3F25A03C59 |
| 1131:7133 | 1461:4255 | Philips... | SAA7131/SAA7133/SAA7135 V... | 11    | saa7134    | E9B2CE4750 |
| 1131:7133 | 0000:4091 | Philips... | SAA7131/SAA7133/SAA7135 V... | 9     | saa7134    | FA070462FC |
| 1131:7130 | 1131:0000 | Philips... | SAA7130 Video Broadcast D... | 8     | saa7134    | D7CC0778FC |
| 1131:7130 | 1461:2115 | Philips... | SAA7130 Video Broadcast D... | 8     | saa7134    | 0528AB77BE |
| 1131:7133 | 185b:c100 | Philips... | SAA7131/SAA7133/SAA7135 V... | 8     | saa7134    | 5FE1529C55 |
| 1131:7133 | 5ace:7290 | Philips... | SAA7131/SAA7133/SAA7135 V... | 8     | saa7134    | 40DB916050 |
| 109e:036e | 1461:0003 | Brooktree  | Bt878 Video Capture          | 7     | bttv       | EBF0DCD676 |
| 1131:7133 | 1461:0155 | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 331F603CE2 |
| 1131:7133 | 1461:a14b | Philips... | SAA7131/SAA7133/SAA7135 V... | 6     | saa7134    | 2EF428DCCE |
| 1131:7133 | 5ace:6090 | Philips... | SAA7131/SAA7133/SAA7135 V... | 6     | saa7134    | 30E31AE3DF |
| 1131:7133 | 5ace:7595 | Philips... | SAA7131/SAA7133/SAA7135 V... | 6     | saa7134    | 04549B5B94 |
| 1131:7134 | 5ace:6070 | Philips... | SAA7134/SAA7135HL Video B... | 6     | saa7134    | 12E892C5EB |
| 4444:0016 | 1461:c439 | Interne... | iTVC16 (CX23416) Video De... | 6     | ivtv       | F6D05FF577 |
| 1131:7130 | 1461:a11b | Philips... | SAA7130 Video Broadcast D... | 5     | saa7134    | B29679845C |
| 1131:7133 | 1461:0055 | Philips... | SAA7131/SAA7133/SAA7135 V... | 5     | saa7134    | 867282B14C |
| 1131:7133 | 1461:a11a | Philips... | SAA7131/SAA7133/SAA7135 V... | 5     | saa7134    | 6B668249FB |
| 1131:7133 | 1461:f11d | Philips... | SAA7131/SAA7133/SAA7135 V... | 5     | saa7134    | 8C6F161892 |
| 1131:7133 | 16be:000d | Philips... | SAA7131/SAA7133/SAA7135 V... | 5     | saa7134    | ECBFA57012 |
| 1131:7133 | 5ace:6193 | Philips... | SAA7131/SAA7133/SAA7135 V... | 5     | saa7134    | 2004961715 |
| 1131:7134 | 5168:0138 | Philips... | SAA7134/SAA7135HL Video B... | 5     | saa7134    | 45AE73B2A9 |
| 14f1:8800 |           | Conexan... | CX23880/1/2/3 PCI Video a... | 5     | cx8800     | FA7FD99F2E |
| 109e:036e | 0070:13eb | Brooktree  | Bt878 Video Capture          | 4     | bttv       | AAECFA3E56 |
| 1131:7130 | 0000:4051 | Philips... | SAA7130 Video Broadcast D... | 4     | saa7134    | 0B3E433CCC |
| 1131:7130 | 1461:2108 | Philips... | SAA7130 Video Broadcast D... | 4     | saa7134    | 61EF761A70 |
| 1131:7130 | 1461:a115 | Philips... | SAA7130 Video Broadcast D... | 4     | saa7134    | 74B6562CCD |
| 1131:7130 | 1461:a11a | Philips... | SAA7130 Video Broadcast D... | 4     | saa7134    | 0200BA924B |
| 1131:7133 | 1043:4845 | Philips... | SAA7131/SAA7133/SAA7135 V... | 4     | saa7134    | 1573DF6188 |
| 1131:7133 | 11bd:002e | Philips... | SAA7131/SAA7133/SAA7135 V... | 4     | saa7134    | CF053FB4E1 |
| 1131:7133 | 5ace:7190 | Philips... | SAA7131/SAA7133/SAA7135 V... | 4     | saa7134    | C1BD1568DC |
| 1131:7134 | 0000:4071 | Philips... | SAA7134/SAA7135HL Video B... | 4     | saa7134    | D096BDC1A3 |
| 1131:7134 | 4e42:0138 | Philips... | SAA7134/SAA7135HL Video B... | 4     | saa7134    | AEAB86C587 |
| 1131:7134 | 5ace:6072 | Philips... | SAA7134/SAA7135HL Video B... | 4     | saa7134    | 254B040C92 |
| 11de:6057 | 1031:7efe | Zoran      | ZR36057PQC Video cutting ... | 4     | zr36067    | 69F477A509 |
| 14f1:8800 | 107d:6611 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     | cx8800     | EBD8A5801D |
| 14f1:8800 | b200:4200 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     | cx8800     | 6933983FAB |
| 14f1:8802 | b200:4200 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     | cx8802     | 6933983FAB |
| 109e:036e | 107d:6609 | Brooktree  | Bt878 Video Capture          | 3     | bttv       | 4A6B13BAEA |
| 1131:7133 | 0000:5071 | Philips... | SAA7131/SAA7133/SAA7135 V... | 3     | saa7134    | 8084584F5B |
| 1131:7133 | 1461:a836 | Philips... | SAA7131/SAA7133/SAA7135 V... | 3     | saa7134    | 1CE26C391A |
| 1131:7133 | 16be:0010 | Philips... | SAA7131/SAA7133/SAA7135 V... | 3     | saa7134    | FF0A7B1FC8 |
| 1131:7133 | 5ace:5030 | Philips... | SAA7131/SAA7133/SAA7135 V... | 3     | saa7134    | 5F1C1865D9 |
| 1131:7133 | 5ace:6091 | Philips... | SAA7131/SAA7133/SAA7135 V... | 3     | saa7134    | 732F07E043 |
| 1131:7133 | 5ace:6092 | Philips... | SAA7131/SAA7133/SAA7135 V... | 3     | saa7134    | 97CDBE1C08 |
| 1131:7133 | 5ace:6190 | Philips... | SAA7131/SAA7133/SAA7135 V... | 3     | saa7134    | E3708C9C07 |
| 14f1:5b7a | 0070:7400 | Conexan... | CX23418 Single-Chip MPEG-... | 3     | cx18       | 86F900F93D |
| 14f1:8800 | 0070:9002 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     | cx8800     | 8168BA11E3 |
| 14f1:8800 | 185b:e000 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     | cx8800     | 5B85C2F248 |
| 14f1:8800 | d420:9022 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     | cx8800     | B8ECD9CD1E |
| 14f1:8801 | 185b:e000 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     | cx88_alsa  | 5B85C2F248 |
| 14f1:8802 | d420:9022 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     | cx8802     | B8ECD9CD1E |
| 14f1:8852 | 8000:3034 | Conexan... | CX23885 PCI Video and Aud... | 3     | cx23885    | 5DDB85C708 |
| 4444:0016 | 0070:8801 | Interne... | iTVC16 (CX23416) Video De... | 3     | ivtv       | 33687A527A |
| 109e:036e | 11bd:0012 | Brooktree  | Bt878 Video Capture          | 2     | bttv       | AB36F565A4 |
| 1131:7130 | 1461:a10a | Philips... | SAA7130 Video Broadcast D... | 2     | saa7134    | 13B9B4E6E9 |
| 1131:7130 | 5168:0138 | Philips... | SAA7130 Video Broadcast D... | 2     | saa7134    | 21AB0E482F |
| 1131:7133 | 0000:507b | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | 1907FA3249 |
| 1131:7133 | 0070:6701 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | CD1B20C35D |
| 1131:7133 | 0458:6008 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | 60C13AD654 |
| 1131:7133 | 1131:0000 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | 30B8A56200 |
| 1131:7133 | 1461:a70a | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | 88CFA65098 |
| 1131:7133 | 1461:f636 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | E814DA247A |
| 1131:7133 | 1461:f936 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | 45F1021882 |
| 1131:7133 | 17de:7136 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | 249D4C1A3F |
| 1131:7133 | 5ace:6093 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | 550810BC29 |
| 1131:7133 | 5ace:6191 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | 4019627ACC |
| 1131:7133 | 5ace:7090 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | DA43CB5805 |
| 1131:7134 | 1131:0000 | Philips... | SAA7134/SAA7135HL Video B... | 2     | saa7134    | 785DD593F5 |
| 1131:7134 | 1131:233e | Philips... | SAA7134/SAA7135HL Video B... | 2     | saa7134    | 835B504D5C |
| 1131:7134 | 1461:a70a | Philips... | SAA7134/SAA7135HL Video B... | 2     | saa7134    | DC6ED89D31 |
| 1131:7134 | 16be:5000 | Philips... | SAA7134/SAA7135HL Video B... | 2     | saa7134    | 7D2057C89D |
| 14f1:5b7a | 0070:740c | Conexan... | CX23418 Single-Chip MPEG-... | 2     | cx18       | 9B75A42A1E |
| 14f1:5b7a | 1179:0110 | Conexan... | CX23418 Single-Chip MPEG-... | 2     | cx18       | 3E0ED41BC7 |
| 14f1:8800 | 17de:08b2 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | 5E5236F775 |
| 14f1:8800 | 1822:0023 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | AB36F565A4 |
| 14f1:8800 | b022:3022 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | AA10363A06 |
| 14f1:8800 | b033:3033 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | 1C7923E9B3 |
| 14f1:8800 | d460:9022 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | FE55ACD2A2 |
| 14f1:8800 | ffff:ffff | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | 6C9247C5EB |
| 14f1:8801 | ffff:ffff | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx88_alsa  | 6C9247C5EB |
| 14f1:8802 | 17de:08b2 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8802     | 5E5236F775 |
| 14f1:8802 | 1822:0023 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8802     | AB36F565A4 |
| 14f1:8802 | b022:3022 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8802     | AA10363A06 |
| 14f1:8802 | b033:3033 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8802     | 1C7923E9B3 |
| 14f1:8802 | d460:9022 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8802     | FE55ACD2A2 |
| 14f1:8852 | 0070:6a28 | Conexan... | CX23885 PCI Video and Aud... | 2     | cx23885    | 09CC6BAB56 |
| 14f1:8852 | 0070:6b28 | Conexan... | CX23885 PCI Video and Aud... | 2     | cx23885    | 09CC6BAB56 |
| 14f1:8852 | 1461:d939 | Conexan... | CX23885 PCI Video and Aud... | 2     | cx23885    | 8E5499B7A2 |
| 14f1:8852 | 14f1:8502 | Conexan... | CX23885 PCI Video and Aud... | 2     | cx23885    | 55AA6443CD |
| 14f1:8852 | 4254:9580 | Conexan... | CX23885 PCI Video and Aud... | 2     | cx23885    | 9057FD4986 |
| 14f1:8852 | d470:9022 | Conexan... | CX23885 PCI Video and Aud... | 2     | cx23885    | 78D2C49977 |
| 14f1:8880 | 0070:c108 | Conexan... | CX23887/8 PCIe Broadcast ... | 2     | cx23885    | 03A71DD3EB |
| 14f1:8880 | 1461:e139 | Conexan... | CX23887/8 PCIe Broadcast ... | 2     | cx23885    | 7999E0452A |
| 14f1:8880 | 5654:2390 | Conexan... | CX23887/8 PCIe Broadcast ... | 2     | cx23885    | AC49C705CB |

### Unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:31a2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_i... | 55981AF24A |
| 8086:5aa2 | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | F8913A087C |
| 8086:5aa2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | 6663E08482 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27c8 | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 570   | uhci_hcd   | FAC5E9FEFA |
| 8086:27c9 | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 570   | uhci_hcd   | FAC5E9FEFA |
| 8086:27ca | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 570   | uhci_hcd   | FAC5E9FEFA |
| 8086:27cb | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 570   | uhci_hcd   | FAC5E9FEFA |
| 8086:27cc | 1043:8179 | Intel      | NM10/ICH7 Family USB2 EHC... | 558   | ehci_hc... | FAC5E9FEFA |
| 1002:4396 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 546   | ehci_hc... | 394C81B911 |
| 1002:4397 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 546   | ohci_hc... | 394C81B911 |
| 1002:4399 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 546   | ohci_hc... | 394C81B911 |
| 1b21:1042 | 1043:8488 | ASMedia... | ASM1042 SuperSpeed USB Ho... | 531   | xhci_pci   | 6A60A724F9 |
| 1002:4396 | 1002:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 504   | ehci_hc... | 5B95BD72C4 |
| 8086:1c26 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 469   | ehci_hc... | 66A5EA0BE5 |
| 8086:1c2d | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 469   | ehci_hc... | 66A5EA0BE5 |
| 8086:27c8 | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 405   | uhci_hcd   | DD0FCDE6C7 |
| 8086:27c9 | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 405   | uhci_hcd   | DD0FCDE6C7 |
| 8086:27ca | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 405   | uhci_hcd   | DD0FCDE6C7 |
| 8086:27cb | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 405   | uhci_hcd   | DD0FCDE6C7 |
| 8086:27cc | 1458:5006 | Intel      | NM10/ICH7 Family USB2 EHC... | 405   | ehci_hc... | DD0FCDE6C7 |
| 1002:4397 | 1002:4397 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 403   | ohci_hc... | 6A60A724F9 |
| 8086:1e26 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 351   | ehci_hc... | 570B707FFB |
| 8086:1e2d | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 351   | ehci_hc... | 570B707FFB |
| 8086:1e31 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 349   | xhci_pci   | 570B707FFB |
| 1002:4396 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 339   | ehci_hc... | D569843A2D |
| 1002:4397 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 339   | ohci_hc... | D569843A2D |
| 1002:4398 | 1043:8389 | AMD        | SB7x0 USB OHCI1 Controller   | 338   | ohci_hc... | D569843A2D |
| 1002:4399 | 1002:4399 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 338   | ohci_hc... | 6A60A724F9 |
| 1002:4399 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 338   | ohci_hc... | D569843A2D |
| 8086:8c26 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 316   | ehci_hc... | F6CCF2BBA6 |
| 8086:8c31 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 313   | xhci_pci   | F6CCF2BBA6 |
| 8086:8c2d | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 312   | ehci_hc... | F6CCF2BBA6 |
| 1002:4398 | 1458:5004 | AMD        | SB7x0 USB OHCI1 Controller   | 301   | ohci_hc... | 8EAEF3C906 |
| 8086:1c26 | 1458:5006 | Intel      | 6 Series/C200 Series Chip... | 290   | ehci_hc... | E4C2A9F4EB |
| 8086:1c2d | 1458:5006 | Intel      | 6 Series/C200 Series Chip... | 290   | ehci_hc... | E4C2A9F4EB |
| 8086:3a34 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 267   | uhci_hcd   | B481805845 |
| 8086:3a35 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 267   | uhci_hcd   | B481805845 |
| 8086:3a36 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 267   | uhci_hcd   | B481805845 |
| 8086:3a37 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 267   | uhci_hcd   | B481805845 |
| 8086:3a38 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 267   | uhci_hcd   | B481805845 |
| 8086:3a39 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 267   | uhci_hcd   | B481805845 |
| 8086:3a3a | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 267   | ehci_hc... | B481805845 |
| 8086:3a3c | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 267   | ehci_hc... | B481805845 |
| 8086:1e26 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 262   | ehci_hc... | 891002E8F2 |
| 8086:1e2d | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 262   | ehci_hc... | 891002E8F2 |
| 8086:1e31 | 17aa:3977 | Intel      | 7 Series/C210 Series Chip... | 255   | xhci_pci   | 891002E8F2 |
| 1b6f:7023 | 1458:5007 | Etron T... | EJ168 USB 3.0 Host Contro... | 252   | xhci_pci   | A9ED28807E |
| 8086:27c8 | 1849:27c8 | Intel      | NM10/ICH7 Family USB UHCI... | 249   | uhci_hcd   | 5F6E1A3B61 |
| 8086:27c9 | 1849:27c9 | Intel      | NM10/ICH7 Family USB UHCI... | 249   | uhci_hcd   | 5F6E1A3B61 |
| 8086:27ca | 1849:27ca | Intel      | NM10/ICH7 Family USB UHCI... | 249   | uhci_hcd   | 5F6E1A3B61 |
| 8086:27cb | 1849:27cb | Intel      | NM10/ICH7 Family USB UHCI... | 249   | uhci_hcd   | 5F6E1A3B61 |
| 8086:27cc | 1849:27cc | Intel      | NM10/ICH7 Family USB2 EHC... | 249   | ehci_hc... | 5F6E1A3B61 |
| 8086:1e26 | 1458:5006 | Intel      | 7 Series/C216 Chipset Fam... | 245   | ehci_hc... | 8C4047657D |
| 8086:1e2d | 1458:5006 | Intel      | 7 Series/C216 Chipset Fam... | 245   | ehci_hc... | 8C4047657D |
| 1b21:1142 | 1043:85bf | ASMedia... | ASM1042A USB 3.0 Host Con... | 241   | xhci_pci   | C0B50F9AE1 |
| 8086:1e31 | 1458:5007 | Intel      | 7 Series/C210 Series Chip... | 229   | xhci_pci   | 8C4047657D |
| 1002:4396 | 1849:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 222   | ehci_hc... | 85F1B83B30 |
| 1002:4397 | 1849:4397 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 222   | ohci_hc... | 85F1B83B30 |
| 1002:4399 | 1849:4399 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 222   | ohci_hc... | 85F1B83B30 |
| 8086:2934 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 211   | uhci_hcd   | 29B7777E42 |
| 8086:2935 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 211   | uhci_hcd   | 29B7777E42 |
| 8086:2936 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 211   | uhci_hcd   | 29B7777E42 |
| 8086:2937 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 211   | uhci_hcd   | 29B7777E42 |
| 8086:2938 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 211   | uhci_hcd   | 29B7777E42 |
| 8086:2939 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 211   | uhci_hcd   | 29B7777E42 |
| 8086:293a | 1043:8277 | Intel      | 82801I (ICH9 Family) USB2... | 211   | ehci_hc... | 29B7777E42 |
| 8086:293c | 1043:8277 | Intel      | 82801I (ICH9 Family) USB2... | 211   | ehci_hc... | 29B7777E42 |
| 8086:a12f | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 197   | xhci_pci   | 99614383EB |
| 10de:03f1 | 1849:03f1 | Nvidia     | MCP61 USB 1.1 Controller     | 194   | ohci_hc... | 816FE60D2D |
| 10de:03f2 | 1849:03f2 | Nvidia     | MCP61 USB 2.0 Controller     | 194   | ehci_hc... | 816FE60D2D |
| 1022:7807 | 1458:5004 | AMD        | FCH USB OHCI Controller      | 185   | ohci_hc... | 8226B90793 |
| 1022:7808 | 1458:5004 | AMD        | FCH USB EHCI Controller      | 185   | ehci_hc... | 8226B90793 |
| 1022:7809 | 1458:5004 | AMD        | FCH USB OHCI Controller      | 182   | ohci_hc... | 8226B90793 |
| 8086:8c26 | 1458:5006 | Intel      | 8 Series/C220 Series Chip... | 179   | ehci_hc... | DD4DA32934 |
| 8086:8c2d | 1458:5006 | Intel      | 8 Series/C220 Series Chip... | 179   | ehci_hc... | DD4DA32934 |
| 8086:8c31 | 1458:5007 | Intel      | 8 Series/C220 Series Chip... | 179   | xhci_pci   | DD4DA32934 |
| 1106:3038 | 1106:3038 | VIA Tec... | VT82xx/62xx UHCI USB 1.1 ... | 176   | uhci_hcd   | 85F1B83B30 |
| 1106:3104 | 1106:3104 | VIA Tec... | USB 2.0                      | 170   | ehci_hc... | 85F1B83B30 |
| 8086:27c8 | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 170   | uhci_hcd   | 6A0513EC8D |
| 8086:27c9 | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 170   | uhci_hcd   | 6A0513EC8D |
| 8086:27ca | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 170   | uhci_hcd   | 6A0513EC8D |
| 8086:27cc | 1043:83ad | Intel      | NM10/ICH7 Family USB2 EHC... | 170   | ehci_hc... | 6A0513EC8D |
| 8086:1c26 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 164   | ehci_hc... | A7618091FB |
| 8086:1c2d | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 164   | ehci_hc... | A7618091FB |
| 8086:9d2f | 1043:201f | Intel      | Sunrise Point-LP USB 3.0 ... | 162   | xhci_hcd   | B6B40DE397 |
| 8086:27cb | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 155   | uhci_hcd   | 6A0513EC8D |
| 1b21:1042 | 1043:1059 | ASMedia... | ASM1042 SuperSpeed USB Ho... | 154   | xhci_pci   | 826F5492EB |
| 1033:0194 | 1043:8413 | NEC Com... | uPD720200 USB 3.0 Host Co... | 151   | xhci_hcd   | B481805845 |
| 8086:3a34 | 1458:5004 | Intel      | 82801JI (ICH10 Family) US... | 142   | uhci_hcd   | F655F180AC |
| 8086:3a35 | 1458:5004 | Intel      | 82801JI (ICH10 Family) US... | 142   | uhci_hcd   | F655F180AC |
| 8086:3a36 | 1458:5004 | Intel      | 82801JI (ICH10 Family) US... | 142   | uhci_hcd   | F655F180AC |
| 8086:3a37 | 1458:5004 | Intel      | 82801JI (ICH10 Family) US... | 142   | uhci_hcd   | F655F180AC |
| 8086:3a38 | 1458:5004 | Intel      | 82801JI (ICH10 Family) US... | 142   | uhci_hcd   | F655F180AC |
| 8086:3a39 | 1458:5004 | Intel      | 82801JI (ICH10 Family) US... | 142   | uhci_hcd   | F655F180AC |
| 8086:3a3a | 1458:5006 | Intel      | 82801JI (ICH10 Family) US... | 142   | ehci_hc... | F655F180AC |
| 8086:3a3c | 1458:5006 | Intel      | 82801JI (ICH10 Family) US... | 142   | ehci_hc... | F655F180AC |
| 1106:3483 | 1458:5007 | VIA Tec... | VL805 USB 3.0 Host Contro... | 133   | xhci_pci   | 394C81B911 |
| 8086:22b5 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 133   | xhci_hcd   | 6053E60588 |
| 1002:4399 | 1002:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 132   | ohci_hc... | 5B95BD72C4 |
| 1022:43bb | 1b21:1142 | AMD        | 300 Series Chipset USB 3.... | 131   | xhci_hcd   | 518A8709C7 |
| 8086:3b34 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 118   | ehci_hc... | 05DC50AA11 |
| 8086:3b3c | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 118   | ehci_hc... | 05DC50AA11 |
| 8086:1c26 | 1849:1c26 | Intel      | 6 Series/C200 Series Chip... | 117   | ehci_hc... | BDA40E6195 |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8d7c | 1043:8600 | Intel      | C610/X99 series chipset SPSR | 27    |            | A8F2B39356 |
| 8086:8d7c | 15d9:0821 | Intel      | C610/X99 series chipset SPSR | 16    |            | 17BF7A3CBC |
| 8086:a1ec | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    |            | 4391DFF8D2 |
| 8086:8d7c | 1028:0617 | Intel      | C610/X99 series chipset SPSR | 10    |            | 019BFC3983 |
| 8086:8d7c | 103c:8030 | Intel      | C610/X99 series chipset SPSR | 6     |            | 140DAF886E |
| 8086:8d7c | 1458:7270 | Intel      | C610/X99 series chipset SPSR | 6     |            | DFC4A93CDF |
| 8086:8d7c | 1849:8d7c | Intel      | C610/X99 series chipset SPSR | 6     |            | 776B559B1F |
| 8086:2690 | 0000:0000 | Intel      | 631xESB/632xESB/3100 Chip... | 5     | pcieport   | A3AC5B74CF |
| 8086:3500 | 0000:0000 | Intel      | 6311ESB/6321ESB PCI Expre... | 5     | pcieport   | A3AC5B74CF |
| 8086:350c | 0000:0000 | Intel      | 6311ESB/6321ESB PCI Expre... | 5     | shpchp     | A3AC5B74CF |
| 8086:3510 | 0000:0000 | Intel      | 6311ESB/6321ESB PCI Expre... | 5     | pcieport   | A3AC5B74CF |
| 8086:3514 | 0000:0000 | Intel      | 6311ESB/6321ESB PCI Expre... | 5     | pcieport   | A3AC5B74CF |
| 8086:a1ec | 8086:7270 | Intel      | C620 Series Chipset Famil... | 5     |            | 8E73F804F5 |
| 10ec:5260 | 1028:0831 | Realtek... | RTS5260 PCI Express Card ... | 4     | rtsx_pci   | F72215BFC0 |
| 1af2:a001 | 1af2:a001 | AVerMedia  | Live Gamer HD                | 4     |            | D5343B85FF |
| 8086:2692 | 0000:0000 | Intel      | 631xESB/632xESB/3100 Chip... | 4     | pcieport   | A3AC5B74CF |
| 8086:2694 | 0000:0000 | Intel      | 631xESB/632xESB/3100 Chip... | 4     | pcieport   | A3AC5B74CF |
| 8086:2696 | 0000:0000 | Intel      | 631xESB/632xESB/3100 Chip... | 4     | pcieport   | A3AC5B74CF |
| 8086:31d6 | 0000:0000 | Intel      | Gemini Lake PCI Express R... | 4     | shpchp     | 5A0A25C9FF |
| 8086:31d7 | 0000:0000 | Intel      | Gemini Lake PCI Express R... | 4     | shpchp     | 5A0A25C9FF |
| 8086:3518 | 0000:0000 | Intel      | 6311ESB/6321ESB PCI Expre... | 4     | pcieport   | A3AC5B74CF |
| 8086:5ad9 | 0000:0000 | Intel      | Celeron N3350/Pentium N42... | 4     | shpchp     | 6F498D9D7D |
| 8086:8d7c | 1462:7885 | Intel      | C610/X99 series chipset SPSR | 4     |            | 608FAFB692 |
| 8086:a1ed | 8086:7270 | Intel      | C620 Series Chipset Famil... | 4     |            | 8E73F804F5 |
| 1002:6900 | 03ea:1af4 | AMD        | Topaz XT [Radeon R7 M260/... | 3     | amdgpu     | 23C8F78D60 |
| 1aea:6625 | 103c:8478 | Alcor M... | Alcor Micro PCIe Card Reader | 3     |            | AD2AA3B388 |
| 8086:3a40 | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 3     | pcieport   | A4847544CA |
| 8086:3a42 | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 3     | pcieport   | A4847544CA |
| 8086:3a48 | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 3     | pcieport   | A4847544CA |
| 8086:8d7c | 1028:0601 | Intel      | C610/X99 series chipset SPSR | 3     |            | AF9F6ACE3F |
| 8086:8d7c | 1028:064c | Intel      | C610/X99 series chipset SPSR | 3     |            | E1BABF19AD |
| 8086:8d7c | 15d9:0857 | Intel      | C610/X99 series chipset SPSR | 3     |            | D05461EFDA |
| 8086:8d7c | 8086:7270 | Intel      | C610/X99 series chipset SPSR | 3     |            | 7658F21E98 |
| 1002:694e | 1002:694e | AMD        | Polaris 22 XL [Radeon RX ... | 2     | amdgpu     | 07A9851CD6 |
| 8086:3a44 | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 2     | pcieport   | 354B501A79 |
| 8086:3a46 | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 2     | pcieport   | 354B501A79 |
| 8086:3a4a | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 2     | pcieport   | 354B501A79 |
| 8086:5ad6 | 0000:0000 | Intel      | Celeron N3350/Pentium N42... | 2     | pcieport   | 6F498D9D7D |
| 8086:8d7c | 103c:212b | Intel      | C610/X99 series chipset SPSR | 2     |            | 6B7FF8ADA9 |
| 8086:8d7c | 1043:85f6 | Intel      | C610/X99 series chipset SPSR | 2     |            | FD500E59D6 |
| 8086:8d7c | 15d9:0824 | Intel      | C610/X99 series chipset SPSR | 2     |            | 6C96E4A591 |
| 8086:8d7c | 15d9:0831 | Intel      | C610/X99 series chipset SPSR | 2     |            | 52D5275C7F |
| 8086:8d7c | 8086:0000 | Intel      | C610/X99 series chipset SPSR | 2     |            | 5F9F099F36 |
| 0000:0000 | 8005:0000 |            |                              | 1     |            | 77F07D2D69 |
| 0000:0002 | 1105:8300 |            |                              | 1     |            | 3859A12973 |
| 1000:fury | 1000:9343 | Broadco... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 29B0070304 |
| 1000:fury | 1014:0456 | LSI Log... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 817865DED6 |
| 1000:fury | 1028:1f44 | LSI Log... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 5B9EC879FC |
| 1000:fury | 1028:1f4b | LSI Log... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | FF3ACF2BDC |
| 106b:0041 |           | Apple      | K2 KeyLargo Mac/IO           | 1     | macio      | 52B4B037A1 |
| 106b:0043 |           | Apple      | K2 ATA/100                   | 1     | pata_pc... | 52B4B037A1 |
| 1131:7146 | ffff:ffff | Philips... | SAA7146                      | 1     |            | 4893225F50 |
| 1166:0140 | 0000:0000 | Broadcom   | HT2100 PCI-Express Bridge    | 1     | shpchp     | B7596E9C0E |
| 1186:4300 | ffff:ffff | D-Link ... | DGE-528T Gigabit Ethernet... | 1     | r8169      | 5C0883B543 |
| 127a:2014 | 144e:2014 | Rockwel... | HSF 56k Data/Fax/Voice Modem | 1     |            | 97FF18DC78 |
| 13f6:0111 | fbff:fffd | C-Media... | CMI8738/CMI8768 PCI Audio    | 1     | snd_cmipci | 0528AB77BE |
| 144a:5101 | 144a:5101 | Adlink ... |                              | 1     |            | E0E966D6B4 |
| 17a0:9750 | 17aa:2279 | Genesys... | GL9750 SD Host Controller    | 1     |            | 93D5C57FFC |
| 1912:001b | 1d49:0a02 | Renesas... | SH7758 PCIe End-Point [PBI]  | 1     |            | 817865DED6 |
| 1931:1011 | 1003:0001 | Option ... |                              | 1     |            | 28DFB478B7 |
| 1931:1011 | 1043:0001 | Option ... |                              | 1     |            | 28DFB478B7 |
| 1a41:0200 |           | Tilera     | TILE-Gx processor            | 1     | tilegxpci  | 08100751B7 |
| 1a41:0201 |           | Tilera     | TILE-Gx Processor Virtual... | 1     |            | 08100751B7 |
| 1aea:6625 | 103c:83aa | Alcor M... | Alcor Micro PCIe Card Reader | 1     |            | 62C7769C30 |
| 1fc8:0be0 |           | Lucid I... | HYDRA 200                    | 1     |            | F24106BC34 |
| 8005:0000 |           |            |                              | 1     |            | 77F07D2D69 |
| 8086:2551 | 1014:2551 | Intel      | E7505/E7205 Series RAS Co... | 1     |            | D6D105AE70 |
| 8086:2930 | 0062:0002 | Intel      | 82801I (ICH9 Family) SMBu... | 1     | i2c_i801   | CDC805BFC1 |
| 8086:2c51 | 1462:7636 | Intel      | Core Processor QuickPath ... | 1     |            | F694A85C3B |
| 8086:2c81 | 1462:7636 | Intel      | Core Processor QuickPath ... | 1     |            | F694A85C3B |
| 8086:2c90 | 1462:7636 | Intel      | Core Processor QPI Link 0    | 1     | i7core_... | F694A85C3B |
| 8086:2c91 | 1462:7636 | Intel      | Core Processor QPI Physic... | 1     |            | F694A85C3B |
| 8086:2c98 | 1462:7636 | Intel      | Core Processor Integrated... | 1     |            | F694A85C3B |
| 8086:2c99 | 1462:7636 | Intel      | Core Processor Integrated... | 1     |            | F694A85C3B |
| 8086:2c9c | 1462:7636 | Intel      | Core Processor Integrated... | 1     |            | F694A85C3B |
| 8086:2ca0 | 1462:7636 | Intel      | Core Processor Integrated... | 1     |            | F694A85C3B |
| 8086:2ca1 | 1462:7636 | Intel      | Core Processor Integrated... | 1     |            | F694A85C3B |
| 8086:2ca2 | 1462:7636 | Intel      | Core Processor Integrated... | 1     |            | F694A85C3B |
| 8086:2ca3 | 1462:7636 | Intel      | Core Processor Integrated... | 1     |            | F694A85C3B |
| 8086:2ca8 | 1462:7636 | Intel      | Core Processor Integrated... | 1     |            | F694A85C3B |
| 8086:2ca9 | 1462:7636 | Intel      | Core Processor Integrated... | 1     |            | F694A85C3B |
| 8086:2caa | 1462:7636 | Intel      | Core Processor Integrated... | 1     |            | F694A85C3B |
| 8086:2cab | 1462:7636 | Intel      | Core Processor Integrated... | 1     |            | F694A85C3B |
| 8086:2e11 |           | Intel      | 4 Series Chipset PCI Expr... | 1     | pcieport   | FFDEB2B6E2 |
| 8086:31d8 | 0000:0000 | Intel      | Gemini Lake PCI Express R... | 1     | shpchp     | 58FC691B81 |
| 8086:31da | 0000:0000 | Intel      | Gemini Lake PCI Express R... | 1     | shpchp     | 58FC691B81 |
| 8086:31db | 0000:0000 | Intel      | Gemini Lake PCI Express R... | 1     | shpchp     | 58FC691B81 |
| 8086:3591 | 103c:3208 | Intel      | E7525/E7520 Error Reporti... | 1     |            | 2C877CF870 |
| 8086:3591 | 8086:3439 | Intel      | E7525/E7520 Error Reporti... | 1     |            | 0F21E859FA |
| 8086:3a70 |           | Intel      | 82801JD/DO (ICH10 Family)... | 1     | pcieport   | FFDEB2B6E2 |
| 8086:3b4e | 0000:0000 | Intel      | 5 Series/3400 Series Chip... | 1     | shpchp     | B642835279 |
| 8086:6ff2 | 103c:21ea | Intel      | Broadwell-E CBo Unicast R... | 1     |            | D9B1EC3C37 |
| 8086:6ff2 | 1849:6ff2 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 87D6B1C03E |
| 8086:6ff2 | 8086:6ff2 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 9EE9F662A8 |
| 8086:6ff3 | 103c:21ea | Intel      | Broadwell-E CBo Unicast R... | 1     |            | D9B1EC3C37 |
| 8086:6ff3 | 1849:6ff3 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 87D6B1C03E |
| 8086:6ff3 | 8086:6ff3 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 9EE9F662A8 |
| 8086:6ff4 | 103c:21ea | Intel      | Broadwell-E CBo Unicast R... | 1     |            | D9B1EC3C37 |
| 8086:6ff4 | 1849:6ff4 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 87D6B1C03E |
| 8086:6ff5 | 103c:21ea | Intel      | Broadwell-E CBo Unicast R... | 1     |            | D9B1EC3C37 |

