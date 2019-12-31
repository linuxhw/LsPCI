Most popular PCI devices in Desktops
====================================

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Desktops ](#pci-devices)
   * [ Bluetooth ](#bluetooth-pci)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Dma controller (eisa dma) ](#dma-controller-eisa-dma-pci)
   * [ Docking station ](#docking-station-pci)
   * [ Dpio module ](#dpio-module-pci)
   * [ Dvb card ](#dvb-card-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Entertainment encryption device ](#entertainment-encryption-device-pci)
   * [ Firewire controller ](#firewire-controller-pci)
   * [ Flash memory ](#flash-memory-pci)
   * [ Generic system peripheral ](#generic-system-peripheral-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ I/o card ](#io-card-pci)
   * [ Input device controller ](#input-device-controller-pci)
   * [ Iommu ](#iommu-pci)
   * [ Ipmi interface (kcs) ](#ipmi-interface-kcs-pci)
   * [ Ipmi smic interface ](#ipmi-smic-interface-pci)
   * [ Isdn adapter ](#isdn-adapter-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Modem ](#modem-pci)
   * [ Multimedia ](#multimedia-pci)
   * [ Multimedia controller ](#multimedia-controller-pci)
   * [ Multiport serial controller ](#multiport-serial-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Non-essential instrumentation ](#non-essential-instrumentation-pci)
   * [ Non-vga unclassified device ](#non-vga-unclassified-device-pci)
   * [ Parallel controller (bidir) ](#parallel-controller-bidir-pci)
   * [ Parallel controller (ecp) ](#parallel-controller-ecp-pci)
   * [ Parallel controller (ieee1284) ](#parallel-controller-ieee1284-pci)
   * [ Performance counters ](#performance-counters-pci)
   * [ Pic (8259) ](#pic-8259-pci)
   * [ Pic (io(x)-apic) ](#pic-iox-apic-pci)
   * [ Pic (io-apic) ](#pic-io-apic-pci)
   * [ Power pc ](#power-pc-pci)
   * [ Processing accelerators ](#processing-accelerators-pci)
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
   * [ Others ](#others-pci)

PCI Devices
-----------

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bluetooth (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1814:3298 | 103c:18ec | Ralink     | RT3290 Bluetooth             | 7     | rtbth      | 92DD9B01DE |
| 1814:3298 | 1a3b:2787 | Ralink     | RT3290 Bluetooth             | 4     |            | 375A7150DE |
| 1814:3298 | 1a3b:2987 | Ralink     | RT3290 Bluetooth             | 1     |            | 1D26C2B648 |

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:4384 |           | AMD        | SBx00 PCI to PCI Bridge      | 2416  |            | F0615F7666 |
| 1022:1200 |           | AMD        | Family 10h Processor Hype... | 1762  |            | 93E77F9DC3 |
| 1022:1201 |           | AMD        | Family 10h Processor Addr... | 1762  |            | 93E77F9DC3 |
| 1022:1202 |           | AMD        | Family 10h Processor DRAM... | 1762  | amd64_e... | 93E77F9DC3 |
| 1022:1203 |           | AMD        | Family 10h Processor Misc... | 1762  | k10temp    | 93E77F9DC3 |
| 1022:1204 |           | AMD        | Family 10h Processor Link... | 1762  |            | 93E77F9DC3 |
| 1022:1100 |           | AMD        | K8 [Athlon64/Opteron] Hyp... | 1025  |            | 476F99FF1B |
| 1022:1101 |           | AMD        | K8 [Athlon64/Opteron] Add... | 1025  |            | 476F99FF1B |
| 1022:1102 |           | AMD        | K8 [Athlon64/Opteron] DRA... | 1025  | amd64_e... | 476F99FF1B |
| 1022:1103 |           | AMD        | K8 [Athlon64/Opteron] Mis... | 1025  | k8temp     | 476F99FF1B |
| 1002:439d | 1002:439d | AMD        | SB7x0/SB8x0/SB9x0 LPC hos... | 1002  |            | E722D70419 |
| 1022:1600 |           | AMD        | Family 15h Processor Func... | 989   |            | 3C504F06A2 |
| 1022:1601 |           | AMD        | Family 15h Processor Func... | 989   |            | 3C504F06A2 |
| 1022:1602 |           | AMD        | Family 15h Processor Func... | 989   |            | 3C504F06A2 |
| 1022:1603 |           | AMD        | Family 15h Processor Func... | 989   | k10temp    | 3C504F06A2 |
| 1022:1604 |           | AMD        | Family 15h Processor Func... | 989   | fam15h_... | 3C504F06A2 |
| 1022:1605 |           | AMD        | Family 15h Processor Func... | 989   |            | 3C504F06A2 |
| 8086:244e | 1458:5000 | Intel      | 82801 PCI Bridge             | 886   |            | ABA2A5E5E6 |
| 1022:780f |           | AMD        | FCH PCI Bridge               | 738   |            | 0CABEB6C95 |
| 8086:244e |           | Intel      | 82801 PCI Bridge             | 737   | shpchp     | 46CBFD5EE9 |
| 1022:1452 |           | AMD        | Family 17h (Models 00h-1f... | 697   |            | 5E8A739106 |
| 1b21:1080 | 1043:8489 | ASMedia... | ASM1083/1085 PCIe to PCI ... | 632   | shpchp     | 2F0B3935B3 |
| 8086:244e | 1043:8179 | Intel      | 82801 PCI Bridge             | 629   |            | B9B80DB558 |
| 8086:27b8 | 1043:8179 | Intel      | 82801GB/GR (ICH7 Family) ... | 629   | lpc_ich    | B9B80DB558 |
| 8086:27d0 | 1043:8179 | Intel      | NM10/ICH7 Family PCI Expr... | 616   | shpchp     | B9B80DB558 |
| 1002:43a0 | 1002:0000 | AMD        | SB700/SB800/SB900 PCI to ... | 573   | shpchp     | E722D70419 |
| 8086:1c10 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 538   | shpchp     | 13AF031E5E |
| 1002:5a14 | 1002:5a14 | AMD        | RD9x0/RX980 Host Bridge      | 537   | ati_agp    | AFDF4A3A9C |
| 1002:5a16 | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 522   | shpchp     | AFDF4A3A9C |
| 1022:1460 |           | AMD        | Family 17h (Models 00h-0f... | 512   |            | 5E8A739106 |
| 1022:1461 |           | AMD        | Family 17h (Models 00h-0f... | 512   |            | 5E8A739106 |
| 1022:1462 |           | AMD        | Family 17h (Models 00h-0f... | 512   |            | 5E8A739106 |
| 1022:1463 |           | AMD        | Family 17h (Models 00h-0f... | 512   | k10temp    | 5E8A739106 |
| 1022:1464 |           | AMD        | Family 17h (Models 00h-0f... | 512   |            | 5E8A739106 |
| 1022:1465 |           | AMD        | Family 17h (Models 00h-0f... | 512   |            | 5E8A739106 |
| 1022:1466 |           | AMD        | Family 17h (Models 00h-0f... | 512   |            | 5E8A739106 |
| 1022:1467 |           | AMD        | Family 17h (Models 00h-0f... | 512   |            | 5E8A739106 |
| 1002:5a18 | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 500   | shpchp     | AFDF4A3A9C |
| 8086:244e | 1849:244e | Intel      | 82801 PCI Bridge             | 484   | pcieport   | 6FDB8DFE61 |
| 8086:27d2 | 1043:8179 | Intel      | NM10/ICH7 Family PCI Expr... | 474   | shpchp     | B9B80DB558 |
| 8086:0c01 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 467   | shpchp     | 15E3126F2C |
| 8086:0c00 | 1043:8534 | Intel      | 4th Gen Core Processor DR... | 466   | hsw_uncore | 15E3126F2C |
| 8086:27b8 | 1458:5001 | Intel      | 82801GB/GR (ICH7 Family) ... | 441   | lpc_ich    | ABA2A5E5E6 |
| 1022:43b4 | 1b21:3306 | AMD        | 300 Series Chipset PCIe Port | 425   | pcieport   | 5E8A739106 |
| 1022:1454 | 1022:1454 | AMD        | Family 17h (Models 00h-0f... | 418   | pcieport   | 5E8A739106 |
| 8086:244e | 1458:8892 | Intel      | 82801 PCI Bridge             | 411   |            | 984B3421C1 |
| 1022:1400 |           | AMD        | Family 15h (Models 10h-1f... | 410   |            | 0CABEB6C95 |
| 1022:1401 |           | AMD        | Family 15h (Models 10h-1f... | 410   |            | 0CABEB6C95 |
| 1022:1402 |           | AMD        | Family 15h (Models 10h-1f... | 410   |            | 0CABEB6C95 |
| 1022:1403 |           | AMD        | Family 15h (Models 10h-1f... | 410   | k10temp    | 0CABEB6C95 |
| 1022:1404 |           | AMD        | Family 15h (Models 10h-1f... | 410   |            | 0CABEB6C95 |
| 1022:1405 |           | AMD        | Family 15h (Models 10h-1f... | 410   |            | 0CABEB6C95 |
| 1002:439d | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 LPC hos... | 406   |            | 3C504F06A2 |
| 8086:0101 | 1043:844d | Intel      | Xeon E3-1200/2nd Generati... | 398   | shpchp     | 274EEA3275 |
| 8086:0100 | 1043:844d | Intel      | 2nd Generation Core Proce... | 397   | snb_uncore | 274EEA3275 |
| 8086:1e10 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 380   | shpchp     | 535FBF3562 |
| 8086:1c1a | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 372   | shpchp     | 13AF031E5E |
| 10de:03e8 | 10de:0000 | Nvidia     | MCP61 PCI Express bridge     | 368   | shpchp     | F60B0BE33D |
| 8086:244e | 1458:5001 | Intel      | 82801 PCI Bridge             | 367   | pcieport   | A5E90F38C5 |
| 8086:8c10 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 355   | shpchp     | 15E3126F2C |
| 8086:1c5c | 1043:844d | Intel      | H61 Express Chipset LPC C... | 343   | lpc_ich    | 13AF031E5E |
| 1022:43a0 | 1022:0000 | AMD        | Hudson PCI to PCI bridge ... | 334   | shpchp     | 22A0854387 |
| 8086:244e | 1043:844d | Intel      | 82801 PCI Bridge             | 324   | pcieport   | 274EEA3275 |
| 8086:244e | 1043:84ca | Intel      | 82801 PCI Bridge             | 322   | pcieport   | 91535E2115 |
| 8086:1c10 | 1458:5001 | Intel      | 6 Series/C200 Series Chip... | 321   | shpchp     | EF2DAAC6D3 |
| 8086:27d0 | 1458:5001 | Intel      | NM10/ICH7 Family PCI Expr... | 318   | shpchp     | ABA2A5E5E6 |
| 1022:9600 | 1043:8388 | AMD        | RS780 Host Bridge            | 316   |            | 3C504F06A2 |
| 8086:244e | 1043:82d4 | Intel      | 82801 PCI Bridge             | 314   |            | 6949452F0E |
| 8086:0c00 | 1458:5000 | Intel      | 4th Gen Core Processor DR... | 308   | hsw_uncore | 984B3421C1 |
| 1002:5a1c | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 303   | shpchp     | AFDF4A3A9C |
| 8086:8c14 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 303   | shpchp     | 15E3126F2C |
| 10de:03e9 | 10de:0000 | Nvidia     | MCP61 PCI Express bridge     | 293   | shpchp     | F60B0BE33D |
| 8086:1e18 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 292   | shpchp     | 535FBF3562 |
| 8086:0150 | 1458:5000 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 289   | ie31200... | 5B67F6ED83 |
| 1022:1453 | 1022:1453 | AMD        | Family 17h (Models 00h-0f... | 284   | pcieport   | 5E8A739106 |
| 8086:0151 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 284   | shpchp     | 91535E2115 |
| 8086:0150 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 283   | ie31200... | 91535E2115 |
| 8086:1e10 | 1458:5001 | Intel      | 7 Series/C216 Chipset Fam... | 281   | shpchp     | 5B67F6ED83 |
| 1022:9600 | 1022:9600 | AMD        | RS780 Host Bridge            | 280   |            | EE209BFCD3 |
| 1022:43c7 | 1b21:3306 | AMD        | 400 Series Chipset PCIe Port | 276   | pcieport   | 5BCFE2F1CE |
| 8086:27d0 | 1849:27d0 | Intel      | NM10/ICH7 Family PCI Expr... | 274   | shpchp     | 6FDB8DFE61 |
| 8086:27b8 | 1849:27b8 | Intel      | 82801GB/GR (ICH7 Family) ... | 270   | lpc_ich    | 6FDB8DFE61 |
| 8086:29c0 | 1458:5000 | Intel      | 82G33/G31/P35/P31 Express... | 264   | agpgart... | ABA2A5E5E6 |
| 8086:27d2 | 1849:27d2 | Intel      | NM10/ICH7 Family PCI Expr... | 263   | shpchp     | 6FDB8DFE61 |
| 8086:1901 | 1043:8694 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 256   | shpchp     | 345BBA3C1F |
| 1002:439d | 1849:439d | AMD        | SB7x0/SB8x0/SB9x0 LPC hos... | 251   |            | 704C328C67 |
| 10de:03f3 | 10de:cb84 | Nvidia     | MCP61 PCI bridge             | 249   |            | 93E77F9DC3 |
| 1022:9603 | 1043:8388 | AMD        | RS780 PCI to PCI bridge (... | 247   | shpchp     | 3C504F06A2 |
| 8086:27d2 | 1458:5001 | Intel      | NM10/ICH7 Family PCI Expr... | 247   | shpchp     | 9928EAEA06 |
| 1002:5a1b | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 241   | shpchp     | 26465880BF |
| 8086:0151 | 1458:5000 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 238   | shpchp     | 5B67F6ED83 |
| 8086:a118 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 238   | shpchp     | B8C562A7E5 |
| 1022:43c6 | 1b21:0201 | AMD        | 400 Series Chipset PCIe B... | 236   | pcieport   | 5BCFE2F1CE |
| 8086:1c18 | 1458:5001 | Intel      | 6 Series/C200 Series Chip... | 236   | shpchp     | EF2DAAC6D3 |
| 8086:244e | 1043:8277 | Intel      | 82801 PCI Bridge             | 236   |            | 5EE0F1DB4C |
| 8086:3a40 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) PC... | 234   | shpchp     | 6949452F0E |
| 1002:43a1 | 1002:0000 | AMD        | SB700/SB800/SB900 PCI to ... | 232   | shpchp     | 0D6CA866B0 |
| 8086:2940 | 1043:8277 | Intel      | 82801I (ICH9 Family) PCI ... | 232   | shpchp     | 5EE0F1DB4C |
| 8086:29c0 | 1043:82b0 | Intel      | 82G33/G31/P35/P31 Express... | 230   | agpgart... | B9B80DB558 |
| 8086:29c1 | 1458:5000 | Intel      | 82G33/G31/P35/P31 Express... | 227   | shpchp     | ABA2A5E5E6 |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:522a | 1458:1000 | Realtek... | RTS522A PCI Express Card ... | 7     | rtsx_pci   | 39694A0489 |
| 10ec:525a | 1028:07ee | Realtek... | RTS525A PCI Express Card ... | 7     | rtsx_pci   | C708B6ADE4 |
| 10ec:5229 | 103c:2b38 | Realtek... | RTS5229 PCI Express Card ... | 6     | rtsx_pci   | C84840828C |
| 10ec:5229 | 17aa:366b | Realtek... | RTS5229 PCI Express Card ... | 6     | rtsx_pci   | EE0395FCB1 |
| 10ec:5229 | 1b0a:016c | Realtek... | RTS5229 PCI Express Card ... | 4     | rtsx_pci   | 0DF79259C1 |
| 10ec:5209 | 103c:2ac3 | Realtek... | RTS5209 PCI Express Card ... | 3     | rtsx_pci   | BE8250E028 |
| 10ec:5209 | 103c:2adc | Realtek... | RTS5209 PCI Express Card ... | 3     | rtsx_pci   | BCB415EA57 |
| 10ec:5209 | 103c:2af0 | Realtek... | RTS5209 PCI Express Card ... | 3     | rtsx_pci   | CE9938531D |
| 10ec:5229 | 103c:2af9 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 28B99207FE |
| 10ec:5289 | 10ec:5289 | Realtek... | RTL8411 PCI Express Card ... | 2     | rtsx_pci   | CD64391DDA |
| 10ec:5209 | 1025:8020 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 06609A514E |
| 10ec:5209 | 103c:2ac5 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 389B273157 |
| 10ec:5209 | 103c:2ac7 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 7A9D5AF1CE |
| 10ec:5209 | 103c:2b02 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 74E79527D5 |
| 10ec:5209 | 103c:3399 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 97624FD935 |
| 10ec:5209 | 1b0a:015e | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 15DEA2CF84 |
| 10ec:5229 | 103c:2af8 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | CF7972F23A |
| 10ec:5229 | 103c:2b15 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 24DD32836D |
| 10ec:5229 | 103c:2b3c | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | B62C50E352 |
| 10ec:5229 | 103c:2b43 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | B6867DCF24 |
| 10ec:5229 | 1b0a:018a | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | CAA7CA382E |
| 10ec:522a | 10ec:522a | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 39694A0489 |
| 10ec:5249 | 10ec:5249 | Realtek... | RTS5249 PCI Express Card ... | 1     | rtsx_pci   | 226AEEFEC2 |
| 10ec:525a | 1028:085a | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | B7022F0A45 |
| 10ec:525a | 1734:122e | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | 14943339B4 |
| 1aea:6621 | 1aea:6621 | Alcor M... | Alcor Micro PCIe Card Reader | 1     |            | 0F9AA13B55 |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0753 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Co-... | 38    |            | AFF249E34F |
| 10de:0753 | 1849:0753 | Nvidia     | MCP78S [GeForce 8200] Co-... | 26    |            | 41F3167FB7 |
| 10de:03f4 | 1462:7309 | Nvidia     | MCP61 SMU                    | 20    |            | C137270C84 |
| 10de:03f4 | 1462:7597 | Nvidia     | MCP61 SMU                    | 16    |            | 2DC1AE73B8 |
| 10de:0753 | 1043:82e2 | Nvidia     | MCP78S [GeForce 8200] Co-... | 11    |            | 007691F448 |
| 10de:0aa3 | 1025:0222 | Nvidia     | MCP79 Co-processor           | 8     | nvidia     | 4F99355CFD |
| 10de:03f4 | 1043:8234 | Nvidia     | MCP61 SMU                    | 7     |            | D3A9A22C8A |
| 10de:03f4 |           | Nvidia     | MCP61 SMU                    | 6     |            | FC9814BA3A |
| 10de:0543 | 1849:0543 | Nvidia     | MCP67 Co-processor           | 6     |            | 1C80EA8C25 |
| 10de:0aa3 | 1b0a:0074 | Nvidia     | MCP79 Co-processor           | 6     | nvidia     | 4EA9D337D7 |
| 10de:0753 | 1043:82e8 | Nvidia     | MCP78S [GeForce 8200] Co-... | 5     |            | 277C381FCC |
| 10de:0753 | 1565:340b | Nvidia     | MCP78S [GeForce 8200] Co-... | 5     |            | 52B394C153 |
| 10de:0aa3 | 1849:0aa3 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | 4DEAD658AD |
| 10de:0753 | 1025:0153 | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | 1F04FD556B |
| 10de:0753 | 1025:0228 | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | B2D5544528 |
| 10de:0753 | 103c:2a81 | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | 8BD9EDAADD |
| 10de:0753 | 1043:82e7 | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | FBFD1473BD |
| 10de:07da | 1462:7366 | Nvidia     | MCP73 Co-processor           | 3     |            | 3C83AF8B83 |
| 10de:0aa3 | 1043:83e2 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 1452DE25DA |
| 10de:03f4 | 1849:03f4 | Nvidia     | MCP61 SMU                    | 2     |            | B7F7A41C71 |
| 10de:0753 | 1025:0462 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 03A71DD3EB |
| 10de:07da | 10de:07d7 | Nvidia     | MCP73 Co-processor           | 2     |            | 7DA8928A0F |
| 10de:0aa3 | 1025:0168 | Nvidia     | MCP79 Co-processor           | 2     |            | 5443C8EC11 |
| 10de:0aa3 | 1462:7621 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | 1BA5C50EAD |
| 10de:0aa3 | 19da:0ae5 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | BA99DCB426 |
| 8086:19e2 | 8086:19e2 | Intel      | Atom Processor C3000 Seri... | 2     |            | 50B6A72C0C |
| 10de:0753 | 1019:1b67 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 4765DCDC47 |
| 10de:0753 | 1019:2646 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | D9ABAF941A |
| 10de:0753 | 1025:0227 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 3CF233B9C4 |
| 10de:0753 | 103c:2a9e | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | DF15AC1D7E |
| 10de:0753 | 1043:8332 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | E527269900 |
| 10de:0753 | 1462:6720 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | E2CB0B1767 |
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
| 10de:0aa3 | 103c:2a83 | Nvidia     | MCP79 Co-processor           | 1     | nvidia     | 226AA094E2 |
| 10de:0aa3 | 103c:2aa1 | Nvidia     | MCP79 Co-processor           | 1     |            | DF47C88DB6 |
| 10de:0aa3 | 1043:8356 | Nvidia     | MCP79 Co-processor           | 1     |            | E5CBBA8ADC |
| 10de:0aa3 | 1043:83f9 | Nvidia     | MCP79 Co-processor           | 1     | nvidia     | D4897620B7 |
| 10de:0aa3 | 105b:0d52 | Nvidia     | MCP79 Co-processor           | 1     |            | BA25C520E2 |
| 10de:0aa3 | 19da:a108 | Nvidia     | MCP79 Co-processor           | 1     |            | 7439F4F707 |
| 10de:0aa3 | 1b0a:000f | Nvidia     | MCP79 Co-processor           | 1     | nvidia     | F298AE57F6 |
| 10de:0aa3 | a0a0:0802 | Nvidia     | MCP79 Co-processor           | 1     |            | B778A6096A |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1c3a | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 535   | mei_me     | 13AF031E5E |
| 8086:1e3a | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 377   | mei_me     | 91535E2115 |
| 8086:8c3a | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 364   | mei_me     | 15E3126F2C |
| 8086:1c3a | 1458:1c3a | Intel      | 6 Series/C200 Series Chip... | 325   | mei_me     | EF2DAAC6D3 |
| 8086:1e3a | 1458:1c3a | Intel      | 7 Series/C216 Chipset Fam... | 274   | mei_me     | 5B67F6ED83 |
| 8086:a13a | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 236   | mei_me     | B8C562A7E5 |
| 8086:8c3a | 1458:1c3a | Intel      | 8 Series/C220 Series Chip... | 224   | mei_me     | 502C5D4B04 |
| 8086:a13a | 1458:1c3a | Intel      | 100 Series/C230 Series Ch... | 138   | mei_me     | 4015843475 |
| 8086:1c3a | 1849:1c3a | Intel      | 6 Series/C200 Series Chip... | 131   | mei_me     | 2A41C5495D |
| 8086:8c3a | 1849:8c3a | Intel      | 8 Series/C220 Series Chip... | 113   | mei_me     | 40DEE920A9 |
| 8086:8cba | 1043:8534 | Intel      | 9 Series Chipset Family M... | 105   | mei_me     | 1D2014DD53 |
| 8086:a2ba | 1458:1c3a | Intel      | 200 Series PCH CSME HECI #1  | 92    | mei_me     | 8F2ECB882C |
| 8086:a2ba | 1043:8694 | Intel      | 200 Series PCH CSME HECI #1  | 88    | mei_me     | 345BBA3C1F |
| 8086:1e3a | 1849:1e3a | Intel      | 7 Series/C216 Chipset Fam... | 84    | mei_me     | E1466EB2EC |
| 8086:8c3a | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 84    | mei_me     | FBE43FC861 |
| 8086:8cba | 1458:1c3a | Intel      | 9 Series Chipset Family M... | 83    | mei_me     | 984B3421C1 |
| 8086:3b64 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 55    | mei_me     | 3CDEB04C0D |
| 8086:a360 | 1458:1c3a | Intel      | Cannon Lake PCH HECI Cont... | 55    | mei_me     | E097415087 |
| 8086:a13a | 1849:a13a | Intel      | 100 Series/C230 Series Ch... | 53    | mei_me     | 0E4F08FCA3 |
| 8086:a360 | 1043:8694 | Intel      | Cannon Lake PCH HECI Cont... | 53    | mei_me     | 0B771C098E |
| 8086:1c3a | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 46    | mei_me     | 7FD884E502 |
| 8086:3b64 | 1458:3b64 | Intel      | 5 Series/3400 Series Chip... | 44    | mei_me     | E60C730AE2 |
| 8086:1d3a | 1043:84ef | Intel      | C600/X79 series chipset M... | 41    | mei_me     | 39F22D868E |
| 8086:1e3a | 1462:7758 | Intel      | 7 Series/C216 Chipset Fam... | 41    | mei_me     | 6DD3E491F5 |
| 8086:a2ba | 1849:a2ba | Intel      | 200 Series PCH CSME HECI #1  | 33    | mei_me     | 1BB0C8F064 |
| 8086:8cba | 1849:8cba | Intel      | 9 Series Chipset Family M... | 32    | mei_me     | 831FF4B7FC |
| 8086:8d3a | 1043:8600 | Intel      | C610/X99 series chipset M... | 32    | mei_me     | 021596F9B3 |
| 8086:1e3a | 1028:0577 | Intel      | 7 Series/C216 Chipset Fam... | 31    | mei_me     | 90FC9AFA3E |
| 8086:a2ba | 1043:872f | Intel      | 200 Series PCH CSME HECI #1  | 31    | mei_me     | 6AA8E0B9B0 |
| 8086:2e14 | 1028:027f | Intel      | 4 Series Chipset HECI Con... | 29    | mei_me     | 439AF540E7 |
| 8086:a13a | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 29    | mei_me     | 53CD422052 |
| 8086:1c3a | 1462:7680 | Intel      | 6 Series/C200 Series Chip... | 28    | mei_me     | E29AC96BDB |
| 8086:a360 | 1849:a360 | Intel      | Cannon Lake PCH HECI Cont... | 28    | mei_me     | B0161E1E77 |
| 8086:29b4 | 1028:0211 | Intel      | 82Q35 Express MEI Controller | 25    | mei_me     | E23742C63F |
| 8086:1c3a | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 23    | mei_me     | 2D378E81BE |
| 8086:29d4 | 103c:281e | Intel      | 82Q33 Express MEI Controller | 23    | mei_me     | 366E5CAC3F |
| 8086:2e14 | 103c:3048 | Intel      | 4 Series Chipset HECI Con... | 23    | mei_me     | 733B76A48E |
| 8086:1c3a | 103c:2abf | Intel      | 6 Series/C200 Series Chip... | 22    | mei_me     | 4AB14207F1 |
| 8086:2e14 | 1028:0420 | Intel      | 4 Series Chipset HECI Con... | 22    | mei_me     | 5151CB704B |
| 8086:29c4 | 8086:5044 | Intel      | 82G33/G31/P35/P31 Express... | 21    | mei_me     | 90F4B2CD0E |
| 8086:3b64 | 8086:0036 | Intel      | 5 Series/3400 Series Chip... | 21    | mei_me     | A57DCF32AA |
| 8086:2e14 | 1734:114c | Intel      | 4 Series Chipset HECI Con... | 20    | mei_me     | 9632357AEB |
| 8086:8c3a | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 20    | mei_me     | E6F6F65F88 |
| 8086:8c3a | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 20    | mei_me     | 01AC5D53D2 |
| 8086:a13a | 1462:7a15 | Intel      | 100 Series/C230 Series Ch... | 20    | mei_me     | 73BFD283E5 |
| 8086:1c3a | 1019:3190 | Intel      | 6 Series/C200 Series Chip... | 19    | mei_me     | 0709E8111B |
| 8086:29a4 | 8086:514d | Intel      | 82P965/G965 HECI Controller  | 18    | mei_me     | 43BE22F6DA |
| 8086:1e3a | 103c:3397 | Intel      | 7 Series/C216 Chipset Fam... | 17    | mei_me     | E68AA86510 |
| 8086:3b64 | 103c:2a9c | Intel      | 5 Series/3400 Series Chip... | 17    | mei_me     | FC9E4D61C1 |
| 8086:8c3a | 1028:0612 | Intel      | 8 Series/C220 Series Chip... | 17    | mei_me     | E7C7088138 |
| 8086:a2ba | 1043:873c | Intel      | 200 Series PCH CSME HECI #1  | 17    | mei_me     | 785E45F5BF |
| 8086:1c3a | 1462:7673 | Intel      | 6 Series/C200 Series Chip... | 16    | mei_me     | 35FFC61791 |
| 8086:1e3a | 103c:339a | Intel      | 7 Series/C216 Chipset Fam... | 16    | mei_me     | 2962B36D7E |
| 8086:29b4 | 103c:2818 | Intel      | 82Q35 Express MEI Controller | 16    | mei_me     | 844CB3BF90 |
| 8086:3b64 | 1462:7636 | Intel      | 5 Series/3400 Series Chip... | 16    | mei_me     | 48D4121155 |
| 8086:1c3a | 1028:047e | Intel      | 6 Series/C200 Series Chip... | 15    | mei_me     | 858ED45F37 |
| 14f1:2f20 | 14f1:200c | Conexan... | HSF 56k Data/Fax Modem       | 14    |            | 32F7F650B9 |
| 14f1:2f20 | 14f1:200f | Conexan... | HSF 56k Data/Fax Modem       | 14    |            | A309FDA4F4 |
| 14f1:2f30 | 14f1:20d5 | Conexan... | SoftV92 SpeakerPhone Soft... | 14    |            | 7DA787439E |
| 8086:1d3a | 1458:1c3a | Intel      | C600/X79 series chipset M... | 14    | mei_me     | 82A8163E58 |
| 8086:2994 | 103c:2801 | Intel      | 82Q963/Q965 HECI Controller  | 14    | mei_me     | 3A37DFD543 |
| 8086:2e14 | 103c:3034 | Intel      | 4 Series Chipset HECI Con... | 14    | mei_me     | A40772FC80 |
| 8086:8c3a | 1462:7816 | Intel      | 8 Series/C220 Series Chip... | 14    | mei_me     | 3686BB6AC0 |
| 8086:8c3a | 1462:7821 | Intel      | 8 Series/C220 Series Chip... | 14    | mei_me     | 542AEF8E5C |
| 8086:1c3a | 1025:0492 | Intel      | 6 Series/C200 Series Chip... | 13    | mei_me     | 42B0E234AF |
| 8086:1c3a | 1025:0589 | Intel      | 6 Series/C200 Series Chip... | 13    | mei_me     | 6F798AB348 |
| 8086:1c3a | 8086:1c3a | Intel      | 6 Series/C200 Series Chip... | 13    | mei_me     | F89781F320 |
| 8086:1d3a | 103c:1589 | Intel      | C600/X79 series chipset M... | 13    | mei_me     | 9D85C4CA60 |
| 8086:1e3a | 1462:7808 | Intel      | 7 Series/C216 Chipset Fam... | 13    | mei_me     | A08CC9782C |
| 8086:2e14 | 17aa:3048 | Intel      | 4 Series Chipset HECI Con... | 13    | mei_me     | 2BFF73F199 |
| 8086:1c3a | 1028:04f5 | Intel      | 6 Series/C200 Series Chip... | 12    | mei_me     | E7ACD0856E |
| 8086:1e3a | 1734:11d6 | Intel      | 7 Series/C216 Chipset Fam... | 12    | mei_me     | 086C06ABD4 |
| 8086:2e14 | 1028:0276 | Intel      | 4 Series Chipset HECI Con... | 12    | mei_me     | C05B5B48DE |
| 8086:3b64 | 8086:3b64 | Intel      | 5 Series/3400 Series Chip... | 12    | mei_me     | 94B8C23EEF |
| 8086:5a9a | 1849:5a9a | Intel      | Celeron N3350/Pentium N42... | 12    | mei_me     | 31B6C12A09 |
| 8086:8c3a | 1025:0750 | Intel      | 8 Series/C220 Series Chip... | 12    | mei_me     | 98191D61C3 |
| 8086:8c3a | 103c:18e7 | Intel      | 8 Series/C220 Series Chip... | 12    | mei_me     | 5A54F0AEAE |
| 8086:8cba | 1462:7850 | Intel      | 9 Series Chipset Family M... | 12    | mei_me     | 0579B2ED3A |
| 9710:9835 | 1000:0012 | MosChip... | PCI 9835 Multi-I/O Contro... | 12    | parport... | 01D5773983 |
| 11c1:0620 | 11c1:0620 | LSI        | Lucent V.92 Data/Fax Modem   | 11    |            | 56F0C1E96B |
| 8086:1c3a | 1028:0585 | Intel      | 6 Series/C200 Series Chip... | 11    | mei_me     | 7B0806B049 |
| 8086:8c3a | 1028:05b7 | Intel      | 8 Series/C220 Series Chip... | 11    | mei_me     | 6ED3187D7A |
| 8086:8c3a | 1462:7850 | Intel      | 8 Series/C220 Series Chip... | 11    | mei_me     | 0F3DCCFE4E |
| 8086:8c3a | 1734:11ea | Intel      | 8 Series/C220 Series Chip... | 11    | mei_me     | 84669A36B5 |
| 8086:a360 | 1025:1238 | Intel      | Cannon Lake PCH HECI Cont... | 11    | mei_me     | FF435389C9 |
| 8086:1c3a | 1019:7b97 | Intel      | 6 Series/C200 Series Chip... | 10    | mei_me     | F4081AB7E2 |
| 8086:1c3a | 1028:04aa | Intel      | 6 Series/C200 Series Chip... | 10    | mei_me     | 871C8E598B |
| 8086:1c3a | 103c:1495 | Intel      | 6 Series/C200 Series Chip... | 10    | mei_me     | D56240BFB5 |
| 8086:1c3a | 103c:1497 | Intel      | 6 Series/C200 Series Chip... | 10    | mei_me     | 51C0A64A32 |
| 8086:1c3a | 17aa:308c | Intel      | 6 Series/C200 Series Chip... | 10    | mei_me     | DE9CAC1509 |
| 8086:1c3a | 17aa:3653 | Intel      | 6 Series/C200 Series Chip... | 10    | mei_me     | 71C83542C5 |
| 8086:1c3a | 8086:2017 | Intel      | 6 Series/C200 Series Chip... | 10    | mei_me     | CA1BAF42C2 |
| 8086:1e3a | 1462:7752 | Intel      | 7 Series/C216 Chipset Fam... | 10    | mei_me     | 169E8E49D9 |
| 8086:29b4 | 8086:4f4a | Intel      | 82Q35 Express MEI Controller | 10    | mei_me     | 0A0C15A32B |
| 8086:2e14 | 103c:3646 | Intel      | 4 Series Chipset HECI Con... | 10    | mei_me     | B84B8A2AAE |
| 8086:8c3a | 1462:7823 | Intel      | 8 Series/C220 Series Chip... | 10    | mei_me     | 73D148603E |
| 8086:8d3a | 1028:0617 | Intel      | C610/X99 series chipset M... | 10    | mei_me     | 019BFC3983 |
| 8086:8d3a | 1458:7270 | Intel      | C610/X99 series chipset M... | 10    | mei_me     | AF58D23265 |
| 8086:a13a | 1462:7971 | Intel      | 100 Series/C230 Series Ch... | 10    | mei_me     | 88221EFDE1 |
| 14f1:10b6 | 14f1:10b6 | Conexan... | CX06834-11 HCF V.92 56k D... | 9     |            | 151D253025 |

### Dma controller (eisa dma) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0f06 | 8086:0f06 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | A968EF1DD8 |
| 8086:0f06 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | A211982E39 |
| 8086:0f40 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | A211982E39 |

### Docking station (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 168c:0829 | 1186:3a7c | Qualcom... | Docking Station              | 1     |            | 544F0D2A23 |

### Dpio module (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 012d:4d4c | 10b5:9080 |            | DPIO module                  | 1     |            | D88A4D7D31 |
| 10b5:9050 | ddd1:0001 | PLX Tec... | PCI <-> IOBus Bridge         | 1     |            | 117638721D |

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
| 1022:1456 | 1022:1456 | AMD        | Family 17h (Models 00h-0f... | 416   | ccp        | 5E8A739106 |
| 1022:15df | 1022:15df | AMD        | Family 17h (Models 10h-1f... | 132   |            | 564EB1FFE4 |
| 1022:1456 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 80    | ccp        | 172F18A294 |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 35    |            | 22A0854387 |
| 1022:15df | 1043:876b | AMD        | Family 17h (Models 10h-1f... | 30    |            | DE065F2CFC |
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 28    | mei_txe    | 08480474F8 |
| 8086:0f18 | 1849:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 25    | mei_txe    | F962D4BBF9 |
| 8086:0f18 | 8086:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 22    | mei_txe    | F0CD2A0468 |
| 1022:1486 | 1022:1486 | AMD        | Starship/Matisse Cryptogr... | 20    | ccp        | 2E60313B01 |
| 8086:0f18 | 1458:1c3a | Intel      | Atom Processor Z36xxx/Z37... | 19    | mei_txe    | 2AD366F4C0 |
| 1022:1486 | 1043:87c0 | AMD        | Starship/Matisse Cryptogr... | 13    | ccp        | 40061999CC |
| 8086:2298 | 1043:8534 | Intel      | Atom/Celeron/Pentium Proc... | 9     | mei_txe    | B4A53FAFC1 |
| 1022:1456 | 1462:7a38 | AMD        | Family 17h (Models 00h-0f... | 8     | ccp        | DCDA3B1F44 |
| 8086:0f18 | 1043:8534 | Intel      | Atom Processor Z36xxx/Z37... | 8     | mei_txe    | 0F8348D5A2 |
| 8086:2298 | 1458:1000 | Intel      | Atom/Celeron/Pentium Proc... | 8     | mei_txe    | C04DCDD5D7 |
| 8086:2298 | 1849:2298 | Intel      | Atom/Celeron/Pentium Proc... | 8     | mei_txe    | B41206F2FD |
| 1022:1537 | 1022:1537 | AMD        | Kabini/Mullins PSP-Platfo... | 7     | ccp        | 2F0C4ABC2E |
| 1022:15df | 1462:7a38 | AMD        | Family 17h (Models 10h-1f... | 7     |            | 924E886E1F |
| 1022:15df | 1462:7c02 | AMD        | Family 17h (Models 10h-1f... | 7     |            | AD51164983 |
| 1022:1456 | 1462:7c02 | AMD        | Family 17h (Models 00h-0f... | 5     | ccp        | 2E3A02EC4D |
| 8086:0f18 | 17aa:368d | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | E04CCB489C |
| 1022:1486 | 1462:7b89 | AMD        | Starship/Matisse Cryptogr... | 4     | ccp        | D85422E2C1 |
| 8086:0f18 | 1019:7ed4 | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 7B14499444 |
| 8086:0f18 | 1025:085e | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 5E3493C08F |
| 8086:0f18 | 105b:0db1 | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 177A7992A1 |
| 8086:0f18 | 8086:2055 | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 4C2CE64AE4 |
| 8086:2298 | 103c:821d | Intel      | Atom/Celeron/Pentium Proc... | 4     | mei_txe    | 1A5AE1397F |
| 8086:2298 | 1458:1c3a | Intel      | Atom/Celeron/Pentium Proc... | 4     | mei_txe    | 5B47EB5CFD |
| 8086:2298 | 17aa:30c9 | Intel      | Atom/Celeron/Pentium Proc... | 4     | mei_txe    | 0E09C1A76D |
| 1022:1456 | 1462:7b86 | AMD        | Family 17h (Models 00h-0f... | 3     | ccp        | 399E8E20C8 |
| 1022:15df | 1462:7b86 | AMD        | Family 17h (Models 10h-1f... | 3     |            | 8F20410642 |
| 1022:15df | 1462:7b87 | AMD        | Family 17h (Models 10h-1f... | 3     |            | 5BCFE2F1CE |
| 8086:0f18 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 3     | mei_txe    | A3EB79407F |
| 8086:2298 | 1019:9bef | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | BBED831835 |
| 8086:2298 | 1025:0953 | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | 1F72AE37E6 |
| 1022:1456 | 1462:7a40 | AMD        | Family 17h (Models 00h-0f... | 2     | ccp        | A215C93612 |
| 1022:1456 | 1462:7b85 | AMD        | Family 17h (Models 00h-0f... | 2     | ccp        | 053F507950 |
| 1022:1456 | 1462:7b89 | AMD        | Family 17h (Models 00h-0f... | 2     | ccp        | 01693744FC |
| 1022:1578 | 17aa:3100 | AMD        | Carrizo Platform Security... | 2     |            | 47B6DBB479 |
| 8086:0f18 | 1019:99ad | Intel      | Atom Processor Z36xxx/Z37... | 2     | mei_txe    | B4F7B429BF |
| 8086:0f18 | 1019:99cf | Intel      | Atom Processor Z36xxx/Z37... | 2     | mei_txe    | 341B8A2D15 |
| 8086:0f18 | 1565:310e | Intel      | Atom Processor Z36xxx/Z37... | 2     | mei_txe    | FCA939A959 |
| 8086:2298 | 1025:101c | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | FCC560CAF6 |
| 8086:2298 | 1025:1064 | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | 92C3E82D58 |
| 8086:2298 | 8086:2298 | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | 61357ECAED |
| 1022:1456 | 1019:9ce5 | AMD        | Family 17h (Models 00h-0f... | 1     | ccp        | 06776696F3 |
| 1022:1456 | 103c:8399 | AMD        | Family 17h (Models 00h-0f... | 1     | ccp        | 9440F6405B |
| 1022:1456 | 1462:7b90 | AMD        | Family 17h (Models 00h-0f... | 1     | ccp        | C7998D926E |
| 1022:1486 | 1462:7a38 | AMD        | Starship/Matisse Cryptogr... | 1     | ccp        | DCB98CB8E2 |
| 1022:1486 | 1462:7c02 | AMD        | Starship/Matisse Cryptogr... | 1     |            | E8131440F2 |
| 1022:1537 | 103c:21ef | AMD        | Kabini/Mullins PSP-Platfo... | 1     | ccp        | F194D347F2 |
| 1022:1537 | 103c:2b29 | AMD        | Kabini/Mullins PSP-Platfo... | 1     | ccp        | 455DDB0E74 |
| 1022:1537 | 103c:2b4f | AMD        | Kabini/Mullins PSP-Platfo... | 1     | ccp        | 188B0E90BC |
| 1022:15df | 103c:8626 | AMD        | Family 17h (Models 10h-1f... | 1     |            | 9BC7D6303D |
| 1022:15df | 1462:7b89 | AMD        | Family 17h (Models 10h-1f... | 1     |            | FE6EE1F7D7 |
| 1022:15df | 17aa:36e8 | AMD        | Family 17h (Models 10h-1f... | 1     |            | 78596220D1 |
| 1172:8004 |           | Altera     | Encryption controller        | 1     | altera_cvp | 0D2A7EFA14 |
| 8086:0f18 |           | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | F88234F842 |
| 8086:0f18 | 1019:99f3 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | 15B706B276 |
| 8086:0f18 | 1028:068d | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | 65A9CF6ADE |
| 8086:0f18 | 103c:2b15 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | 24DD32836D |
| 8086:0f18 | 103c:2b28 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | 70306922D3 |
| 8086:0f18 | 1071:0730 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | DAD78E5959 |
| 8086:0f18 | 1297:4019 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | 03AF7DBE17 |
| 8086:0f18 | 1458:1000 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | 8E5B085C94 |
| 8086:0f18 | 17aa:3688 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | A88328FDB9 |
| 8086:0f18 | 1b0a:017f | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | A303253DA2 |
| 8086:2298 | 1028:06f6 | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | 0784C6115A |
| 8086:2298 | 1028:07c1 | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | 9F4F497293 |

### Entertainment encryption device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:2082 | 1022:2082 | AMD        | Geode LX AES Security Block  | 1     | geode_r... | 6D9551F87E |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 104c:8024 | 1458:1000 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 401   | firewir... | A056C6C7D5 |
| 1106:3044 | 1043:81fe | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 377   | firewir... | 15EA243CBA |
| 11c1:5811 | 1043:8294 | LSI        | FW322/323 [TrueFire] 1394... | 106   | firewir... | 6949452F0E |
| 1106:3044 | 1458:1000 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 105   | firewir... | 0D6CA866B0 |
| 1106:3403 | 1043:8384 | VIA Tec... | VT6315 Series Firewire Co... | 103   | firewir... | DDF9D08A22 |
| 1106:3044 | 1106:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 94    | firewir... | 522AE798B9 |
| 1102:4001 | 1102:0010 | Creativ... | SB Audigy FireWire Port      | 75    | firewir... | F1B384A82B |
| 104c:8023 | 1043:808b | Texas I... | TSB43AB22A IEEE-1394a-200... | 58    | firewir... | 84495E0FB8 |
| 1106:3403 | 1849:3403 | VIA Tec... | VT6315 Series Firewire Co... | 50    | firewir... | A17808DA56 |
| 197b:2380 | 1043:8313 | JMicron... | IEEE 1394 Host Controller    | 31    | firewir... | 6FD74ADF75 |
| 1106:3403 | 1043:8374 | VIA Tec... | VT6315 Series Firewire Co... | 28    | firewir... | FF37EF634B |
| 104c:8023 | 1043:815b | Texas I... | TSB43AB22A IEEE-1394a-200... | 26    | firewir... | 49BC4A3291 |
| 11c1:5811 | 103c:2a6f | LSI        | FW322/323 [TrueFire] 1394... | 18    | firewir... | AC86A586B5 |
| 104c:823f |           | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 15    | firewir... | FA300CEB06 |
| 1106:3044 | 1043:808a | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 15    | firewir... | 741F8CFF05 |
| 1106:3403 | 103c:2a9c | VIA Tec... | VT6315 Series Firewire Co... | 15    | firewir... | A585EAEF35 |
| 11c1:5811 | 103c:1309 | LSI        | FW322/323 [TrueFire] 1394... | 15    | firewir... | 3F2B4E103F |
| 11c1:5811 | 103c:1589 | LSI        | FW322/323 [TrueFire] 1394... | 15    | firewir... | 9D85C4CA60 |
| 104c:8023 | 8086:514d | Texas I... | TSB43AB22A IEEE-1394a-200... | 14    | firewir... | 9E7FA667C7 |
| 104c:8023 | 8086:5044 | Texas I... | TSB43AB22A IEEE-1394a-200... | 13    | firewir... | 90F4B2CD0E |
| 104c:8024 | 1019:8056 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 13    | firewir... | F60B0BE33D |
| 1106:3044 | 1849:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 13    | firewir... | 2123239208 |
| 11c1:5811 | 11c1:5811 | LSI        | FW322/323 [TrueFire] 1394... | 12    | firewir... | 0A0C15A32B |
| 1106:3403 | 1106:3403 | VIA Tec... | VT6315 Series Firewire Co... | 11    | firewir... | 74374104D4 |
| 1106:3044 | 1106:0404 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 10    | firewir... | 451E46E979 |
| 1106:3044 | 17f2:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 8     | firewir... | F235798C9E |
| 11c1:5811 | 1028:5811 | LSI        | FW322/323 [TrueFire] 1394... | 8     | firewir... | 365B2DE3CD |
| 1033:00f2 | 1033:00f2 | NEC Com... | uPD72874 [Firewarden] IEE... | 7     | firewir... | B99C2286C9 |
| 104c:8023 | 1849:8023 | Texas I... | TSB43AB22A IEEE-1394a-200... | 7     | firewir... | 22D2F0F13E |
| 104c:823f | 3412:7856 | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 7     | firewir... | 8C51CE9858 |
| 1106:3044 | 1025:8010 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 7     | firewir... | A4BB2D6329 |
| 11bd:0015 | 11bd:0022 | Pinnacl... | FireWire IEEE1394            | 7     | firewir... | 12C434B6C4 |
| 11c1:5811 | 103c:158a | LSI        | FW322/323 [TrueFire] 1394... | 7     | firewir... | BAF893B7F3 |
| 104c:8025 | 1458:1000 | Texas I... | TSB82AA2 IEEE-1394b Link ... | 6     | firewir... | E7C73C81EC |
| 1106:3044 | 1043:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 6     | firewir... | F479FA880E |
| 1106:3044 | 1462:502d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 6     | firewir... | 3E9F34C334 |
| 11c1:5811 | 103c:2a34 | LSI        | FW322/323 [TrueFire] 1394... | 6     | firewir... | 32F7F650B9 |
| 11c1:5811 | 103c:2a66 | LSI        | FW322/323 [TrueFire] 1394... | 6     | firewir... | E843C895F8 |
| 11c1:5811 | 103c:2a6c | LSI        | FW322/323 [TrueFire] 1394... | 6     | firewir... | 6D882902AD |
| 11c1:5811 | 1734:1026 | LSI        | FW322/323 [TrueFire] 1394... | 6     | firewir... | 71F9B6C386 |
| 197b:2380 | 197b:2380 | JMicron... | IEEE 1394 Host Controller    | 6     | firewir... | 9D4E540AFF |
| 104c:8023 | 1028:021d | Texas I... | TSB43AB22A IEEE-1394a-200... | 5     | firewir... | EEC984CF36 |
| 104c:8023 | 10de:c55e | Texas I... | TSB43AB22A IEEE-1394a-200... | 5     | firewir... | 83BCB98979 |
| 104c:8024 |           | Texas I... | TSB43AB23 IEEE-1394a-2000... | 5     | firewir... | 870D0FE48E |
| 104c:8024 | 105b:0e0a | Texas I... | TSB43AB23 IEEE-1394a-2000... | 5     | firewir... | F052A27A1F |
| 104c:8025 |           | Texas I... | TSB82AA2 IEEE-1394b Link ... | 5     | firewir... | 0061EDE59F |
| 1106:3044 |           | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 5     | firewir... | A169B93D1F |
| 1106:3044 | 103c:2a24 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 5     | firewir... | 09E36FE223 |
| 1106:3044 | 103c:2a6d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 5     | firewir... | DC5CD07CA7 |
| 1106:3403 | 1025:024c | VIA Tec... | VT6315 Series Firewire Co... | 5     | firewir... | 2C202D97E7 |
| 11c1:5811 | 1028:8010 | LSI        | FW322/323 [TrueFire] 1394... | 5     | firewir... | A309FDA4F4 |
| 11c1:5811 | 103c:130a | LSI        | FW322/323 [TrueFire] 1394... | 5     | firewir... | F90C879481 |
| 11c1:5811 | 11bd:000e | LSI        | FW322/323 [TrueFire] 1394... | 5     | firewir... | 0A1BC31C2A |
| 1033:00e7 | 1033:00ce | NEC Com... | uPD72873 [Firewarden] IEE... | 4     | firewir... | 9C581DD7B1 |
| 1033:00f2 | 104d:811e | NEC Com... | uPD72874 [Firewarden] IEE... | 4     | firewir... | F1E5880584 |
| 104c:8023 | 8086:4f43 | Texas I... | TSB43AB22A IEEE-1394a-200... | 4     | firewir... | 6FC36C3EC6 |
| 104c:8024 | 1028:1000 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 4     | firewir... | 39BC0AD7B5 |
| 104c:8024 | 8086:544e | Texas I... | TSB43AB23 IEEE-1394a-2000... | 4     | firewir... | 59B8B5AAFD |
| 1106:3044 | 103c:2a61 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 4     | firewir... | E99F31CD33 |
| 1106:3044 | 1043:2a22 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 4     | firewir... | C1C7D412FB |
| 1106:3044 | 1462:238d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 4     | firewir... | 44726EA287 |
| 11c1:5811 | 103c:130b | LSI        | FW322/323 [TrueFire] 1394... | 4     | firewir... | 269249911A |
| 11c1:5811 | 103c:158b | LSI        | FW322/323 [TrueFire] 1394... | 4     | firewir... | 7A65E2F97F |
| 11c1:5811 | 103c:2a50 | LSI        | FW322/323 [TrueFire] 1394... | 4     | firewir... | FA15256774 |
| 11c1:5811 | 8086:2008 | LSI        | FW322/323 [TrueFire] 1394... | 4     | firewir... | A44CE70FF7 |
| 11c1:5811 | 8086:d701 | LSI        | FW322/323 [TrueFire] 1394... | 4     | firewir... | 0A74735DA6 |
| 197b:2380 | 1462:512d | JMicron... | IEEE 1394 Host Controller    | 4     | firewir... | 178DE664CA |
| 197b:2380 | 1462:522d | JMicron... | IEEE 1394 Host Controller    | 4     | firewir... | 148EE5FA31 |
| 104c:8023 |           | Texas I... | TSB43AB22A IEEE-1394a-200... | 3     | firewir... | 0C951A796F |
| 104c:8023 | 1028:01c0 | Texas I... | TSB43AB22A IEEE-1394a-200... | 3     | firewir... | CB363A3342 |
| 104c:8023 | 1028:026d | Texas I... | TSB43AB22A IEEE-1394a-200... | 3     | firewir... | 82F1FBFA97 |
| 104c:8023 | 147b:1084 | Texas I... | TSB43AB22A IEEE-1394a-200... | 3     | firewir... | 5C0FC04230 |
| 104c:8023 | 8086:4257 | Texas I... | TSB43AB22A IEEE-1394a-200... | 3     | firewir... | C137A7866B |
| 104c:8023 | 8086:4f53 | Texas I... | TSB43AB22A IEEE-1394a-200... | 3     | firewir... | 8A2DE6109C |
| 104c:8024 | 105b:0c9e | Texas I... | TSB43AB23 IEEE-1394a-2000... | 3     | firewir... | F9AE2DABF4 |
| 104c:8024 | 1b5b:010a | Texas I... | TSB43AB23 IEEE-1394a-2000... | 3     | firewir... | 45BCD84783 |
| 104c:8024 | 8086:4e53 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 3     | firewir... | 4EE2A84A23 |
| 104c:8025 | 1043:813c | Texas I... | TSB82AA2 IEEE-1394b Link ... | 3     | firewir... | 87F8B4B22A |
| 1106:3044 | 1019:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 3     | firewir... | 92A4661C26 |
| 1106:3044 | 103c:2a64 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 3     | firewir... | B48AA8562A |
| 1106:3044 | 103c:2a92 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 3     | firewir... | 49AE7CD372 |
| 1106:3044 | 1462:091d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 3     | firewir... | ED179AF34E |
| 1106:3044 | 1462:350d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 3     | firewir... | 92728C6648 |
| 1106:3044 | 1462:376d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 3     | firewir... | 6DEE7C879B |
| 1106:3044 | 1695:900e | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 3     | firewir... | 02CEB963E5 |
| 1106:3403 | 1025:0153 | VIA Tec... | VT6315 Series Firewire Co... | 3     | firewir... | 1F04FD556B |
| 1106:3403 | 1025:024d | VIA Tec... | VT6315 Series Firewire Co... | 3     | firewir... | 9E417BE017 |
| 1106:3403 | 1025:0250 | VIA Tec... | VT6315 Series Firewire Co... | 3     | firewir... | CB4BD052FC |
| 1106:3403 | 1462:576d | VIA Tec... | VT6315 Series Firewire Co... | 3     | firewir... | D7C5C9A383 |
| 1106:3403 | 1462:7616 | VIA Tec... | VT6315 Series Firewire Co... | 3     | firewir... | B9274F20A6 |
| 1106:3403 | 8086:0028 | VIA Tec... | VT6315 Series Firewire Co... | 3     | firewir... | 84ACE23538 |
| 1106:3403 | 8086:2001 | VIA Tec... | VT6315 Series Firewire Co... | 3     | firewir... | 34DBD882BE |
| 11bd:0015 | 11bd:0023 | Pinnacl... | FireWire IEEE1394            | 3     | firewir... | EBD8A5801D |
| 11c1:5811 | 103c:2a58 | LSI        | FW322/323 [TrueFire] 1394... | 3     | firewir... | 32AE4212DF |
| 11c1:5811 | 103c:2a5e | LSI        | FW322/323 [TrueFire] 1394... | 3     | firewir... | C4A328C606 |
| 11c1:5811 | 103c:2a81 | LSI        | FW322/323 [TrueFire] 1394... | 3     | firewir... | 8BD9EDAADD |
| 11c1:5811 | 8086:0024 | LSI        | FW322/323 [TrueFire] 1394... | 3     | firewir... | 363DBD925B |
| 11c1:5811 | 8086:1003 | LSI        | FW322/323 [TrueFire] 1394... | 3     | firewir... | 4E93B3E62B |
| 11c1:5811 | 8086:4356 | LSI        | FW322/323 [TrueFire] 1394... | 3     | firewir... | A8CD5A3679 |
| 197b:2380 | 1025:031f | JMicron... | IEEE 1394 Host Controller    | 3     | firewir... | 8770D9E3AD |

### Flash memory (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1524:0510 | 1524:0510 | ENE Tec... | CB710 Memory Card Reader ... | 2     | cb710      | 932FA70B29 |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1451 | 1022:1451 | AMD        | Family 17h (Models 00h-0f... | 305   |            | 5E8A739106 |
| 1002:5a23 | 1002:5a23 | AMD        | RD890S/RD990 I/O Memory M... | 150   |            | BE1C2E3D9C |
| 1022:1419 | 1022:1419 | AMD        | Family 15h (Models 10h-1f... | 123   |            | EAD3059AA0 |
| 1002:5a23 | 1462:7693 | AMD        | RD890S/RD990 I/O Memory M... | 57    |            | 9650DD9DCE |
| 1022:1423 | 1022:1423 | AMD        | Family 15h (Models 30h-3f... | 23    |            | 8FBC16EBFA |
| 1022:1419 | 1462:7721 | AMD        | Family 15h (Models 10h-1f... | 22    |            | 3486C89441 |
| 1022:1423 | 1462:7721 | AMD        | Family 15h (Models 30h-3f... | 21    |            | 743F3FF81C |
| 1022:1577 | 1022:1577 | AMD        | Family 15h (Models 60h-6f... | 17    |            | 41A165DAF5 |
| 1022:1423 | 1043:85cb | AMD        | Family 15h (Models 30h-3f... | 12    |            | 7C1CD714FB |
| 1022:1419 | 1462:7895 | AMD        | Family 15h (Models 10h-1f... | 8     |            | 20ED2C9B41 |
| 1002:5a23 | 1458:5000 | AMD        | RD890S/RD990 I/O Memory M... | 7     |            | 0D6CA866B0 |
| 1002:5a23 | 1462:7640 | AMD        | RD890S/RD990 I/O Memory M... | 7     |            | 54E2BF8542 |
| 1002:5a23 | 1462:7974 | AMD        | RD890S/RD990 I/O Memory M... | 6     |            | 3F7E1BB390 |
| 1022:1423 | 1462:7895 | AMD        | Family 15h (Models 30h-3f... | 5     |            | E1D561ABB4 |
| 1022:1419 | 1043:8526 | AMD        | Family 15h (Models 10h-1f... | 4     |            | 84CF4C391A |
| 1022:1419 | 1019:7c8d | AMD        | Family 15h (Models 10h-1f... | 3     |            | 8A37732F55 |
| 1022:1419 | 1025:070b | AMD        | Family 15h (Models 10h-1f... | 2     |            | F083D73A9E |
| 8086:19a2 | 8086:19a2 | Intel      | Atom Processor C3000 Seri... | 2     |            | 50B6A72C0C |
| 1022:1419 | 1462:7900 | AMD        | Family 15h (Models 10h-1f... | 1     |            | 985C8F6BB3 |
| 1022:1419 | 17aa:36a0 | AMD        | Family 15h (Models 10h-1f... | 1     |            | BA1A484E84 |
| 1022:1423 | 1462:7793 | AMD        | Family 15h (Models 30h-3f... | 1     |            | 54040FA02B |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0412 | 1458:d000 | Intel      | Xeon E3-1200 v3/4th Gen C... | 158   | i915       | 75C292C941 |
| 8086:0102 | 1043:844d | Intel      | 2nd Generation Core Proce... | 115   | i915       | 274EEA3275 |
| 8086:0412 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 101   | i915       | 1D2014DD53 |
| 8086:0102 | 1458:d000 | Intel      | 2nd Generation Core Proce... | 94    | i915       | B5CEB59A3F |
| 10de:128b | 1462:8c93 | Nvidia     | GK208B [GeForce GT 710]      | 89    | nouveau    | C51735EE45 |
| 10de:0a65 |           | Nvidia     | GT218 [GeForce 210]          | 87    | nouveau    | 11FC0E438A |
| 1002:9616 | 1043:8388 | AMD        | RS780L [Radeon 3000]         | 81    | radeon     | A898DD70F0 |
| 8086:0152 | 1458:d000 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 78    | i915       | BBFED70437 |
| 10de:0615 |           | Nvidia     | G92 [GeForce GTS 250]        | 77    | nvidia     | 82A50E872A |
| 10de:0640 |           | Nvidia     | G96C [GeForce 9500 GT]       | 73    | nouveau    | CED3C3C6BB |
| 10de:0de0 |           | Nvidia     | GF108 [GeForce GT 440]       | 72    | nouveau    | 843A450979 |
| 8086:29c2 | 1043:82b0 | Intel      | 82G33/G31 Express Integra... | 71    | i915       | E62DB6E4E2 |
| 10de:0622 |           | Nvidia     | G94 [GeForce 9600 GT]        | 70    | nvidia     | 69749F7B95 |
| 8086:2e32 | 1043:836d | Intel      | 4 Series Chipset Integrat... | 67    | i915       | 9AC5E13707 |
| 10de:0614 |           | Nvidia     | G92 [GeForce 9800 GT]        | 63    | nouveau    | 2BDA09406C |
| 8086:0402 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 61    | i915       | 63C2D20280 |
| 10de:0ca3 |           | Nvidia     | GT215 [GeForce GT 240]       | 60    | nvidia     | 7F477DA95D |
| 10de:1244 |           | Nvidia     | GF116 [GeForce GTX 550 Ti]   | 59    | nouveau    | 2535033ACD |
| 8086:0152 | 1043:844d | Intel      | Xeon E3-1200 v2/3rd Gen C... | 59    | i915       | 13AF031E5E |
| 8086:2772 | 1043:817a | Intel      | 82945G/GZ Integrated Grap... | 59    | i915       | 46027F2A96 |
| 8086:29c2 | 1849:29c2 | Intel      | 82G33/G31 Express Integra... | 57    | i915       | B64547F948 |
| 10de:03d6 | 1849:03d6 | Nvidia     | C61 [GeForce 7025 / nForc... | 54    | nouveau    | EC1F6C8A0B |
| 10de:0de1 |           | Nvidia     | GF108 [GeForce GT 430]       | 54    | nouveau    | 82A8163E58 |
| 10de:0f00 | 1569:0f00 | Nvidia     | GF108 [GeForce GT 630]       | 53    | nouveau    | 65629CCF94 |
| 10de:0fc6 | 1569:0fc6 | Nvidia     | GK107 [GeForce GTX 650]      | 53    | nouveau    | B9B80DB558 |
| 1002:67df | 1da2:e366 | AMD        | Ellesmere [Radeon RX 470/... | 50    | amdgpu     | 362C1B59B4 |
| 8086:0152 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 50    | i915       | B49F37B1D2 |
| 8086:1912 | 1043:8694 | Intel      | HD Graphics 530              | 49    | i915       | F6CCED2603 |
| 8086:5912 | 1043:8694 | Intel      | HD Graphics 630              | 49    | i915       | 30009478A9 |
| 1002:15dd | 1002:15dd | AMD        | Raven Ridge [Radeon Vega ... | 47    | amdgpu     | 564EB1FFE4 |
| 1002:9616 | 1458:d000 | AMD        | RS780L [Radeon 3000]         | 47    | radeon     | 4237BD1A34 |
| 8086:2e32 | 1458:d000 | Intel      | 4 Series Chipset Integrat... | 44    | i915       | 1B60792885 |
| 10de:0402 |           | Nvidia     | G84 [GeForce 8600 GT]        | 43    | nouveau    | B6FA3D93AF |
| 8086:2772 | 1458:d000 | Intel      | 82945G/GZ Integrated Grap... | 43    | i915       | 53B4651D22 |
| 8086:29c2 | 1458:d000 | Intel      | 82G33/G31 Express Integra... | 43    | i915       | 01B25A0DED |
| 1002:15dd | 1043:876b | AMD        | Raven Ridge [Radeon Vega ... | 41    | amdgpu     | 2FB35125E3 |
| 8086:0402 | 1458:d000 | Intel      | Xeon E3-1200 v3/4th Gen C... | 41    | i915       | 502C5D4B04 |
| 8086:041e | 1458:d000 | Intel      | 4th Generation Core Proce... | 41    | i915       | 9512600654 |
| 1002:68f9 | 174b:e164 | AMD        | Cedar [Radeon HD 5000/600... | 40    | radeon     | F0615F7666 |
| 10de:11c0 | 1569:11c0 | Nvidia     | GK106 [GeForce GTX 660]      | 40    | nvidia     | F1B384A82B |
| 10de:0a65 | 1462:8094 | Nvidia     | GT218 [GeForce 210]          | 38    | nvidia     | 9632357AEB |
| 8086:041e | 1043:8534 | Intel      | 4th Generation Core Proce... | 38    | i915       | 3D5203A376 |
| 10de:1380 | 1043:84bb | Nvidia     | GM107 [GeForce GTX 750 Ti]   | 37    | nouveau    | E82B5BBC50 |
| 10de:1c82 | 1462:8c96 | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 37    | nvidia     | 3AFE42946D |
| 8086:0102 | 1849:0102 | Intel      | 2nd Generation Core Proce... | 37    | i915       | 6D7E3AA70A |
| 8086:0152 | 1849:0152 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 37    | i915       | 39CDF41760 |
| 8086:0162 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 36    | i915       | 91535E2115 |
| 8086:5912 | 1458:d000 | Intel      | HD Graphics 630              | 36    | i915       | 8F2ECB882C |
| 10de:0641 |           | Nvidia     | G96C [GeForce 9400 GT]       | 35    | nvidia     | 868BBBBB38 |
| 10de:0a20 |           | Nvidia     | GT216 [GeForce GT 220]       | 35    | nouveau    | 5964794E61 |
| 10de:0dc4 |           | Nvidia     | GF106 [GeForce GTS 450]      | 34    | nvidia     | A96BD0FFB8 |
| 8086:0412 | 1849:0412 | Intel      | Xeon E3-1200 v3/4th Gen C... | 34    | i915       | C6B09D560F |
| 10de:0f00 | 1458:3544 | Nvidia     | GF108 [GeForce GT 630]       | 33    | nouveau    | 9F3A351654 |
| 10de:10c3 |           | Nvidia     | GT218 [GeForce 8400 GS Re... | 31    | nouveau    | 83592C8857 |
| 10de:11c0 | 1458:354e | Nvidia     | GK106 [GeForce GTX 660]      | 31    | nouveau    | 2373345C64 |
| 8086:0402 | 1462:7817 | Intel      | Xeon E3-1200 v3/4th Gen C... | 31    | i915       | 5697A7E164 |
| 10de:0322 |           | Nvidia     | NV34 [GeForce FX 5200]       | 29    | nouveau    | 9463E5625F |
| 10de:0fc1 | 1569:0fc1 | Nvidia     | GK107 [GeForce GT 640]       | 29    | nouveau    | ADD4F52268 |
| 8086:1912 | 1458:d000 | Intel      | HD Graphics 530              | 29    | i915       | 4015843475 |
| 10de:0421 |           | Nvidia     | G86 [GeForce 8500 GT]        | 28    | nouveau    | 69669B5BDD |
| 10de:0fc1 | 1043:83f3 | Nvidia     | GK107 [GeForce GT 640]       | 28    | nouveau    | 70EA4F97BF |
| 10de:0fc6 | 1458:3553 | Nvidia     | GK107 [GeForce GTX 650]      | 28    | nouveau    | AAF32079F9 |
| 10de:1c82 | 10de:1c82 | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 28    | nvidia     | A9F8B1AD35 |
| 10de:1d01 | 1462:8c98 | Nvidia     | GP108 [GeForce GT 1030]      | 28    | nvidia     | E3B6CE369A |
| 1002:6759 | 174b:e193 | AMD        | Turks PRO [Radeon HD 6570... | 26    | radeon     | 9EE4B80FE3 |
| 10de:0a65 | 1043:848e | Nvidia     | GT218 [GeForce 210]          | 26    | nouveau    | 9DF2C0E0DD |
| 10de:0f00 | 1043:8400 | Nvidia     | GF108 [GeForce GT 630]       | 26    | nouveau    | 90F55C011B |
| 10de:1040 |           | Nvidia     | GF119 [GeForce GT 520]       | 26    | nouveau    | C1E924B844 |
| 10de:1245 |           | Nvidia     | GF116 [GeForce GTS 450 Re... | 26    | nouveau    | A644A3A3AD |
| 8086:0162 | 1849:0162 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 26    | i915       | 84FFC0A890 |
| 1002:6758 | 174b:e194 | AMD        | Turks XT [Radeon HD 6670/... | 25    | radeon     | B656825800 |
| 1002:6779 | 174b:e164 | AMD        | Caicos [Radeon HD 6450/74... | 25    | radeon     | 2902DCE4BA |
| 10de:0392 |           | Nvidia     | G73 [GeForce 7600 GS]        | 25    | nouveau    | AA25C8DFEE |
| 10de:0a65 | 1043:83f4 | Nvidia     | GT218 [GeForce 210]          | 25    | nouveau    | C3FE050E13 |
| 10de:0a65 | 1458:3525 | Nvidia     | GT218 [GeForce 210]          | 25    | nouveau    | E198A17869 |
| 10de:0f02 | 1462:8a9f | Nvidia     | GF108 [GeForce GT 730]       | 25    | nouveau    | BF8E7A5595 |
| 8086:0102 | 1043:84ca | Intel      | 2nd Generation Core Proce... | 25    | i915       | 58EC049231 |
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 25    | i915       | 08480474F8 |
| 8086:2e32 | 1462:7592 | Intel      | 4 Series Chipset Integrat... | 25    | i915       | E5A422358F |
| 8086:3e92 | 1043:8694 | Intel      | UHD Graphics 630 (Desktop)   | 25    | i915       | A3871B3E32 |
| 10de:0393 |           | Nvidia     | G73 [GeForce 7300 GT]        | 24    | nouveau    | 462A7600C8 |
| 10de:0fc6 | 1462:8a96 | Nvidia     | GK107 [GeForce GTX 650]      | 24    | nouveau    | 9E65D54AC9 |
| 10de:1380 | 1043:84be | Nvidia     | GM107 [GeForce GTX 750 Ti]   | 24    | nvidia     | A66E24484E |
| 10de:1380 | 1458:362d | Nvidia     | GM107 [GeForce GTX 750 Ti]   | 24    | nvidia     | B34F330B92 |
| 8086:2e12 | 1028:0420 | Intel      | 4 Series Chipset Integrat... | 24    | i915       | 5151CB704B |
| 8086:2e13 | 1028:0420 | Intel      | 4 Series Chipset Integrat... | 24    |            | 5151CB704B |
| 10de:104a | 1462:809f | Nvidia     | GF119 [GeForce GT 610]       | 23    | nouveau    | 68DB872DF1 |
| 10de:1187 | 1043:847a | Nvidia     | GK104 [GeForce GTX 760]      | 23    | nvidia     | 598C1572B3 |
| 10de:1c82 | 1462:3351 | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 23    | nvidia     | 805E960AA9 |
| 8086:1902 | 1043:8694 | Intel      | HD Graphics 510              | 23    | i915       | 86457D8FC0 |
| 8086:29c2 | 1462:7529 | Intel      | 82G33/G31 Express Integra... | 23    | i915       | 09DEBC5B93 |
| 8086:3e92 | 1458:d000 | Intel      | UHD Graphics 630 (Desktop)   | 23    | i915       | 41795F04DE |
| 1002:6779 | 174b:a004 | AMD        | Caicos [Radeon HD 6450/74... | 22    | radeon     | 50C16B189C |
| 1002:67df | 1682:c580 | AMD        | Ellesmere [Radeon RX 470/... | 22    | amdgpu     | FC98CE50E1 |
| 8086:0162 | 1458:d000 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 22    | i915       | AD56492FB5 |
| 8086:0f31 | 1849:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 22    | i915       | F962D4BBF9 |
| 8086:2e32 | 1849:2e32 | Intel      | 4 Series Chipset Integrat... | 22    | i915       | 6FDB8DFE61 |
| 1002:6613 | 174b:e263 | AMD        | Oland PRO [Radeon R7 240/... | 21    | radeon     | B472118C5A |
| 10de:03d0 | 1043:8234 | Nvidia     | C61 [GeForce 6150SE nForc... | 21    | nouveau    | D3A9A22C8A |
| 10de:0f02 | 1458:365b | Nvidia     | GF108 [GeForce GT 730]       | 21    | nouveau    | A5A715C21F |

### I/o card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10e8:80d8 |           | Applied... | PCI-7200 40MB/s 32-channe... | 1     |            | 3864E6C70F |

### Input device controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1102:7002 | 1102:0020 | Creativ... | SB Live! Game Port           | 91    | emu10k1_gp | A4AE24CFF8 |
| 1102:7003 | 1102:0040 | Creativ... | SB Audigy Game Port          | 61    | emu10k1_gp | 992938DD51 |
| 1102:7003 | 1102:0060 | Creativ... | SB Audigy Game Port          | 15    | emu10k1_gp | F1B384A82B |
| 1319:0802 | 1319:1319 | Fortemedia | Xwave QS3000A [FM801 game... | 6     | fm801_gp   | 6AB359DC43 |
| 1102:7004 | 1102:1003 | Creativ... | [SB Live! Value] Input de... | 1     | emu10k1_gp | B7C8E17F50 |
| 1102:7005 | 1102:1002 | Creativ... | SB Audigy LS Game Port       | 1     | emu10k1_gp | A8AFE9E221 |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 174   |            | 5BCFE2F1CE |
| 1022:1451 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 162   |            | 4ED3A4A663 |
| 1022:1481 | 1022:1481 | AMD        | Starship/Matisse IOMMU       | 23    |            | 2E60313B01 |
| 1022:1481 | 1043:87c0 | AMD        | Starship/Matisse IOMMU       | 15    |            | 40061999CC |
| 1022:1451 | 1462:7a38 | AMD        | Family 17h (Models 00h-0f... | 8     |            | DCDA3B1F44 |
| 1022:1451 | 1028:07ee | AMD        | Family 17h (Models 00h-0f... | 7     |            | C708B6ADE4 |
| 1022:1451 | 1462:7c02 | AMD        | Family 17h (Models 00h-0f... | 5     |            | 2E3A02EC4D |
| 1022:1423 | 103c:2215 | AMD        | Family 15h (Models 30h-3f... | 4     |            | 40C1857EB1 |
| 1022:1481 | 1462:7b89 | AMD        | Starship/Matisse IOMMU       | 4     |            | D85422E2C1 |
| 1022:1423 | 1025:0904 | AMD        | Family 15h (Models 30h-3f... | 3     |            | 86472BF81E |
| 1022:1451 | 1462:7b86 | AMD        | Family 17h (Models 00h-0f... | 3     |            | 399E8E20C8 |
| 1022:1577 | 1043:8719 | AMD        | Family 15h (Models 60h-6f... | 3     |            | 1BB86FEDE4 |
| 1022:1419 | 1019:7c90 | AMD        | Family 15h (Models 10h-1f... | 2     |            | FFB74FCE84 |
| 1022:1419 | 103c:1850 | AMD        | Family 15h (Models 10h-1f... | 2     |            | 898F2B7197 |
| 1022:1419 | 1462:7793 | AMD        | Family 15h (Models 10h-1f... | 2     |            | 30D335A9A4 |
| 1022:1451 | 1028:089a | AMD        | Family 17h (Models 00h-0f... | 2     |            | 6F6209A41E |
| 1022:1451 | 1462:7a40 | AMD        | Family 17h (Models 00h-0f... | 2     |            | A215C93612 |
| 1022:1451 | 1462:7b85 | AMD        | Family 17h (Models 00h-0f... | 2     |            | 053F507950 |
| 1022:1451 | 1462:7b89 | AMD        | Family 17h (Models 00h-0f... | 2     |            | 01693744FC |
| 1022:1577 | 17aa:3100 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 47B6DBB479 |
| 1002:5a23 | 1462:7893 | AMD        | RD890S/RD990 I/O Memory M... | 1     |            | 837F3B9280 |
| 1022:1419 | 1019:9ac9 | AMD        | Family 15h (Models 10h-1f... | 1     |            | 9DA00E895E |
| 1022:1419 | 103c:2215 | AMD        | Family 15h (Models 10h-1f... | 1     |            | 1B3213CA06 |
| 1022:1423 | 1019:99d3 | AMD        | Family 15h (Models 30h-3f... | 1     |            | CFCBE45B0D |
| 1022:1423 | 1019:9a62 | AMD        | Family 15h (Models 30h-3f... | 1     |            | 06FB58E8EE |
| 1022:1423 | 1019:9ac9 | AMD        | Family 15h (Models 30h-3f... | 1     |            | BED1921035 |
| 1022:1423 | 1462:7903 | AMD        | Family 15h (Models 30h-3f... | 1     |            | EADCB61E9F |
| 1022:1423 | 17aa:36a0 | AMD        | Family 15h (Models 30h-3f... | 1     |            | 0D36C8246A |
| 1022:1451 | 1019:9ce5 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 06776696F3 |
| 1022:1451 | 1462:7b90 | AMD        | Family 17h (Models 00h-0f... | 1     |            | C7998D926E |
| 1022:1481 | 1462:7a38 | AMD        | Starship/Matisse IOMMU       | 1     |            | DCB98CB8E2 |
| 1022:1481 | 1462:7c02 | AMD        | Starship/Matisse IOMMU       | 1     |            | E8131440F2 |
| 1022:1481 | 1462:7c35 | AMD        | Starship/Matisse IOMMU       | 1     |            | 9F56AFFC3E |
| 8086:1f16 | 1849:1f16 | Intel      | Atom processor C2000 RCEC    | 1     |            | E398D38584 |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816c | 1019:81ea | Realtek... | Virtual IPMI                 | 1     |            | 06FB58E8EE |
| 10ec:816c | 1025:1248 | Realtek... | Virtual IPMI                 | 1     |            | 688751760E |
| 10ec:816c | 103c:8626 | Realtek... | Virtual IPMI                 | 1     |            | 9BC7D6303D |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 103c:3302 | 103c:3305 | Hewlett... | Integrated Lights-Out Sta... | 5     | ipmi_si    | DF7A5AC424 |
| 10ec:816c | 1458:e000 | Realtek... | Virtual IPMI                 | 4     | ipmi_si    | 02A7674592 |
| 10ec:816c | 1734:1178 | Realtek... | Virtual IPMI                 | 3     | ipmi_si    | F9847F8DC5 |
| 10ec:816c | 17aa:3089 | Realtek... | Virtual IPMI                 | 3     | ipmi_si    | D9A1939AB2 |
| 10ec:816c | 1025:078b | Realtek... | Virtual IPMI                 | 1     |            | 087F924E20 |
| 10ec:816c | 1043:8578 | Realtek... | Virtual IPMI                 | 1     | ipmi_si    | C248800623 |
| 10ec:816c | 10ec:8168 | Realtek... | Virtual IPMI                 | 1     | ipmi_si    | E505745421 |
| 10ec:816c | 10ec:816c | Realtek... | Virtual IPMI                 | 1     |            | 71F9B6C386 |
| 10ec:816c | 17aa:30b2 | Realtek... | Virtual IPMI                 | 1     | ipmi_si    | 36635F76F9 |
| 8086:108e | 8086:0000 | Intel      | 82573E KCS (Active Manage... | 1     | ipmi_si    | 1960567A11 |

### Isdn adapter (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1244:0a00 | 1244:0a00 | AVM        | A1 ISDN [Fritz]              | 2     | fcpci      | 74E6692069 |
| 1244:0e00 | 1244:0e00 | AVM        | Fritz!Card PCI v2.0 ISDN     | 2     | fcpci      | 5A1BBCBC9E |
| 1397:2bd0 | 1397:2bd0 | Cologne... | ISDN network controller [... | 1     | hfcpci     | 83A7C8B23F |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a121 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 238   |            | B8C562A7E5 |
| 10de:03f5 | 1849:03eb | Nvidia     | MCP61 Memory Controller      | 223   |            | EC1F6C8A0B |
| 10de:03e2 | 1849:03e2 | Nvidia     | MCP61 Host Bridge            | 207   |            | EC1F6C8A0B |
| 8086:a121 | 1458:5001 | Intel      | 100 Series/C230 Series Ch... | 138   |            | 4015843475 |
| 10de:03f5 | 1458:0c11 | Nvidia     | MCP61 Memory Controller      | 118   |            | 53DB8982F5 |
| 8086:a36f | 8086:7270 | Intel      | Cannon Lake PCH Shared SRAM  | 107   |            | E097415087 |
| 8086:a2a1 | 1458:5001 | Intel      | 200 Series/Z370 Chipset F... | 92    |            | 8F2ECB882C |
| 8086:a2a1 | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 88    |            | 345BBA3C1F |
| 10de:03ea | 1043:8234 | Nvidia     | MCP61 Memory Controller      | 82    |            | F3B22A675A |
| 10de:03f5 | 1043:8234 | Nvidia     | MCP61 Memory Controller      | 82    |            | F3B22A675A |
| 10de:03ea | 10de:cb84 | Nvidia     | MCP61 Memory Controller      | 78    |            | C7E1B7CEC0 |
| 10de:03e2 | 1043:83a4 | Nvidia     | MCP61 Host Bridge            | 77    |            | A6BD4DA213 |
| 10de:03f5 | 1043:83a4 | Nvidia     | MCP61 Memory Controller      | 77    |            | A6BD4DA213 |
| 10de:03ea | 1458:5001 | Nvidia     | MCP61 Memory Controller      | 66    |            | B1D7110D4D |
| 10de:005e | 1043:815a | Nvidia     | CK804 Memory Controller      | 60    |            | FD8F010178 |
| 8086:a121 | 1849:a121 | Intel      | 100 Series/C230 Series Ch... | 53    |            | 0E4F08FCA3 |
| 8086:a36f | 1043:8694 | Intel      | Cannon Lake PCH Shared SRAM  | 53    |            | 0B771C098E |
| 10de:03e2 | 1458:5001 | Nvidia     | MCP61 Host Bridge            | 52    |            | 53DB8982F5 |
| 10de:03f5 | 1462:7309 | Nvidia     | MCP61 Memory Controller      | 46    |            | 93E77F9DC3 |
| 10de:03f5 | 1565:3407 | Nvidia     | MCP61 Memory Controller      | 38    |            | 1004AD3220 |
| 10de:0444 | 1462:7369 | Nvidia     | MCP65 Memory Controller      | 38    |            | 9DF2C0E0DD |
| 10de:0445 | 1462:7369 | Nvidia     | MCP65 Memory Controller      | 38    |            | 9DF2C0E0DD |
| 10de:0568 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 38    |            | AFF249E34F |
| 10de:0751 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 38    |            | AFF249E34F |
| 10de:0754 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 38    |            | AFF249E34F |
| 10de:0369 | 1043:8239 | Nvidia     | MCP55 Memory Controller      | 36    |            | 44E3D900F5 |
| 8086:a2a1 | 1849:a2a1 | Intel      | 200 Series/Z370 Chipset F... | 33    |            | 1BB0C8F064 |
| 10de:03a9 |           | Nvidia     | C55 Memory Controller        | 31    |            | 15EA243CBA |
| 10de:03aa |           | Nvidia     | C55 Memory Controller        | 31    |            | 15EA243CBA |
| 10de:03ab |           | Nvidia     | C55 Memory Controller        | 31    |            | 15EA243CBA |
| 10de:03b4 |           | Nvidia     | C55 Memory Controller        | 31    |            | 15EA243CBA |
| 10de:03bc |           | Nvidia     | C55 Memory Controller        | 31    |            | 15EA243CBA |
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
| 8086:a121 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 29    |            | 53CD422052 |
| 8086:a36f | 1849:a36f | Intel      | Cannon Lake PCH Shared SRAM  | 28    |            | B0161E1E77 |
| 10de:0568 | 1849:0568 | Nvidia     | MCP78S [GeForce 8200] Mem... | 26    |            | 41F3167FB7 |
| 10de:0751 | 1849:0751 | Nvidia     | MCP78S [GeForce 8200] Mem... | 26    |            | 41F3167FB7 |
| 10de:0754 | 1849:0754 | Nvidia     | MCP78S [GeForce 8200] Mem... | 26    |            | 41F3167FB7 |
| 10de:03ea | 103c:2a6c | Nvidia     | MCP61 Memory Controller      | 21    |            | 6D882902AD |
| 10de:03f5 | 103c:2a6c | Nvidia     | MCP61 Memory Controller      | 21    |            | 6D882902AD |
| 10de:0270 | 1043:81c0 | Nvidia     | MCP51 Host Bridge            | 20    |            | A26BD26890 |
| 10de:0568 |           | Nvidia     | MCP78S [GeForce 8200] Mem... | 20    |            | 1F04FD556B |
| 10de:0751 | 10de:cb84 | Nvidia     | MCP78S [GeForce 8200] Mem... | 20    |            | 1F04FD556B |
| 8086:a121 | 1462:7a15 | Intel      | 100 Series/C230 Series Ch... | 20    |            | 73BFD283E5 |
| 10de:0369 | 1462:7250 | Nvidia     | MCP55 Memory Controller      | 19    |            | C862E6269E |
| 10de:0272 | 1043:81c0 | Nvidia     | MCP51 Memory Controller 0    | 18    |            | A26BD26890 |
| 10de:027e | 1043:81c0 | Nvidia     | C51 Memory Controller 2      | 18    |            | A26BD26890 |
| 10de:027f | 1043:81c0 | Nvidia     | C51 Memory Controller 3      | 18    |            | A26BD26890 |
| 10de:02f0 | 1043:81c0 | Nvidia     | C51 Host Bridge              | 18    |            | A26BD26890 |
| 10de:02f8 | 1043:81c0 | Nvidia     | C51 Memory Controller 5      | 18    |            | A26BD26890 |
| 10de:02f9 | 1043:81c0 | Nvidia     | C51 Memory Controller 4      | 18    |            | A26BD26890 |
| 10de:02fe | 1043:81c0 | Nvidia     | C51 Memory Controller 1      | 18    |            | A26BD26890 |
| 10de:02ff | 1043:81c0 | Nvidia     | C51 Host Bridge              | 18    |            | A26BD26890 |
| 10de:0270 | 1043:81bc | Nvidia     | MCP51 Host Bridge            | 17    |            | 15EA243CBA |
| 10de:0369 | 1043:cb84 | Nvidia     | MCP55 Memory Controller      | 17    |            | 064DD1CCBF |
| 10de:03ea | 1565:3407 | Nvidia     | MCP61 Memory Controller      | 17    |            | C67AE8B7E3 |
| 8086:a2a1 | 1043:873c | Intel      | 200 Series/Z370 Chipset F... | 17    |            | 785E45F5BF |
| 10de:03ea | 1849:03ea | Nvidia     | MCP61 Memory Controller      | 16    |            | 00931DD0B2 |
| 10de:03f5 | 1462:7597 | Nvidia     | MCP61 Memory Controller      | 16    |            | 2DC1AE73B8 |
| 10de:0754 | 1458:5001 | Nvidia     | MCP78S [GeForce 8200] Mem... | 16    |            | 9D06F70055 |
| 10de:005e | 1458:5000 | Nvidia     | CK804 Memory Controller      | 15    |            | 872FEB1CA3 |
| 10de:027e | 10de:027e | Nvidia     | C51 Memory Controller 2      | 15    |            | 064DD1CCBF |
| 10de:027f | 10de:027f | Nvidia     | C51 Memory Controller 3      | 15    |            | 064DD1CCBF |
| 10de:02f8 | 10de:02f8 | Nvidia     | C51 Memory Controller 5      | 15    |            | 064DD1CCBF |
| 10de:02f9 | 10de:02f9 | Nvidia     | C51 Memory Controller 4      | 15    |            | 064DD1CCBF |
| 10de:02fa | 1043:81c0 | Nvidia     | C51 Memory Controller 0      | 15    |            | A26BD26890 |
| 10de:02fa | 10de:02fa | Nvidia     | C51 Memory Controller 0      | 15    |            | 064DD1CCBF |
| 10de:02fe | 10de:02fe | Nvidia     | C51 Memory Controller 1      | 15    |            | 064DD1CCBF |
| 10de:02ff | 10de:02ff | Nvidia     | C51 Host Bridge              | 15    |            | 064DD1CCBF |
| 10de:0369 | 1458:5001 | Nvidia     | MCP55 Memory Controller      | 15    |            | 0CCA59B833 |
| 10de:03ea | 1019:2601 | Nvidia     | MCP61 Memory Controller      | 13    |            | F60B0BE33D |
| 10de:03ea | 103c:2a99 | Nvidia     | MCP61 Memory Controller      | 13    |            | 0BC668FE41 |
| 10de:03f5 | 1019:2601 | Nvidia     | MCP61 Memory Controller      | 13    |            | F60B0BE33D |
| 10de:03f5 | 103c:2a99 | Nvidia     | MCP61 Memory Controller      | 13    |            | 0BC668FE41 |
| 10de:0270 | 1458:5001 | Nvidia     | MCP51 Host Bridge            | 12    |            | 6027467F3B |
| 10de:0272 | 1458:0264 | Nvidia     | MCP51 Memory Controller 0    | 12    |            | 6027467F3B |
| 10de:0444 | 1458:5001 | Nvidia     | MCP65 Memory Controller      | 12    |            | 8AB20AB60D |
| 10de:0445 | 1458:0c11 | Nvidia     | MCP65 Memory Controller      | 12    |            | 8AB20AB60D |
| 10de:0272 | 1043:81bc | Nvidia     | MCP51 Memory Controller 0    | 11    |            | 15EA243CBA |
| 10de:0547 | 1019:2609 | Nvidia     | MCP67 Memory Controller      | 11    |            | 57FB4562E5 |
| 10de:0547 | 1043:82b3 | Nvidia     | MCP67 Memory Controller      | 11    |            | AD4F65C1BD |
| 10de:0568 | 1043:82e2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 11    |            | 007691F448 |
| 10de:0751 | 1043:82e2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 11    |            | 007691F448 |
| 10de:0754 | 1043:82e2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 11    |            | 007691F448 |
| 10de:07c8 | 10de:cb73 | Nvidia     | MCP73 Memory Controller      | 11    |            | 8996CEBF5B |
| 10de:07cb | 10de:cb73 | Nvidia     | nForce 610i/630i memory c... | 11    |            | 8996CEBF5B |
| 10de:07cd | 10de:cb73 | Nvidia     | nForce 610i/630i memory c... | 11    |            | 8996CEBF5B |
| 10de:07ce | 10de:cb73 | Nvidia     | nForce 610i/630i memory c... | 11    |            | 8996CEBF5B |

### Modem (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 11c1:044c | 11c1:044c | LSI        | LT WinModem                  | 13    |            | 461D79E9EB |
| 1057:3052 | 1057:3020 | Motorola   | SM56 Data Fax Modem          | 10    |            | F60B0BE33D |
| 1106:3068 |           | VIA Tec... | AC'97 Modem Controller       | 9     | snd_via... | D20509CA50 |
| 134d:7892 | 134d:0001 | PCTel      | HSP MicroModem 56            | 4     | serial     | 6C9B4F5E0B |
| 8086:1040 | 8086:1000 | Intel      | 536EP Data Fax Modem         | 4     |            | 1263C61735 |
| 1106:3068 | 1019:0c04 | VIA Tec... | AC'97 Modem Controller       | 3     | snd_via... | 7AA84DA312 |
| 1039:7013 | 104d:8128 | Silicon... | AC'97 Modem Controller       | 1     | snd_int... | 72A578315E |
| 1057:3052 | 1631:3034 | Motorola   | SM56 Data Fax Modem          | 1     |            | B7CEC1644D |
| 1106:3068 | 1019:2122 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 25BB71984B |
| 11c1:0440 | 11c1:0440 | LSI        | 56k WinModem                 | 1     |            | 6B2E5020C2 |
| 11c1:0449 | 1468:0410 | LSI        | L56xM+S [Mars-2] WinModem... | 1     |            | A8A13EFBA0 |
| 11c1:044e | 11c1:044e | LSI        | LT WinModem                  | 1     |            | 6203763CC5 |
| 11c1:044e | 1235:044e | LSI        | LT WinModem                  | 1     |            | 3D74179CB7 |
| 11c1:044e | 13e0:0401 | LSI        | LT WinModem                  | 1     |            | E9ACA9663F |
| 11c1:0450 | 144f:1515 | LSI        | LT WinModem                  | 1     |            | 32D5B1A614 |
| 1543:3052 | 1543:3000 | SILICON... | Intel 537 [Winmodem]         | 1     |            | 75C969D54B |
| 163c:3052 | 14fe:0005 | Smart Link | SmartLink SmartPCI562 56K... | 1     | serial     | 9939882441 |
| 2000:2800 | 163c:2800 | Smart Link | SmartPCI2800 V.92 PCI Sof... | 1     |            | 9DEE04D2CB |
| 2003:8800 | 16ef:2800 | Smart Link | LM-I56N                      | 1     |            | 8B4AE6CF41 |
| 2003:8800 | 1801:2800 | Smart Link | LM-I56N                      | 1     |            | 413AE4FF4F |
| 8086:1080 | 1028:1000 | Intel      | FA82537EP 56K V.92 Data/F... | 1     | serial     | 0E73DD68E2 |
| 8086:1080 | 8086:1000 | Intel      | FA82537EP 56K V.92 Data/F... | 1     | serial     | 6DF95E6042 |

### Multimedia (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 0002:8290 | 0004:0000 |            |                              | 1     |            | 95D420F37F |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 109e:0878 |           | Brooktree  | Bt878 Audio Capture          | 18    |            | 80274F5B0C |
| 11bd:bede | 11bd:0022 | Pinnacl... | AV/DV Studio Capture Card    | 9     |            | 12C434B6C4 |
| 109e:0878 | 1461:0003 | Brooktree  | Bt878 Audio Capture          | 8     | snd_bt87x  | 48378AE22B |
| 1131:7160 | 1461:1455 | Philips... | SAA7160                      | 8     |            | 8D0B9127EF |
| 1131:7231 | 5ace:8000 | Philips... | SAA7231                      | 8     |            | FA070462FC |
| 1022:15e2 | 1022:15e2 | AMD        | Raven/Raven2/FireFlight/R... | 5     | snd_pci... | 1AC9EAC22B |
| 109e:0878 | 0070:13eb | Brooktree  | Bt878 Audio Capture          | 5     | snd_bt87x  | A43E9D5913 |
| 1131:7164 | 0070:8851 | Philips... | SAA7164                      | 5     | saa7164    | 54C8F90B14 |
| 1131:7231 | 1461:1400 | Philips... | SAA7231                      | 5     |            | 4F99536247 |
| 1022:15e2 | 103c:8433 | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | D1E501DD66 |
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
| 1022:15e2 | 103c:8434 | AMD        | Raven/Raven2/FireFlight/R... | 2     |            | E2E650868B |
| 109e:0878 | 11bd:0012 | Brooktree  | Bt878 Audio Capture          | 2     | snd_bt87x  | AB36F565A4 |
| 109e:0878 | 1461:0004 | Brooktree  | Bt878 Audio Capture          | 2     |            | F2B7867CAA |
| 1131:7160 | 1461:0855 | Philips... | SAA7160                      | 2     |            | BBDA8BED86 |
| 1131:7160 | 1461:0955 | Philips... | SAA7160                      | 2     |            | D6813FBC7C |
| 1131:7160 | 1461:1855 | Philips... | SAA7160                      | 2     |            | FA070462FC |
| 1131:7160 | 1ae4:0700 | Philips... | SAA7160                      | 2     |            | E9FCA3B9C8 |
| 1131:7231 | 12ab:0763 | Philips... | SAA7231                      | 2     |            | 6F6F611F59 |
| 1131:7231 | 16be:0008 | Philips... | SAA7231                      | 2     |            | 1BA5C50EAD |
| 1131:7231 | 5ace:8150 | Philips... | SAA7231                      | 2     |            | 8603D5BDF5 |
| 11bd:bede | 11bd:0023 | Pinnacl... | AV/DV Studio Capture Card    | 2     |            | EBD8A5801D |
| 14e4:1615 | 14e4:1615 | Broadco... | BCM70015 Video Decoder [C... | 2     |            | 6F7935090C |
| 14f1:8804 | 0070:6906 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     |            | BCEE476272 |
| 14f1:8804 | 1822:0023 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     |            | AB36F565A4 |
| 1822:4e35 | 153b:1178 | Twinhan... | Mantis DTV PCI Bridge Con... | 2     | mantis     | B7812DD3C1 |
| 1822:4e35 | 1ae4:0002 | Twinhan... | Mantis DTV PCI Bridge Con... | 2     | mantis     | CCB302179F |
| 1822:4e35 | 1ae4:0003 | Twinhan... | Mantis DTV PCI Bridge Con... | 2     | mantis     | DA1E5854E0 |
| 8086:0f38 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 2     |            | F9B255CBBC |
| dd01:0003 | dd01:0030 | Digital... | Octopus DVB Adapter          | 2     | ddbridge   | B4A53FAFC1 |
| 0002:8290 | 107d:2609 |            | Multimedia controller        | 1     |            | 95D420F37F |
| 1002:4d51 | 1002:b041 | AMD        | Unified AVStream Driver      | 1     |            | 2CF316774E |
| 1002:ac12 | 12ab:0003 | AMD        | Theater HD T507 (DVB-T) T... | 1     |            | 0921BB94E0 |
| 1002:ad18 | 1682:ad18 | AMD        | Multimedia controller        | 1     |            | 3108FE53D3 |
| 102b:8350 | 102b:9000 | Matrox ... | Matrox Multimedia controller | 1     |            | B3EE98B7CC |
| 1057:3410 | 1057:ffff | Motorola   | DSP56361 Digital Signal P... | 1     |            | 16A7890585 |
| 1057:3410 | 11af:eed2 | Motorola   | DSP56361 Digital Signal P... | 1     |            | 16A7890585 |
| 1057:3410 | 11af:eee1 | Motorola   | DSP56361 Digital Signal P... | 1     |            | 16A7890585 |
| 109e:0878 | 0070:ff02 | Brooktree  | Bt878 Audio Capture          | 1     |            | 84495E0FB8 |
| 109e:0878 | 1047:f331 | Brooktree  | Bt878 Audio Capture          | 1     |            | 444FFBC8A6 |
| 109e:0878 | 107d:6607 | Brooktree  | Bt878 Audio Capture          | 1     |            | 6027467F3B |
| 109e:0878 | 1461:0001 | Brooktree  | Bt878 Audio Capture          | 1     |            | E8072B6F3A |
| 109e:0878 | 1461:0002 | Brooktree  | Bt878 Audio Capture          | 1     |            | A22609B54B |
| 109e:0878 | 1554:4011 | Brooktree  | Bt878 Audio Capture          | 1     | snd_bt87x  | EB0AE92869 |
| 109e:0878 | 800a:763d | Brooktree  | Bt878 Audio Capture          | 1     |            | 08DCF9AA49 |
| 109e:0878 | 800b:763d | Brooktree  | Bt878 Audio Capture          | 1     |            | 08DCF9AA49 |
| 109e:0878 | 800c:763d | Brooktree  | Bt878 Audio Capture          | 1     |            | 08DCF9AA49 |
| 109e:0878 | 800d:763d | Brooktree  | Bt878 Audio Capture          | 1     |            | 08DCF9AA49 |
| 109e:0878 | aa96:45bb | Brooktree  | Bt878 Audio Capture          | 1     | vfio_pci   | E287F6207B |
| 109e:0878 | bd11:1200 | Brooktree  | Bt878 Audio Capture          | 1     | snd_bt87x  | B0C20B14D8 |
| 109e:0878 | bd11:4100 | Brooktree  | Bt878 Audio Capture          | 1     |            | C20B184FC3 |
| 10b5:9056 | 1a0e:006f | PLX Tec... | PCI9056 32-bit 66MHz PCI ... | 1     |            | C6B09D560F |
| 10b5:9056 | 1a0e:0073 | PLX Tec... | PCI9056 32-bit 66MHz PCI ... | 1     | Dta        | A9ADFE83C5 |
| 1131:7160 | 1461:0455 | Philips... | SAA7160                      | 1     |            | F85808C04C |
| 1131:7160 | 1461:0655 | Philips... | SAA7160                      | 1     |            | 58A8ECB02A |
| 1131:7160 | 1461:7561 | Philips... | SAA7160                      | 1     |            | A010F0A8F5 |
| 1131:7160 | 1461:7992 | Philips... | SAA7160                      | 1     |            | 3ACD33354F |
| 1131:7160 | 185b:e750 | Philips... | SAA7160                      | 1     |            | 891F7E03D0 |
| 1131:7160 | 6281:0001 | Philips... | SAA7160                      | 1     | saa716x... | CFCEC9BCBB |
| 1131:7160 | 6928:0001 | Philips... | SAA7160                      | 1     |            | 8C8F8EFAB1 |
| 1131:7160 | 6928:0002 | Philips... | SAA7160                      | 1     |            | 016B4BAE90 |
| 1131:7160 | e517:12ab | Philips... | SAA7160                      | 1     |            | 786069DE60 |
| 1131:7160 | e519:12ab | Philips... | SAA7160                      | 1     |            | 786069DE60 |
| 1131:7162 | 11bd:0101 | Philips... | SAA7162                      | 1     |            | 003EB89135 |
| 1131:7164 | 0070:8953 | Philips... | SAA7164                      | 1     | saa7164    | 035CB4B9FD |
| 1131:7164 | 0070:f111 | Philips... | SAA7164                      | 1     | saa7164    | 2AC18DE610 |
| 1131:7164 | 0070:f120 | Philips... | SAA7164                      | 1     | saa7164    | 0D6CA866B0 |
| 1131:7164 | 185b:e900 | Philips... | SAA7164                      | 1     | saa7164    | 87483BBE5F |
| 11bd:0040 | 11bd:0045 | Pinnacl... | Royal TS Function 1          | 1     |            | FF0A7B1FC8 |
| 11bd:0041 | 11bd:0045 | Pinnacl... | RoyalTS Function 2           | 1     |            | FF0A7B1FC8 |
| 11bd:0042 | 11bd:0045 | Pinnacl... | Royal TS Function 3          | 1     |            | FF0A7B1FC8 |
| 127e:0010 | 127e:0010 | Winnov,... | Videum 1000 Plus             | 1     |            | 37BC71433C |
| 14b5:0200 |           | Creamware  | Scope                        | 1     |            | 783F215994 |
| 14b5:0300 |           | Creamware  | Pulsar                       | 1     |            | 783F215994 |
| 14b5:0600 | 14b5:0600 | Creamware  | Pulsar2                      | 1     |            | 783F215994 |
| 14e4:1612 | 14e4:2612 | Broadcom   | BCM70012 Video Decoder [C... | 1     |            | 71EDB71D27 |
| 14f1:8002 | 14f1:0084 | Conexan... | Conexant Multimedia contr... | 1     |            | 380140EB8D |
| 14f1:8803 | 185b:e000 | Conexan... | CX2388x TV Capture Chip      | 1     |            | 5B85C2F248 |
| 14f1:8804 | 0070:1402 | Conexan... | CX23880/1/2/3 PCI Video a... | 1     |            | 186479593C |
| 14f1:8804 | 0070:9202 | Conexan... | CX23880/1/2/3 PCI Video a... | 1     |            | DFF9C11E07 |
| 1745:2100 | 1043:48b0 | ViXS Sy... | XCode 2100 Series            | 1     |            | AD1D92439F |
| 1797:6805 |           | Intersi... | HV4000 series DVR card       | 1     |            | B2C845B843 |
| 1797:6805 | 1797:6804 | Intersi... | HV4000 series DVR card       | 1     |            | B2C845B843 |
| 1797:6814 | 000a:6814 | Intersi... | TW6816 multimedia video c... | 1     |            | 91371F93D7 |
| 1797:6815 | 000a:6815 | Intersi... | TW6816 multimedia video c... | 1     |            | 91371F93D7 |
| 1797:6816 | 000a:6816 | Intersi... | TW6816 multimedia video c... | 1     |            | 91371F93D7 |
| 1797:6817 | 000a:6817 | Intersi... | TW6816 multimedia video c... | 1     |            | 91371F93D7 |
| 1797:6869 |           | Intersi... | C968 PCIe SD Capture Device  | 1     | tw686x     | A31109BBA8 |
| 1822:4e35 | 1822:0014 | Twinhan... | Mantis DTV PCI Bridge Con... | 1     | mantis     | 175019DBD8 |
| 1822:4e35 | 1822:0048 | Twinhan... | Mantis DTV PCI Bridge Con... | 1     |            | CB1A0D9CDD |
| 1a00:0001 | 1a00:0001 |            | Multimedia controller        | 1     |            | 16A7890585 |

### Multiport serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1fd4:1999 | 1fd4:0002 | SUNIX      | Multiport serial controller  | 5     | serial     | D577562AE7 |
| 135c:0170 | 135c:0170 | Quatech    | QSCLP-100                    | 1     | serial     | 05DF269988 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8168 | 1458:e000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2308  | r8169      | A056C6C7D5 |
| 10ec:8168 | 1849:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 842   | r8169      | C0D7396586 |
| 10ec:8168 | 1043:8505 | Realtek... | RTL8111/8168/8411 PCI Exp... | 792   | r8169      | 13AF031E5E |
| 10ec:8168 | 1043:8432 | Realtek... | RTL8111/8168/8411 PCI Exp... | 633   | r8169      | 3A7D6AD8A5 |
| 10ec:8139 | 10ec:8139 | Realtek... | RTL-8100/8101L/8139 PCI F... | 416   | 8139too... | 967BB75CBB |
| 10ec:8168 | 1043:8677 | Realtek... | RTL8111/8168/8411 PCI Exp... | 404   | r8169      | A3871B3E32 |
| 10ec:8168 | 1043:8554 | Realtek... | RTL8111/8168/8411 PCI Exp... | 322   | r8169      | 535FBF3562 |
| 10ec:8168 | 1043:83a3 | Realtek... | RTL8111/8168/8411 PCI Exp... | 288   | r8169      | E40B76E473 |
| 1969:1048 | 1043:8226 | Qualcom... | Attansic L1 Gigabit Ethernet | 247   | atl1       | 60EC6F52F9 |
| 10ec:8168 | 1043:859e | Realtek... | RTL8111/8168/8411 PCI Exp... | 178   | r8169      | 22A0854387 |
| 1106:3106 | 1186:1405 | VIA Tec... | VT6105/VT6106S [Rhine-III]   | 174   | via_rhine  | A5C61E8040 |
| 8086:15b8 | 1043:8672 | Intel      | Ethernet Connection (2) I... | 174   | e1000e     | 345BBA3C1F |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 156   | r8169      | DAEDE56DC8 |
| 1969:1083 | 1458:e000 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 149   | atl1c      | AD56492FB5 |
| 10ec:8136 | 1849:8136 | Realtek... | RTL810xE PCI Express Fast... | 142   | r8169      | 62DE4DA398 |
| 11ab:4364 | 1043:81f8 | Marvell... | 88E8056 PCI-E Gigabit Eth... | 132   | sky2       | 49BC4A3291 |
| 10ec:8168 | 1043:82c6 | Realtek... | RTL8111/8168/8411 PCI Exp... | 128   | r8169      | DDF9D08A22 |
| 8086:15a1 | 1043:85c4 | Intel      | Ethernet Connection (2) I... | 107   | e1000e     | 1D2014DD53 |
| 10ec:8169 | 10ec:8169 | Realtek... | RTL8169 PCI Gigabit Ether... | 105   | r8169      | 4015843475 |
| 1969:1091 | 1458:e000 | Qualcom... | AR8161 Gigabit Ethernet      | 100   | alx        | A5E90F38C5 |
| 10ec:8168 | 7470:3468 | Realtek... | RTL8111/8168/8411 PCI Exp... | 94    | r8169      | 41795F04DE |
| 1969:1026 | 1043:8304 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 94    | atl1e      | B315D4391D |
| 10ec:8168 | 1043:81aa | Realtek... | RTL8111/8168/8411 PCI Exp... | 93    | r8169      | 53D2EF8D02 |
| 8086:15b8 | 1458:e000 | Intel      | Ethernet Connection (2) I... | 86    | e1000e     | 8F2ECB882C |
| 10ec:8136 | 1043:8347 | Realtek... | RTL810xE PCI Express Fast... | 84    | r8169      | B9B80DB558 |
| 10ec:8168 | 1462:7817 | Realtek... | RTL8111/8168/8411 PCI Exp... | 84    | r8169      | FBE43FC861 |
| 11ab:4320 | 1043:811a | Marvell... | 88E8001 Gigabit Ethernet ... | 79    | skge       | 49BC4A3291 |
| 1969:2048 | 1043:8233 | Qualcom... | Attansic L2 Fast Ethernet    | 71    | atl2       | E643B8ED58 |
| 8086:15b8 | 1849:15b8 | Intel      | Ethernet Connection (2) I... | 62    | e1000e     | 1BB0C8F064 |
| 10ec:8168 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 61    | r8169      | 13AF031E5E |
| 10ec:8168 | 1043:8367 | Realtek... | RTL8111/8168/8411 PCI Exp... | 60    | r8169      | 8FE7FBADA1 |
| 10ec:8168 | 1462:7721 | Realtek... | RTL8111/8168/8411 PCI Exp... | 60    | r8169      | 743F3FF81C |
| 8086:153b | 1458:e000 | Intel      | Ethernet Connection I217-V   | 59    | e1000e     | 984B3421C1 |
| 10ec:8168 | 1025:8000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 57    | r8169      | 7C1A93E022 |
| 10ec:8136 | 10ec:0123 | Realtek... | RTL810xE PCI Express Fast... | 56    | r8169      | F89781F320 |
| 1969:1026 | 1043:8226 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 56    | atl1e      | A5A715C21F |
| 1186:4300 | 1186:4300 | D-Link ... | DGE-528T Gigabit Ethernet... | 55    | r8169      | F85FDA7AF0 |
| 10ec:8167 | 1458:e000 | Realtek... | RTL-8110SC/8169SC Gigabit... | 52    | r8169      | F176A74B87 |
| 1969:1063 | 1043:83fe | Qualcom... | AR8131 Gigabit Ethernet      | 52    | atl1c      | A898DD70F0 |
| 1969:1063 | 1458:e000 | Qualcom... | AR8131 Gigabit Ethernet      | 52    | atl1c      | 9928EAEA06 |
| 1969:2062 | 1849:2062 | Qualcom... | AR8152 v2.0 Fast Ethernet    | 52    | atl1c      | 6FDB8DFE61 |
| 1969:10a1 | 1043:8587 | Qualcom... | QCA8171 Gigabit Ethernet     | 51    | alx        | E5540CB969 |
| 10ec:8168 | 1043:8385 | Realtek... | RTL8111/8168/8411 PCI Exp... | 48    | r8169      | 5D250ED2A6 |
| 8086:153b | 1043:859f | Intel      | Ethernet Connection I217-V   | 46    | e1000e     | E203D0B513 |
| 11ab:4362 | 1043:8142 | Marvell... | 88E8053 PCI-E Gigabit Eth... | 45    | sky2       | 83592C8857 |
| 10ec:8168 | 1462:7693 | Realtek... | RTL8111/8168/8411 PCI Exp... | 44    | r8169      | 9650DD9DCE |
| 13f0:0200 | 13f0:0201 | Sundanc... | IC Plus IP100A Integrated... | 44    | sundance   | 9D0BA3BCD7 |
| 14e4:16b1 | 1849:96b1 | Broadco... | NetLink BCM57781 Gigabit ... | 44    | tg3        | 107280E5A9 |
| 1969:1083 | 1849:1083 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 44    | atl1c      | 2A41C5495D |
| 10ec:8168 | 1019:811e | Realtek... | RTL8111/8168/8411 PCI Exp... | 43    | r8169      | 9091074F4A |
| 1969:1026 | 1043:831c | Qualcom... | AR8121/AR8113/AR8114 Giga... | 42    | atl1e      | B56C2B2E60 |
| 10ec:8168 | 1462:7758 | Realtek... | RTL8111/8168/8411 PCI Exp... | 39    | r8169      | 6DD3E491F5 |
| 1969:e091 | 1458:e000 | Qualcom... | Killer E220x Gigabit Ethe... | 39    | alx        | 75C292C941 |
| 1969:10a1 | 1849:10a1 | Qualcom... | QCA8171 Gigabit Ethernet     | 38    | alx        | FFBFB70794 |
| 10ec:8168 | 1462:369c | Realtek... | RTL8111/8168/8411 PCI Exp... | 37    | r8169      | 9DF2C0E0DD |
| 10ec:8139 | 11f6:8139 | Realtek... | RTL-8100/8101L/8139 PCI F... | 36    | 8139too... | B6FA3D93AF |
| 10ec:8167 | 1043:820d | Realtek... | RTL-8110SC/8169SC Gigabit... | 36    | r8169      | 39DD00A6C2 |
| 1969:1091 | 1043:8507 | Qualcom... | AR8161 Gigabit Ethernet      | 36    | alx        | 1F99995749 |
| 14e4:167a | 1028:01da | Broadco... | NetXtreme BCM5754 Gigabit... | 33    | tg3        | B54A538301 |
| 1969:1083 | 1043:847e | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 33    | atl1c      | 4083A82BD5 |
| 10de:0760 | 1043:82f2 | Nvidia     | MCP77 Ethernet               | 32    | forcedeth  | AFF249E34F |
| 8086:107c | 8086:1376 | Intel      | 82541PI Gigabit Ethernet ... | 31    | e1000      | 4D1157B020 |
| 8086:153b | 1849:153b | Intel      | Ethernet Connection I217-V   | 31    | e1000e     | 40DEE920A9 |
| 10ec:8139 | 1849:8139 | Realtek... | RTL-8100/8101L/8139 PCI F... | 30    | 8139too... | 46CBFD5EE9 |
| 1969:1073 | 1458:e000 | Qualcom... | AR8151 v1.0 Gigabit Ethernet | 29    | atl1c      | A63447351B |
| 10ec:8168 | 1462:7996 | Realtek... | RTL8111/8168/8411 PCI Exp... | 28    | r8169      | 53CD422052 |
| 8086:15bc | 1458:e000 | Intel      | Ethernet Connection (7) I... | 28    | e1000e     | E097415087 |
| 10ec:8136 | 1019:8348 | Realtek... | RTL810xE PCI Express Fast... | 27    | r8169      | C409A64286 |
| 10de:0760 | 1849:0760 | Nvidia     | MCP77 Ethernet               | 26    | forcedeth  | 41F3167FB7 |
| 10ec:8136 | 1043:83d3 | Realtek... | RTL810xE PCI Express Fast... | 26    | r8169      | FE93074CAE |
| 10ec:8168 | 1462:7788 | Realtek... | RTL8111/8168/8411 PCI Exp... | 26    | r8169      | 33654FE678 |
| 8086:15a1 | 1849:15a1 | Intel      | Ethernet Connection (2) I... | 26    | e1000e     | CF6B1C24E5 |
| 10ec:8136 | 1458:e000 | Realtek... | RTL810xE PCI Express Fast... | 25    | r8169      | 787674672C |
| 10ec:8168 | 1462:7599 | Realtek... | RTL8111/8168/8411 PCI Exp... | 24    | r8169      | F0615F7666 |
| 10ec:8168 | 1462:7641 | Realtek... | RTL8111/8168/8411 PCI Exp... | 24    | r8169      | 56E11FA07C |
| 14e4:1677 | 1028:01ad | Broadco... | NetXtreme BCM5751 Gigabit... | 24    | tg3        | 21AE6DBDF0 |
| 8086:153a | 1028:05a4 | Intel      | Ethernet Connection I217-LM  | 24    | e1000e     | E6F6F65F88 |
| 10ec:8168 | 1462:7850 | Realtek... | RTL8111/8168/8411 PCI Exp... | 23    | r8169      | 0579B2ED3A |
| 10ec:8168 | 1462:7a34 | Realtek... | RTL8111/8168/8411 PCI Exp... | 23    | r8169      | A8017F0E83 |
| 10ec:8168 | 8086:d608 | Realtek... | RTL8111/8168/8411 PCI Exp... | 23    | r8169      | 7F477DA95D |
| 11ab:4320 | 1458:e000 | Marvell... | 88E8001 Gigabit Ethernet ... | 23    | skge       | 585D8319DA |
| 8086:15bc | 1043:8672 | Intel      | Ethernet Connection (7) I... | 23    | e1000e     | A548B448E7 |
| 10ec:8139 | 1043:8109 | Realtek... | RTL-8100/8101L/8139 PCI F... | 22    | 8139too... | FBA4BBCEB5 |
| 10ec:8168 | 103c:2abf | Realtek... | RTL8111/8168/8411 PCI Exp... | 22    | r8169      | 4AB14207F1 |
| 10ec:8168 | 1462:7529 | Realtek... | RTL8111/8168/8411 PCI Exp... | 22    | r8169      | 3DCC4EE3D0 |
| 1969:2048 | 1019:2048 | Qualcom... | Attansic L2 Fast Ethernet    | 22    | atl2       | 03C909A2C4 |
| 10ec:8136 | 1043:8136 | Realtek... | RTL810xE PCI Express Fast... | 21    | r8169      | E64F670E53 |
| 10ec:8136 | 1565:2308 | Realtek... | RTL810xE PCI Express Fast... | 21    | r8169      | 2BDA09406C |
| 10ec:8168 | 1462:7a15 | Realtek... | RTL8111/8168/8411 PCI Exp... | 21    | r8169      | 73BFD283E5 |
| 14e4:1681 | 1028:0293 | Broadco... | NetXtreme BCM5761 Gigabit... | 21    | tg3        | FD20ECEEC0 |
| 8086:109a | 1043:81c2 | Intel      | 82573L Gigabit Ethernet C... | 21    | e1000e     | 3B64DC358E |
| 8086:153a | 103c:1998 | Intel      | Ethernet Connection I217-LM  | 21    | e1000e     | 01AC5D53D2 |
| 10ec:8168 | 103c:2a6f | Realtek... | RTL8111/8168/8411 PCI Exp... | 20    | r8169      | AC86A586B5 |
| 10ec:8168 | 1462:7a38 | Realtek... | RTL8111/8168/8411 PCI Exp... | 20    | r8169      | 924E886E1F |
| 1969:2062 | 1019:8152 | Qualcom... | AR8152 v2.0 Fast Ethernet    | 20    | atl1c      | F4081AB7E2 |
| 10ec:8136 | 1462:7788 | Realtek... | RTL810xE PCI Express Fast... | 19    | r8169      | 7FD884E502 |
| 10ec:8139 | 1019:8139 | Realtek... | RTL-8100/8101L/8139 PCI F... | 19    | 8139too... | 4050B2D0D1 |
| 14e4:1681 | 103c:3047 | Broadco... | NetXtreme BCM5761 Gigabit... | 19    | tg3        | 70E4F247FC |
| 8086:15bc | 1849:15bc | Intel      | Ethernet Connection (7) I... | 19    | e1000e     | B0161E1E77 |
| 10ec:8136 | 1462:7592 | Realtek... | RTL810xE PCI Express Fast... | 18    | r8169      | 2553EF6468 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 168c:0032 | 168c:3118 | Qualcom... | AR9485 Wireless Network A... | 95    | ath9k      | 4F4314B0B4 |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 85    | iwlwifi    | 6DF8CD9DDD |
| 168c:002e | 168c:30a4 | Qualcom... | AR9287 Wireless Network A... | 77    | ath9k      | AFDF4A3A9C |
| 168c:002d | 168c:0301 | Qualcom... | AR9227 Wireless Network A... | 70    | ath9k      | E722D70419 |
| 168c:002d | 168c:0300 | Qualcom... | AR9227 Wireless Network A... | 53    | ath9k      | A4AE24CFF8 |
| 1814:3060 | 1186:3c04 | Ralink     | RT3060 Wireless 802.11n 1... | 46    | rt2800pci  | 61CA6E9A9A |
| 168c:0030 | 168c:3112 | Qualcom... | AR93xx Wireless Network A... | 44    | ath9k      | A17808DA56 |
| 1814:5360 | 1186:3c05 | Ralink     | RT5360 Wireless 802.11n 1... | 35    | rt2800pci  | 82EF187455 |
| 10ec:8176 | 1043:84b5 | Realtek... | RTL8188CE 802.11b/g/n WiF... | 32    | rtl8192ce  | B0F374A7DC |
| 10ec:8185 | 10ec:8225 | Realtek... | RTL-8185 IEEE 802.11a/b/g... | 31    | rtl818x... | A1B106DC08 |
| 14e4:43a0 | 14e4:0619 | Broadco... | BCM4360 802.11ac Wireless... | 30    | wl         | C7312AA534 |
| 1814:0302 | 1186:3a71 | Ralink     | RT2561/RT61 rev B 802.11g    | 30    | rt61pci    | AAF32079F9 |
| 8086:2526 | 8086:0014 | Intel      | Wireless-AC 9260             | 29    | iwlwifi    | 053F507950 |
| 10ec:b822 | 1043:8746 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 26    | r8822be    | 345BBA3C1F |
| 168c:0013 | 1186:3a13 | Qualcom... | AR5212/5213/2414 Wireless... | 26    | ath5k      | F8D6F32091 |
| 168c:002b | 168c:30a1 | Qualcom... | AR9285 Wireless Network A... | 25    | ath9k      | 3833787EFA |
| 168c:0032 | 1043:850d | Qualcom... | AR9485 Wireless Network A... | 25    | ath9k      | 01D5773983 |
| 8086:08b1 | 8086:4070 | Intel      | Wireless 7260                | 25    | iwlwifi    | B41206F2FD |
| 10ec:818b | 10ec:8196 | Realtek... | RTL8192EE PCIe Wireless N... | 24    | rtl8192ee  | 9BD54A84F0 |
| 1814:0302 | 1186:3c09 | Ralink     | RT2561/RT61 rev B 802.11g    | 23    | rt61pci    | F9AE2DABF4 |
| 14e4:4359 | 1043:850c | Broadco... | BCM43228 802.11a/b/g/n       | 21    | wl         | 55F43C974B |
| 14e4:43b1 | 1043:855c | Broadco... | BCM4352 802.11ac Wireless... | 20    | wl         | 1D2014DD53 |
| 168c:0034 | 11ad:6621 | Qualcom... | AR9462 Wireless Network A... | 20    | ath9k      | 9712E8E45D |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 20    | iwlwifi    | 0571C7F3B9 |
| 168c:002b | 1a3b:1089 | Qualcom... | AR9285 Wireless Network A... | 19    | ath9k      | 6F480ACA77 |
| 1814:3090 | 11ad:7601 | Ralink     | RT3090 Wireless 802.11n 1... | 18    | rt2800pci  | 42B0E234AF |
| 8086:24f3 | 8086:0010 | Intel      | Wireless 8260                | 18    | iwlwifi    | FC98CE50E1 |
| 10ec:8178 | 1043:84b6 | Realtek... | RTL8192CE PCIe Wireless N... | 17    | rtl8192ce  | 0D6CA866B0 |
| 10ec:8179 | 10ec:8197 | Realtek... | RTL8188EE Wireless Networ... | 17    | rtl8188ee  | 1FC5F15D9A |
| 14e4:4318 | 1043:100f | Broadco... | BCM4318 [AirForce One 54g... | 17    | ssb        | 3CB2CDDB91 |
| 1814:5390 | 1186:3c07 | Ralink     | RT5390 Wireless 802.11n 1... | 17    | rt2800pci  | 73AE3BCE39 |
| 8086:08b3 | 8086:8070 | Intel      | Wireless 3160                | 17    | iwlwifi    | 005D67D00B |
| 168c:001d | 168c:2055 | Qualcom... | AR2417 Wireless Network A... | 16    | ath5k      | 33E8833C53 |
| 168c:0036 | 1028:020c | Qualcom... | QCA9565 / AR9565 Wireless... | 16    | ath9k      | 3C957A3758 |
| 1814:0301 | 1814:2561 | Ralink     | RT2561/RT61 802.11g PCI      | 16    | rt61pci    | E40B76E473 |
| 1814:3090 | 11ad:6632 | Ralink     | RT3090 Wireless 802.11n 1... | 16    | rt2800pci  | 04A6D42A9C |
| 1814:5390 | 1814:f051 | Ralink     | RT5390 Wireless 802.11n 1... | 16    | rt2800pci  | 5D95C5E7FC |
| 10ec:8176 | 10ec:8176 | Realtek... | RTL8188CE 802.11b/g/n WiF... | 15    | rtl8192ce  | 71C83542C5 |
| 14e4:43a0 | 1043:8659 | Broadco... | BCM4360 802.11ac Wireless... | 14    | wl         | 55A6E54ACA |
| 168c:001a | 1186:3a16 | Qualcom... | AR2413/AR2414 Wireless Ne... | 14    | ath5k      | 967BB75CBB |
| 168c:0032 | 1028:0208 | Qualcom... | AR9485 Wireless Network A... | 14    | ath9k      | 12C217A371 |
| 8086:0887 | 8086:4062 | Intel      | Centrino Wireless-N 2230     | 14    | iwlwifi    | 556D9451BA |
| 168c:0013 | 1186:3a73 | Qualcom... | AR5212/5213/2414 Wireless... | 13    | ath5k      | D9048F1428 |
| 168c:0032 | 1028:0209 | Qualcom... | AR9485 Wireless Network A... | 13    | ath9k      | 6ED3187D7A |
| 1814:0301 | 1043:837e | Ralink     | RT2561/RT61 802.11g PCI      | 13    | rt61pci    | 4A1BDB3C5B |
| 1814:0781 | 11ad:7600 | Ralink     | RT2790 Wireless 802.11n 1... | 13    | rt2800pci  | A5E82DE2A1 |
| 1814:3062 | 1814:3062 | Ralink     | RT3062 Wireless 802.11n 2... | 13    | rt2800pci  | 071E4E8502 |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 13    | iwlwifi    | 9333F6F29B |
| 10ec:8821 | 1a3b:2161 | Realtek... | RTL8821AE 802.11ac PCIe W... | 12    | rtl8821ae  | E99B34265E |
| 168c:003e | 1043:86cd | Qualcom... | QCA6174 802.11ac Wireless... | 12    | ath10k_pci | 984F33EE01 |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 12    | iwlwifi    | DBAC8BD679 |
| 10ec:8176 | 10ec:8175 | Realtek... | RTL8188CE 802.11b/g/n WiF... | 11    | rtl8192ce  | FB926E0210 |
| 10ec:b723 | 103c:81c1 | Realtek... | RTL8723BE PCIe Wireless N... | 11    | rtl8723be  | 2F0C4ABC2E |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 11    |            | E5E15DF58D |
| 168c:0013 | 168c:2051 | Qualcom... | AR5212/5213/2414 Wireless... | 11    | ath5k      | 46CBFD5EE9 |
| 1814:3060 | 1043:84e2 | Ralink     | RT3060 Wireless 802.11n 1... | 11    | rt2800pci  | 5FE1529C55 |
| 1814:3060 | 1814:3060 | Ralink     | RT3060 Wireless 802.11n 1... | 11    | rt2800pci  | C1DB00C4E2 |
| 8086:24f3 | 8086:1010 | Intel      | Wireless 8260                | 11    | iwlwifi    | 65DF5317A4 |
| 14e4:43a0 | 1043:85df | Broadco... | BCM4360 802.11ac Wireless... | 10    | wl         | C1E924B844 |
| 168c:0034 | 1043:850e | Qualcom... | AR9462 Wireless Network A... | 10    | ath9k      | 15BB8982DC |
| 8086:a370 | 8086:0034 | Intel      | Wireless-AC 9560 [Jeffers... | 10    | iwlwifi    | 7A67030E4F |
| 8086:a370 | 8086:02a4 | Intel      | Wireless-AC 9560 [Jeffers... | 10    | iwlwifi    | FF435389C9 |
| 10ec:8179 | 17aa:0179 | Realtek... | RTL8188EE Wireless Networ... | 9     | rtl8188ee  | 9880306BE0 |
| 168c:0023 | 168c:3071 | Qualcom... | AR5416 Wireless Network A... | 9     | ath9k      | 1B3B77E4C1 |
| 168c:0042 | 1028:1810 | Qualcom... | QCA9377 802.11ac Wireless... | 9     | ath10k_pci | B98840B380 |
| 8086:08b3 | 8086:0070 | Intel      | Wireless 3160                | 9     | iwlwifi    | 51A3F3BF52 |
| 10ec:8185 | 10ec:8185 | Realtek... | RTL-8185 IEEE 802.11a/b/g... | 8     | rtl8180    | EC6B93D879 |
| 168c:001c | 105b:e008 | Qualcom... | AR242x / AR542x Wireless ... | 8     | ath5k      | 22A3849E3A |
| 168c:0036 | 1028:020e | Qualcom... | QCA9565 / AR9565 Wireless... | 8     | ath9k      | 0F87997CD1 |
| 168c:003e | 1028:0310 | Qualcom... | QCA6174 802.11ac Wireless... | 8     | ath10k_pci | C708B6ADE4 |
| 1814:539b | 103c:18ed | Ralink     | RT5390R 802.11bgn PCIe Wi... | 8     | rt2800pci  | ECA0E999DE |
| 8086:3165 | 8086:4410 | Intel      | Wireless 3165                | 8     | iwlwifi    | 7855843846 |
| 10ec:8179 | 103c:197d | Realtek... | RTL8188EE Wireless Networ... | 7     | rtl8188ee  | 24DD32836D |
| 10ec:8190 | 10ec:8190 | Realtek... | RTL8190 802.11n PCI Wirel... | 7     | wl         | 96A75ACB49 |
| 14e4:4328 | 1028:000a | Broadco... | BCM4321 802.11a/b/g/n        | 7     | wl         | A21708CA72 |
| 14e4:4357 | 14e4:04db | Broadco... | BCM43225 802.11b/g/n         | 7     | wl         | C73B25ED21 |
| 168c:001a | 168c:2052 | Qualcom... | AR2413/AR2414 Wireless Ne... | 7     | ath5k      | 1ECED47226 |
| 168c:001c | 1a3b:1034 | Qualcom... | AR242x / AR542x Wireless ... | 7     | ath5k      | 1ABA3CB35F |
| 168c:0029 | 168c:2091 | Qualcom... | AR922X Wireless Network A... | 7     | ath9k      | 2C4F68ECB1 |
| 168c:002b | 1a3b:2c37 | Qualcom... | AR9285 Wireless Network A... | 7     | ath9k      | 56756CD581 |
| 168c:0030 | 168c:3116 | Qualcom... | AR93xx Wireless Network A... | 7     | ath9k      | E2923BE323 |
| 1814:0781 | 1814:2790 | Ralink     | RT2790 Wireless 802.11n 1... | 7     | rt2800pci  | DB721D3478 |
| 1814:3290 | 103c:18ec | Ralink     | RT3290 Wireless 802.11n 1... | 7     | rt2800pci  | 92DD9B01DE |
| 14e4:432b | 106b:008e | Broadco... | BCM4322 802.11a/b/g/n Wir... | 6     | wl         | FA300CEB06 |
| 14e4:4365 | 103c:804a | Broadco... | BCM43142 802.11b/g/n         | 6     | wl         | C84840828C |
| 14e4:43b1 | 1043:85ba | Broadco... | BCM4352 802.11ac Wireless... | 6     | wl         | DE065F2CFC |
| 14e4:43b1 | 1a3b:2123 | Broadco... | BCM4352 802.11ac Wireless... | 6     | wl         | 7A0FC72547 |
| 168c:001a | 168c:1052 | Qualcom... | AR2413/AR2414 Wireless Ne... | 6     | ath5k      | CFD5732D7A |
| 168c:001b | 11ad:5001 | Qualcom... | AR5413/AR5414 Wireless Ne... | 6     | ath5k      | A95D4AC608 |
| 168c:0032 | 1a3b:1186 | Qualcom... | AR9485 Wireless Network A... | 6     | ath9k      | C13D443BF5 |
| 168c:0032 | 1a3b:1f86 | Qualcom... | AR9485 Wireless Network A... | 6     | ath9k      | 9C23FD1532 |
| 168c:0037 | 1a3b:2100 | Qualcom... | AR9485 Wireless Network A... | 6     | ath9k      | AEEE40220B |
| 168c:003e | 1043:86e0 | Qualcom... | QCA6174 802.11ac Wireless... | 6     | ath10k_pci | 83413EEEDF |
| 1814:5392 | 1186:3c06 | Ralink     | RT5392 PCIe Wireless Netw... | 6     | rt2800pci  | 77B7012656 |
| 1814:5592 | 1043:851a | Ralink     | RT5592 PCIe Wireless Netw... | 6     |            | 08D84A1FF9 |
| 8086:0888 | 8086:4262 | Intel      | Centrino Wireless-N 2230     | 6     | iwlwifi    | C7D04D3D16 |
| 8086:4235 | 8086:1001 | Intel      | Ultimate N WiFi Link 5300    | 6     | iwlwifi    | 210776A202 |
| 10ec:8178 | 1043:85e3 | Realtek... | RTL8192CE PCIe Wireless N... | 5     | rtl8192ce  | 577F91EB8A |
| 10ec:8812 | 1043:86dd | Realtek... | RTL8812AE 802.11ac PCIe W... | 5     | rtl8821ae  | A9F8B1AD35 |
| 11ab:1faa | 1385:6b00 | Marvell... | 88w8335 [Libertas] 802.11... | 5     |            | F30CD368D8 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:03ef | 1849:03ef | Nvidia     | MCP61 Ethernet               | 206   | forcedeth  | EC1F6C8A0B |
| 8086:1539 | 1043:85f0 | Intel      | I211 Gigabit Network Conn... | 154   | igb        | 238AD0F889 |
| 8086:1503 | 1043:849c | Intel      | 82579V Gigabit Network Co... | 152   | e1000e     | BD3C6A762C |
| 10de:03ef | 1458:e000 | Nvidia     | MCP61 Ethernet               | 105   | forcedeth  | 53DB8982F5 |
| 8086:1539 | 1849:1539 | Intel      | I211 Gigabit Network Conn... | 84    | igb        | 5E8A739106 |
| 10de:03ef | 1043:8234 | Nvidia     | MCP61 Ethernet               | 76    | forcedeth  | F3B22A675A |
| 10de:03ef | 1043:83a4 | Nvidia     | MCP61 Ethernet               | 76    | forcedeth  | A6BD4DA213 |
| 8086:1539 | 1458:e000 | Intel      | I211 Gigabit Network Conn... | 63    | igb        | D4813C969B |
| 8086:10de | 1028:0276 | Intel      | 82567LM-3 Gigabit Network... | 48    | e1000e     | 5151CB704B |
| 8086:1502 | 1028:052c | Intel      | 82579LM Gigabit Network C... | 42    | e1000e     | 779B6B3344 |
| 8086:10d3 | 8086:a01f | Intel      | 82574L Gigabit Network Co... | 41    | e1000e     | 2902DCE4BA |
| 10de:03ef | 1462:7309 | Nvidia     | MCP61 Ethernet               | 40    | forcedeth  | 93E77F9DC3 |
| 10de:0057 | 1043:812a | Nvidia     | CK804 Ethernet Controller    | 37    | forcedeth  | 17E56B1C60 |
| 8086:1502 | 1028:047e | Intel      | 82579LM Gigabit Network C... | 37    | e1000e     | 2D378E81BE |
| 10de:0373 | 1043:8239 | Nvidia     | MCP55 Ethernet               | 32    | forcedeth  | 44E3D900F5 |
| 8086:10de | 1028:027f | Intel      | 82567LM-3 Gigabit Network... | 28    | e1000e     | 439AF540E7 |
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 28    | iwlwifi    | 9BFAB5575C |
| 8086:10bd | 1028:0211 | Intel      | 82566DM-2 Gigabit Network... | 27    | e1000e     | E23742C63F |
| 8086:1503 | 1458:e000 | Intel      | 82579V Gigabit Network Co... | 27    | e1000e     | 82A8163E58 |
| 8086:10bd | 103c:2818 | Intel      | 82566DM-2 Gigabit Network... | 26    | e1000e     | 775B90FA5A |
| 8086:104a | 103c:2800 | Intel      | 82566DM Gigabit Network C... | 24    | e1000e     | 3A37DFD543 |
| 8086:10bd | 103c:281e | Intel      | 82566DM-2 Gigabit Network... | 23    | e1000e     | 366E5CAC3F |
| 8086:10de | 103c:3048 | Intel      | 82567LM-3 Gigabit Network... | 23    | e1000e     | 733B76A48E |
| 8086:294c | 8086:0001 | Intel      | 82566DC-2 Gigabit Network... | 21    | e1000e     | 90F4B2CD0E |
| 10de:0057 | 1043:8141 | Nvidia     | CK804 Ethernet Controller    | 20    | forcedeth  | FD8F010178 |
| 10de:03ef | 103c:2a6c | Nvidia     | MCP61 Ethernet               | 20    | forcedeth  | 6D882902AD |
| 1106:3065 | 1043:80ed | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 20    | via_rhine  | 476F99FF1B |
| 8086:1503 | 1025:8000 | Intel      | 82579V Gigabit Network Co... | 20    | e1000e     | 42B0E234AF |
| 10de:0373 | 1462:7250 | Nvidia     | MCP55 Ethernet               | 19    | forcedeth  | C862E6269E |
| 10de:03ef | 1565:2505 | Nvidia     | MCP61 Ethernet               | 19    | forcedeth  | 1004AD3220 |
| 8086:150c | 1043:8457 | Intel      | 82583V Gigabit Network Co... | 19    | e1000e     | B0D238EB2E |
| 10de:0269 | 1043:816a | Nvidia     | MCP51 Ethernet Controller    | 18    | forcedeth  | A26BD26890 |
| 8086:104b | 8086:0001 | Intel      | 82566DC Gigabit Network C... | 18    | e1000e     | 43BE22F6DA |
| 8086:1502 | 103c:3397 | Intel      | 82579LM Gigabit Network C... | 18    | e1000e     | FF9A2F987D |
| 10b7:9200 | 10b7:1000 | 3Com       | 3c905C-TX/TX-M [Tornado]     | 17    | 3c59x      | 278994D939 |
| 8086:1502 | 103c:339a | Intel      | 82579LM Gigabit Network C... | 17    | e1000e     | 2962B36D7E |
| 10de:0057 | 1458:e000 | Nvidia     | CK804 Ethernet Controller    | 15    | forcedeth  | 872FEB1CA3 |
| 10de:0373 | 1043:cb84 | Nvidia     | MCP55 Ethernet               | 15    | forcedeth  | 064DD1CCBF |
| 10de:0373 | 1458:e000 | Nvidia     | MCP55 Ethernet               | 15    | forcedeth  | 0CCA59B833 |
| 1106:3065 | 1849:3065 | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 15    | via_rhine  | 6FAC734286 |
| 8086:10d3 | 15d9:10d3 | Intel      | 82574L Gigabit Network Co... | 15    | e1000e     | CFC42EAC60 |
| 8086:10df | 1734:114d | Intel      | 82567LF-3 Gigabit Network... | 15    | e1000e     | 9632357AEB |
| 8086:1502 | 103c:1589 | Intel      | 82579LM Gigabit Network C... | 15    | e1000e     | 9D85C4CA60 |
| 8086:10c0 | 1028:020d | Intel      | 82562V-2 10/100 Network C... | 14    | e1000e     | 865EB363F8 |
| 8086:10de | 103c:3034 | Intel      | 82567LM-3 Gigabit Network... | 14    | e1000e     | A40772FC80 |
| 8086:10f0 | 8086:0036 | Intel      | 82578DC Gigabit Network C... | 14    | e1000e     | A57DCF32AA |
| 8086:1533 | 1043:8557 | Intel      | I210 Gigabit Network Conn... | 14    | igb        | 785E45F5BF |
| 8086:2723 | 8086:0084 | Intel      | Wi-Fi 6 AX200                | 14    | iwlwifi    | B51C7D1EE8 |
| 10de:03ef | 103c:2a99 | Nvidia     | MCP61 Ethernet               | 13    | forcedeth  | 0BC668FE41 |
| 8086:1539 | 8086:0000 | Intel      | I211 Gigabit Network Conn... | 13    | igb        | E6AC162ADE |
| 10de:0269 | 1458:e000 | Nvidia     | MCP51 Ethernet Controller    | 12    | forcedeth  | 6027467F3B |
| 10de:03ef | 1565:3407 | Nvidia     | MCP61 Ethernet               | 12    | forcedeth  | 2D17F5BB22 |
| 8086:10de | 17aa:3048 | Intel      | 82567LM-3 Gigabit Network... | 12    | e1000e     | 2BFF73F199 |
| 8086:10f0 | 1025:8000 | Intel      | 82578DC Gigabit Network C... | 12    | e1000e     | A4BB2D6329 |
| 8086:1502 | 103c:1495 | Intel      | 82579LM Gigabit Network C... | 12    | e1000e     | D56240BFB5 |
| 8086:10d3 | 1043:8369 | Intel      | 82574L Gigabit Network Co... | 11    | e1000e     | B2D6DABAA7 |
| 8086:1502 | 103c:1497 | Intel      | 82579LM Gigabit Network C... | 11    | e1000e     | 51C0A64A32 |
| 8086:1503 | 8086:0000 | Intel      | 82579V Gigabit Network Co... | 11    | e1000e     | 8F409F32B1 |
| 8086:1503 | 8086:2002 | Intel      | 82579V Gigabit Network Co... | 11    | e1000e     | C9400C1FCB |
| 10de:0269 | 1043:8221 | Nvidia     | MCP51 Ethernet Controller    | 10    | forcedeth  | 15EA243CBA |
| 10de:03ef | 1025:8000 | Nvidia     | MCP61 Ethernet               | 10    | forcedeth  | 31971EE9A6 |
| 1106:3065 | 1019:0102 | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 10    | via_rhine  | 3B9012BDA6 |
| 8086:10bd | 8086:0001 | Intel      | 82566DM-2 Gigabit Network... | 10    | e1000e     | 0A0C15A32B |
| 8086:10c0 | 1028:0238 | Intel      | 82562V-2 10/100 Network C... | 10    | e1000e     | 868BBBBB38 |
| 8086:10ce | 1043:82d5 | Intel      | 82567V-2 Gigabit Network ... | 10    | e1000e     | 6A04D25891 |
| 8086:10de | 103c:3646 | Intel      | 82567LM-3 Gigabit Network... | 10    | e1000e     | B84B8A2AAE |
| 8086:10f0 | 8086:0037 | Intel      | 82578DC Gigabit Network C... | 10    | e1000e     | 64266B67A2 |
| 8086:1503 | 8086:2017 | Intel      | 82579V Gigabit Network Co... | 10    | e1000e     | CA1BAF42C2 |
| 10b7:9055 | 10b7:9055 | 3Com       | 3c905B 100BaseTX [Cyclone]   | 9     | 3c59x      | 0200BA924B |
| 10de:0269 | 105b:0d04 | Nvidia     | MCP51 Ethernet Controller    | 9     | forcedeth  | 8FF0EB4E50 |
| 10de:0373 | 1462:7260 | Nvidia     | MCP55 Ethernet               | 9     | forcedeth  | D67A015497 |
| 10de:03ef | 1019:2242 | Nvidia     | MCP61 Ethernet               | 9     | forcedeth  | A51A8C96DF |
| 8086:10bd | 1043:8268 | Intel      | 82566DM-2 Gigabit Network... | 9     | e1000e     | 9057FD4986 |
| 8086:10ef | 103c:304b | Intel      | 82578DM Gigabit Network C... | 9     | e1000e     | 16542643A0 |
| 8086:1502 | 103c:1494 | Intel      | 82579LM Gigabit Network C... | 9     | e1000e     | B9CA27E33C |
| 8086:1533 | 1849:1533 | Intel      | I210 Gigabit Network Conn... | 9     | igb        | A14B2C7156 |
| 8086:1539 | 1462:7a32 | Intel      | I211 Gigabit Network Conn... | 9     | igb        | 617835BC00 |
| 8086:27dc | 1462:336c | Intel      | NM10/ICH7 Family LAN Cont... | 9     | e100       | 70949E4CAC |
| 10de:0057 | 1695:1010 | Nvidia     | CK804 Ethernet Controller    | 8     | forcedeth  | 3912CD3C3A |
| 10de:0269 | 103c:2a34 | Nvidia     | MCP51 Ethernet Controller    | 8     | forcedeth  | 8854FD6644 |
| 8086:10d3 | 103c:158a | Intel      | 82574L Gigabit Network Co... | 8     | e1000e     | BAF893B7F3 |
| 8086:10f6 | 8086:0000 | Intel      | 82574L Gigabit Network Co... | 8     | e1000e     | FA300CEB06 |
| 8086:1502 | 1028:05d2 | Intel      | 82579LM Gigabit Network C... | 8     | e1000e     | 8EAFAB46BF |
| 8086:1502 | 17aa:3077 | Intel      | 82579LM Gigabit Network C... | 8     | e1000e     | 6C4701993F |
| 10de:03ef | 1019:2609 | Nvidia     | MCP61 Ethernet               | 7     | forcedeth  | 5343BC19E6 |
| 10de:03ef | 105b:0d15 | Nvidia     | MCP61 Ethernet               | 7     | forcedeth  | 214A31BC1A |
| 1106:3065 | 1565:2200 | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 7     | via_rhine  | B3224EB5FC |
| 8086:10d3 | 8086:0000 | Intel      | 82574L Gigabit Network Co... | 7     | e1000e     | 1F5FC8D4A4 |
| 8086:10ef | 8086:0038 | Intel      | 82578DM Gigabit Network C... | 7     | e1000e     | 94B8C23EEF |
| 8086:1502 | 103c:158a | Intel      | 82579LM Gigabit Network C... | 7     | e1000e     | BAF893B7F3 |
| 8086:1502 | 17aa:3084 | Intel      | 82579LM Gigabit Network C... | 7     | e1000e     | A08028C506 |
| 8086:1503 | 1734:11d9 | Intel      | 82579V Gigabit Network Co... | 7     | e1000e     | 48378AE22B |
| 8086:1503 | 8086:2044 | Intel      | 82579V Gigabit Network Co... | 7     | e1000e     | 4F24AD146B |
| 8086:1521 | 15d9:1521 | Intel      | I350 Gigabit Network Conn... | 7     | igb        | 2E6D79F345 |
| 8086:27dc | 8086:3086 | Intel      | NM10/ICH7 Family LAN Cont... | 7     | e100       | 59B8B5AAFD |
| 10de:03ef | 1028:020e | Nvidia     | MCP61 Ethernet               | 6     | forcedeth  | 84263BB67F |
| 10de:03ef | 103c:2a66 | Nvidia     | MCP61 Ethernet               | 6     | forcedeth  | E843C895F8 |
| 10de:03ef | 10de:cb84 | Nvidia     | MCP61 Ethernet               | 6     | forcedeth  | 323D6D5562 |
| 8086:1094 | 8086:0001 | Intel      | PRO/100 VE Network Connec... | 6     | e100       | BFA90A9A05 |
| 8086:10bd | 17aa:3038 | Intel      | 82566DM-2 Gigabit Network... | 6     | e1000e     | 6DF5762C6A |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1455 | 1022:1455 | AMD        | Zeppelin/Renoir PCIe Dumm... | 416   |            | 5E8A739106 |
| 1022:145a | 1022:145a | AMD        | Zeppelin/Raven/Raven2 PCI... | 416   |            | 5E8A739106 |
| 1022:1455 | 1043:8747 | AMD        | Zeppelin/Renoir PCIe Dumm... | 80    |            | 172F18A294 |
| 1022:145a | 1043:8747 | AMD        | Zeppelin/Raven/Raven2 PCI... | 80    |            | 172F18A294 |
| 1022:1485 | 1022:1485 | AMD        | Starship/Matisse Reserved... | 30    |            | 2E60313B01 |
| 1022:148a | 1022:148a | AMD        | Starship/Matisse PCIe Dum... | 28    |            | 2E60313B01 |
| 1022:1485 | 1043:87c0 | AMD        | Starship/Matisse Reserved... | 15    |            | 40061999CC |
| 1022:148a | 1043:87c0 | AMD        | Starship/Matisse PCIe Dum... | 15    |            | 40061999CC |
| 1022:145a | 1043:876b | AMD        | Zeppelin/Raven/Raven2 PCI... | 12    |            | DE065F2CFC |
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
| 1022:1455 | 1019:9ce5 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 06776696F3 |
| 1022:1455 | 103c:8399 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 9440F6405B |
| 1022:1455 | 1462:7b90 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | C7998D926E |
| 1022:145a | 1002:15d8 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 6D716FD307 |
| 1022:145a | 1019:9ce5 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 06776696F3 |
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
| 1022:15e6 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Non-S... | 3     | i2c_amd... | 1AC9EAC22B |
| 104c:9065 |           | Texas I... | TMS320DM642                  | 2     |            | A74B989748 |
| 8086:a2a4 |           | Intel      | 200 Series/Z370 Chipset F... | 2     |            | 46EA2E591E |
| 0090:0000 | 0090:0000 |            |                              | 1     |            | B562E609ED |
| 1274:5882 |           | Ensoniq    |                              | 1     |            | 3F25A03C59 |
| 12f4:5000 |           | Megatel    |                              | 1     |            | F9A4969283 |
| 1a39:0004 | 1a39:e020 |            |                              | 1     |            | 93A39661EC |
| 8086:a135 | 8086:a135 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 2E35C3E421 |
| a411:0000 | 011b:0808 |            |                              | 1     |            | E79C952746 |

### Parallel controller (bidir) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1c00:2170 | 1c00:2170 |            | WCH PCI                      | 2     |            | 9F1B178431 |

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
| 8086:2f30 | 8086:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    | hswep_u... | 021596F9B3 |
| 8086:2f34 | 8086:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    | hswep_u... | 021596F9B3 |
| 8086:2f7d | 8086:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | 021596F9B3 |
| 8086:2f36 | 8086:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 51    | hswep_u... | 021596F9B3 |
| 8086:2f37 | 8086:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 51    | hswep_u... | 021596F9B3 |
| 8086:0e36 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 29    | ivbep_u... | 8EAFAB46BF |
| 8086:2015 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 29    |            | 0217F128CA |
| 8086:204c | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 29    | skx_uncore | 0217F128CA |
| 8086:204d | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 29    | skx_uncore | 0217F128CA |
| 8086:3c44 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to Q... | 25    | snbep_u... | BAF893B7F3 |
| 8086:3ce6 | 8086:0000 | Intel      | Xeon E5/Core i7 QuickPath... | 25    |            | BAF893B7F3 |
| 8086:3c43 | 1043:84ef | Intel      | Xeon E5/Core i7 Ring to P... | 24    | snbep_u... | 39F22D868E |
| 8086:3c43 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to P... | 24    | snbep_u... | BAF893B7F3 |
| 8086:3c44 | 1043:84ef | Intel      | Xeon E5/Core i7 Ring to Q... | 24    | snbep_u... | 39F22D868E |
| 8086:3c46 | 1043:84ef | Intel      | Xeon E5/Core i7 Processor... | 24    | snbep_u... | 39F22D868E |
| 8086:3ce6 | 1043:84ef | Intel      | Xeon E5/Core i7 QuickPath... | 24    |            | 39F22D868E |
| 8086:0e34 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 20    | ivbep_u... | 41EEB14B47 |
| 8086:3c46 |           | Intel      | Xeon E5/Core i7 Processor... | 19    | snbep_u... | BAF893B7F3 |
| 8086:6f30 | 8086:6f30 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 19    | bdx_uncore | 65DF5317A4 |
| 8086:6f34 | 8086:6f34 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 19    | bdx_uncore | 65DF5317A4 |
| 8086:6f7d | 8086:6f7d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 19    |            | 65DF5317A4 |
| 8086:0e30 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 17    | ivbep_u... | EEE7D322DF |
| 8086:0e34 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 17    | ivbep_u... | EEE7D322DF |
| 8086:0e36 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 17    | ivbep_u... | EEE7D322DF |
| 8086:6f36 | 8086:6f36 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 17    | bdx_uncore | 56478E0933 |
| 8086:6f37 | 8086:6f37 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 17    | bdx_uncore | 56478E0933 |
| 8086:0e30 |           | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 12    | ivbep_u... | 9D85C4CA60 |
| 8086:3c43 | 1458:3c43 | Intel      | Xeon E5/Core i7 Ring to P... | 11    | snbep_u... | 82A8163E58 |
| 8086:3c44 | 1458:3c44 | Intel      | Xeon E5/Core i7 Ring to Q... | 11    | snbep_u... | 82A8163E58 |
| 8086:3c46 | 1458:3c46 | Intel      | Xeon E5/Core i7 Processor... | 11    | snbep_u... | 82A8163E58 |
| 8086:3ce6 | 1458:3ce6 | Intel      | Xeon E5/Core i7 QuickPath... | 11    |            | 82A8163E58 |
| 8086:3424 |           | Intel      | 7500/5520/5500/X58 Perfor... | 10    |            | FA300CEB06 |
| 8086:0e30 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 8     | ivbep_u... | 41EEB14B47 |
| 8086:0e30 | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 7     | ivbep_u... | 8EAFAB46BF |
| 8086:0e34 | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 7     | ivbep_u... | 8EAFAB46BF |
| 8086:2f36 | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 7     | hswep_u... | FDE33600E4 |
| 8086:2f37 | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 7     | hswep_u... | FDE33600E4 |
| 8086:2f38 | 8086:2f38 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 6     | hswep_u... | D54DC05BEB |
| 8086:3c43 | 1849:3c43 | Intel      | Xeon E5/Core i7 Ring to P... | 5     | snbep_u... | 1B28CC994F |
| 8086:3c44 | 1849:3c44 | Intel      | Xeon E5/Core i7 Ring to Q... | 5     | snbep_u... | 1B28CC994F |
| 8086:3c46 | 1849:3c46 | Intel      | Xeon E5/Core i7 Processor... | 5     | snbep_u... | 1B28CC994F |
| 8086:3c46 | 8086:0000 | Intel      | Xeon E5/Core i7 Processor... | 5     | snbep_u... | CBEE931F44 |
| 8086:3ce6 | 1849:3ce6 | Intel      | Xeon E5/Core i7 QuickPath... | 5     |            | 1B28CC994F |
| 8086:2f30 | 1849:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | 917E16476B |
| 8086:2f34 | 1849:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | 917E16476B |
| 8086:2f36 | 1849:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | 917E16476B |
| 8086:2f37 | 1849:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | 917E16476B |
| 8086:2f7d | 1849:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | 917E16476B |
| 8086:6f30 | 1849:6f30 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     | bdx_uncore | B09A16F73F |
| 8086:6f34 | 1849:6f34 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     | bdx_uncore | B09A16F73F |
| 8086:6f36 | 1849:6f36 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     | bdx_uncore | B09A16F73F |
| 8086:6f37 | 1849:6f37 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     | bdx_uncore | B09A16F73F |
| 8086:6f7d | 1849:6f7d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     |            | B09A16F73F |
| 8086:0e30 | 1458:3c46 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     | ivbep_u... | DD20758A89 |
| 8086:0e34 | 1458:3c43 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     | ivbep_u... | DD20758A89 |
| 8086:0e36 | 1458:3c44 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     | ivbep_u... | DD20758A89 |
| 8086:2f32 | 8086:2f32 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     | hswep_u... | D54DC05BEB |
| 8086:3c43 | 1028:0497 | Intel      | Xeon E5/Core i7 Ring to P... | 3     | snbep_u... | F1D5B6204E |
| 8086:3c44 | 1028:0497 | Intel      | Xeon E5/Core i7 Ring to Q... | 3     | snbep_u... | F1D5B6204E |
| 8086:3c46 | 1028:0497 | Intel      | Xeon E5/Core i7 Processor... | 3     | snbep_u... | F1D5B6204E |
| 8086:3ce6 | 1028:0497 | Intel      | Xeon E5/Core i7 QuickPath... | 3     |            | F1D5B6204E |
| 8086:6f32 | 8086:6f32 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     | bdx_uncore | 7436C74DCB |
| 8086:6f33 | 8086:6f33 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     | bdx_uncore | 7436C74DCB |
| 8086:0e30 | 1028:05d4 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     | ivbep_u... | C7E1E32971 |
| 8086:0e30 | 1734:11b5 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     | ivbep_u... | 961A7ADB3E |
| 8086:0e34 | 1028:05d4 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     | ivbep_u... | C7E1E32971 |
| 8086:0e34 | 1734:11b5 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     | ivbep_u... | 961A7ADB3E |
| 8086:0e36 | 1734:11b5 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     | ivbep_u... | 961A7ADB3E |
| 8086:3c43 | 1462:7760 | Intel      | Xeon E5/Core i7 Ring to P... | 2     | snbep_u... | 748D276276 |
| 8086:3c43 | 17aa:1027 | Intel      | Xeon E5/Core i7 Ring to P... | 2     | snbep_u... | B7463FD8F2 |
| 8086:3c43 | 17aa:1028 | Intel      | Xeon E5/Core i7 Ring to P... | 2     | snbep_u... | 7E1E79D0B1 |
| 8086:3c44 | 1462:7760 | Intel      | Xeon E5/Core i7 Ring to Q... | 2     | snbep_u... | 748D276276 |
| 8086:3c44 | 17aa:1027 | Intel      | Xeon E5/Core i7 Ring to Q... | 2     | snbep_u... | B7463FD8F2 |
| 8086:3c44 | 17aa:1028 | Intel      | Xeon E5/Core i7 Ring to Q... | 2     | snbep_u... | 7E1E79D0B1 |
| 8086:3c46 | 1462:7760 | Intel      | Xeon E5/Core i7 Processor... | 2     | snbep_u... | 748D276276 |
| 8086:3c46 | 17aa:1027 | Intel      | Xeon E5/Core i7 Processor... | 2     | snbep_u... | B7463FD8F2 |
| 8086:3c46 | 17aa:1028 | Intel      | Xeon E5/Core i7 Processor... | 2     | snbep_u... | 7E1E79D0B1 |
| 8086:3ce6 | 1462:7760 | Intel      | Xeon E5/Core i7 QuickPath... | 2     |            | 748D276276 |
| 8086:3ce6 | 17aa:1027 | Intel      | Xeon E5/Core i7 QuickPath... | 2     |            | B7463FD8F2 |
| 8086:3ce6 | 17aa:1028 | Intel      | Xeon E5/Core i7 QuickPath... | 2     |            | 7E1E79D0B1 |
| 8086:6f38 | 8086:6f38 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     | bdx_uncore | 9EE9F662A8 |
| 8086:0e30 | 1462:7737 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 725B24FE69 |
| 8086:0e30 | 15d9:0628 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | F7519BF7BE |
| 8086:0e30 | 15d9:062c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 2B1034E588 |
| 8086:0e30 | 15d9:0709 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 9F3D443A21 |
| 8086:0e30 | 17aa:1026 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 5A6C7B0805 |
| 8086:0e30 | 1849:0e30 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 69907BBCE0 |
| 8086:0e34 | 1462:7737 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 725B24FE69 |
| 8086:0e34 | 15d9:0628 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | F7519BF7BE |
| 8086:0e34 | 15d9:062c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 2B1034E588 |
| 8086:0e34 | 15d9:0709 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 9F3D443A21 |
| 8086:0e34 | 17aa:1026 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 5A6C7B0805 |
| 8086:0e34 | 1849:0e34 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 69907BBCE0 |
| 8086:0e36 | 1462:7737 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 725B24FE69 |
| 8086:0e36 | 15d9:0628 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | F7519BF7BE |
| 8086:0e36 | 15d9:062c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 2B1034E588 |
| 8086:0e36 | 15d9:0709 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 9F3D443A21 |
| 8086:0e36 | 17aa:1026 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 5A6C7B0805 |
| 8086:0e36 | 1849:0e36 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 69907BBCE0 |
| 8086:0e37 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | ACFF74E0DB |

### Pic (8259) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3422 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 217   |            | F140183571 |
| 8086:3423 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 217   |            | F140183571 |
| 8086:342e |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 217   | i7core_... | F140183571 |
| 8086:3438 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 137   | i5500_temp | F140183571 |
| 8086:3425 |           | Intel      | 7500/5520/5500/X58 Physic... | 86    |            | FA300CEB06 |
| 8086:3426 |           | Intel      | 7500/5520/5500/X58 Routin... | 86    |            | FA300CEB06 |
| 8086:3427 |           | Intel      | 7500/5520/5500 Physical a... | 77    |            | FA300CEB06 |
| 8086:3428 |           | Intel      | 7500/5520/5500 Routing & ... | 77    |            | FA300CEB06 |
| 8086:3422 | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 21    |            | FD20ECEEC0 |
| 8086:3423 | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 21    |            | FD20ECEEC0 |
| 8086:342e | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 21    | i7core_... | FD20ECEEC0 |
| 8086:3422 | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 11    |            | 4D1157B020 |
| 8086:3423 | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 11    |            | 4D1157B020 |
| 8086:342e | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 11    | i7core_... | 4D1157B020 |
| 8086:3422 | 0086:0022 | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     |            | D4CEB4D3BC |
| 8086:3423 | 0086:0023 | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     |            | D4CEB4D3BC |
| 8086:342e | 0086:002e | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     | i7core_... | D4CEB4D3BC |
| 8086:3422 | 0028:006d | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | 82F1FBFA97 |
| 8086:3423 | 0028:006d | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | 82F1FBFA97 |
| 8086:342e | 0028:006d | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     | i7core_... | 82F1FBFA97 |
| 8086:3422 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     |            | DF7A5AC424 |
| 8086:3422 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     |            | B2D6DABAA7 |
| 8086:3423 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     |            | DF7A5AC424 |
| 8086:3423 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     |            | B2D6DABAA7 |
| 8086:3425 | 0043:0063 | Intel      | 7500/5520/5500/X58 Physic... | 3     |            | B2D6DABAA7 |
| 8086:3426 | 0043:0063 | Intel      | 7500/5520/5500/X58 Routin... | 3     |            | B2D6DABAA7 |
| 8086:3427 | 0043:0063 | Intel      | 7500/5520/5500 Physical a... | 3     |            | B2D6DABAA7 |
| 8086:3428 | 0043:0063 | Intel      | 7500/5520/5500 Routing & ... | 3     |            | B2D6DABAA7 |
| 8086:342e | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     | i7core_... | DF7A5AC424 |
| 8086:342e | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     | i7core_... | B2D6DABAA7 |
| 8086:3438 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     | i5500_temp | B2D6DABAA7 |

### Pic (io(x)-apic) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:342f |           | Intel      | 7500/5520/5500/X58 Truste... | 77    |            | FA300CEB06 |
| 8086:342d |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 51    |            | FA300CEB06 |
| 8086:2f2c | 8086:0000 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 29    |            | 021596F9B3 |
| 8086:2026 | 8086:2026 | Intel      | Sky Lake-E IOAPIC            | 26    |            | 0217F128CA |
| 8086:2036 | 8086:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 26    |            | 0217F128CA |
| 8086:3c2c | 8086:3c2c | Intel      | Xeon E5/Core i7 I/O APIC     | 25    |            | BAF893B7F3 |
| 8086:3c2c | 1043:84ef | Intel      | Xeon E5/Core i7 I/O APIC     | 24    |            | 39F22D868E |
| 1106:5327 |           | VIA Tec... | P4M890 I/O APIC Interrupt... | 23    |            | 3FB3954AB5 |
| 1106:5364 |           | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 23    |            | 5A1BBCBC9E |
| 8086:0e2c | 8086:0e2c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |            | 41EEB14B47 |
| 8086:0e2c | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 17    |            | EEE7D322DF |
| 8086:6f2c | 8086:0000 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 14    |            | 65DF5317A4 |
| 8086:3c2c | 1458:5000 | Intel      | Xeon E5/Core i7 I/O APIC     | 11    |            | 82A8163E58 |
| 8086:2f2c | 1028:0617 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 9     |            | 3B5017848A |
| 1106:5336 |           | VIA Tec... | K8M890CE I/O APIC Interru... | 7     |            | DA7AC663BF |
| 1106:5364 | 1106:5364 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 7     |            | B991274CE3 |
| 8086:0e2c | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 7     |            | 8EAFAB46BF |
| 8086:2f2c | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 7     |            | FDE33600E4 |
| 1106:5308 | 1849:5308 | VIA Tec... | PT894 I/O APIC Interrupt ... | 6     |            | FFD7AFA075 |
| 8086:3504 |           | Intel      | 6311ESB/6321ESB I/OxAPIC ... | 5     |            | 0061EDE59F |
| 8086:3c2c | 1849:3c2c | Intel      | Xeon E5/Core i7 I/O APIC     | 5     |            | 1B28CC994F |
| 1106:5238 |           | VIA Tec... | K8T890 I/O APIC Interrupt... | 4     |            | D9174E33E4 |
| 8086:2f2c | 1849:2f2c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | 917E16476B |
| 8086:6f2c | 1849:6f2c | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     |            | B09A16F73F |
| 1106:5336 | 1043:8297 | VIA Tec... | K8M890CE I/O APIC Interru... | 3     |            | 476F99FF1B |
| 1106:5351 |           | VIA Tec... | VT3351 I/O APIC Interrupt... | 3     |            | EBF0DCD676 |
| 1106:5364 | 1849:5364 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 3     |            | 78DDA2C16B |
| 8086:0e2c | 1458:5000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     |            | DD20758A89 |
| 8086:2026 | 8086:0000 | Intel      | Sky Lake-E IOAPIC            | 3     |            | 931EA9A398 |
| 8086:2036 | 8086:0000 | Intel      | Sky Lake-E IOxAPIC Config... | 3     |            | 931EA9A398 |
| 8086:3c2c | 1028:0497 | Intel      | Xeon E5/Core i7 I/O APIC     | 3     |            | F1D5B6204E |
| 1106:5327 | 1849:5327 | VIA Tec... | P4M890 I/O APIC Interrupt... | 2     |            | DAD584057B |
| 8086:0326 |           | Intel      | 6700/6702PXH I/OxAPIC Int... | 2     |            | 96D2EFD1F4 |
| 8086:0326 | 103c:12f1 | Intel      | 6700/6702PXH I/OxAPIC Int... | 2     |            | 21D968D1E3 |
| 8086:0326 | 15d9:7980 | Intel      | 6700/6702PXH I/OxAPIC Int... | 2     |            | 8EB1C21341 |
| 8086:0327 | 103c:12f1 | Intel      | 6700PXH I/OxAPIC Interrup... | 2     |            | 21D968D1E3 |
| 8086:0e2c | 1028:05d4 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | C7E1E32971 |
| 8086:0e2c | 1734:11b5 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | 961A7ADB3E |
| 8086:2f2c | 1028:0618 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     |            | 4C6E30FFB1 |
| 8086:2f2c | 1028:064c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     |            | E1BABF19AD |
| 8086:3c2c | 1462:7760 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | 748D276276 |
| 8086:3c2c | 17aa:1027 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | B7463FD8F2 |
| 8086:3c2c | 17aa:1028 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | 7E1E79D0B1 |
| 1106:5327 | 1631:e035 | VIA Tec... | P4M890 I/O APIC Interrupt... | 1     |            | B3494EC9DB |
| 1106:5351 | 1849:5351 | VIA Tec... | VT3351 I/O APIC Interrupt... | 1     |            | D3A94CD051 |
| 1106:5364 | 1019:2125 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 1     |            | A098C98B04 |
| 1106:5409 | 1106:5409 | VIA Tec... | VX855/VX875 APIC and Cent... | 1     |            | 655547B351 |
| 8086:0327 |           | Intel      | 6700PXH I/OxAPIC Interrup... | 1     |            | 219383F559 |
| 8086:0e2c | 1462:7737 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 725B24FE69 |
| 8086:0e2c | 17aa:1026 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 5A6C7B0805 |
| 8086:0e2c | 1849:0e2c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 69907BBCE0 |
| 8086:0e2c | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | ACFF74E0DB |
| 8086:1461 | 1014:1461 | Intel      | 82870P2 P64H2 I/OxAPIC       | 1     |            | D6D105AE70 |
| 8086:2026 | 1734:122f | Intel      | Sky Lake-E IOAPIC            | 1     |            | 14943339B4 |
| 8086:2036 | 1734:122f | Intel      | Sky Lake-E IOxAPIC Config... | 1     |            | 14943339B4 |
| 8086:25ac |           | Intel      | 6300ESB I/O Advanced Prog... | 1     |            | 21330F2BD7 |
| 8086:25ac | 8086:345e | Intel      | 6300ESB I/O Advanced Prog... | 1     |            | 97CC3C4274 |
| 8086:2f2c | 1028:0619 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | ADB52FAE26 |
| 8086:2f2c | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 02F86A0A2A |
| 8086:2f2c | 1462:7882 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 1E0208BF20 |
| 8086:2f2c | 15d9:0852 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 2E6D79F345 |
| 8086:3c2c | 1028:0496 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | 2597040B1B |
| 8086:3c2c | 1028:05d2 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | 6B90A427C2 |
| 8086:3c2c | 1734:11b5 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | 077A9B9D45 |
| 8086:3c2c | 8086:4953 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | BD6FF7AA0F |
| 8086:6f2c | 1028:0617 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | 019BFC3983 |
| 8086:6f2c | 1028:064c | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | 961BF8073A |
| 8086:6f2c | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | D9B1EC3C37 |
| 8086:6f2c | 1462:7883 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | 227E62B97E |

### Pic (io-apic) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:7451 | 1022:7450 | AMD        | AMD-8131 PCI-X IOAPIC        | 2     |            | 940D3D20F9 |
| 1022:7459 | 1022:7459 | AMD        | AMD-8132 PCI-X IOAPIC        | 1     |            | 3DD30C0B92 |

### Power pc (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1957:c006 | 1a56:1201 | Freesca... | MPC8308                      | 3     |            | 73857FA33C |
| 1957:0085 | 110a:4046 | Freesca... | MPC8347 PBGA                 | 1     |            | 60A7685D8D |
| 1957:00b6 | 1a56:1103 | Freesca... | MPC8314E                     | 1     |            | 703D6110A9 |

### Processing accelerators (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ee:5000 | 10ee:000e | Xilinx     | Processing accelerators      | 1     | xclmgmt    | 774E748AB4 |
| 10ee:5001 | 10ee:000e | Xilinx     | Processing accelerators      | 1     | xocl       | 774E748AB4 |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:7806 | 1022:7806 | AMD        | FCH SD Flash Controller      | 19    | sdhci_pci  | 2AF2FAFEE0 |
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 7     | sdhci_pci  | DAEDE56DC8 |
| 8086:9d2b | 8086:7270 | Intel      | Skylake-U/Y SCC: eMMC        | 7     | sdhci_pci  | C96C722A74 |
| 8086:9d2d | 8086:7270 | Intel      | Sunrise Point-LP Secure D... | 7     | sdhci_pci  | C96C722A74 |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | sdhci_pci  | 15A0FF2280 |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 5     | sdhci_pci  | 15A0FF2280 |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     | sdhci_pci  | 15A0FF2280 |
| 197b:2381 | 103c:2aa2 | JMicron... | Standard SD Host Controller  | 3     | sdhci_pci  | 744EE1496B |
| 8086:2294 | 1458:1000 | Intel      | Atom/Celeron/Pentium Proc... | 3     | sdhci_pci  | 39694A0489 |
| 8086:31cc | 1458:1000 | Intel      | Celeron/Pentium Silver Pr... | 3     | sdhci_pci  | D09484C24C |
| 8086:31d0 | 1458:1000 | Intel      | SD Host Controller           | 3     | sdhci_pci  | D09484C24C |
| 1022:7806 | 103c:2b60 | AMD        | FCH SD Flash Controller      | 2     | sdhci_pci  | A691D43B41 |
| 1022:7906 | 17aa:3100 | AMD        | FCH SD Flash Controller      | 2     | sdhci_pci  | 47B6DBB479 |
| 10ec:5209 | 10ec:5209 | Realtek... | RTS5209 PCI Express Card ... | 2     | sdhci_pci  | 6FC0406A55 |
| 197b:2381 | 103c:2aa6 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | 45542209AF |
| 197b:2381 | 1297:3189 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | 0EFBD74715 |
| 197b:2381 | 1297:4012 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | DE0CC0AB6F |
| 8086:19db | 8086:7270 | Intel      | Atom Processor C3000 Seri... | 2     | sdhci_pci  | 50B6A72C0C |
| 1022:7906 | 103c:8436 | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | 1CBA9F05F4 |
| 1106:401b | 1028:0408 | VIA Tec... | VIA Secure Digital host c... | 1     | sdhci_pci  | 3125B9C83A |
| 1180:0822 | 1509:4780 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 3ADB7D01A9 |
| 1180:e822 | 104d:9060 | Ricoh      | MMC/SD Host Controller       | 1     | sdhci_pci  | 26B75090A9 |
| 1217:7120 | 14ff:a003 | O2 Micro   | Integrated MMC/SD Controller | 1     | sdhci_pci  | 6647A9CB02 |
| 14e4:16bc | 1025:0742 | Broadco... | BCM57765/57785 SDXC/MMC C... | 1     | sdhci_pci  | 868EC85E4C |
| 197b:2381 | 1019:2238 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | 7E782321C8 |
| 197b:2381 | 1025:0275 | JMicron... | Standard SD Host Controller  | 1     |            | 09734ADC68 |
| 197b:2381 | 1297:2005 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | BF79C6A1F6 |
| 197b:2381 | 1297:2020 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | DBBC59A59B |
| 197b:2381 | 1462:6720 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | E2CB0B1767 |
| 197b:2381 | 1558:0390 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | CD09738BCD |
| 8086:0f16 | 8086:0f16 | Intel      | Atom Processor Z36xxx/Z37... | 1     | sdhci_pci  | 6AC9E1A935 |
| 8086:0f50 | 8086:7270 | Intel      | Atom Processor E3800 Seri... | 1     | sdhci_pci  | 6960F82AE6 |
| 8086:2294 | 1019:9bef | Intel      | Atom/Celeron/Pentium Proc... | 1     | sdhci_pci  | BBED831835 |
| 8086:2295 | 1028:07c1 | Intel      | Atom/Celeron/Pentium Proc... | 1     | sdhci_pci  | 9F4F497293 |
| 8086:811c | 8086:8119 | Intel      | US15W/US15X/US15L/UL11L S... | 1     | sdhci_pci  | 1FFCB35DFD |
| 8086:811d | 8086:8119 | Intel      | US15W/US15X/US15L/UL11L S... | 1     | sdhci_pci  | 1FFCB35DFD |
| 8086:9d2b | 8086:2065 | Intel      | Skylake-U/Y SCC: eMMC        | 1     | sdhci_pci  | B1EB5D5F20 |
| 8086:9d2d | 8086:2065 | Intel      | Sunrise Point-LP Secure D... | 1     | sdhci_pci  | B1EB5D5F20 |
| 8086:a375 | 103c:843f | Intel      | 300 Series Chipset Family... | 1     | sdhci_pci  | 16A8455B0D |
| 8086:a375 | 1849:a375 | Intel      | 300 Series Chipset Family... | 1     | sdhci_pci  | D350550408 |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a324 | 8086:7270 | Intel      | Cannon Lake PCH SPI Contr... | 55    |            | E097415087 |
| 8086:a324 | 1043:8694 | Intel      | Cannon Lake PCH SPI Contr... | 53    |            | 0B771C098E |
| 8086:a324 | 1849:a324 | Intel      | Cannon Lake PCH SPI Contr... | 28    |            | B0161E1E77 |
| 8086:a324 | 1025:1238 | Intel      | Cannon Lake PCH SPI Contr... | 11    |            | FF435389C9 |
| 8086:a324 | 1462:7b98 | Intel      | Cannon Lake PCH SPI Contr... | 7     |            | 947E963CAC |
| 8086:a324 | 1025:123c | Intel      | Cannon Lake PCH SPI Contr... | 6     |            | EE7C4D9088 |
| 10de:1adb | 10de:1f08 | Nvidia     | TU106 USB Type-C UCSI Con... | 4     |            | 3CF95EC244 |
| 8086:a324 | 1028:085c | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | 90FEDE556D |
| 8086:a324 | 1462:7b17 | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | F4AAAAC1D8 |
| 8086:a324 | 1462:7b33 | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | 5C290C18C9 |
| 10de:1ad7 | 10de:12a4 | Nvidia     | TU102 USB Type-C UCSI Con... | 3     |            | DACEC1AE2C |
| 10de:1ad7 | 1458:37c4 | Nvidia     | TU102 USB Type-C UCSI Con... | 3     | i2c_nvi... | 91A290D35C |
| 10de:1ad7 | 19da:1503 | Nvidia     | TU102 USB Type-C UCSI Con... | 3     | i2c_nvi... | 4C53FECA58 |
| 10de:1adb | 1458:37c2 | Nvidia     | TU106 USB Type-C UCSI Con... | 3     | i2c_nvi... | D1E8039BA7 |
| 10de:1adb | 1458:3fed | Nvidia     | TU106 USB Type-C UCSI Con... | 3     | i2c_nvi... | 6BEE5D9A22 |
| 10de:1adb | 1462:3732 | Nvidia     | TU106 USB Type-C UCSI Con... | 3     | i2c_nvi... | 0B27AC9B2F |
| 10de:1aed | 1458:3fbe | Nvidia     | TU116 [GeForce GTX 1650 S... | 3     | i2c_nvi... | CECF83927E |
| 8086:5ac8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | pwm_lps... | E6AC162ADE |
| 8086:a324 | 103c:843b | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | 913EB3ADCC |
| 8086:a324 | 103c:843c | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | 7773DC895E |
| 8086:a324 | 1462:7b23 | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | 37076CEBE8 |
| 8086:a324 | 1462:7b24 | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | F83D0A812D |
| 8086:a324 | 1462:7b51 | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | FC98CE50E1 |
| 8086:a324 | 17aa:36e7 | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | 69D10D1093 |
| 8086:a368 | 103c:843b | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | 913EB3ADCC |
| 8086:a368 | 103c:843c | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | 7773DC895E |
| 8086:a368 | 1849:a368 | Intel      | Cannon Lake PCH Serial IO... | 3     |            | B2FAC79AFD |
| 8086:a369 | 103c:843b | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | 913EB3ADCC |
| 8086:a369 | 103c:843c | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | 7773DC895E |
| 8086:a369 | 1849:a369 | Intel      | Cannon Lake PCH Serial IO... | 3     |            | B2FAC79AFD |
| 10de:1ad7 | 1043:866a | Nvidia     | TU102 USB Type-C UCSI Con... | 2     | i2c_nvi... | 79DA8109F3 |
| 10de:1ad7 | 3842:2281 | Nvidia     | TU102 USB Type-C UCSI Con... | 2     | i2c_nvi... | B89B031EB9 |
| 10de:1ad7 | 3842:2382 | Nvidia     | TU102 USB Type-C UCSI Con... | 2     |            | 52469C6D63 |
| 10de:1ad9 | 1458:3feb | Nvidia     | TU104 USB Type-C UCSI Con... | 2     | i2c_nvi... | 15A59F41A1 |
| 10de:1ad9 | 1462:3722 | Nvidia     | TU104 USB Type-C UCSI Con... | 2     | nvidia_gpu | C3052C67D6 |
| 10de:1adb | 1043:8670 | Nvidia     | TU106 USB Type-C UCSI Con... | 2     |            | AF6DA5211E |
| 10de:1adb | 10de:1f02 | Nvidia     | TU106 USB Type-C UCSI Con... | 2     | i2c_nvi... | 7B0B66861A |
| 10de:1adb | 1462:3755 | Nvidia     | TU106 USB Type-C UCSI Con... | 2     |            | 1B28CC994F |
| 10de:1adb | 19da:2516 | Nvidia     | TU106 USB Type-C UCSI Con... | 2     | nvidia_gpu | 049AF64F1E |
| 10de:1aed | 10de:1324 | Nvidia     | TU116 [GeForce GTX 1650 S... | 2     |            | ACDD9E30C7 |
| 10de:1aed | 1458:3fc3 | Nvidia     | TU116 [GeForce GTX 1650 S... | 2     | i2c_nvi... | A816D75097 |
| 10de:1aed | 1458:3fc4 | Nvidia     | TU116 [GeForce GTX 1650 S... | 2     | i2c_nvi... | 61D0162DE0 |
| 10de:1aed | 1462:3750 | Nvidia     | TU116 [GeForce GTX 1650 S... | 2     | nvidia_gpu | 755B719CFD |
| 8086:19e0 | 8086:7270 | Intel      | Atom Processor C3000 Seri... | 2     |            | 50B6A72C0C |
| 8086:a324 | 1028:085a | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 3D80EACDFC |
| 8086:a324 | 103c:83e1 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 6FD9BBB997 |
| 8086:a324 | 17aa:3138 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | F3279F9D14 |
| 8086:a324 | 17aa:3140 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 1882F77EFC |
| 8086:a324 | 17aa:36eb | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 9333F6F29B |
| 8086:a368 | 1028:085a | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | 3D80EACDFC |
| 8086:a368 | 17aa:3138 | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | F3279F9D14 |
| 8086:a369 | 17aa:3138 | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | F3279F9D14 |
| 10de:1ad7 | 1028:3718 | Nvidia     | TU102 USB Type-C UCSI Con... | 1     |            | 30EAA0AC0A |
| 10de:1ad7 | 1043:8675 | Nvidia     | TU102 USB Type-C UCSI Con... | 1     |            | 4BF5646944 |
| 10de:1ad7 | 10b0:1e07 | Nvidia     | TU102 USB Type-C UCSI Con... | 1     | nvidia_gpu | FBC1419396 |
| 10de:1ad7 | 10de:12a3 | Nvidia     | TU102 USB Type-C UCSI Con... | 1     |            | 30502C41DE |
| 10de:1ad7 | 1458:37a9 | Nvidia     | TU102 USB Type-C UCSI Con... | 1     |            | 0DB3841C91 |
| 10de:1ad7 | 1462:3711 | Nvidia     | TU102 USB Type-C UCSI Con... | 1     |            | 62128222FA |
| 10de:1ad7 | 1462:3715 | Nvidia     | TU102 USB Type-C UCSI Con... | 1     |            | CE19512CBB |
| 10de:1ad7 | 3842:2487 | Nvidia     | TU102 USB Type-C UCSI Con... | 1     |            | C3DCC51002 |
| 10de:1ad9 | 1043:865f | Nvidia     | TU104 USB Type-C UCSI Con... | 1     |            | B035392AD6 |
| 10de:1ad9 | 1043:8674 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     | i2c_nvi... | 7436C74DCB |
| 10de:1ad9 | 1043:8676 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     |            | 48041296CA |
| 10de:1ad9 | 1043:8712 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     | i2c_nvi... | 6DF8CD9DDD |
| 10de:1ad9 | 10b0:1e87 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     |            | 220759D042 |
| 10de:1ad9 | 10de:12a0 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     |            | D5D160AFDF |
| 10de:1ad9 | 1458:37a8 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     |            | AAD0551E27 |
| 10de:1ad9 | 1458:3fe9 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     | i2c_nvi... | 39B08D0473 |
| 10de:1ad9 | 1462:3723 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     | i2c_nvi... | 6F8CDFC2D5 |
| 10de:1ad9 | 1462:3726 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     |            | 62A28AA523 |
| 10de:1ad9 | 1462:372d | Nvidia     | TU104 USB Type-C UCSI Con... | 1     | i2c_nvi... | F3C2D2ABFE |
| 10de:1ad9 | 1462:c729 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     | i2c_nvi... | 172F18A294 |
| 10de:1ad9 | 19da:1500 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     |            | 982548AE86 |
| 10de:1ad9 | 3842:3287 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     |            | 3DA3A9D9AD |
| 10de:1adb | 1043:866e | Nvidia     | TU106 USB Type-C UCSI Con... | 1     |            | 17D03076DF |
| 10de:1adb | 1043:8671 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     |            | B52FC761F9 |
| 10de:1adb | 1043:868a | Nvidia     | TU106 USB Type-C UCSI Con... | 1     | i2c_nvi... | D61154EABE |
| 10de:1adb | 1043:868e | Nvidia     | TU106 USB Type-C UCSI Con... | 1     | i2c_nvi... | ADEAE621C7 |
| 10de:1adb | 1043:8698 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     |            | 8D6C4235C3 |
| 10de:1adb | 1043:86fc | Nvidia     | TU106 USB Type-C UCSI Con... | 1     |            | 77E21A24B5 |
| 10de:1adb | 10de:12ad | Nvidia     | TU106 USB Type-C UCSI Con... | 1     | i2c_nvi... | 55119E58D9 |
| 10de:1adb | 1458:37c8 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     | i2c_nvi... | 69F2264D39 |
| 10de:1adb | 1458:3fc1 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     | i2c_nvi... | F48FE985CA |
| 10de:1adb | 1458:3fc2 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     |            | 8DF2C93C38 |
| 10de:1adb | 1458:3fc9 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     |            | 154FBBFFD3 |
| 10de:1adb | 1458:3fda | Nvidia     | TU106 USB Type-C UCSI Con... | 1     | i2c_nvi... | F4AAAAC1D8 |
| 10de:1adb | 1462:3734 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     | nvidia_gpu | 856664A31A |
| 10de:1adb | 1462:373d | Nvidia     | TU106 USB Type-C UCSI Con... | 1     | i2c_nvi... | D043FCBC96 |
| 10de:1adb | 196e:130f | Nvidia     | TU106 USB Type-C UCSI Con... | 1     |            | 328F236B37 |
| 10de:1adb | 196e:1314 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     |            | 14943339B4 |
| 10de:1adb | 3842:1071 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     | nvidia_gpu | A9F5B25B8C |
| 10de:1adb | 3842:2062 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     |            | 326792563D |
| 10de:1adb | 3842:2167 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     |            | 32073E3911 |
| 10de:1adb | 3842:2173 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     | i2c_nvi... | 814D24ED49 |
| 10de:1aed | 1028:375d | Nvidia     | TU116 [GeForce GTX 1650 S... | 1     | i2c_nvi... | 282FF6E8DC |
| 10de:1aed | 1043:869f | Nvidia     | TU116 [GeForce GTX 1650 S... | 1     | i2c_nvi... | FCA77FFE03 |
| 10de:1aed | 1043:86a0 | Nvidia     | TU116 [GeForce GTX 1650 S... | 1     |            | 62428F7C52 |
| 10de:1aed | 1043:86a3 | Nvidia     | TU116 [GeForce GTX 1650 S... | 1     | i2c_nvi... | E891AAE560 |
| 10de:1aed | 1043:86a6 | Nvidia     | TU116 [GeForce GTX 1650 S... | 1     |            | C28821415F |
| 10de:1aed | 10de:2182 | Nvidia     | TU116 [GeForce GTX 1650 S... | 1     |            | C4788779C1 |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8c3d | 1458:1c3a | Intel      | 8 Series/C220 Series Chip... | 61    | serial     | 4D53809886 |
| 8086:2e17 | 1028:027f | Intel      | 4 Series Chipset Serial K... | 29    | serial     | 439AF540E7 |
| 8086:29b7 | 1028:0211 | Intel      | 82Q35 Express Serial KT C... | 25    | serial     | E23742C63F |
| 8086:2e17 | 103c:3048 | Intel      | 4 Series Chipset Serial K... | 23    | serial     | 733B76A48E |
| 8086:2e17 | 1028:0420 | Intel      | 4 Series Chipset Serial K... | 22    | serial     | 5151CB704B |
| 8086:2e17 | 1734:114c | Intel      | 4 Series Chipset Serial K... | 20    | serial     | 9632357AEB |
| 8086:3b67 | 8086:0036 | Intel      | 5 Series/3400 Series Chip... | 20    | serial     | A57DCF32AA |
| 8086:8c3d | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 20    | serial     | 01AC5D53D2 |
| 8086:8c3d | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 19    | serial     | E6F6F65F88 |
| 8086:1e3d | 1028:0577 | Intel      | 7 Series/C210 Series Chip... | 17    | serial     | 90FC9AFA3E |
| 8086:1e3d | 103c:3397 | Intel      | 7 Series/C210 Series Chip... | 17    | serial     | E68AA86510 |
| 8086:1e3d | 103c:339a | Intel      | 7 Series/C210 Series Chip... | 16    | serial     | 2962B36D7E |
| 8086:29b7 | 103c:2818 | Intel      | 82Q35 Express Serial KT C... | 16    | serial     | 844CB3BF90 |
| 8086:1c3d | 1028:047e | Intel      | 6 Series/C200 Series Chip... | 15    | serial     | 858ED45F37 |
| 8086:1c3d | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 15    | serial     | 2D378E81BE |
| 8086:2e17 | 103c:3034 | Intel      | 4 Series Chipset Serial K... | 14    | serial     | A40772FC80 |
| 8086:1d3d | 103c:1589 | Intel      | C600/X79 series chipset K... | 13    | serial     | 9D85C4CA60 |
| 8086:2e17 | 17aa:3048 | Intel      | 4 Series Chipset Serial K... | 13    | serial     | 2BFF73F199 |
| 8086:2e17 | 1028:0276 | Intel      | 4 Series Chipset Serial K... | 12    | serial     | C05B5B48DE |
| 8086:8c3d | 103c:18e7 | Intel      | 8 Series/C220 Series Chip... | 12    | serial     | 5A54F0AEAE |
| 9710:9865 | a000:1000 | MosChip... | PCI 9865 Multi-I/O Contro... | 12    | parport_pc | 8D6C4235C3 |
| 8086:1c3d | 103c:1495 | Intel      | 6 Series/C200 Series Chip... | 10    | serial     | D56240BFB5 |
| 8086:1c3d | 103c:1497 | Intel      | 6 Series/C200 Series Chip... | 10    | serial     | 51C0A64A32 |
| 8086:1e3d | 1458:1c3a | Intel      | 7 Series/C210 Series Chip... | 10    | serial     | 508430F6F8 |
| 8086:2e17 | 103c:3646 | Intel      | 4 Series Chipset Serial K... | 10    | serial     | B84B8A2AAE |
| 8086:29b7 | 1043:8295 | Intel      | 82Q35 Express Serial KT C... | 9     | serial     | 9057FD4986 |
| 8086:3b67 | 103c:304b | Intel      | 5 Series/3400 Series Chip... | 9     | serial     | 16542643A0 |
| 8086:1c3d | 103c:1494 | Intel      | 6 Series/C200 Series Chip... | 8     | serial     | B9CA27E33C |
| 8086:1e3d | 1028:052c | Intel      | 7 Series/C210 Series Chip... | 8     | serial     | 779B6B3344 |
| 8086:3b67 | 8086:3b67 | Intel      | 5 Series/3400 Series Chip... | 8     | serial     | 94B8C23EEF |
| 4348:3253 | 4348:3253 | WCH.CN     | CH352 PCI Dual Serial Por... | 7     | serial     | C87B5D73CA |
| 8086:1c3d | 17aa:3077 | Intel      | 6 Series/C200 Series Chip... | 7     | serial     | 6C4701993F |
| 8086:1e3d | 17aa:3084 | Intel      | 7 Series/C210 Series Chip... | 7     | serial     | A08028C506 |
| 8086:29b7 | 103c:2819 | Intel      | 82Q35 Express Serial KT C... | 7     | serial     | 775B90FA5A |
| 8086:8c3d | 103c:1905 | Intel      | 8 Series/C220 Series Chip... | 7     | serial     | F3873460A2 |
| 8086:8c3d | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 7     | serial     | 01F990EA56 |
| 8086:8c3d | 17aa:3097 | Intel      | 8 Series/C220 Series Chip... | 7     | serial     | F1886B084F |
| 9710:9912 | a000:1000 | MosChip... | PCIe 9912 Multi-I/O Contr... | 7     | serial     | 009DCD4A93 |
| 1c00:3250 | 1c00:3250 |            | WCH PCI Express              | 6     | parport... | BBC8B77127 |
| 8086:1c3d | 17aa:3070 | Intel      | 6 Series/C200 Series Chip... | 6     | serial     | 3EB7EB388C |
| 8086:1d3d | 103c:158a | Intel      | C600/X79 series chipset K... | 6     | serial     | BAF893B7F3 |
| 8086:1e3d | 103c:3396 | Intel      | 7 Series/C210 Series Chip... | 6     | serial     | 992938DD51 |
| 8086:29b7 | 17aa:3038 | Intel      | 82Q35 Express Serial KT C... | 6     | serial     | 6DF5762C6A |
| 8086:2e17 | 103c:3035 | Intel      | 4 Series Chipset Serial K... | 6     | serial     | 035BC3CA39 |
| 8086:3b67 | 103c:304a | Intel      | 5 Series/3400 Series Chip... | 6     | serial     | 32EDD7217C |
| 8086:8d3d | 1028:0617 | Intel      | C610/X99 series chipset K... | 6     | serial     | 945E8A152D |
| 1c00:2273 | 1c00:2273 |            | WCH PCI                      | 5     | serial     | 60CA74AFA7 |
| 8086:1e3d | 17aa:3083 | Intel      | 7 Series/C210 Series Chip... | 5     | serial     | 5BE7CC1609 |
| 8086:29b7 | 1734:10fc | Intel      | 82Q35 Express Serial KT C... | 5     | serial     | FBD6F89151 |
| 8086:2e17 | 8086:1003 | Intel      | 4 Series Chipset Serial K... | 5     | serial     | 4E93B3E62B |
| 8086:8c3d | 17aa:30a3 | Intel      | 8 Series/C220 Series Chip... | 5     | serial     | 7CC0E44901 |
| 9710:9835 | 1000:0002 | MosChip... | PCI 9835 Multi-I/O Contro... | 5     | parport... | 1B2C09C7D1 |
| 10ec:816a | 1458:e000 | Realtek... | Virtual COM1                 | 4     |            | 02A7674592 |
| 10ec:816b | 1458:e000 | Realtek... | RealManage COM2              | 4     |            | 02A7674592 |
| 8086:1c3d | 103c:1496 | Intel      | 6 Series/C200 Series Chip... | 4     | serial     | B31E6E7C4B |
| 8086:1c3d | 1458:1c3d | Intel      | 6 Series/C200 Series Chip... | 4     | serial     | EFD11539D3 |
| 8086:1c3d | 8086:2008 | Intel      | 6 Series/C200 Series Chip... | 4     | serial     | A44CE70FF7 |
| 8086:1d3d | 103c:158b | Intel      | C600/X79 series chipset K... | 4     | serial     | 7A65E2F97F |
| 8086:1e3d | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 4     | serial     | 91535E2115 |
| 8086:2997 | 103c:2801 | Intel      | 82Q963/Q965 KT Controller    | 4     | serial     | 3A37DFD543 |
| 8086:29b7 | 1458:29b7 | Intel      | 82Q35 Express Serial KT C... | 4     | serial     | C9D4B4FC2F |
| 8086:2e17 | 103c:3036 | Intel      | 4 Series Chipset Serial K... | 4     | serial     | 628F536295 |
| 8086:2e17 | 17aa:3047 | Intel      | 4 Series Chipset Serial K... | 4     | serial     | 19C99D72BE |
| 8086:3b67 | 1028:02da | Intel      | 5 Series/3400 Series Chip... | 4     | serial     | 5D617B8DE0 |
| 8086:8c3d | 103c:18e4 | Intel      | 8 Series/C220 Series Chip... | 4     | serial     | 169718EC5D |
| 8086:8c3d | 103c:18e5 | Intel      | 8 Series/C220 Series Chip... | 4     | serial     | CD31C1CBC1 |
| 8086:a13d | 1028:06b9 | Intel      | 100 Series/C230 Series Ch... | 4     | serial     | FF3FDCA5BF |
| 9710:9922 | a000:1000 | MosChip... | MCS9922 PCIe Multi-I/O Co... | 4     | serial     | 4FABC3EA5D |
| 10ec:816a | 1734:1178 | Realtek... | Virtual COM1                 | 3     |            | F9847F8DC5 |
| 10ec:816a | 17aa:3089 | Realtek... | Virtual COM1                 | 3     |            | D9A1939AB2 |
| 10ec:816b | 1734:1178 | Realtek... | RealManage COM2              | 3     |            | F9847F8DC5 |
| 10ec:816b | 17aa:3089 | Realtek... | RealManage COM2              | 3     |            | D9A1939AB2 |
| 8086:1d3d | 1028:05d2 | Intel      | C600/X79 series chipset K... | 3     | serial     | 8EAFAB46BF |
| 8086:1e3d | 1849:1e3d | Intel      | 7 Series/C210 Series Chip... | 3     | serial     | E1466EB2EC |
| 8086:29b7 | 103c:281a | Intel      | 82Q35 Express Serial KT C... | 3     | serial     | 6BAC7D5A5D |
| 8086:29b7 | 8086:4f4a | Intel      | 82Q35 Express Serial KT C... | 3     | serial     | E0AA274C72 |
| 8086:2e17 | 17aa:3049 | Intel      | 4 Series Chipset Serial K... | 3     | serial     | BBE905E397 |
| 8086:3b67 | 8086:0037 | Intel      | 5 Series/3400 Series Chip... | 3     | serial     | 64266B67A2 |
| 8086:a13d | 1028:07c5 | Intel      | 100 Series/C230 Series Ch... | 3     | serial     | 8FBA67A719 |
| 8086:a13d | 103c:805d | Intel      | 100 Series/C230 Series Ch... | 3     | serial     | 7EA80B167D |
| 1393:1141 |           | Moxa Te... | Industrio CP-114             | 2     | mxser      | 1F62DD8462 |
| 1415:c158 | 1415:c158 | Oxford ... | OXPCIe952 Dual 16C950 UART   | 2     | serial     | 7D8D500F39 |
| 4348:7053 | 4348:3253 | WCH.CN     | CH353 PCI Dual Serial and... | 2     | parport... | 4ED9F3C61F |
| 8086:1c3d | 1025:0492 | Intel      | 6 Series/C200 Series Chip... | 2     | serial     | 1111158623 |
| 8086:1c3d | 1025:0493 | Intel      | 6 Series/C200 Series Chip... | 2     | serial     | 2F8EDDD53D |
| 8086:1c3d | 103c:1587 | Intel      | 6 Series/C200 Series Chip... | 2     | serial     | E74C8AB762 |
| 8086:1c3d | 103c:1588 | Intel      | 6 Series/C200 Series Chip... | 2     | serial     | 082313CDB6 |
| 8086:1d3d | 1028:0497 | Intel      | C600/X79 series chipset K... | 2     | serial     | 428006990E |
| 8086:1d3d | 17aa:1027 | Intel      | C600/X79 series chipset K... | 2     | serial     | B7463FD8F2 |
| 8086:1d3d | 17aa:1028 | Intel      | C600/X79 series chipset K... | 2     | serial     | 7E1E79D0B1 |
| 8086:1e3d | 1025:066a | Intel      | 7 Series/C210 Series Chip... | 2     | serial     | A26FF47E37 |
| 8086:1e3d | 103c:3398 | Intel      | 7 Series/C210 Series Chip... | 2     | serial     | ED6F4CE9FB |
| 8086:1e3d | 1462:7808 | Intel      | 7 Series/C210 Series Chip... | 2     | serial     | B376B9520B |
| 8086:1e3d | 17aa:102e | Intel      | 7 Series/C210 Series Chip... | 2     | serial     | A5B315D51A |
| 8086:2997 | 103c:2802 | Intel      | 82Q963/Q965 KT Controller    | 2     | serial     | 52CE0D8CDB |
| 8086:2997 | 8086:4f43 | Intel      | 82Q963/Q965 KT Controller    | 2     | serial     | 1847B52353 |
| 8086:29b7 | 17aa:3037 | Intel      | 82Q35 Express Serial KT C... | 2     | serial     | 487FC34F2F |
| 8086:2e17 | 1025:0151 | Intel      | 4 Series Chipset Serial K... | 2     | serial     | C9DE38152E |
| 8086:2e17 | 103c:3647 | Intel      | 4 Series Chipset Serial K... | 2     | serial     | C95D48DB93 |
| 8086:2e17 | 103c:3648 | Intel      | 4 Series Chipset Serial K... | 2     | serial     | 20DFDBF35B |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a379 | 1458:8888 | Intel      | Cannon Lake PCH Thermal C... | 55    | intel_p... | E097415087 |
| 8086:a131 | 1849:a131 | Intel      | 100 Series/C230 Series Ch... | 53    | intel_p... | 0E4F08FCA3 |
| 8086:a131 | 1458:8888 | Intel      | 100 Series/C230 Series Ch... | 45    | intel_p... | 1947D37E81 |
| 8086:a2b1 | 1849:a2b1 | Intel      | 200 Series PCH Thermal Su... | 33    |            | 1BB0C8F064 |
| 8086:a131 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 29    | intel_p... | 53CD422052 |
| 8086:a379 | 1849:a379 | Intel      | Cannon Lake PCH Thermal C... | 28    | intel_p... | B0161E1E77 |
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 22    | process... | E0B82B7FE8 |
| 8086:a131 | 1462:7a15 | Intel      | 100 Series/C230 Series Ch... | 20    | intel_p... | 73BFD283E5 |
| 8086:a2b1 | 1043:873c | Intel      | 200 Series PCH Thermal Su... | 17    |            | 785E45F5BF |
| 8086:8c24 | 1025:0750 | Intel      | 8 Series Chipset Family T... | 12    | intel_p... | 98191D61C3 |
| 8086:1e24 | 1734:11d6 | Intel      | 7 Series/C210 Series Chip... | 11    |            | 086C06ABD4 |
| 8086:8c24 | 1734:11ea | Intel      | 8 Series Chipset Family T... | 11    | intel_p... | 84669A36B5 |
| 8086:a379 | 1025:1238 | Intel      | Cannon Lake PCH Thermal C... | 11    | intel_p... | FF435389C9 |
| 8086:a131 | 1462:7971 | Intel      | 100 Series/C230 Series Ch... | 10    | intel_p... | 88221EFDE1 |
| 8086:2932 | 1043:8277 | Intel      | 82801I (ICH9 Family) Ther... | 9     |            | 9057FD4986 |
| 8086:a160 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 9     | intel_l... | 53CD422052 |
| 8086:a161 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 9     | intel_l... | 53CD422052 |
| 8086:284f | 1734:0000 | Intel      | 82801H (ICH8 Family) Ther... | 7     |            | 82E5D349D1 |
| 8086:3b32 | 8086:3b32 | Intel      | 5 Series/3400 Series Chip... | 7     | intel_ips  | E13730F188 |
| 8086:9d27 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 7     | intel_l... | C96C722A74 |
| 8086:9d31 | 8086:7270 | Intel      | Sunrise Point-LP Thermal ... | 7     | intel_p... | C96C722A74 |
| 8086:a127 | 1462:7982 | Intel      | 100 Series/C230 Series Ch... | 7     | intel_l... | 90B3457F58 |
| 8086:a127 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 7     | intel_l... | 53CD422052 |
| 8086:a131 | 1028:06b9 | Intel      | 100 Series/C230 Series Ch... | 7     | intel_p... | FF3FDCA5BF |
| 8086:a131 | 1462:7982 | Intel      | 100 Series/C230 Series Ch... | 7     | intel_p... | 90B3457F58 |
| 8086:a131 | 1734:121d | Intel      | 100 Series/C230 Series Ch... | 7     | intel_p... | 8E2B5B679E |
| 8086:a160 | 1462:7982 | Intel      | 100 Series/C230 Series Ch... | 7     | intel_l... | 90B3457F58 |
| 8086:a161 | 1462:7982 | Intel      | 100 Series/C230 Series Ch... | 7     | intel_l... | 90B3457F58 |
| 8086:a2a7 | 103c:82f2 | Intel      | 200 Series/Z370 Chipset F... | 7     | intel_l... | 0B8306E086 |
| 8086:a2e0 | 103c:82f2 | Intel      | 200 Series PCH Serial IO ... | 7     | intel_l... | 0B8306E086 |
| 8086:a2e1 | 103c:82f2 | Intel      | 200 Series PCH Serial IO ... | 7     | intel_l... | 0B8306E086 |
| 8086:a379 | 1462:7b98 | Intel      | Cannon Lake PCH Thermal C... | 7     | intel_p... | 947E963CAC |
| 8086:a131 | 1462:7978 | Intel      | 100 Series/C230 Series Ch... | 6     | intel_p... | 8B7204FCBA |
| 8086:a2b1 | 1028:07a1 | Intel      | 200 Series PCH Thermal Su... | 6     |            | 463475CFEE |
| 8086:a2e0 | 1028:07a1 | Intel      | 200 Series PCH Serial IO ... | 6     | intel_l... | 463475CFEE |
| 8086:a379 | 1025:123c | Intel      | Cannon Lake PCH Thermal C... | 6     | intel_p... | EE7C4D9088 |
| 8086:1c24 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 5     |            | E5693EC0DB |
| 8086:31ac | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | EE27CE77C2 |
| 8086:31ae | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | EE27CE77C2 |
| 8086:31b0 | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | EE27CE77C2 |
| 8086:31b2 | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | EE27CE77C2 |
| 8086:31b4 | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | EE27CE77C2 |
| 8086:31b6 | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | EE27CE77C2 |
| 8086:31b8 | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | EE27CE77C2 |
| 8086:31ba | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | EE27CE77C2 |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 5     | intel_l... | E6AC162ADE |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 5     | intel_l... | E6AC162ADE |
| 8086:a127 | 1462:7a99 | Intel      | 100 Series/C230 Series Ch... | 5     | intel_lpss | 0DD69D07BD |
| 8086:a131 | 1028:06b7 | Intel      | 100 Series/C230 Series Ch... | 5     | intel_p... | 714FC444E1 |
| 8086:a131 | 1462:7972 | Intel      | 100 Series/C230 Series Ch... | 5     | intel_p... | 18E48A635B |
| 8086:a131 | 1462:7a99 | Intel      | 100 Series/C230 Series Ch... | 5     |            | 0DD69D07BD |
| 8086:a160 | 1462:7971 | Intel      | 100 Series/C230 Series Ch... | 5     | intel_l... | ED98074061 |
| 8086:a160 | 1462:7a99 | Intel      | 100 Series/C230 Series Ch... | 5     | intel_lpss | 0DD69D07BD |
| 8086:a161 | 1462:7971 | Intel      | 100 Series/C230 Series Ch... | 5     | intel_l... | ED98074061 |
| 8086:a161 | 1462:7a99 | Intel      | 100 Series/C230 Series Ch... | 5     | intel_lpss | 0DD69D07BD |
| 8086:a2b1 | 1462:7a71 | Intel      | 200 Series PCH Thermal Su... | 5     |            | E0585254D8 |
| 8086:a2b1 | 1462:7a72 | Intel      | 200 Series PCH Thermal Su... | 5     |            | 6FCDEEA0DE |
| 8086:a2b1 | 1462:7a74 | Intel      | 200 Series PCH Thermal Su... | 5     |            | E82B5BBC50 |
| 8086:0050 |           | Intel      | Core Processor Thermal Ma... | 4     |            | 4FFA15CD0F |
| 8086:2932 | 15d9:0000 | Intel      | 82801I (ICH9 Family) Ther... | 4     |            | BF5B58520E |
| 8086:318c | 1849:318c | Intel      | Celeron/Pentium Silver Pr... | 4     | proc_th... | 126ABFCD5A |
| 8086:31b4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 4     | intel_lpss | DAEDE56DC8 |
| 8086:31b6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 4     | intel_lpss | DAEDE56DC8 |
| 8086:31b8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 4     | intel_lpss | DAEDE56DC8 |
| 8086:31ba | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 4     | intel_lpss | DAEDE56DC8 |
| 8086:3b32 | 105b:0dd5 | Intel      | 5 Series/3400 Series Chip... | 4     | intel_ips  | BA59EB12D9 |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | E6AC162ADE |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | E6AC162ADE |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | E6AC162ADE |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | E6AC162ADE |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | E6AC162ADE |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | E6AC162ADE |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | E6AC162ADE |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | E6AC162ADE |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | E6AC162ADE |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | E6AC162ADE |
| 8086:a127 | 1462:7971 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_l... | ED98074061 |
| 8086:a131 | 1025:1000 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_p... | 0571C7F3B9 |
| 8086:a131 | 1025:108e | Intel      | 100 Series/C230 Series Ch... | 4     | intel_p... | 34D1BD348B |
| 8086:a131 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_p... | CC599B8A3A |
| 8086:a131 | 1462:7977 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_p... | 2568EDB51D |
| 8086:a131 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_p... | 072B1A0C91 |
| 8086:a131 | 8086:a131 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_p... | 2E35C3E421 |
| 8086:a160 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_l... | CC599B8A3A |
| 8086:a160 | 1462:7972 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_l... | 18E48A635B |
| 8086:a161 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_l... | CC599B8A3A |
| 8086:a161 | 1462:7972 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_l... | 18E48A635B |
| 8086:a2a7 | 1028:0859 | Intel      | 200 Series/Z370 Chipset F... | 4     | intel_l... | B98840B380 |
| 8086:a2b1 | 1462:7a68 | Intel      | 200 Series PCH Thermal Su... | 4     |            | A3E9040CD5 |
| 8086:a2b1 | 1462:7a70 | Intel      | 200 Series PCH Thermal Su... | 4     |            | 85B1AD8BA6 |
| 8086:a2b1 | 1462:7b45 | Intel      | 200 Series PCH Thermal Su... | 4     |            | 4DC55FEE7C |
| 8086:a379 | 1028:085c | Intel      | Cannon Lake PCH Thermal C... | 4     | intel_p... | 90FEDE556D |
| 8086:a379 | 1462:7b17 | Intel      | Cannon Lake PCH Thermal C... | 4     | intel_p... | F4AAAAC1D8 |
| 8086:a379 | 1462:7b33 | Intel      | Cannon Lake PCH Thermal C... | 4     | intel_p... | 5C290C18C9 |
| 8086:1d24 | 1734:11b6 | Intel      | C600/X79 series chipset T... | 3     |            | 961A7ADB3E |
| 8086:31bc | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_lpss | EE27CE77C2 |
| 8086:31be | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_lpss | EE27CE77C2 |
| 8086:31c0 | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_lpss | EE27CE77C2 |
| 8086:31ee | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_lpss | EE27CE77C2 |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 15A0FF2280 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1c22 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 542   | i2c_i801   | 13AF031E5E |
| 1002:4385 | 1002:4385 | AMD        | SBx00 SMBus Controller       | 530   | i2c_pii... | AFDF4A3A9C |
| 8086:27da | 1043:8179 | Intel      | NM10/ICH7 Family SMBus Co... | 447   | i2c_i801   | B9B80DB558 |
| 8086:27da | 1458:5001 | Intel      | NM10/ICH7 Family SMBus Co... | 445   | i2c_i801   | ABA2A5E5E6 |
| 1002:4385 | 1043:8389 | AMD        | SBx00 SMBus Controller       | 406   | i2c_pii... | 3C504F06A2 |
| 8086:1e22 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 385   | i2c_i801   | 91535E2115 |
| 1002:4385 | 1458:4385 | AMD        | SBx00 SMBus Controller       | 369   | i2c_pii... | A056C6C7D5 |
| 8086:8c22 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 364   | i2c_i801   | 15E3126F2C |
| 8086:1c22 | 1458:5001 | Intel      | 6 Series/C200 Series Chip... | 328   | i2c_i801   | EF2DAAC6D3 |
| 8086:3a30 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) SM... | 310   | i2c_i801   | 6949452F0E |
| 8086:1e22 | 1458:5001 | Intel      | 7 Series/C216 Chipset Fam... | 285   | i2c_i801   | 5B67F6ED83 |
| 8086:27da | 1849:27da | Intel      | NM10/ICH7 Family SMBus Co... | 276   | i2c_i801   | 6FDB8DFE61 |
| 1002:4385 |           | AMD        | SBx00 SMBus Controller       | 275   | i2c_pii... | E722D70419 |
| 1002:4385 | 1849:4385 | AMD        | SBx00 SMBus Controller       | 249   | i2c_pii... | 704C328C67 |
| 8086:a123 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 238   | i2c_i801   | B8C562A7E5 |
| 8086:2930 | 1043:8277 | Intel      | 82801I (ICH9 Family) SMBu... | 236   | i2c_i801   | 5EE0F1DB4C |
| 8086:8c22 | 1458:5001 | Intel      | 8 Series/C220 Series Chip... | 228   | i2c_i801   | 502C5D4B04 |
| 10de:03eb | 1849:03eb | Nvidia     | MCP61 SMBus                  | 223   | i2c_nfo... | EC1F6C8A0B |
| 1022:780b | 1022:780b | AMD        | FCH SMBus Controller         | 180   | i2c_piix4  | 0CABEB6C95 |
| 1022:790b | 1043:8747 | AMD        | FCH SMBus Controller         | 178   | i2c_piix4  | 4ED3A4A663 |
| 1022:790b | 1458:5001 | AMD        | FCH SMBus Controller         | 168   | i2c_piix4  | 564EB1FFE4 |
| 8086:3a30 | 1458:5001 | Intel      | 82801JI (ICH10 Family) SM... | 162   | i2c_i801   | 13ACEC4985 |
| 8086:3b30 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 141   | i2c_i801   | E40B76E473 |
| 8086:a123 | 1458:5001 | Intel      | 100 Series/C230 Series Ch... | 138   | i2c_i801   | 4015843475 |
| 8086:1c22 | 1849:1c22 | Intel      | 6 Series/C200 Series Chip... | 135   | i2c_i801   | 2A41C5495D |
| 1022:780b | 1849:780b | AMD        | FCH SMBus Controller         | 132   | i2c_piix4  | 8230399CC0 |
| 8086:2930 | 1458:5001 | Intel      | 82801I (ICH9 Family) SMBu... | 120   | i2c_i801   | D87E2ED1BC |
| 10de:03eb | 1458:0c11 | Nvidia     | MCP61 SMBus                  | 118   | i2c_nfo... | 53DB8982F5 |
| 8086:8c22 | 1849:8c22 | Intel      | 8 Series/C220 Series Chip... | 113   | i2c_i801   | 40DEE920A9 |
| 8086:8ca2 | 1043:8534 | Intel      | 9 Series Chipset Family S... | 105   | i2c_i801   | 1D2014DD53 |
| 1022:790b | 1849:790b | AMD        | FCH SMBus Controller         | 102   | i2c_piix4  | 5E8A739106 |
| 8086:3b30 | 1458:5001 | Intel      | 5 Series/3400 Series Chip... | 98    | i2c_i801   | E60C730AE2 |
| 8086:a2a3 | 1458:5001 | Intel      | 200 Series/Z370 Chipset F... | 92    | i2c_i801   | 8F2ECB882C |
| 8086:a2a3 | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 88    | i2c_i801   | 345BBA3C1F |
| 8086:1e22 | 1849:1e22 | Intel      | 7 Series/C216 Chipset Fam... | 86    | i2c_i801   | E1466EB2EC |
| 8086:8ca2 | 1458:5001 | Intel      | 9 Series Chipset Family S... | 85    | i2c_i801   | 984B3421C1 |
| 8086:8c22 | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 84    | i2c_i801   | FBE43FC861 |
| 10de:03eb | 1043:8234 | Nvidia     | MCP61 SMBus                  | 82    | i2c_nfo... | F3B22A675A |
| 10de:03eb | 1043:83a4 | Nvidia     | MCP61 SMBus                  | 77    | i2c_nfo... | A6BD4DA213 |
| 8086:283e | 1043:81ec | Intel      | 82801H (ICH8 Family) SMBu... | 69    | i2c_i801   | 49BC4A3291 |
| 1002:4385 | 1043:82ef | AMD        | SBx00 SMBus Controller       | 68    | i2c_pii... | 96FD3589B3 |
| 1022:780b | 1043:85ca | AMD        | FCH SMBus Controller         | 64    | i2c_piix4  | 8F93BF715A |
| 10de:0052 | 1043:815a | Nvidia     | CK804 SMBus                  | 62    | i2c_nfo... | FD8F010178 |
| 1022:780b | 1462:7721 | AMD        | FCH SMBus Controller         | 60    | i2c_piix4  | 743F3FF81C |
| 8086:27da | 1462:7529 | Intel      | NM10/ICH7 Family SMBus Co... | 60    | i2c_i801   | 3DCC4EE3D0 |
| 1002:4385 | 1462:7693 | AMD        | SBx00 SMBus Controller       | 59    | i2c_pii... | 9650DD9DCE |
| 1022:790b | 1043:876b | AMD        | FCH SMBus Controller         | 57    | i2c_piix4  | DE065F2CFC |
| 8086:27da | 1462:7592 | Intel      | NM10/ICH7 Family SMBus Co... | 55    | i2c_i801   | E5A422358F |
| 8086:a323 | 1458:5001 | Intel      | Cannon Lake PCH SMBus Con... | 55    | i2c_i801   | E097415087 |
| 8086:a123 | 1849:a123 | Intel      | 100 Series/C230 Series Ch... | 53    | i2c_i801   | 0E4F08FCA3 |
| 8086:a323 | 1043:8694 | Intel      | Cannon Lake PCH SMBus Con... | 53    | i2c_i801   | 0B771C098E |
| 1022:790b | 1849:ffff | AMD        | FCH SMBus Controller         | 47    | i2c_pii... | 50C613C8D6 |
| 10de:03eb | 1462:7309 | Nvidia     | MCP61 SMBus                  | 46    | i2c_nfo... | 93E77F9DC3 |
| 8086:1c22 | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 46    | i2c_i801   | 7FD884E502 |
| 8086:3b30 | 1849:3b30 | Intel      | 5 Series/3400 Series Chip... | 46    | i2c_i801   | F0971CD52C |
| 1022:780b | 1043:8527 | AMD        | FCH SMBus Controller         | 42    | i2c_piix4  | 958F78D7D3 |
| 8086:1d22 | 1043:84ef | Intel      | C600/X79 series chipset S... | 41    | i2c_i801   | 39F22D868E |
| 8086:1e22 | 1462:7758 | Intel      | 7 Series/C216 Chipset Fam... | 41    | i2c_i801   | 6DD3E491F5 |
| 1022:780b | 1458:4385 | AMD        | FCH SMBus Controller         | 40    | i2c_pii... | 46D69646E5 |
| 10de:03eb | 1565:3407 | Nvidia     | MCP61 SMBus                  | 38    | i2c_nfo... | 1004AD3220 |
| 10de:0446 | 1462:7369 | Nvidia     | MCP65 SMBus                  | 38    | i2c_nfo... | 9DF2C0E0DD |
| 10de:0752 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] SMBus  | 38    | i2c_nfo... | AFF249E34F |
| 8086:1c22 | 8086:1c22 | Intel      | 6 Series/C200 Series Chip... | 37    | i2c_i801   | F89781F320 |
| 8086:27da | 1565:3103 | Intel      | NM10/ICH7 Family SMBus Co... | 37    | i2c_i801   | 843A450979 |
| 1022:780b | 1043:866a | AMD        | FCH SMBus Controller         | 36    | i2c_pii... | 22A0854387 |
| 10de:0368 | 1043:8239 | Nvidia     | MCP55 SMBus Controller       | 36    | i2c_nfo... | 44E3D900F5 |
| 1002:4385 | 1565:3700 | AMD        | SBx00 SMBus Controller       | 35    | i2c_pii... | BD59D48011 |
| 8086:1e22 | 1028:0577 | Intel      | 7 Series/C216 Chipset Fam... | 35    | i2c_i801   | 90FC9AFA3E |
| 8086:24d3 | 1043:80a6 | Intel      | 82801EB/ER (ICH5/ICH5R) S... | 35    | i2c_i801   | 387F6AEA89 |
| 8086:27da | 8086:27da | Intel      | NM10/ICH7 Family SMBus Co... | 35    | i2c_i801   | ED8C30E65A |
| 8086:3a60 | 1028:0420 | Intel      | 82801JD/DO (ICH10 Family)... | 35    | i2c_i801   | 5151CB704B |
| 8086:283e | 1028:01da | Intel      | 82801H (ICH8 Family) SMBu... | 33    | i2c_i801   | B54A538301 |
| 8086:8d22 | 1043:8600 | Intel      | C610/X99 series chipset S... | 33    | i2c_i801   | 021596F9B3 |
| 8086:a2a3 | 1849:a2a3 | Intel      | 200 Series/Z370 Chipset F... | 33    | i2c_i801   | 1BB0C8F064 |
| 8086:8ca2 | 1849:8ca2 | Intel      | 9 Series Chipset Family S... | 32    | i2c_i801   | 831FF4B7FC |
| 8086:283e | 1043:81eb | Intel      | 82801H (ICH8 Family) SMBu... | 31    | i2c_i801   | 11FC0E438A |
| 8086:a2a3 | 1043:872f | Intel      | 200 Series/Z370 Chipset F... | 31    | i2c_i801   | 6AA8E0B9B0 |
| 8086:24d3 | 1458:24d2 | Intel      | 82801EB/ER (ICH5/ICH5R) S... | 30    | i2c_i801   | 9463E5625F |
| 1002:4385 | 1043:81ef | AMD        | SBx00 SMBus Controller       | 29    | i2c_pii... | 475ACD13FF |
| 1002:4385 | 1462:7641 | AMD        | SBx00 SMBus Controller       | 29    | i2c_pii... | 56E11FA07C |
| 8086:3a60 | 1028:027f | Intel      | 82801JD/DO (ICH10 Family)... | 29    | i2c_i801   | 439AF540E7 |
| 8086:a123 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 29    | i2c_i801   | 53CD422052 |
| 8086:1c22 | 1462:7680 | Intel      | 6 Series/C200 Series Chip... | 28    | i2c_i801   | E29AC96BDB |
| 8086:2930 | 1028:0211 | Intel      | 82801I (ICH9 Family) SMBu... | 28    | i2c_i801   | E23742C63F |
| 8086:a323 | 1849:a323 | Intel      | Cannon Lake PCH SMBus Con... | 28    | i2c_i801   | B0161E1E77 |
| 1039:0016 |           | Silicon... | SiS961/2/3 SMBus controller  | 27    | i2c_sis96x | 80274F5B0C |
| 10de:0752 | 1849:0752 | Nvidia     | MCP78S [GeForce 8200] SMBus  | 26    | i2c_nfo... | 41F3167FB7 |
| 1022:780b | 1043:84f2 | AMD        | FCH SMBus Controller         | 25    | i2c_piix4  | 875F14ED53 |
| 8086:0f12 | 1849:0f12 | Intel      | Atom Processor E3800 Seri... | 25    | i2c_i801   | F962D4BBF9 |
| 1002:4385 | 1462:7599 | AMD        | SBx00 SMBus Controller       | 24    | i2c_pii... | F0615F7666 |
| 1022:790b | 1462:7a34 | AMD        | FCH SMBus Controller         | 24    | i2c_piix4  | A8017F0E83 |
| 8086:266a | 1043:80a6 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 24    | i2c_i801   | 83592C8857 |
| 8086:27da | 1028:01ad | Intel      | NM10/ICH7 Family SMBus Co... | 24    | i2c_i801   | 21AE6DBDF0 |
| 8086:27da | 8086:d608 | Intel      | NM10/ICH7 Family SMBus Co... | 24    | i2c_i801   | 7F477DA95D |
| 8086:1c22 | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 23    | i2c_i801   | 2D378E81BE |
| 8086:27da | 1019:2683 | Intel      | NM10/ICH7 Family SMBus Co... | 23    | i2c_i801   | 03C909A2C4 |
| 8086:1c22 | 103c:2abf | Intel      | 6 Series/C200 Series Chip... | 22    | i2c_i801   | 4AB14207F1 |
| 8086:3a30 | 1462:7519 | Intel      | 82801JI (ICH10 Family) SM... | 22    | i2c_i801   | 6CC13B6C09 |
| 10de:03eb | 103c:2a6c | Nvidia     | MCP61 SMBus                  | 21    | i2c_nfo... | 6D882902AD |
| 8086:24d3 | 1849:24d0 | Intel      | 82801EB/ER (ICH5/ICH5R) S... | 21    | i2c_i801   | 46CBFD5EE9 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27d8 | 1458:a002 | Intel      | NM10/ICH7 Family High Def... | 375   | snd_hda... | ABA2A5E5E6 |
| 1002:4383 | 1458:a002 | AMD        | SBx00 Azalia (Intel HDA)     | 301   | snd_hda... | EE209BFCD3 |
| 8086:1c20 | 1458:a002 | Intel      | 6 Series/C200 Series Chip... | 268   | snd_hda... | EF2DAAC6D3 |
| 8086:8c20 | 1043:8576 | Intel      | 8 Series/C220 Series Chip... | 268   | snd_hda... | 15E3126F2C |
| 8086:0c0c | 8086:2010 | Intel      | Xeon E3-1200 v3/4th Gen C... | 242   | snd_hda... | 75C292C941 |
| 1002:4383 | 1043:8445 | AMD        | SBx00 Azalia (Intel HDA)     | 236   | snd_hda... | 3C504F06A2 |
| 8086:8c20 | 1458:a002 | Intel      | 8 Series/C220 Series Chip... | 208   | snd_hda... | 502C5D4B04 |
| 13f6:0111 | 13f6:0111 | C-Media... | CMI8738/CMI8768 PCI Audio    | 202   | snd_cmipci | 53D2EF8D02 |
| 8086:1e20 | 1458:a002 | Intel      | 7 Series/C216 Chipset Fam... | 188   | snd_hda... | 5B67F6ED83 |
| 8086:1c20 | 1043:8445 | Intel      | 6 Series/C200 Series Chip... | 184   | snd_hda... | 13AF031E5E |
| 1002:aab0 | 174b:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 175   | snd_hda... | 21A4325DBF |
| 10de:03f0 | 1849:0397 | Nvidia     | MCP61 High Definition Audio  | 174   | snd_hda... | EC1F6C8A0B |
| 1002:aab0 | 1043:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 170   | snd_hda... | 2C202D97E7 |
| 8086:293e | 1043:829f | Intel      | 82801I (ICH9 Family) HD A... | 163   | snd_hda... | 5EE0F1DB4C |
| 8086:1e20 | 1043:8445 | Intel      | 7 Series/C216 Chipset Fam... | 162   | snd_hda... | 535FBF3562 |
| 8086:a170 | 1043:86c7 | Intel      | 100 Series/C230 Series Ch... | 160   | snd_hda... | 6388AF2414 |
| 8086:1c20 | 1043:8415 | Intel      | 6 Series/C200 Series Chip... | 151   | snd_hda... | F66245AEA5 |
| 8086:27d8 | 1849:3662 | Intel      | NM10/ICH7 Family High Def... | 149   | snd_hda... | C0D7396586 |
| 10de:0bea |           | Nvidia     | GF108 High Definition Aud... | 144   | snd_hda... | 843A450979 |
| 1002:4383 | 1043:836c | AMD        | SBx00 Azalia (Intel HDA)     | 141   | snd_hda... | 2902DCE4BA |
| 1022:780d | 1458:a002 | AMD        | FCH Azalia Controller        | 133   | snd_hda... | EAD3059AA0 |
| 8086:0c0c | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 122   | snd_hda... | 1D2014DD53 |
| 10de:0be3 |           | Nvidia     | High Definition Audio Con... | 120   | snd_hda... | 11FC0E438A |
| 1022:780d | 1043:8576 | AMD        | FCH Azalia Controller        | 116   | snd_hda... | 22A0854387 |
| 8086:a170 | 1458:a182 | Intel      | 100 Series/C230 Series Ch... | 116   | snd_hda... | 4015843475 |
| 10de:03f0 | 1458:a002 | Nvidia     | MCP61 High Definition Audio  | 113   | snd_hda... | 53DB8982F5 |
| 8086:3a3e | 1458:a002 | Intel      | 82801JI (ICH10 Family) HD... | 112   | snd_hda... | 6785C105CC |
| 1002:15de | 1002:15de | AMD        | Raven/Raven2/Fenghuang HD... | 108   | snd_hda... | 5BCFE2F1CE |
| 8086:27d8 | 1043:8290 | Intel      | NM10/ICH7 Family High Def... | 108   | snd_hda... | E643B8ED58 |
| 8086:3a3e | 1043:82fe | Intel      | 82801JI (ICH10 Family) HD... | 100   | snd_hda... | A5A715C21F |
| 1002:4383 | 1458:a102 | AMD        | SBx00 Azalia (Intel HDA)     | 99    | snd_hda... | E722D70419 |
| 1002:aab0 | 1458:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 97    | snd_hda... | E1466EB2EC |
| 1002:4383 | 1043:8444 | AMD        | SBx00 Azalia (Intel HDA)     | 96    | snd_hda... | 26465880BF |
| 8086:293e | 1458:a002 | Intel      | 82801I (ICH9 Family) HD A... | 96    | snd_hda... | E818A123C5 |
| 10de:0bee |           | Nvidia     | GF116 High Definition Aud... | 90    | snd_hda... | A644A3A3AD |
| 1002:4383 | 1458:a182 | AMD        | SBx00 Azalia (Intel HDA)     | 89    | snd_hda... | 98A03A61F1 |
| 1002:aab0 | 1787:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 89    | snd_hda... | BA9BCF582F |
| 10de:0e0f | 1462:8c93 | Nvidia     | GK208 HDMI/DP Audio Contr... | 89    | snd_hda... | C51735EE45 |
| 8086:27d8 | 1849:0397 | Intel      | NM10/ICH7 Family High Def... | 83    | snd_hda... | 6FDB8DFE61 |
| 8086:3b56 | 1458:a002 | Intel      | 5 Series/3400 Series Chip... | 83    | snd_hda... | 7E353F1BDA |
| 8086:8c20 | 1462:d817 | Intel      | 8 Series/C220 Series Chip... | 79    | snd_hda... | FBE43FC861 |
| 1002:4383 | 1849:7892 | AMD        | SBx00 Azalia (Intel HDA)     | 77    | snd_hda... | A17808DA56 |
| 1002:aa38 | 174b:aa38 | AMD        | RV710/730 HDMI Audio [Rad... | 76    | snd_hda... | A056C6C7D5 |
| 1002:aa98 | 174b:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 76    | snd_hda... | 522AE798B9 |
| 10de:0be4 |           | Nvidia     | High Definition Audio Con... | 76    | snd_hda... | 7F477DA95D |
| 8086:a2f0 | 1458:a182 | Intel      | 200 Series PCH HD Audio      | 74    | snd_hda... | 8F2ECB882C |
| 1002:aa90 | 174b:aa90 | AMD        | Turks HDMI Audio [Radeon ... | 73    | snd_hda... | B656825800 |
| 1002:aaf0 | 1da2:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 72    | snd_hda... | FA300CEB06 |
| 1022:1457 | 1458:a182 | AMD        | Family 17h (Models 00h-0f... | 70    | snd_hda... | C188CE2FCE |
| 1002:aab0 | 1462:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 69    | snd_hda... | 704C328C67 |
| 1022:1457 | 1043:86c7 | AMD        | Family 17h (Models 00h-0f... | 69    | snd_hda... | 4ED3A4A663 |
| 8086:1e20 | 1458:a014 | Intel      | 7 Series/C216 Chipset Fam... | 69    | snd_hda... | AD56492FB5 |
| 8086:284b | 1043:81ec | Intel      | 82801H (ICH8 Family) HD A... | 68    | snd_hda... | 49BC4A3291 |
| 8086:27d8 | 1043:817f | Intel      | NM10/ICH7 Family High Def... | 66    | snd_hda... | FF854DCB6E |
| 1002:aa58 | 174b:aa58 | AMD        | Juniper HDMI Audio [Radeo... | 65    | snd_hda... | 6949452F0E |
| 1002:aa68 | 174b:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 65    | snd_hda... | F0615F7666 |
| 1022:780d | 1849:7662 | AMD        | FCH Azalia Controller        | 65    | snd_hda... | 8230399CC0 |
| 8086:27d8 | 1043:82ea | Intel      | NM10/ICH7 Family High Def... | 63    | snd_hda... | B9B80DB558 |
| 1102:0007 | 1102:100a | Creativ... | CA0106/CA0111 [SB Live!/A... | 62    | snd_ca0106 | 4795BF2A94 |
| 8086:27d8 | 1043:83a1 | Intel      | NM10/ICH7 Family High Def... | 61    | snd_hda... | E64F670E53 |
| 8086:293e | 1043:8277 | Intel      | 82801I (ICH9 Family) HD A... | 61    | snd_hda... | 550E44C270 |
| 8086:8ca0 | 1458:a182 | Intel      | 9 Series Chipset Family H... | 61    | snd_hda... | 984B3421C1 |
| 8086:27d8 | 1462:7529 | Intel      | NM10/ICH7 Family High Def... | 60    | snd_hda... | 3DCC4EE3D0 |
| 1022:780d | 1462:d721 | AMD        | FCH Azalia Controller        | 59    | snd_hda... | 743F3FF81C |
| 8086:1e20 | 1043:8415 | Intel      | 7 Series/C216 Chipset Fam... | 59    | snd_hda... | 91535E2115 |
| 1002:4383 | 1849:7662 | AMD        | SBx00 Azalia (Intel HDA)     | 58    | snd_hda... | 1581CB5806 |
| 1022:780d | 1458:a182 | AMD        | FCH Azalia Controller        | 58    | snd_hda... | 0CABEB6C95 |
| 1002:4383 | 1043:84fb | AMD        | SBx00 Azalia (Intel HDA)     | 56    | snd_hda... | B38E3E18FC |
| 1002:4383 | 1462:d693 | AMD        | SBx00 Azalia (Intel HDA)     | 56    | snd_hda... | B5C538F345 |
| 1002:4383 | 1043:8436 | AMD        | SBx00 Azalia (Intel HDA)     | 54    | snd_hda... | AFDF4A3A9C |
| 1002:aaf0 | 1462:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 54    | snd_hda... | B5C538F345 |
| 1102:0012 | 1102:0010 | Creativ... | Sound Core3D [Sound Blast... | 54    | snd_hda... | 13ACEC4985 |
| 8086:27d8 | 1462:7592 | Intel      | NM10/ICH7 Family High Def... | 54    | snd_hda... | E5A422358F |
| 1002:aaf8 | 1002:aaf8 | AMD        | Vega 10 HDMI Audio [Radeo... | 53    | snd_hda... | A645A0DA1D |
| 10de:0bea | 1569:0f00 | Nvidia     | GF108 High Definition Aud... | 53    | snd_hda... | 65629CCF94 |
| 10de:0e1b | 1569:0fc6 | Nvidia     | GK107 HDMI Audio Controller  | 53    | snd_hda... | B9B80DB558 |
| 8086:1c20 | 1043:8444 | Intel      | 6 Series/C200 Series Chip... | 53    | snd_hda... | 6592929D60 |
| 1002:aa68 | 1043:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 52    | snd_hda... | 06FB257B53 |
| 1002:aa60 | 174b:aa60 | AMD        | Redwood HDMI Audio [Radeo... | 51    | snd_hda... | 9E89962708 |
| 8086:27d8 | 1043:8445 | Intel      | NM10/ICH7 Family High Def... | 51    | snd_hda... | 9AC5E13707 |
| 1002:aa58 | 1787:aa58 | AMD        | Juniper HDMI Audio [Radeo... | 50    | snd_hda... | 016B4BAE90 |
| 8086:3a3e | 1043:8357 | Intel      | 82801JI (ICH10 Family) HD... | 48    | snd_hda... | 6949452F0E |
| 1002:4383 | 1043:8576 | AMD        | SBx00 Azalia (Intel HDA)     | 47    | snd_hda... | 30EADCE3B1 |
| 1002:aab0 | 1682:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 47    | snd_hda... | C7998D926E |
| 10de:03f0 | 1043:8234 | Nvidia     | MCP61 High Definition Audio  | 47    | snd_hda... | 8EEDF41BAD |
| 1002:4383 | 1458:a014 | AMD        | SBx00 Azalia (Intel HDA)     | 46    | snd_hda... | 3E65C0157C |
| 1002:4383 | 1458:a022 | AMD        | SBx00 Azalia (Intel HDA)     | 46    | snd_hda... | A056C6C7D5 |
| 1022:15e3 | 1043:86c7 | AMD        | Family 17h (Models 10h-1f... | 46    | snd_hda... | DE065F2CFC |
| 10de:0371 | 1043:81f6 | Nvidia     | MCP55 High Definition Audio  | 46    | snd_hda... | 064DD1CCBF |
| 8086:1c20 | 1462:d788 | Intel      | 6 Series/C200 Series Chip... | 46    | snd_hda... | 7FD884E502 |
| 8086:27d8 | 1043:83d4 | Intel      | NM10/ICH7 Family High Def... | 46    | snd_hda... | 71FC19AA7D |
| 1022:15e3 | 1458:a182 | AMD        | Family 17h (Models 10h-1f... | 45    | snd_hda... | 564EB1FFE4 |
| 8086:0c0c | 1849:0c0c | Intel      | Xeon E3-1200 v3/4th Gen C... | 45    | snd_hda... | C6B09D560F |
| 1002:4383 | 1043:841b | AMD        | SBx00 Azalia (Intel HDA)     | 44    | snd_hda... | FF37EF634B |
| 1002:4383 | 1458:a132 | AMD        | SBx00 Azalia (Intel HDA)     | 44    | snd_hda... | 0D6CA866B0 |
| 1002:aa98 | 1043:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 44    | snd_hda... | 2327D3DDB8 |
| 1002:aaf0 | 1682:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 44    | snd_hda... | FC98CE50E1 |
| 10de:0be2 |           | Nvidia     | GT216 HDMI Audio Controller  | 44    | snd_hda... | 5964794E61 |
| 13f6:8788 | 1043:8467 | C-Media... | CMI8788 [Oxygen HD Audio]    | 43    | snd_oxygen | 1A4946F44F |
| 8086:a2f0 | 1043:86c7 | Intel      | 200 Series PCH HD Audio      | 43    | snd_hda... | A3871B3E32 |

### Storage (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1283:8211 | 1043:8138 | Integra... | ITE 8211F Single Channel ... | 27    | pata_it... | 84495E0FB8 |
| 1000:0058 | 1028:1f0e | LSI Log... | SAS1068E PCI-Express Fusi... | 7     | mptsas     | BCA2EBDBAF |
| 1095:3132 | 1095:3132 | Silicon... | SiI 3132 Serial ATA Raid ... | 5     | sata_sil24 | A0F0B2CB3C |
| 1283:8212 | 1043:813a | Integra... | IT8212 Dual channel ATA R... | 4     | pata_it... | 87F8B4B22A |
| 1283:8212 | 105b:0cc0 | Integra... | IT8212 Dual channel ATA R... | 4     | pata_it... | 6311678EE1 |
| 1077:2432 | 1077:0138 | QLogic     | ISP2432-based 4Gb Fibre C... | 3     | qla2xxx    | FB66D16E30 |
| 1283:8211 | 1283:8211 | Integra... | ITE 8211F Single Channel ... | 3     | pata_it... | BF5B58520E |
| 8086:1d6b | 1734:11b6 | Intel      | C602 chipset 4-Port SATA ... | 3     | isci       | 961A7ADB3E |
| 9004:7178 |           | Adaptec    | AIC-7870P/7871 [AHA-2940/... | 3     | aic7xxx    | 87BEA4712A |
| 9005:8017 | 9005:0045 | Adaptec    | ASC-29320ALP U320            | 3     | aic79xx    | A83B0332F1 |
| 1000:0001 |           | LSI Log... | 53c810                       | 2     | sym53c8xx  | C433E6081D |
| 1000:0030 | 103c:322a | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 2     | mptspi     | C156F0AB27 |
| 1000:0058 | 103c:3229 | LSI Log... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | D082929A57 |
| 1000:0070 | 1000:3010 | LSI Log... | SAS2004 PCI-Express Fusio... | 2     | mpt2sas    | 99E743CA9E |
| 105a:4d68 | 105a:4d68 | Promise... | PDC20268 [Ultra100 TX2]      | 2     | pata_pd... | FE1A587527 |
| 1095:3114 | 1043:8136 | Silicon... | SiI 3114 [SATALink/SATARa... | 2     | sata_sil   | 87F8B4B22A |
| 10df:fe00 | 10df:fe00 | Emulex     | Zephyr-X LightPulse Fibre... | 2     | lpfc       | F930BC123E |
| 1de1:0391 | 1de1:0391 | Tekram ... | TRM-S1040 [DC-315 / DC-39... | 2     | dc395x     | BBFFB3F1D1 |
| 9004:8178 |           | Adaptec    | AIC-7870P/7881U [AHA-2940... | 2     | aic7xxx    | 2BAC98B043 |
| 1000:0030 | 1014:1000 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 659D759E6D |
| 1000:0030 | 103c:1500 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 0F22A261A8 |
| 1000:0030 | 103c:3108 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | A2995F5723 |
| 1000:0050 | 103c:3015 | Broadco... | SAS1064 PCI-X Fusion-MPT SAS | 1     | mptsas     | AA051D69D4 |
| 1000:0056 | 103c:322b | LSI Log... | SAS1064ET PCI-Express Fus... | 1     | mptsas     | 7FE1A5394C |
| 1000:0058 | 103c:12fe | LSI Log... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | D740F3D7E5 |
| 1000:0058 | 17aa:101d | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | 18BE0454DD |
| 1000:0059 | 1000:3002 | LSI Log... | MegaRAID SAS 8208ELP/8208ELP | 1     | mptsas     | 2985792735 |
| 1000:0072 | 1000:3060 | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | FB0F30CB65 |
| 1000:0072 | 1000:3080 | LSI Log... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | FFC0ECBF18 |
| 1000:0072 | 1028:1f1d | LSI Log... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | D4B46091B4 |
| 1000:0097 | 1028:0619 | Broadco... | SAS3008 PCI-Express Fusio... | 1     | mpt3sas    | ADB52FAE26 |
| 105a:3d17 | 105a:3d17 | Promise... | PDC40718 (SATA 300 TX4)      | 1     | sata_pr... | E510EC2AB5 |
| 105a:4d69 | 105a:4d68 | Promise... | 20269                        | 1     | pata_pd... | DA5A7A6B37 |
| 1095:3110 | 1095:7110 | Silicon... | SCSI storage controller      | 1     |            | 69BD5A45B3 |
| 1095:3531 | 1095:3531 | Silicon... | SiI 3531 [SATALink/SATARa... | 1     | sata_sil24 | 7386C9D836 |
| 1095:3531 | 1462:320a | Silicon... | SiI 3531 [SATALink/SATARa... | 1     | sata_sil24 | 20519D31C3 |
| 10b9:5289 | 1043:816b | ULi Ele... | ULi 5289 SATA                | 1     | sata_uli   | 1473488491 |
| 10b9:5289 | 1458:b003 | ULi Ele... | ULi 5289 SATA                | 1     | sata_uli   | 72CD950417 |
| 1103:2310 | 11ab:11ab | HighPoi... | RocketRAID 2310 4 Port SA... | 1     | sata_mv    | 353DF9771E |
| 1106:401a | 1028:0408 | VIA Tec... | VIA Card Reader Host Cont... | 1     |            | 3125B9C83A |
| 117c:0042 | 117c:0042 | ATTO Te... | ExpressSAS 6Gb/s SAS/SATA... | 1     | pm80xx     | 2DF53AC534 |
| 1191:8020 | 1191:8020 | Artop E... | AEC6712U SCSI                | 1     | atp870u    | E593748D4E |
| 11ab:6041 | 1043:8150 | Marvell... | MV88SX6041 4-port SATA II... | 1     | sata_mv    | 3FECAFF6C4 |
| 11ab:7042 | 11ab:11ab | Marvell... | 88SX7042 PCI-e 4-port SAT... | 1     | sata_mv    | 675FB21B01 |
| 1217:7130 | 14ff:a003 | O2 Micro   | Integrated MS/xD Controller  | 1     |            | 6647A9CB02 |
| 19a2:0704 | 10df:e602 | Emulex     | OneConnect OCe10100/OCe10... | 1     | lpfc       | 456CDA8C49 |
| 1aed:3002 | 1014:04d3 | SanDisk    | ioMemory HHHL                | 1     |            | FB0D0A1860 |
| 1b85:1221 | 1b85:1221 | OCZ Tec... | OCZ 12xx SCSI Controller     | 1     |            | 323982480D |
| 8086:1d68 | 8086:1d68 | Intel      | C606 chipset Dual 4-Port ... | 1     | isci       | EBA3BBC86D |
| 8086:1d6b |           | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 99E743CA9E |
| 8086:1d6b | 15d9:0628 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | F7519BF7BE |
| 8086:1d6b | 15d9:062c | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 2B1034E588 |
| 8086:1d6b | 17aa:1026 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 5A6C7B0805 |
| 8086:1d6b | 17aa:1027 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 9506CD65EE |
| 9004:6178 |           | Adaptec    | AIC-7861                     | 1     | aic7xxx    | F1A0393BA2 |
| 9004:6178 | 9004:7861 | Adaptec    | AIC-7861                     | 1     | aic7xxx    | D4B46091B4 |
| 9005:8017 | 9005:0044 | Adaptec    | ASC-29320ALP U320            | 1     | aic79xx    | BB914E2D17 |
| 9005:801d | 10f1:2676 | Adaptec    | AIC-7902B U320               | 1     | aic79xx    | 219383F559 |
| ace1:0005 | ace1:0005 |            | Storage controller           | 1     |            | 22F215C605 |
| ace1:0006 | ace1:0006 |            | Storage controller           | 1     |            | EF20304D33 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:4390 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 364   | ahci       | E722D70419 |
| 8086:8c02 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 352   | ahci       | 15E3126F2C |
| 1002:4390 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 331   | ahci       | 3C504F06A2 |
| 1002:4391 | 1043:84dd | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 321   | ahci       | AFDF4A3A9C |
| 8086:1c02 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 288   | ahci       | 13AF031E5E |
| 8086:1e02 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 279   | ahci       | 91535E2115 |
| 1002:4391 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 274   | ahci       | 0D6CA866B0 |
| 1b21:0612 | 1043:84b7 | ASMedia... | ASM1062 Serial ATA Contro... | 236   | ahci       | AFDF4A3A9C |
| 1022:43c8 | 1b21:1062 | AMD        | 400 Series Chipset SATA C... | 235   | ahci       | 5BCFE2F1CE |
| 8086:a102 | 1043:8694 | Intel      | Q170/Q150/B150/H170/H110/... | 233   | ahci       | B8C562A7E5 |
| 8086:8c02 | 1458:b005 | Intel      | 8 Series/C220 Series Chip... | 210   | ahci       | 502C5D4B04 |
| 1022:7901 | 1043:8747 | AMD        | FCH SATA Controller [AHCI... | 178   | ahci       | 4ED3A4A663 |
| 1022:43b7 | 1b21:1062 | AMD        | 300 Series Chipset SATA C... | 166   | ahci       | 4ED3A4A663 |
| 1022:7901 | 1458:b002 | AMD        | FCH SATA Controller [AHCI... | 153   | ahci       | 564EB1FFE4 |
| 8086:1e02 | 1458:b005 | Intel      | 7 Series/C210 Series Chip... | 145   | ahci       | 5B67F6ED83 |
| 1b21:0612 | 1849:0612 | ASMedia... | ASM1062 Serial ATA Contro... | 137   | ahci       | BAFB10A069 |
| 8086:a102 | 1458:b005 | Intel      | Q170/Q150/B150/H170/H110/... | 137   | ahci       | 4015843475 |
| 1002:4391 | 1849:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 135   | ahci       | 704C328C67 |
| 8086:1c02 | 1458:b005 | Intel      | 6 Series/C200 Series Chip... | 122   | ahci       | 6F8237E870 |
| 1022:7801 | 1458:b002 | AMD        | FCH SATA Controller [AHCI... | 119   | ahci       | 646D568712 |
| 1002:4390 | 1849:4390 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 118   | ahci       | A17808DA56 |
| 1022:43b5 | 1b21:1062 | AMD        | X370 Series Chipset SATA ... | 105   | ahci       | 2E60313B01 |
| 8086:8c02 | 1849:8c02 | Intel      | 8 Series/C220 Series Chip... | 104   | ahci       | 40DEE920A9 |
| 1022:7801 | 1849:7801 | AMD        | FCH SATA Controller [AHCI... | 102   | ahci       | 8230399CC0 |
| 197b:2362 | 1043:8460 | JMicron... | JMB362 SATA Controller       | 102   | ahci       | BD3C6A762C |
| 8086:3a22 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) SA... | 101   | ahci       | A30E689A9E |
| 1022:7901 | 1849:7901 | AMD        | FCH SATA Controller [AHCI... | 100   | ahci       | 5E8A739106 |
| 1022:7800 | 1458:b002 | AMD        | FCH SATA Controller [IDE ... | 98    | ahci       | 0CABEB6C95 |
| 8086:8c82 | 1043:8534 | Intel      | 9 Series Chipset Family S... | 98    | ahci       | 1D2014DD53 |
| 1b4b:9172 | 1458:b000 | Marvell... | 88SE9172 SATA 6Gb/s Contr... | 92    | ahci       | 0D6CA866B0 |
| 1022:43b8 | 1b21:1062 | AMD        | FCH SATA Controller D        | 87    | ahci       | 50C613C8D6 |
| 8086:a282 | 1458:b005 | Intel      | 200 Series PCH SATA contr... | 85    | ahci       | 8F2ECB882C |
| 8086:1e02 | 1849:1e02 | Intel      | 7 Series/C210 Series Chip... | 82    | ahci       | E1466EB2EC |
| 8086:a282 | 1043:8694 | Intel      | 200 Series PCH SATA contr... | 80    | ahci       | 345BBA3C1F |
| 1002:4391 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 79    | ahci       | 2902DCE4BA |
| 8086:8c82 | 1458:b005 | Intel      | 9 Series Chipset Family S... | 79    | ahci       | 984B3421C1 |
| 8086:8c02 | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 78    | ahci       | FBE43FC861 |
| 8086:1c02 | 1849:1c02 | Intel      | 6 Series/C200 Series Chip... | 74    | ahci       | 2A41C5495D |
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 72    | ahci       | 50C613C8D6 |
| 1022:7801 | 1043:85ca | AMD        | FCH SATA Controller [AHCI... | 62    | ahci       | 8F93BF715A |
| 1002:4390 | 1002:4390 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 61    | ahci       | 9A42A921E7 |
| 1002:4390 | 1043:82ef | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 61    | ahci       | 96FD3589B3 |
| 1022:7801 | 1462:7721 | AMD        | FCH SATA Controller [AHCI... | 60    | ahci       | 743F3FF81C |
| 1b21:0612 | 1043:858d | ASMedia... | ASM1062 Serial ATA Contro... | 60    | ahci       | 1D2014DD53 |
| 1b21:0612 | 1b21:1060 | ASMedia... | ASM1062 Serial ATA Contro... | 58    | ahci       | B5BA9A13DC |
| 1022:7901 | 1043:876b | AMD        | FCH SATA Controller [AHCI... | 57    | ahci       | DE065F2CFC |
| 1002:4391 | 1002:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 55    | ahci       | 601775E217 |
| 1022:43c8 | 1849:43c8 | AMD        | 400 Series Chipset SATA C... | 53    | ahci       | 0450F1FE8A |
| 8086:a102 | 1849:a102 | Intel      | Q170/Q150/B150/H170/H110/... | 53    | ahci       | 0E4F08FCA3 |
| 8086:a352 | 1458:b005 | Intel      | Cannon Lake PCH SATA AHCI... | 52    | ahci       | E097415087 |
| 8086:3a22 | 1458:b005 | Intel      | 82801JI (ICH10 Family) SA... | 50    | ahci       | DE978F9E41 |
| 1b4b:9130 | 1043:8438 | Marvell... | 88SE9128 PCIe SATA 6 Gb/s... | 49    | ahci       | 7A8CCFD558 |
| 8086:a352 | 1043:8694 | Intel      | Cannon Lake PCH SATA AHCI... | 46    | ahci       | 0B771C098E |
| 8086:3b22 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 45    | ahci       | E40B76E473 |
| 1b4b:9172 | 1043:8477 | Marvell... | 88SE9172 SATA 6Gb/s Contr... | 44    | ahci       | BD3C6A762C |
| 1022:7801 | 1043:8527 | AMD        | FCH SATA Controller [AHCI... | 41    | ahci       | 958F78D7D3 |
| 1002:4390 | 1043:8443 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 40    | ahci       | FF37EF634B |
| 8086:1e02 | 1462:7758 | Intel      | 7 Series/C210 Series Chip... | 40    | ahci       | 6DD3E491F5 |
| 8086:3b22 | 1458:b005 | Intel      | 5 Series/3400 Series Chip... | 37    | ahci       | 7E353F1BDA |
| 8086:1d02 | 1043:84ef | Intel      | C600/X79 series chipset 6... | 36    | ahci       | 39F22D868E |
| 1022:7801 | 1043:866a | AMD        | FCH SATA Controller [AHCI... | 35    | ahci       | 22A0854387 |
| 1002:4380 | 1043:81ef | AMD        | SB600 Non-Raid-5 SATA        | 34    | ahci       | 367A4F2A17 |
| 1002:4391 | 1462:7693 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 34    | ahci       | 9650DD9DCE |
| 8086:1e02 | 1028:0577 | Intel      | 7 Series/C210 Series Chip... | 32    | ahci       | 90FC9AFA3E |
| 1022:43b6 | 1b21:1062 | AMD        | X399 Series Chipset SATA ... | 31    | ahci       | D4813C969B |
| 8086:8c82 | 1849:8c82 | Intel      | 9 Series Chipset Family S... | 31    | ahci       | 831FF4B7FC |
| 8086:a282 | 1849:a282 | Intel      | 200 Series PCH SATA contr... | 30    | ahci       | 1BB0C8F064 |
| 1002:4390 | 1565:3700 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 29    | ahci       | BD59D48011 |
| 8086:a102 | 1462:7996 | Intel      | Q170/Q150/B150/H170/H110/... | 29    | ahci       | 53CD422052 |
| 8086:8d02 | 1043:8600 | Intel      | C610/X99 series chipset 6... | 27    | ahci       | 021596F9B3 |
| 8086:a282 | 1043:872f | Intel      | 200 Series PCH SATA contr... | 27    | ahci       | 6AA8E0B9B0 |
| 8086:a352 | 1849:a352 | Intel      | Cannon Lake PCH SATA AHCI... | 27    | ahci       | B0161E1E77 |
| 1002:4390 | 1462:7693 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 26    | ahci       | CE4954FA0C |
| 1b4b:9215 | 1b4b:9215 | Marvell... | 92xx SATA 6G Controller      | 25    | ahci       | 83659458FD |
| 1002:4390 | 1019:4390 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 24    | ahci       | 461D79E9EB |
| 1022:7800 | 1849:7800 | AMD        | FCH SATA Controller [IDE ... | 24    | ahci       | 0ABB4F0E21 |
| 1022:7901 | 1462:7a34 | AMD        | FCH SATA Controller [AHCI... | 24    | ahci       | A8017F0E83 |
| 8086:3a02 | 1028:027f | Intel      | 82801JD/DO (ICH10 Family)... | 24    | ahci       | 439AF540E7 |
| 1002:4390 | 1462:7641 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 23    | ahci       | BBD22621AA |
| 8086:2922 | 1043:8277 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 23    | ahci       | 1A129F8DB6 |
| 1002:4390 | 1462:7599 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 22    | ahci       | F0615F7666 |
| 1b4b:9123 | 1043:8400 | Marvell... | 88SE9123 PCIe SATA 6.0 Gb... | 21    | ahci       | E5D614C44C |
| 8086:0f23 | 1849:0f23 | Intel      | Atom Processor E3800 Seri... | 21    | ahci       | F962D4BBF9 |
| 8086:3a02 | 103c:3048 | Intel      | 82801JD/DO (ICH10 Family)... | 21    | ahci       | 733B76A48E |
| 1002:4380 | 1458:b002 | AMD        | SB600 Non-Raid-5 SATA        | 20    | ahci       | 1ECED47226 |
| 8086:1c02 | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 20    | ahci       | 2D378E81BE |
| 8086:2922 | 1028:0211 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 20    | ahci       | E23742C63F |
| 8086:8c02 | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 20    | ahci       | 01AC5D53D2 |
| 8086:a102 | 1462:7a15 | Intel      | Q170/Q150/B150/H170/H110/... | 20    | ahci       | 73BFD283E5 |
| 1022:7901 | 1462:7a38 | AMD        | FCH SATA Controller [AHCI... | 18    | ahci       | 924E886E1F |
| 8086:0f23 | 1458:b002 | Intel      | Atom Processor E3800 Seri... | 18    | ahci       | 2AD366F4C0 |
| 8086:8d62 | 1043:8600 | Intel      | C610/X99 series chipset s... | 18    | ahci       | A16A7137A3 |
| 1022:43b8 | 1849:43c8 | AMD        | FCH SATA Controller D        | 17    | ahci       | 901A69EDCC |
| 10de:0ad4 | 1849:0ad4 | Nvidia     | MCP78S [GeForce 8200] AHC... | 17    | ahci       | 41F3167FB7 |
| 1b4b:9128 | 1458:b000 | Marvell... | 88SE9128 PCIe SATA 6 Gb/s... | 17    | ahci       | 9E65D54AC9 |
| 8086:2923 | 1458:b005 | Intel      | 82801IB (ICH9) 4 port SAT... | 17    | ahci       | D87E2ED1BC |
| 1022:7800 | 1043:84f2 | AMD        | FCH SATA Controller [IDE ... | 16    | ahci       | 875F14ED53 |
| 8086:1c02 | 103c:2abf | Intel      | 6 Series/C200 Series Chip... | 16    | ahci       | 4AB14207F1 |
| 8086:1c02 | 1734:11ba | Intel      | 6 Series/C200 Series Chip... | 16    | ahci       | A98F5F102C |
| 8086:1e02 | 103c:3397 | Intel      | 7 Series/C210 Series Chip... | 16    | ahci       | E68AA86510 |

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
| 10de:03ec | 1043:83a4 | Nvidia     | MCP61 IDE                    | 74    | pata_am... | A6BD4DA213 |
| 1002:439c | 1002:439c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 69    | pata_at... | 9A42A921E7 |
| 8086:2920 | 1043:8277 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 69    | ata_pii... | CBDB605C4F |
| 1002:439c | 1043:82ef | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 68    | pata_at... | 96FD3589B3 |
| 8086:1c00 | 1849:1c00 | Intel      | 6 Series/C200 Series Chip... | 65    | ata_pii... | 5DA8F545AA |
| 8086:1c08 | 1849:1c08 | Intel      | 6 Series/C200 Series Chip... | 64    | ata_pii... | 5DA8F545AA |
| 11ab:6101 | 11ab:6101 | Marvell... | 88SE6101/6102 single-port... | 63    | pata_ma... | 41E70BF30B |
| 10de:0053 | 1043:815a | Nvidia     | CK804 IDE                    | 62    | pata_am... | FD8F010178 |
| 10de:0055 | 1043:815a | Nvidia     | CK804 Serial ATA Controller  | 62    | sata_nv... | FD8F010178 |
| 11ab:6121 | 1043:82a2 | Marvell... | 88SE6111/6121 SATA II / P... | 62    | pata_ma... | 5EE0F1DB4C |
| 10de:0054 | 1043:815a | Nvidia     | CK804 Serial ATA Controller  | 61    | sata_nv... | FD8F010178 |
| 8086:3b20 | 1458:b002 | Intel      | 5 Series/3400 Series Chip... | 61    | ata_pii... | E60C730AE2 |
| 8086:3b26 | 1458:b002 | Intel      | 5 Series/3400 Series Chip... | 61    | ata_pii... | E60C730AE2 |
| 8086:27c0 | 1462:7529 | Intel      | NM10/ICH7 Family SATA Con... | 60    | ata_pii... | 3DCC4EE3D0 |
| 8086:2820 | 1043:81ec | Intel      | 82801H (ICH8 Family) 4 po... | 60    | ata_pii... | 49BC4A3291 |
| 8086:2825 | 1043:81ec | Intel      | 82801HR/HO/HH (ICH8R/DO/D... | 60    | ata_pii... | 49BC4A3291 |
| 8086:27df | 1462:7529 | Intel      | 82801G (ICH7 Family) IDE ... | 58    | ata_pii... | 3DCC4EE3D0 |
| 8086:27c0 | 1462:7592 | Intel      | NM10/ICH7 Family SATA Con... | 55    | ata_pii... | E5A422358F |
| 8086:27c0 | 8086:27c0 | Intel      | NM10/ICH7 Family SATA Con... | 54    | ata_pii... | ED8C30E65A |
| 8086:2921 | 1458:b002 | Intel      | 82801IB (ICH9) 2 port SAT... | 54    | ata_pii... | E818A123C5 |
| 8086:27df | 1462:7592 | Intel      | 82801G (ICH7 Family) IDE ... | 53    | ata_pii... | E5A422358F |
| 8086:27df | 8086:27df | Intel      | 82801G (ICH7 Family) IDE ... | 48    | pata_acpi  | ED8C30E65A |
| 10de:03f6 | 1462:7309 | Nvidia     | MCP61 SATA Controller        | 47    | sata_nv... | 93E77F9DC3 |
| 8086:24db | 1043:80a6 | Intel      | 82801EB/ER (ICH5/ICH5R) I... | 44    | ata_pii... | 387F6AEA89 |
| 1002:439c | 1043:8443 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 43    | pata_at... | FF37EF634B |
| 11ab:6121 | 1043:82e0 | Marvell... | 88SE6111/6121 SATA II / P... | 43    | pata_ma... | BF88ECBED4 |
| 8086:2920 | 1458:b002 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 39    | ata_pii... | 01B25A0DED |
| 10de:03ec | 1565:3407 | Nvidia     | MCP61 IDE                    | 38    | pata_am... | 1004AD3220 |
| 10de:03f6 | 1565:5405 | Nvidia     | MCP61 SATA Controller        | 38    | sata_nv... | 1004AD3220 |
| 10de:036e | 1043:8239 | Nvidia     | MCP55 IDE                    | 36    | pata_am... | 44E3D900F5 |
| 10de:037f | 1043:8239 | Nvidia     | MCP55 SATA Controller        | 36    | sata_nv... | 44E3D900F5 |
| 10de:0448 | 1462:7369 | Nvidia     | MCP65 IDE                    | 36    | pata_am... | 9DF2C0E0DD |
| 8086:27c0 | 1565:5202 | Intel      | NM10/ICH7 Family SATA Con... | 36    | ata_piix   | 843A450979 |
| 8086:27df | 1565:3103 | Intel      | 82801G (ICH7 Family) IDE ... | 36    | ata_piix   | 843A450979 |
| 10de:045d | 1462:7369 | Nvidia     | MCP65 SATA Controller        | 35    | pata_ac... | 9DF2C0E0DD |
| 10de:0759 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] IDE    | 35    | pata_am... | AFF249E34F |
| 10de:0ad0 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] SAT... | 35    | pata_ac... | AFF249E34F |
| 8086:3b20 | 1849:3b20 | Intel      | 5 Series/3400 Series Chip... | 35    | ata_pii... | E6B03B7FED |
| 8086:3b26 | 1849:3b26 | Intel      | 5 Series/3400 Series Chip... | 35    | ata_pii... | E6B03B7FED |
| 1002:439c | 1565:3700 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 34    | pata_at... | BD59D48011 |
| 1106:0415 | 1849:0415 | VIA Tec... | VT6415 PATA IDE Host Cont... | 34    | pata_vi... | 4CF5303FDE |
| 197b:2363 | 197b:2363 | JMicron... | JMB363 SATA/IDE Controller   | 34    | ahci       | 9650DD9DCE |
| 197b:2368 | 1043:824f | JMicron... | JMB368 IDE controller        | 34    | pata_jm... | 550E44C270 |
| 1b4b:917a | 1458:b000 | Marvell... | 88SE9172 SATA III 6Gb/s R... | 34    | pata_ac... | E2923BE323 |
| 11ab:6121 | 11ab:6121 | Marvell... | 88SE6111/6121 SATA II / P... | 33    | pata_ma... | 40DD457351 |
| 8086:1c00 | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 33    | ata_pii... | 4BE423D57C |
| 8086:1c08 | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 33    | ata_pii... | 4BE423D57C |
| 8086:2820 | 1028:01da | Intel      | 82801H (ICH8 Family) 4 po... | 33    | pata_acpi  | B54A538301 |
| 8086:2825 | 1028:01da | Intel      | 82801HR/HO/HH (ICH8R/DO/D... | 33    | pata_acpi  | B54A538301 |
| 197b:2368 | 197b:2368 | JMicron... | JMB368 IDE controller        | 32    | pata_jm... | 0A74735DA6 |
| 197b:2361 | 1043:824f | JMicron... | JMB361 AHCI/IDE              | 31    | ahci       | 4060EB4962 |
| 1002:439c | 1462:7641 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 30    | pata_at... | 56E11FA07C |
| 10de:03ec | 10de:cb84 | Nvidia     | MCP61 IDE                    | 30    | pata_am... | C7E1B7CEC0 |
| 1b4b:91a3 | 1458:b000 | Marvell... | 88SE91A3 SATA-600 Controller | 30    | pata_ac... | 03BCF97EF6 |
| 1002:438c | 1043:81ef | AMD        | SB600 IDE                    | 29    | pata_at... | 475ACD13FF |
| 8086:2e16 | 1028:027f | Intel      | 4 Series Chipset PT IDER ... | 29    | ata_gen... | 439AF540E7 |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 209   | nvme       | 5E8A739106 |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 122   | nvme       | E3B6CE369A |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 32    | nvme       | A9F8B1AD35 |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/PC SN720 NV... | 26    | nvme       | E097415087 |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 21    | nvme       | 85B1AD8BA6 |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 20    | nvme       | 562AF84691 |
| 126f:2263 | 126f:2263 | Silicon... | Non-Volatile memory contr... | 19    | nvme       | EBF0A97D73 |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 19    | nvme       | 345BBA3C1F |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 18    | nvme       | C96C722A74 |
| 2646:5008 | 2646:5008 | Kingsto... | Non-Volatile memory contr... | 16    | nvme       | AD51164983 |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 16    | nvme       | 172F18A294 |
| 126f:2262 | 126f:2262 | Silicon... | Non-Volatile memory contr... | 15    | nvme       | 9BFAB5575C |
| 1987:5007 | 1987:5007 | Phison ... | E7 NVMe Controller           | 13    | nvme       | B711749144 |
| 14a4:22f1 | 1b4b:1093 | Lite-On... | M8Pe Series NVMe SSD         | 9     | nvme       | 6DC8D77438 |
| 1b85:6018 | 1b85:6018 | OCZ Tec... | RD400/400A SSD               | 9     | nvme       | ECD7F31C11 |
| c0a9:2263 | c0a9:2263 | Micron/... | P1 NVMe PCIe SSD             | 9     | nvme       | C1C91FE558 |
| 10ec:5762 | 10ec:5762 | Realtek... | Realtek Non-Volatile memo... | 7     | nvme       | 912F4D4453 |
| 14a4:23f1 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 6     | nvme       | A46DB91F65 |
| 15b7:5003 | 15b7:5003 | Sandisk    | WD Black 2018/PC SN520 NV... | 6     | nvme       | FF435389C9 |
| 2646:2263 | 2646:2263 | Kingsto... | Technology Company Non-Vo... | 6     | nvme       | 7E1E79D0B1 |
| 1179:0115 | 1179:0001 | Toshiba... | XG4 NVMe SSD Controller      | 5     | nvme       | B7F06904F7 |
| 15b7:5001 | 1b4b:1093 | Sandisk    | WD Black NVMe SSD            | 5     | nvme       | 052FE8BC17 |
| 1987:5016 | 1987:5016 | Phison ... | E16 PCIe4 NVMe Controller    | 5     | nvme       | 6DF8CD9DDD |
| 8086:0953 | 8086:370d | Intel      | PCIe Data Center SSD         | 5     | nvme       | 7D5ADE4D65 |
| 10ec:5760 | 5760:10ec | Realtek... | Realtek Non-Volatile memo... | 4     | nvme       | 140C1C062E |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 4     | nvme       | FFF26D5712 |
| 1987:5008 | 1987:5008 | Phison ... | NVMe Storage Controller      | 4     | nvme       | 7B13483E17 |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | Non-Volatile memory contr... | 4     | nvme       | 767E0F71E3 |
| 1179:0113 | 1179:0001 | Toshiba... | BG3 NVMe SSD Controller      | 3     | nvme       | 3D80EACDFC |
| 1c5c:1527 | 1c5c:1527 | SK Hynix   | Non-Volatile memory contr... | 3     | nvme       | DA78DC8E90 |
| 1179:011a | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 2     | nvme       | 6F6209A41E |
| 126f:2260 | 126f:2260 | Silicon... | Non-Volatile memory contr... | 2     | nvme       | 902BF4E864 |
| 14a4:2200 | 1b4b:1093 | Lite-On... | Lite-On Non-Volatile memo... | 2     | nvme       | E751AF6E13 |
| 8086:2700 | 8086:3901 | Intel      | Optane SSD 900P Series       | 2     | nvme       | EC48803226 |
| 10ec:5763 | 10ec:5763 | Realtek... | Realtek Non-Volatile memo... | 1     | nvme       | 26C58B5F58 |
| 14a4:9100 | 126f:2263 | Lite-On... | NVMe Controller              | 1     | nvme       | 8F2F1D6173 |
| 1c5c:1284 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 1     | nvme       | 4CC72409B5 |
| 1c5c:1504 | 0100:1093 | SK Hynix   | SC300 512GB M.2 2280 SATA... | 1     | nvme       | B186519684 |
| 2646:2262 | 2646:2262 | Kingsto... | Technology Company Non-Vo... | 1     | nvme       | 44204F310C |
| 8086:0953 | 8086:00e1 | Intel      | PCIe Data Center SSD         | 1     | nvme       | 019BFC3983 |
| 8086:0953 | 8086:3705 | Intel      | PCIe Data Center SSD         | 1     | nvme       | 3F982F3E86 |
| 8086:0953 | 8086:370e | Intel      | PCIe Data Center SSD         | 1     | nvme       | 57804DB2FA |
| 8086:0a54 | 8086:4802 | Intel      | NVMe Datacenter SSD [3DNA... | 1     | nvme       | 093C4071FD |
| 8086:2522 | 8086:3802 | Intel      | NVMe SSD Optane Series Co... | 1     | nvme       | 9EE9F662A8 |
| 8086:2522 | 8086:3810 | Intel      | NVMe SSD Optane Series Co... | 1     | nvme       | 4FABC3EA5D |
| 8086:2700 | 8086:3900 | Intel      | Optane SSD 900P Series       | 1     | nvme       | 6C2E932759 |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1106:3249 | 1106:3249 | VIA Tec... | VT6421 IDE/SATA Controller   | 37    | sata_via   | 3833787EFA |
| 8086:2822 | 1458:b005 | Intel      | SATA Controller [RAID mode]  | 22    | ahci       | CA561AA481 |
| 8086:2822 | 1028:0420 | Intel      | SATA Controller [RAID mode]  | 21    | ahci       | 2EBE664EEF |
| 8086:2822 | 1043:8694 | Intel      | SATA Controller [RAID mode]  | 21    | ahci       | AE2FCE57B5 |
| 1095:3114 | 1095:7114 | Silicon... | SiI 3114 [SATALink/SATARa... | 15    | sata_sil   | 401C11CCD1 |
| 1095:3132 | 1043:819f | Silicon... | SiI 3132 Serial ATA Raid ... | 15    | sata_sil24 | E41DDE12C3 |
| 8086:2822 | 103c:2a6f | Intel      | SATA Controller [RAID mode]  | 15    | ahci       | 5D4F2621EC |
| 1095:3512 | 1095:6512 | Silicon... | SiI 3512 [SATALink/SATARa... | 13    | sata_sil   | F1A5854551 |
| 8086:2822 | 103c:1309 | Intel      | SATA Controller [RAID mode]  | 13    | ahci       | 3F2B4E103F |
| 1106:3164 | 1106:3164 | VIA Tec... | VT6410 ATA133 RAID contro... | 11    | pata_vi... | 585D8319DA |
| 8086:2822 | 1028:05a4 | Intel      | SATA Controller [RAID mode]  | 11    | ahci       | E6F6F65F88 |
| 8086:2822 | 1458:b000 | Intel      | SATA Controller [RAID mode]  | 11    | ahci       | FCE6EE28A9 |
| 8086:2822 | 1028:047e | Intel      | SATA Controller [RAID mode]  | 10    | ahci       | 858ED45F37 |
| 8086:2822 | 1043:8534 | Intel      | SATA Controller [RAID mode]  | 10    | ahci       | E93453380A |
| 1002:4392 | 1025:0444 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 8     | ahci       | 99825EFDBE |
| 1095:3112 | 1095:6112 | Silicon... | SiI 3112 [SATALink/SATARa... | 8     | sata_sil   | 73AE259285 |
| 1106:3149 | 1043:80ed | VIA Tec... | VIA VT6420 SATA RAID Cont... | 8     | sata_via   | D20509CA50 |
| 8086:2822 | 1028:0293 | Intel      | SATA Controller [RAID mode]  | 8     | ahci       | 952E382624 |
| 1095:3132 | 1095:7132 | Silicon... | SiI 3132 Serial ATA Raid ... | 7     | sata_sil24 | 83413EEEDF |
| 13c1:1004 | 13c1:1004 | 3ware      | 9650SE SATA-II RAID PCIe     | 7     | 3w_9xxx    | B2DA218FF6 |
| 8086:2822 | 103c:130a | Intel      | SATA Controller [RAID mode]  | 7     | ahci       | F90C879481 |
| 8086:2822 | 103c:2a9c | Intel      | SATA Controller [RAID mode]  | 7     | ahci       | B897AD01AD |
| 8086:2822 | 1043:84ca | Intel      | SATA Controller [RAID mode]  | 7     | ahci       | 889648300B |
| 8086:2826 | 103c:1589 | Intel      | C600/X79 series chipset S... | 7     | ahci       | 9D85C4CA60 |
| 1039:0180 | 1043:810e | Silicon... | RAID bus controller 180 S... | 6     | sata_sis   | BF1A9BA973 |
| 1283:8212 | 1283:0001 | Integra... | IT8212 Dual channel ATA R... | 6     | pata_it... | 38F4BB47C3 |
| 8086:2822 | 1043:844d | Intel      | SATA Controller [RAID mode]  | 6     | ahci       | C7951A3833 |
| 1002:4393 | 1043:84df | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 5     | ahci       | 747D9B1FD2 |
| 1095:0680 | 1095:3680 | Silicon... | PCI0680 Ultra ATA-133 Hos... | 5     | pata_si... | 3686BB6AC0 |
| 10b9:5287 | 1043:8056 | ULi Ele... | ULi 5287 SATA                | 5     | sata_uli   | 399101B245 |
| 1283:8212 |           | Integra... | IT8212 Dual channel ATA R... | 5     | pata_it... | 550E44C270 |
| 8086:2682 | 103c:1307 | Intel      | 631xESB/632xESB SATA RAID... | 5     | ahci       | B5BA9A13DC |
| 8086:2822 | 1025:0389 | Intel      | SATA Controller [RAID mode]  | 5     | ahci       | A4BB2D6329 |
| 8086:2822 | 1028:052c | Intel      | SATA Controller [RAID mode]  | 5     | ahci       | 636FBFDCB6 |
| 8086:2822 | 103c:1905 | Intel      | SATA Controller [RAID mode]  | 5     | ahci       | F3873460A2 |
| 8086:2822 | 8086:514d | Intel      | SATA Controller [RAID mode]  | 5     | ahci       | 7409A9492F |
| 1002:4393 | 1002:4393 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 4     | ahci       | E3E631B2A3 |
| 1022:43bd | 1b21:1062 | AMD        | FCH RAID Controller          | 4     |            | 2ED5B5AFC5 |
| 1022:7916 | 1022:7901 | AMD        | RS690 PCI to PCI Bridge (... | 4     | ahci       | 40061999CC |
| 1039:0180 | 1458:b003 | Silicon... | RAID bus controller 180 S... | 4     | sata_sis   | 967BB75CBB |
| 105a:3373 | 1043:80f5 | Promise... | PDC20378 (FastTrak 378/SA... | 4     | sata_pr... | E75F4538BC |
| 1095:3114 | 1095:6114 | Silicon... | SiI 3114 [SATALink/SATARa... | 4     | sata_sil   | 34B91208C5 |
| 8086:2822 | 1025:0427 | Intel      | SATA Controller [RAID mode]  | 4     | ahci       | AE38CF07EA |
| 8086:2822 | 1028:01db | Intel      | SATA Controller [RAID mode]  | 4     | ahci       | A309FDA4F4 |
| 8086:2822 | 1028:026e | Intel      | SATA Controller [RAID mode]  | 4     | ahci       | 0E66E03CAC |
| 8086:2822 | 1028:02da | Intel      | SATA Controller [RAID mode]  | 4     | ahci       | 5D617B8DE0 |
| 8086:2822 | 1028:05a6 | Intel      | SATA Controller [RAID mode]  | 4     | ahci       | 39B61C280E |
| 8086:2822 | 1028:0859 | Intel      | SATA Controller [RAID mode]  | 4     | ahci       | B98840B380 |
| 8086:2826 | 103c:158a | Intel      | C600/X79 series chipset S... | 4     | ahci       | FC47BED30D |
| 1000:0073 | 1028:1f78 | LSI Log... | MegaRAID SAS 2008 [Falcon]   | 3     | megarai... | 4683A284A4 |
| 1002:4392 | 103c:2a92 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 3     | ahci       | 49AE7CD372 |
| 1002:4393 | 1849:4393 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 3     | ahci       | D2B8C394E0 |
| 1095:3124 | 1095:7124 | Silicon... | SiI 3124 PCI-X Serial ATA... | 3     | sata_sil24 | CFC42EAC60 |
| 1095:3132 | 1043:8177 | Silicon... | SiI 3132 Serial ATA Raid ... | 3     | sata_sil24 | 84495E0FB8 |
| 1106:3149 | 1462:7104 | VIA Tec... | VIA VT6420 SATA RAID Cont... | 3     | sata_vi... | C433E6081D |
| 8086:27c3 | 103c:280c | Intel      | 82801GR/GDH (ICH7R/ICH7DH... | 3     | ahci       | FA9C3D044F |
| 8086:27c3 | 1043:2604 | Intel      | 82801GR/GDH (ICH7R/ICH7DH... | 3     | ahci       | 84495E0FB8 |
| 8086:2822 | 1025:023c | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | 91C92A4465 |
| 8086:2822 | 1025:024c | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | A2DBF52E17 |
| 8086:2822 | 1025:0589 | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | 838EE46987 |
| 8086:2822 | 1028:01dd | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | 9BD54A84F0 |
| 8086:2822 | 1028:0276 | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | 6FB69EBDA7 |
| 8086:2822 | 1028:04aa | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | DBCEC87FCF |
| 8086:2822 | 1028:05d7 | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | 2272E1FA1D |
| 8086:2822 | 1028:064c | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | E1BABF19AD |
| 8086:2822 | 1028:06b9 | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | FF3FDCA5BF |
| 8086:2822 | 1028:07a1 | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | 3D49D8B058 |
| 8086:2822 | 1028:07c5 | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | 8FBA67A719 |
| 8086:2822 | 103c:1308 | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | 1787C13656 |
| 8086:2822 | 103c:130b | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | 269249911A |
| 8086:2822 | 1043:82d4 | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | 90A5BB3F2D |
| 8086:2822 | 1043:872f | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | BBAA313D83 |
| 8086:2822 | 1849:a282 | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | 67FA1C4688 |
| 8086:2826 | 1028:0617 | Intel      | C600/X79 series chipset S... | 3     | ahci       | 3B5017848A |
| 1000:005d | 1000:9363 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 2     | megarai... | 2B1034E588 |
| 1000:1960 | 1000:4523 | LSI Log... | MegaRAID                     | 2     | megarai... | 97CC3C4274 |
| 1002:4392 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 2     | ahci       | 4F578CF2C6 |
| 1002:4392 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 2     | ahci       | 791EBD9FDE |
| 1002:4393 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 2     | ahci       | 1D1DFCC8E6 |
| 1039:0180 | 105b:0c56 | Silicon... | RAID bus controller 180 S... | 2     | sata_si... | C8C5CF4F19 |
| 1039:0180 | 1462:7103 | Silicon... | RAID bus controller 180 S... | 2     | sata_sis   | 75102B0383 |
| 103c:3238 | 103c:3211 | Hewlett... | Smart Array E200i (SAS Co... | 2     | hpsa       | 96AE8D3618 |
| 103c:323a | 103c:3245 | Hewlett... | Smart Array G6 controllers   | 2     | hpsa       | 8E0C4F7DB2 |
| 1095:3114 | 1043:8167 | Silicon... | SiI 3114 [SATALink/SATARa... | 2     | sata_sil   | DEE3D2BDAA |
| 10de:0266 | 1028:0249 | Nvidia     | MCP51 Serial ATA Controller  | 2     | sata_nv    | 713C36EFA0 |
| 10de:0267 | 1028:0249 | Nvidia     | MCP51 Serial ATA Controller  | 2     | sata_nv    | 713C36EFA0 |
| 10de:0abc | 1025:0168 | Nvidia     | MCP79 RAID Controller        | 2     | ahci       | 5443C8EC11 |
| 1106:3149 | 1462:7142 | VIA Tec... | VIA VT6420 SATA RAID Cont... | 2     | sata_via   | 4037234F60 |
| 11ab:6145 | 1043:8220 | Marvell... | 88SE6145 SATA II PCI-E co... | 2     | pata_ma... | CF7CA7E96C |
| 11ab:6440 | 1043:82e4 | Marvell... | 88SE6440 SAS/SATA PCIe co... | 2     | mvsas      | F81A55F416 |
| 8086:2682 | 103c:1306 | Intel      | 631xESB/632xESB SATA RAID... | 2     | ahci       | E68759AA8E |
| 8086:27c3 | 1028:01de | Intel      | 82801GR/GDH (ICH7R/ICH7DH... | 2     | ahci       | 2D447D5FC7 |
| 8086:27c3 | 103c:2a50 | Intel      | 82801GR/GDH (ICH7R/ICH7DH... | 2     | ahci       | 107A895F01 |
| 8086:27c3 | 103c:2a5e | Intel      | 82801GR/GDH (ICH7R/ICH7DH... | 2     | ahci       | ACD81F03F2 |
| 8086:2822 | 1025:0491 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | DD9CD8B1C7 |
| 8086:2822 | 1025:123c | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 6EEC9C83FA |
| 8086:2822 | 1028:06b7 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 714FC444E1 |
| 8086:2822 | 1028:072b | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | F967633275 |
| 8086:2822 | 103c:1587 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | E74C8AB762 |
| 8086:2822 | 103c:1588 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 082313CDB6 |

### Storage/sas (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1d6b | 103c:1589 | Intel      | C602 chipset 4-Port SATA ... | 15    | isci       | 9D85C4CA60 |
| 8086:1d6b | 103c:158a | Intel      | C602 chipset 4-Port SATA ... | 8     | isci       | BAF893B7F3 |
| 1000:0086 | 103c:158b | Broadco... | SAS2308 PCI-Express Fusio... | 4     | mpt3sas    | 7A65E2F97F |
| 8086:1d6b | 103c:158b | Intel      | C602 chipset 4-Port SATA ... | 4     | isci       | 7A65E2F97F |
| 1000:0072 | 1000:3020 | LSI Log... | SAS2008 PCI-Express Fusio... | 2     | mpt3sas    | 039AFB9C35 |
| 1000:0072 | 1028:1f1c | LSI Log... | SAS2008 PCI-Express Fusio... | 2     | mpt3sas    | F736E40F50 |
| 1000:0087 | 1028:05a1 | Broadco... | SAS2308 PCI-Express Fusio... | 2     | mpt3sas    | C7E1E32971 |
| 1000:0097 | 1734:1214 | LSI Log... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | 3C409E3FAC |
| 8086:1d6b | 1028:0497 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | F1D5B6204E |
| 8086:1d6b | 17aa:1028 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 7E1E79D0B1 |
| 8086:1d6b | 1849:1d6b | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 2021C0A4A3 |
| 1000:0086 | 1000:0086 | LSI Log... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | 1B28CC994F |
| 1000:0086 | 15d9:0691 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | 9F3D443A21 |
| 1000:0097 | 1000:30a0 | Broadco... | SAS3008 PCI-Express Fusio... | 1     | mpt3sas    | E43A13CE79 |
| 8086:1d6a | 17aa:1027 | Intel      | C600/X79 series chipset D... | 1     | isci       | B7463FD8F2 |
| 8086:1d6b | 15d9:0709 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 9F3D443A21 |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1000:0058 | 1028:021d | LSI Log... | SAS1068E PCI-Express Fusi... | 5     | mptsas     | 82F1FBFA97 |
| 1000:0058 | 103c:130b | LSI Log... | SAS1068E PCI-Express Fusi... | 4     | mptsas     | 269249911A |
| 1000:0054 | 1028:1f08 | LSI Log... | SAS1068 PCI-X Fusion-MPT SAS | 3     | mptsas     | CB363A3342 |
| 1b85:1021 | 1b85:1021 | OCZ Tec... | OCZ SCSI storage controller  | 3     | mvsas      | 6592929D60 |
| 1000:0030 | 103c:12f1 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 2     | mptspi     | 21D968D1E3 |
| 1000:0054 | 103c:0a98 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 2     | mptsas     | E68759AA8E |
| 1000:0056 | 1000:3090 | LSI Log... | SAS1064ET PCI-Express Fus... | 2     | mptsas     | 43427B2365 |
| 10cd:1300 | 10cd:1310 | Advance... | ASC1300 / ASC3030 [ABP940... | 2     | advansys   | 9978BC1A13 |
| 9004:5078 | 9004:7850 | Adaptec    | AIC-7850T/7856T [AVA-2902... | 2     | aic7xxx    | 5A21D12B42 |
| 1000:0030 | 1000:50c0 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | CE615294BF |
| 1000:0058 | 1028:1f10 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | F3E244219B |
| 1000:0058 | 1734:1130 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | 9404AF19C5 |
| 9004:5078 |           | Adaptec    | AIC-7850T/7856T [AVA-2902... | 1     | aic7xxx    | 50F010B8B5 |
| 9005:0010 | 9005:2180 | Adaptec    | AHA-2940U2/U2W               | 1     | aic7xxx    | 63F518652D |
| 9005:0080 | 9005:62a0 | Adaptec    | AIC-7892A U160/m             | 1     | aic7xxx    | 91524AD5FC |
| 9005:8012 | 9005:0042 | Adaptec    | ASC-29320 U320               | 1     | aic79xx    | 0ED86DABCC |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2576 |           | Intel      | 82865G/PE/P Processor to ... | 179   |            | 46CBFD5EE9 |
| 8086:d150 |           | Intel      | Core Processor QPI Link      | 141   |            | E40B76E473 |
| 8086:d151 |           | Intel      | Core Processor QPI Routin... | 141   |            | E40B76E473 |
| 8086:d158 |           | Intel      | Core Processor Miscellane... | 141   |            | E40B76E473 |
| 8086:1911 | 1458:5000 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 88    |            | 8F2ECB882C |
| 8086:d156 |           | Intel      | Core Processor Semaphore ... | 73    |            | 3CDEB04C0D |
| 8086:d155 |           | Intel      | Core Processor System Man... | 72    |            | 3CDEB04C0D |
| 8086:d157 |           | Intel      | Core Processor System Con... | 72    |            | 3CDEB04C0D |
| 8086:d155 | 0043:0083 | Intel      | Core Processor System Man... | 69    |            | E40B76E473 |
| 8086:d156 | 0043:0083 | Intel      | Core Processor Semaphore ... | 69    |            | E40B76E473 |
| 8086:d157 | 0043:0083 | Intel      | Core Processor System Con... | 69    |            | E40B76E473 |
| 8086:2f6e |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 65    |            | 021596F9B3 |
| 8086:2f6f |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 65    |            | 021596F9B3 |
| 8086:2f88 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 65    |            | 021596F9B3 |
| 8086:2f8a |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 65    |            | 021596F9B3 |
| 8086:2fae |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 65    |            | 021596F9B3 |
| 8086:2faf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 65    |            | 021596F9B3 |
| 8086:2fb8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 65    |            | 021596F9B3 |
| 8086:2fb9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 65    |            | 021596F9B3 |
| 8086:2fba |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 65    |            | 021596F9B3 |
| 8086:2fbb |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 65    |            | 021596F9B3 |
| 8086:2fbe |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 65    |            | 021596F9B3 |
| 8086:2fbf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 65    |            | 021596F9B3 |
| 8086:2ff8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 65    |            | 021596F9B3 |
| 8086:2ff9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 65    |            | 021596F9B3 |
| 8086:2f1d | 8086:2f1d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | 021596F9B3 |
| 8086:2f1e | 8086:2f1e | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | 021596F9B3 |
| 8086:2f1f | 8086:2f1f | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | 021596F9B3 |
| 8086:2f71 | 8086:2f71 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | 021596F9B3 |
| 8086:2f98 | 8086:2f98 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | 021596F9B3 |
| 8086:2f99 | 8086:2f99 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | 021596F9B3 |
| 8086:2f9a | 8086:2f9a | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | 021596F9B3 |
| 8086:2f9c | 8086:2f9c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | 021596F9B3 |
| 8086:2fa0 | 8086:2fa0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    | sb_edac    | 021596F9B3 |
| 8086:2fa8 | 8086:2fa8 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | 021596F9B3 |
| 8086:2faa | 8086:2faa | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | 021596F9B3 |
| 8086:2fab | 8086:2fab | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | 021596F9B3 |
| 8086:2fb0 | 8086:2fb0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    | hswep_u... | 021596F9B3 |
| 8086:2fb1 | 8086:2fb1 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    | hswep_u... | 021596F9B3 |
| 8086:2fb2 | 8086:2fb2 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | 021596F9B3 |
| 8086:2fb3 | 8086:2fb3 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    |            | 021596F9B3 |
| 8086:2fc0 | 8086:2fc0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 59    | hswep_u... | 021596F9B3 |
| 8086:2f68 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 57    |            | 021596F9B3 |
| 8086:2fd0 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 57    | hswep_u... | 021596F9B3 |
| 8086:2fac | 8086:2fac | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 53    |            | 021596F9B3 |
| 8086:2fad | 8086:2fad | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 53    |            | 021596F9B3 |
| 8086:2fb4 | 8086:2fb4 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 53    | hswep_u... | 021596F9B3 |
| 8086:2fb5 | 8086:2fb5 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 53    | hswep_u... | 021596F9B3 |
| 8086:2fb6 | 8086:2fb6 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 53    |            | 021596F9B3 |
| 8086:2fb7 | 8086:2fb7 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 53    |            | 021596F9B3 |
| 8086:2f81 | 8086:2f81 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 51    |            | 021596F9B3 |
| 8086:2fe0 | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 51    |            | 021596F9B3 |
| 8086:2fe1 | 8086:2fe1 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 51    |            | 021596F9B3 |
| 8086:2fe2 | 8086:2fe2 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 51    |            | 021596F9B3 |
| 8086:2fe3 | 8086:2fe3 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 51    |            | 021596F9B3 |
| 8086:2ffc | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 51    |            | 021596F9B3 |
| 8086:2ffd | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 51    |            | 021596F9B3 |
| 8086:2ffe | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 51    |            | 021596F9B3 |
| 8086:2fbc |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 45    |            | 021596F9B3 |
| 8086:2fbd |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 45    |            | 021596F9B3 |
| 8086:2f28 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 44    |            | 021596F9B3 |
| 8086:2f29 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 44    |            | 021596F9B3 |
| 8086:2f2a |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 44    |            | 021596F9B3 |
| 8086:2fe4 | 8086:2fe4 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 42    |            | 021596F9B3 |
| 8086:2fe5 | 8086:2fe5 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 42    |            | 021596F9B3 |
| 8086:0e71 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 29    |            | 8EAFAB46BF |
| 8086:0e81 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 29    |            | 8EAFAB46BF |
| 8086:1911 | 1462:7996 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 29    |            | 53CD422052 |
| 8086:2016 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 29    |            | 0217F128CA |
| 8086:2018 | 8086:0000 | Intel      | Sky Lake-E M2PCI Registers   | 29    |            | 0217F128CA |
| 8086:2021 | 8086:0000 | Intel      | Sky Lake-E CBDMA Registers   | 29    | ioatdma    | 0217F128CA |
| 8086:2025 |           | Intel      | Sky Lake-E RAS               | 29    |            | 0217F128CA |
| 8086:2035 |           | Intel      | Sky Lake-E RAS Configurat... | 29    |            | 0217F128CA |
| 8086:2040 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 29    |            | 0217F128CA |
| 8086:2041 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 29    |            | 0217F128CA |
| 8086:2042 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 29    | skx_uncore | 0217F128CA |
| 8086:2043 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 29    |            | 0217F128CA |
| 8086:2044 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 29    |            | 0217F128CA |
| 8086:2045 | 8086:0000 | Intel      | Sky Lake-E LM Channel 1      | 29    |            | 0217F128CA |
| 8086:2046 | 8086:0000 | Intel      | Sky Lake-E LMS Channel 1     | 29    | skx_uncore | 0217F128CA |
| 8086:2047 | 8086:0000 | Intel      | Sky Lake-E LMDP Channel 1    | 29    |            | 0217F128CA |
| 8086:2048 | 8086:0000 | Intel      | Sky Lake-E DECS Channel 2    | 29    |            | 0217F128CA |
| 8086:2049 | 8086:0000 | Intel      | Sky Lake-E LM Channel 2      | 29    |            | 0217F128CA |
| 8086:204a | 8086:0000 | Intel      | Sky Lake-E LMS Channel 2     | 29    | skx_uncore | 0217F128CA |
| 8086:204b | 8086:0000 | Intel      | Sky Lake-E LMDP Channel 2    | 29    |            | 0217F128CA |
| 8086:204e | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 29    | skx_uncore | 0217F128CA |
| 8086:2054 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 29    |            | 0217F128CA |
| 8086:2055 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 29    |            | 0217F128CA |
| 8086:2056 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 29    |            | 0217F128CA |
| 8086:2057 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 29    |            | 0217F128CA |
| 8086:2066 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 29    | skx_uncore | 0217F128CA |
| 8086:2080 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 29    |            | 0217F128CA |
| 8086:2081 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 29    |            | 0217F128CA |
| 8086:2082 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 29    |            | 0217F128CA |
| 8086:2083 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 29    |            | 0217F128CA |
| 8086:2084 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 29    |            | 0217F128CA |
| 8086:2085 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 29    |            | 0217F128CA |
| 8086:2086 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 29    |            | 0217F128CA |
| 8086:208d | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 29    |            | 0217F128CA |
| 8086:208e | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 29    |            | 0217F128CA |

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
| 1131:7133 | 1461:f636 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | A1228CD6CC |
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
| 14f1:8800 | 0070:6906 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | BCEE476272 |
| 14f1:8800 | 14f1:0084 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | 9214D5AED4 |
| 14f1:8800 | 17de:08b2 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | 5E5236F775 |
| 14f1:8800 | 1822:0023 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | AB36F565A4 |
| 14f1:8800 | 8922:8888 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | ADF2D5DACA |
| 14f1:8800 | b022:3022 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | AA10363A06 |
| 14f1:8800 | b033:3033 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | 1C7923E9B3 |
| 14f1:8800 | d460:9022 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | FE55ACD2A2 |
| 14f1:8800 | ffff:ffff | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx8800     | 6C9247C5EB |
| 14f1:8801 | ffff:ffff | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx88_alsa  | 6C9247C5EB |

### Unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:31a2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_i... | 55981AF24A |

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
| 1b21:1042 | 1043:8488 | ASMedia... | ASM1042 SuperSpeed USB Ho... | 582   | xhci_pci   | 2902DCE4BA |
| 8086:1c26 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 542   | ehci_hc... | 13AF031E5E |
| 8086:1c2d | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 542   | ehci_hc... | 13AF031E5E |
| 1002:4396 | 1002:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 534   | ehci_hc... | F0615F7666 |
| 8086:27c8 | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 445   | uhci_hcd   | ABA2A5E5E6 |
| 8086:27c9 | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 445   | uhci_hcd   | ABA2A5E5E6 |
| 8086:27ca | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 445   | uhci_hcd   | ABA2A5E5E6 |
| 8086:27cb | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 445   | uhci_hcd   | ABA2A5E5E6 |
| 8086:27cc | 1458:5006 | Intel      | NM10/ICH7 Family USB2 EHC... | 445   | ehci_hc... | ABA2A5E5E6 |
| 1002:4397 | 1002:4397 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 427   | ohci_hc... | AFDF4A3A9C |
| 1002:4396 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 406   | ehci_hc... | 3C504F06A2 |
| 1002:4397 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 406   | ohci_hc... | 3C504F06A2 |
| 1002:4398 | 1043:8389 | AMD        | SB7x0 USB OHCI1 Controller   | 404   | ohci_hc... | 3C504F06A2 |
| 1002:4399 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 404   | ohci_hc... | 3C504F06A2 |
| 1002:4399 | 1002:4399 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 386   | ohci_hc... | AFDF4A3A9C |
| 8086:1e26 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 385   | ehci_hc... | 91535E2115 |
| 8086:1e2d | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 385   | ehci_hc... | 91535E2115 |
| 8086:1e31 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 382   | xhci_pci   | 91535E2115 |
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
| 8086:8c31 | 1458:5007 | Intel      | 8 Series/C220 Series Chip... | 221   | xhci_pci   | 502C5D4B04 |
| 1022:7807 | 1458:5004 | AMD        | FCH USB OHCI Controller      | 216   | ohci_hc... | 0CABEB6C95 |
| 1022:7808 | 1458:5004 | AMD        | FCH USB EHCI Controller      | 216   | ehci_hc... | 0CABEB6C95 |
| 1022:7809 | 1458:5004 | AMD        | FCH USB OHCI Controller      | 212   | ohci_hc... | 0CABEB6C95 |
| 1106:3038 | 1106:3038 | VIA Tec... | VT82xx/62xx UHCI USB 1.1 ... | 199   | uhci_hcd   | 4908CB8960 |
| 1106:3104 | 1106:3104 | VIA Tec... | USB 2.0                      | 195   | ehci_hc... | 4908CB8960 |
| 1033:0194 | 1043:8413 | NEC Com... | uPD720200 USB 3.0 Host Co... | 179   | xhci_hcd   | E40B76E473 |
| 1106:3483 | 1458:5007 | VIA Tec... | VL805 USB 3.0 Host Contro... | 178   | xhci_pci   | BB239C7852 |
| 1022:43bb | 1b21:1142 | AMD        | 300 Series Chipset USB 3.... | 167   | xhci_hcd   | 4ED3A4A663 |
| 1022:43d5 | 1b21:1142 | AMD        | 400 Series Chipset USB 3.... | 162   | xhci_hcd   | 5BCFE2F1CE |
| 8086:3a34 | 1458:5004 | Intel      | 82801JI (ICH10 Family) US... | 162   | uhci_hcd   | 13ACEC4985 |
| 8086:3a35 | 1458:5004 | Intel      | 82801JI (ICH10 Family) US... | 162   | uhci_hcd   | 13ACEC4985 |
| 8086:3a36 | 1458:5004 | Intel      | 82801JI (ICH10 Family) US... | 162   | uhci_hcd   | 13ACEC4985 |
| 8086:3a37 | 1458:5004 | Intel      | 82801JI (ICH10 Family) US... | 162   | uhci_hcd   | 13ACEC4985 |
| 8086:3a38 | 1458:5004 | Intel      | 82801JI (ICH10 Family) US... | 162   | uhci_hcd   | 13ACEC4985 |
| 8086:3a39 | 1458:5004 | Intel      | 82801JI (ICH10 Family) US... | 162   | uhci_hcd   | 13ACEC4985 |
| 8086:3a3a | 1458:5006 | Intel      | 82801JI (ICH10 Family) US... | 162   | ehci_hc... | 13ACEC4985 |
| 8086:3a3c | 1458:5006 | Intel      | 82801JI (ICH10 Family) US... | 162   | ehci_hc... | 13ACEC4985 |
| 1002:4399 | 1002:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 145   | ohci_hc... | F0615F7666 |
| 8086:3b34 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 141   | ehci_hc... | E40B76E473 |
| 8086:3b3c | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 141   | ehci_hc... | E40B76E473 |
| 8086:a12f | 1458:5007 | Intel      | 100 Series/C230 Series Ch... | 138   | xhci_hcd   | 4015843475 |
| 1106:3483 | 1106:3483 | VIA Tec... | VL805 USB 3.0 Host Contro... | 136   | xhci_hcd   | 053F507950 |
| 8086:1c26 | 1849:1c26 | Intel      | 6 Series/C200 Series Chip... | 135   | ehci_hc... | 2A41C5495D |
| 8086:1c2d | 1849:1c2d | Intel      | 6 Series/C200 Series Chip... | 135   | ehci_hc... | 2A41C5495D |
| 1022:7807 | 1849:7807 | AMD        | FCH USB OHCI Controller      | 132   | ohci_hc... | 8230399CC0 |
| 1022:7808 | 1849:7808 | AMD        | FCH USB EHCI Controller      | 132   | ehci_hc... | 8230399CC0 |
| 1b21:1242 | 1043:8675 | ASMedia... | ASM1142 USB 3.1 Host Cont... | 125   | xhci_hcd   | B8C562A7E5 |
| 1002:4398 | 1849:4398 | AMD        | SB7x0 USB OHCI1 Controller   | 124   | ohci_hc... | 1581CB5806 |
| 1022:7809 | 1849:7809 | AMD        | FCH USB OHCI Controller      | 122   | ohci_hc... | 8230399CC0 |
| 1033:0194 | 1458:5007 | NEC Com... | uPD720200 USB 3.0 Host Co... | 121   | xhci_hcd   | E722D70419 |
| 8086:2934 | 1458:5004 | Intel      | 82801I (ICH9 Family) USB ... | 120   | uhci_hcd   | D87E2ED1BC |
| 8086:2935 | 1458:5004 | Intel      | 82801I (ICH9 Family) USB ... | 120   | uhci_hcd   | D87E2ED1BC |
| 8086:2936 | 1458:5004 | Intel      | 82801I (ICH9 Family) USB ... | 120   | uhci_hcd   | D87E2ED1BC |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8d7c | 1043:8600 | Intel      | C610/X99 series chipset SPSR | 33    |            | 021596F9B3 |
| 8086:8d7c | 1028:0617 | Intel      | C610/X99 series chipset SPSR | 10    |            | 019BFC3983 |
| 8086:8d7c | 1458:7270 | Intel      | C610/X99 series chipset SPSR | 10    |            | AF58D23265 |
| 8086:8d7c | 1849:8d7c | Intel      | C610/X99 series chipset SPSR | 8     |            | 917E16476B |
| 8086:8d7c | 1462:7885 | Intel      | C610/X99 series chipset SPSR | 7     |            | FDE33600E4 |
| 1af2:a001 | 1af2:a001 | AVerMedia  | Live Gamer HD                | 5     |            | 94934B2DA3 |
| 8086:2690 | 0000:0000 | Intel      | 631xESB/632xESB/3100 Chip... | 5     | pcieport   | A3AC5B74CF |
| 8086:3500 | 0000:0000 | Intel      | 6311ESB/6321ESB PCI Expre... | 5     | pcieport   | A3AC5B74CF |
| 8086:350c | 0000:0000 | Intel      | 6311ESB/6321ESB PCI Expre... | 5     | shpchp     | A3AC5B74CF |
| 8086:3510 | 0000:0000 | Intel      | 6311ESB/6321ESB PCI Expre... | 5     | pcieport   | A3AC5B74CF |
| 8086:3514 | 0000:0000 | Intel      | 6311ESB/6321ESB PCI Expre... | 5     | pcieport   | A3AC5B74CF |
| 8086:2692 | 0000:0000 | Intel      | 631xESB/632xESB/3100 Chip... | 4     | pcieport   | A3AC5B74CF |
| 8086:2694 | 0000:0000 | Intel      | 631xESB/632xESB/3100 Chip... | 4     | pcieport   | A3AC5B74CF |
| 8086:2696 | 0000:0000 | Intel      | 631xESB/632xESB/3100 Chip... | 4     | pcieport   | A3AC5B74CF |
| 8086:3518 | 0000:0000 | Intel      | 6311ESB/6321ESB PCI Expre... | 4     | pcieport   | A3AC5B74CF |
| 8086:5ad9 | 0000:0000 | Intel      | Celeron N3350/Pentium N42... | 4     | shpchp     | 6F498D9D7D |
| 8086:3a40 | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 3     | pcieport   | A4847544CA |
| 8086:3a42 | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 3     | pcieport   | A4847544CA |
| 8086:3a48 | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 3     | pcieport   | A4847544CA |
| 8086:8d7c | 1028:064c | Intel      | C610/X99 series chipset SPSR | 3     |            | E1BABF19AD |
| 8086:3a44 | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 2     | pcieport   | 354B501A79 |
| 8086:3a46 | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 2     | pcieport   | 354B501A79 |
| 8086:3a4a | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 2     | pcieport   | 354B501A79 |
| 8086:8d7c | 1028:0618 | Intel      | C610/X99 series chipset SPSR | 2     |            | 4C6E30FFB1 |
| 8086:8d7c | 103c:212b | Intel      | C610/X99 series chipset SPSR | 2     |            | 6B7FF8ADA9 |
| 8086:8d7c | 103c:8030 | Intel      | C610/X99 series chipset SPSR | 2     |            | D9B1EC3C37 |
| 8086:8d7c | 1043:85f6 | Intel      | C610/X99 series chipset SPSR | 2     |            | 7436C74DCB |
| 0000:0000 | 8005:0000 |            |                              | 1     |            | 77F07D2D69 |
| 0000:0002 | 1105:8300 |            |                              | 1     |            | 3859A12973 |
| 1000:fury | 1000:9343 | Broadco... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 29B0070304 |
| 1045:c861 | 0045:8000 | OPTi       | 82C861 OHCI USB Host         | 1     | ohci-pci   | 806796F01E |
| 104c:8024 | 0020:0000 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 1     | firewir... | F5C15B4975 |
| 106b:0041 |           | Apple      | K2 KeyLargo Mac/IO           | 1     | macio      | 52B4B037A1 |
| 106b:0043 |           | Apple      | K2 ATA/100                   | 1     | pata_pc... | 52B4B037A1 |
| 1131:7146 | ffff:ffff | Philips... | SAA7146                      | 1     |            | 4893225F50 |
| 1186:4300 | ffff:ffff | D-Link ... | DGE-528T Gigabit Ethernet... | 1     | r8169      | 5C0883B543 |
| 1274:5880 | ffff:ffff | Ensoniq    | 5880B / Creative Labs CT5880 | 1     | snd_ens... | DF4BA14E49 |
| 127a:2014 | 144e:2014 | Rockwel... | HSF 56k Data/Fax/Voice Modem | 1     |            | 97FF18DC78 |
| 13f6:0111 | 5b7f:ce5f | C-Media... | CMI8738/CMI8768 PCI Audio    | 1     | snd_cmipci | 76442678ED |
| 13f6:0111 | fbff:fffd | C-Media... | CMI8738/CMI8768 PCI Audio    | 1     | snd_cmipci | 0528AB77BE |
| 13f6:8788 | ffff:ffff | C-Media... | CMI8788 [Oxygen HD Audio]    | 1     |            | 306E5B04F7 |
| 144a:5101 | 144a:5101 | Adlink ... |                              | 1     |            | E0E966D6B4 |
| 1931:1011 | 1003:0001 | Option ... |                              | 1     |            | 28DFB478B7 |
| 1931:1011 | 1043:0001 | Option ... |                              | 1     |            | 28DFB478B7 |
| 1fc8:0be0 |           | Lucid I... | HYDRA 200                    | 1     |            | F24106BC34 |
| 8005:0000 |           |            |                              | 1     |            | 77F07D2D69 |
| 8037:cf10 | f377:afbd |            |                              | 1     |            | E02C86805F |
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
| 8086:3593 | 8086:345e | Intel      | E7320 Error Reporting Reg... | 1     |            | 97CC3C4274 |
| 8086:5ad6 | 0000:0000 | Intel      | Celeron N3350/Pentium N42... | 1     | shpchp     | 6F498D9D7D |
| 8086:6ff2 | 103c:21ea | Intel      | Broadwell-E CBo Unicast R... | 1     |            | D9B1EC3C37 |
| 8086:6ff2 | 1849:6ff2 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 87D6B1C03E |
| 8086:6ff2 | 8086:6ff2 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 9EE9F662A8 |
| 8086:6ff3 | 103c:21ea | Intel      | Broadwell-E CBo Unicast R... | 1     |            | D9B1EC3C37 |
| 8086:6ff3 | 1849:6ff3 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 87D6B1C03E |
| 8086:6ff3 | 8086:6ff3 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 9EE9F662A8 |
| 8086:6ff4 | 103c:21ea | Intel      | Broadwell-E CBo Unicast R... | 1     |            | D9B1EC3C37 |
| 8086:6ff4 | 1849:6ff4 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 87D6B1C03E |
| 8086:6ff5 | 103c:21ea | Intel      | Broadwell-E CBo Unicast R... | 1     |            | D9B1EC3C37 |
| 8086:6ff5 | 1849:6ff5 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 87D6B1C03E |
| 8086:8d7c | 1028:0619 | Intel      | C610/X99 series chipset SPSR | 1     |            | ADB52FAE26 |
| 8086:8d7c | 1462:7882 | Intel      | C610/X99 series chipset SPSR | 1     |            | 1E0208BF20 |
| 8086:8d7c | 1462:7883 | Intel      | C610/X99 series chipset SPSR | 1     |            | 227E62B97E |
| 8086:8d7c | 1462:7a21 | Intel      | C610/X99 series chipset SPSR | 1     |            | 65DF5317A4 |
| 8086:8d7c | 15d9:0836 | Intel      | C610/X99 series chipset SPSR | 1     |            | 7756560112 |
| 8086:8d7c | 15d9:0852 | Intel      | C610/X99 series chipset SPSR | 1     |            | 2E6D79F345 |
| 8086:8d7c | 1734:1201 | Intel      | C610/X99 series chipset SPSR | 1     |            | D54DC05BEB |
| 8086:8d7c | 17aa:102f | Intel      | C610/X99 series chipset SPSR | 1     |            | BB3B9B883B |
| 8086:8d7c | 17aa:1030 | Intel      | C610/X99 series chipset SPSR | 1     |            | B89B8C9364 |
| 8086:8d7c | 17aa:1031 | Intel      | C610/X99 series chipset SPSR | 1     |            | 92262238C3 |
| 8086:a1ec | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 1     |            | 931EA9A398 |
| 8086:a1ed | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 1     |            | 931EA9A398 |
| 8086:a2ed | 0000:0000 | Intel      | 200 Series PCH PCI Expres... | 1     | pcieport   | 816A1797C5 |
| 8086:a33d |           | Intel      | Cannon Lake PCH PCI Expre... | 1     | pcieport   | 09F92379DE |
| mxic:0531 |           | Macroni... | MX987x5                      | 1     | tulip      | DF08E5122C |

