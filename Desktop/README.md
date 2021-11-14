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
| 1814:3298 | 103c:18ec | Ralink     | RT3290 Bluetooth             | 19    | rtbt       | E5EDE0905A |
| 1814:3298 | 1a3b:2787 | Ralink     | RT3290 Bluetooth             | 4     |            | 375A7150DE |
| 1814:3298 | 103c:191c | Ralink     | RT3290 Bluetooth             | 1     |            | 3CF5084317 |
| 1814:3298 | 1814:3298 | Ralink     | RT3290 Bluetooth             | 1     |            | EF1E6295A8 |
| 1814:3298 | 1a3b:2987 | Ralink     | RT3290 Bluetooth             | 1     |            | 1D26C2B648 |

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:4384 |           | AMD        | SBx00 PCI to PCI Bridge      | 5454  |            | 588CEFB67B |
| 1022:1452 |           | AMD        | Family 17h (Models 00h-1f... | 3887  |            | 24974BE67E |
| 1022:1200 |           | AMD        | Family 10h Processor Hype... | 3678  |            | 324F6E5FAD |
| 1022:1201 |           | AMD        | Family 10h Processor Addr... | 3678  |            | 324F6E5FAD |
| 1022:1202 |           | AMD        | Family 10h Processor DRAM... | 3678  | amd64_e... | 324F6E5FAD |
| 1022:1203 |           | AMD        | Family 10h Processor Misc... | 3678  | k10temp    | 324F6E5FAD |
| 1022:1204 |           | AMD        | Family 10h Processor Link... | 3678  |            | 324F6E5FAD |
| 1022:1482 |           | AMD        | Starship/Matisse PCIe Dum... | 2906  | vfio_pci   | C537345CE8 |
| 1022:1440 |           | AMD        | Matisse Device 24: Functi... | 2804  |            | C537345CE8 |
| 1022:1441 |           | AMD        | Matisse Device 24: Functi... | 2804  |            | C537345CE8 |
| 1022:1442 |           | AMD        | Matisse Device 24: Functi... | 2804  |            | C537345CE8 |
| 1022:1443 |           | AMD        | Matisse Device 24: Functi... | 2804  | k10temp    | C537345CE8 |
| 1022:1444 |           | AMD        | Matisse Device 24: Functi... | 2804  |            | C537345CE8 |
| 1022:1445 |           | AMD        | Matisse Device 24: Functi... | 2804  |            | C537345CE8 |
| 1022:1446 |           | AMD        | Matisse Device 24: Functi... | 2804  |            | C537345CE8 |
| 1022:1447 |           | AMD        | Matisse Device 24: Functi... | 2804  |            | C537345CE8 |
| 1022:1460 |           | AMD        | Family 17h (Models 00h-0f... | 2663  |            | E52E9002D0 |
| 1022:1461 |           | AMD        | Family 17h (Models 00h-0f... | 2663  |            | E52E9002D0 |
| 1022:1462 |           | AMD        | Family 17h (Models 00h-0f... | 2663  |            | E52E9002D0 |
| 1022:1463 |           | AMD        | Family 17h (Models 00h-0f... | 2663  | k10temp    | E52E9002D0 |
| 1022:1464 |           | AMD        | Family 17h (Models 00h-0f... | 2663  |            | E52E9002D0 |
| 1022:1465 |           | AMD        | Family 17h (Models 00h-0f... | 2663  |            | E52E9002D0 |
| 1022:1466 |           | AMD        | Family 17h (Models 00h-0f... | 2663  |            | E52E9002D0 |
| 1022:1467 |           | AMD        | Family 17h (Models 00h-0f... | 2663  |            | E52E9002D0 |
| 1022:43c7 | 1b21:3306 | AMD        | 400 Series Chipset PCIe Port | 2574  | pcieport   | C537345CE8 |
| 1022:1600 |           | AMD        | Family 15h Processor Func... | 2454  |            | 588CEFB67B |
| 1022:1601 |           | AMD        | Family 15h Processor Func... | 2454  |            | 588CEFB67B |
| 1022:1602 |           | AMD        | Family 15h Processor Func... | 2454  |            | 588CEFB67B |
| 1022:1603 |           | AMD        | Family 15h Processor Func... | 2454  | k10temp    | 588CEFB67B |
| 1022:1604 |           | AMD        | Family 15h Processor Func... | 2454  | fam15h_... | 588CEFB67B |
| 1022:1605 |           | AMD        | Family 15h Processor Func... | 2454  |            | 588CEFB67B |
| 1022:43c6 | 1b21:0201 | AMD        | 400 Series Chipset PCIe B... | 2327  | pcieport   | C537345CE8 |
| 1002:439d | 1002:439d | AMD        | SB7x0/SB8x0/SB9x0 LPC hos... | 2312  |            | 588CEFB67B |
| 1022:43b4 | 1b21:3306 | AMD        | 300 Series Chipset PCIe Port | 2089  | pcieport   | 24974BE67E |
| 1022:1484 | 1022:1484 | AMD        | Starship/Matisse Internal... | 2025  | pcieport   | C537345CE8 |
| 1022:1454 | 1022:1454 | AMD        | Family 17h (Models 00h-0f... | 1875  | pcieport   | E52E9002D0 |
| 1022:780f |           | AMD        | FCH PCI Bridge               | 1817  |            | 42CD4D28BD |
| 1022:1100 |           | AMD        | K8 [Athlon64/Opteron] Hyp... | 1736  |            | F9BFF20C4D |
| 1022:1101 |           | AMD        | K8 [Athlon64/Opteron] Add... | 1736  |            | F9BFF20C4D |
| 1022:1102 |           | AMD        | K8 [Athlon64/Opteron] DRA... | 1736  | amd64_e... | F9BFF20C4D |
| 1022:1103 |           | AMD        | K8 [Athlon64/Opteron] Mis... | 1736  | k8temp     | F9BFF20C4D |
| 1022:790e | 1458:5001 | AMD        | FCH LPC Bridge               | 1710  |            | E52E9002D0 |
| 8086:244e | 1458:5000 | Intel      | 82801 PCI Bridge             | 1702  |            | 40C84C9637 |
| 1b21:1080 | 1043:8489 | ASMedia... | ASM1083/1085 PCIe to PCI ... | 1583  | shpchp     | 278873FF66 |
| 1022:1453 | 1022:1453 | AMD        | Family 17h (Models 00h-0f... | 1525  | pcieport   | E52E9002D0 |
| 1002:43a0 | 1002:0000 | AMD        | SB700/SB800/SB900 PCI to ... | 1436  | pcieport   | 21C683ED97 |
| 1022:57ad |           | AMD        | Matisse Switch Upstream      | 1407  | pcieport   | 93DE1508CB |
| 8086:1901 | 1043:8694 | Intel      | 6th-10th Gen Core Process... | 1252  | pcieport   | 427C8B8D8F |
| 1002:5a14 | 1002:5a14 | AMD        | RD9x0/RX980 Host Bridge      | 1242  | ati_agp    | 588CEFB67B |
| 8086:0c01 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 1232  | pcieport   | 735015DCE2 |
| 1022:15e8 |           | AMD        | Raven/Raven2 Device 24: F... | 1229  |            | 24974BE67E |
| 1022:15e9 |           | AMD        | Raven/Raven2 Device 24: F... | 1229  |            | 24974BE67E |
| 1022:15ea |           | AMD        | Raven/Raven2 Device 24: F... | 1229  |            | 24974BE67E |
| 1022:15eb |           | AMD        | Raven/Raven2 Device 24: F... | 1229  | k10temp    | 24974BE67E |
| 1022:15ec |           | AMD        | Raven/Raven2 Device 24: F... | 1229  |            | 24974BE67E |
| 1022:15ed |           | AMD        | Raven/Raven2 Device 24: F... | 1229  |            | 24974BE67E |
| 1022:15ee |           | AMD        | Raven/Raven2 Device 24: F... | 1229  |            | 24974BE67E |
| 1022:15ef |           | AMD        | Raven/Raven2 Device 24: F... | 1229  |            | 24974BE67E |
| 8086:0c00 | 1043:8534 | Intel      | 4th Gen Core Processor DR... | 1221  | hsw_uncore | 735015DCE2 |
| 1002:5a16 | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 1205  | pcieport   | 588CEFB67B |
| 8086:1c10 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1132  | pcieport   | 278873FF66 |
| 1002:5a18 | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 1127  | pcieport   | 588CEFB67B |
| 1022:1483 | 1022:1453 | AMD        | Starship/Matisse GPP Bridge  | 1123  | pcieport   | C537345CE8 |
| 8086:244e | 1043:8179 | Intel      | 82801 PCI Bridge             | 1071  |            | 4E4E73BA37 |
| 8086:27b8 | 1043:8179 | Intel      | 82801GB/GR (ICH7 Family) ... | 1070  | lpc_ich    | 4E4E73BA37 |
| 8086:244e |           | Intel      | 82801 PCI Bridge             | 1050  | shpchp     | 7CA61CA6E1 |
| 8086:27d0 | 1043:8179 | Intel      | NM10/ICH7 Family PCI Expr... | 1050  | shpchp     | 4E4E73BA37 |
| 1022:57a4 | 1022:1484 | AMD        | Matisse PCIe GPP Bridge      | 1042  | pcieport   | 93DE1508CB |
| 1022:1400 |           | AMD        | Family 15h (Models 10h-1f... | 1011  |            | 42CD4D28BD |
| 1022:1401 |           | AMD        | Family 15h (Models 10h-1f... | 1011  |            | 42CD4D28BD |
| 1022:1402 |           | AMD        | Family 15h (Models 10h-1f... | 1011  |            | 42CD4D28BD |
| 1022:1403 |           | AMD        | Family 15h (Models 10h-1f... | 1011  | k10temp    | 42CD4D28BD |
| 1022:1404 |           | AMD        | Family 15h (Models 10h-1f... | 1011  |            | 42CD4D28BD |
| 1022:1405 |           | AMD        | Family 15h (Models 10h-1f... | 1011  |            | 42CD4D28BD |
| 8086:244e | 1458:8892 | Intel      | 82801 PCI Bridge             | 964   |            | 5EAD0CA3AD |
| 1022:1483 | 1022:1234 | AMD        | Starship/Matisse GPP Bridge  | 946   | pcieport   | 60FFB9D428 |
| 8086:244e | 1849:244e | Intel      | 82801 PCI Bridge             | 924   | pcieport   | 16C678627E |
| 1002:1478 |           | AMD        | Navi 10 XL Upstream Port ... | 913   | pcieport   | C537345CE8 |
| 1002:1479 | 1002:1479 | AMD        | Navi 10 XL Downstream Por... | 912   | pcieport   | C537345CE8 |
| 1022:790e | 1043:87c0 | AMD        | FCH LPC Bridge               | 910   |            | A525C8911B |
| 1022:15db | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 877   | pcieport   | B2D3620851 |
| 1022:43a0 | 1022:0000 | AMD        | Hudson PCI to PCI bridge ... | 876   | pcieport   | 0AC8E061F1 |
| 8086:8c10 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 870   | pcieport   | 735015DCE2 |
| 1022:1450 | 1022:1450 | AMD        | Family 17h (Models 00h-0f... | 866   |            | E52E9002D0 |
| 1002:439d | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 LPC hos... | 860   |            | 6CA4F46D1B |
| 8086:1901 | 1458:5000 | Intel      | 6th-10th Gen Core Process... | 837   | pcieport   | 36BF6DAB37 |
| 1022:790e | 1043:8747 | AMD        | FCH LPC Bridge               | 836   |            | 491D1A96CC |
| 8086:0c00 | 1458:5000 | Intel      | 4th Gen Core Processor DR... | 836   | hsw_uncore | 5EAD0CA3AD |
| 1022:1453 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 832   | pcieport   | 491D1A96CC |
| 1022:1450 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 828   | ryzen_smu  | 491D1A96CC |
| 8086:27d2 | 1043:8179 | Intel      | NM10/ICH7 Family PCI Expr... | 828   | shpchp     | 4E4E73BA37 |
| 1022:57a3 | 1022:1453 | AMD        | Matisse PCIe GPP Bridge      | 824   | pcieport   | 93DE1508CB |
| 8086:0101 | 1043:844d | Intel      | Xeon E3-1200/2nd Generati... | 799   | pcieport   | 278873FF66 |
| 8086:0100 | 1043:844d | Intel      | 2nd Generation Core Proce... | 794   | snb_uncore | 278873FF66 |
| 8086:27b8 | 1458:5001 | Intel      | 82801GB/GR (ICH7 Family) ... | 788   | lpc_ich    | 5AF4FEE0BA |
| 8086:244e | 1458:5001 | Intel      | 82801 PCI Bridge             | 786   | pcieport   | CE787D81EF |
| 1022:15dc | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 782   | pcieport   | DA176384C5 |
| 8086:1e10 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 777   | shpchp     | 1575E2C682 |
| 8086:1c1a | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 756   | shpchp     | 278873FF66 |
| 8086:a118 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 753   | pcieport   | 427C8B8D8F |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:522a | 1458:1000 | Realtek... | RTS522A PCI Express Card ... | 24    | rtsx_pci   | 8B88D7AB23 |
| 10ec:525a | 1028:07ee | Realtek... | RTS525A PCI Express Card ... | 13    | rtsx_pci   | 5256B07A63 |
| 10ec:5209 | 103c:2ac3 | Realtek... | RTS5209 PCI Express Card ... | 11    | rtsx_pci   | AE8B02D9CB |
| 10ec:5229 | 103c:2b38 | Realtek... | RTS5229 PCI Express Card ... | 10    | rtsx_pci   | 2CF327F158 |
| 10ec:5209 | 103c:2adc | Realtek... | RTS5209 PCI Express Card ... | 9     | rtsx_pci   | 48CC7F548E |
| 10ec:525a | 1734:122e | Realtek... | RTS525A PCI Express Card ... | 9     | rtsx_pci   | CF3B2F2089 |
| 10ec:5209 | 103c:2af0 | Realtek... | RTS5209 PCI Express Card ... | 8     | rtsx_pci   | 54077E8D9B |
| 10ec:5229 | 17aa:366b | Realtek... | RTS5229 PCI Express Card ... | 8     | rtsx_pci   | C3D601D88E |
| 10ec:5209 | 103c:3399 | Realtek... | RTS5209 PCI Express Card ... | 6     | rtsx_pci   | A249F36019 |
| 10ec:5289 | 10ec:5289 | Realtek... | RTL8411 PCI Express Card ... | 6     | rtsx_pci   | 11240C3F0F |
| 10ec:5229 | 103c:2b43 | Realtek... | RTS5229 PCI Express Card ... | 5     | rtsx_pci   | 990D8BAE5E |
| 10ec:525a | 10ec:525a | Realtek... | RTS525A PCI Express Card ... | 5     | rtsx_pci   | 2C4113A15A |
| 10ec:5209 | 103c:2ac5 | Realtek... | RTS5209 PCI Express Card ... | 4     | rtsx_pci   | 07FE8046CF |
| 10ec:5229 | 1b0a:016c | Realtek... | RTS5229 PCI Express Card ... | 4     | rtsx_pci   | 0DF79259C1 |
| 10ec:522a | 10ec:522a | Realtek... | RTS522A PCI Express Card ... | 4     | rtsx_pci   | 39F04EC538 |
| 1aea:6621 | 1aea:6621 | Alcor M... | AU6621 PCI-E Flash card r... | 4     | alcor_pci  | 867B1F5318 |
| 10ec:5209 | 1025:8020 | Realtek... | RTS5209 PCI Express Card ... | 3     | rtsx_pci   | BEB207E679 |
| 10ec:5209 | 17aa:3623 | Realtek... | RTS5209 PCI Express Card ... | 3     | rtsx_pci   | E5E08BD1ED |
| 10ec:5229 | 103c:2afa | Realtek... | RTS5229 PCI Express Card ... | 3     | rtsx_pci   | ACC18F350E |
| 10ec:5229 | 103c:2b3c | Realtek... | RTS5229 PCI Express Card ... | 3     | rtsx_pci   | 5E60EFC4A4 |
| 10ec:5209 | 103c:2ae9 | Realtek... | RTS5209 PCI Express Card ... | 2     | rtsx_pci   | 2F1276F263 |
| 10ec:5209 | 103c:2aed | Realtek... | RTS5209 PCI Express Card ... | 2     | rtsx_pci   | FFEE72581F |
| 10ec:5209 | 103c:2aee | Realtek... | RTS5209 PCI Express Card ... | 2     | rtsx_pci   | B24886CD7F |
| 10ec:5229 | 1025:1073 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 707F27E3E8 |
| 10ec:5229 | 103c:2af8 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 73FE3F4EE7 |
| 10ec:5229 | 103c:2af9 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 28B99207FE |
| 10ec:5229 | 103c:2b0b | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | A051170E5F |
| 10ec:5229 | 103c:2b15 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 77B2814746 |
| 10ec:5249 | 10ec:5249 | Realtek... | RTS5249 PCI Express Card ... | 2     | rtsx_pci   | B9FAD5E7DD |
| 10ec:525a | 1734:1249 | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx_pci   | 9320FE9EED |
| 10ec:5209 | 103c:2ac7 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 7A9D5AF1CE |
| 10ec:5209 | 103c:2af5 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 7D17193EB2 |
| 10ec:5209 | 103c:2b02 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 74E79527D5 |
| 10ec:5209 | 10cf:15e0 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 15202A6CAE |
| 10ec:5209 | 17aa:3620 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | 0C3E26BCE7 |
| 10ec:5209 | 1b0a:015e | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx_pci   | EA65434637 |
| 10ec:5229 | 1025:0946 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 3B4F88C98F |
| 10ec:5229 | 103c:2af6 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 824A23BF00 |
| 10ec:5229 | 103c:2b09 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 44E3728303 |
| 10ec:5229 | 10ec:5229 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | CAF59FFB4A |
| 10ec:5229 | 1849:5229 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 95EFD1E9A2 |
| 10ec:5229 | 1b0a:018a | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | CAA7CA382E |
| 10ec:5229 | 8086:2068 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 3313AA3C86 |
| 10ec:5249 | 1462:1113 | Realtek... | RTS5249 PCI Express Card ... | 1     | rtsx_pci   | 8F5D0B74C4 |
| 10ec:525a | 1028:06b9 | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | E7B9652DBD |
| 10ec:525a | 1028:085a | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | B7022F0A45 |
| 10ec:525a | 1028:0860 | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | 038A085F01 |
| 10ec:525a | 1028:09a4 | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | D35C6EA078 |
| 10ec:525a | 1028:09aa | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | DD7D7C5A0C |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0753 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Co-... | 66    |            | 9005621271 |
| 10de:03f4 | 1462:7309 | Nvidia     | MCP61 SMU                    | 38    |            | 72F1E0A452 |
| 10de:03f4 | 1462:7597 | Nvidia     | MCP61 SMU                    | 38    |            | 79851E843C |
| 10de:0753 | 1849:0753 | Nvidia     | MCP78S [GeForce 8200] Co-... | 37    |            | E817658118 |
| 10de:0753 | 1043:82e2 | Nvidia     | MCP78S [GeForce 8200] Co-... | 22    |            | DE0F1A6DD3 |
| 10de:07da | 1025:0137 | Nvidia     | MCP73 Co-processor           | 14    |            | 4AEC616B4D |
| 10de:0aa3 | 1025:0222 | Nvidia     | MCP79 Co-processor           | 13    | nvidia     | 093D03CAF5 |
| 10de:03f4 |           | Nvidia     | MCP61 SMU                    | 12    |            | CB279CFEAF |
| 10de:0753 | 1025:0228 | Nvidia     | MCP78S [GeForce 8200] Co-... | 12    |            | 6017A97F3E |
| 10de:0753 | 1025:0153 | Nvidia     | MCP78S [GeForce 8200] Co-... | 11    |            | 3C4134E3B4 |
| 10de:0aa3 | 1025:0168 | Nvidia     | MCP79 Co-processor           | 11    | nvidia     | 6872AE9FB4 |
| 10de:0753 | 1043:82e8 | Nvidia     | MCP78S [GeForce 8200] Co-... | 10    |            | 9DAF1B6529 |
| 10de:03f4 | 1043:8234 | Nvidia     | MCP61 SMU                    | 9     |            | 56DB54E530 |
| 10de:0543 | 1849:0543 | Nvidia     | MCP67 Co-processor           | 9     |            | 1C6B15BC7B |
| 10de:0753 | 1565:340b | Nvidia     | MCP78S [GeForce 8200] Co-... | 9     |            | BE977291B5 |
| 10de:0aa3 | 1462:7621 | Nvidia     | MCP79 Co-processor           | 9     | nvidia     | 29ECAF9382 |
| 10de:0753 | 103c:2a81 | Nvidia     | MCP78S [GeForce 8200] Co-... | 8     |            | 3A69706315 |
| 10de:0753 | 1043:82e7 | Nvidia     | MCP78S [GeForce 8200] Co-... | 7     |            | 6AA0488E7E |
| 10de:0aa3 | 1b0a:0074 | Nvidia     | MCP79 Co-processor           | 7     | nvidia     | 484AF2A752 |
| 10de:07da | 1462:7504 | Nvidia     | MCP73 Co-processor           | 6     |            | 53C7457A1D |
| 10de:0753 | 1025:0157 | Nvidia     | MCP78S [GeForce 8200] Co-... | 5     |            | 591C077E28 |
| 10de:07da | 1462:7366 | Nvidia     | MCP73 Co-processor           | 5     |            | ADA828F120 |
| 10de:07da | 1462:736b | Nvidia     | MCP73 Co-processor           | 5     |            | C554C3A77F |
| 10de:07da | 1849:07da | Nvidia     | MCP73 Co-processor           | 5     |            | 01E398A327 |
| 10de:0aa3 | 1849:0aa3 | Nvidia     | MCP79 Co-processor           | 5     | nvidia     | B68D01F3AE |
| 10de:03f4 | 1849:03f4 | Nvidia     | MCP61 SMU                    | 4     |            | 5751926628 |
| 10de:0753 | 1025:0227 | Nvidia     | MCP78S [GeForce 8200] Co-... | 4     |            | 4D35606FF5 |
| 10de:0aa3 | 103c:2a95 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | 0E1FA2C583 |
| 10de:0aa3 | 105b:0d52 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | 3F5D854E2F |
| 10de:0aa3 | 19da:0ae5 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | 5CA23CF3F6 |
| 10de:0753 | 1025:0462 | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | BEB8F313F7 |
| 10de:0753 | 103c:2a9e | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | C1329912E7 |
| 10de:0753 | 1462:7612 | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | 905C03A3D4 |
| 10de:07da | 10de:07d7 | Nvidia     | MCP73 Co-processor           | 3     |            | 974A439CC4 |
| 10de:0aa3 | 103c:2aa1 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 622D9B0AE4 |
| 10de:0aa3 | 1043:83e2 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 1452DE25DA |
| 10de:0aa3 | 1043:83e9 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 0D0D8B9925 |
| 10de:0aa3 | 1043:83f9 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 57C3CE82B7 |
| 10de:0aa3 | 10de:cb79 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 879EB33660 |
| 10de:0aa3 | 19da:a108 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 35A29512AC |
| 10de:0753 | 1019:1b67 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 35BFD13207 |
| 10de:0753 | 1019:2646 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | BF975A328C |
| 10de:0753 | 1019:2666 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 5C15176A57 |
| 10de:0753 | 1043:8332 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | FC54031F7E |
| 10de:0753 | 10de:cb84 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 89EEF3C1A9 |
| 10de:0753 | 1462:6720 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | C630018FEA |
| 10de:0753 | 1462:7375 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 07A001660F |
| 10de:0753 | 1462:7578 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 9FC0813DDD |
| 10de:0aa3 | 1043:8356 | Nvidia     | MCP79 Co-processor           | 2     |            | AAF6FAFAD6 |
| 10de:0aa3 | 1458:0aa3 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | 545B983E7C |
| 10de:0aa3 | 1b0a:000f | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | BF054CFF0C |
| 8086:19e2 | 8086:19e2 | Intel      | Atom Processor C3000 Seri... | 2     | qat_c3xxx  | 2B7A8BA5FC |
| 10de:0753 | 1297:3139 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 6B6D198B0D |
| 10de:0753 | 1462:7511 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 87456F207B |
| 10de:0753 | 1631:e03b | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | E6D16C44AA |
| 10de:0753 | 19da:a100 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 50A93243D2 |
| 10de:07da | 105b:0d1f | Nvidia     | MCP73 Co-processor           | 1     |            | 87EF8BCE11 |
| 10de:07da | 10de:cb73 | Nvidia     | MCP73 Co-processor           | 1     |            | 7099E6EF4B |
| 10de:07da | 1462:366f | Nvidia     | MCP73 Co-processor           | 1     |            | 238EC9B2AC |
| 10de:07da | 1462:736a | Nvidia     | MCP73 Co-processor           | 1     |            | 650300C6BF |
| 10de:0aa3 | 1028:02b6 | Nvidia     | MCP79 Co-processor           | 1     |            | 85AAFD27C3 |
| 10de:0aa3 | 103c:2a7c | Nvidia     | MCP79 Co-processor           | 1     |            | 9A3F224628 |
| 10de:0aa3 | 103c:2a83 | Nvidia     | MCP79 Co-processor           | 1     | nvidia     | 226AA094E2 |
| 10de:0aa3 | 19da:a119 | Nvidia     | MCP79 Co-processor           | 1     |            | A6CC2E15FF |
| 10de:0aa3 | 1b0a:0071 | Nvidia     | MCP79 Co-processor           | 1     |            | 2582663F1E |
| 10de:0aa3 | a0a0:0802 | Nvidia     | MCP79 Co-processor           | 1     |            | B778A6096A |
| 1bbf:0003 | 1bbf:0007 | Maxeler... | MAX3                         | 1     |            | 76E711B112 |
| 8086:1f18 | 15d9:0820 | Intel      | Atom processor C2000 QAT     | 1     |            | DAE3697FF8 |
| 8086:225c | 8086:2500 | Intel      | Xeon Phi coprocessor SE10... | 1     | mic        | DAE871210E |
| 8086:225c | 8086:7d95 | Intel      | Xeon Phi coprocessor SE10... | 1     | mic_host   | A37475889B |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1c3a | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1126  | mei_me     | 278873FF66 |
| 8086:8c3a | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 903   | mei_me     | 735015DCE2 |
| 8086:1e3a | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 772   | mei_me     | 1575E2C682 |
| 8086:a13a | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 729   | mei_me     | 427C8B8D8F |
| 8086:1c3a | 1458:1c3a | Intel      | 6 Series/C200 Series Chip... | 716   | mei_me     | 042607D7F1 |
| 8086:8c3a | 1458:1c3a | Intel      | 8 Series/C220 Series Chip... | 592   | mei_me     | 3934A7E59D |
| 8086:1e3a | 1458:1c3a | Intel      | 7 Series/C216 Chipset Fam... | 568   | mei_me     | BB6DE8B3E0 |
| 8086:a2ba | 1043:8694 | Intel      | 200 Series PCH CSME HECI #1  | 460   | mei_me     | 381023907E |
| 8086:a2ba | 1458:1c3a | Intel      | 200 Series PCH CSME HECI #1  | 430   | mei_me     | 8C2B6CF453 |
| 8086:a13a | 1458:1c3a | Intel      | 100 Series/C230 Series Ch... | 418   | mei_me     | 36BF6DAB37 |
| 8086:a360 | 1043:8694 | Intel      | Cannon Lake PCH HECI Cont... | 374   | mei_me     | 22A32FC3F2 |
| 8086:8cba | 1043:8534 | Intel      | 9 Series Chipset Family M... | 329   | mei_me     | 5A5D3A54C3 |
| 8086:a360 | 1458:1c3a | Intel      | Cannon Lake PCH HECI Cont... | 306   | mei_me     | 1C2A383C4F |
| 8086:8c3a | 1849:8c3a | Intel      | 8 Series/C220 Series Chip... | 279   | mei_me     | 111E98DDEF |
| 8086:1c3a | 1849:1c3a | Intel      | 6 Series/C200 Series Chip... | 269   | mei_me     | 7070F2EAF3 |
| 8086:8cba | 1458:1c3a | Intel      | 9 Series Chipset Family M... | 255   | mei_me     | 5EAD0CA3AD |
| 8086:a13a | 1849:a13a | Intel      | 100 Series/C230 Series Ch... | 202   | mei_me     | 6B4C3F811B |
| 8086:1e3a | 1849:1e3a | Intel      | 7 Series/C216 Chipset Fam... | 190   | mei_me     | F6F957DDF3 |
| 8086:8c3a | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 186   | mei_me     | 0420EDF711 |
| 8086:1e3a | 1028:0577 | Intel      | 7 Series/C216 Chipset Fam... | 178   | mei_me     | E1B966B80D |
| 8086:a2ba | 1849:a2ba | Intel      | 200 Series PCH CSME HECI #1  | 178   | mei_me     | 79E6EF3655 |
| 8086:a2ba | 1043:872f | Intel      | 200 Series PCH CSME HECI #1  | 158   | mei_me     | F60A34FE5C |
| 8086:1d3a | 1043:84ef | Intel      | C600/X79 series chipset M... | 141   | mei_me     | 1BB97BC7DF |
| 8086:8c3a | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 137   | mei_me     | CC73A253B3 |
| 8086:1c3a | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 132   | mei_me     | D6237E9949 |
| 8086:a360 | 1849:a360 | Intel      | Cannon Lake PCH HECI Cont... | 124   | mei_me     | 2FF008A28D |
| 8086:8cba | 1849:8cba | Intel      | 9 Series Chipset Family M... | 119   | mei_me     | 8DE72FD346 |
| 8086:3b64 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 115   | mei_me     | C29EE7CA9F |
| 8086:8d3a | 1043:8600 | Intel      | C610/X99 series chipset M... | 113   | mei_me     | D3A4772E4E |
| 8086:1e3a | 103c:3397 | Intel      | 7 Series/C216 Chipset Fam... | 104   | mei_me     | BF9875C5AC |
| 8086:29b4 | 1028:0211 | Intel      | 82Q35 Express MEI Controller | 104   | mei_me     | 7E7D0BC489 |
| 8086:8c3a | 1028:0612 | Intel      | 8 Series/C220 Series Chip... | 100   | mei_me     | 990123A52D |
| 8086:3b64 | 1458:3b64 | Intel      | 5 Series/3400 Series Chip... | 99    | mei_me     | 02DFFBFEA8 |
| 8086:2e14 | 1028:0420 | Intel      | 4 Series Chipset HECI Con... | 96    | mei_me     | 476F78A010 |
| 8086:1c3a | 1028:047e | Intel      | 6 Series/C200 Series Chip... | 87    | mei_me     | 6AF9EA19B5 |
| 8086:1c3a | 1028:04f5 | Intel      | 6 Series/C200 Series Chip... | 87    | mei_me     | 5131593DDF |
| 8086:2e14 | 1028:027f | Intel      | 4 Series Chipset HECI Con... | 87    | mei_me     | F27A29129F |
| 8086:1c3a | 1028:0585 | Intel      | 6 Series/C200 Series Chip... | 86    | mei_me     | E766BCBB62 |
| 8086:1e3a | 103c:339a | Intel      | 7 Series/C216 Chipset Fam... | 85    | mei_me     | 28DA82FF00 |
| 8086:a3ba | 1043:8694 | Intel      | Comet Lake PCH-V Manageme... | 82    | mei_me     | 7B62AD7C35 |
| 8086:1c3a | 103c:2abf | Intel      | 6 Series/C200 Series Chip... | 80    | mei_me     | 380D5AB9F0 |
| 8086:1c3a | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 80    | mei_me     | E5BF692305 |
| 8086:06e0 | 1043:8694 | Intel      | Comet Lake HECI Controller   | 79    | mei_me     | CAFC4421B2 |
| 8086:8c3a | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 79    | mei_me     | B9E492678D |
| 8086:1c3a | 103c:1495 | Intel      | 6 Series/C200 Series Chip... | 75    | mei_me     | E7C0F59F92 |
| 8086:1e3a | 1462:7758 | Intel      | 7 Series/C216 Chipset Fam... | 74    | mei_me     | 3BD9604AE7 |
| 8086:1c3a | 8086:1c3a | Intel      | 6 Series/C200 Series Chip... | 72    | mei_me     | 6978CD209F |
| 8086:a13a | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 71    | mei_me     | EC7609239E |
| 8086:319a | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 70    | mei_me     | D2611BC564 |
| 8086:2e14 | 103c:3048 | Intel      | 4 Series Chipset HECI Con... | 69    | mei_me     | B62359FCB1 |
| 8086:3b64 | 103c:2a9c | Intel      | 5 Series/3400 Series Chip... | 69    | mei_me     | 2F752A1A3E |
| 8086:8c3a | 1734:11ea | Intel      | 8 Series/C220 Series Chip... | 69    | mei_me     | 066CB46C80 |
| 8086:1c3a | 103c:1497 | Intel      | 6 Series/C200 Series Chip... | 68    | mei_me     | C0FB875CA5 |
| 8086:8c3a | 103c:18e7 | Intel      | 8 Series/C220 Series Chip... | 66    | mei_me     | 94C750BA4B |
| 8086:8c3a | 17aa:3098 | Intel      | 8 Series/C220 Series Chip... | 66    | mei_me     | 718011BC1A |
| 8086:2e14 | 1734:114c | Intel      | 4 Series Chipset HECI Con... | 65    | mei_me     | 6B08158329 |
| 8086:1e3a | 1028:052c | Intel      | 7 Series/C216 Chipset Fam... | 57    | mei_me     | 79E64FF0D3 |
| 8086:1e3a | 1734:11d6 | Intel      | 7 Series/C216 Chipset Fam... | 57    | mei_me     | 7A70FC2989 |
| 8086:1c3a | 1734:11ba | Intel      | 6 Series/C200 Series Chip... | 56    | mei_me     | 1229314F25 |
| 8086:3b64 | 8086:0036 | Intel      | 5 Series/3400 Series Chip... | 56    | mei_me     | E5F7233230 |
| 8086:8c3a | 1462:7816 | Intel      | 8 Series/C220 Series Chip... | 54    | mei_me     | 1DDE7A0E87 |
| 14f1:2f20 | 14f1:200f | Conexan... | HSF 56k Data/Fax Modem       | 53    |            | 2E28996126 |
| 8086:29b4 | 103c:2818 | Intel      | 82Q35 Express MEI Controller | 53    | mei_me     | 40DA7A8AE9 |
| 8086:8c3a | 1028:05b7 | Intel      | 8 Series/C220 Series Chip... | 53    | mei_me     | EC418886CD |
| 8086:a13a | 1734:121d | Intel      | 100 Series/C230 Series Ch... | 52    | mei_me     | C3479871D7 |
| 8086:1c3a | 1019:3190 | Intel      | 6 Series/C200 Series Chip... | 51    | mei_me     | 47DEB6E1FB |
| 8086:1c3a | 1462:7680 | Intel      | 6 Series/C200 Series Chip... | 50    | mei_me     | 3A07878154 |
| 8086:29c4 | 8086:5044 | Intel      | 82G33/G31/P35/P31 Express... | 50    | mei_me     | A5121E1871 |
| 8086:1c3a | 17aa:3070 | Intel      | 6 Series/C200 Series Chip... | 47    | mei_me     | 1ECB7A6910 |
| 8086:a13a | 1462:7a15 | Intel      | 100 Series/C230 Series Ch... | 47    | mei_me     | 059A06E95C |
| 8086:06e0 | 1458:1c3a | Intel      | Comet Lake HECI Controller   | 46    | mei_me     | 7983497985 |
| 8086:1c3a | 1025:0492 | Intel      | 6 Series/C200 Series Chip... | 46    | mei_me     | 967427D98C |
| 8086:43e0 | 1043:8694 | Intel      | Tiger Lake-H Management E... | 46    | mei_me     | B9C2FEC8AA |
| 8086:8c3a | 17aa:3097 | Intel      | 8 Series/C220 Series Chip... | 45    | mei_me     | A5026C4013 |
| 8086:06e0 | 1849:06e0 | Intel      | Comet Lake HECI Controller   | 44    | mei_me     | AD42FA5D08 |
| 8086:2e14 | 17aa:3048 | Intel      | 4 Series Chipset HECI Con... | 44    | mei_me     | ED1D55E70A |
| 8086:8d3a | 1458:7270 | Intel      | C610/X99 series chipset M... | 44    | mei_me     | 347D6DF600 |
| 8086:a13a | 1028:06b9 | Intel      | 100 Series/C230 Series Ch... | 44    | mei_me     | 92F15AEB4D |
| 8086:29d4 | 103c:281e | Intel      | 82Q33 Express MEI Controller | 43    | mei_me     | EAA60F7610 |
| 8086:5a9a | 1849:5a9a | Intel      | Celeron N3350/Pentium N42... | 43    | mei_me     | 9FD17A6579 |
| 8086:a13a | 1462:7971 | Intel      | 100 Series/C230 Series Ch... | 43    | mei_me     | 77006702F8 |
| 8086:a2ba | 1043:873c | Intel      | 200 Series PCH CSME HECI #1  | 43    | mei_me     | EACC1E3F66 |
| 8086:1e3a | 8086:1e3a | Intel      | 7 Series/C216 Chipset Fam... | 42    | mei_me     | C2D53C8118 |
| 8086:1c3a | 8086:2017 | Intel      | 6 Series/C200 Series Chip... | 41    | mei_me     | 43E3FCCC3D |
| 8086:1e3a | 17aa:3083 | Intel      | 7 Series/C216 Chipset Fam... | 41    | mei_me     | DF15656FCE |
| 8086:1c3a | 1025:0589 | Intel      | 6 Series/C200 Series Chip... | 40    | mei_me     | 7AB93EC832 |
| 8086:1d3a | 103c:1589 | Intel      | C600/X79 series chipset M... | 40    | mei_me     | 49C747EFAD |
| 8086:8c3a | 1028:0622 | Intel      | 8 Series/C220 Series Chip... | 40    | mei_me     | 287D0004F3 |
| 8086:8d3a | 1849:8d3a | Intel      | C610/X99 series chipset M... | 40    | mei_me     | 2BF61F2EC6 |
| 8086:2e14 | 103c:3034 | Intel      | 4 Series Chipset HECI Con... | 39    | mei_me     | D05CCA1A32 |
| 8086:2e14 | 103c:3646 | Intel      | 4 Series Chipset HECI Con... | 39    | mei_me     | 60FB363058 |
| 8086:8c3a | 1025:0750 | Intel      | 8 Series/C220 Series Chip... | 39    | mei_me     | 4AA46E7581 |
| 8086:a360 | 1462:7b98 | Intel      | Cannon Lake PCH HECI Cont... | 39    | mei_me     | FC6F79950A |
| 8086:8c3a | 17aa:30a3 | Intel      | 8 Series/C220 Series Chip... | 38    | mei_me     | 068BEE7912 |
| 8086:8c3a | 8086:8c3a | Intel      | 8 Series/C220 Series Chip... | 38    | mei_me     | 50758CFAF3 |
| 14f1:2f20 | 14f1:200c | Conexan... | HSF 56k Data/Fax Modem       | 36    |            | BCB9322F96 |
| 8086:1c3a | 103c:1494 | Intel      | 6 Series/C200 Series Chip... | 36    | mei_me     | AE5165603A |
| 8086:8d3a | 1462:7885 | Intel      | C610/X99 series chipset M... | 36    | mei_me     | 90189BED4E |
| 8086:1e3a | 103c:3396 | Intel      | 7 Series/C216 Chipset Fam... | 35    | mei_me     | 147C8ED96C |
| 8086:8c3a | 1028:05a5 | Intel      | 8 Series/C220 Series Chip... | 35    | mei_me     | 827CB9A77A |

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
| 13d0:2103 | 13d0:2103 | Techsan... | B2C2 FlexCopII DVB chip /... | 62    | b2c2_fl... | 38AEBF6955 |
| 1131:7146 | 13c2:1018 | Philips... | SAA7146                      | 28    | budget     | 830837B611 |
| 109e:0878 | 1822:0001 | Brooktree  | Bt878 Audio Capture          | 5     | bt878      | 39FB7FBFDD |
| 1131:7146 | 13c2:101a | Philips... | SAA7146                      | 5     | budget_ci  | 99B906C497 |
| 14f1:8802 | 0070:9002 | Conexan... | CX23880/1/2/3 PCI Video a... | 5     | cx88_dvb   | 1351C7B098 |
| 1131:7146 | 13c2:1019 | Philips... | SAA7146                      | 4     | budget_ci  | 7F15F19A9B |
| 109e:0878 | 11bd:001c | Brooktree  | Bt878 Audio Capture          | 3     | bt878      | BA214D2A0B |
| 1131:7146 | 13c2:0003 | Philips... | SAA7146                      | 3     | dvb_ttpci  | 69DA26C946 |
| 109e:0878 | 1461:0771 | Brooktree  | Bt878 Audio Capture          | 2     | bt878      | AB87264048 |
| 14f1:8802 | 17de:08a6 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     | cx88_dv... | D932872569 |
| 195d:1105 | 195d:1105 |            | Ethernet controller          | 2     | dm1105     | 4AEC213A10 |
| 1131:7146 | 1131:4f56 | Philips... | SAA7146                      | 1     | budget_av  | B220FD9C11 |
| 1131:7146 | 13c2:000a | Philips... | SAA7146                      | 1     | dvb_ttpci  | 9A76597218 |
| 1131:7146 | 13c2:000e | Philips... | SAA7146                      | 1     | dvb_ttpci  | 2A21A99A38 |
| 1131:7146 | 153b:1154 | Philips... | SAA7146                      | 1     | budget_av  | D949336ED1 |
| 1131:7146 | 153b:1156 | Philips... | SAA7146                      | 1     | budget_av  | E514F058FE |
| 1131:7146 | 1894:0022 | Philips... | SAA7146                      | 1     | budget_av  | 931BED40DE |
| 13d0:2103 | ffff:ffff | Techsan... | B2C2 FlexCopII DVB chip /... | 1     | b2c2_fl... | 7609423845 |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1456 | 1022:1456 | AMD        | Family 17h (Models 00h-0f... | 1870  | ccp        | E52E9002D0 |
| 1022:1486 | 1022:1486 | AMD        | Starship/Matisse Cryptogr... | 1371  | ccp        | C537345CE8 |
| 1022:15df | 1022:15df | AMD        | Family 17h (Models 10h-1f... | 930   | ccp        | B2D3620851 |
| 1022:1486 | 1043:87c0 | AMD        | Starship/Matisse Cryptogr... | 727   | ccp        | 161865EDB0 |
| 1022:1456 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 616   | ccp        | 491D1A96CC |
| 1022:15df | 1043:876b | AMD        | Family 17h (Models 10h-1f... | 262   | ccp        | 24974BE67E |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 219   |            | 5114976821 |
| 1022:1486 | 1043:8808 | AMD        | Starship/Matisse Cryptogr... | 163   | ccp        | A525C8911B |
| 1022:1486 | 1462:7c02 | AMD        | Starship/Matisse Cryptogr... | 96    | ccp        | 97620628A8 |
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 76    | mei_txe    | 9333E233D6 |
| 1022:1486 | 1462:7b86 | AMD        | Starship/Matisse Cryptogr... | 66    | ccp        | 7E563A9D44 |
| 8086:0f18 | 1849:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 66    | mei_txe    | 1410D0FFB5 |
| 1022:1456 | 1462:7c02 | AMD        | Family 17h (Models 00h-0f... | 59    | ccp        | F50B61B450 |
| 1022:1456 | 1462:7b86 | AMD        | Family 17h (Models 00h-0f... | 46    | ccp        | F17090E5D2 |
| 1022:1486 | 1462:7b89 | AMD        | Starship/Matisse Cryptogr... | 45    | ccp        | A72102FDB0 |
| 1022:1537 | 1022:1537 | AMD        | Kabini/Mullins PSP-Platfo... | 45    | ccp        | 5B14D08827 |
| 8086:0f18 | 1458:1c3a | Intel      | Atom Processor Z36xxx/Z37... | 35    | mei_txe    | D34B6CFE65 |
| 1022:15df | 1462:7a38 | AMD        | Family 17h (Models 10h-1f... | 29    | ccp        | B914028CA9 |
| 1022:1486 | 1462:7a38 | AMD        | Starship/Matisse Cryptogr... | 28    | ccp        | 11F7EC8B16 |
| 1022:1456 | 1462:7a38 | AMD        | Family 17h (Models 00h-0f... | 27    | ccp        | 276D5FE9E3 |
| 8086:0f18 | 8086:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 27    | mei_txe    | 9367472ACB |
| 8086:2298 | 1849:2298 | Intel      | Atom/Celeron/Pentium Proc... | 27    | mei_txe    | 6E3084CF7F |
| 1022:1486 | 1462:7c94 | AMD        | Starship/Matisse Cryptogr... | 26    | ccp        | 08819513F2 |
| 1022:15df | 1043:87e1 | AMD        | Family 17h (Models 10h-1f... | 26    | ccp        | 740C97FB1C |
| 8086:2298 | 1458:1000 | Intel      | Atom/Celeron/Pentium Proc... | 25    | mei_txe    | 8B88D7AB23 |
| 1022:1456 | 1462:7b89 | AMD        | Family 17h (Models 00h-0f... | 24    | ccp        | E8965C736D |
| 1022:1486 | 1043:87cb | AMD        | Starship/Matisse Cryptogr... | 24    | ccp        | 6E020F3AD1 |
| 1022:1486 | 1462:7c95 | AMD        | Starship/Matisse Cryptogr... | 23    | ccp        | D06DD7E0EC |
| 8086:0f18 | 1025:085e | Intel      | Atom Processor Z36xxx/Z37... | 22    | mei_txe    | 943617D620 |
| 1022:1486 | 1462:7b85 | AMD        | Starship/Matisse Cryptogr... | 21    | ccp        | DB9BFA58F9 |
| 8086:0f18 | 1019:7ed4 | Intel      | Atom Processor Z36xxx/Z37... | 21    | mei_txe    | 509F6B0C67 |
| 8086:0f18 | 8086:2055 | Intel      | Atom Processor Z36xxx/Z37... | 20    | mei_txe    | 75EB93BBE0 |
| 1022:15df | 1462:7c02 | AMD        | Family 17h (Models 10h-1f... | 19    | ccp        | 02983FA577 |
| 8086:0f18 | 1043:8534 | Intel      | Atom Processor Z36xxx/Z37... | 18    | mei_txe    | EBD51400E3 |
| 8086:2298 | 1043:8534 | Intel      | Atom/Celeron/Pentium Proc... | 18    | mei_txe    | E9CD0640F7 |
| 1022:15df | 1462:7b86 | AMD        | Family 17h (Models 10h-1f... | 17    | ccp        | A36474B9FF |
| 1022:1456 | 1462:7b85 | AMD        | Family 17h (Models 00h-0f... | 15    | ccp        | 429525379A |
| 1022:15df | 1462:7b89 | AMD        | Family 17h (Models 10h-1f... | 15    | ccp        | CADB142111 |
| 1022:1486 | 1043:87e2 | AMD        | Starship/Matisse Cryptogr... | 14    | ccp        | EE6DBC679C |
| 1022:1578 | 17aa:364f | AMD        | Carrizo Platform Security... | 12    |            | 95EDC1D588 |
| 1022:1486 | 1462:7a40 | AMD        | Starship/Matisse Cryptogr... | 11    | ccp        | 1CA6C5085E |
| 1022:15df | 1043:8809 | AMD        | Family 17h (Models 10h-1f... | 11    | ccp        | 2FF2EB607A |
| 1022:1456 | 1462:7a40 | AMD        | Family 17h (Models 00h-0f... | 10    | ccp        | 89BF33DB93 |
| 8086:0f18 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 10    | mei_txe    | 0E5100E716 |
| 8086:2298 | 1025:0953 | Intel      | Atom/Celeron/Pentium Proc... | 9     | mei_txe    | EDF84D2336 |
| 8086:2298 | 103c:821d | Intel      | Atom/Celeron/Pentium Proc... | 9     | mei_txe    | 69C8804209 |
| 8086:2298 | 17aa:30c9 | Intel      | Atom/Celeron/Pentium Proc... | 9     | mei_txe    | 174975E4F8 |
| 1022:15df | 103c:87d6 | AMD        | Family 17h (Models 10h-1f... | 8     | ccp        | 6DB404B73C |
| 1022:15df | 1462:7a40 | AMD        | Family 17h (Models 10h-1f... | 8     | ccp        | CACD4B91A5 |
| 8086:0f18 | 1458:1000 | Intel      | Atom Processor Z36xxx/Z37... | 8     | mei_txe    | 3040E45974 |
| 8086:0f18 | 1565:310e | Intel      | Atom Processor Z36xxx/Z37... | 8     | mei_txe    | AF163E54E9 |
| 8086:2298 | 1019:9bef | Intel      | Atom/Celeron/Pentium Proc... | 8     | mei_txe    | DF3A9167C8 |
| 8086:0f18 | 1028:068d | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | 3F25BAF528 |
| 8086:2298 | 1458:1c3a | Intel      | Atom/Celeron/Pentium Proc... | 7     | mei_txe    | 2FD537312F |
| 8086:2298 | 8086:2298 | Intel      | Atom/Celeron/Pentium Proc... | 7     | mei_txe    | 88C472D69E |
| 1022:1456 | 1462:7b87 | AMD        | Family 17h (Models 00h-0f... | 6     | ccp        | 18FF34F941 |
| 1022:1486 | 17aa:1046 | AMD        | Starship/Matisse Cryptogr... | 6     | ccp        | 136C409F1A |
| 1022:1578 | 17aa:3100 | AMD        | Carrizo Platform Security... | 6     |            | BBFCF94452 |
| 1022:15df | 17aa:3708 | AMD        | Family 17h (Models 10h-1f... | 6     | ccp        | A7D8D3CF71 |
| 1022:1578 | 103c:8265 | AMD        | Carrizo Platform Security... | 5     |            | F840AED42D |
| 1022:15df | 103c:83e9 | AMD        | Family 17h (Models 10h-1f... | 5     | ccp        | 7964501CA5 |
| 1022:15df | 1462:7b87 | AMD        | Family 17h (Models 10h-1f... | 5     |            | 02D89D2EE7 |
| 8086:0f18 | 103c:2b28 | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | 14681C925A |
| 1022:1456 | 1462:7b90 | AMD        | Family 17h (Models 00h-0f... | 4     | ccp        | 3642F15AB7 |
| 1022:1486 | 1028:098e | AMD        | Starship/Matisse Cryptogr... | 4     | ccp        | E1BC8D1CDD |
| 1022:1486 | 1043:8815 | AMD        | Starship/Matisse Cryptogr... | 4     | ccp        | 8F7011B085 |
| 1022:1486 | 1462:7b87 | AMD        | Starship/Matisse Cryptogr... | 4     | ccp        | 58A277F8E4 |
| 1022:1498 | 1022:1498 | AMD        | Starship/Matisse PTDMA       | 4     |            | C0104AA33D |
| 1022:1537 | 103c:21ef | AMD        | Kabini/Mullins PSP-Platfo... | 4     | ccp        | 1AB2F81428 |
| 1022:1537 | 103c:2b29 | AMD        | Kabini/Mullins PSP-Platfo... | 4     | ccp        | 06BABD8C13 |
| 1022:1578 | 103c:805b | AMD        | Carrizo Platform Security... | 4     |            | D6C2730444 |
| 1022:15df | 1462:7b85 | AMD        | Family 17h (Models 10h-1f... | 4     | ccp        | 1E96B02BF3 |
| 8086:0f18 | 1019:7ed1 | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 11A52F4D52 |
| 8086:0f18 | 1019:99cf | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 8D82A3932B |
| 8086:0f18 | 1019:99f3 | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 138C2EF6FB |
| 8086:0f18 | 105b:0db1 | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 177A7992A1 |
| 8086:0f18 | 1297:4019 | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 1FD5FA69E2 |
| 1022:1486 | 1462:7c96 | AMD        | Starship/Matisse Cryptogr... | 3     | ccp        | EB1233376B |
| 1022:15df | 103c:83e8 | AMD        | Family 17h (Models 10h-1f... | 3     | ccp        | F378108DC3 |
| 1022:15df | 103c:872b | AMD        | Family 17h (Models 10h-1f... | 3     | ccp        | 1AD7D53F97 |
| 1022:15df | 103c:8906 | AMD        | Family 17h (Models 10h-1f... | 3     | ccp        | B40EA88DA1 |
| 1022:15df | 1462:7c94 | AMD        | Family 17h (Models 10h-1f... | 3     | ccp        | 07E9EE8610 |
| 1022:15df | 1462:7c95 | AMD        | Family 17h (Models 10h-1f... | 3     | ccp        | B806A146D2 |
| 1022:15df | 1849:15df | AMD        | Family 17h (Models 10h-1f... | 3     | ccp        | FD95402AA1 |
| 8086:0f18 | 1019:99ad | Intel      | Atom Processor Z36xxx/Z37... | 3     | mei_txe    | 49CFBBDD47 |
| 8086:2298 | 1019:9af1 | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | 1069244654 |
| 8086:2298 | 1025:1064 | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | 12B9C02A39 |
| 8086:2298 | 103c:2b46 | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | F6C6C78B6D |
| 1022:1456 | 103c:8399 | AMD        | Family 17h (Models 00h-0f... | 2     | ccp        | 733813E901 |
| 1022:1468 | 1022:1468 | AMD        | Zeppelin Cryptographic Co... | 2     | ccp        | 4C4AD9EBE5 |
| 1022:1486 | 1028:0a8b | AMD        | Starship/Matisse Cryptogr... | 2     | ccp        | 5EA23EBFB2 |
| 1022:1486 | 1043:1c81 | AMD        | Starship/Matisse Cryptogr... | 2     | ccp        | 66B9CEA0F2 |
| 1022:1486 | 1849:1486 | AMD        | Starship/Matisse Cryptogr... | 2     | ccp        | 49A0EEC9F5 |
| 1022:1498 | 1849:1498 | AMD        | Starship/Matisse PTDMA       | 2     |            | EBCC16470F |
| 1022:1537 | 103c:2240 | AMD        | Kabini/Mullins PSP-Platfo... | 2     | ccp        | 8D09C291C1 |
| 1022:1578 | 103c:8266 | AMD        | Carrizo Platform Security... | 2     |            | E903E5B250 |
| 1022:15df | 1019:a4cd | AMD        | Family 17h (Models 10h-1f... | 2     |            | 8EB8144AEB |
| 1022:15df | 103c:8626 | AMD        | Family 17h (Models 10h-1f... | 2     | ccp        | E92FA74B31 |
| 1022:15df | 103c:876c | AMD        | Family 17h (Models 10h-1f... | 2     | ccp        | 4048E5035D |
| 1022:15df | 1458:1000 | AMD        | Family 17h (Models 10h-1f... | 2     | ccp        | 68DA5F41B2 |

### Entertainment encryption device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:2082 | 1022:2082 | AMD        | Geode LX AES Security Block  | 1     | geode_r... | 6D9551F87E |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1106:3044 | 1043:81fe | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 814   | firewir... | 588CEFB67B |
| 104c:8024 | 1458:1000 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 769   | firewir... | 370AD865CF |
| 1106:3044 | 1458:1000 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 272   | firewir... | 61D5F808B5 |
| 1106:3403 | 1043:8384 | VIA Tec... | VT6315 Series Firewire Co... | 264   | firewir... | 0C14FFD402 |
| 1106:3044 | 1106:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 220   | firewir... | AAE0C56D3A |
| 11c1:5811 | 1043:8294 | LSI        | FW322/323 [TrueFire] 1394... | 220   | firewir... | F6317B60DD |
| 1102:4001 | 1102:0010 | Creativ... | SB Audigy FireWire Port      | 163   | firewir... | E04A41FC30 |
| 1106:3403 | 1849:3403 | VIA Tec... | VT6315 Series Firewire Co... | 132   | firewir... | 85B942A5C3 |
| 104c:8023 | 1043:808b | Texas I... | TSB43AB22A IEEE-1394a-200... | 100   | firewir... | 1B7F4401BE |
| 104c:823f |           | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 75    | firewir... | EA3E45A8A7 |
| 197b:2380 | 1043:8313 | JMicron... | IEEE 1394 Host Controller    | 69    | firewir... | 0228A60CDE |
| 11c1:5811 | 103c:2a6f | LSI        | FW322/323 [TrueFire] 1394... | 59    | firewir... | D5D1B22B75 |
| 1106:3403 | 103c:2a9c | VIA Tec... | VT6315 Series Firewire Co... | 58    | firewir... | 2F752A1A3E |
| 1106:3403 | 1043:8374 | VIA Tec... | VT6315 Series Firewire Co... | 55    | firewir... | 03B2C2E1AF |
| 104c:8023 | 1043:815b | Texas I... | TSB43AB22A IEEE-1394a-200... | 54    | firewir... | A402BB261D |
| 11c1:5811 | 103c:1309 | LSI        | FW322/323 [TrueFire] 1394... | 47    | firewir... | EB0C052885 |
| 11c1:5811 | 103c:1589 | LSI        | FW322/323 [TrueFire] 1394... | 43    | firewir... | 49C747EFAD |
| 1106:3403 | 1106:3403 | VIA Tec... | VT6315 Series Firewire Co... | 42    | firewir... | 138DF954CB |
| 104c:8023 | 8086:5044 | Texas I... | TSB43AB22A IEEE-1394a-200... | 34    | firewir... | A5121E1871 |
| 104c:823f | 3412:7856 | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 32    | firewir... | 6861CB8EBD |
| 1106:3044 | 1043:808a | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 32    | firewir... | B38568681E |
| 1106:3044 | 1849:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 32    | firewir... | C5E2E9E4A4 |
| 104c:8023 | 8086:514d | Texas I... | TSB43AB22A IEEE-1394a-200... | 28    | firewir... | D3F38DBF63 |
| 11c1:5811 | 103c:130b | LSI        | FW322/323 [TrueFire] 1394... | 28    | firewir... | 665BAE2867 |
| 11c1:5811 | 103c:158a | LSI        | FW322/323 [TrueFire] 1394... | 28    | firewir... | 6C22E51BFC |
| 11c1:5811 | 11c1:5811 | LSI        | FW322/323 [TrueFire] 1394... | 28    | firewir... | D4C089BC2F |
| 11c1:5811 | 1028:5811 | LSI        | FW322/323 [TrueFire] 1394... | 24    | firewir... | FF796824D2 |
| 11c1:5811 | 103c:130a | LSI        | FW322/323 [TrueFire] 1394... | 24    | firewir... | 328FCB35ED |
| 11c1:5811 | 1028:8010 | LSI        | FW322/323 [TrueFire] 1394... | 22    | firewir... | 25E00FC504 |
| 11c1:5811 | 103c:158b | LSI        | FW322/323 [TrueFire] 1394... | 22    | firewir... | 24399F4E69 |
| 104c:8023 | 1028:026d | Texas I... | TSB43AB22A IEEE-1394a-200... | 21    | firewir... | 2F188B606A |
| 104c:8023 | 8086:4257 | Texas I... | TSB43AB22A IEEE-1394a-200... | 21    | firewir... | D4B171DC3D |
| 104c:8024 | 1019:8056 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 21    | firewir... | DE627F1A6C |
| 104c:8025 |           | Texas I... | TSB82AA2 IEEE-1394b Link ... | 21    | firewir... | 1E34F92251 |
| 1106:3044 | 1025:8010 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 20    | firewir... | FDA18DABD0 |
| 1106:3044 | 103c:2a92 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 19    | firewir... | 770AAD2FE5 |
| 11c1:5811 | 8086:2008 | LSI        | FW322/323 [TrueFire] 1394... | 19    | firewir... | 36A4037B9D |
| 197b:2380 | 197b:2380 | JMicron... | IEEE 1394 Host Controller    | 19    | firewir... | 4C36D6B364 |
| 104c:8023 | 1028:021d | Texas I... | TSB43AB22A IEEE-1394a-200... | 17    | firewir... | 8CD7CD5DEE |
| 11bd:0015 | 11bd:0022 | Pinnacl... | FireWire IEEE1394            | 17    | firewir... | CF8D063DEB |
| 1033:00f2 | 1033:00f2 | NEC Com... | uPD72874 [Firewarden] IEE... | 16    | firewir... | 1B2A02AFBE |
| 1106:3044 | 1462:502d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 16    | firewir... | C38A6A2227 |
| 1106:3403 | 1028:040d | VIA Tec... | VT6315 Series Firewire Co... | 16    | firewir... | DAD38E979E |
| 11c1:5811 | 103c:2a50 | LSI        | FW322/323 [TrueFire] 1394... | 16    | firewir... | 42098EE0E7 |
| 104c:8024 | 105b:0e0a | Texas I... | TSB43AB23 IEEE-1394a-2000... | 15    | firewir... | 13957DED6B |
| 11c1:5811 | 103c:2a6c | LSI        | FW322/323 [TrueFire] 1394... | 15    | firewir... | 20FE2CD856 |
| 1106:3044 | 1019:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 14    | firewir... | DBE58885FE |
| 1106:3044 | 103c:2a24 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 14    | firewir... | EEA8D03E34 |
| 1106:3044 | 1043:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 14    | firewir... | 5DCFD80741 |
| 1106:3403 | 1025:0250 | VIA Tec... | VT6315 Series Firewire Co... | 14    | firewir... | F4E981B2C3 |
| 104c:8023 | 10de:c55e | Texas I... | TSB43AB22A IEEE-1394a-200... | 13    | firewir... | 5E986384B2 |
| 1106:3044 | 103c:2a6d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 13    | firewir... | F7EC16D7E7 |
| 1106:3044 | 1043:82eb | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 13    | firewir... | E1DCE50AA6 |
| 1106:3403 | 1025:024c | VIA Tec... | VT6315 Series Firewire Co... | 13    | firewir... | E355190768 |
| 11c1:5811 | 103c:2a5d | LSI        | FW322/323 [TrueFire] 1394... | 13    | firewir... | 1C43B3EF93 |
| 1106:3044 | 17f2:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 12    | firewir... | E91F400988 |
| 11c1:5811 | 103c:2a5e | LSI        | FW322/323 [TrueFire] 1394... | 12    | firewir... | 1F00F6D692 |
| 11c1:5811 | 103c:2a66 | LSI        | FW322/323 [TrueFire] 1394... | 12    | firewir... | BCB9322F96 |
| 11c1:5811 | 1734:1026 | LSI        | FW322/323 [TrueFire] 1394... | 12    | firewir... | D47952EC42 |
| 11c1:5811 | 8086:1003 | LSI        | FW322/323 [TrueFire] 1394... | 12    | firewir... | 543E15E027 |
| 197b:2380 | 1462:522d | JMicron... | IEEE 1394 Host Controller    | 12    | firewir... | 83BC2FB756 |
| 104c:8023 | 1028:0215 | Texas I... | TSB43AB22A IEEE-1394a-200... | 11    | firewir... | DF97B29E2E |
| 104c:8024 |           | Texas I... | TSB43AB23 IEEE-1394a-2000... | 11    | firewir... | BAF100CE1E |
| 1106:3044 | 103c:2a61 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 11    | firewir... | 50B1158D6D |
| 1106:3044 | 1106:0404 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 11    | firewir... | 49371E76EF |
| 1106:3403 | 1025:0153 | VIA Tec... | VT6315 Series Firewire Co... | 11    | firewir... | 3C4134E3B4 |
| 197b:2380 | 1025:0168 | JMicron... | IEEE 1394 Host Controller    | 11    | firewir... | 6872AE9FB4 |
| 197b:2380 | 1462:7646 | JMicron... | IEEE 1394 Host Controller    | 11    | firewir... | 2656CF8992 |
| 104c:8023 | 1849:8023 | Texas I... | TSB43AB22A IEEE-1394a-200... | 10    | firewir... | 4818C2EAE0 |
| 1106:3044 | 1462:309d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 10    | firewir... | FDED86E377 |
| 1106:3403 | 1462:7616 | VIA Tec... | VT6315 Series Firewire Co... | 10    | firewir... | CBD20C24D8 |
| 11c1:5811 | 8086:2035 | LSI        | FW322/323 [TrueFire] 1394... | 10    | firewir... | 391C101A92 |
| 197b:2380 | 2810:ac02 | JMicron... | IEEE 1394 Host Controller    | 10    | firewir... | 3549222788 |
| 104c:8023 |           | Texas I... | TSB43AB22A IEEE-1394a-200... | 9     | firewir... | 48187ACCDE |
| 104c:8023 | 103c:1306 | Texas I... | TSB43AB22A IEEE-1394a-200... | 9     | firewir... | 4299904C4D |
| 104c:8023 | 8086:4f43 | Texas I... | TSB43AB22A IEEE-1394a-200... | 9     | firewir... | 2E9A342427 |
| 104c:8024 | 1028:1000 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 9     | firewir... | 248C508EB0 |
| 104c:8235 | 5678:1234 | Texas I... | XIO2200A IEEE-1394a-2000 ... | 9     | firewir... | 28B6DC130A |
| 1106:3044 |           | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 9     | firewir... | 708CA8F58A |
| 11bd:0015 | 11bd:0023 | Pinnacl... | FireWire IEEE1394            | 9     | firewir... | B6D9B74951 |
| 11c1:5811 | 11bd:000e | LSI        | FW322/323 [TrueFire] 1394... | 9     | firewir... | 9149BE671F |
| 1033:00e7 | 1033:00ce | NEC Com... | uPD72873 [Firewarden] IEE... | 8     | firewir... | 8533331911 |
| 104c:8023 | 8086:424b | Texas I... | TSB43AB22A IEEE-1394a-200... | 8     | firewir... | FA1BE73A3F |
| 104c:8025 | 1458:1000 | Texas I... | TSB82AA2 IEEE-1394b Link ... | 8     | firewir... | 0CFD20F720 |
| 1106:3044 | 1025:0198 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 8     | firewir... | C1A57810E8 |
| 1106:3403 | 1025:0158 | VIA Tec... | VT6315 Series Firewire Co... | 8     | firewir... | 0FE52AFF1E |
| 1106:3403 | 1025:8010 | VIA Tec... | VT6315 Series Firewire Co... | 8     | firewir... | 719B6FFBE5 |
| 1106:3403 | 1462:640d | VIA Tec... | VT6315 Series Firewire Co... | 8     | firewir... | 5901E8C9E2 |
| 1106:3403 | 1462:751d | VIA Tec... | VT6315 Series Firewire Co... | 8     | firewir... | 947CDFD30B |
| 1106:3403 | 8086:4953 | VIA Tec... | VT6315 Series Firewire Co... | 8     | firewir... | 380F10F479 |
| 11c1:5811 | 1028:0249 | LSI        | FW322/323 [TrueFire] 1394... | 8     | firewir... | A3584CB8A9 |
| 11c1:5811 | 103c:2a34 | LSI        | FW322/323 [TrueFire] 1394... | 8     | firewir... | F8D3CA460A |
| 11c1:5811 | 103c:2a81 | LSI        | FW322/323 [TrueFire] 1394... | 8     | firewir... | 3A69706315 |
| 11c1:5811 | 1043:8259 | LSI        | FW322/323 [TrueFire] 1394... | 8     | firewir... | B5D2358B76 |
| 104c:8023 | 17aa:1023 | Texas I... | TSB43AB22A IEEE-1394a-200... | 7     | firewir... | EC9C58B54E |
| 104c:8024 | 105b:0c9e | Texas I... | TSB43AB23 IEEE-1394a-2000... | 7     | firewir... | 652ED79C86 |
| 104c:8024 | 11bd:000e | Texas I... | TSB43AB23 IEEE-1394a-2000... | 7     | firewir... | 214C59A169 |
| 104c:8024 | 1b5b:010a | Texas I... | TSB43AB23 IEEE-1394a-2000... | 7     | firewir... | F13BE12F60 |
| 1106:3044 | 00ff:9a01 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 7     | firewir... | 0F15DCBAA1 |
| 1106:3044 | 0574:086c | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 7     | firewir... | 66E6ADF1EC |

### Flash memory (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1524:0510 | 1524:0510 | ENE Tec... | CB710 Memory Card Reader ... | 2     | cb710      | 932FA70B29 |
| 1524:0510 | 1043:1724 | ENE Tec... | CB710 Memory Card Reader ... | 1     | cb710      | 9FE6163CA2 |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1451 | 1022:1451 | AMD        | Family 17h (Models 00h-0f... | 1434  |            | E52E9002D0 |
| 1002:5a23 | 1002:5a23 | AMD        | RD890S/RD990 I/O Memory M... | 464   |            | E648F33A2F |
| 1022:1419 | 1022:1419 | AMD        | Family 15h (Models 10h-1f... | 262   |            | 2BC95C7D30 |
| 1002:5a23 | 1462:7693 | AMD        | RD890S/RD990 I/O Memory M... | 151   |            | DEC7AC6A34 |
| 1022:1577 | 1022:1577 | AMD        | Family 15h (Models 60h-6f... | 133   |            | 5114976821 |
| 1022:1423 | 1022:1423 | AMD        | Family 15h (Models 30h-3f... | 61    |            | B676D9030A |
| 1022:1419 | 1462:7721 | AMD        | Family 15h (Models 10h-1f... | 55    |            | 69DA26C946 |
| 1022:1423 | 1462:7721 | AMD        | Family 15h (Models 30h-3f... | 39    |            | 3797338B82 |
| 1022:1423 | 1043:85cb | AMD        | Family 15h (Models 30h-3f... | 24    |            | 00C624B592 |
| 1002:5a23 | 1458:5000 | AMD        | RD890S/RD990 I/O Memory M... | 17    |            | FACB3C762D |
| 1002:5a23 | 1462:7640 | AMD        | RD890S/RD990 I/O Memory M... | 17    |            | 6FE8EFAC3A |
| 1022:1419 | 1462:7895 | AMD        | Family 15h (Models 10h-1f... | 15    |            | 4DC951C5ED |
| 1002:5a23 | 1462:7974 | AMD        | RD890S/RD990 I/O Memory M... | 11    |            | 854EEB3251 |
| 1022:1419 | 1043:8526 | AMD        | Family 15h (Models 10h-1f... | 9     |            | 4F9F3CBB83 |
| 1022:1423 | 1462:7895 | AMD        | Family 15h (Models 30h-3f... | 9     |            | 8CF59588A3 |
| 1022:1419 | 1019:7c8d | AMD        | Family 15h (Models 10h-1f... | 4     |            | F04221E5DE |
| 1022:1419 | 1025:070b | AMD        | Family 15h (Models 10h-1f... | 4     |            | C87047835B |
| 1022:1419 | 1462:7900 | AMD        | Family 15h (Models 10h-1f... | 3     |            | A0CBC39688 |
| 1022:1423 | 1462:7793 | AMD        | Family 15h (Models 30h-3f... | 2     |            | 709AAC26C8 |
| 8086:19a2 | 8086:19a2 | Intel      | Atom Processor C3000 Seri... | 2     |            | 2B7A8BA5FC |
| 1022:1419 | 17aa:36a0 | AMD        | Family 15h (Models 10h-1f... | 1     |            | BA1A484E84 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0412 | 1458:d000 | Intel      | Xeon E3-1200 v3/4th Gen C... | 452   | i915       | EB596B1774 |
| 10de:128b | 1462:8c93 | Nvidia     | GK208B [GeForce GT 710]      | 418   | nouveau    | 0233AE7054 |
| 8086:0412 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 304   | i915       | 2253D95E90 |
| 1002:67df | 1da2:e366 | AMD        | Ellesmere [Radeon RX 470/... | 254   | amdgpu     | 9FED362DDE |
| 8086:0102 | 1043:844d | Intel      | 2nd Generation Core Proce... | 225   | i915       | F31E6E3DD0 |
| 8086:0102 | 1458:d000 | Intel      | 2nd Generation Core Proce... | 211   | i915       | 9FC60B0BA8 |
| 1002:15d8 | 1002:15d8 | AMD        | Picasso                      | 206   | amdgpu     | 1FB86737FD |
| 1002:9616 | 1043:8388 | AMD        | RS780L [Radeon 3000]         | 199   | radeon     | 24FE21040D |
| 8086:1912 | 1043:8694 | Intel      | HD Graphics 530              | 193   | i915       | 07067FE66C |
| 1002:15dd | 1002:15dd | AMD        | Raven Ridge [Radeon Vega ... | 188   | amdgpu     | CF804488DD |
| 8086:0152 | 1458:d000 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 180   | i915       | 042607D7F1 |
| 1002:67df | 1682:c580 | AMD        | Ellesmere [Radeon RX 470/... | 161   | amdgpu     | 161865EDB0 |
| 8086:5912 | 1043:8694 | Intel      | HD Graphics 630              | 153   | i915       | BA3DDF870D |
| 10de:1d01 | 1462:8c98 | Nvidia     | GP108 [GeForce GT 1030]      | 149   | nvidia     | 9753F223E2 |
| 1002:67df | 1da2:e353 | AMD        | Ellesmere [Radeon RX 470/... | 145   | amdgpu     | C483A48272 |
| 10de:0a65 |           | Nvidia     | GT218 [GeForce 210]          | 143   | nouveau    | 0582E2316B |
| 10de:1c82 | 1462:8c96 | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 142   | nvidia     | E1B966B80D |
| 8086:29c2 | 1043:82b0 | Intel      | 82G33/G31 Express Integra... | 140   | i915       | EE4F0F6F02 |
| 8086:2e32 | 1043:836d | Intel      | 4 Series Chipset Integrat... | 137   | i915       | FEAC57A6E7 |
| 1002:9616 | 1458:d000 | AMD        | RS780L [Radeon 3000]         | 131   | radeon     | 545DC9A3E0 |
| 1002:67df | 1462:341b | AMD        | Ellesmere [Radeon RX 470/... | 129   | amdgpu     | 61823FB44E |
| 1002:15dd | 1043:876b | AMD        | Raven Ridge [Radeon Vega ... | 128   | amdgpu     | 19EBA77C24 |
| 10de:03d6 | 1849:03d6 | Nvidia     | C61 [GeForce 7025 / nForc... | 123   | nouveau    | 090662DCD6 |
| 8086:0152 | 1043:844d | Intel      | Xeon E3-1200 v2/3rd Gen C... | 123   | i915       | E8AD89CB87 |
| 1002:67df | 1462:3418 | AMD        | Ellesmere [Radeon RX 470/... | 122   | amdgpu     | 1F83ADD647 |
| 10de:0640 |           | Nvidia     | G96C [GeForce 9500 GT]       | 116   | nouveau    | 0F15DCBAA1 |
| 1002:15d8 | 1043:876b | AMD        | Picasso                      | 111   | amdgpu     | 24974BE67E |
| 8086:0162 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 111   | i915       | E59D042DA2 |
| 8086:0402 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 111   | i915       | 352946E177 |
| 8086:0402 | 1458:d000 | Intel      | Xeon E3-1200 v3/4th Gen C... | 111   | i915       | 5EAD0CA3AD |
| 8086:29c2 | 1458:d000 | Intel      | 82G33/G31 Express Integra... | 108   | i915       | 370AD865CF |
| 8086:0152 | 1028:0577 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 107   | i915       | 00FE3AD0A4 |
| 8086:041e | 1458:d000 | Intel      | 4th Generation Core Proce... | 107   | i915       | CE787D81EF |
| 8086:2e32 | 1458:d000 | Intel      | 4 Series Chipset Integrat... | 107   | i915       | E77D7B4B45 |
| 8086:2e12 | 1028:0420 | Intel      | 4 Series Chipset Integrat... | 106   | i915       | C67A8BB677 |
| 8086:2e13 | 1028:0420 | Intel      | 4 Series Chipset Integrat... | 106   |            | C67A8BB677 |
| 10de:0a65 | 1462:8094 | Nvidia     | GT218 [GeForce 210]          | 101   | nouveau    | D9C192EA8C |
| 10de:0622 |           | Nvidia     | G94 [GeForce 9600 GT]        | 100   | nouveau    | 1157C2A82C |
| 8086:0412 | 1849:0412 | Intel      | Xeon E3-1200 v3/4th Gen C... | 100   | i915       | 111E98DDEF |
| 8086:041e | 1043:8534 | Intel      | 4th Generation Core Proce... | 100   | i915       | 7A6479DC2D |
| 8086:3e92 | 1043:8694 | Intel      | CometLake-S GT2 [UHD Grap... | 99    | i915       | 9F69E439BC |
| 8086:0412 | 1028:05a4 | Intel      | Xeon E3-1200 v3/4th Gen C... | 98    | i915       | E04A41FC30 |
| 8086:2772 | 1043:817a | Intel      | 82945G/GZ Integrated Grap... | 97    | i915       | 6B722285DD |
| 10de:13c2 | 1462:3160 | Nvidia     | GM204 [GeForce GTX 970]      | 96    | nvidia     | 77006702F8 |
| 10de:0de0 |           | Nvidia     | GF108 [GeForce GT 440]       | 94    | nouveau    | 270399BF0D |
| 8086:0152 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 94    | i915       | 78D7AD575A |
| 8086:29c2 | 1849:29c2 | Intel      | 82G33/G31 Express Integra... | 94    | i915       | C36147B6A6 |
| 8086:3e92 | 1458:d000 | Intel      | CometLake-S GT2 [UHD Grap... | 94    | i915       | 8C2B6CF453 |
| 10de:0615 |           | Nvidia     | G92 [GeForce GTS 250]        | 90    | nvidia     | 585FF46BB3 |
| 10de:1380 | 1043:84bb | Nvidia     | GM107 [GeForce GTX 750 Ti]   | 90    | nvidia     | B2CBBC04B8 |
| 8086:1912 | 1458:d000 | Intel      | HD Graphics 530              | 90    | i915       | 36BF6DAB37 |
| 1002:68f9 | 174b:e164 | AMD        | Cedar [Radeon HD 5000/600... | 88    | radeon     | 48187ACCDE |
| 1002:731f | 1002:0b36 | AMD        | Navi 10 [Radeon RX 5600 O... | 88    | amdgpu     | C537345CE8 |
| 8086:5912 | 1458:d000 | Intel      | HD Graphics 630              | 88    | i915       | BF9F9E3BB5 |
| 10de:0f00 | 1569:0f00 | Nvidia     | GF108 [GeForce GT 630]       | 87    | nouveau    | 33EAFC06A0 |
| 10de:0614 |           | Nvidia     | G92 [GeForce 9800 GT]        | 86    | nouveau    | 996054B23C |
| 1002:6779 | 174b:e164 | AMD        | Caicos [Radeon HD 6450/74... | 85    | radeon     | 735015DCE2 |
| 10de:1c82 | 10de:1c82 | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 84    | nvidia     | BE8B71D264 |
| 10de:1244 |           | Nvidia     | GF116 [GeForce GTX 550 Ti]   | 83    | nouveau    | 9DEBDD654C |
| 10de:0ca3 |           | Nvidia     | GT215 [GeForce GT 240]       | 82    | nouveau    | 78FAFC3314 |
| 10de:13c2 | 1043:8508 | Nvidia     | GM204 [GeForce GTX 970]      | 79    | nvidia     | BA339B925B |
| 1002:67df | 1682:c570 | AMD        | Ellesmere [Radeon RX 470/... | 78    | amdgpu     | 90FE8A952C |
| 10de:128b | 10de:118b | Nvidia     | GK208B [GeForce GT 710]      | 78    | nvidia     | 51862605EF |
| 8086:0152 | 1849:0152 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 78    | i915       | F6F957DDF3 |
| 1002:6778 | 1028:2120 | AMD        | Caicos XT [Radeon HD 7470... | 77    | radeon     | 40DA7A8AE9 |
| 1002:699f | 1da2:e367 | AMD        | Lexa PRO [Radeon 540/540X... | 77    | amdgpu     | 8A6B85A2D2 |
| 10de:0de1 |           | Nvidia     | GF108 [GeForce GT 430]       | 77    | nouveau    | 69AC6E6156 |
| 1002:67df | 174b:e347 | AMD        | Ellesmere [Radeon RX 470/... | 76    | amdgpu     | 2DC6A1D295 |
| 8086:0102 | 1028:04ad | Intel      | 2nd Generation Core Proce... | 76    | i915       | D6237E9949 |
| 8086:0412 | 103c:1998 | Intel      | Xeon E3-1200 v3/4th Gen C... | 76    | i915       | B9E492678D |
| 10de:128b | 10de:128b | Nvidia     | GK208B [GeForce GT 710]      | 73    | nvidia     | E52E9002D0 |
| 8086:0102 | 1849:0102 | Intel      | 2nd Generation Core Proce... | 73    | i915       | C5E2E9E4A4 |
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 73    | i915       | 9333E233D6 |
| 1002:15dd | 1458:d000 | AMD        | Raven Ridge [Radeon Vega ... | 72    | amdgpu     | 4CB5912DB3 |
| 10de:11c0 | 1458:354e | Nvidia     | GK106 [GeForce GTX 660]      | 72    | nvidia     | 22A32FC3F2 |
| 10de:1c82 | 10de:11bf | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 72    | nvidia     | 2FF008A28D |
| 10de:1d01 | 1458:375c | Nvidia     | GP108 [GeForce GT 1030]      | 72    | nvidia     | C3479871D7 |
| 1002:731f | 1da2:e411 | AMD        | Navi 10 [Radeon RX 5600 O... | 71    | amdgpu     | 58E37C5D93 |
| 8086:0102 | 1028:04f5 | Intel      | 2nd Generation Core Proce... | 71    | i915       | 5131593DDF |
| 8086:0162 | 1849:0162 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 71    | i915       | 4E164A0A47 |
| 8086:2772 | 1458:d000 | Intel      | 82945G/GZ Integrated Grap... | 70    | i915       | 35D876D2DC |
| 8086:29b2 | 1028:0211 | Intel      | 82Q35 Express Integrated ... | 70    | i915       | 42BE865DC0 |
| 8086:29b3 | 1028:0211 | Intel      | 82Q35 Express Integrated ... | 70    |            | 42BE865DC0 |
| 8086:3e98 | 1043:8694 | Intel      | CoffeeLake-S GT2 [UHD Gra... | 69    | i915       | 22A32FC3F2 |
| 10de:0f00 | 1458:3544 | Nvidia     | GF108 [GeForce GT 630]       | 68    | nouveau    | 669CEF5A34 |
| 10de:128b | 1043:85e7 | Nvidia     | GK208B [GeForce GT 710]      | 68    | nvidia     | 6AD4929A33 |
| 1002:67df | 1da2:e387 | AMD        | Ellesmere [Radeon RX 470/... | 67    | amdgpu     | 7C56A7A321 |
| 8086:0162 | 1458:d000 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 67    | i915       | BB6DE8B3E0 |
| 10de:0a65 | 1458:3525 | Nvidia     | GT218 [GeForce 210]          | 65    | nouveau    | A5121E1871 |
| 10de:1c82 | 1462:3351 | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 64    | nvidia     | 6B0A992D9F |
| 8086:0102 | 103c:1495 | Intel      | 2nd Generation Core Proce... | 64    | i915       | E7C0F59F92 |
| 8086:2e12 | 1028:027f | Intel      | 4 Series Chipset Integrat... | 64    | i915       | AADCA45789 |
| 8086:2e13 | 1028:027f | Intel      | 4 Series Chipset Integrat... | 64    |            | AADCA45789 |
| 1002:15d8 | 1458:d000 | AMD        | Picasso                      | 63    | amdgpu     | B2D3620851 |
| 10de:1c81 | 1462:8c97 | Nvidia     | GP107 [GeForce GTX 1050]     | 63    | nvidia     | 70A2909C2D |
| 10de:0f02 | 1462:8a9f | Nvidia     | GF108 [GeForce GT 730]       | 62    | nouveau    | A031BFBDBF |
| 8086:0152 | 103c:3397 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 62    | i915       | BF9875C5AC |
| 10de:0fc6 | 1569:0fc6 | Nvidia     | GK107 [GeForce GTX 650]      | 61    | nouveau    | 9FC0813DDD |
| 10de:1c03 | 19da:1438 | Nvidia     | GP106 [GeForce GTX 1060 6GB] | 60    | nvidia     | 2C6CFC5B5A |
| 8086:3e98 | 1458:d000 | Intel      | CoffeeLake-S GT2 [UHD Gra... | 60    | i915       | 419E0C7EB2 |

### I/o card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10e8:80d8 |           | Applied... | PCI-7200 40MB/s 32-channe... | 1     |            | 3864E6C70F |

### Input device controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1102:7002 | 1102:0020 | Creativ... | SB Live! Game Port           | 179   | emu10k1_gp | 35D876D2DC |
| 1102:7003 | 1102:0040 | Creativ... | SB Audigy Game Port          | 127   | emu10k1_gp | 0E8D69E9B8 |
| 1102:7003 | 1102:0060 | Creativ... | SB Audigy Game Port          | 26    | emu10k1_gp | 4970AA3AFB |
| 1102:7004 | 1102:1003 | Creativ... | [SB Live! Value] Input de... | 10    | emu10k1_gp | 1661F6766F |
| 1319:0802 | 1319:1319 | Fortemedia | Xwave QS3000A [FM801 game... | 8     | fm801_gp   | CE881D4659 |
| 1102:7005 | 1102:1002 | Creativ... | SB Audigy LS Game Port       | 4     | emu10k1_gp | A0BD55A486 |
| 127a:4312 | 1235:4312 | Rockwel... | Riptide PCI Game Controller  | 1     | snd_rip... | 34867AD122 |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1481 | 1022:1481 | AMD        | Starship/Matisse IOMMU       | 1203  |            | 93DE1508CB |
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 942   |            | D3A9F1CE6E |
| 1022:1451 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 798   |            | 491D1A96CC |
| 1022:1481 | 1043:87c0 | AMD        | Starship/Matisse IOMMU       | 732   |            | 161865EDB0 |
| 1022:1481 | 1043:8808 | AMD        | Starship/Matisse IOMMU       | 163   |            | A525C8911B |
| 1022:15d1 | 1043:876b | AMD        | Raven/Raven2 IOMMU           | 111   |            | 24974BE67E |
| 1022:1481 | 1462:7c02 | AMD        | Starship/Matisse IOMMU       | 95    |            | 97620628A8 |
| 1022:1631 | 1022:1631 | AMD        | Renoir/Cezanne IOMMU         | 72    |            | A73FABCD4C |
| 1022:1481 | 1462:7b86 | AMD        | Starship/Matisse IOMMU       | 65    |            | 7E563A9D44 |
| 1022:1451 | 1462:7c02 | AMD        | Family 17h (Models 00h-0f... | 59    |            | F50B61B450 |
| 1022:1451 | 1462:7b86 | AMD        | Family 17h (Models 00h-0f... | 46    |            | F17090E5D2 |
| 1022:1481 | 1462:7c35 | AMD        | Starship/Matisse IOMMU       | 46    |            | 8EA75A2EC0 |
| 1022:1481 | 1462:7b89 | AMD        | Starship/Matisse IOMMU       | 45    |            | A72102FDB0 |
| 1022:1419 | 103c:1850 | AMD        | Family 15h (Models 10h-1f... | 38    |            | E8C750C4B9 |
| 1022:1481 | 1462:7a38 | AMD        | Starship/Matisse IOMMU       | 28    |            | 11F7EC8B16 |
| 1022:1451 | 1462:7a38 | AMD        | Family 17h (Models 00h-0f... | 27    |            | 276D5FE9E3 |
| 1022:1481 | 1462:7c94 | AMD        | Starship/Matisse IOMMU       | 26    |            | 08819513F2 |
| 1022:1631 | 1043:87e1 | AMD        | Renoir/Cezanne IOMMU         | 25    |            | 740C97FB1C |
| 1022:1451 | 1462:7b89 | AMD        | Family 17h (Models 00h-0f... | 24    |            | E8965C736D |
| 1022:1481 | 1043:87cb | AMD        | Starship/Matisse IOMMU       | 24    |            | 6E020F3AD1 |
| 1022:1481 | 1462:7c95 | AMD        | Starship/Matisse IOMMU       | 23    |            | D06DD7E0EC |
| 1022:1481 | 1462:7b85 | AMD        | Starship/Matisse IOMMU       | 20    |            | DB9BFA58F9 |
| 1022:1451 | 1462:7b85 | AMD        | Family 17h (Models 00h-0f... | 15    |            | 429525379A |
| 1022:1481 | 1043:87e2 | AMD        | Starship/Matisse IOMMU       | 14    |            | EE6DBC679C |
| 1022:1423 | 17aa:36a0 | AMD        | Family 15h (Models 30h-3f... | 13    |            | AFBB381CF3 |
| 1022:1451 | 1028:07ee | AMD        | Family 17h (Models 00h-0f... | 13    |            | 5256B07A63 |
| 1022:1577 | 17aa:364f | AMD        | Family 15h (Models 60h-6f... | 12    |            | 95EDC1D588 |
| 1022:1481 | 1462:7a40 | AMD        | Starship/Matisse IOMMU       | 11    |            | 1CA6C5085E |
| 1022:1631 | 1043:8809 | AMD        | Renoir/Cezanne IOMMU         | 11    |            | 2FF2EB607A |
| 1022:1451 | 1462:7a40 | AMD        | Family 17h (Models 00h-0f... | 10    |            | 89BF33DB93 |
| 1022:1423 | 103c:2215 | AMD        | Family 15h (Models 30h-3f... | 9     |            | B0B56138B2 |
| 1022:1577 | 1043:8719 | AMD        | Family 15h (Models 60h-6f... | 8     |            | 8A607B7D4E |
| 1022:1419 | 1462:7793 | AMD        | Family 15h (Models 10h-1f... | 7     |            | 1C7A02BD63 |
| 1022:1423 | 1025:0904 | AMD        | Family 15h (Models 30h-3f... | 7     |            | 77B62F0563 |
| 1022:15d1 | 1462:7b86 | AMD        | Raven/Raven2 IOMMU           | 7     |            | 7CF3758630 |
| 1022:1419 | 1019:7c90 | AMD        | Family 15h (Models 10h-1f... | 6     |            | 4D0AC6A6A2 |
| 1022:1451 | 1028:089a | AMD        | Family 17h (Models 00h-0f... | 6     |            | 12F62738E6 |
| 1022:1451 | 1462:7b87 | AMD        | Family 17h (Models 00h-0f... | 6     |            | 18FF34F941 |
| 1022:1481 | 1462:7c34 | AMD        | Starship/Matisse IOMMU       | 6     |            | 1440E244F6 |
| 1022:1481 | 17aa:1046 | AMD        | Starship/Matisse IOMMU       | 6     |            | 136C409F1A |
| 1022:1577 | 17aa:3100 | AMD        | Family 15h (Models 60h-6f... | 6     |            | BBFCF94452 |
| 1022:1419 | 103c:2215 | AMD        | Family 15h (Models 10h-1f... | 5     |            | 406F93D79E |
| 1022:1419 | 1462:7891 | AMD        | Family 15h (Models 10h-1f... | 5     |            | 0AC16F856D |
| 1022:1567 | 1022:1567 | AMD        | Mullins IOMMU                | 5     |            | C8A3D807BB |
| 1022:1451 | 1462:7b90 | AMD        | Family 17h (Models 00h-0f... | 4     |            | 3642F15AB7 |
| 1022:1481 | 1028:098e | AMD        | Starship/Matisse IOMMU       | 4     |            | E1BC8D1CDD |
| 1022:1481 | 1043:8815 | AMD        | Starship/Matisse IOMMU       | 4     |            | 8F7011B085 |
| 1022:1481 | 1462:7b87 | AMD        | Starship/Matisse IOMMU       | 4     |            | 58A277F8E4 |
| 1022:1481 | 1462:7c36 | AMD        | Starship/Matisse IOMMU       | 4     |            | 26B69278F1 |
| 1022:15d1 | 1462:7a38 | AMD        | Raven/Raven2 IOMMU           | 4     |            | 9A1463FD59 |
| 1022:15d1 | 1462:7c02 | AMD        | Raven/Raven2 IOMMU           | 4     |            | EBD09EC38B |
| 8086:1f16 | 1849:1f16 | Intel      | Atom processor C2000 RCEC    | 4     |            | F539EA8A66 |
| 1022:1423 | 1462:7900 | AMD        | Family 15h (Models 30h-3f... | 3     |            | 930993FD14 |
| 1022:1481 | 1462:7c96 | AMD        | Starship/Matisse IOMMU       | 3     |            | EB1233376B |
| 1022:1631 | 1462:7b89 | AMD        | Renoir/Cezanne IOMMU         | 3     |            | 0107E8FC03 |
| 1022:1631 | 1462:7c94 | AMD        | Renoir/Cezanne IOMMU         | 3     |            | 07E9EE8610 |
| 1022:1631 | 1462:7c95 | AMD        | Renoir/Cezanne IOMMU         | 3     |            | B806A146D2 |
| 1002:5a23 | 1462:7893 | AMD        | RD890S/RD990 I/O Memory M... | 2     |            | C67DD69EA3 |
| 1022:1419 | 1019:9ac9 | AMD        | Family 15h (Models 10h-1f... | 2     |            | E5938AFD2B |
| 1022:1423 | 1462:7891 | AMD        | Family 15h (Models 30h-3f... | 2     |            | A2AB595336 |
| 1022:1481 | 1028:0a8b | AMD        | Starship/Matisse IOMMU       | 2     |            | 5EA23EBFB2 |
| 1022:1481 | 1043:1c81 | AMD        | Starship/Matisse IOMMU       | 2     |            | 66B9CEA0F2 |
| 1022:1481 | 1043:8747 | AMD        | Starship/Matisse IOMMU       | 2     |            | 249D6291CB |
| 1022:1481 | 1849:1481 | AMD        | Starship/Matisse IOMMU       | 2     |            | 49A0EEC9F5 |
| 1022:15d1 | 1019:a4cd | AMD        | Raven/Raven2 IOMMU           | 2     |            | 8EB8144AEB |
| 1022:15d1 | 1462:7a40 | AMD        | Raven/Raven2 IOMMU           | 2     |            | AA41662477 |
| 1022:15d1 | 1462:7b85 | AMD        | Raven/Raven2 IOMMU           | 2     |            | 0548F9650B |
| 1022:15d1 | 1462:7b89 | AMD        | Raven/Raven2 IOMMU           | 2     |            | CADB142111 |
| 1022:15d1 | 17aa:3141 | AMD        | Raven/Raven2 IOMMU           | 2     |            | 82058974D9 |
| 1022:1631 | 1458:1000 | AMD        | Renoir/Cezanne IOMMU         | 2     |            | 68DA5F41B2 |
| 1022:1419 | 1019:7c6f | AMD        | Family 15h (Models 10h-1f... | 1     |            | 783674FDBD |
| 1022:1419 | 1019:7e42 | AMD        | Family 15h (Models 10h-1f... | 1     |            | B08197DF02 |
| 1022:1419 | 1019:9a62 | AMD        | Family 15h (Models 10h-1f... | 1     |            | DF6385E8C2 |
| 1022:1419 | 1462:7913 | AMD        | Family 15h (Models 10h-1f... | 1     |            | 1306310E52 |
| 1022:1419 | 1462:7a83 | AMD        | Family 15h (Models 10h-1f... | 1     |            | 614F005109 |
| 1022:1419 | 17aa:3089 | AMD        | Family 15h (Models 10h-1f... | 1     |            | 1F90A5A2C6 |
| 1022:1423 | 1019:99d3 | AMD        | Family 15h (Models 30h-3f... | 1     |            | CFCBE45B0D |
| 1022:1423 | 1019:9a18 | AMD        | Family 15h (Models 30h-3f... | 1     |            | C24F9ED7E2 |
| 1022:1423 | 1019:9a62 | AMD        | Family 15h (Models 30h-3f... | 1     |            | 06FB58E8EE |
| 1022:1423 | 1019:9ac9 | AMD        | Family 15h (Models 30h-3f... | 1     |            | BED1921035 |
| 1022:1423 | 1019:9aed | AMD        | Family 15h (Models 30h-3f... | 1     |            | 9D69618F17 |
| 1022:1423 | 1019:9bcd | AMD        | Family 15h (Models 30h-3f... | 1     |            | BEF78AFCA1 |
| 1022:1423 | 103c:225e | AMD        | Family 15h (Models 30h-3f... | 1     |            | EADAD0EB90 |
| 1022:1423 | 1462:7903 | AMD        | Family 15h (Models 30h-3f... | 1     |            | EADCB61E9F |
| 1022:1423 | 1462:7913 | AMD        | Family 15h (Models 30h-3f... | 1     |            | A04C671F0B |
| 1022:1423 | 1462:7969 | AMD        | Family 15h (Models 30h-3f... | 1     |            | A2599D7FFB |
| 1022:1437 | 1022:1437 | AMD        | Liverpool I/O Memory Mana... | 1     |            | 2FB1797D3D |
| 1022:1451 | 1019:9ce5 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 06776696F3 |
| 1022:1451 | 1019:9d10 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 277BBC0E9E |
| 1022:1451 | 1019:a412 | AMD        | Family 17h (Models 00h-0f... | 1     |            | C47BA626E7 |
| 1022:1451 | 1019:a4cd | AMD        | Family 17h (Models 00h-0f... | 1     |            | 8106DDD47F |
| 1022:1451 | 103c:8433 | AMD        | Family 17h (Models 00h-0f... | 1     |            | B079CCB608 |
| 1022:1451 | 1462:7c95 | AMD        | Family 17h (Models 00h-0f... | 1     |            | F1A1A21C56 |
| 1022:1451 | 17aa:3141 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 78DD9729FA |
| 1022:1451 | 17aa:36e1 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 31F5158C61 |
| 1022:1481 | 1043:1bf1 | AMD        | Starship/Matisse IOMMU       | 1     |            | 65E2923B50 |
| 1022:1481 | 1462:7c87 | AMD        | Starship/Matisse IOMMU       | 1     |            | 33B88D17A8 |
| 1022:1481 | 17aa:3148 | AMD        | Starship/Matisse IOMMU       | 1     |            | 77A1D53114 |
| 1022:1577 | 1462:7895 | AMD        | Family 15h (Models 60h-6f... | 1     |            | A2AA184709 |
| 1022:15d1 | 1462:7c87 | AMD        | Raven/Raven2 IOMMU           | 1     |            | 91F401BD7C |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816c | 103c:8464 | Realtek... | RTL8111xP IPMI interface     | 6     |            | 7964501CA5 |
| 10ec:816c | 10ec:0123 | Realtek... | RTL8111xP IPMI interface     | 4     |            | C1C5847225 |
| 10ec:816c | 1849:8168 | Realtek... | RTL8111xP IPMI interface     | 4     | ipmi_si    | 9032E4C08A |
| 10ec:816c | 1025:080a | Realtek... | RTL8111xP IPMI interface     | 3     |            | C486FBF03F |
| 10ec:816c | 1025:1248 | Realtek... | RTL8111xP IPMI interface     | 3     |            | 7EE989172F |
| 10ec:816c | 103c:8463 | Realtek... | RTL8111xP IPMI interface     | 3     |            | F378108DC3 |
| 10ec:816c | 1019:81ea | Realtek... | RTL8111xP IPMI interface     | 2     |            | DF6385E8C2 |
| 10ec:816c | 103c:8461 | Realtek... | RTL8111xP IPMI interface     | 2     |            | 991B8A8A71 |
| 10ec:816c | 103c:8618 | Realtek... | RTL8111xP IPMI interface     | 2     |            | A021BE4E84 |
| 10ec:816c | 103c:8626 | Realtek... | RTL8111xP IPMI interface     | 2     |            | E92FA74B31 |
| 10ec:816c | 17aa:30fd | Realtek... | RTL8111xP IPMI interface     | 2     |            | C694A13B5A |
| 10ec:816c | 1025:078d | Realtek... | RTL8111xP IPMI interface     | 1     |            | 504EC0D230 |
| 10ec:816c | 1025:1005 | Realtek... | RTL8111xP IPMI interface     | 1     |            | 8A65F68E82 |
| 10ec:816c | 1025:1180 | Realtek... | RTL8111xP IPMI interface     | 1     |            | 90D9292ABE |
| 10ec:816c | 1025:124c | Realtek... | RTL8111xP IPMI interface     | 1     |            | 8EB6F7795D |
| 10ec:816c | 1734:1216 | Realtek... | RTL8111xP IPMI interface     | 1     |            | A960AEF3AE |
| 10ec:816c | 17aa:3141 | Realtek... | RTL8111xP IPMI interface     | 1     |            | F19B15E3D2 |
| 10ec:816c | 1b0a:00e5 | Realtek... | RTL8111xP IPMI interface     | 1     |            | 3DA36F7282 |
| 8086:108e | 1734:108d | Intel      | 82573E KCS (Active Manage... | 1     | ipmi_si    | CCA0170CC9 |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 103c:3302 | 103c:3305 | Hewlett... | Integrated Lights-Out Sta... | 22    | ipmi_si    | 9753F223E2 |
| 10ec:816c | 10ec:8168 | Realtek... | RTL8111xP IPMI interface     | 22    | ipmi_si    | 07A5B3C465 |
| 10ec:816c | 1458:e000 | Realtek... | RTL8111xP IPMI interface     | 11    | ipmi_si    | 3D75B079F5 |
| 10ec:816c | 17aa:3089 | Realtek... | RTL8111xP IPMI interface     | 10    | ipmi_si    | 2891FE25E6 |
| 10ec:816c | 1734:1178 | Realtek... | RTL8111xP IPMI interface     | 8     | ipmi_si    | B07993A438 |
| 8086:108e | 8086:0000 | Intel      | 82573E KCS (Active Manage... | 6     | ipmi_si    | 2ACFD9617B |
| 10ec:816c | 1025:078b | Realtek... | RTL8111xP IPMI interface     | 5     |            | 1FB7EBE327 |
| 10ec:816c | 17aa:30b2 | Realtek... | RTL8111xP IPMI interface     | 2     | ipmi_si    | 4A0A83693B |
| 10ec:816c | 1043:8578 | Realtek... | RTL8111xP IPMI interface     | 1     | ipmi_si    | C248800623 |
| 10ec:816c | 10ec:816c | Realtek... | RTL8111xP IPMI interface     | 1     |            | A3ECB14C0C |

### Isdn adapter (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1244:0e00 | 1244:0e00 | AVM        | Fritz!Card PCI v2.0 ISDN     | 10    | fcpci      | C9B84C12B7 |
| 1244:0a00 | 1244:0a00 | AVM        | A1 ISDN [Fritz]              | 8     | fcpci      | 98C67DA00D |
| 1133:e00b | 1133:e00b | Dialogic   | Diva ISDN PCI 2.02           | 1     |            | AC7FD78AB8 |
| 1397:2bd0 | 1075:c101 | Cologne... | ISDN network controller [... | 1     | hfcpci     | BE977291B5 |
| 1397:2bd0 | 1397:2bd0 | Cologne... | ISDN network controller [... | 1     | hfcpci     | 83A7C8B23F |
| e159:0001 | 795e:0001 | Tiger J... | Tiger3XX Modem/ISDN inter... | 1     | wcte11xp   | FE13415AC0 |
| e159:0001 | 79fe:0001 | Tiger J... | Tiger3XX Modem/ISDN inter... | 1     | wcte11xp   | B6E88B98F7 |
| e159:0001 | 9100:0001 | Tiger J... | Tiger3XX Modem/ISDN inter... | 1     | netjet     | 74F31779A2 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a121 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 753   |            | 427C8B8D8F |
| 8086:a36f | 8086:7270 | Intel      | Cannon Lake PCH Shared SRAM  | 651   |            | 2FC377709D |
| 8086:a2a1 | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 460   |            | 381023907E |
| 8086:a2a1 | 1458:5001 | Intel      | 200 Series/Z370 Chipset F... | 430   |            | 8C2B6CF453 |
| 10de:03f5 | 1849:03eb | Nvidia     | MCP61 Memory Controller      | 425   |            | 0F23350175 |
| 8086:a121 | 1458:5001 | Intel      | 100 Series/C230 Series Ch... | 420   |            | 36BF6DAB37 |
| 10de:03e2 | 1849:03e2 | Nvidia     | MCP61 Host Bridge            | 390   |            | 0F23350175 |
| 8086:a36f | 1043:8694 | Intel      | Cannon Lake PCH Shared SRAM  | 374   |            | 22A32FC3F2 |
| 10de:03f5 | 1458:0c11 | Nvidia     | MCP61 Memory Controller      | 213   |            | 701EE8CE26 |
| 8086:a121 | 1849:a121 | Intel      | 100 Series/C230 Series Ch... | 205   |            | 6B4C3F811B |
| 8086:a2a1 | 1849:a2a1 | Intel      | 200 Series/Z370 Chipset F... | 178   |            | 79E6EF3655 |
| 10de:03e2 | 1043:83a4 | Nvidia     | MCP61 Host Bridge            | 158   |            | 324F6E5FAD |
| 10de:03f5 | 1043:83a4 | Nvidia     | MCP61 Memory Controller      | 158   |            | 324F6E5FAD |
| 8086:a2a1 | 1043:872f | Intel      | 200 Series/Z370 Chipset F... | 158   |            | F60A34FE5C |
| 10de:03ea | 10de:cb84 | Nvidia     | MCP61 Memory Controller      | 133   |            | 0A4D7FB95D |
| 10de:03ea | 1043:8234 | Nvidia     | MCP61 Memory Controller      | 124   |            | 91FE7919BE |
| 10de:03f5 | 1043:8234 | Nvidia     | MCP61 Memory Controller      | 124   |            | 91FE7919BE |
| 8086:a36f | 1849:a36f | Intel      | Cannon Lake PCH Shared SRAM  | 124   |            | 2FF008A28D |
| 8086:06ef | 8086:7270 | Intel      | Comet Lake PCH Shared SRAM   | 114   |            | 5B55E39C35 |
| 10de:03ea | 1458:5001 | Nvidia     | MCP61 Memory Controller      | 113   |            | 7076F55128 |
| 10de:03e2 | 1458:5001 | Nvidia     | MCP61 Host Bridge            | 100   |            | 701EE8CE26 |
| 10de:005e | 1043:815a | Nvidia     | CK804 Memory Controller      | 97    |            | F9BFF20C4D |
| 8086:a3a1 | 1043:8694 | Intel      | Memory controller            | 82    |            | 7B62AD7C35 |
| 8086:06ef | 1043:8694 | Intel      | Comet Lake PCH Shared SRAM   | 79    |            | CAFC4421B2 |
| 10de:03f5 | 1462:7309 | Nvidia     | MCP61 Memory Controller      | 77    |            | 0A4D7FB95D |
| 8086:43ef |           | Intel      | Tiger Lake-H Shared SRAM     | 77    |            | BE8B71D264 |
| 8086:a121 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 71    |            | EC7609239E |
| 10de:0568 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 66    |            | 9005621271 |
| 10de:0751 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 66    |            | 9005621271 |
| 10de:0754 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 66    |            | 9005621271 |
| 10de:03f5 | 1565:3407 | Nvidia     | MCP61 Memory Controller      | 64    |            | E16A5113BA |
| 10de:0369 | 1043:8239 | Nvidia     | MCP55 Memory Controller      | 56    |            | DFA80F4B9F |
| 10de:03a9 |           | Nvidia     | C55 Memory Controller        | 56    |            | C11BD1C981 |
| 10de:03aa |           | Nvidia     | C55 Memory Controller        | 56    |            | C11BD1C981 |
| 10de:03ab |           | Nvidia     | C55 Memory Controller        | 56    |            | C11BD1C981 |
| 10de:03b4 |           | Nvidia     | C55 Memory Controller        | 56    |            | C11BD1C981 |
| 10de:03bc |           | Nvidia     | C55 Memory Controller        | 56    |            | C11BD1C981 |
| 10de:03a8 |           | Nvidia     | C55 Memory Controller        | 54    |            | C11BD1C981 |
| 10de:03ac |           | Nvidia     | C55 Memory Controller        | 54    |            | C11BD1C981 |
| 10de:03ad |           | Nvidia     | C55 Memory Controller        | 54    |            | C11BD1C981 |
| 10de:03ae |           | Nvidia     | C55 Memory Controller        | 54    |            | C11BD1C981 |
| 10de:03af |           | Nvidia     | C55 Memory Controller        | 54    |            | C11BD1C981 |
| 10de:03b0 |           | Nvidia     | C55 Memory Controller        | 54    |            | C11BD1C981 |
| 10de:03b1 |           | Nvidia     | C55 Memory Controller        | 54    |            | C11BD1C981 |
| 10de:03b2 |           | Nvidia     | C55 Memory Controller        | 54    |            | C11BD1C981 |
| 10de:03b3 |           | Nvidia     | C55 Memory Controller        | 54    |            | C11BD1C981 |
| 10de:03b5 |           | Nvidia     | C55 Memory Controller        | 54    |            | C11BD1C981 |
| 10de:03b6 |           | Nvidia     | C55 Memory Controller        | 54    |            | C11BD1C981 |
| 10de:03ba |           | Nvidia     | C55 Memory Controller        | 54    |            | C11BD1C981 |
| 8086:a121 | 1734:121d | Intel      | 100 Series/C230 Series Ch... | 52    |            | C3479871D7 |
| 8086:9d21 | 8086:7270 | Intel      | Sunrise Point-LP PMC         | 49    |            | B5BD43E606 |
| 10de:0444 | 1462:7369 | Nvidia     | MCP65 Memory Controller      | 48    |            | 0C6668DEE5 |
| 10de:0445 | 1462:7369 | Nvidia     | MCP65 Memory Controller      | 48    |            | 0C6668DEE5 |
| 10de:0568 |           | Nvidia     | MCP78S [GeForce 8200] Mem... | 47    |            | 6B6D198B0D |
| 10de:0751 | 10de:cb84 | Nvidia     | MCP78S [GeForce 8200] Mem... | 47    |            | 6B6D198B0D |
| 8086:a121 | 1462:7a15 | Intel      | 100 Series/C230 Series Ch... | 47    |            | 059A06E95C |
| 8086:43ef | 1043:8694 | Intel      | Tiger Lake-H Shared SRAM     | 46    |            | B9C2FEC8AA |
| 8086:06ef | 1849:06ef | Intel      | Comet Lake PCH Shared SRAM   | 44    |            | AD42FA5D08 |
| 8086:a121 | 1028:06b9 | Intel      | 100 Series/C230 Series Ch... | 44    |            | 92F15AEB4D |
| 8086:a121 | 1462:7971 | Intel      | 100 Series/C230 Series Ch... | 44    |            | 77006702F8 |
| 10de:027e | 10de:027e | Nvidia     | C51 Memory Controller 2      | 43    |            | 8117A9BD4F |
| 10de:027f | 10de:027f | Nvidia     | C51 Memory Controller 3      | 43    |            | 8117A9BD4F |
| 10de:02f8 | 10de:02f8 | Nvidia     | C51 Memory Controller 5      | 43    |            | 8117A9BD4F |
| 10de:02f9 | 10de:02f9 | Nvidia     | C51 Memory Controller 4      | 43    |            | 8117A9BD4F |
| 10de:02fa | 10de:02fa | Nvidia     | C51 Memory Controller 0      | 43    |            | 8117A9BD4F |
| 10de:02fe | 10de:02fe | Nvidia     | C51 Memory Controller 1      | 43    |            | 8117A9BD4F |
| 10de:02ff | 10de:02ff | Nvidia     | C51 Host Bridge              | 43    |            | 8117A9BD4F |
| 8086:a2a1 | 1043:873c | Intel      | 200 Series/Z370 Chipset F... | 43    |            | EACC1E3F66 |
| 10de:03ea | 103c:2a6c | Nvidia     | MCP61 Memory Controller      | 42    |            | 929E48A398 |
| 10de:03f5 | 103c:2a6c | Nvidia     | MCP61 Memory Controller      | 42    |            | 929E48A398 |
| 10de:03ea | 103c:2a99 | Nvidia     | MCP61 Memory Controller      | 39    |            | 29FD6EAE29 |
| 10de:03f5 | 103c:2a99 | Nvidia     | MCP61 Memory Controller      | 39    |            | 29FD6EAE29 |
| 10de:03f5 | 1462:7597 | Nvidia     | MCP61 Memory Controller      | 38    |            | 79851E843C |
| 10de:0568 | 1849:0568 | Nvidia     | MCP78S [GeForce 8200] Mem... | 37    |            | E817658118 |
| 10de:0751 | 1849:0751 | Nvidia     | MCP78S [GeForce 8200] Mem... | 37    |            | E817658118 |
| 10de:0754 | 1849:0754 | Nvidia     | MCP78S [GeForce 8200] Mem... | 37    |            | E817658118 |
| 10de:0270 | 1043:81bc | Nvidia     | MCP51 Host Bridge            | 36    |            | AB314D65BE |
| 10de:0270 | 10de:cb84 | Nvidia     | MCP51 Host Bridge            | 35    |            | 5058172A35 |
| 10de:03ea | 1025:0394 | Nvidia     | MCP61 Memory Controller      | 35    |            | 9DA4BEFF51 |
| 10de:03ea | 1849:03ea | Nvidia     | MCP61 Memory Controller      | 35    |            | A78F46A907 |
| 10de:03f5 | 1025:0394 | Nvidia     | MCP61 Memory Controller      | 35    |            | 9DA4BEFF51 |
| 8086:a36f | 1025:1238 | Intel      | Cannon Lake PCH Shared SRAM  | 35    |            | B961168B44 |
| 8086:a3a1 | 1458:5001 | Intel      | Memory controller            | 35    |            | D3AA74A821 |
| 10de:02f0 | 10de:02f0 | Nvidia     | C51 Host Bridge              | 30    |            | 5058172A35 |
| 10de:0272 | 1043:81bc | Nvidia     | MCP51 Memory Controller 0    | 29    |            | AB314D65BE |
| 8086:a2a1 | 1028:07a3 | Intel      | 200 Series/Z370 Chipset F... | 29    |            | 9D38BA75C7 |
| 8086:a3a1 | 1849:a3a1 | Intel      | Memory controller            | 29    |            | B9DEC327EE |
| 10de:03ea | 1565:3407 | Nvidia     | MCP61 Memory Controller      | 28    |            | 1EAE78EEC0 |
| 8086:a2a1 | 1462:7a70 | Intel      | 200 Series/Z370 Chipset F... | 28    |            | D6BE998202 |
| 8086:a2a1 | 1028:07a1 | Intel      | 200 Series/Z370 Chipset F... | 27    |            | E221C43AF2 |
| 10de:0369 | 1458:5001 | Nvidia     | MCP55 Memory Controller      | 26    |            | E55AF94449 |
| 8086:a2a1 | 103c:82f2 | Intel      | 200 Series/Z370 Chipset F... | 26    |            | FEF1D213B4 |
| 10de:0270 | 1043:81c0 | Nvidia     | MCP51 Host Bridge            | 25    |            | 19BDD9712D |
| 10de:0272 | 1043:81c0 | Nvidia     | MCP51 Memory Controller 0    | 23    |            | 19BDD9712D |
| 10de:027e | 1043:81c0 | Nvidia     | C51 Memory Controller 2      | 23    |            | 19BDD9712D |
| 10de:027f | 1043:81c0 | Nvidia     | C51 Memory Controller 3      | 23    |            | 19BDD9712D |
| 10de:02f0 | 1043:81c0 | Nvidia     | C51 Host Bridge              | 23    |            | 19BDD9712D |
| 10de:02f8 | 1043:81c0 | Nvidia     | C51 Memory Controller 5      | 23    |            | 19BDD9712D |
| 10de:02f9 | 1043:81c0 | Nvidia     | C51 Memory Controller 4      | 23    |            | 19BDD9712D |
| 10de:02fe | 1043:81c0 | Nvidia     | C51 Memory Controller 1      | 23    |            | 19BDD9712D |

### Modem (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1057:3052 | 1057:3020 | Motorola   | SM56 Data Fax Modem          | 24    |            | D342F4E0A4 |
| 1106:3068 |           | VIA Tec... | AC'97 Modem Controller       | 18    | snd_via... | B38568681E |
| 11c1:044c | 11c1:044c | LSI        | LT WinModem                  | 15    |            | 7CA677A33C |
| 8086:1040 | 8086:1000 | Intel      | 536EP Data Fax Modem         | 7     |            | F2CC8FAE4D |
| 1106:3068 | 1019:0c04 | VIA Tec... | AC'97 Modem Controller       | 4     | snd_via... | CAAB4A3B82 |
| 134d:7892 | 134d:0001 | PCTel      | HSP MicroModem 56            | 4     | serial     | 6C9B4F5E0B |
| 1543:3052 | 1543:3000 | SILICON... | Intel 537 [Winmodem]         | 4     |            | B6ADDF8D7B |
| 11c1:0440 | 11c1:0440 | LSI        | 56k WinModem                 | 3     |            | 2700C74BD9 |
| 1039:7013 | 1584:4003 | Silicon... | AC'97 Modem Controller       | 2     |            | E9BC9B3C8A |
| 11c1:044e | 11c1:044e | LSI        | LT WinModem                  | 2     |            | DA6AB84289 |
| 11c1:044e | 1235:044e | LSI        | LT WinModem                  | 2     |            | C22EB5394A |
| 134d:7890 | 134d:0001 | PCTel      | HSP MicroModem 56            | 2     | serial     | 332DDF27C1 |
| 2003:8800 | 1801:2800 | Smart Link | LM-I56N                      | 2     |            | 62AFB6C0F6 |
| 8086:1080 | 1028:1000 | Intel      | FA82537EP 56K V.92 Data/F... | 2     | serial     | DC13BE448C |
| 8086:27dd |           | Intel      | 82801G (ICH7 Family) AC'9... | 2     |            | 78AA035121 |
| 1002:4378 | 103c:3085 | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 46E47F957D |
| 1039:7013 | 1025:0083 | Silicon... | AC'97 Modem Controller       | 1     |            | 985DA6D3F5 |
| 1039:7013 | 104d:8128 | Silicon... | AC'97 Modem Controller       | 1     | snd_int... | 72A578315E |
| 1039:7013 | 1631:3003 | Silicon... | AC'97 Modem Controller       | 1     | snd_int... | A787298BDB |
| 1057:3052 | 1631:3034 | Motorola   | SM56 Data Fax Modem          | 1     |            | B7CEC1644D |
| 10b9:5457 | 10cf:130f | ULi Ele... | M5457 AC'97 Modem Controller | 1     |            | 347EB6B747 |
| 10b9:5459 | 10a5:5459 | ULi Ele... | SmartLink SmartPCI561 56K... | 1     | serial     | CA657531E4 |
| 10b9:545a | 2020:545a | ULi Ele... | SmartLink SmartPCI563 56K... | 1     | serial     | 2A51E0D9E9 |
| 1106:3068 | 1019:2122 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 25BB71984B |
| 11c1:0449 | 1468:0410 | LSI        | L56xM+S [Mars-2] WinModem... | 1     |            | A8A13EFBA0 |
| 11c1:044e | 11c1:044c | LSI        | LT WinModem                  | 1     |            | 885DC78EF1 |
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

### Multimedia (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 0002:8290 | 0004:0000 |            |                              | 1     |            | 95D420F37F |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15e2 | 1022:15e2 | AMD        | Raven/Raven2/FireFlight/R... | 55    | snd_pci... | 72CE248D0C |
| 109e:0878 |           | Brooktree  | Bt878 Audio Capture          | 26    |            | 2B61653CEA |
| 11bd:bede | 11bd:0022 | Pinnacl... | AV/DV Studio Capture Card    | 18    |            | 6CA0293F8E |
| 1022:15e2 | 103c:8433 | AMD        | Raven/Raven2/FireFlight/R... | 17    | snd_pci... | 6183F8775B |
| 109e:0878 | 1461:0003 | Brooktree  | Bt878 Audio Capture          | 15    | snd_bt87x  | 59D57FE423 |
| 1131:7164 | 0070:8851 | Philips... | SAA7164                      | 15    | saa7164    | 75B8BCA0FA |
| 109e:0878 | 0070:13eb | Brooktree  | Bt878 Audio Capture          | 10    | snd_bt87x  | 65649C54D6 |
| 1131:7160 | 1461:1455 | Philips... | SAA7160                      | 10    |            | 2D08F702CF |
| 12ab:0380 | 1cfa:0006 | YUAN Hi... | Game Capture 4K60 Pro        | 10    |            | 6C2BD4DFA4 |
| 1822:4e35 | 1ae4:0003 | Twinhan... | Mantis DTV PCI Bridge Con... | 9     | mantis     | B82FC3C9C2 |
| 1131:7231 | 16be:0008 | Philips... | SAA7231                      | 8     |            | 29ECAF9382 |
| 1131:7231 | 5ace:8000 | Philips... | SAA7231                      | 8     |            | FA070462FC |
| 11bd:bede | 11bd:0023 | Pinnacl... | AV/DV Studio Capture Card    | 8     |            | B6D9B74951 |
| 1822:4e35 | 153b:1178 | Twinhan... | Mantis DTV PCI Bridge Con... | 8     | mantis     | EC6B248EBE |
| 1022:15e2 | 103c:8434 | AMD        | Raven/Raven2/FireFlight/R... | 7     | snd_pci... | 61C3E3852A |
| 1131:7164 | 0070:f111 | Philips... | SAA7164                      | 7     | saa7164    | 4E9DFE2B4B |
| 8086:22b8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 7     | intel_a... | A059116962 |
| 1022:15e2 | 17aa:3708 | AMD        | Raven/Raven2/FireFlight/R... | 6     | snd_pci... | A7D8D3CF71 |
| 109e:0878 | 107d:6609 | Brooktree  | Bt878 Audio Capture          | 6     |            | 31DFECDF4A |
| 1131:7231 | 1461:1400 | Philips... | SAA7231                      | 6     |            | 70C319B3C6 |
| 1822:4e35 | 1ae4:0002 | Twinhan... | Mantis DTV PCI Bridge Con... | 6     | mantis     | CE787D81EF |
| 8086:5a88 |           | Intel      | Celeron N3350/Pentium N42... | 6     |            | 7C30C0C3CA |
| 109e:0878 | 107d:6606 | Brooktree  | Bt878 Audio Capture          | 5     | snd_bt87x  | 89FD130FF2 |
| 109e:0878 | 11bd:0012 | Brooktree  | Bt878 Audio Capture          | 5     | snd_bt87x  | 237CA98302 |
| 1131:7160 | 1ae4:0700 | Philips... | SAA7160                      | 5     |            | 3B43D9B42F |
| 1131:7231 | 16be:0013 | Philips... | SAA7231                      | 5     |            | FD68D44A6A |
| 14f1:8804 | 0070:1402 | Conexan... | CX23880/1/2/3 PCI Video a... | 5     |            | BC782F5E67 |
| 14f1:8804 | 0070:6902 | Conexan... | CX23880/1/2/3 PCI Video a... | 5     |            | C9F48C1D32 |
| 14f1:8804 | 0070:9002 | Conexan... | CX23880/1/2/3 PCI Video a... | 5     |            | 1351C7B098 |
| 1745:3000 | 0070:d180 | ViXS Sy... | Colossus Encoder             | 5     |            | 4AB2137534 |
| 1822:4e35 | 153b:1179 | Twinhan... | Mantis DTV PCI Bridge Con... | 5     | mantis     | 225F795531 |
| 109e:0878 | bd11:1200 | Brooktree  | Bt878 Audio Capture          | 4     | snd_bt87x  | C7B95D7362 |
| 109e:0878 | ffff:ffff | Brooktree  | Bt878 Audio Capture          | 4     |            | 32413546CE |
| 1131:7160 | 1131:0002 | Philips... | SAA7160                      | 4     |            | 0861B33243 |
| 1131:7162 | 11bd:0100 | Philips... | SAA7162                      | 4     |            | D495DD5272 |
| 1131:7162 | 11bd:0101 | Philips... | SAA7162                      | 4     |            | 3C6DF0441A |
| 1131:7231 | 1461:7983 | Philips... | SAA7231                      | 4     |            | 4365F32962 |
| 1131:7231 | 16be:0002 | Philips... | SAA7231                      | 4     |            | 751F3FAAFA |
| 14e4:1615 | 14e4:1615 | Broadcom   | BCM70015 Video Decoder [C... | 4     |            | 490A799D8B |
| 14f1:8804 | 0070:9202 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     |            | 3323601EEF |
| 1002:4d51 | 1002:b041 | AMD        | Unified AVStream             | 3     |            | E0EE188631 |
| 1002:ac12 | 1002:b935 | AMD        | Theater HD T507 (DVB-T) T... | 3     |            | B4CD2CBC1E |
| 1002:ac12 | 12ab:0003 | AMD        | Theater HD T507 (DVB-T) T... | 3     |            | 4E3343DADF |
| 1002:ad18 | 1682:ad18 | AMD        | Multimedia controller        | 3     |            | 829182B838 |
| 1022:15e2 | 1849:15e2 | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | FD95402AA1 |
| 1057:3410 | ecc0:0100 | Motorola   | DSP56361 Digital Signal P... | 3     | snd_echo3g | 162ADDF6E2 |
| 109e:0878 | 107d:6607 | Brooktree  | Bt878 Audio Capture          | 3     | bt878      | 502C4EB91B |
| 109e:0878 | 1554:4011 | Brooktree  | Bt878 Audio Capture          | 3     | snd_bt87x  | 6E3E7E3E30 |
| 10ee:222a | ef11:ddd5 | Xilinx     | Multimedia controller        | 3     | earth_pt1  | A5B2555CC2 |
| 1131:7160 | 1461:0955 | Philips... | SAA7160                      | 3     |            | 62A7B004A4 |
| 1131:7160 | 1461:0f55 | Philips... | SAA7160                      | 3     |            | 7985ADDC49 |
| 1131:7160 | 1461:2655 | Philips... | SAA7160                      | 3     |            | A74B989748 |
| 1131:7164 | 185b:e900 | Philips... | SAA7164                      | 3     | saa7164    | 879303C98C |
| 1131:7231 | 12ab:0763 | Philips... | SAA7231                      | 3     |            | 20768D0E33 |
| 1131:7231 | 5ace:8201 | Philips... | SAA7231                      | 3     |            | 75F255A4E2 |
| 14e4:1615 | 105b:0d77 | Broadcom   | BCM70015 Video Decoder [C... | 3     |            | B036D312E6 |
| 14f1:8804 | 0070:6906 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     |            | 4281E009BB |
| 14f1:8804 | 0070:9402 | Conexan... | CX23880/1/2/3 PCI Video a... | 3     |            | 0A7AB4D43E |
| 1797:6805 |           | Intersi... | HV4000 DVR card              | 3     |            | 8496A00774 |
| 1822:4e35 | 1822:0031 | Twinhan... | Mantis DTV PCI Bridge Con... | 3     | mantis     | 24636D8ED6 |
| 1a00:0001 | 1a00:0001 |            | Multimedia controller        | 3     |            | 9FAFE2C548 |
| 1057:1801 |           | Motorola   | DSP56301 Digital Signal P... | 2     |            | BA572256B0 |
| 109e:0878 | 1002:0003 | Brooktree  | Bt878 Audio Capture          | 2     |            | B03897D3E4 |
| 109e:0878 | 1461:0004 | Brooktree  | Bt878 Audio Capture          | 2     |            | F2B7867CAA |
| 109e:0878 | 1852:1852 | Brooktree  | Bt878 Audio Capture          | 2     |            | C560D2AA9B |
| 109e:0878 | 800a:763d | Brooktree  | Bt878 Audio Capture          | 2     |            | 14B2C1FB89 |
| 109e:0878 | 800b:763d | Brooktree  | Bt878 Audio Capture          | 2     |            | 14B2C1FB89 |
| 109e:0878 | 800c:763d | Brooktree  | Bt878 Audio Capture          | 2     |            | 14B2C1FB89 |
| 109e:0878 | 800d:763d | Brooktree  | Bt878 Audio Capture          | 2     |            | 14B2C1FB89 |
| 1131:7160 | 1043:48b5 | Philips... | SAA7160                      | 2     |            | 6B30DD9FF7 |
| 1131:7160 | 1461:0855 | Philips... | SAA7160                      | 2     |            | BBDA8BED86 |
| 1131:7160 | 1461:0e55 | Philips... | SAA7160                      | 2     |            | 08CED52205 |
| 1131:7160 | 1461:1855 | Philips... | SAA7160                      | 2     |            | FA070462FC |
| 1131:7160 | 1461:7561 | Philips... | SAA7160                      | 2     |            | 1CBEE8A7EF |
| 1131:7160 | 185b:e750 | Philips... | SAA7160                      | 2     |            | 262A709D45 |
| 1131:7160 | 6281:0001 | Philips... | SAA7160                      | 2     | saa716x... | 624E92E15E |
| 1131:7160 | 6928:0001 | Philips... | SAA7160                      | 2     |            | 6FC3B2D35D |
| 1131:7160 | 6928:0002 | Philips... | SAA7160                      | 2     |            | 2F7F236AF3 |
| 1131:7164 | 0070:8891 | Philips... | SAA7164                      | 2     | saa7164    | B70598FB63 |
| 1131:7164 | 0070:8940 | Philips... | SAA7164                      | 2     | saa7164    | 3FF4A460A2 |
| 1131:7164 | 0070:f120 | Philips... | SAA7164                      | 2     | saa7164    | EB55E9A1CD |
| 1131:7231 | 0070:0810 | Philips... | SAA7231                      | 2     |            | 6CB625FE85 |
| 1131:7231 | 0070:49d1 | Philips... | SAA7231                      | 2     |            | 48CC7F548E |
| 1131:7231 | 1461:2a0f | Philips... | SAA7231                      | 2     |            | BEB8F313F7 |
| 1131:7231 | 1461:7981 | Philips... | SAA7231                      | 2     |            | 928BFFA7DF |
| 1131:7231 | 1461:890f | Philips... | SAA7231                      | 2     |            | D5EB8C32FB |
| 1131:7231 | 1b0a:3001 | Philips... | SAA7231                      | 2     |            | 380D5AB9F0 |
| 1131:7231 | 5ace:8150 | Philips... | SAA7231                      | 2     |            | 8603D5BDF5 |
| 116e:00d0 | 116e:0000 | Electro... | Multimedia controller        | 2     |            | 7823D71E26 |
| 116e:0600 | 116e:0012 | Electro... | Multimedia controller        | 2     |            | 7823D71E26 |
| 11bd:0040 | 11bd:0045 | Pinnacl... | Royal TS Function 1          | 2     |            | 7793E267F5 |
| 11bd:0041 | 11bd:0045 | Pinnacl... | RoyalTS Function 2           | 2     |            | 7793E267F5 |
| 11bd:0042 | 11bd:0045 | Pinnacl... | Royal TS Function 3          | 2     |            | 7793E267F5 |
| 12ab:0371 | 1cfa:000b | YUAN Hi... | Game Capture 4K60 Pro        | 2     |            | 508BC3DCEE |
| 12ab:0371 | 1cfa:000c | YUAN Hi... | Game Capture 4K60 Pro        | 2     |            | 508BC3DCEE |
| 14b5:0600 | 14b5:0600 | Creamware  | Pulsar2                      | 2     |            | 176A2484A2 |
| 14f1:8804 | 1822:0023 | Conexan... | CX23880/1/2/3 PCI Video a... | 2     |            | AB36F565A4 |
| 1797:6814 | 000a:6814 | Intersi... | TW6816 multimedia video c... | 2     |            | D455CC3322 |
| 1797:6815 | 000a:6815 | Intersi... | TW6816 multimedia video c... | 2     |            | D455CC3322 |
| 1797:6816 | 000a:6816 | Intersi... | TW6816 multimedia video c... | 2     |            | D455CC3322 |

### Multiport serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1fd4:1999 | 1fd4:0002 | SUNIX      | Multiport serial controller  | 7     | serial     | DF6B2FA3DE |
| 135a:08c1 | 135a:0413 | Brain B... | Multiport serial controller  | 1     |            | 0F6EBD3E93 |
| 135c:0170 | 135c:0170 | Quatech    | QSCLP-100                    | 1     | serial     | 05DF269988 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8168 | 1458:e000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5922  | r8169      | E52E9002D0 |
| 10ec:8168 | 1849:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2569  | r8169      | 42CD4D28BD |
| 10ec:8168 | 1043:8677 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1885  | r8169      | 24974BE67E |
| 10ec:8168 | 1043:8505 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1704  | r8169      | 1BB97BC7DF |
| 10ec:8168 | 1043:8432 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1272  | r8169      | 278873FF66 |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 817   | r8169      | 6978CD209F |
| 8086:15b8 | 1043:8672 | Intel      | Ethernet Connection (2) I... | 762   | e1000e     | 427C8B8D8F |
| 10ec:8168 | 1043:8554 | Realtek... | RTL8111/8168/8411 PCI Exp... | 721   | r8169      | 735015DCE2 |
| 10ec:8139 | 10ec:8139 | Realtek... | RTL-8100/8101L/8139 PCI F... | 694   | 8139too... | 892069341E |
| 10ec:8168 | 1043:83a3 | Realtek... | RTL8111/8168/8411 PCI Exp... | 579   | r8169      | 4E4391F329 |
| 10ec:8168 | 1043:859e | Realtek... | RTL8111/8168/8411 PCI Exp... | 454   | r8169      | F7CE357637 |
| 1969:1048 | 1043:8226 | Qualcom... | Attansic L1 Gigabit Ethernet | 368   | atl1       | D7FBB47C8B |
| 8086:15a1 | 1043:85c4 | Intel      | Ethernet Connection (2) I... | 346   | e1000e     | 5A5D3A54C3 |
| 8086:15b8 | 1458:e000 | Intel      | Ethernet Connection (2) I... | 343   | e1000e     | DD22D96D07 |
| 10ec:8168 | 7470:3468 | Realtek... | RTL8111/8168/8411 PCI Exp... | 329   | r8169      | 7A70FC2989 |
| 1969:1083 | 1458:e000 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 317   | atl1c      | F493A9D83B |
| 11ab:4364 | 1043:81f8 | Marvell... | 88E8056 PCI-E Gigabit Eth... | 294   | sky2       | 6C7ECC284B |
| 10ec:8169 | 10ec:8169 | Realtek... | RTL8169 PCI Gigabit Ether... | 293   | r8169      | DFA80F4B9F |
| 8086:15b8 | 1849:15b8 | Intel      | Ethernet Connection (2) I... | 278   | e1000e     | 5130E7EC94 |
| 10ec:8136 | 10ec:0123 | Realtek... | RTL810xE PCI Express Fast... | 271   | r8169      | 6978CD209F |
| 10ec:8168 | 1043:82c6 | Realtek... | RTL8111/8168/8411 PCI Exp... | 245   | r8169      | A0BD55A486 |
| 10ec:8136 | 1849:8136 | Realtek... | RTL810xE PCI Express Fast... | 241   | r8169      | C96A2AA7A8 |
| 8086:15bc | 1043:8672 | Intel      | Ethernet Connection (7) I... | 233   | e1000e     | 22A32FC3F2 |
| 1969:1091 | 1458:e000 | Qualcom... | AR8161 Gigabit Ethernet      | 219   | alx        | FB7BEB9612 |
| 10ec:8168 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 211   | r8169      | 5E80D808A1 |
| 1106:3106 | 1186:1405 | VIA Tec... | VT6105/VT6106S [Rhine-III]   | 204   | via_rhine  | 8A6B85A2D2 |
| 8086:15bc | 1458:e000 | Intel      | Ethernet Connection (7) I... | 197   | e1000e     | 1C2A383C4F |
| 8086:153b | 1458:e000 | Intel      | Ethernet Connection I217-V   | 193   | e1000e     | CE787D81EF |
| 8086:153a | 1028:05a4 | Intel      | Ethernet Connection I217-LM  | 185   | e1000e     | 827CB9A77A |
| 10ec:8168 | 1043:87c3 | Realtek... | RTL8111/8168/8411 PCI Exp... | 183   | r8169      | A525C8911B |
| 1969:1026 | 1043:8304 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 181   | atl1e      | 97A2C9D098 |
| 10ec:8168 | 1462:7817 | Realtek... | RTL8111/8168/8411 PCI Exp... | 180   | r8169      | 0420EDF711 |
| 8086:15f3 | 1043:87d2 | Intel      | Ethernet Controller I225-V   | 179   | igc        | 82E27C0415 |
| 10ec:8168 | 1462:7c37 | Realtek... | RTL8111/8168/8411 PCI Exp... | 176   | r8169      | 6B0A992D9F |
| 10ec:8168 | 1025:8000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 172   | r8169      | 01DBF1B5EC |
| 10ec:8168 | 1462:7c02 | Realtek... | RTL8111/8168/8411 PCI Exp... | 172   | r8169      | 97620628A8 |
| 11ab:4320 | 1043:811a | Marvell... | 88E8001 Gigabit Ethernet ... | 150   | skge       | 1739E3B05D |
| 10ec:8136 | 1043:8347 | Realtek... | RTL810xE PCI Express Fast... | 146   | r8169      | 1D5227420F |
| 10ec:8168 | 1462:7721 | Realtek... | RTL8111/8168/8411 PCI Exp... | 141   | r8169      | 69DA26C946 |
| 8086:153b | 1043:859f | Intel      | Ethernet Connection I217-V   | 141   | e1000e     | F6DE3176E5 |
| 10ec:8168 | 1043:81aa | Realtek... | RTL8111/8168/8411 PCI Exp... | 139   | r8169      | 1207B5D281 |
| 10ec:8168 | 1462:7b86 | Realtek... | RTL8111/8168/8411 PCI Exp... | 129   | r8169      | 7E563A9D44 |
| 1969:1026 | 1043:8226 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 126   | atl1e      | F6317B60DD |
| 1969:e091 | 1458:e000 | Qualcom... | Killer E220x Gigabit Ethe... | 126   | alx        | 9A9B258736 |
| 1969:10a1 | 1849:10a1 | Qualcom... | QCA8171 Gigabit Ethernet     | 125   | alx        | B676D9030A |
| 14e4:16b1 | 1849:96b1 | Broadcom   | NetLink BCM57781 Gigabit ... | 118   | tg3        | F6F957DDF3 |
| 8086:15a1 | 1849:15a1 | Intel      | Ethernet Connection (2) I... | 117   | e1000e     | 2BF61F2EC6 |
| 1969:2048 | 1043:8233 | Qualcom... | Attansic L2 Fast Ethernet    | 116   | atl2       | 1FF7B16CE4 |
| 10ec:8168 | 1462:7a38 | Realtek... | RTL8111/8168/8411 PCI Exp... | 110   | r8169      | 11F7EC8B16 |
| 1969:1026 | 1043:831c | Qualcom... | AR8121/AR8113/AR8114 Giga... | 110   | atl1e      | 01EC64F498 |
| 10ec:8125 | 1043:879b | Realtek... | RTL8125 2.5GbE Controller    | 105   | r8169      | 36B667DA98 |
| 10ec:8168 | 1043:8367 | Realtek... | RTL8111/8168/8411 PCI Exp... | 104   | r8169      | 36C4B84F94 |
| 1186:4300 | 1186:4300 | D-Link ... | DGE-528T Gigabit Ethernet... | 104   | r8169      | F1B8348661 |
| 1969:1063 | 1043:83fe | Qualcom... | AR8131 Gigabit Ethernet      | 103   | atl1c      | 4E4E73BA37 |
| 1969:1063 | 1458:e000 | Qualcom... | AR8131 Gigabit Ethernet      | 101   | atl1c      | 23B6458508 |
| 8086:15bc | 1849:15bc | Intel      | Ethernet Connection (7) I... | 101   | e1000e     | 2FF008A28D |
| 10ec:8168 | 1028:0612 | Realtek... | RTL8111/8168/8411 PCI Exp... | 99    | r8169      | 990123A52D |
| 10ec:8168 | 1462:7b79 | Realtek... | RTL8111/8168/8411 PCI Exp... | 97    | r8169      | 93FBAD33CF |
| 10ec:8168 | 1028:04f5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 93    | r8169      | 5131593DDF |
| 1969:2062 | 1849:2062 | Qualcom... | AR8152 v2.0 Fast Ethernet    | 92    | atl1c      | 452A28E8FA |
| 10ec:8168 | 1462:7693 | Realtek... | RTL8111/8168/8411 PCI Exp... | 91    | r8169      | A2227F49D9 |
| 1969:e0b1 | 1458:e000 | Qualcom... | Killer E2500 Gigabit Ethe... | 91    | alx        | 922C8C2994 |
| 10ec:8168 | 1565:2312 | Realtek... | RTL8111/8168/8411 PCI Exp... | 90    | r8169      | 3141B2E460 |
| 1969:10a1 | 1043:8587 | Qualcom... | QCA8171 Gigabit Ethernet     | 88    | alx        | AF6AE24A4E |
| 10ec:8167 | 1458:e000 | Realtek... | RTL-8110SC/8169SC Gigabit... | 87    | r8169      | F00A0A0903 |
| 10ec:8168 | 1462:7a34 | Realtek... | RTL8111/8168/8411 PCI Exp... | 87    | r8169      | A119D97189 |
| 10ec:8168 | 1019:8116 | Realtek... | RTL8111/8168/8411 PCI Exp... | 86    | r8169      | 3D23100553 |
| 8086:153a | 103c:1998 | Intel      | Ethernet Connection I217-LM  | 86    | e1000e     | B9E492678D |
| 10ec:8168 | 1019:811e | Realtek... | RTL8111/8168/8411 PCI Exp... | 85    | r8169      | 27E84ACA95 |
| 10ec:8168 | 1462:7b89 | Realtek... | RTL8111/8168/8411 PCI Exp... | 83    | r8169      | CADB142111 |
| 8086:153b | 1849:153b | Intel      | Ethernet Connection I217-V   | 83    | e1000e     | 2EC87A3F6F |
| 10ec:8168 | 103c:2abf | Realtek... | RTL8111/8168/8411 PCI Exp... | 81    | r8169      | 380D5AB9F0 |
| 10ec:8167 | 1043:820d | Realtek... | RTL-8110SC/8169SC Gigabit... | 80    | r8169      | 5947903D48 |
| 14e4:167a | 1028:01da | Broadcom   | NetXtreme BCM5754 Gigabit... | 76    | tg3        | 07965413DB |
| 10ec:8168 | 1028:0585 | Realtek... | RTL8111/8168/8411 PCI Exp... | 75    | r8169      | E766BCBB62 |
| 11ab:4362 | 1043:8142 | Marvell... | 88E8053 PCI-E Gigabit Eth... | 75    | sky2       | 1739E3B05D |
| 1969:1083 | 1849:1083 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 74    | atl1c      | 625A58F05C |
| 14e4:1681 | 103c:3047 | Broadcom   | NetXtreme BCM5761 Gigabit... | 72    | tg3        | EEDAB3769C |
| 10ec:8168 | 1462:7996 | Realtek... | RTL8111/8168/8411 PCI Exp... | 70    | r8169      | EC7609239E |
| 10ec:8168 | 1462:7758 | Realtek... | RTL8111/8168/8411 PCI Exp... | 69    | r8169      | 28F89C8DCF |
| 10ec:8168 | 1043:8385 | Realtek... | RTL8111/8168/8411 PCI Exp... | 67    | r8169      | 75B8BCA0FA |
| 8086:153a | 103c:18e7 | Intel      | Ethernet Connection I217-LM  | 67    | e1000e     | 94C750BA4B |
| 14e4:1677 | 1028:01ad | Broadcom   | NetXtreme BCM5751 Gigabit... | 66    | tg3        | 79FDFFE8EC |
| 10ec:8168 | 103c:2a9c | Realtek... | RTL8111/8168/8411 PCI Exp... | 65    | r8169      | 2F752A1A3E |
| 10ec:8168 | 17aa:3098 | Realtek... | RTL8111/8168/8411 PCI Exp... | 65    | r8169      | 718011BC1A |
| 14e4:1681 | 1028:0293 | Broadcom   | NetXtreme BCM5761 Gigabit... | 65    | tg3        | 0E66D5FD62 |
| 10ec:8168 | 1462:7641 | Realtek... | RTL8111/8168/8411 PCI Exp... | 63    | r8169      | 1161AF8368 |
| 10ec:8168 | 8086:d608 | Realtek... | RTL8111/8168/8411 PCI Exp... | 63    | r8169      | 7CA61CA6E1 |
| 1969:1091 | 1043:8507 | Qualcom... | AR8161 Gigabit Ethernet      | 63    | alx        | F98CCE15A3 |
| 13f0:0200 | 13f0:0201 | Sundanc... | IC Plus IP100A Integrated... | 62    | sundance   | 3AA8308F22 |
| 1969:1083 | 1043:847e | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 62    | atl1c      | 9A9EFF1A0F |
| 10ec:8168 | 103c:2a6f | Realtek... | RTL8111/8168/8411 PCI Exp... | 60    | r8169      | D5D1B22B75 |
| 1969:e091 | 1462:7693 | Qualcom... | Killer E220x Gigabit Ethe... | 59    | alx        | DEC7AC6A34 |
| 8086:107c | 8086:1376 | Intel      | 82541PI Gigabit Ethernet ... | 59    | e1000      | 5E80D808A1 |
| 10ec:8168 | 1462:7850 | Realtek... | RTL8111/8168/8411 PCI Exp... | 58    | r8169      | 5CA8BBD80D |
| 10ec:8136 | 1019:8348 | Realtek... | RTL810xE PCI Express Fast... | 57    | r8169      | 2EA8E79AA2 |
| 1969:e0a1 | 1458:e000 | Qualcom... | Killer E2400 Gigabit Ethe... | 56    | alx        | C67B0490D7 |
| 10ec:8168 | 1565:2400 | Realtek... | RTL8111/8168/8411 PCI Exp... | 55    | r8169      | BC5B7A2417 |
| 8086:1096 | 8086:3499 | Intel      | 80003ES2LAN Gigabit Ether... | 53    | e1000e     | FCC82222D9 |
| 8086:15a0 | 103c:2129 | Intel      | Ethernet Connection (2) I... | 53    | e1000e     | 9D2A807F08 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2723 | 8086:0084 | Intel      | Wi-Fi 6 AX200                | 1253  | iwlwifi    | EACC1E3F66 |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 621   | iwlwifi    | C537345CE8 |
| 8086:2526 | 8086:0014 | Intel      | Wireless-AC 9260             | 415   | iwlwifi    | 27E29303BC |
| 168c:002e | 168c:30a4 | Qualcom... | AR9287 Wireless Network A... | 222   | ath9k      | D04DAE2A56 |
| 168c:0032 | 168c:3118 | Qualcom... | AR9485 Wireless Network A... | 202   | ath9k      | 0FFE725912 |
| 8086:a370 | 8086:0034 | Intel      | Cannon Lake PCH CNVi WiFi    | 201   | iwlwifi    | 2FC377709D |
| 168c:0030 | 168c:3112 | Qualcom... | AR93xx Wireless Network A... | 167   | ath9k      | 8D74DD99C7 |
| 14e4:43a0 | 14e4:0619 | Broadcom   | BCM4360 802.11ac Wireless... | 158   | wl         | 9DA822B1B7 |
| 10ec:818b | 10ec:8196 | Realtek... | RTL8192EE PCIe Wireless N... | 151   | rtl8192ee  | 111E98DDEF |
| 168c:002d | 168c:0300 | Qualcom... | AR9227 Wireless Network A... | 143   | ath9k      | 669CEF5A34 |
| 8086:08b1 | 8086:4070 | Intel      | Wireless 7260                | 128   | iwlwifi    | 1BB97BC7DF |
| 168c:002d | 168c:0301 | Qualcom... | AR9227 Wireless Network A... | 123   | ath9k      | 4E19DF8E3C |
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 123   | iwlwifi    | 7054E3C5D2 |
| 8086:24f3 | 8086:0010 | Intel      | Wireless 8260                | 118   | iwlwifi    | 6E020F3AD1 |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 116   | rtl8821ce  | 6183F8775B |
| 10ec:b822 | 1043:8746 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 110   | r8822be    | DE600DC6CC |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 96    | iwlwifi    | 9D4EDC7252 |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 94    | iwlwifi    | 707F27E3E8 |
| 8086:06f0 | 8086:0074 | Intel      | Comet Lake PCH CNVi WiFi     | 82    | iwlwifi    | 5B55E39C35 |
| 10ec:8179 | 10ec:8197 | Realtek... | RTL8188EE Wireless Networ... | 78    | rtl8188ee  | 059A06E95C |
| 10ec:8178 | 1043:84b6 | Realtek... | RTL8192CE PCIe Wireless N... | 72    | rtl8192ce  | E8CF16B696 |
| 168c:0032 | 1028:0209 | Qualcom... | AR9485 Wireless Network A... | 72    | ath9k      | 17BAA8DC0E |
| 1814:5390 | 1814:f051 | Ralink     | RT5390 Wireless 802.11n 1... | 71    | rt2800pci  | D19235C3D0 |
| 10ec:8185 | 10ec:8225 | Realtek... | RTL-8185 IEEE 802.11a/b/g... | 68    | rtl818x... | B9C8253944 |
| 168c:0034 | 11ad:6621 | Qualcom... | AR9462 Wireless Network A... | 68    | ath9k      | 943617D620 |
| 1814:3090 | 11ad:7601 | Ralink     | RT3090 Wireless 802.11n 1... | 68    | rt2800pci  | 94C750BA4B |
| 168c:002b | 168c:30a1 | Qualcom... | AR9285 Wireless Network A... | 65    | ath9k      | 8BC230F7DC |
| 1814:3060 | 1186:3c04 | Ralink     | RT3060 Wireless 802.11n 1... | 65    | rt2800pci  | 7223BFA184 |
| 168c:0032 | 1043:850d | Qualcom... | AR9485 Wireless Network A... | 63    | ath9k      | 8D2D37223F |
| 10ec:8176 | 1043:84b5 | Realtek... | RTL8188CE 802.11b/g/n WiF... | 62    | rtl8192ce  | A4BF9808A8 |
| 8086:08b3 | 8086:8070 | Intel      | Wireless 3160                | 62    | iwlwifi    | 7A2742F439 |
| 14e4:43a0 | 1043:85df | Broadcom   | BCM4360 802.11ac Wireless... | 61    | wl         | B396E1C4F4 |
| 14e4:43b1 | 1043:855c | Broadcom   | BCM4352 802.11ac Wireless... | 61    | wl         | C49552F889 |
| 168c:0032 | 1028:0208 | Qualcom... | AR9485 Wireless Network A... | 60    | ath9k      | F90352C29F |
| 1814:0301 | 1814:2561 | Ralink     | RT2561/RT61 802.11g PCI      | 58    | rt61pci    | 53439ED943 |
| 8086:a370 | 8086:02a4 | Intel      | Cannon Lake PCH CNVi WiFi    | 58    | iwlwifi    | B961168B44 |
| 168c:0036 | 1028:020c | Qualcom... | QCA9565 / AR9565 Wireless... | 57    | ath9k      | 287D0004F3 |
| 168c:0013 | 1186:3a13 | Qualcom... | AR5212/5213/2414 Wireless... | 56    | ath5k      | 30E50BF019 |
| 168c:003e | 1043:86cd | Qualcom... | QCA6174 802.11ac Wireless... | 53    | ath10k_pci | A6B5188018 |
| 1814:3090 | 11ad:6632 | Ralink     | RT3090 Wireless 802.11n 1... | 53    | rt2800pci  | A47442AA1F |
| 10ec:8821 | 1a3b:2161 | Realtek... | RTL8821AE 802.11ac PCIe W... | 51    | rtl8821ae  | A99608BC0C |
| 168c:0036 | 1028:020e | Qualcom... | QCA9565 / AR9565 Wireless... | 51    | ath9k      | 95530DB3A8 |
| 1814:5360 | 1186:3c05 | Ralink     | RT5360 Wireless 802.11n 1... | 49    | rt2800pci  | 3DDE09D211 |
| 8086:24f3 | 8086:1010 | Intel      | Wireless 8260                | 49    | iwlwifi    | 1FCE457AC6 |
| 14e4:43a0 | 1043:8659 | Broadcom   | BCM4360 802.11ac Wireless... | 48    | wl         | D3A4772E4E |
| 14e4:43b1 | 1043:85ba | Broadcom   | BCM4352 802.11ac Wireless... | 47    | wl         | E387360B0B |
| 1814:0302 | 1186:3a71 | Ralink     | RT2561/RT61 rev B 802.11g    | 47    | rt61pci    | 830837B611 |
| 1814:0781 | 11ad:7600 | Ralink     | RT2790 Wireless 802.11n 1... | 47    | rt2800pci  | FDA18DABD0 |
| 168c:0042 | 1028:1810 | Qualcom... | QCA9377 802.11ac Wireless... | 44    | ath10k_pci | 6F2F7D7453 |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 44    | iwlwifi    | 49E564CB99 |
| 8086:3165 | 8086:4410 | Intel      | Wireless 3165                | 43    | iwlwifi    | 7C99A6ED29 |
| 10ec:8812 | 1043:86dd | Realtek... | RTL8812AE 802.11ac PCIe W... | 41    | rtl8821ae  | 7E7D21D8AE |
| 10ec:8812 | 10ec:8203 | Realtek... | RTL8812AE 802.11ac PCIe W... | 40    | rtl8821ae  | 0EABE998D2 |
| 14e4:4359 | 1043:850c | Broadcom   | BCM43228 802.11a/b/g/n       | 40    | wl         | 59C26CD33A |
| 8086:2725 | 8086:0024 | Intel      | Wi-Fi 6 AX210/AX211/AX411... | 40    | iwlwifi    | B9C2FEC8AA |
| 10ec:8176 | 10ec:8176 | Realtek... | RTL8188CE 802.11b/g/n WiF... | 38    | rtl8192ce  | A2D8CC587D |
| 1814:0302 | 1186:3c09 | Ralink     | RT2561/RT61 rev B 802.11g    | 38    | rt61pci    | ADF114D66E |
| 1814:539b | 103c:18ed | Ralink     | RT5390R 802.11bgn PCIe Wi... | 38    | rt2800pci  | 70AE8E4CDF |
| 168c:001d | 168c:2055 | Qualcom... | AR2417 Wireless Network A... | 37    | ath5k      | 8E02BB30BC |
| 168c:002b | 1a3b:1089 | Qualcom... | AR9285 Wireless Network A... | 35    | ath9k      | 8DFD1C0952 |
| 14e4:43a0 | 106b:0111 | Broadcom   | BCM4360 802.11ac Wireless... | 34    | wl         | B8A7B6080F |
| 168c:0032 | 103c:1838 | Qualcom... | AR9485 Wireless Network A... | 34    | ath9k      | BCC3CE52A5 |
| 8086:0887 | 8086:4062 | Intel      | Centrino Wireless-N 2230     | 33    | iwlwifi    | F1633C1E6C |
| 14e4:432b | 106b:008e | Broadcom   | BCM4322 802.11a/b/g/n Wir... | 32    | wl         | EA3E45A8A7 |
| 1814:3062 | 1814:3062 | Ralink     | RT3062 Wireless 802.11n 2... | 32    | rt2800pci  | A02538183C |
| 10ec:818b | 10ec:818b | Realtek... | RTL8192EE PCIe Wireless N... | 31    | rtl8192ee  | 3134454D4F |
| 168c:0034 | 1043:850e | Qualcom... | AR9462 Wireless Network A... | 31    | ath9k      | 6BB186C28B |
| 168c:003e | 1a56:1535 | Qualcom... | QCA6174 802.11ac Wireless... | 31    | ath10k_pci | 9CCE6740BE |
| 10ec:8178 | 10ec:8178 | Realtek... | RTL8192CE PCIe Wireless N... | 30    | rtl8192ce  | 545DC9A3E0 |
| 14e4:43c3 | 1043:86fb | Broadcom   | Network controller           | 30    | brcmfmac   | DD8260ABF9 |
| 168c:001a | 168c:2052 | Qualcom... | AR2413/AR2414 Wireless Ne... | 30    | ath5k      | C627FC3C07 |
| 8086:3165 | 8086:8010 | Intel      | Wireless 3165                | 30    | iwlwifi    | D9560E08B8 |
| 10ec:8821 | 1043:85b4 | Realtek... | RTL8821AE 802.11ac PCIe W... | 28    | rtl8821ae  | 9452E7DA05 |
| 14e4:4318 | 1043:100f | Broadcom   | BCM4318 [AirForce One 54g... | 28    | ssb        | 1BB0034B64 |
| 10ec:b723 | 103c:81c1 | Realtek... | RTL8723BE PCIe Wireless N... | 27    | rtl8723be  | 69C8804209 |
| 168c:0013 | 168c:2051 | Qualcom... | AR5212/5213/2414 Wireless... | 27    | ath5k      | 4AE2BC6AFD |
| 168c:002a | 168c:0203 | Qualcom... | AR928X Wireless Network A... | 26    | ath9k      | 248C508EB0 |
| 8086:08b1 | 8086:4062 | Intel      | Wireless 7260                | 25    | iwlwifi    | 75EB93BBE0 |
| 10ec:8178 | 7392:7622 | Realtek... | RTL8192CE PCIe Wireless N... | 24    | rtl8192ce  | 9736C8F382 |
| 10ec:b822 | 103c:831b | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 24    | rtw_8822be | 6B8CF94EA2 |
| 168c:0023 | 168c:3071 | Qualcom... | AR5416 Wireless Network A... | 24    | ath9k      | 6030338CC0 |
| 168c:003e | 1043:86e0 | Qualcom... | QCA6174 802.11ac Wireless... | 24    | ath10k_pci | C7BF3FEA46 |
| 1814:0301 | 1737:0055 | Ralink     | RT2561/RT61 802.11g PCI      | 24    | rt61pci    | CB7602A2BD |
| 1814:0781 | 1814:2790 | Ralink     | RT2790 Wireless 802.11n 1... | 24    | rt2800pci  | 8547733D58 |
| 8086:08b1 | 8086:c470 | Intel      | Wireless 7260                | 24    | iwlwifi    | DF95EA94B8 |
| 10ec:8176 | 10ec:8175 | Realtek... | RTL8188CE 802.11b/g/n WiF... | 23    | rtl8192ce  | 11240C3F0F |
| 10ec:c821 | 17aa:c024 | Realtek... | RTL8821CE 802.11ac PCIe W... | 23    | rtl8821ce  | 82058974D9 |
| 10ec:8179 | 103c:197d | Realtek... | RTL8188EE Wireless Networ... | 22    | rtl8188ee  | A2743184D7 |
| 10ec:8812 | 1186:3305 | Realtek... | RTL8812AE 802.11ac PCIe W... | 22    | rtl8821ae  | 00FE3AD0A4 |
| 14e4:43b1 | 1a3b:2123 | Broadcom   | BCM4352 802.11ac Wireless... | 22    | wl         | 2BF61F2EC6 |
| 1814:0601 | 1737:0067 | Ralink     | RT2800 802.11n PCI           | 22    | rt2800pci  | 2B361B1035 |
| 1814:5592 | 1043:851a | Ralink     | RT5592 PCIe Wireless Netw... | 22    | rt5592sta  | A925B0F3D1 |
| 8086:095a | 8086:9010 | Intel      | Wireless 7265                | 22    | iwlwifi    | 3D53583503 |
| 10ec:8178 | 1043:85e3 | Realtek... | RTL8192CE PCIe Wireless N... | 21    | rtl8192ce  | 2322F911C2 |
| 10ec:8179 | 17aa:0179 | Realtek... | RTL8188EE Wireless Networ... | 21    | rtl8188ee  | 02CD32FBB4 |
| 14e4:43a0 | 106b:0117 | Broadco... | BCM4360 802.11ac Wireless... | 21    | wl         | E880DE0931 |
| 168c:003e | 1028:0310 | Qualcom... | QCA6174 802.11ac Wireless... | 21    | ath10k_pci | AF67059921 |
| 168c:0013 | 1186:3a73 | Qualcom... | AR5212/5213/2414 Wireless... | 20    | ath5k      | BEA6762FB6 |
| 1814:0301 | 1043:837e | Ralink     | RT2561/RT61 802.11g PCI      | 20    | rt61pci    | 8DB9070723 |
| 1814:3060 | 1814:3060 | Ralink     | RT3060 Wireless 802.11n 1... | 20    | rt2800pci  | 50053FAAFE |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1539 | 1043:85f0 | Intel      | I211 Gigabit Network Conn... | 911   | igb        | 6E020F3AD1 |
| 8086:1539 | 1458:e000 | Intel      | I211 Gigabit Network Conn... | 667   | igb        | 6B471BC42D |
| 8086:1539 | 1849:1539 | Intel      | I211 Gigabit Network Conn... | 510   | igb        | C537345CE8 |
| 8086:1503 | 1043:849c | Intel      | 82579V Gigabit Network Co... | 425   | e1000e     | EAF4F27F7A |
| 10de:03ef | 1849:03ef | Nvidia     | MCP61 Ethernet               | 391   | forcedeth  | 0F23350175 |
| 8086:1502 | 1028:052c | Intel      | 82579LM Gigabit Network C... | 260   | e1000e     | E1B966B80D |
| 8086:1502 | 1028:047e | Intel      | 82579LM Gigabit Network C... | 223   | e1000e     | D6237E9949 |
| 10de:03ef | 1458:e000 | Nvidia     | MCP61 Ethernet               | 195   | forcedeth  | 701EE8CE26 |
| 10ec:8125 | 1458:e000 | Realtek... | RTL8125 2.5GbE Controller    | 185   | r8169      | 93B56B7543 |
| 8086:10de | 1028:0276 | Intel      | 82567LM-3 Gigabit Network... | 183   | e1000e     | C67A8BB677 |
| 8086:10d3 | 8086:a01f | Intel      | 82574L Gigabit Network Co... | 168   | e1000e     | B14C0E8DD2 |
| 10de:03ef | 1043:83a4 | Nvidia     | MCP61 Ethernet               | 150   | forcedeth  | 324F6E5FAD |
| 10de:03ef | 1043:8234 | Nvidia     | MCP61 Ethernet               | 116   | forcedeth  | 91FE7919BE |
| 8086:10bd | 1028:0211 | Intel      | 82566DM-2 Gigabit Network... | 109   | e1000e     | 7E7D0BC489 |
| 8086:1502 | 103c:3397 | Intel      | 82579LM Gigabit Network C... | 109   | e1000e     | BF9875C5AC |
| 10ec:8125 | 1043:87d7 | Realtek... | RTL8125 2.5GbE Controller    | 89    | r8169      | 4379B423F0 |
| 8086:10de | 1028:027f | Intel      | 82567LM-3 Gigabit Network... | 89    | e1000e     | AADCA45789 |
| 8086:1502 | 103c:339a | Intel      | 82579LM Gigabit Network C... | 89    | e1000e     | 28DA82FF00 |
| 8086:1502 | 103c:1495 | Intel      | 82579LM Gigabit Network C... | 79    | e1000e     | 28835849F0 |
| 8086:1502 | 103c:1497 | Intel      | 82579LM Gigabit Network C... | 78    | e1000e     | C0FB875CA5 |
| 8086:10bd | 103c:2818 | Intel      | 82566DM-2 Gigabit Network... | 75    | e1000e     | 74CFC314C6 |
| 10de:03ef | 1462:7309 | Nvidia     | MCP61 Ethernet               | 70    | forcedeth  | 0A4D7FB95D |
| 8086:10de | 103c:3048 | Intel      | 82567LM-3 Gigabit Network... | 69    | e1000e     | B62359FCB1 |
| 8086:10c0 | 1028:020d | Intel      | 82562V-2 10/100 Network C... | 65    | e1000e     | E77852D5C2 |
| 8086:1503 | 1458:e000 | Intel      | 82579V Gigabit Network Co... | 64    | e1000e     | 8D74DD99C7 |
| 10ec:8125 | 1849:8125 | Realtek... | RTL8125 2.5GbE Controller    | 60    | r8169      | 1FCC4E6895 |
| 10ec:8125 | 1462:7c91 | Realtek... | RTL8125 2.5GbE Controller    | 57    | r8169      | 27B0A66CEB |
| 8086:104a | 103c:2800 | Intel      | 82566DM Gigabit Network C... | 56    | e1000e     | D3B19636D9 |
| 8086:1533 | 1043:8557 | Intel      | I210 Gigabit Network Conn... | 54    | igb        | 2591B8710E |
| 8086:1539 | 8086:0000 | Intel      | I211 Gigabit Network Conn... | 54    | igb        | 7ABD7A20DF |
| 8086:294c | 8086:0001 | Intel      | 82566DC-2 Gigabit Network... | 54    | e1000e     | A5121E1871 |
| 10de:0057 | 1043:812a | Nvidia     | CK804 Ethernet Controller    | 53    | forcedeth  | F9BFF20C4D |
| 8086:1503 | 1025:8000 | Intel      | 82579V Gigabit Network Co... | 53    | e1000e     | 967427D98C |
| 10de:0373 | 1043:8239 | Nvidia     | MCP55 Ethernet               | 47    | forcedeth  | 775AEB5400 |
| 8086:10f0 | 8086:0036 | Intel      | 82578DC Gigabit Network C... | 47    | e1000e     | E5F7233230 |
| 10ec:8125 | 1462:7c35 | Realtek... | RTL8125 2.5GbE Controller    | 46    | r8169      | 8EA75A2EC0 |
| 8086:1502 | 103c:1589 | Intel      | 82579LM Gigabit Network C... | 46    | e1000e     | 49C747EFAD |
| 8086:150c | 1043:8457 | Intel      | 82583V Gigabit Network Co... | 45    | e1000e     | 44DA1EA889 |
| 8086:10df | 1734:114d | Intel      | 82567LF-3 Gigabit Network... | 44    | e1000e     | 138CA0F31D |
| 8086:1502 | 17aa:3070 | Intel      | 82579LM Gigabit Network C... | 44    | e1000e     | 1ECB7A6910 |
| 10ec:8125 | 1462:7c84 | Realtek... | RTL8125 2.5GbE Controller    | 43    | r8169      | 688A36C9DF |
| 8086:10bd | 103c:281e | Intel      | 82566DM-2 Gigabit Network... | 42    | e1000e     | EAA60F7610 |
| 10de:03ef | 103c:2a6c | Nvidia     | MCP61 Ethernet               | 41    | forcedeth  | 929E48A398 |
| 8086:10c0 | 1028:0238 | Intel      | 82562V-2 10/100 Network C... | 41    | e1000e     | D879289E3A |
| 8086:10d3 | 1043:8369 | Intel      | 82574L Gigabit Network Co... | 41    | e1000e     | F0983027EE |
| 8086:10de | 17aa:3048 | Intel      | 82567LM-3 Gigabit Network... | 41    | e1000e     | ED1D55E70A |
| 8086:1539 | 1462:7a32 | Intel      | I211 Gigabit Network Conn... | 41    | igb        | 3ABF73FB8A |
| 8086:1502 | 103c:1494 | Intel      | 82579LM Gigabit Network C... | 40    | e1000e     | AE5165603A |
| 8086:1503 | 8086:2017 | Intel      | 82579V Gigabit Network Co... | 40    | e1000e     | 43E3FCCC3D |
| 8086:1539 | 1462:7b85 | Intel      | I211 Gigabit Network Conn... | 40    | igb        | DB9BFA58F9 |
| 10de:03ef | 103c:2a99 | Nvidia     | MCP61 Ethernet               | 39    | forcedeth  | 29FD6EAE29 |
| 1106:3065 | 1043:80ed | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 39    | via_rhine  | BE5F9F33D4 |
| 8086:10de | 103c:3034 | Intel      | 82567LM-3 Gigabit Network... | 39    | e1000e     | D05CCA1A32 |
| 8086:10de | 103c:3646 | Intel      | 82567LM-3 Gigabit Network... | 39    | e1000e     | 60FB363058 |
| 8086:10f6 | 8086:0000 | Intel      | 82574L Gigabit Network Co... | 39    | e1000e     | EA3E45A8A7 |
| 8086:1502 | 17aa:3083 | Intel      | 82579LM Gigabit Network C... | 39    | e1000e     | DF15656FCE |
| 8086:1533 | 1849:1533 | Intel      | I210 Gigabit Network Conn... | 38    | igb        | ABF0E06A08 |
| 10de:03ef | 1025:8000 | Nvidia     | MCP61 Ethernet               | 37    | forcedeth  | 9DA4BEFF51 |
| 1106:3065 | 1849:3065 | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 37    | via_rhine  | A89CE27A40 |
| 10de:0057 | 1043:8141 | Nvidia     | CK804 Ethernet Controller    | 36    | forcedeth  | 1B7F4401BE |
| 8086:1502 | 103c:3396 | Intel      | 82579LM Gigabit Network C... | 36    | e1000e     | 147C8ED96C |
| 8086:1521 | 15d9:1521 | Intel      | I350 Gigabit Network Conn... | 36    | igb        | 9EFBA142DD |
| 8086:1533 | 1458:e000 | Intel      | I210 Gigabit Network Conn... | 36    | igb        | F2AB7926E3 |
| 10ec:8125 | 10ec:0123 | Realtek... | RTL8125 2.5GbE Controller    | 35    | r8169      | 77E5D91462 |
| 8086:10ef | 103c:304a | Intel      | 82578DM Gigabit Network C... | 35    | e1000e     | 311C6C4C69 |
| 10de:03ef | 1565:2505 | Nvidia     | MCP61 Ethernet               | 34    | forcedeth  | E16A5113BA |
| 8086:10f0 | 1025:8000 | Intel      | 82578DC Gigabit Network C... | 34    | e1000e     | 719B6FFBE5 |
| 8086:10de | 103c:3035 | Intel      | 82567LM-3 Gigabit Network... | 33    | e1000e     | 6914386D3D |
| 8086:104b | 8086:0001 | Intel      | 82566DC Gigabit Network C... | 31    | e1000e     | D3F38DBF63 |
| 8086:1503 | 8086:2002 | Intel      | 82579V Gigabit Network Co... | 31    | e1000e     | B7B3F489F2 |
| 8086:1502 | 17aa:3084 | Intel      | 82579LM Gigabit Network C... | 30    | e1000e     | C7D7CACA33 |
| 10b7:9200 | 10b7:1000 | 3Com       | 3c905C-TX/TX-M [Tornado]     | 29    | 3c59x      | DE0F1A6DD3 |
| 8086:10d3 | 103c:158a | Intel      | 82574L Gigabit Network Co... | 29    | e1000e     | 6C22E51BFC |
| 8086:1502 | 1734:11d9 | Intel      | 82579LM Gigabit Network C... | 29    | e1000e     | 7A70FC2989 |
| 8086:1503 | 1734:11b7 | Intel      | 82579V Gigabit Network Co... | 29    | e1000e     | 46DA6A9EB2 |
| 10b7:9055 | 10b7:9055 | 3Com       | 3c905B 100BaseTX [Cyclone]   | 28    | 3c59x      | F7A252E496 |
| 10ec:8125 | 1462:7c94 | Realtek... | RTL8125 2.5GbE Controller    | 28    | r8169      | 08819513F2 |
| 8086:10de | 1734:114d | Intel      | 82567LM-3 Gigabit Network... | 28    | e1000e     | 6B08158329 |
| 8086:1502 | 1028:0497 | Intel      | 82579LM Gigabit Network C... | 28    | e1000e     | 09302F3BB8 |
| 8086:1502 | 103c:158a | Intel      | 82579LM Gigabit Network C... | 28    | e1000e     | 6C22E51BFC |
| 10de:0269 | 1043:8221 | Nvidia     | MCP51 Ethernet Controller    | 27    | forcedeth  | AB314D65BE |
| 8086:10ef | 1028:02da | Intel      | 82578DM Gigabit Network C... | 27    | e1000e     | 51D64C0798 |
| 8086:10f0 | 8086:0000 | Intel      | 82578DC Gigabit Network C... | 27    | e1000e     | D4B171DC3D |
| 8086:1502 | 17aa:3077 | Intel      | 82579LM Gigabit Network C... | 27    | e1000e     | 3E625A72D2 |
| 10de:0373 | 1458:e000 | Nvidia     | MCP55 Ethernet               | 26    | forcedeth  | E55AF94449 |
| 8086:1502 | 8086:0000 | Intel      | 82579LM Gigabit Network C... | 26    | e1000e     | 53CAFAB8F3 |
| 10ec:8125 | 1462:7c75 | Realtek... | RTL8125 2.5GbE Controller    | 25    | r8169      | B8A7B6080F |
| 8086:10d3 | 15d9:10d3 | Intel      | 82574L Gigabit Network Co... | 25    | e1000e     | C7C31F9BCF |
| 8086:1539 | 1462:7b93 | Intel      | I211 Gigabit Network Conn... | 25    | igb        | 93DE1508CB |
| 8086:1503 | 1734:11d9 | Intel      | 82579V Gigabit Network Co... | 24    | e1000e     | D0C4DEF6BF |
| 8086:1503 | 8086:0000 | Intel      | 82579V Gigabit Network Co... | 24    | e1000e     | 853E99EEE4 |
| 10de:0269 | 1043:816a | Nvidia     | MCP51 Ethernet Controller    | 23    | forcedeth  | 19BDD9712D |
| 10de:0373 | 1462:7250 | Nvidia     | MCP55 Ethernet               | 23    | forcedeth  | 98C67DA00D |
| 10ec:8125 | 1849:8168 | Realtek... | RTL8125 2.5GbE Controller    | 23    | r8169      | DF8AB9EFFB |
| 8086:10de | 17aa:3047 | Intel      | 82567LM-3 Gigabit Network... | 23    | e1000e     | 74363F1551 |
| 8086:1502 | 1734:11b7 | Intel      | 82579LM Gigabit Network C... | 23    | e1000e     | 1229314F25 |
| 8086:10d3 | 8086:0000 | Intel      | 82574L Gigabit Network Co... | 22    | e1000e     | C196142007 |
| 8086:10ef | 8086:0038 | Intel      | 82578DM Gigabit Network C... | 22    | e1000e     | BF6D27F32D |
| 8086:1502 | 103c:158b | Intel      | 82579LM Gigabit Network C... | 22    | e1000e     | 24399F4E69 |
| 8086:1539 | 1462:7b09 | Intel      | I211 Gigabit Network Conn... | 22    | igb        | 4D6C77ACCB |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1455 | 1022:1455 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1870  |            | E52E9002D0 |
| 1022:145a | 1022:145a | AMD        | Zeppelin/Raven/Raven2 PCI... | 1870  |            | E52E9002D0 |
| 1022:1485 | 1022:1485 | AMD        | Starship/Matisse Reserved... | 1638  |            | C537345CE8 |
| 1022:148a | 1022:148a | AMD        | Starship/Matisse PCIe Dum... | 1566  |            | C537345CE8 |
| 1022:1485 | 1043:87c0 | AMD        | Starship/Matisse Reserved... | 734   |            | 161865EDB0 |
| 1022:148a | 1043:87c0 | AMD        | Starship/Matisse PCIe Dum... | 734   |            | 161865EDB0 |
| 1022:1455 | 1043:8747 | AMD        | Zeppelin/Renoir PCIe Dumm... | 616   |            | 491D1A96CC |
| 1022:145a | 1043:8747 | AMD        | Zeppelin/Raven/Raven2 PCI... | 616   |            | 491D1A96CC |
| 1022:1485 | 1043:8808 | AMD        | Starship/Matisse Reserved... | 163   |            | A525C8911B |
| 1022:148a | 1043:8808 | AMD        | Starship/Matisse PCIe Dum... | 163   |            | A525C8911B |
| 1022:1485 | 1462:7c02 | AMD        | Starship/Matisse Reserved... | 96    |            | 97620628A8 |
| 1022:148a | 1462:7c02 | AMD        | Starship/Matisse PCIe Dum... | 96    |            | 97620628A8 |
| 1022:145a | 1043:876b | AMD        | Zeppelin/Raven/Raven2 PCI... | 73    |            | D3A9F1CE6E |
| 1022:1485 | 1462:7b86 | AMD        | Starship/Matisse Reserved... | 66    |            | 7E563A9D44 |
| 1022:148a | 1462:7b86 | AMD        | Starship/Matisse PCIe Dum... | 66    |            | 7E563A9D44 |
| 1022:145a | 1462:7c02 | AMD        | Zeppelin/Raven/Raven2 PCI... | 62    |            | F50B61B450 |
| 1022:1455 | 1462:7c02 | AMD        | Zeppelin/Renoir PCIe Dumm... | 59    |            | F50B61B450 |
| 1022:145a | 1462:7b86 | AMD        | Zeppelin/Raven/Raven2 PCI... | 53    |            | F17090E5D2 |
| 1022:145a | 1458:d000 | AMD        | Zeppelin/Raven/Raven2 PCI... | 51    |            | F316C0A82E |
| 1022:1485 | 1462:7c35 | AMD        | Starship/Matisse Reserved... | 47    |            | 8EA75A2EC0 |
| 1022:148a | 1462:7c35 | AMD        | Starship/Matisse PCIe Dum... | 47    |            | 8EA75A2EC0 |
| 1022:1455 | 1462:7b86 | AMD        | Zeppelin/Renoir PCIe Dumm... | 46    |            | F17090E5D2 |
| 1022:1485 | 1462:7b89 | AMD        | Starship/Matisse Reserved... | 45    |            | A72102FDB0 |
| 1022:148a | 1462:7b89 | AMD        | Starship/Matisse PCIe Dum... | 45    |            | A72102FDB0 |
| 1022:145a | 1002:15d8 | AMD        | Zeppelin/Raven/Raven2 PCI... | 42    |            | 20C432EF7D |
| 1022:145a | 1002:15dd | AMD        | Zeppelin/Raven/Raven2 PCI... | 41    |            | 780E40D828 |
| 1022:145a | 1462:7a38 | AMD        | Zeppelin/Raven/Raven2 PCI... | 34    |            | 952645EF00 |
| 1022:145a | 1462:7b89 | AMD        | Zeppelin/Raven/Raven2 PCI... | 28    |            | 46651B942B |
| 1022:1485 | 1462:7a38 | AMD        | Starship/Matisse Reserved... | 28    |            | 11F7EC8B16 |
| 1022:148a | 1462:7a38 | AMD        | Starship/Matisse PCIe Dum... | 28    |            | 11F7EC8B16 |
| 1022:1455 | 1462:7a38 | AMD        | Zeppelin/Renoir PCIe Dumm... | 27    |            | 276D5FE9E3 |
| 1022:1485 | 1462:7c94 | AMD        | Starship/Matisse Reserved... | 26    |            | 08819513F2 |
| 1022:148a | 1462:7c94 | AMD        | Starship/Matisse PCIe Dum... | 26    |            | 08819513F2 |
| 1022:1455 | 1462:7b89 | AMD        | Zeppelin/Renoir PCIe Dumm... | 24    |            | E8965C736D |
| 1022:1485 | 1043:87cb | AMD        | Starship/Matisse Reserved... | 24    |            | 6E020F3AD1 |
| 1022:148a | 1043:87cb | AMD        | Starship/Matisse PCIe Dum... | 24    |            | 6E020F3AD1 |
| 1022:1485 | 1462:7c95 | AMD        | Starship/Matisse Reserved... | 23    |            | D06DD7E0EC |
| 1022:148a | 1462:7c95 | AMD        | Starship/Matisse PCIe Dum... | 23    |            | D06DD7E0EC |
| 1022:1485 | 1043:8747 | AMD        | Starship/Matisse Reserved... | 21    |            | F66B710A8A |
| 1022:1485 | 1462:7b85 | AMD        | Starship/Matisse Reserved... | 21    |            | DB9BFA58F9 |
| 1022:148a | 1462:7b85 | AMD        | Starship/Matisse PCIe Dum... | 21    |            | DB9BFA58F9 |
| 1022:145a | 1462:7b85 | AMD        | Zeppelin/Raven/Raven2 PCI... | 16    |            | 429525379A |
| 1022:1455 | 1462:7b85 | AMD        | Zeppelin/Renoir PCIe Dumm... | 15    |            | 429525379A |
| 1022:1485 | 1043:87e2 | AMD        | Starship/Matisse Reserved... | 14    |            | EE6DBC679C |
| 1022:148a | 1043:87e2 | AMD        | Starship/Matisse PCIe Dum... | 14    |            | EE6DBC679C |
| 1022:1485 | 1462:7a40 | AMD        | Starship/Matisse Reserved... | 11    |            | 1CA6C5085E |
| 1022:148a | 1462:7a40 | AMD        | Starship/Matisse PCIe Dum... | 11    |            | 1CA6C5085E |
| 1022:1455 | 1462:7a40 | AMD        | Zeppelin/Renoir PCIe Dumm... | 10    |            | 89BF33DB93 |
| 1022:145a | 1462:7a40 | AMD        | Zeppelin/Raven/Raven2 PCI... | 10    |            | 89BF33DB93 |
| 1022:1485 | 1043:876b | AMD        | Starship/Matisse Reserved... | 8     |            | FC6CC9B254 |
| 1022:145a | 1462:7b87 | AMD        | Zeppelin/Raven/Raven2 PCI... | 7     |            | 18FF34F941 |
| 1022:1455 | 1462:7b87 | AMD        | Zeppelin/Renoir PCIe Dumm... | 6     |            | 18FF34F941 |
| 1022:1485 | 1462:7c34 | AMD        | Starship/Matisse Reserved... | 6     |            | 1440E244F6 |
| 1022:1485 | 17aa:1046 | AMD        | Starship/Matisse Reserved... | 6     |            | 136C409F1A |
| 1022:148a | 1462:7c34 | AMD        | Starship/Matisse PCIe Dum... | 6     |            | 1440E244F6 |
| 1022:148a | 17aa:1046 | AMD        | Starship/Matisse PCIe Dum... | 6     |            | 136C409F1A |
| 1022:145a | 1002:1636 | AMD        | Zeppelin/Raven/Raven2 PCI... | 5     |            | AE854C2FF2 |
| 1022:145a | 1462:7b79 | AMD        | Zeppelin/Raven/Raven2 PCI... | 5     |            | 2119A5CDC5 |
| 1022:145a | 1462:7c52 | AMD        | Zeppelin/Raven/Raven2 PCI... | 5     |            | FDA90307D4 |
| 1022:1485 | 1462:7c36 | AMD        | Starship/Matisse Reserved... | 5     |            | F61BA12C20 |
| 1022:148a | 1462:7c36 | AMD        | Starship/Matisse PCIe Dum... | 5     |            | F61BA12C20 |
| 1022:1455 | 1462:7b90 | AMD        | Zeppelin/Renoir PCIe Dumm... | 4     |            | 3642F15AB7 |
| 1022:145a | 1462:7b90 | AMD        | Zeppelin/Raven/Raven2 PCI... | 4     |            | 3642F15AB7 |
| 1022:145a | 1565:170b | AMD        | Zeppelin/Raven/Raven2 PCI... | 4     |            | F0449B9946 |
| 1022:1485 | 1028:098e | AMD        | Starship/Matisse Reserved... | 4     |            | E1BC8D1CDD |
| 1022:1485 | 1043:8815 | AMD        | Starship/Matisse Reserved... | 4     |            | 8F7011B085 |
| 1022:1485 | 1462:7b87 | AMD        | Starship/Matisse Reserved... | 4     |            | 58A277F8E4 |
| 1022:148a | 1028:098e | AMD        | Starship/Matisse PCIe Dum... | 4     |            | E1BC8D1CDD |
| 1022:148a | 1043:8815 | AMD        | Starship/Matisse PCIe Dum... | 4     |            | 8F7011B085 |
| 1022:148a | 1462:7b87 | AMD        | Starship/Matisse PCIe Dum... | 4     |            | 58A277F8E4 |
| 1022:145a | 1462:7a33 | AMD        | Zeppelin/Raven/Raven2 PCI... | 3     |            | 26F4437015 |
| 1022:145a | 1462:7b84 | AMD        | Zeppelin/Raven/Raven2 PCI... | 3     |            | 9644A0A56C |
| 1022:145a | 1462:7c51 | AMD        | Zeppelin/Raven/Raven2 PCI... | 3     |            | 987E9D49E0 |
| 1022:1485 | 1462:7c96 | AMD        | Starship/Matisse Reserved... | 3     |            | EB1233376B |
| 1022:148a | 1462:7c96 | AMD        | Starship/Matisse PCIe Dum... | 3     |            | EB1233376B |
| 1022:1455 | 103c:8399 | AMD        | Zeppelin/Renoir PCIe Dumm... | 2     |            | 733813E901 |
| 1022:145a | 1022:7901 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 19FE989DE3 |
| 1022:145a | 103c:8399 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 733813E901 |
| 1022:145a | 1043:87e1 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 63F68846BB |
| 1022:145a | 1462:7a34 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | CB6CAEFA10 |
| 1022:145a | 1462:7c37 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 90892D21E5 |
| 1022:1485 | 1028:0a8b | AMD        | Starship/Matisse Reserved... | 2     |            | 5EA23EBFB2 |
| 1022:1485 | 1043:1c81 | AMD        | Starship/Matisse Reserved... | 2     |            | 66B9CEA0F2 |
| 1022:1485 | 1043:8809 | AMD        | Starship/Matisse Reserved... | 2     |            | 9ED2B3CF12 |
| 1022:1485 | 1849:1485 | AMD        | Starship/Matisse Reserved... | 2     |            | EBCC16470F |
| 1022:1485 | 1849:148a | AMD        | Starship/Matisse Reserved... | 2     |            | 49A0EEC9F5 |
| 1022:148a | 1028:0a8b | AMD        | Starship/Matisse PCIe Dum... | 2     |            | 5EA23EBFB2 |
| 1022:148a | 1043:1c81 | AMD        | Starship/Matisse PCIe Dum... | 2     |            | 66B9CEA0F2 |
| 1022:148a | 1043:8747 | AMD        | Starship/Matisse PCIe Dum... | 2     |            | 249D6291CB |
| 1022:148a | 1849:148a | AMD        | Starship/Matisse PCIe Dum... | 2     |            | 49A0EEC9F5 |
| 1022:1455 | 1019:9ce5 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 06776696F3 |
| 1022:1455 | 1019:9d10 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 277BBC0E9E |
| 1022:1455 | 1019:a412 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | C47BA626E7 |
| 1022:1455 | 1019:a4cd | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 8106DDD47F |
| 1022:1455 | 1462:7c95 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | F1A1A21C56 |
| 1022:1455 | 17aa:36e1 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 31F5158C61 |
| 1022:1455 | 1849:1455 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 4C4AD9EBE5 |
| 1022:145a | 1019:9ce5 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 06776696F3 |
| 1022:145a | 1019:9d10 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 277BBC0E9E |
| 1022:145a | 1019:a412 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | C47BA626E7 |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15e6 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Non-S... | 28    | i2c_amd... | 72CE248D0C |
| 8086:a2a4 |           | Intel      | 200 Series/Z370 Chipset F... | 7     |            | B59C9CF621 |
| 8086:9d24 |           | Intel      | Skylake-U/Y SPI Controller   | 6     |            | 781FA86FEA |
| 12ab:0380 | 1cfa:0003 | YUAN Hi... | Game Capture 4K60 Pro        | 4     |            | A03E1FDB12 |
| 104c:9065 |           | Texas I... | TMS320DM642                  | 3     |            | 1AA3233F77 |
| 1b4b:9235 |           | Marvell... | 88SE9235 PCIe 2.0 x2 4-po... | 3     |            | 9A98A31681 |
| 0014:7a10 |           | Loongso... | Hyper Transport Bridge Co... | 2     |            | 014BDABB68 |
| 106b:1801 | 106b:1801 | Apple      | T2 Bridge Controller         | 2     |            | 610B9319E9 |
| 106b:1802 | 106b:1802 | Apple      | T2 Secure Enclave Processor  | 2     |            | 610B9319E9 |
| 1b4b:1475 |           | Marvell... |                              | 2     |            | 9A98A31681 |
| 8086:1533 |           | Intel      | I210 Gigabit Network Conn... | 2     |            | 9A98A31681 |
| 8086:6f04 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 9A98A31681 |
| 8086:6f06 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 9A98A31681 |
| 8086:6f08 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 9A98A31681 |
| 8086:6f0a |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 9A98A31681 |
| 8086:8c54 |           | Intel      | C224 Series Chipset Famil... | 2     |            | 9A98A31681 |
| 8086:a135 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_i... | 35FFF898D1 |
| 8086:a135 | 8086:a135 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_i... | C65085AE62 |
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
| 8086:8c22 |           | Intel      | 8 Series/C220 Series Chip... | 1     |            | 8FDAC2FAB2 |
| 8086:9d35 | 8086:7270 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | B1128F0534 |
| 8086:a135 | 15d9:089a | Intel      | 100 Series/C230 Series Ch... | 1     | intel_i... | 4AFDC738DE |
| 8086:a3a4 |           | Intel      | Comet Lake PCH-V SPI (fla... | 1     | intel_s... | 0D1000E904 |
| a411:0000 | 011b:0808 |            |                              | 1     |            | E79C952746 |
| f810:ffff | ffff:ffff |            |                              | 1     |            | 67CBAFF497 |

### Parallel controller (bidir) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1c00:2170 | 1c00:2170 |            | WCH PCI                      | 5     |            | 6441A522B9 |
| 1407:8000 |           | Lava Co... | Lava Parallel                | 1     | parport_pc | 1733DC0809 |
| 1415:9523 | 1415:0001 | Oxford ... | OX16PCI952 Integrated Par... | 1     | parport_pc | AB95A02DA7 |
| 1415:9523 | 1415:1201 | Oxford ... | OX16PCI952 Integrated Par... | 1     | parport_pc | 217BFD48BD |

### Parallel controller (ecp) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1415:c110 | 1415:c110 | Oxford ... | OXPCIe952 Parallel Port      | 13    | parport_pc | F9F1775D7A |
| 1409:7268 | 1409:0103 | Timedia... | SUN1888 (Dual IEEE1284 pa... | 6     | parport_pc | 6872AE9FB4 |
| 1409:7268 | 1409:0104 | Timedia... | SUN1888 (Dual IEEE1284 pa... | 1     | parport_pc | A989D3CA5D |
| 1415:c11c | 1415:c11c | Oxford ... | OXPCIe952 Parallel Port      | 1     | parport_pc | 9D66F53103 |

### Parallel controller (ieee1284) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 9710:9865 | a000:2000 | MosChip... | PCI 9865 Multi-I/O Contro... | 26    | parport_pc | 491117F46C |
| 9710:9912 | a000:2000 | MosChip... | PCIe 9912 Multi-I/O Contr... | 18    | parport... | 414008F0A3 |
| 1fd4:1999 | 1fd4:0100 | SUNIX      | Multiport serial controller  | 14    | parport... | FF477E5A71 |
| ffff:9865 | a000:2000 | Illegal... | Parallel controller          | 5     |            | C40CA96991 |
| 125b:9100 | a000:2000 | Asix El... | AX99100 PCIe to Multi I/O... | 4     |            | 3B8DDCA28E |
| 1415:8403 | 1415:0000 | Oxford ... | OX9162 Mode 0 (parallel p... | 1     | parport_pc | D66BC8959A |
| 9710:8925 | a000:2100 | MosChip... | MosChip Parallel controller  | 1     |            | 4EDB22DA2D |
| 9710:9901 | a000:2000 | MosChip... | PCIe 9901 Multi-I/O Contr... | 1     | parport_pc | 351B3621FD |

### Performance counters (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2f30 | 8086:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 358   | hswep_u... | 9D2A807F08 |
| 8086:2f34 | 8086:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 358   | hswep_u... | 9D2A807F08 |
| 8086:2f7d | 8086:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 358   |            | 9D2A807F08 |
| 8086:2f36 | 8086:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 323   | hswep_u... | 9D2A807F08 |
| 8086:2f37 | 8086:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 323   | hswep_u... | 9D2A807F08 |
| 8086:3c44 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to Q... | 169   | snbep_u... | 60F5B34BDD |
| 8086:3ce6 | 8086:0000 | Intel      | Xeon E5/Core i7 QuickPath... | 169   |            | 60F5B34BDD |
| 8086:3c43 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to P... | 163   | snbep_u... | 60F5B34BDD |
| 8086:0e36 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 129   | ivbep_u... | 97F8374A85 |
| 8086:204c | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 110   | skx_uncore | EACC1E3F66 |
| 8086:204d | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 110   | skx_uncore | EACC1E3F66 |
| 8086:2015 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 107   |            | EACC1E3F66 |
| 8086:6f30 | 8086:6f30 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 105   | bdx_uncore | 6EBA24CF71 |
| 8086:6f34 | 8086:6f34 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 105   | bdx_uncore | 6EBA24CF71 |
| 8086:6f7d | 8086:6f7d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 105   |            | 6EBA24CF71 |
| 8086:0e34 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 104   | ivbep_u... | 97F8374A85 |
| 8086:6f36 | 8086:6f36 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 93    | bdx_uncore | 6EBA24CF71 |
| 8086:6f37 | 8086:6f37 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 93    | bdx_uncore | 6EBA24CF71 |
| 8086:3c43 | 1043:84ef | Intel      | Xeon E5/Core i7 Ring to P... | 90    | snbep_u... | EAF4F27F7A |
| 8086:3c44 | 1043:84ef | Intel      | Xeon E5/Core i7 Ring to Q... | 90    | snbep_u... | EAF4F27F7A |
| 8086:3c46 | 1043:84ef | Intel      | Xeon E5/Core i7 Processor... | 90    | snbep_u... | EAF4F27F7A |
| 8086:3ce6 | 1043:84ef | Intel      | Xeon E5/Core i7 QuickPath... | 90    |            | EAF4F27F7A |
| 8086:3c46 | 8086:0000 | Intel      | Xeon E5/Core i7 Processor... | 87    | snbep_u... | 60F5B34BDD |
| 8086:2f38 | 8086:2f38 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 86    | hswep_u... | F41F68A362 |
| 8086:3c46 |           | Intel      | Xeon E5/Core i7 Processor... | 81    | snbep_u... | 49C747EFAD |
| 8086:0e30 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 59    | ivbep_u... | C720033D3A |
| 8086:0e30 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 51    | ivbep_u... | 1BB97BC7DF |
| 8086:0e34 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 51    | ivbep_u... | 1BB97BC7DF |
| 8086:0e36 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 51    | ivbep_u... | 1BB97BC7DF |
| 8086:0e30 |           | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 45    | ivbep_u... | 97F8374A85 |
| 8086:2f32 | 8086:2f32 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 41    | hswep_u... | F41F68A362 |
| 8086:3424 |           | Intel      | 7500/5520/5500/X58 Perfor... | 41    |            | EA3E45A8A7 |
| 8086:2f33 | 8086:2f33 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 38    | hswep_u... | F41F68A362 |
| 8086:2f36 | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 31    | hswep_u... | 90189BED4E |
| 8086:2f37 | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 31    | hswep_u... | 90189BED4E |
| 8086:2f30 | 1849:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 30    | hswep_u... | B502D23978 |
| 8086:2f34 | 1849:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 30    | hswep_u... | B502D23978 |
| 8086:2f36 | 1849:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 30    | hswep_u... | B502D23978 |
| 8086:2f37 | 1849:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 30    | hswep_u... | B502D23978 |
| 8086:2f7d | 1849:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 30    |            | B502D23978 |
| 8086:3c43 | 1028:0497 | Intel      | Xeon E5/Core i7 Ring to P... | 29    | snbep_u... | 09302F3BB8 |
| 8086:3c44 | 1028:0497 | Intel      | Xeon E5/Core i7 Ring to Q... | 29    | snbep_u... | 09302F3BB8 |
| 8086:3c46 | 1028:0497 | Intel      | Xeon E5/Core i7 Processor... | 29    | snbep_u... | 09302F3BB8 |
| 8086:3ce6 | 1028:0497 | Intel      | Xeon E5/Core i7 QuickPath... | 29    |            | 09302F3BB8 |
| 8086:2088 |           | Intel      | Sky Lake-E DDRIO Registers   | 26    | skx_uncore | 30591F341D |
| 8086:3c43 | 1458:3c43 | Intel      | Xeon E5/Core i7 Ring to P... | 23    | snbep_u... | 853E99EEE4 |
| 8086:3c44 | 1458:3c44 | Intel      | Xeon E5/Core i7 Ring to Q... | 23    | snbep_u... | 853E99EEE4 |
| 8086:3c46 | 1458:3c46 | Intel      | Xeon E5/Core i7 Processor... | 23    | snbep_u... | 853E99EEE4 |
| 8086:3ce6 | 1458:3ce6 | Intel      | Xeon E5/Core i7 QuickPath... | 23    |            | 853E99EEE4 |
| 8086:6f32 | 8086:6f32 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    | bdx_uncore | EB31EDBD6C |
| 8086:6f33 | 8086:6f33 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    | bdx_uncore | EB31EDBD6C |
| 8086:2088 | 8086:0000 | Intel      | Sky Lake-E DDRIO Registers   | 20    | skx_uncore | 30591F341D |
| 8086:6f38 | 8086:6f38 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 20    | bdx_uncore | 17B2218DAB |
| 8086:2015 | 1028:0738 | Intel      | Sky Lake-E Ubox Registers    | 18    |            | 13718F9C0B |
| 8086:204c | 1028:0738 | Intel      | Sky Lake-E M3KTI Registers   | 18    | skx_uncore | 13718F9C0B |
| 8086:204d | 1028:0738 | Intel      | Sky Lake-E M3KTI Registers   | 18    | skx_uncore | 13718F9C0B |
| 8086:0e30 | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 15    | ivbep_u... | 14CD659D3D |
| 8086:0e34 | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 15    | ivbep_u... | 14CD659D3D |
| 8086:0e37 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 14    | ivbep_u... | 97F8374A85 |
| 8086:3c43 | 1849:3c43 | Intel      | Xeon E5/Core i7 Ring to P... | 14    | snbep_u... | 4AE2BC6AFD |
| 8086:3c44 | 1849:3c44 | Intel      | Xeon E5/Core i7 Ring to Q... | 14    | snbep_u... | 4AE2BC6AFD |
| 8086:3c46 | 1849:3c46 | Intel      | Xeon E5/Core i7 Processor... | 14    | snbep_u... | 4AE2BC6AFD |
| 8086:3ce6 | 1849:3ce6 | Intel      | Xeon E5/Core i7 QuickPath... | 14    |            | 4AE2BC6AFD |
| 8086:6f30 | 1849:6f30 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 12    | bdx_uncore | 2BF61F2EC6 |
| 8086:6f34 | 1849:6f34 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 12    | bdx_uncore | 2BF61F2EC6 |
| 8086:6f36 | 1849:6f36 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 12    | bdx_uncore | 2BF61F2EC6 |
| 8086:6f37 | 1849:6f37 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 12    | bdx_uncore | 2BF61F2EC6 |
| 8086:6f7d | 1849:6f7d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 12    |            | 2BF61F2EC6 |
| 8086:0e30 | 1458:3c46 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 10    | ivbep_u... | 349F8DBE53 |
| 8086:0e34 | 1458:3c43 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 10    | ivbep_u... | 349F8DBE53 |
| 8086:0e36 | 1458:3c44 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 10    | ivbep_u... | 349F8DBE53 |
| 8086:3c43 | 8086:4953 | Intel      | Xeon E5/Core i7 Ring to P... | 10    | snbep_u... | 380F10F479 |
| 8086:3c44 | 8086:4953 | Intel      | Xeon E5/Core i7 Ring to Q... | 10    | snbep_u... | 380F10F479 |
| 8086:3c46 | 8086:4953 | Intel      | Xeon E5/Core i7 Processor... | 10    | snbep_u... | 380F10F479 |
| 8086:3ce6 | 8086:4953 | Intel      | Xeon E5/Core i7 QuickPath... | 10    |            | 380F10F479 |
| 8086:0e30 | 1028:05d4 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 7     | ivbep_u... | 3CF0EB9253 |
| 8086:0e34 | 1028:05d4 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 7     | ivbep_u... | 3CF0EB9253 |
| 8086:2058 | 8086:0000 | Intel      | Sky Lake-E KTI 0             | 7     | skx_uncore | 0ADC8FC04D |
| 8086:2088 | 1028:0738 | Intel      | Sky Lake-E DDRIO Registers   | 7     | skx_uncore | 13718F9C0B |
| 8086:2f38 | 1849:2f38 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 7     | hswep_u... | 72B568A9B6 |
| 8086:3c43 | 1028:0495 | Intel      | Xeon E5/Core i7 Ring to P... | 7     | snbep_u... | 0C3A459A0E |
| 8086:3c44 | 1028:0495 | Intel      | Xeon E5/Core i7 Ring to Q... | 7     | snbep_u... | 0C3A459A0E |
| 8086:3c46 | 1028:0495 | Intel      | Xeon E5/Core i7 Processor... | 7     | snbep_u... | 0C3A459A0E |
| 8086:3ce6 | 1028:0495 | Intel      | Xeon E5/Core i7 QuickPath... | 7     |            | 0C3A459A0E |
| 8086:2015 | 1734:122f | Intel      | Sky Lake-E Ubox Registers    | 6     |            | 33A89C4C5A |
| 8086:204c | 1734:122f | Intel      | Sky Lake-E M3KTI Registers   | 6     |            | 33A89C4C5A |
| 8086:204d | 1734:122f | Intel      | Sky Lake-E M3KTI Registers   | 6     | skx_uncore | 33A89C4C5A |
| 8086:3c43 | 1028:0496 | Intel      | Xeon E5/Core i7 Ring to P... | 6     | snbep_u... | 80E68A5C66 |
| 8086:3c43 | 1734:11b5 | Intel      | Xeon E5/Core i7 Ring to P... | 6     | snbep_u... | E689B2DE7A |
| 8086:3c44 | 1028:0496 | Intel      | Xeon E5/Core i7 Ring to Q... | 6     | snbep_u... | 80E68A5C66 |
| 8086:3c44 | 1734:11b5 | Intel      | Xeon E5/Core i7 Ring to Q... | 6     | snbep_u... | E689B2DE7A |
| 8086:3c46 | 1028:0496 | Intel      | Xeon E5/Core i7 Processor... | 6     | snbep_u... | 80E68A5C66 |
| 8086:3c46 | 1734:11b5 | Intel      | Xeon E5/Core i7 Processor... | 6     | snbep_u... | E689B2DE7A |
| 8086:3ce6 | 1028:0496 | Intel      | Xeon E5/Core i7 QuickPath... | 6     |            | 80E68A5C66 |
| 8086:3ce6 | 1734:11b5 | Intel      | Xeon E5/Core i7 QuickPath... | 6     |            | E689B2DE7A |
| 8086:0e30 | 17aa:1026 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 5     | ivbep_u... | 99B572DE7F |
| 8086:0e30 | 1849:0e30 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 5     | ivbep_u... | D3383D57EF |
| 8086:0e34 | 17aa:1026 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 5     | ivbep_u... | 99B572DE7F |
| 8086:0e34 | 1849:0e34 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 5     | ivbep_u... | D3383D57EF |
| 8086:0e36 | 17aa:1026 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 5     | ivbep_u... | 99B572DE7F |

### Pic (8259) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3422 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 660   |            | 40C84C9637 |
| 8086:3423 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 660   |            | 40C84C9637 |
| 8086:342e |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 660   | i7core_... | 40C84C9637 |
| 8086:3438 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 384   | i5500_temp | 6C7ECC284B |
| 8086:3425 |           | Intel      | 7500/5520/5500/X58 Physic... | 284   |            | 40C84C9637 |
| 8086:3426 |           | Intel      | 7500/5520/5500/X58 Routin... | 284   |            | 40C84C9637 |
| 8086:3427 |           | Intel      | 7500/5520/5500 Physical a... | 252   |            | 40C84C9637 |
| 8086:3428 |           | Intel      | 7500/5520/5500 Routing & ... | 252   |            | 40C84C9637 |
| 8086:3422 | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 66    |            | 59C0064E39 |
| 8086:3423 | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 66    |            | 59C0064E39 |
| 8086:342e | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 66    | i7core_... | 59C0064E39 |
| 8086:3422 | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 31    |            | FF796824D2 |
| 8086:3423 | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 31    |            | FF796824D2 |
| 8086:342e | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 31    | i7core_... | FF796824D2 |
| 8086:3422 | 0086:0022 | Intel      | 7500/5520/5500/X58 I/O Hu... | 24    |            | 849CA2DA3D |
| 8086:3423 | 0086:0023 | Intel      | 7500/5520/5500/X58 I/O Hu... | 24    |            | 849CA2DA3D |
| 8086:342e | 0086:002e | Intel      | 7500/5520/5500/X58 I/O Hu... | 24    | i7core_... | 849CA2DA3D |
| 8086:3422 | 0028:006d | Intel      | 7500/5520/5500/X58 I/O Hu... | 22    |            | 2F188B606A |
| 8086:3423 | 0028:006d | Intel      | 7500/5520/5500/X58 I/O Hu... | 22    |            | 2F188B606A |
| 8086:342e | 0028:006d | Intel      | 7500/5520/5500/X58 I/O Hu... | 22    | i7core_... | 2F188B606A |
| 8086:3422 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 17    |            | 9753F223E2 |
| 8086:3423 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 17    |            | 9753F223E2 |
| 8086:342e | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 17    | i7core_... | 9753F223E2 |
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
| 8086:342f |           | Intel      | 7500/5520/5500/X58 Truste... | 251   |            | 40C84C9637 |
| 8086:2f2c | 8086:0000 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 245   |            | 9D2A807F08 |
| 8086:3c2c | 8086:3c2c | Intel      | Xeon E5/Core i7 I/O APIC     | 166   |            | 60F5B34BDD |
| 8086:342d |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 148   |            | 40C84C9637 |
| 8086:0e2c | 8086:0e2c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 98    |            | 6908407322 |
| 8086:2026 | 8086:2026 | Intel      | Sky Lake-E IOAPIC            | 97    |            | EACC1E3F66 |
| 8086:2036 | 8086:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 97    |            | EACC1E3F66 |
| 8086:3c2c | 1043:84ef | Intel      | Xeon E5/Core i7 I/O APIC     | 90    |            | EAF4F27F7A |
| 8086:6f2c | 8086:0000 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 68    |            | 17B2218DAB |
| 1106:5327 |           | VIA Tec... | P4M890 I/O APIC Interrupt... | 51    |            | C499580572 |
| 8086:0e2c | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 51    |            | 1BB97BC7DF |
| 1106:5364 |           | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 44    |            | C61D7B8758 |
| 8086:2f2c | 1849:2f2c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 30    |            | B502D23978 |
| 8086:3c2c | 1028:0497 | Intel      | Xeon E5/Core i7 I/O APIC     | 29    |            | 09302F3BB8 |
| 8086:2f2c | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 28    |            | 90189BED4E |
| 8086:2f2c | 1028:0617 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 25    |            | CC3925F2E7 |
| 8086:3c2c | 1458:5000 | Intel      | Xeon E5/Core i7 I/O APIC     | 23    |            | 853E99EEE4 |
| 1106:5308 | 1849:5308 | VIA Tec... | PT894 I/O APIC Interrupt ... | 21    |            | 6DF28D7EA1 |
| 8086:3504 |           | Intel      | 6311ESB/6321ESB I/OxAPIC ... | 21    |            | 1E34F92251 |
| 8086:2026 | 1028:0738 | Intel      | Sky Lake-E IOAPIC            | 18    |            | 13718F9C0B |
| 8086:2036 | 1028:0738 | Intel      | Sky Lake-E IOxAPIC Config... | 18    |            | 13718F9C0B |
| 1106:5336 |           | VIA Tec... | K8M890CE I/O APIC Interru... | 17    |            | 4BE11BE3F6 |
| 8086:0e2c | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 15    |            | 14CD659D3D |
| 1106:5364 | 1106:5364 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 14    |            | B1490652D3 |
| 8086:3c2c | 1849:3c2c | Intel      | Xeon E5/Core i7 I/O APIC     | 14    |            | 4AE2BC6AFD |
| 8086:0e2c | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 13    |            | 97F8374A85 |
| 8086:2f2c | 1028:0618 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 12    |            | 0E22588D46 |
| 8086:6f2c | 1849:6f2c | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 12    |            | 2BF61F2EC6 |
| 8086:3c2c | 8086:4953 | Intel      | Xeon E5/Core i7 I/O APIC     | 11    |            | 380F10F479 |
| 8086:0e2c | 1458:5000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 10    |            | 349F8DBE53 |
| 8086:2026 | 8086:0000 | Intel      | Sky Lake-E IOAPIC            | 10    |            | 23D528F392 |
| 8086:2036 | 8086:0000 | Intel      | Sky Lake-E IOxAPIC Config... | 10    |            | 23D528F392 |
| 8086:6f2c | 1028:0617 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 10    |            | 6EBA24CF71 |
| 8086:0e2c | 1028:05d4 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 7     |            | 3CF0EB9253 |
| 8086:3c2c | 1028:0495 | Intel      | Xeon E5/Core i7 I/O APIC     | 7     |            | 0C3A459A0E |
| 8086:2026 | 1734:122f | Intel      | Sky Lake-E IOAPIC            | 6     |            | 33A89C4C5A |
| 8086:2036 | 1734:122f | Intel      | Sky Lake-E IOxAPIC Config... | 6     |            | 33A89C4C5A |
| 8086:3c2c | 1028:0496 | Intel      | Xeon E5/Core i7 I/O APIC     | 6     |            | 80E68A5C66 |
| 8086:3c2c | 1734:11b5 | Intel      | Xeon E5/Core i7 I/O APIC     | 6     |            | E689B2DE7A |
| 1106:5351 |           | VIA Tec... | VT3351 I/O APIC Interrupt... | 5     |            | 9B7D8BD5FF |
| 1106:5364 | 1849:5364 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 5     |            | 6410827A2F |
| 8086:0e2c | 17aa:1026 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 5     |            | 99B572DE7F |
| 8086:0e2c | 1849:0e2c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 5     |            | D3383D57EF |
| 8086:2026 | 17aa:1036 | Intel      | Sky Lake-E IOAPIC            | 5     |            | 48145BEF99 |
| 8086:2036 | 17aa:1036 | Intel      | Sky Lake-E IOxAPIC Config... | 5     |            | 48145BEF99 |
| 8086:2f2c | 1028:0619 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 5     |            | D9E5820DB2 |
| 8086:6f2c | 1462:7885 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 5     |            | 53F89BE1B8 |
| 1106:5238 |           | VIA Tec... | K8T890 I/O APIC Interrupt... | 4     |            | D9174E33E4 |
| 1106:5336 | 1043:8297 | VIA Tec... | K8M890CE I/O APIC Interru... | 4     |            | CED2DCBAC9 |
| 1106:5364 | 1019:2125 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 4     |            | 814C427D36 |
| 8086:0326 | 103c:12f1 | Intel      | 6700/6702PXH I/OxAPIC Int... | 4     |            | AD9D1EDCBB |
| 8086:0327 | 103c:12f1 | Intel      | 6700PXH I/OxAPIC Interrup... | 4     |            | AD9D1EDCBB |
| 8086:0e2c | 1734:11b5 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     |            | 8E8715B0CD |
| 8086:2f2c | 1028:064c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | 82F399DFE3 |
| 8086:3c2c | 1028:05d4 | Intel      | Xeon E5/Core i7 I/O APIC     | 4     |            | 12E7B4FF29 |
| 8086:3c2c | 17aa:1026 | Intel      | Xeon E5/Core i7 I/O APIC     | 4     |            | 7EB1F254C9 |
| 8086:3c2c | 17aa:1027 | Intel      | Xeon E5/Core i7 I/O APIC     | 4     |            | E3C6A7B793 |
| 8086:6f2c | 1028:0619 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     |            | 36E6C22CC6 |
| 1106:5327 | 1631:e035 | VIA Tec... | P4M890 I/O APIC Interrupt... | 3     |            | 089D020111 |
| 8086:0326 |           | Intel      | 6700/6702PXH I/OxAPIC Int... | 3     |            | 0511AEEAC6 |
| 8086:0e2c | 1028:05d3 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     |            | 66630328B1 |
| 8086:0e2c | 17aa:1028 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     |            | CD3EBA7A96 |
| 8086:2026 | 1028:0836 | Intel      | Sky Lake-E IOAPIC            | 3     |            | BF5947B943 |
| 8086:2026 | 1028:08b1 | Intel      | Sky Lake-E IOAPIC            | 3     |            | 42BF6B208E |
| 8086:2036 | 1028:08b1 | Intel      | Sky Lake-E IOxAPIC Config... | 3     |            | 42BF6B208E |
| 8086:2036 | 1028:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 3     |            | BF5947B943 |
| 8086:2f2c | 15d9:0844 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     |            | 57BA944640 |
| 8086:3c2c | 1028:0541 | Intel      | Xeon E5/Core i7 I/O APIC     | 3     |            | BEA2C0B6F8 |
| 8086:3c2c | 1462:7735 | Intel      | Xeon E5/Core i7 I/O APIC     | 3     |            | C5B78E1A01 |
| 8086:3c2c | 15d9:0626 | Intel      | Xeon E5/Core i7 I/O APIC     | 3     |            | 42A76FBC95 |
| 1106:5327 | 1849:5327 | VIA Tec... | P4M890 I/O APIC Interrupt... | 2     |            | DAD584057B |
| 1106:5353 |           | VIA Tec... | VX800/VX820 APIC and Cent... | 2     |            | B5933FDE35 |
| 8086:0326 | 15d9:7980 | Intel      | 6700/6702PXH I/OxAPIC Int... | 2     |            | 8EB1C21341 |
| 8086:0327 |           | Intel      | 6700PXH I/OxAPIC Interrup... | 2     |            | 0511AEEAC6 |
| 8086:2026 | 17aa:103c | Intel      | Sky Lake-E IOAPIC            | 2     |            | C4DC7ABDFF |
| 8086:2036 | 17aa:103c | Intel      | Sky Lake-E IOxAPIC Config... | 2     |            | C4DC7ABDFF |
| 8086:3c2c | 1028:05d2 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | 240DD467A0 |
| 8086:3c2c | 1462:7760 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | 748D276276 |
| 8086:3c2c | 17aa:1028 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | 8841F4EB25 |
| 8086:6f2c | 1028:064c | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | E31C5F36AA |
| 8086:6f2c | 1462:7883 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 64A313C9E3 |
| 8086:6f2c | 15d9:0852 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 9EFBA142DD |
| 1106:5308 | 1043:8199 | VIA Tec... | PT894 I/O APIC Interrupt ... | 1     |            | C469D16946 |
| 1106:5308 | 1106:5308 | VIA Tec... | PT894 I/O APIC Interrupt ... | 1     |            | BFA978DEF2 |
| 1106:5336 | 1043:80ed | VIA Tec... | K8M890CE I/O APIC Interru... | 1     |            | 40BED765AC |
| 1106:5351 | 1849:5351 | VIA Tec... | VT3351 I/O APIC Interrupt... | 1     |            | D3A94CD051 |
| 1106:5409 | 1106:5409 | VIA Tec... | VX855/VX875 APIC and Cent... | 1     |            | 655547B351 |
| 8086:0326 | 15d9:d980 | Intel      | 6700/6702PXH I/OxAPIC Int... | 1     |            | 2ABE7E149C |
| 8086:0e2c | 1028:0541 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | BC3B5377F0 |
| 8086:0e2c | 1462:7737 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 725B24FE69 |
| 8086:0e2c | 15d9:062b | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | F791C179A5 |
| 8086:0e2c | 15d9:0702 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | E1213C0B05 |
| 8086:0e2c | 15d9:070a | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F3561AA7D |
| 8086:0e2c | 15d9:070e | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | DABC79444D |
| 8086:1461 | 1014:1461 | Intel      | 82870P2 P64H2 I/OxAPIC       | 1     |            | D6D105AE70 |
| 8086:1461 | 1028:012c | Intel      | 82870P2 P64H2 I/OxAPIC       | 1     |            | 90378ABAC3 |
| 8086:1461 | 15d9:3780 | Intel      | 82870P2 P64H2 I/OxAPIC       | 1     |            | 34867AD122 |
| 8086:2026 | 1849:2026 | Intel      | Sky Lake-E IOAPIC            | 1     |            | D9C47162DC |
| 8086:2036 | 1849:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 1     |            | D9C47162DC |
| 8086:25ac |           | Intel      | 6300ESB I/O Advanced Prog... | 1     |            | 21330F2BD7 |

### Pic (io-apic) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:7451 | 1022:7450 | AMD        | AMD-8131 PCI-X IOAPIC        | 4     |            | A94946D561 |
| 1022:7459 | 1022:7459 | AMD        | AMD-8132 PCI-X IOAPIC        | 1     |            | 68059DB0EE |

### Power pc (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1957:c006 | 1a56:1201 | Freesca... | MPC8308                      | 8     |            | 40C84C9637 |
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
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 66    | sdhci_pci  | D2611BC564 |
| 1022:7806 | 1022:7806 | AMD        | FCH SD Flash Controller      | 63    | sdhci_pci  | 7223BFA184 |
| 8086:31d0 | 8086:7270 | Intel      | SD Host Controller           | 33    | sdhci_pci  | D2611BC564 |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | sdhci_pci  | DBF4F53E70 |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 23    | sdhci_pci  | DBF4F53E70 |
| 8086:9d2b | 8086:7270 | Intel      | Skylake-U/Y SCC: eMMC        | 23    | sdhci_pci  | 1D9DAAB9AA |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 21    | sdhci_pci  | DBF4F53E70 |
| 8086:9d2d | 8086:7270 | Intel      | Sunrise Point-LP Secure D... | 20    | sdhci_pci  | 1D9DAAB9AA |
| 8086:06f5 | 103c:8767 | Intel      | 400 Series Chipset Family... | 13    | sdhci_pci  | 481BC047C1 |
| 8086:31cc | 1458:1000 | Intel      | Celeron/Pentium Silver Pr... | 12    | sdhci_pci  | A973C7F319 |
| 8086:31d0 | 1458:1000 | Intel      | SD Host Controller           | 12    | sdhci_pci  | A973C7F319 |
| 8086:9dc4 | 8086:7270 | Intel      | 300 Series Chipset SD Hos... | 11    | sdhci_pci  | 22DCD2395A |
| 8086:9df5 | 8086:7270 | Intel      | BayHubTech Integrated SD ... | 10    | sdhci_pci  | 22DCD2395A |
| 8086:a375 | 103c:843f | Intel      | 300 Series Chipset Family... | 10    | sdhci_pci  | 2160393DDE |
| 8086:a375 | 103c:8653 | Intel      | 300 Series Chipset Family... | 10    | sdhci_pci  | 3729813684 |
| 1022:7813 | 1022:7806 | AMD        | FCH SD Flash Controller      | 8     | sdhci_pci  | B5E6FC8BA0 |
| 10ec:5209 | 10ec:5209 | Realtek... | RTS5209 PCI Express Card ... | 8     | rtsx_pci   | FFB8AD31E5 |
| 197b:2381 | 103c:2aa2 | JMicron... | Standard SD Host Controller  | 7     | sdhci_pci  | 65E7CD2D3E |
| 197b:2381 | 1297:2005 | JMicron... | Standard SD Host Controller  | 7     | sdhci_pci  | 2154B6A111 |
| 8086:2294 | 1458:1000 | Intel      | Atom/Celeron/Pentium Proc... | 7     | sdhci_pci  | 754EA78372 |
| 8086:a375 | 103c:843b | Intel      | 300 Series Chipset Family... | 7     | sdhci_pci  | 66EA3388B1 |
| 1022:7906 | 17aa:3100 | AMD        | FCH SD Flash Controller      | 6     | sdhci_pci  | BBFCF94452 |
| 8086:a375 | 1849:a375 | Intel      | 300 Series Chipset Family... | 6     | sdhci_pci  | 360ED9475D |
| 8086:a375 | 103c:844c | Intel      | 300 Series Chipset Family... | 5     | sdhci_pci  | 29F7CF64CE |
| 1022:7813 | 1022:7813 | AMD        | FCH SD Flash Controller      | 4     | sdhci_pci  | 745C41CC7D |
| 1022:7906 | 103c:8436 | AMD        | FCH SD Flash Controller      | 4     | sdhci_pci  | 617D5E50FD |
| 1022:7906 | 103c:8459 | AMD        | FCH SD Flash Controller      | 4     | sdhci_pci  | 410E67AB9F |
| 1106:401b | 1028:02f5 | VIA Tec... | VIA Secure Digital host c... | 4     | sdhci_pci  | DA767A9476 |
| 197b:2381 | 103c:2aa6 | JMicron... | Standard SD Host Controller  | 4     | sdhci_pci  | 3EE3ED2E83 |
| 197b:2381 | 1297:2020 | JMicron... | Standard SD Host Controller  | 4     | sdhci_pci  | E8007CF3BE |
| 8086:0f50 |           | Intel      | Atom Processor E3800 Seri... | 4     | sdhci_pci  | D4408F7B0E |
| 8086:a375 | 103c:843c | Intel      | 300 Series Chipset Family... | 4     | sdhci_pci  | E7DF8FECDD |
| 1022:7806 | 103c:2b60 | AMD        | FCH SD Flash Controller      | 3     | sdhci_pci  | 0330705A93 |
| 1217:8620 | 1217:0002 | O2 Micro   | BayHubTech/O2Micro Integr... | 3     | sdhci_pci  | 745C41CC7D |
| 197b:2381 | 1297:4012 | JMicron... | Standard SD Host Controller  | 3     | sdhci_pci  | 24598CF8F9 |
| 8086:5aca | 1458:1000 | Intel      | Celeron N3350/Pentium N42... | 3     | sdhci_pci  | 7741641346 |
| 1106:401b | 1106:401b | VIA Tec... | VIA Secure Digital host c... | 2     | sdhci_pci  | FF6AA83006 |
| 1180:0822 | 1509:4780 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 2     | sdhci_pci  | 4A92B26339 |
| 197b:2381 | 103c:2a97 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | EDEACD39C6 |
| 197b:2381 | 1297:2000 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | FA35222ED7 |
| 197b:2381 | 1297:2023 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | 343861B100 |
| 197b:2381 | 1297:3189 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | 0EFBD74715 |
| 197b:2381 | 1462:6720 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | C630018FEA |
| 197b:2381 | 1558:0390 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | FE920018C7 |
| 197b:2391 | 103c:2af2 | JMicron... | Standard SD Host Controller  | 2     |            | 23E967D7F5 |
| 197b:2391 | 103c:2b00 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | AA243A819D |
| 8086:0f16 | 8086:0f16 | Intel      | Atom Processor Z36xxx/Z37... | 2     | sdhci_pci  | 022E87F791 |
| 8086:19db | 8086:7270 | Intel      | Atom Processor C3000 Seri... | 2     | sdhci_pci  | 2B7A8BA5FC |
| 8086:2295 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 2     | sdhci_pci  | EF051B442A |
| 8086:5ad0 | 1458:1000 | Intel      | Celeron N3350/Pentium N42... | 2     | sdhci_pci  | 7741641346 |
| 8086:811c | 8086:8119 | Intel      | US15W/US15X/US15L/UL11L S... | 2     | sdhci_pci  | 032A1A34DF |
| 8086:811d | 8086:8119 | Intel      | US15W/US15X/US15L/UL11L S... | 2     | sdhci_pci  | 032A1A34DF |
| 8086:9cb5 | 8086:9cb5 | Intel      | Wildcat Point-LP Secure D... | 2     | sdhci_pci  | 0324AFF0A3 |
| 8086:9d2d | 1ae0:006c | Intel      | Sunrise Point-LP Secure D... | 2     | sdhci_pci  | A21EFE9A85 |
| 8086:a375 | 8086:7270 | Intel      | 300 Series Chipset Family... | 2     | sdhci_pci  | 7A2742F439 |
| 104c:8034 | 103c:3085 | Texas I... | PCIxx21/PCIxx11 SD Host C... | 1     | sdhci_pci  | 46E47F957D |
| 104c:803c | 152d:0754 | Texas I... | PCIxx12 SDA Standard Comp... | 1     | sdhci_pci  | 79905DEFFE |
| 1106:401b | 1028:0408 | VIA Tec... | VIA Secure Digital host c... | 1     | sdhci_pci  | B55E0BA8CB |
| 1180:0822 | 1033:8271 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 300E280E8C |
| 1180:0822 | 10cf:12fc | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 347EB6B747 |
| 1180:e822 |           | Ricoh      | MMC/SD Host Controller       | 1     | sdhci_pci  | C0FEDF21BB |
| 1180:e822 | 104d:9060 | Ricoh      | MMC/SD Host Controller       | 1     | sdhci_pci  | 90A75A8826 |
| 1217:7120 | 1025:0124 | O2 Micro   | Integrated MMC/SD Controller | 1     | sdhci_pci  | 1F2C670EC4 |
| 1217:7120 | 14ff:a003 | O2 Micro   | Integrated MMC/SD Controller | 1     | sdhci_pci  | 6647A9CB02 |
| 14e4:16bc | 1025:0742 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 1     | sdhci_pci  | 868EC85E4C |
| 197b:2381 | 1019:2238 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | 7E782321C8 |
| 197b:2381 | 1019:2689 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | 7CF090FB8F |
| 197b:2381 | 1025:0275 | JMicron... | Standard SD Host Controller  | 1     |            | 09734ADC68 |
| 197b:2381 | 1297:2024 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | 3D1F8F75A0 |
| 8086:0f50 | 8086:7270 | Intel      | Atom Processor E3800 Seri... | 1     | sdhci_pci  | 6960F82AE6 |
| 8086:2294 | 1019:9bef | Intel      | Atom/Celeron/Pentium Proc... | 1     | sdhci_pci  | BBED831835 |
| 8086:2294 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 1     | sdhci_pci  | CA4B1C0036 |
| 8086:2294 | 8086:2294 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 2FD537312F |
| 8086:2294 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | sdhci_pci  | EF051B442A |
| 8086:2296 | 8086:2296 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 2FD537312F |
| 8086:2296 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | sdhci_pci  | 6ED2C82A03 |
| 8086:31cc | 1019:a4c6 | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | 11D8FCF22B |
| 8086:31cc | 1043:875e | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | 903B8C265E |
| 8086:5acc | 1849:5acc | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | F07DEA6E74 |
| 8086:5ad0 |           | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 150D692C9A |
| 8086:9d2b |           | Intel      | Skylake-U/Y SCC: eMMC        | 1     | sdhci_pci  | 9DE5E32B25 |
| 8086:9d2b | 8086:2065 | Intel      | Skylake-U/Y SCC: eMMC        | 1     | sdhci_pci  | B1EB5D5F20 |
| 8086:9d2d |           | Intel      | Sunrise Point-LP Secure D... | 1     | sdhci_pci  | 9DE5E32B25 |
| 8086:9d2d | 1025:1223 | Intel      | Sunrise Point-LP Secure D... | 1     | sdhci_pci  | 505F1008B9 |
| 8086:9d2d | 1b0a:01c6 | Intel      | Sunrise Point-LP Secure D... | 1     | sdhci_pci  | 23C5F53C73 |
| 8086:9d2d | 8086:2065 | Intel      | Sunrise Point-LP Secure D... | 1     | sdhci_pci  | B1EB5D5F20 |
| 8086:9d2d | 8086:9d2d | Intel      | Sunrise Point-LP Secure D... | 1     | sdhci_pci  | 4F9AEAAD47 |
| 8086:9dc4 | 8086:2092 | Intel      | 300 Series Chipset SD Hos... | 1     | sdhci_pci  | 4BA8CD9CA2 |
| 8086:9df5 | 8086:2092 | Intel      | BayHubTech Integrated SD ... | 1     | sdhci_pci  | 4BA8CD9CA2 |
| 8086:a375 | 1d92:0254 | Intel      | 300 Series Chipset Family... | 1     | sdhci_pci  | 2F03DC661B |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a324 | 1043:8694 | Intel      | Cannon Lake PCH SPI Contr... | 374   | intel_s... | 22A32FC3F2 |
| 8086:a324 | 8086:7270 | Intel      | Cannon Lake PCH SPI Contr... | 321   | intel_s... | 1C2A383C4F |
| 8086:a324 | 1849:a324 | Intel      | Cannon Lake PCH SPI Contr... | 124   | intel_s... | 2FF008A28D |
| 8086:06a4 | 1043:8694 | Intel      | Comet Lake PCH SPI Contro... | 79    | intel_s... | CAFC4421B2 |
| 8086:06e8 | 1043:8694 | Intel      | Comet Lake PCH Serial IO ... | 75    | intel_l... | CAFC4421B2 |
| 8086:06e9 | 1043:8694 | Intel      | Comet Lake PCH Serial IO ... | 75    | intel_l... | CAFC4421B2 |
| 8086:06a4 | 8086:7270 | Intel      | Comet Lake PCH SPI Contro... | 49    | intel_s... | 7983497985 |
| 8086:43a4 | 1043:8694 | Intel      | Tiger Lake-H SPI Controller  | 46    | intel_spi  | B9C2FEC8AA |
| 8086:43e8 | 1043:8694 | Intel      | Tiger Lake-H Serial IO I2... | 46    | intel_l... | B9C2FEC8AA |
| 8086:06a4 | 1849:06a4 | Intel      | Comet Lake PCH SPI Contro... | 44    | intel_s... | AD42FA5D08 |
| 8086:a324 | 1462:7b98 | Intel      | Cannon Lake PCH SPI Contr... | 39    | intel_s... | FC6F79950A |
| 1002:73a4 | 1002:0408 | AMD        | Navi 21 USB                  | 38    | i2c_des... | 58E3F9C07F |
| 8086:a324 | 1025:1238 | Intel      | Cannon Lake PCH SPI Contr... | 35    | intel_s... | B961168B44 |
| 10de:1adb | 1458:3fc1 | Nvidia     | TU106 USB Type-C UCSI Con... | 33    | i2c_nvi... | 233AD54EF9 |
| 8086:43e9 | 1043:8694 | Intel      | 500 Series Chipset Family... | 32    | intel_l... | B9C2FEC8AA |
| 10de:1aed | 1458:3fc8 | Nvidia     | TU116 USB Type-C UCSI Con... | 30    | i2c_nvi... | 7C99A6ED29 |
| 8086:43a4 |           | Intel      | Tiger Lake-H SPI Controller  | 26    | intel_s... | BE8B71D264 |
| 10de:1ad9 | 1458:4001 | Nvidia     | TU104 USB Type-C UCSI Con... | 25    | i2c_nvi... | 9DA822B1B7 |
| 8086:06a4 | 1462:7c75 | Intel      | Comet Lake PCH SPI Contro... | 25    | intel_spi  | B8A7B6080F |
| 8086:a324 | 1462:7b17 | Intel      | Cannon Lake PCH SPI Contr... | 25    | intel_spi  | D200B00925 |
| 10de:1aed | 1458:4013 | Nvidia     | TU116 USB Type-C UCSI Con... | 24    | i2c_nvi... | EC939FB289 |
| 10de:1aed | 1462:3792 | Nvidia     | TU116 USB Type-C UCSI Con... | 24    | i2c_nvi... | 26C1610442 |
| 10de:1aed | 1462:c75a | Nvidia     | TU116 USB Type-C UCSI Con... | 23    | i2c_nvi... | 35A339AB74 |
| 8086:a324 | 1028:085c | Intel      | Cannon Lake PCH SPI Contr... | 21    | intel_spi  | D4F071950B |
| 10de:1adb | 1458:37c2 | Nvidia     | TU106 USB Type-C UCSI Con... | 20    | i2c_nvi... | FB5109B608 |
| 10de:1aed | 1462:3750 | Nvidia     | TU116 USB Type-C UCSI Con... | 20    | nvidia_gpu | DB63BBCD46 |
| 10de:1aed | 1462:8d95 | Nvidia     | TU116 USB Type-C UCSI Con... | 20    | i2c_nvi... | 0EAAAA663B |
| 8086:43a4 | 1849:43a4 | Intel      | Tiger Lake-H SPI Controller  | 20    | intel_s... | 1FCC4E6895 |
| 8086:a324 | 103c:843b | Intel      | Cannon Lake PCH SPI Contr... | 20    | intel_s... | 66EA3388B1 |
| 8086:a368 | 103c:843b | Intel      | Cannon Lake PCH Serial IO... | 20    | intel_l... | 66EA3388B1 |
| 8086:a369 | 103c:843b | Intel      | Cannon Lake PCH Serial IO... | 20    | intel_l... | 66EA3388B1 |
| 10de:1ad9 | 10de:139f | Nvidia     | TU104 USB Type-C UCSI Con... | 19    | i2c_nvi... | C4800A930A |
| 10de:1aed | 10de:21c4 | Nvidia     | TU116 USB Type-C UCSI Con... | 19    | i2c_nvi... | 3147AE8C58 |
| 10de:1aed | 1462:375a | Nvidia     | TU116 USB Type-C UCSI Con... | 18    | i2c_nvi... | 0981774043 |
| 10de:1adb | 1462:3734 | Nvidia     | TU106 USB Type-C UCSI Con... | 17    | nvidia_gpu | 201BC8D044 |
| 10de:1aed | 1458:4014 | Nvidia     | TU116 USB Type-C UCSI Con... | 17    | i2c_nvi... | EAF4F27F7A |
| 10de:1ad9 | 3842:2068 | Nvidia     | TU104 USB Type-C UCSI Con... | 16    | i2c_nvi... | 45605570FE |
| 10de:1aed | 1462:3850 | Nvidia     | TU116 USB Type-C UCSI Con... | 16    | nvidia_gpu | BC3E2DA7F3 |
| 8086:a324 | 1019:a4a3 | Intel      | Cannon Lake PCH SPI Contr... | 16    | intel_s... | 6D2F43A452 |
| 8086:a324 | 1462:7b22 | Intel      | Cannon Lake PCH SPI Contr... | 16    | intel_s... | A850D4D993 |
| 10de:1ad9 | 1458:3fc1 | Nvidia     | TU104 USB Type-C UCSI Con... | 15    | i2c_nvi... | 4F0C804D51 |
| 10de:1ad9 | 1462:c729 | Nvidia     | TU104 USB Type-C UCSI Con... | 15    | i2c_nvi... | FC6F79950A |
| 10de:1adb | 1458:3ff1 | Nvidia     | TU106 USB Type-C UCSI Con... | 15    | i2c_nvi... | A0ED3C6558 |
| 10de:1adb | 1462:3755 | Nvidia     | TU106 USB Type-C UCSI Con... | 15    | i2c_nvi... | BDA34579B0 |
| 10de:1aed | 10de:1324 | Nvidia     | TU116 USB Type-C UCSI Con... | 15    | i2c_nvi... | CDB8DD9B53 |
| 10de:1aed | 1458:3fbe | Nvidia     | TU116 USB Type-C UCSI Con... | 15    | i2c_nvi... | 8D0D41E1CB |
| 8086:a324 | 1462:7b24 | Intel      | Cannon Lake PCH SPI Contr... | 15    | intel_s... | A9FC1D1222 |
| 10de:1ad7 | 1043:866a | Nvidia     | TU102 USB Type-C UCSI Con... | 14    | i2c_nvi... | C6239B2672 |
| 10de:1aed | 1462:c758 | Nvidia     | TU116 USB Type-C UCSI Con... | 14    | i2c_nvi... | 7E563A9D44 |
| 8086:a324 | 1462:7b51 | Intel      | Cannon Lake PCH SPI Contr... | 14    |            | E40A4C5A0C |
| 10de:1ad7 | 10de:12a3 | Nvidia     | TU102 USB Type-C UCSI Con... | 13    | i2c_nvi... | 0ADC8FC04D |
| 10de:1ad9 | 1458:4008 | Nvidia     | TU104 USB Type-C UCSI Con... | 13    | i2c_nvi... | C0BECED761 |
| 10de:1aed | 1043:874b | Nvidia     | TU116 USB Type-C UCSI Con... | 13    | i2c_nvi... | 2A39EF919C |
| 10de:1aed | 10de:13d3 | Nvidia     | TU116 USB Type-C UCSI Con... | 13    | i2c_nvi... | 8BFD432FBA |
| 10de:1aed | 1458:3fc3 | Nvidia     | TU116 USB Type-C UCSI Con... | 13    | i2c_nvi... | 530994C225 |
| 10de:1aed | 1458:401a | Nvidia     | TU116 USB Type-C UCSI Con... | 13    | i2c_nvi... | 41D1A4F015 |
| 8086:06a4 | 103c:8767 | Intel      | Comet Lake PCH SPI Contro... | 13    | intel_s... | 481BC047C1 |
| 8086:06e8 | 103c:8767 | Intel      | Comet Lake PCH Serial IO ... | 13    | intel_l... | 481BC047C1 |
| 8086:5ac8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 12    | pwm_lpss   | DBF4F53E70 |
| 8086:a324 | 1734:1246 | Intel      | Cannon Lake PCH SPI Contr... | 12    |            | 0184E22E18 |
| 10de:1ad9 | 1462:372d | Nvidia     | TU104 USB Type-C UCSI Con... | 11    | i2c_nvi... | 391C21DB23 |
| 10de:1ad9 | 3842:3071 | Nvidia     | TU104 USB Type-C UCSI Con... | 11    | i2c_nvi... | D200B00925 |
| 10de:1adb | 1043:8670 | Nvidia     | TU106 USB Type-C UCSI Con... | 11    | nvidia_gpu | E2C619E8DD |
| 10de:1adb | 1462:c752 | Nvidia     | TU106 USB Type-C UCSI Con... | 11    | i2c_nvi... | A72102FDB0 |
| 10de:1aed | 10de:139d | Nvidia     | TU116 USB Type-C UCSI Con... | 11    | i2c_nvi... | 60FFB9D428 |
| 8086:43a4 | 1462:7d09 | Intel      | Tiger Lake-H SPI Controller  | 11    | intel_spi  | D8A7A695AE |
| 8086:9da4 | 8086:7270 | Intel      | Cannon Point-LP SPI Contr... | 11    |            | 22DCD2395A |
| 8086:9dc5 | 8086:7270 | Intel      | Cannon Point-LP Serial IO... | 11    | intel_l... | 22DCD2395A |
| 8086:9de8 | 8086:7270 | Intel      | Cannon Point-LP Serial IO... | 11    | intel_l... | 22DCD2395A |
| 8086:a324 | 1025:123c | Intel      | Cannon Lake PCH SPI Contr... | 11    | intel_spi  | C3E994EBDA |
| 8086:a324 | 1462:7b33 | Intel      | Cannon Lake PCH SPI Contr... | 11    | intel_s... | 64F79E5D38 |
| 8086:a324 | 1462:7b53 | Intel      | Cannon Lake PCH SPI Contr... | 11    | intel_s... | E472116CCB |
| 8086:a324 | 17aa:36eb | Intel      | Cannon Lake PCH SPI Contr... | 11    | intel_s... | F8C3745C72 |
| 10de:1ad9 | 1043:8708 | Nvidia     | TU104 USB Type-C UCSI Con... | 10    | i2c_nvi... | B87A3ED6F4 |
| 10de:1adb | 10de:1f08 | Nvidia     | TU106 USB Type-C UCSI Con... | 10    | i2c_nvi... | 9E65E72132 |
| 10de:1adb | 1458:3fda | Nvidia     | TU106 USB Type-C UCSI Con... | 10    | i2c_nvi... | 94848F2347 |
| 10de:1adb | 1462:c757 | Nvidia     | TU106 USB Type-C UCSI Con... | 10    | i2c_nvi... | 4379B423F0 |
| 10de:1aed | 1043:873a | Nvidia     | TU116 USB Type-C UCSI Con... | 10    | i2c_nvi... | 04123E977F |
| 10de:1aed | 1458:401b | Nvidia     | TU116 USB Type-C UCSI Con... | 10    | i2c_nvi... | A45408417E |
| 10de:1aed | 1458:4028 | Nvidia     | TU116 USB Type-C UCSI Con... | 10    | i2c_nvi... | 4B2E1DDC09 |
| 10de:1aed | 19da:5527 | Nvidia     | TU116 USB Type-C UCSI Con... | 10    | i2c_nvi... | DA602634B5 |
| 8086:06a4 | 1462:7c79 | Intel      | Comet Lake PCH SPI Contro... | 10    | intel_spi  | 5B55E39C35 |
| 8086:9de9 | 8086:7270 | Intel      | Cannon Point-LP Serial IO... | 10    | intel_l... | 22DCD2395A |
| 8086:a324 | 1028:085a | Intel      | Cannon Lake PCH SPI Contr... | 10    | intel_s... | 6CED4F2897 |
| 8086:a324 | 1028:0871 | Intel      | Cannon Lake PCH SPI Contr... | 10    | intel_s... | DB2503F46F |
| 8086:a324 | 103c:843f | Intel      | Cannon Lake PCH SPI Contr... | 10    | intel_s... | 2160393DDE |
| 8086:a324 | 103c:8653 | Intel      | Cannon Lake PCH SPI Contr... | 10    | intel_s... | 3729813684 |
| 8086:a324 | 17aa:3140 | Intel      | Cannon Lake PCH SPI Contr... | 10    | intel_s... | 550DAD499F |
| 8086:a368 | 1028:085a | Intel      | Cannon Lake PCH Serial IO... | 10    | intel_l... | 6CED4F2897 |
| 8086:a368 | 1028:0871 | Intel      | Cannon Lake PCH Serial IO... | 10    | intel_l... | DB2503F46F |
| 8086:a368 | 103c:843f | Intel      | Cannon Lake PCH Serial IO... | 10    | intel_lpss | 2160393DDE |
| 8086:a368 | 103c:8653 | Intel      | Cannon Lake PCH Serial IO... | 10    | intel_l... | 3729813684 |
| 8086:a369 | 103c:843f | Intel      | Cannon Lake PCH Serial IO... | 10    | intel_lpss | 2160393DDE |
| 8086:a369 | 103c:8653 | Intel      | Cannon Lake PCH Serial IO... | 10    | intel_l... | 3729813684 |
| 10de:1ad9 | 1462:3722 | Nvidia     | TU104 USB Type-C UCSI Con... | 9     | i2c_nvi... | F5C02601D0 |
| 10de:1adb | 10de:12fd | Nvidia     | TU106 USB Type-C UCSI Con... | 9     | i2c_nvi... | 30591F341D |
| 10de:1aed | 10de:2184 | Nvidia     | TU116 USB Type-C UCSI Con... | 9     | i2c_nvi... | 54E89A0F5A |
| 8086:a324 | 1028:092e | Intel      | Cannon Lake PCH SPI Contr... | 9     | intel_s... | 7952948421 |
| 8086:a324 | 1028:0930 | Intel      | Cannon Lake PCH SPI Contr... | 9     | intel_s... | 438EA99933 |
| 8086:a324 | 103c:843c | Intel      | Cannon Lake PCH SPI Contr... | 9     | intel_s... | E7DF8FECDD |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8c3d | 1458:1c3a | Intel      | 8 Series/C220 Series Chip... | 147   | serial     | FB7BEB9612 |
| 8086:8c3d | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 120   | serial     | CC73A253B3 |
| 8086:1e3d | 103c:3397 | Intel      | 7 Series/C210 Series Chip... | 104   | serial     | BF9875C5AC |
| 8086:29b7 | 1028:0211 | Intel      | 82Q35 Express Serial KT C... | 104   | serial     | 7E7D0BC489 |
| 8086:1e3d | 1028:0577 | Intel      | 7 Series/C210 Series Chip... | 97    | serial     | E1B966B80D |
| 8086:2e17 | 1028:0420 | Intel      | 4 Series Chipset Serial K... | 96    | serial     | 476F78A010 |
| 8086:2e17 | 1028:027f | Intel      | 4 Series Chipset Serial K... | 87    | serial     | F27A29129F |
| 8086:1e3d | 103c:339a | Intel      | 7 Series/C210 Series Chip... | 85    | serial     | 28DA82FF00 |
| 8086:1c3d | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 82    | serial     | C5719C54C2 |
| 8086:1c3d | 1028:047e | Intel      | 6 Series/C200 Series Chip... | 80    | serial     | 6AF9EA19B5 |
| 8086:8c3d | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 79    | serial     | B9E492678D |
| 8086:1c3d | 103c:1495 | Intel      | 6 Series/C200 Series Chip... | 72    | serial     | E7C0F59F92 |
| 8086:2e17 | 103c:3048 | Intel      | 4 Series Chipset Serial K... | 69    | serial     | B62359FCB1 |
| 8086:1c3d | 103c:1497 | Intel      | 6 Series/C200 Series Chip... | 67    | serial     | C0FB875CA5 |
| 8086:8c3d | 103c:18e7 | Intel      | 8 Series/C220 Series Chip... | 66    | serial     | 94C750BA4B |
| 8086:2e17 | 1734:114c | Intel      | 4 Series Chipset Serial K... | 64    | serial     | 6B08158329 |
| 8086:3b67 | 8086:0036 | Intel      | 5 Series/3400 Series Chip... | 55    | serial     | E5F7233230 |
| 8086:29b7 | 103c:2818 | Intel      | 82Q35 Express Serial KT C... | 53    | serial     | 40DA7A8AE9 |
| 8086:1e3d | 1028:052c | Intel      | 7 Series/C210 Series Chip... | 46    | serial     | 79E64FF0D3 |
| 8086:2e17 | 17aa:3048 | Intel      | 4 Series Chipset Serial K... | 44    | serial     | ED1D55E70A |
| 8086:1d3d | 103c:1589 | Intel      | C600/X79 series chipset K... | 40    | serial     | 49C747EFAD |
| 8086:8c3d | 17aa:3097 | Intel      | 8 Series/C220 Series Chip... | 40    | serial     | A5026C4013 |
| 8086:2e17 | 103c:3646 | Intel      | 4 Series Chipset Serial K... | 39    | serial     | 60FB363058 |
| 8086:1c3d | 17aa:3070 | Intel      | 6 Series/C200 Series Chip... | 38    | serial     | 1ECB7A6910 |
| 8086:1e3d | 17aa:3083 | Intel      | 7 Series/C210 Series Chip... | 38    | serial     | DF15656FCE |
| 8086:2e17 | 103c:3034 | Intel      | 4 Series Chipset Serial K... | 38    | serial     | D05CCA1A32 |
| 8086:1e3d | 103c:3396 | Intel      | 7 Series/C210 Series Chip... | 35    | serial     | 147C8ED96C |
| 8086:1c3d | 103c:1494 | Intel      | 6 Series/C200 Series Chip... | 34    | serial     | AE5165603A |
| 8086:3b67 | 103c:304a | Intel      | 5 Series/3400 Series Chip... | 34    | serial     | 311C6C4C69 |
| 8086:a13d | 1028:06b9 | Intel      | 100 Series/C230 Series Ch... | 33    | serial     | 92F15AEB4D |
| 8086:8c3d | 17aa:30a3 | Intel      | 8 Series/C220 Series Chip... | 31    | serial     | 068BEE7912 |
| 8086:2e17 | 103c:3035 | Intel      | 4 Series Chipset Serial K... | 30    | serial     | 6914386D3D |
| 8086:2e17 | 1028:0276 | Intel      | 4 Series Chipset Serial K... | 29    | serial     | 5814B0C5B0 |
| 8086:8d3d | 103c:212b | Intel      | C610/X99 series chipset K... | 28    | serial     | 9D2A807F08 |
| 9710:9865 | a000:1000 | MosChip... | PCI 9865 Multi-I/O Contro... | 28    | parport_pc | 9C631B51B1 |
| 8086:1e3d | 17aa:3084 | Intel      | 7 Series/C210 Series Chip... | 26    | serial     | C7D7CACA33 |
| 8086:8c3d | 1028:05a5 | Intel      | 8 Series/C220 Series Chip... | 25    | serial     | 827CB9A77A |
| 8086:3b67 | 8086:3b67 | Intel      | 5 Series/3400 Series Chip... | 24    | serial     | BF6D27F32D |
| 8086:1c3d | 17aa:3077 | Intel      | 6 Series/C200 Series Chip... | 23    | serial     | 3E625A72D2 |
| 8086:1d3d | 103c:158a | Intel      | C600/X79 series chipset K... | 23    | serial     | 6C22E51BFC |
| 8086:2e17 | 17aa:3047 | Intel      | 4 Series Chipset Serial K... | 23    | serial     | 74363F1551 |
| 8086:a13d | 1734:121d | Intel      | 100 Series/C230 Series Ch... | 23    | serial     | 8B5C674CB9 |
| 10ec:816a | 10ec:8168 | Realtek... | RTL8111xP UART #1            | 22    | serial     | 07A5B3C465 |
| 8086:3b67 | 1028:02da | Intel      | 5 Series/3400 Series Chip... | 22    | serial     | 51D64C0798 |
| 8086:8c3d | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 22    | serial     | 588E2A68E5 |
| 8086:3b67 | 103c:304b | Intel      | 5 Series/3400 Series Chip... | 21    | serial     | 643A84AE14 |
| 8086:8c3d | 103c:1905 | Intel      | 8 Series/C220 Series Chip... | 21    | serial     | 99B9973F19 |
| 8086:1c3d | 8086:2008 | Intel      | 6 Series/C200 Series Chip... | 20    | serial     | 36A4037B9D |
| 8086:8c3d | 17aa:309f | Intel      | 8 Series/C220 Series Chip... | 20    | serial     | 6D09C42ADE |
| 8086:1e3d | 103c:3398 | Intel      | 7 Series/C210 Series Chip... | 18    | serial     | 2B8EFC01BA |
| 8086:2e17 | 103c:3648 | Intel      | 4 Series Chipset Serial K... | 18    | serial     | A21990541E |
| 8086:a2bd | 1028:07a1 | Intel      | 200 Series Chipset Family... | 18    | serial     | E221C43AF2 |
| 1c00:3250 | 1c00:3250 |            | WCH PCI Express              | 17    | parport... | 88316ED281 |
| 8086:1c3d | 103c:1496 | Intel      | 6 Series/C200 Series Chip... | 17    | serial     | F438FDB757 |
| 8086:1d3d | 103c:158b | Intel      | C600/X79 series chipset K... | 17    | serial     | D7836BB820 |
| 8086:29b7 | 103c:2819 | Intel      | 82Q35 Express Serial KT C... | 17    | serial     | 74CFC314C6 |
| 8086:29b7 | 17aa:3038 | Intel      | 82Q35 Express Serial KT C... | 17    | serial     | F094A159CC |
| 8086:2e17 | 103c:3647 | Intel      | 4 Series Chipset Serial K... | 17    | serial     | 2DB1DBEF9F |
| 8086:2e17 | 8086:1003 | Intel      | 4 Series Chipset Serial K... | 17    | serial     | 543E15E027 |
| 8086:a13d | 103c:805d | Intel      | 100 Series/C230 Series Ch... | 17    | serial     | E6583FB63A |
| 9710:9912 | a000:1000 | MosChip... | PCIe 9912 Multi-I/O Contr... | 17    | serial     | 414008F0A3 |
| 8086:8c3d | 17aa:30a5 | Intel      | 8 Series/C220 Series Chip... | 16    | serial     | 51B3FC2150 |
| 8086:29b7 | 1043:8295 | Intel      | 82Q35 Express Serial KT C... | 15    | serial     | D37FED8D0F |
| 8086:29b7 | 1734:10fc | Intel      | 82Q35 Express Serial KT C... | 15    | serial     | 980A095C0F |
| 8086:8c3d | 103c:1825 | Intel      | 8 Series/C220 Series Chip... | 15    | serial     | FF75BE1EA3 |
| 8086:1e3d | 1458:1c3a | Intel      | 7 Series/C210 Series Chip... | 14    | serial     | 3BEB3704CF |
| 8086:1e3d | 17aa:3086 | Intel      | 7 Series/C210 Series Chip... | 14    | serial     | EA812BCD70 |
| 8086:1e3d | 8086:2035 | Intel      | 7 Series/C210 Series Chip... | 14    | serial     | 391C101A92 |
| 8086:2e17 | 17aa:3049 | Intel      | 4 Series Chipset Serial K... | 14    | serial     | 0A417745C3 |
| 8086:8c3d | 103c:18e4 | Intel      | 8 Series/C220 Series Chip... | 14    | serial     | FBD08BC910 |
| 8086:8c3d | 103c:18e5 | Intel      | 8 Series/C220 Series Chip... | 14    | serial     | 6859BB4250 |
| 8086:a13d | 17aa:30be | Intel      | 100 Series/C230 Series Ch... | 14    | serial     | 5ADC857043 |
| 8086:3b67 | 17aa:3059 | Intel      | 5 Series/3400 Series Chip... | 13    | serial     | 4486D669B3 |
| 8086:a13d | 1028:07c5 | Intel      | 100 Series/C230 Series Ch... | 13    | serial     | 29F013D2E2 |
| 8086:a13d | 103c:8055 | Intel      | 100 Series/C230 Series Ch... | 13    | serial     | 12A1144916 |
| 9710:9835 | 1000:0002 | MosChip... | PCI 9835 Multi-I/O Contro... | 13    | parport... | CAD3B9B0F1 |
| 8086:2e17 | 103c:3036 | Intel      | 4 Series Chipset Serial K... | 12    | serial     | C2C9087398 |
| 9710:9922 | a000:1000 | MosChip... | MCS9922 PCIe Multi-I/O Co... | 12    | serial     | FE57B848C7 |
| 10ec:816a | 1458:e000 | Realtek... | RTL8111xP UART #1            | 11    | serial     | 3D75B079F5 |
| 10ec:816b | 1458:e000 | Realtek... | RTL8111xP UART #2            | 11    | serial     | 3D75B079F5 |
| 8086:a13d | 103c:8054 | Intel      | 100 Series/C230 Series Ch... | 11    | serial     | BA0E318652 |
| 10ec:816a | 17aa:3089 | Realtek... | RTL8111xP UART #1            | 10    | serial     | 2891FE25E6 |
| 10ec:816b | 17aa:3089 | Realtek... | RTL8111xP UART #2            | 10    | serial     | 2891FE25E6 |
| 1c00:2273 | 1c00:2273 |            | WCH PCI                      | 10    | serial     | 069C508E80 |
| 8086:1e3d | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 10    | serial     | DC49777CE8 |
| 8086:8c3d | 103c:1906 | Intel      | 8 Series/C220 Series Chip... | 10    | serial     | 62C3738CF9 |
| 8086:8d3d | 103c:2129 | Intel      | C610/X99 series chipset K... | 10    | serial     | 8DE5BAE655 |
| 4348:3253 | 4348:3253 | WCH.CN     | CH352 PCI Dual Serial Por... | 9     | serial     | D6A6EF19FD |
| 8086:1c3d | 1028:0498 | Intel      | 6 Series/C200 Series Chip... | 9     | serial     | 497C824FD5 |
| 8086:1c3d | 17aa:3078 | Intel      | 6 Series/C200 Series Chip... | 9     | serial     | DF033C67A8 |
| 8086:1e3d | 103c:1791 | Intel      | 7 Series/C210 Series Chip... | 9     | serial     | 9DE8DDBD32 |
| 8086:2997 | 103c:2801 | Intel      | 82Q963/Q965 KT Controller    | 9     | serial     | 10AA52CEF5 |
| 8086:8c3d | 103c:21d0 | Intel      | 8 Series/C220 Series Chip... | 9     | serial     | 4CEE9A5C3D |
| 8086:8d3d | 1028:0617 | Intel      | C610/X99 series chipset K... | 9     | serial     | 8FDDBF28A1 |
| 8086:a13d | 103c:8056 | Intel      | 100 Series/C230 Series Ch... | 9     | serial     | 3DE6337339 |
| 10ec:816a | 1734:1178 | Realtek... | RTL8111xP UART #1            | 8     | serial     | B07993A438 |
| 10ec:816b | 1734:1178 | Realtek... | RTL8111xP UART #2            | 8     | serial     | B07993A438 |
| 1fd4:1999 | 1fd4:0001 | SUNIX      | Multiport serial controller  | 8     | serial     | FF477E5A71 |
| 8086:1c3d | 103c:1587 | Intel      | 6 Series/C200 Series Chip... | 8     | serial     | 0D99C162A3 |
| 8086:1d3d | 17aa:1026 | Intel      | C600/X79 series chipset K... | 8     | serial     | 99B572DE7F |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a379 | 1458:8888 | Intel      | Cannon Lake PCH Thermal C... | 306   | intel_p... | 1C2A383C4F |
| 8086:a131 | 1849:a131 | Intel      | 100 Series/C230 Series Ch... | 205   | intel_p... | 6B4C3F811B |
| 8086:a2b1 | 1849:a2b1 | Intel      | 200 Series PCH Thermal Su... | 178   |            | 79E6EF3655 |
| 8086:a379 | 1849:a379 | Intel      | Cannon Lake PCH Thermal C... | 124   | intel_p... | 2FF008A28D |
| 8086:a131 | 1458:8888 | Intel      | 100 Series/C230 Series Ch... | 117   | intel_p... | 36BF6DAB37 |
| 8086:a3b1 | 8086:7270 | Intel      | Comet Lake PCH-V Thermal ... | 81    |            | AE3E01FEF8 |
| 8086:a131 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 71    | intel_p... | EC7609239E |
| 8086:8c24 | 1734:11ea | Intel      | 8 Series Chipset Family T... | 70    | intel_p... | 066CB46C80 |
| 8086:1e24 | 1734:11d6 | Intel      | 7 Series/C210 Series Chip... | 53    |            | 7A70FC2989 |
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 53    | process... | 9333E233D6 |
| 8086:a131 | 1734:121d | Intel      | 100 Series/C230 Series Ch... | 52    | intel_p... | C3479871D7 |
| 8086:a131 | 1462:7a15 | Intel      | 100 Series/C230 Series Ch... | 47    | intel_p... | 059A06E95C |
| 8086:06f9 | 1458:8888 | Intel      | Comet Lake PCH Thermal Co... | 46    | intel_p... | 7983497985 |
| 8086:06f9 | 1849:06f9 | Intel      | Comet Lake PCH Thermal Co... | 44    | intel_p... | AD42FA5D08 |
| 8086:a131 | 1028:06b9 | Intel      | 100 Series/C230 Series Ch... | 44    | intel_p... | 92F15AEB4D |
| 8086:a131 | 1462:7971 | Intel      | 100 Series/C230 Series Ch... | 44    | intel_p... | 77006702F8 |
| 8086:9d31 | 8086:7270 | Intel      | Sunrise Point-LP Thermal ... | 43    | intel_p... | B5BD43E606 |
| 8086:a2b1 | 1043:873c | Intel      | 200 Series PCH Thermal Su... | 43    |            | EACC1E3F66 |
| 8086:31b4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 39    | intel_l... | D2611BC564 |
| 8086:8c24 | 1025:0750 | Intel      | 8 Series Chipset Family T... | 39    | intel_p... | 4AA46E7581 |
| 8086:a379 | 1462:7b98 | Intel      | Cannon Lake PCH Thermal C... | 39    | intel_p... | FC6F79950A |
| 8086:318c | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 35    | process... | D2611BC564 |
| 8086:a379 | 1025:1238 | Intel      | Cannon Lake PCH Thermal C... | 35    | intel_p... | B961168B44 |
| 8086:318c | 1849:318c | Intel      | Celeron/Pentium Silver Pr... | 34    | process... | 2AD609C0C5 |
| 8086:31b6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 34    | intel_l... | D2611BC564 |
| 8086:31b8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 34    | intel_l... | D2611BC564 |
| 8086:31ba | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 29    | intel_lpss | D2611BC564 |
| 8086:a2b1 | 1028:07a3 | Intel      | 200 Series PCH Thermal Su... | 29    |            | 9D38BA75C7 |
| 8086:a3b1 | 1849:a3b1 | Intel      | Comet Lake PCH-V Thermal ... | 29    |            | B9DEC327EE |
| 8086:a2b1 | 1462:7a70 | Intel      | 200 Series PCH Thermal Su... | 28    |            | D6BE998202 |
| 8086:a2b1 | 1028:07a1 | Intel      | 200 Series PCH Thermal Su... | 27    |            | E221C43AF2 |
| 8086:a2e0 | 1028:07a1 | Intel      | 200 Series PCH Serial IO ... | 27    | intel_l... | E221C43AF2 |
| 8086:31bc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 26    | intel_l... | D2611BC564 |
| 8086:31be | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 26    | intel_l... | D2611BC564 |
| 8086:31c0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 26    | intel_l... | D2611BC564 |
| 8086:31ee | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 26    | intel_l... | D2611BC564 |
| 8086:a2a7 | 103c:82f2 | Intel      | 200 Series/Z370 Chipset F... | 26    | intel_l... | FEF1D213B4 |
| 8086:a2e0 | 103c:82f2 | Intel      | 200 Series PCH Serial IO ... | 26    | intel_l... | FEF1D213B4 |
| 8086:a2e1 | 103c:82f2 | Intel      | 200 Series PCH Serial IO ... | 26    | intel_l... | FEF1D213B4 |
| 8086:06f9 | 1462:7c75 | Intel      | Comet Lake PCH Thermal Co... | 25    | intel_p... | B8A7B6080F |
| 8086:9d27 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 25    | intel_l... | B5BD43E606 |
| 8086:a160 | 1462:7971 | Intel      | 100 Series/C230 Series Ch... | 25    | intel_l... | 77006702F8 |
| 8086:a161 | 1462:7971 | Intel      | 100 Series/C230 Series Ch... | 25    | intel_l... | 77006702F8 |
| 8086:a379 | 1462:7b17 | Intel      | Cannon Lake PCH Thermal C... | 25    | intel_p... | D200B00925 |
| 8086:a160 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 24    | intel_l... | 78FAFC3314 |
| 8086:a161 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 24    | intel_l... | 78FAFC3314 |
| 8086:a131 | 1462:7978 | Intel      | 100 Series/C230 Series Ch... | 23    | intel_p... | 2A068AFC0C |
| 8086:a2b1 | 1462:7b48 | Intel      | 200 Series PCH Thermal Su... | 23    |            | E7742AA472 |
| 8086:a131 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 22    | intel_p... | 24FDD41F71 |
| 8086:a2a7 | 1028:0859 | Intel      | 200 Series/Z370 Chipset F... | 22    | intel_l... | 6F2F7D7453 |
| 8086:a2b1 | 1462:7a72 | Intel      | 200 Series PCH Thermal Su... | 22    |            | 24329438D1 |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 21    | intel_l... | E44BED775C |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 21    | intel_l... | E44BED775C |
| 8086:a131 | 1028:06bb | Intel      | 100 Series/C230 Series Ch... | 21    | intel_p... | EA9F525CF5 |
| 8086:a379 | 1028:085c | Intel      | Cannon Lake PCH Thermal C... | 21    | intel_p... | D4F071950B |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 20    | intel_l... | E44BED775C |
| 8086:a127 | 1462:7971 | Intel      | 100 Series/C230 Series Ch... | 20    | intel_l... | 77006702F8 |
| 8086:a127 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 20    | intel_l... | 78FAFC3314 |
| 8086:a379 | 103c:843b | Intel      | Cannon Lake PCH Thermal C... | 20    | intel_p... | 66EA3388B1 |
| 8086:a131 | 1025:108e | Intel      | 100 Series/C230 Series Ch... | 19    | intel_p... | 066A7CE533 |
| 8086:a131 | 1462:7982 | Intel      | 100 Series/C230 Series Ch... | 19    | intel_p... | B396E1C4F4 |
| 8086:31ac | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 18    | intel_lpss | 74BC82899E |
| 8086:31ae | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 18    | intel_lpss | 74BC82899E |
| 8086:31b0 | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 18    | intel_lpss | 74BC82899E |
| 8086:31b2 | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 18    | intel_lpss | 74BC82899E |
| 8086:31b4 | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 18    | intel_lpss | 74BC82899E |
| 8086:31b6 | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 18    | intel_lpss | 74BC82899E |
| 8086:31b8 | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 18    | intel_lpss | 74BC82899E |
| 8086:31ba | 1025:1226 | Intel      | Celeron/Pentium Silver Pr... | 18    | intel_lpss | 74BC82899E |
| 8086:a131 | 103c:805d | Intel      | 100 Series/C230 Series Ch... | 18    | intel_p... | E6583FB63A |
| 8086:a2b1 | 1028:0738 | Intel      | 200 Series PCH Thermal Su... | 18    |            | 13718F9C0B |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 17    | intel_l... | 7ABD7A20DF |
| 8086:a131 | 1028:06b7 | Intel      | 100 Series/C230 Series Ch... | 17    | intel_p... | 9885D45D4F |
| 8086:a131 | 1462:7977 | Intel      | 100 Series/C230 Series Ch... | 17    | intel_p... | D8050622C0 |
| 8086:a131 | 1462:7994 | Intel      | 100 Series/C230 Series Ch... | 17    | intel_p... | C97E6AF0F2 |
| 8086:a2b1 | 1462:7a71 | Intel      | 200 Series PCH Thermal Su... | 17    |            | 6488569B77 |
| 8086:a131 | 1462:7972 | Intel      | 100 Series/C230 Series Ch... | 16    | intel_p... | FD3B108340 |
| 8086:a2b1 | 17aa:3102 | Intel      | 200 Series PCH Thermal Su... | 16    |            | 65810649CF |
| 8086:a379 | 1019:a4a3 | Intel      | Cannon Lake PCH Thermal C... | 16    | intel_p... | 6D2F43A452 |
| 8086:a379 | 1462:7b22 | Intel      | Cannon Lake PCH Thermal C... | 16    | intel_p... | A850D4D993 |
| 8086:31c2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 15    | intel_l... | D2611BC564 |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 15    | intel_l... | DBF4F53E70 |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 15    | intel_l... | DBF4F53E70 |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 15    | intel_l... | DBF4F53E70 |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 15    | intel_l... | DBF4F53E70 |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 15    | intel_l... | DBF4F53E70 |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 15    | intel_l... | DBF4F53E70 |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 15    | intel_l... | DBF4F53E70 |
| 8086:a2b1 | 1462:7a74 | Intel      | 200 Series PCH Thermal Su... | 15    |            | C90BB6ECA1 |
| 8086:a2b1 | 1462:7c09 | Intel      | 200 Series PCH Thermal Su... | 15    |            | 9F21330313 |
| 8086:a379 | 1462:7b24 | Intel      | Cannon Lake PCH Thermal C... | 15    | intel_p... | A9FC1D1222 |
| 8086:2932 | 1043:8277 | Intel      | 82801I (ICH9 Family) Ther... | 14    |            | D37FED8D0F |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 14    | intel_l... | DBF4F53E70 |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 14    | intel_l... | DBF4F53E70 |
| 8086:9d60 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 14    | intel_l... | B5BD43E606 |
| 8086:9d61 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 14    | intel_l... | B5BD43E606 |
| 8086:a131 | 1028:07c5 | Intel      | 100 Series/C230 Series Ch... | 14    | intel_p... | 29F013D2E2 |
| 8086:a379 | 1462:7b51 | Intel      | Cannon Lake PCH Thermal C... | 14    | intel_p... | E40A4C5A0C |
| 8086:a379 | 8086:7270 | Intel      | Cannon Lake PCH Thermal C... | 14    | intel_p... | 7A2742F439 |
| 8086:06f9 | 103c:8767 | Intel      | Comet Lake PCH Thermal Co... | 13    | intel_p... | 481BC047C1 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:790b | 1458:5001 | AMD        | FCH SMBus Controller         | 1710  | i2c_piix4  | E52E9002D0 |
| 1002:4385 | 1002:4385 | AMD        | SBx00 SMBus Controller       | 1227  | i2c_pii... | 588CEFB67B |
| 8086:1c22 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1137  | i2c_i801   | 278873FF66 |
| 1022:790b | 1043:87c0 | AMD        | FCH SMBus Controller         | 910   | piix4_s... | A525C8911B |
| 8086:8c22 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 905   | i2c_i801   | 735015DCE2 |
| 1002:4385 | 1043:8389 | AMD        | SBx00 SMBus Controller       | 860   | i2c_pii... | 6CA4F46D1B |
| 1022:790b | 1043:8747 | AMD        | FCH SMBus Controller         | 836   | i2c_piix4  | 491D1A96CC |
| 1002:4385 | 1458:4385 | AMD        | SBx00 SMBus Controller       | 816   | i2c_pii... | 9CF8898973 |
| 8086:27da | 1458:5001 | Intel      | NM10/ICH7 Family SMBus Co... | 797   | i2c_i801   | 5AF4FEE0BA |
| 8086:1e22 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 784   | i2c_i801   | 1575E2C682 |
| 8086:a123 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 753   | i2c_i801   | 427C8B8D8F |
| 8086:27da | 1043:8179 | Intel      | NM10/ICH7 Family SMBus Co... | 735   | i2c_i801   | D7FBB47C8B |
| 8086:1c22 | 1458:5001 | Intel      | 6 Series/C200 Series Chip... | 724   | i2c_i801   | 042607D7F1 |
| 1022:790b | 1849:790b | AMD        | FCH SMBus Controller         | 692   | i2c_piix4  | 60FFB9D428 |
| 8086:3a30 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) SM... | 665   | i2c_i801   | 6C7ECC284B |
| 1002:4385 |           | AMD        | SBx00 SMBus Controller       | 615   | i2c_pii... | 5E80D808A1 |
| 8086:8c22 | 1458:5001 | Intel      | 8 Series/C220 Series Chip... | 602   | i2c_i801   | 3934A7E59D |
| 8086:1e22 | 1458:5001 | Intel      | 7 Series/C216 Chipset Fam... | 596   | i2c_i801   | BB6DE8B3E0 |
| 1002:4385 | 1849:4385 | AMD        | SBx00 SMBus Controller       | 548   | i2c_pii... | 85B942A5C3 |
| 1022:790b | 1849:ffff | AMD        | FCH SMBus Controller         | 501   | i2c_piix4  | C537345CE8 |
| 8086:27da | 1849:27da | Intel      | NM10/ICH7 Family SMBus Co... | 475   | i2c_i801   | 16C678627E |
| 8086:a2a3 | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 460   | i2c_i801   | 381023907E |
| 8086:a2a3 | 1458:5001 | Intel      | 200 Series/Z370 Chipset F... | 430   | i2c_i801   | 8C2B6CF453 |
| 10de:03eb | 1849:03eb | Nvidia     | MCP61 SMBus                  | 425   | i2c_nfo... | 0F23350175 |
| 8086:a123 | 1458:5001 | Intel      | 100 Series/C230 Series Ch... | 420   | i2c_i801   | 36BF6DAB37 |
| 1022:780b | 1022:780b | AMD        | FCH SMBus Controller         | 411   | i2c_piix4  | 2BC95C7D30 |
| 1022:780b | 1849:780b | AMD        | FCH SMBus Controller         | 383   | i2c_pii... | 42CD4D28BD |
| 8086:2930 | 1043:8277 | Intel      | 82801I (ICH9 Family) SMBu... | 379   | i2c_i801   | 80ADFF7646 |
| 8086:a323 | 1043:8694 | Intel      | Cannon Lake PCH SMBus Con... | 374   | i2c_i801   | 22A32FC3F2 |
| 8086:8ca2 | 1043:8534 | Intel      | 9 Series Chipset Family S... | 329   | i2c_i801   | 5A5D3A54C3 |
| 8086:a323 | 1458:5001 | Intel      | Cannon Lake PCH SMBus Con... | 306   | i2c_i801   | 1C2A383C4F |
| 1022:790b | 1043:876b | AMD        | FCH SMBus Controller         | 305   | i2c_piix4  | 24974BE67E |
| 8086:3b30 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 303   | i2c_i801   | 4E4391F329 |
| 8086:3a30 | 1458:5001 | Intel      | 82801JI (ICH10 Family) SM... | 302   | i2c_i801   | 40C84C9637 |
| 1022:790b | 1022:790b | AMD        | FCH SMBus Controller         | 290   | i2c_piix4  | 93825976F1 |
| 8086:8c22 | 1849:8c22 | Intel      | 8 Series/C220 Series Chip... | 280   | i2c_i801   | 111E98DDEF |
| 8086:1c22 | 1849:1c22 | Intel      | 6 Series/C200 Series Chip... | 274   | i2c_i801   | 7070F2EAF3 |
| 8086:8ca2 | 1458:5001 | Intel      | 9 Series Chipset Family S... | 259   | i2c_i801   | 5EAD0CA3AD |
| 8086:2930 | 1458:5001 | Intel      | 82801I (ICH9 Family) SMBu... | 220   | i2c_i801   | 01145B2627 |
| 8086:3b30 | 1458:5001 | Intel      | 5 Series/3400 Series Chip... | 215   | i2c_i801   | 02DFFBFEA8 |
| 10de:03eb | 1458:0c11 | Nvidia     | MCP61 SMBus                  | 213   | i2c_nfo... | 701EE8CE26 |
| 8086:1e22 | 1028:0577 | Intel      | 7 Series/C216 Chipset Fam... | 207   | i2c_i801   | E1B966B80D |
| 8086:a123 | 1849:a123 | Intel      | 100 Series/C230 Series Ch... | 205   | i2c_i801   | 6B4C3F811B |
| 8086:1e22 | 1849:1e22 | Intel      | 7 Series/C216 Chipset Fam... | 194   | i2c_i801   | F6F957DDF3 |
| 8086:1c22 | 8086:1c22 | Intel      | 6 Series/C200 Series Chip... | 188   | i2c_i801   | 6978CD209F |
| 8086:8c22 | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 186   | i2c_i801   | 0420EDF711 |
| 1022:790b | 1462:7c37 | AMD        | FCH SMBus Controller         | 178   | i2c_piix4  | 6B0A992D9F |
| 8086:a2a3 | 1849:a2a3 | Intel      | 200 Series/Z370 Chipset F... | 178   | i2c_i801   | 79E6EF3655 |
| 1022:790b | 1462:7c02 | AMD        | FCH SMBus Controller         | 175   | i2c_piix4  | 97620628A8 |
| 10de:03eb | 1043:83a4 | Nvidia     | MCP61 SMBus                  | 158   | i2c_nfo... | 324F6E5FAD |
| 8086:a2a3 | 1043:872f | Intel      | 200 Series/Z370 Chipset F... | 158   | i2c_i801   | F60A34FE5C |
| 8086:3a60 | 1028:0420 | Intel      | 82801JD/DO (ICH10 Family)... | 154   | i2c_i801   | C67A8BB677 |
| 1002:4385 | 1462:7693 | AMD        | SBx00 SMBus Controller       | 151   | i2c_pii... | DEC7AC6A34 |
| 1022:780b | 1462:7721 | AMD        | FCH SMBus Controller         | 143   | i2c_piix4  | 69DA26C946 |
| 8086:1d22 | 1043:84ef | Intel      | C600/X79 series chipset S... | 141   | i2c_i801   | 1BB97BC7DF |
| 8086:8c22 | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 140   | i2c_i801   | E04A41FC30 |
| 8086:1c22 | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 135   | i2c_i801   | D6237E9949 |
| 1022:790b | 1462:7b86 | AMD        | FCH SMBus Controller         | 129   | i2c_piix4  | 7E563A9D44 |
| 1022:780b | 1043:85ca | AMD        | FCH SMBus Controller         | 128   | i2c_piix4  | 82894BE7A8 |
| 10de:03eb | 1043:8234 | Nvidia     | MCP61 SMBus                  | 124   | i2c_nfo... | 91FE7919BE |
| 8086:a323 | 1849:a323 | Intel      | Cannon Lake PCH SMBus Con... | 124   | i2c_i801   | 2FF008A28D |
| 1022:780b | 1043:8527 | AMD        | FCH SMBus Controller         | 121   | i2c_piix4  | 0AC8E061F1 |
| 8086:8ca2 | 1849:8ca2 | Intel      | 9 Series Chipset Family S... | 119   | i2c_i801   | 8DE72FD346 |
| 8086:2930 | 1028:0211 | Intel      | 82801I (ICH9 Family) SMBu... | 117   | i2c_i801   | 7E7D0BC489 |
| 8086:283e | 1043:81ec | Intel      | 82801H (ICH8 Family) SMBu... | 115   | i2c_i801   | 7C56A7A321 |
| 8086:1e22 | 103c:3397 | Intel      | 7 Series/C216 Chipset Fam... | 114   | i2c_i801   | BF9875C5AC |
| 8086:8d22 | 1043:8600 | Intel      | C610/X99 series chipset S... | 114   | i2c_i801   | D3A4772E4E |
| 8086:27da | 8086:27da | Intel      | NM10/ICH7 Family SMBus Co... | 113   | i2c_i801   | CE791F779F |
| 1002:4385 | 1043:82ef | AMD        | SBx00 SMBus Controller       | 111   | i2c_pii... | AA48DEDAF3 |
| 8086:27da | 1462:7592 | Intel      | NM10/ICH7 Family SMBus Co... | 107   | i2c_i801   | 4EC5CDCBD1 |
| 1022:790b | 1462:7a38 | AMD        | FCH SMBus Controller         | 103   | i2c_piix4  | 11F7EC8B16 |
| 8086:8c22 | 1028:0612 | Intel      | 8 Series/C220 Series Chip... | 100   | i2c_i801   | 990123A52D |
| 1022:790b | 1462:7b79 | AMD        | FCH SMBus Controller         | 99    | i2c_piix4  | 93FBAD33CF |
| 10de:0052 | 1043:815a | Nvidia     | CK804 SMBus                  | 99    | i2c_nfo... | F9BFF20C4D |
| 8086:1e22 | 103c:339a | Intel      | 7 Series/C216 Chipset Fam... | 92    | i2c_i801   | 28DA82FF00 |
| 1022:790b | 1462:7a34 | AMD        | FCH SMBus Controller         | 91    | i2c_piix4  | A119D97189 |
| 8086:3a60 | 1028:027f | Intel      | 82801JD/DO (ICH10 Family)... | 91    | i2c_i801   | AADCA45789 |
| 8086:1c22 | 1028:047e | Intel      | 6 Series/C200 Series Chip... | 88    | i2c_i801   | 6AF9EA19B5 |
| 8086:1c22 | 1028:04f5 | Intel      | 6 Series/C200 Series Chip... | 87    | i2c_i801   | 5131593DDF |
| 8086:1c22 | 1028:0585 | Intel      | 6 Series/C200 Series Chip... | 86    | i2c_i801   | E766BCBB62 |
| 8086:27da | 1462:7529 | Intel      | NM10/ICH7 Family SMBus Co... | 86    | i2c_i801   | 1157C2A82C |
| 8086:8c22 | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 86    | i2c_i801   | B9E492678D |
| 8086:1d22 | 8086:1d22 | Intel      | C600/X79 series chipset S... | 85    | i2c_i801   | C720033D3A |
| 1022:790b | 1462:7b89 | AMD        | FCH SMBus Controller         | 83    | piix4_s... | CADB142111 |
| 8086:a3a3 | 1043:8694 | Intel      | Comet Lake PCH-V SMBus Ho... | 82    | i2c_i801   | 7B62AD7C35 |
| 8086:1c22 | 103c:2abf | Intel      | 6 Series/C200 Series Chip... | 81    | i2c_i801   | 380D5AB9F0 |
| 8086:1c22 | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 81    | i2c_i801   | E5BF692305 |
| 8086:3b30 | 1849:3b30 | Intel      | 5 Series/3400 Series Chip... | 81    | i2c_i801   | DF6D3817CB |
| 8086:1c22 | 103c:1495 | Intel      | 6 Series/C200 Series Chip... | 80    | i2c_i801   | 28835849F0 |
| 8086:06a3 | 1043:8694 | Intel      | Comet Lake PCH SMBus Cont... | 79    | i2c_i801   | CAFC4421B2 |
| 8086:1c22 | 103c:1497 | Intel      | 6 Series/C200 Series Chip... | 78    | i2c_i801   | C0FB875CA5 |
| 8086:1e22 | 8086:1e22 | Intel      | 7 Series/C216 Chipset Fam... | 78    | i2c_i801   | C2D53C8118 |
| 10de:03eb | 1462:7309 | Nvidia     | MCP61 SMBus                  | 77    | i2c_nfo... | 0A4D7FB95D |
| 8086:27da | 1565:3103 | Intel      | NM10/ICH7 Family SMBus Co... | 76    | i2c_i801   | 94EFEDE651 |
| 8086:283e | 1028:01da | Intel      | 82801H (ICH8 Family) SMBu... | 76    | i2c_i801   | 07965413DB |
| 8086:1c22 | 1734:11ba | Intel      | 6 Series/C200 Series Chip... | 75    | i2c_i801   | 1229314F25 |
| 8086:8d22 | 8086:7270 | Intel      | C610/X99 series chipset S... | 75    | i2c_i801   | 17B2218DAB |
| 1022:780b | 1043:866a | AMD        | FCH SMBus Controller         | 74    | i2c_pii... | 9ACB82276C |
| 8086:1e22 | 1462:7758 | Intel      | 7 Series/C216 Chipset Fam... | 74    | i2c_i801   | 3BD9604AE7 |
| 1002:4385 | 103c:3047 | AMD        | SBx00 SMBus Controller       | 72    | i2c_piix4  | EEDAB3769C |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0c0c | 8086:2010 | Intel      | Xeon E3-1200 v3/4th Gen C... | 701   | snd_hda... | 5EAD0CA3AD |
| 1002:15de | 1002:15de | AMD        | Raven/Raven2/Fenghuang HD... | 699   | snd_hda... | B2D3620851 |
| 8086:27d8 | 1458:a002 | Intel      | NM10/ICH7 Family High Def... | 680   | snd_hda... | 5AF4FEE0BA |
| 1002:ab38 | 1002:ab38 | AMD        | Navi 10 HDMI Audio           | 677   | snd_hda... | C537345CE8 |
| 8086:8c20 | 1043:8576 | Intel      | 8 Series/C220 Series Chip... | 631   | snd_hda... | 735015DCE2 |
| 1002:4383 | 1458:a002 | AMD        | SBx00 Azalia (Intel HDA)     | 592   | snd_hda... | 9CF8898973 |
| 8086:1c20 | 1458:a002 | Intel      | 6 Series/C200 Series Chip... | 592   | snd_hda... | 042607D7F1 |
| 8086:8c20 | 1458:a002 | Intel      | 8 Series/C220 Series Chip... | 530   | snd_hda... | 3934A7E59D |
| 1002:aaf0 | 1da2:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 497   | snd_hda... | C483A48272 |
| 1002:4383 | 1043:8445 | AMD        | SBx00 Azalia (Intel HDA)     | 437   | snd_hda... | 21C683ED97 |
| 10de:0e0f | 1462:8c93 | Nvidia     | GK208 HDMI/DP Audio Contr... | 417   | snd_hda... | 0233AE7054 |
| 1022:1457 | 1458:a182 | AMD        | Family 17h (Models 00h-0f... | 408   | snd_hda... | E52E9002D0 |
| 1002:aab0 | 174b:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 404   | snd_hda... | 0C14FFD402 |
| 8086:a170 | 1043:86c7 | Intel      | 100 Series/C230 Series Ch... | 391   | snd_hda... | 51862605EF |
| 1002:aaf0 | 1462:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 383   | snd_hda... | 6C7ECC284B |
| 8086:1e20 | 1458:a002 | Intel      | 7 Series/C216 Chipset Fam... | 362   | snd_hda... | BB6DE8B3E0 |
| 8086:0c0c | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 356   | snd_hda... | 352946E177 |
| 13f6:0111 | 13f6:0111 | C-Media... | CMI8738/CMI8768 PCI Audio    | 355   | snd_cmipci | 8FE0FCCC66 |
| 8086:1c20 | 1043:8445 | Intel      | 6 Series/C200 Series Chip... | 355   | snd_hda... | 6CEE757CF0 |
| 1002:4383 | 1043:836c | AMD        | SBx00 Azalia (Intel HDA)     | 339   | snd_hda... | B820B810C9 |
| 1022:1457 | 1043:86c7 | AMD        | Family 17h (Models 00h-0f... | 339   | snd_hda... | 491D1A96CC |
| 8086:a2f0 | 1458:a182 | Intel      | 200 Series PCH HD Audio      | 339   | snd_hda... | 8C2B6CF453 |
| 8086:a170 | 1458:a182 | Intel      | 100 Series/C230 Series Ch... | 333   | snd_hda... | 36BF6DAB37 |
| 1002:aab0 | 1043:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 331   | snd_hda... | 15946036B1 |
| 1002:aaf0 | 1682:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 326   | snd_hda... | 161865EDB0 |
| 10de:03f0 | 1849:0397 | Nvidia     | MCP61 High Definition Audio  | 321   | snd_hda... | 0F23350175 |
| 1002:4383 | 1458:a182 | AMD        | SBx00 Azalia (Intel HDA)     | 312   | snd_hda... | 545DC9A3E0 |
| 8086:1e20 | 1043:8445 | Intel      | 7 Series/C216 Chipset Fam... | 312   | snd_hda... | 0CC8CA1A78 |
| 8086:1c20 | 1043:8415 | Intel      | 6 Series/C200 Series Chip... | 282   | snd_hda... | 87ABF841B5 |
| 1022:15e3 | 1458:a182 | AMD        | Family 17h (Models 10h-1f... | 280   | snd_hda... | B2D3620851 |
| 1022:780d | 1458:a002 | AMD        | FCH Azalia Controller        | 274   | snd_hda... | 2BC95C7D30 |
| 1002:aaf0 | 1043:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 256   | snd_hda... | 307DA27696 |
| 1022:15e3 | 1043:86c7 | AMD        | Family 17h (Models 10h-1f... | 256   | snd_hda... | 24974BE67E |
| 1002:aaf8 | 1002:aaf8 | AMD        | Vega 10 HDMI Audio [Radeo... | 250   | snd_hda... | 91C5853577 |
| 8086:293e | 1043:829f | Intel      | 82801I (ICH9 Family) HD A... | 245   | snd_hda... | 109CB750A6 |
| 1022:1487 | 1043:8797 | AMD        | Starship/Matisse HD Audio... | 243   | snd_hda... | A525C8911B |
| 1022:780d | 1043:8576 | AMD        | FCH Azalia Controller        | 243   | snd_hda... | 33D5096A54 |
| 8086:27d8 | 1849:3662 | Intel      | NM10/ICH7 Family High Def... | 243   | snd_hda... | 17892FBF03 |
| 8086:a2f0 | 1043:86c7 | Intel      | 200 Series PCH HD Audio      | 240   | snd_hda... | DF0C058313 |
| 1002:aa98 | 174b:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 232   | snd_hda... | 7A70FC2989 |
| 1002:15de | 1043:876b | AMD        | Raven/Raven2/Fenghuang HD... | 225   | snd_hda... | 24974BE67E |
| 1002:4383 | 1458:a102 | AMD        | SBx00 Azalia (Intel HDA)     | 223   | snd_hda... | D1CF1B316E |
| 1102:0012 | 1102:0010 | Creativ... | Sound Core3D [Sound Blast... | 221   | snd_hda... | EAF4F27F7A |
| 1022:1487 | 1458:a0c3 | AMD        | Starship/Matisse HD Audio... | 212   | snd_hda... | 6B471BC42D |
| 10de:0bea |           | Nvidia     | GF108 High Definition Aud... | 209   | snd_hda... | 118F61B356 |
| 8086:1e20 | 1028:0577 | Intel      | 7 Series/C216 Chipset Fam... | 206   | snd_hda... | E1B966B80D |
| 10de:03f0 | 1458:a002 | Nvidia     | MCP61 High Definition Audio  | 205   | snd_hda... | 701EE8CE26 |
| 8086:3a3e | 1043:82fe | Intel      | 82801JI (ICH10 Family) HD... | 202   | snd_hda... | A0BD55A486 |
| 1002:aaf0 | 1458:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 193   | snd_hda... | 0F4AE74D8E |
| 10de:0be3 |           | Nvidia     | High Definition Audio Con... | 193   | snd_hda... | 1F00F6D692 |
| 8086:8ca0 | 1458:a182 | Intel      | 9 Series Chipset Family H... | 191   | snd_hda... | 5EAD0CA3AD |
| 8086:a348 | 1458:a182 | Intel      | Cannon Lake PCH cAVS         | 188   | snd_hda... | 1C2A383C4F |
| 1002:aa38 | 174b:aa38 | AMD        | RV710/730 HDMI Audio [Rad... | 187   | snd_hda... | C45A00B3D6 |
| 8086:3a3e | 1458:a002 | Intel      | 82801JI (ICH10 Family) HD... | 186   | snd_hda... | 0233AE7054 |
| 1002:4383 | 1043:8444 | AMD        | SBx00 Azalia (Intel HDA)     | 184   | snd_hda... | 2CE7E668C7 |
| 1002:aab0 | 1458:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 182   | snd_hda... | E4CB18707B |
| 1002:aa68 | 174b:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 178   | snd_hda... | C7B95D7362 |
| 1002:aab0 | 1462:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 176   | snd_hda... | A9908463D8 |
| 8086:27d8 | 1043:8290 | Intel      | NM10/ICH7 Family High Def... | 176   | snd_hda... | 1FF7B16CE4 |
| 8086:293e | 1458:a002 | Intel      | 82801I (ICH9 Family) HD A... | 174   | snd_hda... | 01145B2627 |
| 1002:4383 | 1849:7892 | AMD        | SBx00 Azalia (Intel HDA)     | 172   | snd_hda... | 85B942A5C3 |
| 1002:aae0 | 1da2:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 170   | snd_hda... | 863C87266B |
| 8086:1c20 | 8086:1c20 | Intel      | 6 Series/C200 Series Chip... | 168   | snd_hda... | 6978CD209F |
| 1022:1457 | 1849:6893 | AMD        | Family 17h (Models 00h-0f... | 165   | snd_hda... | 54F331C0EC |
| 1022:780d | 1849:7662 | AMD        | FCH Azalia Controller        | 165   | snd_hda... | 42CD4D28BD |
| 8086:3b56 | 1458:a002 | Intel      | 5 Series/3400 Series Chip... | 165   | snd_hda... | 02DFFBFEA8 |
| 8086:1e20 | 1458:a014 | Intel      | 7 Series/C216 Chipset Fam... | 162   | snd_hda... | 05A84215D8 |
| 1002:aab0 | 1787:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 161   | snd_hda... | F00A0A0903 |
| 1022:1457 | 1043:8723 | AMD        | Family 17h (Models 00h-0f... | 161   | snd_hda... | 867E533368 |
| 8086:8c20 | 1462:d817 | Intel      | 8 Series/C220 Series Chip... | 156   | snd_hda... | 0420EDF711 |
| 1022:1487 | 1043:87c5 | AMD        | Starship/Matisse HD Audio... | 155   | snd_hda... | 161865EDB0 |
| 8086:3a6e | 1028:0420 | Intel      | 82801JD/DO (ICH10 Family)... | 154   | snd_hda... | C67A8BB677 |
| 8086:a348 | 1043:86c7 | Intel      | Cannon Lake PCH cAVS         | 153   | snd_hda... | FD2F79C5FC |
| 1002:aa90 | 174b:aa90 | AMD        | Turks HDMI Audio [Radeon ... | 150   | snd_hda... | 2590EC6A56 |
| 8086:27d8 | 1849:0397 | Intel      | NM10/ICH7 Family High Def... | 150   | snd_hda... | 16C678627E |
| 10de:0fb8 | 1462:8c98 | Nvidia     | GP108 High Definition Aud... | 149   | snd_hda... | 9753F223E2 |
| 1022:780d | 1458:a182 | AMD        | FCH Azalia Controller        | 148   | snd_hda... | 15946036B1 |
| 8086:a2f0 | 1043:8723 | Intel      | 200 Series PCH HD Audio      | 147   | snd_hda... | 381023907E |
| 10de:0fb9 | 1462:8c96 | Nvidia     | GP107GL High Definition A... | 142   | snd_hda... | E1B966B80D |
| 1002:4383 | 1043:84fb | AMD        | SBx00 Azalia (Intel HDA)     | 141   | snd_hda... | D66B719066 |
| 1022:780d | 1462:d721 | AMD        | FCH Azalia Controller        | 140   | snd_hda... | 69DA26C946 |
| 1002:4383 | 1462:d693 | AMD        | SBx00 Azalia (Intel HDA)     | 139   | snd_hda... | DEC7AC6A34 |
| 1002:aae0 | 1043:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 139   | snd_hda... | 3ABF73FB8A |
| 1022:1487 | 1458:a182 | AMD        | Starship/Matisse HD Audio... | 139   | snd_hda... | 4F7E3472C2 |
| 8086:8c20 | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 138   | snd_hda... | E04A41FC30 |
| 10de:0bee |           | Nvidia     | GF116 High Definition Aud... | 137   | snd_hda... | 9DEBDD654C |
| 8086:0c0c | 1849:0c0c | Intel      | Xeon E3-1200 v3/4th Gen C... | 137   | snd_hda... | 111E98DDEF |
| 1002:aa68 | 1043:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 136   | snd_hda... | 860BDE5935 |
| 1002:ab28 | 1002:ab28 | AMD        | Navi 21 HDMI Audio [Radeo... | 136   | snd_hda... | 93B56B7543 |
| 1022:1457 | 1043:8733 | AMD        | Family 17h (Models 00h-0f... | 136   | snd_hda... | 48DB1AFDD3 |
| 1002:aa58 | 174b:aa58 | AMD        | Juniper HDMI Audio [Radeo... | 134   | snd_hda... | 3CD5BC35E5 |
| 1022:1487 | 1458:a0cf | AMD        | Starship/Matisse HD Audio... | 134   | snd_hda... | 14E7810BC1 |
| 8086:1c20 | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 133   | snd_hda... | D6237E9949 |
| 1002:aaf0 | 148c:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 132   | snd_hda... | 6B471BC42D |
| 1002:aab0 | 1682:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 131   | snd_hda... | 648FD9DAC9 |
| 1002:4383 | 1043:8576 | AMD        | SBx00 Azalia (Intel HDA)     | 125   | snd_hda... | 24FE21040D |
| 8086:1c20 | 1043:8444 | Intel      | 6 Series/C200 Series Chip... | 125   | snd_hda... | 278873FF66 |
| 1002:4383 | 1043:8436 | AMD        | SBx00 Azalia (Intel HDA)     | 122   | snd_hda... | BD2E23A97B |
| 1002:9902 | 1849:9902 | AMD        | Trinity HDMI Audio Contro... | 122   | snd_hda... | 7B85C81082 |
| 1002:aab0 | 1028:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 122   | snd_hda... | 6EBA24CF71 |

### Storage (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1283:8211 | 1043:8138 | Integra... | ITE 8211F Single Channel ... | 40    | pata_it... | 9E97498649 |
| 105a:4d68 | 105a:4d68 | Promise... | PDC20268 [Ultra100 TX2]      | 4     | pata_pd... | 6967AF910D |
| 105a:4d69 | 105a:4d68 | Promise... | 20269                        | 4     | pata_pd... | 21833C414E |
| 1106:401a | 1028:02f5 | VIA Tec... | VIA Card Reader Host Cont... | 4     |            | DA767A9476 |
| 105a:3d17 | 105a:3d17 | Promise... | PDC40718 (SATA 300 TX4)      | 3     | sata_pr... | 50A778F706 |
| 105a:3d73 | 105a:3d73 | Promise... | PDC40775 (SATA 300 TX2plus)  | 3     | sata_pr... | 8FFB1720D8 |
| 1077:2432 | 1077:0138 | QLogic     | ISP2432-based 4Gb Fibre C... | 3     | qla2xxx    | FB66D16E30 |
| 1283:8211 | 1283:8211 | Integra... | ITE 8211F Single Channel ... | 3     | pata_it... | BF5B58520E |
| 105a:3375 | 105a:3375 | Promise... | PDC20375 (SATA150 TX2plus)   | 2     | sata_pr... | 2A0863DD05 |
| 1077:2432 | 103c:7040 | QLogic     | ISP2432-based 4Gb Fibre C... | 2     | qla2xxx    | 3A362598FB |
| 1077:2532 | 103c:3263 | QLogic     | ISP2532-based 8Gb Fibre C... | 2     | qla2xxx    | D018E3FE5A |
| 10df:f100 | 1014:038a | Emulex     | LPe12000 Series 8Gb Fibre... | 2     | lpfc       | 0767C99ABB |
| 10df:fe00 | 10df:fe00 | Emulex     | Zephyr-X LightPulse Fibre... | 2     | lpfc       | F930BC123E |
| 1106:401a | 1106:401a | VIA Tec... | VIA Card Reader Host Cont... | 2     |            | FF6AA83006 |
| 1000:0646 | 1000:1020 | Broadco... | FC949ES Fibre Channel Ada... | 1     | mptfc      | 557131B1DD |
| 104c:8033 | 103c:3085 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 1     | tifm_7xx1  | 46E47F957D |
| 104c:803b | 104d:9030 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 6A92AB4681 |
| 104c:803b | 152d:0754 | Texas I... | PCIxx12 Flash Media Contr... | 1     | tifm_7xx1  | 79905DEFFE |
| 105a:1275 | 105a:1275 | Promise... | 20275                        | 1     | pata_pd... | E0E805180D |
| 105a:3d75 | 105a:3d75 | Promise... | PDC20575 (SATAII150 TX2plus) | 1     | sata_pr... | 8693B86435 |
| 105a:4d30 | 105a:4d33 | Promise... | PDC20267 (FastTrak100/Ult... | 1     | pata_pd... | 1B02673A1A |
| 1077:2312 | 1077:0100 | QLogic     | ISP2312-based 2Gb Fibre C... | 1     | qla2xxx    | 17333FB7FD |
| 1077:2432 | 103c:7041 | QLogic     | ISP2432-based 4Gb Fibre C... | 1     | qla2xxx    | 14ACFD829D |
| 1077:2532 | 1077:015d | QLogic     | ISP2532-based 8Gb Fibre C... | 1     | qla2xxx    | 7A2B809CB8 |
| 1095:0680 | 1095:0680 | Silicon... | PCI0680 Ultra ATA-133 Hos... | 1     | pata_si... | E77A0A6719 |
| 1095:3124 | 1095:3124 | Silicon... | SiI 3124 PCI-X Serial ATA... | 1     | sata_sil24 | D2997C25FD |
| 10b9:5289 | 1043:816b | ULi Ele... | ULi 5289 SATA                | 1     | sata_uli   | 1473488491 |
| 10df:0724 | 10df:e86b | Emulex     | OneConnect FCoE Initiator... | 1     | lpfc       | 68F608CA5B |
| 10df:f0e5 | 10df:f0e5 | Emulex     | Zephyr LightPulse Fibre C... | 1     | lpfc       | 0569365EA0 |
| 10df:fe00 | 10df:fe01 | Emulex     | Zephyr-X LightPulse Fibre... | 1     | lpfc       | CAEF8BBDD2 |
| 1103:0004 | 1103:0005 | HighPoi... | HPT366/368/370/370A/372/372N | 1     | pata_hp... | 01068C79DF |
| 1106:401a | 1028:0408 | VIA Tec... | VIA Card Reader Host Cont... | 1     |            | B55E0BA8CB |
| 1217:7130 | 1025:0124 | O2 Micro   | Integrated MS/xD Controller  | 1     |            | 1F2C670EC4 |
| 1217:7130 | 14ff:a003 | O2 Micro   | Integrated MS/xD Controller  | 1     |            | 6647A9CB02 |
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
| 1022:43c8 | 1b21:1062 | AMD        | 400 Series Chipset SATA C... | 2311  | ahci       | C537345CE8 |
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 1614  | ahci       | 93DE1508CB |
| 1022:7901 | 1458:b002 | AMD        | FCH SATA Controller [AHCI... | 1200  | ahci       | E52E9002D0 |
| 8086:8c02 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 874   | ahci       | 735015DCE2 |
| 1022:7901 | 1043:8747 | AMD        | FCH SATA Controller [AHCI... | 830   | ahci       | 491D1A96CC |
| 1002:4390 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 768   | ahci       | 9CF8898973 |
| 8086:a102 | 1043:8694 | Intel      | Q170/Q150/B150/H170/H110/... | 736   | ahci       | 427C8B8D8F |
| 1022:43b7 | 1b21:1062 | AMD        | 300 Series Chipset SATA C... | 703   | ahci       | 3AB561BBE8 |
| 1002:4391 | 1043:84dd | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 702   | ahci       | 588CEFB67B |
| 1002:4391 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 702   | ahci       | 5E80D808A1 |
| 1002:4390 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 700   | ahci       | 6CA4F46D1B |
| 1022:7901 | 1849:7901 | AMD        | FCH SATA Controller [AHCI... | 679   | ahci       | 60FFB9D428 |
| 1022:43eb | 1b21:1062 | AMD        | Starship/Matisse Chipset ... | 677   | ahci       | 82E27C0415 |
| 8086:1c02 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 647   | ahci       | 278873FF66 |
| 1022:43b8 | 1b21:1062 | AMD        | FCH SATA Controller D        | 619   | ahci       | 24974BE67E |
| 1b21:0612 | 1043:84b7 | ASMedia... | ASM1062 Serial ATA Contro... | 608   | ahci       | 1BB97BC7DF |
| 8086:1e02 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 585   | ahci       | 1575E2C682 |
| 8086:8c02 | 1458:b005 | Intel      | 8 Series/C220 Series Chip... | 570   | ahci       | 3934A7E59D |
| 1b21:0612 | 1849:0612 | ASMedia... | ASM1062 Serial ATA Contro... | 567   | ahci       | 86F08832C0 |
| 1b21:0612 | 1b21:1060 | ASMedia... | ASM1062 Serial ATA Contro... | 433   | ahci       | 93DE1508CB |
| 8086:a282 | 1043:8694 | Intel      | 200 Series PCH SATA contr... | 414   | ahci       | 9F69E439BC |
| 8086:a102 | 1458:b005 | Intel      | Q170/Q150/B150/H170/H110/... | 412   | ahci       | 36BF6DAB37 |
| 8086:a282 | 1458:b005 | Intel      | 200 Series PCH SATA contr... | 412   | ahci       | 8C2B6CF453 |
| 1022:7901 | 1043:87c0 | AMD        | FCH SATA Controller [AHCI... | 399   | ahci       | D10E4364A0 |
| 1022:43b5 | 1b21:1062 | AMD        | X370 Series Chipset SATA ... | 382   | ahci       | 3ABF73FB8A |
| 1022:43c8 | 1849:43c8 | AMD        | 400 Series Chipset SATA C... | 365   | ahci       | 60FFB9D428 |
| 1002:4391 | 1849:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 326   | ahci       | 33FEFE9DE1 |
| 1022:7801 | 1849:7801 | AMD        | FCH SATA Controller [AHCI... | 322   | ahci       | 42CD4D28BD |
| 8086:1e02 | 1458:b005 | Intel      | 7 Series/C210 Series Chip... | 320   | ahci       | BB6DE8B3E0 |
| 8086:a352 | 1043:8694 | Intel      | Cannon Lake PCH SATA AHCI... | 320   | ahci       | 22A32FC3F2 |
| 8086:8c82 | 1043:8534 | Intel      | 9 Series Chipset Family S... | 295   | ahci       | 5A5D3A54C3 |
| 1022:7801 | 1458:b002 | AMD        | FCH SATA Controller [AHCI... | 294   | ahci       | 15946036B1 |
| 8086:1c02 | 1458:b005 | Intel      | 6 Series/C200 Series Chip... | 286   | ahci       | 863C87266B |
| 8086:a352 | 1458:b005 | Intel      | Cannon Lake PCH SATA AHCI... | 279   | ahci       | 1C2A383C4F |
| 1022:7901 | 1043:876b | AMD        | FCH SATA Controller [AHCI... | 272   | ahci       | 24974BE67E |
| 1b4b:9172 | 1458:b000 | Marvell... | 88SE9172 SATA 6Gb/s Contr... | 267   | ahci       | 853E99EEE4 |
| 8086:8c02 | 1849:8c02 | Intel      | 8 Series/C220 Series Chip... | 261   | ahci       | 111E98DDEF |
| 197b:2362 | 1043:8460 | JMicron... | JMB362 SATA Controller       | 248   | ahci       | 588CEFB67B |
| 8086:8c82 | 1458:b005 | Intel      | 9 Series Chipset Family S... | 245   | ahci       | 5EAD0CA3AD |
| 1b21:0612 | 1043:858d | ASMedia... | ASM1062 Serial ATA Contro... | 239   | ahci       | 0981774043 |
| 1002:4390 | 1849:4390 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 235   | ahci       | 85B942A5C3 |
| 8086:3a22 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) SA... | 228   | ahci       | 6C7ECC284B |
| 8086:a102 | 1849:a102 | Intel      | Q170/Q150/B150/H170/H110/... | 201   | ahci       | 6B4C3F811B |
| 8086:1e02 | 1028:0577 | Intel      | 7 Series/C210 Series Chip... | 197   | ahci       | E1B966B80D |
| 1022:7901 | 1849:ffff | AMD        | FCH SATA Controller [AHCI... | 194   | ahci       | 70D528A8FC |
| 8086:1e02 | 1849:1e02 | Intel      | 7 Series/C210 Series Chip... | 186   | ahci       | F6F957DDF3 |
| 8086:8c02 | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 177   | ahci       | 0420EDF711 |
| 1022:7800 | 1458:b002 | AMD        | FCH SATA Controller [IDE ... | 172   | ahci       | 2BC95C7D30 |
| 8086:a282 | 1849:a282 | Intel      | 200 Series PCH SATA contr... | 168   | ahci       | 79E6EF3655 |
| 1022:43b6 | 1b21:1062 | AMD        | X399 Series Chipset SATA ... | 165   | ahci       | 70D528A8FC |
| 8086:1c02 | 1849:1c02 | Intel      | 6 Series/C200 Series Chip... | 164   | ahci       | 7070F2EAF3 |
| 1022:7901 | 1462:7c02 | AMD        | FCH SATA Controller [AHCI... | 159   | ahci       | 97620628A8 |
| 1002:4391 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 158   | ahci       | CA800107FC |
| 1002:4390 | 1002:4390 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 156   | ahci       | C7B95D7362 |
| 1b4b:9215 | 1b4b:9215 | Marvell... | 88SE9215 PCIe 2.0 x1 4-po... | 151   | ahci       | 93DE1508CB |
| 1022:7801 | 1462:7721 | AMD        | FCH SATA Controller [AHCI... | 140   | ahci       | 69DA26C946 |
| 8086:1d02 | 1043:84ef | Intel      | C600/X79 series chipset 6... | 132   | ahci       | 1BB97BC7DF |
| 8086:a282 | 1043:872f | Intel      | 200 Series PCH SATA contr... | 132   | ahci       | F60A34FE5C |
| 8086:1c02 | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 129   | ahci       | D6237E9949 |
| 1022:7801 | 1043:85ca | AMD        | FCH SATA Controller [AHCI... | 126   | ahci       | 82894BE7A8 |
| 1022:43b8 | 1849:43c8 | AMD        | FCH SATA Controller D        | 121   | ahci       | E5F58B5D76 |
| 1b4b:9130 | 1043:8438 | Marvell... | 88SE9128 PCIe SATA 6 Gb/s... | 121   | ahci       | 0C14FFD402 |
| 8086:a352 | 1849:a352 | Intel      | Cannon Lake PCH SATA AHCI... | 120   | ahci       | 2FF008A28D |
| 1002:4391 | 1002:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 118   | ahci       | FBCB5D8594 |
| 1022:7801 | 1043:8527 | AMD        | FCH SATA Controller [AHCI... | 117   | ahci       | 0AC8E061F1 |
| 1022:7901 | 1462:7b86 | AMD        | FCH SATA Controller [AHCI... | 115   | ahci       | 7E563A9D44 |
| 1b4b:9172 | 1043:8477 | Marvell... | 88SE9172 SATA 6Gb/s Contr... | 113   | ahci       | F11C125224 |
| 8086:8c82 | 1849:8c82 | Intel      | 9 Series Chipset Family S... | 113   | ahci       | 8DE72FD346 |
| 8086:3a22 | 1458:b005 | Intel      | 82801JI (ICH10 Family) SA... | 110   | ahci       | 45661425FF |
| 8086:1c02 | 8086:1c02 | Intel      | 6 Series/C200 Series Chip... | 107   | ahci       | 6978CD209F |
| 8086:3b22 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 105   | ahci       | 4E4391F329 |
| 1022:7901 | 1462:7c37 | AMD        | FCH SATA Controller [AHCI... | 104   | ahci       | DD6513E107 |
| 1002:4390 | 1043:82ef | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 100   | ahci       | AA48DEDAF3 |
| 8086:1e02 | 103c:3397 | Intel      | 7 Series/C210 Series Chip... | 100   | ahci       | BF9875C5AC |
| 8086:8c02 | 1028:0612 | Intel      | 8 Series/C220 Series Chip... | 95    | ahci       | 990123A52D |
| 1002:4391 | 1462:7693 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 94    | ahci       | DEC7AC6A34 |
| 1022:7901 | 1462:7a38 | AMD        | FCH SATA Controller [AHCI... | 94    | ahci       | B914028CA9 |
| 1022:7901 | 1462:7b79 | AMD        | FCH SATA Controller [AHCI... | 94    | ahci       | 93FBAD33CF |
| 8086:8d02 | 1043:8600 | Intel      | C610/X99 series chipset 6... | 94    | ahci       | D3A4772E4E |
| 8086:2922 | 1028:0211 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 93    | ahci       | 7E7D0BC489 |
| 8086:3b22 | 1458:b005 | Intel      | 5 Series/3400 Series Chip... | 93    | ahci       | 02DFFBFEA8 |
| 1022:7901 | 1462:7a34 | AMD        | FCH SATA Controller [AHCI... | 91    | ahci       | A119D97189 |
| 8086:1e02 | 103c:339a | Intel      | 7 Series/C210 Series Chip... | 86    | ahci       | 28DA82FF00 |
| 8086:1c02 | 1028:0585 | Intel      | 6 Series/C200 Series Chip... | 85    | ahci       | E766BCBB62 |
| 8086:1d02 | 8086:1d02 | Intel      | C600/X79 series chipset 6... | 82    | ahci       | C720033D3A |
| 8086:8c02 | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 80    | ahci       | B9E492678D |
| 8086:3a02 | 1028:027f | Intel      | 82801JD/DO (ICH10 Family)... | 76    | ahci       | AADCA45789 |
| 8086:a382 | 1043:8694 | Intel      | 400 Series Chipset Family... | 75    | ahci       | 7B62AD7C35 |
| 8086:1e02 | 1462:7758 | Intel      | 7 Series/C210 Series Chip... | 73    | ahci       | 3BD9604AE7 |
| 1002:4390 | 1043:8443 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 72    | ahci       | 03B2C2E1AF |
| 1022:7801 | 1043:866a | AMD        | FCH SATA Controller [AHCI... | 72    | ahci       | 9ACB82276C |
| 1022:7901 | 1462:7b89 | AMD        | FCH SATA Controller [AHCI... | 72    | ahci       | 46651B942B |
| 8086:8d62 | 1043:8600 | Intel      | C610/X99 series chipset s... | 72    | ahci       | D3A4772E4E |
| 8086:06d2 | 1043:8694 | Intel      | Comet Lake SATA AHCI Cont... | 71    | ahci       | CAFC4421B2 |
| 8086:1c02 | 103c:2abf | Intel      | 6 Series/C200 Series Chip... | 71    | ahci       | 380D5AB9F0 |
| 8086:a102 | 1462:7996 | Intel      | Q170/Q150/B150/H170/H110/... | 71    | ahci       | EC7609239E |
| 1022:43b7 | 1849:43c8 | AMD        | 300 Series Chipset SATA C... | 70    | ahci       | C7798BA8D3 |
| 8086:31e3 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 70    | ahci       | D2611BC564 |
| 8086:1c02 | 1734:11ba | Intel      | 6 Series/C200 Series Chip... | 69    | ahci       | 1229314F25 |
| 8086:1c02 | 103c:1495 | Intel      | 6 Series/C200 Series Chip... | 66    | ahci       | 28835849F0 |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:439c | 1458:5002 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1191  | pata_at... | 9CF8898973 |
| 8086:27df | 1043:8179 | Intel      | 82801G (ICH7 Family) IDE ... | 1054  | ata_pii... | 4E4E73BA37 |
| 1002:439c | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 860   | pata_at... | 6CA4F46D1B |
| 8086:27c0 | 1458:b002 | Intel      | NM10/ICH7 Family SATA Con... | 791   | ata_pii... | 5AF4FEE0BA |
| 8086:27c0 | 1043:8179 | Intel      | NM10/ICH7 Family SATA Con... | 762   | ata_pii... | 4E4E73BA37 |
| 197b:2363 | 1458:b000 | JMicron... | JMB363 SATA/IDE Controller   | 525   | ahci       | 45661425FF |
| 1002:439c | 1849:439c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 521   | pata_at... | 85B942A5C3 |
| 8086:1c00 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 494   | ata_pii... | 6CEE757CF0 |
| 8086:1c08 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 494   | ata_pii... | 6CEE757CF0 |
| 8086:27c0 | 1849:27c0 | Intel      | NM10/ICH7 Family SATA Con... | 461   | ata_pii... | 16C678627E |
| 8086:27df | 1849:27df | Intel      | 82801G (ICH7 Family) IDE ... | 447   | ata_pii... | 16C678627E |
| 8086:3a20 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) 4 ... | 446   | ata_pii... | A0BD55A486 |
| 8086:3a26 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) 2 ... | 446   | ata_pii... | A0BD55A486 |
| 8086:1c08 | 1458:b002 | Intel      | 6 Series/C200 Series Chip... | 434   | ata_pii... | 042607D7F1 |
| 10de:03f6 | 1849:03f6 | Nvidia     | MCP61 SATA Controller        | 424   | sata_nv... | 0F23350175 |
| 10de:03ec | 1849:03ec | Nvidia     | MCP61 IDE                    | 392   | pata_am... | 0F23350175 |
| 197b:2363 | 1043:824f | JMicron... | JMB363 SATA/IDE Controller   | 334   | ahci       | 4E4391F329 |
| 8086:2926 | 1043:8277 | Intel      | 82801I (ICH9 Family) 2 po... | 326   | ata_pii... | 109CB750A6 |
| 197b:2368 | 1458:b000 | JMicron... | JMB368 IDE controller        | 311   | pata_jm... | 0233AE7054 |
| 8086:27c0 | 1043:2601 | Intel      | NM10/ICH7 Family SATA Con... | 297   | ata_pii... | D7FBB47C8B |
| 8086:1e00 | 1458:b005 | Intel      | 7 Series/C210 Series Chip... | 252   | pata_acpi  | A223391BC0 |
| 8086:1e08 | 1458:b002 | Intel      | 7 Series/C210 Series Chip... | 252   | pata_acpi  | A223391BC0 |
| 1022:780c | 1849:780c | AMD        | FCH IDE Controller           | 246   | pata_at... | 42CD4D28BD |
| 8086:1c00 | 1458:b005 | Intel      | 6 Series/C200 Series Chip... | 237   | ata_pii... | 042607D7F1 |
| 10de:03f6 | 1458:b002 | Nvidia     | MCP61 SATA Controller        | 213   | sata_nv... | 701EE8CE26 |
| 8086:2921 | 1043:8277 | Intel      | 82801IB (ICH9) 2 port SAT... | 213   | ata_pii... | 109CB750A6 |
| 1106:0415 | 1043:838f | VIA Tec... | VT6415 PATA IDE Host Cont... | 207   | pata_vi... | 30AA6C2F49 |
| 8086:1c00 | 1458:b002 | Intel      | 6 Series/C200 Series Chip... | 201   | ata_pii... | AB9C12AF26 |
| 197b:2363 | 1043:81e4 | JMicron... | JMB363 SATA/IDE Controller   | 199   | ahci       | 5DCFD80741 |
| 8086:3a20 | 1458:b002 | Intel      | 82801JI (ICH10 Family) 4 ... | 195   | ata_pii... | 40C84C9637 |
| 8086:3a26 | 1458:b002 | Intel      | 82801JI (ICH10 Family) 2 ... | 195   | ata_pii... | 40C84C9637 |
| 8086:3b20 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 194   | ata_pii... | C29EE7CA9F |
| 8086:3b26 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 194   | ata_pii... | C29EE7CA9F |
| 1022:780c | 1458:5002 | AMD        | FCH IDE Controller           | 187   | pata_at... | 2BC95C7D30 |
| 197b:2368 | 1043:827e | JMicron... | JMB368 IDE controller        | 183   | pata_jm... | 704043DEAB |
| 8086:1e00 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 175   | ata_pii... | 2130C28D33 |
| 8086:1e08 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 175   | ata_pii... | 2130C28D33 |
| 1002:439c | 1002:439c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 170   | pata_at... | C7B95D7362 |
| 8086:27df | 1458:b001 | Intel      | 82801G (ICH7 Family) IDE ... | 168   | ata_pii... | 7F06FF456A |
| 8086:2926 | 1458:b002 | Intel      | 82801I (ICH9 Family) 2 po... | 168   | ata_pii... | 0582E2316B |
| 8086:27c0 | 8086:27c0 | Intel      | NM10/ICH7 Family SATA Con... | 166   | pata_acpi  | 7CA61CA6E1 |
| 10de:03f6 | 1043:83a4 | Nvidia     | MCP61 SATA Controller        | 158   | sata_nv... | 324F6E5FAD |
| 10de:03ec | 1458:5002 | Nvidia     | MCP61 IDE                    | 155   | pata_am... | 7076F55128 |
| 10de:03ec | 1043:83a4 | Nvidia     | MCP61 IDE                    | 151   | pata_am... | 324F6E5FAD |
| 8086:27df | 8086:27df | Intel      | 82801G (ICH7 Family) IDE ... | 146   | pata_acpi  | 7CA61CA6E1 |
| 11ab:6101 | 1043:82e0 | Marvell... | 88SE6101/6102 single-port... | 134   | pata_ma... | 77B7D82F05 |
| 11ab:6101 | 11ab:6101 | Marvell... | 88SE6101/6102 single-port... | 125   | pata_ma... | A5121E1871 |
| 10de:03f6 | 1043:8234 | Nvidia     | MCP61 SATA Controller        | 124   | sata_nv... | 91FE7919BE |
| 10de:03ec | 1043:8234 | Nvidia     | MCP61 IDE                    | 121   | pata_am... | 91FE7919BE |
| 8086:3b20 | 1458:b002 | Intel      | 5 Series/3400 Series Chip... | 119   | ata_pii... | 4F5274C16A |
| 8086:3b26 | 1458:b002 | Intel      | 5 Series/3400 Series Chip... | 119   | ata_pii... | 4F5274C16A |
| 8086:2920 | 1043:8277 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 113   | ata_pii... | 77B7D82F05 |
| 8086:1c00 | 1849:1c00 | Intel      | 6 Series/C200 Series Chip... | 112   | ata_pii... | A70EB2D3F8 |
| 1002:439c | 1043:82ef | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 111   | pata_at... | AA48DEDAF3 |
| 8086:1c08 | 1849:1c08 | Intel      | 6 Series/C200 Series Chip... | 111   | ata_pii... | A70EB2D3F8 |
| 8086:27c0 | 1462:7592 | Intel      | NM10/ICH7 Family SATA Con... | 107   | pata_acpi  | 4EC5CDCBD1 |
| 8086:29b6 | 1028:0211 | Intel      | 82Q35 Express PT IDER Con... | 104   | pata_acpi  | 7E7D0BC489 |
| 10de:0053 | 1043:815a | Nvidia     | CK804 IDE                    | 99    | pata_am... | F9BFF20C4D |
| 10de:0055 | 1043:815a | Nvidia     | CK804 Serial ATA Controller  | 99    | sata_nv... | F9BFF20C4D |
| 10de:0054 | 1043:815a | Nvidia     | CK804 Serial ATA Controller  | 98    | sata_nv... | F9BFF20C4D |
| 8086:27df | 1462:7592 | Intel      | 82801G (ICH7 Family) IDE ... | 97    | pata_acpi  | 4EC5CDCBD1 |
| 8086:2e16 | 1028:0420 | Intel      | 4 Series Chipset PT IDER ... | 96    | pata_acpi  | 476F78A010 |
| 11ab:6121 | 1043:82a2 | Marvell... | 88SE6111/6121 SATA II / P... | 95    | pata_ma... | DF44856137 |
| 8086:2825 | 1043:81ec | Intel      | 82801HR/HO/HH (ICH8R/DO/D... | 92    | ata_pii... | A402BB261D |
| 8086:2820 | 1043:81ec | Intel      | 82801H (ICH8 Family) 4 po... | 91    | ata_pii... | A402BB261D |
| 8086:1c00 | 1028:04f5 | Intel      | 6 Series/C200 Series Chip... | 87    | pata_acpi  | 5131593DDF |
| 8086:1c08 | 1028:04f5 | Intel      | 6 Series/C200 Series Chip... | 87    | pata_acpi  | 5131593DDF |
| 8086:2e16 | 1028:027f | Intel      | 4 Series Chipset PT IDER ... | 87    | pata_acpi  | F27A29129F |
| 8086:27c0 | 1462:7529 | Intel      | NM10/ICH7 Family SATA Con... | 86    | ata_pii... | 1157C2A82C |
| 11ab:6121 | 1043:82e0 | Marvell... | 88SE6111/6121 SATA II / P... | 85    | pata_ma... | 70EE05A53E |
| 8086:27df | 1462:7529 | Intel      | 82801G (ICH7 Family) IDE ... | 84    | ata_pii... | 1157C2A82C |
| 8086:2920 | 1458:b002 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 84    | pata_acpi  | 555747351D |
| 8086:2921 | 1458:b002 | Intel      | 82801IB (ICH9) 2 port SAT... | 84    | ata_pii... | 0582E2316B |
| 197b:2363 | 197b:2363 | JMicron... | JMB363 SATA/IDE Controller   | 82    | ahci       | 3AEEEBEB96 |
| 197b:2361 | 1043:824f | JMicron... | JMB361 AHCI/IDE              | 79    | ahci       | C7B95D7362 |
| 10de:03f6 | 1462:7309 | Nvidia     | MCP61 SATA Controller        | 78    | sata_nv... | 0A4D7FB95D |
| 1002:439c | 1043:8443 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 77    | pata_at... | 03B2C2E1AF |
| 8086:2820 | 1028:01da | Intel      | 82801H (ICH8 Family) 4 po... | 76    | pata_acpi  | 07965413DB |
| 8086:2825 | 1028:01da | Intel      | 82801HR/HO/HH (ICH8R/DO/D... | 76    | pata_acpi  | 07965413DB |
| 8086:27c0 | 1565:5202 | Intel      | NM10/ICH7 Family SATA Con... | 75    | ata_piix   | 94EFEDE651 |
| 8086:27df | 1565:3103 | Intel      | 82801G (ICH7 Family) IDE ... | 75    | ata_piix   | 94EFEDE651 |
| 1002:439c | 1462:7641 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 72    | pata_at... | 1161AF8368 |
| 11ab:6121 | 1043:8212 | Marvell... | 88SE6111/6121 SATA II / P... | 71    | pata_ma... | 6C7ECC284B |
| 197b:2368 | 1043:824f | JMicron... | JMB368 IDE controller        | 70    | pata_jm... | A0BD55A486 |
| 1b4b:917a | 1458:b000 | Marvell... | 88SE9172 SATA III 6Gb/s R... | 69    | pata_ac... | E53E495032 |
| 1b4b:91a4 | 1b4b:91a4 | Marvell... | 88SE912x IDE Controller      | 68    | pata_ma... | 2A83508F22 |
| 8086:27c0 | 1028:01ad | Intel      | NM10/ICH7 Family SATA Con... | 67    | pata_acpi  | 79FDFFE8EC |
| 1106:0415 | 1849:0415 | VIA Tec... | VT6415 PATA IDE Host Cont... | 66    | pata_vi... | 98B11D2398 |
| 1b4b:91a3 | 1458:b000 | Marvell... | 88SE91A3 SATA-600 Controller | 66    | ahci, p... | 2DBDB6BAE9 |
| 8086:24db | 1043:80a6 | Intel      | 82801EB/ER (ICH5/ICH5R) I... | 66    | ata_pii... | 4284F4A0F3 |
| 8086:27df | 1028:01ad | Intel      | 82801G (ICH7 Family) IDE ... | 65    | pata_acpi  | 79FDFFE8EC |
| 10de:03f6 | 1565:5405 | Nvidia     | MCP61 SATA Controller        | 64    | sata_nv... | E16A5113BA |
| 8086:2e16 | 1734:114c | Intel      | 4 Series Chipset PT IDER ... | 64    | pata_acpi  | 6B08158329 |
| 10de:03ec | 1565:3407 | Nvidia     | MCP61 IDE                    | 63    | pata_am... | E16A5113BA |
| 8086:2920 | 1028:020d | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 63    | pata_acpi  | E77852D5C2 |
| 8086:2926 | 1028:020d | Intel      | 82801I (ICH9 Family) 2 po... | 63    | pata_acpi  | E77852D5C2 |
| 10de:0759 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] IDE    | 61    | pata_am... | 9005621271 |
| 11ab:6121 | 11ab:6121 | Marvell... | 88SE6111/6121 SATA II / P... | 60    | pata_ma... | BBFA7FB897 |
| 10de:03ec | 10de:cb84 | Nvidia     | MCP61 IDE                    | 59    | pata_am... | 72F1E0A452 |
| 8086:1c00 | 1462:7788 | Intel      | 6 Series/C200 Series Chip... | 59    | ata_pii... | 4C9DF75EEE |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 2054  | nvme       | 27E29303BC |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 607   | nvme       | EACC1E3F66 |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 548   | nvme       | 2FC377709D |
| 126f:2263 | 126f:2263 | Silicon... | SM2263EN/SM2263XT SSD Con... | 314   | nvme       | 70D528A8FC |
| 1987:5016 | 1987:5016 | Phison ... | E16 PCIe4 NVMe Controller    | 310   | nvme       | A525C8911B |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 294   | nvme       | 5B55E39C35 |
| 2646:2263 | 2646:2263 | Kingsto... | A2000 NVMe SSD               | 273   | nvme       | B2D3620851 |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 256   | nvme       | 66B9CEA0F2 |
| 15b7:5009 | 15b7:5009 | Sandisk    | WD Blue SN550 NVMe SSD       | 242   | nvme       | 70A2909C2D |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/SN750 / PC ... | 224   | nvme       | F1CA31B777 |
| c0a9:2263 | c0a9:2263 | Micron/... | P1 NVMe PCIe SSD             | 200   | nvme       | 381023907E |
| 144d:a80a | 144d:a801 | Samsung... | NVMe SSD Controller PM9A1... | 193   | nvme       | 381023907E |
| 15b7:5006 | 15b7:5006 | Sandisk    | WD Black SN750 / PC SN730... | 187   | nvme       | AD0E1A0525 |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 130   | nvme       | C198141A8E |
| 126f:2262 | 126f:2262 | Silicon... | SM2262/SM2262EN SSD Contr... | 126   | nvme       | 3ABF73FB8A |
| 10ec:5762 | 10ec:5762 | Realtek... | RTS5763DL NVMe SSD Contro... | 99    | nvme       | 6B471BC42D |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 92    | nvme       | F20F2BFC32 |
| 144d:a809 | 144d:a801 | Samsung... | NVMe SSD Controller 980      | 87    | nvme       | 1E61CC1252 |
| c0a9:540a | c0a9:540a | Micron/... | P2 NVMe PCIe SSD             | 86    | nvme       | AE3E01FEF8 |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 81    | nvme       | 36B667DA98 |
| 1987:5013 | 1987:5013 | Phison ... | PS5013 E13 NVMe Controller   | 73    | nvme       | 164B215164 |
| 15b7:5003 | 15b7:5003 | Sandisk    | WD Blue SN500 / PC SN520 ... | 70    | nvme       | 6B8CF94EA2 |
| 2646:5008 | 2646:5008 | Kingsto... | U-SNS8154P3 NVMe SSD         | 68    | nvme       | 201BC8D044 |
| 10ec:5763 | 10ec:5763 | Realtek... | Realtek Non-Volatile memo... | 60    | nvme       | DF8AB9EFFB |
| 1987:5007 | 1987:5007 | Phison ... | E7 NVMe Controller           | 58    | nvme       | 0F4AE74D8E |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | BC501 NVMe Solid State Drive | 51    | nvme       | 307DA27696 |
| 1987:5008 | 1987:5008 | Phison ... | NVMe Storage Controller      | 50    | nvme       | B67EC8AF25 |
| 15b7:5011 | 15b7:5011 | Sandisk    | WD Black SN850               | 49    | nvme       | C7A0FE2F88 |
| c0a9:5403 | c0a9:2100 | Micron/... | NVMe Controller              | 47    | nvme       | 9343A7AAC0 |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 37    | nvme       | 667289D1B9 |
| 15b7:5001 | 1b4b:1093 | Sandisk    | WD Black NVMe SSD            | 36    | nvme       | 12DB76B549 |
| 1344:5405 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 33    | nvme       | 36B667DA98 |
| 1bb1:5016 | 1bb1:5016 | Seagate... | FireCuda 520 SSD             | 33    | nvme       | FD95402AA1 |
| 1179:0113 | 1179:0001 | Toshiba... | BG3 NVMe SSD Controller      | 29    | nvme       | A11D4B7C50 |
| 1179:011a | 1179:0001 | Toshiba... | XG6 NVMe SSD Controller      | 27    | nvme       | 8B056A8A9F |
| 14a4:23f1 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 27    | nvme       | AD69186227 |
| 14a4:22f1 | 1b4b:1093 | Lite-On... | M8Pe Series NVMe SSD         | 23    | nvme       | F68A448D75 |
| 1bb1:5012 | 1bb1:5012 | Seagate... | FireCuda 510 SSD             | 23    | nvme       | 7BEEABB20E |
| 8086:faf0 | 8086:390e | Intel      | Non-Volatile memory contr... | 22    | nvme       | 91501CC801 |
| 1179:0115 | 1179:0001 | Toshiba... | XG4 NVMe SSD Controller      | 19    | nvme       | AEA7D9561E |
| 1b85:6018 | 1b85:6018 | OCZ Tec... | RD400/400A SSD               | 19    | nvme       | CC51204B2C |
| c0a9:5412 | c0a9:0100 | Micron/... | Non-Volatile memory contr... | 19    | nvme       | 0184E22E18 |
| 1e0f:0001 | 1e0f:0001 | KIOXIA     | Non-Volatile memory contr... | 18    | nvme       | AB946802EE |
| 2646:2262 | 2646:2262 | Kingsto... | KC2000 NVMe SSD              | 18    | nvme       | 7FFCE9BBC2 |
| 8086:2522 | 8086:3806 | Intel      | NVMe Optane Memory Series    | 17    | nvme       | 8FEE3106F7 |
| 1c5c:1339 | 1c5c:0000 | SK Hynix   | BC511                        | 16    | nvme       | 3729813684 |
| 10ec:5760 | 5760:10ec | Realtek... | Realtek Non-Volatile memo... | 13    | nvme       | B0E10A4766 |
| 126f:2260 | 126f:2260 | Silicon... | Non-Volatile memory contr... | 13    | nvme       | 5130E7EC94 |
| 8086:0953 | 8086:370d | Intel      | PCIe Data Center SSD         | 13    | nvme       | 0569365EA0 |
| 1987:5018 | 1987:5018 | Phison ... | E18 PCIe4 NVMe Controller    | 12    | nvme       | 89C1A7F472 |
| 1c5c:174a | 1c5c:174a | SK Hynix   | Gold P31 SSD                 | 12    | nvme       | D8A7A695AE |
| 8086:2700 | 8086:3900 | Intel      | Optane SSD 900P Series       | 11    | nvme       | 67338CD31A |
| 1344:5410 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 10    | nvme       | 7BA975C504 |
| 1c5c:1527 | 1c5c:1527 | SK Hynix   | PC401 NVMe Solid State Dr... | 10    | nvme       | 694DE952D2 |
| 1c5c:1627 | 1c5c:1627 | SK Hynix   | Non-Volatile memory contr... | 10    | nvme       | DC55F173FE |
| 1d97:2263 | 1d97:2263 | Shenzhe... | SM2263EN/SM2263XT-based O... | 10    | nvme       | F7A082BF52 |
| 8086:2522 | 8086:3810 | Intel      | NVMe Optane Memory Series    | 10    | nvme       | 9CCE6740BE |
| c0a9:5403 | c0a9:1100 | Micron/... | NVMe Controller              | 10    | nvme       | 74709057B7 |
| 1c5c:1639 | 1c5c:1639 | SK Hynix   | Non-Volatile memory contr... | 9     | nvme       | 4054B4EC35 |
| 8086:2700 | 8086:3901 | Intel      | Optane SSD 900P Series       | 9     | nvme       | 0ADC8FC04D |
| 10ec:5765 | 10ec:5765 | Realtek... | Realtek Non-Volatile memo... | 8     | nvme       | 93B56B7543 |
| 1cc1:5350 | 1987:5016 | ADATA T... | Non-Volatile memory contr... | 8     | nvme       | C0104AA33D |
| 1cc1:8201 | 1cc1:1cc1 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 8     | nvme       | FE32C3D470 |
| 2646:500f | 2646:500f | Kingsto... | Technology Company Non-Vo... | 7     | nvme       | 174875A3D4 |
| 1d97:1160 | 1d97:1160 | Shenzhe... | Non-Volatile memory contr... | 6     | nvme       | 9957EF3D80 |
| 1e0f:0009 | 1e0f:0001 | KIOXIA     | NVMe SSD                     | 6     | nvme       | 0548F9650B |
| 2646:500e | 2646:500e | Kingsto... | SNVS2000G [NV1 NVMe PCIe ... | 6     | nvme       | 69F17B7AF8 |
| 14a4:21f1 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 5     | nvme       | 2D6DF73C81 |
| 14a4:9100 | 126f:2263 | Lite-On... | NVMe Controller              | 5     | nvme       | D32CA82327 |
| 15b7:5005 | 15b7:5005 | Sandisk    | PC SN520 NVMe SSD            | 4     | nvme       | B3C4471F54 |
| 1c5c:1283 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 4     | nvme       | 0C3A459A0E |
| 1cc1:5350 | 1cc1:5350 | ADATA T... | A Non-Volatile memory con... | 4     | nvme       | C458B6D1CA |
| 1cc4:5008 | 1cc4:5008 | Union M... | Non-Volatile memory contr... | 4     | nvme       | 5B1BF150BB |
| 1e0f:0008 | 1e0f:0001 | KIOXIA     | Non-Volatile memory contr... | 4     | nvme       | A6C720D609 |
| 8086:0a54 | 8086:4802 | Intel      | NVMe Datacenter SSD [3DNA... | 4     | nvme       | 1D97B5C83D |
| 8086:2522 | 8086:3802 | Intel      | NVMe Optane Memory Series    | 4     | nvme       | 3DE6337339 |
| 1179:010f | 1179:0001 | Toshiba... | NVMe Controller              | 3     | nvme       | 167E800E3A |
| 14a4:2100 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 3     | nvme       | B89F59AD24 |
| 14a4:2200 | 1b4b:1093 | Lite-On... | Lite-On Non-Volatile memo... | 3     | nvme       | 780814E8B8 |
| 14a4:2300 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 3     | nvme       | 4FE62C374E |
| 15b7:5004 | 15b7:5004 | Sandisk    | PC SN520 NVMe SSD            | 3     | nvme       | 7781CAF2E7 |
| 1b4b:1092 | 1d97:1092 | Marvell... | Marvell Non-Volatile memo... | 3     | nvme       | AD5FB0116A |
| 1b4b:2241 | 1b96:4000 | Marvell... | 88NR2241 Non-Volatile mem... | 3     | nvme       | 1E9E468158 |
| 1c5c:1284 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 3     | nvme       | 212AE07786 |
| 1dbe:5236 | 1dbe:5236 |            | Non-Volatile memory contr... | 3     | nvme       | 294D1F6A89 |
| 1e95:35f1 | 1b4b:1092 | Solid S... | Non-Volatile memory contr... | 3     | nvme       | C7B8FCC312 |
| 8086:0975 | 8086:8410 | Intel      | Non-Volatile memory contr... | 3     | nvme       | 1C6A743206 |
| 8086:0975 | 8086:8510 | Intel      | Non-Volatile memory contr... | 3     | nvme       | 1C6A743206 |
| 8086:f1aa | 8086:390f | Intel      | Non-Volatile memory contr... | 3     | nvme       | BCB48851FA |
| 1022:b000 | 15b7:5011 | AMD        | RAID Bottom Device           | 2     | nvme       | A92A7A7F7F |
| 1022:b000 | 1bb1:5016 | AMD        | RAID Bottom Device           | 2     | nvme       | A92A7A7F7F |
| 106b:2005 | 106b:1800 | Apple      | ANS2 NVMe Controller         | 2     | nvme       | 610B9319E9 |
| 15b7:5008 | 15b7:5008 | Sandisk    | Non-Volatile memory contr... | 2     | nvme       | A7D8D3CF71 |
| 15b7:5019 | 15b7:5019 | Sandisk    | Non-Volatile memory contr... | 2     | nvme       | CAFC4421B2 |
| 15b7:501d | 15b7:501d | Sandisk    | Non-Volatile memory contr... | 2     | nvme       | FBD8D927E6 |
| 17aa:0003 | 17aa:1003 | Lenovo     | Non-Volatile memory contr... | 2     | nvme       | D6371109B2 |
| 1c5c:1504 | 0100:1093 | SK Hynix   | SC300 512GB M.2 2280 SATA... | 2     | nvme       | 42FB24801D |
| 1cc1:2263 | 1cc1:2263 | ADATA T... | Non-Volatile memory contr... | 2     | nvme       | 1B292E7E77 |
| 1e49:0001 | 1e49:1e49 | Yangtze... | Non-Volatile memory contr... | 2     | nvme       | A48EC730B7 |
| 1e95:9100 | 126f:2263 | Solid S... | Non-Volatile memory contr... | 2     | nvme       | B87CA56DA6 |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2822 | 1043:8694 | Intel      | SATA Controller [RAID mode]  | 128   | ahci       | 381023907E |
| 8086:2822 | 1458:b005 | Intel      | SATA Controller [RAID mode]  | 96    | ahci       | 83857E3215 |
| 8086:2822 | 1028:0420 | Intel      | SATA Controller [RAID mode]  | 84    | ahci       | 999FEEE9DC |
| 8086:2822 | 1028:05a4 | Intel      | SATA Controller [RAID mode]  | 82    | ahci       | E49216D0BB |
| 1106:3249 | 1106:3249 | VIA Tec... | VT6421 IDE/SATA Controller   | 72    | sata_via   | 863C87266B |
| 8086:2822 | 1028:047e | Intel      | SATA Controller [RAID mode]  | 60    | ahci       | 6AF9EA19B5 |
| 8086:2822 | 103c:1309 | Intel      | SATA Controller [RAID mode]  | 48    | ahci       | EB0C052885 |
| 8086:2822 | 103c:2a6f | Intel      | SATA Controller [RAID mode]  | 45    | ahci       | D5D1B22B75 |
| 1095:3114 | 1095:7114 | Silicon... | SiI 3114 [SATALink/SATARa... | 42    | sata_sil   | 497C824FD5 |
| 8086:2822 | 1043:8534 | Intel      | SATA Controller [RAID mode]  | 39    | ahci       | 6476A95A04 |
| 1022:7916 | 1022:7901 | AMD        | RS690 PCI to PCI Bridge (... | 38    | ahci       | 6B471BC42D |
| 8086:2822 | 103c:2a9c | Intel      | SATA Controller [RAID mode]  | 38    | ahci       | 14712A07FB |
| 8086:2822 | 1028:052c | Intel      | SATA Controller [RAID mode]  | 35    | ahci       | 79E64FF0D3 |
| 8086:2822 | 103c:130a | Intel      | SATA Controller [RAID mode]  | 33    | ahci       | 328FCB35ED |
| 1022:43bd | 1b21:1062 | AMD        | FCH RAID Controller          | 31    | rcraid     | 1E61CC1252 |
| 8086:2822 | 1458:b000 | Intel      | SATA Controller [RAID mode]  | 28    | ahci       | 54642E6EE3 |
| 1095:3132 | 1043:819f | Silicon... | SiI 3132 Serial ATA Raid ... | 27    | sata_sil24 | 1739E3B05D |
| 8086:2822 | 1028:0293 | Intel      | SATA Controller [RAID mode]  | 27    | ahci       | ECDA4970D8 |
| 8086:2822 | 1043:872f | Intel      | SATA Controller [RAID mode]  | 27    | ahci       | 37523E831D |
| 8086:2826 | 103c:1589 | Intel      | C600/X79 series chipset S... | 27    | ahci       | 46C635D9AB |
| 1095:3512 | 1095:6512 | Silicon... | SiI 3512 [SATALink/SATARa... | 26    | sata_sil   | EFDE12BE05 |
| 1095:3132 | 1095:7132 | Silicon... | SiI 3132 Serial ATA Raid ... | 25    | sata_sil24 | C586C22B15 |
| 8086:2822 | 1028:06b9 | Intel      | SATA Controller [RAID mode]  | 23    | ahci       | E4278D3243 |
| 8086:2822 | 103c:130b | Intel      | SATA Controller [RAID mode]  | 23    | ahci       | 665BAE2867 |
| 8086:2827 | 103c:212b | Intel      | C610/X99 series chipset s... | 23    | ahci       | 9D2A807F08 |
| 1095:0680 | 1095:3680 | Silicon... | PCI0680 Ultra ATA-133 Hos... | 19    | pata_si... | 07B9B49ADB |
| 8086:2822 | 1043:84ca | Intel      | SATA Controller [RAID mode]  | 19    | ahci       | 46987EB4C8 |
| 8086:2826 | 103c:212b | Intel      | C600/X79 series chipset S... | 19    | ahci       | 9D2A807F08 |
| 8086:2826 | 103c:158a | Intel      | C600/X79 series chipset S... | 18    | ahci       | 6C22E51BFC |
| 8086:2822 | 1028:02da | Intel      | SATA Controller [RAID mode]  | 17    | ahci       | 51D64C0798 |
| 8086:2822 | 1028:05a6 | Intel      | SATA Controller [RAID mode]  | 17    | ahci       | D41DEB84BF |
| 8086:2822 | 1028:07a3 | Intel      | SATA Controller [RAID mode]  | 17    | ahci       | 9D38BA75C7 |
| 8086:2822 | 1043:844d | Intel      | SATA Controller [RAID mode]  | 17    | ahci       | 834AACD006 |
| 103c:323a | 103c:3245 | Hewlett... | Smart Array G6 controllers   | 16    | hpsa       | 9753F223E2 |
| 8086:2826 | 103c:158b | Intel      | C600/X79 series chipset S... | 16    | ahci       | 24399F4E69 |
| 1002:4392 | 103c:2a92 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 15    | ahci       | A3DE463B27 |
| 8086:2826 | 1028:0738 | Intel      | C600/X79 series chipset S... | 15    | ahci       | 13718F9C0B |
| 1106:3149 | 1043:80ed | VIA Tec... | VIA VT6420 SATA RAID Cont... | 14    | sata_via   | B38568681E |
| 1106:3164 | 1106:3164 | VIA Tec... | VT6410 ATA133 RAID contro... | 14    | pata_vi... | D9D570CAE6 |
| 8086:2826 | 1028:0617 | Intel      | C600/X79 series chipset S... | 14    | ahci       | 6EBA24CF71 |
| 13c1:1004 | 13c1:1004 | 3ware      | 9650SE SATA-II RAID PCIe     | 13    | 3w_9xxx    | 166CC12002 |
| 8086:2822 | 1025:0389 | Intel      | SATA Controller [RAID mode]  | 13    | ahci       | 6E58F49020 |
| 8086:2822 | 1025:1238 | Intel      | SATA Controller [RAID mode]  | 13    | ahci       | B961168B44 |
| 8086:2822 | 1028:0276 | Intel      | SATA Controller [RAID mode]  | 13    | ahci       | 5814B0C5B0 |
| 8086:2822 | 103c:1905 | Intel      | SATA Controller [RAID mode]  | 13    | ahci       | 99B9973F19 |
| 1283:8212 |           | Integra... | IT8212 Dual channel ATA R... | 12    | pata_it... | E42A9DA750 |
| 8086:201d | 1028:0738 | Intel      | Volume Management Device ... | 12    | vmd        | 13718F9C0B |
| 8086:2822 | 1025:0589 | Intel      | SATA Controller [RAID mode]  | 12    | ahci       | 7AB93EC832 |
| 8086:2822 | 1028:085c | Intel      | SATA Controller [RAID mode]  | 12    | ahci       | 453BEAB8C3 |
| 8086:2822 | 103c:8767 | Intel      | SATA Controller [RAID mode]  | 12    | ahci       | 481BC047C1 |
| 8086:2822 | 1849:2822 | Intel      | SATA Controller [RAID mode]  | 12    | ahci       | 7891BFD540 |
| 1095:3112 | 1095:6112 | Silicon... | SiI 3112 [SATALink/SATARa... | 11    | sata_sil   | 484B4E80B1 |
| 10de:07f8 | 1025:0137 | Nvidia     | MCP73 SATA RAID Controller   | 11    | ahci       | 4AEC616B4D |
| 10de:0abc | 1025:0168 | Nvidia     | MCP79 RAID Controller        | 11    | ahci       | 6872AE9FB4 |
| 11ab:6440 | 1043:82e4 | Marvell... | 88SE6440 SAS/SATA PCIe co... | 11    | mvsas      | 6C7ECC284B |
| 8086:27c3 | 103c:2a50 | Intel      | 82801GR/GDH (ICH7R/ICH7DH... | 11    | ahci       | 42098EE0E7 |
| 8086:27c3 | 103c:2a5e | Intel      | 82801GR/GDH (ICH7R/ICH7DH... | 11    | ahci       | 1F00F6D692 |
| 8086:2822 | 1025:024c | Intel      | SATA Controller [RAID mode]  | 11    | ahci       | E355190768 |
| 8086:2822 | 1028:01dd | Intel      | SATA Controller [RAID mode]  | 11    | ahci       | 2E28996126 |
| 8086:2822 | 1028:026e | Intel      | SATA Controller [RAID mode]  | 11    | ahci       | FF796824D2 |
| 8086:2822 | 1028:040d | Intel      | SATA Controller [RAID mode]  | 11    | ahci       | DAD38E979E |
| 8086:2822 | 1028:07a1 | Intel      | SATA Controller [RAID mode]  | 11    | ahci       | F1F58938D1 |
| 8086:2822 | 103c:1308 | Intel      | SATA Controller [RAID mode]  | 11    | ahci       | FCD03CF9F8 |
| 8086:2822 | 1849:a282 | Intel      | SATA Controller [RAID mode]  | 11    | ahci       | EC939FB289 |
| 1000:0073 | 1028:1f78 | LSI Log... | MegaRAID SAS 2008 [Falcon]   | 10    | megarai... | 09302F3BB8 |
| 1002:4392 | 1025:0444 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 10    | ahci       | E6FABE6D7F |
| 1002:4392 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 10    | ahci       | B9259E3604 |
| 1002:4393 | 1043:84df | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 10    | ahci       | 6FA44D2930 |
| 1039:0180 | 1043:810e | Silicon... | RAID bus controller 180 S... | 10    | sata_sis   | 7A323363EF |
| 105a:3373 | 1043:80f5 | Promise... | PDC20378 (FastTrak 378/SA... | 10    | sata_pr... | E739F2F0BA |
| 8086:2822 | 1028:0498 | Intel      | SATA Controller [RAID mode]  | 10    | ahci       | 497C824FD5 |
| 8086:2822 | 1028:0859 | Intel      | SATA Controller [RAID mode]  | 10    | ahci       | DC55F173FE |
| 1000:0079 | 1000:9261 | LSI Log... | MegaRAID SAS 2108 [Libera... | 9     | megarai... | CD2F6268CF |
| 8086:2682 | 103c:1307 | Intel      | 631xESB/632xESB SATA RAID... | 9     | ahci       | E3159A6511 |
| 8086:2822 | 1025:0427 | Intel      | SATA Controller [RAID mode]  | 9     | ahci       | F1AA7841AD |
| 8086:2822 | 1028:01db | Intel      | SATA Controller [RAID mode]  | 9     | ahci       | 579C253FDA |
| 8086:2822 | 1028:07c5 | Intel      | SATA Controller [RAID mode]  | 9     | ahci       | 219A3A234F |
| 8086:2822 | 103c:1587 | Intel      | SATA Controller [RAID mode]  | 9     | ahci       | 0D99C162A3 |
| 8086:2822 | 103c:1791 | Intel      | SATA Controller [RAID mode]  | 9     | ahci       | 9DE8DDBD32 |
| 8086:2822 | 103c:1906 | Intel      | SATA Controller [RAID mode]  | 9     | ahci       | 62C3738CF9 |
| 8086:2822 | 1043:8383 | Intel      | SATA Controller [RAID mode]  | 9     | ahci       | 9A91C78C7A |
| 1022:7917 | 1022:7901 | AMD        | RS690 PCI to PCI Bridge (... | 8     | ahci       | 11DAEB0D8D |
| 1095:3124 | 1095:7124 | Silicon... | SiI 3124 PCI-X Serial ATA... | 8     | sata_sil24 | 25E00FC504 |
| 10de:0266 | 1028:0249 | Nvidia     | MCP51 Serial ATA Controller  | 8     | sata_nv    | A3584CB8A9 |
| 10de:0267 | 1028:0249 | Nvidia     | MCP51 Serial ATA Controller  | 8     | sata_nv    | A3584CB8A9 |
| 11ab:6485 | 11ab:6480 | Marvell... | MV64460/64461/64462 Syste... | 8     | mvsas      | EC9C58B54E |
| 11ab:6485 | 17aa:1023 | Marvell... | MV64460/64461/64462 Syste... | 8     | mvsas      | 311228018C |
| 8086:06d6 | 1043:8694 | Intel      | Comet Lake PCH-H RAID        | 8     | ahci       | 274CBA3955 |
| 8086:2822 | 1028:05d7 | Intel      | SATA Controller [RAID mode]  | 8     | ahci       | 65615A3AAA |
| 8086:2822 | 103c:1790 | Intel      | SATA Controller [RAID mode]  | 8     | ahci       | 75557F3294 |
| 8086:2822 | 1043:82d4 | Intel      | SATA Controller [RAID mode]  | 8     | ahci       | A2C823DDD7 |
| 8086:2826 | 103c:2129 | Intel      | C600/X79 series chipset S... | 8     | ahci       | 8DE5BAE655 |
| 8086:2827 | 103c:2129 | Intel      | C610/X99 series chipset s... | 8     | ahci       | 8DE5BAE655 |
| 1000:0072 | 1734:1177 | Broadco... | SAS2008 PCI-Express Fusio... | 7     | mpt3sas    | 1421A07188 |
| 1002:4393 | 1002:4393 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 7     | ahci       | 9CAFB3AD7A |
| 1002:4393 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 7     | ahci       | 37ADE7DACF |
| 1283:8212 | 1043:813a | Integra... | IT8212 Dual channel ATA R... | 7     | pata_it... | 5A7ACF0D43 |
| 1283:8212 | 1283:0001 | Integra... | IT8212 Dual channel ATA R... | 7     | pata_it... | A1EB33A5F1 |
| 8086:2682 | 103c:1306 | Intel      | 631xESB/632xESB SATA RAID... | 7     | ahci       | 986DB869B7 |
| 8086:2822 | 1028:0215 | Intel      | SATA Controller [RAID mode]  | 7     | ahci       | DF97B29E2E |

### Storage/sas (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1d6b | 103c:1589 | Intel      | C602 chipset 4-Port SATA ... | 43    | isci       | 49C747EFAD |
| 1000:0086 | 103c:158b | Broadco... | SAS2308 PCI-Express Fusio... | 31    | mpt3sas    | 24399F4E69 |
| 8086:1d6b | 103c:158a | Intel      | C602 chipset 4-Port SATA ... | 29    | isci       | 6C22E51BFC |
| 8086:1d6b | 103c:158b | Intel      | C602 chipset 4-Port SATA ... | 22    | isci       | 24399F4E69 |
| 8086:1d6b | 1028:0497 | Intel      | C602 chipset 4-Port SATA ... | 19    | isci       | 0B25532F6B |
| 1000:0072 | 1000:3020 | LSI Log... | SAS2008 PCI-Express Fusio... | 18    | mpt3sas    | A0D316EB3E |
| 1000:0072 | 1028:1f1c | LSI Log... | SAS2008 PCI-Express Fusio... | 12    | mpt3sas    | 2F188B606A |
| 1000:0087 | 1028:05a1 | Broadco... | SAS2308 PCI-Express Fusio... | 11    | mpt3sas    | 3CF0EB9253 |
| 8086:1d6b | 1734:11b6 | Intel      | C602 chipset 4-Port SATA ... | 10    | isci       | E689B2DE7A |
| 1000:0087 | 1000:3020 | LSI Log... | SAS2308 PCI-Express Fusio... | 9     | mpt3sas    | FB32FC7215 |
| 1000:0097 | 1028:0619 | Broadco... | SAS3008 PCI-Express Fusio... | 8     | mpt3sas    | 36E6C22CC6 |
| 8086:1d6b | 17aa:1026 | Intel      | C602 chipset 4-Port SATA ... | 7     | isci       | F8BE96C44A |
| 8086:1d6b | 1849:1d6b | Intel      | C602 chipset 4-Port SATA ... | 5     | isci       | 957F68F2B7 |
| 1000:0064 | 1000:30c0 | Broadco... | SAS2116 PCI-Express Fusio... | 4     | mpt3sas    | E88E18FCCA |
| 1000:0070 | 1000:3010 | LSI Log... | SAS2004 PCI-Express Fusio... | 4     | mpt3sas    | 60FF076C16 |
| 1000:0072 | 1000:3060 | Broadco... | SAS2008 PCI-Express Fusio... | 4     | mpt3sas    | 0D69EE2560 |
| 1000:0086 | 15d9:0691 | Broadco... | SAS2308 PCI-Express Fusio... | 4     | mpt3sas    | 0569365EA0 |
| 1000:0087 | 1000:3060 | Broadco... | SAS2308 PCI-Express Fusio... | 4     | mpt3sas    | BD7193B93F |
| 8086:1d68 | 1028:0495 | Intel      | C606 chipset Dual 4-Port ... | 4     | isci       | 0C3A459A0E |
| 8086:1d6b | 15d9:062c | Intel      | C602 chipset 4-Port SATA ... | 4     | isci       | D8C9D41136 |
| 1000:0072 | 1000:30f0 | Broadco... | SAS2008 PCI-Express Fusio... | 3     | mpt3sas    | 3B97DD5D3E |
| 1000:0072 | 1028:1f1d | LSI Log... | SAS2008 PCI-Express Fusio... | 3     | mpt3sas    | 3B9C7E2331 |
| 1000:0097 | 1000:30a0 | Broadco... | SAS3008 PCI-Express Fusio... | 3     | mpt3sas    | 98EA3E97E6 |
| 8086:1d60 | 1028:0497 | Intel      | C608 chipset Dual 4-Port ... | 3     | isci       | 113235448D |
| 8086:1d6b | 17aa:1028 | Intel      | C602 chipset 4-Port SATA ... | 3     | isci       | 8841F4EB25 |
| 1000:0064 | 1000:3030 | Broadco... | SAS2116 PCI-Express Fusio... | 2     | mpt2sas    | BF66E1D281 |
| 1000:0072 | 1000:3080 | LSI Log... | SAS2008 PCI-Express Fusio... | 2     | mpt3sas    | 53B29EDC51 |
| 1000:0072 | 1000:30b0 | Broadco... | SAS2008 PCI-Express Fusio... | 2     | mpt3sas    | 33A89C4C5A |
| 1000:0072 | 15d9:0400 | Broadco... | SAS2008 PCI-Express Fusio... | 2     | mpt3sas    | 96607F4270 |
| 1000:007e | 108e:050a | Broadco... | SSS6200 PCI-Express Flash... | 2     | mpt3sas    | 12E7B4FF29 |
| 1000:0086 | 1000:0086 | LSI Log... | SAS2308 PCI-Express Fusio... | 2     | mpt3sas    | 63B48DFA23 |
| 1000:0087 | 1000:3030 | Broadco... | SAS2308 PCI-Express Fusio... | 2     | mpt3sas    | 1D8E87502F |
| 1000:0087 | 1590:0041 | Broadco... | SAS2308 PCI-Express Fusio... | 2     | mpt3sas    | DC85BB471A |
| 1000:0097 | 1000:30e0 | LSI Log... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | 8EF7556453 |
| 1000:0097 | 1028:1f46 | Broadco... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | 3C396F0B59 |
| 1000:0097 | 1734:1214 | LSI Log... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | A7138E79C0 |
| 1000:00c4 | 1000:31a0 | Broadco... | SAS3224 PCI-Express Fusio... | 2     | mpt3sas    | 195F9748AD |
| 8086:1d69 | 17aa:1026 | Intel      | C604/X79 series chipset 4... | 2     | isci       | 99B572DE7F |
| 8086:1d6a | 17aa:1027 | Intel      | C600/X79 series chipset D... | 2     | isci       | 8D7A62CE1A |
| 8086:1d6b | 1028:0495 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | BC7C3F8C4D |
| 8086:1d6b | 1028:0496 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 80E68A5C66 |
| 8086:1d6b | 15d9:0628 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 6908407322 |
| 8086:1d6b | 15d9:0709 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 7D84E25468 |
| 8086:1d6b | 17aa:1027 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | E3C6A7B793 |
| 1000:005d | 1000:9a63 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | megarai... | 8EFAF14886 |
| 1000:0064 | 1000:30d0 | Broadco... | SAS2116 PCI-Express Fusio... | 1     | mpt3sas    | 3294F4EFD3 |
| 1000:0087 | 1014:047a | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | B9E45DB0E3 |
| 1000:0087 | 1590:0043 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | AB5267E214 |
| 1000:0087 | 8086:3060 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | F2B18DC242 |
| 1000:0097 | 1043:860c | Broadco... | SAS3008 PCI-Express Fusio... | 1     | mpt3sas    | C624F64EDE |
| 1000:0097 | 15d9:0808 | Broadco... | SAS3008 PCI-Express Fusio... | 1     | mpt3sas    | 4F2775E12D |
| 1000:0097 | 1849:0097 | Broadco... | SAS3008 PCI-Express Fusio... | 1     | mpt3sas    | FA8D061F8F |
| 1000:00ac | 1000:3000 | Broadco... | SAS3416 Fusion-MPT Tri-Mo... | 1     | mpt3sas    | 8C80B197C2 |
| 1000:00af | 1000:3010 | Broadco... | SAS3408 Fusion-MPT Tri-Mo... | 1     | mpt3sas    | 1FCE0AB0E8 |
| 117c:0042 | 117c:0042 | ATTO Te... | ExpressSAS 6Gb/s SAS/SATA... | 1     | pm80xx     | 2DF53AC534 |
| 117c:0042 | 117c:0046 | ATTO Te... | ExpressSAS 6Gb/s SAS/SATA... | 1     | pm80xx     | 72B568A9B6 |
| 8086:1d60 | 1028:0496 | Intel      | C608 chipset Dual 4-Port ... | 1     | isci       | 1518FF90F9 |
| 8086:1d68 | 15d9:0626 | Intel      | C606 chipset Dual 4-Port ... | 1     | isci       | 2B8813F5C4 |
| 8086:1d68 | 15d9:0628 | Intel      | C606 chipset Dual 4-Port ... | 1     | isci       | 74EFA61302 |
| 8086:1d68 | 8086:1d68 | Intel      | C606 chipset Dual 4-Port ... | 1     | isci       | EBA3BBC86D |
| 8086:1d69 | 15d9:0706 | Intel      | C604/X79 series chipset 4... | 1     | isci       | AA3D8595BA |
| 8086:1d69 | 8086:1d69 | Intel      | C604/X79 series chipset 4... | 1     | isci       | 53874D702A |
| 8086:1d6b |           | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 99E743CA9E |
| 8086:1d6b | 15d9:0626 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 42A76FBC95 |
| 8086:1d6b | 15d9:062b | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | A897C366A9 |
| 8086:1d6b | 15d9:0667 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 8FDC5D8AB4 |
| 8086:1d6b | 15d9:070a | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 1F3561AA7D |
| 9005:028d | 9005:0651 | Adaptec    | Series 8 12G SAS/PCIe 3      | 1     | aacraid    | 19A9020FEF |
| 9005:028f | 103c:0600 | Adaptec    | Smart Storage PQI SAS        | 1     | smartpqi   | BE0EB33CD5 |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1000:0058 | 1028:021d | LSI Log... | SAS1068E PCI-Express Fusi... | 28    | mptsas     | 2F188B606A |
| 1000:0058 | 103c:130b | LSI Log... | SAS1068E PCI-Express Fusi... | 27    | mptsas     | 665BAE2867 |
| 1000:0056 | 1000:3090 | LSI Log... | SAS1064ET PCI-Express Fus... | 14    | mptsas     | 06EFEDBF24 |
| 1000:0058 | 1028:1f0e | LSI Log... | SAS1068E PCI-Express Fusi... | 13    | mptsas     | F1B8348661 |
| 1000:0054 | 103c:0a98 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 10    | mptsas     | 4299904C4D |
| 9004:5078 | 9004:7850 | Adaptec    | AIC-7850T/7856T [AVA-2902... | 10    | aic7xxx    | ED9FEAB726 |
| 9004:7178 |           | Adaptec    | AIC-7870P/7871 [AHA-2940/... | 8     | aic7xxx    | CAD3B9B0F1 |
| 9004:8178 |           | Adaptec    | AIC-7870P/7881U [AHA-2940... | 6     | aic7xxx    | E4B76F9137 |
| 9004:8178 | 9004:7881 | Adaptec    | AIC-7870P/7881U [AHA-2940... | 6     | aic7xxx    | AB9C12AF26 |
| 1b85:1021 | 1b85:1021 | OCZ Tec... | OCZ SCSI storage controller  | 5     | mvsas      | 71E296F6E0 |
| 9004:6178 | 9004:7861 | Adaptec    | AIC-7861                     | 5     | aic7xxx    | 5416A71FEA |
| 1000:0001 |           | LSI Log... | 53c810                       | 4     | sym53c8xx  | F2C624A258 |
| 1000:0050 | 103c:3015 | Broadco... | SAS1064 PCI-X Fusion-MPT SAS | 4     | mptsas     | C20157D427 |
| 1000:0058 | 103c:12fe | LSI Log... | SAS1068E PCI-Express Fusi... | 4     | mptsas     | 6D6F2CE899 |
| 1000:0058 | 103c:3229 | LSI Log... | SAS1068E PCI-Express Fusi... | 4     | mptsas     | 078AB4C114 |
| 1de1:0391 | 1de1:0391 | Tekram ... | TRM-S1040 [DC-315 / DC-39... | 4     | dc395x     | 510A70AB34 |
| 9005:8017 | 9005:0045 | Adaptec    | ASC-29320ALP U320            | 4     | aic79xx    | BB541DFDE4 |
| 1000:0030 | 103c:12f1 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 3     | mptspi     | AD9D1EDCBB |
| 1000:0030 | 103c:1500 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 3     | mptspi     | A94946D561 |
| 1000:0054 | 1028:1f08 | LSI Log... | SAS1068 PCI-X Fusion-MPT SAS | 3     | mptsas     | CB363A3342 |
| 10cd:1300 | 10cd:1310 | Advance... | ASC1300 / ASC3030 [ABP940... | 3     | advansys   | A978613702 |
| 9004:5078 |           | Adaptec    | AIC-7850T/7856T [AVA-2902... | 3     | aic7xxx    | 330F034C61 |
| 9004:6178 |           | Adaptec    | AIC-7861                     | 3     | aic7xxx    | A35B309960 |
| 9005:0010 | 9005:a180 | Adaptec    | AHA-2940U2/U2W               | 3     | aic7xxx    | F894ABD641 |
| 9005:0080 | 9005:62a0 | Adaptec    | AIC-7892A U160/m             | 3     | aic7xxx    | 0C6668DEE5 |
| 9005:8017 | 9005:0044 | Adaptec    | ASC-29320ALP U320            | 3     | aic79xx    | 14ACFD829D |
| 1000:000f | 1000:1000 | Broadco... | 53c875                       | 2     | sym53c8xx  | AE45AB5C00 |
| 1000:0030 | 1000:50c0 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 2     | mptspi     | 9844591CD4 |
| 1000:0030 | 103c:322a | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 2     | mptspi     | C156F0AB27 |
| 1000:0056 | 1014:03bb | LSI Log... | SAS1064ET PCI-Express Fus... | 2     | mptsas     | A6FAE29097 |
| 1000:0056 | 103c:322b | LSI Log... | SAS1064ET PCI-Express Fus... | 2     | mptsas     | 9974950D4A |
| 1000:0058 | 1000:3140 | Broadco... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | 7DE05CDBC3 |
| 1000:0058 | 1014:0396 | Broadco... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | E4B76F9137 |
| 1000:0058 | 1734:1130 | Broadco... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | 2A000E48F4 |
| 1000:0058 | 17aa:101d | Broadco... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | 8ADC2B3A82 |
| 11ab:7042 | 11ab:11ab | Marvell... | 88SX7042 PCI-e 4-port SAT... | 2     | sata_mv    | 40990F73A5 |
| 1b85:1041 | 1b85:1041 | OCZ Tec... | RevoDrive 3 X2 PCI-Expres... | 2     | mvsas      | E0FC243F47 |
| 9005:0010 | 9005:2180 | Adaptec    | AHA-2940U2/U2W               | 2     | aic7xxx    | 67C4745D3A |
| 9005:0080 | 9005:e2a0 | Adaptec    | AIC-7892A U160/m             | 2     | aic7xxx    | 04D9B1D5AC |
| 9005:8012 | 9005:0042 | Adaptec    | ASC-29320 U320               | 2     | aic79xx    | 5923C246C4 |
| 1000:0030 | 0e11:00f4 | Broadco... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 72330BE67D |
| 1000:0030 | 1014:1000 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 659D759E6D |
| 1000:0030 | 1028:012c | Broadco... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 90378ABAC3 |
| 1000:0030 | 1028:1040 | Broadco... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | D83C8DDEDF |
| 1000:0030 | 103c:3108 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | A2995F5723 |
| 1000:0054 | 1000:30e0 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | E0E805180D |
| 1000:0054 | 1028:1f09 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | FF69AE3970 |
| 1000:0054 | 103c:3228 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | B4F5FF56BD |
| 1000:0056 | 1734:1131 | Broadco... | SAS1064ET PCI-Express Fus... | 1     | mptsas     | 4E888D4C51 |
| 1000:0058 | 1000:3002 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | 1E88FE8CBB |
| 1000:0058 | 1028:1f10 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | F3E244219B |
| 1000:0058 | 10f1:2918 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | 032066549F |
| 1000:0058 | 1734:115a | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | AD12D1E2B9 |
| 1000:0059 | 1000:3002 | LSI Log... | MegaRAID SAS 8208ELP/8208ELP | 1     | mptsas     | 2985792735 |
| 1022:2020 |           | AMD        | 53c974 [PCscsi]              | 1     | am53c974   | E9A963FC61 |
| 1069:b166 | 1014:02d3 | Mylex      | AcceleRAID 600/500/400/Sa... | 1     | ipr        | E0E805180D |
| 1095:3110 | 1095:7110 | Silicon... | SCSI storage controller      | 1     |            | 69BD5A45B3 |
| 10cd:1300 |           | Advance... | ASC1300 / ASC3030 [ABP940... | 1     | advansys   | 0E8D69E9B8 |
| 1101:9400 | 9292:0202 | Initio     | INI-940 Fast Wide SCSI Ad... | 1     | initio     | 121278EA8F |
| 1101:9500 | 9292:0202 | Initio     | INI-950 SCSI Adapter         | 1     | initio     | 1CEC27CDDD |
| 1103:2310 | 11ab:11ab | HighPoi... | RocketRAID 2310 4 Port SA... | 1     | sata_mv    | 353DF9771E |
| 117c:0030 | 117c:8027 | ATTO Te... | Ultra320 SCSI Host Adapter   | 1     | mptspi     | D08EA242AF |
| 1191:8020 | 1191:8020 | Artop E... | AEC6712U SCSI                | 1     | atp870u    | E593748D4E |
| 1191:8040 | 1191:8040 | Artop E... | AEC6712D SCSI                | 1     | atp870u    | DE67919D1B |
| 11ab:6041 | 1043:8150 | Marvell... | MV88SX6041 4-port SATA II... | 1     | sata_mv    | 3FECAFF6C4 |
| 11ab:6081 | 11ab:11ab | Marvell... | MV88SX6081 8-port SATA II... | 1     | sata_mv    | 1F4F0C96FA |
| 11ab:6440 | 11ab:6480 | Marvell... | 88SE6440 SAS/SATA PCIe co... | 1     | mvsas      | EC1EC65380 |
| 1b85:1221 | 1b85:1221 | OCZ Tec... | OCZ 12xx SCSI Controller     | 1     |            | 323982480D |
| 9004:3860 | 9004:3869 | Adaptec    | AHA-2930CU                   | 1     | aic7xxx    | BC2D1E8C10 |
| 9004:8278 |           | Adaptec    | AHA-3940U/UW/UWD / AIC-7882U | 1     | aic7xxx    | 3A362598FB |
| 9004:8778 | 9004:7887 | Adaptec    | AHA-2940UW Pro / AIC-788x    | 1     | aic7xxx    | E2380E1CCE |
| 9005:0010 | 9005:a100 | Adaptec    | AHA-2940U2/U2W               | 1     | aic7xxx    | 0A58FAB188 |
| 9005:0011 | 9005:0181 | Adaptec    | AHA-2930U2                   | 1     | aic7xxx    | 86D356F643 |
| 9005:0081 | 9005:62a1 | Adaptec    | AIC-7892B U160/m             | 1     | aic7xxx    | 9854E43724 |
| 9005:00c0 | 9005:f620 | Adaptec    | AHA-3960D / AIC-7899A U160/m | 1     | aic7xxx    | A966231E0C |
| 9005:00cf | 15d9:9005 | Adaptec    | AIC-7899P U160/m             | 1     | aic7xxx    | 34867AD122 |
| 9005:8016 | 9005:0040 | Adaptec    | ASC-39320A U320              | 1     |            | 243DBA3B27 |
| 9005:801d | 10f1:2676 | Adaptec    | AIC-7902B U320               | 1     | aic79xx    | 219383F559 |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1911 | 1458:5000 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 412   |            | 8C2B6CF453 |
| 8086:2f6e |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 394   |            | 9D2A807F08 |
| 8086:2f6f |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 394   |            | 9D2A807F08 |
| 8086:2f88 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 394   |            | 9D2A807F08 |
| 8086:2f8a |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 394   |            | 9D2A807F08 |
| 8086:2fae |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 394   |            | 9D2A807F08 |
| 8086:2faf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 394   |            | 9D2A807F08 |
| 8086:2fb8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 394   |            | 9D2A807F08 |
| 8086:2fb9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 394   |            | 9D2A807F08 |
| 8086:2fba |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 394   |            | 9D2A807F08 |
| 8086:2fbb |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 394   |            | 9D2A807F08 |
| 8086:2fbe |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 394   |            | 9D2A807F08 |
| 8086:2fbf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 394   |            | 9D2A807F08 |
| 8086:2ff8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 394   |            | 9D2A807F08 |
| 8086:2ff9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 394   |            | 9D2A807F08 |
| 8086:d150 |           | Intel      | Core Processor QPI Link      | 365   |            | 388CAF40FE |
| 8086:d151 |           | Intel      | Core Processor QPI Routin... | 365   |            | 388CAF40FE |
| 8086:d158 |           | Intel      | Core Processor Miscellane... | 365   |            | 388CAF40FE |
| 8086:2f1d | 8086:2f1d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 358   |            | 9D2A807F08 |
| 8086:2f1e | 8086:2f1e | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 358   |            | 9D2A807F08 |
| 8086:2f1f | 8086:2f1f | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 358   |            | 9D2A807F08 |
| 8086:2f71 | 8086:2f71 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 358   |            | 9D2A807F08 |
| 8086:2f98 | 8086:2f98 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 358   |            | 9D2A807F08 |
| 8086:2f99 | 8086:2f99 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 358   |            | 9D2A807F08 |
| 8086:2f9a | 8086:2f9a | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 358   |            | 9D2A807F08 |
| 8086:2f9c | 8086:2f9c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 358   |            | 9D2A807F08 |
| 8086:2fa0 | 8086:2fa0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 358   | sb_edac    | 9D2A807F08 |
| 8086:2fa8 | 8086:2fa8 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 358   |            | 9D2A807F08 |
| 8086:2faa | 8086:2faa | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 358   |            | 9D2A807F08 |
| 8086:2fab | 8086:2fab | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 358   |            | 9D2A807F08 |
| 8086:2fb0 | 8086:2fb0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 358   | hswep_u... | 9D2A807F08 |
| 8086:2fb1 | 8086:2fb1 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 358   | hswep_u... | 9D2A807F08 |
| 8086:2fb2 | 8086:2fb2 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 358   |            | 9D2A807F08 |
| 8086:2fb3 | 8086:2fb3 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 358   |            | 9D2A807F08 |
| 8086:2fc0 | 8086:2fc0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 358   | hswep_u... | 9D2A807F08 |
| 8086:2f81 | 8086:2f81 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 323   |            | 9D2A807F08 |
| 8086:2fe0 | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 323   |            | 9D2A807F08 |
| 8086:2fe1 | 8086:2fe1 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 323   |            | 9D2A807F08 |
| 8086:2fe2 | 8086:2fe2 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 323   |            | 9D2A807F08 |
| 8086:2fe3 | 8086:2fe3 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 323   |            | 9D2A807F08 |
| 8086:2ffc | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 323   |            | 9D2A807F08 |
| 8086:2ffd | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 323   |            | 9D2A807F08 |
| 8086:2ffe | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 323   |            | 9D2A807F08 |
| 8086:2fbc |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 300   |            | F432BA24E0 |
| 8086:2fbd |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 300   |            | F432BA24E0 |
| 8086:2f68 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 299   |            | 9D2A807F08 |
| 8086:2fd0 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 299   | hswep_u... | 9D2A807F08 |
| 8086:2fe4 | 8086:2fe4 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 283   |            | 9D2A807F08 |
| 8086:2fe5 | 8086:2fe5 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 283   |            | 9D2A807F08 |
| 8086:2fac | 8086:2fac | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 272   |            | 9D2A807F08 |
| 8086:2fad | 8086:2fad | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 272   |            | 9D2A807F08 |
| 8086:2fb4 | 8086:2fb4 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 272   | hswep_u... | 9D2A807F08 |
| 8086:2fb5 | 8086:2fb5 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 272   | hswep_u... | 9D2A807F08 |
| 8086:2fb6 | 8086:2fb6 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 272   |            | 9D2A807F08 |
| 8086:2fb7 | 8086:2fb7 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 272   |            | 9D2A807F08 |
| 8086:2576 |           | Intel      | 82865G/PE/P Processor to ... | 253   |            | 467C3682C1 |
| 8086:2f28 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 218   |            | 9D2A807F08 |
| 8086:2f29 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 218   |            | 9D2A807F08 |
| 8086:2f2a |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 218   |            | 9D2A807F08 |
| 8086:d156 |           | Intel      | Core Processor Semaphore ... | 209   |            | 388CAF40FE |
| 8086:d155 |           | Intel      | Core Processor System Man... | 203   |            | 388CAF40FE |
| 8086:d157 |           | Intel      | Core Processor System Con... | 203   |            | 388CAF40FE |
| 8086:3c71 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 173   |            | 60F5B34BDD |
| 8086:3c45 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to Q... | 172   | snbep_u... | 60F5B34BDD |
| 8086:3cb8 | 8086:0000 | Intel      | Xeon E5/Core i7 DDRIO        | 169   |            | 60F5B34BDD |
| 8086:3ce8 | 8086:0000 | Intel      | Xeon E5/Core i7 Unicast R... | 168   |            | 60F5B34BDD |
| 8086:3c80 | 8086:0000 | Intel      | Xeon E5/Core i7 QPI Link 0   | 167   |            | 60F5B34BDD |
| 8086:3c90 | 8086:0000 | Intel      | Xeon E5/Core i7 QPI Link 1   | 167   |            | 60F5B34BDD |
| 8086:3ca8 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 167   | sb_edac    | 60F5B34BDD |
| 8086:3caa | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 167   |            | 60F5B34BDD |
| 8086:3cab | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 167   |            | 60F5B34BDD |
| 8086:3cac | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 167   |            | 60F5B34BDD |
| 8086:3cad | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 167   |            | 60F5B34BDD |
| 8086:3cae | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 167   |            | 60F5B34BDD |
| 8086:3cb0 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 167   | snbep_u... | 60F5B34BDD |
| 8086:3cb1 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 167   | snbep_u... | 60F5B34BDD |
| 8086:3cb2 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 167   |            | 60F5B34BDD |
| 8086:3cb3 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 167   |            | 60F5B34BDD |
| 8086:3cb5 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 167   | snbep_u... | 60F5B34BDD |
| 8086:3cb6 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 167   |            | 60F5B34BDD |
| 8086:3cb7 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 167   |            | 60F5B34BDD |
| 8086:3cc0 | 8086:0000 | Intel      | Xeon E5/Core i7 Power Con... | 167   |            | 60F5B34BDD |
| 8086:3cc1 | 8086:0000 | Intel      | Xeon E5/Core i7 Power Con... | 167   |            | 60F5B34BDD |
| 8086:3cc2 | 8086:0000 | Intel      | Xeon E5/Core i7 Power Con... | 167   |            | 60F5B34BDD |
| 8086:3cd0 | 8086:0000 | Intel      | Xeon E5/Core i7 Power Con... | 167   |            | 60F5B34BDD |
| 8086:3ce0 | 8086:0000 | Intel      | Xeon E5/Core i7 Interrupt... | 167   |            | 60F5B34BDD |
| 8086:3ce3 | 8086:0000 | Intel      | Xeon E5/Core i7 Semaphore... | 167   |            | 60F5B34BDD |
| 8086:3ce4 | 8086:0000 | Intel      | Xeon E5/Core i7 R2PCIe       | 167   |            | 60F5B34BDD |
| 8086:3c83 | 8086:0000 | Intel      | Xeon E5/Core i7 QPI Link ... | 165   |            | 60F5B34BDD |
| 8086:3c84 | 8086:0000 | Intel      | Xeon E5/Core i7 QPI Link ... | 165   |            | 60F5B34BDD |
| 8086:3c93 | 8086:0000 | Intel      | Xeon E5/Core i7 QPI Link ... | 165   |            | 60F5B34BDD |
| 8086:3c94 | 8086:0000 | Intel      | Xeon E5/Core i7 QPI Link ... | 165   |            | 60F5B34BDD |
| 8086:3cf4 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 165   |            | 60F5B34BDD |
| 8086:3cf5 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 165   |            | 60F5B34BDD |
| 8086:3cf6 | 8086:0000 | Intel      | Xeon E5/Core i7 System Ad... | 165   |            | 60F5B34BDD |
| 8086:3ca0 |           | Intel      | Xeon E5/Core i7 Processor... | 163   |            | 60F5B34BDD |
| 8086:d155 | 0043:0083 | Intel      | Core Processor System Man... | 162   |            | 4E4391F329 |
| 8086:d156 | 0043:0083 | Intel      | Core Processor Semaphore ... | 162   |            | 4E4391F329 |
| 8086:d157 | 0043:0083 | Intel      | Core Processor System Con... | 162   |            | 4E4391F329 |
| 8086:3cb4 | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 157   | snbep_u... | 60F5B34BDD |

### Tv card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 109e:036e |           | Brooktree  | Bt878 Video Capture          | 26    | bttv       | 2B61653CEA |
| 1131:7130 | 5ace:5050 | Philips... | SAA7130 Video Broadcast D... | 20    | saa7134    | 34D12D37FD |
| 1131:7133 | 1461:a11b | Philips... | SAA7131/SAA7133/SAA7135 V... | 20    | saa7134    | D9F1062C4A |
| 1131:7133 | 5ace:5090 | Philips... | SAA7131/SAA7133/SAA7135 V... | 19    | saa7134    | F125F4CD03 |
| 1131:7134 | 5ace:5070 | Philips... | SAA7134/SAA7135HL Video B... | 17    | saa7134    | B6FCAC82E8 |
| 14f1:8880 | 0070:7801 | Conexan... | CX23887/8 PCIe Broadcast ... | 16    | cx23885    | D5D1B22B75 |
| 4444:0016 | 0070:8801 | Interne... | iTVC16 (CX23416) Video De... | 16    | ivtv       | EEA8D03E34 |
| 109e:036e | 1461:0003 | Brooktree  | Bt878 Video Capture          | 15    | bttv       | 59D57FE423 |
| 1131:7133 | 1461:4255 | Philips... | SAA7131/SAA7133/SAA7135 V... | 15    | saa7134    | FB6A317289 |
| 1131:7134 | 1461:9715 | Philips... | SAA7134/SAA7135HL Video B... | 14    | saa7134    | BC313E49BE |
| 1131:7133 | 16be:000d | Philips... | SAA7131/SAA7133/SAA7135 V... | 13    | saa7134    | 91B1729919 |
| 1131:7134 | 185b:c200 | Philips... | SAA7134/SAA7135HL Video B... | 13    | saa7134    | 638993C7B0 |
| 14f1:8852 | 0070:7911 | Conexan... | CX23885 PCI Video and Aud... | 13    | cx23885    | A549C95CBD |
| 1131:7130 | 1131:0000 | Philips... | SAA7130 Video Broadcast D... | 12    | saa7134    | 2C35EE27D9 |
| 109e:036e | 0070:13eb | Brooktree  | Bt878 Video Capture          | 10    | bttv       | 65649C54D6 |
| 1131:7130 | 1461:2115 | Philips... | SAA7130 Video Broadcast D... | 10    | saa7134    | 417D975CD9 |
| 1131:7133 | 0000:4091 | Philips... | SAA7131/SAA7133/SAA7135 V... | 10    | saa7134    | E7042308E9 |
| 1131:7133 | 1131:0000 | Philips... | SAA7131/SAA7133/SAA7135 V... | 10    | saa7134    | 60E1A81B56 |
| 1131:7133 | 11bd:002f | Philips... | SAA7131/SAA7133/SAA7135 V... | 10    | saa7134    | 6AB1C423DB |
| 1131:7134 | 1131:0000 | Philips... | SAA7134/SAA7135HL Video B... | 10    | saa7134    | 7B4F00A530 |
| 1131:7133 | 1043:4871 | Philips... | SAA7131/SAA7133/SAA7135 V... | 9     | saa7134    | 41A11F1678 |
| 1131:7133 | 5ace:6090 | Philips... | SAA7131/SAA7133/SAA7135 V... | 9     | saa7134    | 14E5916050 |
| 1131:7133 | 5ace:7290 | Philips... | SAA7131/SAA7133/SAA7135 V... | 9     | saa7134    | 60AB9AF8C6 |
| 11de:6057 | 1031:7efe | Zoran      | ZR36057PQC Video cutting ... | 9     | zr36067    | 435ED8B17A |
| 14f1:8800 |           | Conexan... | CX23880/1/2/3 PCI Video a... | 9     | cx8800     | 7099E6EF4B |
| 14f1:8880 | 0070:f038 | Conexan... | CX23887/8 PCIe Broadcast ... | 9     | cx23885    | DEC7AC6A34 |
| 4444:0016 | 1461:c439 | Interne... | iTVC16 (CX23416) Video De... | 9     | ivtv       | 0C38152A55 |
| 1131:7130 | 1461:a11b | Philips... | SAA7130 Video Broadcast D... | 8     | saa7134    | D30442701F |
| 1131:7133 | 1461:0155 | Philips... | SAA7131/SAA7133/SAA7135 V... | 8     | saa7134    | 32329B8223 |
| 1131:7133 | 1461:f11d | Philips... | SAA7131/SAA7133/SAA7135 V... | 8     | saa7134    | 818EC10EC8 |
| 1131:7133 | 185b:c100 | Philips... | SAA7131/SAA7133/SAA7135 V... | 8     | saa7134    | 5FE1529C55 |
| 1131:7133 | 5ace:7595 | Philips... | SAA7131/SAA7133/SAA7135 V... | 8     | saa7134    | 8CA76C1F85 |
| 1131:7134 | 5168:0138 | Philips... | SAA7134/SAA7135HL Video B... | 8     | saa7134    | 69A029F975 |
| 1131:7134 | 5ace:6070 | Philips... | SAA7134/SAA7135HL Video B... | 8     | saa7134    | 7920A2997E |
| 14f1:5b7a | 0070:7400 | Conexan... | CX23418 Single-Chip MPEG-... | 8     | cx18       | 79BA20ACCA |
| 14f1:8880 | 0070:c138 | Conexan... | CX23887/8 PCIe Broadcast ... | 8     | cx23885    | D0A1BC0E01 |
| 1131:7133 | 1043:4876 | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | F9BFF20C4D |
| 1131:7133 | 11bd:002e | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 548AFBB702 |
| 1131:7133 | 1461:a11a | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 948B6142EC |
| 1131:7133 | 1461:a14b | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 0F5E8185C5 |
| 1131:7133 | 5ace:6193 | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 01145B2627 |
| 1131:7134 | 16be:0003 | Philips... | SAA7134/SAA7135HL Video B... | 7     | saa7134    | F5D9A3BA0E |
| 14f1:8800 | 107d:6611 | Conexan... | CX23880/1/2/3 PCI Video a... | 7     | cx8800     | ACE5E495F5 |
| 14f1:8852 | 0070:6a28 | Conexan... | CX23885 PCI Video and Aud... | 7     | cx23885    | 517C6137A3 |
| 14f1:8852 | 0070:6b28 | Conexan... | CX23885 PCI Video and Aud... | 7     | cx23885    | 517C6137A3 |
| 14f1:8852 | 0070:71d3 | Conexan... | CX23885 PCI Video and Aud... | 7     | cx23885    | E7E7F905C7 |
| 14f1:8880 | 0070:6a18 | Conexan... | CX23887/8 PCIe Broadcast ... | 7     | cx23885    | DD6513E107 |
| 14f1:8880 | 0070:6b18 | Conexan... | CX23887/8 PCIe Broadcast ... | 7     | cx23885    | DD6513E107 |
| 109e:036e | 107d:6609 | Brooktree  | Bt878 Video Capture          | 6     | bttv       | 31DFECDF4A |
| 1131:7130 | 1a7f:2008 | Philips... | SAA7130 Video Broadcast D... | 6     | saa7134    | 00C624B592 |
| 1131:7130 | 5168:0138 | Philips... | SAA7130 Video Broadcast D... | 6     | saa7134    | CE0076FD09 |
| 1131:7133 | 1461:0055 | Philips... | SAA7131/SAA7133/SAA7135 V... | 6     | saa7134    | 34AB0FD5ED |
| 1131:7133 | 16be:0010 | Philips... | SAA7131/SAA7133/SAA7135 V... | 6     | saa7134    | C554C3A77F |
| 1131:7134 | 0000:4071 | Philips... | SAA7134/SAA7135HL Video B... | 6     | saa7134    | 03AE7F53DD |
| 1131:7134 | 4e42:0138 | Philips... | SAA7134/SAA7135HL Video B... | 6     | saa7134    | 4FF5521749 |
| 14f1:8800 | b200:4200 | Conexan... | CX23880/1/2/3 PCI Video a... | 6     | cx8800     | D3A67F88D8 |
| 14f1:8802 | b200:4200 | Conexan... | CX23880/1/2/3 PCI Video a... | 6     | cx8802     | D3A67F88D8 |
| 14f1:8852 | 4254:0952 | Conexan... | CX23885 PCI Video and Aud... | 6     | cx23885    | 44D5DCA448 |
| 14f1:8880 | 0070:2a18 | Conexan... | CX23887/8 PCIe Broadcast ... | 6     | cx23885    | 9683DF8A33 |
| 14f1:8880 | 0070:6a28 | Conexan... | CX23887/8 PCIe Broadcast ... | 6     | cx23885    | EB20131CD9 |
| 14f1:8880 | 0070:6b28 | Conexan... | CX23887/8 PCIe Broadcast ... | 6     | cx23885    | EB20131CD9 |
| 14f1:8880 | 1461:d439 | Conexan... | CX23887/8 PCIe Broadcast ... | 6     | cx23885    | F9720F4227 |
| 4444:0803 | 0070:4000 | Interne... | iTVC15 (CX23415) Video De... | 6     | ivtv       | AD64896794 |
| 109e:036e | 107d:6606 | Brooktree  | Bt878 Video Capture          | 5     | bttv       | 89FD130FF2 |
| 109e:036e | 11bd:0012 | Brooktree  | Bt878 Video Capture          | 5     | bttv       | 237CA98302 |
| 109e:036e | 1822:0001 | Brooktree  | Bt878 Video Capture          | 5     | bttv       | 39FB7FBFDD |
| 1131:7130 | 0000:4051 | Philips... | SAA7130 Video Broadcast D... | 5     | saa7134    | 1ABE742CC8 |
| 1131:7133 | 0070:6701 | Philips... | SAA7131/SAA7133/SAA7135 V... | 5     | saa7134    | 3CEC37B610 |
| 1131:7133 | 1043:4845 | Philips... | SAA7131/SAA7133/SAA7135 V... | 5     | saa7134    | D288F0A8CD |
| 1131:7134 | 11bd:002b | Philips... | SAA7134/SAA7135HL Video B... | 5     | saa7134    | 1756B98FF7 |
| 1131:7134 | 5ace:6072 | Philips... | SAA7134/SAA7135HL Video B... | 5     | saa7134    | DF65A1698B |
| 14f1:8800 | 0070:1402 | Conexan... | CX23880/1/2/3 PCI Video a... | 5     | cx8800     | BC782F5E67 |
| 14f1:8800 | 0070:6902 | Conexan... | CX23880/1/2/3 PCI Video a... | 5     | cx8800     | C9F48C1D32 |
| 14f1:8800 | 0070:9002 | Conexan... | CX23880/1/2/3 PCI Video a... | 5     | cx8800     | 1351C7B098 |
| 14f1:8802 | 0070:1402 | Conexan... | CX23880/1/2/3 PCI Video a... | 5     | cx8802     | BC782F5E67 |
| 14f1:8802 | 0070:6902 | Conexan... | CX23880/1/2/3 PCI Video a... | 5     | cx8802     | C9F48C1D32 |
| 14f1:8811 | 0070:1402 | Conexan... | CX23880/1/2/3 PCI Video a... | 5     | cx88_alsa  | BC782F5E67 |
| 14f1:8880 | 0070:2259 | Conexan... | CX23887/8 PCIe Broadcast ... | 5     | cx23885    | 9FB8B9219E |
| 14f1:8880 | 1461:e139 | Conexan... | CX23887/8 PCIe Broadcast ... | 5     | cx23885    | A78E4A4750 |
| 109e:036e | bd11:1200 | Brooktree  | Bt878 Video Capture          | 4     | bttv       | C7B95D7362 |
| 109e:036e | ffff:ffff | Brooktree  | Bt878 Video Capture          | 4     | bttv       | 32413546CE |
| 1131:7130 | 107d:6655 | Philips... | SAA7130 Video Broadcast D... | 4     | saa7134    | 7D25217F50 |
| 1131:7130 | 1461:2108 | Philips... | SAA7130 Video Broadcast D... | 4     | saa7134    | 61EF761A70 |
| 1131:7130 | 1461:a115 | Philips... | SAA7130 Video Broadcast D... | 4     | saa7134    | 74B6562CCD |
| 1131:7130 | 1461:a11a | Philips... | SAA7130 Video Broadcast D... | 4     | saa7134    | 0200BA924B |
| 1131:7133 | 0000:5071 | Philips... | SAA7131/SAA7133/SAA7135 V... | 4     | saa7134    | 07314F5868 |
| 1131:7133 | 1461:f936 | Philips... | SAA7131/SAA7133/SAA7135 V... | 4     | saa7134    | DA1FD4246E |
| 1131:7133 | 17de:7136 | Philips... | SAA7131/SAA7133/SAA7135 V... | 4     | saa7134    | 6AFFB516F1 |
| 1131:7133 | 5ace:6190 | Philips... | SAA7131/SAA7133/SAA7135 V... | 4     | saa7134    | D48FCDCB03 |
| 1131:7133 | 5ace:7190 | Philips... | SAA7131/SAA7133/SAA7135 V... | 4     | saa7134    | C1BD1568DC |
| 1131:7134 | 1a7f:2108 | Philips... | SAA7134/SAA7135HL Video B... | 4     | saa7134    | 8BA46DBF50 |
| 14f1:8800 | 0070:9202 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     | cx8800     | 3323601EEF |
| 14f1:8800 | 1002:a101 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     | cx8800     | DA1EA5E754 |
| 14f1:8801 | 0070:9202 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     | cx88_alsa  | 3323601EEF |
| 14f1:8801 | 1002:a101 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     | cx88_alsa  | DA1EA5E754 |
| 14f1:8802 | 0070:9202 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     | cx8802     | 3323601EEF |
| 14f1:8802 | 1002:a101 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     | cx8802     | DA1EA5E754 |
| 14f1:8811 | 0070:6902 | Conexan... | CX23880/1/2/3 PCI Video a... | 4     | cx88_alsa  | C9F48C1D32 |
| 14f1:8852 | 8000:3034 | Conexan... | CX23885 PCI Video and Aud... | 4     | cx23885    | 222D827454 |
| 109e:0350 |           | Brooktree  | Bt848 Video Capture          | 3     | bttv       | 32413546CE |

### Unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:31a2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_i... | E3073F0B11 |
| 8086:5aa2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     | intel_i... | 7ABD7A20DF |
| 13fe:1716 | 13fe:0001 | Advantech  |                              | 1     |            | 047EAD1D70 |
| 1684:0029 | 0008:0000 |            |                              | 1     |            | 3A2604A18A |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:43d5 | 1b21:1142 | AMD        | 400 Series Chipset USB 3.... | 1881  | xhci_hcd   | B2D3620851 |
| 1002:4397 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1465  | ohci_pci   | 5E80D808A1 |
| 1002:4399 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1465  | ohci_pci   | 5E80D808A1 |
| 1002:4396 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 1464  | ehci_pci   | 5E80D808A1 |
| 1022:149c | 1022:148c | AMD        | Matisse USB 3.0 Host Cont... | 1455  | xhci_hcd   | 93DE1508CB |
| 1b21:1042 | 1043:8488 | ASMedia... | ASM1042 SuperSpeed USB Ho... | 1365  | xhci_hcd   | 1BB97BC7DF |
| 1002:4396 | 1002:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 1148  | ehci_pci   | 588CEFB67B |
| 8086:1c26 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1137  | ehci_pci   | 278873FF66 |
| 8086:1c2d | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1137  | ehci_pci   | 278873FF66 |
| 8086:27c8 | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 1071  | uhci_hcd   | 4E4E73BA37 |
| 8086:27c9 | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 1071  | uhci_hcd   | 4E4E73BA37 |
| 8086:27ca | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 1070  | uhci_hcd   | 4E4E73BA37 |
| 8086:27cb | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 1069  | uhci_hcd   | 4E4E73BA37 |
| 8086:27cc | 1043:8179 | Intel      | NM10/ICH7 Family USB2 EHC... | 1055  | ehci_hc... | 4E4E73BA37 |
| 1002:4397 | 1002:4397 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 956   | ohci_pci   | 588CEFB67B |
| 1022:149c | 1043:87c0 | AMD        | Matisse USB 3.0 Host Cont... | 910   | xhci_hcd   | A525C8911B |
| 8086:8c26 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 905   | ehci_pci   | 735015DCE2 |
| 8086:8c31 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 900   | xhci_hcd   | 735015DCE2 |
| 8086:8c2d | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 894   | ehci_pci   | 735015DCE2 |
| 1002:4399 | 1002:4399 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 874   | ohci_pci   | 588CEFB67B |
| 1002:4396 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 860   | ehci_pci   | 6CA4F46D1B |
| 1002:4397 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 860   | ohci_pci   | 6CA4F46D1B |
| 1002:4398 | 1043:8389 | AMD        | SB7x0 USB OHCI1 Controller   | 858   | ohci_pci   | 6CA4F46D1B |
| 1002:4399 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 858   | ohci_pci   | 6CA4F46D1B |
| 1022:149c | 1022:1486 | AMD        | Matisse USB 3.0 Host Cont... | 838   | xhci_hcd   | 93DE1508CB |
| 8086:27c8 | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 797   | uhci_hcd   | 5AF4FEE0BA |
| 8086:27c9 | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 797   | uhci_hcd   | 5AF4FEE0BA |
| 8086:27ca | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 797   | uhci_hcd   | 5AF4FEE0BA |
| 8086:27cb | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 797   | uhci_hcd   | 5AF4FEE0BA |
| 8086:27cc | 1458:5006 | Intel      | NM10/ICH7 Family USB2 EHC... | 796   | ehci_pci   | 5AF4FEE0BA |
| 8086:1e26 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 784   | ehci_pci   | 1575E2C682 |
| 8086:1e2d | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 784   | ehci_pci   | 1575E2C682 |
| 8086:1e31 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 777   | xhci_hcd   | 1575E2C682 |
| 1002:4398 | 1458:5004 | AMD        | SB7x0 USB OHCI1 Controller   | 771   | ohci_pci   | 9CF8898973 |
| 1b21:1142 | 1043:85bf | ASMedia... | ASM1042A USB 3.0 Host Con... | 758   | xhci_hcd   | 21C683ED97 |
| 8086:a12f | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 747   | xhci_hcd   | 427C8B8D8F |
| 8086:1c26 | 1458:5006 | Intel      | 6 Series/C200 Series Chip... | 724   | ehci_pci   | 042607D7F1 |
| 8086:1c2d | 1458:5006 | Intel      | 6 Series/C200 Series Chip... | 724   | ehci_pci   | 042607D7F1 |
| 1022:43bb | 1b21:1142 | AMD        | 300 Series Chipset USB 3.... | 705   | xhci_hcd   | 3AB561BBE8 |
| 8086:3a34 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 665   | uhci_hcd   | 6C7ECC284B |
| 8086:3a35 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 665   | uhci_hcd   | 6C7ECC284B |
| 8086:3a36 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 665   | uhci_hcd   | 6C7ECC284B |
| 8086:3a37 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 665   | uhci_hcd   | 6C7ECC284B |
| 8086:3a38 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 665   | uhci_hcd   | 6C7ECC284B |
| 8086:3a39 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 665   | uhci_hcd   | 6C7ECC284B |
| 8086:3a3c | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 665   | ehci_pci   | 6C7ECC284B |
| 8086:3a3a | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 664   | ehci_pci   | 6C7ECC284B |
| 1022:149c | 1458:5007 | AMD        | Matisse USB 3.0 Host Cont... | 660   | xhci_hcd   | 6B471BC42D |
| 1022:43ee | 1b21:1142 | AMD        | Starship/Matisse USB 3.0 ... | 654   | xhci_hcd   | 82E27C0415 |
| 1022:43bc | 1b21:1142 | AMD        | FCH USB 3.1 XHCI Host Con... | 620   | xhci_hcd   | 24974BE67E |
| 1b21:1242 | 1043:8675 | ASMedia... | ASM1142 USB 3.1 Host Cont... | 613   | xhci_hcd   | 381023907E |
| 1106:3483 | 1106:3483 | VIA Tec... | VL805/806 xHCI USB 3.0 Co... | 605   | xhci_hcd   | DFA80F4B9F |
| 8086:1e26 | 1458:5006 | Intel      | 7 Series/C216 Chipset Fam... | 596   | ehci_pci   | BB6DE8B3E0 |
| 8086:1e2d | 1458:5006 | Intel      | 7 Series/C216 Chipset Fam... | 596   | ehci_pci   | BB6DE8B3E0 |
| 8086:8c31 | 1458:5007 | Intel      | 8 Series/C220 Series Chip... | 584   | xhci_hcd   | 3934A7E59D |
| 8086:8c26 | 1458:5006 | Intel      | 8 Series/C220 Series Chip... | 582   | ehci_pci   | 3934A7E59D |
| 8086:8c2d | 1458:5006 | Intel      | 8 Series/C220 Series Chip... | 582   | ehci_pci   | 3934A7E59D |
| 1b6f:7023 | 1458:5007 | Etron T... | EJ168 USB 3.0 Host Contro... | 579   | xhci_hcd   | 61D5F808B5 |
| 1106:3483 | 1458:5007 | VIA Tec... | VL805/806 xHCI USB 3.0 Co... | 564   | xhci_hcd   | C62F9B7A28 |
| 8086:1e31 | 1458:5007 | Intel      | 7 Series/C210 Series Chip... | 560   | xhci_hcd   | BB6DE8B3E0 |
| 1002:4396 | 1849:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 556   | ehci_pci   | 85B942A5C3 |
| 1002:4397 | 1849:4397 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 556   | ohci_pci   | 85B942A5C3 |
| 1002:4399 | 1849:4399 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 556   | ohci_pci   | 85B942A5C3 |
| 8086:27c8 | 1849:27c8 | Intel      | NM10/ICH7 Family USB UHCI... | 475   | uhci_hcd   | 16C678627E |
| 8086:27c9 | 1849:27c9 | Intel      | NM10/ICH7 Family USB UHCI... | 475   | uhci_hcd   | 16C678627E |
| 8086:27ca | 1849:27ca | Intel      | NM10/ICH7 Family USB UHCI... | 475   | uhci_hcd   | 16C678627E |
| 8086:27cb | 1849:27cb | Intel      | NM10/ICH7 Family USB UHCI... | 475   | uhci_hcd   | 16C678627E |
| 8086:27cc | 1849:27cc | Intel      | NM10/ICH7 Family USB2 EHC... | 474   | ehci_hc... | 16C678627E |
| 1022:7808 | 1458:5004 | AMD        | FCH USB EHCI Controller      | 461   | ehci_pci   | 2BC95C7D30 |
| 8086:a2af | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 461   | xhci_hcd   | 381023907E |
| 1033:0194 | 1043:8413 | NEC Com... | uPD720200 USB 3.0 Host Co... | 460   | xhci_hcd   | FBCB5D8594 |
| 1022:145f | 1043:8747 | AMD        | Zeppelin USB 3.0 Host con... | 459   | xhci_hcd   | 491D1A96CC |
| 1022:7807 | 1458:5004 | AMD        | FCH USB OHCI Controller      | 457   | ohci_pci   | 2BC95C7D30 |
| 1022:7809 | 1458:5004 | AMD        | FCH USB OHCI Controller      | 435   | ohci_pci   | 2BC95C7D30 |
| 1022:43d0 | 1b21:1142 | AMD        | FCH USB 3.1 XHCI Host Con... | 434   | xhci_hcd   | 93FBAD33CF |
| 8086:a2af | 1458:5007 | Intel      | 200 Series/Z370 Chipset F... | 430   | xhci_hcd   | 8C2B6CF453 |
| 10de:03f1 | 1849:03f1 | Nvidia     | MCP61 USB 1.1 Controller     | 425   | ohci_pci   | 0F23350175 |
| 10de:03f2 | 1849:03f2 | Nvidia     | MCP61 USB 2.0 Controller     | 425   | ehci_pci   | 0F23350175 |
| 8086:a12f | 1458:5007 | Intel      | 100 Series/C230 Series Ch... | 420   | xhci_hcd   | 36BF6DAB37 |
| 1106:3038 | 1106:3038 | VIA Tec... | VT82xx/62xx/VX700/8x0/900... | 416   | uhci_hcd   | CB7602A2BD |
| 1106:3104 | 1106:3104 | VIA Tec... | USB 2.0 EHCI-Compliant Ho... | 412   | ehci_pci   | CB7602A2BD |
| 1022:43b9 | 1b21:1142 | AMD        | X370 Series Chipset USB 3... | 383   | xhci_hcd   | 3ABF73FB8A |
| 1022:7807 | 1849:7807 | AMD        | FCH USB OHCI Controller      | 383   | ohci_pci   | 42CD4D28BD |
| 1022:7808 | 1849:7808 | AMD        | FCH USB EHCI Controller      | 383   | ehci_pci   | 42CD4D28BD |
| 8086:2934 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 380   | uhci_hcd   | 80ADFF7646 |
| 8086:2935 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 380   | uhci_hcd   | 80ADFF7646 |
| 8086:2936 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 380   | uhci_hcd   | 80ADFF7646 |
| 8086:2937 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 380   | uhci_hcd   | 80ADFF7646 |
| 8086:2938 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 380   | uhci_hcd   | 80ADFF7646 |
| 8086:2939 | 1043:8277 | Intel      | 82801I (ICH9 Family) USB ... | 380   | uhci_hcd   | 80ADFF7646 |
| 8086:293a | 1043:8277 | Intel      | 82801I (ICH9 Family) USB2... | 380   | ehci_hc... | 80ADFF7646 |
| 8086:293c | 1043:8277 | Intel      | 82801I (ICH9 Family) USB2... | 380   | ehci_hc... | 80ADFF7646 |
| 1022:145c | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 375   | xhci_hcd   | F20F2BFC32 |
| 1022:145f | 1458:5007 | AMD        | Zeppelin USB 3.0 Host con... | 374   | xhci_hcd   | E52E9002D0 |
| 8086:a36d | 1043:8694 | Intel      | Cannon Lake PCH USB 3.1 x... | 374   | xhci_hcd   | 22A32FC3F2 |
| 1022:7809 | 1849:7809 | AMD        | FCH USB OHCI Controller      | 349   | ohci_pci   | 42CD4D28BD |
| 1022:15e0 | 1458:5007 | AMD        | Raven USB 3.1                | 333   | xhci_hcd   | B2D3620851 |
| 1022:15e1 | 1458:5007 | AMD        | Raven USB 3.1                | 333   | xhci_hcd   | B2D3620851 |
| 8086:8ca6 | 1043:8534 | Intel      | 9 Series Chipset Family U... | 329   | ehci_pci   | 5A5D3A54C3 |
| 8086:8cb1 | 1043:8534 | Intel      | 9 Series Chipset Family U... | 326   | xhci_hcd   | 5A5D3A54C3 |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8d7c | 1043:8600 | Intel      | C610/X99 series chipset SPSR | 114   |            | D3A4772E4E |
| 8086:8d7c | 8086:7270 | Intel      | C610/X99 series chipset SPSR | 76    |            | 17B2218DAB |
| 8086:8d7c | 1458:7270 | Intel      | C610/X99 series chipset SPSR | 44    |            | 347D6DF600 |
| 8086:8d7c | 1849:8d7c | Intel      | C610/X99 series chipset SPSR | 42    |            | 2BF61F2EC6 |
| 8086:8d7c | 103c:212b | Intel      | C610/X99 series chipset SPSR | 39    |            | 9D2A807F08 |
| 8086:8d7c | 1462:7885 | Intel      | C610/X99 series chipset SPSR | 36    |            | 90189BED4E |
| 8086:8d7c | 1028:0617 | Intel      | C610/X99 series chipset SPSR | 34    |            | 6EBA24CF71 |
| 10ec:816e | 10ec:8168 | Realtek... | RealManage BMC               | 23    |            | 07A5B3C465 |
| 1af2:a001 | 1af2:a001 | AVerMedia  | Live Gamer HD                | 16    |            | 8D2D37223F |
| 8086:8d7c | 1043:85f6 | Intel      | C610/X99 series chipset SPSR | 15    |            | 2591B8710E |
| 8086:8d7c | 1028:0618 | Intel      | C610/X99 series chipset SPSR | 13    |            | 0E22588D46 |
| 8086:8d7c | 103c:2129 | Intel      | C610/X99 series chipset SPSR | 10    |            | 8DE5BAE655 |
| 8086:8d7c | 1028:0619 | Intel      | C610/X99 series chipset SPSR | 9     |            | 36E6C22CC6 |
| 8086:8d7c | 17aa:102f | Intel      | C610/X99 series chipset SPSR | 8     |            | B6ECA9083A |
| 8086:8d7c | 1028:061b | Intel      | C610/X99 series chipset SPSR | 7     |            | BCD33A41F0 |
| 8086:8d7c | 1028:064c | Intel      | C610/X99 series chipset SPSR | 6     |            | E31C5F36AA |
| 8086:8d7c | 103c:212a | Intel      | C610/X99 series chipset SPSR | 5     |            | 7F51E384F7 |
| 8086:8d7c | 15d9:0836 | Intel      | C610/X99 series chipset SPSR | 5     |            | 078AB4C114 |
| 8086:8d7c | 1734:1201 | Intel      | C610/X99 series chipset SPSR | 5     |            | 081130AC6F |
| 8086:6ff2 | 8086:6ff2 | Intel      | Broadwell-E CBo Unicast R... | 4     |            | 3DB5DD7EA0 |
| 8086:6ff3 | 8086:6ff3 | Intel      | Broadwell-E CBo Unicast R... | 4     |            | 3DB5DD7EA0 |
| 8086:8d7c | 1462:7883 | Intel      | C610/X99 series chipset SPSR | 3     |            | 64A313C9E3 |
| 8086:8d7c | 1462:7a20 | Intel      | C610/X99 series chipset SPSR | 3     |            | B5DCAF3853 |
| 8086:8d7c | 15d9:0844 | Intel      | C610/X99 series chipset SPSR | 3     |            | 57BA944640 |
| 8086:8d7c | 15d9:0852 | Intel      | C610/X99 series chipset SPSR | 3     |            | 9EFBA142DD |
| 8086:a1ec | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 3     |            | 23D528F392 |
| 8086:a1ed | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 3     |            | 23D528F392 |
| 106b:003b |           | Apple      | UniNorth/Intrepid ATA/100    | 2     | pata_pc... | 711599EA49 |
| 106b:003e |           | Apple      | KeyLargo/Intrepid Mac I/O    | 2     | macio      | 711599EA49 |
| 1274:5880 | ffff:ffff | Ensoniq    | 5880B / Creative Labs CT5880 | 2     | snd_ens... | CC0925A796 |
| 8086:3591 | 1028:0173 | Intel      | E7525/E7520 Error Reporti... | 2     |            | CB7602A2BD |
| 8086:3591 | 1043:8145 | Intel      | E7525/E7520 Error Reporti... | 2     |            | C6EF12178F |
| 8086:6ff4 | 8086:6ff4 | Intel      | Broadwell-E CBo Unicast R... | 2     |            | D6444EBF26 |
| 8086:6ff5 | 8086:6ff5 | Intel      | Broadwell-E CBo Unicast R... | 2     |            | D6444EBF26 |
| 8086:8d7c | 103c:8030 | Intel      | C610/X99 series chipset SPSR | 2     |            | D9B1EC3C37 |
| 8086:8d7c | 1462:7a21 | Intel      | C610/X99 series chipset SPSR | 2     |            | 6FAF6514F5 |
| 8086:8d7c | 1462:7a54 | Intel      | C610/X99 series chipset SPSR | 2     |            | 8A1C74B101 |
| 8086:8d7c | 15d9:0833 | Intel      | C610/X99 series chipset SPSR | 2     |            | 115F0BC999 |
| 8086:8d7c | 17aa:1030 | Intel      | C610/X99 series chipset SPSR | 2     |            | A06764AF07 |
| 8086:a1ec | 1028:0739 | Intel      | C620 Series Chipset Famil... | 2     |            | E477AB6481 |
| 8086:a1ec | 1043:871e | Intel      | C620 Series Chipset Famil... | 2     |            | 177BF1F346 |
| 8086:a1ed | 1028:0739 | Intel      | C620 Series Chipset Famil... | 2     |            | E477AB6481 |
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
| 106b:0041 |           | Apple      | K2 KeyLargo Mac/IO           | 1     | macio      | 52B4B037A1 |
| 106b:0043 |           | Apple      | K2 ATA/100                   | 1     | pata_pc... | 52B4B037A1 |
| 106b:004f |           | Apple      | Shasta Mac I/O               | 1     | macio      | 978FCB3A51 |
| 106b:0050 |           | Apple      | Shasta IDE                   | 1     | ide_pmac   | 978FCB3A51 |
| 1093:2a70 |           | Nationa... | PCI-6024E                    | 1     | ni_pcimio  | FB5BC9ACCE |
| 1095:3132 | ffff:ffff | Silicon... | SiI 3132 Serial ATA Raid ... | 1     | sata_sil24 | E5B47E2D75 |
| 10b5:2091 | 10b5:9050 | PLX Tec... |                              | 1     |            | 76A903635A |
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
| 17b6:0229 | 17b6:0000 | GE Medi... |                              | 1     |            | 9844591CD4 |
| 17b6:2000 | 17b6:0003 | GE Medi... |                              | 1     |            | 71678F1D6B |
| 1931:1011 | 1003:0001 | Option ... |                              | 1     |            | 28DFB478B7 |
| 1931:1011 | 1043:0001 | Option ... |                              | 1     |            | 28DFB478B7 |
| 1b21:1042 | ffff:ffff | ASMedia... | ASM1042 SuperSpeed USB Ho... | 1     |            | 03FD0C20FB |
| 1b6f:7023 | 0000:ffff | Etron T... | EJ168 USB 3.0 Host Contro... | 1     |            | 4D09439EF7 |
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

