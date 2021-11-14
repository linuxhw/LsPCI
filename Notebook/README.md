Most popular PCI devices in Notebooks
=====================================

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Notebooks ](#pci-devices)
   * [ Bluetooth ](#bluetooth-pci)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Digitizer pen ](#digitizer-pen-pci)
   * [ Dma controller (eisa dma) ](#dma-controller-eisa-dma-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Firewire controller ](#firewire-controller-pci)
   * [ Flash memory ](#flash-memory-pci)
   * [ Generic system peripheral ](#generic-system-peripheral-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Iommu ](#iommu-pci)
   * [ Ipmi interface (kcs) ](#ipmi-interface-kcs-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Modem ](#modem-pci)
   * [ Multimedia controller ](#multimedia-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Non-essential instrumentation ](#non-essential-instrumentation-pci)
   * [ Non-vga unclassified device ](#non-vga-unclassified-device-pci)
   * [ Performance counters ](#performance-counters-pci)
   * [ Pic (8259) ](#pic-8259-pci)
   * [ Pic (io(x)-apic) ](#pic-iox-apic-pci)
   * [ Rf controller ](#rf-controller-pci)
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
| 1814:3298 | 103c:18ec | Ralink     | RT3290 Bluetooth             | 542   | rtbth      | FBF77D8C63 |
| 1814:3298 | 105b:e056 | Ralink     | RT3290 Bluetooth             | 114   | rtbth      | D96D114426 |
| 1814:3298 | 103c:191c | Ralink     | RT3290 Bluetooth             | 27    | rtbth      | E12E55583D |
| 1814:3298 | 1a3b:2f87 | Ralink     | RT3290 Bluetooth             | 14    |            | 5FAD549031 |
| 1814:3298 | 1a3b:2787 | Ralink     | RT3290 Bluetooth             | 10    |            | 72AA2E75FC |
| 1814:3298 | 1814:3298 | Ralink     | RT3290 Bluetooth             | 5     |            | FCE7CA77F0 |
| 1814:3298 | 10cf:1772 | Ralink     | RT3290 Bluetooth             | 1     |            | 1135E21142 |
| 1814:3298 | 1a3b:210b | Ralink     | RT3290 Bluetooth             | 1     |            | 2333E930AF |
| 1814:3298 | 1a3b:2987 | Ralink     | RT3290 Bluetooth             | 1     |            | EC90AB9922 |

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1452 |           | AMD        | Family 17h (Models 00h-1f... | 2002  |            | E8781DB5AB |
| 1022:15e8 |           | AMD        | Raven/Raven2 Device 24: F... | 1982  |            | E8781DB5AB |
| 1022:15e9 |           | AMD        | Raven/Raven2 Device 24: F... | 1982  |            | E8781DB5AB |
| 1022:15ea |           | AMD        | Raven/Raven2 Device 24: F... | 1982  |            | E8781DB5AB |
| 1022:15eb |           | AMD        | Raven/Raven2 Device 24: F... | 1982  | k10temp    | E8781DB5AB |
| 1022:15ec |           | AMD        | Raven/Raven2 Device 24: F... | 1982  |            | E8781DB5AB |
| 1022:15ed |           | AMD        | Raven/Raven2 Device 24: F... | 1982  |            | E8781DB5AB |
| 1022:15ee |           | AMD        | Raven/Raven2 Device 24: F... | 1982  |            | E8781DB5AB |
| 1022:15ef |           | AMD        | Raven/Raven2 Device 24: F... | 1982  |            | E8781DB5AB |
| 1002:4384 |           | AMD        | SBx00 PCI to PCI Bridge      | 1888  | shpchp     | CF2BC09886 |
| 8086:2c62 | 8086:8086 | Intel      | Core Processor QuickPath ... | 1785  |            | C319EC4A5F |
| 8086:2d01 | 8086:8086 | Intel      | Core Processor QuickPath ... | 1785  |            | C319EC4A5F |
| 8086:2d10 | 8086:8086 | Intel      | Core Processor QPI Link 0    | 1785  |            | C319EC4A5F |
| 8086:2d11 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 1785  |            | C319EC4A5F |
| 8086:2d12 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 1785  |            | C319EC4A5F |
| 8086:2d13 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 1785  |            | C319EC4A5F |
| 1022:15db | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 1659  | pcieport   | E8781DB5AB |
| 1022:780f |           | AMD        | FCH PCI Bridge               | 1569  | shpchp     | B92CD04EE7 |
| 1022:1632 |           | AMD        | Renoir PCIe Dummy Host Br... | 1503  |            | F581CF8319 |
| 1022:1700 |           | AMD        | Family 12h/14h Processor ... | 1499  |            | F6819A066A |
| 1022:1701 |           | AMD        | Family 12h/14h Processor ... | 1499  |            | F6819A066A |
| 1022:1702 |           | AMD        | Family 12h/14h Processor ... | 1499  |            | F6819A066A |
| 1022:1703 |           | AMD        | Family 12h/14h Processor ... | 1499  | k10temp    | F6819A066A |
| 1022:1704 |           | AMD        | Family 12h/14h Processor ... | 1499  |            | F6819A066A |
| 1022:1716 |           | AMD        | Family 12h/14h Processor ... | 1499  |            | F6819A066A |
| 1022:1718 |           | AMD        | Family 12h/14h Processor ... | 1499  |            | F6819A066A |
| 1022:1719 |           | AMD        | Family 12h/14h Processor ... | 1499  |            | F6819A066A |
| 1022:1448 |           | AMD        | Renoir Device 24: Function 0 | 1302  |            | F581CF8319 |
| 1022:1449 |           | AMD        | Renoir Device 24: Function 1 | 1302  |            | F581CF8319 |
| 1022:144a |           | AMD        | Renoir Device 24: Function 2 | 1302  |            | F581CF8319 |
| 1022:144b |           | AMD        | Renoir Device 24: Function 3 | 1302  | k10temp    | F581CF8319 |
| 1022:144c |           | AMD        | Renoir Device 24: Function 4 | 1302  |            | F581CF8319 |
| 1022:144d |           | AMD        | Renoir Device 24: Function 5 | 1302  |            | F581CF8319 |
| 1022:144e |           | AMD        | Renoir Device 24: Function 6 | 1302  |            | F581CF8319 |
| 1022:144f |           | AMD        | Renoir Device 24: Function 7 | 1302  |            | F581CF8319 |
| 1022:15dc | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 1185  | pcieport   | 497BF56CC6 |
| 1022:157b |           | AMD        | Family 15h (Models 60h-6f... | 1171  |            | 3A06ECCCAA |
| 1022:157d |           | AMD        | Carrizo Audio Dummy Host ... | 1171  |            | 3A06ECCCAA |
| 1022:15d3 | 1022:1453 | AMD        | Raven/Raven2 PCIe GPP Bri... | 1168  | pcieport   | E8781DB5AB |
| 1022:1635 | 1022:1635 | AMD        | Renoir Internal PCIe GPP ... | 1092  | pcieport   | F581CF8319 |
| 8086:2448 |           | Intel      | 82801 Mobile PCI Bridge      | 1006  | shpchp     | C0FAA178A2 |
| 1022:15d0 | 1022:15d0 | AMD        | Raven/Raven2 Root Complex    | 911   | k10temp    | 497BF56CC6 |
| 1022:15b0 |           | AMD        | Stoney HT Configuration      | 831   |            | 3A06ECCCAA |
| 1022:15b1 |           | AMD        | Stoney Address Maps          | 831   |            | 3A06ECCCAA |
| 1022:15b2 |           | AMD        | Stoney DRAM Configuration    | 831   |            | 3A06ECCCAA |
| 1022:15b3 |           | AMD        | Stoney Miscellaneous Conf... | 831   | k10temp    | 3A06ECCCAA |
| 1022:15b4 |           | AMD        | Stoney PM Configuration      | 831   | fam15h_... | 3A06ECCCAA |
| 1022:15b5 |           | AMD        | Stoney NB Performance Mon... | 831   |            | 3A06ECCCAA |
| 1022:1439 | 1022:1234 | AMD        | Family 16h Processor Func... | 805   | pcieport   | AB5E53C9ED |
| 1022:156b |           | AMD        | Family 16h (Models 30h-3f... | 797   |            | 65C122FE69 |
| 1022:1580 |           | AMD        | Family 16h (Models 30h-3f... | 797   |            | 65C122FE69 |
| 1022:1581 |           | AMD        | Family 16h (Models 30h-3f... | 797   |            | 65C122FE69 |
| 1022:1582 |           | AMD        | Family 16h (Models 30h-3f... | 797   |            | 65C122FE69 |
| 1022:1583 |           | AMD        | Family 16h (Models 30h-3f... | 797   | k10temp    | 65C122FE69 |
| 1022:1584 |           | AMD        | Family 16h (Models 30h-3f... | 797   | fam15h_... | 65C122FE69 |
| 1022:1585 |           | AMD        | Family 16h (Models 30h-3f... | 797   |            | 65C122FE69 |
| 1022:43a0 | 1022:0000 | AMD        | Hudson PCI to PCI bridge ... | 721   | pcieport   | B92CD04EE7 |
| 1022:1634 | 1022:1453 | AMD        | Renoir/Cezanne PCIe GPP B... | 683   | pcieport   | F581CF8319 |
| 1002:43a0 | 1002:0000 | AMD        | SB700/SB800/SB900 PCI to ... | 644   | pcieport   | C8075F4483 |
| 1022:1400 |           | AMD        | Family 15h (Models 10h-1f... | 644   |            | BB9C65380C |
| 1022:1401 |           | AMD        | Family 15h (Models 10h-1f... | 644   |            | BB9C65380C |
| 1022:1402 |           | AMD        | Family 15h (Models 10h-1f... | 644   |            | BB9C65380C |
| 1022:1403 |           | AMD        | Family 15h (Models 10h-1f... | 644   | k10temp    | BB9C65380C |
| 1022:1404 |           | AMD        | Family 15h (Models 10h-1f... | 644   |            | BB9C65380C |
| 1022:1405 |           | AMD        | Family 15h (Models 10h-1f... | 644   |            | BB9C65380C |
| 1022:1510 | 1022:1510 | AMD        | Family 14h Processor Root... | 610   |            | F6819A066A |
| 1022:1100 |           | AMD        | K8 [Athlon64/Opteron] Hyp... | 601   |            | A649C72C69 |
| 1022:1101 |           | AMD        | K8 [Athlon64/Opteron] Add... | 601   |            | A649C72C69 |
| 1022:1102 |           | AMD        | K8 [Athlon64/Opteron] DRA... | 601   |            | A649C72C69 |
| 1022:1103 |           | AMD        | K8 [Athlon64/Opteron] Mis... | 601   | k8temp     | A649C72C69 |
| 1022:1200 |           | AMD        | Family 10h Processor Hype... | 597   |            | CF2BC09886 |
| 1022:1201 |           | AMD        | Family 10h Processor Addr... | 597   |            | CF2BC09886 |
| 1022:1202 |           | AMD        | Family 10h Processor DRAM... | 597   |            | CF2BC09886 |
| 1022:1203 |           | AMD        | Family 10h Processor Misc... | 597   | k10temp    | CF2BC09886 |
| 1022:1204 |           | AMD        | Family 10h Processor Link... | 597   |            | CF2BC09886 |
| 1022:43a1 | 1022:0000 | AMD        | Hudson PCI to PCI bridge ... | 556   | pcieport   | B92CD04EE7 |
| 8086:1e10 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 555   | shpchp     | 16EBDC4388 |
| 8086:1e12 | 17aa:3977 | Intel      | 7 Series/C210 Series Chip... | 540   | shpchp     | 16EBDC4388 |
| 1022:1630 | 1022:1630 | AMD        | Renoir/Cezanne Root Complex  | 488   | ryzen_smu  | 8948989999 |
| 1022:1414 | 1022:1234 | AMD        | Family 15h (Models 10h-1f... | 485   | pcieport   | BB9C65380C |
| 1022:1530 |           | AMD        | Family 16h Processor Func... | 468   |            | AB5E53C9ED |
| 1022:1531 |           | AMD        | Family 16h Processor Func... | 468   |            | AB5E53C9ED |
| 1022:1532 |           | AMD        | Family 16h Processor Func... | 468   |            | AB5E53C9ED |
| 1022:1533 |           | AMD        | Family 16h Processor Func... | 468   | k10temp    | AB5E53C9ED |
| 1022:1534 |           | AMD        | Family 16h Processor Func... | 468   | fam15h_... | AB5E53C9ED |
| 1022:1535 |           | AMD        | Family 16h Processor Func... | 468   |            | AB5E53C9ED |
| 1022:1538 |           | AMD        | Family 16h Processor Func... | 468   |            | AB5E53C9ED |
| 8086:0154 | 17aa:3977 | Intel      | 3rd Gen Core processor DR... | 465   | ivb_uncore | 16EBDC4388 |
| 8086:2280 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 443   | iosf_mb... | 2FBF6F153B |
| 8086:229c | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 443   | lpc_ich    | 2FBF6F153B |
| 8086:1e59 | 17aa:3977 | Intel      | HM76 Express Chipset LPC ... | 432   | lpc_ich    | 16EBDC4388 |
| 8086:2940 |           | Intel      | 82801I (ICH9 Family) PCI ... | 421   | pcieport   | 01EB2C3459 |
| 1022:1709 | 1022:1234 | AMD        | Family 12h Processor Root... | 401   | shpchp     | 2E9D378E76 |
| 1002:43a1 | 1002:0000 | AMD        | SB700/SB800/SB900 PCI to ... | 397   | pcieport   | C8075F4483 |
| 1022:1512 | 1022:1234 | AMD        | Family 14h Processor Root... | 387   | pcieport   | F6819A066A |
| 8086:294a |           | Intel      | 82801I (ICH9 Family) PCI ... | 363   | pcieport   | C0FAA178A2 |
| 8086:2944 |           | Intel      | 82801I (ICH9 Family) PCI ... | 360   | pcieport   | 01EB2C3459 |
| 1022:1570 |           | AMD        | Family 15h (Models 60h-6f... | 340   |            | E4AA5740C5 |
| 1022:1571 |           | AMD        | Family 15h (Models 60h-6f... | 340   |            | E4AA5740C5 |
| 1022:1572 |           | AMD        | Family 15h (Models 60h-6f... | 340   |            | E4AA5740C5 |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:5287 | 1043:202f | Realtek... | RTL8411B PCI Express Card... | 299   | rtsx_pci   | 739623468A |
| 10ec:5286 | 1043:202f | Realtek... | RTL8402 Integrated 1-LUN ... | 232   | rtsx_pci   | 4A70424B2F |
| 10ec:5289 | 1043:202f | Realtek... | RTL8411 PCI Express Card ... | 172   | rtsx_pci   | 3498166FA2 |
| 10ec:5286 | 10ec:5286 | Realtek... | RTL8402 Integrated 1-LUN ... | 160   | rtsx_pci   | A5F750922A |
| 10ec:525a | 1028:0905 | Realtek... | RTS525A PCI Express Card ... | 140   | rtsx_pci   | 58E43F0514 |
| 10ec:5229 | 1043:202f | Realtek... | RTS5229 PCI Express Card ... | 131   | rtsx_pci   | 085EF9E58D |
| 10ec:522a | 17aa:5082 | Realtek... | RTS522A PCI Express Card ... | 130   | rtsx_pci   | 273A5FF27D |
| 10ec:5227 | 17aa:220c | Realtek... | RTS5227 PCI Express Card ... | 126   | rtsx_pci   | 415CC7FE56 |
| 10ec:522a | 103c:8079 | Realtek... | RTS522A PCI Express Card ... | 120   | rtsx_pci   | 436E9BF227 |
| 10ec:5287 | 1025:1193 | Realtek... | RTL8411B PCI Express Card... | 119   | rtsx_pci   | 43BFEF3BCD |
| 10ec:5287 | 1025:0866 | Realtek... | RTL8411B PCI Express Card... | 118   | rtsx_pci   | 11EBF2008B |
| 10ec:5227 | 17aa:220e | Realtek... | RTS5227 PCI Express Card ... | 117   | rtsx_pci   | 36F407C3AA |
| 10ec:522a | 10ec:522a | Realtek... | RTS522A PCI Express Card ... | 116   | rtsx_pci   | 87B3274937 |
| 10ec:5289 | 10ec:5289 | Realtek... | RTL8411 PCI Express Card ... | 116   | rtsx_pci   | 93116D84F3 |
| 10ec:5227 | 17aa:5034 | Realtek... | RTS5227 PCI Express Card ... | 113   | rtsx_pci   | CEA37DD548 |
| 10ec:525a | 1028:087c | Realtek... | RTS525A PCI Express Card ... | 113   | rtsx_pci   | 0FA8C3ED0C |
| 10ec:5227 | 103c:198f | Realtek... | RTS5227 PCI Express Card ... | 110   | rtsx_pci   | CECD552E89 |
| 10ec:5209 | 104d:908b | Realtek... | RTS5209 PCI Express Card ... | 106   | rtsx_pci   | 11EF4D4BAF |
| 10ec:5287 | 1025:1094 | Realtek... | RTL8411B PCI Express Card... | 105   | rtsx_pci   | 89135238FE |
| 10ec:525a | 1028:07be | Realtek... | RTS525A PCI Express Card ... | 97    | rtsx_pci   | 69938C221E |
| 10ec:525a | 1028:07e6 | Realtek... | RTS525A PCI Express Card ... | 97    | rtsx_pci   | 5A56854746 |
| 10ec:5229 | 17aa:3808 | Realtek... | RTS5229 PCI Express Card ... | 96    | rtsx_pci   | 184B909FC0 |
| 10ec:525a | 1028:0962 | Realtek... | RTS525A PCI Express Card ... | 91    | rtsx_pci   | 8956FEE2F3 |
| 10ec:525a | 1028:08af | Realtek... | RTS525A PCI Express Card ... | 90    | rtsx_pci   | 52DEA66C52 |
| 10ec:5227 | 17aa:2214 | Realtek... | RTS5227 PCI Express Card ... | 89    | rtsx_pci   | F802ABEF07 |
| 10ec:5227 | 17aa:2226 | Realtek... | RTS5227 PCI Express Card ... | 87    | rtsx_pci   | 22A87CB141 |
| 10ec:5209 | 1025:0685 | Realtek... | RTS5209 PCI Express Card ... | 86    | rtsx_pci   | B953B67D06 |
| 10ec:5229 | 103c:1854 | Realtek... | RTS5229 PCI Express Card ... | 86    | rtsx_pci   | B0ED67249E |
| 10ec:5229 | 10ec:5229 | Realtek... | RTS5229 PCI Express Card ... | 85    | rtsx_pci   | 3908342BCB |
| 10ec:522a | 17aa:2233 | Realtek... | RTS522A PCI Express Card ... | 85    | rtsx_pci   | 9EF824D802 |
| 10ec:5287 | 1025:1264 | Realtek... | RTL8411B PCI Express Card... | 85    | rtsx_pci   | 7F70DE1771 |
| 10ec:5209 | 103c:3577 | Realtek... | RTS5209 PCI Express Card ... | 83    | rtsx_pci   | 8E3CEB5DB9 |
| 10ec:5227 | 103c:2216 | Realtek... | RTS5227 PCI Express Card ... | 83    | rtsx_pci   | FFB40F821B |
| 10ec:5260 | 1028:097d | Realtek... | RTS5260 PCI Express Card ... | 82    | rtsx_pci   | 994B96D25D |
| 10ec:5287 | 1025:1295 | Realtek... | RTL8411B PCI Express Card... | 80    | rtsx_pci   | 06114B7EB7 |
| 10ec:522a | 1043:202f | Realtek... | RTS522A PCI Express Card ... | 79    | rtsx_pci   | 4F64B2AEFF |
| 10ec:5287 | 1025:1192 | Realtek... | RTL8411B PCI Express Card... | 79    | rtsx_pci   | F5F4E2457B |
| 10ec:5227 | 103c:1993 | Realtek... | RTS5227 PCI Express Card ... | 73    | rtsx_pci   | 170DD8B241 |
| 10ec:5229 | 10cf:176b | Realtek... | RTS5229 PCI Express Card ... | 71    | rtsx_pci   | 4639F065C8 |
| 10ec:525a | 1028:081c | Realtek... | RTS525A PCI Express Card ... | 69    | rtsx_pci   | ADB96FACBB |
| 10ec:5229 | 1179:f91b | Realtek... | RTS5229 PCI Express Card ... | 67    | rtsx_pci   | F1C33CDDC6 |
| 10ec:5227 | 10ec:5227 | Realtek... | RTS5227 PCI Express Card ... | 66    | rtsx_pci   | 5D323AF087 |
| 10ec:525a | 1028:06de | Realtek... | RTS525A PCI Express Card ... | 66    | rtsx_pci   | 08D4C126FA |
| 10ec:5287 | 10ec:5287 | Realtek... | RTL8411B PCI Express Card... | 66    | rtsx_pci   | 9EC292C9D9 |
| 10ec:5209 | 104d:90b8 | Realtek... | RTS5209 PCI Express Card ... | 65    | rtsx_pci   | 1D79ED8874 |
| 10ec:5287 | 1025:118a | Realtek... | RTL8411B PCI Express Card... | 65    | rtsx_pci   | E4762B54F7 |
| 10ec:522a | 17aa:2279 | Realtek... | RTS522A PCI Express Card ... | 63    | rtsx_pci   | F8024B89D4 |
| 10ec:5229 | 1179:f920 | Realtek... | RTS5229 PCI Express Card ... | 62    | rtsx_pci   | B751D415AD |
| 10ec:5249 | 17aa:3801 | Realtek... | RTS5249 PCI Express Card ... | 62    | rtsx_pci   | 43ADB60059 |
| 10ec:525a | 1028:075b | Realtek... | RTS525A PCI Express Card ... | 62    | rtsx_pci   | 8BB0307157 |
| 10ec:5209 | 104d:90ab | Realtek... | RTS5209 PCI Express Card ... | 61    | rtsx_pci   | ACF29B49FD |
| 10ec:5229 | 103c:188b | Realtek... | RTS5229 PCI Express Card ... | 61    | rtsx_pci   | 65EC913842 |
| 10ec:5260 | 1028:0991 | Realtek... | RTS5260 PCI Express Card ... | 60    | rtsx_pci   | 22BC284F45 |
| 10ec:5229 | 1179:ff1e | Realtek... | RTS5229 PCI Express Card ... | 59    | rtsx_pci   | FE77011ED7 |
| 10ec:525a | 1028:06dc | Realtek... | RTS525A PCI Express Card ... | 59    | rtsx_pci   | 69A251CC1F |
| 10ec:5229 | 103c:2213 | Realtek... | RTS5229 PCI Express Card ... | 57    | rtsx_pci   | 8D9A889ED5 |
| 10ec:5289 | 1043:1587 | Realtek... | RTL8411 PCI Express Card ... | 57    | rtsx_pci   | 1A44FC7E8F |
| 1aea:6625 | 103c:8478 | Alcor M... | AU6625 PCI-E Flash card r... | 56    | alcor_pci  | 362E1D3B99 |
| 10ec:522a | 17aa:5053 | Realtek... | RTS522A PCI Express Card ... | 55    | rtsx_pci   | 4DBC231901 |
| 10ec:525a | 17aa:222e | Realtek... | RTS525A PCI Express Card ... | 54    | rtsx_pci   | 0F1A1FEEFE |
| 10ec:5229 | 103c:1818 | Realtek... | RTS5229 PCI Express Card ... | 52    | rtsx_pci   | 31FF7DD229 |
| 10ec:5229 | 103c:183e | Realtek... | RTS5229 PCI Express Card ... | 52    | rtsx_pci   | 5EBA384ACD |
| 10ec:5229 | 103c:184a | Realtek... | RTS5229 PCI Express Card ... | 52    | rtsx_pci   | E75DC5DCFB |
| 10ec:522a | 103c:8730 | Realtek... | RTS522A PCI Express Card ... | 52    | rtsx_pci   | 1719B2DC9D |
| 10ec:5229 | 1179:f840 | Realtek... | RTS5229 PCI Express Card ... | 50    | rtsx_pci   | A6F33AA565 |
| 10ec:525a | 1028:0906 | Realtek... | RTS525A PCI Express Card ... | 49    | rtsx_pci   | E549029931 |
| 10ec:5209 | 1025:0590 | Realtek... | RTS5209 PCI Express Card ... | 48    | rtsx_pci   | 50B9A36D40 |
| 10ec:5229 | 103c:1858 | Realtek... | RTS5229 PCI Express Card ... | 48    | rtsx_pci   | 22E5D1948A |
| 10ec:525a | 1028:087d | Realtek... | RTS525A PCI Express Card ... | 48    | rtsx_pci   | 7F78C88EA8 |
| 10ec:5289 | 1043:1457 | Realtek... | RTL8411 PCI Express Card ... | 48    | rtsx_pci   | 5163F83320 |
| 10ec:5209 | 103c:1670 | Realtek... | RTS5209 PCI Express Card ... | 47    | rtsx_pci   | 4C2E2B745C |
| 10ec:5229 | 17aa:3800 | Realtek... | RTS5229 PCI Express Card ... | 47    | rtsx_pci   | 07D05077AF |
| 10ec:525a | 1028:096d | Realtek... | RTS525A PCI Express Card ... | 47    | rtsx_pci   | B0CD53DB27 |
| 10ec:5287 | 1025:108f | Realtek... | RTL8411B PCI Express Card... | 47    | rtsx_pci   | 9B5832381A |
| 10ec:5227 | 1179:0001 | Realtek... | RTS5227 PCI Express Card ... | 46    | rtsx_pci   | ED1722174A |
| 10ec:522a | 103c:837d | Realtek... | RTS522A PCI Express Card ... | 46    | rtsx_pci   | 9347A8D008 |
| 10ec:5287 | 1025:1259 | Realtek... | RTL8411B PCI Express Card... | 46    | rtsx_pci   | 3D5D3DDF84 |
| 10ec:5229 | 17aa:5000 | Realtek... | RTS5229 PCI Express Card ... | 44    | rtsx_pci   | 5837EADC8B |
| 10ec:5209 | 104d:907b | Realtek... | RTS5209 PCI Express Card ... | 43    | rtsx_pci   | BE4DB20B0E |
| 10ec:5227 | 17aa:5028 | Realtek... | RTS5227 PCI Express Card ... | 43    | rtsx_pci   | 5F6C98D219 |
| 10ec:5229 | 103c:21f7 | Realtek... | RTS5229 PCI Express Card ... | 42    | rtsx_pci   | AB5E53C9ED |
| 10ec:522a | 17aa:5072 | Realtek... | RTS522A PCI Express Card ... | 42    | rtsx_pci   | C2A180845C |
| 10ec:5289 | 1025:0724 | Realtek... | RTL8411 PCI Express Card ... | 42    | rtsx_pci   | 7302DC6BE1 |
| 10ec:5227 | 10cf:187f | Realtek... | RTS5227 PCI Express Card ... | 41    | rtsx_pci   | A0197C30DB |
| 10ec:525a | 1028:0704 | Realtek... | RTS525A PCI Express Card ... | 41    | rtsx_pci   | 1F26867986 |
| 10ec:5209 | 1025:0781 | Realtek... | RTS5209 PCI Express Card ... | 40    | rtsx_pci   | 10E7FFC71D |
| 10ec:5209 | 103c:3567 | Realtek... | RTS5209 PCI Express Card ... | 40    | rtsx_pci   | 0585DD7016 |
| 10ec:522a | 103c:8101 | Realtek... | RTS522A PCI Express Card ... | 40    | rtsx_pci   | 1069B24865 |
| 10ec:525a | 1028:07a7 | Realtek... | RTS525A PCI Express Card ... | 40    | rtsx_pci   | 3ED90A1781 |
| 10ec:525a | 1028:08e1 | Realtek... | RTS525A PCI Express Card ... | 40    | rtsx_pci   | 2932112DCA |
| 10ec:525a | 1028:06e4 | Realtek... | RTS525A PCI Express Card ... | 39    | rtsx_pci   | 32EC7FD885 |
| 10ec:525a | 17aa:224f | Realtek... | RTS525A PCI Express Card ... | 39    | rtsx_pci   | 2EAC1BFC4F |
| 10ec:522a | 17aa:3852 | Realtek... | RTS522A PCI Express Card ... | 38    | rtsx_pci   | C74557D180 |
| 10ec:522a | 17aa:504a | Realtek... | RTS522A PCI Express Card ... | 38    | rtsx_pci   | 2929E779AD |
| 10ec:522a | 17aa:5124 | Realtek... | RTS522A PCI Express Card ... | 38    | rtsx_pci   | 52BA950565 |
| 10ec:5260 | 1028:098f | Realtek... | RTS5260 PCI Express Card ... | 38    | rtsx_pci   | 5E25D50915 |
| 10ec:5227 | 103c:1991 | Realtek... | RTS5227 PCI Express Card ... | 37    | rtsx_pci   | E2559AC29A |
| 10ec:5229 | 103c:1885 | Realtek... | RTS5229 PCI Express Card ... | 37    | rtsx_pci   | 60D72BDCE7 |
| 10ec:525a | 1028:06df | Realtek... | RTS525A PCI Express Card ... | 37    | rtsx_pci   | D926705B17 |
| 10ec:525a | 1028:08b8 | Realtek... | RTS525A PCI Express Card ... | 37    | rtsx_pci   | 6A14ED2D5E |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0aa3 | 10de:cb79 | Nvidia     | MCP79 Co-processor           | 173   | nvidia     | 25B2F96576 |
| 10de:0d7a | 10de:cb89 | Nvidia     | MCP89 Co-Processor           | 81    |            | 80E0B6AF9E |
| 10de:0753 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] Co-... | 59    |            | B9B0C35DB8 |
| 10de:0543 | 103c:30cf | Nvidia     | MCP67 Co-processor           | 33    |            | 896E1BC2A0 |
| 10de:0543 | 1025:0126 | Nvidia     | MCP67 Co-processor           | 31    |            | AA6D721BF2 |
| 10de:0aa3 | 1043:1cf7 | Nvidia     | MCP79 Co-processor           | 27    | nvidia     | 75903BAEAC |
| 10de:0aa3 | 1043:1fa7 | Nvidia     | MCP79 Co-processor           | 24    | nvidia     | B0BCC6C31C |
| 10de:0271 | 103c:30b7 | Nvidia     | MCP51 PMU                    | 19    |            | C28788427E |
| 10de:0aa3 | 1043:1d17 | Nvidia     | MCP79 Co-processor           | 18    | nvidia     | F1573DB462 |
| 10de:0447 | 103c:30cf | Nvidia     | MCP65 SMU                    | 13    |            | 8774B51F01 |
| 10de:0543 | 1043:16a7 | Nvidia     | MCP67 Co-processor           | 12    |            | 414786C3D5 |
| 10de:0aa3 | 1043:8402 | Nvidia     | MCP79 Co-processor           | 12    | nvidia     | 1FF8ED5A66 |
| 10de:0271 | 1025:0112 | Nvidia     | MCP51 PMU                    | 10    |            | 56639ACA29 |
| 10de:0aa3 | 103c:3651 | Nvidia     | MCP79 Co-processor           | 10    | nvidia     | 50468DF6ED |
| 10de:0aa3 | 1462:1012 | Nvidia     | MCP79 Co-processor           | 8     | nvidia     | 76D2D77034 |
| 10de:0aa3 | 1025:0160 | Nvidia     | MCP79 Co-processor           | 7     | nvidia     | 9BBF3BEFAB |
| 10de:0271 | 103c:30b5 | Nvidia     | MCP51 PMU                    | 6     |            | 31A42ED2B6 |
| 10de:0271 | 1462:3fc1 | Nvidia     | MCP51 PMU                    | 6     |            | 8DB6FA7A1C |
| 10de:0543 | 103c:30d6 | Nvidia     | MCP67 Co-processor           | 6     |            | D6DADC467D |
| 10de:0543 | 103c:30ea | Nvidia     | MCP67 Co-processor           | 6     |            | 1CEE50E485 |
| 10de:0271 | 103c:30bf | Nvidia     | MCP51 PMU                    | 5     |            | BAD7484C1A |
| 10de:0753 | 1025:014d | Nvidia     | MCP78S [GeForce 8200] Co-... | 5     |            | 09694E2816 |
| 10de:0753 | 1462:6720 | Nvidia     | MCP78S [GeForce 8200] Co-... | 5     |            | 46430A6E00 |
| 10de:0aa3 | 1071:9070 | Nvidia     | MCP79 Co-processor           | 5     | nvidia     | ABE849C090 |
| 10de:0271 | 1043:1367 | Nvidia     | MCP51 PMU                    | 4     |            | 7BD5FA25B3 |
| 10de:0aa3 | 1028:0271 | Nvidia     | MCP79 Co-processor           | 4     |            | E54DAEA8F9 |
| 10de:0aa3 | 1043:1fd7 | Nvidia     | MCP79 Co-processor           | 4     |            | AE8948A236 |
| 10de:0271 | 103c:30e5 | Nvidia     | MCP51 PMU                    | 3     |            | A070611109 |
| 10de:0271 | 1462:373d | Nvidia     | MCP51 PMU                    | 3     |            | 154009C211 |
| 10de:0271 | 1734:110c | Nvidia     | MCP51 PMU                    | 3     |            | 79DCA1A7CC |
| 10de:0aa3 | 1043:1a87 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 03675A2262 |
| 10de:0aa3 | 1734:1151 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | E6A298846B |
| 10de:0aa3 | 17aa:38da | Nvidia     | MCP79 Co-processor           | 3     |            | D408DE645F |
| 10de:0271 | 1734:10d4 | Nvidia     | MCP51 PMU                    | 2     |            | 00863FCEA8 |
| 10de:0543 | 1025:0127 | Nvidia     | MCP67 Co-processor           | 2     |            | 0D272A5910 |
| 10de:0753 | 107b:0173 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 23D6F05DAF |
| 10de:0aa3 | 1462:1019 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | 2054B3A4CC |
| 10de:0aa3 | 1b0a:4203 | Nvidia     | MCP79 Co-processor           | 2     |            | 3D1668F30A |
| 10de:0271 | 1043:1322 | Nvidia     | MCP51 PMU                    | 1     |            | 71FE8FB963 |
| 10de:0271 | 1043:14b7 | Nvidia     | MCP51 PMU                    | 1     |            | AFE46A35A8 |
| 10de:0271 | 107b:0317 | Nvidia     | MCP51 PMU                    | 1     |            | 1178CC8597 |
| 10de:0271 | 1734:10d3 | Nvidia     | MCP51 PMU                    | 1     |            | 6172D9B266 |
| 10de:0271 | 17c0:4076 | Nvidia     | MCP51 PMU                    | 1     |            | E8BA4FAFA0 |
| 10de:0543 | 1043:1697 | Nvidia     | MCP67 Co-processor           | 1     |            | C3296D5344 |
| 10de:0543 | 1631:c106 | Nvidia     | MCP67 Co-processor           | 1     |            | E997783E39 |
| 10de:0753 | 1025:014a | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | F63FFEFC64 |
| 10de:0753 | 1462:6520 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 12132D4EBD |
| 10de:0aa3 | 1071:9072 | Nvidia     | MCP79 Co-processor           | 1     | nvidia     | 109599A6F6 |
| 10de:0aa3 | 1071:9515 | Nvidia     | MCP79 Co-processor           | 1     | nvidia     | E028F277D4 |
| 10de:0aa3 | 1462:71f0 | Nvidia     | MCP79 Co-processor           | 1     | nvidia     | FB8A0F79C4 |
| 10de:0aa3 | 1b7d:0040 | Nvidia     | MCP79 Co-processor           | 1     |            | 053ACCA095 |
| 8086:19e2 | 8086:19e2 | Intel      | Atom Processor C3000 Seri... | 1     |            | 50B6A72C0C |
| 8086:2250 | 8086:2500 | Intel      | Xeon Phi coprocessor 5100... | 1     |            | 6027A620DD |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e3a | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 567   | mei_me     | 16EBDC4388 |
| 8086:3b64 | 17aa:215f | Intel      | 5 Series/3400 Series Chip... | 351   | mei_me     | 570863FD8C |
| 8086:1c3a | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 318   | mei_me     | D1D57448C4 |
| 8086:9c3a | 17aa:3978 | Intel      | 8 Series HECI #0             | 309   | mei_me     | 3CDDE1061C |
| 8086:9cba | 8086:7270 | Intel      | Wildcat Point-LP MEI Cont... | 276   | mei_me     | 5BE083EDAB |
| 8086:2a44 | 17aa:20e6 | Intel      | Mobile 4 Series Chipset M... | 264   | mei_me     | 9A7BE426F5 |
| 8086:1c3a | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 214   | mei_me     | ECC4515014 |
| 8086:1e3a | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 205   | mei_me     | 783D081B5A |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 200   | mei_me     | 403E735C43 |
| 8086:3b64 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 188   | mei_me     | E3FC4E0622 |
| 8086:1e3a | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 186   | mei_me     | C9D8EFC9B9 |
| 8086:1c3a | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 171   | mei_me     | A75FFD5203 |
| 8086:8c3a | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 166   | mei_me     | 60FA5FF04C |
| 8086:1e3a | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 165   | mei_me     | A120083D3C |
| 8086:1c3a | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 163   | mei_me     | B96D5D5FDC |
| 8086:1e3a | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 163   | mei_me     | 82E60126C9 |
| 8086:1c3a | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 160   | mei_me     | 4C3C43DAAA |
| 8086:1c3a | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 158   | mei_me     | B66EB36016 |
| 8086:319a | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 158   | mei_me     | F40D5FD5A7 |
| 8086:a328 | 1025:1331 | Intel      | Cannon Lake PCH Serial IO... | 157   | intel_lpss | BC9DC107D1 |
| 8086:a360 | 1025:1331 | Intel      | Cannon Lake PCH HECI Cont... | 157   | mei_me     | BC9DC107D1 |
| 8086:9d3a | 17aa:386e | Intel      | Sunrise Point-LP CSME HEC... | 147   | mei_me     | F86520F5A7 |
| 8086:319a | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 143   | mei_me     | 5C95C74B6C |
| 8086:a360 | 1028:0905 | Intel      | Cannon Lake PCH HECI Cont... | 142   | mei_me     | 58E43F0514 |
| 8086:1c3a | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 141   | mei_me     | 0A8E84DFAD |
| 8086:1e3a | 1028:0534 | Intel      | 7 Series/C216 Chipset Fam... | 141   | mei_me     | FA4D12994D |
| 8086:02e0 | 17aa:5079 | Intel      | Comet Lake Management Eng... | 138   | mei_me     | A35AAAEB6D |
| 8086:3b64 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 138   | mei_me     | A18FB33A6F |
| 8086:1e3a | 1043:124d | Intel      | 7 Series/C216 Chipset Fam... | 136   | mei_me     | 3498166FA2 |
| 8086:3b64 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 136   | mei_me     | 77E0B6A916 |
| 8086:1c3a | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 132   | mei_me     | 532A1D3D01 |
| 8086:3b64 | 17aa:38a5 | Intel      | 5 Series/3400 Series Chip... | 131   | mei_me     | A31437072C |
| 8086:1e3a | 17aa:21f6 | Intel      | 7 Series/C216 Chipset Fam... | 130   | mei_me     | 69A252CCD6 |
| 8086:9c3a | 17aa:220c | Intel      | 8 Series HECI #0             | 130   | mei_me     | 415CC7FE56 |
| 8086:1e3a | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 127   | mei_me     | D74C10F41F |
| 8086:9de0 | 17aa:2279 | Intel      | Cannon Point-LP MEI Contr... | 127   | mei_me     | A01E524A66 |
| 8086:9d3a | 103c:8079 | Intel      | Sunrise Point-LP CSME HEC... | 121   | mei_me     | 436E9BF227 |
| 8086:9d3a | 1025:1193 | Intel      | Sunrise Point-LP CSME HEC... | 119   | mei_me     | 43BFEF3BCD |
| 8086:1e3a | 10cf:16ea | Intel      | 7 Series/C216 Chipset Fam... | 117   | mei_me     | 4639F065C8 |
| 8086:8c3a | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 117   | mei_me     | 36F407C3AA |
| 8086:1c3a | 103c:161c | Intel      | 6 Series/C200 Series Chip... | 114   | mei_me     | B6AC4539D1 |
| 8086:a360 | 1028:087c | Intel      | Cannon Lake PCH HECI Cont... | 114   | mei_me     | 0FA8C3ED0C |
| 8086:1c3a | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 113   | mei_me     | FC712846D9 |
| 8086:9c3a | 103c:198f | Intel      | 8 Series HECI #0             | 113   | mei_me     | CECD552E89 |
| 8086:1e3a | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 112   | mei_me     | 779684E41D |
| 8086:9cba | 17aa:5034 | Intel      | Wildcat Point-LP MEI Cont... | 111   | mei_me     | CEA37DD548 |
| 8086:9d3a | 1028:0810 | Intel      | Sunrise Point-LP CSME HEC... | 110   | mei_me     | C01FA4B013 |
| 8086:1e3a | 1179:fb31 | Intel      | 7 Series/C216 Chipset Fam... | 109   | mei_me     | E9FAA1A00B |
| 8086:9d3a | 17aa:225d | Intel      | Sunrise Point-LP CSME HEC... | 109   | mei_me     | FEB7F2A285 |
| 8086:1e3a | 103c:179b | Intel      | 7 Series/C216 Chipset Fam... | 108   | mei_me     | 1B2FBCDFA0 |
| 8086:9c3a | 1025:0866 | Intel      | 8 Series HECI #0             | 108   | mei_me     | 11EBF2008B |
| 8086:9de0 | 103c:8549 | Intel      | Cannon Point-LP MEI Contr... | 108   | mei_me     | A814284F0B |
| 8086:1c3a | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 107   | mei_me     | 4104E265EA |
| 8086:9c3a | 1028:0651 | Intel      | 8 Series HECI #0             | 106   | mei_me     | 0862DC626B |
| 8086:1c3a | 104d:908b | Intel      | 6 Series/C200 Series Chip... | 104   | mei_me     | 11EF4D4BAF |
| 8086:1c3a | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 103   | mei_me     | 89DF37A291 |
| 8086:1e3a | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 101   | mei_me     | 8BC152AA27 |
| 8086:1c3a | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 100   | mei_me     | 966E771791 |
| 8086:9d3a | 1028:07e6 | Intel      | Sunrise Point-LP CSME HEC... | 99    | mei_me     | 5A56854746 |
| 8086:9d3a | 17aa:3801 | Intel      | Sunrise Point-LP CSME HEC... | 99    | mei_me     | 8272A05168 |
| 8086:a13a | 1028:07be | Intel      | 100 Series/C230 Series Ch... | 99    | mei_me     | 69938C221E |
| 8086:1e3a | 1043:1477 | Intel      | 7 Series/C216 Chipset Fam... | 98    | mei_me     | 1D158DC1F0 |
| 8086:9c3a | 1025:0775 | Intel      | 8 Series HECI #0             | 95    | mei_me     | 0385B295A7 |
| 8086:9d3a |           | Intel      | Sunrise Point-LP CSME HEC... | 95    | mei_me     | CBB0DC67DE |
| 8086:9d3a | 1043:12d1 | Intel      | Sunrise Point-LP CSME HEC... | 95    | mei_me     | 703D0F2090 |
| 8086:1e3a | 1043:14c7 | Intel      | 7 Series/C216 Chipset Fam... | 94    | mei_me     | BC26A9B439 |
| 8086:9de0 | 1028:08af | Intel      | Cannon Point-LP MEI Contr... | 92    | mei_me     | 52DEA66C52 |
| 8086:02e0 | 1028:0962 | Intel      | Comet Lake Management Eng... | 91    | mei_me     | 8956FEE2F3 |
| 8086:9d3a | 1028:078b | Intel      | Sunrise Point-LP CSME HEC... | 91    | mei_me     | 35BCBD121B |
| 8086:9d3a | 17aa:3843 | Intel      | Sunrise Point-LP CSME HEC... | 89    | mei_me     | 4EB6B00CAC |
| 8086:9de0 | 17aa:5072 | Intel      | Cannon Point-LP MEI Contr... | 89    | mei_me     | 3678E02E46 |
| 8086:9c3a | 17aa:2214 | Intel      | 8 Series HECI #0             | 88    | mei_me     | F802ABEF07 |
| 8086:9cba | 17aa:2226 | Intel      | Wildcat Point-LP MEI Cont... | 88    | mei_me     | 22A87CB141 |
| 8086:5a9a | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 86    | mei_me     | 64BC2367EF |
| 8086:9d3a | 17aa:225c | Intel      | Sunrise Point-LP CSME HEC... | 86    | mei_me     | 2B4A1A20D9 |
| 8086:9d3a | 17aa:5068 | Intel      | Sunrise Point-LP CSME HEC... | 86    | mei_me     | 2A70ED5588 |
| 8086:9de0 | 17aa:2292 | Intel      | Cannon Point-LP MEI Contr... | 86    | mei_me     | 26C62915E0 |
| 8086:a328 | 1025:1264 | Intel      | Cannon Lake PCH Serial IO... | 86    | intel_lpss | 7F70DE1771 |
| 8086:a360 | 1025:1264 | Intel      | Cannon Lake PCH HECI Cont... | 86    | mei_me     | 7F70DE1771 |
| 8086:1e3a | 103c:1854 | Intel      | 7 Series/C216 Chipset Fam... | 85    | mei_me     | B0ED67249E |
| 8086:9cba | 103c:2216 | Intel      | Wildcat Point-LP MEI Cont... | 85    | mei_me     | FFB40F821B |
| 8086:06a8 | 1028:097d | Intel      | Comet Lake PCH Serial IO ... | 84    | intel_l... | 994B96D25D |
| 8086:06e0 | 1028:097d | Intel      | Comet Lake HECI Controller   | 84    | mei_me     | 994B96D25D |
| 8086:1e3a | 144d:c652 | Intel      | 7 Series/C216 Chipset Fam... | 82    | mei_me     | BCA6D30092 |
| 8086:3b64 | 10cf:152b | Intel      | 5 Series/3400 Series Chip... | 82    | mei_me     | ED4E9D1A03 |
| 8086:1c3a | 1179:fc30 | Intel      | 6 Series/C200 Series Chip... | 81    | mei_me     | C70057C643 |
| 8086:9d3a | 103c:832a | Intel      | Sunrise Point-LP CSME HEC... | 80    | mei_me     | C9FD6887D4 |
| 8086:8c3a | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 79    | mei_me     | EABB3946AD |
| 8086:9d3a | 1025:1295 | Intel      | Sunrise Point-LP CSME HEC... | 78    | mei_me     | 06114B7EB7 |
| 8086:1e3a | 1179:ff1e | Intel      | 7 Series/C216 Chipset Fam... | 77    | mei_me     | A379AB0FA6 |
| 8086:9c3a | 1028:05cb | Intel      | 8 Series HECI #0             | 77    | mei_me     | 98C988645F |
| 8086:9c3a | 8086:7270 | Intel      | 8 Series HECI #0             | 77    | mei_me     | 0C24CAF245 |
| 8086:9cba | 1025:098a | Intel      | Wildcat Point-LP MEI Cont... | 77    | mei_me     | CCE67D37AA |
| 8086:1c3a | 103c:167c | Intel      | 6 Series/C200 Series Chip... | 76    | mei_me     | 4808FF3A68 |
| 8086:9cba | 1028:062e | Intel      | Wildcat Point-LP MEI Cont... | 76    | mei_me     | 91837758AC |
| 8086:9da8 | 17aa:3807 | Intel      | Cannon Point-LP Serial IO... | 76    | intel_l... | 2DB4EBB6EF |
| 8086:9de0 | 17aa:380f | Intel      | Cannon Point-LP MEI Contr... | 76    | mei_me     | 2DB4EBB6EF |
| 8086:1e3a | 1028:0597 | Intel      | 7 Series/C216 Chipset Fam... | 75    | mei_me     | 5EBA5CDCBF |
| 8086:8c3a | 103c:1993 | Intel      | 8 Series/C220 Series Chip... | 75    | mei_me     | 170DD8B241 |
| 8086:9c3a | 1043:131d | Intel      | 8 Series HECI #0             | 75    | mei_me     | 50B1B1A6C5 |

### Digitizer pen (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a0d0 | 8086:2097 | Intel      | Digitizer Pen                | 7     |            | 4BFFB79E7C |

### Dma controller (eisa dma) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9ce0 | 8086:9ce0 | Intel      | Wildcat Point-LP Serial I... | 265   | dw_dmac... | 5BE083EDAB |
| 8086:9c60 |           | Intel      | 8 Series Low Power Sub-Sy... | 33    | dw_dmac... | 66F91918DC |
| 8086:2286 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 12    | dw_dmac... | 44472E729C |
| 8086:22c0 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 12    | dw_dmac... | 44472E729C |
| 8086:9c60 | 1025:0a11 | Intel      | 8 Series Low Power Sub-Sy... | 7     | dw_dmac... | 9779F3CABD |
| 8086:9c60 | 103c:21ed | Intel      | 8 Series Low Power Sub-Sy... | 5     | dw_dmac... | 9BB0BF9AC8 |
| 8086:0f40 |           | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | 5900E800AA |
| 8086:0f40 | 1025:0939 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | C431BDD246 |
| 8086:0f40 | 103c:8023 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | 49E4112B11 |
| 8086:0f40 | 1170:9991 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | B5C89FA6C1 |
| 8086:0f40 | 17aa:3908 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | 0128495D83 |
| 8086:0f40 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | 0994A3EEB3 |
| 8086:2286 | 1025:106c | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 09F6D20FE1 |
| 8086:2286 | 1025:1151 | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 7B7DB12037 |
| 8086:22c0 | 1025:106c | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 09F6D20FE1 |
| 8086:22c0 | 1025:1151 | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 7B7DB12037 |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15df | 1022:15df | AMD        | Family 17h (Models 10h-1f... | 928   | ccp        | 3F7A2585FE |
| 1022:1537 | 1022:1537 | AMD        | Kabini/Mullins PSP-Platfo... | 407   | ccp        | 65C122FE69 |
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 388   | mei_txe    | 2FBF6F153B |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 236   |            | 34F2870A95 |
| 1022:1537 | 17aa:3801 | AMD        | Kabini/Mullins PSP-Platfo... | 137   | ccp        | 0CDC6E9D84 |
| 1022:1578 | 103c:8330 | AMD        | Carrizo Platform Security... | 120   |            | 18CEA74915 |
| 8086:0f18 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 110   | mei_txe    | 1387FAB9FE |
| 8086:0f18 | 17aa:3909 | Intel      | Atom Processor Z36xxx/Z37... | 96    | mei_txe    | 184B909FC0 |
| 8086:0f18 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 94    | mei_txe    | 31AC5CDF6E |
| 1022:15df | 17aa:5081 | AMD        | Family 17h (Models 10h-1f... | 90    | ccp        | 273A5FF27D |
| 1022:1578 | 103c:84ac | AMD        | Carrizo Platform Security... | 87    |            | 3A06ECCCAA |
| 1022:15df | 19e5:3e19 | AMD        | Family 17h (Models 10h-1f... | 81    | ccp        | 1310B8ABF4 |
| 1022:1578 | 1025:1192 | AMD        | Carrizo Platform Security... | 79    |            | F5F4E2457B |
| 1022:15df | 17aa:507f | AMD        | Family 17h (Models 10h-1f... | 75    | ccp        | 8A34D739FD |
| 1022:1578 | 17aa:3810 | AMD        | Carrizo Platform Security... | 70    |            | D9D0DD7C3C |
| 1022:15df | 17aa:381f | AMD        | Family 17h (Models 10h-1f... | 66    | ccp        | 8A6E0EE275 |
| 8086:0f18 | 8086:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 65    | mei_txe    | 1A0A5790B3 |
| 1022:15df | 1025:134d | AMD        | Family 17h (Models 10h-1f... | 63    | ccp        | 6134BF279A |
| 1022:15df | 17aa:3802 | AMD        | Family 17h (Models 10h-1f... | 63    | ccp        | 497BF56CC6 |
| 1022:15df | 1025:1366 | AMD        | Family 17h (Models 10h-1f... | 61    | ccp        | BCC833AC3C |
| 1022:15df | 17aa:5124 | AMD        | Family 17h (Models 10h-1f... | 61    | ccp        | 52BA950565 |
| 8086:2298 | 1025:1012 | Intel      | Atom/Celeron/Pentium Proc... | 61    | mei_txe    | DC6378E76B |
| 8086:2298 | 1028:06ac | Intel      | Atom/Celeron/Pentium Proc... | 59    | mei_txe    | F1B660B91C |
| 8086:2298 | 103c:832c | Intel      | Atom/Celeron/Pentium Proc... | 59    | mei_txe    | 5B9D2833CC |
| 1022:15df | 103c:84ae | AMD        | Family 17h (Models 10h-1f... | 58    | ccp        | 2E3861AEF3 |
| 1022:15df | 17aa:380f | AMD        | Family 17h (Models 10h-1f... | 58    | ccp        | 3F7C00C1EF |
| 1022:15df | 17aa:3818 | AMD        | Family 17h (Models 10h-1f... | 57    | ccp        | 3CDC08297E |
| 8086:0f18 | 103c:2213 | Intel      | Atom Processor Z36xxx/Z37... | 57    | mei_txe    | 8D9A889ED5 |
| 1022:15df | 17aa:3811 | AMD        | Family 17h (Models 10h-1f... | 54    | ccp        | 8DB63E7A74 |
| 1022:1578 | 17aa:380f | AMD        | Carrizo Platform Security... | 53    |            | 0036C99447 |
| 1022:15df | 17aa:3816 | AMD        | Family 17h (Models 10h-1f... | 52    | ccp        | 88286C36E9 |
| 8086:0f18 | 1043:161d | Intel      | Atom Processor Z36xxx/Z37... | 52    | mei_txe    | 1FA3E8B296 |
| 1022:15df | 17aa:5082 | AMD        | Family 17h (Models 10h-1f... | 51    | ccp        | 037A558C7D |
| 8086:2298 | 1043:10c0 | Intel      | Atom/Celeron/Pentium Proc... | 51    | mei_txe    | 2CE3B8F43C |
| 8086:0f18 | 1297:2041 | Intel      | Atom Processor Z36xxx/Z37... | 50    | mei_txe    | 4BD1D4C963 |
| 1022:15df | 17aa:380d | AMD        | Family 17h (Models 10h-1f... | 47    | ccp        | 8C961555FE |
| 1022:15df | 17aa:3810 | AMD        | Family 17h (Models 10h-1f... | 47    | ccp        | 09ADDF2612 |
| 8086:0f18 | 17aa:3986 | Intel      | Atom Processor Z36xxx/Z37... | 47    | mei_txe    | 07D05077AF |
| 1022:15df | 1025:1259 | AMD        | Family 17h (Models 10h-1f... | 46    | ccp        | 3D5D3DDF84 |
| 8086:2298 | 17aa:3808 | Intel      | Atom/Celeron/Pentium Proc... | 46    | mei_txe    | 662ED28F07 |
| 1022:15df | 103c:8615 | AMD        | Family 17h (Models 10h-1f... | 45    | ccp        | 406FCB6975 |
| 1022:15df | 1d05:109f | AMD        | Family 17h (Models 10h-1f... | 45    | ccp        | 7242436545 |
| 8086:0f18 | 1043:14dd | Intel      | Atom Processor Z36xxx/Z37... | 45    | mei_txe    | 5CAFC52180 |
| 1022:15df | 19e5:3e18 | AMD        | Family 17h (Models 10h-1f... | 44    | ccp        | C0B80E3276 |
| 8086:0f18 | 1025:0933 | Intel      | Atom Processor Z36xxx/Z37... | 42    | mei_txe    | 98323BE6F8 |
| 8086:2298 | 103c:81f1 | Intel      | Atom/Celeron/Pentium Proc... | 42    | mei_txe    | D72905575E |
| 1022:1578 | 17aa:3815 | AMD        | Carrizo Platform Security... | 40    |            | 567F0F4A13 |
| 1022:15df | 17aa:3817 | AMD        | Family 17h (Models 10h-1f... | 40    | ccp        | 86BC5DDC56 |
| 1022:15df | 17aa:507e | AMD        | Family 17h (Models 10h-1f... | 39    | ccp        | E9A8FB1275 |
| 1022:1537 | 17aa:3808 | AMD        | Kabini/Mullins PSP-Platfo... | 38    | ccp        | A34F4E81C4 |
| 1022:15df | 103c:85ea | AMD        | Family 17h (Models 10h-1f... | 38    | ccp        | E8781DB5AB |
| 8086:0f18 | 1179:f91b | Intel      | Atom Processor Z36xxx/Z37... | 38    | mei_txe    | 0914AEED54 |
| 1022:15df | 1025:142b | AMD        | Family 17h (Models 10h-1f... | 37    | ccp        | BCE3E39F4C |
| 8086:0f18 | 1025:0936 | Intel      | Atom Processor Z36xxx/Z37... | 37    | mei_txe    | AA7DD43B73 |
| 1022:15df | 103c:84e7 | AMD        | Family 17h (Models 10h-1f... | 36    | ccp        | CF69BD4423 |
| 1022:15df | 17aa:3809 | AMD        | Family 17h (Models 10h-1f... | 36    | ccp        | 0C3651AF28 |
| 1022:1537 | 1025:104b | AMD        | Kabini/Mullins PSP-Platfo... | 34    | ccp        | C6582BBA7D |
| 1022:15df | 103c:86fd | AMD        | Family 17h (Models 10h-1f... | 34    | ccp        | 5BB4E443F9 |
| 1022:1537 | 1025:108a | AMD        | Kabini/Mullins PSP-Platfo... | 33    | ccp        | CFA7B4AF8F |
| 1022:1578 | 17aa:380c | AMD        | Carrizo Platform Security... | 33    |            | E4AA5740C5 |
| 8086:2298 | 103c:813e | Intel      | Atom/Celeron/Pentium Proc... | 33    | mei_txe    | 0A44B96544 |
| 8086:0f18 | 103c:21de | Intel      | Atom Processor Z36xxx/Z37... | 32    | mei_txe    | A9F0EC716F |
| 8086:2298 | 103c:80c5 | Intel      | Atom/Celeron/Pentium Proc... | 31    | mei_txe    | 2CF6464047 |
| 1022:1578 | 103c:8333 | AMD        | Carrizo Platform Security... | 30    |            | 57EE9BD872 |
| 1022:15df | 1025:134f | AMD        | Family 17h (Models 10h-1f... | 30    | ccp        | 5EDDDC1E2C |
| 1022:15df | 1025:1461 | AMD        | Family 17h (Models 10h-1f... | 30    | ccp        | 264BADF289 |
| 8086:0f18 | 1043:15bd | Intel      | Atom Processor Z36xxx/Z37... | 30    | mei_txe    | 7373CE3DBF |
| 1022:15df | 103c:85b3 | AMD        | Family 17h (Models 10h-1f... | 29    | ccp        | AE1811A242 |
| 8086:2298 | 103c:82bd | Intel      | Atom/Celeron/Pentium Proc... | 29    | mei_txe    | 09D2CE45B4 |
| 1022:1578 | 17aa:380b | AMD        | Carrizo Platform Security... | 28    |            | 85036968BB |
| 1022:15df | 1025:125c | AMD        | Family 17h (Models 10h-1f... | 28    | ccp        | 2FF605BDB0 |
| 8086:2298 | 1043:12e0 | Intel      | Atom/Celeron/Pentium Proc... | 28    | mei_txe    | ED8BB15F60 |
| 8086:2298 | 1043:191d | Intel      | Atom/Celeron/Pentium Proc... | 28    | mei_txe    | 9B5B69452D |
| 1022:1578 | 103c:8331 | AMD        | Carrizo Platform Security... | 27    |            | F60949A3CC |
| 1022:15df | 17aa:5125 | AMD        | Family 17h (Models 10h-1f... | 27    | ccp        | 8E00E1F239 |
| 1022:15df | 1025:1456 | AMD        | Family 17h (Models 10h-1f... | 26    | ccp        | 09F6196E70 |
| 1022:15df | 103c:887a | AMD        | Family 17h (Models 10h-1f... | 26    | ccp        | 2BA5AE42BB |
| 8086:0f18 | 1043:14ed | Intel      | Atom Processor Z36xxx/Z37... | 26    | mei_txe    | EA1ADE9E18 |
| 8086:2298 | 1297:2063 | Intel      | Atom/Celeron/Pentium Proc... | 26    | mei_txe    | 0D1AB84E09 |
| 1022:15df | 19e5:3e06 | AMD        | Family 17h (Models 10h-1f... | 25    | ccp        | 9BEA49D841 |
| 1022:15df | 1025:1455 | AMD        | Family 17h (Models 10h-1f... | 24    | ccp        | F581CF8319 |
| 1022:15df | 103c:85e0 | AMD        | Family 17h (Models 10h-1f... | 24    | ccp        | 1A23A6605B |
| 1022:15df | 17aa:381c | AMD        | Family 17h (Models 10h-1f... | 24    | ccp        | 214D892F21 |
| 8086:0f18 | 1025:0905 | Intel      | Atom Processor Z36xxx/Z37... | 24    | mei_txe    | 7191B6C18E |
| 1022:1578 | 1025:109f | AMD        | Carrizo Platform Security... | 23    |            | 70037BDDCB |
| 1022:1578 | 103c:81f9 | AMD        | Carrizo Platform Security... | 23    |            | F8A1A59318 |
| 1022:15df | 17aa:382a | AMD        | Family 17h (Models 10h-1f... | 23    | ccp        | C7A45F22C5 |
| 1022:15df | 1e83:3e33 | AMD        | Family 17h (Models 10h-1f... | 23    | ccp        | 1E059DB869 |
| 8086:0f18 | 17aa:2224 | Intel      | Atom Processor Z36xxx/Z37... | 23    | mei_txe    | 7F92DCE67E |
| 8086:2298 | 1043:10b0 | Intel      | Atom/Celeron/Pentium Proc... | 23    | mei_txe    | D54A711F31 |
| 1022:15df | 19e5:3e14 | AMD        | Family 17h (Models 10h-1f... | 22    | ccp        | C62BB4ADC9 |
| 1022:15df | 1d05:1100 | AMD        | Family 17h (Models 10h-1f... | 22    | ccp        | 97B2732F29 |
| 8086:2298 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 22    | mei_txe    | 3FF4BE2B55 |
| 8086:2298 | 1028:074d | Intel      | Atom/Celeron/Pentium Proc... | 22    | mei_txe    | DB073988D6 |
| 8086:2298 | 1043:1d5d | Intel      | Atom/Celeron/Pentium Proc... | 22    | mei_txe    | 7034E6708D |
| 8086:0f18 | 103c:2209 | Intel      | Atom Processor Z36xxx/Z37... | 21    | mei_txe    | 6670BBA1D8 |
| 1022:1537 | 103c:82f6 | AMD        | Kabini/Mullins PSP-Platfo... | 19    | ccp        | AB87221BF7 |
| 1022:15df | 1043:1602 | AMD        | Family 17h (Models 10h-1f... | 19    | ccp        | CC4C888046 |
| 1022:15df | 17aa:5097 | AMD        | Family 17h (Models 10h-1f... | 19    | ccp        | 8D45D9544E |
| 8086:0f18 | 1025:0845 | Intel      | Atom Processor Z36xxx/Z37... | 19    | mei_txe    | 5CCB33482F |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 11c1:5901 | 11c1:5900 | LSI        | FW643 [TrueFire] PCIe 139... | 471   | firewir... | 6E17FB6EA4 |
| 1180:0832 | 17aa:20c7 | Ricoh      | R5C832 IEEE 1394 Controller  | 294   | firewir... | 9A7BE426F5 |
| 1180:e832 | 17aa:2136 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 175   | firewir... | 8B21B7CFFE |
| 1180:e832 | 1028:040a | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 138   | firewir... | BA51FC9216 |
| 104c:803a | 1025:011f | Texas I... | PCIxx12 OHCI Compliant IE... | 135   | firewir... | 8592F1650F |
| 1180:0832 | 1028:0233 | Ricoh      | R5C832 IEEE 1394 Controller  | 124   | firewir... | 6B7EF9CAD5 |
| 11c1:5811 | 11c1:5811 | LSI        | FW322/323 [TrueFire] 1394... | 120   | firewir... | 0346BC764A |
| 197b:2380 | 103c:161c | JMicron... | IEEE 1394 Host Controller    | 112   | firewir... | B6AC4539D1 |
| 104c:803a | 1179:ff00 | Texas I... | PCIxx12 OHCI Compliant IE... | 103   | firewir... | 1BF61C0698 |
| 197b:2380 | 103c:179b | JMicron... | IEEE 1394 Host Controller    | 101   | firewir... | 1B2FBCDFA0 |
| 1180:e832 | 17aa:21cf | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 97    | firewir... | 4104E265EA |
| 1217:00f7 | 1028:01f9 | O2 Micro   | Firewire (IEEE 1394)         | 92    | firewir... | 6DBCD5A1C8 |
| 1180:0832 | 1028:022f | Ricoh      | R5C832 IEEE 1394 Controller  | 83    | firewir... | ED2467DC52 |
| 1180:e832 | 17aa:21f6 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 79    | firewir... | 69A252CCD6 |
| 1180:0832 | 103c:30cc | Ricoh      | R5C832 IEEE 1394 Controller  | 73    | firewir... | DD3C7EF3E7 |
| 1180:0832 | 103c:172a | Ricoh      | R5C832 IEEE 1394 Controller  | 65    | firewir... | F527983CC9 |
| 1217:00f7 | 1179:ff50 | O2 Micro   | Firewire (IEEE 1394)         | 60    | firewir... | ABCF2EEE75 |
| 1217:13f7 | 1028:0494 | O2 Micro   | 1394 OHCI Compliant Host ... | 60    | firewir... | B84EF4472B |
| 1180:e832 | 17aa:21ce | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 54    | firewir... | 002840EA37 |
| 1180:e832 | 1028:040b | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 53    | firewir... | 2AB208B5CD |
| 1217:00f7 | 1217:00f7 | O2 Micro   | Firewire (IEEE 1394)         | 53    | firewir... | F1770353A3 |
| 197b:2380 | 103c:3628 | JMicron... | IEEE 1394 Host Controller    | 49    | firewir... | 2992DD1DF0 |
| 1180:0832 | 1028:024f | Ricoh      | R5C832 IEEE 1394 Controller  | 48    | firewir... | E475348B1E |
| 1180:0832 | 1025:011e | Ricoh      | R5C832 IEEE 1394 Controller  | 47    | firewir... | 6472272BF7 |
| 1180:0832 | 103c:7008 | Ricoh      | R5C832 IEEE 1394 Controller  | 47    | firewir... | F31AC36B11 |
| 1180:0832 | 103c:30c0 | Ricoh      | R5C832 IEEE 1394 Controller  | 44    | firewir... | 51AB06C26F |
| 1180:0832 | 103c:30cf | Ricoh      | R5C832 IEEE 1394 Controller  | 44    | firewir... | 8774B51F01 |
| 197b:2380 | 103c:1618 | JMicron... | IEEE 1394 Host Controller    | 43    | firewir... | 48828AD0D3 |
| 1217:13f7 | 1028:049a | O2 Micro   | 1394 OHCI Compliant Host ... | 42    | firewir... | 3405536413 |
| 1180:0832 | 1025:0121 | Ricoh      | R5C832 IEEE 1394 Controller  | 41    | firewir... | D7C90EB05B |
| 1180:0832 | 104d:9035 | Ricoh      | R5C832 IEEE 1394 Controller  | 41    | firewir... | DBFD29F616 |
| 1180:e832 | 103c:146d | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 41    | firewir... | 518E694864 |
| 1180:0832 | 103c:1521 | Ricoh      | R5C832 IEEE 1394 Controller  | 40    | firewir... | 40F54639E6 |
| 11c1:5811 | 103c:30dd | LSI        | FW322/323 [TrueFire] 1394... | 40    | firewir... | 13444FC399 |
| 104c:803a | 1179:ff10 | Texas I... | PCIxx12 OHCI Compliant IE... | 38    | firewir... | 68AC15EEDA |
| 104c:803a | 104d:9005 | Texas I... | PCIxx12 OHCI Compliant IE... | 37    | firewir... | EF87C7EE7B |
| 1180:0832 | 1028:01bd | Ricoh      | R5C832 IEEE 1394 Controller  | 37    | firewir... | FA750DAFE2 |
| 1180:0832 | 1028:024d | Ricoh      | R5C832 IEEE 1394 Controller  | 37    | firewir... | 127B65224F |
| 1217:11f7 | 1028:04a3 | O2 Micro   | OZ600 1394a-2000 Controller  | 37    | firewir... | F442DF91A1 |
| 1217:13f7 | 1028:049b | O2 Micro   | 1394 OHCI Compliant Host ... | 37    | firewir... | A1027F938F |
| 197b:2380 | 103c:17ab | JMicron... | IEEE 1394 Host Controller    | 37    | firewir... | 0BFBD31BA0 |
| 197b:2380 | 103c:1619 | JMicron... | IEEE 1394 Host Controller    | 36    | firewir... | DADA8DD37B |
| 197b:2380 | 103c:17a7 | JMicron... | IEEE 1394 Host Controller    | 36    | firewir... | 8D470E5C26 |
| 104c:803a | 103c:30a2 | Texas I... | PCIxx12 OHCI Compliant IE... | 35    | firewir... | D678BE8583 |
| 1180:0832 | 103c:30db | Ricoh      | R5C832 IEEE 1394 Controller  | 35    | firewir... | AF8E63842A |
| 1180:0832 | 103c:30bb | Ricoh      | R5C832 IEEE 1394 Controller  | 34    | firewir... | 944D6AF89A |
| 1180:0832 | 1043:1877 | Ricoh      | R5C832 IEEE 1394 Controller  | 34    | firewir... | 843C7A8519 |
| 197b:2380 | 103c:161d | JMicron... | IEEE 1394 Host Controller    | 33    | firewir... | 317C62DF4B |
| 1180:0832 | 1025:0126 | Ricoh      | R5C832 IEEE 1394 Controller  | 31    | firewir... | AA6D721BF2 |
| 104c:803a | 104d:9015 | Texas I... | PCIxx12 OHCI Compliant IE... | 30    | firewir... | 538C03B235 |
| 1180:0832 | 1028:0263 | Ricoh      | R5C832 IEEE 1394 Controller  | 30    | firewir... | 286C99863B |
| 104c:803a | 104d:902d | Texas I... | PCIxx12 OHCI Compliant IE... | 28    | firewir... | F76AE4B159 |
| 197b:2380 | 103c:3603 | JMicron... | IEEE 1394 Host Controller    | 28    | firewir... | 74CEE5B7A8 |
| 104c:803a | 1179:0001 | Texas I... | PCIxx12 OHCI Compliant IE... | 27    | firewir... | DF9FBBE08C |
| 197b:2380 | 103c:179c | JMicron... | IEEE 1394 Host Controller    | 27    | firewir... | 7AA667BA1A |
| 1180:0832 | 103c:30c5 | Ricoh      | R5C832 IEEE 1394 Controller  | 25    | firewir... | CBF5040FF7 |
| 197b:2380 | 103c:176b | JMicron... | IEEE 1394 Host Controller    | 25    | firewir... | 492907A363 |
| 104c:8025 |           | Texas I... | TSB82AA2 IEEE-1394b Link ... | 24    | firewir... | 8E5DAE94E9 |
| 1180:0832 | 1179:ff1e | Ricoh      | R5C832 IEEE 1394 Controller  | 24    | firewir... | C5391FAE24 |
| 1180:0832 | 17aa:2109 | Ricoh      | R5C832 IEEE 1394 Controller  | 24    | firewir... | BFBAB4F2DB |
| 197b:2380 | 103c:1631 | JMicron... | IEEE 1394 Host Controller    | 24    | firewir... | 98BD384A42 |
| 197b:2380 | 103c:30f4 | JMicron... | IEEE 1394 Host Controller    | 24    | firewir... | F4BFA397A6 |
| 197b:2380 | 103c:3659 | JMicron... | IEEE 1394 Host Controller    | 24    | firewir... | 4DD419063F |
| 1180:e832 | 1028:0429 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 23    | firewir... | A2E097AFE4 |
| 1180:e832 | 104d:9089 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 23    | firewir... | BCA5866F5E |
| 1217:00f7 | 1028:01fe | O2 Micro   | Firewire (IEEE 1394)         | 23    | firewir... | DAD4FD9AFE |
| 1217:00f7 | 10cf:14d7 | O2 Micro   | Firewire (IEEE 1394)         | 23    | firewir... | 08576DED50 |
| 1180:0832 | 1043:14e7 | Ricoh      | R5C832 IEEE 1394 Controller  | 22    | firewir... | 2494100ECB |
| 1180:0832 | 1179:ff1c | Ricoh      | R5C832 IEEE 1394 Controller  | 22    | firewir... | 8B7FBF3DE6 |
| 1180:0832 | 103c:30e7 | Ricoh      | R5C832 IEEE 1394 Controller  | 21    | firewir... | 37A7444281 |
| 1180:0832 | 1043:1317 | Ricoh      | R5C832 IEEE 1394 Controller  | 21    | firewir... | A4CF3B1E1D |
| 1180:e832 | 104d:9069 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 21    | firewir... | 0FB69D4D18 |
| 11c1:5903 | 11c1:5900 | LSI        | FW533 [TrueFire] PCIe 139... | 21    | firewir... | 359171629F |
| 1217:00f7 | 10cf:143e | O2 Micro   | Firewire (IEEE 1394)         | 21    | firewir... | B8D983BBB2 |
| 1180:0832 | 103c:30be | Ricoh      | R5C832 IEEE 1394 Controller  | 20    | firewir... | 5910FA85E5 |
| 1180:0832 | 103c:7007 | Ricoh      | R5C832 IEEE 1394 Controller  | 20    | firewir... | E8D8BC3EB6 |
| 1180:0832 | 1043:1897 | Ricoh      | R5C832 IEEE 1394 Controller  | 20    | firewir... | 0CFA6348DB |
| 1180:0832 | 17aa:3829 | Ricoh      | R5C832 IEEE 1394 Controller  | 20    | firewir... | 2D8E74D05C |
| 197b:2380 | 103c:3624 | JMicron... | IEEE 1394 Host Controller    | 20    | firewir... | D4B81612A8 |
| 1180:0832 | 1028:02a0 | Ricoh      | R5C832 IEEE 1394 Controller  | 19    | firewir... | B4F16960C4 |
| 1180:0832 | 103c:30cd | Ricoh      | R5C832 IEEE 1394 Controller  | 19    | firewir... | 0B9636C64B |
| 1217:13f7 | 1028:053e | O2 Micro   | 1394 OHCI Compliant Host ... | 19    | firewir... | 8516551E92 |
| 104c:803a | 103c:30aa | Texas I... | PCIxx12 OHCI Compliant IE... | 18    | firewir... | 11A771B463 |
| 1180:0832 | 1028:01f2 | Ricoh      | R5C832 IEEE 1394 Controller  | 18    | firewir... | C74668293E |
| 1180:0832 | 10f7:8338 | Ricoh      | R5C832 IEEE 1394 Controller  | 18    | firewir... | 3678F83BBA |
| 104c:803a | 104d:9016 | Texas I... | PCIxx12 OHCI Compliant IE... | 17    | firewir... | 3F2717CA34 |
| 1180:0832 | 1025:011d | Ricoh      | R5C832 IEEE 1394 Controller  | 17    | firewir... | FAE514C059 |
| 1180:0832 | 1028:0262 | Ricoh      | R5C832 IEEE 1394 Controller  | 17    | firewir... | 7049BBE182 |
| 1180:0832 | 1028:029a | Ricoh      | R5C832 IEEE 1394 Controller  | 17    | firewir... | 55832DD912 |
| 1180:0832 | 104d:9045 | Ricoh      | R5C832 IEEE 1394 Controller  | 17    | firewir... | D24D4DF847 |
| 1180:0832 | 104d:906b | Ricoh      | R5C832 IEEE 1394 Controller  | 17    | firewir... | 3A4E2269AF |
| 1180:e832 | 1028:0413 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 17    | firewir... | 0BD515D97A |
| 1180:e832 | 1028:0428 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 17    | firewir... | 5B02ACCD5B |
| 1180:e832 | 104d:9067 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 17    | firewir... | FFAE60B13A |
| 1180:e832 | 104d:907a | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 17    | firewir... | 6DF1E13E63 |
| 1217:11f7 | 1028:04a4 | O2 Micro   | OZ600 1394a-2000 Controller  | 17    | firewir... | 3C06AD8F67 |
| 197b:2380 | 103c:162a | JMicron... | IEEE 1394 Host Controller    | 17    | firewir... | 0B1F6A34CE |
| 197b:2380 | 103c:176c | JMicron... | IEEE 1394 Host Controller    | 17    | firewir... | D23574ECF1 |
| 1180:0832 | 1028:01f1 | Ricoh      | R5C832 IEEE 1394 Controller  | 16    | firewir... | 3DF4E95976 |
| 1180:0832 | 104d:900e | Ricoh      | R5C832 IEEE 1394 Controller  | 16    | firewir... | 972677CEAB |

### Flash memory (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1524:0520 | 1025:0090 | ENE Tec... | FLASH memory: ENE Technol... | 57    |            | B09A0D7779 |
| 1524:0530 | 1025:0090 | ENE Tec... | ENE PCI Memory Stick Card... | 57    |            | B09A0D7779 |
| 1524:0551 | 1025:0090 | ENE Tec... | SD/MMC Card Reader Contro... | 57    | sdhci_pci  | B09A0D7779 |
| 1524:0551 | 1025:009f | ENE Tec... | SD/MMC Card Reader Contro... | 43    | sdhci_pci  | 86DFC89E4A |
| 1524:0520 | 1025:009f | ENE Tec... | FLASH memory: ENE Technol... | 42    |            | 86DFC89E4A |
| 1524:0530 | 1025:009f | ENE Tec... | ENE PCI Memory Stick Card... | 42    |            | 86DFC89E4A |
| 1524:0720 | 1025:012e | ENE Tec... | Memory Stick Card Reader ... | 20    |            | 7CFA18C731 |
| 1524:0730 | 1025:012e | ENE Tec... | ENE PCI Memory Stick Card... | 20    |            | 7CFA18C731 |
| 1524:0751 | 1025:012e | ENE Tec... | ENE PCI Secure Digital / ... | 20    | sdhci_pci  | 7CFA18C731 |
| 1524:0520 | 1025:010f | ENE Tec... | FLASH memory: ENE Technol... | 16    |            | A9D5FB836A |
| 1524:0530 | 1025:010f | ENE Tec... | ENE PCI Memory Stick Card... | 16    |            | A9D5FB836A |
| 1524:0551 | 1025:010f | ENE Tec... | SD/MMC Card Reader Contro... | 16    | sdhci_pci  | A9D5FB836A |
| 1524:0530 | 14c0:0020 | ENE Tec... | ENE PCI Memory Stick Card... | 11    |            | E24E46E21D |
| 1524:0530 | 1734:10c1 | ENE Tec... | ENE PCI Memory Stick Card... | 11    |            | 1517AC0D45 |
| 1524:0551 | 14c0:0020 | ENE Tec... | SD/MMC Card Reader Contro... | 11    | sdhci_pci  | E24E46E21D |
| 1524:0551 | 1734:10c1 | ENE Tec... | SD/MMC Card Reader Contro... | 11    | sdhci_pci  | 1517AC0D45 |
| 1524:0730 | 1558:5409 | ENE Tec... | ENE PCI Memory Stick Card... | 6     |            | 00EBCAC258 |
| 1524:0751 | 1558:5409 | ENE Tec... | ENE PCI Secure Digital / ... | 6     | sdhci_pci  | 00EBCAC258 |
| 1524:0730 | 1558:0801 | ENE Tec... | ENE PCI Memory Stick Card... | 5     |            | BF5F7A5F0A |
| 1524:0751 | 1558:0801 | ENE Tec... | ENE PCI Secure Digital / ... | 5     | sdhci_pci  | BF5F7A5F0A |
| 1524:0520 | 1179:ff01 | ENE Tec... | FLASH memory: ENE Technol... | 4     |            | 89C7F0F25E |
| 1524:0530 | 1179:ff01 | ENE Tec... | ENE PCI Memory Stick Card... | 4     |            | 89C7F0F25E |
| 1524:0551 | 1179:ff02 | ENE Tec... | SD/MMC Card Reader Contro... | 4     | sdhci_pci  | 89C7F0F25E |
| 1524:0720 | 1025:011b | ENE Tec... | Memory Stick Card Reader ... | 4     |            | CD287A7C40 |
| 1524:0730 | 1025:011b | ENE Tec... | ENE PCI Memory Stick Card... | 4     |            | CD287A7C40 |
| 1524:0730 | 1558:0722 | ENE Tec... | ENE PCI Memory Stick Card... | 4     |            | F92C7E8C3E |
| 1524:0751 | 1025:011b | ENE Tec... | ENE PCI Secure Digital / ... | 4     | sdhci_pci  | CD287A7C40 |
| 1524:0751 | 1558:0722 | ENE Tec... | ENE PCI Secure Digital / ... | 4     | sdhci_pci  | F92C7E8C3E |
| 1106:9530 | 17aa:3891 | VIA Tec... | VX800/820/900 Series Secu... | 3     | via_sdmmc  | 4762847735 |
| 1524:0720 | 1462:2fb3 | ENE Tec... | Memory Stick Card Reader ... | 3     |            | 5604F2B979 |
| 1524:0730 | 1462:2fb3 | ENE Tec... | ENE PCI Memory Stick Card... | 3     |            | 5604F2B979 |
| 1524:0730 | 1558:0669 | ENE Tec... | ENE PCI Memory Stick Card... | 3     |            | 66E0793D5B |
| 1524:0730 | 1558:0802 | ENE Tec... | ENE PCI Memory Stick Card... | 3     |            | 44B42FE693 |
| 1524:0751 | 1462:2fb3 | ENE Tec... | ENE PCI Secure Digital / ... | 3     | sdhci_pci  | 5604F2B979 |
| 1524:0751 | 1558:0669 | ENE Tec... | ENE PCI Secure Digital / ... | 3     | sdhci_pci  | 66E0793D5B |
| 1524:0751 | 1558:0802 | ENE Tec... | ENE PCI Secure Digital / ... | 3     | sdhci_pci  | 44B42FE693 |
| 1106:9530 | 144d:c04e | VIA Tec... | VX800/820/900 Series Secu... | 2     | via_sdmmc  | 085B83A79C |
| 1524:0520 | 1025:007f | ENE Tec... | FLASH memory: ENE Technol... | 2     |            | 14C016A2F9 |
| 1524:0530 | 1025:007f | ENE Tec... | ENE PCI Memory Stick Card... | 2     |            | 14C016A2F9 |
| 1524:0551 | 1025:007f | ENE Tec... | SD/MMC Card Reader Contro... | 2     | sdhci_pci  | 14C016A2F9 |
| 1524:0720 | 1462:2fbd | ENE Tec... | Memory Stick Card Reader ... | 2     |            | 6502446C70 |
| 1524:0730 | 1462:2fbd | ENE Tec... | ENE PCI Memory Stick Card... | 2     |            | 6502446C70 |
| 1524:0730 | 1558:5408 | ENE Tec... | ENE PCI Memory Stick Card... | 2     |            | 01A8AC7CD9 |
| 1524:0751 | 1462:2fbd | ENE Tec... | ENE PCI Secure Digital / ... | 2     | sdhci_pci  | 6502446C70 |
| 1524:0751 | 1558:5408 | ENE Tec... | ENE PCI Secure Digital / ... | 2     | sdhci_pci  | 01A8AC7CD9 |
| 1106:9530 | 152d:0771 | VIA Tec... | VX800/820/900 Series Secu... | 1     | via_sdmmc  | 77A2A10D46 |
| 1524:0500 | 1524:0500 | ENE Tec... | FLASH memory                 | 1     |            | 1312407631 |
| 1524:0510 | 103c:006a | ENE Tec... | CB710 Memory Card Reader ... | 1     | cb710      | 66FC1D68B2 |
| 1524:0510 | 1524:0510 | ENE Tec... | CB710 Memory Card Reader ... | 1     | cb710      | 1312407631 |
| 1524:0510 | 1631:d004 | ENE Tec... | CB710 Memory Card Reader ... | 1     | cb710      | 2EE7FA4DA9 |
| 1524:0520 | 1025:007a | ENE Tec... | FLASH memory: ENE Technol... | 1     |            | E4219525B9 |
| 1524:0520 | 1025:0081 | ENE Tec... | FLASH memory: ENE Technol... | 1     |            | 0C32C44824 |
| 1524:0520 | 1179:ff10 | ENE Tec... | FLASH memory: ENE Technol... | 1     |            | 4375F8C26E |
| 1524:0530 | 1025:007a | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | E4219525B9 |
| 1524:0530 | 1025:0081 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | 0C32C44824 |
| 1524:0530 | 1179:ff10 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | 4375F8C26E |
| 1524:0530 | 1558:5401 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | 8CF7873695 |
| 1524:0530 | 1734:10d7 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | CA3AC06D30 |
| 1524:0530 | 17aa:2079 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | EDAE63A429 |
| 1524:0551 | 1025:007a | ENE Tec... | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | E4219525B9 |
| 1524:0551 | 1025:0081 | ENE Tec... | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 0C32C44824 |
| 1524:0551 | 1179:ff10 | ENE Tec... | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 4375F8C26E |
| 1524:0551 | 1558:5401 | ENE Tec... | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 8CF7873695 |
| 1524:0551 | 1734:10d7 | ENE Tec... | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | CA3AC06D30 |
| 1524:0551 | 17aa:2078 | ENE Tec... | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | EDAE63A429 |
| 1524:0720 | 1025:012a | ENE Tec... | Memory Stick Card Reader ... | 1     |            | C95503E7D2 |
| 1524:0730 | 1025:012a | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | C95503E7D2 |
| 1524:0730 | 1558:0573 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | 95780C2963 |
| 1524:0730 | 1558:0664 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | 51E2E84C28 |
| 1524:0730 | 1558:0668 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | 41C9811E8B |
| 1524:0730 | 1558:0721 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | A52F0F2D7C |
| 1524:0751 | 1025:012a | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | C95503E7D2 |
| 1524:0751 | 1558:0573 | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | 95780C2963 |
| 1524:0751 | 1558:0664 | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | 51E2E84C28 |
| 1524:0751 | 1558:0668 | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | 41C9811E8B |
| 1524:0751 | 1558:0721 | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | A52F0F2D7C |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1577 | 1022:1577 | AMD        | Family 15h (Models 60h-6f... | 409   |            | 34F2870A95 |
| 1022:1423 | 1022:1423 | AMD        | Family 15h (Models 30h-3f... | 27    |            | D80EB2D42C |
| 1022:1577 | 103c:8331 | AMD        | Family 15h (Models 60h-6f... | 27    |            | F60949A3CC |
| 1022:1577 | 103c:81fa | AMD        | Family 15h (Models 60h-6f... | 14    |            | 11013F1334 |
| 1022:1451 | 1022:1451 | AMD        | Family 17h (Models 00h-0f... | 12    |            | 7CB34B0A2E |
| 1022:1577 | 103c:80b5 | AMD        | Family 15h (Models 60h-6f... | 8     |            | 846B2E2A87 |
| 1022:1423 | 103c:812f | AMD        | Family 15h (Models 30h-3f... | 7     |            | 59A4CFC209 |
| 1022:1577 | 103c:80b6 | AMD        | Family 15h (Models 60h-6f... | 2     |            | BEA3C73273 |
| 1022:1577 | 103c:8355 | AMD        | Family 15h (Models 60h-6f... | 2     |            | D6F5348EC7 |
| 8086:19a2 | 8086:19a2 | Intel      | Atom Processor C3000 Seri... | 1     |            | 50B6A72C0C |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 367   | i915       | 2FBF6F153B |
| 8086:0046 | 17aa:215a | Intel      | Core Processor Integrated... | 240   | i915       | 570863FD8C |
| 8086:2a42 | 17aa:20e4 | Intel      | Mobile 4 Series Chipset I... | 206   | i915       | 9A7BE426F5 |
| 8086:2a43 | 17aa:20e4 | Intel      | Mobile 4 Series Chipset I... | 206   |            | 9A7BE426F5 |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics 500              | 165   | i915       | 63FACC4838 |
| 8086:0166 | 17aa:21fa | Intel      | 3rd Gen Core processor Gr... | 164   | i915       | EC8AF5F350 |
| 8086:0166 | 17aa:21f3 | Intel      | 3rd Gen Core processor Gr... | 162   | i915       | C9D8EFC9B9 |
| 8086:3e9b | 1025:1331 | Intel      | CoffeeLake-H GT2 [UHD Gra... | 157   | i915       | BC9DC107D1 |
| 8086:a011 | 1043:83ac | Intel      | Atom Processor D4xx/D5xx/... | 148   | i915       | E74DC83F0A |
| 8086:a012 | 1043:83ac | Intel      | Atom Processor D4xx/D5xx/... | 148   |            | E74DC83F0A |
| 8086:3e9b | 1028:0905 | Intel      | CoffeeLake-H GT2 [UHD Gra... | 142   | i915       | 58E43F0514 |
| 10de:1f91 | 1025:1332 | Nvidia     | TU117M [GeForce GTX 1650 ... | 137   | nvidia     | BC9DC107D1 |
| 10de:1f91 | 1028:0905 | Nvidia     | TU117M [GeForce GTX 1650 ... | 133   | nvidia     | 58E43F0514 |
| 8086:0166 | 1028:0534 | Intel      | 3rd Gen Core processor Gr... | 133   | i915       | FA4D12994D |
| 8086:0126 | 17aa:21ce | Intel      | 2nd Generation Core Proce... | 132   | i915       | A75FFD5203 |
| 8086:0166 | 17aa:3977 | Intel      | 3rd Gen Core processor Gr... | 132   | i915       | 6B1D1F059F |
| 8086:2a42 | 1043:1862 | Intel      | Mobile 4 Series Chipset I... | 131   | i915       | 84F6267AD8 |
| 8086:2a43 | 1043:1862 | Intel      | Mobile 4 Series Chipset I... | 131   |            | 84F6267AD8 |
| 8086:0f31 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 129   | i915       | D04BD787B3 |
| 8086:0a16 | 17aa:220c | Intel      | Haswell-ULT Integrated Gr... | 127   | i915       | 415CC7FE56 |
| 8086:0126 | 1028:0493 | Intel      | 2nd Generation Core Proce... | 123   | i915       | DC9A1E9C1B |
| 8086:1916 | 103c:8079 | Intel      | Skylake GT2 [HD Graphics ... | 123   | i915       | 436E9BF227 |
| 8086:2a02 | 17aa:20b5 | Intel      | Mobile GM965/GL960 Integr... | 123   | i915       | EE90608B54 |
| 8086:2a03 | 17aa:20b5 | Intel      | Mobile GM965/GL960 Integr... | 123   |            | EE90608B54 |
| 8086:1626 | 106b:011b | Intel      | HD Graphics 6000             | 122   | i915       | 5BE083EDAB |
| 1002:98e4 | 103c:8330 | AMD        | Stoney [Radeon R2/R3/R4/R... | 120   | amdgpu     | 18CEA74915 |
| 8086:0126 | 17aa:21da | Intel      | 2nd Generation Core Proce... | 120   | i915       | 402DDBAA44 |
| 8086:0a16 | 17aa:3978 | Intel      | Haswell-ULT Integrated Gr... | 119   | i915       | 2519EFDF20 |
| 8086:2a42 | 17aa:3a02 | Intel      | Mobile 4 Series Chipset I... | 116   | i915       | B9412E1AB2 |
| 8086:2a43 | 17aa:3a02 | Intel      | Mobile 4 Series Chipset I... | 116   |            | B9412E1AB2 |
| 8086:0106 | 1025:0649 | Intel      | 2nd Generation Core Proce... | 115   | i915       | 82E60126C9 |
| 8086:0a16 | 103c:198f | Intel      | Haswell-ULT Integrated Gr... | 115   | i915       | CECD552E89 |
| 8086:3e9b | 1028:087c | Intel      | CoffeeLake-H GT2 [UHD Gra... | 114   | i915       | 0FA8C3ED0C |
| 8086:0116 | 1025:0504 | Intel      | 2nd Generation Core Proce... | 113   | i915       | B66EB36016 |
| 8086:a011 | 1025:0349 | Intel      | Atom Processor D4xx/D5xx/... | 112   | i915       | 09B8FC981C |
| 8086:a012 | 1025:0349 | Intel      | Atom Processor D4xx/D5xx/... | 112   |            | 09B8FC981C |
| 8086:3ea0 | 103c:8549 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 111   | i915       | A814284F0B |
| 8086:0166 | 106b:00fa | Intel      | 3rd Gen Core processor Gr... | 110   | i915       | 783D081B5A |
| 8086:3185 | 1043:1261 | Intel      | GeminiLake [UHD Graphics ... | 109   | i915       | 985D10D314 |
| 8086:5917 | 1028:0810 | Intel      | UHD Graphics 620             | 108   | i915       | C01FA4B013 |
| 8086:0a16 | 1025:0866 | Intel      | Haswell-ULT Integrated Gr... | 107   | i915       | 11EBF2008B |
| 8086:0f31 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 106   | i915       | 1387FAB9FE |
| 8086:2a42 | 1028:02aa | Intel      | Mobile 4 Series Chipset I... | 106   | i915       | E8E9A85406 |
| 8086:2a43 | 1028:02aa | Intel      | Mobile 4 Series Chipset I... | 106   |            | E8E9A85406 |
| 10de:1c8c | 1028:087c | Nvidia     | GP107M [GeForce GTX 1050 ... | 105   | nvidia     | 0FA8C3ED0C |
| 8086:0126 | 106b:00db | Intel      | 2nd Generation Core Proce... | 105   | i915       | 6E17FB6EA4 |
| 8086:2a02 | 1025:011f | Intel      | Mobile GM965/GL960 Integr... | 105   | i915       | 8592F1650F |
| 8086:2a03 | 1025:011f | Intel      | Mobile GM965/GL960 Integr... | 105   |            | 8592F1650F |
| 8086:0166 | 1025:0647 | Intel      | 3rd Gen Core processor Gr... | 103   | i915       | 8BC152AA27 |
| 8086:5917 | 1028:07e6 | Intel      | UHD Graphics 620             | 99    | i915       | 5A56854746 |
| 8086:591b | 1028:07be | Intel      | HD Graphics 630              | 99    | i915       | 69938C221E |
| 8086:0166 | 1043:124d | Intel      | 3rd Gen Core processor Gr... | 98    | i915       | 15E808F714 |
| 8086:0046 | 1028:040a | Intel      | Core Processor Integrated... | 96    | i915       | BA51FC9216 |
| 8086:0f31 | 17aa:3909 | Intel      | Atom Processor Z36xxx/Z37... | 96    | i915       | 184B909FC0 |
| 8086:9b41 | 17aa:5079 | Intel      | CometLake-U GT2 [UHD Grap... | 96    | i915       | 1221048E12 |
| 8086:0166 | 1025:064b | Intel      | 3rd Gen Core processor Gr... | 95    | i915       | D74C10F41F |
| 8086:0416 | 17aa:220e | Intel      | 4th Gen Core Processor In... | 95    | i915       | 36F407C3AA |
| 10de:1c8d | 1028:07be | Nvidia     | GP107M [GeForce GTX 1050 ... | 94    | nvidia     | 69938C221E |
| 1002:15d8 | 1043:18f1 | AMD        | Picasso                      | 92    | amdgpu     | 456B686D28 |
| 8086:3ea0 | 1028:08af | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 92    | i915       | 52DEA66C52 |
| 8086:0156 | 17aa:3977 | Intel      | 3rd Gen Core processor Gr... | 90    | i915       | 5CEAD11297 |
| 8086:0a16 | 17aa:2214 | Intel      | Haswell-ULT Integrated Gr... | 88    | i915       | F802ABEF07 |
| 8086:1616 | 17aa:2226 | Intel      | HD Graphics 5500             | 88    | i915       | 22A87CB141 |
| 1002:98e4 | 103c:84ac | AMD        | Stoney [Radeon R2/R3/R4/R... | 87    | amdgpu     | 3A06ECCCAA |
| 8086:1616 | 103c:2216 | Intel      | HD Graphics 5500             | 86    | i915       | FFB40F821B |
| 8086:2a02 | 1028:022f | Intel      | Mobile GM965/GL960 Integr... | 86    | i915       | 38B4BA227C |
| 8086:2a03 | 1028:022f | Intel      | Mobile GM965/GL960 Integr... | 86    |            | 38B4BA227C |
| 8086:3e9b | 1025:1264 | Intel      | CoffeeLake-H GT2 [UHD Gra... | 86    | i915       | 7F70DE1771 |
| 8086:3ea0 | 17aa:2292 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 86    | i915       | 26C62915E0 |
| 8086:5917 | 17aa:225c | Intel      | UHD Graphics 620             | 86    | i915       | 2B4A1A20D9 |
| 8086:1626 | 106b:011a | Intel      | HD Graphics 6000             | 85    | i915       | 22A831DB3D |
| 8086:0a16 | 1028:0651 | Intel      | Haswell-ULT Integrated Gr... | 84    | i915       | 0862DC626B |
| 8086:9bc4 | 1028:097d | Intel      | CometLake-H GT2 [UHD Grap... | 84    | i915       | 994B96D25D |
| 8086:2a02 | 106b:00a1 | Intel      | Mobile GM965/GL960 Integr... | 83    | i915       | 34FC60E37E |
| 8086:2a03 | 106b:00a1 | Intel      | Mobile GM965/GL960 Integr... | 83    |            | 34FC60E37E |
| 1002:15d8 | 19e5:3e19 | AMD        | Picasso                      | 81    | amdgpu     | 1310B8ABF4 |
| 8086:0a16 | 1028:05cb | Intel      | Haswell-ULT Integrated Gr... | 81    | i915       | 98C988645F |
| 8086:2a42 | 1028:0233 | Intel      | Mobile 4 Series Chipset I... | 81    | i915       | 6B7EF9CAD5 |
| 8086:2a43 | 1028:0233 | Intel      | Mobile 4 Series Chipset I... | 81    |            | 6B7EF9CAD5 |
| 8086:0166 | 103c:179b | Intel      | 3rd Gen Core processor Gr... | 80    | i915       | 1B2FBCDFA0 |
| 8086:0416 | 17aa:3978 | Intel      | 4th Gen Core Processor In... | 80    | i915       | 61B036977B |
| 1002:98e4 | 1025:1192 | AMD        | Stoney [Radeon R2/R3/R4/R... | 79    | amdgpu     | F5F4E2457B |
| 8086:0126 | 103c:161c | Intel      | 2nd Generation Core Proce... | 78    | i915       | 18F27D1F5C |
| 8086:0f31 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 78    | i915       | 31AC5CDF6E |
| 8086:3ea0 | 17aa:2279 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 78    | i915       | A01E524A66 |
| 8086:5916 | 1028:078b | Intel      | HD Graphics 620              | 78    | i915       | 35BCBD121B |
| 1002:6900 | 1028:0810 | AMD        | Topaz XT [Radeon R7 M260/... | 77    | amdgpu     | C01FA4B013 |
| 8086:0166 | 17aa:21f5 | Intel      | 3rd Gen Core processor Gr... | 77    | i915       | 69A252CCD6 |
| 8086:0116 | 1043:1682 | Intel      | 2nd Generation Core Proce... | 76    | i915       | C426070626 |
| 8086:1616 | 1028:062e | Intel      | HD Graphics 5500             | 76    | i915       | 91837758AC |
| 8086:22b1 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 76    | i915       | E9536CCBFB |
| 8086:2a02 | 1028:01f9 | Intel      | Mobile GM965/GL960 Integr... | 76    | i915       | 6DBCD5A1C8 |
| 8086:2a03 | 1028:01f9 | Intel      | Mobile GM965/GL960 Integr... | 76    |            | 6DBCD5A1C8 |
| 8086:3185 | 8086:2212 | Intel      | GeminiLake [UHD Graphics ... | 76    | i915       | F40D5FD5A7 |
| 8086:5917 | 17aa:225d | Intel      | UHD Graphics 620             | 76    | i915       | FEB7F2A285 |
| 1002:1636 | 17aa:507f | AMD        | Renoir                       | 75    | amdgpu     | 8A34D739FD |
| 8086:0416 | 103c:1993 | Intel      | 4th Gen Core Processor In... | 74    | i915       | 170DD8B241 |
| 8086:5916 | 1025:1094 | Intel      | HD Graphics 620              | 74    | i915       | 7046D52A8D |
| 1002:68e0 | 1043:1bf2 | AMD        | Park [Mobility Radeon HD ... | 73    | radeon     | A26C94316C |
| 8086:1916 | 17aa:2233 | Intel      | Skylake GT2 [HD Graphics ... | 73    | i915       | 9EF824D802 |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 1118  |            | 497BF56CC6 |
| 1022:1631 | 1022:1631 | AMD        | Renoir/Cezanne IOMMU         | 481   |            | 8948989999 |
| 1022:1577 | 103c:8330 | AMD        | Family 15h (Models 60h-6f... | 120   |            | 18CEA74915 |
| 1022:1631 | 17aa:5081 | AMD        | Renoir/Cezanne IOMMU         | 90    |            | 273A5FF27D |
| 1022:1577 | 103c:84ac | AMD        | Family 15h (Models 60h-6f... | 87    |            | 3A06ECCCAA |
| 1022:1577 | 1025:1192 | AMD        | Family 15h (Models 60h-6f... | 78    |            | F5F4E2457B |
| 1022:1631 | 17aa:507f | AMD        | Renoir/Cezanne IOMMU         | 75    |            | 8A34D739FD |
| 1022:1631 | 17aa:3803 | AMD        | Renoir/Cezanne IOMMU         | 70    |            | 3CDC08297E |
| 1022:15d1 | 1025:1366 | AMD        | Raven/Raven2 IOMMU           | 61    |            | BCC833AC3C |
| 1022:15d1 | 1025:134d | AMD        | Raven/Raven2 IOMMU           | 59    |            | 6134BF279A |
| 1022:15d1 | 103c:84ae | AMD        | Raven/Raven2 IOMMU           | 58    |            | 2E3861AEF3 |
| 1022:15d1 | 17aa:380a | AMD        | Raven/Raven2 IOMMU           | 58    |            | 3F7C00C1EF |
| 1022:1577 | 17aa:380e | AMD        | Family 15h (Models 60h-6f... | 53    |            | 0036C99447 |
| 1022:1631 | 17aa:5082 | AMD        | Renoir/Cezanne IOMMU         | 51    |            | 037A558C7D |
| 1022:15d1 | 17aa:380b | AMD        | Raven/Raven2 IOMMU           | 47    |            | 09ADDF2612 |
| 1022:15d1 | 103c:8615 | AMD        | Raven/Raven2 IOMMU           | 45    |            | 406FCB6975 |
| 1022:1631 | 1d05:109f | AMD        | Renoir/Cezanne IOMMU         | 45    |            | 7242436545 |
| 1022:15d1 | 1025:1259 | AMD        | Raven/Raven2 IOMMU           | 44    |            | 3D5D3DDF84 |
| 1022:1631 | 17aa:380a | AMD        | Renoir/Cezanne IOMMU         | 40    |            | 86BC5DDC56 |
| 1022:1631 | 17aa:507e | AMD        | Renoir/Cezanne IOMMU         | 39    |            | E9A8FB1275 |
| 1022:15d1 | 103c:85ea | AMD        | Raven/Raven2 IOMMU           | 38    |            | E8781DB5AB |
| 1022:1631 | 1025:142b | AMD        | Renoir/Cezanne IOMMU         | 37    |            | BCE3E39F4C |
| 1022:15d1 | 103c:84e7 | AMD        | Raven/Raven2 IOMMU           | 36    |            | CF69BD4423 |
| 1022:15d1 | 17aa:3804 | AMD        | Raven/Raven2 IOMMU           | 36    |            | 0C3651AF28 |
| 1022:15d1 | 103c:86fd | AMD        | Raven/Raven2 IOMMU           | 34    |            | 5BB4E443F9 |
| 1022:1631 | 17aa:3808 | AMD        | Renoir/Cezanne IOMMU         | 31    |            | 8C961555FE |
| 1022:15d1 | 1025:134f | AMD        | Raven/Raven2 IOMMU           | 30    |            | 5EDDDC1E2C |
| 1022:1631 | 1025:1461 | AMD        | Renoir/Cezanne IOMMU         | 30    |            | 264BADF289 |
| 1022:15d1 | 103c:85b3 | AMD        | Raven/Raven2 IOMMU           | 29    |            | AE1811A242 |
| 1022:15d1 | 1025:125c | AMD        | Raven/Raven2 IOMMU           | 27    |            | 2FF605BDB0 |
| 1022:1631 | 103c:887a | AMD        | Renoir/Cezanne IOMMU         | 26    |            | 2BA5AE42BB |
| 1022:15d1 | 1025:1456 | AMD        | Raven/Raven2 IOMMU           | 24    |            | 09F6196E70 |
| 1022:15d1 | 103c:85e0 | AMD        | Raven/Raven2 IOMMU           | 24    |            | 1A23A6605B |
| 1022:1631 | 1025:1455 | AMD        | Renoir/Cezanne IOMMU         | 24    |            | F581CF8319 |
| 1022:1577 | 1025:109f | AMD        | Family 15h (Models 60h-6f... | 23    |            | 70037BDDCB |
| 1022:1577 | 103c:81f9 | AMD        | Family 15h (Models 60h-6f... | 23    |            | F8A1A59318 |
| 1022:1631 | 17aa:3815 | AMD        | Renoir/Cezanne IOMMU         | 23    |            | C7A45F22C5 |
| 1022:1631 | 1e83:3e33 | AMD        | Renoir/Cezanne IOMMU         | 23    |            | 1E059DB869 |
| 1022:1631 | 1d05:1100 | AMD        | Renoir/Cezanne IOMMU         | 22    |            | 97B2732F29 |
| 1022:1631 | 1043:1602 | AMD        | Renoir/Cezanne IOMMU         | 19    |            | CC4C888046 |
| 1022:1631 | 17aa:5097 | AMD        | Renoir/Cezanne IOMMU         | 19    |            | 8D45D9544E |
| 1022:1631 | 1028:09f5 | AMD        | Renoir/Cezanne IOMMU         | 18    |            | B11BD373D3 |
| 1022:1481 | 1558:50f0 | AMD        | Starship/Matisse IOMMU       | 17    |            | D63FD746BE |
| 1022:15d1 | 103c:8706 | AMD        | Raven/Raven2 IOMMU           | 17    |            | D39BE3EDBA |
| 1022:1631 | 152d:1273 | AMD        | Renoir/Cezanne IOMMU         | 17    |            | BBF16A7212 |
| 1022:1577 | 1028:087e | AMD        | Family 15h (Models 60h-6f... | 16    |            | 4DFA5F5D2E |
| 1022:1577 | 103c:84a0 | AMD        | Family 15h (Models 60h-6f... | 16    |            | DF0FA8E968 |
| 1022:1577 | 103c:84d0 | AMD        | Family 15h (Models 60h-6f... | 16    |            | D4F113F6C4 |
| 1022:15d1 | 1028:0812 | AMD        | Raven/Raven2 IOMMU           | 16    |            | 57A0B50AEC |
| 1022:1631 | 103c:87b1 | AMD        | Renoir/Cezanne IOMMU         | 16    |            | CB7D97FD9E |
| 1022:1631 | 17aa:380d | AMD        | Renoir/Cezanne IOMMU         | 16    |            | 594815BB9D |
| 1022:1577 | 103c:8324 | AMD        | Family 15h (Models 60h-6f... | 15    |            | 5856720999 |
| 1022:1577 | 103c:8333 | AMD        | Family 15h (Models 60h-6f... | 14    |            | 57EE9BD872 |
| 1022:1577 | 103c:85bb | AMD        | Family 15h (Models 60h-6f... | 14    |            | 7F3E3F1E51 |
| 1022:15d1 | 103c:86d5 | AMD        | Raven/Raven2 IOMMU           | 14    |            | 9B0872B3D4 |
| 1022:1577 | 1028:0769 | AMD        | Family 15h (Models 60h-6f... | 13    |            | 9FCA078069 |
| 1022:1577 | 103c:8345 | AMD        | Family 15h (Models 60h-6f... | 13    |            | AE684ABD8C |
| 1022:1577 | 17aa:380d | AMD        | Family 15h (Models 60h-6f... | 13    |            | 6BABB58C51 |
| 1022:15d1 | 1028:0a12 | AMD        | Raven/Raven2 IOMMU           | 13    |            | 38D22B1058 |
| 1022:15d1 | 103c:879e | AMD        | Raven/Raven2 IOMMU           | 13    |            | A94D17F64B |
| 1022:1631 | 103c:87cf | AMD        | Renoir/Cezanne IOMMU         | 13    |            | EDE284A3A3 |
| 1022:1577 | 1025:1099 | AMD        | Family 15h (Models 60h-6f... | 12    |            | FB8D7A6A25 |
| 1022:15d1 | 103c:84d2 | AMD        | Raven/Raven2 IOMMU           | 12    |            | 838188303A |
| 1022:15d1 | 17aa:3809 | AMD        | Raven/Raven2 IOMMU           | 12    |            | C3F376B088 |
| 1022:1631 | 103c:87c5 | AMD        | Renoir/Cezanne IOMMU         | 12    |            | 55F8110D0E |
| 1022:1631 | 17aa:380b | AMD        | Renoir/Cezanne IOMMU         | 12    |            | DCE0B57CDC |
| 1022:15d1 | 103c:86d4 | AMD        | Raven/Raven2 IOMMU           | 11    |            | 98874D48B2 |
| 1022:1631 | 1d72:1953 | AMD        | Renoir/Cezanne IOMMU         | 11    |            | 23546F7A48 |
| 1022:1631 | 1025:151e | AMD        | Renoir/Cezanne IOMMU         | 10    |            | F6DDC3A2DA |
| 1022:1631 | 103c:8786 | AMD        | Renoir/Cezanne IOMMU         | 10    |            | F19AD7CBA2 |
| 1022:1631 | 103c:87b2 | AMD        | Renoir/Cezanne IOMMU         | 10    |            | 2C5F518CC8 |
| 1022:1631 | 17aa:3811 | AMD        | Renoir/Cezanne IOMMU         | 10    |            | A376D9680F |
| 1022:15d1 | 1025:1233 | AMD        | Raven/Raven2 IOMMU           | 9     |            | 6ADFA9E5CD |
| 1022:15d1 | 1028:08d7 | AMD        | Raven/Raven2 IOMMU           | 9     |            | 3A55618AEE |
| 1022:1631 | 103c:88dd | AMD        | Renoir/Cezanne IOMMU         | 9     |            | 8512EE02BD |
| 1022:1631 | 1d72:2031 | AMD        | Renoir/Cezanne IOMMU         | 9     |            | 99EFF2370B |
| 1022:1577 | 1025:1201 | AMD        | Family 15h (Models 60h-6f... | 8     |            | A34056020D |
| 1022:1577 | 1025:1362 | AMD        | Family 15h (Models 60h-6f... | 8     |            | 6DB45D962D |
| 1022:1577 | 103c:84ad | AMD        | Family 15h (Models 60h-6f... | 8     |            | EB0E17A039 |
| 1022:15d1 | 17aa:3803 | AMD        | Raven/Raven2 IOMMU           | 8     |            | D28B90EFDC |
| 1022:1631 | 1558:a500 | AMD        | Renoir/Cezanne IOMMU         | 8     |            | E4FB2B6B8A |
| 1022:1631 | 17aa:5094 | AMD        | Renoir/Cezanne IOMMU         | 8     |            | 11CD74E647 |
| 1022:1631 | 1d72:1951 | AMD        | Renoir/Cezanne IOMMU         | 8     |            | 21F95CA802 |
| 1022:1577 | 1025:1087 | AMD        | Family 15h (Models 60h-6f... | 7     |            | 34AA3DCA40 |
| 1022:1577 | 103c:80af | AMD        | Family 15h (Models 60h-6f... | 7     |            | 8FE2203713 |
| 1022:1577 | 17aa:3803 | AMD        | Family 15h (Models 60h-6f... | 7     |            | B6715F92F7 |
| 1022:1631 | 17aa:3812 | AMD        | Renoir/Cezanne IOMMU         | 7     |            | 644553839A |
| 1022:1577 | 103c:80b0 | AMD        | Family 15h (Models 60h-6f... | 6     |            | FC5CE69792 |
| 1022:1577 | 103c:81fe | AMD        | Family 15h (Models 60h-6f... | 6     |            | 26C8B8BD13 |
| 1022:15d1 | 103c:87b7 | AMD        | Raven/Raven2 IOMMU           | 6     |            | B754C74B11 |
| 1022:15d1 | 17aa:3802 | AMD        | Raven/Raven2 IOMMU           | 6     |            | D3F86F70AE |
| 1022:1631 | 103c:8787 | AMD        | Renoir/Cezanne IOMMU         | 6     |            | 2412314AD9 |
| 1022:1631 | 103c:8919 | AMD        | Renoir/Cezanne IOMMU         | 6     |            | D49638CC86 |
| 1022:1631 | 1a58:2014 | AMD        | Renoir/Cezanne IOMMU         | 6     |            | F424437BD1 |
| 1022:1451 | 1025:1246 | AMD        | Family 17h (Models 00h-0f... | 5     |            | 03FACC3040 |
| 1022:1577 | 1028:087f | AMD        | Family 15h (Models 60h-6f... | 5     |            | 53AC57FBEA |
| 1022:15d1 | 1025:1378 | AMD        | Raven/Raven2 IOMMU           | 5     |            | 589BEB7652 |
| 1022:15d1 | 103c:84a2 | AMD        | Raven/Raven2 IOMMU           | 5     |            | 220E290FCB |
| 1022:15d1 | 103c:86d6 | AMD        | Raven/Raven2 IOMMU           | 5     |            | 1C91BC1DEB |
| 1022:1631 | 1025:1537 | AMD        | Renoir/Cezanne IOMMU         | 5     |            | BE8229729B |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816c | 17aa:5081 | Realtek... | RTL8111xP IPMI interface     | 88    |            | 273A5FF27D |
| 10ec:816c | 17aa:5082 | Realtek... | RTL8111xP IPMI interface     | 47    |            | 037A558C7D |
| 10ec:816c | 17aa:507e | Realtek... | RTL8111xP IPMI interface     | 31    |            | AC5C6A0DD6 |
| 10ec:816c | 17aa:5125 | Realtek... | RTL8111xP IPMI interface     | 27    |            | 8E00E1F239 |
| 10ec:816c | 17aa:5126 | Realtek... | RTL8111xP IPMI interface     | 27    |            | 6B6B00F95C |
| 10ec:816c | 17aa:5122 | Realtek... | RTL8111xP IPMI interface     | 12    |            | 483690E890 |
| 10ec:816c | 103c:8584 | Realtek... | RTL8111xP IPMI interface     | 11    |            | 295112838E |
| 10ec:816c | 103c:83d5 | Realtek... | RTL8111xP IPMI interface     | 9     |            | 7154F86BD2 |
| 10ec:816c | 103c:8589 | Realtek... | RTL8111xP IPMI interface     | 4     |            | 4168E4F738 |
| 10ec:816c | 103c:8401 | Realtek... | RTL8111xP IPMI interface     | 3     |            | 8167AD2172 |
| 10ec:816c | 17aa:5123 | Realtek... | RTL8111xP IPMI interface     | 3     |            | 516554B4E7 |
| 10ec:816c | 10ec:0123 | Realtek... | RTL8111xP IPMI interface     | 2     |            | 65F6D55CEC |
| 10ec:816c | 17aa:5094 | Realtek... | RTL8111xP IPMI interface     | 2     |            | 99DDEF5ED9 |
| 10ec:816c | 17aa:511e | Realtek... | RTL8111xP IPMI interface     | 2     |            | C58E41C382 |
| 10ec:816c | 103c:83da | Realtek... | RTL8111xP IPMI interface     | 1     |            | F0FD278615 |
| 10ec:816c | 17aa:5091 | Realtek... | RTL8111xP IPMI interface     | 1     |            | 6D351FEC42 |
| 10ec:816c | 17aa:511f | Realtek... | RTL8111xP IPMI interface     | 1     |            | DF8C3622E3 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a36f | 8086:7270 | Intel      | Cannon Lake PCH Shared SRAM  | 544   |            | 085EF9E58D |
| 8086:9def | 8086:7270 | Intel      | Cannon Point-LP Shared SRAM  | 321   |            | 67F0B45A7A |
| 8086:9def |           | Intel      | Cannon Point-LP Shared SRAM  | 245   |            | 3678E02E46 |
| 8086:34ef |           | Intel      | Ice Lake-LP DRAM Controller  | 197   |            | C74557D180 |
| 10de:0a88 |           | Nvidia     | MCP79 Memory Controller      | 195   |            | 9BBF3BEFAB |
| 10de:0a89 |           | Nvidia     | MCP79 Memory Controller      | 177   |            | 25B2F96576 |
| 10de:0aa4 |           | Nvidia     | MCP79 Memory Controller      | 177   |            | 25B2F96576 |
| 8086:02ef | 8086:7270 | Intel      | Comet Lake PCH-LP Shared ... | 177   |            | BA8F31C45F |
| 8086:06ef | 8086:7270 | Intel      | Comet Lake PCH Shared SRAM   | 173   |            | 32F01CCAAB |
| 10de:0a98 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 171   |            | 25B2F96576 |
| 8086:a36f | 1025:1331 | Intel      | Cannon Lake PCH Shared SRAM  | 157   |            | BC9DC107D1 |
| 8086:9d21 | 17aa:3872 | Intel      | Sunrise Point-LP PMC         | 147   |            | F86520F5A7 |
| 8086:a36f | 1028:0905 | Intel      | Cannon Lake PCH Shared SRAM  | 142   |            | 58E43F0514 |
| 8086:02ef | 17aa:5079 | Intel      | Comet Lake PCH-LP Shared ... | 138   |            | A35AAAEB6D |
| 8086:9def | 17aa:2279 | Intel      | Cannon Point-LP Shared SRAM  | 127   |            | A01E524A66 |
| 8086:9d21 | 103c:8079 | Intel      | Sunrise Point-LP PMC         | 123   |            | 436E9BF227 |
| 8086:9d21 | 1025:1193 | Intel      | Sunrise Point-LP PMC         | 119   | intel_p... | 43BFEF3BCD |
| 8086:9d21 | 8086:7270 | Intel      | Sunrise Point-LP PMC         | 119   | intel_p... | DD20DE340C |
| 8086:a36f | 1028:087c | Intel      | Cannon Lake PCH Shared SRAM  | 114   |            | 0FA8C3ED0C |
| 8086:9def | 103c:8549 | Intel      | Cannon Point-LP Shared SRAM  | 111   |            | A814284F0B |
| 8086:9d21 | 1028:0810 | Intel      | Sunrise Point-LP PMC         | 110   |            | C01FA4B013 |
| 8086:9d21 | 17aa:225d | Intel      | Sunrise Point-LP PMC         | 109   |            | FEB7F2A285 |
| 8086:9d21 | 1028:07e6 | Intel      | Sunrise Point-LP PMC         | 99    | intel_p... | 5A56854746 |
| 8086:a121 | 1028:07be | Intel      | 100 Series/C230 Series Ch... | 99    |            | 69938C221E |
| 8086:9d21 | 1043:12d1 | Intel      | Sunrise Point-LP PMC         | 95    | intel_p... | 703D0F2090 |
| 8086:9d21 | 8086:9d21 | Intel      | Sunrise Point-LP PMC         | 95    | intel_p... | F3E5EBA0C2 |
| 8086:9def | 1028:08af | Intel      | Cannon Point-LP Shared SRAM  | 92    |            | 52DEA66C52 |
| 8086:02ef | 1028:0962 | Intel      | Comet Lake PCH-LP Shared ... | 91    |            | 8956FEE2F3 |
| 8086:9d21 | 1028:078b | Intel      | Sunrise Point-LP PMC         | 91    |            | 35BCBD121B |
| 8086:9d21 | 17aa:3845 | Intel      | Sunrise Point-LP PMC         | 89    |            | 4EB6B00CAC |
| 8086:9d21 | 17aa:225c | Intel      | Sunrise Point-LP PMC         | 86    |            | 2B4A1A20D9 |
| 8086:9d21 | 17aa:5068 | Intel      | Sunrise Point-LP PMC         | 86    |            | 2A70ED5588 |
| 8086:a36f | 1025:1264 | Intel      | Cannon Lake PCH Shared SRAM  | 86    |            | 7F70DE1771 |
| 8086:06ef | 1028:097d | Intel      | Comet Lake PCH Shared SRAM   | 84    |            | 994B96D25D |
| 10de:0d68 |           | Nvidia     | MCP89 Memory Controller      | 81    |            | 80E0B6AF9E |
| 10de:0d69 |           | Nvidia     | MCP89 Memory Controller      | 81    |            | 80E0B6AF9E |
| 10de:0d6d |           | Nvidia     | MCP89 Memory Controller      | 81    |            | 80E0B6AF9E |
| 10de:0d6e |           | Nvidia     | MCP89 Memory Controller      | 81    |            | 80E0B6AF9E |
| 10de:0d6f |           | Nvidia     | MCP89 Memory Controller      | 81    |            | 80E0B6AF9E |
| 10de:0d70 |           | Nvidia     | MCP89 Memory Controller      | 81    |            | 80E0B6AF9E |
| 10de:0d71 |           | Nvidia     | MCP89 Memory Controller      | 81    |            | 80E0B6AF9E |
| 10de:0d72 |           | Nvidia     | MCP89 Memory Controller      | 81    |            | 80E0B6AF9E |
| 10de:0d75 |           | Nvidia     | MCP89 Memory Controller      | 81    |            | 80E0B6AF9E |
| 10de:0d7b |           | Nvidia     | MCP89 Memory Controller      | 81    |            | 80E0B6AF9E |
| 8086:9d21 | 103c:832a | Intel      | Sunrise Point-LP PMC         | 80    |            | C9FD6887D4 |
| 8086:9d21 | 1025:1295 | Intel      | Sunrise Point-LP PMC         | 78    |            | 06114B7EB7 |
| 10de:0a88 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 76    |            | AE8948A236 |
| 10de:0a89 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 76    |            | AE8948A236 |
| 8086:9d21 | 103c:83b2 | Intel      | Sunrise Point-LP PMC         | 76    |            | E64AEB5FA4 |
| 8086:9def | 17aa:3809 | Intel      | Cannon Point-LP Shared SRAM  | 76    |            | 2DB4EBB6EF |
| 8086:a0ef |           | Intel      | Tiger Lake-LP Shared SRAM    | 76    |            | 4BF23FF82D |
| 8086:9d21 | 1025:115f | Intel      | Sunrise Point-LP PMC         | 74    | intel_p... | 7046D52A8D |
| 8086:9d21 | 17aa:2233 | Intel      | Sunrise Point-LP PMC         | 73    |            | 9EF824D802 |
| 8086:9d21 | 17aa:2245 | Intel      | Sunrise Point-LP PMC         | 73    | intel_p... | 80FB4514C5 |
| 8086:a36f | 17aa:3804 | Intel      | Cannon Lake PCH Shared SRAM  | 73    |            | EAF7694813 |
| 8086:9d21 | 1028:081c | Intel      | Sunrise Point-LP PMC         | 70    |            | ADB96FACBB |
| 8086:9d21 | 17aa:2258 | Intel      | Sunrise Point-LP PMC         | 70    |            | EEB181F50B |
| 8086:9d21 | 103c:84a6 | Intel      | Sunrise Point-LP PMC         | 68    | intel_p... | F0A8FA5E7A |
| 8086:9d21 | 17aa:3851 | Intel      | Sunrise Point-LP PMC         | 67    |            | 08D287D2E2 |
| 8086:a121 | 1028:0798 | Intel      | 100 Series/C230 Series Ch... | 67    |            | 1B93E3C1C9 |
| 8086:9d21 | 1025:1085 | Intel      | Sunrise Point-LP PMC         | 66    | intel_p... | 36C622EABC |
| 8086:9d21 | 1028:06b2 | Intel      | Sunrise Point-LP PMC         | 66    |            | F7EE774D7E |
| 8086:9d21 | 17aa:3816 | Intel      | Sunrise Point-LP PMC         | 66    |            | 60B294879D |
| 8086:a36f | 1028:0949 | Intel      | Cannon Lake PCH Shared SRAM  | 65    |            | 3165D77A8E |
| 8086:9d21 | 1028:075b | Intel      | Sunrise Point-LP PMC         | 63    |            | 8BB0307157 |
| 8086:a121 | 1025:118a | Intel      | 100 Series/C230 Series Ch... | 63    |            | E4762B54F7 |
| 8086:a36f | 17aa:3824 | Intel      | Cannon Lake PCH Shared SRAM  | 63    |            | 75C71D1F1E |
| 8086:a0ef | 1028:0991 | Intel      | Tiger Lake-LP Shared SRAM    | 62    |            | 22BC284F45 |
| 8086:9d21 | 1028:06dc | Intel      | Sunrise Point-LP PMC         | 60    |            | 69A251CC1F |
| 8086:9d21 | 1043:1d30 | Intel      | Sunrise Point-LP PMC         | 60    | intel_p... | 4DFA08CEB3 |
| 8086:a36f | 17aa:3801 | Intel      | Cannon Lake PCH Shared SRAM  | 60    |            | 2AD271E81F |
| 10de:0568 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] Mem... | 59    |            | B9B0C35DB8 |
| 10de:0754 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] Mem... | 59    |            | B9B0C35DB8 |
| 8086:9d21 | 1028:0767 | Intel      | Sunrise Point-LP PMC         | 59    |            | E551D622A8 |
| 8086:9def | 1028:08ca | Intel      | Cannon Point-LP Shared SRAM  | 59    |            | 8F25043C64 |
| 8086:a36f | 1028:086f | Intel      | Cannon Lake PCH Shared SRAM  | 59    |            | 28D725057F |
| 8086:9d21 | 17aa:5053 | Intel      | Sunrise Point-LP PMC         | 58    |            | 4DBC231901 |
| 8086:9d21 | 17aa:3869 | Intel      | Sunrise Point-LP PMC         | 56    |            | 8735C1E718 |
| 8086:a121 | 17aa:3819 | Intel      | 100 Series/C230 Series Ch... | 56    |            | A7045DEFDF |
| 8086:a36f | 103c:8478 | Intel      | Cannon Lake PCH Shared SRAM  | 56    |            | 362E1D3B99 |
| 8086:9d21 | 17aa:225a | Intel      | Sunrise Point-LP PMC         | 55    | intel_p... | 4C8C63DA2F |
| 8086:9def | 8086:9def | Intel      | Cannon Point-LP Shared SRAM  | 55    |            | 0E29003348 |
| 8086:9d21 | 17aa:3844 | Intel      | Sunrise Point-LP PMC         | 54    |            | 2BF6813AD9 |
| 8086:a121 | 17aa:222e | Intel      | 100 Series/C230 Series Ch... | 54    |            | 0F1A1FEEFE |
| 8086:a36f | 1025:1333 | Intel      | Cannon Lake PCH Shared SRAM  | 53    |            | 271C2188CB |
| 8086:9d21 | 1043:1670 | Intel      | Sunrise Point-LP PMC         | 51    | intel_p... | C0303B03F0 |
| 8086:9d21 | 144d:c804 | Intel      | Sunrise Point-LP PMC         | 51    |            | F3400508FB |
| 8086:9d21 | 103c:832b | Intel      | Sunrise Point-LP PMC         | 50    |            | A12360B5DC |
| 8086:a0ef | 17aa:5087 | Intel      | Tiger Lake-LP Shared SRAM    | 50    |            | BE67E01A7D |
| 8086:a36f | 1028:0906 | Intel      | Cannon Lake PCH Shared SRAM  | 50    |            | E549029931 |
| 8086:a36f | 17aa:2267 | Intel      | Cannon Lake PCH Shared SRAM  | 50    |            | 3A76CBDC51 |
| 8086:34ef | 17aa:3810 | Intel      | Ice Lake-LP DRAM Controller  | 49    |            | 5369A455A4 |
| 8086:9def | 17aa:2286 | Intel      | Cannon Point-LP Shared SRAM  | 49    |            | D3700D8667 |
| 8086:a36f | 1028:087d | Intel      | Cannon Lake PCH Shared SRAM  | 48    |            | 7F78C88EA8 |
| 8086:9d21 | 103c:837d | Intel      | Sunrise Point-LP PMC         | 46    | intel_p... | 9347A8D008 |
| 8086:34ef | 8086:7270 | Intel      | Ice Lake-LP DRAM Controller  | 45    |            | D3720F9145 |
| 8086:a36f | 17aa:229f | Intel      | Cannon Lake PCH Shared SRAM  | 45    |            | 3517455DF5 |
| 8086:34ef | 17aa:380f | Intel      | Ice Lake-LP DRAM Controller  | 44    |            | 7125C6F5DD |
| 8086:9d21 | 1043:1490 | Intel      | Sunrise Point-LP PMC         | 44    |            | 212240B258 |
| 8086:444e | 8086:444e | Intel      | Turbo Memory Controller      | 43    |            | 3332A4C510 |

### Modem (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:266d | 14f1:5423 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 29    | snd_int... | F48BAD44CD |
| 8086:266d | 1179:0001 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 22    | snd_int... | 61FEA93E97 |
| 8086:24c6 | 14f1:5422 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 13    | snd_int... | C4A1E26625 |
| 1039:7013 | 1025:0083 | Silicon... | AC'97 Modem Controller       | 12    | snd_int... | 5C114A6E41 |
| 8086:266d | 1025:006a | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 11    | snd_int... | FC6953A3F9 |
| 8086:266d | 103c:099c | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 11    | snd_int... | F54C45AB89 |
| 8086:266d | 1014:0574 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 9     | snd_int... | 67510CC1AA |
| 1002:4378 | 103c:3085 | AMD        | IXP SB400 AC'97 Modem Con... | 8     | snd_ati... | 280B8AF5CC |
| 1039:7013 | 1043:1816 | Silicon... | AC'97 Modem Controller       | 8     | snd_int... | AA92B168C5 |
| 8086:266d | 103c:0944 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 8     | snd_int... | 7F042FAA64 |
| 1002:4378 | 103c:3091 | AMD        | IXP SB400 AC'97 Modem Con... | 7     | snd_ati... | F01F51C47C |
| 8086:266d | 1025:0066 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 7     | snd_int... | 10A0D7E3A2 |
| 1002:4378 | 103c:30a4 | AMD        | IXP SB400 AC'97 Modem Con... | 6     | snd_ati... | 54E16F7626 |
| 8086:24c6 | 1014:0524 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 6     | snd_int... | 86CF78A3CF |
| 8086:24c6 | 1014:0559 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 5     | snd_int... | 2362291C05 |
| 8086:24c6 | 1014:055a | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 5     | snd_int... | 190737F754 |
| 8086:266d | 103c:0934 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 5     |            | BF69B6646D |
| 8086:266d | 103c:3082 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 5     |            | C98B9CF200 |
| 1002:4378 | 103c:308b | AMD        | IXP SB400 AC'97 Modem Con... | 4     | snd_ati... | 8CC604ABC2 |
| 1002:4378 | 103c:309b | AMD        | IXP SB400 AC'97 Modem Con... | 4     | snd_ati... | B64833B0B1 |
| 1002:4378 | 1043:1186 | AMD        | IXP SB400 AC'97 Modem Con... | 4     | snd_ati... | E298B642F1 |
| 8086:266d | 1014:0576 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 4     | snd_int... | E323E5FE53 |
| 8086:266d | 103c:30c4 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 4     | snd_int... | FE8A07348F |
| 8086:266d | 1179:ff31 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 4     | snd_int... | 875478A51A |
| 8086:266d | 144d:2115 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 4     | snd_int... | D7EE30EC16 |
| 1002:434d | 144d:2115 | AMD        | SB200 AC97 Modem Controller  | 3     | snd_ati... | F72BBFF4B7 |
| 1002:4378 | 1025:007e | AMD        | IXP SB400 AC'97 Modem Con... | 3     | snd_ati... | 60873D0A0E |
| 1002:4378 | 1025:0080 | AMD        | IXP SB400 AC'97 Modem Con... | 3     | snd_ati... | 8B304AF834 |
| 1039:7013 | 1025:0082 | Silicon... | AC'97 Modem Controller       | 3     |            | EDF0363AFE |
| 10b9:5457 | 104d:8158 | ULi Ele... | M5457 AC'97 Modem Controller | 3     |            | 7E4F74E16A |
| 10de:00d9 | 103c:006d | Nvidia     | nForce3 Audio                | 3     |            | 564B583FED |
| 1106:3068 | 1631:c015 | VIA Tec... | AC'97 Modem Controller       | 3     | snd_via... | C0B37BC3C3 |
| 1106:3068 | 1734:109b | VIA Tec... | AC'97 Modem Controller       | 3     | snd_via... | 2C34DEA0FC |
| 8086:24c6 | 103c:3080 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 3     | snd_int... | 47FF7370CC |
| 8086:24c6 | 1043:1826 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 3     | snd_int... | AE1C7D3DF6 |
| 8086:24c6 | 1179:0001 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 3     | snd_int... | FBF8640D2E |
| 8086:24c6 | 14e4:4d64 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 3     | snd_int... | 7CF738DA2E |
| 8086:266d | 103c:3081 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 3     | snd_int... | FDC2B74A29 |
| 8086:266d | 103c:309d | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 3     | snd_int... | 837230178B |
| 1002:4378 | 103c:30ae | AMD        | IXP SB400 AC'97 Modem Con... | 2     | snd_ati... | F91A752D4D |
| 1002:4378 | 1734:1092 | AMD        | IXP SB400 AC'97 Modem Con... | 2     | snd_ati... | 4D0D913872 |
| 1002:4378 | 1734:1098 | AMD        | IXP SB400 AC'97 Modem Con... | 2     | snd_ati... | 33762202EF |
| 1039:7013 | 104d:814e | Silicon... | AC'97 Modem Controller       | 2     | snd_int... | 11D39BBA01 |
| 10b9:5457 | 1071:8351 | ULi Ele... | M5457 AC'97 Modem Controller | 2     |            | 7806C7E5CD |
| 10de:00d9 | 1043:1856 | Nvidia     | nForce3 Audio                | 2     | snd_int... | 0A302BFAFD |
| 8086:2486 | 1014:0223 | Intel      | 82801CA/CAM AC'97 Modem C... | 2     | snd_int... | B6D0B8758E |
| 8086:2486 | 1179:0001 | Intel      | 82801CA/CAM AC'97 Modem C... | 2     | snd_int... | A79789524B |
| 8086:2486 | 134d:4c21 | Intel      | 82801CA/CAM AC'97 Modem C... | 2     |            | 5489DF545B |
| 8086:24c6 | 1014:0525 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 2     | snd_int... | 04747E3DF4 |
| 8086:24c6 | 1071:8089 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 2     | snd_int... | 227BF1BA1D |
| 8086:24c6 | 10cf:10d1 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 2     | snd_int... | EA732BEA27 |
| 8086:24c6 | 1179:ff31 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 2     | snd_int... | E9BD04F647 |
| 8086:266d | 1025:0081 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 2     | snd_int... | 34D9BE1B4A |
| 8086:266d | 103c:3080 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 2     | snd_int... | 0572E8425C |
| 8086:266d | 1462:0121 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 2     | snd_int... | 3E407C2B03 |
| 8086:266d | 17c0:10bb | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 2     | snd_int... | E8BFF6EA3D |
| 1002:434d | 1025:0052 | AMD        | SB200 AC97 Modem Controller  | 1     | snd_ati... | 856DF8910C |
| 1002:434d | 103c:006b | AMD        | SB200 AC97 Modem Controller  | 1     | snd_ati... | 5171D8BC33 |
| 1002:4378 | 1179:0001 | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 184C93E6DD |
| 1002:4378 | 1179:ff31 | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 654C60E971 |
| 1002:4378 | 1462:0131 | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 21B7740691 |
| 1002:4378 | 17c0:10bc | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | B115D6B061 |
| 1039:7013 | 1043:1696 | Silicon... | AC'97 Modem Controller       | 1     |            | D385784B22 |
| 1039:7013 | 1558:4201 | Silicon... | AC'97 Modem Controller       | 1     |            | 5B191FE82E |
| 1039:7013 | 1584:4003 | Silicon... | AC'97 Modem Controller       | 1     | snd_int... | CC188D0F25 |
| 1039:7013 | 1734:106c | Silicon... | AC'97 Modem Controller       | 1     |            | BFFEEEDE0D |
| 10b9:5457 | 103c:0850 | ULi Ele... | M5457 AC'97 Modem Controller | 1     |            | 4E9D284D9C |
| 1106:3068 | 1025:0046 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 80E120B3A5 |
| 1106:3068 | 1071:8381 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 9B37C1E94F |
| 1106:3068 | 1071:8666 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 179169EE59 |
| 1106:3068 | 1071:8889 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | E801E7B52C |
| 1106:3068 | 107b:0216 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 2B23BA49B1 |
| 1106:3068 | 1509:4070 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 4BEC822AEC |
| 1106:3068 | 1631:c009 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 06602F9CE5 |
| 1106:3068 | 1734:1054 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | A9DE326D18 |
| 1106:3068 | 1734:10ab | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | BEA6F4F694 |
| 1106:3068 | 1734:10ae | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 06ECBD156A |
| 11c1:0448 | 1014:0131 | LSI        | WinModem 56k                 | 1     |            | F004231106 |
| 11c1:0448 | 1668:2000 | LSI        | WinModem 56k                 | 1     |            | F379321C88 |
| 11c1:0449 | 1468:0410 | LSI        | L56xM+S [Mars-2] WinModem... | 1     |            | A27652B00A |
| 11c1:045c | 8086:2205 | LSI        | LT WinModem                  | 1     | serial     | 1B54E25E77 |
| 8086:2446 | 1025:1027 | Intel      | 82801BA/BAM AC'97 Modem C... | 1     |            | E0A83557FF |
| 8086:2446 | 1179:0001 | Intel      | 82801BA/BAM AC'97 Modem C... | 1     |            | 89EB89D54A |
| 8086:2486 | 1014:0227 | Intel      | 82801CA/CAM AC'97 Modem C... | 1     |            | 65D3C4C3C2 |
| 8086:2486 | 1043:1496 | Intel      | 82801CA/CAM AC'97 Modem C... | 1     |            | 1E7DA431AF |
| 8086:2486 | 104d:8142 | Intel      | 82801CA/CAM AC'97 Modem C... | 1     | snd_int... | 185FD8341C |
| 8086:2486 | 14c0:0012 | Intel      | 82801CA/CAM AC'97 Modem C... | 1     | snd_int... | A8AF42D6E7 |
| 8086:2486 | 14f1:5421 | Intel      | 82801CA/CAM AC'97 Modem C... | 1     |            | 4F9273C63C |
| 8086:24c6 | 1025:005a | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | 21602D608F |
| 8086:24c6 | 1025:0064 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | C7045484B1 |
| 8086:24c6 | 1025:0071 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | BBE6DD58A1 |
| 8086:24c6 | 103c:0890 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | 44DF53B183 |
| 8086:24c6 | 103c:08b0 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 316E375A5C |
| 8086:24c6 | 103c:3084 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | 24A093E347 |
| 8086:24c6 | 1043:1746 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 28A5B48A05 |
| 8086:24c6 | 104d:818c | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 7274BBB49F |
| 8086:24c6 | 1071:a001 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 9D5A19DCF4 |
| 8086:24c6 | 107b:0360 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | 53EC93715E |
| 8086:24c6 | 144d:2115 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 529607257E |
| 8086:24c6 | 144d:c00c | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 8BCCDD8350 |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:1570 | 14e4:1570 | Broadcom   | 720p FaceTime HD Camera      | 451   | bdc_pci    | 0C24CAF245 |
| 1022:15e2 | 1022:15e2 | AMD        | Raven/Raven2/FireFlight/R... | 444   | snd_pci... | BEE34D8394 |
| 8086:22b8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 321   | intel_a... | 2FBF6F153B |
| 1022:15e2 | 17aa:5081 | AMD        | Raven/Raven2/FireFlight/R... | 90    | snd_pci... | 273A5FF27D |
| 1022:15e2 | 19e5:3e19 | AMD        | Raven/Raven2/FireFlight/R... | 81    | snd_pci... | 1310B8ABF4 |
| 1022:15e2 | 17aa:507f | AMD        | Raven/Raven2/FireFlight/R... | 75    | snd_pci... | 8A34D739FD |
| 1022:15e2 | 17aa:3821 | AMD        | Raven/Raven2/FireFlight/R... | 66    | snd_pci... | 8A6E0EE275 |
| 1022:15e2 | 1025:134d | AMD        | Raven/Raven2/FireFlight/R... | 63    | snd_pci... | 6134BF279A |
| 1022:15e2 | 17aa:3807 | AMD        | Raven/Raven2/FireFlight/R... | 63    | snd_pci... | 497BF56CC6 |
| 1022:15e2 | 17aa:5124 | AMD        | Raven/Raven2/FireFlight/R... | 61    | snd_pci... | 52BA950565 |
| 1022:15e2 | 103c:84ae | AMD        | Raven/Raven2/FireFlight/R... | 58    | snd_pci... | 2E3861AEF3 |
| 1022:15e2 | 17aa:3812 | AMD        | Raven/Raven2/FireFlight/R... | 58    | snd_pci... | 3F7C00C1EF |
| 1022:15e2 | 1e21:1043 | AMD        | Raven/Raven2/FireFlight/R... | 58    | snd_pci... | 3802A77D98 |
| 1022:15e2 | 17aa:381c | AMD        | Raven/Raven2/FireFlight/R... | 57    | snd_pci... | 3CDC08297E |
| 1022:15e2 | 17aa:3814 | AMD        | Raven/Raven2/FireFlight/R... | 54    | snd_pci... | 8DB63E7A74 |
| 8086:5a88 |           | Intel      | Celeron N3350/Pentium N42... | 54    |            | AF4BBFFABF |
| 1022:15e2 | 103c:8730 | AMD        | Raven/Raven2/FireFlight/R... | 53    | snd_pci... | 1719B2DC9D |
| 1022:15e2 | 17aa:3813 | AMD        | Raven/Raven2/FireFlight/R... | 47    | snd_pci... | 09ADDF2612 |
| 1022:15e2 | 1d05:109f | AMD        | Raven/Raven2/FireFlight/R... | 45    | snd_pci... | 7242436545 |
| 1022:15e2 | 19e5:3e18 | AMD        | Raven/Raven2/FireFlight/R... | 44    | snd_pci... | C0B80E3276 |
| 1022:15e2 | 103c:8760 | AMD        | Raven/Raven2/FireFlight/R... | 42    | snd_pci... | 9C1DFCB679 |
| 1022:15e2 | 17aa:3822 | AMD        | Raven/Raven2/FireFlight/R... | 40    | snd_pci... | 86BC5DDC56 |
| 1022:15e2 | 17aa:507e | AMD        | Raven/Raven2/FireFlight/R... | 39    | snd_pci... | E9A8FB1275 |
| 1022:15e2 | 103c:85ea | AMD        | Raven/Raven2/FireFlight/R... | 38    | snd_pci... | E8781DB5AB |
| 1022:15e2 | 1025:142b | AMD        | Raven/Raven2/FireFlight/R... | 37    | snd_pci... | BCE3E39F4C |
| 1022:15e2 | 103c:86fd | AMD        | Raven/Raven2/FireFlight/R... | 34    | snd_pci... | 5BB4E443F9 |
| 8086:22b8 | 103c:813e | Intel      | Atom/Celeron/Pentium Proc... | 33    | intel_a... | 0A44B96544 |
| 1022:15e2 | 17aa:380f | AMD        | Raven/Raven2/FireFlight/R... | 31    | snd_pci... | 8C961555FE |
| 1022:15e2 | 1025:134f | AMD        | Raven/Raven2/FireFlight/R... | 30    | snd_pci... | 5EDDDC1E2C |
| 1022:15e2 | 1025:1461 | AMD        | Raven/Raven2/FireFlight/R... | 30    | snd_pci... | 264BADF289 |
| 1022:15e2 | 103c:85b3 | AMD        | Raven/Raven2/FireFlight/R... | 29    | snd_pci... | AE1811A242 |
| 1022:15e2 | 17aa:5084 | AMD        | Raven/Raven2/FireFlight/R... | 29    | snd_pci... | 037A558C7D |
| 1022:15e2 | 17aa:5125 | AMD        | Raven/Raven2/FireFlight/R... | 27    | snd_pci... | 8E00E1F239 |
| 1022:15e2 | 1025:1456 | AMD        | Raven/Raven2/FireFlight/R... | 26    | snd_pci... | 09F6196E70 |
| 1022:15e2 | 103c:887a | AMD        | Raven/Raven2/FireFlight/R... | 26    | snd_pci... | 2BA5AE42BB |
| 8086:22b8 | 1297:2063 | Intel      | Atom/Celeron/Pentium Proc... | 26    | intel_a... | 0D1AB84E09 |
| 1022:15e2 | 19e5:3e06 | AMD        | Raven/Raven2/FireFlight/R... | 25    | snd_pci... | 9BEA49D841 |
| 1022:15e2 | 1a0e:1043 | AMD        | Raven/Raven2/FireFlight/R... | 25    | snd_pci... | 9E88464633 |
| 1022:15e2 | 1025:1455 | AMD        | Raven/Raven2/FireFlight/R... | 24    | snd_pci... | F581CF8319 |
| 1022:15e2 | 17aa:3823 | AMD        | Raven/Raven2/FireFlight/R... | 24    | snd_pci... | 214D892F21 |
| 1022:15e2 | 1e83:3e33 | AMD        | Raven/Raven2/FireFlight/R... | 23    | snd_pci... | 1E059DB869 |
| 1022:15e2 | 19e5:3e14 | AMD        | Raven/Raven2/FireFlight/R... | 22    | snd_pci... | C62BB4ADC9 |
| 1022:15e2 | 103c:85e0 | AMD        | Raven/Raven2/FireFlight/R... | 20    | snd_pci... | 1A23A6605B |
| 1022:15e2 | 17aa:5097 | AMD        | Raven/Raven2/FireFlight/R... | 19    | snd_pci... | 8D45D9544E |
| 1022:15e2 | 1028:09f5 | AMD        | Raven/Raven2/FireFlight/R... | 18    | snd_pci... | B11BD373D3 |
| 1022:15e2 | 1043:1f11 | AMD        | Raven/Raven2/FireFlight/R... | 18    | snd_pci... | 0F6D7BCF66 |
| 1022:15e2 | 103c:8706 | AMD        | Raven/Raven2/FireFlight/R... | 17    | snd_pci... | D39BE3EDBA |
| 1022:15e2 | 152d:1273 | AMD        | Raven/Raven2/FireFlight/R... | 17    | snd_pci... | BBF16A7212 |
| 1022:15e2 | 103c:87b1 | AMD        | Raven/Raven2/FireFlight/R... | 16    | snd_pci... | CB7D97FD9E |
| 1022:15e2 | 17aa:380d | AMD        | Raven/Raven2/FireFlight/R... | 16    | snd_pci... | 594815BB9D |
| 1022:15e2 | 1025:1378 | AMD        | Raven/Raven2/FireFlight/R... | 15    | snd_pci... | 589BEB7652 |
| 1022:15e2 | 17aa:381f | AMD        | Raven/Raven2/FireFlight/R... | 15    | snd_pci... | 8948989999 |
| 1022:15e2 | 17aa:5127 | AMD        | Raven/Raven2/FireFlight/R... | 15    | snd_pci... | 7065F7BB74 |
| 1022:15e2 | 103c:86d5 | AMD        | Raven/Raven2/FireFlight/R... | 14    | snd_pci... | 9B0872B3D4 |
| 1022:15e2 | 1043:1e8e | AMD        | Raven/Raven2/FireFlight/R... | 14    | snd_pci... | 3F7A2585FE |
| 14e4:1615 | 14e4:1615 | Broadcom   | BCM70015 Video Decoder [C... | 14    | crystalhd  | 89BBAFA02E |
| 8086:1919 | 8086:1919 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 14    | ipu3_imgu  | 3B25F1B84A |
| 8086:22b8 | 1043:1bdd | Intel      | Atom/Celeron/Pentium Proc... | 14    | atomisp    | C518746ECE |
| 1022:15e2 | 1028:0a12 | AMD        | Raven/Raven2/FireFlight/R... | 13    | snd_pci... | 38D22B1058 |
| 1022:15e2 | 103c:879e | AMD        | Raven/Raven2/FireFlight/R... | 13    | snd_pci... | A94D17F64B |
| 1022:15e2 | 103c:87cf | AMD        | Raven/Raven2/FireFlight/R... | 13    | snd_pci... | EDE284A3A3 |
| 1022:15e2 | 17aa:5082 | AMD        | Raven/Raven2/FireFlight/R... | 13    | snd_pci... | 534A4C683F |
| 1022:15e2 | 17aa:5126 | AMD        | Raven/Raven2/FireFlight/R... | 13    | snd_pci... | 6B6B00F95C |
| 1022:15e2 | 19e5:3e10 | AMD        | Raven/Raven2/FireFlight/R... | 13    | snd_pci... | 9C73A8D7D6 |
| 8086:9d32 | 8086:9d32 | Intel      | CSI-2 Host Controller        | 13    | ipu3_cio2  | 8C051A0CE9 |
| 1022:15e2 | 103c:84d2 | AMD        | Raven/Raven2/FireFlight/R... | 12    | snd_pci... | 838188303A |
| 1022:15e2 | 103c:87c5 | AMD        | Raven/Raven2/FireFlight/R... | 12    | snd_pci... | 55F8110D0E |
| 1022:15e2 | 1558:a500 | AMD        | Raven/Raven2/FireFlight/R... | 12    | snd_pci... | 769328E65E |
| 1022:15e2 | 17aa:3824 | AMD        | Raven/Raven2/FireFlight/R... | 12    | snd_pci... | DCE0B57CDC |
| 8086:1919 | 103c:80fc | Intel      | Xeon E3-1200 v5/E3-1500 v... | 12    | ipu3_imgu  | 89E5AB8846 |
| 8086:1919 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 12    | ipu3_imgu  | 3B463B959A |
| 8086:9d32 | 103c:80fc | Intel      | CSI-2 Host Controller        | 12    | ipu3_cio2  | 89E5AB8846 |
| 1022:15e2 | 103c:86d4 | AMD        | Raven/Raven2/FireFlight/R... | 11    | snd_pci... | 98874D48B2 |
| 1022:15e2 | 17aa:382c | AMD        | Raven/Raven2/FireFlight/R... | 11    | snd_pci... | C7A45F22C5 |
| 1022:15e2 | 1d72:1953 | AMD        | Raven/Raven2/FireFlight/R... | 11    | snd_pci... | 23546F7A48 |
| 1022:15e2 | 1025:1233 | AMD        | Raven/Raven2/FireFlight/R... | 10    | snd_pci... | 8DF5E13FC0 |
| 1022:15e2 | 103c:8786 | AMD        | Raven/Raven2/FireFlight/R... | 10    | snd_pci... | F19AD7CBA2 |
| 1022:15e2 | 103c:87b2 | AMD        | Raven/Raven2/FireFlight/R... | 10    | snd_pci... | 2C5F518CC8 |
| 1022:15e2 | 1462:12b5 | AMD        | Raven/Raven2/FireFlight/R... | 10    | snd_pci... | 3C8835ECC1 |
| 1022:15e2 | 1462:12c8 | AMD        | Raven/Raven2/FireFlight/R... | 10    | snd_pci... | A904DAF48D |
| 1022:15e2 | 17aa:3826 | AMD        | Raven/Raven2/FireFlight/R... | 10    | snd_pci... | A376D9680F |
| 1022:15e2 | 1025:151e | AMD        | Raven/Raven2/FireFlight/R... | 9     | snd_pci... | F6DDC3A2DA |
| 1022:15e2 | 103c:88dd | AMD        | Raven/Raven2/FireFlight/R... | 9     | snd_pci... | 8512EE02BD |
| 1022:15e2 | 1043:1602 | AMD        | Raven/Raven2/FireFlight/R... | 9     | snd_pci... | 8A14F4F8CE |
| 1022:15e2 | 17aa:3829 | AMD        | Raven/Raven2/FireFlight/R... | 9     | snd_pci... | 9276790A36 |
| 1022:15e2 | 17aa:5083 | AMD        | Raven/Raven2/FireFlight/R... | 9     | snd_pci... | 01362B36BF |
| 1022:15e2 | 1d72:2031 | AMD        | Raven/Raven2/FireFlight/R... | 9     | snd_pci... | 99EFF2370B |
| 1022:15e2 | 17aa:3839 | AMD        | Raven/Raven2/FireFlight/R... | 8     | snd_pci... | 91C65CBE64 |
| 1022:15e2 | 17aa:5094 | AMD        | Raven/Raven2/FireFlight/R... | 8     | snd_pci... | 11CD74E647 |
| 1022:15e2 | 1d72:1951 | AMD        | Raven/Raven2/FireFlight/R... | 8     | snd_pci... | 21F95CA802 |
| 14e4:1612 | 14e4:2612 | Broadcom   | BCM70012 Video Decoder [C... | 8     |            | 80E44F2CF2 |
| 8086:0f38 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 8     | intel_a... | 06D0750E6E |
| 8086:9a19 | 8086:2097 | Intel      | Multimedia controller        | 8     | intel_i... | 4BFFB79E7C |
| 1022:15e2 | 1043:1662 | AMD        | Raven/Raven2/FireFlight/R... | 7     | snd_pci... | E197AB281B |
| 1022:15e2 | 17aa:3804 | AMD        | Raven/Raven2/FireFlight/R... | 7     | snd_pci... | D89008EF64 |
| 1022:15e2 | 17aa:382f | AMD        | Raven/Raven2/FireFlight/R... | 7     | snd_pci... | 644553839A |
| 1022:15e2 | 103c:8787 | AMD        | Raven/Raven2/FireFlight/R... | 6     | snd_pci... | 2412314AD9 |
| 1022:15e2 | 103c:87b7 | AMD        | Raven/Raven2/FireFlight/R... | 6     | snd_pci... | B754C74B11 |
| 1022:15e2 | 103c:8919 | AMD        | Raven/Raven2/FireFlight/R... | 6     | snd_pci... | D49638CC86 |
| 1022:15e2 | 17aa:3811 | AMD        | Raven/Raven2/FireFlight/R... | 6     | snd_pci... | D3F86F70AE |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8168 | 1043:200f | Realtek... | RTL8111/8168/8411 PCI Exp... | 1563  | r8169      | B92CD04EE7 |
| 10ec:8136 | 1043:200f | Realtek... | RTL810xE PCI Express Fast... | 541   | r8169      | 9B382500C5 |
| 10ec:8168 | 1043:208f | Realtek... | RTL8111/8168/8411 PCI Exp... | 475   | r8169      | 32F01CCAAB |
| 14e4:16b5 | 1025:0647 | Broadcom   | NetLink BCM57785 Gigabit ... | 410   | tg3        | 82E60126C9 |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 355   | r8169      | 403E735C43 |
| 14e4:16b4 | 14e4:16b4 | Broadcom   | NetXtreme BCM57765 Gigabi... | 297   | tg3        | 6E17FB6EA4 |
| 10ec:8168 | 1043:16d5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 273   | r8169      | 9D10643A15 |
| 197b:0250 | 1043:1905 | JMicron... | JMC250 PCI Express Gigabi... | 235   | jme        | D5A8ADB8C9 |
| 1969:2062 | 1043:8468 | Attansi... | AR8152 v2.0 Fast Ethernet    | 229   | atl1c      | 95653B7969 |
| 1969:1083 | 1043:1851 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 220   | atl1c      | 997A879973 |
| 8086:155a | 17aa:2214 | Intel      | Ethernet Connection I218-LM  | 214   | e1000e     | F802ABEF07 |
| 14e4:16b5 | 1025:0504 | Broadcom   | NetLink BCM57785 Gigabit ... | 213   | tg3        | F86CA58100 |
| 8086:15a2 | 17aa:2226 | Intel      | Ethernet Connection (3) I... | 187   | e1000e     | 55689E67B3 |
| 14e4:1692 | 1025:036d | Broadcom   | NetLink BCM57780 Gigabit ... | 183   | tg3        | D9521929DA |
| 10ec:8168 | 17aa:5002 | Realtek... | RTL8111/8168/8411 PCI Exp... | 177   | r8169      | 779684E41D |
| 1969:1063 | 1043:1820 | Qualcom... | AR8131 Gigabit Ethernet      | 166   | atl1c      | E3FC4E0622 |
| 10de:0ab0 | 10de:cb79 | Nvidia     | MCP79 Ethernet               | 165   | forcedeth  | 25B2F96576 |
| 10ec:8136 | 1179:ff00 | Realtek... | RTL810xE PCI Express Fast... | 163   | r8169      | 01EB2C3459 |
| 8086:156f | 17aa:2233 | Intel      | Ethernet Connection I219-LM  | 163   | e1000e     | 623506F87F |
| 14e4:1693 | 1025:011c | Broadcom   | NetLink BCM5787M Gigabit ... | 160   | tg3        | 8592F1650F |
| 1969:1090 | 17aa:3979 | Qualcom... | AR8162 Fast Ethernet         | 156   | alx        | EE0A6FC9CA |
| 10ec:8168 | 1025:1331 | Realtek... | RTL8111/8168/8411 PCI Exp... | 151   | r8169      | BC9DC107D1 |
| 10ec:8168 | 17aa:3812 | Realtek... | RTL8111/8168/8411 PCI Exp... | 151   | r8169      | 0CDC6E9D84 |
| 1969:2062 | 17aa:3979 | Qualcom... | AR8152 v2.0 Fast Ethernet    | 151   | atl1c      | D1D57448C4 |
| 10ec:8168 | 17aa:38bb | Realtek... | RTL8111/8168/8411 PCI Exp... | 147   | r8169      | F86520F5A7 |
| 14e4:16b3 | 1025:0775 | Broadcom   | NetXtreme BCM57786 Gigabi... | 145   | tg3        | 921FC6B490 |
| 14e4:1698 | 1025:0207 | Broadcom   | NetLink BCM5784M Gigabit ... | 140   | tg3        | 9B324D7185 |
| 10ec:8136 | 17aa:3975 | Realtek... | RTL810xE PCI Express Fast... | 137   | r8169      | 16EBDC4388 |
| 10ec:8168 | 17aa:5079 | Realtek... | RTL8111/8168/8411 PCI Exp... | 137   | r8169      | A35AAAEB6D |
| 11ab:4381 | 104d:9071 | Marvell... | Yukon Optima 88E8059 [PCI... | 137   | sky2       | A18FB33A6F |
| 10ec:8136 | 1179:ff1e | Realtek... | RTL810xE PCI Express Fast... | 131   | r8169      | A955D2E293 |
| 10ec:8136 | 1028:04b0 | Realtek... | RTL810xE PCI Express Fast... | 129   | r8169      | 532A1D3D01 |
| 1969:1026 | 1043:14f5 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 127   | atl1e      | 0DC4D38ED2 |
| 10ec:8168 | 1b0a:20d9 | Realtek... | RTL8111/8168/8411 PCI Exp... | 126   | r8169      | 1EDD4700FD |
| 10ec:8168 | 1025:1193 | Realtek... | RTL8111/8168/8411 PCI Exp... | 121   | r8169      | 43BFEF3BCD |
| 10ec:8136 | 10ec:0123 | Realtek... | RTL810xE PCI Express Fast... | 119   | r8169      | 153E9A44D1 |
| 10ec:8168 | 1025:0866 | Realtek... | RTL8111/8168/8411 PCI Exp... | 118   | r8169      | 11EBF2008B |
| 8086:153a | 17aa:220e | Intel      | Ethernet Connection I217-LM  | 118   | e1000e     | 36F407C3AA |
| 10ec:8168 | 103c:8330 | Realtek... | RTL8111/8168/8411 PCI Exp... | 117   | r8169      | 18CEA74915 |
| 1969:1062 | 1043:838a | Qualcom... | AR8132 Fast Ethernet         | 116   | atl1c      | E74DC83F0A |
| 10ec:8168 | 17aa:388a | Realtek... | RTL8111/8168/8411 PCI Exp... | 114   | r8169      | 4EB6B00CAC |
| 8086:155a | 103c:198f | Intel      | Ethernet Connection I218-LM  | 114   | e1000e     | CECD552E89 |
| 10ec:8168 | 1043:1277 | Realtek... | RTL8111/8168/8411 PCI Exp... | 112   | r8169      | FC712846D9 |
| 10ec:8136 | 1028:0810 | Realtek... | RTL810xE PCI Express Fast... | 110   | r8169      | C01FA4B013 |
| 14e4:1713 | 17aa:3a23 | Broadcom   | NetLink BCM5906M Fast Eth... | 110   | tg3        | C53BA56444 |
| 10ec:8168 | 17aa:3816 | Realtek... | RTL8111/8168/8411 PCI Exp... | 109   | r8169      | 1387FAB9FE |
| 11ab:4354 | 1028:02aa | Marvell... | 88E8040 PCI-E Fast Ethern... | 109   | sky2       | E8E9A85406 |
| 10ec:8168 | 104d:908b | Realtek... | RTL8111/8168/8411 PCI Exp... | 106   | r8169      | 11EF4D4BAF |
| 10ec:8168 | 1025:1094 | Realtek... | RTL8111/8168/8411 PCI Exp... | 105   | r8169      | 89135238FE |
| 14e4:1692 | 1025:033d | Broadcom   | NetLink BCM57780 Gigabit ... | 105   | tg3        | 55BA94A26E |
| 1969:10a0 | 17aa:3802 | Qualcom... | QCA8172 Fast Ethernet        | 104   | alx        | 23F236B807 |
| 10ec:8136 | 1179:fb37 | Realtek... | RTL810xE PCI Express Fast... | 103   | r8169      | BB9C65380C |
| 1969:1083 | 1043:13c7 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 100   | atl1c      | 966E771791 |
| 10ec:8168 | 144d:c606 | Realtek... | RTL8111/8168/8411 PCI Exp... | 99    | r8169      | 89DF37A291 |
| 1969:1091 | 1043:14c7 | Qualcom... | AR8161 Gigabit Ethernet      | 99    | alx        | BC26A9B439 |
| 14e4:1673 | 1028:01f9 | Broadcom   | NetXtreme BCM5755M Gigabi... | 97    | tg3        | 6DBCD5A1C8 |
| 10ec:8136 | 17aa:3830 | Realtek... | RTL810xE PCI Express Fast... | 96    | r8169      | 184B909FC0 |
| 11ab:436a | 11ab:00ba | Marvell... | 88E8058 PCI-E Gigabit Eth... | 96    | sky2       | 34FC60E37E |
| 10ec:8136 | 10ec:8136 | Realtek... | RTL810xE PCI Express Fast... | 94    | r8169      | 1BF61C0698 |
| 10ec:8168 | 17aa:3854 | Realtek... | RTL8111/8168/8411 PCI Exp... | 94    | r8169      | 60B294879D |
| 8086:153a | 17aa:2210 | Intel      | Ethernet Connection I217-LM  | 92    | e1000e     | 5026826DBE |
| 10ec:8168 | 1043:11f5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 91    | r8169      | B53C1FC258 |
| 1969:2060 | 1179:ff1e | Qualcom... | AR8152 v1.1 Fast Ethernet    | 91    | atl1c      | 39F61AD9FD |
| 10ec:8168 | 103c:84ac | Realtek... | RTL8111/8168/8411 PCI Exp... | 90    | r8169      | 3A06ECCCAA |
| 8086:15be | 17aa:2279 | Intel      | Ethernet Connection (6) I... | 90    | e1000e     | A01E524A66 |
| 10ec:8168 | 144d:c0da | Realtek... | RTL8111/8168/8411 PCI Exp... | 89    | r8169      | DBF7A80E6C |
| 10ec:8168 | 17aa:5072 | Realtek... | RTL8111/8168/8411 PCI Exp... | 88    | r8169      | 3678E02E46 |
| 10ec:8168 | 17aa:5081 | Realtek... | RTL8111/8168/8411 PCI Exp... | 88    | r8169      | 273A5FF27D |
| 10ec:8136 | 103c:3577 | Realtek... | RTL810xE PCI Express Fast... | 86    | r8169      | 8E3CEB5DB9 |
| 1969:1091 | 1043:1477 | Qualcom... | AR8161 Gigabit Ethernet      | 86    | alx        | 1D158DC1F0 |
| 10ec:8168 | 1025:1264 | Realtek... | RTL8111/8168/8411 PCI Exp... | 85    | r8169      | 7F70DE1771 |
| 11ab:4354 | 1028:022f | Marvell... | 88E8040 PCI-E Fast Ethern... | 85    | sky2       | 38B4BA227C |
| 8086:15a2 | 103c:2216 | Intel      | Ethernet Connection (3) I... | 85    | e1000e     | FFB40F821B |
| 10ec:8136 | 17aa:392e | Realtek... | RTL810xE PCI Express Fast... | 84    | r8169      | B9412E1AB2 |
| 10ec:8168 | 1043:205f | Realtek... | RTL8111/8168/8411 PCI Exp... | 84    | r8169      | F108C8522F |
| 10ec:8168 | 17aa:3975 | Realtek... | RTL8111/8168/8411 PCI Exp... | 83    | r8169      | F305E4AB46 |
| 10ec:8168 | 17aa:3821 | Realtek... | RTL8111/8168/8411 PCI Exp... | 82    | r8169      | 2ECC44141A |
| 10ec:8168 | 17aa:5068 | Realtek... | RTL8111/8168/8411 PCI Exp... | 82    | r8169      | 2A70ED5588 |
| 10ec:8168 | 1025:1295 | Realtek... | RTL8111/8168/8411 PCI Exp... | 80    | r8169      | 06114B7EB7 |
| 10ec:8168 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 80    | r8169      | 02E59A3759 |
| 10ec:8168 | 144d:c652 | Realtek... | RTL8111/8168/8411 PCI Exp... | 80    | r8169      | BCA6D30092 |
| 8086:155a | 1028:05cb | Intel      | Ethernet Connection I218-LM  | 80    | e1000e     | 98C988645F |
| 10ec:8168 | 1025:1192 | Realtek... | RTL8111/8168/8411 PCI Exp... | 79    | r8169      | F5F4E2457B |
| 10ec:8168 | 103c:832a | Realtek... | RTL8111/8168/8411 PCI Exp... | 79    | r8169      | C9FD6887D4 |
| 14e4:1684 | 14e4:1684 | Broadcom   | NetXtreme BCM5764M Gigabi... | 79    | tg3        | 80E0B6AF9E |
| 8086:156f | 103c:8079 | Intel      | Ethernet Connection I219-LM  | 78    | e1000e     | 71F0D8F5BB |
| 10ec:8168 | 1025:098a | Realtek... | RTL8111/8168/8411 PCI Exp... | 77    | r8169      | CCE67D37AA |
| 10ec:8168 | 17aa:380a | Realtek... | RTL8111/8168/8411 PCI Exp... | 77    | r8169      | 60E3FE1197 |
| 10ec:8136 | 1028:0651 | Realtek... | RTL810xE PCI Express Fast... | 76    | r8169      | 0862DC626B |
| 1969:1062 | 1025:0212 | Qualcom... | AR8132 Fast Ethernet         | 76    | atl1c      | 9D4F7A1A4B |
| 10ec:8136 | 1028:078a | Realtek... | RTL810xE PCI Express Fast... | 75    | r8169      | 7901CD9339 |
| 8086:15a2 | 1028:062e | Intel      | Ethernet Connection (3) I... | 75    | e1000e     | 91837758AC |
| 10ec:8168 | 17aa:380b | Realtek... | RTL8111/8168/8411 PCI Exp... | 74    | r8169      | 3CDDE1061C |
| 10ec:8168 | 17aa:507f | Realtek... | RTL8111/8168/8411 PCI Exp... | 74    | r8169      | 8A34D739FD |
| 8086:153b | 103c:1993 | Intel      | Ethernet Connection I217-V   | 74    | e1000e     | 170DD8B241 |
| 10ec:8136 | 1028:0597 | Realtek... | RTL810xE PCI Express Fast... | 73    | r8169      | 5EBA5CDCBF |
| 10ec:8139 | 1043:1045 | Realtek... | RTL-8100/8101L/8139 PCI F... | 73    | 8139too... | 41130A006F |
| 10ec:8168 | 103c:17f6 | Realtek... | RTL8111/8168/8411 PCI Exp... | 73    | r8169      | E12D7E47E6 |
| 10ec:8168 | 17aa:38cf | Realtek... | RTL8111/8168/8411 PCI Exp... | 73    | r8169      | EAF7694813 |
| 10ec:8136 | 1028:05f3 | Realtek... | RTL810xE PCI Express Fast... | 70    | r8169      | 0F2394B49D |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2723 | 8086:0084 | Intel      | Wi-Fi 6 AX200                | 1175  | iwlwifi    | F581CF8319 |
| 8086:0085 | 8086:1311 | Intel      | Centrino Advanced-N 6205 ... | 1026  | iwlwifi    | A120083D3C |
| 168c:002b | 1a3b:1089 | Qualcom... | AR9285 Wireless Network A... | 970   | ath9k      | E3FC4E0622 |
| 168c:0042 | 11ad:08a6 | Qualcom... | QCA9377 802.11ac Wireless... | 920   | ath10k_pci | CFA7B4AF8F |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 829   | iwlwifi    | 9C8BB9558A |
| 8086:a370 | 8086:0034 | Intel      | Cannon Lake PCH CNVi WiFi    | 743   | iwlwifi    | D55AC505B9 |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 732   | iwlwifi    | EEB181F50B |
| 168c:0042 | 17aa:0901 | Qualcom... | QCA9377 802.11ac Wireless... | 698   | ath10k_pci | 08D287D2E2 |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 631   | iwlwifi    | 4EB6B00CAC |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 620   | rtl8821ce  | 3A06ECCCAA |
| 10ec:d723 | 103c:8319 | Realtek... | RTL8723DE Wireless Networ... | 612   | rtl8723de  | F4D2F1104E |
| 168c:0042 | 1028:1810 | Qualcom... | QCA9377 802.11ac Wireless... | 605   | ath10k_pci | 60F4AC8CC5 |
| 8086:9df0 | 8086:0034 | Intel      | Cannon Point-LP CNVi [Wir... | 583   | iwlwifi    | A01E524A66 |
| 1814:3290 | 103c:18ec | Ralink     | RT3290 Wireless 802.11n 1... | 542   | rt2800pci  | FBF77D8C63 |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 538   | iwlwifi    | 93C1D9BD4F |
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 489   | iwlwifi    | 9347A8D008 |
| 8086:2723 | 8086:0080 | Intel      | Wi-Fi 6 AX200                | 488   | iwlwifi    | E9A8FB1275 |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 442   | iwlwifi    | 1069B24865 |
| 8086:088e | 8086:4060 | Intel      | Centrino Advanced-N 6235     | 425   | iwlwifi    | 95C381CCD9 |
| 168c:0036 | 11ad:0642 | Qualcom... | QCA9565 / AR9565 Wireless... | 411   | ath9k      | 11EBF2008B |
| 8086:02f0 | 8086:0074 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 403   | iwlwifi    | A35AAAEB6D |
| 8086:4237 | 8086:1211 | Intel      | PRO/Wireless 5100 AGN [Sh... | 392   | iwlwifi    | 9A7BE426F5 |
| 168c:0036 | 1028:020c | Qualcom... | QCA9565 / AR9565 Wireless... | 386   | ath9k      | 0F2394B49D |
| 168c:0032 | 1a3b:2c97 | Qualcom... | AR9485 Wireless Network A... | 380   | ath9k      | 58CC91ABA3 |
| 8086:3165 | 8086:4410 | Intel      | Wireless 3165                | 378   | iwlwifi    | 8894639B19 |
| 168c:003e | 1a56:1535 | Qualcom... | QCA6174 802.11ac Wireless... | 370   | ath10k_pci | EDD545A455 |
| 8086:a0f0 | 8086:0074 | Intel      | Wi-Fi 6 AX201                | 370   | iwlwifi    | EFDB9E6636 |
| 8086:08b2 | 8086:c270 | Intel      | Wireless 7260                | 367   | iwlwifi    | F802ABEF07 |
| 168c:0032 | 144d:4105 | Qualcom... | AR9485 Wireless Network A... | 363   | ath9k      | 2FDE85DC91 |
| 168c:0036 | 1028:020e | Qualcom... | QCA9565 / AR9565 Wireless... | 363   | ath9k      | 5900E800AA |
| 8086:4239 | 8086:1311 | Intel      | Centrino Advanced-N 6200     | 363   | iwlwifi    | 8B21B7CFFE |
| 8086:4222 | 8086:1001 | Intel      | PRO/Wireless 3945ABG [Gol... | 361   | iwl3945    | 1517AC0D45 |
| 8086:4232 | 8086:1201 | Intel      | WiFi Link 5100               | 358   | iwlwifi    | 9B324D7185 |
| 14e4:4365 | 17aa:0611 | Broadcom   | BCM43142 802.11b/g/n         | 351   | wl         | 779684E41D |
| 8086:0082 | 8086:1321 | Intel      | Centrino Advanced-N 6205 ... | 350   | iwlwifi    | D040F874C9 |
| 8086:24fd | 8086:0050 | Intel      | Wireless 8265 / 8275         | 338   | iwlwifi    | 3D0FD285B6 |
| 10ec:c821 | 17aa:c024 | Realtek... | RTL8821CE 802.11ac PCIe W... | 335   | rtl8821ce  | 8DB63E7A74 |
| 168c:002b | 17aa:30a1 | Qualcom... | AR9285 Wireless Network A... | 328   | ath9k      | EE0A6FC9CA |
| 8086:2526 | 8086:0014 | Intel      | Wireless-AC 9260             | 328   | iwlwifi    | FFB40F821B |
| 168c:0034 | 105b:e052 | Qualcom... | AR9462 Wireless Network A... | 321   | ath9k      | 7302DC6BE1 |
| 8086:4238 | 8086:1111 | Intel      | Centrino Ultimate-N 6300     | 317   | iwlwifi    | 69A252CCD6 |
| 168c:003e | 11ad:0807 | Qualcom... | QCA6174 802.11ac Wireless... | 313   | ath10k_pci | 66255CA7B5 |
| 168c:002b | 1a3b:2c37 | Qualcom... | AR9285 Wireless Network A... | 308   | ath9k      | 997A879973 |
| 168c:002e | 105b:e034 | Qualcom... | AR9287 Wireless Network A... | 304   | ath9k      | 7EAEAE034C |
| 8086:06f0 | 8086:0074 | Intel      | Comet Lake PCH CNVi WiFi     | 302   | iwlwifi    | 32F01CCAAB |
| 8086:0887 | 8086:4062 | Intel      | Centrino Wireless-N 2230     | 298   | iwlwifi    | EBEA056239 |
| 8086:422b | 8086:1121 | Intel      | Centrino Ultimate-N 6300     | 297   | iwlwifi    | F442DF91A1 |
| 8086:08b1 | 8086:4470 | Intel      | Wireless 7260                | 295   | iwlwifi    | EC8AF5F350 |
| 10ec:b723 | 17aa:b736 | Realtek... | RTL8723BE PCIe Wireless N... | 289   | rtl8723be  | B76F24F640 |
| 14e4:4727 | 103c:1483 | Broadcom   | BCM4313 802.11bgn Wireles... | 289   | wl         | F696958F46 |
| 14e4:4315 | 1028:000c | Broadco... | BCM4312 802.11b/g LP-PHY     | 288   | wl         | E475348B1E |
| 8086:24fd | 8086:0110 | Intel      | Wireless 8265 / 8275         | 288   | iwlwifi    | 31B241368B |
| 168c:0032 | 11ad:6617 | Qualcom... | AR9485 Wireless Network A... | 278   | ath9k      | 5EBEDD4A1C |
| 168c:003e | 1028:0310 | Qualcom... | QCA6174 802.11ac Wireless... | 278   | ath10k_pci | DA5E2F59CC |
| 8086:0082 | 8086:1301 | Intel      | Centrino Advanced-N 6205 ... | 278   | iwlwifi    | 4639F065C8 |
| 8086:4229 | 8086:1101 | Intel      | PRO/Wireless 4965 AG or A... | 274   | iwl4965    | 3332A4C510 |
| 10ec:c821 | 1a3b:3040 | Realtek... | RTL8821CE 802.11ac PCIe W... | 273   | rtl8821ce  | 67F0B45A7A |
| 168c:0036 | 17aa:4026 | Qualcom... | QCA9565 / AR9565 Wireless... | 269   | ath9k      | 07D05077AF |
| 8086:24f3 | 8086:0010 | Intel      | Wireless 8260                | 268   | iwlwifi    | 436E9BF227 |
| 10ec:b822 | 103c:831b | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 267   | rtwpci     | 339E6CEB69 |
| 8086:095b | 8086:5210 | Intel      | Wireless 7265                | 261   | iwlwifi    | EB89BBEBFE |
| 14e4:43a0 | 106b:0117 | Broadco... | BCM4360 802.11ac Wireless... | 248   | wl         | 5BE083EDAB |
| 8086:24f3 | 8086:0050 | Intel      | Wireless 8260                | 248   | iwlwifi    | E7A049A026 |
| 10ec:b723 | 11ad:1723 | Realtek... | RTL8723BE PCIe Wireless N... | 247   | rtl8723be  | 4C2453C6A2 |
| 8086:0896 | 8086:5005 | Intel      | Centrino Wireless-N 130      | 247   | iwlwifi    | A83E302ABA |
| 8086:0084 | 8086:1315 | Intel      | Centrino Wireless-N 1000 ... | 242   | iwlwifi    | 570863FD8C |
| 8086:095a | 8086:5410 | Intel      | Wireless 7265                | 241   | iwlwifi    | 9834990221 |
| 8086:08b1 | 8086:4070 | Intel      | Wireless 7260                | 234   | iwlwifi    | 6FE3800DD3 |
| 168c:0032 | 1a3b:1186 | Qualcom... | AR9485 Wireless Network A... | 230   | ath9k      | 2E47DD4121 |
| 14e4:4727 | 103c:145c | Broadcom   | BCM4313 802.11bgn Wireles... | 226   | wl         | 7312570938 |
| 168c:002b | 105b:e035 | Qualcom... | AR9285 Wireless Network A... | 223   | ath9k      | 55BA94A26E |
| 8086:24f3 | 8086:0130 | Intel      | Wireless 8260                | 220   | iwlwifi    | F45B082C14 |
| 14e4:4727 | 1028:0010 | Broadcom   | BCM4313 802.11bgn Wireles... | 219   | wl         | 4AD73429AF |
| 168c:0032 | 103c:1838 | Qualcom... | AR9485 Wireless Network A... | 215   | ath9k      | AB5E53C9ED |
| 10ec:c822 | 1058:1e25 | Realtek... | RTL8822CE 802.11ac PCIe W... | 212   | rtw88_8... | C0B80E3276 |
| 8086:08b4 | 8086:8270 | Intel      | Wireless 3160                | 211   | iwlwifi    | 2ECC44141A |
| 168c:001c | 1a3b:1026 | Qualcom... | AR242x / AR542x Wireless ... | 209   | ath5k      | 7A2E7C66E9 |
| 168c:002b | 103c:3040 | Qualcom... | AR9285 Wireless Network A... | 209   | ath9k      | E84CD86EB0 |
| 8086:2723 | 1a56:1654 | Intel      | Wi-Fi 6 AX200                | 208   | iwlwifi    | 58E43F0514 |
| 10ec:c822 | 103c:85f7 | Realtek... | RTL8822CE 802.11ac PCIe W... | 206   | rtw88_8... | 2BA5AE42BB |
| 168c:0032 | 11ad:6627 | Qualcom... | AR9485 Wireless Network A... | 206   | ath9k      | 50B1B1A6C5 |
| 8086:08b3 | 8086:8470 | Intel      | Wireless 3160                | 205   | iwlwifi    | D876CAAE1E |
| 8086:24f3 | 8086:1010 | Intel      | Wireless 8260                | 205   | iwlwifi    | 767EB7C6D3 |
| 10ec:8821 | 17aa:a814 | Realtek... | RTL8821AE 802.11ac PCIe W... | 204   | rtl8821ae  | 2BF6813AD9 |
| 14e4:4365 | 103c:804a | Broadcom   | BCM43142 802.11b/g/n         | 200   | wl         | 65C122FE69 |
| 10ec:8179 | 103c:197d | Realtek... | RTL8188EE Wireless Networ... | 199   | rtl8188ee  | 22807CB857 |
| 10ec:b822 | 17aa:b023 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 199   | rtwpci     | 8272A05168 |
| 168c:0042 | 1a3b:2b31 | Qualcom... | QCA9377 802.11ac Wireless... | 196   | ath10k_pci | 363C1A3642 |
| 8086:08b3 | 8086:0070 | Intel      | Wireless 3160                | 196   | iwlwifi    | 36ACEDB60B |
| 8086:34f0 | 8086:0074 | Intel      | Ice Lake-LP PCH CNVi WiFi    | 194   | iwlwifi    | 7125C6F5DD |
| 10ec:b723 | 103c:2231 | Realtek... | RTL8723BE PCIe Wireless N... | 193   | rtl8723be  | 8D5A256374 |
| 10ec:b723 | 103c:81c1 | Realtek... | RTL8723BE PCIe Wireless N... | 192   | rtl8723be  | B9D36307A5 |
| 168c:003e | 1a56:143a | Qualcom... | QCA6174 802.11ac Wireless... | 190   | ath10k_pci | 5A56854746 |
| 8086:4222 | 103c:135c | Intel      | PRO/Wireless 3945ABG [Gol... | 189   | iwl3945    | 3F34B3E11B |
| 168c:0032 | 103c:1785 | Qualcom... | AR9485 Wireless Network A... | 187   | ath9k      | 49CE392CD2 |
| 168c:002b | 105b:e017 | Qualcom... | AR9285 Wireless Network A... | 184   | ath9k      | A18FB33A6F |
| 168c:001c | 1468:0428 | Qualcom... | AR242x / AR542x Wireless ... | 183   | ath5k      | 01122F69F4 |
| 168c:002b | 105b:e025 | Qualcom... | AR9285 Wireless Network A... | 180   | ath9k      | CF2BC09886 |
| 168c:0032 | 1028:0209 | Qualcom... | AR9485 Wireless Network A... | 180   | ath9k      | D70E2B74D0 |
| 8086:08b1 | 8086:4060 | Intel      | Wireless 7260                | 179   | iwlwifi    | 83D642714B |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1502 | 17aa:21f3 | Intel      | 82579LM Gigabit Network C... | 570   | e1000e     | 69A252CCD6 |
| 8086:1502 | 17aa:21ce | Intel      | 82579LM Gigabit Network C... | 491   | e1000e     | 0A8E84DFAD |
| 8086:10ea | 17aa:2153 | Intel      | 82577LM Gigabit Network C... | 306   | e1000e     | 8B21B7CFFE |
| 8086:10f5 | 17aa:20ee | Intel      | 82567LM Gigabit Network C... | 224   | e1000e     | 9A7BE426F5 |
| 8086:1502 | 1028:0493 | Intel      | 82579LM Gigabit Network C... | 158   | e1000e     | 4C3C43DAAA |
| 8086:10ea | 1028:040a | Intel      | 82577LM Gigabit Network C... | 146   | e1000e     | BA51FC9216 |
| 8086:1502 | 1028:0534 | Intel      | 82579LM Gigabit Network C... | 137   | e1000e     | FA4D12994D |
| 8086:10f5 | 1028:0233 | Intel      | 82567LM Gigabit Network C... | 123   | e1000e     | 6B7EF9CAD5 |
| 8086:1502 | 103c:161c | Intel      | 82579LM Gigabit Network C... | 115   | e1000e     | B6AC4539D1 |
| 8086:1502 | 103c:179b | Intel      | 82579LM Gigabit Network C... | 109   | e1000e     | 1B2FBCDFA0 |
| 8086:1049 | 17aa:20b9 | Intel      | 82566MM Gigabit Network C... | 99    | e1000e     | 87E69E1105 |
| 8086:10ea | 103c:172a | Intel      | 82577LM Gigabit Network C... | 67    | e1000e     | F527983CC9 |
| 8086:1502 | 1028:0535 | Intel      | 82579LM Gigabit Network C... | 67    | e1000e     | FD1375D5F1 |
| 8086:1502 | 1028:0494 | Intel      | 82579LM Gigabit Network C... | 65    | e1000e     | B84EF4472B |
| 8086:1502 | 10cf:161b | Intel      | 82579LM Gigabit Network C... | 61    | e1000e     | 7FAB4F85E2 |
| 8086:10c4 | 103c:30d8 | Intel      | 82562GT 10/100 Network Co... | 58    | e1000e     | E880C038EB |
| 8086:10ea | 1028:040b | Intel      | 82577LM Gigabit Network C... | 55    | e1000e     | 2AB208B5CD |
| 14e4:170c | 1025:0090 | Broadcom   | BCM4401-B0 100Base-TX        | 52    | b44        | B09A0D7779 |
| 8086:10eb | 103c:1471 | Intel      | 82577LC Gigabit Network C... | 52    | e1000e     | 4DB59C8489 |
| 8086:10ea | 103c:7008 | Intel      | 82577LM Gigabit Network C... | 50    | e1000e     | F31AC36B11 |
| 8086:10f5 | 1028:024f | Intel      | 82567LM Gigabit Network C... | 49    | e1000e     | E475348B1E |
| 8086:1502 | 103c:162b | Intel      | 82579LM Gigabit Network C... | 49    | e1000e     | 28D13C49B3 |
| 8086:1502 | 10f7:8338 | Intel      | 82579LM Gigabit Network C... | 49    | e1000e     | 1AED5AEDC2 |
| 8086:1502 | 103c:18df | Intel      | 82579LM Gigabit Network C... | 47    | e1000e     | F66BA65DC8 |
| 8086:1502 | 103c:1618 | Intel      | 82579LM Gigabit Network C... | 44    | e1000e     | 48828AD0D3 |
| 8086:1503 | 10cf:161c | Intel      | 82579V Gigabit Network Co... | 44    | e1000e     | 4639F065C8 |
| 8086:10ea | 103c:1521 | Intel      | 82577LM Gigabit Network C... | 43    | e1000e     | 40F54639E6 |
| 8086:1502 | 1028:0492 | Intel      | 82579LM Gigabit Network C... | 43    | e1000e     | E8538CE77D |
| 14e4:170c | 1028:01f5 | Broadcom   | BCM4401-B0 100Base-TX        | 41    | b44        | 58A2EF72C9 |
| 10ec:8168 | 17aa:505b | Realtek... | RTL8111/8168/8411 PCI Exp... | 40    | r8169      | 4781A28617 |
| 14e4:170c | 1028:01af | Broadcom   | BCM4401-B0 100Base-TX        | 40    | b44        | FA750DAFE2 |
| 10ec:8136 | 103c:3567 | Realtek... | RTL810xE PCI Express Fast... | 38    | r8169      | 0585DD7016 |
| 14e4:170c | 103c:30a2 | Broadcom   | BCM4401-B0 100Base-TX        | 38    | b44        | 1E89CEC8EB |
| 8086:10ea | 10cf:1574 | Intel      | 82577LM Gigabit Network C... | 38    | e1000e     | 08576DED50 |
| 8086:1502 | 1028:04a3 | Intel      | 82579LM Gigabit Network C... | 38    | e1000e     | F442DF91A1 |
| 8086:1502 | 1028:0533 | Intel      | 82579LM Gigabit Network C... | 38    | e1000e     | 872CFFF7DA |
| 8086:1503 | 103c:17ab | Intel      | 82579V Gigabit Network Co... | 38    | e1000e     | 0BFBD31BA0 |
| 8086:10ea | 1028:0410 | Intel      | 82577LM Gigabit Network C... | 37    | e1000e     | 5E7233F129 |
| 8086:10f5 | 1028:024d | Intel      | 82567LM Gigabit Network C... | 37    | e1000e     | 127B65224F |
| 8086:1502 | 103c:17df | Intel      | 82579LM Gigabit Network C... | 37    | e1000e     | DFBC51210D |
| 8086:10f5 | 103c:30db | Intel      | 82567LM Gigabit Network C... | 36    | e1000e     | AF8E63842A |
| 8086:10bf | 17aa:20ee | Intel      | 82567LF Gigabit Network C... | 35    | e1000e     | 0E26427D3D |
| 8086:1502 | 1028:0532 | Intel      | 82579LM Gigabit Network C... | 35    | e1000e     | D040F874C9 |
| 8086:1502 | 103c:17a7 | Intel      | 82579LM Gigabit Network C... | 35    | e1000e     | 8D470E5C26 |
| 8086:1503 | 103c:1619 | Intel      | 82579V Gigabit Network Co... | 35    | e1000e     | DADA8DD37B |
| 8086:1049 | 17aa:20de | Intel      | 82566MM Gigabit Network C... | 33    | e1000e     | EE90608B54 |
| 8086:1092 | 1179:ff10 | Intel      | PRO/100 VE Network Connec... | 32    | e100       | EF126AD790 |
| 8086:1503 | 103c:161d | Intel      | 82579V Gigabit Network Co... | 32    | e1000e     | 317C62DF4B |
| 10ec:8168 | 17aa:3810 | Realtek... | RTL8111/8168/8411 PCI Exp... | 27    | r8169      | EF609865B5 |
| 8086:1049 | 103c:30c5 | Intel      | 82566MM Gigabit Network C... | 27    | e1000e     | CBF5040FF7 |
| 8086:1503 | 103c:179c | Intel      | 82579V Gigabit Network Co... | 27    | e1000e     | 7AA667BA1A |
| 8086:1502 | 103c:1631 | Intel      | 82579LM Gigabit Network C... | 25    | e1000e     | 98BD384A42 |
| 8086:1503 | 1179:0001 | Intel      | 82579V Gigabit Network Co... | 23    | e1000e     | FBE6B1147D |
| 10ec:8168 | 17aa:3819 | Realtek... | RTL8111/8168/8411 PCI Exp... | 22    | r8169      | 1DB80A4DB5 |
| 14e4:170c | 1028:022a | Broadco... | BCM4401-B0 100Base-TX        | 22    | b44        | AE3F94DFBF |
| 8086:10f5 | 103c:30e7 | Intel      | 82567LM Gigabit Network C... | 22    | e1000e     | 37A7444281 |
| 8086:10ea | 103c:7007 | Intel      | 82577LM Gigabit Network C... | 21    | e1000e     | E8D8BC3EB6 |
| 8086:10eb | 1179:0001 | Intel      | 82577LC Gigabit Network C... | 21    | e1000e     | 3062A1AC2F |
| 8086:1502 | 1028:04a9 | Intel      | 82579LM Gigabit Network C... | 21    | e1000e     | 08E1D2F464 |
| 8086:1502 | 103c:176b | Intel      | 82579LM Gigabit Network C... | 21    | e1000e     | 492907A363 |
| 8086:1049 | 103c:30be | Intel      | 82566MM Gigabit Network C... | 20    | e1000e     | 5910FA85E5 |
| 8086:1502 | 1028:053e | Intel      | 82579LM Gigabit Network C... | 20    | e1000e     | 8516551E92 |
| 10de:0269 | 103c:30b7 | Nvidia     | MCP51 Ethernet Controller    | 19    | forcedeth  | C28788427E |
| 14e4:170c | 1028:01f1 | Broadcom   | BCM4401-B0 100Base-TX        | 19    | b44        | 3DF4E95976 |
| 8086:1502 | 1028:04a4 | Intel      | 82579LM Gigabit Network C... | 19    | e1000e     | 3C06AD8F67 |
| 8086:1502 | 103c:162a | Intel      | 82579LM Gigabit Network C... | 19    | e1000e     | 0B1F6A34CE |
| 8086:1502 | 103c:176c | Intel      | 82579LM Gigabit Network C... | 19    | e1000e     | D23574ECF1 |
| 8086:1503 | 1179:0002 | Intel      | 82579V Gigabit Network Co... | 19    | e1000e     | 2768D5CCB6 |
| 14e4:170c | 1028:01c9 | Broadco... | BCM4401-B0 100Base-TX        | 17    | b44        | 5CA4E6101B |
| 14e4:170c | 1028:01f2 | Broadco... | BCM4401-B0 100Base-TX        | 17    | b44        | C74668293E |
| 8086:10ea | 1028:040c | Intel      | 82577LM Gigabit Network C... | 17    | e1000e     | 4BDDA5C7FB |
| 8086:1533 | 1ab6:0214 | Intel      | I210 Gigabit Network Conn... | 17    | igb        | 20EED1CD12 |
| 8086:1533 | ffff:0000 | Intel      | I210 Gigabit Network Conn... | 17    | igb        | CE3945EA8E |
| 14e4:170c | 1028:01cd | Broadco... | BCM4401-B0 100Base-TX        | 16    | b44        | 16B5EE2323 |
| 14e4:170c | 1028:01d4 | Broadcom   | BCM4401-B0 100Base-TX        | 16    | b44        | 8653D10B7A |
| 8086:1092 | 103c:30bb | Intel      | PRO/100 VE Network Connec... | 16    | e100       | 944D6AF89A |
| 14e4:170c | 1028:0228 | Broadco... | BCM4401-B0 100Base-TX        | 15    | b44        | F78B977663 |
| 8086:1092 | 104d:81ef | Intel      | PRO/100 VE Network Connec... | 15    | e100       | 7C1F897BC6 |
| 8086:10ea | 103c:172b | Intel      | 82577LM Gigabit Network C... | 15    | e1000e     | D79747DFAC |
| 8086:1502 | 1028:053f | Intel      | 82579LM Gigabit Network C... | 15    | e1000e     | 0D8CF3BF1C |
| 1106:3065 | 1509:1d41 | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 14    | via_rhine  | 85ABF16CA0 |
| 8086:10ea | 10f7:8338 | Intel      | 82577LM Gigabit Network C... | 14    | e1000e     | B11B688D14 |
| 8086:1539 | 8086:0000 | Intel      | I211 Gigabit Network Conn... | 14    | igb        | 7F5E602975 |
| 8086:1049 | 103c:30c3 | Intel      | 82566MM Gigabit Network C... | 13    | e1000e     | 8668ABCC62 |
| 8086:10f5 | 10f7:8338 | Intel      | 82567LM Gigabit Network C... | 13    | e1000e     | 29EEE33555 |
| 8086:1502 | 103c:1630 | Intel      | 82579LM Gigabit Network C... | 13    | e1000e     | 99FB47DC2B |
| 10ec:8168 | 103c:228d | Realtek... | RTL8111/8168/8411 PCI Exp... | 12    | r8169      | 286D5773A8 |
| 8086:10ea | 1179:0001 | Intel      | 82577LM Gigabit Network C... | 12    | e1000e     | B7B8ADEDEE |
| 8086:10f5 | 103c:30e1 | Intel      | 82567LM Gigabit Network C... | 12    | e1000e     | 7A20AA2C3B |
| 8086:1502 | 1179:0002 | Intel      | 82579LM Gigabit Network C... | 12    | e1000e     | A7D6145C50 |
| 8086:1049 | 103c:30c9 | Intel      | 82566MM Gigabit Network C... | 11    | e1000e     | 1F3C069A21 |
| 8086:10c4 | 103c:30d7 | Intel      | 82562GT 10/100 Network Co... | 11    | e1000e     | D2E067FD63 |
| 8086:10ea | 103c:1520 | Intel      | 82577LM Gigabit Network C... | 11    | e1000e     | 13796B8E87 |
| 8086:10f5 | 103c:30dc | Intel      | 82567LM Gigabit Network C... | 11    | e1000e     | 92E5B634E3 |
| 8086:10f5 | 104d:9025 | Intel      | 82567LM Gigabit Network C... | 11    | e1000e     | 87BD2C1CBF |
| 8086:1502 | 1028:04b4 | Intel      | 82579LM Gigabit Network C... | 11    | e1000e     | E139A9A623 |
| 8086:1502 | 103c:1815 | Intel      | 82579LM Gigabit Network C... | 11    | e1000e     | B5E3AAFF19 |
| 10de:0269 | 1025:0112 | Nvidia     | MCP51 Ethernet Controller    | 10    | forcedeth  | 56639ACA29 |
| 8086:10eb | 104d:905a | Intel      | 82577LC Gigabit Network C... | 10    | e1000e     | 2D1739DC58 |
| 8086:10f5 | 1028:0277 | Intel      | 82567LM Gigabit Network C... | 10    | e1000e     | DB5BAD5ADE |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:145a | 1022:145a | AMD        | Zeppelin/Raven/Raven2 PCI... | 48    |            | 214D892F21 |
| 1022:1485 | 1558:50f0 | AMD        | Starship/Matisse Reserved... | 17    |            | D63FD746BE |
| 1022:148a | 1558:50f0 | AMD        | Starship/Matisse PCIe Dum... | 17    |            | D63FD746BE |
| 8086:5a8e | 8086:7270 | Intel      | Non-Essential Instrumenta... | 14    | intel_t... | BE49BB64E0 |
| 1022:1455 | 1022:1455 | AMD        | Zeppelin/Renoir PCIe Dumm... | 13    |            | 7CB34B0A2E |
| 1022:145a | 17aa:3803 | AMD        | Zeppelin/Raven/Raven2 PCI... | 13    |            | C7A45F22C5 |
| 8086:9d26 |           | Intel      | Skylake-U/Y Northpeak        | 8     | intel_t... | 874D25FF57 |
| 1022:1455 | 1025:1246 | AMD        | Zeppelin/Renoir PCIe Dumm... | 5     |            | 03FACC3040 |
| 1022:145a | 1025:1246 | AMD        | Zeppelin/Raven/Raven2 PCI... | 5     |            | 03FACC3040 |
| 1022:145a | 103c:879c | AMD        | Zeppelin/Raven/Raven2 PCI... | 4     |            | 0071FAABAC |
| 1022:145a | 1d05:1111 | AMD        | Zeppelin/Raven/Raven2 PCI... | 4     |            | 985D394A66 |
| 1022:1455 | 1043:8747 | AMD        | Zeppelin/Renoir PCIe Dumm... | 2     |            | 62042D8665 |
| 1022:145a | 1043:8747 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 62042D8665 |
| 8086:318e |           | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_t... | D08EFA2EF3 |
| 8086:a126 |           | Intel      | 100 Series/C230 Series Ch... | 2     | intel_t... | E5B46A78DE |
| 1022:145a | 1022:7901 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 0FA72B5193 |
| 1022:145a | 152d:1315 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 6DB19936AC |
| 1022:145a | 1d05:1100 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 97AEC9C50F |
| 1022:1485 | 1022:1485 | AMD        | Starship/Matisse Reserved... | 1     |            | B9C02872AA |
| 1022:1485 | 1043:8808 | AMD        | Starship/Matisse Reserved... | 1     |            | E02455114E |
| 1022:1485 | 1462:7c02 | AMD        | Starship/Matisse Reserved... | 1     |            | 9BCD3D5479 |
| 1022:148a | 1022:148a | AMD        | Starship/Matisse PCIe Dum... | 1     |            | B9C02872AA |
| 1022:148a | 1043:8808 | AMD        | Starship/Matisse PCIe Dum... | 1     |            | E02455114E |
| 1022:148a | 1462:7c02 | AMD        | Starship/Matisse PCIe Dum... | 1     |            | 9BCD3D5479 |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15e6 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Non-S... | 206   | i2c_amd... | C4FFE3D08B |
| 106b:1801 | 106b:1801 | Apple      | T2 Bridge Controller         | 53    | apple_bce  | 7B3CDDA6E2 |
| 106b:1802 | 106b:1802 | Apple      | T2 Secure Enclave Processor  | 53    |            | 7B3CDDA6E2 |
| 8086:9d24 |           | Intel      | Skylake-U/Y SPI Controller   | 51    |            | F3E5EBA0C2 |
| 1022:15e6 | 103c:85ea | AMD        | Raven/Raven2/Renoir Non-S... | 38    | i2c_amd... | E8781DB5AB |
| 8086:9d35 | 17aa:2238 | Intel      | Sunrise Point-LP Integrat... | 34    | intel_i... | 623506F87F |
| 8086:22d8 | 103c:813e | Intel      | Integrated Sensor Solution   | 33    | intel_i... | 0A44B96544 |
| 8086:9d35 | 1028:0740 | Intel      | Sunrise Point-LP Integrat... | 27    | intel_i... | 5246EABC5F |
| 1022:15e6 | 1025:1456 | AMD        | Raven/Raven2/Renoir Non-S... | 26    | i2c_amd... | 09F6196E70 |
| 8086:22d8 | 1043:1bdd | Intel      | Integrated Sensor Solution   | 14    | intel_i... | C518746ECE |
| 8086:9d35 | 8086:9d35 | Intel      | Sunrise Point-LP Integrat... | 14    | intel_i... | 33D61B2077 |
| 8086:9d35 | 103c:80fc | Intel      | Sunrise Point-LP Integrat... | 12    | intel_i... | 89E5AB8846 |
| 8086:9d35 | 103c:83b2 | Intel      | Sunrise Point-LP Integrat... | 12    | intel_i... | 1EEA89F8BB |
| 8086:9d35 | 1028:0804 | Intel      | Sunrise Point-LP Integrat... | 11    | intel_i... | 0E30997FF6 |
| 8086:9d35 | 1028:073b | Intel      | Sunrise Point-LP Integrat... | 8     | intel_i... | E14ACDFFAD |
| 8086:9d35 | 1028:0742 | Intel      | Sunrise Point-LP Integrat... | 8     | intel_i... | 1169A22F51 |
| 8086:22d8 | 1043:1400 | Intel      | Integrated Sensor Solution   | 6     | intel_i... | 0A301456DC |
| 8086:9d35 | 1028:0741 | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | 43F15F79DF |
| 8086:9d35 | 1028:0808 | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | 3C56EDEFE6 |
| 8086:9d35 | 17aa:3812 | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | 090E25B77C |
| 8086:22d8 | 103c:8042 | Intel      | Integrated Sensor Solution   | 5     | intel_i... | 0E503AAA16 |
| 8086:9d35 | 1028:0743 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 11E496D162 |
| 8086:9d35 | 1028:0809 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 2713F21DD7 |
| 8086:22d8 | 8086:7270 | Intel      | Integrated Sensor Solution   | 4     | intel_i... | D045383640 |
| 8086:9d35 | 1028:07a4 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 0FAD55C520 |
| 8086:9d35 | 1028:0823 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | D1705E50A2 |
| 8086:9d35 | 103c:8470 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 6C42757430 |
| 8086:9d35 | 1179:0001 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | ED1722174A |
| 8086:a135 | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 4     | intel_i... | 41FC496B9F |
| 1022:15e4 | 1028:090c | AMD        | Raven/Raven2/Renoir Senso... | 3     |            | CDA45B1F3C |
| 1022:15e6 | 103c:87ce | AMD        | Raven/Raven2/Renoir Non-S... | 3     | i2c_amd... | 28930B356E |
| 1022:15e6 | 103c:87d2 | AMD        | Raven/Raven2/Renoir Non-S... | 3     | i2c_amd... | A671B3AAE7 |
| 8086:22d8 | 1043:13a0 | Intel      | Integrated Sensor Solution   | 3     | intel_i... | 036F4F2304 |
| 8086:9d35 | 1028:0744 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 2CF1F86B67 |
| 8086:9d35 | 1028:07ba | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 271C309BFA |
| 8086:9d35 | 1028:081d | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 293B45EDED |
| 8086:9d35 | 103c:8146 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | D20C059F3D |
| 8086:9d35 | 1043:1160 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 52039745C7 |
| 1022:15e6 | 1025:1458 | AMD        | Raven/Raven2/Renoir Non-S... | 2     | i2c_amd... | 195778FCC3 |
| 1022:15e6 | 103c:87d3 | AMD        | Raven/Raven2/Renoir Non-S... | 2     | i2c_amd... | 756904BEC1 |
| 8086:22d8 | 1028:06ea | Intel      | Integrated Sensor Solution   | 2     | intel_i... | 57FDB94877 |
| 8086:22d8 | 103c:8173 | Intel      | Integrated Sensor Solution   | 2     | intel_i... | CCF01919AB |
| 8086:9d35 | 1028:06d6 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | BF9CC483F0 |
| 8086:9d35 | 1028:073e | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 6CCC3403F8 |
| 8086:9d35 | 103c:83b3 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 5570800F48 |
| 8086:9d35 | 10cf:18d0 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 50C2127F6C |
| 8086:9d35 | 17aa:2237 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 19E1E784FC |
| 8086:9d35 | 17aa:506c | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | A68BF7CFC5 |
| 1022:15e6 | 1025:1552 | AMD        | Raven/Raven2/Renoir Non-S... | 1     | i2c_amd... | AD8F403C6D |
| 1022:15e6 | 103c:85ec | AMD        | Raven/Raven2/Renoir Non-S... | 1     | i2c_amd... | 214A977789 |
| 1022:15e6 | 103c:87d1 | AMD        | Raven/Raven2/Renoir Non-S... | 1     | i2c_amd... | FD8AFA6F02 |
| 10ec:0119 | 1025:009f | Realtek... |                              | 1     |            | 1312407631 |
| 1180:8476 |           | Ricoh      |                              | 1     |            | C215EA9980 |
| 14e4:8100 | 0000:8100 | Broadcom   |                              | 1     |            | 784397ABB8 |
| 1524:1412 |           | ENE Tec... | CB-712/4 Cardbus Controller  | 1     |            | 1312407631 |
| 1cbc:0100 | 1cbc:0000 |            |                              | 1     |            | 3CFCCD6F1C |
| 8086:22d8 | 1071:a126 | Intel      | Integrated Sensor Solution   | 1     | intel_i... | F2981C1775 |
| 8086:22d8 | 10cf:191b | Intel      | Integrated Sensor Solution   | 1     | intel_i... | 6D19311F7E |
| 8086:22d8 | 1179:f860 | Intel      | Integrated Sensor Solution   | 1     | intel_i... | 1148737572 |
| 8086:9d35 | 1028:073d | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 81B3E142A3 |
| 8086:9d35 | 1028:073f | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | F0F4829A9A |
| 8086:9d35 | 1028:074f | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 4F8F1DD9C8 |
| 8086:9d35 | 1028:07a5 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 67C03244DC |
| 8086:9d35 | 1028:07aa | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 1DC7215E55 |
| 8086:9d35 | 1028:07ec | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | BF57A8FDAE |
| 8086:9d35 | 103c:8181 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 49A6D8DEC1 |
| 8086:9d35 | 103c:8197 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 910D564E8E |
| 8086:9d35 | 103c:8198 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 236EFC033E |
| 8086:9d35 | 1071:a133 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | F35B5EC303 |
| 8086:9d35 | 10f7:8338 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 6F921AA428 |
| 8086:9d35 | 17aa:2241 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 726380658A |
| 8086:9d35 | 17aa:2259 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 7550150FB5 |
| 8086:9d35 | 17aa:3804 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 2B89909A49 |
| 8086:9d35 | 17aa:504c | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 240BAB94C7 |
| 8086:a124 |           | Intel      | 100 Series/C230 Series Ch... | 1     |            | BF6B408B8A |
| 8086:a135 | 8086:a135 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_i... | CCDADF3870 |

### Performance counters (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27a3 |           | Intel      | 945GM/GU Chipset Hardware... | 47    |            | 0346BC764A |
| 8086:1907 | 8086:2015 | Intel      | Performance counters         | 2     |            | 4D3FFA307C |
| 8086:0107 |           | Intel      | Performance counters         | 1     |            | 8A4C419DA7 |
| 8086:0e30 | 1558:0270 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 1694F6A1B4 |
| 8086:0e30 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | F0368052CB |
| 8086:0e34 | 1558:0270 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 1694F6A1B4 |
| 8086:0e34 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | F0368052CB |
| 8086:0e36 | 1558:0270 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 1694F6A1B4 |
| 8086:0e36 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | F0368052CB |
| 8086:3c43 | 1558:0270 | Intel      | Xeon E5/Core i7 Ring to P... | 1     | snbep_u... | DE166D9BF2 |
| 8086:3c44 | 1558:0270 | Intel      | Xeon E5/Core i7 Ring to Q... | 1     | snbep_u... | DE166D9BF2 |
| 8086:3c46 | 1558:0270 | Intel      | Xeon E5/Core i7 Processor... | 1     | snbep_u... | DE166D9BF2 |
| 8086:3ce6 | 1558:0270 | Intel      | Xeon E5/Core i7 QuickPath... | 1     |            | DE166D9BF2 |

### Pic (8259) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3422 | 0058:0003 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | 7F55996B62 |
| 8086:3423 | 0058:0003 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | 7F55996B62 |
| 8086:342e | 0058:0003 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     | i7core_... | 7F55996B62 |

### Pic (io(x)-apic) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1106:5364 |           | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 45    |            | F770A4F41F |
| 1106:5364 | 103c:3030 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 9     |            | E81CAC058D |
| 1106:5364 | 1734:10f7 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 8     |            | A61C777014 |
| 1106:5336 |           | VIA Tec... | K8M890CE I/O APIC Interru... | 7     |            | 20512BBBE4 |
| 1106:5353 | 17aa:388a | VIA Tec... | VX800/VX820 APIC and Cent... | 3     |            | 4762847735 |
| 1106:5353 | 144d:c04e | VIA Tec... | VX800/VX820 APIC and Cent... | 2     |            | 085B83A79C |
| 1106:5238 | 1734:1093 | VIA Tec... | K8T890 I/O APIC Interrupt... | 1     |            | E9825FB39A |
| 1106:5327 |           | VIA Tec... | P4M890 I/O APIC Interrupt... | 1     |            | 7464ED3C9D |
| 1106:5353 |           | VIA Tec... | VX800/VX820 APIC and Cent... | 1     |            | 77A2A10D46 |
| 1106:5364 | 1509:5364 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 1     |            | D514055CD5 |
| 8086:0e2c | 1558:0270 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1694F6A1B4 |
| 8086:0e2c | 8086:0e2c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | F0368052CB |
| 8086:342d | 0058:0003 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | 7F55996B62 |
| 8086:3c2c | 1558:0270 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | DE166D9BF2 |

### Rf controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:7305 | 10ec:7305 | Realtek... | UWB Radio                    | 1     | whci, w... | 6F4E5774F9 |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:16bc | 1025:0647 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 410   | sdhci_pci  | 82E60126C9 |
| 14e4:16bc | 14e4:0000 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 285   | sdhci_pci  | 6E17FB6EA4 |
| 197b:2381 | 1043:1a07 | JMicron... | Standard SD Host Controller  | 235   | sdhci_pci  | D5A8ADB8C9 |
| 1180:0822 | 17aa:20c8 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 224   | sdhci_pci  | 9A7BE426F5 |
| 8086:9d2d | 8086:9d2d | Intel      | Sunrise Point-LP Secure D... | 216   | sdhci_pci  | F3511CB0AA |
| 14e4:16bc | 1025:0504 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 213   | sdhci_pci  | F86CA58100 |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 204   | sdhci_pci  | 63FACC4838 |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 163   | sdhci_pci  | 63FACC4838 |
| 1217:8221 | 1028:0493 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 154   | sdhci_pci  | 4C3C43DAAA |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 149   | sdhci_pci  | 63FACC4838 |
| 1180:e822 | 1028:040a | Ricoh      | MMC/SD Host Controller       | 145   | sdhci_pci  | BA51FC9216 |
| 14e4:16bc | 1025:0775 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 145   | sdhci_pci  | 921FC6B490 |
| 1022:7813 | 17aa:3801 | AMD        | FCH SD Flash Controller      | 143   | sdhci_pci  | 0CDC6E9D84 |
| 1217:8221 | 1028:0534 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 141   | sdhci_pci  | FA4D12994D |
| 8086:31d0 | 8086:7270 | Intel      | SD Host Controller           | 140   | sdhci_pci  | F40D5FD5A7 |
| 1180:e822 | 104d:9071 | Ricoh      | MMC/SD Host Controller       | 138   | sdhci_pci  | A18FB33A6F |
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 137   | sdhci_pci  | F40D5FD5A7 |
| 104c:803c | 1025:011f | Texas I... | PCIxx12 SDA Standard Comp... | 135   | sdhci_pci  | 8592F1650F |
| 1180:0822 | 1028:0233 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 124   | sdhci_pci  | 6B7EF9CAD5 |
| 197b:2391 | 103c:161c | JMicron... | Standard SD Host Controller  | 116   | sdhci_pci  | B6AC4539D1 |
| 197b:2391 | 103c:179b | JMicron... | Standard SD Host Controller  | 106   | sdhci_pci  | 1B2FBCDFA0 |
| 197b:2391 | 103c:17f6 | JMicron... | Standard SD Host Controller  | 97    | sdhci_pci  | E12D7E47E6 |
| 1217:8621 | 17aa:5068 | O2 Micro   | SD/MMC Card Reader Contro... | 86    | sdhci_pci  | 2A70ED5588 |
| 1180:0822 | 1028:022f | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 83    | sdhci_pci  | ED2467DC52 |
| 1217:8520 | 1028:05cb | O2 Micro   | SD/MMC Card Reader Contro... | 81    | sdhci_pci  | 98C988645F |
| 1022:7806 | 1022:7806 | AMD        | FCH SD Flash Controller      | 75    | sdhci_pci  | 3378B3C989 |
| 10ec:5209 | 10ec:5209 | Realtek... | RTS5209 PCI Express Card ... | 75    | rtsx_pci   | 045B2CD511 |
| 1217:8520 | 1028:062e | O2 Micro   | SD/MMC Card Reader Contro... | 75    | sdhci_pci  | 91837758AC |
| 197b:2391 | 103c:167c | JMicron... | Standard SD Host Controller  | 75    | sdhci_pci  | 4808FF3A68 |
| 1180:0822 | 103c:30cc | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 73    | sdhci_pci  | DD3C7EF3E7 |
| 1217:8520 | 1028:05bd | O2 Micro   | SD/MMC Card Reader Contro... | 69    | sdhci_pci  | 00E8B6E3FD |
| 1217:8520 | 1028:05be | O2 Micro   | SD/MMC Card Reader Contro... | 68    | sdhci_pci  | 298AB39418 |
| 1217:8621 | 1217:0002 | O2 Micro   | SD/MMC Card Reader Contro... | 68    | sdhci_pci  | FD3AEFD54A |
| 1180:0822 | 103c:172a | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 66    | sdhci_pci  | F527983CC9 |
| 1217:8221 | 1028:0535 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 66    | sdhci_pci  | FD1375D5F1 |
| 1217:8321 | 1028:0494 | O2 Micro   | OZ600RJ0/OZ900RJ0/OZ600RJ... | 66    | sdhci_pci  | B84EF4472B |
| 1180:0843 | 1028:0233 | Ricoh      | R5C843 MMC Host Controller   | 64    | sdhci_pci  | 843B7BD830 |
| 8086:9df5 | 8086:7270 | Intel      | BayHubTech Integrated SD ... | 63    | sdhci_pci  | 0E29003348 |
| 17a0:9750 | 17aa:2279 | Genesys... | GL9750 SD Host Controller    | 61    | sdhci_pci  | A01E524A66 |
| 1217:7120 | 1179:ff50 | O2 Micro   | Integrated MMC/SD Controller | 60    | sdhci_pci  | ABCF2EEE75 |
| 1217:8520 | 1028:05ca | O2 Micro   | SD/MMC Card Reader Contro... | 57    | sdhci_pci  | DBF0FD04C3 |
| 1524:0550 | 1025:0090 | ENE Tec... | ENE PCI Secure Digital Ca... | 57    | sdhci_pci  | B09A0D7779 |
| 1217:8621 | 17aa:381f | O2 Micro   | SD/MMC Card Reader Contro... | 56    | sdhci_pci  | A7045DEFDF |
| 1180:e822 | 1028:040b | Ricoh      | MMC/SD Host Controller       | 55    | sdhci_pci  | 2AB208B5CD |
| 1217:8520 | 17aa:2211 | O2 Micro   | SD/MMC Card Reader Contro... | 55    | sdhci_pci  | 8DD2C7497E |
| 1022:7813 | 1025:104b | AMD        | FCH SD Flash Controller      | 54    | sdhci_pci  | C6582BBA7D |
| 104c:803c | 1179:ff00 | Texas I... | PCIxx12 SDA Standard Comp... | 54    | sdhci_pci  | 1BF61C0698 |
| 10ec:5209 | 103c:3388 | Realtek... | RTS5209 PCI Express Card ... | 51    | rtsx_pci   | 0392F507D0 |
| 197b:2391 | 103c:162b | JMicron... | Standard SD Host Controller  | 50    | sdhci_pci  | 28D13C49B3 |
| 1180:0822 | 103c:7008 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 49    | sdhci_pci  | F31AC36B11 |
| 1217:8621 | 17aa:3824 | O2 Micro   | SD/MMC Card Reader Contro... | 49    | sdhci_pci  | 3F7C00C1EF |
| 197b:2381 | 103c:3628 | JMicron... | Standard SD Host Controller  | 49    | sdhci_pci  | 2992DD1DF0 |
| 1180:0822 | 1028:024f | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 48    | sdhci_pci  | E475348B1E |
| 1969:3010 | 1025:076b | Qualcom... | Secure Digital Card Reader   | 48    | sdhci_pci  | DC7A02C862 |
| 197b:2381 | 1297:2027 | JMicron... | Standard SD Host Controller  | 48    | sdhci_pci  | 9F3A43BC94 |
| 197b:2391 | 103c:18df | JMicron... | Standard SD Host Controller  | 48    | sdhci_pci  | F66BA65DC8 |
| 1022:7906 | 1043:1291 | AMD        | FCH SD Flash Controller      | 47    | sdhci_pci  | 34F2870A95 |
| 1180:0822 | 1025:011e | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 47    | sdhci_pci  | 6472272BF7 |
| 197b:2381 | 17aa:212d | JMicron... | Standard SD Host Controller  | 47    | sdhci_pci  | 0BC832BD49 |
| 8086:9d2b | 8086:7270 | Intel      | Skylake-U/Y SCC: eMMC        | 47    | sdhci_pci  | DD20DE340C |
| 1217:8621 | 17aa:5072 | O2 Micro   | SD/MMC Card Reader Contro... | 46    | sdhci_pci  | 3678E02E46 |
| 1180:0822 | 10f7:8338 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 45    | sdhci_pci  | 3678F83BBA |
| 1217:8221 | 1028:0492 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 45    | sdhci_pci  | E8538CE77D |
| 197b:2391 | 103c:1618 | JMicron... | Standard SD Host Controller  | 45    | sdhci_pci  | 48828AD0D3 |
| 8086:2294 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 45    | sdhci_pci  | E9536CCBFB |
| 8086:31cc | 1025:1360 | Intel      | Celeron/Pentium Silver Pr... | 45    | sdhci_pci  | F901B7640E |
| 1180:0822 | 103c:30cf | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 44    | sdhci_pci  | 8774B51F01 |
| 1180:e822 | 103c:146d | Ricoh      | MMC/SD Host Controller       | 44    | sdhci_pci  | 4DB59C8489 |
| 1217:7120 | 10cf:143d | O2 Micro   | Integrated MMC/SD Controller | 44    | sdhci_pci  | 5F0BCD4C39 |
| 1217:8221 | 1028:053c | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 44    | sdhci_pci  | E6D67EBC2E |
| 1217:8321 | 1028:049a | O2 Micro   | OZ600RJ0/OZ900RJ0/OZ600RJ... | 44    | sdhci_pci  | 3405536413 |
| 1180:0822 | 103c:1521 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 43    | sdhci_pci  | 40F54639E6 |
| 1217:8520 | 17aa:3800 | O2 Micro   | SD/MMC Card Reader Contro... | 43    | sdhci_pci  | 2FCA11CF26 |
| 1524:0550 | 1025:009f | ENE Tec... | ENE PCI Secure Digital Ca... | 43    | sdhci_pci  | 86DFC89E4A |
| 197b:2381 | 1558:0801 | JMicron... | Standard SD Host Controller  | 43    | sdhci_pci  | 6F701D72FD |
| 1022:7813 | 103c:21f7 | AMD        | FCH SD Flash Controller      | 42    | sdhci_pci  | AB5E53C9ED |
| 14e4:16bc | 1025:0500 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 42    | sdhci_pci  | 8A74691BA9 |
| 8086:02f5 | 103c:86a0 | Intel      | Comet Lake PCH-LP SCS3       | 42    | sdhci_pci  | C86D75DBBB |
| 104c:803c | 1179:ff02 | Texas I... | PCIxx12 SDA Standard Comp... | 41    | sdhci_pci  | 371CF70DA6 |
| 1180:0822 | 1025:0121 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 41    | sdhci_pci  | D7C90EB05B |
| 1180:0822 | 104d:9035 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 41    | sdhci_pci  | DBFD29F616 |
| 1217:8221 | 1028:0533 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 40    | sdhci_pci  | 872CFFF7DA |
| 8086:9d2b | 8086:9d2b | Intel      | Skylake-U/Y SCC: eMMC        | 40    | sdhci_pci  | 72DED95FAB |
| 1180:0822 | 1028:01f5 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 39    | sdhci_pci  | 58A2EF72C9 |
| 1217:8320 | 1028:04a3 | O2 Micro   | OZ600RJ1/OZ900RJ1 SD/MMC ... | 39    | sdhci_pci  | F442DF91A1 |
| 14e4:16bc | 1025:0742 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 39    | sdhci_pci  | 8068BE142E |
| 104c:803c | 1179:ff10 | Texas I... | PCIxx12 SDA Standard Comp... | 38    | sdhci_pci  | 68AC15EEDA |
| 1180:e822 | 1028:0410 | Ricoh      | MMC/SD Host Controller       | 38    | sdhci_pci  | 5E7233F129 |
| 1217:8321 | 1028:049b | O2 Micro   | OZ600RJ0/OZ900RJ0/OZ600RJ... | 38    | sdhci_pci  | A1027F938F |
| 1217:8520 | 1028:05cc | O2 Micro   | SD/MMC Card Reader Contro... | 38    | sdhci_pci  | 87034ED159 |
| 197b:2391 | 103c:17ab | JMicron... | Standard SD Host Controller  | 38    | sdhci_pci  | 0BFBD31BA0 |
| 197b:2391 | 17aa:3976 | JMicron... | Standard SD Host Controller  | 38    | sdhci_pci  | 409FB80AE5 |
| 8086:9df5 | 103c:8538 | Intel      | BayHubTech Integrated SD ... | 38    | sdhci_pci  | E03D6BA4C2 |
| 1022:7813 | 103c:8137 | AMD        | FCH SD Flash Controller      | 37    | sdhci_pci  | FA33BFD7BC |
| 1180:0822 | 1028:01bd | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 37    | sdhci_pci  | FA750DAFE2 |
| 1180:0822 | 1028:024d | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 37    | sdhci_pci  | 127B65224F |
| 1217:8520 | 1028:05de | O2 Micro   | SD/MMC Card Reader Contro... | 37    | sdhci_pci  | 30A45FE2EE |
| 1217:8520 | 1028:062d | O2 Micro   | SD/MMC Card Reader Contro... | 37    | sdhci_pci  | 9834990221 |
| 14e4:16bc | 1025:0605 | Broadco... | BCM57765/57785 SDXC/MMC C... | 37    | sdhci_pci  | 39FD26F895 |
| 14e4:16bc | 14e4:96bc | Broadco... | BCM57765/57785 SDXC/MMC C... | 37    | sdhci_pci  | 25C8A26C00 |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9da4 | 8086:7270 | Intel      | Cannon Point-LP SPI Contr... | 282   |            | 67F0B45A7A |
| 8086:9ce6 | 8086:9ce6 | Intel      | Wildcat Point-LP Serial I... | 265   | spi_pxa... | 5BE083EDAB |
| 8086:a324 | 8086:7270 | Intel      | Cannon Lake PCH SPI Contr... | 160   | intel_s... | 3C7C0BFB25 |
| 8086:a324 | 1025:1331 | Intel      | Cannon Lake PCH SPI Contr... | 157   | intel_s... | BC9DC107D1 |
| 8086:a368 | 1025:1331 | Intel      | Cannon Lake PCH Serial IO... | 157   | intel_lpss | BC9DC107D1 |
| 8086:a369 | 1025:1331 | Intel      | Cannon Lake PCH Serial IO... | 157   | intel_lpss | BC9DC107D1 |
| 8086:a324 | 1028:0905 | Intel      | Cannon Lake PCH SPI Contr... | 142   | intel_s... | 58E43F0514 |
| 8086:a368 | 1028:0905 | Intel      | Cannon Lake PCH Serial IO... | 142   | intel_l... | 58E43F0514 |
| 8086:a369 | 1028:0905 | Intel      | Cannon Lake PCH Serial IO... | 142   | intel_l... | 58E43F0514 |
| 8086:02a4 | 17aa:5079 | Intel      | Comet Lake SPI (flash) Co... | 138   | intel_s... | A35AAAEB6D |
| 8086:9da4 | 17aa:2279 | Intel      | Cannon Point-LP SPI Contr... | 127   |            | A01E524A66 |
| 8086:9de8 | 17aa:2279 | Intel      | Cannon Point-LP Serial IO... | 126   | intel_l... | A01E524A66 |
| 8086:a324 | 1028:087c | Intel      | Cannon Lake PCH SPI Contr... | 114   | intel_spi  | 0FA8C3ED0C |
| 8086:a368 | 1028:087c | Intel      | Cannon Lake PCH Serial IO... | 114   | intel_l... | 0FA8C3ED0C |
| 8086:a369 | 1028:087c | Intel      | Cannon Lake PCH Serial IO... | 114   | intel_l... | 0FA8C3ED0C |
| 8086:9da4 | 103c:8549 | Intel      | Cannon Point-LP SPI Contr... | 111   |            | A814284F0B |
| 8086:9de8 | 103c:8549 | Intel      | Cannon Point-LP Serial IO... | 111   | intel_l... | A814284F0B |
| 8086:9de9 | 103c:8549 | Intel      | Cannon Point-LP Serial IO... | 111   | intel_l... | A814284F0B |
| 8086:02a4 | 8086:7270 | Intel      | Comet Lake SPI (flash) Co... | 94    | intel_s... | BD39D63927 |
| 10de:1adb | 10de:0000 | Nvidia     | TU106 USB Type-C UCSI Con... | 92    | i2c_nvi... | 2054D0DEE6 |
| 8086:9da4 | 1028:08af | Intel      | Cannon Point-LP SPI Contr... | 92    |            | 52DEA66C52 |
| 8086:9de8 | 1028:08af | Intel      | Cannon Point-LP Serial IO... | 92    | intel_l... | 52DEA66C52 |
| 8086:9de9 | 1028:08af | Intel      | Cannon Point-LP Serial IO... | 92    | intel_l... | 52DEA66C52 |
| 8086:02a4 | 1028:0962 | Intel      | Comet Lake SPI (flash) Co... | 91    | intel_spi  | 8956FEE2F3 |
| 8086:02e8 | 1028:0962 | Intel      | Serial IO I2C Host Contro... | 91    | intel_l... | 8956FEE2F3 |
| 8086:02e9 | 1028:0962 | Intel      | Comet Lake Serial IO I2C ... | 91    | intel_l... | 8956FEE2F3 |
| 8086:9da4 | 17aa:5072 | Intel      | Cannon Point-LP SPI Contr... | 89    |            | 3678E02E46 |
| 8086:9da4 | 17aa:2292 | Intel      | Cannon Point-LP SPI Contr... | 86    |            | 26C62915E0 |
| 8086:9de8 | 17aa:2292 | Intel      | Cannon Point-LP Serial IO... | 86    | intel_l... | 26C62915E0 |
| 8086:a324 | 1025:1264 | Intel      | Cannon Lake PCH SPI Contr... | 86    | intel_s... | 7F70DE1771 |
| 8086:a368 | 1025:1264 | Intel      | Cannon Lake PCH Serial IO... | 86    | intel_lpss | 7F70DE1771 |
| 8086:a369 | 1025:1264 | Intel      | Cannon Lake PCH Serial IO... | 86    | intel_lpss | 7F70DE1771 |
| 8086:9de9 | 17aa:2292 | Intel      | Cannon Point-LP Serial IO... | 85    | intel_l... | 26C62915E0 |
| 8086:06a4 | 1028:097d | Intel      | Comet Lake PCH SPI Contro... | 84    | intel_s... | 994B96D25D |
| 8086:06e8 | 1028:097d | Intel      | Comet Lake PCH Serial IO ... | 84    | intel_l... | 994B96D25D |
| 8086:06e9 | 1028:097d | Intel      | Comet Lake PCH Serial IO ... | 84    | intel_l... | 994B96D25D |
| 8086:9da4 | 17aa:380c | Intel      | Cannon Point-LP SPI Contr... | 76    |            | 2DB4EBB6EF |
| 8086:9de8 | 17aa:3813 | Intel      | Cannon Point-LP Serial IO... | 76    | intel_l... | 2DB4EBB6EF |
| 8086:a324 | 17aa:3803 | Intel      | Cannon Lake PCH SPI Contr... | 73    | intel_s... | EAF7694813 |
| 8086:a368 | 17aa:3805 | Intel      | Cannon Lake PCH Serial IO... | 73    | intel_l... | EAF7694813 |
| 8086:a369 | 17aa:380b | Intel      | Cannon Lake PCH Serial IO... | 73    | intel_l... | EAF7694813 |
| 8086:a324 | 1028:0949 | Intel      | Cannon Lake PCH SPI Contr... | 65    | intel_s... | 3165D77A8E |
| 8086:a368 | 1028:0949 | Intel      | Cannon Lake PCH Serial IO... | 65    | intel_l... | 3165D77A8E |
| 8086:a369 | 1028:0949 | Intel      | Cannon Lake PCH Serial IO... | 65    | intel_l... | 3165D77A8E |
| 8086:a324 | 17aa:3827 | Intel      | Cannon Lake PCH SPI Contr... | 63    | intel_s... | 75C71D1F1E |
| 8086:a368 | 17aa:3803 | Intel      | Cannon Lake PCH Serial IO... | 63    | intel_l... | 75C71D1F1E |
| 8086:a369 | 17aa:3804 | Intel      | Cannon Lake PCH Serial IO... | 63    | intel_l... | 75C71D1F1E |
| 8086:a0a4 | 1028:0991 | Intel      | Tiger Lake-LP SPI Controller | 62    | intel_s... | 22BC284F45 |
| 8086:a0c5 | 1028:0991 | Intel      | Tiger Lake-LP Serial IO I... | 62    | intel_l... | 22BC284F45 |
| 8086:a0c6 | 1028:0991 | Intel      | Tiger Lake-LP Serial IO I... | 62    | intel_l... | 22BC284F45 |
| 8086:a0e8 | 1028:0991 | Intel      | Tiger Lake-LP Serial IO I... | 62    | intel_l... | 22BC284F45 |
| 8086:a0e9 | 1028:0991 | Intel      | Tiger Lake-LP Serial IO I... | 62    | intel_l... | 22BC284F45 |
| 8086:a324 | 17aa:3801 | Intel      | Cannon Lake PCH SPI Contr... | 60    | intel_s... | 2AD271E81F |
| 8086:a368 | 17aa:3806 | Intel      | Cannon Lake PCH Serial IO... | 60    | intel_l... | 2AD271E81F |
| 8086:a369 | 17aa:3809 | Intel      | Cannon Lake PCH Serial IO... | 60    | intel_l... | 2AD271E81F |
| 8086:9da4 | 1028:08ca | Intel      | Cannon Point-LP SPI Contr... | 59    |            | 8F25043C64 |
| 8086:9dc5 | 1028:08ca | Intel      | Cannon Point-LP Serial IO... | 59    | intel_l... | 8F25043C64 |
| 8086:9de8 | 1028:08ca | Intel      | Cannon Point-LP Serial IO... | 59    | intel_l... | 8F25043C64 |
| 8086:9de9 | 1028:08ca | Intel      | Cannon Point-LP Serial IO... | 59    | intel_l... | 8F25043C64 |
| 8086:a324 | 1028:086f | Intel      | Cannon Lake PCH SPI Contr... | 59    | intel_s... | 28D725057F |
| 8086:a368 | 1028:086f | Intel      | Cannon Lake PCH Serial IO... | 59    | intel_l... | 28D725057F |
| 8086:a369 | 1028:086f | Intel      | Cannon Lake PCH Serial IO... | 59    | intel_l... | 28D725057F |
| 8086:a324 | 103c:8478 | Intel      | Cannon Lake PCH SPI Contr... | 56    | intel_s... | 362E1D3B99 |
| 8086:a324 | 1025:1333 | Intel      | Cannon Lake PCH SPI Contr... | 53    |            | 271C2188CB |
| 8086:a368 | 1025:1333 | Intel      | Cannon Lake PCH Serial IO... | 53    | intel_lpss | 271C2188CB |
| 8086:a369 | 1025:1333 | Intel      | Cannon Lake PCH Serial IO... | 53    | intel_lpss | 271C2188CB |
| 8086:a0a4 | 17aa:5087 | Intel      | Tiger Lake-LP SPI Controller | 50    | intel_s... | BE67E01A7D |
| 8086:a0e8 | 17aa:5087 | Intel      | Tiger Lake-LP Serial IO I... | 50    | intel_l... | BE67E01A7D |
| 8086:a0ea | 17aa:5087 | Intel      | Tiger Lake-LP Serial IO I... | 50    | intel_l... | BE67E01A7D |
| 8086:a324 | 1028:0906 | Intel      | Cannon Lake PCH SPI Contr... | 50    | intel_s... | E549029931 |
| 8086:a324 | 17aa:2267 | Intel      | Cannon Lake PCH SPI Contr... | 50    | intel_s... | 3A76CBDC51 |
| 8086:a368 | 1028:0906 | Intel      | Cannon Lake PCH Serial IO... | 50    | intel_l... | E549029931 |
| 8086:a368 | 17aa:2267 | Intel      | Cannon Lake PCH Serial IO... | 50    | intel_l... | 3A76CBDC51 |
| 8086:a369 | 1028:0906 | Intel      | Cannon Lake PCH Serial IO... | 50    | intel_l... | E549029931 |
| 8086:34a4 | 17aa:3842 | Intel      | Ice Lake-LP SPI Controller   | 49    | intel_s... | 5369A455A4 |
| 8086:34e8 | 17aa:3816 | Intel      | Ice Lake-LP Serial IO I2C... | 49    | intel_l... | 5369A455A4 |
| 8086:34e9 | 17aa:3817 | Intel      | Ice Lake-LP Serial IO I2C... | 49    | intel_l... | 5369A455A4 |
| 8086:9da4 | 17aa:2286 | Intel      | Cannon Point-LP SPI Contr... | 49    |            | D3700D8667 |
| 8086:34a4 | 1028:096d | Intel      | Ice Lake-LP SPI Controller   | 48    | intel_spi  | B0CD53DB27 |
| 8086:34e8 | 1028:096d | Intel      | Ice Lake-LP Serial IO I2C... | 48    | intel_l... | B0CD53DB27 |
| 8086:34e9 | 1028:096d | Intel      | Ice Lake-LP Serial IO I2C... | 48    | intel_l... | B0CD53DB27 |
| 8086:a324 | 1028:087d | Intel      | Cannon Lake PCH SPI Contr... | 48    | intel_spi  | 7F78C88EA8 |
| 8086:a368 | 1028:087d | Intel      | Cannon Lake PCH Serial IO... | 48    | intel_l... | 7F78C88EA8 |
| 8086:a369 | 1028:087d | Intel      | Cannon Lake PCH Serial IO... | 48    | intel_l... | 7F78C88EA8 |
| 8086:9daa | 1043:1961 | Intel      | Cannon Point-LP Serial IO... | 47    | intel_lpss | 67F0B45A7A |
| 8086:9dc5 | 1043:1961 | Intel      | Cannon Point-LP Serial IO... | 47    | intel_lpss | 67F0B45A7A |
| 8086:9de8 | 1043:1961 | Intel      | Cannon Point-LP Serial IO... | 47    | intel_lpss | 67F0B45A7A |
| 8086:9de9 | 1043:1961 | Intel      | Cannon Point-LP Serial IO... | 47    | intel_lpss | 67F0B45A7A |
| 8086:a324 | 17aa:229f | Intel      | Cannon Lake PCH SPI Contr... | 45    | intel_s... | 3517455DF5 |
| 8086:a368 | 17aa:229f | Intel      | Cannon Lake PCH Serial IO... | 45    | intel_lpss | 3517455DF5 |
| 8086:06a4 | 8086:7270 | Intel      | Comet Lake PCH SPI Contro... | 44    | intel_spi  | 32F01CCAAB |
| 8086:34a4 | 17aa:3841 | Intel      | Ice Lake-LP SPI Controller   | 44    | intel_s... | 7125C6F5DD |
| 8086:34e8 | 17aa:3815 | Intel      | Ice Lake-LP Serial IO I2C... | 44    | intel_l... | 7125C6F5DD |
| 8086:34e9 | 17aa:3818 | Intel      | Ice Lake-LP Serial IO I2C... | 44    | intel_l... | 7125C6F5DD |
| 8086:a324 | 1028:0825 | Intel      | Cannon Lake PCH SPI Contr... | 43    | intel_s... | AB839FD11F |
| 8086:a368 | 1028:0825 | Intel      | Cannon Lake PCH Serial IO... | 43    | intel_l... | AB839FD11F |
| 8086:a369 | 1028:0825 | Intel      | Cannon Lake PCH Serial IO... | 43    | intel_l... | AB839FD11F |
| 8086:02a4 | 103c:86a0 | Intel      | Comet Lake SPI (flash) Co... | 42    | intel_s... | C86D75DBBB |
| 8086:02e8 | 103c:86a0 | Intel      | Serial IO I2C Host Contro... | 42    | intel_l... | C86D75DBBB |
| 8086:02a4 | 1025:1345 | Intel      | Comet Lake SPI (flash) Co... | 41    | intel_s... | 7463FACB20 |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3b67 | 17aa:2162 | Intel      | 5 Series/3400 Series Chip... | 146   | serial     | 8B21B7CFFE |
| 8086:2a47 | 17aa:20ec | Intel      | Mobile 4 Series Chipset A... | 142   | serial     | 56E7FA3C9B |
| 8086:1c3d | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 125   | serial     | A75FFD5203 |
| 8086:1e3d | 17aa:21f3 | Intel      | 7 Series/C210 Series Chip... | 123   | serial     | B868085BFC |
| 8086:1e3d | 17aa:21fa | Intel      | 7 Series/C210 Series Chip... | 94    | serial     | A120083D3C |
| 10ec:816a | 17aa:5081 | Realtek... | RTL8111xP UART #1            | 88    | serial     | 273A5FF27D |
| 10ec:816b | 17aa:5081 | Realtek... | RTL8111xP UART #2            | 88    | serial     | 273A5FF27D |
| 8086:9c3d | 103c:198f | Intel      | 8 Series HECI KT             | 87    | serial     | CECD552E89 |
| 8086:06fc | 1028:097d | Intel      | 400 Series Chipset Family... | 84    | intel_i... | 994B96D25D |
| 8086:1c3d | 103c:161c | Intel      | 6 Series/C200 Series Chip... | 80    | serial     | B6AC4539D1 |
| 8086:1c3d | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 80    | serial     | 471414140C |
| 8086:9d3d | 103c:8079 | Intel      | Sunrise Point-LP Active M... | 77    | serial     | 436E9BF227 |
| 8086:9c3d | 17aa:220c | Intel      | 8 Series HECI KT             | 72    | serial     | FC5E995432 |
| 8086:1e3d | 103c:179b | Intel      | 7 Series/C210 Series Chip... | 67    | serial     | 1B2FBCDFA0 |
| 8086:1e3d | 17aa:21f6 | Intel      | 7 Series/C210 Series Chip... | 65    | serial     | E80BBD929F |
| 8086:a0fc | 1028:0991 | Intel      | Tiger Lake-LP Integrated ... | 62    | intel_i... | 22BC284F45 |
| 8086:1c3d | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 60    | serial     | 4104E265EA |
| 8086:3b67 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 60    | serial     | DDD6E2A190 |
| 8086:8c3d | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 57    | serial     | 6E8CA97F4B |
| 8086:1e3d | 1028:0534 | Intel      | 7 Series/C210 Series Chip... | 49    | serial     | FA4D12994D |
| 8086:34fc | 1028:096d | Intel      | Ice Lake-LP Integrated Se... | 48    | intel_i... | B0CD53DB27 |
| 10ec:816a | 17aa:5082 | Realtek... | RTL8111xP UART #1            | 47    | serial     | 037A558C7D |
| 10ec:816b | 17aa:5082 | Realtek... | RTL8111xP UART #2            | 47    | serial     | 037A558C7D |
| 8086:1c3d | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 47    | serial     | 027441E6D4 |
| 8086:3b67 | 103c:172a | Intel      | 5 Series/3400 Series Chip... | 46    | serial     | F527983CC9 |
| 8086:9c3d | 1028:05cb | Intel      | 8 Series HECI KT             | 43    | serial     | 98C988645F |
| 8086:9c3d | 17aa:2214 | Intel      | 8 Series HECI KT             | 43    | serial     | A7FA6A8110 |
| 8086:9dfc | 103c:8549 | Intel      | Cannon Point-LP Integrate... | 41    | intel_i... | BA581C25B0 |
| 8086:9d3d | 1028:06dc | Intel      | Sunrise Point-LP Active M... | 40    | serial     | 69A251CC1F |
| 8086:06fc | 1028:098f | Intel      | 400 Series Chipset Family... | 39    | intel_i... | 5E25D50915 |
| 8086:1c3d | 103c:162b | Intel      | 6 Series/C200 Series Chip... | 36    | serial     | D2BBA3F247 |
| 8086:1e3d | 17aa:21fb | Intel      | 7 Series/C210 Series Chip... | 36    | serial     | 319D0DD2FF |
| 8086:1e3d | 10cf:16ed | Intel      | 7 Series/C210 Series Chip... | 35    | serial     | 7FAB4F85E2 |
| 8086:9d3d | 17aa:2245 | Intel      | Sunrise Point-LP Active M... | 35    | serial     | 80FB4514C5 |
| 8086:9de3 | 103c:8549 | Intel      | Cannon Point-LP Keyboard ... | 34    | serial     | CD2412D37E |
| 8086:1c3d | 17aa:21d2 | Intel      | 6 Series/C200 Series Chip... | 33    | serial     | 4F47DC5C55 |
| 8086:3b67 | 103c:1521 | Intel      | 5 Series/3400 Series Chip... | 33    | serial     | A68000E142 |
| 8086:8c3d | 1028:05bd | Intel      | 8 Series/C220 Series Chip... | 33    | serial     | 00E8B6E3FD |
| 8086:9d3d | 17aa:2233 | Intel      | Sunrise Point-LP Active M... | 33    | serial     | 9EF824D802 |
| 8086:a13d | 17aa:222e | Intel      | 100 Series/C230 Series Ch... | 33    | serial     | BE24112A95 |
| 8086:1e3d | 103c:18df | Intel      | 7 Series/C210 Series Chip... | 32    | serial     | F66BA65DC8 |
| 8086:3b67 | 103c:7008 | Intel      | 5 Series/3400 Series Chip... | 32    | serial     | EB060CD2C4 |
| 8086:9c3d | 1028:05ca | Intel      | 8 Series HECI KT             | 32    | serial     | 7048AA6E8B |
| 10ec:816a | 17aa:507e | Realtek... | RTL8111xP UART #1            | 31    | serial     | AC5C6A0DD6 |
| 10ec:816b | 17aa:507e | Realtek... | RTL8111xP UART #2            | 31    | serial     | AC5C6A0DD6 |
| 8086:9d3d | 1028:081c | Intel      | Sunrise Point-LP Active M... | 31    | serial     | F78358FED7 |
| 8086:3b67 | 10cf:152f | Intel      | 5 Series/3400 Series Chip... | 30    | serial     | 08576DED50 |
| 8086:a37c | 1028:0949 | Intel      | VROC Virtual Controller      | 30    | intel_i... | CAAAB11F09 |
| 8086:9d3d | 17aa:5053 | Intel      | Sunrise Point-LP Active M... | 29    | serial     | 4DBC231901 |
| 8086:9de3 | 1028:08e1 | Intel      | Cannon Point-LP Keyboard ... | 29    | serial     | 2932112DCA |
| 8086:9de3 | 17aa:2279 | Intel      | Cannon Point-LP Keyboard ... | 29    | serial     | F8024B89D4 |
| 8086:02fc | 1028:0959 | Intel      | Comet Lake Integrated Sen... | 28    | intel_i... | 0A8AA1439F |
| 8086:8c3d | 1028:05be | Intel      | 8 Series/C220 Series Chip... | 28    | serial     | 298AB39418 |
| 8086:9c3d | 103c:1991 | Intel      | 8 Series HECI KT             | 28    | serial     | 278EC34902 |
| 8086:9d3d | 17aa:225c | Intel      | Sunrise Point-LP Active M... | 28    | serial     | 2B4A1A20D9 |
| 10ec:816a | 17aa:5125 | Realtek... | RTL8111xP UART #1            | 27    | serial     | 8E00E1F239 |
| 10ec:816a | 17aa:5126 | Realtek... | RTL8111xP UART #1            | 27    | serial     | 6B6B00F95C |
| 10ec:816b | 17aa:5125 | Realtek... | RTL8111xP UART #2            | 27    | serial     | 8E00E1F239 |
| 10ec:816b | 17aa:5126 | Realtek... | RTL8111xP UART #2            | 27    | serial     | 6B6B00F95C |
| 8086:1c3d | 103c:1618 | Intel      | 6 Series/C200 Series Chip... | 27    | serial     | 48828AD0D3 |
| 8086:2a47 | 1028:0233 | Intel      | Mobile 4 Series Chipset A... | 27    | serial     | EB47D36417 |
| 8086:9d3d | 17aa:225d | Intel      | Sunrise Point-LP Active M... | 25    | serial     | FC6636E0B5 |
| 8086:02fc | 1028:0957 | Intel      | Comet Lake Integrated Sen... | 23    | intel_i... | 9661AABAFC |
| 8086:1e3d | 1028:0535 | Intel      | 7 Series/C210 Series Chip... | 23    | serial     | 5996ACF813 |
| 8086:1e3d | 103c:17a7 | Intel      | 7 Series/C210 Series Chip... | 23    | serial     | FCC24E96E1 |
| 8086:1c3d | 1028:04a3 | Intel      | 6 Series/C200 Series Chip... | 22    | serial     | F442DF91A1 |
| 8086:8c3d | 17aa:2211 | Intel      | 8 Series/C220 Series Chip... | 22    | serial     | 8DD2C7497E |
| 8086:a363 | 17aa:2267 | Intel      | Cannon Lake PCH Active Ma... | 22    | serial     | 3A76CBDC51 |
| 8086:1c3d | 1028:0492 | Intel      | 6 Series/C200 Series Chip... | 21    | serial     | E8538CE77D |
| 8086:1c3d | 10cf:1614 | Intel      | 6 Series/C200 Series Chip... | 21    | serial     | A470EEAA37 |
| 8086:3b67 | 1028:040b | Intel      | 5 Series/3400 Series Chip... | 21    | serial     | B7071DDEA1 |
| 8086:8c3d | 103c:1909 | Intel      | 8 Series/C220 Series Chip... | 21    | serial     | 206882306C |
| 8086:9d3d | 17aa:224b | Intel      | Sunrise Point-LP Active M... | 21    | serial     | F82B6569D1 |
| 8086:9de3 | 17aa:2292 | Intel      | Cannon Point-LP Keyboard ... | 21    | serial     | ABEB038C57 |
| 8086:1c3d | 17aa:21db | Intel      | 6 Series/C200 Series Chip... | 20    | serial     | 33137C7C23 |
| 8086:2a07 | 103c:30c5 | Intel      | Mobile PM965/GM965 KT Con... | 20    | serial     | 940CCEBF1E |
| 8086:2a47 | 103c:30db | Intel      | Mobile 4 Series Chipset A... | 20    | serial     | AF8E63842A |
| 8086:9d3d | 17aa:504a | Intel      | Sunrise Point-LP Active M... | 20    | serial     | C8E9D8E7A9 |
| 8086:1c3d | 1028:0494 | Intel      | 6 Series/C200 Series Chip... | 19    | serial     | 981A3487DA |
| 8086:3b67 | 1028:0410 | Intel      | 5 Series/3400 Series Chip... | 19    | serial     | 75A9AA20F2 |
| 8086:9d3d | 1028:06de | Intel      | Sunrise Point-LP Active M... | 19    | serial     | 9A036A26A4 |
| 8086:9d3d | 17aa:2258 | Intel      | Sunrise Point-LP Active M... | 19    | serial     | 85A242883C |
| 8086:3b67 | 103c:7007 | Intel      | 5 Series/3400 Series Chip... | 18    | serial     | E8D8BC3EB6 |
| 8086:9d3d | 1028:07a0 | Intel      | Sunrise Point-LP Active M... | 18    | serial     | E4D0ECB120 |
| 8086:9d3d | 17aa:225a | Intel      | Sunrise Point-LP Active M... | 18    | serial     | 65E201224C |
| 8086:9dfc | 1028:08a7 | Intel      | Cannon Point-LP Integrate... | 18    | intel_i... | 4B9F94E0D0 |
| 8086:a13d | 1028:06de | Intel      | 100 Series/C230 Series Ch... | 18    | serial     | 08D4C126FA |
| 8086:1c3d | 10f7:8338 | Intel      | 6 Series/C200 Series Chip... | 17    | serial     | A90D037DCF |
| 8086:2a07 | 17aa:20d4 | Intel      | Mobile PM965/GM965 KT Con... | 17    | serial     | 9D3DAAB4B3 |
| 8086:8c3d | 103c:2101 | Intel      | 8 Series/C220 Series Chip... | 17    | serial     | 15E5C85B3B |
| 8086:9d3d | 103c:83b2 | Intel      | Sunrise Point-LP Active M... | 17    | serial     | A5331A4D5E |
| 8086:a363 | 1028:0918 | Intel      | Cannon Lake PCH Active Ma... | 17    | serial     | 334511B0C1 |
| 8086:06fc | 1028:097e | Intel      | 400 Series Chipset Family... | 16    | intel_i... | 174F79A38C |
| 8086:06fc | 1028:09c3 | Intel      | 400 Series Chipset Family... | 16    | intel_i... | 42890F7542 |
| 8086:9d3d | 1028:06db | Intel      | Sunrise Point-LP Active M... | 16    | serial     | 94D1C284A1 |
| 8086:9d3d | 103c:80fa | Intel      | Sunrise Point-LP Active M... | 16    | serial     | 30974235EA |
| 8086:a363 | 17aa:229f | Intel      | Cannon Lake PCH Active Ma... | 16    | serial     | 3517455DF5 |
| 8086:02fc | 1028:0955 | Intel      | Comet Lake Integrated Sen... | 15    | intel_i... | 0899AC7F63 |
| 8086:02fc | 1028:09be | Intel      | Comet Lake Integrated Sen... | 15    | intel_i... | 8F1A1A4798 |
| 8086:1e3d | 17aa:2203 | Intel      | 7 Series/C210 Series Chip... | 15    | serial     | 93090177CD |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3b32 | 17aa:2190 | Intel      | 5 Series/3400 Series Chip... | 306   | intel_ips  | 570863FD8C |
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 298   | process... | 2FBF6F153B |
| 8086:9d27 | 1043:1d2d | Intel      | Sunrise Point-LP Serial I... | 272   | intel_lpss | F3511CB0AA |
| 8086:9ca4 | 8086:7270 | Intel      | Wildcat Point-LP Thermal ... | 268   | intel_p... | 5BE083EDAB |
| 8086:9d29 | 1043:1d2d | Intel      | Sunrise Point-LP Serial I... | 257   | intel_lpss | F3511CB0AA |
| 8086:22dc | 7270:8086 | Intel      | Atom/Celeron/Pentium Proc... | 243   | process... | FF46DC73D4 |
| 8086:5a8c |           | Intel      | Atom/Celeron/Pentium Dyna... | 227   | process... | 63FACC4838 |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 208   | intel_l... | 403E735C43 |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 206   | intel_l... | 403E735C43 |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 204   | intel_l... | 63FACC4838 |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 203   | intel_l... | 403E735C43 |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 203   | intel_l... | 403E735C43 |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 202   | intel_l... | 63FACC4838 |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 202   | intel_l... | 63FACC4838 |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 202   | intel_l... | 63FACC4838 |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 202   | intel_l... | 63FACC4838 |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 201   | intel_l... | 403E735C43 |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 189   | intel_l... | 403E735C43 |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 189   | intel_l... | 403E735C43 |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 189   | intel_l... | 403E735C43 |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 188   | intel_l... | 63FACC4838 |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 188   | intel_l... | 63FACC4838 |
| 8086:31c6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 159   | intel_l... | F40D5FD5A7 |
| 8086:31be | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 158   | intel_l... | F40D5FD5A7 |
| 8086:31c4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 158   | intel_l... | F40D5FD5A7 |
| 8086:31ee | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 158   | intel_l... | F40D5FD5A7 |
| 8086:a379 | 1025:1331 | Intel      | Cannon Lake PCH Thermal C... | 157   | intel_p... | BC9DC107D1 |
| 8086:31b4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 152   | intel_l... | F40D5FD5A7 |
| 8086:0a03 | 8086:2010 | Intel      | Haswell-ULT Thermal Subsy... | 151   | process... | B2CDA34B7E |
| 8086:318c | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 151   | process... | F40D5FD5A7 |
| 8086:31ba | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 151   | intel_l... | F40D5FD5A7 |
| 8086:31bc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 151   | intel_l... | F40D5FD5A7 |
| 8086:31c2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 151   | intel_l... | F40D5FD5A7 |
| 8086:31c0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 149   | intel_l... | F40D5FD5A7 |
| 8086:31ac | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 147   | intel_l... | F40D5FD5A7 |
| 8086:9d31 | 17aa:3861 | Intel      | Sunrise Point-LP Thermal ... | 147   | intel_p... | F86520F5A7 |
| 8086:9d60 | 17aa:3865 | Intel      | Sunrise Point-LP Serial I... | 147   | intel_l... | F86520F5A7 |
| 8086:31b6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 146   | intel_l... | F40D5FD5A7 |
| 8086:31b8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 146   | intel_l... | F40D5FD5A7 |
| 8086:31ae | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 145   | intel_l... | F40D5FD5A7 |
| 8086:31b0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 145   | intel_l... | F40D5FD5A7 |
| 8086:31b2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 145   | intel_l... | F40D5FD5A7 |
| 8086:3b32 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 145   | intel_ips  | BA51FC9216 |
| 8086:318c | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 143   | proc_th... | 5C95C74B6C |
| 8086:31b4 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 143   | intel_lpss | 5C95C74B6C |
| 8086:31b6 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 143   | intel_lpss | 5C95C74B6C |
| 8086:31bc | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 143   | intel_lpss | 5C95C74B6C |
| 8086:31be | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 143   | intel_lpss | 5C95C74B6C |
| 8086:31c0 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 143   | intel_lpss | 5C95C74B6C |
| 8086:31ee | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 143   | intel_lpss | 5C95C74B6C |
| 8086:1903 | 1028:0905 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 142   | process... | 58E43F0514 |
| 8086:a379 | 1028:0905 | Intel      | Cannon Lake PCH Thermal C... | 142   | intel_p... | 58E43F0514 |
| 8086:02f9 | 17aa:5079 | Intel      | Comet Lake Thermal Subsytem  | 138   | intel_p... | A35AAAEB6D |
| 8086:1903 | 17aa:5079 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 138   | process... | A35AAAEB6D |
| 8086:1903 | 8086:1903 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 129   | process... | 20123F6B2F |
| 8086:1903 | 17aa:2279 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 127   | process... | A01E524A66 |
| 8086:9df9 | 17aa:2279 | Intel      | Cannon Point-LP Thermal C... | 127   | intel_p... | A01E524A66 |
| 8086:9a0d |           | Intel      | Tigerlake Telemetry Aggre... | 126   | intel_pmt  | 8CDB34DBC8 |
| 8086:9d31 | 103c:8079 | Intel      | Sunrise Point-LP Thermal ... | 123   | intel_p... | 436E9BF227 |
| 8086:9d60 | 103c:8079 | Intel      | Sunrise Point-LP Serial I... | 123   | intel_l... | 436E9BF227 |
| 8086:3b32 | 17aa:38c0 | Intel      | 5 Series/3400 Series Chip... | 120   | intel_ips  | 80B7F3E584 |
| 8086:9d60 | 1025:1193 | Intel      | Sunrise Point-LP Serial I... | 119   | intel_lpss | 43BFEF3BCD |
| 8086:9d61 | 1025:1193 | Intel      | Sunrise Point-LP Serial I... | 119   | intel_lpss | 43BFEF3BCD |
| 8086:1903 | 1028:087c | Intel      | Xeon E3-1200 v5/E3-1500 v... | 114   | process... | 0FA8C3ED0C |
| 8086:a379 | 1028:087c | Intel      | Cannon Lake PCH Thermal C... | 114   | intel_p... | 0FA8C3ED0C |
| 8086:9ca4 | 17aa:5034 | Intel      | Wildcat Point-LP Thermal ... | 111   | intel_p... | CEA37DD548 |
| 8086:9df9 | 103c:8549 | Intel      | Cannon Point-LP Thermal C... | 111   | intel_p... | A814284F0B |
| 8086:1903 | 1028:0810 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 110   | process... | C01FA4B013 |
| 8086:9d31 | 1028:0810 | Intel      | Sunrise Point-LP Thermal ... | 110   | intel_p... | C01FA4B013 |
| 8086:9d60 | 1028:0810 | Intel      | Sunrise Point-LP Serial I... | 110   | intel_l... | C01FA4B013 |
| 8086:1903 | 17aa:225d | Intel      | Xeon E3-1200 v5/E3-1500 v... | 109   | process... | FEB7F2A285 |
| 8086:3b32 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 109   | intel_ips  | 77E0B6A916 |
| 8086:9d31 | 17aa:225d | Intel      | Sunrise Point-LP Thermal ... | 109   | intel_p... | FEB7F2A285 |
| 8086:1903 | 103c:8549 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 108   | process... | A814284F0B |
| 8086:1903 | 17aa:2292 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 108   | process... | 080C5280D0 |
| 8086:2932 | 17aa:3a1f | Intel      | 82801I (ICH9 Family) Ther... | 102   |            | B9412E1AB2 |
| 8086:1903 | 1028:07be | Intel      | Xeon E3-1200 v5/E3-1500 v... | 99    | process... | 69938C221E |
| 8086:1903 | 1028:07e6 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 99    | process... | 5A56854746 |
| 8086:9d31 | 1028:07e6 | Intel      | Sunrise Point-LP Thermal ... | 99    | intel_p... | 5A56854746 |
| 8086:9d60 | 1028:07e6 | Intel      | Sunrise Point-LP Serial I... | 99    | intel_l... | 5A56854746 |
| 8086:9d61 | 1028:07e6 | Intel      | Sunrise Point-LP Serial I... | 99    | intel_l... | 5A56854746 |
| 8086:a131 | 1028:07be | Intel      | 100 Series/C230 Series Ch... | 99    | intel_p... | 69938C221E |
| 8086:a160 | 1028:07be | Intel      | 100 Series/C230 Series Ch... | 99    | intel_l... | 69938C221E |
| 8086:a161 | 1028:07be | Intel      | 100 Series/C230 Series Ch... | 99    | intel_l... | 69938C221E |
| 8086:9d27 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 96    | intel_l... | DD20DE340C |
| 8086:1903 | 1043:12d1 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 95    | proc_th... | 703D0F2090 |
| 8086:9d27 | 1043:12d1 | Intel      | Sunrise Point-LP Serial I... | 95    | intel_lpss | 703D0F2090 |
| 8086:9d31 | 1043:12d1 | Intel      | Sunrise Point-LP Thermal ... | 95    | intel_p... | 703D0F2090 |
| 8086:9d60 | 1043:12d1 | Intel      | Sunrise Point-LP Serial I... | 95    | intel_lpss | 703D0F2090 |
| 8086:9d61 | 1043:12d1 | Intel      | Sunrise Point-LP Serial I... | 95    | intel_lpss | 703D0F2090 |
| 8086:1903 | 1028:08af | Intel      | Xeon E3-1200 v5/E3-1500 v... | 92    | process... | 52DEA66C52 |
| 8086:9df9 | 1028:08af | Intel      | Cannon Point-LP Thermal C... | 92    | intel_p... | 52DEA66C52 |
| 8086:02f9 | 1028:0962 | Intel      | Comet Lake Thermal Subsytem  | 91    | intel_p... | 8956FEE2F3 |
| 8086:1903 | 1028:078b | Intel      | Xeon E3-1200 v5/E3-1500 v... | 91    | process... | 35BCBD121B |
| 8086:1903 | 1028:0962 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 91    | process... | 8956FEE2F3 |
| 8086:9d31 | 1028:078b | Intel      | Sunrise Point-LP Thermal ... | 91    | intel_p... | 35BCBD121B |
| 8086:9d60 | 1028:078b | Intel      | Sunrise Point-LP Serial I... | 91    | intel_l... | 35BCBD121B |
| 8086:9d61 | 1028:078b | Intel      | Sunrise Point-LP Serial I... | 91    | intel_l... | 35BCBD121B |
| 8086:9d31 | 8086:9d31 | Intel      | Sunrise Point-LP Thermal ... | 90    | intel_p... | F3E5EBA0C2 |
| 8086:1903 | 17aa:5072 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 89    | process... | 3678E02E46 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e22 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 574   | i2c_i801   | 16EBDC4388 |
| 8086:3b30 | 17aa:2167 | Intel      | 5 Series/3400 Series Chip... | 339   | i2c_i801   | 570863FD8C |
| 8086:1c22 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 320   | i2c_i801   | D1D57448C4 |
| 8086:2930 | 17aa:20f9 | Intel      | 82801I (ICH9 Family) SMBu... | 312   | i2c_i801   | 9A7BE426F5 |
| 8086:9c22 | 17aa:3978 | Intel      | 8 Series SMBus Controller    | 312   | i2c_i801   | 3CDDE1061C |
| 8086:9ca2 | 8086:7270 | Intel      | Wildcat Point-LP SMBus Co... | 296   | i2c_i801   | 5BE083EDAB |
| 1022:790b | 1022:790b | AMD        | FCH SMBus Controller         | 238   | i2c_piix4  | 2BA5AE42BB |
| 8086:8c22 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 227   | i2c_i801   | 60FA5FF04C |
| 8086:1c22 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 217   | i2c_i801   | ECC4515014 |
| 8086:1e22 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 206   | i2c_i801   | 783D081B5A |
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 197   | i2c_i801   | 403E735C43 |
| 1002:4385 |           | AMD        | SBx00 SMBus Controller       | 195   | i2c_pii... | 5A8280A663 |
| 8086:1e22 | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 194   | i2c_i801   | C9D8EFC9B9 |
| 8086:27da | 1043:83ad | Intel      | NM10/ICH7 Family SMBus Co... | 191   | i2c_i801   | E74DC83F0A |
| 10de:0aa2 | 10de:cb79 | Nvidia     | MCP79 SMBus                  | 173   | i2c_nfo... | 25B2F96576 |
| 8086:1c22 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 173   | i2c_i801   | A75FFD5203 |
| 8086:1e22 | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 167   | i2c_i801   | EC8AF5F350 |
| 8086:1c22 | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 165   | i2c_i801   | B96D5D5FDC |
| 8086:1e22 | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 165   | i2c_i801   | 82E60126C9 |
| 8086:1c22 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 160   | i2c_i801   | 4C3C43DAAA |
| 8086:1c22 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 158   | i2c_i801   | B66EB36016 |
| 8086:283e | 17aa:20a9 | Intel      | 82801H (ICH8 Family) SMBu... | 157   | i2c_i801   | 87E69E1105 |
| 8086:2930 | 17aa:3a1d | Intel      | 82801I (ICH9 Family) SMBu... | 157   | i2c_i801   | B9412E1AB2 |
| 8086:a323 | 1025:1331 | Intel      | Cannon Lake PCH SMBus Con... | 157   | i2c_i801   | BC9DC107D1 |
| 8086:31d4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 151   | i2c_i801   | F40D5FD5A7 |
| 8086:3b30 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 150   | i2c_i801   | BA51FC9216 |
| 8086:3b30 | 17aa:38bf | Intel      | 5 Series/3400 Series Chip... | 148   | i2c_i801   | 80B7F3E584 |
| 8086:9d23 | 17aa:386f | Intel      | Sunrise Point-LP SMBus       | 147   | i2c_i801   | F86520F5A7 |
| 1022:780b | 17aa:3801 | AMD        | FCH SMBus Controller         | 143   | i2c_piix4  | 0CDC6E9D84 |
| 8086:31d4 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 143   | i2c_i801   | 5C95C74B6C |
| 8086:1e22 | 1028:0534 | Intel      | 7 Series/C216 Chipset Fam... | 142   | i2c_i801   | FA4D12994D |
| 8086:a323 | 1028:0905 | Intel      | Cannon Lake PCH SMBus Con... | 142   | i2c_i801   | 58E43F0514 |
| 8086:1c22 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 141   | i2c_i801   | 0A8E84DFAD |
| 8086:02a3 | 17aa:5079 | Intel      | Comet Lake PCH-LP SMBus H... | 138   | i2c_i801   | A35AAAEB6D |
| 8086:1e22 | 1043:124d | Intel      | 7 Series/C216 Chipset Fam... | 138   | i2c_i801   | 3498166FA2 |
| 8086:3b30 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 138   | i2c_i801   | A18FB33A6F |
| 8086:3b30 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 136   | i2c_i801   | 77E0B6A916 |
| 8086:3b30 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 136   | i2c_i801   | E3FC4E0622 |
| 8086:283e | 1025:011f | Intel      | 82801H (ICH8 Family) SMBu... | 135   | i2c_i801   | 8592F1650F |
| 8086:1c22 | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 132   | i2c_i801   | 532A1D3D01 |
| 8086:1e22 | 17aa:21f6 | Intel      | 7 Series/C216 Chipset Fam... | 131   | i2c_i801   | 69A252CCD6 |
| 8086:9c22 | 17aa:220c | Intel      | 8 Series SMBus Controller    | 130   | i2c_i801   | 415CC7FE56 |
| 8086:1e22 | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 129   | i2c_i801   | D74C10F41F |
| 8086:9da3 | 17aa:2279 | Intel      | Cannon Point-LP SMBus Con... | 127   | i2c_i801   | A01E524A66 |
| 8086:2930 | 1028:0233 | Intel      | 82801I (ICH9 Family) SMBu... | 124   | i2c_i801   | 6B7EF9CAD5 |
| 8086:9d23 | 103c:8079 | Intel      | Sunrise Point-LP SMBus       | 123   | i2c_i801   | 436E9BF227 |
| 1022:790b | 103c:8330 | AMD        | FCH SMBus Controller         | 120   | i2c_piix4  | 18CEA74915 |
| 8086:9d23 | 1025:1193 | Intel      | Sunrise Point-LP SMBus       | 119   | i2c_i801   | 43BFEF3BCD |
| 8086:9d23 | 8086:7270 | Intel      | Sunrise Point-LP SMBus       | 119   | i2c_i801   | DD20DE340C |
| 8086:8c22 | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 118   | i2c_i801   | 36F407C3AA |
| 8086:1e22 | 10cf:16e6 | Intel      | 7 Series/C216 Chipset Fam... | 117   | i2c_i801   | 4639F065C8 |
| 8086:1e22 | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 117   | i2c_i801   | 779684E41D |
| 8086:9c22 | 103c:198f | Intel      | 8 Series SMBus Controller    | 115   | i2c_i801   | CECD552E89 |
| 8086:2930 | 1028:02aa | Intel      | 82801I (ICH9 Family) SMBu... | 114   | i2c_i801   | E8E9A85406 |
| 8086:a323 | 1028:087c | Intel      | Cannon Lake PCH SMBus Con... | 114   | i2c_i801   | 0FA8C3ED0C |
| 8086:1c22 | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 113   | i2c_i801   | FC712846D9 |
| 8086:27da | 1025:0349 | Intel      | NM10/ICH7 Family SMBus Co... | 112   | i2c_i801   | 09B8FC981C |
| 8086:1e22 | 1179:fb31 | Intel      | 7 Series/C216 Chipset Fam... | 111   | i2c_i801   | E9FAA1A00B |
| 8086:9ca2 | 17aa:5034 | Intel      | Wildcat Point-LP SMBus Co... | 111   | i2c_i801   | CEA37DD548 |
| 8086:9da3 | 103c:8549 | Intel      | Cannon Point-LP SMBus Con... | 111   | i2c_i801   | A814284F0B |
| 8086:0f12 | 17aa:3905 | Intel      | Atom Processor E3800/CE27... | 110   | i2c_i801   | 1387FAB9FE |
| 8086:9d23 | 1028:0810 | Intel      | Sunrise Point-LP SMBus       | 110   | i2c_i801   | C01FA4B013 |
| 8086:9c22 | 1025:0866 | Intel      | 8 Series SMBus Controller    | 109   | i2c_i801   | 11EBF2008B |
| 8086:9d23 | 17aa:225d | Intel      | Sunrise Point-LP SMBus       | 109   | i2c_i801   | FEB7F2A285 |
| 8086:1c22 | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 107   | i2c_i801   | 4104E265EA |
| 8086:1c22 | 104d:908b | Intel      | 6 Series/C200 Series Chip... | 106   | i2c_i801   | 11EF4D4BAF |
| 8086:9c22 | 1028:0651 | Intel      | 8 Series SMBus Controller    | 106   | i2c_i801   | 0862DC626B |
| 8086:1e22 | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 105   | i2c_i801   | 8BC152AA27 |
| 8086:1c22 | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 103   | i2c_i801   | 89DF37A291 |
| 8086:1c22 | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 100   | i2c_i801   | 966E771791 |
| 8086:1e22 | 1043:1477 | Intel      | 7 Series/C216 Chipset Fam... | 99    | i2c_i801   | 1D158DC1F0 |
| 8086:1e22 | 1043:14c7 | Intel      | 7 Series/C216 Chipset Fam... | 99    | i2c_i801   | BC26A9B439 |
| 8086:9d23 | 1028:07e6 | Intel      | Sunrise Point-LP SMBus       | 99    | i2c_i801   | 5A56854746 |
| 8086:a123 | 1028:07be | Intel      | 100 Series/C230 Series Ch... | 99    | i2c_i801   | 69938C221E |
| 8086:283e | 1028:01f9 | Intel      | 82801H (ICH8 Family) SMBu... | 98    | i2c_i801   | 6DBCD5A1C8 |
| 8086:0f12 | 17aa:3909 | Intel      | Atom Processor E3800/CE27... | 96    | i2c_i801   | 184B909FC0 |
| 8086:9c22 | 1025:0775 | Intel      | 8 Series SMBus Controller    | 96    | i2c_i801   | 0385B295A7 |
| 8086:9d23 | 1043:12d1 | Intel      | Sunrise Point-LP SMBus       | 95    | i2c_i801   | 703D0F2090 |
| 1022:790b | 1043:18f1 | AMD        | FCH SMBus Controller         | 92    | i2c_piix4  | 456B686D28 |
| 8086:9da3 | 1028:08af | Intel      | Cannon Point-LP SMBus Con... | 92    | i2c_i801   | 52DEA66C52 |
| 8086:02a3 | 1028:0962 | Intel      | Comet Lake PCH-LP SMBus H... | 91    | i2c_i801   | 8956FEE2F3 |
| 8086:9d23 | 1028:078b | Intel      | Sunrise Point-LP SMBus       | 91    | i2c_i801   | 35BCBD121B |
| 1022:790b | 17aa:5081 | AMD        | FCH SMBus Controller         | 90    | i2c_pii... | 273A5FF27D |
| 8086:9c22 | 8086:7270 | Intel      | 8 Series SMBus Controller    | 90    | i2c_i801   | 0C24CAF245 |
| 8086:9d23 | 17aa:3841 | Intel      | Sunrise Point-LP SMBus       | 89    | i2c_i801   | 4EB6B00CAC |
| 8086:9d23 | 8086:9d23 | Intel      | Sunrise Point-LP SMBus       | 89    | i2c_i801   | F3E5EBA0C2 |
| 8086:9da3 | 17aa:5072 | Intel      | Cannon Point-LP SMBus Con... | 89    | i2c_i801   | 3678E02E46 |
| 8086:9c22 | 17aa:2214 | Intel      | 8 Series SMBus Controller    | 88    | i2c_i801   | F802ABEF07 |
| 8086:9ca2 | 17aa:2226 | Intel      | Wildcat Point-LP SMBus Co... | 88    | i2c_i801   | 22A87CB141 |
| 1002:4385 | 103c:3577 | AMD        | SBx00 SMBus Controller       | 87    | i2c_pii... | 8E3CEB5DB9 |
| 1022:790b | 103c:84ac | AMD        | FCH SMBus Controller         | 87    | i2c_piix4  | 3A06ECCCAA |
| 8086:1e22 | 103c:1854 | Intel      | 7 Series/C216 Chipset Fam... | 86    | i2c_i801   | B0ED67249E |
| 8086:283e | 1028:022f | Intel      | 82801H (ICH8 Family) SMBu... | 86    | i2c_i801   | 38B4BA227C |
| 8086:5ad4 | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 86    | i2c_i801   | 64BC2367EF |
| 8086:9ca2 | 103c:2216 | Intel      | Wildcat Point-LP SMBus Co... | 86    | i2c_i801   | FFB40F821B |
| 8086:9d23 | 17aa:225c | Intel      | Sunrise Point-LP SMBus       | 86    | i2c_i801   | 2B4A1A20D9 |
| 8086:9d23 | 17aa:5068 | Intel      | Sunrise Point-LP SMBus       | 86    | i2c_i801   | 2A70ED5588 |
| 8086:9da3 | 17aa:2292 | Intel      | Cannon Point-LP SMBus Con... | 86    | i2c_i801   | 26C62915E0 |
| 8086:a323 | 1025:1264 | Intel      | Cannon Lake PCH SMBus Con... | 86    | i2c_i801   | 7F70DE1771 |
| 8086:1e22 | 144d:c652 | Intel      | 7 Series/C216 Chipset Fam... | 85    | i2c_i801   | BCA6D30092 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e20 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 574   | snd_hda... | 16EBDC4388 |
| 8086:293e | 17aa:20f2 | Intel      | 82801I (ICH9 Family) HD A... | 336   | snd_hda... | 9A7BE426F5 |
| 10de:0bea |           | Nvidia     | GF108 High Definition Aud... | 333   | snd_hda... | 997A879973 |
| 1002:15de | 1002:15de | AMD        | Raven/Raven2/Fenghuang HD... | 321   | snd_hda... | 31B241368B |
| 8086:3b56 | 17aa:215e | Intel      | 5 Series/3400 Series Chip... | 321   | snd_hda... | 570863FD8C |
| 8086:1c20 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 320   | snd_hda... | D1D57448C4 |
| 8086:0a0c | 17aa:3978 | Intel      | Haswell-ULT HD Audio Cont... | 312   | snd_hda... | 3CDDE1061C |
| 8086:9c20 | 17aa:3978 | Intel      | 8 Series HD Audio Controller | 312   | snd_hda... | 3CDDE1061C |
| 10de:0fb9 |           | Nvidia     | GP107GL High Definition A... | 301   | snd_hda... | D55AC505B9 |
| 8086:0c0c | 8086:2010 | Intel      | Xeon E3-1200 v3/4th Gen C... | 298   | snd_hda... | 739623468A |
| 8086:9ca0 | 8086:7270 | Intel      | Wildcat Point-LP High Def... | 295   | snd_hda... | 5BE083EDAB |
| 8086:1c20 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 201   | snd_hda... | ECC4515014 |
| 1002:1637 | 1002:1637 | AMD        | Renoir Radeon High Defini... | 198   | snd_hda... | 3F7A2585FE |
| 8086:1e20 | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 194   | snd_hda... | C9D8EFC9B9 |
| 8086:1e20 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 191   | snd_hda... | 783D081B5A |
| 10de:0ac0 | 10de:cb79 | Nvidia     | MCP79 High Definition Audio  | 173   | snd_hda... | 25B2F96576 |
| 8086:1c20 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 173   | snd_hda... | A75FFD5203 |
| 8086:8c20 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 170   | snd_hda... | 60FA5FF04C |
| 8086:1e20 | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 167   | snd_hda... | EC8AF5F350 |
| 8086:0c0c | 17aa:3978 | Intel      | Xeon E3-1200 v3/4th Gen C... | 166   | snd_hda... | 60FA5FF04C |
| 8086:1e20 | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 165   | snd_hda... | 82E60126C9 |
| 8086:0a0c | 8086:2010 | Intel      | Haswell-ULT HD Audio Cont... | 164   | snd_hda... | 68FB5BB4E8 |
| 8086:293e | 17aa:3a0d | Intel      | 82801I (ICH9 Family) HD A... | 163   | snd_hda... | B9412E1AB2 |
| 8086:1c20 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 159   | snd_hda... | 4C3C43DAAA |
| 10de:10f1 |           | Nvidia     | GP106 High Definition Aud... | 158   | snd_hda... | A84248C5D5 |
| 8086:1c20 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 158   | snd_hda... | B66EB36016 |
| 8086:284b | 17aa:20ac | Intel      | 82801H (ICH8 Family) HD A... | 157   | snd_hda... | 87E69E1105 |
| 8086:a348 | 1025:1331 | Intel      | Cannon Lake PCH cAVS         | 157   | snd_hda... | BC9DC107D1 |
| 8086:3b56 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 150   | snd_hda... | BA51FC9216 |
| 8086:9d71 | 17aa:3837 | Intel      | Sunrise Point-LP HD Audio    | 147   | snd_hda... | F86520F5A7 |
| 8086:3b56 | 17aa:38af | Intel      | 5 Series/3400 Series Chip... | 146   | snd_hda... | 80B7F3E584 |
| 8086:3198 | 1043:1de0 | Intel      | Celeron/Pentium Silver Pr... | 145   | snd_hda... | 5C95C74B6C |
| 1002:9840 | 17aa:3801 | AMD        | Kabini HDMI/DP Audio         | 143   | snd_hda... | 0CDC6E9D84 |
| 1022:780d | 17aa:3801 | AMD        | FCH Azalia Controller        | 143   | snd_hda... | 0CDC6E9D84 |
| 8086:1e20 | 1028:0534 | Intel      | 7 Series/C216 Chipset Fam... | 142   | snd_hda... | FA4D12994D |
| 8086:a348 | 1028:0905 | Intel      | Cannon Lake PCH cAVS         | 142   | snd_hda... | 58E43F0514 |
| 8086:1c20 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 141   | snd_hda... | 0A8E84DFAD |
| 8086:02c8 | 17aa:5079 | Intel      | Comet Lake PCH-LP cAVS       | 138   | snd_hda... | A35AAAEB6D |
| 8086:3b56 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 138   | snd_hda... | A18FB33A6F |
| 8086:3b56 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 136   | snd_hda... | 77E0B6A916 |
| 10de:10fa | 1025:1332 | Nvidia     | TU107 GeForce GTX 1650 Hi... | 134   | snd_hda... | BC9DC107D1 |
| 8086:284b | 1025:011f | Intel      | 82801H (ICH8 Family) HD A... | 134   | snd_hda... | 8592F1650F |
| 8086:1c20 | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 132   | snd_hda... | 532A1D3D01 |
| 8086:1e20 | 17aa:21f6 | Intel      | 7 Series/C216 Chipset Fam... | 131   | snd_hda... | 69A252CCD6 |
| 8086:0a0c | 17aa:220c | Intel      | Haswell-ULT HD Audio Cont... | 130   | snd_hda... | 415CC7FE56 |
| 8086:1e20 | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 129   | snd_hda... | D74C10F41F |
| 8086:9dc8 | 17aa:2279 | Intel      | Cannon Point-LP High Defi... | 126   | snd_hda... | A01E524A66 |
| 8086:293e | 1028:0233 | Intel      | 82801I (ICH9 Family) HD A... | 124   | snd_hda... | 6B7EF9CAD5 |
| 8086:160c | 106b:011b | Intel      | Broadwell-U Audio Controller | 122   | snd_hda... | 5BE083EDAB |
| 8086:9d70 | 103c:8079 | Intel      | Sunrise Point-LP HD Audio    | 122   | snd_hda... | 436E9BF227 |
| 1002:15b3 | 103c:8330 | AMD        | High Definition Audio Con... | 120   | snd_hda... | 18CEA74915 |
| 1022:157a | 103c:8330 | AMD        | Family 15h (Models 60h-6f... | 120   | snd_hda... | 18CEA74915 |
| 10de:0e0f |           | Nvidia     | GK208 HDMI/DP Audio Contr... | 119   | snd_hda... | A5F750922A |
| 8086:27d8 | 1043:8437 | Intel      | NM10/ICH7 Family High Def... | 119   | snd_hda... | E74DC83F0A |
| 8086:0c0c | 17aa:220e | Intel      | Xeon E3-1200 v3/4th Gen C... | 118   | snd_hda... | 36F407C3AA |
| 8086:8c20 | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 118   | snd_hda... | 36F407C3AA |
| 8086:1c20 | 103c:161c | Intel      | 6 Series/C200 Series Chip... | 117   | snd_hda... | B6AC4539D1 |
| 8086:1e20 | 1043:118f | Intel      | 7 Series/C216 Chipset Fam... | 117   | snd_hda... | 3498166FA2 |
| 8086:1e20 | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 117   | snd_hda... | 779684E41D |
| 8086:9d71 | 1025:1193 | Intel      | Sunrise Point-LP HD Audio    | 117   | snd_hda... | 43BFEF3BCD |
| 8086:0a0c | 103c:198f | Intel      | Haswell-ULT HD Audio Cont... | 115   | snd_hda... | CECD552E89 |
| 8086:1e20 | 10cf:1757 | Intel      | 7 Series/C216 Chipset Fam... | 114   | snd_hda... | 4639F065C8 |
| 8086:293e | 1028:02aa | Intel      | 82801I (ICH9 Family) HD A... | 114   | snd_hda... | E8E9A85406 |
| 8086:9c20 | 103c:198f | Intel      | 8 Series HD Audio Controller | 114   | snd_hda... | CECD552E89 |
| 8086:a348 | 1028:087c | Intel      | Cannon Lake PCH cAVS         | 114   | snd_hda... | 0FA8C3ED0C |
| 8086:1c20 | 1043:1ac3 | Intel      | 6 Series/C200 Series Chip... | 113   | snd_hda... | FC712846D9 |
| 8086:27d8 | 1025:0349 | Intel      | NM10/ICH7 Family High Def... | 112   | snd_hda... | 09B8FC981C |
| 8086:160c | 17aa:5034 | Intel      | Broadwell-U Audio Controller | 111   | snd_hda... | CEA37DD548 |
| 8086:0f04 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 110   | snd_hda... | 1387FAB9FE |
| 8086:9d71 | 1028:0810 | Intel      | Sunrise Point-LP HD Audio    | 110   | snd_hda... | C01FA4B013 |
| 8086:9dc8 | 103c:8549 | Intel      | Cannon Point-LP High Defi... | 110   | snd_hda... | A814284F0B |
| 8086:0a0c | 1025:0866 | Intel      | Haswell-ULT HD Audio Cont... | 109   | snd_hda... | 11EBF2008B |
| 8086:9d71 | 17aa:225d | Intel      | Sunrise Point-LP HD Audio    | 109   | snd_hda... | FEB7F2A285 |
| 8086:1e20 | 103c:179b | Intel      | 7 Series/C216 Chipset Fam... | 108   | snd_hda... | 1B2FBCDFA0 |
| 8086:293e | 1111:1043 | Intel      | 82801I (ICH9 Family) HD A... | 108   | snd_hda... | 0DC4D38ED2 |
| 8086:1c20 | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 107   | snd_hda... | 4104E265EA |
| 8086:0a0c | 1028:0651 | Intel      | Haswell-ULT HD Audio Cont... | 106   | snd_hda... | 0862DC626B |
| 8086:1c20 | 104d:908b | Intel      | 6 Series/C200 Series Chip... | 106   | snd_hda... | 11EF4D4BAF |
| 8086:3b56 | 1043:1643 | Intel      | 5 Series/3400 Series Chip... | 106   | snd_hda... | 0EEDFC8A67 |
| 8086:9c20 | 1028:0651 | Intel      | 8 Series HD Audio Controller | 106   | snd_hda... | 0862DC626B |
| 8086:9d71 | 1043:1a40 | Intel      | Sunrise Point-LP HD Audio    | 106   | snd_hda... | EED2A8B965 |
| 8086:1e20 | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 105   | snd_hda... | 8BC152AA27 |
| 8086:1c20 | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 103   | snd_hda... | 89DF37A291 |
| 1002:1714 | 1002:1714 | AMD        | BeaverCreek HDMI Audio [R... | 102   | snd_hda... | A740A2FAA5 |
| 8086:1c20 | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 100   | snd_hda... | 966E771791 |
| 8086:9d71 | 1028:07e6 | Intel      | Sunrise Point-LP HD Audio    | 99    | snd_hda... | 5A56854746 |
| 8086:a171 | 1028:07be | Intel      | CM238 HD Audio Controller    | 99    | snd_hda... | 69938C221E |
| 8086:284b | 1028:01f9 | Intel      | 82801H (ICH8 Family) HD A... | 98    | snd_hda... | 6DBCD5A1C8 |
| 8086:9d71 | 1043:1460 | Intel      | Sunrise Point-LP HD Audio    | 98    | snd_hda... | 703D0F2090 |
| 8086:0a0c | 1025:0775 | Intel      | Haswell-ULT HD Audio Cont... | 96    | snd_hda... | 0385B295A7 |
| 8086:0f04 | 17aa:3909 | Intel      | Atom Processor Z36xxx/Z37... | 96    | snd_hda... | 184B909FC0 |
| 10de:0fbc |           | Nvidia     | GM107 High Definition Aud... | 95    | snd_hda... | 984D3CDC29 |
| 8086:0f04 | 8086:0f04 | Intel      | Atom Processor Z36xxx/Z37... | 95    | snd_hda... | D04BD787B3 |
| 1022:15e3 | 1043:18f1 | AMD        | Family 17h (Models 10h-1f... | 92    | snd_hda... | 456B686D28 |
| 8086:9dc8 | 1028:08af | Intel      | Cannon Point-LP High Defi... | 92    | snd_hda... | 52DEA66C52 |
| 1002:aa68 | 1043:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 91    | snd_hda... | EDEC5D042A |
| 8086:02c8 | 1028:0962 | Intel      | Comet Lake PCH-LP cAVS       | 91    | snd_hda... | 8956FEE2F3 |
| 1002:1637 | 17aa:5081 | AMD        | Renoir Radeon High Defini... | 90    | snd_hda... | 273A5FF27D |
| 1022:15e3 | 17aa:5081 | AMD        | Family 17h (Models 10h-1f... | 90    | snd_hda... | 273A5FF27D |
| 8086:1c20 | 1043:1b43 | Intel      | 6 Series/C200 Series Chip... | 90    | snd_hda... | E7BE61DF28 |

### Storage (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1217:8231 | 1028:0493 | O2 Micro   | O2Micro Integrated MS/MSP... | 154   |            | 4C3C43DAAA |
| 104c:803b | 1025:011f | Texas I... | PCIxx12 Flash Media Contr... | 135   | tifm_7xx1  | 8592F1650F |
| 1217:8331 | 1028:0494 | O2 Micro   | O2 Flash Memory Card         | 66    |            | B84EF4472B |
| 1217:7130 | 1179:ff50 | O2 Micro   | Integrated MS/xD Controller  | 60    |            | ABCF2EEE75 |
| 104c:803b | 1179:ff00 | Texas I... | PCIxx12 Flash Media Contr... | 54    | tifm_7xx1  | 1BF61C0698 |
| 1217:8331 | 1028:049a | O2 Micro   | O2 Flash Memory Card         | 44    |            | 3405536413 |
| 1217:7130 | 10cf:143d | O2 Micro   | Integrated MS/xD Controller  | 43    |            | 5F0BCD4C39 |
| 104c:803b | 1179:ff02 | Texas I... | PCIxx12 Flash Media Contr... | 41    | tifm_7xx1  | 371CF70DA6 |
| 1217:8330 | 1028:04a3 | O2 Micro   | OZ600 MS/xD Controller       | 39    |            | F442DF91A1 |
| 104c:803b | 1179:ff10 | Texas I... | PCIxx12 Flash Media Contr... | 38    | tifm_7xx1  | 68AC15EEDA |
| 1217:8331 | 1028:049b | O2 Micro   | O2 Flash Memory Card         | 38    |            | A1027F938F |
| 104c:803b | 104d:9005 | Texas I... | PCIxx12 Flash Media Contr... | 37    | tifm_7xx1  | EF87C7EE7B |
| 1217:7130 | 1025:013c | O2 Micro   | Integrated MS/xD Controller  | 35    |            | 3BB0BC9C4D |
| 104c:803b | 104d:9015 | Texas I... | PCIxx12 Flash Media Contr... | 30    | tifm_7xx1  | 538C03B235 |
| 104c:803b | 104d:902d | Texas I... | PCIxx12 Flash Media Contr... | 28    | tifm_7xx1  | F76AE4B159 |
| 1217:7130 | 10cf:14d6 | O2 Micro   | Integrated MS/xD Controller  | 24    |            | 08576DED50 |
| 1217:8231 | 1028:04a9 | O2 Micro   | O2Micro Integrated MS/MSP... | 21    |            | 08E1D2F464 |
| 104c:803b | 1025:0107 | Texas I... | PCIxx12 Flash Media Contr... | 20    | tifm_7xx1  | D6632FCD8B |
| 104c:803b | 1179:0001 | Texas I... | PCIxx12 Flash Media Contr... | 20    | tifm_7xx1  | DF9FBBE08C |
| 104c:803b | 104d:9016 | Texas I... | PCIxx12 Flash Media Contr... | 17    | tifm_7xx1  | 3F2717CA34 |
| 1217:8330 | 1028:04a4 | O2 Micro   | OZ600 MS/xD Controller       | 17    |            | 3C06AD8F67 |
| 104c:803b | 1025:0110 | Texas I... | PCIxx12 Flash Media Contr... | 16    | tifm_7xx1  | 37E8699217 |
| 104c:803b | 103c:30aa | Texas I... | PCIxx12 Flash Media Contr... | 16    | tifm_7xx1  | 11A771B463 |
| 104c:803b | 104d:81ef | Texas I... | PCIxx12 Flash Media Contr... | 15    | tifm_7xx1  | 7C1F897BC6 |
| 104c:803b | 1179:ff31 | Texas I... | PCIxx12 Flash Media Contr... | 15    | tifm_7xx1  | 1B17B5C927 |
| 104c:803b | 1028:02ef | Texas I... | PCIxx12 Flash Media Contr... | 14    | tifm_7xx1  | E56C7EF208 |
| 104c:803b | 104d:9008 | Texas I... | PCIxx12 Flash Media Contr... | 12    | tifm_7xx1  | B41310BEF2 |
| 1217:7130 | 1028:0273 | O2 Micro   | Integrated MS/xD Controller  | 12    |            | 186F1ABCFA |
| 1217:8130 | 1028:02bc | O2 Micro   | Integrated MS/MSPRO/xD Co... | 12    |            | 27A5765EA0 |
| 104c:803b | 104d:81e6 | Texas I... | PCIxx12 Flash Media Contr... | 11    | tifm_7xx1  | 9B51D6EFF6 |
| 1217:8130 | 1028:02eb | O2 Micro   | Integrated MS/MSPRO/xD Co... | 11    |            | 8E77A169F4 |
| 104c:8033 | 1179:ff05 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 10    | tifm_7xx1  | FFE4B92DA3 |
| 104c:803b | 1025:0112 | Texas I... | PCIxx12 Flash Media Contr... | 10    | tifm_7xx1  | 56639ACA29 |
| 104c:803b | 1025:011c | Texas I... | PCIxx12 Flash Media Contr... | 10    | tifm_7xx1  | 04031AB433 |
| 104c:803b | 103c:30ad | Texas I... | PCIxx12 Flash Media Contr... | 10    | tifm_7xx1  | 8E613ADF36 |
| 104c:803b | 104d:8212 | Texas I... | PCIxx12 Flash Media Contr... | 10    | tifm_7xx1  | 7A0E2DFD11 |
| 1217:8130 | 1179:ff50 | O2 Micro   | Integrated MS/MSPRO/xD Co... | 10    |            | 721A4DF615 |
| 104c:8033 | 103c:0944 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 9     | tifm_7xx1  | 7F042FAA64 |
| 104c:ac8f | 104d:8190 | Texas I... | PCI7420/7620 SD/MS-Pro Co... | 9     | tifm_7xx1  | 8E75F0E93F |
| 104c:8033 | 17c0:3007 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 8     | tifm_7xx1  | E8BFF6EA3D |
| 104c:803b | 103c:30b1 | Texas I... | PCIxx12 Flash Media Contr... | 8     | tifm_7xx1  | EEAEE9F1AD |
| 104c:803b | 1179:ff03 | Texas I... | PCIxx12 Flash Media Contr... | 8     | tifm_7xx1  | DF46118AC3 |
| 1217:8330 | 10cf:16ae | O2 Micro   | OZ600 MS/xD Controller       | 7     |            | A470EEAA37 |
| 104c:8033 | 103c:30a4 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 6     | tifm_7xx1  | 54E16F7626 |
| 104c:803b | 1025:0102 | Texas I... | PCIxx12 Flash Media Contr... | 6     | tifm_7xx1  | 7E2DA6D3E9 |
| 104c:803b | 1025:0130 | Texas I... | PCIxx12 Flash Media Contr... | 6     | tifm_7xx1  | AC6597929A |
| 104c:803b | 103c:30a3 | Texas I... | PCIxx12 Flash Media Contr... | 6     | tifm_7xx1  | A33E615CC5 |
| 1217:7130 | 1462:3fc1 | O2 Micro   | Integrated MS/xD Controller  | 6     |            | 8DB6FA7A1C |
| 1217:7130 | 1462:3ff3 | O2 Micro   | Integrated MS/xD Controller  | 6     |            | 182064E2F6 |
| 1217:8130 | 1028:041b | O2 Micro   | Integrated MS/MSPRO/xD Co... | 6     |            | 65DA6AAB71 |
| 104c:8033 | 103c:0934 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 5     | tifm_7xx1  | BF69B6646D |
| 104c:8033 | 103c:3080 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 5     | tifm_7xx1  | 47FF7370CC |
| 104c:8033 | 103c:3082 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 5     | tifm_7xx1  | C98B9CF200 |
| 104c:8033 | 103c:3085 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 5     | tifm_7xx1  | 280B8AF5CC |
| 104c:803b | 1025:006c | Texas I... | PCIxx12 Flash Media Contr... | 5     | tifm_7xx1  | 2D3698DEC2 |
| 104c:803b | 103c:309f | Texas I... | PCIxx12 Flash Media Contr... | 5     | tifm_7xx1  | 3FFD093A67 |
| 1217:7130 | 1025:011a | O2 Micro   | Integrated MS/xD Controller  | 5     |            | C6DB94809C |
| 1217:7130 | 1025:012b | O2 Micro   | Integrated MS/xD Controller  | 5     |            | A01F7549B8 |
| 1217:7130 | 1028:0275 | O2 Micro   | Integrated MS/xD Controller  | 5     |            | D50123C66A |
| 1217:7130 | 107b:0390 | O2 Micro   | Integrated MS/xD Controller  | 5     |            | 716346340E |
| 1217:7130 | 1734:10c7 | O2 Micro   | Integrated MS/xD Controller  | 5     |            | 0D7EFB17BC |
| 1217:8130 | 1025:038b | O2 Micro   | Integrated MS/MSPRO/xD Co... | 5     |            | 6D3DBC9716 |
| 104c:8033 | 1025:0066 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 4     | tifm_7xx1  | 50122B9E8E |
| 104c:8033 | 103c:099c | Texas I... | PCIxx21/PCIxx11 Flash Med... | 4     | tifm_7xx1  | 5F105DDA68 |
| 104c:8033 | 103c:308b | Texas I... | PCIxx21/PCIxx11 Flash Med... | 4     | tifm_7xx1  | 8CC604ABC2 |
| 104c:8033 | 103c:309b | Texas I... | PCIxx21/PCIxx11 Flash Med... | 4     | tifm_7xx1  | B64833B0B1 |
| 104c:8033 | 1179:0001 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 4     | tifm_7xx1  | D5D7DAB02F |
| 104c:803b | 1025:0094 | Texas I... | PCIxx12 Flash Media Contr... | 4     | tifm_7xx1  | 9FE4562E0D |
| 104c:803b | 103c:30ac | Texas I... | PCIxx12 Flash Media Contr... | 4     | tifm_7xx1  | 50213B8AAB |
| 104c:803b | 103c:30b0 | Texas I... | PCIxx12 Flash Media Contr... | 4     | tifm_7xx1  | 14CC279C8C |
| 104c:803b | 104d:81fd | Texas I... | PCIxx12 Flash Media Contr... | 4     | tifm_7xx1  | 52E6107C87 |
| 104c:803b | 104d:820f | Texas I... | PCIxx12 Flash Media Contr... | 4     | tifm_7xx1  | 8D36EEE821 |
| 104c:803b | 152d:0753 | Texas I... | PCIxx12 Flash Media Contr... | 4     | tifm_7xx1  | 63BEE52058 |
| 104c:803b | 17aa:207c | Texas I... | PCIxx12 Flash Media Contr... | 4     | tifm_7xx1  | E609777F1D |
| 1217:7130 | 1025:010d | O2 Micro   | Integrated MS/xD Controller  | 4     |            | 287952FB68 |
| 1217:7130 | 1028:026f | O2 Micro   | Integrated MS/xD Controller  | 4     |            | 79951D3FA6 |
| 1217:7130 | 10cf:13c6 | O2 Micro   | Integrated MS/xD Controller  | 4     |            | 8648B42278 |
| 1217:7130 | 1462:4327 | O2 Micro   | Integrated MS/xD Controller  | 4     |            | 0DCF53C3D6 |
| 1217:7130 | 1462:7220 | O2 Micro   | Integrated MS/xD Controller  | 4     |            | E3C5F7A96F |
| 1217:7130 | 17aa:3a21 | O2 Micro   | Integrated MS/xD Controller  | 4     |            | EF8D0E4B6A |
| 1217:8231 | 1028:04e4 | O2 Micro   | O2Micro Integrated MS/MSP... | 4     |            | C2F47A86A3 |
| 104c:8033 | 1025:007e | Texas I... | PCIxx21/PCIxx11 Flash Med... | 3     | tifm_7xx1  | 60873D0A0E |
| 104c:8033 | 103c:3091 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 3     | tifm_7xx1  | F01F51C47C |
| 104c:8033 | 103c:309d | Texas I... | PCIxx21/PCIxx11 Flash Med... | 3     | tifm_7xx1  | 837230178B |
| 104c:8033 | 161f:203d | Texas I... | PCIxx21/PCIxx11 Flash Med... | 3     | tifm_7xx1  | A942E40F27 |
| 104c:803b | 104d:900f | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | DEBF4B3290 |
| 104c:803b | 107b:0366 | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | BCF6858E7D |
| 104c:803b | 107b:0685 | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | 185E86B37E |
| 104c:803b | 152d:0763 | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | BA6F03E565 |
| 104c:803b | 1854:005f | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | 7611C8EBB8 |
| 1217:7130 | 1025:0138 | O2 Micro   | Integrated MS/xD Controller  | 3     |            | 9098A95664 |
| 1217:7130 | 1631:c218 | O2 Micro   | Integrated MS/xD Controller  | 3     |            | 4EB6918C25 |
| 1217:7130 | 1734:10b8 | O2 Micro   | Integrated MS/xD Controller  | 3     |            | 73A0747F86 |
| 1217:8130 | 1028:02bb | O2 Micro   | Integrated MS/MSPRO/xD Co... | 3     |            | 95DC1639D3 |
| 1217:8130 | 10cf:1568 | O2 Micro   | Integrated MS/MSPRO/xD Co... | 3     |            | 9B2FC1E55F |
| 104c:8033 | 1025:0080 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 2     | tifm_7xx1  | 8B304AF834 |
| 104c:8033 | 103c:3081 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 2     | tifm_7xx1  | FDC2B74A29 |
| 104c:8033 | 107b:0460 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 2     | tifm_7xx1  | 53EC93715E |
| 104c:8033 | 1179:ff03 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 2     | tifm_7xx1  | 61FEA93E97 |
| 104c:8033 | 1734:1092 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 2     | tifm_7xx1  | 4D0D913872 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e03 | 17aa:3977 | Intel      | 7 Series Chipset Family 6... | 529   | ahci       | 16EBDC4388 |
| 8086:9c03 | 17aa:3978 | Intel      | 8 Series SATA Controller ... | 308   | ahci       | 3CDDE1061C |
| 8086:1c03 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 294   | ahci       | D1D57448C4 |
| 8086:2929 | 17aa:20f8 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 289   | ahci       | 59BE8CAA30 |
| 8086:3b2f | 17aa:2168 | Intel      | 5 Series/3400 Series Chip... | 279   | ahci       | 8B21B7CFFE |
| 8086:27c1 | 1043:83ad | Intel      | NM10/ICH7 Family SATA Con... | 255   | ahci       | E74DC83F0A |
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 225   | ahci       | 8948989999 |
| 144d:a801 | 144d:a801 | Samsung... | Electronics SATA controller  | 221   | ahci       | 5BE083EDAB |
| 8086:1e03 | 8086:7270 | Intel      | 7 Series Chipset Family 6... | 206   | ahci       | 783D081B5A |
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 197   | ahci       | 403E735C43 |
| 8086:1c03 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 196   | ahci       | ECC4515014 |
| 8086:1e03 | 17aa:21f3 | Intel      | 7 Series Chipset Family 6... | 185   | ahci       | C9D8EFC9B9 |
| 8086:3b29 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 178   | ahci       | E3FC4E0622 |
| 8086:1c03 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 166   | ahci       | A75FFD5203 |
| 8086:1e03 | 17aa:21fa | Intel      | 7 Series Chipset Family 6... | 162   | ahci       | EC8AF5F350 |
| 8086:1c03 | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 158   | ahci       | B96D5D5FDC |
| 10de:0ab9 | 10de:cb79 | Nvidia     | MCP79 AHCI Controller        | 156   | ahci       | 25B2F96576 |
| 8086:8c03 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 156   | ahci       | 60FA5FF04C |
| 8086:1e03 | 1025:0649 | Intel      | 7 Series Chipset Family 6... | 155   | ahci       | 82E60126C9 |
| 8086:1c03 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 152   | ahci       | B66EB36016 |
| 8086:31e3 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 151   | ahci       | F40D5FD5A7 |
| 8086:9d03 | 17aa:386a | Intel      | Sunrise Point-LP SATA Con... | 146   | ahci       | F86520F5A7 |
| 8086:31e3 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 143   | ahci       | 5C95C74B6C |
| 8086:a353 | 1028:0905 | Intel      | Cannon Lake Mobile PCH SA... | 140   | ahci       | 58E43F0514 |
| 8086:2929 | 17aa:3a1a | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 139   | ahci       | B9412E1AB2 |
| 8086:02d3 | 17aa:5079 | Intel      | Comet Lake SATA AHCI Cont... | 138   | ahci       | A35AAAEB6D |
| 8086:3b29 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 138   | ahci       | A18FB33A6F |
| 8086:1c03 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 135   | ahci       | 0A8E84DFAD |
| 8086:3b29 | 17aa:38c1 | Intel      | 5 Series/3400 Series Chip... | 135   | ahci       | 80B7F3E584 |
| 1022:7801 | 17aa:3801 | AMD        | FCH SATA Controller [AHCI... | 129   | ahci       | 0CDC6E9D84 |
| 8086:1c03 | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 129   | ahci       | 532A1D3D01 |
| 8086:9c03 | 17aa:220c | Intel      | 8 Series SATA Controller ... | 129   | ahci       | 415CC7FE56 |
| 8086:1e03 | 1043:124d | Intel      | 7 Series Chipset Family 6... | 128   | ahci       | 3498166FA2 |
| 8086:2829 | 17aa:20a7 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 128   | ahci       | 87E69E1105 |
| 8086:1e03 | 17aa:21f6 | Intel      | 7 Series Chipset Family 6... | 123   | ahci       | 69A252CCD6 |
| 8086:9d03 | 103c:8079 | Intel      | Sunrise Point-LP SATA Con... | 123   | ahci       | 436E9BF227 |
| 1022:7904 | 103c:8330 | AMD        | FCH SATA Controller [AHCI... | 120   | ahci       | 18CEA74915 |
| 8086:1e03 | 1025:064b | Intel      | 7 Series Chipset Family 6... | 119   | ahci       | D74C10F41F |
| 8086:3b29 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 118   | ahci       | 77E0B6A916 |
| 8086:8c03 | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 118   | ahci       | 36F407C3AA |
| 8086:9d03 | 1025:1193 | Intel      | Sunrise Point-LP SATA Con... | 114   | ahci       | 43BFEF3BCD |
| 8086:1e03 | 10cf:16e2 | Intel      | 7 Series Chipset Family 6... | 113   | ahci       | 4639F065C8 |
| 8086:1e03 | 17aa:5002 | Intel      | 7 Series Chipset Family 6... | 113   | ahci       | 779684E41D |
| 8086:a353 | 1028:087c | Intel      | Cannon Lake Mobile PCH SA... | 113   | ahci       | 0FA8C3ED0C |
| 8086:1c03 | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 110   | ahci       | FC712846D9 |
| 8086:9c03 | 1025:0866 | Intel      | 8 Series SATA Controller ... | 109   | ahci       | 11EBF2008B |
| 8086:9c03 | 103c:198f | Intel      | 8 Series SATA Controller ... | 109   | ahci       | CECD552E89 |
| 8086:9c83 | 17aa:5034 | Intel      | Wildcat Point-LP SATA Con... | 108   | ahci       | CEA37DD548 |
| 8086:1c03 | 104d:908b | Intel      | 6 Series/C200 Series Chip... | 106   | ahci       | 11EF4D4BAF |
| 8086:9c03 | 1028:0651 | Intel      | 8 Series SATA Controller ... | 106   | ahci       | 0862DC626B |
| 8086:2929 | 1028:02aa | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 105   | ahci       | E8E9A85406 |
| 8086:0f23 | 17aa:3905 | Intel      | Atom Processor E3800 Seri... | 103   | ahci       | 1387FAB9FE |
| 8086:1e03 | 103c:179b | Intel      | 7 Series Chipset Family 6... | 103   | ahci       | 1B2FBCDFA0 |
| 8086:1c03 | 103c:161c | Intel      | 6 Series/C200 Series Chip... | 102   | ahci       | 18F27D1F5C |
| 8086:1c03 | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 100   | ahci       | 89DF37A291 |
| 8086:1c03 | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 100   | ahci       | 4104E265EA |
| 8086:1e03 | 1025:0647 | Intel      | 7 Series Chipset Family 6... | 100   | ahci       | 8BC152AA27 |
| 8086:1e03 | 1179:fb31 | Intel      | 7 Series Chipset Family 6... | 100   | ahci       | E9FAA1A00B |
| 8086:27c1 | 1025:0349 | Intel      | NM10/ICH7 Family SATA Con... | 99    | ahci       | A2032BB3CD |
| 8086:0f23 | 17aa:3909 | Intel      | Atom Processor E3800 Seri... | 96    | ahci       | 184B909FC0 |
| 8086:1c03 | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 96    | ahci       | 966E771791 |
| 8086:9c03 | 1025:0775 | Intel      | 8 Series SATA Controller ... | 96    | ahci       | 0385B295A7 |
| 8086:1e03 | 1043:1477 | Intel      | 7 Series Chipset Family 6... | 95    | ahci       | 1D158DC1F0 |
| 8086:2929 | 1043:1867 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 95    | ahci       | 0DC4D38ED2 |
| 8086:9d03 | 1043:12d1 | Intel      | Sunrise Point-LP SATA Con... | 95    | ahci       | 703D0F2090 |
| 8086:1e03 | 1043:14c7 | Intel      | 7 Series Chipset Family 6... | 91    | ahci       | BC26A9B439 |
| 8086:9d03 | 1028:078b | Intel      | Sunrise Point-LP SATA Con... | 91    | ahci       | 35BCBD121B |
| 8086:a103 | 1028:07be | Intel      | HM170/QM170 Chipset SATA ... | 89    | ahci       | 69938C221E |
| 8086:9c03 | 17aa:2214 | Intel      | 8 Series SATA Controller ... | 88    | ahci       | F802ABEF07 |
| 8086:9c83 | 17aa:2226 | Intel      | Wildcat Point-LP SATA Con... | 88    | ahci       | 22A87CB141 |
| 1002:4391 | 103c:3577 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 87    | ahci       | 8E3CEB5DB9 |
| 1022:7904 | 103c:84ac | AMD        | FCH SATA Controller [AHCI... | 87    | ahci       | 3A06ECCCAA |
| 8086:1e03 | 103c:1854 | Intel      | 7 Series Chipset Family 6... | 86    | ahci       | B0ED67249E |
| 8086:5ae3 | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 86    | ahci       | 64BC2367EF |
| 8086:9c83 | 103c:2216 | Intel      | Wildcat Point-LP SATA Con... | 84    | ahci       | FFB40F821B |
| 1022:7901 | 1043:1e21 | AMD        | FCH SATA Controller [AHCI... | 83    | ahci       | 3802A77D98 |
| 8086:2829 | 1028:022f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 83    | ahci       | 38B4BA227C |
| 8086:1e03 | 144d:c652 | Intel      | 7 Series Chipset Family 6... | 82    | ahci       | BCA6D30092 |
| 8086:9d03 | 103c:832a | Intel      | Sunrise Point-LP SATA Con... | 80    | ahci       | C9FD6887D4 |
| 1022:7901 | 1025:1192 | AMD        | FCH SATA Controller [AHCI... | 79    | ahci       | F5F4E2457B |
| 8086:1c03 | 1179:fc30 | Intel      | 6 Series/C200 Series Chip... | 78    | ahci       | C70057C643 |
| 8086:2829 | 106b:00a1 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 77    | ahci       | 34FC60E37E |
| 8086:9c03 | 1043:131d | Intel      | 8 Series SATA Controller ... | 77    | ahci       | 50B1B1A6C5 |
| 8086:9c83 | 1025:098a | Intel      | Wildcat Point-LP SATA Con... | 77    | ahci       | CCE67D37AA |
| 8086:9dd3 | 17aa:3805 | Intel      | Cannon Point-LP SATA Cont... | 76    | ahci       | 2DB4EBB6EF |
| 8086:a353 | 17aa:3801 | Intel      | Cannon Lake Mobile PCH SA... | 76    | ahci       | EAF7694813 |
| 8086:9d03 | 1025:1295 | Intel      | Sunrise Point-LP SATA Con... | 75    | ahci       | 06114B7EB7 |
| 10de:0d88 | 106b:cb89 | Nvidia     | MCP89 SATA Controller (AH... | 74    | ahci       | 80E0B6AF9E |
| 8086:9d03 | 1025:115f | Intel      | Sunrise Point-LP SATA Con... | 74    | ahci       | 7046D52A8D |
| 8086:1e03 | 103c:17f6 | Intel      | 7 Series Chipset Family 6... | 73    | ahci       | E12D7E47E6 |
| 8086:2829 | 103c:30cc | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 73    | ahci       | DD3C7EF3E7 |
| 1022:7804 | 144d:c0da | AMD        | FCH SATA Controller [AHCI... | 72    | ahci       | 4EDBB1B2E6 |
| 8086:2829 | 1025:011f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 72    | ahci       | AAB5A9C849 |
| 8086:8c03 | 103c:1993 | Intel      | 8 Series/C220 Series Chip... | 72    | ahci       | 170DD8B241 |
| 8086:1e03 | 1028:0597 | Intel      | 7 Series Chipset Family 6... | 70    | ahci       | 5EBA5CDCBF |
| 8086:1e03 | 1179:ff1e | Intel      | 7 Series Chipset Family 6... | 70    | ahci       | 5AFFEECE1C |
| 8086:1e03 | 144d:c0d8 | Intel      | 7 Series Chipset Family 6... | 70    | ahci       | 2FDE85DC91 |
| 8086:9d03 | 17aa:5068 | Intel      | Sunrise Point-LP SATA Con... | 70    | ahci       | 2A70ED5588 |
| 1022:7901 | 17aa:380a | AMD        | FCH SATA Controller [AHCI... | 69    | ahci       | D9D0DD7C3C |
| 144d:1600 |           | Samsung... | Apple PCIe SSD               | 69    | ahci       | EABB3946AD |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2850 | 1025:011f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 135   | ata_pii... | 8592F1650F |
| 8086:2850 | 17aa:20a6 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 126   | pata_acpi  | 87E69E1105 |
| 8086:2850 | 1028:01f9 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 98    | pata_acpi  | 6DBCD5A1C8 |
| 8086:2850 | 1028:022f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 86    | pata_acpi  | 38B4BA227C |
| 8086:2850 | 106b:00a1 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 83    | pata_acpi  | 34FC60E37E |
| 8086:2828 | 1028:01f9 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 75    | pata_acpi  | 6DBCD5A1C8 |
| 8086:2850 | 103c:30cc | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 73    | pata_acpi  | DD3C7EF3E7 |
| 8086:2828 | 1025:011f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 67    | ata_pii... | 8592F1650F |
| 1039:5513 | 1039:5513 | Silicon... | 5513 IDE Controller          | 65    | pata_acpi  | AE3220A328 |
| 10de:0759 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] IDE    | 59    | pata_am... | B9B0C35DB8 |
| 1039:1183 | 1039:1183 | Silicon... | SATA Controller / IDE mode   | 58    | sata_si... | A9D87F6D4E |
| 10de:0ad0 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] SAT... | 58    | ahci, p... | B9B0C35DB8 |
| 1002:439c | 1043:104c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 52    | pata_at... | A2F8F1BE7D |
| 8086:27df | 17aa:200c | Intel      | 82801G (ICH7 Family) IDE ... | 50    | pata_acpi  | 2F3B34AAC4 |
| 1039:5513 | 1558:0801 | Silicon... | 5513 IDE Controller          | 49    | pata_acpi  | 6F701D72FD |
| 8086:2850 | 1179:ff00 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 49    | pata_acpi  | DF46118AC3 |
| 8086:2a46 | 17aa:20ea | Intel      | Mobile 4 Series Chipset P... | 49    | pata_acpi  | 36FB1F3891 |
| 8086:2850 | 1025:011e | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 48    | ata_pii... | 6472272BF7 |
| 8086:1e01 | 17aa:3977 | Intel      | 7 Series Chipset Family 4... | 47    | ata_pii... | A4DA62F3ED |
| 8086:27df | 8086:7270 | Intel      | 82801G (ICH7 Family) IDE ... | 47    | pata_acpi  | 0346BC764A |
| 8086:2850 | 1025:0136 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 47    | pata_acpi  | 01122F69F4 |
| 8086:2850 | 103c:30c0 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 47    | ata_pii... | 51AB06C26F |
| 8086:27c4 | 1025:0090 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 46    | ata_pii... | 45C723FAE8 |
| 8086:1e09 | 17aa:3977 | Intel      | 7 Series Chipset Family 2... | 44    | ata_pii... | A4DA62F3ED |
| 1002:4376 | 1025:009f | AMD        | IXP SB4x0 IDE Controller     | 43    | pata_at... | 86DFC89E4A |
| 8086:2850 | 103c:30d9 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 43    | pata_acpi  | 335CD848BB |
| 8086:27c4 | 1179:ff00 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 41    | pata_acpi  | 1BF61C0698 |
| 8086:2850 | 1025:0121 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 41    | pata_acpi  | D7C90EB05B |
| 8086:2928 | 17aa:20f7 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 41    | pata_acpi  | 9A7BE426F5 |
| 8086:27c4 | 1025:015b | Intel      | 82801GBM/GHM (ICH7-M Fami... | 40    | pata_acpi  | 24833C6A59 |
| 1002:438c | 1028:01f5 | AMD        | SB600 IDE                    | 39    | pata_at... | 58A2EF72C9 |
| 8086:27c4 | 1028:01bd | Intel      | 82801GBM/GHM (ICH7-M Fami... | 39    | pata_acpi  | FA750DAFE2 |
| 1039:1183 | 1558:0801 | Silicon... | SATA Controller / IDE mode   | 37    | sata_si... | 6F701D72FD |
| 8086:27c4 | 8086:7270 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 37    | pata_acpi  | 0346BC764A |
| 8086:2850 | 104d:9005 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 37    | pata_acpi  | EF87C7EE7B |
| 1039:1183 | 1043:1cf7 | Silicon... | SATA Controller / IDE mode   | 36    | sata_si... | 02E59A3759 |
| 1039:5513 | 1043:1cf7 | Silicon... | 5513 IDE Controller          | 36    | pata_acpi  | 02E59A3759 |
| 8086:1c01 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 36    | ata_pii... | 6074680FBA |
| 8086:1c09 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 36    | ata_pii... | 6074680FBA |
| 8086:27c4 | 1179:ff10 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 36    | pata_acpi  | EF126AD790 |
| 1002:4379 | 1002:4379 | AMD        | IXP SB4x0 Serial ATA Cont... | 33    | sata_si... | 86DFC89E4A |
| 8086:27df | 103c:30bb | Intel      | 82801G (ICH7 Family) IDE ... | 33    | pata_acpi  | 944D6AF89A |
| 8086:27df | 103c:30d5 | Intel      | 82801G (ICH7 Family) IDE ... | 33    | ata_pii... | 4AEA2D24B1 |
| 8086:2850 | 1179:ff50 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 33    | ata_pii... | A8F19BA877 |
| 10de:0550 | 103c:30cf | Nvidia     | MCP67 AHCI Controller        | 32    | ahci, p... | 896E1BC2A0 |
| 8086:27c4 | 1028:01c2 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 32    | pata_acpi  | ED344B9346 |
| 8086:27df | 17aa:3810 | Intel      | 82801G (ICH7 Family) IDE ... | 32    | ata_pii... | C344D683B4 |
| 8086:2828 | 17aa:20a8 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 32    | pata_acpi  | 87AAD99434 |
| 10de:0550 | 1025:0126 | Nvidia     | MCP67 AHCI Controller        | 31    | pata_ac... | AA6D721BF2 |
| 8086:27df | 103c:30a2 | Intel      | 82801G (ICH7 Family) IDE ... | 31    | ata_pii... | D678BE8583 |
| 8086:2828 | 104d:9015 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 30    | pata_acpi  | 538C03B235 |
| 8086:3b66 | 10cf:152e | Intel      | 5 Series/3400 Series Chip... | 30    | pata_acpi  | 08576DED50 |
| 8086:27c0 | 1043:83ad | Intel      | NM10/ICH7 Family SATA Con... | 29    | ata_pii... | 747B90D33C |
| 1002:438c | 1043:1417 | AMD        | SB600 IDE                    | 28    | pata_at... | 7A2E7C66E9 |
| 1002:438c | 1043:1627 | AMD        | SB600 IDE                    | 28    | pata_at... | 1D1AAD3900 |
| 1039:1183 | 1043:19e7 | Silicon... | SATA Controller / IDE mode   | 28    | sata_si... | C6AB19297F |
| 1039:5513 | 1043:19e7 | Silicon... | 5513 IDE Controller          | 28    | pata_acpi  | C6AB19297F |
| 8086:2850 | 104d:902d | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 28    | pata_acpi  | F76AE4B159 |
| 8086:3b2e | 17aa:2169 | Intel      | 5 Series/3400 Series Chip... | 28    | pata_acpi  | 5DA95784CA |
| 1022:780c | 103c:358d | AMD        | FCH IDE Controller           | 27    | pata_at... | 2E9D378E76 |
| 10de:0560 | 103c:30cf | Nvidia     | MCP67 IDE Controller         | 27    | pata_am... | 896E1BC2A0 |
| 8086:27c4 | 1043:830f | Intel      | 82801GBM/GHM (ICH7-M Fami... | 27    | pata_acpi  | FFB279A366 |
| 8086:2a46 | 1028:0233 | Intel      | Mobile 4 Series Chipset P... | 27    | pata_acpi  | EB47D36417 |
| 8086:3b2d | 17aa:216a | Intel      | 5 Series/3400 Series Chip... | 27    | pata_acpi  | 5DA95784CA |
| 1039:5513 | 1019:5a00 | Silicon... | 5513 IDE Controller          | 26    | pata_sis   | A9D87F6D4E |
| 8086:27c4 | 144d:ca00 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 26    | ata_pii... | 341F7C60ED |
| 8086:2850 | 1028:01fe | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 26    | ata_pii... | DAD4FD9AFE |
| 1002:438c | 144d:c034 | AMD        | SB600 IDE                    | 25    | pata_at... | FB06AE58F0 |
| 1039:1183 | 1039:1180 | Silicon... | SATA Controller / IDE mode   | 25    | sata_si... | AE3220A328 |
| 8086:2850 | 103c:30c5 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 25    | pata_acpi  | CBF5040FF7 |
| 1002:438c | 1028:022a | AMD        | SB600 IDE                    | 24    | pata_at... | AE3F94DFBF |
| 10de:0560 | 1025:0126 | Nvidia     | MCP67 IDE Controller         | 24    | pata_am... | AA6D721BF2 |
| 1002:438c | 103c:30c2 | AMD        | SB600 IDE                    | 23    | pata_at... | 46BE5BD9F4 |
| 8086:27c4 | 17aa:200e | Intel      | 82801GBM/GHM (ICH7-M Fami... | 23    | pata_acpi  | 5850A811E3 |
| 8086:27df | 10cf:1385 | Intel      | 82801G (ICH7 Family) IDE ... | 23    | pata_acpi  | 8B97914970 |
| 8086:2850 | 103c:3618 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 23    | pata_acpi  | 19817702A0 |
| 1002:439c | 1043:101c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 22    | pata_at... | AF980DC491 |
| 8086:2850 | 103c:30d8 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 22    | pata_acpi  | E880C038EB |
| 8086:2850 | 1043:14e7 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 22    | ata_pii... | 2494100ECB |
| 8086:2850 | 1179:ff1c | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 22    | pata_acpi  | 8B7FBF3DE6 |
| 8086:1c01 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 21    | pata_acpi  | 27F53DA246 |
| 8086:2653 | 1014:056a | Intel      | 82801FBM (ICH6M) SATA Con... | 21    | ata_piix   | 67510CC1AA |
| 8086:27c4 | 1043:1317 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 21    | ata_pii... | A54C655AE8 |
| 8086:27c4 | 17aa:3835 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 21    | pata_acpi  | C344D683B4 |
| 8086:2850 | 1179:ff40 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 21    | pata_acpi  | 9881895B74 |
| 8086:3b28 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 21    | pata_acpi  | 1515D7DFBF |
| 8086:3b2d | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 21    | pata_acpi  | 1515D7DFBF |
| 1002:439c | 17aa:3937 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 20    | pata_at... | F24F4A7CE9 |
| 8086:27c4 | 1025:0107 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 20    | ata_pii... | D6632FCD8B |
| 8086:27df | 1025:012e | Intel      | 82801G (ICH7 Family) IDE ... | 20    | ata_pii... | 7CFA18C731 |
| 8086:2a06 | 103c:30c5 | Intel      | Mobile PM965/GM965 PT IDE... | 20    | pata_acpi  | 940CCEBF1E |
| 8086:2a46 | 103c:30db | Intel      | Mobile 4 Series Chipset P... | 20    | pata_acpi  | AF8E63842A |
| 1002:439c | 1025:036e | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 19    | pata_at... | AE7E2AE414 |
| 10de:0265 | 103c:30b7 | Nvidia     | MCP51 IDE                    | 19    | pata_am... | C28788427E |
| 10de:0266 | 103c:30b7 | Nvidia     | MCP51 Serial ATA Controller  | 19    | sata_nv... | C28788427E |
| 8086:2850 | 1028:01f2 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 19    | pata_acpi  | C74668293E |
| 8086:2850 | 103c:30cd | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 19    | pata_acpi  | 0B9636C64B |
| 8086:811a | 1025:0244 | Intel      | US15W/US15X/US15L/UL11L S... | 19    | pata_sc... | EF2CC33022 |
| 8086:24ca | 1014:052d | Intel      | 82801DBM (ICH4-M) IDE Con... | 18    | pata_acpi  | 04747E3DF4 |
| 8086:27df | 103c:30a5 | Intel      | 82801G (ICH7 Family) IDE ... | 18    | pata_acpi  | D37099A83D |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 2451  | nvme       | F3E5EBA0C2 |
| 144d:a809 | 144d:a801 | Samsung... | NVMe SSD Controller 980      | 646   | nvme       | E58D33DF6B |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 620   | nvme       | 8CDB34DBC8 |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 596   | nvme       | 984D3CDC29 |
| 15b7:5006 | 15b7:5006 | Sandisk    | WD Black SN750 / PC SN730... | 587   | nvme       | C0B80E3276 |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | BC501 NVMe Solid State Drive | 453   | nvme       | 7125C6F5DD |
| 15b7:5003 | 15b7:5003 | Sandisk    | WD Blue SN500 / PC SN520 ... | 450   | nvme       | 67F0B45A7A |
| 1179:011a | 1179:0001 | Toshiba... | XG6 NVMe SSD Controller      | 395   | nvme       | F4B1EFA60F |
| 1e0f:0001 | 1e0f:0001 | KIOXIA     | Non-Volatile memory contr... | 375   | nvme       | DA5E2F59CC |
| 15b7:5009 | 15b7:5009 | Sandisk    | WD Blue SN550 NVMe SSD       | 365   | nvme       | F581CF8319 |
| 1c5c:1339 | 1c5c:0000 | SK Hynix   | BC511                        | 312   | nvme       | FF8C85568E |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 282   | nvme       | 623506F87F |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/SN750 / PC ... | 269   | nvme       | D0307FD66E |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 268   | nvme       | 5A56854746 |
| 2646:5008 | 2646:5008 | Kingsto... | U-SNS8154P3 NVMe SSD         | 257   | nvme       | 085EF9E58D |
| 1179:0113 | 1179:0001 | Toshiba... | BG3 NVMe SSD Controller      | 253   | nvme       | A35AAAEB6D |
| 8086:0000 |           | Intel      | PROSet/Wireless WiFi Soft... | 229   | nvme       | BC9DC107D1 |
| 1344:5410 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 208   | nvme       | EC802D2F0B |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 196   | nvme       | 8956FEE2F3 |
| 15b7:5005 | 15b7:5005 | Sandisk    | PC SN520 NVMe SSD            | 179   | nvme       | 8272A05168 |
| 1c5c:1627 | 1c5c:1627 | SK Hynix   | Non-Volatile memory contr... | 174   | nvme       | 58E43F0514 |
| 1c5c:1527 | 1c5c:1527 | SK Hynix   | PC401 NVMe Solid State Dr... | 169   | nvme       | 169DB6C9F8 |
| 1c5c:174a | 1c5c:174a | SK Hynix   | Gold P31 SSD                 | 168   | nvme       | 3F7A2585FE |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 149   | nvme       | 32F01CCAAB |
| 1c5c:1639 | 1c5c:1639 | SK Hynix   | Non-Volatile memory contr... | 149   | nvme       | 6AE3033841 |
| 126f:2263 | 126f:2263 | Silicon... | SM2263EN/SM2263XT SSD Con... | 142   | nvme       | 9BCD3D5479 |
| 1179:0115 | 1179:0001 | Toshiba... | XG4 NVMe SSD Controller      | 135   | nvme       | BF9CC483F0 |
| 2646:500c | 2646:500c | Kingsto... | Technology Company Non-Vo... | 130   | nvme       | A904DAF48D |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 121   | nvme       | 05087F89C1 |
| 144d:a80a | 144d:a801 | Samsung... | NVMe SSD Controller PM9A1... | 111   | nvme       | 4BF23FF82D |
| 1344:5405 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 110   | nvme       | 3CDC08297E |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 109   | nvme       | 23AA2C83AE |
| 15b7:5008 | 15b7:5008 | Sandisk    | Non-Volatile memory contr... | 107   | nvme       | CEC5669039 |
| 2646:2263 | 2646:2263 | Kingsto... | A2000 NVMe SSD               | 107   | nvme       | B91315EE52 |
| c0a9:2263 | c0a9:2263 | Micron/... | P1 NVMe PCIe SSD             | 101   | nvme       | EDD545A455 |
| 106b:2001 | 106b:2001 | Apple      | S1X NVMe Controller          | 87    | nvme       | 22A831DB3D |
| 1cc4:5008 | 1cc4:5008 | Union M... | Non-Volatile memory contr... | 81    | nvme       | 139F682D03 |
| 1cc1:33f3 | 1cc1:33f3 | ADATA T... | Non-Volatile memory contr... | 80    | nvme       | 5434B808B5 |
| 15b7:5004 | 15b7:5004 | Sandisk    | PC SN520 NVMe SSD            | 78    | nvme       | FEB7F2A285 |
| 8086:0975 | 8086:8410 | Intel      | Non-Volatile memory contr... | 70    | nvme       | 22728E37FE |
| 1e95:9100 | 126f:2263 | Solid S... | Non-Volatile memory contr... | 69    | nvme       | 370DDA1922 |
| 8086:0975 | 8086:8510 | Intel      | Non-Volatile memory contr... | 68    | nvme       | 22728E37FE |
| 1179:010f | 1179:0001 | Toshiba... | NVMe Controller              | 66    | nvme       | 4E8A3E6A15 |
| 1344:5404 | 1344:1100 | Micron ... | Non-Volatile memory contr... | 64    | nvme       | 47907AEC3E |
| 126f:2262 | 126f:2262 | Silicon... | SM2262/SM2262EN SSD Contr... | 56    | nvme       | 0A048A009D |
| 1987:5013 | 1987:5013 | Phison ... | PS5013 E13 NVMe Controller   | 54    | nvme       | 97B2732F29 |
| 106b:2005 | 106b:1800 | Apple      | ANS2 NVMe Controller         | 53    | nvme       | 7B3CDDA6E2 |
| 1cc1:33f8 | 1cc1:33f8 | ADATA T... | Non-Volatile memory contr... | 48    | nvme       | BCC833AC3C |
| 10ec:5763 | 10ec:5763 | Realtek... | Realtek Non-Volatile memo... | 43    | nvme       | 34B3BE8C54 |
| c0a9:540a | c0a9:540a | Micron/... | P2 NVMe PCIe SSD             | 42    | nvme       | 94E0E3F047 |
| 10ec:5762 | 10ec:5762 | Realtek... | RTS5763DL NVMe SSD Contro... | 39    | nvme       | FBE1D68B82 |
| 15b7:5007 | 15b7:5007 | Sandisk    | Non-Volatile memory contr... | 37    | nvme       | 5C569C3982 |
| 106b:2003 | 106b:2003 | Apple      | S3X NVMe Controller          | 36    | nvme       | 68EBC1AF79 |
| 14a4:2300 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 34    | nvme       | 4C18C08616 |
| 1987:5008 | 1987:5008 | Phison ... | NVMe Storage Controller      | 32    | nvme       | 07B1AA0F24 |
| 1cc4:6202 | 1cc4:1cc4 | Union M... | Non-Volatile memory contr... | 32    | nvme       | 4770866D46 |
| 14a4:9100 | 126f:2263 | Lite-On... | NVMe Controller              | 28    | nvme       | 8A880E6565 |
| 17aa:0006 | 17aa:1006 | Lenovo     | Non-Volatile memory contr... | 28    | nvme       | D8DB7F3FBD |
| 17aa:0003 | 17aa:1003 | Lenovo     | Non-Volatile memory contr... | 27    | nvme       | 2EAC1BFC4F |
| 1987:5016 | 1987:5016 | Phison ... | E16 PCIe4 NVMe Controller    | 27    | nvme       | C3581D7F8F |
| 1344:5404 | 1344:2100 | Micron ... | Non-Volatile memory contr... | 25    | nvme       | EFDB9E6636 |
| 2646:500d | 2646:500d | Kingsto... | OM3PDP3 NVMe SSD             | 25    | nvme       | DA5E2F59CC |
| 8086:2522 | 8086:3810 | Intel      | NVMe Optane Memory Series    | 24    | nvme       | 9EC292C9D9 |
| 17aa:0005 | 17aa:1005 | Lenovo     | Non-Volatile memory contr... | 22    | nvme       | B2CBCAA16B |
| 17aa:0004 | 17aa:1004 | Lenovo     | Non-Volatile memory contr... | 20    | nvme       | BE6EEE6FB4 |
| 1cc4:6203 | 1cc4:1cc4 | Union M... | Non-Volatile memory contr... | 17    | nvme       | 9B74440DEB |
| 1d97:1160 | 1d97:1160 | Shenzhe... | Non-Volatile memory contr... | 16    | nvme       | CDF70E6D0F |
| 14a4:2100 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 15    | nvme       | C65BE179D9 |
| 1bb1:5012 | 1bb1:5012 | Seagate... | FireCuda 510 SSD             | 15    | nvme       | 5C62EC0CE3 |
| 1c5c:1284 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 15    | nvme       | BB6272E86B |
| 14a4:3500 | 1b4b:1092 | Lite-On... | Non-Volatile memory contr... | 14    | nvme       | F6768265BF |
| 15b7:5001 | 1b4b:1093 | Sandisk    | WD Black NVMe SSD            | 13    | nvme       | BC63393A91 |
| 14a4:2200 | 1b4b:1093 | Lite-On... | Lite-On Non-Volatile memo... | 12    | nvme       | 2B63473D5B |
| 1c5c:1283 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 12    | nvme       | E7A049A026 |
| c0a9:5403 | c0a9:2100 | Micron/... | NVMe Controller              | 12    | nvme       | 080C5280D0 |
| c0a9:5412 | c0a9:0100 | Micron/... | Non-Volatile memory contr... | 12    | nvme       | 4150C71628 |
| 1cc4:2263 | 1cc4:1cc4 | Union M... | Non-Volatile memory contr... | 11    | nvme       | 69243BA50F |
| 15b7:5011 | 15b7:5011 | Sandisk    | WD Black SN850               | 10    | nvme       | EEB181F50B |
| 1c5c:1285 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 10    | nvme       | CC4AC84959 |
| 1cc4:5012 | 1cc4:5012 | Union M... | Non-Volatile memory contr... | 8     | nvme       | 9CD4E14D95 |
| 2646:2262 | 2646:2262 | Kingsto... | KC2000 NVMe SSD              | 8     | nvme       | 1BF80E2FCD |
| 8086:f1aa | 8086:390f | Intel      | Non-Volatile memory contr... | 8     | nvme       | 14D159C564 |
| 8086:faf0 | 8086:390e | Intel      | Non-Volatile memory contr... | 8     | nvme       | 6B06B9E5DD |
| 10ec:5760 | 5760:10ec | Realtek... | Realtek Non-Volatile memo... | 7     | nvme       | 70EB22C07E |
| 10ec:5765 | 10ec:5765 | Realtek... | Realtek Non-Volatile memo... | 7     | nvme       | 5233EA30C6 |
| 1cc4:17aa | 1cc4:17aa | Union M... | Non-Volatile memory contr... | 7     | nvme       | DB6FD3F608 |
| 1bb1:5016 | 1bb1:5016 | Seagate... | FireCuda 520 SSD             | 6     | nvme       | 9445D67978 |
| 1e95:3500 | 1b4b:1092 | Solid S... | Non-Volatile memory contr... | 6     | nvme       | D29FCFD047 |
| c0a9:5403 | c0a9:1100 | Micron/... | NVMe Controller              | 6     | nvme       | 23DBED3AB1 |
| 126f:2260 | 126f:2260 | Silicon... | Non-Volatile memory contr... | 5     | nvme       | 66F91918DC |
| 14a4:23f1 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 5     | nvme       | FCF1A988CF |
| 1c5c:1504 | 0100:1093 | SK Hynix   | SC300 512GB M.2 2280 SATA... | 5     | nvme       | 66C6D53439 |
| 1cc1:8201 | 1cc1:1cc1 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 5     | nvme       | 0D45D49199 |
| 1e0f:0009 | 1e0f:0001 | KIOXIA     | NVMe SSD                     | 5     | nvme       | 1E67C40AE2 |
| 1e0f:000d | 1e0f:0001 | KIOXIA     | Non-Volatile memory contr... | 5     | nvme       | 574B87362F |
| 2646:500e | 2646:500e | Kingsto... | SNVS2000G [NV1 NVMe PCIe ... | 5     | nvme       | 84B1C46F3C |
| 2646:500f | 2646:500f | Kingsto... | Technology Company Non-Vo... | 5     | nvme       | E2FBEC93E6 |
| 2646:5010 | 2646:5010 | Kingsto... | Technology Company Non-Vo... | 5     | nvme       | 8512EE02BD |
| 14a4:22f1 | 1b4b:1093 | Lite-On... | M8Pe Series NVMe SSD         | 4     | nvme       | 090F949643 |
| 1987:5007 | 1987:5007 | Phison ... | E7 NVMe Controller           | 4     | nvme       | 3DA8591AC6 |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:282a | 1025:1331 | Intel      | 82801 Mobile SATA Control... | 124   | intel_n... | BC9DC107D1 |
| 8086:282a | 1028:0233 | Intel      | 82801 Mobile SATA Control... | 103   | ahci       | FBC4BFA1B0 |
| 8086:282a | 1028:0493 | Intel      | 82801 Mobile SATA Control... | 94    | ahci       | 4C3C43DAAA |
| 8086:282a | 1028:0534 | Intel      | 82801 Mobile SATA Control... | 94    | ahci       | FA4D12994D |
| 8086:9a0b | 8086:0000 | Intel      | Volume Management Device ... | 87    | vmd        | 8CDB34DBC8 |
| 8086:282a | 1028:040a | Intel      | 82801 Mobile SATA Control... | 84    | ahci       | BA51FC9216 |
| 8086:282a | 1028:0810 | Intel      | 82801 Mobile SATA Control... | 68    | ahci       | C01FA4B013 |
| 8086:282a | 103c:84a6 | Intel      | 82801 Mobile SATA Control... | 68    | ahci       | F0A8FA5E7A |
| 8086:282a | 103c:1818 | Intel      | 82801 Mobile SATA Control... | 53    | ahci       | 31FF7DD229 |
| 8086:282a | 1028:05cb | Intel      | 82801 Mobile SATA Control... | 51    | ahci       | FE4153E816 |
| 8086:282a | 17aa:380f | Intel      | 82801 Mobile SATA Control... | 51    | ahci       | 3115478A9B |
| 8086:282a | 1025:1264 | Intel      | 82801 Mobile SATA Control... | 48    | ahci       | E0579175C3 |
| 8086:282a | 1025:1333 | Intel      | 82801 Mobile SATA Control... | 48    | intel_n... | 271C2188CB |
| 8086:282a | 1028:062e | Intel      | 82801 Mobile SATA Control... | 46    | ahci       | 91837758AC |
| 8086:282a | 103c:86c9 | Intel      | 82801 Mobile SATA Control... | 40    | ahci       | B81AB61049 |
| 8086:282a | 1028:0535 | Intel      | 82801 Mobile SATA Control... | 39    | ahci       | 41D65E59EB |
| 8086:282a | 103c:8532 | Intel      | 82801 Mobile SATA Control... | 39    | ahci       | B33C31B0CF |
| 8086:282a | 17aa:3814 | Intel      | 82801 Mobile SATA Control... | 37    | ahci       | DB1D64D8B0 |
| 8086:282a | 1028:05be | Intel      | 82801 Mobile SATA Control... | 35    | ahci       | DF9262F810 |
| 8086:282a | 1028:040b | Intel      | 82801 Mobile SATA Control... | 34    | ahci       | 25C1BD8E0E |
| 8086:282a | 1028:05bd | Intel      | 82801 Mobile SATA Control... | 34    | ahci       | 3020581460 |
| 8086:282a | 1028:05ca | Intel      | 82801 Mobile SATA Control... | 34    | ahci       | DBF0FD04C3 |
| 8086:282a | 1028:06dc | Intel      | 82801 Mobile SATA Control... | 34    | ahci       | FDC6203A6E |
| 8086:282a | 1043:1311 | Intel      | 82801 Mobile SATA Control... | 34    | ahci       | F3511CB0AA |
| 8086:282a | 1028:024f | Intel      | 82801 Mobile SATA Control... | 32    | ahci       | E475348B1E |
| 8086:282a | 1043:1961 | Intel      | 82801 Mobile SATA Control... | 32    | ahci       | 20A828B938 |
| 8086:282a | 1028:053c | Intel      | 82801 Mobile SATA Control... | 31    | ahci       | E6D67EBC2E |
| 8086:282a | 17aa:3810 | Intel      | 82801 Mobile SATA Control... | 31    | ahci       | 2BF6813AD9 |
| 8086:9a0b | 1028:0991 | Intel      | Volume Management Device ... | 31    | vmd        | 22BC284F45 |
| 8086:282a | 1028:024d | Intel      | 82801 Mobile SATA Control... | 30    | ahci       | C486155F48 |
| 8086:282a | 1028:0494 | Intel      | 82801 Mobile SATA Control... | 30    | ahci       | E292C83E5F |
| 8086:282a | 1028:0798 | Intel      | 82801 Mobile SATA Control... | 30    | ahci       | 1B93E3C1C9 |
| 8086:282a | 1028:081c | Intel      | 82801 Mobile SATA Control... | 28    | ahci       | 8462C89AD6 |
| 8086:282a | 1028:0533 | Intel      | 82801 Mobile SATA Control... | 27    | ahci       | 872CFFF7DA |
| 8086:282a | 103c:84a7 | Intel      | 82801 Mobile SATA Control... | 27    | ahci       | 20517EF47C |
| 8086:282a | 1025:1345 | Intel      | 82801 Mobile SATA Control... | 26    | intel_n... | 7463FACB20 |
| 8086:282a | 1025:128d | Intel      | 82801 Mobile SATA Control... | 25    | ahci       | 1F5C815672 |
| 8086:282a | 1028:086f | Intel      | 82801 Mobile SATA Control... | 25    | ahci       | 28D725057F |
| 8086:282a | 103c:86c8 | Intel      | 82801 Mobile SATA Control... | 25    | ahci       | 1260542A5E |
| 8086:282a | 1028:06de | Intel      | 82801 Mobile SATA Control... | 24    | ahci       | 17D97E59DE |
| 8086:282a | 1043:1fc0 | Intel      | 82801 Mobile SATA Control... | 23    | ahci       | 31B0B9087E |
| 8086:9a0b | 8086:7270 | Intel      | Volume Management Device ... | 23    | vmd        | 16268DB25B |
| 8086:282a | 1028:0410 | Intel      | 82801 Mobile SATA Control... | 22    | ahci       | 75A9AA20F2 |
| 8086:282a | 1028:04a3 | Intel      | 82801 Mobile SATA Control... | 22    | ahci       | 6E09C36301 |
| 8086:282a | 1028:0532 | Intel      | 82801 Mobile SATA Control... | 22    | ahci       | D040F874C9 |
| 8086:282a | 1028:05de | Intel      | 82801 Mobile SATA Control... | 22    | ahci       | 22977AA779 |
| 8086:282a | 1028:062d | Intel      | 82801 Mobile SATA Control... | 22    | ahci       | 9834990221 |
| 8086:282a | 1028:0492 | Intel      | 82801 Mobile SATA Control... | 21    | ahci       | DC31C90631 |
| 8086:282a | 1028:07a7 | Intel      | 82801 Mobile SATA Control... | 21    | ahci       | 3ED90A1781 |
| 8086:9a0b | 14c0:012d | Intel      | Volume Management Device ... | 21    | vmd        | 3D77CD95D3 |
| 8086:282a | 1028:053d | Intel      | 82801 Mobile SATA Control... | 20    | ahci       | A377D34C0D |
| 8086:282a | 1028:062b | Intel      | 82801 Mobile SATA Control... | 20    | ahci       | FB61A77E5C |
| 8086:282a | 103c:8533 | Intel      | 82801 Mobile SATA Control... | 20    | ahci       | B16AD0BCB8 |
| 8086:282a | 1025:1357 | Intel      | 82801 Mobile SATA Control... | 19    | intel_n... | F06A523887 |
| 8086:282a | 1028:0572 | Intel      | 82801 Mobile SATA Control... | 19    | ahci       | 9A64D0961F |
| 8086:282a | 1028:05e0 | Intel      | 82801 Mobile SATA Control... | 19    | ahci       | 44B8F3A781 |
| 8086:282a | 1028:062c | Intel      | 82801 Mobile SATA Control... | 19    | ahci       | 974759ECDB |
| 8086:282a | 103c:85ef | Intel      | 82801 Mobile SATA Control... | 19    | ahci       | CB73E3814C |
| 8086:9a0b | 103c:87e1 | Intel      | Volume Management Device ... | 19    | vmd        | A92566EE89 |
| 8086:282a | 1028:057e | Intel      | 82801 Mobile SATA Control... | 18    | ahci       | F31078AFD8 |
| 8086:282a | 1028:07a0 | Intel      | 82801 Mobile SATA Control... | 18    | ahci       | C639789B23 |
| 8086:282a | 1043:1501 | Intel      | 82801 Mobile SATA Control... | 18    | ahci       | 42BB3AA5DB |
| 8086:282a | 1028:05cc | Intel      | 82801 Mobile SATA Control... | 17    | ahci       | 2293B2D4C4 |
| 8086:282a | 1028:06db | Intel      | 82801 Mobile SATA Control... | 17    | ahci       | 94D1C284A1 |
| 8086:282a | 1025:1355 | Intel      | 82801 Mobile SATA Control... | 16    | ahci       | 9C4CA39872 |
| 8086:282a | 1028:06df | Intel      | 82801 Mobile SATA Control... | 16    | ahci       | C0E5D1FBDB |
| 8086:282a | 1028:0816 | Intel      | 82801 Mobile SATA Control... | 16    | ahci       | 4EFDBAEEA5 |
| 8086:282a | 1028:0825 | Intel      | 82801 Mobile SATA Control... | 16    | ahci       | 3E4B181CD8 |
| 8086:282a | 103c:18a5 | Intel      | 82801 Mobile SATA Control... | 16    | ahci       | A3DFB4CCF4 |
| 8086:2822 | 1028:06de | Intel      | SATA Controller [RAID mode]  | 15    | ahci       | 08D4C126FA |
| 8086:282a | 103c:18fd | Intel      | 82801 Mobile SATA Control... | 15    | ahci       | 10A67C9E23 |
| 8086:282a | 17aa:3802 | Intel      | 82801 Mobile SATA Control... | 15    | ahci       | D4EC4C5E60 |
| 8086:9a0b | 1025:1464 | Intel      | Volume Management Device ... | 15    | vmd        | D121231EEA |
| 8086:282a | 1025:1343 | Intel      | 82801 Mobile SATA Control... | 14    | intel_n... | 9768281E5C |
| 8086:282a | 1028:04a9 | Intel      | 82801 Mobile SATA Control... | 14    | ahci       | 84556DEE36 |
| 8086:282a | 103c:84da | Intel      | 82801 Mobile SATA Control... | 14    | ahci       | 5FBDC9F939 |
| 8086:282a | 103c:85fc | Intel      | 82801 Mobile SATA Control... | 14    | ahci       | F0C049FC34 |
| 8086:282a | 1043:1591 | Intel      | 82801 Mobile SATA Control... | 14    | ahci       | 05FB4B3BB3 |
| 8086:282a | 1028:053e | Intel      | 82801 Mobile SATA Control... | 13    | ahci       | 8516551E92 |
| 8086:282a | 103c:85e3 | Intel      | 82801 Mobile SATA Control... | 13    | ahci       | 407501F166 |
| 8086:282a | 104d:907b | Intel      | 82801 Mobile SATA Control... | 13    | ahci       | BE4DB20B0E |
| 8086:282a | 1028:04a4 | Intel      | 82801 Mobile SATA Control... | 12    | ahci       | 3C06AD8F67 |
| 8086:282a | 103c:868e | Intel      | 82801 Mobile SATA Control... | 12    | ahci       | E16A18BC8B |
| 8086:282a | 1043:1a81 | Intel      | 82801 Mobile SATA Control... | 12    | ahci       | 91055C07BE |
| 8086:9a0b | 103c:87cb | Intel      | Volume Management Device ... | 12    | vmd        | A56C0A6B4D |
| 8086:9a0b | 103c:881d | Intel      | Volume Management Device ... | 12    | vmd        | 6F87ECE998 |
| 1095:3531 | 17c0:4083 | Silicon... | SiI 3531 [SATALink/SATARa... | 11    | sata_sil24 | A1F9398A77 |
| 8086:282a | 1025:129a | Intel      | 82801 Mobile SATA Control... | 11    | ahci       | 312FB76F1D |
| 8086:282a | 1028:040c | Intel      | 82801 Mobile SATA Control... | 11    | ahci       | D7B650FECF |
| 8086:282a | 1028:05aa | Intel      | 82801 Mobile SATA Control... | 11    | ahci       | 1A6F72A2FD |
| 8086:282a | 1028:05cd | Intel      | 82801 Mobile SATA Control... | 11    | ahci       | 24E7A40A7A |
| 8086:282a | 1028:0704 | Intel      | 82801 Mobile SATA Control... | 11    | ahci       | 1F26867986 |
| 8086:282a | 1028:07be | Intel      | 82801 Mobile SATA Control... | 11    | ahci       | 4D6E9C85C6 |
| 8086:282a | 103c:1894 | Intel      | 82801 Mobile SATA Control... | 11    | ahci       | E8F88BD1B2 |
| 8086:282a | 103c:8574 | Intel      | 82801 Mobile SATA Control... | 11    | ahci       | 7D94C98AA7 |
| 8086:282a | 1043:14e2 | Intel      | 82801 Mobile SATA Control... | 11    | ahci       | 905EF359D4 |
| 8086:9a0b | 1028:0a5c | Intel      | Volume Management Device ... | 11    | vmd        | D13426531E |
| 8086:282a | 1028:0277 | Intel      | 82801 Mobile SATA Control... | 10    | ahci       | DB5BAD5ADE |
| 8086:282a | 1028:0490 | Intel      | 82801 Mobile SATA Control... | 10    | ahci       | DEFE1F021F |
| 8086:282a | 1028:082c | Intel      | 82801 Mobile SATA Control... | 10    | ahci       | 40360BB1E3 |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 9004:8078 | 9004:7880 | Adaptec    | AIC-7880U                    | 1     | aic7xxx    | F379321C88 |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:16be | 1025:0647 | Broadcom   | BCM57765/57785 MS Card Re... | 410   |            | 82E60126C9 |
| 14e4:16bf | 1025:0647 | Broadcom   | BCM57765/57785 xD-Picture... | 410   |            | 82E60126C9 |
| 8086:1513 | 2222:1111 | Intel      | CV82524 Thunderbolt Contr... | 296   | thunder... | 6E17FB6EA4 |
| 1180:e822 | 17aa:2133 | Ricoh      | MMC/SD Host Controller       | 276   | sdhci_pci  | 8B21B7CFFE |
| 197b:2382 | 1043:1a07 | JMicron... | SD/MMC Host Controller       | 235   | sdhci_pci  | D5A8ADB8C9 |
| 14e4:16be | 1025:0504 | Broadcom   | BCM57765/57785 MS Card Re... | 213   |            | F86CA58100 |
| 14e4:16bf | 1025:0504 | Broadcom   | BCM57765/57785 xD-Picture... | 213   |            | F86CA58100 |
| 197b:2383 | 1043:1a07 | JMicron... | MS Host Controller           | 204   | jmb38x_ms  | D5A8ADB8C9 |
| 8086:156a |           | Intel      | DSL5320 Thunderbolt 2 NHI... | 204   | thunder... | 5BE083EDAB |
| 197b:2384 | 1043:1a07 | JMicron... | xD Host Controller           | 202   |            | D5A8ADB8C9 |
| 1180:e230 | 17aa:2134 | Ricoh      | R5U2xx (R5U230 / R5U231 /... | 195   |            | 8B21B7CFFE |
| 1180:0592 | 17aa:20ca | Ricoh      | R5C592 Memory Stick Bus H... | 190   | r592       | 9A7BE426F5 |
| 1180:0852 | 17aa:20cb | Ricoh      | xD-Picture Card Controller   | 190   | r852       | 9A7BE426F5 |
| 8086:15bf | 2222:1111 | Intel      | JHL6240 Thunderbolt 3 NHI... | 183   | thunder... | FEB7F2A285 |
| 8086:1911 | 1025:1331 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 157   |            | BC9DC107D1 |
| 8086:d150 |           | Intel      | Core Processor QPI Link      | 152   |            | A68000E142 |
| 8086:d151 |           | Intel      | Core Processor QPI Routin... | 152   |            | A68000E142 |
| 8086:8a17 |           | Intel      | Ice Lake Thunderbolt 3 NH... | 151   | thunder... | B416F8B251 |
| 8086:3190 | 1043:1de0 | Intel      | Celeron/Pentium Silver Pr... | 146   |            | 5C95C74B6C |
| 8086:1911 | 1028:0905 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 142   |            | 58E43F0514 |
| 8086:15d9 | 1028:0905 | Intel      | JHL6340 Thunderbolt 3 NHI... | 140   | thunder... | 58E43F0514 |
| 1180:e230 | 104d:9071 | Ricoh      | R5U2xx (R5U230 / R5U231 /... | 138   |            | A18FB33A6F |
| 8086:1911 | 17aa:5079 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 138   |            | A35AAAEB6D |
| 1180:e823 | 17aa:21f3 | Ricoh      | PCIe SDXC/MMC Host Contro... | 130   | sdhci_pci  | C9D8EFC9B9 |
| 8086:1911 | 17aa:2279 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 127   |            | A01E524A66 |
| 8086:15bf | 17aa:2279 | Intel      | JHL6240 Thunderbolt 3 NHI... | 120   | thunder... | A01E524A66 |
| 8086:d155 |           | Intel      | Core Processor System Man... | 120   |            | A68000E142 |
| 8086:d156 |           | Intel      | Core Processor Semaphore ... | 120   |            | A68000E142 |
| 8086:d157 |           | Intel      | Core Processor System Con... | 120   |            | A68000E142 |
| 8086:d158 |           | Intel      | Core Processor Miscellane... | 120   |            | A68000E142 |
| 1180:e823 | 17aa:21ce | Ricoh      | PCIe SDXC/MMC Host Contro... | 116   | sdhci_pci  | A75FFD5203 |
| 197b:2392 | 103c:161c | JMicron... | SD/MMC Host Controller       | 116   | sdhci_pci  | B6AC4539D1 |
| 8086:09ab |           | Intel      | System peripheral            | 116   |            | E58D33DF6B |
| 8086:1911 | 1028:087c | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 114   |            | 0FA8C3ED0C |
| 8086:1911 | 17aa:225d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 109   |            | FEB7F2A285 |
| 8086:15e8 | 103c:8549 | Intel      | JHL7540 Thunderbolt 3 NHI... | 108   | thunder... | A814284F0B |
| 8086:1911 | 17aa:2292 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 108   |            | 080C5280D0 |
| 1180:e823 | 17aa:21fa | Ricoh      | PCIe SDXC/MMC Host Contro... | 106   | sdhci_pci  | A120083D3C |
| 197b:2392 | 103c:179b | JMicron... | SD/MMC Host Controller       | 106   | sdhci_pci  | 1B2FBCDFA0 |
| 1180:e823 | 17aa:21da | Ricoh      | PCIe SDXC/MMC Host Contro... | 101   | sdhci_pci  | 0A8E84DFAD |
| 197b:2392 | 103c:17f6 | JMicron... | SD/MMC Host Controller       | 97    | sdhci_pci  | E12D7E47E6 |
| 197b:2393 | 103c:17f6 | JMicron... | MS Host Controller           | 97    | jmb38x_ms  | E12D7E47E6 |
| 8086:15d2 | 17aa:2292 | Intel      | JHL6540 Thunderbolt 3 NHI... | 96    | thunder... | 080C5280D0 |
| 1180:e822 | 17aa:21f3 | Ricoh      | MMC/SD Host Controller       | 94    | sdhci_pci  | 11AB5D413D |
| 8086:1911 | 1028:08af | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 92    |            | 52DEA66C52 |
| 8086:156c |           | Intel      | DSL5520 Thunderbolt 2 NHI... | 91    | thunder... | F69B01435F |
| 8086:15d2 | 1028:0962 | Intel      | JHL6540 Thunderbolt 3 NHI... | 91    | thunder... | 8956FEE2F3 |
| 8086:1911 | 1028:0962 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 91    |            | 8956FEE2F3 |
| 1180:e823 | 17aa:21f6 | Ricoh      | PCIe SDXC/MMC Host Contro... | 89    | sdhci_pci  | 69A252CCD6 |
| 8086:1911 | 17aa:5072 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 89    |            | 3678E02E46 |
| 8086:15d2 | 1028:08af | Intel      | JHL6540 Thunderbolt 3 NHI... | 87    | thunder... | 52DEA66C52 |
| 8086:1911 | 1025:1264 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 86    |            | 7F70DE1771 |
| 8086:1911 | 17aa:225c | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 86    |            | 2B4A1A20D9 |
| 8086:1911 | 17aa:5068 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 86    |            | 2A70ED5588 |
| 8086:15eb | 1028:097d | Intel      | JHL7540 Thunderbolt 3 NHI... | 84    | thunder... | 994B96D25D |
| 8086:1911 | 1028:097d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 84    |            | 994B96D25D |
| 1180:0592 | 1028:022f | Ricoh      | R5C592 Memory Stick Bus H... | 83    | r592       | ED2467DC52 |
| 1180:0852 | 1028:022f | Ricoh      | xD-Picture Card Controller   | 83    | r852       | ED2467DC52 |
| 8086:1911 | 8086:2015 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 82    |            | F3E5EBA0C2 |
| 8086:156c | 2222:1111 | Intel      | DSL5520 Thunderbolt 2 NHI... | 81    | thunder... | 0C24CAF245 |
| 8086:1911 | 103c:832a | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 80    |            | C9FD6887D4 |
| 1180:e822 | 17aa:21fa | Ricoh      | MMC/SD Host Controller       | 77    | sdhci_pci  | EC8AF5F350 |
| 8086:1911 | 17aa:3861 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 76    |            | 2DB4EBB6EF |
| 197b:2392 | 103c:167c | JMicron... | SD/MMC Host Controller       | 75    | sdhci_pci  | 4808FF3A68 |
| 197b:2393 | 103c:167c | JMicron... | MS Host Controller           | 75    | jmb38x_ms  | 4808FF3A68 |
| 8086:1911 | 17aa:2233 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 75    |            | 9EF824D802 |
| 1180:e823 | 17aa:21cf | Ricoh      | PCIe SDXC/MMC Host Contro... | 74    | sdhci_pci  | 4104E265EA |
| 1180:0592 | 103c:30cc | Ricoh      | R5C592 Memory Stick Bus H... | 73    | r592       | DD3C7EF3E7 |
| 1180:0852 | 103c:30cc | Ricoh      | xD-Picture Card Controller   | 73    | r852       | DD3C7EF3E7 |
| 8086:1911 | 17aa:3866 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 73    |            | EAF7694813 |
| 8086:1911 | 17aa:2258 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 70    |            | EEB181F50B |
| 8086:1911 | 103c:84a6 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 68    |            | F0A8FA5E7A |
| 1180:e823 | 1179:0001 | Ricoh      | PCIe SDXC/MMC Host Contro... | 66    | sdhci_pci  | 6378D53C40 |
| 8086:1911 | 1028:0949 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 65    |            | 3165D77A8E |
| 8086:1911 | 17aa:3864 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 63    |            | 75C71D1F1E |
| 8086:1911 | 17aa:384e | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 60    |            | 2AD271E81F |
| 8086:1911 | 8086:7270 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 60    |            | C3F94D8599 |
| 1180:e822 | 17aa:21f6 | Ricoh      | MMC/SD Host Controller       | 59    | sdhci_pci  | EC3329E68A |
| 8086:1911 | 1028:086f | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 59    |            | 28D725057F |
| 8086:1911 | 1028:08ca | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 59    |            | 8F25043C64 |
| 8086:8a0d |           | Intel      | Ice Lake Thunderbolt 3 NH... | 59    | thunder... | 7B3CDDA6E2 |
| 8086:15d2 | 2222:1111 | Intel      | JHL6540 Thunderbolt 3 NHI... | 58    | thunder... | 2B4A1A20D9 |
| 8086:15d9 | 8086:0000 | Intel      | JHL6340 Thunderbolt 3 NHI... | 58    | thunder... | D0C34DB7D4 |
| 8086:1911 | 103c:8478 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 56    |            | 362E1D3B99 |
| 8086:1911 | 8086:1911 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 56    |            | 20123F6B2F |
| 8086:1911 | 17aa:225a | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 55    |            | 4C8C63DA2F |
| 8086:15eb | 17aa:229f | Intel      | JHL7540 Thunderbolt 3 NHI... | 54    | thunder... | 3517455DF5 |
| 8086:15bf | 17aa:22b0 | Intel      | JHL6240 Thunderbolt 3 NHI... | 53    | thunder... | F7309EF31A |
| 8086:1911 | 1025:1333 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 53    |            | 271C2188CB |
| 197b:2392 | 103c:162b | JMicron... | SD/MMC Host Controller       | 50    | sdhci_pci  | 28D13C49B3 |
| 8086:1911 | 1028:0906 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 50    |            | E549029931 |
| 8086:1911 | 103c:832b | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 50    |            | A12360B5DC |
| 8086:1911 | 17aa:2267 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 50    |            | 3A76CBDC51 |
| 197b:2382 | 103c:3628 | JMicron... | SD/MMC Host Controller       | 49    | sdhci_pci  | 2992DD1DF0 |
| 197b:2383 | 103c:3628 | JMicron... | MS Host Controller           | 49    | jmb38x_ms  | 2992DD1DF0 |
| 197b:2384 | 103c:3628 | JMicron... | xD Host Controller           | 49    |            | 2992DD1DF0 |
| 8086:1911 | 17aa:2286 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 49    |            | D3700D8667 |
| 1180:e822 | 17aa:21da | Ricoh      | MMC/SD Host Controller       | 48    | sdhci_pci  | 402DDBAA44 |
| 197b:2382 | 1297:2027 | JMicron... | SD/MMC Host Controller       | 48    | sdhci_pci  | 9F3A43BC94 |
| 197b:2383 | 1297:2027 | JMicron... | MS Host Controller           | 48    | jmb38x_ms  | 9F3A43BC94 |

### Tv card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1131:7133 | 1461:a836 | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 14C016A2F9 |
| 1131:7133 | 1461:e836 | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 6D72715029 |
| 1131:7133 | 1461:f636 | Philips... | SAA7131/SAA7133/SAA7135 V... | 3     | saa7134    | 262909CB28 |
| 14f1:5b7a | 1179:0110 | Conexan... | CX23418 Single-Chip MPEG-... | 3     | cx18       | 0BAD664989 |
| 1131:7133 | 5168:0307 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | A942E40F27 |
| 14f1:5b7a | 1179:0030 | Conexan... | CX23418 Single-Chip MPEG-... | 2     | cx18       | 35691B5DA9 |
| 14f1:8852 | 1461:d939 | Conexan... | CX23885 PCI Video and Aud... | 2     | cx23885    | 8E5499B7A2 |
| 1131:7133 | 0000:5201 | Philips... | SAA7131/SAA7133/SAA7135 V... | 1     | saa7134    | C5FECF0E37 |
| 1131:7133 | 1461:4836 | Philips... | SAA7131/SAA7133/SAA7135 V... | 1     | saa7134    | 23445C1CBB |
| 1131:7133 | 16be:0009 | Philips... | SAA7131/SAA7133/SAA7135 V... | 1     | saa7134    | EFDFFC9FB6 |
| 1131:7133 | 5168:4307 | Philips... | SAA7131/SAA7133/SAA7135 V... | 1     | saa7134    | 771A897694 |
| 14f1:5b7a | 1179:0031 | Conexan... | CX23418 Single-Chip MPEG-... | 1     | cx18       | AE0DBDDFF1 |
| 4444:0016 | 1179:0001 | Interne... | iTVC16 (CX23416) Video De... | 1     | ivtv       | D5D7DAB02F |
| 4444:0016 | 1461:c136 | Interne... | iTVC16 (CX23416) Video De... | 1     | ivtv       | A85F0700D9 |

### Unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:5aa2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_i... | 403E735C43 |
| 8086:31a2 | 17aa:3806 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_i... | EDA2FBC232 |
| 8086:5aa2 | 103c:82ee | Intel      | Celeron N3350/Pentium N42... | 2     | intel_i... | 90AEEA53CC |
| 1217:6120 | 0001:0000 | O2 Micro   |                              | 1     |            | B851103D78 |
| 8086:31a2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_i... | 8FBDEDC1B9 |
| 8086:5aa2 | 1028:07b3 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | 0BF27D0F8E |
| 8086:5aa2 | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | 7EC45DB0DE |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d2f | 1043:201f | Intel      | Sunrise Point-LP USB 3.0 ... | 878   | xhci_hcd   | 02BA908575 |
| 8086:1e26 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 574   | ehci_pci   | 16EBDC4388 |
| 8086:1e2d | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 574   | ehci_pci   | 16EBDC4388 |
| 8086:1e31 | 17aa:3977 | Intel      | 7 Series/C210 Series Chip... | 562   | xhci_hcd   | 16EBDC4388 |
| 8086:22b5 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 435   | xhci_hcd   | 2FBF6F153B |
| 8086:9a1b | 2222:1111 | Intel      | Tiger Lake-LP Thunderbolt... | 357   | thunder... | DA5E2F59CC |
| 8086:3b34 | 17aa:2163 | Intel      | 5 Series/3400 Series Chip... | 339   | ehci_pci   | 570863FD8C |
| 8086:3b3c | 17aa:2163 | Intel      | 5 Series/3400 Series Chip... | 339   | ehci_pci   | 570863FD8C |
| 8086:2934 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 336   | uhci_hcd   | 9A7BE426F5 |
| 8086:2935 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 336   | uhci_hcd   | 9A7BE426F5 |
| 8086:2936 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 336   | uhci_hcd   | 9A7BE426F5 |
| 8086:2937 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 336   | uhci_hcd   | 9A7BE426F5 |
| 8086:2938 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 336   | uhci_hcd   | 9A7BE426F5 |
| 8086:2939 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 336   | uhci_hcd   | 9A7BE426F5 |
| 8086:293a | 17aa:20f1 | Intel      | 82801I (ICH9 Family) USB2... | 336   | ehci_pci   | 9A7BE426F5 |
| 8086:293c | 17aa:20f1 | Intel      | 82801I (ICH9 Family) USB2... | 336   | ehci_pci   | 9A7BE426F5 |
| 1b21:1042 | 1043:1059 | ASMedia... | ASM1042 SuperSpeed USB Ho... | 324   | xhci_hcd   | 011079F499 |
| 8086:1c26 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 320   | ehci_hc... | D1D57448C4 |
| 8086:1c2d | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 320   | ehci_hc... | D1D57448C4 |
| 8086:9c31 | 17aa:3978 | Intel      | 8 Series USB xHCI HC         | 311   | xhci_hcd   | 3CDDE1061C |
| 8086:9cb1 | 8086:7270 | Intel      | Wildcat Point-LP USB xHCI... | 295   | xhci_pci   | 5BE083EDAB |
| 8086:9c26 | 17aa:3978 | Intel      | 8 Series USB EHCI #1         | 289   | ehci_pci   | 3CDDE1061C |
| 8086:27c8 | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 280   | uhci_hcd   | E74DC83F0A |
| 8086:27c9 | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 280   | uhci_hcd   | E74DC83F0A |
| 8086:27ca | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 280   | uhci_hcd   | E74DC83F0A |
| 8086:27cc | 1043:83ad | Intel      | NM10/ICH7 Family USB2 EHC... | 280   | ehci_hc... | E74DC83F0A |
| 8086:9a13 |           | Intel      | Tiger Lake-LP Thunderbolt... | 280   | xhci_pci   | DA5E2F59CC |
| 1022:15e0 | 1043:201f | AMD        | Raven USB 3.1                | 278   | xhci_hcd   | 21379AAD70 |
| 1022:15e1 | 1043:201f | AMD        | Raven USB 3.1                | 278   | xhci_hcd   | 21379AAD70 |
| 8086:a12f | 1043:201f | Intel      | 100 Series/C230 Series Ch... | 277   | xhci_hcd   | 5D4BCE82BD |
| 8086:9ded | 1043:201f | Intel      | Cannon Point-LP USB 3.1 x... | 276   | xhci_hcd   | 67F0B45A7A |
| 8086:9c31 | 1043:201f | Intel      | 8 Series USB xHCI HC         | 272   | xhci_hcd   | AA747D41F1 |
| 8086:27cb | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 259   | uhci_hcd   | E74DC83F0A |
| 8086:31a8 | 1043:201f | Intel      | Celeron/Pentium Silver Pr... | 255   | xhci_hcd   | 4FE54B07A9 |
| 1022:1639 | 1043:201f | AMD        | Renoir/Cezanne USB 3.1       | 238   | xhci_pci   | 3F7A2585FE |
| 8086:9cb1 | 1043:201f | Intel      | Wildcat Point-LP USB xHCI... | 228   | xhci_hcd   | C947E5B1EA |
| 8086:8c26 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 227   | ehci_pci   | 60FA5FF04C |
| 8086:8c2d | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 227   | ehci_pci   | 60FA5FF04C |
| 8086:8c31 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 227   | xhci_hcd   | 60FA5FF04C |
| 8086:a36d | 1043:201f | Intel      | Cannon Lake PCH USB 3.1 x... | 219   | xhci_hcd   | 085EF9E58D |
| 8086:1c26 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 217   | ehci_pci   | ECC4515014 |
| 8086:1c2d | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 217   | ehci_pci   | ECC4515014 |
| 8086:5aa8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 211   | xhci_hcd   | 403E735C43 |
| 8086:9c26 | 1043:201f | Intel      | 8 Series USB EHCI #1         | 208   | ehci_pci   | B2CDA34B7E |
| 8086:15c1 | 2222:1111 | Intel      | JHL6240 Thunderbolt 3 USB... | 206   | xhci_hcd   | FEB7F2A285 |
| 8086:1e26 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 204   | ehci_pci   | 783D081B5A |
| 8086:1e2d | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 204   | ehci_pci   | 783D081B5A |
| 8086:1c27 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 201   | uhci_hcd   | ECC4515014 |
| 8086:1c2c | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 201   | uhci_hcd   | ECC4515014 |
| 8086:1e31 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 195   | xhci_hcd   | 783D081B5A |
| 8086:a0ed |           | Intel      | Tiger Lake-LP USB 3.2 Gen... | 195   | xhci_pci   | DA5E2F59CC |
| 8086:1e26 | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 194   | ehci_pci   | C9D8EFC9B9 |
| 8086:1e2d | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 194   | ehci_pci   | C9D8EFC9B9 |
| 8086:1e31 | 17aa:21f3 | Intel      | 7 Series/C210 Series Chip... | 192   | xhci_hcd   | C9D8EFC9B9 |
| 8086:3b34 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 188   | ehci_pci   | E3FC4E0622 |
| 8086:3b3c | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 188   | ehci_pci   | E3FC4E0622 |
| 8086:1c26 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 173   | ehci_pci   | A75FFD5203 |
| 8086:1c2d | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 173   | ehci_pci   | A75FFD5203 |
| 10de:0aa5 | 10de:cb79 | Nvidia     | MCP79 OHCI USB 1.1 Contro... | 171   | ohci_pci   | 25B2F96576 |
| 10de:0aa6 | 10de:cb79 | Nvidia     | MCP79 EHCI USB 2.0 Contro... | 171   | ehci_pci   | 25B2F96576 |
| 10de:0aa7 | 10de:cb79 | Nvidia     | MCP79 OHCI USB 1.1 Contro... | 171   | ohci_pci   | 25B2F96576 |
| 10de:0aa9 | 10de:cb79 | Nvidia     | MCP79 EHCI USB 2.0 Contro... | 171   | ehci_pci   | 25B2F96576 |
| 8086:1e26 | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 167   | ehci_pci   | EC8AF5F350 |
| 8086:1e2d | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 167   | ehci_pci   | EC8AF5F350 |
| 8086:1e31 | 17aa:21fa | Intel      | 7 Series/C210 Series Chip... | 167   | xhci_hcd   | EC8AF5F350 |
| 8086:1c26 | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 165   | ehci_pci   | B96D5D5FDC |
| 8086:1c2d | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 165   | ehci_pci   | B96D5D5FDC |
| 8086:1e26 | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 165   | ehci_hc... | 82E60126C9 |
| 8086:1e2d | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 165   | ehci_hc... | 82E60126C9 |
| 8086:2934 | 17aa:3a14 | Intel      | 82801I (ICH9 Family) USB ... | 163   | uhci_hcd   | B9412E1AB2 |
| 8086:2935 | 17aa:3a15 | Intel      | 82801I (ICH9 Family) USB ... | 163   | uhci_hcd   | B9412E1AB2 |
| 8086:2936 | 17aa:3a16 | Intel      | 82801I (ICH9 Family) USB ... | 163   | uhci_hcd   | B9412E1AB2 |
| 8086:293a | 17aa:3a17 | Intel      | 82801I (ICH9 Family) USB2... | 163   | ehci_hc... | B9412E1AB2 |
| 8086:293c | 17aa:3a0c | Intel      | 82801I (ICH9 Family) USB2... | 163   | ehci_hc... | B9412E1AB2 |
| 8086:1c26 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 160   | ehci_pci   | 4C3C43DAAA |
| 8086:1c2d | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 160   | ehci_pci   | 4C3C43DAAA |
| 8086:1c26 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 158   | ehci_pci   | B66EB36016 |
| 8086:1c2d | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 158   | ehci_pci   | B66EB36016 |
| 8086:2830 | 17aa:20aa | Intel      | 82801H (ICH8 Family) USB ... | 157   | uhci_hcd   | 87E69E1105 |
| 8086:2831 | 17aa:20aa | Intel      | 82801H (ICH8 Family) USB ... | 157   | uhci_hcd   | 87E69E1105 |
| 8086:2834 | 17aa:20aa | Intel      | 82801H (ICH8 Family) USB ... | 157   | uhci_hcd   | 87E69E1105 |
| 8086:2835 | 17aa:20aa | Intel      | 82801H (ICH8 Family) USB ... | 157   | uhci_hcd   | 87E69E1105 |
| 8086:2836 | 17aa:20ab | Intel      | 82801H (ICH8 Family) USB2... | 157   | ehci_pci   | 87E69E1105 |
| 8086:283a | 17aa:20ab | Intel      | 82801H (ICH8 Family) USB2... | 157   | ehci_pci   | 87E69E1105 |
| 8086:2937 | 17aa:3a09 | Intel      | 82801I (ICH9 Family) USB ... | 157   | uhci_hcd   | B9412E1AB2 |
| 8086:a36d | 1025:1331 | Intel      | Cannon Lake PCH USB 3.1 x... | 157   | xhci_hcd   | BC9DC107D1 |
| 8086:2938 | 17aa:3a0a | Intel      | 82801I (ICH9 Family) USB ... | 152   | uhci_hcd   | B9412E1AB2 |
| 8086:2939 | 17aa:3a0b | Intel      | 82801I (ICH9 Family) USB ... | 150   | uhci_hcd   | B9412E1AB2 |
| 8086:3b34 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 150   | ehci_pci   | BA51FC9216 |
| 8086:3b3c | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 150   | ehci_pci   | BA51FC9216 |
| 8086:31a8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 149   | xhci_hcd   | F40D5FD5A7 |
| 8086:3b34 | 17aa:38b8 | Intel      | 5 Series/3400 Series Chip... | 148   | ehci_hc... | 80B7F3E584 |
| 8086:3b3c | 17aa:38aa | Intel      | 5 Series/3400 Series Chip... | 148   | ehci_hc... | 80B7F3E584 |
| 8086:9d2f | 17aa:3870 | Intel      | Sunrise Point-LP USB 3.0 ... | 147   | xhci_hcd   | F86520F5A7 |
| 1912:0015 |           | Renesas... | uPD720202 USB 3.0 Host Co... | 146   | xhci_pci   | 273A5FF27D |
| 1022:7808 | 17aa:3801 | AMD        | FCH USB EHCI Controller      | 143   | ehci_pci   | 0CDC6E9D84 |
| 1022:7814 | 17aa:3801 | AMD        | FCH USB XHCI Controller      | 143   | xhci_pci   | 0CDC6E9D84 |
| 8086:1e26 | 1028:0534 | Intel      | 7 Series/C216 Chipset Fam... | 142   | ehci_pci   | FA4D12994D |
| 8086:1e2d | 1028:0534 | Intel      | 7 Series/C216 Chipset Fam... | 142   | ehci_pci   | FA4D12994D |
| 8086:1e31 | 1028:0534 | Intel      | 7 Series/C210 Series Chip... | 142   | xhci_hcd   | FA4D12994D |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1eac:1001 | 1eac:2001 |            |                              | 9     | mhi_pci... | 11CD74E647 |
| 1002:6900 | 03ea:1af4 | AMD        | Topaz XT [Radeon R7 M260/... | 6     | amdgpu     | B48E22AF4A |
| 1971:0000 | 105b:0003 | AGEIA T... | AGEIA PhysX 100 PCIe Card    | 3     |            | 5C4A880D42 |
| 106b:003b |           | Apple      | UniNorth/Intrepid ATA/100    | 2     | pata_pc... | 7740C04B4B |
| 106b:003e |           | Apple      | KeyLargo/Intrepid Mac I/O    | 2     | macio      | 7740C04B4B |
| 10de:0e1b | 0043:0000 | Nvidia     | GK107 HDMI Audio Controller  | 2     | snd_hda... | 17B6106770 |
| 10de:1f91 | 103c:8601 | Nvidia     | TU117M [GeForce GTX 1650 ... | 2     | nouveau    | 332EEAE951 |
| 10ec:5228 | 103c:88b5 | Realtek... |                              | 2     | rtsx_pci   | 12EBE0B845 |
| 10ec:5261 | 1462:12fb | Realtek... | PCIe Card Reader             | 2     | rtsx_pci   | CBF3C67BE2 |
| 10ec:5261 | 1462:1305 | Realtek... | PCIe Card Reader             | 2     | rtsx_pci   | D9BC3D0B56 |
| 1002:694e | 1002:694e | AMD        | Polaris 22 XL [Radeon RX ... | 1     | amdgpu     | F5FDC69851 |
| 106b:0022 |           | Apple      | KeyLargo Mac I/O             | 1     | macio      | 48A9C9544A |
| 10de:0bea | 1028:1534 | Nvidia     | GF108 High Definition Aud... | 1     | snd_hda... | 9401066945 |
| 10de:0bea | 1043:105c | Nvidia     | GF108 High Definition Aud... | 1     | snd_hda... | 2512ED1F69 |
| 10de:0e1b | 17aa:221e | Nvidia     | GK107 HDMI Audio Controller  | 1     | snd_hda... | 4C925D546F |
| 10de:1c8c | 17aa:39d1 | Nvidia     | GP107M [GeForce GTX 1050 ... | 1     | nouveau    | 2DA8281FA9 |
| 10de:1fb9 | 10de:0000 | Nvidia     | TU117GLM [Quadro T1000 Mo... | 1     | nvidia     | B53EA50909 |
| 10ec:5261 | 103c:8873 | Realtek... | PCIe Card Reader             | 1     | rtsx_pci   | E59D9DCF16 |
| 1180:8592 | 1043:9627 | Ricoh      |                              | 1     |            | C215EA9980 |
| 1180:8822 | 1043:9627 | Ricoh      |                              | 1     |            | C215EA9980 |
| 17fe:a220 | 1468:0305 | InProComm  |                              | 1     |            | 80E120B3A5 |
| 17fe:a220 | 1468:8305 | InProComm  |                              | 1     |            | 80E120B3A5 |
| 197b:2381 | 197b:2381 | JMicron... | Standard SD Host Controller  | 1     |            | 720AE73C63 |
| 197b:2382 | 197b:2382 | JMicron... | SD/MMC Host Controller       | 1     | sdhci-pci  | 720AE73C63 |
| 197b:2383 | 197b:2383 | JMicron... | MS Host Controller           | 1     | jmb38x_ms  | 720AE73C63 |
| 1aea:6625 | 103c:83aa | Alcor M... | AU6625 PCI-E Flash card r... | 1     |            | 62C7769C30 |
| 1eac:1001 | 1eac:2003 |            |                              | 1     | mhi_pci... | 734B8A2CFA |
| 494f:0100 | 494f:0100 | ACCES I... |                              | 1     |            | B364724E53 |
| 8086:9d2f | 14c0:0062 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 87AC0729E6 |

