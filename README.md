Most popular PCI devices
========================

This is a project to identify most popular PCI devices in modern computers and
share detailed lspci reports collected by Linux users at https://linux-hardware.org.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo hw-probe -all -upload

Total reports: 65925.

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
   * [ Parallel controller (ecp) ](#parallel-controller-ecp-pci)
   * [ Parallel controller (ieee1284) ](#parallel-controller-ieee1284-pci)
   * [ Performance counters ](#performance-counters-pci)
   * [ Pic (8259) ](#pic-8259-pci)
   * [ Pic (io(x)-apic) ](#pic-iox-apic-pci)
   * [ Power pc ](#power-pc-pci)
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
   * [ Storage/sas ](#storagesas-pci)
   * [ Storage/scsi ](#storagescsi-pci)
   * [ System peripheral ](#system-peripheral-pci)
   * [ Tv card ](#tv-card-pci)
   * [ Unclassified device ](#unclassified-device-pci)
   * [ Usb controller ](#usb-controller-pci)
   * [ Wireless controller ](#wireless-controller-pci)
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
| 1814:3298 | 103c:18ec | Ralink     | RT3290 Bluetooth             | 230   | rtbth      | 96C288C457 |
| 1814:3298 | 105b:e056 | Ralink     | RT3290 Bluetooth             | 59    | rtbth      | 12F5A59D53 |
| 1814:3298 | 1a3b:2787 | Ralink     | RT3290 Bluetooth             | 10    |            | 375A7150DE |
| 1814:3298 | 1a3b:2f87 | Ralink     | RT3290 Bluetooth             | 9     |            | F65DC130D7 |
| 1814:3298 | 1a3b:2987 | Ralink     | RT3290 Bluetooth             | 4     |            | 1F5B5C1D86 |
| 1814:3298 | 103c:191c | Ralink     | RT3290 Bluetooth             | 3     |            | B6260EAFCE |
| 1814:3298 | 1814:3298 | Ralink     | RT3290 Bluetooth             | 2     |            | EF1E6295A8 |
| 1814:3298 | 10cf:1772 | Ralink     | RT3290 Bluetooth             | 1     |            | 1135E21142 |
| 1814:3298 | 1a3b:210b | Ralink     | RT3290 Bluetooth             | 1     |            | 2333E930AF |

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:4384 |           | AMD        | SBx00 PCI to PCI Bridge      | 3436  | shpchp     | 34DC7B3038 |
| 1022:1200 |           | AMD        | Family 10h Processor Hype... | 2116  |            | 34DC7B3038 |
| 1022:1201 |           | AMD        | Family 10h Processor Addr... | 2116  |            | 34DC7B3038 |
| 1022:1202 |           | AMD        | Family 10h Processor DRAM... | 2116  | amd64_e... | 34DC7B3038 |
| 1022:1203 |           | AMD        | Family 10h Processor Misc... | 2116  | k10temp    | 34DC7B3038 |
| 1022:1204 |           | AMD        | Family 10h Processor Link... | 2116  |            | 34DC7B3038 |
| 1022:780f |           | AMD        | FCH PCI Bridge               | 1434  | shpchp     | 0CABEB6C95 |
| 1022:1100 |           | AMD        | K8 [Athlon64/Opteron] Hyp... | 1320  |            | 476F99FF1B |
| 1022:1101 |           | AMD        | K8 [Athlon64/Opteron] Add... | 1320  |            | 476F99FF1B |
| 1022:1102 |           | AMD        | K8 [Athlon64/Opteron] DRA... | 1320  | amd64_e... | 476F99FF1B |
| 1022:1103 |           | AMD        | K8 [Athlon64/Opteron] Mis... | 1320  | k8temp     | 476F99FF1B |
| 1002:439d | 1002:439d | AMD        | SB7x0/SB8x0/SB9x0 LPC hos... | 1052  |            | E722D70419 |
| 1022:1600 |           | AMD        | Family 15h Processor Func... | 994   |            | 3C504F06A2 |
| 1022:1601 |           | AMD        | Family 15h Processor Func... | 994   |            | 3C504F06A2 |
| 1022:1602 |           | AMD        | Family 15h Processor Func... | 994   |            | 3C504F06A2 |
| 1022:1603 |           | AMD        | Family 15h Processor Func... | 994   | k10temp    | 3C504F06A2 |
| 1022:1604 |           | AMD        | Family 15h Processor Func... | 994   | fam15h_... | 3C504F06A2 |
| 1022:1605 |           | AMD        | Family 15h Processor Func... | 994   |            | 3C504F06A2 |
| 1022:1452 |           | AMD        | Family 17h (Models 00h-1f... | 924   |            | 5E8A739106 |
| 1022:1700 |           | AMD        | Family 12h/14h Processor ... | 895   |            | FC53E6761D |
| 1022:1701 |           | AMD        | Family 12h/14h Processor ... | 895   |            | FC53E6761D |
| 1022:1702 |           | AMD        | Family 12h/14h Processor ... | 895   |            | FC53E6761D |
| 1022:1703 |           | AMD        | Family 12h/14h Processor ... | 895   | k10temp    | FC53E6761D |
| 1022:1704 |           | AMD        | Family 12h/14h Processor ... | 895   |            | FC53E6761D |
| 1022:1716 |           | AMD        | Family 12h/14h Processor ... | 895   |            | FC53E6761D |
| 1022:1718 |           | AMD        | Family 12h/14h Processor ... | 895   |            | FC53E6761D |
| 1022:1719 |           | AMD        | Family 12h/14h Processor ... | 895   |            | FC53E6761D |
| 1002:43a0 | 1002:0000 | AMD        | SB700/SB800/SB900 PCI to ... | 892   | shpchp     | E722D70419 |
| 8086:244e | 1458:5000 | Intel      | 82801 PCI Bridge             | 886   |            | ABA2A5E5E6 |
| 8086:2d01 | 8086:8086 | Intel      | Core Processor QuickPath ... | 831   |            | 82CB2D5E90 |
| 8086:2d10 | 8086:8086 | Intel      | Core Processor QPI Link 0    | 831   |            | 82CB2D5E90 |
| 8086:2d11 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 831   |            | 82CB2D5E90 |
| 8086:2d12 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 831   |            | 82CB2D5E90 |
| 8086:2d13 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 831   |            | 82CB2D5E90 |
| 8086:244e |           | Intel      | 82801 PCI Bridge             | 769   | shpchp     | 46CBFD5EE9 |
| 1022:1400 |           | AMD        | Family 15h (Models 10h-1f... | 716   |            | 0CABEB6C95 |
| 1022:1401 |           | AMD        | Family 15h (Models 10h-1f... | 716   |            | 0CABEB6C95 |
| 1022:1402 |           | AMD        | Family 15h (Models 10h-1f... | 716   |            | 0CABEB6C95 |
| 1022:1403 |           | AMD        | Family 15h (Models 10h-1f... | 716   | k10temp    | 0CABEB6C95 |
| 1022:1404 |           | AMD        | Family 15h (Models 10h-1f... | 716   |            | 0CABEB6C95 |
| 1022:1405 |           | AMD        | Family 15h (Models 10h-1f... | 716   |            | 0CABEB6C95 |
| 1022:43a0 | 1022:0000 | AMD        | Hudson PCI to PCI bridge ... | 651   | shpchp     | 18F9503086 |
| 8086:2c62 | 8086:8086 | Intel      | Core Processor QuickPath ... | 642   |            | 82CB2D5E90 |
| 1b21:1080 | 1043:8489 | ASMedia... | ASM1083/1085 PCIe to PCI ... | 635   | shpchp     | 2F0B3935B3 |
| 8086:244e | 1043:8179 | Intel      | 82801 PCI Bridge             | 629   |            | B9B80DB558 |
| 8086:27b8 | 1043:8179 | Intel      | 82801GB/GR (ICH7 Family) ... | 629   | lpc_ich    | B9B80DB558 |
| 8086:27d0 | 1043:8179 | Intel      | NM10/ICH7 Family PCI Expr... | 616   | shpchp     | B9B80DB558 |
| 8086:1c10 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 539   | shpchp     | 13AF031E5E |
| 1002:5a14 | 1002:5a14 | AMD        | RD9x0/RX980 Host Bridge      | 537   | ati_agp    | AFDF4A3A9C |
| 1002:5a16 | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 522   | shpchp     | AFDF4A3A9C |
| 1022:1460 |           | AMD        | Family 17h (Models 00h-0f... | 517   |            | 5E8A739106 |
| 1022:1461 |           | AMD        | Family 17h (Models 00h-0f... | 517   |            | 5E8A739106 |
| 1022:1462 |           | AMD        | Family 17h (Models 00h-0f... | 517   |            | 5E8A739106 |
| 1022:1463 |           | AMD        | Family 17h (Models 00h-0f... | 517   | k10temp    | 5E8A739106 |
| 1022:1464 |           | AMD        | Family 17h (Models 00h-0f... | 517   |            | 5E8A739106 |
| 1022:1465 |           | AMD        | Family 17h (Models 00h-0f... | 517   |            | 5E8A739106 |
| 1022:1466 |           | AMD        | Family 17h (Models 00h-0f... | 517   |            | 5E8A739106 |
| 1022:1467 |           | AMD        | Family 17h (Models 00h-0f... | 517   |            | 5E8A739106 |
| 1002:5a18 | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 500   | shpchp     | AFDF4A3A9C |
| 8086:244e | 1849:244e | Intel      | 82801 PCI Bridge             | 484   | pcieport   | 6FDB8DFE61 |
| 8086:27d2 | 1043:8179 | Intel      | NM10/ICH7 Family PCI Expr... | 474   | shpchp     | B9B80DB558 |
| 8086:0c01 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 468   | shpchp     | 15E3126F2C |
| 8086:0c00 | 1043:8534 | Intel      | 4th Gen Core Processor DR... | 467   | hsw_uncore | 15E3126F2C |
| 8086:2448 |           | Intel      | 82801 Mobile PCI Bridge      | 447   | shpchp     | BA9EFF4F3B |
| 8086:27b8 | 1458:5001 | Intel      | 82801GB/GR (ICH7 Family) ... | 441   | lpc_ich    | ABA2A5E5E6 |
| 1022:43b4 | 1b21:3306 | AMD        | 300 Series Chipset PCIe Port | 431   | pcieport   | 5E8A739106 |
| 1022:1454 | 1022:1454 | AMD        | Family 17h (Models 00h-0f... | 422   | pcieport   | 5E8A739106 |
| 1002:43a1 | 1002:0000 | AMD        | SB700/SB800/SB900 PCI to ... | 419   | shpchp     | 0D6CA866B0 |
| 8086:244e | 1458:8892 | Intel      | 82801 PCI Bridge             | 411   |            | 984B3421C1 |
| 1022:15e8 |           | AMD        | Raven/Raven2 Device 24: F... | 407   |            | C65ABD0640 |
| 1022:15e9 |           | AMD        | Raven/Raven2 Device 24: F... | 407   |            | C65ABD0640 |
| 1022:15ea |           | AMD        | Raven/Raven2 Device 24: F... | 407   |            | C65ABD0640 |
| 1022:15eb |           | AMD        | Raven/Raven2 Device 24: F... | 407   | k10temp    | C65ABD0640 |
| 1022:15ec |           | AMD        | Raven/Raven2 Device 24: F... | 407   |            | C65ABD0640 |
| 1022:15ed |           | AMD        | Raven/Raven2 Device 24: F... | 407   |            | C65ABD0640 |
| 1022:15ee |           | AMD        | Raven/Raven2 Device 24: F... | 407   |            | C65ABD0640 |
| 1022:15ef |           | AMD        | Raven/Raven2 Device 24: F... | 407   |            | C65ABD0640 |
| 1002:439d | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 LPC hos... | 406   |            | 3C504F06A2 |
| 8086:0101 | 1043:844d | Intel      | Xeon E3-1200/2nd Generati... | 398   | shpchp     | 274EEA3275 |
| 8086:0100 | 1043:844d | Intel      | 2nd Generation Core Proce... | 397   | snb_uncore | 274EEA3275 |
| 1022:1414 | 1022:1234 | AMD        | Family 15h (Models 10h-1f... | 385   | shpchp     | 0CABEB6C95 |
| 8086:1e10 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 382   | shpchp     | 535FBF3562 |
| 1022:157b |           | AMD        | Family 15h (Models 60h-6f... | 380   |            | 6EEF4CAED6 |
| 1022:157d |           | AMD        | Carrizo Audio Dummy Host ... | 380   |            | 6EEF4CAED6 |
| 8086:1c1a | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 373   | shpchp     | 13AF031E5E |
| 10de:03e8 | 10de:0000 | Nvidia     | MCP61 PCI Express bridge     | 368   | shpchp     | F60B0BE33D |
| 8086:244e | 1458:5001 | Intel      | 82801 PCI Bridge             | 367   | pcieport   | A5E90F38C5 |
| 1022:43a1 | 1022:0000 | AMD        | Hudson PCI to PCI bridge ... | 365   | shpchp     | 18F9503086 |
| 8086:8c10 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 355   | shpchp     | 15E3126F2C |
| 8086:1c5c | 1043:844d | Intel      | H61 Express Chipset LPC C... | 344   | lpc_ich    | 13AF031E5E |
| 1022:15db | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 339   | pcieport   | C65ABD0640 |
| 1002:43a3 | 1002:0000 | AMD        | SB900 PCI to PCI bridge (... | 336   | shpchp     | 0D6CA866B0 |
| 8086:244e | 1043:844d | Intel      | 82801 PCI Bridge             | 324   | pcieport   | 274EEA3275 |
| 8086:244e | 1043:84ca | Intel      | 82801 PCI Bridge             | 324   | pcieport   | 91535E2115 |
| 8086:1c10 | 1458:5001 | Intel      | 6 Series/C200 Series Chip... | 321   | shpchp     | EF2DAAC6D3 |
| 1022:1510 | 1022:1510 | AMD        | Family 14h Processor Root... | 318   |            | 1A825B75E9 |
| 8086:27d0 | 1458:5001 | Intel      | NM10/ICH7 Family PCI Expr... | 318   | shpchp     | ABA2A5E5E6 |
| 1022:9600 | 1043:8388 | AMD        | RS780 Host Bridge            | 316   |            | 3C504F06A2 |
| 1022:43a2 | 1022:0000 | AMD        | Hudson PCI to PCI bridge ... | 315   | shpchp     | 22A0854387 |
| 8086:244e | 1043:82d4 | Intel      | 82801 PCI Bridge             | 315   |            | 6949452F0E |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:5287 | 1043:202f | Realtek... | RTL8411B PCI Express Card... | 104   | rtsx_pci   | 11A297038F |
| 10ec:5286 | 10ec:5286 | Realtek... | RTL8402 Integrated 1-LUN ... | 94    | rtsx_pci   | 6D7501C42A |
| 10ec:5286 | 1043:202f | Realtek... | RTL8402 Integrated 1-LUN ... | 83    | rtsx_pci   | 54A0B1BE15 |
| 10ec:5289 | 1043:202f | Realtek... | RTL8411 PCI Express Card ... | 83    | rtsx_pci   | 179397B4EA |
| 10ec:5209 | 1025:0685 | Realtek... | RTS5209 PCI Express Card ... | 47    | rtsx_pci   | ECACED6F64 |
| 10ec:5287 | 1025:0866 | Realtek... | RTL8411B PCI Express Card... | 46    | rtsx_pci   | 3FD761163B |
| 10ec:5289 | 10ec:5289 | Realtek... | RTL8411 PCI Express Card ... | 46    | rtsx_pci   | C8264FD679 |
| 10ec:5229 | 10ec:5229 | Realtek... | RTS5229 PCI Express Card ... | 38    | rtsx_pci   | B4CE12C939 |
| 10ec:5229 | 17aa:3808 | Realtek... | RTS5229 PCI Express Card ... | 38    | rtsx_pci   | 7D85F9BFAB |
| 10ec:5209 | 104d:908b | Realtek... | RTS5209 PCI Express Card ... | 37    | rtsx_pci   | A9E0A905BD |
| 10ec:5229 | 1043:202f | Realtek... | RTS5229 PCI Express Card ... | 37    | rtsx_pci   | 6421A501F4 |
| 10ec:5287 | 1025:1192 | Realtek... | RTL8411B PCI Express Card... | 37    | rtsx_pci   | 17E62D31B9 |
| 10ec:5227 | 17aa:220c | Realtek... | RTS5227 PCI Express Card ... | 35    | rtsx_pci   | 14015A6CDE |
| 10ec:5287 | 1025:1094 | Realtek... | RTL8411B PCI Express Card... | 35    | rtsx_pci   | A230640EC7 |
| 10ec:5289 | 1043:1587 | Realtek... | RTL8411 PCI Express Card ... | 35    | rtsx_pci   | A14ECCA066 |
| 10ec:5209 | 1025:0590 | Realtek... | RTS5209 PCI Express Card ... | 33    | rtsx_pci   | 326A5F97CA |
| 10ec:5227 | 10ec:5227 | Realtek... | RTS5227 PCI Express Card ... | 32    | rtsx_pci   | DD43C8D14F |
| 10ec:5287 | 1025:1193 | Realtek... | RTL8411B PCI Express Card... | 31    | rtsx_pci   | 02EEEC88C4 |
| 10ec:5209 | 103c:3577 | Realtek... | RTS5209 PCI Express Card ... | 30    | rtsx_pci   | 758C395C78 |
| 10ec:5209 | 104d:90b8 | Realtek... | RTS5209 PCI Express Card ... | 29    | rtsx_pci   | B9133671A8 |
| 10ec:5229 | 103c:184a | Realtek... | RTS5229 PCI Express Card ... | 29    | rtsx_pci   | 4C72CE34FA |
| 10ec:5287 | 10ec:5287 | Realtek... | RTL8411B PCI Express Card... | 28    | rtsx_pci   | 4575E864C2 |
| 10ec:5209 | 104d:90ab | Realtek... | RTS5209 PCI Express Card ... | 26    | rtsx_pci   | A8AF2E8A8D |
| 10ec:5229 | 103c:2213 | Realtek... | RTS5229 PCI Express Card ... | 26    | rtsx_pci   | 8DF8DAD46F |
| 10ec:5229 | 103c:1818 | Realtek... | RTS5229 PCI Express Card ... | 25    | rtsx_pci   | 6C34B57DD0 |
| 10ec:525a | 1028:087c | Realtek... | RTS525A PCI Express Card ... | 24    | rtsx_pci   | 18DC19F3EC |
| 10ec:5287 | 1025:1264 | Realtek... | RTL8411B PCI Express Card... | 24    | rtsx_pci   | AF51F8907E |
| 10ec:5209 | 103c:1670 | Realtek... | RTS5209 PCI Express Card ... | 23    | rtsx_pci   | AC00D2B8C4 |
| 10ec:5209 | 103c:3567 | Realtek... | RTS5209 PCI Express Card ... | 23    | rtsx_pci   | 9C722B6763 |
| 10ec:522a | 103c:8079 | Realtek... | RTS522A PCI Express Card ... | 23    | rtsx_pci   | BCF0EBFEDD |
| 10ec:5227 | 17aa:220e | Realtek... | RTS5227 PCI Express Card ... | 22    | rtsx_pci   | 3021488D7B |
| 10ec:5227 | 17aa:5034 | Realtek... | RTS5227 PCI Express Card ... | 22    | rtsx_pci   | 71DE9234CB |
| 10ec:5229 | 17aa:3800 | Realtek... | RTS5229 PCI Express Card ... | 22    | rtsx_pci   | 4D7E6E73B6 |
| 10ec:5229 | 103c:183e | Realtek... | RTS5229 PCI Express Card ... | 21    | rtsx_pci   | 232BC57E62 |
| 10ec:522a | 10ec:522a | Realtek... | RTS522A PCI Express Card ... | 21    | rtsx_pci   | 556DD6ED0B |
| 10ec:522a | 8086:2074 | Realtek... | RTS522A PCI Express Card ... | 21    | rtsx_pci   | B039AEFD9E |
| 10ec:5289 | 1043:1457 | Realtek... | RTL8411 PCI Express Card ... | 21    | rtsx_pci   | 7DEA034FEB |
| 10ec:5209 | 1025:0781 | Realtek... | RTS5209 PCI Express Card ... | 20    | rtsx_pci   | 19E141A0F7 |
| 10ec:5227 | 17aa:2214 | Realtek... | RTS5227 PCI Express Card ... | 20    | rtsx_pci   | 43DDF539E2 |
| 10ec:5249 | 17aa:3801 | Realtek... | RTS5249 PCI Express Card ... | 20    | rtsx_pci   | 239616AC43 |
| 10ec:5209 | 1025:061f | Realtek... | RTS5209 PCI Express Card ... | 19    | rtsx_pci   | FBE9C7EEE3 |
| 10ec:525a | 1028:08af | Realtek... | RTS525A PCI Express Card ... | 19    | rtsx_pci   | ED8598DB62 |
| 10ec:5227 | 103c:198f | Realtek... | RTS5227 PCI Express Card ... | 18    | rtsx_pci   | 756C79455B |
| 10ec:5229 | 103c:1854 | Realtek... | RTS5229 PCI Express Card ... | 18    | rtsx_pci   | 96C288C457 |
| 10ec:5229 | 1179:f920 | Realtek... | RTS5229 PCI Express Card ... | 18    | rtsx_pci   | A66F77B75E |
| 10ec:5229 | 8086:2068 | Realtek... | RTS5229 PCI Express Card ... | 18    | rtsx_pci   | 145DFF2B67 |
| 10ec:525a | 1028:07e6 | Realtek... | RTS525A PCI Express Card ... | 18    | rtsx_pci   | C26F2A8CCF |
| 10ec:5229 | 103c:1858 | Realtek... | RTS5229 PCI Express Card ... | 17    | rtsx_pci   | 1433FEF646 |
| 10ec:5229 | 103c:1885 | Realtek... | RTS5229 PCI Express Card ... | 17    | rtsx_pci   | BDF9D0AD55 |
| 10ec:525a | 1028:087d | Realtek... | RTS525A PCI Express Card ... | 17    | rtsx_pci   | 5741F67096 |
| 10ec:5289 | 1025:0724 | Realtek... | RTL8411 PCI Express Card ... | 17    | rtsx_pci   | 6A087DD575 |
| 10ec:5229 | 103c:188b | Realtek... | RTS5229 PCI Express Card ... | 16    | rtsx_pci   | F396951092 |
| 10ec:5229 | 1179:f91b | Realtek... | RTS5229 PCI Express Card ... | 16    | rtsx_pci   | AB7FDCFEBC |
| 10ec:5209 | 103c:1672 | Realtek... | RTS5209 PCI Express Card ... | 15    | rtsx_pci   | BC83BDB23D |
| 10ec:5209 | 104d:907b | Realtek... | RTS5209 PCI Express Card ... | 15    | rtsx_pci   | 07B13B0CD0 |
| 10ec:5229 | 103c:1849 | Realtek... | RTS5229 PCI Express Card ... | 15    | rtsx_pci   | 3ACB153D5D |
| 10ec:5229 | 10cf:176b | Realtek... | RTS5229 PCI Express Card ... | 15    | rtsx_pci   | DA5836E2AA |
| 10ec:522a | 17aa:2233 | Realtek... | RTS522A PCI Express Card ... | 15    | rtsx_pci   | 3A4AD5E700 |
| 10ec:525a | 1028:07be | Realtek... | RTS525A PCI Express Card ... | 15    | rtsx_pci   | 14C2B3FA53 |
| 10ec:5287 | 1025:121e | Realtek... | RTL8411B PCI Express Card... | 15    | rtsx_pci   | E1D731F58D |
| 10ec:5289 | 1558:0240 | Realtek... | RTL8411 PCI Express Card ... | 15    | rtsx_pci   | 5515E2E563 |
| 10ec:5289 | 1558:1550 | Realtek... | RTL8411 PCI Express Card ... | 15    | rtsx_pci   | 0830776CD0 |
| 10ec:5209 | 103c:3566 | Realtek... | RTS5209 PCI Express Card ... | 14    | rtsx_pci   | 10758FAB29 |
| 10ec:5229 | 17aa:5000 | Realtek... | RTS5229 PCI Express Card ... | 14    | rtsx_pci   | 91C9287871 |
| 10ec:5287 | 1025:118a | Realtek... | RTL8411B PCI Express Card... | 14    | rtsx_pci   | AA93BE82FD |
| 10ec:5289 | 1043:14f7 | Realtek... | RTL8411 PCI Express Card ... | 14    | rtsx_pci   | CE99670CEB |
| 10ec:5289 | 1297:2041 | Realtek... | RTL8411 PCI Express Card ... | 14    | rtsx_pci   | 199C248CC1 |
| 10ec:5209 | 1025:0624 | Realtek... | RTS5209 PCI Express Card ... | 13    | rtsx_pci   | 5BD4609615 |
| 10ec:5209 | 1025:0696 | Realtek... | RTS5209 PCI Express Card ... | 13    | rtsx_pci   | E7BE897976 |
| 10ec:5209 | 17aa:21dd | Realtek... | RTS5209 PCI Express Card ... | 13    | rtsx_pci   | 916FA6F088 |
| 10ec:5227 | 103c:1993 | Realtek... | RTS5227 PCI Express Card ... | 13    | rtsx_pci   | A1C9FF7880 |
| 10ec:5229 | 17aa:3801 | Realtek... | RTS5229 PCI Express Card ... | 13    | rtsx_pci   | 93AE933802 |
| 10ec:525a | 1028:06de | Realtek... | RTS525A PCI Express Card ... | 13    | rtsx_pci   | CF0F03C40A |
| 10ec:5209 | 104d:90ac | Realtek... | RTS5209 PCI Express Card ... | 12    | rtsx_pci   | 214F765FC8 |
| 10ec:5227 | 103c:2216 | Realtek... | RTS5227 PCI Express Card ... | 12    | rtsx_pci   | 8279148D8F |
| 10ec:5227 | 103c:2246 | Realtek... | RTS5227 PCI Express Card ... | 12    | rtsx_pci   | 845CC60615 |
| 10ec:5227 | 103c:2248 | Realtek... | RTS5227 PCI Express Card ... | 12    | rtsx_pci   | B87761D1C1 |
| 10ec:5287 | 1025:0940 | Realtek... | RTL8411B PCI Express Card... | 12    | rtsx_pci   | AFC9FDB4B3 |
| 10ec:5287 | 1558:6504 | Realtek... | RTL8411B PCI Express Card... | 12    | rtsx_pci   | 0E8F6B44E6 |
| 10ec:5209 | 103c:1666 | Realtek... | RTS5209 PCI Express Card ... | 11    | rtsx_pci   | CB1F2E06E7 |
| 10ec:5209 | 103c:3389 | Realtek... | RTS5209 PCI Express Card ... | 11    | rtsx_pci   | 49B3B8CDE5 |
| 10ec:5227 | 10cf:187f | Realtek... | RTS5227 PCI Express Card ... | 11    | rtsx_pci   | CCBB4BE6BB |
| 10ec:5227 | 17aa:5020 | Realtek... | RTS5227 PCI Express Card ... | 11    | rtsx_pci   | F1C94DC21E |
| 10ec:522a | 103c:8101 | Realtek... | RTS522A PCI Express Card ... | 11    | rtsx_pci   | A0ACA3E800 |
| 10ec:525a | 1028:0704 | Realtek... | RTS525A PCI Express Card ... | 11    | rtsx_pci   | 4D3C815F1C |
| 10ec:525a | 1028:075b | Realtek... | RTS525A PCI Express Card ... | 11    | rtsx_pci   | 6345D39841 |
| 10ec:525a | 1028:082a | Realtek... | RTS525A PCI Express Card ... | 11    | rtsx_pci   | A767963691 |
| 10ec:5286 | 1558:5470 | Realtek... | RTL8402 Integrated 1-LUN ... | 11    | rtsx_pci   | DC84B60140 |
| 10ec:5287 | 1025:1295 | Realtek... | RTL8411B PCI Express Card... | 11    | rtsx_pci   | CE1098A7F5 |
| 10ec:5289 | 103c:18a7 | Realtek... | RTL8411 PCI Express Card ... | 11    | rtsx_pci   | CD1743483A |
| 10ec:5289 | 1043:1447 | Realtek... | RTL8411 PCI Express Card ... | 11    | rtsx_pci   | B3F9A97ADC |
| 10ec:5289 | 1558:6501 | Realtek... | RTL8411 PCI Express Card ... | 11    | rtsx_pci   | 74E2647236 |
| 10ec:5289 | 1558:6502 | Realtek... | RTL8411 PCI Express Card ... | 11    | rtsx_pci   | 5A5E21619D |
| 1aea:6621 | 1aea:6621 | Alcor M... | Alcor Micro PCIe Card Reader | 11    | alcor_pci  | EF5E47EE93 |
| 10ec:5227 | 1028:0616 | Realtek... | RTS5227 PCI Express Card ... | 10    | rtsx_pci   | 2F330BEE0B |
| 10ec:5227 | 17aa:5028 | Realtek... | RTS5227 PCI Express Card ... | 10    | rtsx_pci   | AFC9FC3D29 |
| 10ec:5229 | 103c:216c | Realtek... | RTS5229 PCI Express Card ... | 10    | rtsx_pci   | 65D5A2C9E3 |
| 10ec:5229 | 1179:ff1e | Realtek... | RTS5229 PCI Express Card ... | 10    | rtsx_pci   | 4B9E002F83 |
| 10ec:5229 | 17aa:5018 | Realtek... | RTS5229 PCI Express Card ... | 10    | rtsx_pci   | 485C2FB9C0 |
| 10ec:5229 | 8086:2072 | Realtek... | RTS5229 PCI Express Card ... | 10    | rtsx_pci   | BA6884F66B |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0aa3 | 10de:cb79 | Nvidia     | MCP79 Co-processor           | 46    | nvidia     | 441575D073 |
| 10de:0753 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Co-... | 38    |            | AFF249E34F |
| 10de:0753 | 1849:0753 | Nvidia     | MCP78S [GeForce 8200] Co-... | 26    |            | 41F3167FB7 |
| 10de:0753 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] Co-... | 23    |            | D672B4583E |
| 10de:03f4 | 1462:7309 | Nvidia     | MCP61 SMU                    | 20    |            | C137270C84 |
| 10de:0543 | 1025:0126 | Nvidia     | MCP67 Co-processor           | 20    |            | 590A68AE68 |
| 10de:0d7a | 10de:cb89 | Nvidia     | MCP89 Co-Processor           | 19    |            | 303C043B8B |
| 10de:0aa3 | 1043:1cf7 | Nvidia     | MCP79 Co-processor           | 18    | nvidia     | F0A1399A3F |
| 10de:03f4 | 1462:7597 | Nvidia     | MCP61 SMU                    | 16    |            | 2DC1AE73B8 |
| 10de:0543 | 103c:30cf | Nvidia     | MCP67 Co-processor           | 16    |            | 1031D661DB |
| 10de:0aa3 | 1043:1fa7 | Nvidia     | MCP79 Co-processor           | 14    | nvidia     | F5C8A70507 |
| 10de:0753 | 1043:82e2 | Nvidia     | MCP78S [GeForce 8200] Co-... | 11    |            | 007691F448 |
| 10de:0aa3 | 1043:8402 | Nvidia     | MCP79 Co-processor           | 9     | nvidia     | F47A1D4306 |
| 10de:0271 | 103c:30b7 | Nvidia     | MCP51 PMU                    | 8     |            | 71764E2EB9 |
| 10de:0aa3 | 1025:0222 | Nvidia     | MCP79 Co-processor           | 8     | nvidia     | 4F99355CFD |
| 10de:03f4 | 1043:8234 | Nvidia     | MCP61 SMU                    | 7     |            | D3A9A22C8A |
| 10de:03f4 |           | Nvidia     | MCP61 SMU                    | 6     |            | FC9814BA3A |
| 10de:0543 | 1043:16a7 | Nvidia     | MCP67 Co-processor           | 6     |            | 451EF7B78E |
| 10de:0543 | 1849:0543 | Nvidia     | MCP67 Co-processor           | 6     |            | 1C80EA8C25 |
| 10de:0aa3 | 1b0a:0074 | Nvidia     | MCP79 Co-processor           | 6     | nvidia     | 4EA9D337D7 |
| 10de:0753 | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] Co-... | 5     |            | 4CA7976A88 |
| 10de:0753 | 1043:82e8 | Nvidia     | MCP78S [GeForce 8200] Co-... | 5     |            | 277C381FCC |
| 10de:0753 | 1565:340b | Nvidia     | MCP78S [GeForce 8200] Co-... | 5     |            | 52B394C153 |
| 10de:0aa3 | 103c:3651 | Nvidia     | MCP79 Co-processor           | 5     | nvidia     | 535E45E25D |
| 10de:0aa3 | 1043:1d17 | Nvidia     | MCP79 Co-processor           | 5     | nvidia     | C2F6621CCC |
| 10de:0447 | 103c:30cf | Nvidia     | MCP65 SMU                    | 4     |            | AB1EF36E83 |
| 10de:0aa3 | 1025:0160 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | 69DC96A4D0 |
| 10de:0aa3 | 1462:1012 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | FE43B38080 |
| 10de:0aa3 | 1849:0aa3 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | 4DEAD658AD |
| 10de:0271 | 103c:30e5 | Nvidia     | MCP51 PMU                    | 3     |            | 45FC8F4912 |
| 10de:0271 | 1043:1367 | Nvidia     | MCP51 PMU                    | 3     |            | B934938C50 |
| 10de:0543 | 103c:30ea | Nvidia     | MCP67 Co-processor           | 3     |            | F4E6748E0D |
| 10de:0753 | 1025:0153 | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | 1F04FD556B |
| 10de:0753 | 1025:0228 | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | B2D5544528 |
| 10de:0753 | 103c:2a81 | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | 8BD9EDAADD |
| 10de:0753 | 1043:82e7 | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | FBFD1473BD |
| 10de:0753 | 1462:6720 | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | 8EC812584C |
| 10de:07da | 1462:7366 | Nvidia     | MCP73 Co-processor           | 3     |            | 3C83AF8B83 |
| 10de:0aa3 | 1043:83e2 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 1452DE25DA |
| 10de:0271 | 103c:30b5 | Nvidia     | MCP51 PMU                    | 2     |            | E964514E68 |
| 10de:0271 | 103c:30bf | Nvidia     | MCP51 PMU                    | 2     |            | 6F28F56C47 |
| 10de:0271 | 1462:373d | Nvidia     | MCP51 PMU                    | 2     |            | 6380916978 |
| 10de:0271 | 1462:3fc1 | Nvidia     | MCP51 PMU                    | 2     |            | 278EF4A255 |
| 10de:03f4 | 1849:03f4 | Nvidia     | MCP61 SMU                    | 2     |            | B7F7A41C71 |
| 10de:0543 | 103c:30d6 | Nvidia     | MCP67 Co-processor           | 2     |            | 3B57385D7E |
| 10de:0753 | 1025:0462 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 03A71DD3EB |
| 10de:07da | 10de:07d7 | Nvidia     | MCP73 Co-processor           | 2     |            | 7DA8928A0F |
| 10de:0aa3 | 1025:0168 | Nvidia     | MCP79 Co-processor           | 2     |            | 5443C8EC11 |
| 10de:0aa3 | 1043:1a87 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | C2D93613D4 |
| 10de:0aa3 | 1462:1019 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | 2054B3A4CC |
| 10de:0aa3 | 1462:7621 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | 1BA5C50EAD |
| 10de:0aa3 | 1734:1151 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | 5EB3DC5665 |
| 10de:0aa3 | 17aa:38da | Nvidia     | MCP79 Co-processor           | 2     |            | C38D40E936 |
| 10de:0aa3 | 19da:0ae5 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | BA99DCB426 |
| 8086:19e2 | 8086:19e2 | Intel      | Atom Processor C3000 Seri... | 2     |            | 50B6A72C0C |
| 10de:0271 | 1025:0112 | Nvidia     | MCP51 PMU                    | 1     |            | 9823532B00 |
| 10de:0271 | 1043:1322 | Nvidia     | MCP51 PMU                    | 1     |            | 71FE8FB963 |
| 10de:0271 | 1734:10d3 | Nvidia     | MCP51 PMU                    | 1     |            | 6172D9B266 |
| 10de:0271 | 1734:10d4 | Nvidia     | MCP51 PMU                    | 1     |            | 40B94D516E |
| 10de:0543 | 1025:0127 | Nvidia     | MCP67 Co-processor           | 1     |            | DB69CCC0BF |
| 10de:0543 | 1043:1697 | Nvidia     | MCP67 Co-processor           | 1     |            | C3296D5344 |
| 10de:0753 | 1019:1b67 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 4765DCDC47 |
| 10de:0753 | 1019:2646 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | D9ABAF941A |
| 10de:0753 | 1025:014a | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | F63FFEFC64 |
| 10de:0753 | 1025:014d | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | E3584BFDCF |
| 10de:0753 | 1025:0227 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 3CF233B9C4 |
| 10de:0753 | 103c:2a9e | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | DF15AC1D7E |
| 10de:0753 | 1043:8332 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | E527269900 |
| 10de:0753 | 1462:6520 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 12132D4EBD |
| 10de:0753 | 1462:7375 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 2C3B9EAC17 |
| 10de:0753 | 1462:7578 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | AFECB4A1DB |
| 10de:0753 | 1462:7612 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 1D2EA48480 |
| 10de:0753 | 1631:e03b | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | E6D16C44AA |
| 10de:07da | 1025:0137 | Nvidia     | MCP73 Co-processor           | 1     |            | ACB89AB604 |
| 10de:07da | 105b:0d1f | Nvidia     | MCP73 Co-processor           | 1     |            | 87EF8BCE11 |
| 10de:07da | 1462:366f | Nvidia     | MCP73 Co-processor           | 1     |            | 238EC9B2AC |
| 10de:07da | 1462:736b | Nvidia     | MCP73 Co-processor           | 1     |            | 0445B13D43 |
| 10de:07da | 1462:7504 | Nvidia     | MCP73 Co-processor           | 1     |            | 05F36A437A |
| 10de:07da | 1849:07da | Nvidia     | MCP73 Co-processor           | 1     |            | 64E722CEC4 |
| 10de:0aa3 | 1028:0271 | Nvidia     | MCP79 Co-processor           | 1     |            | 0238C91A6C |
| 10de:0aa3 | 103c:2a83 | Nvidia     | MCP79 Co-processor           | 1     | nvidia     | 226AA094E2 |
| 10de:0aa3 | 103c:2aa1 | Nvidia     | MCP79 Co-processor           | 1     |            | DF47C88DB6 |
| 10de:0aa3 | 1043:1fd7 | Nvidia     | MCP79 Co-processor           | 1     |            | 717DC8F28E |
| 10de:0aa3 | 1043:8356 | Nvidia     | MCP79 Co-processor           | 1     |            | E5CBBA8ADC |
| 10de:0aa3 | 1043:83f9 | Nvidia     | MCP79 Co-processor           | 1     | nvidia     | D4897620B7 |
| 10de:0aa3 | 105b:0d52 | Nvidia     | MCP79 Co-processor           | 1     |            | BA25C520E2 |
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
| 8086:1c3a | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 536   | mei_me     | 13AF031E5E |
| 8086:1e3a | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 379   | mei_me     | 91535E2115 |
| 8086:8c3a | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 364   | mei_me     | 15E3126F2C |
| 8086:1c3a | 1458:1c3a | Intel      | 6 Series/C200 Series Chip... | 325   | mei_me     | EF2DAAC6D3 |
| 8086:1e3a | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 296   | mei_me     | 8CE0C08E9A |
| 8086:1e3a | 1458:1c3a | Intel      | 7 Series/C216 Chipset Fam... | 274   | mei_me     | 5B67F6ED83 |
| 8086:a13a | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 236   | mei_me     | B8C562A7E5 |
| 8086:8c3a | 1458:1c3a | Intel      | 8 Series/C220 Series Chip... | 224   | mei_me     | 502C5D4B04 |
| 8086:1c3a | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 185   | mei_me     | 89EF922929 |
| 8086:a13a | 1458:1c3a | Intel      | 100 Series/C230 Series Ch... | 138   | mei_me     | 4015843475 |
| 8086:1c3a | 1849:1c3a | Intel      | 6 Series/C200 Series Chip... | 131   | mei_me     | 2A41C5495D |
| 8086:8c3a | 1849:8c3a | Intel      | 8 Series/C220 Series Chip... | 113   | mei_me     | 40DEE920A9 |
| 8086:9c3a | 17aa:3978 | Intel      | 8 Series HECI #0             | 113   | mei_me     | 972580DCF6 |
| 8086:3b64 | 17aa:215f | Intel      | 5 Series/3400 Series Chip... | 108   | mei_me     | 9A495F134B |
| 8086:8cba | 1043:8534 | Intel      | 9 Series Chipset Family M... | 106   | mei_me     | 1D2014DD53 |
| 8086:a2ba | 1458:1c3a | Intel      | 200 Series PCH CSME HECI #1  | 92    | mei_me     | 8F2ECB882C |
| 8086:3b64 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 89    | mei_me     | 088FFC2823 |
| 8086:1c3a | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 88    | mei_me     | B7B1C7DF29 |
| 8086:1e3a | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 88    | mei_me     | 7857E6A77B |
| 8086:a2ba | 1043:8694 | Intel      | 200 Series PCH CSME HECI #1  | 88    | mei_me     | 345BBA3C1F |
| 8086:1e3a | 1849:1e3a | Intel      | 7 Series/C216 Chipset Fam... | 84    | mei_me     | E1466EB2EC |
| 8086:8c3a | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 84    | mei_me     | FBE43FC861 |
| 8086:8cba | 1458:1c3a | Intel      | 9 Series Chipset Family M... | 83    | mei_me     | 984B3421C1 |
| 8086:1c3a | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 80    | mei_me     | 25D909CC38 |
| 8086:2a44 | 17aa:20e6 | Intel      | Mobile 4 Series Chipset M... | 79    | mei_me     | 1A90AC4588 |
| 8086:3b64 | 17aa:38a5 | Intel      | 5 Series/3400 Series Chip... | 78    | mei_me     | 15789D122D |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 77    | mei_me     | 97BCBB884E |
| 8086:1e3a | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 75    | mei_me     | 1C3C62EC29 |
| 8086:1e3a | 1043:124d | Intel      | 7 Series/C216 Chipset Fam... | 69    | mei_me     | 179397B4EA |
| 8086:1c3a | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 67    | mei_me     | 47A635ACC1 |
| 8086:1e3a | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 67    | mei_me     | EFE09AFB77 |
| 8086:1e3a | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 66    | mei_me     | 9084C70732 |
| 8086:3b64 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 64    | mei_me     | 53ECD14649 |
| 8086:1e3a | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 61    | mei_me     | 75E8A3936D |
| 8086:8c3a | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 60    | mei_me     | F21C5B69B8 |
| 8086:3b64 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 56    | mei_me     | 3CDEB04C0D |
| 8086:3b64 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 56    | mei_me     | 90D3759348 |
| 8086:a360 | 1458:1c3a | Intel      | Cannon Lake PCH HECI Cont... | 55    | mei_me     | E097415087 |
| 8086:1c3a | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 53    | mei_me     | 2B202B204B |
| 8086:a13a | 1849:a13a | Intel      | 100 Series/C230 Series Ch... | 53    | mei_me     | 0E4F08FCA3 |
| 8086:a360 | 1043:8694 | Intel      | Cannon Lake PCH HECI Cont... | 53    | mei_me     | 0B771C098E |
| 8086:1c3a | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 52    | mei_me     | 4DB132BB33 |
| 8086:1e3a | 17aa:5011 | Intel      | 7 Series/C216 Chipset Fam... | 50    | mei_me     | 82A9861AFD |
| 8086:1c3a | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 49    | mei_me     | 0BF9EE57AF |
| 8086:1c3a | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 48    | mei_me     | F3FBF8BC70 |
| 8086:1c3a | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 47    | mei_me     | DF459BC2B0 |
| 8086:1e3a | 1043:14c7 | Intel      | 7 Series/C216 Chipset Fam... | 47    | mei_me     | 12F5A59D53 |
| 8086:1c3a | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 46    | mei_me     | 7FD884E502 |
| 8086:1d3a | 1043:84ef | Intel      | C600/X79 series chipset M... | 44    | mei_me     | 39F22D868E |
| 8086:1e3a | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 44    | mei_me     | B162D0FD81 |
| 8086:3b64 | 1458:3b64 | Intel      | 5 Series/3400 Series Chip... | 44    | mei_me     | E60C730AE2 |
| 8086:9c3a | 1025:0866 | Intel      | 8 Series HECI #0             | 43    | mei_me     | 3FD761163B |
| 8086:1e3a | 17aa:21f6 | Intel      | 7 Series/C216 Chipset Fam... | 42    | mei_me     | 1949413DC7 |
| 8086:1c3a | 144d:c0b6 | Intel      | 6 Series/C200 Series Chip... | 41    | mei_me     | 5118CD27DD |
| 8086:1e3a | 1462:7758 | Intel      | 7 Series/C216 Chipset Fam... | 41    | mei_me     | 6DD3E491F5 |
| 8086:1c3a | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 40    | mei_me     | CA779DE74C |
| 8086:5a9a | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 40    | mei_me     | F885D0EE5F |
| 8086:1e3a | 1043:1477 | Intel      | 7 Series/C216 Chipset Fam... | 37    | mei_me     | C005B421A9 |
| 8086:1c3a | 104d:908b | Intel      | 6 Series/C200 Series Chip... | 36    | mei_me     | A9E0A905BD |
| 8086:1e3a | 1179:fb31 | Intel      | 7 Series/C216 Chipset Fam... | 36    | mei_me     | A0FFB29C6C |
| 8086:1e3a | 144d:c652 | Intel      | 7 Series/C216 Chipset Fam... | 35    | mei_me     | 7F741A485F |
| 8086:9c3a | 17aa:220c | Intel      | 8 Series HECI #0             | 35    | mei_me     | 14015A6CDE |
| 8086:9d3a | 8086:7270 | Intel      | Sunrise Point-LP CSME HEC... | 35    | mei_me     | 85085D7FF6 |
| 8086:1e3a | 1043:1587 | Intel      | 7 Series/C216 Chipset Fam... | 34    | mei_me     | A14ECCA066 |
| 8086:1e3a | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 34    | mei_me     | AFB801A018 |
| 8086:319a | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 34    | mei_me     | 59974C206C |
| 8086:9c3a | 1025:0775 | Intel      | 8 Series HECI #0             | 34    | mei_me     | 94CD691A35 |
| 8086:1e3a | 10cf:16ea | Intel      | 7 Series/C216 Chipset Fam... | 33    | mei_me     | DA5836E2AA |
| 8086:9d3a | 17aa:386e | Intel      | Sunrise Point-LP CSME HEC... | 33    | mei_me     | 91D8C5CEC3 |
| 8086:a2ba | 1849:a2ba | Intel      | 200 Series PCH CSME HECI #1  | 33    | mei_me     | 1BB0C8F064 |
| 8086:1e3a | 144d:c0d8 | Intel      | 7 Series/C216 Chipset Fam... | 32    | mei_me     | C5694CCAC0 |
| 8086:319a | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 32    | mei_me     | DAEDE56DC8 |
| 8086:8cba | 1849:8cba | Intel      | 9 Series Chipset Family M... | 32    | mei_me     | 831FF4B7FC |
| 8086:8d3a | 1043:8600 | Intel      | C610/X99 series chipset M... | 32    | mei_me     | 021596F9B3 |
| 8086:9c3a | 1028:0651 | Intel      | 8 Series HECI #0             | 32    | mei_me     | DBD15FDF3D |
| 8086:1e3a | 1025:0686 | Intel      | 7 Series/C216 Chipset Fam... | 31    | mei_me     | 1F28286A78 |
| 8086:1e3a | 1028:0577 | Intel      | 7 Series/C216 Chipset Fam... | 31    | mei_me     | 90FC9AFA3E |
| 8086:3b64 | 144d:c581 | Intel      | 5 Series/3400 Series Chip... | 31    | mei_me     | D9ECE67AC1 |
| 8086:9d3a | 1025:1193 | Intel      | Sunrise Point-LP CSME HEC... | 31    | mei_me     | 02EEEC88C4 |
| 8086:9d3e |           | Intel      | Skylake-U/Y CSME: HECI #3    | 31    | mei_me     | 85085D7FF6 |
| 8086:a2ba | 1043:872f | Intel      | 200 Series PCH CSME HECI #1  | 31    | mei_me     | 6AA8E0B9B0 |
| 8086:9c3a | 1043:131d | Intel      | 8 Series HECI #0             | 30    | mei_me     | 9F136B8761 |
| 8086:1c3a | 103c:161c | Intel      | 6 Series/C200 Series Chip... | 29    | mei_me     | 3EAB448396 |
| 8086:1c3a | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 29    | mei_me     | DA7FEA9DD2 |
| 8086:1e3a | 104d:90b8 | Intel      | 7 Series/C216 Chipset Fam... | 29    | mei_me     | B9133671A8 |
| 8086:2e14 | 1028:027f | Intel      | 4 Series Chipset HECI Con... | 29    | mei_me     | 439AF540E7 |
| 8086:9d3a | 1025:1085 | Intel      | Sunrise Point-LP CSME HEC... | 29    | mei_me     | 8BC74BD7FB |
| 8086:a13a | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 29    | mei_me     | 53CD422052 |
| 8086:1c3a | 1462:7680 | Intel      | 6 Series/C200 Series Chip... | 28    | mei_me     | E29AC96BDB |
| 8086:a360 | 1849:a360 | Intel      | Cannon Lake PCH HECI Cont... | 28    | mei_me     | B0161E1E77 |
| 8086:1c3a | 103c:167c | Intel      | 6 Series/C200 Series Chip... | 27    | mei_me     | A56D8D1C28 |
| 8086:1c3a | 1179:fc30 | Intel      | 6 Series/C200 Series Chip... | 27    | mei_me     | A1569BC1E6 |
| 8086:9c3a | 1043:16cd | Intel      | 8 Series HECI #0             | 27    | mei_me     | 786924EC40 |
| 8086:9d3a | 1025:115f | Intel      | Sunrise Point-LP CSME HEC... | 27    | mei_me     | A230640EC7 |
| 8086:9d3a | 17aa:3801 | Intel      | Sunrise Point-LP CSME HEC... | 27    | mei_me     | 3493C4EBA1 |
| 8086:1e3a | 104d:90ab | Intel      | 7 Series/C216 Chipset Fam... | 26    | mei_me     | A8AF2E8A8D |
| 8086:3b64 | 1025:036d | Intel      | 5 Series/3400 Series Chip... | 26    | mei_me     | D16FFC45F1 |
| 8086:3b64 | 10cf:152b | Intel      | 5 Series/3400 Series Chip... | 26    | mei_me     | 95D76D0DE1 |
| 8086:9cba | 1025:098a | Intel      | Wildcat Point-LP MEI Cont... | 26    | mei_me     | 5861B2E713 |
| 8086:9d3a |           | Intel      | Sunrise Point-LP CSME HEC... | 26    | mei_me     | 32D65CC437 |

### Dma controller (eisa dma) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9ce0 | 8086:9ce0 | Intel      | Wildcat Point-LP Serial I... | 17    | dw_dmac... | 1A26D7B485 |
| 8086:22c0 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 9     | dw_dmac... | C7D9257057 |
| 8086:9c60 |           | Intel      | 8 Series Low Power Sub-Sy... | 6     | dw_dmac... | 52DA4E98F9 |
| 8086:2286 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 5     | dw_dmac... | 287D86CC83 |
| 8086:22c0 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 5     | dw_dmac... | 287D86CC83 |
| 8086:9c60 | 1025:0a11 | Intel      | 8 Series Low Power Sub-Sy... | 3     | dw_dmac... | 85437DFA84 |
| 8086:0f40 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 2     | dw_dmac... | 0994A3EEB3 |
| 8086:9c60 | 103c:21ed | Intel      | 8 Series Low Power Sub-Sy... | 2     | dw_dmac... | 4D0C47EAB1 |
| 8086:0f06 | 8086:0f06 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | A968EF1DD8 |
| 8086:0f06 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | A211982E39 |
| 8086:2286 | 1025:106c | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 09F6D20FE1 |
| 8086:22c0 | 1025:106c | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 09F6D20FE1 |

### Dvb card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 13d0:2103 | 13d0:2103 | Techsan... | B2C2 FlexCopII DVB chip /... | 35    | b2c2_fl... | 51389E5C4A |
| 1131:7146 | 13c2:1018 | Philips... | SAA7146                      | 24    | budget     | 626C138C66 |
| 14f1:8802 | 0070:9002 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     | cx88_dvb   | 9531621804 |
| 1131:7146 | 13c2:0003 | Philips... | SAA7146                      | 2     | dvb_ttpci  | DE8317D2C2 |
| 1131:7146 | 13c2:1019 | Philips... | SAA7146                      | 2     | budget_ci  | 367A4F2A17 |
| 109e:0878 | 1822:0001 | Brooktree  | Bt878 Audio Capture          | 1     | bt878      | E53C96510D |
| 1131:7146 | 1131:4f56 | Philips... | SAA7146                      | 1     | budget_av  | B220FD9C11 |
| 1131:7146 | 13c2:000e | Philips... | SAA7146                      | 1     | dvb_ttpci  | 2A21A99A38 |
| 1131:7146 | 13c2:101a | Philips... | SAA7146                      | 1     | budget_ci  | D299FE84F3 |
| 1131:7146 | 1894:0022 | Philips... | SAA7146                      | 1     | budget_av  | 931BED40DE |
| 14f1:8802 | 17de:08a6 | Conexan... | CX23880/1/2/3 PCI Video a... | 1     | cx88_dv... | FBC32972EA |
| 195d:1105 | 195d:1105 |            | Ethernet controller          | 1     | dm1105     | 531BDFDD32 |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1456 | 1022:1456 | AMD        | Family 17h (Models 00h-0f... | 420   | ccp        | 5E8A739106 |
| 1022:15df | 1022:15df | AMD        | Family 17h (Models 10h-1f... | 204   |            | 9809687258 |
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 202   | mei_txe    | AE477CA654 |
| 1022:1537 | 1022:1537 | AMD        | Kabini/Mullins PSP-Platfo... | 152   | ccp        | 4DC7D17844 |
| 1022:1456 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 80    | ccp        | 172F18A294 |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 79    |            | 22A0854387 |
| 8086:0f18 | 8086:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 67    | mei_txe    | DF450C0459 |
| 1022:1537 | 17aa:3801 | AMD        | Kabini/Mullins PSP-Platfo... | 59    | ccp        | 363B08984A |
| 8086:0f18 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 59    | mei_txe    | F2797B8B83 |
| 8086:0f18 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 59    | mei_txe    | 27F3692E24 |
| 1022:1578 | 103c:8330 | AMD        | Carrizo Platform Security... | 47    |            | E26638D750 |
| 8086:0f18 | 17aa:3909 | Intel      | Atom Processor Z36xxx/Z37... | 38    | mei_txe    | 7D85F9BFAB |
| 1022:1578 | 1025:1192 | AMD        | Carrizo Platform Security... | 37    |            | 17E62D31B9 |
| 8086:2298 | 1025:1012 | Intel      | Atom/Celeron/Pentium Proc... | 32    | mei_txe    | 0949108352 |
| 8086:0f18 | 1043:14dd | Intel      | Atom Processor Z36xxx/Z37... | 31    | mei_txe    | CC9B263062 |
| 1022:1578 | 17aa:3810 | AMD        | Carrizo Platform Security... | 30    |            | 8B23CB3E69 |
| 1022:15df | 1043:876b | AMD        | Family 17h (Models 10h-1f... | 30    |            | DE065F2CFC |
| 8086:0f18 | 1297:2041 | Intel      | Atom Processor Z36xxx/Z37... | 27    | mei_txe    | 199C248CC1 |
| 8086:0f18 | 103c:2213 | Intel      | Atom Processor Z36xxx/Z37... | 26    | mei_txe    | 8DF8DAD46F |
| 8086:0f18 | 1043:161d | Intel      | Atom Processor Z36xxx/Z37... | 26    | mei_txe    | 7BE60A0A2C |
| 8086:0f18 | 1849:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 25    | mei_txe    | F962D4BBF9 |
| 1022:15df | 103c:84ae | AMD        | Family 17h (Models 10h-1f... | 24    |            | 3B491B92B3 |
| 8086:2298 | 1043:10c0 | Intel      | Atom/Celeron/Pentium Proc... | 23    | mei_txe    | FB8F7369FA |
| 8086:0f18 | 1043:15bd | Intel      | Atom Processor Z36xxx/Z37... | 22    | mei_txe    | 6D7501C42A |
| 8086:0f18 | 17aa:3986 | Intel      | Atom Processor Z36xxx/Z37... | 22    | mei_txe    | 4D7E6E73B6 |
| 1022:1486 | 1022:1486 | AMD        | Starship/Matisse Cryptogr... | 21    | ccp        | 2E60313B01 |
| 8086:2298 | 1028:06ac | Intel      | Atom/Celeron/Pentium Proc... | 20    | mei_txe    | 8C1ED50973 |
| 8086:0f18 | 1458:1c3a | Intel      | Atom Processor Z36xxx/Z37... | 19    | mei_txe    | 2AD366F4C0 |
| 1022:1578 | 103c:84ac | AMD        | Carrizo Platform Security... | 18    |            | 6EEF4CAED6 |
| 8086:2298 | 17aa:3808 | Intel      | Atom/Celeron/Pentium Proc... | 18    | mei_txe    | 10AB399874 |
| 1022:1537 | 17aa:3808 | AMD        | Kabini/Mullins PSP-Platfo... | 17    | ccp        | 14B5F106DB |
| 1022:1578 | 103c:8331 | AMD        | Carrizo Platform Security... | 17    |            | 7C2CCF2AA7 |
| 8086:2298 | 103c:832c | Intel      | Atom/Celeron/Pentium Proc... | 15    | mei_txe    | A92F12150A |
| 8086:2298 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 15    | mei_txe    | 5D10E3F271 |
| 1022:1578 | 103c:8333 | AMD        | Carrizo Platform Security... | 14    |            | 6950ED44FE |
| 8086:2298 | 1043:12e0 | Intel      | Atom/Celeron/Pentium Proc... | 14    | mei_txe    | A14B78EF65 |
| 1022:1486 | 1043:87c0 | AMD        | Starship/Matisse Cryptogr... | 13    | ccp        | 40061999CC |
| 1022:1537 | 1025:104b | AMD        | Kabini/Mullins PSP-Platfo... | 13    | ccp        | 356E0F5C70 |
| 1022:15df | 17aa:3809 | AMD        | Family 17h (Models 10h-1f... | 11    |            | 6206EB1A2F |
| 8086:0f18 | 1558:5470 | Intel      | Atom Processor Z36xxx/Z37... | 11    | mei_txe    | DC84B60140 |
| 8086:2298 | 103c:80c5 | Intel      | Atom/Celeron/Pentium Proc... | 11    | mei_txe    | DF94931018 |
| 1022:1578 | 17aa:380f | AMD        | Carrizo Platform Security... | 10    |            | F9C34FA042 |
| 8086:0f18 |           | Intel      | Atom Processor Z36xxx/Z37... | 10    | mei_txe    | 94D1AC4B4E |
| 8086:0f18 | 1025:0845 | Intel      | Atom Processor Z36xxx/Z37... | 10    | mei_txe    | 8981357D7A |
| 8086:0f18 | 1025:0936 | Intel      | Atom Processor Z36xxx/Z37... | 10    | mei_txe    | 74719C2872 |
| 8086:0f18 | 1043:176d | Intel      | Atom Processor Z36xxx/Z37... | 10    | mei_txe    | A0D9281AE2 |
| 8086:2298 | 103c:81f1 | Intel      | Atom/Celeron/Pentium Proc... | 10    | mei_txe    | 8DF47391F9 |
| 8086:2298 | 1043:1cbd | Intel      | Atom/Celeron/Pentium Proc... | 10    | mei_txe    | 71CCEBC0C1 |
| 8086:2298 | 1297:2063 | Intel      | Atom/Celeron/Pentium Proc... | 10    | mei_txe    | EBFA71DD99 |
| 8086:2298 | 1558:0945 | Intel      | Atom/Celeron/Pentium Proc... | 10    | mei_txe    | 0D8FAF0AD0 |
| 1022:1537 | 1025:108a | AMD        | Kabini/Mullins PSP-Platfo... | 9     | ccp        | 74C8472D6F |
| 8086:0f18 | 1025:0933 | Intel      | Atom Processor Z36xxx/Z37... | 9     | mei_txe    | F58E07B59C |
| 8086:0f18 | 103c:220f | Intel      | Atom Processor Z36xxx/Z37... | 9     | mei_txe    | F432E62120 |
| 8086:2298 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 9     | mei_txe    | 576A71CE48 |
| 8086:2298 | 1043:10b0 | Intel      | Atom/Celeron/Pentium Proc... | 9     | mei_txe    | 219AE079DC |
| 8086:2298 | 1043:191d | Intel      | Atom/Celeron/Pentium Proc... | 9     | mei_txe    | 8FCA6A9A6C |
| 8086:2298 | 1043:1d5d | Intel      | Atom/Celeron/Pentium Proc... | 9     | mei_txe    | E407354B88 |
| 8086:2298 | 1043:8534 | Intel      | Atom/Celeron/Pentium Proc... | 9     | mei_txe    | B4A53FAFC1 |
| 1022:1456 | 1462:7a38 | AMD        | Family 17h (Models 00h-0f... | 8     | ccp        | DCDA3B1F44 |
| 1022:15df | 1025:125c | AMD        | Family 17h (Models 10h-1f... | 8     |            | B9A37AB909 |
| 1022:15df | 103c:84e7 | AMD        | Family 17h (Models 10h-1f... | 8     |            | EA1E118AD6 |
| 1022:15df | 17aa:3804 | AMD        | Family 17h (Models 10h-1f... | 8     |            | B0FCF85E0D |
| 8086:0f18 | 103c:2190 | Intel      | Atom Processor Z36xxx/Z37... | 8     | mei_txe    | 0EE1D25C7E |
| 8086:0f18 | 103c:21de | Intel      | Atom Processor Z36xxx/Z37... | 8     | mei_txe    | C2C66314AF |
| 8086:0f18 | 1043:8534 | Intel      | Atom Processor Z36xxx/Z37... | 8     | mei_txe    | 0F8348D5A2 |
| 8086:0f18 | 1179:f91b | Intel      | Atom Processor Z36xxx/Z37... | 8     | mei_txe    | AB7FDCFEBC |
| 8086:2298 | 1458:1000 | Intel      | Atom/Celeron/Pentium Proc... | 8     | mei_txe    | C04DCDD5D7 |
| 8086:2298 | 17aa:380a | Intel      | Atom/Celeron/Pentium Proc... | 8     | mei_txe    | 069BD7BAEB |
| 8086:2298 | 1849:2298 | Intel      | Atom/Celeron/Pentium Proc... | 8     | mei_txe    | B41206F2FD |
| 1022:15df | 1462:7a38 | AMD        | Family 17h (Models 10h-1f... | 7     |            | 924E886E1F |
| 1022:15df | 1462:7c02 | AMD        | Family 17h (Models 10h-1f... | 7     |            | AD51164983 |
| 1022:15df | 17aa:380f | AMD        | Family 17h (Models 10h-1f... | 7     |            | B49AAC1247 |
| 8086:0f18 | 1025:0860 | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | F61E2D2B7B |
| 8086:0f18 | 1025:089d | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | 9195B9BDE3 |
| 8086:0f18 | 1025:0905 | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | AF59A812BC |
| 8086:0f18 | 1025:0939 | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | 02A0230AC2 |
| 8086:0f18 | 1028:064d | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | 0E74429D54 |
| 8086:0f18 | 17aa:3985 | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | 4488D384BA |
| 8086:2298 | 1025:1010 | Intel      | Atom/Celeron/Pentium Proc... | 7     | mei_txe    | 7BDA18A1AC |
| 1022:1537 | 103c:2269 | AMD        | Kabini/Mullins PSP-Platfo... | 6     | ccp        | C6002F59CA |
| 1022:1578 | 1025:109f | AMD        | Carrizo Platform Security... | 6     |            | A2C937F34C |
| 1022:1578 | 17aa:380b | AMD        | Carrizo Platform Security... | 6     |            | 5F425571D2 |
| 1022:15df | 103c:85ea | AMD        | Family 17h (Models 10h-1f... | 6     |            | 4250651580 |
| 1022:15df | 17aa:3811 | AMD        | Family 17h (Models 10h-1f... | 6     |            | C65ABD0640 |
| 8086:0f18 | 1043:16dd | Intel      | Atom Processor Z36xxx/Z37... | 6     | mei_txe    | FAA49795FB |
| 8086:0f18 | 17aa:3807 | Intel      | Atom Processor Z36xxx/Z37... | 6     | mei_txe    | 969154A207 |
| 8086:2298 | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 6     | mei_txe    | 53194E03EE |
| 8086:2298 | 103c:82bd | Intel      | Atom/Celeron/Pentium Proc... | 6     | mei_txe    | 777D549872 |
| 8086:2298 | 103c:8320 | Intel      | Atom/Celeron/Pentium Proc... | 6     | mei_txe    | 36570780B5 |
| 8086:2298 | 103c:8342 | Intel      | Atom/Celeron/Pentium Proc... | 6     | mei_txe    | 989461CCA6 |
| 8086:2298 | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 6     | mei_txe    | 725940B944 |
| 8086:2298 | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 6     | mei_txe    | 4CCE625762 |
| 8086:2298 | 1297:2053 | Intel      | Atom/Celeron/Pentium Proc... | 6     | mei_txe    | 5FE5836ED6 |
| 8086:2298 | 17aa:380b | Intel      | Atom/Celeron/Pentium Proc... | 6     | mei_txe    | 167CFC70E5 |
| 8086:2298 | 8086:2298 | Intel      | Atom/Celeron/Pentium Proc... | 6     | mei_txe    | DA374C3C83 |
| 1022:1456 | 1462:7c02 | AMD        | Family 17h (Models 00h-0f... | 5     | ccp        | 2E3A02EC4D |
| 1022:1537 | 103c:226a | AMD        | Kabini/Mullins PSP-Platfo... | 5     | ccp        | E5C53C61E8 |
| 1022:1537 | 103c:226b | AMD        | Kabini/Mullins PSP-Platfo... | 5     | ccp        | 76B4B1F70F |
| 1022:1537 | 103c:82f6 | AMD        | Kabini/Mullins PSP-Platfo... | 5     | ccp        | F14F865A3D |
| 1022:1578 | 1028:087e | AMD        | Carrizo Platform Security... | 5     |            | D72F217DE7 |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 104c:8024 | 1458:1000 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 401   | firewir... | A056C6C7D5 |
| 1106:3044 | 1043:81fe | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 377   | firewir... | 15EA243CBA |
| 11c1:5901 | 11c1:5900 | LSI        | FW643 [TrueFire] PCIe 139... | 131   | firewir... | 75E8A3936D |
| 11c1:5811 | 1043:8294 | LSI        | FW322/323 [TrueFire] 1394... | 106   | firewir... | 6949452F0E |
| 1106:3044 | 1458:1000 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 105   | firewir... | 0D6CA866B0 |
| 1106:3403 | 1043:8384 | VIA Tec... | VT6315 Series Firewire Co... | 104   | firewir... | DDF9D08A22 |
| 1180:0832 | 17aa:20c7 | Ricoh      | R5C832 IEEE 1394 Controller  | 103   | firewir... | 1A90AC4588 |
| 1106:3044 | 1106:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 95    | firewir... | 522AE798B9 |
| 1102:4001 | 1102:0010 | Creativ... | SB Audigy FireWire Port      | 77    | firewir... | EE5C52C67E |
| 104c:803a | 1025:011f | Texas I... | PCIxx12 OHCI Compliant IE... | 71    | firewir... | BA9EFF4F3B |
| 104c:8023 | 1043:808b | Texas I... | TSB43AB22A IEEE-1394a-200... | 58    | firewir... | 84495E0FB8 |
| 1180:e832 | 17aa:2136 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 51    | firewir... | 9A495F134B |
| 1106:3403 | 1849:3403 | VIA Tec... | VT6315 Series Firewire Co... | 50    | firewir... | A17808DA56 |
| 11c1:5811 | 11c1:5811 | LSI        | FW322/323 [TrueFire] 1394... | 49    | firewir... | A760ED1DA6 |
| 104c:803a | 1179:ff00 | Texas I... | PCIxx12 OHCI Compliant IE... | 45    | firewir... | CCB7CB26D3 |
| 104c:823f |           | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 35    | firewir... | FA300CEB06 |
| 1180:0832 | 1028:0233 | Ricoh      | R5C832 IEEE 1394 Controller  | 34    | firewir... | 314E0FF832 |
| 1217:00f7 | 1028:01f9 | O2 Micro   | Firewire (IEEE 1394)         | 31    | firewir... | 4908DA86B8 |
| 197b:2380 | 1043:8313 | JMicron... | IEEE 1394 Host Controller    | 31    | firewir... | 6FD74ADF75 |
| 1180:0832 | 1028:022f | Ricoh      | R5C832 IEEE 1394 Controller  | 29    | firewir... | 56866B9E4C |
| 1180:0832 | 103c:30cc | Ricoh      | R5C832 IEEE 1394 Controller  | 29    | firewir... | 218FD78ECA |
| 1180:e832 | 1028:040a | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 29    | firewir... | 3E3F341EF4 |
| 197b:2380 | 103c:161c | JMicron... | IEEE 1394 Host Controller    | 29    | firewir... | 3EAB448396 |
| 1106:3403 | 1043:8374 | VIA Tec... | VT6315 Series Firewire Co... | 28    | firewir... | FF37EF634B |
| 104c:8023 | 1043:815b | Texas I... | TSB43AB22A IEEE-1394a-200... | 26    | firewir... | 49BC4A3291 |
| 1180:e832 | 17aa:21f6 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 25    | firewir... | 1949413DC7 |
| 1180:0832 | 1025:011e | Ricoh      | R5C832 IEEE 1394 Controller  | 23    | firewir... | 3530E5C8F1 |
| 1180:0832 | 103c:7008 | Ricoh      | R5C832 IEEE 1394 Controller  | 23    | firewir... | 4663DEB0DD |
| 104c:803a | 103c:30a2 | Texas I... | PCIxx12 OHCI Compliant IE... | 22    | firewir... | 527BA99CD2 |
| 197b:2380 | 103c:179b | JMicron... | IEEE 1394 Host Controller    | 22    | firewir... | 7195452FF3 |
| 1217:00f7 | 1179:ff50 | O2 Micro   | Firewire (IEEE 1394)         | 21    | firewir... | 6108B0C47E |
| 1217:00f7 | 1217:00f7 | O2 Micro   | Firewire (IEEE 1394)         | 21    | firewir... | B4AFED8FAD |
| 1180:0832 | 1025:0121 | Ricoh      | R5C832 IEEE 1394 Controller  | 20    | firewir... | C1C791C270 |
| 1180:0832 | 1025:0126 | Ricoh      | R5C832 IEEE 1394 Controller  | 20    | firewir... | 590A68AE68 |
| 1180:0832 | 103c:30cf | Ricoh      | R5C832 IEEE 1394 Controller  | 20    | firewir... | AB1EF36E83 |
| 1180:0832 | 1043:1877 | Ricoh      | R5C832 IEEE 1394 Controller  | 20    | firewir... | A970D9DFC5 |
| 1180:e832 | 17aa:21cf | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 20    | firewir... | DF04D39AC3 |
| 11c1:5811 | 103c:2a6f | LSI        | FW322/323 [TrueFire] 1394... | 18    | firewir... | AC86A586B5 |
| 1180:0832 | 1043:1317 | Ricoh      | R5C832 IEEE 1394 Controller  | 17    | firewir... | 4841CD6D3C |
| 1180:e832 | 17aa:21ce | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 17    | firewir... | AB2CEA0D81 |
| 197b:2380 | 103c:3628 | JMicron... | IEEE 1394 Host Controller    | 17    | firewir... | BF5A8C1756 |
| 104c:803a | 1179:ff10 | Texas I... | PCIxx12 OHCI Compliant IE... | 16    | firewir... | 5FDCE37F38 |
| 1180:e832 | 1028:040b | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 16    | firewir... | 47A22D2542 |
| 1106:3044 | 1043:808a | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 15    | firewir... | 741F8CFF05 |
| 1106:3403 | 103c:2a9c | VIA Tec... | VT6315 Series Firewire Co... | 15    | firewir... | A585EAEF35 |
| 1180:0832 | 1028:01bd | Ricoh      | R5C832 IEEE 1394 Controller  | 15    | firewir... | AB555162C8 |
| 1180:0832 | 1028:024f | Ricoh      | R5C832 IEEE 1394 Controller  | 15    | firewir... | 9F216D6CB3 |
| 1180:0832 | 1043:1897 | Ricoh      | R5C832 IEEE 1394 Controller  | 15    | firewir... | B720D65E19 |
| 11c1:5811 | 103c:1309 | LSI        | FW322/323 [TrueFire] 1394... | 15    | firewir... | 3F2B4E103F |
| 11c1:5811 | 103c:1589 | LSI        | FW322/323 [TrueFire] 1394... | 15    | firewir... | 9D85C4CA60 |
| 104c:8023 | 8086:514d | Texas I... | TSB43AB22A IEEE-1394a-200... | 14    | firewir... | 9E7FA667C7 |
| 1180:0832 | 103c:172a | Ricoh      | R5C832 IEEE 1394 Controller  | 14    | firewir... | D1C32BF428 |
| 1180:0832 | 1043:14e7 | Ricoh      | R5C832 IEEE 1394 Controller  | 14    | firewir... | 7AC6E3C864 |
| 1180:0832 | 104d:9035 | Ricoh      | R5C832 IEEE 1394 Controller  | 14    | firewir... | 0C80B6E23F |
| 197b:2380 | 103c:1618 | JMicron... | IEEE 1394 Host Controller    | 14    | firewir... | 0D2FE88BE0 |
| 197b:2380 | 103c:17ab | JMicron... | IEEE 1394 Host Controller    | 14    | firewir... | 57308077EE |
| 104c:8023 | 8086:5044 | Texas I... | TSB43AB22A IEEE-1394a-200... | 13    | firewir... | 90F4B2CD0E |
| 104c:8024 | 1019:8056 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 13    | firewir... | F60B0BE33D |
| 1106:3044 | 1849:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 13    | firewir... | 2123239208 |
| 1180:0832 | 1043:1517 | Ricoh      | R5C832 IEEE 1394 Controller  | 13    | firewir... | 427546EA21 |
| 1180:0832 | 1179:ff1c | Ricoh      | R5C832 IEEE 1394 Controller  | 13    | firewir... | 420C738977 |
| 1217:13f7 | 1028:0494 | O2 Micro   | 1394 OHCI Compliant Host ... | 13    | firewir... | 4384225066 |
| 197b:2380 | 103c:3603 | JMicron... | IEEE 1394 Host Controller    | 13    | firewir... | F2190D7446 |
| 1106:3403 | 1106:3403 | VIA Tec... | VT6315 Series Firewire Co... | 12    | firewir... | 74374104D4 |
| 1180:0832 | 103c:30c0 | Ricoh      | R5C832 IEEE 1394 Controller  | 12    | firewir... | A4D3F8A8AC |
| 1180:0832 | 1043:1767 | Ricoh      | R5C832 IEEE 1394 Controller  | 12    | firewir... | 4137AC8F54 |
| 1217:11f7 | 1028:04a3 | O2 Micro   | OZ600 1394a-2000 Controller  | 12    | firewir... | D8BA5B1425 |
| 197b:2380 | 103c:3659 | JMicron... | IEEE 1394 Host Controller    | 12    | firewir... | B48F5D5FDD |
| 104c:8025 |           | Texas I... | TSB82AA2 IEEE-1394b Link ... | 11    | firewir... | 3A660A2575 |
| 1180:0832 | 1028:029a | Ricoh      | R5C832 IEEE 1394 Controller  | 11    | firewir... | 394D903321 |
| 1180:0832 | 103c:30db | Ricoh      | R5C832 IEEE 1394 Controller  | 11    | firewir... | 94AF8C86B1 |
| 1180:0832 | 103c:7007 | Ricoh      | R5C832 IEEE 1394 Controller  | 11    | firewir... | 82CB2D5E90 |
| 11c1:5811 | 103c:30dd | LSI        | FW322/323 [TrueFire] 1394... | 11    | firewir... | B7DD4F6E2C |
| 1217:13f7 | 1028:049a | O2 Micro   | 1394 OHCI Compliant Host ... | 11    | firewir... | 6FD4500E86 |
| 1106:3044 | 1106:0404 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 10    | firewir... | 451E46E979 |
| 1180:0832 | 103c:30bb | Ricoh      | R5C832 IEEE 1394 Controller  | 10    | firewir... | 7B1828833F |
| 1180:0832 | 103c:30be | Ricoh      | R5C832 IEEE 1394 Controller  | 10    | firewir... | 6ABE286091 |
| 197b:2380 | 103c:30f4 | JMicron... | IEEE 1394 Host Controller    | 10    | firewir... | 01F5E9CD57 |
| 104c:803a | 104d:902d | Texas I... | PCIxx12 OHCI Compliant IE... | 9     | firewir... | DE6F0F6D83 |
| 104c:803a | 1179:0001 | Texas I... | PCIxx12 OHCI Compliant IE... | 9     | firewir... | 0C90DCED50 |
| 1180:0832 | 10f7:8338 | Ricoh      | R5C832 IEEE 1394 Controller  | 9     | firewir... | 3B2DF65591 |
| 1180:e832 | 103c:146d | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 9     | firewir... | 45A1D9A3BA |
| 197b:2380 | 103c:1619 | JMicron... | IEEE 1394 Host Controller    | 9     | firewir... | 6736244BE1 |
| 197b:2380 | 103c:179c | JMicron... | IEEE 1394 Host Controller    | 9     | firewir... | 883AFD81BF |
| 104c:8032 | 103c:099c | Texas I... | OHCI Compliant IEEE 1394 ... | 8     | firewir... | E0DF895DC8 |
| 104c:803a | 104d:9015 | Texas I... | PCIxx12 OHCI Compliant IE... | 8     | firewir... | B6F0BD6CA4 |
| 104c:823f | 3412:7856 | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 8     | firewir... | 8C51CE9858 |
| 1106:3044 | 17f2:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 8     | firewir... | F235798C9E |
| 1180:0832 | 1028:01f2 | Ricoh      | R5C832 IEEE 1394 Controller  | 8     | firewir... | 09BC8D2536 |
| 1180:0832 | 1028:023a | Ricoh      | R5C832 IEEE 1394 Controller  | 8     | firewir... | 832410EBE7 |
| 1180:0832 | 103c:1521 | Ricoh      | R5C832 IEEE 1394 Controller  | 8     | firewir... | 283EC51B86 |
| 1180:0832 | 104d:900e | Ricoh      | R5C832 IEEE 1394 Controller  | 8     | firewir... | 7B4B0311EA |
| 1180:0832 | 17aa:3829 | Ricoh      | R5C832 IEEE 1394 Controller  | 8     | firewir... | 3C97F337A2 |
| 1180:e832 | 104d:9069 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 8     | firewir... | D21AA077CE |
| 11c1:5811 | 1028:5811 | LSI        | FW322/323 [TrueFire] 1394... | 8     | firewir... | 365B2DE3CD |
| 1217:10f7 | 1028:02bc | O2 Micro   | 1394 OHCI Compliant Host ... | 8     | firewir... | E1FF130D0A |
| 1217:13f7 | 1028:049b | O2 Micro   | 1394 OHCI Compliant Host ... | 8     | firewir... | 4673399116 |
| 1033:00f2 | 1033:00f2 | NEC Com... | uPD72874 [Firewarden] IEE... | 7     | firewir... | B99C2286C9 |
| 104c:8023 | 1849:8023 | Texas I... | TSB43AB22A IEEE-1394a-200... | 7     | firewir... | 22D2F0F13E |
| 104c:803a | 103c:30aa | Texas I... | PCIxx12 OHCI Compliant IE... | 7     | firewir... | 9C1BF7D811 |

### Flash memory (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1524:0520 | 1025:0090 | ENE Tec... | FLASH memory: ENE Technol... | 34    |            | 5979EB4500 |
| 1524:0530 | 1025:0090 | ENE Tec... | ENE PCI Memory Stick Card... | 34    |            | 5979EB4500 |
| 1524:0551 | 1025:0090 | ENE Tec... | SD/MMC Card Reader Contro... | 34    | sdhci_pci  | 5979EB4500 |
| 1524:0520 | 1025:009f | ENE Tec... | FLASH memory: ENE Technol... | 26    |            | 005CF3D43E |
| 1524:0530 | 1025:009f | ENE Tec... | ENE PCI Memory Stick Card... | 26    |            | 005CF3D43E |
| 1524:0551 | 1025:009f | ENE Tec... | SD/MMC Card Reader Contro... | 26    | sdhci_pci  | 005CF3D43E |
| 1524:0720 | 1025:012e | ENE Tec... | Memory Stick Card Reader ... | 12    |            | 48841846AC |
| 1524:0730 | 1025:012e | ENE Tec... | ENE PCI Memory Stick Card... | 12    |            | 48841846AC |
| 1524:0751 | 1025:012e | ENE Tec... | ENE PCI Secure Digital / ... | 12    | sdhci_pci  | 48841846AC |
| 1524:0520 | 1025:010f | ENE Tec... | FLASH memory: ENE Technol... | 8     |            | 7D53608E50 |
| 1524:0530 | 1025:010f | ENE Tec... | ENE PCI Memory Stick Card... | 8     |            | 7D53608E50 |
| 1524:0551 | 1025:010f | ENE Tec... | SD/MMC Card Reader Contro... | 8     | sdhci_pci  | 7D53608E50 |
| 1524:0530 | 14c0:0020 | ENE Tec... | ENE PCI Memory Stick Card... | 7     |            | 0351248973 |
| 1524:0551 | 14c0:0020 | ENE Tec... | SD/MMC Card Reader Contro... | 7     | sdhci_pci  | 0351248973 |
| 1524:0530 | 1734:10c1 | ENE Tec... | ENE PCI Memory Stick Card... | 5     |            | AAAB07D2AE |
| 1524:0551 | 1734:10c1 | ENE Tec... | SD/MMC Card Reader Contro... | 5     | sdhci_pci  | AAAB07D2AE |
| 1106:9530 | 17aa:3891 | VIA Tec... | Secure Digital Memory Car... | 3     | via_sdmmc  | 4AA0EF1314 |
| 1524:0510 | 1524:0510 | ENE Tec... | CB710 Memory Card Reader ... | 2     | cb710      | 932FA70B29 |
| 1524:0520 | 1179:ff01 | ENE Tec... | FLASH memory: ENE Technol... | 2     |            | C27B4CD3AF |
| 1524:0530 | 1179:ff01 | ENE Tec... | ENE PCI Memory Stick Card... | 2     |            | C27B4CD3AF |
| 1524:0551 | 1179:ff02 | ENE Tec... | SD/MMC Card Reader Contro... | 2     | sdhci_pci  | C27B4CD3AF |
| 1524:0720 | 1025:011b | ENE Tec... | Memory Stick Card Reader ... | 2     |            | 89AEC2CFFD |
| 1524:0720 | 1462:2fb3 | ENE Tec... | Memory Stick Card Reader ... | 2     |            | D6A996DA64 |
| 1524:0720 | 1462:2fbd | ENE Tec... | Memory Stick Card Reader ... | 2     |            | 6502446C70 |
| 1524:0730 | 1025:011b | ENE Tec... | ENE PCI Memory Stick Card... | 2     |            | 89AEC2CFFD |
| 1524:0730 | 1462:2fb3 | ENE Tec... | ENE PCI Memory Stick Card... | 2     |            | D6A996DA64 |
| 1524:0730 | 1462:2fbd | ENE Tec... | ENE PCI Memory Stick Card... | 2     |            | 6502446C70 |
| 1524:0730 | 1558:0669 | ENE Tec... | ENE PCI Memory Stick Card... | 2     |            | 647FD58075 |
| 1524:0730 | 1558:5409 | ENE Tec... | ENE PCI Memory Stick Card... | 2     |            | 97181C941C |
| 1524:0751 | 1025:011b | ENE Tec... | ENE PCI Secure Digital / ... | 2     | sdhci_pci  | 89AEC2CFFD |
| 1524:0751 | 1462:2fb3 | ENE Tec... | ENE PCI Secure Digital / ... | 2     | sdhci_pci  | D6A996DA64 |
| 1524:0751 | 1462:2fbd | ENE Tec... | ENE PCI Secure Digital / ... | 2     | sdhci_pci  | 6502446C70 |
| 1524:0751 | 1558:0669 | ENE Tec... | ENE PCI Secure Digital / ... | 2     | sdhci_pci  | 647FD58075 |
| 1524:0751 | 1558:5409 | ENE Tec... | ENE PCI Secure Digital / ... | 2     | sdhci_pci  | 97181C941C |
| 1106:9530 | 144d:c04e | VIA Tec... | Secure Digital Memory Car... | 1     | via_sdmmc  | 3DDEF2506D |
| 1524:0520 | 1025:007a | ENE Tec... | FLASH memory: ENE Technol... | 1     |            | E4219525B9 |
| 1524:0520 | 1025:007f | ENE Tec... | FLASH memory: ENE Technol... | 1     |            | 246BC5476B |
| 1524:0530 | 1025:007a | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | E4219525B9 |
| 1524:0530 | 1025:007f | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | 246BC5476B |
| 1524:0530 | 1558:5401 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | 8CF7873695 |
| 1524:0530 | 1734:10d7 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | CA3AC06D30 |
| 1524:0530 | 17aa:2079 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | EDAE63A429 |
| 1524:0551 | 1025:007a | ENE Tec... | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | E4219525B9 |
| 1524:0551 | 1025:007f | ENE Tec... | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 246BC5476B |
| 1524:0551 | 1558:5401 | ENE Tec... | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 8CF7873695 |
| 1524:0551 | 1734:10d7 | ENE Tec... | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | CA3AC06D30 |
| 1524:0551 | 17aa:2078 | ENE Tec... | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | EDAE63A429 |
| 1524:0720 | 1025:012a | ENE Tec... | Memory Stick Card Reader ... | 1     |            | C95503E7D2 |
| 1524:0730 | 1025:012a | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | C95503E7D2 |
| 1524:0730 | 1558:0664 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | 51E2E84C28 |
| 1524:0730 | 1558:0668 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | 41C9811E8B |
| 1524:0730 | 1558:0801 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | A28F10A223 |
| 1524:0730 | 1558:5408 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | C3A0F0B364 |
| 1524:0751 | 1025:012a | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | C95503E7D2 |
| 1524:0751 | 1558:0664 | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | 51E2E84C28 |
| 1524:0751 | 1558:0668 | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | 41C9811E8B |
| 1524:0751 | 1558:0801 | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | A28F10A223 |
| 1524:0751 | 1558:5408 | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | C3A0F0B364 |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1451 | 1022:1451 | AMD        | Family 17h (Models 00h-0f... | 308   |            | 5E8A739106 |
| 1002:5a23 | 1002:5a23 | AMD        | RD890S/RD990 I/O Memory M... | 153   |            | EE5C52C67E |
| 1022:1419 | 1022:1419 | AMD        | Family 15h (Models 10h-1f... | 123   |            | EAD3059AA0 |
| 1022:1577 | 1022:1577 | AMD        | Family 15h (Models 60h-6f... | 106   |            | 8B23CB3E69 |
| 1002:5a23 | 1462:7693 | AMD        | RD890S/RD990 I/O Memory M... | 57    |            | 9650DD9DCE |
| 1022:1423 | 1022:1423 | AMD        | Family 15h (Models 30h-3f... | 29    |            | 8FBC16EBFA |
| 1022:1419 | 1462:7721 | AMD        | Family 15h (Models 10h-1f... | 22    |            | 3486C89441 |
| 1022:1423 | 1462:7721 | AMD        | Family 15h (Models 30h-3f... | 21    |            | 743F3FF81C |
| 1022:1577 | 103c:8331 | AMD        | Family 15h (Models 60h-6f... | 17    |            | 7C2CCF2AA7 |
| 1022:1423 | 1043:85cb | AMD        | Family 15h (Models 30h-3f... | 12    |            | 7C1CD714FB |
| 1022:1419 | 1462:7895 | AMD        | Family 15h (Models 10h-1f... | 8     |            | 20ED2C9B41 |
| 1002:5a23 | 1458:5000 | AMD        | RD890S/RD990 I/O Memory M... | 7     |            | 0D6CA866B0 |
| 1002:5a23 | 1462:7640 | AMD        | RD890S/RD990 I/O Memory M... | 7     |            | 54E2BF8542 |
| 1002:5a23 | 1462:7974 | AMD        | RD890S/RD990 I/O Memory M... | 6     |            | 3F7E1BB390 |
| 1022:1423 | 1462:7895 | AMD        | Family 15h (Models 30h-3f... | 5     |            | E1D561ABB4 |
| 1022:1577 | 103c:81fa | AMD        | Family 15h (Models 60h-6f... | 5     |            | CD1E50AD54 |
| 1022:1419 | 1043:8526 | AMD        | Family 15h (Models 10h-1f... | 4     |            | 84CF4C391A |
| 1022:1419 | 1019:7c8d | AMD        | Family 15h (Models 10h-1f... | 3     |            | 8A37732F55 |
| 1022:1423 | 103c:812f | AMD        | Family 15h (Models 30h-3f... | 3     |            | CEC70BF357 |
| 1022:1419 | 1025:070b | AMD        | Family 15h (Models 10h-1f... | 2     |            | F083D73A9E |
| 1022:1577 | 103c:80b5 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 407AB6CE27 |
| 1022:1577 | 103c:80b6 | AMD        | Family 15h (Models 60h-6f... | 2     |            | BEA3C73273 |
| 1022:1577 | 103c:8355 | AMD        | Family 15h (Models 60h-6f... | 2     |            | D6F5348EC7 |
| 8086:19a2 | 8086:19a2 | Intel      | Atom Processor C3000 Seri... | 2     |            | 50B6A72C0C |
| 1022:1419 | 1462:7900 | AMD        | Family 15h (Models 10h-1f... | 1     |            | 985C8F6BB3 |
| 1022:1419 | 17aa:36a0 | AMD        | Family 15h (Models 10h-1f... | 1     |            | BA1A484E84 |
| 1022:1423 | 1462:7793 | AMD        | Family 15h (Models 30h-3f... | 1     |            | 54040FA02B |
| 1022:1423 | 17aa:368f | AMD        | Family 15h (Models 30h-3f... | 1     |            | 58DDD6F565 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 185   | i915       | AE477CA654 |
| 8086:0412 | 1458:d000 | Intel      | Xeon E3-1200 v3/4th Gen C... | 158   | i915       | 75C292C941 |
| 8086:0102 | 1043:844d | Intel      | 2nd Generation Core Proce... | 115   | i915       | 274EEA3275 |
| 8086:0412 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 101   | i915       | 1D2014DD53 |
| 8086:0102 | 1458:d000 | Intel      | 2nd Generation Core Proce... | 94    | i915       | B5CEB59A3F |
| 10de:128b | 1462:8c93 | Nvidia     | GK208B [GeForce GT 710]      | 90    | nouveau    | C51735EE45 |
| 8086:a011 | 1043:83ac | Intel      | Atom Processor D4xx/D5xx/... | 88    | i915       | E368A28816 |
| 8086:a012 | 1043:83ac | Intel      | Atom Processor D4xx/D5xx/... | 88    |            | E368A28816 |
| 10de:0a65 |           | Nvidia     | GT218 [GeForce 210]          | 87    | nouveau    | 11FC0E438A |
| 1002:9616 | 1043:8388 | AMD        | RS780L [Radeon 3000]         | 81    | radeon     | A898DD70F0 |
| 8086:0152 | 1458:d000 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 78    | i915       | BBFED70437 |
| 10de:0615 |           | Nvidia     | G92 [GeForce GTS 250]        | 77    | nvidia     | 82A50E872A |
| 8086:0046 | 17aa:215a | Intel      | Core Processor Integrated... | 75    | i915       | 9C774DC87F |
| 10de:0640 |           | Nvidia     | G96C [GeForce 9500 GT]       | 73    | nouveau    | CED3C3C6BB |
| 10de:0de0 |           | Nvidia     | GF108 [GeForce GT 440]       | 72    | nouveau    | 843A450979 |
| 8086:29c2 | 1043:82b0 | Intel      | 82G33/G31 Express Integra... | 71    | i915       | E62DB6E4E2 |
| 10de:0622 |           | Nvidia     | G94 [GeForce 9600 GT]        | 70    | nvidia     | 69749F7B95 |
| 8086:0166 | 1025:0647 | Intel      | 3rd Gen Core processor Gr... | 69    | i915       | 9084C70732 |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics 500              | 68    | i915       | 97BCBB884E |
| 8086:2e32 | 1043:836d | Intel      | 4 Series Chipset Integrat... | 67    | i915       | 9AC5E13707 |
| 8086:0f31 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 66    | i915       | 2332ED0DD8 |
| 10de:0614 |           | Nvidia     | G92 [GeForce 9800 GT]        | 63    | nouveau    | 2BDA09406C |
| 8086:0106 | 1025:0649 | Intel      | 2nd Generation Core Proce... | 61    | i915       | 7857E6A77B |
| 8086:0402 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 61    | i915       | 63C2D20280 |
| 10de:0ca3 |           | Nvidia     | GT215 [GeForce GT 240]       | 60    | nvidia     | 7F477DA95D |
| 8086:2a42 | 17aa:20e4 | Intel      | Mobile 4 Series Chipset I... | 60    | i915       | 1A90AC4588 |
| 8086:2a43 | 17aa:20e4 | Intel      | Mobile 4 Series Chipset I... | 60    |            | 1A90AC4588 |
| 10de:1244 |           | Nvidia     | GF116 [GeForce GTX 550 Ti]   | 59    | nouveau    | 2535033ACD |
| 8086:0152 | 1043:844d | Intel      | Xeon E3-1200 v2/3rd Gen C... | 59    | i915       | 13AF031E5E |
| 8086:2772 | 1043:817a | Intel      | 82945G/GZ Integrated Grap... | 59    | i915       | 46027F2A96 |
| 8086:0f31 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 57    | i915       | F2797B8B83 |
| 8086:29c2 | 1849:29c2 | Intel      | 82G33/G31 Express Integra... | 57    | i915       | B64547F948 |
| 8086:2a02 | 1025:011f | Intel      | Mobile GM965/GL960 Integr... | 57    | i915       | BA9EFF4F3B |
| 8086:2a03 | 1025:011f | Intel      | Mobile GM965/GL960 Integr... | 57    |            | BA9EFF4F3B |
| 8086:2a42 | 1043:1862 | Intel      | Mobile 4 Series Chipset I... | 56    | i915       | 429A82D3C7 |
| 8086:2a42 | 17aa:3a02 | Intel      | Mobile 4 Series Chipset I... | 56    | i915       | 5986AA0AAC |
| 8086:2a43 | 1043:1862 | Intel      | Mobile 4 Series Chipset I... | 56    |            | 429A82D3C7 |
| 8086:2a43 | 17aa:3a02 | Intel      | Mobile 4 Series Chipset I... | 56    |            | 5986AA0AAC |
| 8086:0156 | 17aa:3977 | Intel      | 3rd Gen Core processor Gr... | 55    | i915       | 176A1CCFC5 |
| 10de:03d6 | 1849:03d6 | Nvidia     | C61 [GeForce 7025 / nForc... | 54    | nouveau    | EC1F6C8A0B |
| 10de:0de1 |           | Nvidia     | GF108 [GeForce GT 430]       | 54    | nouveau    | 82A8163E58 |
| 8086:0116 | 1025:0504 | Intel      | 2nd Generation Core Proce... | 54    | i915       | 25D909CC38 |
| 8086:a011 | 1025:0349 | Intel      | Atom Processor D4xx/D5xx/... | 54    | i915       | A911172500 |
| 8086:a012 | 1025:0349 | Intel      | Atom Processor D4xx/D5xx/... | 54    |            | A911172500 |
| 10de:0f00 | 1569:0f00 | Nvidia     | GF108 [GeForce GT 630]       | 53    | nouveau    | 65629CCF94 |
| 10de:0fc6 | 1569:0fc6 | Nvidia     | GK107 [GeForce GTX 650]      | 53    | nouveau    | B9B80DB558 |
| 8086:0166 | 17aa:3977 | Intel      | 3rd Gen Core processor Gr... | 52    | i915       | 3DCE4D353B |
| 8086:0166 | 17aa:5003 | Intel      | 3rd Gen Core processor Gr... | 52    | i915       | 1C3C62EC29 |
| 1002:67df | 1da2:e366 | AMD        | Ellesmere [Radeon RX 470/... | 51    | amdgpu     | 362C1B59B4 |
| 8086:0152 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 50    | i915       | B49F37B1D2 |
| 8086:0166 | 1043:124d | Intel      | 3rd Gen Core processor Gr... | 50    | i915       | 179397B4EA |
| 8086:0f31 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 50    | i915       | 27F3692E24 |
| 8086:1912 | 1043:8694 | Intel      | HD Graphics 530              | 49    | i915       | F6CCED2603 |
| 8086:5912 | 1043:8694 | Intel      | HD Graphics 630              | 49    | i915       | 30009478A9 |
| 8086:0be1 | 1043:84a9 | Intel      | Atom Processor D2xxx/N2xx... | 48    | gma500_gfx | ECB853F69D |
| 1002:15dd | 1002:15dd | AMD        | Raven Ridge [Radeon Vega ... | 47    | amdgpu     | 564EB1FFE4 |
| 1002:9616 | 1458:d000 | AMD        | RS780L [Radeon 3000]         | 47    | radeon     | 4237BD1A34 |
| 1002:98e4 | 103c:8330 | AMD        | Stoney [Radeon R2/R3/R4/R... | 47    | amdgpu     | E26638D750 |
| 8086:0106 | 17aa:3975 | Intel      | 2nd Generation Core Proce... | 45    | i915       | 7C676D0AAC |
| 8086:2e32 | 1458:d000 | Intel      | 4 Series Chipset Integrat... | 44    | i915       | 1B60792885 |
| 10de:0402 |           | Nvidia     | G84 [GeForce 8600 GT]        | 43    | nouveau    | B6FA3D93AF |
| 8086:0166 | 1025:064b | Intel      | 3rd Gen Core processor Gr... | 43    | i915       | D78E0C1E84 |
| 8086:2772 | 1458:d000 | Intel      | 82945G/GZ Integrated Grap... | 43    | i915       | 53B4651D22 |
| 8086:29c2 | 1458:d000 | Intel      | 82G33/G31 Express Integra... | 43    | i915       | 01B25A0DED |
| 1002:68e4 | 17aa:397a | AMD        | Robson CE [Radeon HD 6370... | 42    | radeon     | 0A5AF961D7 |
| 1002:15dd | 1043:876b | AMD        | Raven Ridge [Radeon Vega ... | 41    | amdgpu     | 2FB35125E3 |
| 8086:0402 | 1458:d000 | Intel      | Xeon E3-1200 v3/4th Gen C... | 41    | i915       | 502C5D4B04 |
| 8086:041e | 1458:d000 | Intel      | 4th Generation Core Proce... | 41    | i915       | 9512600654 |
| 8086:0a16 | 1025:0866 | Intel      | Haswell-ULT Integrated Gr... | 41    | i915       | 3FD761163B |
| 1002:68f9 | 174b:e164 | AMD        | Cedar [Radeon HD 5000/600... | 40    | radeon     | F0615F7666 |
| 10de:11c0 | 1569:11c0 | Nvidia     | GK106 [GeForce GTX 660]      | 40    | nvidia     | F1B384A82B |
| 10de:0a65 | 1462:8094 | Nvidia     | GT218 [GeForce 210]          | 39    | nvidia     | 9632357AEB |
| 8086:0116 | 1043:1682 | Intel      | 2nd Generation Core Proce... | 39    | i915       | A874D7CE23 |
| 8086:041e | 1043:8534 | Intel      | 4th Generation Core Proce... | 38    | i915       | 3D5203A376 |
| 8086:0f31 | 17aa:3909 | Intel      | Atom Processor Z36xxx/Z37... | 38    | i915       | 7D85F9BFAB |
| 1002:98e4 | 1025:1192 | AMD        | Stoney [Radeon R2/R3/R4/R... | 37    | amdgpu     | 17E62D31B9 |
| 10de:1380 | 1043:84bb | Nvidia     | GM107 [GeForce GTX 750 Ti]   | 37    | nouveau    | E82B5BBC50 |
| 10de:1c82 | 1462:8c96 | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 37    | nvidia     | 3AFE42946D |
| 8086:0102 | 1849:0102 | Intel      | 2nd Generation Core Proce... | 37    | i915       | 6D7E3AA70A |
| 8086:0126 | 17aa:21ce | Intel      | 2nd Generation Core Proce... | 37    | i915       | F3FBF8BC70 |
| 8086:0152 | 1849:0152 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 37    | i915       | 39CDF41760 |
| 8086:0156 | 17aa:5011 | Intel      | 3rd Gen Core processor Gr... | 37    | i915       | 82A9861AFD |
| 8086:0166 | 17aa:21f3 | Intel      | 3rd Gen Core processor Gr... | 37    | i915       | B162D0FD81 |
| 8086:2a02 | 17aa:20b5 | Intel      | Mobile GM965/GL960 Integr... | 37    | i915       | 514C92A80A |
| 8086:2a03 | 17aa:20b5 | Intel      | Mobile GM965/GL960 Integr... | 37    |            | 514C92A80A |
| 1002:5a62 | 1043:1402 | AMD        | RC410M [Mobility Radeon X... | 36    | radeon     | 6C6A2138D2 |
| 1a03:2000 | 1a03:2000 | ASPEED ... | ASPEED Graphics Family       | 36    | ast        | A14B2C7156 |
| 8086:0162 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 36    | i915       | 91535E2115 |
| 8086:5912 | 1458:d000 | Intel      | HD Graphics 630              | 36    | i915       | 8F2ECB882C |
| 10de:0641 |           | Nvidia     | G96C [GeForce 9400 GT]       | 35    | nvidia     | 868BBBBB38 |
| 10de:0a20 |           | Nvidia     | GT216 [GeForce GT 220]       | 35    | nouveau    | 5964794E61 |
| 10de:0df5 | 1028:04ca | Nvidia     | GF108M [GeForce GT 525M]     | 35    | nouveau    | E693C5E3B9 |
| 1002:68e0 | 1043:1bf2 | AMD        | Park [Mobility Radeon HD ... | 34    | radeon     | 088FFC2823 |
| 10de:0dc4 |           | Nvidia     | GF106 [GeForce GTS 450]      | 34    | nvidia     | A96BD0FFB8 |
| 8086:0412 | 1849:0412 | Intel      | Xeon E3-1200 v3/4th Gen C... | 34    | i915       | C6B09D560F |
| 8086:a011 | 144d:c072 | Intel      | Atom Processor D4xx/D5xx/... | 34    | i915       | 60127AB94A |
| 8086:a012 | 144d:c072 | Intel      | Atom Processor D4xx/D5xx/... | 34    |            | 60127AB94A |
| 10de:0f00 | 1458:3544 | Nvidia     | GF108 [GeForce GT 630]       | 33    | nouveau    | 9F3A351654 |
| 8086:0116 | 144d:c0b6 | Intel      | 2nd Generation Core Proce... | 33    | i915       | 5118CD27DD |
| 8086:0166 | 17aa:21fa | Intel      | 3rd Gen Core processor Gr... | 33    | i915       | AFB801A018 |

### Input device controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1102:7002 | 1102:0020 | Creativ... | SB Live! Game Port           | 91    | emu10k1_gp | A4AE24CFF8 |
| 1102:7003 | 1102:0040 | Creativ... | SB Audigy Game Port          | 62    | emu10k1_gp | 992938DD51 |
| 1102:7003 | 1102:0060 | Creativ... | SB Audigy Game Port          | 15    | emu10k1_gp | F1B384A82B |
| 1319:0802 | 1319:1319 | Fortemedia | Xwave QS3000A [FM801 game... | 6     | fm801_gp   | 6AB359DC43 |
| 1102:7004 | 1102:1003 | Creativ... | [SB Live! Value] Input de... | 1     | emu10k1_gp | B7C8E17F50 |
| 1102:7005 | 1102:1002 | Creativ... | SB Audigy LS Game Port       | 1     | emu10k1_gp | A8AFE9E221 |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 277   |            | C65ABD0640 |
| 1022:1451 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 162   |            | 4ED3A4A663 |
| 1022:1577 | 103c:8330 | AMD        | Family 15h (Models 60h-6f... | 47    |            | E26638D750 |
| 1022:1577 | 1025:1192 | AMD        | Family 15h (Models 60h-6f... | 37    |            | 17E62D31B9 |
| 1022:15d1 | 103c:84ae | AMD        | Raven/Raven2 IOMMU           | 24    |            | 3B491B92B3 |
| 1022:1481 | 1022:1481 | AMD        | Starship/Matisse IOMMU       | 23    |            | 2E60313B01 |
| 1022:1577 | 103c:84ac | AMD        | Family 15h (Models 60h-6f... | 18    |            | 6EEF4CAED6 |
| 1022:1481 | 1043:87c0 | AMD        | Starship/Matisse IOMMU       | 15    |            | 40061999CC |
| 1022:15d1 | 17aa:3804 | AMD        | Raven/Raven2 IOMMU           | 11    |            | 6206EB1A2F |
| 1022:1577 | 17aa:380e | AMD        | Family 15h (Models 60h-6f... | 10    |            | F9C34FA042 |
| 1022:1451 | 1462:7a38 | AMD        | Family 17h (Models 00h-0f... | 8     |            | DCDA3B1F44 |
| 1022:15d1 | 103c:84e7 | AMD        | Raven/Raven2 IOMMU           | 8     |            | EA1E118AD6 |
| 1022:15d1 | 17aa:3809 | AMD        | Raven/Raven2 IOMMU           | 8     |            | B0FCF85E0D |
| 1022:1451 | 1028:07ee | AMD        | Family 17h (Models 00h-0f... | 7     |            | C708B6ADE4 |
| 1022:15d1 | 1025:125c | AMD        | Raven/Raven2 IOMMU           | 7     |            | B9A37AB909 |
| 1022:15d1 | 17aa:380a | AMD        | Raven/Raven2 IOMMU           | 7     |            | B49AAC1247 |
| 1022:1577 | 1025:109f | AMD        | Family 15h (Models 60h-6f... | 6     |            | A2C937F34C |
| 1022:1577 | 103c:8333 | AMD        | Family 15h (Models 60h-6f... | 6     |            | C4B7195697 |
| 1022:15d1 | 103c:85ea | AMD        | Raven/Raven2 IOMMU           | 6     |            | 4250651580 |
| 1022:1451 | 1462:7c02 | AMD        | Family 17h (Models 00h-0f... | 5     |            | 2E3A02EC4D |
| 1022:1577 | 1028:087e | AMD        | Family 15h (Models 60h-6f... | 5     |            | D72F217DE7 |
| 1022:1577 | 103c:84a0 | AMD        | Family 15h (Models 60h-6f... | 5     |            | B34D6AAB90 |
| 1022:15d1 | 1028:0812 | AMD        | Raven/Raven2 IOMMU           | 5     |            | 90C3D47F26 |
| 1022:15d1 | 103c:84d2 | AMD        | Raven/Raven2 IOMMU           | 5     |            | DFC4334B0C |
| 1022:1423 | 103c:2215 | AMD        | Family 15h (Models 30h-3f... | 4     |            | 40C1857EB1 |
| 1022:1481 | 1462:7b89 | AMD        | Starship/Matisse IOMMU       | 4     |            | D85422E2C1 |
| 1022:1577 | 1025:1087 | AMD        | Family 15h (Models 60h-6f... | 4     |            | D5082D8C3F |
| 1022:1577 | 1028:0769 | AMD        | Family 15h (Models 60h-6f... | 4     |            | 5F8E475ACD |
| 1022:1577 | 103c:81f9 | AMD        | Family 15h (Models 60h-6f... | 4     |            | 832AAFEB1A |
| 1022:1577 | 103c:81fe | AMD        | Family 15h (Models 60h-6f... | 4     |            | B0EAB1E9FE |
| 1022:1577 | 103c:8345 | AMD        | Family 15h (Models 60h-6f... | 4     |            | 7E3B6FA95F |
| 1022:1577 | 103c:84ad | AMD        | Family 15h (Models 60h-6f... | 4     |            | 666B6342E0 |
| 1022:15d1 | 1025:134d | AMD        | Raven/Raven2 IOMMU           | 4     |            | 96D84C0576 |
| 1022:15d1 | 103c:8496 | AMD        | Raven/Raven2 IOMMU           | 4     |            | 31DDC7FDCB |
| 1022:15d1 | 103c:85dd | AMD        | Raven/Raven2 IOMMU           | 4     |            | D6005821D4 |
| 1022:1423 | 1025:0904 | AMD        | Family 15h (Models 30h-3f... | 3     |            | 86472BF81E |
| 1022:1451 | 1462:7b86 | AMD        | Family 17h (Models 00h-0f... | 3     |            | 399E8E20C8 |
| 1022:1577 | 1025:1099 | AMD        | Family 15h (Models 60h-6f... | 3     |            | E8EBAD3A57 |
| 1022:1577 | 1025:1201 | AMD        | Family 15h (Models 60h-6f... | 3     |            | 15574B1FE0 |
| 1022:1577 | 103c:8324 | AMD        | Family 15h (Models 60h-6f... | 3     |            | 47B10CD4F1 |
| 1022:1577 | 1043:8719 | AMD        | Family 15h (Models 60h-6f... | 3     |            | 1BB86FEDE4 |
| 1022:15d1 | 1025:1259 | AMD        | Raven/Raven2 IOMMU           | 3     |            | 32C519104F |
| 1022:1419 | 1019:7c90 | AMD        | Family 15h (Models 10h-1f... | 2     |            | FFB74FCE84 |
| 1022:1419 | 103c:1850 | AMD        | Family 15h (Models 10h-1f... | 2     |            | 898F2B7197 |
| 1022:1419 | 1462:7793 | AMD        | Family 15h (Models 10h-1f... | 2     |            | 30D335A9A4 |
| 1022:1451 | 1028:089a | AMD        | Family 17h (Models 00h-0f... | 2     |            | 6F6209A41E |
| 1022:1451 | 1462:7a40 | AMD        | Family 17h (Models 00h-0f... | 2     |            | A215C93612 |
| 1022:1451 | 1462:7b85 | AMD        | Family 17h (Models 00h-0f... | 2     |            | 053F507950 |
| 1022:1451 | 1462:7b89 | AMD        | Family 17h (Models 00h-0f... | 2     |            | 01693744FC |
| 1022:1577 | 1028:076b | AMD        | Family 15h (Models 60h-6f... | 2     |            | C9DF0EF9CD |
| 1022:1577 | 1028:07e3 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 4EB59BF315 |
| 1022:1577 | 103c:80af | AMD        | Family 15h (Models 60h-6f... | 2     |            | 56448591A2 |
| 1022:1577 | 103c:80b0 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 0FB5C5CC88 |
| 1022:1577 | 103c:8346 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 0E99848A09 |
| 1022:1577 | 103c:84d0 | AMD        | Family 15h (Models 60h-6f... | 2     |            | A2D9BA544F |
| 1022:1577 | 103c:84d1 | AMD        | Family 15h (Models 60h-6f... | 2     |            | E3FF835EA0 |
| 1022:1577 | 103c:84e5 | AMD        | Family 15h (Models 60h-6f... | 2     |            | CE87F391CE |
| 1022:1577 | 103c:85bb | AMD        | Family 15h (Models 60h-6f... | 2     |            | 623C96EC6E |
| 1022:1577 | 17aa:3100 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 47B6DBB479 |
| 1022:15d1 | 1025:1233 | AMD        | Raven/Raven2 IOMMU           | 2     |            | 0CD9D87E92 |
| 1022:15d1 | 1025:134f | AMD        | Raven/Raven2 IOMMU           | 2     |            | 1DE476E789 |
| 1022:15d1 | 1028:08d7 | AMD        | Raven/Raven2 IOMMU           | 2     |            | 2B2912B5B0 |
| 1022:15d1 | 103c:84a2 | AMD        | Raven/Raven2 IOMMU           | 2     |            | 3A1243A77F |
| 1022:15d1 | 103c:85e0 | AMD        | Raven/Raven2 IOMMU           | 2     |            | AD06D7DFA7 |
| 1022:15d1 | 103c:8615 | AMD        | Raven/Raven2 IOMMU           | 2     |            | 6EB4516C09 |
| 1022:15d1 | 17aa:380b | AMD        | Raven/Raven2 IOMMU           | 2     |            | 153F2AFA98 |
| 1002:5a23 | 103c:3324 | AMD        | RD890S/RD990 I/O Memory M... | 1     |            | 7CE46A749E |
| 1002:5a23 | 1462:7893 | AMD        | RD890S/RD990 I/O Memory M... | 1     |            | 837F3B9280 |
| 1022:1419 | 1019:9ac9 | AMD        | Family 15h (Models 10h-1f... | 1     |            | 9DA00E895E |
| 1022:1419 | 103c:2215 | AMD        | Family 15h (Models 10h-1f... | 1     |            | 1B3213CA06 |
| 1022:1423 | 1019:99d3 | AMD        | Family 15h (Models 30h-3f... | 1     |            | CFCBE45B0D |
| 1022:1423 | 1019:9a62 | AMD        | Family 15h (Models 30h-3f... | 1     |            | 06FB58E8EE |
| 1022:1423 | 1019:9ac9 | AMD        | Family 15h (Models 30h-3f... | 1     |            | BED1921035 |
| 1022:1423 | 103c:2263 | AMD        | Family 15h (Models 30h-3f... | 1     |            | A07F8E8315 |
| 1022:1423 | 103c:22a9 | AMD        | Family 15h (Models 30h-3f... | 1     |            | FE059A167E |
| 1022:1423 | 1462:7903 | AMD        | Family 15h (Models 30h-3f... | 1     |            | EADCB61E9F |
| 1022:1423 | 17aa:36a0 | AMD        | Family 15h (Models 30h-3f... | 1     |            | 0D36C8246A |
| 1022:1451 | 1019:9ce5 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 06776696F3 |
| 1022:1451 | 1028:07f9 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 8F7FF50C55 |
| 1022:1451 | 1462:7b90 | AMD        | Family 17h (Models 00h-0f... | 1     |            | C7998D926E |
| 1022:1481 | 1462:7a38 | AMD        | Starship/Matisse IOMMU       | 1     |            | DCB98CB8E2 |
| 1022:1481 | 1462:7c02 | AMD        | Starship/Matisse IOMMU       | 1     |            | E8131440F2 |
| 1022:1481 | 1462:7c35 | AMD        | Starship/Matisse IOMMU       | 1     |            | 9F56AFFC3E |
| 1022:1577 | 1025:095e | AMD        | Family 15h (Models 60h-6f... | 1     |            | 5C4BD87BC9 |
| 1022:1577 | 1025:1372 | AMD        | Family 15h (Models 60h-6f... | 1     |            | F7313E11F8 |
| 1022:1577 | 1028:0855 | AMD        | Family 15h (Models 60h-6f... | 1     |            | DACA9432F8 |
| 1022:1577 | 103c:81aa | AMD        | Family 15h (Models 60h-6f... | 1     |            | D103A0F533 |
| 1022:1577 | 103c:81fd | AMD        | Family 15h (Models 60h-6f... | 1     |            | 7C0F244462 |
| 1022:1577 | 103c:8221 | AMD        | Family 15h (Models 60h-6f... | 1     |            | 99CFD11CA2 |
| 1022:1577 | 103c:8311 | AMD        | Family 15h (Models 60h-6f... | 1     |            | EEE03F79BD |
| 1022:1577 | 103c:8353 | AMD        | Family 15h (Models 60h-6f... | 1     |            | BB4FD376C4 |
| 1022:1577 | 103c:8354 | AMD        | Family 15h (Models 60h-6f... | 1     |            | C75D45BEC4 |
| 1022:1577 | 103c:8357 | AMD        | Family 15h (Models 60h-6f... | 1     |            | F017BDEDF1 |
| 1022:1577 | 103c:863c | AMD        | Family 15h (Models 60h-6f... | 1     |            | AA23459104 |
| 1022:1577 | 17aa:36c6 | AMD        | Family 15h (Models 60h-6f... | 1     |            | 5DA9F63B49 |
| 1022:1577 | 17aa:36ec | AMD        | Family 15h (Models 60h-6f... | 1     |            | C586E918F9 |
| 1022:1577 | 17aa:3806 | AMD        | Family 15h (Models 60h-6f... | 1     |            | B9FC5DC357 |
| 1022:1577 | 17aa:380d | AMD        | Family 15h (Models 60h-6f... | 1     |            | E0F719AEB9 |
| 1022:15d1 | 103c:8497 | AMD        | Raven/Raven2 IOMMU           | 1     |            | D9AF75156B |
| 1022:15d1 | 103c:84a3 | AMD        | Raven/Raven2 IOMMU           | 1     |            | 6A706DA421 |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816c | 17aa:5125 | Realtek... | Virtual IPMI                 | 3     |            | E97740F470 |
| 10ec:816c | 17aa:5122 | Realtek... | Virtual IPMI                 | 2     |            | 971B99D081 |
| 10ec:816c | 17aa:5126 | Realtek... | Virtual IPMI                 | 2     |            | ADEC400398 |
| 10ec:816c | 1019:81ea | Realtek... | Virtual IPMI                 | 1     |            | 06FB58E8EE |
| 10ec:816c | 1025:1248 | Realtek... | Virtual IPMI                 | 1     |            | 688751760E |
| 10ec:816c | 103c:83d5 | Realtek... | Virtual IPMI                 | 1     |            | F648DD0082 |
| 10ec:816c | 103c:83da | Realtek... | Virtual IPMI                 | 1     |            | 607DEE6BBB |
| 10ec:816c | 103c:8401 | Realtek... | Virtual IPMI                 | 1     |            | F2F88AAA9D |
| 10ec:816c | 103c:8626 | Realtek... | Virtual IPMI                 | 1     |            | 9BC7D6303D |
| 10ec:816c | 17aa:511f | Realtek... | Virtual IPMI                 | 1     |            | E0363562B7 |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 103c:3302 | 103c:3305 | Hewlett... | Integrated Lights-Out Sta... | 10    | ipmi_si    | DF7A5AC424 |
| 10ec:816c | 1458:e000 | Realtek... | Virtual IPMI                 | 4     | ipmi_si    | 02A7674592 |
| 10ec:816c | 1734:1178 | Realtek... | Virtual IPMI                 | 3     | ipmi_si    | F9847F8DC5 |
| 10ec:816c | 17aa:3089 | Realtek... | Virtual IPMI                 | 3     | ipmi_si    | D9A1939AB2 |
| 10ec:816c | 10ec:8168 | Realtek... | Virtual IPMI                 | 2     | ipmi_si    | 5DD127A865 |
| 10ec:816c | 1025:078b | Realtek... | Virtual IPMI                 | 1     |            | 087F924E20 |
| 10ec:816c | 1043:8578 | Realtek... | Virtual IPMI                 | 1     | ipmi_si    | C248800623 |
| 10ec:816c | 10ec:816c | Realtek... | Virtual IPMI                 | 1     |            | 71F9B6C386 |
| 10ec:816c | 17aa:30b2 | Realtek... | Virtual IPMI                 | 1     | ipmi_si    | 36635F76F9 |
| 8086:108e | 8086:0000 | Intel      | 82573E KCS (Active Manage... | 1     | ipmi_si    | 1960567A11 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a121 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 238   |            | B8C562A7E5 |
| 10de:03f5 | 1849:03eb | Nvidia     | MCP61 Memory Controller      | 223   |            | EC1F6C8A0B |
| 8086:a36f | 8086:7270 | Intel      | Cannon Lake PCH Shared SRAM  | 214   |            | A47D005445 |
| 10de:03e2 | 1849:03e2 | Nvidia     | MCP61 Host Bridge            | 207   |            | EC1F6C8A0B |
| 8086:a121 | 1458:5001 | Intel      | 100 Series/C230 Series Ch... | 138   |            | 4015843475 |
| 10de:03f5 | 1458:0c11 | Nvidia     | MCP61 Memory Controller      | 118   |            | 53DB8982F5 |
| 8086:a2a1 | 1458:5001 | Intel      | 200 Series/Z370 Chipset F... | 92    |            | 8F2ECB882C |
| 8086:a2a1 | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 88    |            | 345BBA3C1F |
| 10de:03ea | 1043:8234 | Nvidia     | MCP61 Memory Controller      | 82    |            | F3B22A675A |
| 10de:03f5 | 1043:8234 | Nvidia     | MCP61 Memory Controller      | 82    |            | F3B22A675A |
| 10de:03ea | 10de:cb84 | Nvidia     | MCP61 Memory Controller      | 78    |            | C7E1B7CEC0 |
| 10de:03e2 | 1043:83a4 | Nvidia     | MCP61 Host Bridge            | 77    |            | A6BD4DA213 |
| 10de:03f5 | 1043:83a4 | Nvidia     | MCP61 Memory Controller      | 77    |            | A6BD4DA213 |
| 10de:03ea | 1458:5001 | Nvidia     | MCP61 Memory Controller      | 66    |            | B1D7110D4D |
| 8086:9d21 | 8086:7270 | Intel      | Sunrise Point-LP PMC         | 66    |            | C96C722A74 |
| 10de:005e | 1043:815a | Nvidia     | CK804 Memory Controller      | 60    |            | FD8F010178 |
| 10de:0a88 |           | Nvidia     | MCP79 Memory Controller      | 58    |            | 441575D073 |
| 8086:a121 | 1849:a121 | Intel      | 100 Series/C230 Series Ch... | 53    |            | 0E4F08FCA3 |
| 8086:a36f | 1043:8694 | Intel      | Cannon Lake PCH Shared SRAM  | 53    |            | 0B771C098E |
| 10de:03e2 | 1458:5001 | Nvidia     | MCP61 Host Bridge            | 52    |            | 53DB8982F5 |
| 10de:0a89 |           | Nvidia     | MCP79 Memory Controller      | 51    |            | 441575D073 |
| 10de:0aa4 |           | Nvidia     | MCP79 Memory Controller      | 51    |            | 441575D073 |
| 8086:9def | 8086:7270 | Intel      | Cannon Point-LP Shared SRAM  | 49    |            | 24F8864FB8 |
| 10de:0a98 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 48    |            | 441575D073 |
| 10de:03f5 | 1462:7309 | Nvidia     | MCP61 Memory Controller      | 46    |            | 93E77F9DC3 |
| 10de:0a88 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 41    |            | F5C8A70507 |
| 10de:0a89 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 41    |            | F5C8A70507 |
| 10de:03f5 | 1565:3407 | Nvidia     | MCP61 Memory Controller      | 38    |            | 1004AD3220 |
| 10de:0444 | 1462:7369 | Nvidia     | MCP65 Memory Controller      | 38    |            | 9DF2C0E0DD |
| 10de:0445 | 1462:7369 | Nvidia     | MCP65 Memory Controller      | 38    |            | 9DF2C0E0DD |
| 10de:0568 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 38    |            | AFF249E34F |
| 10de:0751 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 38    |            | AFF249E34F |
| 10de:0754 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 38    |            | AFF249E34F |
| 10de:0369 | 1043:8239 | Nvidia     | MCP55 Memory Controller      | 36    |            | 44E3D900F5 |
| 8086:9d21 | 17aa:3872 | Intel      | Sunrise Point-LP PMC         | 33    |            | 91D8C5CEC3 |
| 8086:a2a1 | 1849:a2a1 | Intel      | 200 Series/Z370 Chipset F... | 33    |            | 1BB0C8F064 |
| 10de:03a9 |           | Nvidia     | C55 Memory Controller        | 31    |            | 15EA243CBA |
| 10de:03aa |           | Nvidia     | C55 Memory Controller        | 31    |            | 15EA243CBA |
| 10de:03ab |           | Nvidia     | C55 Memory Controller        | 31    |            | 15EA243CBA |
| 10de:03b4 |           | Nvidia     | C55 Memory Controller        | 31    |            | 15EA243CBA |
| 10de:03bc |           | Nvidia     | C55 Memory Controller        | 31    |            | 15EA243CBA |
| 10de:0541 | 10de:cb84 | Nvidia     | MCP67 Memory Controller      | 31    |            | 590A68AE68 |
| 8086:9d21 | 1025:1193 | Intel      | Sunrise Point-LP PMC         | 31    | intel_p... | 02EEEC88C4 |
| 8086:a2a1 | 1043:872f | Intel      | 200 Series/Z370 Chipset F... | 31    |            | 6AA8E0B9B0 |
| 10de:03a8 |           | Nvidia     | C55 Memory Controller        | 29    |            | 15EA243CBA |
| 10de:03ac |           | Nvidia     | C55 Memory Controller        | 29    |            | 15EA243CBA |
| 10de:03ad |           | Nvidia     | C55 Memory Controller        | 29    |            | 15EA243CBA |
| 10de:03ae |           | Nvidia     | C55 Memory Controller        | 29    |            | 15EA243CBA |
| 10de:03af |           | Nvidia     | C55 Memory Controller        | 29    |            | 15EA243CBA |
| 10de:03b0 |           | Nvidia     | C55 Memory Controller        | 29    |            | 15EA243CBA |
| 10de:03b1 |           | Nvidia     | C55 Memory Controller        | 29    |            | 15EA243CBA |
| 10de:03b2 |           | Nvidia     | C55 Memory Controller        | 29    |            | 15EA243CBA |
| 10de:03b3 |           | Nvidia     | C55 Memory Controller        | 29    |            | 15EA243CBA |
| 10de:03b5 |           | Nvidia     | C55 Memory Controller        | 29    |            | 15EA243CBA |
| 10de:03b6 |           | Nvidia     | C55 Memory Controller        | 29    |            | 15EA243CBA |
| 10de:03ba |           | Nvidia     | C55 Memory Controller        | 29    |            | 15EA243CBA |
| 8086:9d21 | 1025:1085 | Intel      | Sunrise Point-LP PMC         | 29    | intel_p... | 8BC74BD7FB |
| 8086:a121 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 29    |            | 53CD422052 |
| 8086:a36f | 1849:a36f | Intel      | Cannon Lake PCH Shared SRAM  | 28    |            | B0161E1E77 |
| 8086:9d21 | 1025:115f | Intel      | Sunrise Point-LP PMC         | 27    | intel_p... | A230640EC7 |
| 8086:9def |           | Intel      | Cannon Point-LP Shared SRAM  | 27    |            | 7C5B2D05AE |
| 10de:0568 | 1849:0568 | Nvidia     | MCP78S [GeForce 8200] Mem... | 26    |            | 41F3167FB7 |
| 10de:0751 | 1849:0751 | Nvidia     | MCP78S [GeForce 8200] Mem... | 26    |            | 41F3167FB7 |
| 10de:0754 | 1849:0754 | Nvidia     | MCP78S [GeForce 8200] Mem... | 26    |            | 41F3167FB7 |
| 8086:9d21 | 103c:832a | Intel      | Sunrise Point-LP PMC         | 26    |            | 931D7104FA |
| 8086:9d21 | 8086:9d21 | Intel      | Sunrise Point-LP PMC         | 25    | intel_p... | A43311F999 |
| 8086:a36f | 1025:1264 | Intel      | Cannon Lake PCH Shared SRAM  | 24    |            | AF51F8907E |
| 8086:a36f | 1028:087c | Intel      | Cannon Lake PCH Shared SRAM  | 24    |            | 18DC19F3EC |
| 10de:0568 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] Mem... | 23    |            | D672B4583E |
| 10de:0754 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] Mem... | 23    |            | D672B4583E |
| 8086:9d21 | 103c:8079 | Intel      | Sunrise Point-LP PMC         | 23    |            | BCF0EBFEDD |
| 8086:9d21 | 1043:1a00 | Intel      | Sunrise Point-LP PMC         | 22    | intel_p... | 8C29A78852 |
| 10de:03ea | 103c:2a6c | Nvidia     | MCP61 Memory Controller      | 21    |            | 6D882902AD |
| 10de:03f5 | 103c:2a6c | Nvidia     | MCP61 Memory Controller      | 21    |            | 6D882902AD |
| 8086:9def | 8086:2074 | Intel      | Cannon Point-LP Shared SRAM  | 21    |            | B039AEFD9E |
| 10de:0270 | 1043:81c0 | Nvidia     | MCP51 Host Bridge            | 20    |            | A26BD26890 |
| 10de:0547 | 1025:0126 | Nvidia     | MCP67 Memory Controller      | 20    |            | 590A68AE68 |
| 10de:0568 |           | Nvidia     | MCP78S [GeForce 8200] Mem... | 20    |            | 1F04FD556B |
| 10de:0751 | 10de:cb84 | Nvidia     | MCP78S [GeForce 8200] Mem... | 20    |            | 1F04FD556B |
| 8086:9d21 | 17aa:3816 | Intel      | Sunrise Point-LP PMC         | 20    |            | 3493C4EBA1 |
| 8086:9d21 | 17aa:5068 | Intel      | Sunrise Point-LP PMC         | 20    |            | F4826C3A2A |
| 8086:a121 | 1462:7a15 | Intel      | 100 Series/C230 Series Ch... | 20    |            | 73BFD283E5 |
| 10de:0369 | 1462:7250 | Nvidia     | MCP55 Memory Controller      | 19    |            | C862E6269E |
| 10de:0d68 |           | Nvidia     | MCP89 Memory Controller      | 19    |            | 303C043B8B |
| 10de:0d69 |           | Nvidia     | MCP89 Memory Controller      | 19    |            | 303C043B8B |
| 10de:0d6d |           | Nvidia     | MCP89 Memory Controller      | 19    |            | 303C043B8B |
| 10de:0d6e |           | Nvidia     | MCP89 Memory Controller      | 19    |            | 303C043B8B |
| 10de:0d6f |           | Nvidia     | MCP89 Memory Controller      | 19    |            | 303C043B8B |
| 10de:0d70 |           | Nvidia     | MCP89 Memory Controller      | 19    |            | 303C043B8B |
| 10de:0d71 |           | Nvidia     | MCP89 Memory Controller      | 19    |            | 303C043B8B |
| 10de:0d72 |           | Nvidia     | MCP89 Memory Controller      | 19    |            | 303C043B8B |
| 10de:0d75 |           | Nvidia     | MCP89 Memory Controller      | 19    |            | 303C043B8B |
| 10de:0d7b |           | Nvidia     | MCP89 Memory Controller      | 19    |            | 303C043B8B |
| 8086:9d21 | 1028:07e6 | Intel      | Sunrise Point-LP PMC         | 19    | intel_p... | C26F2A8CCF |
| 8086:9def | 1028:08af | Intel      | Cannon Point-LP Shared SRAM  | 19    |            | ED8598DB62 |
| 10de:0272 | 1043:81c0 | Nvidia     | MCP51 Memory Controller 0    | 18    |            | A26BD26890 |
| 10de:027e | 1043:81c0 | Nvidia     | C51 Memory Controller 2      | 18    |            | A26BD26890 |
| 10de:027f | 1043:81c0 | Nvidia     | C51 Memory Controller 3      | 18    |            | A26BD26890 |
| 10de:02f0 | 1043:81c0 | Nvidia     | C51 Host Bridge              | 18    |            | A26BD26890 |
| 10de:02f8 | 1043:81c0 | Nvidia     | C51 Memory Controller 5      | 18    |            | A26BD26890 |

### Modem (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 11c1:044c | 11c1:044c | LSI        | LT WinModem                  | 13    |            | 461D79E9EB |
| 8086:266d | 14f1:5423 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 13    | snd_int... | 18E748759E |
| 1057:3052 | 1057:3020 | Motorola   | SM56 Data Fax Modem          | 10    |            | F60B0BE33D |
| 8086:24c6 | 14f1:5422 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 10    | snd_int... | 4EBB330BF9 |
| 8086:266d | 1179:0001 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 10    | snd_int... | 8488B3D0B9 |
| 1106:3068 |           | VIA Tec... | AC'97 Modem Controller       | 9     | snd_via... | D20509CA50 |
| 8086:266d | 1025:006a | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 7     | snd_int... | 77353D6C03 |
| 8086:266d | 103c:099c | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 6     | snd_int... | E0DF895DC8 |
| 8086:266d | 1014:0574 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 5     | snd_int... | BABCA7BCDE |
| 8086:266d | 1025:0066 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 5     | snd_int... | 50122B9E8E |
| 134d:7892 | 134d:0001 | PCTel      | HSP MicroModem 56            | 4     | serial     | 6C9B4F5E0B |
| 8086:1040 | 8086:1000 | Intel      | 536EP Data Fax Modem         | 4     |            | 1263C61735 |
| 1002:434d | 144d:2115 | AMD        | SB200 AC97 Modem Controller  | 3     | snd_ati... | 80073ED5E9 |
| 1002:4378 | 103c:30a4 | AMD        | IXP SB400 AC'97 Modem Con... | 3     | snd_ati... | CCEED80795 |
| 1002:4378 | 1043:1186 | AMD        | IXP SB400 AC'97 Modem Con... | 3     | snd_ati... | 08E7796666 |
| 1039:7013 | 1025:0083 | Silicon... | AC'97 Modem Controller       | 3     |            | 94017E086A |
| 1039:7013 | 1043:1816 | Silicon... | AC'97 Modem Controller       | 3     | snd_int... | C4EBB5D061 |
| 1106:3068 | 1019:0c04 | VIA Tec... | AC'97 Modem Controller       | 3     | snd_via... | 7AA84DA312 |
| 8086:24c6 | 1014:055a | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 3     | snd_int... | A538D3F64D |
| 8086:266d | 103c:0944 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 3     | snd_int... | A770CF025E |
| 8086:266d | 103c:309d | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 3     | snd_int... | 837230178B |
| 8086:266d | 144d:2115 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 3     | snd_int... | 88BAF3B388 |
| 1002:4378 | 103c:3085 | AMD        | IXP SB400 AC'97 Modem Con... | 2     | snd_ati... | 215D2A28A4 |
| 1002:4378 | 103c:308b | AMD        | IXP SB400 AC'97 Modem Con... | 2     | snd_ati... | 7945895A4E |
| 1002:4378 | 103c:3091 | AMD        | IXP SB400 AC'97 Modem Con... | 2     | snd_ati... | 30D7D605F7 |
| 1002:4378 | 1734:1092 | AMD        | IXP SB400 AC'97 Modem Con... | 2     | snd_ati... | 4D0D913872 |
| 8086:2486 | 1179:0001 | Intel      | 82801CA/CAM AC'97 Modem C... | 2     | snd_int... | A79789524B |
| 8086:2486 | 134d:4c21 | Intel      | 82801CA/CAM AC'97 Modem C... | 2     |            | 38C172234D |
| 8086:24c6 | 1014:0559 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 2     | snd_int... | 1811B66E00 |
| 8086:24c6 | 1071:8089 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 2     | snd_int... | 227BF1BA1D |
| 8086:24c6 | 10cf:10d1 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 2     | snd_int... | EA732BEA27 |
| 8086:24c6 | 1179:0001 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 2     | snd_int... | B36ADF3084 |
| 8086:24c6 | 1179:ff31 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 2     | snd_int... | E9BD04F647 |
| 8086:266d | 1014:0576 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 2     | snd_int... | 9809E004BA |
| 8086:266d | 103c:0934 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 2     |            | 16F00AAE37 |
| 8086:266d | 103c:3080 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 2     | snd_int... | 0572E8425C |
| 8086:266d | 103c:30c4 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 2     | snd_int... | 87F8EF65AE |
| 1002:434d | 1025:0052 | AMD        | SB200 AC97 Modem Controller  | 1     | snd_ati... | 856DF8910C |
| 1002:4378 | 1025:007e | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | FAC1D78802 |
| 1002:4378 | 1025:0080 | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 00FDC7C100 |
| 1002:4378 | 103c:309b | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 88BD859F3F |
| 1002:4378 | 103c:30ae | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 347BF6C627 |
| 1002:4378 | 1179:0001 | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 184C93E6DD |
| 1002:4378 | 1179:ff31 | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 563F05AAE7 |
| 1002:4378 | 1462:0131 | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 21B7740691 |
| 1002:4378 | 1734:1098 | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 0328C9BAD3 |
| 1039:7013 | 104d:8128 | Silicon... | AC'97 Modem Controller       | 1     | snd_int... | 72A578315E |
| 1039:7013 | 104d:814e | Silicon... | AC'97 Modem Controller       | 1     | snd_int... | 88ABDEBE09 |
| 1057:3052 | 1631:3034 | Motorola   | SM56 Data Fax Modem          | 1     |            | B7CEC1644D |
| 10b9:5457 | 103c:0850 | ULi Ele... | M5457 AC'97 Modem Controller | 1     |            | 4E9D284D9C |
| 10b9:5457 | 104d:8158 | ULi Ele... | M5457 AC'97 Modem Controller | 1     |            | 2BA72A0486 |
| 10de:00d9 | 103c:006d | Nvidia     | nForce3 Audio                | 1     |            | E1BAA5BDE6 |
| 10de:00d9 | 1043:1856 | Nvidia     | nForce3 Audio                | 1     | snd_int... | 655ACF5FA6 |
| 1106:3068 | 1019:2122 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 25BB71984B |
| 1106:3068 | 1025:0046 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 80E120B3A5 |
| 1106:3068 | 1071:8666 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 179169EE59 |
| 1106:3068 | 1071:8889 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | E801E7B52C |
| 1106:3068 | 1734:1054 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | A9DE326D18 |
| 1106:3068 | 1734:10ab | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | BEA6F4F694 |
| 1106:3068 | 1734:10ae | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 06ECBD156A |
| 11c1:0440 | 11c1:0440 | LSI        | 56k WinModem                 | 1     |            | 6B2E5020C2 |
| 11c1:0449 | 1468:0410 | LSI        | L56xM+S [Mars-2] WinModem... | 1     |            | A8A13EFBA0 |
| 11c1:044e | 11c1:044e | LSI        | LT WinModem                  | 1     |            | 6203763CC5 |
| 11c1:044e | 1235:044e | LSI        | LT WinModem                  | 1     |            | 3D74179CB7 |
| 11c1:044e | 13e0:0401 | LSI        | LT WinModem                  | 1     |            | E9ACA9663F |
| 11c1:0450 | 144f:1515 | LSI        | LT WinModem                  | 1     |            | 32D5B1A614 |
| 11c1:045c | 8086:2205 | LSI        | LT WinModem                  | 1     | serial     | 1B54E25E77 |
| 1543:3052 | 1543:3000 | SILICON... | Intel 537 [Winmodem]         | 1     |            | 75C969D54B |
| 163c:3052 | 14fe:0005 | Smart Link | SmartLink SmartPCI562 56K... | 1     | serial     | 9939882441 |
| 2000:2800 | 163c:2800 | Smart Link | SmartPCI2800 V.92 PCI Sof... | 1     |            | 9DEE04D2CB |
| 2003:8800 | 16ef:2800 | Smart Link | LM-I56N                      | 1     |            | 8B4AE6CF41 |
| 2003:8800 | 1801:2800 | Smart Link | LM-I56N                      | 1     |            | 413AE4FF4F |
| 8086:1080 | 1028:1000 | Intel      | FA82537EP 56K V.92 Data/F... | 1     | serial     | 0E73DD68E2 |
| 8086:1080 | 8086:1000 | Intel      | FA82537EP 56K V.92 Data/F... | 1     | serial     | 6DF95E6042 |
| 8086:2446 | 1025:1027 | Intel      | 82801BA/BAM AC'97 Modem C... | 1     |            | E0A83557FF |
| 8086:2486 | 1014:0223 | Intel      | 82801CA/CAM AC'97 Modem C... | 1     | snd_int... | 3EA811E273 |
| 8086:2486 | 14c0:0012 | Intel      | 82801CA/CAM AC'97 Modem C... | 1     | snd_int... | A8AF42D6E7 |
| 8086:2486 | 14f1:5421 | Intel      | 82801CA/CAM AC'97 Modem C... | 1     |            | 4F9273C63C |
| 8086:24c6 | 1014:0524 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | BE49E35FA4 |
| 8086:24c6 | 1025:0071 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | BBE6DD58A1 |
| 8086:24c6 | 103c:08b0 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 316E375A5C |
| 8086:24c6 | 103c:3080 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | 6802B34FDD |
| 8086:24c6 | 103c:3084 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | 24A093E347 |
| 8086:24c6 | 1043:1826 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | B5CB46FFBA |
| 8086:24c6 | 104d:818c | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 7274BBB49F |
| 8086:24c6 | 1071:a001 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 9D5A19DCF4 |
| 8086:24c6 | 144d:2115 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 529607257E |
| 8086:24c6 | 144d:c00c | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 8BCCDD8350 |
| 8086:24c6 | 14c0:0012 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 8F733593DB |
| 8086:24c6 | 152d:0707 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 81347CD6BB |
| 8086:24c6 | 1734:103c | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | 6F452862B4 |
| 8086:24d6 | 1025:0045 | Intel      | 82801EB/ER (ICH5/ICH5R) A... | 1     |            | 41CC7EB08C |
| 8086:24d6 | 1043:177d | Intel      | 82801EB/ER (ICH5/ICH5R) A... | 1     | snd_int... | 116C24A4D7 |
| 8086:24d6 | 1179:0001 | Intel      | 82801EB/ER (ICH5/ICH5R) A... | 1     |            | A7D4DEEF9E |
| 8086:266d | 1025:007a | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     | snd_int... | E4219525B9 |
| 8086:266d | 103c:3081 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     |            | 1481661DEB |
| 8086:266d | 103c:3082 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     |            | 91C7AE2180 |
| 8086:266d | 107b:0460 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     |            | B62ECA10E8 |
| 8086:266d | 1179:ff31 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     | snd_int... | 8E0AD23326 |
| 8086:266d | 1462:0121 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     | snd_int... | 7A44DA1E2F |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 148   | intel_a... | AE477CA654 |
| 14e4:1570 | 14e4:1570 | Broadco... | 720p FaceTime HD Camera      | 42    | bdc_pci    | 1A26D7B485 |
| 8086:1919 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 34    | ipu3_imgu  | A43311F999 |
| 8086:9d32 | 8086:7270 | Intel      | Skylake-U/Y Camera IO Hos... | 31    | ipu3_cio2  | 85085D7FF6 |
| 1022:15e2 | 1022:15e2 | AMD        | Raven/Raven2/FireFlight/R... | 26    | snd_pci... | 9809687258 |
| 1022:15e2 | 103c:84ae | AMD        | Raven/Raven2/FireFlight/R... | 24    | snd_pci... | 3B491B92B3 |
| 109e:0878 |           | Brooktree  | Bt878 Audio Capture          | 18    |            | 80274F5B0C |
| 8086:5a88 |           | Intel      | Celeron N3350/Pentium N42... | 17    |            | 0BEDF4D656 |
| 8086:22b8 | 1297:2063 | Intel      | Atom/Celeron/Pentium Proc... | 10    | intel_a... | EBFA71DD99 |
| 11bd:bede | 11bd:0022 | Pinnacl... | AV/DV Studio Capture Card    | 9     |            | 12C434B6C4 |
| 109e:0878 | 1461:0003 | Brooktree  | Bt878 Audio Capture          | 8     | snd_bt87x  | 48378AE22B |
| 1131:7160 | 1461:1455 | Philips... | SAA7160                      | 8     |            | 8D0B9127EF |
| 1131:7231 | 5ace:8000 | Philips... | SAA7231                      | 8     |            | FA070462FC |
| 14e4:1615 | 14e4:1615 | Broadco... | BCM70015 Video Decoder [C... | 8     |            | 9910E4B9BB |
| 8086:0f38 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 8     | intel_a... | 0A96B79D5F |
| 8086:22b8 | 17aa:3809 | Intel      | Atom/Celeron/Pentium Proc... | 8     | intel_a... | 069BD7BAEB |
| 1022:15e2 | 17aa:3812 | AMD        | Raven/Raven2/FireFlight/R... | 7     | snd_pci... | B49AAC1247 |
| 1022:15e2 | 103c:85ea | AMD        | Raven/Raven2/FireFlight/R... | 6     | snd_pci... | 4250651580 |
| 1022:15e2 | 17aa:380b | AMD        | Raven/Raven2/FireFlight/R... | 6     | snd_pci... | B0FCF85E0D |
| 1022:15e2 | 17aa:3814 | AMD        | Raven/Raven2/FireFlight/R... | 6     | snd_pci... | C65ABD0640 |
| 1131:7231 | 1461:2a0f | Philips... | SAA7231                      | 6     |            | FF848E7FFB |
| 8086:0f38 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 6     | atomisp    | 362FB52DD0 |
| 8086:22b8 | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 6     | intel_a... | 53194E03EE |
| 8086:22b8 | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 6     | intel_a... | 725940B944 |
| 8086:22b8 | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 6     | intel_a... | 4CCE625762 |
| 1022:15e2 | 103c:84d2 | AMD        | Raven/Raven2/FireFlight/R... | 5     | snd_pci... | DFC4334B0C |
| 1022:15e2 | 19e5:3e06 | AMD        | Raven/Raven2/FireFlight/R... | 5     | snd_pci... | 85DF07509C |
| 109e:0878 | 0070:13eb | Brooktree  | Bt878 Audio Capture          | 5     | snd_bt87x  | A43E9D5913 |
| 1131:7164 | 0070:8851 | Philips... | SAA7164                      | 5     | saa7164    | 54C8F90B14 |
| 1131:7231 | 1461:1400 | Philips... | SAA7231                      | 5     |            | 4F99536247 |
| 8086:1919 | 8086:1919 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 5     | ipu3_imgu  | EFCA370E75 |
| 8086:22b8 | 103c:813e | Intel      | Atom/Celeron/Pentium Proc... | 5     | intel_a... | 43F9ACD60A |
| 8086:9d32 | 8086:9d32 | Intel      | Skylake-U/Y Camera IO Hos... | 5     | ipu3_cio2  | EFCA370E75 |
| 1002:ac12 | 12ab:0003 | AMD        | Theater HD T507 (DVB-T) T... | 4     |            | EA55AE13AC |
| 1022:15e2 | 1025:134d | AMD        | Raven/Raven2/FireFlight/R... | 4     | snd_pci... | 96D84C0576 |
| 1022:15e2 | 103c:85dd | AMD        | Raven/Raven2/FireFlight/R... | 4     | snd_pci... | D6005821D4 |
| 1022:15e2 | 17aa:5124 | AMD        | Raven/Raven2/FireFlight/R... | 4     | snd_pci... | 883C27612D |
| 14e4:1612 | 14e4:2612 | Broadcom   | BCM70012 Video Decoder [C... | 4     |            | 5495F2E86E |
| 8086:9d32 |           | Intel      | Skylake-U/Y Camera IO Hos... | 4     | ipu3_cio2  | 2D71938FC4 |
| 1022:15e2 | 103c:8433 | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | D1E501DD66 |
| 1022:15e2 | 103c:8496 | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | 53B6114671 |
| 1022:15e2 | 17aa:5125 | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | E97740F470 |
| 1022:15e2 | 19e5:3e10 | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | 53631F5F96 |
| 109e:0878 | 107d:6609 | Brooktree  | Bt878 Audio Capture          | 3     |            | 4A6B13BAEA |
| 1131:7160 | 1461:2655 | Philips... | SAA7160                      | 3     |            | A74B989748 |
| 1131:7162 | 11bd:0100 | Philips... | SAA7162                      | 3     |            | EF8A743A1E |
| 1131:7231 | 1461:7983 | Philips... | SAA7231                      | 3     |            | 6186ACA9BB |
| 1131:7231 | 5ace:8201 | Philips... | SAA7231                      | 3     |            | 75F255A4E2 |
| 14e4:1615 | 105b:0d77 | Broadcom   | BCM70015 Video Decoder [C... | 3     |            | B036D312E6 |
| 14f1:8804 | 0070:6902 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     |            | B4A53FAFC1 |
| 14f1:8804 | 0070:9002 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     |            | 9531621804 |
| 1822:4e35 | 153b:1179 | Twinhan... | Mantis DTV PCI Bridge Con... | 3     | mantis     | C6B223FD61 |
| 1822:4e35 | 1822:0031 | Twinhan... | Mantis DTV PCI Bridge Con... | 3     | mantis     | 24636D8ED6 |
| 8086:1919 | 1028:07a4 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | ipu3_imgu  | 73B87C222F |
| 8086:1919 | 17aa:382f | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     |            | 1DD80D33E5 |
| 8086:22b8 | 1043:1c60 | Intel      | Atom/Celeron/Pentium Proc... | 3     | intel_a... | 5FCF1662DB |
| 8086:22b8 | 17aa:38e3 | Intel      | Atom/Celeron/Pentium Proc... | 3     | intel_a... | B276E5AAD5 |
| 8086:9d32 | 1028:07a4 | Intel      | Skylake-U/Y Camera IO Hos... | 3     | ipu3_cio2  | 73B87C222F |
| 8086:9d32 | 17aa:380c | Intel      | Skylake-U/Y Camera IO Hos... | 3     | ipu3_cio2  | 1DD80D33E5 |
| 1022:15e2 | 1025:1233 | AMD        | Raven/Raven2/FireFlight/R... | 2     | snd_pci... | 0CD9D87E92 |
| 1022:15e2 | 1025:134f | AMD        | Raven/Raven2/FireFlight/R... | 2     | snd_pci... | 1DE476E789 |
| 1022:15e2 | 103c:8434 | AMD        | Raven/Raven2/FireFlight/R... | 2     |            | E2E650868B |
| 1022:15e2 | 103c:84a2 | AMD        | Raven/Raven2/FireFlight/R... | 2     | snd_pci... | 3A1243A77F |
| 1022:15e2 | 17aa:3813 | AMD        | Raven/Raven2/FireFlight/R... | 2     | snd_pci... | 153F2AFA98 |
| 1022:15e2 | 17aa:5126 | AMD        | Raven/Raven2/FireFlight/R... | 2     | snd_pci... | ADEC400398 |
| 109e:0878 | 11bd:0012 | Brooktree  | Bt878 Audio Capture          | 2     | snd_bt87x  | AB36F565A4 |
| 109e:0878 | 1461:0004 | Brooktree  | Bt878 Audio Capture          | 2     |            | F2B7867CAA |
| 1131:7160 | 1461:0555 | Philips... | SAA7160                      | 2     |            | D400943350 |
| 1131:7160 | 1461:0855 | Philips... | SAA7160                      | 2     |            | BBDA8BED86 |
| 1131:7160 | 1461:0955 | Philips... | SAA7160                      | 2     |            | D6813FBC7C |
| 1131:7160 | 1461:0a55 | Philips... | SAA7160                      | 2     |            | 99DDBBF195 |
| 1131:7160 | 1461:1855 | Philips... | SAA7160                      | 2     |            | FA070462FC |
| 1131:7160 | 1ae4:0700 | Philips... | SAA7160                      | 2     |            | E9FCA3B9C8 |
| 1131:7231 | 12ab:0762 | Philips... | SAA7231                      | 2     |            | 6DFEC77A25 |
| 1131:7231 | 12ab:0763 | Philips... | SAA7231                      | 2     |            | 6F6F611F59 |
| 1131:7231 | 1461:0b0f | Philips... | SAA7231                      | 2     |            | 791CA50070 |
| 1131:7231 | 16be:0008 | Philips... | SAA7231                      | 2     |            | 1BA5C50EAD |
| 1131:7231 | 5ace:8150 | Philips... | SAA7231                      | 2     |            | 8603D5BDF5 |
| 11bd:bede | 11bd:0023 | Pinnacl... | AV/DV Studio Capture Card    | 2     |            | EBD8A5801D |
| 14f1:8804 | 0070:6906 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     |            | BCEE476272 |
| 14f1:8804 | 1822:0023 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     |            | AB36F565A4 |
| 1822:4e35 | 153b:1178 | Twinhan... | Mantis DTV PCI Bridge Con... | 2     | mantis     | B7812DD3C1 |
| 1822:4e35 | 1ae4:0002 | Twinhan... | Mantis DTV PCI Bridge Con... | 2     | mantis     | CCB302179F |
| 1822:4e35 | 1ae4:0003 | Twinhan... | Mantis DTV PCI Bridge Con... | 2     | mantis     | DA1E5854E0 |
| 8086:1919 | 1025:111e | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     |            | 2D71938FC4 |
| 8086:1919 | 152d:1182 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     |            | 5D3C8DA69A |
| 8086:22b8 | 1043:1bdd | Intel      | Atom/Celeron/Pentium Proc... | 2     | intel_a... | 40D8D33EF9 |
| 8086:22b8 | 17aa:222a | Intel      | Atom/Celeron/Pentium Proc... | 2     | intel_a... | DF76656467 |
| dd01:0003 | dd01:0030 | Digital... | Octopus DVB Adapter          | 2     | ddbridge   | B4A53FAFC1 |
| 0002:8290 | 107d:2609 |            | Multimedia controller        | 1     |            | 95D420F37F |
| 1002:4d51 | 1002:b041 | AMD        | Unified AVStream Driver      | 1     |            | 2CF316774E |
| 1002:ac12 | 1002:b539 | AMD        | Theater HD T507 (DVB-T) T... | 1     |            | DD5E0979B0 |
| 1002:ad18 | 1682:ad18 | AMD        | Multimedia controller        | 1     |            | 3108FE53D3 |
| 1022:15e2 | 103c:84a3 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | 6A706DA421 |
| 1022:15e2 | 103c:84af | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | 2D5F51CDD8 |
| 1022:15e2 | 103c:85b3 | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | 766B0474A3 |
| 1022:15e2 | 103c:85de | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | 70F1D3BF36 |
| 1022:15e2 | 103c:85e0 | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | CA237442E2 |
| 1022:15e2 | 17aa:36f5 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | 7E41940C9C |
| 1022:15e2 | 17aa:3811 | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | 0A0728CD41 |

### Multiport serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1fd4:1999 | 1fd4:0002 | SUNIX      | Multiport serial controller  | 5     | serial     | D577562AE7 |
| 135c:0170 | 135c:0170 | Quatech    | QSCLP-100                    | 1     | serial     | 05DF269988 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8168 | 1458:e000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2314  | r8169      | A056C6C7D5 |
| 10ec:8168 | 1849:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 842   | r8169      | C0D7396586 |
| 10ec:8168 | 1043:8505 | Realtek... | RTL8111/8168/8411 PCI Exp... | 793   | r8169      | 13AF031E5E |
| 10ec:8168 | 1043:8432 | Realtek... | RTL8111/8168/8411 PCI Exp... | 636   | r8169      | 3A7D6AD8A5 |
| 10ec:8168 | 1043:200f | Realtek... | RTL8111/8168/8411 PCI Exp... | 565   | r8169      | 179397B4EA |
| 10ec:8139 | 10ec:8139 | Realtek... | RTL-8100/8101L/8139 PCI F... | 416   | 8139too... | 967BB75CBB |
| 10ec:8168 | 1043:8677 | Realtek... | RTL8111/8168/8411 PCI Exp... | 405   | r8169      | A3871B3E32 |
| 10ec:8168 | 1043:8554 | Realtek... | RTL8111/8168/8411 PCI Exp... | 322   | r8169      | 535FBF3562 |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 301   | r8169      | DAEDE56DC8 |
| 10ec:8168 | 1043:83a3 | Realtek... | RTL8111/8168/8411 PCI Exp... | 288   | r8169      | E40B76E473 |
| 1969:1048 | 1043:8226 | Qualcom... | Attansic L1 Gigabit Ethernet | 247   | atl1       | 60EC6F52F9 |
| 10ec:8136 | 1043:200f | Realtek... | RTL810xE PCI Express Fast... | 244   | r8169      | 6D7501C42A |
| 14e4:16b5 | 1025:0647 | Broadco... | NetLink BCM57785 Gigabit ... | 234   | tg3        | 9084C70732 |
| 10ec:8168 | 1043:859e | Realtek... | RTL8111/8168/8411 PCI Exp... | 178   | r8169      | 22A0854387 |
| 1106:3106 | 1186:1405 | VIA Tec... | VT6105/VT6106S [Rhine-III]   | 174   | via_rhine  | A5C61E8040 |
| 8086:15b8 | 1043:8672 | Intel      | Ethernet Connection (2) I... | 174   | e1000e     | 345BBA3C1F |
| 10ec:8168 | 1043:16d5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 152   | r8169      | 55153BEE1A |
| 1969:1083 | 1458:e000 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 149   | atl1c      | AD56492FB5 |
| 1969:2062 | 1043:8468 | Attansi... | AR8152 v2.0 Fast Ethernet    | 146   | atl1c      | A6B1293F94 |
| 10ec:8136 | 1849:8136 | Realtek... | RTL810xE PCI Express Fast... | 142   | r8169      | 62DE4DA398 |
| 11ab:4364 | 1043:81f8 | Marvell... | 88E8056 PCI-E Gigabit Eth... | 132   | sky2       | 49BC4A3291 |
| 10ec:8168 | 1043:82c6 | Realtek... | RTL8111/8168/8411 PCI Exp... | 128   | r8169      | DDF9D08A22 |
| 10ec:8168 | 17aa:5002 | Realtek... | RTL8111/8168/8411 PCI Exp... | 123   | r8169      | 82A9861AFD |
| 197b:0250 | 1043:1905 | JMicron... | JMC250 PCI Express Gigabi... | 121   | jme        | 088FFC2823 |
| 10ec:8136 | 10ec:0123 | Realtek... | RTL810xE PCI Express Fast... | 119   | r8169      | F89781F320 |
| 1969:1083 | 1043:1851 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 109   | atl1c      | AF47B62F54 |
| 8086:15a1 | 1043:85c4 | Intel      | Ethernet Connection (2) I... | 108   | e1000e     | 1D2014DD53 |
| 10ec:8169 | 10ec:8169 | Realtek... | RTL8169 PCI Gigabit Ether... | 105   | r8169      | 4015843475 |
| 10ec:8168 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 104   | r8169      | 13AF031E5E |
| 14e4:16b5 | 1025:0504 | Broadco... | NetLink BCM57785 Gigabit ... | 104   | tg3        | 832F6EF100 |
| 1969:1091 | 1458:e000 | Qualcom... | AR8161 Gigabit Ethernet      | 100   | alx        | A5E90F38C5 |
| 10ec:8168 | 7470:3468 | Realtek... | RTL8111/8168/8411 PCI Exp... | 95    | r8169      | 41795F04DE |
| 1969:1026 | 1043:8304 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 94    | atl1e      | B315D4391D |
| 1969:2062 | 17aa:3979 | Qualcom... | AR8152 v2.0 Fast Ethernet    | 94    | atl1c      | B6EF514918 |
| 10ec:8168 | 1043:81aa | Realtek... | RTL8111/8168/8411 PCI Exp... | 93    | r8169      | 53D2EF8D02 |
| 14e4:1692 | 1025:036d | Broadco... | NetLink BCM57780 Gigabit ... | 90    | tg3        | B99A6015C7 |
| 14e4:1693 | 1025:011c | Broadco... | NetLink BCM5787M Gigabit ... | 88    | tg3        | BA9EFF4F3B |
| 8086:15b8 | 1458:e000 | Intel      | Ethernet Connection (2) I... | 86    | e1000e     | 8F2ECB882C |
| 1969:1090 | 17aa:3979 | Qualcom... | AR8162 Fast Ethernet         | 85    | alx        | CE8329CC49 |
| 10ec:8136 | 1043:8347 | Realtek... | RTL810xE PCI Express Fast... | 84    | r8169      | B9B80DB558 |
| 10ec:8168 | 1462:7817 | Realtek... | RTL8111/8168/8411 PCI Exp... | 84    | r8169      | FBE43FC861 |
| 1969:2048 | 1043:8233 | Qualcom... | Attansic L2 Fast Ethernet    | 80    | atl2       | E643B8ED58 |
| 11ab:4320 | 1043:811a | Marvell... | 88E8001 Gigabit Ethernet ... | 79    | skge       | 49BC4A3291 |
| 14e4:16b4 | 14e4:16b4 | Broadco... | NetXtreme BCM57765 Gigabi... | 71    | tg3        | 2B202B204B |
| 10ec:8136 | 17aa:3975 | Realtek... | RTL810xE PCI Express Fast... | 70    | r8169      | 47BBFE4D38 |
| 10ec:8168 | 1025:8000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 68    | r8169      | 7C1A93E022 |
| 1969:1063 | 1043:1820 | Qualcom... | AR8131 Gigabit Ethernet      | 68    | atl1c      | BA1E7F648C |
| 10ec:8168 | 1043:1277 | Realtek... | RTL8111/8168/8411 PCI Exp... | 67    | r8169      | 47A635ACC1 |
| 10ec:8168 | 17aa:3812 | Realtek... | RTL8111/8168/8411 PCI Exp... | 66    | r8169      | 363B08984A |
| 1969:1062 | 1043:838a | Qualcom... | AR8132 Fast Ethernet         | 65    | atl1c      | E368A28816 |
| 10ec:8168 | 1b0a:20d9 | Realtek... | RTL8111/8168/8411 PCI Exp... | 63    | r8169      | 5711F7E7F3 |
| 10ec:8168 | 1043:11f5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 62    | r8169      | 427546EA21 |
| 8086:15b8 | 1849:15b8 | Intel      | Ethernet Connection (2) I... | 62    | e1000e     | 1BB0C8F064 |
| 10ec:8136 | 1179:ff00 | Realtek... | RTL810xE PCI Express Fast... | 61    | r8169      | 18FA01EC6B |
| 10ec:8168 | 1043:8367 | Realtek... | RTL8111/8168/8411 PCI Exp... | 60    | r8169      | 8FE7FBADA1 |
| 10ec:8168 | 1462:7721 | Realtek... | RTL8111/8168/8411 PCI Exp... | 60    | r8169      | 743F3FF81C |
| 10ec:8168 | 17aa:3816 | Realtek... | RTL8111/8168/8411 PCI Exp... | 59    | r8169      | F2797B8B83 |
| 8086:153b | 1458:e000 | Intel      | Ethernet Connection I217-V   | 59    | e1000e     | 984B3421C1 |
| 10ec:8136 | 10ec:8136 | Realtek... | RTL810xE PCI Express Fast... | 58    | r8169      | 073EE0D8BC |
| 14e4:16b3 | 1025:0775 | Broadco... | NetXtreme BCM57786 Gigabi... | 58    | tg3        | 94CD691A35 |
| 1969:1026 | 1043:14f5 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 57    | atl1e      | 33E615851D |
| 11ab:4381 | 104d:9071 | Marvell... | Yukon Optima 88E8059 [PCI... | 56    | sky2       | 90D3759348 |
| 1969:1026 | 1043:8226 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 56    | atl1e      | A5A715C21F |
| 1969:10a0 | 17aa:3802 | Qualcom... | QCA8172 Fast Ethernet        | 56    | alx        | 8CE0C08E9A |
| 10ec:8168 | 144d:c0da | Realtek... | RTL8111/8168/8411 PCI Exp... | 55    | r8169      | C5694CCAC0 |
| 10ec:8168 | 17aa:3975 | Realtek... | RTL8111/8168/8411 PCI Exp... | 55    | r8169      | 89EF922929 |
| 1186:4300 | 1186:4300 | D-Link ... | DGE-528T Gigabit Ethernet... | 55    | r8169      | F85FDA7AF0 |
| 14e4:1698 | 1025:0207 | Broadco... | NetLink BCM5784M Gigabit ... | 54    | tg3        | 34DC7B3038 |
| 8086:155a | 17aa:2214 | Intel      | Ethernet Connection I218-LM  | 53    | e1000e     | 14015A6CDE |
| 10ec:8167 | 1458:e000 | Realtek... | RTL-8110SC/8169SC Gigabit... | 52    | r8169      | F176A74B87 |
| 14e4:1713 | 17aa:3a23 | Broadco... | NetLink BCM5906M Fast Eth... | 52    | tg3        | 5986AA0AAC |
| 1969:1063 | 1043:83fe | Qualcom... | AR8131 Gigabit Ethernet      | 52    | atl1c      | A898DD70F0 |
| 1969:1063 | 1458:e000 | Qualcom... | AR8131 Gigabit Ethernet      | 52    | atl1c      | 9928EAEA06 |
| 1969:1083 | 1043:13c7 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 52    | atl1c      | 4DB132BB33 |
| 1969:2062 | 1849:2062 | Qualcom... | AR8152 v2.0 Fast Ethernet    | 52    | atl1c      | 6FDB8DFE61 |
| 1969:10a1 | 1043:8587 | Qualcom... | QCA8171 Gigabit Ethernet     | 51    | alx        | E5540CB969 |
| 10ec:8168 | 1043:8385 | Realtek... | RTL8111/8168/8411 PCI Exp... | 48    | r8169      | 5D250ED2A6 |
| 10ec:8168 | 144d:c606 | Realtek... | RTL8111/8168/8411 PCI Exp... | 48    | r8169      | 0BF9EE57AF |
| 14e4:1692 | 1025:033d | Broadco... | NetLink BCM57780 Gigabit ... | 48    | tg3        | D500F84DEB |
| 1969:1091 | 1043:14c7 | Qualcom... | AR8161 Gigabit Ethernet      | 48    | alx        | 12F5A59D53 |
| 10ec:8136 | 1028:04b0 | Realtek... | RTL810xE PCI Express Fast... | 47    | r8169      | DF459BC2B0 |
| 10ec:8136 | 17aa:392e | Realtek... | RTL810xE PCI Express Fast... | 47    | r8169      | FEAC85F7D7 |
| 10ec:8139 | 1043:1045 | Realtek... | RTL-8100/8101L/8139 PCI F... | 47    | 8139too... | 6C6A2138D2 |
| 10ec:8168 | 1019:811e | Realtek... | RTL8111/8168/8411 PCI Exp... | 47    | r8169      | 9091074F4A |
| 10ec:8168 | 1025:0866 | Realtek... | RTL8111/8168/8411 PCI Exp... | 46    | r8169      | 3FD761163B |
| 10ec:8168 | 103c:8330 | Realtek... | RTL8111/8168/8411 PCI Exp... | 46    | r8169      | E26638D750 |
| 8086:153b | 1043:859f | Intel      | Ethernet Connection I217-V   | 46    | e1000e     | E203D0B513 |
| 10de:0ab0 | 10de:cb79 | Nvidia     | MCP79 Ethernet               | 45    | forcedeth  | 441575D073 |
| 11ab:4362 | 1043:8142 | Marvell... | 88E8053 PCI-E Gigabit Eth... | 45    | sky2       | 83592C8857 |
| 10ec:8168 | 1462:7693 | Realtek... | RTL8111/8168/8411 PCI Exp... | 44    | r8169      | 9650DD9DCE |
| 13f0:0200 | 13f0:0201 | Sundanc... | IC Plus IP100A Integrated... | 44    | sundance   | 9D0BA3BCD7 |
| 14e4:16b1 | 1849:96b1 | Broadco... | NetLink BCM57781 Gigabit ... | 44    | tg3        | 107280E5A9 |
| 1969:1083 | 1849:1083 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 44    | atl1c      | 2A41C5495D |
| 1969:1026 | 1043:831c | Qualcom... | AR8121/AR8113/AR8114 Giga... | 42    | atl1e      | B56C2B2E60 |
| 1969:1062 | 1025:0212 | Qualcom... | AR8132 Fast Ethernet         | 40    | atl1c      | CCC2EA91E1 |
| 10ec:8136 | 1179:fb37 | Realtek... | RTL810xE PCI Express Fast... | 39    | r8169      | C77563A5FB |
| 10ec:8168 | 1462:7758 | Realtek... | RTL8111/8168/8411 PCI Exp... | 39    | r8169      | 6DD3E491F5 |
| 1969:1090 | 17aa:3978 | Qualcom... | AR8162 Fast Ethernet         | 39    | alx        | 3DCE4D353B |
| 1969:e091 | 1458:e000 | Qualcom... | Killer E220x Gigabit Ethe... | 39    | alx        | 75C292C941 |
| 10ec:8136 | 17aa:3830 | Realtek... | RTL810xE PCI Express Fast... | 38    | r8169      | 7D85F9BFAB |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 168c:002b | 1a3b:1089 | Qualcom... | AR9285 Wireless Network A... | 493   | ath9k      | 088FFC2823 |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 235   | iwlwifi    | D5082D8C3F |
| 1814:3290 | 103c:18ec | Ralink     | RT3290 Wireless 802.11n 1... | 230   | rt2800pci  | 96C288C457 |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 222   | iwlwifi    | CCBB4BE6BB |
| 8086:4222 | 8086:1001 | Intel      | PRO/Wireless 3945ABG [Gol... | 206   | iwl3945    | BA9EFF4F3B |
| 14e4:4365 | 17aa:0611 | Broadco... | BCM43142 802.11b/g/n         | 205   | wl         | 8CE0C08E9A |
| 168c:0032 | 1a3b:2c97 | Qualcom... | AR9485 Wireless Network A... | 205   | ath9k      | CE99670CEB |
| 168c:0042 | 11ad:08a6 | Qualcom... | QCA9377 802.11ac Wireless... | 197   | ath10k_pci | CE1098A7F5 |
| 168c:002b | 17aa:30a1 | Qualcom... | AR9285 Wireless Network A... | 193   | ath9k      | 62C717C459 |
| 168c:002b | 105b:e035 | Qualcom... | AR9285 Wireless Network A... | 191   | ath9k      | D500F84DEB |
| 168c:002b | 1a3b:2c37 | Qualcom... | AR9285 Wireless Network A... | 188   | ath9k      | 55153BEE1A |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 176   | iwlwifi    | 0AEADAFA2C |
| 168c:0032 | 144d:4105 | Qualcom... | AR9485 Wireless Network A... | 174   | ath9k      | C5694CCAC0 |
| 168c:0034 | 105b:e052 | Qualcom... | AR9462 Wireless Network A... | 163   | ath9k      | 9084C70732 |
| 168c:0036 | 11ad:0642 | Qualcom... | QCA9565 / AR9565 Wireless... | 163   | ath9k      | 216DFBDCC6 |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 155   | iwlwifi    | D75C0B2DA5 |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 154   | iwlwifi    | 65B1EB0CA1 |
| 8086:a370 | 8086:0034 | Intel      | Wireless-AC 9560 [Jeffers... | 145   | iwlwifi    | A47D005445 |
| 8086:0896 | 8086:5005 | Intel      | Centrino Wireless-N 130      | 142   | iwlwifi    | 0BF9EE57AF |
| 10ec:b723 | 17aa:b736 | Realtek... | RTL8723BE PCIe Wireless N... | 138   | rtl8723be  | 972580DCF6 |
| 14e4:4727 | 103c:1483 | Broadco... | BCM4313 802.11bgn Wireles... | 137   | wl         | 0C390ADEEF |
| 168c:0036 | 1028:020c | Qualcom... | QCA9565 / AR9565 Wireless... | 133   | ath9k      | A0554A7E66 |
| 168c:001c | 1a3b:1026 | Qualcom... | AR242x / AR542x Wireless ... | 130   | ath5k      | DF4FA2D486 |
| 8086:0887 | 8086:4062 | Intel      | Centrino Wireless-N 2230     | 124   | iwlwifi    | 18D138561D |
| 168c:0042 | 17aa:0901 | Qualcom... | QCA9377 802.11ac Wireless... | 121   | ath10k_pci | E0F719AEB9 |
| 8086:4232 | 8086:1201 | Intel      | WiFi Link 5100               | 120   | iwlwifi    | EF1BFF7353 |
| 168c:001c | 1468:0428 | Qualcom... | AR242x / AR542x Wireless ... | 119   | ath5k      | 005CF3D43E |
| 168c:0032 | 11ad:6617 | Qualcom... | AR9485 Wireless Network A... | 118   | ath9k      | 39D47C0F09 |
| 168c:0036 | 1028:020e | Qualcom... | QCA9565 / AR9565 Wireless... | 118   | ath9k      | 0F87997CD1 |
| 8086:4237 | 8086:1211 | Intel      | PRO/Wireless 5100 AGN [Sh... | 117   | iwlwifi    | 01F5E9CD57 |
| 168c:002b | 105b:e025 | Qualcom... | AR9285 Wireless Network A... | 113   | ath9k      | 809DA0D1B4 |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 112   | 8821ce     | 6EEF4CAED6 |
| 14e4:4727 | 14e4:051b | Broadco... | BCM4313 802.11bgn Wireles... | 112   | wl         | 3DCE4D353B |
| 168c:002e | 105b:e034 | Qualcom... | AR9287 Wireless Network A... | 112   | ath9k      | 25D909CC38 |
| 168c:0032 | 103c:1785 | Qualcom... | AR9485 Wireless Network A... | 108   | ath9k      | 9C722B6763 |
| 8086:08ae | 8086:1005 | Intel      | Centrino Wireless-N 100      | 108   | iwlwifi    | 47A635ACC1 |
| 168c:0036 | 17aa:4026 | Qualcom... | QCA9565 / AR9565 Wireless... | 107   | ath9k      | 4D7E6E73B6 |
| 8086:4229 | 8086:1101 | Intel      | PRO/Wireless 4965 AG or A... | 107   | iwl4965    | D201D96AFE |
| 168c:0042 | 1028:1810 | Qualcom... | QCA9377 802.11ac Wireless... | 102   | ath10k_pci | 2B2912B5B0 |
| 10ec:b723 | 11ad:1723 | Realtek... | RTL8723BE PCIe Wireless N... | 99    | rtl8723be  | A14B78EF65 |
| 14e4:4727 | 103c:1795 | Broadco... | BCM4313 802.11bgn Wireles... | 96    | wl         | CD1743483A |
| 168c:0032 | 168c:3118 | Qualcom... | AR9485 Wireless Network A... | 96    | ath9k      | 4F4314B0B4 |
| 168c:0034 | 11ad:6621 | Qualcom... | AR9462 Wireless Network A... | 94    | ath9k      | 7BE60A0A2C |
| 168c:0032 | 11ad:6627 | Qualcom... | AR9485 Wireless Network A... | 91    | ath9k      | 179397B4EA |
| 8086:9df0 | 8086:0034 | Intel      | Cannon Point-LP CNVi [Wir... | 91    | iwlwifi    | E4301E56F9 |
| 168c:002b | 105b:e016 | Qualcom... | AR9285 Wireless Network A... | 88    | ath9k      | CEF0B9CE71 |
| 168c:0032 | 1a3b:1186 | Qualcom... | AR9485 Wireless Network A... | 87    | ath9k      | E407354B88 |
| 8086:4232 | 8086:1206 | Intel      | WiFi Link 5100               | 87    | iwlwifi    | 363190383F |
| 168c:0032 | 17aa:3218 | Qualcom... | AR9485 Wireless Network A... | 86    | ath9k      | 5F1837A6B4 |
| 14e4:4727 | 185f:051a | Broadco... | BCM4313 802.11bgn Wireles... | 85    | wl         | B5AE2A5BE6 |
| 14e4:4315 | 14e4:04b5 | Broadco... | BCM4312 802.11b/g LP-PHY     | 84    | ssb        | 5986AA0AAC |
| 8086:2526 | 8086:0014 | Intel      | Wireless-AC 9260             | 84    | iwlwifi    | D1CA80EDFF |
| 8086:3165 | 8086:4410 | Intel      | Wireless 3165                | 84    | iwlwifi    | 556DD6ED0B |
| 14e4:4727 | 14e4:0510 | Broadco... | BCM4313 802.11bgn Wireles... | 83    | wl         | 3C20BDA761 |
| 168c:002b | 144f:7167 | Qualcom... | AR9285 Wireless Network A... | 83    | ath9k      | A3F9F98355 |
| 168c:003e | 1a56:1535 | Qualcom... | QCA6174 802.11ac Wireless... | 83    | ath10k_pci | 18DC19F3EC |
| 8086:4222 | 103c:135c | Intel      | PRO/Wireless 3945ABG [Gol... | 83    | iwl3945    | B38A821821 |
| 10ec:c821 | 17aa:c024 | Realtek... | RTL8821CE 802.11ac PCIe W... | 82    | rtl8821ce  | C65ABD0640 |
| 14e4:4727 | 105b:e042 | Broadco... | BCM4313 802.11bgn Wireles... | 82    | wl         | 7857E6A77B |
| 10ec:8723 | 10ec:0726 | Realtek... | RTL8723AE PCIe Wireless N... | 80    | rtl8723ae  | 0830776CD0 |
| 10ec:b723 | 103c:2231 | Realtek... | RTL8723BE PCIe Wireless N... | 80    | rtl8723be  | 0A66464BD9 |
| 8086:08b1 | 8086:4070 | Intel      | Wireless 7260                | 80    | iwlwifi    | 14F07E52FE |
| 14e4:4727 | 144f:7179 | Broadco... | BCM4313 802.11bgn Wireles... | 79    | wl         | 60127AB94A |
| 14e4:4315 | 103c:1508 | Broadco... | BCM4312 802.11b/g LP-PHY     | 78    | ssb        | 56A913A0DB |
| 168c:002e | 168c:30a4 | Qualcom... | AR9287 Wireless Network A... | 78    | ath9k      | AFDF4A3A9C |
| 168c:002b | 105b:e017 | Qualcom... | AR9285 Wireless Network A... | 77    | ath9k      | FC53E6761D |
| 14e4:4311 | 1028:0007 | Broadco... | BCM4311 802.11b/g WLAN       | 76    | ssb        | 4908DA86B8 |
| 14e4:4315 | 1028:000c | Broadco... | BCM4312 802.11b/g LP-PHY     | 76    | wl         | ADAA5B6D54 |
| 8086:0084 | 8086:1315 | Intel      | Centrino Wireless-N 1000 ... | 76    | iwlwifi    | F3FBF8BC70 |
| 10ec:b723 | 103c:81c1 | Realtek... | RTL8723BE PCIe Wireless N... | 75    | rtl8723be  | A0C06307BA |
| 168c:002b | 103c:3040 | Qualcom... | AR9285 Wireless Network A... | 75    | ath9k      | 5D02B6C874 |
| 168c:002b | 1028:0205 | Qualcom... | AR9285 Wireless Network A... | 73    | ath9k      | DE4AEAA742 |
| 14e4:4727 | 103c:145c | Broadco... | BCM4313 802.11bgn Wireles... | 72    | wl         | AF73595612 |
| 168c:002b | 103c:1461 | Qualcom... | AR9285 Wireless Network A... | 72    | ath9k      | A56D8D1C28 |
| 10ec:b723 | 10ec:b729 | Realtek... | RTL8723BE PCIe Wireless N... | 71    | rtl8723be  | AA2E59FD60 |
| 14e4:4358 | 105b:e040 | Broadco... | BCM43227 802.11b/g/n         | 71    | wl         | D17275F479 |
| 168c:0032 | 1028:0209 | Qualcom... | AR9485 Wireless Network A... | 71    | ath9k      | 2187C4D783 |
| 168c:002d | 168c:0301 | Qualcom... | AR9227 Wireless Network A... | 70    | ath9k      | E722D70419 |
| 168c:001c | 144f:7131 | Qualcom... | AR242x / AR542x Wireless ... | 69    | ath5k      | F2D52E0253 |
| 168c:0042 | 1a3b:2b31 | Qualcom... | QCA9377 802.11ac Wireless... | 69    | ath10k_pci | 219AE079DC |
| 10ec:8179 | 103c:197d | Realtek... | RTL8188EE Wireless Networ... | 65    | rtl8188ee  | 18F9503086 |
| 168c:0036 | 1a3b:213a | Qualcom... | QCA9565 / AR9565 Wireless... | 65    | ath9k      | 81F8804034 |
| 8086:24fd | 8086:0110 | Intel      | Wireless 8265 / 8275         | 65    | iwlwifi    | 9809687258 |
| 14e4:4365 | 1028:0016 | Broadco... | BCM43142 802.11b/g/n         | 64    | wl         | 17ED1F4194 |
| 8086:08b2 | 8086:c270 | Intel      | Wireless 7260                | 64    | iwlwifi    | 14015A6CDE |
| 10ec:b822 | 103c:831b | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 63    | r8822be    | 992E2074FF |
| 14e4:4365 | 103c:804a | Broadco... | BCM43142 802.11b/g/n         | 63    | wl         | 7C960F54DF |
| 168c:0042 | 17aa:4035 | Qualcom... | QCA9377 802.11ac Wireless... | 63    | ath10k_pci | 10AB399874 |
| 168c:0032 | 103c:1838 | Qualcom... | AR9485 Wireless Network A... | 62    | ath9k      | F432E62120 |
| 14e4:4727 | 1a3b:2047 | Broadco... | BCM4313 802.11bgn Wireles... | 60    | wl         | A6B1293F94 |
| 168c:0032 | 105b:e044 | Qualcom... | AR9485 Wireless Network A... | 60    | ath9k      | 214F765FC8 |
| 10ec:8821 | 17aa:a814 | Realtek... | RTL8821AE 802.11ac PCIe W... | 59    | rtl8821ae  | 2B46AD4F9B |
| 1814:3290 | 105b:e055 | Ralink     | RT3290 Wireless 802.11n 1... | 59    | rt2800pci  | 12F5A59D53 |
| 14e4:4311 | 1468:0422 | Broadco... | BCM4311 802.11b/g WLAN       | 58    | ssb        | 3D881D6E68 |
| 168c:003e | 1028:0310 | Qualcom... | QCA6174 802.11ac Wireless... | 57    | ath10k_pci | D782AD033A |
| 1814:3090 | 103c:1453 | Ralink     | RT3090 Wireless 802.11n 1... | 57    | rt2800pci  | 780F3AE697 |
| 10ec:8723 | 1a3b:2114 | Realtek... | RTL8723AE PCIe Wireless N... | 56    | rtl8723ae  | 6E20292C6B |
| 14e4:4727 | 1028:0010 | Broadco... | BCM4313 802.11bgn Wireles... | 56    | wl         | 4309803872 |
| 168c:0036 | 11ad:0632 | Qualcom... | QCA9565 / AR9565 Wireless... | 56    | ath9k      | 94CD691A35 |
| 8086:08b3 | 8086:0070 | Intel      | Wireless 3160                | 55    | iwlwifi    | 2E33715189 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0085 | 8086:1311 | Intel      | Centrino Advanced-N 6205 ... | 254   | iwlwifi    | B470E45C2C |
| 10ec:d723 | 103c:8319 | Realtek... | RTL8723DE Wireless Networ... | 236   | rtl8723de  | 16EA8E9AC4 |
| 10de:03ef | 1849:03ef | Nvidia     | MCP61 Ethernet               | 206   | forcedeth  | EC1F6C8A0B |
| 8086:1539 | 1043:85f0 | Intel      | I211 Gigabit Network Conn... | 154   | igb        | 238AD0F889 |
| 8086:1503 | 1043:849c | Intel      | 82579V Gigabit Network Co... | 152   | e1000e     | BD3C6A762C |
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 146   | iwlwifi    | 9BFAB5575C |
| 8086:1502 | 17aa:21f3 | Intel      | 82579LM Gigabit Network C... | 139   | e1000e     | 1949413DC7 |
| 8086:088e | 8086:4060 | Intel      | Centrino Advanced-N 6235     | 129   | iwlwifi    | DA5836E2AA |
| 8086:1502 | 17aa:21ce | Intel      | 82579LM Gigabit Network C... | 119   | e1000e     | F3FBF8BC70 |
| 8086:4239 | 8086:1311 | Intel      | Centrino Advanced-N 6200     | 114   | iwlwifi    | 82CB2D5E90 |
| 10de:03ef | 1458:e000 | Nvidia     | MCP61 Ethernet               | 105   | forcedeth  | 53DB8982F5 |
| 8086:10ea | 17aa:2153 | Intel      | 82577LM Gigabit Network C... | 94    | e1000e     | 9A495F134B |
| 8086:0082 | 8086:1321 | Intel      | Centrino Advanced-N 6205 ... | 89    | iwlwifi    | 813731AB25 |
| 8086:1539 | 1849:1539 | Intel      | I211 Gigabit Network Conn... | 84    | igb        | 5E8A739106 |
| 10de:03ef | 1043:8234 | Nvidia     | MCP61 Ethernet               | 76    | forcedeth  | F3B22A675A |
| 10de:03ef | 1043:83a4 | Nvidia     | MCP61 Ethernet               | 76    | forcedeth  | A6BD4DA213 |
| 8086:4238 | 8086:1111 | Intel      | Centrino Ultimate-N 6300     | 74    | iwlwifi    | AB2CEA0D81 |
| 8086:0082 | 8086:1301 | Intel      | Centrino Advanced-N 6205 ... | 67    | iwlwifi    | 71BD398238 |
| 8086:422b | 8086:1121 | Intel      | Centrino Ultimate-N 6300     | 67    | iwlwifi    | 3E3F341EF4 |
| 8086:10f5 | 17aa:20ee | Intel      | 82567LM Gigabit Network C... | 63    | e1000e     | 1A90AC4588 |
| 8086:1539 | 1458:e000 | Intel      | I211 Gigabit Network Conn... | 63    | igb        | D4813C969B |
| 8086:1521 | 15d9:1521 | Intel      | I350 Gigabit Network Conn... | 49    | igb        | E5DA683598 |
| 8086:10de | 1028:0276 | Intel      | 82567LM-3 Gigabit Network... | 48    | e1000e     | 5151CB704B |
| 8086:1502 | 1028:052c | Intel      | 82579LM Gigabit Network C... | 42    | e1000e     | 779B6B3344 |
| 8086:10d3 | 8086:a01f | Intel      | 82574L Gigabit Network Co... | 41    | e1000e     | 2902DCE4BA |
| 8086:2723 | 8086:0084 | Intel      | Wi-Fi 6 AX200                | 41    | iwlwifi    | B944521EC0 |
| 10de:03ef | 1462:7309 | Nvidia     | MCP61 Ethernet               | 40    | forcedeth  | 93E77F9DC3 |
| 8086:1502 | 1028:0493 | Intel      | 82579LM Gigabit Network C... | 39    | e1000e     | CA779DE74C |
| 10de:0057 | 1043:812a | Nvidia     | CK804 Ethernet Controller    | 37    | forcedeth  | 17E56B1C60 |
| 8086:1502 | 1028:047e | Intel      | 82579LM Gigabit Network C... | 37    | e1000e     | 2D378E81BE |
| 8086:1049 | 17aa:20b9 | Intel      | 82566MM Gigabit Network C... | 34    | e1000e     | FB1CD7BF88 |
| 8086:10f5 | 1028:0233 | Intel      | 82567LM Gigabit Network C... | 34    | e1000e     | 314E0FF832 |
| 8086:422c | 8086:1301 | Intel      | Centrino Advanced-N 6200     | 34    | iwlwifi    | 90D3759348 |
| 10de:0373 | 1043:8239 | Nvidia     | MCP55 Ethernet               | 32    | forcedeth  | 44E3D900F5 |
| 8086:10ea | 1028:040a | Intel      | 82577LM Gigabit Network C... | 32    | e1000e     | 3E3F341EF4 |
| 8086:422c | 8086:1321 | Intel      | Centrino Advanced-N 6200     | 32    | iwlwifi    | 1C9F512B78 |
| 14e4:170c | 1025:0090 | Broadco... | BCM4401-B0 100Base-TX        | 31    | b44        | 5979EB4500 |
| 8086:0091 | 8086:5201 | Intel      | Centrino Advanced-N 6230 ... | 31    | iwlwifi    | 7434BE9250 |
| 14e4:4331 | 14e4:4331 | Broadco... | BCM4331 802.11a/b/g/n        | 30    | wl         | 433304B5E5 |
| 8086:10c4 | 103c:30d8 | Intel      | 82562GT 10/100 Network Co... | 30    | e1000e     | FF0936189F |
| 8086:10d3 | 15d9:10d3 | Intel      | 82574L Gigabit Network Co... | 29    | e1000e     | EE5C52C67E |
| 8086:1502 | 103c:161c | Intel      | 82579LM Gigabit Network C... | 29    | e1000e     | 3EAB448396 |
| 8086:10de | 1028:027f | Intel      | 82567LM-3 Gigabit Network... | 28    | e1000e     | 439AF540E7 |
| 8086:10bd | 1028:0211 | Intel      | 82566DM-2 Gigabit Network... | 27    | e1000e     | E23742C63F |
| 8086:1503 | 1458:e000 | Intel      | 82579V Gigabit Network Co... | 27    | e1000e     | 82A8163E58 |
| 8086:10bd | 103c:2818 | Intel      | 82566DM-2 Gigabit Network... | 26    | e1000e     | 775B90FA5A |
| 14e4:170c | 1028:01f5 | Broadco... | BCM4401-B0 100Base-TX        | 25    | b44        | 3D6C8F2267 |
| 8086:088e | 8086:4460 | Intel      | Centrino Advanced-N 6235     | 25    | iwlwifi    | 32D2083BB0 |
| 8086:1502 | 103c:179b | Intel      | 82579LM Gigabit Network C... | 25    | e1000e     | 7195452FF3 |
| 8086:104a | 103c:2800 | Intel      | 82566DM Gigabit Network C... | 24    | e1000e     | 3A37DFD543 |
| 14e4:170c | 103c:30a2 | Broadco... | BCM4401-B0 100Base-TX        | 23    | b44        | 527BA99CD2 |
| 8086:10bd | 103c:281e | Intel      | 82566DM-2 Gigabit Network... | 23    | e1000e     | 366E5CAC3F |
| 8086:10de | 103c:3048 | Intel      | 82567LM-3 Gigabit Network... | 23    | e1000e     | 733B76A48E |
| 8086:10ea | 103c:7008 | Intel      | 82577LM Gigabit Network C... | 23    | e1000e     | 4663DEB0DD |
| 10ec:8136 | 103c:3567 | Realtek... | RTL810xE PCI Express Fast... | 22    | r8169      | 9C722B6763 |
| 8086:1503 | 1025:8000 | Intel      | 82579V Gigabit Network Co... | 22    | e1000e     | 42B0E234AF |
| 8086:1502 | 1028:0534 | Intel      | 82579LM Gigabit Network C... | 21    | e1000e     | 39D47C0F09 |
| 8086:294c | 8086:0001 | Intel      | 82566DC-2 Gigabit Network... | 21    | e1000e     | 90F4B2CD0E |
| 10de:0057 | 1043:8141 | Nvidia     | CK804 Ethernet Controller    | 20    | forcedeth  | FD8F010178 |
| 10de:03ef | 103c:2a6c | Nvidia     | MCP61 Ethernet               | 20    | forcedeth  | 6D882902AD |
| 1106:3065 | 1043:80ed | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 20    | via_rhine  | 476F99FF1B |
| 8086:1533 | 15d9:1533 | Intel      | I210 Gigabit Network Conn... | 20    | igb        | 64918C950D |
| 8086:422b | 8086:1101 | Intel      | Centrino Ultimate-N 6300     | 20    | iwlwifi    | 2D934282A2 |
| 10de:0373 | 1462:7250 | Nvidia     | MCP55 Ethernet               | 19    | forcedeth  | C862E6269E |
| 10de:03ef | 1565:2505 | Nvidia     | MCP61 Ethernet               | 19    | forcedeth  | 1004AD3220 |
| 8086:150c | 1043:8457 | Intel      | 82583V Gigabit Network Co... | 19    | e1000e     | B0D238EB2E |
| 8086:1539 | 8086:0000 | Intel      | I211 Gigabit Network Conn... | 19    | igb        | 277007D50C |
| 10de:0269 | 1043:816a | Nvidia     | MCP51 Ethernet Controller    | 18    | forcedeth  | A26BD26890 |
| 8086:104b | 8086:0001 | Intel      | 82566DC Gigabit Network C... | 18    | e1000e     | 43BE22F6DA |
| 8086:1502 | 103c:3397 | Intel      | 82579LM Gigabit Network C... | 18    | e1000e     | FF9A2F987D |
| 8086:1533 | 1043:8557 | Intel      | I210 Gigabit Network Conn... | 18    | igb        | 785E45F5BF |
| 10b7:9200 | 10b7:1000 | 3Com       | 3c905C-TX/TX-M [Tornado]     | 17    | 3c59x      | 278994D939 |
| 8086:0091 | 8086:5221 | Intel      | Centrino Advanced-N 6230 ... | 17    | iwlwifi    | A2BC6AC4B5 |
| 8086:10d3 | 1043:8369 | Intel      | 82574L Gigabit Network Co... | 17    | e1000e     | B2D6DABAA7 |
| 8086:1502 | 103c:339a | Intel      | 82579LM Gigabit Network C... | 17    | e1000e     | 2962B36D7E |
| 14e4:170c | 1028:01af | Broadco... | BCM4401-B0 100Base-TX        | 16    | b44        | AB555162C8 |
| 8086:10ea | 1028:040b | Intel      | 82577LM Gigabit Network C... | 16    | e1000e     | 3A85FD0475 |
| 8086:1533 | ffff:0000 | Intel      | I210 Gigabit Network Conn... | 16    | igb        | 9BFAB5575C |
| 10de:0057 | 1458:e000 | Nvidia     | CK804 Ethernet Controller    | 15    | forcedeth  | 872FEB1CA3 |
| 10de:0373 | 1043:cb84 | Nvidia     | MCP55 Ethernet               | 15    | forcedeth  | 064DD1CCBF |
| 10de:0373 | 1458:e000 | Nvidia     | MCP55 Ethernet               | 15    | forcedeth  | 0CCA59B833 |
| 1106:3065 | 1849:3065 | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 15    | via_rhine  | 6FAC734286 |
| 8086:1049 | 17aa:20de | Intel      | 82566MM Gigabit Network C... | 15    | e1000e     | 74AA251B27 |
| 8086:10df | 1734:114d | Intel      | 82567LF-3 Gigabit Network... | 15    | e1000e     | 9632357AEB |
| 8086:10f5 | 1028:024f | Intel      | 82567LM Gigabit Network C... | 15    | e1000e     | 9F216D6CB3 |
| 8086:1502 | 1028:0494 | Intel      | 82579LM Gigabit Network C... | 15    | e1000e     | 4384225066 |
| 8086:1502 | 103c:1589 | Intel      | 82579LM Gigabit Network C... | 15    | e1000e     | 9D85C4CA60 |
| 8086:1503 | 103c:17ab | Intel      | 82579V Gigabit Network Co... | 15    | e1000e     | 57308077EE |
| 8086:0087 | 8086:1301 | Intel      | Centrino Advanced-N + WiM... | 14    | iwlwifi    | 44B359D5B3 |
| 8086:1092 | 1179:ff10 | Intel      | PRO/100 VE Network Connec... | 14    | e100       | 5FDCE37F38 |
| 8086:10c0 | 1028:020d | Intel      | 82562V-2 10/100 Network C... | 14    | e1000e     | 865EB363F8 |
| 8086:10de | 103c:3034 | Intel      | 82567LM-3 Gigabit Network... | 14    | e1000e     | A40772FC80 |
| 8086:10ea | 103c:172a | Intel      | 82577LM Gigabit Network C... | 14    | e1000e     | D1C32BF428 |
| 8086:10f0 | 1025:8000 | Intel      | 82578DC Gigabit Network C... | 14    | e1000e     | A4BB2D6329 |
| 8086:10f0 | 8086:0036 | Intel      | 82578DC Gigabit Network C... | 14    | e1000e     | A57DCF32AA |
| 8086:1502 | 103c:1618 | Intel      | 82579LM Gigabit Network C... | 14    | e1000e     | 0D2FE88BE0 |
| 10de:03ef | 103c:2a99 | Nvidia     | MCP61 Ethernet               | 13    | forcedeth  | 0BC668FE41 |
| 8086:10bf | 17aa:20ee | Intel      | 82567LF Gigabit Network C... | 13    | e1000e     | 031F4149FE |
| 8086:10d3 | 8086:0000 | Intel      | 82574L Gigabit Network Co... | 13    | e1000e     | 368A801F1A |
| 8086:1502 | 1028:0532 | Intel      | 82579LM Gigabit Network C... | 13    | e1000e     | 8E240EEE56 |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1455 | 1022:1455 | AMD        | Zeppelin/Renoir PCIe Dumm... | 420   |            | 5E8A739106 |
| 1022:145a | 1022:145a | AMD        | Zeppelin/Raven/Raven2 PCI... | 420   |            | 5E8A739106 |
| 1022:1455 | 1043:8747 | AMD        | Zeppelin/Renoir PCIe Dumm... | 80    |            | 172F18A294 |
| 1022:145a | 1043:8747 | AMD        | Zeppelin/Raven/Raven2 PCI... | 80    |            | 172F18A294 |
| 1022:1485 | 1022:1485 | AMD        | Starship/Matisse Reserved... | 31    |            | 2E60313B01 |
| 1022:148a | 1022:148a | AMD        | Starship/Matisse PCIe Dum... | 29    |            | 2E60313B01 |
| 1022:1485 | 1043:87c0 | AMD        | Starship/Matisse Reserved... | 15    |            | 40061999CC |
| 1022:148a | 1043:87c0 | AMD        | Starship/Matisse PCIe Dum... | 15    |            | 40061999CC |
| 1022:145a | 1043:876b | AMD        | Zeppelin/Raven/Raven2 PCI... | 12    |            | DE065F2CFC |
| 8086:9d26 |           | Intel      | Skylake-U/Y Northpeak        | 11    | intel_t... | 87D31F3F80 |
| 1022:1455 | 1462:7a38 | AMD        | Zeppelin/Renoir PCIe Dumm... | 8     |            | DCDA3B1F44 |
| 1022:145a | 1002:15dd | AMD        | Zeppelin/Raven/Raven2 PCI... | 8     |            | BF727C8928 |
| 1022:145a | 1462:7a38 | AMD        | Zeppelin/Raven/Raven2 PCI... | 8     |            | DCDA3B1F44 |
| 1022:145a | 1458:d000 | AMD        | Zeppelin/Raven/Raven2 PCI... | 7     |            | A9F8B1AD35 |
| 1022:1455 | 1462:7c02 | AMD        | Zeppelin/Renoir PCIe Dumm... | 5     |            | 2E3A02EC4D |
| 1022:145a | 1462:7c02 | AMD        | Zeppelin/Raven/Raven2 PCI... | 5     |            | 2E3A02EC4D |
| 1022:145a | 1462:7b86 | AMD        | Zeppelin/Raven/Raven2 PCI... | 4     |            | 399E8E20C8 |
| 1022:1485 | 1462:7b89 | AMD        | Starship/Matisse Reserved... | 4     |            | D85422E2C1 |
| 1022:148a | 1462:7b89 | AMD        | Starship/Matisse PCIe Dum... | 4     |            | D85422E2C1 |
| 1022:1455 | 1462:7b86 | AMD        | Zeppelin/Renoir PCIe Dumm... | 3     |            | 399E8E20C8 |
| 1022:1455 | 1462:7a40 | AMD        | Zeppelin/Renoir PCIe Dumm... | 2     |            | A215C93612 |
| 1022:1455 | 1462:7b85 | AMD        | Zeppelin/Renoir PCIe Dumm... | 2     |            | 053F507950 |
| 1022:1455 | 1462:7b89 | AMD        | Zeppelin/Renoir PCIe Dumm... | 2     |            | 01693744FC |
| 1022:145a | 1462:7a40 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | A215C93612 |
| 1022:145a | 1462:7b85 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 053F507950 |
| 1022:145a | 1462:7b89 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 01693744FC |
| 8086:a126 |           | Intel      | 100 Series/C230 Series Ch... | 2     | intel_t... | 95260B46FF |
| 1022:1455 | 1019:9ce5 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 06776696F3 |
| 1022:1455 | 1028:07f9 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 8F7FF50C55 |
| 1022:1455 | 103c:8399 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 9440F6405B |
| 1022:1455 | 1462:7b90 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | C7998D926E |
| 1022:145a | 1002:15d8 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 6D716FD307 |
| 1022:145a | 1019:9ce5 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 06776696F3 |
| 1022:145a | 1028:07f9 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 8F7FF50C55 |
| 1022:145a | 103c:8399 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 9440F6405B |
| 1022:145a | 1462:7a33 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | C1253B8603 |
| 1022:145a | 1462:7b84 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 327877AB6E |
| 1022:145a | 1462:7b90 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | C7998D926E |
| 1022:145a | 17aa:36e8 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 78596220D1 |
| 1022:1485 | 1043:8747 | AMD        | Starship/Matisse Reserved... | 1     |            | 172F18A294 |
| 1022:1485 | 1462:7a38 | AMD        | Starship/Matisse Reserved... | 1     |            | DCB98CB8E2 |
| 1022:1485 | 1462:7c02 | AMD        | Starship/Matisse Reserved... | 1     |            | E8131440F2 |
| 1022:1485 | 1462:7c35 | AMD        | Starship/Matisse Reserved... | 1     |            | 9F56AFFC3E |
| 1022:148a | 1462:7a38 | AMD        | Starship/Matisse PCIe Dum... | 1     |            | DCB98CB8E2 |
| 1022:148a | 1462:7c02 | AMD        | Starship/Matisse PCIe Dum... | 1     |            | E8131440F2 |
| 1022:148a | 1462:7c35 | AMD        | Starship/Matisse PCIe Dum... | 1     |            | 9F56AFFC3E |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15e6 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Non-S... | 25    | i2c_amd... | B0FCF85E0D |
| 8086:9d24 |           | Intel      | Skylake-U/Y SPI Controller   | 13    |            | A43311F999 |
| 8086:9d35 | 8086:9d35 | Intel      | Sunrise Point-LP Integrat... | 12    | intel_i... | A9301396F9 |
| 8086:9d35 | 8086:7270 | Intel      | Sunrise Point-LP Integrat... | 10    | intel_i... | 85085D7FF6 |
| 1022:15e6 | 103c:85ea | AMD        | Raven/Raven2/Renoir Non-S... | 6     | i2c_amd... | 4250651580 |
| 8086:22d8 | 103c:827c | Intel      | Integrated Sensor Solution   | 6     | intel_i... | 53194E03EE |
| 8086:22d8 | 1043:13a0 | Intel      | Integrated Sensor Solution   | 6     | intel_i... | 725940B944 |
| 8086:22d8 | 1043:1400 | Intel      | Integrated Sensor Solution   | 6     | intel_i... | 4CCE625762 |
| 8086:9d35 | 17aa:2238 | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | 3504F119EA |
| 8086:22d8 | 103c:813e | Intel      | Integrated Sensor Solution   | 5     | intel_i... | 43F9ACD60A |
| 8086:9d35 | 103c:830f | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 0ECB13EDBF |
| 8086:9d35 | 103c:83b9 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | C28AED72AA |
| 8086:9d35 | 103c:8486 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 7DEF867A41 |
| 8086:9d35 | 103c:8488 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 59D61DD321 |
| 1022:15e4 | 103c:8496 | AMD        | Raven/Raven2/Renoir Senso... | 4     |            | 31DDC7FDCB |
| 1022:15e4 | 103c:85dd | AMD        | Raven/Raven2/Renoir Senso... | 4     |            | D6005821D4 |
| 8086:9d35 | 1028:0740 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 37C0832EC3 |
| 8086:9d35 | 17aa:224e | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 66ACB89125 |
| 8086:a135 | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 4     | intel_i... | 53A016A21C |
| 8086:22d8 | 1043:1c60 | Intel      | Integrated Sensor Solution   | 3     | intel_i... | 5FCF1662DB |
| 8086:9d35 | 1028:073b | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 0DAB5B3510 |
| 8086:9d35 | 1028:07a4 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 73B87C222F |
| 8086:9d35 | 1028:07aa | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | DFDC8C484F |
| 8086:9d35 | 1028:07ba | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 271C309BFA |
| 8086:9d35 | 1028:0804 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | E93E7BA3C5 |
| 8086:9d35 | 103c:827f | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 1DB4A76555 |
| 8086:9d35 | 103c:83b2 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | B355CE68AD |
| 8086:9d35 | 103c:84d8 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 9B4E7338B0 |
| 8086:9d35 | 17aa:2237 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 6AA622B728 |
| 8086:9d35 | 17aa:3807 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 1DD80D33E5 |
| 104c:9065 |           | Texas I... | TMS320DM642                  | 2     |            | A74B989748 |
| 106b:1801 | 106b:1801 | Apple      | T2 Bridge Controller         | 2     |            | D3A040508D |
| 106b:1802 | 106b:1802 | Apple      | T2 Secure Enclave Processor  | 2     |            | D3A040508D |
| 8086:22d8 | 1043:1bdd | Intel      | Integrated Sensor Solution   | 2     | intel_i... | 40D8D33EF9 |
| 8086:22d8 | 8086:7270 | Intel      | Integrated Sensor Solution   | 2     | intel_i... | DF76656467 |
| 8086:9d35 | 1025:111e | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 2D71938FC4 |
| 8086:9d35 | 1028:0741 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | D302412809 |
| 8086:9d35 | 1028:07eb | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 7EB57A3809 |
| 8086:9d35 | 1028:0808 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | EFB686722E |
| 8086:9d35 | 103c:827d | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | E9DECBC4FD |
| 8086:9d35 | 103c:827e | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 28AF751D12 |
| 8086:9d35 | 103c:82c1 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | A9E42C34F6 |
| 8086:9d35 | 103c:8313 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 22FE75A663 |
| 8086:9d35 | 103c:83c4 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 65B956E887 |
| 8086:9d35 | 103c:8503 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | F6ABCD9B4F |
| 8086:9d35 | 1043:1c40 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 18B4F9B58E |
| 8086:9d35 | 1043:1c90 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 7BBD1AB6FE |
| 8086:9d35 | 152d:1182 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 5D3C8DA69A |
| 8086:9d35 | 17aa:380d | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | FC1E9BDE71 |
| 8086:9d35 | 17aa:504c | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 240BAB94C7 |
| 8086:9d35 | 17aa:506c | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 225075209E |
| 8086:a2a4 |           | Intel      | 200 Series/Z370 Chipset F... | 2     |            | 46EA2E591E |
| 0090:0000 | 0090:0000 |            |                              | 1     |            | B562E609ED |
| 1022:15e4 | 103c:8497 | AMD        | Raven/Raven2/Renoir Senso... | 1     |            | D9AF75156B |
| 1022:15e4 | 103c:85de | AMD        | Raven/Raven2/Renoir Senso... | 1     |            | 70F1D3BF36 |
| 1274:5882 |           | Ensoniq    |                              | 1     |            | 3F25A03C59 |
| 12f4:5000 |           | Megatel    |                              | 1     |            | F9A4969283 |
| 1a39:0004 | 1a39:e020 |            |                              | 1     |            | 93A39661EC |
| 8086:22d8 | 1028:06ea | Intel      | Integrated Sensor Solution   | 1     | intel_i... | 721C1A7DC3 |
| 8086:22d8 | 1071:a126 | Intel      | Integrated Sensor Solution   | 1     | intel_i... | F2981C1775 |
| 8086:9d35 | 1028:06e6 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | EC07F9B3A7 |
| 8086:9d35 | 1028:0742 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 2C812C83E2 |
| 8086:9d35 | 1028:0744 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | B4A5AF0E65 |
| 8086:9d35 | 1028:077a | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 57D57D82FE |
| 8086:9d35 | 1028:07a5 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 87A44EF029 |
| 8086:9d35 | 1028:0823 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 83979BC27C |
| 8086:9d35 | 103c:8143 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 49796C6747 |
| 8086:9d35 | 103c:8197 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 910D564E8E |
| 8086:9d35 | 103c:81a1 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | C894E5633B |
| 8086:9d35 | 103c:81ad | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 84C8A9779B |
| 8086:9d35 | 103c:8251 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | C77AFE79C3 |
| 8086:9d35 | 103c:82cb | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | FDB567A59E |
| 8086:9d35 | 103c:83b3 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 2DA46102BD |
| 8086:9d35 | 103c:83ba | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 3743010FB5 |
| 8086:9d35 | 103c:8438 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 7F01433E42 |
| 8086:9d35 | 103c:8483 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 8B7A2D2A08 |
| 8086:9d35 | 103c:8484 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 1B466FC315 |
| 8086:9d35 | 103c:8487 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | C8C863DB3A |
| 8086:9d35 | 1043:1ab0 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | B2D75821A4 |
| 8086:9d35 | 1043:1b40 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | FF2D426E76 |
| 8086:9d35 | 10cf:18d0 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 79CC64010B |
| 8086:9d35 | 144d:c141 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 5B28F6FC87 |
| 8086:9d35 | 144d:c14c | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 6E023867E9 |
| 8086:9d35 | 152d:1147 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 7DA5C4A4FA |
| 8086:9d35 | 17aa:2241 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 1038A34C39 |
| 8086:9d35 | 17aa:3812 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 57EC66B289 |
| 8086:9d35 | 17aa:506d | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 0818236221 |
| 8086:9d35 | 19e5:3e00 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | A76E9D9514 |
| 8086:a135 | 103c:83bb | Intel      | 100 Series/C230 Series Ch... | 1     | intel_i... | CBA3EC356E |
| 8086:a135 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 1     |            | BB8832ACBD |
| 8086:a135 | 8086:a135 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 2E35C3E421 |
| a411:0000 | 011b:0808 |            |                              | 1     |            | E79C952746 |

### Parallel controller (ecp) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1415:c110 | 1415:c110 | Oxford ... | PCI Express ECP Parallel ... | 4     | parport_pc | EC7B8CEB33 |
| 1409:7268 | 1409:0104 | Timedia... | SUN1888 (Dual IEEE1284 pa... | 1     | parport_pc | A989D3CA5D |

### Parallel controller (ieee1284) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 9710:9865 | a000:2000 | MosChip... | PCI 9865 Multi-I/O Contro... | 8     | parport_pc | 8D6C4235C3 |
| 9710:9912 | a000:2000 | MosChip... | PCIe 9912 Multi-I/O Contr... | 7     | parport... | 009DCD4A93 |
| 1fd4:1999 | 1fd4:0100 | SUNIX      | Multiport serial controller  | 3     | parport... | BE51211FE3 |
| ffff:9865 | a000:2000 | Illegal... | Parallel controller          | 3     |            | 8C4716B30A |
| 125b:9100 | a000:2000 | Asix El... | Electronics Parallel cont... | 1     |            | 87DAB1466B |

### Performance counters (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2f30 | 8086:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 74    | hswep_u... | E5DA683598 |
| 8086:2f34 | 8086:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 74    | hswep_u... | E5DA683598 |
| 8086:2f7d | 8086:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 74    |            | E5DA683598 |
| 8086:2f36 | 8086:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 66    | hswep_u... | E5DA683598 |
| 8086:2f37 | 8086:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 66    | hswep_u... | E5DA683598 |
| 8086:2015 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 60    |            | 0217F128CA |
| 8086:204c | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 60    | skx_uncore | 0217F128CA |
| 8086:204d | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 60    | skx_uncore | 0217F128CA |
| 8086:0e36 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 31    | ivbep_u... | 8EAFAB46BF |
| 8086:2058 | 8086:0000 | Intel      | Sky Lake-E KTI 0             | 30    | skx_uncore | 0DFD787765 |
| 8086:27a3 |           | Intel      | 945GM/GU Chipset Hardware... | 30    |            | 3A660A2575 |
| 8086:6f30 | 8086:6f30 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 28    | bdx_uncore | 2903921AEB |
| 8086:6f34 | 8086:6f34 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 28    | bdx_uncore | 2903921AEB |
| 8086:6f7d | 8086:6f7d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 28    |            | 2903921AEB |
| 8086:6f36 | 8086:6f36 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 26    | bdx_uncore | 2903921AEB |
| 8086:6f37 | 8086:6f37 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 26    | bdx_uncore | 2903921AEB |
| 8086:3c44 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to Q... | 25    | snbep_u... | BAF893B7F3 |
| 8086:3ce6 | 8086:0000 | Intel      | Xeon E5/Core i7 QuickPath... | 25    |            | BAF893B7F3 |
| 8086:3c43 | 1043:84ef | Intel      | Xeon E5/Core i7 Ring to P... | 24    | snbep_u... | 39F22D868E |
| 8086:3c43 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to P... | 24    | snbep_u... | BAF893B7F3 |
| 8086:3c44 | 1043:84ef | Intel      | Xeon E5/Core i7 Ring to Q... | 24    | snbep_u... | 39F22D868E |
| 8086:3c46 | 1043:84ef | Intel      | Xeon E5/Core i7 Processor... | 24    | snbep_u... | 39F22D868E |
| 8086:3ce6 | 1043:84ef | Intel      | Xeon E5/Core i7 QuickPath... | 24    |            | 39F22D868E |
| 8086:0e34 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 22    | ivbep_u... | 41EEB14B47 |
| 8086:2088 | 8086:0000 | Intel      | Sky Lake-E DDRIO Registers   | 19    | skx_uncore | 0DFD787765 |
| 8086:3c46 |           | Intel      | Xeon E5/Core i7 Processor... | 19    | snbep_u... | BAF893B7F3 |
| 8086:0e30 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 17    | ivbep_u... | EEE7D322DF |
| 8086:0e34 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 17    | ivbep_u... | EEE7D322DF |
| 8086:0e36 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 17    | ivbep_u... | EEE7D322DF |
| 8086:6f30 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6f34 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6f36 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6f37 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6f7d | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6f32 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 15    | bdx_uncore | 17BF7A3CBC |
| 8086:6f33 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 15    | bdx_uncore | 17BF7A3CBC |
| 8086:0e30 |           | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 14    | ivbep_u... | 9D85C4CA60 |
| 8086:0e30 | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    | ivbep_u... | 53FB02A9EF |
| 8086:0e34 | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    | ivbep_u... | 53FB02A9EF |
| 8086:0e36 | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    | ivbep_u... | 53FB02A9EF |
| 8086:2f32 | 8086:2f32 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 11    | hswep_u... | E5DA683598 |
| 8086:3c43 | 1458:3c43 | Intel      | Xeon E5/Core i7 Ring to P... | 11    | snbep_u... | 82A8163E58 |
| 8086:3c44 | 1458:3c44 | Intel      | Xeon E5/Core i7 Ring to Q... | 11    | snbep_u... | 82A8163E58 |
| 8086:3c46 | 1458:3c46 | Intel      | Xeon E5/Core i7 Processor... | 11    | snbep_u... | 82A8163E58 |
| 8086:3ce6 | 1458:3ce6 | Intel      | Xeon E5/Core i7 QuickPath... | 11    |            | 82A8163E58 |
| 8086:3424 |           | Intel      | 7500/5520/5500/X58 Perfor... | 10    |            | FA300CEB06 |
| 8086:2f38 | 8086:2f38 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 9     | hswep_u... | E5DA683598 |
| 8086:0e30 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 8     | ivbep_u... | 41EEB14B47 |
| 8086:2f33 | 8086:2f33 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 8     | hswep_u... | E5DA683598 |
| 8086:0e30 | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 7     | ivbep_u... | 8EAFAB46BF |
| 8086:0e34 | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 7     | ivbep_u... | 8EAFAB46BF |
| 8086:2f36 | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 7     | hswep_u... | FDE33600E4 |
| 8086:2f37 | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 7     | hswep_u... | FDE33600E4 |
| 8086:6f32 | 8086:6f32 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 7     | bdx_uncore | 2903921AEB |
| 8086:6f33 | 8086:6f33 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 7     | bdx_uncore | 2903921AEB |
| 8086:3c43 | 1849:3c43 | Intel      | Xeon E5/Core i7 Ring to P... | 5     | snbep_u... | 1B28CC994F |
| 8086:3c44 | 1849:3c44 | Intel      | Xeon E5/Core i7 Ring to Q... | 5     | snbep_u... | 1B28CC994F |
| 8086:3c46 | 1849:3c46 | Intel      | Xeon E5/Core i7 Processor... | 5     | snbep_u... | 1B28CC994F |
| 8086:3c46 | 8086:0000 | Intel      | Xeon E5/Core i7 Processor... | 5     | snbep_u... | CBEE931F44 |
| 8086:3ce6 | 1849:3ce6 | Intel      | Xeon E5/Core i7 QuickPath... | 5     |            | 1B28CC994F |
| 8086:2f30 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | C9D389B2A3 |
| 8086:2f30 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | FD108DE325 |
| 8086:2f30 | 1849:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | 917E16476B |
| 8086:2f34 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | C9D389B2A3 |
| 8086:2f34 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | FD108DE325 |
| 8086:2f34 | 1849:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | 917E16476B |
| 8086:2f36 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | C9D389B2A3 |
| 8086:2f36 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | FD108DE325 |
| 8086:2f36 | 1849:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | 917E16476B |
| 8086:2f37 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | C9D389B2A3 |
| 8086:2f37 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | FD108DE325 |
| 8086:2f37 | 1849:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | 917E16476B |
| 8086:2f7d | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | C9D389B2A3 |
| 8086:2f7d | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | FD108DE325 |
| 8086:2f7d | 1849:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | 917E16476B |
| 8086:3c43 | 103c:18a8 | Intel      | Xeon E5/Core i7 Ring to P... | 4     | snbep_u... | 80E0B0265B |
| 8086:3c44 | 103c:18a8 | Intel      | Xeon E5/Core i7 Ring to Q... | 4     | snbep_u... | 80E0B0265B |
| 8086:3c46 | 103c:18a8 | Intel      | Xeon E5/Core i7 Processor... | 4     | snbep_u... | 80E0B0265B |
| 8086:3ce6 | 103c:18a8 | Intel      | Xeon E5/Core i7 QuickPath... | 4     |            | 80E0B0265B |
| 8086:6f30 | 1849:6f30 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     | bdx_uncore | B09A16F73F |
| 8086:6f34 | 1849:6f34 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     | bdx_uncore | B09A16F73F |
| 8086:6f36 | 1849:6f36 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     | bdx_uncore | B09A16F73F |
| 8086:6f37 | 1849:6f37 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     | bdx_uncore | B09A16F73F |
| 8086:6f7d | 1849:6f7d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     |            | B09A16F73F |
| 8086:0e30 | 1458:3c46 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     | ivbep_u... | DD20758A89 |
| 8086:0e34 | 1458:3c43 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     | ivbep_u... | DD20758A89 |
| 8086:0e36 | 1458:3c44 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     | ivbep_u... | DD20758A89 |
| 8086:2f32 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     | hswep_u... | FD108DE325 |
| 8086:2f33 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     | hswep_u... | FD108DE325 |
| 8086:3c43 | 1028:0497 | Intel      | Xeon E5/Core i7 Ring to P... | 3     | snbep_u... | F1D5B6204E |
| 8086:3c43 | 1028:04ce | Intel      | Xeon E5/Core i7 Ring to P... | 3     | snbep_u... | 6DCBDBD9C8 |
| 8086:3c44 | 1028:0497 | Intel      | Xeon E5/Core i7 Ring to Q... | 3     | snbep_u... | F1D5B6204E |
| 8086:3c44 | 1028:04ce | Intel      | Xeon E5/Core i7 Ring to Q... | 3     | snbep_u... | 6DCBDBD9C8 |
| 8086:3c46 | 1028:0497 | Intel      | Xeon E5/Core i7 Processor... | 3     | snbep_u... | F1D5B6204E |
| 8086:3c46 | 1028:04ce | Intel      | Xeon E5/Core i7 Processor... | 3     | snbep_u... | 6DCBDBD9C8 |
| 8086:3ce6 | 1028:0497 | Intel      | Xeon E5/Core i7 QuickPath... | 3     |            | F1D5B6204E |
| 8086:3ce6 | 1028:04ce | Intel      | Xeon E5/Core i7 QuickPath... | 3     |            | 6DCBDBD9C8 |
| 8086:0e30 | 1028:04f8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     | ivbep_u... | E8BE4F8032 |
| 8086:0e30 | 1028:05d4 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     | ivbep_u... | C7E1E32971 |
| 8086:0e30 | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     | ivbep_u... | 07278BAD4B |

### Pic (8259) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:342e |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 256   | i7core_... | F140183571 |
| 8086:3422 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 254   |            | F140183571 |
| 8086:3423 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 254   |            | F140183571 |
| 8086:3438 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 162   | i5500_temp | F140183571 |
| 8086:3425 |           | Intel      | 7500/5520/5500/X58 Physic... | 88    |            | FA300CEB06 |
| 8086:3426 |           | Intel      | 7500/5520/5500/X58 Routin... | 88    |            | FA300CEB06 |
| 8086:3427 |           | Intel      | 7500/5520/5500 Physical a... | 79    |            | FA300CEB06 |
| 8086:3428 |           | Intel      | 7500/5520/5500 Routing & ... | 79    |            | FA300CEB06 |
| 8086:3422 | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 21    |            | FD20ECEEC0 |
| 8086:3423 | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 21    |            | FD20ECEEC0 |
| 8086:342e | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 21    | i7core_... | FD20ECEEC0 |
| 8086:3422 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 12    |            | DF7A5AC424 |
| 8086:3423 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 12    |            | DF7A5AC424 |
| 8086:342e | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 12    | i7core_... | DF7A5AC424 |
| 8086:3422 | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 11    |            | 4D1157B020 |
| 8086:3423 | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 11    |            | 4D1157B020 |
| 8086:342e | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 11    | i7core_... | 4D1157B020 |
| 8086:3422 | 0086:0022 | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     |            | D4CEB4D3BC |
| 8086:3423 | 0086:0023 | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     |            | D4CEB4D3BC |
| 8086:342e | 0086:002e | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     | i7core_... | D4CEB4D3BC |
| 8086:3422 | 0028:006d | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | 82F1FBFA97 |
| 8086:3422 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | B2D6DABAA7 |
| 8086:3423 | 0028:006d | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | 82F1FBFA97 |
| 8086:3423 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | B2D6DABAA7 |
| 8086:3425 | 0043:0063 | Intel      | 7500/5520/5500/X58 Physic... | 4     |            | B2D6DABAA7 |
| 8086:3426 | 0043:0063 | Intel      | 7500/5520/5500/X58 Routin... | 4     |            | B2D6DABAA7 |
| 8086:3427 | 0043:0063 | Intel      | 7500/5520/5500 Physical a... | 4     |            | B2D6DABAA7 |
| 8086:3428 | 0043:0063 | Intel      | 7500/5520/5500 Routing & ... | 4     |            | B2D6DABAA7 |
| 8086:342e | 0028:006d | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     | i7core_... | 82F1FBFA97 |
| 8086:342e | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     | i7core_... | B2D6DABAA7 |
| 8086:3438 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     | i5500_temp | B2D6DABAA7 |
| 8086:3422 | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     |            | 138B84322E |
| 8086:3423 | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     |            | 138B84322E |
| 8086:3425 | 0086:00dc | Intel      | 7500/5520/5500/X58 Physic... | 3     |            | 138B84322E |
| 8086:3426 | 0086:00dc | Intel      | 7500/5520/5500/X58 Routin... | 3     |            | 138B84322E |
| 8086:3427 | 0086:00dc | Intel      | 7500/5520/5500 Physical a... | 3     |            | 138B84322E |
| 8086:3428 | 0086:00dc | Intel      | 7500/5520/5500 Routing & ... | 3     |            | 138B84322E |
| 8086:342e | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     | i7core_... | 138B84322E |
| 8086:3438 | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     | i5500_temp | 138B84322E |
| 8086:3422 | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     |            | DEC98C8F86 |
| 8086:3423 | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     |            | DEC98C8F86 |
| 8086:3425 | 0086:00da | Intel      | 7500/5520/5500/X58 Physic... | 2     |            | DEC98C8F86 |
| 8086:3426 | 0086:00da | Intel      | 7500/5520/5500/X58 Routin... | 2     |            | DEC98C8F86 |
| 8086:3427 | 0086:00da | Intel      | 7500/5520/5500 Physical a... | 2     |            | DEC98C8F86 |
| 8086:3428 | 0086:00da | Intel      | 7500/5520/5500 Routing & ... | 2     |            | DEC98C8F86 |
| 8086:342e | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     | i7core_... | DEC98C8F86 |
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
| 8086:342f |           | Intel      | 7500/5520/5500/X58 Truste... | 79    |            | FA300CEB06 |
| 8086:342d |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 74    |            | FA300CEB06 |
| 8086:2026 | 8086:2026 | Intel      | Sky Lake-E IOAPIC            | 57    |            | 0217F128CA |
| 8086:2036 | 8086:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 57    |            | 0217F128CA |
| 1106:5364 |           | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 38    |            | 5A1BBCBC9E |
| 8086:2f2c | 8086:0000 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 37    |            | E5DA683598 |
| 8086:3c2c | 8086:3c2c | Intel      | Xeon E5/Core i7 I/O APIC     | 25    |            | BAF893B7F3 |
| 8086:0e2c | 8086:0e2c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 24    |            | 41EEB14B47 |
| 8086:3c2c | 1043:84ef | Intel      | Xeon E5/Core i7 I/O APIC     | 24    |            | 39F22D868E |
| 1106:5327 |           | VIA Tec... | P4M890 I/O APIC Interrupt... | 23    |            | 3FB3954AB5 |
| 8086:6f2c | 8086:0000 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 19    |            | 65DF5317A4 |
| 8086:0e2c | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 17    |            | EEE7D322DF |
| 8086:6f2c | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:0e2c | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    |            | 53FB02A9EF |
| 8086:3c2c | 1458:5000 | Intel      | Xeon E5/Core i7 I/O APIC     | 11    |            | 82A8163E58 |
| 1106:5336 |           | VIA Tec... | K8M890CE I/O APIC Interru... | 10    |            | FEDA3B155D |
| 8086:2f2c | 1028:0617 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 9     |            | 3B5017848A |
| 8086:3c2c | 103c:18a8 | Intel      | Xeon E5/Core i7 I/O APIC     | 8     |            | 80E0B0265B |
| 1106:5364 | 1106:5364 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 7     |            | B991274CE3 |
| 8086:0e2c | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 7     |            | 8EAFAB46BF |
| 8086:2f2c | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 7     |            | FDE33600E4 |
| 1106:5308 | 1849:5308 | VIA Tec... | PT894 I/O APIC Interrupt ... | 6     |            | FFD7AFA075 |
| 1106:5364 | 103c:3030 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 5     |            | 99478A8C67 |
| 8086:3504 |           | Intel      | 6311ESB/6321ESB I/OxAPIC ... | 5     |            | 0061EDE59F |
| 8086:3c2c | 1849:3c2c | Intel      | Xeon E5/Core i7 I/O APIC     | 5     |            | 1B28CC994F |
| 1106:5238 |           | VIA Tec... | K8T890 I/O APIC Interrupt... | 4     |            | D9174E33E4 |
| 8086:2026 | 8086:0000 | Intel      | Sky Lake-E IOAPIC            | 4     |            | 931EA9A398 |
| 8086:2036 | 8086:0000 | Intel      | Sky Lake-E IOxAPIC Config... | 4     |            | 931EA9A398 |
| 8086:2f2c | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | C9D389B2A3 |
| 8086:2f2c | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | FD108DE325 |
| 8086:2f2c | 15d9:0857 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | 3347A5EBB1 |
| 8086:2f2c | 1849:2f2c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | 917E16476B |
| 8086:6f2c | 1849:6f2c | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     |            | B09A16F73F |
| 1106:5336 | 1043:8297 | VIA Tec... | K8M890CE I/O APIC Interru... | 3     |            | 476F99FF1B |
| 1106:5351 |           | VIA Tec... | VT3351 I/O APIC Interrupt... | 3     |            | EBF0DCD676 |
| 1106:5353 | 17aa:388a | VIA Tec... | VX800/VX820 APIC and Cent... | 3     |            | 4AA0EF1314 |
| 1106:5364 | 1849:5364 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 3     |            | 78DDA2C16B |
| 8086:0e2c | 1458:5000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     |            | DD20758A89 |
| 8086:342d | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     |            | 138B84322E |
| 8086:342f | 0086:00dc | Intel      | 7500/5520/5500/X58 Truste... | 3     |            | 138B84322E |
| 8086:3c2c | 1028:0497 | Intel      | Xeon E5/Core i7 I/O APIC     | 3     |            | F1D5B6204E |
| 1106:5327 | 1849:5327 | VIA Tec... | P4M890 I/O APIC Interrupt... | 2     |            | DAD584057B |
| 8086:0326 |           | Intel      | 6700/6702PXH I/OxAPIC Int... | 2     |            | 96D2EFD1F4 |
| 8086:0326 | 103c:12f1 | Intel      | 6700/6702PXH I/OxAPIC Int... | 2     |            | 21D968D1E3 |
| 8086:0326 | 15d9:7980 | Intel      | 6700/6702PXH I/OxAPIC Int... | 2     |            | 8EB1C21341 |
| 8086:0327 | 103c:12f1 | Intel      | 6700PXH I/OxAPIC Interrup... | 2     |            | 21D968D1E3 |
| 8086:0e2c | 1028:05d4 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | C7E1E32971 |
| 8086:0e2c | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | 07278BAD4B |
| 8086:0e2c | 1734:11b5 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | 961A7ADB3E |
| 8086:2026 | 17aa:1038 | Intel      | Sky Lake-E IOAPIC            | 2     |            | 3AC4E6EB75 |
| 8086:2036 | 17aa:1038 | Intel      | Sky Lake-E IOxAPIC Config... | 2     |            | 3AC4E6EB75 |
| 8086:2f2c | 1028:0618 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     |            | 4C6E30FFB1 |
| 8086:2f2c | 1028:064c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     |            | E1BABF19AD |
| 8086:342d | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     |            | DEC98C8F86 |
| 8086:342f | 0086:00da | Intel      | 7500/5520/5500/X58 Truste... | 2     |            | DEC98C8F86 |
| 8086:3c2c | 1043:84f0 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | 996F55BB36 |
| 8086:3c2c | 1462:7760 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | 748D276276 |
| 8086:3c2c | 17aa:1027 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | B7463FD8F2 |
| 8086:3c2c | 17aa:1028 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | 7E1E79D0B1 |
| 8086:3c2c | 8086:357e | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | F65EC09250 |
| 8086:6f2c | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 140DAF886E |
| 8086:6f2c | 15d9:0824 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 6C96E4A591 |
| 8086:6f2c | 8086:6f2c | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 2903921AEB |
| 1106:5238 | 1734:1093 | VIA Tec... | K8T890 I/O APIC Interrupt... | 1     |            | E9825FB39A |
| 1106:5327 | 1631:e035 | VIA Tec... | P4M890 I/O APIC Interrupt... | 1     |            | B3494EC9DB |
| 1106:5351 | 1849:5351 | VIA Tec... | VT3351 I/O APIC Interrupt... | 1     |            | D3A94CD051 |
| 1106:5353 | 144d:c04e | VIA Tec... | VX800/VX820 APIC and Cent... | 1     |            | 3DDEF2506D |
| 1106:5364 | 1019:2125 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 1     |            | A098C98B04 |
| 1106:5409 | 1106:5409 | VIA Tec... | VX855/VX875 APIC and Cent... | 1     |            | 655547B351 |
| 8086:0326 | 103c:3208 | Intel      | 6700/6702PXH I/OxAPIC Int... | 1     |            | 2C877CF870 |
| 8086:0326 | 8086:3439 | Intel      | 6700/6702PXH I/OxAPIC Int... | 1     |            | 0F21E859FA |
| 8086:0327 |           | Intel      | 6700PXH I/OxAPIC Interrup... | 1     |            | 219383F559 |
| 8086:0327 | 103c:3208 | Intel      | 6700PXH I/OxAPIC Interrup... | 1     |            | 2C877CF870 |
| 8086:0327 | 8086:3439 | Intel      | 6700PXH I/OxAPIC Interrup... | 1     |            | 0F21E859FA |
| 8086:0e2c | 1043:84f0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 90D8E62525 |
| 8086:0e2c | 1462:7737 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 725B24FE69 |
| 8086:0e2c | 15d9:062a | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1E6B7CA63C |
| 8086:0e2c | 15d9:062f | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | F5F0A90676 |
| 8086:0e2c | 15d9:0665 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | CEC82EF5D0 |
| 8086:0e2c | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 8C793BB137 |
| 8086:0e2c | 15d9:070a | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | B4C8ABC585 |
| 8086:0e2c | 17aa:1026 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 5A6C7B0805 |
| 8086:0e2c | 1849:0e2c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 69907BBCE0 |
| 8086:0e2c | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | ACFF74E0DB |
| 8086:0e2c | 8086:357e | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 018029FB72 |
| 8086:1461 | 1014:1461 | Intel      | 82870P2 P64H2 I/OxAPIC       | 1     |            | D6D105AE70 |
| 8086:2026 | 1590:18a9 | Intel      | Sky Lake-E IOAPIC            | 1     |            | 9E91D0ED19 |
| 8086:2026 | 1734:122f | Intel      | Sky Lake-E IOAPIC            | 1     |            | 14943339B4 |
| 8086:2026 | 8086:35cd | Intel      | Sky Lake-E IOAPIC            | 1     |            | 9CF9DCEEE9 |
| 8086:2026 | 8086:35ce | Intel      | Sky Lake-E IOAPIC            | 1     |            | 9CF9DCEEE9 |
| 8086:2036 | 1590:18a9 | Intel      | Sky Lake-E IOxAPIC Config... | 1     |            | 9E91D0ED19 |
| 8086:2036 | 1734:122f | Intel      | Sky Lake-E IOxAPIC Config... | 1     |            | 14943339B4 |
| 8086:2036 | 8086:35cd | Intel      | Sky Lake-E IOxAPIC Config... | 1     |            | 9CF9DCEEE9 |
| 8086:25ac |           | Intel      | 6300ESB I/O Advanced Prog... | 1     |            | 21330F2BD7 |
| 8086:25ac | 8086:345e | Intel      | 6300ESB I/O Advanced Prog... | 1     |            | 97CC3C4274 |
| 8086:2f2c | 1028:0619 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | ADB52FAE26 |
| 8086:2f2c | 1462:7882 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 1E0208BF20 |
| 8086:2f2c | 15d9:0852 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 2E6D79F345 |
| 8086:2f2c | 19e5:2061 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 5EB4DFC951 |
| 8086:2f2c | 1d49:0a00 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 817865DED6 |

### Power pc (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1957:c006 | 1a56:1201 | Freesca... | MPC8308                      | 3     |            | 73857FA33C |
| 1957:0085 | 110a:4046 | Freesca... | MPC8347 PBGA                 | 1     |            | 60A7685D8D |
| 1957:00b6 | 1a56:1103 | Freesca... | MPC8314E                     | 1     |            | 703D6110A9 |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:16bc | 1025:0647 | Broadco... | BCM57765/57785 SDXC/MMC C... | 234   | sdhci_pci  | 9084C70732 |
| 197b:2381 | 1043:1a07 | JMicron... | Standard SD Host Controller  | 121   | sdhci_pci  | 088FFC2823 |
| 14e4:16bc | 1025:0504 | Broadco... | BCM57765/57785 SDXC/MMC C... | 104   | sdhci_pci  | 832F6EF100 |
| 14e4:16bc | 14e4:0000 | Broadco... | BCM57765/57785 SDXC/MMC C... | 88    | sdhci_pci  | F82FCD2051 |
| 1180:0822 | 17aa:20c8 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 77    | sdhci_pci  | 1A90AC4588 |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 74    | sdhci_pci  | 97BCBB884E |
| 104c:803c | 1025:011f | Texas I... | PCIxx12 SDA Standard Comp... | 71    | sdhci_pci  | BA9EFF4F3B |
| 1022:7806 | 1022:7806 | AMD        | FCH SD Flash Controller      | 65    | sdhci_pci  | 2AF2FAFEE0 |
| 1022:7813 | 17aa:3801 | AMD        | FCH SD Flash Controller      | 63    | sdhci_pci  | 363B08984A |
| 14e4:16bc | 1025:0775 | Broadco... | BCM57765/57785 SDXC/MMC C... | 58    | sdhci_pci  | 94CD691A35 |
| 1180:e822 | 104d:9071 | Ricoh      | MMC/SD Host Controller       | 56    | sdhci_pci  | 90D3759348 |
| 8086:9d2d | 8086:9d2d | Intel      | Sunrise Point-LP Secure D... | 54    | sdhci_pci  | D720B44576 |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 52    | sdhci_pci  | E6212ECE14 |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 51    | sdhci_pci  | E6212ECE14 |
| 1217:8221 | 1028:0493 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 39    | sdhci_pci  | CA779DE74C |
| 10ec:5209 | 10ec:5209 | Realtek... | RTS5209 PCI Express Card ... | 36    | sdhci_pci  | 4C52CE8BDE |
| 1180:0822 | 1028:0233 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 34    | sdhci_pci  | 314E0FF832 |
| 1524:0550 | 1025:0090 | ENE Tec... | ENE PCI Secure Digital Ca... | 34    | sdhci_pci  | 5979EB4500 |
| 197b:2391 | 103c:17f6 | JMicron... | Standard SD Host Controller  | 33    | sdhci_pci  | 1F9408B984 |
| 1180:e822 | 1028:040a | Ricoh      | MMC/SD Host Controller       | 31    | sdhci_pci  | 3E3F341EF4 |
| 1180:0822 | 1028:022f | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 29    | sdhci_pci  | 56866B9E4C |
| 1180:0822 | 103c:30cc | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 29    | sdhci_pci  | 218FD78ECA |
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 29    | sdhci_pci  | DAEDE56DC8 |
| 197b:2391 | 103c:161c | JMicron... | Standard SD Host Controller  | 28    | sdhci_pci  | 3EAB448396 |
| 197b:2391 | 103c:167c | JMicron... | Standard SD Host Controller  | 27    | sdhci_pci  | A56D8D1C28 |
| 104c:803c | 1179:ff00 | Texas I... | PCIxx12 SDA Standard Comp... | 26    | sdhci_pci  | CCB7CB26D3 |
| 1524:0550 | 1025:009f | ENE Tec... | ENE PCI Secure Digital Ca... | 26    | sdhci_pci  | 005CF3D43E |
| 197b:2391 | 103c:179b | JMicron... | Standard SD Host Controller  | 25    | sdhci_pci  | 7195452FF3 |
| 10ec:5209 | 103c:3388 | Realtek... | RTS5209 PCI Express Card ... | 24    | sdhci_pci  | C7D96BB884 |
| 1180:0822 | 1028:01f5 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 24    | sdhci_pci  | 3D6C8F2267 |
| 1969:3010 | 1025:076b | Qualcom... | Secure Digital Card Reader   | 24    | sdhci_pci  | EE73C8C19D |
| 1022:7813 | 1025:104b | AMD        | FCH SD Flash Controller      | 23    | sdhci_pci  | E164F394F1 |
| 1180:0822 | 1025:011e | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 23    | sdhci_pci  | 3530E5C8F1 |
| 1180:0822 | 103c:7008 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 23    | sdhci_pci  | 4663DEB0DD |
| 1180:0843 | 1028:0233 | Ricoh      | R5C843 MMC Host Controller   | 22    | sdhci_pci  | C6A19F5810 |
| 1217:7120 | 1179:ff50 | O2 Micro   | Integrated MMC/SD Controller | 21    | sdhci_pci  | 6108B0C47E |
| 1217:8221 | 1028:0534 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 21    | sdhci_pci  | 39D47C0F09 |
| 1180:0822 | 1025:0121 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 20    | sdhci_pci  | C1C791C270 |
| 1180:0822 | 1025:0126 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 20    | sdhci_pci  | 590A68AE68 |
| 1180:0822 | 103c:30cf | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 20    | sdhci_pci  | AB1EF36E83 |
| 1180:0822 | 1043:1627 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 20    | sdhci_pci  | 6C6A2138D2 |
| 1180:0822 | 1043:1877 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 20    | sdhci_pci  | A970D9DFC5 |
| 1217:7120 | 1025:013c | O2 Micro   | Integrated MMC/SD Controller | 20    | sdhci_pci  | A8E4D6D25F |
| 1217:8621 | 17aa:5068 | O2 Micro   | SD/MMC Card Reader Contro... | 20    | sdhci_pci  | F4826C3A2A |
| 197b:2391 | 17aa:3976 | JMicron... | Standard SD Host Controller  | 20    | sdhci_pci  | 6177430B68 |
| 1022:7813 | 17aa:3800 | AMD        | FCH SD Flash Controller      | 19    | sdhci_pci  | B4CE12C939 |
| 197b:2381 | 17aa:212d | JMicron... | Standard SD Host Controller  | 19    | sdhci_pci  | 4B5548D0BB |
| 8086:9d2b | 8086:7270 | Intel      | Skylake-U/Y SCC: eMMC        | 19    | sdhci_pci  | C96C722A74 |
| 1022:7806 | 1043:107c | AMD        | FCH SD Flash Controller      | 18    | sdhci_pci  | 6A47875DF8 |
| 1217:8520 | 1028:05be | O2 Micro   | SD/MMC Card Reader Contro... | 18    | sdhci_pci  | C7F7A6189C |
| 8086:9d2d | 8086:7270 | Intel      | Sunrise Point-LP Secure D... | 18    | sdhci_pci  | C96C722A74 |
| 104c:803c | 1179:ff02 | Texas I... | PCIxx12 SDA Standard Comp... | 17    | sdhci_pci  | 3CE1664885 |
| 1180:0822 | 1043:1317 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 17    | sdhci_pci  | 4841CD6D3C |
| 1180:0822 | 10f7:8338 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 17    | sdhci_pci  | 3B2DF65591 |
| 1180:e822 | 1028:040b | Ricoh      | MMC/SD Host Controller       | 17    | sdhci_pci  | A13B3BB6D9 |
| 1217:8520 | 17aa:3800 | O2 Micro   | SD/MMC Card Reader Contro... | 17    | sdhci_pci  | B57E5735A5 |
| 14e4:16bc | 1025:0605 | Broadco... | BCM57765/57785 SDXC/MMC C... | 17    | sdhci_pci  | 72878CC6E9 |
| 197b:2381 | 103c:3628 | JMicron... | Standard SD Host Controller  | 17    | sdhci_pci  | BF5A8C1756 |
| 8086:31d0 | 8086:7270 | Intel      | SD Host Controller           | 17    | sdhci_pci  | 7E86F1B5E7 |
| 1022:7813 | 103c:8137 | AMD        | FCH SD Flash Controller      | 16    | sdhci_pci  | 225743793E |
| 104c:803c | 1179:ff10 | Texas I... | PCIxx12 SDA Standard Comp... | 16    | sdhci_pci  | 5FDCE37F38 |
| 1217:8321 | 1028:0494 | O2 Micro   | OZ600RJ0/OZ900RJ0/OZ600RJ... | 16    | sdhci_pci  | 4384225066 |
| 1180:0822 | 1028:01bd | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 15    | sdhci_pci  | AB555162C8 |
| 1180:0822 | 1028:024f | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 15    | sdhci_pci  | 9F216D6CB3 |
| 1180:0822 | 1043:1897 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 15    | sdhci_pci  | B720D65E19 |
| 14e4:16bc | 1025:0742 | Broadco... | BCM57765/57785 SDXC/MMC C... | 15    | sdhci_pci  | 868EC85E4C |
| 197b:2391 | 103c:17ab | JMicron... | Standard SD Host Controller  | 15    | sdhci_pci  | 57308077EE |
| 8086:9d2b | 1025:1085 | Intel      | Skylake-U/Y SCC: eMMC        | 15    | sdhci_pci  | 7528B75013 |
| 1180:0822 | 103c:172a | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 14    | sdhci_pci  | D1C32BF428 |
| 1180:0822 | 1043:14e7 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 14    | sdhci_pci  | 7AC6E3C864 |
| 1180:0822 | 104d:9035 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 14    | sdhci_pci  | 0C80B6E23F |
| 1217:8221 | 1028:0532 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 14    | sdhci_pci  | 8E240EEE56 |
| 1217:8520 | 1028:05ca | O2 Micro   | SD/MMC Card Reader Contro... | 14    | sdhci_pci  | C897C33BBA |
| 197b:2391 | 103c:1618 | JMicron... | Standard SD Host Controller  | 14    | sdhci_pci  | 0D2FE88BE0 |
| 1180:0822 | 103c:7007 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 13    | sdhci_pci  | 82CB2D5E90 |
| 1180:0822 | 1043:1517 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 13    | sdhci_pci  | 427546EA21 |
| 1180:0822 | 1179:ff1c | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 13    | sdhci_pci  | 420C738977 |
| 1217:8221 | 1028:0535 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 13    | sdhci_pci  | 813731AB25 |
| 1217:8221 | 1028:053c | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 13    | sdhci_pci  | F94D8B6C0A |
| 197b:2381 | 103c:3603 | JMicron... | Standard SD Host Controller  | 13    | sdhci_pci  | F2190D7446 |
| 1022:7813 | 1043:141d | AMD        | FCH SD Flash Controller      | 12    | sdhci_pci  | 1412692359 |
| 1022:7813 | 1043:148d | AMD        | FCH SD Flash Controller      | 12    | sdhci_pci  | 19ABB6C0FB |
| 104c:803c | 1025:0107 | Texas I... | PCIxx12 SDA Standard Comp... | 12    | sdhci_pci  | 290DB67DA7 |
| 1180:0822 | 1043:1767 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 12    | sdhci_pci  | 4137AC8F54 |
| 1217:8320 | 1028:04a3 | O2 Micro   | OZ600RJ1/OZ900RJ1 SD/MMC ... | 12    | sdhci_pci  | D8BA5B1425 |
| 1217:8321 | 1028:049a | O2 Micro   | OZ600RJ0/OZ900RJ0/OZ600RJ... | 12    | sdhci_pci  | 6FD4500E86 |
| 1217:8520 | 1028:05de | O2 Micro   | SD/MMC Card Reader Contro... | 12    | sdhci_pci  | 872523B216 |
| 1217:8520 | 1028:062e | O2 Micro   | SD/MMC Card Reader Contro... | 12    | sdhci_pci  | 611A318D07 |
| 1524:0750 | 1025:012e | ENE Tec... | ENE PCI SmartMedia / xD C... | 12    | sdhci_pci  | 48841846AC |
| 197b:2381 | 103c:3659 | JMicron... | Standard SD Host Controller  | 12    | sdhci_pci  | B48F5D5FDD |
| 104c:803c | 1179:0001 | Texas I... | PCIxx12 SDA Standard Comp... | 11    | sdhci_pci  | 0C90DCED50 |
| 1180:0822 | 1028:022a | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 11    | sdhci_pci  | 7043CC968E |
| 1180:0822 | 1028:029a | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 11    | sdhci_pci  | 394D903321 |
| 1180:0822 | 103c:30db | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 11    | sdhci_pci  | 94AF8C86B1 |
| 1180:0822 | 1043:1017 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 11    | sdhci_pci  | F3C9C1F265 |
| 1180:0822 | 1043:1777 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 11    | sdhci_pci  | 9B7F075594 |
| 1217:8221 | 1028:0492 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 11    | sdhci_pci  | 5051F637C0 |
| 1217:8520 | 1028:05cb | O2 Micro   | SD/MMC Card Reader Contro... | 11    | sdhci_pci  | 19F3DF030D |
| 14e4:16bc | 1025:0500 | Broadco... | BCM57765/57785 SDXC/MMC C... | 11    | sdhci_pci  | 94A0B4FAB9 |
| 197b:2391 | 103c:162b | JMicron... | Standard SD Host Controller  | 11    | sdhci_pci  | 1257EBD709 |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a324 | 8086:7270 | Intel      | Cannon Lake PCH SPI Contr... | 95    |            | A47D005445 |
| 8086:a324 | 1043:8694 | Intel      | Cannon Lake PCH SPI Contr... | 53    |            | 0B771C098E |
| 8086:9da4 | 8086:7270 | Intel      | Cannon Point-LP SPI Contr... | 42    |            | 24F8864FB8 |
| 8086:a324 | 1849:a324 | Intel      | Cannon Lake PCH SPI Contr... | 28    |            | B0161E1E77 |
| 8086:a324 | 1025:1264 | Intel      | Cannon Lake PCH SPI Contr... | 24    |            | AF51F8907E |
| 8086:a324 | 1028:087c | Intel      | Cannon Lake PCH SPI Contr... | 24    |            | 18DC19F3EC |
| 8086:a368 | 1025:1264 | Intel      | Cannon Lake PCH Serial IO... | 24    | intel_lpss | AF51F8907E |
| 8086:a368 | 1028:087c | Intel      | Cannon Lake PCH Serial IO... | 24    | intel_l... | 18DC19F3EC |
| 8086:a369 | 1025:1264 | Intel      | Cannon Lake PCH Serial IO... | 24    | intel_lpss | AF51F8907E |
| 8086:a369 | 1028:087c | Intel      | Cannon Lake PCH Serial IO... | 24    | intel_l... | 18DC19F3EC |
| 8086:9da4 | 8086:2074 | Intel      | Cannon Point-LP SPI Contr... | 21    |            | B039AEFD9E |
| 8086:9da4 | 1028:08af | Intel      | Cannon Point-LP SPI Contr... | 19    |            | ED8598DB62 |
| 8086:9de8 | 1028:08af | Intel      | Cannon Point-LP Serial IO... | 19    | intel_l... | ED8598DB62 |
| 8086:9de9 | 1028:08af | Intel      | Cannon Point-LP Serial IO... | 19    | intel_l... | ED8598DB62 |
| 8086:9ce6 | 8086:9ce6 | Intel      | Wildcat Point-LP Serial I... | 17    | spi_pxa... | 1A26D7B485 |
| 8086:a324 | 1028:087d | Intel      | Cannon Lake PCH SPI Contr... | 17    |            | 5741F67096 |
| 8086:a368 | 1028:087d | Intel      | Cannon Lake PCH Serial IO... | 17    | intel_l... | 5741F67096 |
| 8086:a369 | 1028:087d | Intel      | Cannon Lake PCH Serial IO... | 17    | intel_l... | 5741F67096 |
| 8086:a1a4 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    |            | 4391DFF8D2 |
| 8086:9da4 | 17aa:2292 | Intel      | Cannon Point-LP SPI Contr... | 15    |            | 7C5B2D05AE |
| 8086:9de8 | 17aa:2292 | Intel      | Cannon Point-LP Serial IO... | 15    | intel_l... | 7C5B2D05AE |
| 8086:9de9 | 17aa:2292 | Intel      | Cannon Point-LP Serial IO... | 15    | intel_l... | 7C5B2D05AE |
| 8086:a32a | 1043:1e40 | Intel      | 300 Series Chipset Device    | 15    | intel_l... | F4689330D7 |
| 8086:9da4 | 17aa:2279 | Intel      | Cannon Point-LP SPI Contr... | 14    |            | F737A5A121 |
| 8086:9de8 | 17aa:2279 | Intel      | Cannon Point-LP Serial IO... | 14    | intel_l... | F737A5A121 |
| 8086:5ac8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 12    | pwm_lpss   | 2CBA62F744 |
| 8086:a324 | 1025:1238 | Intel      | Cannon Lake PCH SPI Contr... | 11    |            | FF435389C9 |
| 8086:a324 | 17aa:3801 | Intel      | Cannon Lake PCH SPI Contr... | 11    |            | DA4DF48AE5 |
| 8086:a368 | 1043:1fc0 | Intel      | Cannon Lake PCH Serial IO... | 11    | intel_lpss | 5129A11C87 |
| 8086:a368 | 17aa:3806 | Intel      | Cannon Lake PCH Serial IO... | 11    | intel_lpss | DA4DF48AE5 |
| 8086:a369 | 1043:1fc0 | Intel      | Cannon Lake PCH Serial IO... | 11    | intel_lpss | 5129A11C87 |
| 8086:a369 | 17aa:3809 | Intel      | Cannon Lake PCH Serial IO... | 11    | intel_lpss | DA4DF48AE5 |
| 8086:9da4 | 103c:8549 | Intel      | Cannon Point-LP SPI Contr... | 10    |            | 0B8C8AB6F3 |
| 8086:9da4 | 17aa:380c | Intel      | Cannon Point-LP SPI Contr... | 10    |            | 0886AD75BB |
| 8086:9de8 | 103c:8549 | Intel      | Cannon Point-LP Serial IO... | 10    | intel_l... | 0B8C8AB6F3 |
| 8086:9de8 | 17aa:3813 | Intel      | Cannon Point-LP Serial IO... | 10    | intel_l... | 0886AD75BB |
| 8086:9de9 | 103c:8549 | Intel      | Cannon Point-LP Serial IO... | 10    | intel_l... | 0B8C8AB6F3 |
| 8086:a324 | 1028:086f | Intel      | Cannon Lake PCH SPI Contr... | 10    |            | C4FE97CCA2 |
| 8086:a368 | 1028:086f | Intel      | Cannon Lake PCH Serial IO... | 10    | intel_l... | C4FE97CCA2 |
| 8086:a369 | 1028:086f | Intel      | Cannon Lake PCH Serial IO... | 10    | intel_l... | C4FE97CCA2 |
| 8086:22c6 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 9     | i2c_des... | C7D9257057 |
| 8086:22c7 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 9     | i2c_des... | C7D9257057 |
| 8086:9da4 | 103c:8532 | Intel      | Cannon Point-LP SPI Contr... | 9     |            | 30DE8A33D7 |
| 8086:a324 | 1028:0825 | Intel      | Cannon Lake PCH SPI Contr... | 9     |            | 588F6AB038 |
| 8086:a324 | 17aa:2267 | Intel      | Cannon Lake PCH SPI Contr... | 9     |            | 539C9F807E |
| 8086:a368 | 1028:0825 | Intel      | Cannon Lake PCH Serial IO... | 9     | intel_l... | 588F6AB038 |
| 8086:a368 | 17aa:2267 | Intel      | Cannon Lake PCH Serial IO... | 9     | intel_lpss | 539C9F807E |
| 8086:a369 | 1028:0825 | Intel      | Cannon Lake PCH Serial IO... | 9     | intel_l... | 588F6AB038 |
| 8086:a324 | 103c:8478 | Intel      | Cannon Lake PCH SPI Contr... | 8     |            | F473523657 |
| 10de:1adb | 10de:0000 | Nvidia     | TU106 USB Type-C UCSI Con... | 7     | i2c_nvi... | 944DBD3519 |
| 8086:9da4 | 1028:08c9 | Intel      | Cannon Point-LP SPI Contr... | 7     |            | 9FB7AB0162 |
| 8086:9da4 | 17aa:5072 | Intel      | Cannon Point-LP SPI Contr... | 7     |            | 738D96E3F2 |
| 8086:9da4 | 8086:9da4 | Intel      | Cannon Point-LP SPI Contr... | 7     |            | C7DFFC3F2A |
| 8086:9daa | 1043:1461 | Intel      | 8th Gen Intel Core Proces... | 7     | intel_lpss | 67F2124D45 |
| 8086:9dc5 | 1028:08c9 | Intel      | Cannon Point-LP Serial IO... | 7     | intel_l... | 9FB7AB0162 |
| 8086:9dc5 | 1043:14a1 | Intel      | Cannon Point-LP Serial IO... | 7     | intel_l... | 30C00CB837 |
| 8086:9de8 | 1028:08c9 | Intel      | Cannon Point-LP Serial IO... | 7     | intel_l... | 9FB7AB0162 |
| 8086:9de8 | 1043:1461 | Intel      | Cannon Point-LP Serial IO... | 7     | intel_lpss | 67F2124D45 |
| 8086:9de8 | 1043:14a1 | Intel      | Cannon Point-LP Serial IO... | 7     | intel_l... | 30C00CB837 |
| 8086:9de9 | 1028:08c9 | Intel      | Cannon Point-LP Serial IO... | 7     | intel_l... | 9FB7AB0162 |
| 8086:9de9 | 1043:1461 | Intel      | Cannon Point-LP Serial IO... | 7     | intel_lpss | 67F2124D45 |
| 8086:9de9 | 1043:14a1 | Intel      | Cannon Point-LP Serial IO... | 7     | intel_l... | 30C00CB837 |
| 8086:9deb | 1043:14a1 | Intel      | 8th Gen Intel Core Proces... | 7     | intel_l... | 30C00CB837 |
| 8086:a324 | 1462:7b98 | Intel      | Cannon Lake PCH SPI Contr... | 7     |            | 947E963CAC |
| 8086:a324 | 17aa:3802 | Intel      | Cannon Lake PCH SPI Contr... | 7     |            | 0C7FD1D5D6 |
| 8086:a368 | 17aa:3807 | Intel      | Cannon Lake PCH Serial IO... | 7     | intel_l... | 0C7FD1D5D6 |
| 8086:a369 | 17aa:3808 | Intel      | Cannon Lake PCH Serial IO... | 7     | intel_l... | 0C7FD1D5D6 |
| 10de:1adb | 1028:0000 | Nvidia     | TU106 USB Type-C UCSI Con... | 6     | i2c_nvi... | DAE953BAB0 |
| 8086:9c66 |           | Intel      | 8 Series SPI Controller #1   | 6     |            | 52DA4E98F9 |
| 8086:9da4 | 1025:128d | Intel      | Cannon Point-LP SPI Contr... | 6     |            | D2C618DB7F |
| 8086:9da4 | 1558:1323 | Intel      | Cannon Point-LP SPI Contr... | 6     |            | 295D63C071 |
| 8086:9daa | 1043:1501 | Intel      | 8th Gen Intel Core Proces... | 6     | intel_lpss | CF0266106B |
| 8086:9daa | 1043:1961 | Intel      | 8th Gen Intel Core Proces... | 6     | intel_lpss | BAEE55FB37 |
| 8086:9dc5 | 1043:1501 | Intel      | Cannon Point-LP Serial IO... | 6     | intel_lpss | CF0266106B |
| 8086:9dc5 | 1043:1961 | Intel      | Cannon Point-LP Serial IO... | 6     | intel_lpss | BAEE55FB37 |
| 8086:9de8 | 1025:128d | Intel      | Cannon Point-LP Serial IO... | 6     | intel_lpss | D2C618DB7F |
| 8086:9de8 | 1043:1501 | Intel      | Cannon Point-LP Serial IO... | 6     | intel_lpss | CF0266106B |
| 8086:9de8 | 1043:1961 | Intel      | Cannon Point-LP Serial IO... | 6     | intel_lpss | BAEE55FB37 |
| 8086:9de8 | 17aa:380b | Intel      | Cannon Point-LP Serial IO... | 6     | intel_l... | C7DFFC3F2A |
| 8086:9de9 | 1025:128d | Intel      | Cannon Point-LP Serial IO... | 6     | intel_lpss | D2C618DB7F |
| 8086:9de9 | 1043:1501 | Intel      | Cannon Point-LP Serial IO... | 6     | intel_lpss | CF0266106B |
| 8086:9de9 | 1043:1961 | Intel      | Cannon Point-LP Serial IO... | 6     | intel_lpss | BAEE55FB37 |
| 8086:9de9 | 17aa:3804 | Intel      | Cannon Point-LP Serial IO... | 6     | intel_l... | C7DFFC3F2A |
| 8086:9dea | 17aa:3802 | Intel      | 8th Gen Intel Core Proces... | 6     | intel_l... | C7DFFC3F2A |
| 8086:a324 | 1025:123c | Intel      | Cannon Lake PCH SPI Contr... | 6     |            | EE7C4D9088 |
| 8086:a324 | 1028:0870 | Intel      | Cannon Lake PCH SPI Contr... | 6     |            | 624E7A0D96 |
| 8086:a324 | 1462:1227 | Intel      | Cannon Lake PCH SPI Contr... | 6     |            | A9A218F5DD |
| 8086:a368 | 1028:0870 | Intel      | Cannon Lake PCH Serial IO... | 6     | intel_l... | 624E7A0D96 |
| 8086:a369 | 1028:0870 | Intel      | Cannon Lake PCH Serial IO... | 6     | intel_l... | 624E7A0D96 |
| 10de:1ad7 | 1458:37c4 | Nvidia     | TU102 USB Type-C UCSI Con... | 5     | i2c_nvi... | 9CF9DCEEE9 |
| 8086:22c1 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 5     | i2c_des... | 287D86CC83 |
| 8086:9da4 | 1558:1325 | Intel      | Cannon Point-LP SPI Contr... | 5     |            | 8EC259BBD3 |
| 8086:9da4 | 19e5:3e09 | Intel      | Cannon Point-LP SPI Contr... | 5     |            | D60073EAD5 |
| 8086:9dab | 19e5:3e09 | Intel      | 8th Gen Intel Core Proces... | 5     | intel_l... | D60073EAD5 |
| 8086:9de8 | 1558:1325 | Intel      | Cannon Point-LP Serial IO... | 5     | intel_l... | 8EC259BBD3 |
| 8086:9de8 | 19e5:3e09 | Intel      | Cannon Point-LP Serial IO... | 5     | intel_l... | D60073EAD5 |
| 8086:9de9 | 19e5:3e09 | Intel      | Cannon Point-LP Serial IO... | 5     | intel_l... | D60073EAD5 |
| 8086:a1a4 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 5     |            | 8E73F804F5 |
| 8086:a324 | 1028:0824 | Intel      | Cannon Lake PCH SPI Contr... | 5     |            | 38C80D9545 |
| 8086:a324 | 103c:84da | Intel      | Cannon Lake PCH SPI Contr... | 5     |            | 605A299A65 |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8c3d | 1458:1c3a | Intel      | 8 Series/C220 Series Chip... | 61    | serial     | 4D53809886 |
| 8086:3b67 | 17aa:2162 | Intel      | 5 Series/3400 Series Chip... | 44    | serial     | 9A495F134B |
| 8086:2a47 | 17aa:20ec | Intel      | Mobile 4 Series Chipset A... | 43    | serial     | 7AD5A75B0A |
| 8086:1c3d | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 37    | serial     | AB2CEA0D81 |
| 8086:2e17 | 1028:027f | Intel      | 4 Series Chipset Serial K... | 29    | serial     | 439AF540E7 |
| 8086:1e3d | 17aa:21f3 | Intel      | 7 Series/C210 Series Chip... | 27    | serial     | B162D0FD81 |
| 8086:29b7 | 1028:0211 | Intel      | 82Q35 Express Serial KT C... | 25    | serial     | E23742C63F |
| 8086:1e3d | 17aa:21f6 | Intel      | 7 Series/C210 Series Chip... | 24    | serial     | D4095EF900 |
| 8086:2e17 | 103c:3048 | Intel      | 4 Series Chipset Serial K... | 23    | serial     | 733B76A48E |
| 8086:2e17 | 1028:0420 | Intel      | 4 Series Chipset Serial K... | 22    | serial     | 5151CB704B |
| 8086:1e3d | 17aa:21fa | Intel      | 7 Series/C210 Series Chip... | 21    | serial     | AD8913BB6B |
| 8086:1c3d | 103c:161c | Intel      | 6 Series/C200 Series Chip... | 20    | serial     | E8BE126153 |
| 8086:2e17 | 1734:114c | Intel      | 4 Series Chipset Serial K... | 20    | serial     | 9632357AEB |
| 8086:3b67 | 8086:0036 | Intel      | 5 Series/3400 Series Chip... | 20    | serial     | A57DCF32AA |
| 8086:8c3d | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 20    | serial     | 01AC5D53D2 |
| 8086:9c3d | 17aa:220c | Intel      | 8 Series HECI KT             | 20    | serial     | CE53F07ED9 |
| 8086:8c3d | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 19    | serial     | E6F6F65F88 |
| 8086:1e3d | 1028:0577 | Intel      | 7 Series/C210 Series Chip... | 17    | serial     | 90FC9AFA3E |
| 8086:1e3d | 103c:3397 | Intel      | 7 Series/C210 Series Chip... | 17    | serial     | E68AA86510 |
| 8086:1e3d | 103c:179b | Intel      | 7 Series/C210 Series Chip... | 16    | serial     | 3E4C38B4BE |
| 8086:1e3d | 103c:339a | Intel      | 7 Series/C210 Series Chip... | 16    | serial     | 2962B36D7E |
| 8086:29b7 | 103c:2818 | Intel      | 82Q35 Express Serial KT C... | 16    | serial     | 844CB3BF90 |
| 8086:1c3d | 1028:047e | Intel      | 6 Series/C200 Series Chip... | 15    | serial     | 858ED45F37 |
| 8086:1c3d | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 15    | serial     | 2D378E81BE |
| 8086:3b67 | 103c:7008 | Intel      | 5 Series/3400 Series Chip... | 15    | serial     | 4663DEB0DD |
| 8086:9c3d | 103c:198f | Intel      | 8 Series HECI KT             | 15    | serial     | 756C79455B |
| 8086:1c3d | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 14    | serial     | DA7FEA9DD2 |
| 8086:2e17 | 103c:3034 | Intel      | 4 Series Chipset Serial K... | 14    | serial     | A40772FC80 |
| 8086:1d3d | 103c:1589 | Intel      | C600/X79 series chipset K... | 13    | serial     | 9D85C4CA60 |
| 8086:2e17 | 17aa:3048 | Intel      | 4 Series Chipset Serial K... | 13    | serial     | 2BFF73F199 |
| 8086:2e17 | 1028:0276 | Intel      | 4 Series Chipset Serial K... | 12    | serial     | C05B5B48DE |
| 8086:3b67 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 12    | serial     | 3E3F341EF4 |
| 8086:8c3d | 103c:18e7 | Intel      | 8 Series/C220 Series Chip... | 12    | serial     | 5A54F0AEAE |
| 9710:9865 | a000:1000 | MosChip... | PCI 9865 Multi-I/O Contro... | 12    | parport_pc | 8D6C4235C3 |
| 8086:1c3d | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 11    | serial     | CA779DE74C |
| 8086:3b67 | 103c:172a | Intel      | 5 Series/3400 Series Chip... | 11    | serial     | D1C32BF428 |
| 8086:3b67 | 103c:7007 | Intel      | 5 Series/3400 Series Chip... | 11    | serial     | 25F2766AA4 |
| 8086:8c3d | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 11    | serial     | D30516DD82 |
| 8086:1c3d | 103c:1495 | Intel      | 6 Series/C200 Series Chip... | 10    | serial     | D56240BFB5 |
| 8086:1c3d | 103c:1497 | Intel      | 6 Series/C200 Series Chip... | 10    | serial     | 51C0A64A32 |
| 8086:1c3d | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 10    | serial     | DF04D39AC3 |
| 8086:1c3d | 17aa:21d2 | Intel      | 6 Series/C200 Series Chip... | 10    | serial     | 53037BE14E |
| 8086:1e3d | 1458:1c3a | Intel      | 7 Series/C210 Series Chip... | 10    | serial     | 508430F6F8 |
| 8086:2e17 | 103c:3646 | Intel      | 4 Series Chipset Serial K... | 10    | serial     | B84B8A2AAE |
| 8086:8c3d | 1028:05be | Intel      | 8 Series/C220 Series Chip... | 10    | serial     | D78531B63C |
| 8086:9d3d | 103c:8079 | Intel      | Sunrise Point-LP Active M... | 10    | serial     | 13C0B5A2EE |
| 8086:1c3d | 1028:0494 | Intel      | 6 Series/C200 Series Chip... | 9     | serial     | 4384225066 |
| 8086:1c3d | 103c:1618 | Intel      | 6 Series/C200 Series Chip... | 9     | serial     | 0D2FE88BE0 |
| 8086:1c3d | 103c:162b | Intel      | 6 Series/C200 Series Chip... | 9     | serial     | FAF97CF550 |
| 8086:29b7 | 1043:8295 | Intel      | 82Q35 Express Serial KT C... | 9     | serial     | 9057FD4986 |
| 8086:3b67 | 1028:040b | Intel      | 5 Series/3400 Series Chip... | 9     | serial     | 3A85FD0475 |
| 8086:3b67 | 103c:304b | Intel      | 5 Series/3400 Series Chip... | 9     | serial     | 16542643A0 |
| 8086:9c3d | 1028:05ca | Intel      | 8 Series HECI KT             | 9     | serial     | C897C33BBA |
| 8086:1c3d | 103c:1494 | Intel      | 6 Series/C200 Series Chip... | 8     | serial     | B9CA27E33C |
| 8086:1e3d | 1028:052c | Intel      | 7 Series/C210 Series Chip... | 8     | serial     | 779B6B3344 |
| 8086:1e3d | 17aa:21fb | Intel      | 7 Series/C210 Series Chip... | 8     | serial     | 4433C4AB4E |
| 8086:3b67 | 10cf:152f | Intel      | 5 Series/3400 Series Chip... | 8     | serial     | E3DCD9CD51 |
| 8086:3b67 | 8086:3b67 | Intel      | 5 Series/3400 Series Chip... | 8     | serial     | 94B8C23EEF |
| 4348:3253 | 4348:3253 | WCH.CN     | CH352 PCI Dual Serial Por... | 7     | serial     | C87B5D73CA |
| 8086:1c3d | 17aa:3077 | Intel      | 6 Series/C200 Series Chip... | 7     | serial     | 6C4701993F |
| 8086:1e3d | 10cf:16ed | Intel      | 7 Series/C210 Series Chip... | 7     | serial     | DA5836E2AA |
| 8086:1e3d | 17aa:3084 | Intel      | 7 Series/C210 Series Chip... | 7     | serial     | A08028C506 |
| 8086:29b7 | 103c:2819 | Intel      | 82Q35 Express Serial KT C... | 7     | serial     | 775B90FA5A |
| 8086:8c3d | 103c:1905 | Intel      | 8 Series/C220 Series Chip... | 7     | serial     | F3873460A2 |
| 8086:8c3d | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 7     | serial     | 01F990EA56 |
| 8086:8c3d | 17aa:3097 | Intel      | 8 Series/C220 Series Chip... | 7     | serial     | F1886B084F |
| 9710:9912 | a000:1000 | MosChip... | PCIe 9912 Multi-I/O Contr... | 7     | serial     | 009DCD4A93 |
| 1c00:3250 | 1c00:3250 |            | WCH PCI Express              | 6     | parport... | BBC8B77127 |
| 8086:1c3d | 1028:04a3 | Intel      | 6 Series/C200 Series Chip... | 6     | serial     | D8BA5B1425 |
| 8086:1c3d | 17aa:21db | Intel      | 6 Series/C200 Series Chip... | 6     | serial     | 73176F470C |
| 8086:1c3d | 17aa:3070 | Intel      | 6 Series/C200 Series Chip... | 6     | serial     | 3EB7EB388C |
| 8086:1d3d | 103c:158a | Intel      | C600/X79 series chipset K... | 6     | serial     | BAF893B7F3 |
| 8086:1e3d | 1028:0534 | Intel      | 7 Series/C210 Series Chip... | 6     | serial     | 49D71B26E7 |
| 8086:1e3d | 103c:3396 | Intel      | 7 Series/C210 Series Chip... | 6     | serial     | 992938DD51 |
| 8086:29b7 | 17aa:3038 | Intel      | 82Q35 Express Serial KT C... | 6     | serial     | 6DF5762C6A |
| 8086:2a07 | 17aa:20d4 | Intel      | Mobile PM965/GM965 KT Con... | 6     | serial     | 6DC6A318E1 |
| 8086:2e17 | 103c:3035 | Intel      | 4 Series Chipset Serial K... | 6     | serial     | 035BC3CA39 |
| 8086:3b67 | 103c:1521 | Intel      | 5 Series/3400 Series Chip... | 6     | serial     | 283EC51B86 |
| 8086:3b67 | 103c:304a | Intel      | 5 Series/3400 Series Chip... | 6     | serial     | 32EDD7217C |
| 8086:8c3d | 10cf:17e0 | Intel      | 8 Series/C220 Series Chip... | 6     | serial     | CF73AE98A0 |
| 8086:8d3d | 1028:0617 | Intel      | C610/X99 series chipset K... | 6     | serial     | 945E8A152D |
| 8086:9c3d | 103c:1991 | Intel      | 8 Series HECI KT             | 6     | serial     | 4A533D1C93 |
| 8086:9dfc | 103c:8549 | Intel      | Cannon Point-LP Integrate... | 6     | intel_i... | 0B8C8AB6F3 |
| 1c00:2273 | 1c00:2273 |            | WCH PCI                      | 5     | serial     | 60CA74AFA7 |
| 8086:1c3d | 1028:0492 | Intel      | 6 Series/C200 Series Chip... | 5     | serial     | 5051F637C0 |
| 8086:1e3d | 103c:17a7 | Intel      | 7 Series/C210 Series Chip... | 5     | serial     | 930B0C48ED |
| 8086:1e3d | 103c:18df | Intel      | 7 Series/C210 Series Chip... | 5     | serial     | 88109B1B15 |
| 8086:1e3d | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 5     | serial     | 91535E2115 |
| 8086:1e3d | 17aa:21f9 | Intel      | 7 Series/C210 Series Chip... | 5     | serial     | A93A3068CC |
| 8086:1e3d | 17aa:3083 | Intel      | 7 Series/C210 Series Chip... | 5     | serial     | 5BE7CC1609 |
| 8086:29b7 | 1734:10fc | Intel      | 82Q35 Express Serial KT C... | 5     | serial     | FBD6F89151 |
| 8086:2a47 | 103c:30e7 | Intel      | Mobile 4 Series Chipset A... | 5     | serial     | E05FE6B4AB |
| 8086:2e17 | 8086:1003 | Intel      | 4 Series Chipset Serial K... | 5     | serial     | 4E93B3E62B |
| 8086:8c3d | 17aa:30a3 | Intel      | 8 Series/C220 Series Chip... | 5     | serial     | 7CC0E44901 |
| 8086:9c3d | 1028:05cb | Intel      | 8 Series HECI KT             | 5     | serial     | 19F3DF030D |
| 8086:9c3d | 17aa:2214 | Intel      | 8 Series HECI KT             | 5     | serial     | 688A1A737C |
| 8086:9c3d | 17aa:2218 | Intel      | 8 Series HECI KT             | 5     | serial     | C344D6572A |
| 8086:9d3d | 1028:06dc | Intel      | Sunrise Point-LP Active M... | 5     | serial     | 3C44DE609A |
| 8086:9d3d | 1028:081c | Intel      | Sunrise Point-LP Active M... | 5     | serial     | B4899BA50A |
| 8086:9d3d | 17aa:2233 | Intel      | Sunrise Point-LP Active M... | 5     | serial     | 6C8F4AD0D7 |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 152   | process... | AE477CA654 |
| 8086:3b32 | 17aa:2190 | Intel      | 5 Series/3400 Series Chip... | 96    | intel_ips  | 9A495F134B |
| 8086:5a8c |           | Intel      | Dynamic Platform and Ther... | 75    | process... | 97BCBB884E |
| 8086:9d27 | 1043:1d2d | Intel      | Sunrise Point-LP Serial I... | 75    | intel_lpss | D720B44576 |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 72    | intel_l... | 97BCBB884E |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 72    | intel_l... | 97BCBB884E |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 72    | intel_l... | 97BCBB884E |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 72    | intel_l... | 97BCBB884E |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 72    | intel_l... | 97BCBB884E |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 72    | intel_l... | 97BCBB884E |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 72    | intel_l... | 97BCBB884E |
| 8086:22dc | 7270:8086 | Intel      | Atom/Celeron/Pentium Proc... | 71    | process... | A92F12150A |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 71    | intel_l... | 97BCBB884E |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 71    | intel_l... | 97BCBB884E |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 71    | intel_l... | 97BCBB884E |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 71    | intel_l... | 97BCBB884E |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 70    | intel_l... | 97BCBB884E |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 70    | intel_l... | 97BCBB884E |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 70    | intel_l... | 97BCBB884E |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 69    | intel_l... | 97BCBB884E |
| 8086:3b32 | 17aa:38c0 | Intel      | 5 Series/3400 Series Chip... | 64    | intel_ips  | 15789D122D |
| 8086:9d29 | 1043:1d2d | Intel      | Sunrise Point-LP Serial I... | 62    | intel_lpss | D720B44576 |
| 8086:2932 | 17aa:3a1f | Intel      | 82801I (ICH9 Family) Ther... | 55    |            | 5986AA0AAC |
| 8086:9d31 | 8086:7270 | Intel      | Sunrise Point-LP Thermal ... | 55    | intel_p... | C96C722A74 |
| 8086:a379 | 1458:8888 | Intel      | Cannon Lake PCH Thermal C... | 55    | intel_p... | E097415087 |
| 8086:a131 | 1849:a131 | Intel      | 100 Series/C230 Series Ch... | 53    | intel_p... | 0E4F08FCA3 |
| 8086:0a03 | 8086:2010 | Intel      | Haswell-ULT Thermal Subsy... | 50    | process... | 64EDCECFF8 |
| 8086:3b32 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 48    | intel_ips  | 53ECD14649 |
| 8086:a131 | 1458:8888 | Intel      | 100 Series/C230 Series Ch... | 45    | intel_p... | 1947D37E81 |
| 8086:3b32 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 43    | intel_ips  | 088FFC2823 |
| 8086:5a8c | 1043:16a0 | Intel      | Dynamic Platform and Ther... | 40    | proc_th... | F885D0EE5F |
| 8086:5aac | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 40    | intel_lpss | F885D0EE5F |
| 8086:5ab4 | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 40    | intel_lpss | F885D0EE5F |
| 8086:9d60 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 38    | intel_l... | 85085D7FF6 |
| 8086:9d62 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 36    | intel_l... | 85085D7FF6 |
| 8086:3b32 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 35    | intel_ips  | 90D3759348 |
| 8086:9d61 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 35    | intel_l... | 85085D7FF6 |
| 8086:318c | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 34    | proc_th... | 59974C206C |
| 8086:31b4 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 34    | intel_lpss | 59974C206C |
| 8086:31b6 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 34    | intel_lpss | 59974C206C |
| 8086:31bc | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 34    | intel_lpss | 59974C206C |
| 8086:31be | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 34    | intel_lpss | 59974C206C |
| 8086:31c0 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 34    | intel_lpss | 59974C206C |
| 8086:31ee | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 34    | intel_lpss | 59974C206C |
| 8086:9d27 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 34    | intel_l... | C96C722A74 |
| 8086:0a03 | 1043:131d | Intel      | Haswell-ULT Thermal Subsy... | 33    | process... | 9F136B8761 |
| 8086:9d31 | 17aa:3861 | Intel      | Sunrise Point-LP Thermal ... | 33    | intel_p... | 91D8C5CEC3 |
| 8086:9d60 | 17aa:3865 | Intel      | Sunrise Point-LP Serial I... | 33    | intel_l... | 91D8C5CEC3 |
| 8086:a2b1 | 1849:a2b1 | Intel      | 200 Series PCH Thermal Su... | 33    |            | 1BB0C8F064 |
| 8086:3b32 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 31    | intel_ips  | 3E3F341EF4 |
| 8086:9c24 | 1043:131d | Intel      | 8 Series Thermal             | 31    | intel_p... | 9F136B8761 |
| 8086:9d60 | 1025:1193 | Intel      | Sunrise Point-LP Serial I... | 31    | intel_lpss | 02EEEC88C4 |
| 8086:9d61 | 1025:1193 | Intel      | Sunrise Point-LP Serial I... | 31    | intel_lpss | 02EEEC88C4 |
| 8086:9d63 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 31    | intel_l... | 85085D7FF6 |
| 8086:0153 | 1043:1587 | Intel      | 3rd Gen Core Processor Th... | 29    |            | A14ECCA066 |
| 8086:9d60 | 1025:1085 | Intel      | Sunrise Point-LP Serial I... | 29    | intel_l... | 8BC74BD7FB |
| 8086:9d61 | 1025:1085 | Intel      | Sunrise Point-LP Serial I... | 29    | intel_l... | 8BC74BD7FB |
| 8086:a131 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 29    | intel_p... | 53CD422052 |
| 8086:a379 | 1849:a379 | Intel      | Cannon Lake PCH Thermal C... | 28    | intel_p... | B0161E1E77 |
| 8086:1903 | 8086:1903 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 27    | process... | 442F0D1A5A |
| 8086:9c24 | 1043:16cd | Intel      | 8 Series Thermal             | 27    | intel_p... | 786924EC40 |
| 8086:9d31 | 1025:115f | Intel      | Sunrise Point-LP Thermal ... | 27    | intel_p... | A230640EC7 |
| 8086:9d60 | 1025:115f | Intel      | Sunrise Point-LP Serial I... | 27    | intel_l... | A230640EC7 |
| 8086:1903 | 103c:832a | Intel      | Xeon E3-1200 v5/E3-1500 v... | 26    | process... | 931D7104FA |
| 8086:1903 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 26    | process... | D2B107774B |
| 8086:9d31 | 103c:832a | Intel      | Sunrise Point-LP Thermal ... | 26    | intel_p... | 931D7104FA |
| 8086:0a03 | 1043:16cd | Intel      | Haswell-ULT Thermal Subsy... | 25    | process... | EC78CDF03D |
| 8086:3b32 | 10cf:1526 | Intel      | 5 Series/3400 Series Chip... | 25    | intel_ips  | 95D76D0DE1 |
| 8086:1903 | 1028:087c | Intel      | Xeon E3-1200 v5/E3-1500 v... | 24    | process... | 18DC19F3EC |
| 8086:31b4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 24    | intel_lpss | DAEDE56DC8 |
| 8086:31b6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 24    | intel_lpss | DAEDE56DC8 |
| 8086:31b8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 24    | intel_lpss | DAEDE56DC8 |
| 8086:31ba | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 24    | intel_lpss | DAEDE56DC8 |
| 8086:3b32 | 144d:c581 | Intel      | 5 Series/3400 Series Chip... | 24    | intel_ips  | D9ECE67AC1 |
| 8086:9d31 | 8086:9d31 | Intel      | Sunrise Point-LP Thermal ... | 24    | intel_p... | A43311F999 |
| 8086:a379 | 1025:1264 | Intel      | Cannon Lake PCH Thermal C... | 24    | intel_p... | AF51F8907E |
| 8086:a379 | 1028:087c | Intel      | Cannon Lake PCH Thermal C... | 24    | intel_p... | 18DC19F3EC |
| 8086:1603 | 1043:10d0 | Intel      | Broadwell-U Processor The... | 23    | process... | CF2D08BE47 |
| 8086:22dc | 1043:10c0 | Intel      | Atom/Celeron/Pentium Proc... | 23    | process... | FB8F7369FA |
| 8086:3b32 | 103c:7008 | Intel      | 5 Series/3400 Series Chip... | 23    | intel_ips  | 4663DEB0DD |
| 8086:5a8c | 1043:1de0 | Intel      | Dynamic Platform and Ther... | 23    | proc_th... | 6391F5ED0E |
| 8086:5ab4 | 1043:1de0 | Intel      | Celeron N3350/Pentium N42... | 23    | intel_lpss | 6391F5ED0E |
| 8086:9ca4 | 1043:10d0 | Intel      | Wildcat Point-LP Thermal ... | 23    | intel_p... | CF2D08BE47 |
| 8086:9d31 | 103c:8079 | Intel      | Sunrise Point-LP Thermal ... | 23    | intel_p... | BCF0EBFEDD |
| 8086:9d60 | 103c:8079 | Intel      | Sunrise Point-LP Serial I... | 23    | intel_l... | BCF0EBFEDD |
| 8086:1903 | 1043:1a00 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 22    | proc_th... | 8C29A78852 |
| 8086:31be | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 22    | intel_l... | 7E86F1B5E7 |
| 8086:31c4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 22    | intel_l... | 7E86F1B5E7 |
| 8086:31c6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 22    | intel_l... | 7E86F1B5E7 |
| 8086:31ee | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 22    | intel_l... | 7E86F1B5E7 |
| 8086:9ca4 | 17aa:5034 | Intel      | Wildcat Point-LP Thermal ... | 22    | intel_p... | 71DE9234CB |
| 8086:9d27 | 1043:1a00 | Intel      | Sunrise Point-LP Serial I... | 22    | intel_lpss | 8C29A78852 |
| 8086:9d29 | 1043:1a00 | Intel      | Sunrise Point-LP Serial I... | 22    | intel_lpss | 8C29A78852 |
| 8086:9d31 | 1043:1a00 | Intel      | Sunrise Point-LP Thermal ... | 22    | intel_p... | 8C29A78852 |
| 8086:9d60 | 1043:1a00 | Intel      | Sunrise Point-LP Serial I... | 22    | intel_lpss | 8C29A78852 |
| 8086:9d61 | 1043:1a00 | Intel      | Sunrise Point-LP Serial I... | 22    | intel_lpss | 8C29A78852 |
| 8086:9df9 | 8086:2074 | Intel      | Cannon Point-LP Thermal C... | 21    | intel_p... | B039AEFD9E |
| 8086:1603 | 1043:1a6d | Intel      | Broadwell-U Processor The... | 20    | process... | DF4413AF58 |
| 8086:318c | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | process... | 7E86F1B5E7 |
| 8086:31ac | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | intel_l... | 7E86F1B5E7 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:4385 | 1002:4385 | AMD        | SBx00 SMBus Controller       | 566   | i2c_pii... | AFDF4A3A9C |
| 8086:1c22 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 543   | i2c_i801   | 13AF031E5E |
| 8086:27da | 1043:8179 | Intel      | NM10/ICH7 Family SMBus Co... | 447   | i2c_i801   | B9B80DB558 |
| 8086:27da | 1458:5001 | Intel      | NM10/ICH7 Family SMBus Co... | 445   | i2c_i801   | ABA2A5E5E6 |
| 1002:4385 | 1043:8389 | AMD        | SBx00 SMBus Controller       | 406   | i2c_pii... | 3C504F06A2 |
| 1002:4385 |           | AMD        | SBx00 SMBus Controller       | 397   | i2c_pii... | E722D70419 |
| 8086:1e22 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 387   | i2c_i801   | 91535E2115 |
| 1002:4385 | 1458:4385 | AMD        | SBx00 SMBus Controller       | 369   | i2c_pii... | A056C6C7D5 |
| 8086:8c22 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 364   | i2c_i801   | 15E3126F2C |
| 8086:1c22 | 1458:5001 | Intel      | 6 Series/C200 Series Chip... | 328   | i2c_i801   | EF2DAAC6D3 |
| 8086:3a30 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) SM... | 311   | i2c_i801   | 6949452F0E |
| 8086:1e22 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 301   | i2c_i801   | 8CE0C08E9A |
| 8086:1e22 | 1458:5001 | Intel      | 7 Series/C216 Chipset Fam... | 285   | i2c_i801   | 5B67F6ED83 |
| 8086:27da | 1849:27da | Intel      | NM10/ICH7 Family SMBus Co... | 276   | i2c_i801   | 6FDB8DFE61 |
| 1002:4385 | 1849:4385 | AMD        | SBx00 SMBus Controller       | 249   | i2c_pii... | 704C328C67 |
| 8086:a123 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 238   | i2c_i801   | B8C562A7E5 |
| 8086:2930 | 1043:8277 | Intel      | 82801I (ICH9 Family) SMBu... | 236   | i2c_i801   | 5EE0F1DB4C |
| 8086:8c22 | 1458:5001 | Intel      | 8 Series/C220 Series Chip... | 228   | i2c_i801   | 502C5D4B04 |
| 10de:03eb | 1849:03eb | Nvidia     | MCP61 SMBus                  | 223   | i2c_nfo... | EC1F6C8A0B |
| 8086:1c22 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 187   | i2c_i801   | 89EF922929 |
| 1022:780b | 1022:780b | AMD        | FCH SMBus Controller         | 181   | i2c_piix4  | 0CABEB6C95 |
| 1022:790b | 1043:8747 | AMD        | FCH SMBus Controller         | 178   | i2c_piix4  | 4ED3A4A663 |
| 1022:790b | 1458:5001 | AMD        | FCH SMBus Controller         | 168   | i2c_piix4  | 564EB1FFE4 |
| 8086:3a30 | 1458:5001 | Intel      | 82801JI (ICH10 Family) SM... | 162   | i2c_i801   | 13ACEC4985 |
| 8086:3b30 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 142   | i2c_i801   | E40B76E473 |
| 8086:a123 | 1458:5001 | Intel      | 100 Series/C230 Series Ch... | 138   | i2c_i801   | 4015843475 |
| 8086:1c22 | 1849:1c22 | Intel      | 6 Series/C200 Series Chip... | 135   | i2c_i801   | 2A41C5495D |
| 8086:27da | 1043:83ad | Intel      | NM10/ICH7 Family SMBus Co... | 134   | i2c_i801   | A6B1293F94 |
| 1022:780b | 1849:780b | AMD        | FCH SMBus Controller         | 132   | i2c_piix4  | 8230399CC0 |
| 8086:2930 | 1458:5001 | Intel      | 82801I (ICH9 Family) SMBu... | 120   | i2c_i801   | D87E2ED1BC |
| 10de:03eb | 1458:0c11 | Nvidia     | MCP61 SMBus                  | 118   | i2c_nfo... | 53DB8982F5 |
| 8086:9c22 | 17aa:3978 | Intel      | 8 Series SMBus Controller    | 114   | i2c_i801   | 972580DCF6 |
| 8086:8c22 | 1849:8c22 | Intel      | 8 Series/C220 Series Chip... | 113   | i2c_i801   | 40DEE920A9 |
| 8086:8ca2 | 1043:8534 | Intel      | 9 Series Chipset Family S... | 106   | i2c_i801   | 1D2014DD53 |
| 8086:3b30 | 17aa:2167 | Intel      | 5 Series/3400 Series Chip... | 105   | i2c_i801   | 9A495F134B |
| 1022:790b | 1849:790b | AMD        | FCH SMBus Controller         | 102   | i2c_piix4  | 5E8A739106 |
| 8086:3b30 | 1458:5001 | Intel      | 5 Series/3400 Series Chip... | 98    | i2c_i801   | E60C730AE2 |
| 8086:2930 | 17aa:20f9 | Intel      | 82801I (ICH9 Family) SMBu... | 93    | i2c_i801   | 1A90AC4588 |
| 8086:a2a3 | 1458:5001 | Intel      | 200 Series/Z370 Chipset F... | 92    | i2c_i801   | 8F2ECB882C |
| 8086:1c22 | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 89    | i2c_i801   | B7B1C7DF29 |
| 8086:1e22 | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 88    | i2c_i801   | 7857E6A77B |
| 8086:a2a3 | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 88    | i2c_i801   | 345BBA3C1F |
| 8086:1e22 | 1849:1e22 | Intel      | 7 Series/C216 Chipset Fam... | 86    | i2c_i801   | E1466EB2EC |
| 8086:8ca2 | 1458:5001 | Intel      | 9 Series Chipset Family S... | 85    | i2c_i801   | 984B3421C1 |
| 8086:2930 | 17aa:3a1d | Intel      | 82801I (ICH9 Family) SMBu... | 84    | i2c_i801   | 5986AA0AAC |
| 8086:3b30 | 17aa:38bf | Intel      | 5 Series/3400 Series Chip... | 84    | i2c_i801   | 15789D122D |
| 8086:8c22 | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 84    | i2c_i801   | FBE43FC861 |
| 10de:03eb | 1043:8234 | Nvidia     | MCP61 SMBus                  | 82    | i2c_nfo... | F3B22A675A |
| 8086:8c22 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 81    | i2c_i801   | F21C5B69B8 |
| 8086:1c22 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 80    | i2c_i801   | 25D909CC38 |
| 10de:03eb | 1043:83a4 | Nvidia     | MCP61 SMBus                  | 77    | i2c_nfo... | A6BD4DA213 |
| 8086:1e22 | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 75    | i2c_i801   | 1C3C62EC29 |
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 75    | i2c_i801   | 97BCBB884E |
| 8086:1e22 | 1043:124d | Intel      | 7 Series/C216 Chipset Fam... | 71    | i2c_i801   | 179397B4EA |
| 8086:283e | 1025:011f | Intel      | 82801H (ICH8 Family) SMBu... | 71    | i2c_i801   | BA9EFF4F3B |
| 8086:1e22 | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 69    | i2c_i801   | 9084C70732 |
| 8086:283e | 1043:81ec | Intel      | 82801H (ICH8 Family) SMBu... | 69    | i2c_i801   | 49BC4A3291 |
| 1002:4385 | 1043:82ef | AMD        | SBx00 SMBus Controller       | 68    | i2c_pii... | 96FD3589B3 |
| 8086:1e22 | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 68    | i2c_i801   | EFE09AFB77 |
| 8086:1c22 | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 67    | i2c_i801   | 47A635ACC1 |
| 1022:780b | 1043:85ca | AMD        | FCH SMBus Controller         | 64    | i2c_piix4  | 8F93BF715A |
| 8086:3b30 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 64    | i2c_i801   | 53ECD14649 |
| 1022:780b | 17aa:3801 | AMD        | FCH SMBus Controller         | 63    | i2c_piix4  | 363B08984A |
| 10de:0052 | 1043:815a | Nvidia     | CK804 SMBus                  | 62    | i2c_nfo... | FD8F010178 |
| 8086:1e22 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 62    | i2c_i801   | 75E8A3936D |
| 1022:780b | 1462:7721 | AMD        | FCH SMBus Controller         | 60    | i2c_piix4  | 743F3FF81C |
| 8086:27da | 1462:7529 | Intel      | NM10/ICH7 Family SMBus Co... | 60    | i2c_i801   | 3DCC4EE3D0 |
| 1002:4385 | 1462:7693 | AMD        | SBx00 SMBus Controller       | 59    | i2c_pii... | 9650DD9DCE |
| 8086:0f12 | 17aa:3905 | Intel      | Atom Processor E3800 Seri... | 59    | i2c_i801   | F2797B8B83 |
| 1022:790b | 1043:876b | AMD        | FCH SMBus Controller         | 57    | i2c_piix4  | DE065F2CFC |
| 8086:1c22 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 56    | i2c_i801   | 2B202B204B |
| 8086:27da | 1462:7592 | Intel      | NM10/ICH7 Family SMBus Co... | 56    | i2c_i801   | E5A422358F |
| 8086:3b30 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 56    | i2c_i801   | 90D3759348 |
| 8086:283e | 17aa:20a9 | Intel      | 82801H (ICH8 Family) SMBu... | 55    | i2c_i801   | FB1CD7BF88 |
| 8086:a323 | 1458:5001 | Intel      | Cannon Lake PCH SMBus Con... | 55    | i2c_i801   | E097415087 |
| 8086:27da | 1025:0349 | Intel      | NM10/ICH7 Family SMBus Co... | 54    | i2c_i801   | A911172500 |
| 8086:3b30 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 53    | i2c_i801   | 088FFC2823 |
| 8086:a123 | 1849:a123 | Intel      | 100 Series/C230 Series Ch... | 53    | i2c_i801   | 0E4F08FCA3 |
| 8086:a323 | 1043:8694 | Intel      | Cannon Lake PCH SMBus Con... | 53    | i2c_i801   | 0B771C098E |
| 8086:1c22 | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 52    | i2c_i801   | 4DB132BB33 |
| 8086:27da | 8086:27da | Intel      | NM10/ICH7 Family SMBus Co... | 51    | i2c_i801   | ED8C30E65A |
| 8086:1e22 | 17aa:5011 | Intel      | 7 Series/C216 Chipset Fam... | 50    | i2c_i801   | 82A9861AFD |
| 8086:1c22 | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 49    | i2c_i801   | 0BF9EE57AF |
| 8086:1c22 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 48    | i2c_i801   | F3FBF8BC70 |
| 8086:1e22 | 1043:14c7 | Intel      | 7 Series/C216 Chipset Fam... | 48    | i2c_i801   | 12F5A59D53 |
| 1022:790b | 103c:8330 | AMD        | FCH SMBus Controller         | 47    | i2c_piix4  | E26638D750 |
| 1022:790b | 1849:ffff | AMD        | FCH SMBus Controller         | 47    | i2c_pii... | 50C613C8D6 |
| 8086:1c22 | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 47    | i2c_i801   | DF459BC2B0 |
| 10de:03eb | 1462:7309 | Nvidia     | MCP61 SMBus                  | 46    | i2c_nfo... | 93E77F9DC3 |
| 10de:0aa2 | 10de:cb79 | Nvidia     | MCP79 SMBus                  | 46    | i2c_nfo... | 441575D073 |
| 8086:1c22 | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 46    | i2c_i801   | 7FD884E502 |
| 8086:3b30 | 1849:3b30 | Intel      | 5 Series/3400 Series Chip... | 46    | i2c_i801   | F0971CD52C |
| 8086:1d22 | 1043:84ef | Intel      | C600/X79 series chipset S... | 44    | i2c_i801   | 39F22D868E |
| 8086:1e22 | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 44    | i2c_i801   | B162D0FD81 |
| 1022:780b | 144d:c0da | AMD        | FCH SMBus Controller         | 43    | i2c_pii... | 047093E08D |
| 8086:9c22 | 1025:0866 | Intel      | 8 Series SMBus Controller    | 43    | i2c_i801   | 3FD761163B |
| 1022:780b | 1043:8527 | AMD        | FCH SMBus Controller         | 42    | i2c_piix4  | 958F78D7D3 |
| 8086:1e22 | 17aa:21f6 | Intel      | 7 Series/C216 Chipset Fam... | 42    | i2c_i801   | 1949413DC7 |
| 8086:1c22 | 144d:c0b6 | Intel      | 6 Series/C200 Series Chip... | 41    | i2c_i801   | 5118CD27DD |
| 8086:1c22 | 8086:1c22 | Intel      | 6 Series/C200 Series Chip... | 41    | i2c_i801   | F89781F320 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27d8 | 1458:a002 | Intel      | NM10/ICH7 Family High Def... | 375   | snd_hda... | ABA2A5E5E6 |
| 8086:0c0c | 8086:2010 | Intel      | Xeon E3-1200 v3/4th Gen C... | 359   | snd_hda... | 75C292C941 |
| 1002:4383 | 1458:a002 | AMD        | SBx00 Azalia (Intel HDA)     | 301   | snd_hda... | EE209BFCD3 |
| 8086:1e20 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 301   | snd_hda... | 8CE0C08E9A |
| 8086:1c20 | 1458:a002 | Intel      | 6 Series/C200 Series Chip... | 268   | snd_hda... | EF2DAAC6D3 |
| 8086:8c20 | 1043:8576 | Intel      | 8 Series/C220 Series Chip... | 268   | snd_hda... | 15E3126F2C |
| 1002:4383 | 1043:8445 | AMD        | SBx00 Azalia (Intel HDA)     | 236   | snd_hda... | 3C504F06A2 |
| 8086:8c20 | 1458:a002 | Intel      | 8 Series/C220 Series Chip... | 208   | snd_hda... | 502C5D4B04 |
| 10de:0bea |           | Nvidia     | GF108 High Definition Aud... | 206   | snd_hda... | 843A450979 |
| 13f6:0111 | 13f6:0111 | C-Media... | CMI8738/CMI8768 PCI Audio    | 203   | snd_cmipci | 53D2EF8D02 |
| 8086:1e20 | 1458:a002 | Intel      | 7 Series/C216 Chipset Fam... | 188   | snd_hda... | 5B67F6ED83 |
| 8086:1c20 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 187   | snd_hda... | 89EF922929 |
| 8086:1c20 | 1043:8445 | Intel      | 6 Series/C200 Series Chip... | 184   | snd_hda... | 13AF031E5E |
| 1002:aab0 | 174b:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 176   | snd_hda... | 21A4325DBF |
| 10de:03f0 | 1849:0397 | Nvidia     | MCP61 High Definition Audio  | 174   | snd_hda... | EC1F6C8A0B |
| 1002:aab0 | 1043:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 171   | snd_hda... | 2C202D97E7 |
| 8086:293e | 1043:829f | Intel      | 82801I (ICH9 Family) HD A... | 163   | snd_hda... | 5EE0F1DB4C |
| 8086:1e20 | 1043:8445 | Intel      | 7 Series/C216 Chipset Fam... | 162   | snd_hda... | 535FBF3562 |
| 8086:a170 | 1043:86c7 | Intel      | 100 Series/C230 Series Ch... | 160   | snd_hda... | 6388AF2414 |
| 1002:15de | 1002:15de | AMD        | Raven/Raven2/Fenghuang HD... | 154   | snd_hda... | 9809687258 |
| 8086:1c20 | 1043:8415 | Intel      | 6 Series/C200 Series Chip... | 151   | snd_hda... | F66245AEA5 |
| 8086:27d8 | 1849:3662 | Intel      | NM10/ICH7 Family High Def... | 149   | snd_hda... | C0D7396586 |
| 1002:4383 | 1043:836c | AMD        | SBx00 Azalia (Intel HDA)     | 141   | snd_hda... | 2902DCE4BA |
| 1022:780d | 1458:a002 | AMD        | FCH Azalia Controller        | 134   | snd_hda... | EAD3059AA0 |
| 10de:0be3 |           | Nvidia     | High Definition Audio Con... | 126   | snd_hda... | 11FC0E438A |
| 8086:0c0c | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 122   | snd_hda... | 1D2014DD53 |
| 1022:780d | 1043:8576 | AMD        | FCH Azalia Controller        | 116   | snd_hda... | 22A0854387 |
| 8086:a170 | 1458:a182 | Intel      | 100 Series/C230 Series Ch... | 116   | snd_hda... | 4015843475 |
| 8086:0a0c | 17aa:3978 | Intel      | Haswell-ULT HD Audio Cont... | 114   | snd_hda... | 972580DCF6 |
| 8086:9c20 | 17aa:3978 | Intel      | 8 Series HD Audio Controller | 114   | snd_hda... | 972580DCF6 |
| 10de:03f0 | 1458:a002 | Nvidia     | MCP61 High Definition Audio  | 113   | snd_hda... | 53DB8982F5 |
| 8086:3a3e | 1458:a002 | Intel      | 82801JI (ICH10 Family) HD... | 112   | snd_hda... | 6785C105CC |
| 8086:27d8 | 1043:8290 | Intel      | NM10/ICH7 Family High Def... | 108   | snd_hda... | E643B8ED58 |
| 8086:3b56 | 17aa:215e | Intel      | 5 Series/3400 Series Chip... | 102   | snd_hda... | 9A495F134B |
| 8086:293e | 17aa:20f2 | Intel      | 82801I (ICH9 Family) HD A... | 100   | snd_hda... | 1A90AC4588 |
| 8086:3a3e | 1043:82fe | Intel      | 82801JI (ICH10 Family) HD... | 100   | snd_hda... | A5A715C21F |
| 1002:4383 | 1458:a102 | AMD        | SBx00 Azalia (Intel HDA)     | 99    | snd_hda... | E722D70419 |
| 1002:aab0 | 1458:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 98    | snd_hda... | E1466EB2EC |
| 1002:4383 | 1043:8444 | AMD        | SBx00 Azalia (Intel HDA)     | 96    | snd_hda... | 26465880BF |
| 8086:293e | 1458:a002 | Intel      | 82801I (ICH9 Family) HD A... | 96    | snd_hda... | E818A123C5 |
| 1002:aa68 | 1043:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 92    | snd_hda... | 088FFC2823 |
| 10de:0bee |           | Nvidia     | GF116 High Definition Aud... | 91    | snd_hda... | A644A3A3AD |
| 10de:0e0f | 1462:8c93 | Nvidia     | GK208 HDMI/DP Audio Contr... | 90    | snd_hda... | C51735EE45 |
| 1002:4383 | 1458:a182 | AMD        | SBx00 Azalia (Intel HDA)     | 89    | snd_hda... | 98A03A61F1 |
| 1002:aab0 | 1787:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 89    | snd_hda... | BA9BCF582F |
| 8086:1e20 | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 88    | snd_hda... | 7857E6A77B |
| 8086:293e | 17aa:3a0d | Intel      | 82801I (ICH9 Family) HD A... | 85    | snd_hda... | 5986AA0AAC |
| 8086:27d8 | 1849:0397 | Intel      | NM10/ICH7 Family High Def... | 83    | snd_hda... | 6FDB8DFE61 |
| 8086:3b56 | 1458:a002 | Intel      | 5 Series/3400 Series Chip... | 83    | snd_hda... | 7E353F1BDA |
| 8086:3b56 | 17aa:38af | Intel      | 5 Series/3400 Series Chip... | 83    | snd_hda... | 15789D122D |
| 8086:1c20 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 80    | snd_hda... | 25D909CC38 |
| 8086:8c20 | 1462:d817 | Intel      | 8 Series/C220 Series Chip... | 79    | snd_hda... | FBE43FC861 |
| 1002:4383 | 1849:7892 | AMD        | SBx00 Azalia (Intel HDA)     | 77    | snd_hda... | A17808DA56 |
| 1002:aa98 | 174b:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 77    | snd_hda... | 522AE798B9 |
| 1002:aa38 | 174b:aa38 | AMD        | RV710/730 HDMI Audio [Rad... | 76    | snd_hda... | A056C6C7D5 |
| 10de:0be4 |           | Nvidia     | High Definition Audio Con... | 76    | snd_hda... | 7F477DA95D |
| 8086:1e20 | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 75    | snd_hda... | 1C3C62EC29 |
| 1002:aa90 | 174b:aa90 | AMD        | Turks HDMI Audio [Radeon ... | 74    | snd_hda... | B656825800 |
| 8086:a2f0 | 1458:a182 | Intel      | 200 Series PCH HD Audio      | 74    | snd_hda... | 8F2ECB882C |
| 1002:aaf0 | 1da2:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 73    | snd_hda... | FA300CEB06 |
| 1002:aa98 | 1043:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 72    | snd_hda... | 2327D3DDB8 |
| 8086:284b | 1025:011f | Intel      | 82801H (ICH8 Family) HD A... | 71    | snd_hda... | BA9EFF4F3B |
| 1022:1457 | 1458:a182 | AMD        | Family 17h (Models 00h-0f... | 70    | snd_hda... | C188CE2FCE |
| 1002:aab0 | 1462:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 69    | snd_hda... | 704C328C67 |
| 1022:1457 | 1043:86c7 | AMD        | Family 17h (Models 00h-0f... | 69    | snd_hda... | 4ED3A4A663 |
| 8086:1e20 | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 69    | snd_hda... | 9084C70732 |
| 8086:1e20 | 1458:a014 | Intel      | 7 Series/C216 Chipset Fam... | 69    | snd_hda... | AD56492FB5 |
| 8086:1e20 | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 68    | snd_hda... | EFE09AFB77 |
| 8086:27d8 | 1043:8437 | Intel      | NM10/ICH7 Family High Def... | 68    | snd_hda... | DEAF7BC089 |
| 8086:284b | 1043:81ec | Intel      | 82801H (ICH8 Family) HD A... | 68    | snd_hda... | 49BC4A3291 |
| 8086:1c20 | 1043:1ac3 | Intel      | 6 Series/C200 Series Chip... | 67    | snd_hda... | 47A635ACC1 |
| 8086:27d8 | 1043:817f | Intel      | NM10/ICH7 Family High Def... | 66    | snd_hda... | FF854DCB6E |
| 1002:aa58 | 174b:aa58 | AMD        | Juniper HDMI Audio [Radeo... | 65    | snd_hda... | 6949452F0E |
| 1002:aa68 | 174b:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 65    | snd_hda... | F0615F7666 |
| 1022:780d | 1849:7662 | AMD        | FCH Azalia Controller        | 65    | snd_hda... | 8230399CC0 |
| 1102:0007 | 1102:100a | Creativ... | CA0106/CA0111 [SB Live!/A... | 65    | snd_ca0106 | 4795BF2A94 |
| 8086:3b56 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 64    | snd_hda... | 53ECD14649 |
| 1002:9840 | 17aa:3801 | AMD        | Kabini HDMI/DP Audio         | 63    | snd_hda... | 363B08984A |
| 1022:780d | 17aa:3801 | AMD        | FCH Azalia Controller        | 63    | snd_hda... | 363B08984A |
| 8086:27d8 | 1043:82ea | Intel      | NM10/ICH7 Family High Def... | 63    | snd_hda... | B9B80DB558 |
| 8086:0a0c | 8086:2010 | Intel      | Haswell-ULT HD Audio Cont... | 62    | snd_hda... | 64EDCECFF8 |
| 8086:1e20 | 1043:8415 | Intel      | 7 Series/C216 Chipset Fam... | 61    | snd_hda... | 91535E2115 |
| 8086:27d8 | 1043:83a1 | Intel      | NM10/ICH7 Family High Def... | 61    | snd_hda... | E64F670E53 |
| 8086:293e | 1043:8277 | Intel      | 82801I (ICH9 Family) HD A... | 61    | snd_hda... | 550E44C270 |
| 8086:8c20 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 61    | snd_hda... | F21C5B69B8 |
| 8086:8ca0 | 1458:a182 | Intel      | 9 Series Chipset Family H... | 61    | snd_hda... | 984B3421C1 |
| 8086:0c0c | 17aa:3978 | Intel      | Xeon E3-1200 v3/4th Gen C... | 60    | snd_hda... | 239616AC43 |
| 8086:27d8 | 1462:7529 | Intel      | NM10/ICH7 Family High Def... | 60    | snd_hda... | 3DCC4EE3D0 |
| 1022:780d | 1462:d721 | AMD        | FCH Azalia Controller        | 59    | snd_hda... | 743F3FF81C |
| 8086:0f04 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 59    | snd_hda... | F2797B8B83 |
| 1002:4383 | 1849:7662 | AMD        | SBx00 Azalia (Intel HDA)     | 58    | snd_hda... | 1581CB5806 |
| 1002:9902 | 1002:9902 | AMD        | Trinity HDMI Audio Contro... | 58    | snd_hda... | C77563A5FB |
| 1022:780d | 1458:a182 | AMD        | FCH Azalia Controller        | 58    | snd_hda... | 0CABEB6C95 |
| 8086:1e20 | 1043:118f | Intel      | 7 Series/C216 Chipset Fam... | 58    | snd_hda... | B2FB796FAB |
| 10de:0be2 |           | Nvidia     | GT216 HDMI Audio Controller  | 57    | snd_hda... | 56FDCBB995 |
| 1002:4383 | 1043:84fb | AMD        | SBx00 Azalia (Intel HDA)     | 56    | snd_hda... | B38E3E18FC |
| 1002:4383 | 1462:d693 | AMD        | SBx00 Azalia (Intel HDA)     | 56    | snd_hda... | B5C538F345 |
| 8086:3b56 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 56    | snd_hda... | 90D3759348 |
| 1102:0012 | 1102:0010 | Creativ... | Sound Core3D [Sound Blast... | 55    | snd_hda... | 13ACEC4985 |
| 8086:27d8 | 1462:7592 | Intel      | NM10/ICH7 Family High Def... | 55    | snd_hda... | E5A422358F |

### Storage (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 104c:803b | 1025:011f | Texas I... | PCIxx12 Flash Media Contr... | 71    | tifm_7xx1  | BA9EFF4F3B |
| 1217:8231 | 1028:0493 | O2 Micro   | O2Micro Integrated MS/MSP... | 39    |            | CA779DE74C |
| 1283:8211 | 1043:8138 | Integra... | ITE 8211F Single Channel ... | 27    | pata_it... | 84495E0FB8 |
| 104c:803b | 1179:ff00 | Texas I... | PCIxx12 Flash Media Contr... | 26    | tifm_7xx1  | CCB7CB26D3 |
| 1217:7130 | 1179:ff50 | O2 Micro   | Integrated MS/xD Controller  | 21    |            | 6108B0C47E |
| 1217:7130 | 1025:013c | O2 Micro   | Integrated MS/xD Controller  | 20    |            | A8E4D6D25F |
| 104c:803b | 1179:ff02 | Texas I... | PCIxx12 Flash Media Contr... | 17    | tifm_7xx1  | 3CE1664885 |
| 104c:803b | 1179:ff10 | Texas I... | PCIxx12 Flash Media Contr... | 16    | tifm_7xx1  | 5FDCE37F38 |
| 1217:8331 | 1028:0494 | O2 Micro   | O2 Flash Memory Card         | 16    |            | 4384225066 |
| 104c:803b | 1025:0107 | Texas I... | PCIxx12 Flash Media Contr... | 12    | tifm_7xx1  | 290DB67DA7 |
| 104c:803b | 1025:0110 | Texas I... | PCIxx12 Flash Media Contr... | 12    | tifm_7xx1  | D4A385C83A |
| 1217:8330 | 1028:04a3 | O2 Micro   | OZ600 MS/xD Controller       | 12    |            | D8BA5B1425 |
| 1217:8331 | 1028:049a | O2 Micro   | O2 Flash Memory Card         | 12    |            | 6FD4500E86 |
| 1217:7130 | 10cf:143d | O2 Micro   | Integrated MS/xD Controller  | 10    |            | 4A653FDD06 |
| 104c:803b | 104d:902d | Texas I... | PCIxx12 Flash Media Contr... | 9     | tifm_7xx1  | DE6F0F6D83 |
| 104c:803b | 104d:9015 | Texas I... | PCIxx12 Flash Media Contr... | 8     | tifm_7xx1  | B6F0BD6CA4 |
| 104c:803b | 1179:0001 | Texas I... | PCIxx12 Flash Media Contr... | 8     | tifm_7xx1  | 0C90DCED50 |
| 1217:8130 | 1028:02bc | O2 Micro   | Integrated MS/MSPRO/xD Co... | 8     |            | E1FF130D0A |
| 1217:8331 | 1028:049b | O2 Micro   | O2 Flash Memory Card         | 8     |            | 4673399116 |
| 1000:0058 | 1028:1f0e | LSI Log... | SAS1068E PCI-Express Fusi... | 7     | mptsas     | BCA2EBDBAF |
| 104c:803b | 104d:81e6 | Texas I... | PCIxx12 Flash Media Contr... | 7     | tifm_7xx1  | 047C3A9402 |
| 104c:803b | 104d:9005 | Texas I... | PCIxx12 Flash Media Contr... | 7     | tifm_7xx1  | 9B1280E7FC |
| 104c:803b | 1025:011c | Texas I... | PCIxx12 Flash Media Contr... | 6     | tifm_7xx1  | AD2D03638A |
| 104c:803b | 104d:9016 | Texas I... | PCIxx12 Flash Media Contr... | 6     | tifm_7xx1  | FF1CDF1811 |
| 1217:7130 | 10cf:14d6 | O2 Micro   | Integrated MS/xD Controller  | 6     |            | 751064E2A2 |
| 104c:8033 | 1179:ff05 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 5     | tifm_7xx1  | 8488B3D0B9 |
| 104c:803b | 103c:30aa | Texas I... | PCIxx12 Flash Media Contr... | 5     | tifm_7xx1  | 9C1BF7D811 |
| 104c:803b | 104d:8212 | Texas I... | PCIxx12 Flash Media Contr... | 5     | tifm_7xx1  | B389939EE8 |
| 1095:3132 | 1095:3132 | Silicon... | SiI 3132 Serial ATA Raid ... | 5     | sata_sil24 | A0F0B2CB3C |
| 1217:8130 | 1179:ff50 | O2 Micro   | Integrated MS/MSPRO/xD Co... | 5     |            | 60D901703E |
| 1217:8330 | 1028:04a4 | O2 Micro   | OZ600 MS/xD Controller       | 5     |            | 2A2FBFB933 |
| 104c:8033 | 1025:0066 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 4     | tifm_7xx1  | 50122B9E8E |
| 104c:8033 | 103c:0944 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 4     | tifm_7xx1  | A770CF025E |
| 104c:8033 | 1179:0001 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 4     | tifm_7xx1  | D5D7DAB02F |
| 104c:8033 | 17c0:3007 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 4     | tifm_7xx1  | EFDFFC9FB6 |
| 104c:803b | 1025:0130 | Texas I... | PCIxx12 Flash Media Contr... | 4     | tifm_7xx1  | 2165E8969A |
| 1217:7130 | 1025:012b | O2 Micro   | Integrated MS/xD Controller  | 4     |            | 21509117BA |
| 1217:7130 | 1028:0273 | O2 Micro   | Integrated MS/xD Controller  | 4     |            | C9D61D9E11 |
| 1283:8212 | 1043:813a | Integra... | IT8212 Dual channel ATA R... | 4     | pata_it... | 87F8B4B22A |
| 1283:8212 | 105b:0cc0 | Integra... | IT8212 Dual channel ATA R... | 4     | pata_it... | 6311678EE1 |
| 9005:8017 | 9005:0045 | Adaptec    | ASC-29320ALP U320            | 4     | aic79xx    | 5C3DF14DAD |
| 104c:8033 | 103c:3080 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 3     | tifm_7xx1  | 6802B34FDD |
| 104c:8033 | 103c:309d | Texas I... | PCIxx21/PCIxx11 Flash Med... | 3     | tifm_7xx1  | 837230178B |
| 104c:8033 | 103c:30a4 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 3     | tifm_7xx1  | CCEED80795 |
| 104c:803b | 1025:0094 | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | 72E2443AE3 |
| 104c:803b | 103c:309f | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | 5BE41E5F47 |
| 104c:803b | 103c:30ac | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | 3604EF7ED6 |
| 104c:803b | 104d:81ef | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | 8D7F285234 |
| 104c:803b | 104d:820f | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | C623DE88EE |
| 104c:803b | 104d:9008 | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | 639305E27C |
| 104c:ac8f | 104d:8190 | Texas I... | PCI7420/7620 SD/MS-Pro Co... | 3     | tifm_7xx1  | C3CFD62BCD |
| 1077:2432 | 1077:0138 | QLogic     | ISP2432-based 4Gb Fibre C... | 3     | qla2xxx    | FB66D16E30 |
| 10df:fe00 | 10df:fe00 | Emulex     | Zephyr-X LightPulse Fibre... | 3     | lpfc       | 6806624961 |
| 1217:7130 | 1028:026f | O2 Micro   | Integrated MS/xD Controller  | 3     |            | 20788C640E |
| 1217:7130 | 1462:3ff3 | O2 Micro   | Integrated MS/xD Controller  | 3     |            | A249DABAD8 |
| 1217:8231 | 1028:04a9 | O2 Micro   | O2Micro Integrated MS/MSP... | 3     |            | F3F87090B3 |
| 1283:8211 | 1283:8211 | Integra... | ITE 8211F Single Channel ... | 3     | pata_it... | BF5B58520E |
| 8086:1d6b | 1734:11b6 | Intel      | C602 chipset 4-Port SATA ... | 3     | isci       | 961A7ADB3E |
| 9004:7178 |           | Adaptec    | AIC-7870P/7871 [AHA-2940/... | 3     | aic7xxx    | 87BEA4712A |
| 1000:0001 |           | LSI Log... | 53c810                       | 2     | sym53c8xx  | C433E6081D |
| 1000:0030 | 103c:322a | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 2     | mptspi     | C156F0AB27 |
| 1000:0058 | 103c:3229 | LSI Log... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | D082929A57 |
| 1000:0070 | 1000:3010 | LSI Log... | SAS2004 PCI-Express Fusio... | 2     | mpt2sas    | 99E743CA9E |
| 104c:8033 | 103c:0934 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 2     | tifm_7xx1  | 16F00AAE37 |
| 104c:8033 | 103c:3085 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 2     | tifm_7xx1  | 215D2A28A4 |
| 104c:8033 | 103c:308b | Texas I... | PCIxx21/PCIxx11 Flash Med... | 2     | tifm_7xx1  | 7945895A4E |
| 104c:8033 | 1734:1092 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 2     | tifm_7xx1  | 4D0D913872 |
| 104c:803b | 1025:006c | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 1CE26C391A |
| 104c:803b | 1025:0096 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 070206A279 |
| 104c:803b | 1025:0102 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 5CBBF81362 |
| 104c:803b | 1028:02ef | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 089056D291 |
| 104c:803b | 103c:30a3 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | B38A821821 |
| 104c:803b | 103c:30b0 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 7FE3257344 |
| 104c:803b | 103c:30b1 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 25DD8AF3EE |
| 104c:803b | 1179:ff03 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 087C0E291D |
| 104c:803b | 1179:ff31 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 4697BD88EB |
| 104c:803b | 152d:0753 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | F57558EF8E |
| 104c:803b | 152d:0763 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | E07AB48C55 |
| 104c:803b | 1558:0661 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 2A6A5EFE01 |
| 104c:803b | 17aa:207c | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 97AECB0406 |
| 104c:803b | 17ff:0590 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 8B79E00851 |
| 105a:4d68 | 105a:4d68 | Promise... | PDC20268 [Ultra100 TX2]      | 2     | pata_pd... | FE1A587527 |
| 1077:2532 | 1077:015d | QLogic     | ISP2532-based 8Gb Fibre C... | 2     | qla2xxx    | 5EB4DFC951 |
| 1095:3114 | 1043:8136 | Silicon... | SiI 3114 [SATALink/SATARa... | 2     | sata_sil   | 87F8B4B22A |
| 1095:3531 | 1095:3531 | Silicon... | SiI 3531 [SATALink/SATARa... | 2     | sata_sil24 | 7386C9D836 |
| 1217:7130 | 1025:011a | O2 Micro   | Integrated MS/xD Controller  | 2     |            | 69380B60FC |
| 1217:7130 | 1025:0124 | O2 Micro   | Integrated MS/xD Controller  | 2     |            | 5AAFE28787 |
| 1217:7130 | 1028:0275 | O2 Micro   | Integrated MS/xD Controller  | 2     |            | B0314C0713 |
| 1217:7130 | 1462:3fc1 | O2 Micro   | Integrated MS/xD Controller  | 2     |            | 278EF4A255 |
| 1217:7130 | 1734:10c7 | O2 Micro   | Integrated MS/xD Controller  | 2     |            | 6E3970FC39 |
| 1de1:0391 | 1de1:0391 | Tekram ... | TRM-S1040 [DC-315 / DC-39... | 2     | dc395x     | BBFFB3F1D1 |
| 8086:1d6b | 1043:84ef | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 996F55BB36 |
| 9004:8178 |           | Adaptec    | AIC-7870P/7881U [AHA-2940... | 2     | aic7xxx    | 2BAC98B043 |
| 1000:0030 | 1014:026c | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 46973B5B05 |
| 1000:0030 | 1014:1000 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 659D759E6D |
| 1000:0030 | 1028:016e | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 76EF1C8CA9 |
| 1000:0030 | 103c:1500 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 0F22A261A8 |
| 1000:0030 | 103c:3108 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | A2995F5723 |
| 1000:0050 | 103c:3015 | Broadco... | SAS1064 PCI-X Fusion-MPT SAS | 1     | mptsas     | AA051D69D4 |
| 1000:0056 | 1014:03bb | LSI Log... | SAS1064ET PCI-Express Fus... | 1     | mptsas     | E53A957D3F |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:4390 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 364   | ahci       | E722D70419 |
| 8086:8c02 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 352   | ahci       | 15E3126F2C |
| 1002:4390 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 331   | ahci       | 3C504F06A2 |
| 1002:4391 | 1043:84dd | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 321   | ahci       | AFDF4A3A9C |
| 8086:1c02 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 289   | ahci       | 13AF031E5E |
| 8086:1e02 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 281   | ahci       | 91535E2115 |
| 1002:4391 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 274   | ahci       | 0D6CA866B0 |
| 8086:1e03 | 17aa:3977 | Intel      | 7 Series Chipset Family 6... | 274   | ahci       | 8CE0C08E9A |
| 1b21:0612 | 1043:84b7 | ASMedia... | ASM1062 Serial ATA Contro... | 236   | ahci       | AFDF4A3A9C |
| 1022:43c8 | 1b21:1062 | AMD        | 400 Series Chipset SATA C... | 235   | ahci       | 5BCFE2F1CE |
| 8086:a102 | 1043:8694 | Intel      | Q170/Q150/B150/H170/H110/... | 233   | ahci       | B8C562A7E5 |
| 8086:8c02 | 1458:b005 | Intel      | 8 Series/C220 Series Chip... | 210   | ahci       | 502C5D4B04 |
| 1022:7901 | 1043:8747 | AMD        | FCH SATA Controller [AHCI... | 178   | ahci       | 4ED3A4A663 |
| 1022:43b7 | 1b21:1062 | AMD        | 300 Series Chipset SATA C... | 172   | ahci       | 4ED3A4A663 |
| 8086:27c1 | 1043:83ad | Intel      | NM10/ICH7 Family SATA Con... | 171   | ahci       | A6B1293F94 |
| 8086:1c03 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 170   | ahci       | 89EF922929 |
| 1022:7901 | 1458:b002 | AMD        | FCH SATA Controller [AHCI... | 153   | ahci       | 564EB1FFE4 |
| 8086:1e02 | 1458:b005 | Intel      | 7 Series/C210 Series Chip... | 145   | ahci       | 5B67F6ED83 |
| 1b21:0612 | 1849:0612 | ASMedia... | ASM1062 Serial ATA Contro... | 137   | ahci       | BAFB10A069 |
| 8086:a102 | 1458:b005 | Intel      | Q170/Q150/B150/H170/H110/... | 137   | ahci       | 4015843475 |
| 1002:4391 | 1849:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 135   | ahci       | 704C328C67 |
| 1022:7801 | 1458:b002 | AMD        | FCH SATA Controller [AHCI... | 124   | ahci       | 646D568712 |
| 8086:1c02 | 1458:b005 | Intel      | 6 Series/C200 Series Chip... | 122   | ahci       | 6F8237E870 |
| 1002:4390 | 1849:4390 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 118   | ahci       | A17808DA56 |
| 8086:9c03 | 17aa:3978 | Intel      | 8 Series SATA Controller ... | 113   | ahci       | 972580DCF6 |
| 1022:43b5 | 1b21:1062 | AMD        | X370 Series Chipset SATA ... | 105   | ahci       | 2E60313B01 |
| 8086:8c02 | 1849:8c02 | Intel      | 8 Series/C220 Series Chip... | 104   | ahci       | 40DEE920A9 |
| 1022:7801 | 1849:7801 | AMD        | FCH SATA Controller [AHCI... | 102   | ahci       | 8230399CC0 |
| 197b:2362 | 1043:8460 | JMicron... | JMB362 SATA Controller       | 102   | ahci       | BD3C6A762C |
| 8086:3a22 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) SA... | 102   | ahci       | A30E689A9E |
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 100   | ahci       | 50C613C8D6 |
| 1022:7901 | 1849:7901 | AMD        | FCH SATA Controller [AHCI... | 100   | ahci       | 5E8A739106 |
| 8086:8c82 | 1043:8534 | Intel      | 9 Series Chipset Family S... | 99    | ahci       | 1D2014DD53 |
| 1022:7800 | 1458:b002 | AMD        | FCH SATA Controller [IDE ... | 98    | ahci       | 0CABEB6C95 |
| 1b4b:9172 | 1458:b000 | Marvell... | 88SE9172 SATA 6Gb/s Contr... | 92    | ahci       | 0D6CA866B0 |
| 1022:43b8 | 1b21:1062 | AMD        | FCH SATA Controller D        | 87    | ahci       | 50C613C8D6 |
| 8086:2929 | 17aa:20f8 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 87    | ahci       | 1A90AC4588 |
| 8086:1c03 | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 85    | ahci       | B7B1C7DF29 |
| 8086:1e03 | 1025:0649 | Intel      | 7 Series Chipset Family 6... | 85    | ahci       | 7857E6A77B |
| 8086:a282 | 1458:b005 | Intel      | 200 Series PCH SATA contr... | 85    | ahci       | 8F2ECB882C |
| 8086:3b2f | 17aa:2168 | Intel      | 5 Series/3400 Series Chip... | 84    | ahci       | 9A495F134B |
| 8086:3b29 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 83    | ahci       | 088FFC2823 |
| 8086:1e02 | 1849:1e02 | Intel      | 7 Series/C210 Series Chip... | 82    | ahci       | E1466EB2EC |
| 8086:a282 | 1043:8694 | Intel      | 200 Series PCH SATA contr... | 80    | ahci       | 345BBA3C1F |
| 1002:4391 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 79    | ahci       | 2902DCE4BA |
| 8086:8c82 | 1458:b005 | Intel      | 9 Series Chipset Family S... | 79    | ahci       | 984B3421C1 |
| 8086:3b29 | 17aa:38c1 | Intel      | 5 Series/3400 Series Chip... | 78    | ahci       | 15789D122D |
| 8086:8c02 | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 78    | ahci       | FBE43FC861 |
| 8086:1c03 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 77    | ahci       | 25D909CC38 |
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 75    | ahci       | 97BCBB884E |
| 8086:1c02 | 1849:1c02 | Intel      | 6 Series/C200 Series Chip... | 74    | ahci       | 2A41C5495D |
| 8086:1e03 | 17aa:5002 | Intel      | 7 Series Chipset Family 6... | 73    | ahci       | 1C3C62EC29 |
| 8086:2929 | 17aa:3a1a | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 73    | ahci       | 5986AA0AAC |
| 1002:4391 | 1002:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 68    | ahci       | 601775E217 |
| 8086:1c03 | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 67    | ahci       | 47A635ACC1 |
| 8086:1e03 | 1025:0647 | Intel      | 7 Series Chipset Family 6... | 66    | ahci       | 9084C70732 |
| 8086:1e03 | 1043:124d | Intel      | 7 Series Chipset Family 6... | 66    | ahci       | 179397B4EA |
| 1002:4390 | 1002:4390 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 64    | ahci       | 9A42A921E7 |
| 1b21:0612 | 1b21:1060 | ASMedia... | ASM1062 Serial ATA Contro... | 63    | ahci       | B5BA9A13DC |
| 8086:1e03 | 1025:064b | Intel      | 7 Series Chipset Family 6... | 63    | ahci       | EFE09AFB77 |
| 1022:7801 | 1043:85ca | AMD        | FCH SATA Controller [AHCI... | 62    | ahci       | 8F93BF715A |
| 1002:4390 | 1043:82ef | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 61    | ahci       | 96FD3589B3 |
| 1022:7801 | 1462:7721 | AMD        | FCH SATA Controller [AHCI... | 60    | ahci       | 743F3FF81C |
| 1022:7801 | 17aa:3801 | AMD        | FCH SATA Controller [AHCI... | 60    | ahci       | 363B08984A |
| 1b21:0612 | 1043:858d | ASMedia... | ASM1062 Serial ATA Contro... | 60    | ahci       | 1D2014DD53 |
| 8086:1e03 | 8086:7270 | Intel      | 7 Series Chipset Family 6... | 59    | ahci       | 75E8A3936D |
| 1022:7901 | 1043:876b | AMD        | FCH SATA Controller [AHCI... | 57    | ahci       | DE065F2CFC |
| 8086:3b29 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 57    | ahci       | 53ECD14649 |
| 8086:3b29 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 56    | ahci       | 90D3759348 |
| 8086:8c03 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 56    | ahci       | 239616AC43 |
| 8086:0f23 | 17aa:3905 | Intel      | Atom Processor E3800 Seri... | 55    | ahci       | F2797B8B83 |
| 1022:43c8 | 1849:43c8 | AMD        | 400 Series Chipset SATA C... | 53    | ahci       | 0450F1FE8A |
| 8086:a102 | 1849:a102 | Intel      | Q170/Q150/B150/H170/H110/... | 53    | ahci       | 0E4F08FCA3 |
| 8086:a352 | 1458:b005 | Intel      | Cannon Lake PCH SATA AHCI... | 52    | ahci       | E097415087 |
| 8086:1c03 | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 50    | ahci       | 4DB132BB33 |
| 8086:3a22 | 1458:b005 | Intel      | 82801JI (ICH10 Family) SA... | 50    | ahci       | DE978F9E41 |
| 1b4b:9130 | 1043:8438 | Marvell... | 88SE9128 PCIe SATA 6 Gb/s... | 49    | ahci       | 7A8CCFD558 |
| 8086:1c03 | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 49    | ahci       | 0BF9EE57AF |
| 1022:7904 | 103c:8330 | AMD        | FCH SATA Controller [AHCI... | 47    | ahci       | E26638D750 |
| 8086:27c1 | 1025:0349 | Intel      | NM10/ICH7 Family SATA Con... | 47    | ahci       | A911172500 |
| 8086:1c03 | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 46    | ahci       | DF459BC2B0 |
| 8086:1c03 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 46    | ahci       | F3FBF8BC70 |
| 8086:3b22 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 46    | ahci       | E40B76E473 |
| 8086:a352 | 1043:8694 | Intel      | Cannon Lake PCH SATA AHCI... | 46    | ahci       | 0B771C098E |
| 1b4b:9172 | 1043:8477 | Marvell... | 88SE9172 SATA 6Gb/s Contr... | 44    | ahci       | BD3C6A762C |
| 8086:1e03 | 1043:14c7 | Intel      | 7 Series Chipset Family 6... | 44    | ahci       | 12F5A59D53 |
| 8086:1e03 | 17aa:5011 | Intel      | 7 Series Chipset Family 6... | 44    | ahci       | 92C25DEB31 |
| 1022:7804 | 144d:c0da | AMD        | FCH SATA Controller [AHCI... | 43    | ahci       | 047093E08D |
| 8086:9c03 | 1025:0866 | Intel      | 8 Series SATA Controller ... | 43    | ahci       | 3FD761163B |
| 8086:2829 | 17aa:20a7 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 42    | ahci       | FB1CD7BF88 |
| 1002:4391 | 1043:1117 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 41    | ahci       | E9F680E72A |
| 1022:7801 | 1043:8527 | AMD        | FCH SATA Controller [AHCI... | 41    | ahci       | 958F78D7D3 |
| 1002:4390 | 1043:8443 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 40    | ahci       | FF37EF634B |
| 8086:1c03 | 144d:c0b6 | Intel      | 6 Series/C200 Series Chip... | 40    | ahci       | 5CBDF51766 |
| 8086:1e02 | 1462:7758 | Intel      | 7 Series/C210 Series Chip... | 40    | ahci       | 6DD3E491F5 |
| 8086:1e03 | 17aa:21f3 | Intel      | 7 Series Chipset Family 6... | 40    | ahci       | B162D0FD81 |
| 8086:2929 | 1043:1867 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 40    | ahci       | 33E615851D |
| 8086:5ae3 | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 40    | ahci       | F885D0EE5F |
| 8086:1d02 | 1043:84ef | Intel      | C600/X79 series chipset 6... | 39    | ahci       | 39F22D868E |
| 10de:0ab9 | 10de:cb79 | Nvidia     | MCP79 AHCI Controller        | 38    | ahci       | 441575D073 |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27df | 1043:8179 | Intel      | 82801G (ICH7 Family) IDE ... | 617   | ata_pii... | B9B80DB558 |
| 1002:439c | 1458:5002 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 533   | pata_at... | E722D70419 |
| 8086:27c0 | 1458:b002 | Intel      | NM10/ICH7 Family SATA Con... | 442   | ata_pii... | ABA2A5E5E6 |
| 8086:27c0 | 1043:8179 | Intel      | NM10/ICH7 Family SATA Con... | 433   | ata_pii... | B9B80DB558 |
| 1002:439c | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 406   | pata_at... | 3C504F06A2 |
| 8086:27c0 | 1849:27c0 | Intel      | NM10/ICH7 Family SATA Con... | 267   | ata_pii... | 6FDB8DFE61 |
| 8086:27df | 1849:27df | Intel      | 82801G (ICH7 Family) IDE ... | 260   | ata_pii... | 6FDB8DFE61 |
| 8086:1c00 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 258   | ata_pii... | 274EEA3275 |
| 8086:1c08 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 258   | ata_pii... | 274EEA3275 |
| 197b:2363 | 1458:b000 | JMicron... | JMB363 SATA/IDE Controller   | 237   | ahci       | A056C6C7D5 |
| 1002:439c | 1849:439c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 236   | pata_at... | 704C328C67 |
| 10de:03f6 | 1849:03f6 | Nvidia     | MCP61 SATA Controller        | 222   | sata_nv... | EC1F6C8A0B |
| 8086:3a20 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) 4 ... | 215   | ata_pii... | 6949452F0E |
| 8086:3a26 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) 2 ... | 215   | ata_pii... | 6949452F0E |
| 10de:03ec | 1849:03ec | Nvidia     | MCP61 IDE                    | 210   | pata_am... | 9CBD6C2E0E |
| 8086:2926 | 1043:8277 | Intel      | 82801I (ICH9 Family) 2 po... | 209   | ata_pii... | 5EE0F1DB4C |
| 8086:1c08 | 1458:b002 | Intel      | 6 Series/C200 Series Chip... | 207   | ata_pii... | EF2DAAC6D3 |
| 8086:27c0 | 1043:2601 | Intel      | NM10/ICH7 Family SATA Con... | 190   | ata_pii... | 53D2EF8D02 |
| 197b:2368 | 1458:b000 | JMicron... | JMB368 IDE controller        | 177   | pata_jm... | E818A123C5 |
| 197b:2363 | 1043:824f | JMicron... | JMB363 SATA/IDE Controller   | 173   | ahci       | E40B76E473 |
| 8086:2921 | 1043:8277 | Intel      | 82801IB (ICH9) 2 port SAT... | 140   | ata_pii... | 5EE0F1DB4C |
| 8086:1e00 | 1458:b005 | Intel      | 7 Series/C210 Series Chip... | 128   | ata_pii... | A5E90F38C5 |
| 8086:1e08 | 1458:b002 | Intel      | 7 Series/C210 Series Chip... | 128   | ata_pii... | A5E90F38C5 |
| 10de:03f6 | 1458:b002 | Nvidia     | MCP61 SATA Controller        | 118   | sata_nv... | 53DB8982F5 |
| 8086:3a20 | 1458:b002 | Intel      | 82801JI (ICH10 Family) 4 ... | 112   | ata_pii... | 13ACEC4985 |
| 8086:3a26 | 1458:b002 | Intel      | 82801JI (ICH10 Family) 2 ... | 112   | ata_pii... | 13ACEC4985 |
| 1022:780c | 1458:5002 | AMD        | FCH IDE Controller           | 111   | pata_at... | BB64800479 |
| 197b:2363 | 1043:81e4 | JMicron... | JMB363 SATA/IDE Controller   | 110   | ahci       | 49BC4A3291 |
| 8086:1c00 | 1458:b002 | Intel      | 6 Series/C200 Series Chip... | 106   | ata_pii... | EF2DAAC6D3 |
| 1106:0415 | 1043:838f | VIA Tec... | VT6415 PATA IDE Host Cont... | 104   | pata_vi... | A43E9D5913 |
| 197b:2368 | 1043:827e | JMicron... | JMB368 IDE controller        | 104   | pata_jm... | 11FC0E438A |
| 8086:1c00 | 1458:b005 | Intel      | 6 Series/C200 Series Chip... | 103   | ata_pii... | 2302B497CC |
| 8086:1e00 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 100   | ata_pii... | C3FE050E13 |
| 8086:1e08 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 100   | ata_pii... | C3FE050E13 |
| 8086:27df | 1458:b001 | Intel      | 82801G (ICH7 Family) IDE ... | 96    | ata_pii... | 53B4651D22 |
| 8086:3b20 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 95    | ata_pii... | 3CDEB04C0D |
| 8086:3b26 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 95    | ata_pii... | 3CDEB04C0D |
| 10de:03ec | 1458:5002 | Nvidia     | MCP61 IDE                    | 94    | pata_am... | B1D7110D4D |
| 8086:2926 | 1458:b002 | Intel      | 82801I (ICH9 Family) 2 po... | 93    | ata_pii... | E818A123C5 |
| 1022:780c | 1849:780c | AMD        | FCH IDE Controller           | 85    | pata_at... | 8230399CC0 |
| 10de:03f6 | 1043:8234 | Nvidia     | MCP61 SATA Controller        | 82    | sata_nv... | F3B22A675A |
| 11ab:6101 | 1043:82e0 | Marvell... | 88SE6101/6102 single-port... | 82    | pata_ma... | 1A129F8DB6 |
| 10de:03ec | 1043:8234 | Nvidia     | MCP61 IDE                    | 79    | pata_am... | 8EEDF41BAD |
| 10de:03f6 | 1043:83a4 | Nvidia     | MCP61 SATA Controller        | 77    | sata_nv... | A6BD4DA213 |
| 1002:439c | 1002:439c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 75    | pata_at... | 9A42A921E7 |
| 10de:03ec | 1043:83a4 | Nvidia     | MCP61 IDE                    | 74    | pata_am... | A6BD4DA213 |
| 8086:2850 | 1025:011f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 71    | ata_pii... | BA9EFF4F3B |
| 8086:2920 | 1043:8277 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 69    | ata_pii... | CBDB605C4F |
| 1002:439c | 1043:82ef | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 68    | pata_at... | 96FD3589B3 |
| 11ab:6101 | 11ab:6101 | Marvell... | 88SE6101/6102 single-port... | 66    | pata_ma... | 41E70BF30B |
| 8086:1c00 | 1849:1c00 | Intel      | 6 Series/C200 Series Chip... | 65    | ata_pii... | 5DA8F545AA |
| 8086:1c08 | 1849:1c08 | Intel      | 6 Series/C200 Series Chip... | 64    | ata_pii... | 5DA8F545AA |
| 10de:0053 | 1043:815a | Nvidia     | CK804 IDE                    | 62    | pata_am... | FD8F010178 |
| 10de:0055 | 1043:815a | Nvidia     | CK804 Serial ATA Controller  | 62    | sata_nv... | FD8F010178 |
| 11ab:6121 | 1043:82a2 | Marvell... | 88SE6111/6121 SATA II / P... | 62    | pata_ma... | 5EE0F1DB4C |
| 10de:0054 | 1043:815a | Nvidia     | CK804 Serial ATA Controller  | 61    | sata_nv... | FD8F010178 |
| 8086:3b20 | 1458:b002 | Intel      | 5 Series/3400 Series Chip... | 61    | ata_pii... | E60C730AE2 |
| 8086:3b26 | 1458:b002 | Intel      | 5 Series/3400 Series Chip... | 61    | ata_pii... | E60C730AE2 |
| 8086:27c0 | 1462:7529 | Intel      | NM10/ICH7 Family SATA Con... | 60    | ata_pii... | 3DCC4EE3D0 |
| 8086:27c0 | 8086:27c0 | Intel      | NM10/ICH7 Family SATA Con... | 60    | ata_pii... | ED8C30E65A |
| 8086:2820 | 1043:81ec | Intel      | 82801H (ICH8 Family) 4 po... | 60    | ata_pii... | 49BC4A3291 |
| 8086:2825 | 1043:81ec | Intel      | 82801HR/HO/HH (ICH8R/DO/D... | 60    | ata_pii... | 49BC4A3291 |
| 8086:27df | 1462:7529 | Intel      | 82801G (ICH7 Family) IDE ... | 58    | ata_pii... | 3DCC4EE3D0 |
| 8086:27c0 | 1462:7592 | Intel      | NM10/ICH7 Family SATA Con... | 56    | ata_pii... | E5A422358F |
| 8086:2921 | 1458:b002 | Intel      | 82801IB (ICH9) 2 port SAT... | 54    | ata_pii... | E818A123C5 |
| 8086:27df | 1462:7592 | Intel      | 82801G (ICH7 Family) IDE ... | 53    | ata_pii... | E5A422358F |
| 8086:27df | 8086:27df | Intel      | 82801G (ICH7 Family) IDE ... | 48    | pata_acpi  | ED8C30E65A |
| 10de:03f6 | 1462:7309 | Nvidia     | MCP61 SATA Controller        | 47    | sata_nv... | 93E77F9DC3 |
| 1039:5513 | 1039:5513 | Silicon... | 5513 IDE Controller          | 45    | pata_si... | 1E2E967880 |
| 8086:24db | 1043:80a6 | Intel      | 82801EB/ER (ICH5/ICH5R) I... | 44    | ata_pii... | 387F6AEA89 |
| 1002:439c | 1043:8443 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 43    | pata_at... | FF37EF634B |
| 11ab:6121 | 1043:82e0 | Marvell... | 88SE6111/6121 SATA II / P... | 43    | pata_ma... | BF88ECBED4 |
| 8086:2850 | 17aa:20a6 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 42    | pata_acpi  | FB1CD7BF88 |
| 8086:2920 | 1458:b002 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 39    | ata_pii... | 01B25A0DED |
| 10de:03ec | 1565:3407 | Nvidia     | MCP61 IDE                    | 38    | pata_am... | 1004AD3220 |
| 10de:03f6 | 1565:5405 | Nvidia     | MCP61 SATA Controller        | 38    | sata_nv... | 1004AD3220 |
| 8086:2828 | 1025:011f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 37    | ata_pii... | F641323C9D |
| 1002:439c | 1043:104c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 36    | pata_at... | AE90CAFD98 |
| 10de:036e | 1043:8239 | Nvidia     | MCP55 IDE                    | 36    | pata_am... | 44E3D900F5 |
| 10de:037f | 1043:8239 | Nvidia     | MCP55 SATA Controller        | 36    | sata_nv... | 44E3D900F5 |
| 10de:0448 | 1462:7369 | Nvidia     | MCP65 IDE                    | 36    | pata_am... | 9DF2C0E0DD |
| 8086:27c0 | 1565:5202 | Intel      | NM10/ICH7 Family SATA Con... | 36    | ata_piix   | 843A450979 |
| 8086:27df | 1565:3103 | Intel      | 82801G (ICH7 Family) IDE ... | 36    | ata_piix   | 843A450979 |
| 10de:045d | 1462:7369 | Nvidia     | MCP65 SATA Controller        | 35    | pata_ac... | 9DF2C0E0DD |
| 10de:0759 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] IDE    | 35    | pata_am... | AFF249E34F |
| 10de:0ad0 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] SAT... | 35    | pata_ac... | AFF249E34F |
| 197b:2363 | 197b:2363 | JMicron... | JMB363 SATA/IDE Controller   | 35    | ahci       | 9650DD9DCE |
| 8086:3b20 | 1849:3b20 | Intel      | 5 Series/3400 Series Chip... | 35    | ata_pii... | E6B03B7FED |
| 8086:3b26 | 1849:3b26 | Intel      | 5 Series/3400 Series Chip... | 35    | ata_pii... | E6B03B7FED |
| 1002:439c | 1565:3700 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 34    | pata_at... | BD59D48011 |
| 1106:0415 | 1849:0415 | VIA Tec... | VT6415 PATA IDE Host Cont... | 34    | pata_vi... | 4CF5303FDE |
| 197b:2368 | 1043:824f | JMicron... | JMB368 IDE controller        | 34    | pata_jm... | 550E44C270 |
| 197b:2368 | 197b:2368 | JMicron... | JMB368 IDE controller        | 34    | pata_jm... | 0A74735DA6 |
| 1b4b:917a | 1458:b000 | Marvell... | 88SE9172 SATA III 6Gb/s R... | 34    | pata_ac... | E2923BE323 |
| 8086:2850 | 1028:01f9 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 34    | ata_pii... | 4908DA86B8 |
| 11ab:6121 | 11ab:6121 | Marvell... | 88SE6111/6121 SATA II / P... | 33    | pata_ma... | 40DD457351 |
| 8086:1c00 | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 33    | ata_pii... | 4BE423D57C |
| 8086:1c08 | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 33    | ata_pii... | 4BE423D57C |
| 8086:2820 | 1028:01da | Intel      | 82801H (ICH8 Family) 4 po... | 33    | pata_acpi  | B54A538301 |
| 8086:2825 | 1028:01da | Intel      | 82801HR/HO/HH (ICH8R/DO/D... | 33    | pata_acpi  | B54A538301 |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 482   | nvme       | 5E8A739106 |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 303   | nvme       | 65B1EB0CA1 |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 85    | nvme       | 961FA2224D |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 81    | nvme       | 105FE15441 |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/PC SN720 NV... | 75    | nvme       | E097415087 |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 62    | nvme       | F737A5A121 |
| 1179:0113 | 1179:0001 | Toshiba... | BG3 NVMe SSD Controller      | 58    | nvme       | CE87F391CE |
| 15b7:5003 | 15b7:5003 | Sandisk    | WD Black 2018/PC SN520 NV... | 58    | nvme       | 686232836E |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | Non-Volatile memory contr... | 58    | nvme       | E4301E56F9 |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 53    | nvme       | A47D005445 |
| 2646:5008 | 2646:5008 | Kingsto... | Non-Volatile memory contr... | 49    | nvme       | 2B46AD4F9B |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 49    | nvme       | 85B1AD8BA6 |
| 1c5c:1527 | 1c5c:1527 | SK Hynix   | Non-Volatile memory contr... | 46    | nvme       | 85085D7FF6 |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 43    | nvme       | AF51F8907E |
| 1179:0115 | 1179:0001 | Toshiba... | XG4 NVMe SSD Controller      | 38    | nvme       | C04DAFDA20 |
| 1179:011a | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 27    | nvme       | 1820A998EC |
| c0a9:2263 | c0a9:2263 | Micron/... | P1 NVMe PCIe SSD             | 23    | nvme       | 971B99D081 |
| 1179:010f | 1179:0001 | Toshiba... | NVMe Controller              | 22    | nvme       | 95BE835276 |
| 126f:2262 | 126f:2262 | Silicon... | Non-Volatile memory contr... | 21    | nvme       | 9BFAB5575C |
| 126f:2263 | 126f:2263 | Silicon... | Non-Volatile memory contr... | 21    | nvme       | EBF0A97D73 |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 20    | nvme       | C96C722A74 |
| 1987:5007 | 1987:5007 | Phison ... | E7 NVMe Controller           | 18    | nvme       | B711749144 |
| 14a4:2300 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 16    | nvme       | F473523657 |
| 15b7:5005 | 15b7:5005 | Sandisk    | Non-Volatile memory contr... | 12    | nvme       | C65ABD0640 |
| 10ec:5762 | 10ec:5762 | Realtek... | Realtek Non-Volatile memo... | 11    | nvme       | 85BB9ECF3B |
| 14a4:22f1 | 1b4b:1093 | Lite-On... | M8Pe Series NVMe SSD         | 10    | nvme       | 6DC8D77438 |
| 1987:5008 | 1987:5008 | Phison ... | NVMe Storage Controller      | 9     | nvme       | 859E021E2F |
| 1b85:6018 | 1b85:6018 | OCZ Tec... | RD400/400A SSD               | 9     | nvme       | ECD7F31C11 |
| 1cc4:5008 | 1cc4:5008 | Union M... | Non-Volatile memory contr... | 9     | nvme       | 153F2AFA98 |
| 1e0f:0001 | 1e0f:0001 |            | Non-Volatile memory contr... | 8     | nvme       | 2B2912B5B0 |
| 1344:5410 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 7     | nvme       | F2C853DD94 |
| 14a4:23f1 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 7     | nvme       | A46DB91F65 |
| 15b7:5001 | 1b4b:1093 | Sandisk    | WD Black NVMe SSD            | 7     | nvme       | 052FE8BC17 |
| 17aa:0004 | 17aa:1004 | Lenovo     | Non-Volatile memory contr... | 7     | nvme       | 7AB81DBD28 |
| 1c5c:1627 | 1c5c:1627 | SK Hynix   | Non-Volatile memory contr... | 7     | nvme       | 1F29F031C3 |
| 14a4:2200 | 1b4b:1093 | Lite-On... | Lite-On Non-Volatile memo... | 6     | nvme       | 6092C7644C |
| 15b7:5004 | 15b7:5004 | Sandisk    | Non-Volatile memory contr... | 6     | nvme       | 5C096F788D |
| 17aa:0003 | 17aa:1003 | Lenovo     | Non-Volatile memory contr... | 6     | nvme       | 4F055C0CF5 |
| 2646:2263 | 2646:2263 | Kingsto... | Technology Company Non-Vo... | 6     | nvme       | 7E1E79D0B1 |
| 10ec:5760 | 5760:10ec | Realtek... | Realtek Non-Volatile memo... | 5     | nvme       | 8ED3B0B386 |
| 1987:5016 | 1987:5016 | Phison ... | E16 PCIe4 NVMe Controller    | 5     | nvme       | 6DF8CD9DDD |
| 1c5c:1284 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 5     | nvme       | A549A39A12 |
| 8086:0953 | 8086:370d | Intel      | PCIe Data Center SSD         | 5     | nvme       | 7D5ADE4D65 |
| 14a4:2100 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 4     | nvme       | C28AED72AA |
| 17aa:0006 | 17aa:1006 | Lenovo     | Non-Volatile memory contr... | 4     | nvme       | DE55B048C0 |
| 1c5c:1283 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 4     | nvme       | 3B65E519FC |
| 1c5c:1285 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 4     | nvme       | 260CB1A4B0 |
| 1c5c:1504 | 0100:1093 | SK Hynix   | SC300 512GB M.2 2280 SATA... | 4     | nvme       | 58DDD64DA3 |
| 106b:2001 | 106b:2001 | Apple      | S1X NVMe Controller          | 3     | nvme       | 5984E1BBAC |
| 14a4:9100 | 126f:2263 | Lite-On... | NVMe Controller              | 3     | nvme       | 8F2F1D6173 |
| 15b7:5006 | 15b7:5006 | Sandisk    | Non-Volatile memory contr... | 3     | nvme       | E80AE71BD7 |
| 17aa:0005 | 17aa:1005 | Lenovo     | Non-Volatile memory contr... | 3     | nvme       | 444D60D6DA |
| 8086:2700 | 8086:3900 | Intel      | Optane SSD 900P Series       | 3     | nvme       | 376BED560D |
| 106b:2005 | 106b:1800 | Apple      | ANS2 NVMe Controller         | 2     |            | D3A040508D |
| 126f:2260 | 126f:2260 | Silicon... | Non-Volatile memory contr... | 2     | nvme       | 902BF4E864 |
| 144d:a806 | 144d:a801 | Samsung... | Electronics Non-Volatile ... | 2     | nvme       | 591E3665B7 |
| 144d:a809 | 144d:a801 | Samsung... | Electronics Non-Volatile ... | 2     | nvme       | 5D6DDB0705 |
| 2646:2262 | 2646:2262 | Kingsto... | Technology Company Non-Vo... | 2     | nvme       | 44204F310C |
| 8086:0975 | 8086:8410 | Intel      | Non-Volatile memory contr... | 2     | nvme       | 4EA8D503AE |
| 8086:0975 | 8086:8510 | Intel      | Non-Volatile memory contr... | 2     | nvme       | 4EA8D503AE |
| 8086:0a54 | 8086:4802 | Intel      | NVMe Datacenter SSD [3DNA... | 2     | nvme       | 9CF9DCEEE9 |
| 8086:2522 | 8086:3806 | Intel      | NVMe SSD Optane Series Co... | 2     | nvme       | BDA8F46AD6 |
| 8086:2522 | 8086:3810 | Intel      | NVMe SSD Optane Series Co... | 2     | nvme       | 4FABC3EA5D |
| 8086:2700 | 8086:3901 | Intel      | Optane SSD 900P Series       | 2     | nvme       | EC48803226 |
| 106b:2003 | 106b:2003 | Apple      | S3X NVMe Controller          | 1     | nvme       | E20833CAEE |
| 10ec:5763 | 10ec:5763 | Realtek... | Realtek Non-Volatile memo... | 1     | nvme       | 26C58B5F58 |
| 14a4:21f1 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 1     | nvme       | BB13C77033 |
| 14a4:5100 | 14a4:5100 | Lite-On... | Non-Volatile memory contr... | 1     | nvme       | 766158C703 |
| 1bb1:5012 | 1bb1:5012 | Seagate... | Non-Volatile memory contr... | 1     | nvme       | 9013346F71 |
| 1cc4:2260 | 1cc4:2260 | Union M... | Non-Volatile memory contr... | 1     | nvme       | CE03C99485 |
| 1cc4:5012 | 1cc4:5012 | Union M... | Non-Volatile memory contr... | 1     | nvme       | 7A301220F8 |
| 8086:0953 | 8086:00e1 | Intel      | PCIe Data Center SSD         | 1     | nvme       | 019BFC3983 |
| 8086:0953 | 8086:3702 | Intel      | PCIe Data Center SSD         | 1     | nvme       | 64918C950D |
| 8086:0953 | 8086:3704 | Intel      | PCIe Data Center SSD         | 1     | nvme       | 5F6D0233A8 |
| 8086:0953 | 8086:3705 | Intel      | PCIe Data Center SSD         | 1     | nvme       | 3F982F3E86 |
| 8086:0953 | 8086:370e | Intel      | PCIe Data Center SSD         | 1     | nvme       | 57804DB2FA |
| 8086:2522 | 8086:3802 | Intel      | NVMe SSD Optane Series Co... | 1     | nvme       | 9EE9F662A8 |
| 8086:2522 | 8086:3811 | Intel      | NVMe SSD Optane Series Co... | 1     | nvme       | AEAC4E0E68 |
| 8086:2701 | 8086:3904 | Intel      | NVMe Datacenter SSD [Optane] | 1     | nvme       | 64918C950D |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1106:3249 | 1106:3249 | VIA Tec... | VT6421 IDE/SATA Controller   | 37    | sata_via   | 3833787EFA |
| 8086:282a | 1028:0233 | Intel      | 82801 Mobile SATA Control... | 29    | ahci       | 314E0FF832 |
| 8086:282a | 103c:1818 | Intel      | 82801 Mobile SATA Control... | 25    | ahci       | 6C34B57DD0 |
| 8086:2822 | 1458:b005 | Intel      | SATA Controller [RAID mode]  | 22    | ahci       | CA561AA481 |
| 8086:2822 | 1028:0420 | Intel      | SATA Controller [RAID mode]  | 21    | ahci       | 2EBE664EEF |
| 8086:2822 | 1043:8694 | Intel      | SATA Controller [RAID mode]  | 21    | ahci       | AE2FCE57B5 |
| 8086:282a | 1028:0493 | Intel      | 82801 Mobile SATA Control... | 21    | ahci       | 3F252A50FB |
| 8086:282a | 1025:1264 | Intel      | 82801 Mobile SATA Control... | 17    | ahci       | FF5A6B10F9 |
| 8086:282a | 103c:84a6 | Intel      | 82801 Mobile SATA Control... | 17    | ahci       | 56A3768905 |
| 1000:005d | 1000:9363 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 16    | megarai... | 57FC9BDF47 |
| 1095:3114 | 1095:7114 | Silicon... | SiI 3114 [SATALink/SATARa... | 15    | sata_sil   | 401C11CCD1 |
| 1095:3132 | 1043:819f | Silicon... | SiI 3132 Serial ATA Raid ... | 15    | sata_sil24 | E41DDE12C3 |
| 8086:2822 | 103c:2a6f | Intel      | SATA Controller [RAID mode]  | 15    | ahci       | 5D4F2621EC |
| 8086:282a | 1028:040a | Intel      | 82801 Mobile SATA Control... | 15    | ahci       | D5CEA70705 |
| 1095:3512 | 1095:6512 | Silicon... | SiI 3512 [SATALink/SATARa... | 13    | sata_sil   | F1A5854551 |
| 8086:2822 | 103c:1309 | Intel      | SATA Controller [RAID mode]  | 13    | ahci       | 3F2B4E103F |
| 8086:282a | 1028:0534 | Intel      | 82801 Mobile SATA Control... | 13    | ahci       | 39D47C0F09 |
| 8086:282a | 1028:024f | Intel      | 82801 Mobile SATA Control... | 12    | ahci       | 00C163136F |
| 8086:282a | 1028:05ca | Intel      | 82801 Mobile SATA Control... | 12    | ahci       | C897C33BBA |
| 103c:323a | 103c:3245 | Hewlett... | Smart Array G6 controllers   | 11    | hpsa       | 8E0C4F7DB2 |
| 1106:3164 | 1106:3164 | VIA Tec... | VT6410 ATA133 RAID contro... | 11    | pata_vi... | 585D8319DA |
| 8086:2822 | 1028:05a4 | Intel      | SATA Controller [RAID mode]  | 11    | ahci       | E6F6F65F88 |
| 8086:2822 | 1458:b000 | Intel      | SATA Controller [RAID mode]  | 11    | ahci       | FCE6EE28A9 |
| 8086:282a | 1043:1fc0 | Intel      | 82801 Mobile SATA Control... | 11    | ahci       | 5129A11C87 |
| 8086:2822 | 1028:047e | Intel      | SATA Controller [RAID mode]  | 10    | ahci       | 858ED45F37 |
| 8086:2822 | 1043:8534 | Intel      | SATA Controller [RAID mode]  | 10    | ahci       | E93453380A |
| 8086:282a | 1028:062e | Intel      | 82801 Mobile SATA Control... | 10    | ahci       | 611A318D07 |
| 8086:282a | 17aa:3814 | Intel      | 82801 Mobile SATA Control... | 10    | ahci       | C47A5BBFAE |
| 8086:282a | 1028:04a3 | Intel      | 82801 Mobile SATA Control... | 9     | ahci       | D8BA5B1425 |
| 8086:282a | 1028:0532 | Intel      | 82801 Mobile SATA Control... | 9     | ahci       | 8E240EEE56 |
| 8086:282a | 103c:8532 | Intel      | 82801 Mobile SATA Control... | 9     | ahci       | 30DE8A33D7 |
| 1002:4392 | 1025:0444 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 8     | ahci       | 99825EFDBE |
| 1095:3112 | 1095:6112 | Silicon... | SiI 3112 [SATALink/SATARa... | 8     | sata_sil   | 73AE259285 |
| 1095:3132 | 1095:7132 | Silicon... | SiI 3132 Serial ATA Raid ... | 8     | sata_sil24 | 83413EEEDF |
| 1106:3149 | 1043:80ed | VIA Tec... | VIA VT6420 SATA RAID Cont... | 8     | sata_via   | D20509CA50 |
| 8086:2822 | 1028:0293 | Intel      | SATA Controller [RAID mode]  | 8     | ahci       | 952E382624 |
| 8086:282a | 1028:0494 | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | 4384225066 |
| 8086:282a | 1028:0535 | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | 6251A0DB90 |
| 8086:282a | 1028:053d | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | C87C3F181E |
| 8086:282a | 1028:05be | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | C7F7A6189C |
| 8086:282a | 1028:05cb | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | 04BD492077 |
| 8086:282a | 1043:1311 | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | D720B44576 |
| 8086:282a | 17aa:380f | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | 0806E2A6D8 |
| 1000:0079 | 1000:9263 | LSI Log... | MegaRAID SAS 2108 [Libera... | 7     | megarai... | C60718AEF4 |
| 13c1:1004 | 13c1:1004 | 3ware      | 9650SE SATA-II RAID PCIe     | 7     | 3w_9xxx    | B2DA218FF6 |
| 8086:2822 | 103c:130a | Intel      | SATA Controller [RAID mode]  | 7     | ahci       | F90C879481 |
| 8086:2822 | 103c:2a9c | Intel      | SATA Controller [RAID mode]  | 7     | ahci       | B897AD01AD |
| 8086:2822 | 1043:84ca | Intel      | SATA Controller [RAID mode]  | 7     | ahci       | 889648300B |
| 8086:2826 | 103c:1589 | Intel      | C600/X79 series chipset S... | 7     | ahci       | 9D85C4CA60 |
| 8086:282a | 1028:040b | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | 47A22D2542 |
| 8086:282a | 1028:0492 | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | 276041713D |
| 8086:282a | 103c:18a5 | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | A978F2CA38 |
| 8086:282a | 17aa:3810 | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | 7D8BB0BF84 |
| 1039:0180 | 1043:810e | Silicon... | RAID bus controller 180 S... | 6     | sata_sis   | BF1A9BA973 |
| 1283:8212 | 1283:0001 | Integra... | IT8212 Dual channel ATA R... | 6     | pata_it... | 38F4BB47C3 |
| 8086:2822 | 1028:06d9 | Intel      | SATA Controller [RAID mode]  | 6     | ahci       | 5F15FEDC3B |
| 8086:2822 | 1043:844d | Intel      | SATA Controller [RAID mode]  | 6     | ahci       | C7951A3833 |
| 8086:282a | 1028:0572 | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | FA7DA218EC |
| 8086:282a | 1028:06de | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | 78974F9610 |
| 8086:282a | 1028:0810 | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | 5CD9AAC635 |
| 8086:282a | 1028:081c | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | 9F4A416C12 |
| 8086:282a | 103c:18fd | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | 369A2DFC15 |
| 8086:282a | 103c:849a | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | E4CA853A88 |
| 8086:282a | 103c:84a7 | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | C84F48BF16 |
| 8086:282a | 1043:1501 | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | CF0266106B |
| 8086:282a | 1043:1961 | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | BAEE55FB37 |
| 1000:005d | 15d9:0809 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 5     | megarai... | 499CF2B15D |
| 1000:0060 | 1028:1f0c | LSI Log... | MegaRAID SAS 1078            | 5     | megarai... | F233ABA040 |
| 1000:0079 | 1028:1f17 | LSI Log... | MegaRAID SAS 2108 [Libera... | 5     | megarai... | FE6BA6A15C |
| 1002:4393 | 1043:84df | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 5     | ahci       | 747D9B1FD2 |
| 1095:0680 | 1095:3680 | Silicon... | PCI0680 Ultra ATA-133 Hos... | 5     | pata_si... | 3686BB6AC0 |
| 10b9:5287 | 1043:8056 | ULi Ele... | ULi 5287 SATA                | 5     | sata_uli   | 399101B245 |
| 1283:8212 |           | Integra... | IT8212 Dual channel ATA R... | 5     | pata_it... | 550E44C270 |
| 8086:2682 | 103c:1307 | Intel      | 631xESB/632xESB SATA RAID... | 5     | ahci       | B5BA9A13DC |
| 8086:2822 | 1025:0389 | Intel      | SATA Controller [RAID mode]  | 5     | ahci       | A4BB2D6329 |
| 8086:2822 | 1028:052c | Intel      | SATA Controller [RAID mode]  | 5     | ahci       | 636FBFDCB6 |
| 8086:2822 | 103c:1905 | Intel      | SATA Controller [RAID mode]  | 5     | ahci       | F3873460A2 |
| 8086:2822 | 8086:514d | Intel      | SATA Controller [RAID mode]  | 5     | ahci       | 7409A9492F |
| 8086:282a | 1028:024d | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 59050A5736 |
| 8086:282a | 1028:053c | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | F94D8B6C0A |
| 8086:282a | 1028:05aa | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 1D4C1380A3 |
| 8086:282a | 1028:05de | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 7A0E5E1EA2 |
| 8086:282a | 1028:062b | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 001F6A7015 |
| 8086:282a | 103c:1894 | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 0A6F4AEE88 |
| 8086:282a | 103c:84da | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 605A299A65 |
| 8086:282a | 1043:1b90 | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 8FF6A7E718 |
| 1000:005b | 1028:1f34 | LSI Log... | MegaRAID SAS 2208 [Thunde... | 4     | megarai... | D1FAA99D53 |
| 1000:0073 | 1028:1f51 | LSI Log... | MegaRAID SAS 2008 [Falcon]   | 4     | megarai... | 6DCBDBD9C8 |
| 1002:4393 | 1002:4393 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 4     | ahci       | E3E631B2A3 |
| 1022:43bd | 1b21:1062 | AMD        | FCH RAID Controller          | 4     |            | 2ED5B5AFC5 |
| 1022:7916 | 1022:7901 | AMD        | RS690 PCI to PCI Bridge (... | 4     | ahci       | 40061999CC |
| 1039:0180 | 1458:b003 | Silicon... | RAID bus controller 180 S... | 4     | sata_sis   | 967BB75CBB |
| 103c:3239 | 103c:21c0 | Hewlett... | Smart Array Gen9 Controllers | 4     | hpsa       | C9D389B2A3 |
| 103c:323b | 103c:3354 | Hewlett... | Smart Array Gen8 Controllers | 4     | hpsa       | 14A3E68490 |
| 105a:3373 | 1043:80f5 | Promise... | PDC20378 (FastTrak 378/SA... | 4     | sata_pr... | E75F4538BC |
| 1095:3114 | 1095:6114 | Silicon... | SiI 3114 [SATALink/SATARa... | 4     | sata_sil   | 34B91208C5 |
| 8086:2822 | 1025:0427 | Intel      | SATA Controller [RAID mode]  | 4     | ahci       | AE38CF07EA |
| 8086:2822 | 1028:01db | Intel      | SATA Controller [RAID mode]  | 4     | ahci       | A309FDA4F4 |
| 8086:2822 | 1028:026e | Intel      | SATA Controller [RAID mode]  | 4     | ahci       | 0E66E03CAC |
| 8086:2822 | 1028:02da | Intel      | SATA Controller [RAID mode]  | 4     | ahci       | 5D617B8DE0 |

### Storage/sas (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1d6b | 103c:1589 | Intel      | C602 chipset 4-Port SATA ... | 15    | isci       | 9D85C4CA60 |
| 8086:1d6b | 103c:158a | Intel      | C602 chipset 4-Port SATA ... | 8     | isci       | BAF893B7F3 |
| 1000:0072 | 1028:1f1c | LSI Log... | SAS2008 PCI-Express Fusio... | 6     | mpt3sas    | DCC2217331 |
| 1000:0072 | 1000:3020 | LSI Log... | SAS2008 PCI-Express Fusio... | 4     | mpt3sas    | 039AFB9C35 |
| 1000:0086 | 103c:158b | Broadco... | SAS2308 PCI-Express Fusio... | 4     | mpt3sas    | 7A65E2F97F |
| 8086:1d6b | 103c:158b | Intel      | C602 chipset 4-Port SATA ... | 4     | isci       | 7A65E2F97F |
| 1000:0072 | 15d9:0400 | Broadco... | SAS2008 PCI-Express Fusio... | 2     | mpt3sas    | A2C07ECC65 |
| 1000:0086 | 15d9:0691 | Broadco... | SAS2308 PCI-Express Fusio... | 2     | mpt3sas    | 9F3D443A21 |
| 1000:0087 | 1028:05a1 | Broadco... | SAS2308 PCI-Express Fusio... | 2     | mpt3sas    | C7E1E32971 |
| 1000:0097 | 1000:0090 | Broadco... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | 2903921AEB |
| 1000:0097 | 1000:30a0 | Broadco... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | E43A13CE79 |
| 1000:0097 | 1734:1214 | LSI Log... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | 3C409E3FAC |
| 8086:1d6b | 1028:0497 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | F1D5B6204E |
| 8086:1d6b | 17aa:1028 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 7E1E79D0B1 |
| 8086:1d6b | 1849:1d6b | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 2021C0A4A3 |
| 1000:0086 | 1000:0086 | LSI Log... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | 1B28CC994F |
| 8086:1d6a | 17aa:1027 | Intel      | C600/X79 series chipset D... | 1     | isci       | B7463FD8F2 |
| 8086:1d6b | 15d9:062f | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | F5F0A90676 |
| 8086:1d6b | 15d9:0636 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 93AEE84D4C |
| 8086:1d6b | 15d9:0703 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 8C793BB137 |
| 8086:1d6b | 15d9:0705 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | B3D08DD227 |
| 8086:1d6b | 15d9:0709 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 9F3D443A21 |
| 9005:028f | 103c:0701 | Adaptec    | Smart Storage PQI 12G SAS... | 1     | smartpqi   | 9E91D0ED19 |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1000:0058 | 1028:021d | LSI Log... | SAS1068E PCI-Express Fusi... | 5     | mptsas     | 82F1FBFA97 |
| 1000:0058 | 1028:1f0f | LSI Log... | SAS1068E PCI-Express Fusi... | 4     | mptsas     | E566F80CCC |
| 1000:0058 | 103c:130b | LSI Log... | SAS1068E PCI-Express Fusi... | 4     | mptsas     | 269249911A |
| 1000:0054 | 1028:1f08 | LSI Log... | SAS1068 PCI-X Fusion-MPT SAS | 3     | mptsas     | CB363A3342 |
| 1000:0058 | 1028:1f10 | Broadco... | SAS1068E PCI-Express Fusi... | 3     | mptsas     | 155DF30731 |
| 1b85:1021 | 1b85:1021 | OCZ Tec... | OCZ SCSI storage controller  | 3     | mvsas      | 6592929D60 |
| 1000:0030 | 1000:50c0 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 2     | mptspi     | CE615294BF |
| 1000:0030 | 103c:12f1 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 2     | mptspi     | 21D968D1E3 |
| 1000:0054 | 103c:0a98 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 2     | mptsas     | E68759AA8E |
| 1000:0056 | 1000:3090 | LSI Log... | SAS1064ET PCI-Express Fus... | 2     | mptsas     | 43427B2365 |
| 10cd:1300 | 10cd:1310 | Advance... | ASC1300 / ASC3030 [ABP940... | 2     | advansys   | 9978BC1A13 |
| 9004:5078 | 9004:7850 | Adaptec    | AIC-7850T/7856T [AVA-2902... | 2     | aic7xxx    | 5A21D12B42 |
| 1000:0058 | 1000:30a0 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | E5AEAF13AE |
| 1000:0058 | 1734:1130 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | 9404AF19C5 |
| 9004:5078 |           | Adaptec    | AIC-7850T/7856T [AVA-2902... | 1     | aic7xxx    | 50F010B8B5 |
| 9005:0010 | 9005:2180 | Adaptec    | AHA-2940U2/U2W               | 1     | aic7xxx    | 63F518652D |
| 9005:0080 | 9005:62a0 | Adaptec    | AIC-7892A U160/m             | 1     | aic7xxx    | 91524AD5FC |
| 9005:8012 | 9005:0042 | Adaptec    | ASC-29320 U320               | 1     | aic79xx    | 0ED86DABCC |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:16be | 1025:0647 | Broadco... | BCM57765/57785 MS Card Re... | 234   |            | 9084C70732 |
| 14e4:16bf | 1025:0647 | Broadco... | BCM57765/57785 xD-Picture... | 234   |            | 9084C70732 |
| 8086:d150 |           | Intel      | Core Processor QPI Link      | 187   |            | E40B76E473 |
| 8086:d151 |           | Intel      | Core Processor QPI Routin... | 187   |            | E40B76E473 |
| 8086:2576 |           | Intel      | 82865G/PE/P Processor to ... | 182   |            | 46CBFD5EE9 |
| 8086:d158 |           | Intel      | Core Processor Miscellane... | 174   |            | E40B76E473 |
| 197b:2382 | 1043:1a07 | JMicron... | SD/MMC Host Controller       | 121   | sdhci_pci  | 088FFC2823 |
| 8086:d156 |           | Intel      | Core Processor Semaphore ... | 106   |            | 3CDEB04C0D |
| 8086:d155 |           | Intel      | Core Processor System Man... | 105   |            | 3CDEB04C0D |
| 8086:d157 |           | Intel      | Core Processor System Con... | 105   |            | 3CDEB04C0D |
| 14e4:16be | 1025:0504 | Broadco... | BCM57765/57785 MS Card Re... | 104   |            | 832F6EF100 |
| 14e4:16bf | 1025:0504 | Broadco... | BCM57765/57785 xD-Picture... | 104   |            | 832F6EF100 |
| 197b:2383 | 1043:1a07 | JMicron... | MS Host Controller           | 103   | jmb38x_ms  | 088FFC2823 |
| 197b:2384 | 1043:1a07 | JMicron... | xD Host Controller           | 102   |            | 088FFC2823 |
| 8086:1911 | 1458:5000 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 88    |            | 8F2ECB882C |
| 8086:2f6e |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 88    |            | E5DA683598 |
| 8086:2f6f |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 88    |            | E5DA683598 |
| 8086:2f88 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 88    |            | E5DA683598 |
| 8086:2f8a |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 88    |            | E5DA683598 |
| 8086:2fae |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 88    |            | E5DA683598 |
| 8086:2faf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 88    |            | E5DA683598 |
| 8086:2fb8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 88    |            | E5DA683598 |
| 8086:2fb9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 88    |            | E5DA683598 |
| 8086:2fba |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 88    |            | E5DA683598 |
| 8086:2fbb |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 88    |            | E5DA683598 |
| 8086:2fbe |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 88    |            | E5DA683598 |
| 8086:2fbf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 88    |            | E5DA683598 |
| 8086:2ff8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 88    |            | E5DA683598 |
| 8086:2ff9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 88    |            | E5DA683598 |
| 1180:e822 | 17aa:2133 | Ricoh      | MMC/SD Host Controller       | 79    | sdhci_pci  | F3FBF8BC70 |
| 8086:2f1d | 8086:2f1d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 74    |            | E5DA683598 |
| 8086:2f1e | 8086:2f1e | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 74    |            | E5DA683598 |
| 8086:2f1f | 8086:2f1f | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 74    |            | E5DA683598 |
| 8086:2f71 | 8086:2f71 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 74    |            | E5DA683598 |
| 8086:2f98 | 8086:2f98 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 74    |            | E5DA683598 |
| 8086:2f99 | 8086:2f99 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 74    |            | E5DA683598 |
| 8086:2f9a | 8086:2f9a | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 74    |            | E5DA683598 |
| 8086:2f9c | 8086:2f9c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 74    |            | E5DA683598 |
| 8086:2fa0 | 8086:2fa0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 74    | sb_edac    | E5DA683598 |
| 8086:2fa8 | 8086:2fa8 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 74    |            | E5DA683598 |
| 8086:2faa | 8086:2faa | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 74    |            | E5DA683598 |
| 8086:2fab | 8086:2fab | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 74    |            | E5DA683598 |
| 8086:2fb0 | 8086:2fb0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 74    | hswep_u... | E5DA683598 |
| 8086:2fb1 | 8086:2fb1 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 74    | hswep_u... | E5DA683598 |
| 8086:2fb2 | 8086:2fb2 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 74    |            | E5DA683598 |
| 8086:2fb3 | 8086:2fb3 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 74    |            | E5DA683598 |
| 8086:2fc0 | 8086:2fc0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 74    | hswep_u... | E5DA683598 |
| 8086:2f68 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 73    |            | FD108DE325 |
| 8086:2fd0 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 73    | hswep_u... | FD108DE325 |
| 8086:1513 | 2222:1111 | Intel      | CV82524 Thunderbolt Contr... | 69    | pcieport   | 2B202B204B |
| 8086:d155 | 0043:0083 | Intel      | Core Processor System Man... | 69    |            | E40B76E473 |
| 8086:d156 | 0043:0083 | Intel      | Core Processor Semaphore ... | 69    |            | E40B76E473 |
| 8086:d157 | 0043:0083 | Intel      | Core Processor System Con... | 69    |            | E40B76E473 |
| 8086:2f81 | 8086:2f81 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 66    |            | E5DA683598 |
| 8086:2fe0 | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 66    |            | E5DA683598 |
| 8086:2fe1 | 8086:2fe1 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 66    |            | E5DA683598 |
| 8086:2fe2 | 8086:2fe2 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 66    |            | E5DA683598 |
| 8086:2fe3 | 8086:2fe3 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 66    |            | E5DA683598 |
| 8086:2ffc | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 66    |            | E5DA683598 |
| 8086:2ffd | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 66    |            | E5DA683598 |
| 8086:2ffe | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 66    |            | E5DA683598 |
| 8086:2fac | 8086:2fac | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 65    |            | 021596F9B3 |
| 8086:2fad | 8086:2fad | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 65    |            | 021596F9B3 |
| 8086:2fb4 | 8086:2fb4 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 65    | hswep_u... | 021596F9B3 |
| 8086:2fb5 | 8086:2fb5 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 65    | hswep_u... | 021596F9B3 |
| 8086:2fb6 | 8086:2fb6 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 65    |            | 021596F9B3 |
| 8086:2fb7 | 8086:2fb7 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 65    |            | 021596F9B3 |
| 8086:2fbc |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 64    |            | E5DA683598 |
| 8086:2fbd |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 64    |            | E5DA683598 |
| 8086:1911 | 8086:2015 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 62    |            | C96C722A74 |
| 1180:0592 | 17aa:20ca | Ricoh      | R5C592 Memory Stick Bus H... | 61    | r592       | 1A90AC4588 |
| 1180:0852 | 17aa:20cb | Ricoh      | xD-Picture Card Controller   | 61    | r852       | 1A90AC4588 |
| 8086:2016 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 60    |            | 0217F128CA |
| 8086:2018 | 8086:0000 | Intel      | Sky Lake-E M2PCI Registers   | 60    |            | 0217F128CA |
| 8086:2025 |           | Intel      | Sky Lake-E RAS               | 60    |            | 0217F128CA |
| 8086:2035 |           | Intel      | Sky Lake-E RAS Configurat... | 60    |            | 0217F128CA |
| 8086:2040 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 60    |            | 0217F128CA |
| 8086:2041 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 60    |            | 0217F128CA |
| 8086:2042 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 60    | skx_uncore | 0217F128CA |
| 8086:2043 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 60    |            | 0217F128CA |
| 8086:2044 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 60    |            | 0217F128CA |
| 8086:2045 | 8086:0000 | Intel      | Sky Lake-E LM Channel 1      | 60    |            | 0217F128CA |
| 8086:2046 | 8086:0000 | Intel      | Sky Lake-E LMS Channel 1     | 60    | skx_uncore | 0217F128CA |
| 8086:2047 | 8086:0000 | Intel      | Sky Lake-E LMDP Channel 1    | 60    |            | 0217F128CA |
| 8086:2048 | 8086:0000 | Intel      | Sky Lake-E DECS Channel 2    | 60    |            | 0217F128CA |
| 8086:2049 | 8086:0000 | Intel      | Sky Lake-E LM Channel 2      | 60    |            | 0217F128CA |
| 8086:204a | 8086:0000 | Intel      | Sky Lake-E LMS Channel 2     | 60    | skx_uncore | 0217F128CA |
| 8086:204b | 8086:0000 | Intel      | Sky Lake-E LMDP Channel 2    | 60    |            | 0217F128CA |
| 8086:204e | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 60    | skx_uncore | 0217F128CA |
| 8086:2054 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 60    |            | 0217F128CA |
| 8086:2055 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 60    |            | 0217F128CA |
| 8086:2056 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 60    |            | 0217F128CA |
| 8086:2057 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 60    |            | 0217F128CA |
| 8086:2066 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 60    | skx_uncore | 0217F128CA |
| 8086:2080 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 60    |            | 0217F128CA |
| 8086:2081 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 60    |            | 0217F128CA |
| 8086:2082 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 60    |            | 0217F128CA |
| 8086:2083 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 60    |            | 0217F128CA |
| 8086:2084 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 60    |            | 0217F128CA |
| 8086:2085 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 60    |            | 0217F128CA |

### Tv card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1131:7130 | 5ace:5050 | Philips... | SAA7130 Video Broadcast D... | 20    | saa7134    | 9F3A351654 |
| 109e:036e |           | Brooktree  | Bt878 Video Capture          | 18    | bttv       | 80274F5B0C |
| 1131:7133 | 1461:a11b | Philips... | SAA7131/SAA7133/SAA7135 V... | 18    | saa7134    | EEEEA0A3F1 |
| 1131:7133 | 5ace:5090 | Philips... | SAA7131/SAA7133/SAA7135 V... | 17    | saa7134    | E1C9E92E22 |
| 1131:7134 | 1461:9715 | Philips... | SAA7134/SAA7135HL Video B... | 14    | saa7134    | B6EA03FC1A |
| 1131:7134 | 5ace:5070 | Philips... | SAA7134/SAA7135HL Video B... | 14    | saa7134    | CE5C925F91 |
| 1131:7133 | 1461:4255 | Philips... | SAA7131/SAA7133/SAA7135 V... | 12    | saa7134    | E357EFF4D1 |
| 1131:7134 | 185b:c200 | Philips... | SAA7134/SAA7135HL Video B... | 12    | saa7134    | 3F25A03C59 |
| 1131:7130 | 1461:2115 | Philips... | SAA7130 Video Broadcast D... | 10    | saa7134    | 417D975CD9 |
| 1131:7133 | 0000:4091 | Philips... | SAA7131/SAA7133/SAA7135 V... | 9     | saa7134    | FA070462FC |
| 109e:036e | 1461:0003 | Brooktree  | Bt878 Video Capture          | 8     | bttv       | 48378AE22B |
| 1131:7130 | 1131:0000 | Philips... | SAA7130 Video Broadcast D... | 8     | saa7134    | D7CC0778FC |
| 1131:7133 | 185b:c100 | Philips... | SAA7131/SAA7133/SAA7135 V... | 8     | saa7134    | 5FE1529C55 |
| 1131:7133 | 5ace:7290 | Philips... | SAA7131/SAA7133/SAA7135 V... | 8     | saa7134    | 40DB916050 |
| 1131:7133 | 1461:0155 | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 331F603CE2 |
| 1131:7134 | 5ace:6070 | Philips... | SAA7134/SAA7135HL Video B... | 7     | saa7134    | 30A2676C2D |
| 4444:0016 | 0070:8801 | Interne... | iTVC16 (CX23416) Video De... | 7     | ivtv       | 8854FD6644 |
| 4444:0016 | 1461:c439 | Interne... | iTVC16 (CX23416) Video De... | 7     | ivtv       | B315D4391D |
| 1131:7133 | 1461:a14b | Philips... | SAA7131/SAA7133/SAA7135 V... | 6     | saa7134    | 2EF428DCCE |
| 1131:7133 | 16be:000d | Philips... | SAA7131/SAA7133/SAA7135 V... | 6     | saa7134    | B58CD9FD67 |
| 1131:7133 | 5ace:6090 | Philips... | SAA7131/SAA7133/SAA7135 V... | 6     | saa7134    | 30E31AE3DF |
| 1131:7133 | 5ace:7595 | Philips... | SAA7131/SAA7133/SAA7135 V... | 6     | saa7134    | 04549B5B94 |
| 1131:7134 | 5168:0138 | Philips... | SAA7134/SAA7135HL Video B... | 6     | saa7134    | E067B0A694 |
| 11de:6057 | 1031:7efe | Zoran      | ZR36057PQC Video cutting ... | 6     | zr36067    | DDF9D08A22 |
| 109e:036e | 0070:13eb | Brooktree  | Bt878 Video Capture          | 5     | bttv       | A43E9D5913 |
| 1131:7130 | 1461:a11b | Philips... | SAA7130 Video Broadcast D... | 5     | saa7134    | B29679845C |
| 1131:7133 | 1461:0055 | Philips... | SAA7131/SAA7133/SAA7135 V... | 5     | saa7134    | 867282B14C |
| 1131:7133 | 1461:a11a | Philips... | SAA7131/SAA7133/SAA7135 V... | 5     | saa7134    | 6B668249FB |
| 1131:7133 | 1461:f11d | Philips... | SAA7131/SAA7133/SAA7135 V... | 5     | saa7134    | 8C6F161892 |
| 1131:7133 | 5ace:6193 | Philips... | SAA7131/SAA7133/SAA7135 V... | 5     | saa7134    | 31DE6BD45A |
| 14f1:8800 |           | Conexan... | CX23880/1/2/3 PCI Video a... | 5     | cx8800     | 6A2846D1F0 |
| 1131:7130 | 0000:4051 | Philips... | SAA7130 Video Broadcast D... | 4     | saa7134    | 0B3E433CCC |
| 1131:7130 | 1461:2108 | Philips... | SAA7130 Video Broadcast D... | 4     | saa7134    | 61EF761A70 |
| 1131:7130 | 1461:a115 | Philips... | SAA7130 Video Broadcast D... | 4     | saa7134    | 74B6562CCD |
| 1131:7130 | 1461:a11a | Philips... | SAA7130 Video Broadcast D... | 4     | saa7134    | 0200BA924B |
| 1131:7133 | 0000:5071 | Philips... | SAA7131/SAA7133/SAA7135 V... | 4     | saa7134    | 07314F5868 |
| 1131:7133 | 1043:4845 | Philips... | SAA7131/SAA7133/SAA7135 V... | 4     | saa7134    | 1573DF6188 |
| 1131:7133 | 1131:0000 | Philips... | SAA7131/SAA7133/SAA7135 V... | 4     | saa7134    | 992938DD51 |
| 1131:7133 | 11bd:002e | Philips... | SAA7131/SAA7133/SAA7135 V... | 4     | saa7134    | CF053FB4E1 |
| 1131:7133 | 1461:f636 | Philips... | SAA7131/SAA7133/SAA7135 V... | 4     | saa7134    | A1228CD6CC |
| 1131:7133 | 5ace:7190 | Philips... | SAA7131/SAA7133/SAA7135 V... | 4     | saa7134    | C1BD1568DC |
| 1131:7134 | 0000:4071 | Philips... | SAA7134/SAA7135HL Video B... | 4     | saa7134    | D096BDC1A3 |
| 1131:7134 | 1131:0000 | Philips... | SAA7134/SAA7135HL Video B... | 4     | saa7134    | 3DCC4EE3D0 |
| 1131:7134 | 4e42:0138 | Philips... | SAA7134/SAA7135HL Video B... | 4     | saa7134    | AEAB86C587 |
| 1131:7134 | 5ace:6072 | Philips... | SAA7134/SAA7135HL Video B... | 4     | saa7134    | 254B040C92 |
| 14f1:8800 | 107d:6611 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     | cx8800     | EBD8A5801D |
| 14f1:8800 | b200:4200 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     | cx8800     | 6933983FAB |
| 14f1:8802 | b200:4200 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     | cx8802     | 6933983FAB |
| 109e:036e | 107d:6609 | Brooktree  | Bt878 Video Capture          | 3     | bttv       | 4A6B13BAEA |
| 1131:7130 | 1461:a10a | Philips... | SAA7130 Video Broadcast D... | 3     | saa7134    | 71FC19AA7D |
| 1131:7133 | 1461:a836 | Philips... | SAA7131/SAA7133/SAA7135 V... | 3     | saa7134    | 1CE26C391A |
| 1131:7133 | 1461:e836 | Philips... | SAA7131/SAA7133/SAA7135 V... | 3     | saa7134    | 29555CDBC9 |
| 1131:7133 | 16be:0010 | Philips... | SAA7131/SAA7133/SAA7135 V... | 3     | saa7134    | FF0A7B1FC8 |
| 1131:7133 | 5ace:5030 | Philips... | SAA7131/SAA7133/SAA7135 V... | 3     | saa7134    | 5F1C1865D9 |
| 1131:7133 | 5ace:6091 | Philips... | SAA7131/SAA7133/SAA7135 V... | 3     | saa7134    | 732F07E043 |
| 1131:7133 | 5ace:6092 | Philips... | SAA7131/SAA7133/SAA7135 V... | 3     | saa7134    | 97CDBE1C08 |
| 1131:7133 | 5ace:6190 | Philips... | SAA7131/SAA7133/SAA7135 V... | 3     | saa7134    | E3708C9C07 |
| 14f1:5b7a | 0070:7400 | Conexan... | CX23418 Single-Chip MPEG-... | 3     | cx18       | 86F900F93D |
| 14f1:8800 | 0070:6902 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     | cx8800     | B4A53FAFC1 |
| 14f1:8800 | 0070:9002 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     | cx8800     | 9531621804 |
| 14f1:8800 | 185b:e000 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     | cx8800     | 5B85C2F248 |
| 14f1:8800 | d420:9022 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     | cx8800     | B8ECD9CD1E |
| 14f1:8801 | 185b:e000 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     | cx88_alsa  | 5B85C2F248 |
| 14f1:8802 | 0070:6902 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     | cx8802     | B4A53FAFC1 |
| 14f1:8802 | d420:9022 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     | cx8802     | B8ECD9CD1E |
| 14f1:8811 | 0070:6902 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     | cx88_alsa  | B4A53FAFC1 |
| 14f1:8852 | 0070:6a28 | Conexan... | CX23885 PCI Video and Aud... | 3     | cx23885    | 898F2B7197 |
| 14f1:8852 | 0070:6b28 | Conexan... | CX23885 PCI Video and Aud... | 3     | cx23885    | 898F2B7197 |
| 14f1:8852 | 8000:3034 | Conexan... | CX23885 PCI Video and Aud... | 3     | cx23885    | 5DDB85C708 |
| 109e:0350 |           | Brooktree  | Bt848 Video Capture          | 2     | bttv       | FAC164E5F3 |
| 109e:036e | 11bd:0012 | Brooktree  | Bt878 Video Capture          | 2     | bttv       | AB36F565A4 |
| 109e:036e | 1461:0004 | Brooktree  | Bt878 Video Capture          | 2     | bttv       | F2B7867CAA |
| 1131:7130 | 107d:6655 | Philips... | SAA7130 Video Broadcast D... | 2     | saa7134    | 56F0C1E96B |
| 1131:7130 | 5168:0138 | Philips... | SAA7130 Video Broadcast D... | 2     | saa7134    | 21AB0E482F |
| 1131:7133 | 0000:507b | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | 1907FA3249 |
| 1131:7133 | 0070:6701 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | CD1B20C35D |
| 1131:7133 | 0458:6008 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | 60C13AD654 |
| 1131:7133 | 1043:4862 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | C9449F1C4A |
| 1131:7133 | 1461:2155 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | FA7720F25A |
| 1131:7133 | 1461:a70a | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | 88CFA65098 |
| 1131:7133 | 1461:f936 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | 45F1021882 |
| 1131:7133 | 1461:fb36 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | 09C02E478D |
| 1131:7133 | 17de:7136 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | 249D4C1A3F |
| 1131:7133 | 17de:7253 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | EF6C3DA38A |
| 1131:7133 | 5ace:6093 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | 550810BC29 |
| 1131:7133 | 5ace:6191 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | 4019627ACC |
| 1131:7133 | 5ace:7090 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | DA43CB5805 |
| 1131:7134 | 1131:233e | Philips... | SAA7134/SAA7135HL Video B... | 2     | saa7134    | 835B504D5C |
| 1131:7134 | 11bd:002b | Philips... | SAA7134/SAA7135HL Video B... | 2     | saa7134    | 6D5EB8ABBE |
| 1131:7134 | 1461:a70a | Philips... | SAA7134/SAA7135HL Video B... | 2     | saa7134    | DC6ED89D31 |
| 1131:7134 | 16be:5000 | Philips... | SAA7134/SAA7135HL Video B... | 2     | saa7134    | 7D2057C89D |
| 14f1:5b7a | 0070:740c | Conexan... | CX23418 Single-Chip MPEG-... | 2     | cx18       | 9B75A42A1E |
| 14f1:5b7a | 1179:0110 | Conexan... | CX23418 Single-Chip MPEG-... | 2     | cx18       | 3E0ED41BC7 |
| 14f1:8800 | 0070:6906 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | BCEE476272 |
| 14f1:8800 | 14f1:0084 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | 9214D5AED4 |
| 14f1:8800 | 17de:08b2 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | 5E5236F775 |
| 14f1:8800 | 1822:0023 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | AB36F565A4 |
| 14f1:8800 | 8922:8888 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | ADF2D5DACA |
| 14f1:8800 | b022:3022 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | AA10363A06 |
| 14f1:8800 | b033:3033 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | 1C7923E9B3 |

### Unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:31a2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_i... | 55981AF24A |
| 8086:5aa2 | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | F8913A087C |
| 8086:5aa2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | 6663E08482 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:4396 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 635   | ehci_hc... | E722D70419 |
| 1002:4397 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 635   | ohci_hc... | E722D70419 |
| 1002:4399 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 635   | ohci_hc... | E722D70419 |
| 8086:27c8 | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 629   | uhci_hcd   | B9B80DB558 |
| 8086:27c9 | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 629   | uhci_hcd   | B9B80DB558 |
| 8086:27ca | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 629   | uhci_hcd   | B9B80DB558 |
| 8086:27cb | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 629   | uhci_hcd   | B9B80DB558 |
| 8086:27cc | 1043:8179 | Intel      | NM10/ICH7 Family USB2 EHC... | 616   | ehci_hc... | B9B80DB558 |
| 1b21:1042 | 1043:8488 | ASMedia... | ASM1042 SuperSpeed USB Ho... | 602   | xhci_pci   | 2902DCE4BA |
| 1002:4396 | 1002:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 578   | ehci_hc... | F0615F7666 |
| 8086:1c26 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 543   | ehci_hc... | 13AF031E5E |
| 8086:1c2d | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 543   | ehci_hc... | 13AF031E5E |
| 1002:4397 | 1002:4397 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 462   | ohci_hc... | AFDF4A3A9C |
| 8086:27c8 | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 445   | uhci_hcd   | ABA2A5E5E6 |
| 8086:27c9 | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 445   | uhci_hcd   | ABA2A5E5E6 |
| 8086:27ca | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 445   | uhci_hcd   | ABA2A5E5E6 |
| 8086:27cb | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 445   | uhci_hcd   | ABA2A5E5E6 |
| 8086:27cc | 1458:5006 | Intel      | NM10/ICH7 Family USB2 EHC... | 445   | ehci_hc... | ABA2A5E5E6 |
| 1002:4396 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 406   | ehci_hc... | 3C504F06A2 |
| 1002:4397 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 406   | ohci_hc... | 3C504F06A2 |
| 1002:4398 | 1043:8389 | AMD        | SB7x0 USB OHCI1 Controller   | 404   | ohci_hc... | 3C504F06A2 |
| 1002:4399 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 404   | ohci_hc... | 3C504F06A2 |
| 1002:4399 | 1002:4399 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 391   | ohci_hc... | AFDF4A3A9C |
| 8086:1e26 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 387   | ehci_hc... | 91535E2115 |
| 8086:1e2d | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 387   | ehci_hc... | 91535E2115 |
| 8086:1e31 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 384   | xhci_pci   | 91535E2115 |
| 8086:8c26 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 364   | ehci_hc... | 15E3126F2C |
| 8086:8c31 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 360   | xhci_hcd   | 15E3126F2C |
| 8086:8c2d | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 358   | ehci_hc... | 15E3126F2C |
| 1002:4398 | 1458:5004 | AMD        | SB7x0 USB OHCI1 Controller   | 342   | ohci_hc... | EE209BFCD3 |
| 8086:1c26 | 1458:5006 | Intel      | 6 Series/C200 Series Chip... | 328   | ehci_hc... | EF2DAAC6D3 |
| 8086:1c2d | 1458:5006 | Intel      | 6 Series/C200 Series Chip... | 328   | ehci_hc... | EF2DAAC6D3 |
| 8086:3a34 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 310   | uhci_hcd   | 6949452F0E |
| 8086:3a35 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 310   | uhci_hcd   | 6949452F0E |
| 8086:3a36 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 310   | uhci_hcd   | 6949452F0E |
| 8086:3a37 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 310   | uhci_hcd   | 6949452F0E |
| 8086:3a38 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 310   | uhci_hcd   | 6949452F0E |
| 8086:3a39 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 310   | uhci_hcd   | 6949452F0E |
| 8086:3a3a | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 310   | ehci_hc... | 6949452F0E |
| 8086:3a3c | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 310   | ehci_hc... | 6949452F0E |
| 1b21:1142 | 1043:85bf | ASMedia... | ASM1042A USB 3.0 Host Con... | 305   | xhci_hcd   | 22A0854387 |
| 8086:1e26 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 301   | ehci_hc... | 8CE0C08E9A |
| 8086:1e2d | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 301   | ehci_hc... | 8CE0C08E9A |
| 8086:1e31 | 17aa:3977 | Intel      | 7 Series/C210 Series Chip... | 294   | xhci_pci   | 8CE0C08E9A |
| 8086:1e26 | 1458:5006 | Intel      | 7 Series/C216 Chipset Fam... | 285   | ehci_hc... | 5B67F6ED83 |
| 8086:1e2d | 1458:5006 | Intel      | 7 Series/C216 Chipset Fam... | 285   | ehci_hc... | 5B67F6ED83 |
| 8086:27c8 | 1849:27c8 | Intel      | NM10/ICH7 Family USB UHCI... | 276   | uhci_hcd   | 6FDB8DFE61 |
| 8086:27c9 | 1849:27c9 | Intel      | NM10/ICH7 Family USB UHCI... | 276   | uhci_hcd   | 6FDB8DFE61 |
| 8086:27ca | 1849:27ca | Intel      | NM10/ICH7 Family USB UHCI... | 276   | uhci_hcd   | 6FDB8DFE61 |
| 8086:27cb | 1849:27cb | Intel      | NM10/ICH7 Family USB UHCI... | 276   | uhci_hcd   | 6FDB8DFE61 |
| 8086:27cc | 1849:27cc | Intel      | NM10/ICH7 Family USB2 EHC... | 276   | ehci_hc... | 6FDB8DFE61 |
| 1b6f:7023 | 1458:5007 | Etron T... | EJ168 USB 3.0 Host Contro... | 269   | xhci_pci   | 0D6CA866B0 |
| 8086:1e31 | 1458:5007 | Intel      | 7 Series/C210 Series Chip... | 266   | xhci_hcd   | 5B67F6ED83 |
| 1002:4396 | 1849:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 251   | ehci_hc... | 704C328C67 |
| 1002:4397 | 1849:4397 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 251   | ohci_hc... | 704C328C67 |
| 1002:4399 | 1849:4399 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 251   | ohci_hc... | 704C328C67 |
| 8086:9d2f | 1043:201f | Intel      | Sunrise Point-LP USB 3.0 ... | 241   | xhci_hcd   | D720B44576 |
| 8086:2934 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 236   | uhci_hcd   | 5EE0F1DB4C |
| 8086:2935 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 236   | uhci_hcd   | 5EE0F1DB4C |
| 8086:2936 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 236   | uhci_hcd   | 5EE0F1DB4C |
| 8086:2937 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 236   | uhci_hcd   | 5EE0F1DB4C |
| 8086:2938 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 236   | uhci_hcd   | 5EE0F1DB4C |
| 8086:2939 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 236   | uhci_hcd   | 5EE0F1DB4C |
| 8086:293a | 1043:8277 | Intel      | 82801I (ICH9 Family) USB2... | 236   | ehci_hc... | 5EE0F1DB4C |
| 8086:293c | 1043:8277 | Intel      | 82801I (ICH9 Family) USB2... | 236   | ehci_hc... | 5EE0F1DB4C |
| 8086:a12f | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 235   | xhci_pci   | B8C562A7E5 |
| 10de:03f1 | 1849:03f1 | Nvidia     | MCP61 USB 1.1 Controller     | 223   | ohci_hc... | EC1F6C8A0B |
| 10de:03f2 | 1849:03f2 | Nvidia     | MCP61 USB 2.0 Controller     | 223   | ehci_hc... | EC1F6C8A0B |
| 8086:8c26 | 1458:5006 | Intel      | 8 Series/C220 Series Chip... | 222   | ehci_hc... | 502C5D4B04 |
| 8086:8c2d | 1458:5006 | Intel      | 8 Series/C220 Series Chip... | 222   | ehci_hc... | 502C5D4B04 |
| 1022:7807 | 1458:5004 | AMD        | FCH USB OHCI Controller      | 221   | ohci_hc... | 0CABEB6C95 |
| 1022:7808 | 1458:5004 | AMD        | FCH USB EHCI Controller      | 221   | ehci_hc... | 0CABEB6C95 |
| 8086:8c31 | 1458:5007 | Intel      | 8 Series/C220 Series Chip... | 221   | xhci_pci   | 502C5D4B04 |
| 1022:7809 | 1458:5004 | AMD        | FCH USB OHCI Controller      | 217   | ohci_hc... | 0CABEB6C95 |
| 8086:22b5 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 213   | xhci_hcd   | AE477CA654 |
| 1106:3038 | 1106:3038 | VIA Tec... | VT82xx/62xx UHCI USB 1.1 ... | 208   | uhci_hcd   | 4908CB8960 |
| 1106:3104 | 1106:3104 | VIA Tec... | USB 2.0                      | 201   | ehci_hc... | 4908CB8960 |
| 8086:27c8 | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 188   | uhci_hcd   | A6B1293F94 |
| 8086:27c9 | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 188   | uhci_hcd   | A6B1293F94 |
| 8086:27ca | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 188   | uhci_hcd   | A6B1293F94 |
| 8086:27cc | 1043:83ad | Intel      | NM10/ICH7 Family USB2 EHC... | 188   | ehci_hc... | A6B1293F94 |
| 8086:1c26 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 187   | ehci_hc... | 89EF922929 |
| 8086:1c2d | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 187   | ehci_hc... | 89EF922929 |
| 1033:0194 | 1043:8413 | NEC Com... | uPD720200 USB 3.0 Host Co... | 179   | xhci_hcd   | E40B76E473 |
| 1b21:1042 | 1043:1059 | ASMedia... | ASM1042 SuperSpeed USB Ho... | 179   | xhci_pci   | 55153BEE1A |
| 1106:3483 | 1458:5007 | VIA Tec... | VL805 USB 3.0 Host Contro... | 178   | xhci_pci   | BB239C7852 |
| 1022:43bb | 1b21:1142 | AMD        | 300 Series Chipset USB 3.... | 173   | xhci_hcd   | 4ED3A4A663 |
| 8086:27cb | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 172   | uhci_hcd   | A6B1293F94 |
| 1022:43d5 | 1b21:1142 | AMD        | 400 Series Chipset USB 3.... | 162   | xhci_hcd   | 5BCFE2F1CE |
| 8086:3a34 | 1458:5004 | Intel      | 82801JI (ICH10 Family) US... | 162   | uhci_hcd   | 13ACEC4985 |
| 8086:3a35 | 1458:5004 | Intel      | 82801JI (ICH10 Family) US... | 162   | uhci_hcd   | 13ACEC4985 |
| 8086:3a36 | 1458:5004 | Intel      | 82801JI (ICH10 Family) US... | 162   | uhci_hcd   | 13ACEC4985 |
| 8086:3a37 | 1458:5004 | Intel      | 82801JI (ICH10 Family) US... | 162   | uhci_hcd   | 13ACEC4985 |
| 8086:3a38 | 1458:5004 | Intel      | 82801JI (ICH10 Family) US... | 162   | uhci_hcd   | 13ACEC4985 |
| 8086:3a39 | 1458:5004 | Intel      | 82801JI (ICH10 Family) US... | 162   | uhci_hcd   | 13ACEC4985 |
| 8086:3a3a | 1458:5006 | Intel      | 82801JI (ICH10 Family) US... | 162   | ehci_hc... | 13ACEC4985 |
| 8086:3a3c | 1458:5006 | Intel      | 82801JI (ICH10 Family) US... | 162   | ehci_hc... | 13ACEC4985 |
| 1002:4399 | 1002:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 153   | ohci_hc... | F0615F7666 |
| 1106:3483 | 1106:3483 | VIA Tec... | VL805 USB 3.0 Host Contro... | 149   | xhci_hcd   | 053F507950 |
| 8086:3b34 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 142   | ehci_hc... | E40B76E473 |

### Wireless controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:7360 | 8086:0020 | Intel      | XMM7360 LTE Advanced Modem   | 14    |            | 7C5B2D05AE |
| 8086:7360 | 1cf8:8521 | Intel      | XMM7360 LTE Advanced Modem   | 6     |            | 2CF77D999D |
| 8086:7360 | 103c:8337 | Intel      | XMM7360 LTE Advanced Modem   | 5     |            | 65B1EB0CA1 |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8d7c | 1043:8600 | Intel      | C610/X99 series chipset SPSR | 33    |            | 021596F9B3 |
| 8086:8d7c | 15d9:0821 | Intel      | C610/X99 series chipset SPSR | 16    |            | 17BF7A3CBC |
| 8086:a1ec | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    |            | 4391DFF8D2 |
| 17a0:9750 | 17aa:2279 | Genesys... | GL9750 SD Host Controller    | 10    | sdhci_pci  | F737A5A121 |
| 8086:8d7c | 1028:0617 | Intel      | C610/X99 series chipset SPSR | 10    |            | 019BFC3983 |
| 8086:8d7c | 1458:7270 | Intel      | C610/X99 series chipset SPSR | 10    |            | AF58D23265 |
| 1aea:6625 | 103c:8478 | Alcor M... | Alcor Micro PCIe Card Reader | 8     |            | F473523657 |
| 8086:8d7c | 1849:8d7c | Intel      | C610/X99 series chipset SPSR | 8     |            | 917E16476B |
| 8086:8d7c | 1462:7885 | Intel      | C610/X99 series chipset SPSR | 7     |            | FDE33600E4 |
| 8086:8d7c | 103c:8030 | Intel      | C610/X99 series chipset SPSR | 6     |            | 140DAF886E |
| 8086:8d7c | 8086:7270 | Intel      | C610/X99 series chipset SPSR | 6     |            | E5DA683598 |
| 1002:6900 | 03ea:1af4 | AMD        | Topaz XT [Radeon R7 M260/... | 5     | amdgpu     | D0612D575F |
| 1af2:a001 | 1af2:a001 | AVerMedia  | Live Gamer HD                | 5     |            | 94934B2DA3 |
| 8086:2690 | 0000:0000 | Intel      | 631xESB/632xESB/3100 Chip... | 5     | pcieport   | A3AC5B74CF |
| 8086:3500 | 0000:0000 | Intel      | 6311ESB/6321ESB PCI Expre... | 5     | pcieport   | A3AC5B74CF |
| 8086:350c | 0000:0000 | Intel      | 6311ESB/6321ESB PCI Expre... | 5     | shpchp     | A3AC5B74CF |
| 8086:3510 | 0000:0000 | Intel      | 6311ESB/6321ESB PCI Expre... | 5     | pcieport   | A3AC5B74CF |
| 8086:3514 | 0000:0000 | Intel      | 6311ESB/6321ESB PCI Expre... | 5     | pcieport   | A3AC5B74CF |
| 8086:8d7c | 15d9:0831 | Intel      | C610/X99 series chipset SPSR | 5     |            | 64918C950D |
| 8086:8d7c | 8086:0000 | Intel      | C610/X99 series chipset SPSR | 5     |            | 2903921AEB |
| 8086:a1ec | 8086:7270 | Intel      | C620 Series Chipset Famil... | 5     |            | 8E73F804F5 |
| 10ec:5260 | 1028:0831 | Realtek... | RTS5260 PCI Express Card ... | 4     | rtsx_pci   | A5F184FD44 |
| 8086:2692 | 0000:0000 | Intel      | 631xESB/632xESB/3100 Chip... | 4     | pcieport   | A3AC5B74CF |
| 8086:2694 | 0000:0000 | Intel      | 631xESB/632xESB/3100 Chip... | 4     | pcieport   | A3AC5B74CF |
| 8086:2696 | 0000:0000 | Intel      | 631xESB/632xESB/3100 Chip... | 4     | pcieport   | A3AC5B74CF |
| 8086:31d6 | 0000:0000 | Intel      | Gemini Lake PCI Express R... | 4     | shpchp     | 5A0A25C9FF |
| 8086:31d7 | 0000:0000 | Intel      | Gemini Lake PCI Express R... | 4     | shpchp     | 5A0A25C9FF |
| 8086:3518 | 0000:0000 | Intel      | 6311ESB/6321ESB PCI Expre... | 4     | pcieport   | A3AC5B74CF |
| 8086:5ad9 | 0000:0000 | Intel      | Celeron N3350/Pentium N42... | 4     | shpchp     | 6F498D9D7D |
| 8086:8d7c | 15d9:0857 | Intel      | C610/X99 series chipset SPSR | 4     |            | 3347A5EBB1 |
| 8086:a1ed | 8086:7270 | Intel      | C620 Series Chipset Famil... | 4     |            | 8E73F804F5 |
| 8086:3a40 | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 3     | pcieport   | A4847544CA |
| 8086:3a42 | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 3     | pcieport   | A4847544CA |
| 8086:3a48 | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 3     | pcieport   | A4847544CA |
| 8086:8d7c | 1028:0601 | Intel      | C610/X99 series chipset SPSR | 3     |            | AF9F6ACE3F |
| 8086:8d7c | 1028:064c | Intel      | C610/X99 series chipset SPSR | 3     |            | E1BABF19AD |
| 8086:8d7c | 1043:85f6 | Intel      | C610/X99 series chipset SPSR | 3     |            | 7436C74DCB |
| 1002:694e | 1002:694e | AMD        | Polaris 22 XL [Radeon RX ... | 2     | amdgpu     | 07A9851CD6 |
| 17a0:9750 | 17aa:2286 | Genesys... | GL9750 SD Host Controller    | 2     | sdhci_pci  | 5EF9741E90 |
| 8086:3a44 | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 2     | pcieport   | 354B501A79 |
| 8086:3a46 | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 2     | pcieport   | 354B501A79 |
| 8086:3a4a | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 2     | pcieport   | 354B501A79 |
| 8086:5ad6 | 0000:0000 | Intel      | Celeron N3350/Pentium N42... | 2     | pcieport   | 6F498D9D7D |
| 8086:8d7c | 1028:0618 | Intel      | C610/X99 series chipset SPSR | 2     |            | 4C6E30FFB1 |
| 8086:8d7c | 103c:212b | Intel      | C610/X99 series chipset SPSR | 2     |            | 6B7FF8ADA9 |
| 8086:8d7c | 15d9:0824 | Intel      | C610/X99 series chipset SPSR | 2     |            | 6C96E4A591 |
| 8086:a1ec | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 2     |            | 931EA9A398 |
| 8086:a1ec | 15d9:095d | Intel      | C620 Series Chipset Famil... | 2     |            | 0DFD787765 |
| 8086:a1ec | 15d9:096d | Intel      | C620 Series Chipset Famil... | 2     |            | 8A5CFA81DD |
| 8086:a1ec | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 2     |            | 3AC4E6EB75 |
| 8086:a1ed | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 2     |            | 931EA9A398 |
| 8086:a1ed | 15d9:095d | Intel      | C620 Series Chipset Famil... | 2     |            | 0DFD787765 |
| 8086:a1ed | 15d9:096d | Intel      | C620 Series Chipset Famil... | 2     |            | 8A5CFA81DD |
| 8086:a1ed | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 2     |            | 3AC4E6EB75 |
| 0000:0000 | 8005:0000 |            |                              | 1     |            | 77F07D2D69 |
| 0000:0002 | 1105:8300 |            |                              | 1     |            | 3859A12973 |
| 1000:fury | 1000:9341 | Broadco... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 64918C950D |
| 1000:fury | 1000:9343 | Broadco... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 29B0070304 |
| 1000:fury | 1014:0456 | LSI Log... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 817865DED6 |
| 1000:fury | 1028:1f44 | LSI Log... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 5B9EC879FC |
| 1000:fury | 1028:1f4b | LSI Log... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | FF3ACF2BDC |
| 102b:0534 | 1028:04f6 | Matrox ... | G200eR2                      | 1     | mgag200    | 0FC3F83656 |
| 1045:c861 | 0045:8000 | OPTi       | 82C861 OHCI USB Host         | 1     | ohci-pci   | 806796F01E |
| 104c:8024 | 0020:0000 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 1     | firewir... | F5C15B4975 |
| 106b:0041 |           | Apple      | K2 KeyLargo Mac/IO           | 1     | macio      | 52B4B037A1 |
| 106b:0043 |           | Apple      | K2 ATA/100                   | 1     | pata_pc... | 52B4B037A1 |
| 10de:0bea | 1028:1534 | Nvidia     | GF108 High Definition Aud... | 1     | snd_hda... | 9401066945 |
| 10de:0bea | 1043:105c | Nvidia     | GF108 High Definition Aud... | 1     | snd_hda... | 2512ED1F69 |
| 10de:0bea | 1043:1477 | Nvidia     | GF108 High Definition Aud... | 1     | snd_hda... | 5BBF8E1E84 |
| 10de:0e1b | 0043:0000 | Nvidia     | GK107 HDMI Audio Controller  | 1     | snd_hda... | C5B21A1E4F |
| 10de:0e1b | 17aa:221e | Nvidia     | GK107 HDMI Audio Controller  | 1     | snd_hda... | 4C925D546F |
| 10de:10f9 | 17aa:3ffe | Nvidia     | TU106 High Definition Aud... | 1     | snd_hda... | 00ACF9644C |
| 10de:10fa | 10de:0000 | Nvidia     | TU107 GeForce GTX 1650 Hi... | 1     | snd_hda... | 8B4469D047 |
| 10de:1aeb | 1025:1342 | Nvidia     | TU116 High Definition Aud... | 1     | snd_hda... | F1749F3910 |
| 10de:1aeb | 10de:0000 | Nvidia     | TU116 High Definition Aud... | 1     | snd_hda... | 5B494E65BB |
| 10de:1c8c | 17aa:39d1 | Nvidia     | GP107M [GeForce GTX 1050 ... | 1     | nouveau    | 2DA8281FA9 |
| 10de:1f91 | 103c:8601 | Nvidia     | TU117M [GeForce GTX 1650 ... | 1     | nvidia     | 719C9DA612 |
| 10de:1fb9 | 10de:0000 | Nvidia     | TU117GLM [Quadro T1000 Mo... | 1     | nvidia     | B53EA50909 |
| 10ec-b... |           | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 1     | rtwpci     | D6005821D4 |
| 1131:7146 | ffff:ffff | Philips... | SAA7146                      | 1     |            | 4893225F50 |
| 1166:0140 | 0000:0000 | Broadcom   | HT2100 PCI-Express Bridge    | 1     | shpchp     | B7596E9C0E |
| 1186:4300 | ffff:ffff | D-Link ... | DGE-528T Gigabit Ethernet... | 1     | r8169      | 5C0883B543 |
| 1274:5880 | ffff:ffff | Ensoniq    | 5880B / Creative Labs CT5880 | 1     | snd_ens... | DF4BA14E49 |
| 127a:2014 | 144e:2014 | Rockwel... | HSF 56k Data/Fax/Voice Modem | 1     |            | 97FF18DC78 |
| 13f6:0111 | 5b7f:ce5f | C-Media... | CMI8738/CMI8768 PCI Audio    | 1     | snd_cmipci | 76442678ED |
| 13f6:0111 | fbff:fffd | C-Media... | CMI8738/CMI8768 PCI Audio    | 1     | snd_cmipci | 0528AB77BE |
| 13f6:8788 | ffff:ffff | C-Media... | CMI8788 [Oxygen HD Audio]    | 1     |            | 306E5B04F7 |
| 144a:5101 | 144a:5101 | Adlink ... |                              | 1     |            | E0E966D6B4 |
| 17fe:a220 | 1468:0305 | InProComm  |                              | 1     |            | 80E120B3A5 |
| 17fe:a220 | 1468:8305 | InProComm  |                              | 1     |            | 80E120B3A5 |
| 1912:001b | 1d49:0a02 | Renesas... | SH7758 PCIe End-Point [PBI]  | 1     |            | 817865DED6 |
| 1931:1011 | 1003:0001 | Option ... |                              | 1     |            | 28DFB478B7 |
| 1931:1011 | 1043:0001 | Option ... |                              | 1     |            | 28DFB478B7 |
| 1a41:0200 |           | Tilera     | TILE-Gx processor            | 1     | tilegxpci  | 08100751B7 |
| 1a41:0201 |           | Tilera     | TILE-Gx Processor Virtual... | 1     |            | 08100751B7 |
| 1aea:6625 | 103c:8349 | Alcor M... |                              | 1     |            | 1DEE29768A |
| 1aea:6625 | 103c:83a8 | Alcor M... |                              | 1     |            | 9ECD580CF7 |
| 1aea:6625 | 103c:83aa | Alcor M... | Alcor Micro PCIe Card Reader | 1     |            | 62C7769C30 |
| 1aea:6625 | 103c:85fa | Alcor M... |                              | 1     |            | 992E2074FF |
| 1fc8:0be0 |           | Lucid I... | HYDRA 200                    | 1     |            | F24106BC34 |

