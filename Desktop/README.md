Most popular PCI devices in Desktops
====================================

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Desktops ](#pci-devices)
   * [ Access bus ](#access-bus-pci)
   * [ Bluetooth ](#bluetooth-pci)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Dma controller ](#dma-controller-pci)
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

### Access bus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1106:303a | 1106:3038 | VIA Tec... | ACCESS Bus                   | 1     |            | C9A1706533 |

### Bluetooth (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1814:3298 | 103c:18ec | Ralink     | RT3290 Bluetooth             | 17    | rtbt       | AA243A819D |
| 1814:3298 | 1a3b:2787 | Ralink     | RT3290 Bluetooth             | 4     |            | 375A7150DE |
| 1814:3298 | 103c:191c | Ralink     | RT3290 Bluetooth             | 1     |            | 3CF5084317 |
| 1814:3298 | 1814:3298 | Ralink     | RT3290 Bluetooth             | 1     |            | EF1E6295A8 |
| 1814:3298 | 1a3b:2987 | Ralink     | RT3290 Bluetooth             | 1     |            | 1D26C2B648 |

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:4384 |           | AMD        | SBx00 PCI to PCI Bridge      | 4932  |            | 77FCB9CF4A |
| 1022:1200 |           | AMD        | Family 10h Processor Hype... | 3344  |            | 4F82621017 |
| 1022:1201 |           | AMD        | Family 10h Processor Addr... | 3344  |            | 4F82621017 |
| 1022:1202 |           | AMD        | Family 10h Processor DRAM... | 3344  | amd64_e... | 4F82621017 |
| 1022:1203 |           | AMD        | Family 10h Processor Misc... | 3344  | k10temp    | 4F82621017 |
| 1022:1204 |           | AMD        | Family 10h Processor Link... | 3344  |            | 4F82621017 |
| 1022:1452 |           | AMD        | Family 17h (Models 00h-1f... | 3293  |            | F544511E0A |
| 1022:1460 |           | AMD        | Family 17h (Models 00h-0f... | 2291  |            | D88D9DB618 |
| 1022:1461 |           | AMD        | Family 17h (Models 00h-0f... | 2291  |            | D88D9DB618 |
| 1022:1462 |           | AMD        | Family 17h (Models 00h-0f... | 2291  |            | D88D9DB618 |
| 1022:1463 |           | AMD        | Family 17h (Models 00h-0f... | 2291  | k10temp    | D88D9DB618 |
| 1022:1464 |           | AMD        | Family 17h (Models 00h-0f... | 2291  |            | D88D9DB618 |
| 1022:1465 |           | AMD        | Family 17h (Models 00h-0f... | 2291  |            | D88D9DB618 |
| 1022:1466 |           | AMD        | Family 17h (Models 00h-0f... | 2291  |            | D88D9DB618 |
| 1022:1467 |           | AMD        | Family 17h (Models 00h-0f... | 2291  |            | D88D9DB618 |
| 1022:1600 |           | AMD        | Family 15h Processor Func... | 2205  |            | 77FCB9CF4A |
| 1022:1601 |           | AMD        | Family 15h Processor Func... | 2205  |            | 77FCB9CF4A |
| 1022:1602 |           | AMD        | Family 15h Processor Func... | 2205  |            | 77FCB9CF4A |
| 1022:1603 |           | AMD        | Family 15h Processor Func... | 2205  | k10temp    | 77FCB9CF4A |
| 1022:1604 |           | AMD        | Family 15h Processor Func... | 2205  | fam15h_... | 77FCB9CF4A |
| 1022:1605 |           | AMD        | Family 15h Processor Func... | 2205  |            | 77FCB9CF4A |
| 1022:1482 |           | AMD        | Starship/Matisse PCIe Dum... | 2157  | vfio_pci   | 97C17F738A |
| 1022:43c7 | 1b21:3306 | AMD        | 400 Series Chipset PCIe Port | 2106  | pcieport   | 97C17F738A |
| 1002:439d | 1002:439d | AMD        | SB7x0/SB8x0/SB9x0 LPC hos... | 2092  |            | 77FCB9CF4A |
| 1022:1440 |           | AMD        | Matisse Device 24: Functi... | 2081  |            | 97C17F738A |
| 1022:1441 |           | AMD        | Matisse Device 24: Functi... | 2081  |            | 97C17F738A |
| 1022:1442 |           | AMD        | Matisse Device 24: Functi... | 2081  |            | 97C17F738A |
| 1022:1443 |           | AMD        | Matisse Device 24: Functi... | 2081  | k10temp    | 97C17F738A |
| 1022:1444 |           | AMD        | Matisse Device 24: Functi... | 2081  |            | 97C17F738A |
| 1022:1445 |           | AMD        | Matisse Device 24: Functi... | 2081  |            | 97C17F738A |
| 1022:1446 |           | AMD        | Matisse Device 24: Functi... | 2081  |            | 97C17F738A |
| 1022:1447 |           | AMD        | Matisse Device 24: Functi... | 2081  |            | 97C17F738A |
| 1022:43c6 | 1b21:0201 | AMD        | 400 Series Chipset PCIe B... | 1894  | pcieport   | 97C17F738A |
| 1022:43b4 | 1b21:3306 | AMD        | 300 Series Chipset PCIe Port | 1772  | pcieport   | F544511E0A |
| 1022:1100 |           | AMD        | K8 [Athlon64/Opteron] Hyp... | 1636  |            | 32F7B77B77 |
| 1022:1101 |           | AMD        | K8 [Athlon64/Opteron] Add... | 1636  |            | 32F7B77B77 |
| 1022:1102 |           | AMD        | K8 [Athlon64/Opteron] DRA... | 1636  | amd64_e... | 32F7B77B77 |
| 1022:1103 |           | AMD        | K8 [Athlon64/Opteron] Mis... | 1636  | k8temp     | 32F7B77B77 |
| 1022:1454 | 1022:1454 | AMD        | Family 17h (Models 00h-0f... | 1619  | pcieport   | D88D9DB618 |
| 1022:780f |           | AMD        | FCH PCI Bridge               | 1606  |            | 8961CA91B3 |
| 1022:1484 | 1022:1484 | AMD        | Starship/Matisse Internal... | 1581  | pcieport   | 97C17F738A |
| 8086:244e | 1458:5000 | Intel      | 82801 PCI Bridge             | 1572  |            | 43A5D97DD3 |
| 1b21:1080 | 1043:8489 | ASMedia... | ASM1083/1085 PCIe to PCI ... | 1399  | shpchp     | 11EBF0D551 |
| 1022:790e | 1458:5001 | AMD        | FCH LPC Bridge               | 1348  |            | F544511E0A |
| 1022:1453 | 1022:1453 | AMD        | Family 17h (Models 00h-0f... | 1301  | pcieport   | D88D9DB618 |
| 1002:43a0 | 1002:0000 | AMD        | SB700/SB800/SB900 PCI to ... | 1290  | pcieport   | 9F527DED3C |
| 1002:5a14 | 1002:5a14 | AMD        | RD9x0/RX980 Host Bridge      | 1124  | ati_agp    | 77FCB9CF4A |
| 1002:5a16 | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 1092  | pcieport   | 77FCB9CF4A |
| 8086:0c01 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 1078  | pcieport   | 9A23DF55D8 |
| 8086:0c00 | 1043:8534 | Intel      | 4th Gen Core Processor DR... | 1068  | hsw_uncore | 9A23DF55D8 |
| 1022:57ad |           | AMD        | Matisse Switch Upstream      | 1065  | pcieport   | 0619809B36 |
| 8086:1901 | 1043:8694 | Intel      | 6th-10th Gen Core Process... | 1045  | pcieport   | 11EBF0D551 |
| 1002:5a18 | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 1029  | pcieport   | 77FCB9CF4A |
| 8086:1c10 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1010  | shpchp     | EA164260EB |
| 1022:15e8 |           | AMD        | Raven/Raven2 Device 24: F... | 1005  |            | F544511E0A |
| 1022:15e9 |           | AMD        | Raven/Raven2 Device 24: F... | 1005  |            | F544511E0A |
| 1022:15ea |           | AMD        | Raven/Raven2 Device 24: F... | 1005  |            | F544511E0A |
| 1022:15eb |           | AMD        | Raven/Raven2 Device 24: F... | 1005  | k10temp    | F544511E0A |
| 1022:15ec |           | AMD        | Raven/Raven2 Device 24: F... | 1005  |            | F544511E0A |
| 1022:15ed |           | AMD        | Raven/Raven2 Device 24: F... | 1005  |            | F544511E0A |
| 1022:15ee |           | AMD        | Raven/Raven2 Device 24: F... | 1005  |            | F544511E0A |
| 1022:15ef |           | AMD        | Raven/Raven2 Device 24: F... | 1005  |            | F544511E0A |
| 8086:244e | 1043:8179 | Intel      | 82801 PCI Bridge             | 1000  |            | 5889B752F5 |
| 8086:244e |           | Intel      | 82801 PCI Bridge             | 999   | shpchp     | CD3697BD15 |
| 8086:27b8 | 1043:8179 | Intel      | 82801GB/GR (ICH7 Family) ... | 999   | lpc_ich    | 5889B752F5 |
| 8086:27d0 | 1043:8179 | Intel      | NM10/ICH7 Family PCI Expr... | 982   | shpchp     | 5889B752F5 |
| 1022:1400 |           | AMD        | Family 15h (Models 10h-1f... | 893   |            | E03FD39AD4 |
| 1022:1401 |           | AMD        | Family 15h (Models 10h-1f... | 893   |            | E03FD39AD4 |
| 1022:1402 |           | AMD        | Family 15h (Models 10h-1f... | 893   |            | E03FD39AD4 |
| 1022:1403 |           | AMD        | Family 15h (Models 10h-1f... | 893   | k10temp    | E03FD39AD4 |
| 1022:1404 |           | AMD        | Family 15h (Models 10h-1f... | 893   |            | E03FD39AD4 |
| 1022:1405 |           | AMD        | Family 15h (Models 10h-1f... | 893   |            | E03FD39AD4 |
| 8086:244e | 1849:244e | Intel      | 82801 PCI Bridge             | 849   | pcieport   | 87C40FCD51 |
| 8086:244e | 1458:8892 | Intel      | 82801 PCI Bridge             | 843   |            | E0277E3530 |
| 1022:1483 | 1022:1453 | AMD        | Starship/Matisse GPP Bridge  | 829   | pcieport   | 0619809B36 |
| 1022:57a4 | 1022:1484 | AMD        | Matisse PCIe GPP Bridge      | 828   | pcieport   | 0619809B36 |
| 1002:439d | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 LPC hos... | 786   |            | 67B53F9BDB |
| 8086:27d2 | 1043:8179 | Intel      | NM10/ICH7 Family PCI Expr... | 772   | shpchp     | 5889B752F5 |
| 1022:43a0 | 1022:0000 | AMD        | Hudson PCI to PCI bridge ... | 771   | pcieport   | 8961CA91B3 |
| 8086:8c10 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 759   | pcieport   | 9A23DF55D8 |
| 1022:1483 | 1022:1234 | AMD        | Starship/Matisse GPP Bridge  | 732   | pcieport   | 97C17F738A |
| 8086:27b8 | 1458:5001 | Intel      | 82801GB/GR (ICH7 Family) ... | 732   | lpc_ich    | 43A5D97DD3 |
| 1022:790e | 1043:8747 | AMD        | FCH LPC Bridge               | 726   |            | 115EC5ECA4 |
| 8086:0101 | 1043:844d | Intel      | Xeon E3-1200/2nd Generati... | 724   | shpchp     | EA164260EB |
| 8086:0c00 | 1458:5000 | Intel      | 4th Gen Core Processor DR... | 724   | hsw_uncore | E187B3F207 |
| 1022:1453 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 722   | pcieport   | 115EC5ECA4 |
| 1022:15db | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 722   | pcieport   | F544511E0A |
| 1022:1450 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 720   | ryzen_smu  | 115EC5ECA4 |
| 8086:0100 | 1043:844d | Intel      | 2nd Generation Core Proce... | 719   | snb_uncore | EA164260EB |
| 1022:1450 | 1022:1450 | AMD        | Family 17h (Models 00h-0f... | 718   |            | D88D9DB618 |
| 1002:1478 |           | AMD        | Navi 10 XL Upstream Port ... | 714   | pcieport   | B8D0E81636 |
| 1002:1479 | 1002:1479 | AMD        | Navi 10 XL Downstream Por... | 714   | pcieport   | B8D0E81636 |
| 8086:1901 | 1458:5000 | Intel      | 6th-10th Gen Core Process... | 700   | pcieport   | 6BC1B9DCC9 |
| 8086:1e10 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 700   | shpchp     | BA117FEF7E |
| 8086:244e | 1458:5001 | Intel      | 82801 PCI Bridge             | 697   | pcieport   | 912C8764EF |
| 8086:1c1a | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 673   | shpchp     | 7D2B37E6E1 |
| 1022:790e | 1043:87c0 | AMD        | FCH LPC Bridge               | 665   |            | 97C17F738A |
| 1002:5a1c | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 660   | pcieport   | 77FCB9CF4A |
| 1022:15dc | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 654   | pcieport   | F544511E0A |
| 8086:a118 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 648   | pcieport   | 11EBF0D551 |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:522a | 1458:1000 | Realtek... | RTS522A PCI Express Card ... | 23    | rtsx_pci   | E0A36977D5 |
| 10ec:525a | 1028:07ee | Realtek... | RTS525A PCI Express Card ... | 12    | rtsx_pci   | 38CD4647D5 |
| 10ec:5209 | 103c:2ac3 | Realtek... | RTS5209 PCI Express Card ... | 9     | rtsx_pci   | 902963AE8F |
| 10ec:525a | 1734:122e | Realtek... | RTS525A PCI Express Card ... | 9     | rtsx_pci   | CF3B2F2089 |
| 10ec:5209 | 103c:2adc | Realtek... | RTS5209 PCI Express Card ... | 8     | rtsx_pci   | E4BFDDB8D9 |
| 10ec:5209 | 103c:2af0 | Realtek... | RTS5209 PCI Express Card ... | 8     | rtsx_pci   | 54077E8D9B |
| 10ec:5229 | 103c:2b38 | Realtek... | RTS5229 PCI Express Card ... | 8     | rtsx_pci   | FAA262C47B |
| 10ec:5229 | 17aa:366b | Realtek... | RTS5229 PCI Express Card ... | 8     | rtsx_pci   | C3D601D88E |
| 10ec:5209 | 103c:3399 | Realtek... | RTS5209 PCI Express Card ... | 5     | rtsx_pci   | 4085344B20 |
| 10ec:5289 | 10ec:5289 | Realtek... | RTL8411 PCI Express Card ... | 5     | rtsx_pci   | 1FD5FA69E2 |
| 10ec:5209 | 103c:2ac5 | Realtek... | RTS5209 PCI Express Card ... | 4     | rtsx_pci   | 07FE8046CF |
| 10ec:5229 | 103c:2b43 | Realtek... | RTS5229 PCI Express Card ... | 4     | rtsx_pci   | C5450B77F0 |
| 10ec:5229 | 1b0a:016c | Realtek... | RTS5229 PCI Express Card ... | 4     | rtsx_pci   | 0DF79259C1 |
| 10ec:525a | 10ec:525a | Realtek... | RTS525A PCI Express Card ... | 4     | rtsx_pci   | 68A723FA33 |
| 10ec:5209 | 17aa:3623 | Realtek... | RTS5209 PCI Express Card ... | 3     | rtsx_pci   | E5E08BD1ED |
| 10ec:522a | 10ec:522a | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | 3D30BC1C51 |
| 1aea:6621 | 1aea:6621 | Alcor M... | AU6621 PCI-E Flash card r... | 3     | alcor_pci  | FE9015C15E |
| 10ec:5209 | 1025:8020 | Realtek... | RTS5209 PCI Express Card ... | 2     | rtsx_pci   | 2165F3ED5A |
| 10ec:5209 | 103c:2ae9 | Realtek... | RTS5209 PCI Express Card ... | 2     | rtsx_pci   | 2F1276F263 |
| 10ec:5209 | 103c:2aed | Realtek... | RTS5209 PCI Express Card ... | 2     | rtsx_pci   | FFEE72581F |
| 10ec:5229 | 103c:2af8 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 73FE3F4EE7 |
| 10ec:5229 | 103c:2af9 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 28B99207FE |
| 10ec:5229 | 103c:2afa | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | B134DF65E0 |
| 10ec:5229 | 103c:2b0b | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | A051170E5F |
| 10ec:5229 | 103c:2b3c | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 9FF313AD1F |
| 10ec:5249 | 10ec:5249 | Realtek... | RTS5249 PCI Express Card ... | 2     | rtsx_pci   | B9FAD5E7DD |
| 10ec:525a | 1734:1249 | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx_pci   | 9320FE9EED |
| 10ec:5209 | 103c:2ac7 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 7A9D5AF1CE |
| 10ec:5209 | 103c:2af5 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 7D17193EB2 |
| 10ec:5209 | 103c:2b02 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 74E79527D5 |
| 10ec:5209 | 10cf:15e0 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 15202A6CAE |
| 10ec:5209 | 17aa:3620 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 0C3E26BCE7 |
| 10ec:5209 | 1b0a:015e | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | EA65434637 |
| 10ec:5229 | 1025:0946 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 3B4F88C98F |
| 10ec:5229 | 1025:1073 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | E9D0E3D9D4 |
| 10ec:5229 | 103c:2af6 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 824A23BF00 |
| 10ec:5229 | 103c:2b09 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 44E3728303 |
| 10ec:5229 | 103c:2b15 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 24DD32836D |
| 10ec:5229 | 10ec:5229 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | CAF59FFB4A |
| 10ec:5229 | 1849:5229 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 95EFD1E9A2 |
| 10ec:5229 | 1b0a:018a | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | CAA7CA382E |
| 10ec:5249 | 1462:1113 | Realtek... | RTS5249 PCI Express Card ... | 1     | rtsx_pci   | 8F5D0B74C4 |
| 10ec:525a | 1028:085a | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | B7022F0A45 |
| 10ec:525a | 1028:0860 | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | 038A085F01 |
| 10ec:525a | 1028:09aa | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | 32F5299C09 |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0753 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Co-... | 62    |            | 739D1AE9B7 |
| 10de:03f4 | 1462:7597 | Nvidia     | MCP61 SMU                    | 37    |            | 6F22F99F9F |
| 10de:0753 | 1849:0753 | Nvidia     | MCP78S [GeForce 8200] Co-... | 35    |            | 9B0A7F242B |
| 10de:03f4 | 1462:7309 | Nvidia     | MCP61 SMU                    | 34    |            | 78A89AB514 |
| 10de:0753 | 1043:82e2 | Nvidia     | MCP78S [GeForce 8200] Co-... | 20    |            | 4B4D8AA09F |
| 10de:0aa3 | 1025:0222 | Nvidia     | MCP79 Co-processor           | 13    | nvidia     | 093D03CAF5 |
| 10de:07da | 1025:0137 | Nvidia     | MCP73 Co-processor           | 12    |            | 8533331911 |
| 10de:0753 | 1025:0153 | Nvidia     | MCP78S [GeForce 8200] Co-... | 11    |            | 94CDE50175 |
| 10de:03f4 |           | Nvidia     | MCP61 SMU                    | 10    |            | 1D4F1E8E8B |
| 10de:0753 | 1025:0228 | Nvidia     | MCP78S [GeForce 8200] Co-... | 10    |            | 08681C1E94 |
| 10de:0753 | 1043:82e8 | Nvidia     | MCP78S [GeForce 8200] Co-... | 10    |            | 9DAF1B6529 |
| 10de:03f4 | 1043:8234 | Nvidia     | MCP61 SMU                    | 9     |            | 56DB54E530 |
| 10de:0543 | 1849:0543 | Nvidia     | MCP67 Co-processor           | 9     |            | 1C6B15BC7B |
| 10de:0aa3 | 1462:7621 | Nvidia     | MCP79 Co-processor           | 9     | nvidia     | 9D7D398CC1 |
| 10de:0aa3 | 1025:0168 | Nvidia     | MCP79 Co-processor           | 8     | nvidia     | 547C1BF7D7 |
| 10de:0753 | 103c:2a81 | Nvidia     | MCP78S [GeForce 8200] Co-... | 7     |            | 97B60B69C9 |
| 10de:0753 | 1043:82e7 | Nvidia     | MCP78S [GeForce 8200] Co-... | 7     |            | 6AA0488E7E |
| 10de:0753 | 1565:340b | Nvidia     | MCP78S [GeForce 8200] Co-... | 7     |            | 4F82621017 |
| 10de:0aa3 | 1b0a:0074 | Nvidia     | MCP79 Co-processor           | 7     | nvidia     | 484AF2A752 |
| 10de:07da | 1462:7366 | Nvidia     | MCP73 Co-processor           | 5     |            | ADA828F120 |
| 10de:07da | 1462:736b | Nvidia     | MCP73 Co-processor           | 5     |            | C554C3A77F |
| 10de:0aa3 | 1849:0aa3 | Nvidia     | MCP79 Co-processor           | 5     | nvidia     | B68D01F3AE |
| 10de:03f4 | 1849:03f4 | Nvidia     | MCP61 SMU                    | 4     |            | 5751926628 |
| 10de:0753 | 1025:0157 | Nvidia     | MCP78S [GeForce 8200] Co-... | 4     |            | B942B5FB12 |
| 10de:0753 | 1025:0227 | Nvidia     | MCP78S [GeForce 8200] Co-... | 4     |            | 4C4B83CA44 |
| 10de:07da | 1462:7504 | Nvidia     | MCP73 Co-processor           | 4     |            | 56863BBCA2 |
| 10de:07da | 1849:07da | Nvidia     | MCP73 Co-processor           | 4     |            | AC70970005 |
| 10de:0aa3 | 103c:2a95 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | 0E1FA2C583 |
| 10de:0aa3 | 105b:0d52 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | 3F5D854E2F |
| 10de:0753 | 1025:0462 | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | BEB8F313F7 |
| 10de:0753 | 103c:2a9e | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | C1329912E7 |
| 10de:0753 | 1462:7612 | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | 905C03A3D4 |
| 10de:07da | 10de:07d7 | Nvidia     | MCP73 Co-processor           | 3     |            | 974A439CC4 |
| 10de:0aa3 | 1043:83e2 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 1452DE25DA |
| 10de:0aa3 | 1043:83e9 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 0D0D8B9925 |
| 10de:0aa3 | 1043:83f9 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 57C3CE82B7 |
| 10de:0aa3 | 19da:0ae5 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | C18FD136A9 |
| 10de:0aa3 | 19da:a108 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 35A29512AC |
| 10de:0753 | 1019:1b67 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 35BFD13207 |
| 10de:0753 | 1019:2646 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | BF975A328C |
| 10de:0753 | 1019:2666 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 5C15176A57 |
| 10de:0753 | 1043:8332 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | FC54031F7E |
| 10de:0753 | 1462:6720 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | C630018FEA |
| 10de:0753 | 1462:7375 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 07A001660F |
| 10de:0753 | 1462:7578 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 8DB5C49C90 |
| 10de:0aa3 | 103c:2aa1 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | C2FD4F3C01 |
| 10de:0aa3 | 1043:8356 | Nvidia     | MCP79 Co-processor           | 2     |            | AAF6FAFAD6 |
| 10de:0aa3 | 1458:0aa3 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | 6C871AB8BE |
| 10de:0aa3 | 1b0a:000f | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | BF054CFF0C |
| 8086:19e2 | 8086:19e2 | Intel      | Atom Processor C3000 Seri... | 2     |            | 50B6A72C0C |
| 10de:0753 | 10de:cb84 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 236A9A94B1 |
| 10de:0753 | 1462:7511 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 87456F207B |
| 10de:0753 | 1631:e03b | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | E6D16C44AA |
| 10de:0753 | 19da:a100 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 4AF8E42B5A |
| 10de:07da | 105b:0d1f | Nvidia     | MCP73 Co-processor           | 1     |            | 87EF8BCE11 |
| 10de:07da | 10de:cb73 | Nvidia     | MCP73 Co-processor           | 1     |            | 51821B9A72 |
| 10de:07da | 1462:366f | Nvidia     | MCP73 Co-processor           | 1     |            | 238EC9B2AC |
| 10de:07da | 1462:736a | Nvidia     | MCP73 Co-processor           | 1     |            | 650300C6BF |
| 10de:0aa3 | 1028:02b6 | Nvidia     | MCP79 Co-processor           | 1     |            | 85AAFD27C3 |
| 10de:0aa3 | 103c:2a7c | Nvidia     | MCP79 Co-processor           | 1     |            | 9A3F224628 |
| 10de:0aa3 | 103c:2a83 | Nvidia     | MCP79 Co-processor           | 1     | nvidia     | 226AA094E2 |
| 10de:0aa3 | 10de:cb79 | Nvidia     | MCP79 Co-processor           | 1     |            | C1B9864823 |
| 10de:0aa3 | 19da:a119 | Nvidia     | MCP79 Co-processor           | 1     |            | A6CC2E15FF |
| 10de:0aa3 | 1b0a:0071 | Nvidia     | MCP79 Co-processor           | 1     |            | 2582663F1E |
| 10de:0aa3 | a0a0:0802 | Nvidia     | MCP79 Co-processor           | 1     |            | B778A6096A |
| 1bbf:0003 | 1bbf:0007 | Maxeler... | MAX3                         | 1     |            | 76E711B112 |
| 8086:1f18 | 15d9:0820 | Intel      | Atom processor C2000 QAT     | 1     |            | DAE3697FF8 |
| 8086:1f18 | 8086:0000 | Intel      | Atom processor C2000 QAT     | 1     |            | E889E472C5 |
| 8086:225c | 8086:2500 | Intel      | Xeon Phi coprocessor SE10... | 1     | mic        | DAE871210E |
| 8086:225c | 8086:7d95 | Intel      | Xeon Phi coprocessor SE10... | 1     | mic_host   | A37475889B |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1c3a | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1004  | mei_me     | EA164260EB |
| 8086:8c3a | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 789   | mei_me     | 9A23DF55D8 |
| 8086:1e3a | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 696   | mei_me     | BA117FEF7E |
| 8086:a13a | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 630   | mei_me     | 11EBF0D551 |
| 8086:1c3a | 1458:1c3a | Intel      | 6 Series/C200 Series Chip... | 628   | mei_me     | EE570B7B0C |
| 8086:8c3a | 1458:1c3a | Intel      | 8 Series/C220 Series Chip... | 512   | mei_me     | E187B3F207 |
| 8086:1e3a | 1458:1c3a | Intel      | 7 Series/C216 Chipset Fam... | 503   | mei_me     | 89F6EB0671 |
| 8086:a2ba | 1043:8694 | Intel      | 200 Series PCH CSME HECI #1  | 389   | mei_me     | 2696477C0C |
| 8086:a2ba | 1458:1c3a | Intel      | 200 Series PCH CSME HECI #1  | 364   | mei_me     | F91A20DD51 |
| 8086:a13a | 1458:1c3a | Intel      | 100 Series/C230 Series Ch... | 356   | mei_me     | 5474165F7B |
| 8086:a360 | 1043:8694 | Intel      | Cannon Lake PCH HECI Cont... | 301   | mei_me     | 36EBF65D44 |
| 8086:8cba | 1043:8534 | Intel      | 9 Series Chipset Family M... | 290   | mei_me     | 0D40DAA834 |
| 8086:a360 | 1458:1c3a | Intel      | Cannon Lake PCH HECI Cont... | 257   | mei_me     | E8B8B03EBD |
| 8086:8c3a | 1849:8c3a | Intel      | 8 Series/C220 Series Chip... | 248   | mei_me     | F36828F316 |
| 8086:1c3a | 1849:1c3a | Intel      | 6 Series/C200 Series Chip... | 243   | mei_me     | EFEC95A916 |
| 8086:8cba | 1458:1c3a | Intel      | 9 Series Chipset Family M... | 220   | mei_me     | DF13F72A9A |
| 8086:a13a | 1849:a13a | Intel      | 100 Series/C230 Series Ch... | 172   | mei_me     | 3A2A9BD626 |
| 8086:1e3a | 1849:1e3a | Intel      | 7 Series/C216 Chipset Fam... | 171   | mei_me     | E7EBAD7358 |
| 8086:8c3a | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 161   | mei_me     | 75E2E357A3 |
| 8086:a2ba | 1849:a2ba | Intel      | 200 Series PCH CSME HECI #1  | 146   | mei_me     | A8F84AEA94 |
| 8086:1e3a | 1028:0577 | Intel      | 7 Series/C216 Chipset Fam... | 144   | mei_me     | 4DAF9FDC0D |
| 8086:a2ba | 1043:872f | Intel      | 200 Series PCH CSME HECI #1  | 131   | mei_me     | C1BF9C169D |
| 8086:1d3a | 1043:84ef | Intel      | C600/X79 series chipset M... | 123   | mei_me     | F0DC31F93D |
| 8086:1c3a | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 106   | mei_me     | DB42B43D7E |
| 8086:8c3a | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 105   | mei_me     | 0FC3ABDB1C |
| 8086:8cba | 1849:8cba | Intel      | 9 Series Chipset Family M... | 103   | mei_me     | B203387A22 |
| 8086:a360 | 1849:a360 | Intel      | Cannon Lake PCH HECI Cont... | 102   | mei_me     | 839B20476A |
| 8086:3b64 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 99    | mei_me     | 3C0A297EDE |
| 8086:8d3a | 1043:8600 | Intel      | C610/X99 series chipset M... | 95    | mei_me     | E456864B06 |
| 8086:29b4 | 1028:0211 | Intel      | 82Q35 Express MEI Controller | 91    | mei_me     | 962E0B75E4 |
| 8086:3b64 | 1458:3b64 | Intel      | 5 Series/3400 Series Chip... | 91    | mei_me     | 3F02DD61E1 |
| 8086:1e3a | 103c:3397 | Intel      | 7 Series/C216 Chipset Fam... | 90    | mei_me     | 9C1343DD9B |
| 8086:2e14 | 1028:0420 | Intel      | 4 Series Chipset HECI Con... | 84    | mei_me     | 340184FB36 |
| 8086:8c3a | 1028:0612 | Intel      | 8 Series/C220 Series Chip... | 81    | mei_me     | 4C34BAF1DC |
| 8086:2e14 | 1028:027f | Intel      | 4 Series Chipset HECI Con... | 79    | mei_me     | 8F0C6ED152 |
| 8086:1c3a | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 72    | mei_me     | CA302C374F |
| 8086:1e3a | 103c:339a | Intel      | 7 Series/C216 Chipset Fam... | 72    | mei_me     | BA7CCF28B7 |
| 8086:1c3a | 1028:047e | Intel      | 6 Series/C200 Series Chip... | 71    | mei_me     | 959E3DDE54 |
| 8086:1c3a | 1028:04f5 | Intel      | 6 Series/C200 Series Chip... | 71    | mei_me     | 00CE09B473 |
| 8086:1c3a | 1028:0585 | Intel      | 6 Series/C200 Series Chip... | 70    | mei_me     | F146C310D6 |
| 8086:1e3a | 1462:7758 | Intel      | 7 Series/C216 Chipset Fam... | 69    | mei_me     | 8755040EA2 |
| 8086:1c3a | 103c:2abf | Intel      | 6 Series/C200 Series Chip... | 67    | mei_me     | 57FFE115AC |
| 8086:1c3a | 103c:1495 | Intel      | 6 Series/C200 Series Chip... | 64    | mei_me     | 660C4FF2ED |
| 8086:8c3a | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 64    | mei_me     | D8309CFECF |
| 8086:a13a | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 64    | mei_me     | C007D839E7 |
| 8086:06e0 | 1043:8694 | Intel      | Comet Lake HECI Controller   | 61    | mei_me     | BBA08D40AD |
| 8086:1c3a | 8086:1c3a | Intel      | 6 Series/C200 Series Chip... | 61    | mei_me     | 73BFADA83A |
| 8086:3b64 | 103c:2a9c | Intel      | 5 Series/3400 Series Chip... | 61    | mei_me     | 9A3C939249 |
| 8086:2e14 | 103c:3048 | Intel      | 4 Series Chipset HECI Con... | 59    | mei_me     | 39204D22AE |
| 8086:2e14 | 1734:114c | Intel      | 4 Series Chipset HECI Con... | 57    | mei_me     | 8159354A14 |
| 8086:8c3a | 17aa:3098 | Intel      | 8 Series/C220 Series Chip... | 57    | mei_me     | 2767965856 |
| 8086:8c3a | 103c:18e7 | Intel      | 8 Series/C220 Series Chip... | 56    | mei_me     | 9844F6635C |
| 8086:319a | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 55    | mei_me     | 3E408E9EAD |
| 8086:1c3a | 103c:1497 | Intel      | 6 Series/C200 Series Chip... | 54    | mei_me     | 7FA5AD3E42 |
| 8086:8c3a | 1734:11ea | Intel      | 8 Series/C220 Series Chip... | 54    | mei_me     | F2BC4B7196 |
| 8086:a3ba | 1043:8694 | Intel      | Comet Lake PCH-V Manageme... | 51    | mei_me     | 5125306D59 |
| 8086:3b64 | 8086:0036 | Intel      | 5 Series/3400 Series Chip... | 49    | mei_me     | 15FF525EFC |
| 14f1:2f20 | 14f1:200f | Conexan... | HSF 56k Data/Fax Modem       | 48    |            | D8137AB8A4 |
| 8086:1c3a | 1019:3190 | Intel      | 6 Series/C200 Series Chip... | 48    | mei_me     | AAB06F55BD |
| 8086:a13a | 1734:121d | Intel      | 100 Series/C230 Series Ch... | 48    | mei_me     | 4E988AF2DF |
| 8086:8c3a | 1462:7816 | Intel      | 8 Series/C220 Series Chip... | 47    | mei_me     | 01196F313E |
| 8086:29b4 | 103c:2818 | Intel      | 82Q35 Express MEI Controller | 46    | mei_me     | C0E9143E13 |
| 8086:8c3a | 1028:05b7 | Intel      | 8 Series/C220 Series Chip... | 46    | mei_me     | 2B158EA18F |
| 8086:1c3a | 1462:7680 | Intel      | 6 Series/C200 Series Chip... | 45    | mei_me     | 23D2285E8A |
| 8086:1c3a | 1734:11ba | Intel      | 6 Series/C200 Series Chip... | 45    | mei_me     | 17A4D716C5 |
| 8086:1e3a | 1734:11d6 | Intel      | 7 Series/C216 Chipset Fam... | 45    | mei_me     | 1F992DE6EB |
| 8086:1e3a | 1028:052c | Intel      | 7 Series/C216 Chipset Fam... | 44    | mei_me     | DD8DC2D85A |
| 8086:29c4 | 8086:5044 | Intel      | 82G33/G31/P35/P31 Express... | 43    | mei_me     | AF996AA861 |
| 8086:29d4 | 103c:281e | Intel      | 82Q33 Express MEI Controller | 42    | mei_me     | D3603FD2D2 |
| 8086:1c3a | 17aa:3070 | Intel      | 6 Series/C200 Series Chip... | 41    | mei_me     | 6983745C31 |
| 8086:a13a | 1462:7a15 | Intel      | 100 Series/C230 Series Ch... | 41    | mei_me     | B1186D53E5 |
| 8086:2e14 | 17aa:3048 | Intel      | 4 Series Chipset HECI Con... | 39    | mei_me     | 7E76E404EC |
| 8086:5a9a | 1849:5a9a | Intel      | Celeron N3350/Pentium N42... | 38    | mei_me     | 13396A7347 |
| 8086:a13a | 1462:7971 | Intel      | 100 Series/C230 Series Ch... | 38    | mei_me     | 2289424CAC |
| 8086:1e3a | 8086:1e3a | Intel      | 7 Series/C216 Chipset Fam... | 37    | mei_me     | 471FDFC5A9 |
| 8086:8c3a | 17aa:3097 | Intel      | 8 Series/C220 Series Chip... | 37    | mei_me     | 0C78C3EF80 |
| 8086:8d3a | 1458:7270 | Intel      | C610/X99 series chipset M... | 37    | mei_me     | 0C74B85F4C |
| 8086:a2ba | 1043:873c | Intel      | 200 Series PCH CSME HECI #1  | 37    | mei_me     | D5CDC97C3B |
| 8086:1e3a | 17aa:3083 | Intel      | 7 Series/C216 Chipset Fam... | 36    | mei_me     | C0B8E99E35 |
| 8086:8d3a | 1849:8d3a | Intel      | C610/X99 series chipset M... | 36    | mei_me     | 6FEB0AEC47 |
| 8086:1c3a | 1025:0492 | Intel      | 6 Series/C200 Series Chip... | 35    | mei_me     | 1CBEE8A7EF |
| 8086:2e14 | 103c:3646 | Intel      | 4 Series Chipset HECI Con... | 35    | mei_me     | 833B887480 |
| 8086:1c3a | 1025:0589 | Intel      | 6 Series/C200 Series Chip... | 34    | mei_me     | 2C05A7DB2C |
| 8086:2e14 | 103c:3034 | Intel      | 4 Series Chipset HECI Con... | 33    | mei_me     | D69CD77C4D |
| 8086:8c3a | 1028:0622 | Intel      | 8 Series/C220 Series Chip... | 33    | mei_me     | 3A544ADCC9 |
| 8086:1c3a | 8086:2017 | Intel      | 6 Series/C200 Series Chip... | 32    | mei_me     | 5B590117DD |
| 8086:1d3a | 103c:1589 | Intel      | C600/X79 series chipset M... | 32    | mei_me     | A4B0EBBEE2 |
| 8086:8c3a | 1025:0750 | Intel      | 8 Series/C220 Series Chip... | 32    | mei_me     | DB910234A6 |
| 8086:8c3a | 17aa:30a3 | Intel      | 8 Series/C220 Series Chip... | 32    | mei_me     | F5A0BFB5FD |
| 8086:8d3a | 1462:7885 | Intel      | C610/X99 series chipset M... | 31    | mei_me     | 09B0FBCF47 |
| 8086:a360 | 1025:1238 | Intel      | Cannon Lake PCH HECI Cont... | 31    | mei_me     | 5C8AF3A6F6 |
| 8086:a360 | 1462:7b98 | Intel      | Cannon Lake PCH HECI Cont... | 31    | mei_me     | 995EF5ECD6 |
| 14f1:2f20 | 14f1:200c | Conexan... | HSF 56k Data/Fax Modem       | 30    |            | BDCEFA45C2 |
| 8086:1c3a | 103c:1494 | Intel      | 6 Series/C200 Series Chip... | 30    | mei_me     | 646E6E27E3 |
| 8086:8cba | 1462:7917 | Intel      | 9 Series Chipset Family M... | 30    | mei_me     | 254C55FA75 |
| 8086:9d3a | 8086:1999 | Intel      | Sunrise Point-LP CSME HEC... | 30    | mei_me     | 9BC7AB87D1 |
| 8086:1c3a | 17aa:308c | Intel      | 6 Series/C200 Series Chip... | 29    | mei_me     | 749127A8A5 |
| 8086:1d3a | 1458:1c3a | Intel      | C600/X79 series chipset M... | 29    | mei_me     | 912C8764EF |
| 8086:29a4 | 8086:514d | Intel      | 82P965/G965 HECI Controller  | 29    | mei_me     | D76E4B9EC3 |
| 8086:2e14 | 103c:3035 | Intel      | 4 Series Chipset HECI Con... | 29    | mei_me     | EA009F77D1 |

### Dma controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1311:0801 | 0000:ffff | Videose... | DMA controller               | 1     |            | EAD04A61E4 |

### Dma controller (eisa dma) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0f06 | 8086:2056 | Intel      | Atom Processor Z36xxx/Z37... | 1     |            | D4408F7B0E |
| 8086:0f06 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | A211982E39 |
| 8086:0f40 | 8086:2056 | Intel      | Atom Processor Z36xxx/Z37... | 1     |            | D4408F7B0E |
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
| 13d0:2103 | 13d0:2103 | Techsan... | B2C2 FlexCopII DVB chip /... | 61    | b2c2_fl... | 17D284CE82 |
| 1131:7146 | 13c2:1018 | Philips... | SAA7146                      | 27    | budget     | 6028E5342C |
| 109e:0878 | 1822:0001 | Brooktree  | Bt878 Audio Capture          | 5     | bt878      | 39FB7FBFDD |
| 1131:7146 | 13c2:101a | Philips... | SAA7146                      | 5     | budget_ci  | D37856DC0A |
| 14f1:8802 | 0070:9002 | Conexan... | CX23880/1/2/3 PCI Video a... | 5     | cx88_dvb   | 1351C7B098 |
| 1131:7146 | 13c2:1019 | Philips... | SAA7146                      | 4     | budget_ci  | 7F15F19A9B |
| 109e:0878 | 11bd:001c | Brooktree  | Bt878 Audio Capture          | 3     | bt878      | BA214D2A0B |
| 1131:7146 | 13c2:0003 | Philips... | SAA7146                      | 3     | dvb_ttpci  | AF9735C8FD |
| 109e:0878 | 1461:0771 | Brooktree  | Bt878 Audio Capture          | 2     | bt878      | AB87264048 |
| 14f1:8802 | 17de:08a6 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx88_dv... | D932872569 |
| 195d:1105 | 195d:1105 |            | Ethernet controller          | 2     | dm1105     | 4AEC213A10 |
| 1131:7146 | 1131:4f56 | Philips... | SAA7146                      | 1     | budget_av  | B220FD9C11 |
| 1131:7146 | 13c2:000e | Philips... | SAA7146                      | 1     | dvb_ttpci  | 2A21A99A38 |
| 1131:7146 | 153b:1154 | Philips... | SAA7146                      | 1     | budget_av  | D949336ED1 |
| 1131:7146 | 153b:1156 | Philips... | SAA7146                      | 1     | budget_av  | E514F058FE |
| 1131:7146 | 1894:0022 | Philips... | SAA7146                      | 1     | budget_av  | 931BED40DE |
| 13d0:2103 | ffff:ffff | Techsan... | B2C2 FlexCopII DVB chip /... | 1     | b2c2_fl... | 7609423845 |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1456 | 1022:1456 | AMD        | Family 17h (Models 00h-0f... | 1614  | ccp        | D88D9DB618 |
| 1022:1486 | 1022:1486 | AMD        | Starship/Matisse Cryptogr... | 1009  | ccp        | 6056EAC50C |
| 1022:15df | 1022:15df | AMD        | Family 17h (Models 10h-1f... | 742   | ccp        | F544511E0A |
| 1022:1486 | 1043:87c0 | AMD        | Starship/Matisse Cryptogr... | 565   | ccp        | 97C17F738A |
| 1022:1456 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 521   | ccp        | 115EC5ECA4 |
| 1022:15df | 1043:876b | AMD        | Family 17h (Models 10h-1f... | 201   | ccp        | AB4B1B7A15 |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 186   |            | 4654691B7A |
| 1022:1486 | 1043:8808 | AMD        | Starship/Matisse Cryptogr... | 82    | ccp        | 20115EE05D |
| 1022:1486 | 1462:7c02 | AMD        | Starship/Matisse Cryptogr... | 79    | ccp        | A04EB698F8 |
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 66    | mei_txe    | 465523934D |
| 8086:0f18 | 1849:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 57    | mei_txe    | BA2B52B494 |
| 1022:1456 | 1462:7c02 | AMD        | Family 17h (Models 00h-0f... | 50    | ccp        | 2229C9E9F6 |
| 1022:1486 | 1462:7b86 | AMD        | Starship/Matisse Cryptogr... | 49    | ccp        | A42F5B4313 |
| 1022:1456 | 1462:7b86 | AMD        | Family 17h (Models 00h-0f... | 40    | ccp        | 6787B45989 |
| 1022:1537 | 1022:1537 | AMD        | Kabini/Mullins PSP-Platfo... | 40    | ccp        | 4594F040E1 |
| 1022:1486 | 1462:7b89 | AMD        | Starship/Matisse Cryptogr... | 37    | ccp        | 43A19D8280 |
| 8086:0f18 | 1458:1c3a | Intel      | Atom Processor Z36xxx/Z37... | 33    | mei_txe    | 0FF0A247D9 |
| 1022:15df | 1462:7a38 | AMD        | Family 17h (Models 10h-1f... | 27    | ccp        | 3056DB282E |
| 1022:1456 | 1462:7a38 | AMD        | Family 17h (Models 00h-0f... | 26    | ccp        | 00A14A97A2 |
| 8086:2298 | 1458:1000 | Intel      | Atom/Celeron/Pentium Proc... | 24    | mei_txe    | E0A36977D5 |
| 1022:1456 | 1462:7b89 | AMD        | Family 17h (Models 00h-0f... | 23    | ccp        | 463432C55F |
| 8086:0f18 | 8086:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 23    | mei_txe    | 8AE91D28E1 |
| 8086:2298 | 1849:2298 | Intel      | Atom/Celeron/Pentium Proc... | 22    | mei_txe    | 6F289497FC |
| 1022:1486 | 1462:7b85 | AMD        | Starship/Matisse Cryptogr... | 20    | ccp        | B8D0E81636 |
| 1022:1486 | 1462:7a38 | AMD        | Starship/Matisse Cryptogr... | 19    | ccp        | ABF17F0C92 |
| 1022:15df | 1043:87e1 | AMD        | Family 17h (Models 10h-1f... | 19    | ccp        | D8274A2024 |
| 1022:1486 | 1043:87cb | AMD        | Starship/Matisse Cryptogr... | 18    | ccp        | 1F560968AB |
| 8086:0f18 | 1019:7ed4 | Intel      | Atom Processor Z36xxx/Z37... | 18    | mei_txe    | 69C12914CE |
| 1022:1486 | 1462:7c95 | AMD        | Starship/Matisse Cryptogr... | 17    | ccp        | 4A568F856E |
| 1022:15df | 1462:7c02 | AMD        | Family 17h (Models 10h-1f... | 17    | ccp        | A42BEE6110 |
| 8086:0f18 | 1025:085e | Intel      | Atom Processor Z36xxx/Z37... | 17    | mei_txe    | B25FAF16EA |
| 8086:0f18 | 1043:8534 | Intel      | Atom Processor Z36xxx/Z37... | 17    | mei_txe    | 560FD63326 |
| 8086:0f18 | 8086:2055 | Intel      | Atom Processor Z36xxx/Z37... | 17    | mei_txe    | 920E36BE7E |
| 8086:2298 | 1043:8534 | Intel      | Atom/Celeron/Pentium Proc... | 17    | mei_txe    | 714A70D40A |
| 1022:1486 | 1462:7c94 | AMD        | Starship/Matisse Cryptogr... | 16    | ccp        | 640C5ADFC3 |
| 1022:15df | 1462:7b86 | AMD        | Family 17h (Models 10h-1f... | 14    | ccp        | 9B273ADF50 |
| 1022:1456 | 1462:7b85 | AMD        | Family 17h (Models 00h-0f... | 13    | ccp        | 8176B777B9 |
| 1022:1578 | 17aa:364f | AMD        | Carrizo Platform Security... | 11    |            | 973E323F3C |
| 1022:1486 | 1043:87e2 | AMD        | Starship/Matisse Cryptogr... | 10    | ccp        | 76267FCBDA |
| 1022:1486 | 1462:7a40 | AMD        | Starship/Matisse Cryptogr... | 10    | ccp        | B2B10D4380 |
| 1022:15df | 1462:7b89 | AMD        | Family 17h (Models 10h-1f... | 10    | ccp        | 586195F9E8 |
| 8086:2298 | 1025:0953 | Intel      | Atom/Celeron/Pentium Proc... | 9     | mei_txe    | EDF84D2336 |
| 8086:2298 | 103c:821d | Intel      | Atom/Celeron/Pentium Proc... | 9     | mei_txe    | B67EBD33A8 |
| 8086:2298 | 17aa:30c9 | Intel      | Atom/Celeron/Pentium Proc... | 9     | mei_txe    | 174975E4F8 |
| 8086:0f18 | 1565:310e | Intel      | Atom Processor Z36xxx/Z37... | 8     | mei_txe    | AF163E54E9 |
| 1022:1456 | 1462:7a40 | AMD        | Family 17h (Models 00h-0f... | 7     | ccp        | BD8CB19ABD |
| 1022:15df | 1462:7a40 | AMD        | Family 17h (Models 10h-1f... | 7     | ccp        | D03D2796A0 |
| 8086:0f18 | 1028:068d | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | 25AF02542D |
| 8086:0f18 | 1458:1000 | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | CCAD01D04D |
| 8086:0f18 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | 85CE077799 |
| 8086:2298 | 1019:9bef | Intel      | Atom/Celeron/Pentium Proc... | 7     | mei_txe    | ED8391B5FA |
| 8086:2298 | 1458:1c3a | Intel      | Atom/Celeron/Pentium Proc... | 7     | mei_txe    | 2FD537312F |
| 1022:1578 | 17aa:3100 | AMD        | Carrizo Platform Security... | 6     |            | BBFCF94452 |
| 8086:2298 | 8086:2298 | Intel      | Atom/Celeron/Pentium Proc... | 6     | mei_txe    | 26905E1EBD |
| 1022:1456 | 1462:7b87 | AMD        | Family 17h (Models 00h-0f... | 5     | ccp        | 9B8F51B1D4 |
| 1022:15df | 1462:7b87 | AMD        | Family 17h (Models 10h-1f... | 5     |            | 02D89D2EE7 |
| 1022:1486 | 1028:098e | AMD        | Starship/Matisse Cryptogr... | 4     | ccp        | E1BC8D1CDD |
| 1022:1498 | 1022:1498 | AMD        | Starship/Matisse PTDMA       | 4     |            | EBCC16470F |
| 1022:1537 | 103c:2b29 | AMD        | Kabini/Mullins PSP-Platfo... | 4     | ccp        | 3161742F5A |
| 1022:15df | 17aa:3708 | AMD        | Family 17h (Models 10h-1f... | 4     | ccp        | F8BAB84CFF |
| 8086:0f18 | 1019:99cf | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 037E6E58E6 |
| 8086:0f18 | 105b:0db1 | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 177A7992A1 |
| 8086:0f18 | 1297:4019 | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 1FD5FA69E2 |
| 1022:1456 | 1462:7b90 | AMD        | Family 17h (Models 00h-0f... | 3     | ccp        | ABD9798AA8 |
| 1022:1486 | 17aa:1046 | AMD        | Starship/Matisse Cryptogr... | 3     | ccp        | 2C58A29C2A |
| 1022:15df | 103c:83e9 | AMD        | Family 17h (Models 10h-1f... | 3     | ccp        | A112F2F435 |
| 1022:15df | 103c:87d6 | AMD        | Family 17h (Models 10h-1f... | 3     | ccp        | BD63B276CE |
| 1022:15df | 1462:7b85 | AMD        | Family 17h (Models 10h-1f... | 3     | ccp        | 0548F9650B |
| 8086:0f18 | 1019:7ed1 | Intel      | Atom Processor Z36xxx/Z37... | 3     | mei_txe    | F6753A7B07 |
| 8086:0f18 | 1019:99ad | Intel      | Atom Processor Z36xxx/Z37... | 3     | mei_txe    | 49CFBBDD47 |
| 8086:0f18 | 1019:99f3 | Intel      | Atom Processor Z36xxx/Z37... | 3     | mei_txe    | B22810DA38 |
| 8086:0f18 | 103c:2b28 | Intel      | Atom Processor Z36xxx/Z37... | 3     | mei_txe    | 896A921FF8 |
| 8086:2298 | 1019:9af1 | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | 1069244654 |
| 8086:2298 | 1025:1064 | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | 12B9C02A39 |
| 1022:1456 | 103c:8399 | AMD        | Family 17h (Models 00h-0f... | 2     | ccp        | 733813E901 |
| 1022:1468 | 1022:1468 | AMD        | Zeppelin Cryptographic Co... | 2     | ccp        | 4C4AD9EBE5 |
| 1022:1486 | 1462:7c96 | AMD        | Starship/Matisse Cryptogr... | 2     | ccp        | 1DC1C27798 |
| 1022:1498 | 1849:1498 | AMD        | Starship/Matisse PTDMA       | 2     |            | EBCC16470F |
| 1022:1537 | 103c:21ef | AMD        | Kabini/Mullins PSP-Platfo... | 2     | ccp        | BC9D42DF4A |
| 1022:1537 | 103c:2240 | AMD        | Kabini/Mullins PSP-Platfo... | 2     | ccp        | 8D09C291C1 |
| 1022:1578 | 103c:805b | AMD        | Carrizo Platform Security... | 2     |            | 6C46F99EEF |
| 1022:1578 | 103c:8265 | AMD        | Carrizo Platform Security... | 2     |            | C530376A96 |
| 1022:1578 | 103c:8266 | AMD        | Carrizo Platform Security... | 2     |            | E903E5B250 |
| 1022:15df | 1019:a4cd | AMD        | Family 17h (Models 10h-1f... | 2     |            | 8EB8144AEB |
| 1022:15df | 1462:7c94 | AMD        | Family 17h (Models 10h-1f... | 2     | ccp        | 1DA678C883 |
| 1022:15df | 1e39:d009 | AMD        | Family 17h (Models 10h-1f... | 2     | ccp        | 5ED240BCDD |
| 8086:0f18 |           | Intel      | Atom Processor Z36xxx/Z37... | 2     | mei_txe    | 3B11488CA8 |
| 8086:2298 | 1025:101c | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | C31D382CD1 |
| 8086:2298 | 103c:2b46 | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | B7CD9F611B |
| 8086:2298 | 1462:7890 | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | EC0DD2E662 |
| 8086:2298 | 1565:3112 | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | 710471E54C |
| 8086:2298 | 8086:2066 | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | 64AD81C366 |
| 1022:1456 | 1019:9ce5 | AMD        | Family 17h (Models 00h-0f... | 1     | ccp        | 06776696F3 |
| 1022:1456 | 1019:9d10 | AMD        | Family 17h (Models 00h-0f... | 1     | ccp        | 277BBC0E9E |
| 1022:1456 | 1019:a412 | AMD        | Family 17h (Models 00h-0f... | 1     | ccp        | C47BA626E7 |
| 1022:1456 | 1019:a4cd | AMD        | Family 17h (Models 00h-0f... | 1     | ccp        | 8106DDD47F |
| 1022:1456 | 17aa:36e1 | AMD        | Family 17h (Models 00h-0f... | 1     | ccp        | 31F5158C61 |
| 1022:1456 | 1849:1456 | AMD        | Family 17h (Models 00h-0f... | 1     | ccp        | 4C4AD9EBE5 |
| 1022:1468 | 1849:1468 | AMD        | Zeppelin Cryptographic Co... | 1     | ccp        | 4C4AD9EBE5 |
| 1022:1486 | 1028:0a8b | AMD        | Starship/Matisse Cryptogr... | 1     | ccp        | 9F3FE00E5C |

### Entertainment encryption device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:2082 | 1022:2082 | AMD        | Geode LX AES Security Block  | 1     | geode_r... | 6D9551F87E |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1106:3044 | 1043:81fe | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 731   | firewir... | 4B4D8AA09F |
| 104c:8024 | 1458:1000 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 706   | firewir... | 5EBB861FEB |
| 1106:3044 | 1458:1000 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 236   | firewir... | 77FCB9CF4A |
| 1106:3403 | 1043:8384 | VIA Tec... | VT6315 Series Firewire Co... | 232   | firewir... | FA66471153 |
| 11c1:5811 | 1043:8294 | LSI        | FW322/323 [TrueFire] 1394... | 200   | firewir... | 102C78CA6B |
| 1106:3044 | 1106:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 188   | firewir... | 36FB4E2ABA |
| 1102:4001 | 1102:0010 | Creativ... | SB Audigy FireWire Port      | 153   | firewir... | A51030D9A0 |
| 1106:3403 | 1849:3403 | VIA Tec... | VT6315 Series Firewire Co... | 115   | firewir... | 4C10147742 |
| 104c:8023 | 1043:808b | Texas I... | TSB43AB22A IEEE-1394a-200... | 95    | firewir... | 34AB0FD5ED |
| 197b:2380 | 1043:8313 | JMicron... | IEEE 1394 Host Controller    | 64    | firewir... | 4D5F23E6BA |
| 104c:823f |           | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 63    | firewir... | CC088D7F17 |
| 1106:3403 | 103c:2a9c | VIA Tec... | VT6315 Series Firewire Co... | 51    | firewir... | 9A3C939249 |
| 1106:3403 | 1043:8374 | VIA Tec... | VT6315 Series Firewire Co... | 51    | firewir... | 00F250E5C2 |
| 104c:8023 | 1043:815b | Texas I... | TSB43AB22A IEEE-1394a-200... | 50    | firewir... | 926229BE87 |
| 11c1:5811 | 103c:2a6f | LSI        | FW322/323 [TrueFire] 1394... | 50    | firewir... | E051360964 |
| 11c1:5811 | 103c:1309 | LSI        | FW322/323 [TrueFire] 1394... | 41    | firewir... | 83C114D947 |
| 1106:3403 | 1106:3403 | VIA Tec... | VT6315 Series Firewire Co... | 37    | firewir... | ED22ADFD9F |
| 11c1:5811 | 103c:1589 | LSI        | FW322/323 [TrueFire] 1394... | 35    | firewir... | A4B0EBBEE2 |
| 1106:3044 | 1043:808a | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 31    | firewir... | E739F2F0BA |
| 104c:8023 | 8086:5044 | Texas I... | TSB43AB22A IEEE-1394a-200... | 30    | firewir... | AF996AA861 |
| 104c:823f | 3412:7856 | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 29    | firewir... | 0A228B18C1 |
| 1106:3044 | 1849:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 29    | firewir... | C008E87B1C |
| 104c:8023 | 8086:514d | Texas I... | TSB43AB22A IEEE-1394a-200... | 25    | firewir... | D76E4B9EC3 |
| 11c1:5811 | 11c1:5811 | LSI        | FW322/323 [TrueFire] 1394... | 24    | firewir... | 0767C99ABB |
| 11c1:5811 | 103c:158a | LSI        | FW322/323 [TrueFire] 1394... | 23    | firewir... | D70166F107 |
| 11c1:5811 | 103c:130a | LSI        | FW322/323 [TrueFire] 1394... | 21    | firewir... | EE9A2DA17C |
| 104c:8024 | 1019:8056 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 19    | firewir... | 1B1266E526 |
| 11c1:5811 | 1028:5811 | LSI        | FW322/323 [TrueFire] 1394... | 19    | firewir... | ACE51E66CB |
| 11c1:5811 | 1028:8010 | LSI        | FW322/323 [TrueFire] 1394... | 19    | firewir... | 0C5063C25C |
| 11c1:5811 | 103c:130b | LSI        | FW322/323 [TrueFire] 1394... | 19    | firewir... | DFA7EF3696 |
| 11c1:5811 | 103c:158b | LSI        | FW322/323 [TrueFire] 1394... | 19    | firewir... | E7D78D4E6C |
| 104c:8023 | 8086:4257 | Texas I... | TSB43AB22A IEEE-1394a-200... | 18    | firewir... | A760607F4E |
| 104c:8025 |           | Texas I... | TSB82AA2 IEEE-1394b Link ... | 18    | firewir... | 41C18A9562 |
| 197b:2380 | 197b:2380 | JMicron... | IEEE 1394 Host Controller    | 18    | firewir... | ECC0073F45 |
| 104c:8023 | 1028:026d | Texas I... | TSB43AB22A IEEE-1394a-200... | 17    | firewir... | 08F4C825CC |
| 1106:3044 | 103c:2a92 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 17    | firewir... | C3468E4972 |
| 11c1:5811 | 8086:2008 | LSI        | FW322/323 [TrueFire] 1394... | 17    | firewir... | 8FD2974998 |
| 1106:3044 | 1025:8010 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 16    | firewir... | 78FC18FCF4 |
| 104c:8023 | 1028:021d | Texas I... | TSB43AB22A IEEE-1394a-200... | 15    | firewir... | 0BA08ED8F7 |
| 1106:3044 | 1462:502d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 15    | firewir... | 2A2D112995 |
| 1106:3403 | 1028:040d | VIA Tec... | VT6315 Series Firewire Co... | 15    | firewir... | F2760185E3 |
| 11bd:0015 | 11bd:0022 | Pinnacl... | FireWire IEEE1394            | 15    | firewir... | E4F384C278 |
| 11c1:5811 | 103c:2a50 | LSI        | FW322/323 [TrueFire] 1394... | 15    | firewir... | 925EDCDDDC |
| 104c:8024 | 105b:0e0a | Texas I... | TSB43AB23 IEEE-1394a-2000... | 14    | firewir... | 1DE7D0104A |
| 1033:00f2 | 1033:00f2 | NEC Com... | uPD72874 [Firewarden] IEE... | 13    | firewir... | EAFAAED28A |
| 1106:3044 | 103c:2a24 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 13    | firewir... | E47DB7138D |
| 1106:3044 | 103c:2a6d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 13    | firewir... | F7EC16D7E7 |
| 11c1:5811 | 103c:2a6c | LSI        | FW322/323 [TrueFire] 1394... | 13    | firewir... | 78A4331611 |
| 104c:8023 | 10de:c55e | Texas I... | TSB43AB22A IEEE-1394a-200... | 12    | firewir... | CA151A6E5C |
| 1106:3044 | 1019:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 12    | firewir... | FBA2180097 |
| 1106:3044 | 1043:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 12    | firewir... | 58F6116852 |
| 11c1:5811 | 103c:2a5d | LSI        | FW322/323 [TrueFire] 1394... | 12    | firewir... | 9DA28A4AEC |
| 197b:2380 | 1462:522d | JMicron... | IEEE 1394 Host Controller    | 12    | firewir... | 1FBA25DBCF |
| 104c:8024 |           | Texas I... | TSB43AB23 IEEE-1394a-2000... | 11    | firewir... | BAF100CE1E |
| 1106:3044 | 103c:2a61 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 11    | firewir... | 50B1158D6D |
| 1106:3044 | 1106:0404 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 11    | firewir... | 49371E76EF |
| 1106:3044 | 17f2:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 11    | firewir... | 6F870BCCF3 |
| 1106:3403 | 1025:0153 | VIA Tec... | VT6315 Series Firewire Co... | 11    | firewir... | 94CDE50175 |
| 1106:3403 | 1025:024c | VIA Tec... | VT6315 Series Firewire Co... | 11    | firewir... | D6E0E0433A |
| 1106:3403 | 1025:0250 | VIA Tec... | VT6315 Series Firewire Co... | 11    | firewir... | 09D469F1FC |
| 11c1:5811 | 8086:1003 | LSI        | FW322/323 [TrueFire] 1394... | 11    | firewir... | 95642C55FC |
| 104c:8023 | 1849:8023 | Texas I... | TSB43AB22A IEEE-1394a-200... | 10    | firewir... | 4818C2EAE0 |
| 1106:3044 | 1043:82eb | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 10    | firewir... | FF9A9203BD |
| 11c1:5811 | 103c:2a5e | LSI        | FW322/323 [TrueFire] 1394... | 10    | firewir... | BDCEFA45C2 |
| 11c1:5811 | 103c:2a66 | LSI        | FW322/323 [TrueFire] 1394... | 10    | firewir... | AC7B2A7D3A |
| 11c1:5811 | 1734:1026 | LSI        | FW322/323 [TrueFire] 1394... | 10    | firewir... | E381B08FEC |
| 104c:8023 | 8086:4f43 | Texas I... | TSB43AB22A IEEE-1394a-200... | 9     | firewir... | 2E9A342427 |
| 11c1:5811 | 11bd:000e | LSI        | FW322/323 [TrueFire] 1394... | 9     | firewir... | 9149BE671F |
| 1033:00e7 | 1033:00ce | NEC Com... | uPD72873 [Firewarden] IEE... | 8     | firewir... | 8533331911 |
| 104c:8023 | 1028:0215 | Texas I... | TSB43AB22A IEEE-1394a-200... | 8     | firewir... | 5A53A4349A |
| 104c:8024 | 1028:1000 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 8     | firewir... | 523DACC90C |
| 104c:8235 | 5678:1234 | Texas I... | XIO2200A IEEE-1394a-2000 ... | 8     | firewir... | 91B6E1CB16 |
| 1106:3044 |           | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 8     | firewir... | CED2DCBAC9 |
| 1106:3044 | 1462:309d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 8     | firewir... | B50872CAF4 |
| 1106:3403 | 1462:640d | VIA Tec... | VT6315 Series Firewire Co... | 8     | firewir... | 5901E8C9E2 |
| 11bd:0015 | 11bd:0023 | Pinnacl... | FireWire IEEE1394            | 8     | firewir... | FD7DE4EB5A |
| 11c1:5811 | 103c:2a34 | LSI        | FW322/323 [TrueFire] 1394... | 8     | firewir... | F8D3CA460A |
| 197b:2380 | 1025:0168 | JMicron... | IEEE 1394 Host Controller    | 8     | firewir... | 547C1BF7D7 |
| 197b:2380 | 1462:7646 | JMicron... | IEEE 1394 Host Controller    | 8     | firewir... | 799BE90F9C |
| 197b:2380 | 2810:ac02 | JMicron... | IEEE 1394 Host Controller    | 8     | firewir... | 8563E0FB2C |
| 104c:8023 | 8086:424b | Texas I... | TSB43AB22A IEEE-1394a-200... | 7     | firewir... | 5604BE0F67 |
| 104c:8024 | 105b:0c9e | Texas I... | TSB43AB23 IEEE-1394a-2000... | 7     | firewir... | 652ED79C86 |
| 104c:8024 | 11bd:000e | Texas I... | TSB43AB23 IEEE-1394a-2000... | 7     | firewir... | 0B347A19E2 |
| 104c:8025 | 1458:1000 | Texas I... | TSB82AA2 IEEE-1394b Link ... | 7     | firewir... | 8AEDE202BC |
| 1106:3044 | 00ff:9a01 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 7     | firewir... | FA879EE1D2 |
| 1106:3044 | 0574:086c | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 7     | firewir... | 3BAB98FCF2 |
| 1106:3044 | 1462:376d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 7     | firewir... | FC4FD8BA0E |
| 1106:3403 | 1025:0158 | VIA Tec... | VT6315 Series Firewire Co... | 7     | firewir... | D6CB41706D |
| 1106:3403 | 1025:8010 | VIA Tec... | VT6315 Series Firewire Co... | 7     | firewir... | DDB03D82A0 |
| 1106:3403 | 103c:2a90 | VIA Tec... | VT6315 Series Firewire Co... | 7     | firewir... | 8DEBFEF4D1 |
| 1106:3403 | 1462:7616 | VIA Tec... | VT6315 Series Firewire Co... | 7     | firewir... | C3730DB7DD |
| 1106:3403 | 8086:4953 | VIA Tec... | VT6315 Series Firewire Co... | 7     | firewir... | 24893E9CC2 |
| 11c1:5811 | 1028:0249 | LSI        | FW322/323 [TrueFire] 1394... | 7     | firewir... | 85C12975E9 |
| 11c1:5811 | 103c:2a81 | LSI        | FW322/323 [TrueFire] 1394... | 7     | firewir... | 97B60B69C9 |
| 11c1:5811 | 1043:8259 | LSI        | FW322/323 [TrueFire] 1394... | 7     | firewir... | FA9AA5A2B0 |
| 11c1:5811 | 8086:2035 | LSI        | FW322/323 [TrueFire] 1394... | 7     | firewir... | B1A5DA541F |
| 104c:8023 |           | Texas I... | TSB43AB22A IEEE-1394a-200... | 6     | firewir... | AA0FE4677E |
| 104c:8023 | 103c:1306 | Texas I... | TSB43AB22A IEEE-1394a-200... | 6     | firewir... | 71B7E581A6 |
| 104c:8023 | 17aa:1023 | Texas I... | TSB43AB22A IEEE-1394a-200... | 6     | firewir... | 4ABBAF6F5B |
| 104c:8024 | 8086:544e | Texas I... | TSB43AB23 IEEE-1394a-2000... | 6     | firewir... | BCE3FDF194 |

### Flash memory (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1524:0510 | 1524:0510 | ENE Tec... | CB710 Memory Card Reader ... | 2     | cb710      | 932FA70B29 |
| 1524:0510 | 1043:1724 | ENE Tec... | CB710 Memory Card Reader ... | 1     | cb710      | 9FE6163CA2 |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1451 | 1022:1451 | AMD        | Family 17h (Models 00h-0f... | 1231  |            | D88D9DB618 |
| 1002:5a23 | 1002:5a23 | AMD        | RD890S/RD990 I/O Memory M... | 414   |            | 77FCB9CF4A |
| 1022:1419 | 1022:1419 | AMD        | Family 15h (Models 10h-1f... | 233   |            | E03FD39AD4 |
| 1002:5a23 | 1462:7693 | AMD        | RD890S/RD990 I/O Memory M... | 134   |            | D0FD1CE0E8 |
| 1022:1577 | 1022:1577 | AMD        | Family 15h (Models 60h-6f... | 112   |            | 4654691B7A |
| 1022:1423 | 1022:1423 | AMD        | Family 15h (Models 30h-3f... | 55    |            | C22E6D8669 |
| 1022:1419 | 1462:7721 | AMD        | Family 15h (Models 10h-1f... | 50    |            | A9971ED939 |
| 1022:1423 | 1462:7721 | AMD        | Family 15h (Models 30h-3f... | 37    |            | 01C5E2E798 |
| 1022:1423 | 1043:85cb | AMD        | Family 15h (Models 30h-3f... | 19    |            | 8961CA91B3 |
| 1002:5a23 | 1462:7640 | AMD        | RD890S/RD990 I/O Memory M... | 16    |            | 3AB1CD59AE |
| 1002:5a23 | 1458:5000 | AMD        | RD890S/RD990 I/O Memory M... | 15    |            | AB87264048 |
| 1022:1419 | 1462:7895 | AMD        | Family 15h (Models 10h-1f... | 15    |            | 4DC951C5ED |
| 1002:5a23 | 1462:7974 | AMD        | RD890S/RD990 I/O Memory M... | 10    |            | 9DB62B42E7 |
| 1022:1419 | 1043:8526 | AMD        | Family 15h (Models 10h-1f... | 7     |            | 4482A1FB69 |
| 1022:1423 | 1462:7895 | AMD        | Family 15h (Models 30h-3f... | 7     |            | 09A88027C8 |
| 1022:1419 | 1019:7c8d | AMD        | Family 15h (Models 10h-1f... | 4     |            | F04221E5DE |
| 1022:1419 | 1025:070b | AMD        | Family 15h (Models 10h-1f... | 4     |            | C87047835B |
| 1022:1419 | 1462:7900 | AMD        | Family 15h (Models 10h-1f... | 3     |            | 6F21980996 |
| 8086:19a2 | 8086:19a2 | Intel      | Atom Processor C3000 Seri... | 2     |            | 50B6A72C0C |
| 1022:1419 | 17aa:36a0 | AMD        | Family 15h (Models 10h-1f... | 1     |            | BA1A484E84 |
| 1022:1423 | 1462:7793 | AMD        | Family 15h (Models 30h-3f... | 1     |            | 54040FA02B |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0412 | 1458:d000 | Intel      | Xeon E3-1200 v3/4th Gen C... | 394   | i915       | E187B3F207 |
| 10de:128b | 1462:8c93 | Nvidia     | GK208B [GeForce GT 710]      | 349   | nvidia     | F7E3CD3E35 |
| 8086:0412 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 273   | i915       | 0D40DAA834 |
| 1002:67df | 1da2:e366 | AMD        | Ellesmere [Radeon RX 470/... | 214   | amdgpu     | 2E1659CD91 |
| 8086:0102 | 1043:844d | Intel      | 2nd Generation Core Proce... | 202   | i915       | E6F55FAAD0 |
| 8086:0102 | 1458:d000 | Intel      | 2nd Generation Core Proce... | 188   | i915       | 1237BE5BD5 |
| 1002:9616 | 1043:8388 | AMD        | RS780L [Radeon 3000]         | 178   | radeon     | EF97789A6A |
| 1002:15d8 | 1002:15d8 | AMD        | Picasso                      | 173   | amdgpu     | E5421C72D4 |
| 1002:15dd | 1002:15dd | AMD        | Raven Ridge [Radeon Vega ... | 162   | amdgpu     | FCFE2F037F |
| 8086:1912 | 1043:8694 | Intel      | HD Graphics 530              | 158   | i915       | 8AB1F1C2CF |
| 8086:0152 | 1458:d000 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 156   | i915       | E88DE55691 |
| 1002:67df | 1682:c580 | AMD        | Ellesmere [Radeon RX 470/... | 139   | amdgpu     | 11EBF0D551 |
| 10de:0a65 |           | Nvidia     | GT218 [GeForce 210]          | 137   | nouveau    | 5E2CE09E63 |
| 8086:5912 | 1043:8694 | Intel      | HD Graphics 630              | 135   | i915       | 11EBF0D551 |
| 8086:29c2 | 1043:82b0 | Intel      | 82G33/G31 Express Integra... | 131   | i915       | 5889B752F5 |
| 1002:67df | 1da2:e353 | AMD        | Ellesmere [Radeon RX 470/... | 129   | amdgpu     | 77FCB9CF4A |
| 10de:1c82 | 1462:8c96 | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 123   | nvidia     | C1BF9C169D |
| 10de:1d01 | 1462:8c98 | Nvidia     | GP108 [GeForce GT 1030]      | 122   | nvidia     | 229B36F7F9 |
| 8086:2e32 | 1043:836d | Intel      | 4 Series Chipset Integrat... | 122   | i915       | 2E99E6785B |
| 10de:03d6 | 1849:03d6 | Nvidia     | C61 [GeForce 7025 / nForc... | 118   | nouveau    | 0B81DF184D |
| 1002:9616 | 1458:d000 | AMD        | RS780L [Radeon 3000]         | 117   | radeon     | 765CD8D9A0 |
| 1002:67df | 1462:341b | AMD        | Ellesmere [Radeon RX 470/... | 114   | amdgpu     | DFA6B5B067 |
| 10de:0640 |           | Nvidia     | G96C [GeForce 9500 GT]       | 107   | nouveau    | AAB06F55BD |
| 8086:0152 | 1043:844d | Intel      | Xeon E3-1200 v2/3rd Gen C... | 104   | i915       | 7D2B37E6E1 |
| 1002:15dd | 1043:876b | AMD        | Raven Ridge [Radeon Vega ... | 102   | amdgpu     | 3C83289B45 |
| 8086:0162 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 99    | i915       | 92D06972E9 |
| 8086:0402 | 1458:d000 | Intel      | Xeon E3-1200 v3/4th Gen C... | 98    | i915       | 07FCF530F1 |
| 8086:29c2 | 1458:d000 | Intel      | 82G33/G31 Express Integra... | 98    | i915       | 17DB6D39FE |
| 1002:67df | 1462:3418 | AMD        | Ellesmere [Radeon RX 470/... | 97    | amdgpu     | 84FDA964C3 |
| 8086:2e32 | 1458:d000 | Intel      | 4 Series Chipset Integrat... | 97    | i915       | 43A5D97DD3 |
| 10de:0622 |           | Nvidia     | G94 [GeForce 9600 GT]        | 95    | nouveau    | EC9321BD41 |
| 8086:0402 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 91    | i915       | EBA4D60B90 |
| 8086:2772 | 1043:817a | Intel      | 82945G/GZ Integrated Grap... | 91    | i915       | B40733E088 |
| 10de:0a65 | 1462:8094 | Nvidia     | GT218 [GeForce 210]          | 88    | nouveau    | 3814A57318 |
| 10de:0de0 |           | Nvidia     | GF108 [GeForce GT 440]       | 88    | nouveau    | 773FC40103 |
| 8086:29c2 | 1849:29c2 | Intel      | 82G33/G31 Express Integra... | 88    | i915       | AF6E17AC8C |
| 8086:2e12 | 1028:0420 | Intel      | 4 Series Chipset Integrat... | 88    | i915       | 340184FB36 |
| 8086:2e13 | 1028:0420 | Intel      | 4 Series Chipset Integrat... | 88    |            | 340184FB36 |
| 1002:15d8 | 1043:876b | AMD        | Picasso                      | 87    | amdgpu     | AB4B1B7A15 |
| 10de:0615 |           | Nvidia     | G92 [GeForce GTS 250]        | 87    | nvidia     | 55DF0FDEF1 |
| 8086:041e | 1043:8534 | Intel      | 4th Generation Core Proce... | 87    | i915       | 52FA7C5A31 |
| 8086:041e | 1458:d000 | Intel      | 4th Generation Core Proce... | 87    | i915       | DF13F72A9A |
| 8086:0152 | 1028:0577 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 86    | i915       | 4DAF9FDC0D |
| 8086:0152 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 85    | i915       | 6F05AEA2C1 |
| 8086:0412 | 1849:0412 | Intel      | Xeon E3-1200 v3/4th Gen C... | 85    | i915       | 98BBC7AD66 |
| 10de:0614 |           | Nvidia     | G92 [GeForce 9800 GT]        | 84    | nouveau    | AC572EF424 |
| 1002:68f9 | 174b:e164 | AMD        | Cedar [Radeon HD 5000/600... | 82    | radeon     | E31519274B |
| 8086:3e92 | 1043:8694 | Intel      | CometLake-S GT2 [UHD Grap... | 80    | i915       | CF4E1CB0D6 |
| 8086:3e92 | 1458:d000 | Intel      | CometLake-S GT2 [UHD Grap... | 80    | i915       | F23DE0D726 |
| 10de:1380 | 1043:84bb | Nvidia     | GM107 [GeForce GTX 750 Ti]   | 78    | nvidia     | B2A98215C7 |
| 10de:13c2 | 1462:3160 | Nvidia     | GM204 [GeForce GTX 970]      | 78    | nvidia     | 804CEE7367 |
| 1002:731f | 1002:0b36 | AMD        | Navi 10 [Radeon RX 5600 O... | 77    | amdgpu     | D89A4D7338 |
| 10de:1244 |           | Nvidia     | GF116 [GeForce GTX 550 Ti]   | 77    | nouveau    | 0950E49E1A |
| 8086:1912 | 1458:d000 | Intel      | HD Graphics 530              | 77    | i915       | 6CEB83052E |
| 10de:0ca3 |           | Nvidia     | GT215 [GeForce GT 240]       | 76    | nouveau    | 05D8F2C231 |
| 1002:6779 | 174b:e164 | AMD        | Caicos [Radeon HD 6450/74... | 75    | radeon     | D37856DC0A |
| 8086:0412 | 1028:05a4 | Intel      | Xeon E3-1200 v3/4th Gen C... | 75    | i915       | 0FC3ABDB1C |
| 10de:0de1 |           | Nvidia     | GF108 [GeForce GT 430]       | 73    | nouveau    | C50C060EA2 |
| 10de:0f00 | 1569:0f00 | Nvidia     | GF108 [GeForce GT 630]       | 71    | nouveau    | B687E379B9 |
| 8086:0152 | 1849:0152 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 71    | i915       | 3A362598FB |
| 8086:5912 | 1458:d000 | Intel      | HD Graphics 630              | 71    | i915       | 4A801DAF44 |
| 8086:0102 | 1849:0102 | Intel      | 2nd Generation Core Proce... | 68    | i915       | 27D26A7C8B |
| 10de:1c82 | 10de:1c82 | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 67    | nvidia     | 63EFFDE8C3 |
| 1002:67df | 174b:e347 | AMD        | Ellesmere [Radeon RX 470/... | 66    | amdgpu     | D811152E10 |
| 1002:15dd | 1458:d000 | AMD        | Raven Ridge [Radeon Vega ... | 65    | amdgpu     | F04A4BB553 |
| 1002:67df | 1682:c570 | AMD        | Ellesmere [Radeon RX 470/... | 65    | amdgpu     | F544511E0A |
| 10de:0f00 | 1458:3544 | Nvidia     | GF108 [GeForce GT 630]       | 64    | nouveau    | 8A06C635E9 |
| 10de:11c0 | 1458:354e | Nvidia     | GK106 [GeForce GTX 660]      | 64    | nvidia     | 99AE75539D |
| 10de:13c2 | 1043:8508 | Nvidia     | GM204 [GeForce GTX 970]      | 64    | nvidia     | E0982E1F66 |
| 8086:0162 | 1849:0162 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 64    | i915       | E7EBAD7358 |
| 8086:2772 | 1458:d000 | Intel      | 82945G/GZ Integrated Grap... | 64    | i915       | 9890DA0EFD |
| 8086:0412 | 103c:1998 | Intel      | Xeon E3-1200 v3/4th Gen C... | 63    | i915       | D8309CFECF |
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 63    | i915       | 465523934D |
| 10de:128b | 10de:128b | Nvidia     | GK208B [GeForce GT 710]      | 62    | nvidia     | EA009F77D1 |
| 1002:699f | 1da2:e367 | AMD        | Lexa PRO [Radeon 540/540X... | 61    | amdgpu     | 73AB03E040 |
| 10de:0fc6 | 1569:0fc6 | Nvidia     | GK107 [GeForce GTX 650]      | 61    | nouveau    | 961E640BF5 |
| 10de:1c82 | 10de:11bf | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 61    | nvidia     | C6DCB137FB |
| 8086:0102 | 1028:04f5 | Intel      | 2nd Generation Core Proce... | 61    | i915       | 00CE09B473 |
| 8086:29b2 | 1028:0211 | Intel      | 82Q35 Express Integrated ... | 61    | i915       | 962E0B75E4 |
| 8086:29b3 | 1028:0211 | Intel      | 82Q35 Express Integrated ... | 61    |            | 962E0B75E4 |
| 1002:6778 | 1028:2120 | AMD        | Caicos XT [Radeon HD 7470... | 60    | radeon     | 4C34BAF1DC |
| 1002:731f | 1da2:e411 | AMD        | Navi 10 [Radeon RX 5600 O... | 60    | amdgpu     | 9EF9B30F3A |
| 10de:1d01 | 1458:375c | Nvidia     | GP108 [GeForce GT 1030]      | 59    | nvidia     | 25FFFCB5C5 |
| 8086:0102 | 1028:04ad | Intel      | 2nd Generation Core Proce... | 59    | i915       | DB42B43D7E |
| 10de:0a65 | 1458:3525 | Nvidia     | GT218 [GeForce 210]          | 57    | nouveau    | 92920FF59A |
| 10de:128b | 10de:118b | Nvidia     | GK208B [GeForce GT 710]      | 57    | nouveau    | 6B5F72CBAA |
| 8086:2e12 | 1028:027f | Intel      | 4 Series Chipset Integrat... | 57    | i915       | 8F0C6ED152 |
| 8086:2e13 | 1028:027f | Intel      | 4 Series Chipset Integrat... | 57    |            | 8F0C6ED152 |
| 10de:1c81 | 1462:8c97 | Nvidia     | GP107 [GeForce GTX 1050]     | 56    | nvidia     | D640900B8A |
| 1002:67df | 1da2:e387 | AMD        | Ellesmere [Radeon RX 470/... | 55    | amdgpu     | DE14F99534 |
| 8086:0102 | 103c:1495 | Intel      | 2nd Generation Core Proce... | 55    | i915       | 660C4FF2ED |
| 10de:0402 |           | Nvidia     | G84 [GeForce 8600 GT]        | 54    | nouveau    | 8F3E9F6041 |
| 8086:0162 | 1458:d000 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 54    | i915       | 31B25815EC |
| 1002:6759 | 174b:e193 | AMD        | Turks PRO [Radeon HD 6570... | 53    | radeon     | 6BDF2E77C2 |
| 10de:0f02 | 1462:8a9f | Nvidia     | GF108 [GeForce GT 730]       | 53    | nouveau    | E00920532D |
| 10de:1c03 | 19da:1438 | Nvidia     | GP106 [GeForce GTX 1060 6GB] | 53    | nvidia     | 97C17F738A |
| 8086:2e32 | 1849:2e32 | Intel      | 4 Series Chipset Integrat... | 53    | i915       | ADC801308B |
| 1002:66af | 1002:081e | AMD        | Vega 20 [Radeon VII]         | 52    | amdgpu     | 6AC8300CE8 |
| 10de:1c82 | 1462:3351 | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 52    | nvidia     | 0A228B18C1 |
| 8086:3e98 | 1043:8694 | Intel      | CoffeeLake-S GT2 [UHD Gra... | 52    | i915       | 36EBF65D44 |

### I/o card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10e8:80d8 |           | Applied... | PCI-7200 40MB/s 32-channe... | 1     |            | 3864E6C70F |

### Input device controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1102:7002 | 1102:0020 | Creativ... | SB Live! Game Port           | 161   | emu10k1_gp | 73BFADA83A |
| 1102:7003 | 1102:0040 | Creativ... | SB Audigy Game Port          | 121   | emu10k1_gp | A51030D9A0 |
| 1102:7003 | 1102:0060 | Creativ... | SB Audigy Game Port          | 26    | emu10k1_gp | 4970AA3AFB |
| 1102:7004 | 1102:1003 | Creativ... | [SB Live! Value] Input de... | 10    | emu10k1_gp | 1661F6766F |
| 1319:0802 | 1319:1319 | Fortemedia | Xwave QS3000A [FM801 game... | 8     | fm801_gp   | CE881D4659 |
| 1102:7005 | 1102:1002 | Creativ... | SB Audigy LS Game Port       | 1     | emu10k1_gp | A8AFE9E221 |
| 127a:4312 | 1235:4312 | Rockwel... | Riptide PCI Game Controller  | 1     | snd_rip... | 34867AD122 |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1481 | 1022:1481 | AMD        | Starship/Matisse IOMMU       | 882   |            | 0619809B36 |
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 794   |            | F544511E0A |
| 1022:1451 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 693   |            | 115EC5ECA4 |
| 1022:1481 | 1043:87c0 | AMD        | Starship/Matisse IOMMU       | 571   |            | 97C17F738A |
| 1022:1481 | 1043:8808 | AMD        | Starship/Matisse IOMMU       | 82    |            | 20115EE05D |
| 1022:1481 | 1462:7c02 | AMD        | Starship/Matisse IOMMU       | 78    |            | A04EB698F8 |
| 1022:15d1 | 1043:876b | AMD        | Raven/Raven2 IOMMU           | 62    |            | AB4B1B7A15 |
| 1022:1451 | 1462:7c02 | AMD        | Family 17h (Models 00h-0f... | 50    |            | 2229C9E9F6 |
| 1022:1481 | 1462:7b86 | AMD        | Starship/Matisse IOMMU       | 49    |            | A42F5B4313 |
| 1022:1451 | 1462:7b86 | AMD        | Family 17h (Models 00h-0f... | 40    |            | 6787B45989 |
| 1022:1481 | 1462:7b89 | AMD        | Starship/Matisse IOMMU       | 37    |            | 43A19D8280 |
| 1022:1481 | 1462:7c35 | AMD        | Starship/Matisse IOMMU       | 31    |            | A4D2088CC9 |
| 1022:1631 | 1022:1631 | AMD        | Renoir IOMMU                 | 31    |            | 6B0F0CD327 |
| 1022:1419 | 103c:1850 | AMD        | Family 15h (Models 10h-1f... | 29    |            | 3BDE7E8E11 |
| 1022:1451 | 1462:7a38 | AMD        | Family 17h (Models 00h-0f... | 26    |            | 00A14A97A2 |
| 1022:1451 | 1462:7b89 | AMD        | Family 17h (Models 00h-0f... | 23    |            | 463432C55F |
| 1022:1481 | 1462:7a38 | AMD        | Starship/Matisse IOMMU       | 19    |            | ABF17F0C92 |
| 1022:1481 | 1462:7b85 | AMD        | Starship/Matisse IOMMU       | 19    |            | DFA5C022B3 |
| 1022:1481 | 1043:87cb | AMD        | Starship/Matisse IOMMU       | 18    |            | 1F560968AB |
| 1022:1631 | 1043:87e1 | AMD        | Renoir IOMMU                 | 18    |            | D8274A2024 |
| 1022:1481 | 1462:7c95 | AMD        | Starship/Matisse IOMMU       | 17    |            | 4A568F856E |
| 1022:1481 | 1462:7c94 | AMD        | Starship/Matisse IOMMU       | 16    |            | 640C5ADFC3 |
| 1022:1451 | 1462:7b85 | AMD        | Family 17h (Models 00h-0f... | 13    |            | 8176B777B9 |
| 1022:1451 | 1028:07ee | AMD        | Family 17h (Models 00h-0f... | 12    |            | 38CD4647D5 |
| 1022:1577 | 17aa:364f | AMD        | Family 15h (Models 60h-6f... | 11    |            | 973E323F3C |
| 1022:1423 | 17aa:36a0 | AMD        | Family 15h (Models 30h-3f... | 10    |            | 762E9BD18E |
| 1022:1481 | 1043:87e2 | AMD        | Starship/Matisse IOMMU       | 10    |            | 76267FCBDA |
| 1022:1481 | 1462:7a40 | AMD        | Starship/Matisse IOMMU       | 10    |            | B2B10D4380 |
| 1022:1423 | 103c:2215 | AMD        | Family 15h (Models 30h-3f... | 8     |            | BAEFDA0ADA |
| 1022:1577 | 1043:8719 | AMD        | Family 15h (Models 60h-6f... | 8     |            | 8A607B7D4E |
| 1022:1423 | 1025:0904 | AMD        | Family 15h (Models 30h-3f... | 7     |            | 77B62F0563 |
| 1022:1451 | 1462:7a40 | AMD        | Family 17h (Models 00h-0f... | 7     |            | BD8CB19ABD |
| 1022:1419 | 1019:7c90 | AMD        | Family 15h (Models 10h-1f... | 6     |            | 4D0AC6A6A2 |
| 1022:1451 | 1028:089a | AMD        | Family 17h (Models 00h-0f... | 6     |            | 12F62738E6 |
| 1022:1577 | 17aa:3100 | AMD        | Family 15h (Models 60h-6f... | 6     |            | BBFCF94452 |
| 1022:1419 | 1462:7793 | AMD        | Family 15h (Models 10h-1f... | 5     |            | 38737D3922 |
| 1022:1451 | 1462:7b87 | AMD        | Family 17h (Models 00h-0f... | 5     |            | 9B8F51B1D4 |
| 1022:1567 | 1022:1567 | AMD        | Mullins IOMMU                | 5     |            | C8A3D807BB |
| 1022:15d1 | 1462:7b86 | AMD        | Raven/Raven2 IOMMU           | 5     |            | 9B273ADF50 |
| 1022:1481 | 1028:098e | AMD        | Starship/Matisse IOMMU       | 4     |            | E1BC8D1CDD |
| 1022:1481 | 1462:7c34 | AMD        | Starship/Matisse IOMMU       | 4     |            | 3D2E576C95 |
| 1022:1481 | 1462:7c36 | AMD        | Starship/Matisse IOMMU       | 4     |            | 26B69278F1 |
| 1022:15d1 | 1462:7a38 | AMD        | Raven/Raven2 IOMMU           | 4     |            | 9A1463FD59 |
| 1022:1419 | 103c:2215 | AMD        | Family 15h (Models 10h-1f... | 3     |            | 0CE403B929 |
| 1022:1419 | 1462:7891 | AMD        | Family 15h (Models 10h-1f... | 3     |            | 44AC92329A |
| 1022:1423 | 1462:7900 | AMD        | Family 15h (Models 30h-3f... | 3     |            | 930993FD14 |
| 1022:1451 | 1462:7b90 | AMD        | Family 17h (Models 00h-0f... | 3     |            | ABD9798AA8 |
| 1022:1481 | 17aa:1046 | AMD        | Starship/Matisse IOMMU       | 3     |            | 2C58A29C2A |
| 1022:15d1 | 1462:7c02 | AMD        | Raven/Raven2 IOMMU           | 3     |            | A42BEE6110 |
| 8086:1f16 | 1849:1f16 | Intel      | Atom processor C2000 RCEC    | 3     |            | C881809C02 |
| 1002:5a23 | 1462:7893 | AMD        | RD890S/RD990 I/O Memory M... | 2     |            | C67DD69EA3 |
| 1022:1419 | 1019:9ac9 | AMD        | Family 15h (Models 10h-1f... | 2     |            | E5938AFD2B |
| 1022:1423 | 1462:7891 | AMD        | Family 15h (Models 30h-3f... | 2     |            | A2AB595336 |
| 1022:1481 | 1043:8747 | AMD        | Starship/Matisse IOMMU       | 2     |            | 249D6291CB |
| 1022:1481 | 1462:7c96 | AMD        | Starship/Matisse IOMMU       | 2     |            | 1DC1C27798 |
| 1022:15d1 | 1019:a4cd | AMD        | Raven/Raven2 IOMMU           | 2     |            | 8EB8144AEB |
| 1022:15d1 | 1462:7a40 | AMD        | Raven/Raven2 IOMMU           | 2     |            | AA41662477 |
| 1022:15d1 | 1462:7b85 | AMD        | Raven/Raven2 IOMMU           | 2     |            | 0548F9650B |
| 1022:1631 | 1462:7c94 | AMD        | Renoir IOMMU                 | 2     |            | 1DA678C883 |
| 1022:1419 | 1019:7c6f | AMD        | Family 15h (Models 10h-1f... | 1     |            | 783674FDBD |
| 1022:1419 | 1019:7e42 | AMD        | Family 15h (Models 10h-1f... | 1     |            | B08197DF02 |
| 1022:1419 | 1019:9a62 | AMD        | Family 15h (Models 10h-1f... | 1     |            | D0D02802AF |
| 1022:1419 | 1462:7a83 | AMD        | Family 15h (Models 10h-1f... | 1     |            | 614F005109 |
| 1022:1419 | 17aa:3089 | AMD        | Family 15h (Models 10h-1f... | 1     |            | 1F90A5A2C6 |
| 1022:1423 | 1019:99d3 | AMD        | Family 15h (Models 30h-3f... | 1     |            | CFCBE45B0D |
| 1022:1423 | 1019:9a18 | AMD        | Family 15h (Models 30h-3f... | 1     |            | C24F9ED7E2 |
| 1022:1423 | 1019:9a62 | AMD        | Family 15h (Models 30h-3f... | 1     |            | 06FB58E8EE |
| 1022:1423 | 1019:9ac9 | AMD        | Family 15h (Models 30h-3f... | 1     |            | BED1921035 |
| 1022:1423 | 1019:9aed | AMD        | Family 15h (Models 30h-3f... | 1     |            | 9D69618F17 |
| 1022:1423 | 1019:9bcd | AMD        | Family 15h (Models 30h-3f... | 1     |            | BEF78AFCA1 |
| 1022:1423 | 1462:7903 | AMD        | Family 15h (Models 30h-3f... | 1     |            | EADCB61E9F |
| 1022:1423 | 1462:7913 | AMD        | Family 15h (Models 30h-3f... | 1     |            | A04C671F0B |
| 1022:1423 | 1462:7969 | AMD        | Family 15h (Models 30h-3f... | 1     |            | A2599D7FFB |
| 1022:1451 | 1019:9ce5 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 06776696F3 |
| 1022:1451 | 1019:9d10 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 277BBC0E9E |
| 1022:1451 | 1019:a412 | AMD        | Family 17h (Models 00h-0f... | 1     |            | C47BA626E7 |
| 1022:1451 | 1019:a4cd | AMD        | Family 17h (Models 00h-0f... | 1     |            | 8106DDD47F |
| 1022:1451 | 17aa:3141 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 78DD9729FA |
| 1022:1451 | 17aa:36e1 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 31F5158C61 |
| 1022:1481 | 1028:0a8b | AMD        | Starship/Matisse IOMMU       | 1     |            | 9F3FE00E5C |
| 1022:1481 | 1043:1bf1 | AMD        | Starship/Matisse IOMMU       | 1     |            | 65E2923B50 |
| 1022:1481 | 1043:1c81 | AMD        | Starship/Matisse IOMMU       | 1     |            | D748821025 |
| 1022:1481 | 1043:8815 | AMD        | Starship/Matisse IOMMU       | 1     |            | 86CEE5AEF6 |
| 1022:1481 | 1462:7b87 | AMD        | Starship/Matisse IOMMU       | 1     |            | 98E7FEFA9C |
| 1022:1481 | 1462:7c87 | AMD        | Starship/Matisse IOMMU       | 1     |            | 33B88D17A8 |
| 1022:1481 | 17aa:3148 | AMD        | Starship/Matisse IOMMU       | 1     |            | 77A1D53114 |
| 1022:1481 | 1849:1481 | AMD        | Starship/Matisse IOMMU       | 1     |            | 53BDA46668 |
| 1022:1577 | 1462:7895 | AMD        | Family 15h (Models 60h-6f... | 1     |            | A2AA184709 |
| 1022:15d1 | 1462:7c87 | AMD        | Raven/Raven2 IOMMU           | 1     |            | 91F401BD7C |
| 1022:15d1 | 1462:7d14 | AMD        | Raven/Raven2 IOMMU           | 1     |            | C12B7294B9 |
| 1022:15d1 | 17aa:3141 | AMD        | Raven/Raven2 IOMMU           | 1     |            | F19B15E3D2 |
| 1022:15d1 | 1849:15d1 | AMD        | Raven/Raven2 IOMMU           | 1     |            | 68C78F3D59 |
| 1022:1631 | 1462:7b89 | AMD        | Renoir IOMMU                 | 1     |            | E55472CF5F |
| 1022:1631 | 1462:7c95 | AMD        | Renoir IOMMU                 | 1     |            | 59F94E4DB6 |
| 8086:1f16 | 15d9:0820 | Intel      | Atom processor C2000 RCEC    | 1     |            | DAE3697FF8 |
| 8086:1f16 | 8086:0000 | Intel      | Atom processor C2000 RCEC    | 1     |            | E889E472C5 |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816c | 103c:8464 | Realtek... | RTL8111xP IPMI interface     | 4     |            | A112F2F435 |
| 10ec:816c | 10ec:0123 | Realtek... | RTL8111xP IPMI interface     | 4     |            | C1C5847225 |
| 10ec:816c | 1025:1248 | Realtek... | RTL8111xP IPMI interface     | 3     |            | E3FB43377E |
| 10ec:816c | 1849:8168 | Realtek... | RTL8111xP IPMI interface     | 3     | ipmi_si    | 417BCCCFA6 |
| 10ec:816c | 1019:81ea | Realtek... | RTL8111xP IPMI interface     | 2     |            | D0D02802AF |
| 10ec:816c | 1025:080a | Realtek... | RTL8111xP IPMI interface     | 2     |            | D5413884E0 |
| 10ec:816c | 103c:8461 | Realtek... | RTL8111xP IPMI interface     | 2     |            | 991B8A8A71 |
| 10ec:816c | 103c:8618 | Realtek... | RTL8111xP IPMI interface     | 2     |            | A021BE4E84 |
| 10ec:816c | 1025:078d | Realtek... | RTL8111xP IPMI interface     | 1     |            | 504EC0D230 |
| 10ec:816c | 1025:1005 | Realtek... | RTL8111xP IPMI interface     | 1     |            | 8A65F68E82 |
| 10ec:816c | 1025:1180 | Realtek... | RTL8111xP IPMI interface     | 1     |            | F1BB2896EE |
| 10ec:816c | 1025:124c | Realtek... | RTL8111xP IPMI interface     | 1     |            | 8EB6F7795D |
| 10ec:816c | 103c:8626 | Realtek... | RTL8111xP IPMI interface     | 1     |            | 9BC7D6303D |
| 10ec:816c | 1734:1216 | Realtek... | RTL8111xP IPMI interface     | 1     |            | A960AEF3AE |
| 10ec:816c | 17aa:30fd | Realtek... | RTL8111xP IPMI interface     | 1     |            | 9D82F1B7E3 |
| 10ec:816c | 17aa:3141 | Realtek... | RTL8111xP IPMI interface     | 1     |            | F19B15E3D2 |
| 10ec:816c | 1b0a:00e5 | Realtek... | RTL8111xP IPMI interface     | 1     |            | 3DA36F7282 |
| 8086:108e | 1734:108d | Intel      | 82573E KCS (Active Manage... | 1     | ipmi_si    | CCA0170CC9 |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 103c:3302 | 103c:3305 | Hewlett... | Integrated Lights-Out Sta... | 15    | ipmi_si    | 2ED58CCD22 |
| 10ec:816c | 10ec:8168 | Realtek... | RTL8111xP IPMI interface     | 15    | ipmi_si    | 6E60025AC5 |
| 10ec:816c | 1458:e000 | Realtek... | RTL8111xP IPMI interface     | 10    | ipmi_si    | 4B79994619 |
| 10ec:816c | 17aa:3089 | Realtek... | RTL8111xP IPMI interface     | 9     | ipmi_si    | 7D4224DF3F |
| 10ec:816c | 1734:1178 | Realtek... | RTL8111xP IPMI interface     | 7     | ipmi_si    | CD168F769A |
| 8086:108e | 8086:0000 | Intel      | 82573E KCS (Active Manage... | 6     | ipmi_si    | 82933CDF0E |
| 10ec:816c | 1025:078b | Realtek... | RTL8111xP IPMI interface     | 4     |            | FD387BD03F |
| 10ec:816c | 1043:8578 | Realtek... | RTL8111xP IPMI interface     | 1     | ipmi_si    | C248800623 |
| 10ec:816c | 10ec:816c | Realtek... | RTL8111xP IPMI interface     | 1     |            | 1830DAEFB4 |
| 10ec:816c | 17aa:30b2 | Realtek... | RTL8111xP IPMI interface     | 1     | ipmi_si    | 36635F76F9 |

### Isdn adapter (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1244:0e00 | 1244:0e00 | AVM        | Fritz!Card PCI v2.0 ISDN     | 9     | fcpci      | 1A5051E686 |
| 1244:0a00 | 1244:0a00 | AVM        | A1 ISDN [Fritz]              | 7     | fcpci      | AF06884158 |
| 1133:e00b | 1133:e00b | Dialogic   | Diva ISDN PCI 2.02           | 1     |            | AC7FD78AB8 |
| 1397:2bd0 | 1397:2bd0 | Cologne... | ISDN network controller [... | 1     | hfcpci     | 83A7C8B23F |
| e159:0001 | 795e:0001 | Tiger J... | Tiger3XX Modem/ISDN inter... | 1     | wcte11xp   | FE13415AC0 |
| e159:0001 | 79fe:0001 | Tiger J... | Tiger3XX Modem/ISDN inter... | 1     | wcte11xp   | B6E88B98F7 |
| e159:0001 | 9100:0001 | Tiger J... | Tiger3XX Modem/ISDN inter... | 1     | netjet     | 74F31779A2 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a121 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 648   |            | 11EBF0D551 |
| 8086:a36f | 8086:7270 | Intel      | Cannon Lake PCH Shared SRAM  | 544   |            | 3D0DA576B8 |
| 10de:03f5 | 1849:03eb | Nvidia     | MCP61 Memory Controller      | 397   |            | 615502E93E |
| 8086:a2a1 | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 389   |            | 2696477C0C |
| 8086:a2a1 | 1458:5001 | Intel      | 200 Series/Z370 Chipset F... | 364   |            | F91A20DD51 |
| 10de:03e2 | 1849:03e2 | Nvidia     | MCP61 Host Bridge            | 363   |            | 615502E93E |
| 8086:a121 | 1458:5001 | Intel      | 100 Series/C230 Series Ch... | 358   |            | 213A5CCCC3 |
| 8086:a36f | 1043:8694 | Intel      | Cannon Lake PCH Shared SRAM  | 301   |            | 36EBF65D44 |
| 10de:03f5 | 1458:0c11 | Nvidia     | MCP61 Memory Controller      | 195   |            | FB1E012F68 |
| 8086:a121 | 1849:a121 | Intel      | 100 Series/C230 Series Ch... | 173   |            | 3A2A9BD626 |
| 8086:a2a1 | 1849:a2a1 | Intel      | 200 Series/Z370 Chipset F... | 146   |            | A8F84AEA94 |
| 10de:03e2 | 1043:83a4 | Nvidia     | MCP61 Host Bridge            | 144   |            | 1C28AB7987 |
| 10de:03f5 | 1043:83a4 | Nvidia     | MCP61 Memory Controller      | 144   |            | 1C28AB7987 |
| 8086:a2a1 | 1043:872f | Intel      | 200 Series/Z370 Chipset F... | 131   |            | C1BF9C169D |
| 10de:03ea | 10de:cb84 | Nvidia     | MCP61 Memory Controller      | 120   |            | 2537B06002 |
| 10de:03ea | 1043:8234 | Nvidia     | MCP61 Memory Controller      | 116   |            | A5CA2582B6 |
| 10de:03f5 | 1043:8234 | Nvidia     | MCP61 Memory Controller      | 116   |            | A5CA2582B6 |
| 8086:a36f | 1849:a36f | Intel      | Cannon Lake PCH Shared SRAM  | 102   |            | 839B20476A |
| 10de:03ea | 1458:5001 | Nvidia     | MCP61 Memory Controller      | 101   |            | FB1E012F68 |
| 10de:03e2 | 1458:5001 | Nvidia     | MCP61 Host Bridge            | 94    |            | 47DEFF8A39 |
| 10de:005e | 1043:815a | Nvidia     | CK804 Memory Controller      | 90    |            | 00B830F623 |
| 8086:06ef | 8086:7270 | Intel      | Comet Lake PCH Shared SRAM   | 75    |            | 6BC1B9DCC9 |
| 10de:03f5 | 1462:7309 | Nvidia     | MCP61 Memory Controller      | 70    |            | DC2D2CA478 |
| 8086:a121 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 64    |            | C007D839E7 |
| 10de:03f5 | 1565:3407 | Nvidia     | MCP61 Memory Controller      | 62    |            | FF6423FB29 |
| 10de:0568 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 62    |            | 739D1AE9B7 |
| 10de:0751 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 62    |            | 739D1AE9B7 |
| 10de:0754 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 62    |            | 739D1AE9B7 |
| 8086:06ef | 1043:8694 | Intel      | Comet Lake PCH Shared SRAM   | 61    |            | BBA08D40AD |
| 10de:03a9 |           | Nvidia     | C55 Memory Controller        | 54    |            | 3965D087B0 |
| 10de:03aa |           | Nvidia     | C55 Memory Controller        | 54    |            | 3965D087B0 |
| 10de:03ab |           | Nvidia     | C55 Memory Controller        | 54    |            | 3965D087B0 |
| 10de:03b4 |           | Nvidia     | C55 Memory Controller        | 54    |            | 3965D087B0 |
| 10de:03bc |           | Nvidia     | C55 Memory Controller        | 54    |            | 3965D087B0 |
| 10de:0369 | 1043:8239 | Nvidia     | MCP55 Memory Controller      | 52    |            | 476250F98C |
| 10de:03a8 |           | Nvidia     | C55 Memory Controller        | 52    |            | 3965D087B0 |
| 10de:03ac |           | Nvidia     | C55 Memory Controller        | 52    |            | 3965D087B0 |
| 10de:03ad |           | Nvidia     | C55 Memory Controller        | 52    |            | 3965D087B0 |
| 10de:03ae |           | Nvidia     | C55 Memory Controller        | 52    |            | 3965D087B0 |
| 10de:03af |           | Nvidia     | C55 Memory Controller        | 52    |            | 3965D087B0 |
| 10de:03b0 |           | Nvidia     | C55 Memory Controller        | 52    |            | 3965D087B0 |
| 10de:03b1 |           | Nvidia     | C55 Memory Controller        | 52    |            | 3965D087B0 |
| 10de:03b2 |           | Nvidia     | C55 Memory Controller        | 52    |            | 3965D087B0 |
| 10de:03b3 |           | Nvidia     | C55 Memory Controller        | 52    |            | 3965D087B0 |
| 10de:03b5 |           | Nvidia     | C55 Memory Controller        | 52    |            | 3965D087B0 |
| 10de:03b6 |           | Nvidia     | C55 Memory Controller        | 52    |            | 3965D087B0 |
| 10de:03ba |           | Nvidia     | C55 Memory Controller        | 52    |            | 3965D087B0 |
| 8086:a3a1 | 1043:8694 | Intel      | Memory controller            | 51    |            | 5125306D59 |
| 8086:a121 | 1734:121d | Intel      | 100 Series/C230 Series Ch... | 48    |            | 4E988AF2DF |
| 10de:0444 | 1462:7369 | Nvidia     | MCP65 Memory Controller      | 46    |            | 2A0863DD05 |
| 10de:0445 | 1462:7369 | Nvidia     | MCP65 Memory Controller      | 46    |            | 2A0863DD05 |
| 10de:027e | 10de:027e | Nvidia     | C51 Memory Controller 2      | 43    |            | D1B6626B26 |
| 10de:027f | 10de:027f | Nvidia     | C51 Memory Controller 3      | 43    |            | D1B6626B26 |
| 10de:02f8 | 10de:02f8 | Nvidia     | C51 Memory Controller 5      | 43    |            | D1B6626B26 |
| 10de:02f9 | 10de:02f9 | Nvidia     | C51 Memory Controller 4      | 43    |            | D1B6626B26 |
| 10de:02fa | 10de:02fa | Nvidia     | C51 Memory Controller 0      | 43    |            | D1B6626B26 |
| 10de:02fe | 10de:02fe | Nvidia     | C51 Memory Controller 1      | 43    |            | D1B6626B26 |
| 10de:02ff | 10de:02ff | Nvidia     | C51 Host Bridge              | 43    |            | D1B6626B26 |
| 10de:0568 |           | Nvidia     | MCP78S [GeForce 8200] Mem... | 41    |            | 4AF8E42B5A |
| 10de:0751 | 10de:cb84 | Nvidia     | MCP78S [GeForce 8200] Mem... | 41    |            | 236A9A94B1 |
| 8086:a121 | 1462:7a15 | Intel      | 100 Series/C230 Series Ch... | 41    |            | B1186D53E5 |
| 8086:9d21 | 8086:7270 | Intel      | Sunrise Point-LP PMC         | 40    |            | 9BC7AB87D1 |
| 8086:a121 | 1462:7971 | Intel      | 100 Series/C230 Series Ch... | 39    |            | 2289424CAC |
| 10de:03ea | 103c:2a6c | Nvidia     | MCP61 Memory Controller      | 38    |            | 78A4331611 |
| 10de:03f5 | 103c:2a6c | Nvidia     | MCP61 Memory Controller      | 38    |            | 78A4331611 |
| 10de:03f5 | 1462:7597 | Nvidia     | MCP61 Memory Controller      | 37    |            | 6F22F99F9F |
| 8086:a2a1 | 1043:873c | Intel      | 200 Series/Z370 Chipset F... | 37    |            | D5CDC97C3B |
| 10de:0270 | 1043:81bc | Nvidia     | MCP51 Host Bridge            | 35    |            | 3965D087B0 |
| 10de:0270 | 10de:cb84 | Nvidia     | MCP51 Host Bridge            | 35    |            | D1B6626B26 |
| 10de:0568 | 1849:0568 | Nvidia     | MCP78S [GeForce 8200] Mem... | 35    |            | 9B0A7F242B |
| 10de:0751 | 1849:0751 | Nvidia     | MCP78S [GeForce 8200] Mem... | 35    |            | 9B0A7F242B |
| 10de:0754 | 1849:0754 | Nvidia     | MCP78S [GeForce 8200] Mem... | 35    |            | 9B0A7F242B |
| 10de:03ea | 1849:03ea | Nvidia     | MCP61 Memory Controller      | 34    |            | 1F409F9BF1 |
| 10de:03ea | 103c:2a99 | Nvidia     | MCP61 Memory Controller      | 31    |            | 008B548654 |
| 10de:03f5 | 103c:2a99 | Nvidia     | MCP61 Memory Controller      | 31    |            | 008B548654 |
| 8086:a36f | 1025:1238 | Intel      | Cannon Lake PCH Shared SRAM  | 31    |            | 5C8AF3A6F6 |
| 10de:02f0 | 10de:02f0 | Nvidia     | C51 Host Bridge              | 30    |            | D1B6626B26 |
| 8086:a121 | 1028:06b9 | Intel      | 100 Series/C230 Series Ch... | 29    |            | 8989DF3C9D |
| 10de:0272 | 1043:81bc | Nvidia     | MCP51 Memory Controller 0    | 28    |            | 3965D087B0 |
| 10de:03ea | 1025:0394 | Nvidia     | MCP61 Memory Controller      | 28    |            | F0FE18214F |
| 10de:03f5 | 1025:0394 | Nvidia     | MCP61 Memory Controller      | 28    |            | F0FE18214F |
| 8086:a2a1 | 1462:7a70 | Intel      | 200 Series/Z370 Chipset F... | 28    |            | FB2EEF67F2 |
| 8086:a3a1 | 1458:5001 | Intel      | Memory controller            | 28    |            | FF04BD46CB |
| 10de:03ea | 1565:3407 | Nvidia     | MCP61 Memory Controller      | 27    |            | 474A2761F9 |
| 8086:a2a1 | 103c:82f2 | Intel      | 200 Series/Z370 Chipset F... | 24    |            | 4EFC31781E |
| 10de:0270 | 1043:81c0 | Nvidia     | MCP51 Host Bridge            | 23    |            | 37BC060302 |
| 10de:0369 | 1043:cb84 | Nvidia     | MCP55 Memory Controller      | 22    |            | 11CAEB50AC |
| 10de:0369 | 1458:5001 | Nvidia     | MCP55 Memory Controller      | 22    |            | DEEA9868FB |
| 10de:0369 | 1462:7250 | Nvidia     | MCP55 Memory Controller      | 22    |            | BD7BBADAAD |
| 10de:03e2 | 1462:7597 | Nvidia     | MCP61 Host Bridge            | 22    |            | 6F22F99F9F |
| 10de:0272 | 1043:81c0 | Nvidia     | MCP51 Memory Controller 0    | 21    |            | 37BC060302 |
| 10de:027e | 1043:81c0 | Nvidia     | C51 Memory Controller 2      | 21    |            | 37BC060302 |
| 10de:027f | 1043:81c0 | Nvidia     | C51 Memory Controller 3      | 21    |            | 37BC060302 |
| 10de:02f0 | 1043:81c0 | Nvidia     | C51 Host Bridge              | 21    |            | 37BC060302 |
| 10de:02f8 | 1043:81c0 | Nvidia     | C51 Memory Controller 5      | 21    |            | 37BC060302 |
| 10de:02f9 | 1043:81c0 | Nvidia     | C51 Memory Controller 4      | 21    |            | 37BC060302 |
| 10de:02fe | 1043:81c0 | Nvidia     | C51 Memory Controller 1      | 21    |            | 37BC060302 |
| 10de:02ff | 1043:81c0 | Nvidia     | C51 Host Bridge              | 21    |            | 37BC060302 |
| 10de:03ea | 1019:2242 | Nvidia     | MCP61 Memory Controller      | 21    |            | 0C41FF9165 |
| 10de:03ea | 1019:2601 | Nvidia     | MCP61 Memory Controller      | 21    |            | 3559A290C3 |

### Modem (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1057:3052 | 1057:3020 | Motorola   | SM56 Data Fax Modem          | 23    |            | 3A362598FB |
| 1106:3068 |           | VIA Tec... | AC'97 Modem Controller       | 17    | snd_via... | E739F2F0BA |
| 11c1:044c | 11c1:044c | LSI        | LT WinModem                  | 14    |            | 34D12D37FD |
| 8086:1040 | 8086:1000 | Intel      | 536EP Data Fax Modem         | 7     |            | F2CC8FAE4D |
| 1106:3068 | 1019:0c04 | VIA Tec... | AC'97 Modem Controller       | 4     | snd_via... | CAAB4A3B82 |
| 134d:7892 | 134d:0001 | PCTel      | HSP MicroModem 56            | 4     | serial     | 6C9B4F5E0B |
| 1002:4378 | 103c:3085 | AMD        | IXP SB400 AC'97 Modem Con... | 2     | snd_ati... | 32F7B77B77 |
| 1039:7013 | 1584:4003 | Silicon... | AC'97 Modem Controller       | 2     |            | E9BC9B3C8A |
| 11c1:0440 | 11c1:0440 | LSI        | 56k WinModem                 | 2     |            | 31EAA72C65 |
| 11c1:044e | 11c1:044e | LSI        | LT WinModem                  | 2     |            | DA6AB84289 |
| 11c1:044e | 1235:044e | LSI        | LT WinModem                  | 2     |            | C22EB5394A |
| 134d:7890 | 134d:0001 | PCTel      | HSP MicroModem 56            | 2     | serial     | 332DDF27C1 |
| 1543:3052 | 1543:3000 | SILICON... | Intel 537 [Winmodem]         | 2     |            | 6B3BFC1719 |
| 2003:8800 | 1801:2800 | Smart Link | LM-I56N                      | 2     |            | 62AFB6C0F6 |
| 8086:1080 | 1028:1000 | Intel      | FA82537EP 56K V.92 Data/F... | 2     | serial     | DC13BE448C |
| 1039:7013 | 1025:0083 | Silicon... | AC'97 Modem Controller       | 1     |            | 985DA6D3F5 |
| 1039:7013 | 104d:8128 | Silicon... | AC'97 Modem Controller       | 1     | snd_int... | 72A578315E |
| 1057:3052 | 1631:3034 | Motorola   | SM56 Data Fax Modem          | 1     |            | B7CEC1644D |
| 10b9:5457 | 10cf:130f | ULi Ele... | M5457 AC'97 Modem Controller | 1     |            | 347EB6B747 |
| 1106:3068 | 1019:2122 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 25BB71984B |
| 11c1:0449 | 1468:0410 | LSI        | L56xM+S [Mars-2] WinModem... | 1     |            | A8A13EFBA0 |
| 11c1:044e | 13e0:0401 | LSI        | LT WinModem                  | 1     |            | E9ACA9663F |
| 11c1:0450 | 144f:1515 | LSI        | LT WinModem                  | 1     |            | 32D5B1A614 |
| 163c:3052 | 14fe:0005 | Smart Link | SmartLink SmartPCI562 56K... | 1     | serial     | 9939882441 |
| 2000:2800 | 122d:2800 | Smart Link | SmartPCI2800 V.92 PCI Sof... | 1     |            | 3BC558699A |
| 2000:2800 | 163c:2800 | Smart Link | SmartPCI2800 V.92 PCI Sof... | 1     |            | 9DEE04D2CB |
| 2003:8800 | 16ef:2800 | Smart Link | LM-I56N                      | 1     |            | 8B4AE6CF41 |
| 8086:1080 | 8086:1000 | Intel      | FA82537EP 56K V.92 Data/F... | 1     | serial     | 6DF95E6042 |
| 8086:24d6 | 104d:816f | Intel      | 82801EB/ER (ICH5/ICH5R) A... | 1     |            | AB742E4CF2 |
| 8086:266d |           | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     |            | D8653C0683 |
| 8086:266d | 14f1:5423 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     | snd_int... | 1D936DA792 |
| 8086:27dd |           | Intel      | 82801G (ICH7 Family) AC'9... | 1     |            | 151F16B506 |

### Multimedia (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 0002:8290 | 0004:0000 |            |                              | 1     |            | 95D420F37F |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15e2 | 1022:15e2 | AMD        | Raven/Raven2/FireFlight/R... | 38    | snd_pci... | A9EA33D1F6 |
| 109e:0878 |           | Brooktree  | Bt878 Audio Capture          | 23    |            | E739F2F0BA |
| 11bd:bede | 11bd:0022 | Pinnacl... | AV/DV Studio Capture Card    | 16    |            | E4F384C278 |
| 1022:15e2 | 103c:8433 | AMD        | Raven/Raven2/FireFlight/R... | 15    | snd_pci... | 8670420E76 |
| 109e:0878 | 1461:0003 | Brooktree  | Bt878 Audio Capture          | 14    | snd_bt87x  | DCE0418111 |
| 1131:7164 | 0070:8851 | Philips... | SAA7164                      | 13    | saa7164    | 3A3874784C |
| 1131:7160 | 1461:1455 | Philips... | SAA7160                      | 10    |            | 2D08F702CF |
| 109e:0878 | 0070:13eb | Brooktree  | Bt878 Audio Capture          | 9     | snd_bt87x  | A9C46A46ED |
| 1131:7231 | 16be:0008 | Philips... | SAA7231                      | 8     |            | 9D7D398CC1 |
| 1131:7231 | 5ace:8000 | Philips... | SAA7231                      | 8     |            | FA070462FC |
| 12ab:0380 | 1cfa:0006 | YUAN Hi... | Game Capture 4K60 Pro        | 8     |            | 7A840D41B2 |
| 1822:4e35 | 153b:1178 | Twinhan... | Mantis DTV PCI Bridge Con... | 8     | mantis     | 6AC1485BC6 |
| 1822:4e35 | 1ae4:0003 | Twinhan... | Mantis DTV PCI Bridge Con... | 8     | mantis     | C98E498E71 |
| 1022:15e2 | 103c:8434 | AMD        | Raven/Raven2/FireFlight/R... | 7     | snd_pci... | 61C3E3852A |
| 11bd:bede | 11bd:0023 | Pinnacl... | AV/DV Studio Capture Card    | 7     |            | FD7DE4EB5A |
| 109e:0878 | 107d:6609 | Brooktree  | Bt878 Audio Capture          | 6     |            | 31DFECDF4A |
| 1131:7164 | 0070:f111 | Philips... | SAA7164                      | 6     | saa7164    | 9F28DF0F2C |
| 1131:7231 | 1461:1400 | Philips... | SAA7231                      | 6     |            | 70C319B3C6 |
| 8086:22b8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 6     | intel_a... | 87041C97FB |
| 8086:5a88 |           | Intel      | Celeron N3350/Pentium N42... | 6     |            | 7C30C0C3CA |
| 109e:0878 | 107d:6606 | Brooktree  | Bt878 Audio Capture          | 5     | snd_bt87x  | 90F950C23B |
| 109e:0878 | 11bd:0012 | Brooktree  | Bt878 Audio Capture          | 5     | snd_bt87x  | 237CA98302 |
| 1131:7231 | 16be:0013 | Philips... | SAA7231                      | 5     |            | DD4A0707BA |
| 14f1:8804 | 0070:1402 | Conexan... | CX23880/1/2/3 PCI Video a... | 5     |            | BC782F5E67 |
| 14f1:8804 | 0070:6902 | Conexan... | CX23880/1/2/3 PCI Video a... | 5     |            | B2A993FF98 |
| 14f1:8804 | 0070:9002 | Conexan... | CX23880/1/2/3 PCI Video a... | 5     |            | 1351C7B098 |
| 1822:4e35 | 153b:1179 | Twinhan... | Mantis DTV PCI Bridge Con... | 5     | mantis     | 225F795531 |
| 1022:15e2 | 17aa:3708 | AMD        | Raven/Raven2/FireFlight/R... | 4     | snd_pci... | F8BAB84CFF |
| 1131:7160 | 1131:0002 | Philips... | SAA7160                      | 4     |            | 0861B33243 |
| 1131:7160 | 1ae4:0700 | Philips... | SAA7160                      | 4     |            | FA3005B3D4 |
| 1131:7162 | 11bd:0100 | Philips... | SAA7162                      | 4     |            | D495DD5272 |
| 1131:7162 | 11bd:0101 | Philips... | SAA7162                      | 4     |            | 3C6DF0441A |
| 1131:7231 | 1461:7983 | Philips... | SAA7231                      | 4     |            | 4365F32962 |
| 1131:7231 | 16be:0002 | Philips... | SAA7231                      | 4     |            | 751F3FAAFA |
| 14e4:1615 | 14e4:1615 | Broadcom   | BCM70015 Video Decoder [C... | 4     |            | 490A799D8B |
| 14f1:8804 | 0070:9202 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     |            | 3323601EEF |
| 1745:3000 | 0070:d180 | ViXS Sy... | Colossus Encoder             | 4     |            | 3A3874784C |
| 1002:4d51 | 1002:b041 | AMD        | Unified AVStream             | 3     |            | E0EE188631 |
| 1002:ac12 | 1002:b935 | AMD        | Theater HD T507 (DVB-T) T... | 3     |            | B4CD2CBC1E |
| 1002:ac12 | 12ab:0003 | AMD        | Theater HD T507 (DVB-T) T... | 3     |            | 4E3343DADF |
| 1002:ad18 | 1682:ad18 | AMD        | Multimedia controller        | 3     |            | 829182B838 |
| 109e:0878 | 107d:6607 | Brooktree  | Bt878 Audio Capture          | 3     | bt878      | 502C4EB91B |
| 109e:0878 | 1554:4011 | Brooktree  | Bt878 Audio Capture          | 3     | snd_bt87x  | 6E3E7E3E30 |
| 10ee:222a | ef11:ddd5 | Xilinx     | Multimedia controller        | 3     | earth_pt1  | A5B2555CC2 |
| 1131:7160 | 1461:0955 | Philips... | SAA7160                      | 3     |            | 613C8A1900 |
| 1131:7160 | 1461:0f55 | Philips... | SAA7160                      | 3     |            | 7985ADDC49 |
| 1131:7160 | 1461:2655 | Philips... | SAA7160                      | 3     |            | A74B989748 |
| 1131:7164 | 185b:e900 | Philips... | SAA7164                      | 3     | saa7164    | 879303C98C |
| 1131:7231 | 12ab:0763 | Philips... | SAA7231                      | 3     |            | 20768D0E33 |
| 1131:7231 | 5ace:8201 | Philips... | SAA7231                      | 3     |            | 75F255A4E2 |
| 14e4:1615 | 105b:0d77 | Broadcom   | BCM70015 Video Decoder [C... | 3     |            | B036D312E6 |
| 14f1:8804 | 0070:6906 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     |            | 7CC66E3A90 |
| 14f1:8804 | 0070:9402 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     |            | 0A7AB4D43E |
| 1822:4e35 | 1822:0031 | Twinhan... | Mantis DTV PCI Bridge Con... | 3     | mantis     | 24636D8ED6 |
| 1822:4e35 | 1ae4:0002 | Twinhan... | Mantis DTV PCI Bridge Con... | 3     | mantis     | 783DE16210 |
| 1057:1801 |           | Motorola   | DSP56301 Digital Signal P... | 2     |            | BA572256B0 |
| 1057:3410 | ecc0:0100 | Motorola   | DSP56361 Digital Signal P... | 2     | snd_echo3g | D2B9F26B16 |
| 109e:0878 | 1002:0003 | Brooktree  | Bt878 Audio Capture          | 2     |            | B03897D3E4 |
| 109e:0878 | 1461:0004 | Brooktree  | Bt878 Audio Capture          | 2     |            | F2B7867CAA |
| 109e:0878 | 1852:1852 | Brooktree  | Bt878 Audio Capture          | 2     |            | C560D2AA9B |
| 109e:0878 | 800a:763d | Brooktree  | Bt878 Audio Capture          | 2     |            | 14B2C1FB89 |
| 109e:0878 | 800b:763d | Brooktree  | Bt878 Audio Capture          | 2     |            | 14B2C1FB89 |
| 109e:0878 | 800c:763d | Brooktree  | Bt878 Audio Capture          | 2     |            | 14B2C1FB89 |
| 109e:0878 | 800d:763d | Brooktree  | Bt878 Audio Capture          | 2     |            | 14B2C1FB89 |
| 109e:0878 | bd11:1200 | Brooktree  | Bt878 Audio Capture          | 2     | snd_bt87x  | A09E6F3FC7 |
| 1131:7160 | 1043:48b5 | Philips... | SAA7160                      | 2     |            | 6B30DD9FF7 |
| 1131:7160 | 1461:0855 | Philips... | SAA7160                      | 2     |            | BBDA8BED86 |
| 1131:7160 | 1461:0e55 | Philips... | SAA7160                      | 2     |            | 08CED52205 |
| 1131:7160 | 1461:1855 | Philips... | SAA7160                      | 2     |            | FA070462FC |
| 1131:7160 | 1461:7561 | Philips... | SAA7160                      | 2     |            | 1CBEE8A7EF |
| 1131:7160 | 185b:e750 | Philips... | SAA7160                      | 2     |            | 262A709D45 |
| 1131:7160 | 6281:0001 | Philips... | SAA7160                      | 2     | saa716x... | 21E6F57AC5 |
| 1131:7160 | 6928:0002 | Philips... | SAA7160                      | 2     |            | 2F7F236AF3 |
| 1131:7164 | 0070:8940 | Philips... | SAA7164                      | 2     | saa7164    | 3FF4A460A2 |
| 1131:7164 | 0070:f120 | Philips... | SAA7164                      | 2     | saa7164    | EB55E9A1CD |
| 1131:7231 | 0070:0810 | Philips... | SAA7231                      | 2     |            | 6CB625FE85 |
| 1131:7231 | 1461:2a0f | Philips... | SAA7231                      | 2     |            | BEB8F313F7 |
| 1131:7231 | 1461:7981 | Philips... | SAA7231                      | 2     |            | 928BFFA7DF |
| 1131:7231 | 5ace:8150 | Philips... | SAA7231                      | 2     |            | 8603D5BDF5 |
| 116e:00d0 | 116e:0000 | Electro... | Multimedia controller        | 2     |            | 7823D71E26 |
| 116e:0600 | 116e:0012 | Electro... | Multimedia controller        | 2     |            | 7823D71E26 |
| 11bd:0040 | 11bd:0045 | Pinnacl... | Royal TS Function 1          | 2     |            | 7793E267F5 |
| 11bd:0041 | 11bd:0045 | Pinnacl... | RoyalTS Function 2           | 2     |            | 7793E267F5 |
| 11bd:0042 | 11bd:0045 | Pinnacl... | Royal TS Function 3          | 2     |            | 7793E267F5 |
| 12ab:0371 | 1cfa:000b | YUAN Hi... | Game Capture 4K60 Pro        | 2     |            | 508BC3DCEE |
| 12ab:0371 | 1cfa:000c | YUAN Hi... | Game Capture 4K60 Pro        | 2     |            | 508BC3DCEE |
| 14f1:8804 | 1822:0023 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     |            | AB36F565A4 |
| 1797:6805 |           | Intersi... | HV4000 DVR card              | 2     |            | 9800E2F253 |
| 1797:6814 | 000a:6814 | Intersi... | TW6816 multimedia video c... | 2     |            | D455CC3322 |
| 1797:6815 | 000a:6815 | Intersi... | TW6816 multimedia video c... | 2     |            | D455CC3322 |
| 1797:6816 | 000a:6816 | Intersi... | TW6816 multimedia video c... | 2     |            | D455CC3322 |
| 1797:6817 | 000a:6817 | Intersi... | TW6816 multimedia video c... | 2     |            | D455CC3322 |
| 1a00:0001 | 1a00:0001 |            | Multimedia controller        | 2     |            | 16796AF2C3 |
| 544d:6178 | 6205:0001 | TBS Tec... | DVB Tuner PCIe Card          | 2     |            | 7FE42C31D7 |
| 544d:6178 | 6902:0002 | TBS Tec... | DVB Tuner PCIe Card          | 2     |            | 012B402EAC |
| dd01:0003 | dd01:0030 | Digital... | Octopus DVB Adapter          | 2     | ddbridge   | B4A53FAFC1 |
| dd01:0006 | dd01:0032 | Digital... | Cine V7                      | 2     | ddbridge   | 85744CC543 |
| 0002:8290 | 107d:2609 |            | Multimedia controller        | 1     |            | 95D420F37F |
| 1002:4d52 | 1002:a346 | AMD        | Theater 550 PRO PCI [ATI ... | 1     |            | FDE418F259 |
| 1002:4d53 | 1028:a503 | AMD        | Theater 550 PRO PCIe         | 1     |            | A8D52F4DF8 |

### Multiport serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1fd4:1999 | 1fd4:0002 | SUNIX      | Multiport serial controller  | 7     | serial     | DF6B2FA3DE |
| 135a:08c1 | 135a:0413 | Brain B... | Multiport serial controller  | 1     |            | 0F6EBD3E93 |
| 135c:0170 | 135c:0170 | Quatech    | QSCLP-100                    | 1     | serial     | 05DF269988 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8168 | 1458:e000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5195  | r8169      | E187B3F207 |
| 10ec:8168 | 1849:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2184  | r8169      | 87C40FCD51 |
| 10ec:8168 | 1043:8677 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1559  | r8169      | 5F1E86F753 |
| 10ec:8168 | 1043:8505 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1531  | r8169      | 8B10E96F42 |
| 10ec:8168 | 1043:8432 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1153  | r8169      | 67B53F9BDB |
| 8086:15b8 | 1043:8672 | Intel      | Ethernet Connection (2) I... | 646   | e1000e     | 11EBF0D551 |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 643   | r8169      | B92F4485E6 |
| 10ec:8139 | 10ec:8139 | Realtek... | RTL-8100/8101L/8139 PCI F... | 642   | 8139too... | F8D3B991DA |
| 10ec:8168 | 1043:8554 | Realtek... | RTL8111/8168/8411 PCI Exp... | 637   | r8169      | 8961CA91B3 |
| 10ec:8168 | 1043:83a3 | Realtek... | RTL8111/8168/8411 PCI Exp... | 521   | r8169      | AC572EF424 |
| 10ec:8168 | 1043:859e | Realtek... | RTL8111/8168/8411 PCI Exp... | 394   | r8169      | 9A23DF55D8 |
| 1969:1048 | 1043:8226 | Qualcom... | Attansic L1 Gigabit Ethernet | 348   | atl1       | 7165A5413A |
| 8086:15a1 | 1043:85c4 | Intel      | Ethernet Connection (2) I... | 301   | e1000e     | 8F3CA163E7 |
| 8086:15b8 | 1458:e000 | Intel      | Ethernet Connection (2) I... | 294   | e1000e     | 834A7AE73B |
| 1969:1083 | 1458:e000 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 286   | atl1c      | 89F6EB0671 |
| 10ec:8168 | 7470:3468 | Realtek... | RTL8111/8168/8411 PCI Exp... | 273   | r8169      | 84D927D279 |
| 10ec:8169 | 10ec:8169 | Realtek... | RTL8169 PCI Gigabit Ether... | 269   | r8169      | 926229BE87 |
| 11ab:4364 | 1043:81f8 | Marvell... | 88E8056 PCI-E Gigabit Eth... | 261   | sky2       | 926229BE87 |
| 8086:15b8 | 1849:15b8 | Intel      | Ethernet Connection (2) I... | 233   | e1000e     | 2BE44DF65D |
| 10ec:8168 | 1043:82c6 | Realtek... | RTL8111/8168/8411 PCI Exp... | 228   | r8169      | 3B96E27283 |
| 10ec:8136 | 1849:8136 | Realtek... | RTL810xE PCI Express Fast... | 222   | r8169      | ADC801308B |
| 10ec:8136 | 10ec:0123 | Realtek... | RTL810xE PCI Express Fast... | 210   | r8169      | 7502A08A7F |
| 1106:3106 | 1186:1405 | VIA Tec... | VT6105/VT6106S [Rhine-III]   | 196   | via_rhine  | C74DDA083F |
| 1969:1091 | 1458:e000 | Qualcom... | AR8161 Gigabit Ethernet      | 193   | alx        | E163EF1C6E |
| 8086:15bc | 1043:8672 | Intel      | Ethernet Connection (7) I... | 185   | e1000e     | 36EBF65D44 |
| 10ec:8168 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 182   | r8169      | 39497CE3AE |
| 1969:1026 | 1043:8304 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 168   | atl1e      | 5101982911 |
| 8086:153b | 1458:e000 | Intel      | Ethernet Connection I217-V   | 168   | e1000e     | A2454FCD1F |
| 8086:15bc | 1458:e000 | Intel      | Ethernet Connection (7) I... | 166   | e1000e     | 197E319075 |
| 10ec:8168 | 1462:7817 | Realtek... | RTL8111/8168/8411 PCI Exp... | 157   | r8169      | 75E2E357A3 |
| 10ec:8168 | 1025:8000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 150   | r8169      | 722016AF18 |
| 10ec:8168 | 1043:87c3 | Realtek... | RTL8111/8168/8411 PCI Exp... | 145   | r8169      | 379D2F0B1C |
| 10ec:8168 | 1462:7c02 | Realtek... | RTL8111/8168/8411 PCI Exp... | 145   | r8169      | 2229C9E9F6 |
| 10ec:8168 | 1462:7c37 | Realtek... | RTL8111/8168/8411 PCI Exp... | 142   | r8169      | 0619809B36 |
| 8086:153a | 1028:05a4 | Intel      | Ethernet Connection I217-LM  | 142   | e1000e     | 0FC3ABDB1C |
| 10ec:8136 | 1043:8347 | Realtek... | RTL810xE PCI Express Fast... | 141   | r8169      | CB1A775980 |
| 11ab:4320 | 1043:811a | Marvell... | 88E8001 Gigabit Ethernet ... | 138   | skge       | 926229BE87 |
| 10ec:8168 | 1043:81aa | Realtek... | RTL8111/8168/8411 PCI Exp... | 133   | r8169      | 4B68AC1130 |
| 10ec:8168 | 1462:7721 | Realtek... | RTL8111/8168/8411 PCI Exp... | 127   | r8169      | 01C5E2E798 |
| 8086:153b | 1043:859f | Intel      | Ethernet Connection I217-V   | 123   | e1000e     | B0F626D0E4 |
| 1969:1026 | 1043:8226 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 112   | atl1e      | 102C78CA6B |
| 1969:10a1 | 1849:10a1 | Qualcom... | QCA8171 Gigabit Ethernet     | 111   | alx        | 615502E93E |
| 1969:2048 | 1043:8233 | Qualcom... | Attansic L2 Fast Ethernet    | 111   | atl2       | 5E2CE09E63 |
| 14e4:16b1 | 1849:96b1 | Broadcom   | NetLink BCM57781 Gigabit ... | 108   | tg3        | E7EBAD7358 |
| 1969:e091 | 1458:e000 | Qualcom... | Killer E220x Gigabit Ethe... | 108   | alx        | DF13F72A9A |
| 10ec:8168 | 1462:7b86 | Realtek... | RTL8111/8168/8411 PCI Exp... | 103   | r8169      | 6787B45989 |
| 1969:1026 | 1043:831c | Qualcom... | AR8121/AR8113/AR8114 Giga... | 102   | atl1e      | 441067C1C2 |
| 8086:15a1 | 1849:15a1 | Intel      | Ethernet Connection (2) I... | 102   | e1000e     | 6FEB0AEC47 |
| 8086:15f3 | 1043:87d2 | Intel      | Ethernet Controller I225-V   | 101   | igc        | BBA08D40AD |
| 10ec:8168 | 1043:8367 | Realtek... | RTL8111/8168/8411 PCI Exp... | 97    | r8169      | 965BC51C8D |
| 1186:4300 | 1186:4300 | D-Link ... | DGE-528T Gigabit Ethernet... | 96    | r8169      | 7A323363EF |
| 10ec:8168 | 1462:7a38 | Realtek... | RTL8111/8168/8411 PCI Exp... | 95    | r8169      | 3056DB282E |
| 1969:1063 | 1458:e000 | Qualcom... | AR8131 Gigabit Ethernet      | 95    | atl1c      | C49097EC08 |
| 1969:1063 | 1043:83fe | Qualcom... | AR8131 Gigabit Ethernet      | 94    | atl1c      | 1B7AF6841F |
| 1969:2062 | 1849:2062 | Qualcom... | AR8152 v2.0 Fast Ethernet    | 89    | atl1c      | B9B144530E |
| 10ec:8168 | 1462:7b79 | Realtek... | RTL8111/8168/8411 PCI Exp... | 85    | r8169      | B8D3749011 |
| 10ec:8168 | 1462:7693 | Realtek... | RTL8111/8168/8411 PCI Exp... | 83    | r8169      | 7641FD618F |
| 10ec:8168 | 1019:811e | Realtek... | RTL8111/8168/8411 PCI Exp... | 82    | r8169      | 3D11EFA233 |
| 10ec:8167 | 1458:e000 | Realtek... | RTL-8110SC/8169SC Gigabit... | 81    | r8169      | FA824FB67B |
| 1969:10a1 | 1043:8587 | Qualcom... | QCA8171 Gigabit Ethernet     | 81    | alx        | 08ED9AF2B9 |
| 8086:15bc | 1849:15bc | Intel      | Ethernet Connection (7) I... | 81    | e1000e     | 839B20476A |
| 10ec:8125 | 1043:879b | Realtek... | RTL8125 2.5GbE Controller    | 80    | r8169      | A133667E3C |
| 10ec:8168 | 1028:0612 | Realtek... | RTL8111/8168/8411 PCI Exp... | 80    | r8169      | 4C34BAF1DC |
| 10ec:8168 | 1028:04f5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 77    | r8169      | 00CE09B473 |
| 10ec:8168 | 1462:7a34 | Realtek... | RTL8111/8168/8411 PCI Exp... | 76    | r8169      | D640900B8A |
| 8086:153b | 1849:153b | Intel      | Ethernet Connection I217-V   | 74    | e1000e     | B2AB848EA5 |
| 10ec:8167 | 1043:820d | Realtek... | RTL-8110SC/8169SC Gigabit... | 73    | r8169      | 458525BA70 |
| 1969:1083 | 1849:1083 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 72    | atl1c      | C3FFE373AA |
| 1969:e0b1 | 1458:e000 | Qualcom... | Killer E2500 Gigabit Ethe... | 72    | alx        | 3CA0951964 |
| 10ec:8168 | 1019:8116 | Realtek... | RTL8111/8168/8411 PCI Exp... | 71    | r8169      | 5A59D31E03 |
| 11ab:4362 | 1043:8142 | Marvell... | 88E8053 PCI-E Gigabit Eth... | 71    | sky2       | 0C04CD404A |
| 14e4:167a | 1028:01da | Broadcom   | NetXtreme BCM5754 Gigabit... | 71    | tg3        | 8939E63ADE |
| 8086:153a | 103c:1998 | Intel      | Ethernet Connection I217-LM  | 71    | e1000e     | D8309CFECF |
| 10ec:8168 | 1462:7b89 | Realtek... | RTL8111/8168/8411 PCI Exp... | 69    | r8169      | 43A19D8280 |
| 10ec:8168 | 1565:2312 | Realtek... | RTL8111/8168/8411 PCI Exp... | 69    | r8169      | 02E5D996C8 |
| 10ec:8168 | 103c:2abf | Realtek... | RTL8111/8168/8411 PCI Exp... | 68    | r8169      | 57FFE115AC |
| 10ec:8168 | 1043:8385 | Realtek... | RTL8111/8168/8411 PCI Exp... | 66    | r8169      | 825C9359F9 |
| 10ec:8168 | 1462:7758 | Realtek... | RTL8111/8168/8411 PCI Exp... | 65    | r8169      | 8755040EA2 |
| 10ec:8168 | 1462:7996 | Realtek... | RTL8111/8168/8411 PCI Exp... | 63    | r8169      | C007D839E7 |
| 14e4:1677 | 1028:01ad | Broadcom   | NetXtreme BCM5751 Gigabit... | 63    | tg3        | 132993403B |
| 10ec:8168 | 1028:0585 | Realtek... | RTL8111/8168/8411 PCI Exp... | 60    | r8169      | F146C310D6 |
| 1969:1091 | 1043:8507 | Qualcom... | AR8161 Gigabit Ethernet      | 60    | alx        | 9B0D9C1623 |
| 10ec:8168 | 103c:2a9c | Realtek... | RTL8111/8168/8411 PCI Exp... | 57    | r8169      | 9A3C939249 |
| 10ec:8168 | 17aa:3098 | Realtek... | RTL8111/8168/8411 PCI Exp... | 57    | r8169      | 2767965856 |
| 14e4:1681 | 1028:0293 | Broadcom   | NetXtreme BCM5761 Gigabit... | 56    | tg3        | ACE51E66CB |
| 14e4:1681 | 103c:3047 | Broadcom   | NetXtreme BCM5761 Gigabit... | 56    | tg3        | 4E44EC3823 |
| 8086:153a | 103c:18e7 | Intel      | Ethernet Connection I217-LM  | 56    | e1000e     | 9844F6635C |
| 10ec:8168 | 1462:7641 | Realtek... | RTL8111/8168/8411 PCI Exp... | 55    | r8169      | 26947ED7FD |
| 13f0:0200 | 13f0:0201 | Sundanc... | IC Plus IP100A Integrated... | 55    | sundance   | FC4FD8BA0E |
| 8086:107c | 8086:1376 | Intel      | 82541PI Gigabit Ethernet ... | 54    | e1000      | 6396BA1A82 |
| 10ec:8168 | 1565:2400 | Realtek... | RTL8111/8168/8411 PCI Exp... | 52    | r8169      | 21134DA958 |
| 1969:1083 | 1043:847e | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 52    | atl1c      | 96DD2D8F2B |
| 10ec:8168 | 103c:2a6f | Realtek... | RTL8111/8168/8411 PCI Exp... | 51    | r8169      | 23D227C928 |
| 1969:e091 | 1462:7693 | Qualcom... | Killer E220x Gigabit Ethe... | 51    | alx        | D0FD1CE0E8 |
| 10ec:8136 | 1019:8348 | Realtek... | RTL810xE PCI Express Fast... | 50    | r8169      | 86BBF996CF |
| 10ec:8168 | 1462:7850 | Realtek... | RTL8111/8168/8411 PCI Exp... | 50    | r8169      | 05DCAC5E7F |
| 10ec:8168 | 8086:d608 | Realtek... | RTL8111/8168/8411 PCI Exp... | 50    | r8169      | 330F034C61 |
| 10de:0760 | 1043:82f2 | Nvidia     | MCP77 Ethernet               | 48    | forcedeth  | 739D1AE9B7 |
| 1969:e0a1 | 1458:e000 | Qualcom... | Killer E2400 Gigabit Ethe... | 48    | alx        | 84D927D279 |
| 10ec:8139 | 11f6:8139 | Realtek... | RTL-8100/8101L/8139 PCI F... | 47    | 8139too... | C54C370494 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2723 | 8086:0084 | Intel      | Wi-Fi 6 AX200                | 870   | iwlwifi    | 20115EE05D |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 498   | iwlwifi    | 6056EAC50C |
| 8086:2526 | 8086:0014 | Intel      | Wireless-AC 9260             | 333   | iwlwifi    | B8D0E81636 |
| 168c:002e | 168c:30a4 | Qualcom... | AR9287 Wireless Network A... | 193   | ath9k      | D2FA60E459 |
| 168c:0032 | 168c:3118 | Qualcom... | AR9485 Wireless Network A... | 183   | ath9k      | 3D11EFA233 |
| 8086:a370 | 8086:0034 | Intel      | Cannon Lake PCH CNVi WiFi    | 164   | iwlwifi    | 36EBF65D44 |
| 168c:0030 | 168c:3112 | Qualcom... | AR93xx Wireless Network A... | 147   | ath9k      | 52C67D407D |
| 14e4:43a0 | 14e4:0619 | Broadcom   | BCM4360 802.11ac Wireless... | 139   | wl         | 834A7AE73B |
| 168c:002d | 168c:0300 | Qualcom... | AR9227 Wireless Network A... | 132   | ath9k      | 8A06C635E9 |
| 10ec:818b | 10ec:8196 | Realtek... | RTL8192EE PCIe Wireless N... | 124   | rtl8192ee  | 8343ECF081 |
| 168c:002d | 168c:0301 | Qualcom... | AR9227 Wireless Network A... | 111   | ath9k      | B453E98364 |
| 8086:08b1 | 8086:4070 | Intel      | Wireless 7260                | 111   | iwlwifi    | 8F3CA163E7 |
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 106   | iwlwifi    | 5913B80A19 |
| 10ec:b822 | 1043:8746 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 96    | r8822be    | 51E1E33185 |
| 8086:24f3 | 8086:0010 | Intel      | Wireless 8260                | 96    | iwlwifi    | FC6D4C2E7D |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 91    | rtl8821ce  | ECBF2FC044 |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 81    | iwlwifi    | 88279B78CF |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 73    | iwlwifi    | F23DE0D726 |
| 10ec:8179 | 10ec:8197 | Realtek... | RTL8188EE Wireless Networ... | 68    | rtl8188ee  | 3EED0A8556 |
| 168c:0034 | 11ad:6621 | Qualcom... | AR9462 Wireless Network A... | 65    | ath9k      | C339545A11 |
| 10ec:8185 | 10ec:8225 | Realtek... | RTL-8185 IEEE 802.11a/b/g... | 62    | rtl818x... | 23D227C928 |
| 10ec:8178 | 1043:84b6 | Realtek... | RTL8192CE PCIe Wireless N... | 61    | rtl8192ce  | 8411C23010 |
| 168c:0032 | 1028:0209 | Qualcom... | AR9485 Wireless Network A... | 61    | ath9k      | 2B158EA18F |
| 1814:3060 | 1186:3c04 | Ralink     | RT3060 Wireless 802.11n 1... | 60    | rt2800pci  | 32AAE9EA9A |
| 1814:5390 | 1814:f051 | Ralink     | RT5390 Wireless 802.11n 1... | 60    | rt2800pci  | 69B2DC2208 |
| 168c:002b | 168c:30a1 | Qualcom... | AR9285 Wireless Network A... | 59    | ath9k      | 6CEB83052E |
| 14e4:43b1 | 1043:855c | Broadcom   | BCM4352 802.11ac Wireless... | 58    | wl         | E456864B06 |
| 168c:0032 | 1043:850d | Qualcom... | AR9485 Wireless Network A... | 57    | ath9k      | 6F05AEA2C1 |
| 8086:06f0 | 8086:0074 | Intel      | Comet Lake PCH CNVi WiFi     | 57    | iwlwifi    | 57A08FFCEB |
| 168c:0032 | 1028:0208 | Qualcom... | AR9485 Wireless Network A... | 56    | ath9k      | 54C021054A |
| 1814:3090 | 11ad:7601 | Ralink     | RT3090 Wireless 802.11n 1... | 56    | rt2800pci  | 99AE75539D |
| 8086:08b3 | 8086:8070 | Intel      | Wireless 3160                | 55    | iwlwifi    | F03F0287F4 |
| 168c:0013 | 1186:3a13 | Qualcom... | AR5212/5213/2414 Wireless... | 52    | ath5k      | EF264215AF |
| 10ec:8176 | 1043:84b5 | Realtek... | RTL8188CE 802.11b/g/n WiF... | 51    | rtl8192ce  | 45F902869D |
| 14e4:43a0 | 1043:85df | Broadcom   | BCM4360 802.11ac Wireless... | 50    | wl         | DFE212DA86 |
| 168c:0036 | 1028:020c | Qualcom... | QCA9565 / AR9565 Wireless... | 49    | ath9k      | B61E8F0ADC |
| 1814:0301 | 1814:2561 | Ralink     | RT2561/RT61 802.11g PCI      | 49    | rt61pci    | F54143A81D |
| 1814:3090 | 11ad:6632 | Ralink     | RT3090 Wireless 802.11n 1... | 48    | rt2800pci  | 6D788B887D |
| 1814:5360 | 1186:3c05 | Ralink     | RT5360 Wireless 802.11n 1... | 48    | rt2800pci  | 7793CDDE60 |
| 8086:a370 | 8086:02a4 | Intel      | Cannon Lake PCH CNVi WiFi    | 48    | iwlwifi    | 5C8AF3A6F6 |
| 168c:003e | 1043:86cd | Qualcom... | QCA6174 802.11ac Wireless... | 45    | ath10k_pci | 9673F97E2A |
| 1814:0302 | 1186:3a71 | Ralink     | RT2561/RT61 rev B 802.11g    | 44    | rt61pci    | B8B1C3026C |
| 10ec:8821 | 1a3b:2161 | Realtek... | RTL8821AE 802.11ac PCIe W... | 42    | rtl8821ae  | B0F626D0E4 |
| 168c:0036 | 1028:020e | Qualcom... | QCA9565 / AR9565 Wireless... | 41    | ath9k      | E19475CD4C |
| 1814:0781 | 11ad:7600 | Ralink     | RT2790 Wireless 802.11n 1... | 41    | rt2800pci  | 29B840017B |
| 8086:24f3 | 8086:1010 | Intel      | Wireless 8260                | 41    | iwlwifi    | 4E988AF2DF |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 40    | iwlwifi    | 7060061F0B |
| 14e4:43a0 | 1043:8659 | Broadcom   | BCM4360 802.11ac Wireless... | 39    | wl         | 5FEA81AFF7 |
| 14e4:43b1 | 1043:85ba | Broadcom   | BCM4352 802.11ac Wireless... | 38    | wl         | 75E2E357A3 |
| 10ec:8176 | 10ec:8176 | Realtek... | RTL8188CE 802.11b/g/n WiF... | 36    | rtl8192ce  | 3F61F1BE35 |
| 14e4:4359 | 1043:850c | Broadcom   | BCM43228 802.11a/b/g/n       | 36    | wl         | 3E15DD7136 |
| 1814:0302 | 1186:3c09 | Ralink     | RT2561/RT61 rev B 802.11g    | 35    | rt61pci    | 447004C124 |
| 10ec:8812 | 1043:86dd | Realtek... | RTL8812AE 802.11ac PCIe W... | 34    | rtl8821ae  | FE7A0A48F9 |
| 168c:001d | 168c:2055 | Qualcom... | AR2417 Wireless Network A... | 34    | ath5k      | BF40420F1C |
| 168c:0042 | 1028:1810 | Qualcom... | QCA9377 802.11ac Wireless... | 34    | ath10k_pci | 12F62738E6 |
| 168c:002b | 1a3b:1089 | Qualcom... | AR9285 Wireless Network A... | 33    | ath9k      | A3EDD93ADA |
| 8086:3165 | 8086:4410 | Intel      | Wireless 3165                | 32    | iwlwifi    | 7C7AE3C0EF |
| 10ec:8812 | 10ec:8203 | Realtek... | RTL8812AE 802.11ac PCIe W... | 31    | rtl8821ae  | 4C34BAF1DC |
| 1814:539b | 103c:18ed | Ralink     | RT5390R 802.11bgn PCIe Wi... | 31    | rt2800pci  | 716FA00268 |
| 1814:3062 | 1814:3062 | Ralink     | RT3062 Wireless 802.11n 2... | 30    | rt2800pci  | 17A4FB05F4 |
| 14e4:432b | 106b:008e | Broadcom   | BCM4322 802.11a/b/g/n Wir... | 29    | wl         | B14BC57EA5 |
| 8086:0887 | 8086:4062 | Intel      | Centrino Wireless-N 2230     | 29    | iwlwifi    | 848DEF4822 |
| 168c:0032 | 103c:1838 | Qualcom... | AR9485 Wireless Network A... | 28    | ath9k      | 6E2FC02F05 |
| 168c:0034 | 1043:850e | Qualcom... | AR9462 Wireless Network A... | 28    | ath9k      | B7DC673E5C |
| 10ec:8821 | 1043:85b4 | Realtek... | RTL8821AE 802.11ac PCIe W... | 27    | rtl8821ae  | 486AEB5B89 |
| 14e4:4318 | 1043:100f | Broadcom   | BCM4318 [AirForce One 54g... | 27    | ssb        | D16E8A4364 |
| 14e4:43c3 | 1043:86fb | Broadcom   | Network controller           | 27    | brcmfmac   | 9F708B7E14 |
| 8086:3165 | 8086:8010 | Intel      | Wireless 3165                | 27    | iwlwifi    | 7C30C0C3CA |
| 168c:001a | 168c:2052 | Qualcom... | AR2413/AR2414 Wireless Ne... | 26    | ath5k      | BB31FB43B4 |
| 10ec:8178 | 10ec:8178 | Realtek... | RTL8192CE PCIe Wireless N... | 24    | rtl8192ce  | 6BDF2E77C2 |
| 168c:0013 | 168c:2051 | Qualcom... | AR5212/5213/2414 Wireless... | 24    | ath5k      | 72861AA353 |
| 10ec:818b | 10ec:818b | Realtek... | RTL8192EE PCIe Wireless N... | 23    | rtl8192ee  | B021A442D9 |
| 10ec:b723 | 103c:81c1 | Realtek... | RTL8723BE PCIe Wireless N... | 23    | rtl8723be  | 41311D3164 |
| 14e4:43a0 | 106b:0111 | Broadcom   | BCM4360 802.11ac Wireless... | 23    | wl         | DE14F99534 |
| 168c:002a | 168c:0203 | Qualcom... | AR928X Wireless Network A... | 23    | ath9k      | 523DACC90C |
| 1814:0301 | 1737:0055 | Ralink     | RT2561/RT61 802.11g PCI      | 23    | rt61pci    | 1CF830ACD9 |
| 168c:0023 | 168c:3071 | Qualcom... | AR5416 Wireless Network A... | 22    | ath9k      | 3B86484258 |
| 10ec:8176 | 10ec:8175 | Realtek... | RTL8188CE 802.11b/g/n WiF... | 21    | rtl8192ce  | 24598CF8F9 |
| 168c:003e | 1043:86e0 | Qualcom... | QCA6174 802.11ac Wireless... | 21    | ath10k_pci | 649A2A1DA2 |
| 168c:003e | 1a56:1535 | Qualcom... | QCA6174 802.11ac Wireless... | 21    | ath10k_pci | 361469C7D5 |
| 8086:08b1 | 8086:4062 | Intel      | Wireless 7260                | 21    | iwlwifi    | FBD56B7E5C |
| 8086:08b1 | 8086:c470 | Intel      | Wireless 7260                | 21    | iwlwifi    | 7694CA4DFD |
| 10ec:8178 | 7392:7622 | Realtek... | RTL8192CE PCIe Wireless N... | 20    | rtl8192ce  | BB6B82930E |
| 10ec:8179 | 17aa:0179 | Realtek... | RTL8188EE Wireless Networ... | 20    | rtl8188ee  | 31CB6E83ED |
| 10ec:b822 | 103c:831b | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 20    | rtwpci     | E3480E8653 |
| 10ec:c821 | 17aa:c024 | Realtek... | RTL8821CE 802.11ac PCIe W... | 20    | rtl8821ce  | 973E323F3C |
| 14e4:43b1 | 1a3b:2123 | Broadcom   | BCM4352 802.11ac Wireless... | 19    | wl         | B2AB848EA5 |
| 1814:0301 | 1043:837e | Ralink     | RT2561/RT61 802.11g PCI      | 19    | rt61pci    | 6F51E88157 |
| 1814:0601 | 1737:0067 | Ralink     | RT2800 802.11n PCI           | 19    | rt2800pci  | 3CEFB90D05 |
| 1814:0781 | 1814:2790 | Ralink     | RT2790 Wireless 802.11n 1... | 19    | rt2800pci  | 7985ADDC49 |
| 1814:3060 | 1814:3060 | Ralink     | RT3060 Wireless 802.11n 1... | 19    | rt2800pci  | FE0008FA30 |
| 1814:5592 | 1043:851a | Ralink     | RT5592 PCIe Wireless Netw... | 19    | rt5592sta  | 0D40DAA834 |
| 10ec:8172 | 10ec:8172 | Realtek... | RTL8191SEvB Wireless LAN ... | 18    | rtl8192se  | DD4A0707BA |
| 10ec:8178 | 1043:85e3 | Realtek... | RTL8192CE PCIe Wireless N... | 18    | rtl8192ce  | 61235DB641 |
| 10ec:8179 | 103c:197d | Realtek... | RTL8188EE Wireless Networ... | 18    | rtl8188ee  | 7358E30BEF |
| 10ec:8185 | 10ec:8185 | Realtek... | RTL-8185 IEEE 802.11a/b/g... | 18    | rtl818x... | 4B6B54B926 |
| 10ec:8821 | 17aa:a814 | Realtek... | RTL8821AE 802.11ac PCIe W... | 18    | rtl8821ae  | B4F62DDDD2 |
| 14e4:43a0 | 106b:0117 | Broadco... | BCM4360 802.11ac Wireless... | 18    | wl         | 11EBF0D551 |
| 168c:0013 | 1186:3a73 | Qualcom... | AR5212/5213/2414 Wireless... | 18    | ath5k      | 7BF96F8DDA |
| 10ec:8812 | 1186:3305 | Realtek... | RTL8812AE 802.11ac PCIe W... | 17    | rtl8821ae  | E97C041E12 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1539 | 1043:85f0 | Intel      | I211 Gigabit Network Conn... | 764   | igb        | 97C17F738A |
| 8086:1539 | 1458:e000 | Intel      | I211 Gigabit Network Conn... | 530   | igb        | 24D2E85009 |
| 8086:1539 | 1849:1539 | Intel      | I211 Gigabit Network Conn... | 438   | igb        | 84FDA964C3 |
| 8086:1503 | 1043:849c | Intel      | 82579V Gigabit Network Co... | 371   | e1000e     | BA117FEF7E |
| 10de:03ef | 1849:03ef | Nvidia     | MCP61 Ethernet               | 366   | forcedeth  | 0B81DF184D |
| 8086:1502 | 1028:052c | Intel      | 82579LM Gigabit Network C... | 205   | e1000e     | 4DAF9FDC0D |
| 8086:1502 | 1028:047e | Intel      | 82579LM Gigabit Network C... | 180   | e1000e     | 959E3DDE54 |
| 10de:03ef | 1458:e000 | Nvidia     | MCP61 Ethernet               | 179   | forcedeth  | FB1E012F68 |
| 8086:10de | 1028:0276 | Intel      | 82567LM-3 Gigabit Network... | 159   | e1000e     | 5824A76242 |
| 8086:10d3 | 8086:a01f | Intel      | 82574L Gigabit Network Co... | 139   | e1000e     | FB37055E96 |
| 10de:03ef | 1043:83a4 | Nvidia     | MCP61 Ethernet               | 138   | forcedeth  | 1C28AB7987 |
| 10ec:8125 | 1458:e000 | Realtek... | RTL8125 2.5GbE Controller    | 124   | r8169      | 6BC1B9DCC9 |
| 10de:03ef | 1043:8234 | Nvidia     | MCP61 Ethernet               | 108   | forcedeth  | A5CA2582B6 |
| 8086:10bd | 1028:0211 | Intel      | 82566DM-2 Gigabit Network... | 94    | e1000e     | 962E0B75E4 |
| 8086:1502 | 103c:3397 | Intel      | 82579LM Gigabit Network C... | 94    | e1000e     | 9C1343DD9B |
| 8086:10de | 1028:027f | Intel      | 82567LM-3 Gigabit Network... | 80    | e1000e     | 8F0C6ED152 |
| 8086:1502 | 103c:339a | Intel      | 82579LM Gigabit Network C... | 76    | e1000e     | BA7CCF28B7 |
| 8086:1502 | 103c:1495 | Intel      | 82579LM Gigabit Network C... | 67    | e1000e     | 660C4FF2ED |
| 8086:10bd | 103c:2818 | Intel      | 82566DM-2 Gigabit Network... | 64    | e1000e     | 92920FF59A |
| 8086:1502 | 103c:1497 | Intel      | 82579LM Gigabit Network C... | 64    | e1000e     | 7FA5AD3E42 |
| 10de:03ef | 1462:7309 | Nvidia     | MCP61 Ethernet               | 63    | forcedeth  | DC2D2CA478 |
| 8086:10de | 103c:3048 | Intel      | 82567LM-3 Gigabit Network... | 59    | e1000e     | 39204D22AE |
| 8086:10c0 | 1028:020d | Intel      | 82562V-2 10/100 Network C... | 58    | e1000e     | 8A955D2C5A |
| 8086:1503 | 1458:e000 | Intel      | 82579V Gigabit Network Co... | 51    | e1000e     | 31B25815EC |
| 10de:0057 | 1043:812a | Nvidia     | CK804 Ethernet Controller    | 50    | forcedeth  | FF54330A37 |
| 10ec:8125 | 1043:87d7 | Realtek... | RTL8125 2.5GbE Controller    | 49    | r8169      | 20115EE05D |
| 8086:1539 | 8086:0000 | Intel      | I211 Gigabit Network Conn... | 48    | igb        | FE4761D2B2 |
| 8086:104a | 103c:2800 | Intel      | 82566DM Gigabit Network C... | 47    | e1000e     | 2D99B2D79D |
| 8086:1503 | 1025:8000 | Intel      | 82579V Gigabit Network Co... | 47    | e1000e     | 1CBEE8A7EF |
| 8086:294c | 8086:0001 | Intel      | 82566DC-2 Gigabit Network... | 46    | e1000e     | AF996AA861 |
| 10de:0373 | 1043:8239 | Nvidia     | MCP55 Ethernet               | 45    | forcedeth  | 476250F98C |
| 8086:1533 | 1043:8557 | Intel      | I210 Gigabit Network Conn... | 44    | igb        | 90E90490B7 |
| 8086:10bd | 103c:281e | Intel      | 82566DM-2 Gigabit Network... | 41    | e1000e     | D3603FD2D2 |
| 8086:10df | 1734:114d | Intel      | 82567LF-3 Gigabit Network... | 41    | e1000e     | A9B9EB3480 |
| 8086:10f0 | 8086:0036 | Intel      | 82578DC Gigabit Network C... | 41    | e1000e     | 15FF525EFC |
| 8086:150c | 1043:8457 | Intel      | 82583V Gigabit Network Co... | 39    | e1000e     | 88DF6AA3A5 |
| 10ec:8125 | 1849:8125 | Realtek... | RTL8125 2.5GbE Controller    | 38    | r8169      | 52789C01CA |
| 1106:3065 | 1043:80ed | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 38    | via_rhine  | 10DB975AB9 |
| 8086:1502 | 17aa:3070 | Intel      | 82579LM Gigabit Network C... | 38    | e1000e     | 6983745C31 |
| 10de:03ef | 103c:2a6c | Nvidia     | MCP61 Ethernet               | 37    | forcedeth  | 78A4331611 |
| 8086:10c0 | 1028:0238 | Intel      | 82562V-2 10/100 Network C... | 37    | e1000e     | 46A56037D1 |
| 8086:10d3 | 1043:8369 | Intel      | 82574L Gigabit Network Co... | 37    | e1000e     | 910CE6A9D9 |
| 8086:10de | 17aa:3048 | Intel      | 82567LM-3 Gigabit Network... | 37    | e1000e     | 7E76E404EC |
| 8086:1502 | 103c:1589 | Intel      | 82579LM Gigabit Network C... | 36    | e1000e     | A4B0EBBEE2 |
| 8086:1539 | 1462:7b85 | Intel      | I211 Gigabit Network Conn... | 36    | igb        | B8D0E81636 |
| 1106:3065 | 1849:3065 | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 35    | via_rhine  | 6410827A2F |
| 8086:10de | 103c:3646 | Intel      | 82567LM-3 Gigabit Network... | 35    | e1000e     | 833B887480 |
| 8086:1502 | 17aa:3083 | Intel      | 82579LM Gigabit Network C... | 35    | e1000e     | C0B8E99E35 |
| 10ec:8125 | 1462:7c91 | Realtek... | RTL8125 2.5GbE Controller    | 34    | r8169      | C4A7A4682B |
| 8086:10f6 | 8086:0000 | Intel      | 82574L Gigabit Network Co... | 34    | e1000e     | DE14F99534 |
| 8086:1502 | 103c:1494 | Intel      | 82579LM Gigabit Network C... | 34    | e1000e     | 646E6E27E3 |
| 8086:1539 | 1462:7a32 | Intel      | I211 Gigabit Network Conn... | 34    | igb        | D3237E56E1 |
| 10de:0057 | 1043:8141 | Nvidia     | CK804 Ethernet Controller    | 33    | forcedeth  | 00B830F623 |
| 10de:03ef | 1565:2505 | Nvidia     | MCP61 Ethernet               | 33    | forcedeth  | FF6423FB29 |
| 8086:10de | 103c:3034 | Intel      | 82567LM-3 Gigabit Network... | 33    | e1000e     | D69CD77C4D |
| 8086:1503 | 8086:2017 | Intel      | 82579V Gigabit Network Co... | 33    | e1000e     | 5B590117DD |
| 10de:03ef | 103c:2a99 | Nvidia     | MCP61 Ethernet               | 31    | forcedeth  | 008B548654 |
| 10ec:8125 | 1462:7c35 | Realtek... | RTL8125 2.5GbE Controller    | 31    | r8169      | A4D2088CC9 |
| 8086:1533 | 1458:e000 | Intel      | I210 Gigabit Network Conn... | 31    | igb        | A2454FCD1F |
| 10de:03ef | 1025:8000 | Nvidia     | MCP61 Ethernet               | 30    | forcedeth  | F0FE18214F |
| 8086:10de | 103c:3035 | Intel      | 82567LM-3 Gigabit Network... | 30    | e1000e     | EA009F77D1 |
| 8086:10f0 | 1025:8000 | Intel      | 82578DC Gigabit Network C... | 30    | e1000e     | 78FC18FCF4 |
| 8086:1533 | 1849:1533 | Intel      | I210 Gigabit Network Conn... | 29    | igb        | 195F9748AD |
| 10ec:8125 | 10ec:0123 | Realtek... | RTL8125 2.5GbE Controller    | 28    | r8169      | F1C998FD68 |
| 8086:104b | 8086:0001 | Intel      | 82566DC Gigabit Network C... | 28    | e1000e     | D76E4B9EC3 |
| 8086:1521 | 15d9:1521 | Intel      | I350 Gigabit Network Conn... | 28    | igb        | F791C179A5 |
| 10b7:9200 | 10b7:1000 | 3Com       | 3c905C-TX/TX-M [Tornado]     | 27    | 3c59x      | 489ED22243 |
| 10ec:8125 | 1462:7c84 | Realtek... | RTL8125 2.5GbE Controller    | 27    | r8169      | 2679A5931A |
| 8086:10ef | 103c:304a | Intel      | 82578DM Gigabit Network C... | 27    | e1000e     | A6862C2A01 |
| 8086:1502 | 103c:3396 | Intel      | 82579LM Gigabit Network C... | 27    | e1000e     | 25FFFCB5C5 |
| 10de:0269 | 1043:8221 | Nvidia     | MCP51 Ethernet Controller    | 26    | forcedeth  | 3965D087B0 |
| 8086:1503 | 8086:2002 | Intel      | 82579V Gigabit Network Co... | 26    | e1000e     | 61AE6AF54A |
| 10b7:9055 | 10b7:9055 | 3Com       | 3c905B 100BaseTX [Cyclone]   | 25    | 3c59x      | DEB3B51A3D |
| 8086:10d3 | 103c:158a | Intel      | 82574L Gigabit Network Co... | 24    | e1000e     | D70166F107 |
| 8086:10f0 | 8086:0000 | Intel      | 82578DC Gigabit Network C... | 24    | e1000e     | A760607F4E |
| 8086:1502 | 17aa:3084 | Intel      | 82579LM Gigabit Network C... | 24    | e1000e     | AFB7518616 |
| 8086:1502 | 8086:0000 | Intel      | 82579LM Gigabit Network C... | 24    | e1000e     | 73BFADA83A |
| 8086:10de | 1734:114d | Intel      | 82567LM-3 Gigabit Network... | 23    | e1000e     | 8159354A14 |
| 8086:10ef | 1028:02da | Intel      | 82578DM Gigabit Network C... | 23    | e1000e     | 1FE360B027 |
| 8086:1502 | 103c:158a | Intel      | 82579LM Gigabit Network C... | 23    | e1000e     | D70166F107 |
| 8086:1503 | 1734:11b7 | Intel      | 82579V Gigabit Network Co... | 23    | e1000e     | BC93EA6C14 |
| 8086:1503 | 1734:11d9 | Intel      | 82579V Gigabit Network Co... | 23    | e1000e     | 051FEEFA31 |
| 10de:0373 | 1458:e000 | Nvidia     | MCP55 Ethernet               | 22    | forcedeth  | DEEA9868FB |
| 10de:0373 | 1462:7250 | Nvidia     | MCP55 Ethernet               | 22    | forcedeth  | BD7BBADAAD |
| 8086:1503 | 8086:0000 | Intel      | 82579V Gigabit Network Co... | 22    | e1000e     | 00C8D54652 |
| 10de:0269 | 1043:816a | Nvidia     | MCP51 Ethernet Controller    | 21    | forcedeth  | 37BC060302 |
| 8086:10d3 | 15d9:10d3 | Intel      | 82574L Gigabit Network Co... | 21    | e1000e     | EF90389802 |
| 8086:10d3 | 8086:0000 | Intel      | 82574L Gigabit Network Co... | 21    | e1000e     | CBFECFEE53 |
| 8086:1502 | 17aa:3077 | Intel      | 82579LM Gigabit Network C... | 21    | e1000e     | 1B01FF9935 |
| 10de:0057 | 1458:e000 | Nvidia     | CK804 Ethernet Controller    | 20    | forcedeth  | 43D0CB9AC1 |
| 10de:03ef | 1019:2242 | Nvidia     | MCP61 Ethernet               | 20    | forcedeth  | 0C41FF9165 |
| 8086:10ef | 103c:304b | Intel      | 82578DM Gigabit Network C... | 20    | e1000e     | DC42BD8E41 |
| 10de:0373 | 1043:cb84 | Nvidia     | MCP55 Ethernet               | 19    | forcedeth  | 11CAEB50AC |
| 10de:03ef | 1565:3407 | Nvidia     | MCP61 Ethernet               | 19    | forcedeth  | 474A2761F9 |
| 10ec:8125 | 1462:7c75 | Realtek... | RTL8125 2.5GbE Controller    | 19    | r8169      | 654C105561 |
| 8086:10ce | 1043:82d5 | Intel      | 82567V-2 Gigabit Network ... | 19    | e1000e     | E0982E1F66 |
| 8086:10de | 17aa:3047 | Intel      | 82567LM-3 Gigabit Network... | 19    | e1000e     | 0D516E5C8A |
| 8086:10ef | 8086:0038 | Intel      | 82578DM Gigabit Network C... | 19    | e1000e     | C4A24B7D58 |
| 8086:1502 | 103c:158b | Intel      | 82579LM Gigabit Network C... | 19    | e1000e     | E7D78D4E6C |
| 8086:1502 | 1734:11b7 | Intel      | 82579LM Gigabit Network C... | 19    | e1000e     | 17A4D716C5 |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1455 | 1022:1455 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1614  |            | D88D9DB618 |
| 1022:145a | 1022:145a | AMD        | Zeppelin/Raven/Raven2 PCI... | 1614  |            | D88D9DB618 |
| 1022:1485 | 1022:1485 | AMD        | Starship/Matisse Reserved... | 1220  |            | 0619809B36 |
| 1022:148a | 1022:148a | AMD        | Starship/Matisse PCIe Dum... | 1168  |            | 0619809B36 |
| 1022:1485 | 1043:87c0 | AMD        | Starship/Matisse Reserved... | 573   |            | 97C17F738A |
| 1022:148a | 1043:87c0 | AMD        | Starship/Matisse PCIe Dum... | 573   |            | 97C17F738A |
| 1022:1455 | 1043:8747 | AMD        | Zeppelin/Renoir PCIe Dumm... | 521   |            | 115EC5ECA4 |
| 1022:145a | 1043:8747 | AMD        | Zeppelin/Raven/Raven2 PCI... | 521   |            | 115EC5ECA4 |
| 1022:1485 | 1043:8808 | AMD        | Starship/Matisse Reserved... | 82    |            | 20115EE05D |
| 1022:148a | 1043:8808 | AMD        | Starship/Matisse PCIe Dum... | 82    |            | 20115EE05D |
| 1022:1485 | 1462:7c02 | AMD        | Starship/Matisse Reserved... | 79    |            | A04EB698F8 |
| 1022:148a | 1462:7c02 | AMD        | Starship/Matisse PCIe Dum... | 79    |            | A04EB698F8 |
| 1022:145a | 1043:876b | AMD        | Zeppelin/Raven/Raven2 PCI... | 61    |            | 1B292E7E77 |
| 1022:145a | 1462:7c02 | AMD        | Zeppelin/Raven/Raven2 PCI... | 53    |            | 2229C9E9F6 |
| 1022:1455 | 1462:7c02 | AMD        | Zeppelin/Renoir PCIe Dumm... | 50    |            | 2229C9E9F6 |
| 1022:1485 | 1462:7b86 | AMD        | Starship/Matisse Reserved... | 49    |            | A42F5B4313 |
| 1022:148a | 1462:7b86 | AMD        | Starship/Matisse PCIe Dum... | 49    |            | A42F5B4313 |
| 1022:145a | 1462:7b86 | AMD        | Zeppelin/Raven/Raven2 PCI... | 47    |            | 6787B45989 |
| 1022:1455 | 1462:7b86 | AMD        | Zeppelin/Renoir PCIe Dumm... | 40    |            | 6787B45989 |
| 1022:145a | 1002:15d8 | AMD        | Zeppelin/Raven/Raven2 PCI... | 37    |            | F6DEFD08D6 |
| 1022:145a | 1458:d000 | AMD        | Zeppelin/Raven/Raven2 PCI... | 37    |            | F544511E0A |
| 1022:1485 | 1462:7b89 | AMD        | Starship/Matisse Reserved... | 37    |            | 43A19D8280 |
| 1022:148a | 1462:7b89 | AMD        | Starship/Matisse PCIe Dum... | 37    |            | 43A19D8280 |
| 1022:145a | 1002:15dd | AMD        | Zeppelin/Raven/Raven2 PCI... | 32    |            | 39FCD76D77 |
| 1022:1485 | 1462:7c35 | AMD        | Starship/Matisse Reserved... | 32    |            | A4D2088CC9 |
| 1022:148a | 1462:7c35 | AMD        | Starship/Matisse PCIe Dum... | 32    |            | A4D2088CC9 |
| 1022:145a | 1462:7a38 | AMD        | Zeppelin/Raven/Raven2 PCI... | 31    |            | CA0C473E06 |
| 1022:1455 | 1462:7a38 | AMD        | Zeppelin/Renoir PCIe Dumm... | 26    |            | 00A14A97A2 |
| 1022:145a | 1462:7b89 | AMD        | Zeppelin/Raven/Raven2 PCI... | 26    |            | 463432C55F |
| 1022:1455 | 1462:7b89 | AMD        | Zeppelin/Renoir PCIe Dumm... | 23    |            | 463432C55F |
| 1022:1485 | 1462:7b85 | AMD        | Starship/Matisse Reserved... | 20    |            | B8D0E81636 |
| 1022:148a | 1462:7b85 | AMD        | Starship/Matisse PCIe Dum... | 20    |            | B8D0E81636 |
| 1022:1485 | 1462:7a38 | AMD        | Starship/Matisse Reserved... | 19    |            | ABF17F0C92 |
| 1022:148a | 1462:7a38 | AMD        | Starship/Matisse PCIe Dum... | 19    |            | ABF17F0C92 |
| 1022:1485 | 1043:87cb | AMD        | Starship/Matisse Reserved... | 18    |            | 1F560968AB |
| 1022:148a | 1043:87cb | AMD        | Starship/Matisse PCIe Dum... | 18    |            | 1F560968AB |
| 1022:1485 | 1043:8747 | AMD        | Starship/Matisse Reserved... | 17    |            | 43660221DC |
| 1022:1485 | 1462:7c95 | AMD        | Starship/Matisse Reserved... | 17    |            | 4A568F856E |
| 1022:148a | 1462:7c95 | AMD        | Starship/Matisse PCIe Dum... | 17    |            | 4A568F856E |
| 1022:1485 | 1462:7c94 | AMD        | Starship/Matisse Reserved... | 16    |            | 640C5ADFC3 |
| 1022:148a | 1462:7c94 | AMD        | Starship/Matisse PCIe Dum... | 16    |            | 640C5ADFC3 |
| 1022:145a | 1462:7b85 | AMD        | Zeppelin/Raven/Raven2 PCI... | 14    |            | 8176B777B9 |
| 1022:1455 | 1462:7b85 | AMD        | Zeppelin/Renoir PCIe Dumm... | 13    |            | 8176B777B9 |
| 1022:1485 | 1043:87e2 | AMD        | Starship/Matisse Reserved... | 10    |            | 76267FCBDA |
| 1022:1485 | 1462:7a40 | AMD        | Starship/Matisse Reserved... | 10    |            | B2B10D4380 |
| 1022:148a | 1043:87e2 | AMD        | Starship/Matisse PCIe Dum... | 10    |            | 76267FCBDA |
| 1022:148a | 1462:7a40 | AMD        | Starship/Matisse PCIe Dum... | 10    |            | B2B10D4380 |
| 1022:1455 | 1462:7a40 | AMD        | Zeppelin/Renoir PCIe Dumm... | 7     |            | BD8CB19ABD |
| 1022:145a | 1462:7a40 | AMD        | Zeppelin/Raven/Raven2 PCI... | 7     |            | BD8CB19ABD |
| 1022:145a | 1462:7b87 | AMD        | Zeppelin/Raven/Raven2 PCI... | 6     |            | 9B8F51B1D4 |
| 1022:1455 | 1462:7b87 | AMD        | Zeppelin/Renoir PCIe Dumm... | 5     |            | 9B8F51B1D4 |
| 1022:145a | 1462:7b79 | AMD        | Zeppelin/Raven/Raven2 PCI... | 5     |            | 2119A5CDC5 |
| 1022:1485 | 1043:876b | AMD        | Starship/Matisse Reserved... | 5     |            | E1B742D511 |
| 1022:1485 | 1462:7c36 | AMD        | Starship/Matisse Reserved... | 5     |            | 26B69278F1 |
| 1022:148a | 1462:7c36 | AMD        | Starship/Matisse PCIe Dum... | 5     |            | 26B69278F1 |
| 1022:1485 | 1028:098e | AMD        | Starship/Matisse Reserved... | 4     |            | E1BC8D1CDD |
| 1022:1485 | 1462:7c34 | AMD        | Starship/Matisse Reserved... | 4     |            | 3D2E576C95 |
| 1022:148a | 1028:098e | AMD        | Starship/Matisse PCIe Dum... | 4     |            | E1BC8D1CDD |
| 1022:148a | 1462:7c34 | AMD        | Starship/Matisse PCIe Dum... | 4     |            | 3D2E576C95 |
| 1022:1455 | 1462:7b90 | AMD        | Zeppelin/Renoir PCIe Dumm... | 3     |            | ABD9798AA8 |
| 1022:145a | 1462:7a33 | AMD        | Zeppelin/Raven/Raven2 PCI... | 3     |            | 26F4437015 |
| 1022:145a | 1462:7b84 | AMD        | Zeppelin/Raven/Raven2 PCI... | 3     |            | 9644A0A56C |
| 1022:145a | 1462:7b90 | AMD        | Zeppelin/Raven/Raven2 PCI... | 3     |            | ABD9798AA8 |
| 1022:145a | 1462:7c52 | AMD        | Zeppelin/Raven/Raven2 PCI... | 3     |            | 0901294419 |
| 1022:1485 | 17aa:1046 | AMD        | Starship/Matisse Reserved... | 3     |            | 2C58A29C2A |
| 1022:148a | 17aa:1046 | AMD        | Starship/Matisse PCIe Dum... | 3     |            | 2C58A29C2A |
| 1022:1455 | 103c:8399 | AMD        | Zeppelin/Renoir PCIe Dumm... | 2     |            | 733813E901 |
| 1022:145a | 1002:1636 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | CBB2AC50E7 |
| 1022:145a | 103c:8399 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 733813E901 |
| 1022:145a | 1462:7c51 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 0EDF382CEE |
| 1022:145a | 1565:170b | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 3DEE7E8842 |
| 1022:1485 | 1462:7c96 | AMD        | Starship/Matisse Reserved... | 2     |            | 1DC1C27798 |
| 1022:1485 | 1849:1485 | AMD        | Starship/Matisse Reserved... | 2     |            | EBCC16470F |
| 1022:148a | 1043:8747 | AMD        | Starship/Matisse PCIe Dum... | 2     |            | 249D6291CB |
| 1022:148a | 1462:7c96 | AMD        | Starship/Matisse PCIe Dum... | 2     |            | 1DC1C27798 |
| 1022:1455 | 1019:9ce5 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 06776696F3 |
| 1022:1455 | 1019:9d10 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 277BBC0E9E |
| 1022:1455 | 1019:a412 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | C47BA626E7 |
| 1022:1455 | 1019:a4cd | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 8106DDD47F |
| 1022:1455 | 17aa:36e1 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 31F5158C61 |
| 1022:1455 | 1849:1455 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 4C4AD9EBE5 |
| 1022:145a | 1019:9ce5 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 06776696F3 |
| 1022:145a | 1019:9d10 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 277BBC0E9E |
| 1022:145a | 1019:a412 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | C47BA626E7 |
| 1022:145a | 1019:a4cd | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 8106DDD47F |
| 1022:145a | 1043:87e1 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | B4240CAD57 |
| 1022:145a | 1462:7a34 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | E451A207B9 |
| 1022:145a | 1462:7a36 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 896590304A |
| 1022:145a | 1462:7a39 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 52C67D407D |
| 1022:145a | 1462:7c37 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 0AB96B7281 |
| 1022:145a | 1462:7c87 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 5B17A6A565 |
| 1022:145a | 17aa:36e1 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 31F5158C61 |
| 1022:145a | 17aa:36e8 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 78596220D1 |
| 1022:145a | 17aa:3706 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | D19A6FB1AD |
| 1022:145a | 1849:145a | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 4C4AD9EBE5 |
| 1022:1485 | 1028:0a8b | AMD        | Starship/Matisse Reserved... | 1     |            | 9F3FE00E5C |
| 1022:1485 | 1043:1bf1 | AMD        | Starship/Matisse Reserved... | 1     |            | 65E2923B50 |
| 1022:1485 | 1043:1c81 | AMD        | Starship/Matisse Reserved... | 1     |            | D748821025 |
| 1022:1485 | 1043:8815 | AMD        | Starship/Matisse Reserved... | 1     |            | 86CEE5AEF6 |
| 1022:1485 | 1462:7b87 | AMD        | Starship/Matisse Reserved... | 1     |            | 98E7FEFA9C |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15e6 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Non-S... | 20    | i2c_amd... | 3F202F2D16 |
| 8086:9d24 |           | Intel      | Skylake-U/Y SPI Controller   | 5     |            | 4F9AEAAD47 |
| 8086:a2a4 |           | Intel      | 200 Series/Z370 Chipset F... | 5     |            | 672448ACFD |
| 104c:9065 |           | Texas I... | TMS320DM642                  | 3     |            | 1AA3233F77 |
| 12ab:0380 | 1cfa:0003 | YUAN Hi... | Game Capture 4K60 Pro        | 3     |            | B4B00787C2 |
| 1b4b:9235 |           | Marvell... | 88SE9235 PCIe 2.0 x2 4-po... | 3     |            | 7F5766D5DA |
| 1b4b:1475 |           | Marvell... |                              | 2     |            | 7F5766D5DA |
| 8086:1533 |           | Intel      | I210 Gigabit Network Conn... | 2     |            | 7F5766D5DA |
| 8086:6f04 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 7F5766D5DA |
| 8086:6f06 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 7F5766D5DA |
| 8086:6f08 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 7F5766D5DA |
| 8086:6f0a |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 7F5766D5DA |
| 8086:8c22 |           | Intel      | 8 Series/C220 Series Chip... | 2     |            | 7F5766D5DA |
| 8086:8c54 |           | Intel      | C224 Series Chipset Famil... | 2     |            | 7F5766D5DA |
| 8086:a135 | 8086:a135 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_i... | C65085AE62 |
| 0014:7a10 |           | Loongso... | Hyper Transport Bridge Co... | 1     |            | DD319B8387 |
| 0040:0000 | 0040:0000 |            |                              | 1     |            | 0FB21440B5 |
| 004c:8400 | 0026:0000 |            |                              | 1     |            | 2C3F07791C |
| 0090:0000 | 0090:0000 |            |                              | 1     |            | B562E609ED |
| 0702:82b0 | 168c:2091 |            |                              | 1     |            | DD64B76A65 |
| 1001:0013 |           | Kolter ... | PCI-OPTO-RELAIS Digital I... | 1     |            | 0C8ACC8327 |
| 1001:0017 |           | Kolter ... | PROTO-3 PCI Prototyping b... | 1     |            | 0C8ACC8327 |
| 100c:8023 | 103c:12f1 | Tseng Labs |                              | 1     |            | AD9D1EDCBB |
| 1022:15e6 | 1849:15e6 | AMD        | Raven/Raven2/Renoir Non-S... | 1     | i2c_amd... | 68C78F3D59 |
| 1106:3038 |           | VIA Tec... | VT82xx/62xx/VX700/8x0/900... | 1     |            | C9A1706533 |
| 1274:5882 |           | Ensoniq    |                              | 1     |            | 3F25A03C59 |
| 12f4:5000 |           | Megatel    |                              | 1     |            | F9A4969283 |
| 168c:0013 | 1186:3813 | Qualcom... | AR5212/5213/2414 Wireless... | 1     | ath5k      | AADAA92671 |
| 1814:0203 |           | Ralink     |                              | 1     |            | 3634FDCD0C |
| 1a39:0004 | 1a39:e020 |            |                              | 1     |            | 93A39661EC |
| 1b7c:0004 | 1b7c:0004 |            | Ceton InfiniTV Network       | 1     |            | 7052D8B8E5 |
| 1f30:130f | 0030:0000 |            |                              | 1     |            | B054EB3BDB |
| 5555:3b00 | 1a39:0004 | Genroco    | Epiphan DVI2PCIe video ca... | 1     |            | 7B434E7D8F |
| 8005:0000 |           |            |                              | 1     |            | 77F07D2D69 |
| 8086:9d35 | 8086:7270 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | B1128F0534 |
| 8086:a135 | 15d9:089a | Intel      | 100 Series/C230 Series Ch... | 1     | intel_i... | 4AFDC738DE |
| 8086:a3a4 |           | Intel      | Comet Lake PCH-V SPI (fla... | 1     | intel_s... | 0D1000E904 |
| a411:0000 | 011b:0808 |            |                              | 1     |            | E79C952746 |
| f810:ffff | ffff:ffff |            |                              | 1     |            | 67CBAFF497 |

### Parallel controller (bidir) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1c00:2170 | 1c00:2170 |            | WCH PCI                      | 2     |            | 33B7149F5C |
| 1407:8000 |           | Lava Co... | Lava Parallel                | 1     | parport_pc | 1733DC0809 |
| 1415:9523 | 1415:0001 | Oxford ... | OX16PCI952 Integrated Par... | 1     | parport_pc | AB95A02DA7 |
| 1415:9523 | 1415:1201 | Oxford ... | OX16PCI952 Integrated Par... | 1     | parport_pc | 217BFD48BD |

### Parallel controller (ecp) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1415:c110 | 1415:c110 | Oxford ... | OXPCIe952 Parallel Port      | 13    | parport_pc | F9F1775D7A |
| 1409:7268 | 1409:0103 | Timedia... | SUN1888 (Dual IEEE1284 pa... | 4     | parport_pc | 135E652BAA |
| 1409:7268 | 1409:0104 | Timedia... | SUN1888 (Dual IEEE1284 pa... | 1     | parport_pc | A989D3CA5D |

### Parallel controller (ieee1284) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 9710:9865 | a000:2000 | MosChip... | PCI 9865 Multi-I/O Contro... | 23    | parport_pc | 5BFD23A80C |
| 9710:9912 | a000:2000 | MosChip... | PCIe 9912 Multi-I/O Contr... | 17    | parport... | D6A6EF19FD |
| 1fd4:1999 | 1fd4:0100 | SUNIX      | Multiport serial controller  | 11    | parport... | 0C76DDBD03 |
| ffff:9865 | a000:2000 | Illegal... | Parallel controller          | 5     |            | C40CA96991 |
| 125b:9100 | a000:2000 | Asix El... | AX99100 PCIe to Multi I/O... | 4     |            | 3B8DDCA28E |
| 1415:8403 | 1415:0000 | Oxford ... | OX9162 Mode 0 (parallel p... | 1     | parport_pc | D66BC8959A |
| 9710:8925 | a000:2100 | MosChip... | MosChip Parallel controller  | 1     |            | 4EDB22DA2D |
| 9710:9901 | a000:2000 | MosChip... | PCIe 9901 Multi-I/O Contr... | 1     | parport_pc | 351B3621FD |

### Performance counters (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2f30 | 8086:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 288   | hswep_u... | B92F4485E6 |
| 8086:2f34 | 8086:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 288   | hswep_u... | B92F4485E6 |
| 8086:2f7d | 8086:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 288   |            | B92F4485E6 |
| 8086:2f36 | 8086:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 257   | hswep_u... | B92F4485E6 |
| 8086:2f37 | 8086:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 257   | hswep_u... | B92F4485E6 |
| 8086:3c44 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to Q... | 127   | snbep_u... | C6DCB137FB |
| 8086:3ce6 | 8086:0000 | Intel      | Xeon E5/Core i7 QuickPath... | 127   |            | C6DCB137FB |
| 8086:3c43 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to P... | 121   | snbep_u... | C6DCB137FB |
| 8086:0e36 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 110   | ivbep_u... | 150AFCB2D1 |
| 8086:0e34 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 89    | ivbep_u... | 150AFCB2D1 |
| 8086:2015 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 87    |            | 52789C01CA |
| 8086:204c | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 87    | skx_uncore | 52789C01CA |
| 8086:204d | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 87    | skx_uncore | 52789C01CA |
| 8086:3c43 | 1043:84ef | Intel      | Xeon E5/Core i7 Ring to P... | 78    | snbep_u... | 610B68BB7B |
| 8086:3c44 | 1043:84ef | Intel      | Xeon E5/Core i7 Ring to Q... | 78    | snbep_u... | 610B68BB7B |
| 8086:3c46 | 1043:84ef | Intel      | Xeon E5/Core i7 Processor... | 78    | snbep_u... | 610B68BB7B |
| 8086:3ce6 | 1043:84ef | Intel      | Xeon E5/Core i7 QuickPath... | 78    |            | 610B68BB7B |
| 8086:6f30 | 8086:6f30 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 75    | bdx_uncore | 4860ACD042 |
| 8086:6f34 | 8086:6f34 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 75    | bdx_uncore | 4860ACD042 |
| 8086:6f7d | 8086:6f7d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 75    |            | 4860ACD042 |
| 8086:6f36 | 8086:6f36 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 65    | bdx_uncore | 4860ACD042 |
| 8086:6f37 | 8086:6f37 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 65    | bdx_uncore | 4860ACD042 |
| 8086:2f38 | 8086:2f38 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 64    | hswep_u... | B92F4485E6 |
| 8086:3c46 | 8086:0000 | Intel      | Xeon E5/Core i7 Processor... | 63    | snbep_u... | C6DCB137FB |
| 8086:3c46 |           | Intel      | Xeon E5/Core i7 Processor... | 61    | snbep_u... | A4B0EBBEE2 |
| 8086:0e30 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 49    | ivbep_u... | 150AFCB2D1 |
| 8086:0e30 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 45    | ivbep_u... | F0DC31F93D |
| 8086:0e34 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 45    | ivbep_u... | F0DC31F93D |
| 8086:0e36 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 45    | ivbep_u... | F0DC31F93D |
| 8086:0e30 |           | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 40    | ivbep_u... | 730C09F9E6 |
| 8086:3424 |           | Intel      | 7500/5520/5500/X58 Perfor... | 36    |            | DE14F99534 |
| 8086:2f32 | 8086:2f32 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 33    | hswep_u... | 3991895525 |
| 8086:2f33 | 8086:2f33 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 31    | hswep_u... | 3991895525 |
| 8086:2f30 | 1849:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 27    | hswep_u... | 6FEB0AEC47 |
| 8086:2f34 | 1849:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 27    | hswep_u... | 6FEB0AEC47 |
| 8086:2f36 | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 27    | hswep_u... | 09B0FBCF47 |
| 8086:2f36 | 1849:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 27    | hswep_u... | 6FEB0AEC47 |
| 8086:2f37 | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 27    | hswep_u... | 09B0FBCF47 |
| 8086:2f37 | 1849:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 27    | hswep_u... | 6FEB0AEC47 |
| 8086:2f7d | 1849:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 27    |            | 6FEB0AEC47 |
| 8086:3c43 | 1458:3c43 | Intel      | Xeon E5/Core i7 Ring to P... | 22    | snbep_u... | 912C8764EF |
| 8086:3c44 | 1458:3c44 | Intel      | Xeon E5/Core i7 Ring to Q... | 22    | snbep_u... | 912C8764EF |
| 8086:3c46 | 1458:3c46 | Intel      | Xeon E5/Core i7 Processor... | 22    | snbep_u... | 912C8764EF |
| 8086:3ce6 | 1458:3ce6 | Intel      | Xeon E5/Core i7 QuickPath... | 22    |            | 912C8764EF |
| 8086:2088 |           | Intel      | Sky Lake-E DDRIO Registers   | 18    | skx_uncore | 862B2D2013 |
| 8086:3c43 | 1028:0497 | Intel      | Xeon E5/Core i7 Ring to P... | 17    | snbep_u... | 536202A82C |
| 8086:3c44 | 1028:0497 | Intel      | Xeon E5/Core i7 Ring to Q... | 17    | snbep_u... | 536202A82C |
| 8086:3c46 | 1028:0497 | Intel      | Xeon E5/Core i7 Processor... | 17    | snbep_u... | 536202A82C |
| 8086:3ce6 | 1028:0497 | Intel      | Xeon E5/Core i7 QuickPath... | 17    |            | 536202A82C |
| 8086:2015 | 1028:0738 | Intel      | Sky Lake-E Ubox Registers    | 15    |            | 862B2D2013 |
| 8086:204c | 1028:0738 | Intel      | Sky Lake-E M3KTI Registers   | 15    | skx_uncore | 862B2D2013 |
| 8086:204d | 1028:0738 | Intel      | Sky Lake-E M3KTI Registers   | 15    | skx_uncore | 862B2D2013 |
| 8086:0e30 | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 14    | ivbep_u... | 8C9DD0E965 |
| 8086:0e34 | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 14    | ivbep_u... | 8C9DD0E965 |
| 8086:6f32 | 8086:6f32 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 14    | bdx_uncore | 4C55DE0B30 |
| 8086:6f33 | 8086:6f33 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 14    | bdx_uncore | 4C55DE0B30 |
| 8086:0e37 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 13    | ivbep_u... | 27399D8580 |
| 8086:3c43 | 1849:3c43 | Intel      | Xeon E5/Core i7 Ring to P... | 13    | snbep_u... | 87E9E3FF1C |
| 8086:3c44 | 1849:3c44 | Intel      | Xeon E5/Core i7 Ring to Q... | 13    | snbep_u... | 87E9E3FF1C |
| 8086:3c46 | 1849:3c46 | Intel      | Xeon E5/Core i7 Processor... | 13    | snbep_u... | 87E9E3FF1C |
| 8086:3ce6 | 1849:3ce6 | Intel      | Xeon E5/Core i7 QuickPath... | 13    |            | 87E9E3FF1C |
| 8086:6f38 | 8086:6f38 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 13    | bdx_uncore | 4860ACD042 |
| 8086:2088 | 8086:0000 | Intel      | Sky Lake-E DDRIO Registers   | 12    | skx_uncore | 52789C01CA |
| 8086:6f30 | 1849:6f30 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 11    | bdx_uncore | 70928B7215 |
| 8086:6f34 | 1849:6f34 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 11    | bdx_uncore | 70928B7215 |
| 8086:6f36 | 1849:6f36 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 11    | bdx_uncore | 70928B7215 |
| 8086:6f37 | 1849:6f37 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 11    | bdx_uncore | 70928B7215 |
| 8086:6f7d | 1849:6f7d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 11    |            | 70928B7215 |
| 8086:3c43 | 8086:4953 | Intel      | Xeon E5/Core i7 Ring to P... | 9     | snbep_u... | 4D5E452411 |
| 8086:3c44 | 8086:4953 | Intel      | Xeon E5/Core i7 Ring to Q... | 9     | snbep_u... | 4D5E452411 |
| 8086:3c46 | 8086:4953 | Intel      | Xeon E5/Core i7 Processor... | 9     | snbep_u... | 4D5E452411 |
| 8086:3ce6 | 8086:4953 | Intel      | Xeon E5/Core i7 QuickPath... | 9     |            | 4D5E452411 |
| 8086:0e30 | 1458:3c46 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 7     | ivbep_u... | B3247E5E9F |
| 8086:0e34 | 1458:3c43 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 7     | ivbep_u... | B3247E5E9F |
| 8086:0e36 | 1458:3c44 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 7     | ivbep_u... | B3247E5E9F |
| 8086:2015 | 1734:122f | Intel      | Sky Lake-E Ubox Registers    | 6     |            | 9BF79EF1CD |
| 8086:204c | 1734:122f | Intel      | Sky Lake-E M3KTI Registers   | 6     |            | 9BF79EF1CD |
| 8086:204d | 1734:122f | Intel      | Sky Lake-E M3KTI Registers   | 6     | skx_uncore | 9BF79EF1CD |
| 8086:2f38 | 1849:2f38 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 6     | hswep_u... | 9CACD1608E |
| 8086:3c43 | 1028:0496 | Intel      | Xeon E5/Core i7 Ring to P... | 6     | snbep_u... | 80E68A5C66 |
| 8086:3c44 | 1028:0496 | Intel      | Xeon E5/Core i7 Ring to Q... | 6     | snbep_u... | 80E68A5C66 |
| 8086:3c46 | 1028:0496 | Intel      | Xeon E5/Core i7 Processor... | 6     | snbep_u... | 80E68A5C66 |
| 8086:3ce6 | 1028:0496 | Intel      | Xeon E5/Core i7 QuickPath... | 6     |            | 80E68A5C66 |
| 8086:0e30 | 1028:05d4 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 5     | ivbep_u... | 0D40B6190B |
| 8086:0e30 | 1849:0e30 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 5     | ivbep_u... | D3383D57EF |
| 8086:0e34 | 1028:05d4 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 5     | ivbep_u... | 0D40B6190B |
| 8086:0e34 | 1849:0e34 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 5     | ivbep_u... | D3383D57EF |
| 8086:0e36 | 1849:0e36 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 5     | ivbep_u... | D3383D57EF |
| 8086:2058 | 8086:0000 | Intel      | Sky Lake-E KTI 0             | 5     | skx_uncore | 0C434691D6 |
| 8086:2088 | 1028:0738 | Intel      | Sky Lake-E DDRIO Registers   | 5     | skx_uncore | 862B2D2013 |
| 8086:3c43 | 1028:0495 | Intel      | Xeon E5/Core i7 Ring to P... | 5     | snbep_u... | 1AC850D5B7 |
| 8086:3c43 | 1734:11b5 | Intel      | Xeon E5/Core i7 Ring to P... | 5     | snbep_u... | 85A9B68DD8 |
| 8086:3c44 | 1028:0495 | Intel      | Xeon E5/Core i7 Ring to Q... | 5     | snbep_u... | 1AC850D5B7 |
| 8086:3c44 | 1734:11b5 | Intel      | Xeon E5/Core i7 Ring to Q... | 5     | snbep_u... | 85A9B68DD8 |
| 8086:3c46 | 1028:0495 | Intel      | Xeon E5/Core i7 Processor... | 5     | snbep_u... | 1AC850D5B7 |
| 8086:3c46 | 1734:11b5 | Intel      | Xeon E5/Core i7 Processor... | 5     | snbep_u... | 85A9B68DD8 |
| 8086:3ce6 | 1028:0495 | Intel      | Xeon E5/Core i7 QuickPath... | 5     |            | 1AC850D5B7 |
| 8086:3ce6 | 1734:11b5 | Intel      | Xeon E5/Core i7 QuickPath... | 5     |            | 85A9B68DD8 |
| 8086:3c41 | 8086:0000 | Intel      | Sandy Bridge QPI Port 0 P... | 4     | snbep_u... | 813E405E39 |
| 8086:3c42 | 8086:0000 | Intel      | Sandy Bridge QPI Port 1 P... | 4     | snbep_u... | 813E405E39 |

### Pic (8259) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3422 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 562   |            | 2E1659CD91 |
| 8086:3423 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 562   |            | 2E1659CD91 |
| 8086:342e |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 562   | i7core_... | 2E1659CD91 |
| 8086:3438 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 334   | i5500_temp | 2E1659CD91 |
| 8086:3425 |           | Intel      | 7500/5520/5500/X58 Physic... | 241   |            | 7A75936B55 |
| 8086:3426 |           | Intel      | 7500/5520/5500/X58 Routin... | 241   |            | 7A75936B55 |
| 8086:3427 |           | Intel      | 7500/5520/5500 Physical a... | 211   |            | DFA7EF3696 |
| 8086:3428 |           | Intel      | 7500/5520/5500 Routing & ... | 211   |            | DFA7EF3696 |
| 8086:3422 | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 57    |            | ACE51E66CB |
| 8086:3423 | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 57    |            | ACE51E66CB |
| 8086:342e | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 57    | i7core_... | ACE51E66CB |
| 8086:3422 | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 24    |            | 69CBBFEC14 |
| 8086:3423 | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 24    |            | 69CBBFEC14 |
| 8086:342e | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 24    | i7core_... | 69CBBFEC14 |
| 8086:3422 | 0086:0022 | Intel      | 7500/5520/5500/X58 I/O Hu... | 21    |            | DD68978E2B |
| 8086:3423 | 0086:0023 | Intel      | 7500/5520/5500/X58 I/O Hu... | 21    |            | DD68978E2B |
| 8086:342e | 0086:002e | Intel      | 7500/5520/5500/X58 I/O Hu... | 21    | i7core_... | DD68978E2B |
| 8086:3422 | 0028:006d | Intel      | 7500/5520/5500/X58 I/O Hu... | 19    |            | 08F4C825CC |
| 8086:3423 | 0028:006d | Intel      | 7500/5520/5500/X58 I/O Hu... | 19    |            | 08F4C825CC |
| 8086:342e | 0028:006d | Intel      | 7500/5520/5500/X58 I/O Hu... | 19    | i7core_... | 08F4C825CC |
| 8086:3422 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 12    |            | 2ED58CCD22 |
| 8086:3423 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 12    |            | 2ED58CCD22 |
| 8086:342e | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 12    | i7core_... | 2ED58CCD22 |
| 8086:3422 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     |            | 1B777C6F08 |
| 8086:3423 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     |            | 1B777C6F08 |
| 8086:3425 | 0043:0063 | Intel      | 7500/5520/5500/X58 Physic... | 7     |            | 1B777C6F08 |
| 8086:3426 | 0043:0063 | Intel      | 7500/5520/5500/X58 Routin... | 7     |            | 1B777C6F08 |
| 8086:3427 | 0043:0063 | Intel      | 7500/5520/5500 Physical a... | 7     |            | 1B777C6F08 |
| 8086:3428 | 0043:0063 | Intel      | 7500/5520/5500 Routing & ... | 7     |            | 1B777C6F08 |
| 8086:342e | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     | i7core_... | 1B777C6F08 |
| 8086:3438 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     | i5500_temp | 1B777C6F08 |

### Pic (io(x)-apic) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:342f |           | Intel      | 7500/5520/5500/X58 Truste... | 210   |            | DFA7EF3696 |
| 8086:2f2c | 8086:0000 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 192   |            | B92F4485E6 |
| 8086:342d |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 126   |            | 3EC420C60A |
| 8086:3c2c | 8086:3c2c | Intel      | Xeon E5/Core i7 I/O APIC     | 123   |            | C6DCB137FB |
| 8086:0e2c | 8086:0e2c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 83    |            | 150AFCB2D1 |
| 8086:2026 | 8086:2026 | Intel      | Sky Lake-E IOAPIC            | 80    |            | 52789C01CA |
| 8086:2036 | 8086:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 80    |            | 52789C01CA |
| 8086:3c2c | 1043:84ef | Intel      | Xeon E5/Core i7 I/O APIC     | 78    |            | 610B68BB7B |
| 8086:6f2c | 8086:0000 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 48    |            | 4860ACD042 |
| 1106:5327 |           | VIA Tec... | P4M890 I/O APIC Interrupt... | 47    |            | BA603AC9C0 |
| 8086:0e2c | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 45    |            | F0DC31F93D |
| 1106:5364 |           | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 39    |            | 80CC3448B0 |
| 8086:2f2c | 1849:2f2c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 27    |            | 6FEB0AEC47 |
| 8086:2f2c | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 24    |            | 09B0FBCF47 |
| 8086:3c2c | 1458:5000 | Intel      | Xeon E5/Core i7 I/O APIC     | 22    |            | 912C8764EF |
| 1106:5308 | 1849:5308 | VIA Tec... | PT894 I/O APIC Interrupt ... | 21    |            | 517B90D6F4 |
| 8086:2f2c | 1028:0617 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 20    |            | C050F79E2B |
| 8086:3504 |           | Intel      | 6311ESB/6321ESB I/OxAPIC ... | 18    |            | 41C18A9562 |
| 8086:3c2c | 1028:0497 | Intel      | Xeon E5/Core i7 I/O APIC     | 17    |            | 536202A82C |
| 1106:5336 |           | VIA Tec... | K8M890CE I/O APIC Interru... | 16    |            | D58077C2D7 |
| 8086:2026 | 1028:0738 | Intel      | Sky Lake-E IOAPIC            | 15    |            | 862B2D2013 |
| 8086:2036 | 1028:0738 | Intel      | Sky Lake-E IOxAPIC Config... | 15    |            | 862B2D2013 |
| 8086:0e2c | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 14    |            | 8C9DD0E965 |
| 8086:3c2c | 1849:3c2c | Intel      | Xeon E5/Core i7 I/O APIC     | 13    |            | 87E9E3FF1C |
| 1106:5364 | 1106:5364 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 12    |            | F3B2236C7A |
| 8086:0e2c | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 12    |            | 27399D8580 |
| 8086:2f2c | 1028:0618 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 11    |            | 7172CF4F40 |
| 8086:6f2c | 1849:6f2c | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 11    |            | 70928B7215 |
| 8086:3c2c | 8086:4953 | Intel      | Xeon E5/Core i7 I/O APIC     | 10    |            | 4D5E452411 |
| 8086:0e2c | 1458:5000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 7     |            | B3247E5E9F |
| 8086:2026 | 8086:0000 | Intel      | Sky Lake-E IOAPIC            | 7     |            | 672448ACFD |
| 8086:2036 | 8086:0000 | Intel      | Sky Lake-E IOxAPIC Config... | 7     |            | 672448ACFD |
| 8086:6f2c | 1028:0617 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 7     |            | 3440F55127 |
| 8086:2026 | 1734:122f | Intel      | Sky Lake-E IOAPIC            | 6     |            | 9BF79EF1CD |
| 8086:2036 | 1734:122f | Intel      | Sky Lake-E IOxAPIC Config... | 6     |            | 9BF79EF1CD |
| 8086:3c2c | 1028:0496 | Intel      | Xeon E5/Core i7 I/O APIC     | 6     |            | 80E68A5C66 |
| 1106:5351 |           | VIA Tec... | VT3351 I/O APIC Interrupt... | 5     |            | 9B7D8BD5FF |
| 1106:5364 | 1849:5364 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 5     |            | 6410827A2F |
| 8086:0e2c | 1028:05d4 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 5     |            | 0D40B6190B |
| 8086:0e2c | 1849:0e2c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 5     |            | D3383D57EF |
| 8086:3c2c | 1028:0495 | Intel      | Xeon E5/Core i7 I/O APIC     | 5     |            | 1AC850D5B7 |
| 8086:3c2c | 1734:11b5 | Intel      | Xeon E5/Core i7 I/O APIC     | 5     |            | 85A9B68DD8 |
| 1106:5238 |           | VIA Tec... | K8T890 I/O APIC Interrupt... | 4     |            | D9174E33E4 |
| 1106:5336 | 1043:8297 | VIA Tec... | K8M890CE I/O APIC Interru... | 4     |            | CED2DCBAC9 |
| 1106:5364 | 1019:2125 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 4     |            | 814C427D36 |
| 8086:0326 | 103c:12f1 | Intel      | 6700/6702PXH I/OxAPIC Int... | 4     |            | AD9D1EDCBB |
| 8086:0327 | 103c:12f1 | Intel      | 6700PXH I/OxAPIC Interrup... | 4     |            | AD9D1EDCBB |
| 8086:2f2c | 1028:0619 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | F96F352657 |
| 8086:2f2c | 1028:064c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | 82F399DFE3 |
| 8086:3c2c | 1028:05d4 | Intel      | Xeon E5/Core i7 I/O APIC     | 4     |            | F62AEF3E7A |
| 8086:3c2c | 17aa:1026 | Intel      | Xeon E5/Core i7 I/O APIC     | 4     |            | 7EB1F254C9 |
| 8086:3c2c | 17aa:1027 | Intel      | Xeon E5/Core i7 I/O APIC     | 4     |            | E3C6A7B793 |
| 8086:6f2c | 1462:7885 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     |            | 6F27FFD7AA |
| 1106:5327 | 1631:e035 | VIA Tec... | P4M890 I/O APIC Interrupt... | 3     |            | 089D020111 |
| 8086:0e2c | 1734:11b5 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     |            | D018E3FE5A |
| 8086:2026 | 17aa:1036 | Intel      | Sky Lake-E IOAPIC            | 3     |            | E7CE5A5A00 |
| 8086:2036 | 17aa:1036 | Intel      | Sky Lake-E IOxAPIC Config... | 3     |            | E7CE5A5A00 |
| 8086:3c2c | 1028:0541 | Intel      | Xeon E5/Core i7 I/O APIC     | 3     |            | BEA2C0B6F8 |
| 8086:3c2c | 1462:7735 | Intel      | Xeon E5/Core i7 I/O APIC     | 3     |            | 02CD4D8346 |
| 1106:5327 | 1849:5327 | VIA Tec... | P4M890 I/O APIC Interrupt... | 2     |            | DAD584057B |
| 8086:0326 |           | Intel      | 6700/6702PXH I/OxAPIC Int... | 2     |            | 96D2EFD1F4 |
| 8086:0326 | 15d9:7980 | Intel      | 6700/6702PXH I/OxAPIC Int... | 2     |            | 8EB1C21341 |
| 8086:0e2c | 1028:05d3 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | EDCCC7AAD2 |
| 8086:0e2c | 17aa:1026 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | 4EBE8CAFC5 |
| 8086:0e2c | 17aa:1028 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | 20CB7C14F8 |
| 8086:2026 | 1028:08b1 | Intel      | Sky Lake-E IOAPIC            | 2     |            | 84A5D1B575 |
| 8086:2026 | 17aa:103c | Intel      | Sky Lake-E IOAPIC            | 2     |            | C4DC7ABDFF |
| 8086:2036 | 1028:08b1 | Intel      | Sky Lake-E IOxAPIC Config... | 2     |            | 84A5D1B575 |
| 8086:2036 | 17aa:103c | Intel      | Sky Lake-E IOxAPIC Config... | 2     |            | C4DC7ABDFF |
| 8086:3c2c | 1028:05d2 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | 240DD467A0 |
| 8086:3c2c | 1462:7760 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | 748D276276 |
| 8086:3c2c | 17aa:1028 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | 4FFFF27D89 |
| 8086:6f2c | 1028:064c | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | E31C5F36AA |
| 8086:6f2c | 1462:7883 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 64A313C9E3 |
| 1106:5308 | 1043:8199 | VIA Tec... | PT894 I/O APIC Interrupt ... | 1     |            | C469D16946 |
| 1106:5308 | 1106:5308 | VIA Tec... | PT894 I/O APIC Interrupt ... | 1     |            | BFA978DEF2 |
| 1106:5336 | 1043:80ed | VIA Tec... | K8M890CE I/O APIC Interru... | 1     |            | 40BED765AC |
| 1106:5351 | 1849:5351 | VIA Tec... | VT3351 I/O APIC Interrupt... | 1     |            | D3A94CD051 |
| 1106:5353 |           | VIA Tec... | VX800/VX820 APIC and Cent... | 1     |            | 503D9A6D06 |
| 1106:5409 | 1106:5409 | VIA Tec... | VX855/VX875 APIC and Cent... | 1     |            | 655547B351 |
| 8086:0326 | 15d9:d980 | Intel      | 6700/6702PXH I/OxAPIC Int... | 1     |            | 2ABE7E149C |
| 8086:0327 |           | Intel      | 6700PXH I/OxAPIC Interrup... | 1     |            | 219383F559 |
| 8086:0e2c | 1028:0541 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | BC3B5377F0 |
| 8086:0e2c | 1462:7737 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 725B24FE69 |
| 8086:0e2c | 15d9:062b | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | F791C179A5 |
| 8086:0e2c | 15d9:0702 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | E1213C0B05 |
| 8086:0e2c | 15d9:070a | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F3561AA7D |
| 8086:0e2c | 15d9:070e | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | DABC79444D |
| 8086:1461 | 1014:1461 | Intel      | 82870P2 P64H2 I/OxAPIC       | 1     |            | D6D105AE70 |
| 8086:1461 | 1028:012c | Intel      | 82870P2 P64H2 I/OxAPIC       | 1     |            | 90378ABAC3 |
| 8086:1461 | 15d9:3780 | Intel      | 82870P2 P64H2 I/OxAPIC       | 1     |            | 34867AD122 |
| 8086:25ac |           | Intel      | 6300ESB I/O Advanced Prog... | 1     |            | 21330F2BD7 |
| 8086:25ac | 1043:8117 | Intel      | 6300ESB I/O Advanced Prog... | 1     |            | A9C46A46ED |
| 8086:25ac | 8086:345c | Intel      | 6300ESB I/O Advanced Prog... | 1     |            | 727097891C |
| 8086:25ac | 8086:345e | Intel      | 6300ESB I/O Advanced Prog... | 1     |            | 97CC3C4274 |
| 8086:2f2c | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 02F86A0A2A |
| 8086:2f2c | 1462:7882 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 1E0208BF20 |
| 8086:2f2c | 1462:7883 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 97691EF76E |
| 8086:2f2c | 15d9:0833 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 6BAC3401A1 |
| 8086:2f2c | 15d9:0852 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 2E6D79F345 |

### Pic (io-apic) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:7451 | 1022:7450 | AMD        | AMD-8131 PCI-X IOAPIC        | 4     |            | A94946D561 |
| 1022:7459 | 1022:7459 | AMD        | AMD-8132 PCI-X IOAPIC        | 1     |            | 677776B636 |

### Power pc (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1957:c006 | 1a56:1201 | Freesca... | MPC8308                      | 6     |            | 7DC713CD9F |
| 1957:00b6 | 1a56:1103 | Freesca... | MPC8314E                     | 2     |            | B07AC7C26E |
| 1957:0085 | 110a:4046 | Freesca... | MPC8347 PBGA                 | 1     |            | 60A7685D8D |
| 1957:00b6 | 1a56:1101 | Freesca... | MPC8314E                     | 1     |            | FC18CDC2FD |

### Processing accelerators (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ee:5000 | 10ee:000e | Xilinx     | Processing accelerators      | 1     | xclmgmt    | 774E748AB4 |
| 10ee:5001 | 10ee:000e | Xilinx     | Processing accelerators      | 1     | xocl       | 774E748AB4 |
| 10ee:d020 | 10ee:000e | Xilinx     | Processing accelerators      | 1     | xclmgmt    | 7C4EF83797 |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:7806 | 1022:7806 | AMD        | FCH SD Flash Controller      | 55    | sdhci_pci  | 0B29DCFBC0 |
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 53    | sdhci_pci  | 3E408E9EAD |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 25    | sdhci_pci  | 704DB88794 |
| 8086:31d0 | 8086:7270 | Intel      | SD Host Controller           | 22    | sdhci_pci  | 3E408E9EAD |
| 8086:9d2b | 8086:7270 | Intel      | Skylake-U/Y SCC: eMMC        | 22    | sdhci_pci  | B1128F0534 |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 21    | sdhci_pci  | 704DB88794 |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 20    | sdhci_pci  | 704DB88794 |
| 8086:9d2d | 8086:7270 | Intel      | Sunrise Point-LP Secure D... | 19    | sdhci_pci  | B1128F0534 |
| 8086:9dc4 | 8086:7270 | Intel      | 300 Series Chipset SD Hos... | 11    | sdhci_pci  | D1CA5138F2 |
| 8086:9df5 | 8086:7270 | Intel      | BayHubTech Integrated SD ... | 10    | sdhci_pci  | 733B8D0260 |
| 8086:a375 | 103c:843f | Intel      | 300 Series Chipset Family... | 10    | sdhci_pci  | DFA11821CD |
| 8086:31cc | 1458:1000 | Intel      | Celeron/Pentium Silver Pr... | 9     | sdhci_pci  | 07B81A2502 |
| 8086:31d0 | 1458:1000 | Intel      | SD Host Controller           | 9     | sdhci_pci  | 07B81A2502 |
| 1022:7813 | 1022:7806 | AMD        | FCH SD Flash Controller      | 8     | sdhci_pci  | B5E6FC8BA0 |
| 10ec:5209 | 10ec:5209 | Realtek... | RTS5209 PCI Express Card ... | 8     | rtsx_pci   | FFB8AD31E5 |
| 197b:2381 | 1297:2005 | JMicron... | Standard SD Host Controller  | 7     | sdhci_pci  | 2154B6A111 |
| 8086:2294 | 1458:1000 | Intel      | Atom/Celeron/Pentium Proc... | 7     | sdhci_pci  | 754EA78372 |
| 8086:a375 | 103c:8653 | Intel      | 300 Series Chipset Family... | 7     | sdhci_pci  | A9B6E036CD |
| 1022:7906 | 17aa:3100 | AMD        | FCH SD Flash Controller      | 6     | sdhci_pci  | BBFCF94452 |
| 197b:2381 | 103c:2aa2 | JMicron... | Standard SD Host Controller  | 6     | sdhci_pci  | CEEBC6A90B |
| 8086:a375 | 103c:843b | Intel      | 300 Series Chipset Family... | 6     | sdhci_pci  | 08F01868CF |
| 8086:06f5 | 103c:8767 | Intel      | 400 Series Chipset Family... | 5     | sdhci_pci  | 4BFFD20068 |
| 8086:a375 | 103c:844c | Intel      | 300 Series Chipset Family... | 5     | sdhci_pci  | 29F7CF64CE |
| 8086:a375 | 1849:a375 | Intel      | 300 Series Chipset Family... | 5     | sdhci_pci  | 419277B830 |
| 1022:7813 | 1022:7813 | AMD        | FCH SD Flash Controller      | 4     | sdhci_pci  | 745C41CC7D |
| 1022:7906 | 103c:8459 | AMD        | FCH SD Flash Controller      | 4     | sdhci_pci  | B7AC3B44DF |
| 1106:401b | 1028:02f5 | VIA Tec... | VIA Secure Digital host c... | 4     | sdhci_pci  | 8EF532D4EC |
| 197b:2381 | 103c:2aa6 | JMicron... | Standard SD Host Controller  | 4     | sdhci_pci  | 3EE3ED2E83 |
| 197b:2381 | 1297:2020 | JMicron... | Standard SD Host Controller  | 4     | sdhci_pci  | E8007CF3BE |
| 8086:0f50 |           | Intel      | Atom Processor E3800 Seri... | 4     | sdhci_pci  | D4408F7B0E |
| 8086:a375 | 103c:843c | Intel      | 300 Series Chipset Family... | 4     | sdhci_pci  | C10F8FDED4 |
| 1022:7806 | 103c:2b60 | AMD        | FCH SD Flash Controller      | 3     | sdhci_pci  | 0330705A93 |
| 1022:7906 | 103c:8436 | AMD        | FCH SD Flash Controller      | 3     | sdhci_pci  | 8295CEC05D |
| 1217:8620 | 1217:0002 | O2 Micro   | BayHubTech/O2Micro Integr... | 3     | sdhci_pci  | 745C41CC7D |
| 197b:2381 | 1297:4012 | JMicron... | Standard SD Host Controller  | 3     | sdhci_pci  | 24598CF8F9 |
| 8086:5aca | 1458:1000 | Intel      | Celeron N3350/Pentium N42... | 3     | sdhci_pci  | 7741641346 |
| 104c:8034 | 103c:3085 | Texas I... | PCIxx21/PCIxx11 SD Host C... | 2     | sdhci_pci  | 32F7B77B77 |
| 1106:401b | 1106:401b | VIA Tec... | VIA Secure Digital host c... | 2     | sdhci_pci  | FF6AA83006 |
| 1180:0822 | 1509:4780 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 2     | sdhci_pci  | 4A92B26339 |
| 197b:2381 | 103c:2a97 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | EDEACD39C6 |
| 197b:2381 | 1297:3189 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | 0EFBD74715 |
| 197b:2381 | 1462:6720 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | C630018FEA |
| 197b:2381 | 1558:0390 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | FE920018C7 |
| 197b:2391 | 103c:2b00 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | AA243A819D |
| 8086:19db | 8086:7270 | Intel      | Atom Processor C3000 Seri... | 2     | sdhci_pci  | 50B6A72C0C |
| 8086:2295 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 2     | sdhci_pci  | EF051B442A |
| 8086:5ad0 | 1458:1000 | Intel      | Celeron N3350/Pentium N42... | 2     | sdhci_pci  | 7741641346 |
| 8086:811c | 8086:8119 | Intel      | US15W/US15X/US15L/UL11L S... | 2     | sdhci_pci  | 032A1A34DF |
| 8086:811d | 8086:8119 | Intel      | US15W/US15X/US15L/UL11L S... | 2     | sdhci_pci  | 032A1A34DF |
| 8086:9d2d | 1ae0:006c | Intel      | Sunrise Point-LP Secure D... | 2     | sdhci_pci  | A21EFE9A85 |
| 104c:803c | 152d:0754 | Texas I... | PCIxx12 SDA Standard Comp... | 1     | sdhci_pci  | 79905DEFFE |
| 10ec:5250 | 1558:7709 | Realtek... | RTS5250 PCI Express Card ... | 1     | sdhci_pci  | 500847AA07 |
| 1106:401b | 1028:0408 | VIA Tec... | VIA Secure Digital host c... | 1     | sdhci_pci  | B55E0BA8CB |
| 1180:0822 | 1033:8271 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 300E280E8C |
| 1180:0822 | 103c:30ec | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 9650848634 |
| 1180:0822 | 10cf:12fc | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 347EB6B747 |
| 1180:e822 |           | Ricoh      | MMC/SD Host Controller       | 1     | sdhci_pci  | C0FEDF21BB |
| 1180:e822 | 104d:9060 | Ricoh      | MMC/SD Host Controller       | 1     | sdhci_pci  | 90A75A8826 |
| 1217:7120 | 1025:0124 | O2 Micro   | Integrated MMC/SD Controller | 1     | sdhci_pci  | 1F2C670EC4 |
| 1217:7120 | 14ff:a003 | O2 Micro   | Integrated MMC/SD Controller | 1     | sdhci_pci  | 6647A9CB02 |
| 1217:7120 | 1631:0188 | O2 Micro   | Integrated MMC/SD Controller | 1     | sdhci_pci  | 7E9A381494 |
| 14e4:16bc | 1025:0742 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 1     | sdhci_pci  | 868EC85E4C |
| 197b:2381 | 1019:2238 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | 7E782321C8 |
| 197b:2381 | 1019:2689 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | 7CF090FB8F |
| 197b:2381 | 1025:0275 | JMicron... | Standard SD Host Controller  | 1     |            | 09734ADC68 |
| 197b:2381 | 1297:2000 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | A18117BE54 |
| 197b:2381 | 1297:2023 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | 8FCE6FC79B |
| 197b:2391 | 103c:2af2 | JMicron... | Standard SD Host Controller  | 1     |            | F94C9AF809 |
| 8086:0f16 | 8086:0f16 | Intel      | Atom Processor Z36xxx/Z37... | 1     | sdhci_pci  | 6AC9E1A935 |
| 8086:0f50 | 8086:7270 | Intel      | Atom Processor E3800 Seri... | 1     | sdhci_pci  | 6960F82AE6 |
| 8086:2294 | 1019:9bef | Intel      | Atom/Celeron/Pentium Proc... | 1     | sdhci_pci  | BBED831835 |
| 8086:2294 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 1     | sdhci_pci  | CA4B1C0036 |
| 8086:2294 | 8086:2294 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 2FD537312F |
| 8086:2294 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | sdhci_pci  | EF051B442A |
| 8086:2296 | 8086:2296 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 2FD537312F |
| 8086:2296 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | sdhci_pci  | 6ED2C82A03 |
| 8086:31cc | 1019:a4c6 | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | 11D8FCF22B |
| 8086:31cc | 1043:875e | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | 903B8C265E |
| 8086:5ad0 |           | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 150D692C9A |
| 8086:9cb5 | 8086:9cb5 | Intel      | Wildcat Point-LP Secure D... | 1     | sdhci_pci  | 3DB5F67CC9 |
| 8086:9d2b |           | Intel      | Skylake-U/Y SCC: eMMC        | 1     | sdhci_pci  | 9DE5E32B25 |
| 8086:9d2b | 8086:2065 | Intel      | Skylake-U/Y SCC: eMMC        | 1     | sdhci_pci  | B1EB5D5F20 |
| 8086:9d2d |           | Intel      | Sunrise Point-LP Secure D... | 1     | sdhci_pci  | 9DE5E32B25 |
| 8086:9d2d | 1025:1223 | Intel      | Sunrise Point-LP Secure D... | 1     | sdhci_pci  | C3CFF1EC7E |
| 8086:9d2d | 1b0a:01c6 | Intel      | Sunrise Point-LP Secure D... | 1     | sdhci_pci  | 23C5F53C73 |
| 8086:9d2d | 8086:2065 | Intel      | Sunrise Point-LP Secure D... | 1     | sdhci_pci  | B1EB5D5F20 |
| 8086:9d2d | 8086:9d2d | Intel      | Sunrise Point-LP Secure D... | 1     | sdhci_pci  | 4F9AEAAD47 |
| 8086:9dc4 | 8086:2092 | Intel      | 300 Series Chipset SD Hos... | 1     | sdhci_pci  | 4BA8CD9CA2 |
| 8086:9df5 | 8086:2092 | Intel      | BayHubTech Integrated SD ... | 1     | sdhci_pci  | 4BA8CD9CA2 |
| 8086:a375 | 1d92:0254 | Intel      | 300 Series Chipset Family... | 1     | sdhci_pci  | 2F03DC661B |
| 8086:a375 | 8086:7270 | Intel      | 300 Series Chipset Family... | 1     | sdhci_pci  | C0828E682A |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a324 | 1043:8694 | Intel      | Cannon Lake PCH SPI Contr... | 301   | intel_s... | 36EBF65D44 |
| 8086:a324 | 8086:7270 | Intel      | Cannon Lake PCH SPI Contr... | 268   | intel_s... | E8B8B03EBD |
| 8086:a324 | 1849:a324 | Intel      | Cannon Lake PCH SPI Contr... | 102   | intel_s... | 839B20476A |
| 8086:06a4 | 1043:8694 | Intel      | Comet Lake PCH SPI Contro... | 61    | intel_s... | BBA08D40AD |
| 8086:06e8 | 1043:8694 | Intel      | Comet Lake PCH Serial IO ... | 58    | intel_l... | BBA08D40AD |
| 8086:06e9 | 1043:8694 | Intel      | Comet Lake PCH Serial IO ... | 58    | intel_l... | BBA08D40AD |
| 8086:06a4 | 8086:7270 | Intel      | Comet Lake PCH SPI Contro... | 31    |            | 6BC1B9DCC9 |
| 8086:a324 | 1025:1238 | Intel      | Cannon Lake PCH SPI Contr... | 31    | intel_s... | 5C8AF3A6F6 |
| 8086:a324 | 1462:7b98 | Intel      | Cannon Lake PCH SPI Contr... | 31    | intel_s... | 995EF5ECD6 |
| 10de:1aed | 1458:3fc8 | Nvidia     | TU116 USB Type-C UCSI Con... | 24    | i2c_nvi... | A1959C22E0 |
| 10de:1ad9 | 1458:4001 | Nvidia     | TU104 USB Type-C UCSI Con... | 22    | i2c_nvi... | 06BB083E38 |
| 8086:a324 | 1462:7b17 | Intel      | Cannon Lake PCH SPI Contr... | 21    | intel_spi  | 8D22FDB15F |
| 10de:1aed | 1462:3792 | Nvidia     | TU116 USB Type-C UCSI Con... | 20    | i2c_nvi... | C6DC071925 |
| 8086:06a4 | 1462:7c75 | Intel      | Comet Lake PCH SPI Contro... | 19    |            | 654C105561 |
| 10de:1ad9 | 10de:139f | Nvidia     | TU104 USB Type-C UCSI Con... | 18    | i2c_nvi... | 379D2F0B1C |
| 10de:1aed | 1458:4013 | Nvidia     | TU116 USB Type-C UCSI Con... | 18    | i2c_nvi... | 43D63DAFF7 |
| 8086:a324 | 103c:843b | Intel      | Cannon Lake PCH SPI Contr... | 18    | intel_s... | 08F01868CF |
| 8086:a368 | 103c:843b | Intel      | Cannon Lake PCH Serial IO... | 18    | intel_l... | 08F01868CF |
| 8086:a369 | 103c:843b | Intel      | Cannon Lake PCH Serial IO... | 18    | intel_l... | 08F01868CF |
| 10de:1aed | 1462:c75a | Nvidia     | TU116 USB Type-C UCSI Con... | 17    | i2c_nvi... | 88DF6AA3A5 |
| 10de:1aed | 1462:3750 | Nvidia     | TU116 USB Type-C UCSI Con... | 16    | nvidia_gpu | 8C128CE323 |
| 1002:73a4 | 1002:0408 | AMD        | Navi 21 USB                  | 15    |            | 0FF290EF92 |
| 10de:1adb | 1458:37c2 | Nvidia     | TU106 USB Type-C UCSI Con... | 15    | i2c_nvi... | 928D2A495C |
| 10de:1aed | 10de:21c4 | Nvidia     | TU116 USB Type-C UCSI Con... | 15    | i2c_nvi... | A34826BA77 |
| 10de:1aed | 1462:375a | Nvidia     | TU116 USB Type-C UCSI Con... | 15    | i2c_nvi... | 33BB3C3B9A |
| 10de:1aed | 1462:8d95 | Nvidia     | TU116 USB Type-C UCSI Con... | 15    | i2c_nvi... | 123B35C040 |
| 8086:a324 | 1462:7b22 | Intel      | Cannon Lake PCH SPI Contr... | 15    | intel_s... | 3BCEB2D915 |
| 10de:1ad9 | 3842:2068 | Nvidia     | TU104 USB Type-C UCSI Con... | 14    | i2c_nvi... | 86CEE5AEF6 |
| 10de:1adb | 1458:3ff1 | Nvidia     | TU106 USB Type-C UCSI Con... | 14    | i2c_nvi... | 43BC2EF593 |
| 10de:1aed | 1458:3fbe | Nvidia     | TU116 USB Type-C UCSI Con... | 14    | i2c_nvi... | 17578CD92F |
| 10de:1aed | 1462:3850 | Nvidia     | TU116 USB Type-C UCSI Con... | 14    | i2c_nvi... | 0ED78505E8 |
| 8086:a324 | 1028:085c | Intel      | Cannon Lake PCH SPI Contr... | 14    | intel_s... | 48EAE4D9FD |
| 8086:43a4 | 1043:8694 | Intel      | Tiger Lake-H SPI Controller  | 13    |            | 3B8DDCA28E |
| 8086:43e8 | 1043:8694 | Intel      | Tiger Lake-H Serial IO I2... | 13    | intel_l... | 3B8DDCA28E |
| 8086:a324 | 1462:7b24 | Intel      | Cannon Lake PCH SPI Contr... | 13    |            | 62C7E01FA6 |
| 10de:1ad7 | 1043:866a | Nvidia     | TU102 USB Type-C UCSI Con... | 12    | i2c_nvi... | C2EDF69881 |
| 10de:1ad9 | 1458:4008 | Nvidia     | TU104 USB Type-C UCSI Con... | 12    | i2c_nvi... | AEA7394E24 |
| 10de:1adb | 1462:3734 | Nvidia     | TU106 USB Type-C UCSI Con... | 12    | nvidia_gpu | 3D0DA576B8 |
| 10de:1adb | 1462:3755 | Nvidia     | TU106 USB Type-C UCSI Con... | 12    | i2c_nvi... | B3AF421AE5 |
| 10de:1aed | 10de:1324 | Nvidia     | TU116 USB Type-C UCSI Con... | 12    | i2c_nvi... | 833DA5EA1D |
| 10de:1aed | 1458:401a | Nvidia     | TU116 USB Type-C UCSI Con... | 12    | i2c_nvi... | B5701B4CF9 |
| 8086:06a4 | 1849:06a4 | Intel      | Comet Lake PCH SPI Contro... | 12    | intel_s... | D1D4F84E0A |
| 8086:5ac8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 12    | pwm_lpss   | 867223F2CF |
| 8086:a324 | 1019:a4a3 | Intel      | Cannon Lake PCH SPI Contr... | 12    | intel_s... | 704CBD473C |
| 8086:a324 | 1462:7b51 | Intel      | Cannon Lake PCH SPI Contr... | 12    |            | 2EEBD180F8 |
| 10de:1ad9 | 1462:c729 | Nvidia     | TU104 USB Type-C UCSI Con... | 11    | i2c_nvi... | 76D43984B4 |
| 10de:1adb | 1458:3fc1 | Nvidia     | TU106 USB Type-C UCSI Con... | 11    | i2c_nvi... | 788E348569 |
| 10de:1aed | 10de:139d | Nvidia     | TU116 USB Type-C UCSI Con... | 11    | nvidia_gpu | F0606E05AC |
| 10de:1aed | 1458:4014 | Nvidia     | TU116 USB Type-C UCSI Con... | 11    | i2c_nvi... | 8AFD041673 |
| 8086:9da4 | 8086:7270 | Intel      | Cannon Point-LP SPI Contr... | 11    |            | D1CA5138F2 |
| 8086:9dc5 | 8086:7270 | Intel      | Cannon Point-LP Serial IO... | 11    | intel_l... | D1CA5138F2 |
| 8086:9de8 | 8086:7270 | Intel      | Cannon Point-LP Serial IO... | 11    | intel_l... | D1CA5138F2 |
| 8086:a324 | 17aa:36eb | Intel      | Cannon Lake PCH SPI Contr... | 11    | intel_s... | 2C6F4DE8B9 |
| 10de:1ad7 | 10de:12a3 | Nvidia     | TU102 USB Type-C UCSI Con... | 10    | i2c_nvi... | BEE5C78B3B |
| 10de:1ad9 | 1458:3fc1 | Nvidia     | TU104 USB Type-C UCSI Con... | 10    | i2c_nvi... | 993800D632 |
| 10de:1aed | 10de:13d3 | Nvidia     | TU116 USB Type-C UCSI Con... | 10    | i2c_nvi... | D2B33F007E |
| 8086:9de9 | 8086:7270 | Intel      | Cannon Point-LP Serial IO... | 10    | intel_l... | 733B8D0260 |
| 8086:a324 | 103c:843f | Intel      | Cannon Lake PCH SPI Contr... | 10    | intel_s... | DFA11821CD |
| 8086:a324 | 1734:1246 | Intel      | Cannon Lake PCH SPI Contr... | 10    |            | FC1ED40727 |
| 8086:a368 | 103c:843f | Intel      | Cannon Lake PCH Serial IO... | 10    | intel_lpss | DFA11821CD |
| 8086:a369 | 103c:843f | Intel      | Cannon Lake PCH Serial IO... | 10    | intel_lpss | DFA11821CD |
| 10de:1adb | 1043:8670 | Nvidia     | TU106 USB Type-C UCSI Con... | 9     | i2c_nvi... | E7262E0201 |
| 10de:1adb | 10de:1f08 | Nvidia     | TU106 USB Type-C UCSI Con... | 9     | i2c_nvi... | 2E96C9013B |
| 10de:1aed | 1043:874b | Nvidia     | TU116 USB Type-C UCSI Con... | 9     | i2c_nvi... | 2696477C0C |
| 10de:1aed | 1458:3fc3 | Nvidia     | TU116 USB Type-C UCSI Con... | 9     | nvidia_gpu | 995EF5ECD6 |
| 10de:1aed | 1462:c758 | Nvidia     | TU116 USB Type-C UCSI Con... | 9     | i2c_nvi... | 92187479C3 |
| 8086:43e9 | 1043:8694 | Intel      | 500 Series Chipset Family... | 9     | intel_l... | 3B8DDCA28E |
| 8086:a324 | 1025:123c | Intel      | Cannon Lake PCH SPI Contr... | 9     | intel_spi  | E7DDF93F9F |
| 8086:a324 | 1028:0930 | Intel      | Cannon Lake PCH SPI Contr... | 9     | intel_s... | 4F04EEA322 |
| 8086:a324 | 1462:7b33 | Intel      | Cannon Lake PCH SPI Contr... | 9     | intel_s... | BE3B72E745 |
| 8086:a324 | 17aa:3140 | Intel      | Cannon Lake PCH SPI Contr... | 9     | intel_s... | 452F706571 |
| 10de:1ad7 | 10de:12a4 | Nvidia     | TU102 USB Type-C UCSI Con... | 8     | i2c_nvi... | 55CDAF18A6 |
| 10de:1ad9 | 1462:372d | Nvidia     | TU104 USB Type-C UCSI Con... | 8     | i2c_nvi... | 531975EDD5 |
| 10de:1adb | 1043:8698 | Nvidia     | TU106 USB Type-C UCSI Con... | 8     | i2c_nvi... | 88B1B582B5 |
| 10de:1adb | 3842:2173 | Nvidia     | TU106 USB Type-C UCSI Con... | 8     | i2c_nvi... | 5A17C0B238 |
| 10de:1aed | 10de:2182 | Nvidia     | TU116 USB Type-C UCSI Con... | 8     | i2c_nvi... | D0FB912292 |
| 10de:1aed | 1458:401b | Nvidia     | TU116 USB Type-C UCSI Con... | 8     | i2c_nvi... | F4C6BD4B6D |
| 10de:1aed | 1458:4028 | Nvidia     | TU116 USB Type-C UCSI Con... | 8     | i2c_nvi... | 3A544ADCC9 |
| 10de:1aed | 3842:1068 | Nvidia     | TU116 USB Type-C UCSI Con... | 8     | i2c_nvi... | A6097E7501 |
| 8086:06a4 | 1462:7c79 | Intel      | Comet Lake PCH SPI Contro... | 8     | intel_spi  | D202285C25 |
| 8086:a324 | 1028:0871 | Intel      | Cannon Lake PCH SPI Contr... | 8     | intel_s... | E5D4E252C9 |
| 8086:a324 | 1028:092e | Intel      | Cannon Lake PCH SPI Contr... | 8     | intel_s... | FF5BB2EE2A |
| 8086:a324 | 103c:843c | Intel      | Cannon Lake PCH SPI Contr... | 8     | intel_spi  | C10F8FDED4 |
| 8086:a368 | 1028:0871 | Intel      | Cannon Lake PCH Serial IO... | 8     | intel_l... | E5D4E252C9 |
| 8086:a368 | 1028:092e | Intel      | Cannon Lake PCH Serial IO... | 8     | intel_l... | FF5BB2EE2A |
| 8086:a368 | 103c:843c | Intel      | Cannon Lake PCH Serial IO... | 8     | intel_l... | C10F8FDED4 |
| 8086:a369 | 103c:843c | Intel      | Cannon Lake PCH Serial IO... | 8     | intel_l... | C10F8FDED4 |
| 10de:1ad7 | 1462:3715 | Nvidia     | TU102 USB Type-C UCSI Con... | 7     | i2c_nvi... | F0A9A9B376 |
| 10de:1ad9 | 1043:8708 | Nvidia     | TU104 USB Type-C UCSI Con... | 7     | i2c_nvi... | 75557F3294 |
| 10de:1ad9 | 1043:8728 | Nvidia     | TU104 USB Type-C UCSI Con... | 7     | i2c_nvi... | C55A1DD601 |
| 10de:1ad9 | 10de:1e84 | Nvidia     | TU104 USB Type-C UCSI Con... | 7     | i2c_nvi... | C46179B0B2 |
| 10de:1ad9 | 1462:3722 | Nvidia     | TU104 USB Type-C UCSI Con... | 7     | nvidia_gpu | 5C6A5253C8 |
| 10de:1adb | 10de:12fd | Nvidia     | TU106 USB Type-C UCSI Con... | 7     | i2c_nvi... | 5F39051050 |
| 10de:1adb | 1458:3fda | Nvidia     | TU106 USB Type-C UCSI Con... | 7     | i2c_nvi... | F0D57310C5 |
| 10de:1adb | 1458:3fed | Nvidia     | TU106 USB Type-C UCSI Con... | 7     | i2c_nvi... | 0D2EBE98DA |
| 10de:1adb | 1462:3732 | Nvidia     | TU106 USB Type-C UCSI Con... | 7     | nvidia_gpu | C9EC042C96 |
| 10de:1adb | 1462:c752 | Nvidia     | TU106 USB Type-C UCSI Con... | 7     | i2c_nvi... | 8F0E11C580 |
| 10de:1adb | 1462:c757 | Nvidia     | TU106 USB Type-C UCSI Con... | 7     | i2c_nvi... | 7B40989BC7 |
| 10de:1aed | 1043:872a | Nvidia     | TU116 USB Type-C UCSI Con... | 7     | i2c_nvi... | 9BC7AB87D1 |
| 10de:1aed | 1043:873a | Nvidia     | TU116 USB Type-C UCSI Con... | 7     | nvidia_gpu | C339545A11 |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8c3d | 1458:1c3a | Intel      | 8 Series/C220 Series Chip... | 125   | serial     | D8CF951CC3 |
| 8086:29b7 | 1028:0211 | Intel      | 82Q35 Express Serial KT C... | 91    | serial     | 962E0B75E4 |
| 8086:1e3d | 103c:3397 | Intel      | 7 Series/C210 Series Chip... | 90    | serial     | 9C1343DD9B |
| 8086:8c3d | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 89    | serial     | 0FC3ABDB1C |
| 8086:2e17 | 1028:0420 | Intel      | 4 Series Chipset Serial K... | 84    | serial     | 340184FB36 |
| 8086:1e3d | 1028:0577 | Intel      | 7 Series/C210 Series Chip... | 83    | serial     | 3649E87174 |
| 8086:2e17 | 1028:027f | Intel      | 4 Series Chipset Serial K... | 79    | serial     | 8F0C6ED152 |
| 8086:1e3d | 103c:339a | Intel      | 7 Series/C210 Series Chip... | 72    | serial     | BA7CCF28B7 |
| 8086:1c3d | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 69    | serial     | 3F6DDBD81D |
| 8086:1c3d | 1028:047e | Intel      | 6 Series/C200 Series Chip... | 65    | serial     | 959E3DDE54 |
| 8086:8c3d | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 64    | serial     | D8309CFECF |
| 8086:1c3d | 103c:1495 | Intel      | 6 Series/C200 Series Chip... | 61    | serial     | 660C4FF2ED |
| 8086:2e17 | 103c:3048 | Intel      | 4 Series Chipset Serial K... | 59    | serial     | 39204D22AE |
| 8086:2e17 | 1734:114c | Intel      | 4 Series Chipset Serial K... | 56    | serial     | 8159354A14 |
| 8086:8c3d | 103c:18e7 | Intel      | 8 Series/C220 Series Chip... | 56    | serial     | 9844F6635C |
| 8086:1c3d | 103c:1497 | Intel      | 6 Series/C200 Series Chip... | 54    | serial     | 7FA5AD3E42 |
| 8086:3b67 | 8086:0036 | Intel      | 5 Series/3400 Series Chip... | 48    | serial     | 15FF525EFC |
| 8086:29b7 | 103c:2818 | Intel      | 82Q35 Express Serial KT C... | 46    | serial     | C0E9143E13 |
| 8086:2e17 | 17aa:3048 | Intel      | 4 Series Chipset Serial K... | 39    | serial     | 7E76E404EC |
| 8086:1e3d | 1028:052c | Intel      | 7 Series/C210 Series Chip... | 36    | serial     | DD8DC2D85A |
| 8086:2e17 | 103c:3646 | Intel      | 4 Series Chipset Serial K... | 35    | serial     | 833B887480 |
| 8086:1c3d | 17aa:3070 | Intel      | 6 Series/C200 Series Chip... | 34    | serial     | 6983745C31 |
| 8086:1e3d | 17aa:3083 | Intel      | 7 Series/C210 Series Chip... | 33    | serial     | C0B8E99E35 |
| 8086:2e17 | 103c:3034 | Intel      | 4 Series Chipset Serial K... | 33    | serial     | D69CD77C4D |
| 8086:1d3d | 103c:1589 | Intel      | C600/X79 series chipset K... | 32    | serial     | A4B0EBBEE2 |
| 8086:8c3d | 17aa:3097 | Intel      | 8 Series/C220 Series Chip... | 32    | serial     | 0C78C3EF80 |
| 8086:1c3d | 103c:1494 | Intel      | 6 Series/C200 Series Chip... | 28    | serial     | 646E6E27E3 |
| 8086:1e3d | 103c:3396 | Intel      | 7 Series/C210 Series Chip... | 27    | serial     | 25FFFCB5C5 |
| 8086:2e17 | 103c:3035 | Intel      | 4 Series Chipset Serial K... | 27    | serial     | EA009F77D1 |
| 8086:3b67 | 103c:304a | Intel      | 5 Series/3400 Series Chip... | 26    | serial     | A6862C2A01 |
| 8086:8c3d | 17aa:30a3 | Intel      | 8 Series/C220 Series Chip... | 26    | serial     | F5A0BFB5FD |
| 8086:2e17 | 1028:0276 | Intel      | 4 Series Chipset Serial K... | 25    | serial     | 8B417F82C5 |
| 9710:9865 | a000:1000 | MosChip... | PCI 9865 Multi-I/O Contro... | 24    | parport_pc | 1155908299 |
| 8086:1e3d | 17aa:3084 | Intel      | 7 Series/C210 Series Chip... | 22    | serial     | AFB7518616 |
| 8086:a13d | 1734:121d | Intel      | 100 Series/C230 Series Ch... | 22    | serial     | 4E988AF2DF |
| 8086:8c3d | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 21    | serial     | 99AE75539D |
| 8086:3b67 | 103c:304b | Intel      | 5 Series/3400 Series Chip... | 20    | serial     | DC42BD8E41 |
| 8086:3b67 | 8086:3b67 | Intel      | 5 Series/3400 Series Chip... | 20    | serial     | C4A24B7D58 |
| 8086:a13d | 1028:06b9 | Intel      | 100 Series/C230 Series Ch... | 20    | serial     | D26EA79B14 |
| 8086:1d3d | 103c:158a | Intel      | C600/X79 series chipset K... | 19    | serial     | D70166F107 |
| 8086:2e17 | 17aa:3047 | Intel      | 4 Series Chipset Serial K... | 19    | serial     | 0D516E5C8A |
| 8086:8c3d | 1028:05a5 | Intel      | 8 Series/C220 Series Chip... | 19    | serial     | 6B9DBEBE2F |
| 8086:8c3d | 103c:1905 | Intel      | 8 Series/C220 Series Chip... | 19    | serial     | FD0F9E5AB1 |
| 8086:1c3d | 8086:2008 | Intel      | 6 Series/C200 Series Chip... | 18    | serial     | 8FD2974998 |
| 8086:3b67 | 1028:02da | Intel      | 5 Series/3400 Series Chip... | 18    | serial     | 1FE360B027 |
| 8086:1c3d | 17aa:3077 | Intel      | 6 Series/C200 Series Chip... | 17    | serial     | 1B01FF9935 |
| 8086:8d3d | 103c:212b | Intel      | C610/X99 series chipset K... | 17    | serial     | 84296E0108 |
| 8086:a13d | 103c:805d | Intel      | 100 Series/C230 Series Ch... | 17    | serial     | E6583FB63A |
| 8086:1d3d | 103c:158b | Intel      | C600/X79 series chipset K... | 16    | serial     | E7D78D4E6C |
| 8086:1e3d | 103c:3398 | Intel      | 7 Series/C210 Series Chip... | 16    | serial     | ADC9970D79 |
| 8086:2e17 | 103c:3648 | Intel      | 4 Series Chipset Serial K... | 16    | serial     | 62E9EBE765 |
| 9710:9912 | a000:1000 | MosChip... | PCIe 9912 Multi-I/O Contr... | 16    | serial     | D6A6EF19FD |
| 10ec:816a | 10ec:8168 | Realtek... | RTL8111xP UART #1            | 15    | serial     | 6E60025AC5 |
| 8086:1c3d | 103c:1496 | Intel      | 6 Series/C200 Series Chip... | 15    | serial     | EF4E0697D7 |
| 8086:29b7 | 1043:8295 | Intel      | 82Q35 Express Serial KT C... | 15    | serial     | D37FED8D0F |
| 8086:29b7 | 17aa:3038 | Intel      | 82Q35 Express Serial KT C... | 15    | serial     | 095CC14306 |
| 8086:2e17 | 8086:1003 | Intel      | 4 Series Chipset Serial K... | 15    | serial     | 95642C55FC |
| 8086:8c3d | 17aa:30a5 | Intel      | 8 Series/C220 Series Chip... | 15    | serial     | 5E12F8D78F |
| 8086:29b7 | 103c:2819 | Intel      | 82Q35 Express Serial KT C... | 14    | serial     | 888B5F2F1E |
| 8086:8c3d | 103c:1825 | Intel      | 8 Series/C220 Series Chip... | 14    | serial     | 2EFDB3364C |
| 1c00:3250 | 1c00:3250 |            | WCH PCI Express              | 13    | parport... | 02F80C53EA |
| 8086:1e3d | 1458:1c3a | Intel      | 7 Series/C210 Series Chip... | 13    | serial     | CD5789F91B |
| 8086:1e3d | 17aa:3086 | Intel      | 7 Series/C210 Series Chip... | 13    | serial     | 6928EDC4C3 |
| 8086:29b7 | 1734:10fc | Intel      | 82Q35 Express Serial KT C... | 13    | serial     | 8DE7A1B6F8 |
| 8086:2e17 | 103c:3647 | Intel      | 4 Series Chipset Serial K... | 13    | serial     | BD39210291 |
| 8086:2e17 | 17aa:3049 | Intel      | 4 Series Chipset Serial K... | 13    | serial     | 239C4BF44D |
| 8086:3b67 | 17aa:3059 | Intel      | 5 Series/3400 Series Chip... | 13    | serial     | 666E4F970E |
| 8086:8c3d | 103c:18e5 | Intel      | 8 Series/C220 Series Chip... | 13    | serial     | 81676A0984 |
| 8086:8c3d | 17aa:309f | Intel      | 8 Series/C220 Series Chip... | 13    | serial     | 887DBC1614 |
| 8086:8c3d | 103c:18e4 | Intel      | 8 Series/C220 Series Chip... | 12    | serial     | D97F86A6F8 |
| 8086:a13d | 17aa:30be | Intel      | 100 Series/C230 Series Ch... | 12    | serial     | 0F8266989E |
| 9710:9835 | 1000:0002 | MosChip... | PCI 9835 Multi-I/O Contro... | 12    | parport... | 51C9F3B32F |
| 8086:2e17 | 103c:3036 | Intel      | 4 Series Chipset Serial K... | 11    | serial     | BBDEFAB03D |
| 8086:a13d | 1028:07c5 | Intel      | 100 Series/C230 Series Ch... | 11    | serial     | A897526E05 |
| 9710:9922 | a000:1000 | MosChip... | MCS9922 PCIe Multi-I/O Co... | 11    | serial     | 0CC10A7F8B |
| 10ec:816a | 1458:e000 | Realtek... | RTL8111xP UART #1            | 10    | serial     | 4B79994619 |
| 10ec:816b | 1458:e000 | Realtek... | RTL8111xP UART #2            | 10    | serial     | 4B79994619 |
| 8086:1e3d | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 10    | serial     | DC49777CE8 |
| 8086:1e3d | 8086:2035 | Intel      | 7 Series/C210 Series Chip... | 10    | serial     | B1A5DA541F |
| 8086:a13d | 103c:8055 | Intel      | 100 Series/C230 Series Ch... | 10    | serial     | D6291ACC4A |
| 8086:a2bd | 1028:07a1 | Intel      | 200 Series Chipset Family... | 10    | serial     | B9807FA858 |
| 10ec:816a | 17aa:3089 | Realtek... | RTL8111xP UART #1            | 9     | serial     | 7D4224DF3F |
| 10ec:816b | 17aa:3089 | Realtek... | RTL8111xP UART #2            | 9     | serial     | 7D4224DF3F |
| 1c00:2273 | 1c00:2273 |            | WCH PCI                      | 9     | serial     | 8CDAFAC5A3 |
| 4348:3253 | 4348:3253 | WCH.CN     | CH352 PCI Dual Serial Por... | 9     | serial     | D6A6EF19FD |
| 8086:1c3d | 17aa:3078 | Intel      | 6 Series/C200 Series Chip... | 8     | serial     | D27988D8DD |
| 8086:1e3d | 103c:1790 | Intel      | 7 Series/C210 Series Chip... | 8     | serial     | 75557F3294 |
| 8086:1e3d | 103c:1791 | Intel      | 7 Series/C210 Series Chip... | 8     | serial     | AD7AD34A9D |
| 8086:2997 | 103c:2801 | Intel      | 82Q963/Q965 KT Controller    | 8     | serial     | 0C92DC3AB0 |
| 8086:3b67 | 1734:1168 | Intel      | 5 Series/3400 Series Chip... | 8     | serial     | B1A6F49396 |
| 8086:8d3d | 103c:2129 | Intel      | C610/X99 series chipset K... | 8     | serial     | 3991895525 |
| 10ec:816a | 1734:1178 | Realtek... | RTL8111xP UART #1            | 7     | serial     | CD168F769A |
| 10ec:816b | 1734:1178 | Realtek... | RTL8111xP UART #2            | 7     | serial     | CD168F769A |
| 8086:1c3d | 1025:0493 | Intel      | 6 Series/C200 Series Chip... | 7     | serial     | F9C8854F20 |
| 8086:1c3d | 1028:0498 | Intel      | 6 Series/C200 Series Chip... | 7     | serial     | 304541CE36 |
| 8086:1e3d | 103c:3399 | Intel      | 7 Series/C210 Series Chip... | 7     | serial     | 4085344B20 |
| 8086:29b7 | 17aa:3037 | Intel      | 82Q35 Express Serial KT C... | 7     | serial     | 634BD29E96 |
| 8086:29b7 | 8086:4f4a | Intel      | 82Q35 Express Serial KT C... | 7     | serial     | 51C42A0F25 |
| 8086:2e17 | 1458:2e17 | Intel      | 4 Series Chipset Serial K... | 7     | serial     | 2C39A254EE |
| 8086:3b67 | 8086:0037 | Intel      | 5 Series/3400 Series Chip... | 7     | serial     | 2EBFC03CE7 |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a379 | 1458:8888 | Intel      | Cannon Lake PCH Thermal C... | 257   | intel_p... | E8B8B03EBD |
| 8086:a131 | 1849:a131 | Intel      | 100 Series/C230 Series Ch... | 173   | intel_p... | 3A2A9BD626 |
| 8086:a2b1 | 1849:a2b1 | Intel      | 200 Series PCH Thermal Su... | 146   |            | A8F84AEA94 |
| 8086:a131 | 1458:8888 | Intel      | 100 Series/C230 Series Ch... | 102   | intel_p... | 4DA44461B8 |
| 8086:a379 | 1849:a379 | Intel      | Cannon Lake PCH Thermal C... | 102   | intel_p... | 839B20476A |
| 8086:a131 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 64    | intel_p... | C007D839E7 |
| 8086:8c24 | 1734:11ea | Intel      | 8 Series Chipset Family T... | 55    | intel_p... | F2BC4B7196 |
| 8086:a3b1 | 8086:7270 | Intel      | Comet Lake PCH-V Thermal ... | 51    |            | 9229EDCD91 |
| 8086:a131 | 1734:121d | Intel      | 100 Series/C230 Series Ch... | 48    | intel_p... | 4E988AF2DF |
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 47    | process... | DF3FFA30C9 |
| 8086:1e24 | 1734:11d6 | Intel      | 7 Series/C210 Series Chip... | 41    |            | 1F992DE6EB |
| 8086:a131 | 1462:7a15 | Intel      | 100 Series/C230 Series Ch... | 41    | intel_p... | B1186D53E5 |
| 8086:a131 | 1462:7971 | Intel      | 100 Series/C230 Series Ch... | 39    | intel_p... | 2289424CAC |
| 8086:a2b1 | 1043:873c | Intel      | 200 Series PCH Thermal Su... | 37    |            | D5CDC97C3B |
| 8086:9d31 | 8086:7270 | Intel      | Sunrise Point-LP Thermal ... | 35    | intel_p... | 2C887C5D3F |
| 8086:8c24 | 1025:0750 | Intel      | 8 Series Chipset Family T... | 32    | intel_p... | DB910234A6 |
| 8086:a379 | 1025:1238 | Intel      | Cannon Lake PCH Thermal C... | 31    | intel_p... | 5C8AF3A6F6 |
| 8086:a379 | 1462:7b98 | Intel      | Cannon Lake PCH Thermal C... | 31    | intel_p... | 995EF5ECD6 |
| 8086:a131 | 1028:06b9 | Intel      | 100 Series/C230 Series Ch... | 29    | intel_p... | 8989DF3C9D |
| 8086:06f9 | 1458:8888 | Intel      | Comet Lake PCH Thermal Co... | 28    | intel_p... | 6BC1B9DCC9 |
| 8086:31b4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 28    | intel_lpss | F1C998FD68 |
| 8086:a2b1 | 1462:7a70 | Intel      | 200 Series PCH Thermal Su... | 28    |            | FB2EEF67F2 |
| 8086:318c | 1849:318c | Intel      | Celeron/Pentium Silver Pr... | 27    | process... | 5FFE86E682 |
| 8086:31b6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 26    | intel_lpss | F1C998FD68 |
| 8086:31b8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 26    | intel_lpss | F1C998FD68 |
| 8086:318c | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 25    | process... | B4F38B4941 |
| 8086:a2a7 | 103c:82f2 | Intel      | 200 Series/Z370 Chipset F... | 24    | intel_l... | 4EFC31781E |
| 8086:a2e0 | 103c:82f2 | Intel      | 200 Series PCH Serial IO ... | 24    | intel_l... | 4EFC31781E |
| 8086:a2e1 | 103c:82f2 | Intel      | 200 Series PCH Serial IO ... | 24    | intel_l... | 4EFC31781E |
| 8086:9d27 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 23    | intel_l... | B1128F0534 |
| 8086:31ba | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 22    | intel_lpss | F1C998FD68 |
| 8086:a160 | 1462:7971 | Intel      | 100 Series/C230 Series Ch... | 22    | intel_l... | 6C40498976 |
| 8086:a161 | 1462:7971 | Intel      | 100 Series/C230 Series Ch... | 22    | intel_l... | 6C40498976 |
| 8086:a131 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 21    | intel_p... | 047EAD1D70 |
| 8086:a379 | 1462:7b17 | Intel      | Cannon Lake PCH Thermal C... | 21    | intel_p... | 8D22FDB15F |
| 8086:31bc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | intel_l... | 3E408E9EAD |
| 8086:31be | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | intel_l... | 3E408E9EAD |
| 8086:31c0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | intel_l... | 3E408E9EAD |
| 8086:31ee | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | intel_l... | 3E408E9EAD |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 20    | intel_l... | 704DB88794 |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 20    | intel_l... | 704DB88794 |
| 8086:a160 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 20    | intel_l... | C007D839E7 |
| 8086:a161 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 20    | intel_l... | C007D839E7 |
| 8086:a2b1 | 1462:7a72 | Intel      | 200 Series PCH Thermal Su... | 20    |            | 08CC036466 |
| 8086:06f9 | 1462:7c75 | Intel      | Comet Lake PCH Thermal Co... | 19    | intel_p... | 654C105561 |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 19    | intel_l... | 704DB88794 |
| 8086:a131 | 1028:06bb | Intel      | 100 Series/C230 Series Ch... | 19    | intel_p... | 1A7FD4C345 |
| 8086:a2b1 | 1028:07a3 | Intel      | 200 Series PCH Thermal Su... | 19    |            | F3E4767726 |
| 8086:a3b1 | 1849:a3b1 | Intel      | Comet Lake PCH-V Thermal ... | 19    |            | F7FD155DD3 |
| 8086:a131 | 103c:805d | Intel      | 100 Series/C230 Series Ch... | 18    | intel_p... | E6583FB63A |
| 8086:a131 | 1462:7978 | Intel      | 100 Series/C230 Series Ch... | 18    | intel_p... | 8B15965A17 |
| 8086:a379 | 103c:843b | Intel      | Cannon Lake PCH Thermal C... | 18    | intel_p... | 08F01868CF |
| 8086:a127 | 1462:7971 | Intel      | 100 Series/C230 Series Ch... | 17    | intel_l... | 6C40498976 |
| 8086:a131 | 1462:7994 | Intel      | 100 Series/C230 Series Ch... | 17    | intel_p... | A2B72216EF |
| 8086:a2a7 | 1028:0859 | Intel      | 200 Series/Z370 Chipset F... | 17    | intel_l... | 0A24BF8DCA |
| 8086:a2b1 | 1028:07a1 | Intel      | 200 Series PCH Thermal Su... | 17    |            | B9807FA858 |
| 8086:a2e0 | 1028:07a1 | Intel      | 200 Series PCH Serial IO ... | 17    | intel_l... | B9807FA858 |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 16    | intel_l... | 867223F2CF |
| 8086:a127 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 16    | intel_l... | C007D839E7 |
| 8086:a131 | 1025:108e | Intel      | 100 Series/C230 Series Ch... | 16    | intel_p... | C7C28C4F55 |
| 8086:a131 | 1462:7982 | Intel      | 100 Series/C230 Series Ch... | 16    | intel_p... | 4130D9A755 |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 15    | intel_l... | 867223F2CF |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 15    | intel_l... | 867223F2CF |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 15    | intel_l... | 867223F2CF |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 15    | intel_l... | 867223F2CF |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 15    | intel_l... | 867223F2CF |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 15    | intel_l... | 867223F2CF |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 15    | intel_l... | 867223F2CF |
| 8086:a131 | 1462:7972 | Intel      | 100 Series/C230 Series Ch... | 15    | intel_p... | 8502EA76C6 |
| 8086:a131 | 1462:7977 | Intel      | 100 Series/C230 Series Ch... | 15    | intel_p... | 7493D31ACB |
| 8086:a2b1 | 1028:0738 | Intel      | 200 Series PCH Thermal Su... | 15    |            | 862B2D2013 |
| 8086:a2b1 | 1462:7a74 | Intel      | 200 Series PCH Thermal Su... | 15    |            | C90BB6ECA1 |
| 8086:a2b1 | 1462:7b48 | Intel      | 200 Series PCH Thermal Su... | 15    |            | 470BE454F6 |
| 8086:a379 | 1462:7b22 | Intel      | Cannon Lake PCH Thermal C... | 15    | intel_p... | 3BCEB2D915 |
| 8086:2932 | 1043:8277 | Intel      | 82801I (ICH9 Family) Ther... | 14    |            | D37FED8D0F |
| 8086:31ac | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 14    | intel_lpss | 9AA4FA465F |
| 8086:31ae | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 14    | intel_lpss | 9AA4FA465F |
| 8086:31b0 | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 14    | intel_lpss | 9AA4FA465F |
| 8086:31b2 | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 14    | intel_lpss | 9AA4FA465F |
| 8086:31b4 | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 14    | intel_lpss | 9AA4FA465F |
| 8086:31b6 | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 14    | intel_lpss | 9AA4FA465F |
| 8086:31b8 | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 14    | intel_lpss | 9AA4FA465F |
| 8086:31ba | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 14    | intel_lpss | 9AA4FA465F |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 14    | intel_l... | 867223F2CF |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 14    | intel_l... | 867223F2CF |
| 8086:a2b1 | 1462:7a71 | Intel      | 200 Series PCH Thermal Su... | 14    |            | 42139049F7 |
| 8086:a379 | 1028:085c | Intel      | Cannon Lake PCH Thermal C... | 14    | intel_p... | 48EAE4D9FD |
| 8086:a379 | 1462:7b24 | Intel      | Cannon Lake PCH Thermal C... | 13    | intel_p... | 62C7E01FA6 |
| 8086:06f9 | 1849:06f9 | Intel      | Comet Lake PCH Thermal Co... | 12    | intel_p... | D1D4F84E0A |
| 8086:31c2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 12    | intel_l... | 59623AA777 |
| 8086:3b32 | 8086:3b32 | Intel      | 5 Series/3400 Series Chip... | 12    | intel_ips  | A890F1FE70 |
| 8086:9d60 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 12    | intel_l... | B1128F0534 |
| 8086:9d61 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 12    | intel_l... | B1128F0534 |
| 8086:a127 | 1462:7982 | Intel      | 100 Series/C230 Series Ch... | 12    | intel_l... | 5E5FC38226 |
| 8086:a131 | 1028:06b7 | Intel      | 100 Series/C230 Series Ch... | 12    | intel_p... | E2E2E6F179 |
| 8086:a131 | 1028:07c5 | Intel      | 100 Series/C230 Series Ch... | 12    | intel_p... | A897526E05 |
| 8086:a160 | 1462:7982 | Intel      | 100 Series/C230 Series Ch... | 12    | intel_l... | 5E5FC38226 |
| 8086:a161 | 1462:7982 | Intel      | 100 Series/C230 Series Ch... | 12    | intel_l... | 5E5FC38226 |
| 8086:a2b1 | 1462:7b45 | Intel      | 200 Series PCH Thermal Su... | 12    |            | 19C2138C14 |
| 8086:a379 | 1019:a4a3 | Intel      | Cannon Lake PCH Thermal C... | 12    | intel_p... | 704CBD473C |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:790b | 1458:5001 | AMD        | FCH SMBus Controller         | 1348  | i2c_piix4  | F544511E0A |
| 1002:4385 | 1002:4385 | AMD        | SBx00 SMBus Controller       | 1115  | i2c_pii... | 77FCB9CF4A |
| 8086:1c22 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1015  | i2c_i801   | EA164260EB |
| 8086:8c22 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 790   | i2c_i801   | 9A23DF55D8 |
| 1002:4385 | 1043:8389 | AMD        | SBx00 SMBus Controller       | 786   | i2c_pii... | 67B53F9BDB |
| 1002:4385 | 1458:4385 | AMD        | SBx00 SMBus Controller       | 742   | i2c_pii... | 765CD8D9A0 |
| 8086:27da | 1458:5001 | Intel      | NM10/ICH7 Family SMBus Co... | 741   | i2c_i801   | 43A5D97DD3 |
| 1022:790b | 1043:8747 | AMD        | FCH SMBus Controller         | 726   | i2c_piix4  | 115EC5ECA4 |
| 8086:1e22 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 707   | i2c_i801   | BA117FEF7E |
| 8086:27da | 1043:8179 | Intel      | NM10/ICH7 Family SMBus Co... | 695   | i2c_i801   | 5889B752F5 |
| 1022:790b | 1043:87c0 | AMD        | FCH SMBus Controller         | 665   | i2c_piix4  | 97C17F738A |
| 8086:a123 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 648   | i2c_i801   | 11EBF0D551 |
| 8086:1c22 | 1458:5001 | Intel      | 6 Series/C200 Series Chip... | 632   | i2c_i801   | EE570B7B0C |
| 1022:790b | 1849:790b | AMD        | FCH SMBus Controller         | 602   | i2c_piix4  | E1B676D2A4 |
| 8086:3a30 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) SM... | 601   | i2c_i801   | 2E1659CD91 |
| 1002:4385 |           | AMD        | SBx00 SMBus Controller       | 559   | i2c_pii... | 2B9CBC3FAC |
| 8086:1e22 | 1458:5001 | Intel      | 7 Series/C216 Chipset Fam... | 531   | i2c_i801   | 89F6EB0671 |
| 8086:8c22 | 1458:5001 | Intel      | 8 Series/C220 Series Chip... | 522   | i2c_i801   | E187B3F207 |
| 1002:4385 | 1849:4385 | AMD        | SBx00 SMBus Controller       | 487   | i2c_pii... | 0A228B18C1 |
| 8086:27da | 1849:27da | Intel      | NM10/ICH7 Family SMBus Co... | 445   | i2c_i801   | 87C40FCD51 |
| 10de:03eb | 1849:03eb | Nvidia     | MCP61 SMBus                  | 397   | i2c_nfo... | 615502E93E |
| 8086:a2a3 | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 389   | i2c_i801   | 2696477C0C |
| 1022:780b | 1022:780b | AMD        | FCH SMBus Controller         | 371   | i2c_piix4  | E03FD39AD4 |
| 1022:790b | 1849:ffff | AMD        | FCH SMBus Controller         | 370   | i2c_piix4  | 6056EAC50C |
| 8086:a2a3 | 1458:5001 | Intel      | 200 Series/Z370 Chipset F... | 364   | i2c_i801   | F91A20DD51 |
| 8086:a123 | 1458:5001 | Intel      | 100 Series/C230 Series Ch... | 358   | i2c_i801   | 213A5CCCC3 |
| 8086:2930 | 1043:8277 | Intel      | 82801I (ICH9 Family) SMBu... | 356   | i2c_i801   | 4F6DEFB975 |
| 1022:780b | 1849:780b | AMD        | FCH SMBus Controller         | 332   | i2c_pii... | 3D65247771 |
| 8086:a323 | 1043:8694 | Intel      | Cannon Lake PCH SMBus Con... | 301   | i2c_i801   | 36EBF65D44 |
| 8086:8ca2 | 1043:8534 | Intel      | 9 Series Chipset Family S... | 290   | i2c_i801   | 0D40DAA834 |
| 8086:3a30 | 1458:5001 | Intel      | 82801JI (ICH10 Family) SM... | 273   | i2c_i801   | 0B27475327 |
| 8086:3b30 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 264   | i2c_i801   | AC572EF424 |
| 8086:a323 | 1458:5001 | Intel      | Cannon Lake PCH SMBus Con... | 257   | i2c_i801   | E8B8B03EBD |
| 8086:8c22 | 1849:8c22 | Intel      | 8 Series/C220 Series Chip... | 248   | i2c_i801   | F36828F316 |
| 8086:1c22 | 1849:1c22 | Intel      | 6 Series/C200 Series Chip... | 247   | i2c_i801   | EFEC95A916 |
| 1022:790b | 1043:876b | AMD        | FCH SMBus Controller         | 243   | i2c_piix4  | AB4B1B7A15 |
| 8086:8ca2 | 1458:5001 | Intel      | 9 Series Chipset Family S... | 224   | i2c_i801   | DF13F72A9A |
| 1022:790b | 1022:790b | AMD        | FCH SMBus Controller         | 203   | i2c_piix4  | A82D785D77 |
| 8086:2930 | 1458:5001 | Intel      | 82801I (ICH9 Family) SMBu... | 203   | i2c_i801   | 5B2102BA4E |
| 8086:3b30 | 1458:5001 | Intel      | 5 Series/3400 Series Chip... | 200   | i2c_i801   | 053480926C |
| 10de:03eb | 1458:0c11 | Nvidia     | MCP61 SMBus                  | 195   | i2c_nfo... | FB1E012F68 |
| 8086:1e22 | 1849:1e22 | Intel      | 7 Series/C216 Chipset Fam... | 174   | i2c_i801   | E7EBAD7358 |
| 8086:a123 | 1849:a123 | Intel      | 100 Series/C230 Series Ch... | 173   | i2c_i801   | 3A2A9BD626 |
| 8086:1e22 | 1028:0577 | Intel      | 7 Series/C216 Chipset Fam... | 165   | i2c_i801   | 4DAF9FDC0D |
| 8086:8c22 | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 161   | i2c_i801   | 75E2E357A3 |
| 1022:790b | 1462:7c02 | AMD        | FCH SMBus Controller         | 147   | i2c_piix4  | 2229C9E9F6 |
| 8086:a2a3 | 1849:a2a3 | Intel      | 200 Series/Z370 Chipset F... | 146   | i2c_i801   | A8F84AEA94 |
| 8086:1c22 | 8086:1c22 | Intel      | 6 Series/C200 Series Chip... | 145   | i2c_i801   | 73BFADA83A |
| 1022:790b | 1462:7c37 | AMD        | FCH SMBus Controller         | 144   | i2c_piix4  | 0619809B36 |
| 10de:03eb | 1043:83a4 | Nvidia     | MCP61 SMBus                  | 144   | i2c_nfo... | 1C28AB7987 |
| 1002:4385 | 1462:7693 | AMD        | SBx00 SMBus Controller       | 135   | i2c_pii... | D0FD1CE0E8 |
| 8086:3a60 | 1028:0420 | Intel      | 82801JD/DO (ICH10 Family)... | 134   | i2c_i801   | 5824A76242 |
| 8086:a2a3 | 1043:872f | Intel      | 200 Series/Z370 Chipset F... | 131   | i2c_i801   | C1BF9C169D |
| 1022:780b | 1462:7721 | AMD        | FCH SMBus Controller         | 129   | i2c_piix4  | 01C5E2E798 |
| 8086:1d22 | 1043:84ef | Intel      | C600/X79 series chipset S... | 123   | i2c_i801   | F0DC31F93D |
| 1022:780b | 1043:85ca | AMD        | FCH SMBus Controller         | 119   | i2c_piix4  | BDB612797A |
| 10de:03eb | 1043:8234 | Nvidia     | MCP61 SMBus                  | 116   | i2c_nfo... | A5CA2582B6 |
| 8086:283e | 1043:81ec | Intel      | 82801H (ICH8 Family) SMBu... | 110   | i2c_i801   | 926229BE87 |
| 8086:1c22 | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 108   | i2c_i801   | DB42B43D7E |
| 8086:8c22 | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 106   | i2c_i801   | 0FC3ABDB1C |
| 1002:4385 | 1043:82ef | AMD        | SBx00 SMBus Controller       | 105   | i2c_pii... | 3B96E27283 |
| 1022:780b | 1043:8527 | AMD        | FCH SMBus Controller         | 105   | i2c_piix4  | 83BE665736 |
| 1022:790b | 1462:7b86 | AMD        | FCH SMBus Controller         | 103   | i2c_piix4  | 6787B45989 |
| 8086:8ca2 | 1849:8ca2 | Intel      | 9 Series Chipset Family S... | 103   | i2c_i801   | B203387A22 |
| 8086:2930 | 1028:0211 | Intel      | 82801I (ICH9 Family) SMBu... | 102   | i2c_i801   | 962E0B75E4 |
| 8086:a323 | 1849:a323 | Intel      | Cannon Lake PCH SMBus Con... | 102   | i2c_i801   | 839B20476A |
| 8086:1e22 | 103c:3397 | Intel      | 7 Series/C216 Chipset Fam... | 98    | i2c_i801   | 9C1343DD9B |
| 8086:27da | 8086:27da | Intel      | NM10/ICH7 Family SMBus Co... | 98    | i2c_i801   | A22FBCDE28 |
| 8086:27da | 1462:7592 | Intel      | NM10/ICH7 Family SMBus Co... | 96    | i2c_i801   | 57D1C4DAFA |
| 8086:8d22 | 1043:8600 | Intel      | C610/X99 series chipset S... | 96    | i2c_i801   | E456864B06 |
| 10de:0052 | 1043:815a | Nvidia     | CK804 SMBus                  | 92    | i2c_nfo... | 00B830F623 |
| 1022:790b | 1462:7a38 | AMD        | FCH SMBus Controller         | 89    | i2c_piix4  | 3056DB282E |
| 1022:790b | 1462:7b79 | AMD        | FCH SMBus Controller         | 87    | i2c_pii... | B8D3749011 |
| 8086:3a60 | 1028:027f | Intel      | 82801JD/DO (ICH10 Family)... | 82    | i2c_i801   | 8F0C6ED152 |
| 8086:8c22 | 1028:0612 | Intel      | 8 Series/C220 Series Chip... | 81    | i2c_i801   | 4C34BAF1DC |
| 8086:27da | 1462:7529 | Intel      | NM10/ICH7 Family SMBus Co... | 80    | i2c_i801   | A4B55E447A |
| 1022:790b | 1462:7a34 | AMD        | FCH SMBus Controller         | 78    | i2c_piix4  | D640900B8A |
| 8086:1e22 | 103c:339a | Intel      | 7 Series/C216 Chipset Fam... | 77    | i2c_i801   | BA7CCF28B7 |
| 8086:1c22 | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 73    | i2c_i801   | CA302C374F |
| 8086:3b30 | 1849:3b30 | Intel      | 5 Series/3400 Series Chip... | 73    | i2c_i801   | 8041F40EA2 |
| 8086:1c22 | 1028:047e | Intel      | 6 Series/C200 Series Chip... | 72    | i2c_i801   | 959E3DDE54 |
| 8086:1c22 | 1028:04f5 | Intel      | 6 Series/C200 Series Chip... | 71    | i2c_i801   | 00CE09B473 |
| 8086:283e | 1028:01da | Intel      | 82801H (ICH8 Family) SMBu... | 71    | i2c_i801   | 8939E63ADE |
| 8086:8c22 | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 71    | i2c_i801   | D8309CFECF |
| 10de:03eb | 1462:7309 | Nvidia     | MCP61 SMBus                  | 70    | i2c_nfo... | DC2D2CA478 |
| 8086:1c22 | 1028:0585 | Intel      | 6 Series/C200 Series Chip... | 70    | i2c_i801   | F146C310D6 |
| 1022:790b | 1462:7b89 | AMD        | FCH SMBus Controller         | 69    | i2c_piix4  | 43A19D8280 |
| 8086:1e22 | 1462:7758 | Intel      | 7 Series/C216 Chipset Fam... | 69    | i2c_i801   | 8755040EA2 |
| 8086:1c22 | 103c:1495 | Intel      | 6 Series/C200 Series Chip... | 68    | i2c_i801   | 660C4FF2ED |
| 8086:1c22 | 103c:2abf | Intel      | 6 Series/C200 Series Chip... | 68    | i2c_i801   | 57FFE115AC |
| 8086:27da | 1565:3103 | Intel      | NM10/ICH7 Family SMBus Co... | 68    | i2c_i801   | 960762905F |
| 8086:1e22 | 8086:1e22 | Intel      | 7 Series/C216 Chipset Fam... | 65    | i2c_i801   | 471FDFC5A9 |
| 8086:1c22 | 103c:1497 | Intel      | 6 Series/C200 Series Chip... | 64    | i2c_i801   | 7FA5AD3E42 |
| 8086:27da | 1028:01ad | Intel      | NM10/ICH7 Family SMBus Co... | 64    | i2c_i801   | 132993403B |
| 8086:3a60 | 1734:114d | Intel      | 82801JD/DO (ICH10 Family)... | 64    | i2c_i801   | 8159354A14 |
| 8086:a123 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 64    | i2c_i801   | C007D839E7 |
| 1002:4385 | 1462:7641 | AMD        | SBx00 SMBus Controller       | 62    | i2c_piix4  | 92F2B7546B |
| 1022:780b | 1043:866a | AMD        | FCH SMBus Controller         | 62    | i2c_pii... | 8961CA91B3 |
| 10de:03eb | 1565:3407 | Nvidia     | MCP61 SMBus                  | 62    | i2c_nfo... | FF6423FB29 |
| 10de:0752 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] SMBus  | 62    | i2c_nfo... | 739D1AE9B7 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27d8 | 1458:a002 | Intel      | NM10/ICH7 Family High Def... | 635   | snd_hda... | BD17F8FBD9 |
| 8086:0c0c | 8086:2010 | Intel      | Xeon E3-1200 v3/4th Gen C... | 606   | snd_hda... | E187B3F207 |
| 1002:15de | 1002:15de | AMD        | Raven/Raven2/Fenghuang HD... | 588   | snd_hda... | E5421C72D4 |
| 1002:ab38 | 1002:ab38 | AMD        | Navi 10 HDMI Audio           | 588   | snd_hda... | B8D0E81636 |
| 8086:8c20 | 1043:8576 | Intel      | 8 Series/C220 Series Chip... | 551   | snd_hda... | 87F5B4AFC5 |
| 1002:4383 | 1458:a002 | AMD        | SBx00 Azalia (Intel HDA)     | 546   | snd_hda... | 74D6E4FFA4 |
| 8086:1c20 | 1458:a002 | Intel      | 6 Series/C200 Series Chip... | 515   | snd_hda... | E88DE55691 |
| 8086:8c20 | 1458:a002 | Intel      | 8 Series/C220 Series Chip... | 460   | snd_hda... | E187B3F207 |
| 1002:aaf0 | 1da2:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 426   | snd_hda... | 2E1659CD91 |
| 1002:4383 | 1043:8445 | AMD        | SBx00 Azalia (Intel HDA)     | 392   | snd_hda... | 08ED9AF2B9 |
| 1002:aab0 | 174b:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 361   | snd_hda... | E417B5E11E |
| 10de:0e0f | 1462:8c93 | Nvidia     | GK208 HDMI/DP Audio Contr... | 348   | snd_hda... | F7E3CD3E35 |
| 1022:1457 | 1458:a182 | AMD        | Family 17h (Models 00h-0f... | 345   | snd_hda... | 35C74E640B |
| 8086:a170 | 1043:86c7 | Intel      | 100 Series/C230 Series Ch... | 344   | snd_hda... | 47AA9C9E14 |
| 13f6:0111 | 13f6:0111 | C-Media... | CMI8738/CMI8768 PCI Audio    | 338   | snd_cmipci | 01C5E2E798 |
| 1002:aaf0 | 1462:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 326   | snd_hda... | 84FDA964C3 |
| 8086:1e20 | 1458:a002 | Intel      | 7 Series/C216 Chipset Fam... | 324   | snd_hda... | F55F5434E6 |
| 8086:1c20 | 1043:8445 | Intel      | 6 Series/C200 Series Chip... | 319   | snd_hda... | EA164260EB |
| 8086:0c0c | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 311   | snd_hda... | 0D40DAA834 |
| 1002:4383 | 1043:836c | AMD        | SBx00 Azalia (Intel HDA)     | 310   | snd_hda... | 67B53F9BDB |
| 10de:03f0 | 1849:0397 | Nvidia     | MCP61 High Definition Audio  | 302   | snd_hda... | 0B81DF184D |
| 1002:aab0 | 1043:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 297   | snd_hda... | AA3A28C4B3 |
| 8086:a2f0 | 1458:a182 | Intel      | 200 Series PCH HD Audio      | 294   | snd_hda... | F91A20DD51 |
| 1022:1457 | 1043:86c7 | AMD        | Family 17h (Models 00h-0f... | 291   | snd_hda... | 115EC5ECA4 |
| 8086:1e20 | 1043:8445 | Intel      | 7 Series/C216 Chipset Fam... | 286   | snd_hda... | 330B8B499B |
| 1002:aaf0 | 1682:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 281   | snd_hda... | F544511E0A |
| 8086:a170 | 1458:a182 | Intel      | 100 Series/C230 Series Ch... | 281   | snd_hda... | 213A5CCCC3 |
| 1002:4383 | 1458:a182 | AMD        | SBx00 Azalia (Intel HDA)     | 278   | snd_hda... | 84D927D279 |
| 1022:780d | 1458:a002 | AMD        | FCH Azalia Controller        | 253   | snd_hda... | E03FD39AD4 |
| 8086:1c20 | 1043:8415 | Intel      | 6 Series/C200 Series Chip... | 245   | snd_hda... | 86C4259FBC |
| 1022:15e3 | 1458:a182 | AMD        | Family 17h (Models 10h-1f... | 234   | snd_hda... | F544511E0A |
| 8086:293e | 1043:829f | Intel      | 82801I (ICH9 Family) HD A... | 231   | snd_hda... | 50AE548F24 |
| 8086:27d8 | 1849:3662 | Intel      | NM10/ICH7 Family High Def... | 227   | snd_hda... | 87C40FCD51 |
| 1002:aaf8 | 1002:aaf8 | AMD        | Vega 10 HDMI Audio [Radeo... | 221   | snd_hda... | 6787B45989 |
| 1022:780d | 1043:8576 | AMD        | FCH Azalia Controller        | 214   | snd_hda... | D62C1CC4AA |
| 1002:aaf0 | 1043:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 207   | snd_hda... | 01196F313E |
| 1022:15e3 | 1043:86c7 | AMD        | Family 17h (Models 10h-1f... | 207   | snd_hda... | AB4B1B7A15 |
| 1002:aa98 | 174b:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 205   | snd_hda... | 5101982911 |
| 1002:4383 | 1458:a102 | AMD        | SBx00 Azalia (Intel HDA)     | 203   | snd_hda... | 403EF2DA16 |
| 8086:a2f0 | 1043:86c7 | Intel      | 200 Series PCH HD Audio      | 199   | snd_hda... | DD9596A6B0 |
| 1102:0012 | 1102:0010 | Creativ... | Sound Core3D [Sound Blast... | 192   | snd_hda... | D88D9DB618 |
| 10de:0bea |           | Nvidia     | GF108 High Definition Aud... | 191   | snd_hda... | 2961088957 |
| 10de:03f0 | 1458:a002 | Nvidia     | MCP61 High Definition Audio  | 188   | snd_hda... | FB1E012F68 |
| 8086:3a3e | 1043:82fe | Intel      | 82801JI (ICH10 Family) HD... | 187   | snd_hda... | 102C78CA6B |
| 10de:0be3 |           | Nvidia     | High Definition Audio Con... | 182   | snd_hda... | 5E2CE09E63 |
| 1002:15de | 1043:876b | AMD        | Raven/Raven2/Fenghuang HD... | 177   | snd_hda... | AB4B1B7A15 |
| 1022:1487 | 1043:8797 | AMD        | Starship/Matisse HD Audio... | 177   | snd_hda... | 379D2F0B1C |
| 1002:aab0 | 1458:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 170   | snd_hda... | 1770BBE4E2 |
| 8086:3a3e | 1458:a002 | Intel      | 82801JI (ICH10 Family) HD... | 169   | snd_hda... | 25ABEEE3EF |
| 1002:aa38 | 174b:aa38 | AMD        | RV710/730 HDMI Audio [Rad... | 168   | snd_hda... | 4999ECD668 |
| 8086:27d8 | 1043:8290 | Intel      | NM10/ICH7 Family High Def... | 168   | snd_hda... | 5E2CE09E63 |
| 1002:4383 | 1043:8444 | AMD        | SBx00 Azalia (Intel HDA)     | 167   | snd_hda... | D33CCE58A1 |
| 8086:1e20 | 1028:0577 | Intel      | 7 Series/C216 Chipset Fam... | 164   | snd_hda... | 4DAF9FDC0D |
| 1002:aab0 | 1462:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 163   | snd_hda... | 7B8C559DE7 |
| 1002:aaf0 | 1458:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 163   | snd_hda... | 1AD175FDDC |
| 1022:1487 | 1458:a0c3 | AMD        | Starship/Matisse HD Audio... | 162   | snd_hda... | 2A6868991A |
| 8086:8ca0 | 1458:a182 | Intel      | 9 Series Chipset Family H... | 161   | snd_hda... | E0277E3530 |
| 8086:293e | 1458:a002 | Intel      | 82801I (ICH9 Family) HD A... | 160   | snd_hda... | 18D8466531 |
| 1002:aa68 | 174b:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 157   | snd_hda... | 2C05A7DB2C |
| 8086:3b56 | 1458:a002 | Intel      | 5 Series/3400 Series Chip... | 157   | snd_hda... | 053480926C |
| 8086:a348 | 1458:a182 | Intel      | Cannon Lake PCH cAVS         | 155   | snd_hda... | E8B8B03EBD |
| 1002:4383 | 1849:7892 | AMD        | SBx00 Azalia (Intel HDA)     | 153   | snd_hda... | D811152E10 |
| 8086:1e20 | 1458:a014 | Intel      | 7 Series/C216 Chipset Fam... | 146   | snd_hda... | 89F6EB0671 |
| 1002:aab0 | 1787:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 143   | snd_hda... | 7A75936B55 |
| 1022:1457 | 1043:8723 | AMD        | Family 17h (Models 00h-0f... | 142   | snd_hda... | 2C356ECED5 |
| 1022:1457 | 1849:6893 | AMD        | Family 17h (Models 00h-0f... | 142   | snd_hda... | E1B676D2A4 |
| 1022:780d | 1849:7662 | AMD        | FCH Azalia Controller        | 142   | snd_hda... | 9D17B2FF73 |
| 8086:8c20 | 1462:d817 | Intel      | 8 Series/C220 Series Chip... | 141   | snd_hda... | EA9B132E77 |
| 1002:aae0 | 1da2:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 138   | snd_hda... | 115EC5ECA4 |
| 8086:27d8 | 1849:0397 | Intel      | NM10/ICH7 Family High Def... | 137   | snd_hda... | B9B144530E |
| 1002:aa90 | 174b:aa90 | AMD        | Turks HDMI Audio [Radeon ... | 134   | snd_hda... | 926229BE87 |
| 1022:780d | 1458:a182 | AMD        | FCH Azalia Controller        | 134   | snd_hda... | D37FFBB64D |
| 8086:3a6e | 1028:0420 | Intel      | 82801JD/DO (ICH10 Family)... | 134   | snd_hda... | 5824A76242 |
| 1002:4383 | 1043:84fb | AMD        | SBx00 Azalia (Intel HDA)     | 133   | snd_hda... | 8B10E96F42 |
| 8086:a2f0 | 1043:8723 | Intel      | 200 Series PCH HD Audio      | 133   | snd_hda... | C1BF9C169D |
| 10de:0bee |           | Nvidia     | GF116 High Definition Aud... | 130   | snd_hda... | 08ED9AF2B9 |
| 8086:a348 | 1043:86c7 | Intel      | Cannon Lake PCH cAVS         | 130   | snd_hda... | 243CDC0172 |
| 1022:1457 | 1043:8733 | AMD        | Family 17h (Models 00h-0f... | 128   | snd_hda... | 8C22CAC892 |
| 8086:1c20 | 8086:1c20 | Intel      | 6 Series/C200 Series Chip... | 128   | snd_hda... | 7502A08A7F |
| 1002:aa58 | 174b:aa58 | AMD        | Juniper HDMI Audio [Radeo... | 127   | snd_hda... | 9D17B2FF73 |
| 1022:780d | 1462:d721 | AMD        | FCH Azalia Controller        | 127   | snd_hda... | 01C5E2E798 |
| 1002:aa68 | 1043:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 125   | snd_hda... | 13B5910BEB |
| 1002:4383 | 1462:d693 | AMD        | SBx00 Azalia (Intel HDA)     | 124   | snd_hda... | D0FD1CE0E8 |
| 10de:0fb9 | 1462:8c96 | Nvidia     | GP107GL High Definition A... | 123   | snd_hda... | C1BF9C169D |
| 10de:0fb8 | 1462:8c98 | Nvidia     | GP108 High Definition Aud... | 122   | snd_hda... | 229B36F7F9 |
| 1002:aab0 | 1682:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 121   | snd_hda... | 8271176E88 |
| 8086:0c0c | 1849:0c0c | Intel      | Xeon E3-1200 v3/4th Gen C... | 117   | snd_hda... | 98BBC7AD66 |
| 1002:aae0 | 1043:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 116   | snd_hda... | 20115EE05D |
| 8086:1c20 | 1043:8444 | Intel      | 6 Series/C200 Series Chip... | 114   | snd_hda... | 4837692ECC |
| 1002:4383 | 1043:8436 | AMD        | SBx00 Azalia (Intel HDA)     | 113   | snd_hda... | 30406DF55B |
| 1002:4383 | 1043:8576 | AMD        | SBx00 Azalia (Intel HDA)     | 112   | snd_hda... | 1B80AC0E66 |
| 1002:aaf0 | 148c:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 112   | snd_hda... | D2BE74763C |
| 8086:293e | 1043:8277 | Intel      | 82801I (ICH9 Family) HD A... | 109   | snd_hda... | 4F6DEFB975 |
| 1002:9902 | 1849:9902 | AMD        | Trinity HDMI Audio Contro... | 108   | snd_hda... | FC022F03F6 |
| 8086:1c20 | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 108   | snd_hda... | DB42B43D7E |
| 8086:284b | 1043:81ec | Intel      | 82801H (ICH8 Family) HD A... | 108   | snd_hda... | 926229BE87 |
| 1002:4383 | 1849:7662 | AMD        | SBx00 Azalia (Intel HDA)     | 107   | snd_hda... | 6BDF2E77C2 |
| 1022:1487 | 1043:87c5 | AMD        | Starship/Matisse HD Audio... | 106   | snd_hda... | 65310866EB |
| 1102:0007 | 1102:100a | Creativ... | CA0106/CA0111 [SB Live!/A... | 105   | snd_ca0106 | 46A65E835D |
| 1002:4383 | 1458:a132 | AMD        | SBx00 Azalia (Intel HDA)     | 104   | snd_hda... | 77FCB9CF4A |

### Storage (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1283:8211 | 1043:8138 | Integra... | ITE 8211F Single Channel ... | 38    | pata_it... | 72B40A39D4 |
| 105a:4d68 | 105a:4d68 | Promise... | PDC20268 [Ultra100 TX2]      | 4     | pata_pd... | 6967AF910D |
| 105a:4d69 | 105a:4d68 | Promise... | 20269                        | 4     | pata_pd... | 21833C414E |
| 1106:401a | 1028:02f5 | VIA Tec... | VIA Card Reader Host Cont... | 4     |            | 8EF532D4EC |
| 105a:3d17 | 105a:3d17 | Promise... | PDC40718 (SATA 300 TX4)      | 3     | sata_pr... | 50A778F706 |
| 105a:3d73 | 105a:3d73 | Promise... | PDC40775 (SATA 300 TX2plus)  | 3     | sata_pr... | 8FFB1720D8 |
| 1077:2432 | 1077:0138 | QLogic     | ISP2432-based 4Gb Fibre C... | 3     | qla2xxx    | FB66D16E30 |
| 1283:8211 | 1283:8211 | Integra... | ITE 8211F Single Channel ... | 3     | pata_it... | BF5B58520E |
| 104c:8033 | 103c:3085 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 2     | tifm_7xx1  | 32F7B77B77 |
| 105a:3375 | 105a:3375 | Promise... | PDC20375 (SATA150 TX2plus)   | 2     | sata_pr... | 2A0863DD05 |
| 1077:2432 | 103c:7040 | QLogic     | ISP2432-based 4Gb Fibre C... | 2     | qla2xxx    | 3A362598FB |
| 1077:2532 | 103c:3263 | QLogic     | ISP2532-based 8Gb Fibre C... | 2     | qla2xxx    | D018E3FE5A |
| 10df:f100 | 1014:038a | Emulex     | LPe12000 Series 8Gb Fibre... | 2     | lpfc       | 0767C99ABB |
| 10df:fe00 | 10df:fe00 | Emulex     | Zephyr-X LightPulse Fibre... | 2     | lpfc       | F930BC123E |
| 1106:401a | 1106:401a | VIA Tec... | VIA Card Reader Host Cont... | 2     |            | FF6AA83006 |
| 104c:803b | 152d:0754 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 79905DEFFE |
| 1077:2312 | 1077:0100 | QLogic     | ISP2312-based 2Gb Fibre C... | 1     | qla2xxx    | 17333FB7FD |
| 1077:2532 | 1077:015d | QLogic     | ISP2532-based 8Gb Fibre C... | 1     | qla2xxx    | 7A2B809CB8 |
| 1095:0680 | 1095:0680 | Silicon... | PCI0680 Ultra ATA-133 Hos... | 1     | pata_si... | E77A0A6719 |
| 10b9:5289 | 1043:816b | ULi Ele... | ULi 5289 SATA                | 1     | sata_uli   | 1473488491 |
| 10df:0724 | 10df:e86b | Emulex     | OneConnect FCoE Initiator... | 1     | lpfc       | 68F608CA5B |
| 10df:f0e5 | 10df:f0e5 | Emulex     | Zephyr LightPulse Fibre C... | 1     | lpfc       | 24CFA19EA6 |
| 10df:fe00 | 10df:fe01 | Emulex     | Zephyr-X LightPulse Fibre... | 1     | lpfc       | CAEF8BBDD2 |
| 1103:0004 | 1103:0005 | HighPoi... | HPT366/368/370/370A/372/372N | 1     | pata_hp... | FB58321498 |
| 1106:401a | 1028:0408 | VIA Tec... | VIA Card Reader Host Cont... | 1     |            | B55E0BA8CB |
| 1217:7130 | 1025:0124 | O2 Micro   | Integrated MS/xD Controller  | 1     |            | 1F2C670EC4 |
| 1217:7130 | 14ff:a003 | O2 Micro   | Integrated MS/xD Controller  | 1     |            | 6647A9CB02 |
| 1217:7130 | 1631:0188 | O2 Micro   | Integrated MS/xD Controller  | 1     |            | 7E9A381494 |
| 19a2:0704 | 10df:e602 | Emulex     | OneConnect OCe10100/OCe10... | 1     | lpfc       | 456CDA8C49 |
| 1aed:2001 | 1590:006d | SanDisk    | ioDrive2                     | 1     |            | 4A5147AC07 |
| 1aed:2001 | 1aed:2001 | SanDisk    | ioDrive2                     | 1     | iomemor... | 80E12BBDD7 |
| 1aed:3002 | 1014:04d3 | SanDisk    | ioMemory HHHL                | 1     |            | FB0D0A1860 |
| 1aed:3002 | 1137:013d | SanDisk    | ioMemory HHHL                | 1     |            | 775B21277B |
| ace1:0005 | ace1:0005 |            | Storage controller           | 1     |            | 22F215C605 |
| ace1:0006 | ace1:0006 |            | Storage controller           | 1     |            | EF20304D33 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:43c8 | 1b21:1062 | AMD        | 400 Series Chipset SATA C... | 1881  | ahci       | 97C17F738A |
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 1230  | ahci       | 0619809B36 |
| 1022:7901 | 1458:b002 | AMD        | FCH SATA Controller [AHCI... | 999   | ahci       | F544511E0A |
| 8086:8c02 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 763   | ahci       | 9A23DF55D8 |
| 1022:7901 | 1043:8747 | AMD        | FCH SATA Controller [AHCI... | 720   | ahci       | 115EC5ECA4 |
| 1002:4390 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 702   | ahci       | 74D6E4FFA4 |
| 1002:4391 | 1043:84dd | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 637   | ahci       | 9F527DED3C |
| 1002:4390 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 636   | ahci       | 67B53F9BDB |
| 1002:4391 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 633   | ahci       | 77FCB9CF4A |
| 8086:a102 | 1043:8694 | Intel      | Q170/Q150/B150/H170/H110/... | 632   | ahci       | 11EBF0D551 |
| 1022:43b7 | 1b21:1062 | AMD        | 300 Series Chipset SATA C... | 600   | ahci       | 52C67D407D |
| 1022:7901 | 1849:7901 | AMD        | FCH SATA Controller [AHCI... | 591   | ahci       | E1B676D2A4 |
| 8086:1c02 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 572   | ahci       | EA164260EB |
| 1b21:0612 | 1043:84b7 | ASMedia... | ASM1062 Serial ATA Contro... | 546   | ahci       | 9F527DED3C |
| 8086:1e02 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 528   | ahci       | BA117FEF7E |
| 1022:43b8 | 1b21:1062 | AMD        | FCH SATA Controller D        | 505   | ahci       | 4654691B7A |
| 8086:8c02 | 1458:b005 | Intel      | 8 Series/C220 Series Chip... | 491   | ahci       | E187B3F207 |
| 1b21:0612 | 1849:0612 | ASMedia... | ASM1062 Serial ATA Contro... | 489   | ahci       | 39FCD76D77 |
| 1022:43eb | 1b21:1062 | AMD        | Starship/Matisse Chipset ... | 424   | ahci       | A82D785D77 |
| 1b21:0612 | 1b21:1060 | ASMedia... | ASM1062 Serial ATA Contro... | 352   | ahci       | 0619809B36 |
| 8086:a102 | 1458:b005 | Intel      | Q170/Q150/B150/H170/H110/... | 352   | ahci       | 213A5CCCC3 |
| 8086:a282 | 1043:8694 | Intel      | 200 Series PCH SATA contr... | 350   | ahci       | 2696477C0C |
| 8086:a282 | 1458:b005 | Intel      | 200 Series PCH SATA contr... | 348   | ahci       | F91A20DD51 |
| 1022:7901 | 1043:87c0 | AMD        | FCH SATA Controller [AHCI... | 338   | ahci       | 97C17F738A |
| 1022:43b5 | 1b21:1062 | AMD        | X370 Series Chipset SATA ... | 337   | ahci       | F544511E0A |
| 1022:43c8 | 1849:43c8 | AMD        | 400 Series Chipset SATA C... | 312   | ahci       | FCFE2F037F |
| 1002:4391 | 1849:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 293   | ahci       | 0A228B18C1 |
| 8086:1e02 | 1458:b005 | Intel      | 7 Series/C210 Series Chip... | 282   | ahci       | 89F6EB0671 |
| 1022:7801 | 1849:7801 | AMD        | FCH SATA Controller [AHCI... | 280   | ahci       | 3D65247771 |
| 1022:7801 | 1458:b002 | AMD        | FCH SATA Controller [AHCI... | 268   | ahci       | E03FD39AD4 |
| 8086:8c82 | 1043:8534 | Intel      | 9 Series Chipset Family S... | 262   | ahci       | 0D40DAA834 |
| 8086:a352 | 1043:8694 | Intel      | Cannon Lake PCH SATA AHCI... | 260   | ahci       | 2CFB272CEC |
| 8086:1c02 | 1458:b005 | Intel      | 6 Series/C200 Series Chip... | 238   | ahci       | EE570B7B0C |
| 8086:a352 | 1458:b005 | Intel      | Cannon Lake PCH SATA AHCI... | 234   | ahci       | E8B8B03EBD |
| 8086:8c02 | 1849:8c02 | Intel      | 8 Series/C220 Series Chip... | 232   | ahci       | F36828F316 |
| 1022:7901 | 1043:876b | AMD        | FCH SATA Controller [AHCI... | 225   | ahci       | 500976E7D1 |
| 1b4b:9172 | 1458:b000 | Marvell... | 88SE9172 SATA 6Gb/s Contr... | 224   | ahci       | 912C8764EF |
| 197b:2362 | 1043:8460 | JMicron... | JMB362 SATA Controller       | 219   | ahci       | A7526AA47D |
| 8086:8c82 | 1458:b005 | Intel      | 9 Series Chipset Family S... | 212   | ahci       | DF13F72A9A |
| 1002:4390 | 1849:4390 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 207   | ahci       | 256C66503A |
| 8086:3a22 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) SA... | 203   | ahci       | 2E1659CD91 |
| 1b21:0612 | 1043:858d | ASMedia... | ASM1062 Serial ATA Contro... | 199   | ahci       | 86CEE5AEF6 |
| 8086:a102 | 1849:a102 | Intel      | Q170/Q150/B150/H170/H110/... | 170   | ahci       | 3A2A9BD626 |
| 8086:1e02 | 1849:1e02 | Intel      | 7 Series/C210 Series Chip... | 166   | ahci       | E7EBAD7358 |
| 1022:7800 | 1458:b002 | AMD        | FCH SATA Controller [IDE ... | 160   | ahci       | 0E94F2AD8F |
| 8086:1e02 | 1028:0577 | Intel      | 7 Series/C210 Series Chip... | 157   | ahci       | 4DAF9FDC0D |
| 1022:7901 | 1849:ffff | AMD        | FCH SATA Controller [AHCI... | 153   | ahci       | CCD56ACB24 |
| 8086:8c02 | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 152   | ahci       | 75E2E357A3 |
| 1002:4391 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 149   | ahci       | EF97789A6A |
| 8086:1c02 | 1849:1c02 | Intel      | 6 Series/C200 Series Chip... | 148   | ahci       | EFEC95A916 |
| 1002:4390 | 1002:4390 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 143   | ahci       | F977555A51 |
| 8086:a282 | 1849:a282 | Intel      | 200 Series PCH SATA contr... | 138   | ahci       | A8F84AEA94 |
| 1022:7901 | 1462:7c02 | AMD        | FCH SATA Controller [AHCI... | 137   | ahci       | 2229C9E9F6 |
| 1022:43b6 | 1b21:1062 | AMD        | X399 Series Chipset SATA ... | 136   | ahci       | 9A02CBA527 |
| 1022:7801 | 1462:7721 | AMD        | FCH SATA Controller [AHCI... | 126   | ahci       | 01C5E2E798 |
| 1b4b:9215 | 1b4b:9215 | Marvell... | 88SE9215 PCIe 2.0 x1 4-po... | 125   | ahci       | 3310677E00 |
| 1022:7801 | 1043:85ca | AMD        | FCH SATA Controller [AHCI... | 117   | ahci       | BDB612797A |
| 8086:1d02 | 1043:84ef | Intel      | C600/X79 series chipset 6... | 114   | ahci       | F0DC31F93D |
| 1022:43b8 | 1849:43c8 | AMD        | FCH SATA Controller D        | 113   | ahci       | 094ADE14AE |
| 8086:a282 | 1043:872f | Intel      | 200 Series PCH SATA contr... | 111   | ahci       | C1BF9C169D |
| 1002:4391 | 1002:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 108   | ahci       | B4E0DCBA77 |
| 1b4b:9130 | 1043:8438 | Marvell... | 88SE9128 PCIe SATA 6 Gb/s... | 104   | ahci       | BA117FEF7E |
| 1b4b:9172 | 1043:8477 | Marvell... | 88SE9172 SATA 6Gb/s Contr... | 104   | ahci       | 2B0DE1BA10 |
| 8086:1c02 | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 102   | ahci       | DB42B43D7E |
| 1022:7801 | 1043:8527 | AMD        | FCH SATA Controller [AHCI... | 101   | ahci       | 83BE665736 |
| 8086:3a22 | 1458:b005 | Intel      | 82801JI (ICH10 Family) SA... | 101   | ahci       | CECF736FB7 |
| 1022:7901 | 1462:7b86 | AMD        | FCH SATA Controller [AHCI... | 98    | ahci       | 6787B45989 |
| 8086:8c82 | 1849:8c82 | Intel      | 9 Series Chipset Family S... | 98    | ahci       | B203387A22 |
| 8086:a352 | 1849:a352 | Intel      | Cannon Lake PCH SATA AHCI... | 98    | ahci       | 839B20476A |
| 1002:4390 | 1043:82ef | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 94    | ahci       | 3B96E27283 |
| 1022:7901 | 1462:7c37 | AMD        | FCH SATA Controller [AHCI... | 92    | ahci       | 9B20A88D5E |
| 8086:3b22 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 91    | ahci       | 66C62DC8F8 |
| 8086:1e02 | 103c:3397 | Intel      | 7 Series/C210 Series Chip... | 88    | ahci       | 9C1343DD9B |
| 1022:7901 | 1462:7a38 | AMD        | FCH SATA Controller [AHCI... | 85    | ahci       | 3056DB282E |
| 8086:3b22 | 1458:b005 | Intel      | 5 Series/3400 Series Chip... | 85    | ahci       | 053480926C |
| 1022:7901 | 1462:7b79 | AMD        | FCH SATA Controller [AHCI... | 84    | ahci       | B8D3749011 |
| 1002:4391 | 1462:7693 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 83    | ahci       | D0FD1CE0E8 |
| 8086:1c02 | 8086:1c02 | Intel      | 6 Series/C200 Series Chip... | 82    | ahci       | 7502A08A7F |
| 8086:2922 | 1028:0211 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 80    | ahci       | 962E0B75E4 |
| 8086:8d02 | 1043:8600 | Intel      | C610/X99 series chipset 6... | 80    | ahci       | E456864B06 |
| 1022:7901 | 1462:7a34 | AMD        | FCH SATA Controller [AHCI... | 78    | ahci       | D640900B8A |
| 8086:8c02 | 1028:0612 | Intel      | 8 Series/C220 Series Chip... | 76    | ahci       | 4C34BAF1DC |
| 8086:1e02 | 103c:339a | Intel      | 7 Series/C210 Series Chip... | 72    | ahci       | BA7CCF28B7 |
| 8086:1c02 | 1028:0585 | Intel      | 6 Series/C200 Series Chip... | 70    | ahci       | F146C310D6 |
| 8086:1e02 | 1462:7758 | Intel      | 7 Series/C210 Series Chip... | 68    | ahci       | 8755040EA2 |
| 8086:3a02 | 1028:027f | Intel      | 82801JD/DO (ICH10 Family)... | 68    | ahci       | 8F0C6ED152 |
| 1002:4390 | 1043:8443 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 67    | ahci       | 23198E478A |
| 8086:8c02 | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 66    | ahci       | D8309CFECF |
| 1022:7901 | 1462:7b89 | AMD        | FCH SATA Controller [AHCI... | 64    | ahci       | 43A19D8280 |
| 8086:a102 | 1462:7996 | Intel      | Q170/Q150/B150/H170/H110/... | 64    | ahci       | C007D839E7 |
| 1022:43b7 | 1849:43c8 | AMD        | 300 Series Chipset SATA C... | 62    | ahci       | A0686A3F62 |
| 1022:7801 | 1043:866a | AMD        | FCH SATA Controller [AHCI... | 60    | ahci       | 8961CA91B3 |
| 8086:8d62 | 1043:8600 | Intel      | C610/X99 series chipset s... | 60    | ahci       | E456864B06 |
| 8086:1c02 | 103c:2abf | Intel      | 6 Series/C200 Series Chip... | 59    | ahci       | 57FFE115AC |
| 8086:1d02 | 8086:1d02 | Intel      | C600/X79 series chipset 6... | 58    | ahci       | 150AFCB2D1 |
| 8086:1c02 | 103c:1495 | Intel      | 6 Series/C200 Series Chip... | 57    | ahci       | 660C4FF2ED |
| 1002:4380 | 1043:81ef | AMD        | SB600 Non-Raid-5 SATA        | 56    | ahci       | 425DF4A110 |
| 8086:1c02 | 103c:1497 | Intel      | 6 Series/C200 Series Chip... | 56    | ahci       | 7FA5AD3E42 |
| 8086:1c02 | 1734:11ba | Intel      | 6 Series/C200 Series Chip... | 56    | ahci       | 17A4D716C5 |
| 8086:8c02 | 103c:18e7 | Intel      | 8 Series/C220 Series Chip... | 56    | ahci       | 9844F6635C |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:439c | 1458:5002 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1083  | pata_at... | 77FCB9CF4A |
| 8086:27df | 1043:8179 | Intel      | 82801G (ICH7 Family) IDE ... | 983   | ata_pii... | 5889B752F5 |
| 1002:439c | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 786   | pata_at... | 67B53F9BDB |
| 8086:27c0 | 1458:b002 | Intel      | NM10/ICH7 Family SATA Con... | 735   | ata_pii... | 43A5D97DD3 |
| 8086:27c0 | 1043:8179 | Intel      | NM10/ICH7 Family SATA Con... | 708   | ata_pii... | 5889B752F5 |
| 197b:2363 | 1458:b000 | JMicron... | JMB363 SATA/IDE Controller   | 475   | ahci       | 053480926C |
| 1002:439c | 1849:439c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 463   | pata_at... | 0A228B18C1 |
| 8086:1c00 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 448   | ata_pii... | 86C4259FBC |
| 8086:1c08 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 448   | ata_pii... | 86C4259FBC |
| 8086:27c0 | 1849:27c0 | Intel      | NM10/ICH7 Family SATA Con... | 431   | ata_pii... | 87C40FCD51 |
| 8086:27df | 1849:27df | Intel      | 82801G (ICH7 Family) IDE ... | 418   | ata_pii... | 87C40FCD51 |
| 8086:3a20 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) 4 ... | 406   | ata_pii... | 102C78CA6B |
| 8086:3a26 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) 2 ... | 406   | ata_pii... | 102C78CA6B |
| 10de:03f6 | 1849:03f6 | Nvidia     | MCP61 SATA Controller        | 396   | sata_nv... | 615502E93E |
| 8086:1c08 | 1458:b002 | Intel      | 6 Series/C200 Series Chip... | 391   | ata_pii... | E88DE55691 |
| 10de:03ec | 1849:03ec | Nvidia     | MCP61 IDE                    | 367   | pata_am... | 615502E93E |
| 197b:2363 | 1043:824f | JMicron... | JMB363 SATA/IDE Controller   | 309   | ahci       | 73FAB078B8 |
| 8086:2926 | 1043:8277 | Intel      | 82801I (ICH9 Family) 2 po... | 307   | ata_pii... | 4F6DEFB975 |
| 197b:2368 | 1458:b000 | JMicron... | JMB368 IDE controller        | 295   | pata_jm... | 7A17D8EFEF |
| 8086:27c0 | 1043:2601 | Intel      | NM10/ICH7 Family SATA Con... | 283   | ata_pii... | 5E2CE09E63 |
| 8086:1e00 | 1458:b005 | Intel      | 7 Series/C210 Series Chip... | 226   | ata_pii... | F55F5434E6 |
| 8086:1e08 | 1458:b002 | Intel      | 7 Series/C210 Series Chip... | 226   | ata_pii... | F55F5434E6 |
| 1022:780c | 1849:780c | AMD        | FCH IDE Controller           | 219   | pata_at... | 3D65247771 |
| 8086:1c00 | 1458:b005 | Intel      | 6 Series/C200 Series Chip... | 206   | ata_pii... | E88DE55691 |
| 8086:2921 | 1043:8277 | Intel      | 82801IB (ICH9) 2 port SAT... | 199   | ata_pii... | 80549ACBBA |
| 10de:03f6 | 1458:b002 | Nvidia     | MCP61 SATA Controller        | 195   | sata_nv... | FB1E012F68 |
| 197b:2363 | 1043:81e4 | JMicron... | JMB363 SATA/IDE Controller   | 190   | ahci       | 95E596A827 |
| 8086:1c00 | 1458:b002 | Intel      | 6 Series/C200 Series Chip... | 189   | ata_pii... | 2AB2DABD84 |
| 1106:0415 | 1043:838f | VIA Tec... | VT6415 PATA IDE Host Cont... | 182   | pata_vi... | AC572EF424 |
| 8086:3a20 | 1458:b002 | Intel      | 82801JI (ICH10 Family) 4 ... | 174   | ata_pii... | 0B27475327 |
| 8086:3a26 | 1458:b002 | Intel      | 82801JI (ICH10 Family) 2 ... | 174   | ata_pii... | 0B27475327 |
| 1022:780c | 1458:5002 | AMD        | FCH IDE Controller           | 173   | pata_at... | 14F43DC84D |
| 197b:2368 | 1043:827e | JMicron... | JMB368 IDE controller        | 170   | pata_jm... | 965BC51C8D |
| 8086:3b20 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 169   | ata_pii... | AC572EF424 |
| 8086:3b26 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 169   | ata_pii... | AC572EF424 |
| 8086:1e00 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 159   | ata_pii... | 524DE3A747 |
| 8086:1e08 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 159   | ata_pii... | 524DE3A747 |
| 8086:27df | 1458:b001 | Intel      | 82801G (ICH7 Family) IDE ... | 158   | ata_pii... | BD17F8FBD9 |
| 1002:439c | 1002:439c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 156   | pata_at... | F977555A51 |
| 8086:2926 | 1458:b002 | Intel      | 82801I (ICH9 Family) 2 po... | 156   | ata_pii... | 5B2102BA4E |
| 10de:03f6 | 1043:83a4 | Nvidia     | MCP61 SATA Controller        | 144   | sata_nv... | 1C28AB7987 |
| 10de:03ec | 1458:5002 | Nvidia     | MCP61 IDE                    | 142   | pata_am... | FB1E012F68 |
| 10de:03ec | 1043:83a4 | Nvidia     | MCP61 IDE                    | 139   | pata_am... | 1C28AB7987 |
| 8086:27c0 | 8086:27c0 | Intel      | NM10/ICH7 Family SATA Con... | 137   | pata_acpi  | A22FBCDE28 |
| 11ab:6101 | 1043:82e0 | Marvell... | 88SE6101/6102 single-port... | 129   | pata_ma... | 7AAC504D79 |
| 8086:27df | 8086:27df | Intel      | 82801G (ICH7 Family) IDE ... | 120   | pata_acpi  | A22FBCDE28 |
| 10de:03f6 | 1043:8234 | Nvidia     | MCP61 SATA Controller        | 116   | sata_nv... | A5CA2582B6 |
| 10de:03ec | 1043:8234 | Nvidia     | MCP61 IDE                    | 113   | pata_am... | A5CA2582B6 |
| 8086:3b20 | 1458:b002 | Intel      | 5 Series/3400 Series Chip... | 113   | ata_pii... | 25153D8586 |
| 8086:3b26 | 1458:b002 | Intel      | 5 Series/3400 Series Chip... | 113   | ata_pii... | 25153D8586 |
| 11ab:6101 | 11ab:6101 | Marvell... | 88SE6101/6102 single-port... | 111   | pata_ma... | D76E4B9EC3 |
| 8086:2920 | 1043:8277 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 108   | ata_pii... | 4F6DEFB975 |
| 1002:439c | 1043:82ef | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 105   | pata_at... | 3B96E27283 |
| 8086:1c00 | 1849:1c00 | Intel      | 6 Series/C200 Series Chip... | 103   | ata_pii... | 3F3962DF59 |
| 8086:1c08 | 1849:1c08 | Intel      | 6 Series/C200 Series Chip... | 102   | ata_pii... | 3F3962DF59 |
| 8086:27c0 | 1462:7592 | Intel      | NM10/ICH7 Family SATA Con... | 96    | pata_acpi  | 57D1C4DAFA |
| 10de:0053 | 1043:815a | Nvidia     | CK804 IDE                    | 92    | pata_am... | 00B830F623 |
| 10de:0055 | 1043:815a | Nvidia     | CK804 Serial ATA Controller  | 92    | sata_nv... | 00B830F623 |
| 10de:0054 | 1043:815a | Nvidia     | CK804 Serial ATA Controller  | 91    | sata_nv... | 00B830F623 |
| 8086:29b6 | 1028:0211 | Intel      | 82Q35 Express PT IDER Con... | 91    | pata_acpi  | 962E0B75E4 |
| 11ab:6121 | 1043:82a2 | Marvell... | 88SE6111/6121 SATA II / P... | 89    | pata_ma... | 50AE548F24 |
| 8086:2825 | 1043:81ec | Intel      | 82801HR/HO/HH (ICH8R/DO/D... | 89    | ata_pii... | 926229BE87 |
| 8086:2820 | 1043:81ec | Intel      | 82801H (ICH8 Family) 4 po... | 88    | ata_pii... | 926229BE87 |
| 8086:27df | 1462:7592 | Intel      | 82801G (ICH7 Family) IDE ... | 87    | pata_acpi  | 57D1C4DAFA |
| 8086:2e16 | 1028:0420 | Intel      | 4 Series Chipset PT IDER ... | 84    | pata_acpi  | 340184FB36 |
| 8086:27c0 | 1462:7529 | Intel      | NM10/ICH7 Family SATA Con... | 80    | ata_pii... | A4B55E447A |
| 8086:2921 | 1458:b002 | Intel      | 82801IB (ICH9) 2 port SAT... | 79    | ata_pii... | D0DD5188EE |
| 8086:2e16 | 1028:027f | Intel      | 4 Series Chipset PT IDER ... | 79    | pata_acpi  | 8F0C6ED152 |
| 11ab:6121 | 1043:82e0 | Marvell... | 88SE6111/6121 SATA II / P... | 78    | pata_ma... | 102C78CA6B |
| 8086:27df | 1462:7529 | Intel      | 82801G (ICH7 Family) IDE ... | 78    | ata_pii... | A4B55E447A |
| 197b:2363 | 197b:2363 | JMicron... | JMB363 SATA/IDE Controller   | 77    | ahci       | 47F43BD121 |
| 8086:2920 | 1458:b002 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 77    | pata_acpi  | 5B2102BA4E |
| 1002:439c | 1043:8443 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 72    | pata_at... | 23198E478A |
| 10de:03f6 | 1462:7309 | Nvidia     | MCP61 SATA Controller        | 71    | sata_nv... | DC2D2CA478 |
| 8086:1c00 | 1028:04f5 | Intel      | 6 Series/C200 Series Chip... | 71    | pata_acpi  | 00CE09B473 |
| 8086:1c08 | 1028:04f5 | Intel      | 6 Series/C200 Series Chip... | 71    | pata_acpi  | 00CE09B473 |
| 8086:2820 | 1028:01da | Intel      | 82801H (ICH8 Family) 4 po... | 71    | pata_acpi  | 8939E63ADE |
| 8086:2825 | 1028:01da | Intel      | 82801HR/HO/HH (ICH8R/DO/D... | 71    | pata_acpi  | 8939E63ADE |
| 197b:2361 | 1043:824f | JMicron... | JMB361 AHCI/IDE              | 68    | ahci       | A39538D7C5 |
| 8086:27c0 | 1565:5202 | Intel      | NM10/ICH7 Family SATA Con... | 67    | ata_piix   | 960762905F |
| 8086:27df | 1565:3103 | Intel      | 82801G (ICH7 Family) IDE ... | 67    | ata_piix   | 960762905F |
| 1002:439c | 1462:7641 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 64    | pata_at... | 26947ED7FD |
| 8086:24db | 1043:80a6 | Intel      | 82801EB/ER (ICH5/ICH5R) I... | 64    | ata_pii... | 97A6A04DB2 |
| 8086:27c0 | 1028:01ad | Intel      | NM10/ICH7 Family SATA Con... | 64    | pata_acpi  | 132993403B |
| 197b:2368 | 1043:824f | JMicron... | JMB368 IDE controller        | 63    | pata_jm... | 4F6DEFB975 |
| 1b4b:917a | 1458:b000 | Marvell... | 88SE9172 SATA III 6Gb/s R... | 63    | pata_ac... | EE570B7B0C |
| 10de:03f6 | 1565:5405 | Nvidia     | MCP61 SATA Controller        | 62    | sata_nv... | FF6423FB29 |
| 1106:0415 | 1849:0415 | VIA Tec... | VT6415 PATA IDE Host Cont... | 62    | pata_vi... | CB9E834556 |
| 8086:27df | 1028:01ad | Intel      | 82801G (ICH7 Family) IDE ... | 62    | pata_acpi  | 132993403B |
| 10de:03ec | 1565:3407 | Nvidia     | MCP61 IDE                    | 61    | pata_am... | FF6423FB29 |
| 11ab:6121 | 1043:8212 | Marvell... | 88SE6111/6121 SATA II / P... | 61    | pata_ma... | 2E1659CD91 |
| 1b4b:91a4 | 1b4b:91a4 | Marvell... | 88SE912x IDE Controller      | 60    | pata_ma... | 33BB3C3B9A |
| 1b4b:91a3 | 1458:b000 | Marvell... | 88SE91A3 SATA-600 Controller | 59    | ahci, p... | FFBD75E61F |
| 11ab:6121 | 11ab:6121 | Marvell... | 88SE6111/6121 SATA II / P... | 58    | pata_ma... | AE45AB5C00 |
| 10de:0759 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] IDE    | 57    | pata_am... | 739D1AE9B7 |
| 8086:2e16 | 1734:114c | Intel      | 4 Series Chipset PT IDER ... | 56    | pata_acpi  | 8159354A14 |
| 8086:1c00 | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 55    | ata_pii... | 6C184C27D1 |
| 8086:1c08 | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 55    | ata_pii... | 6C184C27D1 |
| 8086:2920 | 1028:020d | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 55    | pata_acpi  | 8A955D2C5A |
| 8086:2926 | 1028:020d | Intel      | 82801I (ICH9 Family) 2 po... | 55    | pata_acpi  | 8A955D2C5A |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 1637  | nvme       | B8D0E81636 |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 504   | nvme       | B8D0E81636 |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 444   | nvme       | 3D0DA576B8 |
| 1987:5016 | 1987:5016 | Phison ... | E16 PCIe4 NVMe Controller    | 242   | nvme       | 65310866EB |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 231   | nvme       | 20115EE05D |
| 126f:2263 | 126f:2263 | Silicon... | SM2263EN/SM2263XT SSD Con... | 229   | nvme       | 92E5728D1A |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 205   | nvme       | 6BC1B9DCC9 |
| 2646:2263 | 2646:2263 | Kingsto... | A2000 NVMe SSD               | 201   | nvme       | 5125306D59 |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/SN750 / PC ... | 188   | nvme       | 36248F1BF0 |
| c0a9:2263 | c0a9:2263 | Micron/... | P1 NVMe PCIe SSD             | 166   | nvme       | 4E5245A71D |
| 15b7:5009 | 15b7:5009 | Sandisk    | WD Blue SN550 NVMe SSD       | 163   | nvme       | 150AFCB2D1 |
| 15b7:5006 | 15b7:5006 | Sandisk    | WD Black SN750 / PC SN730... | 116   | nvme       | 804CEE7367 |
| 126f:2262 | 126f:2262 | Silicon... | SM2262/SM2262EN SSD Contr... | 107   | nvme       | C2640FC882 |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 106   | nvme       | 52789C01CA |
| 144d:a80a | 144d:a801 | Samsung... | NVMe SSD Controller PM9A1... | 87    | nvme       | 62DDF1B4F0 |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 75    | nvme       | 3D1A8CFFC3 |
| 10ec:5762 | 10ec:5762 | Realtek... | RTS5763DL NVMe SSD Contro... | 69    | nvme       | 099F671965 |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 67    | nvme       | 97C17F738A |
| 2646:5008 | 2646:5008 | Kingsto... | U-SNS8154P3 NVMe SSD         | 60    | nvme       | 36EBF65D44 |
| 15b7:5003 | 15b7:5003 | Sandisk    | WD Blue SN500 / PC SN520 ... | 53    | nvme       | ECBF2FC044 |
| 1987:5007 | 1987:5007 | Phison ... | E7 NVMe Controller           | 47    | nvme       | 0F7555A7BD |
| 1987:5013 | 1987:5013 | Phison ... | PS5013 E13 NVMe Controller   | 47    | nvme       | E2588635B4 |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | BC501 NVMe Solid State Dr... | 42    | nvme       | B183BADDEF |
| c0a9:540a | c0a9:540a | Micron/... | P2 NVMe PCIe SSD             | 42    | nvme       | B3724909EC |
| 1987:5008 | 1987:5008 | Phison ... | NVMe Storage Controller      | 41    | nvme       | E8B8B03EBD |
| 10ec:5763 | 10ec:5763 | Realtek... | Realtek Non-Volatile memo... | 39    | nvme       | 2C356ECED5 |
| c0a9:5403 | c0a9:2100 | Micron/... | NVMe Controller              | 37    | nvme       | A82D785D77 |
| 15b7:5001 | 1b4b:1093 | Sandisk    | WD Black NVMe SSD            | 33    | nvme       | E71B786BE5 |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 27    | nvme       | 57A08FFCEB |
| 144d:a809 | 144d:a801 | Samsung... | NVMe Controller              | 25    | nvme       | CEF790F685 |
| 1179:0113 | 1179:0001 | Toshiba... | BG3 NVMe SSD Controller      | 24    | nvme       | 48C22EC264 |
| 14a4:23f1 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 24    | nvme       | BD59689744 |
| 1bb1:5016 | 1bb1:5016 | Seagate... | FireCuda 520 SSD             | 23    | nvme       | 9B20A88D5E |
| 14a4:22f1 | 1b4b:1093 | Lite-On... | M8Pe Series NVMe SSD         | 19    | nvme       | 4601ED2BC4 |
| 1b85:6018 | 1b85:6018 | OCZ Tec... | RD400/400A SSD               | 19    | nvme       | EC035AF0D0 |
| 1179:011a | 1179:0001 | Toshiba... | XG6 NVMe SSD Controller      | 18    | nvme       | 64C121A751 |
| 1344:5405 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 18    | nvme       | 862B2D2013 |
| 1bb1:5012 | 1bb1:5012 | Seagate... | FireCuda 510 SSD             | 18    | nvme       | E0217F85A6 |
| 15b7:5011 | 15b7:5011 | Sandisk    | WD Black SN850               | 16    | nvme       | 654C105561 |
| 1179:0115 | 1179:0001 | Toshiba... | XG4 NVMe SSD Controller      | 14    | nvme       | 016DA6343D |
| 8086:2522 | 8086:3806 | Intel      | NVMe Optane Memory Series    | 14    | nvme       | 40B6622CD1 |
| 8086:faf0 | 8086:390e | Intel      | Non-Volatile memory contr... | 14    | nvme       | AA8070C052 |
| 8086:0953 | 8086:370d | Intel      | PCIe Data Center SSD         | 13    | nvme       | A479D22343 |
| 2646:2262 | 2646:2262 | Kingsto... | KC2000 NVMe SSD              | 12    | nvme       | 6566F6CABC |
| c0a9:5412 | c0a9:0100 | Micron/... | Non-Volatile memory contr... | 12    | nvme       | E278178887 |
| 1c5c:1339 | 1c5c:0000 | SK Hynix   | BC511                        | 11    | nvme       | 68A723FA33 |
| 10ec:5760 | 5760:10ec | Realtek... | Realtek Non-Volatile memo... | 10    | nvme       | C169D54571 |
| 126f:2260 | 126f:2260 | Silicon... | Non-Volatile memory contr... | 10    | nvme       | 3997021D7C |
| c0a9:5403 | c0a9:1100 | Micron/... | NVMe Controller              | 9     | nvme       | 06BB083E38 |
| 1344:5410 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 8     | nvme       | 4391FFAA59 |
| 1cc1:8201 | 1cc1:1cc1 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 8     | nvme       | FE32C3D470 |
| 1e0f:0001 | 1e0f:0001 | KIOXIA     | Non-Volatile memory contr... | 8     | nvme       | B83A47D4F0 |
| 8086:2700 | 8086:3900 | Intel      | Optane SSD 900P Series       | 8     | nvme       | F72C74AA38 |
| 8086:2700 | 8086:3901 | Intel      | Optane SSD 900P Series       | 8     | nvme       | 6FEB0AEC47 |
| 1c5c:1527 | 1c5c:1527 | SK Hynix   | PC401 NVMe Solid State Dr... | 7     | nvme       | 6F116ECC61 |
| 1c5c:1627 | 1c5c:1627 | SK Hynix   | Non-Volatile memory contr... | 6     | nvme       | 3F081F03FE |
| 1e0f:0009 | 1e0f:0001 | KIOXIA     | NVMe SSD                     | 6     | nvme       | 0548F9650B |
| 14a4:9100 | 126f:2263 | Lite-On... | NVMe Controller              | 5     | nvme       | D32CA82327 |
| 1c5c:1639 | 1c5c:1639 | SK Hynix   | Non-Volatile memory contr... | 5     | nvme       | 3440F55127 |
| 1cc1:5350 | 1987:5016 | ADATA T... | Non-Volatile memory contr... | 5     | nvme       | 14ACBA97FD |
| 14a4:21f1 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 4     | nvme       | 6D05038359 |
| 1987:5018 | 1987:5018 | Phison ... | Electronics Non-Volatile ... | 4     | nvme       | A133667E3C |
| 1cc1:5350 | 1cc1:5350 | ADATA T... | A Non-Volatile memory con... | 4     | nvme       | C458B6D1CA |
| 1d97:1160 | 1d97:1160 | Shenzhe... | Non-Volatile memory contr... | 4     | nvme       | F0572BBD96 |
| 1d97:2263 | 1d97:2263 | Shenzhe... | SM2263EN/SM2263XT-based O... | 4     | nvme       | 7DBDABF49B |
| 8086:0a54 | 8086:4802 | Intel      | NVMe Datacenter SSD [3DNA... | 4     | nvme       | 1D97B5C83D |
| 8086:2522 | 8086:3810 | Intel      | NVMe Optane Memory Series    | 4     | nvme       | AB87264048 |
| 14a4:2200 | 1b4b:1093 | Lite-On... | Lite-On Non-Volatile memo... | 3     | nvme       | 780814E8B8 |
| 14a4:2300 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 3     | nvme       | 4FE62C374E |
| 15b7:5004 | 15b7:5004 | Sandisk    | PC SN520 NVMe SSD            | 3     | nvme       | 7781CAF2E7 |
| 15b7:5005 | 15b7:5005 | Sandisk    | PC SN520 NVMe SSD            | 3     | nvme       | F9C36A0B6A |
| 1c5c:1283 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 3     | nvme       | F5F2BF1F67 |
| 1c5c:1284 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 3     | nvme       | 212AE07786 |
| 1c5c:174a | 1c5c:174a | SK Hynix   | NVMe SSD Controller          | 3     | nvme       | 370F1A16B9 |
| 1cc4:5008 | 1cc4:5008 | Union M... | Non-Volatile memory contr... | 3     | nvme       | 099F671965 |
| 1e0f:0008 | 1e0f:0001 | KIOXIA     | Non-Volatile memory contr... | 3     | nvme       | CCDC5F822C |
| 8086:2522 | 8086:3802 | Intel      | NVMe Optane Memory Series    | 3     | nvme       | 3F106C54BA |
| 1179:010f | 1179:0001 | Toshiba... | NVMe Controller              | 2     | nvme       | A225772655 |
| 17aa:0003 | 17aa:1003 | Lenovo     | Non-Volatile memory contr... | 2     | nvme       | D6371109B2 |
| 1b4b:1092 | 1d97:1092 | Marvell... | Marvell Non-Volatile memo... | 2     | nvme       | FD5B65A6E0 |
| 1cc1:2263 | 1cc1:2263 | ADATA T... | Non-Volatile memory contr... | 2     | nvme       | 1B292E7E77 |
| 2646:500d | 2646:500d | Kingsto... | OM3PDP3 NVMe SSD             | 2     | nvme       | 6CA0E6E16F |
| 2646:500e | 2646:500e | Kingsto... | Technology Company Non-Vo... | 2     | nvme       | 7B5519E189 |
| 8086:0953 | 8086:370e | Intel      | PCIe Data Center SSD         | 2     | nvme       | 4F903969F9 |
| 8086:0975 | 8086:8410 | Intel      | Non-Volatile memory contr... | 2     | nvme       | B6AD3B9AA7 |
| 8086:0975 | 8086:8510 | Intel      | Non-Volatile memory contr... | 2     | nvme       | B6AD3B9AA7 |
| 1022:b000 | 144d:a801 | AMD        | RAID Bottom Device           | 1     | nvme       | B52CAEFF3E |
| 1022:b000 | 15b7:5009 | AMD        | RAID Bottom Device           | 1     | nvme       | 755C7A9AD6 |
| 1022:b000 | 15b7:5011 | AMD        | RAID Bottom Device           | 1     | nvme       | C8AD5F8EF8 |
| 1022:b000 | 1987:5016 | AMD        | RAID Bottom Device           | 1     | nvme       | C8AD5F8EF8 |
| 1022:b000 | 1bb1:5016 | AMD        | RAID Bottom Device           | 1     | nvme       | BB19B5F213 |
| 1022:b000 | 1cc1:8201 | AMD        | RAID Bottom Device           | 1     | nvme       | 10498E9D12 |
| 1022:b000 | 2646:2263 | AMD        | RAID Bottom Device           | 1     | nvme       | 2C59BE484E |
| 10ec:5765 | 10ec:5765 | Realtek... | Realtek Non-Volatile memo... | 1     | nvme       | 7996857A22 |
| 1344:5180 | 1344:4000 | Micron ... | 9100 PRO NVMe SSD            | 1     | nvme       | 07CD9EAC56 |
| 1344:5181 | 1344:3000 | Micron ... | 9100 MAX NVMe SSD            | 1     | nvme       | A479D22343 |
| 1344:51a2 | 1344:3100 | Micron ... | Non-Volatile memory contr... | 1     | nvme       | 0BAAF1410F |
| 144d:a822 | 144d:a812 | Samsung... | NVMe SSD Controller 172Xa... | 1     | nvme       | 3062914F46 |
| 14a4:2100 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 1     | nvme       | 3DDAB16FAC |
| 14a4:22a0 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 1     | nvme       | 3F19AA9605 |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2822 | 1043:8694 | Intel      | SATA Controller [RAID mode]  | 105   | ahci       | 243CDC0172 |
| 8086:2822 | 1458:b005 | Intel      | SATA Controller [RAID mode]  | 81    | ahci       | 197E319075 |
| 8086:2822 | 1028:0420 | Intel      | SATA Controller [RAID mode]  | 75    | ahci       | 5824A76242 |
| 1106:3249 | 1106:3249 | VIA Tec... | VT6421 IDE/SATA Controller   | 63    | sata_via   | 5BFD23A80C |
| 8086:2822 | 1028:05a4 | Intel      | SATA Controller [RAID mode]  | 63    | ahci       | 86611A5EFE |
| 8086:2822 | 1028:047e | Intel      | SATA Controller [RAID mode]  | 49    | ahci       | 959E3DDE54 |
| 8086:2822 | 103c:1309 | Intel      | SATA Controller [RAID mode]  | 40    | ahci       | 83C114D947 |
| 8086:2822 | 103c:2a6f | Intel      | SATA Controller [RAID mode]  | 38    | ahci       | D8F52BAB1C |
| 1095:3114 | 1095:7114 | Silicon... | SiI 3114 [SATALink/SATARa... | 37    | sata_sil   | 20EBDE2857 |
| 1022:7916 | 1022:7901 | AMD        | RS690 PCI to PCI Bridge (... | 35    | ahci       | 56B16C9C71 |
| 8086:2822 | 103c:2a9c | Intel      | SATA Controller [RAID mode]  | 34    | ahci       | 9A3C939249 |
| 8086:2822 | 1043:8534 | Intel      | SATA Controller [RAID mode]  | 32    | ahci       | 8F3CA163E7 |
| 8086:2822 | 103c:130a | Intel      | SATA Controller [RAID mode]  | 28    | ahci       | EE9A2DA17C |
| 8086:2822 | 1028:052c | Intel      | SATA Controller [RAID mode]  | 27    | ahci       | C016FC8897 |
| 1095:3132 | 1043:819f | Silicon... | SiI 3132 Serial ATA Raid ... | 25    | sata_sil24 | 0C04CD404A |
| 1095:3132 | 1095:7132 | Silicon... | SiI 3132 Serial ATA Raid ... | 24    | sata_sil24 | 799AD15D8B |
| 8086:2822 | 1028:0293 | Intel      | SATA Controller [RAID mode]  | 24    | ahci       | ACE51E66CB |
| 8086:2822 | 1458:b000 | Intel      | SATA Controller [RAID mode]  | 24    | ahci       | 9021BAB8E3 |
| 1022:43bd | 1b21:1062 | AMD        | FCH RAID Controller          | 23    | rcraid     | 220E356F41 |
| 1095:3512 | 1095:6512 | Silicon... | SiI 3512 [SATALink/SATARa... | 23    | sata_sil   | 751F3FAAFA |
| 8086:2826 | 103c:1589 | Intel      | C600/X79 series chipset S... | 22    | ahci       | 2F621A1BA2 |
| 8086:2822 | 1043:872f | Intel      | SATA Controller [RAID mode]  | 19    | ahci       | AB16E4844B |
| 8086:2822 | 103c:130b | Intel      | SATA Controller [RAID mode]  | 16    | ahci       | DFA7EF3696 |
| 8086:2827 | 103c:212b | Intel      | C610/X99 series chipset s... | 16    | ahci       | 84296E0108 |
| 1095:0680 | 1095:3680 | Silicon... | PCI0680 Ultra ATA-133 Hos... | 15    | pata_si... | DFA6B5B067 |
| 8086:2822 | 1043:84ca | Intel      | SATA Controller [RAID mode]  | 15    | ahci       | 0190551F1E |
| 1002:4392 | 103c:2a92 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 14    | ahci       | C3468E4972 |
| 8086:2822 | 1028:05a6 | Intel      | SATA Controller [RAID mode]  | 14    | ahci       | 8280DED412 |
| 8086:2826 | 103c:158a | Intel      | C600/X79 series chipset S... | 14    | ahci       | 2FAC0FA486 |
| 1106:3149 | 1043:80ed | VIA Tec... | VIA VT6420 SATA RAID Cont... | 13    | sata_via   | E739F2F0BA |
| 8086:2822 | 1028:02da | Intel      | SATA Controller [RAID mode]  | 13    | ahci       | 253FA3E49B |
| 8086:2822 | 1043:844d | Intel      | SATA Controller [RAID mode]  | 13    | ahci       | 2B0DE1BA10 |
| 8086:2826 | 1028:0738 | Intel      | C600/X79 series chipset S... | 13    | ahci       | 862B2D2013 |
| 8086:2826 | 103c:158b | Intel      | C600/X79 series chipset S... | 13    | ahci       | E7D78D4E6C |
| 8086:2826 | 103c:212b | Intel      | C600/X79 series chipset S... | 13    | ahci       | 84296E0108 |
| 1106:3164 | 1106:3164 | VIA Tec... | VT6410 ATA133 RAID contro... | 12    | pata_vi... | E9ED9C7FDF |
| 8086:2822 | 1025:1238 | Intel      | SATA Controller [RAID mode]  | 12    | ahci       | 5C8AF3A6F6 |
| 8086:2822 | 1028:06b9 | Intel      | SATA Controller [RAID mode]  | 12    | ahci       | 8989DF3C9D |
| 103c:323a | 103c:3245 | Hewlett... | Smart Array G6 controllers   | 11    | hpsa       | 2ED58CCD22 |
| 13c1:1004 | 13c1:1004 | 3ware      | 9650SE SATA-II RAID PCIe     | 11    | 3w_9xxx    | FDAC79E308 |
| 8086:2822 | 1025:0389 | Intel      | SATA Controller [RAID mode]  | 11    | ahci       | 8B9E2FB5F2 |
| 8086:2822 | 1025:0589 | Intel      | SATA Controller [RAID mode]  | 11    | ahci       | A32F68C5FD |
| 8086:2822 | 103c:1905 | Intel      | SATA Controller [RAID mode]  | 11    | ahci       | FD0F9E5AB1 |
| 1002:4392 | 1025:0444 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 10    | ahci       | E6FABE6D7F |
| 1039:0180 | 1043:810e | Silicon... | RAID bus controller 180 S... | 10    | sata_sis   | 7A323363EF |
| 105a:3373 | 1043:80f5 | Promise... | PDC20378 (FastTrak 378/SA... | 10    | sata_pr... | E739F2F0BA |
| 1095:3112 | 1095:6112 | Silicon... | SiI 3112 [SATALink/SATARa... | 10    | sata_sil   | D74A86CE44 |
| 10de:07f8 | 1025:0137 | Nvidia     | MCP73 SATA RAID Controller   | 10    | ahci       | 8533331911 |
| 1283:8212 |           | Integra... | IT8212 Dual channel ATA R... | 10    | pata_it... | 2C5644ED9F |
| 8086:27c3 | 103c:2a50 | Intel      | 82801GR/GDH (ICH7R/ICH7DH... | 10    | ahci       | 925EDCDDDC |
| 8086:2822 | 1028:01dd | Intel      | SATA Controller [RAID mode]  | 10    | ahci       | 3E22711262 |
| 8086:2822 | 1028:0276 | Intel      | SATA Controller [RAID mode]  | 10    | ahci       | 8B417F82C5 |
| 8086:2822 | 1028:040d | Intel      | SATA Controller [RAID mode]  | 10    | ahci       | F2760185E3 |
| 8086:2822 | 1028:07a3 | Intel      | SATA Controller [RAID mode]  | 10    | ahci       | F3E4767726 |
| 8086:2826 | 1028:0617 | Intel      | C600/X79 series chipset S... | 10    | ahci       | 6C581928CA |
| 1000:0073 | 1028:1f78 | LSI Log... | MegaRAID SAS 2008 [Falcon]   | 9     | megarai... | 536202A82C |
| 1002:4392 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 9     | ahci       | 6509F2AF70 |
| 1002:4393 | 1043:84df | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 9     | ahci       | B7175ABF98 |
| 11ab:6440 | 1043:82e4 | Marvell... | 88SE6440 SAS/SATA PCIe co... | 9     | mvsas      | FA9AA5A2B0 |
| 8086:201d | 1028:0738 | Intel      | Volume Management Device ... | 9     | vmd        | 7149315F22 |
| 8086:27c3 | 103c:2a5e | Intel      | 82801GR/GDH (ICH7R/ICH7DH... | 9     | ahci       | BDCEFA45C2 |
| 8086:2822 | 1025:024c | Intel      | SATA Controller [RAID mode]  | 9     | ahci       | D6E0E0433A |
| 8086:2822 | 1028:01db | Intel      | SATA Controller [RAID mode]  | 9     | ahci       | 579C253FDA |
| 8086:2822 | 1028:026e | Intel      | SATA Controller [RAID mode]  | 9     | ahci       | 31DA132AE8 |
| 8086:2822 | 1028:0859 | Intel      | SATA Controller [RAID mode]  | 9     | ahci       | F7FD36E7FD |
| 8086:2822 | 1849:2822 | Intel      | SATA Controller [RAID mode]  | 9     | ahci       | 1A53BCFAEE |
| 10de:0abc | 1025:0168 | Nvidia     | MCP79 RAID Controller        | 8     | ahci       | 547C1BF7D7 |
| 11ab:6485 | 17aa:1023 | Marvell... | MV64460/64461/64462 Syste... | 8     | mvsas      | B18EBB71D3 |
| 8086:2682 | 103c:1307 | Intel      | 631xESB/632xESB SATA RAID... | 8     | ahci       | 3B9C7E2331 |
| 8086:2822 | 1025:0427 | Intel      | SATA Controller [RAID mode]  | 8     | ahci       | D9EBC79158 |
| 8086:2822 | 1028:07a1 | Intel      | SATA Controller [RAID mode]  | 8     | ahci       | B9807FA858 |
| 8086:2822 | 1028:07c5 | Intel      | SATA Controller [RAID mode]  | 8     | ahci       | A897526E05 |
| 8086:2822 | 103c:1308 | Intel      | SATA Controller [RAID mode]  | 8     | ahci       | 1A9967AEFE |
| 8086:2822 | 103c:1790 | Intel      | SATA Controller [RAID mode]  | 8     | ahci       | 75557F3294 |
| 8086:2822 | 103c:1791 | Intel      | SATA Controller [RAID mode]  | 8     | ahci       | AD7AD34A9D |
| 8086:2822 | 1043:82d4 | Intel      | SATA Controller [RAID mode]  | 8     | ahci       | A2C823DDD7 |
| 8086:2822 | 1043:8383 | Intel      | SATA Controller [RAID mode]  | 8     | ahci       | 83F55D5BF7 |
| 8086:2822 | 1849:a282 | Intel      | SATA Controller [RAID mode]  | 8     | ahci       | FAE57C7146 |
| 1002:4393 | 1002:4393 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 7     | ahci       | 9CAFB3AD7A |
| 1022:7917 | 1022:7901 | AMD        | RS690 PCI to PCI Bridge (... | 7     | ahci       | 36279FACCE |
| 1095:3124 | 1095:7124 | Silicon... | SiI 3124 PCI-X Serial ATA... | 7     | sata_sil24 | CFF51C85DA |
| 10de:0266 | 1028:0249 | Nvidia     | MCP51 Serial ATA Controller  | 7     | sata_nv    | 85C12975E9 |
| 10de:0267 | 1028:0249 | Nvidia     | MCP51 Serial ATA Controller  | 7     | sata_nv    | 85C12975E9 |
| 1283:8212 | 1043:813a | Integra... | IT8212 Dual channel ATA R... | 7     | pata_it... | 5A7ACF0D43 |
| 8086:2822 | 1028:0498 | Intel      | SATA Controller [RAID mode]  | 7     | ahci       | 304541CE36 |
| 8086:2822 | 1028:05d7 | Intel      | SATA Controller [RAID mode]  | 7     | ahci       | 54C021054A |
| 8086:2822 | 103c:1906 | Intel      | SATA Controller [RAID mode]  | 7     | ahci       | E2C686283C |
| 8086:2822 | 1043:873c | Intel      | SATA Controller [RAID mode]  | 7     | ahci       | D5CDC97C3B |
| 9005:028b | 9005:0200 | Adaptec    | Series 6 - 6G SAS/PCIe 2     | 7     | aacraid    | 8FFB1720D8 |
| 1002:4393 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 6     | ahci       | F2C9184779 |
| 1095:3114 | 1043:8167 | Silicon... | SiI 3114 [SATALink/SATARa... | 6     | sata_sil   | C16C928715 |
| 1106:3149 | 1458:b003 | VIA Tec... | VIA VT6420 SATA RAID Cont... | 6     | sata_vi... | A64CE477EC |
| 11ab:6485 | 11ab:6480 | Marvell... | MV64460/64461/64462 Syste... | 6     | mvsas      | 225F795531 |
| 1283:8212 | 1283:0001 | Integra... | IT8212 Dual channel ATA R... | 6     | pata_it... | FBC56A055A |
| 8086:2822 | 1028:064c | Intel      | SATA Controller [RAID mode]  | 6     | ahci       | E31C5F36AA |
| 8086:2822 | 1028:085c | Intel      | SATA Controller [RAID mode]  | 6     | ahci       | D5A07EB379 |
| 8086:2822 | 1043:8600 | Intel      | SATA Controller [RAID mode]  | 6     | ahci       | 46919A42A3 |
| 8086:2826 | 103c:2129 | Intel      | C600/X79 series chipset S... | 6     | ahci       | 83DFC4B9D8 |
| 8086:2827 | 103c:2129 | Intel      | C610/X99 series chipset s... | 6     | ahci       | 83DFC4B9D8 |
| 9005:0241 | 9005:0241 | Adaptec    | Serial ATA II RAID 1420SA    | 6     | sata_mv    | 51D5CDB6E0 |

### Storage/sas (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1d6b | 103c:1589 | Intel      | C602 chipset 4-Port SATA ... | 34    | isci       | A4B0EBBEE2 |
| 1000:0086 | 103c:158b | Broadco... | SAS2308 PCI-Express Fusio... | 26    | mpt3sas    | 3991895525 |
| 8086:1d6b | 103c:158a | Intel      | C602 chipset 4-Port SATA ... | 24    | isci       | D70166F107 |
| 8086:1d6b | 103c:158b | Intel      | C602 chipset 4-Port SATA ... | 19    | isci       | E7D78D4E6C |
| 1000:0072 | 1000:3020 | LSI Log... | SAS2008 PCI-Express Fusio... | 18    | mpt3sas    | A0D316EB3E |
| 8086:1d6b | 1028:0497 | Intel      | C602 chipset 4-Port SATA ... | 11    | isci       | E81DFF7452 |
| 1000:0072 | 1028:1f1c | LSI Log... | SAS2008 PCI-Express Fusio... | 10    | mpt3sas    | 6F289497FC |
| 1000:0087 | 1028:05a1 | Broadco... | SAS2308 PCI-Express Fusio... | 9     | mpt3sas    | F62AEF3E7A |
| 8086:1d6b | 1734:11b6 | Intel      | C602 chipset 4-Port SATA ... | 8     | isci       | D018E3FE5A |
| 1000:0087 | 1000:3020 | LSI Log... | SAS2308 PCI-Express Fusio... | 6     | mpt3sas    | 065D69BE16 |
| 8086:1d6b | 17aa:1026 | Intel      | C602 chipset 4-Port SATA ... | 5     | isci       | 4EBE8CAFC5 |
| 8086:1d6b | 1849:1d6b | Intel      | C602 chipset 4-Port SATA ... | 5     | isci       | 957F68F2B7 |
| 1000:0070 | 1000:3010 | LSI Log... | SAS2004 PCI-Express Fusio... | 4     | mpt3sas    | 3440F55127 |
| 1000:0086 | 15d9:0691 | Broadco... | SAS2308 PCI-Express Fusio... | 4     | mpt3sas    | 837CECDAE8 |
| 1000:0087 | 1000:3060 | Broadco... | SAS2308 PCI-Express Fusio... | 4     | mpt3sas    | 84296E0108 |
| 1000:0097 | 1028:0619 | Broadco... | SAS3008 PCI-Express Fusio... | 4     | mpt3sas    | F96F352657 |
| 1000:0072 | 1000:3060 | Broadco... | SAS2008 PCI-Express Fusio... | 3     | mpt3sas    | 524206EFF9 |
| 1000:0072 | 1028:1f1d | LSI Log... | SAS2008 PCI-Express Fusio... | 3     | mpt3sas    | 3B9C7E2331 |
| 1000:0097 | 1000:30a0 | Broadco... | SAS3008 PCI-Express Fusio... | 3     | mpt3sas    | 98EA3E97E6 |
| 8086:1d60 | 1028:0497 | Intel      | C608 chipset Dual 4-Port ... | 3     | isci       | E5B81A0DA1 |
| 8086:1d6b | 15d9:062c | Intel      | C602 chipset 4-Port SATA ... | 3     | isci       | FF94B1201C |
| 8086:1d6b | 17aa:1028 | Intel      | C602 chipset 4-Port SATA ... | 3     | isci       | 20CB7C14F8 |
| 1000:0064 | 1000:30c0 | Broadco... | SAS2116 PCI-Express Fusio... | 2     | mpt3sas    | 7AEE1156D8 |
| 1000:0072 | 1000:30f0 | Broadco... | SAS2008 PCI-Express Fusio... | 2     | mpt3sas    | 6EEDB26906 |
| 1000:0072 | 15d9:0400 | Broadco... | SAS2008 PCI-Express Fusio... | 2     | mpt3sas    | 96607F4270 |
| 1000:007e | 108e:050a | Broadco... | SSS6200 PCI-Express Flash... | 2     | mpt3sas    | A7CF5B0EFD |
| 1000:0087 | 1000:3030 | Broadco... | SAS2308 PCI-Express Fusio... | 2     | mpt3sas    | 1D8E87502F |
| 1000:0097 | 1028:1f46 | Broadco... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | 3C396F0B59 |
| 1000:0097 | 1734:1214 | LSI Log... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | A7138E79C0 |
| 1000:00c4 | 1000:31a0 | Broadco... | SAS3224 PCI-Express Fusio... | 2     | mpt3sas    | 195F9748AD |
| 8086:1d68 | 1028:0495 | Intel      | C606 chipset Dual 4-Port ... | 2     | isci       | 1AC850D5B7 |
| 8086:1d6a | 17aa:1027 | Intel      | C600/X79 series chipset D... | 2     | isci       | 8D7A62CE1A |
| 8086:1d6b | 1028:0495 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | BC7C3F8C4D |
| 8086:1d6b | 1028:0496 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 80E68A5C66 |
| 8086:1d6b | 15d9:0709 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 7D84E25468 |
| 8086:1d6b | 17aa:1027 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | E3C6A7B793 |
| 1000:005d | 1000:9a63 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | megarai... | 8EFAF14886 |
| 1000:0064 | 1000:30d0 | Broadco... | SAS2116 PCI-Express Fusio... | 1     | mpt3sas    | 3294F4EFD3 |
| 1000:0072 | 1000:3080 | LSI Log... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | FFC0ECBF18 |
| 1000:0072 | 1000:30b0 | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | 9BF79EF1CD |
| 1000:0086 | 1000:0086 | LSI Log... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | C0122E3715 |
| 1000:0087 | 1590:0041 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | E106326D63 |
| 1000:0087 | 1590:0043 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | AB5267E214 |
| 1000:0087 | 8086:3060 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | F2B18DC242 |
| 1000:0097 | 1000:30e0 | LSI Log... | SAS3008 PCI-Express Fusio... | 1     | mpt3sas    | 7E2DAE216D |
| 1000:0097 | 1043:860c | Broadco... | SAS3008 PCI-Express Fusio... | 1     | mpt3sas    | C624F64EDE |
| 1000:0097 | 1849:0097 | Broadco... | SAS3008 PCI-Express Fusio... | 1     | mpt3sas    | FA8D061F8F |
| 1000:00ac | 1000:3000 | Broadco... | SAS3416 Fusion-MPT Tri-Mo... | 1     | mpt3sas    | 8C80B197C2 |
| 117c:0042 | 117c:0042 | ATTO Te... | ExpressSAS 6Gb/s SAS/SATA... | 1     | pm80xx     | 2DF53AC534 |
| 8086:1d60 | 1028:0496 | Intel      | C608 chipset Dual 4-Port ... | 1     | isci       | 1518FF90F9 |
| 8086:1d68 | 15d9:0626 | Intel      | C606 chipset Dual 4-Port ... | 1     | isci       | 2B8813F5C4 |
| 8086:1d68 | 15d9:0628 | Intel      | C606 chipset Dual 4-Port ... | 1     | isci       | 74EFA61302 |
| 8086:1d68 | 8086:1d68 | Intel      | C606 chipset Dual 4-Port ... | 1     | isci       | EBA3BBC86D |
| 8086:1d69 | 15d9:0706 | Intel      | C604/X79 series chipset 4... | 1     | isci       | AA3D8595BA |
| 8086:1d69 | 17aa:1026 | Intel      | C604/X79 series chipset 4... | 1     | isci       | 7EB1F254C9 |
| 8086:1d69 | 8086:1d69 | Intel      | C604/X79 series chipset 4... | 1     | isci       | 53874D702A |
| 8086:1d6b |           | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 99E743CA9E |
| 8086:1d6b | 15d9:0628 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | F7519BF7BE |
| 8086:1d6b | 15d9:062b | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | A897C366A9 |
| 8086:1d6b | 15d9:0667 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 8FDC5D8AB4 |
| 8086:1d6b | 15d9:070a | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 1F3561AA7D |
| 9005:028d | 9005:0651 | Adaptec    | Series 8 12G SAS/PCIe 3      | 1     | aacraid    | 19A9020FEF |
| 9005:028f | 103c:0600 | Adaptec    | Smart Storage PQI SAS        | 1     | smartpqi   | EB3B40AD4F |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1000:0058 | 1028:021d | LSI Log... | SAS1068E PCI-Express Fusi... | 23    | mptsas     | 0BA08ED8F7 |
| 1000:0058 | 103c:130b | LSI Log... | SAS1068E PCI-Express Fusi... | 18    | mptsas     | DFA7EF3696 |
| 1000:0056 | 1000:3090 | LSI Log... | SAS1064ET PCI-Express Fus... | 11    | mptsas     | 08F4C825CC |
| 1000:0058 | 1028:1f0e | LSI Log... | SAS1068E PCI-Express Fusi... | 10    | mptsas     | 8D7A62CE1A |
| 9004:5078 | 9004:7850 | Adaptec    | AIC-7850T/7856T [AVA-2902... | 9     | aic7xxx    | 97C7481343 |
| 9004:7178 |           | Adaptec    | AIC-7870P/7871 [AHA-2940/... | 8     | aic7xxx    | BDB612797A |
| 1000:0054 | 103c:0a98 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 7     | mptsas     | FC2E31C91F |
| 9004:8178 |           | Adaptec    | AIC-7870P/7881U [AHA-2940... | 6     | aic7xxx    | E4B76F9137 |
| 1b85:1021 | 1b85:1021 | OCZ Tec... | OCZ SCSI storage controller  | 5     | mvsas      | 71E296F6E0 |
| 9004:8178 | 9004:7881 | Adaptec    | AIC-7870P/7881U [AHA-2940... | 5     | aic7xxx    | 4C68880898 |
| 1000:0050 | 103c:3015 | Broadco... | SAS1064 PCI-X Fusion-MPT SAS | 4     | mptsas     | C20157D427 |
| 1de1:0391 | 1de1:0391 | Tekram ... | TRM-S1040 [DC-315 / DC-39... | 4     | dc395x     | 510A70AB34 |
| 9005:8017 | 9005:0045 | Adaptec    | ASC-29320ALP U320            | 4     | aic79xx    | BB541DFDE4 |
| 1000:0001 |           | LSI Log... | 53c810                       | 3     | sym53c8xx  | 608EBB649B |
| 1000:0030 | 103c:12f1 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 3     | mptspi     | AD9D1EDCBB |
| 1000:0030 | 103c:1500 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 3     | mptspi     | A94946D561 |
| 1000:0054 | 1028:1f08 | LSI Log... | SAS1068 PCI-X Fusion-MPT SAS | 3     | mptsas     | CB363A3342 |
| 1000:0058 | 103c:12fe | LSI Log... | SAS1068E PCI-Express Fusi... | 3     | mptsas     | 0633057EE1 |
| 1000:0058 | 103c:3229 | LSI Log... | SAS1068E PCI-Express Fusi... | 3     | mptsas     | 371F1B5B54 |
| 10cd:1300 | 10cd:1310 | Advance... | ASC1300 / ASC3030 [ABP940... | 3     | advansys   | A978613702 |
| 9004:5078 |           | Adaptec    | AIC-7850T/7856T [AVA-2902... | 3     | aic7xxx    | 330F034C61 |
| 9004:6178 |           | Adaptec    | AIC-7861                     | 3     | aic7xxx    | A35B309960 |
| 9004:6178 | 9004:7861 | Adaptec    | AIC-7861                     | 3     | aic7xxx    | 01EAA9281B |
| 9005:0010 | 9005:a180 | Adaptec    | AHA-2940U2/U2W               | 3     | aic7xxx    | F894ABD641 |
| 1000:000f | 1000:1000 | Broadco... | 53c875                       | 2     | sym53c8xx  | AE45AB5C00 |
| 1000:0030 | 1000:50c0 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 2     | mptspi     | 6127AF92BC |
| 1000:0030 | 103c:322a | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 2     | mptspi     | C156F0AB27 |
| 1000:0058 | 1014:0396 | Broadco... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | E4B76F9137 |
| 1000:0058 | 1734:1130 | Broadco... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | 2A000E48F4 |
| 1b85:1041 | 1b85:1041 | OCZ Tec... | RevoDrive 3 X2 PCI-Expres... | 2     | mvsas      | E0FC243F47 |
| 9005:0010 | 9005:2180 | Adaptec    | AHA-2940U2/U2W               | 2     | aic7xxx    | 67C4745D3A |
| 9005:8012 | 9005:0042 | Adaptec    | ASC-29320 U320               | 2     | aic79xx    | 5923C246C4 |
| 9005:8017 | 9005:0044 | Adaptec    | ASC-29320ALP U320            | 2     | aic79xx    | 7483894658 |
| 1000:0030 | 0e11:00f4 | Broadco... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 72330BE67D |
| 1000:0030 | 1014:1000 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 659D759E6D |
| 1000:0030 | 1028:012c | Broadco... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 90378ABAC3 |
| 1000:0030 | 1028:1040 | Broadco... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | D83C8DDEDF |
| 1000:0030 | 103c:3108 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | A2995F5723 |
| 1000:0054 | 103c:3228 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | B4F5FF56BD |
| 1000:0056 | 1014:03bb | LSI Log... | SAS1064ET PCI-Express Fus... | 1     | mptsas     | F45BB4D28D |
| 1000:0056 | 103c:322b | LSI Log... | SAS1064ET PCI-Express Fus... | 1     | mptsas     | 7FE1A5394C |
| 1000:0056 | 1734:1131 | Broadco... | SAS1064ET PCI-Express Fus... | 1     | mptsas     | 4E888D4C51 |
| 1000:0058 | 1000:3002 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | 1E88FE8CBB |
| 1000:0058 | 1000:3140 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | FB13D939DA |
| 1000:0058 | 1028:1f10 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | F3E244219B |
| 1000:0058 | 10f1:2918 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | 032066549F |
| 1000:0058 | 1734:115a | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | AD12D1E2B9 |
| 1000:0058 | 17aa:101d | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | 18BE0454DD |
| 1000:0059 | 1000:3002 | LSI Log... | MegaRAID SAS 8208ELP/8208ELP | 1     | mptsas     | 2985792735 |
| 1022:2020 |           | AMD        | 53c974 [PCscsi]              | 1     | am53c974   | 8DE7A1B6F8 |
| 1095:3110 | 1095:7110 | Silicon... | SCSI storage controller      | 1     |            | 69BD5A45B3 |
| 10cd:1300 |           | Advance... | ASC1300 / ASC3030 [ABP940... | 1     | advansys   | 9072EDAEEF |
| 1101:9400 | 9292:0202 | Initio     | INI-940 Fast Wide SCSI Ad... | 1     | initio     | 121278EA8F |
| 1103:2310 | 11ab:11ab | HighPoi... | RocketRAID 2310 4 Port SA... | 1     | sata_mv    | 353DF9771E |
| 117c:0030 | 117c:8027 | ATTO Te... | Ultra320 SCSI Host Adapter   | 1     | mptspi     | D08EA242AF |
| 1191:8020 | 1191:8020 | Artop E... | AEC6712U SCSI                | 1     | atp870u    | E593748D4E |
| 1191:8040 | 1191:8040 | Artop E... | AEC6712D SCSI                | 1     | atp870u    | DE67919D1B |
| 11ab:6041 | 1043:8150 | Marvell... | MV88SX6041 4-port SATA II... | 1     | sata_mv    | 3FECAFF6C4 |
| 11ab:6081 | 11ab:11ab | Marvell... | MV88SX6081 8-port SATA II... | 1     | sata_mv    | 1F4F0C96FA |
| 11ab:6440 | 11ab:6480 | Marvell... | 88SE6440 SAS/SATA PCIe co... | 1     | mvsas      | EC1EC65380 |
| 11ab:7042 | 11ab:11ab | Marvell... | 88SX7042 PCI-e 4-port SAT... | 1     | sata_mv    | 675FB21B01 |
| 1b85:1221 | 1b85:1221 | OCZ Tec... | OCZ 12xx SCSI Controller     | 1     |            | 323982480D |
| 9004:3860 | 9004:3869 | Adaptec    | AHA-2930CU                   | 1     | aic7xxx    | 7EC632322D |
| 9004:8278 |           | Adaptec    | AHA-3940U/UW/UWD / AIC-7882U | 1     | aic7xxx    | 3A362598FB |
| 9004:8778 | 9004:7887 | Adaptec    | AHA-2940UW Pro / AIC-788x    | 1     | aic7xxx    | E2380E1CCE |
| 9005:0080 | 9005:62a0 | Adaptec    | AIC-7892A U160/m             | 1     | aic7xxx    | 97B51B0912 |
| 9005:0080 | 9005:e2a0 | Adaptec    | AIC-7892A U160/m             | 1     | aic7xxx    | 49D5F9D25E |
| 9005:0081 | 9005:62a1 | Adaptec    | AIC-7892B U160/m             | 1     | aic7xxx    | 9854E43724 |
| 9005:00c0 | 9005:f620 | Adaptec    | AHA-3960D / AIC-7899A U160/m | 1     | aic7xxx    | A966231E0C |
| 9005:00cf | 15d9:9005 | Adaptec    | AIC-7899P U160/m             | 1     | aic7xxx    | 34867AD122 |
| 9005:801d | 10f1:2676 | Adaptec    | AIC-7902B U320               | 1     | aic79xx    | 219383F559 |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1911 | 1458:5000 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 349   |            | F91A20DD51 |
| 8086:2f6e |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 318   |            | B92F4485E6 |
| 8086:2f6f |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 318   |            | B92F4485E6 |
| 8086:2f88 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 318   |            | B92F4485E6 |
| 8086:2f8a |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 318   |            | B92F4485E6 |
| 8086:2fae |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 318   |            | B92F4485E6 |
| 8086:2faf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 318   |            | B92F4485E6 |
| 8086:2fb8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 318   |            | B92F4485E6 |
| 8086:2fb9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 318   |            | B92F4485E6 |
| 8086:2fba |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 318   |            | B92F4485E6 |
| 8086:2fbb |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 318   |            | B92F4485E6 |
| 8086:2fbe |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 318   |            | B92F4485E6 |
| 8086:2fbf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 318   |            | B92F4485E6 |
| 8086:2ff8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 318   |            | B92F4485E6 |
| 8086:2ff9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 318   |            | B92F4485E6 |
| 8086:d150 |           | Intel      | Core Processor QPI Link      | 318   |            | 5EBB861FEB |
| 8086:d151 |           | Intel      | Core Processor QPI Routin... | 318   |            | 5EBB861FEB |
| 8086:d158 |           | Intel      | Core Processor Miscellane... | 318   |            | 5EBB861FEB |
| 8086:2f1d | 8086:2f1d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 288   |            | B92F4485E6 |
| 8086:2f1e | 8086:2f1e | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 288   |            | B92F4485E6 |
| 8086:2f1f | 8086:2f1f | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 288   |            | B92F4485E6 |
| 8086:2f71 | 8086:2f71 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 288   |            | B92F4485E6 |
| 8086:2f98 | 8086:2f98 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 288   |            | B92F4485E6 |
| 8086:2f99 | 8086:2f99 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 288   |            | B92F4485E6 |
| 8086:2f9a | 8086:2f9a | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 288   |            | B92F4485E6 |
| 8086:2f9c | 8086:2f9c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 288   |            | B92F4485E6 |
| 8086:2fa0 | 8086:2fa0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 288   | sb_edac    | B92F4485E6 |
| 8086:2fa8 | 8086:2fa8 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 288   |            | B92F4485E6 |
| 8086:2faa | 8086:2faa | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 288   |            | B92F4485E6 |
| 8086:2fab | 8086:2fab | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 288   |            | B92F4485E6 |
| 8086:2fb0 | 8086:2fb0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 288   | hswep_u... | B92F4485E6 |
| 8086:2fb1 | 8086:2fb1 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 288   | hswep_u... | B92F4485E6 |
| 8086:2fb2 | 8086:2fb2 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 288   |            | B92F4485E6 |
| 8086:2fb3 | 8086:2fb3 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 288   |            | B92F4485E6 |
| 8086:2fc0 | 8086:2fc0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 288   | hswep_u... | B92F4485E6 |
| 8086:2f81 | 8086:2f81 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 257   |            | B92F4485E6 |
| 8086:2fe0 | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 257   |            | B92F4485E6 |
| 8086:2fe1 | 8086:2fe1 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 257   |            | B92F4485E6 |
| 8086:2fe2 | 8086:2fe2 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 257   |            | B92F4485E6 |
| 8086:2fe3 | 8086:2fe3 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 257   |            | B92F4485E6 |
| 8086:2ffc | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 257   |            | B92F4485E6 |
| 8086:2ffd | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 257   |            | B92F4485E6 |
| 8086:2ffe | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 257   |            | B92F4485E6 |
| 8086:2f68 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 246   |            | C050F79E2B |
| 8086:2fd0 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 246   | hswep_u... | C050F79E2B |
| 8086:2576 |           | Intel      | 82865G/PE/P Processor to ... | 241   |            | 52C3157C62 |
| 8086:2fbc |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 241   |            | B92F4485E6 |
| 8086:2fbd |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 241   |            | B92F4485E6 |
| 8086:2fe4 | 8086:2fe4 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 227   |            | B92F4485E6 |
| 8086:2fe5 | 8086:2fe5 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 227   |            | B92F4485E6 |
| 8086:2fac | 8086:2fac | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 224   |            | C050F79E2B |
| 8086:2fad | 8086:2fad | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 224   |            | C050F79E2B |
| 8086:2fb4 | 8086:2fb4 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 224   | hswep_u... | C050F79E2B |
| 8086:2fb5 | 8086:2fb5 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 224   | hswep_u... | C050F79E2B |
| 8086:2fb6 | 8086:2fb6 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 224   |            | C050F79E2B |
| 8086:2fb7 | 8086:2fb7 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 224   |            | C050F79E2B |
| 8086:d156 |           | Intel      | Core Processor Semaphore ... | 185   |            | 5EBB861FEB |
| 8086:2f28 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 182   |            | C050F79E2B |
| 8086:2f29 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 182   |            | C050F79E2B |
| 8086:2f2a |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 182   |            | C050F79E2B |
| 8086:d155 |           | Intel      | Core Processor System Man... | 179   |            | 5EBB861FEB |
| 8086:d157 |           | Intel      | Core Processor System Con... | 179   |            | 5EBB861FEB |
| 8086:d155 | 0043:0083 | Intel      | Core Processor System Man... | 139   |            | 73FAB078B8 |
| 8086:d156 | 0043:0083 | Intel      | Core Processor Semaphore ... | 139   |            | 73FAB078B8 |
| 8086:d157 | 0043:0083 | Intel      | Core Processor System Con... | 139   |            | 73FAB078B8 |
| 8086:3c71 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 131   |            | C6DCB137FB |
| 8086:3c45 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to Q... | 130   | snbep_u... | C6DCB137FB |
| 8086:3cb8 | 8086:0000 | Intel      | Xeon E5/Core i7 DDRIO        | 126   |            | C6DCB137FB |
| 8086:3ce8 | 8086:0000 | Intel      | Xeon E5/Core i7 Unicast R... | 126   |            | C6DCB137FB |
| 8086:3c80 | 8086:0000 | Intel      | Xeon E5/Core i7 QPI Link 0   | 125   |            | C6DCB137FB |
| 8086:3c90 | 8086:0000 | Intel      | Xeon E5/Core i7 QPI Link 1   | 125   |            | C6DCB137FB |
| 8086:3ca8 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 125   | sb_edac    | C6DCB137FB |
| 8086:3caa | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 125   |            | C6DCB137FB |
| 8086:3cab | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 125   |            | C6DCB137FB |
| 8086:3cac | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 125   |            | C6DCB137FB |
| 8086:3cad | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 125   |            | C6DCB137FB |
| 8086:3cae | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 125   |            | C6DCB137FB |
| 8086:3cb0 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 125   | snbep_u... | C6DCB137FB |
| 8086:3cb1 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 125   | snbep_u... | C6DCB137FB |
| 8086:3cb2 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 125   |            | C6DCB137FB |
| 8086:3cb3 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 125   |            | C6DCB137FB |
| 8086:3cb5 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 125   | snbep_u... | C6DCB137FB |
| 8086:3cb6 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 125   |            | C6DCB137FB |
| 8086:3cb7 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 125   |            | C6DCB137FB |
| 8086:3cc0 | 8086:0000 | Intel      | Xeon E5/Core i7 Power Con... | 125   |            | C6DCB137FB |
| 8086:3cc1 | 8086:0000 | Intel      | Xeon E5/Core i7 Power Con... | 125   |            | C6DCB137FB |
| 8086:3cc2 | 8086:0000 | Intel      | Xeon E5/Core i7 Power Con... | 125   |            | C6DCB137FB |
| 8086:3cd0 | 8086:0000 | Intel      | Xeon E5/Core i7 Power Con... | 125   |            | C6DCB137FB |
| 8086:3ce0 | 8086:0000 | Intel      | Xeon E5/Core i7 Interrupt... | 125   |            | C6DCB137FB |
| 8086:3ce3 | 8086:0000 | Intel      | Xeon E5/Core i7 Semaphore... | 125   |            | C6DCB137FB |
| 8086:3ce4 | 8086:0000 | Intel      | Xeon E5/Core i7 R2PCIe       | 125   |            | C6DCB137FB |
| 8086:3c83 | 8086:0000 | Intel      | Xeon E5/Core i7 QPI Link ... | 123   |            | C6DCB137FB |
| 8086:3c84 | 8086:0000 | Intel      | Xeon E5/Core i7 QPI Link ... | 123   |            | C6DCB137FB |
| 8086:3c93 | 8086:0000 | Intel      | Xeon E5/Core i7 QPI Link ... | 123   |            | C6DCB137FB |
| 8086:3c94 | 8086:0000 | Intel      | Xeon E5/Core i7 QPI Link ... | 123   |            | C6DCB137FB |
| 8086:3cf4 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 123   |            | C6DCB137FB |
| 8086:3cf5 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 123   |            | C6DCB137FB |
| 8086:3cf6 | 8086:0000 | Intel      | Xeon E5/Core i7 System Ad... | 123   |            | C6DCB137FB |
| 8086:3ca0 |           | Intel      | Xeon E5/Core i7 Processor... | 121   |            | C6DCB137FB |
| 8086:3cb4 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 117   | snbep_u... | C6DCB137FB |

### Tv card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 109e:036e |           | Brooktree  | Bt878 Video Capture          | 23    | bttv       | E739F2F0BA |
| 1131:7130 | 5ace:5050 | Philips... | SAA7130 Video Broadcast D... | 20    | saa7134    | 34D12D37FD |
| 1131:7133 | 1461:a11b | Philips... | SAA7131/SAA7133/SAA7135 V... | 20    | saa7134    | D9F1062C4A |
| 1131:7133 | 5ace:5090 | Philips... | SAA7131/SAA7133/SAA7135 V... | 19    | saa7134    | F125F4CD03 |
| 1131:7134 | 5ace:5070 | Philips... | SAA7134/SAA7135HL Video B... | 17    | saa7134    | B6FCAC82E8 |
| 4444:0016 | 0070:8801 | Interne... | iTVC16 (CX23416) Video De... | 16    | ivtv       | 37FC7A9D11 |
| 109e:036e | 1461:0003 | Brooktree  | Bt878 Video Capture          | 14    | bttv       | DCE0418111 |
| 1131:7134 | 1461:9715 | Philips... | SAA7134/SAA7135HL Video B... | 14    | saa7134    | BC313E49BE |
| 1131:7133 | 1461:4255 | Philips... | SAA7131/SAA7133/SAA7135 V... | 13    | saa7134    | E32965C387 |
| 1131:7133 | 16be:000d | Philips... | SAA7131/SAA7133/SAA7135 V... | 13    | saa7134    | 91B1729919 |
| 1131:7134 | 185b:c200 | Philips... | SAA7134/SAA7135HL Video B... | 13    | saa7134    | 3BE86AD86B |
| 14f1:8880 | 0070:7801 | Conexan... | CX23887/8 PCIe Broadcast ... | 13    | cx23885    | F1D84C2D34 |
| 1131:7130 | 1131:0000 | Philips... | SAA7130 Video Broadcast D... | 12    | saa7134    | 2C35EE27D9 |
| 14f1:8852 | 0070:7911 | Conexan... | CX23885 PCI Video and Aud... | 12    | cx23885    | 7BED3A3E06 |
| 1131:7130 | 1461:2115 | Philips... | SAA7130 Video Broadcast D... | 10    | saa7134    | 417D975CD9 |
| 1131:7133 | 11bd:002f | Philips... | SAA7131/SAA7133/SAA7135 V... | 10    | saa7134    | 6AB1C423DB |
| 109e:036e | 0070:13eb | Brooktree  | Bt878 Video Capture          | 9     | bttv       | A9C46A46ED |
| 1131:7133 | 0000:4091 | Philips... | SAA7131/SAA7133/SAA7135 V... | 9     | saa7134    | FA070462FC |
| 1131:7133 | 5ace:6090 | Philips... | SAA7131/SAA7133/SAA7135 V... | 9     | saa7134    | 14E5916050 |
| 1131:7133 | 5ace:7290 | Philips... | SAA7131/SAA7133/SAA7135 V... | 9     | saa7134    | 60AB9AF8C6 |
| 1131:7134 | 1131:0000 | Philips... | SAA7134/SAA7135HL Video B... | 9     | saa7134    | 4D5EE48016 |
| 4444:0016 | 1461:c439 | Interne... | iTVC16 (CX23416) Video De... | 9     | ivtv       | 0C38152A55 |
| 1131:7130 | 1461:a11b | Philips... | SAA7130 Video Broadcast D... | 8     | saa7134    | D30442701F |
| 1131:7133 | 1043:4871 | Philips... | SAA7131/SAA7133/SAA7135 V... | 8     | saa7134    | 0B2CF24D70 |
| 1131:7133 | 1461:0155 | Philips... | SAA7131/SAA7133/SAA7135 V... | 8     | saa7134    | 32329B8223 |
| 1131:7133 | 185b:c100 | Philips... | SAA7131/SAA7133/SAA7135 V... | 8     | saa7134    | 5FE1529C55 |
| 1131:7133 | 5ace:7595 | Philips... | SAA7131/SAA7133/SAA7135 V... | 8     | saa7134    | 8CA76C1F85 |
| 1131:7134 | 5168:0138 | Philips... | SAA7134/SAA7135HL Video B... | 8     | saa7134    | 69A029F975 |
| 1131:7134 | 5ace:6070 | Philips... | SAA7134/SAA7135HL Video B... | 8     | saa7134    | 7920A2997E |
| 11de:6057 | 1031:7efe | Zoran      | ZR36057PQC Video cutting ... | 8     | zr36067    | 9D96782463 |
| 14f1:8800 |           | Conexan... | CX23880/1/2/3 PCI Video a... | 8     | cx8800     | 0113CC8AD1 |
| 1131:7133 | 1131:0000 | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 50914BA2F5 |
| 1131:7133 | 11bd:002e | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 548AFBB702 |
| 1131:7133 | 1461:a11a | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 948B6142EC |
| 1131:7133 | 1461:a14b | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 0F5E8185C5 |
| 1131:7133 | 1461:f11d | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 4C528F55F3 |
| 1131:7134 | 16be:0003 | Philips... | SAA7134/SAA7135HL Video B... | 7     | saa7134    | F5D9A3BA0E |
| 14f1:5b7a | 0070:7400 | Conexan... | CX23418 Single-Chip MPEG-... | 7     | cx18       | 925EDCDDDC |
| 14f1:8800 | 107d:6611 | Conexan... | CX23880/1/2/3 PCI Video a... | 7     | cx8800     | ACE5E495F5 |
| 14f1:8852 | 0070:6a28 | Conexan... | CX23885 PCI Video and Aud... | 7     | cx23885    | 517C6137A3 |
| 14f1:8852 | 0070:6b28 | Conexan... | CX23885 PCI Video and Aud... | 7     | cx23885    | 517C6137A3 |
| 109e:036e | 107d:6609 | Brooktree  | Bt878 Video Capture          | 6     | bttv       | 31DFECDF4A |
| 1131:7130 | 5168:0138 | Philips... | SAA7130 Video Broadcast D... | 6     | saa7134    | CE0076FD09 |
| 1131:7133 | 1043:4876 | Philips... | SAA7131/SAA7133/SAA7135 V... | 6     | saa7134    | 79C0025946 |
| 1131:7133 | 1461:0055 | Philips... | SAA7131/SAA7133/SAA7135 V... | 6     | saa7134    | 34AB0FD5ED |
| 1131:7133 | 16be:0010 | Philips... | SAA7131/SAA7133/SAA7135 V... | 6     | saa7134    | C554C3A77F |
| 1131:7133 | 5ace:6193 | Philips... | SAA7131/SAA7133/SAA7135 V... | 6     | saa7134    | 54AB970CAB |
| 1131:7134 | 0000:4071 | Philips... | SAA7134/SAA7135HL Video B... | 6     | saa7134    | 03AE7F53DD |
| 1131:7134 | 4e42:0138 | Philips... | SAA7134/SAA7135HL Video B... | 6     | saa7134    | 4FF5521749 |
| 14f1:8800 | b200:4200 | Conexan... | CX23880/1/2/3 PCI Video a... | 6     | cx8800     | D3A67F88D8 |
| 14f1:8802 | b200:4200 | Conexan... | CX23880/1/2/3 PCI Video a... | 6     | cx8802     | D3A67F88D8 |
| 14f1:8852 | 0070:71d3 | Conexan... | CX23885 PCI Video and Aud... | 6     | cx23885    | 517B7AF416 |
| 14f1:8852 | 4254:0952 | Conexan... | CX23885 PCI Video and Aud... | 6     | cx23885    | 44D5DCA448 |
| 14f1:8880 | 0070:6a28 | Conexan... | CX23887/8 PCIe Broadcast ... | 6     | cx23885    | 240F428975 |
| 14f1:8880 | 0070:6b28 | Conexan... | CX23887/8 PCIe Broadcast ... | 6     | cx23885    | 240F428975 |
| 14f1:8880 | 1461:d439 | Conexan... | CX23887/8 PCIe Broadcast ... | 6     | cx23885    | F9720F4227 |
| 109e:036e | 107d:6606 | Brooktree  | Bt878 Video Capture          | 5     | bttv       | 90F950C23B |
| 109e:036e | 11bd:0012 | Brooktree  | Bt878 Video Capture          | 5     | bttv       | 237CA98302 |
| 109e:036e | 1822:0001 | Brooktree  | Bt878 Video Capture          | 5     | bttv       | 39FB7FBFDD |
| 1131:7130 | 0000:4051 | Philips... | SAA7130 Video Broadcast D... | 5     | saa7134    | 1ABE742CC8 |
| 1131:7133 | 1043:4845 | Philips... | SAA7131/SAA7133/SAA7135 V... | 5     | saa7134    | D288F0A8CD |
| 1131:7134 | 5ace:6072 | Philips... | SAA7134/SAA7135HL Video B... | 5     | saa7134    | DF65A1698B |
| 14f1:8800 | 0070:1402 | Conexan... | CX23880/1/2/3 PCI Video a... | 5     | cx8800     | BC782F5E67 |
| 14f1:8800 | 0070:6902 | Conexan... | CX23880/1/2/3 PCI Video a... | 5     | cx8800     | B2A993FF98 |
| 14f1:8800 | 0070:9002 | Conexan... | CX23880/1/2/3 PCI Video a... | 5     | cx8800     | 1351C7B098 |
| 14f1:8802 | 0070:1402 | Conexan... | CX23880/1/2/3 PCI Video a... | 5     | cx8802     | BC782F5E67 |
| 14f1:8802 | 0070:6902 | Conexan... | CX23880/1/2/3 PCI Video a... | 5     | cx8802     | B2A993FF98 |
| 14f1:8811 | 0070:1402 | Conexan... | CX23880/1/2/3 PCI Video a... | 5     | cx88_alsa  | BC782F5E67 |
| 14f1:8880 | 0070:2259 | Conexan... | CX23887/8 PCIe Broadcast ... | 5     | cx23885    | 573273FC71 |
| 14f1:8880 | 0070:c138 | Conexan... | CX23887/8 PCIe Broadcast ... | 5     | cx23885    | 9D2418F361 |
| 14f1:8880 | 1461:e139 | Conexan... | CX23887/8 PCIe Broadcast ... | 5     | cx23885    | 491D3CFB92 |
| 1131:7130 | 1461:2108 | Philips... | SAA7130 Video Broadcast D... | 4     | saa7134    | 61EF761A70 |
| 1131:7130 | 1461:a115 | Philips... | SAA7130 Video Broadcast D... | 4     | saa7134    | 74B6562CCD |
| 1131:7130 | 1461:a11a | Philips... | SAA7130 Video Broadcast D... | 4     | saa7134    | 0200BA924B |
| 1131:7133 | 0000:5071 | Philips... | SAA7131/SAA7133/SAA7135 V... | 4     | saa7134    | 07314F5868 |
| 1131:7133 | 0070:6701 | Philips... | SAA7131/SAA7133/SAA7135 V... | 4     | saa7134    | DECA40F736 |
| 1131:7133 | 1461:f936 | Philips... | SAA7131/SAA7133/SAA7135 V... | 4     | saa7134    | DA1FD4246E |
| 1131:7133 | 17de:7136 | Philips... | SAA7131/SAA7133/SAA7135 V... | 4     | saa7134    | 6AFFB516F1 |
| 1131:7133 | 5ace:6190 | Philips... | SAA7131/SAA7133/SAA7135 V... | 4     | saa7134    | D48FCDCB03 |
| 1131:7133 | 5ace:7190 | Philips... | SAA7131/SAA7133/SAA7135 V... | 4     | saa7134    | C1BD1568DC |
| 1131:7134 | 11bd:002b | Philips... | SAA7134/SAA7135HL Video B... | 4     | saa7134    | 3993D4BBBC |
| 1131:7134 | 1a7f:2108 | Philips... | SAA7134/SAA7135HL Video B... | 4     | saa7134    | 8BA46DBF50 |
| 14f1:8800 | 0070:9202 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     | cx8800     | 3323601EEF |
| 14f1:8800 | 1002:a101 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     | cx8800     | DA1EA5E754 |
| 14f1:8801 | 0070:9202 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     | cx88_alsa  | 3323601EEF |
| 14f1:8801 | 1002:a101 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     | cx88_alsa  | DA1EA5E754 |
| 14f1:8802 | 0070:9202 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     | cx8802     | 3323601EEF |
| 14f1:8802 | 1002:a101 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     | cx8802     | DA1EA5E754 |
| 14f1:8811 | 0070:6902 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     | cx88_alsa  | B2A993FF98 |
| 14f1:8852 | 8000:3034 | Conexan... | CX23885 PCI Video and Aud... | 4     | cx23885    | 222D827454 |
| 14f1:8880 | 0070:2a18 | Conexan... | CX23887/8 PCIe Broadcast ... | 4     | cx23885    | BCEDC9FAA3 |
| 14f1:8880 | 0070:f038 | Conexan... | CX23887/8 PCIe Broadcast ... | 4     | cx23885    | D0660819A7 |
| 4444:0803 | 0070:4000 | Interne... | iTVC15 (CX23415) Video De... | 4     | ivtv       | 151C6F6C6D |
| 109e:036e | 107d:6607 | Brooktree  | Bt878 Video Capture          | 3     | bttv       | 502C4EB91B |
| 109e:036e | 11bd:001c | Brooktree  | Bt878 Video Capture          | 3     | bttv       | BA214D2A0B |
| 109e:036e | 1554:4011 | Brooktree  | Bt878 Video Capture          | 3     | bttv       | 6E3E7E3E30 |
| 1131:7130 | 107d:6655 | Philips... | SAA7130 Video Broadcast D... | 3     | saa7134    | 1A253FF292 |
| 1131:7130 | 1461:a10a | Philips... | SAA7130 Video Broadcast D... | 3     | saa7134    | 71FC19AA7D |
| 1131:7130 | 1a7f:2008 | Philips... | SAA7130 Video Broadcast D... | 3     | saa7134    | 0C370F7790 |
| 1131:7133 | 16be:0007 | Philips... | SAA7131/SAA7133/SAA7135 V... | 3     | saa7134    | D71CA76FFF |

### Unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:31a2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_i... | E3073F0B11 |
| 8086:5aa2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_i... | 7C30C0C3CA |
| 13fe:1716 | 13fe:0001 | Advantech  |                              | 1     |            | 047EAD1D70 |
| 1684:0029 | 0008:0000 |            |                              | 1     |            | 3A2604A18A |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:43d5 | 1b21:1142 | AMD        | 400 Series Chipset USB 3.... | 1507  | xhci_hcd   | B8D0E81636 |
| 1002:4397 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1330  | ohci_pci   | 77FCB9CF4A |
| 1002:4399 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1330  | ohci_pci   | 77FCB9CF4A |
| 1002:4396 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 1329  | ehci_pci   | 77FCB9CF4A |
| 1b21:1042 | 1043:8488 | ASMedia... | ASM1042 SuperSpeed USB Ho... | 1222  | xhci_hcd   | BA117FEF7E |
| 1022:149c | 1022:148c | AMD        | Matisse USB 3.0 Host Cont... | 1081  | xhci_hcd   | 0619809B36 |
| 1002:4396 | 1002:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 1040  | ehci_pci   | 9F527DED3C |
| 8086:1c26 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1015  | ehci_pci   | EA164260EB |
| 8086:1c2d | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1015  | ehci_pci   | EA164260EB |
| 8086:27c8 | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 1000  | uhci_hcd   | 5889B752F5 |
| 8086:27c9 | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 1000  | uhci_hcd   | 5889B752F5 |
| 8086:27ca | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 999   | uhci_hcd   | 5889B752F5 |
| 8086:27cb | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 998   | uhci_hcd   | 5889B752F5 |
| 8086:27cc | 1043:8179 | Intel      | NM10/ICH7 Family USB2 EHC... | 984   | ehci_hc... | 5889B752F5 |
| 1002:4397 | 1002:4397 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 867   | ohci_pci   | 9F527DED3C |
| 1002:4399 | 1002:4399 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 790   | ohci_pci   | 9F527DED3C |
| 8086:8c26 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 790   | ehci_pci   | 9A23DF55D8 |
| 1002:4396 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 786   | ehci_pci   | 67B53F9BDB |
| 1002:4397 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 786   | ohci_pci   | 67B53F9BDB |
| 8086:8c31 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 785   | xhci_hcd   | 9A23DF55D8 |
| 1002:4398 | 1043:8389 | AMD        | SB7x0 USB OHCI1 Controller   | 784   | ohci_pci   | 67B53F9BDB |
| 1002:4399 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 784   | ohci_pci   | 67B53F9BDB |
| 8086:8c2d | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 779   | ehci_pci   | 9A23DF55D8 |
| 8086:27c8 | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 741   | uhci_hcd   | 43A5D97DD3 |
| 8086:27c9 | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 741   | uhci_hcd   | 43A5D97DD3 |
| 8086:27ca | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 741   | uhci_hcd   | 43A5D97DD3 |
| 8086:27cb | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 741   | uhci_hcd   | 43A5D97DD3 |
| 8086:27cc | 1458:5006 | Intel      | NM10/ICH7 Family USB2 EHC... | 740   | ehci_hc... | 43A5D97DD3 |
| 8086:1e26 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 707   | ehci_pci   | BA117FEF7E |
| 8086:1e2d | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 707   | ehci_pci   | BA117FEF7E |
| 8086:1e31 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 700   | xhci_hcd   | BA117FEF7E |
| 1002:4398 | 1458:5004 | AMD        | SB7x0 USB OHCI1 Controller   | 699   | ohci_pci   | 765CD8D9A0 |
| 1b21:1142 | 1043:85bf | ASMedia... | ASM1042A USB 3.0 Host Con... | 680   | xhci_hcd   | 9F527DED3C |
| 1022:149c | 1043:87c0 | AMD        | Matisse USB 3.0 Host Cont... | 665   | xhci_hcd   | 97C17F738A |
| 1022:149c | 1022:1486 | AMD        | Matisse USB 3.0 Host Cont... | 642   | xhci_hcd   | 0619809B36 |
| 8086:a12f | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 642   | xhci_hcd   | 11EBF0D551 |
| 8086:1c26 | 1458:5006 | Intel      | 6 Series/C200 Series Chip... | 632   | ehci_pci   | EE570B7B0C |
| 8086:1c2d | 1458:5006 | Intel      | 6 Series/C200 Series Chip... | 632   | ehci_pci   | EE570B7B0C |
| 1022:43bb | 1b21:1142 | AMD        | 300 Series Chipset USB 3.... | 602   | xhci_hcd   | 52C67D407D |
| 8086:3a34 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 601   | uhci_hcd   | 2E1659CD91 |
| 8086:3a35 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 601   | uhci_hcd   | 2E1659CD91 |
| 8086:3a36 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 601   | uhci_hcd   | 2E1659CD91 |
| 8086:3a37 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 601   | uhci_hcd   | 2E1659CD91 |
| 8086:3a38 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 601   | uhci_hcd   | 2E1659CD91 |
| 8086:3a39 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 601   | uhci_hcd   | 2E1659CD91 |
| 8086:3a3a | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 601   | ehci_hc... | 2E1659CD91 |
| 8086:3a3c | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 601   | ehci_hc... | 2E1659CD91 |
| 8086:1e26 | 1458:5006 | Intel      | 7 Series/C216 Chipset Fam... | 531   | ehci_pci   | 89F6EB0671 |
| 8086:1e2d | 1458:5006 | Intel      | 7 Series/C216 Chipset Fam... | 531   | ehci_pci   | 89F6EB0671 |
| 1b6f:7023 | 1458:5007 | Etron T... | EJ168 USB 3.0 Host Contro... | 523   | xhci_hcd   | 77FCB9CF4A |
| 1b21:1242 | 1043:8675 | ASMedia... | ASM1142 USB 3.1 Host Cont... | 521   | xhci_hcd   | 97C17F738A |
| 1106:3483 | 1106:3483 | VIA Tec... | VL805/806 xHCI USB 3.0 Co... | 510   | xhci_hcd   | A0D316EB3E |
| 8086:8c26 | 1458:5006 | Intel      | 8 Series/C220 Series Chip... | 508   | ehci_pci   | E187B3F207 |
| 8086:8c2d | 1458:5006 | Intel      | 8 Series/C220 Series Chip... | 508   | ehci_pci   | E187B3F207 |
| 1022:43bc | 1b21:1142 | AMD        | FCH USB 3.1 XHCI Host Con... | 506   | xhci_hcd   | 4654691B7A |
| 8086:8c31 | 1458:5007 | Intel      | 8 Series/C220 Series Chip... | 506   | xhci_hcd   | E187B3F207 |
| 1106:3483 | 1458:5007 | VIA Tec... | VL805/806 xHCI USB 3.0 Co... | 502   | xhci_hcd   | 84D927D279 |
| 8086:1e31 | 1458:5007 | Intel      | 7 Series/C210 Series Chip... | 496   | xhci_hcd   | 89F6EB0671 |
| 1002:4396 | 1849:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 495   | ehci_pci   | 0A228B18C1 |
| 1002:4397 | 1849:4397 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 495   | ohci_pci   | 0A228B18C1 |
| 1002:4399 | 1849:4399 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 495   | ohci_pci   | 0A228B18C1 |
| 1022:149c | 1458:5007 | AMD        | Matisse USB 3.0 Host Cont... | 483   | xhci_hcd   | 06BB083E38 |
| 8086:27c8 | 1849:27c8 | Intel      | NM10/ICH7 Family USB UHCI... | 445   | uhci_hcd   | 87C40FCD51 |
| 8086:27c9 | 1849:27c9 | Intel      | NM10/ICH7 Family USB UHCI... | 445   | uhci_hcd   | 87C40FCD51 |
| 8086:27ca | 1849:27ca | Intel      | NM10/ICH7 Family USB UHCI... | 445   | uhci_hcd   | 87C40FCD51 |
| 8086:27cb | 1849:27cb | Intel      | NM10/ICH7 Family USB UHCI... | 445   | uhci_hcd   | 87C40FCD51 |
| 8086:27cc | 1849:27cc | Intel      | NM10/ICH7 Family USB2 EHC... | 444   | ehci_hc... | 87C40FCD51 |
| 1022:7808 | 1458:5004 | AMD        | FCH USB EHCI Controller      | 424   | ehci_pci   | E03FD39AD4 |
| 1022:7807 | 1458:5004 | AMD        | FCH USB OHCI Controller      | 420   | ohci_pci   | E03FD39AD4 |
| 1022:43ee | 1b21:1142 | AMD        | Starship/Matisse USB 3.0 ... | 416   | xhci_hcd   | A82D785D77 |
| 1033:0194 | 1043:8413 | NEC Com... | uPD720200 USB 3.0 Host Co... | 412   | xhci_hcd   | 67B53F9BDB |
| 1022:7809 | 1458:5004 | AMD        | FCH USB OHCI Controller      | 399   | ohci_pci   | E03FD39AD4 |
| 10de:03f1 | 1849:03f1 | Nvidia     | MCP61 USB 1.1 Controller     | 397   | ohci_pci   | 615502E93E |
| 10de:03f2 | 1849:03f2 | Nvidia     | MCP61 USB 2.0 Controller     | 397   | ehci_pci   | 615502E93E |
| 8086:a2af | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 390   | xhci_hcd   | 2696477C0C |
| 1106:3038 | 1106:3038 | VIA Tec... | VT82xx/62xx/VX700/8x0/900... | 385   | uhci_hcd   | 37BC060302 |
| 1022:43d0 | 1b21:1142 | AMD        | FCH USB 3.1 XHCI Host Con... | 383   | xhci_hcd   | 97C17F738A |
| 1106:3104 | 1106:3104 | VIA Tec... | USB 2.0 EHCI-Compliant Ho... | 381   | ehci_pci   | 37BC060302 |
| 1022:145f | 1043:8747 | AMD        | Zeppelin USB 3.0 Host con... | 379   | xhci_hcd   | 115EC5ECA4 |
| 8086:a2af | 1458:5007 | Intel      | 200 Series/Z370 Chipset F... | 364   | xhci_hcd   | F91A20DD51 |
| 8086:a12f | 1458:5007 | Intel      | 100 Series/C230 Series Ch... | 358   | xhci_hcd   | 213A5CCCC3 |
| 8086:2934 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 357   | uhci_hcd   | 4F6DEFB975 |
| 8086:2935 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 357   | uhci_hcd   | 4F6DEFB975 |
| 8086:2936 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 357   | uhci_hcd   | 4F6DEFB975 |
| 8086:2937 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 357   | uhci_hcd   | 4F6DEFB975 |
| 8086:2938 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 357   | uhci_hcd   | 4F6DEFB975 |
| 8086:2939 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 357   | uhci_hcd   | 4F6DEFB975 |
| 8086:293a | 1043:8277 | Intel      | 82801I (ICH9 Family) USB2... | 357   | ehci_hc... | 4F6DEFB975 |
| 8086:293c | 1043:8277 | Intel      | 82801I (ICH9 Family) USB2... | 357   | ehci_hc... | 4F6DEFB975 |
| 1022:145c | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 345   | xhci_hcd   | DFE212DA86 |
| 1022:43b9 | 1b21:1142 | AMD        | X370 Series Chipset USB 3... | 338   | xhci_hcd   | F544511E0A |
| 1022:7807 | 1849:7807 | AMD        | FCH USB OHCI Controller      | 332   | ohci_pci   | 3D65247771 |
| 1022:7808 | 1849:7808 | AMD        | FCH USB EHCI Controller      | 332   | ehci_pci   | 3D65247771 |
| 1022:145f | 1458:5007 | AMD        | Zeppelin USB 3.0 Host con... | 313   | xhci_hcd   | D88D9DB618 |
| 1022:7809 | 1849:7809 | AMD        | FCH USB OHCI Controller      | 304   | ohci_hc... | 3D65247771 |
| 8086:a36d | 1043:8694 | Intel      | Cannon Lake PCH USB 3.1 x... | 301   | xhci_hcd   | 36EBF65D44 |
| 8086:8ca6 | 1043:8534 | Intel      | 9 Series Chipset Family U... | 290   | ehci_pci   | 0D40DAA834 |
| 8086:8cb1 | 1043:8534 | Intel      | 9 Series Chipset Family U... | 289   | xhci_hcd   | 0D40DAA834 |
| 8086:8cad | 1043:8534 | Intel      | 9 Series Chipset Family U... | 282   | ehci_pci   | 0D40DAA834 |
| 1022:15e0 | 1458:5007 | AMD        | Raven USB 3.1                | 278   | xhci_hcd   | F544511E0A |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8d7c | 1043:8600 | Intel      | C610/X99 series chipset SPSR | 96    |            | E456864B06 |
| 8086:8d7c | 8086:7270 | Intel      | C610/X99 series chipset SPSR | 53    |            | B92F4485E6 |
| 8086:8d7c | 1849:8d7c | Intel      | C610/X99 series chipset SPSR | 38    |            | 6FEB0AEC47 |
| 8086:8d7c | 1458:7270 | Intel      | C610/X99 series chipset SPSR | 37    |            | 0C74B85F4C |
| 8086:8d7c | 1462:7885 | Intel      | C610/X99 series chipset SPSR | 31    |            | 09B0FBCF47 |
| 8086:8d7c | 1028:0617 | Intel      | C610/X99 series chipset SPSR | 26    |            | 3440F55127 |
| 8086:8d7c | 103c:212b | Intel      | C610/X99 series chipset SPSR | 26    |            | 69F0D916A3 |
| 10ec:816e | 10ec:8168 | Realtek... | RealManage BMC               | 16    |            | 6E60025AC5 |
| 1af2:a001 | 1af2:a001 | AVerMedia  | Live Gamer HD                | 13    |            | 8FFB0CF94A |
| 8086:8d7c | 1043:85f6 | Intel      | C610/X99 series chipset SPSR | 13    |            | C624F64EDE |
| 8086:8d7c | 1028:0618 | Intel      | C610/X99 series chipset SPSR | 11    |            | 7172CF4F40 |
| 8086:8d7c | 103c:2129 | Intel      | C610/X99 series chipset SPSR | 8     |            | 3991895525 |
| 8086:8d7c | 1028:061b | Intel      | C610/X99 series chipset SPSR | 7     |            | BCD33A41F0 |
| 8086:8d7c | 1028:064c | Intel      | C610/X99 series chipset SPSR | 6     |            | E31C5F36AA |
| 8086:8d7c | 1028:0619 | Intel      | C610/X99 series chipset SPSR | 5     |            | F96F352657 |
| 8086:8d7c | 1734:1201 | Intel      | C610/X99 series chipset SPSR | 5     |            | 081130AC6F |
| 8086:8d7c | 17aa:102f | Intel      | C610/X99 series chipset SPSR | 5     |            | 4860ACD042 |
| 8086:8d7c | 15d9:0836 | Intel      | C610/X99 series chipset SPSR | 4     |            | 3EFBED680C |
| 8086:8d7c | 103c:212a | Intel      | C610/X99 series chipset SPSR | 3     |            | 90CE777D83 |
| 8086:8d7c | 1462:7883 | Intel      | C610/X99 series chipset SPSR | 3     |            | 64A313C9E3 |
| 8086:8d7c | 1462:7a20 | Intel      | C610/X99 series chipset SPSR | 3     |            | B5DCAF3853 |
| 1274:5880 | ffff:ffff | Ensoniq    | 5880B / Creative Labs CT5880 | 2     | snd_ens... | CC0925A796 |
| 8086:3591 | 1043:8145 | Intel      | E7525/E7520 Error Reporti... | 2     |            | C6EF12178F |
| 8086:6ff2 | 8086:6ff2 | Intel      | Broadwell-E CBo Unicast R... | 2     |            | 2C3CA5276B |
| 8086:6ff3 | 8086:6ff3 | Intel      | Broadwell-E CBo Unicast R... | 2     |            | 2C3CA5276B |
| 8086:8d7c | 103c:8030 | Intel      | C610/X99 series chipset SPSR | 2     |            | D9B1EC3C37 |
| 8086:8d7c | 1462:7a21 | Intel      | C610/X99 series chipset SPSR | 2     |            | 6FAF6514F5 |
| 8086:8d7c | 15d9:0852 | Intel      | C610/X99 series chipset SPSR | 2     |            | 8A8EA3FF31 |
| 8086:a1ec | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 2     |            | 0C434691D6 |
| 8086:a1ec | 1043:871e | Intel      | C620 Series Chipset Famil... | 2     |            | 177BF1F346 |
| 8086:a1ed | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 2     |            | 0C434691D6 |
| 0000:0000 | 8005:0000 |            |                              | 1     |            | 77F07D2D69 |
| 0000:0002 | 1105:8300 |            |                              | 1     |            | 3859A12973 |
| 0018:fd00 | 0115:0000 |            |                              | 1     |            | 67CBAFF497 |
| 0274:0371 | 0274:0371 |            |                              | 1     |            | E579695CC9 |
| 1000:fury | 1000:9343 | Broadco... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 29B0070304 |
| 102f:0181 | 102f:c600 | Toshiba... | TX4925 MIPS RISC PCI Cont... | 1     |            | 245D0631CE |
| 1045:c861 | 0045:8000 | OPTi       | 82C861 OHCI USB Host         | 1     | ohci-pci   | 806796F01E |
| 104c:8024 | 0020:0000 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 1     | firewir... | F5C15B4975 |
| 106b:0022 |           | Apple      | KeyLargo Mac I/O             | 1     | macio      | 23A8F5BBFB |
| 106b:0033 |           | Apple      | UniNorth 2 ATA/100           | 1     | pata_pc... | 23A8F5BBFB |
| 106b:003b |           | Apple      | UniNorth/Intrepid ATA/100    | 1     | pata_pc... | 47DE429737 |
| 106b:003e |           | Apple      | KeyLargo/Intrepid Mac I/O    | 1     | macio      | 47DE429737 |
| 106b:0041 |           | Apple      | K2 KeyLargo Mac/IO           | 1     | macio      | 52B4B037A1 |
| 106b:0043 |           | Apple      | K2 ATA/100                   | 1     | pata_pc... | 52B4B037A1 |
| 106b:004f |           | Apple      | Shasta Mac I/O               | 1     | macio      | 978FCB3A51 |
| 106b:0050 |           | Apple      | Shasta IDE                   | 1     | ide_pmac   | 978FCB3A51 |
| 1093:2a70 |           | Nationa... | PCI-6024E                    | 1     | ni_pcimio  | FB5BC9ACCE |
| 10b5:9050 | 14a0:0007 | PLX Tec... | PCI <-> IOBus Bridge         | 1     |            | 1A8280D068 |
| 1106:3038 | ffff:ffff | VIA Tec... | VT82xx/62xx/VX700/8x0/900... | 1     |            | 84FEB3D2F6 |
| 1131:7146 | ffff:ffff | Philips... | SAA7146                      | 1     |            | 4893225F50 |
| 1186:4300 | ffff:ffff | D-Link ... | DGE-528T Gigabit Ethernet... | 1     | r8169      | 5C0883B543 |
| 125b:9100 | a000:6000 | Asix El... | AX99100 PCIe to Multi I/O... | 1     |            | 9E8C70813F |
| 127a:2014 | 144e:2014 | Rockwel... | HSF 56k Data/Fax/Voice Modem | 1     |            | 97FF18DC78 |
| 1306:3038 | ffff:ffff | Duet Te... |                              | 1     |            | 84FEB3D2F6 |
| 13f6:0111 | 5b7f:ce5f | C-Media... | CMI8738/CMI8768 PCI Audio    | 1     | snd_cmipci | 76442678ED |
| 13f6:0111 | fbff:fffd | C-Media... | CMI8738/CMI8768 PCI Audio    | 1     | snd_cmipci | 0528AB77BE |
| 13f6:8788 | ffff:ffff | C-Media... | CMI8788 [Oxygen HD Audio]    | 1     |            | 306E5B04F7 |
| 13fe:1751 | 10b5:9050 | Advantech  |                              | 1     | adv_pci... | 55AA9109DD |
| 144a:5101 | 144a:5101 | ADLINK ... |                              | 1     |            | E0E966D6B4 |
| 149d:0102 | 149d:0000 | NEWTEK     |                              | 1     |            | 2ACD2A0345 |
| 14f1:2520 | 14f1:200c | Conexan... |                              | 1     |            | 0FDFB3FCBF |
| 168c:001a | ffff:ffff | Qualcom... | AR2413/AR2414 Wireless Ne... | 1     | ath5k      | 64ADED4262 |
| 17b6:0229 | 17b6:0000 | GE Medi... |                              | 1     |            | 6127AF92BC |
| 17b6:2000 | 17b6:0003 | GE Medi... |                              | 1     |            | 71678F1D6B |
| 1931:1011 | 1003:0001 | Option ... |                              | 1     |            | 28DFB478B7 |
| 1931:1011 | 1043:0001 | Option ... |                              | 1     |            | 28DFB478B7 |
| 1b21:1042 | ffff:ffff | ASMedia... | ASM1042 SuperSpeed USB Ho... | 1     |            | 03FD0C20FB |
| 1fc8:0be0 |           | Lucid I... | HYDRA 200                    | 1     |            | F24106BC34 |
| 8037:cf10 | f377:afbd |            |                              | 1     |            | E02C86805F |
| 8086:2541 | 15d9:3780 | Intel      | E7500/E7501 Host RASUM Co... | 1     |            | 34867AD122 |
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
| 8086:3591 | 1028:0173 | Intel      | E7525/E7520 Error Reporti... | 1     |            | 4D032C236B |
| 8086:3591 | 8086:345c | Intel      | E7525/E7520 Error Reporti... | 1     |            | 727097891C |
| 8086:3593 | 8086:345e | Intel      | E7320 Error Reporting Reg... | 1     |            | 97CC3C4274 |
| 8086:6ff2 | 103c:21ea | Intel      | Broadwell-E CBo Unicast R... | 1     |            | D9B1EC3C37 |
| 8086:6ff2 | 1849:6ff2 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 87D6B1C03E |
| 8086:6ff3 | 103c:21ea | Intel      | Broadwell-E CBo Unicast R... | 1     |            | D9B1EC3C37 |
| 8086:6ff3 | 1849:6ff3 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 87D6B1C03E |
| 8086:6ff4 | 103c:21ea | Intel      | Broadwell-E CBo Unicast R... | 1     |            | D9B1EC3C37 |
| 8086:6ff4 | 1849:6ff4 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 87D6B1C03E |
| 8086:6ff4 | 8086:6ff4 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 2C3CA5276B |
| 8086:6ff5 | 103c:21ea | Intel      | Broadwell-E CBo Unicast R... | 1     |            | D9B1EC3C37 |
| 8086:6ff5 | 1849:6ff5 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 87D6B1C03E |

