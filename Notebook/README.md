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
| 1814:3298 | 103c:18ec | Ralink     | RT3290 Bluetooth             | 479   | rtbth      | BDAEE2E27B |
| 1814:3298 | 105b:e056 | Ralink     | RT3290 Bluetooth             | 104   | rtbth      | 1416BA31A9 |
| 1814:3298 | 103c:191c | Ralink     | RT3290 Bluetooth             | 22    | rtbth      | 43B7FFE89B |
| 1814:3298 | 1a3b:2f87 | Ralink     | RT3290 Bluetooth             | 12    |            | E60E072319 |
| 1814:3298 | 1a3b:2787 | Ralink     | RT3290 Bluetooth             | 9     |            | A583282400 |
| 1814:3298 | 1814:3298 | Ralink     | RT3290 Bluetooth             | 4     |            | AAC37423E5 |
| 1814:3298 | 10cf:1772 | Ralink     | RT3290 Bluetooth             | 1     |            | 1135E21142 |
| 1814:3298 | 1a3b:210b | Ralink     | RT3290 Bluetooth             | 1     |            | 2333E930AF |
| 1814:3298 | 1a3b:2987 | Ralink     | RT3290 Bluetooth             | 1     |            | EC90AB9922 |

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:4384 |           | AMD        | SBx00 PCI to PCI Bridge      | 1723  | shpchp     | 2CEB6921C6 |
| 1022:1452 |           | AMD        | Family 17h (Models 00h-1f... | 1629  |            | F504E72617 |
| 1022:15e8 |           | AMD        | Raven/Raven2 Device 24: F... | 1610  |            | F504E72617 |
| 1022:15e9 |           | AMD        | Raven/Raven2 Device 24: F... | 1610  |            | F504E72617 |
| 1022:15ea |           | AMD        | Raven/Raven2 Device 24: F... | 1610  |            | F504E72617 |
| 1022:15eb |           | AMD        | Raven/Raven2 Device 24: F... | 1610  | k10temp    | F504E72617 |
| 1022:15ec |           | AMD        | Raven/Raven2 Device 24: F... | 1610  |            | F504E72617 |
| 1022:15ed |           | AMD        | Raven/Raven2 Device 24: F... | 1610  |            | F504E72617 |
| 1022:15ee |           | AMD        | Raven/Raven2 Device 24: F... | 1610  |            | F504E72617 |
| 1022:15ef |           | AMD        | Raven/Raven2 Device 24: F... | 1610  |            | F504E72617 |
| 8086:2c62 | 8086:8086 | Intel      | Core Processor QuickPath ... | 1556  |            | 9635709179 |
| 8086:2d01 | 8086:8086 | Intel      | Core Processor QuickPath ... | 1556  |            | 9635709179 |
| 8086:2d10 | 8086:8086 | Intel      | Core Processor QPI Link 0    | 1556  |            | 9635709179 |
| 8086:2d11 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 1556  |            | 9635709179 |
| 8086:2d12 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 1556  |            | 9635709179 |
| 8086:2d13 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 1556  |            | 9635709179 |
| 1022:780f |           | AMD        | FCH PCI Bridge               | 1413  | shpchp     | E2CABCDB94 |
| 1022:15db | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 1356  | pcieport   | F504E72617 |
| 1022:1700 |           | AMD        | Family 12h/14h Processor ... | 1326  |            | E2CABCDB94 |
| 1022:1701 |           | AMD        | Family 12h/14h Processor ... | 1326  |            | E2CABCDB94 |
| 1022:1702 |           | AMD        | Family 12h/14h Processor ... | 1326  |            | E2CABCDB94 |
| 1022:1703 |           | AMD        | Family 12h/14h Processor ... | 1326  | k10temp    | E2CABCDB94 |
| 1022:1704 |           | AMD        | Family 12h/14h Processor ... | 1326  |            | E2CABCDB94 |
| 1022:1716 |           | AMD        | Family 12h/14h Processor ... | 1326  |            | E2CABCDB94 |
| 1022:1718 |           | AMD        | Family 12h/14h Processor ... | 1326  |            | E2CABCDB94 |
| 1022:1719 |           | AMD        | Family 12h/14h Processor ... | 1326  |            | E2CABCDB94 |
| 1022:157b |           | AMD        | Family 15h (Models 60h-6f... | 1035  |            | FC5CE69792 |
| 1022:157d |           | AMD        | Carrizo Audio Dummy Host ... | 1035  |            | FC5CE69792 |
| 1022:15dc | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 999   | pcieport   | F504E72617 |
| 1022:15d3 | 1022:1453 | AMD        | Raven/Raven2 PCIe GPP Bri... | 953   | pcieport   | F504E72617 |
| 8086:2448 |           | Intel      | 82801 Mobile PCI Bridge      | 898   | shpchp     | 65FBD3DEF4 |
| 1022:1632 |           | AMD        | Renoir PCIe Dummy Host Br... | 808   |            | 6B6205BC5D |
| 1022:1448 |           | AMD        | Renoir Device 24: Function 0 | 790   |            | 6B6205BC5D |
| 1022:1449 |           | AMD        | Renoir Device 24: Function 1 | 790   |            | 6B6205BC5D |
| 1022:144a |           | AMD        | Renoir Device 24: Function 2 | 790   |            | 6B6205BC5D |
| 1022:144b |           | AMD        | Renoir Device 24: Function 3 | 790   | k10temp    | 6B6205BC5D |
| 1022:144c |           | AMD        | Renoir Device 24: Function 4 | 790   |            | 6B6205BC5D |
| 1022:144d |           | AMD        | Renoir Device 24: Function 5 | 790   |            | 6B6205BC5D |
| 1022:144e |           | AMD        | Renoir Device 24: Function 6 | 790   |            | 6B6205BC5D |
| 1022:144f |           | AMD        | Renoir Device 24: Function 7 | 790   |            | 6B6205BC5D |
| 1022:15b0 |           | AMD        | Stoney HT Configuration      | 739   |            | 161B42524B |
| 1022:15b1 |           | AMD        | Stoney Address Maps          | 739   |            | 161B42524B |
| 1022:15b2 |           | AMD        | Stoney DRAM Configuration    | 739   |            | 161B42524B |
| 1022:15b3 |           | AMD        | Stoney Miscellaneous Conf... | 739   | k10temp    | 161B42524B |
| 1022:15b4 |           | AMD        | Stoney PM Configuration      | 739   | fam15h_... | 161B42524B |
| 1022:15b5 |           | AMD        | Stoney NB Performance Mon... | 739   |            | 161B42524B |
| 1022:15d0 | 1022:15d0 | AMD        | Raven/Raven2 Root Complex    | 727   | k10temp    | F504E72617 |
| 1022:156b |           | AMD        | Family 16h (Models 30h-3f... | 706   |            | 779BFC3B47 |
| 1022:1580 |           | AMD        | Family 16h (Models 30h-3f... | 706   |            | 779BFC3B47 |
| 1022:1581 |           | AMD        | Family 16h (Models 30h-3f... | 706   |            | 779BFC3B47 |
| 1022:1582 |           | AMD        | Family 16h (Models 30h-3f... | 706   |            | 779BFC3B47 |
| 1022:1583 |           | AMD        | Family 16h (Models 30h-3f... | 706   | k10temp    | 779BFC3B47 |
| 1022:1584 |           | AMD        | Family 16h (Models 30h-3f... | 706   | fam15h_... | 779BFC3B47 |
| 1022:1585 |           | AMD        | Family 16h (Models 30h-3f... | 706   |            | 779BFC3B47 |
| 1022:1439 | 1022:1234 | AMD        | Family 16h Processor Func... | 698   | pcieport   | 3B4E5A1EB8 |
| 1022:43a0 | 1022:0000 | AMD        | Hudson PCI to PCI bridge ... | 644   | pcieport   | 1DBB8065D8 |
| 1022:1400 |           | AMD        | Family 15h (Models 10h-1f... | 598   |            | 9D9096B34C |
| 1022:1401 |           | AMD        | Family 15h (Models 10h-1f... | 598   |            | 9D9096B34C |
| 1022:1402 |           | AMD        | Family 15h (Models 10h-1f... | 598   |            | 9D9096B34C |
| 1022:1403 |           | AMD        | Family 15h (Models 10h-1f... | 598   | k10temp    | 9D9096B34C |
| 1022:1404 |           | AMD        | Family 15h (Models 10h-1f... | 598   |            | 9D9096B34C |
| 1022:1405 |           | AMD        | Family 15h (Models 10h-1f... | 598   |            | 9D9096B34C |
| 1002:43a0 | 1002:0000 | AMD        | SB700/SB800/SB900 PCI to ... | 573   | shpchp     | 8A6D18EBAD |
| 1022:1635 | 1022:1635 | AMD        | Renoir Internal PCIe GPP ... | 563   | pcieport   | 8700A7EAED |
| 1022:1200 |           | AMD        | Family 10h Processor Hype... | 556   |            | 6B480BCD67 |
| 1022:1201 |           | AMD        | Family 10h Processor Addr... | 556   |            | 6B480BCD67 |
| 1022:1202 |           | AMD        | Family 10h Processor DRAM... | 556   |            | 6B480BCD67 |
| 1022:1203 |           | AMD        | Family 10h Processor Misc... | 556   | k10temp    | 6B480BCD67 |
| 1022:1204 |           | AMD        | Family 10h Processor Link... | 556   |            | 6B480BCD67 |
| 1022:1100 |           | AMD        | K8 [Athlon64/Opteron] Hyp... | 555   |            | D38F5B09D2 |
| 1022:1101 |           | AMD        | K8 [Athlon64/Opteron] Add... | 555   |            | D38F5B09D2 |
| 1022:1102 |           | AMD        | K8 [Athlon64/Opteron] DRA... | 555   |            | D38F5B09D2 |
| 1022:1103 |           | AMD        | K8 [Athlon64/Opteron] Mis... | 555   | k8temp     | D38F5B09D2 |
| 1022:1510 | 1022:1510 | AMD        | Family 14h Processor Root... | 534   |            | 72608B2EA0 |
| 1022:43a1 | 1022:0000 | AMD        | Hudson PCI to PCI bridge ... | 502   | pcieport   | 1DBB8065D8 |
| 8086:1e10 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 499   | shpchp     | 5872E567EC |
| 8086:1e12 | 17aa:3977 | Intel      | 7 Series/C210 Series Chip... | 487   | shpchp     | 5872E567EC |
| 1022:1414 | 1022:1234 | AMD        | Family 15h (Models 10h-1f... | 456   | pcieport   | 9D9096B34C |
| 8086:0154 | 17aa:3977 | Intel      | 3rd Gen Core processor DR... | 419   | ivb_uncore | 5872E567EC |
| 1022:1530 |           | AMD        | Family 16h Processor Func... | 409   |            | 3B4E5A1EB8 |
| 1022:1531 |           | AMD        | Family 16h Processor Func... | 409   |            | 3B4E5A1EB8 |
| 1022:1532 |           | AMD        | Family 16h Processor Func... | 409   |            | 3B4E5A1EB8 |
| 1022:1533 |           | AMD        | Family 16h Processor Func... | 409   | k10temp    | 3B4E5A1EB8 |
| 1022:1534 |           | AMD        | Family 16h Processor Func... | 409   | fam15h_... | 3B4E5A1EB8 |
| 1022:1535 |           | AMD        | Family 16h Processor Func... | 409   |            | 3B4E5A1EB8 |
| 1022:1538 |           | AMD        | Family 16h Processor Func... | 409   |            | 3B4E5A1EB8 |
| 8086:2280 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 389   | iosf_mb... | 1B5E908CFF |
| 8086:229c | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 389   | lpc_ich    | 1B5E908CFF |
| 8086:1e59 | 17aa:3977 | Intel      | HM76 Express Chipset LPC ... | 388   | lpc_ich    | 5872E567EC |
| 8086:2940 |           | Intel      | 82801I (ICH9 Family) PCI ... | 368   | pcieport   | 65FBD3DEF4 |
| 1022:1709 | 1022:1234 | AMD        | Family 12h Processor Root... | 358   | shpchp     | E2CABCDB94 |
| 1002:43a1 | 1002:0000 | AMD        | SB700/SB800/SB900 PCI to ... | 352   | shpchp     | 8082B08CE8 |
| 1022:1512 | 1022:1234 | AMD        | Family 14h Processor Root... | 341   | shpchp     | 8082B08CE8 |
| 1022:1634 | 1022:1453 | AMD        | Renoir PCIe GPP Bridge       | 339   | pcieport   | 8700A7EAED |
| 8086:294a |           | Intel      | 82801I (ICH9 Family) PCI ... | 329   | pcieport   | 65FBD3DEF4 |
| 8086:2944 |           | Intel      | 82801I (ICH9 Family) PCI ... | 319   | pcieport   | 65FBD3DEF4 |
| 8086:2448 | 17aa:20f4 | Intel      | 82801 Mobile PCI Bridge      | 301   |            | DB936567F0 |
| 8086:2940 | 17aa:20f3 | Intel      | 82801I (ICH9 Family) PCI ... | 301   | pcieport   | DB936567F0 |
| 8086:0104 | 17aa:3975 | Intel      | 2nd Generation Core Proce... | 299   |            | 21DB34139A |
| 8086:1c10 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 299   | shpchp     | 21DB34139A |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:5287 | 1043:202f | Realtek... | RTL8411B PCI Express Card... | 254   | rtsx_pci   | 13FF923546 |
| 10ec:5286 | 1043:202f | Realtek... | RTL8402 Integrated 1-LUN ... | 214   | rtsx_pci   | DCD714D5FA |
| 10ec:5289 | 1043:202f | Realtek... | RTL8411 PCI Express Card ... | 159   | rtsx_pci   | 08930695BC |
| 10ec:5286 | 10ec:5286 | Realtek... | RTL8402 Integrated 1-LUN ... | 143   | rtsx_pci   | 208FC3F30F |
| 10ec:525a | 1028:0905 | Realtek... | RTS525A PCI Express Card ... | 112   | rtsx_pci   | 9CDE952049 |
| 10ec:5229 | 1043:202f | Realtek... | RTS5229 PCI Express Card ... | 111   | rtsx_pci   | 5C45DFB686 |
| 10ec:5227 | 17aa:220c | Realtek... | RTS5227 PCI Express Card ... | 107   | rtsx_pci   | 4C600416F9 |
| 10ec:5287 | 1025:1193 | Realtek... | RTL8411B PCI Express Card... | 105   | rtsx_pci   | E922639FF6 |
| 10ec:5287 | 1025:0866 | Realtek... | RTL8411B PCI Express Card... | 103   | rtsx_pci   | 58B4832D53 |
| 10ec:5289 | 10ec:5289 | Realtek... | RTL8411 PCI Express Card ... | 103   | rtsx_pci   | 8AF930F7E1 |
| 10ec:525a | 1028:087c | Realtek... | RTS525A PCI Express Card ... | 97    | rtsx_pci   | 31A6F21CCD |
| 10ec:5227 | 103c:198f | Realtek... | RTS5227 PCI Express Card ... | 96    | rtsx_pci   | 6573923D55 |
| 10ec:5227 | 17aa:220e | Realtek... | RTS5227 PCI Express Card ... | 95    | rtsx_pci   | 4EC9EAAC2F |
| 10ec:5209 | 104d:908b | Realtek... | RTS5209 PCI Express Card ... | 93    | rtsx_pci   | F88D733F75 |
| 10ec:522a | 103c:8079 | Realtek... | RTS522A PCI Express Card ... | 93    | rtsx_pci   | 0FA8058EEB |
| 10ec:5287 | 1025:1094 | Realtek... | RTL8411B PCI Express Card... | 92    | rtsx_pci   | 9756CE58FC |
| 10ec:522a | 10ec:522a | Realtek... | RTS522A PCI Express Card ... | 89    | rtsx_pci   | ECC7F6B940 |
| 10ec:5227 | 17aa:5034 | Realtek... | RTS5227 PCI Express Card ... | 87    | rtsx_pci   | 6131E3C22A |
| 10ec:5229 | 17aa:3808 | Realtek... | RTS5229 PCI Express Card ... | 86    | rtsx_pci   | BAC9935F0B |
| 10ec:522a | 17aa:5082 | Realtek... | RTS522A PCI Express Card ... | 84    | rtsx_pci   | 6B6205BC5D |
| 10ec:525a | 1028:07e6 | Realtek... | RTS525A PCI Express Card ... | 81    | rtsx_pci   | C2E884F793 |
| 10ec:5209 | 1025:0685 | Realtek... | RTS5209 PCI Express Card ... | 80    | rtsx_pci   | 03831239E1 |
| 10ec:525a | 1028:08af | Realtek... | RTS525A PCI Express Card ... | 80    | rtsx_pci   | 80857F497B |
| 10ec:5229 | 103c:1854 | Realtek... | RTS5229 PCI Express Card ... | 78    | rtsx_pci   | 21FB6389E7 |
| 10ec:5229 | 10ec:5229 | Realtek... | RTS5229 PCI Express Card ... | 78    | rtsx_pci   | A248DFB63E |
| 10ec:525a | 1028:0962 | Realtek... | RTS525A PCI Express Card ... | 77    | rtsx_pci   | 9E26259821 |
| 10ec:5287 | 1025:1295 | Realtek... | RTL8411B PCI Express Card... | 77    | rtsx_pci   | BEDAFBAD9B |
| 10ec:5209 | 103c:3577 | Realtek... | RTS5209 PCI Express Card ... | 75    | rtsx_pci   | C0FCCB63BB |
| 10ec:525a | 1028:07be | Realtek... | RTS525A PCI Express Card ... | 75    | rtsx_pci   | 6EE00932DC |
| 10ec:5227 | 17aa:2214 | Realtek... | RTS5227 PCI Express Card ... | 74    | rtsx_pci   | F100B7CDB9 |
| 10ec:5287 | 1025:1264 | Realtek... | RTL8411B PCI Express Card... | 74    | rtsx_pci   | 9971E42809 |
| 10ec:5287 | 1025:1192 | Realtek... | RTL8411B PCI Express Card... | 73    | rtsx_pci   | CDC742CD03 |
| 10ec:5227 | 103c:2216 | Realtek... | RTS5227 PCI Express Card ... | 72    | rtsx_pci   | 304747E4C6 |
| 10ec:522a | 17aa:2233 | Realtek... | RTS522A PCI Express Card ... | 70    | rtsx_pci   | 79D4310531 |
| 10ec:5227 | 17aa:2226 | Realtek... | RTS5227 PCI Express Card ... | 68    | rtsx_pci   | A5D677976F |
| 10ec:5227 | 103c:1993 | Realtek... | RTS5227 PCI Express Card ... | 64    | rtsx_pci   | 605367D5D4 |
| 10ec:5209 | 104d:90b8 | Realtek... | RTS5209 PCI Express Card ... | 62    | rtsx_pci   | 77DF70A98A |
| 10ec:5227 | 10ec:5227 | Realtek... | RTS5227 PCI Express Card ... | 62    | rtsx_pci   | 5834B6321D |
| 10ec:5287 | 10ec:5287 | Realtek... | RTL8411B PCI Express Card... | 61    | rtsx_pci   | 4FCC4FBCB8 |
| 10ec:5229 | 10cf:176b | Realtek... | RTS5229 PCI Express Card ... | 60    | rtsx_pci   | B2D4A08D24 |
| 10ec:525a | 1028:081c | Realtek... | RTS525A PCI Express Card ... | 59    | rtsx_pci   | A92377CB2A |
| 10ec:5249 | 17aa:3801 | Realtek... | RTS5249 PCI Express Card ... | 58    | rtsx_pci   | CC68265730 |
| 10ec:525a | 1028:075b | Realtek... | RTS525A PCI Express Card ... | 56    | rtsx_pci   | 97DBD7A2D0 |
| 10ec:5229 | 1179:f91b | Realtek... | RTS5229 PCI Express Card ... | 55    | rtsx_pci   | 80080989FA |
| 10ec:522a | 1043:202f | Realtek... | RTS522A PCI Express Card ... | 55    | rtsx_pci   | 8B7EEA5D26 |
| 10ec:5209 | 104d:90ab | Realtek... | RTS5209 PCI Express Card ... | 54    | rtsx_pci   | 23D5E048CB |
| 10ec:525a | 1028:06de | Realtek... | RTS525A PCI Express Card ... | 53    | rtsx_pci   | A725E7458E |
| 10ec:5289 | 1043:1587 | Realtek... | RTL8411 PCI Express Card ... | 53    | rtsx_pci   | C3D21619BB |
| 10ec:5229 | 103c:188b | Realtek... | RTS5229 PCI Express Card ... | 52    | rtsx_pci   | D23F6C89AD |
| 10ec:5229 | 1179:f920 | Realtek... | RTS5229 PCI Express Card ... | 52    | rtsx_pci   | 1C388B7952 |
| 10ec:5229 | 1179:ff1e | Realtek... | RTS5229 PCI Express Card ... | 52    | rtsx_pci   | 33D64C7A69 |
| 10ec:5260 | 1028:097d | Realtek... | RTS5260 PCI Express Card ... | 52    | rtsx_pci   | 8C072EA1C4 |
| 10ec:5287 | 1025:118a | Realtek... | RTL8411B PCI Express Card... | 52    | rtsx_pci   | A1DE054BBB |
| 10ec:5229 | 103c:2213 | Realtek... | RTS5229 PCI Express Card ... | 51    | rtsx_pci   | 1CE25A2590 |
| 10ec:5229 | 103c:184a | Realtek... | RTS5229 PCI Express Card ... | 48    | rtsx_pci   | AB2366FD14 |
| 10ec:5209 | 1025:0590 | Realtek... | RTS5209 PCI Express Card ... | 47    | rtsx_pci   | 1AB9A823AC |
| 10ec:5229 | 103c:183e | Realtek... | RTS5229 PCI Express Card ... | 47    | rtsx_pci   | 03F3D2F19B |
| 10ec:522a | 17aa:2279 | Realtek... | RTS522A PCI Express Card ... | 47    | rtsx_pci   | 81BBBC9593 |
| 10ec:522a | 17aa:5053 | Realtek... | RTS522A PCI Express Card ... | 47    | rtsx_pci   | 6B9264BFE9 |
| 1aea:6625 | 103c:8478 | Alcor M... | AU6625 PCI-E Flash card r... | 47    | alcor_pci  | D3A001E377 |
| 10ec:5209 | 103c:1670 | Realtek... | RTS5209 PCI Express Card ... | 45    | rtsx_pci   | 0245DA9040 |
| 10ec:5229 | 103c:1818 | Realtek... | RTS5229 PCI Express Card ... | 44    | rtsx_pci   | B9FD7914E2 |
| 10ec:525a | 1028:087d | Realtek... | RTS525A PCI Express Card ... | 44    | rtsx_pci   | A5C63380D6 |
| 10ec:5229 | 1179:f840 | Realtek... | RTS5229 PCI Express Card ... | 43    | rtsx_pci   | 6B411D236A |
| 10ec:5289 | 1043:1457 | Realtek... | RTL8411 PCI Express Card ... | 43    | rtsx_pci   | 87C1F4A491 |
| 10ec:5229 | 17aa:5000 | Realtek... | RTS5229 PCI Express Card ... | 42    | rtsx_pci   | 9F605297CB |
| 10ec:525a | 1028:06dc | Realtek... | RTS525A PCI Express Card ... | 42    | rtsx_pci   | FFDB13EDA0 |
| 10ec:522a | 103c:8730 | Realtek... | RTS522A PCI Express Card ... | 41    | rtsx_pci   | FC1870A101 |
| 10ec:5229 | 103c:1858 | Realtek... | RTS5229 PCI Express Card ... | 40    | rtsx_pci   | 710FDCA60A |
| 10ec:5227 | 17aa:5028 | Realtek... | RTS5227 PCI Express Card ... | 39    | rtsx_pci   | 4BED2E361F |
| 10ec:525a | 1028:0906 | Realtek... | RTS525A PCI Express Card ... | 39    | rtsx_pci   | 2B4444A6FA |
| 10ec:5260 | 1028:0991 | Realtek... | RTS5260 PCI Express Card ... | 39    | rtsx_pci   | 089BB7C152 |
| 10ec:5287 | 1025:108f | Realtek... | RTL8411B PCI Express Card... | 39    | rtsx_pci   | D0C45F9B31 |
| 10ec:5209 | 1025:0781 | Realtek... | RTS5209 PCI Express Card ... | 38    | rtsx_pci   | 011928039E |
| 10ec:522a | 103c:837d | Realtek... | RTS522A PCI Express Card ... | 38    | rtsx_pci   | 7799E3D32A |
| 10ec:5209 | 104d:907b | Realtek... | RTS5209 PCI Express Card ... | 37    | rtsx_pci   | 828A8AC75D |
| 10ec:5229 | 103c:21f7 | Realtek... | RTS5229 PCI Express Card ... | 37    | rtsx_pci   | 814D85CF91 |
| 10ec:525a | 1028:096d | Realtek... | RTS525A PCI Express Card ... | 37    | rtsx_pci   | FBBAF8088B |
| 10ec:525a | 17aa:222e | Realtek... | RTS525A PCI Express Card ... | 37    | rtsx_pci   | 88A08A450D |
| 10ec:5287 | 1025:1259 | Realtek... | RTL8411B PCI Express Card... | 37    | rtsx_pci   | 8DAB17C109 |
| 10ec:5289 | 1025:0724 | Realtek... | RTL8411 PCI Express Card ... | 37    | rtsx_pci   | BC54B9763A |
| 10ec:5227 | 10cf:187f | Realtek... | RTS5227 PCI Express Card ... | 36    | rtsx_pci   | 4DCED4EE57 |
| 10ec:5229 | 17aa:3800 | Realtek... | RTS5229 PCI Express Card ... | 36    | rtsx_pci   | 9025A3C7F9 |
| 10ec:5209 | 103c:3567 | Realtek... | RTS5209 PCI Express Card ... | 35    | rtsx_pci   | C774724C5F |
| 10ec:5227 | 1179:0001 | Realtek... | RTS5227 PCI Express Card ... | 35    | rtsx_pci   | 39DD5CA43B |
| 10ec:525a | 1028:06e4 | Realtek... | RTS525A PCI Express Card ... | 35    | rtsx_pci   | EA3FABAB64 |
| 10ec:522a | 17aa:5072 | Realtek... | RTS522A PCI Express Card ... | 34    | rtsx_pci   | 62C94909C7 |
| 10ec:525a | 1028:0704 | Realtek... | RTS525A PCI Express Card ... | 34    | rtsx_pci   | 3796A94A31 |
| 10ec:525a | 1028:07a7 | Realtek... | RTS525A PCI Express Card ... | 34    | rtsx_pci   | 8A2F2558AC |
| 10ec:5287 | 1025:1191 | Realtek... | RTL8411B PCI Express Card... | 34    | rtsx_pci   | 3742059A46 |
| 10ec:522a | 17aa:5124 | Realtek... | RTS522A PCI Express Card ... | 33    | rtsx_pci   | 4DE4650899 |
| 10ec:525a | 1028:08e1 | Realtek... | RTS525A PCI Express Card ... | 33    | rtsx_pci   | 011A257801 |
| 10ec:5287 | 1025:0940 | Realtek... | RTL8411B PCI Express Card... | 33    | rtsx_pci   | A874B34C2A |
| 10ec:5229 | 103c:1849 | Realtek... | RTS5229 PCI Express Card ... | 32    | rtsx_pci   | 1DBB8065D8 |
| 10ec:522a | 103c:8101 | Realtek... | RTS522A PCI Express Card ... | 32    | rtsx_pci   | 37502C4ABE |
| 10ec:525a | 1028:082a | Realtek... | RTS525A PCI Express Card ... | 32    | rtsx_pci   | CB72DB0851 |
| 10ec:5287 | 1025:128d | Realtek... | RTL8411B PCI Express Card... | 32    | rtsx_pci   | D2E4A69C16 |
| 10ec:5209 | 104d:90ac | Realtek... | RTS5209 PCI Express Card ... | 31    | rtsx_pci   | 1202F15783 |
| 10ec:5227 | 17aa:2210 | Realtek... | RTS5227 PCI Express Card ... | 31    | rtsx_pci   | 5D86D2BD4A |
| 10ec:5209 | 1025:061f | Realtek... | RTS5209 PCI Express Card ... | 30    | rtsx_pci   | 6DAC0B495F |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0aa3 | 10de:cb79 | Nvidia     | MCP79 Co-processor           | 140   | nvidia     | F982A2F6CC |
| 10de:0d7a | 10de:cb89 | Nvidia     | MCP89 Co-Processor           | 64    |            | E3121B6209 |
| 10de:0753 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] Co-... | 53    |            | 67C143DFE9 |
| 10de:0543 | 103c:30cf | Nvidia     | MCP67 Co-processor           | 32    |            | CB77A79EE8 |
| 10de:0543 | 1025:0126 | Nvidia     | MCP67 Co-processor           | 31    |            | AA6D721BF2 |
| 10de:0aa3 | 1043:1cf7 | Nvidia     | MCP79 Co-processor           | 25    | nvidia     | 7A84F17BDB |
| 10de:0aa3 | 1043:1fa7 | Nvidia     | MCP79 Co-processor           | 24    | nvidia     | B0BCC6C31C |
| 10de:0271 | 103c:30b7 | Nvidia     | MCP51 PMU                    | 19    |            | C28788427E |
| 10de:0aa3 | 1043:1d17 | Nvidia     | MCP79 Co-processor           | 18    | nvidia     | F1573DB462 |
| 10de:0543 | 1043:16a7 | Nvidia     | MCP67 Co-processor           | 12    |            | 414786C3D5 |
| 10de:0447 | 103c:30cf | Nvidia     | MCP65 SMU                    | 11    |            | D7BE62BFCB |
| 10de:0aa3 | 1043:8402 | Nvidia     | MCP79 Co-processor           | 11    | nvidia     | 07474931C9 |
| 10de:0271 | 1025:0112 | Nvidia     | MCP51 PMU                    | 10    |            | 56639ACA29 |
| 10de:0aa3 | 103c:3651 | Nvidia     | MCP79 Co-processor           | 8     | nvidia     | A29E32B5FB |
| 10de:0aa3 | 1462:1012 | Nvidia     | MCP79 Co-processor           | 8     | nvidia     | B1D00D1444 |
| 10de:0543 | 103c:30d6 | Nvidia     | MCP67 Co-processor           | 6     |            | D6DADC467D |
| 10de:0543 | 103c:30ea | Nvidia     | MCP67 Co-processor           | 6     |            | 1CEE50E485 |
| 10de:0aa3 | 1025:0160 | Nvidia     | MCP79 Co-processor           | 6     | nvidia     | 08C92ED6C5 |
| 10de:0271 | 103c:30b5 | Nvidia     | MCP51 PMU                    | 5     |            | EFFFE561DA |
| 10de:0271 | 103c:30bf | Nvidia     | MCP51 PMU                    | 5     |            | BAD7484C1A |
| 10de:0271 | 1462:3fc1 | Nvidia     | MCP51 PMU                    | 5     |            | 800B19FF2D |
| 10de:0aa3 | 1071:9070 | Nvidia     | MCP79 Co-processor           | 5     | nvidia     | ABE849C090 |
| 10de:0271 | 1043:1367 | Nvidia     | MCP51 PMU                    | 4     |            | 7BD5FA25B3 |
| 10de:0753 | 1462:6720 | Nvidia     | MCP78S [GeForce 8200] Co-... | 4     |            | C26B88DF64 |
| 10de:0271 | 103c:30e5 | Nvidia     | MCP51 PMU                    | 3     |            | A070611109 |
| 10de:0271 | 1462:373d | Nvidia     | MCP51 PMU                    | 3     |            | 154009C211 |
| 10de:0271 | 1734:110c | Nvidia     | MCP51 PMU                    | 3     |            | 79DCA1A7CC |
| 10de:0753 | 1025:014d | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | 77FC351561 |
| 10de:0aa3 | 1043:1a87 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 03675A2262 |
| 10de:0aa3 | 1043:1fd7 | Nvidia     | MCP79 Co-processor           | 3     |            | 4B30E929C5 |
| 10de:0aa3 | 1734:1151 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | E6A298846B |
| 10de:0543 | 1025:0127 | Nvidia     | MCP67 Co-processor           | 2     |            | 0D272A5910 |
| 10de:0aa3 | 1028:0271 | Nvidia     | MCP79 Co-processor           | 2     |            | C928DD680A |
| 10de:0aa3 | 1462:1019 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | 2054B3A4CC |
| 10de:0aa3 | 17aa:38da | Nvidia     | MCP79 Co-processor           | 2     |            | C38D40E936 |
| 10de:0aa3 | 1b0a:4203 | Nvidia     | MCP79 Co-processor           | 2     |            | 3D1668F30A |
| 10de:0271 | 1043:1322 | Nvidia     | MCP51 PMU                    | 1     |            | 71FE8FB963 |
| 10de:0271 | 1043:14b7 | Nvidia     | MCP51 PMU                    | 1     |            | AFE46A35A8 |
| 10de:0271 | 107b:0317 | Nvidia     | MCP51 PMU                    | 1     |            | 1178CC8597 |
| 10de:0271 | 1734:10d3 | Nvidia     | MCP51 PMU                    | 1     |            | 6172D9B266 |
| 10de:0271 | 1734:10d4 | Nvidia     | MCP51 PMU                    | 1     |            | 360270471C |
| 10de:0543 | 1043:1697 | Nvidia     | MCP67 Co-processor           | 1     |            | C3296D5344 |
| 10de:0543 | 1631:c106 | Nvidia     | MCP67 Co-processor           | 1     |            | BC2AD0771E |
| 10de:0753 | 1025:014a | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | F63FFEFC64 |
| 10de:0753 | 107b:0173 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 4A6A75378D |
| 10de:0753 | 1462:6520 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 12132D4EBD |
| 10de:0aa3 | 1071:9072 | Nvidia     | MCP79 Co-processor           | 1     | nvidia     | 109599A6F6 |
| 10de:0aa3 | 1071:9515 | Nvidia     | MCP79 Co-processor           | 1     | nvidia     | E028F277D4 |
| 10de:0aa3 | 1462:71f0 | Nvidia     | MCP79 Co-processor           | 1     | nvidia     | FB8A0F79C4 |
| 10de:0aa3 | 1b7d:0040 | Nvidia     | MCP79 Co-processor           | 1     |            | 053ACCA095 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e3a | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 508   | mei_me     | 5872E567EC |
| 8086:1c3a | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 297   | mei_me     | 21DB34139A |
| 8086:3b64 | 17aa:215f | Intel      | 5 Series/3400 Series Chip... | 295   | mei_me     | 5DC4A1E557 |
| 8086:9c3a | 17aa:3978 | Intel      | 8 Series HECI #0             | 275   | mei_me     | B1B8196F26 |
| 8086:2a44 | 17aa:20e6 | Intel      | Mobile 4 Series Chipset M... | 234   | mei_me     | DB936567F0 |
| 8086:3b64 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 170   | mei_me     | 11F1CDC49A |
| 8086:1e3a | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 166   | mei_me     | EC1ABD9485 |
| 8086:1c3a | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 165   | mei_me     | A53D0DE98A |
| 8086:1e3a | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 165   | mei_me     | C9503690D6 |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 163   | mei_me     | 71A92492E3 |
| 8086:1e3a | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 151   | mei_me     | 52667487D2 |
| 8086:8c3a | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 150   | mei_me     | 7FB630F632 |
| 8086:1c3a | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 148   | mei_me     | 438D785F0E |
| 8086:1c3a | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 147   | mei_me     | 74547808D3 |
| 8086:1c3a | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 145   | mei_me     | B420F25ED4 |
| 8086:1c3a | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 138   | mei_me     | 33617DD1A8 |
| 8086:319a | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 135   | mei_me     | 170B220F5B |
| 8086:1e3a | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 134   | mei_me     | 50D562CAB5 |
| 8086:3b64 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 126   | mei_me     | C172C655DE |
| 8086:3b64 | 17aa:38a5 | Intel      | 5 Series/3400 Series Chip... | 126   | mei_me     | 62053AE42B |
| 8086:1e3a | 1043:124d | Intel      | 7 Series/C216 Chipset Fam... | 125   | mei_me     | 08930695BC |
| 8086:3b64 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 123   | mei_me     | 03E0270FDD |
| 8086:9d3a | 17aa:386e | Intel      | Sunrise Point-LP CSME HEC... | 123   | mei_me     | 19226582D9 |
| 8086:a328 | 1025:1331 | Intel      | Cannon Lake PCH Serial IO... | 119   | intel_lpss | 38688703F4 |
| 8086:a360 | 1025:1331 | Intel      | Cannon Lake PCH HECI Cont... | 119   | mei_me     | 38688703F4 |
| 8086:1c3a | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 118   | mei_me     | FF37A9C00D |
| 8086:1c3a | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 118   | mei_me     | 660A6B9E20 |
| 8086:1e3a | 1028:0534 | Intel      | 7 Series/C216 Chipset Fam... | 117   | mei_me     | 98420A7D92 |
| 8086:319a | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 117   | mei_me     | 021617B9A0 |
| 8086:1e3a | 17aa:21f6 | Intel      | 7 Series/C216 Chipset Fam... | 115   | mei_me     | 9ECBB7A946 |
| 8086:1e3a | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 114   | mei_me     | B732F94275 |
| 8086:a360 | 1028:0905 | Intel      | Cannon Lake PCH HECI Cont... | 113   | mei_me     | 9CDE952049 |
| 8086:9c3a | 17aa:220c | Intel      | 8 Series HECI #0             | 110   | mei_me     | 4C600416F9 |
| 8086:1c3a | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 108   | mei_me     | A8FD68FCCC |
| 8086:02e0 | 17aa:5079 | Intel      | Comet Lake Management Eng... | 107   | mei_me     | 0BC4073D23 |
| 8086:9d3a | 1025:1193 | Intel      | Sunrise Point-LP CSME HEC... | 105   | mei_me     | E922639FF6 |
| 8086:1e3a | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 104   | mei_me     | 2BA1AA7C62 |
| 8086:1c3a | 103c:161c | Intel      | 6 Series/C200 Series Chip... | 101   | mei_me     | 701E56A49F |
| 8086:9c3a | 103c:198f | Intel      | 8 Series HECI #0             | 99    | mei_me     | 6573923D55 |
| 8086:1e3a | 10cf:16ea | Intel      | 7 Series/C216 Chipset Fam... | 98    | mei_me     | B2D4A08D24 |
| 8086:a360 | 1028:087c | Intel      | Cannon Lake PCH HECI Cont... | 98    | mei_me     | 31A6F21CCD |
| 8086:9d3a | 1028:0810 | Intel      | Sunrise Point-LP CSME HEC... | 97    | mei_me     | 2FD333BC52 |
| 8086:8c3a | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 96    | mei_me     | 4EC9EAAC2F |
| 8086:9de0 | 17aa:2279 | Intel      | Cannon Point-LP MEI Contr... | 96    | mei_me     | 2444839350 |
| 8086:9cba | 8086:7270 | Intel      | Wildcat Point-LP MEI Cont... | 95    | mei_me     | C0ED6370C5 |
| 8086:1c3a | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 94    | mei_me     | F8B9508953 |
| 8086:1c3a | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 93    | mei_me     | 389E1A52A6 |
| 8086:1e3a | 103c:179b | Intel      | 7 Series/C216 Chipset Fam... | 93    | mei_me     | 7D39BC1331 |
| 8086:9c3a | 1025:0866 | Intel      | 8 Series HECI #0             | 93    | mei_me     | 58B4832D53 |
| 8086:9d3a | 103c:8079 | Intel      | Sunrise Point-LP CSME HEC... | 93    | mei_me     | 0FA8058EEB |
| 8086:1e3a | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 92    | mei_me     | A5268098B2 |
| 8086:9c3a | 1028:0651 | Intel      | 8 Series HECI #0             | 92    | mei_me     | E1A816CC42 |
| 8086:9de0 | 103c:8549 | Intel      | Cannon Point-LP MEI Contr... | 92    | mei_me     | 9A264DBCB2 |
| 8086:1c3a | 104d:908b | Intel      | 6 Series/C200 Series Chip... | 91    | mei_me     | F88D733F75 |
| 8086:1e3a | 1179:fb31 | Intel      | 7 Series/C216 Chipset Fam... | 91    | mei_me     | 6BECED18DA |
| 8086:1e3a | 1043:1477 | Intel      | 7 Series/C216 Chipset Fam... | 90    | mei_me     | 62C6944A06 |
| 8086:1e3a | 1043:14c7 | Intel      | 7 Series/C216 Chipset Fam... | 90    | mei_me     | 53842E648E |
| 8086:9d3a | 17aa:3801 | Intel      | Sunrise Point-LP CSME HEC... | 90    | mei_me     | 74D1DA4B68 |
| 8086:9d3a | 1043:12d1 | Intel      | Sunrise Point-LP CSME HEC... | 89    | mei_me     | 570905286F |
| 8086:1c3a | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 88    | mei_me     | C40BAA791F |
| 8086:9d3a | 17aa:225d | Intel      | Sunrise Point-LP CSME HEC... | 88    | mei_me     | BBA3BC97B7 |
| 8086:9cba | 17aa:5034 | Intel      | Wildcat Point-LP MEI Cont... | 85    | mei_me     | 6131E3C22A |
| 8086:9c3a | 1025:0775 | Intel      | 8 Series HECI #0             | 84    | mei_me     | 2729E1919C |
| 8086:9d3a |           | Intel      | Sunrise Point-LP CSME HEC... | 84    | mei_me     | 7AEC563171 |
| 8086:9d3a | 1028:07e6 | Intel      | Sunrise Point-LP CSME HEC... | 83    | mei_me     | C2E884F793 |
| 8086:9de0 | 1028:08af | Intel      | Cannon Point-LP MEI Contr... | 82    | mei_me     | 80857F497B |
| 8086:5a9a | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 81    | mei_me     | 9F12330C51 |
| 8086:9d3a | 17aa:3843 | Intel      | Sunrise Point-LP CSME HEC... | 80    | mei_me     | 0540D35606 |
| 8086:9d3a | 17aa:5068 | Intel      | Sunrise Point-LP CSME HEC... | 79    | mei_me     | 893F642CBB |
| 8086:9d3a | 1028:078b | Intel      | Sunrise Point-LP CSME HEC... | 78    | mei_me     | 4F60F64204 |
| 8086:02e0 | 1028:0962 | Intel      | Comet Lake Management Eng... | 77    | mei_me     | 9E26259821 |
| 8086:1e3a | 103c:1854 | Intel      | 7 Series/C216 Chipset Fam... | 77    | mei_me     | 21FB6389E7 |
| 8086:a13a | 1028:07be | Intel      | 100 Series/C230 Series Ch... | 76    | mei_me     | 6EE00932DC |
| 8086:9d3a | 1025:1295 | Intel      | Sunrise Point-LP CSME HEC... | 75    | mei_me     | BEDAFBAD9B |
| 8086:1e3a | 144d:c652 | Intel      | 7 Series/C216 Chipset Fam... | 74    | mei_me     | 326B21D2B4 |
| 8086:a328 | 1025:1264 | Intel      | Cannon Lake PCH Serial IO... | 74    | intel_lpss | 9971E42809 |
| 8086:a360 | 1025:1264 | Intel      | Cannon Lake PCH HECI Cont... | 74    | mei_me     | 9971E42809 |
| 8086:9c3a | 17aa:2214 | Intel      | 8 Series HECI #0             | 73    | mei_me     | F100B7CDB9 |
| 8086:9d3a | 17aa:225c | Intel      | Sunrise Point-LP CSME HEC... | 73    | mei_me     | C33E7CED42 |
| 8086:1c3a | 1179:fc30 | Intel      | 6 Series/C200 Series Chip... | 72    | mei_me     | 60EB674C8F |
| 8086:9cba | 103c:2216 | Intel      | Wildcat Point-LP MEI Cont... | 72    | mei_me     | 304747E4C6 |
| 8086:9de0 | 17aa:2292 | Intel      | Cannon Point-LP MEI Contr... | 72    | mei_me     | FBF4582983 |
| 8086:9d3a | 103c:832a | Intel      | Sunrise Point-LP CSME HEC... | 71    | mei_me     | A7BDFE8774 |
| 8086:3b64 | 10cf:152b | Intel      | 5 Series/3400 Series Chip... | 69    | mei_me     | F220F9AC45 |
| 8086:9cba | 17aa:2226 | Intel      | Wildcat Point-LP MEI Cont... | 69    | mei_me     | A5D677976F |
| 8086:9d3a | 1025:115f | Intel      | Sunrise Point-LP CSME HEC... | 69    | mei_me     | 9756CE58FC |
| 8086:1e3a | 1179:ff1e | Intel      | 7 Series/C216 Chipset Fam... | 68    | mei_me     | E93FDA84E6 |
| 8086:9de0 | 17aa:5072 | Intel      | Cannon Point-LP MEI Contr... | 67    | mei_me     | 62C94909C7 |
| 8086:1c3a | 103c:167c | Intel      | 6 Series/C200 Series Chip... | 66    | mei_me     | DEDDBF979A |
| 8086:3b64 | 1179:ff1e | Intel      | 5 Series/3400 Series Chip... | 66    | mei_me     | C5883A9DA8 |
| 8086:8c3a | 103c:1993 | Intel      | 8 Series/C220 Series Chip... | 66    | mei_me     | 605367D5D4 |
| 8086:1c3a | 144d:c0b6 | Intel      | 6 Series/C200 Series Chip... | 65    | mei_me     | 574B61FC95 |
| 8086:3b64 | 144d:c581 | Intel      | 5 Series/3400 Series Chip... | 65    | mei_me     | 20D4A3A8F9 |
| 8086:8c3a | 1028:05be | Intel      | 8 Series/C220 Series Chip... | 65    | mei_me     | 6399CECB6F |
| 8086:9c3a | 1043:131d | Intel      | 8 Series HECI #0             | 64    | mei_me     | 13FF923546 |
| 8086:1e3a | 103c:17f6 | Intel      | 7 Series/C216 Chipset Fam... | 63    | mei_me     | D0705EF193 |
| 8086:9c3a | 1028:05cb | Intel      | 8 Series HECI #0             | 63    | mei_me     | EF82F4635D |
| 8086:9cba | 1025:098a | Intel      | Wildcat Point-LP MEI Cont... | 62    | mei_me     | D8A334E94C |
| 8086:9cba | 1028:062e | Intel      | Wildcat Point-LP MEI Cont... | 62    | mei_me     | 5F0CE579EC |
| 8086:1e3a | 104d:90b8 | Intel      | 7 Series/C216 Chipset Fam... | 61    | mei_me     | 77DF70A98A |

### Digitizer pen (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a0d0 | 8086:2097 | Intel      | Digitizer Pen                | 1     |            | 71848EA8F6 |

### Dma controller (eisa dma) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9ce0 | 8086:9ce0 | Intel      | Wildcat Point-LP Serial I... | 85    | dw_dmac... | C0ED6370C5 |
| 8086:9c60 |           | Intel      | 8 Series Low Power Sub-Sy... | 26    | dw_dmac... | C89BBD3B30 |
| 8086:2286 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 10    | dw_dmac... | ED6F77168B |
| 8086:22c0 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 10    | dw_dmac... | ED6F77168B |
| 8086:9c60 | 1025:0a11 | Intel      | 8 Series Low Power Sub-Sy... | 6     | dw_dmac... | 9DC2B77BCD |
| 8086:9c60 | 103c:21ed | Intel      | 8 Series Low Power Sub-Sy... | 5     | dw_dmac... | 9BB0BF9AC8 |
| 8086:0f40 | 1025:0939 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | C431BDD246 |
| 8086:0f40 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | 0994A3EEB3 |
| 8086:2286 | 1025:106c | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 09F6D20FE1 |
| 8086:2286 | 1025:1151 | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 7B7DB12037 |
| 8086:22c0 | 1025:106c | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 09F6D20FE1 |
| 8086:22c0 | 1025:1151 | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 7B7DB12037 |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15df | 1022:15df | AMD        | Family 17h (Models 10h-1f... | 670   | ccp        | F504E72617 |
| 1022:1537 | 1022:1537 | AMD        | Kabini/Mullins PSP-Platfo... | 358   | ccp        | C80A118E90 |
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 340   | mei_txe    | 1B5E908CFF |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 208   |            | 3EA595A278 |
| 1022:1537 | 17aa:3801 | AMD        | Kabini/Mullins PSP-Platfo... | 123   | ccp        | 779BFC3B47 |
| 1022:1578 | 103c:8330 | AMD        | Carrizo Platform Security... | 107   |            | 5671BA2F85 |
| 8086:0f18 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 93    | mei_txe    | EB9AAA55EA |
| 8086:0f18 | 17aa:3909 | Intel      | Atom Processor Z36xxx/Z37... | 86    | mei_txe    | BAC9935F0B |
| 8086:0f18 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 85    | mei_txe    | 421DCF0A2F |
| 1022:1578 | 103c:84ac | AMD        | Carrizo Platform Security... | 78    |            | D22A5E8410 |
| 1022:1578 | 1025:1192 | AMD        | Carrizo Platform Security... | 73    |            | CDC742CD03 |
| 1022:1578 | 17aa:3810 | AMD        | Carrizo Platform Security... | 68    |            | E57C2FB16D |
| 1022:15df | 19e5:3e19 | AMD        | Family 17h (Models 10h-1f... | 62    | ccp        | 9908BA82E9 |
| 1022:15df | 17aa:5081 | AMD        | Family 17h (Models 10h-1f... | 60    | ccp        | 6B6205BC5D |
| 1022:15df | 103c:84ae | AMD        | Family 17h (Models 10h-1f... | 56    | ccp        | BFB71F53EC |
| 8086:0f18 | 8086:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 56    | mei_txe    | 61200DD1C9 |
| 1022:15df | 1025:1366 | AMD        | Family 17h (Models 10h-1f... | 55    | ccp        | CF7AB2CA73 |
| 1022:15df | 17aa:507f | AMD        | Family 17h (Models 10h-1f... | 55    | ccp        | 441E3AA589 |
| 8086:2298 | 1025:1012 | Intel      | Atom/Celeron/Pentium Proc... | 54    | mei_txe    | 20016440FD |
| 8086:2298 | 1028:06ac | Intel      | Atom/Celeron/Pentium Proc... | 54    | mei_txe    | 1EA1C9F3FE |
| 1022:15df | 1025:134d | AMD        | Family 17h (Models 10h-1f... | 52    | ccp        | 479F0822FE |
| 8086:0f18 | 1043:161d | Intel      | Atom Processor Z36xxx/Z37... | 52    | mei_txe    | 1FA3E8B296 |
| 8086:0f18 | 103c:2213 | Intel      | Atom Processor Z36xxx/Z37... | 51    | mei_txe    | 1CE25A2590 |
| 1022:15df | 17aa:3818 | AMD        | Family 17h (Models 10h-1f... | 50    | ccp        | EA8B53C3DC |
| 1022:15df | 17aa:5124 | AMD        | Family 17h (Models 10h-1f... | 50    | ccp        | 4DE4650899 |
| 1022:15df | 17aa:380f | AMD        | Family 17h (Models 10h-1f... | 49    | ccp        | 6FE368312C |
| 1022:1578 | 17aa:380f | AMD        | Carrizo Platform Security... | 48    |            | 18D8EEC6A4 |
| 1022:15df | 17aa:381f | AMD        | Family 17h (Models 10h-1f... | 48    | ccp        | 9480BB8E99 |
| 8086:0f18 | 1297:2041 | Intel      | Atom Processor Z36xxx/Z37... | 47    | mei_txe    | 32D3859912 |
| 8086:2298 | 103c:832c | Intel      | Atom/Celeron/Pentium Proc... | 47    | mei_txe    | 618D37F6A5 |
| 1022:15df | 17aa:3811 | AMD        | Family 17h (Models 10h-1f... | 46    | ccp        | FCC7840D63 |
| 8086:2298 | 1043:10c0 | Intel      | Atom/Celeron/Pentium Proc... | 46    | mei_txe    | 0F79FB429B |
| 8086:0f18 | 1043:14dd | Intel      | Atom Processor Z36xxx/Z37... | 42    | mei_txe    | 6F97387DAC |
| 8086:2298 | 17aa:3808 | Intel      | Atom/Celeron/Pentium Proc... | 42    | mei_txe    | 9372D60118 |
| 1022:15df | 1025:1259 | AMD        | Family 17h (Models 10h-1f... | 37    | ccp        | 8DAB17C109 |
| 1022:1537 | 17aa:3808 | AMD        | Kabini/Mullins PSP-Platfo... | 36    | ccp        | 229B548B9A |
| 8086:0f18 | 17aa:3986 | Intel      | Atom Processor Z36xxx/Z37... | 36    | mei_txe    | 9025A3C7F9 |
| 1022:15df | 103c:8615 | AMD        | Family 17h (Models 10h-1f... | 35    | ccp        | 1FA0CB66B1 |
| 1022:15df | 17aa:3802 | AMD        | Family 17h (Models 10h-1f... | 35    | ccp        | E7FDA6091A |
| 1022:15df | 17aa:3810 | AMD        | Family 17h (Models 10h-1f... | 35    | ccp        | 93286A0D38 |
| 1022:15df | 17aa:3816 | AMD        | Family 17h (Models 10h-1f... | 35    | ccp        | 13D155653F |
| 1022:15df | 19e5:3e18 | AMD        | Family 17h (Models 10h-1f... | 35    | ccp        | 430907546B |
| 8086:2298 | 103c:81f1 | Intel      | Atom/Celeron/Pentium Proc... | 35    | mei_txe    | 0374CA0B61 |
| 8086:0f18 | 1025:0933 | Intel      | Atom Processor Z36xxx/Z37... | 34    | mei_txe    | FED9BA4C7D |
| 1022:15df | 103c:84e7 | AMD        | Family 17h (Models 10h-1f... | 33    | ccp        | D2AEC2F67A |
| 1022:15df | 103c:85ea | AMD        | Family 17h (Models 10h-1f... | 33    | ccp        | D03BDBF1DA |
| 1022:15df | 1d05:109f | AMD        | Family 17h (Models 10h-1f... | 33    | ccp        | 69510C22F1 |
| 1022:1578 | 17aa:3815 | AMD        | Carrizo Platform Security... | 32    |            | 27153360C7 |
| 1022:15df | 17aa:3809 | AMD        | Family 17h (Models 10h-1f... | 32    | ccp        | 008C187A8B |
| 8086:0f18 | 1179:f91b | Intel      | Atom Processor Z36xxx/Z37... | 31    | mei_txe    | 80080989FA |
| 1022:1537 | 1025:104b | AMD        | Kabini/Mullins PSP-Platfo... | 29    | ccp        | 6E75E7C288 |
| 1022:15df | 103c:86fd | AMD        | Family 17h (Models 10h-1f... | 29    | ccp        | 415E7E34D6 |
| 1022:15df | 17aa:5082 | AMD        | Family 17h (Models 10h-1f... | 29    | ccp        | 12FFAAEFB1 |
| 8086:2298 | 103c:80c5 | Intel      | Atom/Celeron/Pentium Proc... | 29    | mei_txe    | 3CC10CC5F1 |
| 1022:1578 | 17aa:380c | AMD        | Carrizo Platform Security... | 28    |            | AD6F771DA6 |
| 1022:15df | 1025:142b | AMD        | Family 17h (Models 10h-1f... | 28    | ccp        | 5DCA660F7E |
| 8086:0f18 | 1025:0936 | Intel      | Atom Processor Z36xxx/Z37... | 28    | mei_txe    | 05B439EB53 |
| 8086:0f18 | 103c:21de | Intel      | Atom Processor Z36xxx/Z37... | 28    | mei_txe    | B34D6D63D9 |
| 8086:0f18 | 1043:15bd | Intel      | Atom Processor Z36xxx/Z37... | 28    | mei_txe    | D8057F1C4D |
| 8086:2298 | 103c:813e | Intel      | Atom/Celeron/Pentium Proc... | 28    | mei_txe    | 71120B9356 |
| 1022:1537 | 1025:108a | AMD        | Kabini/Mullins PSP-Platfo... | 27    | ccp        | FDFA81C2E5 |
| 1022:15df | 17aa:380d | AMD        | Family 17h (Models 10h-1f... | 27    | ccp        | CB9D7D7035 |
| 1022:15df | 17aa:3817 | AMD        | Family 17h (Models 10h-1f... | 27    | ccp        | 99D22D0422 |
| 1022:15df | 17aa:507e | AMD        | Family 17h (Models 10h-1f... | 27    | ccp        | 31850CE796 |
| 8086:2298 | 1043:12e0 | Intel      | Atom/Celeron/Pentium Proc... | 27    | mei_txe    | 93F191DCA0 |
| 1022:1578 | 103c:8331 | AMD        | Carrizo Platform Security... | 26    |            | 30C73729A4 |
| 1022:15df | 1025:125c | AMD        | Family 17h (Models 10h-1f... | 26    | ccp        | FF512AC729 |
| 1022:15df | 103c:85b3 | AMD        | Family 17h (Models 10h-1f... | 26    | ccp        | 039DF57583 |
| 8086:2298 | 103c:82bd | Intel      | Atom/Celeron/Pentium Proc... | 26    | mei_txe    | AB155989AA |
| 8086:2298 | 1043:191d | Intel      | Atom/Celeron/Pentium Proc... | 26    | mei_txe    | A1B6970890 |
| 1022:1578 | 103c:8333 | AMD        | Carrizo Platform Security... | 25    |            | 8911FC397F |
| 1022:15df | 17aa:5125 | AMD        | Family 17h (Models 10h-1f... | 25    | ccp        | 452DD792F1 |
| 1022:15df | 1025:1461 | AMD        | Family 17h (Models 10h-1f... | 24    | ccp        | 8D643F3501 |
| 1022:1578 | 1025:109f | AMD        | Carrizo Platform Security... | 23    |            | 70037BDDCB |
| 1022:15df | 1025:134f | AMD        | Family 17h (Models 10h-1f... | 23    | ccp        | 3EC48C5388 |
| 8086:0f18 | 1043:14ed | Intel      | Atom Processor Z36xxx/Z37... | 23    | mei_txe    | BCA3C06314 |
| 1022:15df | 19e5:3e06 | AMD        | Family 17h (Models 10h-1f... | 22    | ccp        | 1797098345 |
| 8086:0f18 | 17aa:2224 | Intel      | Atom Processor Z36xxx/Z37... | 22    | mei_txe    | B1500A1319 |
| 8086:2298 | 1297:2063 | Intel      | Atom/Celeron/Pentium Proc... | 22    | mei_txe    | D6AD6F67A7 |
| 1022:1578 | 17aa:380b | AMD        | Carrizo Platform Security... | 21    |            | 161B42524B |
| 8086:0f18 | 1025:0905 | Intel      | Atom Processor Z36xxx/Z37... | 21    | mei_txe    | 99175F6D0D |
| 8086:2298 | 1043:10b0 | Intel      | Atom/Celeron/Pentium Proc... | 21    | mei_txe    | C323A8132A |
| 8086:2298 | 1043:1d5d | Intel      | Atom/Celeron/Pentium Proc... | 21    | mei_txe    | 1BD16BB71E |
| 1022:1578 | 103c:81f9 | AMD        | Carrizo Platform Security... | 20    |            | 2C2DFBF127 |
| 1022:1537 | 103c:82f6 | AMD        | Kabini/Mullins PSP-Platfo... | 19    | ccp        | AB87221BF7 |
| 1022:15df | 103c:85e0 | AMD        | Family 17h (Models 10h-1f... | 19    | ccp        | C740D1205B |
| 8086:0f18 | 1025:089d | Intel      | Atom Processor Z36xxx/Z37... | 19    | mei_txe    | A7AEA0A2DD |
| 8086:0f18 | 103c:2209 | Intel      | Atom Processor Z36xxx/Z37... | 19    | mei_txe    | 8AAB148F59 |
| 8086:2298 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 19    | mei_txe    | DB306FA1F7 |
| 8086:2298 | 1043:1cbd | Intel      | Atom/Celeron/Pentium Proc... | 19    | mei_txe    | C470382D2A |
| 1022:15df | 1025:1456 | AMD        | Family 17h (Models 10h-1f... | 18    | ccp        | 80CF3DC8E7 |
| 1022:15df | 19e5:3e14 | AMD        | Family 17h (Models 10h-1f... | 18    | ccp        | 2E6A9F05AC |
| 8086:0f18 | 1025:0939 | Intel      | Atom Processor Z36xxx/Z37... | 18    | mei_txe    | A62932FB2D |
| 1022:15df | 17aa:381c | AMD        | Family 17h (Models 10h-1f... | 17    | ccp        | F707B24713 |
| 8086:0f18 | 1558:5470 | Intel      | Atom Processor Z36xxx/Z37... | 17    | mei_txe    | 1ECF28A1C8 |
| 8086:2298 | 1028:074d | Intel      | Atom/Celeron/Pentium Proc... | 17    | mei_txe    | DF9CBA1F5C |
| 8086:0f18 | 1025:0845 | Intel      | Atom Processor Z36xxx/Z37... | 16    | mei_txe    | 5C34C6DC90 |
| 1022:1578 | 1028:087e | AMD        | Carrizo Platform Security... | 15    |            | 4B05B65D0E |
| 1022:1578 | 103c:84d0 | AMD        | Carrizo Platform Security... | 15    |            | C0651C40DC |
| 1022:15df | 17aa:506f | AMD        | Family 17h (Models 10h-1f... | 15    | ccp        | 37FD15B69E |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 11c1:5901 | 11c1:5900 | LSI        | FW643 [TrueFire] PCIe 139... | 369   | firewir... | F982A2F6CC |
| 1180:0832 | 17aa:20c7 | Ricoh      | R5C832 IEEE 1394 Controller  | 257   | firewir... | DB936567F0 |
| 1180:e832 | 17aa:2136 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 148   | firewir... | 4FF6DAE64C |
| 1180:e832 | 1028:040a | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 123   | firewir... | 576A6491F3 |
| 104c:803a | 1025:011f | Texas I... | PCIxx12 OHCI Compliant IE... | 122   | firewir... | 6A05B72968 |
| 1180:0832 | 1028:0233 | Ricoh      | R5C832 IEEE 1394 Controller  | 107   | firewir... | 2A4C5F6EEC |
| 11c1:5811 | 11c1:5811 | LSI        | FW322/323 [TrueFire] 1394... | 102   | firewir... | E31DDE7E74 |
| 197b:2380 | 103c:161c | JMicron... | IEEE 1394 Host Controller    | 96    | firewir... | 701E56A49F |
| 104c:803a | 1179:ff00 | Texas I... | PCIxx12 OHCI Compliant IE... | 92    | firewir... | 8E44C9EDAF |
| 1217:00f7 | 1028:01f9 | O2 Micro   | Firewire (IEEE 1394)         | 87    | firewir... | E271885D51 |
| 197b:2380 | 103c:179b | JMicron... | IEEE 1394 Host Controller    | 86    | firewir... | 7D39BC1331 |
| 1180:e832 | 17aa:21cf | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 79    | firewir... | C40BAA791F |
| 1180:0832 | 1028:022f | Ricoh      | R5C832 IEEE 1394 Controller  | 72    | firewir... | 06130B24C5 |
| 1180:e832 | 17aa:21f6 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 70    | firewir... | 88CEE1E822 |
| 1180:0832 | 103c:30cc | Ricoh      | R5C832 IEEE 1394 Controller  | 62    | firewir... | 4E93C68985 |
| 1217:00f7 | 1179:ff50 | O2 Micro   | Firewire (IEEE 1394)         | 55    | firewir... | FEB13460E8 |
| 1180:0832 | 103c:172a | Ricoh      | R5C832 IEEE 1394 Controller  | 54    | firewir... | 9635709179 |
| 1180:e832 | 17aa:21ce | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 47    | firewir... | 74547808D3 |
| 1217:00f7 | 1217:00f7 | O2 Micro   | Firewire (IEEE 1394)         | 47    | firewir... | 2AE9241025 |
| 1217:13f7 | 1028:0494 | O2 Micro   | 1394 OHCI Compliant Host ... | 46    | firewir... | E58B9D7EA5 |
| 1180:0832 | 1025:011e | Ricoh      | R5C832 IEEE 1394 Controller  | 45    | firewir... | 3C8537DFE3 |
| 1180:0832 | 103c:7008 | Ricoh      | R5C832 IEEE 1394 Controller  | 44    | firewir... | 383932E73B |
| 197b:2380 | 103c:3628 | JMicron... | IEEE 1394 Host Controller    | 43    | firewir... | DCE60F14E1 |
| 1180:0832 | 103c:30c0 | Ricoh      | R5C832 IEEE 1394 Controller  | 41    | firewir... | 4DEAD8CD75 |
| 1180:0832 | 103c:30cf | Ricoh      | R5C832 IEEE 1394 Controller  | 41    | firewir... | CB77A79EE8 |
| 1180:e832 | 1028:040b | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 41    | firewir... | 6902EB0F50 |
| 1180:0832 | 1028:024f | Ricoh      | R5C832 IEEE 1394 Controller  | 40    | firewir... | 3BDEE6855C |
| 1180:0832 | 1025:0121 | Ricoh      | R5C832 IEEE 1394 Controller  | 39    | firewir... | 5D933E19AC |
| 197b:2380 | 103c:1618 | JMicron... | IEEE 1394 Host Controller    | 37    | firewir... | EA1BD5E314 |
| 11c1:5811 | 103c:30dd | LSI        | FW322/323 [TrueFire] 1394... | 36    | firewir... | 65FBD3DEF4 |
| 1180:0832 | 1028:01bd | Ricoh      | R5C832 IEEE 1394 Controller  | 35    | firewir... | 3EB7729825 |
| 1180:0832 | 104d:9035 | Ricoh      | R5C832 IEEE 1394 Controller  | 35    | firewir... | 1A9761824E |
| 1180:e832 | 103c:146d | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 35    | firewir... | 523C397AB6 |
| 104c:803a | 103c:30a2 | Texas I... | PCIxx12 OHCI Compliant IE... | 33    | firewir... | 204F122174 |
| 104c:803a | 1179:ff10 | Texas I... | PCIxx12 OHCI Compliant IE... | 33    | firewir... | B6FB3D3EC3 |
| 1180:0832 | 103c:1521 | Ricoh      | R5C832 IEEE 1394 Controller  | 33    | firewir... | FFC46C9472 |
| 197b:2380 | 103c:1619 | JMicron... | IEEE 1394 Host Controller    | 33    | firewir... | 523614FEE6 |
| 197b:2380 | 103c:17a7 | JMicron... | IEEE 1394 Host Controller    | 33    | firewir... | A66A0DF735 |
| 197b:2380 | 103c:17ab | JMicron... | IEEE 1394 Host Controller    | 33    | firewir... | 2B341B7BF9 |
| 1180:0832 | 103c:30db | Ricoh      | R5C832 IEEE 1394 Controller  | 32    | firewir... | A4CEF366BC |
| 1217:11f7 | 1028:04a3 | O2 Micro   | OZ600 1394a-2000 Controller  | 32    | firewir... | EE6C9C38B0 |
| 1217:13f7 | 1028:049a | O2 Micro   | 1394 OHCI Compliant Host ... | 32    | firewir... | 33B9916878 |
| 1217:13f7 | 1028:049b | O2 Micro   | 1394 OHCI Compliant Host ... | 32    | firewir... | 989DD7D36F |
| 1180:0832 | 1025:0126 | Ricoh      | R5C832 IEEE 1394 Controller  | 31    | firewir... | AA6D721BF2 |
| 1180:0832 | 1028:024d | Ricoh      | R5C832 IEEE 1394 Controller  | 31    | firewir... | 98D088D90D |
| 1180:0832 | 103c:30bb | Ricoh      | R5C832 IEEE 1394 Controller  | 31    | firewir... | 5F6D9F025A |
| 1180:0832 | 1043:1877 | Ricoh      | R5C832 IEEE 1394 Controller  | 30    | firewir... | 139F010F51 |
| 104c:803a | 104d:9005 | Texas I... | PCIxx12 OHCI Compliant IE... | 29    | firewir... | BD472575F4 |
| 197b:2380 | 103c:161d | JMicron... | IEEE 1394 Host Controller    | 27    | firewir... | 06BC21DB81 |
| 197b:2380 | 103c:3603 | JMicron... | IEEE 1394 Host Controller    | 27    | firewir... | 14F176409D |
| 104c:803a | 104d:9015 | Texas I... | PCIxx12 OHCI Compliant IE... | 25    | firewir... | 9AC5C739FF |
| 104c:803a | 104d:902d | Texas I... | PCIxx12 OHCI Compliant IE... | 25    | firewir... | B97D7A8C66 |
| 1180:0832 | 1028:0263 | Ricoh      | R5C832 IEEE 1394 Controller  | 25    | firewir... | 679F6F3259 |
| 104c:803a | 1179:0001 | Texas I... | PCIxx12 OHCI Compliant IE... | 24    | firewir... | EA94C20118 |
| 197b:2380 | 103c:30f4 | JMicron... | IEEE 1394 Host Controller    | 23    | firewir... | E8E3CCB220 |
| 197b:2380 | 103c:3659 | JMicron... | IEEE 1394 Host Controller    | 23    | firewir... | 827D185513 |
| 1180:0832 | 1043:14e7 | Ricoh      | R5C832 IEEE 1394 Controller  | 22    | firewir... | 2494100ECB |
| 1180:0832 | 1179:ff1c | Ricoh      | R5C832 IEEE 1394 Controller  | 22    | firewir... | 8B7FBF3DE6 |
| 1180:0832 | 1179:ff1e | Ricoh      | R5C832 IEEE 1394 Controller  | 22    | firewir... | 37B42247F5 |
| 1180:0832 | 17aa:2109 | Ricoh      | R5C832 IEEE 1394 Controller  | 22    | firewir... | E6E9C572A0 |
| 1217:00f7 | 1028:01fe | O2 Micro   | Firewire (IEEE 1394)         | 22    | firewir... | 4D9D478FFC |
| 197b:2380 | 103c:179c | JMicron... | IEEE 1394 Host Controller    | 22    | firewir... | 687AED65CF |
| 104c:8025 |           | Texas I... | TSB82AA2 IEEE-1394b Link ... | 21    | firewir... | 52F24B3228 |
| 1180:0832 | 103c:30c5 | Ricoh      | R5C832 IEEE 1394 Controller  | 21    | firewir... | F11CC3529C |
| 1180:0832 | 1043:1317 | Ricoh      | R5C832 IEEE 1394 Controller  | 21    | firewir... | A4CF3B1E1D |
| 1180:e832 | 1028:0429 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 21    | firewir... | 5D8F94313F |
| 1180:0832 | 103c:30be | Ricoh      | R5C832 IEEE 1394 Controller  | 20    | firewir... | 5910FA85E5 |
| 1217:00f7 | 10cf:14d7 | O2 Micro   | Firewire (IEEE 1394)         | 20    | firewir... | F220F9AC45 |
| 197b:2380 | 103c:1631 | JMicron... | IEEE 1394 Host Controller    | 20    | firewir... | ADA2C0663B |
| 197b:2380 | 103c:176b | JMicron... | IEEE 1394 Host Controller    | 20    | firewir... | 1125997CC5 |
| 1180:0832 | 1043:1897 | Ricoh      | R5C832 IEEE 1394 Controller  | 19    | firewir... | 8ABF85E052 |
| 1180:e832 | 104d:9089 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 19    | firewir... | 5E0B431CB8 |
| 1217:00f7 | 10cf:143e | O2 Micro   | Firewire (IEEE 1394)         | 19    | firewir... | 3B7266D323 |
| 1180:0832 | 1028:02a0 | Ricoh      | R5C832 IEEE 1394 Controller  | 18    | firewir... | 53C61E21C4 |
| 1180:0832 | 17aa:3829 | Ricoh      | R5C832 IEEE 1394 Controller  | 18    | firewir... | 031CC16615 |
| 1217:13f7 | 1028:053e | O2 Micro   | 1394 OHCI Compliant Host ... | 18    | firewir... | 1D14E22FBD |
| 1180:0832 | 1028:01f2 | Ricoh      | R5C832 IEEE 1394 Controller  | 17    | firewir... | D115C79F7A |
| 1180:0832 | 103c:30cd | Ricoh      | R5C832 IEEE 1394 Controller  | 17    | firewir... | FD5BD80A7D |
| 1180:0832 | 103c:7007 | Ricoh      | R5C832 IEEE 1394 Controller  | 17    | firewir... | 6604EBCF44 |
| 1180:e832 | 104d:9069 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 17    | firewir... | 188765C8F8 |
| 197b:2380 | 103c:3624 | JMicron... | IEEE 1394 Host Controller    | 17    | firewir... | F04EBA21CE |
| 104c:803a | 103c:30aa | Texas I... | PCIxx12 OHCI Compliant IE... | 16    | firewir... | 8831D828D8 |
| 104c:803a | 104d:9016 | Texas I... | PCIxx12 OHCI Compliant IE... | 16    | firewir... | E17FE551FB |
| 1180:0832 | 1025:011d | Ricoh      | R5C832 IEEE 1394 Controller  | 16    | firewir... | 88218A10F4 |
| 1180:0832 | 104d:900e | Ricoh      | R5C832 IEEE 1394 Controller  | 16    | firewir... | F538E64507 |
| 1180:e832 | 104d:907a | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 16    | firewir... | 76B08BA6D3 |
| 11c1:5903 | 11c1:5900 | LSI        | FW533 [TrueFire] PCIe 139... | 16    | firewir... | CC0FA80E46 |
| 197b:2380 | 103c:162a | JMicron... | IEEE 1394 Host Controller    | 16    | firewir... | 7FC1A2DF02 |
| 1180:0832 | 1028:029a | Ricoh      | R5C832 IEEE 1394 Controller  | 15    | firewir... | BEFFD605B7 |
| 1180:0832 | 103c:30e7 | Ricoh      | R5C832 IEEE 1394 Controller  | 15    | firewir... | 889E5E50E0 |
| 1180:0832 | 104d:9045 | Ricoh      | R5C832 IEEE 1394 Controller  | 15    | firewir... | 2AB87A40CC |
| 1180:0832 | 10f7:8338 | Ricoh      | R5C832 IEEE 1394 Controller  | 15    | firewir... | 4502B92271 |
| 1180:e832 | 1028:040c | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 15    | firewir... | CF45F57A60 |
| 1180:e832 | 1028:0413 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 15    | firewir... | 8AF25501BB |
| 1217:11f7 | 1028:04a4 | O2 Micro   | OZ600 1394a-2000 Controller  | 15    | firewir... | 117E981EF3 |
| 197b:2380 | 103c:176c | JMicron... | IEEE 1394 Host Controller    | 15    | firewir... | 9B49622881 |
| 1180:0832 | 1028:01f1 | Ricoh      | R5C832 IEEE 1394 Controller  | 14    | firewir... | B032DCE890 |
| 1180:0832 | 1028:0228 | Ricoh      | R5C832 IEEE 1394 Controller  | 14    | firewir... | 08AA727FE5 |
| 1180:0832 | 1043:1517 | Ricoh      | R5C832 IEEE 1394 Controller  | 14    | firewir... | AFF3370C9E |
| 1180:0832 | 1043:1767 | Ricoh      | R5C832 IEEE 1394 Controller  | 14    | firewir... | 1356FE3FEA |

### Flash memory (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1524:0520 | 1025:0090 | ENE Tec... | FLASH memory: ENE Technol... | 55    |            | 4A0EE2EAA5 |
| 1524:0530 | 1025:0090 | ENE Tec... | ENE PCI Memory Stick Card... | 55    |            | 4A0EE2EAA5 |
| 1524:0551 | 1025:0090 | ENE Tec... | SD/MMC Card Reader Contro... | 55    | sdhci_pci  | 4A0EE2EAA5 |
| 1524:0551 | 1025:009f | ENE Tec... | SD/MMC Card Reader Contro... | 39    | sdhci_pci  | D38F5B09D2 |
| 1524:0520 | 1025:009f | ENE Tec... | FLASH memory: ENE Technol... | 38    |            | D38F5B09D2 |
| 1524:0530 | 1025:009f | ENE Tec... | ENE PCI Memory Stick Card... | 38    |            | D38F5B09D2 |
| 1524:0720 | 1025:012e | ENE Tec... | Memory Stick Card Reader ... | 19    |            | 6EAAA7BA4F |
| 1524:0730 | 1025:012e | ENE Tec... | ENE PCI Memory Stick Card... | 19    |            | 6EAAA7BA4F |
| 1524:0751 | 1025:012e | ENE Tec... | ENE PCI Secure Digital / ... | 19    | sdhci_pci  | 6EAAA7BA4F |
| 1524:0520 | 1025:010f | ENE Tec... | FLASH memory: ENE Technol... | 16    |            | A9D5FB836A |
| 1524:0530 | 1025:010f | ENE Tec... | ENE PCI Memory Stick Card... | 16    |            | A9D5FB836A |
| 1524:0551 | 1025:010f | ENE Tec... | SD/MMC Card Reader Contro... | 16    | sdhci_pci  | A9D5FB836A |
| 1524:0530 | 14c0:0020 | ENE Tec... | ENE PCI Memory Stick Card... | 10    |            | D1D8A50709 |
| 1524:0530 | 1734:10c1 | ENE Tec... | ENE PCI Memory Stick Card... | 10    |            | 37D02AD16C |
| 1524:0551 | 14c0:0020 | ENE Tec... | SD/MMC Card Reader Contro... | 10    | sdhci_pci  | D1D8A50709 |
| 1524:0551 | 1734:10c1 | ENE Tec... | SD/MMC Card Reader Contro... | 10    | sdhci_pci  | 37D02AD16C |
| 1524:0730 | 1558:5409 | ENE Tec... | ENE PCI Memory Stick Card... | 6     |            | 00EBCAC258 |
| 1524:0751 | 1558:5409 | ENE Tec... | ENE PCI Secure Digital / ... | 6     | sdhci_pci  | 00EBCAC258 |
| 1524:0730 | 1558:0801 | ENE Tec... | ENE PCI Memory Stick Card... | 5     |            | BF5F7A5F0A |
| 1524:0751 | 1558:0801 | ENE Tec... | ENE PCI Secure Digital / ... | 5     | sdhci_pci  | BF5F7A5F0A |
| 1524:0520 | 1179:ff01 | ENE Tec... | FLASH memory: ENE Technol... | 4     |            | 89C7F0F25E |
| 1524:0530 | 1179:ff01 | ENE Tec... | ENE PCI Memory Stick Card... | 4     |            | 89C7F0F25E |
| 1524:0551 | 1179:ff02 | ENE Tec... | SD/MMC Card Reader Contro... | 4     | sdhci_pci  | 89C7F0F25E |
| 1524:0720 | 1025:011b | ENE Tec... | Memory Stick Card Reader ... | 4     |            | CD287A7C40 |
| 1524:0730 | 1025:011b | ENE Tec... | ENE PCI Memory Stick Card... | 4     |            | CD287A7C40 |
| 1524:0751 | 1025:011b | ENE Tec... | ENE PCI Secure Digital / ... | 4     | sdhci_pci  | CD287A7C40 |
| 1106:9530 | 17aa:3891 | VIA Tec... | VX800/820/900 Series Secu... | 3     | via_sdmmc  | 4762847735 |
| 1524:0720 | 1462:2fb3 | ENE Tec... | Memory Stick Card Reader ... | 3     |            | 5604F2B979 |
| 1524:0730 | 1462:2fb3 | ENE Tec... | ENE PCI Memory Stick Card... | 3     |            | 5604F2B979 |
| 1524:0730 | 1558:0669 | ENE Tec... | ENE PCI Memory Stick Card... | 3     |            | 66E0793D5B |
| 1524:0730 | 1558:0722 | ENE Tec... | ENE PCI Memory Stick Card... | 3     |            | 019E901528 |
| 1524:0730 | 1558:0802 | ENE Tec... | ENE PCI Memory Stick Card... | 3     |            | 44B42FE693 |
| 1524:0751 | 1462:2fb3 | ENE Tec... | ENE PCI Secure Digital / ... | 3     | sdhci_pci  | 5604F2B979 |
| 1524:0751 | 1558:0669 | ENE Tec... | ENE PCI Secure Digital / ... | 3     | sdhci_pci  | 66E0793D5B |
| 1524:0751 | 1558:0722 | ENE Tec... | ENE PCI Secure Digital / ... | 3     | sdhci_pci  | 019E901528 |
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
| 1524:0730 | 1558:0721 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | 4F4A5860A1 |
| 1524:0751 | 1025:012a | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | C95503E7D2 |
| 1524:0751 | 1558:0573 | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | 95780C2963 |
| 1524:0751 | 1558:0664 | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | 51E2E84C28 |
| 1524:0751 | 1558:0668 | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | 41C9811E8B |
| 1524:0751 | 1558:0721 | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | 4F4A5860A1 |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1577 | 1022:1577 | AMD        | Family 15h (Models 60h-6f... | 361   |            | 3EA595A278 |
| 1022:1577 | 103c:8331 | AMD        | Family 15h (Models 60h-6f... | 26    |            | 30C73729A4 |
| 1022:1423 | 1022:1423 | AMD        | Family 15h (Models 30h-3f... | 25    |            | 5DDDECA3E8 |
| 1022:1577 | 103c:81fa | AMD        | Family 15h (Models 60h-6f... | 13    |            | E11B01BA52 |
| 1022:1451 | 1022:1451 | AMD        | Family 17h (Models 00h-0f... | 12    |            | B79E897508 |
| 1022:1423 | 103c:812f | AMD        | Family 15h (Models 30h-3f... | 7     |            | 59A4CFC209 |
| 1022:1577 | 103c:80b5 | AMD        | Family 15h (Models 60h-6f... | 7     |            | 9193175B26 |
| 1022:1577 | 103c:80b6 | AMD        | Family 15h (Models 60h-6f... | 2     |            | BEA3C73273 |
| 1022:1577 | 103c:8355 | AMD        | Family 15h (Models 60h-6f... | 2     |            | D6F5348EC7 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 319   | i915       | 1B5E908CFF |
| 8086:0046 | 17aa:215a | Intel      | Core Processor Integrated... | 195   | i915       | D86D3E8984 |
| 8086:2a42 | 17aa:20e4 | Intel      | Mobile 4 Series Chipset I... | 187   | i915       | DB936567F0 |
| 8086:2a43 | 17aa:20e4 | Intel      | Mobile 4 Series Chipset I... | 187   |            | DB936567F0 |
| 8086:0166 | 17aa:21f3 | Intel      | 3rd Gen Core processor Gr... | 141   | i915       | C9503690D6 |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics 500              | 139   | i915       | 71A92492E3 |
| 8086:a011 | 1043:83ac | Intel      | Atom Processor D4xx/D5xx/... | 139   | i915       | 2117F02A4F |
| 8086:a012 | 1043:83ac | Intel      | Atom Processor D4xx/D5xx/... | 139   |            | 2117F02A4F |
| 8086:0166 | 17aa:21fa | Intel      | 3rd Gen Core processor Gr... | 133   | i915       | 50D562CAB5 |
| 8086:2a42 | 1043:1862 | Intel      | Mobile 4 Series Chipset I... | 121   | i915       | 498362846A |
| 8086:2a43 | 1043:1862 | Intel      | Mobile 4 Series Chipset I... | 121   |            | 498362846A |
| 8086:3e9b | 1025:1331 | Intel      | CoffeeLake-H GT2 [UHD Gra... | 119   | i915       | 38688703F4 |
| 8086:0166 | 17aa:3977 | Intel      | 3rd Gen Core processor Gr... | 117   | i915       | 2ACA6CD805 |
| 8086:0126 | 17aa:21ce | Intel      | 2nd Generation Core Proce... | 113   | i915       | 74547808D3 |
| 8086:3e9b | 1028:0905 | Intel      | CoffeeLake-H GT2 [UHD Gra... | 113   | i915       | 9CDE952049 |
| 8086:0166 | 1028:0534 | Intel      | 3rd Gen Core processor Gr... | 109   | i915       | 98420A7D92 |
| 8086:0a16 | 17aa:220c | Intel      | Haswell-ULT Integrated Gr... | 108   | i915       | 4C600416F9 |
| 1002:98e4 | 103c:8330 | AMD        | Stoney [Radeon R2/R3/R4/R... | 107   | amdgpu     | 5671BA2F85 |
| 8086:2a42 | 17aa:3a02 | Intel      | Mobile 4 Series Chipset I... | 107   | i915       | 1BBEC614AA |
| 8086:2a43 | 17aa:3a02 | Intel      | Mobile 4 Series Chipset I... | 107   |            | 1BBEC614AA |
| 10de:1f91 | 1028:0905 | Nvidia     | TU117M [GeForce GTX 1650 ... | 106   | nvidia     | 9CDE952049 |
| 8086:0106 | 1025:0649 | Intel      | 2nd Generation Core Proce... | 105   | i915       | ACE8491DE1 |
| 8086:0126 | 1028:0493 | Intel      | 2nd Generation Core Proce... | 105   | i915       | 33617DD1A8 |
| 8086:3185 | 1043:1261 | Intel      | GeminiLake [UHD Graphics ... | 105   | i915       | 170B220F5B |
| 10de:1f91 | 1025:1332 | Nvidia     | TU117M [GeForce GTX 1650 ... | 104   | nvidia     | 38688703F4 |
| 8086:0116 | 1025:0504 | Intel      | 2nd Generation Core Proce... | 104   | i915       | B420F25ED4 |
| 8086:0a16 | 17aa:3978 | Intel      | Haswell-ULT Integrated Gr... | 104   | i915       | 93B4F5B14E |
| 8086:a011 | 1025:0349 | Intel      | Atom Processor D4xx/D5xx/... | 102   | i915       | DA7BA5D53F |
| 8086:a012 | 1025:0349 | Intel      | Atom Processor D4xx/D5xx/... | 102   |            | DA7BA5D53F |
| 8086:0126 | 17aa:21da | Intel      | 2nd Generation Core Proce... | 100   | i915       | 660A6B9E20 |
| 8086:0a16 | 103c:198f | Intel      | Haswell-ULT Integrated Gr... | 99    | i915       | 6573923D55 |
| 8086:2a02 | 17aa:20b5 | Intel      | Mobile GM965/GL960 Integr... | 99    | i915       | E1B3B6E090 |
| 8086:2a03 | 17aa:20b5 | Intel      | Mobile GM965/GL960 Integr... | 99    |            | E1B3B6E090 |
| 8086:3e9b | 1028:087c | Intel      | CoffeeLake-H GT2 [UHD Gra... | 98    | i915       | 31A6F21CCD |
| 8086:2a02 | 1025:011f | Intel      | Mobile GM965/GL960 Integr... | 96    | i915       | 2DA2F6A795 |
| 8086:2a03 | 1025:011f | Intel      | Mobile GM965/GL960 Integr... | 96    |            | 2DA2F6A795 |
| 8086:3ea0 | 103c:8549 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 95    | i915       | 9A264DBCB2 |
| 8086:5917 | 1028:0810 | Intel      | UHD Graphics 620             | 95    | i915       | 2FD333BC52 |
| 8086:0166 | 1025:0647 | Intel      | 3rd Gen Core processor Gr... | 94    | i915       | A5268098B2 |
| 8086:1916 | 103c:8079 | Intel      | Skylake GT2 [HD Graphics ... | 94    | i915       | 0FA8058EEB |
| 8086:0a16 | 1025:0866 | Intel      | Haswell-ULT Integrated Gr... | 92    | i915       | 58B4832D53 |
| 8086:2a42 | 1028:02aa | Intel      | Mobile 4 Series Chipset I... | 92    | i915       | F0D0F92FD9 |
| 8086:2a43 | 1028:02aa | Intel      | Mobile 4 Series Chipset I... | 92    |            | F0D0F92FD9 |
| 10de:1c8c | 1028:087c | Nvidia     | GP107M [GeForce GTX 1050 ... | 91    | nvidia     | 31A6F21CCD |
| 8086:0166 | 1043:124d | Intel      | 3rd Gen Core processor Gr... | 91    | i915       | 08930695BC |
| 8086:0166 | 106b:00fa | Intel      | 3rd Gen Core processor Gr... | 90    | i915       | D82057AFA6 |
| 8086:0f31 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 89    | i915       | EB9AAA55EA |
| 8086:0046 | 1028:040a | Intel      | Core Processor Integrated... | 87    | i915       | 7E35C63842 |
| 8086:0f31 | 17aa:3909 | Intel      | Atom Processor Z36xxx/Z37... | 86    | i915       | BAC9935F0B |
| 8086:0166 | 1025:064b | Intel      | 3rd Gen Core processor Gr... | 85    | i915       | B732F94275 |
| 8086:5917 | 1028:07e6 | Intel      | UHD Graphics 620             | 83    | i915       | C2E884F793 |
| 8086:3ea0 | 1028:08af | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 82    | i915       | 80857F497B |
| 8086:0156 | 17aa:3977 | Intel      | 3rd Gen Core processor Gr... | 81    | i915       | 91CF490677 |
| 8086:0126 | 106b:00db | Intel      | 2nd Generation Core Proce... | 80    | i915       | A53D0DE98A |
| 1002:98e4 | 103c:84ac | AMD        | Stoney [Radeon R2/R3/R4/R... | 78    | amdgpu     | D22A5E8410 |
| 8086:9b41 | 17aa:5079 | Intel      | CometLake-U GT2 [UHD Grap... | 78    | i915       | 0BC4073D23 |
| 8086:0416 | 17aa:220e | Intel      | 4th Gen Core Processor In... | 77    | i915       | 4EC9EAAC2F |
| 8086:591b | 1028:07be | Intel      | HD Graphics 630              | 76    | i915       | 6EE00932DC |
| 1002:15d8 | 1043:18f1 | AMD        | Picasso                      | 75    | amdgpu     | D8A3297AB9 |
| 8086:2a02 | 1028:022f | Intel      | Mobile GM965/GL960 Integr... | 74    | i915       | 06130B24C5 |
| 8086:2a03 | 1028:022f | Intel      | Mobile GM965/GL960 Integr... | 74    |            | 06130B24C5 |
| 8086:3e9b | 1025:1264 | Intel      | CoffeeLake-H GT2 [UHD Gra... | 74    | i915       | 9971E42809 |
| 1002:98e4 | 1025:1192 | AMD        | Stoney [Radeon R2/R3/R4/R... | 73    | amdgpu     | CDC742CD03 |
| 10de:1c8d | 1028:07be | Nvidia     | GP107M [GeForce GTX 1050 ... | 73    | nvidia     | 6EE00932DC |
| 8086:0166 | 103c:179b | Intel      | 3rd Gen Core processor Gr... | 73    | i915       | 7D39BC1331 |
| 8086:0416 | 17aa:3978 | Intel      | 4th Gen Core Processor In... | 73    | i915       | CC68265730 |
| 8086:0a16 | 17aa:2214 | Intel      | Haswell-ULT Integrated Gr... | 73    | i915       | F100B7CDB9 |
| 8086:1616 | 103c:2216 | Intel      | HD Graphics 5500             | 73    | i915       | 304747E4C6 |
| 8086:5917 | 17aa:225c | Intel      | UHD Graphics 620             | 73    | i915       | C33E7CED42 |
| 8086:0116 | 1043:1682 | Intel      | 2nd Generation Core Proce... | 72    | i915       | 7196DE2988 |
| 8086:3ea0 | 17aa:2292 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 72    | i915       | FBF4582983 |
| 8086:0a16 | 1028:0651 | Intel      | Haswell-ULT Integrated Gr... | 71    | i915       | E1A816CC42 |
| 8086:2a02 | 1028:01f9 | Intel      | Mobile GM965/GL960 Integr... | 71    | i915       | E271885D51 |
| 8086:2a03 | 1028:01f9 | Intel      | Mobile GM965/GL960 Integr... | 71    |            | E271885D51 |
| 8086:22b1 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 70    | i915       | CEDCA78B3A |
| 1002:6900 | 1028:0810 | AMD        | Topaz XT [Radeon R7 M260/... | 69    | amdgpu     | 2FD333BC52 |
| 8086:0f31 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 69    | i915       | 3C21016B82 |
| 8086:1616 | 17aa:2226 | Intel      | HD Graphics 5500             | 69    | i915       | A5D677976F |
| 8086:5916 | 1025:1094 | Intel      | HD Graphics 620              | 69    | i915       | 9756CE58FC |
| 1002:68e0 | 1043:1bf2 | AMD        | Park [Mobility Radeon HD ... | 68    | radeon     | 11F1CDC49A |
| 8086:0106 | 17aa:3975 | Intel      | 2nd Generation Core Proce... | 68    | i915       | FE1E9576C6 |
| 8086:0166 | 17aa:21f5 | Intel      | 3rd Gen Core processor Gr... | 68    | i915       | 88CEE1E822 |
| 8086:0126 | 103c:161c | Intel      | 2nd Generation Core Proce... | 67    | i915       | 37F8994BEF |
| 8086:2a02 | 106b:00a1 | Intel      | Mobile GM965/GL960 Integr... | 67    | i915       | E31DDE7E74 |
| 8086:2a03 | 106b:00a1 | Intel      | Mobile GM965/GL960 Integr... | 67    |            | E31DDE7E74 |
| 8086:2a42 | 1028:0233 | Intel      | Mobile 4 Series Chipset I... | 67    | i915       | 2A4C5F6EEC |
| 8086:2a43 | 1028:0233 | Intel      | Mobile 4 Series Chipset I... | 67    |            | 2A4C5F6EEC |
| 8086:5916 | 1028:078b | Intel      | HD Graphics 620              | 67    | i915       | 4F60F64204 |
| 8086:0a16 | 1028:05cb | Intel      | Haswell-ULT Integrated Gr... | 66    | i915       | EF82F4635D |
| 8086:0be1 | 1043:84a9 | Intel      | Atom Processor D2xxx/N2xx... | 66    | gma500_gfx | 92CF086368 |
| 10de:0df5 | 1028:04ca | Nvidia     | GF108M [GeForce GT 525M]     | 65    | nouveau    | AAB4398A6B |
| 8086:0116 | 1028:04ca | Intel      | 2nd Generation Core Proce... | 65    | i915       | C1FF514270 |
| 8086:0416 | 1028:05be | Intel      | 4th Gen Core Processor In... | 65    | i915       | 6399CECB6F |
| 8086:0416 | 103c:1993 | Intel      | 4th Gen Core Processor In... | 65    | i915       | 605367D5D4 |
| 8086:0166 | 17aa:5003 | Intel      | 3rd Gen Core processor Gr... | 64    | i915       | F483FD5A3B |
| 8086:0f31 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 64    | i915       | E789EA6881 |
| 8086:0a16 | 1025:0775 | Intel      | Haswell-ULT Integrated Gr... | 63    | i915       | 43B1A35EA2 |
| 8086:5916 | 1025:1193 | Intel      | HD Graphics 620              | 63    | i915       | E922639FF6 |
| 8086:a011 | 144d:c072 | Intel      | Atom Processor D4xx/D5xx/... | 63    | i915       | D4548D357F |
| 8086:a012 | 144d:c072 | Intel      | Atom Processor D4xx/D5xx/... | 63    |            | D4548D357F |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 904   |            | F504E72617 |
| 1022:1631 | 1022:1631 | AMD        | Renoir IOMMU                 | 268   |            | DB4A212405 |
| 1022:1577 | 103c:8330 | AMD        | Family 15h (Models 60h-6f... | 107   |            | 5671BA2F85 |
| 1022:1577 | 103c:84ac | AMD        | Family 15h (Models 60h-6f... | 78    |            | D22A5E8410 |
| 1022:1577 | 1025:1192 | AMD        | Family 15h (Models 60h-6f... | 72    |            | CDC742CD03 |
| 1022:1631 | 17aa:5081 | AMD        | Renoir IOMMU                 | 60    |            | 6B6205BC5D |
| 1022:1631 | 17aa:3803 | AMD        | Renoir IOMMU                 | 59    |            | EA8B53C3DC |
| 1022:15d1 | 103c:84ae | AMD        | Raven/Raven2 IOMMU           | 56    |            | BFB71F53EC |
| 1022:15d1 | 1025:1366 | AMD        | Raven/Raven2 IOMMU           | 55    |            | CF7AB2CA73 |
| 1022:1631 | 17aa:507f | AMD        | Renoir IOMMU                 | 55    |            | 441E3AA589 |
| 1022:15d1 | 1025:134d | AMD        | Raven/Raven2 IOMMU           | 49    |            | 479F0822FE |
| 1022:15d1 | 17aa:380a | AMD        | Raven/Raven2 IOMMU           | 49    |            | 6FE368312C |
| 1022:1577 | 17aa:380e | AMD        | Family 15h (Models 60h-6f... | 48    |            | 18D8EEC6A4 |
| 1022:15d1 | 1025:1259 | AMD        | Raven/Raven2 IOMMU           | 35    |            | 8DAB17C109 |
| 1022:15d1 | 103c:8615 | AMD        | Raven/Raven2 IOMMU           | 35    |            | 1FA0CB66B1 |
| 1022:15d1 | 17aa:380b | AMD        | Raven/Raven2 IOMMU           | 35    |            | 93286A0D38 |
| 1022:15d1 | 103c:84e7 | AMD        | Raven/Raven2 IOMMU           | 33    |            | D2AEC2F67A |
| 1022:15d1 | 103c:85ea | AMD        | Raven/Raven2 IOMMU           | 33    |            | D03BDBF1DA |
| 1022:1631 | 1d05:109f | AMD        | Renoir IOMMU                 | 33    |            | 69510C22F1 |
| 1022:15d1 | 17aa:3804 | AMD        | Raven/Raven2 IOMMU           | 32    |            | 008C187A8B |
| 1022:15d1 | 103c:86fd | AMD        | Raven/Raven2 IOMMU           | 29    |            | 415E7E34D6 |
| 1022:1631 | 17aa:5082 | AMD        | Renoir IOMMU                 | 29    |            | 12FFAAEFB1 |
| 1022:1631 | 1025:142b | AMD        | Renoir IOMMU                 | 28    |            | 5DCA660F7E |
| 1022:1631 | 17aa:380a | AMD        | Renoir IOMMU                 | 27    |            | 99D22D0422 |
| 1022:1631 | 17aa:507e | AMD        | Renoir IOMMU                 | 27    |            | 31850CE796 |
| 1022:15d1 | 103c:85b3 | AMD        | Raven/Raven2 IOMMU           | 26    |            | 039DF57583 |
| 1022:15d1 | 1025:125c | AMD        | Raven/Raven2 IOMMU           | 25    |            | FF512AC729 |
| 1022:1631 | 1025:1461 | AMD        | Renoir IOMMU                 | 24    |            | 8D643F3501 |
| 1022:1577 | 1025:109f | AMD        | Family 15h (Models 60h-6f... | 23    |            | 70037BDDCB |
| 1022:15d1 | 1025:134f | AMD        | Raven/Raven2 IOMMU           | 23    |            | 3EC48C5388 |
| 1022:1577 | 103c:81f9 | AMD        | Family 15h (Models 60h-6f... | 20    |            | 2C2DFBF127 |
| 1022:15d1 | 103c:85e0 | AMD        | Raven/Raven2 IOMMU           | 19    |            | C740D1205B |
| 1022:15d1 | 1025:1456 | AMD        | Raven/Raven2 IOMMU           | 16    |            | 80CF3DC8E7 |
| 1022:1577 | 1028:087e | AMD        | Family 15h (Models 60h-6f... | 15    |            | 4B05B65D0E |
| 1022:1577 | 103c:84d0 | AMD        | Family 15h (Models 60h-6f... | 15    |            | C0651C40DC |
| 1022:1631 | 17aa:3808 | AMD        | Renoir IOMMU                 | 15    |            | CB9D7D7035 |
| 1022:1631 | 1d05:1100 | AMD        | Renoir IOMMU                 | 15    |            | 60D8A6B854 |
| 1022:1631 | 1e83:3e33 | AMD        | Renoir IOMMU                 | 14    |            | 3F2AA0EB97 |
| 1022:15d1 | 1028:0812 | AMD        | Raven/Raven2 IOMMU           | 13    |            | E558F0ABB0 |
| 1022:1631 | 1028:09f5 | AMD        | Renoir IOMMU                 | 13    |            | 706D306B5E |
| 1022:1481 | 1558:50f0 | AMD        | Starship/Matisse IOMMU       | 12    |            | B34A66FE8D |
| 1022:1577 | 103c:84a0 | AMD        | Family 15h (Models 60h-6f... | 12    |            | D7EB86C002 |
| 1022:1577 | 103c:85bb | AMD        | Family 15h (Models 60h-6f... | 12    |            | 9948FD64F4 |
| 1022:1577 | 17aa:380d | AMD        | Family 15h (Models 60h-6f... | 12    |            | 4CCF4659D4 |
| 1022:15d1 | 103c:84d2 | AMD        | Raven/Raven2 IOMMU           | 12    |            | C66066FF6B |
| 1022:1631 | 17aa:380d | AMD        | Renoir IOMMU                 | 12    |            | 51C5D13230 |
| 1022:1577 | 1028:0769 | AMD        | Family 15h (Models 60h-6f... | 11    |            | 8F75EDA1DE |
| 1022:1577 | 103c:8333 | AMD        | Family 15h (Models 60h-6f... | 11    |            | 8911FC397F |
| 1022:1577 | 103c:8345 | AMD        | Family 15h (Models 60h-6f... | 11    |            | B2207B19C0 |
| 1022:15d1 | 103c:879e | AMD        | Raven/Raven2 IOMMU           | 11    |            | 61A5B2ED1E |
| 1022:1577 | 1025:1099 | AMD        | Family 15h (Models 60h-6f... | 10    |            | 16D7B82A2C |
| 1022:1577 | 103c:8324 | AMD        | Family 15h (Models 60h-6f... | 10    |            | 18175DDCCD |
| 1022:15d1 | 103c:86d5 | AMD        | Raven/Raven2 IOMMU           | 10    |            | 209887E993 |
| 1022:15d1 | 17aa:3809 | AMD        | Raven/Raven2 IOMMU           | 10    |            | 557EF5A2AE |
| 1022:15d1 | 1025:1233 | AMD        | Raven/Raven2 IOMMU           | 9     |            | 6ADFA9E5CD |
| 1022:1631 | 103c:8786 | AMD        | Renoir IOMMU                 | 9     |            | 3F4BBD14BA |
| 1022:1631 | 103c:87b1 | AMD        | Renoir IOMMU                 | 9     |            | E1CF7F4599 |
| 1022:1631 | 1d72:1953 | AMD        | Renoir IOMMU                 | 9     |            | 7139D19A98 |
| 1022:1577 | 1025:1362 | AMD        | Family 15h (Models 60h-6f... | 8     |            | 6DB45D962D |
| 1022:1577 | 103c:84ad | AMD        | Family 15h (Models 60h-6f... | 8     |            | EB0E17A039 |
| 1022:15d1 | 1028:08d7 | AMD        | Raven/Raven2 IOMMU           | 8     |            | DB16E945BB |
| 1022:15d1 | 103c:8706 | AMD        | Raven/Raven2 IOMMU           | 8     |            | F0EEC3E2AA |
| 1022:1577 | 1025:1087 | AMD        | Family 15h (Models 60h-6f... | 7     |            | 34AA3DCA40 |
| 1022:1577 | 103c:80af | AMD        | Family 15h (Models 60h-6f... | 7     |            | 2D0FB807ED |
| 1022:15d1 | 103c:86d4 | AMD        | Raven/Raven2 IOMMU           | 7     |            | 0C1B37ACD2 |
| 1022:1631 | 1025:1455 | AMD        | Renoir IOMMU                 | 7     |            | C118461E82 |
| 1022:1631 | 103c:87b2 | AMD        | Renoir IOMMU                 | 7     |            | 4A21E62A29 |
| 1022:1631 | 1558:a500 | AMD        | Renoir IOMMU                 | 7     |            | 052ED9C216 |
| 1022:1631 | 1d72:1951 | AMD        | Renoir IOMMU                 | 7     |            | 8700A7EAED |
| 1022:1577 | 1025:1201 | AMD        | Family 15h (Models 60h-6f... | 6     |            | 7302B67E75 |
| 1022:1577 | 103c:80b0 | AMD        | Family 15h (Models 60h-6f... | 6     |            | FC5CE69792 |
| 1022:15d1 | 17aa:3803 | AMD        | Raven/Raven2 IOMMU           | 6     |            | D79109BA72 |
| 1022:1631 | 103c:87cf | AMD        | Renoir IOMMU                 | 6     |            | C686837768 |
| 1022:1451 | 1025:1246 | AMD        | Family 17h (Models 00h-0f... | 5     |            | 03FACC3040 |
| 1022:1577 | 103c:81fe | AMD        | Family 15h (Models 60h-6f... | 5     |            | 775D500103 |
| 1022:1577 | 17aa:3803 | AMD        | Family 15h (Models 60h-6f... | 5     |            | 7A59304F76 |
| 1022:15d1 | 103c:84a2 | AMD        | Raven/Raven2 IOMMU           | 5     |            | 220E290FCB |
| 1022:15d1 | 103c:87b7 | AMD        | Raven/Raven2 IOMMU           | 5     |            | A2A6C6FD1A |
| 1022:15d1 | 17aa:3802 | AMD        | Raven/Raven2 IOMMU           | 5     |            | 73AAD972AD |
| 1022:1631 | 1028:0a1e | AMD        | Renoir IOMMU                 | 5     |            | 04E0880C54 |
| 1022:1631 | 103c:8787 | AMD        | Renoir IOMMU                 | 5     |            | 3AE2F83C9F |
| 1022:1631 | 1043:1602 | AMD        | Renoir IOMMU                 | 5     |            | F6856776E4 |
| 1022:1577 | 1028:087f | AMD        | Family 15h (Models 60h-6f... | 4     |            | 84FA76EB2F |
| 1022:1577 | 103c:863c | AMD        | Family 15h (Models 60h-6f... | 4     |            | 2947241FEC |
| 1022:15d1 | 103c:86d6 | AMD        | Raven/Raven2 IOMMU           | 4     |            | 220B969C6D |
| 1022:1631 | 103c:87c5 | AMD        | Renoir IOMMU                 | 4     |            | 4792D19DD2 |
| 1022:1631 | 17aa:380b | AMD        | Renoir IOMMU                 | 4     |            | F2FBB53B7F |
| 1022:1577 | 1028:076b | AMD        | Family 15h (Models 60h-6f... | 3     |            | C9118344E3 |
| 1022:1577 | 103c:8221 | AMD        | Family 15h (Models 60h-6f... | 3     |            | 07EB4784FA |
| 1022:1577 | 103c:8346 | AMD        | Family 15h (Models 60h-6f... | 3     |            | 329A04378C |
| 1022:1577 | 103c:8354 | AMD        | Family 15h (Models 60h-6f... | 3     |            | AF18FA04C3 |
| 1022:1577 | 103c:8357 | AMD        | Family 15h (Models 60h-6f... | 3     |            | 9BB274BF17 |
| 1022:1577 | 103c:84d1 | AMD        | Family 15h (Models 60h-6f... | 3     |            | 413068EDAA |
| 1022:1577 | 103c:84e5 | AMD        | Family 15h (Models 60h-6f... | 3     |            | 9087960124 |
| 1022:1577 | 103c:867a | AMD        | Family 15h (Models 60h-6f... | 3     |            | 9F62224228 |
| 1022:15d1 | 1025:1378 | AMD        | Raven/Raven2 IOMMU           | 3     |            | DA566F34DD |
| 1022:15d1 | 1028:0a12 | AMD        | Raven/Raven2 IOMMU           | 3     |            | 1B68EBC549 |
| 1022:15d1 | 103c:8562 | AMD        | Raven/Raven2 IOMMU           | 3     |            | 3A4703F85D |
| 1022:15d1 | 103c:85b1 | AMD        | Raven/Raven2 IOMMU           | 3     |            | 87CABD058E |
| 1022:1631 | 103c:879c | AMD        | Renoir IOMMU                 | 3     |            | 7D1F6E5B43 |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816c | 17aa:5081 | Realtek... | RTL8111xP IPMI interface     | 58    |            | 6B6205BC5D |
| 10ec:816c | 17aa:5082 | Realtek... | RTL8111xP IPMI interface     | 25    |            | 12FFAAEFB1 |
| 10ec:816c | 17aa:5125 | Realtek... | RTL8111xP IPMI interface     | 25    |            | 452DD792F1 |
| 10ec:816c | 17aa:5126 | Realtek... | RTL8111xP IPMI interface     | 24    |            | 7065F7BB74 |
| 10ec:816c | 17aa:507e | Realtek... | RTL8111xP IPMI interface     | 21    |            | 31850CE796 |
| 10ec:816c | 17aa:5122 | Realtek... | RTL8111xP IPMI interface     | 12    |            | 0293EF3352 |
| 10ec:816c | 103c:8584 | Realtek... | RTL8111xP IPMI interface     | 8     |            | 3BF39BAC3E |
| 10ec:816c | 103c:83d5 | Realtek... | RTL8111xP IPMI interface     | 7     |            | 21422647B7 |
| 10ec:816c | 103c:8401 | Realtek... | RTL8111xP IPMI interface     | 3     |            | 8167AD2172 |
| 10ec:816c | 103c:8589 | Realtek... | RTL8111xP IPMI interface     | 3     |            | FA3E3FF217 |
| 10ec:816c | 17aa:5123 | Realtek... | RTL8111xP IPMI interface     | 3     |            | 516554B4E7 |
| 10ec:816c | 17aa:511e | Realtek... | RTL8111xP IPMI interface     | 2     |            | C58E41C382 |
| 10ec:816c | 103c:83da | Realtek... | RTL8111xP IPMI interface     | 1     |            | F0FD278615 |
| 10ec:816c | 17aa:511f | Realtek... | RTL8111xP IPMI interface     | 1     |            | E0363562B7 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a36f | 8086:7270 | Intel      | Cannon Lake PCH Shared SRAM  | 456   |            | 853BA027FA |
| 8086:9def | 8086:7270 | Intel      | Cannon Point-LP Shared SRAM  | 282   |            | 6AFF8771B1 |
| 8086:9def |           | Intel      | Cannon Point-LP Shared SRAM  | 201   |            | 62C94909C7 |
| 10de:0a88 |           | Nvidia     | MCP79 Memory Controller      | 159   |            | F982A2F6CC |
| 8086:34ef |           | Intel      | Ice Lake-LP DRAM Controller  | 151   |            | FBBAF8088B |
| 10de:0a89 |           | Nvidia     | MCP79 Memory Controller      | 144   |            | F982A2F6CC |
| 10de:0aa4 |           | Nvidia     | MCP79 Memory Controller      | 144   |            | F982A2F6CC |
| 10de:0a98 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 138   |            | F982A2F6CC |
| 8086:02ef | 8086:7270 | Intel      | Comet Lake PCH-LP Shared ... | 137   |            | 23182C745B |
| 8086:9d21 | 17aa:3872 | Intel      | Sunrise Point-LP PMC         | 123   |            | 19226582D9 |
| 8086:a36f | 1025:1331 | Intel      | Cannon Lake PCH Shared SRAM  | 119   |            | 38688703F4 |
| 8086:a36f | 1028:0905 | Intel      | Cannon Lake PCH Shared SRAM  | 113   |            | 9CDE952049 |
| 8086:02ef | 17aa:5079 | Intel      | Comet Lake PCH-LP Shared ... | 107   |            | 0BC4073D23 |
| 8086:9d21 | 1025:1193 | Intel      | Sunrise Point-LP PMC         | 105   | intel_p... | E922639FF6 |
| 8086:06ef | 8086:7270 | Intel      | Comet Lake PCH Shared SRAM   | 100   |            | 3A3BF28C3A |
| 8086:9d21 | 8086:7270 | Intel      | Sunrise Point-LP PMC         | 99    | intel_p... | 1AB69568A5 |
| 8086:a36f | 1028:087c | Intel      | Cannon Lake PCH Shared SRAM  | 98    |            | 31A6F21CCD |
| 8086:9d21 | 1028:0810 | Intel      | Sunrise Point-LP PMC         | 97    |            | 2FD333BC52 |
| 8086:9def | 17aa:2279 | Intel      | Cannon Point-LP Shared SRAM  | 96    |            | 2444839350 |
| 8086:9def | 103c:8549 | Intel      | Cannon Point-LP Shared SRAM  | 95    |            | 9A264DBCB2 |
| 8086:9d21 | 103c:8079 | Intel      | Sunrise Point-LP PMC         | 94    |            | 0FA8058EEB |
| 8086:9d21 | 1043:12d1 | Intel      | Sunrise Point-LP PMC         | 89    | intel_p... | 570905286F |
| 8086:9d21 | 17aa:225d | Intel      | Sunrise Point-LP PMC         | 88    |            | BBA3BC97B7 |
| 8086:9d21 | 1028:07e6 | Intel      | Sunrise Point-LP PMC         | 83    | intel_p... | C2E884F793 |
| 8086:9def | 1028:08af | Intel      | Cannon Point-LP Shared SRAM  | 82    |            | 80857F497B |
| 8086:9d21 | 17aa:3845 | Intel      | Sunrise Point-LP PMC         | 80    |            | 0540D35606 |
| 8086:9d21 | 17aa:5068 | Intel      | Sunrise Point-LP PMC         | 79    |            | 893F642CBB |
| 8086:9d21 | 1028:078b | Intel      | Sunrise Point-LP PMC         | 78    |            | 4F60F64204 |
| 8086:02ef | 1028:0962 | Intel      | Comet Lake PCH-LP Shared ... | 77    |            | 9E26259821 |
| 8086:a121 | 1028:07be | Intel      | 100 Series/C230 Series Ch... | 76    |            | 6EE00932DC |
| 8086:9d21 | 1025:1295 | Intel      | Sunrise Point-LP PMC         | 75    |            | BEDAFBAD9B |
| 8086:9d21 | 8086:9d21 | Intel      | Sunrise Point-LP PMC         | 74    | intel_p... | 02F641EA60 |
| 8086:a36f | 1025:1264 | Intel      | Cannon Lake PCH Shared SRAM  | 74    |            | 9971E42809 |
| 10de:0a88 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 73    |            | 7A84F17BDB |
| 10de:0a89 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 73    |            | 7A84F17BDB |
| 8086:9d21 | 17aa:225c | Intel      | Sunrise Point-LP PMC         | 73    |            | C33E7CED42 |
| 8086:9d21 | 103c:832a | Intel      | Sunrise Point-LP PMC         | 71    |            | A7BDFE8774 |
| 8086:9d21 | 1025:115f | Intel      | Sunrise Point-LP PMC         | 69    | intel_p... | 9756CE58FC |
| 10de:0d68 |           | Nvidia     | MCP89 Memory Controller      | 64    |            | E3121B6209 |
| 10de:0d69 |           | Nvidia     | MCP89 Memory Controller      | 64    |            | E3121B6209 |
| 10de:0d6d |           | Nvidia     | MCP89 Memory Controller      | 64    |            | E3121B6209 |
| 10de:0d6e |           | Nvidia     | MCP89 Memory Controller      | 64    |            | E3121B6209 |
| 10de:0d6f |           | Nvidia     | MCP89 Memory Controller      | 64    |            | E3121B6209 |
| 10de:0d70 |           | Nvidia     | MCP89 Memory Controller      | 64    |            | E3121B6209 |
| 10de:0d71 |           | Nvidia     | MCP89 Memory Controller      | 64    |            | E3121B6209 |
| 10de:0d72 |           | Nvidia     | MCP89 Memory Controller      | 64    |            | E3121B6209 |
| 10de:0d75 |           | Nvidia     | MCP89 Memory Controller      | 64    |            | E3121B6209 |
| 10de:0d7b |           | Nvidia     | MCP89 Memory Controller      | 64    |            | E3121B6209 |
| 8086:9d21 | 103c:83b2 | Intel      | Sunrise Point-LP PMC         | 64    |            | EF516B4F37 |
| 8086:9d21 | 103c:84a6 | Intel      | Sunrise Point-LP PMC         | 61    | intel_p... | 197CBC5A5D |
| 8086:9def | 17aa:3809 | Intel      | Cannon Point-LP Shared SRAM  | 61    |            | 2ED0E50384 |
| 8086:9d21 | 1028:081c | Intel      | Sunrise Point-LP PMC         | 60    |            | A92377CB2A |
| 8086:9d21 | 17aa:3816 | Intel      | Sunrise Point-LP PMC         | 60    |            | 74D1DA4B68 |
| 8086:a36f | 17aa:3804 | Intel      | Cannon Lake PCH Shared SRAM  | 60    |            | AB6647F9DA |
| 8086:9d21 | 17aa:3851 | Intel      | Sunrise Point-LP PMC         | 59    |            | E2D1740F3A |
| 8086:9d21 | 17aa:2233 | Intel      | Sunrise Point-LP PMC         | 58    |            | 79D4310531 |
| 8086:9d21 | 1025:1085 | Intel      | Sunrise Point-LP PMC         | 57    | intel_p... | C16C3F3C20 |
| 8086:9d21 | 1028:075b | Intel      | Sunrise Point-LP PMC         | 57    |            | 97DBD7A2D0 |
| 8086:9d21 | 17aa:2258 | Intel      | Sunrise Point-LP PMC         | 57    |            | 00AA4C11F4 |
| 8086:9d21 | 1028:06b2 | Intel      | Sunrise Point-LP PMC         | 55    |            | 7AEC563171 |
| 8086:06ef | 1028:097d | Intel      | Comet Lake PCH Shared SRAM   | 54    |            | 8C072EA1C4 |
| 8086:9d21 | 1043:1d30 | Intel      | Sunrise Point-LP PMC         | 54    | intel_p... | 51577F00B4 |
| 8086:9d21 | 17aa:2245 | Intel      | Sunrise Point-LP PMC         | 54    | intel_p... | 5ADBF6A949 |
| 8086:a121 | 1028:0798 | Intel      | 100 Series/C230 Series Ch... | 54    |            | C9A0B1991A |
| 10de:0568 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] Mem... | 53    |            | 67C143DFE9 |
| 10de:0754 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] Mem... | 53    |            | 67C143DFE9 |
| 8086:9d21 | 1028:0767 | Intel      | Sunrise Point-LP PMC         | 53    |            | 904017303B |
| 8086:a36f | 1028:0949 | Intel      | Cannon Lake PCH Shared SRAM  | 53    |            | 480FEF69F1 |
| 8086:a36f | 17aa:3801 | Intel      | Cannon Lake PCH Shared SRAM  | 53    |            | 0FE8BCBB7A |
| 8086:a36f | 17aa:3824 | Intel      | Cannon Lake PCH Shared SRAM  | 53    |            | C332C85DCF |
| 8086:9def | 1028:08ca | Intel      | Cannon Point-LP Shared SRAM  | 52    |            | 0D671ACB94 |
| 8086:9d21 | 17aa:5053 | Intel      | Sunrise Point-LP PMC         | 50    |            | 6B9264BFE9 |
| 8086:a121 | 1025:118a | Intel      | 100 Series/C230 Series Ch... | 50    |            | A1DE054BBB |
| 8086:a36f | 1028:086f | Intel      | Cannon Lake PCH Shared SRAM  | 50    |            | 36324023DD |
| 8086:a121 | 17aa:3819 | Intel      | 100 Series/C230 Series Ch... | 49    |            | C45342870C |
| 8086:9d21 | 17aa:3869 | Intel      | Sunrise Point-LP PMC         | 48    |            | 2198E565BF |
| 8086:a36f | 103c:8478 | Intel      | Cannon Lake PCH Shared SRAM  | 47    |            | D3A001E377 |
| 8086:9d21 | 103c:832b | Intel      | Sunrise Point-LP PMC         | 46    |            | E17FF8A9E4 |
| 8086:9d21 | 1043:1670 | Intel      | Sunrise Point-LP PMC         | 45    | intel_p... | D0C8D6944C |
| 8086:9d21 | 144d:c804 | Intel      | Sunrise Point-LP PMC         | 45    |            | 328C6D995C |
| 8086:9d21 | 17aa:3844 | Intel      | Sunrise Point-LP PMC         | 45    |            | 1BDD9DDF9F |
| 8086:9def | 8086:9def | Intel      | Cannon Point-LP Shared SRAM  | 45    |            | 203BB4369E |
| 8086:a36f | 1028:087d | Intel      | Cannon Lake PCH Shared SRAM  | 44    |            | A5C63380D6 |
| 8086:a36f | 17aa:2267 | Intel      | Cannon Lake PCH Shared SRAM  | 44    |            | 8FA5616036 |
| 8086:9d21 | 1028:06dc | Intel      | Sunrise Point-LP PMC         | 43    |            | F972F7D9BA |
| 8086:a36f | 1025:1333 | Intel      | Cannon Lake PCH Shared SRAM  | 42    |            | CE68155512 |
| 8086:a36f | 17aa:229f | Intel      | Cannon Lake PCH Shared SRAM  | 42    |            | 5002E43F11 |
| 8086:9d21 | 17aa:225a | Intel      | Sunrise Point-LP PMC         | 41    | intel_p... | 11C98724D5 |
| 8086:9def | 17aa:2286 | Intel      | Cannon Point-LP Shared SRAM  | 41    |            | 18DA93A841 |
| 8086:a121 | 1028:0706 | Intel      | 100 Series/C230 Series Ch... | 41    |            | 2DFDF7148F |
| 8086:444e | 8086:444e | Intel      | Turbo Memory Controller      | 40    |            | 5982884BE7 |
| 8086:9d21 | 17aa:3808 | Intel      | Sunrise Point-LP PMC         | 40    |            | DA5DA7D713 |
| 8086:a0ef | 1028:0991 | Intel      | Tiger Lake-LP Shared SRAM    | 39    |            | 089BB7C152 |
| 8086:a36f | 1028:0825 | Intel      | Cannon Lake PCH Shared SRAM  | 39    |            | AC76D208AB |
| 8086:a36f | 1028:0906 | Intel      | Cannon Lake PCH Shared SRAM  | 39    |            | 2B4444A6FA |
| 8086:9d21 | 103c:837d | Intel      | Sunrise Point-LP PMC         | 38    | intel_p... | 7799E3D32A |
| 8086:9d21 | 17aa:505b | Intel      | Sunrise Point-LP PMC         | 38    |            | CC35722C1F |
| 8086:a121 | 17aa:3802 | Intel      | 100 Series/C230 Series Ch... | 38    |            | D63399B396 |
| 8086:a121 | 1028:06e4 | Intel      | 100 Series/C230 Series Ch... | 37    |            | EA3FABAB64 |
| 8086:a121 | 17aa:222e | Intel      | 100 Series/C230 Series Ch... | 37    |            | 88A08A450D |

### Modem (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:266d | 14f1:5423 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 26    | snd_int... | A35F6C0969 |
| 8086:266d | 1179:0001 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 19    | snd_int... | 67580C50DF |
| 8086:24c6 | 14f1:5422 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 12    | snd_int... | 60A32F7736 |
| 1039:7013 | 1025:0083 | Silicon... | AC'97 Modem Controller       | 10    | snd_int... | 464DA49516 |
| 8086:266d | 1025:006a | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 10    | snd_int... | C23E462C42 |
| 8086:266d | 103c:099c | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 9     | snd_int... | 5F105DDA68 |
| 1039:7013 | 1043:1816 | Silicon... | AC'97 Modem Controller       | 8     | snd_int... | AA92B168C5 |
| 8086:266d | 1014:0574 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 8     | snd_int... | 3BE2271444 |
| 8086:266d | 103c:0944 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 8     | snd_int... | 7F042FAA64 |
| 1002:4378 | 103c:3091 | AMD        | IXP SB400 AC'97 Modem Con... | 7     | snd_ati... | F01F51C47C |
| 8086:266d | 1025:0066 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 7     | snd_int... | 10A0D7E3A2 |
| 1002:4378 | 103c:3085 | AMD        | IXP SB400 AC'97 Modem Con... | 5     | snd_ati... | 07C5D7BA93 |
| 1002:4378 | 103c:30a4 | AMD        | IXP SB400 AC'97 Modem Con... | 5     | snd_ati... | C2A5CB93AA |
| 8086:24c6 | 1014:0524 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 5     | snd_int... | 71DAF2C5B4 |
| 8086:24c6 | 1014:055a | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 5     | snd_int... | 190737F754 |
| 8086:266d | 103c:3082 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 5     |            | C98B9CF200 |
| 1002:4378 | 103c:309b | AMD        | IXP SB400 AC'97 Modem Con... | 4     | snd_ati... | B64833B0B1 |
| 1002:4378 | 1043:1186 | AMD        | IXP SB400 AC'97 Modem Con... | 4     | snd_ati... | E298B642F1 |
| 8086:266d | 1014:0576 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 4     | snd_int... | E323E5FE53 |
| 8086:266d | 103c:30c4 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 4     | snd_int... | FE8A07348F |
| 8086:266d | 1179:ff31 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 4     | snd_int... | 875478A51A |
| 8086:266d | 144d:2115 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 4     | snd_int... | D7EE30EC16 |
| 1002:434d | 144d:2115 | AMD        | SB200 AC97 Modem Controller  | 3     | snd_ati... | F72BBFF4B7 |
| 1002:4378 | 1025:007e | AMD        | IXP SB400 AC'97 Modem Con... | 3     | snd_ati... | 60873D0A0E |
| 1039:7013 | 1025:0082 | Silicon... | AC'97 Modem Controller       | 3     |            | EDF0363AFE |
| 10b9:5457 | 104d:8158 | ULi Ele... | M5457 AC'97 Modem Controller | 3     |            | 7E4F74E16A |
| 10de:00d9 | 103c:006d | Nvidia     | nForce3 Audio                | 3     |            | 564B583FED |
| 1106:3068 | 1631:c015 | VIA Tec... | AC'97 Modem Controller       | 3     | snd_via... | C0B37BC3C3 |
| 1106:3068 | 1734:109b | VIA Tec... | AC'97 Modem Controller       | 3     | snd_via... | 2C34DEA0FC |
| 8086:24c6 | 1014:0559 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 3     | snd_int... | 58F9CE5671 |
| 8086:24c6 | 1179:0001 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 3     | snd_int... | FBF8640D2E |
| 8086:266d | 103c:0934 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 3     |            | 453696FF5E |
| 8086:266d | 103c:309d | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 3     | snd_int... | 837230178B |
| 1002:4378 | 103c:308b | AMD        | IXP SB400 AC'97 Modem Con... | 2     | snd_ati... | 7945895A4E |
| 1002:4378 | 103c:30ae | AMD        | IXP SB400 AC'97 Modem Con... | 2     | snd_ati... | F91A752D4D |
| 1002:4378 | 1734:1092 | AMD        | IXP SB400 AC'97 Modem Con... | 2     | snd_ati... | 4D0D913872 |
| 1002:4378 | 1734:1098 | AMD        | IXP SB400 AC'97 Modem Con... | 2     | snd_ati... | 33762202EF |
| 1039:7013 | 104d:814e | Silicon... | AC'97 Modem Controller       | 2     | snd_int... | 11D39BBA01 |
| 10b9:5457 | 1071:8351 | ULi Ele... | M5457 AC'97 Modem Controller | 2     |            | 7806C7E5CD |
| 10de:00d9 | 1043:1856 | Nvidia     | nForce3 Audio                | 2     | snd_int... | 0A302BFAFD |
| 8086:2486 | 1014:0223 | Intel      | 82801CA/CAM AC'97 Modem C... | 2     | snd_int... | B6D0B8758E |
| 8086:2486 | 1179:0001 | Intel      | 82801CA/CAM AC'97 Modem C... | 2     | snd_int... | A79789524B |
| 8086:2486 | 134d:4c21 | Intel      | 82801CA/CAM AC'97 Modem C... | 2     |            | 5489DF545B |
| 8086:24c6 | 103c:3080 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 2     | snd_int... | FB937794C7 |
| 8086:24c6 | 1071:8089 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 2     | snd_int... | 227BF1BA1D |
| 8086:24c6 | 10cf:10d1 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 2     | snd_int... | EA732BEA27 |
| 8086:24c6 | 1179:ff31 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 2     | snd_int... | E9BD04F647 |
| 8086:266d | 103c:3080 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 2     | snd_int... | 0572E8425C |
| 8086:266d | 103c:3081 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 2     | snd_int... | FE61304CD4 |
| 8086:266d | 1462:0121 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 2     | snd_int... | 3E407C2B03 |
| 1002:434d | 1025:0052 | AMD        | SB200 AC97 Modem Controller  | 1     | snd_ati... | 856DF8910C |
| 1002:434d | 103c:006b | AMD        | SB200 AC97 Modem Controller  | 1     | snd_ati... | 5171D8BC33 |
| 1002:4378 | 1025:0080 | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 00FDC7C100 |
| 1002:4378 | 1179:0001 | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 184C93E6DD |
| 1002:4378 | 1179:ff31 | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | E40C220E30 |
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
| 11c1:045c | 8086:2205 | LSI        | LT WinModem                  | 1     | serial     | 1B54E25E77 |
| 8086:2446 | 1025:1027 | Intel      | 82801BA/BAM AC'97 Modem C... | 1     |            | E0A83557FF |
| 8086:2446 | 1179:0001 | Intel      | 82801BA/BAM AC'97 Modem C... | 1     |            | 89EB89D54A |
| 8086:2486 | 1014:0227 | Intel      | 82801CA/CAM AC'97 Modem C... | 1     |            | 65D3C4C3C2 |
| 8086:2486 | 1043:1496 | Intel      | 82801CA/CAM AC'97 Modem C... | 1     |            | 1E7DA431AF |
| 8086:2486 | 104d:8142 | Intel      | 82801CA/CAM AC'97 Modem C... | 1     | snd_int... | 185FD8341C |
| 8086:2486 | 14c0:0012 | Intel      | 82801CA/CAM AC'97 Modem C... | 1     | snd_int... | A8AF42D6E7 |
| 8086:2486 | 14f1:5421 | Intel      | 82801CA/CAM AC'97 Modem C... | 1     |            | 4F9273C63C |
| 8086:24c6 | 1014:0525 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | ED7FD6C653 |
| 8086:24c6 | 1025:005a | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | 21602D608F |
| 8086:24c6 | 1025:0064 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | C7045484B1 |
| 8086:24c6 | 1025:0071 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | BBE6DD58A1 |
| 8086:24c6 | 103c:0890 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | 44DF53B183 |
| 8086:24c6 | 103c:08b0 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 316E375A5C |
| 8086:24c6 | 103c:3084 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | 24A093E347 |
| 8086:24c6 | 1043:1746 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 473966E549 |
| 8086:24c6 | 1043:1826 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | B5CB46FFBA |
| 8086:24c6 | 104d:818c | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 7274BBB49F |
| 8086:24c6 | 1071:a001 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 9D5A19DCF4 |
| 8086:24c6 | 107b:0360 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | 53EC93715E |
| 8086:24c6 | 144d:2115 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 529607257E |
| 8086:24c6 | 144d:c00c | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 8BCCDD8350 |
| 8086:24c6 | 14c0:0012 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 38E0AD48B1 |
| 8086:24c6 | 152d:0707 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | snd_int... | 81347CD6BB |
| 8086:24c6 | 1584:4007 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | F13A21C874 |
| 8086:24c6 | 1631:d004 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | 2EE7FA4DA9 |
| 8086:24c6 | 1734:103c | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | 6F452862B4 |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15e2 | 1022:15e2 | AMD        | Raven/Raven2/FireFlight/R... | 339   | snd_pci... | F504E72617 |
| 8086:22b8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 280   | intel_a... | 1B5E908CFF |
| 14e4:1570 | 14e4:1570 | Broadcom   | 720p FaceTime HD Camera      | 226   | bdc_pci    | 1007726831 |
| 1022:15e2 | 19e5:3e19 | AMD        | Raven/Raven2/FireFlight/R... | 62    | snd_pci... | 9908BA82E9 |
| 1022:15e2 | 17aa:5081 | AMD        | Raven/Raven2/FireFlight/R... | 60    | snd_pci... | 6B6205BC5D |
| 1022:15e2 | 103c:84ae | AMD        | Raven/Raven2/FireFlight/R... | 56    | snd_pci... | BFB71F53EC |
| 1022:15e2 | 17aa:507f | AMD        | Raven/Raven2/FireFlight/R... | 55    | snd_pci... | 441E3AA589 |
| 1022:15e2 | 1025:134d | AMD        | Raven/Raven2/FireFlight/R... | 52    | snd_pci... | 479F0822FE |
| 1022:15e2 | 17aa:381c | AMD        | Raven/Raven2/FireFlight/R... | 50    | snd_pci... | EA8B53C3DC |
| 1022:15e2 | 17aa:5124 | AMD        | Raven/Raven2/FireFlight/R... | 50    | snd_pci... | 4DE4650899 |
| 1022:15e2 | 17aa:3812 | AMD        | Raven/Raven2/FireFlight/R... | 49    | snd_pci... | 6FE368312C |
| 1022:15e2 | 17aa:3821 | AMD        | Raven/Raven2/FireFlight/R... | 48    | snd_pci... | 9480BB8E99 |
| 1022:15e2 | 17aa:3814 | AMD        | Raven/Raven2/FireFlight/R... | 46    | snd_pci... | FCC7840D63 |
| 8086:5a88 |           | Intel      | Celeron N3350/Pentium N42... | 43    |            | 7B973470B7 |
| 1022:15e2 | 103c:8730 | AMD        | Raven/Raven2/FireFlight/R... | 41    | snd_pci... | FC1870A101 |
| 1022:15e2 | 1e21:1043 | AMD        | Raven/Raven2/FireFlight/R... | 40    | snd_pci... | BF2D71E7F2 |
| 1022:15e2 | 17aa:3807 | AMD        | Raven/Raven2/FireFlight/R... | 35    | snd_pci... | E7FDA6091A |
| 1022:15e2 | 17aa:3813 | AMD        | Raven/Raven2/FireFlight/R... | 35    | snd_pci... | 93286A0D38 |
| 1022:15e2 | 19e5:3e18 | AMD        | Raven/Raven2/FireFlight/R... | 35    | snd_pci... | 430907546B |
| 1022:15e2 | 103c:85ea | AMD        | Raven/Raven2/FireFlight/R... | 33    | snd_pci... | D03BDBF1DA |
| 1022:15e2 | 1d05:109f | AMD        | Raven/Raven2/FireFlight/R... | 33    | snd_pci... | 69510C22F1 |
| 1022:15e2 | 103c:86fd | AMD        | Raven/Raven2/FireFlight/R... | 29    | snd_pci... | 415E7E34D6 |
| 1022:15e2 | 1025:142b | AMD        | Raven/Raven2/FireFlight/R... | 28    | snd_pci... | 5DCA660F7E |
| 8086:22b8 | 103c:813e | Intel      | Atom/Celeron/Pentium Proc... | 28    | intel_a... | 71120B9356 |
| 1022:15e2 | 103c:8760 | AMD        | Raven/Raven2/FireFlight/R... | 27    | snd_pci... | 936E09E13C |
| 1022:15e2 | 17aa:3822 | AMD        | Raven/Raven2/FireFlight/R... | 27    | snd_pci... | 99D22D0422 |
| 1022:15e2 | 17aa:507e | AMD        | Raven/Raven2/FireFlight/R... | 27    | snd_pci... | 31850CE796 |
| 1022:15e2 | 103c:85b3 | AMD        | Raven/Raven2/FireFlight/R... | 26    | snd_pci... | 039DF57583 |
| 1022:15e2 | 17aa:5125 | AMD        | Raven/Raven2/FireFlight/R... | 25    | snd_pci... | 452DD792F1 |
| 1022:15e2 | 1025:1461 | AMD        | Raven/Raven2/FireFlight/R... | 24    | snd_pci... | 8D643F3501 |
| 1022:15e2 | 1025:134f | AMD        | Raven/Raven2/FireFlight/R... | 23    | snd_pci... | 3EC48C5388 |
| 1022:15e2 | 19e5:3e06 | AMD        | Raven/Raven2/FireFlight/R... | 22    | snd_pci... | 1797098345 |
| 8086:22b8 | 1297:2063 | Intel      | Atom/Celeron/Pentium Proc... | 22    | intel_a... | D6AD6F67A7 |
| 1022:15e2 | 1a0e:1043 | AMD        | Raven/Raven2/FireFlight/R... | 21    | snd_pci... | B3DA27422D |
| 1022:15e2 | 1025:1456 | AMD        | Raven/Raven2/FireFlight/R... | 18    | snd_pci... | 80CF3DC8E7 |
| 1022:15e2 | 17aa:5084 | AMD        | Raven/Raven2/FireFlight/R... | 18    | snd_pci... | 12FFAAEFB1 |
| 1022:15e2 | 19e5:3e14 | AMD        | Raven/Raven2/FireFlight/R... | 18    | snd_pci... | 2E6A9F05AC |
| 1022:15e2 | 17aa:3823 | AMD        | Raven/Raven2/FireFlight/R... | 17    | snd_pci... | F707B24713 |
| 1022:15e2 | 103c:85e0 | AMD        | Raven/Raven2/FireFlight/R... | 16    | snd_pci... | C740D1205B |
| 1022:15e2 | 17aa:380f | AMD        | Raven/Raven2/FireFlight/R... | 15    | snd_pci... | CB9D7D7035 |
| 1022:15e2 | 17aa:5127 | AMD        | Raven/Raven2/FireFlight/R... | 15    | snd_pci... | 7065F7BB74 |
| 1022:15e2 | 1e83:3e33 | AMD        | Raven/Raven2/FireFlight/R... | 14    | snd_pci... | 3F2AA0EB97 |
| 14e4:1615 | 14e4:1615 | Broadcom   | BCM70015 Video Decoder [C... | 14    | crystalhd  | 85DEF78A94 |
| 1022:15e2 | 1028:09f5 | AMD        | Raven/Raven2/FireFlight/R... | 13    | snd_pci... | 706D306B5E |
| 1022:15e2 | 19e5:3e10 | AMD        | Raven/Raven2/FireFlight/R... | 13    | snd_pci... | 9C73A8D7D6 |
| 1022:15e2 | 1025:1378 | AMD        | Raven/Raven2/FireFlight/R... | 12    | snd_pci... | DA566F34DD |
| 1022:15e2 | 103c:84d2 | AMD        | Raven/Raven2/FireFlight/R... | 12    | snd_pci... | C66066FF6B |
| 1022:15e2 | 17aa:380d | AMD        | Raven/Raven2/FireFlight/R... | 12    | snd_pci... | 51C5D13230 |
| 1022:15e2 | 17aa:381f | AMD        | Raven/Raven2/FireFlight/R... | 12    | snd_pci... | 2FE8E30909 |
| 1022:15e2 | 103c:879e | AMD        | Raven/Raven2/FireFlight/R... | 11    | snd_pci... | 61A5B2ED1E |
| 8086:1919 | 8086:1919 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 11    | ipu3_imgu  | B62A6C9162 |
| 8086:1919 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 11    | ipu3_imgu  | D82FB9FDAF |
| 8086:22b8 | 1043:1bdd | Intel      | Atom/Celeron/Pentium Proc... | 11    | intel_a... | 866C75D8E6 |
| 8086:9d32 | 8086:9d32 | Intel      | CSI-2 Host Controller        | 11    | ipu3_cio2  | B62A6C9162 |
| 1022:15e2 | 103c:86d5 | AMD        | Raven/Raven2/FireFlight/R... | 10    | snd_pci... | 209887E993 |
| 1022:15e2 | 17aa:5126 | AMD        | Raven/Raven2/FireFlight/R... | 10    | snd_pci... | EB33727EFF |
| 1022:15e2 | 1025:1233 | AMD        | Raven/Raven2/FireFlight/R... | 9     | snd_pci... | 6ADFA9E5CD |
| 1022:15e2 | 103c:8786 | AMD        | Raven/Raven2/FireFlight/R... | 9     | snd_pci... | 3F4BBD14BA |
| 1022:15e2 | 103c:87b1 | AMD        | Raven/Raven2/FireFlight/R... | 9     | snd_pci... | E1CF7F4599 |
| 1022:15e2 | 1d72:1953 | AMD        | Raven/Raven2/FireFlight/R... | 9     | snd_pci... | 7139D19A98 |
| 1022:15e2 | 103c:8706 | AMD        | Raven/Raven2/FireFlight/R... | 8     | snd_pci... | F0EEC3E2AA |
| 1022:15e2 | 1462:12b5 | AMD        | Raven/Raven2/FireFlight/R... | 8     | snd_pci... | 649DBCEEFF |
| 8086:1919 | 103c:80fc | Intel      | Xeon E3-1200 v5/E3-1500 v... | 8     | ipu3_imgu  | 09240A2A3F |
| 8086:9d32 | 103c:80fc | Intel      | CSI-2 Host Controller        | 8     | ipu3_cio2  | 09240A2A3F |
| 1022:15e2 | 1025:1455 | AMD        | Raven/Raven2/FireFlight/R... | 7     | snd_pci... | C118461E82 |
| 1022:15e2 | 103c:86d4 | AMD        | Raven/Raven2/FireFlight/R... | 7     | snd_pci... | 0C1B37ACD2 |
| 1022:15e2 | 103c:87b2 | AMD        | Raven/Raven2/FireFlight/R... | 7     | snd_pci... | 4A21E62A29 |
| 1022:15e2 | 1558:a500 | AMD        | Raven/Raven2/FireFlight/R... | 7     | snd_pci... | 052ED9C216 |
| 1022:15e2 | 1d72:1951 | AMD        | Raven/Raven2/FireFlight/R... | 7     | snd_pci... | 8700A7EAED |
| 14e4:1612 | 14e4:2612 | Broadcom   | BCM70012 Video Decoder [C... | 7     |            | 6FCADF1396 |
| 8086:0f38 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 7     | intel_a... | AF354E922D |
| 1022:15e2 | 103c:87cf | AMD        | Raven/Raven2/FireFlight/R... | 6     | snd_pci... | C686837768 |
| 1022:15e2 | 17aa:5082 | AMD        | Raven/Raven2/FireFlight/R... | 6     | snd_pci... | 54D7D9C149 |
| 8086:9d32 | 8086:7270 | Intel      | CSI-2 Host Controller        | 6     | ipu3_cio2  | D82FB9FDAF |
| 1022:15e2 | 1028:0a1e | AMD        | Raven/Raven2/FireFlight/R... | 5     | snd_rn_... | 04E0880C54 |
| 1022:15e2 | 103c:84a2 | AMD        | Raven/Raven2/FireFlight/R... | 5     | snd_pci... | 220E290FCB |
| 1022:15e2 | 103c:8787 | AMD        | Raven/Raven2/FireFlight/R... | 5     | snd_pci... | 3AE2F83C9F |
| 1022:15e2 | 103c:87b7 | AMD        | Raven/Raven2/FireFlight/R... | 5     | snd_pci... | A2A6C6FD1A |
| 1022:15e2 | 17aa:3811 | AMD        | Raven/Raven2/FireFlight/R... | 5     | snd_pci... | 73AAD972AD |
| 1022:15e2 | 17aa:5083 | AMD        | Raven/Raven2/FireFlight/R... | 5     | snd_rn_... | D9708C63F5 |
| 1131:7231 | 1461:0b0f | Philips... | SAA7231                      | 5     |            | 6752A255CA |
| 8086:1919 | 17aa:3812 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 5     | ipu3_imgu  | AAEF1C5AE7 |
| 8086:22b8 | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 5     | intel_a... | 781A13F986 |
| 8086:9d32 | 17aa:3812 | Intel      | CSI-2 Host Controller        | 5     | ipu3_cio2  | AAEF1C5AE7 |
| 1022:15e2 | 103c:86d6 | AMD        | Raven/Raven2/FireFlight/R... | 4     | snd_pci... | 220B969C6D |
| 1022:15e2 | 103c:87c5 | AMD        | Raven/Raven2/FireFlight/R... | 4     | snd_pci... | 4792D19DD2 |
| 1022:15e2 | 1043:1e8e | AMD        | Raven/Raven2/FireFlight/R... | 4     | snd_pci... | 0AB74390ED |
| 1022:15e2 | 17aa:380b | AMD        | Raven/Raven2/FireFlight/R... | 4     | snd_pci... | D1AC331FBC |
| 1022:15e2 | 17aa:3824 | AMD        | Raven/Raven2/FireFlight/R... | 4     | snd_pci... | F2FBB53B7F |
| 1131:7160 | 1461:1055 | Philips... | SAA7160                      | 4     |            | B81EC5CB28 |
| 8086:0f38 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 4     | intel_a... | 5C2A2AD95A |
| 8086:22b8 | 1025:1021 | Intel      | Atom/Celeron/Pentium Proc... | 4     | intel_a... | C5A45FDD73 |
| 8086:22b8 | 1025:106e | Intel      | Atom/Celeron/Pentium Proc... | 4     | intel_a... | 4308DD8008 |
| 1022:15e2 | 1025:137a | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | 5D9B2B99FC |
| 1022:15e2 | 1028:0a12 | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | 1B68EBC549 |
| 1022:15e2 | 103c:8562 | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | 3A4703F85D |
| 1022:15e2 | 103c:85b1 | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | 87CABD058E |
| 1022:15e2 | 103c:879c | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | 7D1F6E5B43 |
| 1022:15e2 | 103c:87b3 | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | 5EA126F6DA |
| 1022:15e2 | 103c:887a | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | FFC846888E |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8168 | 1043:200f | Realtek... | RTL8111/8168/8411 PCI Exp... | 1372  | r8169      | 08930695BC |
| 10ec:8136 | 1043:200f | Realtek... | RTL810xE PCI Express Fast... | 494   | r8169      | DCD714D5FA |
| 14e4:16b5 | 1025:0647 | Broadcom   | NetLink BCM57785 Gigabit ... | 377   | tg3        | B732F94275 |
| 10ec:8168 | 1043:208f | Realtek... | RTL8111/8168/8411 PCI Exp... | 329   | r8169      | 3A3BF28C3A |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 303   | r8169      | 20896C9BEF |
| 10ec:8168 | 1043:16d5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 252   | r8169      | 438D785F0E |
| 14e4:16b4 | 14e4:16b4 | Broadcom   | NetXtreme BCM57765 Gigabi... | 231   | tg3        | A53D0DE98A |
| 197b:0250 | 1043:1905 | JMicron... | JMC250 PCI Express Gigabi... | 219   | jme        | 11F1CDC49A |
| 1969:2062 | 1043:8468 | Attansi... | AR8152 v2.0 Fast Ethernet    | 216   | atl1c      | 2117F02A4F |
| 14e4:16b5 | 1025:0504 | Broadcom   | NetLink BCM57785 Gigabit ... | 196   | tg3        | 85BCF858C5 |
| 1969:1083 | 1043:1851 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 193   | atl1c      | 7DC7D11BE2 |
| 8086:155a | 17aa:2214 | Intel      | Ethernet Connection I218-LM  | 181   | e1000e     | 4C600416F9 |
| 10ec:8168 | 17aa:5002 | Realtek... | RTL8111/8168/8411 PCI Exp... | 165   | r8169      | 2BA1AA7C62 |
| 14e4:1692 | 1025:036d | Broadcom   | NetLink BCM57780 Gigabit ... | 163   | tg3        | 2C401BFDB4 |
| 1969:1063 | 1043:1820 | Qualcom... | AR8131 Gigabit Ethernet      | 149   | atl1c      | FBC93A495C |
| 10ec:8136 | 1179:ff00 | Realtek... | RTL810xE PCI Express Fast... | 148   | r8169      | 8E44C9EDAF |
| 14e4:1693 | 1025:011c | Broadcom   | NetLink BCM5787M Gigabit ... | 144   | tg3        | 6A05B72968 |
| 1969:1090 | 17aa:3979 | Qualcom... | AR8162 Fast Ethernet         | 141   | alx        | 5872E567EC |
| 1969:2062 | 17aa:3979 | Qualcom... | AR8152 v2.0 Fast Ethernet    | 141   | atl1c      | FE1E9576C6 |
| 8086:15a2 | 17aa:2226 | Intel      | Ethernet Connection (3) I... | 141   | e1000e     | A5D677976F |
| 10ec:8168 | 17aa:3812 | Realtek... | RTL8111/8168/8411 PCI Exp... | 134   | r8169      | 779BFC3B47 |
| 10de:0ab0 | 10de:cb79 | Nvidia     | MCP79 Ethernet               | 133   | forcedeth  | F982A2F6CC |
| 8086:156f | 17aa:2233 | Intel      | Ethernet Connection I219-LM  | 132   | e1000e     | CAD013A6A5 |
| 14e4:16b3 | 1025:0775 | Broadcom   | NetXtreme BCM57786 Gigabi... | 131   | tg3        | 98166600FA |
| 10ec:8136 | 17aa:3975 | Realtek... | RTL810xE PCI Express Fast... | 126   | r8169      | 21DB34139A |
| 14e4:1698 | 1025:0207 | Broadcom   | NetLink BCM5784M Gigabit ... | 125   | tg3        | F8CF9B2AA2 |
| 10ec:8168 | 17aa:38bb | Realtek... | RTL8111/8168/8411 PCI Exp... | 123   | r8169      | 19226582D9 |
| 11ab:4381 | 104d:9071 | Marvell... | Yukon Optima 88E8059 [PCI... | 122   | sky2       | 03E0270FDD |
| 10ec:8136 | 1179:ff1e | Realtek... | RTL810xE PCI Express Fast... | 120   | r8169      | 40EBC49A02 |
| 1969:1026 | 1043:14f5 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 117   | atl1e      | 498362846A |
| 10ec:8136 | 1028:04b0 | Realtek... | RTL810xE PCI Express Fast... | 116   | r8169      | FF37A9C00D |
| 10ec:8168 | 1025:1331 | Realtek... | RTL8111/8168/8411 PCI Exp... | 115   | r8169      | 38688703F4 |
| 10ec:8136 | 10ec:0123 | Realtek... | RTL810xE PCI Express Fast... | 112   | r8169      | 8DFADF5EDB |
| 10ec:8168 | 1b0a:20d9 | Realtek... | RTL8111/8168/8411 PCI Exp... | 110   | r8169      | 6AF51E631B |
| 10ec:8168 | 1025:1193 | Realtek... | RTL8111/8168/8411 PCI Exp... | 107   | r8169      | E922639FF6 |
| 10ec:8168 | 1043:1277 | Realtek... | RTL8111/8168/8411 PCI Exp... | 107   | r8169      | A8FD68FCCC |
| 10ec:8168 | 17aa:5079 | Realtek... | RTL8111/8168/8411 PCI Exp... | 107   | r8169      | 0BC4073D23 |
| 1969:1062 | 1043:838a | Qualcom... | AR8132 Fast Ethernet         | 107   | atl1c      | E819E51835 |
| 10ec:8168 | 103c:8330 | Realtek... | RTL8111/8168/8411 PCI Exp... | 105   | r8169      | 5671BA2F85 |
| 10ec:8168 | 1025:0866 | Realtek... | RTL8111/8168/8411 PCI Exp... | 103   | r8169      | 58B4832D53 |
| 14e4:1713 | 17aa:3a23 | Broadcom   | NetLink BCM5906M Fast Eth... | 103   | tg3        | 1BBEC614AA |
| 8086:155a | 103c:198f | Intel      | Ethernet Connection I218-LM  | 99    | e1000e     | 6573923D55 |
| 10ec:8168 | 17aa:388a | Realtek... | RTL8111/8168/8411 PCI Exp... | 98    | r8169      | 0540D35606 |
| 10ec:8136 | 1028:0810 | Realtek... | RTL810xE PCI Express Fast... | 96    | r8169      | 2FD333BC52 |
| 1969:10a0 | 17aa:3802 | Qualcom... | QCA8172 Fast Ethernet        | 96    | alx        | 91CF490677 |
| 8086:153a | 17aa:220e | Intel      | Ethernet Connection I217-LM  | 96    | e1000e     | 4EC9EAAC2F |
| 11ab:4354 | 1028:02aa | Marvell... | 88E8040 PCI-E Fast Ethern... | 95    | sky2       | F0D0F92FD9 |
| 1969:1091 | 1043:14c7 | Qualcom... | AR8161 Gigabit Ethernet      | 94    | alx        | 53842E648E |
| 10ec:8168 | 104d:908b | Realtek... | RTL8111/8168/8411 PCI Exp... | 93    | r8169      | F88D733F75 |
| 1969:1083 | 1043:13c7 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 93    | atl1c      | 389E1A52A6 |
| 10ec:8168 | 1025:1094 | Realtek... | RTL8111/8168/8411 PCI Exp... | 92    | r8169      | 9756CE58FC |
| 10ec:8168 | 17aa:3816 | Realtek... | RTL8111/8168/8411 PCI Exp... | 92    | r8169      | EB9AAA55EA |
| 10ec:8168 | 144d:c606 | Realtek... | RTL8111/8168/8411 PCI Exp... | 91    | r8169      | F8B9508953 |
| 14e4:1673 | 1028:01f9 | Broadcom   | NetXtreme BCM5755M Gigabi... | 91    | tg3        | E271885D51 |
| 14e4:1692 | 1025:033d | Broadcom   | NetLink BCM57780 Gigabit ... | 89    | tg3        | ED5C778D4F |
| 10ec:8136 | 1179:fb37 | Realtek... | RTL810xE PCI Express Fast... | 88    | r8169      | 834D15C08C |
| 10ec:8136 | 10ec:8136 | Realtek... | RTL810xE PCI Express Fast... | 87    | r8169      | BEA9269412 |
| 10ec:8136 | 17aa:3830 | Realtek... | RTL810xE PCI Express Fast... | 86    | r8169      | BAC9935F0B |
| 10ec:8168 | 1043:11f5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 86    | r8169      | 7BD5FA25B3 |
| 10ec:8168 | 17aa:3854 | Realtek... | RTL8111/8168/8411 PCI Exp... | 86    | r8169      | 74D1DA4B68 |
| 1969:2060 | 1179:ff1e | Qualcom... | AR8152 v1.1 Fast Ethernet    | 83    | atl1c      | C5883A9DA8 |
| 10ec:8168 | 103c:84ac | Realtek... | RTL8111/8168/8411 PCI Exp... | 82    | r8169      | D22A5E8410 |
| 10ec:8168 | 144d:c0da | Realtek... | RTL8111/8168/8411 PCI Exp... | 82    | r8169      | 541B3E9CBA |
| 10ec:8168 | 1043:205f | Realtek... | RTL8111/8168/8411 PCI Exp... | 80    | r8169      | EA9385EC68 |
| 10ec:8136 | 17aa:392e | Realtek... | RTL810xE PCI Express Fast... | 79    | r8169      | CEAF1A4989 |
| 10ec:8136 | 103c:3577 | Realtek... | RTL810xE PCI Express Fast... | 78    | r8169      | C0FCCB63BB |
| 11ab:436a | 11ab:00ba | Marvell... | 88E8058 PCI-E Gigabit Eth... | 78    | sky2       | E31DDE7E74 |
| 1969:1091 | 1043:1477 | Qualcom... | AR8161 Gigabit Ethernet      | 78    | alx        | C69CD5ACEB |
| 10ec:8168 | 1025:1295 | Realtek... | RTL8111/8168/8411 PCI Exp... | 77    | r8169      | BEDAFBAD9B |
| 10ec:8168 | 17aa:3975 | Realtek... | RTL8111/8168/8411 PCI Exp... | 77    | r8169      | 88621AC34B |
| 10ec:8168 | 17aa:5068 | Realtek... | RTL8111/8168/8411 PCI Exp... | 75    | r8169      | F665CFA22E |
| 10ec:8168 | 1025:1264 | Realtek... | RTL8111/8168/8411 PCI Exp... | 74    | r8169      | 9971E42809 |
| 11ab:4354 | 1028:022f | Marvell... | 88E8040 PCI-E Fast Ethern... | 74    | sky2       | 06130B24C5 |
| 8086:153a | 17aa:2210 | Intel      | Ethernet Connection I217-LM  | 74    | e1000e     | CE71038513 |
| 10ec:8168 | 1025:1192 | Realtek... | RTL8111/8168/8411 PCI Exp... | 73    | r8169      | CDC742CD03 |
| 10ec:8168 | 144d:c652 | Realtek... | RTL8111/8168/8411 PCI Exp... | 72    | r8169      | 326B21D2B4 |
| 8086:15a2 | 103c:2216 | Intel      | Ethernet Connection (3) I... | 72    | e1000e     | 304747E4C6 |
| 10ec:8168 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 71    | r8169      | 40F5C93523 |
| 10ec:8168 | 17aa:380a | Realtek... | RTL8111/8168/8411 PCI Exp... | 71    | r8169      | 80FD6E7115 |
| 1969:1062 | 1025:0212 | Qualcom... | AR8132 Fast Ethernet         | 71    | atl1c      | F573488BDA |
| 10ec:8168 | 103c:832a | Realtek... | RTL8111/8168/8411 PCI Exp... | 70    | r8169      | A7BDFE8774 |
| 10ec:8139 | 1043:1045 | Realtek... | RTL-8100/8101L/8139 PCI F... | 69    | 8139too... | 0451B6DB0A |
| 10ec:8136 | 17aa:3861 | Realtek... | RTL810xE PCI Express Fast... | 68    | r8169      | E57C2FB16D |
| 8086:15be | 17aa:2279 | Intel      | Ethernet Connection (6) I... | 67    | e1000e     | 2444839350 |
| 10ec:8168 | 17aa:5072 | Realtek... | RTL8111/8168/8411 PCI Exp... | 66    | r8169      | 62C94909C7 |
| 8086:153b | 103c:1993 | Intel      | Ethernet Connection I217-V   | 66    | e1000e     | 605367D5D4 |
| 10ec:8168 | 17aa:380b | Realtek... | RTL8111/8168/8411 PCI Exp... | 65    | r8169      | B1B8196F26 |
| 8086:155a | 1028:05cb | Intel      | Ethernet Connection I218-LM  | 65    | e1000e     | EF82F4635D |
| 10ec:8136 | 1028:05f3 | Realtek... | RTL810xE PCI Express Fast... | 64    | r8169      | 1F0CF22837 |
| 10ec:8136 | 1028:0651 | Realtek... | RTL810xE PCI Express Fast... | 64    | r8169      | E1A816CC42 |
| 14e4:1684 | 1025:013c | Broadcom   | NetXtreme BCM5764M Gigabi... | 64    | tg3        | B6E44B21DB |
| 14e4:1684 | 14e4:1684 | Broadcom   | NetXtreme BCM5764M Gigabi... | 64    | tg3        | 85073CEA15 |
| 10ec:8168 | 103c:17f6 | Realtek... | RTL8111/8168/8411 PCI Exp... | 63    | r8169      | D0705EF193 |
| 8086:153a | 1028:05be | Intel      | Ethernet Connection I217-LM  | 63    | e1000e     | 6399CECB6F |
| 10ec:8136 | 1179:fd3c | Realtek... | RTL810xE PCI Express Fast... | 62    | r8169      | 58D3740C30 |
| 10ec:8168 | 1025:098a | Realtek... | RTL8111/8168/8411 PCI Exp... | 62    | r8169      | D8A334E94C |
| 10ec:8168 | 144d:c0b6 | Realtek... | RTL8111/8168/8411 PCI Exp... | 62    | r8169      | 574B61FC95 |
| 10ec:8168 | 17aa:3821 | Realtek... | RTL8111/8168/8411 PCI Exp... | 62    | r8169      | 09CC2AED35 |
| 11ab:4354 | 144d:c072 | Marvell... | 88E8040 PCI-E Fast Ethern... | 62    | sky2       | D4548D357F |
| 8086:15a2 | 1028:062e | Intel      | Ethernet Connection (3) I... | 61    | e1000e     | 5F0CE579EC |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 168c:002b | 1a3b:1089 | Qualcom... | AR9285 Wireless Network A... | 892   | ath9k      | 11F1CDC49A |
| 8086:0085 | 8086:1311 | Intel      | Centrino Advanced-N 6205 ... | 878   | iwlwifi    | AEF8C27B50 |
| 8086:2723 | 8086:0084 | Intel      | Wi-Fi 6 AX200                | 816   | iwlwifi    | 36D147C67F |
| 168c:0042 | 11ad:08a6 | Qualcom... | QCA9377 802.11ac Wireless... | 790   | ath10k_pci | 80CF3DC8E7 |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 698   | iwlwifi    | 3EA595A278 |
| 8086:a370 | 8086:0034 | Intel      | Cannon Lake PCH CNVi WiFi    | 629   | iwlwifi    | ECC7F6B940 |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 611   | iwlwifi    | BBA3BC97B7 |
| 168c:0042 | 17aa:0901 | Qualcom... | QCA9377 802.11ac Wireless... | 570   | ath10k_pci | 6670E1C145 |
| 10ec:d723 | 103c:8319 | Realtek... | RTL8723DE Wireless Networ... | 546   | rtl8723de  | 5E75AF2BA4 |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 538   | iwlwifi    | 19226582D9 |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 518   | rtl8821ce  | 035B3CDC60 |
| 168c:0042 | 1028:1810 | Qualcom... | QCA9377 802.11ac Wireless... | 492   | ath10k_pci | A638ECEE38 |
| 8086:9df0 | 8086:0034 | Intel      | Cannon Point-LP CNVi [Wir... | 489   | iwlwifi    | DB75E4E24F |
| 1814:3290 | 103c:18ec | Ralink     | RT3290 Wireless 802.11n 1... | 479   | rt2800pci  | BDAEE2E27B |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 461   | iwlwifi    | C16C3F3C20 |
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 402   | iwlwifi    | C45342870C |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 387   | iwlwifi    | 20F25688A9 |
| 8086:088e | 8086:4060 | Intel      | Centrino Advanced-N 6235     | 371   | iwlwifi    | 24758ED5B3 |
| 8086:2723 | 8086:0080 | Intel      | Wi-Fi 6 AX200                | 365   | iwlwifi    | 6B6205BC5D |
| 168c:0036 | 11ad:0642 | Qualcom... | QCA9565 / AR9565 Wireless... | 355   | ath9k      | 99175F6D0D |
| 8086:4237 | 8086:1211 | Intel      | PRO/Wireless 5100 AGN [Sh... | 351   | iwlwifi    | 65FBD3DEF4 |
| 168c:0032 | 1a3b:2c97 | Qualcom... | AR9485 Wireless Network A... | 348   | ath9k      | 1F075FEB49 |
| 8086:4222 | 8086:1001 | Intel      | PRO/Wireless 3945ABG [Gol... | 341   | iwl3945    | 6A05B72968 |
| 168c:0036 | 1028:020c | Qualcom... | QCA9565 / AR9565 Wireless... | 336   | ath9k      | F226786C1B |
| 168c:0032 | 144d:4105 | Qualcom... | AR9485 Wireless Network A... | 326   | ath9k      | 228B340863 |
| 14e4:4365 | 17aa:0611 | Broadcom   | BCM43142 802.11b/g/n         | 325   | wl         | 2BA1AA7C62 |
| 168c:0036 | 1028:020e | Qualcom... | QCA9565 / AR9565 Wireless... | 322   | ath9k      | 8EFEEF8292 |
| 168c:003e | 1a56:1535 | Qualcom... | QCA6174 802.11ac Wireless... | 318   | ath10k_pci | 241E2FC9BD |
| 8086:3165 | 8086:4410 | Intel      | Wireless 3165                | 313   | iwlwifi    | D7D4C28D2D |
| 8086:4239 | 8086:1311 | Intel      | Centrino Advanced-N 6200     | 307   | iwlwifi    | 9635709179 |
| 8086:4232 | 8086:1201 | Intel      | WiFi Link 5100               | 305   | iwlwifi    | 2E325CDDC1 |
| 168c:0034 | 105b:e052 | Qualcom... | AR9462 Wireless Network A... | 300   | ath9k      | B732F94275 |
| 168c:002b | 17aa:30a1 | Qualcom... | AR9285 Wireless Network A... | 299   | ath9k      | CEAF1A4989 |
| 8086:0082 | 8086:1321 | Intel      | Centrino Advanced-N 6205 ... | 295   | iwlwifi    | D1D0976880 |
| 10ec:c821 | 17aa:c024 | Realtek... | RTL8821CE 802.11ac PCIe W... | 294   | rtl8821ce  | AB6647F9DA |
| 8086:02f0 | 8086:0074 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 294   | iwlwifi    | B7EC4606A3 |
| 168c:002b | 1a3b:2c37 | Qualcom... | AR9285 Wireless Network A... | 286   | ath9k      | 438D785F0E |
| 8086:24fd | 8086:0050 | Intel      | Wireless 8265 / 8275         | 283   | iwlwifi    | A92377CB2A |
| 8086:2526 | 8086:0014 | Intel      | Wireless-AC 9260             | 271   | iwlwifi    | 62C94909C7 |
| 8086:4238 | 8086:1111 | Intel      | Centrino Ultimate-N 6300     | 271   | iwlwifi    | 5DC4A1E557 |
| 14e4:4727 | 103c:1483 | Broadcom   | BCM4313 802.11bgn Wireles... | 264   | wl         | 0245DA9040 |
| 168c:002e | 105b:e034 | Qualcom... | AR9287 Wireless Network A... | 264   | ath9k      | C172C655DE |
| 8086:08b2 | 8086:c270 | Intel      | Wireless 7260                | 260   | iwlwifi    | F17B6F7270 |
| 10ec:b723 | 17aa:b736 | Realtek... | RTL8723BE PCIe Wireless N... | 258   | rtl8723be  | B1B8196F26 |
| 8086:422b | 8086:1121 | Intel      | Centrino Ultimate-N 6300     | 257   | iwlwifi    | EE6C9C38B0 |
| 168c:003e | 11ad:0807 | Qualcom... | QCA6174 802.11ac Wireless... | 253   | ath10k_pci | 8D643F3501 |
| 8086:24fd | 8086:0110 | Intel      | Wireless 8265 / 8275         | 253   | iwlwifi    | 423B514D2B |
| 14e4:4315 | 1028:000c | Broadco... | BCM4312 802.11b/g LP-PHY     | 250   | wl         | F0D0F92FD9 |
| 8086:0887 | 8086:4062 | Intel      | Centrino Wireless-N 2230     | 250   | iwlwifi    | A70D378DD0 |
| 8086:08b1 | 8086:4470 | Intel      | Wireless 7260                | 250   | iwlwifi    | AC79B35DFD |
| 168c:0032 | 11ad:6617 | Qualcom... | AR9485 Wireless Network A... | 246   | ath9k      | 069EA1CB31 |
| 8086:4229 | 8086:1101 | Intel      | PRO/Wireless 4965 AG or A... | 243   | iwl4965    | 3B7266D323 |
| 8086:0082 | 8086:1301 | Intel      | Centrino Advanced-N 6205 ... | 241   | iwlwifi    | 0233ED2211 |
| 168c:003e | 1028:0310 | Qualcom... | QCA6174 802.11ac Wireless... | 235   | ath10k_pci | 93BA5B0A6F |
| 10ec:b723 | 11ad:1723 | Realtek... | RTL8723BE PCIe Wireless N... | 232   | rtl8723be  | DCD714D5FA |
| 168c:0036 | 17aa:4026 | Qualcom... | QCA9565 / AR9565 Wireless... | 230   | ath9k      | EB9AAA55EA |
| 8086:0896 | 8086:5005 | Intel      | Centrino Wireless-N 130      | 228   | iwlwifi    | B41629F18A |
| 10ec:b822 | 103c:831b | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 220   | rtwpci     | D3A001E377 |
| 168c:002b | 105b:e035 | Qualcom... | AR9285 Wireless Network A... | 218   | ath9k      | DA7BA5D53F |
| 8086:0084 | 8086:1315 | Intel      | Centrino Wireless-N 1000 ... | 213   | iwlwifi    | DACA4B86FC |
| 8086:095b | 8086:5210 | Intel      | Wireless 7265                | 207   | iwlwifi    | 6131E3C22A |
| 10ec:c821 | 1a3b:3040 | Realtek... | RTL8821CE 802.11ac PCIe W... | 206   | rtl8821ce  | AF8045A7B3 |
| 168c:0032 | 1a3b:1186 | Qualcom... | AR9485 Wireless Network A... | 205   | ath9k      | 08930695BC |
| 8086:095a | 8086:5410 | Intel      | Wireless 7265                | 204   | iwlwifi    | 14584EE6C7 |
| 168c:001c | 1a3b:1026 | Qualcom... | AR242x / AR542x Wireless ... | 203   | ath5k      | 1A587EFF16 |
| 8086:24f3 | 8086:0010 | Intel      | Wireless 8260                | 203   | iwlwifi    | C0C2CADFF1 |
| 8086:24f3 | 8086:0050 | Intel      | Wireless 8260                | 199   | iwlwifi    | F972F7D9BA |
| 14e4:4727 | 103c:145c | Broadcom   | BCM4313 802.11bgn Wireles... | 198   | wl         | E96260CFB9 |
| 8086:08b1 | 8086:4070 | Intel      | Wireless 7260                | 198   | iwlwifi    | 679F6F3259 |
| 14e4:4727 | 1028:0010 | Broadcom   | BCM4313 802.11bgn Wireles... | 192   | wl         | E58B9D7EA5 |
| 8086:06f0 | 8086:0074 | Intel      | Comet Lake PCH CNVi WiFi     | 192   | iwlwifi    | 3A3BF28C3A |
| 168c:0032 | 103c:1838 | Qualcom... | AR9485 Wireless Network A... | 187   | ath9k      | 1345E7109D |
| 168c:0032 | 11ad:6627 | Qualcom... | AR9485 Wireless Network A... | 185   | ath9k      | 6C0B7D6353 |
| 10ec:8179 | 103c:197d | Realtek... | RTL8188EE Wireless Networ... | 184   | rtl8188ee  | 8369C42CE2 |
| 10ec:8821 | 17aa:a814 | Realtek... | RTL8821AE 802.11ac PCIe W... | 183   | rtl8821ae  | 0540D35606 |
| 168c:002b | 103c:3040 | Qualcom... | AR9285 Wireless Network A... | 181   | ath9k      | 4D1F768F1A |
| 168c:0042 | 1a3b:2b31 | Qualcom... | QCA9377 802.11ac Wireless... | 180   | ath10k_pci | C323A8132A |
| 168c:0032 | 103c:1785 | Qualcom... | AR9485 Wireless Network A... | 177   | ath9k      | CD6682785D |
| 8086:08b3 | 8086:8470 | Intel      | Wireless 3160                | 176   | iwlwifi    | 6A14872523 |
| 10ec:b723 | 103c:2231 | Realtek... | RTL8723BE PCIe Wireless N... | 174   | rtl8723be  | C80A118E90 |
| 8086:24f3 | 8086:0130 | Intel      | Wireless 8260                | 173   | iwlwifi    | CAD013A6A5 |
| 168c:001c | 1468:0428 | Qualcom... | AR242x / AR542x Wireless ... | 171   | ath5k      | 9357025BC9 |
| 8086:08b4 | 8086:8270 | Intel      | Wireless 3160                | 171   | iwlwifi    | 09CC2AED35 |
| 8086:4222 | 103c:135c | Intel      | PRO/Wireless 3945ABG [Gol... | 171   | iwl3945    | B30D13BBBA |
| 10ec:b822 | 17aa:b023 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 170   | rtwpci     | 4DE4650899 |
| 14e4:4365 | 103c:804a | Broadcom   | BCM43142 802.11b/g/n         | 169   | wl         | 7493540206 |
| 168c:002b | 105b:e017 | Qualcom... | AR9285 Wireless Network A... | 169   | ath9k      | B5D343A89A |
| 8086:24f3 | 8086:1010 | Intel      | Wireless 8260                | 166   | iwlwifi    | BB92AB2244 |
| 168c:003e | 1a56:143a | Qualcom... | QCA6174 802.11ac Wireless... | 165   | ath10k_pci | C2E884F793 |
| 8086:08ae | 8086:1005 | Intel      | Centrino Wireless-N 100      | 163   | iwlwifi    | 1551840210 |
| 8086:08b3 | 8086:0070 | Intel      | Wireless 3160                | 163   | iwlwifi    | 1E178FE783 |
| 8086:2723 | 1a56:1654 | Intel      | Wi-Fi 6 AX200                | 163   | iwlwifi    | 9CDE952049 |
| 10ec:b723 | 103c:81c1 | Realtek... | RTL8723BE PCIe Wireless N... | 162   | rtl8723be  | 7D85368E1C |
| 10ec:b822 | 1a3b:2950 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 162   | rtw_pci    | F504E72617 |
| 168c:002b | 105b:e025 | Qualcom... | AR9285 Wireless Network A... | 162   | ath9k      | 47EC573607 |
| 168c:0032 | 1028:0209 | Qualcom... | AR9485 Wireless Network A... | 160   | ath9k      | 6C15B9E41A |
| 168c:0032 | 17aa:3218 | Qualcom... | AR9485 Wireless Network A... | 160   | ath9k      | 5872E567EC |
| 168c:002b | 103c:1461 | Qualcom... | AR9285 Wireless Network A... | 159   | ath9k      | DEDDBF979A |
| 10ec:c822 | 1058:1e25 | Realtek... | RTL8822CE 802.11ac PCIe W... | 152   | rtw88_8... | 9908BA82E9 |
| 8086:a370 | 8086:4030 | Intel      | Cannon Lake PCH CNVi WiFi    | 152   | iwlwifi    | AC76D208AB |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1502 | 17aa:21f3 | Intel      | 82579LM Gigabit Network C... | 488   | e1000e     | C9503690D6 |
| 8086:1502 | 17aa:21ce | Intel      | 82579LM Gigabit Network C... | 412   | e1000e     | AEF8C27B50 |
| 8086:10ea | 17aa:2153 | Intel      | 82577LM Gigabit Network C... | 258   | e1000e     | 5DC4A1E557 |
| 8086:10f5 | 17aa:20ee | Intel      | 82567LM Gigabit Network C... | 200   | e1000e     | DB936567F0 |
| 8086:1502 | 1028:0493 | Intel      | 82579LM Gigabit Network C... | 135   | e1000e     | 33617DD1A8 |
| 8086:10ea | 1028:040a | Intel      | 82577LM Gigabit Network C... | 130   | e1000e     | 576A6491F3 |
| 8086:1502 | 1028:0534 | Intel      | 82579LM Gigabit Network C... | 116   | e1000e     | 98420A7D92 |
| 8086:10f5 | 1028:0233 | Intel      | 82567LM Gigabit Network C... | 106   | e1000e     | 2A4C5F6EEC |
| 8086:1502 | 103c:161c | Intel      | 82579LM Gigabit Network C... | 100   | e1000e     | 701E56A49F |
| 8086:1502 | 103c:179b | Intel      | 82579LM Gigabit Network C... | 94    | e1000e     | 7D39BC1331 |
| 8086:1049 | 17aa:20b9 | Intel      | 82566MM Gigabit Network C... | 80    | e1000e     | E1B3B6E090 |
| 8086:1502 | 1028:0535 | Intel      | 82579LM Gigabit Network C... | 60    | e1000e     | 2E9B8200A9 |
| 8086:10ea | 103c:172a | Intel      | 82577LM Gigabit Network C... | 56    | e1000e     | 9635709179 |
| 8086:10c4 | 103c:30d8 | Intel      | 82562GT 10/100 Network Co... | 53    | e1000e     | E6E060CA51 |
| 14e4:170c | 1025:0090 | Broadcom   | BCM4401-B0 100Base-TX        | 51    | b44        | 4A0EE2EAA5 |
| 8086:1502 | 1028:0494 | Intel      | 82579LM Gigabit Network C... | 51    | e1000e     | E58B9D7EA5 |
| 8086:1502 | 10cf:161b | Intel      | 82579LM Gigabit Network C... | 49    | e1000e     | B2D4A08D24 |
| 8086:10ea | 103c:7008 | Intel      | 82577LM Gigabit Network C... | 46    | e1000e     | 383932E73B |
| 8086:10eb | 103c:1471 | Intel      | 82577LC Gigabit Network C... | 45    | e1000e     | 523C397AB6 |
| 8086:1502 | 10f7:8338 | Intel      | 82579LM Gigabit Network C... | 45    | e1000e     | 621E3366FD |
| 8086:10ea | 1028:040b | Intel      | 82577LM Gigabit Network C... | 42    | e1000e     | 6902EB0F50 |
| 8086:1502 | 103c:162b | Intel      | 82579LM Gigabit Network C... | 42    | e1000e     | E96260CFB9 |
| 8086:10f5 | 1028:024f | Intel      | 82567LM Gigabit Network C... | 41    | e1000e     | 3BDEE6855C |
| 14e4:170c | 1028:01f5 | Broadcom   | BCM4401-B0 100Base-TX        | 39    | b44        | 32C3521A2E |
| 8086:1502 | 1028:0492 | Intel      | 82579LM Gigabit Network C... | 39    | e1000e     | B9503F222C |
| 8086:1502 | 103c:1618 | Intel      | 82579LM Gigabit Network C... | 38    | e1000e     | EA1BD5E314 |
| 8086:1503 | 10cf:161c | Intel      | 82579V Gigabit Network Co... | 38    | e1000e     | 57D55A953C |
| 10ec:8168 | 17aa:505b | Realtek... | RTL8111/8168/8411 PCI Exp... | 37    | r8169      | CC35722C1F |
| 14e4:170c | 1028:01af | Broadcom   | BCM4401-B0 100Base-TX        | 37    | b44        | 3EB7729825 |
| 8086:10ea | 103c:1521 | Intel      | 82577LM Gigabit Network C... | 36    | e1000e     | FFC46C9472 |
| 8086:1502 | 103c:18df | Intel      | 82579LM Gigabit Network C... | 36    | e1000e     | 3E6A2F7B59 |
| 14e4:170c | 103c:30a2 | Broadcom   | BCM4401-B0 100Base-TX        | 35    | b44        | 204F122174 |
| 8086:1503 | 103c:17ab | Intel      | 82579V Gigabit Network Co... | 34    | e1000e     | 2B341B7BF9 |
| 10ec:8136 | 103c:3567 | Realtek... | RTL810xE PCI Express Fast... | 33    | r8169      | C774724C5F |
| 8086:10ea | 10cf:1574 | Intel      | 82577LM Gigabit Network C... | 33    | e1000e     | F220F9AC45 |
| 8086:10f5 | 103c:30db | Intel      | 82567LM Gigabit Network C... | 33    | e1000e     | A4CEF366BC |
| 8086:1502 | 1028:04a3 | Intel      | 82579LM Gigabit Network C... | 33    | e1000e     | EE6C9C38B0 |
| 8086:1502 | 1028:0532 | Intel      | 82579LM Gigabit Network C... | 33    | e1000e     | 04D10F10D8 |
| 8086:10ea | 1028:0410 | Intel      | 82577LM Gigabit Network C... | 32    | e1000e     | 4135CD0970 |
| 8086:1502 | 103c:17a7 | Intel      | 82579LM Gigabit Network C... | 32    | e1000e     | A66A0DF735 |
| 8086:1502 | 103c:17df | Intel      | 82579LM Gigabit Network C... | 32    | e1000e     | BF8F2C3CB2 |
| 8086:1503 | 103c:1619 | Intel      | 82579V Gigabit Network Co... | 32    | e1000e     | 523614FEE6 |
| 8086:10f5 | 1028:024d | Intel      | 82567LM Gigabit Network C... | 31    | e1000e     | 98D088D90D |
| 8086:1502 | 1028:0533 | Intel      | 82579LM Gigabit Network C... | 31    | e1000e     | 7F740D929F |
| 8086:10bf | 17aa:20ee | Intel      | 82567LF Gigabit Network C... | 30    | e1000e     | B4F44D7932 |
| 8086:1049 | 17aa:20de | Intel      | 82566MM Gigabit Network C... | 28    | e1000e     | 11028F0EE3 |
| 8086:1092 | 1179:ff10 | Intel      | PRO/100 VE Network Connec... | 28    | e100       | B6FB3D3EC3 |
| 8086:1503 | 103c:161d | Intel      | 82579V Gigabit Network Co... | 27    | e1000e     | 06BC21DB81 |
| 10ec:8168 | 17aa:3810 | Realtek... | RTL8111/8168/8411 PCI Exp... | 25    | r8169      | BD075D1778 |
| 8086:1049 | 103c:30c5 | Intel      | 82566MM Gigabit Network C... | 23    | e1000e     | 7E17CF2706 |
| 8086:1503 | 103c:179c | Intel      | 82579V Gigabit Network Co... | 22    | e1000e     | 687AED65CF |
| 8086:1502 | 103c:1631 | Intel      | 82579LM Gigabit Network C... | 21    | e1000e     | ADA2C0663B |
| 8086:1503 | 1179:0001 | Intel      | 82579V Gigabit Network Co... | 21    | e1000e     | 81FFC7BA9E |
| 14e4:170c | 1028:022a | Broadco... | BCM4401-B0 100Base-TX        | 20    | b44        | 6D6B004B73 |
| 8086:1049 | 103c:30be | Intel      | 82566MM Gigabit Network C... | 20    | e1000e     | 5910FA85E5 |
| 10de:0269 | 103c:30b7 | Nvidia     | MCP51 Ethernet Controller    | 19    | forcedeth  | C28788427E |
| 10ec:8168 | 17aa:3819 | Realtek... | RTL8111/8168/8411 PCI Exp... | 19    | r8169      | FBA07779E2 |
| 8086:1502 | 1028:04a9 | Intel      | 82579LM Gigabit Network C... | 19    | e1000e     | 41E38AE50A |
| 8086:1502 | 1028:053e | Intel      | 82579LM Gigabit Network C... | 19    | e1000e     | 2711A6B6A7 |
| 8086:10ea | 103c:7007 | Intel      | 82577LM Gigabit Network C... | 18    | e1000e     | 6604EBCF44 |
| 14e4:170c | 1028:01f1 | Broadcom   | BCM4401-B0 100Base-TX        | 17    | b44        | B032DCE890 |
| 8086:1502 | 1028:04a4 | Intel      | 82579LM Gigabit Network C... | 17    | e1000e     | 117E981EF3 |
| 8086:1502 | 103c:162a | Intel      | 82579LM Gigabit Network C... | 17    | e1000e     | 7FC1A2DF02 |
| 8086:1502 | 103c:176c | Intel      | 82579LM Gigabit Network C... | 17    | e1000e     | 9B49622881 |
| 14e4:170c | 1028:01f2 | Broadco... | BCM4401-B0 100Base-TX        | 16    | b44        | D115C79F7A |
| 8086:10ea | 1028:040c | Intel      | 82577LM Gigabit Network C... | 16    | e1000e     | CF45F57A60 |
| 8086:10eb | 1179:0001 | Intel      | 82577LC Gigabit Network C... | 16    | e1000e     | 0C557895BE |
| 8086:1502 | 103c:176b | Intel      | 82579LM Gigabit Network C... | 16    | e1000e     | 1125997CC5 |
| 8086:1503 | 1179:0002 | Intel      | 82579V Gigabit Network Co... | 16    | e1000e     | 43A653B86D |
| 14e4:170c | 1028:01c9 | Broadco... | BCM4401-B0 100Base-TX        | 15    | b44        | 827A52E58E |
| 14e4:170c | 1028:01cd | Broadco... | BCM4401-B0 100Base-TX        | 15    | b44        | A3087D50B3 |
| 8086:1092 | 103c:30bb | Intel      | PRO/100 VE Network Connec... | 15    | e100       | 5F6D9F025A |
| 8086:10f5 | 103c:30e7 | Intel      | 82567LM Gigabit Network C... | 15    | e1000e     | 889E5E50E0 |
| 8086:1533 | 1ab6:0214 | Intel      | I210 Gigabit Network Conn... | 15    | igb        | C6CC14214F |
| 14e4:170c | 1028:0228 | Broadco... | BCM4401-B0 100Base-TX        | 14    | b44        | 08AA727FE5 |
| 1106:3065 | 1509:1d41 | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 13    | via_rhine  | E45A412C3D |
| 14e4:170c | 1028:01d4 | Broadcom   | BCM4401-B0 100Base-TX        | 13    | b44        | 7A817A0426 |
| 8086:1092 | 104d:81ef | Intel      | PRO/100 VE Network Connec... | 13    | e100       | 82BD19C032 |
| 8086:1539 | 8086:0000 | Intel      | I211 Gigabit Network Conn... | 13    | igb        | 6F9D6686F3 |
| 10ec:8168 | 103c:228d | Realtek... | RTL8111/8168/8411 PCI Exp... | 12    | r8169      | 286D5773A8 |
| 8086:10ea | 103c:172b | Intel      | 82577LM Gigabit Network C... | 12    | e1000e     | 63CF53773D |
| 8086:1502 | 1028:053f | Intel      | 82579LM Gigabit Network C... | 12    | e1000e     | 8A5E6B4598 |
| 8086:1502 | 103c:1630 | Intel      | 82579LM Gigabit Network C... | 12    | e1000e     | DAE07BF8CB |
| 8086:1533 | ffff:0000 | Intel      | I210 Gigabit Network Conn... | 12    | igb        | F70E13FDBA |
| 8086:10ea | 10f7:8338 | Intel      | 82577LM Gigabit Network C... | 11    | e1000e     | E6E31DE556 |
| 8086:10ea | 1179:0001 | Intel      | 82577LM Gigabit Network C... | 11    | e1000e     | AFD83C5750 |
| 8086:10f5 | 103c:30e1 | Intel      | 82567LM Gigabit Network C... | 11    | e1000e     | D54424038E |
| 8086:10f5 | 10f7:8338 | Intel      | 82567LM Gigabit Network C... | 11    | e1000e     | 4502B92271 |
| 10de:0269 | 1025:0112 | Nvidia     | MCP51 Ethernet Controller    | 10    | forcedeth  | 56639ACA29 |
| 8086:1049 | 103c:30c3 | Intel      | 82566MM Gigabit Network C... | 10    | e1000e     | 2B1FFEE1D7 |
| 8086:10c4 | 103c:30d7 | Intel      | 82562GT 10/100 Network Co... | 10    | e1000e     | 551053E9D6 |
| 8086:10f5 | 103c:30dc | Intel      | 82567LM Gigabit Network C... | 10    | e1000e     | DDDE2864E6 |
| 8086:10f5 | 104d:9025 | Intel      | 82567LM Gigabit Network C... | 10    | e1000e     | 13D58B8D90 |
| 8086:1502 | 1179:0002 | Intel      | 82579LM Gigabit Network C... | 10    | e1000e     | 5169C2F96A |
| 8086:1049 | 103c:30c9 | Intel      | 82566MM Gigabit Network C... | 9     | e1000e     | 03E5A5DF0E |
| 8086:10eb | 104d:905a | Intel      | 82577LC Gigabit Network C... | 9     | e1000e     | 537D05799C |
| 8086:10f5 | 1028:0277 | Intel      | 82567LM Gigabit Network C... | 9     | e1000e     | E280D6C346 |
| 8086:1502 | 1028:04b4 | Intel      | 82579LM Gigabit Network C... | 9     | e1000e     | 0FDF8DB86A |
| 8086:1502 | 1179:0001 | Intel      | 82579LM Gigabit Network C... | 9     | e1000e     | F7C456B329 |
| 14e4:1713 | 103c:30c2 | Broadco... | NetLink BCM5906M Fast Eth... | 8     | tg3        | C654E5D5B6 |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:145a | 1022:145a | AMD        | Zeppelin/Raven/Raven2 PCI... | 39    |            | 065A3089D4 |
| 1022:1455 | 1022:1455 | AMD        | Zeppelin/Renoir PCIe Dumm... | 12    |            | B79E897508 |
| 1022:1485 | 1558:50f0 | AMD        | Starship/Matisse Reserved... | 12    |            | B34A66FE8D |
| 1022:148a | 1558:50f0 | AMD        | Starship/Matisse PCIe Dum... | 12    |            | B34A66FE8D |
| 8086:5a8e | 8086:7270 | Intel      | Non-Essential Instrumenta... | 9     | intel_t... | 7B973470B7 |
| 8086:9d26 |           | Intel      | Skylake-U/Y Northpeak        | 7     | intel_t... | 770738F40F |
| 1022:1455 | 1025:1246 | AMD        | Zeppelin/Renoir PCIe Dumm... | 5     |            | 03FACC3040 |
| 1022:145a | 1025:1246 | AMD        | Zeppelin/Raven/Raven2 PCI... | 5     |            | 03FACC3040 |
| 1022:145a | 103c:879c | AMD        | Zeppelin/Raven/Raven2 PCI... | 3     |            | 7D1F6E5B43 |
| 1022:1455 | 1043:8747 | AMD        | Zeppelin/Renoir PCIe Dumm... | 2     |            | 62042D8665 |
| 1022:145a | 1043:8747 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 62042D8665 |
| 1022:145a | 17aa:3803 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | C9E7AE41BA |
| 1022:145a | 1d05:1111 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | E9A891227F |
| 8086:318e |           | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_t... | 7BDEC3EB56 |
| 8086:a126 |           | Intel      | 100 Series/C230 Series Ch... | 2     | intel_t... | E5B46A78DE |
| 1022:145a | 152d:1315 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 6DB19936AC |
| 1022:145a | 1d05:1100 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | C04E6F75E2 |
| 1022:1485 | 1022:1485 | AMD        | Starship/Matisse Reserved... | 1     |            | B9C02872AA |
| 1022:148a | 1022:148a | AMD        | Starship/Matisse PCIe Dum... | 1     |            | B9C02872AA |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15e6 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Non-S... | 171   | i2c_amd... | AF8045A7B3 |
| 8086:9d24 |           | Intel      | Skylake-U/Y SPI Controller   | 39    |            | 1AB69568A5 |
| 106b:1801 | 106b:1801 | Apple      | T2 Bridge Controller         | 36    | apple_bce  | 2BDDF8B98A |
| 106b:1802 | 106b:1802 | Apple      | T2 Secure Enclave Processor  | 36    |            | 2BDDF8B98A |
| 1022:15e6 | 103c:85ea | AMD        | Raven/Raven2/Renoir Non-S... | 33    | i2c_amd... | D03BDBF1DA |
| 8086:22d8 | 103c:813e | Intel      | Integrated Sensor Solution   | 28    | intel_i... | 71120B9356 |
| 8086:9d35 | 17aa:2238 | Intel      | Sunrise Point-LP Integrat... | 27    | intel_i... | CAD013A6A5 |
| 8086:9d35 | 1028:0740 | Intel      | Sunrise Point-LP Integrat... | 26    | intel_i... | E36E444BAC |
| 1022:15e6 | 1025:1456 | AMD        | Raven/Raven2/Renoir Non-S... | 18    | i2c_amd... | 80CF3DC8E7 |
| 8086:9d35 | 103c:83b2 | Intel      | Sunrise Point-LP Integrat... | 12    | intel_i... | 1EEA89F8BB |
| 8086:22d8 | 1043:1bdd | Intel      | Integrated Sensor Solution   | 11    | intel_i... | 866C75D8E6 |
| 8086:9d35 | 1028:0804 | Intel      | Sunrise Point-LP Integrat... | 11    | intel_i... | C15C1DA104 |
| 8086:9d35 | 8086:9d35 | Intel      | Sunrise Point-LP Integrat... | 11    | intel_i... | B0C32B29BB |
| 8086:9d35 | 1028:073b | Intel      | Sunrise Point-LP Integrat... | 8     | intel_i... | E14ACDFFAD |
| 8086:9d35 | 103c:80fc | Intel      | Sunrise Point-LP Integrat... | 8     | intel_i... | 09240A2A3F |
| 8086:9d35 | 1028:0742 | Intel      | Sunrise Point-LP Integrat... | 7     | intel_i... | 2FC3CACC51 |
| 8086:22d8 | 1043:1400 | Intel      | Integrated Sensor Solution   | 5     | intel_i... | 781A13F986 |
| 8086:9d35 | 17aa:3812 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | AAEF1C5AE7 |
| 8086:9d35 | 1028:0741 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | A87267AB19 |
| 8086:9d35 | 1028:0743 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 7EC4FFF3D3 |
| 8086:9d35 | 1028:0808 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 83C30B9084 |
| 8086:9d35 | 103c:8470 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 6C42757430 |
| 8086:a135 | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 4     | intel_i... | 41FC496B9F |
| 8086:22d8 | 103c:8042 | Intel      | Integrated Sensor Solution   | 3     | intel_i... | 45359B58FC |
| 8086:22d8 | 1043:13a0 | Intel      | Integrated Sensor Solution   | 3     | intel_i... | 036F4F2304 |
| 8086:22d8 | 8086:7270 | Intel      | Integrated Sensor Solution   | 3     | intel_i... | 55179F361C |
| 8086:9d35 | 1028:0744 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 2CF1F86B67 |
| 8086:9d35 | 1028:07a4 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | C5396B5734 |
| 8086:9d35 | 1028:07ba | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 271C309BFA |
| 8086:9d35 | 1179:0001 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 4E2285206E |
| 1022:15e4 | 1028:090c | AMD        | Raven/Raven2/Renoir Senso... | 2     |            | B64ACF39C9 |
| 1022:15e6 | 103c:87ce | AMD        | Raven/Raven2/Renoir Non-S... | 2     | i2c_amd... | 527EBE7BDE |
| 1022:15e6 | 103c:87d2 | AMD        | Raven/Raven2/Renoir Non-S... | 2     | i2c_amd... | BBB889A0CA |
| 1022:15e6 | 103c:87d3 | AMD        | Raven/Raven2/Renoir Non-S... | 2     | i2c_amd... | 756904BEC1 |
| 8086:22d8 | 1028:06ea | Intel      | Integrated Sensor Solution   | 2     | intel_i... | 57FDB94877 |
| 8086:9d35 | 1028:081d | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | B314102502 |
| 8086:9d35 | 1028:0823 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | FB785080A3 |
| 8086:9d35 | 103c:8146 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 3C4E95F3C6 |
| 8086:9d35 | 103c:83b3 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 5570800F48 |
| 8086:9d35 | 10cf:18d0 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 50C2127F6C |
| 8086:9d35 | 17aa:2237 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 19E1E784FC |
| 8086:9d35 | 17aa:506c | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | A68BF7CFC5 |
| 1022:15e6 | 1025:1458 | AMD        | Raven/Raven2/Renoir Non-S... | 1     | i2c_amd... | 50F65ED348 |
| 1022:15e6 | 103c:85ec | AMD        | Raven/Raven2/Renoir Non-S... | 1     | i2c_amd... | 214A977789 |
| 1022:15e6 | 103c:87d1 | AMD        | Raven/Raven2/Renoir Non-S... | 1     | i2c_amd... | FD8AFA6F02 |
| 10ec:0119 | 1025:009f | Realtek... |                              | 1     |            | 1312407631 |
| 1180:8476 |           | Ricoh      |                              | 1     |            | C215EA9980 |
| 14e4:8100 | 0000:8100 | Broadcom   |                              | 1     |            | 784397ABB8 |
| 1524:1412 |           | ENE Tec... | CB-712/4 Cardbus Controller  | 1     |            | 1312407631 |
| 1cbc:0100 | 1cbc:0000 |            |                              | 1     |            | 3CFCCD6F1C |
| 8086:22d8 | 103c:8173 | Intel      | Integrated Sensor Solution   | 1     | intel_i... | F487E91BF8 |
| 8086:22d8 | 1071:a126 | Intel      | Integrated Sensor Solution   | 1     | intel_i... | F2981C1775 |
| 8086:22d8 | 10cf:191b | Intel      | Integrated Sensor Solution   | 1     | intel_i... | 6D19311F7E |
| 8086:22d8 | 1179:f860 | Intel      | Integrated Sensor Solution   | 1     | intel_i... | 1148737572 |
| 8086:9d35 | 1028:06d6 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | A8551FD24E |
| 8086:9d35 | 1028:073e | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | D799EB63AF |
| 8086:9d35 | 1028:073f | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | F0F4829A9A |
| 8086:9d35 | 1028:074f | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 4F8F1DD9C8 |
| 8086:9d35 | 1028:07aa | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 1DC7215E55 |
| 8086:9d35 | 1028:07ec | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | BF57A8FDAE |
| 8086:9d35 | 1028:0809 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | DA9284305A |
| 8086:9d35 | 103c:8181 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 49A6D8DEC1 |
| 8086:9d35 | 103c:8197 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 910D564E8E |
| 8086:9d35 | 103c:8198 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 236EFC033E |
| 8086:9d35 | 1043:1160 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 9D6A79D7AC |
| 8086:9d35 | 1071:a133 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | F35B5EC303 |
| 8086:9d35 | 17aa:2241 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 726380658A |
| 8086:9d35 | 17aa:2259 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 7550150FB5 |
| 8086:9d35 | 17aa:504c | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 240BAB94C7 |
| 8086:a124 |           | Intel      | 100 Series/C230 Series Ch... | 1     |            | BF6B408B8A |
| 8086:a135 | 8086:a135 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_i... | CCDADF3870 |

### Performance counters (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27a3 |           | Intel      | 945GM/GU Chipset Hardware... | 44    |            | CC14C7FA2E |
| 8086:1907 | 8086:2015 | Intel      | Performance counters         | 2     |            | 4D3FFA307C |
| 8086:0107 |           | Intel      | Performance counters         | 1     |            | 8A4C419DA7 |
| 8086:0e30 | 1558:0270 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 1694F6A1B4 |
| 8086:0e34 | 1558:0270 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 1694F6A1B4 |
| 8086:0e36 | 1558:0270 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 1694F6A1B4 |
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
| 1106:5364 |           | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 40    |            | 01E1F5151C |
| 1106:5364 | 103c:3030 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 9     |            | E81CAC058D |
| 1106:5336 |           | VIA Tec... | K8M890CE I/O APIC Interru... | 7     |            | 20512BBBE4 |
| 1106:5364 | 1734:10f7 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 7     |            | 3200F41CF0 |
| 1106:5353 | 17aa:388a | VIA Tec... | VX800/VX820 APIC and Cent... | 3     |            | 4762847735 |
| 1106:5353 | 144d:c04e | VIA Tec... | VX800/VX820 APIC and Cent... | 2     |            | 085B83A79C |
| 1106:5238 | 1734:1093 | VIA Tec... | K8T890 I/O APIC Interrupt... | 1     |            | E9825FB39A |
| 1106:5327 |           | VIA Tec... | P4M890 I/O APIC Interrupt... | 1     |            | 7464ED3C9D |
| 1106:5353 |           | VIA Tec... | VX800/VX820 APIC and Cent... | 1     |            | 77A2A10D46 |
| 1106:5364 | 1509:5364 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 1     |            | D514055CD5 |
| 8086:0e2c | 1558:0270 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1694F6A1B4 |
| 8086:342d | 0058:0003 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | 7F55996B62 |
| 8086:3c2c | 1558:0270 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | DE166D9BF2 |

### Rf controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:7305 | 10ec:7305 | Realtek... | UWB Radio                    | 1     | whci, w... | 6F4E5774F9 |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:16bc | 1025:0647 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 377   | sdhci_pci  | B732F94275 |
| 14e4:16bc | 14e4:0000 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 221   | sdhci_pci  | A53D0DE98A |
| 197b:2381 | 1043:1a07 | JMicron... | Standard SD Host Controller  | 219   | sdhci_pci  | 11F1CDC49A |
| 14e4:16bc | 1025:0504 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 196   | sdhci_pci  | 85BCF858C5 |
| 1180:0822 | 17aa:20c8 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 195   | sdhci_pci  | DB936567F0 |
| 8086:9d2d | 8086:9d2d | Intel      | Sunrise Point-LP Secure D... | 190   | sdhci_pci  | AF70469300 |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 163   | sdhci_pci  | 83BAF92C7E |
| 1217:8221 | 1028:0493 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 133   | sdhci_pci  | 33617DD1A8 |
| 14e4:16bc | 1025:0775 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 131   | sdhci_pci  | 98166600FA |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 130   | sdhci_pci  | 71A92492E3 |
| 1180:e822 | 1028:040a | Ricoh      | MMC/SD Host Controller       | 129   | sdhci_pci  | 576A6491F3 |
| 1022:7813 | 17aa:3801 | AMD        | FCH SD Flash Controller      | 128   | sdhci_pci  | 779BFC3B47 |
| 1180:e822 | 104d:9071 | Ricoh      | MMC/SD Host Controller       | 123   | sdhci_pci  | 03E0270FDD |
| 104c:803c | 1025:011f | Texas I... | PCIxx12 SDA Standard Comp... | 122   | sdhci_pci  | 6A05B72968 |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 121   | sdhci_pci  | 71A92492E3 |
| 1217:8221 | 1028:0534 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 117   | sdhci_pci  | 98420A7D92 |
| 1180:0822 | 1028:0233 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 107   | sdhci_pci  | 2A4C5F6EEC |
| 8086:31d0 | 8086:7270 | Intel      | SD Host Controller           | 101   | sdhci_pci  | 021617B9A0 |
| 197b:2391 | 103c:161c | JMicron... | Standard SD Host Controller  | 100   | sdhci_pci  | 701E56A49F |
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 99    | sdhci_pci  | 021617B9A0 |
| 197b:2391 | 103c:179b | JMicron... | Standard SD Host Controller  | 91    | sdhci_pci  | 7D39BC1331 |
| 197b:2391 | 103c:17f6 | JMicron... | Standard SD Host Controller  | 85    | sdhci_pci  | D0705EF193 |
| 1217:8621 | 17aa:5068 | O2 Micro   | SD/MMC Card Reader Contro... | 79    | sdhci_pci  | 893F642CBB |
| 1180:0822 | 1028:022f | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 72    | sdhci_pci  | 06130B24C5 |
| 10ec:5209 | 10ec:5209 | Realtek... | RTS5209 PCI Express Card ... | 71    | rtsx_pci   | 0233ED2211 |
| 1217:8520 | 1028:05cb | O2 Micro   | SD/MMC Card Reader Contro... | 66    | sdhci_pci  | EF82F4635D |
| 1022:7806 | 1022:7806 | AMD        | FCH SD Flash Controller      | 65    | sdhci_pci  | 08D0784B54 |
| 197b:2391 | 103c:167c | JMicron... | Standard SD Host Controller  | 65    | sdhci_pci  | DEDDBF979A |
| 1217:8520 | 1028:05be | O2 Micro   | SD/MMC Card Reader Contro... | 64    | sdhci_pci  | 6399CECB6F |
| 1180:0822 | 103c:30cc | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 62    | sdhci_pci  | 4E93C68985 |
| 1217:8520 | 1028:062e | O2 Micro   | SD/MMC Card Reader Contro... | 61    | sdhci_pci  | 5F0CE579EC |
| 1217:8221 | 1028:0535 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 59    | sdhci_pci  | 2E9B8200A9 |
| 1217:8520 | 1028:05bd | O2 Micro   | SD/MMC Card Reader Contro... | 59    | sdhci_pci  | E1FA24C279 |
| 1180:0822 | 103c:172a | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 55    | sdhci_pci  | 9635709179 |
| 1180:0843 | 1028:0233 | Ricoh      | R5C843 MMC Host Controller   | 55    | sdhci_pci  | D041B30FAF |
| 1217:7120 | 1179:ff50 | O2 Micro   | Integrated MMC/SD Controller | 55    | sdhci_pci  | FEB13460E8 |
| 1524:0550 | 1025:0090 | ENE Tec... | ENE PCI Secure Digital Ca... | 55    | sdhci_pci  | 4A0EE2EAA5 |
| 8086:9df5 | 8086:7270 | Intel      | BayHubTech Integrated SD ... | 55    | sdhci_pci  | 6AFF8771B1 |
| 1217:8321 | 1028:0494 | O2 Micro   | OZ600RJ0/OZ900RJ0/OZ600RJ... | 51    | sdhci_pci  | E58B9D7EA5 |
| 1217:8621 | 17aa:381f | O2 Micro   | SD/MMC Card Reader Contro... | 49    | sdhci_pci  | C45342870C |
| 104c:803c | 1179:ff00 | Texas I... | PCIxx12 SDA Standard Comp... | 48    | sdhci_pci  | 8E44C9EDAF |
| 1217:8520 | 1028:05ca | O2 Micro   | SD/MMC Card Reader Contro... | 48    | sdhci_pci  | 9E790BA3F0 |
| 17a0:9750 | 17aa:2279 | Genesys... | GL9750 SD Host Controller    | 48    | sdhci_pci  | 2444839350 |
| 1022:7813 | 1025:104b | AMD        | FCH SD Flash Controller      | 47    | sdhci_pci  | 6E75E7C288 |
| 1180:0822 | 103c:7008 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 46    | sdhci_pci  | 383932E73B |
| 10ec:5209 | 103c:3388 | Realtek... | RTS5209 PCI Express Card ... | 45    | rtsx_pci   | 482481E697 |
| 1180:0822 | 1025:011e | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 45    | sdhci_pci  | 3C8537DFE3 |
| 1969:3010 | 1025:076b | Qualcom... | Secure Digital Card Reader   | 44    | sdhci_pci  | 212881FBEB |
| 8086:9d2b | 8086:7270 | Intel      | Skylake-U/Y SCC: eMMC        | 44    | sdhci_pci  | 36AA4B2B34 |
| 1022:7906 | 1043:1291 | AMD        | FCH SD Flash Controller      | 43    | sdhci_pci  | F0E3C5B460 |
| 1180:e822 | 1028:040b | Ricoh      | MMC/SD Host Controller       | 43    | sdhci_pci  | 6902EB0F50 |
| 197b:2381 | 103c:3628 | JMicron... | Standard SD Host Controller  | 43    | sdhci_pci  | DCE60F14E1 |
| 197b:2391 | 103c:162b | JMicron... | Standard SD Host Controller  | 43    | sdhci_pci  | E96260CFB9 |
| 197b:2381 | 1297:2027 | JMicron... | Standard SD Host Controller  | 42    | sdhci_pci  | 5C17F36C61 |
| 197b:2381 | 17aa:212d | JMicron... | Standard SD Host Controller  | 42    | sdhci_pci  | A687D09DE6 |
| 1180:0822 | 103c:30cf | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 41    | sdhci_pci  | CB77A79EE8 |
| 1217:8520 | 17aa:2211 | O2 Micro   | SD/MMC Card Reader Contro... | 41    | sdhci_pci  | 30EDEADDE3 |
| 1217:8621 | 17aa:3824 | O2 Micro   | SD/MMC Card Reader Contro... | 41    | sdhci_pci  | 6E91E6E551 |
| 8086:31cc | 1025:1360 | Intel      | Celeron/Pentium Silver Pr... | 41    | sdhci_pci  | C4FA352D95 |
| 1180:0822 | 1028:024f | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 40    | sdhci_pci  | 3BDEE6855C |
| 197b:2381 | 1558:0801 | JMicron... | Standard SD Host Controller  | 40    | sdhci_pci  | F6E75312A4 |
| 1180:0822 | 1025:0121 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 39    | sdhci_pci  | 5D933E19AC |
| 1217:8221 | 1028:0492 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 39    | sdhci_pci  | B9503F222C |
| 1524:0550 | 1025:009f | ENE Tec... | ENE PCI Secure Digital Ca... | 39    | sdhci_pci  | D38F5B09D2 |
| 8086:2294 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 39    | sdhci_pci  | 044D8CA250 |
| 104c:803c | 1179:ff02 | Texas I... | PCIxx12 SDA Standard Comp... | 38    | sdhci_pci  | 3F0EBD44AD |
| 1217:7120 | 10cf:143d | O2 Micro   | Integrated MMC/SD Controller | 38    | sdhci_pci  | 3B7266D323 |
| 1217:8520 | 17aa:3800 | O2 Micro   | SD/MMC Card Reader Contro... | 38    | sdhci_pci  | D63399B396 |
| 197b:2391 | 103c:1618 | JMicron... | Standard SD Host Controller  | 38    | sdhci_pci  | EA1BD5E314 |
| 1022:7813 | 103c:21f7 | AMD        | FCH SD Flash Controller      | 37    | sdhci_pci  | 814D85CF91 |
| 1180:0822 | 1028:01f5 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 37    | sdhci_pci  | 32C3521A2E |
| 1180:e822 | 103c:146d | Ricoh      | MMC/SD Host Controller       | 37    | sdhci_pci  | 523C397AB6 |
| 1217:8621 | 1217:0002 | O2 Micro   | SD/MMC Card Reader Contro... | 37    | sdhci_pci  | 478CA880AB |
| 197b:2391 | 103c:18df | JMicron... | Standard SD Host Controller  | 37    | sdhci_pci  | 3E6A2F7B59 |
| 1180:0822 | 103c:1521 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 36    | sdhci_pci  | FFC46C9472 |
| 1180:0822 | 1028:01bd | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 35    | sdhci_pci  | 3EB7729825 |
| 1180:0822 | 104d:9035 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 35    | sdhci_pci  | 1A9761824E |
| 1180:0822 | 10f7:8338 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 35    | sdhci_pci  | 4502B92271 |
| 1217:8520 | 1028:05de | O2 Micro   | SD/MMC Card Reader Contro... | 35    | sdhci_pci  | EA59351ECE |
| 8086:9d2d | 8086:7270 | Intel      | Sunrise Point-LP Secure D... | 35    | sdhci_pci  | 4D3FFA307C |
| 1217:8221 | 1028:0532 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 34    | sdhci_pci  | 04D10F10D8 |
| 1217:8221 | 1028:053c | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 34    | sdhci_pci  | EE7236C5D8 |
| 1217:8320 | 1028:04a3 | O2 Micro   | OZ600RJ1/OZ900RJ1 SD/MMC ... | 34    | sdhci_pci  | EE6C9C38B0 |
| 1217:8321 | 1028:049a | O2 Micro   | OZ600RJ0/OZ900RJ0/OZ600RJ... | 34    | sdhci_pci  | 33B9916878 |
| 14e4:16bc | 1025:0500 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 34    | sdhci_pci  | 499479904D |
| 14e4:16bc | 1025:0742 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 34    | sdhci_pci  | 342F07FA37 |
| 197b:2391 | 103c:17a7 | JMicron... | Standard SD Host Controller  | 34    | sdhci_pci  | A66A0DF735 |
| 197b:2391 | 103c:17ab | JMicron... | Standard SD Host Controller  | 34    | sdhci_pci  | 2B341B7BF9 |
| 197b:2391 | 17aa:3976 | JMicron... | Standard SD Host Controller  | 34    | sdhci_pci  | 94D22E7673 |
| 104c:803c | 1179:ff10 | Texas I... | PCIxx12 SDA Standard Comp... | 33    | sdhci_pci  | B6FB3D3EC3 |
| 1180:0822 | 103c:30db | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 33    | sdhci_pci  | A4CEF366BC |
| 1180:e822 | 1028:0410 | Ricoh      | MMC/SD Host Controller       | 33    | sdhci_pci  | 4135CD0970 |
| 1217:8221 | 1028:0533 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 33    | sdhci_pci  | 7F740D929F |
| 1217:8321 | 1028:049b | O2 Micro   | OZ600RJ0/OZ900RJ0/OZ600RJ... | 33    | sdhci_pci  | 989DD7D36F |
| 1217:8520 | 1028:05cc | O2 Micro   | SD/MMC Card Reader Contro... | 33    | sdhci_pci  | 2293B2D4C4 |
| 8086:02f5 | 103c:86a0 | Intel      | Comet Lake PCH-LP SCS3       | 33    | sdhci_pci  | DEB906B69F |
| 1217:8621 | 17aa:5072 | O2 Micro   | SD/MMC Card Reader Contro... | 32    | sdhci_pci  | 13C09F3C3E |
| 14e4:16bc | 1025:0605 | Broadco... | BCM57765/57785 SDXC/MMC C... | 32    | sdhci_pci  | 853337664F |
| 197b:2391 | 103c:1619 | JMicron... | Standard SD Host Controller  | 32    | sdhci_pci  | 523614FEE6 |
| 197b:2391 | 103c:17df | JMicron... | Standard SD Host Controller  | 32    | sdhci_pci  | BF8F2C3CB2 |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9da4 | 8086:7270 | Intel      | Cannon Point-LP SPI Contr... | 246   |            | 6AFF8771B1 |
| 8086:a324 | 8086:7270 | Intel      | Cannon Lake PCH SPI Contr... | 138   | intel_s... | 00041CC413 |
| 8086:a324 | 1025:1331 | Intel      | Cannon Lake PCH SPI Contr... | 119   | intel_spi  | 38688703F4 |
| 8086:a368 | 1025:1331 | Intel      | Cannon Lake PCH Serial IO... | 119   | intel_lpss | 38688703F4 |
| 8086:a369 | 1025:1331 | Intel      | Cannon Lake PCH Serial IO... | 119   | intel_lpss | 38688703F4 |
| 8086:a324 | 1028:0905 | Intel      | Cannon Lake PCH SPI Contr... | 113   | intel_s... | 9CDE952049 |
| 8086:a368 | 1028:0905 | Intel      | Cannon Lake PCH Serial IO... | 113   | intel_l... | 9CDE952049 |
| 8086:a369 | 1028:0905 | Intel      | Cannon Lake PCH Serial IO... | 113   | intel_l... | 9CDE952049 |
| 8086:02a4 | 17aa:5079 | Intel      | Comet Lake SPI (flash) Co... | 107   | intel_s... | 0BC4073D23 |
| 8086:a324 | 1028:087c | Intel      | Cannon Lake PCH SPI Contr... | 98    | intel_spi  | 31A6F21CCD |
| 8086:a368 | 1028:087c | Intel      | Cannon Lake PCH Serial IO... | 98    | intel_l... | 31A6F21CCD |
| 8086:a369 | 1028:087c | Intel      | Cannon Lake PCH Serial IO... | 98    | intel_l... | 31A6F21CCD |
| 8086:9da4 | 17aa:2279 | Intel      | Cannon Point-LP SPI Contr... | 96    |            | 2444839350 |
| 8086:9de8 | 17aa:2279 | Intel      | Cannon Point-LP Serial IO... | 96    | intel_l... | 2444839350 |
| 8086:9da4 | 103c:8549 | Intel      | Cannon Point-LP SPI Contr... | 95    |            | 9A264DBCB2 |
| 8086:9de8 | 103c:8549 | Intel      | Cannon Point-LP Serial IO... | 95    | intel_l... | 9A264DBCB2 |
| 8086:9de9 | 103c:8549 | Intel      | Cannon Point-LP Serial IO... | 95    | intel_l... | 9A264DBCB2 |
| 8086:9ce6 | 8086:9ce6 | Intel      | Wildcat Point-LP Serial I... | 85    | spi_pxa... | C0ED6370C5 |
| 8086:9da4 | 1028:08af | Intel      | Cannon Point-LP SPI Contr... | 82    |            | 80857F497B |
| 8086:9de8 | 1028:08af | Intel      | Cannon Point-LP Serial IO... | 82    | intel_l... | 80857F497B |
| 8086:9de9 | 1028:08af | Intel      | Cannon Point-LP Serial IO... | 82    | intel_l... | 80857F497B |
| 8086:02a4 | 1028:0962 | Intel      | Comet Lake SPI (flash) Co... | 77    | intel_s... | 9E26259821 |
| 8086:02e8 | 1028:0962 | Intel      | Serial IO I2C Host Contro... | 77    | intel_l... | 9E26259821 |
| 8086:02e9 | 1028:0962 | Intel      | Comet Lake Serial IO I2C ... | 77    | intel_l... | 9E26259821 |
| 8086:a324 | 1025:1264 | Intel      | Cannon Lake PCH SPI Contr... | 74    | intel_s... | 9971E42809 |
| 8086:a368 | 1025:1264 | Intel      | Cannon Lake PCH Serial IO... | 74    | intel_lpss | 9971E42809 |
| 8086:a369 | 1025:1264 | Intel      | Cannon Lake PCH Serial IO... | 74    | intel_lpss | 9971E42809 |
| 8086:02a4 | 8086:7270 | Intel      | Comet Lake SPI (flash) Co... | 73    | intel_s... | 94D2095D5F |
| 8086:9da4 | 17aa:2292 | Intel      | Cannon Point-LP SPI Contr... | 72    |            | FBF4582983 |
| 8086:9de8 | 17aa:2292 | Intel      | Cannon Point-LP Serial IO... | 72    | intel_l... | FBF4582983 |
| 8086:9de9 | 17aa:2292 | Intel      | Cannon Point-LP Serial IO... | 71    | intel_l... | FBF4582983 |
| 8086:9da4 | 17aa:5072 | Intel      | Cannon Point-LP SPI Contr... | 67    |            | 62C94909C7 |
| 10de:1adb | 10de:0000 | Nvidia     | TU106 USB Type-C UCSI Con... | 62    | i2c_nvi... | 2735F9B34E |
| 8086:9da4 | 17aa:380c | Intel      | Cannon Point-LP SPI Contr... | 61    |            | 2ED0E50384 |
| 8086:9de8 | 17aa:3813 | Intel      | Cannon Point-LP Serial IO... | 61    | intel_l... | 2ED0E50384 |
| 8086:a324 | 17aa:3803 | Intel      | Cannon Lake PCH SPI Contr... | 60    | intel_s... | AB6647F9DA |
| 8086:a368 | 17aa:3805 | Intel      | Cannon Lake PCH Serial IO... | 60    | intel_l... | AB6647F9DA |
| 8086:a369 | 17aa:380b | Intel      | Cannon Lake PCH Serial IO... | 60    | intel_l... | AB6647F9DA |
| 8086:06a4 | 1028:097d | Intel      | Comet Lake PCH SPI Contro... | 54    | intel_spi  | 8C072EA1C4 |
| 8086:06e8 | 1028:097d | Intel      | Comet Lake PCH Serial IO ... | 54    | intel_l... | 8C072EA1C4 |
| 8086:06e9 | 1028:097d | Intel      | Comet Lake PCH Serial IO ... | 54    | intel_l... | 8C072EA1C4 |
| 8086:a324 | 1028:0949 | Intel      | Cannon Lake PCH SPI Contr... | 53    | intel_s... | 480FEF69F1 |
| 8086:a324 | 17aa:3801 | Intel      | Cannon Lake PCH SPI Contr... | 53    | intel_s... | 0FE8BCBB7A |
| 8086:a324 | 17aa:3827 | Intel      | Cannon Lake PCH SPI Contr... | 53    | intel_s... | C332C85DCF |
| 8086:a368 | 1028:0949 | Intel      | Cannon Lake PCH Serial IO... | 53    | intel_l... | 480FEF69F1 |
| 8086:a368 | 17aa:3803 | Intel      | Cannon Lake PCH Serial IO... | 53    | intel_l... | C332C85DCF |
| 8086:a368 | 17aa:3806 | Intel      | Cannon Lake PCH Serial IO... | 53    | intel_l... | 0FE8BCBB7A |
| 8086:a369 | 1028:0949 | Intel      | Cannon Lake PCH Serial IO... | 53    | intel_l... | 480FEF69F1 |
| 8086:a369 | 17aa:3804 | Intel      | Cannon Lake PCH Serial IO... | 53    | intel_l... | C332C85DCF |
| 8086:a369 | 17aa:3809 | Intel      | Cannon Lake PCH Serial IO... | 53    | intel_l... | 0FE8BCBB7A |
| 8086:9da4 | 1028:08ca | Intel      | Cannon Point-LP SPI Contr... | 52    |            | 0D671ACB94 |
| 8086:9dc5 | 1028:08ca | Intel      | Cannon Point-LP Serial IO... | 52    | intel_l... | 0D671ACB94 |
| 8086:9de8 | 1028:08ca | Intel      | Cannon Point-LP Serial IO... | 52    | intel_l... | 0D671ACB94 |
| 8086:9de9 | 1028:08ca | Intel      | Cannon Point-LP Serial IO... | 52    | intel_l... | 0D671ACB94 |
| 8086:a324 | 1028:086f | Intel      | Cannon Lake PCH SPI Contr... | 50    | intel_s... | 36324023DD |
| 8086:a368 | 1028:086f | Intel      | Cannon Lake PCH Serial IO... | 50    | intel_l... | 36324023DD |
| 8086:a369 | 1028:086f | Intel      | Cannon Lake PCH Serial IO... | 50    | intel_l... | 36324023DD |
| 8086:a324 | 103c:8478 | Intel      | Cannon Lake PCH SPI Contr... | 47    | intel_s... | D3A001E377 |
| 8086:a324 | 1028:087d | Intel      | Cannon Lake PCH SPI Contr... | 44    | intel_spi  | A5C63380D6 |
| 8086:a324 | 17aa:2267 | Intel      | Cannon Lake PCH SPI Contr... | 44    | intel_s... | 8FA5616036 |
| 8086:a368 | 1028:087d | Intel      | Cannon Lake PCH Serial IO... | 44    | intel_l... | A5C63380D6 |
| 8086:a368 | 17aa:2267 | Intel      | Cannon Lake PCH Serial IO... | 44    | intel_l... | 8FA5616036 |
| 8086:a369 | 1028:087d | Intel      | Cannon Lake PCH Serial IO... | 44    | intel_l... | A5C63380D6 |
| 8086:a324 | 1025:1333 | Intel      | Cannon Lake PCH SPI Contr... | 42    |            | CE68155512 |
| 8086:a324 | 17aa:229f | Intel      | Cannon Lake PCH SPI Contr... | 42    | intel_s... | 5002E43F11 |
| 8086:a368 | 1025:1333 | Intel      | Cannon Lake PCH Serial IO... | 42    | intel_lpss | CE68155512 |
| 8086:a368 | 17aa:229f | Intel      | Cannon Lake PCH Serial IO... | 42    | intel_lpss | 5002E43F11 |
| 8086:a369 | 1025:1333 | Intel      | Cannon Lake PCH Serial IO... | 42    | intel_lpss | CE68155512 |
| 8086:9da4 | 17aa:2286 | Intel      | Cannon Point-LP SPI Contr... | 41    |            | 18DA93A841 |
| 8086:9daa | 1043:1961 | Intel      | Cannon Point-LP Serial IO... | 41    | intel_lpss | DA20CA4C64 |
| 8086:9dc5 | 1043:1961 | Intel      | Cannon Point-LP Serial IO... | 41    | intel_lpss | DA20CA4C64 |
| 8086:9de8 | 1043:1961 | Intel      | Cannon Point-LP Serial IO... | 41    | intel_lpss | DA20CA4C64 |
| 8086:9de9 | 1043:1961 | Intel      | Cannon Point-LP Serial IO... | 41    | intel_lpss | DA20CA4C64 |
| 8086:a0a4 | 1028:0991 | Intel      | Tiger Lake-LP SPI Controller | 39    | intel_s... | 089BB7C152 |
| 8086:a0c5 | 1028:0991 | Intel      | Tiger Lake-LP Serial IO I... | 39    | intel_l... | 089BB7C152 |
| 8086:a0c6 | 1028:0991 | Intel      | Tiger Lake-LP Serial IO I... | 39    | intel_l... | 089BB7C152 |
| 8086:a0e8 | 1028:0991 | Intel      | Tiger Lake-LP Serial IO I... | 39    | intel_l... | 089BB7C152 |
| 8086:a0e9 | 1028:0991 | Intel      | Tiger Lake-LP Serial IO I... | 39    | intel_l... | 089BB7C152 |
| 8086:a324 | 1028:0825 | Intel      | Cannon Lake PCH SPI Contr... | 39    | intel_s... | AC76D208AB |
| 8086:a324 | 1028:0906 | Intel      | Cannon Lake PCH SPI Contr... | 39    | intel_s... | 2B4444A6FA |
| 8086:a368 | 1028:0825 | Intel      | Cannon Lake PCH Serial IO... | 39    | intel_l... | AC76D208AB |
| 8086:a368 | 1028:0906 | Intel      | Cannon Lake PCH Serial IO... | 39    | intel_l... | 2B4444A6FA |
| 8086:a369 | 1028:0825 | Intel      | Cannon Lake PCH Serial IO... | 39    | intel_l... | AC76D208AB |
| 8086:a369 | 1028:0906 | Intel      | Cannon Lake PCH Serial IO... | 39    | intel_l... | 2B4444A6FA |
| 8086:34a4 | 1028:096d | Intel      | Ice Lake-LP SPI Controller   | 38    | intel_spi  | FBBAF8088B |
| 8086:34e8 | 1028:096d | Intel      | Ice Lake-LP Serial IO I2C... | 38    | intel_l... | FBBAF8088B |
| 8086:34e9 | 1028:096d | Intel      | Ice Lake-LP Serial IO I2C... | 38    | intel_l... | FBBAF8088B |
| 8086:34a4 | 17aa:3842 | Intel      | Ice Lake-LP SPI Controller   | 34    | intel_s... | 2ABD900016 |
| 8086:34e8 | 17aa:3816 | Intel      | Ice Lake-LP Serial IO I2C... | 34    | intel_l... | 2ABD900016 |
| 8086:34e9 | 17aa:3817 | Intel      | Ice Lake-LP Serial IO I2C... | 34    | intel_l... | 2ABD900016 |
| 8086:02a4 | 103c:86a0 | Intel      | Comet Lake SPI (flash) Co... | 33    | intel_s... | DEB906B69F |
| 8086:02e8 | 103c:86a0 | Intel      | Serial IO I2C Host Contro... | 33    | intel_l... | DEB906B69F |
| 8086:34a4 | 103c:86c9 | Intel      | Ice Lake-LP SPI Controller   | 33    | intel_s... | B40784D2C7 |
| 8086:34e8 | 103c:86c9 | Intel      | Ice Lake-LP Serial IO I2C... | 33    | intel_l... | B40784D2C7 |
| 8086:34e9 | 103c:86c9 | Intel      | Ice Lake-LP Serial IO I2C... | 33    | intel_l... | B40784D2C7 |
| 8086:9da4 | 1028:08e1 | Intel      | Cannon Point-LP SPI Contr... | 33    |            | 011A257801 |
| 8086:9da4 | 103c:8532 | Intel      | Cannon Point-LP SPI Contr... | 33    |            | 92D97521BC |
| 8086:9da4 | 8086:9da4 | Intel      | Cannon Point-LP SPI Contr... | 33    |            | 203BB4369E |
| 8086:9dc5 | 1028:08e1 | Intel      | Cannon Point-LP Serial IO... | 33    | intel_l... | 011A257801 |
| 8086:9de8 | 1028:08e1 | Intel      | Cannon Point-LP Serial IO... | 33    | intel_l... | 011A257801 |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2a47 | 17aa:20ec | Intel      | Mobile 4 Series Chipset A... | 132   | serial     | DB936567F0 |
| 8086:3b67 | 17aa:2162 | Intel      | 5 Series/3400 Series Chip... | 128   | serial     | 5DC4A1E557 |
| 8086:1e3d | 17aa:21f3 | Intel      | 7 Series/C210 Series Chip... | 109   | serial     | C9503690D6 |
| 8086:1c3d | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 108   | serial     | 11FDC99047 |
| 8086:9c3d | 103c:198f | Intel      | 8 Series HECI KT             | 75    | serial     | 6573923D55 |
| 8086:1e3d | 17aa:21fa | Intel      | 7 Series/C210 Series Chip... | 74    | serial     | 0D334AF224 |
| 8086:1c3d | 103c:161c | Intel      | 6 Series/C200 Series Chip... | 72    | serial     | 37F8994BEF |
| 8086:1c3d | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 68    | serial     | B948FE4DD5 |
| 8086:9c3d | 17aa:220c | Intel      | 8 Series HECI KT             | 63    | serial     | 4C600416F9 |
| 8086:1e3d | 17aa:21f6 | Intel      | 7 Series/C210 Series Chip... | 59    | serial     | B79CAD571B |
| 8086:9d3d | 103c:8079 | Intel      | Sunrise Point-LP Active M... | 59    | serial     | BC4CDD85CE |
| 10ec:816a | 17aa:5081 | Realtek... | RTL8111xP UART #1            | 58    | serial     | 6B6205BC5D |
| 10ec:816b | 17aa:5081 | Realtek... | RTL8111xP UART #2            | 58    | serial     | 6B6205BC5D |
| 8086:1e3d | 103c:179b | Intel      | 7 Series/C210 Series Chip... | 56    | serial     | 7D39BC1331 |
| 8086:06fc | 1028:097d | Intel      | 400 Series Chipset Family... | 54    | intel_i... | 8C072EA1C4 |
| 8086:3b67 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 52    | serial     | 576A6491F3 |
| 8086:1c3d | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 48    | serial     | 8E0B4EE3A1 |
| 8086:8c3d | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 48    | serial     | 4EC9EAAC2F |
| 8086:1e3d | 1028:0534 | Intel      | 7 Series/C210 Series Chip... | 41    | serial     | 98420A7D92 |
| 8086:1c3d | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 39    | serial     | 33617DD1A8 |
| 8086:3b67 | 103c:172a | Intel      | 5 Series/3400 Series Chip... | 39    | serial     | 66A3F34824 |
| 8086:a0fc | 1028:0991 | Intel      | Tiger Lake-LP Integrated ... | 39    | intel_i... | 089BB7C152 |
| 8086:34fc | 1028:096d | Intel      | Ice Lake-LP Integrated Se... | 38    | intel_i... | FBBAF8088B |
| 8086:9dfc | 103c:8549 | Intel      | Cannon Point-LP Integrate... | 38    | intel_i... | 7DBEB6844A |
| 8086:9c3d | 1028:05cb | Intel      | 8 Series HECI KT             | 36    | serial     | EF82F4635D |
| 8086:1e3d | 17aa:21fb | Intel      | 7 Series/C210 Series Chip... | 34    | serial     | AEF8C27B50 |
| 8086:9c3d | 17aa:2214 | Intel      | 8 Series HECI KT             | 33    | serial     | F100B7CDB9 |
| 8086:1c3d | 103c:162b | Intel      | 6 Series/C200 Series Chip... | 30    | serial     | C75019619F |
| 8086:9d3d | 1028:06dc | Intel      | Sunrise Point-LP Active M... | 30    | serial     | F972F7D9BA |
| 8086:06fc | 1028:098f | Intel      | 400 Series Chipset Family... | 29    | intel_i... | 3B1546B203 |
| 8086:1e3d | 10cf:16ed | Intel      | 7 Series/C210 Series Chip... | 29    | serial     | B2D4A08D24 |
| 8086:3b67 | 103c:7008 | Intel      | 5 Series/3400 Series Chip... | 29    | serial     | 86286FAD9C |
| 8086:1c3d | 17aa:21d2 | Intel      | 6 Series/C200 Series Chip... | 28    | serial     | 74057C8385 |
| 8086:3b67 | 103c:1521 | Intel      | 5 Series/3400 Series Chip... | 28    | serial     | FFC46C9472 |
| 8086:8c3d | 1028:05bd | Intel      | 8 Series/C220 Series Chip... | 28    | serial     | 535815022C |
| 8086:9c3d | 1028:05ca | Intel      | 8 Series HECI KT             | 28    | serial     | 9E790BA3F0 |
| 8086:9d3d | 1028:081c | Intel      | Sunrise Point-LP Active M... | 28    | serial     | B3010001A3 |
| 8086:9de3 | 103c:8549 | Intel      | Cannon Point-LP Keyboard ... | 27    | serial     | A9CD0A6239 |
| 8086:1e3d | 103c:18df | Intel      | 7 Series/C210 Series Chip... | 26    | serial     | 3E6A2F7B59 |
| 8086:8c3d | 1028:05be | Intel      | 8 Series/C220 Series Chip... | 26    | serial     | 6399CECB6F |
| 8086:9d3d | 17aa:5053 | Intel      | Sunrise Point-LP Active M... | 26    | serial     | 6B9264BFE9 |
| 8086:a37c | 1028:0949 | Intel      | VROC Virtual Controller      | 26    | intel_i... | 1E15CE5E51 |
| 10ec:816a | 17aa:5082 | Realtek... | RTL8111xP UART #1            | 25    | serial     | 12FFAAEFB1 |
| 10ec:816a | 17aa:5125 | Realtek... | RTL8111xP UART #1            | 25    | serial     | 452DD792F1 |
| 10ec:816b | 17aa:5082 | Realtek... | RTL8111xP UART #2            | 25    | serial     | 12FFAAEFB1 |
| 10ec:816b | 17aa:5125 | Realtek... | RTL8111xP UART #2            | 25    | serial     | 452DD792F1 |
| 8086:02fc | 1028:0959 | Intel      | Comet Lake Integrated Sen... | 25    | intel_i... | 9D8401675E |
| 8086:1c3d | 103c:1618 | Intel      | 6 Series/C200 Series Chip... | 25    | serial     | EA1BD5E314 |
| 8086:3b67 | 10cf:152f | Intel      | 5 Series/3400 Series Chip... | 25    | serial     | F220F9AC45 |
| 8086:9d3d | 17aa:2233 | Intel      | Sunrise Point-LP Active M... | 25    | serial     | 24B49E957C |
| 8086:9d3d | 17aa:225c | Intel      | Sunrise Point-LP Active M... | 25    | serial     | D49E5B0303 |
| 10ec:816a | 17aa:5126 | Realtek... | RTL8111xP UART #1            | 24    | serial     | 7065F7BB74 |
| 10ec:816b | 17aa:5126 | Realtek... | RTL8111xP UART #2            | 24    | serial     | 7065F7BB74 |
| 8086:9d3d | 17aa:2245 | Intel      | Sunrise Point-LP Active M... | 24    | serial     | 4EB1086713 |
| 8086:9de3 | 1028:08e1 | Intel      | Cannon Point-LP Keyboard ... | 24    | serial     | 011A257801 |
| 8086:1e3d | 103c:17a7 | Intel      | 7 Series/C210 Series Chip... | 23    | serial     | A66A0DF735 |
| 8086:9de3 | 17aa:2279 | Intel      | Cannon Point-LP Keyboard ... | 23    | serial     | 3F74A71C6E |
| 8086:02fc | 1028:0957 | Intel      | Comet Lake Integrated Sen... | 22    | intel_i... | 6901F8A463 |
| 10ec:816a | 17aa:507e | Realtek... | RTL8111xP UART #1            | 21    | serial     | 31850CE796 |
| 10ec:816b | 17aa:507e | Realtek... | RTL8111xP UART #2            | 21    | serial     | 31850CE796 |
| 8086:2a47 | 1028:0233 | Intel      | Mobile 4 Series Chipset A... | 21    | serial     | 2EA2BB4954 |
| 8086:9d3d | 17aa:225d | Intel      | Sunrise Point-LP Active M... | 21    | serial     | 1649C0AE85 |
| 8086:1e3d | 1028:0535 | Intel      | 7 Series/C210 Series Chip... | 20    | serial     | 2E9B8200A9 |
| 8086:a13d | 17aa:222e | Intel      | 100 Series/C230 Series Ch... | 20    | serial     | 6F9D0F45BB |
| 8086:a363 | 17aa:2267 | Intel      | Cannon Lake PCH Active Ma... | 20    | serial     | 8FA5616036 |
| 8086:1c3d | 1028:04a3 | Intel      | 6 Series/C200 Series Chip... | 19    | serial     | EE6C9C38B0 |
| 8086:8c3d | 103c:1909 | Intel      | 8 Series/C220 Series Chip... | 19    | serial     | A3159494C8 |
| 8086:1c3d | 1028:0492 | Intel      | 6 Series/C200 Series Chip... | 18    | serial     | 8A49FDBB8F |
| 8086:2a07 | 103c:30c5 | Intel      | Mobile PM965/GM965 KT Con... | 18    | serial     | 7E17CF2706 |
| 8086:3b67 | 1028:040b | Intel      | 5 Series/3400 Series Chip... | 18    | serial     | 06D38294AB |
| 8086:9d3d | 1028:06de | Intel      | Sunrise Point-LP Active M... | 18    | serial     | 6ADE45EE37 |
| 8086:9dfc | 1028:08a7 | Intel      | Cannon Point-LP Integrate... | 18    | intel_i... | F914E0D1B3 |
| 8086:1c3d | 10cf:1614 | Intel      | 6 Series/C200 Series Chip... | 17    | serial     | 1CB3267B57 |
| 8086:2a47 | 103c:30db | Intel      | Mobile 4 Series Chipset A... | 17    | serial     | A4CEF366BC |
| 8086:8c3d | 17aa:2211 | Intel      | 8 Series/C220 Series Chip... | 17    | serial     | 30EDEADDE3 |
| 8086:9c3d | 103c:1991 | Intel      | 8 Series HECI KT             | 17    | serial     | 688D3890FE |
| 8086:9de3 | 17aa:2292 | Intel      | Cannon Point-LP Keyboard ... | 17    | serial     | B6CAC26930 |
| 8086:1c3d | 1028:0494 | Intel      | 6 Series/C200 Series Chip... | 16    | serial     | EEAE263935 |
| 8086:1c3d | 10f7:8338 | Intel      | 6 Series/C200 Series Chip... | 16    | serial     | 00A042E805 |
| 8086:1c3d | 17aa:21db | Intel      | 6 Series/C200 Series Chip... | 16    | serial     | FB1DB30A5F |
| 8086:3b67 | 1028:0410 | Intel      | 5 Series/3400 Series Chip... | 16    | serial     | 4135CD0970 |
| 8086:3b67 | 103c:7007 | Intel      | 5 Series/3400 Series Chip... | 16    | serial     | 6604EBCF44 |
| 8086:9d3d | 17aa:2258 | Intel      | Sunrise Point-LP Active M... | 16    | serial     | 77FA169F83 |
| 8086:9d3d | 17aa:225a | Intel      | Sunrise Point-LP Active M... | 16    | serial     | 11C98724D5 |
| 8086:9c3d | 1028:05de | Intel      | 8 Series HECI KT             | 15    | serial     | EA59351ECE |
| 8086:9d3d | 17aa:504a | Intel      | Sunrise Point-LP Active M... | 15    | serial     | 76F7F1C140 |
| 8086:02fc | 1028:0955 | Intel      | Comet Lake Integrated Sen... | 14    | intel_i... | 3644971313 |
| 8086:02fc | 1028:09be | Intel      | Comet Lake Integrated Sen... | 14    | intel_i... | F99332E9B6 |
| 8086:2a07 | 17aa:20d4 | Intel      | Mobile PM965/GM965 KT Con... | 14    | serial     | C366A3E7A2 |
| 8086:8c3d | 10cf:17e0 | Intel      | 8 Series/C220 Series Chip... | 14    | serial     | 4DCED4EE57 |
| 8086:9d3d | 1028:07a0 | Intel      | Sunrise Point-LP Active M... | 14    | serial     | 0F2477786D |
| 8086:9d3d | 1028:07a7 | Intel      | Sunrise Point-LP Active M... | 14    | serial     | 8A2F2558AC |
| 8086:9d3d | 17aa:224b | Intel      | Sunrise Point-LP Active M... | 14    | serial     | 8BCA9F26DF |
| 8086:a363 | 1028:0918 | Intel      | Cannon Lake PCH Active Ma... | 14    | serial     | 335ECBB107 |
| 8086:a363 | 17aa:229f | Intel      | Cannon Lake PCH Active Ma... | 14    | serial     | 5002E43F11 |
| 8086:8c3d | 103c:2101 | Intel      | 8 Series/C220 Series Chip... | 13    | serial     | E47D5AF235 |
| 8086:9c3d | 17aa:2218 | Intel      | 8 Series HECI KT             | 13    | serial     | 99AB618BEE |
| 8086:9d3d | 1028:06db | Intel      | Sunrise Point-LP Active M... | 13    | serial     | B0E028DBE3 |
| 10ec:816a | 17aa:5122 | Realtek... | RTL8111xP UART #1            | 12    | serial     | 0293EF3352 |
| 10ec:816b | 17aa:5122 | Realtek... | RTL8111xP UART #2            | 12    | serial     | 0293EF3352 |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 261   | process... | CE72C3ED0D |
| 8086:3b32 | 17aa:2190 | Intel      | 5 Series/3400 Series Chip... | 252   | intel_ips  | 5DC4A1E557 |
| 8086:9d27 | 1043:1d2d | Intel      | Sunrise Point-LP Serial I... | 242   | intel_lpss | AF70469300 |
| 8086:9d29 | 1043:1d2d | Intel      | Sunrise Point-LP Serial I... | 230   | intel_lpss | AF70469300 |
| 8086:22dc | 7270:8086 | Intel      | Atom/Celeron/Pentium Proc... | 205   | process... | 5E75AF2BA4 |
| 8086:5a8c |           | Intel      | Atom/Celeron/Pentium Dyna... | 180   | process... | 71A92492E3 |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 167   | intel_l... | 71A92492E3 |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 166   | intel_l... | 71A92492E3 |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 165   | intel_l... | 71A92492E3 |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 165   | intel_l... | 71A92492E3 |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 164   | intel_l... | 71A92492E3 |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 164   | intel_l... | 71A92492E3 |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 164   | intel_l... | 71A92492E3 |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 164   | intel_l... | 71A92492E3 |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 164   | intel_l... | 71A92492E3 |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 162   | intel_l... | 71A92492E3 |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 156   | intel_l... | 71A92492E3 |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 156   | intel_l... | 71A92492E3 |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 156   | intel_l... | 71A92492E3 |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 155   | intel_l... | 71A92492E3 |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 155   | intel_l... | 71A92492E3 |
| 8086:318c | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 135   | proc_th... | 170B220F5B |
| 8086:31b4 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 135   | intel_lpss | 170B220F5B |
| 8086:31b6 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 135   | intel_lpss | 170B220F5B |
| 8086:31bc | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 135   | intel_lpss | 170B220F5B |
| 8086:31be | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 135   | intel_lpss | 170B220F5B |
| 8086:31c0 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 135   | intel_lpss | 170B220F5B |
| 8086:31ee | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 135   | intel_lpss | 170B220F5B |
| 8086:0a03 | 8086:2010 | Intel      | Haswell-ULT Thermal Subsy... | 133   | process... | 7619CF7632 |
| 8086:3b32 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 129   | intel_ips  | 576A6491F3 |
| 8086:9d31 | 17aa:3861 | Intel      | Sunrise Point-LP Thermal ... | 123   | intel_p... | 19226582D9 |
| 8086:9d60 | 17aa:3865 | Intel      | Sunrise Point-LP Serial I... | 123   | intel_l... | 19226582D9 |
| 8086:a379 | 1025:1331 | Intel      | Cannon Lake PCH Thermal C... | 119   | intel_p... | 38688703F4 |
| 8086:31c6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 117   | intel_l... | 021617B9A0 |
| 8086:31be | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 116   | intel_l... | 021617B9A0 |
| 8086:31c4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 116   | intel_l... | 021617B9A0 |
| 8086:31ee | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 116   | intel_l... | 021617B9A0 |
| 8086:3b32 | 17aa:38c0 | Intel      | 5 Series/3400 Series Chip... | 115   | intel_ips  | 62053AE42B |
| 8086:1903 | 1028:0905 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 113   | process... | 9CDE952049 |
| 8086:a379 | 1028:0905 | Intel      | Cannon Lake PCH Thermal C... | 113   | intel_p... | 9CDE952049 |
| 8086:31b4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 111   | intel_l... | 021617B9A0 |
| 8086:31ba | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 111   | intel_l... | 021617B9A0 |
| 8086:31bc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 111   | intel_l... | 021617B9A0 |
| 8086:31c2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 111   | intel_l... | 021617B9A0 |
| 8086:318c | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 110   | process... | 021617B9A0 |
| 8086:31ac | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 110   | intel_l... | 021617B9A0 |
| 8086:31b6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 110   | intel_l... | 021617B9A0 |
| 8086:31b8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 110   | intel_l... | 021617B9A0 |
| 8086:31c0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 110   | intel_l... | 021617B9A0 |
| 8086:31ae | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 109   | intel_l... | 021617B9A0 |
| 8086:31b0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 109   | intel_l... | 021617B9A0 |
| 8086:31b2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 109   | intel_l... | 021617B9A0 |
| 8086:02f9 | 17aa:5079 | Intel      | Comet Lake Thermal Subsytem  | 107   | intel_p... | 0BC4073D23 |
| 8086:1903 | 17aa:5079 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 107   | process... | 0BC4073D23 |
| 8086:9d60 | 1025:1193 | Intel      | Sunrise Point-LP Serial I... | 105   | intel_lpss | E922639FF6 |
| 8086:9d61 | 1025:1193 | Intel      | Sunrise Point-LP Serial I... | 105   | intel_lpss | E922639FF6 |
| 8086:3b32 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 101   | intel_ips  | C172C655DE |
| 8086:1903 | 1028:087c | Intel      | Xeon E3-1200 v5/E3-1500 v... | 98    | process... | 31A6F21CCD |
| 8086:a379 | 1028:087c | Intel      | Cannon Lake PCH Thermal C... | 98    | intel_p... | 31A6F21CCD |
| 8086:1903 | 1028:0810 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 97    | process... | 2FD333BC52 |
| 8086:9d31 | 1028:0810 | Intel      | Sunrise Point-LP Thermal ... | 97    | intel_p... | 2FD333BC52 |
| 8086:9d60 | 1028:0810 | Intel      | Sunrise Point-LP Serial I... | 97    | intel_l... | 2FD333BC52 |
| 8086:1903 | 17aa:2279 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 96    | process... | 2444839350 |
| 8086:1903 | 8086:1903 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 96    | process... | 35941050E8 |
| 8086:9df9 | 17aa:2279 | Intel      | Cannon Point-LP Thermal C... | 96    | intel_p... | 2444839350 |
| 8086:9df9 | 103c:8549 | Intel      | Cannon Point-LP Thermal C... | 95    | intel_p... | 9A264DBCB2 |
| 8086:2932 | 17aa:3a1f | Intel      | 82801I (ICH9 Family) Ther... | 94    |            | 1BBEC614AA |
| 8086:9d31 | 103c:8079 | Intel      | Sunrise Point-LP Thermal ... | 94    | intel_p... | 0FA8058EEB |
| 8086:9d60 | 103c:8079 | Intel      | Sunrise Point-LP Serial I... | 94    | intel_l... | 0FA8058EEB |
| 8086:1903 | 103c:8549 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 92    | process... | 9A264DBCB2 |
| 8086:1903 | 17aa:2292 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 92    | process... | FBF4582983 |
| 8086:1903 | 1043:12d1 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 89    | proc_th... | 570905286F |
| 8086:9d27 | 1043:12d1 | Intel      | Sunrise Point-LP Serial I... | 89    | intel_lpss | 570905286F |
| 8086:9d31 | 1043:12d1 | Intel      | Sunrise Point-LP Thermal ... | 89    | intel_p... | 570905286F |
| 8086:9d60 | 1043:12d1 | Intel      | Sunrise Point-LP Serial I... | 89    | intel_lpss | 570905286F |
| 8086:9d61 | 1043:12d1 | Intel      | Sunrise Point-LP Serial I... | 89    | intel_lpss | 570905286F |
| 8086:1903 | 17aa:225d | Intel      | Xeon E3-1200 v5/E3-1500 v... | 88    | process... | BBA3BC97B7 |
| 8086:9ca4 | 8086:7270 | Intel      | Wildcat Point-LP Thermal ... | 88    | intel_p... | C0ED6370C5 |
| 8086:9d31 | 17aa:225d | Intel      | Sunrise Point-LP Thermal ... | 88    | intel_p... | BBA3BC97B7 |
| 8086:9ca4 | 17aa:5034 | Intel      | Wildcat Point-LP Thermal ... | 85    | intel_p... | 6131E3C22A |
| 8086:1903 | 1028:07e6 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 83    | process... | C2E884F793 |
| 8086:9d31 | 1028:07e6 | Intel      | Sunrise Point-LP Thermal ... | 83    | intel_p... | C2E884F793 |
| 8086:9d60 | 1028:07e6 | Intel      | Sunrise Point-LP Serial I... | 83    | intel_l... | C2E884F793 |
| 8086:9d61 | 1028:07e6 | Intel      | Sunrise Point-LP Serial I... | 83    | intel_l... | C2E884F793 |
| 8086:1903 | 1028:08af | Intel      | Xeon E3-1200 v5/E3-1500 v... | 82    | process... | 80857F497B |
| 8086:9d27 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 82    | intel_l... | 8030B99150 |
| 8086:9df9 | 1028:08af | Intel      | Cannon Point-LP Thermal C... | 82    | intel_p... | 80857F497B |
| 8086:5a8c | 1043:16a0 | Intel      | Atom/Celeron/Pentium Dyna... | 81    | proc_th... | 9F12330C51 |
| 8086:5aac | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 81    | intel_lpss | 9F12330C51 |
| 8086:5ab4 | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 81    | intel_lpss | 9F12330C51 |
| 8086:9d31 | 17aa:3836 | Intel      | Sunrise Point-LP Thermal ... | 80    | intel_p... | 0540D35606 |
| 8086:9d60 | 17aa:383b | Intel      | Sunrise Point-LP Serial I... | 80    | intel_l... | 0540D35606 |
| 8086:9d31 | 17aa:5068 | Intel      | Sunrise Point-LP Thermal ... | 79    | intel_p... | 893F642CBB |
| 8086:1903 | 1028:078b | Intel      | Xeon E3-1200 v5/E3-1500 v... | 78    | process... | 4F60F64204 |
| 8086:3b32 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 78    | intel_ips  | E79E0F2021 |
| 8086:9d31 | 1028:078b | Intel      | Sunrise Point-LP Thermal ... | 78    | intel_p... | 4F60F64204 |
| 8086:9d60 | 1028:078b | Intel      | Sunrise Point-LP Serial I... | 78    | intel_l... | 4F60F64204 |
| 8086:9d61 | 1028:078b | Intel      | Sunrise Point-LP Serial I... | 78    | intel_l... | 4F60F64204 |
| 8086:02f9 | 1028:0962 | Intel      | Comet Lake Thermal Subsytem  | 77    | intel_p... | 9E26259821 |
| 8086:1903 | 1028:0962 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 77    | process... | 9E26259821 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e22 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 515   | i2c_i801   | 5872E567EC |
| 8086:1c22 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 299   | i2c_i801   | 21DB34139A |
| 8086:3b30 | 17aa:2167 | Intel      | 5 Series/3400 Series Chip... | 284   | i2c_i801   | 5DC4A1E557 |
| 8086:2930 | 17aa:20f9 | Intel      | 82801I (ICH9 Family) SMBu... | 279   | i2c_i801   | DB936567F0 |
| 8086:9c22 | 17aa:3978 | Intel      | 8 Series SMBus Controller    | 278   | i2c_i801   | B1B8196F26 |
| 8086:8c22 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 205   | i2c_i801   | 76D72EB45F |
| 8086:27da | 1043:83ad | Intel      | NM10/ICH7 Family SMBus Co... | 184   | i2c_i801   | 2E4383BD79 |
| 1002:4385 |           | AMD        | SBx00 SMBus Controller       | 180   | i2c_pii... | 72608B2EA0 |
| 8086:1e22 | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 171   | i2c_i801   | C9503690D6 |
| 8086:1e22 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 168   | i2c_i801   | EC1ABD9485 |
| 8086:1c22 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 166   | i2c_i801   | A53D0DE98A |
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 159   | i2c_i801   | 71A92492E3 |
| 8086:1e22 | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 153   | i2c_i801   | 52667487D2 |
| 8086:1c22 | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 150   | i2c_i801   | 438D785F0E |
| 8086:1c22 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 149   | i2c_i801   | 74547808D3 |
| 8086:2930 | 17aa:3a1d | Intel      | 82801I (ICH9 Family) SMBu... | 146   | i2c_i801   | 1BBEC614AA |
| 8086:1c22 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 145   | i2c_i801   | B420F25ED4 |
| 8086:3b30 | 17aa:38bf | Intel      | 5 Series/3400 Series Chip... | 142   | i2c_i801   | 62053AE42B |
| 10de:0aa2 | 10de:cb79 | Nvidia     | MCP79 SMBus                  | 140   | i2c_nfo... | F982A2F6CC |
| 1022:790b | 1022:790b | AMD        | FCH SMBus Controller         | 139   | i2c_piix4  | FC5CE69792 |
| 8086:1c22 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 138   | i2c_i801   | 33617DD1A8 |
| 8086:1e22 | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 136   | i2c_i801   | 50D562CAB5 |
| 8086:31d4 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 135   | i2c_i801   | 170B220F5B |
| 8086:3b30 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 134   | i2c_i801   | 576A6491F3 |
| 8086:283e | 17aa:20a9 | Intel      | 82801H (ICH8 Family) SMBu... | 129   | i2c_i801   | E1B3B6E090 |
| 1022:780b | 17aa:3801 | AMD        | FCH SMBus Controller         | 128   | i2c_piix4  | 779BFC3B47 |
| 8086:1e22 | 1043:124d | Intel      | 7 Series/C216 Chipset Fam... | 127   | i2c_i801   | 08930695BC |
| 8086:3b30 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 126   | i2c_i801   | C172C655DE |
| 8086:3b30 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 123   | i2c_i801   | 03E0270FDD |
| 8086:9d23 | 17aa:386f | Intel      | Sunrise Point-LP SMBus       | 123   | i2c_i801   | 19226582D9 |
| 8086:283e | 1025:011f | Intel      | 82801H (ICH8 Family) SMBu... | 122   | i2c_i801   | 6A05B72968 |
| 8086:3b30 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 121   | i2c_i801   | 11F1CDC49A |
| 8086:a323 | 1025:1331 | Intel      | Cannon Lake PCH SMBus Con... | 119   | i2c_i801   | 38688703F4 |
| 8086:1c22 | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 118   | i2c_i801   | FF37A9C00D |
| 8086:1c22 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 118   | i2c_i801   | 660A6B9E20 |
| 8086:1e22 | 1028:0534 | Intel      | 7 Series/C216 Chipset Fam... | 118   | i2c_i801   | 98420A7D92 |
| 8086:1e22 | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 116   | i2c_i801   | B732F94275 |
| 8086:1e22 | 17aa:21f6 | Intel      | 7 Series/C216 Chipset Fam... | 115   | i2c_i801   | 9ECBB7A946 |
| 8086:a323 | 1028:0905 | Intel      | Cannon Lake PCH SMBus Con... | 113   | i2c_i801   | 9CDE952049 |
| 8086:9ca2 | 8086:7270 | Intel      | Wildcat Point-LP SMBus Co... | 111   | i2c_i801   | C0ED6370C5 |
| 8086:31d4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 110   | i2c_i801   | 021617B9A0 |
| 8086:9c22 | 17aa:220c | Intel      | 8 Series SMBus Controller    | 110   | i2c_i801   | 4C600416F9 |
| 8086:1c22 | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 108   | i2c_i801   | A8FD68FCCC |
| 8086:1e22 | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 108   | i2c_i801   | 2BA1AA7C62 |
| 1022:790b | 103c:8330 | AMD        | FCH SMBus Controller         | 107   | i2c_piix4  | 5671BA2F85 |
| 8086:02a3 | 17aa:5079 | Intel      | Comet Lake PCH-LP SMBus H... | 107   | i2c_i801   | 0BC4073D23 |
| 8086:2930 | 1028:0233 | Intel      | 82801I (ICH9 Family) SMBu... | 107   | i2c_i801   | 2A4C5F6EEC |
| 8086:9d23 | 1025:1193 | Intel      | Sunrise Point-LP SMBus       | 105   | i2c_i801   | E922639FF6 |
| 8086:27da | 1025:0349 | Intel      | NM10/ICH7 Family SMBus Co... | 102   | i2c_i801   | DA7BA5D53F |
| 8086:2930 | 1028:02aa | Intel      | 82801I (ICH9 Family) SMBu... | 100   | i2c_i801   | F0D0F92FD9 |
| 8086:9c22 | 103c:198f | Intel      | 8 Series SMBus Controller    | 99    | i2c_i801   | 6573923D55 |
| 8086:9d23 | 8086:7270 | Intel      | Sunrise Point-LP SMBus       | 99    | i2c_i801   | 1AB69568A5 |
| 8086:1e22 | 10cf:16e6 | Intel      | 7 Series/C216 Chipset Fam... | 98    | i2c_i801   | B2D4A08D24 |
| 8086:a323 | 1028:087c | Intel      | Cannon Lake PCH SMBus Con... | 98    | i2c_i801   | 31A6F21CCD |
| 8086:9d23 | 1028:0810 | Intel      | Sunrise Point-LP SMBus       | 97    | i2c_i801   | 2FD333BC52 |
| 8086:1e22 | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 96    | i2c_i801   | A5268098B2 |
| 8086:8c22 | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 96    | i2c_i801   | 4EC9EAAC2F |
| 8086:9da3 | 17aa:2279 | Intel      | Cannon Point-LP SMBus Con... | 96    | i2c_i801   | 2444839350 |
| 8086:9da3 | 103c:8549 | Intel      | Cannon Point-LP SMBus Con... | 95    | i2c_i801   | 9A264DBCB2 |
| 8086:1c22 | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 94    | i2c_i801   | F8B9508953 |
| 8086:1e22 | 1043:14c7 | Intel      | 7 Series/C216 Chipset Fam... | 94    | i2c_i801   | 53842E648E |
| 8086:9c22 | 1025:0866 | Intel      | 8 Series SMBus Controller    | 94    | i2c_i801   | 58B4832D53 |
| 8086:9d23 | 103c:8079 | Intel      | Sunrise Point-LP SMBus       | 94    | i2c_i801   | 0FA8058EEB |
| 8086:0f12 | 17aa:3905 | Intel      | Atom Processor E3800 Seri... | 93    | i2c_i801   | EB9AAA55EA |
| 8086:1c22 | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 93    | i2c_i801   | 389E1A52A6 |
| 8086:1c22 | 104d:908b | Intel      | 6 Series/C200 Series Chip... | 93    | i2c_i801   | F88D733F75 |
| 8086:1e22 | 1179:fb31 | Intel      | 7 Series/C216 Chipset Fam... | 92    | i2c_i801   | 6BECED18DA |
| 8086:283e | 1028:01f9 | Intel      | 82801H (ICH8 Family) SMBu... | 92    | i2c_i801   | E271885D51 |
| 8086:9c22 | 1028:0651 | Intel      | 8 Series SMBus Controller    | 92    | i2c_i801   | E1A816CC42 |
| 8086:1e22 | 1043:1477 | Intel      | 7 Series/C216 Chipset Fam... | 91    | i2c_i801   | 62C6944A06 |
| 8086:9d23 | 1043:12d1 | Intel      | Sunrise Point-LP SMBus       | 89    | i2c_i801   | 570905286F |
| 8086:1c22 | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 88    | i2c_i801   | C40BAA791F |
| 8086:9d23 | 17aa:225d | Intel      | Sunrise Point-LP SMBus       | 88    | i2c_i801   | BBA3BC97B7 |
| 8086:0f12 | 17aa:3909 | Intel      | Atom Processor E3800 Seri... | 86    | i2c_i801   | BAC9935F0B |
| 8086:9c22 | 1025:0775 | Intel      | 8 Series SMBus Controller    | 85    | i2c_i801   | 2729E1919C |
| 8086:9ca2 | 17aa:5034 | Intel      | Wildcat Point-LP SMBus Co... | 85    | i2c_i801   | 6131E3C22A |
| 8086:9d23 | 1028:07e6 | Intel      | Sunrise Point-LP SMBus       | 83    | i2c_i801   | C2E884F793 |
| 8086:9da3 | 1028:08af | Intel      | Cannon Point-LP SMBus Con... | 82    | i2c_i801   | 80857F497B |
| 8086:5ad4 | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 81    | i2c_i801   | 9F12330C51 |
| 8086:9d23 | 17aa:3841 | Intel      | Sunrise Point-LP SMBus       | 80    | i2c_i801   | 0540D35606 |
| 1002:4385 | 103c:3577 | AMD        | SBx00 SMBus Controller       | 79    | i2c_pii... | C0FCCB63BB |
| 8086:9d23 | 17aa:5068 | Intel      | Sunrise Point-LP SMBus       | 79    | i2c_i801   | 893F642CBB |
| 1022:790b | 103c:84ac | AMD        | FCH SMBus Controller         | 78    | i2c_piix4  | D22A5E8410 |
| 8086:1e22 | 103c:1854 | Intel      | 7 Series/C216 Chipset Fam... | 78    | i2c_i801   | 21FB6389E7 |
| 8086:9d23 | 1028:078b | Intel      | Sunrise Point-LP SMBus       | 78    | i2c_i801   | 4F60F64204 |
| 8086:02a3 | 1028:0962 | Intel      | Comet Lake PCH-LP SMBus H... | 77    | i2c_i801   | 9E26259821 |
| 8086:1e22 | 144d:c652 | Intel      | 7 Series/C216 Chipset Fam... | 77    | i2c_i801   | 326B21D2B4 |
| 8086:a123 | 1028:07be | Intel      | 100 Series/C230 Series Ch... | 76    | i2c_i801   | 6EE00932DC |
| 1022:790b | 1043:18f1 | AMD        | FCH SMBus Controller         | 75    | i2c_piix4  | D8A3297AB9 |
| 8086:9d23 | 1025:1295 | Intel      | Sunrise Point-LP SMBus       | 75    | i2c_i801   | BEDAFBAD9B |
| 8086:283e | 1028:022f | Intel      | 82801H (ICH8 Family) SMBu... | 74    | i2c_i801   | 06130B24C5 |
| 8086:a323 | 1025:1264 | Intel      | Cannon Lake PCH SMBus Con... | 74    | i2c_i801   | 9971E42809 |
| 1022:790b | 1025:1192 | AMD        | FCH SMBus Controller         | 73    | piix4_s... | CDC742CD03 |
| 8086:9c22 | 17aa:2214 | Intel      | 8 Series SMBus Controller    | 73    | i2c_i801   | F100B7CDB9 |
| 8086:9ca2 | 103c:2216 | Intel      | Wildcat Point-LP SMBus Co... | 73    | i2c_i801   | 304747E4C6 |
| 8086:9d23 | 17aa:225c | Intel      | Sunrise Point-LP SMBus       | 73    | i2c_i801   | C33E7CED42 |
| 8086:1c22 | 1179:fc30 | Intel      | 6 Series/C200 Series Chip... | 72    | i2c_i801   | 60EB674C8F |
| 8086:9da3 | 17aa:2292 | Intel      | Cannon Point-LP SMBus Con... | 72    | i2c_i801   | FBF4582983 |
| 8086:2930 | 1025:0212 | Intel      | 82801I (ICH9 Family) SMBu... | 71    | i2c_i801   | F573488BDA |
| 8086:9c22 | 8086:7270 | Intel      | 8 Series SMBus Controller    | 71    | i2c_i801   | 1007726831 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e20 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 515   | snd_hda... | 5872E567EC |
| 8086:293e | 17aa:20f2 | Intel      | 82801I (ICH9 Family) HD A... | 301   | snd_hda... | DB936567F0 |
| 10de:0bea |           | Nvidia     | GF108 High Definition Aud... | 299   | snd_hda... | 2E9B8200A9 |
| 8086:1c20 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 299   | snd_hda... | 21DB34139A |
| 8086:0a0c | 17aa:3978 | Intel      | Haswell-ULT HD Audio Cont... | 278   | snd_hda... | B1B8196F26 |
| 8086:9c20 | 17aa:3978 | Intel      | 8 Series HD Audio Controller | 278   | snd_hda... | B1B8196F26 |
| 8086:3b56 | 17aa:215e | Intel      | 5 Series/3400 Series Chip... | 268   | snd_hda... | 4FF6DAE64C |
| 1002:15de | 1002:15de | AMD        | Raven/Raven2/Fenghuang HD... | 264   | snd_hda... | F504E72617 |
| 8086:0c0c | 8086:2010 | Intel      | Xeon E3-1200 v3/4th Gen C... | 262   | snd_hda... | 76D72EB45F |
| 10de:0fb9 |           | Nvidia     | GP107GL High Definition A... | 243   | snd_hda... | 1060065F34 |
| 8086:1e20 | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 171   | snd_hda... | C9503690D6 |
| 8086:1c20 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 153   | snd_hda... | A53D0DE98A |
| 8086:1e20 | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 153   | snd_hda... | 52667487D2 |
| 8086:1e20 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 153   | snd_hda... | EC1ABD9485 |
| 8086:8c20 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 153   | snd_hda... | 7FB630F632 |
| 8086:293e | 17aa:3a0d | Intel      | 82801I (ICH9 Family) HD A... | 151   | snd_hda... | 1BBEC614AA |
| 8086:0c0c | 17aa:3978 | Intel      | Xeon E3-1200 v3/4th Gen C... | 150   | snd_hda... | 7FB630F632 |
| 8086:1c20 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 149   | snd_hda... | 74547808D3 |
| 8086:0a0c | 8086:2010 | Intel      | Haswell-ULT HD Audio Cont... | 145   | snd_hda... | AA03D405BC |
| 8086:1c20 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 145   | snd_hda... | B420F25ED4 |
| 10de:0ac0 | 10de:cb79 | Nvidia     | MCP79 High Definition Audio  | 140   | snd_hda... | F982A2F6CC |
| 8086:3b56 | 17aa:38af | Intel      | 5 Series/3400 Series Chip... | 140   | snd_hda... | 62053AE42B |
| 8086:1c20 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 137   | snd_hda... | 33617DD1A8 |
| 8086:1e20 | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 136   | snd_hda... | 50D562CAB5 |
| 8086:3198 | 1043:1de0 | Intel      | Celeron/Pentium Silver Pr... | 136   | snd_hda... | 170B220F5B |
| 8086:3b56 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 134   | snd_hda... | 576A6491F3 |
| 10de:10f1 |           | Nvidia     | GP106 High Definition Aud... | 133   | snd_hda... | AC76D208AB |
| 8086:284b | 17aa:20ac | Intel      | 82801H (ICH8 Family) HD A... | 129   | snd_hda... | E1B3B6E090 |
| 1002:9840 | 17aa:3801 | AMD        | Kabini HDMI/DP Audio         | 128   | snd_hda... | 779BFC3B47 |
| 1022:780d | 17aa:3801 | AMD        | FCH Azalia Controller        | 128   | snd_hda... | 779BFC3B47 |
| 8086:3b56 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 126   | snd_hda... | C172C655DE |
| 8086:3b56 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 123   | snd_hda... | 03E0270FDD |
| 8086:9d71 | 17aa:3837 | Intel      | Sunrise Point-LP HD Audio    | 123   | snd_hda... | 19226582D9 |
| 8086:284b | 1025:011f | Intel      | 82801H (ICH8 Family) HD A... | 121   | snd_hda... | 6A05B72968 |
| 8086:a348 | 1025:1331 | Intel      | Cannon Lake PCH cAVS         | 119   | snd_hda... | 38688703F4 |
| 8086:1c20 | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 118   | snd_hda... | FF37A9C00D |
| 8086:1c20 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 118   | snd_hda... | 660A6B9E20 |
| 8086:1e20 | 1028:0534 | Intel      | 7 Series/C216 Chipset Fam... | 118   | snd_hda... | 98420A7D92 |
| 8086:1e20 | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 116   | snd_hda... | B732F94275 |
| 8086:1e20 | 17aa:21f6 | Intel      | 7 Series/C216 Chipset Fam... | 115   | snd_hda... | 9ECBB7A946 |
| 8086:27d8 | 1043:8437 | Intel      | NM10/ICH7 Family High Def... | 114   | snd_hda... | 2117F02A4F |
| 8086:a348 | 1028:0905 | Intel      | Cannon Lake PCH cAVS         | 113   | snd_hda... | 9CDE952049 |
| 8086:0a0c | 17aa:220c | Intel      | Haswell-ULT HD Audio Cont... | 110   | snd_hda... | 4C600416F9 |
| 8086:9ca0 | 8086:7270 | Intel      | Wildcat Point-LP High Def... | 110   | snd_hda... | C0ED6370C5 |
| 8086:1c20 | 1043:1ac3 | Intel      | 6 Series/C200 Series Chip... | 108   | snd_hda... | A8FD68FCCC |
| 8086:1e20 | 1043:118f | Intel      | 7 Series/C216 Chipset Fam... | 108   | snd_hda... | 08930695BC |
| 8086:1e20 | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 108   | snd_hda... | 2BA1AA7C62 |
| 1002:15b3 | 103c:8330 | AMD        | High Definition Audio Con... | 107   | snd_hda... | 5671BA2F85 |
| 1022:157a | 103c:8330 | AMD        | Family 15h (Models 60h-6f... | 107   | snd_hda... | 5671BA2F85 |
| 8086:02c8 | 17aa:5079 | Intel      | Comet Lake PCH-LP cAVS       | 107   | snd_hda... | 0BC4073D23 |
| 8086:293e | 1028:0233 | Intel      | 82801I (ICH9 Family) HD A... | 107   | snd_hda... | 2A4C5F6EEC |
| 8086:9d71 | 1025:1193 | Intel      | Sunrise Point-LP HD Audio    | 103   | snd_hda... | E922639FF6 |
| 8086:27d8 | 1025:0349 | Intel      | NM10/ICH7 Family High Def... | 102   | snd_hda... | DA7BA5D53F |
| 10de:10fa | 1025:1332 | Nvidia     | TU107 GeForce GTX 1650 Hi... | 101   | snd_hda... | 38688703F4 |
| 8086:1c20 | 103c:161c | Intel      | 6 Series/C200 Series Chip... | 101   | snd_hda... | 701E56A49F |
| 8086:293e | 1028:02aa | Intel      | 82801I (ICH9 Family) HD A... | 100   | snd_hda... | F0D0F92FD9 |
| 8086:0a0c | 103c:198f | Intel      | Haswell-ULT HD Audio Cont... | 99    | snd_hda... | 6573923D55 |
| 8086:293e | 1111:1043 | Intel      | 82801I (ICH9 Family) HD A... | 99    | snd_hda... | 498362846A |
| 10de:0e0f |           | Nvidia     | GK208 HDMI/DP Audio Contr... | 98    | snd_hda... | 6A14872523 |
| 8086:9c20 | 103c:198f | Intel      | 8 Series HD Audio Controller | 98    | snd_hda... | 6573923D55 |
| 8086:a348 | 1028:087c | Intel      | Cannon Lake PCH cAVS         | 98    | snd_hda... | 31A6F21CCD |
| 8086:9d71 | 1028:0810 | Intel      | Sunrise Point-LP HD Audio    | 97    | snd_hda... | 2FD333BC52 |
| 8086:0c0c | 17aa:220e | Intel      | Xeon E3-1200 v3/4th Gen C... | 96    | snd_hda... | 4EC9EAAC2F |
| 8086:1e20 | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 96    | snd_hda... | A5268098B2 |
| 8086:1e20 | 10cf:1757 | Intel      | 7 Series/C216 Chipset Fam... | 96    | snd_hda... | B2D4A08D24 |
| 8086:3b56 | 1043:1643 | Intel      | 5 Series/3400 Series Chip... | 96    | snd_hda... | 11F1CDC49A |
| 8086:8c20 | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 96    | snd_hda... | 4EC9EAAC2F |
| 1002:1637 | 1002:1637 | AMD        | Renoir Radeon High Defini... | 95    | snd_hda... | DB4A212405 |
| 8086:9dc8 | 103c:8549 | Intel      | Cannon Point-LP High Defi... | 95    | snd_hda... | 9A264DBCB2 |
| 8086:9dc8 | 17aa:2279 | Intel      | Cannon Point-LP High Defi... | 95    | snd_hda... | 2444839350 |
| 8086:0a0c | 1025:0866 | Intel      | Haswell-ULT HD Audio Cont... | 94    | snd_hda... | 58B4832D53 |
| 8086:1c20 | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 94    | snd_hda... | F8B9508953 |
| 8086:9d70 | 103c:8079 | Intel      | Sunrise Point-LP HD Audio    | 94    | snd_hda... | 0FA8058EEB |
| 8086:0f04 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 93    | snd_hda... | EB9AAA55EA |
| 8086:1c20 | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 93    | snd_hda... | 389E1A52A6 |
| 8086:1c20 | 104d:908b | Intel      | 6 Series/C200 Series Chip... | 93    | snd_hda... | F88D733F75 |
| 8086:1e20 | 103c:179b | Intel      | 7 Series/C216 Chipset Fam... | 93    | snd_hda... | 7D39BC1331 |
| 8086:0a0c | 1028:0651 | Intel      | Haswell-ULT HD Audio Cont... | 92    | snd_hda... | E1A816CC42 |
| 8086:284b | 1028:01f9 | Intel      | 82801H (ICH8 Family) HD A... | 92    | snd_hda... | E271885D51 |
| 8086:9c20 | 1028:0651 | Intel      | 8 Series HD Audio Controller | 92    | snd_hda... | E1A816CC42 |
| 8086:9d71 | 1043:1460 | Intel      | Sunrise Point-LP HD Audio    | 92    | snd_hda... | 570905286F |
| 8086:9d71 | 1043:1a40 | Intel      | Sunrise Point-LP HD Audio    | 91    | snd_hda... | 51577F00B4 |
| 1002:1714 | 1002:1714 | AMD        | BeaverCreek HDMI Audio [R... | 88    | snd_hda... | CEE81ADBAF |
| 8086:1c20 | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 88    | snd_hda... | C40BAA791F |
| 8086:9d71 | 17aa:225d | Intel      | Sunrise Point-LP HD Audio    | 88    | snd_hda... | BBA3BC97B7 |
| 8086:0f04 | 17aa:3909 | Intel      | Atom Processor Z36xxx/Z37... | 86    | snd_hda... | BAC9935F0B |
| 8086:0a0c | 1025:0775 | Intel      | Haswell-ULT HD Audio Cont... | 85    | snd_hda... | 2729E1919C |
| 8086:160c | 17aa:5034 | Intel      | Broadwell-U Audio Controller | 85    | snd_hda... | 6131E3C22A |
| 1002:aa68 | 1043:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 84    | snd_hda... | 11F1CDC49A |
| 8086:9d71 | 1028:07e6 | Intel      | Sunrise Point-LP HD Audio    | 83    | snd_hda... | C2E884F793 |
| 8086:1c20 | 1043:1b43 | Intel      | 6 Series/C200 Series Chip... | 82    | snd_hda... | 314E6BBBD2 |
| 8086:9dc8 | 1028:08af | Intel      | Cannon Point-LP High Defi... | 82    | snd_hda... | 80857F497B |
| 8086:5a98 | 1043:12e0 | Intel      | Celeron N3350/Pentium N42... | 81    | snd_hda... | 9F12330C51 |
| 8086:9d71 | 17aa:380d | Intel      | Sunrise Point-LP HD Audio    | 80    | snd_hda... | 0540D35606 |
| 1002:4383 | 103c:3577 | AMD        | SBx00 Azalia (Intel HDA)     | 79    | snd_hda... | C0FCCB63BB |
| 8086:9ca0 | 1043:19ad | Intel      | Wildcat Point-LP High Def... | 79    | snd_hda... | 10B0865CAB |
| 1002:15b3 | 103c:84ac | AMD        | High Definition Audio Con... | 78    | snd_hda... | D22A5E8410 |
| 8086:1e20 | 103c:1854 | Intel      | 7 Series/C216 Chipset Fam... | 78    | snd_hda... | 21FB6389E7 |
| 8086:9d71 | 17aa:5068 | Intel      | Sunrise Point-LP HD Audio    | 78    | snd_hda... | 893F642CBB |
| 8086:02c8 | 1028:0962 | Intel      | Comet Lake PCH-LP cAVS       | 77    | snd_hda... | 9E26259821 |

### Storage (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1217:8231 | 1028:0493 | O2 Micro   | O2Micro Integrated MS/MSP... | 133   |            | 33617DD1A8 |
| 104c:803b | 1025:011f | Texas I... | PCIxx12 Flash Media Contr... | 122   | tifm_7xx1  | 6A05B72968 |
| 1217:7130 | 1179:ff50 | O2 Micro   | Integrated MS/xD Controller  | 55    |            | FEB13460E8 |
| 1217:8331 | 1028:0494 | O2 Micro   | O2 Flash Memory Card         | 51    |            | E58B9D7EA5 |
| 104c:803b | 1179:ff00 | Texas I... | PCIxx12 Flash Media Contr... | 48    | tifm_7xx1  | 8E44C9EDAF |
| 104c:803b | 1179:ff02 | Texas I... | PCIxx12 Flash Media Contr... | 38    | tifm_7xx1  | 3F0EBD44AD |
| 1217:7130 | 10cf:143d | O2 Micro   | Integrated MS/xD Controller  | 37    |            | 3B7266D323 |
| 1217:8330 | 1028:04a3 | O2 Micro   | OZ600 MS/xD Controller       | 34    |            | EE6C9C38B0 |
| 1217:8331 | 1028:049a | O2 Micro   | O2 Flash Memory Card         | 34    |            | 33B9916878 |
| 104c:803b | 1179:ff10 | Texas I... | PCIxx12 Flash Media Contr... | 33    | tifm_7xx1  | B6FB3D3EC3 |
| 1217:8331 | 1028:049b | O2 Micro   | O2 Flash Memory Card         | 33    |            | 989DD7D36F |
| 1217:7130 | 1025:013c | O2 Micro   | Integrated MS/xD Controller  | 31    |            | B6E44B21DB |
| 104c:803b | 104d:9005 | Texas I... | PCIxx12 Flash Media Contr... | 29    | tifm_7xx1  | BD472575F4 |
| 104c:803b | 104d:9015 | Texas I... | PCIxx12 Flash Media Contr... | 25    | tifm_7xx1  | 9AC5C739FF |
| 104c:803b | 104d:902d | Texas I... | PCIxx12 Flash Media Contr... | 25    | tifm_7xx1  | B97D7A8C66 |
| 1217:7130 | 10cf:14d6 | O2 Micro   | Integrated MS/xD Controller  | 21    |            | F220F9AC45 |
| 1217:8231 | 1028:04a9 | O2 Micro   | O2Micro Integrated MS/MSP... | 19    |            | 41E38AE50A |
| 104c:803b | 1025:0107 | Texas I... | PCIxx12 Flash Media Contr... | 18    | tifm_7xx1  | 502B2847A6 |
| 104c:803b | 1179:0001 | Texas I... | PCIxx12 Flash Media Contr... | 18    | tifm_7xx1  | EA94C20118 |
| 104c:803b | 1025:0110 | Texas I... | PCIxx12 Flash Media Contr... | 16    | tifm_7xx1  | 53EE388D7D |
| 104c:803b | 104d:9016 | Texas I... | PCIxx12 Flash Media Contr... | 16    | tifm_7xx1  | E17FE551FB |
| 1217:8330 | 1028:04a4 | O2 Micro   | OZ600 MS/xD Controller       | 15    |            | 117E981EF3 |
| 104c:803b | 1028:02ef | Texas I... | PCIxx12 Flash Media Contr... | 14    | tifm_7xx1  | E56C7EF208 |
| 104c:803b | 103c:30aa | Texas I... | PCIxx12 Flash Media Contr... | 14    | tifm_7xx1  | 87BEFC0401 |
| 104c:803b | 104d:81ef | Texas I... | PCIxx12 Flash Media Contr... | 13    | tifm_7xx1  | 82BD19C032 |
| 104c:803b | 1179:ff31 | Texas I... | PCIxx12 Flash Media Contr... | 13    | tifm_7xx1  | 3752763DD2 |
| 104c:803b | 104d:9008 | Texas I... | PCIxx12 Flash Media Contr... | 12    | tifm_7xx1  | E958267BEC |
| 1217:7130 | 1028:0273 | O2 Micro   | Integrated MS/xD Controller  | 12    |            | 186F1ABCFA |
| 1217:8130 | 1028:02bc | O2 Micro   | Integrated MS/MSPRO/xD Co... | 11    |            | F2747CCCC2 |
| 1217:8130 | 1028:02eb | O2 Micro   | Integrated MS/MSPRO/xD Co... | 11    |            | 31C1B6A828 |
| 104c:803b | 1025:0112 | Texas I... | PCIxx12 Flash Media Contr... | 10    | tifm_7xx1  | 56639ACA29 |
| 104c:803b | 104d:81e6 | Texas I... | PCIxx12 Flash Media Contr... | 10    | tifm_7xx1  | BEDA953594 |
| 1217:8130 | 1179:ff50 | O2 Micro   | Integrated MS/MSPRO/xD Co... | 10    |            | 721A4DF615 |
| 104c:8033 | 103c:0944 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 9     | tifm_7xx1  | 7F042FAA64 |
| 104c:8033 | 1179:ff05 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 9     | tifm_7xx1  | 67580C50DF |
| 104c:803b | 1025:011c | Texas I... | PCIxx12 Flash Media Contr... | 9     | tifm_7xx1  | 1BDA4268F4 |
| 104c:803b | 104d:8212 | Texas I... | PCIxx12 Flash Media Contr... | 9     | tifm_7xx1  | 6900BEE5AC |
| 104c:ac8f | 104d:8190 | Texas I... | PCI7420/7620 SD/MS-Pro Co... | 9     | tifm_7xx1  | 8E75F0E93F |
| 104c:803b | 103c:30b1 | Texas I... | PCIxx12 Flash Media Contr... | 8     | tifm_7xx1  | EEAEE9F1AD |
| 104c:8033 | 17c0:3007 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 7     | tifm_7xx1  | B115D6B061 |
| 104c:803b | 103c:30ad | Texas I... | PCIxx12 Flash Media Contr... | 7     | tifm_7xx1  | 25FFC80D33 |
| 104c:803b | 103c:30a3 | Texas I... | PCIxx12 Flash Media Contr... | 6     | tifm_7xx1  | A33E615CC5 |
| 104c:803b | 1179:ff03 | Texas I... | PCIxx12 Flash Media Contr... | 6     | tifm_7xx1  | 84D2D0D8CF |
| 104c:8033 | 103c:3082 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 5     | tifm_7xx1  | C98B9CF200 |
| 104c:8033 | 103c:30a4 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 5     | tifm_7xx1  | C2A5CB93AA |
| 104c:803b | 1025:006c | Texas I... | PCIxx12 Flash Media Contr... | 5     | tifm_7xx1  | 2D3698DEC2 |
| 104c:803b | 1025:0102 | Texas I... | PCIxx12 Flash Media Contr... | 5     | tifm_7xx1  | A59E16433A |
| 104c:803b | 103c:309f | Texas I... | PCIxx12 Flash Media Contr... | 5     | tifm_7xx1  | 3FFD093A67 |
| 1217:7130 | 1025:012b | O2 Micro   | Integrated MS/xD Controller  | 5     |            | A01F7549B8 |
| 1217:7130 | 107b:0390 | O2 Micro   | Integrated MS/xD Controller  | 5     |            | 716346340E |
| 1217:7130 | 1462:3fc1 | O2 Micro   | Integrated MS/xD Controller  | 5     |            | 800B19FF2D |
| 1217:7130 | 1462:3ff3 | O2 Micro   | Integrated MS/xD Controller  | 5     |            | 483C20774A |
| 1217:7130 | 1734:10c7 | O2 Micro   | Integrated MS/xD Controller  | 5     |            | 0D7EFB17BC |
| 1217:8330 | 10cf:16ae | O2 Micro   | OZ600 MS/xD Controller       | 5     |            | 1CB3267B57 |
| 104c:8033 | 1025:0066 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 4     | tifm_7xx1  | 50122B9E8E |
| 104c:8033 | 103c:099c | Texas I... | PCIxx21/PCIxx11 Flash Med... | 4     | tifm_7xx1  | 5F105DDA68 |
| 104c:8033 | 103c:3080 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 4     | tifm_7xx1  | FB937794C7 |
| 104c:8033 | 103c:309b | Texas I... | PCIxx21/PCIxx11 Flash Med... | 4     | tifm_7xx1  | B64833B0B1 |
| 104c:8033 | 1179:0001 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 4     | tifm_7xx1  | D5D7DAB02F |
| 104c:803b | 1025:0094 | Texas I... | PCIxx12 Flash Media Contr... | 4     | tifm_7xx1  | 9FE4562E0D |
| 104c:803b | 1025:0130 | Texas I... | PCIxx12 Flash Media Contr... | 4     | tifm_7xx1  | 2165E8969A |
| 104c:803b | 103c:30ac | Texas I... | PCIxx12 Flash Media Contr... | 4     | tifm_7xx1  | 50213B8AAB |
| 104c:803b | 103c:30b0 | Texas I... | PCIxx12 Flash Media Contr... | 4     | tifm_7xx1  | 14CC279C8C |
| 104c:803b | 104d:81fd | Texas I... | PCIxx12 Flash Media Contr... | 4     | tifm_7xx1  | 52E6107C87 |
| 104c:803b | 104d:820f | Texas I... | PCIxx12 Flash Media Contr... | 4     | tifm_7xx1  | 8D36EEE821 |
| 104c:803b | 152d:0753 | Texas I... | PCIxx12 Flash Media Contr... | 4     | tifm_7xx1  | 63BEE52058 |
| 104c:803b | 17aa:207c | Texas I... | PCIxx12 Flash Media Contr... | 4     | tifm_7xx1  | E609777F1D |
| 1217:7130 | 1025:010d | O2 Micro   | Integrated MS/xD Controller  | 4     |            | 287952FB68 |
| 1217:7130 | 1025:011a | O2 Micro   | Integrated MS/xD Controller  | 4     |            | 9B2C049705 |
| 1217:7130 | 1028:026f | O2 Micro   | Integrated MS/xD Controller  | 4     |            | 79951D3FA6 |
| 1217:7130 | 10cf:13c6 | O2 Micro   | Integrated MS/xD Controller  | 4     |            | 8648B42278 |
| 1217:7130 | 1462:4327 | O2 Micro   | Integrated MS/xD Controller  | 4     |            | 0DCF53C3D6 |
| 1217:7130 | 1462:7220 | O2 Micro   | Integrated MS/xD Controller  | 4     |            | E3C5F7A96F |
| 1217:8130 | 1025:038b | O2 Micro   | Integrated MS/MSPRO/xD Co... | 4     |            | 18D1FC7788 |
| 1217:8130 | 1028:041b | O2 Micro   | Integrated MS/MSPRO/xD Co... | 4     |            | 3AAE3F0B4B |
| 104c:8033 | 1025:007e | Texas I... | PCIxx21/PCIxx11 Flash Med... | 3     | tifm_7xx1  | 60873D0A0E |
| 104c:8033 | 103c:0934 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 3     | tifm_7xx1  | 453696FF5E |
| 104c:8033 | 103c:3085 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 3     | tifm_7xx1  | 07C5D7BA93 |
| 104c:8033 | 103c:3091 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 3     | tifm_7xx1  | F01F51C47C |
| 104c:8033 | 103c:309d | Texas I... | PCIxx21/PCIxx11 Flash Med... | 3     | tifm_7xx1  | 837230178B |
| 104c:8033 | 161f:203d | Texas I... | PCIxx21/PCIxx11 Flash Med... | 3     | tifm_7xx1  | A942E40F27 |
| 104c:803b | 104d:900f | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | 055903703C |
| 104c:803b | 107b:0366 | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | BCF6858E7D |
| 104c:803b | 152d:0763 | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | BA6F03E565 |
| 104c:803b | 1854:005f | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | 7611C8EBB8 |
| 1217:7130 | 1028:0275 | O2 Micro   | Integrated MS/xD Controller  | 3     |            | A359187C45 |
| 1217:7130 | 17aa:3a21 | O2 Micro   | Integrated MS/xD Controller  | 3     |            | BF3EE678DA |
| 1217:8130 | 1028:02bb | O2 Micro   | Integrated MS/MSPRO/xD Co... | 3     |            | 95DC1639D3 |
| 1217:8130 | 10cf:1568 | O2 Micro   | Integrated MS/MSPRO/xD Co... | 3     |            | 9B2FC1E55F |
| 1217:8231 | 1028:04e4 | O2 Micro   | O2Micro Integrated MS/MSP... | 3     |            | 0BDB8E28F5 |
| 104c:8033 | 103c:308b | Texas I... | PCIxx21/PCIxx11 Flash Med... | 2     | tifm_7xx1  | 7945895A4E |
| 104c:8033 | 107b:0460 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 2     | tifm_7xx1  | 53EC93715E |
| 104c:8033 | 1734:1092 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 2     | tifm_7xx1  | 4D0D913872 |
| 104c:8033 | 1734:1098 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 2     | tifm_7xx1  | 33762202EF |
| 104c:803b | 1025:0096 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 070206A279 |
| 104c:803b | 1025:0129 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | D1A0E6A322 |
| 104c:803b | 103c:30a5 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 87B9F12D09 |
| 104c:803b | 104d:8207 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 63E4911A68 |
| 104c:803b | 1558:0661 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 2A6A5EFE01 |
| 104c:803b | 1631:c018 | Texas I... | PCIxx12 Flash Media Contr... | 2     | tifm_7xx1  | 210B740311 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e03 | 17aa:3977 | Intel      | 7 Series Chipset Family 6... | 473   | ahci       | 5872E567EC |
| 8086:1c03 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 275   | ahci       | 21DB34139A |
| 8086:9c03 | 17aa:3978 | Intel      | 8 Series SATA Controller ... | 275   | ahci       | B1B8196F26 |
| 8086:2929 | 17aa:20f8 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 256   | ahci       | DB936567F0 |
| 8086:27c1 | 1043:83ad | Intel      | NM10/ICH7 Family SATA Con... | 245   | ahci       | 2117F02A4F |
| 8086:3b2f | 17aa:2168 | Intel      | 5 Series/3400 Series Chip... | 234   | ahci       | 5DC4A1E557 |
| 8086:1e03 | 8086:7270 | Intel      | 7 Series Chipset Family 6... | 167   | ahci       | EC1ABD9485 |
| 8086:1e03 | 17aa:21f3 | Intel      | 7 Series Chipset Family 6... | 162   | ahci       | C9503690D6 |
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 160   | ahci       | 008C187A8B |
| 8086:3b29 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 159   | ahci       | 11F1CDC49A |
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 159   | ahci       | 71A92492E3 |
| 8086:1c03 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 153   | ahci       | A53D0DE98A |
| 8086:1c03 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 144   | ahci       | 74547808D3 |
| 8086:1c03 | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 143   | ahci       | 438D785F0E |
| 8086:1e03 | 1025:0649 | Intel      | 7 Series Chipset Family 6... | 143   | ahci       | 52667487D2 |
| 8086:8c03 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 141   | ahci       | 7FB630F632 |
| 8086:1c03 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 139   | ahci       | B420F25ED4 |
| 8086:31e3 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 135   | ahci       | 170B220F5B |
| 8086:1e03 | 17aa:21fa | Intel      | 7 Series Chipset Family 6... | 133   | ahci       | 50D562CAB5 |
| 8086:2929 | 17aa:3a1a | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 130   | ahci       | 1BBEC614AA |
| 8086:3b29 | 17aa:38c1 | Intel      | 5 Series/3400 Series Chip... | 129   | ahci       | CEAF1A4989 |
| 10de:0ab9 | 10de:cb79 | Nvidia     | MCP79 AHCI Controller        | 127   | ahci       | F982A2F6CC |
| 8086:3b29 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 123   | ahci       | 03E0270FDD |
| 8086:9d03 | 17aa:386a | Intel      | Sunrise Point-LP SATA Con... | 123   | ahci       | 19226582D9 |
| 8086:1e03 | 1043:124d | Intel      | 7 Series Chipset Family 6... | 118   | ahci       | 08930695BC |
| 1022:7801 | 17aa:3801 | AMD        | FCH SATA Controller [AHCI... | 115   | ahci       | 779BFC3B47 |
| 8086:1c03 | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 115   | ahci       | FF37A9C00D |
| 8086:1c03 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 114   | ahci       | 660A6B9E20 |
| 144d:a801 | 144d:a801 | Samsung... | Electronics SATA controller  | 112   | ahci       | C0ED6370C5 |
| 8086:a353 | 1028:0905 | Intel      | Cannon Lake Mobile PCH SA... | 112   | ahci       | 9CDE952049 |
| 8086:31e3 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 110   | ahci       | 021617B9A0 |
| 8086:3b29 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 109   | ahci       | C172C655DE |
| 8086:9c03 | 17aa:220c | Intel      | 8 Series SATA Controller ... | 109   | ahci       | 4C600416F9 |
| 8086:1e03 | 1025:064b | Intel      | 7 Series Chipset Family 6... | 108   | ahci       | B732F94275 |
| 1022:7904 | 103c:8330 | AMD        | FCH SATA Controller [AHCI... | 107   | ahci       | 5671BA2F85 |
| 8086:02d3 | 17aa:5079 | Intel      | Comet Lake SATA AHCI Cont... | 107   | ahci       | 0BC4073D23 |
| 8086:1e03 | 17aa:21f6 | Intel      | 7 Series Chipset Family 6... | 107   | ahci       | 9ECBB7A946 |
| 8086:1c03 | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 105   | ahci       | A8FD68FCCC |
| 8086:2829 | 17aa:20a7 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 105   | ahci       | 8A05529E0C |
| 8086:1e03 | 17aa:5002 | Intel      | 7 Series Chipset Family 6... | 104   | ahci       | 2BA1AA7C62 |
| 8086:9d03 | 1025:1193 | Intel      | Sunrise Point-LP SATA Con... | 102   | ahci       | E922639FF6 |
| 8086:a353 | 1028:087c | Intel      | Cannon Lake Mobile PCH SA... | 97    | ahci       | 31A6F21CCD |
| 8086:8c03 | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 96    | ahci       | 4EC9EAAC2F |
| 8086:1e03 | 10cf:16e2 | Intel      | 7 Series Chipset Family 6... | 94    | ahci       | B2D4A08D24 |
| 8086:9c03 | 1025:0866 | Intel      | 8 Series SATA Controller ... | 94    | ahci       | 58B4832D53 |
| 8086:9d03 | 103c:8079 | Intel      | Sunrise Point-LP SATA Con... | 94    | ahci       | 0FA8058EEB |
| 8086:1c03 | 104d:908b | Intel      | 6 Series/C200 Series Chip... | 93    | ahci       | F88D733F75 |
| 8086:9c03 | 103c:198f | Intel      | 8 Series SATA Controller ... | 93    | ahci       | 6573923D55 |
| 8086:27c1 | 1025:0349 | Intel      | NM10/ICH7 Family SATA Con... | 92    | ahci       | DA7BA5D53F |
| 8086:2929 | 1028:02aa | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 92    | ahci       | F0D0F92FD9 |
| 8086:9c03 | 1028:0651 | Intel      | 8 Series SATA Controller ... | 92    | ahci       | E1A816CC42 |
| 8086:1c03 | 103c:161c | Intel      | 6 Series/C200 Series Chip... | 91    | ahci       | 42EEAF84D9 |
| 8086:1c03 | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 91    | ahci       | F8B9508953 |
| 8086:1e03 | 1025:0647 | Intel      | 7 Series Chipset Family 6... | 91    | ahci       | A5268098B2 |
| 8086:1c03 | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 89    | ahci       | 389E1A52A6 |
| 8086:1e03 | 103c:179b | Intel      | 7 Series Chipset Family 6... | 89    | ahci       | 7D39BC1331 |
| 8086:9d03 | 1043:12d1 | Intel      | Sunrise Point-LP SATA Con... | 89    | ahci       | 570905286F |
| 8086:1e03 | 1043:1477 | Intel      | 7 Series Chipset Family 6... | 87    | ahci       | 62C6944A06 |
| 8086:2929 | 1043:1867 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 87    | ahci       | 498362846A |
| 8086:0f23 | 17aa:3905 | Intel      | Atom Processor E3800 Seri... | 86    | ahci       | 4C8E456405 |
| 8086:0f23 | 17aa:3909 | Intel      | Atom Processor E3800 Seri... | 86    | ahci       | BAC9935F0B |
| 8086:1e03 | 1043:14c7 | Intel      | 7 Series Chipset Family 6... | 86    | ahci       | 53842E648E |
| 8086:9c03 | 1025:0775 | Intel      | 8 Series SATA Controller ... | 85    | ahci       | 2729E1919C |
| 8086:9c83 | 17aa:5034 | Intel      | Wildcat Point-LP SATA Con... | 83    | ahci       | 6131E3C22A |
| 8086:1e03 | 1179:fb31 | Intel      | 7 Series Chipset Family 6... | 82    | ahci       | 834D15C08C |
| 8086:1c03 | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 81    | ahci       | C40BAA791F |
| 8086:5ae3 | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 81    | ahci       | 9F12330C51 |
| 1002:4391 | 103c:3577 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 79    | ahci       | C0FCCB63BB |
| 1022:7904 | 103c:84ac | AMD        | FCH SATA Controller [AHCI... | 78    | ahci       | D22A5E8410 |
| 8086:1e03 | 103c:1854 | Intel      | 7 Series Chipset Family 6... | 78    | ahci       | 21FB6389E7 |
| 8086:9d03 | 1028:078b | Intel      | Sunrise Point-LP SATA Con... | 78    | ahci       | 4F60F64204 |
| 8086:1e03 | 144d:c652 | Intel      | 7 Series Chipset Family 6... | 74    | ahci       | C83A466F92 |
| 1022:7901 | 1025:1192 | AMD        | FCH SATA Controller [AHCI... | 73    | ahci       | CDC742CD03 |
| 8086:9c03 | 17aa:2214 | Intel      | 8 Series SATA Controller ... | 73    | ahci       | F100B7CDB9 |
| 8086:2829 | 1028:022f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 72    | ahci       | 06130B24C5 |
| 8086:9d03 | 1025:1295 | Intel      | Sunrise Point-LP SATA Con... | 72    | ahci       | BEDAFBAD9B |
| 8086:9c83 | 103c:2216 | Intel      | Wildcat Point-LP SATA Con... | 71    | ahci       | 304747E4C6 |
| 8086:9d03 | 103c:832a | Intel      | Sunrise Point-LP SATA Con... | 71    | ahci       | A7BDFE8774 |
| 8086:1c03 | 1179:fc30 | Intel      | 6 Series/C200 Series Chip... | 70    | ahci       | 60EB674C8F |
| 8086:9c83 | 17aa:2226 | Intel      | Wildcat Point-LP SATA Con... | 69    | ahci       | A5D677976F |
| 8086:9d03 | 1025:115f | Intel      | Sunrise Point-LP SATA Con... | 69    | ahci       | 9756CE58FC |
| 8086:a103 | 1028:07be | Intel      | HM170/QM170 Chipset SATA ... | 69    | ahci       | 6EE00932DC |
| 1022:7901 | 17aa:380a | AMD        | FCH SATA Controller [AHCI... | 67    | ahci       | E57C2FB16D |
| 1022:7804 | 144d:c0da | AMD        | FCH SATA Controller [AHCI... | 66    | ahci       | 541B3E9CBA |
| 8086:1e03 | 103c:17f6 | Intel      | 7 Series Chipset Family 6... | 65    | ahci       | D0705EF193 |
| 8086:2829 | 1025:011f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 65    | ahci       | 2DA2F6A795 |
| 8086:9c03 | 1043:131d | Intel      | 8 Series SATA Controller ... | 65    | ahci       | 13FF923546 |
| 8086:3b29 | 1179:ff1e | Intel      | 5 Series/3400 Series Chip... | 64    | ahci       | C5883A9DA8 |
| 8086:9d03 | 17aa:5068 | Intel      | Sunrise Point-LP SATA Con... | 64    | ahci       | 893F642CBB |
| 8086:1c03 | 144d:c0b6 | Intel      | 6 Series/C200 Series Chip... | 63    | ahci       | 574B61FC95 |
| 8086:2829 | 106b:00a1 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 63    | ahci       | E31DDE7E74 |
| 8086:8c03 | 103c:1993 | Intel      | 8 Series/C220 Series Chip... | 63    | ahci       | 605367D5D4 |
| 8086:a353 | 17aa:3801 | Intel      | Cannon Lake Mobile PCH SA... | 63    | ahci       | AB6647F9DA |
| 8086:1e03 | 104d:90b8 | Intel      | 7 Series Chipset Family 6... | 62    | ahci       | 77DF70A98A |
| 8086:1e03 | 1179:ff1e | Intel      | 7 Series Chipset Family 6... | 62    | ahci       | E93FDA84E6 |
| 8086:2829 | 103c:30cc | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 62    | ahci       | 4E93C68985 |
| 8086:2929 | 1025:0212 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 62    | ahci       | F573488BDA |
| 8086:3b29 | 144d:c581 | Intel      | 5 Series/3400 Series Chip... | 62    | ahci       | 20D4A3A8F9 |
| 8086:9c83 | 1025:098a | Intel      | Wildcat Point-LP SATA Con... | 62    | ahci       | D8A334E94C |
| 1022:7901 | 1043:1e21 | AMD        | FCH SATA Controller [AHCI... | 61    | ahci       | B3DA27422D |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2850 | 1025:011f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 122   | ata_pii... | 6A05B72968 |
| 8086:2850 | 17aa:20a6 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 103   | pata_acpi  | 8A05529E0C |
| 8086:2850 | 1028:01f9 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 92    | pata_acpi  | E271885D51 |
| 8086:2850 | 1028:022f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 74    | pata_acpi  | 06130B24C5 |
| 8086:2828 | 1028:01f9 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 72    | pata_acpi  | E271885D51 |
| 8086:2850 | 106b:00a1 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 67    | pata_acpi  | E31DDE7E74 |
| 8086:2850 | 103c:30cc | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 62    | pata_acpi  | 4E93C68985 |
| 8086:2828 | 1025:011f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 61    | ata_pii... | 6A05B72968 |
| 1039:5513 | 1039:5513 | Silicon... | 5513 IDE Controller          | 56    | pata_acpi  | 1A587EFF16 |
| 10de:0759 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] IDE    | 53    | pata_am... | 67C143DFE9 |
| 10de:0ad0 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] SAT... | 52    | ahci, p... | 67C143DFE9 |
| 1002:439c | 1043:104c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 49    | pata_at... | 5516AC1695 |
| 1039:1183 | 1039:1183 | Silicon... | SATA Controller / IDE mode   | 49    | sata_si... | 660022B46F |
| 1039:5513 | 1558:0801 | Silicon... | 5513 IDE Controller          | 46    | pata_acpi  | F6E75312A4 |
| 8086:2850 | 1025:011e | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 46    | ata_pii... | 3C8537DFE3 |
| 8086:27c4 | 1025:0090 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 45    | ata_pii... | 4A0EE2EAA5 |
| 8086:27df | 17aa:200c | Intel      | 82801G (ICH7 Family) IDE ... | 44    | pata_acpi  | 784D057761 |
| 8086:27df | 8086:7270 | Intel      | 82801G (ICH7 Family) IDE ... | 44    | pata_acpi  | CC14C7FA2E |
| 8086:2850 | 1179:ff00 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 44    | pata_acpi  | 3F0EBD44AD |
| 8086:1e01 | 17aa:3977 | Intel      | 7 Series Chipset Family 4... | 43    | ata_pii... | D0AEB8AAFC |
| 8086:2850 | 103c:30c0 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 43    | ata_pii... | 4DEAD8CD75 |
| 8086:2a46 | 17aa:20ea | Intel      | Mobile 4 Series Chipset P... | 43    | pata_acpi  | DB936567F0 |
| 8086:2850 | 1025:0136 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 41    | pata_acpi  | 9357025BC9 |
| 8086:1e09 | 17aa:3977 | Intel      | 7 Series Chipset Family 2... | 40    | ata_pii... | D0AEB8AAFC |
| 8086:2850 | 103c:30d9 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 40    | pata_acpi  | 75719D651A |
| 1002:4376 | 1025:009f | AMD        | IXP SB4x0 IDE Controller     | 39    | pata_at... | D38F5B09D2 |
| 8086:2850 | 1025:0121 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 39    | pata_acpi  | 5D933E19AC |
| 8086:2928 | 17aa:20f7 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 39    | pata_acpi  | 73E76BAB10 |
| 1002:438c | 1028:01f5 | AMD        | SB600 IDE                    | 37    | pata_at... | 32C3521A2E |
| 8086:27c4 | 1179:ff00 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 37    | ata_pii... | 8E44C9EDAF |
| 8086:27c4 | 1028:01bd | Intel      | 82801GBM/GHM (ICH7-M Fami... | 36    | pata_acpi  | 3EB7729825 |
| 8086:27c4 | 8086:7270 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 36    | pata_acpi  | CC14C7FA2E |
| 1039:1183 | 1043:1cf7 | Silicon... | SATA Controller / IDE mode   | 34    | sata_si... | 40F5C93523 |
| 1039:1183 | 1558:0801 | Silicon... | SATA Controller / IDE mode   | 34    | sata_si... | F6E75312A4 |
| 1039:5513 | 1043:1cf7 | Silicon... | 5513 IDE Controller          | 34    | pata_acpi  | 40F5C93523 |
| 8086:1c01 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 34    | ata_pii... | 1E6D2C2FA7 |
| 8086:1c09 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 34    | ata_pii... | 1E6D2C2FA7 |
| 8086:27c4 | 1025:015b | Intel      | 82801GBM/GHM (ICH7-M Fami... | 34    | pata_acpi  | 19783E7AF3 |
| 8086:27c4 | 1179:ff10 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 32    | pata_acpi  | B6FB3D3EC3 |
| 8086:2850 | 1179:ff50 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 32    | ata_pii... | 5982884BE7 |
| 1002:4379 | 1002:4379 | AMD        | IXP SB4x0 Serial ATA Cont... | 31    | sata_si... | D38F5B09D2 |
| 10de:0550 | 1025:0126 | Nvidia     | MCP67 AHCI Controller        | 31    | pata_ac... | AA6D721BF2 |
| 10de:0550 | 103c:30cf | Nvidia     | MCP67 AHCI Controller        | 31    | ahci, p... | CB77A79EE8 |
| 8086:27df | 103c:30d5 | Intel      | 82801G (ICH7 Family) IDE ... | 31    | ata_pii... | E94B7216D1 |
| 8086:27df | 17aa:3810 | Intel      | 82801G (ICH7 Family) IDE ... | 31    | ata_pii... | FFC6990547 |
| 8086:27df | 103c:30bb | Intel      | 82801G (ICH7 Family) IDE ... | 30    | pata_acpi  | 5F6D9F025A |
| 8086:27c0 | 1043:83ad | Intel      | NM10/ICH7 Family SATA Con... | 29    | ata_pii... | 747B90D33C |
| 8086:27df | 103c:30a2 | Intel      | 82801G (ICH7 Family) IDE ... | 29    | ata_pii... | 204F122174 |
| 8086:2850 | 104d:9005 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 29    | pata_acpi  | BD472575F4 |
| 8086:27c4 | 1028:01c2 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 28    | ata_pii... | 116568909E |
| 8086:2828 | 17aa:20a8 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 27    | pata_acpi  | E1B3B6E090 |
| 1002:438c | 1043:1417 | AMD        | SB600 IDE                    | 26    | pata_at... | E575C47A9F |
| 1002:438c | 1043:1627 | AMD        | SB600 IDE                    | 26    | pata_at... | 0451B6DB0A |
| 1039:1183 | 1043:19e7 | Silicon... | SATA Controller / IDE mode   | 26    | sata_si... | 667E25F2DD |
| 1039:5513 | 1043:19e7 | Silicon... | 5513 IDE Controller          | 26    | pata_acpi  | 667E25F2DD |
| 10de:0560 | 103c:30cf | Nvidia     | MCP67 IDE Controller         | 26    | pata_am... | CB77A79EE8 |
| 8086:27c4 | 1043:830f | Intel      | 82801GBM/GHM (ICH7-M Fami... | 25    | pata_acpi  | 0479F1DB7F |
| 8086:2828 | 104d:9015 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 25    | pata_acpi  | 9AC5C739FF |
| 8086:2850 | 1028:01fe | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 25    | ata_pii... | 4D9D478FFC |
| 8086:2850 | 104d:902d | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 25    | pata_acpi  | B97D7A8C66 |
| 8086:3b2e | 17aa:2169 | Intel      | 5 Series/3400 Series Chip... | 25    | pata_acpi  | 41032E0F42 |
| 8086:3b66 | 10cf:152e | Intel      | 5 Series/3400 Series Chip... | 25    | pata_acpi  | F220F9AC45 |
| 10de:0560 | 1025:0126 | Nvidia     | MCP67 IDE Controller         | 24    | pata_am... | AA6D721BF2 |
| 8086:3b2d | 17aa:216a | Intel      | 5 Series/3400 Series Chip... | 24    | pata_acpi  | 6D77D65333 |
| 1002:438c | 103c:30c2 | AMD        | SB600 IDE                    | 23    | pata_at... | 46BE5BD9F4 |
| 1039:1183 | 1039:1180 | Silicon... | SATA Controller / IDE mode   | 23    | sata_si... | 1A587EFF16 |
| 1039:5513 | 1019:5a00 | Silicon... | 5513 IDE Controller          | 23    | pata_sis   | 660022B46F |
| 8086:27c4 | 144d:ca00 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 23    | ata_pii... | 768DC05536 |
| 1002:438c | 1028:022a | AMD        | SB600 IDE                    | 22    | pata_at... | 6D6B004B73 |
| 1002:438c | 144d:c034 | AMD        | SB600 IDE                    | 22    | pata_at... | EFBF027F96 |
| 8086:27c4 | 17aa:200e | Intel      | 82801GBM/GHM (ICH7-M Fami... | 22    | pata_acpi  | 6652275E18 |
| 8086:2850 | 1043:14e7 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 22    | ata_pii... | 2494100ECB |
| 8086:2850 | 1179:ff1c | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 22    | pata_acpi  | 8B7FBF3DE6 |
| 1022:780c | 103c:358d | AMD        | FCH IDE Controller           | 21    | pata_at... | 46E5EAF436 |
| 8086:27c4 | 1043:1317 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 21    | ata_pii... | A54C655AE8 |
| 8086:27df | 10cf:1385 | Intel      | 82801G (ICH7 Family) IDE ... | 21    | pata_acpi  | 8648B42278 |
| 8086:2850 | 103c:30c5 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 21    | ata_pii... | 7E17CF2706 |
| 8086:2850 | 103c:30d8 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 21    | pata_acpi  | 90714DE680 |
| 8086:2850 | 103c:3618 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 21    | ata_piix   | E6E060CA51 |
| 8086:2850 | 1179:ff40 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 21    | pata_acpi  | 1C418BBCEF |
| 8086:2a46 | 1028:0233 | Intel      | Mobile 4 Series Chipset P... | 21    | pata_acpi  | 2EA2BB4954 |
| 1002:439c | 1043:101c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 20    | pata_at... | 6C0B7D6353 |
| 8086:2653 | 1014:056a | Intel      | 82801FBM (ICH6M) SATA Con... | 20    | pata_acpi  | C25352D131 |
| 8086:27c4 | 17aa:3835 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 20    | pata_acpi  | 1AD049BF43 |
| 1002:439c | 1025:036e | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 19    | pata_at... | AE7E2AE414 |
| 1002:439c | 17aa:3937 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 19    | pata_at... | F32877769D |
| 10de:0265 | 103c:30b7 | Nvidia     | MCP51 IDE                    | 19    | pata_am... | C28788427E |
| 10de:0266 | 103c:30b7 | Nvidia     | MCP51 Serial ATA Controller  | 19    | sata_nv... | C28788427E |
| 8086:27df | 1025:012e | Intel      | 82801G (ICH7 Family) IDE ... | 19    | ata_pii... | 6EAAA7BA4F |
| 8086:3b28 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 19    | pata_acpi  | D9EF3C97BB |
| 8086:3b2d | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 19    | pata_acpi  | D9EF3C97BB |
| 8086:27c4 | 1025:0107 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 18    | ata_pii... | 502B2847A6 |
| 8086:27df | 103c:30a5 | Intel      | 82801G (ICH7 Family) IDE ... | 18    | pata_acpi  | D37099A83D |
| 8086:2850 | 1028:01f2 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 18    | pata_acpi  | D115C79F7A |
| 8086:2a06 | 103c:30c5 | Intel      | Mobile PM965/GM965 PT IDE... | 18    | pata_acpi  | 7E17CF2706 |
| 8086:2850 | 103c:30be | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 17    | pata_acpi  | 5910FA85E5 |
| 8086:2850 | 103c:30cd | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 17    | pata_acpi  | FD5BD80A7D |
| 8086:2850 | 1179:ff64 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 17    | pata_acpi  | 6472A832B4 |
| 8086:2928 | 1043:1867 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 17    | ata_pii... | 0609E0680E |
| 8086:292d | 1043:1867 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 17    | ata_pii... | 0609E0680E |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 1932  | nvme       | 6670E1C145 |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 497   | nvme       | 1AB69568A5 |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 496   | nvme       | 3A3BF28C3A |
| 15b7:5006 | 15b7:5006 | Sandisk    | WD Black SN750 / PC SN730... | 384   | nvme       | 011A257801 |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | BC501 NVMe Solid State Dr... | 371   | nvme       | 052B95BA1D |
| 15b7:5003 | 15b7:5003 | Sandisk    | WD Blue SN500 / PC SN520 ... | 369   | nvme       | CDD4DC075D |
| 144d:a809 | 144d:a801 | Samsung... | NVMe Controller              | 354   | nvme       | B7EC4606A3 |
| 1179:011a | 1179:0001 | Toshiba... | XG6 NVMe SSD Controller      | 276   | nvme       | 11F1E42FBE |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 246   | nvme       | 9358C3AFBF |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 244   | nvme       | F7A69152B9 |
| 1e0f:0001 | 1e0f:0001 | KIOXIA     | Non-Volatile memory contr... | 226   | nvme       | FC1870A101 |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/SN750 / PC ... | 220   | nvme       | 1060065F34 |
| 1179:0113 | 1179:0001 | Toshiba... | BG3 NVMe SSD Controller      | 217   | nvme       | 62C94909C7 |
| 1c5c:1339 | 1c5c:0000 | SK Hynix   | BC511                        | 209   | nvme       | BD16A61719 |
| 2646:5008 | 2646:5008 | Kingsto... | U-SNS8154P3 NVMe SSD         | 207   | nvme       | 95561AE2CF |
| 15b7:5009 | 15b7:5009 | Sandisk    | WD Blue SN550 NVMe SSD       | 190   | nvme       | E18B16565F |
| 8086:0000 |           | Intel      | PROSet/Wireless WiFi Soft... | 180   | nvme       | 883283C763 |
| 1344:5410 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 171   | nvme       | E50E7E65B4 |
| 1c5c:1527 | 1c5c:1527 | SK Hynix   | PC401 NVMe Solid State Dr... | 154   | nvme       | A8C47AD7F6 |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 149   | nvme       | 31850CE796 |
| 15b7:5005 | 15b7:5005 | Sandisk    | PC SN520 NVMe SSD            | 146   | nvme       | AB6647F9DA |
| 1c5c:1627 | 1c5c:1627 | SK Hynix   | Non-Volatile memory contr... | 137   | nvme       | 02D50458CE |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 125   | nvme       | 54BAAAD690 |
| 1179:0115 | 1179:0001 | Toshiba... | XG4 NVMe SSD Controller      | 107   | nvme       | 02894A3C1D |
| 1c5c:1639 | 1c5c:1639 | SK Hynix   | Non-Volatile memory contr... | 105   | nvme       | FBBAF8088B |
| 126f:2263 | 126f:2263 | Silicon... | SM2263EN/SM2263XT SSD Con... | 99    | nvme       | F03341D873 |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 94    | nvme       | 5ADBF6A949 |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 78    | nvme       | CC69851E7F |
| 2646:500c | 2646:500c | Kingsto... | Technology Company Non-Vo... | 77    | nvme       | F504E72617 |
| c0a9:2263 | c0a9:2263 | Micron/... | P1 NVMe PCIe SSD             | 74    | nvme       | 0D9F5609E7 |
| 1cc4:5008 | 1cc4:5008 | Union M... | Non-Volatile memory contr... | 73    | nvme       | D090EAF727 |
| 2646:2263 | 2646:2263 | Kingsto... | A2000 NVMe SSD               | 69    | nvme       | 5756ECAB4B |
| 15b7:5004 | 15b7:5004 | Sandisk    | PC SN520 NVMe SSD            | 64    | nvme       | DB1162156B |
| 1179:010f | 1179:0001 | Toshiba... | NVMe Controller              | 58    | nvme       | 6FE52D4F4F |
| 1cc1:33f3 | 1cc1:33f3 | ADATA T... | Non-Volatile memory contr... | 53    | nvme       | ED812AF95A |
| 15b7:5008 | 15b7:5008 | Sandisk    | Non-Volatile memory contr... | 51    | nvme       | 80A31F37F4 |
| 1344:5405 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 50    | nvme       | F301495B9C |
| 126f:2262 | 126f:2262 | Silicon... | SM2262/SM2262EN SSD Contr... | 45    | nvme       | 0A4BF488D4 |
| 8086:0975 | 8086:8410 | Intel      | Non-Volatile memory contr... | 45    | nvme       | 6B44551C8C |
| 8086:0975 | 8086:8510 | Intel      | Non-Volatile memory contr... | 44    | nvme       | 6B44551C8C |
| 1cc1:33f8 | 1cc1:33f8 | ADATA T... | Non-Volatile memory contr... | 38    | nvme       | 80CF3DC8E7 |
| 106b:2005 | 106b:1800 | Apple      | ANS2 NVMe Controller         | 36    | nvme       | 2BDDF8B98A |
| 1e95:9100 | 126f:2263 | Solid S... | Non-Volatile memory contr... | 36    | nvme       | DE11AB3CC4 |
| 1c5c:174a | 1c5c:174a | SK Hynix   | NVMe SSD Controller          | 35    | nvme       | DB4A212405 |
| 10ec:5763 | 10ec:5763 | Realtek... | Realtek Non-Volatile memo... | 34    | nvme       | EEE4DBBB99 |
| 14a4:2300 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 31    | nvme       | 7FD687D091 |
| 1987:5008 | 1987:5008 | Phison ... | NVMe Storage Controller      | 30    | nvme       | AE668F7B16 |
| 1987:5013 | 1987:5013 | Phison ... | PS5013 E13 NVMe Controller   | 28    | nvme       | F19E7920CA |
| 106b:2003 | 106b:2003 | Apple      | S3X NVMe Controller          | 27    | nvme       | 8030B99150 |
| 10ec:5762 | 10ec:5762 | Realtek... | RTS5763DL NVMe SSD Contro... | 27    | nvme       | 1AED3EE552 |
| 144d:a80a | 144d:a801 | Samsung... | NVMe SSD Controller PM9A1... | 26    | nvme       | 71848EA8F6 |
| 14a4:9100 | 126f:2263 | Lite-On... | NVMe Controller              | 22    | nvme       | 649DBCEEFF |
| 17aa:0003 | 17aa:1003 | Lenovo     | Non-Volatile memory contr... | 22    | nvme       | F665CFA22E |
| 17aa:0006 | 17aa:1006 | Lenovo     | Non-Volatile memory contr... | 21    | nvme       | 1649C0AE85 |
| 17aa:0004 | 17aa:1004 | Lenovo     | Non-Volatile memory contr... | 20    | nvme       | DE4F669B51 |
| c0a9:540a | c0a9:540a | Micron/... | P2 NVMe PCIe SSD             | 20    | nvme       | BEF33BDD29 |
| 17aa:0005 | 17aa:1005 | Lenovo     | Non-Volatile memory contr... | 18    | nvme       | 37FD15B69E |
| 1987:5016 | 1987:5016 | Phison ... | E16 PCIe4 NVMe Controller    | 18    | nvme       | B093A6F0EE |
| 8086:2522 | 8086:3810 | Intel      | NVMe Optane Memory Series    | 17    | nvme       | 2198E565BF |
| 1344:5404 | 1344:2100 | Micron ... | Non-Volatile memory contr... | 15    | nvme       | B70A62225D |
| 1d97:1160 | 1d97:1160 | Shenzhe... | Non-Volatile memory contr... | 14    | nvme       | 02F641EA60 |
| 15b7:5001 | 1b4b:1093 | Sandisk    | WD Black NVMe SSD            | 13    | nvme       | BC63393A91 |
| 15b7:5007 | 15b7:5007 | Sandisk    | Non-Volatile memory contr... | 13    | nvme       | 4157528079 |
| 1bb1:5012 | 1bb1:5012 | Seagate... | FireCuda 510 SSD             | 12    | nvme       | 31CD72DB1B |
| 1c5c:1284 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 12    | nvme       | DBEA4F6B5F |
| 14a4:2100 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 11    | nvme       | 471A5FED37 |
| 14a4:2200 | 1b4b:1093 | Lite-On... | Lite-On Non-Volatile memo... | 11    | nvme       | DB99936C38 |
| 1cc4:6202 | 1cc4:1cc4 | Union M... | Non-Volatile memory contr... | 11    | nvme       | 1697AC5B27 |
| 1c5c:1283 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 10    | nvme       | 97DBD7A2D0 |
| 1344:5404 | 1344:1100 | Micron ... | Non-Volatile memory contr... | 8     | nvme       | 5707E7AE37 |
| 14a4:3500 | 1b4b:1092 | Lite-On... | Non-Volatile memory contr... | 8     | nvme       | 969B2E9724 |
| 1c5c:1285 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 8     | nvme       | C0542C238C |
| 1cc4:5012 | 1cc4:5012 | Union M... | Non-Volatile memory contr... | 8     | nvme       | 9CD4E14D95 |
| 1cc4:2263 | 1cc4:1cc4 | Union M... | Non-Volatile memory contr... | 7     | nvme       | 4DE4650899 |
| 1cc4:6203 | 1cc4:1cc4 | Union M... | Non-Volatile memory contr... | 7     | nvme       | 90BA83BEAD |
| 106b:2001 | 106b:2001 | Apple      | S1X NVMe Controller          | 6     | nvme       | 9D1694385F |
| 2646:2262 | 2646:2262 | Kingsto... | KC2000 NVMe SSD              | 6     | nvme       | 6D2CB2D750 |
| 2646:500d | 2646:500d | Kingsto... | OM3PDP3 NVMe SSD             | 6     | nvme       | D88C558CDA |
| c0a9:5403 | c0a9:2100 | Micron/... | NVMe Controller              | 6     | nvme       | B3DA27422D |
| 10ec:5760 | 5760:10ec | Realtek... | Realtek Non-Volatile memo... | 5     | nvme       | 7D0B344759 |
| 14a4:23f1 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 5     | nvme       | FCF1A988CF |
| 1bb1:5016 | 1bb1:5016 | Seagate... | FireCuda 520 SSD             | 5     | nvme       | 33402F594E |
| 1c5c:1504 | 0100:1093 | SK Hynix   | SC300 512GB M.2 2280 SATA... | 5     | nvme       | 66C6D53439 |
| 1cc1:8201 | 1cc1:1cc1 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 5     | nvme       | F03341D873 |
| c0a9:5412 | c0a9:0100 | Micron/... | Non-Volatile memory contr... | 5     | nvme       | B82B8BFC07 |
| 10ec:5765 | 10ec:5765 | Realtek... | Realtek Non-Volatile memo... | 4     | nvme       | 0449B14156 |
| 14a4:22f1 | 1b4b:1093 | Lite-On... | M8Pe Series NVMe SSD         | 4     | nvme       | 090F949643 |
| 1e0f:0009 | 1e0f:0001 | KIOXIA     | NVMe SSD                     | 4     | nvme       | DC8521E74C |
| 8086:2522 | 8086:3806 | Intel      | NVMe Optane Memory Series    | 4     | nvme       | 3AE7D1367D |
| 8086:faf0 | 8086:390e | Intel      | Non-Volatile memory contr... | 4     | nvme       | 4B127C0BA4 |
| c0a9:5403 | c0a9:1100 | Micron/... | NVMe Controller              | 4     | nvme       | 8E1F902D84 |
| 1cc4:17ab | 1cc4:1007 | Union M... | NVMe 256G SSD device         | 3     | nvme       | 0A6B310E81 |
| 1e95:3500 | 1b4b:1092 | Solid S... | Non-Volatile memory contr... | 3     | nvme       | 3F74A71C6E |
| 126f:2260 | 126f:2260 | Silicon... | Non-Volatile memory contr... | 2     | nvme       | 7484F1F7B0 |
| 14a4:5100 | 14a4:5100 | Lite-On... | Non-Volatile memory contr... | 2     | nvme       | 58F412DE26 |
| 15b7:5011 | 15b7:5011 | Sandisk    | WD Black SN850               | 2     | nvme       | 6F0263CC5E |
| 1987:5007 | 1987:5007 | Phison ... | E7 NVMe Controller           | 2     | nvme       | 586FBB553D |
| 1b85:6018 | 1b85:6018 | OCZ Tec... | RD400/400A SSD               | 2     | nvme       | 9C550CFCA2 |
| 1cc4:17aa | 1cc4:1008 | Union M... | Non-Volatile memory contr... | 2     | nvme       | DD90911F14 |
| 1cc4:17aa | 1cc4:17aa | Union M... | Non-Volatile memory contr... | 2     | nvme       | 39B121F107 |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:282a | 1025:1331 | Intel      | 82801 Mobile SATA Control... | 98    | intel_n... | 38688703F4 |
| 8086:282a | 1028:0233 | Intel      | 82801 Mobile SATA Control... | 87    | ahci       | 2A4C5F6EEC |
| 8086:282a | 1028:0534 | Intel      | 82801 Mobile SATA Control... | 79    | ahci       | 98420A7D92 |
| 8086:282a | 1028:0493 | Intel      | 82801 Mobile SATA Control... | 77    | ahci       | 33617DD1A8 |
| 8086:282a | 1028:040a | Intel      | 82801 Mobile SATA Control... | 76    | ahci       | 7E35C63842 |
| 8086:282a | 103c:84a6 | Intel      | 82801 Mobile SATA Control... | 61    | ahci       | 197CBC5A5D |
| 8086:282a | 1028:0810 | Intel      | 82801 Mobile SATA Control... | 58    | ahci       | 2FD333BC52 |
| 8086:282a | 1028:05cb | Intel      | 82801 Mobile SATA Control... | 47    | ahci       | EF82F4635D |
| 8086:282a | 103c:1818 | Intel      | 82801 Mobile SATA Control... | 45    | ahci       | B9FD7914E2 |
| 8086:282a | 17aa:380f | Intel      | 82801 Mobile SATA Control... | 45    | ahci       | 27B310BDD9 |
| 8086:282a | 1025:1264 | Intel      | 82801 Mobile SATA Control... | 44    | ahci       | 99EE0E5718 |
| 8086:282a | 1025:1333 | Intel      | 82801 Mobile SATA Control... | 37    | intel_n... | CE68155512 |
| 8086:282a | 1028:0535 | Intel      | 82801 Mobile SATA Control... | 35    | ahci       | 2E9B8200A9 |
| 8086:282a | 1028:062e | Intel      | 82801 Mobile SATA Control... | 35    | ahci       | FFEE376E78 |
| 8086:282a | 17aa:3814 | Intel      | 82801 Mobile SATA Control... | 34    | ahci       | E2D1740F3A |
| 8086:282a | 103c:8532 | Intel      | 82801 Mobile SATA Control... | 33    | ahci       | 92D97521BC |
| 8086:282a | 103c:86c9 | Intel      | 82801 Mobile SATA Control... | 33    | ahci       | B40784D2C7 |
| 8086:9a0b | 8086:0000 | Intel      | Volume Management Device ... | 33    | vmd        | B63698A4AF |
| 8086:282a | 1028:05be | Intel      | 82801 Mobile SATA Control... | 32    | ahci       | B704F13C9D |
| 8086:282a | 1043:1961 | Intel      | 82801 Mobile SATA Control... | 32    | ahci       | DA20CA4C64 |
| 8086:282a | 1043:1311 | Intel      | 82801 Mobile SATA Control... | 31    | ahci       | AF70469300 |
| 8086:282a | 1028:05ca | Intel      | 82801 Mobile SATA Control... | 29    | ahci       | 9E790BA3F0 |
| 8086:282a | 1028:05bd | Intel      | 82801 Mobile SATA Control... | 28    | ahci       | FCD8E5D146 |
| 8086:282a | 1028:024f | Intel      | 82801 Mobile SATA Control... | 27    | ahci       | 3BDEE6855C |
| 8086:282a | 1028:0494 | Intel      | 82801 Mobile SATA Control... | 27    | ahci       | E58B9D7EA5 |
| 8086:282a | 1028:0798 | Intel      | 82801 Mobile SATA Control... | 27    | ahci       | 122ED0BBA8 |
| 8086:282a | 1028:024d | Intel      | 82801 Mobile SATA Control... | 25    | ahci       | 98D088D90D |
| 8086:282a | 1028:040b | Intel      | 82801 Mobile SATA Control... | 25    | ahci       | 6902EB0F50 |
| 8086:282a | 1028:06dc | Intel      | 82801 Mobile SATA Control... | 25    | ahci       | 1058573F86 |
| 8086:282a | 1028:081c | Intel      | 82801 Mobile SATA Control... | 25    | ahci       | A92377CB2A |
| 8086:282a | 17aa:3810 | Intel      | 82801 Mobile SATA Control... | 24    | ahci       | 1BDD9DDF9F |
| 8086:282a | 1028:0533 | Intel      | 82801 Mobile SATA Control... | 23    | ahci       | 4D7A7112A7 |
| 8086:282a | 103c:84a7 | Intel      | 82801 Mobile SATA Control... | 23    | ahci       | 3084883E0D |
| 8086:282a | 1025:128d | Intel      | 82801 Mobile SATA Control... | 22    | ahci       | D2E4A69C16 |
| 8086:282a | 1028:0532 | Intel      | 82801 Mobile SATA Control... | 22    | ahci       | 04D10F10D8 |
| 8086:282a | 1028:06de | Intel      | 82801 Mobile SATA Control... | 22    | ahci       | 9ED0C349F9 |
| 8086:282a | 1028:086f | Intel      | 82801 Mobile SATA Control... | 22    | ahci       | 927F243CBC |
| 8086:282a | 1028:053c | Intel      | 82801 Mobile SATA Control... | 21    | ahci       | ED6B3B5754 |
| 8086:282a | 1043:1fc0 | Intel      | 82801 Mobile SATA Control... | 21    | ahci       | 6456EB3B2D |
| 8086:282a | 1028:0410 | Intel      | 82801 Mobile SATA Control... | 20    | ahci       | 4135CD0970 |
| 8086:282a | 1028:0492 | Intel      | 82801 Mobile SATA Control... | 20    | ahci       | B9503F222C |
| 8086:282a | 1028:05de | Intel      | 82801 Mobile SATA Control... | 20    | ahci       | EA59351ECE |
| 8086:282a | 103c:86c8 | Intel      | 82801 Mobile SATA Control... | 20    | ahci       | BE83DBD275 |
| 8086:282a | 1028:04a3 | Intel      | 82801 Mobile SATA Control... | 19    | ahci       | F11BC44848 |
| 8086:282a | 1028:07a7 | Intel      | 82801 Mobile SATA Control... | 19    | ahci       | BC9170F4CD |
| 8086:282a | 103c:8533 | Intel      | 82801 Mobile SATA Control... | 19    | ahci       | 6DA5C04DE8 |
| 8086:282a | 1025:1357 | Intel      | 82801 Mobile SATA Control... | 18    | intel_n... | 7ACA41296B |
| 8086:282a | 1028:05e0 | Intel      | 82801 Mobile SATA Control... | 18    | ahci       | C17B0805A4 |
| 8086:282a | 1028:062d | Intel      | 82801 Mobile SATA Control... | 18    | ahci       | 8F57FEF409 |
| 8086:9a0b | 1028:0991 | Intel      | Volume Management Device ... | 18    | vmd        | F94CED9A41 |
| 8086:282a | 1025:1345 | Intel      | 82801 Mobile SATA Control... | 17    | intel_n... | AA70EAAAEC |
| 8086:282a | 1028:05cc | Intel      | 82801 Mobile SATA Control... | 17    | ahci       | 2293B2D4C4 |
| 8086:282a | 1043:1501 | Intel      | 82801 Mobile SATA Control... | 17    | ahci       | 4AA6169D3C |
| 8086:282a | 1028:0572 | Intel      | 82801 Mobile SATA Control... | 16    | ahci       | 518DC99F15 |
| 8086:282a | 1028:062b | Intel      | 82801 Mobile SATA Control... | 16    | ahci       | 5CE2BAD1C1 |
| 8086:282a | 1028:07a0 | Intel      | 82801 Mobile SATA Control... | 16    | ahci       | 6B9E1797C6 |
| 8086:282a | 1028:0825 | Intel      | 82801 Mobile SATA Control... | 16    | ahci       | AC76D208AB |
| 8086:282a | 103c:85ef | Intel      | 82801 Mobile SATA Control... | 16    | ahci       | F71D6DD289 |
| 8086:282a | 1028:053d | Intel      | 82801 Mobile SATA Control... | 15    | ahci       | DED5232894 |
| 8086:282a | 1028:057e | Intel      | 82801 Mobile SATA Control... | 15    | ahci       | C88A617A2D |
| 8086:282a | 1028:062c | Intel      | 82801 Mobile SATA Control... | 15    | ahci       | 765E6B13E0 |
| 8086:282a | 1028:06db | Intel      | 82801 Mobile SATA Control... | 15    | ahci       | B0E028DBE3 |
| 8086:282a | 1028:0816 | Intel      | 82801 Mobile SATA Control... | 14    | ahci       | 266B7DD4F0 |
| 8086:282a | 103c:18a5 | Intel      | 82801 Mobile SATA Control... | 14    | ahci       | 1F794C0FC3 |
| 8086:282a | 1043:1591 | Intel      | 82801 Mobile SATA Control... | 14    | ahci       | 8BC72609A6 |
| 8086:282a | 1028:04a9 | Intel      | 82801 Mobile SATA Control... | 13    | ahci       | 41E38AE50A |
| 8086:282a | 1028:06df | Intel      | 82801 Mobile SATA Control... | 13    | ahci       | BD6382243C |
| 8086:282a | 103c:18fd | Intel      | 82801 Mobile SATA Control... | 13    | ahci       | 6778794F42 |
| 8086:282a | 17aa:3802 | Intel      | 82801 Mobile SATA Control... | 13    | ahci       | 8856C82ED6 |
| 8086:282a | 1025:1343 | Intel      | 82801 Mobile SATA Control... | 12    | intel_n... | 0AFA1E0FDF |
| 8086:282a | 1025:1355 | Intel      | 82801 Mobile SATA Control... | 12    | ahci       | 4A57537B9C |
| 8086:282a | 1028:04a4 | Intel      | 82801 Mobile SATA Control... | 12    | ahci       | 117E981EF3 |
| 8086:282a | 1028:053e | Intel      | 82801 Mobile SATA Control... | 12    | ahci       | 2711A6B6A7 |
| 8086:282a | 103c:84da | Intel      | 82801 Mobile SATA Control... | 11    | ahci       | C04AE03FB3 |
| 8086:282a | 103c:85e3 | Intel      | 82801 Mobile SATA Control... | 11    | ahci       | 4F8155D538 |
| 8086:282a | 1028:040c | Intel      | 82801 Mobile SATA Control... | 10    | ahci       | 784B8E3DB4 |
| 8086:282a | 1028:05aa | Intel      | 82801 Mobile SATA Control... | 10    | ahci       | 024ABE4666 |
| 8086:282a | 1043:1a81 | Intel      | 82801 Mobile SATA Control... | 10    | ahci       | CC811E1FAF |
| 8086:282a | 104d:907b | Intel      | 82801 Mobile SATA Control... | 10    | ahci       | D0AC721883 |
| 8086:2822 | 1028:06de | Intel      | SATA Controller [RAID mode]  | 9     | ahci       | A725E7458E |
| 8086:282a | 1028:0490 | Intel      | 82801 Mobile SATA Control... | 9     | ahci       | 2CCB22546D |
| 8086:282a | 103c:18fa | Intel      | 82801 Mobile SATA Control... | 9     | ahci       | 069EA1CB31 |
| 8086:282a | 103c:85fc | Intel      | 82801 Mobile SATA Control... | 9     | ahci       | FD6CB8BD93 |
| 8086:282a | 103c:868e | Intel      | 82801 Mobile SATA Control... | 9     | ahci       | 2F3ACDF081 |
| 8086:282a | 1043:1b90 | Intel      | 82801 Mobile SATA Control... | 9     | ahci       | AB804C36D0 |
| 8086:282a | 104d:905a | Intel      | 82801 Mobile SATA Control... | 9     | ahci       | 537D05799C |
| 8086:2822 | 1028:06d9 | Intel      | SATA Controller [RAID mode]  | 8     | ahci       | CEDAF22C01 |
| 8086:282a | 1025:129a | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | B9EC42B5FF |
| 8086:282a | 1025:1422 | Intel      | 82801 Mobile SATA Control... | 8     | intel_n... | 883283C763 |
| 8086:282a | 1028:0277 | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | E280D6C346 |
| 8086:282a | 1028:02ef | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | E56C7EF208 |
| 8086:282a | 1028:079f | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | 7F4EF4BF0E |
| 8086:282a | 1028:07a8 | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | 9FD0E8F6B5 |
| 8086:282a | 1028:07be | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | 6DD46EBB68 |
| 8086:282a | 1028:082c | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | 4684D49D1F |
| 8086:282a | 103c:1894 | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | 05AEA251CE |
| 8086:282a | 103c:849a | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | 0B1F015609 |
| 8086:282a | 103c:84ca | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | A3F263E12B |
| 8086:282a | 103c:84db | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | E5142AC582 |
| 8086:282a | 103c:85f1 | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | 1689AAB845 |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:16be | 1025:0647 | Broadcom   | BCM57765/57785 MS Card Re... | 377   |            | B732F94275 |
| 14e4:16bf | 1025:0647 | Broadcom   | BCM57765/57785 xD-Picture... | 377   |            | B732F94275 |
| 1180:e822 | 17aa:2133 | Ricoh      | MMC/SD Host Controller       | 236   | sdhci_pci  | 5DC4A1E557 |
| 8086:1513 | 2222:1111 | Intel      | CV82524 Thunderbolt Contr... | 230   | thunder... | A53D0DE98A |
| 197b:2382 | 1043:1a07 | JMicron... | SD/MMC Host Controller       | 219   | sdhci_pci  | 11F1CDC49A |
| 14e4:16be | 1025:0504 | Broadcom   | BCM57765/57785 MS Card Re... | 196   |            | 85BCF858C5 |
| 14e4:16bf | 1025:0504 | Broadcom   | BCM57765/57785 xD-Picture... | 196   |            | 85BCF858C5 |
| 197b:2383 | 1043:1a07 | JMicron... | MS Host Controller           | 189   | jmb38x_ms  | 11F1CDC49A |
| 197b:2384 | 1043:1a07 | JMicron... | xD Host Controller           | 187   |            | 11F1CDC49A |
| 1180:0592 | 17aa:20ca | Ricoh      | R5C592 Memory Stick Bus H... | 166   | r592       | DB936567F0 |
| 1180:0852 | 17aa:20cb | Ricoh      | xD-Picture Card Controller   | 166   | r852       | DB936567F0 |
| 1180:e230 | 17aa:2134 | Ricoh      | R5U2xx (R5U230 / R5U231 /... | 161   |            | 4FF6DAE64C |
| 8086:15bf | 2222:1111 | Intel      | JHL6240 Thunderbolt 3 NHI... | 148   | thunder... | FC12F446BB |
| 8086:d150 |           | Intel      | Core Processor QPI Link      | 139   |            | 41032E0F42 |
| 8086:d151 |           | Intel      | Core Processor QPI Routin... | 139   |            | 41032E0F42 |
| 8086:3190 | 1043:1de0 | Intel      | Celeron/Pentium Silver Pr... | 137   |            | 170B220F5B |
| 1180:e230 | 104d:9071 | Ricoh      | R5U2xx (R5U230 / R5U231 /... | 123   |            | 03E0270FDD |
| 8086:1911 | 1025:1331 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 119   |            | 38688703F4 |
| 8086:8a17 |           | Intel      | Ice Lake Thunderbolt 3 NH... | 114   | thunder... | FBBAF8088B |
| 8086:1911 | 1028:0905 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 113   |            | 9CDE952049 |
| 8086:15d9 | 1028:0905 | Intel      | JHL6340 Thunderbolt 3 NHI... | 111   | thunder... | 9CDE952049 |
| 8086:d155 |           | Intel      | Core Processor System Man... | 111   |            | 41032E0F42 |
| 8086:d156 |           | Intel      | Core Processor Semaphore ... | 111   |            | 41032E0F42 |
| 8086:d157 |           | Intel      | Core Processor System Con... | 111   |            | 41032E0F42 |
| 8086:d158 |           | Intel      | Core Processor Miscellane... | 111   |            | 41032E0F42 |
| 1180:e823 | 17aa:21f3 | Ricoh      | PCIe SDXC/MMC Host Contro... | 110   | sdhci_pci  | C9503690D6 |
| 8086:1911 | 17aa:5079 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 107   |            | 0BC4073D23 |
| 197b:2392 | 103c:161c | JMicron... | SD/MMC Host Controller       | 100   | sdhci_pci  | 701E56A49F |
| 8086:1911 | 1028:087c | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 98    |            | 31A6F21CCD |
| 1180:e823 | 17aa:21ce | Ricoh      | PCIe SDXC/MMC Host Contro... | 97    | sdhci_pci  | 74547808D3 |
| 8086:1911 | 17aa:2279 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 96    |            | 2444839350 |
| 8086:15e8 | 103c:8549 | Intel      | JHL7540 Thunderbolt 3 NHI... | 92    | thunder... | 9A264DBCB2 |
| 8086:1911 | 17aa:2292 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 92    |            | FBF4582983 |
| 197b:2392 | 103c:179b | JMicron... | SD/MMC Host Controller       | 91    | sdhci_pci  | 7D39BC1331 |
| 1180:e822 | 17aa:21f3 | Ricoh      | MMC/SD Host Controller       | 90    | sdhci_pci  | 07B30926E1 |
| 8086:15bf | 17aa:2279 | Intel      | JHL6240 Thunderbolt 3 NHI... | 89    | thunder... | 2444839350 |
| 8086:1911 | 17aa:225d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 88    |            | BBA3BC97B7 |
| 1180:e823 | 17aa:21da | Ricoh      | PCIe SDXC/MMC Host Contro... | 86    | sdhci_pci  | B948FE4DD5 |
| 1180:e823 | 17aa:21fa | Ricoh      | PCIe SDXC/MMC Host Contro... | 86    | sdhci_pci  | 50D562CAB5 |
| 197b:2392 | 103c:17f6 | JMicron... | SD/MMC Host Controller       | 85    | sdhci_pci  | D0705EF193 |
| 197b:2393 | 103c:17f6 | JMicron... | MS Host Controller           | 85    | jmb38x_ms  | D0705EF193 |
| 8086:15d2 | 17aa:2292 | Intel      | JHL6540 Thunderbolt 3 NHI... | 85    | thunder... | FBF4582983 |
| 8086:1911 | 1028:08af | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 82    |            | 80857F497B |
| 1180:e823 | 17aa:21f6 | Ricoh      | PCIe SDXC/MMC Host Contro... | 79    | sdhci_pci  | 9ECBB7A946 |
| 8086:1911 | 17aa:5068 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 79    |            | 893F642CBB |
| 8086:15d2 | 1028:08af | Intel      | JHL6540 Thunderbolt 3 NHI... | 77    | thunder... | 80857F497B |
| 8086:15d2 | 1028:0962 | Intel      | JHL6540 Thunderbolt 3 NHI... | 77    | thunder... | 9E26259821 |
| 8086:1911 | 1028:0962 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 77    |            | 9E26259821 |
| 8086:1911 | 1025:1264 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 74    |            | 9971E42809 |
| 8086:1911 | 17aa:225c | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 73    |            | C33E7CED42 |
| 1180:0592 | 1028:022f | Ricoh      | R5C592 Memory Stick Bus H... | 72    | r592       | 06130B24C5 |
| 1180:0852 | 1028:022f | Ricoh      | xD-Picture Card Controller   | 72    | r852       | 06130B24C5 |
| 8086:1911 | 103c:832a | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 71    |            | A7BDFE8774 |
| 8086:1911 | 8086:2015 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 71    |            | 36AA4B2B34 |
| 8086:1911 | 17aa:5072 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 67    |            | 62C94909C7 |
| 197b:2392 | 103c:167c | JMicron... | SD/MMC Host Controller       | 65    | sdhci_pci  | DEDDBF979A |
| 197b:2393 | 103c:167c | JMicron... | MS Host Controller           | 65    | jmb38x_ms  | DEDDBF979A |
| 1180:e822 | 17aa:21fa | Ricoh      | MMC/SD Host Controller       | 64    | sdhci_pci  | 049671564E |
| 8086:156c |           | Intel      | DSL5520 Thunderbolt 2 NHI... | 64    | thunder... | 550A3398EE |
| 1180:0592 | 103c:30cc | Ricoh      | R5C592 Memory Stick Bus H... | 62    | r592       | 4E93C68985 |
| 1180:0852 | 103c:30cc | Ricoh      | xD-Picture Card Controller   | 62    | r852       | 4E93C68985 |
| 8086:156c | 2222:1111 | Intel      | DSL5520 Thunderbolt 2 NHI... | 61    | thunder... | 1007726831 |
| 8086:1911 | 103c:84a6 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 61    |            | 197CBC5A5D |
| 8086:1911 | 17aa:3861 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 61    |            | 2ED0E50384 |
| 1180:e823 | 17aa:21cf | Ricoh      | PCIe SDXC/MMC Host Contro... | 60    | sdhci_pci  | 915D41F361 |
| 8086:1911 | 17aa:3866 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 60    |            | AB6647F9DA |
| 8086:1911 | 17aa:2233 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 59    |            | 79D4310531 |
| 1180:e823 | 1179:0001 | Ricoh      | PCIe SDXC/MMC Host Contro... | 58    | sdhci_pci  | 81FFC7BA9E |
| 8086:1911 | 17aa:2258 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 57    |            | 00AA4C11F4 |
| 8086:15eb | 1028:097d | Intel      | JHL7540 Thunderbolt 3 NHI... | 54    | thunder... | 8C072EA1C4 |
| 8086:1911 | 1028:097d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 54    |            | 8C072EA1C4 |
| 8086:1911 | 1028:0949 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 53    |            | 480FEF69F1 |
| 8086:1911 | 17aa:384e | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 53    |            | 0FE8BCBB7A |
| 8086:1911 | 17aa:3864 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 53    |            | C332C85DCF |
| 8086:1911 | 1028:08ca | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 52    |            | 0D671ACB94 |
| 8086:15eb | 17aa:229f | Intel      | JHL7540 Thunderbolt 3 NHI... | 51    | thunder... | 5002E43F11 |
| 1180:e822 | 17aa:21f6 | Ricoh      | MMC/SD Host Controller       | 50    | sdhci_pci  | A0ED307832 |
| 8086:1911 | 1028:086f | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 50    |            | 36324023DD |
| 8086:15d9 | 8086:0000 | Intel      | JHL6340 Thunderbolt 3 NHI... | 49    | thunder... | B3FFC8D1CB |
| 8086:1911 | 103c:8478 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 47    |            | D3A001E377 |
| 8086:1911 | 103c:832b | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 46    |            | E17FF8A9E4 |
| 1180:0592 | 1025:011e | Ricoh      | R5C592 Memory Stick Bus H... | 45    | r592       | 3C8537DFE3 |
| 8086:1911 | 8086:7270 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 45    |            | 94D2095D5F |
| 1180:0852 | 1025:011e | Ricoh      | xD-Picture Card Controller   | 44    | r852       | 3C8537DFE3 |
| 8086:156a |           | Intel      | DSL5320 Thunderbolt 2 NHI... | 44    | thunder... | C0ED6370C5 |
| 8086:15d2 | 2222:1111 | Intel      | JHL6540 Thunderbolt 3 NHI... | 44    | thunder... | 614037AEE0 |
| 8086:1911 | 1028:087d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 44    |            | A5C63380D6 |
| 8086:1911 | 17aa:2267 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 44    |            | 8FA5616036 |
| 197b:2382 | 103c:3628 | JMicron... | SD/MMC Host Controller       | 43    | sdhci_pci  | DCE60F14E1 |
| 197b:2383 | 103c:3628 | JMicron... | MS Host Controller           | 43    | jmb38x_ms  | DCE60F14E1 |
| 197b:2384 | 103c:3628 | JMicron... | xD Host Controller           | 43    |            | DCE60F14E1 |
| 197b:2392 | 103c:162b | JMicron... | SD/MMC Host Controller       | 43    | sdhci_pci  | E96260CFB9 |
| 197b:2382 | 1297:2027 | JMicron... | SD/MMC Host Controller       | 42    | sdhci_pci  | 5C17F36C61 |
| 197b:2382 | 17aa:212e | JMicron... | SD/MMC Host Controller       | 42    | sdhci_pci  | A687D09DE6 |
| 197b:2383 | 1297:2027 | JMicron... | MS Host Controller           | 42    | jmb38x_ms  | 5C17F36C61 |
| 197b:2383 | 17aa:212f | JMicron... | MS Host Controller           | 42    | jmb38x_ms  | A687D09DE6 |
| 197b:2384 | 17aa:2130 | JMicron... | xD Host Controller           | 42    |            | A687D09DE6 |
| 8086:1911 | 1025:1333 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 42    |            | CE68155512 |
| 8086:1911 | 17aa:229f | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 42    |            | 5002E43F11 |
| 8086:1911 | 8086:1911 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 42    |            | 02F641EA60 |

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
| 8086:31a2 | 17aa:3806 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_i... | EDA2FBC232 |
| 1217:6120 | 0001:0000 | O2 Micro   |                              | 1     |            | B851103D78 |
| 8086:31a2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_i... | 8FBDEDC1B9 |
| 8086:5aa2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     |            | 622CED4019 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d2f | 1043:201f | Intel      | Sunrise Point-LP USB 3.0 ... | 776   | xhci_hcd   | AF70469300 |
| 8086:1e26 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 515   | ehci_hc... | 5872E567EC |
| 8086:1e2d | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 515   | ehci_hc... | 5872E567EC |
| 8086:1e31 | 17aa:3977 | Intel      | 7 Series/C210 Series Chip... | 505   | xhci_hcd   | 5872E567EC |
| 8086:22b5 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 381   | xhci_hcd   | 1B5E908CFF |
| 8086:2934 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 301   | uhci_hcd   | DB936567F0 |
| 8086:2935 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 301   | uhci_hcd   | DB936567F0 |
| 8086:2936 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 301   | uhci_hcd   | DB936567F0 |
| 8086:2937 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 301   | uhci_hcd   | DB936567F0 |
| 8086:2938 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 301   | uhci_hcd   | DB936567F0 |
| 8086:2939 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 301   | uhci_hcd   | DB936567F0 |
| 8086:293a | 17aa:20f1 | Intel      | 82801I (ICH9 Family) USB2... | 301   | ehci_pci   | DB936567F0 |
| 8086:293c | 17aa:20f1 | Intel      | 82801I (ICH9 Family) USB2... | 301   | ehci_pci   | DB936567F0 |
| 8086:1c26 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 299   | ehci_hc... | 21DB34139A |
| 8086:1c2d | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 299   | ehci_hc... | 21DB34139A |
| 1b21:1042 | 1043:1059 | ASMedia... | ASM1042 SuperSpeed USB Ho... | 293   | xhci_pci   | 389E1A52A6 |
| 8086:3b34 | 17aa:2163 | Intel      | 5 Series/3400 Series Chip... | 284   | ehci_pci   | 5DC4A1E557 |
| 8086:3b3c | 17aa:2163 | Intel      | 5 Series/3400 Series Chip... | 284   | ehci_pci   | 5DC4A1E557 |
| 8086:9c31 | 17aa:3978 | Intel      | 8 Series USB xHCI HC         | 277   | xhci_hcd   | B1B8196F26 |
| 8086:27c8 | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 270   | uhci_hcd   | 2117F02A4F |
| 8086:27c9 | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 270   | uhci_hcd   | 2117F02A4F |
| 8086:27ca | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 270   | uhci_hcd   | 2117F02A4F |
| 8086:27cc | 1043:83ad | Intel      | NM10/ICH7 Family USB2 EHC... | 270   | ehci_hc... | 2117F02A4F |
| 8086:9c26 | 17aa:3978 | Intel      | 8 Series USB EHCI #1         | 257   | ehci_pci   | B1B8196F26 |
| 8086:27cb | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 249   | uhci_hcd   | 2117F02A4F |
| 8086:9ded | 1043:201f | Intel      | Cannon Point-LP USB 3.1 x... | 245   | xhci_hcd   | 6AFF8771B1 |
| 8086:9c31 | 1043:201f | Intel      | 8 Series USB xHCI HC         | 240   | xhci_hcd   | 13FF923546 |
| 8086:a12f | 1043:201f | Intel      | 100 Series/C230 Series Ch... | 235   | xhci_hcd   | 5C45DFB686 |
| 1022:15e0 | 1043:201f | AMD        | Raven USB 3.1                | 233   | xhci_hcd   | F504E72617 |
| 1022:15e1 | 1043:201f | AMD        | Raven USB 3.1                | 233   | xhci_hcd   | F504E72617 |
| 8086:31a8 | 1043:201f | Intel      | Celeron/Pentium Silver Pr... | 220   | xhci_hcd   | BBD93F8E6D |
| 8086:8c26 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 205   | ehci_pci   | 76D72EB45F |
| 8086:8c2d | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 205   | ehci_pci   | 76D72EB45F |
| 8086:8c31 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 205   | xhci_hcd   | 76D72EB45F |
| 8086:9cb1 | 1043:201f | Intel      | Wildcat Point-LP USB xHCI... | 199   | xhci_hcd   | DCD714D5FA |
| 8086:a36d | 1043:201f | Intel      | Cannon Lake PCH USB 3.1 x... | 194   | xhci_hcd   | 00041CC413 |
| 8086:9c26 | 1043:201f | Intel      | 8 Series USB EHCI #1         | 183   | ehci_pci   | 13FF923546 |
| 8086:1e26 | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 171   | ehci_pci   | C9503690D6 |
| 8086:1e2d | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 171   | ehci_pci   | C9503690D6 |
| 8086:1e31 | 17aa:21f3 | Intel      | 7 Series/C210 Series Chip... | 170   | xhci_hcd   | C9503690D6 |
| 8086:3b34 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 170   | ehci_pci   | 11F1CDC49A |
| 8086:3b3c | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 170   | ehci_pci   | 11F1CDC49A |
| 8086:5aa8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 168   | xhci_hcd   | 71A92492E3 |
| 8086:1c26 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 166   | ehci_pci   | A53D0DE98A |
| 8086:1c2d | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 166   | ehci_pci   | A53D0DE98A |
| 8086:1e26 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 166   | ehci_pci   | EC1ABD9485 |
| 8086:1e2d | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 166   | ehci_pci   | EC1ABD9485 |
| 8086:15c1 | 2222:1111 | Intel      | JHL6240 Thunderbolt 3 USB... | 164   | xhci_hcd   | 35941050E8 |
| 8086:1e31 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 157   | xhci_hcd   | EC1ABD9485 |
| 8086:1c27 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 153   | uhci_hcd   | A53D0DE98A |
| 8086:1c2c | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 153   | uhci_hcd   | A53D0DE98A |
| 8086:1e26 | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 153   | ehci_hc... | 52667487D2 |
| 8086:1e2d | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 153   | ehci_hc... | 52667487D2 |
| 8086:2934 | 17aa:3a14 | Intel      | 82801I (ICH9 Family) USB ... | 151   | uhci_hcd   | 1BBEC614AA |
| 8086:2935 | 17aa:3a15 | Intel      | 82801I (ICH9 Family) USB ... | 151   | uhci_hcd   | 1BBEC614AA |
| 8086:2936 | 17aa:3a16 | Intel      | 82801I (ICH9 Family) USB ... | 151   | uhci_hcd   | 1BBEC614AA |
| 8086:293a | 17aa:3a17 | Intel      | 82801I (ICH9 Family) USB2... | 151   | ehci_hc... | 1BBEC614AA |
| 8086:293c | 17aa:3a0c | Intel      | 82801I (ICH9 Family) USB2... | 151   | ehci_hc... | 1BBEC614AA |
| 8086:1c26 | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 150   | ehci_hc... | 438D785F0E |
| 8086:1c2d | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 150   | ehci_hc... | 438D785F0E |
| 8086:1c26 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 149   | ehci_pci   | 74547808D3 |
| 8086:1c2d | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 149   | ehci_pci   | 74547808D3 |
| 8086:2937 | 17aa:3a09 | Intel      | 82801I (ICH9 Family) USB ... | 146   | uhci_hcd   | 1BBEC614AA |
| 8086:1c26 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 145   | ehci_pci   | B420F25ED4 |
| 8086:1c2d | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 145   | ehci_pci   | B420F25ED4 |
| 8086:2938 | 17aa:3a0a | Intel      | 82801I (ICH9 Family) USB ... | 142   | uhci_hcd   | 1BBEC614AA |
| 8086:3b34 | 17aa:38b8 | Intel      | 5 Series/3400 Series Chip... | 142   | ehci_hc... | 62053AE42B |
| 8086:3b3c | 17aa:38aa | Intel      | 5 Series/3400 Series Chip... | 142   | ehci_hc... | 62053AE42B |
| 8086:2939 | 17aa:3a0b | Intel      | 82801I (ICH9 Family) USB ... | 140   | uhci_hcd   | 1BBEC614AA |
| 10de:0aa5 | 10de:cb79 | Nvidia     | MCP79 OHCI USB 1.1 Contro... | 138   | ohci_pci   | F982A2F6CC |
| 10de:0aa6 | 10de:cb79 | Nvidia     | MCP79 EHCI USB 2.0 Contro... | 138   | ehci_pci   | F982A2F6CC |
| 10de:0aa7 | 10de:cb79 | Nvidia     | MCP79 OHCI USB 1.1 Contro... | 138   | ohci_pci   | F982A2F6CC |
| 10de:0aa9 | 10de:cb79 | Nvidia     | MCP79 EHCI USB 2.0 Contro... | 138   | ehci_pci   | F982A2F6CC |
| 8086:1c26 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 138   | ehci_pci   | 33617DD1A8 |
| 8086:1c2d | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 138   | ehci_pci   | 33617DD1A8 |
| 8086:1e26 | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 136   | ehci_pci   | 50D562CAB5 |
| 8086:1e2d | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 136   | ehci_pci   | 50D562CAB5 |
| 8086:1e31 | 17aa:21fa | Intel      | 7 Series/C210 Series Chip... | 136   | xhci_hcd   | 50D562CAB5 |
| 8086:3b34 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 134   | ehci_pci   | 576A6491F3 |
| 8086:3b3c | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 134   | ehci_pci   | 576A6491F3 |
| 8086:2830 | 17aa:20aa | Intel      | 82801H (ICH8 Family) USB ... | 129   | uhci_hcd   | E1B3B6E090 |
| 8086:2831 | 17aa:20aa | Intel      | 82801H (ICH8 Family) USB ... | 129   | uhci_hcd   | E1B3B6E090 |
| 8086:2834 | 17aa:20aa | Intel      | 82801H (ICH8 Family) USB ... | 129   | uhci_hcd   | E1B3B6E090 |
| 8086:2835 | 17aa:20aa | Intel      | 82801H (ICH8 Family) USB ... | 129   | uhci_hcd   | E1B3B6E090 |
| 8086:2836 | 17aa:20ab | Intel      | 82801H (ICH8 Family) USB2... | 129   | ehci_pci   | E1B3B6E090 |
| 8086:283a | 17aa:20ab | Intel      | 82801H (ICH8 Family) USB2... | 129   | ehci_pci   | E1B3B6E090 |
| 1022:7808 | 17aa:3801 | AMD        | FCH USB EHCI Controller      | 128   | ehci_pci   | 779BFC3B47 |
| 1022:7814 | 17aa:3801 | AMD        | FCH USB XHCI Controller      | 128   | xhci_pci   | 779BFC3B47 |
| 8086:1e26 | 1043:124d | Intel      | 7 Series/C216 Chipset Fam... | 127   | ehci_hc... | 08930695BC |
| 8086:1e2d | 1043:124d | Intel      | 7 Series/C216 Chipset Fam... | 127   | ehci_hc... | 08930695BC |
| 8086:1e31 | 1043:124d | Intel      | 7 Series/C210 Series Chip... | 126   | xhci_hcd   | 08930695BC |
| 8086:3b34 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 126   | ehci_pci   | C172C655DE |
| 8086:3b3c | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 126   | ehci_pci   | C172C655DE |
| 1022:1639 | 1043:201f | AMD        | Renoir USB 3.1               | 124   | xhci_pci   | DB4A212405 |
| 8086:3b34 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 123   | ehci_hc... | 03E0270FDD |
| 8086:3b3c | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 123   | ehci_hc... | 03E0270FDD |
| 8086:9a1b | 2222:1111 | Intel      | Tiger Lake-LP Thunderbolt... | 123   | thunder... | 11F1E42FBE |
| 8086:9d2f | 17aa:3870 | Intel      | Sunrise Point-LP USB 3.0 ... | 123   | xhci_hcd   | 19226582D9 |
| 8086:2830 | 1025:011f | Intel      | 82801H (ICH8 Family) USB ... | 122   | uhci_hcd   | 6A05B72968 |
| 8086:2831 | 1025:011f | Intel      | 82801H (ICH8 Family) USB ... | 122   | uhci_hcd   | 6A05B72968 |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:6900 | 03ea:1af4 | AMD        | Topaz XT [Radeon R7 M260/... | 6     | amdgpu     | B48E22AF4A |
| 1971:0000 | 105b:0003 | AGEIA T... | AGEIA PhysX 100 PCIe Card    | 3     |            | 5C4A880D42 |
| 106b:003b |           | Apple      | UniNorth/Intrepid ATA/100    | 2     | pata_pc... | 7740C04B4B |
| 106b:003e |           | Apple      | KeyLargo/Intrepid Mac I/O    | 2     | macio      | 7740C04B4B |
| 10de:0e1b | 0043:0000 | Nvidia     | GK107 HDMI Audio Controller  | 2     | snd_hda... | 17B6106770 |
| 10de:1f91 | 103c:8601 | Nvidia     | TU117M [GeForce GTX 1650 ... | 2     | nouveau    | 332EEAE951 |
| 1002:694e | 1002:694e | AMD        | Polaris 22 XL [Radeon RX ... | 1     | amdgpu     | F5FDC69851 |
| 106b:0022 |           | Apple      | KeyLargo Mac I/O             | 1     | macio      | 48A9C9544A |
| 10de:0bea | 1028:1534 | Nvidia     | GF108 High Definition Aud... | 1     | snd_hda... | 9401066945 |
| 10de:0bea | 1043:105c | Nvidia     | GF108 High Definition Aud... | 1     | snd_hda... | 2512ED1F69 |
| 10de:0e1b | 17aa:221e | Nvidia     | GK107 HDMI Audio Controller  | 1     | snd_hda... | 4C925D546F |
| 10de:1c8c | 17aa:39d1 | Nvidia     | GP107M [GeForce GTX 1050 ... | 1     | nouveau    | 2DA8281FA9 |
| 10de:1fb9 | 10de:0000 | Nvidia     | TU117GLM [Quadro T1000 Mo... | 1     | nvidia     | B53EA50909 |
| 1180:8592 | 1043:9627 | Ricoh      |                              | 1     |            | C215EA9980 |
| 1180:8822 | 1043:9627 | Ricoh      |                              | 1     |            | C215EA9980 |
| 17fe:a220 | 1468:0305 | InProComm  |                              | 1     |            | 80E120B3A5 |
| 17fe:a220 | 1468:8305 | InProComm  |                              | 1     |            | 80E120B3A5 |
| 197b:2381 | 197b:2381 | JMicron... | Standard SD Host Controller  | 1     |            | 720AE73C63 |
| 197b:2382 | 197b:2382 | JMicron... | SD/MMC Host Controller       | 1     | sdhci-pci  | 720AE73C63 |
| 197b:2383 | 197b:2383 | JMicron... | MS Host Controller           | 1     | jmb38x_ms  | 720AE73C63 |
| 1aea:6625 | 103c:83a8 | Alcor M... | AU6625 PCI-E Flash card r... | 1     |            | 9ECD580CF7 |
| 1aea:6625 | 103c:83aa | Alcor M... | AU6625 PCI-E Flash card r... | 1     |            | 62C7769C30 |
| 494f:0100 | 494f:0100 | ACCES I... |                              | 1     |            | B364724E53 |
| 8086:9d2f | 14c0:0062 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 87AC0729E6 |

