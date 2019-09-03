Most popular PCI devices in Desktops
====================================

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Desktops ](#pci-devices)
   * [ ? ](#-pci)
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

### ? (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8037:cf10 | f377:afbd |            |                              | 1     |            | E02C86805F |

### Bluetooth (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1814:3298 | 103c:18ec | Ralink     | RT3290 Bluetooth             | 4     |            | F299E43433 |
| 1814:3298 | 1a3b:2787 | Ralink     | RT3290 Bluetooth             | 3     |            | 4C67B55B77 |
| 1814:3298 | 1a3b:2987 | Ralink     | RT3290 Bluetooth             | 1     |            | 1D26C2B648 |

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:4384 |           | AMD        | SBx00 PCI to PCI Bridge      | 2072  |            | 394C81B911 |
| 1022:1200 |           | AMD        | Family 10h Processor Hype... | 1523  |            | 62E3C9247C |
| 1022:1201 |           | AMD        | Family 10h Processor Addr... | 1523  |            | 62E3C9247C |
| 1022:1202 |           | AMD        | Family 10h Processor DRAM... | 1523  | amd64_e... | 62E3C9247C |
| 1022:1203 |           | AMD        | Family 10h Processor Misc... | 1523  | k10temp    | 62E3C9247C |
| 1022:1204 |           | AMD        | Family 10h Processor Link... | 1523  |            | 62E3C9247C |
| 1022:1100 |           | AMD        | K8 [Athlon64/Opteron] Hyp... | 911   |            | B26ED41AB8 |
| 1022:1101 |           | AMD        | K8 [Athlon64/Opteron] Add... | 911   |            | B26ED41AB8 |
| 1022:1102 |           | AMD        | K8 [Athlon64/Opteron] DRA... | 911   | amd64_e... | B26ED41AB8 |
| 1022:1103 |           | AMD        | K8 [Athlon64/Opteron] Mis... | 911   | k8temp     | B26ED41AB8 |
| 1002:439d | 1002:439d | AMD        | SB7x0/SB8x0/SB9x0 LPC hos... | 863   |            | 394C81B911 |
| 1022:1600 |           | AMD        | Family 15h Processor Func... | 826   |            | 394C81B911 |
| 1022:1601 |           | AMD        | Family 15h Processor Func... | 826   |            | 394C81B911 |
| 1022:1602 |           | AMD        | Family 15h Processor Func... | 826   |            | 394C81B911 |
| 1022:1603 |           | AMD        | Family 15h Processor Func... | 826   | k10temp    | 394C81B911 |
| 1022:1604 |           | AMD        | Family 15h Processor Func... | 826   | fam15h_... | 394C81B911 |
| 1022:1605 |           | AMD        | Family 15h Processor Func... | 826   |            | 394C81B911 |
| 8086:244e | 1458:5000 | Intel      | 82801 PCI Bridge             | 794   |            | B39AC90CA0 |
| 8086:244e |           | Intel      | 82801 PCI Bridge             | 637   | shpchp     | 8C4047657D |
| 1022:780f |           | AMD        | FCH PCI Bridge               | 622   |            | 8226B90793 |
| 8086:244e | 1043:8179 | Intel      | 82801 PCI Bridge             | 570   |            | FAC5E9FEFA |
| 8086:27b8 | 1043:8179 | Intel      | 82801GB/GR (ICH7 Family) ... | 570   | lpc_ich    | FAC5E9FEFA |
| 8086:27d0 | 1043:8179 | Intel      | NM10/ICH7 Family PCI Expr... | 559   | shpchp     | FAC5E9FEFA |
| 1b21:1080 | 1043:8489 | ASMedia... | ASM1083/1085 PCIe to PCI ... | 540   | shpchp     | 99614383EB |
| 1002:43a0 | 1002:0000 | AMD        | SB700/SB800/SB900 PCI to ... | 487   | shpchp     | 394C81B911 |
| 8086:1c10 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 466   | shpchp     | 66A5EA0BE5 |
| 1002:5a14 | 1002:5a14 | AMD        | RD9x0/RX980 Host Bridge      | 455   |            | 394C81B911 |
| 1002:5a16 | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 443   | shpchp     | 394C81B911 |
| 8086:27d2 | 1043:8179 | Intel      | NM10/ICH7 Family PCI Expr... | 430   | shpchp     | FAC5E9FEFA |
| 1002:5a18 | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 426   | shpchp     | 6A60A724F9 |
| 1022:1452 |           | AMD        | Family 17h (Models 00h-1f... | 418   |            | 4A2455EAE6 |
| 8086:244e | 1849:244e | Intel      | 82801 PCI Bridge             | 418   |            | 5F6E1A3B61 |
| 8086:27b8 | 1458:5001 | Intel      | 82801GB/GR (ICH7 Family) ... | 402   | lpc_ich    | D0D6CD20B1 |
| 8086:0c01 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 390   | shpchp     | F6CCF2BBA6 |
| 8086:0c00 | 1043:8534 | Intel      | 4th Gen Core Processor DR... | 389   | hsw_uncore | F6CCF2BBA6 |
| 8086:0101 | 1043:844d | Intel      | Xeon E3-1200/2nd Generati... | 350   | shpchp     | 66A5EA0BE5 |
| 8086:0100 | 1043:844d | Intel      | 2nd Generation Core Proce... | 349   | snb_uncore | 66A5EA0BE5 |
| 1022:1400 |           | AMD        | Family 15h (Models 10h-1f... | 347   |            | 32E1C72BAA |
| 1022:1401 |           | AMD        | Family 15h (Models 10h-1f... | 347   |            | 32E1C72BAA |
| 1022:1402 |           | AMD        | Family 15h (Models 10h-1f... | 347   |            | 32E1C72BAA |
| 1022:1403 |           | AMD        | Family 15h (Models 10h-1f... | 347   | k10temp    | 32E1C72BAA |
| 1022:1404 |           | AMD        | Family 15h (Models 10h-1f... | 347   |            | 32E1C72BAA |
| 1022:1405 |           | AMD        | Family 15h (Models 10h-1f... | 347   |            | 32E1C72BAA |
| 8086:1e10 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 347   | shpchp     | 570B707FFB |
| 8086:244e | 1458:8892 | Intel      | 82801 PCI Bridge             | 343   |            | 8C4047657D |
| 1002:439d | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 LPC hos... | 339   |            | D569843A2D |
| 10de:03e8 | 10de:0000 | Nvidia     | MCP61 PCI Express bridge     | 327   | shpchp     | 11D0376265 |
| 8086:1c1a | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 325   | shpchp     | 66A5EA0BE5 |
| 8086:244e | 1458:5001 | Intel      | 82801 PCI Bridge             | 320   | pcieport   | 8C4047657D |
| 1022:1460 |           | AMD        | Family 17h (Models 00h-0f... | 319   |            | 4A2455EAE6 |
| 1022:1461 |           | AMD        | Family 17h (Models 00h-0f... | 319   |            | 4A2455EAE6 |
| 1022:1462 |           | AMD        | Family 17h (Models 00h-0f... | 319   |            | 4A2455EAE6 |
| 1022:1463 |           | AMD        | Family 17h (Models 00h-0f... | 319   | k10temp    | 4A2455EAE6 |
| 1022:1464 |           | AMD        | Family 17h (Models 00h-0f... | 319   |            | 4A2455EAE6 |
| 1022:1465 |           | AMD        | Family 17h (Models 00h-0f... | 319   |            | 4A2455EAE6 |
| 1022:1466 |           | AMD        | Family 17h (Models 00h-0f... | 319   |            | 4A2455EAE6 |
| 1022:1467 |           | AMD        | Family 17h (Models 00h-0f... | 319   |            | 4A2455EAE6 |
| 8086:8c10 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 308   | shpchp     | F6CCF2BBA6 |
| 8086:1c5c | 1043:844d | Intel      | H61 Express Chipset LPC C... | 299   | lpc_ich    | 6CF789DF63 |
| 8086:244e | 1043:84ca | Intel      | 82801 PCI Bridge             | 296   |            | 1434651158 |
| 8086:27d0 | 1458:5001 | Intel      | NM10/ICH7 Family PCI Expr... | 293   | shpchp     | DD0FCDE6C7 |
| 1022:43b4 | 1b21:3306 | AMD        | 300 Series Chipset PCIe Port | 287   | pcieport   | D084D64BDF |
| 8086:1c10 | 1458:5001 | Intel      | 6 Series/C200 Series Chip... | 285   | shpchp     | E4C2A9F4EB |
| 1022:43a0 | 1022:0000 | AMD        | Hudson PCI to PCI bridge ... | 282   | shpchp     | 9137FB3859 |
| 8086:244e | 1043:844d | Intel      | 82801 PCI Bridge             | 282   | pcieport   | 66A5EA0BE5 |
| 1022:1454 | 1022:1454 | AMD        | Family 17h (Models 00h-0f... | 277   | pcieport   | D084D64BDF |
| 8086:244e | 1043:82d4 | Intel      | 82801 PCI Bridge             | 271   |            | B481805845 |
| 8086:1e18 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 266   | shpchp     | 570B707FFB |
| 8086:8c14 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 266   | shpchp     | F6CCF2BBA6 |
| 1022:9600 | 1043:8388 | AMD        | RS780 Host Bridge            | 263   |            | D569843A2D |
| 10de:03e9 | 10de:0000 | Nvidia     | MCP61 PCI Express bridge     | 257   | shpchp     | 11D0376265 |
| 8086:0150 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 254   | ie31200... | 570B707FFB |
| 8086:0151 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 254   | shpchp     | 570B707FFB |
| 1002:5a1c | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 251   | shpchp     | 394C81B911 |
| 8086:0150 | 1458:5000 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 250   | ie31200... | 8C4047657D |
| 8086:0c00 | 1458:5000 | Intel      | 4th Gen Core Processor DR... | 247   | hsw_uncore | DD4DA32934 |
| 8086:27d0 | 1849:27d0 | Intel      | NM10/ICH7 Family PCI Expr... | 247   | shpchp     | 5F6E1A3B61 |
| 8086:27b8 | 1849:27b8 | Intel      | 82801GB/GR (ICH7 Family) ... | 243   | lpc_ich    | 5F6E1A3B61 |
| 1022:9600 | 1022:9600 | AMD        | RS780 Host Bridge            | 241   |            | 8EAEF3C906 |
| 8086:1e10 | 1458:5001 | Intel      | 7 Series/C216 Chipset Fam... | 241   | shpchp     | 8C4047657D |
| 8086:27d2 | 1849:27d2 | Intel      | NM10/ICH7 Family PCI Expr... | 238   | shpchp     | 5F6E1A3B61 |
| 8086:29c0 | 1458:5000 | Intel      | 82G33/G31/P35/P31 Express... | 235   | agpgart... | 54231260FF |
| 8086:27d2 | 1458:5001 | Intel      | NM10/ICH7 Family PCI Expr... | 231   | shpchp     | DD0FCDE6C7 |
| 10de:03f3 | 10de:cb84 | Nvidia     | MCP61 PCI bridge             | 223   |            | 11D0376265 |
| 1002:439d | 1849:439d | AMD        | SB7x0/SB8x0/SB9x0 LPC hos... | 222   |            | 85F1B83B30 |
| 1022:9603 | 1043:8388 | AMD        | RS780 PCI to PCI bridge (... | 217   | shpchp     | 277055C3E7 |
| 8086:1c18 | 1458:5001 | Intel      | 6 Series/C200 Series Chip... | 213   | shpchp     | E4C2A9F4EB |
| 8086:244e | 1043:8277 | Intel      | 82801 PCI Bridge             | 211   |            | 29B7777E42 |
| 8086:0151 | 1458:5000 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 210   | shpchp     | 8C4047657D |
| 8086:29c0 | 1043:82b0 | Intel      | 82G33/G31/P35/P31 Express... | 210   | agpgart... | FAC5E9FEFA |
| 1002:5a1b | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 209   | shpchp     | 6A60A724F9 |
| 8086:2940 | 1043:8277 | Intel      | 82801I (ICH9 Family) PCI ... | 208   | shpchp     | 29B7777E42 |
| 8086:3a40 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) PC... | 208   | shpchp     | 2FDD668590 |
| 8086:29c1 | 1458:5000 | Intel      | 82G33/G31/P35/P31 Express... | 201   | shpchp     | 54231260FF |
| 8086:a118 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 198   | shpchp     | 99614383EB |
| 1002:43a1 | 1002:0000 | AMD        | SB700/SB800/SB900 PCI to ... | 197   | shpchp     | A2F40FA9C0 |
| 10de:03e8 | 1849:03e8 | Nvidia     | MCP61 PCI Express bridge     | 194   | shpchp     | 816FE60D2D |
| 10de:03e9 | 1849:03e9 | Nvidia     | MCP61 PCI Express bridge     | 194   | shpchp     | 816FE60D2D |
| 10de:03f3 | 1849:03f3 | Nvidia     | MCP61 PCI bridge             | 194   |            | 816FE60D2D |
| 8086:2e20 | 1043:82d3 | Intel      | 4 Series Chipset DRAM Con... | 193   | agpgart... | 2FDD668590 |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:522a | 1458:1000 | Realtek... | RTS522A PCI Express Card ... | 7     | rtsx_pci   | 39694A0489 |
| 10ec:5209 | 103c:2ac5 | Realtek... | RTS5209 PCI Express Card ... | 6     | rtsx_pci   | 512D1C0495 |
| 10ec:5229 | 17aa:366b | Realtek... | RTS5229 PCI Express Card ... | 5     | rtsx_pci   | AADDFBD58B |
| 10ec:525a | 1028:07ee | Realtek... | RTS525A PCI Express Card ... | 5     | rtsx_pci   | DB32491DFE |
| 10ec:5229 | 1b0a:016c | Realtek... | RTS5229 PCI Express Card ... | 4     | rtsx_pci   | 0DF79259C1 |
| 10ec:5209 | 103c:2ac3 | Realtek... | RTS5209 PCI Express Card ... | 3     | rtsx_pci   | BE8250E028 |
| 10ec:5209 | 103c:2aed | Realtek... | RTS5209 PCI Express Card ... | 3     | rtsx_pci   | 00FCD6CB57 |
| 10ec:5209 | 103c:2af0 | Realtek... | RTS5209 PCI Express Card ... | 3     | rtsx_pci   | CE9938531D |
| 10ec:5209 | 103c:2adc | Realtek... | RTS5209 PCI Express Card ... | 2     | rtsx_pci   | 2F18EFFE9B |
| 10ec:5229 | 103c:2b38 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 4D6F67B025 |
| 10ec:5249 | 103c:18e6 | Realtek... | RTS5249 PCI Express Card ... | 2     | rtsx_pci   | C0BDA7E63F |
| 10ec:5289 | 10ec:5289 | Realtek... | RTL8411 PCI Express Card ... | 2     | rtsx_pci   | CD64391DDA |
| 10ec:5209 | 1025:8020 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 06609A514E |
| 10ec:5209 | 103c:2ac7 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 7A9D5AF1CE |
| 10ec:5209 | 103c:2b02 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | E49892B06D |
| 10ec:5209 | 1b0a:015e | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 15DEA2CF84 |
| 10ec:5229 | 103c:2179 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 73F746B58F |
| 10ec:5229 | 103c:2af8 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | CF7972F23A |
| 10ec:5229 | 103c:2af9 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 6D0940251F |
| 10ec:5229 | 103c:2b3c | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | B62C50E352 |
| 10ec:5229 | 103c:2b43 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | B6867DCF24 |
| 10ec:5229 | 1b0a:018a | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | CAA7CA382E |
| 10ec:522a | 10ec:522a | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 39694A0489 |
| 10ec:525a | 1028:085a | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | B7022F0A45 |
| 10ec:525a | 1734:122e | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | 14943339B4 |
| 1aea:6621 | 1aea:6621 | Alcor M... | Alcor Micro PCIe Card Reader | 1     |            | 0F9AA13B55 |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0753 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Co-... | 33    |            | 88719BBDD6 |
| 10de:0753 | 1849:0753 | Nvidia     | MCP78S [GeForce 8200] Co-... | 21    |            | AC2555A764 |
| 10de:03f4 | 1462:7309 | Nvidia     | MCP61 SMU                    | 18    |            | C9F702BE07 |
| 10de:03f4 | 1462:7597 | Nvidia     | MCP61 SMU                    | 14    |            | A0A7F774C4 |
| 10de:0753 | 1043:82e2 | Nvidia     | MCP78S [GeForce 8200] Co-... | 10    |            | 94F06CBF32 |
| 10de:0aa3 | 1025:0222 | Nvidia     | MCP79 Co-processor           | 8     | nvidia     | 4F99355CFD |
| 10de:03f4 | 1043:8234 | Nvidia     | MCP61 SMU                    | 6     |            | 8C4716B30A |
| 10de:0543 | 1849:0543 | Nvidia     | MCP67 Co-processor           | 6     |            | 1C80EA8C25 |
| 10de:03f4 |           | Nvidia     | MCP61 SMU                    | 5     |            | 5343BC19E6 |
| 10de:0753 | 1565:340b | Nvidia     | MCP78S [GeForce 8200] Co-... | 5     |            | 52B394C153 |
| 10de:0aa3 | 1b0a:0074 | Nvidia     | MCP79 Co-processor           | 5     | nvidia     | 957D335223 |
| 10de:0753 | 1043:82e8 | Nvidia     | MCP78S [GeForce 8200] Co-... | 4     |            | 5AFC22B5E1 |
| 10de:0aa3 | 1849:0aa3 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | 1CADF5EB87 |
| 10de:0753 | 1025:0228 | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | B2D5544528 |
| 10de:07da | 1462:7366 | Nvidia     | MCP73 Co-processor           | 3     |            | 3C83AF8B83 |
| 10de:0aa3 | 1043:83e2 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 1452DE25DA |
| 10de:03f4 | 1849:03f4 | Nvidia     | MCP61 SMU                    | 2     |            | B7F7A41C71 |
| 10de:0753 | 1025:0153 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 96600BDB45 |
| 10de:0753 | 1025:0462 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 03A71DD3EB |
| 10de:0753 | 103c:2a81 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 2E29A30FA2 |
| 10de:0753 | 1043:82e7 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 97B83F48DF |
| 10de:07da | 10de:07d7 | Nvidia     | MCP73 Co-processor           | 2     |            | 975F642709 |
| 10de:0aa3 | 1025:0168 | Nvidia     | MCP79 Co-processor           | 2     |            | 5443C8EC11 |
| 10de:0aa3 | 1462:7621 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | 1BA5C50EAD |
| 10de:0aa3 | 19da:0ae5 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | BA99DCB426 |
| 10de:0753 | 1019:1b67 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 4765DCDC47 |
| 10de:0753 | 1025:0227 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 3CF233B9C4 |
| 10de:0753 | 103c:2a9e | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | DF15AC1D7E |
| 10de:0753 | 1043:8332 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | E527269900 |
| 10de:0753 | 1462:6720 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | E2CB0B1767 |
| 10de:0753 | 1462:7375 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 2C3B9EAC17 |
| 10de:0753 | 1462:7578 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | AFECB4A1DB |
| 10de:0753 | 1631:e03b | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | E6D16C44AA |
| 10de:07da | 1025:0137 | Nvidia     | MCP73 Co-processor           | 1     |            | 9204CB3BAC |
| 10de:07da | 1462:736b | Nvidia     | MCP73 Co-processor           | 1     |            | 0445B13D43 |
| 10de:07da | 1462:7504 | Nvidia     | MCP73 Co-processor           | 1     |            | 05F36A437A |
| 10de:07da | 1849:07da | Nvidia     | MCP73 Co-processor           | 1     |            | 64E722CEC4 |
| 10de:0aa3 | 103c:2a83 | Nvidia     | MCP79 Co-processor           | 1     | nvidia     | 226AA094E2 |
| 10de:0aa3 | 103c:2aa1 | Nvidia     | MCP79 Co-processor           | 1     |            | DF47C88DB6 |
| 10de:0aa3 | 1043:8356 | Nvidia     | MCP79 Co-processor           | 1     |            | E5CBBA8ADC |
| 10de:0aa3 | 19da:a108 | Nvidia     | MCP79 Co-processor           | 1     |            | 7439F4F707 |
| 10de:0aa3 | 1b0a:000f | Nvidia     | MCP79 Co-processor           | 1     | nvidia     | F298AE57F6 |
| 10de:0aa3 | a0a0:0802 | Nvidia     | MCP79 Co-processor           | 1     |            | B778A6096A |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1c3a | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 463   | mei_me     | 66A5EA0BE5 |
| 8086:1e3a | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 342   | mei_me     | 570B707FFB |
| 8086:8c3a | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 316   | mei_me     | F6CCF2BBA6 |
| 8086:1c3a | 1458:1c3a | Intel      | 6 Series/C200 Series Chip... | 287   | mei_me     | 1984E65634 |
| 8086:1e3a | 1458:1c3a | Intel      | 7 Series/C216 Chipset Fam... | 235   | mei_me     | 8C4047657D |
| 8086:a13a | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 196   | mei_me     | 99614383EB |
| 8086:8c3a | 1458:1c3a | Intel      | 8 Series/C220 Series Chip... | 182   | mei_me     | DD4DA32934 |
| 8086:1c3a | 1849:1c3a | Intel      | 6 Series/C200 Series Chip... | 114   | mei_me     | BDA40E6195 |
| 8086:a13a | 1458:1c3a | Intel      | 100 Series/C230 Series Ch... | 103   | mei_me     | 0BF4CAF942 |
| 8086:8c3a | 1849:8c3a | Intel      | 8 Series/C220 Series Chip... | 79    | mei_me     | 8AE6B6F651 |
| 8086:8cba | 1043:8534 | Intel      | 9 Series Chipset Family M... | 76    | mei_me     | EFA3992D9A |
| 8086:8c3a | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 72    | mei_me     | 7BBCD6F17D |
| 8086:8cba | 1458:1c3a | Intel      | 9 Series Chipset Family M... | 66    | mei_me     | 2DDBCF3D21 |
| 8086:1e3a | 1849:1e3a | Intel      | 7 Series/C216 Chipset Fam... | 63    | mei_me     | 3D8C4FEBC3 |
| 8086:a2ba | 1458:1c3a | Intel      | 200 Series PCH CSME HECI #1  | 63    | mei_me     | AAD0551E27 |
| 8086:a2ba | 1043:8694 | Intel      | 200 Series PCH CSME HECI #1  | 54    | mei_me     | 7F1F084A4F |
| 8086:3b64 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 46    | mei_me     | 9A8E939D8B |
| 8086:1c3a | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 41    | mei_me     | 7AF20CDF5A |
| 8086:3b64 | 1458:3b64 | Intel      | 5 Series/3400 Series Chip... | 38    | mei_me     | 85F57C764C |
| 8086:1d3a | 1043:84ef | Intel      | C600/X79 series chipset M... | 37    | mei_me     | EEE7D322DF |
| 8086:a13a | 1849:a13a | Intel      | 100 Series/C230 Series Ch... | 37    | mei_me     | BCB3EF58AB |
| 8086:1e3a | 1462:7758 | Intel      | 7 Series/C216 Chipset Fam... | 34    | mei_me     | 0A593D376A |
| 8086:a360 | 1043:8694 | Intel      | Cannon Lake PCH HECI Cont... | 32    | mei_me     | 68BABB69CB |
| 8086:a360 | 1458:1c3a | Intel      | Cannon Lake PCH HECI Cont... | 31    | mei_me     | 0B02A9E571 |
| 8086:8d3a | 1043:8600 | Intel      | C610/X99 series chipset M... | 26    | mei_me     | A8F2B39356 |
| 8086:1c3a | 1462:7680 | Intel      | 6 Series/C200 Series Chip... | 25    | mei_me     | CBE52D9E29 |
| 8086:a2ba | 1043:872f | Intel      | 200 Series PCH CSME HECI #1  | 23    | mei_me     | 3B3DC1A093 |
| 8086:a2ba | 1849:a2ba | Intel      | 200 Series PCH CSME HECI #1  | 23    | mei_me     | CACD7C9489 |
| 8086:8cba | 1849:8cba | Intel      | 9 Series Chipset Family M... | 21    | mei_me     | 09CC6BAB56 |
| 8086:a13a | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 21    | mei_me     | BD6DC70775 |
| 8086:2e14 | 1028:027f | Intel      | 4 Series Chipset HECI Con... | 20    | mei_me     | DFA7361038 |
| 8086:a360 | 1849:a360 | Intel      | Cannon Lake PCH HECI Cont... | 20    | mei_me     | 39C0FBE126 |
| 8086:1c3a | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 19    | mei_me     | 5C380FEC25 |
| 8086:2e14 | 103c:3048 | Intel      | 4 Series Chipset HECI Con... | 19    | mei_me     | B511052CC4 |
| 8086:1e3a | 1028:0577 | Intel      | 7 Series/C216 Chipset Fam... | 18    | mei_me     | 87DAB1466B |
| 8086:29b4 | 1028:0211 | Intel      | 82Q35 Express MEI Controller | 18    | mei_me     | 8C1C529BDC |
| 8086:29c4 | 8086:5044 | Intel      | 82G33/G31/P35/P31 Express... | 18    | mei_me     | 969A371A99 |
| 8086:1c3a | 103c:2abf | Intel      | 6 Series/C200 Series Chip... | 17    | mei_me     | 6567AEB3C4 |
| 8086:29a4 | 8086:514d | Intel      | 82P965/G965 HECI Controller  | 16    | mei_me     | 9E17250CD3 |
| 8086:29d4 | 103c:281e | Intel      | 82Q33 Express MEI Controller | 16    | mei_me     | D7AB000EA5 |
| 8086:3b64 | 103c:2a9c | Intel      | 5 Series/3400 Series Chip... | 16    | mei_me     | A585EAEF35 |
| 8086:3b64 | 8086:0036 | Intel      | 5 Series/3400 Series Chip... | 16    | mei_me     | 3462CD0CCD |
| 8086:a13a | 1462:7a15 | Intel      | 100 Series/C230 Series Ch... | 16    | mei_me     | 7C7D8F8CB6 |
| 8086:1c3a | 1019:3190 | Intel      | 6 Series/C200 Series Chip... | 14    | mei_me     | 6D38C064DD |
| 8086:2e14 | 1028:0420 | Intel      | 4 Series Chipset HECI Con... | 14    | mei_me     | 0C9CE69911 |
| 8086:1e3a | 103c:339a | Intel      | 7 Series/C216 Chipset Fam... | 13    | mei_me     | 76F6D2AF22 |
| 8086:2e14 | 1734:114c | Intel      | 4 Series Chipset HECI Con... | 13    | mei_me     | D6D2A25AA4 |
| 14f1:2f30 | 14f1:20d5 | Conexan... | SoftV92 SpeakerPhone Soft... | 12    |            | 16CD9F0B26 |
| 8086:1c3a | 1462:7673 | Intel      | 6 Series/C200 Series Chip... | 12    | mei_me     | 4104F2EABE |
| 8086:1e3a | 1462:7808 | Intel      | 7 Series/C216 Chipset Fam... | 12    | mei_me     | 4120DB4E70 |
| 8086:3b64 | 1462:7636 | Intel      | 5 Series/3400 Series Chip... | 12    | mei_me     | B4F81E84C8 |
| 8086:8c3a | 1462:7816 | Intel      | 8 Series/C220 Series Chip... | 12    | mei_me     | 08BF7B0C07 |
| 14f1:2f20 | 14f1:200c | Conexan... | HSF 56k Data/Fax Modem       | 11    |            | 9E3BA9F39A |
| 14f1:2f20 | 14f1:200f | Conexan... | HSF 56k Data/Fax Modem       | 11    |            | BC9F90FD94 |
| 8086:1d3a | 103c:1589 | Intel      | C600/X79 series chipset M... | 11    | mei_me     | E14EB74EA5 |
| 8086:1d3a | 1458:1c3a | Intel      | C600/X79 series chipset M... | 11    | mei_me     | DD20758A89 |
| 8086:1e3a | 103c:3397 | Intel      | 7 Series/C216 Chipset Fam... | 11    | mei_me     | 195649904F |
| 8086:8c3a | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 11    | mei_me     | 475863E34D |
| 8086:8c3a | 1462:7821 | Intel      | 8 Series/C220 Series Chip... | 11    | mei_me     | 91D43B6213 |
| 8086:8c3a | 1462:7850 | Intel      | 8 Series/C220 Series Chip... | 11    | mei_me     | 0F3DCCFE4E |
| 8086:a2ba | 1043:873c | Intel      | 200 Series PCH CSME HECI #1  | 11    | mei_me     | 30502C41DE |
| 8086:29b4 | 103c:2818 | Intel      | 82Q35 Express MEI Controller | 10    | mei_me     | 6D02866E6C |
| 8086:2e14 | 103c:3034 | Intel      | 4 Series Chipset HECI Con... | 10    | mei_me     | 5DC57BDE0C |
| 8086:8c3a | 1025:0750 | Intel      | 8 Series/C220 Series Chip... | 10    | mei_me     | 7FDD5F778A |
| 8086:8c3a | 1028:0612 | Intel      | 8 Series/C220 Series Chip... | 10    | mei_me     | BBF6D32B86 |
| 8086:8d3a | 1028:0617 | Intel      | C610/X99 series chipset M... | 10    | mei_me     | 019BFC3983 |
| 9710:9835 | 1000:0012 | MosChip... | PCI 9835 Multi-I/O Contro... | 10    | parport... | A3A5486DDC |
| 14f1:10b6 | 14f1:10b6 | Conexan... | CX06834-11 HCF V.92 56k D... | 9     |            | 151D253025 |
| 8086:1c3a | 1019:7b97 | Intel      | 6 Series/C200 Series Chip... | 9     | mei_me     | 1BF34F6B5A |
| 8086:1c3a | 103c:1497 | Intel      | 6 Series/C200 Series Chip... | 9     | mei_me     | 6227F00E30 |
| 8086:1e3a | 1462:7752 | Intel      | 7 Series/C216 Chipset Fam... | 9     | mei_me     | C0B520C2B2 |
| 8086:2994 | 103c:2801 | Intel      | 82Q963/Q965 HECI Controller  | 9     | mei_me     | 086180546A |
| 8086:29b4 | 1043:8295 | Intel      | 82Q35 Express MEI Controller | 9     | mei_me     | 9057FD4986 |
| 8086:3b64 | 8086:3b64 | Intel      | 5 Series/3400 Series Chip... | 9     | mei_me     | 046006226D |
| 8086:8c3a | 1462:7823 | Intel      | 8 Series/C220 Series Chip... | 9     | mei_me     | 4C0C5DE2E6 |
| 8086:8cba | 1462:7850 | Intel      | 9 Series Chipset Family M... | 9     | mei_me     | 847A0934D7 |
| 8086:1c3a | 1025:0589 | Intel      | 6 Series/C200 Series Chip... | 8     | mei_me     | EDE121860B |
| 8086:1c3a | 1028:047e | Intel      | 6 Series/C200 Series Chip... | 8     | mei_me     | 5C7816B17A |
| 8086:1c3a | 103c:1495 | Intel      | 6 Series/C200 Series Chip... | 8     | mei_me     | 3D9E77AE8A |
| 8086:1c3a | 17aa:308c | Intel      | 6 Series/C200 Series Chip... | 8     | mei_me     | 96A1EAB120 |
| 8086:1c3a | 8086:1c3a | Intel      | 6 Series/C200 Series Chip... | 8     | mei_me     | 000C50C428 |
| 8086:1c3a | 8086:2017 | Intel      | 6 Series/C200 Series Chip... | 8     | mei_me     | C2DCE3184C |
| 8086:29b4 | 8086:4f4a | Intel      | 82Q35 Express MEI Controller | 8     | mei_me     | 7F57AD053D |
| 8086:2e14 | 103c:3646 | Intel      | 4 Series Chipset HECI Con... | 8     | mei_me     | 878673A8E4 |
| 8086:2e14 | 17aa:3048 | Intel      | 4 Series Chipset HECI Con... | 8     | mei_me     | D44E51F592 |
| 8086:8c3a | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 8     | mei_me     | 24870345D1 |
| 8086:8c3a | 1462:7851 | Intel      | 8 Series/C220 Series Chip... | 8     | mei_me     | B0BE456A64 |
| 8086:8cba | 1462:7917 | Intel      | 9 Series Chipset Family M... | 8     | mei_me     | 6A9086BF86 |
| 11c1:048c | 11c1:044c | LSI        | V.92 56K WinModem            | 7     |            | 6A798F999C |
| 11c1:0620 | 11c1:0620 | LSI        | Lucent V.92 Data/Fax Modem   | 7     |            | 005023EE9D |
| 14f1:2f00 | 14f1:2004 | Conexan... | HSF 56k HSFi Modem           | 7     |            | C78BDF01D1 |
| 8086:1c3a | 1019:7df5 | Intel      | 6 Series/C200 Series Chip... | 7     | mei_me     | AA36029D7F |
| 8086:1c3a | 1025:0493 | Intel      | 6 Series/C200 Series Chip... | 7     | mei_me     | 87868C9316 |
| 8086:1c3a | 1028:04aa | Intel      | 6 Series/C200 Series Chip... | 7     | mei_me     | FED40374F1 |
| 8086:1c3a | 1028:04f5 | Intel      | 6 Series/C200 Series Chip... | 7     | mei_me     | 4C2D54B4E5 |
| 8086:1c3a | 1028:0585 | Intel      | 6 Series/C200 Series Chip... | 7     | mei_me     | 0C9D9C254F |
| 8086:1c3a | 103c:2ab5 | Intel      | 6 Series/C200 Series Chip... | 7     | mei_me     | C87217D642 |
| 8086:1c3a | 1462:7681 | Intel      | 6 Series/C200 Series Chip... | 7     | mei_me     | 6561B662F9 |
| 8086:1c3a | 1734:11ba | Intel      | 6 Series/C200 Series Chip... | 7     | mei_me     | 72CEF14842 |
| 8086:1c3a | 17aa:3077 | Intel      | 6 Series/C200 Series Chip... | 7     | mei_me     | CB4983BAF6 |

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
| 1022:1456 | 1022:1456 | AMD        | Family 17h (Models 00h-0f... | 275   | ccp        | D084D64BDF |
| 1022:15df | 1022:15df | AMD        | Family 17h (Models 10h-1f... | 77    |            | E090419355 |
| 1022:1456 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 37    | ccp        | 4A2455EAE6 |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 22    |            | 37D7E42722 |
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 22    | mei_txe    | 6053E60588 |
| 8086:0f18 | 8086:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 21    | mei_txe    | BAE419604E |
| 8086:0f18 | 1849:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 18    | mei_txe    | EF6230C726 |
| 8086:0f18 | 1458:1c3a | Intel      | Atom Processor Z36xxx/Z37... | 13    | mei_txe    | 2D2468C273 |
| 1022:15df | 1043:876b | AMD        | Family 17h (Models 10h-1f... | 11    |            | 76E2078928 |
| 8086:0f18 | 1043:8534 | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | 7F66D8C94D |
| 8086:2298 | 1043:8534 | Intel      | Atom/Celeron/Pentium Proc... | 7     | mei_txe    | 9BB60AEDD5 |
| 8086:2298 | 1458:1000 | Intel      | Atom/Celeron/Pentium Proc... | 7     | mei_txe    | 39694A0489 |
| 1022:1456 | 1462:7a38 | AMD        | Family 17h (Models 00h-0f... | 6     | ccp        | 4B9FC100D8 |
| 8086:0f18 | 17aa:368d | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | E04CCB489C |
| 8086:2298 | 1849:2298 | Intel      | Atom/Celeron/Pentium Proc... | 5     | mei_txe    | 4A3BD3D31E |
| 1022:1537 | 1022:1537 | AMD        | Kabini/Mullins PSP-Platfo... | 4     | ccp        | 50919B2DDB |
| 1022:15df | 1462:7c02 | AMD        | Family 17h (Models 10h-1f... | 4     |            | 74440073DF |
| 8086:0f18 | 8086:2055 | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 4C2CE64AE4 |
| 8086:2298 | 103c:821d | Intel      | Atom/Celeron/Pentium Proc... | 4     | mei_txe    | 46064EAB76 |
| 8086:2298 | 1458:1c3a | Intel      | Atom/Celeron/Pentium Proc... | 4     | mei_txe    | 5B47EB5CFD |
| 1022:15df | 1462:7a38 | AMD        | Family 17h (Models 10h-1f... | 3     |            | 0D21F94B25 |
| 8086:0f18 | 1019:7ed4 | Intel      | Atom Processor Z36xxx/Z37... | 3     | mei_txe    | 1D7422A66F |
| 8086:0f18 | 1025:085e | Intel      | Atom Processor Z36xxx/Z37... | 3     | mei_txe    | 909A1E4D24 |
| 8086:0f18 | 105b:0db1 | Intel      | Atom Processor Z36xxx/Z37... | 3     | mei_txe    | 0C90B25A45 |
| 8086:2298 | 1025:0953 | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | 1F72AE37E6 |
| 8086:2298 | 17aa:30c9 | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | 97D80013FF |
| 1022:15df | 1462:7b86 | AMD        | Family 17h (Models 10h-1f... | 2     |            | 69D51E68B0 |
| 8086:0f18 | 1019:99ad | Intel      | Atom Processor Z36xxx/Z37... | 2     | mei_txe    | B4F7B429BF |
| 8086:0f18 | 1565:310e | Intel      | Atom Processor Z36xxx/Z37... | 2     | mei_txe    | FCA939A959 |
| 8086:0f18 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 2     | mei_txe    | B4068AB10D |
| 8086:2298 | 1019:9bef | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | A4FB1E5351 |
| 8086:2298 | 1025:1064 | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | 92C3E82D58 |
| 8086:2298 | 8086:2298 | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | DB87D8567E |
| 1022:1456 | 1019:9ce5 | AMD        | Family 17h (Models 00h-0f... | 1     | ccp        | 06776696F3 |
| 1022:1456 | 103c:8399 | AMD        | Family 17h (Models 00h-0f... | 1     | ccp        | 9440F6405B |
| 1022:1456 | 1462:7a40 | AMD        | Family 17h (Models 00h-0f... | 1     | ccp        | 515A7DFA4F |
| 1022:1456 | 1462:7b85 | AMD        | Family 17h (Models 00h-0f... | 1     | ccp        | 29C3842F1D |
| 1022:1456 | 1462:7b86 | AMD        | Family 17h (Models 00h-0f... | 1     | ccp        | 73F23254C0 |
| 1022:1456 | 1462:7b89 | AMD        | Family 17h (Models 00h-0f... | 1     | ccp        | 63314DCB31 |
| 1022:1537 | 103c:21ef | AMD        | Kabini/Mullins PSP-Platfo... | 1     | ccp        | F194D347F2 |
| 1022:1537 | 103c:2b29 | AMD        | Kabini/Mullins PSP-Platfo... | 1     | ccp        | 455DDB0E74 |
| 1022:1537 | 103c:2b4f | AMD        | Kabini/Mullins PSP-Platfo... | 1     | ccp        | 188B0E90BC |
| 1022:1578 | 17aa:3100 | AMD        | Carrizo Platform Security... | 1     |            | 5BD277D767 |
| 1022:15df | 1462:7b87 | AMD        | Family 17h (Models 10h-1f... | 1     |            | 6B3081B433 |
| 1022:15df | 17aa:36e8 | AMD        | Family 17h (Models 10h-1f... | 1     |            | 78596220D1 |
| 1172:8004 |           | Altera     | Encryption controller        | 1     | altera_cvp | 0D2A7EFA14 |
| 8086:0f18 |           | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | F88234F842 |
| 8086:0f18 | 1019:99cf | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | 409DBDEF33 |
| 8086:0f18 | 1028:068d | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | 65A9CF6ADE |
| 8086:0f18 | 1071:0730 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | DAD78E5959 |
| 8086:0f18 | 1297:4019 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | 03AF7DBE17 |
| 8086:0f18 | 1458:1000 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | 8E5B085C94 |
| 8086:0f18 | 17aa:3688 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | A88328FDB9 |
| 8086:0f18 | 1b0a:017f | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | A303253DA2 |
| 8086:2298 | 1025:101c | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | 6003A69BD5 |
| 8086:2298 | 1028:06f6 | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | 0784C6115A |
| 8086:2298 | 1028:07c1 | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | 9F4F497293 |

### Entertainment encryption device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:2082 | 1022:2082 | AMD        | Geode LX AES Security Block  | 1     | geode_r... | 6D9551F87E |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 104c:8024 | 1458:1000 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 353   | firewir... | 8EAEF3C906 |
| 1106:3044 | 1043:81fe | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 331   | firewir... | B481805845 |
| 1106:3044 | 1458:1000 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 94    | firewir... | 394C81B911 |
| 11c1:5811 | 1043:8294 | LSI        | FW322/323 [TrueFire] 1394... | 92    | firewir... | 29B7777E42 |
| 1106:3403 | 1043:8384 | VIA Tec... | VT6315 Series Firewire Co... | 83    | firewir... | AC377EFFFB |
| 1106:3044 | 1106:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 78    | firewir... | B26ED41AB8 |
| 1102:4001 | 1102:0010 | Creativ... | SB Audigy FireWire Port      | 62    | firewir... | 7A74EB0F6F |
| 104c:8023 | 1043:808b | Texas I... | TSB43AB22A IEEE-1394a-200... | 48    | firewir... | 38155B66BB |
| 1106:3403 | 1849:3403 | VIA Tec... | VT6315 Series Firewire Co... | 41    | firewir... | 7B99FD4C95 |
| 1106:3403 | 1043:8374 | VIA Tec... | VT6315 Series Firewire Co... | 26    | firewir... | 054E0BF393 |
| 197b:2380 | 1043:8313 | JMicron... | IEEE 1394 Host Controller    | 26    | firewir... | 6ED85C31F2 |
| 104c:8023 | 1043:815b | Texas I... | TSB43AB22A IEEE-1394a-200... | 20    | firewir... | 6932570C80 |
| 1106:3403 | 103c:2a9c | VIA Tec... | VT6315 Series Firewire Co... | 15    | firewir... | A585EAEF35 |
| 1106:3044 | 1043:808a | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 13    | firewir... | A4A45B8A8B |
| 11c1:5811 | 103c:2a6f | LSI        | FW322/323 [TrueFire] 1394... | 13    | firewir... | AA83F14B99 |
| 104c:8023 | 8086:514d | Texas I... | TSB43AB22A IEEE-1394a-200... | 12    | firewir... | 9E17250CD3 |
| 11c1:5811 | 103c:1589 | LSI        | FW322/323 [TrueFire] 1394... | 12    | firewir... | E14EB74EA5 |
| 104c:823f |           | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 11    | firewir... | AA53E34C56 |
| 11c1:5811 | 103c:1309 | LSI        | FW322/323 [TrueFire] 1394... | 11    | firewir... | 5A8BAD0B76 |
| 104c:8023 | 8086:5044 | Texas I... | TSB43AB22A IEEE-1394a-200... | 10    | firewir... | 969A371A99 |
| 11c1:5811 | 11c1:5811 | LSI        | FW322/323 [TrueFire] 1394... | 10    | firewir... | 082313CDB6 |
| 1106:3044 | 1106:0404 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 9     | firewir... | 5302586F9D |
| 1106:3044 | 1849:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 9     | firewir... | C44B707FC4 |
| 1106:3403 | 1106:3403 | VIA Tec... | VT6315 Series Firewire Co... | 9     | firewir... | D77F80F180 |
| 104c:8024 | 1019:8056 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 8     | firewir... | 5647BADC5C |
| 1106:3044 | 17f2:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 8     | firewir... | 7B106B9427 |
| 1033:00f2 | 1033:00f2 | NEC Com... | uPD72874 [Firewarden] IEE... | 7     | firewir... | B99C2286C9 |
| 1106:3044 | 1025:8010 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 7     | firewir... | A4DA822D7B |
| 11c1:5811 | 1028:5811 | LSI        | FW322/323 [TrueFire] 1394... | 7     | firewir... | A72C60B73B |
| 104c:8023 | 1849:8023 | Texas I... | TSB43AB22A IEEE-1394a-200... | 6     | firewir... | 34021FD6BD |
| 1106:3044 | 1043:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 6     | firewir... | F479FA880E |
| 1106:3044 | 1462:502d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 6     | firewir... | 3E9F34C334 |
| 11bd:0015 | 11bd:0022 | Pinnacl... | FireWire IEEE1394            | 6     | firewir... | FDF3041748 |
| 11c1:5811 | 103c:158a | LSI        | FW322/323 [TrueFire] 1394... | 6     | firewir... | 2AB82BCF03 |
| 104c:823f | 3412:7856 | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 5     | firewir... | 92F011CFCF |
| 1106:3044 |           | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 5     | firewir... | A169B93D1F |
| 11c1:5811 | 103c:2a66 | LSI        | FW322/323 [TrueFire] 1394... | 5     | firewir... | B3F948427E |
| 1033:00f2 | 104d:811e | NEC Com... | uPD72874 [Firewarden] IEE... | 4     | firewir... | F1E5880584 |
| 104c:8024 | 105b:0e0a | Texas I... | TSB43AB23 IEEE-1394a-2000... | 4     | firewir... | AD85843155 |
| 104c:8025 |           | Texas I... | TSB82AA2 IEEE-1394b Link ... | 4     | firewir... | 37E5DABF3C |
| 104c:8025 | 1458:1000 | Texas I... | TSB82AA2 IEEE-1394b Link ... | 4     | firewir... | 556AE96F13 |
| 1106:3044 | 103c:2a24 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 4     | firewir... | F93B42EEF8 |
| 1106:3044 | 103c:2a61 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 4     | firewir... | 2B1F0714E0 |
| 1106:3044 | 103c:2a6d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 4     | firewir... | 092205321D |
| 1106:3044 | 1043:2a22 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 4     | firewir... | C1C7D412FB |
| 1106:3403 | 1025:024c | VIA Tec... | VT6315 Series Firewire Co... | 4     | firewir... | A2DBF52E17 |
| 11c1:5811 | 103c:2a34 | LSI        | FW322/323 [TrueFire] 1394... | 4     | firewir... | 11EC1ACB37 |
| 11c1:5811 | 1734:1026 | LSI        | FW322/323 [TrueFire] 1394... | 4     | firewir... | 102A89A278 |
| 11c1:5811 | 8086:2008 | LSI        | FW322/323 [TrueFire] 1394... | 4     | firewir... | A44CE70FF7 |
| 197b:2380 | 197b:2380 | JMicron... | IEEE 1394 Host Controller    | 4     | firewir... | 4E72D045DC |
| 1033:00e7 | 1033:00ce | NEC Com... | uPD72873 [Firewarden] IEE... | 3     | firewir... | D2E8E4CA3D |
| 104c:8023 | 1028:021d | Texas I... | TSB43AB22A IEEE-1394a-200... | 3     | firewir... | FFC0ECBF18 |
| 104c:8023 | 147b:1084 | Texas I... | TSB43AB22A IEEE-1394a-200... | 3     | firewir... | 5C0FC04230 |
| 104c:8023 | 8086:4257 | Texas I... | TSB43AB22A IEEE-1394a-200... | 3     | firewir... | 78B4FE060A |
| 104c:8023 | 8086:4f43 | Texas I... | TSB43AB22A IEEE-1394a-200... | 3     | firewir... | 1847B52353 |
| 104c:8024 | 1028:1000 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 3     | firewir... | A8D0FA2257 |
| 104c:8024 | 1b5b:010a | Texas I... | TSB43AB23 IEEE-1394a-2000... | 3     | firewir... | 45BCD84783 |
| 104c:8024 | 8086:4e53 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 3     | firewir... | 4EE2A84A23 |
| 104c:8025 | 1043:813c | Texas I... | TSB82AA2 IEEE-1394b Link ... | 3     | firewir... | 87F8B4B22A |
| 1106:3044 | 1462:091d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 3     | firewir... | E8794A0676 |
| 1106:3044 | 1462:238d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 3     | firewir... | CE49F9F59A |
| 1106:3044 | 1462:350d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 3     | firewir... | 92728C6648 |
| 1106:3044 | 1462:376d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 3     | firewir... | 6DEE7C879B |
| 1106:3044 | 1695:900e | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 3     | firewir... | 02CEB963E5 |
| 1106:3403 | 1025:024d | VIA Tec... | VT6315 Series Firewire Co... | 3     | firewir... | 9E417BE017 |
| 1106:3403 | 1025:0250 | VIA Tec... | VT6315 Series Firewire Co... | 3     | firewir... | CB4BD052FC |
| 1106:3403 | 1462:576d | VIA Tec... | VT6315 Series Firewire Co... | 3     | firewir... | D7C5C9A383 |
| 1106:3403 | 1462:7616 | VIA Tec... | VT6315 Series Firewire Co... | 3     | firewir... | B9274F20A6 |
| 1106:3403 | 8086:2001 | VIA Tec... | VT6315 Series Firewire Co... | 3     | firewir... | 34DBD882BE |
| 11bd:0015 | 11bd:0023 | Pinnacl... | FireWire IEEE1394            | 3     | firewir... | EBD8A5801D |
| 11c1:5811 | 1028:8010 | LSI        | FW322/323 [TrueFire] 1394... | 3     | firewir... | 0B9FEF01EC |
| 11c1:5811 | 103c:130a | LSI        | FW322/323 [TrueFire] 1394... | 3     | firewir... | 1F84E6825F |
| 11c1:5811 | 103c:2a50 | LSI        | FW322/323 [TrueFire] 1394... | 3     | firewir... | 6FC9B4048B |
| 11c1:5811 | 103c:2a58 | LSI        | FW322/323 [TrueFire] 1394... | 3     | firewir... | 32AE4212DF |
| 11c1:5811 | 103c:2a6c | LSI        | FW322/323 [TrueFire] 1394... | 3     | firewir... | A24AC2DE87 |
| 11c1:5811 | 11bd:000e | LSI        | FW322/323 [TrueFire] 1394... | 3     | firewir... | 4732CE2414 |
| 11c1:5811 | 8086:0024 | LSI        | FW322/323 [TrueFire] 1394... | 3     | firewir... | 363DBD925B |
| 197b:2380 | 1025:031f | JMicron... | IEEE 1394 Host Controller    | 3     | firewir... | 8770D9E3AD |
| 197b:2380 | 1462:512d | JMicron... | IEEE 1394 Host Controller    | 3     | firewir... | 7999E0452A |
| 197b:2380 | 1462:7646 | JMicron... | IEEE 1394 Host Controller    | 3     | firewir... | 0BE5F7A9E8 |
| 1006:3044 | 1006:3044 | Reply G... | Reply FireWire (IEEE 1394)   | 2     | firewir... | 297E534CF0 |
| 104c:8020 | 15c5:8010 | Texas I... | TSB12LV26 IEEE-1394 Contr... | 2     | firewir... | F2EC6A0A02 |
| 104c:8023 |           | Texas I... | TSB43AB22A IEEE-1394a-200... | 2     | firewir... | 323982480D |
| 104c:8023 | 104c:8023 | Texas I... | TSB43AB22A IEEE-1394a-200... | 2     | firewir... | 0D2E8C1F17 |
| 104c:8023 | 147b:1083 | Texas I... | TSB43AB22A IEEE-1394a-200... | 2     | firewir... | DDBD6F8246 |
| 104c:8023 | 8086:424b | Texas I... | TSB43AB22A IEEE-1394a-200... | 2     | firewir... | 05A4F47131 |
| 104c:8023 | 8086:4742 | Texas I... | TSB43AB22A IEEE-1394a-200... | 2     | firewir... | 87533B7EF3 |
| 104c:8024 |           | Texas I... | TSB43AB23 IEEE-1394a-2000... | 2     | firewir... | 9BD2F03817 |
| 104c:8024 | 105b:0c9e | Texas I... | TSB43AB23 IEEE-1394a-2000... | 2     | firewir... | 1E807288A2 |
| 104c:8024 | 8086:544e | Texas I... | TSB43AB23 IEEE-1394a-2000... | 2     | firewir... | 23BAC57788 |
| 104c:8024 | 8086:5842 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 2     | firewir... | BC81595AD7 |
| 104c:8025 | 1409:3110 | Texas I... | TSB82AA2 IEEE-1394b Link ... | 2     | firewir... | 48B2ED99AE |
| 10b9:5253 | 10b9:5253 | ULi Ele... | M5253 P1394 OHCI 1.1 Cont... | 2     | firewir... | E44FBB6E80 |
| 10de:006e | 1043:809a | Nvidia     | nForce2 FireWire (IEEE 13... | 2     | firewir... | 543960170E |
| 1106:3044 | 00ff:9a01 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 2     | firewir... | C46668413C |
| 1106:3044 | 1019:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 2     | firewir... | EB188637A2 |
| 1106:3044 | 1025:025d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 2     | firewir... | 8C28446A53 |
| 1106:3044 | 103c:2a64 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 2     | firewir... | A20DD4DABA |
| 1106:3044 | 103c:2a65 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 2     | firewir... | 71ECB869B0 |
| 1106:3044 | 103c:2a92 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 2     | firewir... | C620D9EB5A |

### Flash memory (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1524:0510 | 1524:0510 | ENE Tec... | CB710 Memory Card Reader ... | 1     | cb710      | 10AFC2AC6A |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1451 | 1022:1451 | AMD        | Family 17h (Models 00h-0f... | 187   |            | D084D64BDF |
| 1002:5a23 | 1002:5a23 | AMD        | RD890S/RD990 I/O Memory M... | 121   |            | B77180A9F5 |
| 1022:1419 | 1022:1419 | AMD        | Family 15h (Models 10h-1f... | 107   |            | 32E1C72BAA |
| 1002:5a23 | 1462:7693 | AMD        | RD890S/RD990 I/O Memory M... | 47    |            | FEAA959521 |
| 1022:1419 | 1462:7721 | AMD        | Family 15h (Models 10h-1f... | 19    |            | B801DD3F7D |
| 1022:1423 | 1462:7721 | AMD        | Family 15h (Models 30h-3f... | 19    |            | BA5B7B57D6 |
| 1022:1423 | 1022:1423 | AMD        | Family 15h (Models 30h-3f... | 17    |            | 33CFE3D019 |
| 1022:1423 | 1043:85cb | AMD        | Family 15h (Models 30h-3f... | 11    |            | BE7AE862C6 |
| 1022:1577 | 1022:1577 | AMD        | Family 15h (Models 60h-6f... | 10    |            | 37D7E42722 |
| 1022:1419 | 1462:7895 | AMD        | Family 15h (Models 10h-1f... | 8     |            | FD55D656A8 |
| 1002:5a23 | 1462:7640 | AMD        | RD890S/RD990 I/O Memory M... | 6     |            | 23ACB95370 |
| 1002:5a23 | 1458:5000 | AMD        | RD890S/RD990 I/O Memory M... | 5     |            | 792BC1DD6F |
| 1002:5a23 | 1462:7974 | AMD        | RD890S/RD990 I/O Memory M... | 5     |            | 83FB735308 |
| 1022:1423 | 1462:7895 | AMD        | Family 15h (Models 30h-3f... | 5     |            | E1D561ABB4 |
| 1022:1419 | 1019:7c8d | AMD        | Family 15h (Models 10h-1f... | 3     |            | 8A37732F55 |
| 1022:1419 | 1025:070b | AMD        | Family 15h (Models 10h-1f... | 2     |            | F083D73A9E |
| 1022:1419 | 1043:8526 | AMD        | Family 15h (Models 10h-1f... | 2     |            | 7EFEC12422 |
| 1022:1419 | 1462:7900 | AMD        | Family 15h (Models 10h-1f... | 1     |            | 985C8F6BB3 |
| 1022:1419 | 17aa:36a0 | AMD        | Family 15h (Models 10h-1f... | 1     |            | BA1A484E84 |
| 1022:1423 | 1462:7793 | AMD        | Family 15h (Models 30h-3f... | 1     |            | 54040FA02B |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0412 | 1458:d000 | Intel      | Xeon E3-1200 v3/4th Gen C... | 124   | i915       | DD4DA32934 |
| 8086:0102 | 1043:844d | Intel      | 2nd Generation Core Proce... | 96    | i915       | CF410274A0 |
| 8086:0102 | 1458:d000 | Intel      | 2nd Generation Core Proce... | 82    | i915       | A1E970227D |
| 8086:0412 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 78    | i915       | B61D174C21 |
| 10de:0a65 |           | Nvidia     | GT218 [GeForce 210]          | 73    | nouveau    | 7267B22360 |
| 10de:0615 |           | Nvidia     | G92 [GeForce GTS 250]        | 71    | nvidia     | 1114B40A02 |
| 10de:0622 |           | Nvidia     | G94 [GeForce 9600 GT]        | 68    | nvidia     | E3128E9139 |
| 10de:0de0 |           | Nvidia     | GF108 [GeForce GT 440]       | 67    | nouveau    | 88E3DD8AEA |
| 10de:0640 |           | Nvidia     | G96C [GeForce 9500 GT]       | 66    | nouveau    | 71B889E4FD |
| 8086:0152 | 1458:d000 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 66    | i915       | 9FF94DE707 |
| 10de:128b | 1462:8c93 | Nvidia     | GK208B [GeForce GT 710]      | 65    | nouveau    | 606AACED27 |
| 8086:29c2 | 1043:82b0 | Intel      | 82G33/G31 Express Integra... | 63    | i915       | 85261DC7A2 |
| 10de:0614 |           | Nvidia     | G92 [GeForce 9800 GT]        | 60    | nouveau    | 54F8BAB8A3 |
| 10de:1244 |           | Nvidia     | GF116 [GeForce GTX 550 Ti]   | 58    | nouveau    | 0414258B09 |
| 8086:2e32 | 1043:836d | Intel      | 4 Series Chipset Integrat... | 58    | i915       | D81A6BB2A7 |
| 8086:0402 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 57    | i915       | 08D84A1FF9 |
| 10de:0ca3 |           | Nvidia     | GT215 [GeForce GT 240]       | 56    | nvidia     | 20093DA7FB |
| 1002:9616 | 1043:8388 | AMD        | RS780L [Radeon 3000]         | 55    | radeon     | D569843A2D |
| 8086:2772 | 1043:817a | Intel      | 82945G/GZ Integrated Grap... | 54    | i915       | C701909BC8 |
| 10de:0de1 |           | Nvidia     | GF108 [GeForce GT 430]       | 52    | nouveau    | 4B83E684CA |
| 10de:0f00 | 1569:0f00 | Nvidia     | GF108 [GeForce GT 630]       | 52    | nouveau    | F99AFC78BD |
| 10de:0fc6 | 1569:0fc6 | Nvidia     | GK107 [GeForce GTX 650]      | 51    | nvidia     | 230E4F00BA |
| 8086:29c2 | 1849:29c2 | Intel      | 82G33/G31 Express Integra... | 51    | i915       | 42C519E784 |
| 8086:0152 | 1043:844d | Intel      | Xeon E3-1200 v2/3rd Gen C... | 48    | i915       | 154C64D953 |
| 10de:03d6 | 1849:03d6 | Nvidia     | C61 [GeForce 7025 / nForc... | 42    | nouveau    | 88EC731DFB |
| 8086:2e32 | 1458:d000 | Intel      | 4 Series Chipset Integrat... | 41    | i915       | D0D6CD20B1 |
| 10de:0402 |           | Nvidia     | G84 [GeForce 8600 GT]        | 40    | nouveau    | F2DFFD30F5 |
| 8086:0152 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 40    | i915       | E3C3739395 |
| 8086:29c2 | 1458:d000 | Intel      | 82G33/G31 Express Integra... | 40    | i915       | 22D8D62C57 |
| 8086:1912 | 1043:8694 | Intel      | HD Graphics 530              | 39    | i915       | 99614383EB |
| 1002:9616 | 1458:d000 | AMD        | RS780L [Radeon 3000]         | 37    | radeon     | ED68722348 |
| 8086:2772 | 1458:d000 | Intel      | 82945G/GZ Integrated Grap... | 37    | i915       | 080AE7C292 |
| 8086:5912 | 1043:8694 | Intel      | HD Graphics 630              | 37    | i915       | BD3CFBCE71 |
| 10de:11c0 | 1569:11c0 | Nvidia     | GK106 [GeForce GTX 660]      | 36    | nvidia     | E4A1AC8DFE |
| 10de:0a65 | 1462:8094 | Nvidia     | GT218 [GeForce 210]          | 35    | nvidia     | FA683DF592 |
| 8086:041e | 1458:d000 | Intel      | 4th Generation Core Proce... | 35    | i915       | BEBF195E43 |
| 1002:68f9 | 174b:e164 | AMD        | Cedar [Radeon HD 5000/600... | 33    | radeon     | EBB5316694 |
| 10de:0641 |           | Nvidia     | G96C [GeForce 9400 GT]       | 33    | nvidia     | 54231260FF |
| 10de:0a20 |           | Nvidia     | GT216 [GeForce GT 220]       | 33    | nouveau    | EF3F0A5B2B |
| 10de:0dc4 |           | Nvidia     | GF106 [GeForce GTS 450]      | 33    | nvidia     | DEB6214FDD |
| 8086:0402 | 1458:d000 | Intel      | Xeon E3-1200 v3/4th Gen C... | 33    | i915       | 7B12481536 |
| 8086:041e | 1043:8534 | Intel      | 4th Generation Core Proce... | 33    | i915       | 2656A5F4E6 |
| 10de:1380 | 1043:84bb | Nvidia     | GM107 [GeForce GTX 750 Ti]   | 31    | nvidia     | 32D6CC8A86 |
| 8086:0102 | 1849:0102 | Intel      | 2nd Generation Core Proce... | 31    | i915       | DCC0E8E5F5 |
| 8086:0152 | 1849:0152 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 30    | i915       | 3D8C4FEBC3 |
| 1002:15dd | 1043:876b | AMD        | Raven Ridge [Radeon Vega ... | 29    | amdgpu     | 76E2078928 |
| 10de:0f00 | 1458:3544 | Nvidia     | GF108 [GeForce GT 630]       | 29    | nouveau    | 9204CB3BAC |
| 10de:0fc1 | 1569:0fc1 | Nvidia     | GK107 [GeForce GT 640]       | 29    | nouveau    | ADD4F52268 |
| 10de:11c0 | 1458:354e | Nvidia     | GK106 [GeForce GTX 660]      | 29    | nouveau    | 0FA01E4D66 |
| 10de:0322 |           | Nvidia     | NV34 [GeForce FX 5200]       | 28    | nouveau    | C3F87286B5 |
| 10de:1c82 | 1462:8c96 | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 28    | nvidia     | 6D9668A464 |
| 8086:0162 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 28    | i915       | 570B707FFB |
| 8086:0402 | 1462:7817 | Intel      | Xeon E3-1200 v3/4th Gen C... | 28    | i915       | 9770B67FA6 |
| 10de:0421 |           | Nvidia     | G86 [GeForce 8500 GT]        | 27    | nouveau    | 8214980C4C |
| 10de:0fc6 | 1458:3553 | Nvidia     | GK107 [GeForce GTX 650]      | 27    | nouveau    | 5F582A0578 |
| 10de:10c3 |           | Nvidia     | GT218 [GeForce 8400 GS Re... | 27    | nouveau    | 85F57C764C |
| 1002:67df | 1da2:e366 | AMD        | Ellesmere [Radeon RX 470/... | 26    | amdgpu     | 394C81B911 |
| 10de:0fc1 | 1043:83f3 | Nvidia     | GK107 [GeForce GT 640]       | 26    | nouveau    | BC68308D9C |
| 10de:1245 |           | Nvidia     | GF116 [GeForce GTS 450 Re... | 26    | nouveau    | 3D266E48F2 |
| 10de:0392 |           | Nvidia     | G73 [GeForce 7600 GS]        | 24    | nouveau    | 5BCDAFD426 |
| 10de:1380 | 1458:362d | Nvidia     | GM107 [GeForce GTX 750 Ti]   | 24    | nvidia     | B34F330B92 |
| 10de:1c82 | 10de:1c82 | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 24    | nvidia     | 01EB97A943 |
| 8086:0102 | 1043:84ca | Intel      | 2nd Generation Core Proce... | 24    | i915       | F3E244219B |
| 8086:0412 | 1849:0412 | Intel      | Xeon E3-1200 v3/4th Gen C... | 24    | i915       | 6BDC4A2A9B |
| 8086:1912 | 1458:d000 | Intel      | HD Graphics 530              | 24    | i915       | DBB5ADCE58 |
| 1002:6758 | 174b:e194 | AMD        | Turks XT [Radeon HD 6670/... | 23    | radeon     | A420D17B64 |
| 1002:6759 | 174b:e193 | AMD        | Turks PRO [Radeon HD 6570... | 23    | radeon     | DF39CB5EE3 |
| 10de:0393 |           | Nvidia     | G73 [GeForce 7300 GT]        | 23    | nouveau    | 77FDA1B520 |
| 10de:0a65 | 1043:83f4 | Nvidia     | GT218 [GeForce 210]          | 23    | nouveau    | 81D8954A1C |
| 10de:0a65 | 1458:3525 | Nvidia     | GT218 [GeForce 210]          | 23    | nouveau    | A1ADC281B3 |
| 10de:1040 |           | Nvidia     | GF119 [GeForce GT 520]       | 23    | nouveau    | BF6981FAB9 |
| 10de:1d01 | 1462:8c98 | Nvidia     | GP108 [GeForce GT 1030]      | 23    | nouveau    | E4C2A9F4EB |
| 10de:1187 | 1043:847a | Nvidia     | GK104 [GeForce GTX 760]      | 22    | nvidia     | A585EAEF35 |
| 10de:1380 | 1043:84be | Nvidia     | GM107 [GeForce GTX 750 Ti]   | 22    | nvidia     | 834628BB5E |
| 10de:0f00 | 1043:8400 | Nvidia     | GF108 [GeForce GT 630]       | 21    | nouveau    | 4ADDC7302B |
| 10de:0f02 | 1462:8a9f | Nvidia     | GF108 [GeForce GT 730]       | 21    | nouveau    | 16C4C7C1C0 |
| 1002:6779 | 174b:a004 | AMD        | Caicos [Radeon HD 6450/74... | 20    | radeon     | A5BBF4389F |
| 10de:0fc6 | 1462:8a96 | Nvidia     | GK107 [GeForce GTX 650]      | 20    | nouveau    | C41FAC8640 |
| 8086:1902 | 1043:8694 | Intel      | HD Graphics 510              | 20    | i915       | 0A749C0738 |
| 1002:15dd | 1002:15dd | AMD        | Raven Ridge [Radeon Vega ... | 19    | amdgpu     | FDD7A2F512 |
| 1002:6613 | 174b:e263 | AMD        | Oland PRO [Radeon R7 240/... | 19    | radeon     | 7CB5494874 |
| 10de:0a65 | 1043:848e | Nvidia     | GT218 [GeForce 210]          | 19    | nouveau    | 6809C88E52 |
| 10de:0f02 | 1458:365b | Nvidia     | GF108 [GeForce GT 730]       | 19    | nouveau    | 6C7C70F0E2 |
| 10de:0fc6 | 1458:3555 | Nvidia     | GK107 [GeForce GTX 650]      | 19    | nouveau    | 6A6FF6EC8A |
| 10de:104a | 1462:809f | Nvidia     | GF119 [GeForce GT 610]       | 19    | nouveau    | 3D9E77AE8A |
| 10de:104a | 1569:104a | Nvidia     | GF119 [GeForce GT 610]       | 19    | nouveau    | B378AD2452 |
| 10de:11c0 | 1043:8422 | Nvidia     | GK106 [GeForce GTX 660]      | 19    | nvidia     | 74DEA1731E |
| 8086:29c2 | 1462:7529 | Intel      | 82G33/G31 Express Integra... | 19    | i915       | 95C164BFE9 |
| 8086:2e32 | 1462:7592 | Intel      | 4 Series Chipset Integrat... | 19    | i915       | 0CDA55A753 |
| 8086:5912 | 1458:d000 | Intel      | HD Graphics 630              | 19    | i915       | 936BEEBE68 |
| 1002:68d9 | 174b:e142 | AMD        | Redwood PRO [Radeon HD 55... | 18    | radeon     | A192868848 |
| 10de:03d0 | 1043:8234 | Nvidia     | C61 [GeForce 6150SE nForc... | 18    | nouveau    | 2F49EDDD49 |
| 10de:0a65 | 1043:8354 | Nvidia     | GT218 [GeForce 210]          | 18    | nouveau    | EB0CDD472F |
| 10de:104a | 1043:8417 | Nvidia     | GF119 [GeForce GT 610]       | 18    | nouveau    | 3602A90378 |
| 8086:0162 | 1458:d000 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 18    | i915       | 41F60D966A |
| 8086:0162 | 1849:0162 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 18    | i915       | BDA40E6195 |
| 8086:0402 | 1849:0402 | Intel      | Xeon E3-1200 v3/4th Gen C... | 18    | i915       | 8AE6B6F651 |
| 8086:0f31 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 18    | i915       | BAE419604E |
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 18    | i915       | 6053E60588 |
| 1002:6779 | 1043:03da | AMD        | Caicos [Radeon HD 6450/74... | 17    | radeon     | 0EE338DA52 |

### I/o card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10e8:80d8 |           | Applied... | PCI-7200 40MB/s 32-channe... | 1     |            | 3864E6C70F |

### Input device controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1102:7002 | 1102:0020 | Creativ... | SB Live! Game Port           | 82    | emu10k1_gp | 6D9668A464 |
| 1102:7003 | 1102:0040 | Creativ... | SB Audigy Game Port          | 51    | emu10k1_gp | C80D56CB77 |
| 1102:7003 | 1102:0060 | Creativ... | SB Audigy Game Port          | 12    | emu10k1_gp | 7A74EB0F6F |
| 1319:0802 | 1319:1319 | Fortemedia | Xwave QS3000A [FM801 game... | 6     | fm801_gp   | 6AB359DC43 |
| 1102:7004 | 1102:1003 | Creativ... | [SB Live! Value] Input de... | 1     | emu10k1_gp | B7C8E17F50 |
| 1102:7005 | 1102:1002 | Creativ... | SB Audigy LS Game Port       | 1     | emu10k1_gp | A8AFE9E221 |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1451 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 113   |            | 4A2455EAE6 |
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 96    |            | 76E2078928 |
| 1022:1451 | 1462:7a38 | AMD        | Family 17h (Models 00h-0f... | 6     |            | 4B9FC100D8 |
| 1022:1451 | 1028:07ee | AMD        | Family 17h (Models 00h-0f... | 5     |            | DB32491DFE |
| 1022:1419 | 1019:7c90 | AMD        | Family 15h (Models 10h-1f... | 2     |            | FFB74FCE84 |
| 1022:1423 | 1025:0904 | AMD        | Family 15h (Models 30h-3f... | 2     |            | 3458AC22F5 |
| 1002:5a23 | 1462:7893 | AMD        | RD890S/RD990 I/O Memory M... | 1     |            | 837F3B9280 |
| 1022:1419 | 103c:1850 | AMD        | Family 15h (Models 10h-1f... | 1     |            | C6E0706214 |
| 1022:1419 | 103c:2215 | AMD        | Family 15h (Models 10h-1f... | 1     |            | 1B3213CA06 |
| 1022:1419 | 1462:7793 | AMD        | Family 15h (Models 10h-1f... | 1     |            | C3610DBBF7 |
| 1022:1423 | 1019:99d3 | AMD        | Family 15h (Models 30h-3f... | 1     |            | CFCBE45B0D |
| 1022:1423 | 1019:9a62 | AMD        | Family 15h (Models 30h-3f... | 1     |            | 06FB58E8EE |
| 1022:1423 | 1019:9ac9 | AMD        | Family 15h (Models 30h-3f... | 1     |            | BED1921035 |
| 1022:1423 | 103c:2215 | AMD        | Family 15h (Models 30h-3f... | 1     |            | 7CA812503F |
| 1022:1423 | 1462:7903 | AMD        | Family 15h (Models 30h-3f... | 1     |            | EADCB61E9F |
| 1022:1451 | 1019:9ce5 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 06776696F3 |
| 1022:1451 | 1028:089a | AMD        | Family 17h (Models 00h-0f... | 1     |            | 451A733603 |
| 1022:1451 | 1462:7a40 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 515A7DFA4F |
| 1022:1451 | 1462:7b85 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 29C3842F1D |
| 1022:1451 | 1462:7b86 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 73F23254C0 |
| 1022:1451 | 1462:7b89 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 63314DCB31 |
| 1022:1481 | 1022:1481 | AMD        | Starship/Matisse IOMMU       | 1     |            | 35B960D525 |
| 1022:1577 | 1043:8719 | AMD        | Family 15h (Models 60h-6f... | 1     |            | 13D633A029 |
| 1022:1577 | 17aa:3100 | AMD        | Family 15h (Models 60h-6f... | 1     |            | 5BD277D767 |
| 8086:1f16 | 1849:1f16 | Intel      | Atom processor C2000 RCEC    | 1     |            | E398D38584 |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816c | 1019:81ea | Realtek... | Virtual IPMI                 | 1     |            | 06FB58E8EE |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816c | 1458:e000 | Realtek... | Virtual IPMI                 | 3     | ipmi_si    | E528F92A7A |
| 10ec:816c | 17aa:3089 | Realtek... | Virtual IPMI                 | 3     | ipmi_si    | D9A1939AB2 |
| 103c:3302 | 103c:3305 | Hewlett... | Integrated Lights-Out Sta... | 2     | ipmi_si    | 96AE8D3618 |
| 10ec:816c | 1025:078b | Realtek... | Virtual IPMI                 | 1     |            | 087F924E20 |
| 10ec:816c | 10ec:8168 | Realtek... | Virtual IPMI                 | 1     | ipmi_si    | E505745421 |
| 10ec:816c | 1734:1178 | Realtek... | Virtual IPMI                 | 1     |            | 102A89A278 |
| 10ec:816c | 17aa:30b2 | Realtek... | Virtual IPMI                 | 1     | ipmi_si    | 36635F76F9 |
| 8086:108e | 8086:0000 | Intel      | 82573E KCS (Active Manage... | 1     | ipmi_si    | 1960567A11 |

### Isdn adapter (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1244:0a00 | 1244:0a00 | AVM        | A1 ISDN [Fritz]              | 1     | fcpci      | 9697B3D9F1 |
| 1244:0e00 | 1244:0e00 | AVM        | Fritz!Card PCI v2.0 ISDN     | 1     | fcpci      | AC522E55CE |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a121 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 198   |            | 99614383EB |
| 10de:03f5 | 1849:03eb | Nvidia     | MCP61 Memory Controller      | 194   |            | 816FE60D2D |
| 10de:03e2 | 1849:03e2 | Nvidia     | MCP61 Host Bridge            | 180   |            | 4E526BB85F |
| 10de:03f5 | 1458:0c11 | Nvidia     | MCP61 Memory Controller      | 105   |            | BBF6B6F632 |
| 8086:a121 | 1458:5001 | Intel      | 100 Series/C230 Series Ch... | 103   |            | 0BF4CAF942 |
| 10de:03ea | 1043:8234 | Nvidia     | MCP61 Memory Controller      | 72    |            | 2A30939325 |
| 10de:03f5 | 1043:8234 | Nvidia     | MCP61 Memory Controller      | 72    |            | 2A30939325 |
| 10de:03ea | 10de:cb84 | Nvidia     | MCP61 Memory Controller      | 68    |            | 11D0376265 |
| 10de:03e2 | 1043:83a4 | Nvidia     | MCP61 Host Bridge            | 66    |            | 3248DFD987 |
| 10de:03f5 | 1043:83a4 | Nvidia     | MCP61 Memory Controller      | 66    |            | 3248DFD987 |
| 8086:a2a1 | 1458:5001 | Intel      | 200 Series/Z370 Chipset F... | 63    |            | AAD0551E27 |
| 10de:03ea | 1458:5001 | Nvidia     | MCP61 Memory Controller      | 61    |            | D083D84DB1 |
| 8086:a36f | 8086:7270 | Intel      | Cannon Lake PCH Shared SRAM  | 57    |            | D1EC1DAC8F |
| 8086:a2a1 | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 54    |            | 7F1F084A4F |
| 10de:005e | 1043:815a | Nvidia     | CK804 Memory Controller      | 52    |            | C92DC5D0CF |
| 10de:03e2 | 1458:5001 | Nvidia     | MCP61 Host Bridge            | 44    |            | BBF6B6F632 |
| 10de:03f5 | 1462:7309 | Nvidia     | MCP61 Memory Controller      | 42    |            | 11D0376265 |
| 8086:a121 | 1849:a121 | Intel      | 100 Series/C230 Series Ch... | 37    |            | BCB3EF58AB |
| 10de:03f5 | 1565:3407 | Nvidia     | MCP61 Memory Controller      | 36    |            | E327FDD558 |
| 10de:0444 | 1462:7369 | Nvidia     | MCP65 Memory Controller      | 36    |            | C46668413C |
| 10de:0445 | 1462:7369 | Nvidia     | MCP65 Memory Controller      | 36    |            | C46668413C |
| 10de:0568 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 33    |            | 88719BBDD6 |
| 10de:0751 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 33    |            | 88719BBDD6 |
| 10de:0754 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 33    |            | 88719BBDD6 |
| 10de:0369 | 1043:8239 | Nvidia     | MCP55 Memory Controller      | 32    |            | 4EA0694850 |
| 8086:a36f | 1043:8694 | Intel      | Cannon Lake PCH Shared SRAM  | 32    |            | 68BABB69CB |
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
| 8086:a2a1 | 1043:872f | Intel      | 200 Series/Z370 Chipset F... | 23    |            | 3B3DC1A093 |
| 8086:a2a1 | 1849:a2a1 | Intel      | 200 Series/Z370 Chipset F... | 23    |            | CACD7C9489 |
| 10de:0568 | 1849:0568 | Nvidia     | MCP78S [GeForce 8200] Mem... | 21    |            | AC2555A764 |
| 10de:0751 | 1849:0751 | Nvidia     | MCP78S [GeForce 8200] Mem... | 21    |            | AC2555A764 |
| 10de:0754 | 1849:0754 | Nvidia     | MCP78S [GeForce 8200] Mem... | 21    |            | AC2555A764 |
| 8086:a121 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 21    |            | BD6DC70775 |
| 8086:a36f | 1849:a36f | Intel      | Cannon Lake PCH Shared SRAM  | 20    |            | 39C0FBE126 |
| 10de:0369 | 1462:7250 | Nvidia     | MCP55 Memory Controller      | 18    |            | 005023EE9D |
| 10de:0568 |           | Nvidia     | MCP78S [GeForce 8200] Mem... | 18    |            | 96600BDB45 |
| 10de:0751 | 10de:cb84 | Nvidia     | MCP78S [GeForce 8200] Mem... | 18    |            | 96600BDB45 |
| 10de:0270 | 1043:81c0 | Nvidia     | MCP51 Host Bridge            | 17    |            | 15B9CC8D28 |
| 10de:03ea | 1565:3407 | Nvidia     | MCP61 Memory Controller      | 17    |            | C67AE8B7E3 |
| 10de:0754 | 1458:5001 | Nvidia     | MCP78S [GeForce 8200] Mem... | 16    |            | 9D06F70055 |
| 8086:a121 | 1462:7a15 | Intel      | 100 Series/C230 Series Ch... | 16    |            | 7C7D8F8CB6 |
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
| 10de:02fa | 1043:81c0 | Nvidia     | C51 Memory Controller 0      | 14    |            | 15B9CC8D28 |
| 10de:03ea | 103c:2a6c | Nvidia     | MCP61 Memory Controller      | 14    |            | 579C5E3CDC |
| 10de:03ea | 1849:03ea | Nvidia     | MCP61 Memory Controller      | 14    |            | 816FE60D2D |
| 10de:03f5 | 103c:2a6c | Nvidia     | MCP61 Memory Controller      | 14    |            | 579C5E3CDC |
| 10de:03f5 | 1462:7597 | Nvidia     | MCP61 Memory Controller      | 14    |            | A0A7F774C4 |
| 10de:0270 | 1043:81bc | Nvidia     | MCP51 Host Bridge            | 13    |            | C7934C20A0 |
| 10de:027e | 10de:027e | Nvidia     | C51 Memory Controller 2      | 13    |            | D1F4A0FF97 |
| 10de:027f | 10de:027f | Nvidia     | C51 Memory Controller 3      | 13    |            | D1F4A0FF97 |
| 10de:02f8 | 10de:02f8 | Nvidia     | C51 Memory Controller 5      | 13    |            | D1F4A0FF97 |
| 10de:02f9 | 10de:02f9 | Nvidia     | C51 Memory Controller 4      | 13    |            | D1F4A0FF97 |
| 10de:02fa | 10de:02fa | Nvidia     | C51 Memory Controller 0      | 13    |            | D1F4A0FF97 |
| 10de:02fe | 10de:02fe | Nvidia     | C51 Memory Controller 1      | 13    |            | D1F4A0FF97 |
| 10de:02ff | 10de:02ff | Nvidia     | C51 Host Bridge              | 13    |            | D1F4A0FF97 |
| 10de:005e | 1458:5000 | Nvidia     | CK804 Memory Controller      | 12    |            | 556AE96F13 |
| 10de:0444 | 1458:5001 | Nvidia     | MCP65 Memory Controller      | 12    |            | 003A6FD79D |
| 10de:0445 | 1458:0c11 | Nvidia     | MCP65 Memory Controller      | 12    |            | 003A6FD79D |
| 10de:0270 | 1458:5001 | Nvidia     | MCP51 Host Bridge            | 11    |            | 3C440908D8 |
| 10de:0272 | 1458:0264 | Nvidia     | MCP51 Memory Controller 0    | 11    |            | 3C440908D8 |
| 10de:03ea | 103c:2a99 | Nvidia     | MCP61 Memory Controller      | 11    |            | 4950E6BB13 |
| 10de:03f5 | 103c:2a99 | Nvidia     | MCP61 Memory Controller      | 11    |            | 4950E6BB13 |
| 10de:0547 | 1019:2609 | Nvidia     | MCP67 Memory Controller      | 11    |            | 57FB4562E5 |
| 8086:a2a1 | 1043:873c | Intel      | 200 Series/Z370 Chipset F... | 11    |            | 30502C41DE |
| 10de:0547 | 1043:82b3 | Nvidia     | MCP67 Memory Controller      | 10    |            | 88EB91B4F7 |
| 10de:0568 | 1043:82e2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 10    |            | 94F06CBF32 |
| 10de:0751 | 1043:82e2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 10    |            | 94F06CBF32 |
| 10de:0754 | 1043:82e2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 10    |            | 94F06CBF32 |
| 10de:005e | 1695:1010 | Nvidia     | CK804 Memory Controller      | 9     |            | 83BFA1527C |
| 10de:027e | 1458:5000 | Nvidia     | C51 Memory Controller 2      | 9     |            | 3C440908D8 |
| 10de:027f | 1458:5000 | Nvidia     | C51 Memory Controller 3      | 9     |            | 3C440908D8 |
| 10de:02f8 | 1458:5000 | Nvidia     | C51 Memory Controller 5      | 9     |            | 3C440908D8 |
| 10de:02f9 | 1458:5000 | Nvidia     | C51 Memory Controller 4      | 9     |            | 3C440908D8 |
| 10de:02fe | 1458:5000 | Nvidia     | C51 Memory Controller 1      | 9     |            | 3C440908D8 |
| 10de:02ff | 1458:5000 | Nvidia     | C51 Host Bridge              | 9     |            | 3C440908D8 |

### Modem (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 11c1:044c | 11c1:044c | LSI        | LT WinModem                  | 12    |            | E75F4538BC |
| 1057:3052 | 1057:3020 | Motorola   | SM56 Data Fax Modem          | 7     |            | D3B45DE297 |
| 1106:3068 |           | VIA Tec... | AC'97 Modem Controller       | 7     | snd_via... | E75F4538BC |
| 8086:1040 | 8086:1000 | Intel      | 536EP Data Fax Modem         | 4     |            | 1263C61735 |
| 134d:7892 | 134d:0001 | PCTel      | HSP MicroModem 56            | 3     | serial     | F7D15035EC |
| 1106:3068 | 1019:0c04 | VIA Tec... | AC'97 Modem Controller       | 2     | snd_via... | 1263C61735 |
| 1039:7013 | 104d:8128 | Silicon... | AC'97 Modem Controller       | 1     | snd_int... | 72A578315E |
| 1057:3052 | 1631:3034 | Motorola   | SM56 Data Fax Modem          | 1     |            | B7CEC1644D |
| 1106:3068 | 1019:2122 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 25BB71984B |
| 11c1:0440 | 11c1:0440 | LSI        | 56k WinModem                 | 1     |            | 6B2E5020C2 |
| 11c1:0449 | 1468:0410 | LSI        | L56xM+S [Mars-2] WinModem... | 1     |            | A8A13EFBA0 |
| 11c1:044e | 11c1:044e | LSI        | LT WinModem                  | 1     |            | 6203763CC5 |
| 11c1:044e | 1235:044e | LSI        | LT WinModem                  | 1     |            | 3D74179CB7 |
| 1543:3052 | 1543:3000 | SILICON... | Intel 537 [Winmodem]         | 1     |            | 75C969D54B |
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
| 109e:0878 |           | Brooktree  | Bt878 Audio Capture          | 15    |            | BA9CCBD3A5 |
| 1131:7231 | 5ace:8000 | Philips... | SAA7231                      | 8     |            | FA070462FC |
| 11bd:bede | 11bd:0022 | Pinnacl... | AV/DV Studio Capture Card    | 8     |            | BC68308D9C |
| 109e:0878 | 1461:0003 | Brooktree  | Bt878 Audio Capture          | 7     | snd_bt87x  | EBF0DCD676 |
| 1131:7160 | 1461:1455 | Philips... | SAA7160                      | 7     |            | C785DD2710 |
| 1131:7164 | 0070:8851 | Philips... | SAA7164                      | 5     | saa7164    | 54C8F90B14 |
| 1131:7231 | 1461:1400 | Philips... | SAA7231                      | 5     |            | 4F99536247 |
| 109e:0878 | 0070:13eb | Brooktree  | Bt878 Audio Capture          | 4     | snd_bt87x  | AAECFA3E56 |
| 109e:0878 | 107d:6609 | Brooktree  | Bt878 Audio Capture          | 3     |            | 4A6B13BAEA |
| 1131:7160 | 1461:2655 | Philips... | SAA7160                      | 3     |            | A74B989748 |
| 1131:7162 | 11bd:0100 | Philips... | SAA7162                      | 3     |            | EF8A743A1E |
| 1131:7231 | 1461:7983 | Philips... | SAA7231                      | 3     |            | 6186ACA9BB |
| 14e4:1615 | 105b:0d77 | Broadcom   | BCM70015 Video Decoder [C... | 3     |            | B036D312E6 |
| 14f1:8804 | 0070:9002 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     |            | 8168BA11E3 |
| 1822:4e35 | 153b:1179 | Twinhan... | Mantis DTV PCI Bridge Con... | 3     | mantis     | C6B223FD61 |
| 1822:4e35 | 1822:0031 | Twinhan... | Mantis DTV PCI Bridge Con... | 3     | mantis     | 24636D8ED6 |
| 1022:15e2 | 1022:15e2 | AMD        | Raven/Raven2/FireFlight/R... | 2     |            | 52ED0BAFBD |
| 1022:15e2 | 103c:8433 | AMD        | Raven/Raven2/FireFlight/R... | 2     | snd_pci... | 33A03DF803 |
| 1022:15e2 | 103c:8434 | AMD        | Raven/Raven2/FireFlight/R... | 2     |            | E2E650868B |
| 109e:0878 | 11bd:0012 | Brooktree  | Bt878 Audio Capture          | 2     | snd_bt87x  | AB36F565A4 |
| 1131:7160 | 1461:0855 | Philips... | SAA7160                      | 2     |            | BBDA8BED86 |
| 1131:7160 | 1461:1855 | Philips... | SAA7160                      | 2     |            | FA070462FC |
| 1131:7160 | 1ae4:0700 | Philips... | SAA7160                      | 2     |            | E9FCA3B9C8 |
| 1131:7231 | 12ab:0763 | Philips... | SAA7231                      | 2     |            | 6F6F611F59 |
| 1131:7231 | 16be:0008 | Philips... | SAA7231                      | 2     |            | 1BA5C50EAD |
| 1131:7231 | 5ace:8150 | Philips... | SAA7231                      | 2     |            | 8603D5BDF5 |
| 1131:7231 | 5ace:8201 | Philips... | SAA7231                      | 2     |            | 3D68E82C9F |
| 11bd:bede | 11bd:0023 | Pinnacl... | AV/DV Studio Capture Card    | 2     |            | EBD8A5801D |
| 14e4:1615 | 14e4:1615 | Broadco... | BCM70015 Video Decoder [C... | 2     |            | 6F7935090C |
| 14f1:8804 | 1822:0023 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     |            | AB36F565A4 |
| 1822:4e35 | 153b:1178 | Twinhan... | Mantis DTV PCI Bridge Con... | 2     | mantis     | B7812DD3C1 |
| 1822:4e35 | 1ae4:0002 | Twinhan... | Mantis DTV PCI Bridge Con... | 2     | mantis     | CCB302179F |
| 1822:4e35 | 1ae4:0003 | Twinhan... | Mantis DTV PCI Bridge Con... | 2     | mantis     | DA1E5854E0 |
| 8086:0f38 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 2     |            | F9B255CBBC |
| 0002:8290 | 107d:2609 |            | Multimedia controller        | 1     |            | 95D420F37F |
| 1002:4d51 | 1002:b041 | AMD        | Unified AVStream Driver      | 1     |            | 2CF316774E |
| 1002:ac12 | 12ab:0003 | AMD        | Theater HD T507 (DVB-T) T... | 1     |            | 0921BB94E0 |
| 1002:ad18 | 1682:ad18 | AMD        | Multimedia controller        | 1     |            | 3108FE53D3 |
| 1057:3410 | 1057:ffff | Motorola   | DSP56361 Digital Signal P... | 1     |            | 16A7890585 |
| 1057:3410 | 11af:eed2 | Motorola   | DSP56361 Digital Signal P... | 1     |            | 16A7890585 |
| 1057:3410 | 11af:eee1 | Motorola   | DSP56361 Digital Signal P... | 1     |            | 16A7890585 |
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
| 1131:7160 | 1461:0455 | Philips... | SAA7160                      | 1     |            | F85808C04C |
| 1131:7160 | 1461:0955 | Philips... | SAA7160                      | 1     |            | 388696B306 |
| 1131:7160 | 6281:0001 | Philips... | SAA7160                      | 1     | saa716x... | E9A12FFEAF |
| 1131:7160 | 6928:0001 | Philips... | SAA7160                      | 1     |            | 8C8F8EFAB1 |
| 1131:7160 | 6928:0002 | Philips... | SAA7160                      | 1     |            | 47FD7AB796 |
| 1131:7162 | 11bd:0101 | Philips... | SAA7162                      | 1     |            | 003EB89135 |
| 1131:7164 | 0070:8953 | Philips... | SAA7164                      | 1     | saa7164    | 035CB4B9FD |
| 1131:7164 | 0070:f111 | Philips... | SAA7164                      | 1     | saa7164    | 2AC18DE610 |
| 1131:7164 | 185b:e900 | Philips... | SAA7164                      | 1     | saa7164    | 87483BBE5F |
| 11bd:0040 | 11bd:0045 | Pinnacl... | Royal TS Function 1          | 1     |            | FF0A7B1FC8 |
| 11bd:0041 | 11bd:0045 | Pinnacl... | RoyalTS Function 2           | 1     |            | FF0A7B1FC8 |
| 11bd:0042 | 11bd:0045 | Pinnacl... | Royal TS Function 3          | 1     |            | FF0A7B1FC8 |
| 14e4:1612 | 14e4:2612 | Broadcom   | BCM70012 Video Decoder [C... | 1     |            | 71EDB71D27 |
| 14f1:8803 | 185b:e000 | Conexan... | CX2388x TV Capture Chip      | 1     |            | 5B85C2F248 |
| 14f1:8804 | 0070:1402 | Conexan... | CX23880/1/2/3 PCI Video a... | 1     |            | 186479593C |
| 14f1:8804 | 0070:6902 | Conexan... | CX23880/1/2/3 PCI Video a... | 1     |            | 556AE96F13 |
| 14f1:8804 | 0070:6906 | Conexan... | CX23880/1/2/3 PCI Video a... | 1     |            | B95995E16E |
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
| 8086:22b8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 1A008EB1B2 |
| dd01:0003 | dd01:0030 | Digital... | Octopus DVB Adapter          | 1     | ddbridge   | BA5B7B57D6 |
| dd01:0006 | dd01:0022 | Digital... | Cine V7                      | 1     |            | FCF4AFE5C6 |

### Multiport serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1fd4:1999 | 1fd4:0002 | SUNIX      | Multiport serial controller  | 3     | serial     | A9E837C9EB |
| 135c:0170 | 135c:0170 | Quatech    | QSCLP-100                    | 1     | serial     | 05DF269988 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8168 | 1458:e000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1922  | r8169      | B39AC90CA0 |
| 10ec:8168 | 1043:8505 | Realtek... | RTL8111/8168/8411 PCI Exp... | 696   | r8169      | 570B707FFB |
| 10ec:8168 | 1849:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 675   | r8169      | EF6230C726 |
| 10ec:8168 | 1043:8432 | Realtek... | RTL8111/8168/8411 PCI Exp... | 559   | r8169      | 6A60A724F9 |
| 10ec:8139 | 10ec:8139 | Realtek... | RTL-8100/8101L/8139 PCI F... | 379   | 8139too... | 70E729A005 |
| 10ec:8168 | 1043:8677 | Realtek... | RTL8111/8168/8411 PCI Exp... | 300   | r8169      | 99614383EB |
| 10ec:8168 | 1043:8554 | Realtek... | RTL8111/8168/8411 PCI Exp... | 282   | r8169      | F6CCF2BBA6 |
| 10ec:8168 | 1043:83a3 | Realtek... | RTL8111/8168/8411 PCI Exp... | 245   | r8169      | EB9D0FE3F5 |
| 1969:1048 | 1043:8226 | Qualcom... | Attansic L1 Gigabit Ethernet | 226   | atl1       | 48709E5844 |
| 1106:3106 | 1186:1405 | VIA Tec... | VT6105/VT6106S [Rhine-III]   | 163   | via_rhine  | 080AE7C292 |
| 10ec:8168 | 1043:859e | Realtek... | RTL8111/8168/8411 PCI Exp... | 147   | r8169      | 3A1BF1D002 |
| 1969:1083 | 1458:e000 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 137   | atl1c      | D3FFE4FDA2 |
| 10ec:8136 | 1849:8136 | Realtek... | RTL810xE PCI Express Fast... | 133   | r8169      | 42C519E784 |
| 8086:15b8 | 1043:8672 | Intel      | Ethernet Connection (2) I... | 121   | e1000e     | 89F4BB64D7 |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 115   | r8169      | 44204F310C |
| 10ec:8168 | 1043:82c6 | Realtek... | RTL8111/8168/8411 PCI Exp... | 112   | r8169      | 42CC2F59E6 |
| 11ab:4364 | 1043:81f8 | Marvell... | 88E8056 PCI-E Gigabit Eth... | 111   | sky2       | B481805845 |
| 10ec:8169 | 10ec:8169 | Realtek... | RTL8169 PCI Gigabit Ether... | 88    | r8169      | D569843A2D |
| 10ec:8168 | 1043:81aa | Realtek... | RTL8111/8168/8411 PCI Exp... | 84    | r8169      | EB0CDD472F |
| 1969:1026 | 1043:8304 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 84    | atl1e      | 6C7C70F0E2 |
| 1969:1091 | 1458:e000 | Qualcom... | AR8161 Gigabit Ethernet      | 84    | alx        | 8C4047657D |
| 8086:15a1 | 1043:85c4 | Intel      | Ethernet Connection (2) I... | 80    | e1000e     | A8F2B39356 |
| 10ec:8168 | 7470:3468 | Realtek... | RTL8111/8168/8411 PCI Exp... | 77    | r8169      | AEC91031D4 |
| 10ec:8136 | 1043:8347 | Realtek... | RTL810xE PCI Express Fast... | 75    | r8169      | 85261DC7A2 |
| 10ec:8168 | 1462:7817 | Realtek... | RTL8111/8168/8411 PCI Exp... | 72    | r8169      | 7BBCD6F17D |
| 11ab:4320 | 1043:811a | Marvell... | 88E8001 Gigabit Ethernet ... | 72    | skge       | B26ED41AB8 |
| 1969:2048 | 1043:8233 | Qualcom... | Attansic L2 Fast Ethernet    | 65    | atl2       | 7D6812488D |
| 8086:15b8 | 1458:e000 | Intel      | Ethernet Connection (2) I... | 65    | e1000e     | AAD0551E27 |
| 10ec:8168 | 1043:8367 | Realtek... | RTL8111/8168/8411 PCI Exp... | 55    | r8169      | 699B1F26E0 |
| 10ec:8168 | 1462:7721 | Realtek... | RTL8111/8168/8411 PCI Exp... | 51    | r8169      | B801DD3F7D |
| 10ec:8168 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 48    | r8169      | 7A74EB0F6F |
| 1969:1026 | 1043:8226 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 48    | atl1e      | 28DFB478B7 |
| 1969:2062 | 1849:2062 | Qualcom... | AR8152 v2.0 Fast Ethernet    | 48    | atl1c      | 5F6E1A3B61 |
| 8086:153b | 1458:e000 | Intel      | Ethernet Connection I217-V   | 47    | e1000e     | 7875ECD5A5 |
| 10ec:8167 | 1458:e000 | Realtek... | RTL-8110SC/8169SC Gigabit... | 46    | r8169      | 9CD2D7F72B |
| 10ec:8168 | 1025:8000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 46    | r8169      | 99825EFDBE |
| 1969:1063 | 1043:83fe | Qualcom... | AR8131 Gigabit Ethernet      | 46    | atl1c      | E267629A35 |
| 1969:1063 | 1458:e000 | Qualcom... | AR8131 Gigabit Ethernet      | 46    | atl1c      | E73646B8DF |
| 10ec:8168 | 1043:8385 | Realtek... | RTL8111/8168/8411 PCI Exp... | 45    | r8169      | EE184BFE51 |
| 1186:4300 | 1186:4300 | D-Link ... | DGE-528T Gigabit Ethernet... | 45    | r8169      | 66A5EA0BE5 |
| 1969:10a1 | 1043:8587 | Qualcom... | QCA8171 Gigabit Ethernet     | 45    | alx        | BF6F67F7A5 |
| 8086:15b8 | 1849:15b8 | Intel      | Ethernet Connection (2) I... | 45    | e1000e     | CACD7C9489 |
| 11ab:4362 | 1043:8142 | Marvell... | 88E8053 PCI-E Gigabit Eth... | 42    | sky2       | 2BF9512AD1 |
| 13f0:0200 | 13f0:0201 | Sundanc... | IC Plus IP100A Integrated... | 41    | sundance   | 6ED85C31F2 |
| 10ec:8168 | 1462:7693 | Realtek... | RTL8111/8168/8411 PCI Exp... | 39    | r8169      | FEAA959521 |
| 1969:1083 | 1849:1083 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 39    | atl1c      | 27E239601B |
| 10ec:8136 | 10ec:0123 | Realtek... | RTL810xE PCI Express Fast... | 38    | r8169      | 9137FB3859 |
| 8086:153b | 1043:859f | Intel      | Ethernet Connection I217-V   | 37    | e1000e     | B61D174C21 |
| 10ec:8168 | 1019:811e | Realtek... | RTL8111/8168/8411 PCI Exp... | 36    | r8169      | 78E822AD79 |
| 1969:1026 | 1043:831c | Qualcom... | AR8121/AR8113/AR8114 Giga... | 36    | atl1e      | 5C690583ED |
| 10ec:8139 | 11f6:8139 | Realtek... | RTL-8100/8101L/8139 PCI F... | 35    | 8139too... | 96FBD72727 |
| 10ec:8168 | 1462:369c | Realtek... | RTL8111/8168/8411 PCI Exp... | 35    | r8169      | C46668413C |
| 1969:1091 | 1043:8507 | Qualcom... | AR8161 Gigabit Ethernet      | 33    | alx        | 9F6FB489EC |
| 10ec:8168 | 1462:7758 | Realtek... | RTL8111/8168/8411 PCI Exp... | 32    | r8169      | 0A593D376A |
| 14e4:16b1 | 1849:96b1 | Broadco... | NetLink BCM57781 Gigabit ... | 32    | tg3        | F88D5A4221 |
| 1969:e091 | 1458:e000 | Qualcom... | Killer E220x Gigabit Ethe... | 32    | alx        | 7552A8CB4C |
| 1969:10a1 | 1849:10a1 | Qualcom... | QCA8171 Gigabit Ethernet     | 30    | alx        | 33CFE3D019 |
| 10ec:8167 | 1043:820d | Realtek... | RTL-8110SC/8169SC Gigabit... | 29    | r8169      | 29B7777E42 |
| 1969:1073 | 1458:e000 | Qualcom... | AR8151 v1.0 Gigabit Ethernet | 29    | atl1c      | A63447351B |
| 1969:1083 | 1043:847e | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 29    | atl1c      | F39C397507 |
| 10de:0760 | 1043:82f2 | Nvidia     | MCP77 Ethernet               | 28    | forcedeth  | 2CAE195313 |
| 10ec:8139 | 1849:8139 | Realtek... | RTL-8100/8101L/8139 PCI F... | 27    | 8139too... | 0B6FD94458 |
| 10ec:8168 | 1462:7788 | Realtek... | RTL8111/8168/8411 PCI Exp... | 25    | r8169      | 7AF20CDF5A |
| 10ec:8136 | 1019:8348 | Realtek... | RTL810xE PCI Express Fast... | 24    | r8169      | E706D81D0A |
| 10ec:8136 | 1043:83d3 | Realtek... | RTL810xE PCI Express Fast... | 24    | r8169      | 1A62B680D7 |
| 8086:153b | 1849:153b | Intel      | Ethernet Connection I217-V   | 24    | e1000e     | 9736CAAF2E |
| 10ec:8136 | 1458:e000 | Realtek... | RTL810xE PCI Express Fast... | 22    | r8169      | F6B9026258 |
| 14e4:167a | 1028:01da | Broadco... | NetXtreme BCM5754 Gigabit... | 22    | tg3        | 5D6E2E4B43 |
| 8086:107c | 8086:1376 | Intel      | 82541PI Gigabit Ethernet ... | 22    | e1000      | C44B707FC4 |
| 10de:0760 | 1849:0760 | Nvidia     | MCP77 Ethernet               | 21    | forcedeth  | AC2555A764 |
| 10ec:8136 | 1043:8136 | Realtek... | RTL810xE PCI Express Fast... | 21    | r8169      | 6154EA6AE1 |
| 10ec:8168 | 1462:7529 | Realtek... | RTL8111/8168/8411 PCI Exp... | 21    | r8169      | B4A6A81552 |
| 10ec:8168 | 1462:7599 | Realtek... | RTL8111/8168/8411 PCI Exp... | 21    | r8169      | 132397AB90 |
| 11ab:4320 | 1458:e000 | Marvell... | 88E8001 Gigabit Ethernet ... | 21    | skge       | 1012BD5A43 |
| 10ec:8136 | 1565:2308 | Realtek... | RTL810xE PCI Express Fast... | 20    | r8169      | 6BEA5C9500 |
| 10ec:8139 | 1043:8109 | Realtek... | RTL-8100/8101L/8139 PCI F... | 20    | 8139too... | 3549E0C30D |
| 10ec:8168 | 1462:7850 | Realtek... | RTL8111/8168/8411 PCI Exp... | 20    | r8169      | 0F3DCCFE4E |
| 10ec:8168 | 1462:7996 | Realtek... | RTL8111/8168/8411 PCI Exp... | 20    | r8169      | BD6DC70775 |
| 8086:109a | 1043:81c2 | Intel      | 82573L Gigabit Ethernet C... | 20    | e1000e     | 0738B91B0B |
| 8086:15a1 | 1849:15a1 | Intel      | Ethernet Connection (2) I... | 20    | e1000e     | CC9738C393 |
| 10ec:8168 | 1462:7641 | Realtek... | RTL8111/8168/8411 PCI Exp... | 19    | r8169      | 77F07D2D69 |
| 1969:2048 | 1019:2048 | Qualcom... | Attansic L2 Fast Ethernet    | 19    | atl2       | D3B45DE297 |
| 10ec:8168 | 8086:d608 | Realtek... | RTL8111/8168/8411 PCI Exp... | 18    | r8169      | 08DCF9AA49 |
| 14e4:1677 | 1028:01ad | Broadco... | NetXtreme BCM5751 Gigabit... | 18    | tg3        | 018144B94B |
| 10ec:8136 | 1462:7592 | Realtek... | RTL810xE PCI Express Fast... | 17    | r8169      | B0B570F44B |
| 10ec:8168 | 103c:2abf | Realtek... | RTL8111/8168/8411 PCI Exp... | 17    | r8169      | 6567AEB3C4 |
| 10ec:8168 | 1462:7a15 | Realtek... | RTL8111/8168/8411 PCI Exp... | 17    | r8169      | 7C7D8F8CB6 |
| 10ec:8139 | 1019:8139 | Realtek... | RTL-8100/8101L/8139 PCI F... | 16    | 8139too... | F8AE92B32F |
| 10ec:8168 | 1565:230e | Realtek... | RTL8111/8168/8411 PCI Exp... | 16    | r8169      | 7066B7C86B |
| 1969:2062 | 1019:8152 | Qualcom... | AR8152 v2.0 Fast Ethernet    | 16    | atl1c      | 6D38C064DD |
| 10ec:8136 | 1462:7788 | Realtek... | RTL810xE PCI Express Fast... | 15    | r8169      | 805BEF206C |
| 10ec:8168 | 103c:2a9c | Realtek... | RTL8111/8168/8411 PCI Exp... | 15    | r8169      | A585EAEF35 |
| 14e4:1681 | 1028:0293 | Broadco... | NetXtreme BCM5761 Gigabit... | 15    | tg3        | A72C60B73B |
| 1969:1063 | 1462:7592 | Qualcom... | AR8131 Gigabit Ethernet      | 15    | atl1c      | 171A79CEFA |
| 8086:15bc | 1458:e000 | Intel      | Ethernet Connection (7) I... | 15    | e1000e     | B1E690FC69 |
| 10ec:8136 | 1019:8136 | Realtek... | RTL810xE PCI Express Fast... | 14    | r8169      | 5302586F9D |
| 10ec:8139 | 1186:1104 | Realtek... | RTL-8100/8101L/8139 PCI F... | 14    | 8139too... | D969A32092 |
| 10ec:8168 | 103c:2a6f | Realtek... | RTL8111/8168/8411 PCI Exp... | 14    | r8169      | AA83F14B99 |
| 10ec:8168 | 1462:7808 | Realtek... | RTL8111/8168/8411 PCI Exp... | 14    | r8169      | 4120DB4E70 |
| 10ec:8168 | 1462:7816 | Realtek... | RTL8111/8168/8411 PCI Exp... | 14    | r8169      | 08BF7B0C07 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 168c:0032 | 168c:3118 | Qualcom... | AR9485 Wireless Network A... | 83    | ath9k      | CDCE9B48F0 |
| 168c:002d | 168c:0301 | Qualcom... | AR9227 Wireless Network A... | 58    | ath9k      | BDB727808F |
| 168c:002e | 168c:30a4 | Qualcom... | AR9287 Wireless Network A... | 55    | ath9k      | 8B7204FCBA |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 55    | iwlwifi    | 240876777B |
| 168c:002d | 168c:0300 | Qualcom... | AR9227 Wireless Network A... | 46    | ath9k      | 8C518D5D23 |
| 1814:3060 | 1186:3c04 | Ralink     | RT3060 Wireless 802.11n 1... | 43    | rt2800pci  | F79EDA31F9 |
| 168c:0030 | 168c:3112 | Qualcom... | AR93xx Wireless Network A... | 32    | ath9k      | 7F1BE20709 |
| 1814:5360 | 1186:3c05 | Ralink     | RT5360 Wireless 802.11n 1... | 32    | rt2800pci  | 80E0CB37AD |
| 1814:0302 | 1186:3a71 | Ralink     | RT2561/RT61 rev B 802.11g    | 30    | rt61pci    | BCDE3B8E90 |
| 10ec:8176 | 1043:84b5 | Realtek... | RTL8188CE 802.11b/g/n WiF... | 29    | rtl8192ce  | 596AFEF750 |
| 10ec:8185 | 10ec:8225 | Realtek... | RTL-8185 IEEE 802.11a/b/g... | 29    | rtl818x... | A63447351B |
| 168c:0013 | 1186:3a13 | Qualcom... | AR5212/5213/2414 Wireless... | 25    | ath5k      | D6D2A25AA4 |
| 168c:002b | 168c:30a1 | Qualcom... | AR9285 Wireless Network A... | 23    | ath9k      | FBDB9043B4 |
| 168c:0032 | 1043:850d | Qualcom... | AR9485 Wireless Network A... | 23    | ath9k      | F6D05FF577 |
| 1814:0302 | 1186:3c09 | Ralink     | RT2561/RT61 rev B 802.11g    | 21    | rt61pci    | AC2555A764 |
| 14e4:4359 | 1043:850c | Broadco... | BCM43228 802.11a/b/g/n       | 20    | wl         | 571C27C038 |
| 1814:5390 | 1814:f051 | Ralink     | RT5390 Wireless 802.11n 1... | 20    | rt2800pci  | 39EA514961 |
| 8086:08b1 | 8086:4070 | Intel      | Wireless 7260                | 18    | iwlwifi    | BF930C8C33 |
| 14e4:4318 | 1043:100f | Broadco... | BCM4318 [AirForce One 54g... | 17    | ssb        | 3CB2CDDB91 |
| 14e4:43b1 | 1043:855c | Broadco... | BCM4352 802.11ac Wireless... | 16    | wl         | EEE7D322DF |
| 1814:5390 | 1186:3c07 | Ralink     | RT5390 Wireless 802.11n 1... | 16    | rt2800pci  | 84B606DA8F |
| 8086:08b3 | 8086:8070 | Intel      | Wireless 3160                | 16    | iwlwifi    | CACD7C9489 |
| 168c:0034 | 11ad:6621 | Qualcom... | AR9462 Wireless Network A... | 15    | ath9k      | 7750967159 |
| 10ec:8176 | 10ec:8176 | Realtek... | RTL8188CE 802.11b/g/n WiF... | 14    | rtl8192ce  | 23C449B086 |
| 168c:001d | 168c:2055 | Qualcom... | AR2417 Wireless Network A... | 14    | ath5k      | 4B83E684CA |
| 168c:002b | 1a3b:1089 | Qualcom... | AR9285 Wireless Network A... | 14    | ath9k      | 9B1B3A3479 |
| 8086:0887 | 8086:4062 | Intel      | Centrino Wireless-N 2230     | 14    | iwlwifi    | 606AACED27 |
| 8086:24f3 | 8086:0010 | Intel      | Wireless 8260                | 14    | iwlwifi    | 19AB08EB6F |
| 14e4:43a0 | 1043:8659 | Broadco... | BCM4360 802.11ac Wireless... | 13    | wl         | 7F1BE20709 |
| 14e4:43a0 | 14e4:0619 | Broadco... | BCM4360 802.11ac Wireless... | 13    | wl         | 537D11B224 |
| 1814:0301 | 1043:837e | Ralink     | RT2561/RT61 802.11g PCI      | 13    | rt61pci    | 4A1BDB3C5B |
| 10ec:8178 | 1043:84b6 | Realtek... | RTL8192CE PCIe Wireless N... | 12    | rtl8192ce  | 4BD42BC14C |
| 10ec:8821 | 1a3b:2161 | Realtek... | RTL8821AE 802.11ac PCIe W... | 12    | rtl8821ae  | 50919B2DDB |
| 1814:3090 | 11ad:6632 | Ralink     | RT3090 Wireless 802.11n 1... | 12    | rt2800pci  | 22CB9D3AF2 |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 12    | iwlwifi    | 06776696F3 |
| 10ec:818b | 10ec:8196 | Realtek... | RTL8192EE PCIe Wireless N... | 11    | rtl8192ee  | 3D5D3F552C |
| 168c:0013 | 1186:3a73 | Qualcom... | AR5212/5213/2414 Wireless... | 11    | ath5k      | FAC5E9FEFA |
| 168c:001a | 1186:3a16 | Qualcom... | AR2413/AR2414 Wireless Ne... | 11    | ath5k      | 33687A527A |
| 1814:3060 | 1043:84e2 | Ralink     | RT3060 Wireless 802.11n 1... | 11    | rt2800pci  | 5FE1529C55 |
| 1814:3062 | 1814:3062 | Ralink     | RT3062 Wireless 802.11n 2... | 11    | rt2800pci  | F9823E634A |
| 8086:2526 | 8086:0014 | Intel      | Wireless-AC 9260             | 11    | iwlwifi    | B88A1B7070 |
| 10ec:8176 | 10ec:8175 | Realtek... | RTL8188CE 802.11b/g/n WiF... | 10    | rtl8192ce  | CD64391DDA |
| 168c:0032 | 1028:0208 | Qualcom... | AR9485 Wireless Network A... | 10    | ath9k      | 6DAC78DB97 |
| 168c:0036 | 1028:020c | Qualcom... | QCA9565 / AR9565 Wireless... | 10    | ath9k      | 65A9CF6ADE |
| 1814:0301 | 1814:2561 | Ralink     | RT2561/RT61 802.11g PCI      | 10    | rt61pci    | 8C518D5D23 |
| 1814:3060 | 1814:3060 | Ralink     | RT3060 Wireless 802.11n 1... | 10    | rt2800pci  | 931EFEC797 |
| 10ec:8179 | 10ec:8197 | Realtek... | RTL8188EE Wireless Networ... | 9     | rtl8188ee  | 7C7D8F8CB6 |
| 10ec:b723 | 103c:81c1 | Realtek... | RTL8723BE PCIe Wireless N... | 9     | rtl8723be  | 200C878097 |
| 10ec:b822 | 1043:8746 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 9     | r8822be    | 8560134FAB |
| 168c:0032 | 1028:0209 | Qualcom... | AR9485 Wireless Network A... | 9     | ath9k      | 84E10F6B4C |
| 168c:003e | 1043:86cd | Qualcom... | QCA6174 802.11ac Wireless... | 9     | ath10k_pci | B0D2314507 |
| 1814:0781 | 11ad:7600 | Ralink     | RT2790 Wireless 802.11n 1... | 9     | rt2800pci  | 878673A8E4 |
| 1814:3090 | 11ad:7601 | Ralink     | RT3090 Wireless 802.11n 1... | 9     | rt2800pci  | 85ECA8E08E |
| 1814:539b | 103c:18ed | Ralink     | RT5390R 802.11bgn PCIe Wi... | 9     | rt2800pci  | 8AE9A7407B |
| 8086:24f3 | 8086:1010 | Intel      | Wireless 8260                | 9     | iwlwifi    | 1B55239D68 |
| 10ec:8179 | 17aa:0179 | Realtek... | RTL8188EE Wireless Networ... | 8     | rtl8188ee  | 92A61C8B37 |
| 10ec:8185 | 10ec:8185 | Realtek... | RTL-8185 IEEE 802.11a/b/g... | 8     | rtl8180    | EC6B93D879 |
| 168c:001c | 105b:e008 | Qualcom... | AR242x / AR542x Wireless ... | 8     | ath5k      | 22A3849E3A |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 8     | iwlwifi    | F630716406 |
| 14e4:4357 | 14e4:04db | Broadco... | BCM43225 802.11b/g/n         | 7     | wl         | C73B25ED21 |
| 168c:001c | 1a3b:1034 | Qualcom... | AR242x / AR542x Wireless ... | 7     | ath5k      | 1ABA3CB35F |
| 168c:002b | 1a3b:2c37 | Qualcom... | AR9285 Wireless Network A... | 7     | ath9k      | 7C249D6E27 |
| 168c:0034 | 1043:850e | Qualcom... | AR9462 Wireless Network A... | 7     | ath9k      | BA46A03C82 |
| 168c:0036 | 1028:020e | Qualcom... | QCA9565 / AR9565 Wireless... | 7     | ath9k      | 3548830389 |
| 1814:0781 | 1814:2790 | Ralink     | RT2790 Wireless 802.11n 1... | 7     | rt2800pci  | DB721D3478 |
| 8086:08b3 | 8086:0070 | Intel      | Wireless 3160                | 7     | iwlwifi    | 462D521F3E |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 7     | iwlwifi    | E3FD7D5295 |
| 8086:a370 | 8086:0034 | Intel      | Wireless-AC 9560 [Jeffers... | 7     | iwlwifi    | 328F236B37 |
| 14e4:43b1 | 1a3b:2123 | Broadco... | BCM4352 802.11ac Wireless... | 6     | wl         | 7A0FC72547 |
| 168c:0013 | 168c:2051 | Qualcom... | AR5212/5213/2414 Wireless... | 6     | ath5k      | 7D6812488D |
| 168c:0023 | 168c:3071 | Qualcom... | AR5416 Wireless Network A... | 6     | ath9k      | A9E1FDFB3E |
| 168c:0029 | 168c:2091 | Qualcom... | AR922X Wireless Network A... | 6     | ath9k      | D5F4BDB1B5 |
| 168c:0032 | 1a3b:1186 | Qualcom... | AR9485 Wireless Network A... | 6     | ath9k      | C13D443BF5 |
| 168c:003e | 1028:0310 | Qualcom... | QCA6174 802.11ac Wireless... | 6     | ath10k_pci | DB32491DFE |
| 1814:5592 | 1043:851a | Ralink     | RT5592 PCIe Wireless Netw... | 6     |            | 08D84A1FF9 |
| 10ec:8190 | 10ec:8190 | Realtek... | RTL8190 802.11n PCI Wirel... | 5     | wl         | 3462CD0CCD |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 5     |            | 33A03DF803 |
| 14e4:43a0 | 1043:85df | Broadco... | BCM4360 802.11ac Wireless... | 5     | bcma       | 6D9668A464 |
| 168c:001a | 168c:2052 | Qualcom... | AR2413/AR2414 Wireless Ne... | 5     | ath5k      | 2D9D561137 |
| 168c:001b | 11ad:5001 | Qualcom... | AR5413/AR5414 Wireless Ne... | 5     | ath5k      | 719994A01B |
| 168c:0032 | 103c:1838 | Qualcom... | AR9485 Wireless Network A... | 5     | ath9k      | E49892B06D |
| 168c:0032 | 1a3b:1f86 | Qualcom... | AR9485 Wireless Network A... | 5     | ath9k      | A695A9C422 |
| 1814:0601 | 1814:2860 | Ralink     | RT2800 802.11n PCI           | 5     | rt2800pci  | EA8698BD14 |
| 1814:3090 | 1814:3090 | Ralink     | RT3090 Wireless 802.11n 1... | 5     | rt2800pci  | 3FA1F2131B |
| 1814:5392 | 1186:3c06 | Ralink     | RT5392 PCIe Wireless Netw... | 5     | rt2800pci  | 6F852B2FDB |
| 8086:0888 | 8086:4262 | Intel      | Centrino Wireless-N 2230     | 5     | iwlwifi    | 46E1A9FC55 |
| 8086:3165 | 8086:4410 | Intel      | Wireless 3165                | 5     | iwlwifi    | 4CC72409B5 |
| 8086:a370 | 8086:02a4 | Intel      | Wireless-AC 9560 [Jeffers... | 5     | iwlwifi    | AE6F83F149 |
| 10ec:8178 | 1043:85e3 | Realtek... | RTL8192CE PCIe Wireless N... | 4     | rtl8192ce  | E1610DFA98 |
| 10ec:8179 | 1a3b:1d38 | Realtek... | RTL8188EE Wireless Networ... | 4     | rtl8188ee  | 17CAB2AF03 |
| 10ec:8185 | 187e:8225 | Realtek... | RTL-8185 IEEE 802.11a/b/g... | 4     | rtl818x... | 71C6E9D18E |
| 10ec:8812 | 1043:86dd | Realtek... | RTL8812AE 802.11ac PCIe W... | 4     | rtl8821ae  | 54DA3F78E7 |
| 11ab:1faa | 1385:6b00 | Marvell... | 88w8335 [Libertas] 802.11... | 4     |            | C9EEDBA4ED |
| 14e4:4328 | 1028:000a | Broadco... | BCM4321 802.11a/b/g/n        | 4     | wl         | F1E9A76397 |
| 14e4:4353 | 1028:000e | Broadco... | BCM43224 802.11a/b/g/n       | 4     | wl         | AE29C83D96 |
| 14e4:43b1 | 1043:85ba | Broadco... | BCM4352 802.11ac Wireless... | 4     | wl         | AD38954E38 |
| 168c:001a | 168c:1052 | Qualcom... | AR2413/AR2414 Wireless Ne... | 4     | ath5k      | 0738B91B0B |
| 168c:002b | 105b:e025 | Qualcom... | AR9285 Wireless Network A... | 4     | ath9k      | 86B54A46B1 |
| 168c:0030 | 168c:3116 | Qualcom... | AR93xx Wireless Network A... | 4     | ath9k      | 6F98DD0410 |
| 168c:0037 | 1a3b:2100 | Qualcom... | AR9485 Wireless Network A... | 4     | ath9k      | B8ECD9CD1E |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:03ef | 1849:03ef | Nvidia     | MCP61 Ethernet               | 180   | forcedeth  | 816FE60D2D |
| 8086:1503 | 1043:849c | Intel      | 82579V Gigabit Network Co... | 138   | e1000e     | AC377EFFFB |
| 8086:1539 | 1043:85f0 | Intel      | I211 Gigabit Network Conn... | 101   | igb        | 4A2455EAE6 |
| 10de:03ef | 1458:e000 | Nvidia     | MCP61 Ethernet               | 94    | forcedeth  | BBF6B6F632 |
| 10de:03ef | 1043:8234 | Nvidia     | MCP61 Ethernet               | 67    | forcedeth  | 2A30939325 |
| 10de:03ef | 1043:83a4 | Nvidia     | MCP61 Ethernet               | 65    | forcedeth  | 3248DFD987 |
| 8086:1539 | 1849:1539 | Intel      | I211 Gigabit Network Conn... | 56    | igb        | 54A49FCBF7 |
| 10de:03ef | 1462:7309 | Nvidia     | MCP61 Ethernet               | 36    | forcedeth  | 11D0376265 |
| 10de:0057 | 1043:812a | Nvidia     | CK804 Ethernet Controller    | 35    | forcedeth  | C92DC5D0CF |
| 8086:1539 | 1458:e000 | Intel      | I211 Gigabit Network Conn... | 34    | igb        | 2B34A6E94A |
| 8086:10de | 1028:0276 | Intel      | 82567LM-3 Gigabit Network... | 33    | e1000e     | 88DB43EE6F |
| 10de:0373 | 1043:8239 | Nvidia     | MCP55 Ethernet               | 29    | forcedeth  | 4EA0694850 |
| 8086:1502 | 1028:052c | Intel      | 82579LM Gigabit Network C... | 27    | e1000e     | 87DAB1466B |
| 8086:10d3 | 8086:a01f | Intel      | 82574L Gigabit Network Co... | 26    | e1000e     | 01E8F93721 |
| 8086:1502 | 1028:047e | Intel      | 82579LM Gigabit Network C... | 26    | e1000e     | 5C380FEC25 |
| 8086:1503 | 1458:e000 | Intel      | 82579V Gigabit Network Co... | 23    | e1000e     | DD20758A89 |
| 8086:10bd | 1028:0211 | Intel      | 82566DM-2 Gigabit Network... | 19    | e1000e     | 8C1C529BDC |
| 8086:10de | 1028:027f | Intel      | 82567LM-3 Gigabit Network... | 19    | e1000e     | DFA7361038 |
| 8086:10de | 103c:3048 | Intel      | 82567LM-3 Gigabit Network... | 19    | e1000e     | B511052CC4 |
| 10de:0373 | 1462:7250 | Nvidia     | MCP55 Ethernet               | 18    | forcedeth  | 005023EE9D |
| 10de:03ef | 1565:2505 | Nvidia     | MCP61 Ethernet               | 18    | forcedeth  | E327FDD558 |
| 8086:294c | 8086:0001 | Intel      | 82566DC-2 Gigabit Network... | 18    | e1000e     | 969A371A99 |
| 8086:10bd | 103c:2818 | Intel      | 82566DM-2 Gigabit Network... | 17    | e1000e     | 073E07ECC0 |
| 10b7:9200 | 10b7:1000 | 3Com       | 3c905C-TX/TX-M [Tornado]     | 16    | 3c59x      | E56205BFC8 |
| 10de:0057 | 1043:8141 | Nvidia     | CK804 Ethernet Controller    | 16    | forcedeth  | 38155B66BB |
| 1106:3065 | 1043:80ed | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 16    | via_rhine  | D9174E33E4 |
| 8086:104b | 8086:0001 | Intel      | 82566DC Gigabit Network C... | 16    | e1000e     | 9E17250CD3 |
| 8086:10bd | 103c:281e | Intel      | 82566DM-2 Gigabit Network... | 16    | e1000e     | D7AB000EA5 |
| 10de:0269 | 1043:816a | Nvidia     | MCP51 Ethernet Controller    | 15    | forcedeth  | 15B9CC8D28 |
| 10de:0373 | 1458:e000 | Nvidia     | MCP55 Ethernet               | 15    | forcedeth  | 0CCA59B833 |
| 1106:3065 | 1849:3065 | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 15    | via_rhine  | 83CCCBAF1A |
| 8086:104a | 103c:2800 | Intel      | 82566DM Gigabit Network C... | 15    | e1000e     | C6129C8C14 |
| 8086:10d3 | 15d9:10d3 | Intel      | 82574L Gigabit Network Co... | 15    | e1000e     | CFC42EAC60 |
| 8086:150c | 1043:8457 | Intel      | 82583V Gigabit Network Co... | 15    | e1000e     | 927A46266A |
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 15    | iwlwifi    | 0438613602 |
| 8086:1502 | 103c:339a | Intel      | 82579LM Gigabit Network C... | 14    | e1000e     | 76F6D2AF22 |
| 10de:0373 | 1043:cb84 | Nvidia     | MCP55 Ethernet               | 13    | forcedeth  | BC336B5882 |
| 10de:03ef | 103c:2a6c | Nvidia     | MCP61 Ethernet               | 13    | forcedeth  | 579C5E3CDC |
| 10de:0057 | 1458:e000 | Nvidia     | CK804 Ethernet Controller    | 12    | forcedeth  | 556AE96F13 |
| 10de:03ef | 1565:3407 | Nvidia     | MCP61 Ethernet               | 12    | forcedeth  | 2D17F5BB22 |
| 8086:1502 | 103c:1589 | Intel      | 82579LM Gigabit Network C... | 12    | e1000e     | E14EB74EA5 |
| 8086:1539 | 8086:0000 | Intel      | I211 Gigabit Network Conn... | 12    | igb        | 55981AF24A |
| 10de:0269 | 1458:e000 | Nvidia     | MCP51 Ethernet Controller    | 11    | forcedeth  | 3C440908D8 |
| 10de:03ef | 103c:2a99 | Nvidia     | MCP61 Ethernet               | 11    | forcedeth  | 4950E6BB13 |
| 8086:10c0 | 1028:020d | Intel      | 82562V-2 10/100 Network C... | 11    | e1000e     | C80A50B2B4 |
| 8086:10f0 | 1025:8000 | Intel      | 82578DC Gigabit Network C... | 11    | e1000e     | A4DA822D7B |
| 8086:1502 | 103c:3397 | Intel      | 82579LM Gigabit Network C... | 11    | e1000e     | 195649904F |
| 8086:10de | 103c:3034 | Intel      | 82567LM-3 Gigabit Network... | 10    | e1000e     | 5DC57BDE0C |
| 8086:10f0 | 8086:0036 | Intel      | 82578DC Gigabit Network C... | 10    | e1000e     | F2560038AF |
| 8086:1502 | 103c:1497 | Intel      | 82579LM Gigabit Network C... | 10    | e1000e     | 6227F00E30 |
| 8086:1533 | 1043:8557 | Intel      | I210 Gigabit Network Conn... | 10    | igb        | 510AE49DF2 |
| 10b7:9055 | 10b7:9055 | 3Com       | 3c905B 100BaseTX [Cyclone]   | 9     | 3c59x      | 0200BA924B |
| 10de:03ef | 1019:2242 | Nvidia     | MCP61 Ethernet               | 9     | forcedeth  | A51A8C96DF |
| 1106:3065 | 1019:0102 | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 9     | via_rhine  | 9B79E448AF |
| 8086:10bd | 1043:8268 | Intel      | 82566DM-2 Gigabit Network... | 9     | e1000e     | 9057FD4986 |
| 8086:10ce | 1043:82d5 | Intel      | 82567V-2 Gigabit Network ... | 9     | e1000e     | C9CCBD7C3F |
| 8086:1503 | 8086:0000 | Intel      | 82579V Gigabit Network Co... | 9     | e1000e     | 2F37CFF8B0 |
| 10de:0373 | 1462:7260 | Nvidia     | MCP55 Ethernet               | 8     | forcedeth  | F87C76BA83 |
| 10de:03ef | 1025:8000 | Nvidia     | MCP61 Ethernet               | 8     | forcedeth  | 80200A8169 |
| 8086:10bd | 8086:0001 | Intel      | 82566DM-2 Gigabit Network... | 8     | e1000e     | 7F57AD053D |
| 8086:10de | 103c:3646 | Intel      | 82567LM-3 Gigabit Network... | 8     | e1000e     | 878673A8E4 |
| 8086:10de | 17aa:3048 | Intel      | 82567LM-3 Gigabit Network... | 8     | e1000e     | D44E51F592 |
| 8086:10df | 1734:114d | Intel      | 82567LF-3 Gigabit Network... | 8     | e1000e     | CDAEC9B4A5 |
| 8086:10f0 | 8086:0037 | Intel      | 82578DC Gigabit Network C... | 8     | e1000e     | 3462CD0CCD |
| 8086:1502 | 103c:1495 | Intel      | 82579LM Gigabit Network C... | 8     | e1000e     | 3D9E77AE8A |
| 8086:1503 | 1025:8000 | Intel      | 82579V Gigabit Network Co... | 8     | e1000e     | CABB268939 |
| 8086:1503 | 8086:2017 | Intel      | 82579V Gigabit Network Co... | 8     | e1000e     | C2DCE3184C |
| 10de:0057 | 1695:1010 | Nvidia     | CK804 Ethernet Controller    | 7     | forcedeth  | 83BFA1527C |
| 10de:0269 | 105b:0d04 | Nvidia     | MCP51 Ethernet Controller    | 7     | forcedeth  | 63D2D50C37 |
| 10de:03ef | 1019:2609 | Nvidia     | MCP61 Ethernet               | 7     | forcedeth  | 5343BC19E6 |
| 1106:3065 | 1565:2200 | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 7     | via_rhine  | B3224EB5FC |
| 8086:10d3 | 1043:8369 | Intel      | 82574L Gigabit Network Co... | 7     | e1000e     | 81C929F40D |
| 8086:10ef | 103c:304b | Intel      | 82578DM Gigabit Network C... | 7     | e1000e     | 16C4C7C1C0 |
| 8086:1502 | 17aa:3077 | Intel      | 82579LM Gigabit Network C... | 7     | e1000e     | CB4983BAF6 |
| 8086:1503 | 8086:2002 | Intel      | 82579V Gigabit Network Co... | 7     | e1000e     | 9CD7C321BD |
| 8086:1539 | 1462:7a32 | Intel      | I211 Gigabit Network Conn... | 7     | igb        | 3E9DFA313B |
| 10de:0269 | 1043:8221 | Nvidia     | MCP51 Ethernet Controller    | 6     | forcedeth  | C7934C20A0 |
| 10de:03ef | 10de:cb84 | Nvidia     | MCP61 Ethernet               | 6     | forcedeth  | 74564F66F9 |
| 8086:10c0 | 1028:0238 | Intel      | 82562V-2 10/100 Network C... | 6     | e1000e     | A1E89001D2 |
| 8086:10d3 | 103c:158a | Intel      | 82574L Gigabit Network Co... | 6     | e1000e     | 2AB82BCF03 |
| 8086:10f0 | 8086:0000 | Intel      | 82578DC Gigabit Network C... | 6     | e1000e     | 78B4FE060A |
| 8086:1502 | 103c:158a | Intel      | 82579LM Gigabit Network C... | 6     | e1000e     | 2AB82BCF03 |
| 8086:27dc | 1462:336c | Intel      | NM10/ICH7 Family LAN Cont... | 6     | e100       | 6F3EF2A57D |
| 10de:0057 | 105b:0ca4 | Nvidia     | CK804 Ethernet Controller    | 5     | forcedeth  | 3645A71E94 |
| 10de:0057 | 1695:1011 | Nvidia     | CK804 Ethernet Controller    | 5     | forcedeth  | 02CEB963E5 |
| 10de:0269 | 103c:2a34 | Nvidia     | MCP51 Ethernet Controller    | 5     | forcedeth  | 11EC1ACB37 |
| 10de:0269 | 1043:8141 | Nvidia     | MCP51 Ethernet Controller    | 5     | forcedeth  | 3F5DF90EE9 |
| 10de:0269 | 105b:0caf | Nvidia     | MCP51 Ethernet Controller    | 5     | forcedeth  | D6D1DC7CD6 |
| 10de:03ef | 103c:2a66 | Nvidia     | MCP61 Ethernet               | 5     | forcedeth  | B3F948427E |
| 10de:03ef | 105b:0d15 | Nvidia     | MCP61 Ethernet               | 5     | forcedeth  | 9DF0CEE262 |
| 1106:3065 | 1462:7255 | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 5     | via_rhine  | E8E3F154BE |
| 8086:10bd | 17aa:3038 | Intel      | 82566DM-2 Gigabit Network... | 5     | e1000e     | C399CBB5F3 |
| 8086:10bd | 8086:0000 | Intel      | 82566DM-2 Gigabit Network... | 5     | e1000e     | C9D4B4FC2F |
| 8086:10c0 | 1462:502c | Intel      | 82562V-2 10/100 Network C... | 5     | e1000e     | 3E9F34C334 |
| 8086:10d3 | 8086:0000 | Intel      | 82574L Gigabit Network Co... | 5     | e1000e     | 046006226D |
| 8086:10de | 1734:114d | Intel      | 82567LM-3 Gigabit Network... | 5     | e1000e     | D6D2A25AA4 |
| 8086:10ef | 103c:304a | Intel      | 82578DM Gigabit Network C... | 5     | e1000e     | 99C6F2F320 |
| 8086:1502 | 103c:1494 | Intel      | 82579LM Gigabit Network C... | 5     | e1000e     | A4BD1F1736 |
| 8086:1502 | 17aa:3084 | Intel      | 82579LM Gigabit Network C... | 5     | e1000e     | 435E64F300 |
| 8086:1502 | 8086:0000 | Intel      | 82579LM Gigabit Network C... | 5     | e1000e     | 492B205B03 |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1455 | 1022:1455 | AMD        | Zeppelin/Renoir PCIe Dumm... | 275   |            | D084D64BDF |
| 1022:145a | 1022:145a | AMD        | Zeppelin/Raven/Raven2 PCI... | 275   |            | D084D64BDF |
| 1022:1455 | 1043:8747 | AMD        | Zeppelin/Renoir PCIe Dumm... | 37    |            | 4A2455EAE6 |
| 1022:145a | 1043:8747 | AMD        | Zeppelin/Raven/Raven2 PCI... | 37    |            | 4A2455EAE6 |
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

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 104c:9065 |           | Texas I... | TMS320DM642                  | 2     |            | A74B989748 |
| 8086:a2a4 |           | Intel      | 200 Series/Z370 Chipset F... | 2     |            | 46EA2E591E |
| 0090:0000 | 0090:0000 |            |                              | 1     |            | B562E609ED |
| 1274:5882 |           | Ensoniq    |                              | 1     |            | 3F25A03C59 |
| 12f4:5000 |           | Megatel    |                              | 1     |            | F9A4969283 |
| 1a39:0004 | 1a39:e020 |            |                              | 1     |            | 93A39661EC |
| 8086:a135 | 8086:a135 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 2E35C3E421 |

### Parallel controller (bidir) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1c00:2170 | 1c00:2170 |            | WCH PCI                      | 1     |            | 204047130C |

### Parallel controller (ecp) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1415:c110 | 1415:c110 | Oxford ... | PCI Express ECP Parallel ... | 2     | parport_pc | E21B8FB5B6 |

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
| 8086:2f30 | 8086:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    | hswep_u... | A8F2B39356 |
| 8086:2f34 | 8086:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    | hswep_u... | A8F2B39356 |
| 8086:2f7d | 8086:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    |            | A8F2B39356 |
| 8086:2f36 | 8086:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 41    | hswep_u... | A8F2B39356 |
| 8086:2f37 | 8086:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 41    | hswep_u... | A8F2B39356 |
| 8086:3c43 | 1043:84ef | Intel      | Xeon E5/Core i7 Ring to P... | 20    | snbep_u... | 1E7C5CF3CF |
| 8086:3c44 | 1043:84ef | Intel      | Xeon E5/Core i7 Ring to Q... | 20    | snbep_u... | 1E7C5CF3CF |
| 8086:3c46 | 1043:84ef | Intel      | Xeon E5/Core i7 Processor... | 20    | snbep_u... | 1E7C5CF3CF |
| 8086:3ce6 | 1043:84ef | Intel      | Xeon E5/Core i7 QuickPath... | 20    |            | 1E7C5CF3CF |
| 8086:2015 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 18    |            | 30502C41DE |
| 8086:204c | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 18    | skx_uncore | 30502C41DE |
| 8086:204d | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 18    | skx_uncore | 30502C41DE |
| 8086:0e30 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 17    | ivbep_u... | EEE7D322DF |
| 8086:0e34 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 17    | ivbep_u... | EEE7D322DF |
| 8086:0e36 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 17    | ivbep_u... | EEE7D322DF |
| 8086:0e36 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 17    | ivbep_u... | 84D3F5ED57 |
| 8086:3c43 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to P... | 15    | snbep_u... | E14EB74EA5 |
| 8086:3c44 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to Q... | 15    | snbep_u... | E14EB74EA5 |
| 8086:3ce6 | 8086:0000 | Intel      | Xeon E5/Core i7 QuickPath... | 15    |            | E14EB74EA5 |
| 8086:6f30 | 8086:6f30 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 14    | bdx_uncore | 7F1BE20709 |
| 8086:6f34 | 8086:6f34 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 14    | bdx_uncore | 7F1BE20709 |
| 8086:6f36 | 8086:6f36 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 14    | bdx_uncore | 7F1BE20709 |
| 8086:6f37 | 8086:6f37 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 14    | bdx_uncore | 7F1BE20709 |
| 8086:6f7d | 8086:6f7d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 14    |            | 7F1BE20709 |
| 8086:0e34 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 13    | ivbep_u... | 84D3F5ED57 |
| 8086:3c46 |           | Intel      | Xeon E5/Core i7 Processor... | 13    | snbep_u... | E14EB74EA5 |
| 8086:0e30 |           | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 9     | ivbep_u... | 84D3F5ED57 |
| 8086:3c43 | 1458:3c43 | Intel      | Xeon E5/Core i7 Ring to P... | 8     | snbep_u... | E3CD42A469 |
| 8086:3c44 | 1458:3c44 | Intel      | Xeon E5/Core i7 Ring to Q... | 8     | snbep_u... | E3CD42A469 |
| 8086:3c46 | 1458:3c46 | Intel      | Xeon E5/Core i7 Processor... | 8     | snbep_u... | E3CD42A469 |
| 8086:3ce6 | 1458:3ce6 | Intel      | Xeon E5/Core i7 QuickPath... | 8     |            | E3CD42A469 |
| 8086:3424 |           | Intel      | 7500/5520/5500/X58 Perfor... | 6     |            | 6710749660 |
| 8086:0e30 | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     | ivbep_u... | 7B26B20B57 |
| 8086:0e30 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     | ivbep_u... | ACF28B5D91 |
| 8086:0e34 | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     | ivbep_u... | 7B26B20B57 |
| 8086:2f36 | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | 608FAFB692 |
| 8086:2f37 | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | 608FAFB692 |
| 8086:0e30 | 1458:3c46 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     | ivbep_u... | DD20758A89 |
| 8086:0e34 | 1458:3c43 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     | ivbep_u... | DD20758A89 |
| 8086:0e36 | 1458:3c44 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     | ivbep_u... | DD20758A89 |
| 8086:2f30 | 1849:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     | hswep_u... | 776B559B1F |
| 8086:2f34 | 1849:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     | hswep_u... | 776B559B1F |
| 8086:2f36 | 1849:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     | hswep_u... | 776B559B1F |
| 8086:2f37 | 1849:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     | hswep_u... | 776B559B1F |
| 8086:2f38 | 8086:2f38 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     | hswep_u... | B89B8C9364 |
| 8086:2f7d | 1849:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     |            | 776B559B1F |
| 8086:6f30 | 1849:6f30 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     | bdx_uncore | 87D6B1C03E |
| 8086:6f34 | 1849:6f34 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     | bdx_uncore | 87D6B1C03E |
| 8086:6f36 | 1849:6f36 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     | bdx_uncore | 87D6B1C03E |
| 8086:6f37 | 1849:6f37 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     | bdx_uncore | 87D6B1C03E |
| 8086:6f7d | 1849:6f7d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     |            | 87D6B1C03E |
| 8086:0e30 | 1734:11b5 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     | ivbep_u... | 961A7ADB3E |
| 8086:0e34 | 1734:11b5 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     | ivbep_u... | 961A7ADB3E |
| 8086:0e36 | 1734:11b5 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     | ivbep_u... | 961A7ADB3E |
| 8086:2f32 | 8086:2f32 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     | hswep_u... | ADB52FAE26 |
| 8086:3c43 | 1028:0497 | Intel      | Xeon E5/Core i7 Ring to P... | 2     | snbep_u... | 428006990E |
| 8086:3c43 | 1462:7760 | Intel      | Xeon E5/Core i7 Ring to P... | 2     | snbep_u... | 748D276276 |
| 8086:3c43 | 1849:3c43 | Intel      | Xeon E5/Core i7 Ring to P... | 2     | snbep_u... | FE65462E73 |
| 8086:3c44 | 1028:0497 | Intel      | Xeon E5/Core i7 Ring to Q... | 2     | snbep_u... | 428006990E |
| 8086:3c44 | 1462:7760 | Intel      | Xeon E5/Core i7 Ring to Q... | 2     | snbep_u... | 748D276276 |
| 8086:3c44 | 1849:3c44 | Intel      | Xeon E5/Core i7 Ring to Q... | 2     | snbep_u... | FE65462E73 |
| 8086:3c46 | 1028:0497 | Intel      | Xeon E5/Core i7 Processor... | 2     | snbep_u... | 428006990E |
| 8086:3c46 | 1462:7760 | Intel      | Xeon E5/Core i7 Processor... | 2     | snbep_u... | 748D276276 |
| 8086:3c46 | 1849:3c46 | Intel      | Xeon E5/Core i7 Processor... | 2     | snbep_u... | FE65462E73 |
| 8086:3c46 | 8086:0000 | Intel      | Xeon E5/Core i7 Processor... | 2     | snbep_u... | A0EFAA8A88 |
| 8086:3ce6 | 1028:0497 | Intel      | Xeon E5/Core i7 QuickPath... | 2     |            | 428006990E |
| 8086:3ce6 | 1462:7760 | Intel      | Xeon E5/Core i7 QuickPath... | 2     |            | 748D276276 |
| 8086:3ce6 | 1849:3ce6 | Intel      | Xeon E5/Core i7 QuickPath... | 2     |            | FE65462E73 |
| 8086:6f32 | 8086:6f32 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     | bdx_uncore | 9EE9F662A8 |
| 8086:6f33 | 8086:6f33 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     | bdx_uncore | 9EE9F662A8 |
| 8086:6f38 | 8086:6f38 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     | bdx_uncore | 9EE9F662A8 |
| 8086:0e30 | 1462:7737 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 725B24FE69 |
| 8086:0e30 | 15d9:0628 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | F7519BF7BE |
| 8086:0e30 | 15d9:062c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 2B1034E588 |
| 8086:0e30 | 17aa:1026 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 5A6C7B0805 |
| 8086:0e30 | 1849:0e30 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 69907BBCE0 |
| 8086:0e34 | 1462:7737 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 725B24FE69 |
| 8086:0e34 | 15d9:0628 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | F7519BF7BE |
| 8086:0e34 | 15d9:062c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 2B1034E588 |
| 8086:0e34 | 17aa:1026 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 5A6C7B0805 |
| 8086:0e34 | 1849:0e34 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 69907BBCE0 |
| 8086:0e36 | 1462:7737 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 725B24FE69 |
| 8086:0e36 | 15d9:0628 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | F7519BF7BE |
| 8086:0e36 | 15d9:062c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 2B1034E588 |
| 8086:0e36 | 17aa:1026 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 5A6C7B0805 |
| 8086:0e36 | 1849:0e36 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 69907BBCE0 |
| 8086:0e38 | 1849:0e38 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 69907BBCE0 |
| 8086:1c23 |           | Intel      | Performance counters         | 1     |            | E5693EC0DB |
| 8086:2015 | 1734:122f | Intel      | Sky Lake-E Ubox Registers    | 1     |            | 14943339B4 |
| 8086:204c | 1734:122f | Intel      | Sky Lake-E M3KTI Registers   | 1     |            | 14943339B4 |
| 8086:204d | 1734:122f | Intel      | Sky Lake-E M3KTI Registers   | 1     | skx_uncore | 14943339B4 |
| 8086:2f30 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     | hswep_u... | 02F86A0A2A |
| 8086:2f34 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     | hswep_u... | 02F86A0A2A |
| 8086:2f36 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     | hswep_u... | 02F86A0A2A |
| 8086:2f36 | 1462:7882 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     | hswep_u... | 1E0208BF20 |
| 8086:2f37 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     | hswep_u... | 02F86A0A2A |
| 8086:2f37 | 1462:7882 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     | hswep_u... | 1E0208BF20 |
| 8086:2f38 | 1849:2f38 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     | hswep_u... | 08B141A0B8 |
| 8086:2f7d | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 02F86A0A2A |
| 8086:3c43 | 1028:0496 | Intel      | Xeon E5/Core i7 Ring to P... | 1     | snbep_u... | 2597040B1B |

### Pic (8259) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3422 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 169   |            | B481805845 |
| 8086:3423 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 169   |            | B481805845 |
| 8086:342e |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 169   | i7core_... | B481805845 |
| 8086:3438 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 105   | i5500_temp | B481805845 |
| 8086:3425 |           | Intel      | 7500/5520/5500/X58 Physic... | 66    |            | 47FD7AB796 |
| 8086:3426 |           | Intel      | 7500/5520/5500/X58 Routin... | 66    |            | 47FD7AB796 |
| 8086:3427 |           | Intel      | 7500/5520/5500 Physical a... | 60    |            | 47FD7AB796 |
| 8086:3428 |           | Intel      | 7500/5520/5500 Routing & ... | 60    |            | 47FD7AB796 |
| 8086:3422 | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 15    |            | A72C60B73B |
| 8086:3423 | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 15    |            | A72C60B73B |
| 8086:342e | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 15    | i7core_... | A72C60B73B |
| 8086:3422 | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 9     |            | CC88E139CC |
| 8086:3423 | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 9     |            | CC88E139CC |
| 8086:342e | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 9     | i7core_... | CC88E139CC |
| 8086:3422 | 0086:0022 | Intel      | 7500/5520/5500/X58 I/O Hu... | 6     |            | 29B0070304 |
| 8086:3423 | 0086:0023 | Intel      | 7500/5520/5500/X58 I/O Hu... | 6     |            | 29B0070304 |
| 8086:342e | 0086:002e | Intel      | 7500/5520/5500/X58 I/O Hu... | 6     | i7core_... | 29B0070304 |
| 8086:3422 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | 81C929F40D |
| 8086:3423 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | 81C929F40D |
| 8086:3425 | 0043:0063 | Intel      | 7500/5520/5500/X58 Physic... | 1     |            | 81C929F40D |
| 8086:3426 | 0043:0063 | Intel      | 7500/5520/5500/X58 Routin... | 1     |            | 81C929F40D |
| 8086:3427 | 0043:0063 | Intel      | 7500/5520/5500 Physical a... | 1     |            | 81C929F40D |
| 8086:3428 | 0043:0063 | Intel      | 7500/5520/5500 Routing & ... | 1     |            | 81C929F40D |
| 8086:342e | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     | i7core_... | 81C929F40D |
| 8086:3438 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | 81C929F40D |

### Pic (io(x)-apic) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:342f |           | Intel      | 7500/5520/5500/X58 Truste... | 60    |            | 47FD7AB796 |
| 8086:342d |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 43    |            | 47FD7AB796 |
| 8086:2f2c | 8086:0000 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 23    |            | A8F2B39356 |
| 1106:5327 |           | VIA Tec... | P4M890 I/O APIC Interrupt... | 21    |            | ECBFA57012 |
| 8086:3c2c | 1043:84ef | Intel      | Xeon E5/Core i7 I/O APIC     | 20    |            | 1E7C5CF3CF |
| 1106:5364 |           | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 18    |            | B3224EB5FC |
| 8086:0e2c | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 17    |            | EEE7D322DF |
| 8086:2026 | 8086:2026 | Intel      | Sky Lake-E IOAPIC            | 16    |            | 30502C41DE |
| 8086:2036 | 8086:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 16    |            | 30502C41DE |
| 8086:3c2c | 8086:3c2c | Intel      | Xeon E5/Core i7 I/O APIC     | 16    |            | E14EB74EA5 |
| 8086:0e2c | 8086:0e2c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 15    |            | 84D3F5ED57 |
| 8086:6f2c | 8086:0000 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 11    |            | 7F1BE20709 |
| 8086:2f2c | 1028:0617 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 9     |            | 3B5017848A |
| 8086:3c2c | 1458:5000 | Intel      | Xeon E5/Core i7 I/O APIC     | 8     |            | E3CD42A469 |
| 1106:5336 |           | VIA Tec... | K8M890CE I/O APIC Interru... | 7     |            | DA7AC663BF |
| 1106:5308 | 1849:5308 | VIA Tec... | PT894 I/O APIC Interrupt ... | 6     |            | FFD7AFA075 |
| 1106:5238 |           | VIA Tec... | K8T890 I/O APIC Interrupt... | 4     |            | D9174E33E4 |
| 1106:5364 | 1106:5364 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 4     |            | 95BF887281 |
| 8086:0e2c | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     |            | 7B26B20B57 |
| 8086:2f2c | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | 608FAFB692 |
| 8086:3504 |           | Intel      | 6311ESB/6321ESB I/OxAPIC ... | 4     |            | 37E5DABF3C |
| 1106:5351 |           | VIA Tec... | VT3351 I/O APIC Interrupt... | 3     |            | EBF0DCD676 |
| 1106:5364 | 1849:5364 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 3     |            | 78DDA2C16B |
| 8086:0e2c | 1458:5000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     |            | DD20758A89 |
| 8086:2f2c | 1849:2f2c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     |            | 776B559B1F |
| 8086:6f2c | 1849:6f2c | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     |            | 87D6B1C03E |
| 1106:5327 | 1849:5327 | VIA Tec... | P4M890 I/O APIC Interrupt... | 2     |            | DAD584057B |
| 8086:0326 | 15d9:7980 | Intel      | 6700/6702PXH I/OxAPIC Int... | 2     |            | 8EB1C21341 |
| 8086:0e2c | 1734:11b5 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | 961A7ADB3E |
| 8086:2026 | 8086:0000 | Intel      | Sky Lake-E IOAPIC            | 2     |            | 46EA2E591E |
| 8086:2036 | 8086:0000 | Intel      | Sky Lake-E IOxAPIC Config... | 2     |            | 46EA2E591E |
| 8086:2f2c | 1028:064c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     |            | E1BABF19AD |
| 8086:3c2c | 1028:0497 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | 428006990E |
| 8086:3c2c | 1462:7760 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | 748D276276 |
| 8086:3c2c | 1849:3c2c | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | FE65462E73 |
| 1106:5327 | 1631:e035 | VIA Tec... | P4M890 I/O APIC Interrupt... | 1     |            | B3494EC9DB |
| 1106:5336 | 1043:8297 | VIA Tec... | K8M890CE I/O APIC Interru... | 1     |            | 9FC75A870D |
| 1106:5351 | 1849:5351 | VIA Tec... | VT3351 I/O APIC Interrupt... | 1     |            | D3A94CD051 |
| 1106:5364 | 1019:2125 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 1     |            | A098C98B04 |
| 8086:0326 |           | Intel      | 6700/6702PXH I/OxAPIC Int... | 1     |            | 219383F559 |
| 8086:0326 | 103c:12f1 | Intel      | 6700/6702PXH I/OxAPIC Int... | 1     |            | 79DDE19254 |
| 8086:0327 |           | Intel      | 6700PXH I/OxAPIC Interrup... | 1     |            | 219383F559 |
| 8086:0327 | 103c:12f1 | Intel      | 6700PXH I/OxAPIC Interrup... | 1     |            | 79DDE19254 |
| 8086:0e2c | 1462:7737 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 725B24FE69 |
| 8086:0e2c | 17aa:1026 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 5A6C7B0805 |
| 8086:0e2c | 1849:0e2c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 69907BBCE0 |
| 8086:1461 | 1014:1461 | Intel      | 82870P2 P64H2 I/OxAPIC       | 1     |            | D6D105AE70 |
| 8086:2026 | 1734:122f | Intel      | Sky Lake-E IOAPIC            | 1     |            | 14943339B4 |
| 8086:2036 | 1734:122f | Intel      | Sky Lake-E IOxAPIC Config... | 1     |            | 14943339B4 |
| 8086:25ac |           | Intel      | 6300ESB I/O Advanced Prog... | 1     |            | 21330F2BD7 |
| 8086:2f2c | 1028:0618 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 76B60C0E5F |
| 8086:2f2c | 1028:0619 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | ADB52FAE26 |
| 8086:2f2c | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 02F86A0A2A |
| 8086:2f2c | 1462:7882 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 1E0208BF20 |
| 8086:3c2c | 1028:0496 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | 2597040B1B |
| 8086:3c2c | 1734:11b5 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | 077A9B9D45 |
| 8086:3c2c | 17aa:1027 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | 9506CD65EE |
| 8086:3c2c | 8086:4953 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | BD6FF7AA0F |
| 8086:6f2c | 1028:0617 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | 019BFC3983 |
| 8086:6f2c | 1028:064c | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | 961BF8073A |
| 8086:6f2c | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | D9B1EC3C37 |

### Pic (io-apic) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:7451 | 1022:7450 | AMD        | AMD-8131 PCI-X IOAPIC        | 2     |            | 940D3D20F9 |

### Power pc (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1957:c006 | 1a56:1201 | Freesca... | MPC8308                      | 2     |            | C784644541 |
| 1957:0085 | 110a:4046 | Freesca... | MPC8347 PBGA                 | 1     |            | 60A7685D8D |

### Processing accelerators (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ee:5000 | 10ee:000e | Xilinx     | Processing accelerators      | 1     | xclmgmt    | 774E748AB4 |
| 10ee:5001 | 10ee:000e | Xilinx     | Processing accelerators      | 1     | xocl       | 774E748AB4 |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:7806 | 1022:7806 | AMD        | FCH SD Flash Controller      | 12    | sdhci_pci  | 1E01EC96F7 |
| 8086:9d2b | 8086:7270 | Intel      | Skylake-U/Y SCC: eMMC        | 6     | sdhci_pci  | 44204F310C |
| 8086:9d2d | 8086:7270 | Intel      | Sunrise Point-LP Secure D... | 6     | sdhci_pci  | 44204F310C |
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | sdhci_pci  | 6144FC259F |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     | sdhci_pci  | 6F498D9D7D |
| 8086:2294 | 1458:1000 | Intel      | Atom/Celeron/Pentium Proc... | 3     | sdhci_pci  | 39694A0489 |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | sdhci_pci  | 6F498D9D7D |
| 10ec:5209 | 10ec:5209 | Realtek... | RTS5209 PCI Express Card ... | 2     | sdhci_pci  | 6FC0406A55 |
| 197b:2381 | 103c:2aa2 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | D8AA06CBF6 |
| 197b:2381 | 103c:2aa6 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | 45542209AF |
| 197b:2381 | 1297:3189 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | 0EFBD74715 |
| 197b:2381 | 1297:4012 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | DE0CC0AB6F |
| 8086:31cc | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 2     | sdhci_pci  | 1C078E1FC5 |
| 8086:31cc | 1458:1000 | Intel      | Celeron/Pentium Silver Pr... | 2     | sdhci_pci  | 8991709C89 |
| 8086:31d0 | 1458:1000 | Intel      | SD Host Controller           | 2     | sdhci_pci  | 8991709C89 |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | sdhci_pci  | 6327FB5122 |
| 1022:7806 | 103c:2b60 | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | 931EFEC797 |
| 1022:7906 | 17aa:3100 | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | 5BD277D767 |
| 1180:0822 | 1509:4780 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 3ADB7D01A9 |
| 1180:e822 | 104d:9060 | Ricoh      | MMC/SD Host Controller       | 1     | sdhci_pci  | 26B75090A9 |
| 1217:7120 | 14ff:a003 | O2 Micro   | Integrated MMC/SD Controller | 1     | sdhci_pci  | 6647A9CB02 |
| 197b:2381 | 1019:2238 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | 7E782321C8 |
| 197b:2381 | 1025:0275 | JMicron... | Standard SD Host Controller  | 1     |            | 09734ADC68 |
| 197b:2381 | 1297:2005 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | BF79C6A1F6 |
| 197b:2381 | 1462:6720 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | E2CB0B1767 |
| 197b:2381 | 1558:0390 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | CD09738BCD |
| 8086:0f16 | 8086:0f16 | Intel      | Atom Processor Z36xxx/Z37... | 1     | sdhci_pci  | 6AC9E1A935 |
| 8086:0f50 | 8086:7270 | Intel      | Atom Processor E3800 Seri... | 1     | sdhci_pci  | 6960F82AE6 |
| 8086:2295 | 1028:07c1 | Intel      | Atom/Celeron/Pentium Proc... | 1     | sdhci_pci  | 9F4F497293 |
| 8086:811c | 8086:8119 | Intel      | US15W/US15X/US15L/UL11L S... | 1     | sdhci_pci  | 1FFCB35DFD |
| 8086:811d | 8086:8119 | Intel      | US15W/US15X/US15L/UL11L S... | 1     | sdhci_pci  | 1FFCB35DFD |
| 8086:9d2b | 8086:2065 | Intel      | Skylake-U/Y SCC: eMMC        | 1     | sdhci_pci  | B1EB5D5F20 |
| 8086:9d2d | 8086:2065 | Intel      | Sunrise Point-LP Secure D... | 1     | sdhci_pci  | B1EB5D5F20 |
| 8086:a375 | 1849:a375 | Intel      | 300 Series Chipset Family... | 1     | sdhci_pci  | D350550408 |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a324 | 1043:8694 | Intel      | Cannon Lake PCH SPI Contr... | 32    |            | 68BABB69CB |
| 8086:a324 | 8086:7270 | Intel      | Cannon Lake PCH SPI Contr... | 31    |            | 0B02A9E571 |
| 8086:a324 | 1849:a324 | Intel      | Cannon Lake PCH SPI Contr... | 20    |            | 39C0FBE126 |
| 8086:a324 | 1025:1238 | Intel      | Cannon Lake PCH SPI Contr... | 5     |            | 1CC81789AC |
| 8086:a324 | 1025:123c | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | AE6F83F149 |
| 8086:a324 | 1462:7b33 | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | 45282961F0 |
| 8086:a324 | 1462:7b98 | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | 21F5EEF1AB |
| 10de:1adb | 10de:1f08 | Nvidia     | TU106 USB Type-C Port Pol... | 3     |            | 35B960D525 |
| 8086:a324 | 17aa:36e7 | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | 1B85D8DB4E |
| 8086:a368 | 1849:a368 | Intel      | Cannon Lake PCH Serial IO... | 3     |            | B2FAC79AFD |
| 8086:a369 | 1849:a369 | Intel      | Cannon Lake PCH Serial IO... | 3     |            | B2FAC79AFD |
| 10de:1ad7 | 19da:1503 | Nvidia     | TU102 UCSI Controller        | 2     | i2c_nvi... | F733910E90 |
| 10de:1ad7 | 3842:2382 | Nvidia     | TU102 UCSI Controller        | 2     |            | 52469C6D63 |
| 10de:1ad9 | 1462:3722 | Nvidia     | TU104 RTX 2080 USB Type-C... | 2     | nvidia_gpu | C3052C67D6 |
| 10de:1adb | 1043:8670 | Nvidia     | TU106 USB Type-C Port Pol... | 2     |            | AF6DA5211E |
| 8086:5ac8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | pwm_lps... | 6F498D9D7D |
| 8086:a324 | 1028:085a | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 3D80EACDFC |
| 8086:a324 | 1028:085c | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 2454AEB8AB |
| 8086:a324 | 103c:83e1 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 6FD9BBB997 |
| 8086:a324 | 103c:843b | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 0FDAC41856 |
| 8086:a324 | 1462:7b23 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 11FD85642C |
| 8086:a324 | 17aa:3138 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | F3279F9D14 |
| 8086:a368 | 1028:085a | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | 3D80EACDFC |
| 8086:a368 | 103c:843b | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | 0FDAC41856 |
| 8086:a368 | 17aa:3138 | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | F3279F9D14 |
| 8086:a369 | 103c:843b | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | 0FDAC41856 |
| 8086:a369 | 17aa:3138 | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | F3279F9D14 |
| 10de:1ad7 | 1028:3718 | Nvidia     | TU102 UCSI Controller        | 1     |            | 30EAA0AC0A |
| 10de:1ad7 | 1043:8675 | Nvidia     | TU102 UCSI Controller        | 1     |            | 4BF5646944 |
| 10de:1ad7 | 10de:12a3 | Nvidia     | TU102 UCSI Controller        | 1     |            | 30502C41DE |
| 10de:1ad7 | 1458:37a9 | Nvidia     | TU102 UCSI Controller        | 1     |            | 0DB3841C91 |
| 10de:1ad7 | 1458:37c4 | Nvidia     | TU102 UCSI Controller        | 1     |            | 510AE49DF2 |
| 10de:1ad7 | 1462:3711 | Nvidia     | TU102 UCSI Controller        | 1     |            | 62128222FA |
| 10de:1ad7 | 1462:3715 | Nvidia     | TU102 UCSI Controller        | 1     |            | CE19512CBB |
| 10de:1ad7 | 3842:2487 | Nvidia     | TU102 UCSI Controller        | 1     |            | C3DCC51002 |
| 10de:1ad9 | 1043:865f | Nvidia     | TU104 RTX 2080 USB Type-C... | 1     |            | B035392AD6 |
| 10de:1ad9 | 1043:8676 | Nvidia     | TU104 RTX 2080 USB Type-C... | 1     |            | 48041296CA |
| 10de:1ad9 | 10b0:1e87 | Nvidia     | TU104 RTX 2080 USB Type-C... | 1     |            | 220759D042 |
| 10de:1ad9 | 10de:12a0 | Nvidia     | TU104 RTX 2080 USB Type-C... | 1     |            | D5D160AFDF |
| 10de:1ad9 | 1458:37a8 | Nvidia     | TU104 RTX 2080 USB Type-C... | 1     |            | AAD0551E27 |
| 10de:1ad9 | 19da:1500 | Nvidia     | TU104 RTX 2080 USB Type-C... | 1     |            | 982548AE86 |
| 10de:1adb | 1043:8671 | Nvidia     | TU106 USB Type-C Port Pol... | 1     |            | B52FC761F9 |
| 10de:1adb | 1043:868a | Nvidia     | TU106 USB Type-C Port Pol... | 1     | i2c_nvi... | D61154EABE |
| 10de:1adb | 1043:868e | Nvidia     | TU106 USB Type-C Port Pol... | 1     | i2c_nvi... | ADEAE621C7 |
| 10de:1adb | 10de:12ad | Nvidia     | TU106 USB Type-C Port Pol... | 1     | i2c_nvi... | 55119E58D9 |
| 10de:1adb | 1458:37c2 | Nvidia     | TU106 USB Type-C Port Pol... | 1     | i2c_nvi... | 54C1F8C1DE |
| 10de:1adb | 1458:37c8 | Nvidia     | TU106 USB Type-C Port Pol... | 1     | i2c_nvi... | 69F2264D39 |
| 10de:1adb | 1458:3fc2 | Nvidia     | TU106 USB Type-C Port Pol... | 1     |            | 8DF2C93C38 |
| 10de:1adb | 1458:3fc9 | Nvidia     | TU106 USB Type-C Port Pol... | 1     |            | 154FBBFFD3 |
| 10de:1adb | 1462:3732 | Nvidia     | TU106 USB Type-C Port Pol... | 1     |            | E86994545D |
| 10de:1adb | 196e:130f | Nvidia     | TU106 USB Type-C Port Pol... | 1     |            | 328F236B37 |
| 10de:1adb | 196e:1314 | Nvidia     | TU106 USB Type-C Port Pol... | 1     |            | 14943339B4 |
| 10de:1adb | 19da:2516 | Nvidia     | TU106 USB Type-C Port Pol... | 1     | i2c_nvi... | A4F9D060D6 |
| 10de:1adb | 3842:2167 | Nvidia     | TU106 USB Type-C Port Pol... | 1     |            | 32073E3911 |
| 10de:1aed | 1043:86a0 | Nvidia     | TU116 RTX 1660/1660 Ti US... | 1     |            | 62428F7C52 |
| 10de:1aed | 10de:1324 | Nvidia     | TU116 RTX 1660/1660 Ti US... | 1     |            | DB0CFC7354 |
| 10de:1aed | 10de:2182 | Nvidia     | TU116 RTX 1660/1660 Ti US... | 1     |            | C4788779C1 |
| 10de:1aed | 1458:3fbe | Nvidia     | TU116 RTX 1660/1660 Ti US... | 1     | i2c_nvi... | 537D11B224 |
| 10de:1aed | 1462:3750 | Nvidia     | TU116 RTX 1660/1660 Ti US... | 1     |            | FB532E634D |
| 10de:1aed | 3842:1167 | Nvidia     | TU116 RTX 1660/1660 Ti US... | 1     | i2c_nvi... | B67D9E13CA |
| 10de:1aed | 3842:1261 | Nvidia     | TU116 RTX 1660/1660 Ti US... | 1     |            | 4591CA066B |
| 8086:0f08 | 8086:0f08 | Intel      | Atom Processor Z36xxx/Z37... | 1     | pwm_lps... | A968EF1DD8 |
| 8086:0f09 | 8086:0f09 | Intel      | Atom Processor Z36xxx/Z37... | 1     | pwm_lps... | A968EF1DD8 |
| 8086:0f0e | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 1     | spi_pxa... | A211982E39 |
| 8086:0f41 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 1     | i2c_des... | A211982E39 |
| 8086:0f42 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 1     | i2c_des... | A211982E39 |
| 8086:5a96 |           | Intel      | Serial bus controller        | 1     |            | 3D61CAE371 |
| 8086:a324 | 1028:085b | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | EDC4AF2350 |
| 8086:a324 | 1028:0866 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 29ECA9D63C |
| 8086:a324 | 1028:0871 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | B186519684 |
| 8086:a324 | 103c:83ed | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 532B72754E |
| 8086:a324 | 103c:843c | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | E06AE20A25 |
| 8086:a324 | 1462:7b17 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | D1EC1DAC8F |
| 8086:a324 | 1462:7b18 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | B67D9E13CA |
| 8086:a324 | 1462:7b25 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | EDC325267B |
| 8086:a324 | 1462:7b29 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 10D87BF0EA |
| 8086:a324 | 1462:7b51 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 59C3AFA37A |
| 8086:a324 | 1462:b919 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 95EF6A898D |
| 8086:a324 | 1734:1246 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | E9AD0C032A |
| 8086:a368 | 1028:085b | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | EDC4AF2350 |
| 8086:a368 | 1028:0871 | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | B186519684 |
| 8086:a368 | 103c:843c | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | E06AE20A25 |
| 8086:a369 | 103c:843c | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | E06AE20A25 |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8c3d | 1458:1c3a | Intel      | 8 Series/C220 Series Chip... | 53    | serial     | 1E5997F695 |
| 8086:2e17 | 1028:027f | Intel      | 4 Series Chipset Serial K... | 20    | serial     | DFA7361038 |
| 8086:2e17 | 103c:3048 | Intel      | 4 Series Chipset Serial K... | 19    | serial     | B511052CC4 |
| 8086:29b7 | 1028:0211 | Intel      | 82Q35 Express Serial KT C... | 18    | serial     | 8C1C529BDC |
| 8086:3b67 | 8086:0036 | Intel      | 5 Series/3400 Series Chip... | 15    | serial     | 3462CD0CCD |
| 8086:2e17 | 1028:0420 | Intel      | 4 Series Chipset Serial K... | 14    | serial     | 0C9CE69911 |
| 8086:1e3d | 103c:339a | Intel      | 7 Series/C210 Series Chip... | 13    | serial     | 76F6D2AF22 |
| 8086:2e17 | 1734:114c | Intel      | 4 Series Chipset Serial K... | 13    | serial     | D6D2A25AA4 |
| 8086:1c3d | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 11    | serial     | 5C380FEC25 |
| 8086:1d3d | 103c:1589 | Intel      | C600/X79 series chipset K... | 11    | serial     | E14EB74EA5 |
| 8086:1e3d | 103c:3397 | Intel      | 7 Series/C210 Series Chip... | 11    | serial     | 195649904F |
| 8086:8c3d | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 11    | serial     | 475863E34D |
| 9710:9865 | a000:1000 | MosChip... | PCI 9865 Multi-I/O Contro... | 11    | parport_pc | 1D3FD80F42 |
| 8086:29b7 | 103c:2818 | Intel      | 82Q35 Express Serial KT C... | 10    | serial     | 6D02866E6C |
| 8086:2e17 | 103c:3034 | Intel      | 4 Series Chipset Serial K... | 10    | serial     | 5DC57BDE0C |
| 8086:1c3d | 103c:1497 | Intel      | 6 Series/C200 Series Chip... | 9     | serial     | 6227F00E30 |
| 8086:1e3d | 1458:1c3a | Intel      | 7 Series/C210 Series Chip... | 9     | serial     | BD8118E7B8 |
| 8086:29b7 | 1043:8295 | Intel      | 82Q35 Express Serial KT C... | 9     | serial     | 9057FD4986 |
| 8086:1c3d | 1028:047e | Intel      | 6 Series/C200 Series Chip... | 8     | serial     | 5C7816B17A |
| 8086:1c3d | 103c:1495 | Intel      | 6 Series/C200 Series Chip... | 8     | serial     | 3D9E77AE8A |
| 8086:2e17 | 103c:3646 | Intel      | 4 Series Chipset Serial K... | 8     | serial     | 878673A8E4 |
| 8086:2e17 | 17aa:3048 | Intel      | 4 Series Chipset Serial K... | 8     | serial     | D44E51F592 |
| 8086:1e3d | 1028:0577 | Intel      | 7 Series/C210 Series Chip... | 7     | serial     | 87DAB1466B |
| 8086:2e17 | 1028:0276 | Intel      | 4 Series Chipset Serial K... | 7     | serial     | 888F2F55D8 |
| 8086:3b67 | 103c:304b | Intel      | 5 Series/3400 Series Chip... | 7     | serial     | 16C4C7C1C0 |
| 8086:8c3d | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 7     | serial     | 24870345D1 |
| 8086:8c3d | 103c:18e7 | Intel      | 8 Series/C220 Series Chip... | 7     | serial     | D1235890E4 |
| 4348:3253 | 4348:3253 | WCH.CN     | CH352 PCI Dual Serial Por... | 6     | serial     | A2F40FA9C0 |
| 8086:1c3d | 17aa:3077 | Intel      | 6 Series/C200 Series Chip... | 6     | serial     | CB4983BAF6 |
| 8086:8c3d | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 6     | serial     | E412FEBD37 |
| 8086:8d3d | 1028:0617 | Intel      | C610/X99 series chipset K... | 6     | serial     | 945E8A152D |
| 9710:9912 | a000:1000 | MosChip... | PCIe 9912 Multi-I/O Contr... | 6     | serial     | 92F011CFCF |
| 8086:1c3d | 103c:1494 | Intel      | 6 Series/C200 Series Chip... | 5     | serial     | A4BD1F1736 |
| 8086:1d3d | 103c:158a | Intel      | C600/X79 series chipset K... | 5     | serial     | 2AB82BCF03 |
| 8086:1e3d | 1028:052c | Intel      | 7 Series/C210 Series Chip... | 5     | serial     | AEA3EEF94B |
| 8086:1e3d | 17aa:3084 | Intel      | 7 Series/C210 Series Chip... | 5     | serial     | 435E64F300 |
| 8086:29b7 | 103c:2819 | Intel      | 82Q35 Express Serial KT C... | 5     | serial     | 073E07ECC0 |
| 8086:29b7 | 17aa:3038 | Intel      | 82Q35 Express Serial KT C... | 5     | serial     | C399CBB5F3 |
| 8086:3b67 | 103c:304a | Intel      | 5 Series/3400 Series Chip... | 5     | serial     | 99C6F2F320 |
| 8086:3b67 | 8086:3b67 | Intel      | 5 Series/3400 Series Chip... | 5     | serial     | 046006226D |
| 1c00:2273 | 1c00:2273 |            | WCH PCI                      | 4     | serial     | 579DE6C00D |
| 8086:1c3d | 103c:1496 | Intel      | 6 Series/C200 Series Chip... | 4     | serial     | 4E44453A25 |
| 8086:1c3d | 8086:2008 | Intel      | 6 Series/C200 Series Chip... | 4     | serial     | A44CE70FF7 |
| 8086:1e3d | 103c:3396 | Intel      | 7 Series/C210 Series Chip... | 4     | serial     | 59CF4AC8D6 |
| 8086:29b7 | 1458:29b7 | Intel      | 82Q35 Express Serial KT C... | 4     | serial     | C9D4B4FC2F |
| 8086:29b7 | 1734:10fc | Intel      | 82Q35 Express Serial KT C... | 4     | serial     | FD6FD654DB |
| 8086:2e17 | 103c:3035 | Intel      | 4 Series Chipset Serial K... | 4     | serial     | 68675FA918 |
| 8086:2e17 | 103c:3036 | Intel      | 4 Series Chipset Serial K... | 4     | serial     | 628F536295 |
| 8086:2e17 | 17aa:3047 | Intel      | 4 Series Chipset Serial K... | 4     | serial     | B1781FED7E |
| 9710:9835 | 1000:0002 | MosChip... | PCI 9835 Multi-I/O Contro... | 4     | parport... | E04FF14502 |
| 10ec:816a | 1458:e000 | Realtek... | Virtual COM1                 | 3     |            | E528F92A7A |
| 10ec:816a | 17aa:3089 | Realtek... | Virtual COM1                 | 3     |            | D9A1939AB2 |
| 10ec:816b | 1458:e000 | Realtek... | RealManage COM2              | 3     |            | E528F92A7A |
| 10ec:816b | 17aa:3089 | Realtek... | RealManage COM2              | 3     |            | D9A1939AB2 |
| 1c00:3250 | 1c00:3250 |            | WCH PCI Express              | 3     | parport... | B8D65BF075 |
| 8086:1c3d | 17aa:3070 | Intel      | 6 Series/C200 Series Chip... | 3     | serial     | C8F1C4E6D9 |
| 8086:1e3d | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 3     | serial     | 8C024FD42B |
| 8086:2e17 | 17aa:3049 | Intel      | 4 Series Chipset Serial K... | 3     | serial     | BBE905E397 |
| 8086:8c3d | 103c:18e4 | Intel      | 8 Series/C220 Series Chip... | 3     | serial     | 862146DFEC |
| 8086:a13d | 1028:06b9 | Intel      | 100 Series/C230 Series Ch... | 3     | serial     | 1916690FA7 |
| 9710:9922 | a000:1000 | MosChip... | MCS9922 PCIe Multi-I/O Co... | 3     | serial     | C59E0D2B42 |
| 1393:1141 |           | Moxa Te... | Industrio CP-114             | 2     | mxser      | 1F62DD8462 |
| 1415:c158 | 1415:c158 | Oxford ... | OXPCIe952 Dual 16C950 UART   | 2     | serial     | 7D8D500F39 |
| 4348:7053 | 4348:3253 | WCH.CN     | CH353 PCI Dual Serial and... | 2     | parport... | 4ED9F3C61F |
| 8086:1c3d | 1025:0493 | Intel      | 6 Series/C200 Series Chip... | 2     | serial     | 2F8EDDD53D |
| 8086:1c3d | 103c:1587 | Intel      | 6 Series/C200 Series Chip... | 2     | serial     | E74C8AB762 |
| 8086:1c3d | 103c:1588 | Intel      | 6 Series/C200 Series Chip... | 2     | serial     | 082313CDB6 |
| 8086:1c3d | 1458:1c3d | Intel      | 6 Series/C200 Series Chip... | 2     | serial     | 492B205B03 |
| 8086:1d3d | 1028:0497 | Intel      | C600/X79 series chipset K... | 2     | serial     | 428006990E |
| 8086:1d3d | 1028:05d2 | Intel      | C600/X79 series chipset K... | 2     | serial     | 95BA8F99A0 |
| 8086:1d3d | 103c:158b | Intel      | C600/X79 series chipset K... | 2     | serial     | E9DB290332 |
| 8086:1e3d | 1462:7808 | Intel      | 7 Series/C210 Series Chip... | 2     | serial     | 4120DB4E70 |
| 8086:1e3d | 17aa:102e | Intel      | 7 Series/C210 Series Chip... | 2     | serial     | A5B315D51A |
| 8086:1e3d | 17aa:3083 | Intel      | 7 Series/C210 Series Chip... | 2     | serial     | 2E7ABFE281 |
| 8086:2997 | 103c:2801 | Intel      | 82Q963/Q965 KT Controller    | 2     | serial     | 086180546A |
| 8086:2997 | 8086:4f43 | Intel      | 82Q963/Q965 KT Controller    | 2     | serial     | 1847B52353 |
| 8086:29b7 | 103c:281a | Intel      | 82Q35 Express Serial KT C... | 2     | serial     | B388241442 |
| 8086:29b7 | 17aa:3037 | Intel      | 82Q35 Express Serial KT C... | 2     | serial     | 487FC34F2F |
| 8086:29b7 | 8086:4f4a | Intel      | 82Q35 Express Serial KT C... | 2     | serial     | 3EE5BD924C |
| 8086:2e17 | 1025:0151 | Intel      | 4 Series Chipset Serial K... | 2     | serial     | C9DE38152E |
| 8086:2e17 | 103c:3647 | Intel      | 4 Series Chipset Serial K... | 2     | serial     | C95D48DB93 |
| 8086:2e17 | 1458:2e17 | Intel      | 4 Series Chipset Serial K... | 2     | serial     | FFDEB2B6E2 |
| 8086:2e17 | 8086:1003 | Intel      | 4 Series Chipset Serial K... | 2     | serial     | 53C6C139DA |
| 8086:3b67 | 1025:039f | Intel      | 5 Series/3400 Series Chip... | 2     | serial     | C80D56CB77 |
| 8086:3b67 | 1028:02da | Intel      | 5 Series/3400 Series Chip... | 2     | serial     | 4A526A31BD |
| 8086:3b67 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 2     | serial     | DE250A8BBE |
| 8086:3b67 | 1734:1168 | Intel      | 5 Series/3400 Series Chip... | 2     | serial     | 9ED71FDBCF |
| 8086:3b67 | 8086:0037 | Intel      | 5 Series/3400 Series Chip... | 2     | serial     | F58375E009 |
| 8086:8c3d | 103c:1825 | Intel      | 8 Series/C220 Series Chip... | 2     | serial     | 44A8F8DE17 |
| 8086:8c3d | 103c:18e5 | Intel      | 8 Series/C220 Series Chip... | 2     | serial     | 4E440FBE69 |
| 8086:8c3d | 103c:18e6 | Intel      | 8 Series/C220 Series Chip... | 2     | serial     | C0BDA7E63F |
| 8086:8c3d | 103c:1905 | Intel      | 8 Series/C220 Series Chip... | 2     | serial     | D6546C5E95 |
| 8086:8c3d | 17aa:3097 | Intel      | 8 Series/C220 Series Chip... | 2     | serial     | F664FB0C42 |
| 8086:8c3d | 17aa:309f | Intel      | 8 Series/C220 Series Chip... | 2     | serial     | 14CBA25E3E |
| 8086:8c3d | 17aa:30a3 | Intel      | 8 Series/C220 Series Chip... | 2     | serial     | 0AEB179EB6 |
| 8086:8c3d | 17aa:30a5 | Intel      | 8 Series/C220 Series Chip... | 2     | serial     | BBD219F883 |
| 8086:a13d | 1028:07c5 | Intel      | 100 Series/C230 Series Ch... | 2     | serial     | ADD4A57D4C |
| 8086:a13d | 8086:1999 | Intel      | 100 Series/C230 Series Ch... | 2     | serial     | 0D2A7EFA14 |
| 8086:a363 | 1028:085a | Intel      | Cannon Lake PCH Active Ma... | 2     | serial     | 3D80EACDFC |
| 8086:a363 | 103c:83e1 | Intel      | Cannon Lake PCH Active Ma... | 2     | serial     | 6FD9BBB997 |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a131 | 1458:8888 | Intel      | 100 Series/C230 Series Ch... | 37    | intel_p... | 85B34D0336 |
| 8086:a131 | 1849:a131 | Intel      | 100 Series/C230 Series Ch... | 37    | intel_p... | BCB3EF58AB |
| 8086:a379 | 1458:8888 | Intel      | Cannon Lake PCH Thermal C... | 31    | intel_p... | 0B02A9E571 |
| 8086:a2b1 | 1849:a2b1 | Intel      | 200 Series PCH Thermal Su... | 23    |            | CACD7C9489 |
| 8086:a131 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 21    | intel_p... | BD6DC70775 |
| 8086:a379 | 1849:a379 | Intel      | Cannon Lake PCH Thermal C... | 20    | intel_p... | 39C0FBE126 |
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 16    | process... | 6053E60588 |
| 8086:a131 | 1462:7a15 | Intel      | 100 Series/C230 Series Ch... | 16    | intel_p... | 7C7D8F8CB6 |
| 8086:a2b1 | 1043:873c | Intel      | 200 Series PCH Thermal Su... | 11    |            | 30502C41DE |
| 8086:8c24 | 1025:0750 | Intel      | 8 Series Chipset Family T... | 10    | intel_p... | 7FDD5F778A |
| 8086:2932 | 1043:8277 | Intel      | 82801I (ICH9 Family) Ther... | 9     |            | 9057FD4986 |
| 8086:284f | 1734:0000 | Intel      | 82801H (ICH8 Family) Ther... | 7     |            | 82E5D349D1 |
| 8086:a131 | 1462:7971 | Intel      | 100 Series/C230 Series Ch... | 7     | intel_p... | 32625A3743 |
| 8086:a160 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 7     | intel_l... | C040F989FE |
| 8086:a161 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 7     | intel_l... | C040F989FE |
| 8086:3b32 | 8086:3b32 | Intel      | 5 Series/3400 Series Chip... | 6     | intel_ips  | 02BE0926E8 |
| 8086:8c24 | 1734:11ea | Intel      | 8 Series Chipset Family T... | 6     | intel_p... | D7D5245A1A |
| 8086:9d27 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 6     | intel_l... | 44204F310C |
| 8086:9d31 | 8086:7270 | Intel      | Sunrise Point-LP Thermal ... | 6     | intel_p... | 44204F310C |
| 8086:a131 | 1028:06b9 | Intel      | 100 Series/C230 Series Ch... | 6     | intel_p... | 5E6308D089 |
| 8086:a131 | 1462:7978 | Intel      | 100 Series/C230 Series Ch... | 6     | intel_p... | 8B7204FCBA |
| 8086:1c24 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 5     |            | E5693EC0DB |
| 8086:a127 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 5     | intel_l... | C040F989FE |
| 8086:a379 | 1025:1238 | Intel      | Cannon Lake PCH Thermal C... | 5     | intel_p... | 1CC81789AC |
| 8086:3b32 | 105b:0dd5 | Intel      | 5 Series/3400 Series Chip... | 4     | intel_ips  | BA59EB12D9 |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | 6F498D9D7D |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | 6F498D9D7D |
| 8086:a127 | 1462:7982 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_l... | 291EF2F99E |
| 8086:a131 | 1462:7977 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_p... | 2568EDB51D |
| 8086:a131 | 1462:7982 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_p... | 291EF2F99E |
| 8086:a131 | 1734:121d | Intel      | 100 Series/C230 Series Ch... | 4     | intel_p... | 29C7E9E412 |
| 8086:a131 | 8086:a131 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_p... | 2E35C3E421 |
| 8086:a160 | 1462:7971 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_l... | C7C0E1D152 |
| 8086:a160 | 1462:7982 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_l... | 291EF2F99E |
| 8086:a161 | 1462:7971 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_l... | C7C0E1D152 |
| 8086:a161 | 1462:7982 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_l... | 291EF2F99E |
| 8086:a2a7 | 103c:82f2 | Intel      | 200 Series/Z370 Chipset F... | 4     | intel_l... | D4DD63F262 |
| 8086:a2b1 | 1462:7a71 | Intel      | 200 Series PCH Thermal Su... | 4     |            | FCC69B7D1E |
| 8086:a2e0 | 103c:82f2 | Intel      | 200 Series PCH Serial IO ... | 4     | intel_l... | D4DD63F262 |
| 8086:a2e1 | 103c:82f2 | Intel      | 200 Series PCH Serial IO ... | 4     | intel_l... | D4DD63F262 |
| 8086:a379 | 1025:123c | Intel      | Cannon Lake PCH Thermal C... | 4     | intel_p... | AE6F83F149 |
| 8086:a379 | 1462:7b33 | Intel      | Cannon Lake PCH Thermal C... | 4     | intel_p... | 45282961F0 |
| 8086:a379 | 1462:7b98 | Intel      | Cannon Lake PCH Thermal C... | 4     | intel_p... | 21F5EEF1AB |
| 8086:0050 |           | Intel      | Core Processor Thermal Ma... | 3     |            | 4529486397 |
| 8086:1d24 | 1734:11b6 | Intel      | C600/X79 series chipset T... | 3     |            | 961A7ADB3E |
| 8086:1e24 | 1734:11d6 | Intel      | 7 Series/C210 Series Chip... | 3     |            | 7C008C61B0 |
| 8086:2932 | 15d9:0000 | Intel      | 82801I (ICH9 Family) Ther... | 3     |            | 73C2854798 |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 6F498D9D7D |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 6F498D9D7D |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 6F498D9D7D |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 6F498D9D7D |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 6F498D9D7D |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 6F498D9D7D |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 6F498D9D7D |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 6F498D9D7D |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 6327FB5122 |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 6327FB5122 |
| 8086:9d31 | 1458:1000 | Intel      | Sunrise Point-LP Thermal ... | 3     | intel_p... | 9A73BB53F0 |
| 8086:a127 | 1462:7971 | Intel      | 100 Series/C230 Series Ch... | 3     | intel_l... | 5BA3AD1DDD |
| 8086:a127 | 1462:7a99 | Intel      | 100 Series/C230 Series Ch... | 3     | intel_l... | A71AC3A709 |
| 8086:a131 | 1025:108e | Intel      | 100 Series/C230 Series Ch... | 3     | intel_p... | 240876777B |
| 8086:a131 | 1028:06b7 | Intel      | 100 Series/C230 Series Ch... | 3     | intel_p... | C4ABA2451D |
| 8086:a131 | 1462:7972 | Intel      | 100 Series/C230 Series Ch... | 3     | intel_p... | 3ADE7D10F3 |
| 8086:a131 | 1462:7a99 | Intel      | 100 Series/C230 Series Ch... | 3     |            | A71AC3A709 |
| 8086:a131 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 3     | intel_p... | 0D2A7EFA14 |
| 8086:a160 | 1462:7972 | Intel      | 100 Series/C230 Series Ch... | 3     | intel_l... | 3ADE7D10F3 |
| 8086:a160 | 1462:7a99 | Intel      | 100 Series/C230 Series Ch... | 3     | intel_l... | A71AC3A709 |
| 8086:a161 | 1462:7972 | Intel      | 100 Series/C230 Series Ch... | 3     | intel_l... | 3ADE7D10F3 |
| 8086:a161 | 1462:7a99 | Intel      | 100 Series/C230 Series Ch... | 3     | intel_l... | A71AC3A709 |
| 8086:a2b1 | 1028:07a1 | Intel      | 200 Series PCH Thermal Su... | 3     |            | DA78DC8E90 |
| 8086:a2b1 | 1462:7a68 | Intel      | 200 Series PCH Thermal Su... | 3     |            | 842E440F34 |
| 8086:a2b1 | 1462:7a70 | Intel      | 200 Series PCH Thermal Su... | 3     |            | 15AA30ADA9 |
| 8086:a2b1 | 1462:7a72 | Intel      | 200 Series PCH Thermal Su... | 3     |            | EEBB334395 |
| 8086:a2b1 | 1462:7a74 | Intel      | 200 Series PCH Thermal Su... | 3     |            | 72BD3E81F9 |
| 8086:a2b1 | 1462:7a94 | Intel      | 200 Series PCH Thermal Su... | 3     |            | F06F57DDE9 |
| 8086:a2e0 | 1028:07a1 | Intel      | 200 Series PCH Serial IO ... | 3     | intel_l... | DA78DC8E90 |
| 8086:a379 | 17aa:36e7 | Intel      | Cannon Lake PCH Thermal C... | 3     | intel_p... | 1B85D8DB4E |
| 8086:1e24 | 1b0a:0152 | Intel      | 7 Series/C210 Series Chip... | 2     |            | 33F2CAEB25 |
| 8086:1e24 | 8086:1e24 | Intel      | 7 Series/C210 Series Chip... | 2     |            | 084B561015 |
| 8086:284f | 1028:0279 | Intel      | 82801H (ICH8 Family) Ther... | 2     |            | 99B958E286 |
| 8086:31b4 | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_l... | 1C078E1FC5 |
| 8086:31b4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_lpss | 6144FC259F |
| 8086:31b6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_lpss | 6144FC259F |
| 8086:31b8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_lpss | 6144FC259F |
| 8086:31ba | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_l... | 1C078E1FC5 |
| 8086:31ba | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_lpss | 6144FC259F |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 6F498D9D7D |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 6F498D9D7D |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 6F498D9D7D |
| 8086:8d24 | 1458:0000 | Intel      | C610/X99 series chipset T... | 2     |            | 3EC20D4B0A |
| 8086:9d60 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_l... | 44204F310C |
| 8086:9d61 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_l... | 44204F310C |
| 8086:9d62 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_l... | 44204F310C |
| 8086:a127 | 1462:7972 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_l... | 0D8910952F |
| 8086:a127 | 1462:7977 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_l... | 4C23B11A16 |
| 8086:a127 | 1462:7994 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_l... | ED7B2348A1 |
| 8086:a131 | 1019:9bc9 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 744A3F2E54 |
| 8086:a131 | 1019:9c32 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_p... | 7F43E2651E |
| 8086:a131 | 1019:9c56 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_p... | 5C2A8BB899 |
| 8086:a131 | 1025:098e | Intel      | 100 Series/C230 Series Ch... | 2     | intel_p... | 25BCBB7C25 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1c22 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 469   | i2c_i801   | 66A5EA0BE5 |
| 1002:4385 | 1002:4385 | AMD        | SBx00 SMBus Controller       | 447   | i2c_pii... | 394C81B911 |
| 8086:27da | 1043:8179 | Intel      | NM10/ICH7 Family SMBus Co... | 407   | i2c_i801   | FAC5E9FEFA |
| 8086:27da | 1458:5001 | Intel      | NM10/ICH7 Family SMBus Co... | 405   | i2c_i801   | DD0FCDE6C7 |
| 8086:1e22 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 350   | i2c_i801   | 570B707FFB |
| 1002:4385 | 1043:8389 | AMD        | SBx00 SMBus Controller       | 339   | i2c_pii... | D569843A2D |
| 1002:4385 | 1458:4385 | AMD        | SBx00 SMBus Controller       | 326   | i2c_pii... | 8EAEF3C906 |
| 8086:8c22 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 316   | i2c_i801   | F6CCF2BBA6 |
| 8086:1c22 | 1458:5001 | Intel      | 6 Series/C200 Series Chip... | 290   | i2c_i801   | E4C2A9F4EB |
| 8086:3a30 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) SM... | 267   | i2c_i801   | B481805845 |
| 8086:27da | 1849:27da | Intel      | NM10/ICH7 Family SMBus Co... | 249   | i2c_i801   | 5F6E1A3B61 |
| 8086:1e22 | 1458:5001 | Intel      | 7 Series/C216 Chipset Fam... | 245   | i2c_i801   | 8C4047657D |
| 1002:4385 |           | AMD        | SBx00 SMBus Controller       | 244   | i2c_pii... | 33F663A020 |
| 1002:4385 | 1849:4385 | AMD        | SBx00 SMBus Controller       | 222   | i2c_pii... | 85F1B83B30 |
| 8086:2930 | 1043:8277 | Intel      | 82801I (ICH9 Family) SMBu... | 211   | i2c_i801   | 29B7777E42 |
| 8086:a123 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 198   | i2c_i801   | 99614383EB |
| 10de:03eb | 1849:03eb | Nvidia     | MCP61 SMBus                  | 194   | i2c_nfo... | 816FE60D2D |
| 8086:8c22 | 1458:5001 | Intel      | 8 Series/C220 Series Chip... | 184   | i2c_i801   | DD4DA32934 |
| 1022:780b | 1022:780b | AMD        | FCH SMBus Controller         | 146   | i2c_piix4  | 9137FB3859 |
| 8086:3a30 | 1458:5001 | Intel      | 82801JI (ICH10 Family) SM... | 142   | i2c_i801   | F655F180AC |
| 1022:790b | 1043:8747 | AMD        | FCH SMBus Controller         | 123   | i2c_piix4  | 4A2455EAE6 |
| 8086:1c22 | 1849:1c22 | Intel      | 6 Series/C200 Series Chip... | 117   | i2c_i801   | BDA40E6195 |
| 8086:3b30 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 117   | i2c_i801   | 05DC50AA11 |
| 1022:780b | 1849:780b | AMD        | FCH SMBus Controller         | 116   | i2c_piix4  | 54FB4AE774 |
| 8086:2930 | 1458:5001 | Intel      | 82801I (ICH9 Family) SMBu... | 107   | i2c_i801   | 54231260FF |
| 10de:03eb | 1458:0c11 | Nvidia     | MCP61 SMBus                  | 105   | i2c_nfo... | BBF6B6F632 |
| 8086:a123 | 1458:5001 | Intel      | 100 Series/C230 Series Ch... | 103   | i2c_i801   | 0BF4CAF942 |
| 1022:790b | 1458:5001 | AMD        | FCH SMBus Controller         | 88    | i2c_piix4  | 0438613602 |
| 8086:3b30 | 1458:5001 | Intel      | 5 Series/3400 Series Chip... | 85    | i2c_i801   | B39AC90CA0 |
| 8086:8c22 | 1849:8c22 | Intel      | 8 Series/C220 Series Chip... | 79    | i2c_i801   | 8AE6B6F651 |
| 8086:8ca2 | 1043:8534 | Intel      | 9 Series Chipset Family S... | 76    | i2c_i801   | EFA3992D9A |
| 10de:03eb | 1043:8234 | Nvidia     | MCP61 SMBus                  | 72    | i2c_nfo... | 2A30939325 |
| 8086:8c22 | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 72    | i2c_i801   | 7BBCD6F17D |
| 8086:8ca2 | 1458:5001 | Intel      | 9 Series Chipset Family S... | 67    | i2c_i801   | 2DDBCF3D21 |
| 10de:03eb | 1043:83a4 | Nvidia     | MCP61 SMBus                  | 66    | i2c_nfo... | 3248DFD987 |
| 1002:4385 | 1043:82ef | AMD        | SBx00 SMBus Controller       | 65    | i2c_pii... | EE184BFE51 |
| 8086:1e22 | 1849:1e22 | Intel      | 7 Series/C216 Chipset Fam... | 65    | i2c_i801   | 3D8C4FEBC3 |
| 8086:a2a3 | 1458:5001 | Intel      | 200 Series/Z370 Chipset F... | 63    | i2c_i801   | AAD0551E27 |
| 8086:283e | 1043:81ec | Intel      | 82801H (ICH8 Family) SMBu... | 62    | i2c_i801   | A4A45B8A8B |
| 1022:780b | 1043:85ca | AMD        | FCH SMBus Controller         | 57    | i2c_piix4  | 35160C78AD |
| 8086:27da | 1462:7529 | Intel      | NM10/ICH7 Family SMBus Co... | 56    | i2c_i801   | 95C164BFE9 |
| 10de:0052 | 1043:815a | Nvidia     | CK804 SMBus                  | 54    | i2c_nfo... | C92DC5D0CF |
| 8086:a2a3 | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 54    | i2c_i801   | 7F1F084A4F |
| 1022:780b | 1462:7721 | AMD        | FCH SMBus Controller         | 51    | i2c_piix4  | B801DD3F7D |
| 1002:4385 | 1462:7693 | AMD        | SBx00 SMBus Controller       | 49    | i2c_pii... | FEAA959521 |
| 1022:790b | 1849:790b | AMD        | FCH SMBus Controller         | 49    | i2c_piix4  | 54A49FCBF7 |
| 8086:27da | 1462:7592 | Intel      | NM10/ICH7 Family SMBus Co... | 49    | i2c_i801   | B0B570F44B |
| 10de:03eb | 1462:7309 | Nvidia     | MCP61 SMBus                  | 42    | i2c_nfo... | 11D0376265 |
| 8086:1c22 | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 41    | i2c_i801   | 7AF20CDF5A |
| 8086:3b30 | 1849:3b30 | Intel      | 5 Series/3400 Series Chip... | 40    | i2c_i801   | 6CDC452D68 |
| 1022:780b | 1458:4385 | AMD        | FCH SMBus Controller         | 39    | i2c_piix4  | 8226B90793 |
| 8086:1d22 | 1043:84ef | Intel      | C600/X79 series chipset S... | 37    | i2c_i801   | EEE7D322DF |
| 8086:a123 | 1849:a123 | Intel      | 100 Series/C230 Series Ch... | 37    | i2c_i801   | BCB3EF58AB |
| 10de:03eb | 1565:3407 | Nvidia     | MCP61 SMBus                  | 36    | i2c_nfo... | E327FDD558 |
| 10de:0446 | 1462:7369 | Nvidia     | MCP65 SMBus                  | 36    | i2c_nfo... | C46668413C |
| 1022:780b | 1043:8527 | AMD        | FCH SMBus Controller         | 35    | i2c_piix4  | 88E3DD8AEA |
| 8086:27da | 1565:3103 | Intel      | NM10/ICH7 Family SMBus Co... | 35    | i2c_i801   | A1DD312C27 |
| 1002:4385 | 1565:3700 | AMD        | SBx00 SMBus Controller       | 34    | i2c_pii... | C9FA6E4826 |
| 1022:790b | 1043:876b | AMD        | FCH SMBus Controller         | 34    | i2c_piix4  | 76E2078928 |
| 8086:1e22 | 1462:7758 | Intel      | 7 Series/C216 Chipset Fam... | 34    | i2c_i801   | 0A593D376A |
| 10de:0752 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] SMBus  | 33    | i2c_nfo... | 88719BBDD6 |
| 10de:0368 | 1043:8239 | Nvidia     | MCP55 SMBus Controller       | 32    | i2c_nfo... | 4EA0694850 |
| 8086:a323 | 1043:8694 | Intel      | Cannon Lake PCH SMBus Con... | 32    | i2c_i801   | 68BABB69CB |
| 8086:24d3 | 1043:80a6 | Intel      | 82801EB/ER (ICH5/ICH5R) S... | 31    | i2c_i801   | 03602DBEA6 |
| 8086:a323 | 1458:5001 | Intel      | Cannon Lake PCH SMBus Con... | 31    | i2c_i801   | 0B02A9E571 |
| 8086:27da | 8086:27da | Intel      | NM10/ICH7 Family SMBus Co... | 29    | i2c_i801   | 2A6F47B09B |
| 1022:780b | 1043:866a | AMD        | FCH SMBus Controller         | 28    | i2c_pii... | AEC91031D4 |
| 1022:790b | 1849:ffff | AMD        | FCH SMBus Controller         | 28    | i2c_pii... | 88354E515F |
| 8086:24d3 | 1458:24d2 | Intel      | 82801EB/ER (ICH5/ICH5R) S... | 28    | i2c_i801   | 2F12FE1C28 |
| 8086:283e | 1043:81eb | Intel      | 82801H (ICH8 Family) SMBu... | 27    | i2c_i801   | 8DF7E26722 |
| 8086:8d22 | 1043:8600 | Intel      | C610/X99 series chipset S... | 27    | i2c_i801   | A8F2B39356 |
| 8086:3a60 | 1028:0420 | Intel      | 82801JD/DO (ICH10 Family)... | 26    | i2c_i801   | 88DB43EE6F |
| 1039:0016 |           | Silicon... | SiS961/2/3 SMBus controller  | 25    | i2c_sis96x | 6440D5167C |
| 8086:1c22 | 1462:7680 | Intel      | 6 Series/C200 Series Chip... | 25    | i2c_i801   | CBE52D9E29 |
| 8086:1c22 | 8086:1c22 | Intel      | 6 Series/C200 Series Chip... | 25    | i2c_i801   | 808448B5B6 |
| 1002:4385 | 1043:81ef | AMD        | SBx00 SMBus Controller       | 24    | i2c_pii... | EB0CDD472F |
| 1002:4385 | 1462:7641 | AMD        | SBx00 SMBus Controller       | 24    | i2c_pii... | 77F07D2D69 |
| 8086:a2a3 | 1043:872f | Intel      | 200 Series/Z370 Chipset F... | 23    | i2c_i801   | 3B3DC1A093 |
| 8086:a2a3 | 1849:a2a3 | Intel      | 200 Series/Z370 Chipset F... | 23    | i2c_i801   | CACD7C9489 |
| 1002:4385 | 1462:7599 | AMD        | SBx00 SMBus Controller       | 22    | i2c_pii... | 132397AB90 |
| 1022:780b | 1043:84f2 | AMD        | FCH SMBus Controller         | 22    | i2c_piix4  | EF4E23ECE5 |
| 8086:266a | 1043:80a6 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 22    | i2c_i801   | 47C35A4877 |
| 8086:283e | 1028:01da | Intel      | 82801H (ICH8 Family) SMBu... | 22    | i2c_i801   | 5D6E2E4B43 |
| 10de:0752 | 1849:0752 | Nvidia     | MCP78S [GeForce 8200] SMBus  | 21    | i2c_nfo... | AC2555A764 |
| 8086:1e22 | 1028:0577 | Intel      | 7 Series/C216 Chipset Fam... | 21    | i2c_i801   | 87DAB1466B |
| 8086:27da | 1019:2683 | Intel      | NM10/ICH7 Family SMBus Co... | 21    | i2c_i801   | D3B45DE297 |
| 8086:283e | 1458:5001 | Intel      | 82801H (ICH8 Family) SMBu... | 21    | i2c_i801   | BBB6C77D49 |
| 8086:8ca2 | 1849:8ca2 | Intel      | 9 Series Chipset Family S... | 21    | i2c_i801   | 09CC6BAB56 |
| 8086:a123 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 21    | i2c_i801   | BD6DC70775 |
| 8086:2930 | 1028:0211 | Intel      | 82801I (ICH9 Family) SMBu... | 20    | i2c_i801   | 8C1C529BDC |
| 8086:3a30 | 1462:7519 | Intel      | 82801JI (ICH10 Family) SM... | 20    | i2c_i801   | 9994FB8ABA |
| 8086:3a60 | 1028:027f | Intel      | 82801JD/DO (ICH10 Family)... | 20    | i2c_i801   | DFA7361038 |
| 8086:a323 | 1849:a323 | Intel      | Cannon Lake PCH SMBus Con... | 20    | i2c_i801   | 39C0FBE126 |
| 8086:1c22 | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 19    | i2c_i801   | 5C380FEC25 |
| 8086:24d3 | 1849:24d0 | Intel      | 82801EB/ER (ICH5/ICH5R) S... | 19    | i2c_i801   | 0B6FD94458 |
| 10de:0368 | 1462:7250 | Nvidia     | MCP55 SMBus Controller       | 18    | i2c_nfo... | 005023EE9D |
| 8086:0f12 | 1849:0f12 | Intel      | Atom Processor E3800 Seri... | 18    | i2c_i801   | EF6230C726 |
| 8086:27da | 1028:01ad | Intel      | NM10/ICH7 Family SMBus Co... | 18    | i2c_i801   | 018144B94B |
| 8086:27da | 8086:d608 | Intel      | NM10/ICH7 Family SMBus Co... | 18    | i2c_i801   | 08DCF9AA49 |
| 8086:2930 | 8086:5044 | Intel      | 82801I (ICH9 Family) SMBu... | 18    | i2c_i801   | 969A371A99 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27d8 | 1458:a002 | Intel      | NM10/ICH7 Family High Def... | 336   | snd_hda... | D0D6CD20B1 |
| 1002:4383 | 1458:a002 | AMD        | SBx00 Azalia (Intel HDA)     | 278   | snd_hda... | 8EAEF3C906 |
| 8086:1c20 | 1458:a002 | Intel      | 6 Series/C200 Series Chip... | 239   | snd_hda... | E4C2A9F4EB |
| 8086:8c20 | 1043:8576 | Intel      | 8 Series/C220 Series Chip... | 239   | snd_hda... | F6CCF2BBA6 |
| 1002:4383 | 1043:8445 | AMD        | SBx00 Azalia (Intel HDA)     | 213   | snd_hda... | C0B50F9AE1 |
| 8086:0c0c | 8086:2010 | Intel      | Xeon E3-1200 v3/4th Gen C... | 195   | snd_hda... | DD4DA32934 |
| 8086:8c20 | 1458:a002 | Intel      | 8 Series/C220 Series Chip... | 169   | snd_hda... | DD4DA32934 |
| 13f6:0111 | 13f6:0111 | C-Media... | CMI8738/CMI8768 PCI Audio    | 168   | snd_cmipci | F6B9026258 |
| 8086:1e20 | 1458:a002 | Intel      | 7 Series/C216 Chipset Fam... | 163   | snd_hda... | A1E970227D |
| 8086:1c20 | 1043:8445 | Intel      | 6 Series/C200 Series Chip... | 159   | snd_hda... | CF410274A0 |
| 1002:aab0 | 174b:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 155   | snd_hda... | 5F6E1A3B61 |
| 1002:aab0 | 1043:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 152   | snd_hda... | 85F1B83B30 |
| 10de:03f0 | 1849:0397 | Nvidia     | MCP61 High Definition Audio  | 152   | snd_hda... | 4E526BB85F |
| 8086:1e20 | 1043:8445 | Intel      | 7 Series/C216 Chipset Fam... | 150   | snd_hda... | 6BF48D4173 |
| 8086:293e | 1043:829f | Intel      | 82801I (ICH9 Family) HD A... | 146   | snd_hda... | 48709E5844 |
| 8086:a170 | 1043:86c7 | Intel      | 100 Series/C230 Series Ch... | 142   | snd_hda... | 99614383EB |
| 8086:27d8 | 1849:3662 | Intel      | NM10/ICH7 Family High Def... | 137   | snd_hda... | 42C519E784 |
| 10de:0bea |           | Nvidia     | GF108 High Definition Aud... | 136   | snd_hda... | 88E3DD8AEA |
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
| 8086:293e | 1458:a002 | Intel      | 82801I (ICH9 Family) HD A... | 88    | snd_hda... | 54231260FF |
| 8086:3a3e | 1043:82fe | Intel      | 82801JI (ICH10 Family) HD... | 88    | snd_hda... | 6C7C70F0E2 |
| 8086:a170 | 1458:a182 | Intel      | 100 Series/C230 Series Ch... | 87    | snd_hda... | 0BF4CAF942 |
| 1002:4383 | 1043:8444 | AMD        | SBx00 Azalia (Intel HDA)     | 85    | snd_hda... | BDE522FB15 |
| 1002:4383 | 1458:a102 | AMD        | SBx00 Azalia (Intel HDA)     | 84    | snd_hda... | A450827948 |
| 1002:aab0 | 1458:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 81    | snd_hda... | CD0F6202CB |
| 1002:aab0 | 1787:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 80    | snd_hda... | 98FF7EAA07 |
| 8086:27d8 | 1849:0397 | Intel      | NM10/ICH7 Family High Def... | 76    | snd_hda... | 5F6E1A3B61 |
| 8086:3b56 | 1458:a002 | Intel      | 5 Series/3400 Series Chip... | 74    | snd_hda... | B39AC90CA0 |
| 10de:0be4 |           | Nvidia     | High Definition Audio Con... | 71    | snd_hda... | 20093DA7FB |
| 1002:4383 | 1849:7892 | AMD        | SBx00 Azalia (Intel HDA)     | 68    | snd_hda... | 4CFBA0B699 |
| 8086:8c20 | 1462:d817 | Intel      | 8 Series/C220 Series Chip... | 68    | snd_hda... | 7BBCD6F17D |
| 1002:aa90 | 174b:aa90 | AMD        | Turks HDMI Audio [Radeon ... | 66    | snd_hda... | A420D17B64 |
| 10de:0e0f | 1462:8c93 | Nvidia     | GK208 HDMI/DP Audio Contr... | 65    | snd_hda... | 606AACED27 |
| 1002:4383 | 1458:a182 | AMD        | SBx00 Azalia (Intel HDA)     | 64    | snd_hda... | 8CDD8FFE23 |
| 1002:aab0 | 1462:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 64    | snd_hda... | 46F0ADE589 |
| 8086:27d8 | 1043:817f | Intel      | NM10/ICH7 Family High Def... | 61    | snd_hda... | 0C62C4C191 |
| 8086:284b | 1043:81ec | Intel      | 82801H (ICH8 Family) HD A... | 61    | snd_hda... | A4A45B8A8B |
| 1002:aa38 | 174b:aa38 | AMD        | RV710/730 HDMI Audio [Rad... | 60    | snd_hda... | 7A74EB0F6F |
| 8086:1e20 | 1458:a014 | Intel      | 7 Series/C216 Chipset Fam... | 60    | snd_hda... | 8C4047657D |
| 8086:27d8 | 1043:82ea | Intel      | NM10/ICH7 Family High Def... | 59    | snd_hda... | 9D3DBD169B |
| 1002:aa98 | 174b:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 58    | snd_hda... | 9CD2D7F72B |
| 8086:27d8 | 1043:83a1 | Intel      | NM10/ICH7 Family High Def... | 58    | snd_hda... | 1A62B680D7 |
| 1002:aa58 | 174b:aa58 | AMD        | Juniper HDMI Audio [Radeo... | 57    | snd_hda... | A4DA822D7B |
| 1102:0007 | 1102:100a | Creativ... | CA0106/CA0111 [SB Live!/A... | 56    | snd_ca0106 | BDE522FB15 |
| 8086:27d8 | 1462:7529 | Intel      | NM10/ICH7 Family High Def... | 56    | snd_hda... | 95C164BFE9 |
| 1022:780d | 1849:7662 | AMD        | FCH Azalia Controller        | 55    | snd_hda... | 5AEB4ABFE6 |
| 1002:aa68 | 174b:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 54    | snd_hda... | EBB5316694 |
| 8086:293e | 1043:8277 | Intel      | 82801I (ICH9 Family) HD A... | 54    | snd_hda... | 29B7777E42 |
| 10de:0bea | 1569:0f00 | Nvidia     | GF108 High Definition Aud... | 52    | snd_hda... | F99AFC78BD |
| 1002:15de | 1002:15de | AMD        | Raven/Raven2/Fenghuang HD... | 51    | snd_hda... | FDD7A2F512 |
| 1002:4383 | 1849:7662 | AMD        | SBx00 Azalia (Intel HDA)     | 51    | snd_hda... | 98FF7EAA07 |
| 10de:0e1b | 1569:0fc6 | Nvidia     | GK107 HDMI Audio Controller  | 51    | snd_hda... | 230E4F00BA |
| 8086:a2f0 | 1458:a182 | Intel      | 200 Series PCH HD Audio      | 51    | snd_hda... | AAD0551E27 |
| 1022:780d | 1462:d721 | AMD        | FCH Azalia Controller        | 50    | snd_hda... | B801DD3F7D |
| 1002:aa58 | 1787:aa58 | AMD        | Juniper HDMI Audio [Radeo... | 49    | snd_hda... | 47FD7AB796 |
| 1022:1457 | 1043:86c7 | AMD        | Family 17h (Models 00h-0f... | 49    | snd_hda... | 03B0E6294F |
| 8086:1e20 | 1043:8415 | Intel      | 7 Series/C216 Chipset Fam... | 49    | snd_hda... | F3E244219B |
| 8086:27d8 | 1462:7592 | Intel      | NM10/ICH7 Family High Def... | 49    | snd_hda... | B0B570F44B |
| 8086:8ca0 | 1458:a182 | Intel      | 9 Series Chipset Family H... | 49    | snd_hda... | 2DDBCF3D21 |
| 8086:1c20 | 1043:8444 | Intel      | 6 Series/C200 Series Chip... | 48    | snd_hda... | 7A74EB0F6F |
| 1002:4383 | 1043:8436 | AMD        | SBx00 Azalia (Intel HDA)     | 46    | snd_hda... | A2F40FA9C0 |
| 1002:4383 | 1462:d693 | AMD        | SBx00 Azalia (Intel HDA)     | 46    | snd_hda... | D9438B26E4 |
| 1002:aa60 | 174b:aa60 | AMD        | Redwood HDMI Audio [Radeo... | 46    | snd_hda... | 42619A6CCA |
| 1002:4383 | 1043:84fb | AMD        | SBx00 Azalia (Intel HDA)     | 45    | snd_hda... | 9876ED8DB9 |
| 8086:27d8 | 1043:8445 | Intel      | NM10/ICH7 Family High Def... | 45    | snd_hda... | E267629A35 |
| 10de:03f0 | 1043:8234 | Nvidia     | MCP61 High Definition Audio  | 44    | snd_hda... | 37805D6D7E |
| 1022:780d | 1458:a182 | AMD        | FCH Azalia Controller        | 43    | snd_hda... | 77FDDE1684 |
| 1002:aa68 | 1043:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 42    | snd_hda... | A0A7F774C4 |
| 10de:0be2 |           | Nvidia     | GT216 HDMI Audio Controller  | 42    | snd_hda... | EF3F0A5B2B |
| 1022:1457 | 1458:a182 | AMD        | Family 17h (Models 00h-0f... | 41    | snd_hda... | E3FD7D5295 |
| 8086:1c20 | 1462:d788 | Intel      | 6 Series/C200 Series Chip... | 41    | snd_hda... | 7AF20CDF5A |
| 1002:4383 | 1043:841b | AMD        | SBx00 Azalia (Intel HDA)     | 40    | snd_hda... | 81E1D743E9 |
| 1002:4383 | 1458:a022 | AMD        | SBx00 Azalia (Intel HDA)     | 40    | snd_hda... | ADA2BD30FA |
| 1002:aa90 | 1043:aa90 | AMD        | Turks HDMI Audio [Radeon ... | 40    | snd_hda... | BDE522FB15 |
| 8086:27d8 | 1043:83d4 | Intel      | NM10/ICH7 Family High Def... | 40    | snd_hda... | D81A6BB2A7 |
| 10de:0371 | 1043:81f6 | Nvidia     | MCP55 High Definition Audio  | 39    | snd_hda... | 4EA0694850 |
| 1002:4383 | 1458:a014 | AMD        | SBx00 Azalia (Intel HDA)     | 38    | snd_hda... | 2FAE8819F7 |
| 1002:4383 | 1458:a132 | AMD        | SBx00 Azalia (Intel HDA)     | 38    | snd_hda... | B77180A9F5 |
| 1002:aa88 | 174b:aa88 | AMD        | Barts HDMI Audio [Radeon ... | 38    | snd_hda... | 976A601924 |
| 1002:aa98 | 1043:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 38    | snd_hda... | 5FE132E54D |
| 8086:27d8 | 1043:8249 | Intel      | NM10/ICH7 Family High Def... | 38    | snd_hda... | 11C7FDB267 |
| 8086:3a3e | 1043:8357 | Intel      | 82801JI (ICH10 Family) HD... | 38    | snd_hda... | 42CC2F59E6 |
| 1002:4383 | 1043:8410 | AMD        | SBx00 Azalia (Intel HDA)     | 37    | snd_hda... | 6A60A724F9 |
| 13f6:8788 | 1043:8467 | C-Media... | CMI8788 [Oxygen HD Audio]    | 37    | snd_oxygen | E4A1AC8DFE |
| 1002:aab0 | 1682:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 36    | snd_hda... | 0C7ACF2C99 |
| 1002:aaf0 | 1462:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 36    | snd_hda... | FA2BA48F57 |
| 10de:0e0b | 1569:11c0 | Nvidia     | GK106 HDMI Audio Controller  | 36    | snd_hda... | E4A1AC8DFE |
| 1102:0012 | 1102:0010 | Creativ... | Sound Core3D [Sound Blast... | 36    | snd_hda... | 23ACB95370 |
| 1002:aa30 | 174b:aa30 | AMD        | RV770 HDMI Audio [Radeon ... | 35    | snd_hda... | 290FCAF1E8 |
| 1002:aaf0 | 1da2:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 35    | snd_hda... | 394C81B911 |
| 10de:0be3 | 1462:8094 | Nvidia     | High Definition Audio Con... | 35    | snd_hda... | FA683DF592 |

### Storage (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1283:8211 | 1043:8138 | Integra... | ITE 8211F Single Channel ... | 23    | pata_it... | 2BF9512AD1 |
| 1095:3132 | 1043:819f | Silicon... | SiI 3132 Serial ATA Raid ... | 12    | sata_sil24 | 2BF9512AD1 |
| 8086:1d6b | 103c:1589 | Intel      | C602 chipset 4-Port SATA ... | 12    | isci       | E14EB74EA5 |
| 1000:0058 | 1028:1f0e | LSI Log... | SAS1068E PCI-Express Fusi... | 7     | mptsas     | BCA2EBDBAF |
| 1b85:6018 | 1b85:6018 | OCZ Tec... | RD400/400A SSD               | 6     | nvme       | 19AD634C13 |
| 8086:1d6b | 103c:158a | Intel      | C602 chipset 4-Port SATA ... | 6     | isci       | 2AB82BCF03 |
| 1095:3132 | 1095:3132 | Silicon... | SiI 3132 Serial ATA Raid ... | 5     | sata_sil24 | A0F0B2CB3C |
| 1283:8212 | 1043:813a | Integra... | IT8212 Dual channel ATA R... | 4     | pata_it... | 87F8B4B22A |
| 1283:8212 | 105b:0cc0 | Integra... | IT8212 Dual channel ATA R... | 4     | pata_it... | 6311678EE1 |
| 1077:2432 | 1077:0138 | QLogic     | ISP2432-based 4Gb Fibre C... | 3     | qla2xxx    | FB66D16E30 |
| 8086:1d6b | 1734:11b6 | Intel      | C602 chipset 4-Port SATA ... | 3     | isci       | 961A7ADB3E |
| 9004:7178 |           | Adaptec    | AIC-7870P/7871 [AHA-2940/... | 3     | aic7xxx    | 87BEA4712A |
| 9005:8017 | 9005:0045 | Adaptec    | ASC-29320ALP U320            | 3     | aic79xx    | A83B0332F1 |
| 1000:0001 |           | LSI Log... | 53c810                       | 2     | sym53c8xx  | C433E6081D |
| 1000:0030 | 103c:322a | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 2     | mptspi     | C156F0AB27 |
| 1000:0058 | 103c:3229 | LSI Log... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | D082929A57 |
| 1000:0070 | 1000:3010 | LSI Log... | SAS2004 PCI-Express Fusio... | 2     | mpt2sas    | 99E743CA9E |
| 1000:0086 | 103c:158b | Broadco... | SAS2308 PCI-Express Fusio... | 2     | mpt3sas    | E9DB290332 |
| 1095:3114 | 1043:8136 | Silicon... | SiI 3114 [SATALink/SATARa... | 2     | sata_sil   | 87F8B4B22A |
| 10df:fe00 | 10df:fe00 | Emulex     | Zephyr-X LightPulse Fibre... | 2     | lpfc       | F930BC123E |
| 1283:8211 | 1283:8211 | Integra... | ITE 8211F Single Channel ... | 2     | pata_it... | 27A7AB5704 |
| 1b85:1021 | 1b85:1021 | OCZ Tec... | OCZ SCSI storage controller  | 2     | mvsas      | 88092CA377 |
| 1de1:0391 | 1de1:0391 | Tekram ... | TRM-S1040 [DC-315 / DC-39... | 2     | dc395x     | BBFFB3F1D1 |
| 8086:1d6b | 103c:158b | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | E9DB290332 |
| 9004:5078 | 9004:7850 | Adaptec    | AIC-7850T/7856T [AVA-2902... | 2     | aic7xxx    | 5A21D12B42 |
| 9004:8178 |           | Adaptec    | AIC-7870P/7881U [AHA-2940... | 2     | aic7xxx    | 2BAC98B043 |
| 1000:0030 | 1014:1000 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 659D759E6D |
| 1000:0030 | 103c:12f1 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 79DDE19254 |
| 1000:0030 | 103c:1500 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 0F22A261A8 |
| 1000:0030 | 103c:3108 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | A2995F5723 |
| 1000:0050 | 103c:3015 | Broadco... | SAS1064 PCI-X Fusion-MPT SAS | 1     | mptsas     | AA051D69D4 |
| 1000:0054 | 1028:1f08 | LSI Log... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | E4EA2F3DB0 |
| 1000:0054 | 103c:0a98 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | EBE24C86FC |
| 1000:0056 | 1000:3090 | LSI Log... | SAS1064ET PCI-Express Fus... | 1     | mptsas     | 1D642553B7 |
| 1000:0056 | 103c:322b | LSI Log... | SAS1064ET PCI-Express Fus... | 1     | mptsas     | 7FE1A5394C |
| 1000:0058 | 1028:021d | LSI Log... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | 2170E1E6BC |
| 1000:0058 | 1028:1f10 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | F3E244219B |
| 1000:0058 | 103c:12fe | LSI Log... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | D740F3D7E5 |
| 1000:0058 | 103c:130b | LSI Log... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | D790109D9A |
| 1000:0058 | 17aa:101d | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | 18BE0454DD |
| 1000:0059 | 1000:3002 | LSI Log... | MegaRAID SAS 8208ELP/8208ELP | 1     | mptsas     | 2985792735 |
| 1000:0072 | 1000:3020 | LSI Log... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | 96AE8D3618 |
| 1000:0072 | 1000:3060 | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | FB0F30CB65 |
| 1000:0072 | 1000:3080 | LSI Log... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | FFC0ECBF18 |
| 1000:0072 | 1028:1f1c | LSI Log... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | 0EEF21306D |
| 1000:0072 | 1028:1f1d | LSI Log... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | D4B46091B4 |
| 1000:0097 | 1028:0619 | Broadco... | SAS3008 PCI-Express Fusio... | 1     | mpt3sas    | ADB52FAE26 |
| 105a:3d17 | 105a:3d17 | Promise... | PDC40718 (SATA 300 TX4)      | 1     | sata_pr... | E510EC2AB5 |
| 105a:4d68 | 105a:4d68 | Promise... | PDC20268 [Ultra100 TX2]      | 1     | pata_pd... | 082AEB0C22 |
| 105a:4d69 | 105a:4d68 | Promise... | 20269                        | 1     | pata_pd... | DA5A7A6B37 |
| 1095:3110 | 1095:7110 | Silicon... | SCSI storage controller      | 1     |            | 69BD5A45B3 |
| 1095:3531 | 1095:3531 | Silicon... | SiI 3531 [SATALink/SATARa... | 1     | sata_sil24 | 7386C9D836 |
| 1095:3531 | 1462:320a | Silicon... | SiI 3531 [SATALink/SATARa... | 1     | sata_sil24 | 20519D31C3 |
| 10b9:5289 | 1043:816b | ULi Ele... | ULi 5289 SATA                | 1     | sata_uli   | 1473488491 |
| 10b9:5289 | 1458:b003 | ULi Ele... | ULi 5289 SATA                | 1     | sata_uli   | 2637354069 |
| 10cd:1300 | 10cd:1310 | Advance... | ASC1300 / ASC3030 [ABP940... | 1     | advansys   | B7C8E17F50 |
| 1103:2310 | 11ab:11ab | HighPoi... | RocketRAID 2310 4 Port SA... | 1     | sata_mv    | 353DF9771E |
| 117c:0042 | 117c:0042 | ATTO Te... | ExpressSAS 6Gb/s SAS/SATA... | 1     | pm80xx     | 2DF53AC534 |
| 1191:8020 | 1191:8020 | Artop E... | AEC6712U SCSI                | 1     | atp870u    | E593748D4E |
| 11ab:6041 | 1043:8150 | Marvell... | MV88SX6041 4-port SATA II... | 1     | sata_mv    | 3FECAFF6C4 |
| 11ab:7042 | 11ab:11ab | Marvell... | 88SX7042 PCI-e 4-port SAT... | 1     | sata_mv    | 675FB21B01 |
| 1217:7130 | 14ff:a003 | O2 Micro   | Integrated MS/xD Controller  | 1     |            | 6647A9CB02 |
| 19a2:0704 | 10df:e602 | Emulex     | OneConnect OCe10100/OCe10... | 1     | lpfc       | 456CDA8C49 |
| 1b85:1221 | 1b85:1221 | OCZ Tec... | OCZ 12xx SCSI Controller     | 1     |            | 323982480D |
| 8086:1d68 | 8086:1d68 | Intel      | C606 chipset Dual 4-Port ... | 1     | isci       | EBA3BBC86D |
| 8086:1d6b |           | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 99E743CA9E |
| 8086:1d6b | 1028:0497 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 428006990E |
| 8086:1d6b | 15d9:0628 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | F7519BF7BE |
| 8086:1d6b | 15d9:062c | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 2B1034E588 |
| 8086:1d6b | 17aa:1026 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 5A6C7B0805 |
| 8086:1d6b | 17aa:1027 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 9506CD65EE |
| 8086:1d6b | 1849:1d6b | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 69907BBCE0 |
| 9004:5078 |           | Adaptec    | AIC-7850T/7856T [AVA-2902... | 1     | aic7xxx    | 50F010B8B5 |
| 9004:6178 |           | Adaptec    | AIC-7861                     | 1     | aic7xxx    | F1A0393BA2 |
| 9004:6178 | 9004:7861 | Adaptec    | AIC-7861                     | 1     | aic7xxx    | D4B46091B4 |
| 9005:0010 | 9005:2180 | Adaptec    | AHA-2940U2/U2W               | 1     | aic7xxx    | 42124436C1 |
| 9005:8017 | 9005:0044 | Adaptec    | ASC-29320ALP U320            | 1     | aic79xx    | BB914E2D17 |
| 9005:801d | 10f1:2676 | Adaptec    | AIC-7902B U320               | 1     | aic79xx    | 219383F559 |
| ace1:0005 | ace1:0005 |            | Storage controller           | 1     |            | 22F215C605 |
| ace1:0006 | ace1:0006 |            | Storage controller           | 1     |            | EF20304D33 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:4390 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 323   | ahci       | 804B46A359 |
| 8086:8c02 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 308   | ahci       | F6CCF2BBA6 |
| 1002:4390 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 275   | ahci       | D569843A2D |
| 1002:4391 | 1043:84dd | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 274   | ahci       | 6A60A724F9 |
| 8086:1e02 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 255   | ahci       | 570B707FFB |
| 8086:1c02 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 246   | ahci       | 66A5EA0BE5 |
| 1002:4391 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 223   | ahci       | 394C81B911 |
| 1b21:0612 | 1043:84b7 | ASMedia... | ASM1062 Serial ATA Contro... | 207   | ahci       | 9876ED8DB9 |
| 8086:a102 | 1043:8694 | Intel      | Q170/Q150/B150/H170/H110/... | 196   | ahci       | 99614383EB |
| 8086:8c02 | 1458:b005 | Intel      | 8 Series/C220 Series Chip... | 168   | ahci       | DD4DA32934 |
| 8086:1e02 | 1458:b005 | Intel      | 7 Series/C210 Series Chip... | 125   | ahci       | BD8118E7B8 |
| 1022:43b7 | 1b21:1062 | AMD        | 300 Series Chipset SATA C... | 123   | ahci       | 518A8709C7 |
| 1022:7901 | 1043:8747 | AMD        | FCH SATA Controller [AHCI... | 123   | ahci       | 4A2455EAE6 |
| 1002:4391 | 1849:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 121   | ahci       | 85F1B83B30 |
| 1022:43c8 | 1b21:1062 | AMD        | 400 Series Chipset SATA C... | 109   | ahci       | 4A2455EAE6 |
| 8086:1c02 | 1458:b005 | Intel      | 6 Series/C200 Series Chip... | 108   | ahci       | 048F01BE63 |
| 8086:a102 | 1458:b005 | Intel      | Q170/Q150/B150/H170/H110/... | 103   | ahci       | 0BF4CAF942 |
| 1002:4390 | 1849:4390 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 102   | ahci       | A41EFF2ADC |
| 1022:7801 | 1458:b002 | AMD        | FCH SATA Controller [AHCI... | 102   | ahci       | 4C91A0DF19 |
| 1b21:0612 | 1849:0612 | ASMedia... | ASM1062 Serial ATA Contro... | 91    | ahci       | 85F1B83B30 |
| 1022:7801 | 1849:7801 | AMD        | FCH SATA Controller [AHCI... | 89    | ahci       | BF930C8C33 |
| 8086:3a22 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) SA... | 88    | ahci       | EBB5316694 |
| 1022:7901 | 1458:b002 | AMD        | FCH SATA Controller [AHCI... | 86    | ahci       | 0438613602 |
| 197b:2362 | 1043:8460 | JMicron... | JMB362 SATA Controller       | 85    | ahci       | 6A60A724F9 |
| 1022:43b5 | 1b21:1062 | AMD        | X370 Series Chipset SATA ... | 80    | ahci       | D084D64BDF |
| 1022:7800 | 1458:b002 | AMD        | FCH SATA Controller [IDE ... | 80    | ahci       | 8226B90793 |
| 1b4b:9172 | 1458:b000 | Marvell... | 88SE9172 SATA 6Gb/s Contr... | 77    | ahci       | 394C81B911 |
| 8086:8c82 | 1043:8534 | Intel      | 9 Series Chipset Family S... | 72    | ahci       | EFA3992D9A |
| 8086:8c02 | 1849:8c02 | Intel      | 8 Series/C220 Series Chip... | 71    | ahci       | 8AE6B6F651 |
| 1002:4391 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 69    | ahci       | 277055C3E7 |
| 8086:8c02 | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 68    | ahci       | 7BBCD6F17D |
| 8086:1c02 | 1849:1c02 | Intel      | 6 Series/C200 Series Chip... | 62    | ahci       | BDA40E6195 |
| 8086:1e02 | 1849:1e02 | Intel      | 7 Series/C210 Series Chip... | 62    | ahci       | 3D8C4FEBC3 |
| 8086:8c82 | 1458:b005 | Intel      | 9 Series Chipset Family S... | 62    | ahci       | 2DDBCF3D21 |
| 1002:4390 | 1043:82ef | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 60    | ahci       | EE184BFE51 |
| 8086:a282 | 1458:b005 | Intel      | 200 Series PCH SATA contr... | 58    | ahci       | AAD0551E27 |
| 1002:4390 | 1002:4390 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 55    | ahci       | 33F663A020 |
| 1022:7801 | 1043:85ca | AMD        | FCH SATA Controller [AHCI... | 55    | ahci       | 35160C78AD |
| 1022:7801 | 1462:7721 | AMD        | FCH SATA Controller [AHCI... | 51    | ahci       | B801DD3F7D |
| 8086:a282 | 1043:8694 | Intel      | 200 Series PCH SATA contr... | 49    | ahci       | C9E6C4517D |
| 1022:7901 | 1849:7901 | AMD        | FCH SATA Controller [AHCI... | 48    | ahci       | 54A49FCBF7 |
| 1022:43b8 | 1b21:1062 | AMD        | FCH SATA Controller D        | 47    | ahci       | A0518E949A |
| 1002:4391 | 1002:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 46    | ahci       | A420D17B64 |
| 1b21:0612 | 1043:858d | ASMedia... | ASM1062 Serial ATA Contro... | 45    | ahci       | B61D174C21 |
| 1b4b:9130 | 1043:8438 | Marvell... | 88SE9128 PCIe SATA 6 Gb/s... | 41    | ahci       | AC377EFFFB |
| 8086:3a22 | 1458:b005 | Intel      | 82801JI (ICH10 Family) SA... | 38    | ahci       | F655F180AC |
| 1002:4390 | 1043:8443 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 37    | ahci       | 054E0BF393 |
| 1b21:0612 | 1b21:1060 | ASMedia... | ASM1062 Serial ATA Contro... | 37    | ahci       | 5AFC22B5E1 |
| 1b4b:9172 | 1043:8477 | Marvell... | 88SE9172 SATA 6Gb/s Contr... | 37    | ahci       | 0EEF21306D |
| 8086:a102 | 1849:a102 | Intel      | Q170/Q150/B150/H170/H110/... | 37    | ahci       | BCB3EF58AB |
| 8086:3b22 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 35    | ahci       | 349A68F1F0 |
| 1022:7801 | 1043:8527 | AMD        | FCH SATA Controller [AHCI... | 34    | ahci       | 88E3DD8AEA |
| 1022:7901 | 1043:876b | AMD        | FCH SATA Controller [AHCI... | 34    | ahci       | 76E2078928 |
| 8086:1e02 | 1462:7758 | Intel      | 7 Series/C210 Series Chip... | 33    | ahci       | 0A593D376A |
| 8086:1d02 | 1043:84ef | Intel      | C600/X79 series chipset 6... | 32    | ahci       | 1E7C5CF3CF |
| 8086:3b22 | 1458:b005 | Intel      | 5 Series/3400 Series Chip... | 31    | ahci       | B39AC90CA0 |
| 1002:4380 | 1043:81ef | AMD        | SB600 Non-Raid-5 SATA        | 30    | ahci       | B26ED41AB8 |
| 8086:a352 | 1458:b005 | Intel      | Cannon Lake PCH SATA AHCI... | 29    | ahci       | 0B02A9E571 |
| 1002:4390 | 1565:3700 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 28    | ahci       | C9FA6E4826 |
| 1022:7801 | 1043:866a | AMD        | FCH SATA Controller [AHCI... | 28    | ahci       | AEC91031D4 |
| 8086:a352 | 1043:8694 | Intel      | Cannon Lake PCH SATA AHCI... | 27    | ahci       | 68BABB69CB |
| 1002:4391 | 1462:7693 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 26    | ahci       | FEAA959521 |
| 1022:43c8 | 1849:43c8 | AMD        | 400 Series Chipset SATA C... | 26    | ahci       | 54A49FCBF7 |
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 26    | ahci       | 35B960D525 |
| 1002:4390 | 1462:7693 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 24    | ahci       | D9438B26E4 |
| 8086:a282 | 1849:a282 | Intel      | 200 Series PCH SATA contr... | 23    | ahci       | CACD7C9489 |
| 1022:7800 | 1849:7800 | AMD        | FCH SATA Controller [IDE ... | 21    | ahci       | 54FB4AE774 |
| 8086:8d02 | 1043:8600 | Intel      | C610/X99 series chipset 6... | 21    | ahci       | A8F2B39356 |
| 8086:a102 | 1462:7996 | Intel      | Q170/Q150/B150/H170/H110/... | 21    | ahci       | BD6DC70775 |
| 1002:4390 | 1462:7599 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 20    | ahci       | 132397AB90 |
| 1002:4390 | 1462:7641 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 20    | ahci       | 77F07D2D69 |
| 8086:8c82 | 1849:8c82 | Intel      | 9 Series Chipset Family S... | 20    | ahci       | 09CC6BAB56 |
| 8086:a282 | 1043:872f | Intel      | 200 Series PCH SATA contr... | 20    | ahci       | 3B3DC1A093 |
| 1002:4380 | 1458:b002 | AMD        | SB600 Non-Raid-5 SATA        | 19    | ahci       | 727B2B7099 |
| 8086:1e02 | 1028:0577 | Intel      | 7 Series/C210 Series Chip... | 19    | ahci       | 87DAB1466B |
| 8086:a352 | 1849:a352 | Intel      | Cannon Lake PCH SATA AHCI... | 19    | ahci       | 39C0FBE126 |
| 1022:43b6 | 1b21:1062 | AMD        | X399 Series Chipset SATA ... | 18    | ahci       | 0438613602 |
| 8086:2922 | 1043:8277 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 18    | ahci       | 29B7777E42 |
| 8086:3a02 | 103c:3048 | Intel      | 82801JD/DO (ICH10 Family)... | 17    | ahci       | 44FFC77631 |
| 1b4b:9123 | 1043:8400 | Marvell... | 88SE9123 PCIe SATA 6.0 Gb... | 16    | ahci       | C9CCBD7C3F |
| 8086:1c02 | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 16    | ahci       | 0BE7A39100 |
| 8086:2922 | 1028:0211 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 16    | ahci       | 8C1C529BDC |
| 8086:3a02 | 1028:027f | Intel      | 82801JD/DO (ICH10 Family)... | 16    | ahci       | DFA7361038 |
| 8086:a102 | 1462:7a15 | Intel      | Q170/Q150/B150/H170/H110/... | 16    | ahci       | 7C7D8F8CB6 |
| 1002:4390 | 1019:4390 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 15    | ahci       | CA438DD2A7 |
| 1b4b:9128 | 1458:b000 | Marvell... | 88SE9128 PCIe SATA 6 Gb/s... | 15    | ahci       | 47FD7AB796 |
| 1b4b:9215 | 1b4b:9215 | Marvell... | 92xx SATA 6G Controller      | 15    | ahci       | C92DC5D0CF |
| 1002:4391 | 1043:8443 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 14    | ahci       | 81E1D743E9 |
| 1022:7901 | 1462:7a34 | AMD        | FCH SATA Controller [AHCI... | 14    | ahci       | 518A8709C7 |
| 10de:0ad4 | 1849:0ad4 | Nvidia     | MCP78S [GeForce 8200] AHC... | 14    | ahci       | BCD563149D |
| 8086:0f23 | 1849:0f23 | Intel      | Atom Processor E3800 Seri... | 14    | ahci       | 9F5937D37E |
| 8086:0f23 | 8086:0f23 | Intel      | Atom Processor E3800 Seri... | 14    | ahci       | BAE419604E |
| 8086:2923 | 1458:b005 | Intel      | 82801IB (ICH9) 4 port SAT... | 14    | ahci       | 6496BC4F36 |
| 8086:8d62 | 1043:8600 | Intel      | C610/X99 series chipset s... | 14    | ahci       | A8F2B39356 |
| 1022:7800 | 1043:84f2 | AMD        | FCH SATA Controller [IDE ... | 13    | ahci       | EF4E23ECE5 |
| 197b:2360 | 1043:8208 | JMicron... | JMB360 AHCI Controller       | 13    | ahci       | C7934C20A0 |
| 1b21:0612 | 1043:85e2 | ASMedia... | ASM1062 Serial ATA Contro... | 13    | ahci       | AB917AE97E |
| 1b4b:9230 | 1b4b:9230 | Marvell... | 88SE9230 PCIe SATA 6Gb/s ... | 13    | ahci       | ED68722348 |
| 8086:0f23 | 1458:b002 | Intel      | Atom Processor E3800 Seri... | 13    | ahci       | 2D2468C273 |
| 8086:1c02 | 103c:2abf | Intel      | 6 Series/C200 Series Chip... | 13    | ahci       | 6567AEB3C4 |

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
| 10de:03f6 | 1043:83a4 | Nvidia     | MCP61 SATA Controller        | 66    | sata_nv... | 3248DFD987 |
| 1002:439c | 1043:82ef | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 65    | pata_at... | EE184BFE51 |
| 10de:03ec | 1043:83a4 | Nvidia     | MCP61 IDE                    | 64    | pata_am... | 3248DFD987 |
| 1002:439c | 1002:439c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 63    | pata_at... | 33F663A020 |
| 8086:2920 | 1043:8277 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 62    | ata_pii... | 48709E5844 |
| 8086:1c00 | 1849:1c00 | Intel      | 6 Series/C200 Series Chip... | 59    | ata_pii... | EC6555DA94 |
| 8086:1c08 | 1849:1c08 | Intel      | 6 Series/C200 Series Chip... | 58    | ata_pii... | EC6555DA94 |
| 11ab:6121 | 1043:82a2 | Marvell... | 88SE6111/6121 SATA II / P... | 56    | pata_ma... | 500CF9D1A0 |
| 8086:27c0 | 1462:7529 | Intel      | NM10/ICH7 Family SATA Con... | 56    | ata_pii... | 95C164BFE9 |
| 10de:0053 | 1043:815a | Nvidia     | CK804 IDE                    | 54    | pata_am... | C92DC5D0CF |
| 10de:0055 | 1043:815a | Nvidia     | CK804 Serial ATA Controller  | 54    | sata_nv... | C92DC5D0CF |
| 11ab:6101 | 11ab:6101 | Marvell... | 88SE6101/6102 single-port... | 54    | pata_ma... | FE7535550F |
| 8086:27df | 1462:7529 | Intel      | 82801G (ICH7 Family) IDE ... | 54    | ata_pii... | 95C164BFE9 |
| 8086:3b20 | 1458:b002 | Intel      | 5 Series/3400 Series Chip... | 54    | ata_pii... | 85F57C764C |
| 8086:3b26 | 1458:b002 | Intel      | 5 Series/3400 Series Chip... | 54    | ata_pii... | 85F57C764C |
| 10de:0054 | 1043:815a | Nvidia     | CK804 Serial ATA Controller  | 53    | sata_nv... | C92DC5D0CF |
| 8086:2820 | 1043:81ec | Intel      | 82801H (ICH8 Family) 4 po... | 53    | ata_pii... | A4A45B8A8B |
| 8086:2825 | 1043:81ec | Intel      | 82801HR/HO/HH (ICH8R/DO/D... | 53    | ata_pii... | A4A45B8A8B |
| 8086:27c0 | 1462:7592 | Intel      | NM10/ICH7 Family SATA Con... | 49    | ata_pii... | B0B570F44B |
| 8086:2921 | 1458:b002 | Intel      | 82801IB (ICH9) 2 port SAT... | 49    | ata_pii... | 54231260FF |
| 8086:27df | 1462:7592 | Intel      | 82801G (ICH7 Family) IDE ... | 47    | ata_pii... | B0B570F44B |
| 10de:03f6 | 1462:7309 | Nvidia     | MCP61 SATA Controller        | 43    | sata_nv... | 11D0376265 |
| 8086:27c0 | 8086:27c0 | Intel      | NM10/ICH7 Family SATA Con... | 42    | ata_pii... | 08DCF9AA49 |
| 1002:439c | 1043:8443 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 40    | pata_at... | 054E0BF393 |
| 8086:24db | 1043:80a6 | Intel      | 82801EB/ER (ICH5/ICH5R) I... | 38    | ata_pii... | 03602DBEA6 |
| 11ab:6121 | 1043:82e0 | Marvell... | 88SE6111/6121 SATA II / P... | 37    | pata_ma... | 28DFB478B7 |
| 8086:27df | 8086:27df | Intel      | 82801G (ICH7 Family) IDE ... | 37    | ata_pii... | 08DCF9AA49 |
| 10de:03ec | 1565:3407 | Nvidia     | MCP61 IDE                    | 36    | pata_am... | E327FDD558 |
| 10de:03f6 | 1565:5405 | Nvidia     | MCP61 SATA Controller        | 36    | sata_nv... | E327FDD558 |
| 8086:2920 | 1458:b002 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 36    | ata_pii... | 048C1A4F90 |
| 10de:0448 | 1462:7369 | Nvidia     | MCP65 IDE                    | 34    | pata_am... | C46668413C |
| 8086:27c0 | 1565:5202 | Intel      | NM10/ICH7 Family SATA Con... | 34    | ata_pii... | A1DD312C27 |
| 8086:27df | 1565:3103 | Intel      | 82801G (ICH7 Family) IDE ... | 34    | ata_piix   | A1DD312C27 |
| 1002:439c | 1565:3700 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 33    | pata_at... | C9FA6E4826 |
| 10de:045d | 1462:7369 | Nvidia     | MCP65 SATA Controller        | 33    | pata_ac... | C46668413C |
| 1106:0415 | 1849:0415 | VIA Tec... | VT6415 PATA IDE Host Cont... | 33    | pata_vi... | EC6555DA94 |
| 10de:036e | 1043:8239 | Nvidia     | MCP55 IDE                    | 32    | pata_am... | 4EA0694850 |
| 10de:037f | 1043:8239 | Nvidia     | MCP55 SATA Controller        | 32    | sata_nv... | 4EA0694850 |
| 10de:0759 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] IDE    | 31    | pata_am... | 88719BBDD6 |
| 197b:2368 | 1043:824f | JMicron... | JMB368 IDE controller        | 31    | pata_jm... | 6486BDE550 |
| 10de:0ad0 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] SAT... | 30    | pata_ac... | 2CAE195313 |
| 8086:1c00 | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 30    | ata_pii... | 7AF20CDF5A |
| 8086:1c08 | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 30    | ata_pii... | 7AF20CDF5A |
| 8086:3b20 | 1849:3b20 | Intel      | 5 Series/3400 Series Chip... | 30    | ata_pii... | 6CDC452D68 |
| 8086:3b26 | 1849:3b26 | Intel      | 5 Series/3400 Series Chip... | 30    | ata_pii... | 6CDC452D68 |
| 197b:2363 | 197b:2363 | JMicron... | JMB363 SATA/IDE Controller   | 29    | ahci       | FEAA959521 |
| 1b4b:917a | 1458:b000 | Marvell... | 88SE9172 SATA III 6Gb/s R... | 29    | pata_ac... | 706E1E0BAF |
| 197b:2361 | 1043:824f | JMicron... | JMB361 AHCI/IDE              | 28    | ahci       | 33F663A020 |
| 11ab:6121 | 11ab:6121 | Marvell... | 88SE6111/6121 SATA II / P... | 27    | pata_ma... | 150FE724DE |
| 1b4b:91a3 | 1458:b000 | Marvell... | 88SE91A3 SATA-600 Controller | 27    | pata_ac... | 551193665F |
| 10de:03ec | 10de:cb84 | Nvidia     | MCP61 IDE                    | 26    | pata_am... | C9F702BE07 |
| 197b:2368 | 197b:2368 | JMicron... | JMB368 IDE controller        | 26    | pata_jm... | 363DBD925B |
| 1002:438c | 1458:5002 | AMD        | SB600 IDE                    | 25    | pata_at... | 727B2B7099 |
| 1002:439c | 1462:7641 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 25    | pata_at... | 77F07D2D69 |
| 10de:03ec | 1462:7309 | Nvidia     | MCP61 IDE                    | 25    | pata_am... | 11D0376265 |
| 1002:438c | 1043:81ef | AMD        | SB600 IDE                    | 24    | pata_at... | EB0CDD472F |
| 1002:439c | 1462:7599 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 24    | pata_at... | 132397AB90 |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 103   | nvme       | 4A2455EAE6 |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 84    | nvme       | D084D64BDF |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 16    | nvme       | 537D11B224 |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 15    | nvme       | C9E6C4517D |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/PC SN720 NV... | 14    | nvme       | 89F4BB64D7 |
| 2646:5008 | 2646:5008 | Kingsto... | Non-Volatile memory contr... | 11    | nvme       | 327877AB6E |
| 126f:2263 | 126f:2263 | Silicon... | Non-Volatile memory contr... | 9     | nvme       | 72BD3E81F9 |
| 1cc1:8201 | 1cc1:8201 |            | Non-Volatile memory contr... | 9     | nvme       | 21F5EEF1AB |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 9     | nvme       | 5FE1529C55 |
| 14a4:22f1 | 1b4b:1093 | Lite-On... | M8Pe Series NVMe SSD         | 8     | nvme       | 6707C4A123 |
| 1987:5007 | 1987:5007 | Phison ... | E7 NVMe Controller           | 8     | nvme       | EA54CD12AB |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 7     | nvme       | 6DA17E4170 |
| 126f:2262 | 126f:2262 | Silicon... | Non-Volatile memory contr... | 5     | nvme       | AAD0551E27 |
| 8086:0953 | 8086:370d | Intel      | PCIe Data Center SSD         | 5     | nvme       | 7D5ADE4D65 |
| 10ec:5760 | 5760:10ec | Realtek... | Realtek Non-Volatile memo... | 4     | nvme       | 1EA306CF47 |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 4     | nvme       | 7B5E5B23E7 |
| 1179:0113 | 1179:0001 | Toshiba... | BG3 NVMe SSD Controller      | 3     | nvme       | 3D80EACDFC |
| 1179:0115 | 1179:0001 | Toshiba... | XG4 NVMe SSD Controller      | 3     | nvme       | DB32491DFE |
| 1987:5008 | 1987:5008 | Phison ... | NVMe Storage Controller      | 3     | nvme       | A6040FD25F |
| 1c5c:1527 | 1c5c:1527 | SK Hynix   | Non-Volatile memory contr... | 3     | nvme       | DA78DC8E90 |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 2     | nvme       | F967633275 |
| 14a4:23f1 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 2     | nvme       | 9046D12A6A |
| 15b7:5001 | 1b4b:1093 | Sandisk    | WD Black NVMe SSD            | 2     | nvme       | A3096A6446 |
| 15b7:5003 | 15b7:5003 | Sandisk    | WD Black 2018/PC SN520 NV... | 2     | nvme       | DE187292C8 |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | Non-Volatile memory contr... | 2     | nvme       | E06AE20A25 |
| c0a9:2263 | c0a9:2263 | Micron/... | Non-Volatile memory contr... | 2     | nvme       | 9A41C725F3 |
| 10ec:5762 | 10ec:5762 | Realtek... | Realtek Non-Volatile memo... | 1     | nvme       | EBED6181EA |
| 1179:011a | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 1     | nvme       | B7022F0A45 |
| 126f:2260 | 126f:2260 | Silicon... | Non-Volatile memory contr... | 1     | nvme       | A9E837C9EB |
| 14a4:2200 | 1b4b:1093 | Lite-On... | Lite-On Non-Volatile memo... | 1     | nvme       | 093C4071FD |
| 1c5c:1284 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 1     | nvme       | 4CC72409B5 |
| 1c5c:1504 | 0100:1093 | SK Hynix   | SC300 512GB M.2 2280 SATA... | 1     | nvme       | B186519684 |
| 2646:2262 | 2646:2262 | Kingsto... | Technology Company Non-Vo... | 1     | nvme       | 44204F310C |
| 8086:0953 | 8086:00e1 | Intel      | PCIe Data Center SSD         | 1     | nvme       | 019BFC3983 |
| 8086:0953 | 8086:3705 | Intel      | PCIe Data Center SSD         | 1     | nvme       | 3F982F3E86 |
| 8086:0a54 | 8086:4802 | Intel      | NVMe Datacenter SSD [3DNA... | 1     | nvme       | 093C4071FD |
| 8086:2522 | 8086:3802 | Intel      | NVMe SSD Optane Series Co... | 1     | nvme       | 9EE9F662A8 |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1106:3249 | 1106:3249 | VIA Tec... | VT6421 IDE/SATA Controller   | 33    | sata_via   | 6C7C70F0E2 |
| 8086:2822 | 1458:b005 | Intel      | SATA Controller [RAID mode]  | 18    | ahci       | 0BB045504D |
| 8086:2822 | 1028:0420 | Intel      | SATA Controller [RAID mode]  | 14    | ahci       | 88DB43EE6F |
| 8086:2822 | 1043:8694 | Intel      | SATA Controller [RAID mode]  | 12    | ahci       | 7F1F084A4F |
| 8086:2822 | 103c:2a6f | Intel      | SATA Controller [RAID mode]  | 11    | ahci       | AA83F14B99 |
| 1095:3512 | 1095:6512 | Silicon... | SiI 3512 [SATALink/SATARa... | 10    | sata_sil   | 399101B245 |
| 1095:3114 | 1095:7114 | Silicon... | SiI 3114 [SATALink/SATARa... | 9     | sata_sil   | 9FF9E9007D |
| 8086:2822 | 103c:1309 | Intel      | SATA Controller [RAID mode]  | 9     | ahci       | 5A8BAD0B76 |
| 8086:2822 | 1458:b000 | Intel      | SATA Controller [RAID mode]  | 9     | ahci       | DF39CB5EE3 |
| 1002:4392 | 1025:0444 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 8     | ahci       | 99825EFDBE |
| 1106:3164 | 1106:3164 | VIA Tec... | VT6410 ATA133 RAID contro... | 8     | pata_vi... | 1012BD5A43 |
| 1095:3112 | 1095:6112 | Silicon... | SiI 3112 [SATALink/SATARa... | 7     | sata_sil   | 543960170E |
| 8086:2822 | 103c:2a9c | Intel      | SATA Controller [RAID mode]  | 7     | ahci       | B897AD01AD |
| 1039:0180 | 1043:810e | Silicon... | RAID bus controller 180 S... | 6     | sata_sis   | BF1A9BA973 |
| 1106:3149 | 1043:80ed | VIA Tec... | VIA VT6420 SATA RAID Cont... | 6     | sata_via   | E75F4538BC |
| 8086:2822 | 1028:0293 | Intel      | SATA Controller [RAID mode]  | 6     | ahci       | A72C60B73B |
| 8086:2822 | 1028:05a4 | Intel      | SATA Controller [RAID mode]  | 6     | ahci       | 24870345D1 |
| 8086:2822 | 1043:8534 | Intel      | SATA Controller [RAID mode]  | 6     | ahci       | 155E4D7633 |
| 1002:4393 | 1043:84df | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 5     | ahci       | 747D9B1FD2 |
| 1095:3132 | 1095:7132 | Silicon... | SiI 3132 Serial ATA Raid ... | 5     | sata_sil24 | BFE6BFAFC7 |
| 10b9:5287 | 1043:8056 | ULi Ele... | ULi 5287 SATA                | 5     | sata_uli   | 399101B245 |
| 1283:8212 | 1283:0001 | Integra... | IT8212 Dual channel ATA R... | 5     | pata_it... | 52229B9C49 |
| 8086:2822 | 1025:0389 | Intel      | SATA Controller [RAID mode]  | 5     | ahci       | A4DA822D7B |
| 8086:2822 | 1028:047e | Intel      | SATA Controller [RAID mode]  | 5     | ahci       | 166533E420 |
| 8086:2822 | 103c:130a | Intel      | SATA Controller [RAID mode]  | 5     | ahci       | 1D642553B7 |
| 8086:2822 | 1043:844d | Intel      | SATA Controller [RAID mode]  | 5     | ahci       | 0EEF21306D |
| 8086:2822 | 1043:84ca | Intel      | SATA Controller [RAID mode]  | 5     | ahci       | E85D169088 |
| 8086:2822 | 8086:514d | Intel      | SATA Controller [RAID mode]  | 5     | ahci       | 7409A9492F |
| 8086:2826 | 103c:1589 | Intel      | C600/X79 series chipset S... | 5     | ahci       | 2EEB0DCBEF |
| 1022:43bd | 1b21:1062 | AMD        | FCH RAID Controller          | 4     |            | 2ED5B5AFC5 |
| 105a:3373 | 1043:80f5 | Promise... | PDC20378 (FastTrak 378/SA... | 4     | sata_pr... | E75F4538BC |
| 1095:0680 | 1095:3680 | Silicon... | PCI0680 Ultra ATA-133 Hos... | 4     | pata_si... | 8168BA11E3 |
| 1095:3114 | 1095:6114 | Silicon... | SiI 3114 [SATALink/SATARa... | 4     | sata_sil   | 34B91208C5 |
| 1283:8212 |           | Integra... | IT8212 Dual channel ATA R... | 4     | pata_it... | 3DD6E989DE |
| 8086:2822 | 1025:0427 | Intel      | SATA Controller [RAID mode]  | 4     | ahci       | AE38CF07EA |
| 8086:2822 | 1028:052c | Intel      | SATA Controller [RAID mode]  | 4     | ahci       | AEA3EEF94B |
| 1000:0073 | 1028:1f78 | LSI Log... | MegaRAID SAS 2008 [Falcon]   | 3     | megarai... | 4683A284A4 |
| 1002:4393 | 1002:4393 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 3     | ahci       | 04549B5B94 |
| 1002:4393 | 1849:4393 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 3     | ahci       | D2B8C394E0 |
| 1022:7916 | 1022:7901 | AMD        | RS690 PCI to PCI Bridge (... | 3     | ahci       | 2ED5B5AFC5 |
| 1039:0180 | 1458:b003 | Silicon... | RAID bus controller 180 S... | 3     | sata_sis   | DB5DEDA228 |
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
| 1000:005d | 1000:9363 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 2     | megarai... | 2B1034E588 |
| 1002:4392 | 103c:2a92 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 2     | ahci       | C620D9EB5A |
| 1002:4392 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 2     | ahci       | 4F578CF2C6 |
| 1002:4393 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 2     | ahci       | 1D1DFCC8E6 |
| 103c:3238 | 103c:3211 | Hewlett... | Smart Array E200i (SAS Co... | 2     | hpsa       | 96AE8D3618 |
| 10de:0abc | 1025:0168 | Nvidia     | MCP79 RAID Controller        | 2     | ahci       | 5443C8EC11 |
| 11ab:6145 | 1043:8220 | Marvell... | 88SE6145 SATA II PCI-E co... | 2     | pata_ma... | CF7CA7E96C |
| 11ab:6440 | 1043:82e4 | Marvell... | 88SE6440 SAS/SATA PCIe co... | 2     | mvsas      | 568DE70E4A |
| 8086:27c3 | 1028:01de | Intel      | 82801GR/GDH (ICH7R/ICH7DH... | 2     | ahci       | 2D447D5FC7 |
| 8086:27c3 | 103c:2a50 | Intel      | 82801GR/GDH (ICH7R/ICH7DH... | 2     | ahci       | 107A895F01 |
| 8086:27c3 | 103c:2a5e | Intel      | 82801GR/GDH (ICH7R/ICH7DH... | 2     | ahci       | ACD81F03F2 |
| 8086:2822 | 1025:0491 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | DD9CD8B1C7 |
| 8086:2822 | 1025:123c | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 6EEC9C83FA |
| 8086:2822 | 1028:01dd | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | C50923E1A9 |
| 8086:2822 | 1028:02da | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 4A526A31BD |
| 8086:2822 | 1028:04aa | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 2A4C870403 |
| 8086:2822 | 1028:06b9 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 2335EDDD94 |
| 8086:2822 | 1028:072b | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | F967633275 |
| 8086:2822 | 1028:07a1 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | DA78DC8E90 |
| 8086:2822 | 1028:07c5 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | ADD4A57D4C |
| 8086:2822 | 103c:1587 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | E74C8AB762 |
| 8086:2822 | 103c:1588 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 082313CDB6 |
| 8086:2822 | 1043:82d4 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 88092CA377 |
| 8086:2822 | 1043:84ef | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 2D0E168B00 |
| 8086:2822 | 1043:8600 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | AB917AE97E |
| 8086:2822 | 1043:872f | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 54BDDABC8F |
| 8086:2822 | 1849:2822 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 6CCB8DE60D |
| 8086:2826 | 103c:81c5 | Intel      | C600/X79 series chipset S... | 2     | ahci       | 46EA2E591E |
| 8086:2826 | 1043:84ef | Intel      | C600/X79 series chipset S... | 2     | ahci       | 2ED4BD5F01 |
| 8086:2827 | 103c:212b | Intel      | C610/X99 series chipset s... | 2     | ahci       | 6B7FF8ADA9 |
| 9005:028b | 9005:0200 | Adaptec    | Series 6 - 6G SAS/PCIe 2     | 2     | aacraid    | B7E74540B3 |
| 1000:005d | 8086:9380 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 1     | megarai... | 02F86A0A2A |
| 1000:005f | 1000:9340 | LSI Log... | MegaRAID SAS-3 3008 [Fury]   | 1     | megarai... | BB3B9B883B |
| 1000:005f | 1000:9343 | Broadco... | MegaRAID SAS-3 3008 [Fury]   | 1     | megarai... | 29B0070304 |
| 1000:0060 | 1000:1006 | LSI Log... | MegaRAID SAS 1078            | 1     | megarai... | 7FBD02378A |
| 1000:0072 | 1000:0072 | LSI Log... | SAS2008 PCI-Express Fusio... | 1     | mpt2sas    | 67BFE1B221 |
| 1000:0073 | 1014:03b1 | LSI Log... | MegaRAID SAS 2008 [Falcon]   | 1     | megarai... | B2F1A1E102 |
| 1000:0079 | 1000:9260 | LSI Log... | MegaRAID SAS 2108 [Libera... | 1     | megarai... | 093472BA51 |
| 1000:1960 | 1000:4523 | LSI Log... | MegaRAID                     | 1     | megarai... | A876D7FA9F |
| 1000:fury | 1000:9340 | LSI Log... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | BB3B9B883B |
| 1002:4380 | 1849:4381 | AMD        | SB600 Non-Raid-5 SATA        | 1     | ahci       | 4902AA6164 |
| 1002:4392 | 1002:4392 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 6363AAB98C |
| 1002:4392 | 1025:031f | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | E34D018E73 |
| 1002:4392 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 91F3BBB5A4 |
| 1002:4392 | 1462:7641 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | B6BAE789D0 |
| 1002:4392 | 1849:4392 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | BF175FAFA8 |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2576 |           | Intel      | 82865G/PE/P Processor to ... | 155   |            | E3D9D5BAE8 |
| 8086:d150 |           | Intel      | Core Processor QPI Link      | 116   |            | B39AC90CA0 |
| 8086:d151 |           | Intel      | Core Processor QPI Routin... | 116   |            | B39AC90CA0 |
| 8086:d158 |           | Intel      | Core Processor Miscellane... | 116   |            | B39AC90CA0 |
| 8086:1911 | 1458:5000 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 62    |            | 9A41C725F3 |
| 8086:d156 |           | Intel      | Core Processor Semaphore ... | 60    |            | B39AC90CA0 |
| 8086:d155 |           | Intel      | Core Processor System Man... | 59    |            | B39AC90CA0 |
| 8086:d157 |           | Intel      | Core Processor System Con... | 59    |            | B39AC90CA0 |
| 8086:d155 | 0043:0083 | Intel      | Core Processor System Man... | 57    |            | F048270617 |
| 8086:d156 | 0043:0083 | Intel      | Core Processor Semaphore ... | 57    |            | F048270617 |
| 8086:d157 | 0043:0083 | Intel      | Core Processor System Con... | 57    |            | F048270617 |
| 8086:2f6e |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | A8F2B39356 |
| 8086:2f6f |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | A8F2B39356 |
| 8086:2f88 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | A8F2B39356 |
| 8086:2f8a |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | A8F2B39356 |
| 8086:2fae |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | A8F2B39356 |
| 8086:2faf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | A8F2B39356 |
| 8086:2fb8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | A8F2B39356 |
| 8086:2fb9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | A8F2B39356 |
| 8086:2fba |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | A8F2B39356 |
| 8086:2fbb |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | A8F2B39356 |
| 8086:2fbe |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | A8F2B39356 |
| 8086:2fbf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | A8F2B39356 |
| 8086:2ff8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | A8F2B39356 |
| 8086:2ff9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | A8F2B39356 |
| 8086:2f1d | 8086:2f1d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    |            | A8F2B39356 |
| 8086:2f1e | 8086:2f1e | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    |            | A8F2B39356 |
| 8086:2f1f | 8086:2f1f | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    |            | A8F2B39356 |
| 8086:2f68 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    |            | A8F2B39356 |
| 8086:2f71 | 8086:2f71 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    |            | A8F2B39356 |
| 8086:2f98 | 8086:2f98 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    |            | A8F2B39356 |
| 8086:2f99 | 8086:2f99 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    |            | A8F2B39356 |
| 8086:2f9a | 8086:2f9a | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    |            | A8F2B39356 |
| 8086:2f9c | 8086:2f9c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    |            | A8F2B39356 |
| 8086:2fa0 | 8086:2fa0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    | sb_edac    | A8F2B39356 |
| 8086:2fa8 | 8086:2fa8 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    |            | A8F2B39356 |
| 8086:2faa | 8086:2faa | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    |            | A8F2B39356 |
| 8086:2fab | 8086:2fab | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    |            | A8F2B39356 |
| 8086:2fb0 | 8086:2fb0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    | hswep_u... | A8F2B39356 |
| 8086:2fb1 | 8086:2fb1 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    | hswep_u... | A8F2B39356 |
| 8086:2fb2 | 8086:2fb2 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    |            | A8F2B39356 |
| 8086:2fb3 | 8086:2fb3 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    |            | A8F2B39356 |
| 8086:2fc0 | 8086:2fc0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    | hswep_u... | A8F2B39356 |
| 8086:2fd0 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 46    | hswep_u... | A8F2B39356 |
| 8086:2fac | 8086:2fac | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 43    |            | A8F2B39356 |
| 8086:2fad | 8086:2fad | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 43    |            | A8F2B39356 |
| 8086:2fb4 | 8086:2fb4 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 43    | hswep_u... | A8F2B39356 |
| 8086:2fb5 | 8086:2fb5 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 43    | hswep_u... | A8F2B39356 |
| 8086:2fb6 | 8086:2fb6 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 43    |            | A8F2B39356 |
| 8086:2fb7 | 8086:2fb7 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 43    |            | A8F2B39356 |
| 8086:2f81 | 8086:2f81 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 41    |            | A8F2B39356 |
| 8086:2fe0 | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 41    |            | A8F2B39356 |
| 8086:2fe1 | 8086:2fe1 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 41    |            | A8F2B39356 |
| 8086:2fe2 | 8086:2fe2 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 41    |            | A8F2B39356 |
| 8086:2fe3 | 8086:2fe3 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 41    |            | A8F2B39356 |
| 8086:2ffc | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 41    |            | A8F2B39356 |
| 8086:2ffd | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 41    |            | A8F2B39356 |
| 8086:2ffe | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 41    |            | A8F2B39356 |
| 8086:2f28 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 36    |            | A8F2B39356 |
| 8086:2f29 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 36    |            | A8F2B39356 |
| 8086:2f2a |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 36    |            | A8F2B39356 |
| 8086:2fbc |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 33    |            | A8F2B39356 |
| 8086:2fbd |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 33    |            | A8F2B39356 |
| 8086:2fe4 | 8086:2fe4 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 32    |            | A8F2B39356 |
| 8086:2fe5 | 8086:2fe5 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 32    |            | A8F2B39356 |
| 8086:1911 | 1462:7996 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 21    |            | BD6DC70775 |
| 8086:3c28 | 1043:84ef | Intel      | Xeon E5/Core i7 Address M... | 20    |            | 1E7C5CF3CF |
| 8086:3c2a | 1043:84ef | Intel      | Xeon E5/Core i7 Control S... | 20    |            | 1E7C5CF3CF |
| 8086:3c45 | 1043:84ef | Intel      | Xeon E5/Core i7 Ring to Q... | 20    | snbep_u... | 1E7C5CF3CF |
| 8086:3c71 | 1043:84ef | Intel      | Xeon E5/Core i7 Integrate... | 20    |            | 1E7C5CF3CF |
| 8086:3c80 | 1043:84ef | Intel      | Xeon E5/Core i7 QPI Link 0   | 20    |            | 1E7C5CF3CF |
| 8086:3c83 | 1043:84ef | Intel      | Xeon E5/Core i7 QPI Link ... | 20    |            | 1E7C5CF3CF |
| 8086:3c84 | 1043:84ef | Intel      | Xeon E5/Core i7 QPI Link ... | 20    |            | 1E7C5CF3CF |
| 8086:3c90 | 1043:84ef | Intel      | Xeon E5/Core i7 QPI Link 1   | 20    |            | 1E7C5CF3CF |
| 8086:3c93 | 1043:84ef | Intel      | Xeon E5/Core i7 QPI Link ... | 20    |            | 1E7C5CF3CF |
| 8086:3c94 | 1043:84ef | Intel      | Xeon E5/Core i7 QPI Link ... | 20    |            | 1E7C5CF3CF |
| 8086:3ca0 | 1043:84ef | Intel      | Xeon E5/Core i7 Processor... | 20    | sb_edac    | 1E7C5CF3CF |
| 8086:3ca8 | 1043:84ef | Intel      | Xeon E5/Core i7 Integrate... | 20    | sb_edac    | 1E7C5CF3CF |
| 8086:3caa | 1043:84ef | Intel      | Xeon E5/Core i7 Integrate... | 20    |            | 1E7C5CF3CF |
| 8086:3cab | 1043:84ef | Intel      | Xeon E5/Core i7 Integrate... | 20    |            | 1E7C5CF3CF |
| 8086:3cac | 1043:84ef | Intel      | Xeon E5/Core i7 Integrate... | 20    |            | 1E7C5CF3CF |
| 8086:3cad | 1043:84ef | Intel      | Xeon E5/Core i7 Integrate... | 20    |            | 1E7C5CF3CF |
| 8086:3cae | 1043:84ef | Intel      | Xeon E5/Core i7 Integrate... | 20    |            | 1E7C5CF3CF |
| 8086:3cb0 | 1043:84ef | Intel      | Xeon E5/Core i7 Integrate... | 20    | snbep_u... | 1E7C5CF3CF |
| 8086:3cb1 | 1043:84ef | Intel      | Xeon E5/Core i7 Integrate... | 20    | snbep_u... | 1E7C5CF3CF |
| 8086:3cb2 | 1043:84ef | Intel      | Xeon E5/Core i7 Integrate... | 20    |            | 1E7C5CF3CF |
| 8086:3cb3 | 1043:84ef | Intel      | Xeon E5/Core i7 Integrate... | 20    |            | 1E7C5CF3CF |
| 8086:3cb4 | 1043:84ef | Intel      | Xeon E5/Core i7 Integrate... | 20    | snbep_u... | 1E7C5CF3CF |
| 8086:3cb5 | 1043:84ef | Intel      | Xeon E5/Core i7 Integrate... | 20    | snbep_u... | 1E7C5CF3CF |
| 8086:3cb6 | 1043:84ef | Intel      | Xeon E5/Core i7 Integrate... | 20    |            | 1E7C5CF3CF |
| 8086:3cb7 | 1043:84ef | Intel      | Xeon E5/Core i7 Integrate... | 20    |            | 1E7C5CF3CF |
| 8086:3cb8 | 1043:84ef | Intel      | Xeon E5/Core i7 DDRIO        | 20    |            | 1E7C5CF3CF |
| 8086:3cc0 | 1043:84ef | Intel      | Xeon E5/Core i7 Power Con... | 20    |            | 1E7C5CF3CF |
| 8086:3cc1 | 1043:84ef | Intel      | Xeon E5/Core i7 Power Con... | 20    |            | 1E7C5CF3CF |
| 8086:3cc2 | 1043:84ef | Intel      | Xeon E5/Core i7 Power Con... | 20    |            | 1E7C5CF3CF |
| 8086:3cd0 | 1043:84ef | Intel      | Xeon E5/Core i7 Power Con... | 20    |            | 1E7C5CF3CF |
| 8086:3ce0 | 1043:84ef | Intel      | Xeon E5/Core i7 Interrupt... | 20    |            | 1E7C5CF3CF |
| 8086:3ce3 | 1043:84ef | Intel      | Xeon E5/Core i7 Semaphore... | 20    |            | 1E7C5CF3CF |
| 8086:3ce4 | 1043:84ef | Intel      | Xeon E5/Core i7 R2PCIe       | 20    |            | 1E7C5CF3CF |
| 8086:3ce8 | 1043:84ef | Intel      | Xeon E5/Core i7 Unicast R... | 20    |            | 1E7C5CF3CF |

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
| 14f1:8852 | 14f1:8502 | Conexan... | CX23885 PCI Video and Aud... | 2     | cx23885    | 55AA6443CD |
| 14f1:8852 | 4254:9580 | Conexan... | CX23885 PCI Video and Aud... | 2     | cx23885    | 9057FD4986 |
| 14f1:8852 | d470:9022 | Conexan... | CX23885 PCI Video and Aud... | 2     | cx23885    | 78D2C49977 |
| 14f1:8880 | 0070:c108 | Conexan... | CX23887/8 PCIe Broadcast ... | 2     | cx23885    | 03A71DD3EB |
| 14f1:8880 | 1461:e139 | Conexan... | CX23887/8 PCIe Broadcast ... | 2     | cx23885    | 7999E0452A |
| 14f1:8880 | 5654:2390 | Conexan... | CX23887/8 PCIe Broadcast ... | 2     | cx23885    | AC49C705CB |
| 109e:0350 |           | Brooktree  | Bt848 Video Capture          | 1     | bttv       | A2E8F4444E |
| 109e:0351 |           | Brooktree  | Bt849A Video capture         | 1     | bttv       | 08D7917C8C |
| 109e:036e | 1047:f331 | Brooktree  | Bt878 Video Capture          | 1     | bttv       | 444FFBC8A6 |
| 109e:036e | 1461:0001 | Brooktree  | Bt878 Video Capture          | 1     | bttv       | E8072B6F3A |

### Unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:31a2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_i... | 55981AF24A |

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
| 1b21:1042 | 1043:8488 | ASMedia... | ASM1042 SuperSpeed USB Ho... | 513   | xhci_pci   | 6A60A724F9 |
| 8086:1c26 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 469   | ehci_hc... | 66A5EA0BE5 |
| 8086:1c2d | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 469   | ehci_hc... | 66A5EA0BE5 |
| 1002:4396 | 1002:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 468   | ehci_hc... | 5B95BD72C4 |
| 8086:27c8 | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 405   | uhci_hcd   | DD0FCDE6C7 |
| 8086:27c9 | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 405   | uhci_hcd   | DD0FCDE6C7 |
| 8086:27ca | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 405   | uhci_hcd   | DD0FCDE6C7 |
| 8086:27cb | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 405   | uhci_hcd   | DD0FCDE6C7 |
| 8086:27cc | 1458:5006 | Intel      | NM10/ICH7 Family USB2 EHC... | 405   | ehci_hc... | DD0FCDE6C7 |
| 1002:4397 | 1002:4397 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 371   | ohci_hc... | 6A60A724F9 |
| 8086:1e26 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 350   | ehci_hc... | 570B707FFB |
| 8086:1e2d | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 350   | ehci_hc... | 570B707FFB |
| 8086:1e31 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 348   | xhci_pci   | 570B707FFB |
| 1002:4396 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 339   | ehci_hc... | D569843A2D |
| 1002:4397 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 339   | ohci_hc... | D569843A2D |
| 1002:4398 | 1043:8389 | AMD        | SB7x0 USB OHCI1 Controller   | 338   | ohci_hc... | D569843A2D |
| 1002:4399 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 338   | ohci_hc... | D569843A2D |
| 1002:4399 | 1002:4399 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 334   | ohci_hc... | 6A60A724F9 |
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
| 1022:7807 | 1458:5004 | AMD        | FCH USB OHCI Controller      | 181   | ohci_hc... | 8226B90793 |
| 1022:7808 | 1458:5004 | AMD        | FCH USB EHCI Controller      | 181   | ehci_hc... | 8226B90793 |
| 8086:8c26 | 1458:5006 | Intel      | 8 Series/C220 Series Chip... | 179   | ehci_hc... | DD4DA32934 |
| 8086:8c2d | 1458:5006 | Intel      | 8 Series/C220 Series Chip... | 179   | ehci_hc... | DD4DA32934 |
| 8086:8c31 | 1458:5007 | Intel      | 8 Series/C220 Series Chip... | 179   | xhci_pci   | DD4DA32934 |
| 1022:7809 | 1458:5004 | AMD        | FCH USB OHCI Controller      | 178   | ohci_hc... | 8226B90793 |
| 1106:3038 | 1106:3038 | VIA Tec... | VT82xx/62xx UHCI USB 1.1 ... | 169   | uhci_hcd   | 85F1B83B30 |
| 1106:3104 | 1106:3104 | VIA Tec... | USB 2.0                      | 165   | ehci_hc... | 85F1B83B30 |
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
| 1002:4399 | 1002:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 130   | ohci_hc... | 5B95BD72C4 |
| 1022:43bb | 1b21:1142 | AMD        | 300 Series Chipset USB 3.... | 125   | xhci_hcd   | 518A8709C7 |
| 8086:1c26 | 1849:1c26 | Intel      | 6 Series/C200 Series Chip... | 117   | ehci_hc... | BDA40E6195 |
| 8086:1c2d | 1849:1c2d | Intel      | 6 Series/C200 Series Chip... | 117   | ehci_hc... | BDA40E6195 |
| 8086:3b34 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 117   | ehci_hc... | 05DC50AA11 |
| 8086:3b3c | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 117   | ehci_hc... | 05DC50AA11 |
| 1022:7807 | 1849:7807 | AMD        | FCH USB OHCI Controller      | 116   | ohci_hc... | 54FB4AE774 |
| 1022:7808 | 1849:7808 | AMD        | FCH USB EHCI Controller      | 116   | ehci_hc... | 54FB4AE774 |
| 1002:4398 | 1849:4398 | AMD        | SB7x0 USB OHCI1 Controller   | 112   | ohci_hc... | 666B4349AD |
| 8086:2934 | 1458:5004 | Intel      | 82801I (ICH9 Family) USB ... | 107   | uhci_hcd   | 54231260FF |
| 8086:2935 | 1458:5004 | Intel      | 82801I (ICH9 Family) USB ... | 107   | uhci_hcd   | 54231260FF |
| 8086:2936 | 1458:5004 | Intel      | 82801I (ICH9 Family) USB ... | 107   | uhci_hcd   | 54231260FF |
| 8086:2937 | 1458:5004 | Intel      | 82801I (ICH9 Family) USB ... | 107   | uhci_hcd   | 54231260FF |
| 8086:2938 | 1458:5004 | Intel      | 82801I (ICH9 Family) USB ... | 107   | uhci_hcd   | 54231260FF |
| 8086:2939 | 1458:5004 | Intel      | 82801I (ICH9 Family) USB ... | 107   | uhci_hcd   | 54231260FF |
| 8086:293a | 1458:5006 | Intel      | 82801I (ICH9 Family) USB2... | 107   | ehci_hc... | 54231260FF |
| 8086:293c | 1458:5006 | Intel      | 82801I (ICH9 Family) USB2... | 107   | ehci_hc... | 54231260FF |
| 1022:7809 | 1849:7809 | AMD        | FCH USB OHCI Controller      | 106   | ohci_hc... | 33CFE3D019 |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8d7c | 1043:8600 | Intel      | C610/X99 series chipset SPSR | 27    |            | A8F2B39356 |
| 8086:8d7c | 1028:0617 | Intel      | C610/X99 series chipset SPSR | 10    |            | 019BFC3983 |
| 8086:8d7c | 1458:7270 | Intel      | C610/X99 series chipset SPSR | 6     |            | DFC4A93CDF |
| 8086:8d7c | 1849:8d7c | Intel      | C610/X99 series chipset SPSR | 6     |            | 776B559B1F |
| 8086:2690 | 0000:0000 | Intel      | 631xESB/632xESB/3100 Chip... | 5     | pcieport   | A3AC5B74CF |
| 8086:3500 | 0000:0000 | Intel      | 6311ESB/6321ESB PCI Expre... | 5     | pcieport   | A3AC5B74CF |
| 8086:350c | 0000:0000 | Intel      | 6311ESB/6321ESB PCI Expre... | 5     | shpchp     | A3AC5B74CF |
| 8086:3510 | 0000:0000 | Intel      | 6311ESB/6321ESB PCI Expre... | 5     | pcieport   | A3AC5B74CF |
| 8086:3514 | 0000:0000 | Intel      | 6311ESB/6321ESB PCI Expre... | 5     | pcieport   | A3AC5B74CF |
| 1af2:a001 | 1af2:a001 | AVerMedia  | Live Gamer HD                | 4     |            | D5343B85FF |
| 8086:2692 | 0000:0000 | Intel      | 631xESB/632xESB/3100 Chip... | 4     | pcieport   | A3AC5B74CF |
| 8086:2694 | 0000:0000 | Intel      | 631xESB/632xESB/3100 Chip... | 4     | pcieport   | A3AC5B74CF |
| 8086:2696 | 0000:0000 | Intel      | 631xESB/632xESB/3100 Chip... | 4     | pcieport   | A3AC5B74CF |
| 8086:3518 | 0000:0000 | Intel      | 6311ESB/6321ESB PCI Expre... | 4     | pcieport   | A3AC5B74CF |
| 8086:5ad9 | 0000:0000 | Intel      | Celeron N3350/Pentium N42... | 4     | shpchp     | 6F498D9D7D |
| 8086:8d7c | 1462:7885 | Intel      | C610/X99 series chipset SPSR | 4     |            | 608FAFB692 |
| 8086:3a40 | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 3     | pcieport   | A4847544CA |
| 8086:3a42 | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 3     | pcieport   | A4847544CA |
| 8086:3a48 | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 3     | pcieport   | A4847544CA |
| 8086:8d7c | 1028:064c | Intel      | C610/X99 series chipset SPSR | 3     |            | E1BABF19AD |
| 8086:3a44 | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 2     | pcieport   | 354B501A79 |
| 8086:3a46 | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 2     | pcieport   | 354B501A79 |
| 8086:3a4a | 0000:0000 | Intel      | 82801JI (ICH10 Family) PC... | 2     | pcieport   | 354B501A79 |
| 8086:8d7c | 103c:212b | Intel      | C610/X99 series chipset SPSR | 2     |            | 6B7FF8ADA9 |
| 8086:8d7c | 103c:8030 | Intel      | C610/X99 series chipset SPSR | 2     |            | D9B1EC3C37 |
| 0000:0000 | 8005:0000 |            |                              | 1     |            | 77F07D2D69 |
| 0000:0002 | 1105:8300 |            |                              | 1     |            | 3859A12973 |
| 1000:fury | 1000:9343 | Broadco... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 29B0070304 |
| 106b:0041 |           | Apple      | K2 KeyLargo Mac/IO           | 1     | macio      | 52B4B037A1 |
| 106b:0043 |           | Apple      | K2 ATA/100                   | 1     | pata_pc... | 52B4B037A1 |
| 1131:7146 | ffff:ffff | Philips... | SAA7146                      | 1     |            | 4893225F50 |
| 1186:4300 | ffff:ffff | D-Link ... | DGE-528T Gigabit Ethernet... | 1     | r8169      | 5C0883B543 |
| 127a:2014 | 144e:2014 | Rockwel... | HSF 56k Data/Fax/Voice Modem | 1     |            | 97FF18DC78 |
| 13f6:0111 | fbff:fffd | C-Media... | CMI8738/CMI8768 PCI Audio    | 1     | snd_cmipci | 0528AB77BE |
| 144a:5101 | 144a:5101 | Adlink ... |                              | 1     |            | E0E966D6B4 |
| 1931:1011 | 1003:0001 | Option ... |                              | 1     |            | 28DFB478B7 |
| 1931:1011 | 1043:0001 | Option ... |                              | 1     |            | 28DFB478B7 |
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
| 8086:3a70 |           | Intel      | 82801JD/DO (ICH10 Family)... | 1     | pcieport   | FFDEB2B6E2 |
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
| 8086:8d7c | 1028:0618 | Intel      | C610/X99 series chipset SPSR | 1     |            | 76B60C0E5F |
| 8086:8d7c | 1028:0619 | Intel      | C610/X99 series chipset SPSR | 1     |            | ADB52FAE26 |
| 8086:8d7c | 1043:85f6 | Intel      | C610/X99 series chipset SPSR | 1     |            | 9EE9F662A8 |
| 8086:8d7c | 1462:7882 | Intel      | C610/X99 series chipset SPSR | 1     |            | 1E0208BF20 |
| 8086:8d7c | 15d9:0836 | Intel      | C610/X99 series chipset SPSR | 1     |            | 7756560112 |
| 8086:8d7c | 17aa:102f | Intel      | C610/X99 series chipset SPSR | 1     |            | BB3B9B883B |
| 8086:8d7c | 17aa:1030 | Intel      | C610/X99 series chipset SPSR | 1     |            | B89B8C9364 |
| 8086:8d7c | 17aa:1031 | Intel      | C610/X99 series chipset SPSR | 1     |            | 92262238C3 |
| 8086:a2ed | 0000:0000 | Intel      | 200 Series PCH PCI Expres... | 1     | pcieport   | 816A1797C5 |
| 8086:a33d |           | Intel      | Cannon Lake PCH PCI Expre... | 1     | pcieport   | 09F92379DE |
| mxic:0531 |           | Macroni... | MX987x5                      | 1     | tulip      | DF08E5122C |

