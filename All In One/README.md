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
   * [ Ipmi interface (kcs) ](#ipmi-interface-kcs-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Multimedia controller ](#multimedia-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Non-essential instrumentation ](#non-essential-instrumentation-pci)
   * [ Non-vga unclassified device ](#non-vga-unclassified-device-pci)
   * [ Performance counters ](#performance-counters-pci)
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
| 1814:3298 | 1a3b:2987 | Ralink     | RT3290 Bluetooth             | 1     |            | 1F5B5C1D86 |

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2448 |           | Intel      | 82801 Mobile PCI Bridge      | 94    |            | 00CC913F3D |
| 8086:2815 | 106b:00a0 | Intel      | 82801HM (ICH8M) LPC Inter... | 77    | lpc_ich    | 00CC913F3D |
| 8086:283f |           | Intel      | 82801H (ICH8 Family) PCI ... | 77    | pcieport   | 00CC913F3D |
| 8086:2845 |           | Intel      | 82801H (ICH8 Family) PCI ... | 77    | pcieport   | 00CC913F3D |
| 8086:2847 |           | Intel      | 82801H (ICH8 Family) PCI ... | 77    | pcieport   | 00CC913F3D |
| 8086:2849 |           | Intel      | 82801H (ICH8 Family) PCI ... | 77    | pcieport   | 00CC913F3D |
| 8086:2a00 | 106b:00a0 | Intel      | Mobile PM965/GM965/GL960 ... | 77    | intel_agp  | 00CC913F3D |
| 8086:2a01 | 8086:0000 | Intel      | Mobile PM965/GM965/GL960 ... | 77    | pcieport   | 00CC913F3D |
| 8086:244e | 8086:7270 | Intel      | 82801 PCI Bridge             | 64    |            | C5621D630D |
| 104c:823e |           | Texas I... | XIO2213A/B/XIO2221 PCI Ex... | 63    | shpchp     | 8AB1BA226D |
| 8086:1513 |           | Intel      | CV82524 Thunderbolt Contr... | 63    | pcieport   | 2216DC8384 |
| 8086:1c10 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 63    | pcieport   | 2216DC8384 |
| 8086:1c14 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 63    | pcieport   | 2216DC8384 |
| 8086:1c18 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 63    | pcieport   | 2216DC8384 |
| 8086:1c44 | 8086:7270 | Intel      | Z68 Express Chipset LPC C... | 63    | lpc_ich    | 2216DC8384 |
| 8086:1c12 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 62    | pcieport   | 2216DC8384 |
| 10de:0aab | 10de:cb79 | Nvidia     | MCP79 PCI Bridge             | 46    |            | 8AB1BA226D |
| 10de:0ac4 | 10de:0000 | Nvidia     | MCP79 PCI Express Bridge     | 46    | pcieport   | 8AB1BA226D |
| 10de:0ac6 | 10de:0000 | Nvidia     | MCP79 PCI Express Bridge     | 46    | pcieport   | 8AB1BA226D |
| 10de:0ac7 | 10de:0000 | Nvidia     | MCP79 PCI Express Bridge     | 46    | pcieport   | 8AB1BA226D |
| 8086:1547 | 2222:1111 | Intel      | DSL3510 Thunderbolt Contr... | 46    | pcieport   | 20FB29A6AE |
| 8086:3b02 | 8086:7270 | Intel      | P55 Chipset LPC Interface... | 44    | lpc_ich    | C5621D630D |
| 8086:3b42 | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 44    | pcieport   | C5621D630D |
| 8086:3b44 | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 44    | pcieport   | C5621D630D |
| 8086:3b46 | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 44    | pcieport   | C5621D630D |
| 8086:1578 | 8086:0000 | Intel      | DSL6540 Thunderbolt 3 Bri... | 38    | pcieport   | EB3D04E089 |
| 8086:2d01 | 8086:8086 | Intel      | Core Processor QuickPath ... | 37    |            | C5621D630D |
| 8086:2d10 | 8086:8086 | Intel      | Core Processor QPI Link 0    | 37    |            | C5621D630D |
| 8086:2d11 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 37    |            | C5621D630D |
| 8086:2d12 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 37    |            | C5621D630D |
| 8086:2d13 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 37    |            | C5621D630D |
| 1022:156b |           | AMD        | Family 16h (Models 30h-3f... | 36    |            | 40434F824A |
| 1022:1580 |           | AMD        | Family 16h (Models 30h-3f... | 36    |            | 40434F824A |
| 1022:1581 |           | AMD        | Family 16h (Models 30h-3f... | 36    |            | 40434F824A |
| 1022:1582 |           | AMD        | Family 16h (Models 30h-3f... | 36    |            | 40434F824A |
| 1022:1583 |           | AMD        | Family 16h (Models 30h-3f... | 36    | k10temp    | 40434F824A |
| 1022:1584 |           | AMD        | Family 16h (Models 30h-3f... | 36    | fam15h_... | 40434F824A |
| 1022:1585 |           | AMD        | Family 16h (Models 30h-3f... | 36    |            | 40434F824A |
| 8086:0100 | 8086:2010 | Intel      | 2nd Generation Core Proce... | 35    | snb_uncore | 448D99E8C5 |
| 8086:0101 | 8086:2010 | Intel      | Xeon E3-1200/2nd Generati... | 35    | pcieport   | 448D99E8C5 |
| 8086:2c61 | 8086:8086 | Intel      | Core Processor QuickPath ... | 35    |            | C5621D630D |
| 8086:8c10 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 33    | pcieport   | 20FB29A6AE |
| 8086:8c14 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 33    | pcieport   | 20FB29A6AE |
| 8086:8c16 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 33    | pcieport   | 20FB29A6AE |
| 8086:8c18 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 33    | pcieport   | 20FB29A6AE |
| 10de:0aa0 | 10de:0000 | Nvidia     | MCP79 PCI Express Bridge     | 31    | shpchp     | 5AB2A08577 |
| 1022:157b |           | AMD        | Family 15h (Models 60h-6f... | 29    |            | ACCB6ADA09 |
| 1022:157d |           | AMD        | Carrizo Audio Dummy Host ... | 29    |            | ACCB6ADA09 |
| 8086:0100 | 106b:0000 | Intel      | 2nd Generation Core Proce... | 28    | snb_uncore | 2216DC8384 |
| 8086:0101 | 106b:0000 | Intel      | Xeon E3-1200/2nd Generati... | 28    | pcieport   | 2216DC8384 |
| 8086:a110 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 28    | pcieport   | E53C63BA89 |
| 8086:a111 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 28    | pcieport   | E53C63BA89 |
| 8086:a145 | 8086:7270 | Intel      | Z170 Chipset LPC/eSPI Con... | 28    |            | E53C63BA89 |
| 10de:0a82 |           | Nvidia     | MCP79 Host Bridge            | 27    |            | 4AD5BC744A |
| 10de:0aae | 10de:cb79 | Nvidia     | MCP79 LPC Bridge             | 27    |            | 4AD5BC744A |
| 8086:2c51 | 8086:8086 | Intel      | Core Processor QuickPath ... | 26    |            | 9AC85E317C |
| 8086:2c81 | 8086:8086 | Intel      | Core Processor QuickPath ... | 26    |            | 9AC85E317C |
| 8086:2c90 | 8086:8086 | Intel      | Core Processor QPI Link 0    | 26    | i7core_... | 9AC85E317C |
| 8086:2c91 | 8086:8086 | Intel      | Core Processor QPI Physic... | 26    |            | 9AC85E317C |
| 8086:2c98 | 8086:8086 | Intel      | Core Processor Integrated... | 26    |            | 9AC85E317C |
| 8086:2c99 | 8086:8086 | Intel      | Core Processor Integrated... | 26    |            | 9AC85E317C |
| 8086:2c9c | 8086:8086 | Intel      | Core Processor Integrated... | 26    |            | 9AC85E317C |
| 8086:2ca0 | 8086:8086 | Intel      | Core Processor Integrated... | 26    |            | 9AC85E317C |
| 8086:2ca1 | 8086:8086 | Intel      | Core Processor Integrated... | 26    |            | 9AC85E317C |
| 8086:2ca2 | 8086:8086 | Intel      | Core Processor Integrated... | 26    |            | 9AC85E317C |
| 8086:2ca3 | 8086:8086 | Intel      | Core Processor Integrated... | 26    |            | 9AC85E317C |
| 8086:2ca8 | 8086:8086 | Intel      | Core Processor Integrated... | 26    |            | 9AC85E317C |
| 8086:2ca9 | 8086:8086 | Intel      | Core Processor Integrated... | 26    |            | 9AC85E317C |
| 8086:2caa | 8086:8086 | Intel      | Core Processor Integrated... | 26    |            | 9AC85E317C |
| 8086:2cab | 8086:8086 | Intel      | Core Processor Integrated... | 26    |            | 9AC85E317C |
| 8086:d131 | 8086:0000 | Intel      | Core Processor DMI           | 26    |            | 9AC85E317C |
| 8086:d138 | 8086:0000 | Intel      | Core Processor PCI Expres... | 26    | pcieport   | 9AC85E317C |
| 1022:15b0 |           | AMD        | Stoney HT Configuration      | 25    |            | 5C5ADCC248 |
| 1022:15b1 |           | AMD        | Stoney Address Maps          | 25    |            | 5C5ADCC248 |
| 1022:15b2 |           | AMD        | Stoney DRAM Configuration    | 25    |            | 5C5ADCC248 |
| 1022:15b3 |           | AMD        | Stoney Miscellaneous Conf... | 25    | k10temp    | 5C5ADCC248 |
| 1022:15b4 |           | AMD        | Stoney PM Configuration      | 25    | fam15h_... | 5C5ADCC248 |
| 1022:15b5 |           | AMD        | Stoney NB Performance Mon... | 25    |            | 5C5ADCC248 |
| 8086:156d |           | Intel      | DSL5520 Thunderbolt 2 Bri... | 23    | pcieport   | E53C63BA89 |
| 8086:8c44 | 8086:7270 | Intel      | Z87 Express LPC Controller   | 23    | lpc_ich    | 20FB29A6AE |
| 8086:15d3 | 8086:0000 | Intel      | JHL6540 Thunderbolt 3 Bri... | 22    | pcieport   | 632B6526F7 |
| 1022:1700 |           | AMD        | Family 12h/14h Processor ... | 20    |            | DD885000B5 |
| 1022:1701 |           | AMD        | Family 12h/14h Processor ... | 20    |            | DD885000B5 |
| 1022:1702 |           | AMD        | Family 12h/14h Processor ... | 20    |            | DD885000B5 |
| 1022:1703 |           | AMD        | Family 12h/14h Processor ... | 20    | k10temp    | DD885000B5 |
| 1022:1704 |           | AMD        | Family 12h/14h Processor ... | 20    |            | DD885000B5 |
| 1022:1716 |           | AMD        | Family 12h/14h Processor ... | 20    |            | DD885000B5 |
| 1022:1718 |           | AMD        | Family 12h/14h Processor ... | 20    |            | DD885000B5 |
| 1022:1719 |           | AMD        | Family 12h/14h Processor ... | 20    |            | DD885000B5 |
| 8086:1e10 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 20    | pcieport   | DAE7632445 |
| 8086:1e14 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 20    | pcieport   | DAE7632445 |
| 8086:1e16 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 20    | pcieport   | DAE7632445 |
| 8086:1e18 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 20    | pcieport   | DAE7632445 |
| 8086:1e44 | 8086:7270 | Intel      | Z77 Express Chipset LPC C... | 20    | lpc_ich    | DAE7632445 |
| 10de:0aac | 10de:cb79 | Nvidia     | MCP79 LPC Bridge             | 19    |            | 8AB1BA226D |
| 8086:0040 |           | Intel      | Core Processor DRAM Contr... | 18    |            | C5621D630D |
| 8086:0041 | 8086:0000 | Intel      | Core Processor PCI Expres... | 18    | pcieport   | C5621D630D |
| 8086:1901 | 8086:7270 | Intel      | 6th-10th Gen Core Process... | 18    | pcieport   | EB3D04E089 |
| 1002:4384 |           | AMD        | SBx00 PCI to PCI Bridge      | 17    |            | D404124022 |
| 1022:1530 |           | AMD        | Family 16h Processor Func... | 17    |            | A8BF79BC54 |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:5229 | 17aa:365e | Realtek... | RTS5229 PCI Express Card ... | 12    | rtsx_pci   | 9164B5B105 |
| 10ec:5209 | 103c:2ac5 | Realtek... | RTS5209 PCI Express Card ... | 11    | rtsx_pci   | 55450C73C0 |
| 10ec:5209 | 1025:8020 | Realtek... | RTS5209 PCI Express Card ... | 10    | rtsx_pci   | 0362E43257 |
| 10ec:5209 | 1028:0543 | Realtek... | RTS5209 PCI Express Card ... | 10    | rtsx_pci   | 0E4A62B59F |
| 10ec:5209 | 1028:0548 | Realtek... | RTS5209 PCI Express Card ... | 9     | rtsx_pci   | 8184B0981F |
| 10ec:5209 | 1028:05db | Realtek... | RTS5209 PCI Express Card ... | 8     | rtsx_pci   | 80CA4B15A5 |
| 10ec:5209 | 1028:05a7 | Realtek... | RTS5209 PCI Express Card ... | 7     | rtsx_pci   | 16927C4FC4 |
| 10ec:5229 | 17aa:366c | Realtek... | RTS5229 PCI Express Card ... | 7     | rtsx_pci   | 3903A96DE3 |
| 10ec:522a | 1854:0308 | Realtek... | RTS522A PCI Express Card ... | 6     | rtsx_pci   | 125F68D06E |
| 10ec:5229 | 103c:82dc | Realtek... | RTS5229 PCI Express Card ... | 5     | rtsx_pci   | 036481482E |
| 10ec:5229 | 17aa:367b | Realtek... | RTS5229 PCI Express Card ... | 5     | rtsx_pci   | A459000D17 |
| 10ec:522a | 1028:0754 | Realtek... | RTS522A PCI Express Card ... | 5     | rtsx_pci   | 83612FBDEE |
| 10ec:5289 | 17aa:3671 | Realtek... | RTL8411 PCI Express Card ... | 5     | rtsx_pci   | 2A92010AD3 |
| 10ec:5229 | 103c:81b7 | Realtek... | RTS5229 PCI Express Card ... | 4     | rtsx_pci   | AA69312028 |
| 10ec:5229 | 17aa:3686 | Realtek... | RTS5229 PCI Express Card ... | 4     | rtsx_pci   | 1E467924BF |
| 10ec:5249 | 103c:18e6 | Realtek... | RTS5249 PCI Express Card ... | 4     | rtsx_pci   | CF3ED91B8A |
| 10ec:5209 | 103c:2aed | Realtek... | RTS5209 PCI Express Card ... | 3     | rtsx_pci   | 00FCD6CB57 |
| 10ec:5209 | 1854:0167 | Realtek... | RTS5209 PCI Express Card ... | 3     | rtsx_pci   | D0CF0BEEA8 |
| 10ec:5229 | 103c:2b2f | Realtek... | RTS5229 PCI Express Card ... | 3     | rtsx_pci   | 093F49B44C |
| 10ec:5229 | 103c:838b | Realtek... | RTS5229 PCI Express Card ... | 3     | rtsx_pci   | A8811301BC |
| 10ec:5229 | 10ec:5229 | Realtek... | RTS5229 PCI Express Card ... | 3     | rtsx_pci   | DD885000B5 |
| 10ec:5229 | 17aa:3685 | Realtek... | RTS5229 PCI Express Card ... | 3     | rtsx_pci   | 647613F22B |
| 10ec:5229 | 17aa:36ab | Realtek... | RTS5229 PCI Express Card ... | 3     | rtsx_pci   | 93BC9B0BE9 |
| 10ec:522a | 10ec:522a | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | 41FA541CA4 |
| 10ec:5287 | 1297:2053 | Realtek... | RTL8411B PCI Express Card... | 3     | rtsx_pci   | FFF1EFB11D |
| 10ec:5289 | 1297:2032 | Realtek... | RTL8411 PCI Express Card ... | 3     | rtsx_pci   | 26A6CD4678 |
| 10ec:5289 | 17aa:3670 | Realtek... | RTL8411 PCI Express Card ... | 3     | rtsx_pci   | 225E0C36DC |
| 10ec:5209 | 1028:05b0 | Realtek... | RTS5209 PCI Express Card ... | 2     | rtsx_pci   | BDF125B54E |
| 10ec:5209 | 1179:ff1e | Realtek... | RTS5209 PCI Express Card ... | 2     | rtsx_pci   | E1BB0618FD |
| 10ec:5209 | 17aa:3629 | Realtek... | RTS5209 PCI Express Card ... | 2     | rtsx_pci   | D404124022 |
| 10ec:5209 | 1b0a:0183 | Realtek... | RTS5209 PCI Express Card ... | 2     | rtsx_pci   | 78D39E18EF |
| 10ec:5227 | 103c:2b1c | Realtek... | RTS5227 PCI Express Card ... | 2     | rtsx_pci   | EA47F5ADBE |
| 10ec:5229 | 1025:085f | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 90FF435FAD |
| 10ec:5229 | 103c:2179 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 7B6E93783B |
| 10ec:5229 | 103c:2afc | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 7A71F7247E |
| 10ec:5229 | 103c:2b0a | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | BA22741458 |
| 10ec:5229 | 103c:2b0d | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 5C13B7BB96 |
| 10ec:5229 | 103c:2b13 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 991915273E |
| 10ec:5229 | 103c:2b3b | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | BA4DA15B98 |
| 10ec:5229 | 103c:2b3e | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | E370DBFC53 |
| 10ec:5229 | 17aa:30fc | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 4740E3EA20 |
| 10ec:5229 | 17aa:3633 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 53B3108CB8 |
| 10ec:5229 | 17aa:3636 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 3F2A054B58 |
| 10ec:5229 | 17aa:3639 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 9A0E5BD73B |
| 10ec:5229 | 17aa:365b | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | E4DFE645A8 |
| 10ec:5229 | 17aa:3696 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 4C3DD6A28B |
| 10ec:5229 | 17aa:369c | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | A027E01C3B |
| 10ec:5229 | 17aa:369e | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 766F235D4B |
| 10ec:5229 | 17aa:36bc | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | F9C1063722 |
| 10ec:5229 | 17aa:36bd | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | CE295294E2 |
| 10ec:5229 | 17aa:36be | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 4863245A0E |
| 10ec:522a | 103c:85a2 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 930847F29A |
| 10ec:524a | 1028:06d4 | Realtek... | RTS524A PCI Express Card ... | 2     | rtsx_pci   | 275E0EEAEF |
| 10ec:524a | 103c:829b | Realtek... | RTS524A PCI Express Card ... | 2     | rtsx_pci   | 44675B1F55 |
| 10ec:524a | 10ec:524a | Realtek... | RTS524A PCI Express Card ... | 2     | rtsx_pci   | 8DF63D744B |
| 10ec:525a | 1028:06c5 | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx_pci   | 0E09B99FC0 |
| 10ec:525a | 1028:075d | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx_pci   | 404A8B3A68 |
| 10ec:525a | 1028:084b | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx_pci   | 301B4DE8EA |
| 10ec:525a | 1028:0984 | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx_pci   | 3A565370DE |
| 10ec:5209 | 1025:0781 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 63B708B27B |
| 10ec:5209 | 1028:054b | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 45F86E051C |
| 10ec:5209 | 1028:05d1 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 45C116DB45 |
| 10ec:5209 | 1028:0666 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 20F6E2B8DE |
| 10ec:5209 | 17aa:362a | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | DCE4B1A82B |
| 10ec:5227 | 103c:2141 | Realtek... | RTS5227 PCI Express Card ... | 1     | rtsx_pci   | EAFEC5FB57 |
| 10ec:5229 | 1025:090a | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | A586C561CC |
| 10ec:5229 | 103c:18ea | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 67E2E927B6 |
| 10ec:5229 | 103c:2b1f | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | F01E3C859D |
| 10ec:5229 | 103c:2b56 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 3979EC6E73 |
| 10ec:5229 | 103c:81b9 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 15C46542B5 |
| 10ec:5229 | 103c:826a | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | C60FCEAEE4 |
| 10ec:5229 | 103c:82a6 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | DD3E2FA2B5 |
| 10ec:5229 | 103c:82f3 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | E25D57F967 |
| 10ec:5229 | 103c:8374 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | DEEDD3ED67 |
| 10ec:5229 | 103c:8448 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 9C6AD0A8DB |
| 10ec:5229 | 103c:8449 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 0C2804436F |
| 10ec:5229 | 17aa:30df | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 9374D57487 |
| 10ec:5229 | 17aa:3113 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 7739219D01 |
| 10ec:5229 | 17aa:3127 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | DF28137212 |
| 10ec:5229 | 17aa:3630 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | F96B4E9ECA |
| 10ec:5229 | 17aa:3683 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | EAAC06252B |
| 10ec:5229 | 17aa:368f | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 58DDD6F565 |
| 10ec:5229 | 17aa:3697 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 54E6A4A4F7 |
| 10ec:5229 | 17aa:369d | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | FF239AD52E |
| 10ec:5229 | 17aa:36a5 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | C486FF05F5 |
| 10ec:5229 | 17aa:36a6 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 84248BB07C |
| 10ec:5229 | 17aa:36a9 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | A8185511A2 |
| 10ec:5229 | 17aa:36ad | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 92B26540F0 |
| 10ec:5229 | 17aa:36bb | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | B790C5FA32 |
| 10ec:5229 | 17aa:36d0 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 9A305C10EC |
| 10ec:5229 | 17aa:36ed | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 8DFF428CAB |
| 10ec:522a | 1028:06c6 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 69820330AA |
| 10ec:522a | 1028:074b | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 0DE1EB4A35 |
| 10ec:522a | 1028:079e | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 2BF103DD36 |
| 10ec:522a | 103c:83eb | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | C73E03D65D |
| 10ec:5249 | 103c:18e8 | Realtek... | RTS5249 PCI Express Card ... | 1     | rtsx_pci   | 182C662F57 |
| 10ec:524a | 103c:8058 | Realtek... | RTS524A PCI Express Card ... | 1     | rtsx_pci   | 2281502A3C |
| 10ec:524a | 103c:805e | Realtek... | RTS524A PCI Express Card ... | 1     | rtsx_pci   | FDD0A4E977 |
| 10ec:524a | 1462:a623 | Realtek... | RTS524A PCI Express Card ... | 1     | rtsx_pci   | B633258FB4 |
| 10ec:524a | 1462:aac2 | Realtek... | RTS524A PCI Express Card ... | 1     | rtsx_pci   | 1DAC035476 |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0aa3 | 10de:cb79 | Nvidia     | MCP79 Co-processor           | 46    | nvidia     | 8AB1BA226D |
| 10de:0753 | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] Co-... | 7     |            | 04B8123AA5 |
| 10de:0aa3 | 1462:4570 | Nvidia     | MCP79 Co-processor           | 1     | nvidia     | EE06AF7B45 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1c3a | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 63    | mei_me     | 2216DC8384 |
| 8086:8c3a | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 33    | mei_me     | 20FB29A6AE |
| 8086:a13a | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 28    | mei_me     | E53C63BA89 |
| 8086:1e3a | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 20    | mei_me     | DAE7632445 |
| 8086:a360 | 8086:7270 | Intel      | Cannon Lake PCH HECI Cont... | 17    | mei_me     | EB3D04E089 |
| 8086:a328 | 8086:7270 | Intel      | Cannon Lake PCH Serial IO... | 16    | intel_l... | EB3D04E089 |
| 8086:a329 | 8086:7270 | Intel      | 300 Series Chipset Family    | 16    | intel_l... | EB3D04E089 |
| 8086:1c3a | 17aa:365e | Intel      | 6 Series/C200 Series Chip... | 12    | mei_me     | 9164B5B105 |
| 8086:9d3a | 103c:84de | Intel      | Sunrise Point-LP CSME HEC... | 12    | mei_me     | B5E9340D85 |
| 8086:1c3a | 103c:2ac5 | Intel      | 6 Series/C200 Series Chip... | 11    | mei_me     | 55450C73C0 |
| 8086:1e3a | 1028:0543 | Intel      | 7 Series/C216 Chipset Fam... | 10    | mei_me     | 0E4A62B59F |
| 8086:9d3a | 8086:9d3a | Intel      | Sunrise Point-LP CSME HEC... | 10    | mei_me     | 1096F1F298 |
| 8086:1e3a | 1028:0548 | Intel      | 7 Series/C216 Chipset Fam... | 9     | mei_me     | 8184B0981F |
| 8086:319a | 1025:1304 | Intel      | Celeron/Pentium Silver Pr... | 9     | mei_me     | B7F823BFDA |
| 8086:9d3a | 1025:1287 | Intel      | Sunrise Point-LP CSME HEC... | 9     | mei_me     | EB23862DED |
| 8086:8c3a | 1028:05db | Intel      | 8 Series/C220 Series Chip... | 8     | mei_me     | 80CA4B15A5 |
| 8086:1c3a | 104d:907e | Intel      | 6 Series/C200 Series Chip... | 7     | mei_me     | 626BFE0484 |
| 8086:1c3a | 17aa:366c | Intel      | 6 Series/C200 Series Chip... | 7     | mei_me     | 3903A96DE3 |
| 8086:3b64 | 17aa:306a | Intel      | 5 Series/3400 Series Chip... | 7     | mei_me     | 0EF323D23D |
| 8086:8c3a | 1028:05a7 | Intel      | 8 Series/C220 Series Chip... | 7     | mei_me     | 16927C4FC4 |
| 8086:1c3a | 1028:0511 | Intel      | 6 Series/C200 Series Chip... | 6     | mei_me     | 5C781B927F |
| 8086:1e3a | 144d:b091 | Intel      | 7 Series/C216 Chipset Fam... | 6     | mei_me     | 0F9E022C5E |
| 8086:319a | 1854:0308 | Intel      | Celeron/Pentium Silver Pr... | 6     | mei_me     | 125F68D06E |
| 8086:a360 | 103c:84ee | Intel      | Cannon Lake PCH HECI Cont... | 6     | mei_me     | DF07E6AAB4 |
| 8086:1c3a | 104d:9083 | Intel      | 6 Series/C200 Series Chip... | 5     | mei_me     | EEB433BF77 |
| 8086:1e3a | 104d:9097 | Intel      | 7 Series/C216 Chipset Fam... | 5     | mei_me     | B2B912EF1E |
| 8086:1e3a | 17aa:3671 | Intel      | 7 Series/C216 Chipset Fam... | 5     | mei_me     | 2A92010AD3 |
| 8086:5a9a | 17aa:36c4 | Intel      | Celeron N3350/Pentium N42... | 5     | mei_me     | 4B68C7AEE7 |
| 8086:8c3a | 103c:18e6 | Intel      | 8 Series/C220 Series Chip... | 5     | mei_me     | CF3ED91B8A |
| 8086:8c3a | 17aa:367b | Intel      | 8 Series/C220 Series Chip... | 5     | mei_me     | A459000D17 |
| 8086:9d3a | 1028:0754 | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | 83612FBDEE |
| 8086:a13a | 8086:a13a | Intel      | 100 Series/C230 Series Ch... | 5     | mei_me     | 31E48D8DA1 |
| 8086:1c3a | 1019:7c94 | Intel      | 6 Series/C200 Series Chip... | 4     | mei_me     | 4FF205BED4 |
| 8086:1c3a | 1025:0618 | Intel      | 6 Series/C200 Series Chip... | 4     | mei_me     | 0362E43257 |
| 8086:319a | 103c:86f0 | Intel      | Celeron/Pentium Silver Pr... | 4     | mei_me     | 9FDCC0F2AF |
| 8086:319a | 1043:1e80 | Intel      | Celeron/Pentium Silver Pr... | 4     | mei_me     | BA03906EB8 |
| 8086:319a | 1043:1ea0 | Intel      | Celeron/Pentium Silver Pr... | 4     | mei_me     | 3B910E6A74 |
| 8086:319a | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 4     | mei_me     | 32E5618CFE |
| 8086:8c3a | 1028:0623 | Intel      | 8 Series/C220 Series Chip... | 4     | mei_me     | 3C11289E85 |
| 8086:8c3a | 17aa:3686 | Intel      | 8 Series/C220 Series Chip... | 4     | mei_me     | 1E467924BF |
| 8086:8cba | 8086:7270 | Intel      | 9 Series Chipset Family M... | 4     | mei_me     | 74E99D5666 |
| 8086:9cba | 8086:9cba | Intel      | Wildcat Point-LP MEI Cont... | 4     | mei_me     | 6CF5332D62 |
| 8086:9d3a | 103c:82dd | Intel      | Sunrise Point-LP CSME HEC... | 4     | mei_me     | 0A0BE4F02F |
| 8086:9de0 | 1043:17b1 | Intel      | Cannon Point-LP MEI Contr... | 4     | mei_me     | 72FCC11E52 |
| 8086:a13a | 103c:82dc | Intel      | 100 Series/C230 Series Ch... | 4     | mei_me     | 036481482E |
| 8086:a360 | 103c:8446 | Intel      | Cannon Lake PCH HECI Cont... | 4     | mei_me     | 651C327218 |
| 8086:1c3a | 1025:0492 | Intel      | 6 Series/C200 Series Chip... | 3     | mei_me     | D8225AFA7A |
| 8086:1c3a | 1025:0608 | Intel      | 6 Series/C200 Series Chip... | 3     | mei_me     | D0F0DA0187 |
| 8086:1c3a | 103c:2aed | Intel      | 6 Series/C200 Series Chip... | 3     | mei_me     | 00FCD6CB57 |
| 8086:1c3a | 1043:1c3a | Intel      | 6 Series/C200 Series Chip... | 3     | mei_me     | 0554804F5F |
| 8086:1c3a | 8086:1c3a | Intel      | 6 Series/C200 Series Chip... | 3     | mei_me     | 19478FF625 |
| 8086:1e3a | 1043:844d | Intel      | 7 Series/C216 Chipset Fam... | 3     | mei_me     | 61B5866007 |
| 8086:2e24 | 104d:9060 | Intel      | 4 Series Chipset HECI Con... | 3     | mei_me     | 05CFF66AC2 |
| 8086:34e0 | 1025:1418 | Intel      | Ice Lake-LP Management En... | 3     | mei_me     | 5820A2D4C3 |
| 8086:3b64 | 1025:0297 | Intel      | 5 Series/3400 Series Chip... | 3     | mei_me     | 96C29C6C68 |
| 8086:3b64 | 1028:0478 | Intel      | 5 Series/3400 Series Chip... | 3     | mei_me     | A288705A4D |
| 8086:5a9a | 1854:0267 | Intel      | Celeron N3350/Pentium N42... | 3     | mei_me     | 41FA541CA4 |
| 8086:8c3a | 1028:0626 | Intel      | 8 Series/C220 Series Chip... | 3     | mei_me     | F61158882E |
| 8086:8c3a | 17aa:3685 | Intel      | 8 Series/C220 Series Chip... | 3     | mei_me     | 647613F22B |
| 8086:8c3a | 1b0a:0188 | Intel      | 8 Series/C220 Series Chip... | 3     | mei_me     | 0C24A93146 |
| 8086:9c3a | 8086:7270 | Intel      | 8 Series HECI #0             | 3     | mei_me     | 2F7B60E4CD |
| 8086:9d3a |           | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | CD5915910D |
| 8086:9d3a | 1028:0852 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | 5A27DEAF8A |
| 8086:9d3a | 1043:12a1 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | E0EF808E3F |
| 8086:9d3a | 8086:7270 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | 94DEDAFA8A |
| 8086:a13a | 103c:81b7 | Intel      | 100 Series/C230 Series Ch... | 3     | mei_me     | AA69312028 |
| 8086:a13a | 17aa:30ba | Intel      | 100 Series/C230 Series Ch... | 3     | mei_me     | F3E9E0B2F5 |
| 8086:a2ba | 103c:838b | Intel      | 200 Series PCH CSME HECI #1  | 3     | mei_me     | A8811301BC |
| 8086:02e0 | 1028:0954 | Intel      | Comet Lake Management Eng... | 2     | mei_me     | 51D212B73F |
| 8086:06e0 | 1028:0984 | Intel      | Comet Lake HECI Controller   | 2     |            | 3A565370DE |
| 8086:1c3a | 1019:0777 | Intel      | 6 Series/C200 Series Chip... | 2     | mei_me     | 1F5B5C1D86 |
| 8086:1c3a | 1025:061c | Intel      | 6 Series/C200 Series Chip... | 2     | mei_me     | 155DE85715 |
| 8086:1c3a | 1025:063f | Intel      | 6 Series/C200 Series Chip... | 2     | mei_me     | 5EBFC68D96 |
| 8086:1c3a | 1025:0640 | Intel      | 6 Series/C200 Series Chip... | 2     | mei_me     | 22317B4B49 |
| 8086:1c3a | 103c:3395 | Intel      | 6 Series/C200 Series Chip... | 2     | mei_me     | 02F1FBC843 |
| 8086:1c3a | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 2     | mei_me     | 11466C75B0 |
| 8086:1c3a | 104d:908e | Intel      | 6 Series/C200 Series Chip... | 2     | mei_me     | 59BB8EC907 |
| 8086:1c3a | 1179:ff1e | Intel      | 6 Series/C200 Series Chip... | 2     | mei_me     | E1BB0618FD |
| 8086:1c3a | 144d:b091 | Intel      | 6 Series/C200 Series Chip... | 2     | mei_me     | 738C727E3E |
| 8086:1c3a | 1bcf:a013 | Intel      | 6 Series/C200 Series Chip... | 2     | mei_me     | 1494683BB9 |
| 8086:1e3a | 1025:0792 | Intel      | 7 Series/C216 Chipset Fam... | 2     | mei_me     | 3D1389215D |
| 8086:1e3a | 1028:05c2 | Intel      | 7 Series/C216 Chipset Fam... | 2     | mei_me     | 3E115C67CD |
| 8086:1e3a | 1179:ff1e | Intel      | 7 Series/C216 Chipset Fam... | 2     | mei_me     | D417AD3262 |
| 8086:1e3a | 1462:b062 | Intel      | 7 Series/C216 Chipset Fam... | 2     | mei_me     | 0FC1178D7D |
| 8086:1e3a | 152d:0924 | Intel      | 7 Series/C216 Chipset Fam... | 2     | mei_me     | D3B0FDDEDF |
| 8086:1e3a | 17aa:365b | Intel      | 7 Series/C216 Chipset Fam... | 2     | mei_me     | E4DFE645A8 |
| 8086:1e3a | 1854:0167 | Intel      | 7 Series/C216 Chipset Fam... | 2     | mei_me     | 4A7F3EDFF2 |
| 8086:2e14 | 103c:1489 | Intel      | 4 Series Chipset HECI Con... | 2     | mei_me     | 603E26F80F |
| 8086:2e24 | 104d:9044 | Intel      | 4 Series Chipset HECI Con... | 2     | mei_me     | EB74857893 |
| 8086:319a | 103c:8431 | Intel      | Celeron/Pentium Silver Pr... | 2     | mei_me     | 02681BB7AC |
| 8086:3b64 | 104d:9074 | Intel      | 5 Series/3400 Series Chip... | 2     | mei_me     | 68937CF6BB |
| 8086:5a9a | 103c:8304 | Intel      | Celeron N3350/Pentium N42... | 2     | mei_me     | A63E8373C4 |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | mei_me     | 7FEFB7E572 |
| 8086:8c3a | 1028:05b0 | Intel      | 8 Series/C220 Series Chip... | 2     | mei_me     | BDF125B54E |
| 8086:8c3a | 103c:2179 | Intel      | 8 Series/C220 Series Chip... | 2     | mei_me     | 7B6E93783B |
| 8086:8c3a | 103c:2b0d | Intel      | 8 Series/C220 Series Chip... | 2     | mei_me     | 5C13B7BB96 |
| 8086:8c3a | 103c:2b1c | Intel      | 8 Series/C220 Series Chip... | 2     | mei_me     | EA47F5ADBE |
| 8086:8c3a | 1462:ae67 | Intel      | 8 Series/C220 Series Chip... | 2     | mei_me     | 881CDBC376 |
| 8086:8c3a | 17aa:3696 | Intel      | 8 Series/C220 Series Chip... | 2     | mei_me     | 4C3DD6A28B |
| 8086:8c3a | 17aa:369c | Intel      | 8 Series/C220 Series Chip... | 2     | mei_me     | A027E01C3B |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1537 | 1022:1537 | AMD        | Kabini/Mullins PSP-Platfo... | 15    | ccp        | A586C561CC |
| 1022:1537 | 103c:8245 | AMD        | Kabini/Mullins PSP-Platfo... | 11    | ccp        | 40434F824A |
| 1022:1578 | 103c:8381 | AMD        | Carrizo Platform Security... | 8     |            | B4A3EC103B |
| 8086:2298 | 103c:81bb | Intel      | Atom/Celeron/Pentium Proc... | 7     | mei_txe    | CA80EA46C5 |
| 1022:1537 | 103c:2b3b | AMD        | Kabini/Mullins PSP-Platfo... | 6     | ccp        | 1A5D2C36EC |
| 1022:1578 | 103c:8430 | AMD        | Carrizo Platform Security... | 6     |            | 5C5ADCC248 |
| 8086:2298 | 1028:06cc | Intel      | Atom/Celeron/Pentium Proc... | 6     | mei_txe    | 3AC5DA5F93 |
| 8086:0f18 | 17aa:3695 | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | CB2927D290 |
| 8086:0f18 |           | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | B3E778A640 |
| 1022:1537 | 103c:2b2f | AMD        | Kabini/Mullins PSP-Platfo... | 3     | ccp        | 093F49B44C |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 3     |            | 2B4A157052 |
| 1022:1578 | 1028:07e3 | AMD        | Carrizo Platform Security... | 3     |            | ACCB6ADA09 |
| 1022:15df | 103c:86f3 | AMD        | Family 17h (Models 10h-1f... | 3     | ccp        | 4B12BB887A |
| 1022:15df | 17aa:36f5 | AMD        | Family 17h (Models 10h-1f... | 3     | ccp        | EB38810FB8 |
| 8086:0f18 | 1025:0994 | Intel      | Atom Processor Z36xxx/Z37... | 3     | mei_txe    | 6247D83BAB |
| 8086:0f18 | 1297:2041 | Intel      | Atom Processor Z36xxx/Z37... | 3     | mei_txe    | 26A6CD4678 |
| 8086:0f18 | 1854:0200 | Intel      | Atom Processor Z36xxx/Z37... | 3     | mei_txe    | 40E267DF98 |
| 8086:2298 | 1025:0992 | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | F2703DFC7E |
| 8086:2298 | 1297:2053 | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | FFF1EFB11D |
| 1022:1456 | 1022:1456 | AMD        | Family 17h (Models 00h-0f... | 2     | ccp        | 42B182D5F0 |
| 1022:1578 | 17aa:36bd | AMD        | Carrizo Platform Security... | 2     |            | CE295294E2 |
| 1022:1578 | 17aa:36be | AMD        | Carrizo Platform Security... | 2     |            | 4863245A0E |
| 1022:1578 | 17aa:36ec | AMD        | Carrizo Platform Security... | 2     |            | 2CFA2D338E |
| 1022:15df | 103c:8582 | AMD        | Family 17h (Models 10h-1f... | 2     | ccp        | BACA8B82E5 |
| 1022:15df | 17aa:371c | AMD        | Family 17h (Models 10h-1f... | 2     |            | 65195D0D22 |
| 8086:0f18 | 1025:085f | Intel      | Atom Processor Z36xxx/Z37... | 2     | mei_txe    | 90FF435FAD |
| 8086:0f18 | 1028:0690 | Intel      | Atom Processor Z36xxx/Z37... | 2     | mei_txe    | 84027725C5 |
| 8086:0f18 | 17aa:368a | Intel      | Atom Processor Z36xxx/Z37... | 2     | mei_txe    | 08057029E5 |
| 8086:0f18 | 17aa:36a8 | Intel      | Atom Processor Z36xxx/Z37... | 2     | mei_txe    | 5F6FF0EBDA |
| 8086:2298 | 1025:098f | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | 350CC83AC7 |
| 8086:2298 | 1025:1065 | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | 21CA50C386 |
| 8086:2298 | 8086:2298 | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | E20AC63341 |
| 1022:1486 | 1022:1486 | AMD        | Starship/Matisse Cryptogr... | 1     | ccp        | 991A74F3E5 |
| 1022:1486 | 1043:87c0 | AMD        | Starship/Matisse Cryptogr... | 1     | ccp        | 577AD83B8F |
| 1022:1537 | 103c:2b54 | AMD        | Kabini/Mullins PSP-Platfo... | 1     | ccp        | 161455EFD7 |
| 1022:1578 | 1028:0855 | AMD        | Carrizo Platform Security... | 1     |            | DACA9432F8 |
| 1022:1578 | 103c:81b9 | AMD        | Carrizo Platform Security... | 1     |            | 15C46542B5 |
| 1022:1578 | 103c:8374 | AMD        | Carrizo Platform Security... | 1     |            | DEEDD3ED67 |
| 1022:15df | 1022:15df | AMD        | Family 17h (Models 10h-1f... | 1     |            | CB6D3B830B |
| 1022:15df | 103c:8449 | AMD        | Family 17h (Models 10h-1f... | 1     | ccp        | 0C2804436F |
| 1022:15df | 103c:84ef | AMD        | Family 17h (Models 10h-1f... | 1     | ccp        | 6917C1729B |
| 1022:15df | 103c:85ba | AMD        | Family 17h (Models 10h-1f... | 1     |            | 071C59D998 |
| 1022:15df | 103c:86ee | AMD        | Family 17h (Models 10h-1f... | 1     |            | 8579540A18 |
| 1022:15df | 17aa:3703 | AMD        | Family 17h (Models 10h-1f... | 1     |            | 91A80D30D0 |
| 1022:15df | 17aa:371d | AMD        | Family 17h (Models 10h-1f... | 1     | ccp        | 98A498AE78 |
| 8086:0f18 | 1025:084d | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | 95465E168F |
| 8086:0f18 | 1b0a:01a5 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | E745E03926 |
| 8086:2298 |           | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | A2CB18D2E5 |
| 8086:2298 | 1462:a623 | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | B633258FB4 |
| 8086:2298 | 1462:ac16 | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | 8DF63D744B |
| 8086:2298 | 1854:0236 | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | C3FA4BE680 |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 11c1:5901 | 11c1:5900 | LSI        | FW643 [TrueFire] PCIe 139... | 167   | firewir... | 00CC913F3D |
| 104c:823f |           | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 63    | firewir... | 8AB1BA226D |
| 11c1:5811 | 11c1:5811 | LSI        | FW322/323 [TrueFire] 1394... | 15    | firewir... | 394EF62F20 |
| 1180:e832 | 104d:907e | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 7     | firewir... | 626BFE0484 |
| 1180:e832 | 104d:9097 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 5     | firewir... | B2B912EF1E |
| 197b:2380 | 17aa:3602 | JMicron... | IEEE 1394 Host Controller    | 4     | firewir... | C25FDFE643 |
| 1180:e832 | 104d:9060 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 3     | firewir... | 05CFF66AC2 |
| 104c:8025 |           | Texas I... | TSB82AA2 IEEE-1394b Link ... | 2     | firewir... | 2BAA39FB91 |
| 1180:0832 | 104d:9044 | Ricoh      | R5C832 IEEE 1394 Controller  | 2     | firewir... | EB74857893 |
| 1180:e832 | 104d:9074 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 2     | firewir... | 68937CF6BB |
| 1180:e832 | 104d:908e | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 2     | firewir... | 59BB8EC907 |
| 1217:13f7 | 1bcf:a013 | O2 Micro   | 1394 OHCI Compliant Host ... | 2     | firewir... | 1494683BB9 |
| 197b:2380 | 103c:1489 | JMicron... | IEEE 1394 Host Controller    | 2     | firewir... | 603E26F80F |
| 104c:8024 | 9005:0030 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 1     | firewir... | 098FE372A3 |
| 104c:8029 | 107b:4009 | Texas I... | PCI4510 IEEE-1394 Controller | 1     | firewir... | 0213C3A21C |
| 1106:3401 | 17aa:3608 | VIA Tec... | FireWire (IEEE 1394)         | 1     | firewir... | 69574214D7 |
| 1180:0552 | 1033:886f | Ricoh      | R5C552 IEEE 1394 Controller  | 1     | firewir... | 86771347FB |
| 1180:0832 | 104d:9043 | Ricoh      | R5C832 IEEE 1394 Controller  | 1     | firewir... | CFDCAC5734 |
| 1217:10f7 | 17aa:3068 | O2 Micro   | 1394 OHCI Compliant Host ... | 1     | firewir... | 27E7D42D53 |
| 197b:2380 | 103c:3561 | JMicron... | IEEE 1394 Host Controller    | 1     | firewir... | 90E0F93E8D |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1577 | 1022:1577 | AMD        | Family 15h (Models 60h-6f... | 10    |            | 9FC1D2D346 |
| 1022:1423 | 17aa:368f | AMD        | Family 15h (Models 30h-3f... | 1     |            | 58DDD6F565 |
| 1022:1451 | 1022:1451 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 42B182D5F0 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:9583 | 106b:0083 | AMD        | RV630/M76 [Mobility Radeo... | 50    | radeon     | 00CC913F3D |
| 8086:0102 | 8086:2010 | Intel      | 2nd Generation Core Proce... | 34    | i915       | 448D99E8C5 |
| 8086:0102 | 106b:0000 | Intel      | 2nd Generation Core Proce... | 28    | i915       | 2216DC8384 |
| 1002:94c8 | 106b:0084 | AMD        | RV610/M74 [Mobility Radeo... | 25    | radeon     | B513DFD9C0 |
| 1002:6741 | 106b:6741 | AMD        | Whistler [Radeon HD 6630M... | 24    | radeon     | 448D99E8C5 |
| 1002:6740 | 106b:6740 | AMD        | Whistler [Radeon HD 6730M... | 23    | radeon     | 2216DC8384 |
| 1002:9488 | 106b:00b6 | AMD        | RV730/M96-XT [Mobility Ra... | 18    | radeon     | 8AB1BA226D |
| 10de:0867 | 106b:00ad | Nvidia     | C79 [GeForce 9400]           | 18    | nouveau    | DF46BFF297 |
| 1002:6720 | 106b:0b00 | AMD        | Blackcomb [Radeon HD 6970... | 14    | radeon     | 123A822BE5 |
| 1002:71c5 | 106b:0080 | AMD        | RV530/M56-P [Mobility Rad... | 14    | radeon     | 394EF62F20 |
| 1002:68a1 | 106b:00cc | AMD        | Broadway PRO [Mobility Ra... | 13    | radeon     | 9AC85E317C |
| 10de:0869 | 106b:00b4 | Nvidia     | MCP7A [GeForce 9400]         | 13    | nouveau    | 5AB2A08577 |
| 1002:944a | 106b:00b5 | AMD        | RV770/M98L [Mobility Rade... | 12    | radeon     | E01CF9234B |
| 8086:5917 | 103c:84de | Intel      | UHD Graphics 620             | 12    | i915       | B5E9340D85 |
| 8086:0102 | 103c:2ac5 | Intel      | 2nd Generation Core Proce... | 11    | i915       | 55450C73C0 |
| 10de:0fd8 | 106b:0109 | Nvidia     | GK107M [GeForce GT 640M M... | 10    | nvidia     | DAE7632445 |
| 8086:0d22 | 106b:0122 | Intel      | Crystal Well Integrated I... | 10    | i915       | 0761ED6181 |
| 8086:5917 | 1025:1287 | Intel      | UHD Graphics 620             | 9     | i915       | EB23862DED |
| 1002:98e4 | 103c:8381 | AMD        | Stoney [Radeon R2/R3/R4/R... | 8     | amdgpu     | B4A3EC103B |
| 8086:0042 | 17aa:306a | Intel      | Core Processor Integrated... | 8     | i915       | 0EF323D23D |
| 8086:0416 | 1028:05db | Intel      | 4th Gen Core Processor In... | 8     | i915       | 80CA4B15A5 |
| 1002:6751 | 1028:0548 | AMD        | Turks [Radeon HD 7650A/76... | 7     | radeon     | 8184B0981F |
| 1002:67ef | 106b:016b | AMD        | Baffin [Radeon RX 460/560... | 7     | amdgpu     | 632B6526F7 |
| 10de:0dea | 17aa:365e | Nvidia     | GF108M [GeForce 610M]        | 7     | nouveau    | 9164B5B105 |
| 8086:0102 | 1028:0511 | Intel      | 2nd Generation Core Proce... | 7     | i915       | 5C781B927F |
| 8086:0412 | 1028:05a7 | Intel      | Xeon E3-1200 v3/4th Gen C... | 7     | i915       | 16927C4FC4 |
| 8086:22b1 | 103c:81bb | Intel      | Atom/Celeron/Pentium Proc... | 7     | i915       | CA80EA46C5 |
| 1002:6660 | 1028:05db | AMD        | Sun XT [Radeon HD 8670A/8... | 6     | radeon     | 80CA4B15A5 |
| 1002:6819 | 106b:014e | AMD        | Pitcairn PRO [Radeon HD 7... | 6     | radeon     | 520FC2DB5C |
| 1002:68c0 | 106b:00d2 | AMD        | Madison [Mobility Radeon ... | 6     | radeon     | C5621D630D |
| 1002:9851 | 103c:8245 | AMD        | Mullins [Radeon R4/R5 Gra... | 6     | radeon     | 40434F824A |
| 1002:98e4 | 103c:8430 | AMD        | Stoney [Radeon R2/R3/R4/R... | 6     | amdgpu     | 5C5ADCC248 |
| 10de:0655 | 106b:0633 | Nvidia     | G96 [GeForce GT 120 Mac E... | 6     | nouveau    | D222E55136 |
| 8086:0152 | 1028:0548 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 6     | i915       | 8184B0981F |
| 8086:0162 | 1028:0543 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 6     | i915       | 0E4A62B59F |
| 8086:22b1 | 1028:06cc | Intel      | Atom/Celeron/Pentium Proc... | 6     | i915       | 3AC5DA5F93 |
| 8086:3185 | 1025:1304 | Intel      | GeminiLake [UHD Graphics ... | 6     | i915       | B7F823BFDA |
| 8086:3185 | 1854:0308 | Intel      | GeminiLake [UHD Graphics ... | 6     | i915       | 125F68D06E |
| 1002:67df | 106b:019e | AMD        | Ellesmere [Radeon RX 470/... | 5     | amdgpu     | 74EC4FCD5B |
| 1002:6840 | 144d:b091 | AMD        | Thames [Radeon HD 7500M/7... | 5     | radeon     | 0F9E022C5E |
| 1002:9553 | 1025:0266 | AMD        | RV710/M92 [Mobility Radeo... | 5     | radeon     | B24FDB7446 |
| 1002:9850 | 103c:8245 | AMD        | Mullins [Radeon R3 Graphics] | 5     | radeon     | 4D5B43BDDC |
| 10de:0dea | 17aa:366c | Nvidia     | GF108M [GeForce 610M]        | 5     | nouveau    | 42BC05AF33 |
| 10de:0df4 | 104d:907e | Nvidia     | GF108M [GeForce GT 540M]     | 5     | nouveau    | 626BFE0484 |
| 10de:0fea | 106b:011f | Nvidia     | GK107M [GeForce GT 755M M... | 5     | nvidia     | 20FB29A6AE |
| 10de:119d | 106b:0120 | Nvidia     | GK104M [GeForce GTX 775M ... | 5     | nouveau    | 6C0206DD85 |
| 10de:119e | 106b:0121 | Nvidia     | GK104M [GeForce GTX 780M ... | 5     | nouveau    | CCAB3D35E1 |
| 8086:0152 | 17aa:365e | Intel      | Xeon E3-1200 v2/3rd Gen C... | 5     | i915       | 31DA58CF2B |
| 8086:0412 | 17aa:367b | Intel      | Xeon E3-1200 v3/4th Gen C... | 5     | i915       | A459000D17 |
| 8086:0f31 | 17aa:3695 | Intel      | Atom Processor Z36xxx/Z37... | 5     | i915       | CB2927D290 |
| 8086:5912 | 103c:82dc | Intel      | HD Graphics 630              | 5     | i915       | 036481482E |
| 8086:5916 | 1028:0754 | Intel      | HD Graphics 620              | 5     | i915       | 83612FBDEE |
| 1002:6640 | 106b:014b | AMD        | Saturn XT [FirePro M6100]    | 4     | radeon     | F04DA4053D |
| 1002:6663 | 17aa:367b | AMD        | Sun PRO [Radeon HD 8570A/... | 4     | radeon     | A459000D17 |
| 1002:67ef | 106b:016a | AMD        | Baffin [Radeon RX 460/560... | 4     | amdgpu     | 523B31291C |
| 1002:67ef | 106b:0197 | AMD        | Baffin [Radeon RX 460/560... | 4     | amdgpu     | B7CD69DE99 |
| 10de:0de5 | 174b:7162 | Nvidia     | GF108 [GeForce GT 530]       | 4     | nouveau    | 22317B4B49 |
| 10de:11a3 | 106b:010d | Nvidia     | GK104M [GeForce GTX 680MX]   | 4     | nouveau    | 674668F4DD |
| 8086:0412 | 103c:18e6 | Intel      | Xeon E3-1200 v3/4th Gen C... | 4     | i915       | CF3ED91B8A |
| 8086:041e | 1028:0623 | Intel      | 4th Generation Core Proce... | 4     | i915       | 3C11289E85 |
| 8086:1622 | 106b:014f | Intel      | Iris Pro Graphics 6200       | 4     | i915       | 74E99D5666 |
| 8086:162b | 1e50:8002 | Intel      | Iris Graphics 6100           | 4     | i915       | 6CF5332D62 |
| 8086:1912 | 103c:81b7 | Intel      | HD Graphics 530              | 4     | i915       | AA69312028 |
| 8086:1912 | 8086:1912 | Intel      | HD Graphics 530              | 4     | i915       | 31E48D8DA1 |
| 8086:3184 | 103c:86f0 | Intel      | GeminiLake [UHD Graphics ... | 4     | i915       | 9FDCC0F2AF |
| 8086:3185 | 1043:1ea0 | Intel      | GeminiLake [UHD Graphics ... | 4     | i915       | 3B910E6A74 |
| 8086:3185 | 8086:2212 | Intel      | GeminiLake [UHD Graphics ... | 4     | i915       | 32E5618CFE |
| 8086:3e92 | 103c:84ee | Intel      | CometLake-S GT2 [UHD Grap... | 4     | i915       | DF07E6AAB4 |
| 8086:3ea0 | 1043:17b1 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 4     | i915       | 72FCC11E52 |
| 8086:5916 | 103c:82dd | Intel      | HD Graphics 620              | 4     | i915       | 0A0BE4F02F |
| 8086:5a85 | 17aa:36c4 | Intel      | HD Graphics 500              | 4     | i915       | 4B68C7AEE7 |
| 8086:a001 | 17aa:3610 | Intel      | Atom Processor D4xx/D5xx/... | 4     | i915       | 5DFF29AF66 |
| 1002:15d8 | 103c:86f3 | AMD        | Picasso                      | 3     | amdgpu     | 4B12BB887A |
| 1002:15dd | 17aa:36f5 | AMD        | Raven Ridge [Radeon Vega ... | 3     | amdgpu     | EB38810FB8 |
| 1002:6760 | 104d:9087 | AMD        | Seymour [Radeon HD 6400M/... | 3     | radeon     | EEB433BF77 |
| 1002:67df | 106b:0163 | AMD        | Ellesmere [Radeon RX 470/... | 3     | amdgpu     | EA0E6932CF |
| 1002:67ef | 106b:019f | AMD        | Baffin [Radeon RX 460/560... | 3     | amdgpu     | 53D9AA344F |
| 1002:68e0 | 1028:0478 | AMD        | Park [Mobility Radeon HD ... | 3     | radeon     | A288705A4D |
| 1002:6938 | 106b:013a | AMD        | Tonga XT / Amethyst XT [R... | 3     | amdgpu     | 7D12EF42AC |
| 1002:9712 | 1028:0479 | AMD        | RS880M [Mobility Radeon H... | 3     | radeon     | F7EF0F2C13 |
| 1002:9809 | 17aa:3670 | AMD        | Wrestler [Radeon HD 7310]    | 3     | radeon     | 225E0C36DC |
| 1002:9850 | 103c:2b3b | AMD        | Mullins [Radeon R3 Graphics] | 3     | radeon     | 1A5D2C36EC |
| 1002:9851 | 1028:06d1 | AMD        | Mullins [Radeon R4/R5 Gra... | 3     | radeon     | 05A046D623 |
| 1002:9851 | 103c:2b3b | AMD        | Mullins [Radeon R4/R5 Gra... | 3     | radeon     | BA4DA15B98 |
| 1002:9851 | 17aa:36ab | AMD        | Mullins [Radeon R4/R5 Gra... | 3     | radeon     | 93BC9B0BE9 |
| 1002:9853 | 103c:2b2f | AMD        | Mullins [Radeon R2 Graphics] | 3     | radeon     | 093F49B44C |
| 10de:0df5 | 1028:0511 | Nvidia     | GF108M [GeForce GT 525M]     | 3     | nouveau    | 6E0B7C86D5 |
| 10de:0fd2 | 104d:9097 | Nvidia     | GK107M [GeForce GT 640M]     | 3     | nouveau    | B2B912EF1E |
| 10de:0fd5 | 106b:010a | Nvidia     | GK107M [GeForce GT 650M M... | 3     | nvidia     | 5C0A369ED2 |
| 10de:134e | 103c:82dc | Nvidia     | GM108M [GeForce 930MX]       | 3     | nvidia     | 83064FB44F |
| 10de:174d | 1025:1418 | Nvidia     | GM108M [GeForce MX130]       | 3     | nvidia     | 5820A2D4C3 |
| 10de:174e | 1028:0852 | Nvidia     | GM108M [GeForce MX110]       | 3     | nouveau    | 5A27DEAF8A |
| 8086:0102 | 1025:0618 | Intel      | 2nd Generation Core Proce... | 3     | i915       | 0362E43257 |
| 8086:0106 | 1043:844d | Intel      | 2nd Generation Core Proce... | 3     | i915       | 61B5866007 |
| 8086:0106 | 17aa:3671 | Intel      | 2nd Generation Core Proce... | 3     | i915       | ADE7CDF9A4 |
| 8086:0116 | 104d:9087 | Intel      | 2nd Generation Core Proce... | 3     | i915       | EEB433BF77 |
| 8086:0152 | 1028:0543 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 3     | i915       | AF055D20B7 |
| 8086:0152 | 103c:2aed | Intel      | Xeon E3-1200 v2/3rd Gen C... | 3     | i915       | 00FCD6CB57 |
| 8086:0166 | 1025:0792 | Intel      | 3rd Gen Core processor Gr... | 3     | i915       | 89F713C877 |
| 8086:0166 | 1854:0167 | Intel      | 3rd Gen Core processor Gr... | 3     | i915       | D0CF0BEEA8 |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 13    |            | 4B12BB887A |
| 1022:1577 | 1028:07e3 | AMD        | Family 15h (Models 60h-6f... | 3     |            | ACCB6ADA09 |
| 1022:1481 | 1022:1481 | AMD        | Starship/Matisse IOMMU       | 2     |            | 991A74F3E5 |
| 1022:1577 | 17aa:36ec | AMD        | Family 15h (Models 60h-6f... | 2     |            | 2CFA2D338E |
| 1022:1631 | 17aa:371c | AMD        | Renoir IOMMU                 | 2     |            | 65195D0D22 |
| 1022:1451 | 1028:07e4 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 0B1F7CCED7 |
| 1022:1481 | 1043:87c0 | AMD        | Starship/Matisse IOMMU       | 1     |            | 577AD83B8F |
| 1022:1577 | 1028:0855 | AMD        | Family 15h (Models 60h-6f... | 1     |            | DACA9432F8 |
| 1022:1577 | 17aa:36c6 | AMD        | Family 15h (Models 60h-6f... | 1     |            | 5DA9F63B49 |
| 1022:1631 | 103c:86ee | AMD        | Renoir IOMMU                 | 1     |            | 8579540A18 |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816c | 1025:1290 | Realtek... | RTL8111xP IPMI interface     | 2     |            | A27363041A |
| 10ec:816c | 1025:1291 | Realtek... | RTL8111xP IPMI interface     | 1     |            | 866F2F8C49 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0a88 |           | Nvidia     | MCP79 Memory Controller      | 46    |            | 8AB1BA226D |
| 10de:0a89 |           | Nvidia     | MCP79 Memory Controller      | 46    |            | 8AB1BA226D |
| 10de:0a98 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 46    |            | 8AB1BA226D |
| 10de:0aa4 |           | Nvidia     | MCP79 Memory Controller      | 46    |            | 8AB1BA226D |
| 8086:a121 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 28    |            | E53C63BA89 |
| 8086:a36f | 8086:7270 | Intel      | Cannon Lake PCH Shared SRAM  | 19    |            | 9440CC0137 |
| 8086:a36f |           | Intel      | Cannon Lake PCH Shared SRAM  | 16    |            | EB3D04E089 |
| 8086:9d21 | 103c:84de | Intel      | Sunrise Point-LP PMC         | 12    |            | B5E9340D85 |
| 8086:9d21 | 8086:9d21 | Intel      | Sunrise Point-LP PMC         | 10    | intel_p... | 1096F1F298 |
| 8086:9d21 | 1025:1287 | Intel      | Sunrise Point-LP PMC         | 9     | intel_p... | EB23862DED |
| 10de:0568 | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] Mem... | 7     |            | 04B8123AA5 |
| 10de:0751 | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] Mem... | 7     |            | 04B8123AA5 |
| 10de:0754 | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] Mem... | 7     |            | 04B8123AA5 |
| 8086:9d21 | 1028:0754 | Intel      | Sunrise Point-LP PMC         | 5     |            | 83612FBDEE |
| 8086:a121 | 103c:82dc | Intel      | 100 Series/C230 Series Ch... | 5     |            | 036481482E |
| 8086:a121 | 8086:a121 | Intel      | 100 Series/C230 Series Ch... | 5     |            | 31E48D8DA1 |
| 8086:34ef | 8086:7270 | Intel      | Ice Lake-LP DRAM Controller  | 4     |            | 49834DA4FA |
| 8086:9d21 | 103c:82dd | Intel      | Sunrise Point-LP PMC         | 4     |            | 0A0BE4F02F |
| 8086:9def | 8086:7270 | Intel      | Cannon Point-LP Shared SRAM  | 4     |            | 72FCC11E52 |
| 8086:a121 | 103c:81b7 | Intel      | 100 Series/C230 Series Ch... | 4     |            | AA69312028 |
| 8086:06ef | 8086:7270 | Intel      | Comet Lake PCH Shared SRAM   | 3     |            | B928A63EF1 |
| 8086:9d21 | 1028:0852 | Intel      | Sunrise Point-LP PMC         | 3     |            | 5A27DEAF8A |
| 8086:9d21 | 1043:12a1 | Intel      | Sunrise Point-LP PMC         | 3     |            | E0EF808E3F |
| 8086:9d21 | 8086:7270 | Intel      | Sunrise Point-LP PMC         | 3     |            | 94DEDAFA8A |
| 8086:a121 | 17aa:30ba | Intel      | 100 Series/C230 Series Ch... | 3     |            | F3E9E0B2F5 |
| 8086:a2a1 | 103c:838b | Intel      | 200 Series/Z370 Chipset F... | 3     |            | A8811301BC |
| 8086:02ef | 1028:0954 | Intel      | Comet Lake PCH-LP Shared ... | 2     |            | 51D212B73F |
| 8086:9d21 | 17aa:3630 | Intel      | Sunrise Point-LP PMC         | 2     |            | F96B4E9ECA |
| 8086:9d21 | 17aa:36dc | Intel      | Sunrise Point-LP PMC         | 2     |            | CD5915910D |
| 8086:9def | 17aa:36fe | Intel      | Cannon Point-LP Shared SRAM  | 2     |            | CA86244C1D |
| 8086:a121 | 1025:1063 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 2B787D7F5F |
| 8086:a121 | 1028:06c5 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 0E09B99FC0 |
| 8086:a121 | 1028:06d4 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 275E0EEAEF |
| 8086:a121 | 1028:075d | Intel      | 100 Series/C230 Series Ch... | 2     |            | 404A8B3A68 |
| 8086:a121 | 103c:2b3e | Intel      | 100 Series/C230 Series Ch... | 2     |            | E370DBFC53 |
| 8086:a121 | 103c:8058 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 09B55E64F6 |
| 8086:a121 | 17aa:30fc | Intel      | 100 Series/C230 Series Ch... | 2     |            | 4740E3EA20 |
| 8086:a121 | 17aa:3636 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 3F2A054B58 |
| 8086:a121 | 17aa:36bc | Intel      | 100 Series/C230 Series Ch... | 2     |            | F9C1063722 |
| 8086:a2a1 | 103c:829b | Intel      | 200 Series/Z370 Chipset F... | 2     |            | 44675B1F55 |
| 8086:a2a1 | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 2     |            | DA913ED8D3 |
| 8086:a2a1 | 17aa:3718 | Intel      | 200 Series/Z370 Chipset F... | 2     |            | 78AB4FCC2D |
| 8086:a2a1 | 8086:7270 | Intel      | 200 Series/Z370 Chipset F... | 2     |            | 43CB3AF3A5 |
| 8086:a36f | 1025:1290 | Intel      | Cannon Lake PCH Shared SRAM  | 2     |            | A27363041A |
| 8086:a36f | 103c:85a2 | Intel      | Cannon Lake PCH Shared SRAM  | 2     |            | 930847F29A |
| 8086:a36f | 17aa:313d | Intel      | Cannon Lake PCH Shared SRAM  | 2     |            | 50AAA5CF43 |
| 8086:a36f | 17aa:36f4 | Intel      | Cannon Lake PCH Shared SRAM  | 2     |            | 773BE13AA2 |
| 8086:a36f | 17aa:3701 | Intel      | Cannon Lake PCH Shared SRAM  | 2     |            | 3AAB28E1E4 |
| 8086:a3a1 | 8086:7270 | Intel      | Memory controller            | 2     |            | E8A54D0908 |
| 10de:0a88 | 1462:4570 | Nvidia     | MCP79 Memory Controller      | 1     |            | EE06AF7B45 |
| 10de:0a89 | 1462:4570 | Nvidia     | MCP79 Memory Controller      | 1     |            | EE06AF7B45 |
| 10de:0aa4 | 1462:4570 | Nvidia     | MCP79 Memory Controller      | 1     |            | EE06AF7B45 |
| 8086:02ef | 1028:0953 | Intel      | Comet Lake PCH-LP Shared ... | 1     |            | D77787D6EC |
| 8086:02ef | 17aa:3185 | Intel      | Comet Lake PCH-LP Shared ... | 1     |            | 324F862858 |
| 8086:02ef | 17aa:370b | Intel      | Comet Lake PCH-LP Shared ... | 1     |            | F179844FE4 |
| 8086:02ef | 17aa:370c | Intel      | Comet Lake PCH-LP Shared ... | 1     |            | E678313D40 |
| 8086:02ef | 8086:7270 | Intel      | Comet Lake PCH-LP Shared ... | 1     |            | 19963E0F47 |
| 8086:06ef |           | Intel      | Comet Lake PCH Shared SRAM   | 1     |            | 0E4DAA1DE2 |
| 8086:06ef | 103c:871c | Intel      | Comet Lake PCH Shared SRAM   | 1     |            | 2F7FD6200F |
| 8086:34ef | 1025:1434 | Intel      | Ice Lake-LP DRAM Controller  | 1     |            | D8FFD8A934 |
| 8086:9d21 | 1025:102b | Intel      | Sunrise Point-LP PMC         | 1     |            | E470B33078 |
| 8086:9d21 | 1025:1130 | Intel      | Sunrise Point-LP PMC         | 1     |            | D33236ABB3 |
| 8086:9d21 | 1028:074b | Intel      | Sunrise Point-LP PMC         | 1     |            | 0DE1EB4A35 |
| 8086:9d21 | 1028:0853 | Intel      | Sunrise Point-LP PMC         | 1     |            | 107F431AD7 |
| 8086:9d21 | 103c:81ba | Intel      | Sunrise Point-LP PMC         | 1     |            | 00A2BE4ED1 |
| 8086:9d21 | 1297:2077 | Intel      | Sunrise Point-LP PMC         | 1     |            | 2DCDB3995E |
| 8086:9d21 | 144d:c133 | Intel      | Sunrise Point-LP PMC         | 1     |            | 39977FE582 |
| 8086:9d21 | 144d:c160 | Intel      | Sunrise Point-LP PMC         | 1     |            | F3306807BA |
| 8086:9d21 | 17aa:36df | Intel      | Sunrise Point-LP PMC         | 1     |            | F6B6499298 |
| 8086:a0ef | 1043:1482 | Intel      | Tiger Lake-LP Shared SRAM    | 1     |            | 8D0477EA03 |
| 8086:a121 | 1025:1052 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 9C5ED5E063 |
| 8086:a121 | 1028:06c6 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 69820330AA |
| 8086:a121 | 1028:075c | Intel      | 100 Series/C230 Series Ch... | 1     |            | 071C584451 |
| 8086:a121 | 103c:805e | Intel      | 100 Series/C230 Series Ch... | 1     |            | FDD0A4E977 |
| 8086:a121 | 103c:82f3 | Intel      | 100 Series/C230 Series Ch... | 1     |            | E25D57F967 |
| 8086:a121 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 1     |            | E13500CDFD |
| 8086:a121 | 1071:0752 | Intel      | 100 Series/C230 Series Ch... | 1     |            | F27AEE762C |
| 8086:a121 | 1462:aac1 | Intel      | 100 Series/C230 Series Ch... | 1     |            | D77183679A |
| 8086:a121 | 1462:aea1 | Intel      | 100 Series/C230 Series Ch... | 1     |            | E033B6FBEA |
| 8086:a121 | 1462:b090 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 8E135DE620 |
| 8086:a121 | 17aa:3113 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 7739219D01 |
| 8086:a121 | 17aa:36bb | Intel      | 100 Series/C230 Series Ch... | 1     |            | B790C5FA32 |
| 8086:a121 | 17aa:36cc | Intel      | 100 Series/C230 Series Ch... | 1     |            | 9A305C10EC |
| 8086:a2a1 | 1019:a5a1 | Intel      | 200 Series/Z370 Chipset F... | 1     |            | A8A11B1A92 |
| 8086:a2a1 | 1028:079c | Intel      | 200 Series/Z370 Chipset F... | 1     |            | 4F4887AB67 |
| 8086:a2a1 | 1028:079e | Intel      | 200 Series/Z370 Chipset F... | 1     |            | 2BF103DD36 |
| 8086:a2a1 | 103c:826a | Intel      | 200 Series/Z370 Chipset F... | 1     |            | C60FCEAEE4 |
| 8086:a2a1 | 103c:82a6 | Intel      | 200 Series/Z370 Chipset F... | 1     |            | DD3E2FA2B5 |
| 8086:a2a1 | 17aa:36dd | Intel      | 200 Series/Z370 Chipset F... | 1     |            | 7EBBF6AAD0 |
| 8086:a36f | 1025:126c | Intel      | Cannon Lake PCH Shared SRAM  | 1     |            | C1339E884A |
| 8086:a36f | 1025:1291 | Intel      | Cannon Lake PCH Shared SRAM  | 1     |            | 866F2F8C49 |
| 8086:a36f | 1028:0851 | Intel      | Cannon Lake PCH Shared SRAM  | 1     |            | 05D6B79D2F |
| 8086:a36f | 103c:83eb | Intel      | Cannon Lake PCH Shared SRAM  | 1     |            | C73E03D65D |
| 8086:a36f | 17aa:3123 | Intel      | Cannon Lake PCH Shared SRAM  | 1     |            | 943F3319E9 |
| 8086:a36f | 17aa:313b | Intel      | Cannon Lake PCH Shared SRAM  | 1     |            | 56D6E59000 |
| 8086:a36f | 17aa:36f2 | Intel      | Cannon Lake PCH Shared SRAM  | 1     |            | F172B5B1EA |
| 8086:a3a1 | 103c:86f7 | Intel      | Memory controller            | 1     |            | 82E222B1FA |
| 8086:a3a1 | 17aa:3184 | Intel      | Memory controller            | 1     |            | BD5551C49A |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1131:7231 | 1461:2a0f | Philips... | SAA7231                      | 8     |            | 8D3C2E38D3 |
| 1002:ac12 | 12ab:0003 | AMD        | Theater HD T507 (DVB-T) T... | 4     |            | 69574214D7 |
| 1022:15e2 | 17aa:36f5 | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | EB38810FB8 |
| 1131:7231 | 1461:2b0f | Philips... | SAA7231                      | 3     |            | 42BC05AF33 |
| 1022:15e2 | 17aa:371c | AMD        | Raven/Raven2/FireFlight/R... | 2     |            | 65195D0D22 |
| 1002:ac12 | 1002:b539 | AMD        | Theater HD T507 (DVB-T) T... | 1     |            | DD5E0979B0 |
| 1022:15e2 | 1022:15e2 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | 91A80D30D0 |
| 1022:15e2 | 17aa:371d | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | 98A498AE78 |
| 10cf:2030 | 104d:9053 | Fujitsu... | Fujitsu Multimedia contro... | 1     |            | CFDCAC5734 |
| 10cf:2030 | 104d:9062 | Fujitsu... | Fujitsu Multimedia contro... | 1     |            | 2628EBE1BB |
| 10cf:2036 | 104d:906e | Fujitsu... | DT-XXX                       | 1     |            | 68937CF6BB |
| 1131:7160 | 1461:2155 | Philips... | SAA7160                      | 1     |            | 27E7D42D53 |
| 1131:7231 | 1461:2b07 | Philips... | SAA7231                      | 1     |            | 8672A3F85D |
| 1745:3000 | 104d:9049 | ViXS Sy... | Colossus Encoder             | 1     |            | 2628EBE1BB |
| 1745:3000 | 1bcf:a023 | ViXS Sy... | Colossus Encoder             | 1     |            | 1494683BB9 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:1686 | 14e4:1686 | Broadcom   | NetXtreme BCM57766 Gigabi... | 103   | tg3        | EB3D04E089 |
| 11ab:436a | 11ab:00ba | Marvell... | 88E8058 PCI-E Gigabit Eth... | 77    | sky2       | 00CC913F3D |
| 14e4:16b4 | 14e4:16b4 | Broadcom   | NetXtreme BCM57765 Gigabi... | 63    | tg3        | 2216DC8384 |
| 10de:0ab0 | 10de:cb79 | Nvidia     | MCP79 Ethernet               | 46    | forcedeth  | 8AB1BA226D |
| 14e4:1684 | 14e4:1684 | Broadcom   | NetXtreme BCM5764M Gigabi... | 44    | tg3        | C5621D630D |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 26    | r8169      | 32E5618CFE |
| 10ec:8168 | 1025:8000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 18    | r8169      | D0F0DA0187 |
| 11ab:4362 | 11ab:5321 | Marvell... | 88E8053 PCI-E Gigabit Eth... | 17    | sky2       | 394EF62F20 |
| 10ec:8168 | 1b50:4606 | Realtek... | RTL8111/8168/8411 PCI Exp... | 15    | r8169      | B7F823BFDA |
| 10ec:8168 | 1043:205f | Realtek... | RTL8111/8168/8411 PCI Exp... | 14    | r8169      | 8D0477EA03 |
| 10ec:8168 | 103c:84de | Realtek... | RTL8111/8168/8411 PCI Exp... | 12    | r8169      | B5E9340D85 |
| 10ec:8168 | 17aa:365e | Realtek... | RTL8111/8168/8411 PCI Exp... | 12    | r8169      | 9164B5B105 |
| 10ec:8168 | 103c:2ac5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 11    | r8169      | 55450C73C0 |
| 10ec:8168 | 103c:8245 | Realtek... | RTL8111/8168/8411 PCI Exp... | 11    | r8169      | 40434F824A |
| 10ec:8168 | 1025:0266 | Realtek... | RTL8111/8168/8411 PCI Exp... | 9     | r8169      | B24FDB7446 |
| 10ec:8168 | 1025:1287 | Realtek... | RTL8111/8168/8411 PCI Exp... | 9     | r8169      | EB23862DED |
| 10ec:8168 | 1043:858f | Realtek... | RTL8111/8168/8411 PCI Exp... | 9     | r8169      | 1096F1F298 |
| 1969:1091 | 1028:0548 | Qualcom... | AR8161 Gigabit Ethernet      | 9     | alx        | 8184B0981F |
| 10ec:8168 | 1028:05db | Realtek... | RTL8111/8168/8411 PCI Exp... | 8     | r8169      | 80CA4B15A5 |
| 10ec:8168 | 103c:8381 | Realtek... | RTL8111/8168/8411 PCI Exp... | 8     | r8169      | B4A3EC103B |
| 10ec:8168 | 144d:b091 | Realtek... | RTL8111/8168/8411 PCI Exp... | 8     | r8169      | 0F9E022C5E |
| 10de:0760 | 1025:8000 | Nvidia     | MCP77 Ethernet               | 7     | forcedeth  | 04B8123AA5 |
| 10ec:8168 | 1028:0511 | Realtek... | RTL8111/8168/8411 PCI Exp... | 7     | r8169      | 5C781B927F |
| 10ec:8168 | 103c:81bb | Realtek... | RTL8111/8168/8411 PCI Exp... | 7     | r8169      | CA80EA46C5 |
| 10ec:8168 | 1043:200f | Realtek... | RTL8111/8168/8411 PCI Exp... | 7     | r8169      | 608D0CE708 |
| 10ec:8168 | 17aa:366c | Realtek... | RTL8111/8168/8411 PCI Exp... | 7     | r8169      | 3903A96DE3 |
| 14e4:1686 | 106b:0110 | Broadcom   | NetXtreme BCM57766 Gigabi... | 7     | tg3        | 674668F4DD |
| 8086:153a | 1028:05a7 | Intel      | Ethernet Connection I217-LM  | 7     | e1000e     | 16927C4FC4 |
| 10ec:8168 | 1028:06cc | Realtek... | RTL8111/8168/8411 PCI Exp... | 6     | r8169      | 3AC5DA5F93 |
| 10ec:8168 | 103c:2b3b | Realtek... | RTL8111/8168/8411 PCI Exp... | 6     | r8169      | 1A5D2C36EC |
| 10ec:8168 | 103c:8430 | Realtek... | RTL8111/8168/8411 PCI Exp... | 6     | r8169      | 5C5ADCC248 |
| 10ec:8168 | 103c:84ee | Realtek... | RTL8111/8168/8411 PCI Exp... | 6     | r8169      | DF07E6AAB4 |
| 10ec:8168 | 104d:907e | Realtek... | RTL8111/8168/8411 PCI Exp... | 6     | r8169      | 626BFE0484 |
| 10ec:8168 | 1854:0308 | Realtek... | RTL8111/8168/8411 PCI Exp... | 6     | r8169      | 125F68D06E |
| 8086:153a | 103c:18e6 | Intel      | Ethernet Connection I217-LM  | 6     | e1000e     | CF3ED91B8A |
| 10ec:8136 | 1028:0754 | Realtek... | RTL810xE PCI Express Fast... | 5     | r8169      | 83612FBDEE |
| 10ec:8136 | 10ec:8136 | Realtek... | RTL810xE PCI Express Fast... | 5     | r8169      | 84027725C5 |
| 10ec:8168 | 1019:811e | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8169      | 79A4A7BBDD |
| 10ec:8168 | 103c:82dc | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8169      | 036481482E |
| 10ec:8168 | 1043:84cd | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8169      | 11466C75B0 |
| 10ec:8168 | 104d:9083 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8169      | EEB433BF77 |
| 10ec:8168 | 104d:9097 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8169      | B2B912EF1E |
| 10ec:8168 | 17aa:3671 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8169      | 2A92010AD3 |
| 10ec:8168 | 17aa:367b | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8169      | A459000D17 |
| 10ec:8168 | 17aa:3695 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8168      | CB2927D290 |
| 10ec:8168 | 17aa:36ab | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8169      | 9A0E5BD73B |
| 10ec:8168 | 17aa:36c4 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8169      | 4B68C7AEE7 |
| 10ec:8168 | 1028:0623 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 3C11289E85 |
| 10ec:8168 | 1028:07e4 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | ACCB6ADA09 |
| 10ec:8168 | 103c:81b7 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | AA69312028 |
| 10ec:8168 | 103c:82dd | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 0A0BE4F02F |
| 10ec:8168 | 103c:8446 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 651C327218 |
| 10ec:8168 | 103c:86f0 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 9FDCC0F2AF |
| 10ec:8168 | 1043:204f | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | BA03906EB8 |
| 10ec:8168 | 1043:8432 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 0554804F5F |
| 10ec:8168 | 17aa:3686 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 1E467924BF |
| 10ec:8136 | 103c:2b2f | Realtek... | RTL810xE PCI Express Fast... | 3     | r8169      | 093F49B44C |
| 10ec:8168 | 1025:0275 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 49DF2710DC |
| 10ec:8168 | 1025:0720 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | B972470309 |
| 10ec:8168 | 1025:0792 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 89F713C877 |
| 10ec:8168 | 1025:0992 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | F2703DFC7E |
| 10ec:8168 | 1025:0994 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 6247D83BAB |
| 10ec:8168 | 1028:0478 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | A288705A4D |
| 10ec:8168 | 1028:0479 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | F7EF0F2C13 |
| 10ec:8168 | 1028:06d1 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 05A046D623 |
| 10ec:8168 | 1028:0852 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 5A27DEAF8A |
| 10ec:8168 | 103c:2aed | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 00FCD6CB57 |
| 10ec:8168 | 103c:838b | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | A8811301BC |
| 10ec:8168 | 103c:86f3 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 4B12BB887A |
| 10ec:8168 | 1043:208f | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | E0EF808E3F |
| 10ec:8168 | 1297:2032 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 26A6CD4678 |
| 10ec:8168 | 1297:2053 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | FFF1EFB11D |
| 10ec:8168 | 17aa:3670 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 225E0C36DC |
| 10ec:8168 | 17aa:3685 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 647613F22B |
| 10ec:8168 | 17aa:36f5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | EB38810FB8 |
| 10ec:8168 | 1854:0167 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | D0CF0BEEA8 |
| 10ec:8168 | 1854:0200 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 40E267DF98 |
| 10ec:8168 | 1854:0267 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 41FA541CA4 |
| 10ec:8168 | 1b0a:0188 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 0C24A93146 |
| 10ec:8168 | 1b50:4607 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 5820A2D4C3 |
| 8086:153a | 1028:0626 | Intel      | Ethernet Connection I217-LM  | 3     | e1000e     | F61158882E |
| 8086:15b7 | 17aa:30ba | Intel      | Ethernet Connection (2) I... | 3     | e1000e     | F3E9E0B2F5 |
| 10ec:8136 | 17aa:3602 | Realtek... | RTL810xE PCI Express Fast... | 2     | r8169      | 60AE7E3358 |
| 10ec:8168 | 1019:7c94 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 4FF205BED4 |
| 10ec:8168 | 1025:025a | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | CA89C2F311 |
| 10ec:8168 | 1025:085f | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 90FF435FAD |
| 10ec:8168 | 1025:098f | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 350CC83AC7 |
| 10ec:8168 | 1025:1063 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 2B787D7F5F |
| 10ec:8168 | 1025:1065 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 21CA50C386 |
| 10ec:8168 | 1025:1290 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | A27363041A |
| 10ec:8168 | 1028:05b0 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | BDF125B54E |
| 10ec:8168 | 1028:05c2 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 3E115C67CD |
| 10ec:8168 | 1028:0628 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | BB462BF2F6 |
| 10ec:8168 | 1028:06d4 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 275E0EEAEF |
| 10ec:8168 | 1028:0954 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8168      | 51D212B73F |
| 10ec:8168 | 103c:2179 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 7B6E93783B |
| 10ec:8168 | 103c:2afc | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 7A71F7247E |
| 10ec:8168 | 103c:2b0a | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | BA22741458 |
| 10ec:8168 | 103c:2b0d | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 5C13B7BB96 |
| 10ec:8168 | 103c:2b13 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 991915273E |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 168c:002a | 106b:008f | Qualcom... | AR928X Wireless Network A... | 62    | ath9k      | 8AB1BA226D |
| 168c:0030 | 106b:009a | Qualcom... | AR93xx Wireless Network A... | 62    | ath9k      | 2216DC8384 |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 48    | rtl8821ce  | 4B12BB887A |
| 14e4:4328 | 106b:008c | Broadcom   | BCM4321 802.11a/b/g/n        | 42    | wl         | 00CC913F3D |
| 14e4:4328 | 106b:0088 | Broadcom   | BCM4321 802.11a/b/g/n        | 35    | wl         | 950D5432A8 |
| 14e4:43a0 | 106b:0111 | Broadcom   | BCM4360 802.11ac Wireless... | 33    | wl         | 20FB29A6AE |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 33    | iwlwifi    | EB23862DED |
| 14e4:432b | 106b:008e | Broadcom   | BCM4322 802.11a/b/g/n Wir... | 27    | wl         | 4AD5BC744A |
| 10ec:b723 | 103c:81c1 | Realtek... | RTL8723BE PCIe Wireless N... | 23    | rtl8723be  | 40434F824A |
| 168c:0042 | 1a3b:2231 | Qualcom... | QCA9377 802.11ac Wireless... | 21    | ath10k_pci | 1096F1F298 |
| 14e4:4331 | 106b:00f4 | Broadco... | BCM4331 802.11a/b/g/n        | 20    | wl         | DAE7632445 |
| 14e4:4464 | 106b:07bf | Broadcom   | BCM4364 802.11ac Wireless... | 19    | brcmfmac   | EB3D04E089 |
| 10ec:8179 | 17aa:0179 | Realtek... | RTL8188EE Wireless Networ... | 18    | rtl8188ee  | 766F235D4B |
| 10ec:8176 | 10ec:8176 | Realtek... | RTL8188CE 802.11b/g/n WiF... | 14    | rtl8192ce  | DD885000B5 |
| 168c:0032 | 17aa:3118 | Qualcom... | AR9485 Wireless Network A... | 14    | ath9k      | 9164B5B105 |
| 168c:0034 | 11ad:6621 | Qualcom... | AR9462 Wireless Network A... | 14    | ath9k      | D0F0DA0187 |
| 168c:0042 | 17aa:0901 | Qualcom... | QCA9377 802.11ac Wireless... | 14    | ath10k_pci | CD5915910D |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 14    | iwlwifi    | F2703DFC7E |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 14    | iwlwifi    | 50AAA5CF43 |
| 10ec:c821 | 17aa:c024 | Realtek... | RTL8821CE 802.11ac PCIe W... | 13    | 8821ce     | F179844FE4 |
| 1814:3090 | 11ad:6622 | Ralink     | RT3090 Wireless 802.11n 1... | 13    | rt2800pci  | 0362E43257 |
| 10ec:b822 | 103c:831b | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 12    | rtw_pci    | DF07E6AAB4 |
| 14e4:43ba | 106b:014a | Broadcom   | BCM43602 802.11ac Wireles... | 11    | brcmfmac   | E53C63BA89 |
| 14e4:43ba | 106b:016e | Broadcom   | BCM43602 802.11ac Wireles... | 11    | brcmfmac   | 632B6526F7 |
| 168c:0036 | 1028:020c | Qualcom... | QCA9565 / AR9565 Wireless... | 11    | ath9k      | 80CA4B15A5 |
| 168c:0036 | 1028:020e | Qualcom... | QCA9565 / AR9565 Wireless... | 11    | ath9k      | 6E2C90AC7B |
| 1814:5390 | 1814:f051 | Ralink     | RT5390 Wireless 802.11n 1... | 11    | rt2800pci  | 55450C73C0 |
| 168c:002b | 1a3b:1089 | Qualcom... | AR9285 Wireless Network A... | 10    | ath9k      | 0554804F5F |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 10    | iwlwifi    | AA69312028 |
| 10ec:8179 | 1a3b:1f38 | Realtek... | RTL8188EE Wireless Networ... | 9     | rtl8188ee  | A8BF79BC54 |
| 14e4:4328 | 106b:0087 | Broadco... | BCM4321 802.11a/b/g/n        | 9     | ssb        | B513DFD9C0 |
| 168c:0032 | 1028:0209 | Qualcom... | AR9485 Wireless Network A... | 9     | ath9k      | 8184B0981F |
| 8086:08b3 | 8086:8070 | Intel      | Wireless 3160                | 9     | iwlwifi    | 40E267DF98 |
| 10ec:8172 | 10ec:e021 | Realtek... | RTL8191SEvB Wireless LAN ... | 8     | rtl8192se  | B24FDB7446 |
| 168c:002b | 105b:e017 | Qualcom... | AR9285 Wireless Network A... | 8     | ath9k      | EEB433BF77 |
| 168c:002b | 105b:e037 | Qualcom... | AR9285 Wireless Network A... | 8     | ath9k      | 626BFE0484 |
| 168c:002b | 17aa:30a1 | Qualcom... | AR9285 Wireless Network A... | 8     | ath9k      | 5DFF29AF66 |
| 168c:0032 | 103c:1838 | Qualcom... | AR9485 Wireless Network A... | 8     | ath9k      | 5C07C319BD |
| 168c:0034 | 144d:4112 | Qualcom... | AR9462 Wireless Network A... | 8     | ath9k      | 0F9E022C5E |
| 14e4:4312 | 106b:0089 | Broadcom   | BCM4311 802.11a/b/g          | 7     | ssb        | 376EF8BAEC |
| 168c:003e | 1028:0310 | Qualcom... | QCA6174 802.11ac Wireless... | 7     | ath10k_pci | ACCB6ADA09 |
| 8086:3165 | 8086:4410 | Intel      | Wireless 3165                | 7     | iwlwifi    | 83612FBDEE |
| 8086:a370 | 8086:0034 | Intel      | Cannon Lake PCH CNVi WiFi    | 7     | iwlwifi    | C73E03D65D |
| 10ec:8179 | 103c:804b | Realtek... | RTL8188EE Wireless Networ... | 6     | rtl8188ee  | 1A5D2C36EC |
| 14e4:43a0 | 106b:0142 | Broadcom   | BCM4360 802.11ac Wireless... | 6     | wl         | 7D12EF42AC |
| 14e4:43ba | 106b:016f | Broadcom   | BCM43602 802.11ac Wireles... | 6     | brcmfmac   | EA0E6932CF |
| 14e4:4727 | 1028:0010 | Broadcom   | BCM4313 802.11bgn Wireles... | 6     | bcma       | A288705A4D |
| 168c:0036 | 17aa:3026 | Qualcom... | QCA9565 / AR9565 Wireless... | 6     | ath9k      | 5CADA9C3E7 |
| 10ec:8179 | 10ec:0189 | Realtek... | RTL8188EE Wireless Networ... | 5     | rtl8188ee  | B3E778A640 |
| 10ec:b723 | 17aa:b728 | Realtek... | RTL8723BE PCIe Wireless N... | 5     | rtl8723be  | 84248BB07C |
| 14e4:4359 | 14e4:05e2 | Broadcom   | BCM43228 802.11a/b/g/n       | 5     | wl         | EA47F5ADBE |
| 14e4:4727 | 14e4:051b | Broadcom   | BCM4313 802.11bgn Wireles... | 5     | wl         | BB1DFBE2CD |
| 168c:002a | 105b:e007 | Qualcom... | AR928X Wireless Network A... | 5     | ath9k      | EB74857893 |
| 168c:0032 | 105b:e044 | Qualcom... | AR9485 Wireless Network A... | 5     | ath9k      | B2B912EF1E |
| 168c:0042 | 1028:1810 | Qualcom... | QCA9377 802.11ac Wireless... | 5     | ath10k_pci | 107F431AD7 |
| 8086:0887 | 8086:4062 | Intel      | Centrino Wireless-N 2230     | 5     | iwlwifi    | D417AD3262 |
| 8086:088e | 8086:4460 | Intel      | Centrino Advanced-N 6235     | 5     | iwlwifi    | 23FDBD4CAA |
| 10ec:8176 | 1a3b:1139 | Realtek... | RTL8188CE 802.11b/g/n WiF... | 4     | rtl8192ce  | 46EE7CCE23 |
| 10ec:8723 | 1a3b:2114 | Realtek... | RTL8723AE PCIe Wireless N... | 4     | rtl8723ae  | 0C24A93146 |
| 10ec:8821 | 17aa:a803 | Realtek... | RTL8821AE 802.11ac PCIe W... | 4     | rtl8821ae  | FF239AD52E |
| 10ec:b723 | 10ec:8739 | Realtek... | RTL8723BE PCIe Wireless N... | 4     | rtl8723be  | 3AC5DA5F93 |
| 168c:002b | 1028:0205 | Qualcom... | AR9285 Wireless Network A... | 4     | ath9k      | D90E79C0B2 |
| 168c:0032 | 1a3b:1f86 | Qualcom... | AR9485 Wireless Network A... | 4     | ath9k      | 11466C75B0 |
| 168c:0036 | 11ad:0642 | Qualcom... | QCA9565 / AR9565 Wireless... | 4     | ath9k      | A586C561CC |
| 168c:0042 | 11ad:08a6 | Qualcom... | QCA9377 802.11ac Wireless... | 4     | ath10k_pci | E470B33078 |
| 168c:0042 | 1235:0901 | Qualcom... | QCA9377 802.11ac Wireless... | 4     | ath10k_pci | 086AAC0C2A |
| 1814:3090 | 1814:3090 | Ralink     | RT3090 Wireless 802.11n 1... | 4     | rt2800pci  | C8807A3887 |
| 1814:5390 | 1a3b:1155 | Ralink     | RT5390 Wireless 802.11n 1... | 4     | rt2800pci  | 4FF205BED4 |
| 8086:0091 | 8086:5221 | Intel      | Centrino Advanced-N 6230 ... | 4     | iwlwifi    | 5C781B927F |
| 8086:08b1 | 8086:c420 | Intel      | Wireless 7260                | 4     | iwlwifi    | 3C11289E85 |
| 8086:24f3 | 8086:0050 | Intel      | Wireless 8260                | 4     | iwlwifi    | 0E09B99FC0 |
| 8086:9df0 | 8086:0034 | Intel      | Cannon Point-LP CNVi [Wir... | 4     | iwlwifi    | 72FCC11E52 |
| 10ec:8179 | 1a3b:12a8 | Realtek... | RTL8188EE Wireless Networ... | 3     | rtl8188ee  | 6247D83BAB |
| 10ec:8821 | 17aa:a814 | Realtek... | RTL8821AE 802.11ac PCIe W... | 3     | rtl8821ae  | 4863245A0E |
| 10ec:8821 | 1a3b:2161 | Realtek... | RTL8821AE 802.11ac PCIe W... | 3     | rtl8821ae  | E20AC63341 |
| 10ec:b723 | 1a3b:2159 | Realtek... | RTL8723BE PCIe Wireless N... | 3     | rtl8723be  | B31B556424 |
| 14e4:4365 | 103c:804a | Broadcom   | BCM43142 802.11b/g/n         | 3     | wl         | BA4DA15B98 |
| 14e4:43ba | 106b:0156 | Broadcom   | BCM43602 802.11ac Wireles... | 3     | brcmfmac   | 0D0029DB58 |
| 14e4:43ba | 106b:016d | Broadcom   | BCM43602 802.11ac Wireles... | 3     | brcmfmac   | 94DEDAFA8A |
| 168c:0032 | 11ad:6627 | Qualcom... | AR9485 Wireless Network A... | 3     | ath9k      | 61B5866007 |
| 168c:0034 | 1a56:2003 | Qualcom... | AR9462 Wireless Network A... | 3     | ath9k      | BDF125B54E |
| 1814:539b | 103c:18ed | Ralink     | RT5390R 802.11bgn PCIe Wi... | 3     | rt2800pci  | 00FCD6CB57 |
| 8086:0084 | 8086:1315 | Intel      | Centrino Wireless-N 1000 ... | 3     | iwlwifi    | 03B15C1544 |
| 8086:02f0 | 8086:42a4 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 3     | iwlwifi    | 51D212B73F |
| 8086:24f3 | 8086:0010 | Intel      | Wireless 8260                | 3     | iwlwifi    | F3E9E0B2F5 |
| 8086:3165 | 8086:8110 | Intel      | Wireless 3165                | 3     | iwlwifi    | EDB63CD57D |
| 8086:31dc | 8086:0264 | Intel      | Gemini Lake PCH CNVi WiFi    | 3     | iwlwifi    | 32E5618CFE |
| 8086:34f0 | 8086:02a4 | Intel      | Ice Lake-LP PCH CNVi WiFi    | 3     | iwlwifi    | 5820A2D4C3 |
| 8086:a370 | 8086:4030 | Intel      | Cannon Lake PCH CNVi WiFi    | 3     | iwlwifi    | 9440CC0137 |
| 10ec:8171 | 10ec:8186 | Realtek... | RTL8191SEvA Wireless LAN ... | 2     | rtl8192se  | 19FBB5D44C |
| 10ec:8821 | 1a3b:216a | Realtek... | RTL8821AE 802.11ac PCIe W... | 2     | rtl8821ae  | 2146FDE0CF |
| 10ec:b723 | 17aa:b736 | Realtek... | RTL8723BE PCIe Wireless N... | 2     | rtl8723be  | 08057029E5 |
| 10ec:c821 | 10ec:c821 | Realtek... | RTL8821CE 802.11ac PCIe W... | 2     | rtl8821ce  | E8A54D0908 |
| 10ec:c822 | 103c:85f7 | Realtek... | RTL8822CE 802.11ac PCIe W... | 2     | rtwpci     | 8579540A18 |
| 14e4:4357 | 14e4:04da | Broadco... | BCM43225 802.11b/g/n         | 2     | bcma       | 1494683BB9 |
| 14e4:4359 | 1028:0014 | Broadcom   | BCM43228 802.11a/b/g/n       | 2     | wl         | 3E115C67CD |
| 14e4:4359 | 103c:2135 | Broadcom   | BCM43228 802.11a/b/g/n       | 2     | bcma_pc... | 5C13B7BB96 |
| 14e4:43ae | 17aa:0622 | Broadcom   | BCM43162 802.11ac Wireles... | 2     |            | 13561E5336 |
| 14e4:43ba | 106b:0155 | Broadco... | BCM43602 802.11ac Wireles... | 2     | brcmfmac   | 906BCD4AC8 |
| 168c:0032 | 11ad:6617 | Qualcom... | AR9485 Wireless Network A... | 2     | ath9k      | B972470309 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1502 | 1028:0543 | Intel      | 82579LM Gigabit Network C... | 9     | e1000e     | 0E4A62B59F |
| 8086:10ef | 17aa:306a | Intel      | 82578DM Gigabit Network C... | 7     | e1000e     | 0EF323D23D |
| 8086:10fe | 17aa:3610 | Intel      | 82552 10/100 Network Conn... | 4     | e100       | 5DFF29AF66 |
| 8086:10ce | 104d:9060 | Intel      | 82567V-2 Gigabit Network ... | 3     | e1000e     | 05CFF66AC2 |
| 8086:10f0 | 1025:8000 | Intel      | 82578DC Gigabit Network C... | 3     | e1000e     | 96C29C6C68 |
| 8086:1503 | 1025:8000 | Intel      | 82579V Gigabit Network Co... | 3     | e1000e     | D8225AFA7A |
| 8086:10ce | 1025:048f | Intel      | 82567V-2 Gigabit Network ... | 2     | e1000e     | 24D42A520E |
| 8086:10ce | 104d:9044 | Intel      | 82567V-2 Gigabit Network ... | 2     | e1000e     | EB74857893 |
| 8086:10de | 103c:1489 | Intel      | 82567LM-3 Gigabit Network... | 2     | e1000e     | 603E26F80F |
| 8086:1502 | 103c:3395 | Intel      | 82579LM Gigabit Network C... | 2     | e1000e     | 02F1FBC843 |
| 8086:1539 | 1043:85f0 | Intel      | I211 Gigabit Network Conn... | 2     | igb        | 577AD83B8F |
| 8086:10ce | 104d:9043 | Intel      | 82567V-2 Gigabit Network ... | 1     | e1000e     | CFDCAC5734 |
| 8086:10eb | 17aa:3608 | Intel      | 82577LC Gigabit Network C... | 1     | e1000e     | 69574214D7 |
| 8086:1502 | 8086:0000 | Intel      | 82579LM Gigabit Network C... | 1     | e1000e     | 81CF385125 |
| 8086:1503 | 1043:849c | Intel      | 82579V Gigabit Network Co... | 1     | e1000e     | 259158AB96 |
| 8086:1539 | 1458:e000 | Intel      | I211 Gigabit Network Conn... | 1     | igb        | 42B182D5F0 |
| 8086:1539 | 1849:1539 | Intel      | I211 Gigabit Network Conn... | 1     | igb        | 991A74F3E5 |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1485 | 1022:1485 | AMD        | Starship/Matisse Reserved... | 3     |            | 991A74F3E5 |
| 1022:1455 | 1022:1455 | AMD        | Zeppelin/Renoir PCIe Dumm... | 2     |            | 42B182D5F0 |
| 1022:145a | 1022:145a | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 42B182D5F0 |
| 1022:148a | 1022:148a | AMD        | Starship/Matisse PCIe Dum... | 2     |            | 991A74F3E5 |
| 1022:1485 | 1043:87c0 | AMD        | Starship/Matisse Reserved... | 1     |            | 577AD83B8F |
| 1022:148a | 1043:87c0 | AMD        | Starship/Matisse PCIe Dum... | 1     |            | 577AD83B8F |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 106b:1801 | 106b:1801 | Apple      | T2 Bridge Controller         | 3     |            | 0E4DAA1DE2 |
| 106b:1802 | 106b:1802 | Apple      | T2 Secure Enclave Processor  | 3     |            | 0E4DAA1DE2 |

### Performance counters (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27a3 |           | Intel      | 945GM/GU Chipset Hardware... | 17    |            | 394EF62F20 |
| 8086:2015 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 2     |            | 43CB3AF3A5 |
| 8086:204c | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 2     |            | 43CB3AF3A5 |
| 8086:204d | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 2     | skx_uncore | 43CB3AF3A5 |
| 8086:0e30 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 259158AB96 |
| 8086:0e34 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 259158AB96 |
| 8086:0e36 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 259158AB96 |
| 8086:2f30 | 8086:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     | hswep_u... | B2AD449201 |
| 8086:2f32 | 8086:2f32 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     | hswep_u... | B2AD449201 |
| 8086:2f33 | 8086:2f33 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     | hswep_u... | B2AD449201 |
| 8086:2f34 | 8086:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     | hswep_u... | B2AD449201 |
| 8086:2f36 | 8086:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     | hswep_u... | B2AD449201 |
| 8086:2f37 | 8086:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     | hswep_u... | B2AD449201 |
| 8086:2f38 | 8086:2f38 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     | hswep_u... | B2AD449201 |
| 8086:2f7d | 8086:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | B2AD449201 |

### Pic (io(x)-apic) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2026 | 8086:2026 | Intel      | Sky Lake-E IOAPIC            | 2     |            | 43CB3AF3A5 |
| 8086:2036 | 8086:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 2     |            | 43CB3AF3A5 |
| 8086:0e2c | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 259158AB96 |
| 8086:2f2c | 8086:0000 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | B2AD449201 |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:16bc | 14e4:0000 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 84    | sdhci_pci  | EB3D04E089 |
| 14e4:16bc | 14e4:96bc | Broadco... | BCM57765/57785 SDXC/MMC C... | 18    | sdhci_pci  | 20FB29A6AE |
| 197b:2381 | 1025:0266 | JMicron... | Standard SD Host Controller  | 9     | sdhci_pci  | B24FDB7446 |
| 1217:8621 | 1217:0002 | O2 Micro   | SD/MMC Card Reader Contro... | 8     | sdhci_pci  | 6E2C90AC7B |
| 14e4:16bc | 106b:0000 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 7     | sdhci_pci  | 674668F4DD |
| 10ec:5209 | 10ec:5209 | Realtek... | RTS5209 PCI Express Card ... | 6     | rtsx_pci   | 40E267DF98 |
| 8086:a375 | 103c:84ee | Intel      | 300 Series Chipset Family... | 6     | sdhci_pci  | DF07E6AAB4 |
| 1180:e823 | 104d:907e | Ricoh      | PCIe SDXC/MMC Host Contro... | 5     | sdhci_pci  | 626BFE0484 |
| 8086:5aca | 17aa:36c4 | Intel      | Celeron N3350/Pentium N42... | 5     | sdhci_pci  | 4B68C7AEE7 |
| 1022:7813 | 103c:2b3b | AMD        | FCH SD Flash Controller      | 4     | sdhci_pci  | 1A5D2C36EC |
| 1180:e822 | 104d:9083 | Ricoh      | MMC/SD Host Controller       | 4     | sdhci_pci  | B6A48C3652 |
| 197b:2381 | 17aa:3602 | JMicron... | Standard SD Host Controller  | 4     | sdhci_pci  | C25FDFE643 |
| 8086:31cc | 1043:1ea0 | Intel      | Celeron/Pentium Silver Pr... | 4     | sdhci_pci  | 3B910E6A74 |
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 4     | sdhci_pci  | 32E5618CFE |
| 8086:31d0 | 8086:7270 | Intel      | SD Host Controller           | 4     | sdhci_pci  | 32E5618CFE |
| 1022:7806 | 17aa:3670 | AMD        | FCH SD Flash Controller      | 3     | sdhci_pci  | 225E0C36DC |
| 1022:7813 | 1028:06d1 | AMD        | FCH SD Flash Controller      | 3     | sdhci_pci  | 05A046D623 |
| 10ec:5209 | 1b0a:0188 | Realtek... | RTS5209 PCI Express Card ... | 3     | sdhci_pci  | 0C24A93146 |
| 1180:e822 | 104d:9060 | Ricoh      | MMC/SD Host Controller       | 3     | sdhci_pci  | 05CFF66AC2 |
| 1180:e822 | 104d:907e | Ricoh      | MMC/SD Host Controller       | 3     | sdhci_pci  | BD3B2324DB |
| 1180:e822 | 104d:9097 | Ricoh      | MMC/SD Host Controller       | 3     | sdhci_pci  | 4657C4112A |
| 1180:e823 | 104d:9083 | Ricoh      | PCIe SDXC/MMC Host Contro... | 3     | sdhci_pci  | EEB433BF77 |
| 1217:8520 | 1028:0626 | O2 Micro   | SD/MMC Card Reader Contro... | 3     | sdhci_pci  | F61158882E |
| 197b:2381 | 1025:0275 | JMicron... | Standard SD Host Controller  | 3     | sdhci_pci  | 49DF2710DC |
| 8086:5acc | 1854:0267 | Intel      | Celeron N3350/Pentium N42... | 3     | sdhci_pci  | 41FA541CA4 |
| 1022:7806 | 1462:aa5e | AMD        | FCH SD Flash Controller      | 2     | sdhci_pci  | A70A78E0D0 |
| 1022:7813 | 1028:0628 | AMD        | FCH SD Flash Controller      | 2     | sdhci_pci  | BB462BF2F6 |
| 1022:7906 | 17aa:36bd | AMD        | FCH SD Flash Controller      | 2     | sdhci_pci  | CE295294E2 |
| 1022:7906 | 17aa:36be | AMD        | FCH SD Flash Controller      | 2     | sdhci_pci  | 4863245A0E |
| 1022:7906 | 17aa:36ec | AMD        | FCH SD Flash Controller      | 2     | sdhci_pci  | 2CFA2D338E |
| 1180:0822 | 104d:9044 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 2     | sdhci_pci  | EB74857893 |
| 1180:e822 | 104d:9074 | Ricoh      | MMC/SD Host Controller       | 2     | sdhci_pci  | 68937CF6BB |
| 1180:e822 | 104d:908e | Ricoh      | MMC/SD Host Controller       | 2     | sdhci_pci  | FE0F4C11DF |
| 1180:e823 | 104d:908e | Ricoh      | PCIe SDXC/MMC Host Contro... | 2     | sdhci_pci  | 59BB8EC907 |
| 1180:e823 | 104d:9097 | Ricoh      | PCIe SDXC/MMC Host Contro... | 2     | sdhci_pci  | B2B912EF1E |
| 1217:8321 | 1bcf:a013 | O2 Micro   | OZ600RJ0/OZ900RJ0/OZ600RJ... | 2     | sdhci_pci  | 1494683BB9 |
| 197b:2381 | 1025:0608 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | BEDE9EC674 |
| 197b:2381 | 103c:1489 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | 603E26F80F |
| 197b:2381 | 1043:842d | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | F1E1BF19CC |
| 197b:2391 | 1043:84c1 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | DB3BBECDD0 |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | sdhci_pci  | 7FEFB7E572 |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | sdhci_pci  | 7FEFB7E572 |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | sdhci_pci  | 7FEFB7E572 |
| 1022:7813 | 1028:074a | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | D07D321CCE |
| 1022:7813 | 103c:2b56 | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | 3DB64C4252 |
| 1022:7906 | 1028:0855 | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | DACA9432F8 |
| 1022:7906 | 17aa:36c6 | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | 5DA9F63B49 |
| 1022:7906 | 17aa:36da | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | DE2A851C8F |
| 1106:401b | 17aa:3608 | VIA Tec... | VIA Secure Digital host c... | 1     | sdhci_pci  | 69574214D7 |
| 1180:0822 | 1033:886f | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 86771347FB |
| 1180:0822 | 104d:9043 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | CFDCAC5734 |
| 1217:8120 | 17aa:3068 | O2 Micro   | Integrated MMC/SD Controller | 1     | sdhci_pci  | 27E7D42D53 |
| 1217:8520 | 1028:0625 | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 48D68A1579 |
| 197b:2381 | 1025:039d | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | A629A81791 |
| 197b:2381 | 1043:842e | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | E0910009B1 |
| 197b:2381 | 1043:84af | JMicron... | Standard SD Host Controller  | 1     |            | DF82BB0E17 |
| 197b:2381 | 1043:84c1 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | 0554804F5F |
| 197b:2386 | 197b:2386 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | D0F0DA0187 |
| 197b:2391 | 103c:3561 | JMicron... | Standard SD Host Controller  | 1     |            | 90E0F93E8D |
| 8086:2296 | 1462:a623 | Intel      | Atom/Celeron/Pentium Proc... | 1     | sdhci_pci  | B633258FB4 |
| 8086:31cc | 1043:1632 | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | 73BF014D38 |
| 8086:31cc | 1043:1e80 | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | 5F116B16F1 |
| 8086:31cc | 1854:0308 | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | 530346DA62 |
| 8086:9d2b | 1297:2077 | Intel      | Skylake-U/Y SCC: eMMC        | 1     | sdhci_pci  | 2DCDB3995E |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a324 | 8086:7270 | Intel      | Cannon Lake PCH SPI Contr... | 19    |            | EB3D04E089 |
| 8086:a324 | 103c:84ee | Intel      | Cannon Lake PCH SPI Contr... | 6     |            | DF07E6AAB4 |
| 8086:9da4 | 8086:7270 | Intel      | Cannon Point-LP SPI Contr... | 4     |            | 72FCC11E52 |
| 8086:9dc5 | 1043:17b1 | Intel      | Cannon Point-LP Serial IO... | 4     | intel_lpss | 72FCC11E52 |
| 8086:9de8 | 1043:17b1 | Intel      | Cannon Point-LP Serial IO... | 4     | intel_lpss | 72FCC11E52 |
| 8086:9de9 | 1043:17b1 | Intel      | Cannon Point-LP Serial IO... | 4     | intel_lpss | 72FCC11E52 |
| 8086:a324 | 103c:8446 | Intel      | Cannon Lake PCH SPI Contr... | 4     | intel_spi  | 651C327218 |
| 8086:34a4 | 1025:1418 | Intel      | Ice Lake-LP SPI Controller   | 3     |            | 5820A2D4C3 |
| 8086:02a4 | 1028:0954 | Intel      | Comet Lake SPI (flash) Co... | 2     |            | 51D212B73F |
| 8086:06a4 | 1028:0984 | Intel      | Comet Lake PCH SPI Contro... | 2     |            | 3A565370DE |
| 8086:9da4 | 17aa:36fe | Intel      | Cannon Point-LP SPI Contr... | 2     |            | CA86244C1D |
| 8086:a324 | 1025:1290 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | A27363041A |
| 8086:a324 | 1028:084b | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 301B4DE8EA |
| 8086:a324 | 103c:85a2 | Intel      | Cannon Lake PCH SPI Contr... | 2     | intel_s... | 930847F29A |
| 8086:a324 | 17aa:313d | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 50AAA5CF43 |
| 8086:a324 | 17aa:36f4 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 773BE13AA2 |
| 8086:a324 | 17aa:3701 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 3AAB28E1E4 |
| 8086:a368 | 1025:1290 | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_lpss | A27363041A |
| 8086:a368 | 1043:1241 | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | 608D0CE708 |
| 8086:a369 | 1043:1241 | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | 608D0CE708 |
| 10de:1adb | 10de:13ad | Nvidia     | TU106 USB Type-C UCSI Con... | 1     | i2c_nvi... | E0192EBFC1 |
| 8086:02a4 | 1028:0953 | Intel      | Comet Lake SPI (flash) Co... | 1     |            | D77787D6EC |
| 8086:02a4 | 17aa:3185 | Intel      | Comet Lake SPI (flash) Co... | 1     |            | 324F862858 |
| 8086:02a4 | 17aa:370b | Intel      | Comet Lake SPI (flash) Co... | 1     |            | F179844FE4 |
| 8086:02a4 | 17aa:370c | Intel      | Comet Lake SPI (flash) Co... | 1     |            | E678313D40 |
| 8086:02a4 | 8086:7270 | Intel      | Comet Lake SPI (flash) Co... | 1     |            | 19963E0F47 |
| 8086:02c5 | 1043:1f51 | Intel      | Comet Lake Serial IO I2C ... | 1     | intel_lpss | 19963E0F47 |
| 8086:02e8 | 1043:1f51 | Intel      | Serial IO I2C Host Contro... | 1     | intel_lpss | 19963E0F47 |
| 8086:02e9 | 1043:1f51 | Intel      | Comet Lake Serial IO I2C ... | 1     | intel_lpss | 19963E0F47 |
| 8086:06a4 | 103c:86c7 | Intel      | Comet Lake PCH SPI Contro... | 1     |            | B928A63EF1 |
| 8086:06a4 | 103c:871c | Intel      | Comet Lake PCH SPI Contro... | 1     |            | 2F7FD6200F |
| 8086:06a4 | 8086:7270 | Intel      | Comet Lake PCH SPI Contro... | 1     |            | 0E4DAA1DE2 |
| 8086:34a4 | 1025:1434 | Intel      | Ice Lake-LP SPI Controller   | 1     |            | D8FFD8A934 |
| 8086:34a4 | 103c:87a4 | Intel      | Ice Lake-LP SPI Controller   | 1     | intel_s... | 49834DA4FA |
| 8086:a0a4 | 1043:1482 | Intel      | Tiger Lake-LP SPI Controller | 1     |            | 8D0477EA03 |
| 8086:a324 | 1025:126c | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | C1339E884A |
| 8086:a324 | 1025:1291 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 866F2F8C49 |
| 8086:a324 | 1028:0851 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 05D6B79D2F |
| 8086:a324 | 1028:0934 | Intel      | Cannon Lake PCH SPI Contr... | 1     | intel_s... | 9440CC0137 |
| 8086:a324 | 1028:0935 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 46AD418D75 |
| 8086:a324 | 103c:83eb | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | C73E03D65D |
| 8086:a324 | 103c:8448 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 9C6AD0A8DB |
| 8086:a324 | 103c:86c6 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 0ADE825910 |
| 8086:a324 | 17aa:3123 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 943F3319E9 |
| 8086:a324 | 17aa:313b | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 56D6E59000 |
| 8086:a324 | 17aa:36f2 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | F172B5B1EA |
| 8086:a32a | 1043:1e40 | Intel      | 300 Series Chipset Family    | 1     | intel_l... | 4313964FA7 |
| 8086:a368 | 1025:1291 | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_lpss | 866F2F8C49 |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e3d | 1028:0543 | Intel      | 7 Series/C210 Series Chip... | 10    | serial     | 0E4A62B59F |
| 8086:8c3d | 1028:05a7 | Intel      | 8 Series/C220 Series Chip... | 6     | serial     | 16927C4FC4 |
| 8086:8c3d | 103c:18e6 | Intel      | 8 Series/C220 Series Chip... | 5     | serial     | CF3ED91B8A |
| 8086:a13d | 17aa:30ba | Intel      | 100 Series/C230 Series Ch... | 3     | serial     | F3E9E0B2F5 |
| 10ec:816a | 1025:1290 | Realtek... | RTL8111xP UART #1            | 2     |            | A27363041A |
| 10ec:816b | 1025:1290 | Realtek... | RTL8111xP UART #2            | 2     |            | A27363041A |
| 8086:1c3d | 103c:3395 | Intel      | 6 Series/C200 Series Chip... | 2     | serial     | 02F1FBC843 |
| 8086:2e17 | 103c:1489 | Intel      | 4 Series Chipset Serial K... | 2     | serial     | 603E26F80F |
| 8086:a13d | 1028:075d | Intel      | 100 Series/C230 Series Ch... | 2     | serial     | 404A8B3A68 |
| 8086:a13d | 103c:8058 | Intel      | 100 Series/C230 Series Ch... | 2     | serial     | 09B55E64F6 |
| 8086:a2bd | 103c:829b | Intel      | 200 Series Chipset Family... | 2     | serial     | 44675B1F55 |
| 8086:a363 | 103c:85a2 | Intel      | Cannon Lake PCH Active Ma... | 2     | serial     | 930847F29A |
| 10ec:816a | 1025:1291 | Realtek... | RTL8111xP UART #1            | 1     |            | 866F2F8C49 |
| 10ec:816b | 1025:1291 | Realtek... | RTL8111xP UART #2            | 1     |            | 866F2F8C49 |
| 13a8:0354 |           | Exar       | Exar's 4-Port UART PCIe Card | 1     | 8250_exar  | B5FBC6A19B |
| 8086:06e3 | 103c:871c | Intel      | Comet Lake Keyboard and T... | 1     | serial     | 2F7FD6200F |
| 8086:1c3d | 103c:3561 | Intel      | 6 Series/C200 Series Chip... | 1     | serial     | 90E0F93E8D |
| 8086:1e3d | 1854:f004 | Intel      | 7 Series/C210 Series Chip... | 1     | serial     | 81CF385125 |
| 8086:8c3d | 103c:18e8 | Intel      | 8 Series/C220 Series Chip... | 1     | serial     | 182C662F57 |
| 8086:8c3d | 8086:204c | Intel      | 8 Series/C220 Series Chip... | 1     | serial     | 098FE372A3 |
| 8086:8d3d | 8086:7270 | Intel      | C610/X99 series chipset K... | 1     | serial     | B2AD449201 |
| 8086:a13d | 103c:805e | Intel      | 100 Series/C230 Series Ch... | 1     | serial     | FDD0A4E977 |
| 8086:a2bd | 1028:079c | Intel      | 200 Series Chipset Family... | 1     | serial     | 4F4887AB67 |
| 8086:a363 | 103c:83eb | Intel      | Cannon Lake PCH Active Ma... | 1     | serial     | C73E03D65D |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3b32 | 8086:0000 | Intel      | 5 Series/3400 Series Chip... | 44    | intel_ips  | C5621D630D |
| 8086:9d61 | 8086:9d61 | Intel      | Sunrise Point-LP Serial I... | 20    | intel_l... | B5E9340D85 |
| 8086:a379 | 8086:7270 | Intel      | Cannon Lake PCH Thermal C... | 17    | intel_p... | EB3D04E089 |
| 8086:9d60 | 103c:84de | Intel      | Sunrise Point-LP Serial I... | 12    | intel_l... | B5E9340D85 |
| 8086:9d31 | 8086:9d31 | Intel      | Sunrise Point-LP Thermal ... | 10    | intel_p... | 1096F1F298 |
| 8086:318c | 1025:1304 | Intel      | Celeron/Pentium Silver Pr... | 9     | proc_th... | B7F823BFDA |
| 8086:3a32 | 1025:0266 | Intel      | 82801JI (ICH10 Family) Th... | 9     |            | B24FDB7446 |
| 8086:9d31 | 1025:1287 | Intel      | Sunrise Point-LP Thermal ... | 9     | intel_p... | EB23862DED |
| 8086:22dc |           | Intel      | Atom/Celeron/Pentium Proc... | 8     | process... | 3AC5DA5F93 |
| 8086:9d60 | 8086:9d60 | Intel      | Sunrise Point-LP Serial I... | 8     | intel_l... | 2FDFFAE0E5 |
| 8086:1903 | 8086:1903 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 7     | proc_th... | 2FDFFAE0E5 |
| 8086:318c | 1854:0308 | Intel      | Celeron/Pentium Silver Pr... | 6     | process... | 125F68D06E |
| 8086:a379 | 103c:84ee | Intel      | Cannon Lake PCH Thermal C... | 6     | intel_p... | DF07E6AAB4 |
| 8086:5a8c | 17aa:36c4 | Intel      | Atom/Celeron/Pentium Dyna... | 5     | process... | 4B68C7AEE7 |
| 8086:9d31 | 1028:0754 | Intel      | Sunrise Point-LP Thermal ... | 5     | intel_p... | 83612FBDEE |
| 8086:9d60 | 1028:0754 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 83612FBDEE |
| 8086:9d61 | 1028:0754 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 83612FBDEE |
| 8086:a131 | 8086:a131 | Intel      | 100 Series/C230 Series Ch... | 5     | intel_p... | 31E48D8DA1 |
| 8086:1903 | 1043:17b1 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 4     | proc_th... | 72FCC11E52 |
| 8086:318c | 103c:86f0 | Intel      | Celeron/Pentium Silver Pr... | 4     | process... | 9FDCC0F2AF |
| 8086:318c | 1043:1e80 | Intel      | Celeron/Pentium Silver Pr... | 4     | proc_th... | BA03906EB8 |
| 8086:318c | 1043:1ea0 | Intel      | Celeron/Pentium Silver Pr... | 4     | proc_th... | 3B910E6A74 |
| 8086:31b4 | 1043:1e80 | Intel      | Celeron/Pentium Silver Pr... | 4     | intel_lpss | BA03906EB8 |
| 8086:31b4 | 1043:1ea0 | Intel      | Celeron/Pentium Silver Pr... | 4     | intel_lpss | 3B910E6A74 |
| 8086:31b6 | 1043:1e80 | Intel      | Celeron/Pentium Silver Pr... | 4     | intel_lpss | BA03906EB8 |
| 8086:31b6 | 1043:1ea0 | Intel      | Celeron/Pentium Silver Pr... | 4     | intel_lpss | 3B910E6A74 |
| 8086:31c2 | 1043:1e80 | Intel      | Celeron/Pentium Silver Pr... | 4     | intel_lpss | BA03906EB8 |
| 8086:31c2 | 1043:1ea0 | Intel      | Celeron/Pentium Silver Pr... | 4     | intel_lpss | 3B910E6A74 |
| 8086:8ca4 | 8086:7270 | Intel      | 9 Series Chipset Family T... | 4     |            | 74E99D5666 |
| 8086:9df9 | 1043:17b1 | Intel      | Cannon Point-LP Thermal C... | 4     | intel_p... | 72FCC11E52 |
| 8086:a379 | 103c:8446 | Intel      | Cannon Lake PCH Thermal C... | 4     | intel_p... | 651C327218 |
| 8086:1903 | 1043:12a1 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | proc_th... | E0EF808E3F |
| 8086:5a8c |           | Intel      | Atom/Celeron/Pentium Dyna... | 3     | process... | 7FEFB7E572 |
| 8086:9d31 | 1028:0852 | Intel      | Sunrise Point-LP Thermal ... | 3     | intel_p... | 5A27DEAF8A |
| 8086:9d31 | 1043:12a1 | Intel      | Sunrise Point-LP Thermal ... | 3     | intel_p... | E0EF808E3F |
| 8086:9d60 | 1028:0852 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 5A27DEAF8A |
| 8086:9d60 | 1043:12a1 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_lpss | E0EF808E3F |
| 8086:9d61 | 1028:0852 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 5A27DEAF8A |
| 8086:9d61 | 1043:12a1 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_lpss | E0EF808E3F |
| 8086:a127 | 17aa:30ba | Intel      | 100 Series/C230 Series Ch... | 3     | intel_l... | F3E9E0B2F5 |
| 8086:a131 | 17aa:30ba | Intel      | 100 Series/C230 Series Ch... | 3     | intel_p... | F3E9E0B2F5 |
| 8086:a3b1 | 8086:7270 | Intel      | Comet Lake PCH-V Thermal ... | 3     |            | E8A54D0908 |
| 8086:02f9 | 1028:0954 | Intel      | Comet Lake Thermal Subsytem  | 2     |            | 51D212B73F |
| 8086:06f9 | 1028:0984 | Intel      | Comet Lake PCH Thermal Co... | 2     | intel_p... | 3A565370DE |
| 8086:1603 | 8086:2010 | Intel      | Broadwell-U Processor The... | 2     | process... | 008B8709C8 |
| 8086:1903 | 1043:1241 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | process... | 608D0CE708 |
| 8086:1e24 | 1462:b062 | Intel      | 7 Series/C210 Series Chip... | 2     |            | 0FC1178D7D |
| 8086:3b32 | 1b7d:0050 | Intel      | 5 Series/3400 Series Chip... | 2     | intel_ips  | 446E846D8A |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 7FEFB7E572 |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 7FEFB7E572 |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 7FEFB7E572 |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 7FEFB7E572 |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 7FEFB7E572 |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 7FEFB7E572 |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 7FEFB7E572 |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 7FEFB7E572 |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 7FEFB7E572 |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 7FEFB7E572 |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 7FEFB7E572 |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 7FEFB7E572 |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 7FEFB7E572 |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 7FEFB7E572 |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 7FEFB7E572 |
| 8086:9c24 | 17aa:36a4 | Intel      | 8 Series Thermal             | 2     | intel_p... | 511D087D03 |
| 8086:9ca4 | 8086:7270 | Intel      | Wildcat Point-LP Thermal ... | 2     | intel_p... | 906BCD4AC8 |
| 8086:9d31 | 17aa:3630 | Intel      | Sunrise Point-LP Thermal ... | 2     | intel_p... | F96B4E9ECA |
| 8086:9d31 | 17aa:36dc | Intel      | Sunrise Point-LP Thermal ... | 2     | intel_p... | CD5915910D |
| 8086:9df9 | 17aa:36fe | Intel      | Cannon Point-LP Thermal C... | 2     | intel_p... | CA86244C1D |
| 8086:a131 | 1025:1063 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_p... | 2B787D7F5F |
| 8086:a131 | 1028:06c5 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_p... | 0E09B99FC0 |
| 8086:a131 | 1028:06d4 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 275E0EEAEF |
| 8086:a131 | 103c:8058 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_p... | 09B55E64F6 |
| 8086:a131 | 17aa:30fc | Intel      | 100 Series/C230 Series Ch... | 2     | intel_p... | 4740E3EA20 |
| 8086:a131 | 17aa:3636 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_p... | 3F2A054B58 |
| 8086:a131 | 17aa:36bc | Intel      | 100 Series/C230 Series Ch... | 2     | intel_p... | F9C1063722 |
| 8086:a2a7 | 8086:7270 | Intel      | 200 Series/Z370 Chipset F... | 2     | intel_l... | 43CB3AF3A5 |
| 8086:a2a8 | 8086:7270 | Intel      | 200 Series/Z370 Chipset F... | 2     | intel_l... | 43CB3AF3A5 |
| 8086:a2b1 | 103c:829b | Intel      | 200 Series PCH Thermal Su... | 2     |            | 44675B1F55 |
| 8086:a2b1 | 17aa:3718 | Intel      | 200 Series PCH Thermal Su... | 2     |            | 78AB4FCC2D |
| 8086:a379 | 1025:1290 | Intel      | Cannon Lake PCH Thermal C... | 2     | intel_p... | A27363041A |
| 8086:a379 | 1028:084b | Intel      | Cannon Lake PCH Thermal C... | 2     | intel_p... | 301B4DE8EA |
| 8086:a379 | 103c:85a2 | Intel      | Cannon Lake PCH Thermal C... | 2     | intel_p... | 930847F29A |
| 8086:a379 | 1043:1241 | Intel      | Cannon Lake PCH Thermal C... | 2     | intel_p... | 608D0CE708 |
| 8086:a379 | 17aa:313d | Intel      | Cannon Lake PCH Thermal C... | 2     | intel_p... | 50AAA5CF43 |
| 8086:a379 | 17aa:36f4 | Intel      | Cannon Lake PCH Thermal C... | 2     | intel_p... | 773BE13AA2 |
| 8086:a379 | 17aa:3701 | Intel      | Cannon Lake PCH Thermal C... | 2     | intel_p... | 3AAB28E1E4 |
| 8086:02f9 | 1028:0953 | Intel      | Comet Lake Thermal Subsytem  | 1     | intel_p... | D77787D6EC |
| 8086:02f9 | 1043:1f51 | Intel      | Comet Lake Thermal Subsytem  | 1     |            | 19963E0F47 |
| 8086:02f9 | 17aa:3185 | Intel      | Comet Lake Thermal Subsytem  | 1     |            | 324F862858 |
| 8086:02f9 | 17aa:370b | Intel      | Comet Lake Thermal Subsytem  | 1     |            | F179844FE4 |
| 8086:02f9 | 17aa:370c | Intel      | Comet Lake Thermal Subsytem  | 1     |            | E678313D40 |
| 8086:06f9 | 103c:86c7 | Intel      | Comet Lake PCH Thermal Co... | 1     | intel_p... | B928A63EF1 |
| 8086:06f9 | 103c:871c | Intel      | Comet Lake PCH Thermal Co... | 1     |            | 2F7FD6200F |
| 8086:06f9 | 8086:7270 | Intel      | Comet Lake PCH Thermal Co... | 1     | intel_p... | 0E4DAA1DE2 |
| 8086:1903 | 103c:86c7 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | process... | B928A63EF1 |
| 8086:1903 | 103c:86f7 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | process... | 82E222B1FA |
| 8086:1903 | 1043:1f51 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | proc_th... | 19963E0F47 |
| 8086:1903 | 17aa:3184 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | process... | BD5551C49A |
| 8086:1c24 | 17aa:362a | Intel      | 6 Series/C200 Series Chip... | 1     |            | DCE4B1A82B |
| 8086:22dc | 1854:0236 | Intel      | Atom/Celeron/Pentium Proc... | 1     | process... | C3FA4BE680 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:283e | 106b:00a0 | Intel      | 82801H (ICH8 Family) SMBu... | 77    | i2c_i801   | 00CC913F3D |
| 8086:1c22 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 63    | i2c_i801   | 2216DC8384 |
| 10de:0aa2 | 10de:cb79 | Nvidia     | MCP79 SMBus                  | 46    | i2c_nfo... | 8AB1BA226D |
| 8086:3b30 | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 44    | i2c_i801   | C5621D630D |
| 8086:8c22 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 33    | i2c_i801   | 20FB29A6AE |
| 8086:a123 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 28    | i2c_i801   | E53C63BA89 |
| 8086:1e22 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 20    | i2c_i801   | DAE7632445 |
| 8086:27da | 8086:7270 | Intel      | NM10/ICH7 Family SMBus Co... | 17    | i2c_i801   | 394EF62F20 |
| 8086:a323 | 8086:7270 | Intel      | Cannon Lake PCH SMBus Con... | 17    | i2c_i801   | EB3D04E089 |
| 8086:1c22 | 17aa:365e | Intel      | 6 Series/C200 Series Chip... | 12    | i2c_i801   | 9164B5B105 |
| 8086:9d23 | 103c:84de | Intel      | Sunrise Point-LP SMBus       | 12    | i2c_i801   | B5E9340D85 |
| 1022:780b | 103c:8245 | AMD        | FCH SMBus Controller         | 11    | i2c_piix4  | 40434F824A |
| 8086:1c22 | 103c:2ac5 | Intel      | 6 Series/C200 Series Chip... | 11    | i2c_i801   | 55450C73C0 |
| 8086:1e22 | 1028:0543 | Intel      | 7 Series/C216 Chipset Fam... | 10    | i2c_i801   | 0E4A62B59F |
| 8086:9d23 | 8086:9d23 | Intel      | Sunrise Point-LP SMBus       | 10    | i2c_i801   | 1096F1F298 |
| 8086:1e22 | 1028:0548 | Intel      | 7 Series/C216 Chipset Fam... | 9     | i2c_i801   | 8184B0981F |
| 8086:31d4 | 1025:1304 | Intel      | Celeron/Pentium Silver Pr... | 9     |            | B7F823BFDA |
| 8086:3a30 | 1025:0266 | Intel      | 82801JI (ICH10 Family) SM... | 9     | i2c_i801   | B24FDB7446 |
| 8086:9d23 | 1025:1287 | Intel      | Sunrise Point-LP SMBus       | 9     | i2c_i801   | EB23862DED |
| 1022:790b | 103c:8381 | AMD        | FCH SMBus Controller         | 8     | i2c_pii... | B4A3EC103B |
| 8086:3b30 | 17aa:306a | Intel      | 5 Series/3400 Series Chip... | 8     | i2c_i801   | 0EF323D23D |
| 8086:8c22 | 1028:05db | Intel      | 8 Series/C220 Series Chip... | 8     | i2c_i801   | 80CA4B15A5 |
| 1002:4385 |           | AMD        | SBx00 SMBus Controller       | 7     | i2c_piix4  | F7EF0F2C13 |
| 10de:0752 | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] SMBus  | 7     | i2c_nfo... | 04B8123AA5 |
| 8086:1c22 | 1028:0511 | Intel      | 6 Series/C200 Series Chip... | 7     | i2c_i801   | 5C781B927F |
| 8086:1c22 | 104d:907e | Intel      | 6 Series/C200 Series Chip... | 7     | i2c_i801   | 626BFE0484 |
| 8086:1c22 | 17aa:366c | Intel      | 6 Series/C200 Series Chip... | 7     | i2c_i801   | 3903A96DE3 |
| 8086:2292 | 103c:81bb | Intel      | Atom/Celeron/Pentium Proc... | 7     | i801_smbus | CA80EA46C5 |
| 8086:8c22 | 1028:05a7 | Intel      | 8 Series/C220 Series Chip... | 7     | i2c_i801   | 16927C4FC4 |
| 1022:780b | 103c:2b3b | AMD        | FCH SMBus Controller         | 6     | i2c_piix4  | 1A5D2C36EC |
| 1022:790b | 103c:8430 | AMD        | FCH SMBus Controller         | 6     | i2c_pii... | 5C5ADCC248 |
| 8086:1e22 | 144d:b091 | Intel      | 7 Series/C216 Chipset Fam... | 6     | i2c_i801   | 0F9E022C5E |
| 8086:2292 | 1028:06cc | Intel      | Atom/Celeron/Pentium Proc... | 6     | i2c_i801   | 3AC5DA5F93 |
| 8086:31d4 | 1854:0308 | Intel      | Celeron/Pentium Silver Pr... | 6     | i2c_i801   | 125F68D06E |
| 8086:8c22 | 103c:18e6 | Intel      | 8 Series/C220 Series Chip... | 6     | i2c_i801   | CF3ED91B8A |
| 8086:a323 | 103c:84ee | Intel      | Cannon Lake PCH SMBus Con... | 6     | i801_smbus | DF07E6AAB4 |
| 8086:0f12 | 17aa:3695 | Intel      | Atom Processor E3800 Seri... | 5     | i2c_i801   | CB2927D290 |
| 8086:1c22 | 104d:9083 | Intel      | 6 Series/C200 Series Chip... | 5     | i2c_i801   | EEB433BF77 |
| 8086:1e22 | 104d:9097 | Intel      | 7 Series/C216 Chipset Fam... | 5     | i2c_i801   | B2B912EF1E |
| 8086:1e22 | 17aa:3671 | Intel      | 7 Series/C216 Chipset Fam... | 5     | i2c_i801   | 2A92010AD3 |
| 8086:5ad4 | 17aa:36c4 | Intel      | Celeron N3350/Pentium N42... | 5     | i2c_i801   | 4B68C7AEE7 |
| 8086:8c22 | 17aa:367b | Intel      | 8 Series/C220 Series Chip... | 5     | i2c_i801   | A459000D17 |
| 8086:9d23 | 1028:0754 | Intel      | Sunrise Point-LP SMBus       | 5     | i2c_i801   | 83612FBDEE |
| 8086:a123 | 103c:82dc | Intel      | 100 Series/C230 Series Ch... | 5     | i2c_i801   | 036481482E |
| 8086:a123 | 8086:a123 | Intel      | 100 Series/C230 Series Ch... | 5     | i2c_i801   | 31E48D8DA1 |
| 8086:0f12 |           | Intel      | Atom Processor E3800 Seri... | 4     | i2c_i801   | B3E778A640 |
| 8086:1c22 | 1019:7c94 | Intel      | 6 Series/C200 Series Chip... | 4     | i2c_i801   | 4FF205BED4 |
| 8086:1c22 | 1025:0618 | Intel      | 6 Series/C200 Series Chip... | 4     | i2c_i801   | 0362E43257 |
| 8086:27da | 17aa:3602 | Intel      | NM10/ICH7 Family SMBus Co... | 4     | i2c_i801   | C25FDFE643 |
| 8086:27da | 17aa:3610 | Intel      | NM10/ICH7 Family SMBus Co... | 4     | i2c_i801   | 5DFF29AF66 |
| 8086:31d4 | 103c:86f0 | Intel      | Celeron/Pentium Silver Pr... | 4     | i2c_i801   | 9FDCC0F2AF |
| 8086:31d4 | 1043:1e80 | Intel      | Celeron/Pentium Silver Pr... | 4     |            | BA03906EB8 |
| 8086:31d4 | 1043:1ea0 | Intel      | Celeron/Pentium Silver Pr... | 4     |            | 3B910E6A74 |
| 8086:31d4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 4     | i801_smbus | 32E5618CFE |
| 8086:3b30 | 1025:045c | Intel      | 5 Series/3400 Series Chip... | 4     | i2c_i801   | 306081B9C5 |
| 8086:8c22 | 1028:0623 | Intel      | 8 Series/C220 Series Chip... | 4     | i2c_i801   | 3C11289E85 |
| 8086:8c22 | 17aa:3686 | Intel      | 8 Series/C220 Series Chip... | 4     | i2c_i801   | 1E467924BF |
| 8086:8ca2 | 8086:7270 | Intel      | 9 Series Chipset Family S... | 4     | i2c_i801   | 74E99D5666 |
| 8086:9ca2 | 8086:9ca2 | Intel      | Wildcat Point-LP SMBus Co... | 4     | i2c_i801   | 6CF5332D62 |
| 8086:9d23 | 103c:82dd | Intel      | Sunrise Point-LP SMBus       | 4     | i2c_i801   | 0A0BE4F02F |
| 8086:9da3 | 1043:17b1 | Intel      | Cannon Point-LP SMBus Con... | 4     |            | 72FCC11E52 |
| 8086:a123 | 103c:81b7 | Intel      | 100 Series/C230 Series Ch... | 4     | i2c_i801   | AA69312028 |
| 8086:a323 | 103c:8446 | Intel      | Cannon Lake PCH SMBus Con... | 4     | i2c_i801   | 651C327218 |
| 1002:4385 | 1002:4385 | AMD        | SBx00 SMBus Controller       | 3     | i2c_piix4  | DF82BB0E17 |
| 1022:780b | 1025:0642 | AMD        | FCH SMBus Controller         | 3     | i2c_piix4  | AFC950475D |
| 1022:780b | 1025:0720 | AMD        | FCH SMBus Controller         | 3     | i2c_piix4  | B972470309 |
| 1022:780b | 1028:06d1 | AMD        | FCH SMBus Controller         | 3     | i2c_piix4  | 05A046D623 |
| 1022:780b | 103c:2b2f | AMD        | FCH SMBus Controller         | 3     | piix4_s... | 093F49B44C |
| 1022:780b | 17aa:3670 | AMD        | FCH SMBus Controller         | 3     | i2c_piix4  | 225E0C36DC |
| 1022:780b | 17aa:36ab | AMD        | FCH SMBus Controller         | 3     | piix4_s... | 93BC9B0BE9 |
| 1022:790b | 1028:07e3 | AMD        | FCH SMBus Controller         | 3     | i2c_piix4  | ACCB6ADA09 |
| 1022:790b | 103c:86f3 | AMD        | FCH SMBus Controller         | 3     | i2c_piix4  | 4B12BB887A |
| 1022:790b | 17aa:36f5 | AMD        | FCH SMBus Controller         | 3     | i2c_pii... | EB38810FB8 |
| 8086:0f12 | 1025:0994 | Intel      | Atom Processor E3800 Seri... | 3     | i2c_i801   | 6247D83BAB |
| 8086:0f12 | 1297:2041 | Intel      | Atom Processor E3800 Seri... | 3     | i801_smbus | 26A6CD4678 |
| 8086:0f12 | 1854:0200 | Intel      | Atom Processor E3800 Seri... | 3     | i801_smbus | 40E267DF98 |
| 8086:1c22 | 1025:0492 | Intel      | 6 Series/C200 Series Chip... | 3     | i2c_i801   | D8225AFA7A |
| 8086:1c22 | 1025:0608 | Intel      | 6 Series/C200 Series Chip... | 3     | i2c_i801   | D0F0DA0187 |
| 8086:1c22 | 103c:2aed | Intel      | 6 Series/C200 Series Chip... | 3     | i2c_i801   | 00FCD6CB57 |
| 8086:1c22 | 1043:1c22 | Intel      | 6 Series/C200 Series Chip... | 3     | i2c_i801   | 0554804F5F |
| 8086:1c22 | 8086:1c22 | Intel      | 6 Series/C200 Series Chip... | 3     | i2c_i801   | 19478FF625 |
| 8086:1e22 | 1025:0792 | Intel      | 7 Series/C216 Chipset Fam... | 3     | i2c_i801   | 89F713C877 |
| 8086:1e22 | 1043:844d | Intel      | 7 Series/C216 Chipset Fam... | 3     | i2c_i801   | 61B5866007 |
| 8086:1e22 | 1854:0167 | Intel      | 7 Series/C216 Chipset Fam... | 3     |            | D0CF0BEEA8 |
| 8086:2292 | 1025:0992 | Intel      | Atom/Celeron/Pentium Proc... | 3     | i801_smbus | F2703DFC7E |
| 8086:2292 | 1297:2053 | Intel      | Atom/Celeron/Pentium Proc... | 3     | i2c_i801   | FFF1EFB11D |
| 8086:2930 | 1025:0275 | Intel      | 82801I (ICH9 Family) SMBu... | 3     |            | 49DF2710DC |
| 8086:34a3 | 1025:1418 | Intel      | Ice Lake-LP SMBus Controller | 3     | i2c_i801   | 5820A2D4C3 |
| 8086:3a30 | 104d:9060 | Intel      | 82801JI (ICH10 Family) SM... | 3     | i2c_i801   | 05CFF66AC2 |
| 8086:3b30 | 1025:0297 | Intel      | 5 Series/3400 Series Chip... | 3     | i2c_i801   | 96C29C6C68 |
| 8086:3b30 | 1028:0478 | Intel      | 5 Series/3400 Series Chip... | 3     | i2c_i801   | A288705A4D |
| 8086:5ad4 | 1854:0267 | Intel      | Celeron N3350/Pentium N42... | 3     | i2c_i801   | 41FA541CA4 |
| 8086:8c22 | 1028:0626 | Intel      | 8 Series/C220 Series Chip... | 3     | i2c_i801   | F61158882E |
| 8086:8c22 | 17aa:3685 | Intel      | 8 Series/C220 Series Chip... | 3     | i2c_i801   | 647613F22B |
| 8086:8c22 | 1b0a:0188 | Intel      | 8 Series/C220 Series Chip... | 3     | i2c_i801   | 0C24A93146 |
| 8086:9c22 | 8086:7270 | Intel      | 8 Series SMBus Controller    | 3     |            | 2F7B60E4CD |
| 8086:9d23 | 1028:0852 | Intel      | Sunrise Point-LP SMBus       | 3     | i2c_i801   | 5A27DEAF8A |
| 8086:9d23 | 1043:12a1 | Intel      | Sunrise Point-LP SMBus       | 3     |            | E0EF808E3F |
| 8086:9d23 | 8086:7270 | Intel      | Sunrise Point-LP SMBus       | 3     | i2c_i801   | 94DEDAFA8A |
| 8086:a123 | 17aa:30ba | Intel      | 100 Series/C230 Series Ch... | 3     | i2c_i801   | F3E9E0B2F5 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:284b | 106b:00a0 | Intel      | 82801H (ICH8 Family) HD A... | 77    | snd_hda... | 00CC913F3D |
| 8086:1c20 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 63    | snd_hda... | 2216DC8384 |
| 1002:aa90 | 106b:aa90 | AMD        | Turks HDMI Audio [Radeon ... | 47    | snd_hda... | 2216DC8384 |
| 10de:0ac0 | 10de:cb79 | Nvidia     | MCP79 High Definition Audio  | 46    | snd_hda... | 8AB1BA226D |
| 8086:3b56 | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 44    | snd_hda... | C5621D630D |
| 8086:8c20 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 33    | snd_hda... | 20FB29A6AE |
| 8086:a170 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 28    | snd_hda... | E53C63BA89 |
| 8086:1e20 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 20    | snd_hda... | DAE7632445 |
| 1002:aa38 | 106b:aa38 | AMD        | RV710/730 HDMI Audio [Rad... | 18    | snd_hda... | 8AB1BA226D |
| 1002:aae0 | 1002:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 18    | snd_hda... | 632B6526F7 |
| 8086:a348 | 8086:7270 | Intel      | Cannon Lake PCH cAVS         | 17    | snd_hda... | EB3D04E089 |
| 1002:aaf0 | 1002:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 15    | snd_hda... | 74EC4FCD5B |
| 8086:27d8 | 8384:7680 | Intel      | NM10/ICH7 Family High Def... | 15    | snd_hda... | 394EF62F20 |
| 1002:aa88 | 106b:aa88 | AMD        | Barts HDMI Audio [Radeon ... | 14    | snd_hda... | 123A822BE5 |
| 1002:aa30 | 106b:aa30 | AMD        | RV770 HDMI Audio [Radeon ... | 13    | snd_hda... | E01CF9234B |
| 1002:aa58 | 106b:aa58 | AMD        | Juniper HDMI Audio [Radeo... | 13    | snd_hda... | 9AC85E317C |
| 8086:1c20 | 17aa:365e | Intel      | 6 Series/C200 Series Chip... | 12    | snd_hda... | 9164B5B105 |
| 8086:9d71 | 103c:84de | Intel      | Sunrise Point-LP HD Audio    | 12    | snd_hda... | B5E9340D85 |
| 1002:9840 | 103c:8245 | AMD        | Kabini HDMI/DP Audio         | 11    | snd_hda... | 40434F824A |
| 1022:780d | 103c:8245 | AMD        | FCH Azalia Controller        | 11    | snd_hda... | 40434F824A |
| 8086:1c20 | 103c:2ac5 | Intel      | 6 Series/C200 Series Chip... | 11    | snd_hda... | 55450C73C0 |
| 10de:0e0a |           | Nvidia     | GK104 HDMI Audio Controller  | 10    | snd_hda... | CCAB3D35E1 |
| 10de:0e1b | 106b:0109 | Nvidia     | GK107 HDMI Audio Controller  | 10    | snd_hda... | DAE7632445 |
| 8086:0d0c | 106b:0122 | Intel      | Crystal Well HD Audio Con... | 10    | snd_hda... | 0761ED6181 |
| 8086:1e20 | 1028:0543 | Intel      | 7 Series/C216 Chipset Fam... | 10    | snd_hda... | 0E4A62B59F |
| 1002:aab0 | 0000:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 9     | snd_hda... | 8EBAD885B5 |
| 8086:1e20 | 1028:0548 | Intel      | 7 Series/C216 Chipset Fam... | 9     | snd_hda... | 8184B0981F |
| 8086:3198 | 1025:1130 | Intel      | Celeron/Pentium Silver Pr... | 9     | snd_hda... | B7F823BFDA |
| 8086:3a3e | 1025:0266 | Intel      | 82801JI (ICH10 Family) HD... | 9     | snd_hda... | B24FDB7446 |
| 8086:9d71 | 1025:1287 | Intel      | Sunrise Point-LP HD Audio    | 9     | snd_hda... | EB23862DED |
| 1002:15b3 | 103c:8381 | AMD        | High Definition Audio Con... | 8     | snd_hda... | B4A3EC103B |
| 1022:157a | 103c:8381 | AMD        | Family 15h (Models 60h-6f... | 8     | snd_hda... | B4A3EC103B |
| 8086:0c0c | 1028:05db | Intel      | Xeon E3-1200 v3/4th Gen C... | 8     | snd_hda... | 80CA4B15A5 |
| 8086:3b56 | 17aa:306a | Intel      | 5 Series/3400 Series Chip... | 8     | snd_hda... | 0EF323D23D |
| 8086:8c20 | 1028:05db | Intel      | 8 Series/C220 Series Chip... | 8     | snd_hda... | 80CA4B15A5 |
| 10de:0774 | 1025:0461 | Nvidia     | MCP72XE/MCP72P/MCP78U/MCP... | 7     | snd_hda... | 04B8123AA5 |
| 10de:0bea | 17aa:365e | Nvidia     | GF108 High Definition Aud... | 7     | snd_hda... | 9164B5B105 |
| 10de:0e1b |           | Nvidia     | GK107 HDMI Audio Controller  | 7     | snd_hda... | 20FB29A6AE |
| 8086:0c0c | 1028:05a7 | Intel      | Xeon E3-1200 v3/4th Gen C... | 7     | snd_hda... | 16927C4FC4 |
| 8086:0c0c | 8086:2010 | Intel      | Xeon E3-1200 v3/4th Gen C... | 7     | snd_hda... | A027E01C3B |
| 8086:1c20 | 1028:0511 | Intel      | 6 Series/C200 Series Chip... | 7     | snd_hda... | 5C781B927F |
| 8086:1c20 | 104d:907e | Intel      | 6 Series/C200 Series Chip... | 7     | snd_hda... | 626BFE0484 |
| 8086:1c20 | 17aa:366c | Intel      | 6 Series/C200 Series Chip... | 7     | snd_hda... | 3903A96DE3 |
| 8086:2284 | 103c:81bb | Intel      | Atom/Celeron/Pentium Proc... | 7     | snd_hda... | CA80EA46C5 |
| 8086:8c20 | 1028:05a7 | Intel      | 8 Series/C220 Series Chip... | 7     | snd_hda... | 16927C4FC4 |
| 1002:15b3 | 103c:8430 | AMD        | High Definition Audio Con... | 6     | snd_hda... | 5C5ADCC248 |
| 1002:9840 | 103c:2b3b | AMD        | Kabini HDMI/DP Audio         | 6     | snd_hda... | 1A5D2C36EC |
| 1002:aa60 | 106b:aa60 | AMD        | Redwood HDMI Audio [Radeo... | 6     | snd_hda... | C5621D630D |
| 1022:157a | 103c:8430 | AMD        | Family 15h (Models 60h-6f... | 6     | snd_hda... | 5C5ADCC248 |
| 1022:780d | 103c:2b3b | AMD        | FCH Azalia Controller        | 6     | snd_hda... | 1A5D2C36EC |
| 8086:0c0c | 103c:18e6 | Intel      | Xeon E3-1200 v3/4th Gen C... | 6     | snd_hda... | CF3ED91B8A |
| 8086:1e20 | 144d:b091 | Intel      | 7 Series/C216 Chipset Fam... | 6     | snd_hda... | 0F9E022C5E |
| 8086:2284 | 1028:06cc | Intel      | Atom/Celeron/Pentium Proc... | 6     | snd_hda... | 3AC5DA5F93 |
| 8086:3198 | 1854:0308 | Intel      | Celeron/Pentium Silver Pr... | 6     | snd_hda... | 125F68D06E |
| 8086:8c20 | 103c:18e6 | Intel      | 8 Series/C220 Series Chip... | 6     | snd_hda... | CF3ED91B8A |
| 8086:a348 | 103c:84ee | Intel      | Cannon Lake PCH cAVS         | 6     | snd_hda... | DF07E6AAB4 |
| 1002:aa90 | 144d:b091 | AMD        | Turks HDMI Audio [Radeon ... | 5     | snd_hda... | 0F9E022C5E |
| 10de:0bea | 104d:907e | Nvidia     | GF108 High Definition Aud... | 5     | snd_hda... | 626BFE0484 |
| 10de:0bea | 17aa:366c | Nvidia     | GF108 High Definition Aud... | 5     | snd_hda... | 42BC05AF33 |
| 8086:0c0c | 17aa:367b | Intel      | Xeon E3-1200 v3/4th Gen C... | 5     | snd_hda... | A459000D17 |
| 8086:0f04 | 17aa:3695 | Intel      | Atom Processor Z36xxx/Z37... | 5     | snd_hda... | CB2927D290 |
| 8086:1c20 | 104d:9083 | Intel      | 6 Series/C200 Series Chip... | 5     | snd_hda... | EEB433BF77 |
| 8086:1e20 | 104d:9097 | Intel      | 7 Series/C216 Chipset Fam... | 5     | snd_hda... | B2B912EF1E |
| 8086:1e20 | 17aa:3671 | Intel      | 7 Series/C216 Chipset Fam... | 5     | snd_hda... | 2A92010AD3 |
| 8086:3198 | 1043:3160 | Intel      | Celeron/Pentium Silver Pr... | 5     | snd_hda... | 3B910E6A74 |
| 8086:5a98 | 17aa:36c4 | Intel      | Celeron N3350/Pentium N42... | 5     | snd_hda... | 4B68C7AEE7 |
| 8086:8c20 | 17aa:367b | Intel      | 8 Series/C220 Series Chip... | 5     | snd_hda... | A459000D17 |
| 8086:9d71 | 1028:0754 | Intel      | Sunrise Point-LP HD Audio    | 5     | snd_hda... | 83612FBDEE |
| 8086:a170 | 103c:82dc | Intel      | 100 Series/C230 Series Ch... | 5     | snd_hda... | 036481482E |
| 1002:aac0 | 0000:aac0 | AMD        | Tobago HDMI Audio [Radeon... | 4     | snd_hda... | F04DA4053D |
| 1002:aad8 | 1002:aad8 | AMD        | Tonga HDMI Audio [Radeon ... | 4     | snd_hda... | E53C63BA89 |
| 10de:0e0a | 106b:010d | Nvidia     | GK104 HDMI Audio Controller  | 4     | snd_hda... | 674668F4DD |
| 8086:0c0c | 17aa:3686 | Intel      | Xeon E3-1200 v3/4th Gen C... | 4     | snd_hda... | 1E467924BF |
| 8086:0f04 | 1b50:5709 | Intel      | Atom Processor Z36xxx/Z37... | 4     | snd_hda... | B3E778A640 |
| 8086:160c | 106b:014f | Intel      | Broadwell-U Audio Controller | 4     | snd_hda... | 74E99D5666 |
| 8086:160c | 111e:10ec | Intel      | Broadwell-U Audio Controller | 4     | snd_hda... | 6CF5332D62 |
| 8086:1c20 | 1019:7c94 | Intel      | 6 Series/C200 Series Chip... | 4     | snd_hda... | 4FF205BED4 |
| 8086:1c20 | 1025:0618 | Intel      | 6 Series/C200 Series Chip... | 4     | snd_hda... | 0362E43257 |
| 8086:27d8 | 17aa:3602 | Intel      | NM10/ICH7 Family High Def... | 4     | snd_hda... | C25FDFE643 |
| 8086:27d8 | 17aa:3610 | Intel      | NM10/ICH7 Family High Def... | 4     | snd_hda... | 5DFF29AF66 |
| 8086:3198 | 103c:86f0 | Intel      | Celeron/Pentium Silver Pr... | 4     | snd_hda... | 9FDCC0F2AF |
| 8086:3198 | 1043:3150 | Intel      | Celeron/Pentium Silver Pr... | 4     | snd_hda... | BA03906EB8 |
| 8086:3b56 | 1025:045c | Intel      | 5 Series/3400 Series Chip... | 4     | snd_hda... | 306081B9C5 |
| 8086:8c20 | 1028:0623 | Intel      | 8 Series/C220 Series Chip... | 4     | snd_hda... | 3C11289E85 |
| 8086:8c20 | 17aa:3686 | Intel      | 8 Series/C220 Series Chip... | 4     | snd_hda... | 1E467924BF |
| 8086:8ca0 | 8086:7270 | Intel      | 9 Series Chipset Family H... | 4     | snd_hda... | 74E99D5666 |
| 8086:9ca0 | 8086:9ca0 | Intel      | Wildcat Point-LP High Def... | 4     | snd_hda... | 6CF5332D62 |
| 8086:9d71 | 103c:82dd | Intel      | Sunrise Point-LP HD Audio    | 4     | snd_hda... | 0A0BE4F02F |
| 8086:9dc8 | 1043:31e0 | Intel      | Cannon Point-LP High Defi... | 4     | snd_hda... | 72FCC11E52 |
| 8086:a170 | 103c:81b7 | Intel      | 100 Series/C230 Series Ch... | 4     | snd_hda... | AA69312028 |
| 8086:a348 | 103c:8446 | Intel      | Cannon Lake PCH cAVS         | 4     | snd_hda... | 651C327218 |
| 1002:1314 | 17aa:3670 | AMD        | Wrestler HDMI Audio          | 3     | snd_hda... | 225E0C36DC |
| 1002:15de | 103c:86f3 | AMD        | Raven/Raven2/Fenghuang HD... | 3     | snd_hda... | 4B12BB887A |
| 1002:15de | 17aa:36f5 | AMD        | Raven/Raven2/Fenghuang HD... | 3     | snd_hda... | EB38810FB8 |
| 1002:1714 | 1025:0642 | AMD        | BeaverCreek HDMI Audio [R... | 3     | snd_hda... | AFC950475D |
| 1002:4383 | 1028:0479 | AMD        | SBx00 Azalia (Intel HDA)     | 3     | snd_hda... | F7EF0F2C13 |
| 1002:4383 | 1bfd:0001 | AMD        | SBx00 Azalia (Intel HDA)     | 3     | snd_hda... | 09FE5E4566 |
| 1002:9840 | 1028:06d1 | AMD        | Kabini HDMI/DP Audio         | 3     | snd_hda... | 05A046D623 |
| 1002:9840 | 103c:2b2f | AMD        | Kabini HDMI/DP Audio         | 3     | snd_hda... | 093F49B44C |
| 1002:9840 | 17aa:36ab | AMD        | Kabini HDMI/DP Audio         | 3     | snd_hda... | 93BC9B0BE9 |

### Storage (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1217:8331 | 1bcf:a013 | O2 Micro   | O2 Flash Memory Card         | 2     |            | 1494683BB9 |
| 1106:401a | 17aa:3608 | VIA Tec... | VIA Card Reader Host Cont... | 1     |            | 69574214D7 |
| 1217:8130 | 17aa:3068 | O2 Micro   | Integrated MS/MSPRO/xD Co... | 1     |            | 27E7D42D53 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2829 | 106b:00a0 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 67    | ahci       | 00CC913F3D |
| 8086:1c02 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 62    | ahci       | 2216DC8384 |
| 10de:0ab9 | 10de:cb79 | Nvidia     | MCP79 AHCI Controller        | 42    | ahci       | 8AB1BA226D |
| 8086:3b22 | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 41    | ahci       | C5621D630D |
| 8086:a102 | 8086:7270 | Intel      | Q170/Q150/B150/H170/H110/... | 28    | ahci       | E53C63BA89 |
| 8086:1e02 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 20    | ahci       | DAE7632445 |
| 8086:8c02 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 19    | ahci       | 20FB29A6AE |
| 8086:a352 | 8086:7270 | Intel      | Cannon Lake PCH SATA AHCI... | 17    | ahci       | EB3D04E089 |
| 1022:7801 | 103c:8245 | AMD        | FCH SATA Controller [AHCI... | 11    | ahci       | 40434F824A |
| 8086:1c02 | 103c:2ac5 | Intel      | 6 Series/C200 Series Chip... | 11    | ahci       | 55450C73C0 |
| 8086:1c02 | 17aa:365e | Intel      | 6 Series/C200 Series Chip... | 11    | ahci       | 9164B5B105 |
| 144d:a801 | 144d:a801 | Samsung... | Electronics SATA controller  | 10    | ahci       | E53C63BA89 |
| 8086:1e02 | 1028:0543 | Intel      | 7 Series/C210 Series Chip... | 10    | ahci       | 0E4A62B59F |
| 8086:8c03 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 10    | ahci       | 0761ED6181 |
| 8086:9d03 | 8086:9d03 | Intel      | Sunrise Point-LP SATA Con... | 10    | ahci       | 1096F1F298 |
| 8086:1e02 | 1028:0548 | Intel      | 7 Series/C210 Series Chip... | 9     | ahci       | 8184B0981F |
| 8086:31e3 | 1025:1304 | Intel      | Celeron/Pentium Silver Pr... | 9     | ahci       | B7F823BFDA |
| 8086:3a22 | 1025:0266 | Intel      | 82801JI (ICH10 Family) SA... | 9     | ahci       | B24FDB7446 |
| 8086:9d03 | 1025:1287 | Intel      | Sunrise Point-LP SATA Con... | 9     | ahci       | EB23862DED |
| 8086:9d03 | 103c:84de | Intel      | Sunrise Point-LP SATA Con... | 8     | ahci       | B5E9340D85 |
| 1022:7901 | 103c:8381 | AMD        | FCH SATA Controller [AHCI... | 7     | ahci       | B4A3EC103B |
| 10de:0ad4 | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] AHC... | 7     | ahci       | 04B8123AA5 |
| 8086:1c02 | 1028:0511 | Intel      | 6 Series/C200 Series Chip... | 7     | ahci       | 5C781B927F |
| 8086:1c02 | 17aa:366c | Intel      | 6 Series/C200 Series Chip... | 7     | ahci       | 3903A96DE3 |
| 8086:1c03 | 104d:907e | Intel      | 6 Series/C200 Series Chip... | 7     | ahci       | 626BFE0484 |
| 8086:22a3 | 103c:81bb | Intel      | Atom/Celeron/Pentium Proc... | 7     | ahci       | CA80EA46C5 |
| 8086:3b22 | 17aa:306a | Intel      | 5 Series/3400 Series Chip... | 7     | ahci       | 0EF323D23D |
| 8086:8c03 | 1028:05db | Intel      | 8 Series/C220 Series Chip... | 7     | ahci       | 80CA4B15A5 |
| 1022:7801 | 103c:2b3b | AMD        | FCH SATA Controller [AHCI... | 6     | ahci       | 1A5D2C36EC |
| 1022:7901 | 103c:8430 | AMD        | FCH SATA Controller [AHCI... | 6     | ahci       | 5C5ADCC248 |
| 8086:1e02 | 144d:b091 | Intel      | 7 Series/C210 Series Chip... | 6     | ahci       | 0F9E022C5E |
| 8086:22a3 | 1028:06cc | Intel      | Atom/Celeron/Pentium Proc... | 6     | ahci       | 3AC5DA5F93 |
| 8086:31e3 | 1854:0308 | Intel      | Celeron/Pentium Silver Pr... | 6     | ahci       | 125F68D06E |
| 8086:8c02 | 103c:18e6 | Intel      | 8 Series/C220 Series Chip... | 6     | ahci       | CF3ED91B8A |
| 8086:a352 | 103c:84ee | Intel      | Cannon Lake PCH SATA AHCI... | 6     | ahci       | DF07E6AAB4 |
| 1b4b:9183 | 1b4b:9183 | Marvell... | 88SS9183 PCIe SSD Controller | 5     | ahci       | CCAB3D35E1 |
| 8086:0f23 | 17aa:3695 | Intel      | Atom Processor E3800 Seri... | 5     | ahci       | CB2927D290 |
| 8086:1c03 | 104d:9083 | Intel      | 6 Series/C200 Series Chip... | 5     | ahci       | EEB433BF77 |
| 8086:1e03 | 104d:9097 | Intel      | 7 Series Chipset Family 6... | 5     | ahci       | B2B912EF1E |
| 8086:5ae3 | 17aa:36c4 | Intel      | Celeron N3350/Pentium N42... | 5     | ahci       | 4B68C7AEE7 |
| 8086:8c02 | 17aa:367b | Intel      | 8 Series/C220 Series Chip... | 5     | ahci       | A459000D17 |
| 8086:9d03 | 1028:0754 | Intel      | Sunrise Point-LP SATA Con... | 5     | ahci       | 83612FBDEE |
| 8086:a102 | 103c:82dc | Intel      | Q170/Q150/B150/H170/H110/... | 5     | ahci       | 036481482E |
| 1022:43b7 | 1b21:1062 | AMD        | 300 Series Chipset SATA C... | 4     | ahci       | ACCB6ADA09 |
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 4     | ahci       | 991A74F3E5 |
| 8086:1c02 | 1019:7c94 | Intel      | 6 Series/C200 Series Chip... | 4     | ahci       | 4FF205BED4 |
| 8086:31e3 | 103c:86f0 | Intel      | Celeron/Pentium Silver Pr... | 4     | ahci       | 9FDCC0F2AF |
| 8086:31e3 | 1043:1e80 | Intel      | Celeron/Pentium Silver Pr... | 4     | ahci       | BA03906EB8 |
| 8086:31e3 | 1043:1ea0 | Intel      | Celeron/Pentium Silver Pr... | 4     | ahci       | 3B910E6A74 |
| 8086:31e3 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 4     | ahci       | 32E5618CFE |
| 8086:3b22 | 1025:045c | Intel      | 5 Series/3400 Series Chip... | 4     | ahci       | 306081B9C5 |
| 8086:8c02 | 1028:0623 | Intel      | 8 Series/C220 Series Chip... | 4     | ahci       | 3C11289E85 |
| 8086:8c02 | 17aa:3686 | Intel      | 8 Series/C220 Series Chip... | 4     | ahci       | 1E467924BF |
| 8086:8c83 | 8086:7270 | Intel      | 9 Series Chipset Family S... | 4     | ahci       | 74E99D5666 |
| 8086:9c83 | 8086:9c83 | Intel      | Wildcat Point-LP SATA Con... | 4     | ahci       | 6CF5332D62 |
| 8086:9d03 | 103c:82dd | Intel      | Sunrise Point-LP SATA Con... | 4     | ahci       | 0A0BE4F02F |
| 8086:a102 | 103c:81b7 | Intel      | Q170/Q150/B150/H170/H110/... | 4     | ahci       | AA69312028 |
| 8086:a102 | 8086:a102 | Intel      | Q170/Q150/B150/H170/H110/... | 4     | ahci       | 31E48D8DA1 |
| 8086:a352 | 103c:8446 | Intel      | Cannon Lake PCH SATA AHCI... | 4     | ahci       | 651C327218 |
| 1002:4391 | 1002:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 3     | ahci       | 09FE5E4566 |
| 1002:4391 | 1028:0479 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 3     | ahci       | F7EF0F2C13 |
| 1022:7801 | 1025:0642 | AMD        | FCH SATA Controller [AHCI... | 3     | ahci       | AFC950475D |
| 1022:7801 | 1025:0720 | AMD        | FCH SATA Controller [AHCI... | 3     | ahci       | B972470309 |
| 1022:7801 | 1028:06d1 | AMD        | FCH SATA Controller [AHCI... | 3     | ahci       | 05A046D623 |
| 1022:7801 | 103c:2b2f | AMD        | FCH SATA Controller [AHCI... | 3     | ahci       | 093F49B44C |
| 1022:7801 | 17aa:3670 | AMD        | FCH SATA Controller [AHCI... | 3     | ahci       | 225E0C36DC |
| 1022:7801 | 17aa:36ab | AMD        | FCH SATA Controller [AHCI... | 3     | ahci       | 93BC9B0BE9 |
| 1022:7901 | 1028:07e3 | AMD        | FCH SATA Controller [AHCI... | 3     | ahci       | ACCB6ADA09 |
| 1022:7901 | 103c:86f3 | AMD        | FCH SATA Controller [AHCI... | 3     | ahci       | 4B12BB887A |
| 1022:7901 | 17aa:36f5 | AMD        | FCH SATA Controller [AHCI... | 3     | ahci       | EB38810FB8 |
| 144d:1600 |           | Samsung... | Apple PCIe SSD               | 3     | ahci       | 7D12EF42AC |
| 1b21:0612 | 1b21:1060 | ASMedia... | ASM1062 Serial ATA Contro... | 3     | ahci       | FC4BF98DC2 |
| 8086:0f23 |           | Intel      | Atom Processor E3800 Seri... | 3     | ahci       | E6BCDB1E4D |
| 8086:0f23 | 1025:0994 | Intel      | Atom Processor E3800 Seri... | 3     | ahci       | 6247D83BAB |
| 8086:0f23 | 1297:2041 | Intel      | Atom Processor E3800 Seri... | 3     | ahci       | 26A6CD4678 |
| 8086:0f23 | 1854:0200 | Intel      | Atom Processor E3800 Seri... | 3     | ahci       | 40E267DF98 |
| 8086:1c02 | 1025:0492 | Intel      | 6 Series/C200 Series Chip... | 3     | ahci       | D8225AFA7A |
| 8086:1c02 | 1025:0608 | Intel      | 6 Series/C200 Series Chip... | 3     | ahci       | D0F0DA0187 |
| 8086:1c02 | 1025:0618 | Intel      | 6 Series/C200 Series Chip... | 3     | ahci       | 0362E43257 |
| 8086:1c02 | 1043:1c02 | Intel      | 6 Series/C200 Series Chip... | 3     | ahci       | 0554804F5F |
| 8086:1c02 | 8086:1c02 | Intel      | 6 Series/C200 Series Chip... | 3     | ahci       | 19478FF625 |
| 8086:1e03 | 1025:0792 | Intel      | 7 Series Chipset Family 6... | 3     | ahci       | 89F713C877 |
| 8086:1e03 | 1043:844d | Intel      | 7 Series Chipset Family 6... | 3     | ahci       | 61B5866007 |
| 8086:1e03 | 17aa:3671 | Intel      | 7 Series Chipset Family 6... | 3     | ahci       | 2A92010AD3 |
| 8086:1e03 | 1854:0167 | Intel      | 7 Series Chipset Family 6... | 3     | ahci       | D0CF0BEEA8 |
| 8086:22a3 | 1025:0992 | Intel      | Atom/Celeron/Pentium Proc... | 3     | ahci       | F2703DFC7E |
| 8086:3b22 | 1025:0297 | Intel      | 5 Series/3400 Series Chip... | 3     | ahci       | 96C29C6C68 |
| 8086:3b2f | 1028:0478 | Intel      | 5 Series/3400 Series Chip... | 3     | ahci       | A288705A4D |
| 8086:5ae3 | 1854:0267 | Intel      | Celeron N3350/Pentium N42... | 3     | ahci       | 41FA541CA4 |
| 8086:8c02 | 1028:0626 | Intel      | 8 Series/C220 Series Chip... | 3     | ahci       | F61158882E |
| 8086:8c02 | 17aa:3685 | Intel      | 8 Series/C220 Series Chip... | 3     | ahci       | 647613F22B |
| 8086:8c02 | 1b0a:0188 | Intel      | 8 Series/C220 Series Chip... | 3     | ahci       | 0C24A93146 |
| 8086:9c03 | 8086:7270 | Intel      | 8 Series SATA Controller ... | 3     | ahci       | 2F7B60E4CD |
| 8086:9d03 | 1028:0852 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 5A27DEAF8A |
| 8086:9d03 | 1043:12a1 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | E0EF808E3F |
| 8086:9d03 | 8086:7270 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 94DEDAFA8A |
| 8086:a102 | 17aa:30ba | Intel      | Q170/Q150/B150/H170/H110/... | 3     | ahci       | F3E9E0B2F5 |
| 1002:4390 | 17aa:3619 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 2     | ahci       | 79C67392D7 |
| 1002:4390 | 17aa:3629 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 2     | ahci       | D404124022 |
| 1002:4391 | 1043:8431 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 2     | ahci       | F1E1BF19CC |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2850 | 106b:00a0 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 77    | pata_acpi  | 00CC913F3D |
| 8086:27df | 8086:7270 | Intel      | 82801G (ICH7 Family) IDE ... | 17    | pata_acpi  | 394EF62F20 |
| 8086:27c4 | 8086:7270 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 16    | pata_acpi  | 394EF62F20 |
| 8086:2828 | 106b:00a0 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 11    | pata_acpi  | F4EA5B4B7E |
| 1002:439c | 1002:439c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 6     | pata_at... | DF82BB0E17 |
| 10de:0ab5 | 10de:cb79 | Nvidia     | MCP79 SATA Controller        | 4     | ahci, p... | 2212090FF2 |
| 8086:27c0 | 17aa:3602 | Intel      | NM10/ICH7 Family SATA Con... | 4     | ata_pii... | C25FDFE643 |
| 8086:27c0 | 17aa:3610 | Intel      | NM10/ICH7 Family SATA Con... | 4     | ata_pii... | 5D8EF57728 |
| 8086:3a20 | 104d:9060 | Intel      | 82801JI (ICH10 Family) 4 ... | 3     | ata_pii... | 05CFF66AC2 |
| 8086:3b20 | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 3     | ata_piix   | E9E4822309 |
| 1002:439c | 17aa:3629 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 2     | pata_at... | D404124022 |
| 8086:1c01 | 1bcf:a013 | Intel      | 6 Series/C200 Series Chip... | 2     | pata_acpi  | 1494683BB9 |
| 8086:1e01 | 17aa:3671 | Intel      | 7 Series Chipset Family 4... | 2     | ata_pii... | 906A62D75E |
| 8086:1e09 | 17aa:3671 | Intel      | 7 Series Chipset Family 2... | 2     | ata_pii... | 906A62D75E |
| 8086:27c4 | 1025:025a | Intel      | 82801GBM/GHM (ICH7-M Fami... | 2     | pata_acpi  | CA89C2F311 |
| 8086:3a20 | 104d:9044 | Intel      | 82801JI (ICH10 Family) 4 ... | 2     | ata_piix   | EB74857893 |
| 8086:8c00 | 1b0a:0183 | Intel      | 8 Series/C220 Series Chip... | 2     | ata_pii... | 78D39E18EF |
| 8086:8c08 | 1b0a:0183 | Intel      | 8 Series/C220 Series Chip... | 2     | ata_pii... | 78D39E18EF |
| 1002:438c | 1033:886f | AMD        | SB600 IDE                    | 1     | pata_at... | 86771347FB |
| 1002:439c | 1462:aa53 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | pata_at... | 7BD55BD71D |
| 1022:780c | 1043:8589 | AMD        | FCH IDE Controller           | 1     | pata_at... | C8D8836613 |
| 10de:0759 | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] IDE    | 1     | pata_am... | 04B8123AA5 |
| 197b:2363 | 1462:ae11 | JMicron... | JMB363 SATA/IDE Controller   | 1     | ahci       | 17AD880F72 |
| 197b:2363 | 197b:2363 | JMicron... | JMB363 SATA/IDE Controller   | 1     | ahci       | 8ADEBB44D3 |
| 8086:0f21 |           | Intel      | Atom Processor E3800 Seri... | 1     | ata_piix   | B3E778A640 |
| 8086:0f21 | 1025:085f | Intel      | Atom Processor E3800 Seri... | 1     | ata_pii... | 7923ACCECA |
| 8086:1c00 | 1019:0777 | Intel      | 6 Series/C200 Series Chip... | 1     | ata_pii... | 79832DA9DA |
| 8086:1c00 | 1025:0618 | Intel      | 6 Series/C200 Series Chip... | 1     | pata_acpi  | B8E61A53BD |
| 8086:1c00 | 103c:2aed | Intel      | 6 Series/C200 Series Chip... | 1     | ata_pii... | E2ADA83EE9 |
| 8086:1c00 | 17aa:365e | Intel      | 6 Series/C200 Series Chip... | 1     | ata_pii... | 098D8022D0 |
| 8086:1c00 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     | pata_acpi  | 3E6BAC2212 |
| 8086:1c08 | 1019:0777 | Intel      | 6 Series/C200 Series Chip... | 1     | ata_pii... | 79832DA9DA |
| 8086:1c08 | 1025:0618 | Intel      | 6 Series/C200 Series Chip... | 1     | pata_acpi  | B8E61A53BD |
| 8086:1c08 | 103c:2aed | Intel      | 6 Series/C200 Series Chip... | 1     | ata_pii... | E2ADA83EE9 |
| 8086:1c08 | 17aa:365e | Intel      | 6 Series/C200 Series Chip... | 1     | ata_pii... | 098D8022D0 |
| 8086:1c3c | 103c:3561 | Intel      | 6 Series/C200 Series Chip... | 1     | ata_gen... | 90E0F93E8D |
| 8086:1e01 | 1462:a953 | Intel      | 7 Series Chipset Family 4... | 1     | ata_pii... | 1EAD53F6C2 |
| 8086:2651 | 107b:4009 | Intel      | 82801FB/FW (ICH6/ICH6W) S... | 1     | pata_acpi  | 0213C3A21C |
| 8086:27c0 | 1043:8179 | Intel      | NM10/ICH7 Family SATA Con... | 1     | ata_pii... | A4A1D08110 |
| 8086:27c0 | 1462:a912 | Intel      | NM10/ICH7 Family SATA Con... | 1     | pata_acpi  | 24B782CFDD |
| 8086:27c0 | 1462:ae11 | Intel      | NM10/ICH7 Family SATA Con... | 1     | ata_pii... | 17AD880F72 |
| 8086:27c4 | 8086:27c4 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 1     | ata_pii... | B4CB6D23B4 |
| 8086:27df | 1043:8179 | Intel      | 82801G (ICH7 Family) IDE ... | 1     | ata_pii... | A4A1D08110 |
| 8086:27df | 1462:ae11 | Intel      | 82801G (ICH7 Family) IDE ... | 1     | ata_pii... | 17AD880F72 |
| 8086:2828 | 8086:2828 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 1     | pata_acpi  | CA755B34FD |
| 8086:2928 | 1025:0275 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 1     | pata_acpi  | 19FBB5D44C |
| 8086:2928 | 1043:833f | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 1     | ata_pii... | AADAAE6450 |
| 8086:2928 | 17aa:3068 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 1     | pata_acpi  | 27E7D42D53 |
| 8086:3a20 | 104d:9043 | Intel      | 82801JI (ICH10 Family) 4 ... | 1     | pata_acpi  | CFDCAC5734 |
| 8086:3b20 | 1462:ae31 | Intel      | 5 Series/3400 Series Chip... | 1     | ata_pii... | CBD910EA06 |
| 8086:3b20 | 17aa:306a | Intel      | 5 Series/3400 Series Chip... | 1     | ata_piix   | F15D263E67 |
| 8086:3b26 | 17aa:306a | Intel      | 5 Series/3400 Series Chip... | 1     | ata_piix   | F15D263E67 |
| 8086:3b28 | 17aa:360e | Intel      | 5 Series/3400 Series Chip... | 1     | pata_acpi  | 262A3EE2EE |
| 8086:8d3c | 8086:7270 | Intel      | C610/X99 series chipset I... | 1     |            | B2AD449201 |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a806 | 144d:a801 | Samsung... | Electronics Non-Volatile ... | 16    | nvme       | 74EC4FCD5B |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 14    | nvme       | EB3D04E089 |
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 13    | nvme       | F179844FE4 |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | BC501 NVMe Solid State Dr... | 10    | nvme       | 19963E0F47 |
| 15b7:5003 | 15b7:5003 | Sandisk    | WD Blue SN500 / PC SN520 ... | 6     | nvme       | 49834DA4FA |
| 106b:2001 | 106b:2001 | Apple      | S1X NVMe Controller          | 5     | nvme       | 520FC2DB5C |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 4     | nvme       | 301B4DE8EA |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 4     | nvme       | 8579540A18 |
| 106b:2005 | 106b:1800 | Apple      | ANS2 NVMe Controller         | 3     | nvme       | 0E4DAA1DE2 |
| 1179:0113 | 1179:0001 | Toshiba... | BG3 NVMe SSD Controller      | 3     | nvme       | EB38810FB8 |
| 1344:5410 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 3     | nvme       | 9440CC0137 |
| 2646:5008 | 2646:5008 | Kingsto... | U-SNS8154P3 NVMe SSD         | 3     | nvme       | 5820A2D4C3 |
| 126f:2263 | 126f:2263 | Silicon... | SM2263EN/SM2263XT SSD Con... | 2     | nvme       | B2AD449201 |
| 144d:a809 | 144d:a801 | Samsung... | NVMe Controller              | 2     | nvme       | 65195D0D22 |
| 1987:5007 | 1987:5007 | Phison ... | E7 NVMe Controller           | 2     | nvme       | DA913ED8D3 |
| 1179:0115 | 1179:0001 | Toshiba... | XG4 NVMe SSD Controller      | 1     | nvme       | F41BD5BF5B |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 1     | nvme       | 773BE13AA2 |
| 1179:011a | 1179:0001 | Toshiba... | XG6 NVMe SSD Controller      | 1     | nvme       | 930847F29A |
| 126f:2262 | 126f:2262 | Silicon... | SM2262/SM2262EN SSD Contr... | 1     | nvme       | 42B182D5F0 |
| 144d:a808 | 144d:a811 | Samsung... | NVMe SSD Controller SM981... | 1     | nvme       | 25999BFD58 |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/SN750 / PC ... | 1     | nvme       | 2BF103DD36 |
| 15b7:5006 | 15b7:5006 | Sandisk    | WD Black SN750 / PC SN730... | 1     | nvme       | E13500CDFD |
| 15b7:5007 | 15b7:5007 | Sandisk    | Non-Volatile memory contr... | 1     | nvme       | 3A565370DE |
| 15b7:5008 | 15b7:5008 | Sandisk    | Non-Volatile memory contr... | 1     | nvme       | B2EA83F411 |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 1     | nvme       | CB6D3B830B |
| 1cc4:2263 | 1cc4:1cc4 | Union M... | Non-Volatile memory contr... | 1     | nvme       | BF45CB3ED6 |
| 1e0f:0001 | 1e0f:0001 | KIOXIA     | Non-Volatile memory contr... | 1     | nvme       | 2F7FD6200F |
| 1e95:9100 | 126f:2263 | Solid S... | Non-Volatile memory contr... | 1     | nvme       | 2039BF53C7 |
| 2646:500c | 2646:500c | Kingsto... | Technology Company Non-Vo... | 1     | nvme       | 8D0477EA03 |
| 8086:0975 | 8086:8410 | Intel      | Non-Volatile memory contr... | 1     | nvme       | B928A63EF1 |
| 8086:0975 | 8086:8510 | Intel      | Non-Volatile memory contr... | 1     | nvme       | B928A63EF1 |
| 8086:2522 | 8086:3810 | Intel      | NVMe Optane Memory Series    | 1     | nvme       | F172B5B1EA |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 1     | nvme       | D77183679A |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 1     | nvme       | 577AD83B8F |
| c0a9:2263 | c0a9:2263 | Micron/... | P1 NVMe PCIe SSD             | 1     | nvme       | 0B1F7CCED7 |
| c0a9:540a | c0a9:540a | Micron/... | P2 NVMe PCIe SSD             | 1     | nvme       | BE2D770858 |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2822 | 1028:05a7 | Intel      | SATA Controller [RAID mode]  | 5     | ahci       | 24B92D8C70 |
| 8086:282a | 103c:84de | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 6B7FA4FF60 |
| 8086:282a | 1043:17b1 | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 72FCC11E52 |
| 8086:282a | 1025:1418 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 5820A2D4C3 |
| 8086:2822 | 1028:06c5 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 0E09B99FC0 |
| 8086:282a | 1028:0954 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 51D212B73F |
| 8086:282a | 152d:0924 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | D3B0FDDEDF |
| 8086:2822 | 1028:05b0 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | BDF125B54E |
| 8086:2822 | 1028:0625 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | 48D68A1579 |
| 8086:2822 | 1028:075d | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | F41BD5BF5B |
| 8086:2822 | 1028:079e | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | 2BF103DD36 |
| 8086:2822 | 103c:3561 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | 90E0F93E8D |
| 8086:2822 | 103c:82a6 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | DD3E2FA2B5 |
| 8086:2822 | 103c:838b | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | AC62725ABE |
| 8086:2822 | 103c:86c7 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | B928A63EF1 |
| 8086:2822 | 17aa:36dd | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | 7EBBF6AAD0 |
| 8086:282a | 1028:05d1 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 45C116DB45 |
| 8086:282a | 1028:05db | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 1DBF9CCED7 |
| 8086:282a | 1028:0853 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 107F431AD7 |
| 8086:282a | 1028:0953 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | D77787D6EC |
| 8086:282a | 17aa:36dc | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | A4AFD5181F |
| 8086:9a0b | 8086:0000 | Intel      | Volume Management Device ... | 1     | vmd        | 8D0477EA03 |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1513 | 2222:1111 | Intel      | CV82524 Thunderbolt Contr... | 63    | thunder... | 2216DC8384 |
| 8086:d150 |           | Intel      | Core Processor QPI Link      | 26    |            | 9AC85E317C |
| 8086:d151 |           | Intel      | Core Processor QPI Routin... | 26    |            | 9AC85E317C |
| 8086:d155 |           | Intel      | Core Processor System Man... | 26    |            | 9AC85E317C |
| 8086:d156 |           | Intel      | Core Processor Semaphore ... | 26    |            | 9AC85E317C |
| 8086:d157 |           | Intel      | Core Processor System Con... | 26    |            | 9AC85E317C |
| 8086:d158 |           | Intel      | Core Processor Miscellane... | 26    |            | 9AC85E317C |
| 8086:156c |           | Intel      | DSL5520 Thunderbolt 2 NHI... | 23    | thunder... | E53C63BA89 |
| 8086:15d2 | 8086:0000 | Intel      | JHL6540 Thunderbolt 3 NHI... | 22    | thunder... | 632B6526F7 |
| 8086:15eb | 8086:0000 | Intel      | JHL7540 Thunderbolt 3 NHI... | 17    | thunder... | EB3D04E089 |
| 197b:2382 | 1025:0266 | JMicron... | SD/MMC Host Controller       | 9     | sdhci_pci  | B24FDB7446 |
| 197b:2383 | 1025:0266 | JMicron... | MS Host Controller           | 9     | jmb38x_ms  | B24FDB7446 |
| 8086:1911 | 1025:1287 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 9     |            | EB23862DED |
| 8086:1911 | 8086:1911 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 9     |            | 2FDFFAE0E5 |
| 8086:3190 |           | Intel      | Celeron/Pentium Silver Pr... | 9     |            | 3B910E6A74 |
| 8086:3190 | 1025:1304 | Intel      | Celeron/Pentium Silver Pr... | 9     |            | B7F823BFDA |
| 1180:e232 | 104d:907e | Ricoh      | PCIe Memory Stick Host Co... | 7     |            | 626BFE0484 |
| 8086:1911 | 103c:84ee | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 6     |            | DF07E6AAB4 |
| 1180:e232 | 104d:9083 | Ricoh      | PCIe Memory Stick Host Co... | 5     |            | EEB433BF77 |
| 1180:e232 | 104d:9097 | Ricoh      | PCIe Memory Stick Host Co... | 5     |            | B2B912EF1E |
| 8086:1911 | 1028:0754 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 83612FBDEE |
| 197b:2382 | 17aa:3602 | JMicron... | SD/MMC Host Controller       | 4     | sdhci_pci  | C25FDFE643 |
| 197b:2383 | 17aa:3602 | JMicron... | MS Host Controller           | 4     | jmb38x_ms  | C25FDFE643 |
| 197b:2384 | 17aa:3602 | JMicron... | xD Host Controller           | 4     |            | C25FDFE643 |
| 8086:1911 | 103c:8446 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | 651C327218 |
| 8086:1911 | 1043:17b1 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | 72FCC11E52 |
| 8086:3190 | 103c:86f0 | Intel      | Celeron/Pentium Silver Pr... | 4     |            | 9FDCC0F2AF |
| 1180:e230 | 104d:9060 | Ricoh      | R5U2xx (R5U230 / R5U231 /... | 3     |            | 05CFF66AC2 |
| 197b:2382 | 1025:0275 | JMicron... | SD/MMC Host Controller       | 3     | sdhci_pci  | 49DF2710DC |
| 197b:2383 | 1025:0275 | JMicron... | MS Host Controller           | 3     | jmb38x_ms  | 49DF2710DC |
| 8086:1568 | 2222:1111 | Intel      | DSL4510 Thunderbolt NHI [... | 3     |            | 2F7B60E4CD |
| 8086:1911 | 1028:0852 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | 5A27DEAF8A |
| 8086:1911 | 8086:7270 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | E8A54D0908 |
| 8086:3190 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     |            | 32E5618CFE |
| 1180:0592 | 104d:9044 | Ricoh      | R5C592 Memory Stick Bus H... | 2     | r592       | EB74857893 |
| 1180:e230 | 104d:9074 | Ricoh      | R5U2xx (R5U230 / R5U231 /... | 2     |            | 68937CF6BB |
| 1180:e232 | 104d:908e | Ricoh      | PCIe Memory Stick Host Co... | 2     |            | 59BB8EC907 |
| 197b:2382 | 1025:0608 | JMicron... | SD/MMC Host Controller       | 2     | sdhci_pci  | BEDE9EC674 |
| 197b:2382 | 103c:1489 | JMicron... | SD/MMC Host Controller       | 2     | sdhci_pci  | 603E26F80F |
| 197b:2382 | 1043:842d | JMicron... | SD/MMC Host Controller       | 2     | sdhci_pci  | F1E1BF19CC |
| 197b:2383 | 1025:0608 | JMicron... | MS Host Controller           | 2     | jmb38x_ms  | BEDE9EC674 |
| 197b:2383 | 103c:1489 | JMicron... | MS Host Controller           | 2     | jmb38x_ms  | 603E26F80F |
| 197b:2384 | 103c:1489 | JMicron... | xD Host Controller           | 2     |            | 603E26F80F |
| 197b:2392 | 1043:84c1 | JMicron... | SD/MMC Host Controller       | 2     | sdhci_pci  | DB3BBECDD0 |
| 8086:1911 | 1025:1290 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | A27363041A |
| 8086:1911 | 1028:084b | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 301B4DE8EA |
| 8086:1911 | 1028:0954 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 51D212B73F |
| 8086:1911 | 1028:0984 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 3A565370DE |
| 8086:1911 | 1043:1241 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 608D0CE708 |
| 8086:1911 | 17aa:313d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 50AAA5CF43 |
| 8086:1911 | 17aa:36f4 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 773BE13AA2 |
| 8086:1911 | 17aa:36fe | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | CA86244C1D |
| 8086:1911 | 17aa:3701 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 3AAB28E1E4 |
| 8086:2014 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 2     |            | 43CB3AF3A5 |
| 8086:2016 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 2     |            | 43CB3AF3A5 |
| 8086:2018 |           | Intel      | Sky Lake-E M2PCI Registers   | 2     |            | 43CB3AF3A5 |
| 8086:2018 | 8086:0000 | Intel      | Sky Lake-E M2PCI Registers   | 2     |            | 43CB3AF3A5 |
| 8086:2021 | 8086:0000 | Intel      | Sky Lake-E CBDMA Registers   | 2     | ioatdma    | 43CB3AF3A5 |
| 8086:2024 | 8086:0000 | Intel      | Sky Lake-E MM/Vt-d Config... | 2     |            | 43CB3AF3A5 |
| 8086:2025 |           | Intel      | Sky Lake-E RAS               | 2     |            | 43CB3AF3A5 |
| 8086:2034 | 8086:0000 | Intel      | Sky Lake-E VT-d              | 2     |            | 43CB3AF3A5 |
| 8086:2035 |           | Intel      | Sky Lake-E RAS Configurat... | 2     |            | 43CB3AF3A5 |
| 8086:2040 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 2     |            | 43CB3AF3A5 |
| 8086:2041 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 2     |            | 43CB3AF3A5 |
| 8086:2042 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 2     | skx_uncore | 43CB3AF3A5 |
| 8086:2043 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 2     |            | 43CB3AF3A5 |
| 8086:2044 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 2     |            | 43CB3AF3A5 |
| 8086:2045 | 8086:0000 | Intel      | Sky Lake-E LM Channel 1      | 2     |            | 43CB3AF3A5 |
| 8086:2046 | 8086:0000 | Intel      | Sky Lake-E LMS Channel 1     | 2     | skx_uncore | 43CB3AF3A5 |
| 8086:2047 | 8086:0000 | Intel      | Sky Lake-E LMDP Channel 1    | 2     |            | 43CB3AF3A5 |
| 8086:2048 | 8086:0000 | Intel      | Sky Lake-E DECS Channel 2    | 2     |            | 43CB3AF3A5 |
| 8086:2049 | 8086:0000 | Intel      | Sky Lake-E LM Channel 2      | 2     |            | 43CB3AF3A5 |
| 8086:204a | 8086:0000 | Intel      | Sky Lake-E LMS Channel 2     | 2     | skx_uncore | 43CB3AF3A5 |
| 8086:204b | 8086:0000 | Intel      | Sky Lake-E LMDP Channel 2    | 2     |            | 43CB3AF3A5 |
| 8086:204e | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 2     | skx_uncore | 43CB3AF3A5 |
| 8086:2054 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 2     |            | 43CB3AF3A5 |
| 8086:2055 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 2     |            | 43CB3AF3A5 |
| 8086:2056 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 2     |            | 43CB3AF3A5 |
| 8086:2057 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 2     |            | 43CB3AF3A5 |
| 8086:2066 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 2     | skx_uncore | 43CB3AF3A5 |
| 8086:2080 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 2     |            | 43CB3AF3A5 |
| 8086:2081 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 2     |            | 43CB3AF3A5 |
| 8086:2082 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 2     |            | 43CB3AF3A5 |
| 8086:2083 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 2     |            | 43CB3AF3A5 |
| 8086:2084 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 2     |            | 43CB3AF3A5 |
| 8086:2085 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 2     |            | 43CB3AF3A5 |
| 8086:2086 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 2     |            | 43CB3AF3A5 |
| 8086:208d | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 2     |            | 43CB3AF3A5 |
| 8086:208e | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 2     |            | 43CB3AF3A5 |
| 8086:3190 | 103c:8431 | Intel      | Celeron/Pentium Silver Pr... | 2     |            | 02681BB7AC |
| 1180:0592 | 1033:886f | Ricoh      | R5C592 Memory Stick Bus H... | 1     | r592       | 86771347FB |
| 1180:0592 | 104d:9043 | Ricoh      | R5C592 Memory Stick Bus H... | 1     | r592       | CFDCAC5734 |
| 1180:0852 | 1033:886f | Ricoh      | xD-Picture Card Controller   | 1     | r852       | 86771347FB |
| 197b:2382 | 1025:039d | JMicron... | SD/MMC Host Controller       | 1     | sdhci_pci  | A629A81791 |
| 197b:2382 | 1043:842e | JMicron... | SD/MMC Host Controller       | 1     | sdhci_pci  | E0910009B1 |
| 197b:2382 | 1043:84af | JMicron... | SD/MMC Host Controller       | 1     | sdhci_pci  | DF82BB0E17 |
| 197b:2382 | 1043:84c1 | JMicron... | SD/MMC Host Controller       | 1     | sdhci_pci  | 0554804F5F |
| 197b:2383 | 1025:039d | JMicron... | MS Host Controller           | 1     | jmb38x_ms  | A629A81791 |
| 197b:2387 | 197b:2387 | JMicron... | SD/MMC Host Controller       | 1     |            | D0F0DA0187 |
| 197b:2388 | 197b:2388 | JMicron... | MS Host Controller           | 1     | jmb38x_ms  | D0F0DA0187 |

### Tv card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1131:7134 | 16be:5000 | Philips... | SAA7134/SAA7135HL Video B... | 1     | saa7134    | 098FE372A3 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2830 | 106b:00a0 | Intel      | 82801H (ICH8 Family) USB ... | 77    | uhci_hcd   | 00CC913F3D |
| 8086:2831 | 106b:00a0 | Intel      | 82801H (ICH8 Family) USB ... | 77    | uhci_hcd   | 00CC913F3D |
| 8086:2832 | 106b:00a0 | Intel      | 82801H (ICH8 Family) USB ... | 77    | uhci_hcd   | 00CC913F3D |
| 8086:2834 |           | Intel      | 82801H (ICH8 Family) USB ... | 77    | uhci_hcd   | 00CC913F3D |
| 8086:2835 | 106b:00a0 | Intel      | 82801H (ICH8 Family) USB ... | 77    | uhci_hcd   | 00CC913F3D |
| 8086:2836 | 106b:00a0 | Intel      | 82801H (ICH8 Family) USB2... | 77    | ehci_pci   | 00CC913F3D |
| 8086:283a | 106b:00a0 | Intel      | 82801H (ICH8 Family) USB2... | 77    | ehci_pci   | 00CC913F3D |
| 8086:1c26 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 63    | ehci_pci   | 2216DC8384 |
| 8086:1c27 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 63    | uhci_hcd   | 2216DC8384 |
| 8086:1c2c | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 63    | uhci_hcd   | 2216DC8384 |
| 8086:1c2d | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 63    | ehci_pci   | 2216DC8384 |
| 10de:0aa5 | 10de:cb79 | Nvidia     | MCP79 OHCI USB 1.1 Contro... | 46    | ohci_pci   | 8AB1BA226D |
| 10de:0aa6 | 10de:cb79 | Nvidia     | MCP79 EHCI USB 2.0 Contro... | 46    | ehci_pci   | 8AB1BA226D |
| 10de:0aa7 | 10de:cb79 | Nvidia     | MCP79 OHCI USB 1.1 Contro... | 46    | ohci_pci   | 8AB1BA226D |
| 10de:0aa9 | 10de:cb79 | Nvidia     | MCP79 EHCI USB 2.0 Contro... | 46    | ehci_pci   | 8AB1BA226D |
| 8086:3b34 | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 44    | ehci_pci   | C5621D630D |
| 8086:3b36 | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 44    | uhci_hcd   | C5621D630D |
| 8086:3b3b | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 44    | uhci_hcd   | C5621D630D |
| 8086:3b3c | 8086:7270 | Intel      | 5 Series/3400 Series Chip... | 44    | ehci_pci   | C5621D630D |
| 8086:8c31 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 33    | xhci_hcd   | 20FB29A6AE |
| 8086:a12f | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 28    | xhci_hcd   | E53C63BA89 |
| 8086:15d4 | 8086:0000 | Intel      | JHL6540 Thunderbolt 3 USB... | 22    | xhci_hcd   | 632B6526F7 |
| 8086:1e26 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 20    | ehci_pci   | DAE7632445 |
| 8086:1e2d | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 20    | ehci_pci   | DAE7632445 |
| 8086:1e31 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 20    | xhci_hcd   | DAE7632445 |
| 8086:15ec | 8086:0000 | Intel      | JHL7540 Thunderbolt 3 USB... | 17    | xhci_hcd   | EB3D04E089 |
| 8086:27c8 | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 17    | uhci_hcd   | 394EF62F20 |
| 8086:27c9 | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 17    | uhci_hcd   | 394EF62F20 |
| 8086:27ca | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 17    | uhci_hcd   | 394EF62F20 |
| 8086:27cb | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 17    | uhci_hcd   | 394EF62F20 |
| 8086:27cc | 8086:7270 | Intel      | NM10/ICH7 Family USB2 EHC... | 17    | ehci_pci   | 394EF62F20 |
| 8086:a36d | 8086:7270 | Intel      | Cannon Lake PCH USB 3.1 x... | 17    | xhci_hcd   | EB3D04E089 |
| 8086:1c26 | 17aa:365e | Intel      | 6 Series/C200 Series Chip... | 12    | ehci_hc... | 9164B5B105 |
| 8086:1c2d | 17aa:365e | Intel      | 6 Series/C200 Series Chip... | 12    | ehci_hc... | 9164B5B105 |
| 8086:9d2f | 103c:84de | Intel      | Sunrise Point-LP USB 3.0 ... | 12    | xhci_hcd   | B5E9340D85 |
| 1022:7808 | 103c:8245 | AMD        | FCH USB EHCI Controller      | 11    | ehci_pci   | 40434F824A |
| 1022:7814 | 103c:8245 | AMD        | FCH USB XHCI Controller      | 11    | xhci_hcd   | 40434F824A |
| 8086:1c26 | 103c:2ac5 | Intel      | 6 Series/C200 Series Chip... | 11    | ehci_pci   | 55450C73C0 |
| 8086:1c2d | 103c:2ac5 | Intel      | 6 Series/C200 Series Chip... | 11    | ehci_pci   | 55450C73C0 |
| 1912:0015 | 17aa:365e | Renesas... | uPD720202 USB 3.0 Host Co... | 10    | xhci_pci   | 9164B5B105 |
| 1b6f:7023 | 1025:8030 | Etron T... | EJ168 USB 3.0 Host Contro... | 10    | xhci_hcd   | 0362E43257 |
| 8086:1e26 | 1028:0543 | Intel      | 7 Series/C216 Chipset Fam... | 10    | ehci_pci   | 0E4A62B59F |
| 8086:1e2d | 1028:0543 | Intel      | 7 Series/C216 Chipset Fam... | 10    | ehci_pci   | 0E4A62B59F |
| 8086:1e31 | 1028:0543 | Intel      | 7 Series/C210 Series Chip... | 10    | xhci_hcd   | 0E4A62B59F |
| 8086:1e26 | 1028:0548 | Intel      | 7 Series/C216 Chipset Fam... | 9     | ehci_pci   | 8184B0981F |
| 8086:1e2d | 1028:0548 | Intel      | 7 Series/C216 Chipset Fam... | 9     | ehci_pci   | 8184B0981F |
| 8086:1e31 | 1028:0548 | Intel      | 7 Series/C210 Series Chip... | 9     | xhci_hcd   | 8184B0981F |
| 8086:31a8 | 1025:1304 | Intel      | Celeron/Pentium Silver Pr... | 9     | xhci_hcd   | B7F823BFDA |
| 8086:31a8 | 1043:201f | Intel      | Celeron/Pentium Silver Pr... | 9     | xhci_hcd   | 3B910E6A74 |
| 8086:3a34 | 1025:0266 | Intel      | 82801JI (ICH10 Family) US... | 9     | uhci_hcd   | B24FDB7446 |
| 8086:3a35 | 1025:0266 | Intel      | 82801JI (ICH10 Family) US... | 9     | uhci_hcd   | B24FDB7446 |
| 8086:3a36 | 1025:0266 | Intel      | 82801JI (ICH10 Family) US... | 9     | uhci_hcd   | B24FDB7446 |
| 8086:3a37 | 1025:0266 | Intel      | 82801JI (ICH10 Family) US... | 9     | uhci_hcd   | B24FDB7446 |
| 8086:3a38 | 1025:0266 | Intel      | 82801JI (ICH10 Family) US... | 9     | uhci_hcd   | B24FDB7446 |
| 8086:3a39 | 1025:0266 | Intel      | 82801JI (ICH10 Family) US... | 9     | uhci_hcd   | B24FDB7446 |
| 8086:3a3a | 1025:0266 | Intel      | 82801JI (ICH10 Family) US... | 9     | ehci_pci   | B24FDB7446 |
| 8086:3a3c | 1025:0266 | Intel      | 82801JI (ICH10 Family) US... | 9     | ehci_pci   | B24FDB7446 |
| 8086:9d2f | 1025:1287 | Intel      | Sunrise Point-LP USB 3.0 ... | 9     | xhci_hcd   | EB23862DED |
| 1022:7908 | 103c:8381 | AMD        | FCH USB EHCI Controller      | 8     | ehci_pci   | B4A3EC103B |
| 1022:7914 | 103c:8381 | AMD        | FCH USB XHCI Controller      | 8     | xhci_hcd   | B4A3EC103B |
| 8086:3b34 | 17aa:306a | Intel      | 5 Series/3400 Series Chip... | 8     | ehci_pci   | 0EF323D23D |
| 8086:3b3c | 17aa:306a | Intel      | 5 Series/3400 Series Chip... | 8     | ehci_pci   | 0EF323D23D |
| 8086:8c26 | 1028:05db | Intel      | 8 Series/C220 Series Chip... | 8     | ehci_pci   | 80CA4B15A5 |
| 8086:8c2d | 1028:05db | Intel      | 8 Series/C220 Series Chip... | 8     | ehci_pci   | 80CA4B15A5 |
| 8086:8c31 | 1028:05db | Intel      | 8 Series/C220 Series Chip... | 8     | xhci_hcd   | 80CA4B15A5 |
| 8086:9d2f | 1043:8694 | Intel      | Sunrise Point-LP USB 3.0 ... | 8     | xhci_hcd   | 2FDFFAE0E5 |
| 1033:0194 | 104d:907e | NEC Com... | uPD720200 USB 3.0 Host Co... | 7     | xhci_pci   | 626BFE0484 |
| 10de:077b | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] OHC... | 7     | ohci_hc... | 04B8123AA5 |
| 10de:077c | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] EHC... | 7     | ehci_hc... | 04B8123AA5 |
| 10de:077d | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] OHC... | 7     | ohci_hc... | 04B8123AA5 |
| 10de:077e | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] EHC... | 7     | ehci_hc... | 04B8123AA5 |
| 1912:0015 | 17aa:366c | Renesas... | uPD720202 USB 3.0 Host Co... | 7     | xhci_pci   | 3903A96DE3 |
| 8086:1c26 | 1028:0511 | Intel      | 6 Series/C200 Series Chip... | 7     | ehci_pci   | 5C781B927F |
| 8086:1c26 | 104d:907e | Intel      | 6 Series/C200 Series Chip... | 7     | ehci_hc... | 626BFE0484 |
| 8086:1c26 | 17aa:366c | Intel      | 6 Series/C200 Series Chip... | 7     | ehci_hc... | 3903A96DE3 |
| 8086:1c2d | 1028:0511 | Intel      | 6 Series/C200 Series Chip... | 7     | ehci_pci   | 5C781B927F |
| 8086:1c2d | 104d:907e | Intel      | 6 Series/C200 Series Chip... | 7     | ehci_hc... | 626BFE0484 |
| 8086:1c2d | 17aa:366c | Intel      | 6 Series/C200 Series Chip... | 7     | ehci_hc... | 3903A96DE3 |
| 8086:22b5 |           | Intel      | Atom/Celeron/Pentium Proc... | 7     | xhci_hcd   | 3AC5DA5F93 |
| 8086:22b5 | 103c:81bb | Intel      | Atom/Celeron/Pentium Proc... | 7     | xhci_hcd   | CA80EA46C5 |
| 8086:8c26 | 1028:05a7 | Intel      | 8 Series/C220 Series Chip... | 7     | ehci_pci   | 16927C4FC4 |
| 8086:8c2d | 1028:05a7 | Intel      | 8 Series/C220 Series Chip... | 7     | ehci_pci   | 16927C4FC4 |
| 8086:8c31 | 1028:05a7 | Intel      | 8 Series/C220 Series Chip... | 7     | xhci_hcd   | 16927C4FC4 |
| 1002:4396 | 1002:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 6     | ehci_hc... | DF82BB0E17 |
| 1002:4397 | 1002:4397 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 6     | ohci_hc... | DF82BB0E17 |
| 1022:7808 | 103c:2b3b | AMD        | FCH USB EHCI Controller      | 6     | ehci_pci   | 1A5D2C36EC |
| 1022:7814 | 103c:2b3b | AMD        | FCH USB XHCI Controller      | 6     | xhci_hcd   | 1A5D2C36EC |
| 1022:7908 | 103c:8430 | AMD        | FCH USB EHCI Controller      | 6     | ehci_hcd   | 5C5ADCC248 |
| 1022:7914 | 103c:8430 | AMD        | FCH USB XHCI Controller      | 6     | xhci_hcd   | 5C5ADCC248 |
| 8086:1e26 | 144d:b091 | Intel      | 7 Series/C216 Chipset Fam... | 6     | ehci_hc... | 0F9E022C5E |
| 8086:1e2d | 144d:b091 | Intel      | 7 Series/C216 Chipset Fam... | 6     | ehci_hc... | 0F9E022C5E |
| 8086:1e31 | 144d:b091 | Intel      | 7 Series/C210 Series Chip... | 6     | xhci_pci   | 0F9E022C5E |
| 8086:31a8 | 1854:0308 | Intel      | Celeron/Pentium Silver Pr... | 6     | xhci_hcd   | 125F68D06E |
| 8086:8c26 | 103c:18e6 | Intel      | 8 Series/C220 Series Chip... | 6     | ehci_hc... | CF3ED91B8A |
| 8086:8c2d | 103c:18e6 | Intel      | 8 Series/C220 Series Chip... | 6     | ehci_hc... | CF3ED91B8A |
| 8086:8c31 | 103c:18e6 | Intel      | 8 Series/C220 Series Chip... | 6     | xhci_pci   | CF3ED91B8A |
| 8086:a36d | 103c:84ee | Intel      | Cannon Lake PCH USB 3.1 x... | 6     | xhci_hcd   | DF07E6AAB4 |
| 1002:4399 | 1002:4399 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 5     | ohci_hc... | DF82BB0E17 |
| 1033:0194 | 104d:9083 | NEC Com... | uPD720200 USB 3.0 Host Co... | 5     | xhci_hcd   | EEB433BF77 |
| 8086:0f35 | 17aa:3695 | Intel      | Atom Processor Z36xxx/Z37... | 5     | xhci_hcd   | CB2927D290 |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8d7c | 8086:7270 | Intel      | C610/X99 series chipset SPSR | 1     |            | B2AD449201 |

