Most popular PCI devices
========================

This is a project to identify most popular PCI devices in modern computers and
share detailed lspci reports collected by Linux users at https://linux-hardware.org.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Total reports: 179807.

Contents
--------

1. [ About ](#about)
2. [ PCI Devices ](#pci-devices)
   * [ Bluetooth ](#bluetooth-pci)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Dma controller (eisa dma) ](#dma-controller-eisa-dma-pci)
   * [ Dvb card ](#dvb-card-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Firewire controller ](#firewire-controller-pci)
   * [ Flash memory ](#flash-memory-pci)
   * [ Generic system peripheral ](#generic-system-peripheral-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Input device controller ](#input-device-controller-pci)
   * [ Iommu ](#iommu-pci)
   * [ Ipmi interface (kcs) ](#ipmi-interface-kcs-pci)
   * [ Ipmi smic interface ](#ipmi-smic-interface-pci)
   * [ Isdn adapter ](#isdn-adapter-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Modem ](#modem-pci)
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

About
-----

The structure of the repository is the following:

    {COMPUTER TYPE}/{VENDOR}/{MODEL PREFIX}/{MODEL}/{HWID}/{OS}/{KERNEL}/{ARCH}/{PROBE ID}

    ( e.g. Notebook/Lenovo/ThinkPad/ThinkPad W540/376C44AF6B85/DEBIAN-9.1/4.9.0-3-AMD64/X86_64/F51B828085 )

You can find appropriate lspci report in this repository by a probe ID as follows:

    find . -name {PROBE ID}

PCI Devices
-----------

Top 100 most popular devices in each category.

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bluetooth (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1814:3298 | 103c:18ec | Ralink     | RT3290 Bluetooth             | 496   | rtbth      | BDAEE2E27B |
| 1814:3298 | 105b:e056 | Ralink     | RT3290 Bluetooth             | 104   | rtbth      | 1416BA31A9 |
| 1814:3298 | 103c:191c | Ralink     | RT3290 Bluetooth             | 23    | rtbth      | 43B7FFE89B |
| 1814:3298 | 1a3b:2787 | Ralink     | RT3290 Bluetooth             | 13    |            | A583282400 |
| 1814:3298 | 1a3b:2f87 | Ralink     | RT3290 Bluetooth             | 12    |            | E60E072319 |
| 1814:3298 | 1a3b:2987 | Ralink     | RT3290 Bluetooth             | 6     |            | 121F403E29 |
| 1814:3298 | 1814:3298 | Ralink     | RT3290 Bluetooth             | 5     |            | AAC37423E5 |
| 1814:3298 | 10cf:1772 | Ralink     | RT3290 Bluetooth             | 1     |            | 1135E21142 |
| 1814:3298 | 1a3b:210b | Ralink     | RT3290 Bluetooth             | 1     |            | 2333E930AF |

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:4384 |           | AMD        | SBx00 PCI to PCI Bridge      | 6734  | shpchp     | 77FCB9CF4A |
| 1022:1452 |           | AMD        | Family 17h (Models 00h-1f... | 5074  |            | F504E72617 |
| 1022:1200 |           | AMD        | Family 10h Processor Hype... | 3936  |            | 4F82621017 |
| 1022:1201 |           | AMD        | Family 10h Processor Addr... | 3936  |            | 4F82621017 |
| 1022:1202 |           | AMD        | Family 10h Processor DRAM... | 3936  | amd64_e... | 4F82621017 |
| 1022:1203 |           | AMD        | Family 10h Processor Misc... | 3936  | k10temp    | 4F82621017 |
| 1022:1204 |           | AMD        | Family 10h Processor Link... | 3936  |            | 4F82621017 |
| 1022:780f |           | AMD        | FCH PCI Bridge               | 3037  | shpchp     | 8961CA91B3 |
| 1022:15e8 |           | AMD        | Raven/Raven2 Device 24: F... | 2760  |            | F504E72617 |
| 1022:15e9 |           | AMD        | Raven/Raven2 Device 24: F... | 2760  |            | F504E72617 |
| 1022:15ea |           | AMD        | Raven/Raven2 Device 24: F... | 2760  |            | F504E72617 |
| 1022:15eb |           | AMD        | Raven/Raven2 Device 24: F... | 2760  | k10temp    | F504E72617 |
| 1022:15ec |           | AMD        | Raven/Raven2 Device 24: F... | 2760  |            | F504E72617 |
| 1022:15ed |           | AMD        | Raven/Raven2 Device 24: F... | 2760  |            | F504E72617 |
| 1022:15ee |           | AMD        | Raven/Raven2 Device 24: F... | 2760  |            | F504E72617 |
| 1022:15ef |           | AMD        | Raven/Raven2 Device 24: F... | 2760  |            | F504E72617 |
| 1022:1460 |           | AMD        | Family 17h (Models 00h-0f... | 2317  |            | D88D9DB618 |
| 1022:1461 |           | AMD        | Family 17h (Models 00h-0f... | 2317  |            | D88D9DB618 |
| 1022:1462 |           | AMD        | Family 17h (Models 00h-0f... | 2317  |            | D88D9DB618 |
| 1022:1463 |           | AMD        | Family 17h (Models 00h-0f... | 2317  | k10temp    | D88D9DB618 |
| 1022:1464 |           | AMD        | Family 17h (Models 00h-0f... | 2317  |            | D88D9DB618 |
| 1022:1465 |           | AMD        | Family 17h (Models 00h-0f... | 2317  |            | D88D9DB618 |
| 1022:1466 |           | AMD        | Family 17h (Models 00h-0f... | 2317  |            | D88D9DB618 |
| 1022:1467 |           | AMD        | Family 17h (Models 00h-0f... | 2317  |            | D88D9DB618 |
| 1022:1600 |           | AMD        | Family 15h Processor Func... | 2223  |            | 77FCB9CF4A |
| 1022:1601 |           | AMD        | Family 15h Processor Func... | 2223  |            | 77FCB9CF4A |
| 1022:1602 |           | AMD        | Family 15h Processor Func... | 2223  |            | 77FCB9CF4A |
| 1022:1603 |           | AMD        | Family 15h Processor Func... | 2223  | k10temp    | 77FCB9CF4A |
| 1022:1604 |           | AMD        | Family 15h Processor Func... | 2223  | fam15h_... | 77FCB9CF4A |
| 1022:1605 |           | AMD        | Family 15h Processor Func... | 2223  |            | 77FCB9CF4A |
| 1022:15db | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 2214  | pcieport   | F504E72617 |
| 1022:1100 |           | AMD        | K8 [Athlon64/Opteron] Hyp... | 2196  |            | D38F5B09D2 |
| 1022:1101 |           | AMD        | K8 [Athlon64/Opteron] Add... | 2196  |            | D38F5B09D2 |
| 1022:1102 |           | AMD        | K8 [Athlon64/Opteron] DRA... | 2196  | amd64_e... | D38F5B09D2 |
| 1022:1103 |           | AMD        | K8 [Athlon64/Opteron] Mis... | 2196  | k8temp     | D38F5B09D2 |
| 1002:439d | 1002:439d | AMD        | SB7x0/SB8x0/SB9x0 LPC hos... | 2185  |            | 77FCB9CF4A |
| 1022:1482 |           | AMD        | Starship/Matisse PCIe Dum... | 2183  | vfio_pci   | 97C17F738A |
| 1022:43c7 | 1b21:3306 | AMD        | 400 Series Chipset PCIe Port | 2115  | pcieport   | 97C17F738A |
| 1022:1440 |           | AMD        | Matisse Device 24: Functi... | 2097  |            | 97C17F738A |
| 1022:1441 |           | AMD        | Matisse Device 24: Functi... | 2097  |            | 97C17F738A |
| 1022:1442 |           | AMD        | Matisse Device 24: Functi... | 2097  |            | 97C17F738A |
| 1022:1443 |           | AMD        | Matisse Device 24: Functi... | 2097  | k10temp    | 97C17F738A |
| 1022:1444 |           | AMD        | Matisse Device 24: Functi... | 2097  |            | 97C17F738A |
| 1022:1445 |           | AMD        | Matisse Device 24: Functi... | 2097  |            | 97C17F738A |
| 1022:1446 |           | AMD        | Matisse Device 24: Functi... | 2097  |            | 97C17F738A |
| 1022:1447 |           | AMD        | Matisse Device 24: Functi... | 2097  |            | 97C17F738A |
| 8086:2d01 | 8086:8086 | Intel      | Core Processor QuickPath ... | 2073  |            | 9635709179 |
| 8086:2d10 | 8086:8086 | Intel      | Core Processor QPI Link 0    | 2073  |            | 9635709179 |
| 8086:2d11 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 2073  |            | 9635709179 |
| 8086:2d12 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 2073  |            | 9635709179 |
| 8086:2d13 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 2073  |            | 9635709179 |
| 1022:43c6 | 1b21:0201 | AMD        | 400 Series Chipset PCIe B... | 1898  | pcieport   | 97C17F738A |
| 1002:43a0 | 1002:0000 | AMD        | SB700/SB800/SB900 PCI to ... | 1886  | pcieport   | 9F527DED3C |
| 1022:43b4 | 1b21:3306 | AMD        | 300 Series Chipset PCIe Port | 1789  | pcieport   | F544511E0A |
| 1022:1700 |           | AMD        | Family 12h/14h Processor ... | 1769  |            | 0E94F2AD8F |
| 1022:1701 |           | AMD        | Family 12h/14h Processor ... | 1769  |            | 0E94F2AD8F |
| 1022:1702 |           | AMD        | Family 12h/14h Processor ... | 1769  |            | 0E94F2AD8F |
| 1022:1703 |           | AMD        | Family 12h/14h Processor ... | 1769  | k10temp    | 0E94F2AD8F |
| 1022:1704 |           | AMD        | Family 12h/14h Processor ... | 1769  |            | 0E94F2AD8F |
| 1022:1716 |           | AMD        | Family 12h/14h Processor ... | 1769  |            | 0E94F2AD8F |
| 1022:1718 |           | AMD        | Family 12h/14h Processor ... | 1769  |            | 0E94F2AD8F |
| 1022:1719 |           | AMD        | Family 12h/14h Processor ... | 1769  |            | 0E94F2AD8F |
| 1022:15dc | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 1729  | pcieport   | F504E72617 |
| 1022:1454 | 1022:1454 | AMD        | Family 17h (Models 00h-0f... | 1640  | pcieport   | D88D9DB618 |
| 1022:1484 | 1022:1484 | AMD        | Starship/Matisse Internal... | 1606  | pcieport   | 97C17F738A |
| 1022:15d3 | 1022:1453 | AMD        | Raven/Raven2 PCIe GPP Bri... | 1590  | pcieport   | F504E72617 |
| 8086:2c62 | 8086:8086 | Intel      | Core Processor QuickPath ... | 1575  |            | 9635709179 |
| 8086:244e | 1458:5000 | Intel      | 82801 PCI Bridge             | 1572  |            | 43A5D97DD3 |
| 1022:1400 |           | AMD        | Family 15h (Models 10h-1f... | 1493  |            | E03FD39AD4 |
| 1022:1401 |           | AMD        | Family 15h (Models 10h-1f... | 1493  |            | E03FD39AD4 |
| 1022:1402 |           | AMD        | Family 15h (Models 10h-1f... | 1493  |            | E03FD39AD4 |
| 1022:1403 |           | AMD        | Family 15h (Models 10h-1f... | 1493  | k10temp    | E03FD39AD4 |
| 1022:1404 |           | AMD        | Family 15h (Models 10h-1f... | 1493  |            | E03FD39AD4 |
| 1022:1405 |           | AMD        | Family 15h (Models 10h-1f... | 1493  |            | E03FD39AD4 |
| 1022:43a0 | 1022:0000 | AMD        | Hudson PCI to PCI bridge ... | 1433  | pcieport   | 8961CA91B3 |
| 1b21:1080 | 1043:8489 | ASMedia... | ASM1083/1085 PCIe to PCI ... | 1403  | shpchp     | 11EBF0D551 |
| 1022:15d0 | 1022:15d0 | AMD        | Raven/Raven2 Root Complex    | 1352  | k10temp    | F504E72617 |
| 1022:790e | 1458:5001 | AMD        | FCH LPC Bridge               | 1352  |            | F544511E0A |
| 1022:1453 | 1022:1453 | AMD        | Family 17h (Models 00h-0f... | 1318  | pcieport   | D88D9DB618 |
| 1022:157b |           | AMD        | Family 15h (Models 60h-6f... | 1305  |            | FC5CE69792 |
| 1022:157d |           | AMD        | Carrizo Audio Dummy Host ... | 1305  |            | FC5CE69792 |
| 1002:5a14 | 1002:5a14 | AMD        | RD9x0/RX980 Host Bridge      | 1124  | ati_agp    | 77FCB9CF4A |
| 1002:5a16 | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 1092  | pcieport   | 77FCB9CF4A |
| 8086:0c01 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 1078  | pcieport   | 9A23DF55D8 |
| 1022:57ad |           | AMD        | Matisse Switch Upstream      | 1068  | pcieport   | 0619809B36 |
| 8086:0c00 | 1043:8534 | Intel      | 4th Gen Core Processor DR... | 1068  | hsw_uncore | 9A23DF55D8 |
| 8086:244e |           | Intel      | 82801 PCI Bridge             | 1060  | shpchp     | CD3697BD15 |
| 8086:1901 | 1043:8694 | Intel      | 6th-10th Gen Core Process... | 1048  | pcieport   | 11EBF0D551 |
| 1002:5a18 | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 1029  | pcieport   | 77FCB9CF4A |
| 1022:1632 |           | AMD        | Renoir PCIe Dummy Host Br... | 1017  |            | 6B6205BC5D |
| 8086:1c10 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1012  | shpchp     | EA164260EB |
| 8086:2448 |           | Intel      | 82801 Mobile PCI Bridge      | 1011  | shpchp     | 65FBD3DEF4 |
| 8086:244e | 1043:8179 | Intel      | 82801 PCI Bridge             | 1001  |            | 5889B752F5 |
| 8086:27b8 | 1043:8179 | Intel      | 82801GB/GR (ICH7 Family) ... | 1000  | lpc_ich    | 5889B752F5 |
| 1022:1448 |           | AMD        | Renoir Device 24: Function 0 | 998   |            | 6B6205BC5D |
| 1022:1449 |           | AMD        | Renoir Device 24: Function 1 | 998   |            | 6B6205BC5D |
| 1022:144a |           | AMD        | Renoir Device 24: Function 2 | 998   |            | 6B6205BC5D |
| 1022:144b |           | AMD        | Renoir Device 24: Function 3 | 998   | k10temp    | 6B6205BC5D |
| 1022:144c |           | AMD        | Renoir Device 24: Function 4 | 998   |            | 6B6205BC5D |
| 1022:144d |           | AMD        | Renoir Device 24: Function 5 | 998   |            | 6B6205BC5D |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:5287 | 1043:202f | Realtek... | RTL8411B PCI Express Card... | 254   | rtsx_pci   | 13FF923546 |
| 10ec:5286 | 1043:202f | Realtek... | RTL8402 Integrated 1-LUN ... | 214   | rtsx_pci   | DCD714D5FA |
| 10ec:5289 | 1043:202f | Realtek... | RTL8411 PCI Express Card ... | 159   | rtsx_pci   | 08930695BC |
| 10ec:5286 | 10ec:5286 | Realtek... | RTL8402 Integrated 1-LUN ... | 143   | rtsx_pci   | 208FC3F30F |
| 10ec:522a | 8086:2074 | Realtek... | RTS522A PCI Express Card ... | 114   | rtsx_pci   | 7CA350189C |
| 10ec:525a | 1028:0905 | Realtek... | RTS525A PCI Express Card ... | 112   | rtsx_pci   | 9CDE952049 |
| 10ec:5229 | 1043:202f | Realtek... | RTS5229 PCI Express Card ... | 111   | rtsx_pci   | 5C45DFB686 |
| 10ec:5289 | 10ec:5289 | Realtek... | RTL8411 PCI Express Card ... | 108   | rtsx_pci   | 1FD5FA69E2 |
| 10ec:5227 | 17aa:220c | Realtek... | RTS5227 PCI Express Card ... | 107   | rtsx_pci   | 4C600416F9 |
| 10ec:5287 | 1025:1193 | Realtek... | RTL8411B PCI Express Card... | 105   | rtsx_pci   | E922639FF6 |
| 10ec:5287 | 1025:0866 | Realtek... | RTL8411B PCI Express Card... | 103   | rtsx_pci   | 58B4832D53 |
| 10ec:525a | 1028:087c | Realtek... | RTS525A PCI Express Card ... | 97    | rtsx_pci   | 31A6F21CCD |
| 10ec:5227 | 103c:198f | Realtek... | RTS5227 PCI Express Card ... | 96    | rtsx_pci   | 6573923D55 |
| 10ec:5227 | 17aa:220e | Realtek... | RTS5227 PCI Express Card ... | 95    | rtsx_pci   | 4EC9EAAC2F |
| 10ec:522a | 10ec:522a | Realtek... | RTS522A PCI Express Card ... | 95    | rtsx_pci   | ECC7F6B940 |
| 10ec:5209 | 104d:908b | Realtek... | RTS5209 PCI Express Card ... | 93    | rtsx_pci   | F88D733F75 |
| 10ec:522a | 103c:8079 | Realtek... | RTS522A PCI Express Card ... | 93    | rtsx_pci   | 0FA8058EEB |
| 10ec:5287 | 1025:1094 | Realtek... | RTL8411B PCI Express Card... | 92    | rtsx_pci   | 9756CE58FC |
| 10ec:5229 | 10ec:5229 | Realtek... | RTS5229 PCI Express Card ... | 90    | rtsx_pci   | DD885000B5 |
| 10ec:5227 | 17aa:5034 | Realtek... | RTS5227 PCI Express Card ... | 87    | rtsx_pci   | 6131E3C22A |
| 10ec:5229 | 17aa:3808 | Realtek... | RTS5229 PCI Express Card ... | 86    | rtsx_pci   | BAC9935F0B |
| 10ec:522a | 17aa:5082 | Realtek... | RTS522A PCI Express Card ... | 84    | rtsx_pci   | 6B6205BC5D |
| 10ec:525a | 1028:07e6 | Realtek... | RTS525A PCI Express Card ... | 81    | rtsx_pci   | C2E884F793 |
| 10ec:5209 | 1025:0685 | Realtek... | RTS5209 PCI Express Card ... | 80    | rtsx_pci   | 03831239E1 |
| 10ec:525a | 1028:08af | Realtek... | RTS525A PCI Express Card ... | 80    | rtsx_pci   | 80857F497B |
| 10ec:5229 | 103c:1854 | Realtek... | RTS5229 PCI Express Card ... | 78    | rtsx_pci   | 21FB6389E7 |
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
| 10ec:5287 | 10ec:5287 | Realtek... | RTL8411B PCI Express Card... | 62    | rtsx_pci   | 4FCC4FBCB8 |
| 10ec:5229 | 10cf:176b | Realtek... | RTS5229 PCI Express Card ... | 60    | rtsx_pci   | B2D4A08D24 |
| 10ec:525a | 1028:081c | Realtek... | RTS525A PCI Express Card ... | 59    | rtsx_pci   | A92377CB2A |
| 10ec:5249 | 17aa:3801 | Realtek... | RTS5249 PCI Express Card ... | 58    | rtsx_pci   | CC68265730 |
| 10ec:5229 | 8086:2068 | Realtek... | RTS5229 PCI Express Card ... | 56    | rtsx_pci   | 38D5C55BD7 |
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
| 10ec:5229 | 17aa:3832 | Realtek... | RTS5229 PCI Express Card ... | 48    | rtsx_pci   | EF40B26D84 |
| 10ec:5209 | 1025:0590 | Realtek... | RTS5209 PCI Express Card ... | 47    | rtsx_pci   | 1AB9A823AC |
| 10ec:5229 | 103c:183e | Realtek... | RTS5229 PCI Express Card ... | 47    | rtsx_pci   | 03F3D2F19B |
| 10ec:522a | 17aa:2279 | Realtek... | RTS522A PCI Express Card ... | 47    | rtsx_pci   | 81BBBC9593 |
| 10ec:522a | 17aa:5053 | Realtek... | RTS522A PCI Express Card ... | 47    | rtsx_pci   | 6B9264BFE9 |
| 1aea:6625 | 103c:8478 | Alcor M... | AU6625 PCI-E Flash card r... | 47    | alcor_pci  | D3A001E377 |
| 10ec:5209 | 103c:1670 | Realtek... | RTS5209 PCI Express Card ... | 45    | rtsx_pci   | 0245DA9040 |
| 10ec:5229 | 103c:1818 | Realtek... | RTS5229 PCI Express Card ... | 44    | rtsx_pci   | B9FD7914E2 |
| 10ec:525a | 1028:087d | Realtek... | RTS525A PCI Express Card ... | 44    | rtsx_pci   | A5C63380D6 |
| 10ec:5229 | 1179:f840 | Realtek... | RTS5229 PCI Express Card ... | 43    | rtsx_pci   | 6B411D236A |
| 10ec:525a | 17aa:2238 | Realtek... | RTS525A PCI Express Card ... | 43    | rtsx_pci   | CAD013A6A5 |
| 10ec:5289 | 1043:1457 | Realtek... | RTL8411 PCI Express Card ... | 43    | rtsx_pci   | 87C1F4A491 |
| 10ec:5229 | 17aa:5000 | Realtek... | RTS5229 PCI Express Card ... | 42    | rtsx_pci   | 9F605297CB |
| 10ec:525a | 1028:06dc | Realtek... | RTS525A PCI Express Card ... | 42    | rtsx_pci   | FFDB13EDA0 |
| 10ec:522a | 103c:8730 | Realtek... | RTS522A PCI Express Card ... | 41    | rtsx_pci   | FC1870A101 |
| 10ec:5229 | 103c:1858 | Realtek... | RTS5229 PCI Express Card ... | 40    | rtsx_pci   | 710FDCA60A |
| 10ec:5209 | 1025:0781 | Realtek... | RTS5209 PCI Express Card ... | 39    | rtsx_pci   | 011928039E |
| 10ec:5227 | 17aa:5028 | Realtek... | RTS5227 PCI Express Card ... | 39    | rtsx_pci   | 4BED2E361F |
| 10ec:522a | 17aa:380e | Realtek... | RTS522A PCI Express Card ... | 39    | rtsx_pci   | CC7CB4A34E |
| 10ec:525a | 1028:0906 | Realtek... | RTS525A PCI Express Card ... | 39    | rtsx_pci   | 2B4444A6FA |
| 10ec:5260 | 1028:0991 | Realtek... | RTS5260 PCI Express Card ... | 39    | rtsx_pci   | 089BB7C152 |
| 10ec:5287 | 1025:108f | Realtek... | RTL8411B PCI Express Card... | 39    | rtsx_pci   | D0C45F9B31 |
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

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0aa3 | 10de:cb79 | Nvidia     | MCP79 Co-processor           | 202   | nvidia     | F982A2F6CC |
| 10de:0d7a | 10de:cb89 | Nvidia     | MCP89 Co-Processor           | 75    |            | E3121B6209 |
| 10de:0753 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Co-... | 62    |            | 739D1AE9B7 |
| 10de:0753 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] Co-... | 53    |            | 67C143DFE9 |
| 10de:03f4 | 1462:7597 | Nvidia     | MCP61 SMU                    | 37    |            | 6F22F99F9F |
| 10de:0753 | 1849:0753 | Nvidia     | MCP78S [GeForce 8200] Co-... | 35    |            | 9B0A7F242B |
| 10de:03f4 | 1462:7309 | Nvidia     | MCP61 SMU                    | 34    |            | 78A89AB514 |
| 10de:0543 | 103c:30cf | Nvidia     | MCP67 Co-processor           | 32    |            | CB77A79EE8 |
| 10de:0543 | 1025:0126 | Nvidia     | MCP67 Co-processor           | 31    |            | AA6D721BF2 |
| 10de:0aa3 | 1043:1cf7 | Nvidia     | MCP79 Co-processor           | 25    | nvidia     | 7A84F17BDB |
| 10de:0aa3 | 1043:1fa7 | Nvidia     | MCP79 Co-processor           | 24    | nvidia     | B0BCC6C31C |
| 10de:0753 | 1043:82e2 | Nvidia     | MCP78S [GeForce 8200] Co-... | 20    |            | 4B4D8AA09F |
| 10de:0271 | 103c:30b7 | Nvidia     | MCP51 PMU                    | 19    |            | C28788427E |
| 10de:0aa3 | 1043:1d17 | Nvidia     | MCP79 Co-processor           | 18    | nvidia     | F1573DB462 |
| 10de:0aa3 | 1025:0222 | Nvidia     | MCP79 Co-processor           | 13    | nvidia     | 093D03CAF5 |
| 10de:0543 | 1043:16a7 | Nvidia     | MCP67 Co-processor           | 12    |            | 414786C3D5 |
| 10de:07da | 1025:0137 | Nvidia     | MCP73 Co-processor           | 12    |            | 8533331911 |
| 10de:0447 | 103c:30cf | Nvidia     | MCP65 SMU                    | 11    |            | D7BE62BFCB |
| 10de:0753 | 1025:0153 | Nvidia     | MCP78S [GeForce 8200] Co-... | 11    |            | 94CDE50175 |
| 10de:0aa3 | 1043:8402 | Nvidia     | MCP79 Co-processor           | 11    | nvidia     | 07474931C9 |
| 10de:0271 | 1025:0112 | Nvidia     | MCP51 PMU                    | 10    |            | 56639ACA29 |
| 10de:03f4 |           | Nvidia     | MCP61 SMU                    | 10    |            | 1D4F1E8E8B |
| 10de:0753 | 1025:0228 | Nvidia     | MCP78S [GeForce 8200] Co-... | 10    |            | 08681C1E94 |
| 10de:0753 | 1043:82e8 | Nvidia     | MCP78S [GeForce 8200] Co-... | 10    |            | 9DAF1B6529 |
| 10de:03f4 | 1043:8234 | Nvidia     | MCP61 SMU                    | 9     |            | 56DB54E530 |
| 10de:0543 | 1849:0543 | Nvidia     | MCP67 Co-processor           | 9     |            | 1C6B15BC7B |
| 10de:0aa3 | 1462:7621 | Nvidia     | MCP79 Co-processor           | 9     | nvidia     | 9D7D398CC1 |
| 10de:0aa3 | 1025:0168 | Nvidia     | MCP79 Co-processor           | 8     | nvidia     | 547C1BF7D7 |
| 10de:0aa3 | 103c:3651 | Nvidia     | MCP79 Co-processor           | 8     | nvidia     | A29E32B5FB |
| 10de:0aa3 | 1462:1012 | Nvidia     | MCP79 Co-processor           | 8     | nvidia     | B1D00D1444 |
| 10de:0753 | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] Co-... | 7     |            | 04B8123AA5 |
| 10de:0753 | 103c:2a81 | Nvidia     | MCP78S [GeForce 8200] Co-... | 7     |            | 97B60B69C9 |
| 10de:0753 | 1043:82e7 | Nvidia     | MCP78S [GeForce 8200] Co-... | 7     |            | 6AA0488E7E |
| 10de:0753 | 1565:340b | Nvidia     | MCP78S [GeForce 8200] Co-... | 7     |            | 4F82621017 |
| 10de:0aa3 | 1b0a:0074 | Nvidia     | MCP79 Co-processor           | 7     | nvidia     | 484AF2A752 |
| 10de:0543 | 103c:30d6 | Nvidia     | MCP67 Co-processor           | 6     |            | D6DADC467D |
| 10de:0543 | 103c:30ea | Nvidia     | MCP67 Co-processor           | 6     |            | 1CEE50E485 |
| 10de:0753 | 1462:6720 | Nvidia     | MCP78S [GeForce 8200] Co-... | 6     |            | C630018FEA |
| 10de:0aa3 | 1025:0160 | Nvidia     | MCP79 Co-processor           | 6     | nvidia     | 08C92ED6C5 |
| 10de:0271 | 103c:30b5 | Nvidia     | MCP51 PMU                    | 5     |            | EFFFE561DA |
| 10de:0271 | 103c:30bf | Nvidia     | MCP51 PMU                    | 5     |            | BAD7484C1A |
| 10de:0271 | 1462:3fc1 | Nvidia     | MCP51 PMU                    | 5     |            | 800B19FF2D |
| 10de:07da | 1462:7366 | Nvidia     | MCP73 Co-processor           | 5     |            | ADA828F120 |
| 10de:07da | 1462:736b | Nvidia     | MCP73 Co-processor           | 5     |            | C554C3A77F |
| 10de:0aa3 | 1071:9070 | Nvidia     | MCP79 Co-processor           | 5     | nvidia     | ABE849C090 |
| 10de:0aa3 | 1849:0aa3 | Nvidia     | MCP79 Co-processor           | 5     | nvidia     | B68D01F3AE |
| 10de:0271 | 1043:1367 | Nvidia     | MCP51 PMU                    | 4     |            | 7BD5FA25B3 |
| 10de:03f4 | 1849:03f4 | Nvidia     | MCP61 SMU                    | 4     |            | 5751926628 |
| 10de:0753 | 1025:0157 | Nvidia     | MCP78S [GeForce 8200] Co-... | 4     |            | B942B5FB12 |
| 10de:0753 | 1025:0227 | Nvidia     | MCP78S [GeForce 8200] Co-... | 4     |            | 4C4B83CA44 |
| 10de:07da | 1462:7504 | Nvidia     | MCP73 Co-processor           | 4     |            | 56863BBCA2 |
| 10de:07da | 1849:07da | Nvidia     | MCP73 Co-processor           | 4     |            | AC70970005 |
| 10de:0aa3 | 103c:2a95 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | 0E1FA2C583 |
| 10de:0aa3 | 105b:0d52 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | 3F5D854E2F |
| 10de:0271 | 103c:30e5 | Nvidia     | MCP51 PMU                    | 3     |            | A070611109 |
| 10de:0271 | 1462:373d | Nvidia     | MCP51 PMU                    | 3     |            | 154009C211 |
| 10de:0271 | 1734:110c | Nvidia     | MCP51 PMU                    | 3     |            | 79DCA1A7CC |
| 10de:0753 | 1025:014d | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | 77FC351561 |
| 10de:0753 | 1025:0462 | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | BEB8F313F7 |
| 10de:0753 | 103c:2a9e | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | C1329912E7 |
| 10de:0753 | 1462:7612 | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | 905C03A3D4 |
| 10de:07da | 10de:07d7 | Nvidia     | MCP73 Co-processor           | 3     |            | 974A439CC4 |
| 10de:0aa3 | 1043:1a87 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 03675A2262 |
| 10de:0aa3 | 1043:1fd7 | Nvidia     | MCP79 Co-processor           | 3     |            | 4B30E929C5 |
| 10de:0aa3 | 1043:83e2 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 1452DE25DA |
| 10de:0aa3 | 1043:83e9 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 0D0D8B9925 |
| 10de:0aa3 | 1043:83f9 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 57C3CE82B7 |
| 10de:0aa3 | 1734:1151 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | E6A298846B |
| 10de:0aa3 | 19da:0ae5 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | C18FD136A9 |
| 10de:0aa3 | 19da:a108 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 35A29512AC |
| 10de:0543 | 1025:0127 | Nvidia     | MCP67 Co-processor           | 2     |            | 0D272A5910 |
| 10de:0753 | 1019:1b67 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 35BFD13207 |
| 10de:0753 | 1019:2646 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | BF975A328C |
| 10de:0753 | 1019:2666 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 5C15176A57 |
| 10de:0753 | 1043:8332 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | FC54031F7E |
| 10de:0753 | 1462:7375 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 07A001660F |
| 10de:0753 | 1462:7578 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 8DB5C49C90 |
| 10de:0aa3 | 1028:0271 | Nvidia     | MCP79 Co-processor           | 2     |            | C928DD680A |
| 10de:0aa3 | 103c:2aa1 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | C2FD4F3C01 |
| 10de:0aa3 | 1043:8356 | Nvidia     | MCP79 Co-processor           | 2     |            | AAF6FAFAD6 |
| 10de:0aa3 | 1458:0aa3 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | 6C871AB8BE |
| 10de:0aa3 | 1462:1019 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | 2054B3A4CC |
| 10de:0aa3 | 17aa:38da | Nvidia     | MCP79 Co-processor           | 2     |            | C38D40E936 |
| 10de:0aa3 | 1b0a:000f | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | BF054CFF0C |
| 10de:0aa3 | 1b0a:4203 | Nvidia     | MCP79 Co-processor           | 2     |            | 3D1668F30A |
| 8086:19e2 | 8086:0000 | Intel      | Atom Processor C3000 Seri... | 2     | qat_c3xxx  | 40E07B4DAD |
| 8086:19e2 | 8086:19e2 | Intel      | Atom Processor C3000 Seri... | 2     |            | 50B6A72C0C |
| 8086:1f18 | 15d9:0820 | Intel      | Atom processor C2000 QAT     | 2     |            | B9AC0D657E |
| 8086:1f18 | 8086:0000 | Intel      | Atom processor C2000 QAT     | 2     |            | C1D37659C1 |
| 8086:225c | 8086:2500 | Intel      | Xeon Phi coprocessor SE10... | 2     | mic        | 9D9DA282F6 |
| 8086:37c8 | 8086:0000 | Intel      | C62x Chipset QuickAssist ... | 2     | qat_c62x   | 331227D869 |
| 10de:0271 | 1043:1322 | Nvidia     | MCP51 PMU                    | 1     |            | 71FE8FB963 |
| 10de:0271 | 1043:14b7 | Nvidia     | MCP51 PMU                    | 1     |            | AFE46A35A8 |
| 10de:0271 | 107b:0317 | Nvidia     | MCP51 PMU                    | 1     |            | 1178CC8597 |
| 10de:0271 | 1734:10d3 | Nvidia     | MCP51 PMU                    | 1     |            | 6172D9B266 |
| 10de:0271 | 1734:10d4 | Nvidia     | MCP51 PMU                    | 1     |            | 360270471C |
| 10de:0543 | 1043:1697 | Nvidia     | MCP67 Co-processor           | 1     |            | C3296D5344 |
| 10de:0543 | 1631:c106 | Nvidia     | MCP67 Co-processor           | 1     |            | BC2AD0771E |
| 10de:0753 | 1025:014a | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | F63FFEFC64 |
| 10de:0753 | 107b:0173 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | 4A6A75378D |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1c3a | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1006  | mei_me     | EA164260EB |
| 8086:8c3a | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 789   | mei_me     | 9A23DF55D8 |
| 8086:1e3a | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 697   | mei_me     | BA117FEF7E |
| 8086:a13a | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 632   | mei_me     | 11EBF0D551 |
| 8086:1c3a | 1458:1c3a | Intel      | 6 Series/C200 Series Chip... | 628   | mei_me     | EE570B7B0C |
| 8086:8c3a | 1458:1c3a | Intel      | 8 Series/C220 Series Chip... | 512   | mei_me     | E187B3F207 |
| 8086:1e3a | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 508   | mei_me     | 5872E567EC |
| 8086:1e3a | 1458:1c3a | Intel      | 7 Series/C216 Chipset Fam... | 504   | mei_me     | 89F6EB0671 |
| 8086:a2ba | 1043:8694 | Intel      | 200 Series PCH CSME HECI #1  | 391   | mei_me     | 2696477C0C |
| 8086:a2ba | 1458:1c3a | Intel      | 200 Series PCH CSME HECI #1  | 364   | mei_me     | F91A20DD51 |
| 8086:a13a | 1458:1c3a | Intel      | 100 Series/C230 Series Ch... | 356   | mei_me     | 5474165F7B |
| 8086:a360 | 1043:8694 | Intel      | Cannon Lake PCH HECI Cont... | 301   | mei_me     | 36EBF65D44 |
| 8086:1c3a | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 297   | mei_me     | 21DB34139A |
| 8086:3b64 | 17aa:215f | Intel      | 5 Series/3400 Series Chip... | 295   | mei_me     | 5DC4A1E557 |
| 8086:8cba | 1043:8534 | Intel      | 9 Series Chipset Family M... | 290   | mei_me     | 0D40DAA834 |
| 8086:9c3a | 17aa:3978 | Intel      | 8 Series HECI #0             | 275   | mei_me     | B1B8196F26 |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 267   | mei_me     | 71A92492E3 |
| 8086:a360 | 1458:1c3a | Intel      | Cannon Lake PCH HECI Cont... | 257   | mei_me     | E8B8B03EBD |
| 8086:1c3a | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 254   | mei_me     | 7EBB0672C0 |
| 8086:8c3a | 1849:8c3a | Intel      | 8 Series/C220 Series Chip... | 248   | mei_me     | F36828F316 |
| 8086:1c3a | 1849:1c3a | Intel      | 6 Series/C200 Series Chip... | 243   | mei_me     | EFEC95A916 |
| 8086:2a44 | 17aa:20e6 | Intel      | Mobile 4 Series Chipset M... | 234   | mei_me     | DB936567F0 |
| 8086:1e3a | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 222   | mei_me     | 066B825941 |
| 8086:8cba | 1458:1c3a | Intel      | 9 Series Chipset Family M... | 220   | mei_me     | DF13F72A9A |
| 8086:319a | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 215   | mei_me     | 021617B9A0 |
| 8086:a13a | 1849:a13a | Intel      | 100 Series/C230 Series Ch... | 172   | mei_me     | 3A2A9BD626 |
| 8086:1e3a | 1849:1e3a | Intel      | 7 Series/C216 Chipset Fam... | 171   | mei_me     | E7EBAD7358 |
| 8086:3b64 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 170   | mei_me     | 11F1CDC49A |
| 8086:1e3a | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 165   | mei_me     | C9503690D6 |
| 8086:8c3a | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 161   | mei_me     | 75E2E357A3 |
| 8086:1e3a | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 151   | mei_me     | 52667487D2 |
| 8086:8c3a | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 150   | mei_me     | 7FB630F632 |
| 8086:9d3a | 8086:7270 | Intel      | Sunrise Point-LP CSME HEC... | 150   | mei_me     | 8030B99150 |
| 8086:1c3a | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 148   | mei_me     | 438D785F0E |
| 8086:1c3a | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 147   | mei_me     | 74547808D3 |
| 8086:a2ba | 1849:a2ba | Intel      | 200 Series PCH CSME HECI #1  | 146   | mei_me     | A8F84AEA94 |
| 8086:1c3a | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 145   | mei_me     | B420F25ED4 |
| 8086:1e3a | 1028:0577 | Intel      | 7 Series/C216 Chipset Fam... | 144   | mei_me     | 4DAF9FDC0D |
| 8086:1c3a | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 138   | mei_me     | 33617DD1A8 |
| 8086:1d3a | 1043:84ef | Intel      | C600/X79 series chipset M... | 137   | mei_me     | F0DC31F93D |
| 8086:319a | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 135   | mei_me     | 170B220F5B |
| 8086:1e3a | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 134   | mei_me     | 50D562CAB5 |
| 8086:a2ba | 1043:872f | Intel      | 200 Series PCH CSME HECI #1  | 131   | mei_me     | C1BF9C169D |
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
| 8086:9de0 | 8086:2074 | Intel      | Cannon Point-LP MEI Contr... | 116   | mei_me     | 7CA350189C |
| 8086:1e3a | 17aa:21f6 | Intel      | 7 Series/C216 Chipset Fam... | 115   | mei_me     | 9ECBB7A946 |
| 8086:1e3a | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 114   | mei_me     | B732F94275 |
| 8086:a360 | 1028:0905 | Intel      | Cannon Lake PCH HECI Cont... | 113   | mei_me     | 9CDE952049 |
| 8086:9d3e |           | Intel      | Skylake-U/Y CSME: HECI #3    | 112   | mei_me     | 0E1D0B8D70 |
| 8086:9c3a | 17aa:220c | Intel      | 8 Series HECI #0             | 110   | mei_me     | 4C600416F9 |
| 8086:9d3a | 17aa:3801 | Intel      | Sunrise Point-LP CSME HEC... | 109   | mei_me     | 74D1DA4B68 |
| 8086:1c3a | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 108   | mei_me     | A8FD68FCCC |
| 8086:02e0 | 17aa:5079 | Intel      | Comet Lake Management Eng... | 107   | mei_me     | 0BC4073D23 |
| 8086:1c3a | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 107   | mei_me     | DB42B43D7E |
| 8086:8c3a | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 105   | mei_me     | 0FC3ABDB1C |
| 8086:9cba | 8086:7270 | Intel      | Wildcat Point-LP MEI Cont... | 105   | mei_me     | C0ED6370C5 |
| 8086:9d3a | 1025:1193 | Intel      | Sunrise Point-LP CSME HEC... | 105   | mei_me     | E922639FF6 |
| 8086:1e3a | 17aa:5002 | Intel      | 7 Series/C216 Chipset Fam... | 104   | mei_me     | 2BA1AA7C62 |
| 8086:8cba | 1849:8cba | Intel      | 9 Series Chipset Family M... | 103   | mei_me     | B203387A22 |
| 8086:a360 | 1849:a360 | Intel      | Cannon Lake PCH HECI Cont... | 102   | mei_me     | 839B20476A |
| 8086:1c3a | 103c:161c | Intel      | 6 Series/C200 Series Chip... | 101   | mei_me     | 701E56A49F |
| 8086:3b64 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 100   | mei_me     | 3C0A297EDE |
| 8086:1e3a | 10cf:16ea | Intel      | 7 Series/C216 Chipset Fam... | 99    | mei_me     | B2D4A08D24 |
| 8086:9c3a | 103c:198f | Intel      | 8 Series HECI #0             | 99    | mei_me     | 6573923D55 |
| 8086:a360 | 1028:087c | Intel      | Cannon Lake PCH HECI Cont... | 98    | mei_me     | 31A6F21CCD |
| 8086:9d3a | 1028:0810 | Intel      | Sunrise Point-LP CSME HEC... | 97    | mei_me     | 2FD333BC52 |
| 8086:8c3a | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 96    | mei_me     | 4EC9EAAC2F |
| 8086:9de0 | 17aa:2279 | Intel      | Cannon Point-LP MEI Contr... | 96    | mei_me     | 2444839350 |
| 8086:8d3a | 1043:8600 | Intel      | C610/X99 series chipset M... | 95    | mei_me     | E456864B06 |
| 8086:1c3a | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 94    | mei_me     | F8B9508953 |
| 8086:8c3a | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 94    | mei_me     | 07190AC752 |
| 8086:1c3a | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 93    | mei_me     | 389E1A52A6 |
| 8086:1e3a | 103c:179b | Intel      | 7 Series/C216 Chipset Fam... | 93    | mei_me     | 7D39BC1331 |
| 8086:9c3a | 1025:0866 | Intel      | 8 Series HECI #0             | 93    | mei_me     | 58B4832D53 |
| 8086:9d3a | 103c:8079 | Intel      | Sunrise Point-LP CSME HEC... | 93    | mei_me     | 0FA8058EEB |
| 8086:1e3a | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 92    | mei_me     | A5268098B2 |
| 8086:9c3a | 1028:0651 | Intel      | 8 Series HECI #0             | 92    | mei_me     | E1A816CC42 |
| 8086:9de0 | 103c:8549 | Intel      | Cannon Point-LP MEI Contr... | 92    | mei_me     | 9A264DBCB2 |
| 8086:1c3a | 104d:908b | Intel      | 6 Series/C200 Series Chip... | 91    | mei_me     | F88D733F75 |
| 8086:1e3a | 1179:fb31 | Intel      | 7 Series/C216 Chipset Fam... | 91    | mei_me     | 6BECED18DA |
| 8086:29b4 | 1028:0211 | Intel      | 82Q35 Express MEI Controller | 91    | mei_me     | 962E0B75E4 |
| 8086:3b64 | 1458:3b64 | Intel      | 5 Series/3400 Series Chip... | 91    | mei_me     | 3F02DD61E1 |
| 8086:1e3a | 103c:3397 | Intel      | 7 Series/C216 Chipset Fam... | 90    | mei_me     | 9C1343DD9B |
| 8086:1e3a | 1043:1477 | Intel      | 7 Series/C216 Chipset Fam... | 90    | mei_me     | 62C6944A06 |
| 8086:1e3a | 1043:14c7 | Intel      | 7 Series/C216 Chipset Fam... | 90    | mei_me     | 53842E648E |
| 8086:9d3a | 1043:12d1 | Intel      | Sunrise Point-LP CSME HEC... | 89    | mei_me     | 570905286F |
| 8086:1c3a | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 88    | mei_me     | C40BAA791F |
| 8086:9d3a | 17aa:225d | Intel      | Sunrise Point-LP CSME HEC... | 88    | mei_me     | BBA3BC97B7 |
| 8086:9de0 | 17aa:2292 | Intel      | Cannon Point-LP MEI Contr... | 88    | mei_me     | FBF4582983 |
| 8086:9d3a |           | Intel      | Sunrise Point-LP CSME HEC... | 87    | mei_me     | 7AEC563171 |
| 8086:9c3a | 8086:7270 | Intel      | 8 Series HECI #0             | 85    | mei_me     | 1007726831 |

### Dma controller (eisa dma) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9ce0 | 8086:9ce0 | Intel      | Wildcat Point-LP Serial I... | 85    | dw_dmac... | C0ED6370C5 |
| 8086:9c60 |           | Intel      | 8 Series Low Power Sub-Sy... | 26    | dw_dmac... | C89BBD3B30 |
| 8086:22c0 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 18    | dw_dmac... | F084020240 |
| 8086:2286 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 10    | dw_dmac... | ED6F77168B |
| 8086:22c0 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 10    | dw_dmac... | ED6F77168B |
| 8086:9c60 | 1025:0a11 | Intel      | 8 Series Low Power Sub-Sy... | 6     | dw_dmac... | 9DC2B77BCD |
| 8086:9c60 | 103c:21ed | Intel      | 8 Series Low Power Sub-Sy... | 5     | dw_dmac... | 9BB0BF9AC8 |
| 8086:0f40 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 2     | dw_dmac... | 0994A3EEB3 |
| 8086:0f06 | 8086:0f06 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | A968EF1DD8 |
| 8086:0f06 | 8086:2056 | Intel      | Atom Processor Z36xxx/Z37... | 1     |            | D4408F7B0E |
| 8086:0f06 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | A211982E39 |
| 8086:0f40 | 1025:0939 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | C431BDD246 |
| 8086:0f40 | 8086:2056 | Intel      | Atom Processor Z36xxx/Z37... | 1     |            | D4408F7B0E |
| 8086:2286 | 1025:106c | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 09F6D20FE1 |
| 8086:2286 | 1025:1151 | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 7B7DB12037 |
| 8086:22c0 | 1025:106c | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 09F6D20FE1 |
| 8086:22c0 | 1025:1151 | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 7B7DB12037 |

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
| 1022:1456 | 1022:1456 | AMD        | Family 17h (Models 00h-0f... | 1630  | ccp        | D88D9DB618 |
| 1022:15df | 1022:15df | AMD        | Family 17h (Models 10h-1f... | 1509  | ccp        | F504E72617 |
| 1022:1486 | 1022:1486 | AMD        | Starship/Matisse Cryptogr... | 1017  | ccp        | 6056EAC50C |
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 570   | mei_txe    | 1B5E908CFF |
| 1022:1486 | 1043:87c0 | AMD        | Starship/Matisse Cryptogr... | 566   | ccp        | 97C17F738A |
| 1022:1456 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 523   | ccp        | 115EC5ECA4 |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 415   |            | 3EA595A278 |
| 1022:1537 | 1022:1537 | AMD        | Kabini/Mullins PSP-Platfo... | 413   | ccp        | 4594F040E1 |
| 1022:15df | 1043:876b | AMD        | Family 17h (Models 10h-1f... | 201   | ccp        | AB4B1B7A15 |
| 8086:0f18 | 8086:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 154   | mei_txe    | 8AE91D28E1 |
| 1022:1537 | 17aa:3801 | AMD        | Kabini/Mullins PSP-Platfo... | 123   | ccp        | 779BFC3B47 |
| 8086:0f18 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 117   | mei_txe    | EED35A825A |
| 1022:1578 | 103c:8330 | AMD        | Carrizo Platform Security... | 107   |            | 5671BA2F85 |
| 8086:0f18 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 93    | mei_txe    | EB9AAA55EA |
| 8086:0f18 | 17aa:3909 | Intel      | Atom Processor Z36xxx/Z37... | 86    | mei_txe    | BAC9935F0B |
| 1022:1486 | 1043:8808 | AMD        | Starship/Matisse Cryptogr... | 82    | ccp        | 20115EE05D |
| 1022:1486 | 1462:7c02 | AMD        | Starship/Matisse Cryptogr... | 79    | ccp        | A04EB698F8 |
| 1022:1578 | 103c:84ac | AMD        | Carrizo Platform Security... | 78    |            | D22A5E8410 |
| 1022:1578 | 1025:1192 | AMD        | Carrizo Platform Security... | 73    |            | CDC742CD03 |
| 1022:1578 | 17aa:3810 | AMD        | Carrizo Platform Security... | 68    |            | E57C2FB16D |
| 1022:15df | 19e5:3e19 | AMD        | Family 17h (Models 10h-1f... | 62    | ccp        | 9908BA82E9 |
| 1022:15df | 17aa:5081 | AMD        | Family 17h (Models 10h-1f... | 60    | ccp        | 6B6205BC5D |
| 8086:0f18 | 1849:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 57    | mei_txe    | BA2B52B494 |
| 1022:15df | 103c:84ae | AMD        | Family 17h (Models 10h-1f... | 56    | ccp        | BFB71F53EC |
| 1022:15df | 1025:1366 | AMD        | Family 17h (Models 10h-1f... | 55    | ccp        | CF7AB2CA73 |
| 1022:15df | 17aa:507f | AMD        | Family 17h (Models 10h-1f... | 55    | ccp        | 441E3AA589 |
| 8086:2298 | 1025:1012 | Intel      | Atom/Celeron/Pentium Proc... | 54    | mei_txe    | 20016440FD |
| 8086:2298 | 1028:06ac | Intel      | Atom/Celeron/Pentium Proc... | 54    | mei_txe    | 1EA1C9F3FE |
| 1022:15df | 1025:134d | AMD        | Family 17h (Models 10h-1f... | 52    | ccp        | 479F0822FE |
| 8086:0f18 | 1043:161d | Intel      | Atom Processor Z36xxx/Z37... | 52    | mei_txe    | 1FA3E8B296 |
| 8086:0f18 | 103c:2213 | Intel      | Atom Processor Z36xxx/Z37... | 51    | mei_txe    | 1CE25A2590 |
| 1022:1456 | 1462:7c02 | AMD        | Family 17h (Models 00h-0f... | 50    | ccp        | 2229C9E9F6 |
| 1022:15df | 17aa:3818 | AMD        | Family 17h (Models 10h-1f... | 50    | ccp        | EA8B53C3DC |
| 1022:15df | 17aa:5124 | AMD        | Family 17h (Models 10h-1f... | 50    | ccp        | 4DE4650899 |
| 8086:0f18 | 1297:2041 | Intel      | Atom Processor Z36xxx/Z37... | 50    | mei_txe    | 32D3859912 |
| 1022:1486 | 1462:7b86 | AMD        | Starship/Matisse Cryptogr... | 49    | ccp        | A42F5B4313 |
| 1022:15df | 17aa:380f | AMD        | Family 17h (Models 10h-1f... | 49    | ccp        | 6FE368312C |
| 1022:1578 | 17aa:380f | AMD        | Carrizo Platform Security... | 48    |            | 18D8EEC6A4 |
| 1022:15df | 17aa:381f | AMD        | Family 17h (Models 10h-1f... | 48    | ccp        | 9480BB8E99 |
| 8086:2298 | 103c:832c | Intel      | Atom/Celeron/Pentium Proc... | 47    | mei_txe    | 618D37F6A5 |
| 1022:15df | 17aa:3811 | AMD        | Family 17h (Models 10h-1f... | 46    | ccp        | FCC7840D63 |
| 8086:2298 | 1043:10c0 | Intel      | Atom/Celeron/Pentium Proc... | 46    | mei_txe    | 0F79FB429B |
| 8086:0f18 | 1043:14dd | Intel      | Atom Processor Z36xxx/Z37... | 42    | mei_txe    | 6F97387DAC |
| 8086:2298 | 17aa:3808 | Intel      | Atom/Celeron/Pentium Proc... | 42    | mei_txe    | 9372D60118 |
| 1022:1456 | 1462:7b86 | AMD        | Family 17h (Models 00h-0f... | 40    | ccp        | 6787B45989 |
| 1022:1486 | 1462:7b89 | AMD        | Starship/Matisse Cryptogr... | 37    | ccp        | 43A19D8280 |
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
| 8086:0f18 | 1458:1c3a | Intel      | Atom Processor Z36xxx/Z37... | 33    | mei_txe    | 0FF0A247D9 |
| 8086:2298 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 33    | mei_txe    | 9E568EF477 |
| 1022:1578 | 17aa:3815 | AMD        | Carrizo Platform Security... | 32    |            | 27153360C7 |
| 1022:15df | 17aa:3809 | AMD        | Family 17h (Models 10h-1f... | 32    | ccp        | 008C187A8B |
| 8086:0f18 | 1179:f91b | Intel      | Atom Processor Z36xxx/Z37... | 31    | mei_txe    | 80080989FA |
| 8086:2298 | 17aa:380c | Intel      | Atom/Celeron/Pentium Proc... | 31    | mei_txe    | F21B55E1F7 |
| 1022:15df | 103c:86fd | AMD        | Family 17h (Models 10h-1f... | 30    | ccp        | 415E7E34D6 |
| 1022:1537 | 1025:104b | AMD        | Kabini/Mullins PSP-Platfo... | 29    | ccp        | 6E75E7C288 |
| 1022:15df | 17aa:5082 | AMD        | Family 17h (Models 10h-1f... | 29    | ccp        | 12FFAAEFB1 |
| 8086:2298 | 103c:80c5 | Intel      | Atom/Celeron/Pentium Proc... | 29    | mei_txe    | 3CC10CC5F1 |
| 8086:2298 | 17aa:380a | Intel      | Atom/Celeron/Pentium Proc... | 29    | mei_txe    | 4AC35C901A |
| 1022:1578 | 17aa:380c | AMD        | Carrizo Platform Security... | 28    |            | AD6F771DA6 |
| 1022:15df | 1025:142b | AMD        | Family 17h (Models 10h-1f... | 28    | ccp        | 5DCA660F7E |
| 8086:0f18 | 1025:0936 | Intel      | Atom Processor Z36xxx/Z37... | 28    | mei_txe    | 05B439EB53 |
| 8086:0f18 | 103c:21de | Intel      | Atom Processor Z36xxx/Z37... | 28    | mei_txe    | B34D6D63D9 |
| 8086:0f18 | 1043:15bd | Intel      | Atom Processor Z36xxx/Z37... | 28    | mei_txe    | D8057F1C4D |
| 8086:2298 | 103c:813e | Intel      | Atom/Celeron/Pentium Proc... | 28    | mei_txe    | 71120B9356 |
| 1022:1537 | 1025:108a | AMD        | Kabini/Mullins PSP-Platfo... | 27    | ccp        | FDFA81C2E5 |
| 1022:15df | 103c:876f | AMD        | Family 17h (Models 10h-1f... | 27    | ccp        | 08B513769D |
| 1022:15df | 1462:7a38 | AMD        | Family 17h (Models 10h-1f... | 27    | ccp        | 3056DB282E |
| 1022:15df | 17aa:380d | AMD        | Family 17h (Models 10h-1f... | 27    | ccp        | CB9D7D7035 |
| 1022:15df | 17aa:3817 | AMD        | Family 17h (Models 10h-1f... | 27    | ccp        | 99D22D0422 |
| 1022:15df | 17aa:507e | AMD        | Family 17h (Models 10h-1f... | 27    | ccp        | 31850CE796 |
| 8086:2298 | 1043:12e0 | Intel      | Atom/Celeron/Pentium Proc... | 27    | mei_txe    | 93F191DCA0 |
| 1022:1456 | 1462:7a38 | AMD        | Family 17h (Models 00h-0f... | 26    | ccp        | 00A14A97A2 |
| 1022:1578 | 103c:8331 | AMD        | Carrizo Platform Security... | 26    |            | 30C73729A4 |
| 1022:15df | 1025:125c | AMD        | Family 17h (Models 10h-1f... | 26    | ccp        | FF512AC729 |
| 1022:15df | 103c:85b3 | AMD        | Family 17h (Models 10h-1f... | 26    | ccp        | 039DF57583 |
| 1022:15df | 103c:876e | AMD        | Family 17h (Models 10h-1f... | 26    | ccp        | F77E2EBB10 |
| 1022:15df | 17aa:3804 | AMD        | Family 17h (Models 10h-1f... | 26    | ccp        | 57651669E3 |
| 8086:2298 | 103c:82bd | Intel      | Atom/Celeron/Pentium Proc... | 26    | mei_txe    | AB155989AA |
| 8086:2298 | 1043:191d | Intel      | Atom/Celeron/Pentium Proc... | 26    | mei_txe    | A1B6970890 |
| 1022:1578 | 103c:8333 | AMD        | Carrizo Platform Security... | 25    |            | 8911FC397F |
| 1022:15df | 17aa:5125 | AMD        | Family 17h (Models 10h-1f... | 25    | ccp        | 452DD792F1 |
| 1022:15df | 1025:1461 | AMD        | Family 17h (Models 10h-1f... | 24    | ccp        | 8D643F3501 |
| 8086:2298 | 1458:1000 | Intel      | Atom/Celeron/Pentium Proc... | 24    | mei_txe    | E0A36977D5 |
| 1022:1456 | 1462:7b89 | AMD        | Family 17h (Models 00h-0f... | 23    | ccp        | 463432C55F |
| 1022:1578 | 1025:109f | AMD        | Carrizo Platform Security... | 23    |            | 70037BDDCB |
| 1022:15df | 1025:134f | AMD        | Family 17h (Models 10h-1f... | 23    | ccp        | 3EC48C5388 |
| 8086:0f18 | 1043:14ed | Intel      | Atom Processor Z36xxx/Z37... | 23    | mei_txe    | BCA3C06314 |
| 1022:15df | 103c:85dd | AMD        | Family 17h (Models 10h-1f... | 22    | ccp        | A93B2565DF |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1106:3044 | 1043:81fe | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 731   | firewir... | 4B4D8AA09F |
| 104c:8024 | 1458:1000 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 706   | firewir... | 5EBB861FEB |
| 11c1:5901 | 11c1:5900 | LSI        | FW643 [TrueFire] PCIe 139... | 589   | firewir... | 066B825941 |
| 1180:0832 | 17aa:20c7 | Ricoh      | R5C832 IEEE 1394 Controller  | 257   | firewir... | DB936567F0 |
| 1106:3403 | 1043:8384 | VIA Tec... | VT6315 Series Firewire Co... | 237   | firewir... | FA66471153 |
| 1106:3044 | 1458:1000 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 236   | firewir... | 77FCB9CF4A |
| 11c1:5811 | 1043:8294 | LSI        | FW322/323 [TrueFire] 1394... | 200   | firewir... | 102C78CA6B |
| 1106:3044 | 1106:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 189   | firewir... | 36FB4E2ABA |
| 104c:823f |           | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 165   | firewir... | CC088D7F17 |
| 1102:4001 | 1102:0010 | Creativ... | SB Audigy FireWire Port      | 157   | firewir... | A51030D9A0 |
| 11c1:5811 | 11c1:5811 | LSI        | FW322/323 [TrueFire] 1394... | 155   | firewir... | C480910C6C |
| 1180:e832 | 17aa:2136 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 148   | firewir... | 4FF6DAE64C |
| 1180:e832 | 1028:040a | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 123   | firewir... | 576A6491F3 |
| 104c:803a | 1025:011f | Texas I... | PCIxx12 OHCI Compliant IE... | 122   | firewir... | 6A05B72968 |
| 1106:3403 | 1849:3403 | VIA Tec... | VT6315 Series Firewire Co... | 115   | firewir... | 4C10147742 |
| 1180:0832 | 1028:0233 | Ricoh      | R5C832 IEEE 1394 Controller  | 107   | firewir... | 2A4C5F6EEC |
| 197b:2380 | 103c:161c | JMicron... | IEEE 1394 Host Controller    | 96    | firewir... | 701E56A49F |
| 104c:8023 | 1043:808b | Texas I... | TSB43AB22A IEEE-1394a-200... | 95    | firewir... | 34AB0FD5ED |
| 104c:803a | 1179:ff00 | Texas I... | PCIxx12 OHCI Compliant IE... | 92    | firewir... | 8E44C9EDAF |
| 1217:00f7 | 1028:01f9 | O2 Micro   | Firewire (IEEE 1394)         | 87    | firewir... | E271885D51 |
| 197b:2380 | 103c:179b | JMicron... | IEEE 1394 Host Controller    | 86    | firewir... | 7D39BC1331 |
| 1180:e832 | 17aa:21cf | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 79    | firewir... | C40BAA791F |
| 1180:0832 | 1028:022f | Ricoh      | R5C832 IEEE 1394 Controller  | 72    | firewir... | 06130B24C5 |
| 1180:e832 | 17aa:21f6 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 70    | firewir... | 88CEE1E822 |
| 197b:2380 | 1043:8313 | JMicron... | IEEE 1394 Host Controller    | 64    | firewir... | 4D5F23E6BA |
| 1180:0832 | 103c:30cc | Ricoh      | R5C832 IEEE 1394 Controller  | 62    | firewir... | 4E93C68985 |
| 1217:00f7 | 1179:ff50 | O2 Micro   | Firewire (IEEE 1394)         | 55    | firewir... | FEB13460E8 |
| 1180:0832 | 103c:172a | Ricoh      | R5C832 IEEE 1394 Controller  | 54    | firewir... | 9635709179 |
| 1106:3403 | 103c:2a9c | VIA Tec... | VT6315 Series Firewire Co... | 51    | firewir... | 9A3C939249 |
| 1106:3403 | 1043:8374 | VIA Tec... | VT6315 Series Firewire Co... | 51    | firewir... | 00F250E5C2 |
| 104c:8023 | 1043:815b | Texas I... | TSB43AB22A IEEE-1394a-200... | 50    | firewir... | 926229BE87 |
| 11c1:5811 | 103c:2a6f | LSI        | FW322/323 [TrueFire] 1394... | 50    | firewir... | E051360964 |
| 1180:e832 | 17aa:21ce | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 47    | firewir... | 74547808D3 |
| 1217:00f7 | 1217:00f7 | O2 Micro   | Firewire (IEEE 1394)         | 47    | firewir... | 2AE9241025 |
| 1217:13f7 | 1028:0494 | O2 Micro   | 1394 OHCI Compliant Host ... | 46    | firewir... | E58B9D7EA5 |
| 1180:0832 | 1025:011e | Ricoh      | R5C832 IEEE 1394 Controller  | 45    | firewir... | 3C8537DFE3 |
| 1180:0832 | 103c:7008 | Ricoh      | R5C832 IEEE 1394 Controller  | 44    | firewir... | 383932E73B |
| 197b:2380 | 103c:3628 | JMicron... | IEEE 1394 Host Controller    | 43    | firewir... | DCE60F14E1 |
| 104c:8025 |           | Texas I... | TSB82AA2 IEEE-1394b Link ... | 41    | firewir... | 41C18A9562 |
| 1180:0832 | 103c:30c0 | Ricoh      | R5C832 IEEE 1394 Controller  | 41    | firewir... | 4DEAD8CD75 |
| 1180:0832 | 103c:30cf | Ricoh      | R5C832 IEEE 1394 Controller  | 41    | firewir... | CB77A79EE8 |
| 1180:e832 | 1028:040b | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 41    | firewir... | 6902EB0F50 |
| 11c1:5811 | 103c:1309 | LSI        | FW322/323 [TrueFire] 1394... | 41    | firewir... | 83C114D947 |
| 1106:3403 | 1106:3403 | VIA Tec... | VT6315 Series Firewire Co... | 40    | firewir... | ED22ADFD9F |
| 1180:0832 | 1028:024f | Ricoh      | R5C832 IEEE 1394 Controller  | 40    | firewir... | 3BDEE6855C |
| 1180:0832 | 1025:0121 | Ricoh      | R5C832 IEEE 1394 Controller  | 39    | firewir... | 5D933E19AC |
| 197b:2380 | 103c:1618 | JMicron... | IEEE 1394 Host Controller    | 37    | firewir... | EA1BD5E314 |
| 11c1:5811 | 103c:30dd | LSI        | FW322/323 [TrueFire] 1394... | 36    | firewir... | 65FBD3DEF4 |
| 1180:0832 | 1028:01bd | Ricoh      | R5C832 IEEE 1394 Controller  | 35    | firewir... | 3EB7729825 |
| 1180:0832 | 104d:9035 | Ricoh      | R5C832 IEEE 1394 Controller  | 35    | firewir... | 1A9761824E |
| 1180:e832 | 103c:146d | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 35    | firewir... | 523C397AB6 |
| 11c1:5811 | 103c:1589 | LSI        | FW322/323 [TrueFire] 1394... | 35    | firewir... | A4B0EBBEE2 |
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
| 1106:3044 | 1043:808a | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 31    | firewir... | E739F2F0BA |
| 1180:0832 | 1025:0126 | Ricoh      | R5C832 IEEE 1394 Controller  | 31    | firewir... | AA6D721BF2 |
| 1180:0832 | 1028:024d | Ricoh      | R5C832 IEEE 1394 Controller  | 31    | firewir... | 98D088D90D |
| 1180:0832 | 103c:30bb | Ricoh      | R5C832 IEEE 1394 Controller  | 31    | firewir... | 5F6D9F025A |
| 104c:8023 | 8086:5044 | Texas I... | TSB43AB22A IEEE-1394a-200... | 30    | firewir... | AF996AA861 |
| 104c:823f | 3412:7856 | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 30    | firewir... | 0A228B18C1 |
| 1180:0832 | 1043:1877 | Ricoh      | R5C832 IEEE 1394 Controller  | 30    | firewir... | 139F010F51 |
| 104c:803a | 104d:9005 | Texas I... | PCIxx12 OHCI Compliant IE... | 29    | firewir... | BD472575F4 |
| 1106:3044 | 1849:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 29    | firewir... | C008E87B1C |
| 197b:2380 | 103c:161d | JMicron... | IEEE 1394 Host Controller    | 27    | firewir... | 06BC21DB81 |
| 197b:2380 | 103c:3603 | JMicron... | IEEE 1394 Host Controller    | 27    | firewir... | 14F176409D |
| 104c:8023 | 8086:514d | Texas I... | TSB43AB22A IEEE-1394a-200... | 25    | firewir... | D76E4B9EC3 |
| 104c:803a | 104d:9015 | Texas I... | PCIxx12 OHCI Compliant IE... | 25    | firewir... | 9AC5C739FF |
| 104c:803a | 104d:902d | Texas I... | PCIxx12 OHCI Compliant IE... | 25    | firewir... | B97D7A8C66 |
| 1180:0832 | 1028:0263 | Ricoh      | R5C832 IEEE 1394 Controller  | 25    | firewir... | 679F6F3259 |
| 104c:803a | 1179:0001 | Texas I... | PCIxx12 OHCI Compliant IE... | 24    | firewir... | EA94C20118 |
| 11c1:5811 | 103c:158a | LSI        | FW322/323 [TrueFire] 1394... | 23    | firewir... | D70166F107 |
| 197b:2380 | 103c:30f4 | JMicron... | IEEE 1394 Host Controller    | 23    | firewir... | E8E3CCB220 |
| 197b:2380 | 103c:3659 | JMicron... | IEEE 1394 Host Controller    | 23    | firewir... | 827D185513 |
| 1180:0832 | 1043:14e7 | Ricoh      | R5C832 IEEE 1394 Controller  | 22    | firewir... | 2494100ECB |
| 1180:0832 | 1179:ff1c | Ricoh      | R5C832 IEEE 1394 Controller  | 22    | firewir... | 8B7FBF3DE6 |
| 1180:0832 | 1179:ff1e | Ricoh      | R5C832 IEEE 1394 Controller  | 22    | firewir... | 37B42247F5 |
| 1180:0832 | 17aa:2109 | Ricoh      | R5C832 IEEE 1394 Controller  | 22    | firewir... | E6E9C572A0 |
| 1217:00f7 | 1028:01fe | O2 Micro   | Firewire (IEEE 1394)         | 22    | firewir... | 4D9D478FFC |
| 197b:2380 | 103c:179c | JMicron... | IEEE 1394 Host Controller    | 22    | firewir... | 687AED65CF |
| 1180:0832 | 103c:30c5 | Ricoh      | R5C832 IEEE 1394 Controller  | 21    | firewir... | F11CC3529C |
| 1180:0832 | 1043:1317 | Ricoh      | R5C832 IEEE 1394 Controller  | 21    | firewir... | A4CF3B1E1D |
| 1180:e832 | 1028:0429 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 21    | firewir... | 5D8F94313F |
| 11c1:5811 | 103c:130a | LSI        | FW322/323 [TrueFire] 1394... | 21    | firewir... | EE9A2DA17C |
| 1180:0832 | 103c:30be | Ricoh      | R5C832 IEEE 1394 Controller  | 20    | firewir... | 5910FA85E5 |
| 1217:00f7 | 10cf:14d7 | O2 Micro   | Firewire (IEEE 1394)         | 20    | firewir... | F220F9AC45 |
| 197b:2380 | 103c:1631 | JMicron... | IEEE 1394 Host Controller    | 20    | firewir... | ADA2C0663B |
| 197b:2380 | 103c:176b | JMicron... | IEEE 1394 Host Controller    | 20    | firewir... | 1125997CC5 |
| 104c:8023 | 8086:4257 | Texas I... | TSB43AB22A IEEE-1394a-200... | 19    | firewir... | A760607F4E |
| 104c:8024 | 1019:8056 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 19    | firewir... | 1B1266E526 |
| 1180:0832 | 1043:1897 | Ricoh      | R5C832 IEEE 1394 Controller  | 19    | firewir... | 8ABF85E052 |
| 1180:e832 | 104d:9089 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 19    | firewir... | 5E0B431CB8 |
| 11c1:5811 | 1028:5811 | LSI        | FW322/323 [TrueFire] 1394... | 19    | firewir... | ACE51E66CB |

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
| 1524:0510 | 1524:0510 | ENE Tec... | CB710 Memory Card Reader ... | 3     | cb710      | 1312407631 |
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
| 1524:0510 | 1043:1724 | ENE Tec... | CB710 Memory Card Reader ... | 1     | cb710      | 9FE6163CA2 |
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
| 1022:1451 | 1022:1451 | AMD        | Family 17h (Models 00h-0f... | 1244  |            | D88D9DB618 |
| 1022:1577 | 1022:1577 | AMD        | Family 15h (Models 60h-6f... | 498   |            | 3EA595A278 |
| 1002:5a23 | 1002:5a23 | AMD        | RD890S/RD990 I/O Memory M... | 423   |            | 77FCB9CF4A |
| 1022:1419 | 1022:1419 | AMD        | Family 15h (Models 10h-1f... | 233   |            | E03FD39AD4 |
| 1002:5a23 | 1462:7693 | AMD        | RD890S/RD990 I/O Memory M... | 134   |            | D0FD1CE0E8 |
| 1022:1423 | 1022:1423 | AMD        | Family 15h (Models 30h-3f... | 80    |            | C22E6D8669 |
| 1022:1419 | 1462:7721 | AMD        | Family 15h (Models 10h-1f... | 50    |            | A9971ED939 |
| 1022:1423 | 1462:7721 | AMD        | Family 15h (Models 30h-3f... | 37    |            | 01C5E2E798 |
| 1022:1577 | 103c:8331 | AMD        | Family 15h (Models 60h-6f... | 26    |            | 30C73729A4 |
| 1022:1423 | 1043:85cb | AMD        | Family 15h (Models 30h-3f... | 19    |            | 8961CA91B3 |
| 1002:5a23 | 1462:7640 | AMD        | RD890S/RD990 I/O Memory M... | 16    |            | 3AB1CD59AE |
| 1002:5a23 | 1458:5000 | AMD        | RD890S/RD990 I/O Memory M... | 15    |            | AB87264048 |
| 1022:1419 | 1462:7895 | AMD        | Family 15h (Models 10h-1f... | 15    |            | 4DC951C5ED |
| 1022:1577 | 103c:81fa | AMD        | Family 15h (Models 60h-6f... | 13    |            | E11B01BA52 |
| 1002:5a23 | 1462:7974 | AMD        | RD890S/RD990 I/O Memory M... | 10    |            | 9DB62B42E7 |
| 1022:1419 | 1043:8526 | AMD        | Family 15h (Models 10h-1f... | 7     |            | 4482A1FB69 |
| 1022:1423 | 103c:812f | AMD        | Family 15h (Models 30h-3f... | 7     |            | 59A4CFC209 |
| 1022:1423 | 1462:7895 | AMD        | Family 15h (Models 30h-3f... | 7     |            | 09A88027C8 |
| 1022:1577 | 103c:80b5 | AMD        | Family 15h (Models 60h-6f... | 7     |            | 9193175B26 |
| 1022:1419 | 1019:7c8d | AMD        | Family 15h (Models 10h-1f... | 4     |            | F04221E5DE |
| 1022:1419 | 1025:070b | AMD        | Family 15h (Models 10h-1f... | 4     |            | C87047835B |
| 1022:1419 | 1462:7900 | AMD        | Family 15h (Models 10h-1f... | 3     |            | 6F21980996 |
| 1022:1577 | 103c:80b6 | AMD        | Family 15h (Models 60h-6f... | 2     |            | BEA3C73273 |
| 1022:1577 | 103c:8355 | AMD        | Family 15h (Models 60h-6f... | 2     |            | D6F5348EC7 |
| 8086:19a2 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 2     | pcieport   | 40E07B4DAD |
| 8086:19a2 | 8086:19a2 | Intel      | Atom Processor C3000 Seri... | 2     |            | 50B6A72C0C |
| 1022:1419 | 17aa:36a0 | AMD        | Family 15h (Models 10h-1f... | 1     |            | BA1A484E84 |
| 1022:1423 | 1462:7793 | AMD        | Family 15h (Models 30h-3f... | 1     |            | 54040FA02B |
| 1022:1423 | 17aa:368f | AMD        | Family 15h (Models 30h-3f... | 1     |            | 58DDD6F565 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 522   | i915       | 1B5E908CFF |
| 8086:0412 | 1458:d000 | Intel      | Xeon E3-1200 v3/4th Gen C... | 394   | i915       | E187B3F207 |
| 10de:128b | 1462:8c93 | Nvidia     | GK208B [GeForce GT 710]      | 355   | nouveau    | F7E3CD3E35 |
| 8086:0412 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 273   | i915       | 0D40DAA834 |
| 1002:67df | 1da2:e366 | AMD        | Ellesmere [Radeon RX 470/... | 221   | amdgpu     | 2E1659CD91 |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics 500              | 211   | i915       | 71A92492E3 |
| 8086:0102 | 1043:844d | Intel      | 2nd Generation Core Proce... | 202   | i915       | E6F55FAAD0 |
| 8086:0046 | 17aa:215a | Intel      | Core Processor Integrated... | 195   | i915       | D86D3E8984 |
| 8086:0102 | 1458:d000 | Intel      | 2nd Generation Core Proce... | 188   | i915       | 1237BE5BD5 |
| 8086:2a42 | 17aa:20e4 | Intel      | Mobile 4 Series Chipset I... | 187   | i915       | DB936567F0 |
| 8086:2a43 | 17aa:20e4 | Intel      | Mobile 4 Series Chipset I... | 187   |            | DB936567F0 |
| 1002:9616 | 1043:8388 | AMD        | RS780L [Radeon 3000]         | 178   | radeon     | EF97789A6A |
| 1002:15d8 | 1002:15d8 | AMD        | Picasso                      | 176   | amdgpu     | E5421C72D4 |
| 8086:0f31 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 163   | i915       | E789EA6881 |
| 1002:15dd | 1002:15dd | AMD        | Raven Ridge [Radeon Vega ... | 162   | amdgpu     | FCFE2F037F |
| 8086:1912 | 1043:8694 | Intel      | HD Graphics 530              | 160   | i915       | 8AB1F1C2CF |
| 8086:0152 | 1458:d000 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 157   | i915       | E88DE55691 |
| 1002:67df | 1682:c580 | AMD        | Ellesmere [Radeon RX 470/... | 142   | amdgpu     | 11EBF0D551 |
| 8086:0166 | 17aa:21f3 | Intel      | 3rd Gen Core processor Gr... | 141   | i915       | C9503690D6 |
| 8086:a011 | 1043:83ac | Intel      | Atom Processor D4xx/D5xx/... | 139   | i915       | 2117F02A4F |
| 8086:a012 | 1043:83ac | Intel      | Atom Processor D4xx/D5xx/... | 139   |            | 2117F02A4F |
| 10de:0a65 |           | Nvidia     | GT218 [GeForce 210]          | 137   | nouveau    | 5E2CE09E63 |
| 8086:5912 | 1043:8694 | Intel      | HD Graphics 630              | 135   | i915       | 11EBF0D551 |
| 1002:67df | 1da2:e353 | AMD        | Ellesmere [Radeon RX 470/... | 133   | amdgpu     | 77FCB9CF4A |
| 8086:0166 | 17aa:21fa | Intel      | 3rd Gen Core processor Gr... | 133   | i915       | 50D562CAB5 |
| 8086:29c2 | 1043:82b0 | Intel      | 82G33/G31 Express Integra... | 131   | i915       | 5889B752F5 |
| 10de:1c82 | 1462:8c96 | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 124   | nvidia     | C1BF9C169D |
| 8086:2e32 | 1043:836d | Intel      | 4 Series Chipset Integrat... | 123   | i915       | A4A1D08110 |
| 10de:1d01 | 1462:8c98 | Nvidia     | GP108 [GeForce GT 1030]      | 122   | nvidia     | 229B36F7F9 |
| 8086:2a42 | 1043:1862 | Intel      | Mobile 4 Series Chipset I... | 121   | i915       | 498362846A |
| 8086:2a43 | 1043:1862 | Intel      | Mobile 4 Series Chipset I... | 121   |            | 498362846A |
| 8086:3185 | 8086:2212 | Intel      | GeminiLake [UHD Graphics ... | 120   | i915       | 021617B9A0 |
| 8086:3e9b | 1025:1331 | Intel      | CoffeeLake-H GT2 [UHD Gra... | 119   | i915       | 38688703F4 |
| 10de:03d6 | 1849:03d6 | Nvidia     | C61 [GeForce 7025 / nForc... | 118   | nouveau    | 0B81DF184D |
| 1002:9616 | 1458:d000 | AMD        | RS780L [Radeon 3000]         | 117   | radeon     | 765CD8D9A0 |
| 8086:0166 | 17aa:3977 | Intel      | 3rd Gen Core processor Gr... | 117   | i915       | 2ACA6CD805 |
| 8086:3ea5 | 8086:2074 | Intel      | CoffeeLake-U GT3e [Iris P... | 116   | i915       | 7CA350189C |
| 1002:67df | 1462:341b | AMD        | Ellesmere [Radeon RX 470/... | 115   | amdgpu     | DFA6B5B067 |
| 8086:0126 | 17aa:21ce | Intel      | 2nd Generation Core Proce... | 113   | i915       | 74547808D3 |
| 8086:3e9b | 1028:0905 | Intel      | CoffeeLake-H GT2 [UHD Gra... | 113   | i915       | 9CDE952049 |
| 8086:0166 | 1028:0534 | Intel      | 3rd Gen Core processor Gr... | 109   | i915       | 98420A7D92 |
| 10de:0640 |           | Nvidia     | G96C [GeForce 9500 GT]       | 108   | nouveau    | AAB06F55BD |
| 8086:0a16 | 17aa:220c | Intel      | Haswell-ULT Integrated Gr... | 108   | i915       | 4C600416F9 |
| 1002:98e4 | 103c:8330 | AMD        | Stoney [Radeon R2/R3/R4/R... | 107   | amdgpu     | 5671BA2F85 |
| 8086:2a42 | 17aa:3a02 | Intel      | Mobile 4 Series Chipset I... | 107   | i915       | 1BBEC614AA |
| 8086:2a43 | 17aa:3a02 | Intel      | Mobile 4 Series Chipset I... | 107   |            | 1BBEC614AA |
| 10de:1f91 | 1028:0905 | Nvidia     | TU117M [GeForce GTX 1650 ... | 106   | nvidia     | 9CDE952049 |
| 8086:0106 | 1025:0649 | Intel      | 2nd Generation Core Proce... | 105   | i915       | ACE8491DE1 |
| 8086:0126 | 1028:0493 | Intel      | 2nd Generation Core Proce... | 105   | i915       | 33617DD1A8 |
| 8086:0152 | 1043:844d | Intel      | Xeon E3-1200 v2/3rd Gen C... | 105   | i915       | 7D2B37E6E1 |
| 8086:3185 | 1043:1261 | Intel      | GeminiLake [UHD Graphics ... | 105   | i915       | 170B220F5B |
| 10de:1f91 | 1025:1332 | Nvidia     | TU117M [GeForce GTX 1650 ... | 104   | nvidia     | 38688703F4 |
| 8086:0116 | 1025:0504 | Intel      | 2nd Generation Core Proce... | 104   | i915       | B420F25ED4 |
| 8086:0a16 | 17aa:3978 | Intel      | Haswell-ULT Integrated Gr... | 104   | i915       | 93B4F5B14E |
| 1002:15dd | 1043:876b | AMD        | Raven Ridge [Radeon Vega ... | 102   | amdgpu     | 3C83289B45 |
| 8086:a011 | 1025:0349 | Intel      | Atom Processor D4xx/D5xx/... | 102   | i915       | DA7BA5D53F |
| 8086:a012 | 1025:0349 | Intel      | Atom Processor D4xx/D5xx/... | 102   |            | DA7BA5D53F |
| 8086:0126 | 17aa:21da | Intel      | 2nd Generation Core Proce... | 100   | i915       | 660A6B9E20 |
| 8086:0162 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 99    | i915       | 92D06972E9 |
| 8086:0a16 | 103c:198f | Intel      | Haswell-ULT Integrated Gr... | 99    | i915       | 6573923D55 |
| 8086:2a02 | 17aa:20b5 | Intel      | Mobile GM965/GL960 Integr... | 99    | i915       | E1B3B6E090 |
| 8086:2a03 | 17aa:20b5 | Intel      | Mobile GM965/GL960 Integr... | 99    |            | E1B3B6E090 |
| 8086:0402 | 1458:d000 | Intel      | Xeon E3-1200 v3/4th Gen C... | 98    | i915       | 07FCF530F1 |
| 8086:29c2 | 1458:d000 | Intel      | 82G33/G31 Express Integra... | 98    | i915       | 17DB6D39FE |
| 8086:3e9b | 1028:087c | Intel      | CoffeeLake-H GT2 [UHD Gra... | 98    | i915       | 31A6F21CCD |
| 1002:67df | 1462:3418 | AMD        | Ellesmere [Radeon RX 470/... | 97    | amdgpu     | 84FDA964C3 |
| 8086:2e32 | 1458:d000 | Intel      | 4 Series Chipset Integrat... | 97    | i915       | 43A5D97DD3 |
| 8086:2a02 | 1025:011f | Intel      | Mobile GM965/GL960 Integr... | 96    | i915       | 2DA2F6A795 |
| 8086:2a03 | 1025:011f | Intel      | Mobile GM965/GL960 Integr... | 96    |            | 2DA2F6A795 |
| 10de:0622 |           | Nvidia     | G94 [GeForce 9600 GT]        | 95    | nouveau    | EC9321BD41 |
| 8086:3ea0 | 103c:8549 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 95    | i915       | 9A264DBCB2 |
| 8086:5917 | 1028:0810 | Intel      | UHD Graphics 620             | 95    | i915       | 2FD333BC52 |
| 8086:0166 | 1025:0647 | Intel      | 3rd Gen Core processor Gr... | 94    | i915       | A5268098B2 |
| 8086:1916 | 103c:8079 | Intel      | Skylake GT2 [HD Graphics ... | 94    | i915       | 0FA8058EEB |
| 8086:0a16 | 1025:0866 | Intel      | Haswell-ULT Integrated Gr... | 92    | i915       | 58B4832D53 |
| 8086:2a42 | 1028:02aa | Intel      | Mobile 4 Series Chipset I... | 92    | i915       | F0D0F92FD9 |
| 8086:2a43 | 1028:02aa | Intel      | Mobile 4 Series Chipset I... | 92    |            | F0D0F92FD9 |
| 10de:1c8c | 1028:087c | Nvidia     | GP107M [GeForce GTX 1050 ... | 91    | nvidia     | 31A6F21CCD |
| 8086:0166 | 1043:124d | Intel      | 3rd Gen Core processor Gr... | 91    | i915       | 08930695BC |
| 8086:0402 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 91    | i915       | EBA4D60B90 |
| 8086:2772 | 1043:817a | Intel      | 82945G/GZ Integrated Grap... | 91    | i915       | B40733E088 |
| 8086:0166 | 106b:00fa | Intel      | 3rd Gen Core processor Gr... | 90    | i915       | D82057AFA6 |
| 10de:0a65 | 1462:8094 | Nvidia     | GT218 [GeForce 210]          | 89    | nouveau    | 3814A57318 |
| 8086:0f31 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 89    | i915       | EB9AAA55EA |
| 10de:0de0 |           | Nvidia     | GF108 [GeForce GT 440]       | 88    | nouveau    | 773FC40103 |
| 8086:29c2 | 1849:29c2 | Intel      | 82G33/G31 Express Integra... | 88    | i915       | AF6E17AC8C |
| 8086:2e12 | 1028:0420 | Intel      | 4 Series Chipset Integrat... | 88    | i915       | 340184FB36 |
| 8086:2e13 | 1028:0420 | Intel      | 4 Series Chipset Integrat... | 88    |            | 340184FB36 |
| 8086:3ea0 | 17aa:2292 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 88    | i915       | FBF4582983 |
| 1002:15d8 | 1043:876b | AMD        | Picasso                      | 87    | amdgpu     | AB4B1B7A15 |
| 10de:0615 |           | Nvidia     | G92 [GeForce GTS 250]        | 87    | nvidia     | 55DF0FDEF1 |
| 8086:0046 | 1028:040a | Intel      | Core Processor Integrated... | 87    | i915       | 7E35C63842 |
| 8086:041e | 1043:8534 | Intel      | 4th Generation Core Proce... | 87    | i915       | 52FA7C5A31 |
| 8086:041e | 1458:d000 | Intel      | 4th Generation Core Proce... | 87    | i915       | DF13F72A9A |
| 8086:0152 | 1028:0577 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 86    | i915       | 4DAF9FDC0D |
| 8086:0f31 | 17aa:3909 | Intel      | Atom Processor Z36xxx/Z37... | 86    | i915       | BAC9935F0B |
| 8086:0152 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 85    | i915       | 6F05AEA2C1 |
| 8086:0166 | 1025:064b | Intel      | 3rd Gen Core processor Gr... | 85    | i915       | B732F94275 |
| 8086:0412 | 1849:0412 | Intel      | Xeon E3-1200 v3/4th Gen C... | 85    | i915       | 98BBC7AD66 |
| 8086:22b1 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 85    | i915       | CEDCA78B3A |

### Input device controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1102:7002 | 1102:0020 | Creativ... | SB Live! Game Port           | 162   | emu10k1_gp | 73BFADA83A |
| 1102:7003 | 1102:0040 | Creativ... | SB Audigy Game Port          | 123   | emu10k1_gp | A51030D9A0 |
| 1102:7003 | 1102:0060 | Creativ... | SB Audigy Game Port          | 27    | emu10k1_gp | 4970AA3AFB |
| 1102:7004 | 1102:1003 | Creativ... | [SB Live! Value] Input de... | 10    | emu10k1_gp | 1661F6766F |
| 1319:0802 | 1319:1319 | Fortemedia | Xwave QS3000A [FM801 game... | 8     | fm801_gp   | CE881D4659 |
| 1102:7005 | 1102:1002 | Creativ... | SB Audigy LS Game Port       | 1     | emu10k1_gp | A8AFE9E221 |
| 127a:4312 | 1235:4312 | Rockwel... | Riptide PCI Game Controller  | 1     | snd_rip... | 34867AD122 |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 1740  |            | F504E72617 |
| 1022:1481 | 1022:1481 | AMD        | Starship/Matisse IOMMU       | 890   |            | 0619809B36 |
| 1022:1451 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 695   |            | 115EC5ECA4 |
| 1022:1481 | 1043:87c0 | AMD        | Starship/Matisse IOMMU       | 572   |            | 97C17F738A |
| 1022:1631 | 1022:1631 | AMD        | Renoir IOMMU                 | 377   |            | DB4A212405 |
| 1022:1577 | 103c:8330 | AMD        | Family 15h (Models 60h-6f... | 107   |            | 5671BA2F85 |
| 1022:1481 | 1043:8808 | AMD        | Starship/Matisse IOMMU       | 82    |            | 20115EE05D |
| 1022:1481 | 1462:7c02 | AMD        | Starship/Matisse IOMMU       | 78    |            | A04EB698F8 |
| 1022:1577 | 103c:84ac | AMD        | Family 15h (Models 60h-6f... | 78    |            | D22A5E8410 |
| 1022:1577 | 1025:1192 | AMD        | Family 15h (Models 60h-6f... | 72    |            | CDC742CD03 |
| 1022:15d1 | 1043:876b | AMD        | Raven/Raven2 IOMMU           | 62    |            | AB4B1B7A15 |
| 1022:1631 | 17aa:5081 | AMD        | Renoir IOMMU                 | 60    |            | 6B6205BC5D |
| 1022:1631 | 17aa:3803 | AMD        | Renoir IOMMU                 | 59    |            | EA8B53C3DC |
| 1022:15d1 | 103c:84ae | AMD        | Raven/Raven2 IOMMU           | 56    |            | BFB71F53EC |
| 1022:15d1 | 1025:1366 | AMD        | Raven/Raven2 IOMMU           | 55    |            | CF7AB2CA73 |
| 1022:1631 | 17aa:507f | AMD        | Renoir IOMMU                 | 55    |            | 441E3AA589 |
| 1022:1451 | 1462:7c02 | AMD        | Family 17h (Models 00h-0f... | 50    |            | 2229C9E9F6 |
| 1022:1481 | 1462:7b86 | AMD        | Starship/Matisse IOMMU       | 49    |            | A42F5B4313 |
| 1022:15d1 | 1025:134d | AMD        | Raven/Raven2 IOMMU           | 49    |            | 479F0822FE |
| 1022:15d1 | 17aa:380a | AMD        | Raven/Raven2 IOMMU           | 49    |            | 6FE368312C |
| 1022:1577 | 17aa:380e | AMD        | Family 15h (Models 60h-6f... | 48    |            | 18D8EEC6A4 |
| 1022:1451 | 1462:7b86 | AMD        | Family 17h (Models 00h-0f... | 40    |            | 6787B45989 |
| 1022:1481 | 1462:7b89 | AMD        | Starship/Matisse IOMMU       | 37    |            | 43A19D8280 |
| 1022:15d1 | 1025:1259 | AMD        | Raven/Raven2 IOMMU           | 35    |            | 8DAB17C109 |
| 1022:15d1 | 103c:8615 | AMD        | Raven/Raven2 IOMMU           | 35    |            | 1FA0CB66B1 |
| 1022:15d1 | 17aa:380b | AMD        | Raven/Raven2 IOMMU           | 35    |            | 93286A0D38 |
| 1022:15d1 | 103c:84e7 | AMD        | Raven/Raven2 IOMMU           | 33    |            | D2AEC2F67A |
| 1022:15d1 | 103c:85ea | AMD        | Raven/Raven2 IOMMU           | 33    |            | D03BDBF1DA |
| 1022:1631 | 1d05:109f | AMD        | Renoir IOMMU                 | 33    |            | 69510C22F1 |
| 1022:15d1 | 17aa:3804 | AMD        | Raven/Raven2 IOMMU           | 32    |            | 008C187A8B |
| 1022:1481 | 1462:7c35 | AMD        | Starship/Matisse IOMMU       | 31    |            | A4D2088CC9 |
| 1022:15d1 | 103c:86fd | AMD        | Raven/Raven2 IOMMU           | 30    |            | 415E7E34D6 |
| 1022:1419 | 103c:1850 | AMD        | Family 15h (Models 10h-1f... | 29    |            | 3BDE7E8E11 |
| 1022:1631 | 17aa:5082 | AMD        | Renoir IOMMU                 | 29    |            | 12FFAAEFB1 |
| 1022:1631 | 1025:142b | AMD        | Renoir IOMMU                 | 28    |            | 5DCA660F7E |
| 1022:1631 | 103c:876f | AMD        | Renoir IOMMU                 | 27    |            | 08B513769D |
| 1022:1631 | 17aa:380a | AMD        | Renoir IOMMU                 | 27    |            | 99D22D0422 |
| 1022:1631 | 17aa:507e | AMD        | Renoir IOMMU                 | 27    |            | 31850CE796 |
| 1022:1451 | 1462:7a38 | AMD        | Family 17h (Models 00h-0f... | 26    |            | 00A14A97A2 |
| 1022:15d1 | 103c:85b3 | AMD        | Raven/Raven2 IOMMU           | 26    |            | 039DF57583 |
| 1022:15d1 | 17aa:3809 | AMD        | Raven/Raven2 IOMMU           | 26    |            | 57651669E3 |
| 1022:1631 | 103c:876e | AMD        | Renoir IOMMU                 | 26    |            | F77E2EBB10 |
| 1022:15d1 | 1025:125c | AMD        | Raven/Raven2 IOMMU           | 25    |            | FF512AC729 |
| 1022:1631 | 1025:1461 | AMD        | Renoir IOMMU                 | 24    |            | 8D643F3501 |
| 1022:1451 | 1462:7b89 | AMD        | Family 17h (Models 00h-0f... | 23    |            | 463432C55F |
| 1022:1577 | 1025:109f | AMD        | Family 15h (Models 60h-6f... | 23    |            | 70037BDDCB |
| 1022:15d1 | 1025:134f | AMD        | Raven/Raven2 IOMMU           | 23    |            | 3EC48C5388 |
| 1022:15d1 | 103c:85dd | AMD        | Raven/Raven2 IOMMU           | 22    |            | A93B2565DF |
| 1022:1577 | 103c:81f9 | AMD        | Family 15h (Models 60h-6f... | 20    |            | 2C2DFBF127 |
| 1022:1481 | 1462:7a38 | AMD        | Starship/Matisse IOMMU       | 19    |            | ABF17F0C92 |
| 1022:1481 | 1462:7b85 | AMD        | Starship/Matisse IOMMU       | 19    |            | DFA5C022B3 |
| 1022:15d1 | 103c:85e0 | AMD        | Raven/Raven2 IOMMU           | 19    |            | C740D1205B |
| 1022:1481 | 1043:87cb | AMD        | Starship/Matisse IOMMU       | 18    |            | 1F560968AB |
| 1022:1631 | 1043:87e1 | AMD        | Renoir IOMMU                 | 18    |            | D8274A2024 |
| 1022:1481 | 1462:7c95 | AMD        | Starship/Matisse IOMMU       | 17    |            | 4A568F856E |
| 1022:15d1 | 103c:85de | AMD        | Raven/Raven2 IOMMU           | 17    |            | 9E86C8EDE5 |
| 1022:1481 | 1462:7c94 | AMD        | Starship/Matisse IOMMU       | 16    |            | 640C5ADFC3 |
| 1022:15d1 | 1025:1456 | AMD        | Raven/Raven2 IOMMU           | 16    |            | 80CF3DC8E7 |
| 1022:1577 | 1028:087e | AMD        | Family 15h (Models 60h-6f... | 15    |            | 4B05B65D0E |
| 1022:1577 | 103c:84d0 | AMD        | Family 15h (Models 60h-6f... | 15    |            | C0651C40DC |
| 1022:15d1 | 103c:83c6 | AMD        | Raven/Raven2 IOMMU           | 15    |            | 168717D052 |
| 1022:1631 | 17aa:3808 | AMD        | Renoir IOMMU                 | 15    |            | CB9D7D7035 |
| 1022:1631 | 1d05:1100 | AMD        | Renoir IOMMU                 | 15    |            | 60D8A6B854 |
| 1022:15d1 | 103c:8496 | AMD        | Raven/Raven2 IOMMU           | 14    |            | 8A63E2E055 |
| 1022:1631 | 1e83:3e33 | AMD        | Renoir IOMMU                 | 14    |            | 3F2AA0EB97 |
| 1022:1451 | 1462:7b85 | AMD        | Family 17h (Models 00h-0f... | 13    |            | 8176B777B9 |
| 1022:15d1 | 1028:0812 | AMD        | Raven/Raven2 IOMMU           | 13    |            | E558F0ABB0 |
| 1022:15d1 | 103c:8497 | AMD        | Raven/Raven2 IOMMU           | 13    |            | 2910A4173E |
| 1022:1631 | 1028:09f5 | AMD        | Renoir IOMMU                 | 13    |            | 706D306B5E |
| 1022:1451 | 1028:07ee | AMD        | Family 17h (Models 00h-0f... | 12    |            | 38CD4647D5 |
| 1022:1481 | 1558:50f0 | AMD        | Starship/Matisse IOMMU       | 12    |            | B34A66FE8D |
| 1022:1577 | 103c:84a0 | AMD        | Family 15h (Models 60h-6f... | 12    |            | D7EB86C002 |
| 1022:1577 | 103c:85bb | AMD        | Family 15h (Models 60h-6f... | 12    |            | 9948FD64F4 |
| 1022:1577 | 17aa:380d | AMD        | Family 15h (Models 60h-6f... | 12    |            | 4CCF4659D4 |
| 1022:15d1 | 103c:84d2 | AMD        | Raven/Raven2 IOMMU           | 12    |            | C66066FF6B |
| 1022:1631 | 17aa:380d | AMD        | Renoir IOMMU                 | 12    |            | 51C5D13230 |
| 1022:1577 | 1028:0769 | AMD        | Family 15h (Models 60h-6f... | 11    |            | 8F75EDA1DE |
| 1022:1577 | 103c:8333 | AMD        | Family 15h (Models 60h-6f... | 11    |            | 8911FC397F |
| 1022:1577 | 103c:8345 | AMD        | Family 15h (Models 60h-6f... | 11    |            | B2207B19C0 |
| 1022:1577 | 17aa:364f | AMD        | Family 15h (Models 60h-6f... | 11    |            | 973E323F3C |
| 1022:15d1 | 103c:879e | AMD        | Raven/Raven2 IOMMU           | 11    |            | 61A5B2ED1E |
| 1022:1423 | 17aa:36a0 | AMD        | Family 15h (Models 30h-3f... | 10    |            | 762E9BD18E |
| 1022:1481 | 1043:87e2 | AMD        | Starship/Matisse IOMMU       | 10    |            | 76267FCBDA |
| 1022:1481 | 1462:7a40 | AMD        | Starship/Matisse IOMMU       | 10    |            | B2B10D4380 |
| 1022:1577 | 1025:1099 | AMD        | Family 15h (Models 60h-6f... | 10    |            | 16D7B82A2C |
| 1022:1577 | 103c:8324 | AMD        | Family 15h (Models 60h-6f... | 10    |            | 18175DDCCD |
| 1022:15d1 | 103c:86d5 | AMD        | Raven/Raven2 IOMMU           | 10    |            | 209887E993 |
| 1022:15d1 | 1025:1233 | AMD        | Raven/Raven2 IOMMU           | 9     |            | 6ADFA9E5CD |
| 1022:1631 | 103c:8786 | AMD        | Renoir IOMMU                 | 9     |            | 3F4BBD14BA |
| 1022:1631 | 103c:87b1 | AMD        | Renoir IOMMU                 | 9     |            | E1CF7F4599 |
| 1022:1631 | 1d72:1953 | AMD        | Renoir IOMMU                 | 9     |            | 7139D19A98 |
| 1022:1423 | 103c:2215 | AMD        | Family 15h (Models 30h-3f... | 8     |            | BAEFDA0ADA |
| 1022:1577 | 1025:1362 | AMD        | Family 15h (Models 60h-6f... | 8     |            | 6DB45D962D |
| 1022:1577 | 103c:84ad | AMD        | Family 15h (Models 60h-6f... | 8     |            | EB0E17A039 |
| 1022:1577 | 1043:8719 | AMD        | Family 15h (Models 60h-6f... | 8     |            | 8A607B7D4E |
| 1022:15d1 | 1028:08d7 | AMD        | Raven/Raven2 IOMMU           | 8     |            | DB16E945BB |
| 1022:15d1 | 103c:8706 | AMD        | Raven/Raven2 IOMMU           | 8     |            | F0EEC3E2AA |
| 1022:1423 | 1025:0904 | AMD        | Family 15h (Models 30h-3f... | 7     |            | 77B62F0563 |
| 1022:1451 | 1462:7a40 | AMD        | Family 17h (Models 00h-0f... | 7     |            | BD8CB19ABD |
| 1022:1577 | 1025:1087 | AMD        | Family 15h (Models 60h-6f... | 7     |            | 34AA3DCA40 |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816c | 17aa:5081 | Realtek... | RTL8111xP IPMI interface     | 58    |            | 6B6205BC5D |
| 10ec:816c | 17aa:5082 | Realtek... | RTL8111xP IPMI interface     | 25    |            | 12FFAAEFB1 |
| 10ec:816c | 17aa:5125 | Realtek... | RTL8111xP IPMI interface     | 25    |            | 452DD792F1 |
| 10ec:816c | 17aa:5126 | Realtek... | RTL8111xP IPMI interface     | 24    |            | 7065F7BB74 |
| 10ec:816c | 17aa:507e | Realtek... | RTL8111xP IPMI interface     | 21    |            | 31850CE796 |
| 10ec:816c | 17aa:5122 | Realtek... | RTL8111xP IPMI interface     | 12    |            | 0293EF3352 |
| 10ec:816c | 1043:85b5 | Realtek... | RTL8111xP IPMI interface     | 10    |            | 79EEA28A8B |
| 10ec:816c | 103c:8584 | Realtek... | RTL8111xP IPMI interface     | 8     |            | 3BF39BAC3E |
| 10ec:816c | 103c:83d5 | Realtek... | RTL8111xP IPMI interface     | 7     |            | 21422647B7 |
| 10ec:816c | 103c:8464 | Realtek... | RTL8111xP IPMI interface     | 4     |            | A112F2F435 |
| 10ec:816c | 10ec:0123 | Realtek... | RTL8111xP IPMI interface     | 4     |            | C1C5847225 |
| 10ec:816c | 17aa:3151 | Realtek... | RTL8111xP IPMI interface     | 4     |            | E57DFE6F39 |
| 10ec:816c | 1025:1248 | Realtek... | RTL8111xP IPMI interface     | 3     |            | E3FB43377E |
| 10ec:816c | 103c:8401 | Realtek... | RTL8111xP IPMI interface     | 3     |            | 8167AD2172 |
| 10ec:816c | 103c:8589 | Realtek... | RTL8111xP IPMI interface     | 3     |            | FA3E3FF217 |
| 10ec:816c | 17aa:5123 | Realtek... | RTL8111xP IPMI interface     | 3     |            | 516554B4E7 |
| 10ec:816c | 1849:8168 | Realtek... | RTL8111xP IPMI interface     | 3     | ipmi_si    | 417BCCCFA6 |
| 10ec:816c | 1019:81ea | Realtek... | RTL8111xP IPMI interface     | 2     |            | D0D02802AF |
| 10ec:816c | 1025:080a | Realtek... | RTL8111xP IPMI interface     | 2     |            | D5413884E0 |
| 10ec:816c | 1025:1290 | Realtek... | RTL8111xP IPMI interface     | 2     |            | A27363041A |
| 10ec:816c | 103c:8461 | Realtek... | RTL8111xP IPMI interface     | 2     |            | 991B8A8A71 |
| 10ec:816c | 103c:8618 | Realtek... | RTL8111xP IPMI interface     | 2     |            | A021BE4E84 |
| 10ec:816c | 17aa:30fd | Realtek... | RTL8111xP IPMI interface     | 2     |            | 5F6F9A1C6C |
| 10ec:816c | 17aa:511e | Realtek... | RTL8111xP IPMI interface     | 2     |            | C58E41C382 |
| 10ec:816c | 1025:078d | Realtek... | RTL8111xP IPMI interface     | 1     |            | 504EC0D230 |
| 10ec:816c | 1025:1005 | Realtek... | RTL8111xP IPMI interface     | 1     |            | 8A65F68E82 |
| 10ec:816c | 1025:1180 | Realtek... | RTL8111xP IPMI interface     | 1     |            | F1BB2896EE |
| 10ec:816c | 1025:124c | Realtek... | RTL8111xP IPMI interface     | 1     |            | 8EB6F7795D |
| 10ec:816c | 1025:1291 | Realtek... | RTL8111xP IPMI interface     | 1     |            | 866F2F8C49 |
| 10ec:816c | 103c:83da | Realtek... | RTL8111xP IPMI interface     | 1     |            | F0FD278615 |
| 10ec:816c | 103c:8523 | Realtek... | RTL8111xP IPMI interface     | 1     |            | BAB721D52E |
| 10ec:816c | 103c:8626 | Realtek... | RTL8111xP IPMI interface     | 1     |            | 9BC7D6303D |
| 10ec:816c | 1734:1216 | Realtek... | RTL8111xP IPMI interface     | 1     |            | A960AEF3AE |
| 10ec:816c | 17aa:3141 | Realtek... | RTL8111xP IPMI interface     | 1     |            | F19B15E3D2 |
| 10ec:816c | 17aa:3181 | Realtek... | RTL8111xP IPMI interface     | 1     |            | A203CD8C57 |
| 10ec:816c | 17aa:511f | Realtek... | RTL8111xP IPMI interface     | 1     |            | E0363562B7 |
| 10ec:816c | 1b0a:00e5 | Realtek... | RTL8111xP IPMI interface     | 1     |            | 3DA36F7282 |
| 8086:108e | 1734:108d | Intel      | 82573E KCS (Active Manage... | 1     | ipmi_si    | CCA0170CC9 |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 103c:3302 | 103c:3305 | Hewlett... | Integrated Lights-Out Sta... | 36    | ipmi_si    | 2ED58CCD22 |
| 10ec:816c | 10ec:8168 | Realtek... | RTL8111xP IPMI interface     | 19    | ipmi_si    | 6E60025AC5 |
| 10ec:816c | 1458:e000 | Realtek... | RTL8111xP IPMI interface     | 10    | ipmi_si    | 4B79994619 |
| 10ec:816c | 17aa:3089 | Realtek... | RTL8111xP IPMI interface     | 9     | ipmi_si    | 7D4224DF3F |
| 10ec:816c | 1734:1178 | Realtek... | RTL8111xP IPMI interface     | 7     | ipmi_si    | CD168F769A |
| 10ec:816c | 17aa:3130 | Realtek... | RTL8111xP IPMI interface     | 7     |            | DBFBDEA28F |
| 8086:108e | 8086:0000 | Intel      | 82573E KCS (Active Manage... | 6     | ipmi_si    | 82933CDF0E |
| 10ec:816c | 1025:078b | Realtek... | RTL8111xP IPMI interface     | 4     |            | FD387BD03F |
| 10ec:816c | 1043:8578 | Realtek... | RTL8111xP IPMI interface     | 1     | ipmi_si    | C248800623 |
| 10ec:816c | 10ec:816c | Realtek... | RTL8111xP IPMI interface     | 1     |            | 1830DAEFB4 |
| 10ec:816c | 17aa:30b2 | Realtek... | RTL8111xP IPMI interface     | 1     | ipmi_si    | 36635F76F9 |

### Isdn adapter (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1244:0e00 | 1244:0e00 | AVM        | Fritz!Card PCI v2.0 ISDN     | 9     | fcpci      | 1A5051E686 |
| 1244:0a00 | 1244:0a00 | AVM        | A1 ISDN [Fritz]              | 8     | fcpci      | AF06884158 |
| 1133:e00b | 1133:e00b | Dialogic   | Diva ISDN PCI 2.02           | 1     |            | AC7FD78AB8 |
| 1397:2bd0 | 1397:2bd0 | Cologne... | ISDN network controller [... | 1     | hfcpci     | 83A7C8B23F |
| e159:0001 | 795e:0001 | Tiger J... | Tiger3XX Modem/ISDN inter... | 1     | wcte11xp   | FE13415AC0 |
| e159:0001 | 79fe:0001 | Tiger J... | Tiger3XX Modem/ISDN inter... | 1     | wcte11xp   | B6E88B98F7 |
| e159:0001 | 9100:0001 | Tiger J... | Tiger3XX Modem/ISDN inter... | 1     | netjet     | 74F31779A2 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a36f | 8086:7270 | Intel      | Cannon Lake PCH Shared SRAM  | 1036  |            | 3D0DA576B8 |
| 8086:a121 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 650   |            | 11EBF0D551 |
| 10de:03f5 | 1849:03eb | Nvidia     | MCP61 Memory Controller      | 397   |            | 615502E93E |
| 8086:a2a1 | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 391   |            | 2696477C0C |
| 8086:a2a1 | 1458:5001 | Intel      | 200 Series/Z370 Chipset F... | 364   |            | F91A20DD51 |
| 10de:03e2 | 1849:03e2 | Nvidia     | MCP61 Host Bridge            | 363   |            | 615502E93E |
| 8086:a121 | 1458:5001 | Intel      | 100 Series/C230 Series Ch... | 358   |            | 213A5CCCC3 |
| 8086:9def | 8086:7270 | Intel      | Cannon Point-LP Shared SRAM  | 313   |            | 6AFF8771B1 |
| 8086:a36f | 1043:8694 | Intel      | Cannon Lake PCH Shared SRAM  | 301   |            | 36EBF65D44 |
| 8086:9d21 | 8086:7270 | Intel      | Sunrise Point-LP PMC         | 262   | intel_p... | 1AB69568A5 |
| 8086:9def |           | Intel      | Cannon Point-LP Shared SRAM  | 228   |            | 62C94909C7 |
| 10de:0a88 |           | Nvidia     | MCP79 Memory Controller      | 226   |            | F982A2F6CC |
| 10de:0a89 |           | Nvidia     | MCP79 Memory Controller      | 211   |            | F982A2F6CC |
| 10de:0aa4 |           | Nvidia     | MCP79 Memory Controller      | 210   |            | F982A2F6CC |
| 10de:0a98 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 202   |            | F982A2F6CC |
| 10de:03f5 | 1458:0c11 | Nvidia     | MCP61 Memory Controller      | 195   |            | FB1E012F68 |
| 8086:34ef |           | Intel      | Ice Lake-LP DRAM Controller  | 184   |            | FBBAF8088B |
| 8086:06ef | 8086:7270 | Intel      | Comet Lake PCH Shared SRAM   | 178   |            | 3A3BF28C3A |
| 8086:a121 | 1849:a121 | Intel      | 100 Series/C230 Series Ch... | 173   |            | 3A2A9BD626 |
| 8086:02ef | 8086:7270 | Intel      | Comet Lake PCH-LP Shared ... | 151   |            | 23182C745B |
| 8086:a2a1 | 1849:a2a1 | Intel      | 200 Series/Z370 Chipset F... | 146   |            | A8F84AEA94 |
| 10de:03e2 | 1043:83a4 | Nvidia     | MCP61 Host Bridge            | 144   |            | 1C28AB7987 |
| 10de:03f5 | 1043:83a4 | Nvidia     | MCP61 Memory Controller      | 144   |            | 1C28AB7987 |
| 8086:a2a1 | 1043:872f | Intel      | 200 Series/Z370 Chipset F... | 131   |            | C1BF9C169D |
| 8086:9d21 | 17aa:3872 | Intel      | Sunrise Point-LP PMC         | 123   |            | 19226582D9 |
| 10de:03ea | 10de:cb84 | Nvidia     | MCP61 Memory Controller      | 120   |            | 2537B06002 |
| 8086:a36f | 1025:1331 | Intel      | Cannon Lake PCH Shared SRAM  | 119   |            | 38688703F4 |
| 10de:03ea | 1043:8234 | Nvidia     | MCP61 Memory Controller      | 116   |            | A5CA2582B6 |
| 10de:03f5 | 1043:8234 | Nvidia     | MCP61 Memory Controller      | 116   |            | A5CA2582B6 |
| 8086:9def | 8086:2074 | Intel      | Cannon Point-LP Shared SRAM  | 116   |            | 7CA350189C |
| 8086:a36f | 1028:0905 | Intel      | Cannon Lake PCH Shared SRAM  | 113   |            | 9CDE952049 |
| 8086:02ef | 17aa:5079 | Intel      | Comet Lake PCH-LP Shared ... | 107   |            | 0BC4073D23 |
| 8086:9d21 | 1025:1193 | Intel      | Sunrise Point-LP PMC         | 105   | intel_p... | E922639FF6 |
| 8086:9d21 | 8086:9d21 | Intel      | Sunrise Point-LP PMC         | 104   | intel_p... | 02F641EA60 |
| 8086:a36f | 1849:a36f | Intel      | Cannon Lake PCH Shared SRAM  | 102   |            | 839B20476A |
| 10de:03ea | 1458:5001 | Nvidia     | MCP61 Memory Controller      | 101   |            | FB1E012F68 |
| 8086:a36f | 1028:087c | Intel      | Cannon Lake PCH Shared SRAM  | 98    |            | 31A6F21CCD |
| 8086:9d21 | 1028:0810 | Intel      | Sunrise Point-LP PMC         | 97    |            | 2FD333BC52 |
| 8086:9def | 17aa:2279 | Intel      | Cannon Point-LP Shared SRAM  | 96    |            | 2444839350 |
| 8086:9def | 103c:8549 | Intel      | Cannon Point-LP Shared SRAM  | 95    |            | 9A264DBCB2 |
| 10de:03e2 | 1458:5001 | Nvidia     | MCP61 Host Bridge            | 94    |            | 47DEFF8A39 |
| 8086:9d21 | 103c:8079 | Intel      | Sunrise Point-LP PMC         | 94    |            | 0FA8058EEB |
| 10de:005e | 1043:815a | Nvidia     | CK804 Memory Controller      | 90    |            | 00B830F623 |
| 8086:9d21 | 1043:12d1 | Intel      | Sunrise Point-LP PMC         | 89    | intel_p... | 570905286F |
| 8086:9d21 | 17aa:225d | Intel      | Sunrise Point-LP PMC         | 88    |            | BBA3BC97B7 |
| 8086:9d21 | 1028:07e6 | Intel      | Sunrise Point-LP PMC         | 83    | intel_p... | C2E884F793 |
| 8086:9def | 1028:08af | Intel      | Cannon Point-LP Shared SRAM  | 82    |            | 80857F497B |
| 8086:9d21 | 17aa:3845 | Intel      | Sunrise Point-LP PMC         | 80    |            | 0540D35606 |
| 8086:9d21 | 17aa:5068 | Intel      | Sunrise Point-LP PMC         | 79    |            | 893F642CBB |
| 10de:0a88 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 78    |            | 7A84F17BDB |
| 10de:0a89 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 78    |            | 7A84F17BDB |
| 8086:9d21 | 1028:078b | Intel      | Sunrise Point-LP PMC         | 78    |            | 4F60F64204 |
| 8086:02ef | 1028:0962 | Intel      | Comet Lake PCH-LP Shared ... | 77    |            | 9E26259821 |
| 8086:a121 | 1028:07be | Intel      | 100 Series/C230 Series Ch... | 76    |            | 6EE00932DC |
| 10de:0d68 |           | Nvidia     | MCP89 Memory Controller      | 75    |            | E3121B6209 |
| 10de:0d69 |           | Nvidia     | MCP89 Memory Controller      | 75    |            | E3121B6209 |
| 10de:0d6d |           | Nvidia     | MCP89 Memory Controller      | 75    |            | E3121B6209 |
| 10de:0d6e |           | Nvidia     | MCP89 Memory Controller      | 75    |            | E3121B6209 |
| 10de:0d6f |           | Nvidia     | MCP89 Memory Controller      | 75    |            | E3121B6209 |
| 10de:0d70 |           | Nvidia     | MCP89 Memory Controller      | 75    |            | E3121B6209 |
| 10de:0d71 |           | Nvidia     | MCP89 Memory Controller      | 75    |            | E3121B6209 |
| 10de:0d72 |           | Nvidia     | MCP89 Memory Controller      | 75    |            | E3121B6209 |
| 10de:0d75 |           | Nvidia     | MCP89 Memory Controller      | 75    |            | E3121B6209 |
| 10de:0d7b |           | Nvidia     | MCP89 Memory Controller      | 75    |            | E3121B6209 |
| 8086:9d21 | 1025:1295 | Intel      | Sunrise Point-LP PMC         | 75    |            | BEDAFBAD9B |
| 8086:a36f | 1025:1264 | Intel      | Cannon Lake PCH Shared SRAM  | 74    |            | 9971E42809 |
| 8086:9d21 | 17aa:225c | Intel      | Sunrise Point-LP PMC         | 73    |            | C33E7CED42 |
| 8086:9def | 8086:9def | Intel      | Cannon Point-LP Shared SRAM  | 72    |            | 203BB4369E |
| 8086:9d21 | 103c:832a | Intel      | Sunrise Point-LP PMC         | 71    |            | A7BDFE8774 |
| 8086:a121 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 71    |            | 047EAD1D70 |
| 10de:03f5 | 1462:7309 | Nvidia     | MCP61 Memory Controller      | 70    |            | DC2D2CA478 |
| 8086:9d21 | 1025:115f | Intel      | Sunrise Point-LP PMC         | 69    | intel_p... | 9756CE58FC |
| 8086:9d21 | 103c:83b2 | Intel      | Sunrise Point-LP PMC         | 64    |            | EF516B4F37 |
| 8086:a121 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 64    |            | C007D839E7 |
| 10de:03f5 | 1565:3407 | Nvidia     | MCP61 Memory Controller      | 62    |            | FF6423FB29 |
| 10de:0568 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 62    |            | 739D1AE9B7 |
| 10de:0751 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 62    |            | 739D1AE9B7 |
| 10de:0754 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 62    |            | 739D1AE9B7 |
| 8086:06ef | 1043:8694 | Intel      | Comet Lake PCH Shared SRAM   | 61    |            | BBA08D40AD |
| 8086:9d21 | 103c:84a6 | Intel      | Sunrise Point-LP PMC         | 61    | intel_p... | 197CBC5A5D |
| 8086:9def | 17aa:3809 | Intel      | Cannon Point-LP Shared SRAM  | 61    |            | 2ED0E50384 |
| 8086:9d21 | 1028:081c | Intel      | Sunrise Point-LP PMC         | 60    |            | A92377CB2A |
| 8086:9d21 | 17aa:3816 | Intel      | Sunrise Point-LP PMC         | 60    |            | 74D1DA4B68 |
| 8086:a36f | 17aa:3804 | Intel      | Cannon Lake PCH Shared SRAM  | 60    |            | AB6647F9DA |
| 8086:9d21 | 17aa:3851 | Intel      | Sunrise Point-LP PMC         | 59    |            | E2D1740F3A |
| 8086:a36f |           | Intel      | Cannon Lake PCH Shared SRAM  | 59    |            | EB3D04E089 |
| 8086:9d21 | 17aa:2233 | Intel      | Sunrise Point-LP PMC         | 58    |            | 79D4310531 |
| 8086:9d21 | 8086:2068 | Intel      | Sunrise Point-LP PMC         | 58    |            | 38D5C55BD7 |
| 8086:9d21 | 1025:1085 | Intel      | Sunrise Point-LP PMC         | 57    | intel_p... | C16C3F3C20 |
| 8086:9d21 | 1028:075b | Intel      | Sunrise Point-LP PMC         | 57    |            | 97DBD7A2D0 |
| 8086:9d21 | 17aa:2258 | Intel      | Sunrise Point-LP PMC         | 57    |            | 00AA4C11F4 |
| 8086:9d21 | 1028:06b2 | Intel      | Sunrise Point-LP PMC         | 55    |            | 7AEC563171 |
| 10de:03a9 |           | Nvidia     | C55 Memory Controller        | 54    |            | 3965D087B0 |
| 10de:03aa |           | Nvidia     | C55 Memory Controller        | 54    |            | 3965D087B0 |
| 10de:03ab |           | Nvidia     | C55 Memory Controller        | 54    |            | 3965D087B0 |
| 10de:03b4 |           | Nvidia     | C55 Memory Controller        | 54    |            | 3965D087B0 |
| 10de:03bc |           | Nvidia     | C55 Memory Controller        | 54    |            | 3965D087B0 |
| 8086:02ef | 8086:2081 | Intel      | Comet Lake PCH-LP Shared ... | 54    |            | 92AA2017B9 |
| 8086:06ef | 1028:097d | Intel      | Comet Lake PCH Shared SRAM   | 54    |            | 8C072EA1C4 |
| 8086:9d21 | 1043:1d30 | Intel      | Sunrise Point-LP PMC         | 54    | intel_p... | 51577F00B4 |

### Modem (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:266d | 14f1:5423 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 27    | snd_int... | A35F6C0969 |
| 1057:3052 | 1057:3020 | Motorola   | SM56 Data Fax Modem          | 23    |            | 3A362598FB |
| 8086:266d | 1179:0001 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 19    | snd_int... | 67580C50DF |
| 1106:3068 |           | VIA Tec... | AC'97 Modem Controller       | 17    | snd_via... | E739F2F0BA |
| 11c1:044c | 11c1:044c | LSI        | LT WinModem                  | 14    |            | 34D12D37FD |
| 8086:24c6 | 14f1:5422 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 12    | snd_int... | 60A32F7736 |
| 1039:7013 | 1025:0083 | Silicon... | AC'97 Modem Controller       | 11    | snd_int... | 464DA49516 |
| 8086:266d | 1025:006a | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 10    | snd_int... | C23E462C42 |
| 8086:266d | 103c:099c | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 9     | snd_int... | 5F105DDA68 |
| 1039:7013 | 1043:1816 | Silicon... | AC'97 Modem Controller       | 8     | snd_int... | AA92B168C5 |
| 8086:266d | 1014:0574 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 8     | snd_int... | 3BE2271444 |
| 8086:266d | 103c:0944 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 8     | snd_int... | 7F042FAA64 |
| 1002:4378 | 103c:3085 | AMD        | IXP SB400 AC'97 Modem Con... | 7     | snd_ati... | 32F7B77B77 |
| 1002:4378 | 103c:3091 | AMD        | IXP SB400 AC'97 Modem Con... | 7     | snd_ati... | F01F51C47C |
| 8086:1040 | 8086:1000 | Intel      | 536EP Data Fax Modem         | 7     |            | F2CC8FAE4D |
| 8086:266d | 1025:0066 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 7     | snd_int... | 10A0D7E3A2 |
| 1002:4378 | 103c:30a4 | AMD        | IXP SB400 AC'97 Modem Con... | 5     | snd_ati... | C2A5CB93AA |
| 8086:24c6 | 1014:0524 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 5     | snd_int... | 71DAF2C5B4 |
| 8086:24c6 | 1014:055a | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 5     | snd_int... | 190737F754 |
| 8086:266d | 103c:3082 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 5     |            | C98B9CF200 |
| 1002:4378 | 103c:309b | AMD        | IXP SB400 AC'97 Modem Con... | 4     | snd_ati... | B64833B0B1 |
| 1002:4378 | 1043:1186 | AMD        | IXP SB400 AC'97 Modem Con... | 4     | snd_ati... | E298B642F1 |
| 1106:3068 | 1019:0c04 | VIA Tec... | AC'97 Modem Controller       | 4     | snd_via... | CAAB4A3B82 |
| 134d:7892 | 134d:0001 | PCTel      | HSP MicroModem 56            | 4     | serial     | 6C9B4F5E0B |
| 8086:266d | 1014:0576 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 4     | snd_int... | E323E5FE53 |
| 8086:266d | 103c:30c4 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 4     | snd_int... | FE8A07348F |
| 8086:266d | 1179:ff31 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 4     | snd_int... | 875478A51A |
| 8086:266d | 144d:2115 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 4     | snd_int... | D7EE30EC16 |
| 1002:434d | 144d:2115 | AMD        | SB200 AC97 Modem Controller  | 3     | snd_ati... | F72BBFF4B7 |
| 1002:4378 | 1025:007e | AMD        | IXP SB400 AC'97 Modem Con... | 3     | snd_ati... | 60873D0A0E |
| 1039:7013 | 1025:0082 | Silicon... | AC'97 Modem Controller       | 3     |            | EDF0363AFE |
| 1039:7013 | 1584:4003 | Silicon... | AC'97 Modem Controller       | 3     | snd_int... | E9BC9B3C8A |
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
| 11c1:0440 | 11c1:0440 | LSI        | 56k WinModem                 | 2     |            | 31EAA72C65 |
| 11c1:044e | 11c1:044e | LSI        | LT WinModem                  | 2     |            | DA6AB84289 |
| 11c1:044e | 1235:044e | LSI        | LT WinModem                  | 2     |            | C22EB5394A |
| 134d:7890 | 134d:0001 | PCTel      | HSP MicroModem 56            | 2     | serial     | 332DDF27C1 |
| 1543:3052 | 1543:3000 | SILICON... | Intel 537 [Winmodem]         | 2     |            | 6B3BFC1719 |
| 2003:8800 | 1801:2800 | Smart Link | LM-I56N                      | 2     |            | 62AFB6C0F6 |
| 8086:1080 | 1028:1000 | Intel      | FA82537EP 56K V.92 Data/F... | 2     | serial     | DC13BE448C |
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
| 1039:7013 | 104d:8128 | Silicon... | AC'97 Modem Controller       | 1     | snd_int... | 72A578315E |
| 1039:7013 | 1558:4201 | Silicon... | AC'97 Modem Controller       | 1     |            | 5B191FE82E |
| 1039:7013 | 1734:106c | Silicon... | AC'97 Modem Controller       | 1     |            | BFFEEEDE0D |
| 1057:3052 | 1631:3034 | Motorola   | SM56 Data Fax Modem          | 1     |            | B7CEC1644D |
| 10b9:5457 | 103c:0850 | ULi Ele... | M5457 AC'97 Modem Controller | 1     |            | 4E9D284D9C |
| 10b9:5457 | 10cf:130f | ULi Ele... | M5457 AC'97 Modem Controller | 1     |            | 347EB6B747 |
| 1106:3068 | 1019:2122 | VIA Tec... | AC'97 Modem Controller       | 1     | snd_via... | 25BB71984B |
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
| 11c1:0449 | 1468:0410 | LSI        | L56xM+S [Mars-2] WinModem... | 1     |            | A8A13EFBA0 |
| 11c1:044e | 13e0:0401 | LSI        | LT WinModem                  | 1     |            | E9ACA9663F |
| 11c1:0450 | 144f:1515 | LSI        | LT WinModem                  | 1     |            | 32D5B1A614 |
| 11c1:045c | 8086:2205 | LSI        | LT WinModem                  | 1     | serial     | 1B54E25E77 |
| 163c:3052 | 14fe:0005 | Smart Link | SmartLink SmartPCI562 56K... | 1     | serial     | 9939882441 |
| 2000:2800 | 122d:2800 | Smart Link | SmartPCI2800 V.92 PCI Sof... | 1     |            | 3BC558699A |
| 2000:2800 | 163c:2800 | Smart Link | SmartPCI2800 V.92 PCI Sof... | 1     |            | 9DEE04D2CB |
| 2003:8800 | 16ef:2800 | Smart Link | LM-I56N                      | 1     |            | 8B4AE6CF41 |
| 8086:1080 | 8086:1000 | Intel      | FA82537EP 56K V.92 Data/F... | 1     | serial     | 6DF95E6042 |
| 8086:2446 | 1025:1027 | Intel      | 82801BA/BAM AC'97 Modem C... | 1     |            | E0A83557FF |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 411   | intel_a... | 1B5E908CFF |
| 1022:15e2 | 1022:15e2 | AMD        | Raven/Raven2/FireFlight/R... | 404   | snd_pci... | F504E72617 |
| 14e4:1570 | 14e4:1570 | Broadcom   | 720p FaceTime HD Camera      | 226   | bdc_pci    | 1007726831 |
| 8086:1919 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 122   | ipu3_imgu  | 0E1D0B8D70 |
| 8086:9d32 | 8086:7270 | Intel      | CSI-2 Host Controller        | 113   | ipu3_cio2  | 0E1D0B8D70 |
| 8086:5a88 |           | Intel      | Celeron N3350/Pentium N42... | 69    |            | 902AD35DB3 |
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
| 1022:15e2 | 17aa:381b | AMD        | Raven/Raven2/FireFlight/R... | 46    | snd_pci... | 64A9E43743 |
| 1022:15e2 | 103c:8730 | AMD        | Raven/Raven2/FireFlight/R... | 41    | snd_pci... | FC1870A101 |
| 1022:15e2 | 1e21:1043 | AMD        | Raven/Raven2/FireFlight/R... | 40    | snd_pci... | BF2D71E7F2 |
| 1022:15e2 | 17aa:3807 | AMD        | Raven/Raven2/FireFlight/R... | 35    | snd_pci... | E7FDA6091A |
| 1022:15e2 | 17aa:3813 | AMD        | Raven/Raven2/FireFlight/R... | 35    | snd_pci... | 93286A0D38 |
| 1022:15e2 | 19e5:3e18 | AMD        | Raven/Raven2/FireFlight/R... | 35    | snd_pci... | 430907546B |
| 1022:15e2 | 103c:85ea | AMD        | Raven/Raven2/FireFlight/R... | 33    | snd_pci... | D03BDBF1DA |
| 1022:15e2 | 1d05:109f | AMD        | Raven/Raven2/FireFlight/R... | 33    | snd_pci... | 69510C22F1 |
| 8086:22b8 | 17aa:38e3 | Intel      | Atom/Celeron/Pentium Proc... | 31    | intel_a... | F21B55E1F7 |
| 1022:15e2 | 103c:86fd | AMD        | Raven/Raven2/FireFlight/R... | 30    | snd_pci... | 415E7E34D6 |
| 8086:22b8 | 17aa:3809 | Intel      | Atom/Celeron/Pentium Proc... | 29    | intel_a... | 4AC35C901A |
| 1022:15e2 | 1025:142b | AMD        | Raven/Raven2/FireFlight/R... | 28    | snd_pci... | 5DCA660F7E |
| 8086:22b8 | 103c:813e | Intel      | Atom/Celeron/Pentium Proc... | 28    | intel_a... | 71120B9356 |
| 1022:15e2 | 103c:8760 | AMD        | Raven/Raven2/FireFlight/R... | 27    | snd_pci... | 936E09E13C |
| 1022:15e2 | 103c:876f | AMD        | Raven/Raven2/FireFlight/R... | 27    | snd_pci... | 08B513769D |
| 1022:15e2 | 17aa:3822 | AMD        | Raven/Raven2/FireFlight/R... | 27    | snd_pci... | 99D22D0422 |
| 1022:15e2 | 17aa:507e | AMD        | Raven/Raven2/FireFlight/R... | 27    | snd_pci... | 31850CE796 |
| 1022:15e2 | 103c:85b3 | AMD        | Raven/Raven2/FireFlight/R... | 26    | snd_pci... | 039DF57583 |
| 1022:15e2 | 103c:876e | AMD        | Raven/Raven2/FireFlight/R... | 26    | snd_pci... | F77E2EBB10 |
| 1022:15e2 | 17aa:5125 | AMD        | Raven/Raven2/FireFlight/R... | 25    | snd_pci... | 452DD792F1 |
| 109e:0878 |           | Brooktree  | Bt878 Audio Capture          | 25    | bt878      | E739F2F0BA |
| 1022:15e2 | 1025:1461 | AMD        | Raven/Raven2/FireFlight/R... | 24    | snd_pci... | 8D643F3501 |
| 1022:15e2 | 1025:134f | AMD        | Raven/Raven2/FireFlight/R... | 23    | snd_pci... | 3EC48C5388 |
| 1022:15e2 | 103c:85dd | AMD        | Raven/Raven2/FireFlight/R... | 22    | snd_pci... | A93B2565DF |
| 1022:15e2 | 19e5:3e06 | AMD        | Raven/Raven2/FireFlight/R... | 22    | snd_pci... | 1797098345 |
| 8086:1919 | 8086:1919 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 22    | ipu3_imgu  | 5FE3179524 |
| 8086:22b8 | 1297:2063 | Intel      | Atom/Celeron/Pentium Proc... | 22    | intel_a... | D6AD6F67A7 |
| 1022:15e2 | 1a0e:1043 | AMD        | Raven/Raven2/FireFlight/R... | 21    | snd_pci... | B3DA27422D |
| 8086:9d32 |           | Intel      | CSI-2 Host Controller        | 21    | ipu3_cio2  | 6F018F175E |
| 8086:22b8 | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 20    | intel_a... | 83AE87648C |
| 1022:15e2 | 1025:1456 | AMD        | Raven/Raven2/FireFlight/R... | 18    | snd_pci... | 80CF3DC8E7 |
| 1022:15e2 | 17aa:5084 | AMD        | Raven/Raven2/FireFlight/R... | 18    | snd_pci... | 12FFAAEFB1 |
| 1022:15e2 | 19e5:3e14 | AMD        | Raven/Raven2/FireFlight/R... | 18    | snd_pci... | 2E6A9F05AC |
| 14e4:1615 | 14e4:1615 | Broadcom   | BCM70015 Video Decoder [C... | 18    | crystalhd  | 85DEF78A94 |
| 1022:15e2 | 103c:85de | AMD        | Raven/Raven2/FireFlight/R... | 17    | snd_pci... | 9E86C8EDE5 |
| 1022:15e2 | 17aa:3823 | AMD        | Raven/Raven2/FireFlight/R... | 17    | snd_pci... | F707B24713 |
| 8086:8a19 | 1028:08b0 | Intel      | Image Signal Processor       | 17    |            | 6B27A727BE |
| 8086:9d32 | 8086:9d32 | Intel      | CSI-2 Host Controller        | 17    | ipu3_cio2  | 5FE3179524 |
| 1022:15e2 | 103c:85e0 | AMD        | Raven/Raven2/FireFlight/R... | 16    | snd_pci... | C740D1205B |
| 11bd:bede | 11bd:0022 | Pinnacl... | AV/DV Studio Capture Card    | 16    |            | E4F384C278 |
| 8086:22b8 | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 16    | intel_a... | E5A8BA60CF |
| 8086:22b8 | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 16    | intel_a... | 0542145A63 |
| 1022:15e2 | 103c:8433 | AMD        | Raven/Raven2/FireFlight/R... | 15    | snd_pci... | 8670420E76 |
| 1022:15e2 | 17aa:380f | AMD        | Raven/Raven2/FireFlight/R... | 15    | snd_pci... | CB9D7D7035 |
| 1022:15e2 | 17aa:5127 | AMD        | Raven/Raven2/FireFlight/R... | 15    | snd_pci... | 7065F7BB74 |
| 1022:15e2 | 1e83:3e33 | AMD        | Raven/Raven2/FireFlight/R... | 14    | snd_pci... | 3F2AA0EB97 |
| 109e:0878 | 1461:0003 | Brooktree  | Bt878 Audio Capture          | 14    | snd_bt87x  | DCE0418111 |
| 1022:15e2 | 1028:09f5 | AMD        | Raven/Raven2/FireFlight/R... | 13    | snd_pci... | 706D306B5E |
| 1022:15e2 | 19e5:3e10 | AMD        | Raven/Raven2/FireFlight/R... | 13    | snd_pci... | 9C73A8D7D6 |
| 1131:7164 | 0070:8851 | Philips... | SAA7164                      | 13    | saa7164    | 3A3874784C |
| 1022:15e2 | 1025:1378 | AMD        | Raven/Raven2/FireFlight/R... | 12    | snd_pci... | DA566F34DD |
| 1022:15e2 | 103c:84d2 | AMD        | Raven/Raven2/FireFlight/R... | 12    | snd_pci... | C66066FF6B |
| 1022:15e2 | 17aa:380d | AMD        | Raven/Raven2/FireFlight/R... | 12    | snd_pci... | 51C5D13230 |
| 1022:15e2 | 17aa:381f | AMD        | Raven/Raven2/FireFlight/R... | 12    | snd_pci... | 2FE8E30909 |
| 1022:15e2 | 103c:8735 | AMD        | Raven/Raven2/FireFlight/R... | 11    | snd_pci... | F36EA99568 |
| 1022:15e2 | 103c:879e | AMD        | Raven/Raven2/FireFlight/R... | 11    | snd_pci... | 61A5B2ED1E |
| 1022:15e2 | 17aa:380b | AMD        | Raven/Raven2/FireFlight/R... | 11    | snd_pci... | 8B75181A08 |
| 8086:22b8 | 1043:1bdd | Intel      | Atom/Celeron/Pentium Proc... | 11    | intel_a... | 866C75D8E6 |
| 1022:15e2 | 103c:86d5 | AMD        | Raven/Raven2/FireFlight/R... | 10    | snd_pci... | 209887E993 |
| 1022:15e2 | 17aa:5126 | AMD        | Raven/Raven2/FireFlight/R... | 10    | snd_pci... | EB33727EFF |
| 1131:7160 | 1461:1455 | Philips... | SAA7160                      | 10    |            | 2D08F702CF |
| 1131:7231 | 1461:2a0f | Philips... | SAA7231                      | 10    |            | BEB8F313F7 |
| 8086:0f38 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 10    | intel_a... | AF354E922D |
| 1022:15e2 | 1025:1233 | AMD        | Raven/Raven2/FireFlight/R... | 9     | snd_pci... | 6ADFA9E5CD |
| 1022:15e2 | 103c:8786 | AMD        | Raven/Raven2/FireFlight/R... | 9     | snd_pci... | 3F4BBD14BA |
| 1022:15e2 | 103c:87b1 | AMD        | Raven/Raven2/FireFlight/R... | 9     | snd_pci... | E1CF7F4599 |
| 1022:15e2 | 1d72:1953 | AMD        | Raven/Raven2/FireFlight/R... | 9     | snd_pci... | 7139D19A98 |
| 109e:0878 | 0070:13eb | Brooktree  | Bt878 Audio Capture          | 9     | snd_bt87x  | A9C46A46ED |
| 8086:0f38 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 9     | intel_a... | 87E6D2F056 |
| 8086:1919 | 152d:1182 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 9     | ipu3_imgu  | 3EB69E8095 |
| 8086:8a19 | 8086:7270 | Intel      | Image Signal Processor       | 9     |            | 4265905516 |
| 1022:15e2 | 103c:8706 | AMD        | Raven/Raven2/FireFlight/R... | 8     | snd_pci... | F0EEC3E2AA |
| 1022:15e2 | 1462:12b5 | AMD        | Raven/Raven2/FireFlight/R... | 8     | snd_pci... | 649DBCEEFF |
| 1131:7231 | 16be:0008 | Philips... | SAA7231                      | 8     |            | 9D7D398CC1 |
| 1131:7231 | 5ace:8000 | Philips... | SAA7231                      | 8     |            | FA070462FC |
| 12ab:0380 | 1cfa:0006 | YUAN Hi... | Game Capture 4K60 Pro        | 8     |            | 7A840D41B2 |
| 14e4:1612 | 14e4:2612 | Broadcom   | BCM70012 Video Decoder [C... | 8     |            | 6FCADF1396 |
| 1822:4e35 | 153b:1178 | Twinhan... | Mantis DTV PCI Bridge Con... | 8     | mantis     | 6AC1485BC6 |
| 1822:4e35 | 1ae4:0003 | Twinhan... | Mantis DTV PCI Bridge Con... | 8     | mantis     | C98E498E71 |
| 8086:1919 | 1028:07a4 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 8     | ipu3_imgu  | C5396B5734 |
| 8086:1919 | 103c:80fc | Intel      | Xeon E3-1200 v5/E3-1500 v... | 8     | ipu3_imgu  | 09240A2A3F |
| 8086:22b8 | 1414:0009 | Intel      | Atom/Celeron/Pentium Proc... | 8     | intel_a... | 85D49B081C |
| 8086:9d32 | 1028:07a4 | Intel      | CSI-2 Host Controller        | 8     | ipu3_cio2  | C5396B5734 |
| 8086:9d32 | 103c:80fc | Intel      | CSI-2 Host Controller        | 8     | ipu3_cio2  | 09240A2A3F |

### Multiport serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1fd4:1999 | 1fd4:0002 | SUNIX      | Multiport serial controller  | 7     | serial     | DF6B2FA3DE |
| 135a:08c1 | 135a:0413 | Brain B... | Multiport serial controller  | 1     |            | 0F6EBD3E93 |
| 135c:0170 | 135c:0170 | Quatech    | QSCLP-100                    | 1     | serial     | 05DF269988 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8168 | 1458:e000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5209  | r8169      | E187B3F207 |
| 10ec:8168 | 1849:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2184  | r8169      | 87C40FCD51 |
| 10ec:8168 | 1043:8677 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1574  | r8169      | 5F1E86F753 |
| 10ec:8168 | 1043:8505 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1532  | r8169      | 8B10E96F42 |
| 10ec:8168 | 1043:200f | Realtek... | RTL8111/8168/8411 PCI Exp... | 1384  | r8169      | 08930695BC |
| 10ec:8168 | 1043:8432 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1157  | r8169      | 67B53F9BDB |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1100  | r8169      | B92F4485E6 |
| 8086:15b8 | 1043:8672 | Intel      | Ethernet Connection (2) I... | 648   | e1000e     | 11EBF0D551 |
| 10ec:8139 | 10ec:8139 | Realtek... | RTL-8100/8101L/8139 PCI F... | 645   | 8139too... | F8D3B991DA |
| 10ec:8168 | 1043:8554 | Realtek... | RTL8111/8168/8411 PCI Exp... | 637   | r8169      | 8961CA91B3 |
| 10ec:8168 | 1043:83a3 | Realtek... | RTL8111/8168/8411 PCI Exp... | 521   | r8169      | AC572EF424 |
| 10ec:8136 | 1043:200f | Realtek... | RTL810xE PCI Express Fast... | 494   | r8169      | DCD714D5FA |
| 10ec:8168 | 1043:859e | Realtek... | RTL8111/8168/8411 PCI Exp... | 396   | r8169      | 9A23DF55D8 |
| 14e4:16b5 | 1025:0647 | Broadcom   | NetLink BCM57785 Gigabit ... | 377   | tg3        | B732F94275 |
| 1969:1048 | 1043:8226 | Qualcom... | Attansic L1 Gigabit Ethernet | 348   | atl1       | 7165A5413A |
| 10ec:8168 | 1043:208f | Realtek... | RTL8111/8168/8411 PCI Exp... | 332   | r8169      | 3A3BF28C3A |
| 14e4:16b4 | 14e4:16b4 | Broadcom   | NetXtreme BCM57765 Gigabi... | 331   | tg3        | 7EBB0672C0 |
| 10ec:8136 | 10ec:0123 | Realtek... | RTL810xE PCI Express Fast... | 324   | r8169      | 8DFADF5EDB |
| 8086:15a1 | 1043:85c4 | Intel      | Ethernet Connection (2) I... | 301   | e1000e     | 8F3CA163E7 |
| 8086:15b8 | 1458:e000 | Intel      | Ethernet Connection (2) I... | 294   | e1000e     | 834A7AE73B |
| 1969:1083 | 1458:e000 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 287   | atl1c      | 89F6EB0671 |
| 10ec:8168 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 278   | r8169      | 39497CE3AE |
| 10ec:8168 | 7470:3468 | Realtek... | RTL8111/8168/8411 PCI Exp... | 277   | r8169      | 84D927D279 |
| 10ec:8169 | 10ec:8169 | Realtek... | RTL8169 PCI Gigabit Ether... | 269   | r8169      | 926229BE87 |
| 11ab:4364 | 1043:81f8 | Marvell... | 88E8056 PCI-E Gigabit Eth... | 262   | sky2       | 926229BE87 |
| 10ec:8168 | 1043:16d5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 252   | r8169      | 438D785F0E |
| 8086:15b8 | 1849:15b8 | Intel      | Ethernet Connection (2) I... | 233   | e1000e     | 2BE44DF65D |
| 10ec:8168 | 1043:82c6 | Realtek... | RTL8111/8168/8411 PCI Exp... | 228   | r8169      | 3B96E27283 |
| 10ec:8136 | 1849:8136 | Realtek... | RTL810xE PCI Express Fast... | 222   | r8169      | ADC801308B |
| 197b:0250 | 1043:1905 | JMicron... | JMC250 PCI Express Gigabi... | 219   | jme        | 11F1CDC49A |
| 1969:2062 | 1043:8468 | Attansi... | AR8152 v2.0 Fast Ethernet    | 216   | atl1c      | 2117F02A4F |
| 1106:3106 | 1186:1405 | VIA Tec... | VT6105/VT6106S [Rhine-III]   | 196   | via_rhine  | C74DDA083F |
| 14e4:16b5 | 1025:0504 | Broadcom   | NetLink BCM57785 Gigabit ... | 196   | tg3        | 85BCF858C5 |
| 10de:0ab0 | 10de:cb79 | Nvidia     | MCP79 Ethernet               | 194   | forcedeth  | F982A2F6CC |
| 1969:1083 | 1043:1851 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 193   | atl1c      | 7DC7D11BE2 |
| 1969:1091 | 1458:e000 | Qualcom... | AR8161 Gigabit Ethernet      | 193   | alx        | E163EF1C6E |
| 8086:15bc | 1043:8672 | Intel      | Ethernet Connection (7) I... | 187   | e1000e     | 36EBF65D44 |
| 8086:155a | 17aa:2214 | Intel      | Ethernet Connection I218-LM  | 181   | e1000e     | 4C600416F9 |
| 10ec:8168 | 1025:8000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 168   | r8169      | 722016AF18 |
| 1969:1026 | 1043:8304 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 168   | atl1e      | 5101982911 |
| 8086:153b | 1458:e000 | Intel      | Ethernet Connection I217-V   | 168   | e1000e     | A2454FCD1F |
| 8086:15bc | 1458:e000 | Intel      | Ethernet Connection (7) I... | 166   | e1000e     | 197E319075 |
| 10ec:8168 | 17aa:5002 | Realtek... | RTL8111/8168/8411 PCI Exp... | 165   | r8169      | 2BA1AA7C62 |
| 14e4:1692 | 1025:036d | Broadcom   | NetLink BCM57780 Gigabit ... | 163   | tg3        | 2C401BFDB4 |
| 10ec:8168 | 1462:7817 | Realtek... | RTL8111/8168/8411 PCI Exp... | 157   | r8169      | 75E2E357A3 |
| 14e4:1686 | 14e4:1686 | Broadcom   | NetXtreme BCM57766 Gigabi... | 156   | tg3        | 066B825941 |
| 11ab:436a | 11ab:00ba | Marvell... | 88E8058 PCI-E Gigabit Eth... | 155   | sky2       | 00CC913F3D |
| 1969:1063 | 1043:1820 | Qualcom... | AR8131 Gigabit Ethernet      | 149   | atl1c      | FBC93A495C |
| 10ec:8136 | 1179:ff00 | Realtek... | RTL810xE PCI Express Fast... | 148   | r8169      | 8E44C9EDAF |
| 10ec:8168 | 1043:87c3 | Realtek... | RTL8111/8168/8411 PCI Exp... | 145   | r8169      | 379D2F0B1C |
| 10ec:8168 | 1462:7c02 | Realtek... | RTL8111/8168/8411 PCI Exp... | 145   | r8169      | 2229C9E9F6 |
| 14e4:1693 | 1025:011c | Broadcom   | NetLink BCM5787M Gigabit ... | 144   | tg3        | 6A05B72968 |
| 10ec:8168 | 1462:7c37 | Realtek... | RTL8111/8168/8411 PCI Exp... | 143   | r8169      | 0619809B36 |
| 8086:156f | 17aa:2233 | Intel      | Ethernet Connection I219-LM  | 143   | e1000e     | CAD013A6A5 |
| 8086:153a | 1028:05a4 | Intel      | Ethernet Connection I217-LM  | 142   | e1000e     | 0FC3ABDB1C |
| 10ec:8136 | 1043:8347 | Realtek... | RTL810xE PCI Express Fast... | 141   | r8169      | CB1A775980 |
| 1969:1090 | 17aa:3979 | Qualcom... | AR8162 Fast Ethernet         | 141   | alx        | 5872E567EC |
| 1969:2062 | 17aa:3979 | Qualcom... | AR8152 v2.0 Fast Ethernet    | 141   | atl1c      | FE1E9576C6 |
| 8086:15a2 | 17aa:2226 | Intel      | Ethernet Connection (3) I... | 141   | e1000e     | A5D677976F |
| 11ab:4320 | 1043:811a | Marvell... | 88E8001 Gigabit Ethernet ... | 138   | skge       | 926229BE87 |
| 10ec:8168 | 17aa:3812 | Realtek... | RTL8111/8168/8411 PCI Exp... | 134   | r8169      | 779BFC3B47 |
| 10ec:8168 | 1043:81aa | Realtek... | RTL8111/8168/8411 PCI Exp... | 133   | r8169      | 4B68AC1130 |
| 14e4:16b3 | 1025:0775 | Broadcom   | NetXtreme BCM57786 Gigabi... | 131   | tg3        | 98166600FA |
| 10ec:8168 | 1462:7721 | Realtek... | RTL8111/8168/8411 PCI Exp... | 127   | r8169      | 01C5E2E798 |
| 10ec:8136 | 17aa:3975 | Realtek... | RTL810xE PCI Express Fast... | 126   | r8169      | 21DB34139A |
| 14e4:1698 | 1025:0207 | Broadcom   | NetLink BCM5784M Gigabit ... | 125   | tg3        | F8CF9B2AA2 |
| 10ec:8168 | 17aa:38bb | Realtek... | RTL8111/8168/8411 PCI Exp... | 123   | r8169      | 19226582D9 |
| 8086:153b | 1043:859f | Intel      | Ethernet Connection I217-V   | 123   | e1000e     | B0F626D0E4 |
| 11ab:4381 | 104d:9071 | Marvell... | Yukon Optima 88E8059 [PCI... | 122   | sky2       | 03E0270FDD |
| 1969:2048 | 1043:8233 | Qualcom... | Attansic L2 Fast Ethernet    | 122   | atl2       | 5E2CE09E63 |
| 10ec:8136 | 1179:ff1e | Realtek... | RTL810xE PCI Express Fast... | 120   | r8169      | 40EBC49A02 |
| 1969:1026 | 1043:14f5 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 117   | atl1e      | 498362846A |
| 10ec:8136 | 1028:04b0 | Realtek... | RTL810xE PCI Express Fast... | 116   | r8169      | FF37A9C00D |
| 10ec:8136 | 10ec:8136 | Realtek... | RTL810xE PCI Express Fast... | 116   | r8169      | BEA9269412 |
| 10ec:8168 | 1025:1331 | Realtek... | RTL8111/8168/8411 PCI Exp... | 115   | r8169      | 38688703F4 |
| 8086:15be | 8086:2074 | Intel      | Ethernet Connection (6) I... | 115   | e1000e     | 7CA350189C |
| 10ec:8168 | 1b0a:20d9 | Realtek... | RTL8111/8168/8411 PCI Exp... | 112   | r8169      | 6AF51E631B |
| 1969:1026 | 1043:8226 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 112   | atl1e      | 102C78CA6B |
| 1969:10a1 | 1849:10a1 | Qualcom... | QCA8171 Gigabit Ethernet     | 111   | alx        | 615502E93E |
| 14e4:1684 | 14e4:1684 | Broadcom   | NetXtreme BCM5764M Gigabi... | 108   | tg3        | 85073CEA15 |
| 14e4:16b1 | 1849:96b1 | Broadcom   | NetLink BCM57781 Gigabit ... | 108   | tg3        | E7EBAD7358 |
| 1969:e091 | 1458:e000 | Qualcom... | Killer E220x Gigabit Ethe... | 108   | alx        | DF13F72A9A |
| 10ec:8168 | 1025:1193 | Realtek... | RTL8111/8168/8411 PCI Exp... | 107   | r8169      | E922639FF6 |
| 10ec:8168 | 1043:1277 | Realtek... | RTL8111/8168/8411 PCI Exp... | 107   | r8169      | A8FD68FCCC |
| 10ec:8168 | 17aa:5079 | Realtek... | RTL8111/8168/8411 PCI Exp... | 107   | r8169      | 0BC4073D23 |
| 1969:1062 | 1043:838a | Qualcom... | AR8132 Fast Ethernet         | 107   | atl1c      | E819E51835 |
| 10ec:8168 | 1043:205f | Realtek... | RTL8111/8168/8411 PCI Exp... | 106   | r8169      | EA9385EC68 |
| 10ec:8168 | 103c:8330 | Realtek... | RTL8111/8168/8411 PCI Exp... | 105   | r8169      | 5671BA2F85 |
| 10ec:8168 | 1025:0866 | Realtek... | RTL8111/8168/8411 PCI Exp... | 103   | r8169      | 58B4832D53 |
| 10ec:8168 | 1462:7b86 | Realtek... | RTL8111/8168/8411 PCI Exp... | 103   | r8169      | 6787B45989 |
| 14e4:1713 | 17aa:3a23 | Broadcom   | NetLink BCM5906M Fast Eth... | 103   | tg3        | 1BBEC614AA |
| 1969:1026 | 1043:831c | Qualcom... | AR8121/AR8113/AR8114 Giga... | 102   | atl1e      | 441067C1C2 |
| 8086:15a1 | 1849:15a1 | Intel      | Ethernet Connection (2) I... | 102   | e1000e     | 6FEB0AEC47 |
| 8086:15f3 | 1043:87d2 | Intel      | Ethernet Controller I225-V   | 101   | igc        | BBA08D40AD |
| 8086:155a | 103c:198f | Intel      | Ethernet Connection I218-LM  | 99    | e1000e     | 6573923D55 |
| 10ec:8168 | 17aa:388a | Realtek... | RTL8111/8168/8411 PCI Exp... | 98    | r8169      | 0540D35606 |
| 10ec:8168 | 1043:8367 | Realtek... | RTL8111/8168/8411 PCI Exp... | 97    | r8169      | 965BC51C8D |
| 10ec:8168 | 1462:7a38 | Realtek... | RTL8111/8168/8411 PCI Exp... | 97    | r8169      | 3056DB282E |
| 1186:4300 | 1186:4300 | D-Link ... | DGE-528T Gigabit Ethernet... | 97    | r8169      | 7A323363EF |
| 10ec:8136 | 1028:0810 | Realtek... | RTL810xE PCI Express Fast... | 96    | r8169      | 2FD333BC52 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2723 | 8086:0084 | Intel      | Wi-Fi 6 AX200                | 1761  | iwlwifi    | 20115EE05D |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 1045  | iwlwifi    | 6056EAC50C |
| 168c:002b | 1a3b:1089 | Qualcom... | AR9285 Wireless Network A... | 935   | ath9k      | 11F1CDC49A |
| 8086:0085 | 8086:1311 | Intel      | Centrino Advanced-N 6205 ... | 887   | iwlwifi    | AEF8C27B50 |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 870   | iwlwifi    | 3EA595A278 |
| 8086:a370 | 8086:0034 | Intel      | Cannon Lake PCH CNVi WiFi    | 809   | iwlwifi    | ECC7F6B940 |
| 168c:0042 | 11ad:08a6 | Qualcom... | QCA9377 802.11ac Wireless... | 807   | ath10k_pci | 80CF3DC8E7 |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 690   | rtl8821ce  | 035B3CDC60 |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 686   | iwlwifi    | BBA3BC97B7 |
| 8086:9df0 | 8086:0034 | Intel      | Cannon Point-LP CNVi [Wir... | 679   | iwlwifi    | DB75E4E24F |
| 8086:2526 | 8086:0014 | Intel      | Wireless-AC 9260             | 640   | iwlwifi    | B8D0E81636 |
| 168c:0042 | 17aa:0901 | Qualcom... | QCA9377 802.11ac Wireless... | 630   | ath10k_pci | 6670E1C145 |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 629   | iwlwifi    | 19226582D9 |
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 594   | iwlwifi    | C45342870C |
| 10ec:d723 | 103c:8319 | Realtek... | RTL8723DE Wireless Networ... | 554   | rtl8723de  | 5E75AF2BA4 |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 546   | iwlwifi    | 20F25688A9 |
| 168c:0042 | 1028:1810 | Qualcom... | QCA9377 802.11ac Wireless... | 534   | ath10k_pci | A638ECEE38 |
| 1814:3290 | 103c:18ec | Ralink     | RT3290 Wireless 802.11n 1... | 496   | rt2800pci  | BDAEE2E27B |
| 8086:02f0 | 8086:0074 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 399   | iwlwifi    | B7EC4606A3 |
| 168c:0036 | 1028:020c | Qualcom... | QCA9565 / AR9565 Wireless... | 397   | ath9k      | F226786C1B |
| 8086:2723 | 8086:0080 | Intel      | Wi-Fi 6 AX200                | 382   | iwlwifi    | 6B6205BC5D |
| 8086:088e | 8086:4060 | Intel      | Centrino Advanced-N 6235     | 381   | iwlwifi    | 24758ED5B3 |
| 168c:0036 | 1028:020e | Qualcom... | QCA9565 / AR9565 Wireless... | 374   | ath9k      | 8EFEEF8292 |
| 168c:0036 | 11ad:0642 | Qualcom... | QCA9565 / AR9565 Wireless... | 366   | ath9k      | 99175F6D0D |
| 8086:4237 | 8086:1211 | Intel      | PRO/Wireless 5100 AGN [Sh... | 356   | iwlwifi    | 65FBD3DEF4 |
| 10ec:b822 | 103c:831b | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 354   | rtwpci     | D3A001E377 |
| 8086:3165 | 8086:4410 | Intel      | Wireless 3165                | 352   | iwlwifi    | D7D4C28D2D |
| 168c:0032 | 1a3b:2c97 | Qualcom... | AR9485 Wireless Network A... | 348   | ath9k      | 1F075FEB49 |
| 8086:4222 | 8086:1001 | Intel      | PRO/Wireless 3945ABG [Gol... | 344   | iwl3945    | 6A05B72968 |
| 168c:003e | 1a56:1535 | Qualcom... | QCA6174 802.11ac Wireless... | 340   | ath10k_pci | 241E2FC9BD |
| 10ec:c821 | 17aa:c024 | Realtek... | RTL8821CE 802.11ac PCIe W... | 339   | rtl8821ce  | AB6647F9DA |
| 168c:0032 | 144d:4105 | Qualcom... | AR9485 Wireless Network A... | 333   | ath9k      | 228B340863 |
| 14e4:4365 | 17aa:0611 | Broadcom   | BCM43142 802.11b/g/n         | 325   | wl         | 2BA1AA7C62 |
| 8086:08b1 | 8086:4070 | Intel      | Wireless 7260                | 313   | iwlwifi    | 8F3CA163E7 |
| 8086:4232 | 8086:1201 | Intel      | WiFi Link 5100               | 313   | iwlwifi    | 2E325CDDC1 |
| 168c:002b | 17aa:30a1 | Qualcom... | AR9285 Wireless Network A... | 311   | ath9k      | CEAF1A4989 |
| 8086:4239 | 8086:1311 | Intel      | Centrino Advanced-N 6200     | 308   | iwlwifi    | 9635709179 |
| 168c:002b | 1a3b:2c37 | Qualcom... | AR9285 Wireless Network A... | 304   | ath9k      | 438D785F0E |
| 168c:0034 | 105b:e052 | Qualcom... | AR9462 Wireless Network A... | 303   | ath9k      | B732F94275 |
| 8086:24f3 | 8086:0010 | Intel      | Wireless 8260                | 302   | iwlwifi    | FC6D4C2E7D |
| 8086:0082 | 8086:1321 | Intel      | Centrino Advanced-N 6205 ... | 298   | iwlwifi    | D1D0976880 |
| 8086:24fd | 8086:0050 | Intel      | Wireless 8265 / 8275         | 292   | iwlwifi    | A92377CB2A |
| 8086:0887 | 8086:4062 | Intel      | Centrino Wireless-N 2230     | 286   | iwlwifi    | 848DEF4822 |
| 8086:4238 | 8086:1111 | Intel      | Centrino Ultimate-N 6300     | 271   | iwlwifi    | 5DC4A1E557 |
| 14e4:4727 | 103c:1483 | Broadcom   | BCM4313 802.11bgn Wireles... | 267   | wl         | 0245DA9040 |
| 168c:002e | 105b:e034 | Qualcom... | AR9287 Wireless Network A... | 266   | ath9k      | C172C655DE |
| 8086:08b1 | 8086:4470 | Intel      | Wireless 7260                | 266   | iwlwifi    | AC79B35DFD |
| 168c:003e | 11ad:0807 | Qualcom... | QCA6174 802.11ac Wireless... | 264   | ath10k_pci | 8D643F3501 |
| 168c:003e | 1028:0310 | Qualcom... | QCA6174 802.11ac Wireless... | 262   | ath10k_pci | 93BA5B0A6F |
| 8086:08b2 | 8086:c270 | Intel      | Wireless 7260                | 261   | iwlwifi    | F17B6F7270 |
| 8086:422b | 8086:1121 | Intel      | Centrino Ultimate-N 6300     | 261   | iwlwifi    | EE6C9C38B0 |
| 10ec:b723 | 17aa:b736 | Realtek... | RTL8723BE PCIe Wireless N... | 260   | rtl8723be  | B1B8196F26 |
| 14e4:4315 | 1028:000c | Broadco... | BCM4312 802.11b/g LP-PHY     | 257   | wl         | F0D0F92FD9 |
| 8086:24fd | 8086:0110 | Intel      | Wireless 8265 / 8275         | 256   | iwlwifi    | 423B514D2B |
| 8086:06f0 | 8086:0074 | Intel      | Comet Lake PCH CNVi WiFi     | 253   | iwlwifi    | 3A3BF28C3A |
| 8086:0082 | 8086:1301 | Intel      | Centrino Advanced-N 6205 ... | 252   | iwlwifi    | 0233ED2211 |
| 168c:0032 | 11ad:6617 | Qualcom... | AR9485 Wireless Network A... | 248   | ath9k      | 069EA1CB31 |
| 8086:4229 | 8086:1101 | Intel      | PRO/Wireless 4965 AG or A... | 244   | iwl4965    | 3B7266D323 |
| 10ec:b723 | 11ad:1723 | Realtek... | RTL8723BE PCIe Wireless N... | 233   | rtl8723be  | DCD714D5FA |
| 8086:0896 | 8086:5005 | Intel      | Centrino Wireless-N 130      | 232   | iwlwifi    | B41629F18A |
| 168c:0032 | 1028:0209 | Qualcom... | AR9485 Wireless Network A... | 230   | ath9k      | 2B158EA18F |
| 168c:0036 | 17aa:4026 | Qualcom... | QCA9565 / AR9565 Wireless... | 230   | ath9k      | EB9AAA55EA |
| 8086:3165 | 8086:8010 | Intel      | Wireless 3165                | 229   | iwlwifi    | 161E6B136E |
| 168c:0032 | 103c:1838 | Qualcom... | AR9485 Wireless Network A... | 223   | ath9k      | 6E2FC02F05 |
| 8086:24fd | 8086:9010 | Intel      | Wireless 8265 / 8275         | 219   | iwlwifi    | 38D5C55BD7 |
| 168c:002b | 105b:e035 | Qualcom... | AR9285 Wireless Network A... | 218   | ath9k      | DA7BA5D53F |
| 8086:0084 | 8086:1315 | Intel      | Centrino Wireless-N 1000 ... | 217   | iwlwifi    | DACA4B86FC |
| 168c:0032 | 1a3b:1186 | Qualcom... | AR9485 Wireless Network A... | 216   | ath9k      | 08930695BC |
| 8086:095a | 8086:5410 | Intel      | Wireless 7265                | 216   | iwlwifi    | 14584EE6C7 |
| 8086:24f3 | 8086:0050 | Intel      | Wireless 8260                | 216   | iwlwifi    | F972F7D9BA |
| 8086:24f3 | 8086:1010 | Intel      | Wireless 8260                | 212   | iwlwifi    | BB92AB2244 |
| 8086:095b | 8086:5210 | Intel      | Wireless 7265                | 211   | iwlwifi    | 6131E3C22A |
| 10ec:b723 | 103c:81c1 | Realtek... | RTL8723BE PCIe Wireless N... | 210   | rtl8723be  | 7D85368E1C |
| 14e4:4727 | 1028:0010 | Broadcom   | BCM4313 802.11bgn Wireles... | 210   | wl         | E58B9D7EA5 |
| 168c:001c | 1a3b:1026 | Qualcom... | AR242x / AR542x Wireless ... | 207   | ath5k      | 1A587EFF16 |
| 8086:34f0 | 8086:0074 | Intel      | Ice Lake-LP PCH CNVi WiFi    | 207   | iwlwifi    | 520E728AF7 |
| 10ec:c821 | 1a3b:3040 | Realtek... | RTL8821CE 802.11ac PCIe W... | 206   | rtl8821ce  | AF8045A7B3 |
| 10ec:8821 | 17aa:a814 | Realtek... | RTL8821AE 802.11ac PCIe W... | 204   | rtl8821ae  | 0540D35606 |
| 10ec:8179 | 103c:197d | Realtek... | RTL8188EE Wireless Networ... | 203   | rtl8188ee  | 8369C42CE2 |
| 10ec:b822 | 17aa:b023 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 201   | rtwpci     | 4DE4650899 |
| 168c:0034 | 11ad:6621 | Qualcom... | AR9462 Wireless Network A... | 200   | ath9k      | D0F0DA0187 |
| 14e4:4727 | 103c:145c | Broadcom   | BCM4313 802.11bgn Wireles... | 199   | wl         | E96260CFB9 |
| 8086:08b3 | 8086:0070 | Intel      | Wireless 3160                | 197   | iwlwifi    | 1E178FE783 |
| 168c:002e | 168c:30a4 | Qualcom... | AR9287 Wireless Network A... | 194   | ath9k      | D2FA60E459 |
| 8086:24f3 | 8086:0130 | Intel      | Wireless 8260                | 192   | iwlwifi    | CAD013A6A5 |
| 168c:0032 | 11ad:6627 | Qualcom... | AR9485 Wireless Network A... | 190   | ath9k      | 6C0B7D6353 |
| 168c:0032 | 168c:3118 | Qualcom... | AR9485 Wireless Network A... | 185   | ath9k      | 3D11EFA233 |
| 168c:002b | 103c:3040 | Qualcom... | AR9285 Wireless Network A... | 183   | ath9k      | 4D1F768F1A |
| 14e4:4365 | 103c:804a | Broadcom   | BCM43142 802.11b/g/n         | 181   | wl         | 7493540206 |
| 168c:0042 | 1a3b:2b31 | Qualcom... | QCA9377 802.11ac Wireless... | 180   | ath10k_pci | C323A8132A |
| 168c:0032 | 103c:1785 | Qualcom... | AR9485 Wireless Network A... | 179   | ath9k      | 0144616BB9 |
| 168c:002b | 105b:e017 | Qualcom... | AR9285 Wireless Network A... | 178   | ath9k      | EEB433BF77 |
| 8086:08b3 | 8086:8470 | Intel      | Wireless 3160                | 178   | iwlwifi    | 6A14872523 |
| 168c:001c | 1468:0428 | Qualcom... | AR242x / AR542x Wireless ... | 177   | ath5k      | 9357025BC9 |
| 8086:2723 | 1a56:1654 | Intel      | Wi-Fi 6 AX200                | 176   | iwlwifi    | 9CDE952049 |
| 10ec:b723 | 103c:2231 | Realtek... | RTL8723BE PCIe Wireless N... | 175   | rtl8723be  | C80A118E90 |
| 10ec:c822 | 103c:85f7 | Realtek... | RTL8822CE 802.11ac PCIe W... | 175   | rtw88_8... | F77E2EBB10 |
| 168c:003e | 1a56:143a | Qualcom... | QCA6174 802.11ac Wireless... | 174   | ath10k_pci | C2E884F793 |
| 8086:a0f0 | 8086:0074 | Intel      | Wi-Fi 6 AX201                | 174   | iwlwifi    | B6047B1557 |
| 8086:4222 | 103c:135c | Intel      | PRO/Wireless 3945ABG [Gol... | 172   | iwl3945    | B30D13BBBA |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1539 | 1043:85f0 | Intel      | I211 Gigabit Network Conn... | 766   | igb        | 97C17F738A |
| 8086:1539 | 1458:e000 | Intel      | I211 Gigabit Network Conn... | 532   | igb        | 24D2E85009 |
| 8086:1502 | 17aa:21f3 | Intel      | 82579LM Gigabit Network C... | 488   | e1000e     | C9503690D6 |
| 8086:1539 | 1849:1539 | Intel      | I211 Gigabit Network Conn... | 439   | igb        | 84FDA964C3 |
| 8086:1502 | 17aa:21ce | Intel      | 82579LM Gigabit Network C... | 412   | e1000e     | AEF8C27B50 |
| 8086:1503 | 1043:849c | Intel      | 82579V Gigabit Network Co... | 372   | e1000e     | BA117FEF7E |
| 10de:03ef | 1849:03ef | Nvidia     | MCP61 Ethernet               | 366   | forcedeth  | 0B81DF184D |
| 8086:10ea | 17aa:2153 | Intel      | 82577LM Gigabit Network C... | 258   | e1000e     | 5DC4A1E557 |
| 8086:1502 | 1028:052c | Intel      | 82579LM Gigabit Network C... | 205   | e1000e     | 4DAF9FDC0D |
| 8086:10f5 | 17aa:20ee | Intel      | 82567LM Gigabit Network C... | 200   | e1000e     | DB936567F0 |
| 8086:1502 | 1028:047e | Intel      | 82579LM Gigabit Network C... | 180   | e1000e     | 959E3DDE54 |
| 10de:03ef | 1458:e000 | Nvidia     | MCP61 Ethernet               | 179   | forcedeth  | FB1E012F68 |
| 8086:10de | 1028:0276 | Intel      | 82567LM-3 Gigabit Network... | 159   | e1000e     | 5824A76242 |
| 8086:10d3 | 8086:a01f | Intel      | 82574L Gigabit Network Co... | 141   | e1000e     | FB37055E96 |
| 10de:03ef | 1043:83a4 | Nvidia     | MCP61 Ethernet               | 138   | forcedeth  | 1C28AB7987 |
| 8086:1502 | 1028:0493 | Intel      | 82579LM Gigabit Network C... | 135   | e1000e     | 33617DD1A8 |
| 8086:10ea | 1028:040a | Intel      | 82577LM Gigabit Network C... | 130   | e1000e     | 576A6491F3 |
| 10ec:8125 | 1458:e000 | Realtek... | RTL8125 2.5GbE Controller    | 124   | r8169      | 6BC1B9DCC9 |
| 8086:1502 | 1028:0534 | Intel      | 82579LM Gigabit Network C... | 116   | e1000e     | 98420A7D92 |
| 10de:03ef | 1043:8234 | Nvidia     | MCP61 Ethernet               | 108   | forcedeth  | A5CA2582B6 |
| 8086:10f5 | 1028:0233 | Intel      | 82567LM Gigabit Network C... | 106   | e1000e     | 2A4C5F6EEC |
| 8086:1502 | 103c:161c | Intel      | 82579LM Gigabit Network C... | 100   | e1000e     | 701E56A49F |
| 8086:10bd | 1028:0211 | Intel      | 82566DM-2 Gigabit Network... | 94    | e1000e     | 962E0B75E4 |
| 8086:1502 | 103c:179b | Intel      | 82579LM Gigabit Network C... | 94    | e1000e     | 7D39BC1331 |
| 8086:1502 | 103c:3397 | Intel      | 82579LM Gigabit Network C... | 94    | e1000e     | 9C1343DD9B |
| 8086:1521 | 15d9:1521 | Intel      | I350 Gigabit Network Conn... | 85    | igb        | 331227D869 |
| 8086:1049 | 17aa:20b9 | Intel      | 82566MM Gigabit Network C... | 80    | e1000e     | E1B3B6E090 |
| 8086:10de | 1028:027f | Intel      | 82567LM-3 Gigabit Network... | 80    | e1000e     | 8F0C6ED152 |
| 8086:1502 | 103c:339a | Intel      | 82579LM Gigabit Network C... | 76    | e1000e     | BA7CCF28B7 |
| 8086:1539 | 8086:0000 | Intel      | I211 Gigabit Network Conn... | 76    | igb        | FE4761D2B2 |
| 8086:1502 | 103c:1495 | Intel      | 82579LM Gigabit Network C... | 67    | e1000e     | 660C4FF2ED |
| 8086:10bd | 103c:2818 | Intel      | 82566DM-2 Gigabit Network... | 64    | e1000e     | 92920FF59A |
| 8086:1502 | 103c:1497 | Intel      | 82579LM Gigabit Network C... | 64    | e1000e     | 7FA5AD3E42 |
| 10de:03ef | 1462:7309 | Nvidia     | MCP61 Ethernet               | 63    | forcedeth  | DC2D2CA478 |
| 8086:1502 | 1028:0535 | Intel      | 82579LM Gigabit Network C... | 60    | e1000e     | 2E9B8200A9 |
| 8086:1533 | 1043:8557 | Intel      | I210 Gigabit Network Conn... | 60    | igb        | 90E90490B7 |
| 8086:10de | 103c:3048 | Intel      | 82567LM-3 Gigabit Network... | 59    | e1000e     | 39204D22AE |
| 8086:10c0 | 1028:020d | Intel      | 82562V-2 10/100 Network C... | 58    | e1000e     | 8A955D2C5A |
| 8086:10ea | 103c:172a | Intel      | 82577LM Gigabit Network C... | 56    | e1000e     | 9635709179 |
| 8086:1533 | 15d9:1533 | Intel      | I210 Gigabit Network Conn... | 56    | igb        | CF083F4B62 |
| 8086:10d3 | 1043:8369 | Intel      | 82574L Gigabit Network Co... | 54    | e1000e     | 910CE6A9D9 |
| 8086:10c4 | 103c:30d8 | Intel      | 82562GT 10/100 Network Co... | 53    | e1000e     | E6E060CA51 |
| 8086:1533 | ffff:0000 | Intel      | I210 Gigabit Network Conn... | 52    | igb        | 592FA60C7D |
| 14e4:170c | 1025:0090 | Broadcom   | BCM4401-B0 100Base-TX        | 51    | b44        | 4A0EE2EAA5 |
| 8086:1502 | 1028:0494 | Intel      | 82579LM Gigabit Network C... | 51    | e1000e     | E58B9D7EA5 |
| 8086:1503 | 1458:e000 | Intel      | 82579V Gigabit Network Co... | 51    | e1000e     | 31B25815EC |
| 10de:0057 | 1043:812a | Nvidia     | CK804 Ethernet Controller    | 50    | forcedeth  | FF54330A37 |
| 8086:1503 | 1025:8000 | Intel      | 82579V Gigabit Network Co... | 50    | e1000e     | 1CBEE8A7EF |
| 10ec:8125 | 1043:87d7 | Realtek... | RTL8125 2.5GbE Controller    | 49    | r8169      | 20115EE05D |
| 8086:1502 | 10cf:161b | Intel      | 82579LM Gigabit Network C... | 49    | e1000e     | B2D4A08D24 |
| 8086:104a | 103c:2800 | Intel      | 82566DM Gigabit Network C... | 47    | e1000e     | 2D99B2D79D |
| 8086:10ea | 103c:7008 | Intel      | 82577LM Gigabit Network C... | 46    | e1000e     | 383932E73B |
| 8086:294c | 8086:0001 | Intel      | 82566DC-2 Gigabit Network... | 46    | e1000e     | AF996AA861 |
| 10de:0373 | 1043:8239 | Nvidia     | MCP55 Ethernet               | 45    | forcedeth  | 476250F98C |
| 8086:10eb | 103c:1471 | Intel      | 82577LC Gigabit Network C... | 45    | e1000e     | 523C397AB6 |
| 8086:1502 | 10f7:8338 | Intel      | 82579LM Gigabit Network C... | 45    | e1000e     | 621E3366FD |
| 8086:10ea | 1028:040b | Intel      | 82577LM Gigabit Network C... | 42    | e1000e     | 6902EB0F50 |
| 8086:1502 | 103c:162b | Intel      | 82579LM Gigabit Network C... | 42    | e1000e     | E96260CFB9 |
| 8086:10bd | 103c:281e | Intel      | 82566DM-2 Gigabit Network... | 41    | e1000e     | D3603FD2D2 |
| 8086:10df | 1734:114d | Intel      | 82567LF-3 Gigabit Network... | 41    | e1000e     | A9B9EB3480 |
| 8086:10f0 | 8086:0036 | Intel      | 82578DC Gigabit Network C... | 41    | e1000e     | 15FF525EFC |
| 8086:10f5 | 1028:024f | Intel      | 82567LM Gigabit Network C... | 41    | e1000e     | 3BDEE6855C |
| 8086:10d3 | 15d9:10d3 | Intel      | 82574L Gigabit Network Co... | 40    | e1000e     | CF37C43C55 |
| 14e4:170c | 1028:01f5 | Broadcom   | BCM4401-B0 100Base-TX        | 39    | b44        | 32C3521A2E |
| 8086:1502 | 1028:0492 | Intel      | 82579LM Gigabit Network C... | 39    | e1000e     | B9503F222C |
| 8086:150c | 1043:8457 | Intel      | 82583V Gigabit Network Co... | 39    | e1000e     | 88DF6AA3A5 |
| 8086:157b | 8086:0000 | Intel      | I210 Gigabit Network Conn... | 39    | igb        | D186AF4EE3 |
| 10ec:8125 | 1849:8125 | Realtek... | RTL8125 2.5GbE Controller    | 38    | r8169      | 52789C01CA |
| 1106:3065 | 1043:80ed | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 38    | via_rhine  | 10DB975AB9 |
| 8086:1502 | 103c:1618 | Intel      | 82579LM Gigabit Network C... | 38    | e1000e     | EA1BD5E314 |
| 8086:1502 | 17aa:3070 | Intel      | 82579LM Gigabit Network C... | 38    | e1000e     | 6983745C31 |
| 8086:1503 | 10cf:161c | Intel      | 82579V Gigabit Network Co... | 38    | e1000e     | 57D55A953C |
| 10de:03ef | 103c:2a6c | Nvidia     | MCP61 Ethernet               | 37    | forcedeth  | 78A4331611 |
| 10ec:8168 | 17aa:505b | Realtek... | RTL8111/8168/8411 PCI Exp... | 37    | r8169      | CC35722C1F |
| 14e4:170c | 1028:01af | Broadcom   | BCM4401-B0 100Base-TX        | 37    | b44        | 3EB7729825 |
| 8086:10c0 | 1028:0238 | Intel      | 82562V-2 10/100 Network C... | 37    | e1000e     | 46A56037D1 |
| 8086:10de | 17aa:3048 | Intel      | 82567LM-3 Gigabit Network... | 37    | e1000e     | 7E76E404EC |
| 8086:10ea | 103c:1521 | Intel      | 82577LM Gigabit Network C... | 36    | e1000e     | FFC46C9472 |
| 8086:1502 | 103c:1589 | Intel      | 82579LM Gigabit Network C... | 36    | e1000e     | A4B0EBBEE2 |
| 8086:1502 | 103c:18df | Intel      | 82579LM Gigabit Network C... | 36    | e1000e     | 3E6A2F7B59 |
| 8086:1539 | 1462:7b85 | Intel      | I211 Gigabit Network Conn... | 36    | igb        | B8D0E81636 |
| 1106:3065 | 1849:3065 | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 35    | via_rhine  | 6410827A2F |
| 14e4:170c | 103c:30a2 | Broadcom   | BCM4401-B0 100Base-TX        | 35    | b44        | 204F122174 |
| 8086:10de | 103c:3646 | Intel      | 82567LM-3 Gigabit Network... | 35    | e1000e     | 833B887480 |
| 8086:1502 | 17aa:3083 | Intel      | 82579LM Gigabit Network C... | 35    | e1000e     | C0B8E99E35 |
| 10ec:8125 | 1462:7c91 | Realtek... | RTL8125 2.5GbE Controller    | 34    | r8169      | C4A7A4682B |
| 8086:10f6 | 8086:0000 | Intel      | 82574L Gigabit Network Co... | 34    | e1000e     | DE14F99534 |
| 8086:1502 | 103c:1494 | Intel      | 82579LM Gigabit Network C... | 34    | e1000e     | 646E6E27E3 |
| 8086:1503 | 103c:17ab | Intel      | 82579V Gigabit Network Co... | 34    | e1000e     | 2B341B7BF9 |
| 8086:1539 | 1462:7a32 | Intel      | I211 Gigabit Network Conn... | 34    | igb        | D3237E56E1 |
| 10de:0057 | 1043:8141 | Nvidia     | CK804 Ethernet Controller    | 33    | forcedeth  | 00B830F623 |
| 10de:03ef | 1565:2505 | Nvidia     | MCP61 Ethernet               | 33    | forcedeth  | FF6423FB29 |
| 10ec:8136 | 103c:3567 | Realtek... | RTL810xE PCI Express Fast... | 33    | r8169      | C774724C5F |
| 8086:10de | 103c:3034 | Intel      | 82567LM-3 Gigabit Network... | 33    | e1000e     | D69CD77C4D |
| 8086:10ea | 10cf:1574 | Intel      | 82577LM Gigabit Network C... | 33    | e1000e     | F220F9AC45 |
| 8086:10f0 | 1025:8000 | Intel      | 82578DC Gigabit Network C... | 33    | e1000e     | 78FC18FCF4 |
| 8086:10f5 | 103c:30db | Intel      | 82567LM Gigabit Network C... | 33    | e1000e     | A4CEF366BC |
| 8086:1502 | 1028:04a3 | Intel      | 82579LM Gigabit Network C... | 33    | e1000e     | EE6C9C38B0 |
| 8086:1502 | 1028:0532 | Intel      | 82579LM Gigabit Network C... | 33    | e1000e     | 04D10F10D8 |
| 8086:1503 | 8086:2017 | Intel      | 82579V Gigabit Network Co... | 33    | e1000e     | 5B590117DD |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:145a | 1022:145a | AMD        | Zeppelin/Raven/Raven2 PCI... | 1657  |            | D88D9DB618 |
| 1022:1455 | 1022:1455 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1630  |            | D88D9DB618 |
| 1022:1485 | 1022:1485 | AMD        | Starship/Matisse Reserved... | 1230  |            | 0619809B36 |
| 1022:148a | 1022:148a | AMD        | Starship/Matisse PCIe Dum... | 1177  |            | 0619809B36 |
| 1022:1485 | 1043:87c0 | AMD        | Starship/Matisse Reserved... | 574   |            | 97C17F738A |
| 1022:148a | 1043:87c0 | AMD        | Starship/Matisse PCIe Dum... | 574   |            | 97C17F738A |
| 1022:1455 | 1043:8747 | AMD        | Zeppelin/Renoir PCIe Dumm... | 523   |            | 115EC5ECA4 |
| 1022:145a | 1043:8747 | AMD        | Zeppelin/Raven/Raven2 PCI... | 523   |            | 115EC5ECA4 |
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
| 8086:9d26 |           | Intel      | Skylake-U/Y Northpeak        | 26    | intel_t... | 03065735FF |
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
| 1022:1485 | 1558:50f0 | AMD        | Starship/Matisse Reserved... | 12    |            | B34A66FE8D |
| 1022:148a | 1558:50f0 | AMD        | Starship/Matisse PCIe Dum... | 12    |            | B34A66FE8D |
| 1022:1485 | 1043:87e2 | AMD        | Starship/Matisse Reserved... | 10    |            | 76267FCBDA |
| 1022:1485 | 1462:7a40 | AMD        | Starship/Matisse Reserved... | 10    |            | B2B10D4380 |
| 1022:148a | 1043:87e2 | AMD        | Starship/Matisse PCIe Dum... | 10    |            | 76267FCBDA |
| 1022:148a | 1462:7a40 | AMD        | Starship/Matisse PCIe Dum... | 10    |            | B2B10D4380 |
| 8086:5a8e | 8086:7270 | Intel      | Non-Essential Instrumenta... | 9     | intel_t... | 7B973470B7 |
| 1022:1455 | 1462:7a40 | AMD        | Zeppelin/Renoir PCIe Dumm... | 7     |            | BD8CB19ABD |
| 1022:145a | 1462:7a40 | AMD        | Zeppelin/Raven/Raven2 PCI... | 7     |            | BD8CB19ABD |
| 1022:145a | 1462:7b87 | AMD        | Zeppelin/Raven/Raven2 PCI... | 6     |            | 9B8F51B1D4 |
| 1022:1455 | 1025:1246 | AMD        | Zeppelin/Renoir PCIe Dumm... | 5     |            | 03FACC3040 |
| 1022:1455 | 1462:7b87 | AMD        | Zeppelin/Renoir PCIe Dumm... | 5     |            | 9B8F51B1D4 |
| 1022:145a | 1025:1246 | AMD        | Zeppelin/Raven/Raven2 PCI... | 5     |            | 03FACC3040 |
| 1022:145a | 1462:7b79 | AMD        | Zeppelin/Raven/Raven2 PCI... | 5     |            | 2119A5CDC5 |
| 1022:1485 | 1043:876b | AMD        | Starship/Matisse Reserved... | 5     |            | E1B742D511 |
| 1022:1485 | 1462:7c36 | AMD        | Starship/Matisse Reserved... | 5     |            | 26B69278F1 |
| 1022:148a | 1462:7c36 | AMD        | Starship/Matisse PCIe Dum... | 5     |            | 26B69278F1 |
| 8086:a126 |           | Intel      | 100 Series/C230 Series Ch... | 5     | intel_t... | E5B46A78DE |
| 1022:1485 | 1028:098e | AMD        | Starship/Matisse Reserved... | 4     |            | E1BC8D1CDD |
| 1022:1485 | 1462:7c34 | AMD        | Starship/Matisse Reserved... | 4     |            | 3D2E576C95 |
| 1022:148a | 1028:098e | AMD        | Starship/Matisse PCIe Dum... | 4     |            | E1BC8D1CDD |
| 1022:148a | 1462:7c34 | AMD        | Starship/Matisse PCIe Dum... | 4     |            | 3D2E576C95 |
| 8086:318e |           | Intel      | Celeron/Pentium Silver Pr... | 4     | intel_t... | 7BDEC3EB56 |
| 1022:1455 | 1462:7b90 | AMD        | Zeppelin/Renoir PCIe Dumm... | 3     |            | ABD9798AA8 |
| 1022:145a | 103c:879c | AMD        | Zeppelin/Raven/Raven2 PCI... | 3     |            | 7D1F6E5B43 |
| 1022:145a | 1462:7a33 | AMD        | Zeppelin/Raven/Raven2 PCI... | 3     |            | 26F4437015 |
| 1022:145a | 1462:7b84 | AMD        | Zeppelin/Raven/Raven2 PCI... | 3     |            | 9644A0A56C |
| 1022:145a | 1462:7b90 | AMD        | Zeppelin/Raven/Raven2 PCI... | 3     |            | ABD9798AA8 |
| 1022:145a | 1462:7c52 | AMD        | Zeppelin/Raven/Raven2 PCI... | 3     |            | 0901294419 |
| 1022:1485 | 1458:1000 | AMD        | Starship/Matisse Reserved... | 3     |            | D140FF934B |
| 1022:1485 | 17aa:1046 | AMD        | Starship/Matisse Reserved... | 3     |            | 2C58A29C2A |
| 1022:148a | 1458:1000 | AMD        | Starship/Matisse PCIe Dum... | 3     |            | D140FF934B |
| 1022:148a | 17aa:1046 | AMD        | Starship/Matisse PCIe Dum... | 3     |            | 2C58A29C2A |
| 1022:1455 | 103c:8399 | AMD        | Zeppelin/Renoir PCIe Dumm... | 2     |            | 733813E901 |
| 1022:1455 | 1458:1000 | AMD        | Zeppelin/Renoir PCIe Dumm... | 2     |            | 6D486A7EE9 |
| 1022:145a | 1002:1636 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | CBB2AC50E7 |
| 1022:145a | 103c:8399 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 733813E901 |
| 1022:145a | 1458:1000 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 6D486A7EE9 |
| 1022:145a | 1462:7c51 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 0EDF382CEE |
| 1022:145a | 1565:170b | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 3DEE7E8842 |
| 1022:145a | 17aa:3803 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | C9E7AE41BA |
| 1022:145a | 1d05:1111 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | E9A891227F |
| 1022:1485 | 1462:7c96 | AMD        | Starship/Matisse Reserved... | 2     |            | 1DC1C27798 |
| 1022:1485 | 1849:1485 | AMD        | Starship/Matisse Reserved... | 2     |            | EBCC16470F |
| 1022:148a | 1043:8747 | AMD        | Starship/Matisse PCIe Dum... | 2     |            | 249D6291CB |
| 1022:148a | 1462:7c96 | AMD        | Starship/Matisse PCIe Dum... | 2     |            | 1DC1C27798 |
| 1022:1455 | 1019:9ce5 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 06776696F3 |
| 1022:1455 | 1019:9d10 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 277BBC0E9E |
| 1022:1455 | 1019:a412 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | C47BA626E7 |
| 1022:1455 | 1019:a4cd | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 8106DDD47F |
| 1022:1455 | 1028:07f9 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 8F7FF50C55 |
| 1022:1455 | 17aa:36e1 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 31F5158C61 |
| 1022:1455 | 1849:1455 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 4C4AD9EBE5 |
| 1022:145a | 1019:9ce5 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 06776696F3 |
| 1022:145a | 1019:9d10 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 277BBC0E9E |
| 1022:145a | 1019:a412 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | C47BA626E7 |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15e6 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Non-S... | 211   | i2c_amd... | AF8045A7B3 |
| 8086:9d24 |           | Intel      | Skylake-U/Y SPI Controller   | 51    |            | 1AB69568A5 |
| 106b:1801 | 106b:1801 | Apple      | T2 Bridge Controller         | 46    | apple_bce  | 2BDDF8B98A |
| 106b:1802 | 106b:1802 | Apple      | T2 Secure Enclave Processor  | 46    |            | 2BDDF8B98A |
| 8086:9d35 | 17aa:2238 | Intel      | Sunrise Point-LP Integrat... | 46    | intel_i... | CAD013A6A5 |
| 8086:9d35 | 8086:9d35 | Intel      | Sunrise Point-LP Integrat... | 45    | intel_i... | B0C32B29BB |
| 8086:9d35 | 8086:7270 | Intel      | Sunrise Point-LP Integrat... | 41    | intel_i... | 7A294509DE |
| 1022:15e6 | 103c:85ea | AMD        | Raven/Raven2/Renoir Non-S... | 33    | i2c_amd... | D03BDBF1DA |
| 8086:22d8 | 103c:813e | Intel      | Integrated Sensor Solution   | 28    | intel_i... | 71120B9356 |
| 8086:9d35 | 1028:0740 | Intel      | Sunrise Point-LP Integrat... | 26    | intel_i... | E36E444BAC |
| 8086:9d35 | 103c:83b9 | Intel      | Sunrise Point-LP Integrat... | 24    | intel_i... | 2C533BE257 |
| 1022:15e4 | 103c:85dd | AMD        | Raven/Raven2/Renoir Senso... | 22    | amd_sfh    | A93B2565DF |
| 8086:22d8 | 1043:13a0 | Intel      | Integrated Sensor Solution   | 20    | intel_i... | 83AE87648C |
| 8086:9d35 | 17aa:380d | Intel      | Sunrise Point-LP Integrat... | 19    | intel_i... | 1A0B1FFDBD |
| 1022:15e6 | 1025:1456 | AMD        | Raven/Raven2/Renoir Non-S... | 18    | i2c_amd... | 80CF3DC8E7 |
| 1022:15e4 | 103c:85de | AMD        | Raven/Raven2/Renoir Senso... | 17    | amd_sfh    | 9E86C8EDE5 |
| 8086:22d8 | 103c:827c | Intel      | Integrated Sensor Solution   | 17    | intel_i... | E5A8BA60CF |
| 8086:22d8 | 1043:1400 | Intel      | Integrated Sensor Solution   | 17    | intel_i... | 0542145A63 |
| 1022:15e4 | 103c:8496 | AMD        | Raven/Raven2/Renoir Senso... | 14    | amd_sfh    | 8A63E2E055 |
| 8086:9d35 | 103c:830f | Intel      | Sunrise Point-LP Integrat... | 14    | intel_i... | B6BC75336E |
| 1022:15e4 | 103c:8497 | AMD        | Raven/Raven2/Renoir Senso... | 13    | pcie_mp... | 2910A4173E |
| 8086:9d35 | 103c:827d | Intel      | Sunrise Point-LP Integrat... | 13    | intel_i... | 51178C1953 |
| 8086:9d35 | 103c:8486 | Intel      | Sunrise Point-LP Integrat... | 13    | intel_i... | B149A04EE8 |
| 8086:9d35 | 17aa:2259 | Intel      | Sunrise Point-LP Integrat... | 13    | intel_i... | C96223F666 |
| 8086:a135 | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 13    | intel_i... | C28F77B8F1 |
| 8086:a135 | 103c:83bb | Intel      | 100 Series/C230 Series Ch... | 13    | intel_i... | BA09E3B76F |
| 8086:9d35 | 103c:827e | Intel      | Sunrise Point-LP Integrat... | 12    | intel_i... | B3CFF29C2E |
| 8086:9d35 | 103c:83b2 | Intel      | Sunrise Point-LP Integrat... | 12    | intel_i... | 1EEA89F8BB |
| 8086:22d8 | 1043:1bdd | Intel      | Integrated Sensor Solution   | 11    | intel_i... | 866C75D8E6 |
| 8086:9d35 | 1028:077a | Intel      | Sunrise Point-LP Integrat... | 11    | intel_i... | C0A9C9443B |
| 8086:9d35 | 1028:0804 | Intel      | Sunrise Point-LP Integrat... | 11    | intel_i... | C15C1DA104 |
| 8086:9d35 | 17aa:224e | Intel      | Sunrise Point-LP Integrat... | 11    | intel_i... | B866426527 |
| 8086:9d35 | 103c:8488 | Intel      | Sunrise Point-LP Integrat... | 10    | intel_i... | 7B7C2317D8 |
| 8086:9d35 | 1043:1ab0 | Intel      | Sunrise Point-LP Integrat... | 10    | intel_i... | CE8E9AF30D |
| 8086:22d8 | 8086:7270 | Intel      | Integrated Sensor Solution   | 9     | intel_i... | 42B9111B9B |
| 8086:9d35 | 103c:81a1 | Intel      | Sunrise Point-LP Integrat... | 9     | intel_i... | B37CBA5DF4 |
| 8086:9d35 | 152d:1182 | Intel      | Sunrise Point-LP Integrat... | 9     | intel_i... | 3EB69E8095 |
| 8086:9d35 | 1028:073b | Intel      | Sunrise Point-LP Integrat... | 8     | intel_i... | E14ACDFFAD |
| 8086:9d35 | 1028:07a4 | Intel      | Sunrise Point-LP Integrat... | 8     | intel_i... | C5396B5734 |
| 8086:9d35 | 103c:80fc | Intel      | Sunrise Point-LP Integrat... | 8     | intel_i... | 09240A2A3F |
| 8086:9d35 | 103c:8438 | Intel      | Sunrise Point-LP Integrat... | 8     | intel_i... | 633CDE303A |
| 8086:9d35 | 17aa:2237 | Intel      | Sunrise Point-LP Integrat... | 8     | intel_i... | 2A0ECA4670 |
| 8086:9d35 | 1028:0742 | Intel      | Sunrise Point-LP Integrat... | 7     | intel_i... | 2FC3CACC51 |
| 8086:9d35 | 103c:82ca | Intel      | Sunrise Point-LP Integrat... | 7     | intel_i... | D6AB5352B8 |
| 8086:9d35 | 103c:8470 | Intel      | Sunrise Point-LP Integrat... | 7     | intel_i... | EF7445EB15 |
| 8086:9d35 | 17aa:506c | Intel      | Sunrise Point-LP Integrat... | 7     | intel_i... | 6C4ABD0606 |
| 8086:9d35 | 17aa:506d | Intel      | Sunrise Point-LP Integrat... | 7     | intel_i... | 847655CB40 |
| 8086:9d35 | 1028:081d | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | 1ABEA9314A |
| 8086:9d35 | 103c:8484 | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | D46010346C |
| 8086:9d35 | 1043:1c90 | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | AED32F7A4D |
| 8086:9d35 | 17aa:504c | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | 4983586FE5 |
| 1022:15e4 | 1028:090c | AMD        | Raven/Raven2/Renoir Senso... | 5     |            | B64ACF39C9 |
| 8086:22d8 | 103c:82f4 | Intel      | Integrated Sensor Solution   | 5     | intel_i... | 1C188B150F |
| 8086:9d35 | 1028:07eb | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | E4FFC93C6A |
| 8086:9d35 | 103c:81a9 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 0BB3F77C75 |
| 8086:9d35 | 103c:81ad | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | CE728E8715 |
| 8086:9d35 | 103c:827f | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | BD5BDFD31F |
| 8086:9d35 | 103c:828b | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 3196DC7C2A |
| 8086:9d35 | 103c:8313 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | DCD840E8A2 |
| 8086:9d35 | 103c:8483 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | C41A1DE997 |
| 8086:9d35 | 103c:8487 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | CA8936A74C |
| 8086:9d35 | 17aa:3812 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | AAEF1C5AE7 |
| 8086:a2a4 |           | Intel      | 200 Series/Z370 Chipset F... | 5     |            | 672448ACFD |
| 8086:22d8 | 1043:1c60 | Intel      | Integrated Sensor Solution   | 4     | intel_i... | A8198C3153 |
| 8086:9d35 | 1028:06d6 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | A8551FD24E |
| 8086:9d35 | 1028:06e6 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 36CE9AD0C9 |
| 8086:9d35 | 1028:0741 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | A87267AB19 |
| 8086:9d35 | 1028:0743 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 7EC4FFF3D3 |
| 8086:9d35 | 1028:07aa | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 5492FDD780 |
| 8086:9d35 | 1028:0808 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 83C30B9084 |
| 8086:9d35 | 103c:81a7 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | BC77E670A5 |
| 8086:9d35 | 103c:82c1 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | CF06BA276E |
| 8086:9d35 | 103c:83c4 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 3F62C672FB |
| 8086:9d35 | 103c:84d8 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 03FE12C3CC |
| 8086:9d35 | 1179:0001 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 430A666F91 |
| 8086:9d35 | 152d:1237 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 2618117BB7 |
| 8086:9d35 | 17aa:2241 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 1C271464F4 |
| 8086:9d35 | 17aa:2244 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 234767F4BA |
| 8086:9d35 | 17aa:3807 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | F78D607B1F |
| 8086:9d35 | 17aa:5061 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 9FCFE8BF6A |
| 104c:9065 |           | Texas I... | TMS320DM642                  | 3     |            | 1AA3233F77 |
| 12ab:0380 | 1cfa:0003 | YUAN Hi... | Game Capture 4K60 Pro        | 3     |            | B4B00787C2 |
| 1b4b:9235 |           | Marvell... | 88SE9235 PCIe 2.0 x2 4-po... | 3     |            | 7F5766D5DA |
| 8086:22d8 | 103c:8042 | Intel      | Integrated Sensor Solution   | 3     | intel_i... | 45359B58FC |
| 8086:9d35 | 1025:111e | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 1A171E7553 |
| 8086:9d35 | 1028:0744 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 2CF1F86B67 |
| 8086:9d35 | 1028:07a5 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 0325FE3F75 |
| 8086:9d35 | 1028:07ba | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 271C309BFA |
| 8086:9d35 | 1028:0823 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 1BB17DC648 |
| 8086:9d35 | 1028:0878 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 91F3D918A0 |
| 8086:9d35 | 103c:82b7 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 3B8F11D2DB |
| 8086:9d35 | 103c:8310 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | D7D0DE8CF4 |
| 8086:9d35 | 103c:83ba | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | FB88A217E9 |
| 8086:9d35 | 1043:1c40 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | BD57C16BE8 |
| 8086:9d35 | 144d:c162 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 5DA835E33E |
| 8086:9d35 | 17aa:380c | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 32B0895AB5 |
| 8086:a135 | 15d9:089a | Intel      | 100 Series/C230 Series Ch... | 3     | intel_i... | 6B930AF6EC |
| 8086:a135 | 8086:a135 | Intel      | 100 Series/C230 Series Ch... | 3     | intel_i... | CCDADF3870 |
| 1022:15e4 | 1025:1506 | AMD        | Raven/Raven2/Renoir Senso... | 2     | amd_sfh    | D000862005 |
| 1022:15e6 | 103c:87ce | AMD        | Raven/Raven2/Renoir Non-S... | 2     | i2c_amd... | 527EBE7BDE |

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
| 8086:2f30 | 8086:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 324   | hswep_u... | F90168C69D |
| 8086:2f34 | 8086:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 324   | hswep_u... | F90168C69D |
| 8086:2f7d | 8086:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 324   |            | F90168C69D |
| 8086:2f36 | 8086:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 293   | hswep_u... | F90168C69D |
| 8086:2f37 | 8086:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 293   | hswep_u... | F90168C69D |
| 8086:204c | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 176   | skx_uncore | 2D1D9030E8 |
| 8086:204d | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 176   | skx_uncore | 2D1D9030E8 |
| 8086:2015 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 175   |            | 2D1D9030E8 |
| 8086:3c44 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to Q... | 132   | snbep_u... | C6DCB137FB |
| 8086:3ce6 | 8086:0000 | Intel      | Xeon E5/Core i7 QuickPath... | 132   |            | C6DCB137FB |
| 8086:3c43 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to P... | 126   | snbep_u... | C6DCB137FB |
| 8086:0e36 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 112   | ivbep_u... | 150AFCB2D1 |
| 8086:6f30 | 8086:6f30 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 94    | bdx_uncore | 4860ACD042 |
| 8086:6f34 | 8086:6f34 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 94    | bdx_uncore | 4860ACD042 |
| 8086:6f7d | 8086:6f7d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 94    |            | 4860ACD042 |
| 8086:0e34 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 91    | ivbep_u... | 150AFCB2D1 |
| 8086:2058 | 8086:0000 | Intel      | Sky Lake-E KTI 0             | 88    | skx_uncore | 2D1D9030E8 |
| 8086:6f36 | 8086:6f36 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 84    | bdx_uncore | 4860ACD042 |
| 8086:6f37 | 8086:6f37 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 84    | bdx_uncore | 4860ACD042 |
| 8086:3c43 | 1043:84ef | Intel      | Xeon E5/Core i7 Ring to P... | 78    | snbep_u... | 610B68BB7B |
| 8086:3c44 | 1043:84ef | Intel      | Xeon E5/Core i7 Ring to Q... | 78    | snbep_u... | 610B68BB7B |
| 8086:3c46 | 1043:84ef | Intel      | Xeon E5/Core i7 Processor... | 78    | snbep_u... | 610B68BB7B |
| 8086:3ce6 | 1043:84ef | Intel      | Xeon E5/Core i7 QuickPath... | 78    |            | 610B68BB7B |
| 8086:2f38 | 8086:2f38 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 77    | hswep_u... | F90168C69D |
| 8086:27a3 |           | Intel      | 945GM/GU Chipset Hardware... | 75    |            | C480910C6C |
| 8086:3c46 |           | Intel      | Xeon E5/Core i7 Processor... | 66    | snbep_u... | A4B0EBBEE2 |
| 8086:3c46 | 8086:0000 | Intel      | Xeon E5/Core i7 Processor... | 63    | snbep_u... | C6DCB137FB |
| 8086:2f32 | 8086:2f32 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 54    | hswep_u... | F90168C69D |
| 8086:2088 | 8086:0000 | Intel      | Sky Lake-E DDRIO Registers   | 53    | skx_uncore | 52789C01CA |
| 8086:2f33 | 8086:2f33 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 51    | hswep_u... | F90168C69D |
| 8086:0e30 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 49    | ivbep_u... | 150AFCB2D1 |
| 8086:0e30 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 46    | ivbep_u... | F0DC31F93D |
| 8086:0e34 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 46    | ivbep_u... | F0DC31F93D |
| 8086:0e36 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 46    | ivbep_u... | F0DC31F93D |
| 8086:0e30 |           | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 42    | ivbep_u... | 730C09F9E6 |
| 8086:3424 |           | Intel      | 7500/5520/5500/X58 Perfor... | 36    |            | DE14F99534 |
| 8086:2f30 | 1849:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 27    | hswep_u... | 6FEB0AEC47 |
| 8086:2f34 | 1849:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 27    | hswep_u... | 6FEB0AEC47 |
| 8086:2f36 | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 27    | hswep_u... | 09B0FBCF47 |
| 8086:2f36 | 1849:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 27    | hswep_u... | 6FEB0AEC47 |
| 8086:2f37 | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 27    | hswep_u... | 09B0FBCF47 |
| 8086:2f37 | 1849:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 27    | hswep_u... | 6FEB0AEC47 |
| 8086:2f7d | 1849:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 27    |            | 6FEB0AEC47 |
| 8086:3c43 | 103c:18a8 | Intel      | Xeon E5/Core i7 Ring to P... | 24    | snbep_u... | 799CC190DB |
| 8086:3c44 | 103c:18a8 | Intel      | Xeon E5/Core i7 Ring to Q... | 24    | snbep_u... | 799CC190DB |
| 8086:3c46 | 103c:18a8 | Intel      | Xeon E5/Core i7 Processor... | 24    | snbep_u... | 799CC190DB |
| 8086:3ce6 | 103c:18a8 | Intel      | Xeon E5/Core i7 QuickPath... | 24    |            | 799CC190DB |
| 8086:3c43 | 1458:3c43 | Intel      | Xeon E5/Core i7 Ring to P... | 22    | snbep_u... | 912C8764EF |
| 8086:3c44 | 1458:3c44 | Intel      | Xeon E5/Core i7 Ring to Q... | 22    | snbep_u... | 912C8764EF |
| 8086:3c46 | 1458:3c46 | Intel      | Xeon E5/Core i7 Processor... | 22    | snbep_u... | 912C8764EF |
| 8086:3ce6 | 1458:3ce6 | Intel      | Xeon E5/Core i7 QuickPath... | 22    |            | 912C8764EF |
| 8086:6f32 | 8086:6f32 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 21    | bdx_uncore | 2F38C3FD0E |
| 8086:6f33 | 8086:6f33 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 21    | bdx_uncore | 2F38C3FD0E |
| 8086:2088 |           | Intel      | Sky Lake-E DDRIO Registers   | 19    | skx_uncore | 862B2D2013 |
| 8086:3c43 | 1028:0497 | Intel      | Xeon E5/Core i7 Ring to P... | 17    | snbep_u... | 536202A82C |
| 8086:3c44 | 1028:0497 | Intel      | Xeon E5/Core i7 Ring to Q... | 17    | snbep_u... | 536202A82C |
| 8086:3c46 | 1028:0497 | Intel      | Xeon E5/Core i7 Processor... | 17    | snbep_u... | 536202A82C |
| 8086:3ce6 | 1028:0497 | Intel      | Xeon E5/Core i7 QuickPath... | 17    |            | 536202A82C |
| 8086:6f38 | 8086:6f38 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 17    | bdx_uncore | 4860ACD042 |
| 8086:6f30 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6f34 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6f36 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6f37 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6f7d | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:2015 | 1028:0738 | Intel      | Sky Lake-E Ubox Registers    | 15    |            | 862B2D2013 |
| 8086:204c | 1028:0738 | Intel      | Sky Lake-E M3KTI Registers   | 15    | skx_uncore | 862B2D2013 |
| 8086:204d | 1028:0738 | Intel      | Sky Lake-E M3KTI Registers   | 15    | skx_uncore | 862B2D2013 |
| 8086:6f32 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 15    | bdx_uncore | 17BF7A3CBC |
| 8086:6f33 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 15    | bdx_uncore | 17BF7A3CBC |
| 8086:0e30 | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 14    | ivbep_u... | 8C9DD0E965 |
| 8086:0e34 | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 14    | ivbep_u... | 8C9DD0E965 |
| 8086:0e37 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 14    | ivbep_u... | 27399D8580 |
| 8086:3c43 | 1849:3c43 | Intel      | Xeon E5/Core i7 Ring to P... | 13    | snbep_u... | 87E9E3FF1C |
| 8086:3c44 | 1849:3c44 | Intel      | Xeon E5/Core i7 Ring to Q... | 13    | snbep_u... | 87E9E3FF1C |
| 8086:3c46 | 1849:3c46 | Intel      | Xeon E5/Core i7 Processor... | 13    | snbep_u... | 87E9E3FF1C |
| 8086:3ce6 | 1849:3ce6 | Intel      | Xeon E5/Core i7 QuickPath... | 13    |            | 87E9E3FF1C |
| 8086:0e30 | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 12    | ivbep_u... | DD93F62FFC |
| 8086:0e34 | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 12    | ivbep_u... | DD93F62FFC |
| 8086:0e36 | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 12    | ivbep_u... | DD93F62FFC |
| 8086:2058 |           | Intel      | Sky Lake-E KTI 0             | 12    | skx_uncore | 177BF1F346 |
| 8086:6f30 | 1849:6f30 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 11    | bdx_uncore | 70928B7215 |
| 8086:6f34 | 1849:6f34 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 11    | bdx_uncore | 70928B7215 |
| 8086:6f36 | 1849:6f36 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 11    | bdx_uncore | 70928B7215 |
| 8086:6f37 | 1849:6f37 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 11    | bdx_uncore | 70928B7215 |
| 8086:6f7d | 1849:6f7d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 11    |            | 70928B7215 |
| 8086:3c41 | 8086:0000 | Intel      | Sandy Bridge QPI Port 0 P... | 9     | snbep_u... | 813E405E39 |
| 8086:3c42 | 8086:0000 | Intel      | Sandy Bridge QPI Port 1 P... | 9     | snbep_u... | 813E405E39 |
| 8086:3c43 | 8086:4953 | Intel      | Xeon E5/Core i7 Ring to P... | 9     | snbep_u... | 4D5E452411 |
| 8086:3c44 | 8086:4953 | Intel      | Xeon E5/Core i7 Ring to Q... | 9     | snbep_u... | 4D5E452411 |
| 8086:3c46 | 8086:4953 | Intel      | Xeon E5/Core i7 Processor... | 9     | snbep_u... | 4D5E452411 |
| 8086:3ce6 | 8086:4953 | Intel      | Xeon E5/Core i7 QuickPath... | 9     |            | 4D5E452411 |
| 8086:0e30 | 1458:3c46 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 7     | ivbep_u... | B3247E5E9F |
| 8086:0e34 | 1458:3c43 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 7     | ivbep_u... | B3247E5E9F |
| 8086:0e36 | 1458:3c44 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 7     | ivbep_u... | B3247E5E9F |
| 8086:2015 | 1734:122f | Intel      | Sky Lake-E Ubox Registers    | 7     |            | 9BF79EF1CD |
| 8086:2015 | 17aa:7808 | Intel      | Sky Lake-E Ubox Registers    | 7     |            | CEE7ED2CE9 |
| 8086:204c | 17aa:7808 | Intel      | Sky Lake-E M3KTI Registers   | 7     | skx_uncore | CEE7ED2CE9 |
| 8086:204d | 17aa:7808 | Intel      | Sky Lake-E M3KTI Registers   | 7     | skx_uncore | CEE7ED2CE9 |
| 8086:2058 | 17aa:7808 | Intel      | Sky Lake-E KTI 0             | 7     | skx_uncore | CEE7ED2CE9 |
| 8086:2088 | 17aa:7808 | Intel      | Sky Lake-E DDRIO Registers   | 7     | skx_uncore | CEE7ED2CE9 |

### Pic (8259) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:342e |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 669   | i7core_... | 2E1659CD91 |
| 8086:3422 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 667   |            | 2E1659CD91 |
| 8086:3423 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 667   |            | 2E1659CD91 |
| 8086:3438 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 390   | i5500_temp | 2E1659CD91 |
| 8086:3425 |           | Intel      | 7500/5520/5500/X58 Physic... | 248   |            | 7A75936B55 |
| 8086:3426 |           | Intel      | 7500/5520/5500/X58 Routin... | 248   |            | 7A75936B55 |
| 8086:3427 |           | Intel      | 7500/5520/5500 Physical a... | 218   |            | DFA7EF3696 |
| 8086:3428 |           | Intel      | 7500/5520/5500 Routing & ... | 218   |            | DFA7EF3696 |
| 8086:3422 | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 57    |            | ACE51E66CB |
| 8086:3423 | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 57    |            | ACE51E66CB |
| 8086:342e | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 57    | i7core_... | ACE51E66CB |
| 8086:3422 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 46    |            | 28B04C3004 |
| 8086:3423 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 46    |            | 28B04C3004 |
| 8086:342e | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 46    | i7core_... | 28B04C3004 |
| 8086:3422 | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 24    |            | 69CBBFEC14 |
| 8086:3423 | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 24    |            | 69CBBFEC14 |
| 8086:342e | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 24    | i7core_... | 69CBBFEC14 |
| 8086:3422 | 0086:0022 | Intel      | 7500/5520/5500/X58 I/O Hu... | 21    |            | DD68978E2B |
| 8086:3423 | 0086:0023 | Intel      | 7500/5520/5500/X58 I/O Hu... | 21    |            | DD68978E2B |
| 8086:342e | 0086:002e | Intel      | 7500/5520/5500/X58 I/O Hu... | 21    | i7core_... | DD68978E2B |
| 8086:3422 | 0028:006d | Intel      | 7500/5520/5500/X58 I/O Hu... | 19    |            | 08F4C825CC |
| 8086:3423 | 0028:006d | Intel      | 7500/5520/5500/X58 I/O Hu... | 19    |            | 08F4C825CC |
| 8086:342e | 0028:006d | Intel      | 7500/5520/5500/X58 I/O Hu... | 19    | i7core_... | 08F4C825CC |
| 8086:3422 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 8     |            | 1B777C6F08 |
| 8086:3423 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 8     |            | 1B777C6F08 |
| 8086:3425 | 0043:0063 | Intel      | 7500/5520/5500/X58 Physic... | 8     |            | 1B777C6F08 |
| 8086:3426 | 0043:0063 | Intel      | 7500/5520/5500/X58 Routin... | 8     |            | 1B777C6F08 |
| 8086:3427 | 0043:0063 | Intel      | 7500/5520/5500 Physical a... | 8     |            | 1B777C6F08 |
| 8086:3428 | 0043:0063 | Intel      | 7500/5520/5500 Routing & ... | 8     |            | 1B777C6F08 |
| 8086:342e | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 8     | i7core_... | 1B777C6F08 |
| 8086:3438 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 8     | i5500_temp | 1B777C6F08 |
| 8086:3422 | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 6     |            | 61DFD26E01 |
| 8086:3423 | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 6     |            | 61DFD26E01 |
| 8086:3425 | 0086:00dc | Intel      | 7500/5520/5500/X58 Physic... | 6     |            | 61DFD26E01 |
| 8086:3426 | 0086:00dc | Intel      | 7500/5520/5500/X58 Routin... | 6     |            | 61DFD26E01 |
| 8086:3427 | 0086:00dc | Intel      | 7500/5520/5500 Physical a... | 6     |            | 61DFD26E01 |
| 8086:3428 | 0086:00dc | Intel      | 7500/5520/5500 Routing & ... | 6     |            | 61DFD26E01 |
| 8086:342e | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 6     | i7core_... | 61DFD26E01 |
| 8086:3438 | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 6     | i5500_temp | 61DFD26E01 |
| 8086:3422 | 0034:0027 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | 4874F3ABB6 |
| 8086:3422 | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | FE3D758C20 |
| 8086:3422 | 0086:00e2 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | D577FE5BA4 |
| 8086:3423 | 0034:0027 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | 4874F3ABB6 |
| 8086:3423 | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | FE3D758C20 |
| 8086:3423 | 0086:00e2 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | D577FE5BA4 |
| 8086:3425 | 0034:0027 | Intel      | 7500/5520/5500/X58 Physic... | 4     |            | 4874F3ABB6 |
| 8086:3425 | 0086:00da | Intel      | 7500/5520/5500/X58 Physic... | 4     |            | FE3D758C20 |
| 8086:3425 | 0086:00e2 | Intel      | 7500/5520/5500/X58 Physic... | 4     |            | D577FE5BA4 |
| 8086:3426 | 0034:0027 | Intel      | 7500/5520/5500/X58 Routin... | 4     |            | 4874F3ABB6 |
| 8086:3426 | 0086:00da | Intel      | 7500/5520/5500/X58 Routin... | 4     |            | FE3D758C20 |
| 8086:3426 | 0086:00e2 | Intel      | 7500/5520/5500/X58 Routin... | 4     |            | D577FE5BA4 |
| 8086:3427 | 0034:0027 | Intel      | 7500/5520/5500 Physical a... | 4     |            | 4874F3ABB6 |
| 8086:3427 | 0086:00da | Intel      | 7500/5520/5500 Physical a... | 4     |            | FE3D758C20 |
| 8086:3427 | 0086:00e2 | Intel      | 7500/5520/5500 Physical a... | 4     |            | D577FE5BA4 |
| 8086:3428 | 0034:0027 | Intel      | 7500/5520/5500 Routing & ... | 4     |            | 4874F3ABB6 |
| 8086:3428 | 0086:00da | Intel      | 7500/5520/5500 Routing & ... | 4     |            | FE3D758C20 |
| 8086:3428 | 0086:00e2 | Intel      | 7500/5520/5500 Routing & ... | 4     |            | D577FE5BA4 |
| 8086:342e | 0034:0027 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     | i7core_... | 4874F3ABB6 |
| 8086:342e | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     | i7core_... | FE3D758C20 |
| 8086:342e | 0086:00e2 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     | i7core_... | D577FE5BA4 |
| 8086:3438 | 0034:0027 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     | i5500_temp | 4874F3ABB6 |
| 8086:3438 | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     | i5500_temp | FE3D758C20 |
| 8086:3438 | 0086:00e2 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     | i5500_temp | D577FE5BA4 |
| 8086:3422 | 0086:00de | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     |            | 3AB9D48A33 |
| 8086:3423 | 0086:00de | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     |            | 3AB9D48A33 |
| 8086:3425 | 0086:00de | Intel      | 7500/5520/5500/X58 Physic... | 2     |            | 3AB9D48A33 |
| 8086:3426 | 0086:00de | Intel      | 7500/5520/5500/X58 Routin... | 2     |            | 3AB9D48A33 |
| 8086:3427 | 0086:00de | Intel      | 7500/5520/5500 Physical a... | 2     |            | 3AB9D48A33 |
| 8086:3428 | 0086:00de | Intel      | 7500/5520/5500 Routing & ... | 2     |            | 3AB9D48A33 |
| 8086:342e | 0086:00de | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     | i7core_... | 3AB9D48A33 |
| 8086:3438 | 0086:00de | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     | i5500_temp | 3AB9D48A33 |
| 8086:3422 | 0058:0003 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | 7F55996B62 |
| 8086:3422 | 0086:0000 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | CBBE408AAC |
| 8086:3423 | 0058:0003 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | 7F55996B62 |
| 8086:3423 | 0086:0000 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | CBBE408AAC |
| 8086:3425 | 0086:0000 | Intel      | 7500/5520/5500/X58 Physic... | 1     |            | CBBE408AAC |
| 8086:3426 | 0086:0000 | Intel      | 7500/5520/5500/X58 Routin... | 1     |            | CBBE408AAC |
| 8086:3427 | 0086:0000 | Intel      | 7500/5520/5500 Physical a... | 1     |            | CBBE408AAC |
| 8086:3428 | 0086:0000 | Intel      | 7500/5520/5500 Routing & ... | 1     |            | CBBE408AAC |
| 8086:342e | 0058:0003 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     | i7core_... | 7F55996B62 |
| 8086:342e | 0086:0000 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     | i7core_... | CBBE408AAC |
| 8086:3438 | 0086:0000 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     | i5500_temp | CBBE408AAC |

### Pic (io(x)-apic) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2f2c | 8086:0000 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 217   |            | F90168C69D |
| 8086:342f |           | Intel      | 7500/5520/5500/X58 Truste... | 215   |            | DFA7EF3696 |
| 8086:342d |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 173   |            | D9ED4F04A3 |
| 8086:2026 | 8086:2026 | Intel      | Sky Lake-E IOAPIC            | 165   |            | 2D1D9030E8 |
| 8086:2036 | 8086:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 165   |            | 2D1D9030E8 |
| 8086:3c2c | 8086:3c2c | Intel      | Xeon E5/Core i7 I/O APIC     | 123   |            | C6DCB137FB |
| 8086:0e2c | 8086:0e2c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 85    |            | 150AFCB2D1 |
| 1106:5364 |           | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 79    |            | 01E1F5151C |
| 8086:3c2c | 1043:84ef | Intel      | Xeon E5/Core i7 I/O APIC     | 78    |            | 610B68BB7B |
| 8086:6f2c | 8086:0000 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 57    |            | 4860ACD042 |
| 1106:5327 |           | VIA Tec... | P4M890 I/O APIC Interrupt... | 48    |            | BA603AC9C0 |
| 8086:0e2c | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 46    |            | F0DC31F93D |
| 8086:3c2c | 103c:18a8 | Intel      | Xeon E5/Core i7 I/O APIC     | 28    |            | 799CC190DB |
| 8086:2f2c | 1849:2f2c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 27    |            | 6FEB0AEC47 |
| 8086:2f2c | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 24    |            | 09B0FBCF47 |
| 1106:5336 |           | VIA Tec... | K8M890CE I/O APIC Interru... | 23    |            | 20512BBBE4 |
| 8086:3c2c | 1458:5000 | Intel      | Xeon E5/Core i7 I/O APIC     | 22    |            | 912C8764EF |
| 1106:5308 | 1849:5308 | VIA Tec... | PT894 I/O APIC Interrupt ... | 21    |            | 517B90D6F4 |
| 8086:2f2c | 1028:0617 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 20    |            | C050F79E2B |
| 8086:3504 |           | Intel      | 6311ESB/6321ESB I/OxAPIC ... | 18    |            | 41C18A9562 |
| 8086:3c2c | 1028:0497 | Intel      | Xeon E5/Core i7 I/O APIC     | 17    |            | 536202A82C |
| 8086:6f2c | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:2026 | 1028:0738 | Intel      | Sky Lake-E IOAPIC            | 15    |            | 862B2D2013 |
| 8086:2036 | 1028:0738 | Intel      | Sky Lake-E IOxAPIC Config... | 15    |            | 862B2D2013 |
| 8086:0e2c | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 14    |            | 8C9DD0E965 |
| 8086:3c2c | 1849:3c2c | Intel      | Xeon E5/Core i7 I/O APIC     | 13    |            | 87E9E3FF1C |
| 1106:5364 | 1106:5364 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 12    |            | F3B2236C7A |
| 8086:0e2c | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 12    |            | DD93F62FFC |
| 8086:0e2c | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 12    |            | 27399D8580 |
| 8086:2026 | 8086:0000 | Intel      | Sky Lake-E IOAPIC            | 12    |            | 672448ACFD |
| 8086:2036 | 8086:0000 | Intel      | Sky Lake-E IOxAPIC Config... | 12    |            | 672448ACFD |
| 8086:2f2c | 1028:0618 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 11    |            | 7172CF4F40 |
| 8086:6f2c | 1849:6f2c | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 11    |            | 70928B7215 |
| 8086:3c2c | 8086:4953 | Intel      | Xeon E5/Core i7 I/O APIC     | 10    |            | 4D5E452411 |
| 1106:5364 | 103c:3030 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 9     |            | E81CAC058D |
| 1106:5364 | 1734:10f7 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 7     |            | 3200F41CF0 |
| 8086:0e2c | 1458:5000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 7     |            | B3247E5E9F |
| 8086:2026 | 17aa:7808 | Intel      | Sky Lake-E IOAPIC            | 7     |            | CEE7ED2CE9 |
| 8086:2036 | 17aa:7808 | Intel      | Sky Lake-E IOxAPIC Config... | 7     |            | CEE7ED2CE9 |
| 8086:2f2c | 15d9:0857 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 7     |            | 7CF4F8ED17 |
| 8086:3c2c | 1043:84f0 | Intel      | Xeon E5/Core i7 I/O APIC     | 7     |            | 6ACBF140D4 |
| 8086:6f2c | 1028:0617 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 7     |            | 3440F55127 |
| 8086:0e2c | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 6     |            | 2FC41158D5 |
| 8086:0e2c | 1043:84f0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 6     |            | A4C832AB44 |
| 8086:2026 | 1734:122f | Intel      | Sky Lake-E IOAPIC            | 6     |            | 9BF79EF1CD |
| 8086:2036 | 1734:122f | Intel      | Sky Lake-E IOxAPIC Config... | 6     |            | 9BF79EF1CD |
| 8086:2f2c | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 6     |            | 0B1954F5E9 |
| 8086:342d | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 6     |            | 61DFD26E01 |
| 8086:342f | 0086:00dc | Intel      | 7500/5520/5500/X58 Truste... | 6     |            | 61DFD26E01 |
| 8086:3c2c | 1028:0496 | Intel      | Xeon E5/Core i7 I/O APIC     | 6     |            | 80E68A5C66 |
| 8086:3c2c | 1734:11b5 | Intel      | Xeon E5/Core i7 I/O APIC     | 6     |            | 85A9B68DD8 |
| 1106:5351 |           | VIA Tec... | VT3351 I/O APIC Interrupt... | 5     |            | 9B7D8BD5FF |
| 1106:5364 | 1849:5364 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 5     |            | 6410827A2F |
| 8086:0e2c | 1028:05d4 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 5     |            | 0D40B6190B |
| 8086:0e2c | 1849:0e2c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 5     |            | D3383D57EF |
| 8086:2026 | 1590:18a9 | Intel      | Sky Lake-E IOAPIC            | 5     |            | 3120E02C21 |
| 8086:2036 | 1590:18a9 | Intel      | Sky Lake-E IOxAPIC Config... | 5     |            | 3120E02C21 |
| 8086:3c2c | 1028:0495 | Intel      | Xeon E5/Core i7 I/O APIC     | 5     |            | 1AC850D5B7 |
| 8086:6f2c | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 5     |            | 23F12250E5 |
| 1106:5238 |           | VIA Tec... | K8T890 I/O APIC Interrupt... | 4     |            | D9174E33E4 |
| 1106:5336 | 1043:8297 | VIA Tec... | K8M890CE I/O APIC Interru... | 4     |            | CED2DCBAC9 |
| 1106:5364 | 1019:2125 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 4     |            | 814C427D36 |
| 8086:0326 | 103c:12f1 | Intel      | 6700/6702PXH I/OxAPIC Int... | 4     |            | AD9D1EDCBB |
| 8086:0327 | 103c:12f1 | Intel      | 6700PXH I/OxAPIC Interrup... | 4     |            | AD9D1EDCBB |
| 8086:0e2c | 8086:35a0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     |            | FE1E6CFF79 |
| 8086:2f2c | 1028:0619 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | F96F352657 |
| 8086:2f2c | 1028:064c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | 82F399DFE3 |
| 8086:2f2c | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | FD108DE325 |
| 8086:342d | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | FE3D758C20 |
| 8086:342d | 0086:00e2 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | D577FE5BA4 |
| 8086:342f | 0034:0027 | Intel      | 7500/5520/5500/X58 Truste... | 4     |            | 4874F3ABB6 |
| 8086:342f | 0086:00da | Intel      | 7500/5520/5500/X58 Truste... | 4     |            | FE3D758C20 |
| 8086:342f | 0086:00e2 | Intel      | 7500/5520/5500/X58 Truste... | 4     |            | D577FE5BA4 |
| 8086:3c2c | 1028:05d4 | Intel      | Xeon E5/Core i7 I/O APIC     | 4     |            | F62AEF3E7A |
| 8086:3c2c | 17aa:1026 | Intel      | Xeon E5/Core i7 I/O APIC     | 4     |            | 7EB1F254C9 |
| 8086:3c2c | 17aa:1027 | Intel      | Xeon E5/Core i7 I/O APIC     | 4     |            | E3C6A7B793 |
| 8086:6f2c | 1462:7885 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     |            | 6F27FFD7AA |
| 1106:5327 | 1631:e035 | VIA Tec... | P4M890 I/O APIC Interrupt... | 3     |            | 089D020111 |
| 1106:5353 | 17aa:388a | VIA Tec... | VX800/VX820 APIC and Cent... | 3     |            | 4762847735 |
| 8086:0326 |           | Intel      | 6700/6702PXH I/OxAPIC Int... | 3     |            | 4FDE34B201 |
| 8086:0e2c | 1734:11b5 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     |            | D018E3FE5A |
| 8086:2026 | 17aa:1036 | Intel      | Sky Lake-E IOAPIC            | 3     |            | E7CE5A5A00 |
| 8086:2026 | 17aa:1038 | Intel      | Sky Lake-E IOAPIC            | 3     |            | 5658A2FB98 |
| 8086:2026 | 1849:2026 | Intel      | Sky Lake-E IOAPIC            | 3     |            | 35C171899E |
| 8086:2026 | 8086:35ce | Intel      | Sky Lake-E IOAPIC            | 3     |            | D373AF93CD |
| 8086:2036 | 17aa:1036 | Intel      | Sky Lake-E IOxAPIC Config... | 3     |            | E7CE5A5A00 |
| 8086:2036 | 17aa:1038 | Intel      | Sky Lake-E IOxAPIC Config... | 3     |            | 5658A2FB98 |
| 8086:2036 | 1849:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 3     |            | 35C171899E |
| 8086:3c2c | 1028:0541 | Intel      | Xeon E5/Core i7 I/O APIC     | 3     |            | BEA2C0B6F8 |
| 8086:3c2c | 1462:7735 | Intel      | Xeon E5/Core i7 I/O APIC     | 3     |            | 02CD4D8346 |
| 8086:3c2c | 8086:357e | Intel      | Xeon E5/Core i7 I/O APIC     | 3     |            | 0FADD1EBE3 |
| 8086:6f2c | 15d9:0834 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     |            | 72BAE0BDE8 |
| 1106:5327 | 1849:5327 | VIA Tec... | P4M890 I/O APIC Interrupt... | 2     |            | DAD584057B |
| 1106:5353 |           | VIA Tec... | VX800/VX820 APIC and Cent... | 2     |            | 503D9A6D06 |
| 1106:5353 | 144d:c04e | VIA Tec... | VX800/VX820 APIC and Cent... | 2     |            | 085B83A79C |
| 8086:0326 | 15d9:7980 | Intel      | 6700/6702PXH I/OxAPIC Int... | 2     |            | 8EB1C21341 |
| 8086:0e2c | 1028:05d3 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | EDCCC7AAD2 |
| 8086:0e2c | 15d9:0626 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | 00FDD71981 |
| 8086:0e2c | 15d9:062a | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | 2E139151DE |
| 8086:0e2c | 15d9:062b | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | F791C179A5 |

### Pic (io-apic) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:7451 | 1022:7450 | AMD        | AMD-8131 PCI-X IOAPIC        | 4     |            | A94946D561 |
| 1022:7451 | 10f1:2895 | AMD        | AMD-8131 PCI-X IOAPIC        | 1     |            | 768571B831 |
| 1022:7459 | 1022:7459 | AMD        | AMD-8132 PCI-X IOAPIC        | 1     |            | 677776B636 |

### Power pc (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1957:c006 | 1a56:1201 | Freesca... | MPC8308                      | 6     |            | 7DC713CD9F |
| 1957:00b6 | 1a56:1103 | Freesca... | MPC8314E                     | 2     |            | B07AC7C26E |
| 1957:0085 | 110a:4046 | Freesca... | MPC8347 PBGA                 | 1     |            | 60A7685D8D |
| 1957:00b6 | 1a56:1101 | Freesca... | MPC8314E                     | 1     |            | FC18CDC2FD |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:16bc | 14e4:0000 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 395   | sdhci_pci  | 066B825941 |
| 14e4:16bc | 1025:0647 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 377   | sdhci_pci  | B732F94275 |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 260   | sdhci_pci  | 902AD35DB3 |
| 197b:2381 | 1043:1a07 | JMicron... | Standard SD Host Controller  | 219   | sdhci_pci  | 11F1CDC49A |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 202   | sdhci_pci  | 71A92492E3 |
| 8086:9d2d | 8086:9d2d | Intel      | Sunrise Point-LP Secure D... | 199   | sdhci_pci  | AF70469300 |
| 14e4:16bc | 1025:0504 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 196   | sdhci_pci  | 85BCF858C5 |
| 1180:0822 | 17aa:20c8 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 195   | sdhci_pci  | DB936567F0 |
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 194   | sdhci_pci  | 021617B9A0 |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 182   | sdhci_pci  | 71A92492E3 |
| 8086:31d0 | 8086:7270 | Intel      | SD Host Controller           | 165   | sdhci_pci  | 021617B9A0 |
| 1217:8221 | 1028:0493 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 133   | sdhci_pci  | 33617DD1A8 |
| 14e4:16bc | 1025:0775 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 131   | sdhci_pci  | 98166600FA |
| 1180:e822 | 1028:040a | Ricoh      | MMC/SD Host Controller       | 129   | sdhci_pci  | 576A6491F3 |
| 1022:7813 | 17aa:3801 | AMD        | FCH SD Flash Controller      | 128   | sdhci_pci  | 779BFC3B47 |
| 1180:e822 | 104d:9071 | Ricoh      | MMC/SD Host Controller       | 123   | sdhci_pci  | 03E0270FDD |
| 104c:803c | 1025:011f | Texas I... | PCIxx12 SDA Standard Comp... | 122   | sdhci_pci  | 6A05B72968 |
| 1022:7806 | 1022:7806 | AMD        | FCH SD Flash Controller      | 120   | sdhci_pci  | 0B29DCFBC0 |
| 1217:8221 | 1028:0534 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 117   | sdhci_pci  | 98420A7D92 |
| 1180:0822 | 1028:0233 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 107   | sdhci_pci  | 2A4C5F6EEC |
| 197b:2391 | 103c:161c | JMicron... | Standard SD Host Controller  | 100   | sdhci_pci  | 701E56A49F |
| 197b:2391 | 103c:179b | JMicron... | Standard SD Host Controller  | 91    | sdhci_pci  | 7D39BC1331 |
| 10ec:5209 | 10ec:5209 | Realtek... | RTS5209 PCI Express Card ... | 88    | rtsx_pci   | 0233ED2211 |
| 197b:2391 | 103c:17f6 | JMicron... | Standard SD Host Controller  | 85    | sdhci_pci  | D0705EF193 |
| 1217:8621 | 17aa:5068 | O2 Micro   | SD/MMC Card Reader Contro... | 79    | sdhci_pci  | 893F642CBB |
| 1180:0822 | 1028:022f | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 72    | sdhci_pci  | 06130B24C5 |
| 8086:9d2b | 8086:7270 | Intel      | Skylake-U/Y SCC: eMMC        | 67    | sdhci_pci  | 36AA4B2B34 |
| 1217:8520 | 1028:05cb | O2 Micro   | SD/MMC Card Reader Contro... | 66    | sdhci_pci  | EF82F4635D |
| 8086:9df5 | 8086:7270 | Intel      | BayHubTech Integrated SD ... | 66    | sdhci_pci  | 6AFF8771B1 |
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
| 8086:9d2d | 8086:7270 | Intel      | Sunrise Point-LP Secure D... | 54    | sdhci_pci  | B1128F0534 |
| 17a0:9755 | 8086:2081 | Genesys... | GL9755 SD Host Controller    | 53    | sdhci_pci  | 92AA2017B9 |
| 1217:8321 | 1028:0494 | O2 Micro   | OZ600RJ0/OZ900RJ0/OZ600RJ... | 51    | sdhci_pci  | E58B9D7EA5 |
| 1217:8621 | 17aa:381f | O2 Micro   | SD/MMC Card Reader Contro... | 49    | sdhci_pci  | C45342870C |
| 104c:803c | 1179:ff00 | Texas I... | PCIxx12 SDA Standard Comp... | 48    | sdhci_pci  | 8E44C9EDAF |
| 1217:8520 | 1028:05ca | O2 Micro   | SD/MMC Card Reader Contro... | 48    | sdhci_pci  | 9E790BA3F0 |
| 14e4:16bc | 14e4:96bc | Broadco... | BCM57765/57785 SDXC/MMC C... | 48    | sdhci_pci  | 5372B6674E |
| 17a0:9750 | 17aa:2279 | Genesys... | GL9750 SD Host Controller    | 48    | sdhci_pci  | 2444839350 |
| 1022:7813 | 1025:104b | AMD        | FCH SD Flash Controller      | 47    | sdhci_pci  | 6E75E7C288 |
| 1180:0822 | 103c:7008 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 46    | sdhci_pci  | 383932E73B |
| 10ec:5209 | 103c:3388 | Realtek... | RTS5209 PCI Express Card ... | 45    | rtsx_pci   | 482481E697 |
| 1180:0822 | 1025:011e | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 45    | sdhci_pci  | 3C8537DFE3 |
| 1217:8621 | 1217:0002 | O2 Micro   | SD/MMC Card Reader Contro... | 45    | sdhci_pci  | 478CA880AB |
| 8086:2294 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 45    | sdhci_pci  | CABBA2C402 |
| 1969:3010 | 1025:076b | Qualcom... | Secure Digital Card Reader   | 44    | sdhci_pci  | 212881FBEB |
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
| 104c:803c | 1179:ff02 | Texas I... | PCIxx12 SDA Standard Comp... | 38    | sdhci_pci  | 3F0EBD44AD |
| 1217:7120 | 10cf:143d | O2 Micro   | Integrated MMC/SD Controller | 38    | sdhci_pci  | 3B7266D323 |
| 1217:8520 | 17aa:3800 | O2 Micro   | SD/MMC Card Reader Contro... | 38    | sdhci_pci  | D63399B396 |
| 197b:2391 | 103c:1618 | JMicron... | Standard SD Host Controller  | 38    | sdhci_pci  | EA1BD5E314 |
| 1022:7813 | 103c:21f7 | AMD        | FCH SD Flash Controller      | 37    | sdhci_pci  | 814D85CF91 |
| 1180:0822 | 1028:01f5 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 37    | sdhci_pci  | 32C3521A2E |
| 1180:e822 | 103c:146d | Ricoh      | MMC/SD Host Controller       | 37    | sdhci_pci  | 523C397AB6 |
| 197b:2391 | 103c:18df | JMicron... | Standard SD Host Controller  | 37    | sdhci_pci  | 3E6A2F7B59 |
| 1180:0822 | 103c:1521 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 36    | sdhci_pci  | FFC46C9472 |
| 1180:0822 | 1028:01bd | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 35    | sdhci_pci  | 3EB7729825 |
| 1180:0822 | 104d:9035 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 35    | sdhci_pci  | 1A9761824E |
| 1180:0822 | 10f7:8338 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 35    | sdhci_pci  | 4502B92271 |
| 1217:8520 | 1028:05de | O2 Micro   | SD/MMC Card Reader Contro... | 35    | sdhci_pci  | EA59351ECE |
| 14e4:16bc | 1025:0742 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 35    | sdhci_pci  | 342F07FA37 |
| 8086:9d2b | 8086:9d2b | Intel      | Skylake-U/Y SCC: eMMC        | 35    | sdhci_pci  | 02F641EA60 |
| 1217:8221 | 1028:0532 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 34    | sdhci_pci  | 04D10F10D8 |
| 1217:8221 | 1028:053c | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 34    | sdhci_pci  | EE7236C5D8 |
| 1217:8320 | 1028:04a3 | O2 Micro   | OZ600RJ1/OZ900RJ1 SD/MMC ... | 34    | sdhci_pci  | EE6C9C38B0 |
| 1217:8321 | 1028:049a | O2 Micro   | OZ600RJ0/OZ900RJ0/OZ600RJ... | 34    | sdhci_pci  | 33B9916878 |
| 14e4:16bc | 1025:0500 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 34    | sdhci_pci  | 499479904D |
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

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a324 | 8086:7270 | Intel      | Cannon Lake PCH SPI Contr... | 436   | intel_s... | E8B8B03EBD |
| 8086:a324 | 1043:8694 | Intel      | Cannon Lake PCH SPI Contr... | 301   | intel_s... | 36EBF65D44 |
| 8086:9da4 | 8086:7270 | Intel      | Cannon Point-LP SPI Contr... | 275   |            | 6AFF8771B1 |
| 8086:a324 | 1025:1331 | Intel      | Cannon Lake PCH SPI Contr... | 119   | intel_spi  | 38688703F4 |
| 8086:a368 | 1025:1331 | Intel      | Cannon Lake PCH Serial IO... | 119   | intel_lpss | 38688703F4 |
| 8086:a369 | 1025:1331 | Intel      | Cannon Lake PCH Serial IO... | 119   | intel_lpss | 38688703F4 |
| 8086:9da4 | 8086:2074 | Intel      | Cannon Point-LP SPI Contr... | 116   |            | 7CA350189C |
| 8086:a324 | 1028:0905 | Intel      | Cannon Lake PCH SPI Contr... | 113   | intel_s... | 9CDE952049 |
| 8086:a368 | 1028:0905 | Intel      | Cannon Lake PCH Serial IO... | 113   | intel_l... | 9CDE952049 |
| 8086:a369 | 1028:0905 | Intel      | Cannon Lake PCH Serial IO... | 113   | intel_l... | 9CDE952049 |
| 8086:02a4 | 17aa:5079 | Intel      | Comet Lake SPI (flash) Co... | 107   | intel_s... | 0BC4073D23 |
| 8086:a324 | 1849:a324 | Intel      | Cannon Lake PCH SPI Contr... | 102   | intel_s... | 839B20476A |
| 8086:a324 | 1028:087c | Intel      | Cannon Lake PCH SPI Contr... | 98    | intel_spi  | 31A6F21CCD |
| 8086:a368 | 1028:087c | Intel      | Cannon Lake PCH Serial IO... | 98    | intel_l... | 31A6F21CCD |
| 8086:a369 | 1028:087c | Intel      | Cannon Lake PCH Serial IO... | 98    | intel_l... | 31A6F21CCD |
| 8086:9da4 | 17aa:2279 | Intel      | Cannon Point-LP SPI Contr... | 96    |            | 2444839350 |
| 8086:9de8 | 17aa:2279 | Intel      | Cannon Point-LP Serial IO... | 96    | intel_l... | 2444839350 |
| 8086:9da4 | 103c:8549 | Intel      | Cannon Point-LP SPI Contr... | 95    |            | 9A264DBCB2 |
| 8086:9de8 | 103c:8549 | Intel      | Cannon Point-LP Serial IO... | 95    | intel_l... | 9A264DBCB2 |
| 8086:9de9 | 103c:8549 | Intel      | Cannon Point-LP Serial IO... | 95    | intel_l... | 9A264DBCB2 |
| 8086:9da4 | 17aa:2292 | Intel      | Cannon Point-LP SPI Contr... | 88    |            | FBF4582983 |
| 8086:9de8 | 17aa:2292 | Intel      | Cannon Point-LP Serial IO... | 88    | intel_l... | FBF4582983 |
| 8086:9de9 | 17aa:2292 | Intel      | Cannon Point-LP Serial IO... | 87    | intel_l... | FBF4582983 |
| 8086:9ce6 | 8086:9ce6 | Intel      | Wildcat Point-LP Serial I... | 85    | spi_pxa... | C0ED6370C5 |
| 8086:02a4 | 8086:7270 | Intel      | Comet Lake SPI (flash) Co... | 82    | intel_s... | 94D2095D5F |
| 8086:9da4 | 1028:08af | Intel      | Cannon Point-LP SPI Contr... | 82    |            | 80857F497B |
| 8086:9de8 | 1028:08af | Intel      | Cannon Point-LP Serial IO... | 82    | intel_l... | 80857F497B |
| 8086:9de9 | 1028:08af | Intel      | Cannon Point-LP Serial IO... | 82    | intel_l... | 80857F497B |
| 8086:02a4 | 1028:0962 | Intel      | Comet Lake SPI (flash) Co... | 77    | intel_s... | 9E26259821 |
| 8086:02e8 | 1028:0962 | Intel      | Serial IO I2C Host Contro... | 77    | intel_l... | 9E26259821 |
| 8086:02e9 | 1028:0962 | Intel      | Comet Lake Serial IO I2C ... | 77    | intel_l... | 9E26259821 |
| 8086:a324 | 1025:1264 | Intel      | Cannon Lake PCH SPI Contr... | 74    | intel_s... | 9971E42809 |
| 8086:a368 | 1025:1264 | Intel      | Cannon Lake PCH Serial IO... | 74    | intel_lpss | 9971E42809 |
| 8086:a369 | 1025:1264 | Intel      | Cannon Lake PCH Serial IO... | 74    | intel_lpss | 9971E42809 |
| 8086:9da4 | 17aa:5072 | Intel      | Cannon Point-LP SPI Contr... | 67    |            | 62C94909C7 |
| 10de:1adb | 10de:0000 | Nvidia     | TU106 USB Type-C UCSI Con... | 62    | i2c_nvi... | 2735F9B34E |
| 8086:06a4 | 1043:8694 | Intel      | Comet Lake PCH SPI Contro... | 61    | intel_s... | BBA08D40AD |
| 8086:9da4 | 17aa:380c | Intel      | Cannon Point-LP SPI Contr... | 61    |            | 2ED0E50384 |
| 8086:9de8 | 17aa:3813 | Intel      | Cannon Point-LP Serial IO... | 61    | intel_l... | 2ED0E50384 |
| 8086:a324 | 17aa:3803 | Intel      | Cannon Lake PCH SPI Contr... | 60    | intel_s... | AB6647F9DA |
| 8086:a368 | 17aa:3805 | Intel      | Cannon Lake PCH Serial IO... | 60    | intel_l... | AB6647F9DA |
| 8086:a369 | 17aa:380b | Intel      | Cannon Lake PCH Serial IO... | 60    | intel_l... | AB6647F9DA |
| 8086:06e8 | 1043:8694 | Intel      | Comet Lake PCH Serial IO ... | 58    | intel_l... | BBA08D40AD |
| 8086:06e9 | 1043:8694 | Intel      | Comet Lake PCH Serial IO ... | 58    | intel_l... | BBA08D40AD |
| 8086:06a4 | 8086:7270 | Intel      | Comet Lake PCH SPI Contro... | 57    | intel_s... | 3A3BF28C3A |
| 8086:9da4 | 8086:9da4 | Intel      | Cannon Point-LP SPI Contr... | 57    |            | 203BB4369E |
| 8086:02a4 | 8086:2081 | Intel      | Comet Lake SPI (flash) Co... | 54    | intel_s... | 92AA2017B9 |
| 8086:02e8 | 8086:2081 | Intel      | Serial IO I2C Host Contro... | 54    | intel_l... | 92AA2017B9 |
| 8086:02ea | 8086:2081 | Intel      | Comet Lake PCH-LP LPSS: I... | 54    | intel_l... | 92AA2017B9 |
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
| 8086:5ac8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 35    | pwm_lpss   | 867223F2CF |
| 8086:34a4 | 17aa:3842 | Intel      | Ice Lake-LP SPI Controller   | 34    | intel_s... | 2ABD900016 |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2a47 | 17aa:20ec | Intel      | Mobile 4 Series Chipset A... | 132   | serial     | DB936567F0 |
| 8086:3b67 | 17aa:2162 | Intel      | 5 Series/3400 Series Chip... | 128   | serial     | 5DC4A1E557 |
| 8086:8c3d | 1458:1c3a | Intel      | 8 Series/C220 Series Chip... | 125   | serial     | D8CF951CC3 |
| 8086:1e3d | 17aa:21f3 | Intel      | 7 Series/C210 Series Chip... | 109   | serial     | C9503690D6 |
| 8086:1c3d | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 108   | serial     | 11FDC99047 |
| 8086:29b7 | 1028:0211 | Intel      | 82Q35 Express Serial KT C... | 91    | serial     | 962E0B75E4 |
| 8086:1e3d | 103c:3397 | Intel      | 7 Series/C210 Series Chip... | 90    | serial     | 9C1343DD9B |
| 8086:8c3d | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 89    | serial     | 0FC3ABDB1C |
| 8086:2e17 | 1028:0420 | Intel      | 4 Series Chipset Serial K... | 84    | serial     | 340184FB36 |
| 8086:1e3d | 1028:0577 | Intel      | 7 Series/C210 Series Chip... | 83    | serial     | 3649E87174 |
| 8086:2e17 | 1028:027f | Intel      | 4 Series Chipset Serial K... | 79    | serial     | 8F0C6ED152 |
| 8086:9c3d | 103c:198f | Intel      | 8 Series HECI KT             | 75    | serial     | 6573923D55 |
| 8086:1e3d | 17aa:21fa | Intel      | 7 Series/C210 Series Chip... | 74    | serial     | 0D334AF224 |
| 8086:1c3d | 103c:161c | Intel      | 6 Series/C200 Series Chip... | 72    | serial     | 37F8994BEF |
| 8086:1e3d | 103c:339a | Intel      | 7 Series/C210 Series Chip... | 72    | serial     | BA7CCF28B7 |
| 8086:1c3d | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 69    | serial     | 3F6DDBD81D |
| 8086:1c3d | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 68    | serial     | B948FE4DD5 |
| 8086:1c3d | 1028:047e | Intel      | 6 Series/C200 Series Chip... | 65    | serial     | 959E3DDE54 |
| 8086:8c3d | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 64    | serial     | D8309CFECF |
| 8086:9c3d | 17aa:220c | Intel      | 8 Series HECI KT             | 63    | serial     | 4C600416F9 |
| 8086:1c3d | 103c:1495 | Intel      | 6 Series/C200 Series Chip... | 61    | serial     | 660C4FF2ED |
| 8086:1e3d | 17aa:21f6 | Intel      | 7 Series/C210 Series Chip... | 59    | serial     | B79CAD571B |
| 8086:2e17 | 103c:3048 | Intel      | 4 Series Chipset Serial K... | 59    | serial     | 39204D22AE |
| 8086:9d3d | 103c:8079 | Intel      | Sunrise Point-LP Active M... | 59    | serial     | BC4CDD85CE |
| 10ec:816a | 17aa:5081 | Realtek... | RTL8111xP UART #1            | 58    | serial     | 6B6205BC5D |
| 10ec:816b | 17aa:5081 | Realtek... | RTL8111xP UART #2            | 58    | serial     | 6B6205BC5D |
| 8086:1e3d | 103c:179b | Intel      | 7 Series/C210 Series Chip... | 56    | serial     | 7D39BC1331 |
| 8086:2e17 | 1734:114c | Intel      | 4 Series Chipset Serial K... | 56    | serial     | 8159354A14 |
| 8086:8c3d | 103c:18e7 | Intel      | 8 Series/C220 Series Chip... | 56    | serial     | 9844F6635C |
| 8086:06fc | 1028:097d | Intel      | 400 Series Chipset Family... | 54    | intel_i... | 8C072EA1C4 |
| 8086:1c3d | 103c:1497 | Intel      | 6 Series/C200 Series Chip... | 54    | serial     | 7FA5AD3E42 |
| 8086:3b67 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 52    | serial     | 576A6491F3 |
| 8086:1c3d | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 48    | serial     | 8E0B4EE3A1 |
| 8086:3b67 | 8086:0036 | Intel      | 5 Series/3400 Series Chip... | 48    | serial     | 15FF525EFC |
| 8086:8c3d | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 48    | serial     | 4EC9EAAC2F |
| 8086:29b7 | 103c:2818 | Intel      | 82Q35 Express Serial KT C... | 46    | serial     | C0E9143E13 |
| 8086:1e3d | 1028:0534 | Intel      | 7 Series/C210 Series Chip... | 41    | serial     | 98420A7D92 |
| 8086:1c3d | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 39    | serial     | 33617DD1A8 |
| 8086:2e17 | 17aa:3048 | Intel      | 4 Series Chipset Serial K... | 39    | serial     | 7E76E404EC |
| 8086:3b67 | 103c:172a | Intel      | 5 Series/3400 Series Chip... | 39    | serial     | 66A3F34824 |
| 8086:a0fc | 1028:0991 | Intel      | Tiger Lake-LP Integrated ... | 39    | intel_i... | 089BB7C152 |
| 8086:34fc | 1028:096d | Intel      | Ice Lake-LP Integrated Se... | 38    | intel_i... | FBBAF8088B |
| 8086:9dfc | 103c:8549 | Intel      | Cannon Point-LP Integrate... | 38    | intel_i... | 7DBEB6844A |
| 8086:1e3d | 1028:052c | Intel      | 7 Series/C210 Series Chip... | 36    | serial     | DD8DC2D85A |
| 8086:9c3d | 1028:05cb | Intel      | 8 Series HECI KT             | 36    | serial     | EF82F4635D |
| 8086:2e17 | 103c:3646 | Intel      | 4 Series Chipset Serial K... | 35    | serial     | 833B887480 |
| 8086:1c3d | 17aa:3070 | Intel      | 6 Series/C200 Series Chip... | 34    | serial     | 6983745C31 |
| 8086:1e3d | 17aa:21fb | Intel      | 7 Series/C210 Series Chip... | 34    | serial     | AEF8C27B50 |
| 8086:1e3d | 17aa:3083 | Intel      | 7 Series/C210 Series Chip... | 33    | serial     | C0B8E99E35 |
| 8086:2e17 | 103c:3034 | Intel      | 4 Series Chipset Serial K... | 33    | serial     | D69CD77C4D |
| 8086:9c3d | 17aa:2214 | Intel      | 8 Series HECI KT             | 33    | serial     | F100B7CDB9 |
| 8086:1d3d | 103c:1589 | Intel      | C600/X79 series chipset K... | 32    | serial     | A4B0EBBEE2 |
| 8086:8c3d | 17aa:3097 | Intel      | 8 Series/C220 Series Chip... | 32    | serial     | 0C78C3EF80 |
| 8086:1c3d | 103c:162b | Intel      | 6 Series/C200 Series Chip... | 30    | serial     | C75019619F |
| 8086:9d3d | 1028:06dc | Intel      | Sunrise Point-LP Active M... | 30    | serial     | F972F7D9BA |
| 8086:06fc | 1028:098f | Intel      | 400 Series Chipset Family... | 29    | intel_i... | 3B1546B203 |
| 8086:1e3d | 10cf:16ed | Intel      | 7 Series/C210 Series Chip... | 29    | serial     | B2D4A08D24 |
| 8086:3b67 | 103c:7008 | Intel      | 5 Series/3400 Series Chip... | 29    | serial     | 86286FAD9C |
| 8086:02fc | 17aa:3804 | Intel      | Comet Lake Integrated Sen... | 28    | intel_i... | F72E765EF0 |
| 8086:1c3d | 103c:1494 | Intel      | 6 Series/C200 Series Chip... | 28    | serial     | 646E6E27E3 |
| 8086:1c3d | 17aa:21d2 | Intel      | 6 Series/C200 Series Chip... | 28    | serial     | 74057C8385 |
| 8086:3b67 | 103c:1521 | Intel      | 5 Series/3400 Series Chip... | 28    | serial     | FFC46C9472 |
| 8086:8c3d | 1028:05bd | Intel      | 8 Series/C220 Series Chip... | 28    | serial     | 535815022C |
| 8086:9c3d | 1028:05ca | Intel      | 8 Series HECI KT             | 28    | serial     | 9E790BA3F0 |
| 8086:9d3d | 1028:081c | Intel      | Sunrise Point-LP Active M... | 28    | serial     | B3010001A3 |
| 8086:1e3d | 103c:3396 | Intel      | 7 Series/C210 Series Chip... | 27    | serial     | 25FFFCB5C5 |
| 8086:2e17 | 103c:3035 | Intel      | 4 Series Chipset Serial K... | 27    | serial     | EA009F77D1 |
| 8086:9de3 | 103c:8549 | Intel      | Cannon Point-LP Keyboard ... | 27    | serial     | A9CD0A6239 |
| 8086:1e3d | 103c:18df | Intel      | 7 Series/C210 Series Chip... | 26    | serial     | 3E6A2F7B59 |
| 8086:3b67 | 103c:304a | Intel      | 5 Series/3400 Series Chip... | 26    | serial     | A6862C2A01 |
| 8086:8c3d | 1028:05be | Intel      | 8 Series/C220 Series Chip... | 26    | serial     | 6399CECB6F |
| 8086:8c3d | 17aa:30a3 | Intel      | 8 Series/C220 Series Chip... | 26    | serial     | F5A0BFB5FD |
| 8086:9d3d | 17aa:5053 | Intel      | Sunrise Point-LP Active M... | 26    | serial     | 6B9264BFE9 |
| 8086:a37c | 1028:0949 | Intel      | VROC Virtual Controller      | 26    | intel_i... | 1E15CE5E51 |
| 10ec:816a | 17aa:5082 | Realtek... | RTL8111xP UART #1            | 25    | serial     | 12FFAAEFB1 |
| 10ec:816a | 17aa:5125 | Realtek... | RTL8111xP UART #1            | 25    | serial     | 452DD792F1 |
| 10ec:816b | 17aa:5082 | Realtek... | RTL8111xP UART #2            | 25    | serial     | 12FFAAEFB1 |
| 10ec:816b | 17aa:5125 | Realtek... | RTL8111xP UART #2            | 25    | serial     | 452DD792F1 |
| 8086:02fc | 1028:0959 | Intel      | Comet Lake Integrated Sen... | 25    | intel_i... | 9D8401675E |
| 8086:1c3d | 103c:1618 | Intel      | 6 Series/C200 Series Chip... | 25    | serial     | EA1BD5E314 |
| 8086:2e17 | 1028:0276 | Intel      | 4 Series Chipset Serial K... | 25    | serial     | 8B417F82C5 |
| 8086:3b67 | 10cf:152f | Intel      | 5 Series/3400 Series Chip... | 25    | serial     | F220F9AC45 |
| 8086:9d3d | 17aa:2233 | Intel      | Sunrise Point-LP Active M... | 25    | serial     | 24B49E957C |
| 8086:9d3d | 17aa:225c | Intel      | Sunrise Point-LP Active M... | 25    | serial     | D49E5B0303 |
| 10ec:816a | 17aa:5126 | Realtek... | RTL8111xP UART #1            | 24    | serial     | 7065F7BB74 |
| 10ec:816b | 17aa:5126 | Realtek... | RTL8111xP UART #2            | 24    | serial     | 7065F7BB74 |
| 8086:9d3d | 17aa:2245 | Intel      | Sunrise Point-LP Active M... | 24    | serial     | 4EB1086713 |
| 8086:9de3 | 1028:08e1 | Intel      | Cannon Point-LP Keyboard ... | 24    | serial     | 011A257801 |
| 9710:9865 | a000:1000 | MosChip... | PCI 9865 Multi-I/O Contro... | 24    | parport_pc | 1155908299 |
| 8086:1e3d | 103c:17a7 | Intel      | 7 Series/C210 Series Chip... | 23    | serial     | A66A0DF735 |
| 8086:9de3 | 17aa:2279 | Intel      | Cannon Point-LP Keyboard ... | 23    | serial     | 3F74A71C6E |
| 8086:9dfc | 103c:8514 | Intel      | Cannon Point-LP Integrate... | 23    | intel_i... | 2352CAA9CF |
| 8086:02fc | 1028:0957 | Intel      | Comet Lake Integrated Sen... | 22    | intel_i... | 6901F8A463 |
| 8086:1e3d | 17aa:3084 | Intel      | 7 Series/C210 Series Chip... | 22    | serial     | AFB7518616 |
| 8086:9de3 | 17aa:2292 | Intel      | Cannon Point-LP Keyboard ... | 22    | serial     | B6CAC26930 |
| 8086:a13d | 1734:121d | Intel      | 100 Series/C230 Series Ch... | 22    | serial     | 4E988AF2DF |
| 10ec:816a | 17aa:507e | Realtek... | RTL8111xP UART #1            | 21    | serial     | 31850CE796 |
| 10ec:816b | 17aa:507e | Realtek... | RTL8111xP UART #2            | 21    | serial     | 31850CE796 |
| 8086:2a47 | 1028:0233 | Intel      | Mobile 4 Series Chipset A... | 21    | serial     | 2EA2BB4954 |
| 8086:34fc | 17aa:380e | Intel      | Ice Lake-LP Integrated Se... | 21    | intel_i... | 7C965E245C |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 418   | process... | 1866D29174 |
| 8086:a379 | 1458:8888 | Intel      | Cannon Lake PCH Thermal C... | 257   | intel_p... | E8B8B03EBD |
| 8086:3b32 | 17aa:2190 | Intel      | 5 Series/3400 Series Chip... | 252   | intel_ips  | 5DC4A1E557 |
| 8086:5a8c |           | Intel      | Atom/Celeron/Pentium Dyna... | 251   | process... | 71A92492E3 |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 245   | intel_l... | 71A92492E3 |
| 8086:9d27 | 1043:1d2d | Intel      | Sunrise Point-LP Serial I... | 243   | intel_lpss | AF70469300 |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 242   | intel_l... | 71A92492E3 |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 242   | intel_l... | 71A92492E3 |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 242   | intel_l... | 71A92492E3 |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 240   | intel_l... | 71A92492E3 |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 239   | intel_l... | 71A92492E3 |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 238   | intel_l... | 71A92492E3 |
| 8086:22dc | 7270:8086 | Intel      | Atom/Celeron/Pentium Proc... | 236   | process... | 5E75AF2BA4 |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 236   | intel_l... | 71A92492E3 |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 235   | intel_l... | 71A92492E3 |
| 8086:9d29 | 1043:1d2d | Intel      | Sunrise Point-LP Serial I... | 231   | intel_lpss | AF70469300 |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 230   | intel_l... | 71A92492E3 |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 230   | intel_l... | 71A92492E3 |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 229   | intel_l... | 71A92492E3 |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 226   | intel_l... | 71A92492E3 |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 226   | intel_l... | 71A92492E3 |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 224   | intel_l... | 71A92492E3 |
| 8086:9d31 | 8086:7270 | Intel      | Sunrise Point-LP Thermal ... | 212   | intel_p... | 1AB69568A5 |
| 8086:9d60 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 183   | intel_l... | 0E1D0B8D70 |
| 8086:31b4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 176   | intel_l... | 021617B9A0 |
| 8086:31b6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 173   | intel_l... | 021617B9A0 |
| 8086:31b8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 173   | intel_l... | 021617B9A0 |
| 8086:a131 | 1849:a131 | Intel      | 100 Series/C230 Series Ch... | 173   | intel_p... | 3A2A9BD626 |
| 8086:31be | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 171   | intel_l... | 021617B9A0 |
| 8086:31ee | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 171   | intel_l... | 021617B9A0 |
| 8086:318c | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 170   | process... | 021617B9A0 |
| 8086:31ba | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 170   | intel_l... | 021617B9A0 |
| 8086:31bc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 166   | intel_l... | 021617B9A0 |
| 8086:31c0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 165   | intel_l... | 021617B9A0 |
| 8086:31c6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 162   | intel_l... | 021617B9A0 |
| 8086:9d62 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 162   | intel_l... | 0E1D0B8D70 |
| 8086:31c4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 161   | intel_l... | 021617B9A0 |
| 8086:31c2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 160   | intel_l... | 021617B9A0 |
| 8086:9d27 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 157   | intel_l... | 8030B99150 |
| 8086:31ac | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 156   | intel_l... | 021617B9A0 |
| 8086:31ae | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 155   | intel_l... | 021617B9A0 |
| 8086:31b0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 155   | intel_l... | 021617B9A0 |
| 8086:31b2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 155   | intel_l... | 021617B9A0 |
| 8086:9d61 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 153   | intel_l... | 0E1D0B8D70 |
| 8086:a2b1 | 1849:a2b1 | Intel      | 200 Series PCH Thermal Su... | 146   |            | A8F84AEA94 |
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
| 8086:1903 | 8086:1903 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 120   | process... | 35941050E8 |
| 8086:a379 | 1025:1331 | Intel      | Cannon Lake PCH Thermal C... | 119   | intel_p... | 38688703F4 |
| 8086:9df9 | 8086:2074 | Intel      | Cannon Point-LP Thermal C... | 116   | intel_p... | 7CA350189C |
| 8086:1903 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 115   | process... | 1AB69568A5 |
| 8086:3b32 | 17aa:38c0 | Intel      | 5 Series/3400 Series Chip... | 115   | intel_ips  | 62053AE42B |
| 8086:1903 | 1028:0905 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 113   | process... | 9CDE952049 |
| 8086:1903 | 17aa:2292 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 113   | process... | 32CA60DCEA |
| 8086:a379 | 1028:0905 | Intel      | Cannon Lake PCH Thermal C... | 113   | intel_p... | 9CDE952049 |
| 8086:9d63 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 111   | intel_l... | 0E1D0B8D70 |
| 8086:02f9 | 17aa:5079 | Intel      | Comet Lake Thermal Subsytem  | 107   | intel_p... | 0BC4073D23 |
| 8086:1903 | 17aa:5079 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 107   | process... | 0BC4073D23 |
| 8086:9d60 | 1025:1193 | Intel      | Sunrise Point-LP Serial I... | 105   | intel_lpss | E922639FF6 |
| 8086:9d61 | 1025:1193 | Intel      | Sunrise Point-LP Serial I... | 105   | intel_lpss | E922639FF6 |
| 8086:a131 | 1458:8888 | Intel      | 100 Series/C230 Series Ch... | 102   | intel_p... | 4DA44461B8 |
| 8086:a379 | 1849:a379 | Intel      | Cannon Lake PCH Thermal C... | 102   | intel_p... | 839B20476A |
| 8086:3b32 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 101   | intel_ips  | C172C655DE |
| 8086:9d31 | 8086:9d31 | Intel      | Sunrise Point-LP Thermal ... | 101   | intel_p... | 02F641EA60 |
| 8086:1903 | 1028:087c | Intel      | Xeon E3-1200 v5/E3-1500 v... | 98    | process... | 31A6F21CCD |
| 8086:a379 | 1028:087c | Intel      | Cannon Lake PCH Thermal C... | 98    | intel_p... | 31A6F21CCD |
| 8086:1903 | 1028:0810 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 97    | process... | 2FD333BC52 |
| 8086:9d31 | 1028:0810 | Intel      | Sunrise Point-LP Thermal ... | 97    | intel_p... | 2FD333BC52 |
| 8086:9d60 | 1028:0810 | Intel      | Sunrise Point-LP Serial I... | 97    | intel_l... | 2FD333BC52 |
| 8086:1903 | 17aa:2279 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 96    | process... | 2444839350 |
| 8086:9df9 | 17aa:2279 | Intel      | Cannon Point-LP Thermal C... | 96    | intel_p... | 2444839350 |
| 8086:9df9 | 103c:8549 | Intel      | Cannon Point-LP Thermal C... | 95    | intel_p... | 9A264DBCB2 |
| 8086:2932 | 17aa:3a1f | Intel      | 82801I (ICH9 Family) Ther... | 94    |            | 1BBEC614AA |
| 8086:9d31 | 103c:8079 | Intel      | Sunrise Point-LP Thermal ... | 94    | intel_p... | 0FA8058EEB |
| 8086:9d60 | 103c:8079 | Intel      | Sunrise Point-LP Serial I... | 94    | intel_l... | 0FA8058EEB |
| 8086:1903 | 103c:8549 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 92    | process... | 9A264DBCB2 |
| 8086:9ca4 | 8086:7270 | Intel      | Wildcat Point-LP Thermal ... | 90    | intel_p... | C0ED6370C5 |
| 8086:1903 | 1043:12d1 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 89    | proc_th... | 570905286F |
| 8086:9d27 | 1043:12d1 | Intel      | Sunrise Point-LP Serial I... | 89    | intel_lpss | 570905286F |
| 8086:9d31 | 1043:12d1 | Intel      | Sunrise Point-LP Thermal ... | 89    | intel_p... | 570905286F |
| 8086:9d60 | 1043:12d1 | Intel      | Sunrise Point-LP Serial I... | 89    | intel_lpss | 570905286F |
| 8086:9d61 | 1043:12d1 | Intel      | Sunrise Point-LP Serial I... | 89    | intel_lpss | 570905286F |
| 8086:1903 | 17aa:225d | Intel      | Xeon E3-1200 v5/E3-1500 v... | 88    | process... | BBA3BC97B7 |
| 8086:9d31 | 17aa:225d | Intel      | Sunrise Point-LP Thermal ... | 88    | intel_p... | BBA3BC97B7 |
| 8086:9df9 | 17aa:2292 | Intel      | Cannon Point-LP Thermal C... | 88    | intel_p... | FBF4582983 |
| 1022:15e4 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Senso... | 86    | amd_sfh    | 64A9E43743 |
| 8086:9ca4 | 17aa:5034 | Intel      | Wildcat Point-LP Thermal ... | 85    | intel_p... | 6131E3C22A |
| 8086:1903 | 1028:07e6 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 83    | process... | C2E884F793 |
| 8086:9d31 | 1028:07e6 | Intel      | Sunrise Point-LP Thermal ... | 83    | intel_p... | C2E884F793 |
| 8086:9d60 | 1028:07e6 | Intel      | Sunrise Point-LP Serial I... | 83    | intel_l... | C2E884F793 |
| 8086:9d61 | 1028:07e6 | Intel      | Sunrise Point-LP Serial I... | 83    | intel_l... | C2E884F793 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:790b | 1458:5001 | AMD        | FCH SMBus Controller         | 1352  | i2c_piix4  | F544511E0A |
| 1002:4385 | 1002:4385 | AMD        | SBx00 SMBus Controller       | 1169  | i2c_pii... | 77FCB9CF4A |
| 8086:1c22 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1017  | i2c_i801   | EA164260EB |
| 8086:8c22 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 790   | i2c_i801   | 9A23DF55D8 |
| 1002:4385 | 1043:8389 | AMD        | SBx00 SMBus Controller       | 786   | i2c_pii... | 67B53F9BDB |
| 1002:4385 |           | AMD        | SBx00 SMBus Controller       | 746   | i2c_pii... | 2B9CBC3FAC |
| 1002:4385 | 1458:4385 | AMD        | SBx00 SMBus Controller       | 743   | i2c_pii... | 765CD8D9A0 |
| 8086:27da | 1458:5001 | Intel      | NM10/ICH7 Family SMBus Co... | 741   | i2c_i801   | 43A5D97DD3 |
| 1022:790b | 1043:8747 | AMD        | FCH SMBus Controller         | 728   | i2c_piix4  | 115EC5ECA4 |
| 8086:1e22 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 708   | i2c_i801   | BA117FEF7E |
| 8086:27da | 1043:8179 | Intel      | NM10/ICH7 Family SMBus Co... | 695   | i2c_i801   | 5889B752F5 |
| 1022:790b | 1043:87c0 | AMD        | FCH SMBus Controller         | 666   | i2c_piix4  | 97C17F738A |
| 8086:a123 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 650   | i2c_i801   | 11EBF0D551 |
| 8086:1c22 | 1458:5001 | Intel      | 6 Series/C200 Series Chip... | 632   | i2c_i801   | EE570B7B0C |
| 8086:3a30 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) SM... | 604   | i2c_i801   | 2E1659CD91 |
| 1022:790b | 1849:790b | AMD        | FCH SMBus Controller         | 602   | i2c_piix4  | E1B676D2A4 |
| 8086:1e22 | 1458:5001 | Intel      | 7 Series/C216 Chipset Fam... | 532   | i2c_i801   | 89F6EB0671 |
| 8086:8c22 | 1458:5001 | Intel      | 8 Series/C220 Series Chip... | 522   | i2c_i801   | E187B3F207 |
| 8086:1e22 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 515   | i2c_i801   | 5872E567EC |
| 1002:4385 | 1849:4385 | AMD        | SBx00 SMBus Controller       | 487   | i2c_pii... | 0A228B18C1 |
| 8086:27da | 1849:27da | Intel      | NM10/ICH7 Family SMBus Co... | 445   | i2c_i801   | 87C40FCD51 |
| 10de:03eb | 1849:03eb | Nvidia     | MCP61 SMBus                  | 397   | i2c_nfo... | 615502E93E |
| 8086:a2a3 | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 391   | i2c_i801   | 2696477C0C |
| 1022:780b | 1022:780b | AMD        | FCH SMBus Controller         | 380   | i2c_piix4  | E03FD39AD4 |
| 1022:790b | 1849:ffff | AMD        | FCH SMBus Controller         | 370   | i2c_piix4  | 6056EAC50C |
| 8086:a2a3 | 1458:5001 | Intel      | 200 Series/Z370 Chipset F... | 364   | i2c_i801   | F91A20DD51 |
| 8086:a123 | 1458:5001 | Intel      | 100 Series/C230 Series Ch... | 358   | i2c_i801   | 213A5CCCC3 |
| 8086:2930 | 1043:8277 | Intel      | 82801I (ICH9 Family) SMBu... | 356   | i2c_i801   | 4F6DEFB975 |
| 1022:790b | 1022:790b | AMD        | FCH SMBus Controller         | 353   | i2c_piix4  | FC5CE69792 |
| 1022:780b | 1849:780b | AMD        | FCH SMBus Controller         | 332   | i2c_pii... | 3D65247771 |
| 8086:a323 | 1043:8694 | Intel      | Cannon Lake PCH SMBus Con... | 301   | i2c_i801   | 36EBF65D44 |
| 8086:1c22 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 299   | i2c_i801   | 21DB34139A |
| 8086:8ca2 | 1043:8534 | Intel      | 9 Series Chipset Family S... | 290   | i2c_i801   | 0D40DAA834 |
| 8086:3b30 | 17aa:2167 | Intel      | 5 Series/3400 Series Chip... | 284   | i2c_i801   | 5DC4A1E557 |
| 8086:9c22 | 17aa:3978 | Intel      | 8 Series SMBus Controller    | 280   | i2c_i801   | B1B8196F26 |
| 8086:2930 | 17aa:20f9 | Intel      | 82801I (ICH9 Family) SMBu... | 279   | i2c_i801   | DB936567F0 |
| 8086:3a30 | 1458:5001 | Intel      | 82801JI (ICH10 Family) SM... | 273   | i2c_i801   | 0B27475327 |
| 8086:3b30 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 265   | i2c_i801   | AC572EF424 |
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 263   | i2c_i801   | 71A92492E3 |
| 8086:1c22 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 261   | i2c_i801   | 2F0AE62282 |
| 8086:a323 | 1458:5001 | Intel      | Cannon Lake PCH SMBus Con... | 257   | i2c_i801   | E8B8B03EBD |
| 8086:8c22 | 1849:8c22 | Intel      | 8 Series/C220 Series Chip... | 248   | i2c_i801   | F36828F316 |
| 8086:1c22 | 1849:1c22 | Intel      | 6 Series/C200 Series Chip... | 247   | i2c_i801   | EFEC95A916 |
| 1022:790b | 1043:876b | AMD        | FCH SMBus Controller         | 243   | i2c_piix4  | AB4B1B7A15 |
| 8086:1e22 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 224   | i2c_i801   | 066B825941 |
| 8086:8ca2 | 1458:5001 | Intel      | 9 Series Chipset Family S... | 224   | i2c_i801   | DF13F72A9A |
| 8086:31d4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 208   | i2c_i801   | 021617B9A0 |
| 8086:8c22 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 205   | i2c_i801   | 76D72EB45F |
| 8086:2930 | 1458:5001 | Intel      | 82801I (ICH9 Family) SMBu... | 203   | i2c_i801   | 5B2102BA4E |
| 10de:0aa2 | 10de:cb79 | Nvidia     | MCP79 SMBus                  | 202   | i2c_nfo... | F982A2F6CC |
| 8086:3b30 | 1458:5001 | Intel      | 5 Series/3400 Series Chip... | 201   | i2c_i801   | 053480926C |
| 10de:03eb | 1458:0c11 | Nvidia     | MCP61 SMBus                  | 195   | i2c_nfo... | FB1E012F68 |
| 8086:27da | 1043:83ad | Intel      | NM10/ICH7 Family SMBus Co... | 187   | i2c_i801   | 2E4383BD79 |
| 8086:1e22 | 1849:1e22 | Intel      | 7 Series/C216 Chipset Fam... | 174   | i2c_i801   | E7EBAD7358 |
| 8086:a123 | 1849:a123 | Intel      | 100 Series/C230 Series Ch... | 173   | i2c_i801   | 3A2A9BD626 |
| 8086:1e22 | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 171   | i2c_i801   | C9503690D6 |
| 8086:1e22 | 1028:0577 | Intel      | 7 Series/C216 Chipset Fam... | 165   | i2c_i801   | 4DAF9FDC0D |
| 8086:9d23 | 8086:7270 | Intel      | Sunrise Point-LP SMBus       | 162   | i2c_i801   | 1AB69568A5 |
| 8086:8c22 | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 161   | i2c_i801   | 75E2E357A3 |
| 8086:1e22 | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 153   | i2c_i801   | 52667487D2 |
| 8086:1c22 | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 150   | i2c_i801   | 438D785F0E |
| 8086:1c22 | 8086:1c22 | Intel      | 6 Series/C200 Series Chip... | 150   | i2c_i801   | 73BFADA83A |
| 8086:1c22 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 149   | i2c_i801   | 74547808D3 |
| 1022:790b | 1462:7c02 | AMD        | FCH SMBus Controller         | 147   | i2c_piix4  | 2229C9E9F6 |
| 8086:2930 | 17aa:3a1d | Intel      | 82801I (ICH9 Family) SMBu... | 146   | i2c_i801   | 1BBEC614AA |
| 8086:a2a3 | 1849:a2a3 | Intel      | 200 Series/Z370 Chipset F... | 146   | i2c_i801   | A8F84AEA94 |
| 1022:790b | 1462:7c37 | AMD        | FCH SMBus Controller         | 145   | i2c_piix4  | 0619809B36 |
| 8086:1c22 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 145   | i2c_i801   | B420F25ED4 |
| 10de:03eb | 1043:83a4 | Nvidia     | MCP61 SMBus                  | 144   | i2c_nfo... | 1C28AB7987 |
| 8086:3b30 | 17aa:38bf | Intel      | 5 Series/3400 Series Chip... | 142   | i2c_i801   | 62053AE42B |
| 8086:1c22 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 138   | i2c_i801   | 33617DD1A8 |
| 8086:1d22 | 1043:84ef | Intel      | C600/X79 series chipset S... | 137   | i2c_i801   | F0DC31F93D |
| 8086:1e22 | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 136   | i2c_i801   | 50D562CAB5 |
| 1002:4385 | 1462:7693 | AMD        | SBx00 SMBus Controller       | 135   | i2c_pii... | D0FD1CE0E8 |
| 8086:31d4 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 135   | i2c_i801   | 170B220F5B |
| 8086:3a60 | 1028:0420 | Intel      | 82801JD/DO (ICH10 Family)... | 134   | i2c_i801   | 5824A76242 |
| 8086:3b30 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 134   | i2c_i801   | 576A6491F3 |
| 8086:a2a3 | 1043:872f | Intel      | 200 Series/Z370 Chipset F... | 131   | i2c_i801   | C1BF9C169D |
| 1022:780b | 1462:7721 | AMD        | FCH SMBus Controller         | 129   | i2c_piix4  | 01C5E2E798 |
| 8086:283e | 17aa:20a9 | Intel      | 82801H (ICH8 Family) SMBu... | 129   | i2c_i801   | E1B3B6E090 |
| 1022:780b | 17aa:3801 | AMD        | FCH SMBus Controller         | 128   | i2c_piix4  | 779BFC3B47 |
| 8086:1e22 | 1043:124d | Intel      | 7 Series/C216 Chipset Fam... | 127   | i2c_i801   | 08930695BC |
| 8086:3b30 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 126   | i2c_i801   | C172C655DE |
| 8086:3b30 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 123   | i2c_i801   | 03E0270FDD |
| 8086:9d23 | 17aa:386f | Intel      | Sunrise Point-LP SMBus       | 123   | i2c_i801   | 19226582D9 |
| 8086:283e | 1025:011f | Intel      | 82801H (ICH8 Family) SMBu... | 122   | i2c_i801   | 6A05B72968 |
| 8086:3b30 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 121   | i2c_i801   | 11F1CDC49A |
| 8086:9ca2 | 8086:7270 | Intel      | Wildcat Point-LP SMBus Co... | 121   | i2c_i801   | C0ED6370C5 |
| 8086:27da | 8086:27da | Intel      | NM10/ICH7 Family SMBus Co... | 120   | i2c_i801   | A22FBCDE28 |
| 1022:780b | 1043:85ca | AMD        | FCH SMBus Controller         | 119   | i2c_piix4  | BDB612797A |
| 8086:a323 | 1025:1331 | Intel      | Cannon Lake PCH SMBus Con... | 119   | i2c_i801   | 38688703F4 |
| 8086:1c22 | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 118   | i2c_i801   | FF37A9C00D |
| 8086:1c22 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 118   | i2c_i801   | 660A6B9E20 |
| 8086:1e22 | 1028:0534 | Intel      | 7 Series/C216 Chipset Fam... | 118   | i2c_i801   | 98420A7D92 |
| 10de:03eb | 1043:8234 | Nvidia     | MCP61 SMBus                  | 116   | i2c_nfo... | A5CA2582B6 |
| 8086:1e22 | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 116   | i2c_i801   | B732F94275 |
| 8086:9da3 | 8086:2074 | Intel      | Cannon Point-LP SMBus Con... | 116   | i2c_i801   | 7CA350189C |
| 8086:1e22 | 17aa:21f6 | Intel      | 7 Series/C216 Chipset Fam... | 115   | i2c_i801   | 9ECBB7A946 |
| 8086:a323 | 1028:0905 | Intel      | Cannon Lake PCH SMBus Con... | 113   | i2c_i801   | 9CDE952049 |
| 8086:283e | 1043:81ec | Intel      | 82801H (ICH8 Family) SMBu... | 110   | i2c_i801   | 926229BE87 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:15de | 1002:15de | AMD        | Raven/Raven2/Fenghuang HD... | 876   | snd_hda... | F504E72617 |
| 8086:0c0c | 8086:2010 | Intel      | Xeon E3-1200 v3/4th Gen C... | 875   | snd_hda... | E187B3F207 |
| 8086:27d8 | 1458:a002 | Intel      | NM10/ICH7 Family High Def... | 635   | snd_hda... | BD17F8FBD9 |
| 1002:ab38 | 1002:ab38 | AMD        | Navi 10 HDMI Audio           | 600   | snd_hda... | B8D0E81636 |
| 8086:8c20 | 1043:8576 | Intel      | 8 Series/C220 Series Chip... | 551   | snd_hda... | 87F5B4AFC5 |
| 1002:4383 | 1458:a002 | AMD        | SBx00 Azalia (Intel HDA)     | 547   | snd_hda... | 74D6E4FFA4 |
| 8086:1c20 | 1458:a002 | Intel      | 6 Series/C200 Series Chip... | 515   | snd_hda... | E88DE55691 |
| 8086:1e20 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 515   | snd_hda... | 5872E567EC |
| 10de:0bea |           | Nvidia     | GF108 High Definition Aud... | 492   | snd_hda... | 2E9B8200A9 |
| 8086:8c20 | 1458:a002 | Intel      | 8 Series/C220 Series Chip... | 460   | snd_hda... | E187B3F207 |
| 1002:aaf0 | 1da2:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 436   | snd_hda... | 2E1659CD91 |
| 1002:4383 | 1043:8445 | AMD        | SBx00 Azalia (Intel HDA)     | 392   | snd_hda... | 08ED9AF2B9 |
| 1002:aab0 | 174b:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 365   | snd_hda... | E417B5E11E |
| 10de:0e0f | 1462:8c93 | Nvidia     | GK208 HDMI/DP Audio Contr... | 354   | snd_hda... | F7E3CD3E35 |
| 1022:1457 | 1458:a182 | AMD        | Family 17h (Models 00h-0f... | 346   | snd_hda... | 35C74E640B |
| 8086:a170 | 1043:86c7 | Intel      | 100 Series/C230 Series Ch... | 345   | snd_hda... | 47AA9C9E14 |
| 13f6:0111 | 13f6:0111 | C-Media... | CMI8738/CMI8768 PCI Audio    | 342   | snd_cmipci | 01C5E2E798 |
| 1002:aaf0 | 1462:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 328   | snd_hda... | 84FDA964C3 |
| 8086:1e20 | 1458:a002 | Intel      | 7 Series/C216 Chipset Fam... | 324   | snd_hda... | F55F5434E6 |
| 8086:1c20 | 1043:8445 | Intel      | 6 Series/C200 Series Chip... | 319   | snd_hda... | EA164260EB |
| 8086:0c0c | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 311   | snd_hda... | 0D40DAA834 |
| 1002:4383 | 1043:836c | AMD        | SBx00 Azalia (Intel HDA)     | 310   | snd_hda... | 67B53F9BDB |
| 10de:03f0 | 1849:0397 | Nvidia     | MCP61 High Definition Audio  | 302   | snd_hda... | 0B81DF184D |
| 8086:293e | 17aa:20f2 | Intel      | 82801I (ICH9 Family) HD A... | 301   | snd_hda... | DB936567F0 |
| 8086:1c20 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 299   | snd_hda... | 21DB34139A |
| 1002:aab0 | 1043:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 298   | snd_hda... | AA3A28C4B3 |
| 8086:a2f0 | 1458:a182 | Intel      | 200 Series PCH HD Audio      | 294   | snd_hda... | F91A20DD51 |
| 1022:1457 | 1043:86c7 | AMD        | Family 17h (Models 00h-0f... | 293   | snd_hda... | 115EC5ECA4 |
| 1002:aaf0 | 1682:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 286   | snd_hda... | F544511E0A |
| 8086:1e20 | 1043:8445 | Intel      | 7 Series/C216 Chipset Fam... | 286   | snd_hda... | 330B8B499B |
| 8086:a170 | 1458:a182 | Intel      | 100 Series/C230 Series Ch... | 281   | snd_hda... | 213A5CCCC3 |
| 8086:0a0c | 17aa:3978 | Intel      | Haswell-ULT HD Audio Cont... | 280   | snd_hda... | B1B8196F26 |
| 8086:9c20 | 17aa:3978 | Intel      | 8 Series HD Audio Controller | 280   | snd_hda... | B1B8196F26 |
| 1002:4383 | 1458:a182 | AMD        | SBx00 Azalia (Intel HDA)     | 278   | snd_hda... | 84D927D279 |
| 8086:3b56 | 17aa:215e | Intel      | 5 Series/3400 Series Chip... | 268   | snd_hda... | 4FF6DAE64C |
| 1022:780d | 1458:a002 | AMD        | FCH Azalia Controller        | 253   | snd_hda... | E03FD39AD4 |
| 10de:0fb9 |           | Nvidia     | GP107GL High Definition A... | 246   | snd_hda... | 1060065F34 |
| 8086:1c20 | 1043:8415 | Intel      | 6 Series/C200 Series Chip... | 245   | snd_hda... | 86C4259FBC |
| 8086:1c20 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 243   | snd_hda... | 7EBB0672C0 |
| 1022:15e3 | 1458:a182 | AMD        | Family 17h (Models 10h-1f... | 234   | snd_hda... | F544511E0A |
| 8086:293e | 1043:829f | Intel      | 82801I (ICH9 Family) HD A... | 231   | snd_hda... | 50AE548F24 |
| 1002:aaf8 | 1002:aaf8 | AMD        | Vega 10 HDMI Audio [Radeo... | 228   | snd_hda... | 6787B45989 |
| 8086:27d8 | 1849:3662 | Intel      | NM10/ICH7 Family High Def... | 227   | snd_hda... | 87C40FCD51 |
| 1022:780d | 1043:8576 | AMD        | FCH Azalia Controller        | 215   | snd_hda... | D62C1CC4AA |
| 1002:aaf0 | 1043:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 213   | snd_hda... | 01196F313E |
| 1002:aa68 | 1043:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 212   | snd_hda... | 11F1CDC49A |
| 8086:1e20 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 209   | snd_hda... | 066B825941 |
| 10de:0be3 |           | Nvidia     | High Definition Audio Con... | 208   | snd_hda... | 5E2CE09E63 |
| 1022:15e3 | 1043:86c7 | AMD        | Family 17h (Models 10h-1f... | 207   | snd_hda... | AB4B1B7A15 |
| 1002:aa98 | 174b:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 206   | snd_hda... | 5101982911 |
| 1002:4383 | 1458:a102 | AMD        | SBx00 Azalia (Intel HDA)     | 203   | snd_hda... | 403EF2DA16 |
| 10de:0ac0 | 10de:cb79 | Nvidia     | MCP79 High Definition Audio  | 201   | snd_hda... | F982A2F6CC |
| 1102:0012 | 1102:0010 | Creativ... | Sound Core3D [Sound Blast... | 200   | snd_hda... | D88D9DB618 |
| 8086:a2f0 | 1043:86c7 | Intel      | 200 Series PCH HD Audio      | 200   | snd_hda... | DD9596A6B0 |
| 1002:1637 | 1002:1637 | AMD        | Renoir Radeon High Defini... | 192   | snd_hda... | DB4A212405 |
| 10de:03f0 | 1458:a002 | Nvidia     | MCP61 High Definition Audio  | 188   | snd_hda... | FB1E012F68 |
| 8086:3a3e | 1043:82fe | Intel      | 82801JI (ICH10 Family) HD... | 187   | snd_hda... | 102C78CA6B |
| 1002:15de | 1043:876b | AMD        | Raven/Raven2/Fenghuang HD... | 177   | snd_hda... | AB4B1B7A15 |
| 1022:1487 | 1043:8797 | AMD        | Starship/Matisse HD Audio... | 177   | snd_hda... | 379D2F0B1C |
| 1002:aab0 | 1458:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 172   | snd_hda... | 1770BBE4E2 |
| 8086:1e20 | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 171   | snd_hda... | C9503690D6 |
| 8086:3a3e | 1458:a002 | Intel      | 82801JI (ICH10 Family) HD... | 169   | snd_hda... | 25ABEEE3EF |
| 1002:aa38 | 174b:aa38 | AMD        | RV710/730 HDMI Audio [Rad... | 168   | snd_hda... | 4999ECD668 |
| 8086:27d8 | 1043:8290 | Intel      | NM10/ICH7 Family High Def... | 168   | snd_hda... | 5E2CE09E63 |
| 1002:4383 | 1043:8444 | AMD        | SBx00 Azalia (Intel HDA)     | 167   | snd_hda... | D33CCE58A1 |
| 8086:9d71 | 8086:7270 | Intel      | Sunrise Point-LP HD Audio    | 166   | snd_hda... | 8030B99150 |
| 1002:aab0 | 1462:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 164   | snd_hda... | 7B8C559DE7 |
| 1002:aaf0 | 1458:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 164   | snd_hda... | 1AD175FDDC |
| 8086:1e20 | 1028:0577 | Intel      | 7 Series/C216 Chipset Fam... | 164   | snd_hda... | 4DAF9FDC0D |
| 1022:1487 | 1458:a0c3 | AMD        | Starship/Matisse HD Audio... | 162   | snd_hda... | 2A6868991A |
| 8086:8ca0 | 1458:a182 | Intel      | 9 Series Chipset Family H... | 161   | snd_hda... | E0277E3530 |
| 8086:293e | 1458:a002 | Intel      | 82801I (ICH9 Family) HD A... | 160   | snd_hda... | 18D8466531 |
| 8086:0a0c | 8086:2010 | Intel      | Haswell-ULT HD Audio Cont... | 158   | snd_hda... | AA03D405BC |
| 1002:aa68 | 174b:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 157   | snd_hda... | 2C05A7DB2C |
| 8086:3b56 | 1458:a002 | Intel      | 5 Series/3400 Series Chip... | 157   | snd_hda... | 053480926C |
| 8086:a348 | 1458:a182 | Intel      | Cannon Lake PCH cAVS         | 155   | snd_hda... | E8B8B03EBD |
| 1002:4383 | 1849:7892 | AMD        | SBx00 Azalia (Intel HDA)     | 153   | snd_hda... | D811152E10 |
| 8086:1e20 | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 153   | snd_hda... | 52667487D2 |
| 8086:8c20 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 153   | snd_hda... | 7FB630F632 |
| 8086:293e | 17aa:3a0d | Intel      | 82801I (ICH9 Family) HD A... | 151   | snd_hda... | 1BBEC614AA |
| 8086:0c0c | 17aa:3978 | Intel      | Xeon E3-1200 v3/4th Gen C... | 150   | snd_hda... | 7FB630F632 |
| 8086:1c20 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 149   | snd_hda... | 74547808D3 |
| 8086:1e20 | 1458:a014 | Intel      | 7 Series/C216 Chipset Fam... | 147   | snd_hda... | 89F6EB0671 |
| 8086:1c20 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 145   | snd_hda... | B420F25ED4 |
| 1002:9840 | 1002:9840 | AMD        | Kabini HDMI/DP Audio         | 144   | snd_hda... | 4654691B7A |
| 1002:aa98 | 1043:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 144   | snd_hda... | A9FC556262 |
| 1002:aab0 | 1787:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 144   | snd_hda... | 7A75936B55 |
| 1022:1457 | 1043:8723 | AMD        | Family 17h (Models 00h-0f... | 142   | snd_hda... | 2C356ECED5 |
| 1022:1457 | 1849:6893 | AMD        | Family 17h (Models 00h-0f... | 142   | snd_hda... | E1B676D2A4 |
| 1022:780d | 1849:7662 | AMD        | FCH Azalia Controller        | 142   | snd_hda... | 9D17B2FF73 |
| 8086:8c20 | 1462:d817 | Intel      | 8 Series/C220 Series Chip... | 141   | snd_hda... | EA9B132E77 |
| 8086:3b56 | 17aa:38af | Intel      | 5 Series/3400 Series Chip... | 140   | snd_hda... | 62053AE42B |
| 1002:aae0 | 1da2:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 139   | snd_hda... | 115EC5ECA4 |
| 8086:1c20 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 137   | snd_hda... | 33617DD1A8 |
| 8086:27d8 | 1849:0397 | Intel      | NM10/ICH7 Family High Def... | 137   | snd_hda... | B9B144530E |
| 1002:aa90 | 174b:aa90 | AMD        | Turks HDMI Audio [Radeon ... | 136   | snd_hda... | 926229BE87 |
| 10de:0bee |           | Nvidia     | GF116 High Definition Aud... | 136   | snd_hda... | 08ED9AF2B9 |
| 10de:10f1 |           | Nvidia     | GP106 High Definition Aud... | 136   | snd_hda... | AC76D208AB |
| 8086:1e20 | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 136   | snd_hda... | 50D562CAB5 |
| 8086:3198 | 1043:1de0 | Intel      | Celeron/Pentium Silver Pr... | 136   | snd_hda... | 170B220F5B |

### Storage (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1217:8231 | 1028:0493 | O2 Micro   | O2Micro Integrated MS/MSP... | 133   |            | 33617DD1A8 |
| 104c:803b | 1025:011f | Texas I... | PCIxx12 Flash Media Contr... | 122   | tifm_7xx1  | 6A05B72968 |
| 1217:7130 | 1179:ff50 | O2 Micro   | Integrated MS/xD Controller  | 55    |            | FEB13460E8 |
| 1217:8331 | 1028:0494 | O2 Micro   | O2 Flash Memory Card         | 51    |            | E58B9D7EA5 |
| 104c:803b | 1179:ff00 | Texas I... | PCIxx12 Flash Media Contr... | 48    | tifm_7xx1  | 8E44C9EDAF |
| 104c:803b | 1179:ff02 | Texas I... | PCIxx12 Flash Media Contr... | 38    | tifm_7xx1  | 3F0EBD44AD |
| 1283:8211 | 1043:8138 | Integra... | ITE 8211F Single Channel ... | 38    | pata_it... | 72B40A39D4 |
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
| 104c:8033 | 103c:3085 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 5     | tifm_7xx1  | 32F7B77B77 |
| 104c:8033 | 103c:30a4 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 5     | tifm_7xx1  | C2A5CB93AA |
| 104c:803b | 1025:006c | Texas I... | PCIxx12 Flash Media Contr... | 5     | tifm_7xx1  | 2D3698DEC2 |
| 104c:803b | 1025:0102 | Texas I... | PCIxx12 Flash Media Contr... | 5     | tifm_7xx1  | A59E16433A |
| 104c:803b | 103c:309f | Texas I... | PCIxx12 Flash Media Contr... | 5     | tifm_7xx1  | 3FFD093A67 |
| 1077:2532 | 1077:015d | QLogic     | ISP2532-based 8Gb Fibre C... | 5     | qla2xxx    | 7A2B809CB8 |
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
| 105a:4d68 | 105a:4d68 | Promise... | PDC20268 [Ultra100 TX2]      | 4     | pata_pd... | 6967AF910D |
| 105a:4d69 | 105a:4d68 | Promise... | 20269                        | 4     | pata_pd... | 21833C414E |
| 1106:401a | 1028:02f5 | VIA Tec... | VIA Card Reader Host Cont... | 4     |            | 8EF532D4EC |
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
| 104c:8033 | 103c:3091 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 3     | tifm_7xx1  | F01F51C47C |
| 104c:8033 | 103c:309d | Texas I... | PCIxx21/PCIxx11 Flash Med... | 3     | tifm_7xx1  | 837230178B |
| 104c:8033 | 161f:203d | Texas I... | PCIxx21/PCIxx11 Flash Med... | 3     | tifm_7xx1  | A942E40F27 |
| 104c:803b | 104d:900f | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | 055903703C |
| 104c:803b | 107b:0366 | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | BCF6858E7D |
| 104c:803b | 152d:0763 | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | BA6F03E565 |
| 104c:803b | 1854:005f | Texas I... | PCIxx12 Flash Media Contr... | 3     | tifm_7xx1  | 7611C8EBB8 |
| 105a:3d17 | 105a:3d17 | Promise... | PDC40718 (SATA 300 TX4)      | 3     | sata_pr... | 50A778F706 |
| 105a:3d73 | 105a:3d73 | Promise... | PDC40775 (SATA 300 TX2plus)  | 3     | sata_pr... | 8FFB1720D8 |
| 1077:2432 | 103c:7040 | QLogic     | ISP2432-based 4Gb Fibre C... | 3     | qla2xxx    | 3A362598FB |
| 1077:2432 | 1077:0138 | QLogic     | ISP2432-based 4Gb Fibre C... | 3     | qla2xxx    | FB66D16E30 |
| 10df:fe00 | 10df:fe00 | Emulex     | Zephyr-X LightPulse Fibre... | 3     | lpfc       | 6806624961 |
| 11f8:8032 | 117c:003b | PMC-Sierra | PM8032 Tachyon QE8           | 3     | celerit... | FB8C0A4C3A |
| 1217:7130 | 1028:0275 | O2 Micro   | Integrated MS/xD Controller  | 3     |            | A359187C45 |
| 1217:7130 | 17aa:3a21 | O2 Micro   | Integrated MS/xD Controller  | 3     |            | BF3EE678DA |
| 1217:8130 | 1028:02bb | O2 Micro   | Integrated MS/MSPRO/xD Co... | 3     |            | 95DC1639D3 |
| 1217:8130 | 10cf:1568 | O2 Micro   | Integrated MS/MSPRO/xD Co... | 3     |            | 9B2FC1E55F |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:43c8 | 1b21:1062 | AMD        | 400 Series Chipset SATA C... | 1885  | ahci       | 97C17F738A |
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 1447  | ahci       | 0619809B36 |
| 1022:7901 | 1458:b002 | AMD        | FCH SATA Controller [AHCI... | 1002  | ahci       | F544511E0A |
| 8086:8c02 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 763   | ahci       | 9A23DF55D8 |
| 1022:7901 | 1043:8747 | AMD        | FCH SATA Controller [AHCI... | 722   | ahci       | 115EC5ECA4 |
| 1002:4390 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 703   | ahci       | 74D6E4FFA4 |
| 1002:4391 | 1043:84dd | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 637   | ahci       | 9F527DED3C |
| 1002:4390 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 636   | ahci       | 67B53F9BDB |
| 8086:a102 | 1043:8694 | Intel      | Q170/Q150/B150/H170/H110/... | 634   | ahci       | 11EBF0D551 |
| 1002:4391 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 633   | ahci       | 77FCB9CF4A |
| 1022:43b7 | 1b21:1062 | AMD        | 300 Series Chipset SATA C... | 611   | ahci       | 52C67D407D |
| 1022:7901 | 1849:7901 | AMD        | FCH SATA Controller [AHCI... | 591   | ahci       | E1B676D2A4 |
| 8086:1c02 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 574   | ahci       | EA164260EB |
| 1b21:0612 | 1043:84b7 | ASMedia... | ASM1062 Serial ATA Contro... | 547   | ahci       | 9F527DED3C |
| 8086:1e02 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 529   | ahci       | BA117FEF7E |
| 1022:43b8 | 1b21:1062 | AMD        | FCH SATA Controller D        | 509   | ahci       | 4654691B7A |
| 8086:8c02 | 1458:b005 | Intel      | 8 Series/C220 Series Chip... | 491   | ahci       | E187B3F207 |
| 1b21:0612 | 1849:0612 | ASMedia... | ASM1062 Serial ATA Contro... | 489   | ahci       | 39FCD76D77 |
| 8086:1e03 | 17aa:3977 | Intel      | 7 Series Chipset Family 6... | 473   | ahci       | 5872E567EC |
| 1022:43eb | 1b21:1062 | AMD        | Starship/Matisse Chipset ... | 424   | ahci       | A82D785D77 |
| 1b21:0612 | 1b21:1060 | ASMedia... | ASM1062 Serial ATA Contro... | 364   | ahci       | 0619809B36 |
| 8086:a102 | 1458:b005 | Intel      | Q170/Q150/B150/H170/H110/... | 352   | ahci       | 213A5CCCC3 |
| 8086:a282 | 1043:8694 | Intel      | 200 Series PCH SATA contr... | 352   | ahci       | 2696477C0C |
| 8086:a282 | 1458:b005 | Intel      | 200 Series PCH SATA contr... | 348   | ahci       | F91A20DD51 |
| 1022:43b5 | 1b21:1062 | AMD        | X370 Series Chipset SATA ... | 339   | ahci       | F544511E0A |
| 1022:7901 | 1043:87c0 | AMD        | FCH SATA Controller [AHCI... | 339   | ahci       | 97C17F738A |
| 1022:43c8 | 1849:43c8 | AMD        | 400 Series Chipset SATA C... | 312   | ahci       | FCFE2F037F |
| 1002:4391 | 1849:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 293   | ahci       | 0A228B18C1 |
| 8086:1e02 | 1458:b005 | Intel      | 7 Series/C210 Series Chip... | 283   | ahci       | 89F6EB0671 |
| 1022:7801 | 1849:7801 | AMD        | FCH SATA Controller [AHCI... | 280   | ahci       | 3D65247771 |
| 8086:1c03 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 275   | ahci       | 21DB34139A |
| 8086:9c03 | 17aa:3978 | Intel      | 8 Series SATA Controller ... | 275   | ahci       | B1B8196F26 |
| 1022:7801 | 1458:b002 | AMD        | FCH SATA Controller [AHCI... | 274   | ahci       | E03FD39AD4 |
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 262   | ahci       | 71A92492E3 |
| 8086:8c82 | 1043:8534 | Intel      | 9 Series Chipset Family S... | 262   | ahci       | 0D40DAA834 |
| 8086:a352 | 1043:8694 | Intel      | Cannon Lake PCH SATA AHCI... | 260   | ahci       | 2CFB272CEC |
| 8086:2929 | 17aa:20f8 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 256   | ahci       | DB936567F0 |
| 8086:27c1 | 1043:83ad | Intel      | NM10/ICH7 Family SATA Con... | 248   | ahci       | 2117F02A4F |
| 8086:1c02 | 1458:b005 | Intel      | 6 Series/C200 Series Chip... | 238   | ahci       | EE570B7B0C |
| 8086:3b2f | 17aa:2168 | Intel      | 5 Series/3400 Series Chip... | 234   | ahci       | 5DC4A1E557 |
| 8086:a352 | 1458:b005 | Intel      | Cannon Lake PCH SATA AHCI... | 234   | ahci       | E8B8B03EBD |
| 8086:8c02 | 1849:8c02 | Intel      | 8 Series/C220 Series Chip... | 232   | ahci       | F36828F316 |
| 1022:7901 | 1043:876b | AMD        | FCH SATA Controller [AHCI... | 225   | ahci       | 500976E7D1 |
| 1b4b:9172 | 1458:b000 | Marvell... | 88SE9172 SATA 6Gb/s Contr... | 225   | ahci       | 912C8764EF |
| 197b:2362 | 1043:8460 | JMicron... | JMB362 SATA Controller       | 219   | ahci       | A7526AA47D |
| 8086:8c82 | 1458:b005 | Intel      | 9 Series Chipset Family S... | 212   | ahci       | DF13F72A9A |
| 8086:31e3 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 208   | ahci       | 021617B9A0 |
| 1002:4390 | 1849:4390 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 207   | ahci       | 256C66503A |
| 8086:3a22 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) SA... | 206   | ahci       | 2E1659CD91 |
| 8086:1e03 | 8086:7270 | Intel      | 7 Series Chipset Family 6... | 203   | ahci       | 066B825941 |
| 1b21:0612 | 1043:858d | ASMedia... | ASM1062 Serial ATA Contro... | 200   | ahci       | 86CEE5AEF6 |
| 10de:0ab9 | 10de:cb79 | Nvidia     | MCP79 AHCI Controller        | 181   | ahci       | F982A2F6CC |
| 8086:1c03 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 176   | ahci       | 7EBB0672C0 |
| 8086:a102 | 1849:a102 | Intel      | Q170/Q150/B150/H170/H110/... | 170   | ahci       | 3A2A9BD626 |
| 8086:1e02 | 1849:1e02 | Intel      | 7 Series/C210 Series Chip... | 166   | ahci       | E7EBAD7358 |
| 8086:1e03 | 17aa:21f3 | Intel      | 7 Series Chipset Family 6... | 162   | ahci       | C9503690D6 |
| 1022:7800 | 1458:b002 | AMD        | FCH SATA Controller [IDE ... | 160   | ahci       | 0E94F2AD8F |
| 8086:3b29 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 159   | ahci       | 11F1CDC49A |
| 8086:1e02 | 1028:0577 | Intel      | 7 Series/C210 Series Chip... | 157   | ahci       | 4DAF9FDC0D |
| 1022:7901 | 1849:ffff | AMD        | FCH SATA Controller [AHCI... | 153   | ahci       | CCD56ACB24 |
| 8086:8c02 | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 152   | ahci       | 75E2E357A3 |
| 1002:4390 | 1002:4390 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 149   | ahci       | F977555A51 |
| 1002:4391 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 149   | ahci       | EF97789A6A |
| 8086:1c02 | 1849:1c02 | Intel      | 6 Series/C200 Series Chip... | 148   | ahci       | EFEC95A916 |
| 144d:a801 | 144d:a801 | Samsung... | Electronics SATA controller  | 144   | ahci       | C0ED6370C5 |
| 8086:1c03 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 144   | ahci       | 74547808D3 |
| 8086:1c03 | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 143   | ahci       | 438D785F0E |
| 8086:1e03 | 1025:0649 | Intel      | 7 Series Chipset Family 6... | 143   | ahci       | 52667487D2 |
| 8086:8c03 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 141   | ahci       | 7FB630F632 |
| 8086:1c03 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 139   | ahci       | B420F25ED4 |
| 8086:a282 | 1849:a282 | Intel      | 200 Series PCH SATA contr... | 138   | ahci       | A8F84AEA94 |
| 1002:4391 | 1002:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 137   | ahci       | B4E0DCBA77 |
| 1022:7901 | 1462:7c02 | AMD        | FCH SATA Controller [AHCI... | 137   | ahci       | 2229C9E9F6 |
| 1022:43b6 | 1b21:1062 | AMD        | X399 Series Chipset SATA ... | 136   | ahci       | 9A02CBA527 |
| 8086:31e3 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 135   | ahci       | 170B220F5B |
| 8086:1e03 | 17aa:21fa | Intel      | 7 Series Chipset Family 6... | 133   | ahci       | 50D562CAB5 |
| 1b4b:9215 | 1b4b:9215 | Marvell... | 88SE9215 PCIe 2.0 x1 4-po... | 132   | ahci       | 3310677E00 |
| 8086:2929 | 17aa:3a1a | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 130   | ahci       | 1BBEC614AA |
| 8086:3b29 | 17aa:38c1 | Intel      | 5 Series/3400 Series Chip... | 129   | ahci       | CEAF1A4989 |
| 8086:1d02 | 1043:84ef | Intel      | C600/X79 series chipset 6... | 128   | ahci       | F0DC31F93D |
| 1022:7801 | 1462:7721 | AMD        | FCH SATA Controller [AHCI... | 126   | ahci       | 01C5E2E798 |
| 8086:3b29 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 123   | ahci       | 03E0270FDD |
| 8086:9d03 | 17aa:386a | Intel      | Sunrise Point-LP SATA Con... | 123   | ahci       | 19226582D9 |
| 8086:1e03 | 1043:124d | Intel      | 7 Series Chipset Family 6... | 118   | ahci       | 08930695BC |
| 1022:7801 | 1043:85ca | AMD        | FCH SATA Controller [AHCI... | 117   | ahci       | BDB612797A |
| 1022:7801 | 17aa:3801 | AMD        | FCH SATA Controller [AHCI... | 115   | ahci       | 779BFC3B47 |
| 8086:1c03 | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 115   | ahci       | FF37A9C00D |
| 8086:1c03 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 114   | ahci       | 660A6B9E20 |
| 1022:43b8 | 1849:43c8 | AMD        | FCH SATA Controller D        | 113   | ahci       | 094ADE14AE |
| 8086:9dd3 | 8086:2074 | Intel      | Cannon Point-LP SATA Cont... | 112   | ahci       | 7CA350189C |
| 8086:a353 | 1028:0905 | Intel      | Cannon Lake Mobile PCH SA... | 112   | ahci       | 9CDE952049 |
| 8086:a282 | 1043:872f | Intel      | 200 Series PCH SATA contr... | 111   | ahci       | C1BF9C169D |
| 8086:3b29 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 109   | ahci       | C172C655DE |
| 8086:9c03 | 17aa:220c | Intel      | 8 Series SATA Controller ... | 109   | ahci       | 4C600416F9 |
| 8086:1e03 | 1025:064b | Intel      | 7 Series Chipset Family 6... | 108   | ahci       | B732F94275 |
| 1022:7904 | 103c:8330 | AMD        | FCH SATA Controller [AHCI... | 107   | ahci       | 5671BA2F85 |
| 8086:02d3 | 17aa:5079 | Intel      | Comet Lake SATA AHCI Cont... | 107   | ahci       | 0BC4073D23 |
| 8086:1e03 | 17aa:21f6 | Intel      | 7 Series Chipset Family 6... | 107   | ahci       | 9ECBB7A946 |
| 1b4b:9130 | 1043:8438 | Marvell... | 88SE9128 PCIe SATA 6 Gb/s... | 105   | ahci       | BA117FEF7E |
| 8086:1c03 | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 105   | ahci       | A8FD68FCCC |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:439c | 1458:5002 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1084  | pata_at... | 77FCB9CF4A |
| 8086:27df | 1043:8179 | Intel      | 82801G (ICH7 Family) IDE ... | 984   | ata_pii... | 5889B752F5 |
| 1002:439c | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 786   | pata_at... | 67B53F9BDB |
| 8086:27c0 | 1458:b002 | Intel      | NM10/ICH7 Family SATA Con... | 735   | ata_pii... | 43A5D97DD3 |
| 8086:27c0 | 1043:8179 | Intel      | NM10/ICH7 Family SATA Con... | 709   | ata_pii... | 5889B752F5 |
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
| 1002:439c | 1002:439c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 163   | pata_at... | F977555A51 |
| 8086:1e00 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 159   | ata_pii... | 524DE3A747 |
| 8086:1e08 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 159   | ata_pii... | 524DE3A747 |
| 8086:27df | 1458:b001 | Intel      | 82801G (ICH7 Family) IDE ... | 158   | ata_pii... | BD17F8FBD9 |
| 8086:2926 | 1458:b002 | Intel      | 82801I (ICH9 Family) 2 po... | 156   | ata_pii... | 5B2102BA4E |
| 8086:27c0 | 8086:27c0 | Intel      | NM10/ICH7 Family SATA Con... | 145   | pata_acpi  | A22FBCDE28 |
| 10de:03f6 | 1043:83a4 | Nvidia     | MCP61 SATA Controller        | 144   | sata_nv... | 1C28AB7987 |
| 10de:03ec | 1458:5002 | Nvidia     | MCP61 IDE                    | 142   | pata_am... | FB1E012F68 |
| 10de:03ec | 1043:83a4 | Nvidia     | MCP61 IDE                    | 139   | pata_am... | 1C28AB7987 |
| 11ab:6101 | 1043:82e0 | Marvell... | 88SE6101/6102 single-port... | 129   | pata_ma... | 7AAC504D79 |
| 8086:2850 | 1025:011f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 122   | ata_pii... | 6A05B72968 |
| 8086:27df | 8086:27df | Intel      | 82801G (ICH7 Family) IDE ... | 120   | pata_acpi  | A22FBCDE28 |
| 11ab:6101 | 11ab:6101 | Marvell... | 88SE6101/6102 single-port... | 119   | pata_ma... | 4502B92271 |
| 10de:03f6 | 1043:8234 | Nvidia     | MCP61 SATA Controller        | 116   | sata_nv... | A5CA2582B6 |
| 10de:03ec | 1043:8234 | Nvidia     | MCP61 IDE                    | 113   | pata_am... | A5CA2582B6 |
| 8086:3b20 | 1458:b002 | Intel      | 5 Series/3400 Series Chip... | 113   | ata_pii... | 25153D8586 |
| 8086:3b26 | 1458:b002 | Intel      | 5 Series/3400 Series Chip... | 113   | ata_pii... | 25153D8586 |
| 8086:2920 | 1043:8277 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 108   | ata_pii... | 4F6DEFB975 |
| 1002:439c | 1043:82ef | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 105   | pata_at... | 3B96E27283 |
| 8086:1c00 | 1849:1c00 | Intel      | 6 Series/C200 Series Chip... | 103   | ata_pii... | 3F3962DF59 |
| 8086:2850 | 17aa:20a6 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 103   | pata_acpi  | 8A05529E0C |
| 8086:1c08 | 1849:1c08 | Intel      | 6 Series/C200 Series Chip... | 102   | ata_pii... | 3F3962DF59 |
| 8086:27c0 | 1462:7592 | Intel      | NM10/ICH7 Family SATA Con... | 96    | pata_acpi  | 57D1C4DAFA |
| 10de:0053 | 1043:815a | Nvidia     | CK804 IDE                    | 92    | pata_am... | 00B830F623 |
| 10de:0055 | 1043:815a | Nvidia     | CK804 Serial ATA Controller  | 92    | sata_nv... | 00B830F623 |
| 8086:2850 | 1028:01f9 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 92    | pata_acpi  | E271885D51 |
| 10de:0054 | 1043:815a | Nvidia     | CK804 Serial ATA Controller  | 91    | sata_nv... | 00B830F623 |
| 8086:29b6 | 1028:0211 | Intel      | 82Q35 Express PT IDER Con... | 91    | pata_acpi  | 962E0B75E4 |
| 11ab:6121 | 1043:82a2 | Marvell... | 88SE6111/6121 SATA II / P... | 89    | pata_ma... | 50AE548F24 |
| 8086:2825 | 1043:81ec | Intel      | 82801HR/HO/HH (ICH8R/DO/D... | 89    | ata_pii... | 926229BE87 |
| 8086:2820 | 1043:81ec | Intel      | 82801H (ICH8 Family) 4 po... | 88    | ata_pii... | 926229BE87 |
| 8086:27df | 1462:7592 | Intel      | 82801G (ICH7 Family) IDE ... | 87    | pata_acpi  | 57D1C4DAFA |
| 8086:2e16 | 1028:0420 | Intel      | 4 Series Chipset PT IDER ... | 84    | pata_acpi  | 340184FB36 |
| 8086:2850 | 106b:00a0 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 82    | pata_acpi  | 00CC913F3D |
| 8086:27c0 | 1462:7529 | Intel      | NM10/ICH7 Family SATA Con... | 80    | ata_pii... | A4B55E447A |
| 197b:2363 | 197b:2363 | JMicron... | JMB363 SATA/IDE Controller   | 79    | ahci       | 47F43BD121 |
| 8086:2921 | 1458:b002 | Intel      | 82801IB (ICH9) 2 port SAT... | 79    | ata_pii... | D0DD5188EE |
| 8086:2e16 | 1028:027f | Intel      | 4 Series Chipset PT IDER ... | 79    | pata_acpi  | 8F0C6ED152 |
| 11ab:6121 | 1043:82e0 | Marvell... | 88SE6111/6121 SATA II / P... | 78    | pata_ma... | 102C78CA6B |
| 8086:27df | 1462:7529 | Intel      | 82801G (ICH7 Family) IDE ... | 78    | ata_pii... | A4B55E447A |
| 8086:2920 | 1458:b002 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 77    | pata_acpi  | 5B2102BA4E |
| 8086:27df | 8086:7270 | Intel      | 82801G (ICH7 Family) IDE ... | 75    | pata_acpi  | C480910C6C |
| 8086:2850 | 1028:022f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 74    | pata_acpi  | 06130B24C5 |
| 1039:5513 | 1039:5513 | Silicon... | 5513 IDE Controller          | 73    | pata_acpi  | 1A587EFF16 |
| 1002:439c | 1043:8443 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 72    | pata_at... | 23198E478A |
| 8086:2828 | 1028:01f9 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 72    | pata_acpi  | E271885D51 |
| 10de:03f6 | 1462:7309 | Nvidia     | MCP61 SATA Controller        | 71    | sata_nv... | DC2D2CA478 |
| 8086:1c00 | 1028:04f5 | Intel      | 6 Series/C200 Series Chip... | 71    | pata_acpi  | 00CE09B473 |
| 8086:1c08 | 1028:04f5 | Intel      | 6 Series/C200 Series Chip... | 71    | pata_acpi  | 00CE09B473 |
| 8086:2820 | 1028:01da | Intel      | 82801H (ICH8 Family) 4 po... | 71    | pata_acpi  | 8939E63ADE |
| 8086:2825 | 1028:01da | Intel      | 82801HR/HO/HH (ICH8R/DO/D... | 71    | pata_acpi  | 8939E63ADE |
| 197b:2361 | 1043:824f | JMicron... | JMB361 AHCI/IDE              | 68    | ahci       | A39538D7C5 |
| 8086:27c0 | 1565:5202 | Intel      | NM10/ICH7 Family SATA Con... | 67    | ata_piix   | 960762905F |
| 8086:27df | 1565:3103 | Intel      | 82801G (ICH7 Family) IDE ... | 67    | ata_piix   | 960762905F |
| 8086:2850 | 106b:00a1 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 67    | pata_acpi  | E31DDE7E74 |
| 1002:439c | 1462:7641 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 64    | pata_at... | 26947ED7FD |
| 8086:24db | 1043:80a6 | Intel      | 82801EB/ER (ICH5/ICH5R) I... | 64    | ata_pii... | 97A6A04DB2 |
| 8086:27c0 | 1028:01ad | Intel      | NM10/ICH7 Family SATA Con... | 64    | pata_acpi  | 132993403B |
| 197b:2368 | 1043:824f | JMicron... | JMB368 IDE controller        | 63    | pata_jm... | 4F6DEFB975 |
| 1b4b:917a | 1458:b000 | Marvell... | 88SE9172 SATA III 6Gb/s R... | 63    | pata_ac... | EE570B7B0C |
| 8086:27c4 | 8086:7270 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 63    | pata_acpi  | C480910C6C |
| 10de:03f6 | 1565:5405 | Nvidia     | MCP61 SATA Controller        | 62    | sata_nv... | FF6423FB29 |
| 1106:0415 | 1849:0415 | VIA Tec... | VT6415 PATA IDE Host Cont... | 62    | pata_vi... | CB9E834556 |
| 8086:27df | 1028:01ad | Intel      | 82801G (ICH7 Family) IDE ... | 62    | pata_acpi  | 132993403B |
| 8086:2850 | 103c:30cc | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 62    | pata_acpi  | 4E93C68985 |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 3964  | nvme       | 6670E1C145 |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 1159  | nvme       | B8D0E81636 |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 770   | nvme       | 3A3BF28C3A |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 619   | nvme       | 3D0DA576B8 |
| 15b7:5006 | 15b7:5006 | Sandisk    | WD Black SN750 / PC SN730... | 543   | nvme       | 011A257801 |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | BC501 NVMe Solid State Dr... | 476   | nvme       | 052B95BA1D |
| 15b7:5003 | 15b7:5003 | Sandisk    | WD Blue SN500 / PC SN520 ... | 466   | nvme       | CDD4DC075D |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/SN750 / PC ... | 446   | nvme       | 36248F1BF0 |
| 144d:a809 | 144d:a801 | Samsung... | NVMe Controller              | 433   | nvme       | B7EC4606A3 |
| 15b7:5009 | 15b7:5009 | Sandisk    | WD Blue SN550 NVMe SSD       | 366   | nvme       | 150AFCB2D1 |
| 126f:2263 | 126f:2263 | Silicon... | SM2263EN/SM2263XT SSD Con... | 345   | nvme       | 92E5728D1A |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 332   | nvme       | 97C17F738A |
| 1179:011a | 1179:0001 | Toshiba... | XG6 NVMe SSD Controller      | 329   | nvme       | 11F1E42FBE |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 322   | nvme       | 9358C3AFBF |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 322   | nvme       | CC69851E7F |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 309   | nvme       | 54BAAAD690 |
| 1179:0113 | 1179:0001 | Toshiba... | BG3 NVMe SSD Controller      | 304   | nvme       | 62C94909C7 |
| 1e0f:0001 | 1e0f:0001 | KIOXIA     | Non-Volatile memory contr... | 294   | nvme       | AD3C1FB56A |
| 2646:2263 | 2646:2263 | Kingsto... | A2000 NVMe SSD               | 285   | nvme       | 5125306D59 |
| 2646:5008 | 2646:5008 | Kingsto... | U-SNS8154P3 NVMe SSD         | 274   | nvme       | 36EBF65D44 |
| 1987:5016 | 1987:5016 | Phison ... | E16 PCIe4 NVMe Controller    | 263   | nvme       | 65310866EB |
| c0a9:2263 | c0a9:2263 | Micron/... | P1 NVMe PCIe SSD             | 255   | nvme       | 4E5245A71D |
| 1c5c:1339 | 1c5c:0000 | SK Hynix   | BC511                        | 254   | nvme       | BD16A61719 |
| 1c5c:1527 | 1c5c:1527 | SK Hynix   | PC401 NVMe Solid State Dr... | 201   | nvme       | 1A0B1FFDBD |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 201   | nvme       | 3D1A8CFFC3 |
| 1344:5410 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 189   | nvme       | B0722E1B57 |
| 8086:0000 |           | Intel      | PROSet/Wireless WiFi Soft... | 182   | nvme       | 883283C763 |
| 15b7:5005 | 15b7:5005 | Sandisk    | PC SN520 NVMe SSD            | 161   | nvme       | AB6647F9DA |
| 126f:2262 | 126f:2262 | Silicon... | SM2262/SM2262EN SSD Contr... | 157   | nvme       | 0A4BF488D4 |
| 1c5c:1627 | 1c5c:1627 | SK Hynix   | Non-Volatile memory contr... | 157   | nvme       | 02D50458CE |
| 1179:0115 | 1179:0001 | Toshiba... | XG4 NVMe SSD Controller      | 140   | nvme       | 02894A3C1D |
| 1c5c:1639 | 1c5c:1639 | SK Hynix   | Non-Volatile memory contr... | 119   | nvme       | FBBAF8088B |
| 144d:a80a | 144d:a801 | Samsung... | NVMe SSD Controller PM9A1... | 116   | nvme       | 62DDF1B4F0 |
| 8086:0975 | 8086:8410 | Intel      | Non-Volatile memory contr... | 102   | nvme       | 520E728AF7 |
| 8086:0975 | 8086:8510 | Intel      | Non-Volatile memory contr... | 100   | nvme       | 520E728AF7 |
| 10ec:5762 | 10ec:5762 | Realtek... | RTS5763DL NVMe SSD Contro... | 99    | nvme       | 099F671965 |
| 1987:5013 | 1987:5013 | Phison ... | PS5013 E13 NVMe Controller   | 81    | nvme       | F19E7920CA |
| 2646:500c | 2646:500c | Kingsto... | Technology Company Non-Vo... | 81    | nvme       | F504E72617 |
| 1cc4:5008 | 1cc4:5008 | Union M... | Non-Volatile memory contr... | 79    | nvme       | 099F671965 |
| 1344:5405 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 78    | nvme       | 862B2D2013 |
| 15b7:5004 | 15b7:5004 | Sandisk    | PC SN520 NVMe SSD            | 77    | nvme       | DB1162156B |
| 1987:5008 | 1987:5008 | Phison ... | NVMe Storage Controller      | 77    | nvme       | E8B8B03EBD |
| 10ec:5763 | 10ec:5763 | Realtek... | Realtek Non-Volatile memo... | 76    | nvme       | EEE4DBBB99 |
| 1179:010f | 1179:0001 | Toshiba... | NVMe Controller              | 67    | nvme       | 6FE52D4F4F |
| c0a9:540a | c0a9:540a | Micron/... | P2 NVMe PCIe SSD             | 66    | nvme       | DACE055942 |
| 15b7:5008 | 15b7:5008 | Sandisk    | Non-Volatile memory contr... | 63    | nvme       | 80A31F37F4 |
| 1cc1:33f3 | 1cc1:33f3 | ADATA T... | Non-Volatile memory contr... | 56    | nvme       | ED812AF95A |
| 1987:5007 | 1987:5007 | Phison ... | E7 NVMe Controller           | 54    | nvme       | 0F7555A7BD |
| 15b7:5001 | 1b4b:1093 | Sandisk    | WD Black NVMe SSD            | 48    | nvme       | E71B786BE5 |
| 106b:2005 | 106b:1800 | Apple      | ANS2 NVMe Controller         | 46    | nvme       | 2BDDF8B98A |
| c0a9:5403 | c0a9:2100 | Micron/... | NVMe Controller              | 45    | nvme       | A82D785D77 |
| 14a4:2300 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 41    | nvme       | 7FD687D091 |
| 1c5c:174a | 1c5c:174a | SK Hynix   | NVMe SSD Controller          | 41    | nvme       | DB4A212405 |
| 1cc1:33f8 | 1cc1:33f8 | ADATA T... | Non-Volatile memory contr... | 38    | nvme       | 80CF3DC8E7 |
| 1e95:9100 | 126f:2263 | Solid S... | Non-Volatile memory contr... | 38    | nvme       | DE11AB3CC4 |
| 144d:a806 | 144d:a801 | Samsung... | Electronics Non-Volatile ... | 32    | nvme       | 7A294509DE |
| 1bb1:5012 | 1bb1:5012 | Seagate... | FireCuda 510 SSD             | 32    | nvme       | E0217F85A6 |
| 14a4:23f1 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 30    | nvme       | BD59689744 |
| 1bb1:5016 | 1bb1:5016 | Seagate... | FireCuda 520 SSD             | 29    | nvme       | 9B20A88D5E |
| 14a4:9100 | 126f:2263 | Lite-On... | NVMe Controller              | 28    | nvme       | D32CA82327 |
| 106b:2003 | 106b:2003 | Apple      | S3X NVMe Controller          | 27    | nvme       | 8030B99150 |
| 14a4:22f1 | 1b4b:1093 | Lite-On... | M8Pe Series NVMe SSD         | 25    | nvme       | 4601ED2BC4 |
| 17aa:0003 | 17aa:1003 | Lenovo     | Non-Volatile memory contr... | 24    | nvme       | D6371109B2 |
| 8086:2522 | 8086:3810 | Intel      | NVMe Optane Memory Series    | 23    | nvme       | 2198E565BF |
| 1b85:6018 | 1b85:6018 | OCZ Tec... | RD400/400A SSD               | 22    | nvme       | EC035AF0D0 |
| 17aa:0004 | 17aa:1004 | Lenovo     | Non-Volatile memory contr... | 21    | nvme       | DE4F669B51 |
| 17aa:0006 | 17aa:1006 | Lenovo     | Non-Volatile memory contr... | 21    | nvme       | 1649C0AE85 |
| 1cc4:6202 | 1cc4:1cc4 | Union M... | Non-Volatile memory contr... | 21    | nvme       | 1697AC5B27 |
| 8086:2522 | 8086:3806 | Intel      | NVMe Optane Memory Series    | 21    | nvme       | 40B6622CD1 |
| 8086:faf0 | 8086:390e | Intel      | Non-Volatile memory contr... | 21    | nvme       | AA8070C052 |
| 15b7:5011 | 15b7:5011 | Sandisk    | WD Black SN850               | 19    | nvme       | 654C105561 |
| 17aa:0005 | 17aa:1005 | Lenovo     | Non-Volatile memory contr... | 19    | nvme       | 37FD15B69E |
| 2646:2262 | 2646:2262 | Kingsto... | KC2000 NVMe SSD              | 19    | nvme       | 6566F6CABC |
| c0a9:5412 | c0a9:0100 | Micron/... | Non-Volatile memory contr... | 19    | nvme       | 3CCC205BB6 |
| 15b7:5007 | 15b7:5007 | Sandisk    | Non-Volatile memory contr... | 18    | nvme       | 4157528079 |
| 1d97:1160 | 1d97:1160 | Shenzhe... | Non-Volatile memory contr... | 18    | nvme       | 02F641EA60 |
| 1c5c:1284 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 17    | nvme       | DBEA4F6B5F |
| 10ec:5760 | 5760:10ec | Realtek... | Realtek Non-Volatile memo... | 16    | nvme       | 7D0B344759 |
| 1344:5404 | 1344:2100 | Micron ... | Non-Volatile memory contr... | 15    | nvme       | B70A62225D |
| 14a4:2200 | 1b4b:1093 | Lite-On... | Lite-On Non-Volatile memo... | 14    | nvme       | DB99936C38 |
| 1c5c:1283 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 14    | nvme       | 97DBD7A2D0 |
| 126f:2260 | 126f:2260 | Silicon... | Non-Volatile memory contr... | 13    | nvme       | 400EFE971D |
| 14a4:2100 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 13    | nvme       | 471A5FED37 |
| 1cc1:8201 | 1cc1:1cc1 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 13    | nvme       | F03341D873 |
| 1cc4:6203 | 1cc4:1cc4 | Union M... | Non-Volatile memory contr... | 13    | nvme       | 64A9E43743 |
| 8086:0953 | 8086:370d | Intel      | PCIe Data Center SSD         | 13    | nvme       | A479D22343 |
| c0a9:5403 | c0a9:1100 | Micron/... | NVMe Controller              | 13    | nvme       | 06BB083E38 |
| 106b:2001 | 106b:2001 | Apple      | S1X NVMe Controller          | 11    | nvme       | 9D1694385F |
| 1344:5404 | 1344:1100 | Micron ... | Non-Volatile memory contr... | 10    | nvme       | 5707E7AE37 |
| 1e0f:0009 | 1e0f:0001 | KIOXIA     | NVMe SSD                     | 10    | nvme       | 0548F9650B |
| 8086:2700 | 8086:3900 | Intel      | Optane SSD 900P Series       | 10    | nvme       | F72C74AA38 |
| 1cc4:2263 | 1cc4:1cc4 | Union M... | Non-Volatile memory contr... | 9     | nvme       | 4DE4650899 |
| 2646:500d | 2646:500d | Kingsto... | OM3PDP3 NVMe SSD             | 9     | nvme       | D88C558CDA |
| 8086:0a54 | 8086:4802 | Intel      | NVMe Datacenter SSD [3DNA... | 9     | nvme       | 1D97B5C83D |
| 14a4:3500 | 1b4b:1092 | Lite-On... | Non-Volatile memory contr... | 8     | nvme       | 969B2E9724 |
| 1c5c:1285 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 8     | nvme       | C0542C238C |
| 1cc4:5012 | 1cc4:5012 | Union M... | Non-Volatile memory contr... | 8     | nvme       | 9CD4E14D95 |
| 8086:2700 | 8086:3901 | Intel      | Optane SSD 900P Series       | 8     | nvme       | 6FEB0AEC47 |
| 1c5c:1504 | 0100:1093 | SK Hynix   | SC300 512GB M.2 2280 SATA... | 6     | nvme       | 66C6D53439 |
| 1d97:2263 | 1d97:2263 | Shenzhe... | SM2263EN/SM2263XT-based O... | 6     | nvme       | 7DBDABF49B |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2822 | 1043:8694 | Intel      | SATA Controller [RAID mode]  | 105   | ahci       | 243CDC0172 |
| 8086:282a | 1025:1331 | Intel      | 82801 Mobile SATA Control... | 98    | intel_n... | 38688703F4 |
| 8086:282a | 1028:0233 | Intel      | 82801 Mobile SATA Control... | 87    | ahci       | 2A4C5F6EEC |
| 8086:2822 | 1458:b005 | Intel      | SATA Controller [RAID mode]  | 81    | ahci       | 197E319075 |
| 8086:282a | 1028:0534 | Intel      | 82801 Mobile SATA Control... | 79    | ahci       | 98420A7D92 |
| 8086:282a | 1028:0493 | Intel      | 82801 Mobile SATA Control... | 77    | ahci       | 33617DD1A8 |
| 8086:282a | 1028:040a | Intel      | 82801 Mobile SATA Control... | 76    | ahci       | 7E35C63842 |
| 8086:2822 | 1028:0420 | Intel      | SATA Controller [RAID mode]  | 75    | ahci       | 5824A76242 |
| 1106:3249 | 1106:3249 | VIA Tec... | VT6421 IDE/SATA Controller   | 63    | sata_via   | 5BFD23A80C |
| 8086:2822 | 1028:05a4 | Intel      | SATA Controller [RAID mode]  | 63    | ahci       | 86611A5EFE |
| 8086:282a | 103c:84a6 | Intel      | 82801 Mobile SATA Control... | 61    | ahci       | 197CBC5A5D |
| 8086:282a | 1028:0810 | Intel      | 82801 Mobile SATA Control... | 58    | ahci       | 2FD333BC52 |
| 8086:2822 | 1028:047e | Intel      | SATA Controller [RAID mode]  | 49    | ahci       | 959E3DDE54 |
| 8086:282a | 1028:05cb | Intel      | 82801 Mobile SATA Control... | 47    | ahci       | EF82F4635D |
| 8086:9a0b | 8086:0000 | Intel      | Volume Management Device ... | 47    | vmd        | B63698A4AF |
| 8086:282a | 103c:1818 | Intel      | 82801 Mobile SATA Control... | 45    | ahci       | B9FD7914E2 |
| 8086:282a | 17aa:380f | Intel      | 82801 Mobile SATA Control... | 45    | ahci       | 27B310BDD9 |
| 8086:282a | 1025:1264 | Intel      | 82801 Mobile SATA Control... | 44    | ahci       | 99EE0E5718 |
| 103c:323a | 103c:3245 | Hewlett... | Smart Array G6 controllers   | 43    | hpsa       | C56840DF98 |
| 8086:2822 | 103c:1309 | Intel      | SATA Controller [RAID mode]  | 40    | ahci       | 83C114D947 |
| 8086:2822 | 103c:2a6f | Intel      | SATA Controller [RAID mode]  | 38    | ahci       | D8F52BAB1C |
| 1095:3114 | 1095:7114 | Silicon... | SiI 3114 [SATALink/SATARa... | 37    | sata_sil   | 20EBDE2857 |
| 8086:282a | 1025:1333 | Intel      | 82801 Mobile SATA Control... | 37    | intel_n... | CE68155512 |
| 1022:7916 | 1022:7901 | AMD        | RS690 PCI to PCI Bridge (... | 35    | ahci       | 56B16C9C71 |
| 8086:282a | 1028:0535 | Intel      | 82801 Mobile SATA Control... | 35    | ahci       | 2E9B8200A9 |
| 8086:282a | 1028:062e | Intel      | 82801 Mobile SATA Control... | 35    | ahci       | FFEE376E78 |
| 8086:2822 | 103c:2a9c | Intel      | SATA Controller [RAID mode]  | 34    | ahci       | 9A3C939249 |
| 8086:282a | 17aa:3814 | Intel      | 82801 Mobile SATA Control... | 34    | ahci       | E2D1740F3A |
| 8086:282a | 103c:8532 | Intel      | 82801 Mobile SATA Control... | 33    | ahci       | 92D97521BC |
| 8086:282a | 103c:86c9 | Intel      | 82801 Mobile SATA Control... | 33    | ahci       | B40784D2C7 |
| 8086:2822 | 1043:8534 | Intel      | SATA Controller [RAID mode]  | 32    | ahci       | 8F3CA163E7 |
| 8086:282a | 1028:05be | Intel      | 82801 Mobile SATA Control... | 32    | ahci       | B704F13C9D |
| 8086:282a | 1043:1961 | Intel      | 82801 Mobile SATA Control... | 32    | ahci       | DA20CA4C64 |
| 8086:282a | 1043:1311 | Intel      | 82801 Mobile SATA Control... | 31    | ahci       | AF70469300 |
| 8086:282a | 1028:05ca | Intel      | 82801 Mobile SATA Control... | 29    | ahci       | 9E790BA3F0 |
| 8086:2822 | 103c:130a | Intel      | SATA Controller [RAID mode]  | 28    | ahci       | EE9A2DA17C |
| 8086:282a | 1028:05bd | Intel      | 82801 Mobile SATA Control... | 28    | ahci       | FCD8E5D146 |
| 8086:2822 | 1028:052c | Intel      | SATA Controller [RAID mode]  | 27    | ahci       | C016FC8897 |
| 8086:282a | 1028:024f | Intel      | 82801 Mobile SATA Control... | 27    | ahci       | 3BDEE6855C |
| 8086:282a | 1028:0494 | Intel      | 82801 Mobile SATA Control... | 27    | ahci       | E58B9D7EA5 |
| 8086:282a | 1028:0798 | Intel      | 82801 Mobile SATA Control... | 27    | ahci       | 122ED0BBA8 |
| 1095:3132 | 1043:819f | Silicon... | SiI 3132 Serial ATA Raid ... | 25    | sata_sil24 | 0C04CD404A |
| 1095:3132 | 1095:7132 | Silicon... | SiI 3132 Serial ATA Raid ... | 25    | sata_sil24 | 799AD15D8B |
| 8086:282a | 1028:024d | Intel      | 82801 Mobile SATA Control... | 25    | ahci       | 98D088D90D |
| 8086:282a | 1028:040b | Intel      | 82801 Mobile SATA Control... | 25    | ahci       | 6902EB0F50 |
| 8086:282a | 1028:06dc | Intel      | 82801 Mobile SATA Control... | 25    | ahci       | 1058573F86 |
| 8086:282a | 1028:081c | Intel      | 82801 Mobile SATA Control... | 25    | ahci       | A92377CB2A |
| 8086:2822 | 1028:0293 | Intel      | SATA Controller [RAID mode]  | 24    | ahci       | ACE51E66CB |
| 8086:2822 | 1458:b000 | Intel      | SATA Controller [RAID mode]  | 24    | ahci       | 9021BAB8E3 |
| 8086:282a | 17aa:3810 | Intel      | 82801 Mobile SATA Control... | 24    | ahci       | 1BDD9DDF9F |
| 1022:43bd | 1b21:1062 | AMD        | FCH RAID Controller          | 23    | rcraid     | 220E356F41 |
| 1095:3512 | 1095:6512 | Silicon... | SiI 3512 [SATALink/SATARa... | 23    | sata_sil   | 751F3FAAFA |
| 8086:282a | 1028:0533 | Intel      | 82801 Mobile SATA Control... | 23    | ahci       | 4D7A7112A7 |
| 8086:282a | 103c:84a7 | Intel      | 82801 Mobile SATA Control... | 23    | ahci       | 3084883E0D |
| 8086:2826 | 103c:1589 | Intel      | C600/X79 series chipset S... | 22    | ahci       | 2F621A1BA2 |
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
| 103c:323b | 103c:3354 | Hewlett... | Smart Array Gen8 Controllers | 19    | hpsa       | 799CC190DB |
| 8086:2822 | 1043:872f | Intel      | SATA Controller [RAID mode]  | 19    | ahci       | AB16E4844B |
| 8086:282a | 1028:04a3 | Intel      | 82801 Mobile SATA Control... | 19    | ahci       | F11BC44848 |
| 8086:282a | 1028:07a7 | Intel      | 82801 Mobile SATA Control... | 19    | ahci       | BC9170F4CD |
| 8086:282a | 103c:8533 | Intel      | 82801 Mobile SATA Control... | 19    | ahci       | 6DA5C04DE8 |
| 1000:005d | 1000:9363 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 18    | megarai... | 2F38C3FD0E |
| 1000:0079 | 1028:1f17 | LSI Log... | MegaRAID SAS 2108 [Libera... | 18    | megarai... | B913A90C28 |
| 8086:282a | 1025:1357 | Intel      | 82801 Mobile SATA Control... | 18    | intel_n... | 7ACA41296B |
| 8086:282a | 1028:05e0 | Intel      | 82801 Mobile SATA Control... | 18    | ahci       | C17B0805A4 |
| 8086:282a | 1028:062d | Intel      | 82801 Mobile SATA Control... | 18    | ahci       | 8F57FEF409 |
| 8086:282a | 17aa:380e | Intel      | 82801 Mobile SATA Control... | 18    | ahci       | ACC650A900 |
| 8086:9a0b | 1028:0991 | Intel      | Volume Management Device ... | 18    | vmd        | F94CED9A41 |
| 8086:282a | 1025:1345 | Intel      | 82801 Mobile SATA Control... | 17    | intel_n... | AA70EAAAEC |
| 8086:282a | 1028:05cc | Intel      | 82801 Mobile SATA Control... | 17    | ahci       | 2293B2D4C4 |
| 8086:282a | 1043:1501 | Intel      | 82801 Mobile SATA Control... | 17    | ahci       | 4AA6169D3C |
| 8086:2822 | 103c:130b | Intel      | SATA Controller [RAID mode]  | 16    | ahci       | DFA7EF3696 |
| 8086:2827 | 103c:212b | Intel      | C610/X99 series chipset s... | 16    | ahci       | 84296E0108 |
| 8086:282a | 1028:0572 | Intel      | 82801 Mobile SATA Control... | 16    | ahci       | 518DC99F15 |
| 8086:282a | 1028:062b | Intel      | 82801 Mobile SATA Control... | 16    | ahci       | 5CE2BAD1C1 |
| 8086:282a | 1028:07a0 | Intel      | 82801 Mobile SATA Control... | 16    | ahci       | 6B9E1797C6 |
| 8086:282a | 1028:0825 | Intel      | 82801 Mobile SATA Control... | 16    | ahci       | AC76D208AB |
| 8086:282a | 103c:85ef | Intel      | 82801 Mobile SATA Control... | 16    | ahci       | F71D6DD289 |
| 1095:0680 | 1095:3680 | Silicon... | PCI0680 Ultra ATA-133 Hos... | 15    | pata_si... | DFA6B5B067 |
| 8086:2822 | 1043:84ca | Intel      | SATA Controller [RAID mode]  | 15    | ahci       | 0190551F1E |
| 8086:282a | 1028:053d | Intel      | 82801 Mobile SATA Control... | 15    | ahci       | DED5232894 |
| 8086:282a | 1028:057e | Intel      | 82801 Mobile SATA Control... | 15    | ahci       | C88A617A2D |
| 8086:282a | 1028:062c | Intel      | 82801 Mobile SATA Control... | 15    | ahci       | 765E6B13E0 |
| 8086:282a | 1028:06db | Intel      | 82801 Mobile SATA Control... | 15    | ahci       | B0E028DBE3 |
| 1002:4392 | 103c:2a92 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 14    | ahci       | C3468E4972 |
| 8086:2822 | 1028:05a6 | Intel      | SATA Controller [RAID mode]  | 14    | ahci       | 8280DED412 |
| 8086:2826 | 103c:158a | Intel      | C600/X79 series chipset S... | 14    | ahci       | 2FAC0FA486 |
| 8086:282a | 1028:0816 | Intel      | 82801 Mobile SATA Control... | 14    | ahci       | 266B7DD4F0 |
| 8086:282a | 103c:18a5 | Intel      | 82801 Mobile SATA Control... | 14    | ahci       | 1F794C0FC3 |
| 8086:282a | 1043:1591 | Intel      | 82801 Mobile SATA Control... | 14    | ahci       | 8BC72609A6 |
| 1106:3149 | 1043:80ed | VIA Tec... | VIA VT6420 SATA RAID Cont... | 13    | sata_via   | E739F2F0BA |

### Storage/sas (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1d6b | 103c:1589 | Intel      | C602 chipset 4-Port SATA ... | 34    | isci       | A4B0EBBEE2 |
| 1000:0086 | 103c:158b | Broadco... | SAS2308 PCI-Express Fusio... | 26    | mpt3sas    | 3991895525 |
| 1000:0072 | 1000:3020 | LSI Log... | SAS2008 PCI-Express Fusio... | 25    | mpt3sas    | A0D316EB3E |
| 8086:1d6b | 103c:158a | Intel      | C602 chipset 4-Port SATA ... | 24    | isci       | D70166F107 |
| 8086:1d6b | 103c:158b | Intel      | C602 chipset 4-Port SATA ... | 19    | isci       | E7D78D4E6C |
| 1000:0072 | 1028:1f1c | LSI Log... | SAS2008 PCI-Express Fusio... | 18    | mpt3sas    | 6F289497FC |
| 8086:1d6b | 1028:0497 | Intel      | C602 chipset 4-Port SATA ... | 11    | isci       | E81DFF7452 |
| 1000:0072 | 15d9:0400 | Broadco... | SAS2008 PCI-Express Fusio... | 10    | mpt3sas    | D5563E325C |
| 8086:1d6b | 1043:84ef | Intel      | C602 chipset 4-Port SATA ... | 10    | isci       | A4C832AB44 |
| 1000:0087 | 1028:05a1 | Broadco... | SAS2308 PCI-Express Fusio... | 9     | mpt3sas    | F62AEF3E7A |
| 8086:1d6b | 1734:11b6 | Intel      | C602 chipset 4-Port SATA ... | 8     | isci       | D018E3FE5A |
| 1000:0072 | 1028:1f1d | LSI Log... | SAS2008 PCI-Express Fusio... | 7     | mpt3sas    | 3B9C7E2331 |
| 1000:0087 | 1000:3020 | LSI Log... | SAS2308 PCI-Express Fusio... | 7     | mpt3sas    | 065D69BE16 |
| 1000:0070 | 1000:3010 | LSI Log... | SAS2004 PCI-Express Fusio... | 6     | mpt3sas    | 3440F55127 |
| 1000:0086 | 15d9:0691 | Broadco... | SAS2308 PCI-Express Fusio... | 6     | mpt3sas    | 837CECDAE8 |
| 1000:0072 | 1028:1f1e | Broadco... | SAS2008 PCI-Express Fusio... | 5     | mpt3sas    | 0335142464 |
| 19e5:a230 |           | Huawei ... | HiSilicon SAS 3.0 HBA        | 5     | hisi_sa... | 63BDABB5A4 |
| 8086:1d6b | 17aa:1026 | Intel      | C602 chipset 4-Port SATA ... | 5     | isci       | 4EBE8CAFC5 |
| 8086:1d6b | 1849:1d6b | Intel      | C602 chipset 4-Port SATA ... | 5     | isci       | 957F68F2B7 |
| 1000:0087 | 1000:3060 | Broadco... | SAS2308 PCI-Express Fusio... | 4     | mpt3sas    | 84296E0108 |
| 1000:0097 | 1000:30a0 | Broadco... | SAS3008 PCI-Express Fusio... | 4     | mpt3sas    | 98EA3E97E6 |
| 1000:0097 | 1000:30e0 | LSI Log... | SAS3008 PCI-Express Fusio... | 4     | mpt3sas    | F9D5463C17 |
| 1000:0097 | 1028:0619 | Broadco... | SAS3008 PCI-Express Fusio... | 4     | mpt3sas    | F96F352657 |
| 8086:1d6b | 8086:35a1 | Intel      | C602 chipset 4-Port SATA ... | 4     | isci       | FE1E6CFF79 |
| 1000:0072 | 1000:3040 | LSI Log... | SAS2008 PCI-Express Fusio... | 3     | mpt3sas    | 61DFD26E01 |
| 1000:0072 | 1000:3060 | Broadco... | SAS2008 PCI-Express Fusio... | 3     | mpt3sas    | 524206EFF9 |
| 8086:1d60 | 1028:0497 | Intel      | C608 chipset Dual 4-Port ... | 3     | isci       | E5B81A0DA1 |
| 8086:1d6b | 15d9:062c | Intel      | C602 chipset 4-Port SATA ... | 3     | isci       | FF94B1201C |
| 8086:1d6b | 17aa:1028 | Intel      | C602 chipset 4-Port SATA ... | 3     | isci       | 20CB7C14F8 |
| 9005:028f | 103c:0602 | Adaptec    | Smart Storage PQI SAS        | 3     | smartpqi   | A0E4A8C71D |
| 1000:0064 | 1000:30c0 | Broadco... | SAS2116 PCI-Express Fusio... | 2     | mpt3sas    | 7AEE1156D8 |
| 1000:0064 | 1000:30d0 | Broadco... | SAS2116 PCI-Express Fusio... | 2     | mpt3sas    | 31EA0B6D96 |
| 1000:0072 | 1000:30f0 | Broadco... | SAS2008 PCI-Express Fusio... | 2     | mpt3sas    | 6EEDB26906 |
| 1000:007e | 108e:050a | Broadco... | SSS6200 PCI-Express Flash... | 2     | mpt3sas    | A7CF5B0EFD |
| 1000:0087 | 1000:3030 | Broadco... | SAS2308 PCI-Express Fusio... | 2     | mpt3sas    | 1D8E87502F |
| 1000:0087 | 1000:3040 | LSI Log... | SAS2308 PCI-Express Fusio... | 2     | mpt3sas    | 9FC500CA2E |
| 1000:0097 | 1000:0090 | Broadco... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | 2903921AEB |
| 1000:0097 | 1028:1f46 | Broadco... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | 3C396F0B59 |
| 1000:0097 | 1028:1f53 | Broadco... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | DF9A63BE43 |
| 1000:0097 | 1043:860c | Broadco... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | C934F8E023 |
| 1000:0097 | 1734:1214 | LSI Log... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | A7138E79C0 |
| 1000:00c4 | 1000:31a0 | Broadco... | SAS3224 PCI-Express Fusio... | 2     | mpt3sas    | 195F9748AD |
| 8086:1d68 | 1028:0495 | Intel      | C606 chipset Dual 4-Port ... | 2     | isci       | 1AC850D5B7 |
| 8086:1d68 | 15d9:0626 | Intel      | C606 chipset Dual 4-Port ... | 2     | isci       | 2B8813F5C4 |
| 8086:1d6a | 17aa:1027 | Intel      | C600/X79 series chipset D... | 2     | isci       | 8D7A62CE1A |
| 8086:1d6b | 1028:0495 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | BC7C3F8C4D |
| 8086:1d6b | 1028:0496 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 80E68A5C66 |
| 8086:1d6b | 15d9:0636 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | DD93F62FFC |
| 8086:1d6b | 15d9:0660 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | AFE42B7E58 |
| 8086:1d6b | 15d9:0709 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 7D84E25468 |
| 8086:1d6b | 15d9:070a | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 1F3561AA7D |
| 8086:1d6b | 17aa:1027 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | E3C6A7B793 |
| 1000:005d | 1000:9a63 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | megarai... | 8EFAF14886 |
| 1000:005d | 8086:3a1e | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | megarai... | 98C12554CB |
| 1000:0064 | 1000:3030 | Broadco... | SAS2116 PCI-Express Fusio... | 1     | mpt3sas    | 32951A000F |
| 1000:0064 | 15d9:083c | LSI Log... | SAS2116 PCI-Express Fusio... | 1     | mpt3sas    | DB25C87154 |
| 1000:0070 | 1014:03f7 | LSI Log... | SAS2004 PCI-Express Fusio... | 1     | mpt2sas    | D7CBC31CEE |
| 1000:0070 | 1014:03f8 | Broadco... | SAS2004 PCI-Express Fusio... | 1     | mpt2sas    | 7C109612B9 |
| 1000:0072 | 1000:3050 | LSI Log... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | 0B2E10175B |
| 1000:0072 | 1000:3080 | LSI Log... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | FFC0ECBF18 |
| 1000:0072 | 1000:30b0 | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | 9BF79EF1CD |
| 1000:0072 | 1014:03cb | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | 2B9980B42B |
| 1000:007e | 1000:0507 | Broadco... | SSS6200 PCI-Express Flash... | 1     | mpt3sas    | BA4FFBDA6D |
| 1000:0086 | 1000:0086 | LSI Log... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | C0122E3715 |
| 1000:0087 | 1000:0087 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | BA0F3C3B41 |
| 1000:0087 | 1590:0041 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | E106326D63 |
| 1000:0087 | 1590:0042 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | A14015F487 |
| 1000:0087 | 1590:0043 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | AB5267E214 |
| 1000:0087 | 8086:3060 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | F2B18DC242 |
| 1000:0087 | 8086:3519 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | FBDCC4D1F5 |
| 1000:0097 | 1849:0097 | Broadco... | SAS3008 PCI-Express Fusio... | 1     | mpt3sas    | FA8D061F8F |
| 1000:00ac | 1000:3000 | Broadco... | SAS3416 Fusion-MPT Tri-Mo... | 1     | mpt3sas    | 8C80B197C2 |
| 1000:00c4 | 1000:3190 | Broadco... | SAS3224 PCI-Express Fusio... | 1     | mpt3sas    | 00FDD71981 |
| 117c:0042 | 117c:0042 | ATTO Te... | ExpressSAS 6Gb/s SAS/SATA... | 1     | pm80xx     | 2DF53AC534 |
| 11f8:8001 |           | PMC-Sierra | SPC 8x6G SAS/SATA (storport) | 1     | pm80xx     | 4F5756D065 |
| 8086:1d60 | 1028:0496 | Intel      | C608 chipset Dual 4-Port ... | 1     | isci       | 1518FF90F9 |
| 8086:1d68 | 15d9:0628 | Intel      | C606 chipset Dual 4-Port ... | 1     | isci       | 74EFA61302 |
| 8086:1d68 | 15d9:0630 | Intel      | C606 chipset Dual 4-Port ... | 1     | isci       | 575A60EDC8 |
| 8086:1d68 | 8086:1d68 | Intel      | C606 chipset Dual 4-Port ... | 1     | isci       | EBA3BBC86D |
| 8086:1d69 | 15d9:0706 | Intel      | C604/X79 series chipset 4... | 1     | isci       | AA3D8595BA |
| 8086:1d69 | 17aa:1026 | Intel      | C604/X79 series chipset 4... | 1     | isci       | 7EB1F254C9 |
| 8086:1d69 | 8086:1d69 | Intel      | C604/X79 series chipset 4... | 1     | isci       | 53874D702A |
| 8086:1d6a | 8086:3583 | Intel      | C600/X79 series chipset D... | 1     | isci       | 9F6D925B73 |
| 8086:1d6b |           | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 99E743CA9E |
| 8086:1d6b | 1014:0432 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | FC0558920D |
| 8086:1d6b | 15d9:0628 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | F7519BF7BE |
| 8086:1d6b | 15d9:062a | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 2E139151DE |
| 8086:1d6b | 15d9:062b | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | A897C366A9 |
| 8086:1d6b | 15d9:062f | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | F5F0A90676 |
| 8086:1d6b | 15d9:0665 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | CEC82EF5D0 |
| 8086:1d6b | 15d9:0667 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 8FDC5D8AB4 |
| 8086:1d6b | 15d9:066b | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 1FF0EE8759 |
| 8086:1d6b | 15d9:0703 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 8C793BB137 |
| 8086:1d6b | 15d9:0705 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | B3D08DD227 |
| 8086:1d6b | 8086:357f | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 7DC714253B |
| 8086:1d6b | 8086:358d | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | D15B8F8758 |
| 8086:1d6b | 8086:3595 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 91F3C901D3 |
| 8086:1d6b | 8086:35b1 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 30CFD7BC18 |
| 8086:1d6d | 1734:11b6 | Intel      | C600/X79 series chipset 4... | 1     |            | 9C16958A72 |
| 8086:1d6f | 8086:3595 | Intel      | C600/X79 series chipset 4... | 1     |            | FBDCC4D1F5 |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1000:0058 | 1028:021d | LSI Log... | SAS1068E PCI-Express Fusi... | 23    | mptsas     | 0BA08ED8F7 |
| 1000:0058 | 103c:130b | LSI Log... | SAS1068E PCI-Express Fusi... | 18    | mptsas     | DFA7EF3696 |
| 1000:0058 | 1028:1f0e | LSI Log... | SAS1068E PCI-Express Fusi... | 14    | mptsas     | 4DEBADA4BF |
| 1000:0056 | 1000:3090 | LSI Log... | SAS1064ET PCI-Express Fus... | 11    | mptsas     | 08F4C825CC |
| 9004:5078 | 9004:7850 | Adaptec    | AIC-7850T/7856T [AVA-2902... | 10    | aic7xxx    | 97C7481343 |
| 9004:7178 |           | Adaptec    | AIC-7870P/7871 [AHA-2940/... | 8     | aic7xxx    | BDB612797A |
| 1000:0054 | 103c:0a98 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 7     | mptsas     | FC2E31C91F |
| 1000:0056 | 1014:03bb | LSI Log... | SAS1064ET PCI-Express Fus... | 6     | mptsas     | 882EA8E25E |
| 1000:0058 | 1028:1f10 | Broadco... | SAS1068E PCI-Express Fusi... | 6     | mptsas     | 5FBC90E0CD |
| 9004:8178 |           | Adaptec    | AIC-7870P/7881U [AHA-2940... | 6     | aic7xxx    | E4B76F9137 |
| 1000:0058 | 1028:1f0f | LSI Log... | SAS1068E PCI-Express Fusi... | 5     | mptsas     | 5136C6B827 |
| 1b85:1021 | 1b85:1021 | OCZ Tec... | OCZ SCSI storage controller  | 5     | mvsas      | 71E296F6E0 |
| 9004:8178 | 9004:7881 | Adaptec    | AIC-7870P/7881U [AHA-2940... | 5     | aic7xxx    | 4C68880898 |
| 9005:8017 | 9005:0045 | Adaptec    | ASC-29320ALP U320            | 5     | aic79xx    | BB541DFDE4 |
| 1000:0050 | 103c:3015 | Broadco... | SAS1064 PCI-X Fusion-MPT SAS | 4     | mptsas     | C20157D427 |
| 1de1:0391 | 1de1:0391 | Tekram ... | TRM-S1040 [DC-315 / DC-39... | 4     | dc395x     | 510A70AB34 |
| 1000:0001 |           | LSI Log... | 53c810                       | 3     | sym53c8xx  | 608EBB649B |
| 1000:0030 | 1000:50c0 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 3     | mptspi     | 6127AF92BC |
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
| 1000:0030 | 103c:322a | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 2     | mptspi     | C156F0AB27 |
| 1000:0056 | 8086:3486 | Broadco... | SAS1064ET PCI-Express Fus... | 2     | mptsas     | 7E72574FF4 |
| 1000:0058 | 1014:0394 | LSI Log... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | 5C4A86988B |
| 1000:0058 | 1014:0396 | Broadco... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | E4B76F9137 |
| 1000:0058 | 15d9:0001 | Broadco... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | F645C4227C |
| 1000:0058 | 1734:1130 | Broadco... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | 2A000E48F4 |
| 1b85:1041 | 1b85:1041 | OCZ Tec... | RevoDrive 3 X2 PCI-Expres... | 2     | mvsas      | E0FC243F47 |
| 9005:0010 | 9005:2180 | Adaptec    | AHA-2940U2/U2W               | 2     | aic7xxx    | 67C4745D3A |
| 9005:8012 | 9005:0042 | Adaptec    | ASC-29320 U320               | 2     | aic79xx    | 5923C246C4 |
| 9005:8017 | 9005:0044 | Adaptec    | ASC-29320ALP U320            | 2     | aic79xx    | 7483894658 |
| 1000:000f | 0e11:7004 | Broadco... | 53c875                       | 1     | sym53c8xx  | AFF808A68F |
| 1000:0030 | 0e11:00f4 | Broadco... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 72330BE67D |
| 1000:0030 | 1014:026c | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 46973B5B05 |
| 1000:0030 | 1014:1000 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 659D759E6D |
| 1000:0030 | 1028:012c | Broadco... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 90378ABAC3 |
| 1000:0030 | 1028:016e | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 76EF1C8CA9 |
| 1000:0030 | 1028:1040 | Broadco... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | D83C8DDEDF |
| 1000:0030 | 103c:3108 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | A2995F5723 |
| 1000:0054 | 1028:1f09 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | 4FDE34B201 |
| 1000:0054 | 103c:3228 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | B4F5FF56BD |
| 1000:0054 | 1734:10b9 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | A0F9679F57 |
| 1000:0054 | 8086:3504 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | A61FFACB08 |
| 1000:0056 | 103c:322b | LSI Log... | SAS1064ET PCI-Express Fus... | 1     | mptsas     | 7FE1A5394C |
| 1000:0056 | 1734:1131 | Broadco... | SAS1064ET PCI-Express Fus... | 1     | mptsas     | 4E888D4C51 |
| 1000:0056 | 8086:346c | Broadco... | SAS1064ET PCI-Express Fus... | 1     | mptsas     | 390F15B7F9 |
| 1000:0058 | 1000:3002 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | 1E88FE8CBB |
| 1000:0058 | 1000:30a0 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | E5AEAF13AE |
| 1000:0058 | 1000:3140 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | FB13D939DA |
| 1000:0058 | 1000:3150 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | 8F6E544820 |
| 1000:0058 | 10f1:2918 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | 032066549F |
| 1000:0058 | 1734:115a | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | AD12D1E2B9 |
| 1000:0058 | 17aa:101d | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | 18BE0454DD |
| 1000:0059 | 1000:3002 | LSI Log... | MegaRAID SAS 8208ELP/8208ELP | 1     | mptsas     | 2985792735 |
| 1000:0059 | 15d9:0006 | Broadco... | MegaRAID SAS 8208ELP/8208ELP | 1     | mptsas     | 8F945E0A15 |
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
| 9005:801f | 8086:341a | Adaptec    | AIC-7902 U320                | 1     | aic79xx    | 37AA8C0E8E |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:d150 |           | Intel      | Core Processor QPI Link      | 502   |            | 5EBB861FEB |
| 8086:d151 |           | Intel      | Core Processor QPI Routin... | 502   |            | 5EBB861FEB |
| 8086:d158 |           | Intel      | Core Processor Miscellane... | 474   |            | 5EBB861FEB |
| 14e4:16be | 1025:0647 | Broadcom   | BCM57765/57785 MS Card Re... | 377   |            | B732F94275 |
| 14e4:16bf | 1025:0647 | Broadcom   | BCM57765/57785 xD-Picture... | 377   |            | B732F94275 |
| 8086:2f6e |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 369   |            | F90168C69D |
| 8086:2f6f |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 369   |            | F90168C69D |
| 8086:2f88 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 369   |            | F90168C69D |
| 8086:2f8a |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 369   |            | F90168C69D |
| 8086:2fae |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 369   |            | F90168C69D |
| 8086:2faf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 369   |            | F90168C69D |
| 8086:2fb8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 369   |            | F90168C69D |
| 8086:2fb9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 369   |            | F90168C69D |
| 8086:2fba |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 369   |            | F90168C69D |
| 8086:2fbb |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 369   |            | F90168C69D |
| 8086:2fbe |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 369   |            | F90168C69D |
| 8086:2fbf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 369   |            | F90168C69D |
| 8086:2ff8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 369   |            | F90168C69D |
| 8086:2ff9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 369   |            | F90168C69D |
| 8086:1911 | 1458:5000 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 349   |            | F91A20DD51 |
| 8086:d156 |           | Intel      | Core Processor Semaphore ... | 341   |            | 5EBB861FEB |
| 8086:d155 |           | Intel      | Core Processor System Man... | 335   |            | 5EBB861FEB |
| 8086:d157 |           | Intel      | Core Processor System Con... | 335   |            | 5EBB861FEB |
| 8086:2f1d | 8086:2f1d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 324   |            | F90168C69D |
| 8086:2f1e | 8086:2f1e | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 324   |            | F90168C69D |
| 8086:2f1f | 8086:2f1f | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 324   |            | F90168C69D |
| 8086:2f71 | 8086:2f71 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 324   |            | F90168C69D |
| 8086:2f98 | 8086:2f98 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 324   |            | F90168C69D |
| 8086:2f99 | 8086:2f99 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 324   |            | F90168C69D |
| 8086:2f9a | 8086:2f9a | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 324   |            | F90168C69D |
| 8086:2f9c | 8086:2f9c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 324   |            | F90168C69D |
| 8086:2fa0 | 8086:2fa0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 324   | sb_edac    | F90168C69D |
| 8086:2fa8 | 8086:2fa8 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 324   |            | F90168C69D |
| 8086:2faa | 8086:2faa | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 324   |            | F90168C69D |
| 8086:2fab | 8086:2fab | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 324   |            | F90168C69D |
| 8086:2fb0 | 8086:2fb0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 324   | hswep_u... | F90168C69D |
| 8086:2fb1 | 8086:2fb1 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 324   | hswep_u... | F90168C69D |
| 8086:2fb2 | 8086:2fb2 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 324   |            | F90168C69D |
| 8086:2fb3 | 8086:2fb3 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 324   |            | F90168C69D |
| 8086:2fc0 | 8086:2fc0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 324   | hswep_u... | F90168C69D |
| 8086:1513 | 2222:1111 | Intel      | CV82524 Thunderbolt Contr... | 319   | thunder... | 7EBB0672C0 |
| 8086:2f81 | 8086:2f81 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 293   |            | F90168C69D |
| 8086:2fe0 | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 293   |            | F90168C69D |
| 8086:2fe1 | 8086:2fe1 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 293   |            | F90168C69D |
| 8086:2fe2 | 8086:2fe2 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 293   |            | F90168C69D |
| 8086:2fe3 | 8086:2fe3 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 293   |            | F90168C69D |
| 8086:2ffc | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 293   |            | F90168C69D |
| 8086:2ffd | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 293   |            | F90168C69D |
| 8086:2ffe | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 293   |            | F90168C69D |
| 8086:2fbc |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 286   |            | F90168C69D |
| 8086:2fbd |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 286   |            | F90168C69D |
| 8086:2f68 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 278   |            | C050F79E2B |
| 8086:2fd0 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 278   | hswep_u... | C050F79E2B |
| 8086:2fe4 | 8086:2fe4 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 260   |            | F90168C69D |
| 8086:2fe5 | 8086:2fe5 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 260   |            | F90168C69D |
| 8086:2576 |           | Intel      | 82865G/PE/P Processor to ... | 247   |            | 52C3157C62 |
| 8086:2fac | 8086:2fac | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 247   |            | C050F79E2B |
| 8086:2fad | 8086:2fad | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 247   |            | C050F79E2B |
| 8086:2fb4 | 8086:2fb4 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 247   | hswep_u... | C050F79E2B |
| 8086:2fb5 | 8086:2fb5 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 247   | hswep_u... | C050F79E2B |
| 8086:2fb6 | 8086:2fb6 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 247   |            | C050F79E2B |
| 8086:2fb7 | 8086:2fb7 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 247   |            | C050F79E2B |
| 1180:e822 | 17aa:2133 | Ricoh      | MMC/SD Host Controller       | 236   | sdhci_pci  | 5DC4A1E557 |
| 197b:2382 | 1043:1a07 | JMicron... | SD/MMC Host Controller       | 219   | sdhci_pci  | 11F1CDC49A |
| 8086:2f28 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 206   |            | F90168C69D |
| 8086:2f29 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 206   |            | F90168C69D |
| 8086:2f2a |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 206   |            | F90168C69D |
| 14e4:16be | 1025:0504 | Broadcom   | BCM57765/57785 MS Card Re... | 196   |            | 85BCF858C5 |
| 14e4:16bf | 1025:0504 | Broadcom   | BCM57765/57785 xD-Picture... | 196   |            | 85BCF858C5 |
| 8086:1911 | 8086:2015 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 193   |            | 047EAD1D70 |
| 8086:2035 |           | Intel      | Sky Lake-E RAS Configurat... | 193   |            | 862B2D2013 |
| 8086:2025 |           | Intel      | Sky Lake-E RAS               | 192   |            | 862B2D2013 |
| 197b:2383 | 1043:1a07 | JMicron... | MS Host Controller           | 189   | jmb38x_ms  | 11F1CDC49A |
| 197b:2384 | 1043:1a07 | JMicron... | xD Host Controller           | 187   |            | 11F1CDC49A |
| 8086:204e | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 179   | skx_uncore | 2D1D9030E8 |
| 8086:2018 | 8086:0000 | Intel      | Sky Lake-E M2PCI Registers   | 176   |            | 2D1D9030E8 |
| 8086:2040 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 176   |            | 2D1D9030E8 |
| 8086:2041 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 176   |            | 2D1D9030E8 |
| 8086:2042 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 176   | skx_uncore | 2D1D9030E8 |
| 8086:2043 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 176   |            | 2D1D9030E8 |
| 8086:2044 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 176   |            | 2D1D9030E8 |
| 8086:2045 | 8086:0000 | Intel      | Sky Lake-E LM Channel 1      | 176   |            | 2D1D9030E8 |
| 8086:2046 | 8086:0000 | Intel      | Sky Lake-E LMS Channel 1     | 176   | skx_uncore | 2D1D9030E8 |
| 8086:2047 | 8086:0000 | Intel      | Sky Lake-E LMDP Channel 1    | 176   |            | 2D1D9030E8 |
| 8086:2048 | 8086:0000 | Intel      | Sky Lake-E DECS Channel 2    | 176   |            | 2D1D9030E8 |
| 8086:2049 | 8086:0000 | Intel      | Sky Lake-E LM Channel 2      | 176   |            | 2D1D9030E8 |
| 8086:204a | 8086:0000 | Intel      | Sky Lake-E LMS Channel 2     | 176   | skx_uncore | 2D1D9030E8 |
| 8086:204b | 8086:0000 | Intel      | Sky Lake-E LMDP Channel 2    | 176   |            | 2D1D9030E8 |
| 8086:2054 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 176   |            | 2D1D9030E8 |
| 8086:2055 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 176   |            | 2D1D9030E8 |
| 8086:2056 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 176   |            | 2D1D9030E8 |
| 8086:2057 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 176   |            | 2D1D9030E8 |
| 8086:2066 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 176   | skx_uncore | 2D1D9030E8 |
| 8086:2080 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 176   |            | 2D1D9030E8 |
| 8086:2081 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 176   |            | 2D1D9030E8 |
| 8086:2082 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 176   |            | 2D1D9030E8 |
| 8086:2083 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 176   |            | 2D1D9030E8 |
| 8086:2084 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 176   |            | 2D1D9030E8 |
| 8086:2085 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 176   |            | 2D1D9030E8 |
| 8086:2086 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 176   |            | 2D1D9030E8 |

### Tv card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 109e:036e |           | Brooktree  | Bt878 Video Capture          | 25    | bttv       | E739F2F0BA |
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
| 1131:7133 | 1461:a836 | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 14C016A2F9 |
| 1131:7133 | 1461:e836 | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 6D72715029 |
| 1131:7133 | 1461:f11d | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 4C528F55F3 |
| 1131:7134 | 16be:0003 | Philips... | SAA7134/SAA7135HL Video B... | 7     | saa7134    | F5D9A3BA0E |
| 14f1:5b7a | 0070:7400 | Conexan... | CX23418 Single-Chip MPEG-... | 7     | cx18       | 925EDCDDDC |
| 14f1:8800 | 107d:6611 | Conexan... | CX23880/1/2/3 PCI Video a... | 7     | cx8800     | ACE5E495F5 |
| 14f1:8852 | 0070:6a28 | Conexan... | CX23885 PCI Video and Aud... | 7     | cx23885    | 517C6137A3 |
| 14f1:8852 | 0070:6b28 | Conexan... | CX23885 PCI Video and Aud... | 7     | cx23885    | 517C6137A3 |
| 14f1:8880 | 1461:d439 | Conexan... | CX23887/8 PCIe Broadcast ... | 7     | cx23885    | D8325626F2 |
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
| 109e:036e | 107d:6606 | Brooktree  | Bt878 Video Capture          | 5     | bttv       | 90F950C23B |
| 109e:036e | 11bd:0012 | Brooktree  | Bt878 Video Capture          | 5     | bttv       | 237CA98302 |
| 109e:036e | 1822:0001 | Brooktree  | Bt878 Video Capture          | 5     | bttv       | 39FB7FBFDD |
| 1131:7130 | 0000:4051 | Philips... | SAA7130 Video Broadcast D... | 5     | saa7134    | 1ABE742CC8 |
| 1131:7133 | 1043:4845 | Philips... | SAA7131/SAA7133/SAA7135 V... | 5     | saa7134    | D288F0A8CD |
| 1131:7133 | 1461:f636 | Philips... | SAA7131/SAA7133/SAA7135 V... | 5     | saa7134    | 4A92B26339 |
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
| 109e:036e | 800a:763d | Brooktree  | Bt878 Video Capture          | 3     | bttv       | 7E72574FF4 |

### Unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:31a2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 7     | intel_i... | 1A6758A371 |
| 8086:5aa2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 7     | intel_i... | 7C30C0C3CA |
| 8086:5aa2 | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 5     | intel_i... | 98851C034C |
| 8086:31a2 | 1028:081f | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_i... | 582965792D |
| 8086:31a2 | 17aa:3801 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_i... | 3E9117AA42 |
| 8086:31a2 | 17aa:3806 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_i... | EDA2FBC232 |
| 8086:5aa2 | 103c:830d | Intel      | Celeron N3350/Pentium N42... | 2     | intel_i... | 27DC03B58E |
| 8086:5aa2 | 1043:1d90 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_i... | C8D3F204E5 |
| 1217:6120 | 0001:0000 | O2 Micro   |                              | 1     |            | B851103D78 |
| 13fe:1716 | 13fe:0001 | Advantech  |                              | 1     |            | 047EAD1D70 |
| 1684:0029 | 0008:0000 |            |                              | 1     |            | 3A2604A18A |
| 8086:1aa2 | 8086:7270 | Intel      | Integrated Sensor Solution   | 1     | intel_i... | 555A26F0D1 |
| 8086:31a2 | 103c:84fa | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_i... | 345648FE18 |
| 8086:31a2 | 103c:85ca | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_i... | 363C54D31F |
| 8086:31a2 | 103c:86cf | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_i... | 33D5688BFC |
| 8086:5aa2 |           | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | 49D345EC0B |
| 8086:5aa2 | 1043:1930 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | B6FC10EFA8 |
| 8086:5aa2 | 1043:1d60 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | 45B1907784 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:43d5 | 1b21:1142 | AMD        | 400 Series Chipset USB 3.... | 1511  | xhci_hcd   | B8D0E81636 |
| 1002:4397 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1331  | ohci_pci   | 77FCB9CF4A |
| 1002:4399 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1331  | ohci_pci   | 77FCB9CF4A |
| 1002:4396 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 1330  | ehci_pci   | 77FCB9CF4A |
| 1b21:1042 | 1043:8488 | ASMedia... | ASM1042 SuperSpeed USB Ho... | 1256  | xhci_hcd   | BA117FEF7E |
| 1002:4396 | 1002:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 1115  | ehci_pci   | 9F527DED3C |
| 1022:149c | 1022:148c | AMD        | Matisse USB 3.0 Host Cont... | 1096  | xhci_hcd   | 0619809B36 |
| 8086:1c26 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1017  | ehci_pci   | EA164260EB |
| 8086:1c2d | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1017  | ehci_pci   | EA164260EB |
| 8086:27c8 | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 1001  | uhci_hcd   | 5889B752F5 |
| 8086:27c9 | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 1001  | uhci_hcd   | 5889B752F5 |
| 8086:27ca | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 1000  | uhci_hcd   | 5889B752F5 |
| 8086:27cb | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 999   | uhci_hcd   | 5889B752F5 |
| 8086:27cc | 1043:8179 | Intel      | NM10/ICH7 Family USB2 EHC... | 985   | ehci_hc... | 5889B752F5 |
| 1106:3483 | 1106:3483 | VIA Tec... | VL805/806 xHCI USB 3.0 Co... | 925   | xhci_hcd   | 2C283A99A8 |
| 1002:4397 | 1002:4397 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 921   | ohci_pci   | 9F527DED3C |
| 8086:9d2f | 1043:201f | Intel      | Sunrise Point-LP USB 3.0 ... | 835   | xhci_hcd   | AF70469300 |
| 1002:4399 | 1002:4399 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 798   | ohci_pci   | 9F527DED3C |
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
| 8086:1e26 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 708   | ehci_pci   | BA117FEF7E |
| 8086:1e2d | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 708   | ehci_pci   | BA117FEF7E |
| 8086:1e31 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 701   | xhci_hcd   | BA117FEF7E |
| 1002:4398 | 1458:5004 | AMD        | SB7x0 USB OHCI1 Controller   | 700   | ohci_pci   | 765CD8D9A0 |
| 1b21:1142 | 1043:85bf | ASMedia... | ASM1042A USB 3.0 Host Con... | 692   | xhci_hcd   | 9F527DED3C |
| 1022:149c | 1043:87c0 | AMD        | Matisse USB 3.0 Host Cont... | 666   | xhci_hcd   | 97C17F738A |
| 1022:149c | 1022:1486 | AMD        | Matisse USB 3.0 Host Cont... | 645   | xhci_hcd   | 0619809B36 |
| 8086:a12f | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 644   | xhci_hcd   | 11EBF0D551 |
| 8086:1c26 | 1458:5006 | Intel      | 6 Series/C200 Series Chip... | 632   | ehci_pci   | EE570B7B0C |
| 8086:1c2d | 1458:5006 | Intel      | 6 Series/C200 Series Chip... | 632   | ehci_pci   | EE570B7B0C |
| 1022:43bb | 1b21:1142 | AMD        | 300 Series Chipset USB 3.... | 613   | xhci_hcd   | 52C67D407D |
| 8086:3a34 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 601   | uhci_hcd   | 2E1659CD91 |
| 8086:3a35 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 601   | uhci_hcd   | 2E1659CD91 |
| 8086:3a36 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 601   | uhci_hcd   | 2E1659CD91 |
| 8086:3a37 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 601   | uhci_hcd   | 2E1659CD91 |
| 8086:3a38 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 601   | uhci_hcd   | 2E1659CD91 |
| 8086:3a39 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 601   | uhci_hcd   | 2E1659CD91 |
| 8086:3a3a | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 601   | ehci_hc... | 2E1659CD91 |
| 8086:3a3c | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 601   | ehci_hc... | 2E1659CD91 |
| 8086:22b5 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 598   | xhci_hcd   | 1B5E908CFF |
| 8086:1e26 | 1458:5006 | Intel      | 7 Series/C216 Chipset Fam... | 532   | ehci_pci   | 89F6EB0671 |
| 8086:1e2d | 1458:5006 | Intel      | 7 Series/C216 Chipset Fam... | 531   | ehci_pci   | 89F6EB0671 |
| 1b6f:7023 | 1458:5007 | Etron T... | EJ168 USB 3.0 Host Contro... | 523   | xhci_hcd   | 77FCB9CF4A |
| 1b21:1242 | 1043:8675 | ASMedia... | ASM1142 USB 3.1 Host Cont... | 522   | xhci_hcd   | 97C17F738A |
| 8086:1e26 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 515   | ehci_hc... | 5872E567EC |
| 8086:1e2d | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 515   | ehci_hc... | 5872E567EC |
| 1022:43bc | 1b21:1142 | AMD        | FCH USB 3.1 XHCI Host Con... | 510   | xhci_hcd   | 4654691B7A |
| 8086:8c26 | 1458:5006 | Intel      | 8 Series/C220 Series Chip... | 508   | ehci_pci   | E187B3F207 |
| 8086:8c2d | 1458:5006 | Intel      | 8 Series/C220 Series Chip... | 508   | ehci_pci   | E187B3F207 |
| 8086:8c31 | 1458:5007 | Intel      | 8 Series/C220 Series Chip... | 506   | xhci_hcd   | E187B3F207 |
| 8086:1e31 | 17aa:3977 | Intel      | 7 Series/C210 Series Chip... | 505   | xhci_hcd   | 5872E567EC |
| 1106:3483 | 1458:5007 | VIA Tec... | VL805/806 xHCI USB 3.0 Co... | 502   | xhci_hcd   | 84D927D279 |
| 8086:1e31 | 1458:5007 | Intel      | 7 Series/C210 Series Chip... | 497   | xhci_hcd   | 89F6EB0671 |
| 1002:4396 | 1849:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 495   | ehci_pci   | 0A228B18C1 |
| 1002:4397 | 1849:4397 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 495   | ohci_pci   | 0A228B18C1 |
| 1002:4399 | 1849:4399 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 495   | ohci_pci   | 0A228B18C1 |
| 1022:149c | 1458:5007 | AMD        | Matisse USB 3.0 Host Cont... | 484   | xhci_hcd   | 06BB083E38 |
| 8086:27c8 | 1849:27c8 | Intel      | NM10/ICH7 Family USB UHCI... | 445   | uhci_hcd   | 87C40FCD51 |
| 8086:27c9 | 1849:27c9 | Intel      | NM10/ICH7 Family USB UHCI... | 445   | uhci_hcd   | 87C40FCD51 |
| 8086:27ca | 1849:27ca | Intel      | NM10/ICH7 Family USB UHCI... | 445   | uhci_hcd   | 87C40FCD51 |
| 8086:27cb | 1849:27cb | Intel      | NM10/ICH7 Family USB UHCI... | 445   | uhci_hcd   | 87C40FCD51 |
| 8086:27cc | 1849:27cc | Intel      | NM10/ICH7 Family USB2 EHC... | 444   | ehci_hc... | 87C40FCD51 |
| 1022:7808 | 1458:5004 | AMD        | FCH USB EHCI Controller      | 430   | ehci_pci   | E03FD39AD4 |
| 1022:7807 | 1458:5004 | AMD        | FCH USB OHCI Controller      | 426   | ohci_pci   | E03FD39AD4 |
| 1106:3038 | 1106:3038 | VIA Tec... | VT82xx/62xx/VX700/8x0/900... | 421   | uhci_hcd   | 15268C0CCC |
| 1022:43ee | 1b21:1142 | AMD        | Starship/Matisse USB 3.0 ... | 416   | xhci_hcd   | A82D785D77 |
| 1033:0194 | 1043:8413 | NEC Com... | uPD720200 USB 3.0 Host Co... | 412   | xhci_hcd   | 67B53F9BDB |
| 1022:7809 | 1458:5004 | AMD        | FCH USB OHCI Controller      | 405   | ohci_pci   | E03FD39AD4 |
| 1106:3104 | 1106:3104 | VIA Tec... | USB 2.0 EHCI-Compliant Ho... | 403   | ehci_pci   | 15268C0CCC |
| 10de:03f1 | 1849:03f1 | Nvidia     | MCP61 USB 1.1 Controller     | 397   | ohci_pci   | 615502E93E |
| 10de:03f2 | 1849:03f2 | Nvidia     | MCP61 USB 2.0 Controller     | 397   | ehci_pci   | 615502E93E |
| 8086:a2af | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 392   | xhci_hcd   | 2696477C0C |
| 1022:43d0 | 1b21:1142 | AMD        | FCH USB 3.1 XHCI Host Con... | 383   | xhci_hcd   | 97C17F738A |
| 1022:145f | 1043:8747 | AMD        | Zeppelin USB 3.0 Host con... | 380   | xhci_hcd   | 115EC5ECA4 |
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
| 1022:145c | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 346   | xhci_hcd   | DFE212DA86 |
| 1022:43b9 | 1b21:1142 | AMD        | X370 Series Chipset USB 3... | 340   | xhci_hcd   | F544511E0A |
| 1022:7807 | 1849:7807 | AMD        | FCH USB OHCI Controller      | 332   | ohci_pci   | 3D65247771 |
| 1022:7808 | 1849:7808 | AMD        | FCH USB EHCI Controller      | 332   | ehci_pci   | 3D65247771 |
| 1022:145f | 1458:5007 | AMD        | Zeppelin USB 3.0 Host con... | 315   | xhci_hcd   | D88D9DB618 |
| 1022:7809 | 1849:7809 | AMD        | FCH USB OHCI Controller      | 304   | ohci_hc... | 3D65247771 |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8d7c | 1043:8600 | Intel      | C610/X99 series chipset SPSR | 96    |            | E456864B06 |
| 8086:8d7c | 8086:7270 | Intel      | C610/X99 series chipset SPSR | 63    |            | B92F4485E6 |
| 8086:8d7c | 1849:8d7c | Intel      | C610/X99 series chipset SPSR | 38    |            | 6FEB0AEC47 |
| 8086:8d7c | 1458:7270 | Intel      | C610/X99 series chipset SPSR | 37    |            | 0C74B85F4C |
| 8086:8d7c | 1462:7885 | Intel      | C610/X99 series chipset SPSR | 31    |            | 09B0FBCF47 |
| 8086:8d7c | 1028:0617 | Intel      | C610/X99 series chipset SPSR | 26    |            | 3440F55127 |
| 8086:8d7c | 103c:212b | Intel      | C610/X99 series chipset SPSR | 26    |            | 69F0D916A3 |
| 10ec:816e | 10ec:8168 | Realtek... | RealManage BMC               | 23    |            | 0E48C94F83 |
| 8086:8d7c | 1043:85f6 | Intel      | C610/X99 series chipset SPSR | 20    |            | 4158CB76EF |
| 8086:8d7c | 15d9:0821 | Intel      | C610/X99 series chipset SPSR | 16    |            | 17BF7A3CBC |
| 8086:a1ec | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    |            | 4391DFF8D2 |
| 8086:a1ec | 8086:7270 | Intel      | C620 Series Chipset Famil... | 14    |            | FD087082C0 |
| 1af2:a001 | 1af2:a001 | AVerMedia  | Live Gamer HD                | 13    |            | 8FFB0CF94A |
| 8086:a1ed | 8086:7270 | Intel      | C620 Series Chipset Famil... | 12    |            | FD087082C0 |
| 8086:8d7c | 1028:0618 | Intel      | C610/X99 series chipset SPSR | 11    |            | 7172CF4F40 |
| 8086:8d7c | 103c:8030 | Intel      | C610/X99 series chipset SPSR | 11    |            | 23F12250E5 |
| 8086:8d7c | 103c:2129 | Intel      | C610/X99 series chipset SPSR | 8     |            | 3991895525 |
| 8086:8d7c | 15d9:0857 | Intel      | C610/X99 series chipset SPSR | 8     |            | 7CF4F8ED17 |
| 8086:8d7c | 8086:0000 | Intel      | C610/X99 series chipset SPSR | 8     |            | BA0F3C3B41 |
| 8086:a1ec | 1043:871e | Intel      | C620 Series Chipset Famil... | 8     |            | 177BF1F346 |
| 8086:8d7c | 1028:061b | Intel      | C610/X99 series chipset SPSR | 7     |            | BCD33A41F0 |
| 8086:a1ec | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     |            | CEE7ED2CE9 |
| 1002:6900 | 03ea:1af4 | AMD        | Topaz XT [Radeon R7 M260/... | 6     | amdgpu     | B48E22AF4A |
| 8086:8d7c | 1028:0601 | Intel      | C610/X99 series chipset SPSR | 6     |            | F90168C69D |
| 8086:8d7c | 1028:064c | Intel      | C610/X99 series chipset SPSR | 6     |            | E31C5F36AA |
| 8086:8d7c | 1028:0619 | Intel      | C610/X99 series chipset SPSR | 5     |            | F96F352657 |
| 8086:8d7c | 15d9:0831 | Intel      | C610/X99 series chipset SPSR | 5     |            | 64918C950D |
| 8086:8d7c | 1734:1201 | Intel      | C610/X99 series chipset SPSR | 5     |            | 081130AC6F |
| 8086:8d7c | 17aa:102f | Intel      | C610/X99 series chipset SPSR | 5     |            | 4860ACD042 |
| 8086:a1ec | 1028:0739 | Intel      | C620 Series Chipset Famil... | 5     |            | 2D1D9030E8 |
| 8086:a1ec | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 5     |            | 0C434691D6 |
| 8086:a1ec | 1590:00eb | Intel      | C620 Series Chipset Famil... | 5     |            | 3120E02C21 |
| 8086:a1ed | 1028:0739 | Intel      | C620 Series Chipset Famil... | 5     |            | 2D1D9030E8 |
| 8086:a1ed | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 5     |            | 0C434691D6 |
| 8086:a1ed | 1590:00eb | Intel      | C620 Series Chipset Famil... | 5     |            | 3120E02C21 |
| 8086:8d7c | 15d9:0834 | Intel      | C610/X99 series chipset SPSR | 4     |            | 72BAE0BDE8 |
| 8086:8d7c | 15d9:0836 | Intel      | C610/X99 series chipset SPSR | 4     |            | 3EFBED680C |
| 8086:a1ec | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     |            | E9A1FC86F9 |
| 8086:a1ec | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 4     |            | 7AD1F5EB4E |
| 8086:a1ec | 15d9:096d | Intel      | C620 Series Chipset Famil... | 4     |            | F9D0B2BC99 |
| 8086:a1ec | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 4     |            | CD543E37E2 |
| 8086:a1ed | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 4     |            | 7AD1F5EB4E |
| 8086:a1ed | 15d9:096d | Intel      | C620 Series Chipset Famil... | 4     |            | F9D0B2BC99 |
| 8086:a1ed | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 4     |            | CD543E37E2 |
| 106b:003b |           | Apple      | UniNorth/Intrepid ATA/100    | 3     | pata_pc... | 47DE429737 |
| 106b:003e |           | Apple      | KeyLargo/Intrepid Mac I/O    | 3     | macio      | 47DE429737 |
| 1912:001b | 1d49:0a02 | Renesas... | SH7758 PCIe End-Point [PBI]  | 3     |            | 3510DD7B10 |
| 1971:0000 | 105b:0003 | AGEIA T... | AGEIA PhysX 100 PCIe Card    | 3     |            | 5C4A880D42 |
| 8086:6ff2 | 8086:6ff2 | Intel      | Broadwell-E CBo Unicast R... | 3     |            | 822418675E |
| 8086:6ff3 | 8086:6ff3 | Intel      | Broadwell-E CBo Unicast R... | 3     |            | 822418675E |
| 8086:8d7c | 1028:0600 | Intel      | C610/X99 series chipset SPSR | 3     |            | A98D12AD3E |
| 8086:8d7c | 103c:212a | Intel      | C610/X99 series chipset SPSR | 3     |            | 90CE777D83 |
| 8086:8d7c | 1458:1000 | Intel      | C610/X99 series chipset SPSR | 3     |            | 2F69A2F89C |
| 8086:8d7c | 1462:7883 | Intel      | C610/X99 series chipset SPSR | 3     |            | 64A313C9E3 |
| 8086:8d7c | 1462:7a20 | Intel      | C610/X99 series chipset SPSR | 3     |            | B5DCAF3853 |
| 8086:8d7c | 1d49:0a00 | Intel      | C610/X99 series chipset SPSR | 3     |            | 3510DD7B10 |
| 8086:a1ec | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | E752263E49 |
| 8086:a1ec | 1028:073a | Intel      | C620 Series Chipset Famil... | 3     |            | 33FDE2B5FB |
| 8086:a1ec | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     |            | C682299C13 |
| 8086:a1ec | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     |            | 5658A2FB98 |
| 8086:a1ec | 1849:a1ec | Intel      | C620 Series Chipset Famil... | 3     |            | 35C171899E |
| 8086:a1ec | 8086:0000 | Intel      | C620 Series Chipset Famil... | 3     |            | D373AF93CD |
| 8086:a1ed | 1028:073a | Intel      | C620 Series Chipset Famil... | 3     |            | 33FDE2B5FB |
| 8086:a1ed | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     |            | C682299C13 |
| 8086:a1ed | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     |            | 5658A2FB98 |
| 8086:a1ed | 1849:a1ed | Intel      | C620 Series Chipset Famil... | 3     |            | 35C171899E |
| 8086:a1ed | 8086:35ce | Intel      | C620 Series Chipset Famil... | 3     |            | D373AF93CD |
| 1002:694e | 1002:694e | AMD        | Polaris 22 XL [Radeon RX ... | 2     | amdgpu     | 07A9851CD6 |
| 106b:0022 |           | Apple      | KeyLargo Mac I/O             | 2     | macio      | 23A8F5BBFB |
| 10de:0e1b | 0043:0000 | Nvidia     | GK107 HDMI Audio Controller  | 2     | snd_hda... | 17B6106770 |
| 10de:1f91 | 103c:8601 | Nvidia     | TU117M [GeForce GTX 1650 ... | 2     | nouveau    | 332EEAE951 |
| 1274:5880 | ffff:ffff | Ensoniq    | 5880B / Creative Labs CT5880 | 2     | snd_ens... | CC0925A796 |
| 8086:3591 | 1043:8145 | Intel      | E7525/E7520 Error Reporti... | 2     |            | C6EF12178F |
| 8086:6ff4 | 8086:6ff4 | Intel      | Broadwell-E CBo Unicast R... | 2     |            | 822418675E |
| 8086:6ff5 | 8086:6ff5 | Intel      | Broadwell-E CBo Unicast R... | 2     |            | 822418675E |
| 8086:8d7c | 1028:0639 | Intel      | C610/X99 series chipset SPSR | 2     |            | B39BBB71E2 |
| 8086:8d7c | 1028:063a | Intel      | C610/X99 series chipset SPSR | 2     |            | E4DEE6FAF7 |
| 8086:8d7c | 1462:7a21 | Intel      | C610/X99 series chipset SPSR | 2     |            | 6FAF6514F5 |
| 8086:8d7c | 15d9:0824 | Intel      | C610/X99 series chipset SPSR | 2     |            | 6C96E4A591 |
| 8086:8d7c | 15d9:0852 | Intel      | C610/X99 series chipset SPSR | 2     |            | 8A8EA3FF31 |
| 8086:a1ec | 1028:0718 | Intel      | C620 Series Chipset Famil... | 2     |            | 1CCB5D67C2 |
| 8086:a1ec | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     |            | DF9A63BE43 |
| 8086:a1ec | 1028:07e5 | Intel      | C620 Series Chipset Famil... | 2     |            | 4C88B2E09B |
| 8086:a1ec | 103c:81c6 | Intel      | C620 Series Chipset Famil... | 2     |            | 9D6E46ECA9 |
| 8086:a1ec | 15d9:091c | Intel      | C620 Series Chipset Famil... | 2     |            | 748FB8054B |
| 8086:a1ec | 15d9:0941 | Intel      | C620 Series Chipset Famil... | 2     |            | C619DB847B |
| 8086:a1ed | 103c:81c6 | Intel      | C620 Series Chipset Famil... | 2     |            | 9D6E46ECA9 |
| 8086:a1ed | 15d9:091c | Intel      | C620 Series Chipset Famil... | 2     |            | 748FB8054B |
| 8086:a1ed | 15d9:0941 | Intel      | C620 Series Chipset Famil... | 2     |            | C619DB847B |
| 0000:0000 | 8005:0000 |            |                              | 1     |            | 77F07D2D69 |
| 0000:0002 | 1105:8300 |            |                              | 1     |            | 3859A12973 |
| 0018:fd00 | 0115:0000 |            |                              | 1     |            | 67CBAFF497 |
| 0274:0371 | 0274:0371 |            |                              | 1     |            | E579695CC9 |
| 1000:fury | 1000:9341 | Broadco... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 64918C950D |
| 1000:fury | 1000:9343 | Broadco... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 29B0070304 |
| 1000:fury | 1014:0456 | LSI Log... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 817865DED6 |
| 1000:fury | 1028:1f44 | LSI Log... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 5B9EC879FC |
| 1000:fury | 1028:1f4b | LSI Log... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | FF3ACF2BDC |
| 102f:0181 | 102f:c600 | Toshiba... | TX4925 MIPS RISC PCI Cont... | 1     |            | 245D0631CE |
| 1045:c861 | 0045:8000 | OPTi       | 82C861 OHCI USB Host         | 1     | ohci-pci   | 806796F01E |

