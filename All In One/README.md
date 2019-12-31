Most popular PCI devices in All In Ones
=======================================

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in All In Ones ](#pci-devices)
   * [ Bluetooth ](#bluetooth-pci)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Firewire controller ](#firewire-controller-pci)
   * [ Generic system peripheral ](#generic-system-peripheral-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Iommu ](#iommu-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Multimedia controller ](#multimedia-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Performance counters ](#performance-counters-pci)
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
   * [ Usb controller ](#usb-controller-pci)

PCI Devices
-----------

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bluetooth (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1814:3298 | 1a3b:2987 | Ralink     | RT3290 Bluetooth             | 1     |            | 1F5B5C1D86 |

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2448 |           | Intel      | 82801 Mobile PCI Bridge      | 24    |            | 8889AFD8F1 |
| 8086:2815 | 106b:00a0 | Intel      | 82801HM (ICH8M) LPC Inter... | 16    | lpc_ich    | 8889AFD8F1 |
| 8086:283f |           | Intel      | 82801H (ICH8 Family) PCI ... | 16    | shpchp     | 8889AFD8F1 |
| 8086:2845 |           | Intel      | 82801H (ICH8 Family) PCI ... | 16    | shpchp     | 8889AFD8F1 |
| 8086:2847 |           | Intel      | 82801H (ICH8 Family) PCI ... | 16    | shpchp     | 8889AFD8F1 |
| 8086:2849 |           | Intel      | 82801H (ICH8 Family) PCI ... | 16    | shpchp     | 8889AFD8F1 |
| 8086:2a00 | 106b:00a0 | Intel      | Mobile PM965/GM965/GL960 ... | 16    |            | 8889AFD8F1 |
| 8086:2a01 | 8086:0000 | Intel      | Mobile PM965/GM965/GL960 ... | 16    | shpchp     | 8889AFD8F1 |
| 1022:157b |           | AMD        | Family 15h (Models 60h-6f... | 13    |            | DE2A851C8F |
| 1022:157d |           | AMD        | Carrizo Audio Dummy Host ... | 13    |            | DE2A851C8F |
| 1022:1200 |           | AMD        | Family 10h Processor Hype... | 12    |            | F1E1BF19CC |
| 1022:1201 |           | AMD        | Family 10h Processor Addr... | 12    |            | F1E1BF19CC |
| 1022:1202 |           | AMD        | Family 10h Processor DRAM... | 12    |            | F1E1BF19CC |
| 1022:1203 |           | AMD        | Family 10h Processor Misc... | 12    | k10temp    | F1E1BF19CC |
| 1022:1204 |           | AMD        | Family 10h Processor Link... | 12    |            | F1E1BF19CC |
| 8086:1c10 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 12    | pcieport   | C88A6086FA |
| 8086:1c12 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 12    | pcieport   | C88A6086FA |
| 8086:1c14 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 12    | pcieport   | C88A6086FA |
| 8086:1c18 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 12    | pcieport   | C88A6086FA |
| 8086:1c44 | 8086:7270 | Intel      | Z68 Express Chipset LPC C... | 12    | lpc_ich    | C88A6086FA |
| 8086:2d01 | 8086:8086 | Intel      | Core Processor QuickPath ... | 12    |            | FF848E7FFB |
| 8086:2d10 | 8086:8086 | Intel      | Core Processor QPI Link 0    | 12    |            | FF848E7FFB |
| 8086:2d11 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 12    |            | FF848E7FFB |
| 8086:2d12 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 12    |            | FF848E7FFB |
| 8086:2d13 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 12    |            | FF848E7FFB |
| 1002:4384 |           | AMD        | SBx00 PCI to PCI Bridge      | 11    |            | F1E1BF19CC |
| 1022:15b0 |           | AMD        | Stoney HT Configuration      | 11    |            | DE2A851C8F |
| 1022:15b1 |           | AMD        | Stoney Address Maps          | 11    |            | DE2A851C8F |
| 1022:15b2 |           | AMD        | Stoney DRAM Configuration    | 11    |            | DE2A851C8F |
| 1022:15b3 |           | AMD        | Stoney Miscellaneous Conf... | 11    | k10temp    | DE2A851C8F |
| 1022:15b4 |           | AMD        | Stoney PM Configuration      | 11    | fam15h_... | DE2A851C8F |
| 1022:15b5 |           | AMD        | Stoney NB Performance Mon... | 11    |            | DE2A851C8F |
| 104c:823e |           | Texas I... | XIO2213A/B/XIO2221 PCI Ex... | 11    | shpchp     | D26C5DA01F |
| 8086:244e | 8086:7270 | Intel      | 82801 PCI Bridge             | 11    |            | CD3C0C4583 |
| 8086:2c61 | 8086:8086 | Intel      | Core Processor QuickPath ... | 11    |            | FF848E7FFB |
| 10de:0aab | 10de:cb79 | Nvidia     | MCP79 PCI Bridge             | 10    |            | 8361590CBD |
| 10de:0ac4 | 10de:0000 | Nvidia     | MCP79 PCI Express Bridge     | 10    | pcieport   | 8361590CBD |
| 10de:0ac6 | 10de:0000 | Nvidia     | MCP79 PCI Express Bridge     | 10    | pcieport   | 8361590CBD |
| 10de:0ac7 | 10de:0000 | Nvidia     | MCP79 PCI Express Bridge     | 10    | pcieport   | 8361590CBD |
| 8086:1513 |           | Intel      | CV82524 Thunderbolt Contr... | 10    | pcieport   | 561B991E16 |
| 8086:1547 | 2222:1111 | Intel      | DSL3510 Thunderbolt Contr... | 10    | shpchp     | F82FCD2051 |
| 1022:1530 |           | AMD        | Family 16h Processor Func... | 9     |            | 346458F274 |
| 1022:1531 |           | AMD        | Family 16h Processor Func... | 9     |            | 346458F274 |
| 1022:1532 |           | AMD        | Family 16h Processor Func... | 9     |            | 346458F274 |
| 1022:1533 |           | AMD        | Family 16h Processor Func... | 9     | k10temp    | 346458F274 |
| 1022:1534 |           | AMD        | Family 16h Processor Func... | 9     | fam15h_... | 346458F274 |
| 1022:1535 |           | AMD        | Family 16h Processor Func... | 9     |            | 346458F274 |
| 1022:1538 |           | AMD        | Family 16h Processor Func... | 9     |            | 346458F274 |
| 1022:1700 |           | AMD        | Family 12h/14h Processor ... | 9     |            | CD624C7BA5 |
| 1022:1701 |           | AMD        | Family 12h/14h Processor ... | 9     |            | CD624C7BA5 |
| 1022:1702 |           | AMD        | Family 12h/14h Processor ... | 9     |            | CD624C7BA5 |
| 1022:1703 |           | AMD        | Family 12h/14h Processor ... | 9     | k10temp    | CD624C7BA5 |
| 1022:1704 |           | AMD        | Family 12h/14h Processor ... | 9     |            | CD624C7BA5 |
| 1022:1716 |           | AMD        | Family 12h/14h Processor ... | 9     |            | CD624C7BA5 |
| 1022:1718 |           | AMD        | Family 12h/14h Processor ... | 9     |            | CD624C7BA5 |
| 1022:1719 |           | AMD        | Family 12h/14h Processor ... | 9     |            | CD624C7BA5 |
| 8086:1c10 | 17aa:365e | Intel      | 6 Series/C200 Series Chip... | 9     | shpchp     | 338C59EF86 |
| 8086:1c14 | 17aa:365e | Intel      | 6 Series/C200 Series Chip... | 9     | shpchp     | 338C59EF86 |
| 8086:1c16 | 17aa:365e | Intel      | 6 Series/C200 Series Chip... | 9     | shpchp     | 338C59EF86 |
| 8086:1c1a | 17aa:365e | Intel      | 6 Series/C200 Series Chip... | 9     | shpchp     | 338C59EF86 |
| 8086:1c5c | 17aa:365e | Intel      | H61 Express Chipset LPC C... | 9     | lpc_ich    | 338C59EF86 |
| 8086:8c10 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 9     | shpchp     | F82FCD2051 |
| 8086:8c14 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 9     | shpchp     | F82FCD2051 |
| 8086:8c16 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 9     | shpchp     | F82FCD2051 |
| 8086:8c18 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 9     | shpchp     | F82FCD2051 |
| 1022:156b |           | AMD        | Family 16h (Models 30h-3f... | 8     |            | 2D74D9A2EF |
| 1022:1580 |           | AMD        | Family 16h (Models 30h-3f... | 8     |            | 2D74D9A2EF |
| 1022:1581 |           | AMD        | Family 16h (Models 30h-3f... | 8     |            | 2D74D9A2EF |
| 1022:1582 |           | AMD        | Family 16h (Models 30h-3f... | 8     |            | 2D74D9A2EF |
| 1022:1583 |           | AMD        | Family 16h (Models 30h-3f... | 8     | k10temp    | 2D74D9A2EF |
| 1022:1584 |           | AMD        | Family 16h (Models 30h-3f... | 8     | fam15h_... | 2D74D9A2EF |
| 1022:1585 |           | AMD        | Family 16h (Models 30h-3f... | 8     |            | 2D74D9A2EF |
| 1022:43a0 | 1022:0000 | AMD        | Hudson PCI to PCI bridge ... | 8     | shpchp     | CD624C7BA5 |
| 1022:780f |           | AMD        | FCH PCI Bridge               | 8     |            | CD624C7BA5 |
| 8086:0100 | 103c:2ac5 | Intel      | 2nd Generation Core Proce... | 8     | snb_uncore | A5E0E95D2C |
| 8086:0100 | 106b:0000 | Intel      | 2nd Generation Core Proce... | 8     | snb_uncore | C88A6086FA |
| 8086:0101 | 106b:0000 | Intel      | Xeon E3-1200/2nd Generati... | 8     | pcieport   | C88A6086FA |
| 8086:0150 | 17aa:365e | Intel      | Xeon E3-1200 v2/3rd Gen C... | 8     | ie31200... | 338C59EF86 |
| 8086:1c10 | 103c:2ac5 | Intel      | 6 Series/C200 Series Chip... | 8     | shpchp     | A5E0E95D2C |
| 8086:1c12 | 17aa:365e | Intel      | 6 Series/C200 Series Chip... | 8     | shpchp     | 338C59EF86 |
| 8086:1c14 | 103c:2ac5 | Intel      | 6 Series/C200 Series Chip... | 8     | shpchp     | A5E0E95D2C |
| 8086:1c16 | 103c:2ac5 | Intel      | 6 Series/C200 Series Chip... | 8     | shpchp     | A5E0E95D2C |
| 8086:1c1a | 103c:2ac5 | Intel      | 6 Series/C200 Series Chip... | 8     | shpchp     | A5E0E95D2C |
| 8086:1c5c | 103c:2ac5 | Intel      | H61 Express Chipset LPC C... | 8     | lpc_ich    | A5E0E95D2C |
| 8086:27a0 | 8086:7270 | Intel      | Mobile 945GM/PM/GMS, 943/... | 8     |            | B24608A945 |
| 8086:27a1 | 8086:0000 | Intel      | Mobile 945GM/PM/GMS, 943/... | 8     | shpchp     | B24608A945 |
| 8086:27b9 | 8086:7270 | Intel      | 82801GBM (ICH7-M) LPC Int... | 8     | lpc_ich    | B24608A945 |
| 8086:27d0 |           | Intel      | NM10/ICH7 Family PCI Expr... | 8     | shpchp     | B24608A945 |
| 8086:27d2 |           | Intel      | NM10/ICH7 Family PCI Expr... | 8     | shpchp     | B24608A945 |
| 8086:3b02 | 8086:7270 | Intel      | P55 Chipset LPC Interface... | 8     | lpc_ich    | F0515A0217 |
| 8086:3b42 | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 8     | pcieport   | F0515A0217 |
| 8086:3b44 | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 8     | pcieport   | F0515A0217 |
| 8086:3b46 | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 8     | pcieport   | F0515A0217 |
| 10de:0a82 |           | Nvidia     | MCP79 Host Bridge            | 7     |            | 8361590CBD |
| 10de:0aa0 | 10de:0000 | Nvidia     | MCP79 PCI Express Bridge     | 7     | shpchp     | 8361590CBD |
| 10de:0aae | 10de:cb79 | Nvidia     | MCP79 LPC Bridge             | 7     |            | 8361590CBD |
| 8086:156d |           | Intel      | DSL5520 Thunderbolt 2 Bri... | 7     | pcieport   | 5984E1BBAC |
| 8086:5914 | 103c:84de | Intel      | Xeon E3-1200 v6/7th Gen C... | 6     | skl_uncore | 6B7FA4FF60 |
| 8086:8c44 | 8086:7270 | Intel      | Z87 Express LPC Controller   | 6     | lpc_ich    | F82FCD2051 |
| 8086:9d18 | 103c:84de | Intel      | Sunrise Point-LP PCI Expr... | 6     | pcieport   | 6B7FA4FF60 |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:5229 | 17aa:365e | Realtek... | RTS5229 PCI Express Card ... | 9     | rtsx_pci   | 338C59EF86 |
| 10ec:5209 | 103c:2ac5 | Realtek... | RTS5209 PCI Express Card ... | 8     | rtsx_pci   | A5E0E95D2C |
| 10ec:5209 | 1025:8020 | Realtek... | RTS5209 PCI Express Card ... | 5     | rtsx_pci   | 5EBFC68D96 |
| 10ec:5229 | 17aa:366c | Realtek... | RTS5229 PCI Express Card ... | 4     | rtsx_pci   | A922BB8973 |
| 10ec:5209 | 1028:0548 | Realtek... | RTS5209 PCI Express Card ... | 3     | rtsx_pci   | 229BA614EC |
| 10ec:5209 | 103c:2aed | Realtek... | RTS5209 PCI Express Card ... | 3     | rtsx_pci   | 00FCD6CB57 |
| 10ec:5229 | 17aa:3685 | Realtek... | RTS5229 PCI Express Card ... | 3     | rtsx_pci   | 647613F22B |
| 10ec:522a | 1028:0754 | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | 7CC5A36861 |
| 10ec:5289 | 17aa:3671 | Realtek... | RTL8411 PCI Express Card ... | 3     | rtsx_pci   | 906A62D75E |
| 10ec:5209 | 17aa:3623 | Realtek... | RTS5209 PCI Express Card ... | 2     | rtsx_pci   | B98E1F49EA |
| 10ec:5209 | 1b0a:0183 | Realtek... | RTS5209 PCI Express Card ... | 2     | rtsx_pci   | 78D39E18EF |
| 10ec:5229 | 1025:085f | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 90FF435FAD |
| 10ec:5229 | 103c:2179 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 7B6E93783B |
| 10ec:5229 | 103c:2afc | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 346458F274 |
| 10ec:5229 | 103c:81b7 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 447E6C6392 |
| 10ec:5229 | 17aa:367b | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 3EBFFF7DAD |
| 10ec:5229 | 17aa:36be | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 3A3B100E41 |
| 10ec:5249 | 103c:18e6 | Realtek... | RTS5249 PCI Express Card ... | 2     | rtsx_pci   | C0BDA7E63F |
| 10ec:524a | 1028:06d4 | Realtek... | RTS524A PCI Express Card ... | 2     | rtsx_pci   | 275E0EEAEF |
| 10ec:525a | 1028:075d | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx_pci   | 404A8B3A68 |
| 10ec:5209 | 1028:0543 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 0776B86016 |
| 10ec:5209 | 1028:054b | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 45F86E051C |
| 10ec:5209 | 1028:05db | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 3FEDAA45BD |
| 10ec:5209 | 1179:ff1e | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | A2613DB100 |
| 10ec:5209 | 17aa:3620 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 0C3E26BCE7 |
| 10ec:5209 | 17aa:3629 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 8F09E8179C |
| 10ec:5227 | 103c:2141 | Realtek... | RTS5227 PCI Express Card ... | 1     | rtsx_pci   | EAFEC5FB57 |
| 10ec:5227 | 103c:2b1c | Realtek... | RTS5227 PCI Express Card ... | 1     | rtsx_pci   | 3321732E8E |
| 10ec:5229 | 103c:18ea | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 101B838D0E |
| 10ec:5229 | 103c:2b0a | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 499EA7DFBB |
| 10ec:5229 | 103c:2b0d | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 3E13F8A157 |
| 10ec:5229 | 103c:2b13 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 8553F899D5 |
| 10ec:5229 | 103c:2b1f | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | F01E3C859D |
| 10ec:5229 | 103c:2b3e | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 8B96DC41BD |
| 10ec:5229 | 103c:81b9 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 15C46542B5 |
| 10ec:5229 | 103c:838b | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | AC62725ABE |
| 10ec:5229 | 17aa:30df | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 9374D57487 |
| 10ec:5229 | 17aa:30fc | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 70E8C27FFF |
| 10ec:5229 | 17aa:3113 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 7739219D01 |
| 10ec:5229 | 17aa:3686 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 5C64D33462 |
| 10ec:5229 | 17aa:368f | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 58DDD6F565 |
| 10ec:5229 | 17aa:369e | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 93F51B8717 |
| 10ec:5229 | 17aa:36a5 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | C486FF05F5 |
| 10ec:5229 | 17aa:36ab | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 89586A0608 |
| 10ec:5229 | 17aa:36bb | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | B790C5FA32 |
| 10ec:5229 | 17aa:36bc | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 06513D31C5 |
| 10ec:5229 | 17aa:36bd | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | E1331356C7 |
| 10ec:5229 | 17aa:36d0 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 9A305C10EC |
| 10ec:5229 | 17aa:36ed | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 8DFF428CAB |
| 10ec:522a | 1028:079e | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 2BF103DD36 |
| 10ec:522a | 1854:0308 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 530346DA62 |
| 10ec:524a | 103c:8058 | Realtek... | RTS524A PCI Express Card ... | 1     | rtsx_pci   | 2281502A3C |
| 10ec:524a | 103c:805e | Realtek... | RTS524A PCI Express Card ... | 1     | rtsx_pci   | FDD0A4E977 |
| 10ec:524a | 10ec:524a | Realtek... | RTS524A PCI Express Card ... | 1     | rtsx_pci   | D77183679A |
| 10ec:525a | 10ec:525a | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | 05D6B79D2F |
| 10ec:5287 | 1297:2053 | Realtek... | RTL8411B PCI Express Card... | 1     | rtsx_pci   | D2834ADB05 |
| 10ec:5289 | 17aa:3670 | Realtek... | RTL8411 PCI Express Card ... | 1     | rtsx_pci   | 46E2D4B676 |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0aa3 | 10de:cb79 | Nvidia     | MCP79 Co-processor           | 10    | nvidia     | 8361590CBD |
| 10de:0753 | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] Co-... | 5     |            | 4CA7976A88 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1c3a | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 12    | mei_me     | C88A6086FA |
| 8086:1c3a | 17aa:365e | Intel      | 6 Series/C200 Series Chip... | 9     | mei_me     | 338C59EF86 |
| 8086:8c3a | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 9     | mei_me     | F82FCD2051 |
| 8086:1c3a | 103c:2ac5 | Intel      | 6 Series/C200 Series Chip... | 8     | mei_me     | A5E0E95D2C |
| 8086:9d3a | 103c:84de | Intel      | Sunrise Point-LP CSME HEC... | 6     | mei_me     | 6B7FA4FF60 |
| 8086:1e3a | 144d:b091 | Intel      | 7 Series/C216 Chipset Fam... | 5     | mei_me     | 857C8BE5D0 |
| 8086:1c3a | 104d:907e | Intel      | 6 Series/C200 Series Chip... | 4     | mei_me     | 4A2DA5DD1B |
| 8086:1c3a | 17aa:366c | Intel      | 6 Series/C200 Series Chip... | 4     | mei_me     | A922BB8973 |
| 8086:5a9a | 17aa:36c4 | Intel      | Celeron N3350/Pentium N42... | 4     | mei_me     | 00A1738003 |
| 8086:9d3a | 8086:9d3a | Intel      | Sunrise Point-LP CSME HEC... | 4     | mei_me     | 5F28079AA4 |
| 8086:1c3a | 1028:0511 | Intel      | 6 Series/C200 Series Chip... | 3     | mei_me     | 8672A3F85D |
| 8086:1c3a | 103c:2aed | Intel      | 6 Series/C200 Series Chip... | 3     | mei_me     | 00FCD6CB57 |
| 8086:1c3a | 104d:9083 | Intel      | 6 Series/C200 Series Chip... | 3     | mei_me     | B4CF237F88 |
| 8086:1c3a | 8086:1c3a | Intel      | 6 Series/C200 Series Chip... | 3     | mei_me     | 19478FF625 |
| 8086:1e3a | 1028:0548 | Intel      | 7 Series/C216 Chipset Fam... | 3     | mei_me     | 229BA614EC |
| 8086:1e3a | 17aa:3671 | Intel      | 7 Series/C216 Chipset Fam... | 3     | mei_me     | 906A62D75E |
| 8086:1e3a | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 3     | mei_me     | CD3C0C4583 |
| 8086:2e24 | 104d:9060 | Intel      | 4 Series Chipset HECI Con... | 3     | mei_me     | 05CFF66AC2 |
| 8086:8c3a | 17aa:3685 | Intel      | 8 Series/C220 Series Chip... | 3     | mei_me     | 647613F22B |
| 8086:9d3a | 1025:1287 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | C861864ED7 |
| 8086:9d3a | 1028:0754 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | 7CC5A36861 |
| 8086:9d3a | 1028:0852 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | 5A27DEAF8A |
| 8086:a13a | 17aa:30ba | Intel      | 100 Series/C230 Series Ch... | 3     | mei_me     | 818DCABBD8 |
| 8086:a13a | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 3     | mei_me     | 5984E1BBAC |
| 8086:1c3a | 1019:0777 | Intel      | 6 Series/C200 Series Chip... | 2     | mei_me     | 1F5B5C1D86 |
| 8086:1c3a | 1025:0492 | Intel      | 6 Series/C200 Series Chip... | 2     | mei_me     | D44BEF08F5 |
| 8086:1c3a | 1025:0608 | Intel      | 6 Series/C200 Series Chip... | 2     | mei_me     | BEDE9EC674 |
| 8086:1c3a | 1025:063f | Intel      | 6 Series/C200 Series Chip... | 2     | mei_me     | 5EBFC68D96 |
| 8086:1c3a | 1025:0640 | Intel      | 6 Series/C200 Series Chip... | 2     | mei_me     | 22317B4B49 |
| 8086:1c3a | 103c:3395 | Intel      | 6 Series/C200 Series Chip... | 2     | mei_me     | 02F1FBC843 |
| 8086:1c3a | 1043:1c3a | Intel      | 6 Series/C200 Series Chip... | 2     | mei_me     | DB3BBECDD0 |
| 8086:1c3a | 104d:908e | Intel      | 6 Series/C200 Series Chip... | 2     | mei_me     | 59BB8EC907 |
| 8086:1c3a | 17aa:3623 | Intel      | 6 Series/C200 Series Chip... | 2     | mei_me     | B98E1F49EA |
| 8086:1e3a | 1025:0792 | Intel      | 7 Series/C216 Chipset Fam... | 2     | mei_me     | 3D1389215D |
| 8086:1e3a | 104d:9097 | Intel      | 7 Series/C216 Chipset Fam... | 2     | mei_me     | 7685534B8E |
| 8086:1e3a | 1462:b062 | Intel      | 7 Series/C216 Chipset Fam... | 2     | mei_me     | 0FC1178D7D |
| 8086:3b64 | 1025:0297 | Intel      | 5 Series/3400 Series Chip... | 2     | mei_me     | 1E17CF76B7 |
| 8086:5a9a | 103c:8304 | Intel      | Celeron N3350/Pentium N42... | 2     | mei_me     | A63E8373C4 |
| 8086:8c3a | 103c:18e6 | Intel      | 8 Series/C220 Series Chip... | 2     | mei_me     | C0BDA7E63F |
| 8086:8c3a | 103c:2179 | Intel      | 8 Series/C220 Series Chip... | 2     | mei_me     | 7B6E93783B |
| 8086:8c3a | 1462:ae67 | Intel      | 8 Series/C220 Series Chip... | 2     | mei_me     | 881CDBC376 |
| 8086:8c3a | 17aa:367b | Intel      | 8 Series/C220 Series Chip... | 2     | mei_me     | 3EBFFF7DAD |
| 8086:8c3a | 1b0a:0183 | Intel      | 8 Series/C220 Series Chip... | 2     | mei_me     | 78D39E18EF |
| 8086:8c3a | 1b0a:0188 | Intel      | 8 Series/C220 Series Chip... | 2     | mei_me     | A94F1201C4 |
| 8086:9cba | 8086:7270 | Intel      | Wildcat Point-LP MEI Cont... | 2     | mei_me     | 906BCD4AC8 |
| 8086:a13a | 1028:06d4 | Intel      | 100 Series/C230 Series Ch... | 2     | mei_me     | 275E0EEAEF |
| 8086:a13a | 1028:075d | Intel      | 100 Series/C230 Series Ch... | 2     | mei_me     | 404A8B3A68 |
| 8086:a13a | 8086:a13a | Intel      | 100 Series/C230 Series Ch... | 2     | mei_me     | 4F5252C592 |
| 8086:a360 | 103c:84ee | Intel      | Cannon Lake PCH HECI Cont... | 2     | mei_me     | 5D5C8FEFBA |
| 8086:02e0 | 1028:0954 | Intel      | Comet Lake Management Eng... | 1     |            | 8740133E10 |
| 8086:1c3a | 1025:0618 | Intel      | 6 Series/C200 Series Chip... | 1     | mei_me     | 7CFCB49FC2 |
| 8086:1c3a | 103c:18dd | Intel      | 6 Series/C200 Series Chip... | 1     | mei_me     | 73E763ADFA |
| 8086:1c3a | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1     | mei_me     | 48A3B0ECA9 |
| 8086:1c3a | 1179:ff1e | Intel      | 6 Series/C200 Series Chip... | 1     | mei_me     | A2613DB100 |
| 8086:1c3a | 17aa:3620 | Intel      | 6 Series/C200 Series Chip... | 1     | mei_me     | 0C3E26BCE7 |
| 8086:1e3a | 1028:0543 | Intel      | 7 Series/C216 Chipset Fam... | 1     | mei_me     | 0776B86016 |
| 8086:1e3a | 1028:05c2 | Intel      | 7 Series/C216 Chipset Fam... | 1     | mei_me     | EFDACF8C18 |
| 8086:1e3a | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 1     | mei_me     | EB1E63578D |
| 8086:1e3a | 1462:a953 | Intel      | 7 Series/C216 Chipset Fam... | 1     | mei_me     | 1EAD53F6C2 |
| 8086:1e3a | 1854:f004 | Intel      | 7 Series/C216 Chipset Fam... | 1     | mei_me     | 81CF385125 |
| 8086:2e14 | 103c:1489 | Intel      | 4 Series Chipset HECI Con... | 1     | mei_me     | A6305AD3A0 |
| 8086:319a | 1043:1e80 | Intel      | Celeron/Pentium Silver Pr... | 1     | mei_me     | 5F116B16F1 |
| 8086:319a | 1043:1ea0 | Intel      | Celeron/Pentium Silver Pr... | 1     | mei_me     | 7F0055E131 |
| 8086:319a | 17aa:36ed | Intel      | Celeron/Pentium Silver Pr... | 1     | mei_me     | 8DFF428CAB |
| 8086:319a | 1854:0308 | Intel      | Celeron/Pentium Silver Pr... | 1     | mei_me     | 530346DA62 |
| 8086:319a | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | mei_me     | B4AB9671B3 |
| 8086:3b64 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 1     | mei_me     | 7F0F347502 |
| 8086:3b64 | 1462:ae31 | Intel      | 5 Series/3400 Series Chip... | 1     | mei_me     | CBD910EA06 |
| 8086:3b64 | 17aa:306a | Intel      | 5 Series/3400 Series Chip... | 1     | mei_me     | F15D263E67 |
| 8086:3b64 | 17aa:3608 | Intel      | 5 Series/3400 Series Chip... | 1     | mei_me     | EA55AE13AC |
| 8086:5a9a |           | Intel      | Celeron N3350/Pentium N42... | 1     | mei_me     | E6838B3DD6 |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | mei_me     | 8A67730AF4 |
| 8086:8c3a | 1025:0863 | Intel      | 8 Series/C220 Series Chip... | 1     | mei_me     | 3370E1020B |
| 8086:8c3a | 1028:05db | Intel      | 8 Series/C220 Series Chip... | 1     | mei_me     | 3FEDAA45BD |
| 8086:8c3a | 1028:0623 | Intel      | 8 Series/C220 Series Chip... | 1     |            | 29D0AD2441 |
| 8086:8c3a | 1028:0626 | Intel      | 8 Series/C220 Series Chip... | 1     | mei_me     | C1A91BB2D3 |
| 8086:8c3a | 103c:18ea | Intel      | 8 Series/C220 Series Chip... | 1     | mei_me     | 101B838D0E |
| 8086:8c3a | 103c:2b0d | Intel      | 8 Series/C220 Series Chip... | 1     | mei_me     | 3E13F8A157 |
| 8086:8c3a | 103c:2b1c | Intel      | 8 Series/C220 Series Chip... | 1     | mei_me     | 3321732E8E |
| 8086:8c3a | 1462:ac95 | Intel      | 8 Series/C220 Series Chip... | 1     | mei_me     | 70DEC15340 |
| 8086:8c3a | 17aa:3686 | Intel      | 8 Series/C220 Series Chip... | 1     | mei_me     | 5C64D33462 |
| 8086:8cba | 8086:7270 | Intel      | 9 Series Chipset Family M... | 1     | mei_me     | 92012F60BF |
| 8086:9c3a | 103c:2141 | Intel      | 8 Series HECI #0             | 1     | mei_me     | EAFEC5FB57 |
| 8086:9c3a | 17aa:369e | Intel      | 8 Series HECI #0             | 1     | mei_me     | 93F51B8717 |
| 8086:9c3a | 8086:7270 | Intel      | 8 Series HECI #0             | 1     | mei_me     | 99683A7632 |
| 8086:9cba | 1025:105c | Intel      | Wildcat Point-LP MEI Cont... | 1     | mei_me     | E7395D0EE2 |
| 8086:9cba | 1854:0218 | Intel      | Wildcat Point-LP MEI Cont... | 1     | mei_me     | C95062D4FF |
| 8086:9cba | 1bc6:01ac | Intel      | Wildcat Point-LP MEI Cont... | 1     | mei_me     | D40CB39503 |
| 8086:9d3a | 1025:1130 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | D33236ABB3 |
| 8086:9d3a | 1043:12a1 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 689F9F13AF |
| 8086:9d3a | 144d:c133 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 39977FE582 |
| 8086:9d3a | 17aa:3630 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 9374D57487 |
| 8086:9d3a | 8086:7270 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 39AFD1D7B1 |
| 8086:a13a | 1025:1063 | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | 057A5601FF |
| 8086:a13a | 103c:2b3e | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | 8B96DC41BD |
| 8086:a13a | 103c:8058 | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | 2281502A3C |
| 8086:a13a | 103c:805e | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | FDD0A4E977 |
| 8086:a13a | 103c:81b7 | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | 9FFCD25291 |
| 8086:a13a | 1071:0752 | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | 3BDFB07582 |
| 8086:a13a | 1462:aac1 | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | D77183679A |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1537 | 103c:8245 | AMD        | Kabini/Mullins PSP-Platfo... | 4     | ccp        | 2D74D9A2EF |
| 1022:1537 | 1022:1537 | AMD        | Kabini/Mullins PSP-Platfo... | 3     | ccp        | 89586A0608 |
| 8086:0f18 |           | Intel      | Atom Processor Z36xxx/Z37... | 3     | mei_txe    | E6BCDB1E4D |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 2     |            | DE2A851C8F |
| 1022:1578 | 1028:07e3 | AMD        | Carrizo Platform Security... | 2     |            | 4EB59BF315 |
| 1022:1578 | 103c:8381 | AMD        | Carrizo Platform Security... | 2     |            | 83034BC0E9 |
| 1022:1578 | 17aa:36be | AMD        | Carrizo Platform Security... | 2     |            | 3A3B100E41 |
| 8086:0f18 | 1025:085f | Intel      | Atom Processor Z36xxx/Z37... | 2     | mei_txe    | 90FF435FAD |
| 8086:0f18 | 17aa:3695 | Intel      | Atom Processor Z36xxx/Z37... | 2     | mei_txe    | 08BB09B100 |
| 8086:0f18 | 17aa:36a8 | Intel      | Atom Processor Z36xxx/Z37... | 2     | mei_txe    | 5F6FF0EBDA |
| 8086:0f18 | 1854:0200 | Intel      | Atom Processor Z36xxx/Z37... | 2     | mei_txe    | 2128A4CD93 |
| 8086:2298 | 1025:098f | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | 350CC83AC7 |
| 8086:2298 | 1025:1065 | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | 21CA50C386 |
| 8086:2298 | 17aa:30dd | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | C64BB03524 |
| 8086:2298 | 17aa:3637 | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | 91FFB55E1F |
| 1022:1537 | 103c:2b3b | AMD        | Kabini/Mullins PSP-Platfo... | 1     | ccp        | A772887752 |
| 1022:1578 | 1028:0855 | AMD        | Carrizo Platform Security... | 1     |            | DACA9432F8 |
| 1022:1578 | 103c:81b9 | AMD        | Carrizo Platform Security... | 1     |            | 15C46542B5 |
| 1022:1578 | 103c:8430 | AMD        | Carrizo Platform Security... | 1     |            | 2B0CDC9F2B |
| 1022:1578 | 17aa:36bd | AMD        | Carrizo Platform Security... | 1     |            | E1331356C7 |
| 1022:1578 | 17aa:36ec | AMD        | Carrizo Platform Security... | 1     |            | C586E918F9 |
| 1022:15df | 17aa:36f5 | AMD        | Family 17h (Models 10h-1f... | 1     |            | 7E41940C9C |
| 8086:0f18 | 17aa:368a | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | F14A7F7311 |
| 8086:0f18 | 1b0a:01a5 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | E745E03926 |
| 8086:2298 |           | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | A2CB18D2E5 |
| 8086:2298 | 1028:06cc | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | E534D33394 |
| 8086:2298 | 103c:81bb | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | 0F82F36E74 |
| 8086:2298 | 1297:2053 | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | D2834ADB05 |
| 8086:2298 | 8086:2298 | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | DA374C3C83 |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 11c1:5901 | 11c1:5900 | LSI        | FW643 [TrueFire] PCIe 139... | 35    | firewir... | 8889AFD8F1 |
| 104c:823f |           | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 11    | firewir... | D26C5DA01F |
| 11c1:5811 | 11c1:5811 | LSI        | FW322/323 [TrueFire] 1394... | 7     | firewir... | B24608A945 |
| 1180:e832 | 104d:907e | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 4     | firewir... | 4A2DA5DD1B |
| 1180:e832 | 104d:9060 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 3     | firewir... | 05CFF66AC2 |
| 197b:2380 | 17aa:3602 | JMicron... | IEEE 1394 Host Controller    | 3     | firewir... | 55C2F8E26B |
| 1180:e832 | 104d:908e | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 2     | firewir... | 59BB8EC907 |
| 1180:e832 | 104d:9097 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 2     | firewir... | 7685534B8E |
| 104c:8025 |           | Texas I... | TSB82AA2 IEEE-1394b Link ... | 1     | firewir... | 0DF85531E1 |
| 1106:3401 | 17aa:3608 | VIA Tec... | FireWire (IEEE 1394)         | 1     | firewir... | EA55AE13AC |
| 1180:0552 | 1033:886f | Ricoh      | R5C552 IEEE 1394 Controller  | 1     | firewir... | 86771347FB |
| 197b:2380 | 103c:1489 | JMicron... | IEEE 1394 Host Controller    | 1     | firewir... | A6305AD3A0 |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1577 | 1022:1577 | AMD        | Family 15h (Models 60h-6f... | 4     |            | DE2A851C8F |
| 1022:1423 | 17aa:368f | AMD        | Family 15h (Models 30h-3f... | 1     |            | 58DDD6F565 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:9583 | 106b:0083 | AMD        | RV630/M76 [Mobility Radeo... | 13    | radeon     | 8889AFD8F1 |
| 8086:0102 | 103c:2ac5 | Intel      | 2nd Generation Core Proce... | 8     | i915       | A5E0E95D2C |
| 8086:0102 | 106b:0000 | Intel      | 2nd Generation Core Proce... | 8     | i915       | C88A6086FA |
| 1002:71c5 | 106b:0080 | AMD        | RV530/M56-P [Mobility Rad... | 7     | radeon     | B24608A945 |
| 1002:6740 | 106b:6740 | AMD        | Whistler [Radeon HD 6730M... | 6     | radeon     | C88A6086FA |
| 8086:5917 | 103c:84de | Intel      | UHD Graphics 620             | 6     | i915       | 6B7FA4FF60 |
| 10de:0dea | 17aa:365e | Nvidia     | GF108M [GeForce 610M]        | 5     | nouveau    | BAA91679D8 |
| 1002:6720 | 106b:0b00 | AMD        | Blackcomb [Radeon HD 6970... | 4     | radeon     | 561B991E16 |
| 1002:6840 | 144d:b091 | AMD        | Thames [Radeon HD 7500M/7... | 4     | radeon     | 16D6FCA3F1 |
| 10de:0867 | 106b:00ad | Nvidia     | C79 [GeForce 9400]           | 4     | nouveau    | 8361590CBD |
| 10de:0de5 | 174b:7162 | Nvidia     | GF108 [GeForce GT 530]       | 4     | nouveau    | 22317B4B49 |
| 10de:0dea | 17aa:366c | Nvidia     | GF108M [GeForce 610M]        | 4     | nouveau    | A922BB8973 |
| 10de:0df4 | 104d:907e | Nvidia     | GF108M [GeForce GT 540M]     | 4     | nouveau    | 4A2DA5DD1B |
| 8086:0102 | 8086:2010 | Intel      | 2nd Generation Core Proce... | 4     | i915       | 8515B44489 |
| 8086:0152 | 17aa:365e | Intel      | Xeon E3-1200 v2/3rd Gen C... | 4     | i915       | 338C59EF86 |
| 1002:944a | 106b:00b5 | AMD        | RV770/M98L [Mobility Rade... | 3     | radeon     | 63741AC6DC |
| 1002:9488 | 106b:00b6 | AMD        | RV730/M96-XT [Mobility Ra... | 3     |            | F0515A0217 |
| 1002:94c8 | 106b:0084 | AMD        | RV610/M74 [Mobility Radeo... | 3     | radeon     | 44E71D3F5A |
| 1002:9850 | 103c:8245 | AMD        | Mullins [Radeon R3 Graphics] | 3     | radeon     | 2D74D9A2EF |
| 10de:0869 | 106b:00b4 | Nvidia     | MCP7A [GeForce 9400]         | 3     | nouveau    | D26C5DA01F |
| 10de:174e | 1028:0852 | Nvidia     | GM108M [GeForce MX110]       | 3     | nouveau    | 5A27DEAF8A |
| 8086:0102 | 1028:0511 | Intel      | 2nd Generation Core Proce... | 3     | i915       | 8672A3F85D |
| 8086:0152 | 103c:2aed | Intel      | Xeon E3-1200 v2/3rd Gen C... | 3     | i915       | 00FCD6CB57 |
| 8086:0d22 | 106b:0122 | Intel      | Crystal Well Integrated I... | 3     | i915       | 3FFA6AA435 |
| 8086:0f31 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 3     | i915       | E6BCDB1E4D |
| 8086:1912 | 17aa:30ba | Intel      | HD Graphics 530              | 3     | i915       | 818DCABBD8 |
| 8086:5916 | 1028:0754 | Intel      | HD Graphics 620              | 3     | i915       | 7CC5A36861 |
| 8086:5916 | 1028:0852 | Intel      | HD Graphics 620              | 3     | i915       | 5A27DEAF8A |
| 8086:5917 | 1025:1287 | Intel      | UHD Graphics 620             | 3     | i915       | C861864ED7 |
| 8086:5a85 | 17aa:36c4 | Intel      | HD Graphics 500              | 3     | i915       | 00A1738003 |
| 8086:a001 | 17aa:3610 | Intel      | Atom Processor D4xx/D5xx/... | 3     | i915       | E98AA97F27 |
| 1002:6640 | 106b:014b | AMD        | Saturn XT [FirePro M6100]    | 2     | radeon     | 48BADA4AFA |
| 1002:6660 | 1025:0792 | AMD        | Sun XT [Radeon HD 8670A/8... | 2     | radeon     | 3D1389215D |
| 1002:6741 | 106b:6741 | AMD        | Whistler [Radeon HD 6630M... | 2     | radeon     | 8515B44489 |
| 1002:6751 | 1028:0548 | AMD        | Turks [Radeon HD 7650A/76... | 2     | radeon     | 98B3AC895B |
| 1002:6760 | 104d:9087 | AMD        | Seymour [Radeon HD 6400M/... | 2     | radeon     | B4CF237F88 |
| 1002:68a1 | 106b:00cc | AMD        | Broadway PRO [Mobility Ra... | 2     | radeon     | 6149AFDA8F |
| 1002:68e0 | 1043:8430 | AMD        | Park [Mobility Radeon HD ... | 2     | radeon     | F1E1BF19CC |
| 1002:68e4 | 1bfd:000a | AMD        | Robson CE [Radeon HD 6370... | 2     | radeon     | 09FE5E4566 |
| 1002:68f9 | 17aa:3602 | AMD        | Cedar [Radeon HD 5000/600... | 2     | radeon     | 60AE7E3358 |
| 1002:9553 | 1025:0266 | AMD        | RV710/M92 [Mobility Radeo... | 2     | radeon     | 57AD94D04A |
| 1002:9830 | 103c:2afc | AMD        | Kabini [Radeon HD 8400 / ... | 2     | radeon     | 346458F274 |
| 1002:98e4 | 103c:8381 | AMD        | Stoney [Radeon R2/R3/R4/R... | 2     | amdgpu     | 83034BC0E9 |
| 1002:98e4 | 17aa:36be | AMD        | Stoney [Radeon R2/R3/R4/R... | 2     | amdgpu     | 3A3B100E41 |
| 10de:0655 | 106b:0633 | Nvidia     | G96 [GeForce GT 120 Mac E... | 2     | nouveau    | F633253277 |
| 10de:0a74 | 104d:9060 | Nvidia     | GT218M [GeForce G210M]       | 2     | nouveau    | 05CFF66AC2 |
| 10de:0de9 | 1043:8518 | Nvidia     | GF108M [GeForce GT 620M/6... | 2     | nouveau    | DB3BBECDD0 |
| 10de:0df4 | 104d:908e | Nvidia     | GF108M [GeForce GT 540M]     | 2     | nouveau    | 59BB8EC907 |
| 10de:0df5 | 1028:0511 | Nvidia     | GF108M [GeForce GT 525M]     | 2     | nouveau    | 8672A3F85D |
| 10de:0fea | 106b:011f | Nvidia     | GK107M [GeForce GT 755M M... | 2     | nouveau    | C6F2E8BC12 |
| 10de:119d | 106b:0120 | Nvidia     | GK104M [GeForce GTX 775M ... | 2     | nvidia     | F82FCD2051 |
| 10de:1340 | 1b0a:90d8 | Nvidia     | GM108M [GeForce 830M]        | 2     | nouveau    | 78D39E18EF |
| 10de:1346 | 1028:06d4 | Nvidia     | GM108M [GeForce 930M]        | 2     | nouveau    | 275E0EEAEF |
| 10de:134e | 103c:81b7 | Nvidia     | GM108M [GeForce 930MX]       | 2     | nouveau    | 447E6C6392 |
| 10de:134f | 1028:0754 | Nvidia     | GM108M [GeForce 920MX]       | 2     | nouveau    | 30D175ED83 |
| 10de:1392 | 1462:ae67 | Nvidia     | GM107M [GeForce GTX 860M]    | 2     | nouveau    | 881CDBC376 |
| 10de:1c8d | 103c:84ee | Nvidia     | GP107M [GeForce GTX 1050 ... | 2     | nvidia     | 5D5C8FEFBA |
| 8086:0102 | 1025:063f | Intel      | 2nd Generation Core Proce... | 2     | i915       | 5EBFC68D96 |
| 8086:0102 | 1025:0640 | Intel      | 2nd Generation Core Proce... | 2     | i915       | 22317B4B49 |
| 8086:0102 | 103c:3395 | Intel      | 2nd Generation Core Proce... | 2     | i915       | 02F1FBC843 |
| 8086:0106 | 17aa:3671 | Intel      | 2nd Generation Core Proce... | 2     | i915       | 906A62D75E |
| 8086:0116 | 104d:9087 | Intel      | 2nd Generation Core Proce... | 2     | i915       | B4CF237F88 |
| 8086:0152 | 1028:0548 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 2     | i915       | 98B3AC895B |
| 8086:0166 | 1025:0792 | Intel      | 3rd Gen Core processor Gr... | 2     | i915       | 3D1389215D |
| 8086:0412 | 17aa:367b | Intel      | Xeon E3-1200 v3/4th Gen C... | 2     | i915       | 3EBFFF7DAD |
| 8086:0416 | 1462:ae67 | Intel      | 4th Gen Core Processor In... | 2     | i915       | 881CDBC376 |
| 8086:041e | 17aa:3685 | Intel      | 4th Generation Core Proce... | 2     | i915       | A0BEE3E8DE |
| 8086:041e | 1b0a:0183 | Intel      | 4th Generation Core Proce... | 2     | i915       | 78D39E18EF |
| 8086:0f31 | 1025:085f | Intel      | Atom Processor Z36xxx/Z37... | 2     | i915       | 90FF435FAD |
| 8086:0f31 | 17aa:3695 | Intel      | Atom Processor Z36xxx/Z37... | 2     | i915       | 08BB09B100 |
| 8086:0f31 | 17aa:36a8 | Intel      | Atom Processor Z36xxx/Z37... | 2     | i915       | 5F6FF0EBDA |
| 8086:0f31 | 1854:0200 | Intel      | Atom Processor Z36xxx/Z37... | 2     | i915       | 2128A4CD93 |
| 8086:1626 | 106b:0146 | Intel      | HD Graphics 6000             | 2     | i915       | 906BCD4AC8 |
| 8086:162b | 1bc6:01ac | Intel      | Iris Graphics 6100           | 2     | i915       | 2146FDE0CF |
| 8086:1912 | 1028:06d4 | Intel      | HD Graphics 530              | 2     | i915       | 275E0EEAEF |
| 8086:1912 | 103c:81b7 | Intel      | HD Graphics 530              | 2     | i915       | 447E6C6392 |
| 8086:22b1 | 1025:098f | Intel      | Atom/Celeron/Pentium Proc... | 2     | i915       | 350CC83AC7 |
| 8086:22b1 | 1025:1065 | Intel      | Atom/Celeron/Pentium Proc... | 2     | i915       | 21CA50C386 |
| 8086:22b1 | 17aa:30dd | Intel      | Atom/Celeron/Pentium Proc... | 2     | i915       | C64BB03524 |
| 8086:22b1 | 17aa:3637 | Intel      | Atom/Celeron/Pentium Proc... | 2     | i915       | 91FFB55E1F |
| 8086:22b1 | 8086:22b1 | Intel      | Atom/Celeron/Pentium Proc... | 2     | i915       | DA374C3C83 |
| 8086:2a42 | 1025:0275 | Intel      | Mobile 4 Series Chipset I... | 2     | i915       | 19FBB5D44C |
| 8086:2a43 | 1025:0275 | Intel      | Mobile 4 Series Chipset I... | 2     |            | 19FBB5D44C |
| 8086:3e92 | 103c:84ee | Intel      | UHD Graphics 630 (Desktop)   | 2     | i915       | 5D5C8FEFBA |
| 1002:130f | 17aa:368f | AMD        | Kaveri [Radeon R7 Graphics]  | 1     | amdgpu     | 58DDD6F565 |
| 1002:15dd | 17aa:36f5 | AMD        | Raven Ridge [Radeon Vega ... | 1     |            | 7E41940C9C |
| 1002:6600 | 103c:2b3e | AMD        | Mars [Radeon HD 8670A/867... | 1     | radeon     | 8B96DC41BD |
| 1002:6660 | 1028:05db | AMD        | Sun XT [Radeon HD 8670A/8... | 1     |            | 3FEDAA45BD |
| 1002:6663 | 17aa:367b | AMD        | Sun PRO [Radeon HD 8570A/... | 1     | radeon     | F1FDC67882 |
| 1002:6665 | 103c:2b1f | AMD        | Jet PRO [Radeon R5 M230 /... | 1     | radeon     | F01E3C859D |
| 1002:6743 | 1854:f004 | AMD        | Whistler [Radeon E6760]      | 1     | radeon     | 81CF385125 |
| 1002:6759 | 1462:2503 | AMD        | Turks PRO [Radeon HD 6570... | 1     | radeon     | BD0C627D01 |
| 1002:6759 | 174b:e181 | AMD        | Turks PRO [Radeon HD 6570... | 1     | radeon     | 4CA7976A88 |
| 1002:6770 | 17aa:3623 | AMD        | Caicos [Radeon HD 6450A/7... | 1     | radeon     | B98E1F49EA |
| 1002:6778 | 174b:e145 | AMD        | Caicos XT [Radeon HD 7470... | 1     | radeon     | 0BB1CDF16A |
| 1002:6779 | 174b:e180 | AMD        | Caicos [Radeon HD 6450/74... | 1     | radeon     | AD16F12938 |
| 1002:679a | 148c:3000 | AMD        | Tahiti PRO [Radeon HD 795... | 1     | radeon     | EB1E63578D |
| 1002:67e8 | 1028:075d | AMD        | Baffin [Radeon Pro WX 413... | 1     | amdgpu     | 404A8B3A68 |
| 1002:67ff | 1028:07e3 | AMD        | Baffin [Radeon RX 550 640... | 1     | amdgpu     | 4EB59BF315 |
| 1002:6819 | 106b:014e | AMD        | Pitcairn PRO [Radeon HD 7... | 1     | radeon     | 5984E1BBAC |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1577 | 1028:07e3 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 4EB59BF315 |
| 1022:1577 | 1028:0855 | AMD        | Family 15h (Models 60h-6f... | 1     |            | DACA9432F8 |
| 1022:1577 | 17aa:36c6 | AMD        | Family 15h (Models 60h-6f... | 1     |            | 5DA9F63B49 |
| 1022:1577 | 17aa:36ec | AMD        | Family 15h (Models 60h-6f... | 1     |            | C586E918F9 |
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 1     |            | 7E41940C9C |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0a88 |           | Nvidia     | MCP79 Memory Controller      | 10    |            | 8361590CBD |
| 10de:0a89 |           | Nvidia     | MCP79 Memory Controller      | 10    |            | 8361590CBD |
| 10de:0a98 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 10    |            | 8361590CBD |
| 10de:0aa4 |           | Nvidia     | MCP79 Memory Controller      | 10    |            | 8361590CBD |
| 8086:9d21 | 103c:84de | Intel      | Sunrise Point-LP PMC         | 6     |            | 6B7FA4FF60 |
| 10de:0568 | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] Mem... | 5     |            | 4CA7976A88 |
| 10de:0751 | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] Mem... | 5     |            | 4CA7976A88 |
| 10de:0754 | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] Mem... | 5     |            | 4CA7976A88 |
| 8086:9d21 | 8086:9d21 | Intel      | Sunrise Point-LP PMC         | 4     | intel_p... | 5F28079AA4 |
| 8086:9d21 | 1025:1287 | Intel      | Sunrise Point-LP PMC         | 3     | intel_p... | C861864ED7 |
| 8086:9d21 | 1028:0754 | Intel      | Sunrise Point-LP PMC         | 3     |            | 7CC5A36861 |
| 8086:9d21 | 1028:0852 | Intel      | Sunrise Point-LP PMC         | 3     |            | 5A27DEAF8A |
| 8086:a121 | 17aa:30ba | Intel      | 100 Series/C230 Series Ch... | 3     |            | 818DCABBD8 |
| 8086:a121 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 3     |            | 5984E1BBAC |
| 8086:a36f | 8086:7270 | Intel      | Cannon Lake PCH Shared SRAM  | 3     |            | 5D5C8FEFBA |
| 8086:a121 | 1028:06d4 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 275E0EEAEF |
| 8086:a121 | 1028:075d | Intel      | 100 Series/C230 Series Ch... | 2     |            | 404A8B3A68 |
| 8086:a121 | 103c:81b7 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 447E6C6392 |
| 8086:a121 | 8086:a121 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 4F5252C592 |
| 8086:02ef | 1028:0954 | Intel      | Comet Lake PCH-LP Shared ... | 1     |            | 8740133E10 |
| 8086:9d21 | 1025:1130 | Intel      | Sunrise Point-LP PMC         | 1     |            | D33236ABB3 |
| 8086:9d21 | 1043:12a1 | Intel      | Sunrise Point-LP PMC         | 1     |            | 689F9F13AF |
| 8086:9d21 | 144d:c133 | Intel      | Sunrise Point-LP PMC         | 1     |            | 39977FE582 |
| 8086:9d21 | 17aa:3630 | Intel      | Sunrise Point-LP PMC         | 1     |            | 9374D57487 |
| 8086:9d21 | 8086:7270 | Intel      | Sunrise Point-LP PMC         | 1     |            | 39AFD1D7B1 |
| 8086:a121 | 1025:1063 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 057A5601FF |
| 8086:a121 | 103c:2b3e | Intel      | 100 Series/C230 Series Ch... | 1     |            | 8B96DC41BD |
| 8086:a121 | 103c:8058 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 2281502A3C |
| 8086:a121 | 103c:805e | Intel      | 100 Series/C230 Series Ch... | 1     |            | FDD0A4E977 |
| 8086:a121 | 1071:0752 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 3BDFB07582 |
| 8086:a121 | 1462:aac1 | Intel      | 100 Series/C230 Series Ch... | 1     |            | D77183679A |
| 8086:a121 | 1462:aea1 | Intel      | 100 Series/C230 Series Ch... | 1     |            | E033B6FBEA |
| 8086:a121 | 17aa:30fc | Intel      | 100 Series/C230 Series Ch... | 1     |            | 70E8C27FFF |
| 8086:a121 | 17aa:3113 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 7739219D01 |
| 8086:a121 | 17aa:36bb | Intel      | 100 Series/C230 Series Ch... | 1     |            | B790C5FA32 |
| 8086:a121 | 17aa:36bc | Intel      | 100 Series/C230 Series Ch... | 1     |            | 06513D31C5 |
| 8086:a121 | 17aa:36cc | Intel      | 100 Series/C230 Series Ch... | 1     |            | 9A305C10EC |
| 8086:a2a1 | 1028:079e | Intel      | 200 Series/Z370 Chipset F... | 1     |            | 2BF103DD36 |
| 8086:a2a1 | 103c:838b | Intel      | 200 Series/Z370 Chipset F... | 1     |            | AC62725ABE |
| 8086:a36f | 1028:0851 | Intel      | Cannon Lake PCH Shared SRAM  | 1     |            | 05D6B79D2F |
| 8086:a36f | 17aa:3123 | Intel      | Cannon Lake PCH Shared SRAM  | 1     |            | 943F3319E9 |
| 8086:a36f | 17aa:313d | Intel      | Cannon Lake PCH Shared SRAM  | 1     |            | 5BCA9F711E |
| 8086:a36f | 17aa:36f4 | Intel      | Cannon Lake PCH Shared SRAM  | 1     |            | 6543F3C4AF |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1131:7231 | 1461:2a0f | Philips... | SAA7231                      | 6     |            | FF848E7FFB |
| 1002:ac12 | 12ab:0003 | AMD        | Theater HD T507 (DVB-T) T... | 3     |            | EA55AE13AC |
| 1002:ac12 | 1002:b539 | AMD        | Theater HD T507 (DVB-T) T... | 1     |            | DD5E0979B0 |
| 1022:15e2 | 17aa:36f5 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | 7E41940C9C |
| 10cf:2030 | 104d:9062 | Fujitsu... | Fujitsu Multimedia contro... | 1     |            | 2628EBE1BB |
| 1131:7231 | 1461:2b07 | Philips... | SAA7231                      | 1     |            | 8672A3F85D |
| 1131:7231 | 1461:2b0f | Philips... | SAA7231                      | 1     |            | F92CB57F54 |
| 1745:3000 | 104d:9049 | ViXS Sy... | Colossus Encoder Device      | 1     |            | 2628EBE1BB |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:1686 | 14e4:1686 | Broadco... | NetXtreme BCM57766 Gigabi... | 19    | tg3        | F82FCD2051 |
| 11ab:436a | 11ab:00ba | Marvell... | 88E8058 PCI-E Gigabit Eth... | 16    | sky2       | 8889AFD8F1 |
| 14e4:16b4 | 14e4:16b4 | Broadco... | NetXtreme BCM57765 Gigabi... | 12    | tg3        | C88A6086FA |
| 10ec:8168 | 1025:8000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 11    | r8169      | FF848E7FFB |
| 10de:0ab0 | 10de:cb79 | Nvidia     | MCP79 Ethernet               | 10    | forcedeth  | 8361590CBD |
| 10ec:8168 | 17aa:365e | Realtek... | RTL8111/8168/8411 PCI Exp... | 9     | r8169      | 338C59EF86 |
| 10ec:8168 | 103c:2ac5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 8     | r8169      | A5E0E95D2C |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 8     | r8169      | 3BDFB07582 |
| 11ab:4362 | 11ab:5321 | Marvell... | 88E8053 PCI-E Gigabit Eth... | 8     | sky2       | B24608A945 |
| 14e4:1684 | 14e4:1684 | Broadco... | NetXtreme BCM5764M Gigabi... | 8     | tg3        | F0515A0217 |
| 10ec:8168 | 103c:84de | Realtek... | RTL8111/8168/8411 PCI Exp... | 6     | r8169      | 6B7FA4FF60 |
| 10de:0760 | 1025:8000 | Nvidia     | MCP77 Ethernet               | 5     | forcedeth  | 4CA7976A88 |
| 10ec:8168 | 1043:205f | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8169      | E6838B3DD6 |
| 10ec:8168 | 144d:b091 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8169      | 857C8BE5D0 |
| 10ec:8168 | 1b50:4606 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8169      | D33236ABB3 |
| 10ec:8168 | 1025:0266 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | A2FF4426C9 |
| 10ec:8168 | 103c:8245 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 2D74D9A2EF |
| 10ec:8168 | 1043:858f | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | DA374C3C83 |
| 10ec:8168 | 104d:907e | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 4A2DA5DD1B |
| 10ec:8168 | 17aa:366c | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | A922BB8973 |
| 10ec:8168 | 17aa:36c4 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 00A1738003 |
| 10ec:8136 | 1028:0754 | Realtek... | RTL810xE PCI Express Fast... | 3     | r8169      | 7CC5A36861 |
| 10ec:8168 | 1025:1287 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | C861864ED7 |
| 10ec:8168 | 1028:0511 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 8672A3F85D |
| 10ec:8168 | 1028:0852 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 5A27DEAF8A |
| 10ec:8168 | 103c:2aed | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 00FCD6CB57 |
| 10ec:8168 | 1043:8432 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 7F0F347502 |
| 10ec:8168 | 104d:9083 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | B4CF237F88 |
| 10ec:8168 | 17aa:3671 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 906A62D75E |
| 10ec:8168 | 17aa:3685 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 647613F22B |
| 1969:1091 | 1028:0548 | Qualcom... | AR8161 Gigabit Ethernet      | 3     | alx        | 229BA614EC |
| 8086:15b7 | 17aa:30ba | Intel      | Ethernet Connection (2) I... | 3     | e1000e     | 818DCABBD8 |
| 10ec:8136 | 10ec:8136 | Realtek... | RTL810xE PCI Express Fast... | 2     | r8169      | 55C2F8E26B |
| 10ec:8136 | 17aa:3602 | Realtek... | RTL810xE PCI Express Fast... | 2     | r8169      | 60AE7E3358 |
| 10ec:8168 | 1019:811e | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 1F5B5C1D86 |
| 10ec:8168 | 1025:0275 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 19FBB5D44C |
| 10ec:8168 | 1025:0792 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 3D1389215D |
| 10ec:8168 | 1025:085f | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 90FF435FAD |
| 10ec:8168 | 1025:098f | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 350CC83AC7 |
| 10ec:8168 | 1025:1065 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 21CA50C386 |
| 10ec:8168 | 1028:06d4 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 275E0EEAEF |
| 10ec:8168 | 1028:07e4 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 4EB59BF315 |
| 10ec:8168 | 103c:2179 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 7B6E93783B |
| 10ec:8168 | 103c:2afc | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 346458F274 |
| 10ec:8168 | 103c:81b7 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 447E6C6392 |
| 10ec:8168 | 103c:8304 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | A63E8373C4 |
| 10ec:8168 | 103c:8381 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 83034BC0E9 |
| 10ec:8168 | 103c:84ee | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 5D5C8FEFBA |
| 10ec:8168 | 1043:200f | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 7F0055E131 |
| 10ec:8168 | 104d:908e | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 59BB8EC907 |
| 10ec:8168 | 104d:9097 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 7685534B8E |
| 10ec:8168 | 1462:b062 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 0FC1178D7D |
| 10ec:8168 | 17aa:30dd | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | C64BB03524 |
| 10ec:8168 | 17aa:3637 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 91FFB55E1F |
| 10ec:8168 | 17aa:367b | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 3EBFFF7DAD |
| 10ec:8168 | 17aa:3695 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8168      | 08BB09B100 |
| 10ec:8168 | 17aa:36a8 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 5F6FF0EBDA |
| 10ec:8168 | 17aa:36be | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 3A3B100E41 |
| 10ec:8168 | 1854:0200 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 2128A4CD93 |
| 10ec:8168 | 1b0a:0183 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 78D39E18EF |
| 10ec:8168 | 1b0a:0188 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | A94F1201C4 |
| 10ec:8168 | 1bc6:01ac | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 2146FDE0CF |
| 1969:e091 | 1462:ae67 | Qualcom... | Killer E220x Gigabit Ethe... | 2     | alx        | 881CDBC376 |
| 8086:153a | 103c:18e6 | Intel      | Ethernet Connection I217-LM  | 2     | e1000e     | C0BDA7E63F |
| 8086:15b7 | 1028:075d | Intel      | Ethernet Connection (2) I... | 2     | e1000e     | 404A8B3A68 |
| 10ec:8136 | 17aa:300f | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | 1112BF63F0 |
| 10ec:8136 | 1b50:4605 | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | EBBCA68281 |
| 10ec:8168 | 1025:039d | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | A629A81791 |
| 10ec:8168 | 1025:0640 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | D973B3B4E4 |
| 10ec:8168 | 1025:0720 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | D3734872B2 |
| 10ec:8168 | 1025:0863 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 3370E1020B |
| 10ec:8168 | 1025:105c | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | E7395D0EE2 |
| 10ec:8168 | 1025:1063 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 057A5601FF |
| 10ec:8168 | 1028:0479 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 2E89DCF36E |
| 10ec:8168 | 1028:05c2 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | EFDACF8C18 |
| 10ec:8168 | 1028:05db | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 3FEDAA45BD |
| 10ec:8168 | 1028:0623 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 29D0AD2441 |
| 10ec:8168 | 1028:0628 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | A3E9972EEA |
| 10ec:8168 | 1028:06cc | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | E534D33394 |
| 10ec:8168 | 1028:074a | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | D07D321CCE |
| 10ec:8168 | 1028:079e | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 2BF103DD36 |
| 10ec:8168 | 1028:0855 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | DACA9432F8 |
| 10ec:8168 | 1028:0954 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 8740133E10 |
| 10ec:8168 | 103c:18dd | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 73E763ADFA |
| 10ec:8168 | 103c:18ea | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 101B838D0E |
| 10ec:8168 | 103c:2b0a | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 499EA7DFBB |
| 10ec:8168 | 103c:2b0d | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 3E13F8A157 |
| 10ec:8168 | 103c:2b13 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 8553F899D5 |
| 10ec:8168 | 103c:2b1c | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 3321732E8E |
| 10ec:8168 | 103c:2b1f | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | F01E3C859D |
| 10ec:8168 | 103c:2b3b | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | A772887752 |
| 10ec:8168 | 103c:2b3e | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 8B96DC41BD |
| 10ec:8168 | 103c:81b9 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 15C46542B5 |
| 10ec:8168 | 103c:81bb | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 0F82F36E74 |
| 10ec:8168 | 103c:838b | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | AC62725ABE |
| 10ec:8168 | 103c:8430 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 2B0CDC9F2B |
| 10ec:8168 | 1043:204f | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 5F116B16F1 |
| 10ec:8168 | 1043:208f | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 689F9F13AF |
| 10ec:8168 | 1043:83b4 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | AADAAE6450 |
| 10ec:8168 | 1043:84cd | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 48A3B0ECA9 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 168c:0030 | 106b:009a | Qualcom... | AR93xx Wireless Network A... | 12    | ath9k      | C88A6086FA |
| 10ec:8179 | 17aa:0179 | Realtek... | RTL8188EE Wireless Networ... | 11    | rtl8188ee  | 647613F22B |
| 14e4:4328 | 106b:008c | Broadco... | BCM4321 802.11a/b/g/n        | 11    | wl         | 8889AFD8F1 |
| 168c:002a | 106b:008f | Qualcom... | AR928X Wireless Network A... | 11    | ath9k      | D26C5DA01F |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 10    | 8821ce     | A63E8373C4 |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 10    | iwlwifi    | 9374D57487 |
| 14e4:43a0 | 106b:0111 | Broadco... | BCM4360 802.11ac Wireless... | 9     | wl         | F82FCD2051 |
| 168c:002b | 17aa:30a1 | Qualcom... | AR9285 Wireless Network A... | 8     | ath9k      | 55C2F8E26B |
| 168c:0042 | 17aa:0901 | Qualcom... | QCA9377 802.11ac Wireless... | 8     | ath10k_pci | 00A1738003 |
| 168c:0042 | 1a3b:2231 | Qualcom... | QCA9377 802.11ac Wireless... | 8     | ath10k_pci | 7F0055E131 |
| 1814:5390 | 1814:f051 | Ralink     | RT5390 Wireless 802.11n 1... | 8     | rt2800pci  | A5E0E95D2C |
| 10ec:8176 | 10ec:8176 | Realtek... | RTL8188CE 802.11b/g/n WiF... | 7     | rtl8192ce  | A922BB8973 |
| 14e4:432b | 106b:008e | Broadco... | BCM4322 802.11a/b/g/n Wir... | 7     | ssb        | 8361590CBD |
| 168c:002b | 1a3b:1089 | Qualcom... | AR9285 Wireless Network A... | 7     | ath9k      | 7BD55BD71D |
| 168c:0032 | 17aa:3118 | Qualcom... | AR9485 Wireless Network A... | 7     | ath9k      | AF35D3346C |
| 1814:3090 | 11ad:6622 | Ralink     | RT3090 Wireless 802.11n 1... | 7     | rt2800pci  | 5EBFC68D96 |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 7     | iwlwifi    | D33236ABB3 |
| 10ec:b723 | 103c:81c1 | Realtek... | RTL8723BE PCIe Wireless N... | 6     | rtl8723be  | 2D74D9A2EF |
| 14e4:4328 | 106b:0088 | Broadco... | BCM4321 802.11a/b/g/n        | 6     | wl         | 44E71D3F5A |
| 168c:0034 | 11ad:6621 | Qualcom... | AR9462 Wireless Network A... | 6     | ath9k      | BEDE9EC674 |
| 168c:002b | 105b:e037 | Qualcom... | AR9285 Wireless Network A... | 5     | ath9k      | 4A2DA5DD1B |
| 168c:0034 | 144d:4112 | Qualcom... | AR9462 Wireless Network A... | 5     | ath9k      | 857C8BE5D0 |
| 10ec:8172 | 10ec:e021 | Realtek... | RTL8191SEvB Wireless LAN ... | 4     | rtl8192se  | A2FF4426C9 |
| 10ec:8179 | 10ec:0189 | Realtek... | RTL8188EE Wireless Networ... | 4     | rtl8188ee  | E6BCDB1E4D |
| 10ec:8179 | 1a3b:1f38 | Realtek... | RTL8188EE Wireless Networ... | 4     | rtl8188ee  | 227CCDA2A1 |
| 14e4:4328 | 106b:0087 | Broadco... | BCM4321 802.11a/b/g/n        | 4     | ssb        | 0DF85531E1 |
| 14e4:4359 | 14e4:05e2 | Broadco... | BCM43228 802.11a/b/g/n       | 4     | wl         | 101B838D0E |
| 168c:002b | 105b:e017 | Qualcom... | AR9285 Wireless Network A... | 4     | ath9k      | B4CF237F88 |
| 168c:0032 | 1028:0209 | Qualcom... | AR9485 Wireless Network A... | 4     | ath9k      | 45F86E051C |
| 168c:0032 | 103c:1838 | Qualcom... | AR9485 Wireless Network A... | 4     | ath9k      | 346458F274 |
| 168c:003e | 1028:0310 | Qualcom... | QCA6174 802.11ac Wireless... | 4     | ath10k_pci | F41BD5BF5B |
| 168c:0042 | 1028:1810 | Qualcom... | QCA9377 802.11ac Wireless... | 4     | ath10k_pci | 5A27DEAF8A |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 4     | iwlwifi    | FDD0A4E977 |
| 10ec:8176 | 1a3b:1139 | Realtek... | RTL8188CE 802.11b/g/n WiF... | 3     | rtl8192ce  | 0FC1178D7D |
| 10ec:8723 | 1a3b:2114 | Realtek... | RTL8723AE PCIe Wireless N... | 3     | rtl8723ae  | A94F1201C4 |
| 10ec:8821 | 17aa:a814 | Realtek... | RTL8821AE 802.11ac PCIe W... | 3     | rtl8821ae  | 5DA9F63B49 |
| 10ec:b822 | 103c:831b | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 3     | r8822be    | 5D5C8FEFBA |
| 10ec:c821 | 17aa:c024 | Realtek... | RTL8821CE 802.11ac PCIe W... | 3     | 8821ce     | DE2A851C8F |
| 14e4:4312 | 106b:0089 | Broadco... | BCM4311 802.11a/b/g          | 3     | ssb        | B24608A945 |
| 14e4:4331 | 106b:00f4 | Broadco... | BCM4331 802.11a/b/g/n        | 3     | bcma       | CD3C0C4583 |
| 14e4:43ba | 106b:014a | Broadco... | BCM43602 802.11ac Wireles... | 3     | brcmfmac   | 5984E1BBAC |
| 14e4:4727 | 14e4:051b | Broadco... | BCM4313 802.11bgn Wireles... | 3     | wl         | 338C59EF86 |
| 168c:0036 | 1028:020e | Qualcom... | QCA9565 / AR9565 Wireless... | 3     | ath9k      | C1A91BB2D3 |
| 168c:0036 | 11ad:0642 | Qualcom... | QCA9565 / AR9565 Wireless... | 3     | ath9k      | 3370E1020B |
| 168c:0036 | 17aa:3026 | Qualcom... | QCA9565 / AR9565 Wireless... | 3     | ath9k      | 3EBFFF7DAD |
| 1814:539b | 103c:18ed | Ralink     | RT5390R 802.11bgn PCIe Wi... | 3     | rt2800pci  | 00FCD6CB57 |
| 8086:08b3 | 8086:8070 | Intel      | Wireless 3160                | 3     | iwlwifi    | 2128A4CD93 |
| 8086:24f3 | 8086:0010 | Intel      | Wireless 8260                | 3     | iwlwifi    | 818DCABBD8 |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 3     | iwlwifi    | 447E6C6392 |
| 8086:3165 | 8086:4410 | Intel      | Wireless 3165                | 3     | iwlwifi    | D07D321CCE |
| 10ec:8171 | 10ec:8186 | Realtek... | RTL8191SEvA Wireless LAN ... | 2     | rtl8192se  | 19FBB5D44C |
| 10ec:8821 | 1a3b:216a | Realtek... | RTL8821AE 802.11ac PCIe W... | 2     | rtl8821ae  | 2146FDE0CF |
| 10ec:b723 | 10ec:8739 | Realtek... | RTL8723BE PCIe Wireless N... | 2     | rtl8723be  | 275E0EEAEF |
| 10ec:b723 | 17aa:b728 | Realtek... | RTL8723BE PCIe Wireless N... | 2     | rtl8723be  | 89586A0608 |
| 10ec:b723 | 1a3b:2159 | Realtek... | RTL8723BE PCIe Wireless N... | 2     | rtl8723be  | 881CDBC376 |
| 14e4:43ba | 106b:0155 | Broadco... | BCM43602 802.11ac Wireles... | 2     | brcmfmac   | 906BCD4AC8 |
| 168c:002a | 105b:e007 | Qualcom... | AR928X Wireless Network A... | 2     | ath9k      | 05CFF66AC2 |
| 168c:0032 | 105b:e044 | Qualcom... | AR9485 Wireless Network A... | 2     | ath9k      | 7685534B8E |
| 168c:0032 | 1a3b:1195 | Qualcom... | AR9485 Wireless Network A... | 2     | ath9k      | 09FE5E4566 |
| 168c:0036 | 1028:020c | Qualcom... | QCA9565 / AR9565 Wireless... | 2     | ath9k      | A3E9972EEA |
| 168c:0042 | 11ad:08a6 | Qualcom... | QCA9377 802.11ac Wireless... | 2     | ath10k_pci | 21CA50C386 |
| 1814:5390 | 1a3b:1155 | Ralink     | RT5390 Wireless 802.11n 1... | 2     | rt2800pci  | DA0C20FDF7 |
| 10ec:8171 | 1113:7811 | Realtek... | RTL8191SEvA Wireless LAN ... | 1     | rtl8192se  | F1E1BF19CC |
| 10ec:8171 | 1462:897a | Realtek... | RTL8191SEvA Wireless LAN ... | 1     | rtl8192se  | 17AD880F72 |
| 10ec:8179 | 103c:197d | Realtek... | RTL8188EE Wireless Networ... | 1     | rtl8188ee  | F01E3C859D |
| 10ec:8179 | 1a3b:1d38 | Realtek... | RTL8188EE Wireless Networ... | 1     | rtl8188ee  | E89226495D |
| 10ec:8723 | 10ec:8723 | Realtek... | RTL8723AE PCIe Wireless N... | 1     | rtl8723ae  | 3BDFB07582 |
| 10ec:8821 | 1a3b:2161 | Realtek... | RTL8821AE 802.11ac PCIe W... | 1     | rtl8821ae  | DA374C3C83 |
| 10ec:b723 | 10ec:b723 | Realtek... | RTL8723BE PCIe Wireless N... | 1     | rtl8723be  | E745E03926 |
| 10ec:b723 | 17aa:b736 | Realtek... | RTL8723BE PCIe Wireless N... | 1     | rtl8723be  | F14A7F7311 |
| 10ec:b723 | 1a3b:2165 | Realtek... | RTL8723BE PCIe Wireless N... | 1     | rtl8723be  | D2834ADB05 |
| 14e4:4315 | 14e4:04ad | Broadco... | BCM4312 802.11b/g LP-PHY     | 1     | ssb        | 1112BF63F0 |
| 14e4:4359 | 1028:0014 | Broadco... | BCM43228 802.11a/b/g/n       | 1     | wl         | EFDACF8C18 |
| 14e4:4359 | 103c:2135 | Broadco... | BCM43228 802.11a/b/g/n       | 1     |            | 3E13F8A157 |
| 14e4:4365 | 103c:804a | Broadco... | BCM43142 802.11b/g/n         | 1     | wl         | A772887752 |
| 14e4:43a0 | 106b:0142 | Broadco... | BCM4360 802.11ac Wireless... | 1     | bcma       | 2CB78484FB |
| 14e4:43b1 | 103c:2154 | Broadco... | BCM4352 802.11ac Wireless... | 1     | wl         | EAFEC5FB57 |
| 14e4:43ba | 106b:0156 | Broadco... | BCM43602 802.11ac Wireles... | 1     | brcmfmac   | 92012F60BF |
| 14e4:43ba | 106b:016d | Broadco... | BCM43602 802.11ac Wireles... | 1     | brcmfmac   | 39AFD1D7B1 |
| 14e4:4727 | 1028:0010 | Broadco... | BCM4313 802.11bgn Wireles... | 1     | wl         | 2E89DCF36E |
| 14e4:4727 | 14e4:0510 | Broadco... | BCM4313 802.11bgn Wireles... | 1     | wl         | EA55AE13AC |
| 168c:001c | 10e9:1025 | Qualcom... | AR242x / AR542x Wireless ... | 1     | ath5k      | 86771347FB |
| 168c:002b | 1028:0205 | Qualcom... | AR9285 Wireless Network A... | 1     | ath9k      | 068C18FB16 |
| 168c:002b | 11ad:6613 | Qualcom... | AR9285 Wireless Network A... | 1     | ath9k      | A2613DB100 |
| 168c:002b | 1a3b:2c37 | Qualcom... | AR9285 Wireless Network A... | 1     | ath9k      | 7EF4233E74 |
| 168c:002e | 105b:e030 | Qualcom... | AR9287 Wireless Network A... | 1     | ath9k      | 9A053A8872 |
| 168c:0032 | 11ad:6617 | Qualcom... | AR9485 Wireless Network A... | 1     | ath9k      | D3734872B2 |
| 168c:0032 | 11ad:6627 | Qualcom... | AR9485 Wireless Network A... | 1     | ath9k      | C8D8836613 |
| 168c:0032 | 1a3b:1f86 | Qualcom... | AR9485 Wireless Network A... | 1     | ath9k      | 48A3B0ECA9 |
| 168c:0034 | 103c:1864 | Qualcom... | AR9462 Wireless Network A... | 1     | ath9k      | C0BDA7E63F |
| 168c:0036 | 144d:411c | Qualcom... | QCA9565 / AR9565 Wireless... | 1     | ath9k      | 40AB94A580 |
| 168c:0036 | 1a3b:2182 | Qualcom... | QCA9565 / AR9565 Wireless... | 1     | ath9k      | EE7F588C0D |
| 168c:0036 | 1a3b:218b | Qualcom... | QCA9565 / AR9565 Wireless... | 1     | ath9k      | 350CC83AC7 |
| 168c:0042 | 11ad:0806 | Qualcom... | QCA9377 802.11ac Wireless... | 1     |            | ECB6A89DFC |
| 168c:0042 | 1235:0901 | Qualcom... | QCA9377 802.11ac Wireless... | 1     | ath10k_pci | 530346DA62 |
| 168c:0042 | 144d:412b | Qualcom... | QCA9377 802.11ac Wireless... | 1     | ath10k_pci | 39977FE582 |
| 1814:3090 | 1462:872a | Ralink     | RT3090 Wireless 802.11n 1... | 1     | rt2800pci  | CBD910EA06 |
| 1814:3090 | 1814:3090 | Ralink     | RT3090 Wireless 802.11n 1... | 1     | rt2800pci  | E4BDC45558 |
| 1814:3090 | 1a3b:1087 | Ralink     | RT3090 Wireless 802.11n 1... | 1     | rt2800pci  | 7F0F347502 |
| 1814:3290 | 1a3b:2b87 | Ralink     | RT3290 Wireless 802.11n 1... | 1     | rt2800pci  | 1F5B5C1D86 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:10ce | 104d:9060 | Intel      | 82567V-2 Gigabit Network ... | 3     | e1000e     | 05CFF66AC2 |
| 8086:10fe | 17aa:3610 | Intel      | 82552 10/100 Network Conn... | 3     | e100       | E98AA97F27 |
| 8086:0085 | 8086:1311 | Intel      | Centrino Advanced-N 6205 ... | 2     | iwlwifi    | 02F1FBC843 |
| 8086:0091 | 8086:5221 | Intel      | Centrino Advanced-N 6230 ... | 2     | iwlwifi    | 8672A3F85D |
| 8086:10f0 | 1025:8000 | Intel      | 82578DC Gigabit Network C... | 2     | e1000e     | 1E17CF76B7 |
| 8086:1502 | 103c:3395 | Intel      | 82579LM Gigabit Network C... | 2     | e1000e     | 02F1FBC843 |
| 8086:1503 | 1025:8000 | Intel      | 82579V Gigabit Network Co... | 2     | e1000e     | D44BEF08F5 |
| 8086:1503 | 17aa:3623 | Intel      | 82579V Gigabit Network Co... | 2     | e1000e     | B98E1F49EA |
| 8086:0082 | 8086:1301 | Intel      | Centrino Advanced-N 6205 ... | 1     | iwlwifi    | 73E763ADFA |
| 8086:02f0 | 8086:42a4 | Intel      | Wireless-AC 9462             | 1     | wl         | 8740133E10 |
| 8086:10ce | 1025:048f | Intel      | 82567V-2 Gigabit Network ... | 1     | e1000e     | 25DFBA352F |
| 8086:10de | 103c:1489 | Intel      | 82567LM-3 Gigabit Network... | 1     | e1000e     | A6305AD3A0 |
| 8086:10eb | 17aa:3608 | Intel      | 82577LC Gigabit Network C... | 1     | e1000e     | EA55AE13AC |
| 8086:10ef | 17aa:306a | Intel      | 82578DM Gigabit Network C... | 1     | e1000e     | F15D263E67 |
| 8086:1502 | 1028:0543 | Intel      | 82579LM Gigabit Network C... | 1     | e1000e     | 0776B86016 |
| 8086:1502 | 8086:0000 | Intel      | 82579LM Gigabit Network C... | 1     | e1000e     | 81CF385125 |
| 8086:1503 | 17aa:3620 | Intel      | 82579V Gigabit Network Co... | 1     | e1000e     | 0C3E26BCE7 |

### Performance counters (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27a3 |           | Intel      | 945GM/GU Chipset Hardware... | 8     |            | B24608A945 |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:16bc | 14e4:0000 | Broadco... | BCM57765/57785 SDXC/MMC C... | 16    | sdhci_pci  | F82FCD2051 |
| 197b:2381 | 1025:0266 | JMicron... | Standard SD Host Controller  | 4     | sdhci_pci  | A2FF4426C9 |
| 8086:5aca | 17aa:36c4 | Intel      | Celeron N3350/Pentium N42... | 4     | sdhci_pci  | 00A1738003 |
| 10ec:5209 | 10ec:5209 | Realtek... | RTS5209 PCI Express Card ... | 3     | rtsx_pci   | 2128A4CD93 |
| 1180:e822 | 104d:9060 | Ricoh      | MMC/SD Host Controller       | 3     | sdhci_pci  | 05CFF66AC2 |
| 1180:e822 | 104d:9083 | Ricoh      | MMC/SD Host Controller       | 3     | sdhci_pci  | B4CF237F88 |
| 1180:e823 | 104d:907e | Ricoh      | PCIe SDXC/MMC Host Contro... | 3     | sdhci_pci  | 265BA34E71 |
| 14e4:16bc | 14e4:96bc | Broadco... | BCM57765/57785 SDXC/MMC C... | 3     | sdhci_pci  | C6F2E8BC12 |
| 197b:2381 | 17aa:3602 | JMicron... | Standard SD Host Controller  | 3     | sdhci_pci  | 55C2F8E26B |
| 1022:7906 | 17aa:36be | AMD        | FCH SD Flash Controller      | 2     | sdhci_pci  | 3A3B100E41 |
| 10ec:5209 | 1b0a:0188 | Realtek... | RTS5209 PCI Express Card ... | 2     | sdhci_pci  | A94F1201C4 |
| 1180:e822 | 104d:907e | Ricoh      | MMC/SD Host Controller       | 2     | sdhci_pci  | 4A2DA5DD1B |
| 1180:e822 | 104d:908e | Ricoh      | MMC/SD Host Controller       | 2     | sdhci_pci  | FE0F4C11DF |
| 1180:e823 | 104d:908e | Ricoh      | PCIe SDXC/MMC Host Contro... | 2     | sdhci_pci  | 59BB8EC907 |
| 1217:8621 | 1217:0002 | O2 Micro   | SD/MMC Card Reader Contro... | 2     | sdhci_pci  | 057A5601FF |
| 197b:2381 | 1025:0275 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | 19FBB5D44C |
| 197b:2381 | 1025:0608 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | BEDE9EC674 |
| 197b:2381 | 1043:842d | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | F1E1BF19CC |
| 197b:2391 | 1043:84c1 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | DB3BBECDD0 |
| 8086:a375 | 103c:84ee | Intel      | 300 Series Chipset Family... | 2     | sdhci_pci  | 5D5C8FEFBA |
| 1022:7806 | 1462:aa5e | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | 5DC25F1C8F |
| 1022:7806 | 17aa:3670 | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | 46E2D4B676 |
| 1022:7813 | 1028:0628 | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | A3E9972EEA |
| 1022:7813 | 1028:074a | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | D07D321CCE |
| 1022:7813 | 103c:2b3b | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | A772887752 |
| 1022:7906 | 1028:0855 | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | DACA9432F8 |
| 1022:7906 | 17aa:36bd | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | E1331356C7 |
| 1022:7906 | 17aa:36c6 | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | 5DA9F63B49 |
| 1022:7906 | 17aa:36da | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | DE2A851C8F |
| 1022:7906 | 17aa:36ec | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | C586E918F9 |
| 1106:401b | 17aa:3608 | VIA Tec... | VIA Secure Digital host c... | 1     | sdhci_pci  | EA55AE13AC |
| 1180:0822 | 1033:886f | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 86771347FB |
| 1180:e822 | 104d:9097 | Ricoh      | MMC/SD Host Controller       | 1     | sdhci_pci  | 7685534B8E |
| 1180:e823 | 104d:9083 | Ricoh      | PCIe SDXC/MMC Host Contro... | 1     | sdhci_pci  | A130539775 |
| 1180:e823 | 104d:9097 | Ricoh      | PCIe SDXC/MMC Host Contro... | 1     | sdhci_pci  | 81CEB684C0 |
| 1217:8520 | 1028:0626 | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | C1A91BB2D3 |
| 14e4:16bc | 106b:0000 | Broadco... | BCM57765/57785 SDXC/MMC C... | 1     | sdhci_pci  | CD3C0C4583 |
| 197b:2381 | 1025:039d | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | A629A81791 |
| 197b:2381 | 103c:1489 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | A6305AD3A0 |
| 197b:2381 | 1043:842e | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | E0910009B1 |
| 8086:31cc | 1043:1e80 | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | 5F116B16F1 |
| 8086:31cc | 1043:1ea0 | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | 7F0055E131 |
| 8086:31cc | 1854:0308 | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | 530346DA62 |
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | B4AB9671B3 |
| 8086:31d0 | 8086:7270 | Intel      | SD Host Controller           | 1     | sdhci_pci  | B4AB9671B3 |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 8A67730AF4 |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 8A67730AF4 |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 8A67730AF4 |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a324 | 103c:84ee | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 5D5C8FEFBA |
| 10de:1adb | 10de:13ad | Nvidia     | TU106 USB Type-C UCSI Con... | 1     | i2c_nvi... | E0192EBFC1 |
| 8086:02a4 | 1028:0954 | Intel      | Comet Lake SPI (flash) Co... | 1     |            | 8740133E10 |
| 8086:a324 | 1028:0851 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 05D6B79D2F |
| 8086:a324 | 17aa:3123 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 943F3319E9 |
| 8086:a324 | 17aa:313d | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 5BCA9F711E |
| 8086:a324 | 17aa:36f4 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 6543F3C4AF |
| 8086:a324 | 8086:7270 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 4313964FA7 |
| 8086:a32a | 1043:1e40 | Intel      | 300 Series Chipset Device    | 1     | intel_l... | 4313964FA7 |
| 8086:a368 | 1043:1241 | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | 4313964FA7 |
| 8086:a369 | 1043:1241 | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | 4313964FA7 |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a13d | 17aa:30ba | Intel      | 100 Series/C230 Series Ch... | 3     | serial     | 818DCABBD8 |
| 8086:1c3d | 103c:3395 | Intel      | 6 Series/C200 Series Chip... | 2     | serial     | 02F1FBC843 |
| 8086:8c3d | 103c:18e6 | Intel      | 8 Series/C220 Series Chip... | 2     | serial     | C0BDA7E63F |
| 8086:a13d | 1028:075d | Intel      | 100 Series/C230 Series Ch... | 2     | serial     | 404A8B3A68 |
| 8086:1e3d | 1028:0543 | Intel      | 7 Series/C210 Series Chip... | 1     | serial     | 0776B86016 |
| 8086:1e3d | 1854:f004 | Intel      | 7 Series/C210 Series Chip... | 1     | serial     | 81CF385125 |
| 8086:2e17 | 103c:1489 | Intel      | 4 Series Chipset Serial K... | 1     | serial     | A6305AD3A0 |
| 8086:a13d | 103c:8058 | Intel      | 100 Series/C230 Series Ch... | 1     | serial     | 2281502A3C |
| 8086:a13d | 103c:805e | Intel      | 100 Series/C230 Series Ch... | 1     | serial     | FDD0A4E977 |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d61 | 8086:9d61 | Intel      | Sunrise Point-LP Serial I... | 9     | intel_l... | 6B7FA4FF60 |
| 8086:3b32 | 8086:0000 | Intel      | 5 Series/3400 Series Chip... | 8     | intel_ips  | F0515A0217 |
| 8086:9d60 | 103c:84de | Intel      | Sunrise Point-LP Serial I... | 6     | intel_l... | 6B7FA4FF60 |
| 8086:3a32 | 1025:0266 | Intel      | 82801JI (ICH10 Family) Th... | 4     |            | A2FF4426C9 |
| 8086:5a8c | 17aa:36c4 | Intel      | Dynamic Platform and Ther... | 4     | process... | 00A1738003 |
| 8086:9d31 | 8086:9d31 | Intel      | Sunrise Point-LP Thermal ... | 4     | intel_p... | 5F28079AA4 |
| 8086:1903 | 8086:1903 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | proc_th... | AA4322078C |
| 8086:9d31 | 1025:1287 | Intel      | Sunrise Point-LP Thermal ... | 3     | intel_p... | C861864ED7 |
| 8086:9d31 | 1028:0754 | Intel      | Sunrise Point-LP Thermal ... | 3     | intel_p... | 7CC5A36861 |
| 8086:9d31 | 1028:0852 | Intel      | Sunrise Point-LP Thermal ... | 3     | intel_p... | 5A27DEAF8A |
| 8086:9d60 | 1028:0754 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 7CC5A36861 |
| 8086:9d60 | 1028:0852 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 5A27DEAF8A |
| 8086:9d60 | 8086:9d60 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_lpss | AA4322078C |
| 8086:9d61 | 1028:0754 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 7CC5A36861 |
| 8086:9d61 | 1028:0852 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 5A27DEAF8A |
| 8086:a127 | 17aa:30ba | Intel      | 100 Series/C230 Series Ch... | 3     | intel_l... | 818DCABBD8 |
| 8086:a131 | 17aa:30ba | Intel      | 100 Series/C230 Series Ch... | 3     | intel_p... | 818DCABBD8 |
| 8086:1e24 | 1462:b062 | Intel      | 7 Series/C210 Series Chip... | 2     |            | 0FC1178D7D |
| 8086:22dc |           | Intel      | Atom/Celeron/Pentium Proc... | 2     | process... | DA374C3C83 |
| 8086:5a8c |           | Intel      | Dynamic Platform and Ther... | 2     | process... | E6838B3DD6 |
| 8086:9ca4 | 8086:7270 | Intel      | Wildcat Point-LP Thermal ... | 2     | intel_p... | 906BCD4AC8 |
| 8086:a131 | 1028:06d4 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 275E0EEAEF |
| 8086:a131 | 8086:a131 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_p... | 4F5252C592 |
| 8086:a379 | 103c:84ee | Intel      | Cannon Lake PCH Thermal C... | 2     | intel_p... | 5D5C8FEFBA |
| 8086:02f9 | 1028:0954 | Intel      | Comet Lake Thermal Subsytem  | 1     |            | 8740133E10 |
| 8086:1603 | 8086:2010 | Intel      | Broadwell-U Processor The... | 1     | process... | C95062D4FF |
| 8086:1903 | 1043:1241 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | process... | 4313964FA7 |
| 8086:1903 | 1043:12a1 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | proc_th... | 689F9F13AF |
| 8086:318c | 1043:1e80 | Intel      | Celeron/Pentium Silver Pr... | 1     |            | 5F116B16F1 |
| 8086:318c | 1043:1ea0 | Intel      | Celeron/Pentium Silver Pr... | 1     | proc_th... | 7F0055E131 |
| 8086:318c | 17aa:36ed | Intel      | Celeron/Pentium Silver Pr... | 1     | process... | 8DFF428CAB |
| 8086:318c | 1854:0308 | Intel      | Celeron/Pentium Silver Pr... | 1     | proc_th... | 530346DA62 |
| 8086:31b4 | 1043:1e80 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_lpss | 5F116B16F1 |
| 8086:31b4 | 1043:1ea0 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_lpss | 7F0055E131 |
| 8086:31b6 | 1043:1e80 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_lpss | 5F116B16F1 |
| 8086:31b6 | 1043:1ea0 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_lpss | 7F0055E131 |
| 8086:31bc | 17aa:36ed | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 8DFF428CAB |
| 8086:31be | 17aa:36ed | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 8DFF428CAB |
| 8086:31c0 | 17aa:36ed | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 8DFF428CAB |
| 8086:31c2 | 1043:1e80 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_lpss | 5F116B16F1 |
| 8086:31c2 | 1043:1ea0 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_lpss | 7F0055E131 |
| 8086:31c2 | 17aa:36ed | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 8DFF428CAB |
| 8086:31c4 | 17aa:36ed | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 8DFF428CAB |
| 8086:31c6 | 17aa:36ed | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 8DFF428CAB |
| 8086:31ee | 17aa:36ed | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 8DFF428CAB |
| 8086:3b32 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 1     | intel_ips  | 7F0F347502 |
| 8086:3b32 | 1462:ae31 | Intel      | 5 Series/3400 Series Chip... | 1     | intel_ips  | CBD910EA06 |
| 8086:3b32 | 17aa:3608 | Intel      | 5 Series/3400 Series Chip... | 1     | intel_ips  | EA55AE13AC |
| 8086:3b32 | 1b7d:0050 | Intel      | 5 Series/3400 Series Chip... | 1     | intel_ips  | E4BDC45558 |
| 8086:5aac | 1043:3000 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | E6838B3DD6 |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 8A67730AF4 |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 8A67730AF4 |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 8A67730AF4 |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 8A67730AF4 |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 8A67730AF4 |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 8A67730AF4 |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 8A67730AF4 |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 8A67730AF4 |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 8A67730AF4 |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 8A67730AF4 |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 8A67730AF4 |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 8A67730AF4 |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 8A67730AF4 |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 8A67730AF4 |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 8A67730AF4 |
| 8086:8ca4 | 8086:7270 | Intel      | 9 Series Chipset Family T... | 1     |            | 92012F60BF |
| 8086:9d31 | 1043:12a1 | Intel      | Sunrise Point-LP Thermal ... | 1     | intel_p... | 689F9F13AF |
| 8086:9d31 | 144d:c133 | Intel      | Sunrise Point-LP Thermal ... | 1     | intel_p... | 39977FE582 |
| 8086:9d31 | 17aa:3630 | Intel      | Sunrise Point-LP Thermal ... | 1     | intel_p... | 9374D57487 |
| 8086:9d60 | 1043:12a1 | Intel      | Sunrise Point-LP Serial I... | 1     | intel_lpss | 689F9F13AF |
| 8086:9d61 | 1043:12a1 | Intel      | Sunrise Point-LP Serial I... | 1     | intel_lpss | 689F9F13AF |
| 8086:a127 | 1071:0752 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_l... | 3BDFB07582 |
| 8086:a127 | 1462:aea1 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_l... | E033B6FBEA |
| 8086:a131 | 1025:1063 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | 057A5601FF |
| 8086:a131 | 1028:075d | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | F41BD5BF5B |
| 8086:a131 | 103c:8058 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 2281502A3C |
| 8086:a131 | 103c:805e | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | FDD0A4E977 |
| 8086:a131 | 1071:0752 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | 3BDFB07582 |
| 8086:a131 | 1462:aac1 | Intel      | 100 Series/C230 Series Ch... | 1     |            | D77183679A |
| 8086:a131 | 1462:aea1 | Intel      | 100 Series/C230 Series Ch... | 1     |            | E033B6FBEA |
| 8086:a131 | 17aa:30fc | Intel      | 100 Series/C230 Series Ch... | 1     |            | 70E8C27FFF |
| 8086:a131 | 17aa:3113 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 7739219D01 |
| 8086:a131 | 17aa:36bb | Intel      | 100 Series/C230 Series Ch... | 1     |            | B790C5FA32 |
| 8086:a131 | 17aa:36bc | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | 06513D31C5 |
| 8086:a131 | 17aa:36cc | Intel      | 100 Series/C230 Series Ch... | 1     |            | 9A305C10EC |
| 8086:a160 | 1028:075d | Intel      | 100 Series/C230 Series Ch... | 1     | intel_lpss | 404A8B3A68 |
| 8086:a160 | 1071:0752 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_l... | 3BDFB07582 |
| 8086:a160 | 1462:aea1 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_l... | E033B6FBEA |
| 8086:a160 | 8086:a160 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_l... | 4F5252C592 |
| 8086:a161 | 1071:0752 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_l... | 3BDFB07582 |
| 8086:a161 | 1462:aea1 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_l... | E033B6FBEA |
| 8086:a161 | 8086:a161 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_l... | 4F5252C592 |
| 8086:a162 | 1028:075d | Intel      | 100 Series/C230 Series Ch... | 1     | intel_lpss | 404A8B3A68 |
| 8086:a2b1 | 1028:079e | Intel      | 200 Series PCH Thermal Su... | 1     |            | 2BF103DD36 |
| 8086:a379 | 1028:0851 | Intel      | Cannon Lake PCH Thermal C... | 1     |            | 05D6B79D2F |
| 8086:a379 | 1043:1241 | Intel      | Cannon Lake PCH Thermal C... | 1     | intel_p... | 4313964FA7 |
| 8086:a379 | 17aa:3123 | Intel      | Cannon Lake PCH Thermal C... | 1     | intel_p... | 943F3319E9 |
| 8086:a379 | 17aa:313d | Intel      | Cannon Lake PCH Thermal C... | 1     | intel_p... | 5BCA9F711E |
| 8086:a379 | 17aa:36f4 | Intel      | Cannon Lake PCH Thermal C... | 1     | intel_p... | 6543F3C4AF |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:283e | 106b:00a0 | Intel      | 82801H (ICH8 Family) SMBu... | 16    | i2c_i801   | 8889AFD8F1 |
| 8086:1c22 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 12    | i2c_i801   | C88A6086FA |
| 10de:0aa2 | 10de:cb79 | Nvidia     | MCP79 SMBus                  | 10    | i2c_nfo... | 8361590CBD |
| 8086:1c22 | 17aa:365e | Intel      | 6 Series/C200 Series Chip... | 9     | i2c_i801   | 338C59EF86 |
| 8086:8c22 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 9     | i2c_i801   | F82FCD2051 |
| 8086:1c22 | 103c:2ac5 | Intel      | 6 Series/C200 Series Chip... | 8     | i2c_i801   | A5E0E95D2C |
| 8086:27da | 8086:7270 | Intel      | NM10/ICH7 Family SMBus Co... | 8     | i2c_i801   | B24608A945 |
| 8086:3b30 | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 8     | i2c_i801   | F0515A0217 |
| 8086:9d23 | 103c:84de | Intel      | Sunrise Point-LP SMBus       | 6     | i2c_i801   | 6B7FA4FF60 |
| 10de:0752 | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] SMBus  | 5     | i2c_nfo... | 4CA7976A88 |
| 8086:1e22 | 144d:b091 | Intel      | 7 Series/C216 Chipset Fam... | 5     | i2c_i801   | 857C8BE5D0 |
| 1002:4385 |           | AMD        | SBx00 SMBus Controller       | 4     | i2c_pii... | 2E89DCF36E |
| 1022:780b | 103c:8245 | AMD        | FCH SMBus Controller         | 4     | i2c_piix4  | 2D74D9A2EF |
| 8086:1c22 | 104d:907e | Intel      | 6 Series/C200 Series Chip... | 4     | i2c_i801   | 4A2DA5DD1B |
| 8086:1c22 | 17aa:366c | Intel      | 6 Series/C200 Series Chip... | 4     | i2c_i801   | A922BB8973 |
| 8086:3a30 | 1025:0266 | Intel      | 82801JI (ICH10 Family) SM... | 4     | i2c_i801   | A2FF4426C9 |
| 8086:5ad4 | 17aa:36c4 | Intel      | Celeron N3350/Pentium N42... | 4     | i2c_i801   | 00A1738003 |
| 8086:9d23 | 8086:9d23 | Intel      | Sunrise Point-LP SMBus       | 4     | i2c_i801   | 5F28079AA4 |
| 8086:0f12 |           | Intel      | Atom Processor E3800 Seri... | 3     | i2c_i801   | E6BCDB1E4D |
| 8086:1c22 | 1028:0511 | Intel      | 6 Series/C200 Series Chip... | 3     | i2c_i801   | 8672A3F85D |
| 8086:1c22 | 103c:2aed | Intel      | 6 Series/C200 Series Chip... | 3     | i2c_i801   | 00FCD6CB57 |
| 8086:1c22 | 104d:9083 | Intel      | 6 Series/C200 Series Chip... | 3     | i2c_i801   | B4CF237F88 |
| 8086:1c22 | 8086:1c22 | Intel      | 6 Series/C200 Series Chip... | 3     | i2c_i801   | 19478FF625 |
| 8086:1e22 | 1028:0548 | Intel      | 7 Series/C216 Chipset Fam... | 3     | i2c_i801   | 229BA614EC |
| 8086:1e22 | 17aa:3671 | Intel      | 7 Series/C216 Chipset Fam... | 3     | i2c_i801   | 906A62D75E |
| 8086:1e22 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 3     | i2c_i801   | CD3C0C4583 |
| 8086:27da | 17aa:3602 | Intel      | NM10/ICH7 Family SMBus Co... | 3     | i2c_i801   | 55C2F8E26B |
| 8086:27da | 17aa:3610 | Intel      | NM10/ICH7 Family SMBus Co... | 3     | i2c_i801   | E98AA97F27 |
| 8086:3a30 | 104d:9060 | Intel      | 82801JI (ICH10 Family) SM... | 3     | i2c_i801   | 05CFF66AC2 |
| 8086:3b30 | 1025:045c | Intel      | 5 Series/3400 Series Chip... | 3     | i2c_i801   | FF848E7FFB |
| 8086:8c22 | 17aa:3685 | Intel      | 8 Series/C220 Series Chip... | 3     | i2c_i801   | 647613F22B |
| 8086:9d23 | 1025:1287 | Intel      | Sunrise Point-LP SMBus       | 3     | i2c_i801   | C861864ED7 |
| 8086:9d23 | 1028:0754 | Intel      | Sunrise Point-LP SMBus       | 3     | i2c_i801   | 7CC5A36861 |
| 8086:9d23 | 1028:0852 | Intel      | Sunrise Point-LP SMBus       | 3     | i2c_i801   | 5A27DEAF8A |
| 8086:a123 | 17aa:30ba | Intel      | 100 Series/C230 Series Ch... | 3     | i2c_i801   | 818DCABBD8 |
| 8086:a123 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 3     | i801_smbus | 5984E1BBAC |
| 1002:4385 | 1002:4385 | AMD        | SBx00 SMBus Controller       | 2     | i2c_piix4  | F1E1BF19CC |
| 1022:780b | 1025:0642 | AMD        | FCH SMBus Controller         | 2     | i2c_piix4  | 973EEE4869 |
| 1022:780b | 103c:2afc | AMD        | FCH SMBus Controller         | 2     | i2c_piix4  | 346458F274 |
| 1022:790b | 1028:07e3 | AMD        | FCH SMBus Controller         | 2     | i2c_piix4  | 4EB59BF315 |
| 1022:790b | 103c:8381 | AMD        | FCH SMBus Controller         | 2     | i2c_pii... | 83034BC0E9 |
| 1022:790b | 17aa:36be | AMD        | FCH SMBus Controller         | 2     | i2c_pii... | 3A3B100E41 |
| 8086:0f12 | 1025:085f | Intel      | Atom Processor E3800 Seri... | 2     | i2c_i801   | 90FF435FAD |
| 8086:0f12 | 17aa:3695 | Intel      | Atom Processor E3800 Seri... | 2     |            | 08BB09B100 |
| 8086:0f12 | 17aa:36a8 | Intel      | Atom Processor E3800 Seri... | 2     | i2c_i801   | 5F6FF0EBDA |
| 8086:0f12 | 1854:0200 | Intel      | Atom Processor E3800 Seri... | 2     |            | 2128A4CD93 |
| 8086:1c22 | 1019:0777 | Intel      | 6 Series/C200 Series Chip... | 2     | i2c_i801   | 1F5B5C1D86 |
| 8086:1c22 | 1025:0492 | Intel      | 6 Series/C200 Series Chip... | 2     | i2c_i801   | D44BEF08F5 |
| 8086:1c22 | 1025:0608 | Intel      | 6 Series/C200 Series Chip... | 2     | i2c_i801   | BEDE9EC674 |
| 8086:1c22 | 1025:063f | Intel      | 6 Series/C200 Series Chip... | 2     | i2c_i801   | 5EBFC68D96 |
| 8086:1c22 | 1025:0640 | Intel      | 6 Series/C200 Series Chip... | 2     | i2c_i801   | 22317B4B49 |
| 8086:1c22 | 103c:3395 | Intel      | 6 Series/C200 Series Chip... | 2     | i2c_i801   | 02F1FBC843 |
| 8086:1c22 | 1043:1c22 | Intel      | 6 Series/C200 Series Chip... | 2     | i2c_i801   | DB3BBECDD0 |
| 8086:1c22 | 104d:908e | Intel      | 6 Series/C200 Series Chip... | 2     | i2c_i801   | 59BB8EC907 |
| 8086:1c22 | 17aa:3623 | Intel      | 6 Series/C200 Series Chip... | 2     | i2c_i801   | B98E1F49EA |
| 8086:1e22 | 1025:0792 | Intel      | 7 Series/C216 Chipset Fam... | 2     | i2c_i801   | 3D1389215D |
| 8086:1e22 | 104d:9097 | Intel      | 7 Series/C216 Chipset Fam... | 2     | i2c_i801   | 7685534B8E |
| 8086:1e22 | 1462:b062 | Intel      | 7 Series/C216 Chipset Fam... | 2     | i2c_i801   | 0FC1178D7D |
| 8086:2292 | 1025:098f | Intel      | Atom/Celeron/Pentium Proc... | 2     | i2c_i801   | 350CC83AC7 |
| 8086:2292 | 1025:1065 | Intel      | Atom/Celeron/Pentium Proc... | 2     | i2c_i801   | 21CA50C386 |
| 8086:2292 | 17aa:30dd | Intel      | Atom/Celeron/Pentium Proc... | 2     | i2c_i801   | C64BB03524 |
| 8086:2292 | 17aa:3637 | Intel      | Atom/Celeron/Pentium Proc... | 2     | i2c_i801   | 91FFB55E1F |
| 8086:2930 | 1025:0275 | Intel      | 82801I (ICH9 Family) SMBu... | 2     |            | 19FBB5D44C |
| 8086:3b30 | 1025:0297 | Intel      | 5 Series/3400 Series Chip... | 2     | i2c_i801   | 1E17CF76B7 |
| 8086:5ad4 | 103c:8304 | Intel      | Celeron N3350/Pentium N42... | 2     | i2c_i801   | A63E8373C4 |
| 8086:8c22 | 103c:18e6 | Intel      | 8 Series/C220 Series Chip... | 2     | i2c_i801   | C0BDA7E63F |
| 8086:8c22 | 103c:2179 | Intel      | 8 Series/C220 Series Chip... | 2     | i2c_i801   | 7B6E93783B |
| 8086:8c22 | 1462:ae67 | Intel      | 8 Series/C220 Series Chip... | 2     | i2c_i801   | 881CDBC376 |
| 8086:8c22 | 17aa:367b | Intel      | 8 Series/C220 Series Chip... | 2     | i2c_i801   | 3EBFFF7DAD |
| 8086:8c22 | 1b0a:0183 | Intel      | 8 Series/C220 Series Chip... | 2     | i2c_i801   | 78D39E18EF |
| 8086:8c22 | 1b0a:0188 | Intel      | 8 Series/C220 Series Chip... | 2     | i2c_i801   | A94F1201C4 |
| 8086:9ca2 | 1bc6:01ac | Intel      | Wildcat Point-LP SMBus Co... | 2     | i2c_i801   | 2146FDE0CF |
| 8086:9ca2 | 8086:7270 | Intel      | Wildcat Point-LP SMBus Co... | 2     | i2c_i801   | 906BCD4AC8 |
| 8086:a123 | 1028:06d4 | Intel      | 100 Series/C230 Series Ch... | 2     | i2c_i801   | 275E0EEAEF |
| 8086:a123 | 1028:075d | Intel      | 100 Series/C230 Series Ch... | 2     | i801_smbus | 404A8B3A68 |
| 8086:a123 | 103c:81b7 | Intel      | 100 Series/C230 Series Ch... | 2     | i2c_i801   | 447E6C6392 |
| 8086:a123 | 8086:a123 | Intel      | 100 Series/C230 Series Ch... | 2     | i2c_i801   | 4F5252C592 |
| 8086:a323 | 103c:84ee | Intel      | Cannon Lake PCH SMBus Con... | 2     |            | 5D5C8FEFBA |
| 1002:4385 | 1033:886f | AMD        | SBx00 SMBus Controller       | 1     | i2c_piix4  | 86771347FB |
| 1002:4385 | 1462:aa53 | AMD        | SBx00 SMBus Controller       | 1     | piix4_s... | 7BD55BD71D |
| 1002:4385 | 17aa:300f | ATI Tec... | SBx00 SMBus Controller       | 1     | sp5100_... | 1112BF63F0 |
| 1002:4385 | 17aa:3619 | AMD        | SBx00 SMBus Controller       | 1     | i2c_pii... | 70CA845CDF |
| 1002:4385 | 17aa:3629 | AMD        | SBx00 SMBus Controller       | 1     | i2c_pii... | 8F09E8179C |
| 1022:780b | 1025:0720 | AMD        | FCH SMBus Controller         | 1     | i2c_pii... | D3734872B2 |
| 1022:780b | 1028:0628 | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | A3E9972EEA |
| 1022:780b | 1028:074a | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | D07D321CCE |
| 1022:780b | 103c:2b0a | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | 499EA7DFBB |
| 1022:780b | 103c:2b13 | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | 8553F899D5 |
| 1022:780b | 103c:2b1f | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | F01E3C859D |
| 1022:780b | 103c:2b3b | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | A772887752 |
| 1022:780b | 1043:8589 | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | C8D8836613 |
| 1022:780b | 144d:c102 | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | 40AB94A580 |
| 1022:780b | 1462:aa5e | AMD        | FCH SMBus Controller         | 1     | i2c_pii... | 5DC25F1C8F |
| 1022:780b | 1462:aa81 | AMD        | FCH SMBus Controller         | 1     | i2c_pii... | 582AB9032D |
| 1022:780b | 1462:ac15 | AMD        | FCH SMBus Controller         | 1     | i2c_pii... | 227CCDA2A1 |
| 1022:780b | 17aa:3090 | AMD        | FCH SMBus Controller         | 1     | i2c_pii... | CD624C7BA5 |
| 1022:780b | 17aa:3670 | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | 46E2D4B676 |
| 1022:780b | 17aa:368f | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | 58DDD6F565 |
| 1022:780b | 17aa:36a5 | AMD        | FCH SMBus Controller         | 1     | i2c_pii... | C486FF05F5 |
| 1022:780b | 17aa:36ab | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | 89586A0608 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:284b | 106b:00a0 | Intel      | 82801H (ICH8 Family) HD A... | 16    | snd_hda... | 8889AFD8F1 |
| 8086:1c20 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 12    | snd_hda... | C88A6086FA |
| 10de:0ac0 | 10de:cb79 | Nvidia     | MCP79 High Definition Audio  | 10    | snd_hda... | 8361590CBD |
| 8086:1c20 | 17aa:365e | Intel      | 6 Series/C200 Series Chip... | 9     | snd_hda... | 338C59EF86 |
| 8086:8c20 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 9     | snd_hda... | F82FCD2051 |
| 1002:aa90 | 106b:aa90 | AMD        | Turks HDMI Audio [Radeon ... | 8     | snd_hda... | C88A6086FA |
| 8086:1c20 | 103c:2ac5 | Intel      | 6 Series/C200 Series Chip... | 8     | snd_hda... | A5E0E95D2C |
| 8086:3b56 | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 8     | snd_hda... | F0515A0217 |
| 8086:27d8 | 8384:7680 | Intel      | NM10/ICH7 Family High Def... | 7     | snd_hda... | B24608A945 |
| 8086:9d71 | 103c:84de | Intel      | Sunrise Point-LP HD Audio    | 6     | snd_hda... | 6B7FA4FF60 |
| 10de:0774 | 1025:0461 | Nvidia     | MCP72XE/MCP72P/MCP78U/MCP... | 5     | snd_hda... | 4CA7976A88 |
| 10de:0bea | 17aa:365e | Nvidia     | GF108 High Definition Aud... | 5     | snd_hda... | BAA91679D8 |
| 8086:1e20 | 144d:b091 | Intel      | 7 Series/C216 Chipset Fam... | 5     | snd_hda... | 857C8BE5D0 |
| 1002:9840 | 103c:8245 | AMD        | Kabini HDMI/DP Audio         | 4     | snd_hda... | 2D74D9A2EF |
| 1002:aa30 | 106b:aa30 | AMD        | RV770 HDMI Audio [Radeon ... | 4     | snd_hda... | A68B8E8206 |
| 1002:aa88 | 106b:aa88 | AMD        | Barts HDMI Audio [Radeon ... | 4     | snd_hda... | 561B991E16 |
| 1002:aa90 | 144d:b091 | AMD        | Turks HDMI Audio [Radeon ... | 4     | snd_hda... | 16D6FCA3F1 |
| 1022:780d | 103c:8245 | AMD        | FCH Azalia Controller        | 4     | snd_hda... | 2D74D9A2EF |
| 10de:0bea | 104d:907e | Nvidia     | GF108 High Definition Aud... | 4     | snd_hda... | 4A2DA5DD1B |
| 10de:0bea | 17aa:366c | Nvidia     | GF108 High Definition Aud... | 4     | snd_hda... | A922BB8973 |
| 8086:0c0c | 8086:2010 | Intel      | Xeon E3-1200 v3/4th Gen C... | 4     | snd_hda... | 647613F22B |
| 8086:1c20 | 104d:907e | Intel      | 6 Series/C200 Series Chip... | 4     | snd_hda... | 4A2DA5DD1B |
| 8086:1c20 | 17aa:366c | Intel      | 6 Series/C200 Series Chip... | 4     | snd_hda... | A922BB8973 |
| 8086:3a3e | 1025:0266 | Intel      | 82801JI (ICH10 Family) HD... | 4     | snd_hda... | A2FF4426C9 |
| 8086:5a98 | 17aa:36c4 | Intel      | Celeron N3350/Pentium N42... | 4     | snd_hda... | 00A1738003 |
| 1002:4383 | 1bfd:0001 | AMD        | SBx00 Azalia (Intel HDA)     | 3     | snd_hda... | 09FE5E4566 |
| 1002:aa38 | 106b:aa38 | AMD        | RV710/730 HDMI Audio [Rad... | 3     | snd_hda... | F0515A0217 |
| 10de:0e1b |           | Nvidia     | GK107 HDMI Audio Controller  | 3     | snd_hda... | C6F2E8BC12 |
| 8086:0d0c | 106b:0122 | Intel      | Crystal Well HD Audio Con... | 3     | snd_hda... | 3FFA6AA435 |
| 8086:0f04 | 1b50:5709 | Intel      | Atom Processor Z36xxx/Z37... | 3     | snd_hda... | E6BCDB1E4D |
| 8086:1c20 | 1028:0511 | Intel      | 6 Series/C200 Series Chip... | 3     | snd_hda... | 8672A3F85D |
| 8086:1c20 | 103c:2aed | Intel      | 6 Series/C200 Series Chip... | 3     | snd_hda... | 00FCD6CB57 |
| 8086:1c20 | 104d:9083 | Intel      | 6 Series/C200 Series Chip... | 3     | snd_hda... | B4CF237F88 |
| 8086:1e20 | 1028:0548 | Intel      | 7 Series/C216 Chipset Fam... | 3     | snd_hda... | 229BA614EC |
| 8086:1e20 | 17aa:3671 | Intel      | 7 Series/C216 Chipset Fam... | 3     | snd_hda... | 906A62D75E |
| 8086:1e20 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 3     | snd_hda... | CD3C0C4583 |
| 8086:27d8 | 17aa:3602 | Intel      | NM10/ICH7 Family High Def... | 3     | snd_hda... | 55C2F8E26B |
| 8086:27d8 | 17aa:3610 | Intel      | NM10/ICH7 Family High Def... | 3     | snd_hda... | E98AA97F27 |
| 8086:3a3e | 104d:9060 | Intel      | 82801JI (ICH10 Family) HD... | 3     | snd_hda... | 05CFF66AC2 |
| 8086:3b56 | 1025:045c | Intel      | 5 Series/3400 Series Chip... | 3     | snd_hda... | FF848E7FFB |
| 8086:8c20 | 17aa:3685 | Intel      | 8 Series/C220 Series Chip... | 3     | snd_hda... | 647613F22B |
| 8086:9d71 | 1025:1287 | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | C861864ED7 |
| 8086:9d71 | 1028:0754 | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | 7CC5A36861 |
| 8086:9d71 | 1028:0852 | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | 5A27DEAF8A |
| 8086:a170 | 17aa:30ba | Intel      | 100 Series/C230 Series Ch... | 3     | snd_hda... | 818DCABBD8 |
| 8086:a170 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 3     | snd_hda... | 5984E1BBAC |
| 1002:15b3 | 103c:8381 | AMD        | High Definition Audio Con... | 2     | snd_hda... | 83034BC0E9 |
| 1002:15b3 | 17aa:36be | AMD        | High Definition Audio Con... | 2     | snd_hda... | 3A3B100E41 |
| 1002:1714 | 1025:0642 | AMD        | BeaverCreek HDMI Audio [R... | 2     | snd_hda... | 973EEE4869 |
| 1002:aa58 | 106b:aa58 | AMD        | Juniper HDMI Audio [Radeo... | 2     | snd_hda... | 6149AFDA8F |
| 1002:aa68 | 1002:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 2     | snd_hda... | 09FE5E4566 |
| 1002:aac0 | 0000:aac0 | AMD        | Tobago HDMI Audio [Radeon... | 2     | snd_hda... | 48BADA4AFA |
| 1022:157a | 1028:07e3 | AMD        | Family 15h (Models 60h-6f... | 2     | snd_hda... | 4EB59BF315 |
| 1022:157a | 103c:8381 | AMD        | Family 15h (Models 60h-6f... | 2     | snd_hda... | 83034BC0E9 |
| 1022:157a | 17aa:36be | AMD        | Family 15h (Models 60h-6f... | 2     | snd_hda... | 3A3B100E41 |
| 1022:780d | 1025:0642 | AMD        | FCH Azalia Controller        | 2     | snd_hda... | 973EEE4869 |
| 1022:780d | 103c:2afc | AMD        | FCH Azalia Controller        | 2     | snd_hda... | 346458F274 |
| 10de:0be2 | 10de:0688 | Nvidia     | GT216 HDMI Audio Controller  | 2     | snd_hda... | A2FF4426C9 |
| 10de:0bea | 104d:908e | Nvidia     | GF108 High Definition Aud... | 2     | snd_hda... | 59BB8EC907 |
| 10de:0bea | 10de:0bea | Nvidia     | GF108 High Definition Aud... | 2     | snd_hda... | DB3BBECDD0 |
| 10de:0bea | 174b:7162 | Nvidia     | GF108 High Definition Aud... | 2     | snd_hda... | 6A47F8B3A3 |
| 10de:0e0a |           | Nvidia     | GK104 HDMI Audio Controller  | 2     | snd_hda... | F82FCD2051 |
| 8086:0c0c | 103c:18e6 | Intel      | Xeon E3-1200 v3/4th Gen C... | 2     | snd_hda... | C0BDA7E63F |
| 8086:0c0c | 103c:2179 | Intel      | Xeon E3-1200 v3/4th Gen C... | 2     | snd_hda... | 7B6E93783B |
| 8086:0c0c | 1462:ae67 | Intel      | Xeon E3-1200 v3/4th Gen C... | 2     | snd_hda... | 881CDBC376 |
| 8086:0c0c | 17aa:367b | Intel      | Xeon E3-1200 v3/4th Gen C... | 2     | snd_hda... | 3EBFFF7DAD |
| 8086:0c0c | 1b0a:0183 | Intel      | Xeon E3-1200 v3/4th Gen C... | 2     | snd_hda... | 78D39E18EF |
| 8086:0c0c | 1b0a:0188 | Intel      | Xeon E3-1200 v3/4th Gen C... | 2     | snd_hda... | A94F1201C4 |
| 8086:0f04 | 1025:085f | Intel      | Atom Processor Z36xxx/Z37... | 2     | snd_hda... | 90FF435FAD |
| 8086:0f04 | 17aa:3695 | Intel      | Atom Processor Z36xxx/Z37... | 2     | snd_hda... | 08BB09B100 |
| 8086:0f04 | 17aa:36a8 | Intel      | Atom Processor Z36xxx/Z37... | 2     | snd_hda... | 5F6FF0EBDA |
| 8086:0f04 | 1854:0200 | Intel      | Atom Processor Z36xxx/Z37... | 2     | snd_hda... | 2128A4CD93 |
| 8086:160c | 106b:0146 | Intel      | Broadwell-U Audio Controller | 2     | snd_hda... | 906BCD4AC8 |
| 8086:160c | 1bc6:01ac | Intel      | Broadwell-U Audio Controller | 2     | snd_hda... | 2146FDE0CF |
| 8086:1c20 | 1019:0777 | Intel      | 6 Series/C200 Series Chip... | 2     | snd_hda... | 1F5B5C1D86 |
| 8086:1c20 | 1025:0492 | Intel      | 6 Series/C200 Series Chip... | 2     | snd_hda... | D44BEF08F5 |
| 8086:1c20 | 1025:0608 | Intel      | 6 Series/C200 Series Chip... | 2     | snd_hda... | BEDE9EC674 |
| 8086:1c20 | 1025:063f | Intel      | 6 Series/C200 Series Chip... | 2     | snd_hda... | 5EBFC68D96 |
| 8086:1c20 | 1025:0640 | Intel      | 6 Series/C200 Series Chip... | 2     | snd_hda... | 22317B4B49 |
| 8086:1c20 | 103c:3395 | Intel      | 6 Series/C200 Series Chip... | 2     | snd_hda... | 02F1FBC843 |
| 8086:1c20 | 1043:8519 | Intel      | 6 Series/C200 Series Chip... | 2     | snd_hda... | DB3BBECDD0 |
| 8086:1c20 | 104d:908e | Intel      | 6 Series/C200 Series Chip... | 2     | snd_hda... | 59BB8EC907 |
| 8086:1c20 | 1071:0675 | Intel      | 6 Series/C200 Series Chip... | 2     | snd_hda... | DA0C20FDF7 |
| 8086:1c20 | 17aa:3623 | Intel      | 6 Series/C200 Series Chip... | 2     | snd_hda... | B98E1F49EA |
| 8086:1e20 | 1025:0792 | Intel      | 7 Series/C216 Chipset Fam... | 2     | snd_hda... | 3D1389215D |
| 8086:1e20 | 104d:9097 | Intel      | 7 Series/C216 Chipset Fam... | 2     | snd_hda... | 7685534B8E |
| 8086:1e20 | 1462:b062 | Intel      | 7 Series/C216 Chipset Fam... | 2     | snd_hda... | 0FC1178D7D |
| 8086:2284 | 1025:098f | Intel      | Atom/Celeron/Pentium Proc... | 2     | snd_hda... | 350CC83AC7 |
| 8086:2284 | 1025:1065 | Intel      | Atom/Celeron/Pentium Proc... | 2     | snd_hda... | 21CA50C386 |
| 8086:2284 | 17aa:30dd | Intel      | Atom/Celeron/Pentium Proc... | 2     | snd_hda... | C64BB03524 |
| 8086:2284 | 17aa:3637 | Intel      | Atom/Celeron/Pentium Proc... | 2     | snd_hda... | 91FFB55E1F |
| 8086:293e | 1025:0275 | Intel      | 82801I (ICH9 Family) HD A... | 2     | snd_hda... | 19FBB5D44C |
| 8086:5a98 | 103c:8304 | Intel      | Celeron N3350/Pentium N42... | 2     | snd_hda... | A63E8373C4 |
| 8086:8c20 | 103c:18e6 | Intel      | 8 Series/C220 Series Chip... | 2     | snd_hda... | C0BDA7E63F |
| 8086:8c20 | 103c:2179 | Intel      | 8 Series/C220 Series Chip... | 2     | snd_hda... | 7B6E93783B |
| 8086:8c20 | 1462:ae67 | Intel      | 8 Series/C220 Series Chip... | 2     | snd_hda... | 881CDBC376 |
| 8086:8c20 | 17aa:367b | Intel      | 8 Series/C220 Series Chip... | 2     | snd_hda... | 3EBFFF7DAD |
| 8086:8c20 | 1b0a:0183 | Intel      | 8 Series/C220 Series Chip... | 2     | snd_hda... | 78D39E18EF |
| 8086:8c20 | 1b0a:0188 | Intel      | 8 Series/C220 Series Chip... | 2     | snd_hda... | A94F1201C4 |
| 8086:9ca0 | 1bc6:01ac | Intel      | Wildcat Point-LP High Def... | 2     | snd_hda... | 2146FDE0CF |

### Storage (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1106:401a | 17aa:3608 | VIA Tec... | VIA Card Reader Host Cont... | 1     |            | EA55AE13AC |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2829 | 106b:00a0 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 13    | ahci       | 8889AFD8F1 |
| 8086:1c02 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 12    | ahci       | C88A6086FA |
| 8086:1c02 | 103c:2ac5 | Intel      | 6 Series/C200 Series Chip... | 8     | ahci       | A5E0E95D2C |
| 8086:1c02 | 17aa:365e | Intel      | 6 Series/C200 Series Chip... | 8     | ahci       | 338C59EF86 |
| 10de:0ab9 | 10de:cb79 | Nvidia     | MCP79 AHCI Controller        | 7     | ahci       | 5BA8F4B10F |
| 8086:3b22 | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 7     | ahci       | F0515A0217 |
| 10de:0ad4 | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] AHC... | 5     | ahci       | 4CA7976A88 |
| 144d:a801 | 144d:a801 | Samsung... | Electronics SATA controller  | 5     | ahci       | 48BADA4AFA |
| 8086:1e02 | 144d:b091 | Intel      | 7 Series/C210 Series Chip... | 5     | ahci       | 857C8BE5D0 |
| 8086:8c02 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 5     | ahci       | F82FCD2051 |
| 1022:7801 | 103c:8245 | AMD        | FCH SATA Controller [AHCI... | 4     | ahci       | 2D74D9A2EF |
| 8086:1c02 | 17aa:366c | Intel      | 6 Series/C200 Series Chip... | 4     | ahci       | A922BB8973 |
| 8086:1c03 | 104d:907e | Intel      | 6 Series/C200 Series Chip... | 4     | ahci       | 4A2DA5DD1B |
| 8086:3a22 | 1025:0266 | Intel      | 82801JI (ICH10 Family) SA... | 4     | ahci       | A2FF4426C9 |
| 8086:5ae3 | 17aa:36c4 | Intel      | Celeron N3350/Pentium N42... | 4     | ahci       | 00A1738003 |
| 8086:9d03 | 8086:9d03 | Intel      | Sunrise Point-LP SATA Con... | 4     | ahci       | 5F28079AA4 |
| 1002:4391 | 1002:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 3     | ahci       | 09FE5E4566 |
| 8086:0f23 |           | Intel      | Atom Processor E3800 Seri... | 3     | ahci       | E6BCDB1E4D |
| 8086:1c02 | 1028:0511 | Intel      | 6 Series/C200 Series Chip... | 3     | ahci       | 8672A3F85D |
| 8086:1c02 | 8086:1c02 | Intel      | 6 Series/C200 Series Chip... | 3     | ahci       | 19478FF625 |
| 8086:1c03 | 104d:9083 | Intel      | 6 Series/C200 Series Chip... | 3     | ahci       | B4CF237F88 |
| 8086:1e02 | 1028:0548 | Intel      | 7 Series/C210 Series Chip... | 3     | ahci       | 229BA614EC |
| 8086:1e02 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 3     | ahci       | CD3C0C4583 |
| 8086:3b22 | 1025:045c | Intel      | 5 Series/3400 Series Chip... | 3     | ahci       | FF848E7FFB |
| 8086:8c02 | 17aa:3685 | Intel      | 8 Series/C220 Series Chip... | 3     | ahci       | 647613F22B |
| 8086:8c03 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 3     | ahci       | 3FFA6AA435 |
| 8086:9d03 | 1025:1287 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | C861864ED7 |
| 8086:9d03 | 1028:0754 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 7CC5A36861 |
| 8086:9d03 | 1028:0852 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 5A27DEAF8A |
| 8086:a102 | 17aa:30ba | Intel      | Q170/Q150/B150/H170/H110/... | 3     | ahci       | 818DCABBD8 |
| 8086:a102 | 8086:7270 | Intel      | Q170/Q150/B150/H170/H110/... | 3     | ahci       | 5984E1BBAC |
| 1002:4391 | 1043:8431 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 2     | ahci       | F1E1BF19CC |
| 1022:43b7 | 1b21:1062 | AMD        | 300 Series Chipset SATA C... | 2     | ahci       | 4EB59BF315 |
| 1022:7801 | 1025:0642 | AMD        | FCH SATA Controller [AHCI... | 2     | ahci       | 973EEE4869 |
| 1022:7801 | 103c:2afc | AMD        | FCH SATA Controller [AHCI... | 2     | ahci       | 346458F274 |
| 1022:7901 | 1028:07e3 | AMD        | FCH SATA Controller [AHCI... | 2     | ahci       | 4EB59BF315 |
| 1022:7901 | 103c:8381 | AMD        | FCH SATA Controller [AHCI... | 2     | ahci       | 7CD9296ED7 |
| 1022:7901 | 17aa:36be | AMD        | FCH SATA Controller [AHCI... | 2     | ahci       | 3A3B100E41 |
| 8086:0f23 | 17aa:3695 | Intel      | Atom Processor E3800 Seri... | 2     | ahci       | 08BB09B100 |
| 8086:0f23 | 17aa:36a8 | Intel      | Atom Processor E3800 Seri... | 2     | ahci       | 5F6FF0EBDA |
| 8086:0f23 | 1854:0200 | Intel      | Atom Processor E3800 Seri... | 2     | ahci       | 2128A4CD93 |
| 8086:1c02 | 1025:0492 | Intel      | 6 Series/C200 Series Chip... | 2     | ahci       | D44BEF08F5 |
| 8086:1c02 | 1025:0608 | Intel      | 6 Series/C200 Series Chip... | 2     | ahci       | BEDE9EC674 |
| 8086:1c02 | 1025:063f | Intel      | 6 Series/C200 Series Chip... | 2     | ahci       | 5EBFC68D96 |
| 8086:1c02 | 1025:0640 | Intel      | 6 Series/C200 Series Chip... | 2     | ahci       | 22317B4B49 |
| 8086:1c02 | 103c:2aed | Intel      | 6 Series/C200 Series Chip... | 2     | ahci       | 00FCD6CB57 |
| 8086:1c02 | 103c:3395 | Intel      | 6 Series/C200 Series Chip... | 2     | ahci       | 02F1FBC843 |
| 8086:1c02 | 1043:1c02 | Intel      | 6 Series/C200 Series Chip... | 2     | ahci       | DB3BBECDD0 |
| 8086:1c02 | 17aa:3623 | Intel      | 6 Series/C200 Series Chip... | 2     | ahci       | B98E1F49EA |
| 8086:1c03 | 104d:908e | Intel      | 6 Series/C200 Series Chip... | 2     | ahci       | 59BB8EC907 |
| 8086:1e03 | 1025:0792 | Intel      | 7 Series Chipset Family 6... | 2     | ahci       | 3D1389215D |
| 8086:1e03 | 104d:9097 | Intel      | 7 Series Chipset Family 6... | 2     | ahci       | 7685534B8E |
| 8086:1e03 | 1462:b062 | Intel      | 7 Series Chipset Family 6... | 2     | ahci       | 0FC1178D7D |
| 8086:22a3 | 1025:098f | Intel      | Atom/Celeron/Pentium Proc... | 2     | ahci       | 350CC83AC7 |
| 8086:22a3 | 1025:1065 | Intel      | Atom/Celeron/Pentium Proc... | 2     | ahci       | 21CA50C386 |
| 8086:22a3 | 17aa:30dd | Intel      | Atom/Celeron/Pentium Proc... | 2     | ahci       | C64BB03524 |
| 8086:22a3 | 17aa:3637 | Intel      | Atom/Celeron/Pentium Proc... | 2     | ahci       | 91FFB55E1F |
| 8086:3b22 | 1025:0297 | Intel      | 5 Series/3400 Series Chip... | 2     | ahci       | 1E17CF76B7 |
| 8086:5ae3 | 103c:8304 | Intel      | Celeron N3350/Pentium N42... | 2     | ahci       | A63E8373C4 |
| 8086:8c02 | 103c:18e6 | Intel      | 8 Series/C220 Series Chip... | 2     | ahci       | C0BDA7E63F |
| 8086:8c02 | 103c:2179 | Intel      | 8 Series/C220 Series Chip... | 2     | ahci       | 7B6E93783B |
| 8086:8c02 | 17aa:367b | Intel      | 8 Series/C220 Series Chip... | 2     | ahci       | 3EBFFF7DAD |
| 8086:8c02 | 1b0a:0188 | Intel      | 8 Series/C220 Series Chip... | 2     | ahci       | A94F1201C4 |
| 8086:8c03 | 1462:ae67 | Intel      | 8 Series/C220 Series Chip... | 2     | ahci       | 881CDBC376 |
| 8086:9c83 | 1bc6:01ac | Intel      | Wildcat Point-LP SATA Con... | 2     | ahci       | 2146FDE0CF |
| 8086:9c83 | 8086:7270 | Intel      | Wildcat Point-LP SATA Con... | 2     | ahci       | 906BCD4AC8 |
| 8086:9d03 | 103c:84de | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 94BD16E6CB |
| 8086:a102 | 1028:06d4 | Intel      | Q170/Q150/B150/H170/H110/... | 2     | ahci       | 275E0EEAEF |
| 8086:a102 | 103c:81b7 | Intel      | Q170/Q150/B150/H170/H110/... | 2     | ahci       | 447E6C6392 |
| 8086:a352 | 103c:84ee | Intel      | Cannon Lake PCH SATA AHCI... | 2     | ahci       | 5D5C8FEFBA |
| 1002:4380 | 1033:886f | AMD        | SB600 Non-Raid-5 SATA        | 1     | ahci       | 86771347FB |
| 1002:4390 | 17aa:3619 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 70CA845CDF |
| 1002:4390 | 17aa:3629 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 8F09E8179C |
| 1002:4391 | 1028:0479 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 2E89DCF36E |
| 1002:4391 | 1462:aa53 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 7BD55BD71D |
| 1002:4391 | 17aa:300f | ATI Tec... | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 1112BF63F0 |
| 1022:7800 | 1462:aa5e | AMD        | FCH SATA Controller [IDE ... | 1     | ahci       | 5DC25F1C8F |
| 1022:7801 | 1025:0720 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | D3734872B2 |
| 1022:7801 | 1028:0628 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | A3E9972EEA |
| 1022:7801 | 1028:074a | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | D07D321CCE |
| 1022:7801 | 103c:2b0a | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 499EA7DFBB |
| 1022:7801 | 103c:2b13 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 8553F899D5 |
| 1022:7801 | 103c:2b1f | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | F01E3C859D |
| 1022:7801 | 103c:2b3b | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | A772887752 |
| 1022:7801 | 1043:8589 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | C8D8836613 |
| 1022:7801 | 144d:c102 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 40AB94A580 |
| 1022:7801 | 1462:aa81 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 582AB9032D |
| 1022:7801 | 1462:ac15 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 227CCDA2A1 |
| 1022:7801 | 17aa:3090 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | CD624C7BA5 |
| 1022:7801 | 17aa:3670 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 46E2D4B676 |
| 1022:7801 | 17aa:368f | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 58DDD6F565 |
| 1022:7801 | 17aa:36a5 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | C486FF05F5 |
| 1022:7801 | 17aa:36ab | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 89586A0608 |
| 1022:7900 | 103c:8381 | AMD        | FCH SATA Controller [IDE ... | 1     | ahci       | 83034BC0E9 |
| 1022:7901 | 1028:0855 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | DACA9432F8 |
| 1022:7901 | 103c:81b9 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 15C46542B5 |
| 1022:7901 | 103c:8430 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 2B0CDC9F2B |
| 1022:7901 | 17aa:36bd | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | E1331356C7 |
| 1022:7901 | 17aa:36c6 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 5DA9F63B49 |
| 1022:7901 | 17aa:36da | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | DE2A851C8F |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2850 | 106b:00a0 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 16    | pata_acpi  | 8889AFD8F1 |
| 8086:27c4 | 8086:7270 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 8     | pata_acpi  | B24608A945 |
| 8086:27df | 8086:7270 | Intel      | 82801G (ICH7 Family) IDE ... | 8     | pata_acpi  | B24608A945 |
| 1002:439c | 1002:439c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 5     | pata_at... | F1E1BF19CC |
| 10de:0ab5 | 10de:cb79 | Nvidia     | MCP79 SATA Controller        | 3     | ahci, p... | 8361590CBD |
| 8086:27c0 | 17aa:3602 | Intel      | NM10/ICH7 Family SATA Con... | 3     | ata_pii... | 55C2F8E26B |
| 8086:27c0 | 17aa:3610 | Intel      | NM10/ICH7 Family SATA Con... | 3     | ata_pii... | E98AA97F27 |
| 8086:2828 | 106b:00a0 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 3     | pata_acpi  | 1527CB5135 |
| 8086:3a20 | 104d:9060 | Intel      | 82801JI (ICH10 Family) 4 ... | 3     | ata_pii... | 05CFF66AC2 |
| 8086:1e01 | 17aa:3671 | Intel      | 7 Series Chipset Family 4... | 2     | ata_pii... | 906A62D75E |
| 8086:1e09 | 17aa:3671 | Intel      | 7 Series Chipset Family 2... | 2     | ata_pii... | 906A62D75E |
| 8086:8c00 | 1b0a:0183 | Intel      | 8 Series/C220 Series Chip... | 2     | ata_pii... | 78D39E18EF |
| 8086:8c08 | 1b0a:0183 | Intel      | 8 Series/C220 Series Chip... | 2     | ata_pii... | 78D39E18EF |
| 1002:438c | 1033:886f | AMD        | SB600 IDE                    | 1     | pata_at... | 86771347FB |
| 1002:439c | 1462:aa53 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | pata_at... | 7BD55BD71D |
| 1002:439c | 17aa:3629 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | pata_at... | 8F09E8179C |
| 1022:780c | 1043:8589 | AMD        | FCH IDE Controller           | 1     | pata_at... | C8D8836613 |
| 197b:2363 | 1462:ae11 | JMicron... | JMB363 SATA/IDE Controller   | 1     | ahci       | 17AD880F72 |
| 8086:0f21 | 1025:085f | Intel      | Atom Processor E3800 Seri... | 1     | ata_pii... | 7923ACCECA |
| 8086:1c00 | 1019:0777 | Intel      | 6 Series/C200 Series Chip... | 1     | ata_pii... | 79832DA9DA |
| 8086:1c00 | 103c:2aed | Intel      | 6 Series/C200 Series Chip... | 1     | ata_pii... | E2ADA83EE9 |
| 8086:1c00 | 17aa:365e | Intel      | 6 Series/C200 Series Chip... | 1     | ata_pii... | 098D8022D0 |
| 8086:1c08 | 1019:0777 | Intel      | 6 Series/C200 Series Chip... | 1     | ata_pii... | 79832DA9DA |
| 8086:1c08 | 103c:2aed | Intel      | 6 Series/C200 Series Chip... | 1     | ata_pii... | E2ADA83EE9 |
| 8086:1c08 | 17aa:365e | Intel      | 6 Series/C200 Series Chip... | 1     | ata_pii... | 098D8022D0 |
| 8086:1e01 | 1462:a953 | Intel      | 7 Series Chipset Family 4... | 1     | ata_pii... | 1EAD53F6C2 |
| 8086:27c0 | 1462:7592 | Intel      | NM10/ICH7 Family SATA Con... | 1     | ata_pii... | DEABFE7945 |
| 8086:27c0 | 1462:ae11 | Intel      | NM10/ICH7 Family SATA Con... | 1     | ata_pii... | 17AD880F72 |
| 8086:27df | 1462:ae11 | Intel      | 82801G (ICH7 Family) IDE ... | 1     | ata_pii... | 17AD880F72 |
| 8086:2928 | 1025:0275 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 1     | pata_acpi  | 19FBB5D44C |
| 8086:2928 | 1043:833f | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 1     | ata_pii... | AADAAE6450 |
| 8086:3b20 | 1462:ae31 | Intel      | 5 Series/3400 Series Chip... | 1     | ata_pii... | CBD910EA06 |
| 8086:3b20 | 17aa:306a | Intel      | 5 Series/3400 Series Chip... | 1     | ata_piix   | F15D263E67 |
| 8086:3b20 | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 1     | ata_pii... | 3FDB026301 |
| 8086:3b26 | 17aa:306a | Intel      | 5 Series/3400 Series Chip... | 1     | ata_piix   | F15D263E67 |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 2     | nvme       | 404A8B3A68 |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | Non-Volatile memory contr... | 2     | nvme       | 5D5C8FEFBA |
| 106b:2001 | 106b:2001 | Apple      | S1X NVMe Controller          | 1     | nvme       | 5984E1BBAC |
| 1179:0113 | 1179:0001 | Toshiba... | BG3 NVMe SSD Controller      | 1     | nvme       | 8269929E09 |
| 1179:0115 | 1179:0001 | Toshiba... | XG4 NVMe SSD Controller      | 1     | nvme       | F41BD5BF5B |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 1     | nvme       | 4EB59BF315 |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/PC SN720 NV... | 1     | nvme       | 2BF103DD36 |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 1     | nvme       | D77183679A |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:282a | 103c:84de | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 6B7FA4FF60 |
| 8086:2822 | 1028:075d | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | F41BD5BF5B |
| 8086:2822 | 1028:079e | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | 2BF103DD36 |
| 8086:2822 | 103c:838b | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | AC62725ABE |
| 8086:282a | 1028:0954 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 8740133E10 |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1513 | 2222:1111 | Intel      | CV82524 Thunderbolt Contr... | 12    | pcieport   | C88A6086FA |
| 8086:156c |           | Intel      | DSL5520 Thunderbolt 2 NHI... | 7     | thunder... | 5984E1BBAC |
| 8086:d150 |           | Intel      | Core Processor QPI Link      | 5     |            | 63741AC6DC |
| 8086:d151 |           | Intel      | Core Processor QPI Routin... | 5     |            | 63741AC6DC |
| 8086:d155 |           | Intel      | Core Processor System Man... | 5     |            | 63741AC6DC |
| 8086:d156 |           | Intel      | Core Processor Semaphore ... | 5     |            | 63741AC6DC |
| 8086:d157 |           | Intel      | Core Processor System Con... | 5     |            | 63741AC6DC |
| 8086:d158 |           | Intel      | Core Processor Miscellane... | 5     |            | 63741AC6DC |
| 1180:e232 | 104d:907e | Ricoh      | PCIe Memory Stick Host Co... | 4     |            | 4A2DA5DD1B |
| 197b:2382 | 1025:0266 | JMicron... | SD/MMC Host Controller       | 4     | sdhci_pci  | A2FF4426C9 |
| 197b:2383 | 1025:0266 | JMicron... | MS Host Controller           | 4     | jmb38x_ms  | A2FF4426C9 |
| 8086:1911 | 8086:1911 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | 4F5252C592 |
| 1180:e230 | 104d:9060 | Ricoh      | R5U2xx (R5U230 / R5U231 /... | 3     |            | 05CFF66AC2 |
| 1180:e232 | 104d:9083 | Ricoh      | PCIe Memory Stick Host Co... | 3     |            | B4CF237F88 |
| 197b:2382 | 17aa:3602 | JMicron... | SD/MMC Host Controller       | 3     | sdhci_pci  | 55C2F8E26B |
| 197b:2383 | 17aa:3602 | JMicron... | MS Host Controller           | 3     | jmb38x_ms  | 55C2F8E26B |
| 197b:2384 | 17aa:3602 | JMicron... | xD Host Controller           | 3     |            | 55C2F8E26B |
| 8086:1911 | 1025:1287 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | C861864ED7 |
| 8086:1911 | 1028:0754 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | 7CC5A36861 |
| 8086:1911 | 1028:0852 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | 5A27DEAF8A |
| 1180:e232 | 104d:908e | Ricoh      | PCIe Memory Stick Host Co... | 2     |            | 59BB8EC907 |
| 1180:e232 | 104d:9097 | Ricoh      | PCIe Memory Stick Host Co... | 2     |            | 7685534B8E |
| 197b:2382 | 1025:0275 | JMicron... | SD/MMC Host Controller       | 2     | sdhci_pci  | 19FBB5D44C |
| 197b:2382 | 1025:0608 | JMicron... | SD/MMC Host Controller       | 2     | sdhci_pci  | BEDE9EC674 |
| 197b:2382 | 1043:842d | JMicron... | SD/MMC Host Controller       | 2     | sdhci_pci  | F1E1BF19CC |
| 197b:2383 | 1025:0275 | JMicron... | MS Host Controller           | 2     | jmb38x_ms  | 19FBB5D44C |
| 197b:2383 | 1025:0608 | JMicron... | MS Host Controller           | 2     | jmb38x_ms  | BEDE9EC674 |
| 197b:2392 | 1043:84c1 | JMicron... | SD/MMC Host Controller       | 2     | sdhci_pci  | DB3BBECDD0 |
| 8086:1911 | 103c:84ee | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 5D5C8FEFBA |
| 8086:3190 |           | Intel      | Celeron/Pentium Silver Pr... | 2     |            | 7F0055E131 |
| 1180:0592 | 1033:886f | Ricoh      | R5C592 Memory Stick Bus H... | 1     | r592       | 86771347FB |
| 1180:0852 | 1033:886f | Ricoh      | xD-Picture Card Controller   | 1     | r852       | 86771347FB |
| 197b:2382 | 1025:039d | JMicron... | SD/MMC Host Controller       | 1     | sdhci_pci  | A629A81791 |
| 197b:2382 | 103c:1489 | JMicron... | SD/MMC Host Controller       | 1     | sdhci_pci  | A6305AD3A0 |
| 197b:2382 | 1043:842e | JMicron... | SD/MMC Host Controller       | 1     | sdhci_pci  | E0910009B1 |
| 197b:2383 | 1025:039d | JMicron... | MS Host Controller           | 1     | jmb38x_ms  | A629A81791 |
| 197b:2383 | 103c:1489 | JMicron... | MS Host Controller           | 1     | jmb38x_ms  | A6305AD3A0 |
| 197b:2384 | 103c:1489 | JMicron... | xD Host Controller           | 1     |            | A6305AD3A0 |
| 8086:1568 | 2222:1111 | Intel      | DSL4510 Thunderbolt NHI [... | 1     |            | 99683A7632 |
| 8086:15d2 | 8086:0000 | Intel      | JHL6540 Thunderbolt 3 NHI... | 1     | thunder... | 39AFD1D7B1 |
| 8086:1911 | 1025:1063 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 057A5601FF |
| 8086:1911 | 1028:0851 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 05D6B79D2F |
| 8086:1911 | 1028:0954 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 8740133E10 |
| 8086:1911 | 1043:1241 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 4313964FA7 |
| 8086:1911 | 1071:0752 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 3BDFB07582 |
| 8086:1911 | 1462:aac1 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | D77183679A |
| 8086:1911 | 1462:aea1 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | E033B6FBEA |
| 8086:1911 | 17aa:3123 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 943F3319E9 |
| 8086:1911 | 17aa:313d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 5BCA9F711E |
| 8086:1911 | 17aa:36f4 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 6543F3C4AF |
| 8086:3190 | 17aa:36ed | Intel      | Celeron/Pentium Silver Pr... | 1     |            | 8DFF428CAB |
| 8086:3190 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     |            | B4AB9671B3 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2830 | 106b:00a0 | Intel      | 82801H (ICH8 Family) USB ... | 16    | uhci_hcd   | 8889AFD8F1 |
| 8086:2831 | 106b:00a0 | Intel      | 82801H (ICH8 Family) USB ... | 16    | uhci_hcd   | 8889AFD8F1 |
| 8086:2832 | 106b:00a0 | Intel      | 82801H (ICH8 Family) USB ... | 16    | uhci_hcd   | 8889AFD8F1 |
| 8086:2834 |           | Intel      | 82801H (ICH8 Family) USB ... | 16    | uhci_hcd   | 8889AFD8F1 |
| 8086:2835 | 106b:00a0 | Intel      | 82801H (ICH8 Family) USB ... | 16    | uhci_hcd   | 8889AFD8F1 |
| 8086:2836 | 106b:00a0 | Intel      | 82801H (ICH8 Family) USB2... | 16    | ehci_pci   | 8889AFD8F1 |
| 8086:283a | 106b:00a0 | Intel      | 82801H (ICH8 Family) USB2... | 16    | ehci_pci   | 8889AFD8F1 |
| 8086:1c26 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 12    | ehci_pci   | C88A6086FA |
| 8086:1c27 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 12    | uhci_hcd   | C88A6086FA |
| 8086:1c2c | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 12    | uhci_hcd   | C88A6086FA |
| 8086:1c2d | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 12    | ehci_pci   | C88A6086FA |
| 10de:0aa5 | 10de:cb79 | Nvidia     | MCP79 OHCI USB 1.1 Contro... | 10    | ohci_pci   | 8361590CBD |
| 10de:0aa6 | 10de:cb79 | Nvidia     | MCP79 EHCI USB 2.0 Contro... | 10    | ehci_pci   | 8361590CBD |
| 10de:0aa7 | 10de:cb79 | Nvidia     | MCP79 OHCI USB 1.1 Contro... | 10    | ohci_pci   | 8361590CBD |
| 10de:0aa9 | 10de:cb79 | Nvidia     | MCP79 EHCI USB 2.0 Contro... | 10    | ehci_pci   | 8361590CBD |
| 8086:1c26 | 17aa:365e | Intel      | 6 Series/C200 Series Chip... | 9     | ehci_hc... | 338C59EF86 |
| 8086:1c2d | 17aa:365e | Intel      | 6 Series/C200 Series Chip... | 9     | ehci_hc... | 338C59EF86 |
| 8086:8c31 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 9     | xhci_pci   | F82FCD2051 |
| 1912:0015 | 17aa:365e | Renesas... | uPD720202 USB 3.0 Host Co... | 8     | xhci_pci   | 338C59EF86 |
| 8086:1c26 | 103c:2ac5 | Intel      | 6 Series/C200 Series Chip... | 8     | ehci_pci   | A5E0E95D2C |
| 8086:1c2d | 103c:2ac5 | Intel      | 6 Series/C200 Series Chip... | 8     | ehci_pci   | A5E0E95D2C |
| 8086:27c8 | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 8     | uhci_hcd   | B24608A945 |
| 8086:27c9 | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 8     | uhci_hcd   | B24608A945 |
| 8086:27ca | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 8     | uhci_hcd   | B24608A945 |
| 8086:27cb | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 8     | uhci_hcd   | B24608A945 |
| 8086:27cc | 8086:7270 | Intel      | NM10/ICH7 Family USB2 EHC... | 8     | ehci_pci   | B24608A945 |
| 8086:3b34 | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 8     | ehci_pci   | F0515A0217 |
| 8086:3b36 | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 8     | uhci_hcd   | F0515A0217 |
| 8086:3b3b | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 8     | uhci_hcd   | F0515A0217 |
| 8086:3b3c | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 8     | ehci_pci   | F0515A0217 |
| 8086:9d2f | 103c:84de | Intel      | Sunrise Point-LP USB 3.0 ... | 6     | xhci_hcd   | 6B7FA4FF60 |
| 1002:4396 | 1002:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 5     | ehci_hc... | F1E1BF19CC |
| 1002:4397 | 1002:4397 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 5     | ohci_hc... | F1E1BF19CC |
| 10de:077b | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] OHC... | 5     | ohci_hc... | 4CA7976A88 |
| 10de:077c | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] EHC... | 5     | ehci_hc... | 4CA7976A88 |
| 10de:077d | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] OHC... | 5     | ohci_hc... | 4CA7976A88 |
| 10de:077e | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] EHC... | 5     | ehci_hc... | 4CA7976A88 |
| 1b6f:7023 | 1025:8030 | Etron T... | EJ168 USB 3.0 Host Contro... | 5     | xhci_hcd   | 5EBFC68D96 |
| 8086:1e26 | 144d:b091 | Intel      | 7 Series/C216 Chipset Fam... | 5     | ehci_hc... | 857C8BE5D0 |
| 8086:1e2d | 144d:b091 | Intel      | 7 Series/C216 Chipset Fam... | 5     | ehci_hc... | 857C8BE5D0 |
| 8086:1e31 | 144d:b091 | Intel      | 7 Series/C210 Series Chip... | 5     | xhci_pci   | 857C8BE5D0 |
| 1002:4399 | 1002:4399 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 4     | ohci_hc... | F1E1BF19CC |
| 1022:7808 | 103c:8245 | AMD        | FCH USB EHCI Controller      | 4     | ehci_pci   | 2D74D9A2EF |
| 1022:7814 | 103c:8245 | AMD        | FCH USB XHCI Controller      | 4     | xhci_hcd   | 2D74D9A2EF |
| 1033:0194 | 104d:907e | NEC Com... | uPD720200 USB 3.0 Host Co... | 4     | xhci_pci   | 4A2DA5DD1B |
| 1912:0015 | 17aa:366c | Renesas... | uPD720202 USB 3.0 Host Co... | 4     | xhci_pci   | A922BB8973 |
| 8086:1c26 | 104d:907e | Intel      | 6 Series/C200 Series Chip... | 4     | ehci_hc... | 4A2DA5DD1B |
| 8086:1c26 | 17aa:366c | Intel      | 6 Series/C200 Series Chip... | 4     | ehci_hc... | A922BB8973 |
| 8086:1c2d | 104d:907e | Intel      | 6 Series/C200 Series Chip... | 4     | ehci_hc... | 4A2DA5DD1B |
| 8086:1c2d | 17aa:366c | Intel      | 6 Series/C200 Series Chip... | 4     | ehci_hc... | A922BB8973 |
| 8086:3a34 | 1025:0266 | Intel      | 82801JI (ICH10 Family) US... | 4     | uhci_hcd   | A2FF4426C9 |
| 8086:3a35 | 1025:0266 | Intel      | 82801JI (ICH10 Family) US... | 4     | uhci_hcd   | A2FF4426C9 |
| 8086:3a36 | 1025:0266 | Intel      | 82801JI (ICH10 Family) US... | 4     | uhci_hcd   | A2FF4426C9 |
| 8086:3a37 | 1025:0266 | Intel      | 82801JI (ICH10 Family) US... | 4     | uhci_hcd   | A2FF4426C9 |
| 8086:3a38 | 1025:0266 | Intel      | 82801JI (ICH10 Family) US... | 4     | uhci_hcd   | A2FF4426C9 |
| 8086:3a39 | 1025:0266 | Intel      | 82801JI (ICH10 Family) US... | 4     | uhci_hcd   | A2FF4426C9 |
| 8086:3a3a | 1025:0266 | Intel      | 82801JI (ICH10 Family) US... | 4     | ehci_hc... | A2FF4426C9 |
| 8086:3a3c | 1025:0266 | Intel      | 82801JI (ICH10 Family) US... | 4     | ehci_hc... | A2FF4426C9 |
| 8086:5aa8 | 17aa:36c4 | Intel      | Celeron N3350/Pentium N42... | 4     | xhci_hcd   | 00A1738003 |
| 1033:0194 | 104d:9083 | NEC Com... | uPD720200 USB 3.0 Host Co... | 3     | xhci_hcd   | B4CF237F88 |
| 104c:8241 | 103c:2aed | Texas I... | TUSB73x0 SuperSpeed USB 3... | 3     | xhci_pci   | 00FCD6CB57 |
| 8086:0f35 |           | Intel      | Atom Processor Z36xxx/Z37... | 3     | xhci_hcd   | E6BCDB1E4D |
| 8086:1c26 | 1028:0511 | Intel      | 6 Series/C200 Series Chip... | 3     | ehci_pci   | 8672A3F85D |
| 8086:1c26 | 103c:2aed | Intel      | 6 Series/C200 Series Chip... | 3     | ehci_hc... | 00FCD6CB57 |
| 8086:1c26 | 104d:9083 | Intel      | 6 Series/C200 Series Chip... | 3     | ehci_pci   | B4CF237F88 |
| 8086:1c26 | 8086:1c26 | Intel      | 6 Series/C200 Series Chip... | 3     | ehci_pci   | 19478FF625 |
| 8086:1c2d | 1028:0511 | Intel      | 6 Series/C200 Series Chip... | 3     | ehci_pci   | 8672A3F85D |
| 8086:1c2d | 103c:2aed | Intel      | 6 Series/C200 Series Chip... | 3     | ehci_hc... | 00FCD6CB57 |
| 8086:1c2d | 104d:9083 | Intel      | 6 Series/C200 Series Chip... | 3     | ehci_pci   | B4CF237F88 |
| 8086:1c2d | 8086:1c2d | Intel      | 6 Series/C200 Series Chip... | 3     | ehci_pci   | 19478FF625 |
| 8086:1e26 | 1028:0548 | Intel      | 7 Series/C216 Chipset Fam... | 3     | ehci_pci   | 229BA614EC |
| 8086:1e26 | 17aa:3671 | Intel      | 7 Series/C216 Chipset Fam... | 3     | ehci_hc... | 906A62D75E |
| 8086:1e26 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 3     | ehci_pci   | CD3C0C4583 |
| 8086:1e2d | 1028:0548 | Intel      | 7 Series/C216 Chipset Fam... | 3     | ehci_pci   | 229BA614EC |
| 8086:1e2d | 17aa:3671 | Intel      | 7 Series/C216 Chipset Fam... | 3     | ehci_hc... | 906A62D75E |
| 8086:1e2d | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 3     | ehci_pci   | CD3C0C4583 |
| 8086:1e31 | 1028:0548 | Intel      | 7 Series/C210 Series Chip... | 3     | xhci_hcd   | 229BA614EC |
| 8086:1e31 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 3     | xhci_hcd   | CD3C0C4583 |
| 8086:27c8 | 17aa:3602 | Intel      | NM10/ICH7 Family USB UHCI... | 3     | uhci_hcd   | 55C2F8E26B |
| 8086:27c8 | 17aa:3610 | Intel      | NM10/ICH7 Family USB UHCI... | 3     | uhci_hcd   | E98AA97F27 |
| 8086:27c9 | 17aa:3602 | Intel      | NM10/ICH7 Family USB UHCI... | 3     | uhci_hcd   | 55C2F8E26B |
| 8086:27c9 | 17aa:3610 | Intel      | NM10/ICH7 Family USB UHCI... | 3     | uhci_hcd   | E98AA97F27 |
| 8086:27ca | 17aa:3602 | Intel      | NM10/ICH7 Family USB UHCI... | 3     | uhci_hcd   | 55C2F8E26B |
| 8086:27ca | 17aa:3610 | Intel      | NM10/ICH7 Family USB UHCI... | 3     | uhci_hcd   | E98AA97F27 |
| 8086:27cb | 17aa:3602 | Intel      | NM10/ICH7 Family USB UHCI... | 3     | uhci_hcd   | 55C2F8E26B |
| 8086:27cb | 17aa:3610 | Intel      | NM10/ICH7 Family USB UHCI... | 3     | uhci_hcd   | E98AA97F27 |
| 8086:27cc | 17aa:3602 | Intel      | NM10/ICH7 Family USB2 EHC... | 3     | ehci_hc... | 55C2F8E26B |
| 8086:27cc | 17aa:3610 | Intel      | NM10/ICH7 Family USB2 EHC... | 3     | ehci_hc... | E98AA97F27 |
| 8086:3a34 | 104d:9060 | Intel      | 82801JI (ICH10 Family) US... | 3     | uhci_hcd   | 05CFF66AC2 |
| 8086:3a35 | 104d:9060 | Intel      | 82801JI (ICH10 Family) US... | 3     | uhci_hcd   | 05CFF66AC2 |
| 8086:3a36 | 104d:9060 | Intel      | 82801JI (ICH10 Family) US... | 3     | uhci_hcd   | 05CFF66AC2 |
| 8086:3a37 | 104d:9060 | Intel      | 82801JI (ICH10 Family) US... | 3     | uhci_hcd   | 05CFF66AC2 |
| 8086:3a38 | 104d:9060 | Intel      | 82801JI (ICH10 Family) US... | 3     | uhci_hcd   | 05CFF66AC2 |
| 8086:3a39 | 104d:9060 | Intel      | 82801JI (ICH10 Family) US... | 3     | uhci_hcd   | 05CFF66AC2 |
| 8086:3a3a | 104d:9060 | Intel      | 82801JI (ICH10 Family) US... | 3     | ehci_hc... | 05CFF66AC2 |
| 8086:3a3c | 104d:9060 | Intel      | 82801JI (ICH10 Family) US... | 3     | ehci_hc... | 05CFF66AC2 |
| 8086:3b34 | 1025:045c | Intel      | 5 Series/3400 Series Chip... | 3     | ehci_hc... | FF848E7FFB |
| 8086:3b3c | 1025:045c | Intel      | 5 Series/3400 Series Chip... | 3     | ehci_hc... | FF848E7FFB |
| 8086:8c26 | 17aa:3685 | Intel      | 8 Series/C220 Series Chip... | 3     | ehci_hc... | 647613F22B |
| 8086:8c2d | 17aa:3685 | Intel      | 8 Series/C220 Series Chip... | 3     | ehci_hc... | 647613F22B |

