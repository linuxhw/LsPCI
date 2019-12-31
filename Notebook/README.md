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
   * [ Multimedia ](#multimedia-pci)
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
   * [ Wireless controller ](#wireless-controller-pci)
   * [ Others ](#others-pci)

PCI Devices
-----------

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bluetooth (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1814:3298 | 103c:18ec | Ralink     | RT3290 Bluetooth             | 223   | rtbth      | 96C288C457 |
| 1814:3298 | 105b:e056 | Ralink     | RT3290 Bluetooth             | 59    | rtbth      | 12F5A59D53 |
| 1814:3298 | 1a3b:2f87 | Ralink     | RT3290 Bluetooth             | 9     |            | F65DC130D7 |
| 1814:3298 | 1a3b:2787 | Ralink     | RT3290 Bluetooth             | 6     |            | 0E1770A053 |
| 1814:3298 | 103c:191c | Ralink     | RT3290 Bluetooth             | 3     |            | B6260EAFCE |
| 1814:3298 | 1814:3298 | Ralink     | RT3290 Bluetooth             | 2     |            | EF1E6295A8 |
| 1814:3298 | 10cf:1772 | Ralink     | RT3290 Bluetooth             | 1     |            | 1135E21142 |
| 1814:3298 | 1a3b:210b | Ralink     | RT3290 Bluetooth             | 1     |            | 2333E930AF |
| 1814:3298 | 1a3b:2987 | Ralink     | RT3290 Bluetooth             | 1     |            | EC90AB9922 |

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:4384 |           | AMD        | SBx00 PCI to PCI Bridge      | 994   | shpchp     | 34DC7B3038 |
| 1022:1700 |           | AMD        | Family 12h/14h Processor ... | 691   |            | FC53E6761D |
| 1022:1701 |           | AMD        | Family 12h/14h Processor ... | 691   |            | FC53E6761D |
| 1022:1702 |           | AMD        | Family 12h/14h Processor ... | 691   |            | FC53E6761D |
| 1022:1703 |           | AMD        | Family 12h/14h Processor ... | 691   | k10temp    | FC53E6761D |
| 1022:1704 |           | AMD        | Family 12h/14h Processor ... | 691   |            | FC53E6761D |
| 1022:1716 |           | AMD        | Family 12h/14h Processor ... | 691   |            | FC53E6761D |
| 1022:1718 |           | AMD        | Family 12h/14h Processor ... | 691   |            | FC53E6761D |
| 1022:1719 |           | AMD        | Family 12h/14h Processor ... | 691   |            | FC53E6761D |
| 1022:780f |           | AMD        | FCH PCI Bridge               | 686   | shpchp     | 18F9503086 |
| 8086:2c62 | 8086:8086 | Intel      | Core Processor QuickPath ... | 633   |            | 82CB2D5E90 |
| 8086:2d01 | 8086:8086 | Intel      | Core Processor QuickPath ... | 633   |            | 82CB2D5E90 |
| 8086:2d10 | 8086:8086 | Intel      | Core Processor QPI Link 0    | 633   |            | 82CB2D5E90 |
| 8086:2d11 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 633   |            | 82CB2D5E90 |
| 8086:2d12 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 633   |            | 82CB2D5E90 |
| 8086:2d13 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 633   |            | 82CB2D5E90 |
| 8086:2448 |           | Intel      | 82801 Mobile PCI Bridge      | 417   | shpchp     | BA9EFF4F3B |
| 1022:1200 |           | AMD        | Family 10h Processor Hype... | 336   |            | 34DC7B3038 |
| 1022:1201 |           | AMD        | Family 10h Processor Addr... | 336   |            | 34DC7B3038 |
| 1022:1202 |           | AMD        | Family 10h Processor DRAM... | 336   |            | 34DC7B3038 |
| 1022:1203 |           | AMD        | Family 10h Processor Misc... | 336   | k10temp    | 34DC7B3038 |
| 1022:1204 |           | AMD        | Family 10h Processor Link... | 336   |            | 34DC7B3038 |
| 1022:157b |           | AMD        | Family 15h (Models 60h-6f... | 323   |            | 6EEF4CAED6 |
| 1022:157d |           | AMD        | Carrizo Audio Dummy Host ... | 323   |            | 6EEF4CAED6 |
| 1002:43a0 | 1002:0000 | AMD        | SB700/SB800/SB900 PCI to ... | 314   | shpchp     | 68B01574FB |
| 1022:43a0 | 1022:0000 | AMD        | Hudson PCI to PCI bridge ... | 308   | shpchp     | 18F9503086 |
| 1022:1400 |           | AMD        | Family 15h (Models 10h-1f... | 304   |            | 18F9503086 |
| 1022:1401 |           | AMD        | Family 15h (Models 10h-1f... | 304   |            | 18F9503086 |
| 1022:1402 |           | AMD        | Family 15h (Models 10h-1f... | 304   |            | 18F9503086 |
| 1022:1403 |           | AMD        | Family 15h (Models 10h-1f... | 304   | k10temp    | 18F9503086 |
| 1022:1404 |           | AMD        | Family 15h (Models 10h-1f... | 304   |            | 18F9503086 |
| 1022:1405 |           | AMD        | Family 15h (Models 10h-1f... | 304   |            | 18F9503086 |
| 1022:1100 |           | AMD        | K8 [Athlon64/Opteron] Hyp... | 293   |            | 005CF3D43E |
| 1022:1101 |           | AMD        | K8 [Athlon64/Opteron] Add... | 293   |            | 005CF3D43E |
| 1022:1102 |           | AMD        | K8 [Athlon64/Opteron] DRA... | 293   |            | 005CF3D43E |
| 1022:1103 |           | AMD        | K8 [Athlon64/Opteron] Mis... | 293   | k8temp     | 005CF3D43E |
| 8086:1e10 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 292   | shpchp     | 8CE0C08E9A |
| 1022:1439 | 1022:1234 | AMD        | Family 16h Processor Func... | 291   | shpchp     | A0C06307BA |
| 1022:156b |           | AMD        | Family 16h (Models 30h-3f... | 287   |            | 4DC7D17844 |
| 1022:1580 |           | AMD        | Family 16h (Models 30h-3f... | 287   |            | 4DC7D17844 |
| 1022:1581 |           | AMD        | Family 16h (Models 30h-3f... | 287   |            | 4DC7D17844 |
| 1022:1582 |           | AMD        | Family 16h (Models 30h-3f... | 287   |            | 4DC7D17844 |
| 1022:1583 |           | AMD        | Family 16h (Models 30h-3f... | 287   | k10temp    | 4DC7D17844 |
| 1022:1584 |           | AMD        | Family 16h (Models 30h-3f... | 287   | fam15h_... | 4DC7D17844 |
| 1022:1585 |           | AMD        | Family 16h (Models 30h-3f... | 287   |            | 4DC7D17844 |
| 8086:1e12 | 17aa:3977 | Intel      | 7 Series/C210 Series Chip... | 286   | shpchp     | 8CE0C08E9A |
| 1022:1510 | 1022:1510 | AMD        | Family 14h Processor Root... | 278   |            | 1A825B75E9 |
| 8086:0154 | 17aa:3977 | Intel      | 3rd Gen Core processor DR... | 238   | ivb_uncore | 8CE0C08E9A |
| 1022:1414 | 1022:1234 | AMD        | Family 15h (Models 10h-1f... | 234   | shpchp     | 18F9503086 |
| 1022:43a1 | 1022:0000 | AMD        | Hudson PCI to PCI bridge ... | 232   | shpchp     | 18F9503086 |
| 1022:15b0 |           | AMD        | Stoney HT Configuration      | 231   |            | 6EEF4CAED6 |
| 1022:15b1 |           | AMD        | Stoney Address Maps          | 231   |            | 6EEF4CAED6 |
| 1022:15b2 |           | AMD        | Stoney DRAM Configuration    | 231   |            | 6EEF4CAED6 |
| 1022:15b3 |           | AMD        | Stoney Miscellaneous Conf... | 231   | k10temp    | 6EEF4CAED6 |
| 1022:15b4 |           | AMD        | Stoney PM Configuration      | 231   | fam15h_... | 6EEF4CAED6 |
| 1022:15b5 |           | AMD        | Stoney NB Performance Mon... | 231   |            | 6EEF4CAED6 |
| 8086:1e59 | 17aa:3977 | Intel      | HM76 Express Chipset LPC ... | 221   | lpc_ich    | 8CE0C08E9A |
| 8086:2448 | 0000:0000 | Intel      | 82801 Mobile PCI Bridge      | 214   |            | 2AEE48E77B |
| 1022:1452 |           | AMD        | Family 17h (Models 00h-1f... | 211   |            | C65ABD0640 |
| 1022:15e8 |           | AMD        | Raven/Raven2 Device 24: F... | 207   |            | C65ABD0640 |
| 1022:15e9 |           | AMD        | Raven/Raven2 Device 24: F... | 207   |            | C65ABD0640 |
| 1022:15ea |           | AMD        | Raven/Raven2 Device 24: F... | 207   |            | C65ABD0640 |
| 1022:15eb |           | AMD        | Raven/Raven2 Device 24: F... | 207   | k10temp    | C65ABD0640 |
| 1022:15ec |           | AMD        | Raven/Raven2 Device 24: F... | 207   |            | C65ABD0640 |
| 1022:15ed |           | AMD        | Raven/Raven2 Device 24: F... | 207   |            | C65ABD0640 |
| 1022:15ee |           | AMD        | Raven/Raven2 Device 24: F... | 207   |            | C65ABD0640 |
| 1022:15ef |           | AMD        | Raven/Raven2 Device 24: F... | 207   |            | C65ABD0640 |
| 1022:1709 | 1022:1234 | AMD        | Family 12h Processor Root... | 205   | shpchp     | 9C722B6763 |
| 1022:1512 | 1022:1234 | AMD        | Family 14h Processor Root... | 190   | shpchp     | AE90CAFD98 |
| 1022:15db | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 188   | pcieport   | C65ABD0640 |
| 8086:0104 | 17aa:3975 | Intel      | 2nd Generation Core Proce... | 187   |            | 89EF922929 |
| 8086:1c10 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 187   | shpchp     | 89EF922929 |
| 8086:1c49 | 17aa:3975 | Intel      | HM65 Express Chipset LPC ... | 187   | lpc_ich    | 89EF922929 |
| 8086:2448 | 1043:83ad | Intel      | 82801 Mobile PCI Bridge      | 187   |            | A6B1293F94 |
| 8086:27bc | 1043:83ad | Intel      | NM10 Family LPC Controller   | 187   | lpc_ich    | A6B1293F94 |
| 8086:27d0 | 1043:83ad | Intel      | NM10/ICH7 Family PCI Expr... | 187   | shpchp     | A6B1293F94 |
| 8086:27d2 | 1043:83ad | Intel      | NM10/ICH7 Family PCI Expr... | 187   | shpchp     | A6B1293F94 |
| 1002:43a1 | 1002:0000 | AMD        | SB700/SB800/SB900 PCI to ... | 184   | shpchp     | AE90CAFD98 |
| 8086:1c12 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 184   | shpchp     | 89EF922929 |
| 1022:15dc | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 172   | pcieport   | C65ABD0640 |
| 1022:1412 | 1022:1234 | AMD        | Family 15h (Models 10h-1f... | 169   | shpchp     | 5F1837A6B4 |
| 8086:2448 | 17aa:383f | Intel      | 82801 Mobile PCI Bridge      | 169   |            | 5986AA0AAC |
| 8086:27d6 | 1043:83ad | Intel      | NM10/ICH7 Family PCI Expr... | 168   | shpchp     | E368A28816 |
| 1022:1530 |           | AMD        | Family 16h Processor Func... | 167   |            | 19ABB6C0FB |
| 1022:1531 |           | AMD        | Family 16h Processor Func... | 167   |            | 19ABB6C0FB |
| 1022:1532 |           | AMD        | Family 16h Processor Func... | 167   |            | 19ABB6C0FB |
| 1022:1533 |           | AMD        | Family 16h Processor Func... | 167   | k10temp    | 19ABB6C0FB |
| 1022:1534 |           | AMD        | Family 16h Processor Func... | 167   | fam15h_... | 19ABB6C0FB |
| 1022:1535 |           | AMD        | Family 16h Processor Func... | 167   |            | 19ABB6C0FB |
| 1022:1538 |           | AMD        | Family 16h Processor Func... | 167   |            | 19ABB6C0FB |
| 1022:1415 | 1022:1234 | AMD        | Family 15h (Models 10h-1f... | 148   | shpchp     | 5F1837A6B4 |
| 1022:15d3 | 1022:1453 | AMD        | Raven/Raven2 PCIe GPP Bri... | 144   | pcieport   | C65ABD0640 |
| 1002:43a2 | 1002:0000 | AMD        | SB900 PCI to PCI bridge (... | 143   | shpchp     | 684866EE94 |
| 1022:1707 | 1022:1234 | AMD        | Family 12h Processor Root... | 137   | shpchp     | 9C722B6763 |
| 8086:2940 |           | Intel      | 82801I (ICH9 Family) PCI ... | 137   | shpchp     | 189F28A68E |
| 1022:170a | 1022:1234 | AMD        | Family 12h Processor Root... | 135   | shpchp     | 9C722B6763 |
| 1002:43a3 | 1002:0000 | AMD        | SB900 PCI to PCI bridge (... | 133   | shpchp     | A54B8C9315 |
| 8086:2280 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 133   | iosf_mb... | AE477CA654 |
| 8086:229c | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 133   | lpc_ich    | AE477CA654 |
| 1022:1300 |           | AMD        | Family 11h Processor Hype... | 132   |            | 5D02B6C874 |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:5287 | 1043:202f | Realtek... | RTL8411B PCI Express Card... | 104   | rtsx_pci   | 11A297038F |
| 10ec:5286 | 10ec:5286 | Realtek... | RTL8402 Integrated 1-LUN ... | 94    | rtsx_pci   | 6D7501C42A |
| 10ec:5286 | 1043:202f | Realtek... | RTL8402 Integrated 1-LUN ... | 83    | rtsx_pci   | 54A0B1BE15 |
| 10ec:5289 | 1043:202f | Realtek... | RTL8411 PCI Express Card ... | 83    | rtsx_pci   | 179397B4EA |
| 10ec:5209 | 1025:0685 | Realtek... | RTS5209 PCI Express Card ... | 47    | rtsx_pci   | ECACED6F64 |
| 10ec:5287 | 1025:0866 | Realtek... | RTL8411B PCI Express Card... | 46    | rtsx_pci   | 3FD761163B |
| 10ec:5289 | 10ec:5289 | Realtek... | RTL8411 PCI Express Card ... | 44    | rtsx_pci   | C8264FD679 |
| 10ec:5229 | 17aa:3808 | Realtek... | RTS5229 PCI Express Card ... | 38    | rtsx_pci   | 7D85F9BFAB |
| 10ec:5209 | 104d:908b | Realtek... | RTS5209 PCI Express Card ... | 37    | rtsx_pci   | A9E0A905BD |
| 10ec:5229 | 1043:202f | Realtek... | RTS5229 PCI Express Card ... | 37    | rtsx_pci   | 6421A501F4 |
| 10ec:5229 | 10ec:5229 | Realtek... | RTS5229 PCI Express Card ... | 37    | rtsx_pci   | B4CE12C939 |
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
| 10ec:5289 | 1043:1457 | Realtek... | RTL8411 PCI Express Card ... | 21    | rtsx_pci   | 7DEA034FEB |
| 10ec:5209 | 1025:0781 | Realtek... | RTS5209 PCI Express Card ... | 20    | rtsx_pci   | 19E141A0F7 |
| 10ec:5227 | 17aa:2214 | Realtek... | RTS5227 PCI Express Card ... | 20    | rtsx_pci   | 43DDF539E2 |
| 10ec:522a | 10ec:522a | Realtek... | RTS522A PCI Express Card ... | 20    | rtsx_pci   | 556DD6ED0B |
| 10ec:5249 | 17aa:3801 | Realtek... | RTS5249 PCI Express Card ... | 20    | rtsx_pci   | 239616AC43 |
| 10ec:5209 | 1025:061f | Realtek... | RTS5209 PCI Express Card ... | 19    | rtsx_pci   | FBE9C7EEE3 |
| 10ec:525a | 1028:08af | Realtek... | RTS525A PCI Express Card ... | 19    | rtsx_pci   | ED8598DB62 |
| 10ec:5227 | 103c:198f | Realtek... | RTS5227 PCI Express Card ... | 18    | rtsx_pci   | 756C79455B |
| 10ec:5229 | 103c:1854 | Realtek... | RTS5229 PCI Express Card ... | 18    | rtsx_pci   | 96C288C457 |
| 10ec:5229 | 1179:f920 | Realtek... | RTS5229 PCI Express Card ... | 18    | rtsx_pci   | A66F77B75E |
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
| 10ec:5227 | 1028:0616 | Realtek... | RTS5227 PCI Express Card ... | 10    | rtsx_pci   | 2F330BEE0B |
| 10ec:5227 | 17aa:5028 | Realtek... | RTS5227 PCI Express Card ... | 10    | rtsx_pci   | AFC9FC3D29 |
| 10ec:5229 | 103c:216c | Realtek... | RTS5229 PCI Express Card ... | 10    | rtsx_pci   | 65D5A2C9E3 |
| 10ec:5229 | 1179:ff1e | Realtek... | RTS5229 PCI Express Card ... | 10    | rtsx_pci   | 4B9E002F83 |
| 10ec:5229 | 17aa:5018 | Realtek... | RTS5229 PCI Express Card ... | 10    | rtsx_pci   | 485C2FB9C0 |
| 10ec:522a | 103c:837d | Realtek... | RTS522A PCI Express Card ... | 10    | rtsx_pci   | 9441C13CE5 |
| 10ec:525a | 1028:081c | Realtek... | RTS525A PCI Express Card ... | 10    | rtsx_pci   | B4899BA50A |
| 10ec:5287 | 1025:0798 | Realtek... | RTL8411B PCI Express Card... | 10    | rtsx_pci   | 7537E7CB35 |
| 10ec:5287 | 1025:1194 | Realtek... | RTL8411B PCI Express Card... | 10    | rtsx_pci   | 702D379DD6 |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0aa3 | 10de:cb79 | Nvidia     | MCP79 Co-processor           | 31    | nvidia     | 441575D073 |
| 10de:0753 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] Co-... | 23    |            | D672B4583E |
| 10de:0543 | 1025:0126 | Nvidia     | MCP67 Co-processor           | 20    |            | 590A68AE68 |
| 10de:0aa3 | 1043:1cf7 | Nvidia     | MCP79 Co-processor           | 18    | nvidia     | F0A1399A3F |
| 10de:0d7a | 10de:cb89 | Nvidia     | MCP89 Co-Processor           | 17    |            | 303C043B8B |
| 10de:0543 | 103c:30cf | Nvidia     | MCP67 Co-processor           | 16    |            | 1031D661DB |
| 10de:0aa3 | 1043:1fa7 | Nvidia     | MCP79 Co-processor           | 14    | nvidia     | F5C8A70507 |
| 10de:0aa3 | 1043:8402 | Nvidia     | MCP79 Co-processor           | 9     | nvidia     | F47A1D4306 |
| 10de:0271 | 103c:30b7 | Nvidia     | MCP51 PMU                    | 8     |            | 71764E2EB9 |
| 10de:0543 | 1043:16a7 | Nvidia     | MCP67 Co-processor           | 6     |            | 451EF7B78E |
| 10de:0aa3 | 103c:3651 | Nvidia     | MCP79 Co-processor           | 5     | nvidia     | 535E45E25D |
| 10de:0aa3 | 1043:1d17 | Nvidia     | MCP79 Co-processor           | 5     | nvidia     | C2F6621CCC |
| 10de:0447 | 103c:30cf | Nvidia     | MCP65 SMU                    | 4     |            | AB1EF36E83 |
| 10de:0aa3 | 1025:0160 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | 69DC96A4D0 |
| 10de:0aa3 | 1462:1012 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | FE43B38080 |
| 10de:0271 | 103c:30e5 | Nvidia     | MCP51 PMU                    | 3     |            | 45FC8F4912 |
| 10de:0271 | 1043:1367 | Nvidia     | MCP51 PMU                    | 3     |            | B934938C50 |
| 10de:0543 | 103c:30ea | Nvidia     | MCP67 Co-processor           | 3     |            | F4E6748E0D |
| 10de:0271 | 103c:30b5 | Nvidia     | MCP51 PMU                    | 2     |            | E964514E68 |
| 10de:0271 | 103c:30bf | Nvidia     | MCP51 PMU                    | 2     |            | 6F28F56C47 |
| 10de:0271 | 1462:373d | Nvidia     | MCP51 PMU                    | 2     |            | 6380916978 |
| 10de:0271 | 1462:3fc1 | Nvidia     | MCP51 PMU                    | 2     |            | 278EF4A255 |
| 10de:0543 | 103c:30d6 | Nvidia     | MCP67 Co-processor           | 2     |            | 3B57385D7E |
| 10de:0753 | 1462:6720 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 8EC812584C |
| 10de:0aa3 | 1043:1a87 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | C2D93613D4 |
| 10de:0aa3 | 1462:1019 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | 2054B3A4CC |
| 10de:0aa3 | 1734:1151 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | 5EB3DC5665 |
| 10de:0aa3 | 17aa:38da | Nvidia     | MCP79 Co-processor           | 2     |            | C38D40E936 |
| 10de:0271 | 1025:0112 | Nvidia     | MCP51 PMU                    | 1     |            | 9823532B00 |
| 10de:0271 | 1043:1322 | Nvidia     | MCP51 PMU                    | 1     |            | 71FE8FB963 |
| 10de:0271 | 1734:10d3 | Nvidia     | MCP51 PMU                    | 1     |            | 6172D9B266 |
| 10de:0271 | 1734:10d4 | Nvidia     | MCP51 PMU                    | 1     |            | 40B94D516E |
| 10de:0543 | 1025:0127 | Nvidia     | MCP67 Co-processor           | 1     |            | DB69CCC0BF |
| 10de:0543 | 1043:1697 | Nvidia     | MCP67 Co-processor           | 1     |            | C3296D5344 |
| 10de:0753 | 1025:014a | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | F63FFEFC64 |
| 10de:0753 | 1025:014d | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | E3584BFDCF |
| 10de:0753 | 1462:6520 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 12132D4EBD |
| 10de:0aa3 | 1028:0271 | Nvidia     | MCP79 Co-processor           | 1     |            | 0238C91A6C |
| 10de:0aa3 | 1043:1fd7 | Nvidia     | MCP79 Co-processor           | 1     |            | 717DC8F28E |
| 10de:0aa3 | 1071:9070 | Nvidia     | MCP79 Co-processor           | 1     |            | 3D0D6AEFBF |
| 10de:0aa3 | 1071:9515 | Nvidia     | MCP79 Co-processor           | 1     | nvidia     | E028F277D4 |
| 10de:0aa3 | 1b0a:4203 | Nvidia     | MCP79 Co-processor           | 1     |            | 926753D3C7 |
| 10de:0aa3 | 1b7d:0040 | Nvidia     | MCP79 Co-processor           | 1     |            | 053ACCA095 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e3a | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 296   | mei_me     | 8CE0C08E9A |
| 8086:1c3a | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 185   | mei_me     | 89EF922929 |
| 8086:9c3a | 17aa:3978 | Intel      | 8 Series HECI #0             | 113   | mei_me     | 972580DCF6 |
| 8086:3b64 | 17aa:215f | Intel      | 5 Series/3400 Series Chip... | 108   | mei_me     | 9A495F134B |
| 8086:3b64 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 89    | mei_me     | 088FFC2823 |
| 8086:1c3a | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 88    | mei_me     | B7B1C7DF29 |
| 8086:1e3a | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 88    | mei_me     | 7857E6A77B |
| 8086:1c3a | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 80    | mei_me     | 25D909CC38 |
| 8086:2a44 | 17aa:20e6 | Intel      | Mobile 4 Series Chipset M... | 79    | mei_me     | 1A90AC4588 |
| 8086:3b64 | 17aa:38a5 | Intel      | 5 Series/3400 Series Chip... | 78    | mei_me     | 15789D122D |
| 8086:1e3a | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 75    | mei_me     | 1C3C62EC29 |
| 8086:1e3a | 1043:124d | Intel      | 7 Series/C216 Chipset Fam... | 69    | mei_me     | 179397B4EA |
| 8086:1c3a | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 67    | mei_me     | 47A635ACC1 |
| 8086:1e3a | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 67    | mei_me     | EFE09AFB77 |
| 8086:1e3a | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 66    | mei_me     | 9084C70732 |
| 8086:3b64 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 64    | mei_me     | 53ECD14649 |
| 8086:8c3a | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 60    | mei_me     | F21C5B69B8 |
| 8086:3b64 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 56    | mei_me     | 90D3759348 |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 55    | mei_me     | 97BCBB884E |
| 8086:1c3a | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 52    | mei_me     | 4DB132BB33 |
| 8086:1e3a | 17aa:5011 | Intel      | 7 Series/C216 Chipset Fam... | 50    | mei_me     | 82A9861AFD |
| 8086:1c3a | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 49    | mei_me     | 0BF9EE57AF |
| 8086:1c3a | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 48    | mei_me     | F3FBF8BC70 |
| 8086:1c3a | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 47    | mei_me     | DF459BC2B0 |
| 8086:1e3a | 1043:14c7 | Intel      | 7 Series/C216 Chipset Fam... | 47    | mei_me     | 12F5A59D53 |
| 8086:1e3a | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 47    | mei_me     | D28ACFF1E6 |
| 8086:1e3a | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 44    | mei_me     | B162D0FD81 |
| 8086:9c3a | 1025:0866 | Intel      | 8 Series HECI #0             | 43    | mei_me     | 3FD761163B |
| 8086:1e3a | 17aa:21f6 | Intel      | 7 Series/C216 Chipset Fam... | 42    | mei_me     | 1949413DC7 |
| 8086:1c3a | 144d:c0b6 | Intel      | 6 Series/C200 Series Chip... | 41    | mei_me     | 5118CD27DD |
| 8086:1c3a | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 40    | mei_me     | CA779DE74C |
| 8086:5a9a | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 40    | mei_me     | F885D0EE5F |
| 8086:1e3a | 1043:1477 | Intel      | 7 Series/C216 Chipset Fam... | 37    | mei_me     | C005B421A9 |
| 8086:1c3a | 104d:908b | Intel      | 6 Series/C200 Series Chip... | 36    | mei_me     | A9E0A905BD |
| 8086:1e3a | 1179:fb31 | Intel      | 7 Series/C216 Chipset Fam... | 36    | mei_me     | A0FFB29C6C |
| 8086:1e3a | 144d:c652 | Intel      | 7 Series/C216 Chipset Fam... | 35    | mei_me     | 7F741A485F |
| 8086:9c3a | 17aa:220c | Intel      | 8 Series HECI #0             | 35    | mei_me     | 14015A6CDE |
| 8086:1c3a | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 34    | mei_me     | 2B202B204B |
| 8086:1e3a | 1043:1587 | Intel      | 7 Series/C216 Chipset Fam... | 34    | mei_me     | A14ECCA066 |
| 8086:1e3a | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 34    | mei_me     | AFB801A018 |
| 8086:319a | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 34    | mei_me     | 59974C206C |
| 8086:9c3a | 1025:0775 | Intel      | 8 Series HECI #0             | 34    | mei_me     | 94CD691A35 |
| 8086:1e3a | 10cf:16ea | Intel      | 7 Series/C216 Chipset Fam... | 33    | mei_me     | DA5836E2AA |
| 8086:9d3a | 17aa:386e | Intel      | Sunrise Point-LP CSME HEC... | 33    | mei_me     | 91D8C5CEC3 |
| 8086:1e3a | 144d:c0d8 | Intel      | 7 Series/C216 Chipset Fam... | 32    | mei_me     | C5694CCAC0 |
| 8086:9c3a | 1028:0651 | Intel      | 8 Series HECI #0             | 32    | mei_me     | DBD15FDF3D |
| 8086:1e3a | 1025:0686 | Intel      | 7 Series/C216 Chipset Fam... | 31    | mei_me     | 1F28286A78 |
| 8086:3b64 | 144d:c581 | Intel      | 5 Series/3400 Series Chip... | 31    | mei_me     | D9ECE67AC1 |
| 8086:9d3a | 1025:1193 | Intel      | Sunrise Point-LP CSME HEC... | 31    | mei_me     | 02EEEC88C4 |
| 8086:9c3a | 1043:131d | Intel      | 8 Series HECI #0             | 30    | mei_me     | 9F136B8761 |
| 8086:1c3a | 103c:161c | Intel      | 6 Series/C200 Series Chip... | 29    | mei_me     | 3EAB448396 |
| 8086:1c3a | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 29    | mei_me     | DA7FEA9DD2 |
| 8086:1e3a | 104d:90b8 | Intel      | 7 Series/C216 Chipset Fam... | 29    | mei_me     | B9133671A8 |
| 8086:9d3a | 1025:1085 | Intel      | Sunrise Point-LP CSME HEC... | 29    | mei_me     | 8BC74BD7FB |
| 8086:1c3a | 103c:167c | Intel      | 6 Series/C200 Series Chip... | 27    | mei_me     | A56D8D1C28 |
| 8086:1c3a | 1179:fc30 | Intel      | 6 Series/C200 Series Chip... | 27    | mei_me     | A1569BC1E6 |
| 8086:9c3a | 1043:16cd | Intel      | 8 Series HECI #0             | 27    | mei_me     | 786924EC40 |
| 8086:9d3a | 1025:115f | Intel      | Sunrise Point-LP CSME HEC... | 27    | mei_me     | A230640EC7 |
| 8086:1e3a | 104d:90ab | Intel      | 7 Series/C216 Chipset Fam... | 26    | mei_me     | A8AF2E8A8D |
| 8086:3b64 | 1025:036d | Intel      | 5 Series/3400 Series Chip... | 26    | mei_me     | D16FFC45F1 |
| 8086:3b64 | 10cf:152b | Intel      | 5 Series/3400 Series Chip... | 26    | mei_me     | 95D76D0DE1 |
| 8086:9cba | 1025:098a | Intel      | Wildcat Point-LP MEI Cont... | 26    | mei_me     | 5861B2E713 |
| 8086:9d3a |           | Intel      | Sunrise Point-LP CSME HEC... | 26    | mei_me     | 32D65CC437 |
| 8086:9d3a | 103c:832a | Intel      | Sunrise Point-LP CSME HEC... | 26    | mei_me     | 931D7104FA |
| 8086:1c3a | 1025:0511 | Intel      | 6 Series/C200 Series Chip... | 25    | mei_me     | 832F6EF100 |
| 8086:1e3a | 103c:1818 | Intel      | 7 Series/C216 Chipset Fam... | 25    | mei_me     | 6C34B57DD0 |
| 8086:9d3a | 17aa:3801 | Intel      | Sunrise Point-LP CSME HEC... | 25    | mei_me     | 3493C4EBA1 |
| 8086:1c3a | 103c:3388 | Intel      | 6 Series/C200 Series Chip... | 24    | mei_me     | C7D96BB884 |
| 8086:1e3a | 1025:0835 | Intel      | 7 Series/C216 Chipset Fam... | 24    | mei_me     | 9D92944E6C |
| 8086:1e3a | 103c:179b | Intel      | 7 Series/C216 Chipset Fam... | 24    | mei_me     | 7195452FF3 |
| 8086:a328 | 1025:1264 | Intel      | Cannon Lake PCH Serial IO... | 24    | intel_lpss | AF51F8907E |
| 8086:a360 | 1025:1264 | Intel      | Cannon Lake PCH HECI Cont... | 24    | mei_me     | AF51F8907E |
| 8086:a360 | 1028:087c | Intel      | Cannon Lake PCH HECI Cont... | 24    | mei_me     | 18DC19F3EC |
| 8086:1c3a | 103c:1670 | Intel      | 6 Series/C200 Series Chip... | 23    | mei_me     | AC00D2B8C4 |
| 8086:1e3a | 103c:17f6 | Intel      | 7 Series/C216 Chipset Fam... | 23    | mei_me     | 1F9408B984 |
| 8086:3b64 | 1028:0447 | Intel      | 5 Series/3400 Series Chip... | 23    | mei_me     | D5FEC65DF9 |
| 8086:3b64 | 103c:7008 | Intel      | 5 Series/3400 Series Chip... | 23    | mei_me     | 4663DEB0DD |
| 8086:5a9a | 1043:1de0 | Intel      | Celeron N3350/Pentium N42... | 23    | mei_me     | 6391F5ED0E |
| 8086:9cba | 1043:10d0 | Intel      | Wildcat Point-LP MEI Cont... | 23    | mei_me     | CF2D08BE47 |
| 8086:9d3a | 103c:8079 | Intel      | Sunrise Point-LP CSME HEC... | 23    | mei_me     | BCF0EBFEDD |
| 8086:1c3a | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 22    | mei_me     | DF04D39AC3 |
| 8086:1e3a | 1028:0597 | Intel      | 7 Series/C216 Chipset Fam... | 22    | mei_me     | 7C2D23E11D |
| 8086:8c3a | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 22    | mei_me     | 3021488D7B |
| 8086:9cba | 17aa:5034 | Intel      | Wildcat Point-LP MEI Cont... | 22    | mei_me     | 71DE9234CB |
| 8086:9d3a | 1043:1a00 | Intel      | Sunrise Point-LP CSME HEC... | 22    | mei_me     | 8C29A78852 |
| 8086:1e3a | 1028:0534 | Intel      | 7 Series/C216 Chipset Fam... | 21    | mei_me     | 39D47C0F09 |
| 8086:1e3a | 103c:183e | Intel      | 7 Series/C216 Chipset Fam... | 21    | mei_me     | 232BC57E62 |
| 8086:1e3a | 1043:1457 | Intel      | 7 Series/C216 Chipset Fam... | 21    | mei_me     | 89ABB69269 |
| 8086:1e3a | 1b0a:20ca | Intel      | 7 Series/C216 Chipset Fam... | 21    | mei_me     | AD24DC02F0 |
| 8086:3b64 | 103c:143a | Intel      | 5 Series/3400 Series Chip... | 21    | mei_me     | E4428DA94F |
| 8086:3b64 | 1179:ff1e | Intel      | 5 Series/3400 Series Chip... | 21    | mei_me     | A8E11B6717 |
| 8086:8c3a | 1025:0781 | Intel      | 8 Series/C220 Series Chip... | 21    | mei_me     | 19E141A0F7 |
| 8086:9cba | 17aa:390b | Intel      | Wildcat Point-LP MEI Cont... | 21    | mei_me     | 81E6241D52 |
| 8086:1e3a | 1028:0572 | Intel      | 7 Series/C216 Chipset Fam... | 20    | mei_me     | 19B3FE3FF8 |
| 8086:319a | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | mei_me     | 7E86F1B5E7 |
| 8086:8c3a | 8086:2010 | Intel      | 8 Series/C220 Series Chip... | 20    | mei_me     | D11FBEC88A |
| 8086:9c3a | 17aa:2214 | Intel      | 8 Series HECI #0             | 20    | mei_me     | 43DDF539E2 |
| 8086:9cba | 1043:1a6d | Intel      | Wildcat Point-LP MEI Cont... | 20    | mei_me     | DF4413AF58 |
| 8086:9d3a | 17aa:5068 | Intel      | Sunrise Point-LP CSME HEC... | 20    | mei_me     | F4826C3A2A |
| 8086:1e3a | 1179:ff1e | Intel      | 7 Series/C216 Chipset Fam... | 19    | mei_me     | BC5AB2CB48 |

### Dma controller (eisa dma) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9ce0 | 8086:9ce0 | Intel      | Wildcat Point-LP Serial I... | 17    | dw_dmac... | 1A26D7B485 |
| 8086:9c60 |           | Intel      | 8 Series Low Power Sub-Sy... | 6     | dw_dmac... | 52DA4E98F9 |
| 8086:2286 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 5     | dw_dmac... | 287D86CC83 |
| 8086:22c0 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 5     | dw_dmac... | 287D86CC83 |
| 8086:9c60 | 1025:0a11 | Intel      | 8 Series Low Power Sub-Sy... | 3     | dw_dmac... | 85437DFA84 |
| 8086:9c60 | 103c:21ed | Intel      | 8 Series Low Power Sub-Sy... | 2     | dw_dmac... | 4D0C47EAB1 |
| 8086:0f40 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | 0994A3EEB3 |
| 8086:2286 | 1025:106c | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 09F6D20FE1 |
| 8086:22c0 | 1025:106c | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 09F6D20FE1 |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1537 | 1022:1537 | AMD        | Kabini/Mullins PSP-Platfo... | 142   | ccp        | 4DC7D17844 |
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 119   | mei_txe    | AE477CA654 |
| 1022:15df | 1022:15df | AMD        | Family 17h (Models 10h-1f... | 72    |            | 9809687258 |
| 1022:1537 | 17aa:3801 | AMD        | Kabini/Mullins PSP-Platfo... | 59    | ccp        | 363B08984A |
| 8086:0f18 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 59    | mei_txe    | F2797B8B83 |
| 1022:1578 | 103c:8330 | AMD        | Carrizo Platform Security... | 47    |            | E26638D750 |
| 8086:0f18 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 47    | mei_txe    | 27F3692E24 |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 38    |            | 5566AEFD34 |
| 8086:0f18 | 17aa:3909 | Intel      | Atom Processor Z36xxx/Z37... | 38    | mei_txe    | 7D85F9BFAB |
| 1022:1578 | 1025:1192 | AMD        | Carrizo Platform Security... | 37    |            | 17E62D31B9 |
| 8086:0f18 | 8086:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 34    | mei_txe    | 33401FDBF4 |
| 8086:2298 | 1025:1012 | Intel      | Atom/Celeron/Pentium Proc... | 32    | mei_txe    | 0949108352 |
| 8086:0f18 | 1043:14dd | Intel      | Atom Processor Z36xxx/Z37... | 31    | mei_txe    | CC9B263062 |
| 1022:1578 | 17aa:3810 | AMD        | Carrizo Platform Security... | 30    |            | 8B23CB3E69 |
| 8086:0f18 | 1297:2041 | Intel      | Atom Processor Z36xxx/Z37... | 27    | mei_txe    | 199C248CC1 |
| 8086:0f18 | 103c:2213 | Intel      | Atom Processor Z36xxx/Z37... | 26    | mei_txe    | 8DF8DAD46F |
| 8086:0f18 | 1043:161d | Intel      | Atom Processor Z36xxx/Z37... | 26    | mei_txe    | 7BE60A0A2C |
| 1022:15df | 103c:84ae | AMD        | Family 17h (Models 10h-1f... | 24    |            | 3B491B92B3 |
| 8086:2298 | 1043:10c0 | Intel      | Atom/Celeron/Pentium Proc... | 23    | mei_txe    | FB8F7369FA |
| 8086:0f18 | 1043:15bd | Intel      | Atom Processor Z36xxx/Z37... | 22    | mei_txe    | 6D7501C42A |
| 8086:0f18 | 17aa:3986 | Intel      | Atom Processor Z36xxx/Z37... | 22    | mei_txe    | 4D7E6E73B6 |
| 8086:2298 | 1028:06ac | Intel      | Atom/Celeron/Pentium Proc... | 20    | mei_txe    | 8C1ED50973 |
| 1022:1578 | 103c:84ac | AMD        | Carrizo Platform Security... | 18    |            | 6EEF4CAED6 |
| 8086:2298 | 17aa:3808 | Intel      | Atom/Celeron/Pentium Proc... | 18    | mei_txe    | 10AB399874 |
| 1022:1537 | 17aa:3808 | AMD        | Kabini/Mullins PSP-Platfo... | 17    | ccp        | 14B5F106DB |
| 1022:1578 | 103c:8331 | AMD        | Carrizo Platform Security... | 17    |            | 7C2CCF2AA7 |
| 8086:2298 | 103c:832c | Intel      | Atom/Celeron/Pentium Proc... | 15    | mei_txe    | A92F12150A |
| 1022:1578 | 103c:8333 | AMD        | Carrizo Platform Security... | 14    |            | 6950ED44FE |
| 8086:2298 | 1043:12e0 | Intel      | Atom/Celeron/Pentium Proc... | 14    | mei_txe    | A14B78EF65 |
| 1022:1537 | 1025:104b | AMD        | Kabini/Mullins PSP-Platfo... | 13    | ccp        | 356E0F5C70 |
| 1022:15df | 17aa:3809 | AMD        | Family 17h (Models 10h-1f... | 11    |            | 6206EB1A2F |
| 8086:0f18 | 1558:5470 | Intel      | Atom Processor Z36xxx/Z37... | 11    | mei_txe    | DC84B60140 |
| 8086:2298 | 103c:80c5 | Intel      | Atom/Celeron/Pentium Proc... | 11    | mei_txe    | DF94931018 |
| 1022:1578 | 17aa:380f | AMD        | Carrizo Platform Security... | 10    |            | F9C34FA042 |
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
| 1022:15df | 1025:125c | AMD        | Family 17h (Models 10h-1f... | 8     |            | B9A37AB909 |
| 1022:15df | 103c:84e7 | AMD        | Family 17h (Models 10h-1f... | 8     |            | EA1E118AD6 |
| 8086:0f18 | 103c:2190 | Intel      | Atom Processor Z36xxx/Z37... | 8     | mei_txe    | 0EE1D25C7E |
| 8086:0f18 | 103c:21de | Intel      | Atom Processor Z36xxx/Z37... | 8     | mei_txe    | C2C66314AF |
| 8086:0f18 | 1179:f91b | Intel      | Atom Processor Z36xxx/Z37... | 8     | mei_txe    | AB7FDCFEBC |
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
| 8086:2298 | 103c:82bd | Intel      | Atom/Celeron/Pentium Proc... | 6     | mei_txe    | 777D549872 |
| 8086:2298 | 103c:8320 | Intel      | Atom/Celeron/Pentium Proc... | 6     | mei_txe    | 36570780B5 |
| 8086:2298 | 103c:8342 | Intel      | Atom/Celeron/Pentium Proc... | 6     | mei_txe    | 989461CCA6 |
| 8086:2298 | 17aa:380b | Intel      | Atom/Celeron/Pentium Proc... | 6     | mei_txe    | 167CFC70E5 |
| 1022:1537 | 103c:226a | AMD        | Kabini/Mullins PSP-Platfo... | 5     | ccp        | E5C53C61E8 |
| 1022:1537 | 103c:226b | AMD        | Kabini/Mullins PSP-Platfo... | 5     | ccp        | 76B4B1F70F |
| 1022:1537 | 103c:82f6 | AMD        | Kabini/Mullins PSP-Platfo... | 5     | ccp        | F14F865A3D |
| 1022:1578 | 1028:087e | AMD        | Carrizo Platform Security... | 5     |            | D72F217DE7 |
| 1022:1578 | 103c:81fa | AMD        | Carrizo Platform Security... | 5     |            | CD1E50AD54 |
| 1022:1578 | 103c:81fe | AMD        | Carrizo Platform Security... | 5     |            | B0EAB1E9FE |
| 1022:1578 | 103c:84a0 | AMD        | Carrizo Platform Security... | 5     |            | B34D6AAB90 |
| 1022:1578 | 17aa:380c | AMD        | Carrizo Platform Security... | 5     |            | 99302C7F68 |
| 1022:15df | 1028:0812 | AMD        | Family 17h (Models 10h-1f... | 5     |            | 90C3D47F26 |
| 1022:15df | 103c:84d2 | AMD        | Family 17h (Models 10h-1f... | 5     |            | DFC4334B0C |
| 1022:15df | 19e5:3e06 | AMD        | Family 17h (Models 10h-1f... | 5     |            | 85DF07509C |
| 8086:0f18 |           | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | 94D1AC4B4E |
| 8086:0f18 | 1025:0928 | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | 736C6C41BC |
| 8086:0f18 | 103c:2209 | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | C07CF80476 |
| 8086:0f18 | 1043:14ed | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | 3B8A5EA4C5 |
| 8086:2298 | 1028:0725 | Intel      | Atom/Celeron/Pentium Proc... | 5     | mei_txe    | 94A897D5A7 |
| 8086:2298 | 103c:813e | Intel      | Atom/Celeron/Pentium Proc... | 5     | mei_txe    | 43F9ACD60A |
| 8086:2298 | 1297:2053 | Intel      | Atom/Celeron/Pentium Proc... | 5     | mei_txe    | 5FE5836ED6 |
| 1022:1456 | 1022:1456 | AMD        | Family 17h (Models 00h-0f... | 4     | ccp        | 35BF9EB2EF |
| 1022:1578 | 1025:1087 | AMD        | Carrizo Platform Security... | 4     |            | D5082D8C3F |
| 1022:1578 | 1025:1201 | AMD        | Carrizo Platform Security... | 4     |            | 15574B1FE0 |
| 1022:1578 | 1028:0769 | AMD        | Carrizo Platform Security... | 4     |            | 5F8E475ACD |
| 1022:1578 | 103c:81f9 | AMD        | Carrizo Platform Security... | 4     |            | 832AAFEB1A |
| 1022:1578 | 103c:8332 | AMD        | Carrizo Platform Security... | 4     |            | 7653D7FA4D |
| 1022:1578 | 103c:8345 | AMD        | Carrizo Platform Security... | 4     |            | 7E3B6FA95F |
| 1022:1578 | 103c:84ad | AMD        | Carrizo Platform Security... | 4     |            | 666B6342E0 |
| 1022:1578 | 17aa:3805 | AMD        | Carrizo Platform Security... | 4     |            | A2DA44CE3D |
| 1022:15df | 1025:1259 | AMD        | Family 17h (Models 10h-1f... | 4     |            | 32C519104F |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1180:0832 | 17aa:20c7 | Ricoh      | R5C832 IEEE 1394 Controller  | 103   | firewir... | 1A90AC4588 |
| 11c1:5901 | 11c1:5900 | LSI        | FW643 [TrueFire] PCIe 139... | 80    | firewir... | 2B202B204B |
| 104c:803a | 1025:011f | Texas I... | PCIxx12 OHCI Compliant IE... | 71    | firewir... | BA9EFF4F3B |
| 1180:e832 | 17aa:2136 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 51    | firewir... | 9A495F134B |
| 104c:803a | 1179:ff00 | Texas I... | PCIxx12 OHCI Compliant IE... | 45    | firewir... | CCB7CB26D3 |
| 1180:0832 | 1028:0233 | Ricoh      | R5C832 IEEE 1394 Controller  | 34    | firewir... | 314E0FF832 |
| 1217:00f7 | 1028:01f9 | O2 Micro   | Firewire (IEEE 1394)         | 31    | firewir... | 4908DA86B8 |
| 1180:0832 | 1028:022f | Ricoh      | R5C832 IEEE 1394 Controller  | 29    | firewir... | 56866B9E4C |
| 1180:0832 | 103c:30cc | Ricoh      | R5C832 IEEE 1394 Controller  | 29    | firewir... | 218FD78ECA |
| 1180:e832 | 1028:040a | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 29    | firewir... | 3E3F341EF4 |
| 197b:2380 | 103c:161c | JMicron... | IEEE 1394 Host Controller    | 29    | firewir... | 3EAB448396 |
| 11c1:5811 | 11c1:5811 | LSI        | FW322/323 [TrueFire] 1394... | 26    | firewir... | A760ED1DA6 |
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
| 1180:0832 | 1043:1317 | Ricoh      | R5C832 IEEE 1394 Controller  | 17    | firewir... | 4841CD6D3C |
| 1180:e832 | 17aa:21ce | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 17    | firewir... | AB2CEA0D81 |
| 197b:2380 | 103c:3628 | JMicron... | IEEE 1394 Host Controller    | 17    | firewir... | BF5A8C1756 |
| 104c:803a | 1179:ff10 | Texas I... | PCIxx12 OHCI Compliant IE... | 16    | firewir... | 5FDCE37F38 |
| 1180:e832 | 1028:040b | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 16    | firewir... | 47A22D2542 |
| 1180:0832 | 1028:01bd | Ricoh      | R5C832 IEEE 1394 Controller  | 15    | firewir... | AB555162C8 |
| 1180:0832 | 1028:024f | Ricoh      | R5C832 IEEE 1394 Controller  | 15    | firewir... | 9F216D6CB3 |
| 1180:0832 | 1043:1897 | Ricoh      | R5C832 IEEE 1394 Controller  | 15    | firewir... | B720D65E19 |
| 1180:0832 | 103c:172a | Ricoh      | R5C832 IEEE 1394 Controller  | 14    | firewir... | D1C32BF428 |
| 1180:0832 | 1043:14e7 | Ricoh      | R5C832 IEEE 1394 Controller  | 14    | firewir... | 7AC6E3C864 |
| 1180:0832 | 104d:9035 | Ricoh      | R5C832 IEEE 1394 Controller  | 14    | firewir... | 0C80B6E23F |
| 197b:2380 | 103c:1618 | JMicron... | IEEE 1394 Host Controller    | 14    | firewir... | 0D2FE88BE0 |
| 197b:2380 | 103c:17ab | JMicron... | IEEE 1394 Host Controller    | 14    | firewir... | 57308077EE |
| 1180:0832 | 1043:1517 | Ricoh      | R5C832 IEEE 1394 Controller  | 13    | firewir... | 427546EA21 |
| 1180:0832 | 1179:ff1c | Ricoh      | R5C832 IEEE 1394 Controller  | 13    | firewir... | 420C738977 |
| 1217:13f7 | 1028:0494 | O2 Micro   | 1394 OHCI Compliant Host ... | 13    | firewir... | 4384225066 |
| 197b:2380 | 103c:3603 | JMicron... | IEEE 1394 Host Controller    | 13    | firewir... | F2190D7446 |
| 1180:0832 | 103c:30c0 | Ricoh      | R5C832 IEEE 1394 Controller  | 12    | firewir... | A4D3F8A8AC |
| 1180:0832 | 1043:1767 | Ricoh      | R5C832 IEEE 1394 Controller  | 12    | firewir... | 4137AC8F54 |
| 1217:11f7 | 1028:04a3 | O2 Micro   | OZ600 1394a-2000 Controller  | 12    | firewir... | D8BA5B1425 |
| 197b:2380 | 103c:3659 | JMicron... | IEEE 1394 Host Controller    | 12    | firewir... | B48F5D5FDD |
| 1180:0832 | 1028:029a | Ricoh      | R5C832 IEEE 1394 Controller  | 11    | firewir... | 394D903321 |
| 1180:0832 | 103c:30db | Ricoh      | R5C832 IEEE 1394 Controller  | 11    | firewir... | 94AF8C86B1 |
| 1180:0832 | 103c:7007 | Ricoh      | R5C832 IEEE 1394 Controller  | 11    | firewir... | 82CB2D5E90 |
| 11c1:5811 | 103c:30dd | LSI        | FW322/323 [TrueFire] 1394... | 11    | firewir... | B7DD4F6E2C |
| 1217:13f7 | 1028:049a | O2 Micro   | 1394 OHCI Compliant Host ... | 11    | firewir... | 6FD4500E86 |
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
| 1180:0832 | 1028:01f2 | Ricoh      | R5C832 IEEE 1394 Controller  | 8     | firewir... | 09BC8D2536 |
| 1180:0832 | 1028:023a | Ricoh      | R5C832 IEEE 1394 Controller  | 8     | firewir... | 832410EBE7 |
| 1180:0832 | 103c:1521 | Ricoh      | R5C832 IEEE 1394 Controller  | 8     | firewir... | 283EC51B86 |
| 1180:0832 | 104d:900e | Ricoh      | R5C832 IEEE 1394 Controller  | 8     | firewir... | 7B4B0311EA |
| 1180:0832 | 17aa:3829 | Ricoh      | R5C832 IEEE 1394 Controller  | 8     | firewir... | 3C97F337A2 |
| 1180:e832 | 104d:9069 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 8     | firewir... | D21AA077CE |
| 1217:10f7 | 1028:02bc | O2 Micro   | 1394 OHCI Compliant Host ... | 8     | firewir... | E1FF130D0A |
| 1217:13f7 | 1028:049b | O2 Micro   | 1394 OHCI Compliant Host ... | 8     | firewir... | 4673399116 |
| 104c:803a | 103c:30aa | Texas I... | PCIxx12 OHCI Compliant IE... | 7     | firewir... | 9C1BF7D811 |
| 104c:803a | 104d:81e6 | Texas I... | PCIxx12 OHCI Compliant IE... | 7     | firewir... | 047C3A9402 |
| 104c:803a | 104d:9005 | Texas I... | PCIxx12 OHCI Compliant IE... | 7     | firewir... | 9B1280E7FC |
| 1106:3044 | 14c0:0020 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 7     | firewir... | 0351248973 |
| 1180:0552 | 1043:1237 | Ricoh      | R5C552 IEEE 1394 Controller  | 7     | firewir... | C1DA7EE91F |
| 1180:0832 | 1025:011d | Ricoh      | R5C832 IEEE 1394 Controller  | 7     | firewir... | 2BD735CBDF |
| 1180:0832 | 1028:024d | Ricoh      | R5C832 IEEE 1394 Controller  | 7     | firewir... | 884C3CACED |
| 1180:0832 | 1179:ff1e | Ricoh      | R5C832 IEEE 1394 Controller  | 7     | firewir... | 9BD874BAB4 |
| 1180:0832 | 17aa:2109 | Ricoh      | R5C832 IEEE 1394 Controller  | 7     | firewir... | FBBABC5836 |
| 104c:803a | 1025:011c | Texas I... | PCIxx12 OHCI Compliant IE... | 6     | firewir... | AD2D03638A |
| 104c:803a | 104d:9016 | Texas I... | PCIxx12 OHCI Compliant IE... | 6     | firewir... | FF1CDF1811 |
| 1180:0832 | 1028:0228 | Ricoh      | R5C832 IEEE 1394 Controller  | 6     | firewir... | 5672A8EE03 |
| 1180:0832 | 1028:0263 | Ricoh      | R5C832 IEEE 1394 Controller  | 6     | firewir... | D16BF3353E |
| 1180:0832 | 1028:02a0 | Ricoh      | R5C832 IEEE 1394 Controller  | 6     | firewir... | 98264016B9 |
| 1180:0832 | 103c:30c2 | Ricoh      | R5C832 IEEE 1394 Controller  | 6     | firewir... | 0FDD28110E |
| 1180:0832 | 103c:30c5 | Ricoh      | R5C832 IEEE 1394 Controller  | 6     | firewir... | AB3B50FF87 |
| 1180:0832 | 103c:30cd | Ricoh      | R5C832 IEEE 1394 Controller  | 6     | firewir... | 65DCADAC42 |
| 1180:0832 | 17aa:3d94 | Ricoh      | R5C832 IEEE 1394 Controller  | 6     | firewir... | 81D0AC0AA8 |
| 1180:e832 | 1028:0402 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 6     | firewir... | 400532E714 |
| 1217:00f7 | 1028:01fe | O2 Micro   | Firewire (IEEE 1394)         | 6     | firewir... | 8CD472192D |
| 197b:2380 | 103c:162a | JMicron... | IEEE 1394 Host Controller    | 6     | firewir... | 6D298DA4A5 |
| 197b:2380 | 103c:1631 | JMicron... | IEEE 1394 Host Controller    | 6     | firewir... | F1C7178572 |
| 197b:2380 | 103c:176b | JMicron... | IEEE 1394 Host Controller    | 6     | firewir... | 4C4BD75E1B |
| 197b:2380 | 103c:3624 | JMicron... | IEEE 1394 Host Controller    | 6     | firewir... | 0C8D7641B2 |
| 197b:2380 | 103c:7001 | JMicron... | IEEE 1394 Host Controller    | 6     | firewir... | 2D49142FA9 |
| 104c:8023 | 1179:0001 | Texas I... | TSB43AB22A IEEE-1394a-200... | 5     | firewir... | AACC3C982F |
| 104c:8025 |           | Texas I... | TSB82AA2 IEEE-1394b Link ... | 5     | firewir... | 3A660A2575 |
| 104c:8032 | 1179:ff00 | Texas I... | OHCI Compliant IEEE 1394 ... | 5     | firewir... | 8488B3D0B9 |
| 104c:803a | 104d:8212 | Texas I... | PCIxx12 OHCI Compliant IE... | 5     | firewir... | B389939EE8 |
| 1106:3044 | 1025:009f | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 5     | firewir... | 2D2CBC0A8D |
| 1180:0551 | 144d:b023 | Ricoh      | R5C551 IEEE 1394 Controller  | 5     | firewir... | 529607257E |

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
| 1022:1577 | 1022:1577 | AMD        | Family 15h (Models 60h-6f... | 83    |            | 8B23CB3E69 |
| 1022:1577 | 103c:8331 | AMD        | Family 15h (Models 60h-6f... | 17    |            | 7C2CCF2AA7 |
| 1022:1423 | 1022:1423 | AMD        | Family 15h (Models 30h-3f... | 6     |            | 1C82C3C564 |
| 1022:1577 | 103c:81fa | AMD        | Family 15h (Models 60h-6f... | 5     |            | CD1E50AD54 |
| 1022:1423 | 103c:812f | AMD        | Family 15h (Models 30h-3f... | 3     |            | CEC70BF357 |
| 1022:1451 | 1022:1451 | AMD        | Family 17h (Models 00h-0f... | 3     |            | 35BF9EB2EF |
| 1022:1577 | 103c:80b5 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 407AB6CE27 |
| 1022:1577 | 103c:80b6 | AMD        | Family 15h (Models 60h-6f... | 2     |            | BEA3C73273 |
| 1022:1577 | 103c:8355 | AMD        | Family 15h (Models 60h-6f... | 2     |            | D6F5348EC7 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 111   | i915       | AE477CA654 |
| 8086:a011 | 1043:83ac | Intel      | Atom Processor D4xx/D5xx/... | 88    | i915       | E368A28816 |
| 8086:a012 | 1043:83ac | Intel      | Atom Processor D4xx/D5xx/... | 88    |            | E368A28816 |
| 8086:0046 | 17aa:215a | Intel      | Core Processor Integrated... | 75    | i915       | 9C774DC87F |
| 8086:0166 | 1025:0647 | Intel      | 3rd Gen Core processor Gr... | 69    | i915       | 9084C70732 |
| 8086:0106 | 1025:0649 | Intel      | 2nd Generation Core Proce... | 61    | i915       | 7857E6A77B |
| 8086:2a42 | 17aa:20e4 | Intel      | Mobile 4 Series Chipset I... | 60    | i915       | 1A90AC4588 |
| 8086:2a43 | 17aa:20e4 | Intel      | Mobile 4 Series Chipset I... | 60    |            | 1A90AC4588 |
| 8086:0f31 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 57    | i915       | F2797B8B83 |
| 8086:2a02 | 1025:011f | Intel      | Mobile GM965/GL960 Integr... | 57    | i915       | BA9EFF4F3B |
| 8086:2a03 | 1025:011f | Intel      | Mobile GM965/GL960 Integr... | 57    |            | BA9EFF4F3B |
| 8086:2a42 | 1043:1862 | Intel      | Mobile 4 Series Chipset I... | 56    | i915       | 429A82D3C7 |
| 8086:2a42 | 17aa:3a02 | Intel      | Mobile 4 Series Chipset I... | 56    | i915       | 5986AA0AAC |
| 8086:2a43 | 1043:1862 | Intel      | Mobile 4 Series Chipset I... | 56    |            | 429A82D3C7 |
| 8086:2a43 | 17aa:3a02 | Intel      | Mobile 4 Series Chipset I... | 56    |            | 5986AA0AAC |
| 8086:0156 | 17aa:3977 | Intel      | 3rd Gen Core processor Gr... | 55    | i915       | 176A1CCFC5 |
| 8086:0116 | 1025:0504 | Intel      | 2nd Generation Core Proce... | 54    | i915       | 25D909CC38 |
| 8086:a011 | 1025:0349 | Intel      | Atom Processor D4xx/D5xx/... | 54    | i915       | A911172500 |
| 8086:a012 | 1025:0349 | Intel      | Atom Processor D4xx/D5xx/... | 54    |            | A911172500 |
| 8086:0166 | 17aa:3977 | Intel      | 3rd Gen Core processor Gr... | 52    | i915       | 3DCE4D353B |
| 8086:0166 | 17aa:5003 | Intel      | 3rd Gen Core processor Gr... | 52    | i915       | 1C3C62EC29 |
| 8086:0166 | 1043:124d | Intel      | 3rd Gen Core processor Gr... | 50    | i915       | 179397B4EA |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics 500              | 50    | i915       | 97BCBB884E |
| 8086:0be1 | 1043:84a9 | Intel      | Atom Processor D2xxx/N2xx... | 48    | gma500_gfx | ECB853F69D |
| 1002:98e4 | 103c:8330 | AMD        | Stoney [Radeon R2/R3/R4/R... | 47    | amdgpu     | E26638D750 |
| 8086:0106 | 17aa:3975 | Intel      | 2nd Generation Core Proce... | 45    | i915       | 7C676D0AAC |
| 8086:0166 | 1025:064b | Intel      | 3rd Gen Core processor Gr... | 43    | i915       | D78E0C1E84 |
| 1002:68e4 | 17aa:397a | AMD        | Robson CE [Radeon HD 6370... | 42    | radeon     | 0A5AF961D7 |
| 8086:0f31 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 42    | i915       | 27F3692E24 |
| 8086:0a16 | 1025:0866 | Intel      | Haswell-ULT Integrated Gr... | 41    | i915       | 3FD761163B |
| 8086:0116 | 1043:1682 | Intel      | 2nd Generation Core Proce... | 39    | i915       | A874D7CE23 |
| 8086:0f31 | 17aa:3909 | Intel      | Atom Processor Z36xxx/Z37... | 38    | i915       | 7D85F9BFAB |
| 1002:98e4 | 1025:1192 | AMD        | Stoney [Radeon R2/R3/R4/R... | 37    | amdgpu     | 17E62D31B9 |
| 8086:0126 | 17aa:21ce | Intel      | 2nd Generation Core Proce... | 37    | i915       | F3FBF8BC70 |
| 8086:0156 | 17aa:5011 | Intel      | 3rd Gen Core processor Gr... | 37    | i915       | 82A9861AFD |
| 8086:0166 | 17aa:21f3 | Intel      | 3rd Gen Core processor Gr... | 37    | i915       | B162D0FD81 |
| 8086:2a02 | 17aa:20b5 | Intel      | Mobile GM965/GL960 Integr... | 37    | i915       | 514C92A80A |
| 8086:2a03 | 17aa:20b5 | Intel      | Mobile GM965/GL960 Integr... | 37    |            | 514C92A80A |
| 1002:5a62 | 1043:1402 | AMD        | RC410M [Mobility Radeon X... | 36    | radeon     | 6C6A2138D2 |
| 10de:0df5 | 1028:04ca | Nvidia     | GF108M [GeForce GT 525M]     | 35    | nouveau    | E693C5E3B9 |
| 1002:68e0 | 1043:1bf2 | AMD        | Park [Mobility Radeon HD ... | 34    | radeon     | 088FFC2823 |
| 8086:a011 | 144d:c072 | Intel      | Atom Processor D4xx/D5xx/... | 34    | i915       | 60127AB94A |
| 8086:a012 | 144d:c072 | Intel      | Atom Processor D4xx/D5xx/... | 34    |            | 60127AB94A |
| 8086:0116 | 144d:c0b6 | Intel      | 2nd Generation Core Proce... | 33    | i915       | 5118CD27DD |
| 8086:0166 | 17aa:21fa | Intel      | 3rd Gen Core processor Gr... | 33    | i915       | AFB801A018 |
| 8086:0a16 | 17aa:220c | Intel      | Haswell-ULT Integrated Gr... | 33    | i915       | 14015A6CDE |
| 8086:0f31 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 33    | i915       | 2332ED0DD8 |
| 8086:a011 | 1025:0590 | Intel      | Atom Processor D4xx/D5xx/... | 33    | i915       | 326A5F97CA |
| 8086:a012 | 1025:0590 | Intel      | Atom Processor D4xx/D5xx/... | 33    |            | 326A5F97CA |
| 10de:1051 | 144d:c0b6 | Nvidia     | GF119M [GeForce GT 520MX]    | 32    | nouveau    | 5CBDF51766 |
| 10de:1140 | 1025:0691 | Nvidia     | GF117M [GeForce 610M/710M... | 32    | nouveau    | 0290B46D43 |
| 8086:0116 | 1043:1652 | Intel      | 2nd Generation Core Proce... | 32    | i915       | 71FD2610FE |
| 8086:22b1 | 1025:1012 | Intel      | Atom/Celeron/Pentium Proc... | 32    | i915       | 0949108352 |
| 8086:2a42 | 1025:0212 | Intel      | Mobile 4 Series Chipset I... | 32    | i915       | CCC2EA91E1 |
| 8086:2a43 | 1025:0212 | Intel      | Mobile 4 Series Chipset I... | 32    |            | CCC2EA91E1 |
| 1002:6840 | 144d:c0da | AMD        | Thames [Radeon HD 7500M/7... | 31    | radeon     | 3CD05B2B28 |
| 10de:1051 | 144d:c606 | Nvidia     | GF119M [GeForce GT 520MX]    | 31    | nouveau    | C790C085ED |
| 8086:0106 | 17aa:3977 | Intel      | 2nd Generation Core Proce... | 31    | i915       | D6B2FD9EC1 |
| 8086:0166 | 1025:0686 | Intel      | 3rd Gen Core processor Gr... | 31    | i915       | 1F28286A78 |
| 8086:0f31 | 1043:14dd | Intel      | Atom Processor Z36xxx/Z37... | 31    | i915       | CC9B263062 |
| 10de:1058 | 1043:1652 | Nvidia     | GF119M [GeForce 610M]        | 30    | nouveau    | 54110B9929 |
| 8086:0116 | 1028:04ca | Intel      | 2nd Generation Core Proce... | 30    | i915       | 2C0E4BE82C |
| 8086:0a16 | 17aa:3978 | Intel      | Haswell-ULT Integrated Gr... | 30    | i915       | F30B5E8075 |
| 1002:6840 | 103c:184a | AMD        | Thames [Radeon HD 7500M/7... | 29    | radeon     | 4C72CE34FA |
| 8086:0126 | 1028:0493 | Intel      | 2nd Generation Core Proce... | 29    | i915       | 3F252A50FB |
| 8086:0166 | 1043:1587 | Intel      | 3rd Gen Core processor Gr... | 29    | i915       | A14ECCA066 |
| 8086:2a02 | 1028:022f | Intel      | Mobile GM965/GL960 Integr... | 29    | i915       | 56866B9E4C |
| 8086:2a03 | 1028:022f | Intel      | Mobile GM965/GL960 Integr... | 29    |            | 56866B9E4C |
| 8086:5a85 | 1043:16a0 | Intel      | HD Graphics 500              | 29    | i915       | F885D0EE5F |
| 10de:0df4 | 1043:15f2 | Nvidia     | GF108M [GeForce GT 540M]     | 28    | nouveau    | 47A635ACC1 |
| 8086:0046 | 17aa:3920 | Intel      | Core Processor Integrated... | 28    | i915       | 3C20BDA761 |
| 8086:0166 | 144d:c0d8 | Intel      | 3rd Gen Core processor Gr... | 28    | i915       | C5694CCAC0 |
| 8086:0166 | 17aa:3901 | Intel      | 3rd Gen Core processor Gr... | 28    | i915       | CE8329CC49 |
| 1002:6840 | 144d:c0d8 | AMD        | Thames [Radeon HD 7500M/7... | 27    | radeon     | C5694CCAC0 |
| 8086:0046 | 1025:0488 | Intel      | Core Processor Integrated... | 27    | i915       | 53ECD14649 |
| 8086:0116 | 144d:c606 | Intel      | 2nd Generation Core Proce... | 27    | i915       | 981F3F6502 |
| 8086:0a16 | 1043:16cd | Intel      | Haswell-ULT Integrated Gr... | 27    | i915       | 786924EC40 |
| 8086:0f31 | 1297:2041 | Intel      | Atom Processor Z36xxx/Z37... | 27    | i915       | 199C248CC1 |
| 8086:5916 | 1025:1094 | Intel      | HD Graphics 620              | 27    | i915       | A230640EC7 |
| 1002:98e4 | 17aa:39f3 | AMD        | Stoney [Radeon R2/R3/R4/R... | 26    | amdgpu     | 8B23CB3E69 |
| 10de:0a70 | 17aa:3966 | Nvidia     | GT218M [GeForce 310M]        | 26    | nouveau    | 15789D122D |
| 8086:0046 | 17aa:3957 | Intel      | Core Processor Integrated... | 26    | i915       | 15789D122D |
| 8086:0f31 | 103c:2213 | Intel      | Atom Processor Z36xxx/Z37... | 26    | i915       | 8DF8DAD46F |
| 8086:0f31 | 1043:161d | Intel      | Atom Processor Z36xxx/Z37... | 26    | i915       | 7BE60A0A2C |
| 8086:2a02 | 1028:01f9 | Intel      | Mobile GM965/GL960 Integr... | 26    | i915       | 4908DA86B8 |
| 8086:2a03 | 1028:01f9 | Intel      | Mobile GM965/GL960 Integr... | 26    |            | 4908DA86B8 |
| 8086:2a42 | 144d:c06d | Intel      | Mobile 4 Series Chipset I... | 26    | i915       | 72819F11A2 |
| 8086:2a43 | 144d:c06d | Intel      | Mobile 4 Series Chipset I... | 26    |            | 72819F11A2 |
| 10de:1055 | 104d:908b | Nvidia     | GF119M [GeForce 410M]        | 25    | nouveau    | 5B1ADBE8F0 |
| 10de:1140 | 17aa:5003 | Nvidia     | GF117M [GeForce 610M/710M... | 25    | nouveau    | 1C3C62EC29 |
| 8086:0116 | 1043:15f2 | Intel      | 2nd Generation Core Proce... | 25    | i915       | 47A635ACC1 |
| 8086:0126 | 17aa:21da | Intel      | 2nd Generation Core Proce... | 25    | i915       | DA7FEA9DD2 |
| 8086:0166 | 17aa:21f5 | Intel      | 3rd Gen Core processor Gr... | 25    | i915       | 1949413DC7 |
| 8086:0416 | 17aa:3978 | Intel      | 4th Gen Core Processor In... | 25    | i915       | 239616AC43 |
| 1002:15dd | 103c:84ae | AMD        | Raven Ridge [Radeon Vega ... | 24    | amdgpu     | 3B491B92B3 |
| 1002:68e4 | 1043:1c92 | AMD        | Robson CE [Radeon HD 6370... | 24    | radeon     | 1016010629 |
| 1002:718a | 1043:1449 | AMD        | RV516/M64 [Mobility Radeo... | 24    | radeon     | 4841CD6D3C |
| 10de:0fdf | 1043:1587 | Nvidia     | GK107M [GeForce GT 740M]     | 24    | nouveau    | A14ECCA066 |
| 10de:1140 | 1043:223a | Nvidia     | GF117M [GeForce 610M/710M... | 24    | nouveau    | 3C131AF038 |
| 8086:0166 | 106b:00fa | Intel      | 3rd Gen Core processor Gr... | 24    | i915       | 0F16F5186B |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 102   |            | C65ABD0640 |
| 1022:1577 | 103c:8330 | AMD        | Family 15h (Models 60h-6f... | 47    |            | E26638D750 |
| 1022:1577 | 1025:1192 | AMD        | Family 15h (Models 60h-6f... | 37    |            | 17E62D31B9 |
| 1022:15d1 | 103c:84ae | AMD        | Raven/Raven2 IOMMU           | 24    |            | 3B491B92B3 |
| 1022:1577 | 103c:84ac | AMD        | Family 15h (Models 60h-6f... | 18    |            | 6EEF4CAED6 |
| 1022:15d1 | 17aa:3804 | AMD        | Raven/Raven2 IOMMU           | 11    |            | 6206EB1A2F |
| 1022:1577 | 17aa:380e | AMD        | Family 15h (Models 60h-6f... | 10    |            | F9C34FA042 |
| 1022:15d1 | 103c:84e7 | AMD        | Raven/Raven2 IOMMU           | 8     |            | EA1E118AD6 |
| 1022:15d1 | 1025:125c | AMD        | Raven/Raven2 IOMMU           | 7     |            | B9A37AB909 |
| 1022:15d1 | 17aa:380a | AMD        | Raven/Raven2 IOMMU           | 7     |            | B49AAC1247 |
| 1022:1577 | 1025:109f | AMD        | Family 15h (Models 60h-6f... | 6     |            | A2C937F34C |
| 1022:1577 | 103c:8333 | AMD        | Family 15h (Models 60h-6f... | 6     |            | C4B7195697 |
| 1022:15d1 | 103c:85ea | AMD        | Raven/Raven2 IOMMU           | 6     |            | 4250651580 |
| 1022:1577 | 1028:087e | AMD        | Family 15h (Models 60h-6f... | 5     |            | D72F217DE7 |
| 1022:1577 | 103c:84a0 | AMD        | Family 15h (Models 60h-6f... | 5     |            | B34D6AAB90 |
| 1022:15d1 | 1028:0812 | AMD        | Raven/Raven2 IOMMU           | 5     |            | 90C3D47F26 |
| 1022:15d1 | 103c:84d2 | AMD        | Raven/Raven2 IOMMU           | 5     |            | DFC4334B0C |
| 1022:1577 | 1025:1087 | AMD        | Family 15h (Models 60h-6f... | 4     |            | D5082D8C3F |
| 1022:1577 | 1028:0769 | AMD        | Family 15h (Models 60h-6f... | 4     |            | 5F8E475ACD |
| 1022:1577 | 103c:81f9 | AMD        | Family 15h (Models 60h-6f... | 4     |            | 832AAFEB1A |
| 1022:1577 | 103c:81fe | AMD        | Family 15h (Models 60h-6f... | 4     |            | B0EAB1E9FE |
| 1022:1577 | 103c:8345 | AMD        | Family 15h (Models 60h-6f... | 4     |            | 7E3B6FA95F |
| 1022:1577 | 103c:84ad | AMD        | Family 15h (Models 60h-6f... | 4     |            | 666B6342E0 |
| 1022:15d1 | 1025:134d | AMD        | Raven/Raven2 IOMMU           | 4     |            | 96D84C0576 |
| 1022:15d1 | 17aa:3809 | AMD        | Raven/Raven2 IOMMU           | 4     |            | 98794ACEB7 |
| 1022:1577 | 1025:1099 | AMD        | Family 15h (Models 60h-6f... | 3     |            | E8EBAD3A57 |
| 1022:1577 | 1025:1201 | AMD        | Family 15h (Models 60h-6f... | 3     |            | 15574B1FE0 |
| 1022:1577 | 103c:8324 | AMD        | Family 15h (Models 60h-6f... | 3     |            | 47B10CD4F1 |
| 1022:15d1 | 1025:1259 | AMD        | Raven/Raven2 IOMMU           | 3     |            | 32C519104F |
| 1022:1577 | 1028:076b | AMD        | Family 15h (Models 60h-6f... | 2     |            | C9DF0EF9CD |
| 1022:1577 | 103c:80af | AMD        | Family 15h (Models 60h-6f... | 2     |            | 56448591A2 |
| 1022:1577 | 103c:80b0 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 0FB5C5CC88 |
| 1022:1577 | 103c:8346 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 0E99848A09 |
| 1022:1577 | 103c:84d0 | AMD        | Family 15h (Models 60h-6f... | 2     |            | A2D9BA544F |
| 1022:1577 | 103c:84d1 | AMD        | Family 15h (Models 60h-6f... | 2     |            | E3FF835EA0 |
| 1022:1577 | 103c:84e5 | AMD        | Family 15h (Models 60h-6f... | 2     |            | CE87F391CE |
| 1022:1577 | 103c:85bb | AMD        | Family 15h (Models 60h-6f... | 2     |            | 623C96EC6E |
| 1022:15d1 | 1025:1233 | AMD        | Raven/Raven2 IOMMU           | 2     |            | 0CD9D87E92 |
| 1022:15d1 | 1025:134f | AMD        | Raven/Raven2 IOMMU           | 2     |            | 1DE476E789 |
| 1022:15d1 | 1028:08d7 | AMD        | Raven/Raven2 IOMMU           | 2     |            | 2B2912B5B0 |
| 1022:15d1 | 103c:84a2 | AMD        | Raven/Raven2 IOMMU           | 2     |            | 3A1243A77F |
| 1022:15d1 | 103c:85e0 | AMD        | Raven/Raven2 IOMMU           | 2     |            | AD06D7DFA7 |
| 1022:15d1 | 103c:8615 | AMD        | Raven/Raven2 IOMMU           | 2     |            | 6EB4516C09 |
| 1022:15d1 | 17aa:380b | AMD        | Raven/Raven2 IOMMU           | 2     |            | 153F2AFA98 |
| 1022:1423 | 103c:2263 | AMD        | Family 15h (Models 30h-3f... | 1     |            | A07F8E8315 |
| 1022:1423 | 103c:22a9 | AMD        | Family 15h (Models 30h-3f... | 1     |            | FE059A167E |
| 1022:1577 | 1025:095e | AMD        | Family 15h (Models 60h-6f... | 1     |            | 5C4BD87BC9 |
| 1022:1577 | 1025:1372 | AMD        | Family 15h (Models 60h-6f... | 1     |            | F7313E11F8 |
| 1022:1577 | 103c:81fd | AMD        | Family 15h (Models 60h-6f... | 1     |            | 7C0F244462 |
| 1022:1577 | 103c:8221 | AMD        | Family 15h (Models 60h-6f... | 1     |            | 99CFD11CA2 |
| 1022:1577 | 103c:8353 | AMD        | Family 15h (Models 60h-6f... | 1     |            | BB4FD376C4 |
| 1022:1577 | 103c:8354 | AMD        | Family 15h (Models 60h-6f... | 1     |            | C75D45BEC4 |
| 1022:1577 | 103c:8357 | AMD        | Family 15h (Models 60h-6f... | 1     |            | F017BDEDF1 |
| 1022:1577 | 103c:863c | AMD        | Family 15h (Models 60h-6f... | 1     |            | AA23459104 |
| 1022:1577 | 17aa:380d | AMD        | Family 15h (Models 60h-6f... | 1     |            | E0F719AEB9 |
| 1022:15d1 | 103c:84a3 | AMD        | Raven/Raven2 IOMMU           | 1     |            | 6A706DA421 |
| 1022:15d1 | 103c:84af | AMD        | Raven/Raven2 IOMMU           | 1     |            | 2D5F51CDD8 |
| 1022:15d1 | 103c:85b3 | AMD        | Raven/Raven2 IOMMU           | 1     |            | 766B0474A3 |
| 1022:15d1 | 17aa:3802 | AMD        | Raven/Raven2 IOMMU           | 1     |            | 0A0728CD41 |
| 1022:15d1 | 17aa:3803 | AMD        | Raven/Raven2 IOMMU           | 1     |            | 1697395761 |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816c | 17aa:5125 | Realtek... | Virtual IPMI                 | 3     |            | E97740F470 |
| 10ec:816c | 17aa:5122 | Realtek... | Virtual IPMI                 | 2     |            | 971B99D081 |
| 10ec:816c | 17aa:5126 | Realtek... | Virtual IPMI                 | 2     |            | ADEC400398 |
| 10ec:816c | 103c:83d5 | Realtek... | Virtual IPMI                 | 1     |            | F648DD0082 |
| 10ec:816c | 103c:83da | Realtek... | Virtual IPMI                 | 1     |            | 607DEE6BBB |
| 10ec:816c | 103c:8401 | Realtek... | Virtual IPMI                 | 1     |            | F2F88AAA9D |
| 10ec:816c | 17aa:511f | Realtek... | Virtual IPMI                 | 1     |            | E0363562B7 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a36f | 8086:7270 | Intel      | Cannon Lake PCH Shared SRAM  | 103   |            | A47D005445 |
| 8086:9def | 8086:7270 | Intel      | Cannon Point-LP Shared SRAM  | 47    |            | 24F8864FB8 |
| 10de:0a88 |           | Nvidia     | MCP79 Memory Controller      | 41    |            | 441575D073 |
| 10de:0a88 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 40    |            | F5C8A70507 |
| 10de:0a89 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 40    |            | F5C8A70507 |
| 10de:0a89 |           | Nvidia     | MCP79 Memory Controller      | 34    |            | 441575D073 |
| 10de:0aa4 |           | Nvidia     | MCP79 Memory Controller      | 34    |            | 441575D073 |
| 8086:9d21 | 17aa:3872 | Intel      | Sunrise Point-LP PMC         | 33    |            | 91D8C5CEC3 |
| 10de:0a98 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 31    |            | 441575D073 |
| 8086:9d21 | 1025:1193 | Intel      | Sunrise Point-LP PMC         | 31    | intel_p... | 02EEEC88C4 |
| 8086:9d21 | 1025:1085 | Intel      | Sunrise Point-LP PMC         | 29    | intel_p... | 8BC74BD7FB |
| 8086:9d21 | 1025:115f | Intel      | Sunrise Point-LP PMC         | 27    | intel_p... | A230640EC7 |
| 8086:9d21 | 103c:832a | Intel      | Sunrise Point-LP PMC         | 26    |            | 931D7104FA |
| 8086:9d21 | 8086:7270 | Intel      | Sunrise Point-LP PMC         | 25    |            | 87D31F3F80 |
| 8086:a36f | 1025:1264 | Intel      | Cannon Lake PCH Shared SRAM  | 24    |            | AF51F8907E |
| 8086:a36f | 1028:087c | Intel      | Cannon Lake PCH Shared SRAM  | 24    |            | 18DC19F3EC |
| 10de:0568 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] Mem... | 23    |            | D672B4583E |
| 10de:0754 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] Mem... | 23    |            | D672B4583E |
| 8086:9d21 | 103c:8079 | Intel      | Sunrise Point-LP PMC         | 23    |            | BCF0EBFEDD |
| 8086:9def |           | Intel      | Cannon Point-LP Shared SRAM  | 23    |            | BA2DACFEFB |
| 10de:0541 | 10de:cb84 | Nvidia     | MCP67 Memory Controller      | 22    |            | 590A68AE68 |
| 8086:9d21 | 1043:1a00 | Intel      | Sunrise Point-LP PMC         | 22    | intel_p... | 8C29A78852 |
| 10de:0547 | 1025:0126 | Nvidia     | MCP67 Memory Controller      | 20    |            | 590A68AE68 |
| 8086:9d21 | 17aa:3816 | Intel      | Sunrise Point-LP PMC         | 20    |            | 3493C4EBA1 |
| 8086:9d21 | 17aa:5068 | Intel      | Sunrise Point-LP PMC         | 20    |            | F4826C3A2A |
| 8086:9d21 | 1028:07e6 | Intel      | Sunrise Point-LP PMC         | 19    | intel_p... | C26F2A8CCF |
| 8086:9def | 1028:08af | Intel      | Cannon Point-LP Shared SRAM  | 19    |            | ED8598DB62 |
| 10de:0aa4 | 1043:1cf7 | Nvidia     | MCP79 Memory Controller      | 18    |            | F0A1399A3F |
| 10de:0d68 |           | Nvidia     | MCP89 Memory Controller      | 17    |            | 303C043B8B |
| 10de:0d69 |           | Nvidia     | MCP89 Memory Controller      | 17    |            | 303C043B8B |
| 10de:0d6d |           | Nvidia     | MCP89 Memory Controller      | 17    |            | 303C043B8B |
| 10de:0d6e |           | Nvidia     | MCP89 Memory Controller      | 17    |            | 303C043B8B |
| 10de:0d6f |           | Nvidia     | MCP89 Memory Controller      | 17    |            | 303C043B8B |
| 10de:0d70 |           | Nvidia     | MCP89 Memory Controller      | 17    |            | 303C043B8B |
| 10de:0d71 |           | Nvidia     | MCP89 Memory Controller      | 17    |            | 303C043B8B |
| 10de:0d72 |           | Nvidia     | MCP89 Memory Controller      | 17    |            | 303C043B8B |
| 10de:0d75 |           | Nvidia     | MCP89 Memory Controller      | 17    |            | 303C043B8B |
| 10de:0d7b |           | Nvidia     | MCP89 Memory Controller      | 17    |            | 303C043B8B |
| 8086:444e | 8086:444e | Intel      | Turbo Memory Controller      | 17    |            | 514C92A80A |
| 8086:9d21 | 103c:84a6 | Intel      | Sunrise Point-LP PMC         | 17    | intel_p... | 56A3768905 |
| 8086:9d21 | 17aa:3845 | Intel      | Sunrise Point-LP PMC         | 17    |            | AD1F14D1A1 |
| 8086:9d21 | 8086:9d21 | Intel      | Sunrise Point-LP PMC         | 17    |            | A43311F999 |
| 8086:a121 | 17aa:3802 | Intel      | 100 Series/C230 Series Ch... | 17    |            | B57E5735A5 |
| 8086:a36f | 1028:087d | Intel      | Cannon Lake PCH Shared SRAM  | 17    |            | 5741F67096 |
| 10de:0547 | 103c:30cf | Nvidia     | MCP67 Memory Controller      | 16    |            | 1031D661DB |
| 8086:9d21 | 1028:0810 | Intel      | Sunrise Point-LP PMC         | 16    |            | 5CD9AAC635 |
| 8086:9d21 | 17aa:225d | Intel      | Sunrise Point-LP PMC         | 16    |            | BE40A37EA8 |
| 8086:a121 | 1028:07be | Intel      | 100 Series/C230 Series Ch... | 16    |            | 9BF3CB8563 |
| 8086:9d21 | 1025:121e | Intel      | Sunrise Point-LP PMC         | 15    | intel_p... | E1D731F58D |
| 8086:9d21 | 17aa:3851 | Intel      | Sunrise Point-LP PMC         | 15    |            | 187A7265F0 |
| 10de:0aa4 | 1043:1fa7 | Nvidia     | MCP79 Memory Controller      | 14    |            | F5C8A70507 |
| 8086:9d21 | 1028:06b2 | Intel      | Sunrise Point-LP PMC         | 14    |            | 32D65CC437 |
| 8086:9d21 | 1028:0767 | Intel      | Sunrise Point-LP PMC         | 14    |            | 68B91906DC |
| 8086:9d21 | 1028:078b | Intel      | Sunrise Point-LP PMC         | 14    |            | EEF040BA40 |
| 8086:9d21 | 103c:8328 | Intel      | Sunrise Point-LP PMC         | 14    |            | D59CC110FE |
| 8086:9d21 | 1043:12d1 | Intel      | Sunrise Point-LP PMC         | 14    | intel_p... | D7F1320909 |
| 8086:9d21 | 17aa:3844 | Intel      | Sunrise Point-LP PMC         | 14    |            | 74837A3467 |
| 8086:9d21 | 1d72:1701 | Intel      | Sunrise Point-LP PMC         | 14    | intel_p... | 4DCFEFF869 |
| 8086:9def | 17aa:2279 | Intel      | Cannon Point-LP Shared SRAM  | 14    |            | F737A5A121 |
| 8086:a121 | 1025:118a | Intel      | 100 Series/C230 Series Ch... | 14    |            | AA93BE82FD |
| 10de:027e |           | Nvidia     | C51 Memory Controller 2      | 13    |            | 71764E2EB9 |
| 10de:0541 | 103c:30cf | Nvidia     | MCP67 Memory Controller      | 13    |            | 1031D661DB |
| 8086:9d21 | 103c:832b | Intel      | Sunrise Point-LP PMC         | 13    |            | 95572C5A05 |
| 8086:9d21 | 17aa:2245 | Intel      | Sunrise Point-LP PMC         | 13    | intel_p... | 9F5951C997 |
| 8086:9d21 | 17aa:225c | Intel      | Sunrise Point-LP PMC         | 13    |            | A4567A345B |
| 8086:9d21 | 17aa:3808 | Intel      | Sunrise Point-LP PMC         | 13    |            | B82C81826B |
| 8086:a121 | 1028:0706 | Intel      | 100 Series/C230 Series Ch... | 13    |            | 556DD6ED0B |
| 8086:a121 | 1043:15e0 | Intel      | 100 Series/C230 Series Ch... | 13    |            | 6421A501F4 |
| 8086:9d21 | 1028:083f | Intel      | Sunrise Point-LP PMC         | 12    |            | CA85CB68A2 |
| 8086:9d21 | 1043:1d30 | Intel      | Sunrise Point-LP PMC         | 12    | intel_p... | C8302947A4 |
| 8086:9d21 | 17aa:3869 | Intel      | Sunrise Point-LP PMC         | 12    |            | 442F0D1A5A |
| 8086:9d21 | 17aa:505b | Intel      | Sunrise Point-LP PMC         | 12    |            | 78818887EE |
| 8086:9d21 | 1025:100c | Intel      | Sunrise Point-LP PMC         | 11    |            | B9139A5B72 |
| 8086:9d21 | 1025:1295 | Intel      | Sunrise Point-LP PMC         | 11    |            | CE1098A7F5 |
| 8086:9d21 | 1028:0704 | Intel      | Sunrise Point-LP PMC         | 11    | intel_p... | 4D3C815F1C |
| 8086:9d21 | 1028:075b | Intel      | Sunrise Point-LP PMC         | 11    |            | 6345D39841 |
| 8086:9d21 | 1028:082a | Intel      | Sunrise Point-LP PMC         | 11    | intel_p... | A767963691 |
| 8086:9d21 | 103c:8101 | Intel      | Sunrise Point-LP PMC         | 11    |            | A0ACA3E800 |
| 8086:9d21 | 103c:81ec | Intel      | Sunrise Point-LP PMC         | 11    | intel_p... | 9F62C51A20 |
| 8086:9d21 | 103c:83b2 | Intel      | Sunrise Point-LP PMC         | 11    |            | 65B1EB0CA1 |
| 8086:9d21 | 1043:1670 | Intel      | Sunrise Point-LP PMC         | 11    | intel_p... | 060179220F |
| 8086:9d21 | 17aa:2233 | Intel      | Sunrise Point-LP PMC         | 11    |            | 3A4AD5E700 |
| 8086:9d21 | 19e5:3e04 | Intel      | Sunrise Point-LP PMC         | 11    |            | 61DE3D6439 |
| 8086:a36f | 17aa:3801 | Intel      | Cannon Lake PCH Shared SRAM  | 11    |            | DA4DF48AE5 |
| 8086:9d21 | 1028:081c | Intel      | Sunrise Point-LP PMC         | 10    |            | B4899BA50A |
| 8086:9d21 | 103c:837d | Intel      | Sunrise Point-LP PMC         | 10    | intel_p... | 9441C13CE5 |
| 8086:9d21 | 1043:1490 | Intel      | Sunrise Point-LP PMC         | 10    |            | ACF44DF993 |
| 8086:9def | 103c:8549 | Intel      | Cannon Point-LP Shared SRAM  | 10    |            | 0B8C8AB6F3 |
| 8086:9def | 17aa:3809 | Intel      | Cannon Point-LP Shared SRAM  | 10    |            | 0886AD75BB |
| 8086:a121 | 1462:11c8 | Intel      | 100 Series/C230 Series Ch... | 10    |            | B8AA5EF26C |
| 8086:a121 | 17aa:3819 | Intel      | 100 Series/C230 Series Ch... | 10    |            | C7B13E4BA2 |
| 8086:a36f | 1028:086f | Intel      | Cannon Lake PCH Shared SRAM  | 10    |            | C4FE97CCA2 |
| 10de:0a88 | 1043:8402 | Nvidia     | MCP79 Memory Controller      | 9     |            | F47A1D4306 |
| 10de:0a89 | 1043:8402 | Nvidia     | MCP79 Memory Controller      | 9     |            | F47A1D4306 |
| 10de:0aa4 | 1043:8402 | Nvidia     | MCP79 Memory Controller      | 9     |            | F47A1D4306 |
| 8086:9d21 | 1025:1191 | Intel      | Sunrise Point-LP PMC         | 9     |            | 0B7890A8FC |
| 8086:9d21 | 1028:06de | Intel      | Sunrise Point-LP PMC         | 9     |            | CF0F03C40A |
| 8086:9d21 | 17aa:225a | Intel      | Sunrise Point-LP PMC         | 9     | intel_p... | CABDFDF87F |
| 8086:9d21 | 17aa:3815 | Intel      | Sunrise Point-LP PMC         | 9     |            | DD8DE8C9A2 |
| 8086:9d21 | 17aa:3857 | Intel      | Sunrise Point-LP PMC         | 9     |            | F7054F16AE |

### Modem (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:266d | 14f1:5423 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 13    | snd_int... | 18E748759E |
| 8086:24c6 | 14f1:5422 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 10    | snd_int... | 4EBB330BF9 |
| 8086:266d | 1179:0001 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 10    | snd_int... | 8488B3D0B9 |
| 8086:266d | 1025:006a | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 7     | snd_int... | 77353D6C03 |
| 8086:266d | 103c:099c | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 6     | snd_int... | E0DF895DC8 |
| 8086:266d | 1014:0574 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 5     | snd_int... | BABCA7BCDE |
| 8086:266d | 1025:0066 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 5     | snd_int... | 50122B9E8E |
| 1002:434d | 144d:2115 | AMD        | SB200 AC97 Modem Controller  | 3     | snd_ati... | 80073ED5E9 |
| 1002:4378 | 103c:30a4 | AMD        | IXP SB400 AC'97 Modem Con... | 3     | snd_ati... | CCEED80795 |
| 1002:4378 | 1043:1186 | AMD        | IXP SB400 AC'97 Modem Con... | 3     | snd_ati... | 08E7796666 |
| 1039:7013 | 1025:0083 | Silicon... | AC'97 Modem Controller       | 3     |            | 94017E086A |
| 1039:7013 | 1043:1816 | Silicon... | AC'97 Modem Controller       | 3     | snd_int... | C4EBB5D061 |
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
| 1039:7013 | 104d:814e | Silicon... | AC'97 Modem Controller       | 1     | snd_int... | 88ABDEBE09 |
| 10b9:5457 | 103c:0850 | ULi Ele... | M5457 AC'97 Modem Controller | 1     |            | 4E9D284D9C |
| 10b9:5457 | 104d:8158 | ULi Ele... | M5457 AC'97 Modem Controller | 1     |            | 2BA72A0486 |
| 10de:00d9 | 103c:006d | Nvidia     | nForce3 Audio                | 1     |            | E1BAA5BDE6 |
| 10de:00d9 | 1043:1856 | Nvidia     | nForce3 Audio                | 1     | snd_int... | 655ACF5FA6 |
| 1106:3068 | 1025:0046 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 80E120B3A5 |
| 1106:3068 | 1071:8666 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 179169EE59 |
| 1106:3068 | 1071:8889 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | E801E7B52C |
| 1106:3068 | 1734:1054 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | A9DE326D18 |
| 1106:3068 | 1734:10ab | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | BEA6F4F694 |
| 1106:3068 | 1734:10ae | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 06ECBD156A |
| 11c1:045c | 8086:2205 | LSI        | LT WinModem                  | 1     | serial     | 1B54E25E77 |
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
| 8086:266d | 14ff:1013 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     | snd_int... | B6BA04DCE2 |
| 8086:266d | 17aa:207c | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     |            | EDAE63A429 |
| 8086:266d | 17c0:10bb | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     | snd_int... | 0808A2772F |

### Multimedia (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0f38 |           | Intel      | Atom Processor Z36xxx/Z37... | 1     |            | C4198C729C |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 103   | intel_a... | AE477CA654 |
| 14e4:1570 | 14e4:1570 | Broadco... | 720p FaceTime HD Camera      | 42    | bdc_pci    | 1A26D7B485 |
| 1022:15e2 | 103c:84ae | AMD        | Raven/Raven2/FireFlight/R... | 24    | snd_pci... | 3B491B92B3 |
| 1022:15e2 | 1022:15e2 | AMD        | Raven/Raven2/FireFlight/R... | 21    | snd_pci... | 9809687258 |
| 8086:5a88 |           | Intel      | Celeron N3350/Pentium N42... | 13    |            | 2CBA62F744 |
| 8086:22b8 | 1297:2063 | Intel      | Atom/Celeron/Pentium Proc... | 10    | intel_a... | EBFA71DD99 |
| 1022:15e2 | 17aa:3812 | AMD        | Raven/Raven2/FireFlight/R... | 7     | snd_pci... | B49AAC1247 |
| 1022:15e2 | 103c:85ea | AMD        | Raven/Raven2/FireFlight/R... | 6     | snd_pci... | 4250651580 |
| 1022:15e2 | 17aa:3814 | AMD        | Raven/Raven2/FireFlight/R... | 6     | snd_pci... | C65ABD0640 |
| 14e4:1615 | 14e4:1615 | Broadco... | BCM70015 Video Decoder [C... | 6     |            | 9910E4B9BB |
| 8086:0f38 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 6     | intel_a... | 0994A3EEB3 |
| 1022:15e2 | 103c:84d2 | AMD        | Raven/Raven2/FireFlight/R... | 5     | snd_pci... | DFC4334B0C |
| 1022:15e2 | 19e5:3e06 | AMD        | Raven/Raven2/FireFlight/R... | 5     | snd_pci... | 85DF07509C |
| 8086:22b8 | 103c:813e | Intel      | Atom/Celeron/Pentium Proc... | 5     | intel_a... | 43F9ACD60A |
| 1022:15e2 | 1025:134d | AMD        | Raven/Raven2/FireFlight/R... | 4     | snd_pci... | 96D84C0576 |
| 1022:15e2 | 17aa:5124 | AMD        | Raven/Raven2/FireFlight/R... | 4     | snd_pci... | 883C27612D |
| 8086:0f38 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 4     | atomisp    | 362FB52DD0 |
| 1022:15e2 | 17aa:380b | AMD        | Raven/Raven2/FireFlight/R... | 3     |            | 102D5EFAD5 |
| 1022:15e2 | 17aa:5125 | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | E97740F470 |
| 1022:15e2 | 19e5:3e10 | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | 53631F5F96 |
| 14e4:1612 | 14e4:2612 | Broadcom   | BCM70012 Video Decoder [C... | 3     |            | 5495F2E86E |
| 8086:1919 | 8086:1919 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | ipu3_imgu  | 12B475E9FD |
| 8086:1919 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | ipu3_imgu  | A43311F999 |
| 8086:9d32 | 8086:9d32 | Intel      | Skylake-U/Y Camera IO Hos... | 3     | ipu3_cio2  | 12B475E9FD |
| 1022:15e2 | 1025:1233 | AMD        | Raven/Raven2/FireFlight/R... | 2     | snd_pci... | 0CD9D87E92 |
| 1022:15e2 | 1025:134f | AMD        | Raven/Raven2/FireFlight/R... | 2     | snd_pci... | 1DE476E789 |
| 1022:15e2 | 103c:84a2 | AMD        | Raven/Raven2/FireFlight/R... | 2     | snd_pci... | 3A1243A77F |
| 1022:15e2 | 17aa:3813 | AMD        | Raven/Raven2/FireFlight/R... | 2     | snd_pci... | 153F2AFA98 |
| 1022:15e2 | 17aa:5126 | AMD        | Raven/Raven2/FireFlight/R... | 2     | snd_pci... | ADEC400398 |
| 1131:7160 | 1461:0555 | Philips... | SAA7160                      | 2     |            | D400943350 |
| 1131:7160 | 1461:0a55 | Philips... | SAA7160                      | 2     |            | 99DDBBF195 |
| 1131:7231 | 12ab:0762 | Philips... | SAA7231                      | 2     |            | 6DFEC77A25 |
| 1131:7231 | 1461:0b0f | Philips... | SAA7231                      | 2     |            | 791CA50070 |
| 8086:22b8 | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 2     | intel_a... | 4CCE625762 |
| 8086:22b8 | 1043:1bdd | Intel      | Atom/Celeron/Pentium Proc... | 2     | intel_a... | 40D8D33EF9 |
| 1022:15e2 | 103c:84a3 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | 6A706DA421 |
| 1022:15e2 | 103c:84af | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | 2D5F51CDD8 |
| 1022:15e2 | 103c:85b3 | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | 766B0474A3 |
| 1022:15e2 | 103c:85e0 | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | CA237442E2 |
| 1022:15e2 | 17aa:3811 | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | 0A0728CD41 |
| 10cf:202a | 104d:81fa | Fujitsu... | Integrated MPEG Encoder      | 1     |            | 7F0BB0CC92 |
| 1131:7160 | 1461:1055 | Philips... | SAA7160                      | 1     |            | 9E921922BA |
| 1131:7160 | 1461:2355 | Philips... | SAA7160                      | 1     |            | B98B8362E0 |
| 1131:7160 | 16be:0034 | Philips... | SAA7160                      | 1     |            | 2B8D93B7EC |
| 1131:7231 | 1461:110f | Philips... | SAA7231                      | 1     |            | 90DFBFB6FA |
| 1131:7231 | 1461:3301 | Philips... | SAA7231                      | 1     |            | 7E1176A7C2 |
| 8086:1919 | 1028:07a5 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     |            | 87A44EF029 |
| 8086:1919 | 17aa:2241 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     |            | 1038A34C39 |
| 8086:1919 | 17aa:3812 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     |            | 57EC66B289 |
| 8086:22b8 | 1025:1021 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 663247803F |
| 8086:22b8 | 1025:106e | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 425D589D65 |
| 8086:22b8 | 1025:113a | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | FBF9B74A34 |
| 8086:22b8 | 1028:06ea | Intel      | Atom/Celeron/Pentium Proc... | 1     | intel_a... | 721C1A7DC3 |
| 8086:22b8 | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | C508886F10 |
| 8086:22b8 | 1071:a126 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | F2981C1775 |
| 8086:9d32 | 1028:07a5 | Intel      | Skylake-U/Y Camera IO Hos... | 1     |            | 87A44EF029 |
| 8086:9d32 | 17aa:2241 | Intel      | Skylake-U/Y Camera IO Hos... | 1     | ipu3_cio2  | 1038A34C39 |
| 8086:9d32 | 17aa:3812 | Intel      | Skylake-U/Y Camera IO Hos... | 1     | ipu3_cio2  | 57EC66B289 |
| 8086:9d32 | 8086:7270 | Intel      | Skylake-U/Y Camera IO Hos... | 1     | ipu3_cio2  | 192FBE0755 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8168 | 1043:200f | Realtek... | RTL8111/8168/8411 PCI Exp... | 563   | r8169      | 179397B4EA |
| 10ec:8136 | 1043:200f | Realtek... | RTL810xE PCI Express Fast... | 244   | r8169      | 6D7501C42A |
| 14e4:16b5 | 1025:0647 | Broadco... | NetLink BCM57785 Gigabit ... | 234   | tg3        | 9084C70732 |
| 10ec:8168 | 1043:16d5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 152   | r8169      | 55153BEE1A |
| 1969:2062 | 1043:8468 | Attansi... | AR8152 v2.0 Fast Ethernet    | 146   | atl1c      | A6B1293F94 |
| 10ec:8168 | 17aa:5002 | Realtek... | RTL8111/8168/8411 PCI Exp... | 123   | r8169      | 82A9861AFD |
| 197b:0250 | 1043:1905 | JMicron... | JMC250 PCI Express Gigabi... | 121   | jme        | 088FFC2823 |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 111   | r8169      | EBB7E1B084 |
| 1969:1083 | 1043:1851 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 109   | atl1c      | AF47B62F54 |
| 14e4:16b5 | 1025:0504 | Broadco... | NetLink BCM57785 Gigabit ... | 104   | tg3        | 832F6EF100 |
| 1969:2062 | 17aa:3979 | Qualcom... | AR8152 v2.0 Fast Ethernet    | 94    | atl1c      | B6EF514918 |
| 14e4:1692 | 1025:036d | Broadco... | NetLink BCM57780 Gigabit ... | 90    | tg3        | B99A6015C7 |
| 14e4:1693 | 1025:011c | Broadco... | NetLink BCM5787M Gigabit ... | 88    | tg3        | BA9EFF4F3B |
| 1969:1090 | 17aa:3979 | Qualcom... | AR8162 Fast Ethernet         | 85    | alx        | CE8329CC49 |
| 10ec:8136 | 17aa:3975 | Realtek... | RTL810xE PCI Express Fast... | 70    | r8169      | 47BBFE4D38 |
| 1969:1063 | 1043:1820 | Qualcom... | AR8131 Gigabit Ethernet      | 68    | atl1c      | BA1E7F648C |
| 10ec:8168 | 1043:1277 | Realtek... | RTL8111/8168/8411 PCI Exp... | 67    | r8169      | 47A635ACC1 |
| 10ec:8168 | 17aa:3812 | Realtek... | RTL8111/8168/8411 PCI Exp... | 66    | r8169      | 363B08984A |
| 1969:1062 | 1043:838a | Qualcom... | AR8132 Fast Ethernet         | 65    | atl1c      | E368A28816 |
| 10ec:8168 | 1b0a:20d9 | Realtek... | RTL8111/8168/8411 PCI Exp... | 63    | r8169      | 5711F7E7F3 |
| 10ec:8136 | 10ec:0123 | Realtek... | RTL810xE PCI Express Fast... | 62    | r8169      | 7BE60A0A2C |
| 10ec:8168 | 1043:11f5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 62    | r8169      | 427546EA21 |
| 10ec:8136 | 1179:ff00 | Realtek... | RTL810xE PCI Express Fast... | 61    | r8169      | 18FA01EC6B |
| 10ec:8168 | 17aa:3816 | Realtek... | RTL8111/8168/8411 PCI Exp... | 59    | r8169      | F2797B8B83 |
| 14e4:16b3 | 1025:0775 | Broadco... | NetXtreme BCM57786 Gigabi... | 58    | tg3        | 94CD691A35 |
| 1969:1026 | 1043:14f5 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 57    | atl1e      | 33E615851D |
| 11ab:4381 | 104d:9071 | Marvell... | Yukon Optima 88E8059 [PCI... | 56    | sky2       | 90D3759348 |
| 1969:10a0 | 17aa:3802 | Qualcom... | QCA8172 Fast Ethernet        | 56    | alx        | 8CE0C08E9A |
| 10ec:8168 | 144d:c0da | Realtek... | RTL8111/8168/8411 PCI Exp... | 55    | r8169      | C5694CCAC0 |
| 10ec:8168 | 17aa:3975 | Realtek... | RTL8111/8168/8411 PCI Exp... | 55    | r8169      | 89EF922929 |
| 14e4:1698 | 1025:0207 | Broadco... | NetLink BCM5784M Gigabit ... | 54    | tg3        | 34DC7B3038 |
| 8086:155a | 17aa:2214 | Intel      | Ethernet Connection I218-LM  | 53    | e1000e     | 14015A6CDE |
| 14e4:1713 | 17aa:3a23 | Broadco... | NetLink BCM5906M Fast Eth... | 52    | tg3        | 5986AA0AAC |
| 1969:1083 | 1043:13c7 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 52    | atl1c      | 4DB132BB33 |
| 14e4:16b4 | 14e4:16b4 | Broadco... | NetXtreme BCM57765 Gigabi... | 50    | tg3        | 2B202B204B |
| 10ec:8168 | 144d:c606 | Realtek... | RTL8111/8168/8411 PCI Exp... | 48    | r8169      | 0BF9EE57AF |
| 14e4:1692 | 1025:033d | Broadco... | NetLink BCM57780 Gigabit ... | 48    | tg3        | D500F84DEB |
| 1969:1091 | 1043:14c7 | Qualcom... | AR8161 Gigabit Ethernet      | 48    | alx        | 12F5A59D53 |
| 10ec:8136 | 1028:04b0 | Realtek... | RTL810xE PCI Express Fast... | 47    | r8169      | DF459BC2B0 |
| 10ec:8136 | 10ec:8136 | Realtek... | RTL810xE PCI Express Fast... | 47    | r8169      | 1B0CB30A1E |
| 10ec:8136 | 17aa:392e | Realtek... | RTL810xE PCI Express Fast... | 47    | r8169      | FEAC85F7D7 |
| 10ec:8139 | 1043:1045 | Realtek... | RTL-8100/8101L/8139 PCI F... | 47    | 8139too... | 6C6A2138D2 |
| 10ec:8168 | 1025:0866 | Realtek... | RTL8111/8168/8411 PCI Exp... | 46    | r8169      | 3FD761163B |
| 10ec:8168 | 103c:8330 | Realtek... | RTL8111/8168/8411 PCI Exp... | 46    | r8169      | E26638D750 |
| 1969:1062 | 1025:0212 | Qualcom... | AR8132 Fast Ethernet         | 40    | atl1c      | CCC2EA91E1 |
| 10ec:8136 | 1179:fb37 | Realtek... | RTL810xE PCI Express Fast... | 39    | r8169      | C77563A5FB |
| 10ec:8168 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 39    | r8169      | 907647C4E8 |
| 1969:1090 | 17aa:3978 | Qualcom... | AR8162 Fast Ethernet         | 39    | alx        | 3DCE4D353B |
| 10ec:8136 | 17aa:3830 | Realtek... | RTL810xE PCI Express Fast... | 38    | r8169      | 7D85F9BFAB |
| 10ec:8168 | 144d:c0b6 | Realtek... | RTL8111/8168/8411 PCI Exp... | 38    | r8169      | 5118CD27DD |
| 10ec:8168 | 1025:1192 | Realtek... | RTL8111/8168/8411 PCI Exp... | 37    | r8169      | 17E62D31B9 |
| 10ec:8168 | 104d:908b | Realtek... | RTL8111/8168/8411 PCI Exp... | 37    | r8169      | A9E0A905BD |
| 10ec:8168 | 1043:104c | Realtek... | RTL8111/8168/8411 PCI Exp... | 36    | r8169      | AE90CAFD98 |
| 10ec:8168 | 144d:c652 | Realtek... | RTL8111/8168/8411 PCI Exp... | 36    | r8169      | 7F741A485F |
| 1969:1063 | 17aa:3956 | Qualcom... | AR8131 Gigabit Ethernet      | 36    | atl1c      | 15789D122D |
| 10ec:8168 | 1025:1094 | Realtek... | RTL8111/8168/8411 PCI Exp... | 35    | r8169      | A230640EC7 |
| 10ec:8168 | 1043:208f | Realtek... | RTL8111/8168/8411 PCI Exp... | 35    | r8169      | A47D005445 |
| 11ab:4354 | 144d:c06d | Marvell... | 88E8040 PCI-E Fast Ethern... | 35    | sky2       | 3A86D13DA1 |
| 1039:0191 | 1043:1815 | Silicon... | 191 Gigabit Ethernet Adapter | 34    | sis190     | 14EEC92B5D |
| 10ec:8136 | 1179:ff1e | Realtek... | RTL810xE PCI Express Fast... | 34    | r8169      | F49AB6DB04 |
| 10ec:8168 | 1043:1587 | Realtek... | RTL8111/8168/8411 PCI Exp... | 34    | r8169      | A14ECCA066 |
| 11ab:4354 | 144d:c072 | Marvell... | 88E8040 PCI-E Fast Ethern... | 34    | sky2       | 60127AB94A |
| 14e4:1673 | 1028:01f9 | Broadco... | NetXtreme BCM5755M Gigabi... | 34    | tg3        | 4908DA86B8 |
| 14e4:1684 | 1025:013c | Broadco... | NetXtreme BCM5764M Gigabi... | 34    | tg3        | A8E4D6D25F |
| 10ec:8136 | 1025:0590 | Realtek... | RTL810xE PCI Express Fast... | 33    | r8169      | 326A5F97CA |
| 10ec:8168 | 1025:1012 | Realtek... | RTL8111/8168/8411 PCI Exp... | 33    | r8169      | 0949108352 |
| 10ec:8168 | 17aa:38bb | Realtek... | RTL8111/8168/8411 PCI Exp... | 33    | r8169      | 91D8C5CEC3 |
| 1969:1062 | 1043:14e5 | Qualcom... | AR8132 Fast Ethernet         | 33    | atl1c      | 429A82D3C7 |
| 10ec:8136 | 103c:3577 | Realtek... | RTL810xE PCI Express Fast... | 32    | r8169      | 758C395C78 |
| 11ab:4354 | 144d:c07f | Marvell... | 88E8040 PCI-E Fast Ethern... | 32    | sky2       | A3F9F98355 |
| 1969:1091 | 1043:1477 | Qualcom... | AR8161 Gigabit Ethernet      | 32    | alx        | C005B421A9 |
| 10ec:8168 | 1025:1193 | Realtek... | RTL8111/8168/8411 PCI Exp... | 31    | r8169      | 02EEEC88C4 |
| 1969:1083 | 1025:0686 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 31    | atl1c      | 1F28286A78 |
| 1969:10a0 | 17aa:3806 | Qualcom... | QCA8172 Fast Ethernet        | 31    | alx        | 5F1837A6B4 |
| 1969:2060 | 1179:ff1e | Qualcom... | AR8152 v1.1 Fast Ethernet    | 31    | atl1c      | 984A530B85 |
| 10de:0ab0 | 10de:cb79 | Nvidia     | MCP79 Ethernet               | 30    | forcedeth  | 441575D073 |
| 10ec:8136 | 17aa:3861 | Realtek... | RTL810xE PCI Express Fast... | 30    | r8169      | 8B23CB3E69 |
| 10ec:8168 | 17aa:380a | Realtek... | RTL8111/8168/8411 PCI Exp... | 30    | r8169      | 9BBE2A2129 |
| 10ec:8136 | 103c:184a | Realtek... | RTL810xE PCI Express Fast... | 29    | r8169      | 4C72CE34FA |
| 10ec:8168 | 1025:1085 | Realtek... | RTL8111/8168/8411 PCI Exp... | 29    | r8169      | 8BC74BD7FB |
| 11ab:4354 | 1028:022f | Marvell... | 88E8040 PCI-E Fast Ethern... | 29    | sky2       | 56866B9E4C |
| 8086:15a2 | 17aa:2226 | Intel      | Ethernet Connection (3) I... | 29    | e1000e     | 71DE9234CB |
| 1969:1062 | 1025:0349 | Qualcom... | AR8132 Fast Ethernet         | 28    | atl1c      | A911172500 |
| 10ec:8168 | 144d:c581 | Realtek... | RTL8111/8168/8411 PCI Exp... | 27    | r8169      | D9ECE67AC1 |
| 10ec:8168 | 17aa:380b | Realtek... | RTL8111/8168/8411 PCI Exp... | 27    | r8169      | 972580DCF6 |
| 1969:10a0 | 17aa:3805 | Qualcom... | QCA8172 Fast Ethernet        | 27    | alx        | AAC48DC435 |
| 10ec:8136 | 103c:2213 | Realtek... | RTL810xE PCI Express Fast... | 26    | r8169      | 8DF8DAD46F |
| 10ec:8168 | 1025:098a | Realtek... | RTL8111/8168/8411 PCI Exp... | 26    | r8169      | 5861B2E713 |
| 10ec:8168 | 104d:90ab | Realtek... | RTL8111/8168/8411 PCI Exp... | 26    | r8169      | A8AF2E8A8D |
| 10ec:8168 | 10cf:175a | Realtek... | RTL8111/8168/8411 PCI Exp... | 26    | r8169      | 1676E72B8C |
| 10ec:8168 | 17aa:388a | Realtek... | RTL8111/8168/8411 PCI Exp... | 26    | r8169      | AD1F14D1A1 |
| 10ec:8136 | 1179:fd3c | Realtek... | RTL810xE PCI Express Fast... | 25    | r8169      | A36FC6A447 |
| 10ec:8136 | 144d:c059 | Realtek... | RTL810xE PCI Express Fast... | 25    | r8169      | 809DA0D1B4 |
| 10ec:8168 | 103c:1818 | Realtek... | RTL8111/8168/8411 PCI Exp... | 25    | r8169      | 6C34B57DD0 |
| 10ec:8168 | 103c:832a | Realtek... | RTL8111/8168/8411 PCI Exp... | 25    | r8169      | 931D7104FA |
| 10ec:8168 | 17aa:3854 | Realtek... | RTL8111/8168/8411 PCI Exp... | 25    | r8169      | 3493C4EBA1 |
| 10ec:8168 | 1025:1264 | Realtek... | RTL8111/8168/8411 PCI Exp... | 24    | r8169      | AF51F8907E |
| 10ec:8168 | 103c:3388 | Realtek... | RTL8111/8168/8411 PCI Exp... | 24    | r8169      | C7D96BB884 |
| 10ec:8168 | 17aa:3821 | Realtek... | RTL8111/8168/8411 PCI Exp... | 24    | r8169      | 81E6241D52 |
| 14e4:1713 | 1025:0136 | Broadco... | NetLink BCM5906M Fast Eth... | 24    | tg3        | EDE5F01079 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 168c:002b | 1a3b:1089 | Qualcom... | AR9285 Wireless Network A... | 467   | ath9k      | 088FFC2823 |
| 1814:3290 | 103c:18ec | Ralink     | RT3290 Wireless 802.11n 1... | 223   | rt2800pci  | 96C288C457 |
| 14e4:4365 | 17aa:0611 | Broadco... | BCM43142 802.11b/g/n         | 205   | wl         | 8CE0C08E9A |
| 168c:0032 | 1a3b:2c97 | Qualcom... | AR9485 Wireless Network A... | 205   | ath9k      | CE99670CEB |
| 8086:4222 | 8086:1001 | Intel      | PRO/Wireless 3945ABG [Gol... | 203   | iwl3945    | BA9EFF4F3B |
| 168c:0042 | 11ad:08a6 | Qualcom... | QCA9377 802.11ac Wireless... | 195   | ath10k_pci | CE1098A7F5 |
| 168c:002b | 105b:e035 | Qualcom... | AR9285 Wireless Network A... | 191   | ath9k      | D500F84DEB |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 189   | iwlwifi    | CCBB4BE6BB |
| 168c:002b | 17aa:30a1 | Qualcom... | AR9285 Wireless Network A... | 185   | ath9k      | 62C717C459 |
| 168c:002b | 1a3b:2c37 | Qualcom... | AR9285 Wireless Network A... | 180   | ath9k      | 55153BEE1A |
| 168c:0032 | 144d:4105 | Qualcom... | AR9485 Wireless Network A... | 171   | ath9k      | C5694CCAC0 |
| 168c:0034 | 105b:e052 | Qualcom... | AR9462 Wireless Network A... | 161   | ath9k      | 9084C70732 |
| 168c:0036 | 11ad:0642 | Qualcom... | QCA9565 / AR9565 Wireless... | 157   | ath9k      | 216DFBDCC6 |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 147   | iwlwifi    | 0AEADAFA2C |
| 8086:0896 | 8086:5005 | Intel      | Centrino Wireless-N 130      | 139   | iwlwifi    | 0BF9EE57AF |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 138   | iwlwifi    | D5082D8C3F |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 138   | iwlwifi    | 65B1EB0CA1 |
| 10ec:b723 | 17aa:b736 | Realtek... | RTL8723BE PCIe Wireless N... | 137   | rtl8723be  | 972580DCF6 |
| 14e4:4727 | 103c:1483 | Broadco... | BCM4313 802.11bgn Wireles... | 136   | wl         | 0C390ADEEF |
| 8086:a370 | 8086:0034 | Intel      | Wireless-AC 9560 [Jeffers... | 133   | iwlwifi    | A47D005445 |
| 168c:001c | 1a3b:1026 | Qualcom... | AR242x / AR542x Wireless ... | 129   | ath5k      | DF4FA2D486 |
| 168c:0032 | 11ad:6617 | Qualcom... | AR9485 Wireless Network A... | 117   | ath9k      | 39D47C0F09 |
| 8086:4232 | 8086:1201 | Intel      | WiFi Link 5100               | 117   | iwlwifi    | EF1BFF7353 |
| 168c:001c | 1468:0428 | Qualcom... | AR242x / AR542x Wireless ... | 115   | ath5k      | 005CF3D43E |
| 168c:0036 | 1028:020c | Qualcom... | QCA9565 / AR9565 Wireless... | 115   | ath9k      | A0554A7E66 |
| 8086:4237 | 8086:1211 | Intel      | PRO/Wireless 5100 AGN [Sh... | 114   | iwlwifi    | 01F5E9CD57 |
| 168c:002e | 105b:e034 | Qualcom... | AR9287 Wireless Network A... | 111   | ath9k      | 25D909CC38 |
| 14e4:4727 | 14e4:051b | Broadco... | BCM4313 802.11bgn Wireles... | 109   | wl         | 3DCE4D353B |
| 168c:002b | 105b:e025 | Qualcom... | AR9285 Wireless Network A... | 109   | ath9k      | 809DA0D1B4 |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 109   | iwlwifi    | D75C0B2DA5 |
| 168c:0032 | 103c:1785 | Qualcom... | AR9485 Wireless Network A... | 108   | ath9k      | 9C722B6763 |
| 8086:0887 | 8086:4062 | Intel      | Centrino Wireless-N 2230     | 108   | iwlwifi    | 18D138561D |
| 8086:08ae | 8086:1005 | Intel      | Centrino Wireless-N 100      | 108   | iwlwifi    | 47A635ACC1 |
| 168c:0036 | 1028:020e | Qualcom... | QCA9565 / AR9565 Wireless... | 107   | ath9k      | 5759D12C82 |
| 168c:0036 | 17aa:4026 | Qualcom... | QCA9565 / AR9565 Wireless... | 107   | ath9k      | 4D7E6E73B6 |
| 8086:4229 | 8086:1101 | Intel      | PRO/Wireless 4965 AG or A... | 107   | iwl4965    | D201D96AFE |
| 168c:0042 | 17aa:0901 | Qualcom... | QCA9377 802.11ac Wireless... | 103   | ath10k_pci | E0F719AEB9 |
| 10ec:b723 | 11ad:1723 | Realtek... | RTL8723BE PCIe Wireless N... | 99    | rtl8723be  | A14B78EF65 |
| 14e4:4727 | 103c:1795 | Broadco... | BCM4313 802.11bgn Wireles... | 95    | wl         | CD1743483A |
| 168c:0032 | 11ad:6627 | Qualcom... | AR9485 Wireless Network A... | 89    | ath9k      | 179397B4EA |
| 168c:0042 | 1028:1810 | Qualcom... | QCA9377 802.11ac Wireless... | 89    | ath10k_pci | 2B2912B5B0 |
| 8086:4232 | 8086:1206 | Intel      | WiFi Link 5100               | 87    | iwlwifi    | 363190383F |
| 168c:002b | 105b:e016 | Qualcom... | AR9285 Wireless Network A... | 86    | ath9k      | CEF0B9CE71 |
| 168c:0032 | 17aa:3218 | Qualcom... | AR9485 Wireless Network A... | 85    | ath9k      | 5F1837A6B4 |
| 14e4:4315 | 14e4:04b5 | Broadco... | BCM4312 802.11b/g LP-PHY     | 84    | ssb        | 5986AA0AAC |
| 14e4:4727 | 185f:051a | Broadco... | BCM4313 802.11bgn Wireles... | 84    | wl         | B5AE2A5BE6 |
| 168c:002b | 144f:7167 | Qualcom... | AR9285 Wireless Network A... | 83    | ath9k      | A3F9F98355 |
| 8086:4222 | 103c:135c | Intel      | PRO/Wireless 3945ABG [Gol... | 83    | iwl3945    | B38A821821 |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 82    | 8821ce     | 6EEF4CAED6 |
| 14e4:4727 | 105b:e042 | Broadco... | BCM4313 802.11bgn Wireles... | 82    | wl         | 7857E6A77B |
| 14e4:4727 | 14e4:0510 | Broadco... | BCM4313 802.11bgn Wireles... | 82    | wl         | 3C20BDA761 |
| 168c:0032 | 1a3b:1186 | Qualcom... | AR9485 Wireless Network A... | 81    | ath9k      | E407354B88 |
| 10ec:8723 | 10ec:0726 | Realtek... | RTL8723AE PCIe Wireless N... | 80    | rtl8723ae  | 0830776CD0 |
| 10ec:b723 | 103c:2231 | Realtek... | RTL8723BE PCIe Wireless N... | 80    | rtl8723be  | 0A66464BD9 |
| 168c:003e | 1a56:1535 | Qualcom... | QCA6174 802.11ac Wireless... | 80    | ath10k_pci | 18DC19F3EC |
| 14e4:4727 | 144f:7179 | Broadco... | BCM4313 802.11bgn Wireles... | 79    | wl         | 60127AB94A |
| 14e4:4315 | 103c:1508 | Broadco... | BCM4312 802.11b/g LP-PHY     | 78    | ssb        | 56A913A0DB |
| 10ec:c821 | 17aa:c024 | Realtek... | RTL8821CE 802.11ac PCIe W... | 75    | rtl8821ce  | C65ABD0640 |
| 14e4:4315 | 1028:000c | Broadco... | BCM4312 802.11b/g LP-PHY     | 75    | wl         | ADAA5B6D54 |
| 168c:002b | 103c:3040 | Qualcom... | AR9285 Wireless Network A... | 74    | ath9k      | 5D02B6C874 |
| 8086:0084 | 8086:1315 | Intel      | Centrino Wireless-N 1000 ... | 74    | iwlwifi    | F3FBF8BC70 |
| 14e4:4311 | 1028:0007 | Broadco... | BCM4311 802.11b/g WLAN       | 73    | ssb        | 4908DA86B8 |
| 8086:3165 | 8086:4410 | Intel      | Wireless 3165                | 73    | iwlwifi    | 556DD6ED0B |
| 168c:002b | 1028:0205 | Qualcom... | AR9285 Wireless Network A... | 72    | ath9k      | DE4AEAA742 |
| 168c:002b | 103c:1461 | Qualcom... | AR9285 Wireless Network A... | 72    | ath9k      | A56D8D1C28 |
| 168c:002b | 105b:e017 | Qualcom... | AR9285 Wireless Network A... | 72    | ath9k      | FC53E6761D |
| 10ec:b723 | 10ec:b729 | Realtek... | RTL8723BE PCIe Wireless N... | 71    | rtl8723be  | AA2E59FD60 |
| 14e4:4358 | 105b:e040 | Broadco... | BCM43227 802.11b/g/n         | 71    | wl         | D17275F479 |
| 14e4:4727 | 103c:145c | Broadco... | BCM4313 802.11bgn Wireles... | 71    | wl         | AF73595612 |
| 168c:0042 | 1a3b:2b31 | Qualcom... | QCA9377 802.11ac Wireless... | 69    | ath10k_pci | 219AE079DC |
| 168c:001c | 144f:7131 | Qualcom... | AR242x / AR542x Wireless ... | 68    | ath5k      | F2D52E0253 |
| 168c:0034 | 11ad:6621 | Qualcom... | AR9462 Wireless Network A... | 68    | ath9k      | 7BE60A0A2C |
| 168c:0036 | 1a3b:213a | Qualcom... | QCA9565 / AR9565 Wireless... | 65    | ath9k      | 81F8804034 |
| 14e4:4365 | 1028:0016 | Broadco... | BCM43142 802.11b/g/n         | 64    | wl         | 17ED1F4194 |
| 8086:08b2 | 8086:c270 | Intel      | Wireless 7260                | 64    | iwlwifi    | 14015A6CDE |
| 8086:24fd | 8086:0110 | Intel      | Wireless 8265 / 8275         | 64    | iwlwifi    | 9809687258 |
| 8086:9df0 | 8086:0034 | Intel      | Cannon Point-LP CNVi [Wir... | 64    | iwlwifi    | E4301E56F9 |
| 14e4:4727 | 1a3b:2047 | Broadco... | BCM4313 802.11bgn Wireles... | 59    | wl         | A6B1293F94 |
| 1814:3290 | 105b:e055 | Ralink     | RT3290 Wireless 802.11n 1... | 59    | rt2800pci  | 12F5A59D53 |
| 10ec:b723 | 103c:81c1 | Realtek... | RTL8723BE PCIe Wireless N... | 58    | rtl8723be  | A0C06307BA |
| 168c:0032 | 105b:e044 | Qualcom... | AR9485 Wireless Network A... | 58    | ath9k      | 214F765FC8 |
| 168c:0042 | 17aa:4035 | Qualcom... | QCA9377 802.11ac Wireless... | 58    | ath10k_pci | 10AB399874 |
| 10ec:8179 | 103c:197d | Realtek... | RTL8188EE Wireless Networ... | 57    | rtl8188ee  | 18F9503086 |
| 14e4:4311 | 1468:0422 | Broadco... | BCM4311 802.11b/g WLAN       | 57    | ssb        | 3D881D6E68 |
| 14e4:4365 | 103c:804a | Broadco... | BCM43142 802.11b/g/n         | 56    | wl         | 7C960F54DF |
| 168c:0036 | 11ad:0632 | Qualcom... | QCA9565 / AR9565 Wireless... | 56    | ath9k      | 94CD691A35 |
| 1814:3090 | 103c:1453 | Ralink     | RT3090 Wireless 802.11n 1... | 56    | rt2800pci  | 780F3AE697 |
| 168c:0032 | 1028:0209 | Qualcom... | AR9485 Wireless Network A... | 54    | ath9k      | 2187C4D783 |
| 168c:0032 | 105b:e047 | Qualcom... | AR9485 Wireless Network A... | 54    | ath9k      | A54B8C9315 |
| 8086:08b1 | 8086:4070 | Intel      | Wireless 7260                | 54    | iwlwifi    | 14F07E52FE |
| 10ec:8821 | 17aa:a814 | Realtek... | RTL8821AE 802.11ac PCIe W... | 53    | rtl8821ae  | 2B46AD4F9B |
| 168c:0032 | 103c:1838 | Qualcom... | AR9485 Wireless Network A... | 53    | ath9k      | F432E62120 |
| 10ec:8723 | 1a3b:2114 | Realtek... | RTL8723AE PCIe Wireless N... | 52    | rtl8723ae  | 6E20292C6B |
| 168c:001c | 103c:137b | Qualcom... | AR242x / AR542x Wireless ... | 52    | ath5k      | AB1EF36E83 |
| 168c:0036 | 105b:e07f | Qualcom... | QCA9565 / AR9565 Wireless... | 51    | ath9k      | F61E2D2B7B |
| 8086:08b1 | 8086:4470 | Intel      | Wireless 7260                | 51    | iwlwifi    | 33E615851D |
| 14e4:4357 | 105b:e021 | Broadco... | BCM43225 802.11b/g/n         | 50    | wl         | BF3E8AB91C |
| 14e4:4727 | 1028:0010 | Broadco... | BCM4313 802.11bgn Wireles... | 50    | wl         | 4309803872 |
| 168c:001c | 144f:7128 | Qualcom... | AR242x / AR542x Wireless ... | 50    | ath5k      | 276E98BB3C |
| 168c:0032 | 1a3b:2126 | Qualcom... | AR9485 Wireless Network A... | 50    | ath9k      | A8BE285B93 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0085 | 8086:1311 | Intel      | Centrino Advanced-N 6205 ... | 251   | iwlwifi    | B470E45C2C |
| 10ec:d723 | 103c:8319 | Realtek... | RTL8723DE Wireless Networ... | 232   | rtl8723de  | 16EA8E9AC4 |
| 8086:1502 | 17aa:21f3 | Intel      | 82579LM Gigabit Network C... | 139   | e1000e     | 1949413DC7 |
| 8086:088e | 8086:4060 | Intel      | Centrino Advanced-N 6235     | 127   | iwlwifi    | DA5836E2AA |
| 8086:1502 | 17aa:21ce | Intel      | 82579LM Gigabit Network C... | 119   | e1000e     | F3FBF8BC70 |
| 8086:4239 | 8086:1311 | Intel      | Centrino Advanced-N 6200     | 114   | iwlwifi    | 82CB2D5E90 |
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 96    | iwlwifi    | 3D9A8AFD81 |
| 8086:10ea | 17aa:2153 | Intel      | 82577LM Gigabit Network C... | 94    | e1000e     | 9A495F134B |
| 8086:0082 | 8086:1321 | Intel      | Centrino Advanced-N 6205 ... | 88    | iwlwifi    | 813731AB25 |
| 8086:4238 | 8086:1111 | Intel      | Centrino Ultimate-N 6300     | 74    | iwlwifi    | AB2CEA0D81 |
| 8086:0082 | 8086:1301 | Intel      | Centrino Advanced-N 6205 ... | 63    | iwlwifi    | 71BD398238 |
| 8086:10f5 | 17aa:20ee | Intel      | 82567LM Gigabit Network C... | 63    | e1000e     | 1A90AC4588 |
| 8086:422b | 8086:1121 | Intel      | Centrino Ultimate-N 6300     | 63    | iwlwifi    | 3E3F341EF4 |
| 8086:1502 | 1028:0493 | Intel      | 82579LM Gigabit Network C... | 39    | e1000e     | CA779DE74C |
| 8086:1049 | 17aa:20b9 | Intel      | 82566MM Gigabit Network C... | 34    | e1000e     | FB1CD7BF88 |
| 8086:10f5 | 1028:0233 | Intel      | 82567LM Gigabit Network C... | 34    | e1000e     | 314E0FF832 |
| 8086:10ea | 1028:040a | Intel      | 82577LM Gigabit Network C... | 32    | e1000e     | 3E3F341EF4 |
| 8086:422c | 8086:1301 | Intel      | Centrino Advanced-N 6200     | 32    | iwlwifi    | 90D3759348 |
| 14e4:170c | 1025:0090 | Broadco... | BCM4401-B0 100Base-TX        | 31    | b44        | 5979EB4500 |
| 8086:0091 | 8086:5201 | Intel      | Centrino Advanced-N 6230 ... | 31    | iwlwifi    | 7434BE9250 |
| 8086:422c | 8086:1321 | Intel      | Centrino Advanced-N 6200     | 31    | iwlwifi    | 1C9F512B78 |
| 8086:10c4 | 103c:30d8 | Intel      | 82562GT 10/100 Network Co... | 30    | e1000e     | FF0936189F |
| 8086:1502 | 103c:161c | Intel      | 82579LM Gigabit Network C... | 29    | e1000e     | 3EAB448396 |
| 8086:2723 | 8086:0084 | Intel      | Wi-Fi 6 AX200                | 27    | iwlwifi    | B944521EC0 |
| 14e4:170c | 1028:01f5 | Broadco... | BCM4401-B0 100Base-TX        | 25    | b44        | 3D6C8F2267 |
| 8086:088e | 8086:4460 | Intel      | Centrino Advanced-N 6235     | 25    | iwlwifi    | 32D2083BB0 |
| 8086:1502 | 103c:179b | Intel      | 82579LM Gigabit Network C... | 25    | e1000e     | 7195452FF3 |
| 14e4:170c | 103c:30a2 | Broadco... | BCM4401-B0 100Base-TX        | 23    | b44        | 527BA99CD2 |
| 14e4:4331 | 14e4:4331 | Broadco... | BCM4331 802.11a/b/g/n        | 23    | wl         | 433304B5E5 |
| 8086:10ea | 103c:7008 | Intel      | 82577LM Gigabit Network C... | 23    | e1000e     | 4663DEB0DD |
| 10ec:8136 | 103c:3567 | Realtek... | RTL810xE PCI Express Fast... | 22    | r8169      | 9C722B6763 |
| 8086:1502 | 1028:0534 | Intel      | 82579LM Gigabit Network C... | 21    | e1000e     | 39D47C0F09 |
| 8086:422b | 8086:1101 | Intel      | Centrino Ultimate-N 6300     | 18    | iwlwifi    | 2D934282A2 |
| 14e4:170c | 1028:01af | Broadco... | BCM4401-B0 100Base-TX        | 16    | b44        | AB555162C8 |
| 8086:10ea | 1028:040b | Intel      | 82577LM Gigabit Network C... | 16    | e1000e     | 3A85FD0475 |
| 8086:0091 | 8086:5221 | Intel      | Centrino Advanced-N 6230 ... | 15    | iwlwifi    | A2BC6AC4B5 |
| 8086:1049 | 17aa:20de | Intel      | 82566MM Gigabit Network C... | 15    | e1000e     | 74AA251B27 |
| 8086:10f5 | 1028:024f | Intel      | 82567LM Gigabit Network C... | 15    | e1000e     | 9F216D6CB3 |
| 8086:1502 | 1028:0494 | Intel      | 82579LM Gigabit Network C... | 15    | e1000e     | 4384225066 |
| 8086:1503 | 103c:17ab | Intel      | 82579V Gigabit Network Co... | 15    | e1000e     | 57308077EE |
| 8086:0087 | 8086:1301 | Intel      | Centrino Advanced-N + WiM... | 14    | iwlwifi    | 44B359D5B3 |
| 8086:1092 | 1179:ff10 | Intel      | PRO/100 VE Network Connec... | 14    | e100       | 5FDCE37F38 |
| 8086:10ea | 103c:172a | Intel      | 82577LM Gigabit Network C... | 14    | e1000e     | D1C32BF428 |
| 8086:1502 | 103c:1618 | Intel      | 82579LM Gigabit Network C... | 14    | e1000e     | 0D2FE88BE0 |
| 8086:10bf | 17aa:20ee | Intel      | 82567LF Gigabit Network C... | 13    | e1000e     | 031F4149FE |
| 8086:1502 | 1028:0532 | Intel      | 82579LM Gigabit Network C... | 13    | e1000e     | 8E240EEE56 |
| 8086:1502 | 1028:0535 | Intel      | 82579LM Gigabit Network C... | 13    | e1000e     | 813731AB25 |
| 10ec:818b | 10ec:001b | Realtek... | RTL8192EE PCIe Wireless N... | 12    | rtl8192ee  | 51730DD555 |
| 8086:0087 | 8086:1306 | Intel      | Centrino Advanced-N + WiM... | 12    | iwlwifi    | 1DE544887B |
| 8086:10ea | 103c:7007 | Intel      | 82577LM Gigabit Network C... | 12    | e1000e     | 82CB2D5E90 |
| 8086:10eb | 103c:1471 | Intel      | 82577LC Gigabit Network C... | 12    | e1000e     | 89C840D7E1 |
| 8086:1502 | 1028:04a3 | Intel      | 82579LM Gigabit Network C... | 12    | e1000e     | D8BA5B1425 |
| 8086:1502 | 10cf:161b | Intel      | 82579LM Gigabit Network C... | 12    | e1000e     | DA5836E2AA |
| 8086:1502 | 10f7:8338 | Intel      | 82579LM Gigabit Network C... | 12    | e1000e     | 71BD398238 |
| 8086:2723 | 8086:0080 | Intel      | Wi-Fi 6 AX200                | 12    | iwlwifi    | B921C3D4A7 |
| 10ec:8168 | 17aa:505b | Realtek... | RTL8111/8168/8411 PCI Exp... | 11    | r8169      | 78818887EE |
| 8086:10f5 | 103c:30db | Intel      | 82567LM Gigabit Network C... | 11    | e1000e     | 94AF8C86B1 |
| 8086:1503 | 1179:0001 | Intel      | 82579V Gigabit Network Co... | 11    | e1000e     | 6D794063DD |
| 14e4:170c | 1028:022a | Broadco... | BCM4401-B0 100Base-TX        | 10    | b44        | 7043CC968E |
| 8086:1049 | 103c:30be | Intel      | 82566MM Gigabit Network C... | 10    | e1000e     | 6ABE286091 |
| 8086:10ea | 10cf:1574 | Intel      | 82577LM Gigabit Network C... | 10    | e1000e     | 751064E2A2 |
| 8086:1502 | 1028:0492 | Intel      | 82579LM Gigabit Network C... | 10    | e1000e     | 4309803872 |
| 8086:1502 | 103c:162b | Intel      | 82579LM Gigabit Network C... | 10    | e1000e     | 1257EBD709 |
| 8086:1503 | 103c:179c | Intel      | 82579V Gigabit Network Co... | 10    | e1000e     | EB42776DAA |
| 8086:1503 | 10cf:161c | Intel      | 82579V Gigabit Network Co... | 10    | e1000e     | FD96E57299 |
| 14e4:170c | 1028:01c9 | Broadco... | BCM4401-B0 100Base-TX        | 9     | b44        | 2533BAD4C1 |
| 8086:0085 | 8086:c220 | Intel      | Centrino Advanced-N 6205 ... | 9     | iwlwifi    | A93A3068CC |
| 10de:0269 | 103c:30b7 | Nvidia     | MCP51 Ethernet Controller    | 8     | forcedeth  | 71764E2EB9 |
| 8086:10ea | 103c:1521 | Intel      | 82577LM Gigabit Network C... | 8     | e1000e     | 283EC51B86 |
| 8086:1502 | 103c:18df | Intel      | 82579LM Gigabit Network C... | 8     | e1000e     | 88109B1B15 |
| 8086:1503 | 103c:1619 | Intel      | 82579V Gigabit Network Co... | 8     | e1000e     | 791C17D2AF |
| 8086:2723 | 1a56:1654 | Intel      | Wi-Fi 6 AX200                | 8     | iwlwifi    | 1F29F031C3 |
| 14e4:170c | 1028:01f2 | Broadco... | BCM4401-B0 100Base-TX        | 7     | b44        | 63A97B9A22 |
| 14e4:170c | 103c:099c | Broadco... | BCM4401-B0 100Base-TX        | 7     | b44        | E0DF895DC8 |
| 8086:10f5 | 1028:024d | Intel      | 82567LM Gigabit Network C... | 7     | e1000e     | 884C3CACED |
| 14e4:170c | 1028:01cd | Broadco... | BCM4401-B0 100Base-TX        | 6     | b44        | ADD1EF0CA9 |
| 14e4:170c | 1028:01f1 | Broadco... | BCM4401-B0 100Base-TX        | 6     | b44        | 09BC8D2536 |
| 14e4:170c | 1028:0228 | Broadco... | BCM4401-B0 100Base-TX        | 6     | b44        | 5672A8EE03 |
| 8086:1049 | 103c:30c5 | Intel      | 82566MM Gigabit Network C... | 6     | e1000e     | AB3B50FF87 |
| 8086:10c4 | 103c:30d7 | Intel      | 82562GT 10/100 Network Co... | 6     | e1000e     | 39BC6E8D0A |
| 8086:10ea | 1028:0410 | Intel      | 82577LM Gigabit Network C... | 6     | e1000e     | 537A117E41 |
| 8086:1502 | 1028:0533 | Intel      | 82579LM Gigabit Network C... | 6     | e1000e     | 4FBD98DB12 |
| 8086:1502 | 103c:162a | Intel      | 82579LM Gigabit Network C... | 6     | e1000e     | 6D298DA4A5 |
| 8086:1502 | 103c:1631 | Intel      | 82579LM Gigabit Network C... | 6     | e1000e     | F1C7178572 |
| 8086:1502 | 103c:176b | Intel      | 82579LM Gigabit Network C... | 6     | e1000e     | 4C4BD75E1B |
| 8086:1533 | ffff:0000 | Intel      | I210 Gigabit Network Conn... | 6     | igb        | F3F9DAB3E6 |
| 8086:2723 | 8086:4080 | Intel      | Wi-Fi 6 AX200                | 6     | iwlwifi    | 1FA52D766E |
| 8086:4239 | 8086:1316 | Intel      | Centrino Advanced-N 6200     | 6     | iwlwifi    | 1A4E8CEDDB |
| 10de:0269 | 1043:1385 | Nvidia     | MCP51 Ethernet Controller    | 5     | forcedeth  | 0947EDE840 |
| 10ec:8168 | 17aa:3810 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8169      | 33A0E5FDCA |
| 10ec:c822 | 1a3b:3750 | Realtek... | 8822CE Wireless LAN 802.1... | 5     | rtwpci     | 8143D2C859 |
| 14e4:1713 | 103c:30c2 | Broadco... | NetLink BCM5906M Fast Eth... | 5     | tg3        | 320661CA9F |
| 8086:10ea | 1028:040c | Intel      | 82577LM Gigabit Network C... | 5     | e1000e     | FB2C2A5FA3 |
| 8086:10ea | 103c:1520 | Intel      | 82577LM Gigabit Network C... | 5     | e1000e     | DDA2AE0A87 |
| 8086:10ea | 10f7:8338 | Intel      | 82577LM Gigabit Network C... | 5     | e1000e     | 400317E66E |
| 8086:10f5 | 103c:30dc | Intel      | 82567LM Gigabit Network C... | 5     | e1000e     | 8A8E2ED193 |
| 8086:10f5 | 103c:30e7 | Intel      | 82567LM Gigabit Network C... | 5     | e1000e     | E05FE6B4AB |
| 8086:1502 | 1028:04a4 | Intel      | 82579LM Gigabit Network C... | 5     | e1000e     | 2A2FBFB933 |
| 8086:1502 | 1028:053e | Intel      | 82579LM Gigabit Network C... | 5     | e1000e     | 776A50340E |
| 8086:1502 | 1028:053f | Intel      | 82579LM Gigabit Network C... | 5     | e1000e     | 26E9910108 |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d26 |           | Intel      | Skylake-U/Y Northpeak        | 6     | intel_t... | 87D31F3F80 |
| 1022:1455 | 1022:1455 | AMD        | Zeppelin/Renoir PCIe Dumm... | 4     |            | 35BF9EB2EF |
| 1022:145a | 1022:145a | AMD        | Zeppelin/Raven/Raven2 PCI... | 4     |            | 35BF9EB2EF |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15e6 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Non-S... | 18    | i2c_amd... | 98794ACEB7 |
| 8086:9d24 |           | Intel      | Skylake-U/Y SPI Controller   | 11    |            | A43311F999 |
| 1022:15e6 | 103c:85ea | AMD        | Raven/Raven2/Renoir Non-S... | 6     | i2c_amd... | 4250651580 |
| 8086:22d8 | 103c:813e | Intel      | Integrated Sensor Solution   | 5     | intel_i... | 43F9ACD60A |
| 8086:9d35 | 1028:0740 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 37C0832EC3 |
| 8086:9d35 | 1028:073b | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 0DAB5B3510 |
| 8086:9d35 | 1028:07ba | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 271C309BFA |
| 8086:9d35 | 1028:0804 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | E93E7BA3C5 |
| 8086:9d35 | 103c:83b2 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | B355CE68AD |
| 8086:9d35 | 17aa:2238 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 3497939F58 |
| 8086:9d35 | 8086:9d35 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 28127ECC18 |
| 106b:1801 | 106b:1801 | Apple      | T2 Bridge Controller         | 2     |            | D3A040508D |
| 106b:1802 | 106b:1802 | Apple      | T2 Secure Enclave Processor  | 2     |            | D3A040508D |
| 8086:22d8 | 1043:1400 | Intel      | Integrated Sensor Solution   | 2     | intel_i... | 4CCE625762 |
| 8086:22d8 | 1043:1bdd | Intel      | Integrated Sensor Solution   | 2     | intel_i... | 40D8D33EF9 |
| 8086:9d35 | 1028:0741 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | D302412809 |
| 8086:9d35 | 1028:0808 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | EFB686722E |
| 8086:a135 | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 2     | intel_i... | 53A016A21C |
| 8086:22d8 | 1028:06ea | Intel      | Integrated Sensor Solution   | 1     | intel_i... | 721C1A7DC3 |
| 8086:22d8 | 1043:13a0 | Intel      | Integrated Sensor Solution   | 1     | intel_i... | C508886F10 |
| 8086:22d8 | 1071:a126 | Intel      | Integrated Sensor Solution   | 1     | intel_i... | F2981C1775 |
| 8086:9d35 | 1028:0742 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 2C812C83E2 |
| 8086:9d35 | 1028:0744 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | B4A5AF0E65 |
| 8086:9d35 | 1028:07a5 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 87A44EF029 |
| 8086:9d35 | 1028:07aa | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 1DC7215E55 |
| 8086:9d35 | 1028:0823 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 83979BC27C |
| 8086:9d35 | 103c:8197 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 910D564E8E |
| 8086:9d35 | 103c:83b3 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 2DA46102BD |
| 8086:9d35 | 10cf:18d0 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 79CC64010B |
| 8086:9d35 | 17aa:2237 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | B189CB8509 |
| 8086:9d35 | 17aa:2241 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 1038A34C39 |
| 8086:9d35 | 17aa:3812 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 57EC66B289 |
| 8086:9d35 | 17aa:504c | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 240BAB94C7 |

### Performance counters (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27a3 |           | Intel      | 945GM/GU Chipset Hardware... | 18    |            | 3A660A2575 |
| 8086:1907 | 8086:2015 | Intel      | Performance counters         | 1     |            | C0A7FF9958 |

### Pic (io(x)-apic) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1106:5364 |           | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 15    |            | 97181C941C |
| 1106:5364 | 103c:3030 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 5     |            | 99478A8C67 |
| 1106:5336 |           | VIA Tec... | K8M890CE I/O APIC Interru... | 3     |            | FEDA3B155D |
| 1106:5353 | 17aa:388a | VIA Tec... | VX800/VX820 APIC and Cent... | 3     |            | 4AA0EF1314 |
| 1106:5238 | 1734:1093 | VIA Tec... | K8T890 I/O APIC Interrupt... | 1     |            | E9825FB39A |
| 1106:5353 | 144d:c04e | VIA Tec... | VX800/VX820 APIC and Cent... | 1     |            | 3DDEF2506D |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:16bc | 1025:0647 | Broadco... | BCM57765/57785 SDXC/MMC C... | 234   | sdhci_pci  | 9084C70732 |
| 197b:2381 | 1043:1a07 | JMicron... | Standard SD Host Controller  | 121   | sdhci_pci  | 088FFC2823 |
| 14e4:16bc | 1025:0504 | Broadco... | BCM57765/57785 SDXC/MMC C... | 104   | sdhci_pci  | 832F6EF100 |
| 1180:0822 | 17aa:20c8 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 77    | sdhci_pci  | 1A90AC4588 |
| 104c:803c | 1025:011f | Texas I... | PCIxx12 SDA Standard Comp... | 71    | sdhci_pci  | BA9EFF4F3B |
| 1022:7813 | 17aa:3801 | AMD        | FCH SD Flash Controller      | 63    | sdhci_pci  | 363B08984A |
| 14e4:16bc | 1025:0775 | Broadco... | BCM57765/57785 SDXC/MMC C... | 58    | sdhci_pci  | 94CD691A35 |
| 1180:e822 | 104d:9071 | Ricoh      | MMC/SD Host Controller       | 56    | sdhci_pci  | 90D3759348 |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 52    | sdhci_pci  | 97BCBB884E |
| 8086:9d2d | 8086:9d2d | Intel      | Sunrise Point-LP Secure D... | 52    | sdhci_pci  | D720B44576 |
| 14e4:16bc | 14e4:0000 | Broadco... | BCM57765/57785 SDXC/MMC C... | 48    | sdhci_pci  | 2B202B204B |
| 1022:7806 | 1022:7806 | AMD        | FCH SD Flash Controller      | 46    | sdhci_pci  | 7873FB02D1 |
| 1217:8221 | 1028:0493 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 39    | sdhci_pci  | CA779DE74C |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 38    | sdhci_pci  | E6212ECE14 |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 37    | sdhci_pci  | E6212ECE14 |
| 1180:0822 | 1028:0233 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 34    | sdhci_pci  | 314E0FF832 |
| 1524:0550 | 1025:0090 | ENE Tec... | ENE PCI Secure Digital Ca... | 34    | sdhci_pci  | 5979EB4500 |
| 197b:2391 | 103c:17f6 | JMicron... | Standard SD Host Controller  | 33    | sdhci_pci  | 1F9408B984 |
| 10ec:5209 | 10ec:5209 | Realtek... | RTS5209 PCI Express Card ... | 31    | sdhci_pci  | 4C52CE8BDE |
| 1180:e822 | 1028:040a | Ricoh      | MMC/SD Host Controller       | 31    | sdhci_pci  | 3E3F341EF4 |
| 1180:0822 | 1028:022f | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 29    | sdhci_pci  | 56866B9E4C |
| 1180:0822 | 103c:30cc | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 29    | sdhci_pci  | 218FD78ECA |
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
| 1022:7806 | 1043:107c | AMD        | FCH SD Flash Controller      | 18    | sdhci_pci  | 6A47875DF8 |
| 1217:8520 | 1028:05be | O2 Micro   | SD/MMC Card Reader Contro... | 18    | sdhci_pci  | C7F7A6189C |
| 104c:803c | 1179:ff02 | Texas I... | PCIxx12 SDA Standard Comp... | 17    | sdhci_pci  | 3CE1664885 |
| 1180:0822 | 1043:1317 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 17    | sdhci_pci  | 4841CD6D3C |
| 1180:0822 | 10f7:8338 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 17    | sdhci_pci  | 3B2DF65591 |
| 1180:e822 | 1028:040b | Ricoh      | MMC/SD Host Controller       | 17    | sdhci_pci  | A13B3BB6D9 |
| 1217:8520 | 17aa:3800 | O2 Micro   | SD/MMC Card Reader Contro... | 17    | sdhci_pci  | B57E5735A5 |
| 14e4:16bc | 1025:0605 | Broadco... | BCM57765/57785 SDXC/MMC C... | 17    | sdhci_pci  | 72878CC6E9 |
| 197b:2381 | 103c:3628 | JMicron... | Standard SD Host Controller  | 17    | sdhci_pci  | BF5A8C1756 |
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 17    | sdhci_pci  | 7E86F1B5E7 |
| 1022:7813 | 103c:8137 | AMD        | FCH SD Flash Controller      | 16    | sdhci_pci  | 225743793E |
| 104c:803c | 1179:ff10 | Texas I... | PCIxx12 SDA Standard Comp... | 16    | sdhci_pci  | 5FDCE37F38 |
| 1217:8321 | 1028:0494 | O2 Micro   | OZ600RJ0/OZ900RJ0/OZ600RJ... | 16    | sdhci_pci  | 4384225066 |
| 1180:0822 | 1028:01bd | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 15    | sdhci_pci  | AB555162C8 |
| 1180:0822 | 1028:024f | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 15    | sdhci_pci  | 9F216D6CB3 |
| 1180:0822 | 1043:1897 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 15    | sdhci_pci  | B720D65E19 |
| 197b:2391 | 103c:17ab | JMicron... | Standard SD Host Controller  | 15    | sdhci_pci  | 57308077EE |
| 8086:9d2b | 1025:1085 | Intel      | Skylake-U/Y SCC: eMMC        | 15    | sdhci_pci  | 7528B75013 |
| 1180:0822 | 103c:172a | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 14    | sdhci_pci  | D1C32BF428 |
| 1180:0822 | 1043:14e7 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 14    | sdhci_pci  | 7AC6E3C864 |
| 1180:0822 | 104d:9035 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 14    | sdhci_pci  | 0C80B6E23F |
| 1217:8221 | 1028:0532 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 14    | sdhci_pci  | 8E240EEE56 |
| 1217:8520 | 1028:05ca | O2 Micro   | SD/MMC Card Reader Contro... | 14    | sdhci_pci  | C897C33BBA |
| 14e4:16bc | 1025:0742 | Broadco... | BCM57765/57785 SDXC/MMC C... | 14    | sdhci_pci  | 1F85BC5BA6 |
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
| 8086:31d0 | 8086:7270 | Intel      | SD Host Controller           | 12    | sdhci_pci  | 7E86F1B5E7 |
| 8086:9d2b | 8086:7270 | Intel      | Skylake-U/Y SCC: eMMC        | 12    | sdhci_pci  | C2F20FEC02 |
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
| 8086:9d2d | 8086:7270 | Intel      | Sunrise Point-LP Secure D... | 11    | sdhci_pci  | C2F20FEC02 |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9da4 | 8086:7270 | Intel      | Cannon Point-LP SPI Contr... | 42    |            | 24F8864FB8 |
| 8086:a324 | 8086:7270 | Intel      | Cannon Lake PCH SPI Contr... | 38    |            | A47D005445 |
| 8086:a324 | 1025:1264 | Intel      | Cannon Lake PCH SPI Contr... | 24    |            | AF51F8907E |
| 8086:a324 | 1028:087c | Intel      | Cannon Lake PCH SPI Contr... | 24    |            | 18DC19F3EC |
| 8086:a368 | 1025:1264 | Intel      | Cannon Lake PCH Serial IO... | 24    | intel_lpss | AF51F8907E |
| 8086:a368 | 1028:087c | Intel      | Cannon Lake PCH Serial IO... | 24    | intel_l... | 18DC19F3EC |
| 8086:a369 | 1025:1264 | Intel      | Cannon Lake PCH Serial IO... | 24    | intel_lpss | AF51F8907E |
| 8086:a369 | 1028:087c | Intel      | Cannon Lake PCH Serial IO... | 24    | intel_l... | 18DC19F3EC |
| 8086:9da4 | 1028:08af | Intel      | Cannon Point-LP SPI Contr... | 19    |            | ED8598DB62 |
| 8086:9de8 | 1028:08af | Intel      | Cannon Point-LP Serial IO... | 19    | intel_l... | ED8598DB62 |
| 8086:9de9 | 1028:08af | Intel      | Cannon Point-LP Serial IO... | 19    | intel_l... | ED8598DB62 |
| 8086:9ce6 | 8086:9ce6 | Intel      | Wildcat Point-LP Serial I... | 17    | spi_pxa... | 1A26D7B485 |
| 8086:a324 | 1028:087d | Intel      | Cannon Lake PCH SPI Contr... | 17    |            | 5741F67096 |
| 8086:a368 | 1028:087d | Intel      | Cannon Lake PCH Serial IO... | 17    | intel_l... | 5741F67096 |
| 8086:a369 | 1028:087d | Intel      | Cannon Lake PCH Serial IO... | 17    | intel_l... | 5741F67096 |
| 8086:9da4 | 17aa:2279 | Intel      | Cannon Point-LP SPI Contr... | 14    |            | F737A5A121 |
| 8086:9de8 | 17aa:2279 | Intel      | Cannon Point-LP Serial IO... | 14    | intel_l... | F737A5A121 |
| 8086:a32a | 1043:1e40 | Intel      | 300 Series Chipset Device    | 14    | intel_l... | F4689330D7 |
| 8086:9da4 | 17aa:2292 | Intel      | Cannon Point-LP SPI Contr... | 12    |            | BA2DACFEFB |
| 8086:9de8 | 17aa:2292 | Intel      | Cannon Point-LP Serial IO... | 12    | intel_l... | BA2DACFEFB |
| 8086:9de9 | 17aa:2292 | Intel      | Cannon Point-LP Serial IO... | 12    | intel_l... | BA2DACFEFB |
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
| 8086:a324 | 17aa:3802 | Intel      | Cannon Lake PCH SPI Contr... | 7     |            | 0C7FD1D5D6 |
| 8086:a368 | 17aa:3807 | Intel      | Cannon Lake PCH Serial IO... | 7     | intel_l... | 0C7FD1D5D6 |
| 8086:a369 | 17aa:3808 | Intel      | Cannon Lake PCH Serial IO... | 7     | intel_l... | 0C7FD1D5D6 |
| 10de:1adb | 1028:0000 | Nvidia     | TU106 USB Type-C UCSI Con... | 6     | i2c_nvi... | DAE953BAB0 |
| 8086:5ac8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | pwm_lpss   | 2CBA62F744 |
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
| 8086:9de9 | 1025:128d | Intel      | Cannon Point-LP Serial IO... | 6     | intel_lpss | D2C618DB7F |
| 8086:9de9 | 1043:1501 | Intel      | Cannon Point-LP Serial IO... | 6     | intel_lpss | CF0266106B |
| 8086:9de9 | 1043:1961 | Intel      | Cannon Point-LP Serial IO... | 6     | intel_lpss | BAEE55FB37 |
| 8086:a324 | 1028:0870 | Intel      | Cannon Lake PCH SPI Contr... | 6     |            | 624E7A0D96 |
| 8086:a324 | 1462:1227 | Intel      | Cannon Lake PCH SPI Contr... | 6     |            | A9A218F5DD |
| 8086:a368 | 1028:0870 | Intel      | Cannon Lake PCH Serial IO... | 6     | intel_l... | 624E7A0D96 |
| 8086:a369 | 1028:0870 | Intel      | Cannon Lake PCH Serial IO... | 6     | intel_l... | 624E7A0D96 |
| 8086:22c1 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 5     | i2c_des... | 287D86CC83 |
| 8086:9da4 | 1558:1325 | Intel      | Cannon Point-LP SPI Contr... | 5     |            | 8EC259BBD3 |
| 8086:9da4 | 19e5:3e09 | Intel      | Cannon Point-LP SPI Contr... | 5     |            | D60073EAD5 |
| 8086:9dab | 19e5:3e09 | Intel      | 8th Gen Intel Core Proces... | 5     | intel_l... | D60073EAD5 |
| 8086:9de8 | 1558:1325 | Intel      | Cannon Point-LP Serial IO... | 5     | intel_l... | 8EC259BBD3 |
| 8086:9de8 | 19e5:3e09 | Intel      | Cannon Point-LP Serial IO... | 5     | intel_l... | D60073EAD5 |
| 8086:9de9 | 19e5:3e09 | Intel      | Cannon Point-LP Serial IO... | 5     | intel_l... | D60073EAD5 |
| 8086:a324 | 1028:0824 | Intel      | Cannon Lake PCH SPI Contr... | 5     |            | 38C80D9545 |
| 8086:a324 | 103c:84da | Intel      | Cannon Lake PCH SPI Contr... | 5     |            | 605A299A65 |
| 8086:a324 | 1462:1214 | Intel      | Cannon Lake PCH SPI Contr... | 5     |            | A2411EB3FE |
| 8086:a324 | 1462:1219 | Intel      | Cannon Lake PCH SPI Contr... | 5     |            | 9013346F71 |
| 8086:a324 | 17aa:3827 | Intel      | Cannon Lake PCH SPI Contr... | 5     |            | 9F588841BD |
| 8086:a368 | 1028:0824 | Intel      | Cannon Lake PCH Serial IO... | 5     | intel_l... | 38C80D9545 |
| 8086:a368 | 1043:1fd0 | Intel      | Cannon Lake PCH Serial IO... | 5     | intel_l... | 578F1342D9 |
| 8086:a368 | 17aa:3803 | Intel      | Cannon Lake PCH Serial IO... | 5     | intel_l... | 9F588841BD |
| 8086:a369 | 1028:0824 | Intel      | Cannon Lake PCH Serial IO... | 5     | intel_l... | 38C80D9545 |
| 8086:a369 | 1043:1fd0 | Intel      | Cannon Lake PCH Serial IO... | 5     | intel_l... | 578F1342D9 |
| 8086:a369 | 17aa:3804 | Intel      | Cannon Lake PCH Serial IO... | 5     | intel_l... | 9F588841BD |
| 8086:34a4 | 1028:0979 | Intel      | Ice Lake-LP SPI Controller   | 4     |            | 2CC62B102B |
| 8086:34c5 | 1028:0979 | Intel      | Ice Lake-LP Serial IO I2c... | 4     | intel_l... | 2CC62B102B |
| 8086:34e8 | 1028:0979 | Intel      | Ice Lake-LP Serial IO I2C... | 4     | intel_l... | 2CC62B102B |
| 8086:34e9 | 1028:0979 | Intel      | Ice Lake-LP Serial IO I2C... | 4     | intel_l... | 2CC62B102B |
| 8086:9da4 | 1028:08a6 | Intel      | Cannon Point-LP SPI Contr... | 4     |            | 1DA82F475D |
| 8086:9da4 | 1028:08a8 | Intel      | Cannon Point-LP SPI Contr... | 4     |            | B6DF9FEC5F |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3b67 | 17aa:2162 | Intel      | 5 Series/3400 Series Chip... | 44    | serial     | 9A495F134B |
| 8086:2a47 | 17aa:20ec | Intel      | Mobile 4 Series Chipset A... | 43    | serial     | 7AD5A75B0A |
| 8086:1c3d | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 37    | serial     | AB2CEA0D81 |
| 8086:1e3d | 17aa:21f3 | Intel      | 7 Series/C210 Series Chip... | 27    | serial     | B162D0FD81 |
| 8086:1e3d | 17aa:21f6 | Intel      | 7 Series/C210 Series Chip... | 24    | serial     | D4095EF900 |
| 8086:1e3d | 17aa:21fa | Intel      | 7 Series/C210 Series Chip... | 21    | serial     | AD8913BB6B |
| 8086:1c3d | 103c:161c | Intel      | 6 Series/C200 Series Chip... | 20    | serial     | E8BE126153 |
| 8086:9c3d | 17aa:220c | Intel      | 8 Series HECI KT             | 20    | serial     | CE53F07ED9 |
| 8086:1e3d | 103c:179b | Intel      | 7 Series/C210 Series Chip... | 16    | serial     | 3E4C38B4BE |
| 8086:3b67 | 103c:7008 | Intel      | 5 Series/3400 Series Chip... | 15    | serial     | 4663DEB0DD |
| 8086:9c3d | 103c:198f | Intel      | 8 Series HECI KT             | 15    | serial     | 756C79455B |
| 8086:1c3d | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 14    | serial     | DA7FEA9DD2 |
| 8086:3b67 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 12    | serial     | 3E3F341EF4 |
| 8086:1c3d | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 11    | serial     | CA779DE74C |
| 8086:3b67 | 103c:172a | Intel      | 5 Series/3400 Series Chip... | 11    | serial     | D1C32BF428 |
| 8086:3b67 | 103c:7007 | Intel      | 5 Series/3400 Series Chip... | 11    | serial     | 25F2766AA4 |
| 8086:8c3d | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 11    | serial     | D30516DD82 |
| 8086:1c3d | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 10    | serial     | DF04D39AC3 |
| 8086:1c3d | 17aa:21d2 | Intel      | 6 Series/C200 Series Chip... | 10    | serial     | 53037BE14E |
| 8086:8c3d | 1028:05be | Intel      | 8 Series/C220 Series Chip... | 10    | serial     | D78531B63C |
| 8086:9d3d | 103c:8079 | Intel      | Sunrise Point-LP Active M... | 10    | serial     | 13C0B5A2EE |
| 8086:1c3d | 1028:0494 | Intel      | 6 Series/C200 Series Chip... | 9     | serial     | 4384225066 |
| 8086:1c3d | 103c:1618 | Intel      | 6 Series/C200 Series Chip... | 9     | serial     | 0D2FE88BE0 |
| 8086:1c3d | 103c:162b | Intel      | 6 Series/C200 Series Chip... | 9     | serial     | FAF97CF550 |
| 8086:3b67 | 1028:040b | Intel      | 5 Series/3400 Series Chip... | 9     | serial     | 3A85FD0475 |
| 8086:9c3d | 1028:05ca | Intel      | 8 Series HECI KT             | 9     | serial     | C897C33BBA |
| 8086:1e3d | 17aa:21fb | Intel      | 7 Series/C210 Series Chip... | 8     | serial     | 4433C4AB4E |
| 8086:3b67 | 10cf:152f | Intel      | 5 Series/3400 Series Chip... | 8     | serial     | E3DCD9CD51 |
| 8086:1e3d | 10cf:16ed | Intel      | 7 Series/C210 Series Chip... | 7     | serial     | DA5836E2AA |
| 8086:1c3d | 1028:04a3 | Intel      | 6 Series/C200 Series Chip... | 6     | serial     | D8BA5B1425 |
| 8086:1c3d | 17aa:21db | Intel      | 6 Series/C200 Series Chip... | 6     | serial     | 73176F470C |
| 8086:1e3d | 1028:0534 | Intel      | 7 Series/C210 Series Chip... | 6     | serial     | 49D71B26E7 |
| 8086:2a07 | 17aa:20d4 | Intel      | Mobile PM965/GM965 KT Con... | 6     | serial     | 6DC6A318E1 |
| 8086:3b67 | 103c:1521 | Intel      | 5 Series/3400 Series Chip... | 6     | serial     | 283EC51B86 |
| 8086:8c3d | 10cf:17e0 | Intel      | 8 Series/C220 Series Chip... | 6     | serial     | CF73AE98A0 |
| 8086:9c3d | 103c:1991 | Intel      | 8 Series HECI KT             | 6     | serial     | 4A533D1C93 |
| 8086:9dfc | 103c:8549 | Intel      | Cannon Point-LP Integrate... | 6     | intel_i... | 0B8C8AB6F3 |
| 8086:1c3d | 1028:0492 | Intel      | 6 Series/C200 Series Chip... | 5     | serial     | 5051F637C0 |
| 8086:1e3d | 103c:17a7 | Intel      | 7 Series/C210 Series Chip... | 5     | serial     | 930B0C48ED |
| 8086:1e3d | 103c:18df | Intel      | 7 Series/C210 Series Chip... | 5     | serial     | 88109B1B15 |
| 8086:1e3d | 17aa:21f9 | Intel      | 7 Series/C210 Series Chip... | 5     | serial     | A93A3068CC |
| 8086:2a47 | 103c:30e7 | Intel      | Mobile 4 Series Chipset A... | 5     | serial     | E05FE6B4AB |
| 8086:9c3d | 1028:05cb | Intel      | 8 Series HECI KT             | 5     | serial     | 19F3DF030D |
| 8086:9c3d | 17aa:2214 | Intel      | 8 Series HECI KT             | 5     | serial     | 688A1A737C |
| 8086:9c3d | 17aa:2218 | Intel      | 8 Series HECI KT             | 5     | serial     | C344D6572A |
| 8086:9d3d | 1028:06dc | Intel      | Sunrise Point-LP Active M... | 5     | serial     | 3C44DE609A |
| 8086:9d3d | 1028:081c | Intel      | Sunrise Point-LP Active M... | 5     | serial     | B4899BA50A |
| 8086:9d3d | 17aa:2233 | Intel      | Sunrise Point-LP Active M... | 5     | serial     | 6C8F4AD0D7 |
| 8086:9d3d | 17aa:2245 | Intel      | Sunrise Point-LP Active M... | 5     | serial     | 9F5951C997 |
| 8086:9d3d | 17aa:225c | Intel      | Sunrise Point-LP Active M... | 5     | serial     | ACED6CD1BD |
| 8086:a13d | 17aa:222e | Intel      | 100 Series/C230 Series Ch... | 5     | serial     | 6FF485C6DD |
| 8086:1c3d | 10cf:1614 | Intel      | 6 Series/C200 Series Chip... | 4     | serial     | 12ED876B92 |
| 8086:1c3d | 10f7:8338 | Intel      | 6 Series/C200 Series Chip... | 4     | serial     | 71BD398238 |
| 8086:1c3d | 1179:0001 | Intel      | 6 Series/C200 Series Chip... | 4     | serial     | 4398E73607 |
| 8086:1e3d | 1028:0535 | Intel      | 7 Series/C210 Series Chip... | 4     | serial     | 6251A0DB90 |
| 8086:1e3d | 17aa:2203 | Intel      | 7 Series/C210 Series Chip... | 4     | serial     | D06826DB64 |
| 8086:2a07 | 103c:30be | Intel      | Mobile PM965/GM965 KT Con... | 4     | serial     | 2724623348 |
| 8086:2a07 | 103c:30c3 | Intel      | Mobile PM965/GM965 KT Con... | 4     | serial     | D201D96AFE |
| 8086:2a07 | 103c:30c5 | Intel      | Mobile PM965/GM965 KT Con... | 4     | serial     | AB3B50FF87 |
| 8086:2a47 | 103c:30db | Intel      | Mobile 4 Series Chipset A... | 4     | serial     | 856FCDED98 |
| 8086:2a47 | 103c:30dc | Intel      | Mobile 4 Series Chipset A... | 4     | serial     | 8A8E2ED193 |
| 8086:2a47 | 1734:1147 | Intel      | Mobile 4 Series Chipset A... | 4     | serial     | 09C1DFABF4 |
| 8086:3b67 | 103c:1520 | Intel      | 5 Series/3400 Series Chip... | 4     | serial     | DDA2AE0A87 |
| 8086:3b67 | 103c:172b | Intel      | 5 Series/3400 Series Chip... | 4     | serial     | 35E3CAB7FD |
| 8086:8c3d | 1028:05bd | Intel      | 8 Series/C220 Series Chip... | 4     | serial     | 428350F750 |
| 8086:8c3d | 103c:1909 | Intel      | 8 Series/C220 Series Chip... | 4     | serial     | 196DFE92A3 |
| 8086:9d3d | 17aa:504a | Intel      | Sunrise Point-LP Active M... | 4     | serial     | EFBD2122B7 |
| 8086:9d3d | 17aa:5053 | Intel      | Sunrise Point-LP Active M... | 4     | serial     | C37E8C9E3E |
| 8086:9dfc | 1028:08a8 | Intel      | Cannon Point-LP Integrate... | 4     | intel_i... | B6DF9FEC5F |
| 10ec:816a | 17aa:5125 | Realtek... | Virtual COM1                 | 3     |            | E97740F470 |
| 10ec:816b | 17aa:5125 | Realtek... | RealManage COM2              | 3     |            | E97740F470 |
| 8086:1c3d | 1028:04a4 | Intel      | 6 Series/C200 Series Chip... | 3     | serial     | 370EF78297 |
| 8086:1c3d | 103c:162a | Intel      | 6 Series/C200 Series Chip... | 3     | serial     | 5951373CC3 |
| 8086:1e3d | 103c:176c | Intel      | 7 Series/C210 Series Chip... | 3     | serial     | 2D934282A2 |
| 8086:2a07 | 17aa:20d0 | Intel      | Mobile PM965/GM965 KT Con... | 3     | serial     | D8398B196B |
| 8086:2a47 | 1028:024f | Intel      | Mobile 4 Series Chipset A... | 3     | serial     | 00C163136F |
| 8086:2a47 | 103c:30e1 | Intel      | Mobile 4 Series Chipset A... | 3     | serial     | 189F28A68E |
| 8086:8c3d | 103c:190a | Intel      | 8 Series/C220 Series Chip... | 3     | serial     | 8D43E4B1AB |
| 8086:9c3d | 1028:05de | Intel      | 8 Series HECI KT             | 3     | serial     | C50DF1C2F3 |
| 8086:9c3d | 1028:0605 | Intel      | 8 Series HECI KT             | 3     | serial     | A9838B4E45 |
| 8086:9c3d | 103c:213e | Intel      | 8 Series HECI KT             | 3     | serial     | F9CD4D265E |
| 8086:9d3d | 1028:06de | Intel      | Sunrise Point-LP Active M... | 3     | serial     | 5BF1258E74 |
| 8086:9d3d | 1028:081b | Intel      | Sunrise Point-LP Active M... | 3     | serial     | 714656669C |
| 8086:9de3 | 103c:8549 | Intel      | Cannon Point-LP Keyboard ... | 3     | serial     | 0B8C8AB6F3 |
| 8086:9de3 | 17aa:2279 | Intel      | Cannon Point-LP Keyboard ... | 3     | serial     | 9E6BA8B8D7 |
| 8086:9de3 | 17aa:2292 | Intel      | Cannon Point-LP Keyboard ... | 3     | serial     | 7B90AA9C1B |
| 8086:9dfc | 1028:08a7 | Intel      | Cannon Point-LP Integrate... | 3     | intel_i... | 4100D4ED4F |
| 8086:a13d | 1028:07bf | Intel      | 100 Series/C230 Series Ch... | 3     | serial     | EBB304F58E |
| 8086:a13d | 17aa:224d | Intel      | 100 Series/C230 Series Ch... | 3     | serial     | 46BFB60272 |
| 8086:a363 | 103c:8427 | Intel      | Cannon Lake PCH Active Ma... | 3     | serial     | A6D0CC5DA1 |
| 8086:a363 | 17aa:2267 | Intel      | Cannon Lake PCH Active Ma... | 3     | serial     | 444D60D6DA |
| 8086:a37c | 1028:0949 | Intel      | VROC Virtual Controller      | 3     | intel_i... | 0652C09B6F |
| 10ec:816a | 17aa:5122 | Realtek... | Virtual COM1                 | 2     |            | 971B99D081 |
| 10ec:816a | 17aa:5126 | Realtek... | Virtual COM1                 | 2     |            | ADEC400398 |
| 10ec:816b | 17aa:5122 | Realtek... | RealManage COM2              | 2     |            | 971B99D081 |
| 10ec:816b | 17aa:5126 | Realtek... | RealManage COM2              | 2     |            | ADEC400398 |
| 8086:1c3d | 103c:1631 | Intel      | 6 Series/C200 Series Chip... | 2     | serial     | 22661D8917 |
| 8086:1e3d | 1028:0532 | Intel      | 7 Series/C210 Series Chip... | 2     | serial     | 388A2900EF |
| 8086:1e3d | 1028:0533 | Intel      | 7 Series/C210 Series Chip... | 2     | serial     | BBAA208359 |
| 8086:1e3d | 1028:0549 | Intel      | 7 Series/C210 Series Chip... | 2     | serial     | 6136663F73 |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3b32 | 17aa:2190 | Intel      | 5 Series/3400 Series Chip... | 96    | intel_ips  | 9A495F134B |
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 90    | process... | AE477CA654 |
| 8086:9d27 | 1043:1d2d | Intel      | Sunrise Point-LP Serial I... | 74    | intel_lpss | D720B44576 |
| 8086:3b32 | 17aa:38c0 | Intel      | 5 Series/3400 Series Chip... | 64    | intel_ips  | 15789D122D |
| 8086:22dc | 7270:8086 | Intel      | Atom/Celeron/Pentium Proc... | 62    | process... | A92F12150A |
| 8086:9d29 | 1043:1d2d | Intel      | Sunrise Point-LP Serial I... | 61    | intel_lpss | D720B44576 |
| 8086:5a8c |           | Intel      | Dynamic Platform and Ther... | 58    | process... | 97BCBB884E |
| 8086:2932 | 17aa:3a1f | Intel      | 82801I (ICH9 Family) Ther... | 55    |            | 5986AA0AAC |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 53    | intel_l... | 97BCBB884E |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 53    | intel_l... | 97BCBB884E |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 53    | intel_l... | 97BCBB884E |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 53    | intel_l... | 97BCBB884E |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 53    | intel_l... | 97BCBB884E |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 53    | intel_l... | 97BCBB884E |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 53    | intel_l... | 97BCBB884E |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 53    | intel_l... | 97BCBB884E |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 53    | intel_l... | 97BCBB884E |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 53    | intel_l... | 97BCBB884E |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 53    | intel_l... | 97BCBB884E |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 53    | intel_l... | 97BCBB884E |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 53    | intel_l... | 97BCBB884E |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 53    | intel_l... | 97BCBB884E |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 51    | intel_l... | 97BCBB884E |
| 8086:0a03 | 8086:2010 | Intel      | Haswell-ULT Thermal Subsy... | 50    | process... | 64EDCECFF8 |
| 8086:3b32 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 48    | intel_ips  | 53ECD14649 |
| 8086:3b32 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 43    | intel_ips  | 088FFC2823 |
| 8086:5a8c | 1043:16a0 | Intel      | Dynamic Platform and Ther... | 40    | proc_th... | F885D0EE5F |
| 8086:5aac | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 40    | intel_lpss | F885D0EE5F |
| 8086:5ab4 | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 40    | intel_lpss | F885D0EE5F |
| 8086:3b32 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 35    | intel_ips  | 90D3759348 |
| 8086:318c | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 34    | proc_th... | 59974C206C |
| 8086:31b4 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 34    | intel_lpss | 59974C206C |
| 8086:31b6 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 34    | intel_lpss | 59974C206C |
| 8086:31bc | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 34    | intel_lpss | 59974C206C |
| 8086:31be | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 34    | intel_lpss | 59974C206C |
| 8086:31c0 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 34    | intel_lpss | 59974C206C |
| 8086:31ee | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 34    | intel_lpss | 59974C206C |
| 8086:0a03 | 1043:131d | Intel      | Haswell-ULT Thermal Subsy... | 33    | process... | 9F136B8761 |
| 8086:9d31 | 17aa:3861 | Intel      | Sunrise Point-LP Thermal ... | 33    | intel_p... | 91D8C5CEC3 |
| 8086:9d60 | 17aa:3865 | Intel      | Sunrise Point-LP Serial I... | 33    | intel_l... | 91D8C5CEC3 |
| 8086:3b32 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 31    | intel_ips  | 3E3F341EF4 |
| 8086:9c24 | 1043:131d | Intel      | 8 Series Thermal             | 31    | intel_p... | 9F136B8761 |
| 8086:9d60 | 1025:1193 | Intel      | Sunrise Point-LP Serial I... | 31    | intel_lpss | 02EEEC88C4 |
| 8086:9d61 | 1025:1193 | Intel      | Sunrise Point-LP Serial I... | 31    | intel_lpss | 02EEEC88C4 |
| 8086:0153 | 1043:1587 | Intel      | 3rd Gen Core Processor Th... | 29    |            | A14ECCA066 |
| 8086:9d60 | 1025:1085 | Intel      | Sunrise Point-LP Serial I... | 29    | intel_l... | 8BC74BD7FB |
| 8086:9d61 | 1025:1085 | Intel      | Sunrise Point-LP Serial I... | 29    | intel_l... | 8BC74BD7FB |
| 8086:9c24 | 1043:16cd | Intel      | 8 Series Thermal             | 27    | intel_p... | 786924EC40 |
| 8086:9d31 | 1025:115f | Intel      | Sunrise Point-LP Thermal ... | 27    | intel_p... | A230640EC7 |
| 8086:9d60 | 1025:115f | Intel      | Sunrise Point-LP Serial I... | 27    | intel_l... | A230640EC7 |
| 8086:1903 | 103c:832a | Intel      | Xeon E3-1200 v5/E3-1500 v... | 26    | process... | 931D7104FA |
| 8086:9d31 | 103c:832a | Intel      | Sunrise Point-LP Thermal ... | 26    | intel_p... | 931D7104FA |
| 8086:0a03 | 1043:16cd | Intel      | Haswell-ULT Thermal Subsy... | 25    | process... | EC78CDF03D |
| 8086:3b32 | 10cf:1526 | Intel      | 5 Series/3400 Series Chip... | 25    | intel_ips  | 95D76D0DE1 |
| 8086:1903 | 1028:087c | Intel      | Xeon E3-1200 v5/E3-1500 v... | 24    | process... | 18DC19F3EC |
| 8086:3b32 | 144d:c581 | Intel      | 5 Series/3400 Series Chip... | 24    | intel_ips  | D9ECE67AC1 |
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
| 8086:9ca4 | 17aa:5034 | Intel      | Wildcat Point-LP Thermal ... | 22    | intel_p... | 71DE9234CB |
| 8086:9d27 | 1043:1a00 | Intel      | Sunrise Point-LP Serial I... | 22    | intel_lpss | 8C29A78852 |
| 8086:9d29 | 1043:1a00 | Intel      | Sunrise Point-LP Serial I... | 22    | intel_lpss | 8C29A78852 |
| 8086:9d31 | 1043:1a00 | Intel      | Sunrise Point-LP Thermal ... | 22    | intel_p... | 8C29A78852 |
| 8086:9d60 | 1043:1a00 | Intel      | Sunrise Point-LP Serial I... | 22    | intel_lpss | 8C29A78852 |
| 8086:9d61 | 1043:1a00 | Intel      | Sunrise Point-LP Serial I... | 22    | intel_lpss | 8C29A78852 |
| 8086:1603 | 1043:1a6d | Intel      | Broadwell-U Processor The... | 20    | process... | DF4413AF58 |
| 8086:9ca4 | 1043:1a6d | Intel      | Wildcat Point-LP Thermal ... | 20    | intel_p... | DF4413AF58 |
| 8086:9d31 | 17aa:380e | Intel      | Sunrise Point-LP Thermal ... | 20    | intel_p... | 3493C4EBA1 |
| 8086:9d31 | 17aa:5068 | Intel      | Sunrise Point-LP Thermal ... | 20    | intel_p... | F4826C3A2A |
| 8086:1903 | 1028:07e6 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 19    | process... | C26F2A8CCF |
| 8086:1903 | 1028:08af | Intel      | Xeon E3-1200 v5/E3-1500 v... | 19    | process... | ED8598DB62 |
| 8086:31be | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 19    | intel_l... | 7E86F1B5E7 |
| 8086:31c4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 19    | intel_l... | 7E86F1B5E7 |
| 8086:31c6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 19    | intel_l... | 7E86F1B5E7 |
| 8086:31ee | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 19    | intel_l... | 7E86F1B5E7 |
| 8086:3b32 | 1025:0601 | Intel      | 5 Series/3400 Series Chip... | 19    | intel_ips  | 06E96D08B8 |
| 8086:9d31 | 1028:07e6 | Intel      | Sunrise Point-LP Thermal ... | 19    | intel_p... | C26F2A8CCF |
| 8086:9d60 | 1028:07e6 | Intel      | Sunrise Point-LP Serial I... | 19    | intel_l... | C26F2A8CCF |
| 8086:9d61 | 1028:07e6 | Intel      | Sunrise Point-LP Serial I... | 19    | intel_l... | C26F2A8CCF |
| 8086:9df9 | 1028:08af | Intel      | Cannon Point-LP Thermal C... | 19    | intel_p... | ED8598DB62 |
| 8086:1903 | 8086:1903 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 18    | process... | 442F0D1A5A |
| 8086:3b32 | 1043:1f27 | Intel      | 5 Series/3400 Series Chip... | 18    | intel_ips  | 4DDE29EA59 |
| 8086:3b32 | 144d:c06a | Intel      | 5 Series/3400 Series Chip... | 18    | intel_ips  | D5A18944DD |
| 8086:9ca4 | 8086:7270 | Intel      | Wildcat Point-LP Thermal ... | 18    | intel_p... | 1A26D7B485 |
| 8086:1603 | 1043:19ad | Intel      | Broadwell-U Processor The... | 17    | process... | E39A8168E3 |
| 8086:1903 | 1028:087d | Intel      | Xeon E3-1200 v5/E3-1500 v... | 17    | process... | 5741F67096 |
| 8086:1903 | 103c:84a6 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 17    | process... | 56A3768905 |
| 8086:2932 | 103c:3628 | Intel      | 82801I (ICH9 Family) Ther... | 17    |            | BF5A8C1756 |
| 8086:318c | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 17    | process... | 7E86F1B5E7 |
| 8086:31ac | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 17    | intel_l... | 7E86F1B5E7 |
| 8086:31ae | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 17    | intel_l... | 7E86F1B5E7 |
| 8086:31b0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 17    | intel_l... | 7E86F1B5E7 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e22 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 301   | i2c_i801   | 8CE0C08E9A |
| 8086:1c22 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 187   | i2c_i801   | 89EF922929 |
| 8086:27da | 1043:83ad | Intel      | NM10/ICH7 Family SMBus Co... | 133   | i2c_i801   | A6B1293F94 |
| 1002:4385 |           | AMD        | SBx00 SMBus Controller       | 118   | i2c_pii... | D500F84DEB |
| 8086:9c22 | 17aa:3978 | Intel      | 8 Series SMBus Controller    | 114   | i2c_i801   | 972580DCF6 |
| 8086:3b30 | 17aa:2167 | Intel      | 5 Series/3400 Series Chip... | 105   | i2c_i801   | 9A495F134B |
| 8086:2930 | 17aa:20f9 | Intel      | 82801I (ICH9 Family) SMBu... | 93    | i2c_i801   | 1A90AC4588 |
| 8086:1c22 | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 89    | i2c_i801   | B7B1C7DF29 |
| 8086:1e22 | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 88    | i2c_i801   | 7857E6A77B |
| 8086:2930 | 17aa:3a1d | Intel      | 82801I (ICH9 Family) SMBu... | 84    | i2c_i801   | 5986AA0AAC |
| 8086:3b30 | 17aa:38bf | Intel      | 5 Series/3400 Series Chip... | 84    | i2c_i801   | 15789D122D |
| 8086:8c22 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 81    | i2c_i801   | F21C5B69B8 |
| 8086:1c22 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 80    | i2c_i801   | 25D909CC38 |
| 8086:1e22 | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 75    | i2c_i801   | 1C3C62EC29 |
| 8086:1e22 | 1043:124d | Intel      | 7 Series/C216 Chipset Fam... | 71    | i2c_i801   | 179397B4EA |
| 8086:283e | 1025:011f | Intel      | 82801H (ICH8 Family) SMBu... | 71    | i2c_i801   | BA9EFF4F3B |
| 8086:1e22 | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 69    | i2c_i801   | 9084C70732 |
| 8086:1e22 | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 68    | i2c_i801   | EFE09AFB77 |
| 8086:1c22 | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 67    | i2c_i801   | 47A635ACC1 |
| 8086:3b30 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 64    | i2c_i801   | 53ECD14649 |
| 1022:780b | 17aa:3801 | AMD        | FCH SMBus Controller         | 63    | i2c_piix4  | 363B08984A |
| 8086:0f12 | 17aa:3905 | Intel      | Atom Processor E3800 Seri... | 59    | i2c_i801   | F2797B8B83 |
| 8086:3b30 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 56    | i2c_i801   | 90D3759348 |
| 8086:283e | 17aa:20a9 | Intel      | 82801H (ICH8 Family) SMBu... | 55    | i2c_i801   | FB1CD7BF88 |
| 8086:27da | 1025:0349 | Intel      | NM10/ICH7 Family SMBus Co... | 54    | i2c_i801   | A911172500 |
| 8086:3b30 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 53    | i2c_i801   | 088FFC2823 |
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 53    | i2c_i801   | 97BCBB884E |
| 8086:1c22 | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 52    | i2c_i801   | 4DB132BB33 |
| 8086:1e22 | 17aa:5011 | Intel      | 7 Series/C216 Chipset Fam... | 50    | i2c_i801   | 82A9861AFD |
| 8086:1c22 | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 49    | i2c_i801   | 0BF9EE57AF |
| 8086:1c22 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 48    | i2c_i801   | F3FBF8BC70 |
| 8086:1e22 | 1043:14c7 | Intel      | 7 Series/C216 Chipset Fam... | 48    | i2c_i801   | 12F5A59D53 |
| 8086:1e22 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 48    | i2c_i801   | D28ACFF1E6 |
| 1022:790b | 103c:8330 | AMD        | FCH SMBus Controller         | 47    | i2c_piix4  | E26638D750 |
| 8086:1c22 | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 47    | i2c_i801   | DF459BC2B0 |
| 8086:1e22 | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 44    | i2c_i801   | B162D0FD81 |
| 1022:780b | 144d:c0da | AMD        | FCH SMBus Controller         | 43    | i2c_pii... | 047093E08D |
| 8086:9c22 | 1025:0866 | Intel      | 8 Series SMBus Controller    | 43    | i2c_i801   | 3FD761163B |
| 8086:1e22 | 17aa:21f6 | Intel      | 7 Series/C216 Chipset Fam... | 42    | i2c_i801   | 1949413DC7 |
| 8086:1c22 | 144d:c0b6 | Intel      | 6 Series/C200 Series Chip... | 41    | i2c_i801   | 5118CD27DD |
| 8086:1c22 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 40    | i2c_i801   | CA779DE74C |
| 8086:2930 | 1025:0212 | Intel      | 82801I (ICH9 Family) SMBu... | 40    | i2c_i801   | CCC2EA91E1 |
| 8086:5ad4 | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 40    | i2c_i801   | F885D0EE5F |
| 8086:0f12 | 17aa:3909 | Intel      | Atom Processor E3800 Seri... | 38    | i2c_i801   | 7D85F9BFAB |
| 1022:790b | 1025:1192 | AMD        | FCH SMBus Controller         | 37    | piix4_s... | 17E62D31B9 |
| 8086:1c22 | 104d:908b | Intel      | 6 Series/C200 Series Chip... | 37    | i2c_i801   | A9E0A905BD |
| 8086:1e22 | 1043:1477 | Intel      | 7 Series/C216 Chipset Fam... | 37    | i2c_i801   | C005B421A9 |
| 8086:1e22 | 144d:c652 | Intel      | 7 Series/C216 Chipset Fam... | 37    | i2c_i801   | 7F741A485F |
| 1002:4385 | 1043:104c | AMD        | SBx00 SMBus Controller       | 36    | i2c_pii... | AE90CAFD98 |
| 8086:1e22 | 1179:fb31 | Intel      | 7 Series/C216 Chipset Fam... | 36    | i2c_i801   | A0FFB29C6C |
| 8086:2930 | 144d:c06d | Intel      | 82801I (ICH9 Family) SMBu... | 36    | i2c_i801   | 3A86D13DA1 |
| 8086:1e22 | 1043:1587 | Intel      | 7 Series/C216 Chipset Fam... | 35    | i2c_i801   | A14ECCA066 |
| 8086:27da | 1025:0090 | Intel      | NM10/ICH7 Family SMBus Co... | 35    | i2c_i801   | 5979EB4500 |
| 8086:9c22 | 17aa:220c | Intel      | 8 Series SMBus Controller    | 35    | i2c_i801   | 14015A6CDE |
| 8086:1c22 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 34    | i2c_i801   | 2B202B204B |
| 8086:1e22 | 144d:c0d8 | Intel      | 7 Series/C216 Chipset Fam... | 34    | i2c_i801   | C5694CCAC0 |
| 8086:1e22 | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 34    | i2c_i801   | AFB801A018 |
| 8086:27da | 144d:c072 | Intel      | NM10/ICH7 Family SMBus Co... | 34    | i2c_i801   | 60127AB94A |
| 8086:283e | 1028:01f9 | Intel      | 82801H (ICH8 Family) SMBu... | 34    | i2c_i801   | 4908DA86B8 |
| 8086:2930 | 1028:0233 | Intel      | 82801I (ICH9 Family) SMBu... | 34    | i2c_i801   | 314E0FF832 |
| 8086:31d4 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 34    | i2c_i801   | 59974C206C |
| 8086:9c22 | 1025:0775 | Intel      | 8 Series SMBus Controller    | 34    | i2c_i801   | 94CD691A35 |
| 1002:4385 | 1002:4385 | AMD        | SBx00 SMBus Controller       | 33    | i2c_pii... | 684866EE94 |
| 1002:4385 | 103c:3577 | AMD        | SBx00 SMBus Controller       | 33    | i2c_pii... | 758C395C78 |
| 1002:4385 | 17aa:397b | AMD        | SBx00 SMBus Controller       | 33    | i2c_pii... | 54094B2977 |
| 1022:780b | 17aa:397c | AMD        | FCH SMBus Controller         | 33    | i2c_piix4  | 5F1837A6B4 |
| 8086:1e22 | 10cf:16e6 | Intel      | 7 Series/C216 Chipset Fam... | 33    | i2c_i801   | DA5836E2AA |
| 8086:27da | 1025:0590 | Intel      | NM10/ICH7 Family SMBus Co... | 33    | i2c_i801   | 326A5F97CA |
| 8086:3b30 | 144d:c07f | Intel      | 5 Series/3400 Series Chip... | 33    | i2c_i801   | A3F9F98355 |
| 8086:9d23 | 17aa:386f | Intel      | Sunrise Point-LP SMBus       | 33    | i2c_i801   | 91D8C5CEC3 |
| 8086:2292 | 1025:1012 | Intel      | Atom/Celeron/Pentium Proc... | 32    | i2c_i801   | 0949108352 |
| 8086:3b30 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 32    | i2c_i801   | 3E3F341EF4 |
| 8086:9c22 | 1028:0651 | Intel      | 8 Series SMBus Controller    | 32    | i2c_i801   | DBD15FDF3D |
| 10de:0aa2 | 10de:cb79 | Nvidia     | MCP79 SMBus                  | 31    | i2c_nfo... | 441575D073 |
| 8086:0f12 | 1043:14dd | Intel      | Atom Processor E3800 Seri... | 31    | i2c_i801   | CC9B263062 |
| 8086:1e22 | 1025:0686 | Intel      | 7 Series/C216 Chipset Fam... | 31    | i2c_i801   | 1F28286A78 |
| 8086:3b30 | 144d:c581 | Intel      | 5 Series/3400 Series Chip... | 31    | i2c_i801   | D9ECE67AC1 |
| 8086:9c22 | 1043:131d | Intel      | 8 Series SMBus Controller    | 31    | i2c_i801   | 9F136B8761 |
| 8086:9d23 | 1025:1193 | Intel      | Sunrise Point-LP SMBus       | 31    | i2c_i801   | 02EEEC88C4 |
| 1022:780b | 17aa:3802 | AMD        | FCH SMBus Controller         | 30    | i2c_piix4  | AAC48DC435 |
| 1022:790b | 17aa:3816 | AMD        | FCH SMBus Controller         | 30    | i2c_piix4  | 8B23CB3E69 |
| 1022:780b | 103c:184a | AMD        | FCH SMBus Controller         | 29    | i2c_piix4  | 4C72CE34FA |
| 8086:1c22 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 29    | i2c_i801   | DA7FEA9DD2 |
| 8086:1e22 | 104d:90b8 | Intel      | 7 Series/C216 Chipset Fam... | 29    | i2c_i801   | B9133671A8 |
| 8086:283e | 1028:022f | Intel      | 82801H (ICH8 Family) SMBu... | 29    | i2c_i801   | 56866B9E4C |
| 8086:283e | 103c:30cc | Intel      | 82801H (ICH8 Family) SMBu... | 29    | i2c_i801   | 218FD78ECA |
| 8086:2930 | 1025:013c | Intel      | 82801I (ICH9 Family) SMBu... | 29    | i2c_i801   | A8E4D6D25F |
| 8086:9d23 | 1025:1085 | Intel      | Sunrise Point-LP SMBus       | 29    | i2c_i801   | 8BC74BD7FB |
| 8086:3b30 | 144d:c06a | Intel      | 5 Series/3400 Series Chip... | 28    | i2c_i801   | EF6EEF8F3E |
| 8086:0f12 | 1297:2041 | Intel      | Atom Processor E3800 Seri... | 27    | i2c_i801   | 199C248CC1 |
| 8086:1c22 | 1179:fc30 | Intel      | 6 Series/C200 Series Chip... | 27    | i2c_i801   | A1569BC1E6 |
| 8086:9c22 | 1043:16cd | Intel      | 8 Series SMBus Controller    | 27    | i2c_i801   | 786924EC40 |
| 8086:9d23 | 1025:115f | Intel      | Sunrise Point-LP SMBus       | 27    | i2c_i801   | A230640EC7 |
| 1002:4372 | 1025:009f | AMD        | IXP SB4x0 SMBus Controller   | 26    | i2c_piix4  | 005CF3D43E |
| 1002:4385 | 1025:0489 | AMD        | SBx00 SMBus Controller       | 26    | i2c_pii... | B99A6015C7 |
| 8086:0f12 | 103c:2213 | Intel      | Atom Processor E3800 Seri... | 26    | i2c_i801   | 8DF8DAD46F |
| 8086:0f12 | 1043:161d | Intel      | Atom Processor E3800 Seri... | 26    | i2c_i801   | 7BE60A0A2C |
| 8086:1e22 | 104d:90ab | Intel      | 7 Series/C216 Chipset Fam... | 26    | i2c_i801   | A8AF2E8A8D |
| 8086:2930 | 144d:c059 | Intel      | 82801I (ICH9 Family) SMBu... | 26    | i2c_i801   | 809DA0D1B4 |
| 8086:3b30 | 1025:036d | Intel      | 5 Series/3400 Series Chip... | 26    | i2c_i801   | D16FFC45F1 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e20 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 301   | snd_hda... | 8CE0C08E9A |
| 8086:1c20 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 187   | snd_hda... | 89EF922929 |
| 8086:0a0c | 17aa:3978 | Intel      | Haswell-ULT HD Audio Cont... | 114   | snd_hda... | 972580DCF6 |
| 8086:9c20 | 17aa:3978 | Intel      | 8 Series HD Audio Controller | 114   | snd_hda... | 972580DCF6 |
| 8086:0c0c | 8086:2010 | Intel      | Xeon E3-1200 v3/4th Gen C... | 113   | snd_hda... | A8BE285B93 |
| 8086:3b56 | 17aa:215e | Intel      | 5 Series/3400 Series Chip... | 102   | snd_hda... | 9A495F134B |
| 8086:293e | 17aa:20f2 | Intel      | 82801I (ICH9 Family) HD A... | 100   | snd_hda... | 1A90AC4588 |
| 8086:1e20 | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 88    | snd_hda... | 7857E6A77B |
| 8086:293e | 17aa:3a0d | Intel      | 82801I (ICH9 Family) HD A... | 85    | snd_hda... | 5986AA0AAC |
| 8086:3b56 | 17aa:38af | Intel      | 5 Series/3400 Series Chip... | 83    | snd_hda... | 15789D122D |
| 8086:1c20 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 80    | snd_hda... | 25D909CC38 |
| 8086:1e20 | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 75    | snd_hda... | 1C3C62EC29 |
| 8086:284b | 1025:011f | Intel      | 82801H (ICH8 Family) HD A... | 71    | snd_hda... | BA9EFF4F3B |
| 8086:1e20 | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 69    | snd_hda... | 9084C70732 |
| 8086:1e20 | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 68    | snd_hda... | EFE09AFB77 |
| 8086:27d8 | 1043:8437 | Intel      | NM10/ICH7 Family High Def... | 68    | snd_hda... | DEAF7BC089 |
| 8086:1c20 | 1043:1ac3 | Intel      | 6 Series/C200 Series Chip... | 67    | snd_hda... | 47A635ACC1 |
| 8086:3b56 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 64    | snd_hda... | 53ECD14649 |
| 1002:9840 | 17aa:3801 | AMD        | Kabini HDMI/DP Audio         | 63    | snd_hda... | 363B08984A |
| 1022:780d | 17aa:3801 | AMD        | FCH Azalia Controller        | 63    | snd_hda... | 363B08984A |
| 10de:0bea |           | Nvidia     | GF108 High Definition Aud... | 62    | snd_hda... | 2512ED1F69 |
| 8086:8c20 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 61    | snd_hda... | F21C5B69B8 |
| 8086:0c0c | 17aa:3978 | Intel      | Xeon E3-1200 v3/4th Gen C... | 60    | snd_hda... | 239616AC43 |
| 8086:0f04 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 59    | snd_hda... | F2797B8B83 |
| 8086:0a0c | 8086:2010 | Intel      | Haswell-ULT HD Audio Cont... | 58    | snd_hda... | 64EDCECFF8 |
| 8086:1e20 | 1043:118f | Intel      | 7 Series/C216 Chipset Fam... | 58    | snd_hda... | B2FB796FAB |
| 8086:3b56 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 56    | snd_hda... | 90D3759348 |
| 8086:284b | 17aa:20ac | Intel      | 82801H (ICH8 Family) HD A... | 55    | snd_hda... | FB1CD7BF88 |
| 8086:27d8 | 1025:0349 | Intel      | NM10/ICH7 Family High Def... | 54    | snd_hda... | A911172500 |
| 8086:1c20 | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 52    | snd_hda... | 4DB132BB33 |
| 8086:1e20 | 17aa:5011 | Intel      | 7 Series/C216 Chipset Fam... | 50    | snd_hda... | 82A9861AFD |
| 8086:1c20 | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 49    | snd_hda... | 0BF9EE57AF |
| 1002:1714 | 1002:1714 | AMD        | BeaverCreek HDMI Audio [R... | 48    | snd_hda... | 350BDA07BC |
| 8086:1c20 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 48    | snd_hda... | F3FBF8BC70 |
| 8086:3b56 | 1043:1643 | Intel      | 5 Series/3400 Series Chip... | 48    | snd_hda... | 088FFC2823 |
| 1002:15b3 | 103c:8330 | AMD        | High Definition Audio Con... | 47    | snd_hda... | E26638D750 |
| 1022:157a | 103c:8330 | AMD        | Family 15h (Models 60h-6f... | 47    | snd_hda... | E26638D750 |
| 8086:1c20 | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 47    | snd_hda... | DF459BC2B0 |
| 8086:293e | 1111:1043 | Intel      | 82801I (ICH9 Family) HD A... | 47    | snd_hda... | 33E615851D |
| 1002:15de | 1002:15de | AMD        | Raven/Raven2/Fenghuang HD... | 46    | snd_hda... | 9809687258 |
| 8086:27d8 | 1043:841c | Intel      | NM10/ICH7 Family High Def... | 46    | snd_hda... | A6B1293F94 |
| 8086:1c20 | 1043:1b43 | Intel      | 6 Series/C200 Series Chip... | 45    | snd_hda... | E9DCCED0F7 |
| 8086:1e20 | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 44    | snd_hda... | B162D0FD81 |
| 1002:4383 | 1043:1339 | AMD        | SBx00 Azalia (Intel HDA)     | 43    | snd_hda... | 6C6A2138D2 |
| 1002:9902 | 144d:c0da | AMD        | Trinity HDMI Audio Contro... | 43    | snd_hda... | 047093E08D |
| 1022:780d | 144d:c0da | AMD        | FCH Azalia Controller        | 43    | snd_hda... | 047093E08D |
| 8086:0a0c | 1025:0866 | Intel      | Haswell-ULT HD Audio Cont... | 43    | snd_hda... | 3FD761163B |
| 8086:1e20 | 17aa:21f6 | Intel      | 7 Series/C216 Chipset Fam... | 42    | snd_hda... | 1949413DC7 |
| 1002:aa38 | 1002:aa38 | AMD        | RV710/730 HDMI Audio [Rad... | 41    | snd_hda... | E835F92F9B |
| 8086:1c20 | 144d:c0b6 | Intel      | 6 Series/C200 Series Chip... | 41    | snd_hda... | 5118CD27DD |
| 8086:27d8 | 1043:8516 | Intel      | NM10/ICH7 Family High Def... | 41    | snd_hda... | ECB853F69D |
| 8086:284b | 1043:1339 | Intel      | 82801H (ICH8 Family) HD A... | 41    | snd_hda... | 427546EA21 |
| 8086:1c20 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 40    | snd_hda... | CA779DE74C |
| 8086:293e | 1025:0212 | Intel      | 82801I (ICH9 Family) HD A... | 40    | snd_hda... | CCC2EA91E1 |
| 8086:5a98 | 1043:12e0 | Intel      | Celeron N3350/Pentium N42... | 40    | snd_hda... | F885D0EE5F |
| 1002:aa68 | 1043:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 39    | snd_hda... | 088FFC2823 |
| 1022:15e3 | 1043:1b70 | AMD        | Family 17h (Models 10h-1f... | 39    | snd_hda... | EF7FEC98F2 |
| 8086:1e20 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 39    | snd_hda... | D28ACFF1E6 |
| 8086:0f04 | 17aa:3909 | Intel      | Atom Processor Z36xxx/Z37... | 38    | snd_hda... | 7D85F9BFAB |
| 1002:15b3 | 1025:1192 | AMD        | High Definition Audio Con... | 37    | snd_hda... | 17E62D31B9 |
| 1022:157a | 1025:1192 | AMD        | Family 15h (Models 60h-6f... | 37    | snd_hda... | 17E62D31B9 |
| 8086:1c20 | 104d:908b | Intel      | 6 Series/C200 Series Chip... | 37    | snd_hda... | A9E0A905BD |
| 8086:1e20 | 144d:c652 | Intel      | 7 Series/C216 Chipset Fam... | 37    | snd_hda... | 7F741A485F |
| 8086:9ca0 | 1043:19ad | Intel      | Wildcat Point-LP High Def... | 37    | snd_hda... | DF4413AF58 |
| 1002:1314 | 1043:104c | AMD        | Wrestler HDMI Audio          | 36    | snd_hda... | AE90CAFD98 |
| 1002:4383 | 1043:104c | AMD        | SBx00 Azalia (Intel HDA)     | 36    | snd_hda... | AE90CAFD98 |
| 8086:293e | 144d:c06d | Intel      | 82801I (ICH9 Family) HD A... | 36    | snd_hda... | 3A86D13DA1 |
| 8086:0a0c | 17aa:220c | Intel      | Haswell-ULT HD Audio Cont... | 35    | snd_hda... | 14015A6CDE |
| 8086:1e20 | 1043:1c33 | Intel      | 7 Series/C216 Chipset Fam... | 35    | snd_hda... | AA793ABA9F |
| 8086:27d8 | 1025:0090 | Intel      | NM10/ICH7 Family High Def... | 35    | snd_hda... | 5979EB4500 |
| 8086:3b56 | 1043:13f3 | Intel      | 5 Series/3400 Series Chip... | 35    | snd_hda... | 4DDE29EA59 |
| 10de:0fb9 |           | Nvidia     | GP107GL High Definition A... | 34    | snd_hda... | 98395B298B |
| 8086:0a0c | 1025:0775 | Intel      | Haswell-ULT HD Audio Cont... | 34    | snd_hda... | 94CD691A35 |
| 8086:1e20 | 144d:c0d8 | Intel      | 7 Series/C216 Chipset Fam... | 34    | snd_hda... | C5694CCAC0 |
| 8086:1e20 | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 34    | snd_hda... | AFB801A018 |
| 8086:27d8 | 144d:c072 | Intel      | NM10/ICH7 Family High Def... | 34    | snd_hda... | 60127AB94A |
| 8086:284b | 1028:01f9 | Intel      | 82801H (ICH8 Family) HD A... | 34    | snd_hda... | 4908DA86B8 |
| 8086:293e | 1028:0233 | Intel      | 82801I (ICH9 Family) HD A... | 34    | snd_hda... | 314E0FF832 |
| 8086:3198 | 1043:1de0 | Intel      | Smart Sound Technology (I... | 34    | snd_hda... | 59974C206C |
| 1002:4383 | 103c:3577 | AMD        | SBx00 Azalia (Intel HDA)     | 33    | snd_hda... | 758C395C78 |
| 1002:4383 | 17aa:397b | AMD        | SBx00 Azalia (Intel HDA)     | 33    | snd_hda... | 54094B2977 |
| 1002:9902 | 17aa:397c | AMD        | Trinity HDMI Audio Contro... | 33    | snd_hda... | 5F1837A6B4 |
| 1022:780d | 17aa:397c | AMD        | FCH Azalia Controller        | 33    | snd_hda... | 5F1837A6B4 |
| 8086:1e20 | 10cf:1757 | Intel      | 7 Series/C216 Chipset Fam... | 33    | snd_hda... | DA5836E2AA |
| 8086:27d8 | 1025:0590 | Intel      | NM10/ICH7 Family High Def... | 33    | snd_hda... | 326A5F97CA |
| 8086:3b56 | 144d:c07f | Intel      | 5 Series/3400 Series Chip... | 33    | snd_hda... | A3F9F98355 |
| 8086:9d71 | 17aa:3837 | Intel      | Sunrise Point-LP HD Audio    | 33    | snd_hda... | 91D8C5CEC3 |
| 8086:0a0c | 1028:0651 | Intel      | Haswell-ULT HD Audio Cont... | 32    | snd_hda... | DBD15FDF3D |
| 8086:2284 | 1025:1012 | Intel      | Atom/Celeron/Pentium Proc... | 32    | snd_hda... | 0949108352 |
| 8086:3b56 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 32    | snd_hda... | 3E3F341EF4 |
| 8086:9c20 | 1028:0651 | Intel      | 8 Series HD Audio Controller | 32    | snd_hda... | DBD15FDF3D |
| 10de:0ac0 | 10de:cb79 | Nvidia     | MCP79 High Definition Audio  | 31    | snd_hda... | 441575D073 |
| 8086:0a0c | 1043:131d | Intel      | Haswell-ULT HD Audio Cont... | 31    | snd_hda... | 9F136B8761 |
| 8086:0f04 | 1043:14dd | Intel      | Atom Processor Z36xxx/Z37... | 31    | snd_hda... | CC9B263062 |
| 8086:1e20 | 1025:0686 | Intel      | 7 Series/C216 Chipset Fam... | 31    | snd_hda... | 1F28286A78 |
| 8086:1e20 | 1043:1587 | Intel      | 7 Series/C216 Chipset Fam... | 31    | snd_hda... | A14ECCA066 |
| 8086:3b56 | 144d:c581 | Intel      | 5 Series/3400 Series Chip... | 31    | snd_hda... | D9ECE67AC1 |
| 8086:9c20 | 1025:0775 | Intel      | 8 Series HD Audio Controller | 31    | snd_hda... | 94CD691A35 |
| 8086:9c20 | 1043:11af | Intel      | 8 Series HD Audio Controller | 31    | snd_hda... | 9F136B8761 |
| 1002:15b3 | 17aa:380b | AMD        | High Definition Audio Con... | 30    | snd_hda... | 8B23CB3E69 |

### Storage (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 104c:803b | 1025:011f | Texas I... | PCIxx12 Flash Media Contr... | 71    | tifm_7xx1  | BA9EFF4F3B |
| 1217:8231 | 1028:0493 | O2 Micro   | O2Micro Integrated MS/MSP... | 39    |            | CA779DE74C |
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
| 104c:803b | 104d:81e6 | Texas I... | PCIxx12 Flash Media Contr... | 7     | tifm_7xx1  | 047C3A9402 |
| 104c:803b | 104d:9005 | Texas I... | PCIxx12 Flash Media Contr... | 7     | tifm_7xx1  | 9B1280E7FC |
| 104c:803b | 1025:011c | Texas I... | PCIxx12 Flash Media Contr... | 6     | tifm_7xx1  | AD2D03638A |
| 104c:803b | 104d:9016 | Texas I... | PCIxx12 Flash Media Contr... | 6     | tifm_7xx1  | FF1CDF1811 |
| 1217:7130 | 10cf:14d6 | O2 Micro   | Integrated MS/xD Controller  | 6     |            | 751064E2A2 |
| 104c:8033 | 1179:ff05 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 5     | tifm_7xx1  | 8488B3D0B9 |
| 104c:803b | 103c:30aa | Texas I... | PCIxx12 Flash Media Contr... | 5     | tifm_7xx1  | 9C1BF7D811 |
| 104c:803b | 104d:8212 | Texas I... | PCIxx12 Flash Media Contr... | 5     | tifm_7xx1  | B389939EE8 |
| 1217:8130 | 1179:ff50 | O2 Micro   | Integrated MS/MSPRO/xD Co... | 5     |            | 60D901703E |
| 1217:8330 | 1028:04a4 | O2 Micro   | OZ600 MS/xD Controller       | 5     |            | 2A2FBFB933 |
| 104c:8033 | 1025:0066 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 4     | tifm_7xx1  | 50122B9E8E |
| 104c:8033 | 103c:0944 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 4     | tifm_7xx1  | A770CF025E |
| 104c:8033 | 1179:0001 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 4     | tifm_7xx1  | D5D7DAB02F |
| 104c:8033 | 17c0:3007 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 4     | tifm_7xx1  | EFDFFC9FB6 |
| 104c:803b | 1025:0130 | Texas I... | PCIxx12 Flash Media Contr... | 4     | tifm_7xx1  | 2165E8969A |
| 1217:7130 | 1025:012b | O2 Micro   | Integrated MS/xD Controller  | 4     |            | 21509117BA |
| 1217:7130 | 1028:0273 | O2 Micro   | Integrated MS/xD Controller  | 4     |            | C9D61D9E11 |
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
| 1217:7130 | 1028:026f | O2 Micro   | Integrated MS/xD Controller  | 3     |            | 20788C640E |
| 1217:7130 | 1462:3ff3 | O2 Micro   | Integrated MS/xD Controller  | 3     |            | A249DABAD8 |
| 1217:8231 | 1028:04a9 | O2 Micro   | O2Micro Integrated MS/MSP... | 3     |            | F3F87090B3 |
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
| 1217:7130 | 1025:011a | O2 Micro   | Integrated MS/xD Controller  | 2     |            | 69380B60FC |
| 1217:7130 | 1025:0124 | O2 Micro   | Integrated MS/xD Controller  | 2     |            | 5AAFE28787 |
| 1217:7130 | 1028:0275 | O2 Micro   | Integrated MS/xD Controller  | 2     |            | B0314C0713 |
| 1217:7130 | 1462:3fc1 | O2 Micro   | Integrated MS/xD Controller  | 2     |            | 278EF4A255 |
| 1217:7130 | 1734:10c7 | O2 Micro   | Integrated MS/xD Controller  | 2     |            | 6E3970FC39 |
| 104c:8033 | 1025:0067 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | A260AE3290 |
| 104c:8033 | 1025:007e | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | FAC1D78802 |
| 104c:8033 | 103c:099c | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | AFE75774F3 |
| 104c:8033 | 103c:3081 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | 1481661DEB |
| 104c:8033 | 103c:3082 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | 91C7AE2180 |
| 104c:8033 | 103c:3091 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | 30D7D605F7 |
| 104c:8033 | 103c:309b | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | 88BD859F3F |
| 104c:8033 | 104d:81e2 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | C7597917F8 |
| 104c:8033 | 107b:0460 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | B62ECA10E8 |
| 104c:8033 | 161f:203d | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | E244649FAC |
| 104c:8033 | 1631:c00a | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | AD3BB711D8 |
| 104c:8033 | 1734:1098 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | 0328C9BAD3 |
| 104c:8033 | 1854:0031 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | 18F757F572 |
| 104c:8033 | 1854:0085 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | 0170F7F468 |
| 104c:8033 | 1854:010c | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | 253B1DAE47 |
| 104c:803b |           | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | E65D36DCAA |
| 104c:803b | 1025:0101 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 153247F60A |
| 104c:803b | 1025:010e | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | C4C9F4E659 |
| 104c:803b | 1025:0112 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 9823532B00 |
| 104c:803b | 1025:0129 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 4F1C235318 |
| 104c:803b | 103c:30ad | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 9F51D8D813 |
| 104c:803b | 104d:81fc | Texas I... | PCIxx12 Flash Media Contr... | 1     |            | 7F0BB0CC92 |
| 104c:803b | 104d:81fd | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 7DFBCB9E53 |
| 104c:803b | 104d:8207 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 76350B5F91 |
| 104c:803b | 104d:900f | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 3A190D628A |
| 104c:803b | 104d:9018 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 8A814A5779 |
| 104c:803b | 1071:8212 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 01F778FE4E |
| 104c:803b | 107b:0366 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 668DB92873 |
| 104c:803b | 107b:0685 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 543C2B2F79 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e03 | 17aa:3977 | Intel      | 7 Series Chipset Family 6... | 274   | ahci       | 8CE0C08E9A |
| 8086:1c03 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 170   | ahci       | 89EF922929 |
| 8086:27c1 | 1043:83ad | Intel      | NM10/ICH7 Family SATA Con... | 170   | ahci       | A6B1293F94 |
| 8086:9c03 | 17aa:3978 | Intel      | 8 Series SATA Controller ... | 113   | ahci       | 972580DCF6 |
| 8086:2929 | 17aa:20f8 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 87    | ahci       | 1A90AC4588 |
| 8086:1c03 | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 85    | ahci       | B7B1C7DF29 |
| 8086:1e03 | 1025:0649 | Intel      | 7 Series Chipset Family 6... | 85    | ahci       | 7857E6A77B |
| 8086:3b2f | 17aa:2168 | Intel      | 5 Series/3400 Series Chip... | 84    | ahci       | 9A495F134B |
| 8086:3b29 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 83    | ahci       | 088FFC2823 |
| 8086:3b29 | 17aa:38c1 | Intel      | 5 Series/3400 Series Chip... | 78    | ahci       | 15789D122D |
| 8086:1c03 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 77    | ahci       | 25D909CC38 |
| 8086:1e03 | 17aa:5002 | Intel      | 7 Series Chipset Family 6... | 73    | ahci       | 1C3C62EC29 |
| 8086:2929 | 17aa:3a1a | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 73    | ahci       | 5986AA0AAC |
| 8086:1c03 | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 67    | ahci       | 47A635ACC1 |
| 8086:1e03 | 1025:0647 | Intel      | 7 Series Chipset Family 6... | 66    | ahci       | 9084C70732 |
| 8086:1e03 | 1043:124d | Intel      | 7 Series Chipset Family 6... | 66    | ahci       | 179397B4EA |
| 8086:1e03 | 1025:064b | Intel      | 7 Series Chipset Family 6... | 63    | ahci       | EFE09AFB77 |
| 1022:7801 | 17aa:3801 | AMD        | FCH SATA Controller [AHCI... | 60    | ahci       | 363B08984A |
| 8086:3b29 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 57    | ahci       | 53ECD14649 |
| 8086:3b29 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 56    | ahci       | 90D3759348 |
| 8086:8c03 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 56    | ahci       | 239616AC43 |
| 8086:0f23 | 17aa:3905 | Intel      | Atom Processor E3800 Seri... | 55    | ahci       | F2797B8B83 |
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 53    | ahci       | 97BCBB884E |
| 8086:1c03 | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 50    | ahci       | 4DB132BB33 |
| 8086:1c03 | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 49    | ahci       | 0BF9EE57AF |
| 8086:1e03 | 8086:7270 | Intel      | 7 Series Chipset Family 6... | 48    | ahci       | D28ACFF1E6 |
| 1022:7904 | 103c:8330 | AMD        | FCH SATA Controller [AHCI... | 47    | ahci       | E26638D750 |
| 8086:27c1 | 1025:0349 | Intel      | NM10/ICH7 Family SATA Con... | 47    | ahci       | A911172500 |
| 8086:1c03 | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 46    | ahci       | DF459BC2B0 |
| 8086:1c03 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 46    | ahci       | F3FBF8BC70 |
| 8086:1e03 | 1043:14c7 | Intel      | 7 Series Chipset Family 6... | 44    | ahci       | 12F5A59D53 |
| 8086:1e03 | 17aa:5011 | Intel      | 7 Series Chipset Family 6... | 44    | ahci       | 92C25DEB31 |
| 1022:7804 | 144d:c0da | AMD        | FCH SATA Controller [AHCI... | 43    | ahci       | 047093E08D |
| 8086:9c03 | 1025:0866 | Intel      | 8 Series SATA Controller ... | 43    | ahci       | 3FD761163B |
| 8086:2829 | 17aa:20a7 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 42    | ahci       | FB1CD7BF88 |
| 1002:4391 | 1043:1117 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 41    | ahci       | E9F680E72A |
| 8086:1c03 | 144d:c0b6 | Intel      | 6 Series/C200 Series Chip... | 40    | ahci       | 5CBDF51766 |
| 8086:1e03 | 17aa:21f3 | Intel      | 7 Series Chipset Family 6... | 40    | ahci       | B162D0FD81 |
| 8086:2929 | 1043:1867 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 40    | ahci       | 33E615851D |
| 8086:5ae3 | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 40    | ahci       | F885D0EE5F |
| 8086:0f23 | 17aa:3909 | Intel      | Atom Processor E3800 Seri... | 38    | ahci       | 7D85F9BFAB |
| 8086:1e03 | 17aa:21f6 | Intel      | 7 Series Chipset Family 6... | 38    | ahci       | D0B40A5BE3 |
| 1022:7901 | 1025:1192 | AMD        | FCH SATA Controller [AHCI... | 37    | ahci       | 17E62D31B9 |
| 8086:1c03 | 104d:908b | Intel      | 6 Series/C200 Series Chip... | 37    | ahci       | A9E0A905BD |
| 8086:1e03 | 144d:c652 | Intel      | 7 Series Chipset Family 6... | 37    | ahci       | 7F741A485F |
| 8086:2829 | 1025:011f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 36    | ahci       | BA9EFF4F3B |
| 8086:2929 | 1025:0212 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 36    | ahci       | EC1EF6DC07 |
| 8086:1e03 | 1043:1477 | Intel      | 7 Series Chipset Family 6... | 35    | ahci       | C005B421A9 |
| 8086:9c03 | 17aa:220c | Intel      | 8 Series SATA Controller ... | 35    | ahci       | 14015A6CDE |
| 8086:1e03 | 1179:fb31 | Intel      | 7 Series Chipset Family 6... | 34    | ahci       | A0FFB29C6C |
| 8086:1e03 | 144d:c0d8 | Intel      | 7 Series Chipset Family 6... | 34    | ahci       | C5694CCAC0 |
| 8086:31e3 | 1043:1261 | Intel      | SATA controller              | 34    | ahci       | 59974C206C |
| 8086:9c03 | 1025:0775 | Intel      | 8 Series SATA Controller ... | 34    | ahci       | 94CD691A35 |
| 1002:4391 | 103c:3577 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 33    | ahci       | 758C395C78 |
| 1022:7801 | 17aa:397c | AMD        | FCH SATA Controller [AHCI... | 33    | ahci       | 5F1837A6B4 |
| 8086:1e03 | 1043:1587 | Intel      | 7 Series Chipset Family 6... | 33    | ahci       | A14ECCA066 |
| 8086:1e03 | 17aa:21fa | Intel      | 7 Series Chipset Family 6... | 33    | ahci       | AFB801A018 |
| 8086:2929 | 144d:c06d | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 33    | ahci       | 3A86D13DA1 |
| 8086:9d03 | 17aa:386a | Intel      | Sunrise Point-LP SATA Con... | 33    | ahci       | 91D8C5CEC3 |
| 8086:22a3 | 1025:1012 | Intel      | Atom/Celeron/Pentium Proc... | 32    | ahci       | 0949108352 |
| 8086:9c03 | 1028:0651 | Intel      | 8 Series SATA Controller ... | 32    | ahci       | DBD15FDF3D |
| 1002:4391 | 1043:104c | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 31    | ahci       | 72756E903E |
| 8086:0f23 | 1043:14dd | Intel      | Atom Processor E3800 Seri... | 31    | ahci       | CC9B263062 |
| 8086:1c03 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 31    | ahci       | 2B202B204B |
| 8086:1e03 | 10cf:16e2 | Intel      | 7 Series Chipset Family 6... | 31    | ahci       | DA5836E2AA |
| 8086:9c03 | 1043:131d | Intel      | 8 Series SATA Controller ... | 31    | ahci       | 9F136B8761 |
| 8086:9d03 | 1025:1193 | Intel      | Sunrise Point-LP SATA Con... | 31    | ahci       | 02EEEC88C4 |
| 1022:7901 | 17aa:380a | AMD        | FCH SATA Controller [AHCI... | 30    | ahci       | 8B23CB3E69 |
| 8086:1e03 | 1025:0686 | Intel      | 7 Series Chipset Family 6... | 30    | ahci       | B535D08C79 |
| 8086:27c1 | 144d:c072 | Intel      | NM10/ICH7 Family SATA Con... | 30    | ahci       | 60127AB94A |
| 8086:3b29 | 144d:c07f | Intel      | 5 Series/3400 Series Chip... | 30    | ahci       | A3F9F98355 |
| 8086:3b29 | 144d:c581 | Intel      | 5 Series/3400 Series Chip... | 30    | ahci       | D9ECE67AC1 |
| 1022:7804 | 103c:184a | AMD        | FCH SATA Controller [AHCI... | 29    | ahci       | 4C72CE34FA |
| 8086:1e03 | 104d:90b8 | Intel      | 7 Series Chipset Family 6... | 29    | ahci       | B9133671A8 |
| 8086:2829 | 103c:30cc | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 29    | ahci       | 218FD78ECA |
| 8086:9d03 | 1025:1085 | Intel      | Sunrise Point-LP SATA Con... | 29    | ahci       | 8BC74BD7FB |
| 10de:0ab9 | 10de:cb79 | Nvidia     | MCP79 AHCI Controller        | 28    | ahci       | 441575D073 |
| 197b:2360 | 1043:1348 | JMicron... | JMB360 AHCI Controller       | 28    | ahci       | 0860A0C8E0 |
| 8086:1c03 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 28    | ahci       | DA7FEA9DD2 |
| 8086:2829 | 1028:022f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 28    | ahci       | 56866B9E4C |
| 1022:7801 | 17aa:3802 | AMD        | FCH SATA Controller [AHCI... | 27    | ahci       | AAC48DC435 |
| 8086:0f23 | 1297:2041 | Intel      | Atom Processor E3800 Seri... | 27    | ahci       | 199C248CC1 |
| 8086:9c03 | 1043:16cd | Intel      | 8 Series SATA Controller ... | 27    | ahci       | 786924EC40 |
| 8086:9d03 | 1025:115f | Intel      | Sunrise Point-LP SATA Con... | 27    | ahci       | A230640EC7 |
| 1002:4391 | 1002:4390 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 26    | ahci       | 684866EE94 |
| 8086:0f23 | 103c:2213 | Intel      | Atom Processor E3800 Seri... | 26    | ahci       | 8DF8DAD46F |
| 8086:1c03 | 103c:161c | Intel      | 6 Series/C200 Series Chip... | 26    | ahci       | 3EAB448396 |
| 8086:1c03 | 1179:fc30 | Intel      | 6 Series/C200 Series Chip... | 26    | ahci       | A1569BC1E6 |
| 8086:1e03 | 104d:90ab | Intel      | 7 Series Chipset Family 6... | 26    | ahci       | A8AF2E8A8D |
| 8086:3b29 | 144d:c06a | Intel      | 5 Series/3400 Series Chip... | 26    | ahci       | EF6EEF8F3E |
| 8086:9c83 | 1025:098a | Intel      | Wildcat Point-LP SATA Con... | 26    | ahci       | 5861B2E713 |
| 8086:9d03 | 103c:832a | Intel      | Sunrise Point-LP SATA Con... | 26    | ahci       | 931D7104FA |
| 8086:3b29 | 1025:036d | Intel      | 5 Series/3400 Series Chip... | 25    | ahci       | D16FFC45F1 |
| 1002:4380 | 1028:01f5 | AMD        | SB600 Non-Raid-5 SATA        | 24    | ahci       | 3D6C8F2267 |
| 1002:4391 | 1025:0489 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 24    | ahci       | B99A6015C7 |
| 1022:7901 | 103c:84ae | AMD        | FCH SATA Controller [AHCI... | 24    | ahci       | 3B491B92B3 |
| 8086:1c03 | 103c:3388 | Intel      | 6 Series/C200 Series Chip... | 24    | ahci       | C7D96BB884 |
| 8086:1e03 | 103c:179b | Intel      | 7 Series Chipset Family 6... | 24    | ahci       | 7195452FF3 |
| 8086:1e03 | 103c:17f6 | Intel      | 7 Series Chipset Family 6... | 24    | ahci       | 1F9408B984 |
| 8086:a353 | 1028:087c | Intel      | Cannon Lake Mobile PCH SA... | 24    | ahci       | 18DC19F3EC |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2850 | 1025:011f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 71    | ata_pii... | BA9EFF4F3B |
| 8086:2850 | 17aa:20a6 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 42    | pata_acpi  | FB1CD7BF88 |
| 8086:2828 | 1025:011f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 37    | ata_pii... | F641323C9D |
| 1002:439c | 1043:104c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 36    | pata_at... | AE90CAFD98 |
| 1039:5513 | 1039:5513 | Silicon... | 5513 IDE Controller          | 34    | pata_si... | 1E2E967880 |
| 8086:2850 | 1028:01f9 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 34    | ata_pii... | 4908DA86B8 |
| 8086:1e01 | 17aa:3977 | Intel      | 7 Series Chipset Family 4... | 29    | ata_pii... | E1DE6C6DC3 |
| 8086:2850 | 1028:022f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 29    | pata_acpi  | 56866B9E4C |
| 8086:2850 | 103c:30cc | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 29    | ata_pii... | 218FD78ECA |
| 8086:27c4 | 1025:0090 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 28    | ata_pii... | 17F0CF7EA2 |
| 8086:2828 | 1028:01f9 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 27    | ata_pii... | 4908DA86B8 |
| 1002:4376 | 1025:009f | AMD        | IXP SB4x0 IDE Controller     | 26    | pata_at... | 005CF3D43E |
| 8086:1e09 | 17aa:3977 | Intel      | 7 Series Chipset Family 2... | 26    | ata_pii... | E1DE6C6DC3 |
| 1002:438c | 1028:01f5 | AMD        | SB600 IDE                    | 24    | pata_at... | 3D6C8F2267 |
| 1039:1183 | 1039:1183 | Silicon... | SATA Controller / IDE mode   | 24    | sata_si... | 1E2E967880 |
| 8086:1c01 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 24    | ata_pii... | 1872DCA02C |
| 8086:1c09 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 24    | ata_pii... | 1872DCA02C |
| 8086:2850 | 1025:011e | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 24    | ata_pii... | 3530E5C8F1 |
| 8086:2850 | 1025:0136 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 24    | ata_pii... | EDE5F01079 |
| 10de:0759 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] IDE    | 23    | pata_am... | D672B4583E |
| 10de:0ad0 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] SAT... | 23    | ahci, p... | D672B4583E |
| 1002:4379 | 1002:4379 | AMD        | IXP SB4x0 Serial ATA Cont... | 21    | sata_si... | 005CF3D43E |
| 1002:438c | 1043:1627 | AMD        | SB600 IDE                    | 21    | pata_at... | 6C6A2138D2 |
| 8086:27c0 | 1043:83ad | Intel      | NM10/ICH7 Family SATA Con... | 21    | ata_pii... | D0AFCBE081 |
| 8086:27df | 17aa:3810 | Intel      | 82801G (ICH7 Family) IDE ... | 21    | ata_pii... | CA79C7E0E9 |
| 1039:1183 | 1043:1cf7 | Silicon... | SATA Controller / IDE mode   | 20    | sata_si... | 907647C4E8 |
| 1039:5513 | 1043:1cf7 | Silicon... | 5513 IDE Controller          | 20    | pata_si... | 907647C4E8 |
| 10de:0550 | 1025:0126 | Nvidia     | MCP67 AHCI Controller        | 20    | pata_ac... | 590A68AE68 |
| 8086:27c4 | 1179:ff00 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 20    | ata_pii... | CCB7CB26D3 |
| 8086:2850 | 1025:0121 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 20    | ata_pii... | C1C791C270 |
| 8086:2850 | 1179:ff00 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 19    | ata_pii... | 087C0E291D |
| 1039:1183 | 1043:19e7 | Silicon... | SATA Controller / IDE mode   | 18    | sata_si... | 14EEC92B5D |
| 1039:5513 | 1043:19e7 | Silicon... | 5513 IDE Controller          | 18    | pata_si... | 14EEC92B5D |
| 8086:27df | 103c:30a2 | Intel      | 82801G (ICH7 Family) IDE ... | 18    | ata_pii... | 527BA99CD2 |
| 8086:27df | 8086:7270 | Intel      | 82801G (ICH7 Family) IDE ... | 18    | pata_acpi  | 3A660A2575 |
| 8086:27c4 | 1043:1317 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 17    | ata_pii... | 4841CD6D3C |
| 1002:438c | 144d:c034 | AMD        | SB600 IDE                    | 16    | pata_at... | 9A7F6FCF9E |
| 1002:439c | 17aa:3937 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 16    | pata_at... | 5BD0975D5C |
| 1039:1183 | 1039:1180 | Silicon... | SATA Controller / IDE mode   | 16    | sata_si... | 8C665A5EB1 |
| 10de:0550 | 103c:30cf | Nvidia     | MCP67 AHCI Controller        | 16    | ahci, p... | 1031D661DB |
| 8086:27c4 | 1028:01bd | Intel      | 82801GBM/GHM (ICH7-M Fami... | 16    | ata_pii... | AB555162C8 |
| 8086:27c4 | 1179:ff10 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 16    | ata_pii... | 5FDCE37F38 |
| 8086:2a46 | 17aa:20ea | Intel      | Mobile 4 Series Chipset P... | 16    | pata_acpi  | 7AD5A75B0A |
| 1002:438c | 1043:1417 | AMD        | SB600 IDE                    | 15    | pata_at... | 54C92BF69C |
| 1002:438c | 144d:c511 | AMD        | SB600 IDE                    | 15    | pata_at... | FA196B80FA |
| 10de:0560 | 1025:0126 | Nvidia     | MCP67 IDE Controller         | 15    | pata_am... | 4521FFBD6D |
| 8086:27c4 | 1025:015b | Intel      | 82801GBM/GHM (ICH7-M Fami... | 15    | ata_pii... | E0500C7CE3 |
| 8086:27c4 | 8086:7270 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 15    | pata_acpi  | 3A660A2575 |
| 8086:2850 | 103c:30d8 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 15    | ata_pii... | CA22DF90DC |
| 8086:2850 | 103c:30d9 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 15    | pata_acpi  | CB550F69F7 |
| 8086:2850 | 1179:ff50 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 15    | ata_pii... | 6108B0C47E |
| 1002:438c | 103c:30c2 | AMD        | SB600 IDE                    | 14    | pata_at... | 0FDD28110E |
| 1022:780c | 1028:04b1 | AMD        | FCH IDE Controller           | 14    | pata_at... | 7873FB02D1 |
| 8086:2653 | 1014:056a | Intel      | 82801FBM (ICH6M) SATA Con... | 14    | ata_gen... | BABCA7BCDE |
| 8086:27c4 | 1028:01c2 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 14    | ata_pii... | 48CAE00098 |
| 8086:27c4 | 1043:830f | Intel      | 82801GBM/GHM (ICH7-M Fami... | 14    | ata_pii... | 05370DB3D6 |
| 8086:27df | 17aa:200c | Intel      | 82801G (ICH7 Family) IDE ... | 14    | ata_pii... | 3DAAC5C0C6 |
| 8086:2828 | 17aa:20a8 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 14    | ata_pii... | 6DC6A318E1 |
| 8086:2850 | 1043:14e7 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 14    | ata_pii... | 7AC6E3C864 |
| 8086:2850 | 1043:1517 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 13    | ata_pii... | 427546EA21 |
| 8086:2850 | 1179:ff1c | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 13    | ata_pii... | 420C738977 |
| 1002:439c | 1025:036e | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 12    | pata_at... | 9FBD6EB508 |
| 1002:439c | 1043:101c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 12    | pata_at... | C8A811D2FC |
| 1022:780c | 103c:358d | AMD        | FCH IDE Controller           | 12    | pata_at... | 10C6188426 |
| 8086:27c4 | 1025:0107 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 12    | ata_pii... | 290DB67DA7 |
| 8086:27c4 | 144d:ca00 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 12    | ata_pii... | FC7D577AB7 |
| 8086:27c4 | 1462:0110 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 12    | ata_pii... | 8E7A1F63E7 |
| 8086:27df | 1025:012e | Intel      | 82801G (ICH7 Family) IDE ... | 12    | ata_pii... | 48841846AC |
| 8086:27df | 103c:30d5 | Intel      | 82801G (ICH7 Family) IDE ... | 12    | ata_pii... | 445A4251A7 |
| 8086:2850 | 103c:30c0 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 12    | ata_pii... | 0323CDBA14 |
| 8086:2850 | 1043:1767 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 12    | ata_pii... | 4137AC8F54 |
| 1002:438c | 1028:022a | AMD        | SB600 IDE                    | 11    | pata_at... | 7043CC968E |
| 1002:439c | 1043:1067 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 11    | pata_at... | E69E0C49CF |
| 1022:780c | 103c:3593 | AMD        | FCH IDE Controller           | 11    | pata_at... | 4A75772380 |
| 1039:1183 | 1043:1a77 | Silicon... | SATA Controller / IDE mode   | 11    | sata_si... | 9B7F075594 |
| 1039:5513 | 1558:0801 | Silicon... | 5513 IDE Controller          | 11    | pata_acpi  | 7CEADDD485 |
| 10de:0560 | 103c:30cf | Nvidia     | MCP67 IDE Controller         | 11    | pata_am... | 1031D661DB |
| 8086:27df | 103c:30bb | Intel      | 82801G (ICH7 Family) IDE ... | 11    | ata_pii... | E6D736339F |
| 8086:2828 | 1028:029a | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 11    | ata_pii... | 394D903321 |
| 8086:2850 | 1043:1017 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 11    | ata_pii... | F3C9C1F265 |
| 8086:2850 | 106b:00a1 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 11    | pata_acpi  | A760ED1DA6 |
| 8086:2850 | 1179:ff64 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 11    | pata_acpi  | C21C72FEED |
| 8086:811a | 1025:0244 | Intel      | US15W/US15X/US15L/UL11L S... | 11    | pata_sc... | 508A9677AC |
| 1002:4376 | 1179:ff31 | AMD        | IXP SB4x0 IDE Controller     | 10    | pata_at... | 563F05AAE7 |
| 8086:27c0 | 1025:0590 | Intel      | NM10/ICH7 Family SATA Con... | 10    | ata_pii... | 326A5F97CA |
| 8086:27c4 | 17aa:200e | Intel      | 82801GBM/GHM (ICH7-M Fami... | 10    | pata_acpi  | 1DF2C0B1ED |
| 8086:27df | 10cf:1385 | Intel      | 82801G (ICH7 Family) IDE ... | 10    | pata_acpi  | B4AFED8FAD |
| 8086:2850 | 103c:30be | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 10    | pata_acpi  | 6ABE286091 |
| 8086:2928 | 17aa:20f7 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 10    | ata_piix   | 82BF41BAA8 |
| 8086:3b2d | 17aa:216a | Intel      | 5 Series/3400 Series Chip... | 10    | pata_acpi  | 18B034B977 |
| 8086:3b2e | 17aa:2169 | Intel      | 5 Series/3400 Series Chip... | 10    | pata_acpi  | 18B034B977 |
| 8086:811a | 1043:83ce | Intel      | US15W/US15X/US15L/UL11L S... | 10    | pata_sc... | 61837B2A0E |
| 1002:4379 | 1179:ff31 | AMD        | IXP SB4x0 Serial ATA Cont... | 9     | sata_si... | D1E500A1E6 |
| 1022:780c | 1043:14b7 | AMD        | FCH IDE Controller           | 9     | pata_at... | 6C12E2EE00 |
| 8086:2653 | 1043:82d8 | Intel      | 82801FBM (ICH6M) SATA Con... | 9     | ata_gen... | DF4FA2D486 |
| 8086:266f | 1028:01c9 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 9     | ata_pii... | 2533BAD4C1 |
| 8086:27c4 | 1025:0110 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 9     | ata_pii... | 9708C7ABC2 |
| 8086:27c4 | 17aa:3835 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 9     | ata_pii... | 876835D508 |
| 8086:2850 | 1028:01f2 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 9     | ata_pii... | 09BC8D2536 |
| 8086:2850 | 104d:902d | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 9     | ata_pii... | DE6F0F6D83 |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 213   | nvme       | 98395B298B |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 144   | nvme       | 65B1EB0CA1 |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 68    | nvme       | 961FA2224D |
| 15b7:5003 | 15b7:5003 | Sandisk    | WD Black 2018/PC SN520 NV... | 52    | nvme       | 686232836E |
| 1179:0113 | 1179:0001 | Toshiba... | BG3 NVMe SSD Controller      | 44    | nvme       | CE87F391CE |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | Non-Volatile memory contr... | 44    | nvme       | E4301E56F9 |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/PC SN720 NV... | 41    | nvme       | 17674B4CBD |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 41    | nvme       | F737A5A121 |
| 1c5c:1527 | 1c5c:1527 | SK Hynix   | Non-Volatile memory contr... | 39    | nvme       | B50C99FDF7 |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 38    | nvme       | 105FE15441 |
| 2646:5008 | 2646:5008 | Kingsto... | Non-Volatile memory contr... | 32    | nvme       | 2B46AD4F9B |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 29    | nvme       | A47D005445 |
| 1179:0115 | 1179:0001 | Toshiba... | XG4 NVMe SSD Controller      | 28    | nvme       | C04DAFDA20 |
| 1179:011a | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 22    | nvme       | 1820A998EC |
| 1179:010f | 1179:0001 | Toshiba... | NVMe Controller              | 21    | nvme       | 95BE835276 |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 21    | nvme       | DEB2849EF5 |
| 15b7:5005 | 15b7:5005 | Sandisk    | Non-Volatile memory contr... | 11    | nvme       | C65ABD0640 |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 11    | nvme       | AF51F8907E |
| c0a9:2263 | c0a9:2263 | Micron/... | P1 NVMe PCIe SSD             | 11    | nvme       | 971B99D081 |
| 14a4:2300 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 10    | nvme       | F473523657 |
| 1cc4:5008 | 1cc4:5008 | Union M... | Non-Volatile memory contr... | 8     | nvme       | 153F2AFA98 |
| 1344:5410 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 7     | nvme       | F2C853DD94 |
| 17aa:0004 | 17aa:1004 | Lenovo     | Non-Volatile memory contr... | 7     | nvme       | 7AB81DBD28 |
| 1c5c:1627 | 1c5c:1627 | SK Hynix   | Non-Volatile memory contr... | 7     | nvme       | 1F29F031C3 |
| 1e0f:0001 | 1e0f:0001 |            | Non-Volatile memory contr... | 7     | nvme       | 2B2912B5B0 |
| 15b7:5004 | 15b7:5004 | Sandisk    | Non-Volatile memory contr... | 6     | nvme       | 5C096F788D |
| 17aa:0003 | 17aa:1003 | Lenovo     | Non-Volatile memory contr... | 6     | nvme       | 4F055C0CF5 |
| 126f:2262 | 126f:2262 | Silicon... | Non-Volatile memory contr... | 5     | nvme       | BD1EBC8235 |
| 1987:5008 | 1987:5008 | Phison ... | NVMe Storage Controller      | 5     | nvme       | 859E021E2F |
| 14a4:2200 | 1b4b:1093 | Lite-On... | Lite-On Non-Volatile memo... | 4     | nvme       | 6092C7644C |
| 17aa:0006 | 17aa:1006 | Lenovo     | Non-Volatile memory contr... | 4     | nvme       | DE55B048C0 |
| 1c5c:1283 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 4     | nvme       | 3B65E519FC |
| 1c5c:1285 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 4     | nvme       | 260CB1A4B0 |
| 10ec:5762 | 10ec:5762 | Realtek... | Realtek Non-Volatile memo... | 3     | nvme       | 85BB9ECF3B |
| 14a4:2100 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 3     | nvme       | 1C54F7F564 |
| 15b7:5006 | 15b7:5006 | Sandisk    | Non-Volatile memory contr... | 3     | nvme       | E80AE71BD7 |
| 17aa:0005 | 17aa:1005 | Lenovo     | Non-Volatile memory contr... | 3     | nvme       | 444D60D6DA |
| 1c5c:1284 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 3     | nvme       | A549A39A12 |
| 1c5c:1504 | 0100:1093 | SK Hynix   | SC300 512GB M.2 2280 SATA... | 3     | nvme       | 58DDD64DA3 |
| 106b:2001 | 106b:2001 | Apple      | S1X NVMe Controller          | 2     | nvme       | 195DAC413B |
| 106b:2005 | 106b:1800 | Apple      | ANS2 NVMe Controller         | 2     |            | D3A040508D |
| 126f:2263 | 126f:2263 | Silicon... | Non-Volatile memory contr... | 2     | nvme       | 6616FE975F |
| 144d:a809 | 144d:a801 | Samsung... | Electronics Non-Volatile ... | 2     | nvme       | 5D6DDB0705 |
| 15b7:5001 | 1b4b:1093 | Sandisk    | WD Black NVMe SSD            | 2     | nvme       | B2B217C7BA |
| 1987:5007 | 1987:5007 | Phison ... | E7 NVMe Controller           | 2     | nvme       | 586FBB553D |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 2     | nvme       | 47182BD3E3 |
| 106b:2003 | 106b:2003 | Apple      | S3X NVMe Controller          | 1     | nvme       | E20833CAEE |
| 14a4:21f1 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 1     | nvme       | BB13C77033 |
| 14a4:22f1 | 1b4b:1093 | Lite-On... | M8Pe Series NVMe SSD         | 1     | nvme       | ED328FC569 |
| 14a4:23f1 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 1     | nvme       | FE49019BE0 |
| 14a4:5100 | 14a4:5100 | Lite-On... | Non-Volatile memory contr... | 1     | nvme       | 766158C703 |
| 14a4:9100 | 126f:2263 | Lite-On... | NVMe Controller              | 1     | nvme       | 2051B36B5B |
| 1bb1:5012 | 1bb1:5012 | Seagate... | Non-Volatile memory contr... | 1     | nvme       | 9013346F71 |
| 1cc4:5012 | 1cc4:5012 | Union M... | Non-Volatile memory contr... | 1     | nvme       | 7A301220F8 |
| 2646:2262 | 2646:2262 | Kingsto... | Technology Company Non-Vo... | 1     | nvme       | 048229855F |
| 8086:0975 | 8086:8410 | Intel      | Non-Volatile memory contr... | 1     | nvme       | 4EA8D503AE |
| 8086:0975 | 8086:8510 | Intel      | Non-Volatile memory contr... | 1     | nvme       | 4EA8D503AE |
| 8086:2522 | 8086:3806 | Intel      | NVMe SSD Optane Series Co... | 1     | nvme       | EFDC2E3D09 |
| 8086:2522 | 8086:3810 | Intel      | NVMe SSD Optane Series Co... | 1     | nvme       | DEE55623F8 |
| 8086:2522 | 8086:3811 | Intel      | NVMe SSD Optane Series Co... | 1     | nvme       | AEAC4E0E68 |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:282a | 1028:0233 | Intel      | 82801 Mobile SATA Control... | 29    | ahci       | 314E0FF832 |
| 8086:282a | 103c:1818 | Intel      | 82801 Mobile SATA Control... | 25    | ahci       | 6C34B57DD0 |
| 8086:282a | 1028:0493 | Intel      | 82801 Mobile SATA Control... | 21    | ahci       | 3F252A50FB |
| 8086:282a | 1025:1264 | Intel      | 82801 Mobile SATA Control... | 17    | ahci       | FF5A6B10F9 |
| 8086:282a | 103c:84a6 | Intel      | 82801 Mobile SATA Control... | 17    | ahci       | 56A3768905 |
| 8086:282a | 1028:040a | Intel      | 82801 Mobile SATA Control... | 15    | ahci       | D5CEA70705 |
| 8086:282a | 1028:0534 | Intel      | 82801 Mobile SATA Control... | 13    | ahci       | 39D47C0F09 |
| 8086:282a | 1028:024f | Intel      | 82801 Mobile SATA Control... | 12    | ahci       | 00C163136F |
| 8086:282a | 1028:05ca | Intel      | 82801 Mobile SATA Control... | 12    | ahci       | C897C33BBA |
| 8086:282a | 1043:1fc0 | Intel      | 82801 Mobile SATA Control... | 11    | ahci       | 5129A11C87 |
| 8086:282a | 1028:062e | Intel      | 82801 Mobile SATA Control... | 10    | ahci       | 611A318D07 |
| 8086:282a | 17aa:3814 | Intel      | 82801 Mobile SATA Control... | 10    | ahci       | C47A5BBFAE |
| 8086:282a | 1028:04a3 | Intel      | 82801 Mobile SATA Control... | 9     | ahci       | D8BA5B1425 |
| 8086:282a | 1028:0532 | Intel      | 82801 Mobile SATA Control... | 9     | ahci       | 8E240EEE56 |
| 8086:282a | 103c:8532 | Intel      | 82801 Mobile SATA Control... | 9     | ahci       | 30DE8A33D7 |
| 8086:282a | 1028:0494 | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | 4384225066 |
| 8086:282a | 1028:0535 | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | 6251A0DB90 |
| 8086:282a | 1028:053d | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | C87C3F181E |
| 8086:282a | 1028:05be | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | C7F7A6189C |
| 8086:282a | 1028:05cb | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | 04BD492077 |
| 8086:282a | 1043:1311 | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | D720B44576 |
| 8086:282a | 17aa:380f | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | 0806E2A6D8 |
| 8086:282a | 1028:040b | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | 47A22D2542 |
| 8086:282a | 1028:0492 | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | 276041713D |
| 8086:282a | 103c:18a5 | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | A978F2CA38 |
| 8086:282a | 17aa:3810 | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | 7D8BB0BF84 |
| 8086:2822 | 1028:06d9 | Intel      | SATA Controller [RAID mode]  | 6     | ahci       | 5F15FEDC3B |
| 8086:282a | 1028:0572 | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | FA7DA218EC |
| 8086:282a | 1028:06de | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | 78974F9610 |
| 8086:282a | 1028:0810 | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | 5CD9AAC635 |
| 8086:282a | 1028:081c | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | 9F4A416C12 |
| 8086:282a | 103c:18fd | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | 369A2DFC15 |
| 8086:282a | 103c:849a | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | E4CA853A88 |
| 8086:282a | 103c:84a7 | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | C84F48BF16 |
| 8086:282a | 1043:1501 | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | CF0266106B |
| 8086:282a | 1043:1961 | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | BAEE55FB37 |
| 8086:282a | 1028:024d | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 59050A5736 |
| 8086:282a | 1028:053c | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | F94D8B6C0A |
| 8086:282a | 1028:05aa | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 1D4C1380A3 |
| 8086:282a | 1028:05de | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 7A0E5E1EA2 |
| 8086:282a | 1028:062b | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 001F6A7015 |
| 8086:282a | 103c:1894 | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 0A6F4AEE88 |
| 8086:282a | 103c:84da | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 605A299A65 |
| 8086:282a | 1043:1b90 | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 8FF6A7E718 |
| 8086:282a | 1025:128d | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | D2C618DB7F |
| 8086:282a | 1028:040c | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | FB2C2A5FA3 |
| 8086:282a | 1028:04a4 | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 2A2FBFB933 |
| 8086:282a | 1028:0533 | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | BBAA208359 |
| 8086:282a | 1028:05bd | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | C231680C2F |
| 8086:282a | 1028:062d | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 4926835893 |
| 8086:282a | 1028:06dc | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 9872B0F2CF |
| 8086:282a | 1028:079f | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | D18E59C26A |
| 8086:282a | 1028:0825 | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 588F6AB038 |
| 8086:282a | 103c:1793 | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 6A0E9D372C |
| 8086:282a | 1043:1591 | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 24F8864FB8 |
| 1095:3531 | 1734:1107 | Silicon... | SiI 3531 [SATALink/SATARa... | 3     | sata_sil24 | EA3B68E3CD |
| 1106:3249 | 1734:107c | VIA Tec... | VT6421 IDE/SATA Controller   | 3     | sata_via   | 593A8E1A1A |
| 8086:2822 | 1028:06de | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | 4CCFEAF9AE |
| 8086:282a | 1025:129a | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 0701047539 |
| 8086:282a | 1028:0277 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | F474D6B56B |
| 8086:282a | 1028:053e | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 7B41570D1D |
| 8086:282a | 1028:05e0 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | FF0970D119 |
| 8086:282a | 1028:062c | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 9FC9C18210 |
| 8086:282a | 1028:06df | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 80B843095C |
| 8086:282a | 1028:0798 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 882D11658B |
| 8086:282a | 1028:081b | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 714656669C |
| 8086:282a | 1028:08a6 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 1DA82F475D |
| 8086:282a | 103c:1897 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 6BECFAD5CB |
| 8086:282a | 103c:84ca | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 94E22053F6 |
| 8086:282a | 103c:84db | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 6455FEDD97 |
| 8086:282a | 103c:85ef | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | D2C562AB31 |
| 8086:282a | 1043:1f40 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | B6B40DE397 |
| 8086:282a | 104d:905a | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | EB4E58C4D9 |
| 8086:282a | 104d:907b | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 9E7981F839 |
| 8086:282a | 104d:9084 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 6E74A95929 |
| 8086:282a | 17aa:3802 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | C7B13E4BA2 |
| 1095:3531 | 103c:30d4 | Silicon... | SiI 3531 [SATALink/SATARa... | 2     | sata_sil24 | FAC36A561A |
| 1095:3531 | 17c0:4083 | Silicon... | SiI 3531 [SATALink/SATARa... | 2     | sata_sil24 | 433D38B4A1 |
| 8086:2822 | 1028:06df | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 5ABDD53903 |
| 8086:2822 | 1028:06e5 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | C55A94275F |
| 8086:2822 | 1028:07d1 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 7ABF5FBCE7 |
| 8086:282a | 1025:125e | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 291836CDCE |
| 8086:282a | 1025:1269 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 25698E7FF9 |
| 8086:282a | 1025:1273 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 68B2E174B1 |
| 8086:282a | 1028:04a9 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 37CF274F19 |
| 8086:282a | 1028:04b4 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 4CCAA2E0E2 |
| 8086:282a | 1028:0549 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 6136663F73 |
| 8086:282a | 1028:057e | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | F0C39947CF |
| 8086:282a | 1028:05ab | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 023510307E |
| 8086:282a | 1028:05cc | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 12EDFC1426 |
| 8086:282a | 1028:0684 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 32D2083BB0 |
| 8086:282a | 1028:0704 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 6F1DE9BD47 |
| 8086:282a | 1028:0708 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | E47A8C5A1D |
| 8086:282a | 1028:0797 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | F887B76EAB |
| 8086:282a | 1028:07a7 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | F488CFD08F |
| 8086:282a | 1028:07be | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 6D13CCAE42 |
| 8086:282a | 1028:07e6 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | AD9D887C75 |
| 8086:282a | 1028:0811 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | FCE3A6A178 |
| 8086:282a | 1028:086f | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 9402076861 |
| 8086:282a | 1028:0877 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 8B270D4228 |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:16be | 1025:0647 | Broadco... | BCM57765/57785 MS Card Re... | 234   |            | 9084C70732 |
| 14e4:16bf | 1025:0647 | Broadco... | BCM57765/57785 xD-Picture... | 234   |            | 9084C70732 |
| 197b:2382 | 1043:1a07 | JMicron... | SD/MMC Host Controller       | 121   | sdhci_pci  | 088FFC2823 |
| 14e4:16be | 1025:0504 | Broadco... | BCM57765/57785 MS Card Re... | 104   |            | 832F6EF100 |
| 14e4:16bf | 1025:0504 | Broadco... | BCM57765/57785 xD-Picture... | 104   |            | 832F6EF100 |
| 197b:2383 | 1043:1a07 | JMicron... | MS Host Controller           | 103   | jmb38x_ms  | 088FFC2823 |
| 197b:2384 | 1043:1a07 | JMicron... | xD Host Controller           | 102   |            | 088FFC2823 |
| 1180:e822 | 17aa:2133 | Ricoh      | MMC/SD Host Controller       | 79    | sdhci_pci  | F3FBF8BC70 |
| 1180:0592 | 17aa:20ca | Ricoh      | R5C592 Memory Stick Bus H... | 61    | r592       | 1A90AC4588 |
| 1180:0852 | 17aa:20cb | Ricoh      | xD-Picture Card Controller   | 61    | r852       | 1A90AC4588 |
| 1180:e230 | 104d:9071 | Ricoh      | R5U2xx (R5U230 / R5U231 /... | 56    |            | 90D3759348 |
| 1180:e230 | 17aa:2134 | Ricoh      | R5U2xx (R5U230 / R5U231 /... | 54    |            | 9A495F134B |
| 8086:1513 | 2222:1111 | Intel      | CV82524 Thunderbolt Contr... | 50    | pcieport   | 2B202B204B |
| 8086:d150 |           | Intel      | Core Processor QPI Link      | 37    |            | D7BF7F6352 |
| 8086:d151 |           | Intel      | Core Processor QPI Routin... | 37    |            | D7BF7F6352 |
| 8086:3190 | 1043:1de0 | Intel      | Celeron/Pentium Silver Pr... | 34    |            | 59974C206C |
| 197b:2392 | 103c:17f6 | JMicron... | SD/MMC Host Controller       | 33    | sdhci_pci  | 1F9408B984 |
| 197b:2393 | 103c:17f6 | JMicron... | MS Host Controller           | 33    | jmb38x_ms  | 1F9408B984 |
| 1180:e823 | 17aa:21f6 | Ricoh      | PCIe SDXC/MMC Host Contro... | 32    | sdhci_pci  | 1949413DC7 |
| 1180:0592 | 1028:022f | Ricoh      | R5C592 Memory Stick Bus H... | 29    | r592       | 56866B9E4C |
| 1180:0592 | 103c:30cc | Ricoh      | R5C592 Memory Stick Bus H... | 29    | r592       | 218FD78ECA |
| 1180:0852 | 1028:022f | Ricoh      | xD-Picture Card Controller   | 29    | r852       | 56866B9E4C |
| 1180:0852 | 103c:30cc | Ricoh      | xD-Picture Card Controller   | 29    | r852       | 218FD78ECA |
| 8086:1911 | 8086:2015 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 29    |            | A43311F999 |
| 1180:e823 | 17aa:21ce | Ricoh      | PCIe SDXC/MMC Host Contro... | 28    | sdhci_pci  | AB2CEA0D81 |
| 197b:2392 | 103c:161c | JMicron... | SD/MMC Host Controller       | 28    | sdhci_pci  | 3EAB448396 |
| 1180:e822 | 17aa:21f3 | Ricoh      | MMC/SD Host Controller       | 27    | sdhci_pci  | B162D0FD81 |
| 1180:e823 | 17aa:21f3 | Ricoh      | PCIe SDXC/MMC Host Contro... | 27    | sdhci_pci  | DDE1CE17CC |
| 197b:2392 | 103c:167c | JMicron... | SD/MMC Host Controller       | 27    | sdhci_pci  | A56D8D1C28 |
| 197b:2393 | 103c:167c | JMicron... | MS Host Controller           | 27    | jmb38x_ms  | A56D8D1C28 |
| 8086:1911 | 103c:832a | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 26    |            | 931D7104FA |
| 197b:2392 | 103c:179b | JMicron... | SD/MMC Host Controller       | 25    | sdhci_pci  | 7195452FF3 |
| 1180:0843 | 1028:01f5 | Ricoh      | R5C843 MMC Host Controller   | 24    | sdhci_pci  | 3D6C8F2267 |
| 8086:15bf | 2222:1111 | Intel      | JHL6240 Thunderbolt 3 NHI... | 24    | thunder... | CABDFDF87F |
| 8086:1911 | 1025:1264 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 24    |            | AF51F8907E |
| 8086:1911 | 1028:087c | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 24    |            | 18DC19F3EC |
| 8086:d155 |           | Intel      | Core Processor System Man... | 24    |            | D7BF7F6352 |
| 8086:d156 |           | Intel      | Core Processor Semaphore ... | 24    |            | D7BF7F6352 |
| 8086:d157 |           | Intel      | Core Processor System Con... | 24    |            | D7BF7F6352 |
| 8086:d158 |           | Intel      | Core Processor Miscellane... | 24    |            | D7BF7F6352 |
| 1180:0592 | 1025:011e | Ricoh      | R5C592 Memory Stick Bus H... | 23    | r592       | 3530E5C8F1 |
| 1180:0852 | 1025:011e | Ricoh      | xD-Picture Card Controller   | 22    | r852       | 3530E5C8F1 |
| 1180:0592 | 1025:0121 | Ricoh      | R5C592 Memory Stick Bus H... | 20    | r592       | C1C791C270 |
| 1180:0592 | 1025:0126 | Ricoh      | R5C592 Memory Stick Bus H... | 20    | r592       | 590A68AE68 |
| 1180:0592 | 103c:30cf | Ricoh      | R5C592 Memory Stick Bus H... | 20    | r592       | AB1EF36E83 |
| 1180:0592 | 1043:1627 | Ricoh      | R5C592 Memory Stick Bus H... | 20    | r592       | 6C6A2138D2 |
| 1180:0592 | 1043:1877 | Ricoh      | R5C592 Memory Stick Bus H... | 20    | r592       | A970D9DFC5 |
| 1180:0852 | 1025:0121 | Ricoh      | xD-Picture Card Controller   | 20    | r852       | C1C791C270 |
| 1180:0852 | 1025:0126 | Ricoh      | xD-Picture Card Controller   | 20    | r852       | 590A68AE68 |
| 1180:0852 | 103c:30cf | Ricoh      | xD-Picture Card Controller   | 20    | r852       | AB1EF36E83 |
| 1180:0852 | 1043:1877 | Ricoh      | xD-Picture Card Controller   | 20    | r852       | A970D9DFC5 |
| 1180:e823 | 17aa:21da | Ricoh      | PCIe SDXC/MMC Host Contro... | 20    | sdhci_pci  | DA7FEA9DD2 |
| 1180:e823 | 17aa:21fa | Ricoh      | PCIe SDXC/MMC Host Contro... | 20    | sdhci_pci  | FADDCC4F2B |
| 197b:2392 | 17aa:3976 | JMicron... | SD/MMC Host Controller       | 20    | sdhci_pci  | 6177430B68 |
| 197b:2393 | 17aa:3976 | JMicron... | MS Host Controller           | 20    | jmb38x_ms  | 6177430B68 |
| 197b:2394 | 17aa:3976 | JMicron... | xD Host Controller           | 20    |            | 6177430B68 |
| 8086:1911 | 17aa:5068 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 20    |            | F4826C3A2A |
| 1180:e823 | 1179:0001 | Ricoh      | PCIe SDXC/MMC Host Contro... | 19    | sdhci_pci  | 6D794063DD |
| 197b:2382 | 17aa:212e | JMicron... | SD/MMC Host Controller       | 19    | sdhci_pci  | 4B5548D0BB |
| 197b:2383 | 17aa:212f | JMicron... | MS Host Controller           | 19    | jmb38x_ms  | 4B5548D0BB |
| 197b:2384 | 17aa:2130 | JMicron... | xD Host Controller           | 19    |            | 4B5548D0BB |
| 8086:1911 | 1028:08af | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 19    |            | ED8598DB62 |
| 1180:0592 | 1043:1317 | Ricoh      | R5C592 Memory Stick Bus H... | 17    | r592       | 4841CD6D3C |
| 1180:0843 | 1043:1317 | Ricoh      | R5C843 MMC Host Controller   | 17    | sdhci_pci  | 4841CD6D3C |
| 1180:e822 | 17aa:21f6 | Ricoh      | MMC/SD Host Controller       | 17    | sdhci_pci  | 052686C1D4 |
| 14e4:16be | 1025:0605 | Broadco... | BCM57765/57785 MS Card Re... | 17    |            | 72878CC6E9 |
| 14e4:16bf | 1025:0605 | Broadco... | BCM57765/57785 xD-Picture... | 17    |            | 72878CC6E9 |
| 197b:2382 | 103c:3628 | JMicron... | SD/MMC Host Controller       | 17    | sdhci_pci  | BF5A8C1756 |
| 197b:2383 | 103c:3628 | JMicron... | MS Host Controller           | 17    | jmb38x_ms  | BF5A8C1756 |
| 197b:2384 | 103c:3628 | JMicron... | xD Host Controller           | 17    |            | BF5A8C1756 |
| 8086:15d2 | 1028:08af | Intel      | JHL6540 Thunderbolt 3 NHI... | 17    | thunder... | ED8598DB62 |
| 8086:1911 | 1028:087d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 17    |            | 5741F67096 |
| 8086:1911 | 103c:84a6 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 17    |            | 56A3768905 |
| 8086:1911 | 17aa:225d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 16    |            | BE40A37EA8 |
| 1180:0592 | 1028:01bd | Ricoh      | R5C592 Memory Stick Bus H... | 15    | r592       | AB555162C8 |
| 1180:0592 | 1043:1897 | Ricoh      | R5C592 Memory Stick Bus H... | 15    | r592       | B720D65E19 |
| 1180:0852 | 1028:01bd | Ricoh      | xD-Picture Card Controller   | 15    | r852       | AB555162C8 |
| 1180:0852 | 1043:1897 | Ricoh      | xD-Picture Card Controller   | 15    | r852       | B720D65E19 |
| 1180:e822 | 17aa:21fa | Ricoh      | MMC/SD Host Controller       | 15    | sdhci_pci  | AFB801A018 |
| 1180:e823 | 17aa:21cf | Ricoh      | PCIe SDXC/MMC Host Contro... | 15    | sdhci_pci  | DF04D39AC3 |
| 197b:2392 | 103c:17ab | JMicron... | SD/MMC Host Controller       | 15    | sdhci_pci  | 57308077EE |
| 1180:0592 | 1043:14e7 | Ricoh      | R5C592 Memory Stick Bus H... | 14    | r592       | 7AC6E3C864 |
| 1180:0592 | 104d:9035 | Ricoh      | R5C592 Memory Stick Bus H... | 14    | r592       | 0C80B6E23F |
| 1180:0852 | 1043:14e7 | Ricoh      | xD-Picture Card Controller   | 14    | r852       | 7AC6E3C864 |
| 197b:2392 | 103c:1618 | JMicron... | SD/MMC Host Controller       | 14    | sdhci_pci  | 0D2FE88BE0 |
| 8086:1911 | 103c:8328 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 14    |            | D59CC110FE |
| 8086:1911 | 17aa:2279 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 14    |            | F737A5A121 |
| 8086:1911 | 17aa:2292 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 14    |            | 1820A998EC |
| 8086:1911 | 1d72:1701 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 14    |            | 4DCFEFF869 |
| 1180:0592 | 1043:1517 | Ricoh      | R5C592 Memory Stick Bus H... | 13    | r592       | 427546EA21 |
| 1180:0592 | 1179:ff1c | Ricoh      | R5C592 Memory Stick Bus H... | 13    | r592       | 420C738977 |
| 1180:0852 | 1043:1517 | Ricoh      | xD-Picture Card Controller   | 13    | r852       | 427546EA21 |
| 1180:0852 | 1179:ff1c | Ricoh      | xD-Picture Card Controller   | 13    | r852       | 420C738977 |
| 197b:2382 | 103c:3603 | JMicron... | SD/MMC Host Controller       | 13    | sdhci_pci  | F2190D7446 |
| 197b:2383 | 103c:3603 | JMicron... | MS Host Controller           | 13    | jmb38x_ms  | F2190D7446 |
| 197b:2384 | 103c:3603 | JMicron... | xD Host Controller           | 13    |            | F2190D7446 |
| 8086:156c | 2222:1111 | Intel      | DSL5520 Thunderbolt 2 NHI... | 13    | thunder... | 3A512A24A7 |
| 8086:15bf | 17aa:2279 | Intel      | JHL6240 Thunderbolt 3 NHI... | 13    | thunder... | F737A5A121 |
| 8086:15d2 | 17aa:2292 | Intel      | JHL6540 Thunderbolt 3 NHI... | 13    | thunder... | 1820A998EC |
| 8086:1911 | 103c:832b | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 13    |            | 95572C5A05 |

### Tv card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1131:7133 | 1461:a836 | Philips... | SAA7131/SAA7133/SAA7135 V... | 3     | saa7134    | 1CE26C391A |
| 1131:7133 | 1461:e836 | Philips... | SAA7131/SAA7133/SAA7135 V... | 3     | saa7134    | 29555CDBC9 |
| 1131:7133 | 1461:f636 | Philips... | SAA7131/SAA7133/SAA7135 V... | 2     | saa7134    | BAE8402D0D |
| 14f1:5b7a | 1179:0110 | Conexan... | CX23418 Single-Chip MPEG-... | 2     | cx18       | 3E0ED41BC7 |
| 14f1:8852 | 1461:d939 | Conexan... | CX23885 PCI Video and Aud... | 2     | cx23885    | 8E5499B7A2 |
| 1131:7133 | 0000:5201 | Philips... | SAA7131/SAA7133/SAA7135 V... | 1     | saa7134    | C5FECF0E37 |
| 1131:7133 | 16be:0009 | Philips... | SAA7131/SAA7133/SAA7135 V... | 1     | saa7134    | EFDFFC9FB6 |
| 1131:7133 | 5168:0307 | Philips... | SAA7131/SAA7133/SAA7135 V... | 1     | saa7134    | E244649FAC |
| 14f1:5b7a | 1179:0030 | Conexan... | CX23418 Single-Chip MPEG-... | 1     | cx18       | B5DB9CE313 |
| 14f1:5b7a | 1179:0031 | Conexan... | CX23418 Single-Chip MPEG-... | 1     | cx18       | AE0DBDDFF1 |
| 4444:0016 | 1179:0001 | Interne... | iTVC16 (CX23416) Video De... | 1     | ivtv       | D5D7DAB02F |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e26 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 301   | ehci_hc... | 8CE0C08E9A |
| 8086:1e2d | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 301   | ehci_hc... | 8CE0C08E9A |
| 8086:1e31 | 17aa:3977 | Intel      | 7 Series/C210 Series Chip... | 294   | xhci_pci   | 8CE0C08E9A |
| 8086:9d2f | 1043:201f | Intel      | Sunrise Point-LP USB 3.0 ... | 225   | xhci_hcd   | D720B44576 |
| 8086:1c26 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 187   | ehci_hc... | 89EF922929 |
| 8086:1c2d | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 187   | ehci_hc... | 89EF922929 |
| 8086:27c8 | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 187   | uhci_hcd   | A6B1293F94 |
| 8086:27c9 | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 187   | uhci_hcd   | A6B1293F94 |
| 8086:27ca | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 187   | uhci_hcd   | A6B1293F94 |
| 8086:27cc | 1043:83ad | Intel      | NM10/ICH7 Family USB2 EHC... | 187   | ehci_hc... | A6B1293F94 |
| 1b21:1042 | 1043:1059 | ASMedia... | ASM1042 SuperSpeed USB Ho... | 179   | xhci_pci   | 55153BEE1A |
| 8086:27cb | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 171   | uhci_hcd   | A6B1293F94 |
| 8086:22b5 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 131   | xhci_hcd   | AE477CA654 |
| 8086:9c31 | 17aa:3978 | Intel      | 8 Series USB xHCI HC         | 113   | xhci_hcd   | 972580DCF6 |
| 8086:9c26 | 17aa:3978 | Intel      | 8 Series USB EHCI #1         | 110   | ehci_hc... | 972580DCF6 |
| 8086:9c31 | 1043:201f | Intel      | 8 Series USB xHCI HC         | 107   | xhci_hcd   | E6D66177E4 |
| 8086:3b34 | 17aa:2163 | Intel      | 5 Series/3400 Series Chip... | 105   | ehci_pci   | 9A495F134B |
| 8086:3b3c | 17aa:2163 | Intel      | 5 Series/3400 Series Chip... | 105   | ehci_pci   | 9A495F134B |
| 8086:2934 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 100   | uhci_hcd   | 1A90AC4588 |
| 8086:2935 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 100   | uhci_hcd   | 1A90AC4588 |
| 8086:2936 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 100   | uhci_hcd   | 1A90AC4588 |
| 8086:2937 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 100   | uhci_hcd   | 1A90AC4588 |
| 8086:2938 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 100   | uhci_hcd   | 1A90AC4588 |
| 8086:2939 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 100   | uhci_hcd   | 1A90AC4588 |
| 8086:293a | 17aa:20f1 | Intel      | 82801I (ICH9 Family) USB2... | 100   | ehci_pci   | 1A90AC4588 |
| 8086:293c | 17aa:20f1 | Intel      | 82801I (ICH9 Family) USB2... | 100   | ehci_pci   | 1A90AC4588 |
| 8086:1c26 | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 89    | ehci_hc... | B7B1C7DF29 |
| 8086:1c2d | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 89    | ehci_hc... | B7B1C7DF29 |
| 8086:3b34 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 89    | ehci_hc... | 088FFC2823 |
| 8086:3b3c | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 89    | ehci_hc... | 088FFC2823 |
| 8086:9cb1 | 1043:201f | Intel      | Wildcat Point-LP USB xHCI... | 89    | xhci_hcd   | CF2D08BE47 |
| 8086:1e26 | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 88    | ehci_hc... | 7857E6A77B |
| 8086:1e2d | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 88    | ehci_hc... | 7857E6A77B |
| 8086:9c26 | 1043:201f | Intel      | 8 Series USB EHCI #1         | 86    | ehci_hc... | 9F136B8761 |
| 8086:2934 | 17aa:3a14 | Intel      | 82801I (ICH9 Family) USB ... | 85    | uhci_hcd   | 5986AA0AAC |
| 8086:2935 | 17aa:3a15 | Intel      | 82801I (ICH9 Family) USB ... | 85    | uhci_hcd   | 5986AA0AAC |
| 8086:2936 | 17aa:3a16 | Intel      | 82801I (ICH9 Family) USB ... | 85    | uhci_hcd   | 5986AA0AAC |
| 8086:293a | 17aa:3a17 | Intel      | 82801I (ICH9 Family) USB2... | 85    | ehci_hc... | 5986AA0AAC |
| 8086:293c | 17aa:3a0c | Intel      | 82801I (ICH9 Family) USB2... | 85    | ehci_hc... | 5986AA0AAC |
| 8086:2937 | 17aa:3a09 | Intel      | 82801I (ICH9 Family) USB ... | 84    | uhci_hcd   | 5986AA0AAC |
| 8086:3b34 | 17aa:38b8 | Intel      | 5 Series/3400 Series Chip... | 84    | ehci_hc... | 15789D122D |
| 8086:3b3c | 17aa:38aa | Intel      | 5 Series/3400 Series Chip... | 84    | ehci_hc... | 15789D122D |
| 8086:2938 | 17aa:3a0a | Intel      | 82801I (ICH9 Family) USB ... | 81    | uhci_hcd   | 5986AA0AAC |
| 8086:8c26 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 81    | ehci_hc... | F21C5B69B8 |
| 8086:8c2d | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 81    | ehci_hc... | F21C5B69B8 |
| 8086:8c31 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 81    | xhci_pci   | F21C5B69B8 |
| 8086:1c26 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 80    | ehci_hc... | 25D909CC38 |
| 8086:1c2d | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 80    | ehci_hc... | 25D909CC38 |
| 8086:2939 | 17aa:3a0b | Intel      | 82801I (ICH9 Family) USB ... | 80    | uhci_hcd   | 5986AA0AAC |
| 8086:1e26 | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 75    | ehci_hc... | 1C3C62EC29 |
| 8086:1e2d | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 75    | ehci_hc... | 1C3C62EC29 |
| 8086:1e31 | 17aa:5002 | Intel      | 7 Series/C210 Series Chip... | 75    | xhci_pci   | 1C3C62EC29 |
| 8086:1e26 | 1043:124d | Intel      | 7 Series/C216 Chipset Fam... | 71    | ehci_hc... | 179397B4EA |
| 8086:1e2d | 1043:124d | Intel      | 7 Series/C216 Chipset Fam... | 71    | ehci_hc... | 179397B4EA |
| 8086:2830 | 1025:011f | Intel      | 82801H (ICH8 Family) USB ... | 71    | uhci_hcd   | BA9EFF4F3B |
| 8086:2831 | 1025:011f | Intel      | 82801H (ICH8 Family) USB ... | 71    | uhci_hcd   | BA9EFF4F3B |
| 8086:2832 | 1025:011f | Intel      | 82801H (ICH8 Family) USB ... | 71    | uhci_hcd   | BA9EFF4F3B |
| 8086:2834 | 1025:011f | Intel      | 82801H (ICH8 Family) USB ... | 71    | uhci_hcd   | BA9EFF4F3B |
| 8086:2835 | 1025:011f | Intel      | 82801H (ICH8 Family) USB ... | 71    | uhci_hcd   | BA9EFF4F3B |
| 8086:2836 | 1025:011f | Intel      | 82801H (ICH8 Family) USB2... | 71    | ehci_hc... | BA9EFF4F3B |
| 8086:283a | 1025:011f | Intel      | 82801H (ICH8 Family) USB2... | 71    | ehci_hc... | BA9EFF4F3B |
| 8086:1e31 | 1043:124d | Intel      | 7 Series/C210 Series Chip... | 70    | xhci_pci   | B2FB796FAB |
| 8086:1e26 | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 69    | ehci_hc... | 9084C70732 |
| 8086:1e2d | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 69    | ehci_hc... | 9084C70732 |
| 8086:1e31 | 1025:0647 | Intel      | 7 Series/C210 Series Chip... | 69    | xhci_pci   | 9084C70732 |
| 8086:a12f | 1043:201f | Intel      | 100 Series/C230 Series Ch... | 69    | xhci_hcd   | 11A297038F |
| 8086:1e26 | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 68    | ehci_hc... | EFE09AFB77 |
| 8086:1e2d | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 68    | ehci_hc... | EFE09AFB77 |
| 8086:1c26 | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 67    | ehci_hc... | 47A635ACC1 |
| 8086:1c2d | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 67    | ehci_hc... | 47A635ACC1 |
| 8086:3b34 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 64    | ehci_hc... | 53ECD14649 |
| 8086:3b3c | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 64    | ehci_hc... | 53ECD14649 |
| 1022:7808 | 17aa:3801 | AMD        | FCH USB EHCI Controller      | 63    | ehci_hc... | 363B08984A |
| 1022:7814 | 17aa:3801 | AMD        | FCH USB XHCI Controller      | 63    | xhci_pci   | 363B08984A |
| 8086:31a8 | 1043:201f | Intel      | USB Controller               | 58    | xhci_hcd   | 59974C206C |
| 8086:3b34 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 56    | ehci_hc... | 90D3759348 |
| 8086:3b3c | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 56    | ehci_hc... | 90D3759348 |
| 8086:2830 | 17aa:20aa | Intel      | 82801H (ICH8 Family) USB ... | 55    | uhci_hcd   | FB1CD7BF88 |
| 8086:2831 | 17aa:20aa | Intel      | 82801H (ICH8 Family) USB ... | 55    | uhci_hcd   | FB1CD7BF88 |
| 8086:2834 | 17aa:20aa | Intel      | 82801H (ICH8 Family) USB ... | 55    | uhci_hcd   | FB1CD7BF88 |
| 8086:2835 | 17aa:20aa | Intel      | 82801H (ICH8 Family) USB ... | 55    | uhci_hcd   | FB1CD7BF88 |
| 8086:2836 | 17aa:20ab | Intel      | 82801H (ICH8 Family) USB2... | 55    | ehci_pci   | FB1CD7BF88 |
| 8086:283a | 17aa:20ab | Intel      | 82801H (ICH8 Family) USB2... | 55    | ehci_pci   | FB1CD7BF88 |
| 1b73:1000 | 1043:1039 | Fresco ... | FL1000G USB 3.0 Host Cont... | 54    | xhci_pci   | B7B1C7DF29 |
| 8086:27c8 | 1025:0349 | Intel      | NM10/ICH7 Family USB UHCI... | 54    | uhci_hcd   | A911172500 |
| 8086:27c9 | 1025:0349 | Intel      | NM10/ICH7 Family USB UHCI... | 54    | uhci_hcd   | A911172500 |
| 8086:27ca | 1025:0349 | Intel      | NM10/ICH7 Family USB UHCI... | 54    | uhci_hcd   | A911172500 |
| 8086:27cb | 1025:0349 | Intel      | NM10/ICH7 Family USB UHCI... | 54    | uhci_hcd   | A911172500 |
| 8086:27cc | 1025:0349 | Intel      | NM10/ICH7 Family USB2 EHC... | 54    | ehci_hc... | A911172500 |
| 8086:5aa8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 53    | xhci_hcd   | 97BCBB884E |
| 8086:1c26 | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 52    | ehci_hc... | 4DB132BB33 |
| 8086:1c2d | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 52    | ehci_hc... | 4DB132BB33 |
| 8086:1e26 | 17aa:5011 | Intel      | 7 Series/C216 Chipset Fam... | 50    | ehci_hc... | 82A9861AFD |
| 8086:1e2d | 17aa:5011 | Intel      | 7 Series/C216 Chipset Fam... | 50    | ehci_hc... | 82A9861AFD |
| 8086:a36d | 1043:201f | Intel      | Cannon Lake PCH USB 3.1 x... | 50    | xhci_hcd   | A47D005445 |
| 8086:1c26 | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 49    | ehci_hc... | 0BF9EE57AF |
| 8086:1c2d | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 49    | ehci_hc... | 0BF9EE57AF |
| 8086:0f35 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 48    | xhci_hcd   | 27F3692E24 |
| 8086:1c26 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 48    | ehci_pci   | F3FBF8BC70 |
| 8086:1c2d | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 48    | ehci_pci   | F3FBF8BC70 |

### Wireless controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:7360 | 8086:0020 | Intel      | XMM7360 LTE Advanced Modem   | 12    |            | B921C3D4A7 |
| 8086:7360 | 1cf8:8521 | Intel      | XMM7360 LTE Advanced Modem   | 6     |            | 2CF77D999D |
| 8086:7360 | 103c:8337 | Intel      | XMM7360 LTE Advanced Modem   | 5     |            | 65B1EB0CA1 |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 17a0:9750 | 17aa:2279 | Genesys... | GL9750 SD Host Controller    | 10    | sdhci_pci  | F737A5A121 |
| 1aea:6625 | 103c:8478 | Alcor M... | Alcor Micro PCIe Card Reader | 8     |            | F473523657 |
| 1002:6900 | 03ea:1af4 | AMD        | Topaz XT [Radeon R7 M260/... | 5     | amdgpu     | D0612D575F |
| 10ec:5260 | 1028:0831 | Realtek... | RTS5260 PCI Express Card ... | 4     | rtsx_pci   | A5F184FD44 |
| 8086:31d6 | 0000:0000 | Intel      | Gemini Lake PCI Express R... | 4     | shpchp     | 5A0A25C9FF |
| 8086:31d7 | 0000:0000 | Intel      | Gemini Lake PCI Express R... | 4     | shpchp     | 5A0A25C9FF |
| 17a0:9750 | 17aa:2286 | Genesys... | GL9750 SD Host Controller    | 2     | sdhci_pci  | 5EF9741E90 |
| 1002:694e | 1002:694e | AMD        | Polaris 22 XL [Radeon RX ... | 1     | amdgpu     | F5FDC69851 |
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
| 17fe:a220 | 1468:0305 | InProComm  |                              | 1     |            | 80E120B3A5 |
| 17fe:a220 | 1468:8305 | InProComm  |                              | 1     |            | 80E120B3A5 |
| 1aea:6625 | 103c:8349 | Alcor M... |                              | 1     |            | 1DEE29768A |
| 1aea:6625 | 103c:83a8 | Alcor M... |                              | 1     |            | 9ECD580CF7 |
| 1aea:6625 | 103c:83aa | Alcor M... | Alcor Micro PCIe Card Reader | 1     |            | 62C7769C30 |
| 1aea:6625 | 103c:85fa | Alcor M... |                              | 1     |            | 992E2074FF |
| 8086:31d8 | 0000:0000 | Intel      | Gemini Lake PCI Express R... | 1     | shpchp     | 58FC691B81 |
| 8086:31da | 0000:0000 | Intel      | Gemini Lake PCI Express R... | 1     | shpchp     | 58FC691B81 |
| 8086:31db | 0000:0000 | Intel      | Gemini Lake PCI Express R... | 1     | shpchp     | 58FC691B81 |
| 8086:3b4e | 0000:0000 | Intel      | 5 Series/3400 Series Chip... | 1     | shpchp     | B642835279 |
| 8086:5ad6 | 0000:0000 | Intel      | Celeron N3350/Pentium N42... | 1     | pcieport   | FAE89FAE49 |
| 8086:9d2f | 14c0:0062 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 87AC0729E6 |
| 8086:a110 | 0000:0000 | Intel      | 100 Series/C230 Series Ch... | 1     | pcieport   | C8A8910A82 |

