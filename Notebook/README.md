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
| 1814:3298 | 103c:18ec | Ralink     | RT3290 Bluetooth             | 189   | rtbth      | A978F2CA38 |
| 1814:3298 | 105b:e056 | Ralink     | RT3290 Bluetooth             | 55    |            | F71E42FC3C |
| 1814:3298 | 1a3b:2f87 | Ralink     | RT3290 Bluetooth             | 7     |            | 45F3B356CF |
| 1814:3298 | 1a3b:2787 | Ralink     | RT3290 Bluetooth             | 6     |            | 0E1770A053 |
| 1814:3298 | 103c:191c | Ralink     | RT3290 Bluetooth             | 2     |            | 9B25B9E02E |
| 1814:3298 | 10cf:1772 | Ralink     | RT3290 Bluetooth             | 1     |            | 1135E21142 |
| 1814:3298 | 1814:3298 | Ralink     | RT3290 Bluetooth             | 1     |            | FE9255E7F3 |
| 1814:3298 | 1a3b:210b | Ralink     | RT3290 Bluetooth             | 1     |            | 2333E930AF |
| 1814:3298 | 1a3b:2987 | Ralink     | RT3290 Bluetooth             | 1     |            | EC90AB9922 |

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:4384 |           | AMD        | SBx00 PCI to PCI Bridge      | 898   | shpchp     | F9F3745636 |
| 1022:1700 |           | AMD        | Family 12h/14h Processor ... | 620   |            | F9F3745636 |
| 1022:1701 |           | AMD        | Family 12h/14h Processor ... | 620   |            | F9F3745636 |
| 1022:1702 |           | AMD        | Family 12h/14h Processor ... | 620   |            | F9F3745636 |
| 1022:1703 |           | AMD        | Family 12h/14h Processor ... | 620   | k10temp    | F9F3745636 |
| 1022:1704 |           | AMD        | Family 12h/14h Processor ... | 620   |            | F9F3745636 |
| 1022:1716 |           | AMD        | Family 12h/14h Processor ... | 620   |            | F9F3745636 |
| 1022:1718 |           | AMD        | Family 12h/14h Processor ... | 620   |            | F9F3745636 |
| 1022:1719 |           | AMD        | Family 12h/14h Processor ... | 620   |            | F9F3745636 |
| 1022:780f |           | AMD        | FCH PCI Bridge               | 599   | shpchp     | 92AE8C0F3B |
| 8086:2c62 | 8086:8086 | Intel      | Core Processor QuickPath ... | 506   |            | 86987CF1ED |
| 8086:2d01 | 8086:8086 | Intel      | Core Processor QuickPath ... | 506   |            | 86987CF1ED |
| 8086:2d10 | 8086:8086 | Intel      | Core Processor QPI Link 0    | 506   |            | 86987CF1ED |
| 8086:2d11 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 506   |            | 86987CF1ED |
| 8086:2d12 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 506   |            | 86987CF1ED |
| 8086:2d13 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 506   |            | 86987CF1ED |
| 8086:2448 |           | Intel      | 82801 Mobile PCI Bridge      | 333   | shpchp     | E9BD04F647 |
| 1022:1200 |           | AMD        | Family 10h Processor Hype... | 302   |            | 690FFF1815 |
| 1022:1201 |           | AMD        | Family 10h Processor Addr... | 302   |            | 690FFF1815 |
| 1022:1202 |           | AMD        | Family 10h Processor DRAM... | 302   |            | 690FFF1815 |
| 1022:1203 |           | AMD        | Family 10h Processor Misc... | 302   | k10temp    | 690FFF1815 |
| 1022:1204 |           | AMD        | Family 10h Processor Link... | 302   |            | 690FFF1815 |
| 1002:43a0 | 1002:0000 | AMD        | SB700/SB800/SB900 PCI to ... | 284   | shpchp     | F9F3745636 |
| 1022:1400 |           | AMD        | Family 15h (Models 10h-1f... | 265   |            | 92AE8C0F3B |
| 1022:1401 |           | AMD        | Family 15h (Models 10h-1f... | 265   |            | 92AE8C0F3B |
| 1022:1402 |           | AMD        | Family 15h (Models 10h-1f... | 265   |            | 92AE8C0F3B |
| 1022:1403 |           | AMD        | Family 15h (Models 10h-1f... | 265   | k10temp    | 92AE8C0F3B |
| 1022:1404 |           | AMD        | Family 15h (Models 10h-1f... | 265   |            | 92AE8C0F3B |
| 1022:1405 |           | AMD        | Family 15h (Models 10h-1f... | 265   |            | 92AE8C0F3B |
| 1022:43a0 | 1022:0000 | AMD        | Hudson PCI to PCI bridge ... | 263   | shpchp     | 92AE8C0F3B |
| 8086:1e10 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 253   | shpchp     | 891002E8F2 |
| 8086:1e12 | 17aa:3977 | Intel      | 7 Series/C210 Series Chip... | 247   | shpchp     | 891002E8F2 |
| 1022:1439 | 1022:1234 | AMD        | Family 16h Processor Func... | 246   | shpchp     | 1CC2218397 |
| 1022:1510 | 1022:1510 | AMD        | Family 14h Processor Root... | 242   |            | F9F3745636 |
| 1022:1100 |           | AMD        | K8 [Athlon64/Opteron] Hyp... | 239   |            | 084F7E13DA |
| 1022:1101 |           | AMD        | K8 [Athlon64/Opteron] Add... | 239   |            | 084F7E13DA |
| 1022:1102 |           | AMD        | K8 [Athlon64/Opteron] DRA... | 239   |            | 084F7E13DA |
| 1022:1103 |           | AMD        | K8 [Athlon64/Opteron] Mis... | 239   | k8temp     | 084F7E13DA |
| 1022:156b |           | AMD        | Family 16h (Models 30h-3f... | 226   |            | 1CC2218397 |
| 1022:1580 |           | AMD        | Family 16h (Models 30h-3f... | 226   |            | 1CC2218397 |
| 1022:1581 |           | AMD        | Family 16h (Models 30h-3f... | 226   |            | 1CC2218397 |
| 1022:1582 |           | AMD        | Family 16h (Models 30h-3f... | 226   |            | 1CC2218397 |
| 1022:1583 |           | AMD        | Family 16h (Models 30h-3f... | 226   | k10temp    | 1CC2218397 |
| 1022:1584 |           | AMD        | Family 16h (Models 30h-3f... | 226   | fam15h_... | 1CC2218397 |
| 1022:1585 |           | AMD        | Family 16h (Models 30h-3f... | 226   |            | 1CC2218397 |
| 8086:2448 | 0000:0000 | Intel      | 82801 Mobile PCI Bridge      | 213   |            | 46F4E56E3F |
| 8086:0154 | 17aa:3977 | Intel      | 3rd Gen Core processor DR... | 207   | ivb_uncore | 5C4E5B6717 |
| 1022:1414 | 1022:1234 | AMD        | Family 15h (Models 10h-1f... | 205   | shpchp     | 67B0C18725 |
| 1022:43a1 | 1022:0000 | AMD        | Hudson PCI to PCI bridge ... | 196   | shpchp     | 92AE8C0F3B |
| 1022:157b |           | AMD        | Family 15h (Models 60h-6f... | 192   |            | C61C9E33F6 |
| 1022:157d |           | AMD        | Carrizo Audio Dummy Host ... | 192   |            | C61C9E33F6 |
| 8086:1e59 | 17aa:3977 | Intel      | HM76 Express Chipset LPC ... | 189   | lpc_ich    | 891002E8F2 |
| 1022:1709 | 1022:1234 | AMD        | Family 12h Processor Root... | 188   | shpchp     | 2C903F36D0 |
| 1022:1512 | 1022:1234 | AMD        | Family 14h Processor Root... | 169   | shpchp     | A84D413088 |
| 8086:2448 | 1043:83ad | Intel      | 82801 Mobile PCI Bridge      | 169   |            | 6A0513EC8D |
| 8086:27bc | 1043:83ad | Intel      | NM10 Family LPC Controller   | 169   | lpc_ich    | 6A0513EC8D |
| 8086:27d0 | 1043:83ad | Intel      | NM10/ICH7 Family PCI Expr... | 169   | shpchp     | 6A0513EC8D |
| 8086:27d2 | 1043:83ad | Intel      | NM10/ICH7 Family PCI Expr... | 169   | shpchp     | 6A0513EC8D |
| 1002:43a1 | 1002:0000 | AMD        | SB700/SB800/SB900 PCI to ... | 166   | shpchp     | F9F3745636 |
| 8086:0104 | 17aa:3975 | Intel      | 2nd Generation Core Proce... | 164   |            | A7618091FB |
| 8086:1c10 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 164   | shpchp     | A7618091FB |
| 8086:1c49 | 17aa:3975 | Intel      | HM65 Express Chipset LPC ... | 164   | lpc_ich    | A7618091FB |
| 8086:1c12 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 161   | shpchp     | A7618091FB |
| 1022:1412 | 1022:1234 | AMD        | Family 15h (Models 10h-1f... | 159   | shpchp     | 67B0C18725 |
| 8086:27d6 | 1043:83ad | Intel      | NM10/ICH7 Family PCI Expr... | 153   | shpchp     | 6A0513EC8D |
| 8086:2448 | 17aa:383f | Intel      | 82801 Mobile PCI Bridge      | 149   |            | 74624FF493 |
| 1022:1530 |           | AMD        | Family 16h Processor Func... | 140   |            | C081ADAAE3 |
| 1022:1531 |           | AMD        | Family 16h Processor Func... | 140   |            | C081ADAAE3 |
| 1022:1532 |           | AMD        | Family 16h Processor Func... | 140   |            | C081ADAAE3 |
| 1022:1533 |           | AMD        | Family 16h Processor Func... | 140   | k10temp    | C081ADAAE3 |
| 1022:1534 |           | AMD        | Family 16h Processor Func... | 140   | fam15h_... | C081ADAAE3 |
| 1022:1535 |           | AMD        | Family 16h Processor Func... | 140   |            | C081ADAAE3 |
| 1022:1538 |           | AMD        | Family 16h Processor Func... | 140   |            | C081ADAAE3 |
| 1002:43a2 | 1002:0000 | AMD        | SB900 PCI to PCI bridge (... | 134   | shpchp     | F7B38B6B8B |
| 1022:1415 | 1022:1234 | AMD        | Family 15h (Models 10h-1f... | 133   | shpchp     | 67B0C18725 |
| 1022:15b0 |           | AMD        | Stoney HT Configuration      | 132   |            | C61C9E33F6 |
| 1022:15b1 |           | AMD        | Stoney Address Maps          | 132   |            | C61C9E33F6 |
| 1022:15b2 |           | AMD        | Stoney DRAM Configuration    | 132   |            | C61C9E33F6 |
| 1022:15b3 |           | AMD        | Stoney Miscellaneous Conf... | 132   | k10temp    | C61C9E33F6 |
| 1022:15b4 |           | AMD        | Stoney PM Configuration      | 132   | fam15h_... | C61C9E33F6 |
| 1022:15b5 |           | AMD        | Stoney NB Performance Mon... | 132   |            | C61C9E33F6 |
| 1002:43a3 | 1002:0000 | AMD        | SB900 PCI to PCI bridge (... | 126   | shpchp     | 4201CDD966 |
| 1022:1707 | 1022:1234 | AMD        | Family 12h Processor Root... | 125   | shpchp     | 04E7074682 |
| 1022:170a | 1022:1234 | AMD        | Family 12h Processor Root... | 124   | shpchp     | 04E7074682 |
| 1022:1300 |           | AMD        | Family 11h Processor Hype... | 114   |            | 6E4F973484 |
| 1022:1301 |           | AMD        | Family 11h Processor Addr... | 114   |            | 6E4F973484 |
| 1022:1302 |           | AMD        | Family 11h Processor DRAM... | 114   |            | 6E4F973484 |
| 1022:1303 |           | AMD        | Family 11h Processor Misc... | 114   | k10temp    | 6E4F973484 |
| 1022:1304 |           | AMD        | Family 11h Processor Link... | 114   |            | 6E4F973484 |
| 8086:0151 | 17aa:3977 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 112   | shpchp     | F3D7E4E13D |
| 1039:000a | 1039:0004 | Silicon... | PCI-to-PCI bridge            | 110   | shpchp     | 868812FE2A |
| 8086:0101 | 17aa:3975 | Intel      | Xeon E3-1200/2nd Generati... | 107   | shpchp     | A7618091FB |
| 1022:9602 | 1022:9602 | AMD        | RS780/RS880 PCI to PCI br... | 104   | shpchp     | 6E4F973484 |
| 1022:170b | 1022:1234 | AMD        | Family 12h Processor Root... | 97    | shpchp     | 2C903F36D0 |
| 8086:2940 |           | Intel      | 82801I (ICH9 Family) PCI ... | 97    | shpchp     | C5ADBBB2B3 |
| 8086:294a |           | Intel      | 82801I (ICH9 Family) PCI ... | 96    | shpchp     | C5ADBBB2B3 |
| 1022:1452 |           | AMD        | Family 17h (Models 00h-1f... | 93    |            | D7977A3B0E |
| 1002:5a3f | 1002:5a3f | AMD        | RC4xx/RS4xx PCI Bridge [i... | 92    | shpchp     | 54C92BF69C |
| 8086:a010 | 1043:83ac | Intel      | Atom Processor D4xx/D5xx/... | 92    | agpgart... | B658C90327 |
| 1039:0004 | 1039:0004 | Silicon... | PCI-to-PCI bridge            | 91    | shpchp     | 868812FE2A |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:5287 | 1043:202f | Realtek... | RTL8411B PCI Express Card... | 87    | rtsx_pci   | DDA26EE2AA |
| 10ec:5286 | 10ec:5286 | Realtek... | RTL8402 Integrated 1-LUN ... | 80    | rtsx_pci   | EFA97B65E3 |
| 10ec:5289 | 1043:202f | Realtek... | RTL8411 PCI Express Card ... | 73    | rtsx_pci   | 0F8CE4DCC0 |
| 10ec:5286 | 1043:202f | Realtek... | RTL8402 Integrated 1-LUN ... | 60    | rtsx_pci   | 5AEE6B7CA7 |
| 10ec:5209 | 1025:0685 | Realtek... | RTS5209 PCI Express Card ... | 40    | rtsx_pci   | BB4B4DE9DD |
| 10ec:5287 | 1025:0866 | Realtek... | RTL8411B PCI Express Card... | 35    | rtsx_pci   | 1C77D7A584 |
| 10ec:5289 | 10ec:5289 | Realtek... | RTL8411 PCI Express Card ... | 34    | rtsx_pci   | E103A76D85 |
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
| 10ec:5289 | 1025:0724 | Realtek... | RTL8411 PCI Express Card ... | 15    | rtsx_pci   | 68C4019E33 |
| 10ec:5209 | 103c:1672 | Realtek... | RTS5209 PCI Express Card ... | 14    | rtsx_pci   | 05F2682C5B |
| 10ec:522a | 10ec:522a | Realtek... | RTS522A PCI Express Card ... | 14    | rtsx_pci   | 9104464264 |
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
| 10ec:5229 | 17aa:5018 | Realtek... | RTS5229 PCI Express Card ... | 9     | rtsx_pci   | 991CC1AF7C |
| 10ec:522a | 103c:8101 | Realtek... | RTS522A PCI Express Card ... | 9     | rtsx_pci   | B9E21A89DA |
| 10ec:525a | 1028:087d | Realtek... | RTS525A PCI Express Card ... | 9     | rtsx_pci   | 75F82151FF |
| 10ec:5287 | 1558:0945 | Realtek... | RTL8411B PCI Express Card... | 9     | rtsx_pci   | 749E4A0BA1 |
| 10ec:5209 | 103c:3672 | Realtek... | RTS5209 PCI Express Card ... | 8     | rtsx_pci   | 7306A03690 |
| 10ec:5227 | 10cf:187f | Realtek... | RTS5227 PCI Express Card ... | 8     | rtsx_pci   | 491E66B3D8 |
| 10ec:5229 | 103c:1842 | Realtek... | RTS5229 PCI Express Card ... | 8     | rtsx_pci   | FEF9011BE9 |
| 10ec:5229 | 103c:184c | Realtek... | RTS5229 PCI Express Card ... | 8     | rtsx_pci   | B0D6527F67 |
| 10ec:5229 | 103c:216c | Realtek... | RTS5229 PCI Express Card ... | 8     | rtsx_pci   | 67B0C18725 |
| 10ec:5229 | 17aa:5000 | Realtek... | RTS5229 PCI Express Card ... | 8     | rtsx_pci   | FA98476936 |
| 10ec:522a | 103c:837d | Realtek... | RTS522A PCI Express Card ... | 8     | rtsx_pci   | 9B82C44F0C |
| 10ec:525a | 1028:082a | Realtek... | RTS525A PCI Express Card ... | 8     | rtsx_pci   | 174CC02B16 |
| 10ec:525a | 1028:08af | Realtek... | RTS525A PCI Express Card ... | 8     | rtsx_pci   | D4A2D02674 |
| 10ec:5287 | 1025:079b | Realtek... | RTL8411B PCI Express Card... | 8     | rtsx_pci   | 07CD36611F |
| 10ec:5287 | 1025:0865 | Realtek... | RTL8411B PCI Express Card... | 8     | rtsx_pci   | B8D1E63435 |
| 10ec:5287 | 1025:118a | Realtek... | RTL8411B PCI Express Card... | 8     | rtsx_pci   | C80CAABFC9 |
| 1aea:6621 | 1aea:6621 | Alcor M... | Alcor Micro PCIe Card Reader | 8     | alcor_pci  | B4ED65654C |
| 10ec:5209 | 1025:0690 | Realtek... | RTS5209 PCI Express Card ... | 7     | rtsx_pci   | 018F45163A |
| 10ec:5209 | 104d:9099 | Realtek... | RTS5209 PCI Express Card ... | 7     | rtsx_pci   | 3DA1069C3D |
| 10ec:5227 | 103c:1942 | Realtek... | RTS5227 PCI Express Card ... | 7     | rtsx_pci   | CE6DF77B4C |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0aa3 | 10de:cb79 | Nvidia     | MCP79 Co-processor           | 21    | nvidia     | 9F753AC669 |
| 10de:0aa3 | 1043:1cf7 | Nvidia     | MCP79 Co-processor           | 18    | nvidia     | F0A1399A3F |
| 10de:0543 | 1025:0126 | Nvidia     | MCP67 Co-processor           | 17    |            | F7695ADD11 |
| 10de:0753 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] Co-... | 15    |            | 265A212FDC |
| 10de:0aa3 | 1043:1fa7 | Nvidia     | MCP79 Co-processor           | 13    | nvidia     | C4A5E49D47 |
| 10de:0d7a | 10de:cb89 | Nvidia     | MCP89 Co-Processor           | 12    |            | 80ECBDE76E |
| 10de:0543 | 103c:30cf | Nvidia     | MCP67 Co-processor           | 9     |            | 1184F5572B |
| 10de:0aa3 | 1043:8402 | Nvidia     | MCP79 Co-processor           | 9     | nvidia     | 353AB385C9 |
| 10de:0271 | 103c:30b7 | Nvidia     | MCP51 PMU                    | 6     |            | B699788F33 |
| 10de:0543 | 1043:16a7 | Nvidia     | MCP67 Co-processor           | 5     |            | 9227856E4A |
| 10de:0aa3 | 103c:3651 | Nvidia     | MCP79 Co-processor           | 5     | nvidia     | 535E45E25D |
| 10de:0aa3 | 1025:0160 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | 69DC96A4D0 |
| 10de:0aa3 | 1462:1012 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | FE43B38080 |
| 10de:0271 | 103c:30e5 | Nvidia     | MCP51 PMU                    | 3     |            | 45FC8F4912 |
| 10de:0447 | 103c:30cf | Nvidia     | MCP65 SMU                    | 3     |            | 084F7E13DA |
| 10de:0aa3 | 1043:1d17 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 14A1FEC4BA |
| 10de:0271 | 103c:30b5 | Nvidia     | MCP51 PMU                    | 2     |            | E964514E68 |
| 10de:0271 | 1043:1367 | Nvidia     | MCP51 PMU                    | 2     |            | D455CC767C |
| 10de:0271 | 1462:3fc1 | Nvidia     | MCP51 PMU                    | 2     |            | 278EF4A255 |
| 10de:0543 | 103c:30d6 | Nvidia     | MCP67 Co-processor           | 2     |            | 3B57385D7E |
| 10de:0543 | 103c:30ea | Nvidia     | MCP67 Co-processor           | 2     |            | 8BC37D1961 |
| 10de:0aa3 | 1043:1a87 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | C2D93613D4 |
| 10de:0aa3 | 1462:1019 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | 2054B3A4CC |
| 10de:0aa3 | 1734:1151 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | 47DF471783 |
| 10de:0aa3 | 17aa:38da | Nvidia     | MCP79 Co-processor           | 2     |            | C38D40E936 |
| 10de:0271 | 103c:30bf | Nvidia     | MCP51 PMU                    | 1     |            | 4A6A073320 |
| 10de:0271 | 1043:1322 | Nvidia     | MCP51 PMU                    | 1     |            | 71FE8FB963 |
| 10de:0271 | 1462:373d | Nvidia     | MCP51 PMU                    | 1     |            | F6C1542CAC |
| 10de:0271 | 1734:10d3 | Nvidia     | MCP51 PMU                    | 1     |            | 6172D9B266 |
| 10de:0543 | 1025:0127 | Nvidia     | MCP67 Co-processor           | 1     |            | DB69CCC0BF |
| 10de:0543 | 1043:1697 | Nvidia     | MCP67 Co-processor           | 1     |            | C3296D5344 |
| 10de:0753 | 1025:014a | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | F63FFEFC64 |
| 10de:0753 | 1462:6520 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 12132D4EBD |
| 10de:0753 | 1462:6720 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | E6DAA26D63 |
| 10de:0aa3 | 1028:0271 | Nvidia     | MCP79 Co-processor           | 1     |            | 0238C91A6C |
| 10de:0aa3 | 1071:9070 | Nvidia     | MCP79 Co-processor           | 1     |            | 3D0D6AEFBF |
| 10de:0aa3 | 1071:9515 | Nvidia     | MCP79 Co-processor           | 1     | nvidia     | E028F277D4 |
| 10de:0aa3 | 1b0a:4203 | Nvidia     | MCP79 Co-processor           | 1     |            | 926753D3C7 |
| 10de:0aa3 | 1b7d:0040 | Nvidia     | MCP79 Co-processor           | 1     |            | 053ACCA095 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e3a | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 258   | mei_me     | 891002E8F2 |
| 8086:1c3a | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 162   | mei_me     | A7618091FB |
| 8086:9c3a | 17aa:3978 | Intel      | 8 Series HECI #0             | 88    | mei_me     | C0E6FFA24F |
| 8086:3b64 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 85    | mei_me     | 49783F833C |
| 8086:1c3a | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 80    | mei_me     | 6B25B8982D |
| 8086:1e3a | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 80    | mei_me     | F28D18F3E9 |
| 8086:3b64 | 17aa:215f | Intel      | 5 Series/3400 Series Chip... | 77    | mei_me     | DA5E944C6C |
| 8086:3b64 | 17aa:38a5 | Intel      | 5 Series/3400 Series Chip... | 70    | mei_me     | 62697BF35B |
| 8086:1e3a | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 69    | mei_me     | CE3DDF28FC |
| 8086:1c3a | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 65    | mei_me     | 8579BA1B16 |
| 8086:2a44 | 17aa:20e6 | Intel      | Mobile 4 Series Chipset M... | 62    | mei_me     | FDAB3CF92F |
| 8086:1e3a | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 61    | mei_me     | E67DFC255A |
| 8086:1c3a | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 60    | mei_me     | 826F5492EB |
| 8086:1e3a | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 60    | mei_me     | 6478022B75 |
| 8086:1e3a | 1043:124d | Intel      | 7 Series/C216 Chipset Fam... | 59    | mei_me     | 0F8CE4DCC0 |
| 8086:3b64 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 56    | mei_me     | D023F50697 |
| 8086:8c3a | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 52    | mei_me     | 262BB6B100 |
| 8086:1e3a | 17aa:5011 | Intel      | 7 Series/C216 Chipset Fam... | 46    | mei_me     | 65D329A2C6 |
| 8086:1e3a | 1043:14c7 | Intel      | 7 Series/C216 Chipset Fam... | 45    | mei_me     | 9A401175B3 |
| 8086:1c3a | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 44    | mei_me     | EE56C112BB |
| 8086:1c3a | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 43    | mei_me     | EA07B48EB4 |
| 8086:1c3a | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 41    | mei_me     | C0868A2B0C |
| 8086:3b64 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 39    | mei_me     | 3C5767E938 |
| 8086:1c3a | 144d:c0b6 | Intel      | 6 Series/C200 Series Chip... | 38    | mei_me     | 616616B60F |
| 8086:1e3a | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 38    | mei_me     | 39CA2BE7BB |
| 8086:1c3a | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 35    | mei_me     | FBF8462F41 |
| 8086:9c3a | 1025:0866 | Intel      | 8 Series HECI #0             | 34    | mei_me     | 1C77D7A584 |
| 8086:5a9a | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 32    | mei_me     | 0FAD7AC4EB |
| 8086:1e3a | 17aa:21f6 | Intel      | 7 Series/C216 Chipset Fam... | 31    | mei_me     | 7DA7A083D7 |
| 8086:1e3a | 1043:1587 | Intel      | 7 Series/C216 Chipset Fam... | 30    | mei_me     | 469E04E0D5 |
| 8086:1e3a | 1179:fb31 | Intel      | 7 Series/C216 Chipset Fam... | 30    | mei_me     | 806B890CCF |
| 8086:1e3a | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 30    | mei_me     | 6D5F1234C2 |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 30    | mei_me     | 1579402536 |
| 8086:9c3a | 1025:0775 | Intel      | 8 Series HECI #0             | 29    | mei_me     | 3BD8AD186F |
| 8086:1c3a | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 28    | mei_me     | CA6EFEBBD7 |
| 8086:1e3a | 1043:1477 | Intel      | 7 Series/C216 Chipset Fam... | 28    | mei_me     | C38728C67C |
| 8086:1e3a | 144d:c652 | Intel      | 7 Series/C216 Chipset Fam... | 28    | mei_me     | A57B555F26 |
| 8086:3b64 | 144d:c581 | Intel      | 5 Series/3400 Series Chip... | 28    | mei_me     | 4B260556B7 |
| 8086:9c3a | 1028:0651 | Intel      | 8 Series HECI #0             | 27    | mei_me     | 1E1FE2154B |
| 8086:9c3a | 1043:131d | Intel      | 8 Series HECI #0             | 27    | mei_me     | 761A86BDC8 |
| 8086:1e3a | 10cf:16ea | Intel      | 7 Series/C216 Chipset Fam... | 26    | mei_me     | B9A4817612 |
| 8086:1e3a | 144d:c0d8 | Intel      | 7 Series/C216 Chipset Fam... | 26    | mei_me     | 0F042024B4 |
| 8086:9d3a | 1025:1193 | Intel      | Sunrise Point-LP CSME HEC... | 26    | mei_me     | 141D7917FF |
| 8086:1e3a | 1025:0686 | Intel      | 7 Series/C216 Chipset Fam... | 25    | mei_me     | 29CFE1AD23 |
| 8086:1e3a | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 25    | mei_me     | DB9250D9E0 |
| 8086:1c3a | 104d:908b | Intel      | 6 Series/C200 Series Chip... | 24    | mei_me     | BD70BB63B5 |
| 8086:9c3a | 1043:16cd | Intel      | 8 Series HECI #0             | 24    | mei_me     | FDD61F096B |
| 8086:1c3a | 103c:167c | Intel      | 6 Series/C200 Series Chip... | 23    | mei_me     | 15E5D2BB9D |
| 8086:3b64 | 1025:036d | Intel      | 5 Series/3400 Series Chip... | 23    | mei_me     | 333F038ACE |
| 8086:9d3a | 1025:1085 | Intel      | Sunrise Point-LP CSME HEC... | 23    | mei_me     | AE1CE65D11 |
| 8086:1c3a | 1025:0511 | Intel      | 6 Series/C200 Series Chip... | 22    | mei_me     | F618F23CD4 |
| 8086:1c3a | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 22    | mei_me     | 88B8816BFE |
| 8086:1e3a | 103c:1818 | Intel      | 7 Series/C216 Chipset Fam... | 22    | mei_me     | C865BDB72F |
| 8086:1e3a | 104d:90b8 | Intel      | 7 Series/C216 Chipset Fam... | 22    | mei_me     | 66E469F722 |
| 8086:1e3a | 1025:0835 | Intel      | 7 Series/C216 Chipset Fam... | 21    | mei_me     | AB33DE8D3B |
| 8086:1e3a | 104d:90ab | Intel      | 7 Series/C216 Chipset Fam... | 21    | mei_me     | B56B7F6394 |
| 8086:3b64 | 10cf:152b | Intel      | 5 Series/3400 Series Chip... | 21    | mei_me     | EEFC712947 |
| 8086:9cba | 1025:098a | Intel      | Wildcat Point-LP MEI Cont... | 21    | mei_me     | 6D1C781DE0 |
| 8086:9d3a | 1025:115f | Intel      | Sunrise Point-LP CSME HEC... | 21    | mei_me     | E4B342382F |
| 8086:9d3a | 17aa:3801 | Intel      | Sunrise Point-LP CSME HEC... | 21    | mei_me     | 005771EDFD |
| 8086:1c3a | 103c:1670 | Intel      | 6 Series/C200 Series Chip... | 20    | mei_me     | FC29696703 |
| 8086:1c3a | 1179:fc30 | Intel      | 6 Series/C200 Series Chip... | 20    | mei_me     | FE2AB22987 |
| 8086:1c3a | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 20    | mei_me     | 23DAC0F1B6 |
| 8086:1e3a | 103c:183e | Intel      | 7 Series/C216 Chipset Fam... | 20    | mei_me     | 19D5DAD934 |
| 8086:3b64 | 1179:ff1e | Intel      | 5 Series/3400 Series Chip... | 20    | mei_me     | 725958F861 |
| 8086:9c3a | 17aa:220c | Intel      | 8 Series HECI #0             | 20    | mei_me     | 7637F3DE5F |
| 8086:1c3a | 103c:3388 | Intel      | 6 Series/C200 Series Chip... | 19    | mei_me     | EDC722485A |
| 8086:1e3a | 1b0a:20ca | Intel      | 7 Series/C216 Chipset Fam... | 19    | mei_me     | 052EF081E3 |
| 8086:3b64 | 1025:0498 | Intel      | 5 Series/3400 Series Chip... | 19    | mei_me     | DFC1F3692A |
| 8086:3b64 | 103c:143a | Intel      | 5 Series/3400 Series Chip... | 19    | mei_me     | 2E967DD7C0 |
| 8086:8c3a | 8086:2010 | Intel      | 8 Series/C220 Series Chip... | 19    | mei_me     | DEDB8E43CB |
| 8086:1e3a | 1028:0597 | Intel      | 7 Series/C216 Chipset Fam... | 18    | mei_me     | 6C7804AC48 |
| 8086:9d3a |           | Intel      | Sunrise Point-LP CSME HEC... | 18    | mei_me     | 39C3F65CF9 |
| 8086:9d3a | 103c:832a | Intel      | Sunrise Point-LP CSME HEC... | 18    | mei_me     | 8B699D7E6C |
| 8086:1c3a | 1025:050e | Intel      | 6 Series/C200 Series Chip... | 17    | mei_me     | 8CB0F2007B |
| 8086:1e3a | 103c:179b | Intel      | 7 Series/C216 Chipset Fam... | 17    | mei_me     | ED317797F0 |
| 8086:1e3a | 103c:17f6 | Intel      | 7 Series/C216 Chipset Fam... | 17    | mei_me     | AB69AA73CD |
| 8086:1e3a | 1043:1457 | Intel      | 7 Series/C216 Chipset Fam... | 17    | mei_me     | 1AC2B8EE74 |
| 8086:8c3a | 1043:129d | Intel      | 8 Series/C220 Series Chip... | 17    | mei_me     | 2D1845C282 |
| 8086:9cba | 1043:10d0 | Intel      | Wildcat Point-LP MEI Cont... | 17    | mei_me     | B507AA7D6F |
| 8086:9cba | 17aa:390b | Intel      | Wildcat Point-LP MEI Cont... | 17    | mei_me     | 7A87F02269 |
| 8086:9d3a | 1043:1a00 | Intel      | Sunrise Point-LP CSME HEC... | 17    | mei_me     | BEB89C26D9 |
| 8086:9d3a | 17aa:386e | Intel      | Sunrise Point-LP CSME HEC... | 17    | mei_me     | 240FE2C985 |
| 8086:1c3a | 103c:161c | Intel      | 6 Series/C200 Series Chip... | 16    | mei_me     | 6F7AAF1391 |
| 8086:1c3a | 144d:c0c1 | Intel      | 6 Series/C200 Series Chip... | 16    | mei_me     | 6150CCFA00 |
| 8086:1c3a | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 16    | mei_me     | E7A16D4FC1 |
| 8086:1e3a | 103c:1858 | Intel      | 7 Series/C216 Chipset Fam... | 16    | mei_me     | F7D8D4D158 |
| 8086:1e3a | 1043:117d | Intel      | 7 Series/C216 Chipset Fam... | 16    | mei_me     | 8C2A862254 |
| 8086:319a | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 16    | mei_me     | AAAC90F58C |
| 8086:3b64 | 1025:0601 | Intel      | 5 Series/3400 Series Chip... | 16    | mei_me     | 1ABB956626 |
| 8086:3b64 | 1028:0447 | Intel      | 5 Series/3400 Series Chip... | 16    | mei_me     | 26FD2C3388 |
| 8086:3b64 | 1043:1f27 | Intel      | 5 Series/3400 Series Chip... | 16    | mei_me     | A6D13752DA |
| 8086:8c3a | 1025:0781 | Intel      | 8 Series/C220 Series Chip... | 16    | mei_me     | 6CC64DA5C5 |
| 8086:9cba | 17aa:382a | Intel      | Wildcat Point-LP MEI Cont... | 16    | mei_me     | 2AB250A99B |
| 8086:1e3a | 103c:1854 | Intel      | 7 Series/C216 Chipset Fam... | 15    | mei_me     | 69CEE0DC90 |
| 8086:1e3a | 1558:1550 | Intel      | 7 Series/C216 Chipset Fam... | 15    | mei_me     | 4671F06112 |
| 8086:3b64 | 103c:7008 | Intel      | 5 Series/3400 Series Chip... | 15    | mei_me     | AB17752168 |
| 8086:8c3a | 1043:11cd | Intel      | 8 Series/C220 Series Chip... | 15    | mei_me     | D3769C3F4D |
| 8086:8c3a | 1558:6502 | Intel      | 8 Series/C220 Series Chip... | 15    | mei_me     | 5A5E21619D |
| 8086:9cba | 1043:1a6d | Intel      | Wildcat Point-LP MEI Cont... | 15    | mei_me     | 5919CA05FE |

### Dma controller (eisa dma) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9ce0 | 8086:9ce0 | Intel      | Wildcat Point-LP Serial I... | 8     | dw_dmac... | 5515E7AA30 |
| 8086:2286 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 4     | dw_dmac... | 8069B2A3BC |
| 8086:22c0 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 4     | dw_dmac... | 8069B2A3BC |
| 8086:9c60 |           | Intel      | 8 Series Low Power Sub-Sy... | 4     | dw_dmac... | 1D4DA7DE61 |
| 8086:9c60 | 1025:0a11 | Intel      | 8 Series Low Power Sub-Sy... | 2     | dw_dmac... | F304E3BA6B |
| 8086:0f40 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | 0994A3EEB3 |
| 8086:9c60 | 103c:21ed | Intel      | 8 Series Low Power Sub-Sy... | 1     | dw_dmac... | ED9149D4A2 |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1537 | 1022:1537 | AMD        | Kabini/Mullins PSP-Platfo... | 111   | ccp        | 1CC2218397 |
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 70    | mei_txe    | 4414412FCB |
| 8086:0f18 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 54    | mei_txe    | CC7193A7B9 |
| 8086:0f18 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 45    | mei_txe    | 0994A3EEB3 |
| 1022:1537 | 17aa:3801 | AMD        | Kabini/Mullins PSP-Platfo... | 42    | ccp        | 760B445B08 |
| 8086:0f18 | 17aa:3909 | Intel      | Atom Processor Z36xxx/Z37... | 33    | mei_txe    | EE1CFF7014 |
| 1022:15df | 1022:15df | AMD        | Family 17h (Models 10h-1f... | 32    |            | 123447177A |
| 8086:0f18 | 1043:14dd | Intel      | Atom Processor Z36xxx/Z37... | 29    | mei_txe    | 8D51E5FEC5 |
| 8086:0f18 | 8086:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 28    | mei_txe    | CEAC334581 |
| 1022:1578 | 103c:8330 | AMD        | Carrizo Platform Security... | 27    |            | D32B7275C3 |
| 8086:2298 | 1025:1012 | Intel      | Atom/Celeron/Pentium Proc... | 27    | mei_txe    | 5A7F96289D |
| 8086:0f18 | 1297:2041 | Intel      | Atom Processor Z36xxx/Z37... | 26    | mei_txe    | 100EB984CA |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 24    |            | 259A32BE33 |
| 1022:1578 | 1025:1192 | AMD        | Carrizo Platform Security... | 22    |            | 0D71E52A34 |
| 8086:0f18 | 103c:2213 | Intel      | Atom Processor Z36xxx/Z37... | 22    | mei_txe    | 964E06B446 |
| 8086:0f18 | 1043:161d | Intel      | Atom Processor Z36xxx/Z37... | 22    | mei_txe    | BDFF3A60F1 |
| 8086:2298 | 1043:10c0 | Intel      | Atom/Celeron/Pentium Proc... | 22    | mei_txe    | F8FDA4EFC3 |
| 8086:0f18 | 17aa:3986 | Intel      | Atom Processor Z36xxx/Z37... | 20    | mei_txe    | E3105C7B7A |
| 1022:1578 | 17aa:3810 | AMD        | Carrizo Platform Security... | 17    |            | C61C9E33F6 |
| 8086:0f18 | 1043:15bd | Intel      | Atom Processor Z36xxx/Z37... | 17    | mei_txe    | CE2184CB68 |
| 1022:1537 | 17aa:3808 | AMD        | Kabini/Mullins PSP-Platfo... | 15    | ccp        | 10DEE916FF |
| 1022:15df | 103c:84ae | AMD        | Family 17h (Models 10h-1f... | 14    |            | E8755C7EF8 |
| 8086:2298 | 17aa:3808 | Intel      | Atom/Celeron/Pentium Proc... | 14    | mei_txe    | 7957C03703 |
| 8086:2298 | 1028:06ac | Intel      | Atom/Celeron/Pentium Proc... | 13    | mei_txe    | CE847DF44A |
| 1022:1578 | 103c:8331 | AMD        | Carrizo Platform Security... | 12    |            | 9111BD09BB |
| 8086:2298 | 1043:12e0 | Intel      | Atom/Celeron/Pentium Proc... | 12    | mei_txe    | 6458C4F07B |
| 1022:1537 | 1025:104b | AMD        | Kabini/Mullins PSP-Platfo... | 11    | ccp        | 35F6E0CE5F |
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
| 8086:0f18 | 1025:0905 | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | 50FFA5DCEC |
| 8086:0f18 | 103c:2190 | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | E900AD9CFC |
| 8086:0f18 | 103c:21de | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | 4677C67DBA |
| 8086:0f18 | 1043:176d | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | 4E37AD043D |
| 8086:2298 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 7     | mei_txe    | D91699583D |
| 8086:2298 | 103c:80c5 | Intel      | Atom/Celeron/Pentium Proc... | 7     | mei_txe    | E1B215CA26 |
| 8086:2298 | 1043:10b0 | Intel      | Atom/Celeron/Pentium Proc... | 7     | mei_txe    | AA9F4B66AD |
| 8086:2298 | 1043:191d | Intel      | Atom/Celeron/Pentium Proc... | 7     | mei_txe    | 70DE2F36AE |
| 8086:0f18 | 1025:089d | Intel      | Atom Processor Z36xxx/Z37... | 6     | mei_txe    | 2619209EC5 |
| 8086:0f18 | 1025:0936 | Intel      | Atom Processor Z36xxx/Z37... | 6     | mei_txe    | A1D2E02773 |
| 8086:0f18 | 1025:0939 | Intel      | Atom Processor Z36xxx/Z37... | 6     | mei_txe    | 39B0D513AA |
| 1022:1537 | 103c:2269 | AMD        | Kabini/Mullins PSP-Platfo... | 5     | ccp        | 9A3053250C |
| 1022:1578 | 17aa:380b | AMD        | Carrizo Platform Security... | 5     |            | FF3ABD912F |
| 1022:15df | 103c:84d2 | AMD        | Family 17h (Models 10h-1f... | 5     |            | DEFB86D43A |
| 8086:0f18 | 1028:064d | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | C72380C4E8 |
| 8086:0f18 | 103c:220f | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | 6F9FB4A3FD |
| 8086:0f18 | 1043:16dd | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | 7297A28A7F |
| 8086:0f18 | 17aa:3807 | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | 5C27867F6E |
| 8086:0f18 | 17aa:3985 | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | 1004F2D148 |
| 8086:2298 | 1025:1010 | Intel      | Atom/Celeron/Pentium Proc... | 5     | mei_txe    | C5CB60A44F |
| 8086:2298 | 1028:0725 | Intel      | Atom/Celeron/Pentium Proc... | 5     | mei_txe    | 94A897D5A7 |
| 8086:2298 | 103c:82bd | Intel      | Atom/Celeron/Pentium Proc... | 5     | mei_txe    | 8A7389044C |
| 8086:2298 | 1297:2063 | Intel      | Atom/Celeron/Pentium Proc... | 5     | mei_txe    | 2D91F64A77 |
| 1022:1456 | 1022:1456 | AMD        | Family 17h (Models 00h-0f... | 4     | ccp        | 35BF9EB2EF |
| 1022:1537 | 103c:226a | AMD        | Kabini/Mullins PSP-Platfo... | 4     | ccp        | 4B70A9D252 |
| 1022:1537 | 103c:226b | AMD        | Kabini/Mullins PSP-Platfo... | 4     | ccp        | 01CBF7482C |
| 1022:1578 | 103c:81f9 | AMD        | Carrizo Platform Security... | 4     |            | 7FAA2ABF56 |
| 1022:1578 | 103c:8345 | AMD        | Carrizo Platform Security... | 4     |            | 7E3B6FA95F |
| 1022:1578 | 17aa:380f | AMD        | Carrizo Platform Security... | 4     |            | C19D82302D |
| 1022:15df | 1025:125c | AMD        | Family 17h (Models 10h-1f... | 4     |            | 6AEFA7E06C |
| 8086:0f18 |           | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | A154D9D080 |
| 8086:0f18 | 1025:0860 | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 4086083D68 |
| 8086:0f18 | 1025:0928 | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | C10F5336A8 |
| 8086:0f18 | 1043:14ed | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 492943101C |
| 8086:0f18 | 1179:f91b | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 71C7CF2056 |
| 8086:0f18 | 17aa:390c | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 54908845C3 |
| 8086:2298 | 103c:8320 | Intel      | Atom/Celeron/Pentium Proc... | 4     | mei_txe    | E97A9CF2C6 |
| 8086:2298 | 103c:8342 | Intel      | Atom/Celeron/Pentium Proc... | 4     | mei_txe    | F8B5956A65 |
| 1022:1537 | 1025:0960 | AMD        | Kabini/Mullins PSP-Platfo... | 3     | ccp        | 64956D50FC |
| 1022:1537 | 103c:80b8 | AMD        | Kabini/Mullins PSP-Platfo... | 3     | ccp        | 5048EB8853 |
| 1022:1537 | 103c:82f6 | AMD        | Kabini/Mullins PSP-Platfo... | 3     | ccp        | B09BE0C6DA |
| 1022:1537 | 103c:82f7 | AMD        | Kabini/Mullins PSP-Platfo... | 3     | ccp        | 137E2EA71E |
| 1022:1578 | 1025:109f | AMD        | Carrizo Platform Security... | 3     |            | 41E017C4AE |
| 1022:1578 | 1025:1201 | AMD        | Carrizo Platform Security... | 3     |            | 1D59285089 |
| 1022:1578 | 1028:087e | AMD        | Carrizo Platform Security... | 3     |            | 5DA2258C77 |
| 1022:1578 | 103c:81fa | AMD        | Carrizo Platform Security... | 3     |            | BAEB555043 |
| 1022:1578 | 103c:8332 | AMD        | Carrizo Platform Security... | 3     |            | 5B3D1F6E1E |
| 1022:1578 | 17aa:380c | AMD        | Carrizo Platform Security... | 3     |            | 3C184815C4 |
| 1022:15df | 1028:0812 | AMD        | Family 17h (Models 10h-1f... | 3     |            | 2EF740F66D |
| 1022:15df | 103c:84e7 | AMD        | Family 17h (Models 10h-1f... | 3     |            | 788CB4019C |
| 1022:15df | 103c:85ea | AMD        | Family 17h (Models 10h-1f... | 3     |            | D7977A3B0E |
| 1022:15df | 17aa:3804 | AMD        | Family 17h (Models 10h-1f... | 3     |            | 102D5EFAD5 |
| 8086:0f18 | 1025:087f | Intel      | Atom Processor Z36xxx/Z37... | 3     | mei_txe    | 60681259FD |
| 8086:0f18 | 1028:06ab | Intel      | Atom Processor Z36xxx/Z37... | 3     | mei_txe    | FF1BF9089C |
| 8086:0f18 | 103c:8023 | Intel      | Atom Processor Z36xxx/Z37... | 3     | mei_txe    | 8CAFEBD59C |
| 8086:0f18 | 17aa:3904 | Intel      | Atom Processor Z36xxx/Z37... | 3     | mei_txe    | 92BEFCA350 |
| 8086:0f18 | 17aa:3907 | Intel      | Atom Processor Z36xxx/Z37... | 3     | mei_txe    | D0C5A93E77 |
| 8086:2298 | 1025:100f | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | D6E27568F6 |
| 8086:2298 | 1025:108c | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | F590C9BDB7 |
| 8086:2298 | 103c:813e | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | F91E0FBE6B |
| 8086:2298 | 103c:8175 | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | 995E0C3E1F |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1180:0832 | 17aa:20c7 | Ricoh      | R5C832 IEEE 1394 Controller  | 84    | firewir... | A23E000798 |
| 104c:803a | 1025:011f | Texas I... | PCIxx12 OHCI Compliant IE... | 64    | firewir... | 7387D70AD5 |
| 11c1:5901 | 11c1:5900 | LSI        | FW643 [TrueFire] PCIe 139... | 56    | firewir... | 9F753AC669 |
| 104c:803a | 1179:ff00 | Texas I... | PCIxx12 OHCI Compliant IE... | 42    | firewir... | 3CE1664885 |
| 1180:e832 | 17aa:2136 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 34    | firewir... | DA5E944C6C |
| 1180:0832 | 1028:0233 | Ricoh      | R5C832 IEEE 1394 Controller  | 30    | firewir... | 1F49A84F1F |
| 1180:0832 | 103c:30cc | Ricoh      | R5C832 IEEE 1394 Controller  | 27    | firewir... | 9EDE738BFC |
| 1217:00f7 | 1028:01f9 | O2 Micro   | Firewire (IEEE 1394)         | 27    | firewir... | C331358BBE |
| 104c:803a | 103c:30a2 | Texas I... | PCIxx12 OHCI Compliant IE... | 22    | firewir... | 531D26CDD8 |
| 1180:0832 | 1025:011e | Ricoh      | R5C832 IEEE 1394 Controller  | 21    | firewir... | ED83D72FBE |
| 1180:0832 | 1028:022f | Ricoh      | R5C832 IEEE 1394 Controller  | 21    | firewir... | 55CD396670 |
| 1180:e832 | 17aa:21f6 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 21    | firewir... | 7DA7A083D7 |
| 1180:e832 | 1028:040a | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 20    | firewir... | D588CD38C2 |
| 1217:00f7 | 1179:ff50 | O2 Micro   | Firewire (IEEE 1394)         | 18    | firewir... | B6017B2145 |
| 1180:0832 | 1025:0121 | Ricoh      | R5C832 IEEE 1394 Controller  | 17    | firewir... | CFBA4082BB |
| 1180:0832 | 1025:0126 | Ricoh      | R5C832 IEEE 1394 Controller  | 17    | firewir... | F7695ADD11 |
| 1180:0832 | 1043:1317 | Ricoh      | R5C832 IEEE 1394 Controller  | 16    | firewir... | B304C61746 |
| 11c1:5811 | 11c1:5811 | LSI        | FW322/323 [TrueFire] 1394... | 16    | firewir... | FDEA938323 |
| 1217:00f7 | 1217:00f7 | O2 Micro   | Firewire (IEEE 1394)         | 16    | firewir... | DE010A6F04 |
| 197b:2380 | 103c:161c | JMicron... | IEEE 1394 Host Controller    | 16    | firewir... | 6F7AAF1391 |
| 104c:803a | 1179:ff10 | Texas I... | PCIxx12 OHCI Compliant IE... | 15    | firewir... | 4FFE571137 |
| 1180:0832 | 103c:7008 | Ricoh      | R5C832 IEEE 1394 Controller  | 15    | firewir... | AB17752168 |
| 1180:0832 | 1043:1877 | Ricoh      | R5C832 IEEE 1394 Controller  | 15    | firewir... | CB27B32040 |
| 1180:0832 | 1043:1897 | Ricoh      | R5C832 IEEE 1394 Controller  | 15    | firewir... | 96E310C22E |
| 197b:2380 | 103c:179b | JMicron... | IEEE 1394 Host Controller    | 15    | firewir... | ED317797F0 |
| 197b:2380 | 103c:3628 | JMicron... | IEEE 1394 Host Controller    | 15    | firewir... | E09686C315 |
| 1180:e832 | 17aa:21cf | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 14    | firewir... | E7A16D4FC1 |
| 1180:0832 | 1043:14e7 | Ricoh      | R5C832 IEEE 1394 Controller  | 13    | firewir... | D9970BDA58 |
| 1180:0832 | 1028:01bd | Ricoh      | R5C832 IEEE 1394 Controller  | 12    | firewir... | 586A6A9F8A |
| 1180:0832 | 103c:30cf | Ricoh      | R5C832 IEEE 1394 Controller  | 12    | firewir... | 084F7E13DA |
| 1180:0832 | 1043:1767 | Ricoh      | R5C832 IEEE 1394 Controller  | 12    | firewir... | 4137AC8F54 |
| 1180:0832 | 104d:9035 | Ricoh      | R5C832 IEEE 1394 Controller  | 12    | firewir... | A3C4D07088 |
| 1180:0832 | 1179:ff1c | Ricoh      | R5C832 IEEE 1394 Controller  | 12    | firewir... | 588EAD6870 |
| 1180:e832 | 1028:040b | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 12    | firewir... | 80B359DC57 |
| 1180:e832 | 17aa:21ce | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 12    | firewir... | 029641C14A |
| 197b:2380 | 103c:17ab | JMicron... | IEEE 1394 Host Controller    | 12    | firewir... | 3B64B265CF |
| 197b:2380 | 103c:3603 | JMicron... | IEEE 1394 Host Controller    | 12    | firewir... | 9CE29D0583 |
| 1180:0832 | 1028:024f | Ricoh      | R5C832 IEEE 1394 Controller  | 11    | firewir... | 5A8B3F34A3 |
| 1180:0832 | 1028:029a | Ricoh      | R5C832 IEEE 1394 Controller  | 11    | firewir... | 394D903321 |
| 1180:0832 | 1043:1517 | Ricoh      | R5C832 IEEE 1394 Controller  | 11    | firewir... | FAECBEFA9B |
| 1217:11f7 | 1028:04a3 | O2 Micro   | OZ600 1394a-2000 Controller  | 10    | firewir... | 19E1CA5871 |
| 197b:2380 | 103c:3659 | JMicron... | IEEE 1394 Host Controller    | 10    | firewir... | AFAAE2AA59 |
| 1180:0832 | 103c:30bb | Ricoh      | R5C832 IEEE 1394 Controller  | 9     | firewir... | FB7F51216E |
| 1180:0832 | 103c:7007 | Ricoh      | R5C832 IEEE 1394 Controller  | 9     | firewir... | 83E800C91C |
| 1180:0832 | 10f7:8338 | Ricoh      | R5C832 IEEE 1394 Controller  | 9     | firewir... | FDCC1DFB81 |
| 11c1:5811 | 103c:30dd | LSI        | FW322/323 [TrueFire] 1394... | 9     | firewir... | 6832A5FE8D |
| 197b:2380 | 103c:30f4 | JMicron... | IEEE 1394 Host Controller    | 9     | firewir... | DDA054B15D |
| 104c:8032 | 103c:099c | Texas I... | OHCI Compliant IEEE 1394 ... | 8     | firewir... | E0DF895DC8 |
| 104c:803a | 1179:0001 | Texas I... | PCIxx12 OHCI Compliant IE... | 8     | firewir... | 3E0ED41BC7 |
| 1180:0832 | 1028:023a | Ricoh      | R5C832 IEEE 1394 Controller  | 8     | firewir... | 2B5F0594D3 |
| 1180:0832 | 103c:172a | Ricoh      | R5C832 IEEE 1394 Controller  | 8     | firewir... | E2C04796A0 |
| 1180:0832 | 103c:30be | Ricoh      | R5C832 IEEE 1394 Controller  | 8     | firewir... | 2B9B5142AF |
| 1180:0832 | 103c:30c0 | Ricoh      | R5C832 IEEE 1394 Controller  | 8     | firewir... | 21ACEB2150 |
| 1180:0832 | 103c:30db | Ricoh      | R5C832 IEEE 1394 Controller  | 8     | firewir... | 9792924118 |
| 1217:13f7 | 1028:0494 | O2 Micro   | 1394 OHCI Compliant Host ... | 8     | firewir... | A217BF3485 |
| 197b:2380 | 103c:1618 | JMicron... | IEEE 1394 Host Controller    | 8     | firewir... | 7D1AE28E6D |
| 104c:803a | 104d:902d | Texas I... | PCIxx12 OHCI Compliant IE... | 7     | firewir... | BD8A19714A |
| 1106:3044 | 14c0:0020 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 7     | firewir... | 0351248973 |
| 1180:0552 | 1043:1237 | Ricoh      | R5C552 IEEE 1394 Controller  | 7     | firewir... | C1DA7EE91F |
| 1180:0832 | 1025:011d | Ricoh      | R5C832 IEEE 1394 Controller  | 7     | firewir... | 2BD735CBDF |
| 1180:0832 | 104d:900e | Ricoh      | R5C832 IEEE 1394 Controller  | 7     | firewir... | 3284C77676 |
| 1180:0832 | 1179:ff1e | Ricoh      | R5C832 IEEE 1394 Controller  | 7     | firewir... | CFEBF5C5A2 |
| 1180:0832 | 17aa:3829 | Ricoh      | R5C832 IEEE 1394 Controller  | 7     | firewir... | 74624FF493 |
| 1217:13f7 | 1028:049a | O2 Micro   | 1394 OHCI Compliant Host ... | 7     | firewir... | 5D67AE99E3 |
| 104c:803a | 103c:30aa | Texas I... | PCIxx12 OHCI Compliant IE... | 6     | firewir... | CF41AB5F1A |
| 104c:803a | 104d:81e6 | Texas I... | PCIxx12 OHCI Compliant IE... | 6     | firewir... | 50E5B9D6CA |
| 104c:803a | 104d:9005 | Texas I... | PCIxx12 OHCI Compliant IE... | 6     | firewir... | 858BD651B7 |
| 104c:803a | 104d:9015 | Texas I... | PCIxx12 OHCI Compliant IE... | 6     | firewir... | 3BEE1DDF68 |
| 1180:0832 | 1028:024d | Ricoh      | R5C832 IEEE 1394 Controller  | 6     | firewir... | 59050A5736 |
| 1180:0832 | 103c:30c5 | Ricoh      | R5C832 IEEE 1394 Controller  | 6     | firewir... | AB3B50FF87 |
| 1180:0832 | 17aa:2109 | Ricoh      | R5C832 IEEE 1394 Controller  | 6     | firewir... | C15AB53D21 |
| 1180:0832 | 17aa:3d94 | Ricoh      | R5C832 IEEE 1394 Controller  | 6     | firewir... | 81D0AC0AA8 |
| 1217:13f7 | 1028:049b | O2 Micro   | 1394 OHCI Compliant Host ... | 6     | firewir... | 26DE378A54 |
| 197b:2380 | 103c:1619 | JMicron... | IEEE 1394 Host Controller    | 6     | firewir... | 6140D0688E |
| 197b:2380 | 103c:7001 | JMicron... | IEEE 1394 Host Controller    | 6     | firewir... | 2D49142FA9 |
| 104c:803a | 1025:011c | Texas I... | PCIxx12 OHCI Compliant IE... | 5     | firewir... | 89E46BA6FF |
| 1180:0551 | 144d:b023 | Ricoh      | R5C551 IEEE 1394 Controller  | 5     | firewir... | 529607257E |
| 1180:0832 | 1028:01f2 | Ricoh      | R5C832 IEEE 1394 Controller  | 5     | firewir... | AEF28A0D3B |
| 1180:0832 | 103c:30c2 | Ricoh      | R5C832 IEEE 1394 Controller  | 5     | firewir... | 1749B0B757 |
| 1180:0832 | 103c:30e7 | Ricoh      | R5C832 IEEE 1394 Controller  | 5     | firewir... | E05FE6B4AB |
| 1180:0832 | 104d:9045 | Ricoh      | R5C832 IEEE 1394 Controller  | 5     | firewir... | BE4CAF88A1 |
| 1180:e832 | 1028:0402 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 5     | firewir... | 9E4109323B |
| 1180:e832 | 103c:146d | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 5     | firewir... | 801F83247C |
| 1180:e832 | 104d:9069 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 5     | firewir... | 94C60C4371 |
| 1217:00f7 | 1028:01fe | O2 Micro   | Firewire (IEEE 1394)         | 5     | firewir... | 7129998723 |
| 1217:11f7 | 1028:04a4 | O2 Micro   | OZ600 1394a-2000 Controller  | 5     | firewir... | 370EF78297 |
| 197b:2380 | 103c:179c | JMicron... | IEEE 1394 Host Controller    | 5     | firewir... | 6008FDBA9D |
| 197b:2380 | 103c:3600 | JMicron... | IEEE 1394 Host Controller    | 5     | firewir... | 3F857E2920 |
| 104c:8023 | 1179:0001 | Texas I... | TSB43AB22A IEEE-1394a-200... | 4     | firewir... | 88852BE56A |
| 104c:8032 | 1179:0001 | Texas I... | OHCI Compliant IEEE 1394 ... | 4     | firewir... | D5D7DAB02F |
| 104c:803a | 104d:8212 | Texas I... | PCIxx12 OHCI Compliant IE... | 4     | firewir... | 8938DD9A9E |
| 104c:803a | 104d:9016 | Texas I... | PCIxx12 OHCI Compliant IE... | 4     | firewir... | C257EC2DD4 |
| 1106:3044 | 1025:009f | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 4     | firewir... | 109CDB17E1 |
| 1180:0832 | 1028:01cd | Ricoh      | R5C832 IEEE 1394 Controller  | 4     | firewir... | 8557CCF8D1 |
| 1180:0832 | 1028:01f1 | Ricoh      | R5C832 IEEE 1394 Controller  | 4     | firewir... | CA83DB613D |
| 1180:0832 | 1028:01f8 | Ricoh      | R5C832 IEEE 1394 Controller  | 4     | firewir... | 8AA0E22374 |
| 1180:0832 | 1028:0209 | Ricoh      | R5C832 IEEE 1394 Controller  | 4     | firewir... | 14AC7530E2 |
| 1180:0832 | 1028:0228 | Ricoh      | R5C832 IEEE 1394 Controller  | 4     | firewir... | 9295D48DD9 |
| 1180:0832 | 1028:0229 | Ricoh      | R5C832 IEEE 1394 Controller  | 4     | firewir... | 557BDF0E0D |
| 1180:0832 | 103c:1520 | Ricoh      | R5C832 IEEE 1394 Controller  | 4     | firewir... | 5BC72880EA |

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
| 1022:1577 | 1022:1577 | AMD        | Family 15h (Models 60h-6f... | 51    |            | C61C9E33F6 |
| 1022:1577 | 103c:8331 | AMD        | Family 15h (Models 60h-6f... | 12    |            | 9111BD09BB |
| 1022:1423 | 1022:1423 | AMD        | Family 15h (Models 30h-3f... | 4     |            | E7C8A22676 |
| 1022:1451 | 1022:1451 | AMD        | Family 17h (Models 00h-0f... | 3     |            | 35BF9EB2EF |
| 1022:1577 | 103c:81fa | AMD        | Family 15h (Models 60h-6f... | 3     |            | BAEB555043 |
| 1022:1423 | 103c:812f | AMD        | Family 15h (Models 30h-3f... | 2     |            | FDB3CCB899 |
| 1022:1577 | 103c:80b5 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 2D0E845055 |
| 1022:1577 | 103c:80b6 | AMD        | Family 15h (Models 60h-6f... | 2     |            | BEA3C73273 |
| 1022:1577 | 103c:8355 | AMD        | Family 15h (Models 60h-6f... | 2     |            | D6F5348EC7 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a011 | 1043:83ac | Intel      | Atom Processor D4xx/D5xx/... | 79    | i915       | B658C90327 |
| 8086:a012 | 1043:83ac | Intel      | Atom Processor D4xx/D5xx/... | 79    |            | B658C90327 |
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 67    | i915       | 4414412FCB |
| 8086:0166 | 1025:0647 | Intel      | 3rd Gen Core processor Gr... | 63    | i915       | 6478022B75 |
| 8086:0106 | 1025:0649 | Intel      | 2nd Generation Core Proce... | 55    | i915       | F28D18F3E9 |
| 8086:0f31 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 52    | i915       | CC7193A7B9 |
| 8086:0046 | 17aa:215a | Intel      | Core Processor Integrated... | 51    | i915       | DA5E944C6C |
| 8086:2a02 | 1025:011f | Intel      | Mobile GM965/GL960 Integr... | 51    | i915       | 7387D70AD5 |
| 8086:2a03 | 1025:011f | Intel      | Mobile GM965/GL960 Integr... | 51    |            | 7387D70AD5 |
| 8086:a011 | 1025:0349 | Intel      | Atom Processor D4xx/D5xx/... | 51    | i915       | 8CE41DB531 |
| 8086:a012 | 1025:0349 | Intel      | Atom Processor D4xx/D5xx/... | 51    |            | 8CE41DB531 |
| 8086:0166 | 17aa:5003 | Intel      | 3rd Gen Core processor Gr... | 50    | i915       | CE3DDF28FC |
| 8086:2a42 | 17aa:3a02 | Intel      | Mobile 4 Series Chipset I... | 49    | i915       | 601D53F9EB |
| 8086:2a43 | 17aa:3a02 | Intel      | Mobile 4 Series Chipset I... | 49    |            | 601D53F9EB |
| 8086:0156 | 17aa:3977 | Intel      | 3rd Gen Core processor Gr... | 48    | i915       | 4FAA6112C3 |
| 8086:2a42 | 1043:1862 | Intel      | Mobile 4 Series Chipset I... | 48    | i915       | 38190AD2E1 |
| 8086:2a43 | 1043:1862 | Intel      | Mobile 4 Series Chipset I... | 48    |            | 38190AD2E1 |
| 8086:2a42 | 17aa:20e4 | Intel      | Mobile 4 Series Chipset I... | 47    | i915       | FDAB3CF92F |
| 8086:2a43 | 17aa:20e4 | Intel      | Mobile 4 Series Chipset I... | 47    |            | FDAB3CF92F |
| 8086:0116 | 1025:0504 | Intel      | 2nd Generation Core Proce... | 45    | i915       | 8579BA1B16 |
| 8086:0166 | 17aa:3977 | Intel      | 3rd Gen Core processor Gr... | 44    | i915       | B19B3500F2 |
| 8086:0166 | 1043:124d | Intel      | 3rd Gen Core processor Gr... | 42    | i915       | 0F8CE4DCC0 |
| 8086:0be1 | 1043:84a9 | Intel      | Atom Processor D2xxx/N2xx... | 42    | gma500_gfx | 6A0513EC8D |
| 8086:0166 | 1025:064b | Intel      | 3rd Gen Core processor Gr... | 40    | i915       | E67DFC255A |
| 8086:0f31 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 40    | i915       | 0994A3EEB3 |
| 8086:0106 | 17aa:3975 | Intel      | 2nd Generation Core Proce... | 39    | i915       | 05D969D697 |
| 1002:68e4 | 17aa:397a | AMD        | Robson CE [Radeon HD 6370... | 38    | radeon     | A7618091FB |
| 8086:0116 | 1043:1682 | Intel      | 2nd Generation Core Proce... | 36    | i915       | FB3C3B769A |
| 8086:0156 | 17aa:5011 | Intel      | 3rd Gen Core processor Gr... | 34    | i915       | 65D329A2C6 |
| 8086:2a02 | 17aa:20b5 | Intel      | Mobile GM965/GL960 Integr... | 34    | i915       | 037CAC7A3D |
| 8086:2a03 | 17aa:20b5 | Intel      | Mobile GM965/GL960 Integr... | 34    |            | 037CAC7A3D |
| 1002:5a62 | 1043:1402 | AMD        | RC410M [Mobility Radeon X... | 33    | radeon     | 54C92BF69C |
| 10de:0df5 | 1028:04ca | Nvidia     | GF108M [GeForce GT 525M]     | 33    | nouveau    | C0868A2B0C |
| 8086:0f31 | 17aa:3909 | Intel      | Atom Processor Z36xxx/Z37... | 33    | i915       | EE1CFF7014 |
| 1002:68e0 | 1043:1bf2 | AMD        | Park [Mobility Radeon HD ... | 32    | radeon     | 13D9E84E8D |
| 8086:0a16 | 1025:0866 | Intel      | Haswell-ULT Integrated Gr... | 32    | i915       | 1C77D7A584 |
| 10de:1051 | 144d:c0b6 | Nvidia     | GF119M [GeForce GT 520MX]    | 31    | nouveau    | 616616B60F |
| 10de:1140 | 1025:0691 | Nvidia     | GF117M [GeForce 610M/710M... | 31    | nouveau    | E67DFC255A |
| 1002:6840 | 144d:c0da | AMD        | Thames [Radeon HD 7500M/7... | 30    | radeon     | A06125BD54 |
| 8086:0116 | 144d:c0b6 | Intel      | 2nd Generation Core Proce... | 30    | i915       | 616616B60F |
| 8086:0116 | 1043:1652 | Intel      | 2nd Generation Core Proce... | 29    | i915       | 6B25B8982D |
| 8086:0f31 | 1043:14dd | Intel      | Atom Processor Z36xxx/Z37... | 29    | i915       | 8D51E5FEC5 |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics                  | 29    | i915       | 1579402536 |
| 8086:a011 | 1025:0590 | Intel      | Atom Processor D4xx/D5xx/... | 29    | i915       | D5A624C8FE |
| 8086:a011 | 144d:c072 | Intel      | Atom Processor D4xx/D5xx/... | 29    | i915       | 3A0FEA4700 |
| 8086:a012 | 1025:0590 | Intel      | Atom Processor D4xx/D5xx/... | 29    |            | D5A624C8FE |
| 8086:a012 | 144d:c072 | Intel      | Atom Processor D4xx/D5xx/... | 29    |            | 3A0FEA4700 |
| 10de:1051 | 144d:c606 | Nvidia     | GF119M [GeForce GT 520MX]    | 28    | nouveau    | 0BFEB87324 |
| 10de:1058 | 1043:1652 | Nvidia     | GF119M [GeForce 610M]        | 28    | nouveau    | 6B25B8982D |
| 8086:0116 | 1028:04ca | Intel      | 2nd Generation Core Proce... | 28    | i915       | 5137B5B274 |
| 1002:6840 | 103c:184a | AMD        | Thames [Radeon HD 7500M/7... | 27    | radeon     | 0D67044A36 |
| 1002:98e4 | 103c:8330 | AMD        | Stoney [Radeon R2/R3/R4/R... | 27    | amdgpu     | D32B7275C3 |
| 8086:0046 | 1025:0488 | Intel      | Core Processor Integrated... | 27    | i915       | 8CD4AF2E88 |
| 8086:0126 | 17aa:21ce | Intel      | 2nd Generation Core Proce... | 27    | i915       | FBF8462F41 |
| 8086:22b1 | 1025:1012 | Intel      | Atom/Celeron/Pentium Proc... | 27    | i915       | 5A7F96289D |
| 8086:0106 | 17aa:3977 | Intel      | 2nd Generation Core Proce... | 26    | i915       | ECF9D3F57B |
| 8086:0166 | 17aa:21f3 | Intel      | 3rd Gen Core processor Gr... | 26    | i915       | 6D5F1234C2 |
| 8086:0166 | 17aa:3901 | Intel      | 3rd Gen Core processor Gr... | 26    | i915       | F3D7E4E13D |
| 8086:0f31 | 1297:2041 | Intel      | Atom Processor Z36xxx/Z37... | 26    | i915       | 100EB984CA |
| 8086:2a42 | 1025:0212 | Intel      | Mobile 4 Series Chipset I... | 26    | i915       | 6029A4A18A |
| 8086:2a43 | 1025:0212 | Intel      | Mobile 4 Series Chipset I... | 26    |            | 6029A4A18A |
| 8086:0116 | 144d:c606 | Intel      | 2nd Generation Core Proce... | 25    | i915       | EE56C112BB |
| 8086:0166 | 1025:0686 | Intel      | 3rd Gen Core processor Gr... | 25    | i915       | 29CFE1AD23 |
| 8086:0166 | 1043:1587 | Intel      | 3rd Gen Core processor Gr... | 25    | i915       | 469E04E0D5 |
| 8086:0166 | 17aa:21fa | Intel      | 3rd Gen Core processor Gr... | 25    | i915       | DB9250D9E0 |
| 8086:0a16 | 17aa:3978 | Intel      | Haswell-ULT Integrated Gr... | 25    | i915       | 23BD541BF1 |
| 1002:68e4 | 1043:1c92 | AMD        | Robson CE [Radeon HD 6370... | 24    | radeon     | 52035C5F01 |
| 8086:0046 | 17aa:3920 | Intel      | Core Processor Integrated... | 24    | i915       | 4BF2811044 |
| 8086:0166 | 144d:c0d8 | Intel      | 3rd Gen Core processor Gr... | 24    | i915       | 0F042024B4 |
| 8086:0a16 | 1043:16cd | Intel      | Haswell-ULT Integrated Gr... | 24    | i915       | FDD61F096B |
| 8086:0f31 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 24    | i915       | CEAC334581 |
| 8086:2a42 | 144d:c06d | Intel      | Mobile 4 Series Chipset I... | 24    | i915       | E027071CC1 |
| 8086:2a43 | 144d:c06d | Intel      | Mobile 4 Series Chipset I... | 24    |            | E027071CC1 |
| 1002:6840 | 144d:c0d8 | AMD        | Thames [Radeon HD 7500M/7... | 23    | radeon     | 0F042024B4 |
| 10de:1140 | 17aa:5003 | Nvidia     | GF117M [GeForce 610M/710M... | 23    | nouveau    | CE3DDF28FC |
| 8086:0126 | 1028:0493 | Intel      | 2nd Generation Core Proce... | 23    | i915       | CA6EFEBBD7 |
| 8086:27a2 | 103c:30a2 | Intel      | Mobile 945GM/GMS, 943/940... | 23    | i915       | 531D26CDD8 |
| 8086:27a6 | 103c:30a2 | Intel      | Mobile 945GM/GMS/GME, 943... | 23    |            | 531D26CDD8 |
| 8086:2a02 | 1025:0136 | Intel      | Mobile GM965/GL960 Integr... | 23    | i915       | 1EF9D813A6 |
| 8086:2a03 | 1025:0136 | Intel      | Mobile GM965/GL960 Integr... | 23    |            | 1EF9D813A6 |
| 1002:718a | 1043:1449 | AMD        | RV516/M64 [Mobility Radeo... | 22    | radeon     | F8B36F76B8 |
| 1002:98e4 | 1025:1192 | AMD        | Stoney [Radeon R2/R3/R4/R... | 22    | amdgpu     | 0D71E52A34 |
| 10de:0a70 | 17aa:3966 | Nvidia     | GT218M [GeForce 310M]        | 22    | nouveau    | 17BE920F30 |
| 10de:0df4 | 1043:15f2 | Nvidia     | GF108M [GeForce GT 540M]     | 22    | nouveau    | 4A4D727652 |
| 10de:1058 | 17aa:5003 | Nvidia     | GF119M [GeForce 610M]        | 22    | nouveau    | 4E9B15C5D8 |
| 10de:1140 | 1043:223a | Nvidia     | GF117M [GeForce 610M/710M... | 22    | nouveau    | F7D67A61C1 |
| 8086:0046 | 17aa:3957 | Intel      | Core Processor Integrated... | 22    | i915       | 17BE920F30 |
| 8086:0f31 | 103c:2213 | Intel      | Atom Processor Z36xxx/Z37... | 22    | i915       | 964E06B446 |
| 8086:0f31 | 1043:161d | Intel      | Atom Processor Z36xxx/Z37... | 22    | i915       | BDFF3A60F1 |
| 8086:22b1 | 1043:10c0 | Intel      | Atom/Celeron/Pentium Proc... | 22    | i915       | F8FDA4EFC3 |
| 8086:5a85 | 1043:16a0 | Intel      | HD Graphics                  | 22    | i915       | 0FAD7AC4EB |
| 1002:9900 | 144d:c0da | AMD        | Trinity [Radeon HD 7660G]    | 21    | radeon     | A06125BD54 |
| 10de:0fdf | 1043:1587 | Nvidia     | GK107M [GeForce GT 740M]     | 21    | nouveau    | 31252AFE6F |
| 10de:1051 | 1043:1762 | Nvidia     | GF119M [GeForce GT 520MX]    | 21    | nouveau    | FB3C3B769A |
| 8086:0166 | 17aa:3800 | Intel      | 3rd Gen Core processor Gr... | 21    | i915       | 4FC85D1C31 |
| 8086:0416 | 17aa:3801 | Intel      | 4th Gen Core Processor In... | 21    | i915       | 6ADE50F197 |
| 8086:0416 | 17aa:3978 | Intel      | 4th Gen Core Processor In... | 21    | i915       | 262BB6B100 |
| 8086:2a02 | 1028:01f9 | Intel      | Mobile GM965/GL960 Integr... | 21    | i915       | C331358BBE |
| 8086:2a02 | 1028:022f | Intel      | Mobile GM965/GL960 Integr... | 21    | i915       | 55CD396670 |
| 8086:2a03 | 1028:01f9 | Intel      | Mobile GM965/GL960 Integr... | 21    |            | C331358BBE |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 39    |            | 123447177A |
| 1022:1577 | 103c:8330 | AMD        | Family 15h (Models 60h-6f... | 27    |            | D32B7275C3 |
| 1022:1577 | 1025:1192 | AMD        | Family 15h (Models 60h-6f... | 22    |            | 0D71E52A34 |
| 1022:15d1 | 103c:84ae | AMD        | Raven/Raven2 IOMMU           | 14    |            | E8755C7EF8 |
| 1022:15d1 | 17aa:3804 | AMD        | Raven/Raven2 IOMMU           | 9     |            | F6996F43AE |
| 1022:1577 | 103c:84ac | AMD        | Family 15h (Models 60h-6f... | 8     |            | 44E78B4D3F |
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
| 1022:15d1 | 17aa:3809 | AMD        | Raven/Raven2 IOMMU           | 3     |            | 102D5EFAD5 |
| 1022:1577 | 1025:1099 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 326E32CFB9 |
| 1022:1577 | 1025:1201 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 1D59285089 |
| 1022:1577 | 1028:0769 | AMD        | Family 15h (Models 60h-6f... | 2     |            | AA9862538A |
| 1022:1577 | 1028:076b | AMD        | Family 15h (Models 60h-6f... | 2     |            | C9DF0EF9CD |
| 1022:1577 | 103c:80b0 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 3F7F72D7A2 |
| 1022:1577 | 103c:8324 | AMD        | Family 15h (Models 60h-6f... | 2     |            | FEEB8EA6F8 |
| 1022:1577 | 103c:8333 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 1C1D0D6198 |
| 1022:1577 | 103c:84a0 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 908E49B930 |
| 1022:1577 | 103c:84d0 | AMD        | Family 15h (Models 60h-6f... | 2     |            | C77FA19C2B |
| 1022:1577 | 103c:84d1 | AMD        | Family 15h (Models 60h-6f... | 2     |            | E3FF835EA0 |
| 1022:15d1 | 1025:1233 | AMD        | Raven/Raven2 IOMMU           | 2     |            | 856A212CAA |
| 1022:1423 | 103c:2263 | AMD        | Family 15h (Models 30h-3f... | 1     |            | A07F8E8315 |
| 1022:1423 | 103c:22a9 | AMD        | Family 15h (Models 30h-3f... | 1     |            | FE059A167E |
| 1022:1577 | 1025:1087 | AMD        | Family 15h (Models 60h-6f... | 1     |            | 9A0D26C5FB |
| 1022:1577 | 1025:1372 | AMD        | Family 15h (Models 60h-6f... | 1     |            | F7313E11F8 |
| 1022:1577 | 103c:80af | AMD        | Family 15h (Models 60h-6f... | 1     |            | 6186029A96 |
| 1022:1577 | 103c:81fd | AMD        | Family 15h (Models 60h-6f... | 1     |            | 7C0F244462 |
| 1022:1577 | 103c:8346 | AMD        | Family 15h (Models 60h-6f... | 1     |            | B53E43FC3C |
| 1022:1577 | 103c:8353 | AMD        | Family 15h (Models 60h-6f... | 1     |            | BB4FD376C4 |
| 1022:1577 | 103c:8354 | AMD        | Family 15h (Models 60h-6f... | 1     |            | C75D45BEC4 |
| 1022:1577 | 103c:8357 | AMD        | Family 15h (Models 60h-6f... | 1     |            | F017BDEDF1 |
| 1022:1577 | 103c:84ad | AMD        | Family 15h (Models 60h-6f... | 1     |            | CB1771B144 |
| 1022:1577 | 103c:84e5 | AMD        | Family 15h (Models 60h-6f... | 1     |            | B92FF40DA0 |
| 1022:1577 | 103c:85bb | AMD        | Family 15h (Models 60h-6f... | 1     |            | A6C908654C |
| 1022:15d1 | 1028:08d7 | AMD        | Raven/Raven2 IOMMU           | 1     |            | ADFAD3DD99 |
| 1022:15d1 | 103c:85b3 | AMD        | Raven/Raven2 IOMMU           | 1     |            | 766B0474A3 |
| 1022:15d1 | 103c:8615 | AMD        | Raven/Raven2 IOMMU           | 1     |            | 048229855F |
| 1022:15d1 | 17aa:3802 | AMD        | Raven/Raven2 IOMMU           | 1     |            | 878BBF3E54 |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816c | 103c:83da | Realtek... | Virtual IPMI                 | 1     |            | 607DEE6BBB |
| 10ec:816c | 103c:8401 | Realtek... | Virtual IPMI                 | 1     |            | F2F88AAA9D |
| 10ec:816c | 17aa:511f | Realtek... | Virtual IPMI                 | 1     |            | 259A32BE33 |
| 10ec:816c | 17aa:5122 | Realtek... | Virtual IPMI                 | 1     |            | 7CCAC31D71 |
| 10ec:816c | 17aa:5125 | Realtek... | Virtual IPMI                 | 1     |            | 7A1C4A299D |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a36f | 8086:7270 | Intel      | Cannon Lake PCH Shared SRAM  | 55    |            | 3DF62034D2 |
| 10de:0a88 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 36    |            | C4A5E49D47 |
| 10de:0a89 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 36    |            | C4A5E49D47 |
| 10de:0a88 |           | Nvidia     | MCP79 Memory Controller      | 31    |            | 9F753AC669 |
| 8086:9d21 | 1025:1193 | Intel      | Sunrise Point-LP PMC         | 26    | intel_p... | 141D7917FF |
| 10de:0a89 |           | Nvidia     | MCP79 Memory Controller      | 24    |            | 9F753AC669 |
| 10de:0aa4 |           | Nvidia     | MCP79 Memory Controller      | 24    |            | 9F753AC669 |
| 8086:9d21 | 1025:1085 | Intel      | Sunrise Point-LP PMC         | 23    | intel_p... | AE1CE65D11 |
| 10de:0a98 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 21    |            | 9F753AC669 |
| 8086:9d21 | 1025:115f | Intel      | Sunrise Point-LP PMC         | 21    | intel_p... | E4B342382F |
| 8086:9d21 | 17aa:3816 | Intel      | Sunrise Point-LP PMC         | 20    |            | 005771EDFD |
| 10de:0541 | 10de:cb84 | Nvidia     | MCP67 Memory Controller      | 19    |            | F7695ADD11 |
| 10de:0aa4 | 1043:1cf7 | Nvidia     | MCP79 Memory Controller      | 18    |            | F0A1399A3F |
| 8086:9d21 | 103c:832a | Intel      | Sunrise Point-LP PMC         | 18    |            | 8B699D7E6C |
| 10de:0547 | 1025:0126 | Nvidia     | MCP67 Memory Controller      | 17    |            | F7695ADD11 |
| 8086:9d21 | 1043:1a00 | Intel      | Sunrise Point-LP PMC         | 17    | intel_p... | BEB89C26D9 |
| 8086:9d21 | 17aa:3872 | Intel      | Sunrise Point-LP PMC         | 17    |            | 240FE2C985 |
| 8086:444e | 8086:444e | Intel      | Turbo Memory Controller      | 16    |            | 253B1DAE47 |
| 8086:9d21 | 8086:7270 | Intel      | Sunrise Point-LP PMC         | 16    |            | 8EB32C768B |
| 8086:a121 | 17aa:3802 | Intel      | 100 Series/C230 Series Ch... | 16    |            | 9A9BC31C3D |
| 10de:0568 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] Mem... | 15    |            | 265A212FDC |
| 10de:0754 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] Mem... | 15    |            | 265A212FDC |
| 8086:9d21 | 103c:8079 | Intel      | Sunrise Point-LP PMC         | 15    |            | B8392B7335 |
| 8086:9d21 | 1028:07e6 | Intel      | Sunrise Point-LP PMC         | 14    | intel_p... | 5D2CB1E1B0 |
| 10de:0aa4 | 1043:1fa7 | Nvidia     | MCP79 Memory Controller      | 13    |            | C4A5E49D47 |
| 8086:9d21 | 8086:9d21 | Intel      | Sunrise Point-LP PMC         | 13    |            | 6813C9B2D3 |
| 8086:9def | 8086:7270 | Intel      | Cannon Point-LP Shared SRAM  | 13    |            | EA12327BDD |
| 8086:a121 | 1028:07be | Intel      | 100 Series/C230 Series Ch... | 13    |            | CB9F8EC46D |
| 10de:0d68 |           | Nvidia     | MCP89 Memory Controller      | 12    |            | 80ECBDE76E |
| 10de:0d69 |           | Nvidia     | MCP89 Memory Controller      | 12    |            | 80ECBDE76E |
| 10de:0d6d |           | Nvidia     | MCP89 Memory Controller      | 12    |            | 80ECBDE76E |
| 10de:0d6e |           | Nvidia     | MCP89 Memory Controller      | 12    |            | 80ECBDE76E |
| 10de:0d6f |           | Nvidia     | MCP89 Memory Controller      | 12    |            | 80ECBDE76E |
| 10de:0d70 |           | Nvidia     | MCP89 Memory Controller      | 12    |            | 80ECBDE76E |
| 10de:0d71 |           | Nvidia     | MCP89 Memory Controller      | 12    |            | 80ECBDE76E |
| 10de:0d72 |           | Nvidia     | MCP89 Memory Controller      | 12    |            | 80ECBDE76E |
| 10de:0d75 |           | Nvidia     | MCP89 Memory Controller      | 12    |            | 80ECBDE76E |
| 10de:0d7b |           | Nvidia     | MCP89 Memory Controller      | 12    |            | 80ECBDE76E |
| 8086:9d21 | 103c:84a6 | Intel      | Sunrise Point-LP PMC         | 12    | intel_p... | 1A3504B63C |
| 8086:a36f | 1028:087c | Intel      | Cannon Lake PCH Shared SRAM  | 12    |            | 7A9639F003 |
| 8086:9d21 | 1028:083f | Intel      | Sunrise Point-LP PMC         | 11    |            | A38D1A4CE9 |
| 8086:9d21 | 17aa:3808 | Intel      | Sunrise Point-LP PMC         | 11    |            | 37E18B856C |
| 8086:9d21 | 17aa:3845 | Intel      | Sunrise Point-LP PMC         | 11    |            | 31400D27D2 |
| 8086:a121 | 1028:0706 | Intel      | 100 Series/C230 Series Ch... | 11    |            | 9104464264 |
| 10de:027e |           | Nvidia     | C51 Memory Controller 2      | 10    |            | 4A6A073320 |
| 8086:9d21 | 1025:121e | Intel      | Sunrise Point-LP PMC         | 10    | intel_p... | 951A7053B0 |
| 8086:9d21 | 1028:0704 | Intel      | Sunrise Point-LP PMC         | 10    | intel_p... | 159AB17857 |
| 8086:9d21 | 17aa:3844 | Intel      | Sunrise Point-LP PMC         | 10    |            | 3FFC2E920B |
| 8086:9d21 | 17aa:3851 | Intel      | Sunrise Point-LP PMC         | 10    |            | 298E510C05 |
| 8086:9d21 | 17aa:5068 | Intel      | Sunrise Point-LP PMC         | 10    |            | CE2A6FB934 |
| 8086:9d21 | 1d72:1701 | Intel      | Sunrise Point-LP PMC         | 10    | intel_p... | A159026F22 |
| 8086:a36f | 1025:1264 | Intel      | Cannon Lake PCH Shared SRAM  | 10    |            | F3941C8871 |
| 10de:0547 | 103c:30cf | Nvidia     | MCP67 Memory Controller      | 9     |            | 1184F5572B |
| 10de:0a88 | 1043:8402 | Nvidia     | MCP79 Memory Controller      | 9     |            | 353AB385C9 |
| 10de:0a89 | 1043:8402 | Nvidia     | MCP79 Memory Controller      | 9     |            | 353AB385C9 |
| 10de:0aa4 | 1043:8402 | Nvidia     | MCP79 Memory Controller      | 9     |            | 353AB385C9 |
| 8086:9d21 | 1025:100c | Intel      | Sunrise Point-LP PMC         | 9     |            | AB58C20DE3 |
| 8086:9d21 | 1028:06b2 | Intel      | Sunrise Point-LP PMC         | 9     |            | 4CBF20A7CF |
| 8086:9d21 | 103c:8101 | Intel      | Sunrise Point-LP PMC         | 9     |            | B9E21A89DA |
| 8086:9d21 | 103c:832b | Intel      | Sunrise Point-LP PMC         | 9     |            | ED8AF41B6E |
| 8086:9d21 | 1043:1d30 | Intel      | Sunrise Point-LP PMC         | 9     | intel_p... | AC46496374 |
| 8086:9d21 | 17aa:225d | Intel      | Sunrise Point-LP PMC         | 9     |            | CA4D5C11F7 |
| 8086:a121 | 1028:0798 | Intel      | 100 Series/C230 Series Ch... | 9     |            | D12ECD3663 |
| 8086:a121 | 1462:11c8 | Intel      | 100 Series/C230 Series Ch... | 9     |            | D0C54EF6E4 |
| 8086:a36f | 1028:087d | Intel      | Cannon Lake PCH Shared SRAM  | 9     |            | 75F82151FF |
| 8086:9d21 | 1028:0767 | Intel      | Sunrise Point-LP PMC         | 8     |            | 8090C8CC68 |
| 8086:9d21 | 1028:0810 | Intel      | Sunrise Point-LP PMC         | 8     |            | EB05A1DBC4 |
| 8086:9d21 | 1028:082a | Intel      | Sunrise Point-LP PMC         | 8     | intel_p... | 174CC02B16 |
| 8086:9d21 | 103c:8328 | Intel      | Sunrise Point-LP PMC         | 8     |            | 7D8551E612 |
| 8086:9d21 | 103c:837d | Intel      | Sunrise Point-LP PMC         | 8     | intel_p... | 9B82C44F0C |
| 8086:9d21 | 17aa:2245 | Intel      | Sunrise Point-LP PMC         | 8     | intel_p... | 0F9287651D |
| 8086:9d21 | 19e5:3e04 | Intel      | Sunrise Point-LP PMC         | 8     |            | 5F7A70586E |
| 8086:9def | 1028:08af | Intel      | Cannon Point-LP Shared SRAM  | 8     |            | D4A2D02674 |
| 8086:a121 | 1025:118a | Intel      | 100 Series/C230 Series Ch... | 8     |            | C80CAABFC9 |
| 8086:a121 | 1043:15e0 | Intel      | 100 Series/C230 Series Ch... | 8     |            | 1A816E6EBB |
| 8086:9d21 | 1025:1094 | Intel      | Sunrise Point-LP PMC         | 7     |            | 64BD62C7EA |
| 8086:9d21 | 1028:070a | Intel      | Sunrise Point-LP PMC         | 7     |            | 39C3F65CF9 |
| 8086:9d21 | 1028:075b | Intel      | Sunrise Point-LP PMC         | 7     |            | 3A71C37AE2 |
| 8086:9d21 | 1028:078b | Intel      | Sunrise Point-LP PMC         | 7     |            | 71A5A103B0 |
| 8086:9d21 | 103c:81ec | Intel      | Sunrise Point-LP PMC         | 7     | intel_p... | 84C148AE92 |
| 8086:9d21 | 1043:10e1 | Intel      | Sunrise Point-LP PMC         | 7     | intel_p... | BE9E8FF107 |
| 8086:9d21 | 1043:1670 | Intel      | Sunrise Point-LP PMC         | 7     | intel_p... | BAF89919E7 |
| 8086:9d21 | 1043:1b1d | Intel      | Sunrise Point-LP PMC         | 7     |            | 30A8F9D279 |
| 8086:9d21 | 17aa:2233 | Intel      | Sunrise Point-LP PMC         | 7     |            | 78932B3C9B |
| 8086:9d21 | 17aa:225a | Intel      | Sunrise Point-LP PMC         | 7     | intel_p... | D24D45BE87 |
| 8086:9d21 | 17aa:3806 | Intel      | Sunrise Point-LP PMC         | 7     |            | BD7312440F |
| 8086:9d21 | 17aa:3815 | Intel      | Sunrise Point-LP PMC         | 7     |            | ED62F572C5 |
| 8086:a121 | 1558:850a | Intel      | 100 Series/C230 Series Ch... | 7     |            | 4F92CFF461 |
| 10de:0270 | 103c:30b7 | Nvidia     | MCP51 Host Bridge            | 6     |            | B699788F33 |
| 10de:027f | 103c:30b7 | Nvidia     | C51 Memory Controller 3      | 6     |            | B699788F33 |
| 10de:02f0 | 103c:30b7 | Nvidia     | C51 Host Bridge              | 6     |            | B699788F33 |
| 10de:02f8 | 103c:30b7 | Nvidia     | C51 Memory Controller 5      | 6     |            | B699788F33 |
| 10de:02f9 | 103c:30b7 | Nvidia     | C51 Memory Controller 4      | 6     |            | B699788F33 |
| 10de:02fa | 103c:30b7 | Nvidia     | C51 Memory Controller 0      | 6     |            | B699788F33 |
| 10de:02fe | 103c:30b7 | Nvidia     | C51 Memory Controller 1      | 6     |            | B699788F33 |
| 10de:02ff | 103c:30b7 | Nvidia     | C51 Host Bridge              | 6     |            | B699788F33 |
| 10de:0541 | 103c:30cf | Nvidia     | MCP67 Memory Controller      | 6     |            | 1184F5572B |
| 8086:9d21 | 1025:1134 | Intel      | Sunrise Point-LP PMC         | 6     | intel_p... | BEF9865EC7 |
| 8086:9d21 | 1025:1269 | Intel      | Sunrise Point-LP PMC         | 6     |            | 060D0346D8 |
| 8086:9d21 | 1028:06dc | Intel      | Sunrise Point-LP PMC         | 6     |            | 90E9F8DFAD |

### Modem (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:266d | 14f1:5423 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 10    | snd_int... | 23F9D951DE |
| 8086:24c6 | 14f1:5422 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 8     | snd_int... | 0504CC20A9 |
| 8086:266d | 1179:0001 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 8     | snd_int... | D5D7DAB02F |
| 8086:266d | 103c:099c | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 6     | snd_int... | E0DF895DC8 |
| 8086:266d | 1025:006a | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 5     | snd_int... | F47019C8BA |
| 8086:266d | 1014:0574 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 4     | snd_int... | 4916E9EC9C |
| 8086:266d | 1025:0066 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 4     | snd_int... | E814DA247A |
| 1002:434d | 144d:2115 | AMD        | SB200 AC97 Modem Controller  | 3     | snd_ati... | 80073ED5E9 |
| 1002:4378 | 1043:1186 | AMD        | IXP SB400 AC'97 Modem Con... | 3     | snd_ati... | 08E7796666 |
| 1039:7013 | 1043:1816 | Silicon... | AC'97 Modem Controller       | 3     | snd_int... | C4EBB5D061 |
| 8086:24c6 | 1014:055a | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 3     | snd_int... | A538D3F64D |
| 8086:266d | 103c:309d | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 3     | snd_int... | 837230178B |
| 8086:266d | 144d:2115 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 3     | snd_int... | 88BAF3B388 |
| 1002:4378 | 103c:3091 | AMD        | IXP SB400 AC'97 Modem Con... | 2     | snd_ati... | 30D7D605F7 |
| 1002:4378 | 103c:30a4 | AMD        | IXP SB400 AC'97 Modem Con... | 2     | snd_ati... | 817D97FE5A |
| 1002:4378 | 1734:1092 | AMD        | IXP SB400 AC'97 Modem Con... | 2     | snd_ati... | 4D0D913872 |
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
| 1039:7013 | 104d:814e | Silicon... | AC'97 Modem Controller       | 1     | snd_int... | 88ABDEBE09 |
| 10b9:5457 | 103c:0850 | ULi Ele... | M5457 AC'97 Modem Controller | 1     |            | 4E9D284D9C |
| 10de:00d9 | 1043:1856 | Nvidia     | nForce3 Audio                | 1     | snd_int... | 655ACF5FA6 |
| 1106:3068 | 1071:8666 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 179169EE59 |
| 1106:3068 | 1071:8889 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | E801E7B52C |
| 1106:3068 | 1734:10ae | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 06ECBD156A |
| 11c1:045c | 8086:2205 | LSI        | LT WinModem                  | 1     | serial     | 1B54E25E77 |
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

### Multimedia (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0f38 |           | Intel      | Atom Processor Z36xxx/Z37... | 1     |            | C4198C729C |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 66    | intel_a... | 4414412FCB |
| 14e4:1570 | 14e4:1570 | Broadco... | 720p FaceTime HD Camera      | 22    | bdc_pci    | B57A70D35E |
| 1022:15e2 | 103c:84ae | AMD        | Raven/Raven2/FireFlight/R... | 14    | snd_pci... | E8755C7EF8 |
| 8086:5a88 |           | Intel      | Celeron N3350/Pentium N42... | 10    |            | F92E526676 |
| 1022:15e2 | 1022:15e2 | AMD        | Raven/Raven2/FireFlight/R... | 6     | snd_pci... | 048229855F |
| 8086:0f38 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 6     | intel_a... | 0994A3EEB3 |
| 1022:15e2 | 103c:84d2 | AMD        | Raven/Raven2/FireFlight/R... | 5     |            | DEFB86D43A |
| 8086:22b8 | 1297:2063 | Intel      | Atom/Celeron/Pentium Proc... | 5     | intel_a... | 2D91F64A77 |
| 14e4:1615 | 14e4:1615 | Broadco... | BCM70015 Video Decoder [C... | 4     |            | E6CF3D7F11 |
| 8086:0f38 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 4     | atomisp    | CEAC334581 |
| 1022:15e2 | 103c:85ea | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | D7977A3B0E |
| 1022:15e2 | 17aa:380b | AMD        | Raven/Raven2/FireFlight/R... | 3     |            | 102D5EFAD5 |
| 8086:22b8 | 103c:813e | Intel      | Atom/Celeron/Pentium Proc... | 3     |            | F91E0FBE6B |
| 1022:15e2 | 1025:1233 | AMD        | Raven/Raven2/FireFlight/R... | 2     |            | 856A212CAA |
| 1131:7160 | 1461:0555 | Philips... | SAA7160                      | 2     |            | D400943350 |
| 1131:7160 | 1461:0a55 | Philips... | SAA7160                      | 2     |            | 99DDBBF195 |
| 1131:7231 | 12ab:0762 | Philips... | SAA7231                      | 2     |            | A72F1BCDE6 |
| 1131:7231 | 1461:0b0f | Philips... | SAA7231                      | 2     |            | 791CA50070 |
| 14e4:1612 | 14e4:2612 | Broadcom   | BCM70012 Video Decoder [C... | 2     |            | 3CBFF8D8F5 |
| 8086:1919 | 8086:1919 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     |            | 707E0DB074 |
| 8086:1919 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     |            | 00259367C8 |
| 8086:22b8 | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 2     | intel_a... | 1A0E086EF8 |
| 8086:9d32 | 8086:9d32 | Intel      | Skylake-U/Y Camera IO Hos... | 2     | ipu3_cio2  | 707E0DB074 |
| 1022:15e2 | 103c:85b3 | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | 766B0474A3 |
| 1022:15e2 | 17aa:3811 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | 878BBF3E54 |
| 1022:15e2 | 17aa:5124 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | 79E53D2DB5 |
| 1022:15e2 | 17aa:5125 | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | 7A1C4A299D |
| 1022:15e2 | 19e5:3e06 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | 2CDCEA8607 |
| 10cf:202a | 104d:81fa | Fujitsu... | Integrated MPEG Encoder      | 1     |            | 7F0BB0CC92 |
| 1131:7160 | 1461:1055 | Philips... | SAA7160                      | 1     |            | 9E921922BA |
| 1131:7160 | 1461:2355 | Philips... | SAA7160                      | 1     |            | B98B8362E0 |
| 1131:7160 | 16be:0034 | Philips... | SAA7160                      | 1     |            | 2B8D93B7EC |
| 1131:7231 | 1461:110f | Philips... | SAA7231                      | 1     |            | 90DFBFB6FA |
| 1131:7231 | 1461:3301 | Philips... | SAA7231                      | 1     |            | 7E1176A7C2 |
| 8086:1919 | 17aa:2241 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     |            | 1038A34C39 |
| 8086:1919 | 17aa:3812 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     |            | 57EC66B289 |
| 8086:22b8 | 1025:1021 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 663247803F |
| 8086:22b8 | 1025:106e | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 425D589D65 |
| 8086:22b8 | 1028:06ea | Intel      | Atom/Celeron/Pentium Proc... | 1     | intel_a... | 721C1A7DC3 |
| 8086:22b8 | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | C508886F10 |
| 8086:22b8 | 1043:1bdd | Intel      | Atom/Celeron/Pentium Proc... | 1     | intel_a... | E3400F39DF |
| 8086:22b8 | 1071:a126 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | F2981C1775 |
| 8086:9d32 | 17aa:2241 | Intel      | Skylake-U/Y Camera IO Hos... | 1     | ipu3_cio2  | 1038A34C39 |
| 8086:9d32 | 17aa:3812 | Intel      | Skylake-U/Y Camera IO Hos... | 1     | ipu3_cio2  | 57EC66B289 |
| 8086:9d32 | 8086:7270 | Intel      | Skylake-U/Y Camera IO Hos... | 1     | ipu3_cio2  | 192FBE0755 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8168 | 1043:200f | Realtek... | RTL8111/8168/8411 PCI Exp... | 441   | r8169      | C53DF5F083 |
| 14e4:16b5 | 1025:0647 | Broadco... | NetLink BCM57785 Gigabit ... | 212   | tg3        | E67DFC255A |
| 10ec:8136 | 1043:200f | Realtek... | RTL810xE PCI Express Fast... | 198   | r8169      | F8FDA4EFC3 |
| 10ec:8168 | 1043:16d5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 138   | r8169      | 527313B5FF |
| 1969:2062 | 1043:8468 | Attansi... | AR8152 v2.0 Fast Ethernet    | 134   | atl1c      | A84D413088 |
| 10ec:8168 | 17aa:5002 | Realtek... | RTL8111/8168/8411 PCI Exp... | 116   | r8169      | 65D329A2C6 |
| 197b:0250 | 1043:1905 | JMicron... | JMC250 PCI Express Gigabi... | 116   | jme        | F47F34752E |
| 1969:1083 | 1043:1851 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 95    | atl1c      | 6B25B8982D |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 86    | r8169      | 8EB32C768B |
| 14e4:16b5 | 1025:0504 | Broadco... | NetLink BCM57785 Gigabit ... | 86    | tg3        | 8579BA1B16 |
| 1969:2062 | 17aa:3979 | Qualcom... | AR8152 v2.0 Fast Ethernet    | 84    | atl1c      | A7618091FB |
| 14e4:1693 | 1025:011c | Broadco... | NetLink BCM5787M Gigabit ... | 79    | tg3        | 7387D70AD5 |
| 14e4:1692 | 1025:036d | Broadco... | NetLink BCM57780 Gigabit ... | 77    | tg3        | D023F50697 |
| 1969:1090 | 17aa:3979 | Qualcom... | AR8162 Fast Ethernet         | 75    | alx        | 891002E8F2 |
| 10ec:8136 | 17aa:3975 | Realtek... | RTL810xE PCI Express Fast... | 62    | r8169      | F72A609702 |
| 1969:1063 | 1043:1820 | Qualcom... | AR8131 Gigabit Ethernet      | 61    | atl1c      | 49783F833C |
| 10ec:8168 | 1043:1277 | Realtek... | RTL8111/8168/8411 PCI Exp... | 60    | r8169      | 826F5492EB |
| 1969:1062 | 1043:838a | Qualcom... | AR8132 Fast Ethernet         | 59    | atl1c      | B658C90327 |
| 10ec:8136 | 1179:ff00 | Realtek... | RTL810xE PCI Express Fast... | 56    | r8169      | C5ADBBB2B3 |
| 10ec:8136 | 10ec:0123 | Realtek... | RTL810xE PCI Express Fast... | 55    | r8169      | BDFF3A60F1 |
| 10ec:8168 | 17aa:3816 | Realtek... | RTL8111/8168/8411 PCI Exp... | 54    | r8169      | CC7193A7B9 |
| 10ec:8168 | 1043:11f5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 53    | r8169      | FAECBEFA9B |
| 10ec:8168 | 1b0a:20d9 | Realtek... | RTL8111/8168/8411 PCI Exp... | 52    | r8169      | AC77E66D3F |
| 1969:1026 | 1043:14f5 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 52    | atl1e      | 38190AD2E1 |
| 1969:10a0 | 17aa:3802 | Qualcom... | QCA8172 Fast Ethernet        | 51    | alx        | 06603D3DCE |
| 14e4:1698 | 1025:0207 | Broadco... | NetLink BCM5784M Gigabit ... | 50    | tg3        | 47E2374F61 |
| 14e4:16b3 | 1025:0775 | Broadco... | NetXtreme BCM57786 Gigabi... | 50    | tg3        | AB33DE8D3B |
| 10ec:8168 | 144d:c0da | Realtek... | RTL8111/8168/8411 PCI Exp... | 49    | r8169      | 0F042024B4 |
| 10ec:8168 | 17aa:3975 | Realtek... | RTL8111/8168/8411 PCI Exp... | 48    | r8169      | 05D969D697 |
| 10ec:8168 | 17aa:3812 | Realtek... | RTL8111/8168/8411 PCI Exp... | 46    | r8169      | 760B445B08 |
| 1969:1091 | 1043:14c7 | Qualcom... | AR8161 Gigabit Ethernet      | 46    | alx        | 9A401175B3 |
| 10ec:8136 | 17aa:392e | Realtek... | RTL810xE PCI Express Fast... | 45    | r8169      | 601D53F9EB |
| 14e4:1713 | 17aa:3a23 | Broadco... | NetLink BCM5906M Fast Eth... | 44    | tg3        | 370DCD58CC |
| 10ec:8168 | 144d:c606 | Realtek... | RTL8111/8168/8411 PCI Exp... | 43    | r8169      | EE56C112BB |
| 1969:1083 | 1043:13c7 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 43    | atl1c      | EA07B48EB4 |
| 10ec:8136 | 1028:04b0 | Realtek... | RTL810xE PCI Express Fast... | 41    | r8169      | C0868A2B0C |
| 10ec:8139 | 1043:1045 | Realtek... | RTL-8100/8101L/8139 PCI F... | 41    | 8139too... | 1B0893029F |
| 14e4:1692 | 1025:033d | Broadco... | NetLink BCM57780 Gigabit ... | 40    | tg3        | CB3BAA60D9 |
| 11ab:4381 | 104d:9071 | Marvell... | Yukon Optima 88E8059 [PCI... | 39    | sky2       | 3C5767E938 |
| 10ec:8136 | 10ec:8136 | Realtek... | RTL810xE PCI Express Fast... | 38    | r8169      | EB58946826 |
| 10ec:8168 | 1025:0866 | Realtek... | RTL8111/8168/8411 PCI Exp... | 35    | r8169      | 1C77D7A584 |
| 10ec:8168 | 144d:c0b6 | Realtek... | RTL8111/8168/8411 PCI Exp... | 35    | r8169      | 616616B60F |
| 10ec:8168 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 34    | r8169      | 02A2AC15DE |
| 14e4:16b4 | 14e4:16b4 | Broadco... | NetXtreme BCM57765 Gigabi... | 34    | tg3        | 16BDB52C40 |
| 10ec:8136 | 17aa:3830 | Realtek... | RTL810xE PCI Express Fast... | 33    | r8169      | EE1CFF7014 |
| 1969:1062 | 1025:0212 | Qualcom... | AR8132 Fast Ethernet         | 33    | atl1c      | 6029A4A18A |
| 8086:155a | 17aa:2214 | Intel      | Ethernet Connection I218-LM  | 33    | e1000e     | 7637F3DE5F |
| 10ec:8136 | 1179:fb37 | Realtek... | RTL810xE PCI Express Fast... | 32    | r8169      | 806B890CCF |
| 10ec:8168 | 1043:104c | Realtek... | RTL8111/8168/8411 PCI Exp... | 32    | r8169      | 0051F69751 |
| 11ab:4354 | 144d:c06d | Marvell... | 88E8040 PCI-E Fast Ethern... | 32    | sky2       | BC68546696 |
| 1969:1090 | 17aa:3978 | Qualcom... | AR8162 Fast Ethernet         | 32    | alx        | ECF9D3F57B |
| 1039:0191 | 1043:1815 | Silicon... | 191 Gigabit Ethernet Adapter | 30    | sis190     | DAC4B8C42F |
| 10ec:8136 | 103c:3577 | Realtek... | RTL810xE PCI Express Fast... | 30    | r8169      | 4201CDD966 |
| 10ec:8168 | 1043:1587 | Realtek... | RTL8111/8168/8411 PCI Exp... | 30    | r8169      | 8B6978A8BF |
| 1969:1063 | 17aa:3956 | Qualcom... | AR8131 Gigabit Ethernet      | 30    | atl1c      | 17BE920F30 |
| 10ec:8136 | 1025:0590 | Realtek... | RTL810xE PCI Express Fast... | 29    | r8169      | D5A624C8FE |
| 10ec:8168 | 144d:c652 | Realtek... | RTL8111/8168/8411 PCI Exp... | 29    | r8169      | A57B555F26 |
| 11ab:4354 | 144d:c072 | Marvell... | 88E8040 PCI-E Fast Ethern... | 29    | sky2       | 3A0FEA4700 |
| 14e4:1673 | 1028:01f9 | Broadco... | NetXtreme BCM5755M Gigabi... | 29    | tg3        | E5DE762918 |
| 14e4:1684 | 1025:013c | Broadco... | NetXtreme BCM5764M Gigabi... | 29    | tg3        | 77E3B20E26 |
| 1969:2060 | 1179:ff1e | Qualcom... | AR8152 v1.1 Fast Ethernet    | 29    | atl1c      | 37460463A1 |
| 10ec:8168 | 1025:1012 | Realtek... | RTL8111/8168/8411 PCI Exp... | 28    | r8169      | 5A7F96289D |
| 10ec:8168 | 1025:1094 | Realtek... | RTL8111/8168/8411 PCI Exp... | 28    | r8169      | E4B342382F |
| 11ab:4354 | 144d:c07f | Marvell... | 88E8040 PCI-E Fast Ethern... | 28    | sky2       | 408D0B84F9 |
| 1969:1062 | 1043:14e5 | Qualcom... | AR8132 Fast Ethernet         | 28    | atl1c      | 70E60207C2 |
| 10ec:8136 | 103c:184a | Realtek... | RTL810xE PCI Express Fast... | 27    | r8169      | 0D67044A36 |
| 1969:1062 | 1025:0349 | Qualcom... | AR8132 Fast Ethernet         | 27    | atl1c      | 2612D462D9 |
| 1969:10a0 | 17aa:3806 | Qualcom... | QCA8172 Fast Ethernet        | 27    | alx        | E1D3B73A71 |
| 10ec:8168 | 1025:1193 | Realtek... | RTL8111/8168/8411 PCI Exp... | 26    | r8169      | 141D7917FF |
| 10ec:8168 | 103c:8330 | Realtek... | RTL8111/8168/8411 PCI Exp... | 26    | r8169      | D32B7275C3 |
| 1969:1091 | 1043:1477 | Qualcom... | AR8161 Gigabit Ethernet      | 26    | alx        | C38728C67C |
| 1969:10a0 | 17aa:3805 | Qualcom... | QCA8172 Fast Ethernet        | 26    | alx        | 6420DFC899 |
| 10ec:8136 | 1179:ff1e | Realtek... | RTL810xE PCI Express Fast... | 25    | r8169      | FD3E1CD25E |
| 10ec:8168 | 104d:908b | Realtek... | RTL8111/8168/8411 PCI Exp... | 25    | r8169      | 9B5D49431C |
| 10ec:8168 | 17aa:3854 | Realtek... | RTL8111/8168/8411 PCI Exp... | 25    | r8169      | 005771EDFD |
| 1969:1083 | 1025:0686 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 25    | atl1c      | 29CFE1AD23 |
| 10ec:8168 | 144d:c581 | Realtek... | RTL8111/8168/8411 PCI Exp... | 24    | r8169      | 4B260556B7 |
| 10ec:8168 | 1025:1085 | Realtek... | RTL8111/8168/8411 PCI Exp... | 23    | r8169      | AE1CE65D11 |
| 10ec:8168 | 10cf:175a | Realtek... | RTL8111/8168/8411 PCI Exp... | 23    | r8169      | B9A4817612 |
| 10ec:8168 | 17aa:380a | Realtek... | RTL8111/8168/8411 PCI Exp... | 23    | r8169      | E4D4717A01 |
| 14e4:1713 | 1025:0136 | Broadco... | NetLink BCM5906M Fast Eth... | 23    | tg3        | 1EF9D813A6 |
| 10ec:8136 | 103c:2213 | Realtek... | RTL810xE PCI Express Fast... | 22    | r8169      | 964E06B446 |
| 10ec:8136 | 144d:c059 | Realtek... | RTL810xE PCI Express Fast... | 22    | r8169      | 79C2C53D26 |
| 10ec:8168 | 1025:1192 | Realtek... | RTL8111/8168/8411 PCI Exp... | 22    | r8169      | 0D71E52A34 |
| 10ec:8168 | 103c:1818 | Realtek... | RTL8111/8168/8411 PCI Exp... | 22    | r8169      | C865BDB72F |
| 10ec:8168 | 104d:90ab | Realtek... | RTL8111/8168/8411 PCI Exp... | 22    | r8169      | B56B7F6394 |
| 14e4:1692 | 1025:047f | Broadco... | NetLink BCM57780 Gigabit ... | 22    | tg3        | DE168F8DCC |
| 14e4:1692 | 1025:0487 | Broadco... | NetLink BCM57780 Gigabit ... | 22    | tg3        | E6323014B6 |
| 1969:2060 | 1025:0349 | Qualcom... | AR8152 v1.1 Fast Ethernet    | 22    | atl1c      | 8CE41DB531 |
| 10de:0ab0 | 10de:cb79 | Nvidia     | MCP79 Ethernet               | 21    | forcedeth  | 9F753AC669 |
| 10ec:8136 | 1179:fd3c | Realtek... | RTL810xE PCI Express Fast... | 21    | r8169      | BD758B3E12 |
| 10ec:8168 | 1025:098a | Realtek... | RTL8111/8168/8411 PCI Exp... | 21    | r8169      | 6D1C781DE0 |
| 11ab:4354 | 1028:022f | Marvell... | 88E8040 PCI-E Fast Ethern... | 21    | sky2       | 55CD396670 |
| 14e4:1693 | 1025:011e | Broadco... | NetLink BCM5787M Gigabit ... | 21    | tg3        | ED83D72FBE |
| 1969:1048 | 1043:14e5 | Qualcom... | Attansic L1 Gigabit Ethernet | 21    | atl1       | D9970BDA58 |
| 1969:10a0 | 17aa:3801 | Qualcom... | QCA8172 Fast Ethernet        | 21    | alx        | 6ADE50F197 |
| 1969:10a1 | 1025:076b | Qualcom... | QCA8171 Gigabit Ethernet     | 21    | alx        | 6479F7F12B |
| 10ec:8136 | 1028:0651 | Realtek... | RTL810xE PCI Express Fast... | 20    | r8169      | 1E1FE2154B |
| 10ec:8136 | 103c:143a | Realtek... | RTL810xE PCI Express Fast... | 20    | r8169      | 2E967DD7C0 |
| 10ec:8136 | 103c:1670 | Realtek... | RTL810xE PCI Express Fast... | 20    | r8169      | FC29696703 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 168c:002b | 1a3b:1089 | Qualcom... | AR9285 Wireless Network A... | 418   | ath9k      | 07CD36611F |
| 1814:3290 | 103c:18ec | Ralink     | RT3290 Wireless 802.11n 1... | 189   | rt2800pci  | A978F2CA38 |
| 14e4:4365 | 17aa:0611 | Broadco... | BCM43142 802.11b/g/n         | 183   | wl         | 06603D3DCE |
| 168c:0032 | 1a3b:2c97 | Qualcom... | AR9485 Wireless Network A... | 183   | ath9k      | 92AE8C0F3B |
| 168c:002b | 105b:e035 | Qualcom... | AR9285 Wireless Network A... | 182   | ath9k      | D023F50697 |
| 8086:4222 | 8086:1001 | Intel      | PRO/Wireless 3945ABG [Gol... | 179   | iwl3945    | 253B1DAE47 |
| 168c:002b | 17aa:30a1 | Qualcom... | AR9285 Wireless Network A... | 168   | ath9k      | A7618091FB |
| 168c:002b | 1a3b:2c37 | Qualcom... | AR9285 Wireless Network A... | 166   | ath9k      | 6B25B8982D |
| 168c:0032 | 144d:4105 | Qualcom... | AR9485 Wireless Network A... | 144   | ath9k      | 53302E45B6 |
| 168c:0034 | 105b:e052 | Qualcom... | AR9462 Wireless Network A... | 139   | ath9k      | DE168F8DCC |
| 168c:0036 | 11ad:0642 | Qualcom... | QCA9565 / AR9565 Wireless... | 130   | ath9k      | 50FFA5DCEC |
| 8086:0896 | 8086:5005 | Intel      | Centrino Wireless-N 130      | 129   | iwlwifi    | EE56C112BB |
| 168c:0042 | 11ad:08a6 | Qualcom... | QCA9377 802.11ac Wireless... | 121   | ath10k_pci | 6E04F26B23 |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 120   | iwlwifi    | AC96DD45F9 |
| 14e4:4727 | 103c:1483 | Broadco... | BCM4313 802.11bgn Wireles... | 116   | wl         | 23E7475693 |
| 168c:001c | 1a3b:1026 | Qualcom... | AR242x / AR542x Wireless ... | 114   | ath5k      | 54C92BF69C |
| 10ec:b723 | 17aa:b736 | Realtek... | RTL8723BE PCIe Wireless N... | 113   | rtl8723be  | 00C22F3924 |
| 168c:001c | 1468:0428 | Qualcom... | AR242x / AR542x Wireless ... | 107   | ath5k      | 6029A4A18A |
| 168c:0032 | 11ad:6617 | Qualcom... | AR9485 Wireless Network A... | 100   | ath9k      | 4B260556B7 |
| 168c:0036 | 1028:020c | Qualcom... | QCA9565 / AR9565 Wireless... | 99    | ath9k      | 6BC169574C |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 99    | iwlwifi    | D0C54EF6E4 |
| 168c:002b | 105b:e025 | Qualcom... | AR9285 Wireless Network A... | 97    | ath9k      | 86987CF1ED |
| 8086:4232 | 8086:1201 | Intel      | WiFi Link 5100               | 95    | iwlwifi    | 508F60B315 |
| 168c:0032 | 103c:1785 | Qualcom... | AR9485 Wireless Network A... | 94    | ath9k      | AB69AA73CD |
| 8086:08ae | 8086:1005 | Intel      | Centrino Wireless-N 100      | 94    | iwlwifi    | 6150CCFA00 |
| 8086:4229 | 8086:1101 | Intel      | PRO/Wireless 4965 AG or A... | 93    | iwl4965    | CF3A7AD203 |
| 168c:002e | 105b:e034 | Qualcom... | AR9287 Wireless Network A... | 92    | ath9k      | 690FFF1815 |
| 168c:0036 | 17aa:4026 | Qualcom... | QCA9565 / AR9565 Wireless... | 92    | ath9k      | 4A22031CA8 |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 89    | iwlwifi    | CE2A6FB934 |
| 14e4:4727 | 14e4:051b | Broadco... | BCM4313 802.11bgn Wireles... | 88    | wl         | F9F3745636 |
| 14e4:4727 | 103c:1795 | Broadco... | BCM4313 802.11bgn Wireles... | 87    | wl         | 42DF53B120 |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 84    | iwlwifi    | C53DF5F083 |
| 168c:0036 | 1028:020e | Qualcom... | QCA9565 / AR9565 Wireless... | 83    | ath9k      | A38D1A4CE9 |
| 8086:0887 | 8086:4062 | Intel      | Centrino Wireless-N 2230     | 82    | iwlwifi    | 3F62942EFE |
| 8086:4237 | 8086:1211 | Intel      | PRO/Wireless 5100 AGN [Sh... | 82    | iwlwifi    | FDAB3CF92F |
| 168c:002b | 105b:e016 | Qualcom... | AR9285 Wireless Network A... | 81    | ath9k      | 6827DB0C63 |
| 8086:4232 | 8086:1206 | Intel      | WiFi Link 5100               | 81    | iwlwifi    | 77E3B20E26 |
| 10ec:8723 | 10ec:0726 | Realtek... | RTL8723AE PCIe Wireless N... | 78    | rtl8723ae  | 891DE458D7 |
| 14e4:4727 | 105b:e042 | Broadco... | BCM4313 802.11bgn Wireles... | 76    | wl         | E67DFC255A |
| 168c:0032 | 17aa:3218 | Qualcom... | AR9485 Wireless Network A... | 76    | ath9k      | DB0C6A651D |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 76    | iwlwifi    | A586F57112 |
| 8086:4222 | 103c:135c | Intel      | PRO/Wireless 3945ABG [Gol... | 76    | iwl3945    | 531D26CDD8 |
| 14e4:4727 | 144f:7179 | Broadco... | BCM4313 802.11bgn Wireles... | 74    | wl         | EB58946826 |
| 168c:002b | 144f:7167 | Qualcom... | AR9285 Wireless Network A... | 74    | ath9k      | BC68546696 |
| 10ec:b723 | 11ad:1723 | Realtek... | RTL8723BE PCIe Wireless N... | 71    | rtl8723be  | 8BBDB85BE4 |
| 14e4:4727 | 14e4:0510 | Broadco... | BCM4313 802.11bgn Wireles... | 71    | wl         | 8E79CDDBDA |
| 14e4:4727 | 185f:051a | Broadco... | BCM4313 802.11bgn Wireles... | 71    | wl         | 82EA1BF753 |
| 168c:0032 | 1a3b:1186 | Qualcom... | AR9485 Wireless Network A... | 70    | ath9k      | 5AEE6B7CA7 |
| 14e4:4315 | 103c:1508 | Broadco... | BCM4312 802.11b/g LP-PHY     | 69    | ssb        | AB17752168 |
| 14e4:4315 | 14e4:04b5 | Broadco... | BCM4312 802.11b/g LP-PHY     | 69    | ssb        | 601D53F9EB |
| 168c:002b | 103c:3040 | Qualcom... | AR9285 Wireless Network A... | 68    | ath9k      | 73E5B46F66 |
| 10ec:b723 | 10ec:b729 | Realtek... | RTL8723BE PCIe Wireless N... | 66    | rtl8723be  | D607079392 |
| 168c:001c | 144f:7131 | Qualcom... | AR242x / AR542x Wireless ... | 65    | ath5k      | FC7D577AB7 |
| 168c:002b | 103c:1461 | Qualcom... | AR9285 Wireless Network A... | 65    | ath9k      | 7306A03690 |
| 168c:0032 | 11ad:6627 | Qualcom... | AR9485 Wireless Network A... | 65    | ath9k      | 0F8CE4DCC0 |
| 10ec:b723 | 103c:2231 | Realtek... | RTL8723BE PCIe Wireless N... | 64    | rtl8723be  | 4B70A9D252 |
| 8086:a370 | 8086:0034 | Intel      | Wireless-AC 9560 [Jeffers... | 64    | iwlwifi    | 3A4D90A1C3 |
| 14e4:4311 | 1028:0007 | Broadco... | BCM4311 802.11b/g WLAN       | 61    | ssb        | 14AC7530E2 |
| 168c:0034 | 11ad:6621 | Qualcom... | AR9462 Wireless Network A... | 60    | ath9k      | 03766A19F1 |
| 168c:0042 | 17aa:0901 | Qualcom... | QCA9377 802.11ac Wireless... | 60    | ath10k_pci | DE5FB421D9 |
| 168c:002b | 1028:0205 | Qualcom... | AR9285 Wireless Network A... | 59    | ath9k      | 3ACD13490F |
| 14e4:4358 | 105b:e040 | Broadco... | BCM43227 802.11b/g/n         | 58    | wl         | 8579BA1B16 |
| 168c:0036 | 1a3b:213a | Qualcom... | QCA9565 / AR9565 Wireless... | 58    | ath9k      | F8FDA4EFC3 |
| 14e4:4315 | 1028:000c | Broadco... | BCM4312 802.11b/g LP-PHY     | 56    | wl         | B7AD02779E |
| 14e4:4727 | 1a3b:2047 | Broadco... | BCM4313 802.11bgn Wireles... | 56    | wl         | 4ADFAB3C4E |
| 1814:3290 | 105b:e055 | Ralink     | RT3290 Wireless 802.11n 1... | 55    | rt2800pci  | F71E42FC3C |
| 8086:0084 | 8086:1315 | Intel      | Centrino Wireless-N 1000 ... | 55    | iwlwifi    | 72424367AD |
| 168c:002b | 105b:e017 | Qualcom... | AR9285 Wireless Network A... | 54    | ath9k      | 3C5767E938 |
| 168c:003e | 1a56:1535 | Qualcom... | QCA6174 802.11ac Wireless... | 53    | ath10k_pci | 3A71C37AE2 |
| 8086:3165 | 8086:4410 | Intel      | Wireless 3165                | 53    | iwlwifi    | 8090C8CC68 |
| 14e4:4727 | 103c:145c | Broadco... | BCM4313 802.11bgn Wireles... | 52    | wl         | 1FF111737A |
| 14e4:4311 | 1468:0422 | Broadco... | BCM4311 802.11b/g WLAN       | 51    | ssb        | 16BE592F4F |
| 168c:0042 | 17aa:4035 | Qualcom... | QCA9377 802.11ac Wireless... | 51    | ath10k_pci | 7957C03703 |
| 14e4:4365 | 1028:0016 | Broadco... | BCM43142 802.11b/g/n         | 49    | wl         | 67CD98E6C7 |
| 168c:0032 | 105b:e044 | Qualcom... | AR9485 Wireless Network A... | 49    | ath9k      | B56B7F6394 |
| 168c:0032 | 105b:e047 | Qualcom... | AR9485 Wireless Network A... | 48    | ath9k      | 11B9C937C9 |
| 168c:0032 | 1a3b:2126 | Qualcom... | AR9485 Wireless Network A... | 48    | ath9k      | 2D1845C282 |
| 168c:0036 | 11ad:0632 | Qualcom... | QCA9565 / AR9565 Wireless... | 48    | ath9k      | 4A1964118D |
| 10ec:8723 | 1a3b:2114 | Realtek... | RTL8723AE PCIe Wireless N... | 45    | rtl8723ae  | 86D04818BE |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 45    | 8821ce     | 4F9294F4B5 |
| 1814:3090 | 103c:1453 | Ralink     | RT3090 Wireless 802.11n 1... | 45    | rt2800pci  | 36FF276D26 |
| 14e4:4727 | 144f:7175 | Broadco... | BCM4313 802.11bgn Wireles... | 43    | wl         | BD758B3E12 |
| 168c:0032 | 1028:0209 | Qualcom... | AR9485 Wireless Network A... | 43    | ath9k      | F72534E2D2 |
| 168c:0036 | 105b:e07f | Qualcom... | QCA9565 / AR9565 Wireless... | 43    | ath9k      | 1C77D7A584 |
| 8086:24fd | 8086:0110 | Intel      | Wireless 8265 / 8275         | 43    | iwlwifi    | CA74DF306B |
| 168c:001c | 103c:137b | Qualcom... | AR242x / AR542x Wireless ... | 42    | ath5k      | 084F7E13DA |
| 168c:0032 | 11ad:6628 | Qualcom... | AR9485 Wireless Network A... | 42    | ath9k      | A1A1F1965A |
| 1814:5390 | 105b:e054 | Ralink     | RT5390 Wireless 802.11n 1... | 42    | rt2800pci  | 923B4CD756 |
| 10ec:8179 | 103c:197d | Realtek... | RTL8188EE Wireless Networ... | 41    | rtl8188ee  | 99C1387438 |
| 14e4:4357 | 105b:e021 | Broadco... | BCM43225 802.11b/g/n         | 41    | wl         | 4C990A61B6 |
| 14e4:4365 | 103c:804a | Broadco... | BCM43142 802.11b/g/n         | 41    | wl         | 2EC22FA87A |
| 14e4:4727 | 14e4:0608 | Broadco... | BCM4313 802.11bgn Wireles... | 41    | wl         | FA98476936 |
| 168c:002b | 11ad:6613 | Qualcom... | AR9285 Wireless Network A... | 41    | ath9k      | FE2AB22987 |
| 168c:0042 | 1028:1810 | Qualcom... | QCA9377 802.11ac Wireless... | 41    | ath10k_pci | 9402076861 |
| 8086:08b2 | 8086:c270 | Intel      | Wireless 7260                | 41    | iwlwifi    | 7637F3DE5F |
| 10ec:b723 | 103c:81c1 | Realtek... | RTL8723BE PCIe Wireless N... | 40    | rtl8723be  | 1CC2218397 |
| 168c:002e | 11ad:6603 | Qualcom... | AR9287 Wireless Network A... | 40    | ath9k      | E5D4CDDD0B |
| 168c:0036 | 1a3b:2130 | Qualcom... | QCA9565 / AR9565 Wireless... | 40    | ath9k      | 70DE2F36AE |
| 168c:0042 | 1a3b:2b31 | Qualcom... | QCA9377 802.11ac Wireless... | 39    | ath10k_pci | 7D2B995B44 |
| 8086:4222 | 8086:1041 | Intel      | PRO/Wireless 3945ABG [Gol... | 39    | iwl3945    | 4FFE571137 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0085 | 8086:1311 | Intel      | Centrino Advanced-N 6205 ... | 169   | iwlwifi    | 6D5F1234C2 |
| 10ec:d723 | 103c:8319 | Realtek... | RTL8723DE Wireless Networ... | 135   | rtl8723de  | D7977A3B0E |
| 8086:088e | 8086:4060 | Intel      | Centrino Advanced-N 6235     | 99    | iwlwifi    | B884A5EAC4 |
| 8086:1502 | 17aa:21f3 | Intel      | 82579LM Gigabit Network C... | 97    | e1000e     | 6D5F1234C2 |
| 8086:1502 | 17aa:21ce | Intel      | 82579LM Gigabit Network C... | 82    | e1000e     | FBF8462F41 |
| 8086:4239 | 8086:1311 | Intel      | Centrino Advanced-N 6200     | 77    | iwlwifi    | E2C04796A0 |
| 8086:10ea | 17aa:2153 | Intel      | 82577LM Gigabit Network C... | 66    | e1000e     | DA5E944C6C |
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 60    | iwlwifi    | AC77E66D3F |
| 8086:0082 | 8086:1321 | Intel      | Centrino Advanced-N 6205 ... | 55    | iwlwifi    | CA6EFEBBD7 |
| 8086:422b | 8086:1121 | Intel      | Centrino Ultimate-N 6300     | 51    | iwlwifi    | 8B920A3699 |
| 8086:4238 | 8086:1111 | Intel      | Centrino Ultimate-N 6300     | 51    | iwlwifi    | C99279F977 |
| 8086:10f5 | 17aa:20ee | Intel      | 82567LM Gigabit Network C... | 47    | e1000e     | FDAB3CF92F |
| 8086:0082 | 8086:1301 | Intel      | Centrino Advanced-N 6205 ... | 39    | iwlwifi    | B9A4817612 |
| 8086:10f5 | 1028:0233 | Intel      | 82567LM Gigabit Network C... | 30    | e1000e     | 1F49A84F1F |
| 14e4:170c | 1025:0090 | Broadco... | BCM4401-B0 100Base-TX        | 28    | b44        | 719BE91D02 |
| 8086:1049 | 17aa:20b9 | Intel      | 82566MM Gigabit Network C... | 28    | e1000e     | 7F41843359 |
| 8086:10c4 | 103c:30d8 | Intel      | 82562GT 10/100 Network Co... | 28    | e1000e     | 48EE31D6E9 |
| 8086:1502 | 1028:0493 | Intel      | 82579LM Gigabit Network C... | 28    | e1000e     | CA6EFEBBD7 |
| 8086:0091 | 8086:5201 | Intel      | Centrino Advanced-N 6230 ... | 26    | iwlwifi    | 4398E73607 |
| 8086:422c | 8086:1301 | Intel      | Centrino Advanced-N 6200     | 24    | iwlwifi    | EEFC712947 |
| 14e4:170c | 103c:30a2 | Broadco... | BCM4401-B0 100Base-TX        | 23    | b44        | 531D26CDD8 |
| 14e4:170c | 1028:01f5 | Broadco... | BCM4401-B0 100Base-TX        | 21    | b44        | BFDE36E2F4 |
| 8086:10ea | 1028:040a | Intel      | 82577LM Gigabit Network C... | 21    | e1000e     | D588CD38C2 |
| 10ec:8136 | 103c:3567 | Realtek... | RTL810xE PCI Express Fast... | 19    | r8169      | 937DD869FC |
| 14e4:4331 | 14e4:4331 | Broadco... | BCM4331 802.11a/b/g/n        | 18    | wl         | 16BDB52C40 |
| 8086:422c | 8086:1321 | Intel      | Centrino Advanced-N 6200     | 18    | iwlwifi    | D588CD38C2 |
| 8086:088e | 8086:4460 | Intel      | Centrino Advanced-N 6235     | 17    | iwlwifi    | B20F51D9C3 |
| 8086:1502 | 103c:179b | Intel      | 82579LM Gigabit Network C... | 17    | e1000e     | ED317797F0 |
| 8086:1502 | 103c:161c | Intel      | 82579LM Gigabit Network C... | 16    | e1000e     | 6F7AAF1391 |
| 8086:422b | 8086:1101 | Intel      | Centrino Ultimate-N 6300     | 16    | iwlwifi    | ED317797F0 |
| 8086:10ea | 103c:7008 | Intel      | 82577LM Gigabit Network C... | 15    | e1000e     | AB17752168 |
| 14e4:170c | 1028:01af | Broadco... | BCM4401-B0 100Base-TX        | 13    | b44        | 586A6A9F8A |
| 8086:1049 | 17aa:20de | Intel      | 82566MM Gigabit Network C... | 13    | e1000e     | F5D4852384 |
| 8086:1092 | 1179:ff10 | Intel      | PRO/100 VE Network Connec... | 13    | e100       | 4FFE571137 |
| 8086:1502 | 1028:0534 | Intel      | 82579LM Gigabit Network C... | 13    | e1000e     | 8C26DF88EE |
| 8086:1503 | 103c:17ab | Intel      | 82579V Gigabit Network Co... | 13    | e1000e     | 3B64B265CF |
| 8086:0091 | 8086:5221 | Intel      | Centrino Advanced-N 6230 ... | 12    | iwlwifi    | FC0B23D4DC |
| 8086:10bf | 17aa:20ee | Intel      | 82567LF Gigabit Network C... | 12    | e1000e     | AEA2A879A0 |
| 8086:10ea | 1028:040b | Intel      | 82577LM Gigabit Network C... | 12    | e1000e     | 80B359DC57 |
| 8086:0087 | 8086:1306 | Intel      | Centrino Advanced-N + WiM... | 11    | iwlwifi    | 26EAFF6014 |
| 8086:10f5 | 1028:024f | Intel      | 82567LM Gigabit Network C... | 11    | e1000e     | 5A8B3F34A3 |
| 8086:0087 | 8086:1301 | Intel      | Centrino Advanced-N + WiM... | 10    | iwlwifi    | 195F0109A8 |
| 8086:10ea | 103c:7007 | Intel      | 82577LM Gigabit Network C... | 10    | e1000e     | 9D71D7ED76 |
| 8086:1502 | 1028:0494 | Intel      | 82579LM Gigabit Network C... | 10    | e1000e     | 31F0876A89 |
| 8086:1502 | 1028:04a3 | Intel      | 82579LM Gigabit Network C... | 10    | e1000e     | 19E1CA5871 |
| 8086:1502 | 1028:0535 | Intel      | 82579LM Gigabit Network C... | 9     | e1000e     | 95A631AAE1 |
| 8086:1502 | 103c:162b | Intel      | 82579LM Gigabit Network C... | 9     | e1000e     | FAF97CF550 |
| 8086:1503 | 1179:0001 | Intel      | 82579V Gigabit Network Co... | 9     | e1000e     | 2D428CD5FA |
| 14e4:170c | 1028:01c9 | Broadco... | BCM4401-B0 100Base-TX        | 8     | b44        | 8947DE9DC2 |
| 14e4:170c | 1028:022a | Broadco... | BCM4401-B0 100Base-TX        | 8     | b44        | 77649E9A5A |
| 8086:0085 | 8086:c220 | Intel      | Centrino Advanced-N 6205 ... | 8     | iwlwifi    | DF1FD87B87 |
| 8086:1049 | 103c:30be | Intel      | 82566MM Gigabit Network C... | 8     | e1000e     | 2B9B5142AF |
| 8086:10ea | 103c:172a | Intel      | 82577LM Gigabit Network C... | 8     | e1000e     | E2C04796A0 |
| 8086:10f5 | 103c:30db | Intel      | 82567LM Gigabit Network C... | 8     | e1000e     | 9792924118 |
| 8086:1502 | 1028:0532 | Intel      | 82579LM Gigabit Network C... | 8     | e1000e     | 963D3EBFE9 |
| 8086:1502 | 103c:1618 | Intel      | 82579LM Gigabit Network C... | 8     | e1000e     | 7D1AE28E6D |
| 10ec:818b | 10ec:001b | Realtek... | RTL8192EE PCIe Wireless N... | 7     | rtl8192ee  | A8ECB197C5 |
| 14e4:170c | 103c:099c | Broadco... | BCM4401-B0 100Base-TX        | 7     | b44        | E0DF895DC8 |
| 8086:10ea | 10cf:1574 | Intel      | 82577LM Gigabit Network C... | 7     | e1000e     | EEFC712947 |
| 8086:10eb | 103c:1471 | Intel      | 82577LC Gigabit Network C... | 7     | e1000e     | 801F83247C |
| 8086:1502 | 1028:0492 | Intel      | 82579LM Gigabit Network C... | 7     | e1000e     | 9C07EE4C86 |
| 8086:1502 | 10cf:161b | Intel      | 82579LM Gigabit Network C... | 7     | e1000e     | 8F2E060D39 |
| 10de:0269 | 103c:30b7 | Nvidia     | MCP51 Ethernet Controller    | 6     | forcedeth  | B699788F33 |
| 8086:1049 | 103c:30c5 | Intel      | 82566MM Gigabit Network C... | 6     | e1000e     | AB3B50FF87 |
| 8086:10f5 | 1028:024d | Intel      | 82567LM Gigabit Network C... | 6     | e1000e     | 59050A5736 |
| 8086:1502 | 103c:18df | Intel      | 82579LM Gigabit Network C... | 6     | e1000e     | 4D5087B262 |
| 8086:1503 | 103c:1619 | Intel      | 82579V Gigabit Network Co... | 6     | e1000e     | 6140D0688E |
| 10ec:8168 | 17aa:3810 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8169      | 539D35250D |
| 10ec:8168 | 17aa:505b | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8169      | 627FE75106 |
| 14e4:170c | 1028:01cd | Broadco... | BCM4401-B0 100Base-TX        | 5     | b44        | 8557CCF8D1 |
| 14e4:170c | 1028:01f1 | Broadco... | BCM4401-B0 100Base-TX        | 5     | b44        | CA83DB613D |
| 14e4:170c | 1028:01f2 | Broadco... | BCM4401-B0 100Base-TX        | 5     | b44        | AEF28A0D3B |
| 8086:10ea | 1028:0410 | Intel      | 82577LM Gigabit Network C... | 5     | e1000e     | 3B2BF6356F |
| 8086:10ea | 103c:1520 | Intel      | 82577LM Gigabit Network C... | 5     | e1000e     | 5BC72880EA |
| 8086:10ea | 10f7:8338 | Intel      | 82577LM Gigabit Network C... | 5     | e1000e     | 400317E66E |
| 8086:10f5 | 103c:30e7 | Intel      | 82567LM Gigabit Network C... | 5     | e1000e     | E05FE6B4AB |
| 8086:1502 | 1028:04a4 | Intel      | 82579LM Gigabit Network C... | 5     | e1000e     | 370EF78297 |
| 8086:1503 | 103c:179c | Intel      | 82579V Gigabit Network Co... | 5     | e1000e     | 6008FDBA9D |
| 8086:1503 | 10cf:161c | Intel      | 82579V Gigabit Network Co... | 5     | e1000e     | 39D3E69B25 |
| 8086:422c | 8086:1326 | Intel      | Centrino Advanced-N 6200     | 5     | iwlwifi    | A85D804D5A |
| 8086:4239 | 8086:1316 | Intel      | Centrino Advanced-N 6200     | 5     | iwlwifi    | 0358601780 |
| 10de:0269 | 1043:1385 | Nvidia     | MCP51 Ethernet Controller    | 4     | forcedeth  | 067B3284C7 |
| 14e4:170c | 1028:01cb | Broadco... | BCM4401-B0 100Base-TX        | 4     | b44        | 304B57FAF2 |
| 14e4:170c | 1028:01d4 | Broadcom   | BCM4401-B0 100Base-TX        | 4     | b44        | C01C810908 |
| 14e4:170c | 1028:0228 | Broadco... | BCM4401-B0 100Base-TX        | 4     | b44        | 9295D48DD9 |
| 14e4:170c | 1028:0229 | Broadco... | BCM4401-B0 100Base-TX        | 4     | b44        | 557BDF0E0D |
| 14e4:170c | 144d:b028 | Broadco... | BCM4401-B0 100Base-TX        | 4     | b44        | 55C9A5E56D |
| 14e4:1713 | 103c:30c2 | Broadco... | NetLink BCM5906M Fast Eth... | 4     | tg3        | 30A849B6CA |
| 8086:1092 | 1734:10ad | Intel      | PRO/100 VE Network Connec... | 4     | e100       | B4C2FB4D5A |
| 8086:10c4 | 103c:30d7 | Intel      | 82562GT 10/100 Network Co... | 4     | e1000e     | 696E11AC42 |
| 8086:10ea | 1028:040c | Intel      | 82577LM Gigabit Network C... | 4     | e1000e     | F827065AC9 |
| 8086:10ea | 103c:172b | Intel      | 82577LM Gigabit Network C... | 4     | e1000e     | 35E3CAB7FD |
| 8086:10f5 | 10f7:8338 | Intel      | 82567LM Gigabit Network C... | 4     | e1000e     | FDCC1DFB81 |
| 8086:1502 | 1028:053f | Intel      | 82579LM Gigabit Network C... | 4     | e1000e     | 4D67416D5E |
| 8086:1502 | 103c:162a | Intel      | 82579LM Gigabit Network C... | 4     | e1000e     | 19BF4CEBAD |
| 8086:1502 | 103c:1631 | Intel      | 82579LM Gigabit Network C... | 4     | e1000e     | A31B1E8E5E |
| 8086:1502 | 103c:176b | Intel      | 82579LM Gigabit Network C... | 4     | e1000e     | 46EA3231EB |
| 8086:1502 | 103c:17a7 | Intel      | 82579LM Gigabit Network C... | 4     | e1000e     | AE6CF1B3CA |
| 8086:1502 | 103c:17df | Intel      | 82579LM Gigabit Network C... | 4     | e1000e     | 68A86E6E3F |
| 8086:1502 | 10f7:8338 | Intel      | 82579LM Gigabit Network C... | 4     | e1000e     | B10B744D50 |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1455 | 1022:1455 | AMD        | Zeppelin/Renoir PCIe Dumm... | 4     |            | 35BF9EB2EF |
| 1022:145a | 1022:145a | AMD        | Zeppelin/Raven/Raven2 PCI... | 4     |            | 35BF9EB2EF |
| 8086:9d26 |           | Intel      | Skylake-U/Y Northpeak        | 4     | intel_t... | 1CC0697D7C |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15e6 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Non-S... | 10    | i2c_amd... | 048229855F |
| 8086:9d24 |           | Intel      | Skylake-U/Y SPI Controller   | 7     |            | 3E70A8DFF1 |
| 1022:15e6 | 103c:85ea | AMD        | Raven/Raven2/Renoir Non-S... | 3     | i2c_amd... | D7977A3B0E |
| 8086:22d8 | 103c:813e | Intel      | Integrated Sensor Solution   | 3     | intel_i... | F91E0FBE6B |
| 8086:22d8 | 1043:1400 | Intel      | Integrated Sensor Solution   | 2     | intel_i... | 1A0E086EF8 |
| 8086:9d35 | 1028:073b | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 10A11C50C0 |
| 8086:9d35 | 1028:0740 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | F938CE631A |
| 8086:9d35 | 1028:0741 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | D302412809 |
| 8086:9d35 | 1028:07aa | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 1DC7215E55 |
| 8086:9d35 | 1028:0804 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 9D1947C3A7 |
| 8086:9d35 | 103c:83b2 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 240B48EAA4 |
| 8086:9d35 | 17aa:2238 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 01BED504BA |
| 8086:22d8 | 1028:06ea | Intel      | Integrated Sensor Solution   | 1     | intel_i... | 721C1A7DC3 |
| 8086:22d8 | 1043:13a0 | Intel      | Integrated Sensor Solution   | 1     | intel_i... | C508886F10 |
| 8086:22d8 | 1043:1bdd | Intel      | Integrated Sensor Solution   | 1     | intel_i... | E3400F39DF |
| 8086:22d8 | 1071:a126 | Intel      | Integrated Sensor Solution   | 1     | intel_i... | F2981C1775 |
| 8086:9d35 | 1028:0744 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | B4A5AF0E65 |
| 8086:9d35 | 1028:07ba | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 112EB80A9E |
| 8086:9d35 | 1028:0808 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | A06F19936B |
| 8086:9d35 | 103c:8197 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 910D564E8E |
| 8086:9d35 | 103c:83b3 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | ECE59B9429 |
| 8086:9d35 | 17aa:2241 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 1038A34C39 |
| 8086:9d35 | 17aa:3812 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 57EC66B289 |
| 8086:9d35 | 8086:9d35 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | F1A46E64BC |
| 8086:a135 | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 1     |            | F5FDC69851 |

### Performance counters (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27a3 |           | Intel      | 945GM/GU Chipset Hardware... | 10    |            | FDEA938323 |

### Pic (io(x)-apic) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1106:5364 |           | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 11    |            | 2DFDF716CA |
| 1106:5364 | 103c:3030 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 4     |            | 7EECEB0DB3 |
| 1106:5336 |           | VIA Tec... | K8M890CE I/O APIC Interru... | 3     |            | FEDA3B155D |
| 1106:5353 | 17aa:388a | VIA Tec... | VX800/VX820 APIC and Cent... | 2     |            | CE7524ED3B |
| 1106:5238 | 1734:1093 | VIA Tec... | K8T890 I/O APIC Interrupt... | 1     |            | E9825FB39A |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:16bc | 1025:0647 | Broadco... | BCM57765/57785 SDXC/MMC C... | 212   | sdhci_pci  | E67DFC255A |
| 197b:2381 | 1043:1a07 | JMicron... | Standard SD Host Controller  | 116   | sdhci_pci  | F47F34752E |
| 14e4:16bc | 1025:0504 | Broadco... | BCM57765/57785 SDXC/MMC C... | 86    | sdhci_pci  | 8579BA1B16 |
| 1180:0822 | 17aa:20c8 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 65    | sdhci_pci  | A23E000798 |
| 104c:803c | 1025:011f | Texas I... | PCIxx12 SDA Standard Comp... | 64    | sdhci_pci  | 7387D70AD5 |
| 14e4:16bc | 1025:0775 | Broadco... | BCM57765/57785 SDXC/MMC C... | 50    | sdhci_pci  | AB33DE8D3B |
| 1022:7813 | 17aa:3801 | AMD        | FCH SD Flash Controller      | 44    | sdhci_pci  | 760B445B08 |
| 1022:7806 | 1022:7806 | AMD        | FCH SD Flash Controller      | 43    | sdhci_pci  | 2C903F36D0 |
| 1180:e822 | 104d:9071 | Ricoh      | MMC/SD Host Controller       | 39    | sdhci_pci  | 3C5767E938 |
| 14e4:16bc | 14e4:0000 | Broadco... | BCM57765/57785 SDXC/MMC C... | 36    | sdhci_pci  | 16BDB52C40 |
| 8086:9d2d | 8086:9d2d | Intel      | Sunrise Point-LP Secure D... | 32    | sdhci_pci  | B6B40DE397 |
| 1524:0550 | 1025:0090 | ENE Tec... | ENE PCI Secure Digital Ca... | 31    | sdhci_pci  | 719BE91D02 |
| 1180:0822 | 1028:0233 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 30    | sdhci_pci  | 1F49A84F1F |
| 1217:8221 | 1028:0493 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 28    | sdhci_pci  | CA6EFEBBD7 |
| 1180:0822 | 103c:30cc | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 27    | sdhci_pci  | 9EDE738BFC |
| 197b:2391 | 103c:17f6 | JMicron... | Standard SD Host Controller  | 27    | sdhci_pci  | AB69AA73CD |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | sdhci_pci  | 1579402536 |
| 10ec:5209 | 10ec:5209 | Realtek... | RTS5209 PCI Express Card ... | 26    | sdhci_pci  | DE168F8DCC |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 25    | sdhci_pci  | 1579402536 |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 24    | sdhci_pci  | 1579402536 |
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
| 104c:803c | 1179:ff10 | Texas I... | PCIxx12 SDA Standard Comp... | 15    | sdhci_pci  | 4FFE571137 |
| 1180:0822 | 103c:7008 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 15    | sdhci_pci  | AB17752168 |
| 1180:0822 | 1043:1877 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 15    | sdhci_pci  | CB27B32040 |
| 1180:0822 | 1043:1897 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 15    | sdhci_pci  | 96E310C22E |
| 14e4:16bc | 1025:0605 | Broadco... | BCM57765/57785 SDXC/MMC C... | 15    | sdhci_pci  | 4BBB490EBC |
| 197b:2381 | 103c:3628 | JMicron... | Standard SD Host Controller  | 15    | sdhci_pci  | E09686C315 |
| 197b:2381 | 17aa:212d | JMicron... | Standard SD Host Controller  | 15    | sdhci_pci  | 2AFD83B0D3 |
| 197b:2391 | 103c:161c | JMicron... | Standard SD Host Controller  | 15    | sdhci_pci  | 6AE9888758 |
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
| 8086:9d2b | 8086:7270 | Intel      | Skylake-U/Y SCC: eMMC        | 10    | sdhci_pci  | 8EB32C768B |
| 8086:9d2d | 8086:7270 | Intel      | Sunrise Point-LP Secure D... | 10    | sdhci_pci  | 8EB32C768B |
| 1022:7806 | 1043:14b7 | AMD        | FCH SD Flash Controller      | 9     | sdhci_pci  | 6C12E2EE00 |
| 1022:7813 | 103c:80cc | AMD        | FCH SD Flash Controller      | 9     | sdhci_pci  | 2EC22FA87A |
| 104c:803c | 1179:0001 | Texas I... | PCIxx12 SDA Standard Comp... | 9     | sdhci_pci  | 3E0ED41BC7 |
| 1180:0822 | 103c:30bb | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 9     | sdhci_pci  | FB7F51216E |
| 1217:8221 | 1028:0532 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 9     | sdhci_pci  | 963D3EBFE9 |
| 1217:8221 | 1028:0535 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 9     | sdhci_pci  | 95A631AAE1 |
| 1217:8520 | 1028:05ca | O2 Micro   | SD/MMC Card Reader Contro... | 9     | sdhci_pci  | CA9C198099 |
| 1217:8520 | 1028:05de | O2 Micro   | SD/MMC Card Reader Contro... | 9     | sdhci_pci  | F40C3D18FB |
| 197b:2381 | 103c:30f4 | JMicron... | Standard SD Host Controller  | 9     | sdhci_pci  | DDA054B15D |
| 1022:7813 | 1025:0865 | AMD        | FCH SD Flash Controller      | 8     | sdhci_pci  | B8D1E63435 |
| 1022:7813 | 1025:108a | AMD        | FCH SD Flash Controller      | 8     | sdhci_pci  | 15AB2F9B58 |
| 1022:7813 | 103c:81f5 | AMD        | FCH SD Flash Controller      | 8     | sdhci_pci  | 2043A9B3C9 |
| 1022:7813 | 1043:148d | AMD        | FCH SD Flash Controller      | 8     | sdhci_pci  | 7C8E8CFB76 |
| 1180:0822 | 1028:022a | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 8     | sdhci_pci  | 77649E9A5A |
| 1180:0822 | 1028:023a | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 8     | sdhci_pci  | 2B5F0594D3 |
| 1180:0822 | 103c:172a | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 8     | sdhci_pci  | E2C04796A0 |
| 1180:0822 | 103c:30db | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 8     | sdhci_pci  | 9792924118 |
| 1180:0822 | 1043:1017 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 8     | sdhci_pci  | 7A5FBF55AD |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a324 | 8086:7270 | Intel      | Cannon Lake PCH SPI Contr... | 22    |            | 383A34EDD1 |
| 8086:9da4 | 8086:7270 | Intel      | Cannon Point-LP SPI Contr... | 13    |            | EA12327BDD |
| 8086:a324 | 1028:087c | Intel      | Cannon Lake PCH SPI Contr... | 12    |            | 7A9639F003 |
| 8086:a368 | 1028:087c | Intel      | Cannon Lake PCH Serial IO... | 12    | intel_l... | 7A9639F003 |
| 8086:a369 | 1028:087c | Intel      | Cannon Lake PCH Serial IO... | 12    | intel_l... | 7A9639F003 |
| 8086:a324 | 1025:1264 | Intel      | Cannon Lake PCH SPI Contr... | 10    |            | F3941C8871 |
| 8086:a32a | 1043:1e40 | Intel      | 300 Series Chipset Device    | 10    | intel_lpss | BBAF5C143F |
| 8086:a368 | 1025:1264 | Intel      | Cannon Lake PCH Serial IO... | 10    | intel_lpss | F3941C8871 |
| 8086:a369 | 1025:1264 | Intel      | Cannon Lake PCH Serial IO... | 10    | intel_lpss | F3941C8871 |
| 8086:a324 | 1028:087d | Intel      | Cannon Lake PCH SPI Contr... | 9     |            | 75F82151FF |
| 8086:a368 | 1028:087d | Intel      | Cannon Lake PCH Serial IO... | 9     | intel_l... | 75F82151FF |
| 8086:a369 | 1028:087d | Intel      | Cannon Lake PCH Serial IO... | 9     | intel_l... | 75F82151FF |
| 8086:9ce6 | 8086:9ce6 | Intel      | Wildcat Point-LP Serial I... | 8     | spi_pxa... | 5515E7AA30 |
| 8086:9da4 | 1028:08af | Intel      | Cannon Point-LP SPI Contr... | 8     |            | D4A2D02674 |
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
| 8086:a324 | 1028:0825 | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | 75BA2F8829 |
| 8086:a324 | 1028:0831 | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | F72215BFC0 |
| 8086:a324 | 103c:84da | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | A8DE86DAD5 |
| 8086:a324 | 1462:1219 | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | A1D0BDB94B |
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
| 8086:5ac8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | pwm_lps... | FAE06BB10F |
| 8086:9da4 | 17aa:5072 | Intel      | Cannon Point-LP SPI Contr... | 3     |            | DA7C2876D3 |
| 8086:a324 | 1028:0870 | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | 8ACE47254A |
| 8086:a324 | 1028:0877 | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | 8B270D4228 |
| 8086:a324 | 103c:8478 | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | AD2AA3B388 |
| 8086:a324 | 1043:10c1 | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | C1EDFCFA1C |
| 8086:a324 | 1558:8555 | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | 6ACA3CA73D |
| 8086:a324 | 1558:95e6 | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | 94C3F1BC72 |
| 8086:a368 | 1028:0870 | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | 8ACE47254A |
| 8086:a368 | 1028:0877 | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | 8B270D4228 |
| 8086:a368 | 1043:10c1 | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | C1EDFCFA1C |
| 8086:a368 | 1558:95e6 | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | 94C3F1BC72 |
| 8086:a369 | 1028:0870 | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | 8ACE47254A |
| 8086:a369 | 1558:95e6 | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | 94C3F1BC72 |
| 10de:1adb |           | Nvidia     | TU106 USB Type-C Port Pol... | 2     | nvidia_gpu | 3A4D90A1C3 |
| 10de:1adb | 1028:0000 | Nvidia     | TU106 USB Type-C Port Pol... | 2     | nvidia_gpu | AACC137FAA |
| 10de:1adb | 10de:0000 | Nvidia     | TU106 USB Type-C Port Pol... | 2     |            | 087A8F3344 |
| 8086:9c61 | 1025:0a11 | Intel      | 8 Series I2C Controller #0   | 2     | i2c_des... | F304E3BA6B |
| 8086:9c62 | 1025:0a11 | Intel      | 8 Series I2C Controller #1   | 2     | i2c_des... | F304E3BA6B |
| 8086:9da4 | 1025:128d | Intel      | Cannon Point-LP SPI Contr... | 2     |            | 517CAD6069 |
| 8086:9da4 | 1028:089c | Intel      | Cannon Point-LP SPI Contr... | 2     |            | 1E82DEB58E |
| 8086:9da4 | 1028:08c9 | Intel      | Cannon Point-LP SPI Contr... | 2     |            | 6694F62BE3 |
| 8086:9da4 | 19e5:3e09 | Intel      | Cannon Point-LP SPI Contr... | 2     |            | 87EF40FDD4 |
| 8086:9daa | 1043:1461 | Intel      | 8th Gen Intel Core Proces... | 2     | intel_lpss | 0FCCED0386 |
| 8086:9dab | 19e5:3e09 | Intel      | 8th Gen Intel Core Proces... | 2     | intel_l... | 87EF40FDD4 |
| 8086:9dc5 | 1028:08c9 | Intel      | 8th Gen Intel Core Proces... | 2     | intel_l... | 6694F62BE3 |
| 8086:9de8 | 1025:128d | Intel      | Cannon Point-LP Serial IO... | 2     | intel_lpss | 517CAD6069 |
| 8086:9de8 | 1028:089c | Intel      | Cannon Point-LP Serial IO... | 2     | intel_l... | 1E82DEB58E |
| 8086:9de8 | 1028:08c9 | Intel      | Cannon Point-LP Serial IO... | 2     | intel_l... | 6694F62BE3 |
| 8086:9de8 | 1043:1461 | Intel      | Cannon Point-LP Serial IO... | 2     | intel_lpss | 0FCCED0386 |
| 8086:9de8 | 19e5:3e09 | Intel      | Cannon Point-LP Serial IO... | 2     | intel_l... | 87EF40FDD4 |
| 8086:9de9 | 1025:128d | Intel      | Cannon Point-LP Serial IO... | 2     | intel_lpss | 517CAD6069 |
| 8086:9de9 | 1028:089c | Intel      | Cannon Point-LP Serial IO... | 2     | intel_l... | 1E82DEB58E |
| 8086:9de9 | 1028:08c9 | Intel      | Cannon Point-LP Serial IO... | 2     | intel_l... | 6694F62BE3 |
| 8086:9de9 | 1043:1461 | Intel      | Cannon Point-LP Serial IO... | 2     | intel_lpss | 0FCCED0386 |
| 8086:9de9 | 19e5:3e09 | Intel      | Cannon Point-LP Serial IO... | 2     | intel_l... | 87EF40FDD4 |
| 8086:a324 | 1025:125e | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 291836CDCE |
| 8086:a324 | 1028:0824 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 7872901FE9 |
| 8086:a324 | 1028:0885 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 59EAF9F30E |
| 8086:a324 | 1028:08a1 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | AACC137FAA |
| 8086:a324 | 103c:84db | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 71A27E6106 |
| 8086:a324 | 103c:84e9 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 049AF97B03 |
| 8086:a324 | 1043:1041 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 328975F3A5 |
| 8086:a324 | 1462:1214 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | DD39CC35AF |
| 8086:a324 | 1462:1215 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | A78D2DC653 |
| 8086:a324 | 1462:1223 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 3DF62034D2 |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2a47 | 17aa:20ec | Intel      | Mobile 4 Series Chipset A... | 34    | serial     | FDAB3CF92F |
| 8086:3b67 | 17aa:2162 | Intel      | 5 Series/3400 Series Chip... | 32    | serial     | DA5E944C6C |
| 8086:1c3d | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 28    | serial     | FBF8462F41 |
| 8086:1e3d | 17aa:21f3 | Intel      | 7 Series/C210 Series Chip... | 19    | serial     | 4D1B987AAC |
| 8086:1e3d | 17aa:21f6 | Intel      | 7 Series/C210 Series Chip... | 17    | serial     | C087621D89 |
| 8086:1e3d | 17aa:21fa | Intel      | 7 Series/C210 Series Chip... | 16    | serial     | C9FFBA0281 |
| 8086:1e3d | 103c:179b | Intel      | 7 Series/C210 Series Chip... | 13    | serial     | 707703A569 |
| 8086:1c3d | 103c:161c | Intel      | 6 Series/C200 Series Chip... | 12    | serial     | A00C60042E |
| 8086:9c3d | 17aa:220c | Intel      | 8 Series HECI KT             | 11    | serial     | 7637F3DE5F |
| 8086:3b67 | 103c:7007 | Intel      | 5 Series/3400 Series Chip... | 10    | serial     | FE89EA62D2 |
| 8086:1c3d | 103c:162b | Intel      | 6 Series/C200 Series Chip... | 9     | serial     | FAF97CF550 |
| 8086:8c3d | 1028:05be | Intel      | 8 Series/C220 Series Chip... | 9     | serial     | 54B56F30BA |
| 8086:9c3d | 103c:198f | Intel      | 8 Series HECI KT             | 9     | serial     | DCE9CDAF8E |
| 8086:1c3d | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 8     | serial     | 9306CAC54C |
| 8086:1c3d | 17aa:21d2 | Intel      | 6 Series/C200 Series Chip... | 8     | serial     | 97E66DDFC9 |
| 8086:1c3d | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 8     | serial     | E8A5C28644 |
| 8086:3b67 | 103c:7008 | Intel      | 5 Series/3400 Series Chip... | 8     | serial     | B5409A9615 |
| 8086:1c3d | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 7     | serial     | 8C536BE4D8 |
| 8086:3b67 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 7     | serial     | 8978395722 |
| 8086:9d3d | 103c:8079 | Intel      | Sunrise Point-LP Active M... | 7     | serial     | B8392B7335 |
| 8086:1c3d | 1028:0494 | Intel      | 6 Series/C200 Series Chip... | 6     | serial     | A217BF3485 |
| 8086:3b67 | 1028:040b | Intel      | 5 Series/3400 Series Chip... | 6     | serial     | A9143BEECD |
| 8086:3b67 | 103c:172a | Intel      | 5 Series/3400 Series Chip... | 6     | serial     | E2C04796A0 |
| 8086:8c3d | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 6     | serial     | 364B159B80 |
| 8086:1c3d | 1028:04a3 | Intel      | 6 Series/C200 Series Chip... | 5     | serial     | 19E1CA5871 |
| 8086:1c3d | 103c:1618 | Intel      | 6 Series/C200 Series Chip... | 5     | serial     | 7D1AE28E6D |
| 8086:1e3d | 1028:0534 | Intel      | 7 Series/C210 Series Chip... | 5     | serial     | C8334C6A31 |
| 8086:1e3d | 17aa:21fb | Intel      | 7 Series/C210 Series Chip... | 5     | serial     | 2CA24B0A50 |
| 8086:2a07 | 17aa:20d4 | Intel      | Mobile PM965/GM965 KT Con... | 5     | serial     | 037CAC7A3D |
| 8086:2a47 | 103c:30e7 | Intel      | Mobile 4 Series Chipset A... | 5     | serial     | E05FE6B4AB |
| 8086:3b67 | 10cf:152f | Intel      | 5 Series/3400 Series Chip... | 5     | serial     | 177FE65920 |
| 8086:1c3d | 1179:0001 | Intel      | 6 Series/C200 Series Chip... | 4     | serial     | 4398E73607 |
| 8086:1e3d | 103c:17a7 | Intel      | 7 Series/C210 Series Chip... | 4     | serial     | AE6CF1B3CA |
| 8086:1e3d | 103c:18df | Intel      | 7 Series/C210 Series Chip... | 4     | serial     | 4D5087B262 |
| 8086:1e3d | 10cf:16ed | Intel      | 7 Series/C210 Series Chip... | 4     | serial     | B7F6E1F635 |
| 8086:1e3d | 17aa:21f9 | Intel      | 7 Series/C210 Series Chip... | 4     | serial     | DF1FD87B87 |
| 8086:1e3d | 17aa:2203 | Intel      | 7 Series/C210 Series Chip... | 4     | serial     | D06826DB64 |
| 8086:2a07 | 103c:30c5 | Intel      | Mobile PM965/GM965 KT Con... | 4     | serial     | AB3B50FF87 |
| 8086:3b67 | 103c:1520 | Intel      | 5 Series/3400 Series Chip... | 4     | serial     | 5BC72880EA |
| 8086:3b67 | 103c:172b | Intel      | 5 Series/3400 Series Chip... | 4     | serial     | 35E3CAB7FD |
| 8086:8c3d | 10cf:17e0 | Intel      | 8 Series/C220 Series Chip... | 4     | serial     | 491E66B3D8 |
| 8086:9c3d | 1028:05ca | Intel      | 8 Series HECI KT             | 4     | serial     | C0C75EF0DF |
| 8086:9c3d | 1028:05cb | Intel      | 8 Series HECI KT             | 4     | serial     | 613D54A9CE |
| 8086:9c3d | 103c:1991 | Intel      | 8 Series HECI KT             | 4     | serial     | 475A1011AB |
| 8086:9c3d | 17aa:2218 | Intel      | 8 Series HECI KT             | 4     | serial     | B19667D81D |
| 8086:9d3d | 1028:06dc | Intel      | Sunrise Point-LP Active M... | 4     | serial     | 90E9F8DFAD |
| 8086:a13d | 17aa:222e | Intel      | 100 Series/C230 Series Ch... | 4     | serial     | 6F5CF8EFB9 |
| 8086:1c3d | 1028:0492 | Intel      | 6 Series/C200 Series Chip... | 3     | serial     | 9C07EE4C86 |
| 8086:1c3d | 1028:04a4 | Intel      | 6 Series/C200 Series Chip... | 3     | serial     | 370EF78297 |
| 8086:1c3d | 103c:162a | Intel      | 6 Series/C200 Series Chip... | 3     | serial     | 19BF4CEBAD |
| 8086:1c3d | 17aa:21db | Intel      | 6 Series/C200 Series Chip... | 3     | serial     | 659C24D76A |
| 8086:2a07 | 103c:30be | Intel      | Mobile PM965/GM965 KT Con... | 3     | serial     | 803A20E4AA |
| 8086:2a07 | 103c:30c3 | Intel      | Mobile PM965/GM965 KT Con... | 3     | serial     | 1614D64C28 |
| 8086:2a47 | 103c:30db | Intel      | Mobile 4 Series Chipset A... | 3     | serial     | C949572837 |
| 8086:2a47 | 103c:30dc | Intel      | Mobile 4 Series Chipset A... | 3     | serial     | E073E6B98E |
| 8086:2a47 | 1734:1147 | Intel      | Mobile 4 Series Chipset A... | 3     | serial     | 418C3E7B73 |
| 8086:3b67 | 103c:1521 | Intel      | 5 Series/3400 Series Chip... | 3     | serial     | 0C321D2B22 |
| 8086:9c3d | 1028:05de | Intel      | 8 Series HECI KT             | 3     | serial     | C50DF1C2F3 |
| 8086:9d3d | 17aa:2233 | Intel      | Sunrise Point-LP Active M... | 3     | serial     | 78932B3C9B |
| 8086:9d3d | 17aa:504a | Intel      | Sunrise Point-LP Active M... | 3     | serial     | C61C8F1ABC |
| 8086:9d3d | 17aa:5053 | Intel      | Sunrise Point-LP Active M... | 3     | serial     | B8645E850C |
| 8086:a363 | 17aa:2267 | Intel      | Cannon Lake PCH Active Ma... | 3     | serial     | 444D60D6DA |
| 8086:1c3d | 103c:1631 | Intel      | 6 Series/C200 Series Chip... | 2     | serial     | 22661D8917 |
| 8086:1c3d | 10cf:1614 | Intel      | 6 Series/C200 Series Chip... | 2     | serial     | CC992BCBBD |
| 8086:1e3d | 1028:0535 | Intel      | 7 Series/C210 Series Chip... | 2     | serial     | 845089C5AC |
| 8086:1e3d | 1028:0549 | Intel      | 7 Series/C210 Series Chip... | 2     | serial     | 6136663F73 |
| 8086:1e3d | 103c:176b | Intel      | 7 Series/C210 Series Chip... | 2     | serial     | 46EA3231EB |
| 8086:1e3d | 103c:176c | Intel      | 7 Series/C210 Series Chip... | 2     | serial     | EA9A7CC6F1 |
| 8086:1e3d | 103c:17df | Intel      | 7 Series/C210 Series Chip... | 2     | serial     | 79EFD09885 |
| 8086:1e3d | 103c:18f8 | Intel      | 7 Series/C210 Series Chip... | 2     | serial     | D16CE79DB7 |
| 8086:2a07 | 103c:30c1 | Intel      | Mobile PM965/GM965 KT Con... | 2     | serial     | D608971413 |
| 8086:2a07 | 17aa:20d0 | Intel      | Mobile PM965/GM965 KT Con... | 2     | serial     | 7F41843359 |
| 8086:2a47 | 1028:024d | Intel      | Mobile 4 Series Chipset A... | 2     | serial     | 8B31B50BCA |
| 8086:2a47 | 1028:024f | Intel      | Mobile 4 Series Chipset A... | 2     | serial     | 2B1EF8244A |
| 8086:2a47 | 103c:30e1 | Intel      | Mobile 4 Series Chipset A... | 2     | serial     | B2E125B932 |
| 8086:2a47 | 103c:30eb | Intel      | Mobile 4 Series Chipset A... | 2     | serial     | BEF5665070 |
| 8086:8c3d | 1028:05bd | Intel      | 8 Series/C220 Series Chip... | 2     | serial     | 73CA2A6E27 |
| 8086:8c3d | 103c:1909 | Intel      | 8 Series/C220 Series Chip... | 2     | serial     | 4DADC69EFA |
| 8086:8c3d | 103c:190a | Intel      | 8 Series/C220 Series Chip... | 2     | serial     | 561770352F |
| 8086:9c3d | 10cf:183b | Intel      | 8 Series HECI KT             | 2     | serial     | 734FCAFBD7 |
| 8086:9c3d | 17aa:2214 | Intel      | 8 Series HECI KT             | 2     | serial     | ACFF59197D |
| 8086:9d3d | 1028:06df | Intel      | Sunrise Point-LP Active M... | 2     | serial     | 1ED6532125 |
| 8086:9d3d | 1028:081a | Intel      | Sunrise Point-LP Active M... | 2     | serial     | 3E31BE830B |
| 8086:9d3d | 1028:081c | Intel      | Sunrise Point-LP Active M... | 2     | serial     | 2E9A3BAB26 |
| 8086:9d3d | 17aa:2245 | Intel      | Sunrise Point-LP Active M... | 2     | serial     | C731CA9F7F |
| 8086:9d3d | 17aa:225c | Intel      | Sunrise Point-LP Active M... | 2     | serial     | 1F6532F9A7 |
| 8086:a13d | 1028:07b1 | Intel      | 100 Series/C230 Series Ch... | 2     | serial     | 1675040CCD |
| 8086:a363 | 8086:7270 | Intel      | Cannon Lake PCH Active Ma... | 2     | serial     | CD4CAE5343 |
| 8086:a37c | 1028:08a1 | Intel      | VROC Virtual Controller      | 2     | intel_i... | AACC137FAA |
| 10ec:816a | 103c:83da | Realtek... | Virtual COM1                 | 1     |            | 607DEE6BBB |
| 10ec:816a | 103c:8401 | Realtek... | Virtual COM1                 | 1     |            | F2F88AAA9D |
| 10ec:816a | 17aa:511f | Realtek... | Virtual COM1                 | 1     |            | 259A32BE33 |
| 10ec:816a | 17aa:5122 | Realtek... | Virtual COM1                 | 1     |            | 7CCAC31D71 |
| 10ec:816a | 17aa:5125 | Realtek... | Virtual COM1                 | 1     |            | 7A1C4A299D |
| 10ec:816b | 103c:83da | Realtek... | RealManage COM2              | 1     |            | 607DEE6BBB |
| 10ec:816b | 103c:8401 | Realtek... | RealManage COM2              | 1     |            | F2F88AAA9D |
| 10ec:816b | 17aa:511f | Realtek... | RealManage COM2              | 1     |            | 259A32BE33 |
| 10ec:816b | 17aa:5122 | Realtek... | RealManage COM2              | 1     |            | 7CCAC31D71 |
| 10ec:816b | 17aa:5125 | Realtek... | RealManage COM2              | 1     |            | 7A1C4A299D |
| 1415:9504 | 1415:0000 | Oxford ... | AAEON OX16PCI954 PCI UART... | 1     | serial     | C8B31C9D99 |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3b32 | 17aa:2190 | Intel      | 5 Series/3400 Series Chip... | 67    | intel_ips  | DA5E944C6C |
| 8086:9d27 | 1043:1d2d | Intel      | Sunrise Point-LP Serial I... | 58    | intel_lpss | B6B40DE397 |
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 57    | process... | 9E88CD9DFE |
| 8086:3b32 | 17aa:38c0 | Intel      | 5 Series/3400 Series Chip... | 55    | intel_ips  | 62697BF35B |
| 8086:2932 | 17aa:3a1f | Intel      | 82801I (ICH9 Family) Ther... | 46    |            | 601D53F9EB |
| 8086:9d29 | 1043:1d2d | Intel      | Sunrise Point-LP Serial I... | 46    | intel_lpss | B6B40DE397 |
| 8086:3b32 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 43    | intel_ips  | D023F50697 |
| 8086:0a03 | 8086:2010 | Intel      | Haswell-ULT Thermal Subsy... | 41    | process... | 8D5390FEAE |
| 8086:3b32 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 40    | intel_ips  | DA7D4E2098 |
| 8086:22dc | 7270:8086 | Intel      | Atom/Celeron/Pentium Proc... | 36    | process... | 4414412FCB |
| 8086:5a8c | 1043:16a0 | Intel      | Dynamic Platform and Ther... | 32    | proc_th... | 0FAD7AC4EB |
| 8086:5aac | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 32    | intel_lpss | 0FAD7AC4EB |
| 8086:5ab4 | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 32    | intel_lpss | 0FAD7AC4EB |
| 8086:5a8c |           | Intel      | Dynamic Platform and Ther... | 31    | process... | 1579402536 |
| 8086:0a03 | 1043:131d | Intel      | Haswell-ULT Thermal Subsy... | 30    | process... | FDD61F096B |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 28    | intel_l... | 1579402536 |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 28    | intel_l... | 1579402536 |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 28    | intel_l... | 1579402536 |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 28    | intel_l... | 1579402536 |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 28    | intel_l... | 1579402536 |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 28    | intel_l... | 1579402536 |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 28    | intel_l... | 1579402536 |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 28    | intel_l... | 1579402536 |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 28    | intel_l... | 1579402536 |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 28    | intel_l... | 1579402536 |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 28    | intel_l... | 1579402536 |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 28    | intel_l... | 1579402536 |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 28    | intel_l... | 1579402536 |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 28    | intel_l... | 1579402536 |
| 8086:9c24 | 1043:131d | Intel      | 8 Series Thermal             | 28    | intel_p... | 761A86BDC8 |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 26    | intel_l... | 1579402536 |
| 8086:9d60 | 1025:1193 | Intel      | Sunrise Point-LP Serial I... | 26    | intel_lpss | 141D7917FF |
| 8086:9d61 | 1025:1193 | Intel      | Sunrise Point-LP Serial I... | 26    | intel_lpss | 141D7917FF |
| 8086:0153 | 1043:1587 | Intel      | 3rd Gen Core Processor Th... | 25    |            | 469E04E0D5 |
| 8086:3b32 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 24    | intel_ips  | 3C5767E938 |
| 8086:9c24 | 1043:16cd | Intel      | 8 Series Thermal             | 24    | intel_p... | FDD61F096B |
| 8086:9d60 | 1025:1085 | Intel      | Sunrise Point-LP Serial I... | 23    | intel_l... | AE1CE65D11 |
| 8086:9d61 | 1025:1085 | Intel      | Sunrise Point-LP Serial I... | 23    | intel_l... | AE1CE65D11 |
| 8086:0a03 | 1043:16cd | Intel      | Haswell-ULT Thermal Subsy... | 22    | process... | 2A224752BA |
| 8086:22dc | 1043:10c0 | Intel      | Atom/Celeron/Pentium Proc... | 22    | process... | F8FDA4EFC3 |
| 8086:3b32 | 144d:c581 | Intel      | 5 Series/3400 Series Chip... | 21    | intel_ips  | 4B260556B7 |
| 8086:9d31 | 1025:115f | Intel      | Sunrise Point-LP Thermal ... | 21    | intel_p... | E4B342382F |
| 8086:9d60 | 1025:115f | Intel      | Sunrise Point-LP Serial I... | 21    | intel_l... | E4B342382F |
| 8086:3b32 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 20    | intel_ips  | D588CD38C2 |
| 8086:3b32 | 10cf:1526 | Intel      | 5 Series/3400 Series Chip... | 20    | intel_ips  | EEFC712947 |
| 8086:9d31 | 17aa:380e | Intel      | Sunrise Point-LP Thermal ... | 20    | intel_p... | 005771EDFD |
| 8086:1903 | 103c:832a | Intel      | Xeon E3-1200 v5/E3-1500 v... | 18    | process... | 8B699D7E6C |
| 8086:9d31 | 103c:832a | Intel      | Sunrise Point-LP Thermal ... | 18    | intel_p... | 8B699D7E6C |
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
| 8086:1603 | 1043:1a6d | Intel      | Broadwell-U Processor The... | 15    | process... | 5919CA05FE |
| 8086:2932 | 103c:3628 | Intel      | 82801I (ICH9 Family) Ther... | 15    |            | E09686C315 |
| 8086:3b32 | 103c:7008 | Intel      | 5 Series/3400 Series Chip... | 15    | intel_ips  | AB17752168 |
| 8086:9ca4 | 1043:1a6d | Intel      | Wildcat Point-LP Thermal ... | 15    | intel_p... | 5919CA05FE |
| 8086:9d31 | 103c:8079 | Intel      | Sunrise Point-LP Thermal ... | 15    | intel_p... | B8392B7335 |
| 8086:9d60 | 103c:8079 | Intel      | Sunrise Point-LP Serial I... | 15    | intel_l... | B8392B7335 |
| 8086:1903 | 1028:07e6 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 14    | process... | 5D2CB1E1B0 |
| 8086:3b32 | 144d:c06a | Intel      | 5 Series/3400 Series Chip... | 14    | intel_ips  | 86987CF1ED |
| 8086:9d31 | 1028:07e6 | Intel      | Sunrise Point-LP Thermal ... | 14    | intel_p... | 5D2CB1E1B0 |
| 8086:9d60 | 1028:07e6 | Intel      | Sunrise Point-LP Serial I... | 14    | intel_l... | 5D2CB1E1B0 |
| 8086:9d61 | 1028:07e6 | Intel      | Sunrise Point-LP Serial I... | 14    | intel_l... | 5D2CB1E1B0 |
| 8086:1903 | 1028:07be | Intel      | Xeon E3-1200 v5/E3-1500 v... | 13    | process... | CB9F8EC46D |
| 8086:2932 | 103c:1605 | Intel      | 82801I (ICH9 Family) Ther... | 13    |            | D3AFE1DB4A |
| 8086:5a8c | 1043:1de0 | Intel      | Dynamic Platform and Ther... | 13    | proc_th... | 8633F4E071 |
| 8086:5ab4 | 1043:1de0 | Intel      | Celeron N3350/Pentium N42... | 13    | intel_lpss | 8633F4E071 |
| 8086:9ca4 | 17aa:5034 | Intel      | Wildcat Point-LP Thermal ... | 13    | intel_p... | BA450606A3 |
| 8086:9d31 | 8086:7270 | Intel      | Sunrise Point-LP Thermal ... | 13    | intel_p... | 8EB32C768B |
| 8086:a131 | 1028:07be | Intel      | 100 Series/C230 Series Ch... | 13    | intel_p... | CB9F8EC46D |
| 8086:a160 | 1028:07be | Intel      | 100 Series/C230 Series Ch... | 13    | intel_l... | CB9F8EC46D |
| 8086:a161 | 1028:07be | Intel      | 100 Series/C230 Series Ch... | 13    | intel_l... | CB9F8EC46D |
| 8086:1603 | 1043:19ad | Intel      | Broadwell-U Processor The... | 12    | process... | 33775F7BA5 |
| 8086:1903 | 1028:087c | Intel      | Xeon E3-1200 v5/E3-1500 v... | 12    | process... | 7A9639F003 |
| 8086:1903 | 103c:84a6 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 12    | process... | 1A3504B63C |
| 8086:22dc | 1043:12e0 | Intel      | Atom/Celeron/Pentium Proc... | 12    | process... | 6458C4F07B |
| 8086:2932 | 103c:3603 | Intel      | 82801I (ICH9 Family) Ther... | 12    |            | 9CE29D0583 |
| 8086:3b32 | 1043:1f37 | Intel      | 5 Series/3400 Series Chip... | 12    | intel_ips  | B2218D3C9F |
| 8086:3b32 | 144d:c07f | Intel      | 5 Series/3400 Series Chip... | 12    | intel_ips  | 408D0B84F9 |
| 8086:9c24 | 1043:130d | Intel      | 8 Series Thermal             | 12    | intel_p... | 8D5390FEAE |
| 8086:9ca4 | 1043:19ad | Intel      | Wildcat Point-LP Thermal ... | 12    | intel_p... | 33775F7BA5 |
| 8086:9d27 | 1025:1085 | Intel      | Sunrise Point-LP Serial I... | 12    | intel_l... | 88BCBB545E |
| 8086:9d27 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 12    | intel_l... | 8EB32C768B |
| 8086:9d31 | 103c:84a6 | Intel      | Sunrise Point-LP Thermal ... | 12    | intel_p... | 1A3504B63C |
| 8086:9d31 | 17aa:3808 | Intel      | Sunrise Point-LP Thermal ... | 12    | intel_p... | 37E18B856C |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e22 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 262   | i2c_i801   | 891002E8F2 |
| 8086:1c22 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 164   | i2c_i801   | A7618091FB |
| 8086:27da | 1043:83ad | Intel      | NM10/ICH7 Family SMBus Co... | 119   | i2c_i801   | 6A0513EC8D |
| 1002:4385 |           | AMD        | SBx00 SMBus Controller       | 111   | i2c_pii... | F47F34752E |
| 8086:9c22 | 17aa:3978 | Intel      | 8 Series SMBus Controller    | 89    | i2c_i801   | AFD92BF265 |
| 8086:1c22 | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 80    | i2c_i801   | 6B25B8982D |
| 8086:1e22 | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 80    | i2c_i801   | F28D18F3E9 |
| 8086:3b30 | 17aa:2167 | Intel      | 5 Series/3400 Series Chip... | 75    | i2c_i801   | DA5E944C6C |
| 8086:3b30 | 17aa:38bf | Intel      | 5 Series/3400 Series Chip... | 75    | i2c_i801   | 62697BF35B |
| 8086:2930 | 17aa:20f9 | Intel      | 82801I (ICH9 Family) SMBu... | 73    | i2c_i801   | FDAB3CF92F |
| 8086:2930 | 17aa:3a1d | Intel      | 82801I (ICH9 Family) SMBu... | 73    | i2c_i801   | 601D53F9EB |
| 8086:8c22 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 72    | i2c_i801   | 262BB6B100 |
| 8086:1e22 | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 69    | i2c_i801   | CE3DDF28FC |
| 8086:1c22 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 65    | i2c_i801   | 8579BA1B16 |
| 8086:283e | 1025:011f | Intel      | 82801H (ICH8 Family) SMBu... | 64    | i2c_i801   | 7387D70AD5 |
| 8086:1e22 | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 63    | i2c_i801   | 6478022B75 |
| 8086:1e22 | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 62    | i2c_i801   | E67DFC255A |
| 8086:1e22 | 1043:124d | Intel      | 7 Series/C216 Chipset Fam... | 61    | i2c_i801   | 0F8CE4DCC0 |
| 8086:1c22 | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 60    | i2c_i801   | 826F5492EB |
| 8086:3b30 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 56    | i2c_i801   | D023F50697 |
| 8086:0f12 | 17aa:3905 | Intel      | Atom Processor E3800 Seri... | 54    | i2c_i801   | CC7193A7B9 |
| 8086:27da | 1025:0349 | Intel      | NM10/ICH7 Family SMBus Co... | 51    | i2c_i801   | 8CE41DB531 |
| 8086:3b30 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 51    | i2c_i801   | 52035C5F01 |
| 8086:283e | 17aa:20a9 | Intel      | 82801H (ICH8 Family) SMBu... | 47    | i2c_i801   | 7F41843359 |
| 8086:1e22 | 1043:14c7 | Intel      | 7 Series/C216 Chipset Fam... | 46    | i2c_i801   | 9A401175B3 |
| 8086:1e22 | 17aa:5011 | Intel      | 7 Series/C216 Chipset Fam... | 46    | i2c_i801   | 65D329A2C6 |
| 1022:780b | 17aa:3801 | AMD        | FCH SMBus Controller         | 44    | i2c_piix4  | 760B445B08 |
| 8086:1c22 | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 44    | i2c_i801   | EE56C112BB |
| 8086:1c22 | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 43    | i2c_i801   | EA07B48EB4 |
| 8086:1c22 | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 41    | i2c_i801   | C0868A2B0C |
| 1022:780b | 144d:c0da | AMD        | FCH SMBus Controller         | 40    | i2c_piix4  | A06125BD54 |
| 8086:1e22 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 39    | i2c_i801   | 39CA2BE7BB |
| 8086:3b30 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 39    | i2c_i801   | 3C5767E938 |
| 8086:1c22 | 144d:c0b6 | Intel      | 6 Series/C200 Series Chip... | 38    | i2c_i801   | 616616B60F |
| 8086:1c22 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 35    | i2c_i801   | FBF8462F41 |
| 8086:9c22 | 1025:0866 | Intel      | 8 Series SMBus Controller    | 34    | i2c_i801   | 1C77D7A584 |
| 8086:0f12 | 17aa:3909 | Intel      | Atom Processor E3800 Seri... | 33    | i2c_i801   | EE1CFF7014 |
| 8086:2930 | 1025:0212 | Intel      | 82801I (ICH9 Family) SMBu... | 33    | i2c_i801   | 6029A4A18A |
| 8086:2930 | 144d:c06d | Intel      | 82801I (ICH9 Family) SMBu... | 33    | i2c_i801   | BC68546696 |
| 1002:4385 | 1002:4385 | AMD        | SBx00 SMBus Controller       | 32    | i2c_pii... | A84D413088 |
| 1002:4385 | 1043:104c | AMD        | SBx00 SMBus Controller       | 32    | i2c_pii... | 0051F69751 |
| 8086:27da | 1025:0090 | Intel      | NM10/ICH7 Family SMBus Co... | 32    | i2c_i801   | 719BE91D02 |
| 8086:5ad4 | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 32    | i2c_i801   | 0FAD7AC4EB |
| 1002:4385 | 103c:3577 | AMD        | SBx00 SMBus Controller       | 31    | i2c_pii... | 4201CDD966 |
| 8086:1e22 | 1043:1587 | Intel      | 7 Series/C216 Chipset Fam... | 31    | i2c_i801   | 469E04E0D5 |
| 8086:1e22 | 17aa:21f6 | Intel      | 7 Series/C216 Chipset Fam... | 31    | i2c_i801   | 7DA7A083D7 |
| 1002:4385 | 17aa:397b | AMD        | SBx00 SMBus Controller       | 30    | i2c_pii... | F9F3745636 |
| 8086:1e22 | 1179:fb31 | Intel      | 7 Series/C216 Chipset Fam... | 30    | i2c_i801   | 806B890CCF |
| 8086:1e22 | 144d:c652 | Intel      | 7 Series/C216 Chipset Fam... | 30    | i2c_i801   | A57B555F26 |
| 8086:1e22 | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 30    | i2c_i801   | 6D5F1234C2 |
| 8086:2930 | 1028:0233 | Intel      | 82801I (ICH9 Family) SMBu... | 30    | i2c_i801   | 1F49A84F1F |
| 1022:780b | 17aa:397c | AMD        | FCH SMBus Controller         | 29    | i2c_piix4  | E1D3B73A71 |
| 8086:0f12 | 1043:14dd | Intel      | Atom Processor E3800 Seri... | 29    | i2c_i801   | 8D51E5FEC5 |
| 8086:27da | 1025:0590 | Intel      | NM10/ICH7 Family SMBus Co... | 29    | i2c_i801   | D5A624C8FE |
| 8086:27da | 144d:c072 | Intel      | NM10/ICH7 Family SMBus Co... | 29    | i2c_i801   | 3A0FEA4700 |
| 8086:283e | 1028:01f9 | Intel      | 82801H (ICH8 Family) SMBu... | 29    | i2c_i801   | E5DE762918 |
| 8086:3b30 | 144d:c07f | Intel      | 5 Series/3400 Series Chip... | 29    | i2c_i801   | 408D0B84F9 |
| 8086:9c22 | 1025:0775 | Intel      | 8 Series SMBus Controller    | 29    | i2c_i801   | 3BD8AD186F |
| 1022:780b | 17aa:3802 | AMD        | FCH SMBus Controller         | 28    | i2c_piix4  | ACD1BCBBC4 |
| 8086:1c22 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 28    | i2c_i801   | CA6EFEBBD7 |
| 8086:1e22 | 1043:1477 | Intel      | 7 Series/C216 Chipset Fam... | 28    | i2c_i801   | C38728C67C |
| 8086:1e22 | 144d:c0d8 | Intel      | 7 Series/C216 Chipset Fam... | 28    | i2c_i801   | 0F042024B4 |
| 8086:3b30 | 144d:c581 | Intel      | 5 Series/3400 Series Chip... | 28    | i2c_i801   | 4B260556B7 |
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 28    | i2c_i801   | 1579402536 |
| 8086:9c22 | 1043:131d | Intel      | 8 Series SMBus Controller    | 28    | i2c_i801   | 761A86BDC8 |
| 1022:780b | 103c:184a | AMD        | FCH SMBus Controller         | 27    | i2c_piix4  | 0D67044A36 |
| 1022:790b | 103c:8330 | AMD        | FCH SMBus Controller         | 27    | i2c_pii... | D32B7275C3 |
| 8086:2292 | 1025:1012 | Intel      | Atom/Celeron/Pentium Proc... | 27    | i2c_i801   | 5A7F96289D |
| 8086:283e | 103c:30cc | Intel      | 82801H (ICH8 Family) SMBu... | 27    | i2c_i801   | 9EDE738BFC |
| 8086:9c22 | 1028:0651 | Intel      | 8 Series SMBus Controller    | 27    | i2c_i801   | 1E1FE2154B |
| 8086:0f12 | 1297:2041 | Intel      | Atom Processor E3800 Seri... | 26    | i2c_i801   | 100EB984CA |
| 8086:1e22 | 10cf:16e6 | Intel      | 7 Series/C216 Chipset Fam... | 26    | i2c_i801   | B9A4817612 |
| 8086:9d23 | 1025:1193 | Intel      | Sunrise Point-LP SMBus       | 26    | i2c_i801   | 141D7917FF |
| 8086:1c22 | 104d:908b | Intel      | 6 Series/C200 Series Chip... | 25    | i2c_i801   | 9B5D49431C |
| 8086:1e22 | 1025:0686 | Intel      | 7 Series/C216 Chipset Fam... | 25    | i2c_i801   | 29CFE1AD23 |
| 8086:1e22 | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 25    | i2c_i801   | DB9250D9E0 |
| 8086:2930 | 1025:013c | Intel      | 82801I (ICH9 Family) SMBu... | 24    | i2c_i801   | 77E3B20E26 |
| 8086:9c22 | 1043:16cd | Intel      | 8 Series SMBus Controller    | 24    | i2c_i801   | FDD61F096B |
| 1002:4372 | 1025:009f | AMD        | IXP SB4x0 SMBus Controller   | 23    | i2c_piix4  | A28F7B2623 |
| 1002:4385 | 1025:0489 | AMD        | SBx00 SMBus Controller       | 23    | i2c_pii... | E5D4CDDD0B |
| 8086:283e | 1025:0136 | Intel      | 82801H (ICH8 Family) SMBu... | 23    | i2c_i801   | 1EF9D813A6 |
| 8086:2930 | 144d:c059 | Intel      | 82801I (ICH9 Family) SMBu... | 23    | i2c_i801   | 79C2C53D26 |
| 8086:3b30 | 1025:036d | Intel      | 5 Series/3400 Series Chip... | 23    | i2c_i801   | 333F038ACE |
| 8086:9d23 | 1025:1085 | Intel      | Sunrise Point-LP SMBus       | 23    | i2c_i801   | AE1CE65D11 |
| 1002:4385 | 17aa:3936 | AMD        | SBx00 SMBus Controller       | 22    | i2c_pii... | 9F3EAD2DB7 |
| 1022:790b | 1025:1192 | AMD        | FCH SMBus Controller         | 22    | piix4_s... | 0D71E52A34 |
| 8086:0f12 | 103c:2213 | Intel      | Atom Processor E3800 Seri... | 22    | i2c_i801   | 964E06B446 |
| 8086:0f12 | 1043:161d | Intel      | Atom Processor E3800 Seri... | 22    | i2c_i801   | BDFF3A60F1 |
| 8086:1c22 | 1025:0511 | Intel      | 6 Series/C200 Series Chip... | 22    | i2c_i801   | F618F23CD4 |
| 8086:1c22 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 22    | i2c_i801   | 88B8816BFE |
| 8086:1e22 | 1025:0835 | Intel      | 7 Series/C216 Chipset Fam... | 22    | i2c_i801   | AB33DE8D3B |
| 8086:1e22 | 103c:1818 | Intel      | 7 Series/C216 Chipset Fam... | 22    | i2c_i801   | C865BDB72F |
| 8086:1e22 | 104d:90ab | Intel      | 7 Series/C216 Chipset Fam... | 22    | i2c_i801   | B56B7F6394 |
| 8086:1e22 | 104d:90b8 | Intel      | 7 Series/C216 Chipset Fam... | 22    | i2c_i801   | 66E469F722 |
| 8086:2292 | 1043:10c0 | Intel      | Atom/Celeron/Pentium Proc... | 22    | i2c_i801   | F8FDA4EFC3 |
| 8086:283e | 1025:011e | Intel      | 82801H (ICH8 Family) SMBu... | 22    | i2c_i801   | ED83D72FBE |
| 8086:3b30 | 144d:c06a | Intel      | 5 Series/3400 Series Chip... | 22    | i2c_i801   | 86987CF1ED |
| 1002:4385 | 1028:01f5 | AMD        | SBx00 SMBus Controller       | 21    | i2c_pii... | BFDE36E2F4 |
| 10de:0aa2 | 10de:cb79 | Nvidia     | MCP79 SMBus                  | 21    | i2c_nfo... | 9F753AC669 |
| 8086:283e | 1028:022f | Intel      | 82801H (ICH8 Family) SMBu... | 21    | i2c_i801   | 55CD396670 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e20 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 262   | snd_hda... | 891002E8F2 |
| 8086:1c20 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 164   | snd_hda... | A7618091FB |
| 8086:0c0c | 8086:2010 | Intel      | Xeon E3-1200 v3/4th Gen C... | 100   | snd_hda... | 2D1845C282 |
| 8086:0a0c | 17aa:3978 | Intel      | Haswell-ULT HD Audio Cont... | 89    | snd_hda... | AFD92BF265 |
| 8086:9c20 | 17aa:3978 | Intel      | 8 Series HD Audio Controller | 89    | snd_hda... | AFD92BF265 |
| 8086:1e20 | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 80    | snd_hda... | F28D18F3E9 |
| 8086:293e | 17aa:20f2 | Intel      | 82801I (ICH9 Family) HD A... | 79    | snd_hda... | FDAB3CF92F |
| 8086:3b56 | 17aa:38af | Intel      | 5 Series/3400 Series Chip... | 75    | snd_hda... | 62697BF35B |
| 8086:293e | 17aa:3a0d | Intel      | 82801I (ICH9 Family) HD A... | 74    | snd_hda... | 601D53F9EB |
| 8086:3b56 | 17aa:215e | Intel      | 5 Series/3400 Series Chip... | 72    | snd_hda... | DA5E944C6C |
| 8086:1e20 | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 69    | snd_hda... | CE3DDF28FC |
| 8086:1c20 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 65    | snd_hda... | 8579BA1B16 |
| 8086:284b | 1025:011f | Intel      | 82801H (ICH8 Family) HD A... | 64    | snd_hda... | 7387D70AD5 |
| 8086:1e20 | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 63    | snd_hda... | 6478022B75 |
| 8086:1e20 | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 62    | snd_hda... | E67DFC255A |
| 8086:27d8 | 1043:8437 | Intel      | NM10/ICH7 Family High Def... | 62    | snd_hda... | 595F2E7155 |
| 8086:1c20 | 1043:1ac3 | Intel      | 6 Series/C200 Series Chip... | 60    | snd_hda... | 826F5492EB |
| 8086:3b56 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 56    | snd_hda... | D023F50697 |
| 8086:0f04 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 54    | snd_hda... | CC7193A7B9 |
| 8086:0c0c | 17aa:3978 | Intel      | Xeon E3-1200 v3/4th Gen C... | 53    | snd_hda... | 262BB6B100 |
| 8086:8c20 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 53    | snd_hda... | 262BB6B100 |
| 8086:1e20 | 1043:118f | Intel      | 7 Series/C216 Chipset Fam... | 51    | snd_hda... | 0F8CE4DCC0 |
| 8086:27d8 | 1025:0349 | Intel      | NM10/ICH7 Family High Def... | 51    | snd_hda... | 8CE41DB531 |
| 8086:284b | 17aa:20ac | Intel      | 82801H (ICH8 Family) HD A... | 47    | snd_hda... | 7F41843359 |
| 8086:1e20 | 17aa:5011 | Intel      | 7 Series/C216 Chipset Fam... | 46    | snd_hda... | 65D329A2C6 |
| 8086:3b56 | 1043:1643 | Intel      | 5 Series/3400 Series Chip... | 46    | snd_hda... | 52035C5F01 |
| 1002:1714 | 1002:1714 | AMD        | BeaverCreek HDMI Audio [R... | 44    | snd_hda... | 04E7074682 |
| 1002:9840 | 17aa:3801 | AMD        | Kabini HDMI/DP Audio         | 44    | snd_hda... | 760B445B08 |
| 1022:780d | 17aa:3801 | AMD        | FCH Azalia Controller        | 44    | snd_hda... | 760B445B08 |
| 8086:1c20 | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 44    | snd_hda... | EE56C112BB |
| 8086:0a0c | 8086:2010 | Intel      | Haswell-ULT HD Audio Cont... | 43    | snd_hda... | F71E42FC3C |
| 8086:1c20 | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 43    | snd_hda... | EA07B48EB4 |
| 8086:27d8 | 1043:841c | Intel      | NM10/ICH7 Family High Def... | 43    | snd_hda... | 4ADFAB3C4E |
| 8086:293e | 1111:1043 | Intel      | 82801I (ICH9 Family) HD A... | 43    | snd_hda... | 38190AD2E1 |
| 8086:1c20 | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 41    | snd_hda... | C0868A2B0C |
| 8086:1c20 | 1043:1b43 | Intel      | 6 Series/C200 Series Chip... | 41    | snd_hda... | 6B25B8982D |
| 1002:4383 | 1043:1339 | AMD        | SBx00 Azalia (Intel HDA)     | 40    | snd_hda... | 54C92BF69C |
| 1002:9902 | 144d:c0da | AMD        | Trinity HDMI Audio Contro... | 40    | snd_hda... | A06125BD54 |
| 1022:780d | 144d:c0da | AMD        | FCH Azalia Controller        | 40    | snd_hda... | A06125BD54 |
| 10de:0bea |           | Nvidia     | GF108 High Definition Aud... | 39    | snd_hda... | C0868A2B0C |
| 8086:3b56 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 39    | snd_hda... | 3C5767E938 |
| 8086:1c20 | 144d:c0b6 | Intel      | 6 Series/C200 Series Chip... | 38    | snd_hda... | 616616B60F |
| 1002:aa68 | 1043:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 37    | snd_hda... | 52035C5F01 |
| 8086:27d8 | 1043:8516 | Intel      | NM10/ICH7 Family High Def... | 37    | snd_hda... | 6A0513EC8D |
| 8086:284b | 1043:1339 | Intel      | 82801H (ICH8 Family) HD A... | 36    | snd_hda... | FAECBEFA9B |
| 8086:1c20 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 35    | snd_hda... | FBF8462F41 |
| 1002:aa38 | 1002:aa38 | AMD        | RV710/730 HDMI Audio [Rad... | 34    | snd_hda... | 18D94651FD |
| 8086:0a0c | 1025:0866 | Intel      | Haswell-ULT HD Audio Cont... | 34    | snd_hda... | 1C77D7A584 |
| 8086:1e20 | 1043:1c33 | Intel      | 7 Series/C216 Chipset Fam... | 34    | snd_hda... | 9A401175B3 |
| 8086:0f04 | 17aa:3909 | Intel      | Atom Processor Z36xxx/Z37... | 33    | snd_hda... | EE1CFF7014 |
| 8086:293e | 1025:0212 | Intel      | 82801I (ICH9 Family) HD A... | 33    | snd_hda... | 6029A4A18A |
| 8086:293e | 144d:c06d | Intel      | 82801I (ICH9 Family) HD A... | 33    | snd_hda... | BC68546696 |
| 1002:1314 | 1043:104c | AMD        | Wrestler HDMI Audio          | 32    | snd_hda... | 0051F69751 |
| 1002:4383 | 1043:104c | AMD        | SBx00 Azalia (Intel HDA)     | 32    | snd_hda... | 0051F69751 |
| 8086:27d8 | 1025:0090 | Intel      | NM10/ICH7 Family High Def... | 32    | snd_hda... | 719BE91D02 |
| 8086:3b56 | 1043:13f3 | Intel      | 5 Series/3400 Series Chip... | 32    | snd_hda... | A6D13752DA |
| 8086:5a98 | 1043:12e0 | Intel      | Celeron N3350/Pentium N42... | 32    | snd_hda... | 0FAD7AC4EB |
| 1002:4383 | 103c:3577 | AMD        | SBx00 Azalia (Intel HDA)     | 31    | snd_hda... | 4201CDD966 |
| 8086:1e20 | 17aa:21f6 | Intel      | 7 Series/C216 Chipset Fam... | 31    | snd_hda... | 7DA7A083D7 |
| 1002:4383 | 17aa:397b | AMD        | SBx00 Azalia (Intel HDA)     | 30    | snd_hda... | F9F3745636 |
| 8086:1e20 | 144d:c652 | Intel      | 7 Series/C216 Chipset Fam... | 30    | snd_hda... | A57B555F26 |
| 8086:1e20 | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 30    | snd_hda... | 6D5F1234C2 |
| 8086:1e20 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 30    | snd_hda... | 16BDB52C40 |
| 8086:293e | 1028:0233 | Intel      | 82801I (ICH9 Family) HD A... | 30    | snd_hda... | 1F49A84F1F |
| 1002:9902 | 17aa:397c | AMD        | Trinity HDMI Audio Contro... | 29    | snd_hda... | E1D3B73A71 |
| 1022:780d | 17aa:397c | AMD        | FCH Azalia Controller        | 29    | snd_hda... | E1D3B73A71 |
| 8086:0a0c | 1025:0775 | Intel      | Haswell-ULT HD Audio Cont... | 29    | snd_hda... | 3BD8AD186F |
| 8086:0f04 | 1043:14dd | Intel      | Atom Processor Z36xxx/Z37... | 29    | snd_hda... | 8D51E5FEC5 |
| 8086:27d8 | 1025:0590 | Intel      | NM10/ICH7 Family High Def... | 29    | snd_hda... | D5A624C8FE |
| 8086:27d8 | 144d:c072 | Intel      | NM10/ICH7 Family High Def... | 29    | snd_hda... | 3A0FEA4700 |
| 8086:284b | 1028:01f9 | Intel      | 82801H (ICH8 Family) HD A... | 29    | snd_hda... | E5DE762918 |
| 8086:3b56 | 144d:c07f | Intel      | 5 Series/3400 Series Chip... | 29    | snd_hda... | 408D0B84F9 |
| 1022:780d | 17aa:3802 | AMD        | FCH Azalia Controller        | 28    | snd_hda... | ACD1BCBBC4 |
| 8086:0a0c | 1043:131d | Intel      | Haswell-ULT HD Audio Cont... | 28    | snd_hda... | 761A86BDC8 |
| 8086:1c20 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 28    | snd_hda... | CA6EFEBBD7 |
| 8086:1e20 | 144d:c0d8 | Intel      | 7 Series/C216 Chipset Fam... | 28    | snd_hda... | 0F042024B4 |
| 8086:3b56 | 144d:c581 | Intel      | 5 Series/3400 Series Chip... | 28    | snd_hda... | 4B260556B7 |
| 8086:9c20 | 1043:11af | Intel      | 8 Series HD Audio Controller | 28    | snd_hda... | 761A86BDC8 |
| 1002:15b3 | 103c:8330 | AMD        | High Definition Audio Con... | 27    | snd_hda... | D32B7275C3 |
| 1002:9840 | 17aa:3802 | AMD        | Kabini HDMI/DP Audio         | 27    | snd_hda... | 6420DFC899 |
| 1002:9902 | 103c:184a | AMD        | Trinity HDMI Audio Contro... | 27    | snd_hda... | 0D67044A36 |
| 1022:157a | 103c:8330 | AMD        | Family 15h (Models 60h-6f... | 27    | snd_hda... | D32B7275C3 |
| 1022:780d | 103c:184a | AMD        | FCH Azalia Controller        | 27    | snd_hda... | 0D67044A36 |
| 1039:7502 | 1043:1339 | Silicon... | Azalia Audio Controller      | 27    | snd_hda... | 9B7F075594 |
| 8086:0a0c | 1028:0651 | Intel      | Haswell-ULT HD Audio Cont... | 27    | snd_hda... | 1E1FE2154B |
| 8086:1c20 | 1043:1063 | Intel      | 6 Series/C200 Series Chip... | 27    | snd_hda... | F569FE2E74 |
| 8086:1e20 | 1043:1587 | Intel      | 7 Series/C216 Chipset Fam... | 27    | snd_hda... | 8B6978A8BF |
| 8086:2284 | 1025:1012 | Intel      | Atom/Celeron/Pentium Proc... | 27    | snd_hda... | 5A7F96289D |
| 8086:284b | 103c:30cc | Intel      | 82801H (ICH8 Family) HD A... | 27    | snd_hda... | 9EDE738BFC |
| 8086:9c20 | 1028:0651 | Intel      | 8 Series HD Audio Controller | 27    | snd_hda... | 1E1FE2154B |
| 8086:9ca0 | 1043:19ad | Intel      | Wildcat Point-LP High Def... | 27    | snd_hda... | 5919CA05FE |
| 8086:0f04 | 1297:2041 | Intel      | Atom Processor Z36xxx/Z37... | 26    | snd_hda... | 100EB984CA |
| 8086:1e20 | 10cf:1757 | Intel      | 7 Series/C216 Chipset Fam... | 26    | snd_hda... | B9A4817612 |
| 8086:9c20 | 1025:0775 | Intel      | 8 Series HD Audio Controller | 26    | snd_hda... | 3BD8AD186F |
| 8086:9d71 | 1025:1193 | Intel      | Sunrise Point-LP HD Audio    | 26    | snd_hda... | 141D7917FF |
| 1002:aa98 | 1043:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 25    | snd_hda... | EA07B48EB4 |
| 8086:1c20 | 104d:908b | Intel      | 6 Series/C200 Series Chip... | 25    | snd_hda... | 9B5D49431C |
| 8086:1e20 | 1025:0686 | Intel      | 7 Series/C216 Chipset Fam... | 25    | snd_hda... | 29CFE1AD23 |
| 8086:1e20 | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 25    | snd_hda... | DB9250D9E0 |
| 8086:0a0c | 1043:16cd | Intel      | Haswell-ULT HD Audio Cont... | 24    | snd_hda... | FDD61F096B |

### Storage (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 104c:803b | 1025:011f | Texas I... | PCIxx12 Flash Media Contr... | 64    | tifm_7xx1  | 7387D70AD5 |
| 1217:8231 | 1028:0493 | O2 Micro   | O2Micro Integrated MS/MSP... | 28    |            | CA6EFEBBD7 |
| 104c:803b | 1179:ff00 | Texas I... | PCIxx12 Flash Media Contr... | 23    | tifm_7xx1  | 92ACB586D2 |
| 1217:7130 | 1025:013c | O2 Micro   | Integrated MS/xD Controller  | 18    |            | 77E3B20E26 |
| 1217:7130 | 1179:ff50 | O2 Micro   | Integrated MS/xD Controller  | 18    |            | B6017B2145 |
| 104c:803b | 1179:ff02 | Texas I... | PCIxx12 Flash Media Contr... | 17    | tifm_7xx1  | 3CE1664885 |
| 104c:803b | 1179:ff10 | Texas I... | PCIxx12 Flash Media Contr... | 15    | tifm_7xx1  | 4FFE571137 |
| 104c:803b | 1025:0110 | Texas I... | PCIxx12 Flash Media Contr... | 12    | tifm_7xx1  | D4A385C83A |
| 104c:803b | 1025:0107 | Texas I... | PCIxx12 Flash Media Contr... | 10    | tifm_7xx1  | D14CE30BB6 |
| 1217:8330 | 1028:04a3 | O2 Micro   | OZ600 MS/xD Controller       | 10    |            | 19E1CA5871 |
| 1217:8331 | 1028:0494 | O2 Micro   | O2 Flash Memory Card         | 10    |            | 31F0876A89 |
| 1217:8331 | 1028:049a | O2 Micro   | O2 Flash Memory Card         | 8     |            | 5D67AE99E3 |
| 104c:803b | 104d:902d | Texas I... | PCIxx12 Flash Media Contr... | 7     | tifm_7xx1  | BD8A19714A |
| 1217:7130 | 10cf:143d | O2 Micro   | Integrated MS/xD Controller  | 7     |            | 6639C529C5 |
| 104c:803b | 104d:81e6 | Texas I... | PCIxx12 Flash Media Contr... | 6     | tifm_7xx1  | 50E5B9D6CA |
| 104c:803b | 104d:9005 | Texas I... | PCIxx12 Flash Media Contr... | 6     | tifm_7xx1  | 858BD651B7 |
| 104c:803b | 104d:9015 | Texas I... | PCIxx12 Flash Media Contr... | 6     | tifm_7xx1  | 3BEE1DDF68 |
| 104c:803b | 1179:0001 | Texas I... | PCIxx12 Flash Media Contr... | 6     | tifm_7xx1  | 3E0ED41BC7 |
| 1217:8331 | 1028:049b | O2 Micro   | O2 Flash Memory Card         | 6     |            | 26DE378A54 |
| 104c:803b | 1025:011c | Texas I... | PCIxx12 Flash Media Contr... | 5     | tifm_7xx1  | 89E46BA6FF |
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
| 1095:3531 | 1734:1107 | Silicon... | SiI 3531 [SATALink/SATARa... | 3     | sata_sil24 | 7F4ACC9070 |
| 1217:7130 | 1462:3ff3 | O2 Micro   | Integrated MS/xD Controller  | 3     |            | E6FCAC8295 |
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
| 1217:7130 | 1025:011a | O2 Micro   | Integrated MS/xD Controller  | 2     |            | 69380B60FC |
| 1217:7130 | 1025:0124 | O2 Micro   | Integrated MS/xD Controller  | 2     |            | 5AAFE28787 |
| 1217:7130 | 1028:026f | O2 Micro   | Integrated MS/xD Controller  | 2     |            | D6AAC94E1F |
| 1217:7130 | 1028:0275 | O2 Micro   | Integrated MS/xD Controller  | 2     |            | B0314C0713 |
| 1217:7130 | 1462:3fc1 | O2 Micro   | Integrated MS/xD Controller  | 2     |            | 278EF4A255 |
| 104c:8033 | 1025:0067 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | A260AE3290 |
| 104c:8033 | 1025:007e | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | FAC1D78802 |
| 104c:8033 | 103c:099c | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | AFE75774F3 |
| 104c:8033 | 103c:3082 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | 91C7AE2180 |
| 104c:8033 | 103c:308b | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | 0148BED7F1 |
| 104c:8033 | 103c:3091 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | 30D7D605F7 |
| 104c:8033 | 103c:309b | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | 88BD859F3F |
| 104c:8033 | 104d:81e2 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | C7597917F8 |
| 104c:8033 | 1631:c00a | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | AD3BB711D8 |
| 104c:8033 | 1734:1098 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | 0328C9BAD3 |
| 104c:8033 | 1854:0031 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | 18F757F572 |
| 104c:8033 | 1854:010c | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | 253B1DAE47 |
| 104c:803b | 1025:0101 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 153247F60A |
| 104c:803b | 1025:010e | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | C4C9F4E659 |
| 104c:803b | 1025:0129 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 4F1C235318 |
| 104c:803b | 103c:30a3 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | E5523A66D5 |
| 104c:803b | 103c:30ad | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 9F51D8D813 |
| 104c:803b | 103c:30b1 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | D4DC67EA5D |
| 104c:803b | 104d:81fc | Texas I... | PCIxx12 Flash Media Contr... | 1     |            | 7F0BB0CC92 |
| 104c:803b | 104d:8207 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 76350B5F91 |
| 104c:803b | 104d:820f | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 811EFEE1FC |
| 104c:803b | 104d:900f | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 3A190D628A |
| 104c:803b | 104d:9018 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 8A814A5779 |
| 104c:803b | 1071:8212 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 01F778FE4E |
| 104c:803b | 107b:0366 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 668DB92873 |
| 104c:803b | 1179:ff31 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | FED8975477 |
| 104c:803b | 1558:5407 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 353E3A22FD |
| 104c:803b | 17ff:0560 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 998C10A33A |
| 104c:803b | 1854:005f | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | F60C56AC42 |
| 104c:803b | 1854:0068 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 454736A9CC |
| 104c:803b | 5678:1234 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 52D85B0E27 |
| 104c:ac8f | 1028:018d | Texas I... | PCI7420/7620 SD/MS-Pro Co... | 1     | tifm_7xx1  | 97B5AC4625 |
| 104c:ac8f | 1854:000e | Texas I... | PCI7420/7620 SD/MS-Pro Co... | 1     | tifm_7xx1  | 76F306DE39 |
| 1095:3512 | 1095:3512 | Silicon... | SiI 3512 [SATALink/SATARa... | 1     | sata_sil   | 3EA811E273 |
| 1095:3531 | 103c:30d4 | Silicon... | SiI 3531 [SATALink/SATARa... | 1     | sata_sil24 | CF3A7AD203 |
| 1095:3531 | 1095:3531 | Silicon... | SiI 3531 [SATALink/SATARa... | 1     | sata_sil24 | CD49627D94 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e03 | 17aa:3977 | Intel      | 7 Series Chipset Family 6... | 241   | ahci       | 891002E8F2 |
| 8086:27c1 | 1043:83ad | Intel      | NM10/ICH7 Family SATA Con... | 153   | ahci       | 6A0513EC8D |
| 8086:1c03 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 149   | ahci       | A7618091FB |
| 8086:9c03 | 17aa:3978 | Intel      | 8 Series SATA Controller ... | 89    | ahci       | AFD92BF265 |
| 8086:3b29 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 79    | ahci       | 52035C5F01 |
| 8086:1e03 | 1025:0649 | Intel      | 7 Series Chipset Family 6... | 77    | ahci       | F28D18F3E9 |
| 8086:1c03 | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 76    | ahci       | 6B25B8982D |
| 8086:3b29 | 17aa:38c1 | Intel      | 5 Series/3400 Series Chip... | 70    | ahci       | 62697BF35B |
| 8086:2929 | 17aa:20f8 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 69    | ahci       | A23E000798 |
| 8086:1e03 | 17aa:5002 | Intel      | 7 Series Chipset Family 6... | 67    | ahci       | CE3DDF28FC |
| 8086:2929 | 17aa:3a1a | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 63    | ahci       | 601D53F9EB |
| 8086:1c03 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 62    | ahci       | 8579BA1B16 |
| 8086:1c03 | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 60    | ahci       | 826F5492EB |
| 8086:1e03 | 1025:0647 | Intel      | 7 Series Chipset Family 6... | 60    | ahci       | 6478022B75 |
| 8086:1e03 | 1025:064b | Intel      | 7 Series Chipset Family 6... | 57    | ahci       | E67DFC255A |
| 8086:1e03 | 1043:124d | Intel      | 7 Series Chipset Family 6... | 57    | ahci       | 0F8CE4DCC0 |
| 8086:3b2f | 17aa:2168 | Intel      | 5 Series/3400 Series Chip... | 57    | ahci       | DA5E944C6C |
| 8086:3b29 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 51    | ahci       | D023F50697 |
| 8086:0f23 | 17aa:3905 | Intel      | Atom Processor E3800 Seri... | 50    | ahci       | CC7193A7B9 |
| 8086:8c03 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 49    | ahci       | 262BB6B100 |
| 8086:1c03 | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 44    | ahci       | EE56C112BB |
| 8086:27c1 | 1025:0349 | Intel      | NM10/ICH7 Family SATA Con... | 44    | ahci       | 8CE41DB531 |
| 1022:7801 | 17aa:3801 | AMD        | FCH SATA Controller [AHCI... | 42    | ahci       | 760B445B08 |
| 8086:1c03 | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 42    | ahci       | EA07B48EB4 |
| 8086:1e03 | 1043:14c7 | Intel      | 7 Series Chipset Family 6... | 42    | ahci       | 9A401175B3 |
| 8086:1e03 | 17aa:5011 | Intel      | 7 Series Chipset Family 6... | 41    | ahci       | 65D329A2C6 |
| 1002:4391 | 1043:1117 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 40    | ahci       | 527313B5FF |
| 1022:7804 | 144d:c0da | AMD        | FCH SATA Controller [AHCI... | 40    | ahci       | A06125BD54 |
| 8086:1c03 | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 40    | ahci       | C0868A2B0C |
| 8086:1e03 | 8086:7270 | Intel      | 7 Series Chipset Family 6... | 39    | ahci       | 39CA2BE7BB |
| 8086:3b29 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 39    | ahci       | 3C5767E938 |
| 8086:1c03 | 144d:c0b6 | Intel      | 6 Series/C200 Series Chip... | 38    | ahci       | 616616B60F |
| 8086:2929 | 1043:1867 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 37    | ahci       | 38190AD2E1 |
| 8086:2829 | 17aa:20a7 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 36    | ahci       | 7F41843359 |
| 8086:9c03 | 1025:0866 | Intel      | 8 Series SATA Controller ... | 34    | ahci       | 1C77D7A584 |
| 8086:0f23 | 17aa:3909 | Intel      | Atom Processor E3800 Seri... | 33    | ahci       | EE1CFF7014 |
| 8086:1c03 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 33    | ahci       | FBF8462F41 |
| 8086:2829 | 1025:011f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 32    | ahci       | 7387D70AD5 |
| 8086:5ae3 | 1043:16a0 | Intel      | Celeron N3350/Pentium N42... | 32    | ahci       | 0FAD7AC4EB |
| 1002:4391 | 103c:3577 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 31    | ahci       | 4201CDD966 |
| 8086:2929 | 1025:0212 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 31    | ahci       | 6029A4A18A |
| 8086:1e03 | 1043:1587 | Intel      | 7 Series Chipset Family 6... | 30    | ahci       | 469E04E0D5 |
| 8086:1e03 | 144d:c652 | Intel      | 7 Series Chipset Family 6... | 30    | ahci       | A57B555F26 |
| 8086:2929 | 144d:c06d | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 30    | ahci       | BC68546696 |
| 1002:4391 | 1043:104c | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 29    | ahci       | 0051F69751 |
| 1022:7801 | 17aa:397c | AMD        | FCH SATA Controller [AHCI... | 29    | ahci       | E1D3B73A71 |
| 8086:0f23 | 1043:14dd | Intel      | Atom Processor E3800 Seri... | 29    | ahci       | 8D51E5FEC5 |
| 8086:1e03 | 1179:fb31 | Intel      | 7 Series Chipset Family 6... | 29    | ahci       | 806B890CCF |
| 8086:1e03 | 17aa:21f3 | Intel      | 7 Series Chipset Family 6... | 29    | ahci       | 6D5F1234C2 |
| 8086:9c03 | 1025:0775 | Intel      | 8 Series SATA Controller ... | 29    | ahci       | 3BD8AD186F |
| 8086:1e03 | 144d:c0d8 | Intel      | 7 Series Chipset Family 6... | 28    | ahci       | 0F042024B4 |
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 28    | ahci       | 1579402536 |
| 8086:9c03 | 1043:131d | Intel      | 8 Series SATA Controller ... | 28    | ahci       | 761A86BDC8 |
| 1022:7804 | 103c:184a | AMD        | FCH SATA Controller [AHCI... | 27    | ahci       | 0D67044A36 |
| 1022:7904 | 103c:8330 | AMD        | FCH SATA Controller [AHCI... | 27    | ahci       | D32B7275C3 |
| 197b:2360 | 1043:1348 | JMicron... | JMB360 AHCI Controller       | 27    | ahci       | 4137AC8F54 |
| 8086:1e03 | 17aa:21f6 | Intel      | 7 Series Chipset Family 6... | 27    | ahci       | 7DA7A083D7 |
| 8086:22a3 | 1025:1012 | Intel      | Atom/Celeron/Pentium Proc... | 27    | ahci       | 5A7F96289D |
| 8086:2829 | 103c:30cc | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 27    | ahci       | 9EDE738BFC |
| 8086:3b29 | 144d:c581 | Intel      | 5 Series/3400 Series Chip... | 27    | ahci       | 4B260556B7 |
| 8086:9c03 | 1028:0651 | Intel      | 8 Series SATA Controller ... | 27    | ahci       | 1E1FE2154B |
| 8086:0f23 | 1297:2041 | Intel      | Atom Processor E3800 Seri... | 26    | ahci       | 100EB984CA |
| 8086:1e03 | 1043:1477 | Intel      | 7 Series Chipset Family 6... | 26    | ahci       | C38728C67C |
| 8086:3b29 | 144d:c07f | Intel      | 5 Series/3400 Series Chip... | 26    | ahci       | 408D0B84F9 |
| 8086:9d03 | 1025:1193 | Intel      | Sunrise Point-LP SATA Con... | 26    | ahci       | 141D7917FF |
| 1002:4391 | 1002:4390 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 25    | ahci       | 5E3F89149F |
| 1022:7801 | 17aa:3802 | AMD        | FCH SATA Controller [AHCI... | 25    | ahci       | 105DCB0993 |
| 8086:1c03 | 104d:908b | Intel      | 6 Series/C200 Series Chip... | 25    | ahci       | 9B5D49431C |
| 8086:1e03 | 1025:0686 | Intel      | 7 Series Chipset Family 6... | 25    | ahci       | 29CFE1AD23 |
| 8086:27c1 | 144d:c072 | Intel      | NM10/ICH7 Family SATA Con... | 25    | ahci       | 3A0FEA4700 |
| 8086:1e03 | 10cf:16e2 | Intel      | 7 Series Chipset Family 6... | 24    | ahci       | B9A4817612 |
| 8086:1e03 | 17aa:21fa | Intel      | 7 Series Chipset Family 6... | 24    | ahci       | DB9250D9E0 |
| 8086:9c03 | 1043:16cd | Intel      | 8 Series SATA Controller ... | 24    | ahci       | FDD61F096B |
| 8086:9d03 | 1025:1085 | Intel      | Sunrise Point-LP SATA Con... | 23    | ahci       | AE1CE65D11 |
| 1022:7901 | 1025:1192 | AMD        | FCH SATA Controller [AHCI... | 22    | ahci       | 0D71E52A34 |
| 8086:0f23 | 103c:2213 | Intel      | Atom Processor E3800 Seri... | 22    | ahci       | 964E06B446 |
| 8086:1e03 | 104d:90ab | Intel      | 7 Series Chipset Family 6... | 22    | ahci       | B56B7F6394 |
| 8086:1e03 | 104d:90b8 | Intel      | 7 Series Chipset Family 6... | 22    | ahci       | 66E469F722 |
| 8086:22a3 | 1043:10c0 | Intel      | Atom/Celeron/Pentium Proc... | 22    | ahci       | F8FDA4EFC3 |
| 8086:3b29 | 1025:036d | Intel      | 5 Series/3400 Series Chip... | 22    | ahci       | 333F038ACE |
| 1002:4380 | 1028:01f5 | AMD        | SB600 Non-Raid-5 SATA        | 21    | ahci       | BFDE36E2F4 |
| 1002:4391 | 1025:0489 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 21    | ahci       | E5D4CDDD0B |
| 1002:4391 | 1043:1313 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 21    | ahci       | 8D5F16B3AC |
| 8086:27c1 | 1025:0590 | Intel      | NM10/ICH7 Family SATA Con... | 21    | ahci       | D95215116B |
| 8086:3b29 | 144d:c06a | Intel      | 5 Series/3400 Series Chip... | 21    | ahci       | 86987CF1ED |
| 8086:9c83 | 1025:098a | Intel      | Wildcat Point-LP SATA Con... | 21    | ahci       | 6D1C781DE0 |
| 8086:9d03 | 1025:115f | Intel      | Sunrise Point-LP SATA Con... | 21    | ahci       | E4B342382F |
| 8086:0f23 | 17aa:3986 | Intel      | Atom Processor E3800 Seri... | 20    | ahci       | E3105C7B7A |
| 8086:1c03 | 1025:0511 | Intel      | 6 Series/C200 Series Chip... | 20    | ahci       | 1024538738 |
| 8086:1c03 | 103c:1670 | Intel      | 6 Series/C200 Series Chip... | 20    | ahci       | FC29696703 |
| 8086:1c03 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 20    | ahci       | 88B8816BFE |
| 8086:1e03 | 103c:183e | Intel      | 7 Series Chipset Family 6... | 20    | ahci       | 19D5DAD934 |
| 8086:2829 | 1025:011e | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 20    | ahci       | ED83D72FBE |
| 8086:2829 | 1025:0136 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 20    | ahci       | 1EF9D813A6 |
| 8086:2829 | 1028:022f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 20    | ahci       | 55CD396670 |
| 8086:9c03 | 17aa:220c | Intel      | 8 Series SATA Controller ... | 20    | ahci       | 7637F3DE5F |
| 8086:9d03 | 17aa:3809 | Intel      | Sunrise Point-LP SATA Con... | 20    | ahci       | 005771EDFD |
| 1002:4391 | 1025:0598 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 19    | ahci       | 8ECDC739A8 |
| 1002:4391 | 144d:c589 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 19    | ahci       | 99E97125D1 |
| 10de:0ab9 | 10de:cb79 | Nvidia     | MCP79 AHCI Controller        | 19    | ahci       | 9F753AC669 |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2850 | 1025:011f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 64    | ata_pii... | 7387D70AD5 |
| 8086:2850 | 17aa:20a6 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 36    | ata_pii... | 7F41843359 |
| 8086:2828 | 1025:011f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 34    | ata_pii... | C8EDDEAB31 |
| 1002:439c | 1043:104c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 32    | pata_at... | 0051F69751 |
| 1039:5513 | 1039:5513 | Silicon... | 5513 IDE Controller          | 30    | pata_si... | 2F635C2315 |
| 8086:2850 | 1028:01f9 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 29    | ata_pii... | E5DE762918 |
| 8086:2850 | 103c:30cc | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 27    | ata_pii... | 9EDE738BFC |
| 8086:27c4 | 1025:0090 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 26    | ata_pii... | 719BE91D02 |
| 8086:2828 | 1028:01f9 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 24    | ata_pii... | E5DE762918 |
| 1002:4376 | 1025:009f | AMD        | IXP SB4x0 IDE Controller     | 23    | pata_at... | A28F7B2623 |
| 8086:1e01 | 17aa:3977 | Intel      | 7 Series Chipset Family 4... | 23    | ata_pii... | 867B6D5AEC |
| 8086:2850 | 1025:0136 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 23    | ata_pii... | 1EF9D813A6 |
| 8086:1c01 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 22    | ata_pii... | BD698398A7 |
| 8086:1c09 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 22    | ata_pii... | BD698398A7 |
| 8086:2850 | 1025:011e | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 22    | ata_pii... | ED83D72FBE |
| 1002:438c | 1028:01f5 | AMD        | SB600 IDE                    | 21    | pata_at... | BFDE36E2F4 |
| 8086:1e09 | 17aa:3977 | Intel      | 7 Series Chipset Family 2... | 21    | ata_pii... | 867B6D5AEC |
| 8086:2850 | 1028:022f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 21    | pata_acpi  | 55CD396670 |
| 8086:27c0 | 1043:83ad | Intel      | NM10/ICH7 Family SATA Con... | 20    | ata_pii... | DDBC734D1C |
| 1039:1183 | 1039:1183 | Silicon... | SATA Controller / IDE mode   | 19    | sata_si... | 2F635C2315 |
| 1039:1183 | 1043:1cf7 | Silicon... | SATA Controller / IDE mode   | 19    | sata_si... | C7C21D1A2A |
| 1039:5513 | 1043:1cf7 | Silicon... | 5513 IDE Controller          | 19    | pata_si... | C7C21D1A2A |
| 8086:2850 | 1179:ff00 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 19    | ata_pii... | 3CE1664885 |
| 1002:4379 | 1002:4379 | AMD        | IXP SB4x0 Serial ATA Cont... | 18    | sata_si... | A28F7B2623 |
| 1002:438c | 1043:1627 | AMD        | SB600 IDE                    | 18    | pata_at... | 7E94795F51 |
| 8086:27c4 | 1179:ff00 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 18    | ata_pii... | 92ACB586D2 |
| 8086:27df | 103c:30a2 | Intel      | 82801G (ICH7 Family) IDE ... | 18    | ata_pii... | 531D26CDD8 |
| 8086:27df | 17aa:3810 | Intel      | 82801G (ICH7 Family) IDE ... | 18    | ata_pii... | 876835D508 |
| 10de:0550 | 1025:0126 | Nvidia     | MCP67 AHCI Controller        | 17    | pata_ac... | F7695ADD11 |
| 8086:2850 | 1025:0121 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 17    | ata_pii... | CFBA4082BB |
| 1039:1183 | 1039:1180 | Silicon... | SATA Controller / IDE mode   | 16    | sata_si... | 8C665A5EB1 |
| 8086:27c4 | 1043:1317 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 16    | ata_pii... | B304C61746 |
| 1002:438c | 1043:1417 | AMD        | SB600 IDE                    | 15    | pata_at... | 54C92BF69C |
| 1002:438c | 144d:c034 | AMD        | SB600 IDE                    | 15    | pata_at... | BFB5C59BD6 |
| 10de:0759 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] IDE    | 15    | pata_am... | 265A212FDC |
| 10de:0ad0 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] SAT... | 15    | pata_ac... | 265A212FDC |
| 8086:27c4 | 1179:ff10 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 15    | ata_pii... | 4FFE571137 |
| 1002:439c | 17aa:3937 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 14    | pata_at... | 9F3EAD2DB7 |
| 1039:1183 | 1043:19e7 | Silicon... | SATA Controller / IDE mode   | 14    | sata_si... | D7439F8AE4 |
| 1039:5513 | 1043:19e7 | Silicon... | 5513 IDE Controller          | 14    | pata_si... | D7439F8AE4 |
| 8086:2850 | 103c:30d8 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 14    | ata_pii... | 48EE31D6E9 |
| 1002:438c | 144d:c511 | AMD        | SB600 IDE                    | 13    | pata_at... | 666CC686BC |
| 1022:780c | 1028:04b1 | AMD        | FCH IDE Controller           | 13    | pata_at... | 2C903F36D0 |
| 10de:0560 | 1025:0126 | Nvidia     | MCP67 IDE Controller         | 13    | pata_am... | F7695ADD11 |
| 8086:2653 | 1014:056a | Intel      | 82801FBM (ICH6M) SATA Con... | 13    | ata_gen... | CCA643879F |
| 8086:27c4 | 1025:015b | Intel      | 82801GBM/GHM (ICH7-M Fami... | 13    | ata_pii... | 5DA90F3771 |
| 8086:27c4 | 1028:01bd | Intel      | 82801GBM/GHM (ICH7-M Fami... | 13    | ata_pii... | 586A6A9F8A |
| 8086:2850 | 1043:14e7 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 13    | ata_pii... | D9970BDA58 |
| 1002:438c | 103c:30c2 | AMD        | SB600 IDE                    | 12    | pata_at... | 9B49EE4D5C |
| 8086:27c4 | 1028:01c2 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 12    | ata_pii... | 3B31FF8739 |
| 8086:27c4 | 144d:ca00 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 12    | ata_pii... | FC7D577AB7 |
| 8086:27df | 103c:30d5 | Intel      | 82801G (ICH7 Family) IDE ... | 12    | ata_pii... | 445A4251A7 |
| 8086:2828 | 17aa:20a8 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 12    | ata_pii... | 037CAC7A3D |
| 8086:2850 | 103c:30d9 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 12    | pata_acpi  | BD55864B86 |
| 8086:2850 | 1043:1767 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 12    | ata_pii... | 4137AC8F54 |
| 8086:2850 | 1179:ff1c | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 12    | ata_pii... | 588EAD6870 |
| 8086:2850 | 1179:ff50 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 12    | ata_pii... | B7716C3755 |
| 1002:439c | 1025:036e | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 11    | pata_at... | ACFD67A4EA |
| 1002:439c | 1043:101c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 11    | pata_at... | 7EAE69FEDB |
| 1002:439c | 1043:1067 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 11    | pata_at... | E69E0C49CF |
| 1022:780c | 103c:358d | AMD        | FCH IDE Controller           | 11    | pata_at... | 2F05A42A82 |
| 1022:780c | 103c:3593 | AMD        | FCH IDE Controller           | 11    | pata_at... | 5BA1A4660E |
| 1039:1183 | 1043:1a77 | Silicon... | SATA Controller / IDE mode   | 11    | sata_si... | 9B7F075594 |
| 8086:27df | 17aa:200c | Intel      | 82801G (ICH7 Family) IDE ... | 11    | ata_pii... | 28C1100253 |
| 8086:2828 | 1028:029a | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 11    | ata_pii... | 394D903321 |
| 8086:2850 | 1043:1517 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 11    | ata_pii... | FAECBEFA9B |
| 8086:27c4 | 1025:0107 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 10    | ata_pii... | D14CE30BB6 |
| 8086:27df | 1025:012e | Intel      | 82801G (ICH7 Family) IDE ... | 10    | ata_pii... | 16BE592F4F |
| 8086:27df | 8086:7270 | Intel      | 82801G (ICH7 Family) IDE ... | 10    | pata_acpi  | FDEA938323 |
| 8086:2850 | 103c:30c0 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 10    | ata_pii... | 21ACEB2150 |
| 8086:2850 | 1179:ff64 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 10    | ata_pii... | 30865D7A41 |
| 8086:811a | 1025:0244 | Intel      | US15W/US15X/US15L/UL11L S... | 10    | pata_sc... | 5E830F987C |
| 1002:4376 | 1179:ff31 | AMD        | IXP SB4x0 IDE Controller     | 9     | pata_at... | BA3F405EF7 |
| 1022:780c | 1043:14b7 | AMD        | FCH IDE Controller           | 9     | pata_at... | 6C12E2EE00 |
| 10de:0550 | 103c:30cf | Nvidia     | MCP67 AHCI Controller        | 9     | ahci, p... | 1184F5572B |
| 8086:27c4 | 1025:0110 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 9     | ata_pii... | 9708C7ABC2 |
| 8086:27c4 | 1043:830f | Intel      | 82801GBM/GHM (ICH7-M Fami... | 9     | ata_pii... | 2D4D5EFCB2 |
| 8086:27c4 | 1462:0110 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 9     | ata_pii... | 7CDCFE9788 |
| 8086:27c4 | 17aa:3835 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 9     | ata_pii... | 876835D508 |
| 8086:27df | 103c:30bb | Intel      | 82801G (ICH7 Family) IDE ... | 9     | ata_pii... | FB7F51216E |
| 8086:2a46 | 17aa:20ea | Intel      | Mobile 4 Series Chipset P... | 9     | pata_acpi  | 62191496FD |
| 1002:4379 | 1179:ff31 | AMD        | IXP SB4x0 Serial ATA Cont... | 8     | sata_si... | 475E8B06F8 |
| 1002:438c | 1028:022a | AMD        | SB600 IDE                    | 8     | pata_at... | 77649E9A5A |
| 1002:439c | 1025:0489 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 8     | pata_at... | 675A304171 |
| 1039:5513 | 1558:0801 | Silicon... | 5513 IDE Controller          | 8     | pata_acpi  | 868812FE2A |
| 10de:0ab5 | 1043:8402 | Nvidia     | MCP79 SATA Controller        | 8     | pata_ac... | 715375448A |
| 8086:266f | 1028:01c9 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 8     | ata_pii... | 8947DE9DC2 |
| 8086:266f | 103c:099c | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 8     | ata_pii... | E0DF895DC8 |
| 8086:27c0 | 1025:0590 | Intel      | NM10/ICH7 Family SATA Con... | 8     | ata_pii... | D5A624C8FE |
| 8086:2850 | 1028:023a | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 8     | ata_pii... | 2B5F0594D3 |
| 8086:2850 | 103c:30be | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 8     | pata_acpi  | 2B9B5142AF |
| 8086:2850 | 1043:1017 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 8     | ata_pii... | 7A5FBF55AD |
| 8086:2850 | 106b:00a1 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 8     | pata_acpi  | B7FF730CA4 |
| 8086:2928 | 1043:1867 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 8     | ata_pii... | B994521F10 |
| 8086:292d | 1043:1867 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 8     | ata_pii... | B994521F10 |
| 8086:3b2d | 17aa:216a | Intel      | 5 Series/3400 Series Chip... | 8     | pata_acpi  | 14BF9C4413 |
| 8086:3b2e | 17aa:2169 | Intel      | 5 Series/3400 Series Chip... | 8     | pata_acpi  | 14BF9C4413 |
| 8086:811a | 1043:83ce | Intel      | US15W/US15X/US15L/UL11L S... | 8     | pata_sc... | 70E60207C2 |
| 1039:5513 | 1019:5a00 | Silicon... | 5513 IDE Controller          | 7     | pata_sis   | 629C9532FE |
| 8086:0f21 | 1043:161d | Intel      | Atom Processor E3800 Seri... | 7     | ata_pii... | 9328A19EB6 |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 95    | nvme       | 3A4D90A1C3 |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 94    | nvme       | DE5FB421D9 |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 43    | nvme       | 5F7A70586E |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 26    | nvme       | 3240076AA6 |
| 1c5c:1527 | 1c5c:1527 | SK Hynix   | Non-Volatile memory contr... | 22    | nvme       | 75F82151FF |
| 1179:0113 | 1179:0001 | Toshiba... | BG3 NVMe SSD Controller      | 18    | nvme       | 766B0474A3 |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 18    | nvme       | 58528DA222 |
| 1179:0115 | 1179:0001 | Toshiba... | XG4 NVMe SSD Controller      | 17    | nvme       | 0E036EFA3C |
| 15b7:5003 | 15b7:5003 | Sandisk    | WD Black 2018/PC SN520 NV... | 17    | nvme       | 24A04CA275 |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | Non-Volatile memory contr... | 14    | nvme       | 79E53D2DB5 |
| 1179:010f | 1179:0001 | Toshiba... | NVMe Controller              | 11    | nvme       | DFA0A0A8A4 |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/PC SN720 NV... | 11    | nvme       | 87EF40FDD4 |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 11    | nvme       | DDA26EE2AA |
| 2646:5008 | 2646:5008 | Kingsto... | Non-Volatile memory contr... | 9     | nvme       | EA12327BDD |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 7     | nvme       | 123447177A |
| 17aa:0004 | 17aa:1004 | Lenovo     | Non-Volatile memory contr... | 5     | nvme       | 4B9BEB25C2 |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 5     | nvme       | 7CCAC31D71 |
| 14a4:2300 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 4     | nvme       | CAFA9C8DA5 |
| 15b7:5005 | 15b7:5005 | Sandisk    | Non-Volatile memory contr... | 4     | nvme       | C537E40686 |
| 1987:5008 | 1987:5008 | Phison ... | NVMe Storage Controller      | 4     | nvme       | EE055BD7C1 |
| 15b7:5004 | 15b7:5004 | Sandisk    | Non-Volatile memory contr... | 3     | nvme       | 1E82DEB58E |
| 17aa:0005 | 17aa:1005 | Lenovo     | Non-Volatile memory contr... | 3     | nvme       | 444D60D6DA |
| 1c5c:1283 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 3     | nvme       | 1675040CCD |
| c0a9:2263 | c0a9:2263 | Micron/... | Non-Volatile memory contr... | 3     | nvme       | BF4A9DEE07 |
| 106b:2001 | 106b:2001 | Apple      | S1X NVMe Controller          | 2     | nvme       | 195DAC413B |
| 1179:011a | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 2     | nvme       | DBB0FFDB96 |
| 126f:2262 | 126f:2262 | Silicon... | Non-Volatile memory contr... | 2     | nvme       | A12FF60DCD |
| 14a4:2100 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 2     | nvme       | 0594A8F475 |
| 15b7:5001 | 1b4b:1093 | Sandisk    | WD Black NVMe SSD            | 2     | nvme       | B2B217C7BA |
| 17aa:0003 | 17aa:1003 | Lenovo     | Non-Volatile memory contr... | 2     | nvme       | 6F9DCA6953 |
| 1c5c:1284 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 2     | nvme       | EA9D592F39 |
| 1c5c:1285 | 1c5c:0000 | SK Hynix   | Non-Volatile memory contr... | 2     | nvme       | F1ACFE989D |
| 10ec:5762 | 10ec:5762 | Realtek... | Realtek Non-Volatile memo... | 1     | nvme       | FECF8A1623 |
| 126f:2263 | 126f:2263 | Silicon... | Non-Volatile memory contr... | 1     | nvme       | D999B85EFE |
| 14a4:21f1 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 1     | nvme       | BB13C77033 |
| 14a4:2200 | 1b4b:1093 | Lite-On... | Lite-On Non-Volatile memo... | 1     | nvme       | 8A7077867F |
| 14a4:22f1 | 1b4b:1093 | Lite-On... | M8Pe Series NVMe SSD         | 1     | nvme       | ED328FC569 |
| 14a4:23f1 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 1     | nvme       | 05BB755A5A |
| 14a4:5100 | 14a4:5100 | Lite-On... | Non-Volatile memory contr... | 1     | nvme       | 766158C703 |
| 17aa:0006 | 17aa:1006 | Lenovo     | Non-Volatile memory contr... | 1     | nvme       | 8B3F86E523 |
| 1987:5007 | 1987:5007 | Phison ... | E7 NVMe Controller           | 1     | nvme       | 6EFF91BD25 |
| 1c5c:1504 | 0100:1093 | SK Hynix   | SC300 512GB M.2 2280 SATA... | 1     | nvme       | 75AEAE69AD |
| 1c5c:1627 | 1c5c:1627 | SK Hynix   | Non-Volatile memory contr... | 1     | nvme       | 8FB4429DD6 |
| 1cc1:8201 | 1cc1:8201 |            | Non-Volatile memory contr... | 1     | nvme       | AACC137FAA |
| 1cc4:5008 | 1cc4:5008 | Union M... | Non-Volatile memory contr... | 1     | nvme       | 89D8981E8C |
| 2646:2262 | 2646:2262 | Kingsto... | Technology Company Non-Vo... | 1     | nvme       | 048229855F |
| 8086:2522 | 8086:3806 | Intel      | NVMe SSD Optane Series Co... | 1     | nvme       | EFDC2E3D09 |
| 8086:2522 | 8086:3811 | Intel      | NVMe SSD Optane Series Co... | 1     | nvme       | AEAC4E0E68 |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:282a | 1028:0233 | Intel      | 82801 Mobile SATA Control... | 26    | ahci       | 1F49A84F1F |
| 8086:282a | 103c:1818 | Intel      | 82801 Mobile SATA Control... | 22    | ahci       | C865BDB72F |
| 8086:282a | 1028:0493 | Intel      | 82801 Mobile SATA Control... | 14    | ahci       | CA6EFEBBD7 |
| 8086:282a | 103c:84a6 | Intel      | 82801 Mobile SATA Control... | 12    | ahci       | 1A3504B63C |
| 8086:282a | 1028:0534 | Intel      | 82801 Mobile SATA Control... | 10    | ahci       | 8C26DF88EE |
| 8086:282a | 1028:024f | Intel      | 82801 Mobile SATA Control... | 9     | ahci       | 5A8B3F34A3 |
| 8086:282a | 1028:040a | Intel      | 82801 Mobile SATA Control... | 9     | ahci       | E8A892A43C |
| 8086:282a | 1043:1fc0 | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | BBAF5C143F |
| 8086:282a | 1028:04a3 | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | 19E1CA5871 |
| 8086:282a | 1028:05ca | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | CA9C198099 |
| 8086:282a | 103c:18a5 | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | A978F2CA38 |
| 8086:282a | 17aa:380f | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | F3FC3BB5F8 |
| 8086:282a | 1025:1264 | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | F3941C8871 |
| 8086:282a | 1028:0535 | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | 95A631AAE1 |
| 8086:282a | 1028:05be | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | D8BE8B7344 |
| 8086:282a | 103c:8532 | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | 3839DE934E |
| 8086:282a | 17aa:3810 | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | 3FFC2E920B |
| 8086:282a | 17aa:3814 | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | 287B0F5C3B |
| 8086:282a | 1028:024d | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 59050A5736 |
| 8086:282a | 1028:040b | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 80B359DC57 |
| 8086:282a | 1028:0492 | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 9C07EE4C86 |
| 8086:282a | 1028:053d | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 85B9549CFF |
| 8086:282a | 1028:05aa | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | A1B30D6B32 |
| 8086:282a | 103c:1894 | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 0A6F4AEE88 |
| 8086:282a | 103c:18fd | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | C56EC0A2C5 |
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
| 8086:282a | 1028:0277 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | F474D6B56B |
| 8086:282a | 1028:040c | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | F827065AC9 |
| 8086:282a | 1028:062b | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 73DB320B5F |
| 8086:282a | 1028:062e | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 6C5F8E4975 |
| 8086:282a | 1028:06dc | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | EE5666AC16 |
| 8086:282a | 1028:06de | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 310649AEDE |
| 8086:282a | 1028:06df | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 80B843095C |
| 8086:282a | 1028:0798 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 882D11658B |
| 8086:282a | 1028:0810 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | EB05A1DBC4 |
| 8086:282a | 103c:1793 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 42DF53B120 |
| 8086:282a | 103c:849a | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 368BA9E33B |
| 8086:282a | 103c:84a7 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 92550C4EB8 |
| 8086:282a | 103c:84ca | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 0BEFDCEA98 |
| 8086:282a | 1043:1311 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | ADFF6B4EC1 |
| 8086:282a | 1043:1f40 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | B6B40DE397 |
| 8086:282a | 104d:905a | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | EB4E58C4D9 |
| 8086:282a | 104d:907b | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 9E7981F839 |
| 8086:282a | 104d:9084 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 9109D4A264 |
| 1106:3249 | 1734:107c | VIA Tec... | VT6421 IDE/SATA Controller   | 2     | sata_via   | 95CA42DAA7 |
| 8086:2822 | 1028:06de | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 105F2EC750 |
| 8086:2822 | 1028:06df | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 5ABDD53903 |
| 8086:282a | 1025:125e | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 291836CDCE |
| 8086:282a | 1028:0549 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 6136663F73 |
| 8086:282a | 1028:057e | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | F0C39947CF |
| 8086:282a | 1028:05ab | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 023510307E |
| 8086:282a | 1028:05bd | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 0D6F7B2905 |
| 8086:282a | 1028:05e0 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | B98000D304 |
| 8086:282a | 1028:062c | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 738FC0AEF7 |
| 8086:282a | 1028:0704 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 6F1DE9BD47 |
| 8086:282a | 1028:0797 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | F887B76EAB |
| 8086:282a | 1028:079f | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 83AF48D592 |
| 8086:282a | 1028:07a7 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | F488CFD08F |
| 8086:282a | 1028:07e6 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | AD9D887C75 |
| 8086:282a | 1028:081c | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | BE727B6EED |
| 8086:282a | 1028:086f | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 9402076861 |
| 8086:282a | 1028:0877 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 8B270D4228 |
| 8086:282a | 103c:1896 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 7720ED3668 |
| 8086:282a | 103c:1897 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | E9EFD90C84 |
| 8086:282a | 103c:18ee | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 6996375996 |
| 8086:282a | 103c:195e | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 219510589C |
| 8086:282a | 103c:7009 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 33F0AAADD9 |
| 8086:282a | 103c:84b2 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 7B60495AED |
| 8086:282a | 103c:84db | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 71A27E6106 |
| 8086:282a | 1043:15a7 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 68D415ACCA |
| 8086:282a | 1043:1a10 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | B7725FE47A |
| 8086:282a | 1043:1bb0 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | B8BE17D96B |
| 8086:282a | 1043:1bc0 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | F941D319CB |
| 8086:282a | 1179:fb30 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 81064653ED |
| 8086:282a | 17aa:3977 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 9C0894F95C |
| 8086:27c6 | 1025:006c | Intel      | 82801GHM (ICH7-M DH) SATA... | 1     | ahci       | 1CE26C391A |
| 8086:2822 | 1028:0776 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | F9BD7B0C74 |
| 8086:2822 | 1028:07a9 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | 4AFB8F7991 |
| 8086:2822 | 1028:07b0 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | EFA61A5893 |
| 8086:2822 | 1043:13f0 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | 9E9F9D13D1 |
| 8086:2822 | 1043:17d0 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | C6173B38B7 |
| 8086:282a | 1025:0924 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | E6ED7A4F8D |
| 8086:282a | 1025:105b | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 8D320DFB2E |
| 8086:282a | 1025:1266 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | D6D7F9CC30 |
| 8086:282a | 1025:1269 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 68576788C6 |
| 8086:282a | 1025:1273 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | CF276AF2EE |
| 8086:282a | 1025:128d | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 517CAD6069 |
| 8086:282a | 1025:1300 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | CB5E242074 |
| 8086:282a | 1028:0252 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 8DCD69450D |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:16be | 1025:0647 | Broadco... | BCM57765/57785 MS Card Re... | 212   |            | E67DFC255A |
| 14e4:16bf | 1025:0647 | Broadco... | BCM57765/57785 xD-Picture... | 212   |            | E67DFC255A |
| 197b:2382 | 1043:1a07 | JMicron... | SD/MMC Host Controller       | 116   | sdhci_pci  | F47F34752E |
| 197b:2383 | 1043:1a07 | JMicron... | MS Host Controller           | 98    | jmb38x_ms  | F47F34752E |
| 197b:2384 | 1043:1a07 | JMicron... | xD Host Controller           | 97    |            | F47F34752E |
| 14e4:16be | 1025:0504 | Broadco... | BCM57765/57785 MS Card Re... | 86    |            | 8579BA1B16 |
| 14e4:16bf | 1025:0504 | Broadco... | BCM57765/57785 xD-Picture... | 86    |            | 8579BA1B16 |
| 1180:e822 | 17aa:2133 | Ricoh      | MMC/SD Host Controller       | 55    | sdhci_pci  | DA5E944C6C |
| 1180:0592 | 17aa:20ca | Ricoh      | R5C592 Memory Stick Bus H... | 51    | r592       | A23E000798 |
| 1180:0852 | 17aa:20cb | Ricoh      | xD-Picture Card Controller   | 51    | r852       | A23E000798 |
| 1180:e230 | 104d:9071 | Ricoh      | R5U2xx (R5U230 / R5U231 /... | 39    |            | 3C5767E938 |
| 1180:e230 | 17aa:2134 | Ricoh      | R5U2xx (R5U230 / R5U231 /... | 36    |            | DA5E944C6C |
| 8086:1513 | 2222:1111 | Intel      | CV82524 Thunderbolt Contr... | 34    | pcieport   | 16BDB52C40 |
| 8086:d150 |           | Intel      | Core Processor QPI Link      | 33    |            | 1BF77DE21D |
| 8086:d151 |           | Intel      | Core Processor QPI Routin... | 33    |            | 1BF77DE21D |
| 1180:0592 | 103c:30cc | Ricoh      | R5C592 Memory Stick Bus H... | 27    | r592       | 9EDE738BFC |
| 1180:0852 | 103c:30cc | Ricoh      | xD-Picture Card Controller   | 27    | r852       | 9EDE738BFC |
| 197b:2392 | 103c:17f6 | JMicron... | SD/MMC Host Controller       | 27    | sdhci_pci  | AB69AA73CD |
| 197b:2393 | 103c:17f6 | JMicron... | MS Host Controller           | 27    | jmb38x_ms  | AB69AA73CD |
| 1180:e823 | 17aa:21f6 | Ricoh      | PCIe SDXC/MMC Host Contro... | 23    | sdhci_pci  | A4911B787A |
| 197b:2392 | 103c:167c | JMicron... | SD/MMC Host Controller       | 23    | sdhci_pci  | 15E5D2BB9D |
| 197b:2393 | 103c:167c | JMicron... | MS Host Controller           | 23    | jmb38x_ms  | 15E5D2BB9D |
| 1180:0592 | 1025:011e | Ricoh      | R5C592 Memory Stick Bus H... | 21    | r592       | ED83D72FBE |
| 1180:0592 | 1028:022f | Ricoh      | R5C592 Memory Stick Bus H... | 21    | r592       | 55CD396670 |
| 1180:0843 | 1028:01f5 | Ricoh      | R5C843 MMC Host Controller   | 21    | sdhci_pci  | BFDE36E2F4 |
| 1180:0852 | 1028:022f | Ricoh      | xD-Picture Card Controller   | 21    | r852       | 55CD396670 |
| 8086:1911 | 8086:2015 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 21    |            | 8EB32C768B |
| 8086:d155 |           | Intel      | Core Processor System Man... | 21    |            | 1BF77DE21D |
| 8086:d156 |           | Intel      | Core Processor Semaphore ... | 21    |            | 1BF77DE21D |
| 8086:d157 |           | Intel      | Core Processor System Con... | 21    |            | 1BF77DE21D |
| 8086:d158 |           | Intel      | Core Processor Miscellane... | 21    |            | 1BF77DE21D |
| 1180:0852 | 1025:011e | Ricoh      | xD-Picture Card Controller   | 20    | r852       | ED83D72FBE |
| 1180:e823 | 17aa:21ce | Ricoh      | PCIe SDXC/MMC Host Contro... | 20    | sdhci_pci  | EBA01DE2BA |
| 1180:e822 | 17aa:21f3 | Ricoh      | MMC/SD Host Controller       | 19    | sdhci_pci  | 6D5F1234C2 |
| 1180:0592 | 1043:1627 | Ricoh      | R5C592 Memory Stick Bus H... | 18    | r592       | 7E94795F51 |
| 1180:e823 | 17aa:21f3 | Ricoh      | PCIe SDXC/MMC Host Contro... | 18    | sdhci_pci  | AB7375BCE4 |
| 8086:1911 | 103c:832a | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 18    |            | 8B699D7E6C |
| 1180:0592 | 1025:0121 | Ricoh      | R5C592 Memory Stick Bus H... | 17    | r592       | CFBA4082BB |
| 1180:0592 | 1025:0126 | Ricoh      | R5C592 Memory Stick Bus H... | 17    | r592       | F7695ADD11 |
| 1180:0852 | 1025:0121 | Ricoh      | xD-Picture Card Controller   | 17    | r852       | CFBA4082BB |
| 1180:0852 | 1025:0126 | Ricoh      | xD-Picture Card Controller   | 17    | r852       | F7695ADD11 |
| 197b:2392 | 103c:179b | JMicron... | SD/MMC Host Controller       | 17    | sdhci_pci  | ED317797F0 |
| 197b:2392 | 17aa:3976 | JMicron... | SD/MMC Host Controller       | 17    | sdhci_pci  | DF1A1447C6 |
| 197b:2393 | 17aa:3976 | JMicron... | MS Host Controller           | 17    | jmb38x_ms  | DF1A1447C6 |
| 197b:2394 | 17aa:3976 | JMicron... | xD Host Controller           | 17    |            | DF1A1447C6 |
| 1180:0592 | 1043:1317 | Ricoh      | R5C592 Memory Stick Bus H... | 16    | r592       | B304C61746 |
| 1180:0843 | 1043:1317 | Ricoh      | R5C843 MMC Host Controller   | 16    | sdhci_pci  | B304C61746 |
| 1180:e823 | 1179:0001 | Ricoh      | PCIe SDXC/MMC Host Contro... | 16    | sdhci_pci  | 4398E73607 |
| 8086:15bf | 2222:1111 | Intel      | JHL6240 Thunderbolt 3 NHI... | 16    | thunder... | C15E0482CA |
| 8086:3190 | 1043:1de0 | Intel      | Celeron/Pentium Silver Pr... | 16    |            | AAAC90F58C |
| 1180:0592 | 1043:1877 | Ricoh      | R5C592 Memory Stick Bus H... | 15    | r592       | CB27B32040 |
| 1180:0592 | 1043:1897 | Ricoh      | R5C592 Memory Stick Bus H... | 15    | r592       | 96E310C22E |
| 1180:0852 | 1043:1877 | Ricoh      | xD-Picture Card Controller   | 15    | r852       | CB27B32040 |
| 1180:0852 | 1043:1897 | Ricoh      | xD-Picture Card Controller   | 15    | r852       | 96E310C22E |
| 14e4:16be | 1025:0605 | Broadco... | BCM57765/57785 MS Card Re... | 15    |            | 4BBB490EBC |
| 14e4:16bf | 1025:0605 | Broadco... | BCM57765/57785 xD-Picture... | 15    |            | 4BBB490EBC |
| 197b:2382 | 103c:3628 | JMicron... | SD/MMC Host Controller       | 15    | sdhci_pci  | E09686C315 |
| 197b:2382 | 17aa:212e | JMicron... | SD/MMC Host Controller       | 15    | sdhci_pci  | 2AFD83B0D3 |
| 197b:2383 | 103c:3628 | JMicron... | MS Host Controller           | 15    | jmb38x_ms  | E09686C315 |
| 197b:2383 | 17aa:212f | JMicron... | MS Host Controller           | 15    | jmb38x_ms  | 2AFD83B0D3 |
| 197b:2384 | 103c:3628 | JMicron... | xD Host Controller           | 15    |            | E09686C315 |
| 197b:2384 | 17aa:2130 | JMicron... | xD Host Controller           | 15    |            | 2AFD83B0D3 |
| 197b:2392 | 103c:161c | JMicron... | SD/MMC Host Controller       | 15    | sdhci_pci  | 6AE9888758 |
| 1180:e822 | 17aa:21fa | Ricoh      | MMC/SD Host Controller       | 14    | sdhci_pci  | DB9250D9E0 |
| 1180:0592 | 1043:14e7 | Ricoh      | R5C592 Memory Stick Bus H... | 13    | r592       | D9970BDA58 |
| 1180:0852 | 1043:14e7 | Ricoh      | xD-Picture Card Controller   | 13    | r852       | D9970BDA58 |
| 1180:e823 | 17aa:21da | Ricoh      | PCIe SDXC/MMC Host Contro... | 13    | sdhci_pci  | 23DAC0F1B6 |
| 1180:e823 | 17aa:21fa | Ricoh      | PCIe SDXC/MMC Host Contro... | 13    | sdhci_pci  | C9FFBA0281 |
| 197b:2392 | 103c:17ab | JMicron... | SD/MMC Host Controller       | 13    | sdhci_pci  | 3B64B265CF |
| 1180:0592 | 1028:01bd | Ricoh      | R5C592 Memory Stick Bus H... | 12    | r592       | 586A6A9F8A |
| 1180:0592 | 103c:30cf | Ricoh      | R5C592 Memory Stick Bus H... | 12    | r592       | 084F7E13DA |
| 1180:0592 | 1043:1767 | Ricoh      | R5C592 Memory Stick Bus H... | 12    | r592       | 4137AC8F54 |
| 1180:0592 | 104d:9035 | Ricoh      | R5C592 Memory Stick Bus H... | 12    | r592       | A3C4D07088 |
| 1180:0592 | 1179:ff1c | Ricoh      | R5C592 Memory Stick Bus H... | 12    | r592       | 588EAD6870 |
| 1180:0852 | 1028:01bd | Ricoh      | xD-Picture Card Controller   | 12    | r852       | 586A6A9F8A |
| 1180:0852 | 103c:30cf | Ricoh      | xD-Picture Card Controller   | 12    | r852       | 084F7E13DA |
| 1180:0852 | 1043:1767 | Ricoh      | xD-Picture Card Controller   | 12    | r852       | 4137AC8F54 |
| 1180:0852 | 1179:ff1c | Ricoh      | xD-Picture Card Controller   | 12    | r852       | 588EAD6870 |
| 197b:2382 | 103c:3603 | JMicron... | SD/MMC Host Controller       | 12    | sdhci_pci  | 9CE29D0583 |
| 197b:2383 | 103c:3603 | JMicron... | MS Host Controller           | 12    | jmb38x_ms  | 9CE29D0583 |
| 197b:2384 | 103c:3603 | JMicron... | xD Host Controller           | 12    |            | 9CE29D0583 |
| 8086:1911 | 1028:087c | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 12    |            | 7A9639F003 |
| 8086:1911 | 103c:84a6 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 12    |            | 1A3504B63C |
| 1180:0592 | 1043:1517 | Ricoh      | R5C592 Memory Stick Bus H... | 11    | r592       | FAECBEFA9B |
| 1180:0592 | 1043:1777 | Ricoh      | R5C592 Memory Stick Bus H... | 11    | r592       | 9B7F075594 |
| 1180:0852 | 1043:1517 | Ricoh      | xD-Picture Card Controller   | 11    | r852       | FAECBEFA9B |
| 1180:e822 | 17aa:21f6 | Ricoh      | MMC/SD Host Controller       | 11    | sdhci_pci  | 7DA7A083D7 |
| 1180:e823 | 17aa:21cf | Ricoh      | PCIe SDXC/MMC Host Contro... | 10    | sdhci_pci  | E7A16D4FC1 |
| 197b:2382 | 103c:3659 | JMicron... | SD/MMC Host Controller       | 10    | sdhci_pci  | AFAAE2AA59 |
| 197b:2383 | 103c:3659 | JMicron... | MS Host Controller           | 10    | jmb38x_ms  | AFAAE2AA59 |
| 197b:2384 | 103c:3659 | JMicron... | xD Host Controller           | 10    |            | AFAAE2AA59 |
| 197b:2392 | 103c:162b | JMicron... | SD/MMC Host Controller       | 10    | sdhci_pci  | FAF97CF550 |
| 8086:1911 | 1025:1264 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 10    |            | F3941C8871 |
| 8086:1911 | 17aa:5068 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 10    |            | CE2A6FB934 |
| 8086:1911 | 1d72:1701 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 10    |            | A159026F22 |
| 1180:0592 | 103c:30bb | Ricoh      | R5C592 Memory Stick Bus H... | 9     | r592       | FB7F51216E |
| 1180:0852 | 103c:30bb | Ricoh      | xD-Picture Card Controller   | 9     | r852       | FB7F51216E |
| 1180:e232 | 104d:9095 | Ricoh      | PCIe Memory Stick Host Co... | 9     |            | 3F62942EFE |
| 1180:e822 | 17aa:21cf | Ricoh      | MMC/SD Host Controller       | 9     | sdhci_pci  | 977C44B97A |
| 197b:2382 | 103c:30f4 | JMicron... | SD/MMC Host Controller       | 9     | sdhci_pci  | DDA054B15D |

### Tv card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1131:7133 | 1461:a836 | Philips... | SAA7131/SAA7133/SAA7135 V... | 3     | saa7134    | 1CE26C391A |
| 14f1:5b7a | 1179:0110 | Conexan... | CX23418 Single-Chip MPEG-... | 2     | cx18       | 3E0ED41BC7 |
| 14f1:8852 | 1461:d939 | Conexan... | CX23885 PCI Video and Aud... | 2     | cx23885    | 8E5499B7A2 |
| 1131:7133 | 0000:5201 | Philips... | SAA7131/SAA7133/SAA7135 V... | 1     | saa7134    | C5FECF0E37 |
| 1131:7133 | 1461:e836 | Philips... | SAA7131/SAA7133/SAA7135 V... | 1     | saa7134    | 8A814A5779 |
| 1131:7133 | 1461:f636 | Philips... | SAA7131/SAA7133/SAA7135 V... | 1     | saa7134    | E814DA247A |
| 1131:7133 | 16be:0009 | Philips... | SAA7131/SAA7133/SAA7135 V... | 1     | saa7134    | EFDFFC9FB6 |
| 14f1:5b7a | 1179:0030 | Conexan... | CX23418 Single-Chip MPEG-... | 1     | cx18       | B5DB9CE313 |
| 14f1:5b7a | 1179:0031 | Conexan... | CX23418 Single-Chip MPEG-... | 1     | cx18       | AE0DBDDFF1 |
| 4444:0016 | 1179:0001 | Interne... | iTVC16 (CX23416) Video De... | 1     | ivtv       | D5D7DAB02F |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e26 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 262   | ehci_hc... | 891002E8F2 |
| 8086:1e2d | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 262   | ehci_hc... | 891002E8F2 |
| 8086:1e31 | 17aa:3977 | Intel      | 7 Series/C210 Series Chip... | 255   | xhci_pci   | 891002E8F2 |
| 8086:27c8 | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 169   | uhci_hcd   | 6A0513EC8D |
| 8086:27c9 | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 169   | uhci_hcd   | 6A0513EC8D |
| 8086:27ca | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 169   | uhci_hcd   | 6A0513EC8D |
| 8086:27cc | 1043:83ad | Intel      | NM10/ICH7 Family USB2 EHC... | 169   | ehci_hc... | 6A0513EC8D |
| 8086:1c26 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 164   | ehci_hc... | A7618091FB |
| 8086:1c2d | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 164   | ehci_hc... | A7618091FB |
| 1b21:1042 | 1043:1059 | ASMedia... | ASM1042 SuperSpeed USB Ho... | 154   | xhci_pci   | 826F5492EB |
| 8086:27cb | 1043:83ad | Intel      | NM10/ICH7 Family USB UHCI... | 154   | uhci_hcd   | 6A0513EC8D |
| 8086:9d2f | 1043:201f | Intel      | Sunrise Point-LP USB 3.0 ... | 152   | xhci_hcd   | B6B40DE397 |
| 8086:9c31 | 1043:201f | Intel      | 8 Series USB xHCI HC         | 96    | xhci_pci   | FDD61F096B |
| 8086:9c31 | 17aa:3978 | Intel      | 8 Series USB xHCI HC         | 88    | xhci_hcd   | AFD92BF265 |
| 8086:3b34 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 85    | ehci_hc... | 49783F833C |
| 8086:3b3c | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 85    | ehci_hc... | 49783F833C |
| 8086:9c26 | 17aa:3978 | Intel      | 8 Series USB EHCI #1         | 85    | ehci_hc... | AFD92BF265 |
| 8086:1c26 | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 80    | ehci_hc... | 6B25B8982D |
| 8086:1c2d | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 80    | ehci_hc... | 6B25B8982D |
| 8086:1e26 | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 80    | ehci_hc... | F28D18F3E9 |
| 8086:1e2d | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 80    | ehci_hc... | F28D18F3E9 |
| 8086:2934 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 79    | uhci_hcd   | FDAB3CF92F |
| 8086:2935 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 79    | uhci_hcd   | FDAB3CF92F |
| 8086:2936 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 79    | uhci_hcd   | FDAB3CF92F |
| 8086:2937 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 79    | uhci_hcd   | FDAB3CF92F |
| 8086:2938 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 79    | uhci_hcd   | FDAB3CF92F |
| 8086:2939 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 79    | uhci_hcd   | FDAB3CF92F |
| 8086:293a | 17aa:20f1 | Intel      | 82801I (ICH9 Family) USB2... | 79    | ehci_hc... | FDAB3CF92F |
| 8086:293c | 17aa:20f1 | Intel      | 82801I (ICH9 Family) USB2... | 79    | ehci_hc... | FDAB3CF92F |
| 8086:22b5 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 77    | xhci_hcd   | 514C494F7F |
| 8086:9c26 | 1043:201f | Intel      | 8 Series USB EHCI #1         | 77    | ehci_hc... | FDD61F096B |
| 8086:3b34 | 17aa:2163 | Intel      | 5 Series/3400 Series Chip... | 75    | ehci_hc... | DA5E944C6C |
| 8086:3b34 | 17aa:38b8 | Intel      | 5 Series/3400 Series Chip... | 75    | ehci_hc... | 62697BF35B |
| 8086:3b3c | 17aa:2163 | Intel      | 5 Series/3400 Series Chip... | 75    | ehci_hc... | DA5E944C6C |
| 8086:3b3c | 17aa:38aa | Intel      | 5 Series/3400 Series Chip... | 75    | ehci_hc... | 62697BF35B |
| 8086:2934 | 17aa:3a14 | Intel      | 82801I (ICH9 Family) USB ... | 74    | uhci_hcd   | 601D53F9EB |
| 8086:2935 | 17aa:3a15 | Intel      | 82801I (ICH9 Family) USB ... | 74    | uhci_hcd   | 601D53F9EB |
| 8086:2936 | 17aa:3a16 | Intel      | 82801I (ICH9 Family) USB ... | 74    | uhci_hcd   | 601D53F9EB |
| 8086:293a | 17aa:3a17 | Intel      | 82801I (ICH9 Family) USB2... | 74    | ehci_hc... | 601D53F9EB |
| 8086:293c | 17aa:3a0c | Intel      | 82801I (ICH9 Family) USB2... | 74    | ehci_hc... | 601D53F9EB |
| 8086:2937 | 17aa:3a09 | Intel      | 82801I (ICH9 Family) USB ... | 73    | uhci_hcd   | 601D53F9EB |
| 8086:8c26 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 72    | ehci_hc... | 262BB6B100 |
| 8086:8c2d | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 72    | ehci_hc... | 262BB6B100 |
| 8086:8c31 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 72    | xhci_pci   | 262BB6B100 |
| 8086:2938 | 17aa:3a0a | Intel      | 82801I (ICH9 Family) USB ... | 70    | uhci_hcd   | 601D53F9EB |
| 8086:1e26 | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 69    | ehci_hc... | CE3DDF28FC |
| 8086:1e2d | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 69    | ehci_hc... | CE3DDF28FC |
| 8086:1e31 | 17aa:5002 | Intel      | 7 Series/C210 Series Chip... | 69    | xhci_pci   | CE3DDF28FC |
| 8086:2939 | 17aa:3a0b | Intel      | 82801I (ICH9 Family) USB ... | 69    | uhci_hcd   | 601D53F9EB |
| 8086:1c26 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 65    | ehci_hc... | 8579BA1B16 |
| 8086:1c2d | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 65    | ehci_hc... | 8579BA1B16 |
| 8086:2830 | 1025:011f | Intel      | 82801H (ICH8 Family) USB ... | 64    | uhci_hcd   | 7387D70AD5 |
| 8086:2831 | 1025:011f | Intel      | 82801H (ICH8 Family) USB ... | 64    | uhci_hcd   | 7387D70AD5 |
| 8086:2832 | 1025:011f | Intel      | 82801H (ICH8 Family) USB ... | 64    | uhci_hcd   | 7387D70AD5 |
| 8086:2834 | 1025:011f | Intel      | 82801H (ICH8 Family) USB ... | 64    | uhci_hcd   | 7387D70AD5 |
| 8086:2835 | 1025:011f | Intel      | 82801H (ICH8 Family) USB ... | 64    | uhci_hcd   | 7387D70AD5 |
| 8086:2836 | 1025:011f | Intel      | 82801H (ICH8 Family) USB2... | 64    | ehci_hc... | 7387D70AD5 |
| 8086:283a | 1025:011f | Intel      | 82801H (ICH8 Family) USB2... | 64    | ehci_hc... | 7387D70AD5 |
| 8086:9cb1 | 1043:201f | Intel      | Wildcat Point-LP USB xHCI... | 64    | xhci_pci   | F8E8617476 |
| 8086:1e26 | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 63    | ehci_hc... | 6478022B75 |
| 8086:1e2d | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 63    | ehci_hc... | 6478022B75 |
| 8086:1e31 | 1025:0647 | Intel      | 7 Series/C210 Series Chip... | 63    | xhci_pci   | 6478022B75 |
| 8086:1e26 | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 62    | ehci_hc... | E67DFC255A |
| 8086:1e2d | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 62    | ehci_hc... | E67DFC255A |
| 8086:1e26 | 1043:124d | Intel      | 7 Series/C216 Chipset Fam... | 61    | ehci_hc... | 0F8CE4DCC0 |
| 8086:1e2d | 1043:124d | Intel      | 7 Series/C216 Chipset Fam... | 61    | ehci_hc... | 0F8CE4DCC0 |
| 8086:1e31 | 1043:124d | Intel      | 7 Series/C210 Series Chip... | 61    | xhci_pci   | 0F8CE4DCC0 |
| 8086:1c26 | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 60    | ehci_hc... | 826F5492EB |
| 8086:1c2d | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 60    | ehci_hc... | 826F5492EB |
| 8086:3b34 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 56    | ehci_hc... | D023F50697 |
| 8086:3b3c | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 56    | ehci_hc... | D023F50697 |
| 8086:27c8 | 1025:0349 | Intel      | NM10/ICH7 Family USB UHCI... | 51    | uhci_hcd   | 8CE41DB531 |
| 8086:27c9 | 1025:0349 | Intel      | NM10/ICH7 Family USB UHCI... | 51    | uhci_hcd   | 8CE41DB531 |
| 8086:27ca | 1025:0349 | Intel      | NM10/ICH7 Family USB UHCI... | 51    | uhci_hcd   | 8CE41DB531 |
| 8086:27cb | 1025:0349 | Intel      | NM10/ICH7 Family USB UHCI... | 51    | uhci_hcd   | 8CE41DB531 |
| 8086:27cc | 1025:0349 | Intel      | NM10/ICH7 Family USB2 EHC... | 51    | ehci_hc... | 8CE41DB531 |
| 8086:2830 | 17aa:20aa | Intel      | 82801H (ICH8 Family) USB ... | 47    | uhci_hcd   | 7F41843359 |
| 8086:2831 | 17aa:20aa | Intel      | 82801H (ICH8 Family) USB ... | 47    | uhci_hcd   | 7F41843359 |
| 8086:2834 | 17aa:20aa | Intel      | 82801H (ICH8 Family) USB ... | 47    | uhci_hcd   | 7F41843359 |
| 8086:2835 | 17aa:20aa | Intel      | 82801H (ICH8 Family) USB ... | 47    | uhci_hcd   | 7F41843359 |
| 8086:2836 | 17aa:20ab | Intel      | 82801H (ICH8 Family) USB2... | 47    | ehci_hc... | 7F41843359 |
| 8086:283a | 17aa:20ab | Intel      | 82801H (ICH8 Family) USB2... | 47    | ehci_hc... | 7F41843359 |
| 8086:a12f | 1043:201f | Intel      | 100 Series/C230 Series Ch... | 47    | xhci_hcd   | C53DF5F083 |
| 8086:0f35 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 46    | xhci_hcd   | 0994A3EEB3 |
| 8086:1e26 | 1043:14c7 | Intel      | 7 Series/C216 Chipset Fam... | 46    | ehci_hc... | 9A401175B3 |
| 8086:1e26 | 17aa:5011 | Intel      | 7 Series/C216 Chipset Fam... | 46    | ehci_hc... | 65D329A2C6 |
| 8086:1e2d | 1043:14c7 | Intel      | 7 Series/C216 Chipset Fam... | 46    | ehci_hc... | 9A401175B3 |
| 8086:1e2d | 17aa:5011 | Intel      | 7 Series/C216 Chipset Fam... | 46    | ehci_hc... | 65D329A2C6 |
| 8086:1e31 | 1043:14c7 | Intel      | 7 Series/C210 Series Chip... | 46    | xhci_pci   | 9A401175B3 |
| 8086:1e31 | 1043:201f | Intel      | 7 Series/C210 Series Chip... | 45    | xhci_hcd   | EFA97B65E3 |
| 1022:7808 | 17aa:3801 | AMD        | FCH USB EHCI Controller      | 44    | ehci_hc... | 760B445B08 |
| 1022:7814 | 17aa:3801 | AMD        | FCH USB XHCI Controller      | 44    | xhci_pci   | 760B445B08 |
| 1b73:1000 | 1043:1039 | Fresco ... | FL1000G USB 3.0 Host Cont... | 44    | xhci_pci   | 89BB311DBD |
| 8086:1c26 | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 44    | ehci_hc... | EE56C112BB |
| 8086:1c2d | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 44    | ehci_hc... | EE56C112BB |
| 8086:1e26 | 1043:201f | Intel      | 7 Series/C216 Chipset Fam... | 44    | ehci_hc... | EFA97B65E3 |
| 8086:1e2d | 1043:201f | Intel      | 7 Series/C216 Chipset Fam... | 44    | ehci_hc... | EFA97B65E3 |
| 8086:1e31 | 17aa:5011 | Intel      | 7 Series/C210 Series Chip... | 44    | xhci_pci   | 65D329A2C6 |
| 8086:2934 | 1043:1867 | Intel      | 82801I (ICH9 Family) USB ... | 44    | uhci_hcd   | 38190AD2E1 |
| 8086:2935 | 1043:1867 | Intel      | 82801I (ICH9 Family) USB ... | 44    | uhci_hcd   | 38190AD2E1 |

### Wireless controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:7360 | 8086:0020 | Intel      | XMM7360 LTE Advanced Modem   | 1     |            | 57C89FEBD9 |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:5260 | 1028:0831 | Realtek... | RTS5260 PCI Express Card ... | 4     | rtsx_pci   | F72215BFC0 |
| 8086:31d6 | 0000:0000 | Intel      | Gemini Lake PCI Express R... | 4     | shpchp     | 5A0A25C9FF |
| 8086:31d7 | 0000:0000 | Intel      | Gemini Lake PCI Express R... | 4     | shpchp     | 5A0A25C9FF |
| 1002:6900 | 03ea:1af4 | AMD        | Topaz XT [Radeon R7 M260/... | 3     | amdgpu     | 23C8F78D60 |
| 1aea:6625 | 103c:8478 | Alcor M... | Alcor Micro PCIe Card Reader | 3     |            | AD2AA3B388 |
| 1002:694e | 1002:694e | AMD        | Polaris 22 XL [Radeon RX ... | 1     | amdgpu     | F5FDC69851 |
| 17a0:9750 | 17aa:2279 | Genesys... | GL9750 SD Host Controller    | 1     |            | 93D5C57FFC |
| 1aea:6625 | 103c:83aa | Alcor M... | Alcor Micro PCIe Card Reader | 1     |            | 62C7769C30 |
| 8086:31d8 | 0000:0000 | Intel      | Gemini Lake PCI Express R... | 1     | shpchp     | 58FC691B81 |
| 8086:31da | 0000:0000 | Intel      | Gemini Lake PCI Express R... | 1     | shpchp     | 58FC691B81 |
| 8086:31db | 0000:0000 | Intel      | Gemini Lake PCI Express R... | 1     | shpchp     | 58FC691B81 |
| 8086:3b4e | 0000:0000 | Intel      | 5 Series/3400 Series Chip... | 1     | shpchp     | B642835279 |
| 8086:5ad6 | 0000:0000 | Intel      | Celeron N3350/Pentium N42... | 1     | pcieport   | FAE89FAE49 |
| 8086:9d2f | 14c0:0062 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 87AC0729E6 |
| 8086:a110 | 0000:0000 | Intel      | 100 Series/C230 Series Ch... | 1     | pcieport   | C8A8910A82 |

