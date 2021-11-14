Most popular PCI devices
========================

This is a project to identify most popular PCI devices in modern computers and
share detailed lspci reports collected by Linux users at https://linux-hardware.org.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Total reports: 211239.

Contents
--------

1. [ About ](#about)
2. [ PCI Devices ](#pci-devices)
   * [ Bluetooth ](#bluetooth-pci)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Digitizer pen ](#digitizer-pen-pci)
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
| 1814:3298 | 103c:18ec | Ralink     | RT3290 Bluetooth             | 561   | rtbth      | FBF77D8C63 |
| 1814:3298 | 105b:e056 | Ralink     | RT3290 Bluetooth             | 114   | rtbth      | D96D114426 |
| 1814:3298 | 103c:191c | Ralink     | RT3290 Bluetooth             | 28    | rtbth      | E12E55583D |
| 1814:3298 | 1a3b:2787 | Ralink     | RT3290 Bluetooth             | 14    |            | 72AA2E75FC |
| 1814:3298 | 1a3b:2f87 | Ralink     | RT3290 Bluetooth             | 14    |            | 5FAD549031 |
| 1814:3298 | 1814:3298 | Ralink     | RT3290 Bluetooth             | 6     |            | FCE7CA77F0 |
| 1814:3298 | 1a3b:2987 | Ralink     | RT3290 Bluetooth             | 6     |            | 121F403E29 |
| 1814:3298 | 10cf:1772 | Ralink     | RT3290 Bluetooth             | 1     |            | 1135E21142 |
| 1814:3298 | 1a3b:210b | Ralink     | RT3290 Bluetooth             | 1     |            | 2333E930AF |

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:4384 |           | AMD        | SBx00 PCI to PCI Bridge      | 7434  | shpchp     | CF2BC09886 |
| 1022:1452 |           | AMD        | Family 17h (Models 00h-1f... | 6064  |            | 24974BE67E |
| 1022:1200 |           | AMD        | Family 10h Processor Hype... | 4314  |            | CF2BC09886 |
| 1022:1201 |           | AMD        | Family 10h Processor Addr... | 4314  |            | CF2BC09886 |
| 1022:1202 |           | AMD        | Family 10h Processor DRAM... | 4314  | amd64_e... | CF2BC09886 |
| 1022:1203 |           | AMD        | Family 10h Processor Misc... | 4314  | k10temp    | CF2BC09886 |
| 1022:1204 |           | AMD        | Family 10h Processor Link... | 4314  |            | CF2BC09886 |
| 1022:780f |           | AMD        | FCH PCI Bridge               | 3405  | shpchp     | 42CD4D28BD |
| 1022:15e8 |           | AMD        | Raven/Raven2 Device 24: F... | 3376  |            | 24974BE67E |
| 1022:15e9 |           | AMD        | Raven/Raven2 Device 24: F... | 3376  |            | 24974BE67E |
| 1022:15ea |           | AMD        | Raven/Raven2 Device 24: F... | 3376  |            | 24974BE67E |
| 1022:15eb |           | AMD        | Raven/Raven2 Device 24: F... | 3376  | k10temp    | 24974BE67E |
| 1022:15ec |           | AMD        | Raven/Raven2 Device 24: F... | 3376  |            | 24974BE67E |
| 1022:15ed |           | AMD        | Raven/Raven2 Device 24: F... | 3376  |            | 24974BE67E |
| 1022:15ee |           | AMD        | Raven/Raven2 Device 24: F... | 3376  |            | 24974BE67E |
| 1022:15ef |           | AMD        | Raven/Raven2 Device 24: F... | 3376  |            | 24974BE67E |
| 1022:1482 |           | AMD        | Starship/Matisse PCIe Dum... | 2947  | vfio_pci   | C537345CE8 |
| 1022:1440 |           | AMD        | Matisse Device 24: Functi... | 2827  |            | C537345CE8 |
| 1022:1441 |           | AMD        | Matisse Device 24: Functi... | 2827  |            | C537345CE8 |
| 1022:1442 |           | AMD        | Matisse Device 24: Functi... | 2827  |            | C537345CE8 |
| 1022:1443 |           | AMD        | Matisse Device 24: Functi... | 2827  | k10temp    | C537345CE8 |
| 1022:1444 |           | AMD        | Matisse Device 24: Functi... | 2827  |            | C537345CE8 |
| 1022:1445 |           | AMD        | Matisse Device 24: Functi... | 2827  |            | C537345CE8 |
| 1022:1446 |           | AMD        | Matisse Device 24: Functi... | 2827  |            | C537345CE8 |
| 1022:1447 |           | AMD        | Matisse Device 24: Functi... | 2827  |            | C537345CE8 |
| 1022:1460 |           | AMD        | Family 17h (Models 00h-0f... | 2693  |            | E52E9002D0 |
| 1022:1461 |           | AMD        | Family 17h (Models 00h-0f... | 2693  |            | E52E9002D0 |
| 1022:1462 |           | AMD        | Family 17h (Models 00h-0f... | 2693  |            | E52E9002D0 |
| 1022:1463 |           | AMD        | Family 17h (Models 00h-0f... | 2693  | k10temp    | E52E9002D0 |
| 1022:1464 |           | AMD        | Family 17h (Models 00h-0f... | 2693  |            | E52E9002D0 |
| 1022:1465 |           | AMD        | Family 17h (Models 00h-0f... | 2693  |            | E52E9002D0 |
| 1022:1466 |           | AMD        | Family 17h (Models 00h-0f... | 2693  |            | E52E9002D0 |
| 1022:1467 |           | AMD        | Family 17h (Models 00h-0f... | 2693  |            | E52E9002D0 |
| 1022:15db | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 2692  | pcieport   | B2D3620851 |
| 1022:43c7 | 1b21:3306 | AMD        | 400 Series Chipset PCIe Port | 2584  | pcieport   | C537345CE8 |
| 1022:1600 |           | AMD        | Family 15h Processor Func... | 2477  |            | 588CEFB67B |
| 1022:1601 |           | AMD        | Family 15h Processor Func... | 2477  |            | 588CEFB67B |
| 1022:1602 |           | AMD        | Family 15h Processor Func... | 2477  |            | 588CEFB67B |
| 1022:1603 |           | AMD        | Family 15h Processor Func... | 2477  | k10temp    | 588CEFB67B |
| 1022:1604 |           | AMD        | Family 15h Processor Func... | 2477  | fam15h_... | 588CEFB67B |
| 1022:1605 |           | AMD        | Family 15h Processor Func... | 2477  |            | 588CEFB67B |
| 1002:439d | 1002:439d | AMD        | SB7x0/SB8x0/SB9x0 LPC hos... | 2417  |            | 588CEFB67B |
| 8086:2d01 | 8086:8086 | Intel      | Core Processor QuickPath ... | 2361  |            | C319EC4A5F |
| 8086:2d10 | 8086:8086 | Intel      | Core Processor QPI Link 0    | 2361  |            | C319EC4A5F |
| 8086:2d11 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 2361  |            | C319EC4A5F |
| 8086:2d12 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 2361  |            | C319EC4A5F |
| 8086:2d13 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 2361  |            | C319EC4A5F |
| 1022:1100 |           | AMD        | K8 [Athlon64/Opteron] Hyp... | 2343  |            | F9BFF20C4D |
| 1022:1101 |           | AMD        | K8 [Athlon64/Opteron] Add... | 2343  |            | F9BFF20C4D |
| 1022:1102 |           | AMD        | K8 [Athlon64/Opteron] DRA... | 2343  | amd64_e... | F9BFF20C4D |
| 1022:1103 |           | AMD        | K8 [Athlon64/Opteron] Mis... | 2343  | k8temp     | F9BFF20C4D |
| 1022:43c6 | 1b21:0201 | AMD        | 400 Series Chipset PCIe B... | 2332  | pcieport   | C537345CE8 |
| 1022:43b4 | 1b21:3306 | AMD        | 300 Series Chipset PCIe Port | 2110  | pcieport   | 24974BE67E |
| 1002:43a0 | 1002:0000 | AMD        | SB700/SB800/SB900 PCI to ... | 2109  | pcieport   | 21C683ED97 |
| 1022:1484 | 1022:1484 | AMD        | Starship/Matisse Internal... | 2063  | pcieport   | C537345CE8 |
| 1022:15dc | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 2054  | pcieport   | 497BF56CC6 |
| 1022:1700 |           | AMD        | Family 12h/14h Processor ... | 2003  |            | F6819A066A |
| 1022:1701 |           | AMD        | Family 12h/14h Processor ... | 2003  |            | F6819A066A |
| 1022:1702 |           | AMD        | Family 12h/14h Processor ... | 2003  |            | F6819A066A |
| 1022:1703 |           | AMD        | Family 12h/14h Processor ... | 2003  | k10temp    | F6819A066A |
| 1022:1704 |           | AMD        | Family 12h/14h Processor ... | 2003  |            | F6819A066A |
| 1022:1716 |           | AMD        | Family 12h/14h Processor ... | 2003  |            | F6819A066A |
| 1022:1718 |           | AMD        | Family 12h/14h Processor ... | 2003  |            | F6819A066A |
| 1022:1719 |           | AMD        | Family 12h/14h Processor ... | 2003  |            | F6819A066A |
| 1022:15d3 | 1022:1453 | AMD        | Raven/Raven2 PCIe GPP Bri... | 1950  | pcieport   | B2D3620851 |
| 1022:1454 | 1022:1454 | AMD        | Family 17h (Models 00h-0f... | 1900  | pcieport   | E52E9002D0 |
| 1022:1632 |           | AMD        | Renoir PCIe Dummy Host Br... | 1888  |            | F581CF8319 |
| 8086:2c62 | 8086:8086 | Intel      | Core Processor QuickPath ... | 1806  |            | C319EC4A5F |
| 1022:790e | 1458:5001 | AMD        | FCH LPC Bridge               | 1714  |            | E52E9002D0 |
| 8086:244e | 1458:5000 | Intel      | 82801 PCI Bridge             | 1702  |            | 40C84C9637 |
| 1022:15d0 | 1022:15d0 | AMD        | Raven/Raven2 Root Complex    | 1676  | k10temp    | B2D3620851 |
| 1022:1400 |           | AMD        | Family 15h (Models 10h-1f... | 1658  |            | 42CD4D28BD |
| 1022:1401 |           | AMD        | Family 15h (Models 10h-1f... | 1658  |            | 42CD4D28BD |
| 1022:1402 |           | AMD        | Family 15h (Models 10h-1f... | 1658  |            | 42CD4D28BD |
| 1022:1403 |           | AMD        | Family 15h (Models 10h-1f... | 1658  | k10temp    | 42CD4D28BD |
| 1022:1404 |           | AMD        | Family 15h (Models 10h-1f... | 1658  |            | 42CD4D28BD |
| 1022:1405 |           | AMD        | Family 15h (Models 10h-1f... | 1658  |            | 42CD4D28BD |
| 1022:1448 |           | AMD        | Renoir Device 24: Function 0 | 1649  |            | F581CF8319 |
| 1022:1449 |           | AMD        | Renoir Device 24: Function 1 | 1649  |            | F581CF8319 |
| 1022:144a |           | AMD        | Renoir Device 24: Function 2 | 1649  |            | F581CF8319 |
| 1022:144b |           | AMD        | Renoir Device 24: Function 3 | 1649  | k10temp    | F581CF8319 |
| 1022:144c |           | AMD        | Renoir Device 24: Function 4 | 1649  |            | F581CF8319 |
| 1022:144d |           | AMD        | Renoir Device 24: Function 5 | 1649  |            | F581CF8319 |
| 1022:144e |           | AMD        | Renoir Device 24: Function 6 | 1649  |            | F581CF8319 |
| 1022:144f |           | AMD        | Renoir Device 24: Function 7 | 1649  |            | F581CF8319 |
| 1022:43a0 | 1022:0000 | AMD        | Hudson PCI to PCI bridge ... | 1616  | pcieport   | B92CD04EE7 |
| 1b21:1080 | 1043:8489 | ASMedia... | ASM1083/1085 PCIe to PCI ... | 1588  | shpchp     | 278873FF66 |
| 1022:1453 | 1022:1453 | AMD        | Family 17h (Models 00h-0f... | 1546  | pcieport   | E52E9002D0 |
| 1022:157b |           | AMD        | Family 15h (Models 60h-6f... | 1490  |            | 3A06ECCCAA |
| 1022:157d |           | AMD        | Carrizo Audio Dummy Host ... | 1490  |            | 3A06ECCCAA |
| 1022:1635 | 1022:1635 | AMD        | Renoir Internal PCIe GPP ... | 1419  | pcieport   | F581CF8319 |
| 1022:57ad |           | AMD        | Matisse Switch Upstream      | 1411  | pcieport   | 93DE1508CB |
| 8086:1901 | 1043:8694 | Intel      | 6th-10th Gen Core Process... | 1257  | pcieport   | 427C8B8D8F |
| 1002:5a14 | 1002:5a14 | AMD        | RD9x0/RX980 Host Bridge      | 1245  | ati_agp    | 588CEFB67B |
| 8086:0c01 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 1232  | pcieport   | 735015DCE2 |
| 8086:0c00 | 1043:8534 | Intel      | 4th Gen Core Processor DR... | 1221  | hsw_uncore | 735015DCE2 |
| 1002:5a16 | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 1208  | pcieport   | 588CEFB67B |
| 1022:1483 | 1022:1453 | AMD        | Starship/Matisse GPP Bridge  | 1134  | pcieport   | C537345CE8 |
| 8086:1c10 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1134  | pcieport   | 278873FF66 |
| 8086:2448 |           | Intel      | 82801 Mobile PCI Bridge      | 1134  | shpchp     | C0FAA178A2 |

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
| 10ec:522a | 8086:2074 | Realtek... | RTS522A PCI Express Card ... | 127   | rtsx_pci   | 7EEEAAA250 |
| 10ec:5227 | 17aa:220c | Realtek... | RTS5227 PCI Express Card ... | 126   | rtsx_pci   | 415CC7FE56 |
| 10ec:522a | 10ec:522a | Realtek... | RTS522A PCI Express Card ... | 124   | rtsx_pci   | 87B3274937 |
| 10ec:5289 | 10ec:5289 | Realtek... | RTL8411 PCI Express Card ... | 122   | rtsx_pci   | 93116D84F3 |
| 10ec:522a | 103c:8079 | Realtek... | RTS522A PCI Express Card ... | 120   | rtsx_pci   | 436E9BF227 |
| 10ec:5287 | 1025:1193 | Realtek... | RTL8411B PCI Express Card... | 119   | rtsx_pci   | 43BFEF3BCD |
| 10ec:5287 | 1025:0866 | Realtek... | RTL8411B PCI Express Card... | 118   | rtsx_pci   | 11EBF2008B |
| 10ec:5227 | 17aa:220e | Realtek... | RTS5227 PCI Express Card ... | 117   | rtsx_pci   | 36F407C3AA |
| 10ec:5227 | 17aa:5034 | Realtek... | RTS5227 PCI Express Card ... | 113   | rtsx_pci   | CEA37DD548 |
| 10ec:525a | 1028:087c | Realtek... | RTS525A PCI Express Card ... | 113   | rtsx_pci   | 0FA8C3ED0C |
| 10ec:5227 | 103c:198f | Realtek... | RTS5227 PCI Express Card ... | 110   | rtsx_pci   | CECD552E89 |
| 10ec:5209 | 104d:908b | Realtek... | RTS5209 PCI Express Card ... | 106   | rtsx_pci   | 11EF4D4BAF |
| 10ec:5287 | 1025:1094 | Realtek... | RTL8411B PCI Express Card... | 105   | rtsx_pci   | 89135238FE |
| 10ec:5229 | 10ec:5229 | Realtek... | RTS5229 PCI Express Card ... | 103   | rtsx_pci   | 3908342BCB |
| 10ec:525a | 1028:07be | Realtek... | RTS525A PCI Express Card ... | 97    | rtsx_pci   | 69938C221E |
| 10ec:525a | 1028:07e6 | Realtek... | RTS525A PCI Express Card ... | 97    | rtsx_pci   | 5A56854746 |
| 10ec:5229 | 17aa:3808 | Realtek... | RTS5229 PCI Express Card ... | 96    | rtsx_pci   | 184B909FC0 |
| 10ec:525a | 1028:0962 | Realtek... | RTS525A PCI Express Card ... | 91    | rtsx_pci   | 8956FEE2F3 |
| 10ec:525a | 1028:08af | Realtek... | RTS525A PCI Express Card ... | 90    | rtsx_pci   | 52DEA66C52 |
| 10ec:5227 | 17aa:2214 | Realtek... | RTS5227 PCI Express Card ... | 89    | rtsx_pci   | F802ABEF07 |
| 10ec:5227 | 17aa:2226 | Realtek... | RTS5227 PCI Express Card ... | 87    | rtsx_pci   | 22A87CB141 |
| 10ec:5209 | 1025:0685 | Realtek... | RTS5209 PCI Express Card ... | 86    | rtsx_pci   | B953B67D06 |
| 10ec:5229 | 103c:1854 | Realtek... | RTS5229 PCI Express Card ... | 86    | rtsx_pci   | B0ED67249E |
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
| 10ec:5229 | 8086:2068 | Realtek... | RTS5229 PCI Express Card ... | 69    | rtsx_pci   | 82B124D8C4 |
| 10ec:525a | 1028:081c | Realtek... | RTS525A PCI Express Card ... | 69    | rtsx_pci   | ADB96FACBB |
| 10ec:5229 | 1179:f91b | Realtek... | RTS5229 PCI Express Card ... | 67    | rtsx_pci   | F1C33CDDC6 |
| 10ec:5287 | 10ec:5287 | Realtek... | RTL8411B PCI Express Card... | 67    | rtsx_pci   | 9EC292C9D9 |
| 10ec:5227 | 10ec:5227 | Realtek... | RTS5227 PCI Express Card ... | 66    | rtsx_pci   | 5D323AF087 |
| 10ec:525a | 1028:06de | Realtek... | RTS525A PCI Express Card ... | 66    | rtsx_pci   | 08D4C126FA |
| 10ec:5209 | 104d:90b8 | Realtek... | RTS5209 PCI Express Card ... | 65    | rtsx_pci   | 1D79ED8874 |
| 10ec:5287 | 1025:118a | Realtek... | RTL8411B PCI Express Card... | 65    | rtsx_pci   | E4762B54F7 |
| 10ec:522a | 17aa:2279 | Realtek... | RTS522A PCI Express Card ... | 63    | rtsx_pci   | F8024B89D4 |
| 10ec:5229 | 1179:f920 | Realtek... | RTS5229 PCI Express Card ... | 62    | rtsx_pci   | B751D415AD |
| 10ec:5249 | 17aa:3801 | Realtek... | RTS5249 PCI Express Card ... | 62    | rtsx_pci   | 43ADB60059 |
| 10ec:525a | 1028:075b | Realtek... | RTS525A PCI Express Card ... | 62    | rtsx_pci   | 8BB0307157 |
| 10ec:5209 | 104d:90ab | Realtek... | RTS5209 PCI Express Card ... | 61    | rtsx_pci   | ACF29B49FD |
| 10ec:5229 | 103c:188b | Realtek... | RTS5229 PCI Express Card ... | 61    | rtsx_pci   | 65EC913842 |
| 10ec:522a | 17aa:5089 | Realtek... | RTS522A PCI Express Card ... | 61    | rtsx_pci   | 1EC4861E97 |
| 10ec:5260 | 1028:0991 | Realtek... | RTS5260 PCI Express Card ... | 60    | rtsx_pci   | 22BC284F45 |
| 10ec:5229 | 1179:ff1e | Realtek... | RTS5229 PCI Express Card ... | 59    | rtsx_pci   | FE77011ED7 |
| 10ec:5229 | 17aa:3832 | Realtek... | RTS5229 PCI Express Card ... | 59    | rtsx_pci   | 92A4BA4AA3 |
| 10ec:525a | 1028:06dc | Realtek... | RTS525A PCI Express Card ... | 59    | rtsx_pci   | 69A251CC1F |
| 10ec:5229 | 103c:2213 | Realtek... | RTS5229 PCI Express Card ... | 57    | rtsx_pci   | 8D9A889ED5 |
| 10ec:5289 | 1043:1587 | Realtek... | RTL8411 PCI Express Card ... | 57    | rtsx_pci   | 1A44FC7E8F |
| 1aea:6625 | 103c:8478 | Alcor M... | AU6625 PCI-E Flash card r... | 56    | alcor_pci  | 362E1D3B99 |
| 10ec:522a | 17aa:5053 | Realtek... | RTS522A PCI Express Card ... | 55    | rtsx_pci   | 4DBC231901 |
| 10ec:525a | 17aa:222e | Realtek... | RTS525A PCI Express Card ... | 54    | rtsx_pci   | 0F1A1FEEFE |
| 10ec:525a | 17aa:2238 | Realtek... | RTS525A PCI Express Card ... | 53    | rtsx_pci   | 623506F87F |
| 10ec:5229 | 103c:1818 | Realtek... | RTS5229 PCI Express Card ... | 52    | rtsx_pci   | 31FF7DD229 |
| 10ec:5229 | 103c:183e | Realtek... | RTS5229 PCI Express Card ... | 52    | rtsx_pci   | 5EBA384ACD |
| 10ec:5229 | 103c:184a | Realtek... | RTS5229 PCI Express Card ... | 52    | rtsx_pci   | E75DC5DCFB |
| 10ec:522a | 103c:8730 | Realtek... | RTS522A PCI Express Card ... | 52    | rtsx_pci   | 1719B2DC9D |
| 10ec:5229 | 1179:f840 | Realtek... | RTS5229 PCI Express Card ... | 50    | rtsx_pci   | A6F33AA565 |
| 10ec:522a | 17aa:380e | Realtek... | RTS522A PCI Express Card ... | 50    | rtsx_pci   | F07B9B77F5 |
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
| 10ec:5209 | 1025:0781 | Realtek... | RTS5209 PCI Express Card ... | 41    | rtsx_pci   | 10E7FFC71D |
| 10ec:5227 | 10cf:187f | Realtek... | RTS5227 PCI Express Card ... | 41    | rtsx_pci   | A0197C30DB |
| 10ec:525a | 1028:0704 | Realtek... | RTS525A PCI Express Card ... | 41    | rtsx_pci   | 1F26867986 |
| 10ec:5209 | 103c:3567 | Realtek... | RTS5209 PCI Express Card ... | 40    | rtsx_pci   | 0585DD7016 |
| 10ec:522a | 103c:8101 | Realtek... | RTS522A PCI Express Card ... | 40    | rtsx_pci   | 1069B24865 |
| 10ec:525a | 1028:07a7 | Realtek... | RTS525A PCI Express Card ... | 40    | rtsx_pci   | 3ED90A1781 |
| 10ec:525a | 1028:08e1 | Realtek... | RTS525A PCI Express Card ... | 40    | rtsx_pci   | 2932112DCA |
| 10ec:525a | 1028:06e4 | Realtek... | RTS525A PCI Express Card ... | 39    | rtsx_pci   | 32EC7FD885 |
| 10ec:525a | 17aa:224f | Realtek... | RTS525A PCI Express Card ... | 39    | rtsx_pci   | 2EAC1BFC4F |
| 10ec:522a | 103c:876e | Realtek... | RTS522A PCI Express Card ... | 38    | rtsx_pci   | 28B152BB19 |
| 10ec:522a | 17aa:3852 | Realtek... | RTS522A PCI Express Card ... | 38    | rtsx_pci   | C74557D180 |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0aa3 | 10de:cb79 | Nvidia     | MCP79 Co-processor           | 254   | nvidia     | 25B2F96576 |
| 10de:0d7a | 10de:cb89 | Nvidia     | MCP89 Co-Processor           | 95    |            | 80E0B6AF9E |
| 10de:0753 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Co-... | 66    |            | 9005621271 |
| 10de:0753 | 103c:360a | Nvidia     | MCP78S [GeForce 8200] Co-... | 59    |            | B9B0C35DB8 |
| 10de:03f4 | 1462:7309 | Nvidia     | MCP61 SMU                    | 38    |            | 72F1E0A452 |
| 10de:03f4 | 1462:7597 | Nvidia     | MCP61 SMU                    | 38    |            | 79851E843C |
| 10de:0753 | 1849:0753 | Nvidia     | MCP78S [GeForce 8200] Co-... | 37    |            | E817658118 |
| 10de:0543 | 103c:30cf | Nvidia     | MCP67 Co-processor           | 33    |            | 896E1BC2A0 |
| 10de:0543 | 1025:0126 | Nvidia     | MCP67 Co-processor           | 31    |            | AA6D721BF2 |
| 10de:0aa3 | 1043:1cf7 | Nvidia     | MCP79 Co-processor           | 27    | nvidia     | 75903BAEAC |
| 10de:0aa3 | 1043:1fa7 | Nvidia     | MCP79 Co-processor           | 24    | nvidia     | B0BCC6C31C |
| 10de:0753 | 1043:82e2 | Nvidia     | MCP78S [GeForce 8200] Co-... | 22    |            | DE0F1A6DD3 |
| 10de:0271 | 103c:30b7 | Nvidia     | MCP51 PMU                    | 19    |            | C28788427E |
| 10de:0aa3 | 1043:1d17 | Nvidia     | MCP79 Co-processor           | 18    | nvidia     | F1573DB462 |
| 10de:07da | 1025:0137 | Nvidia     | MCP73 Co-processor           | 14    |            | 4AEC616B4D |
| 10de:0447 | 103c:30cf | Nvidia     | MCP65 SMU                    | 13    |            | 8774B51F01 |
| 10de:0aa3 | 1025:0222 | Nvidia     | MCP79 Co-processor           | 13    | nvidia     | 093D03CAF5 |
| 10de:03f4 |           | Nvidia     | MCP61 SMU                    | 12    |            | CB279CFEAF |
| 10de:0543 | 1043:16a7 | Nvidia     | MCP67 Co-processor           | 12    |            | 414786C3D5 |
| 10de:0753 | 1025:0228 | Nvidia     | MCP78S [GeForce 8200] Co-... | 12    |            | 6017A97F3E |
| 10de:0aa3 | 1043:8402 | Nvidia     | MCP79 Co-processor           | 12    | nvidia     | 1FF8ED5A66 |
| 10de:0753 | 1025:0153 | Nvidia     | MCP78S [GeForce 8200] Co-... | 11    |            | 3C4134E3B4 |
| 10de:0aa3 | 1025:0168 | Nvidia     | MCP79 Co-processor           | 11    | nvidia     | 6872AE9FB4 |
| 10de:0271 | 1025:0112 | Nvidia     | MCP51 PMU                    | 10    |            | 56639ACA29 |
| 10de:0753 | 1043:82e8 | Nvidia     | MCP78S [GeForce 8200] Co-... | 10    |            | 9DAF1B6529 |
| 10de:0aa3 | 103c:3651 | Nvidia     | MCP79 Co-processor           | 10    | nvidia     | 50468DF6ED |
| 10de:03f4 | 1043:8234 | Nvidia     | MCP61 SMU                    | 9     |            | 56DB54E530 |
| 10de:0543 | 1849:0543 | Nvidia     | MCP67 Co-processor           | 9     |            | 1C6B15BC7B |
| 10de:0753 | 1565:340b | Nvidia     | MCP78S [GeForce 8200] Co-... | 9     |            | BE977291B5 |
| 10de:0aa3 | 1462:7621 | Nvidia     | MCP79 Co-processor           | 9     | nvidia     | 29ECAF9382 |
| 10de:0753 | 103c:2a81 | Nvidia     | MCP78S [GeForce 8200] Co-... | 8     |            | 3A69706315 |
| 10de:0aa3 | 1462:1012 | Nvidia     | MCP79 Co-processor           | 8     | nvidia     | 76D2D77034 |
| 10de:0753 | 1025:0461 | Nvidia     | MCP78S [GeForce 8200] Co-... | 7     |            | 04B8123AA5 |
| 10de:0753 | 1043:82e7 | Nvidia     | MCP78S [GeForce 8200] Co-... | 7     |            | 6AA0488E7E |
| 10de:0753 | 1462:6720 | Nvidia     | MCP78S [GeForce 8200] Co-... | 7     |            | 46430A6E00 |
| 10de:0aa3 | 1025:0160 | Nvidia     | MCP79 Co-processor           | 7     | nvidia     | 9BBF3BEFAB |
| 10de:0aa3 | 1b0a:0074 | Nvidia     | MCP79 Co-processor           | 7     | nvidia     | 484AF2A752 |
| 10de:0271 | 103c:30b5 | Nvidia     | MCP51 PMU                    | 6     |            | 31A42ED2B6 |
| 10de:0271 | 1462:3fc1 | Nvidia     | MCP51 PMU                    | 6     |            | 8DB6FA7A1C |
| 10de:0543 | 103c:30d6 | Nvidia     | MCP67 Co-processor           | 6     |            | D6DADC467D |
| 10de:0543 | 103c:30ea | Nvidia     | MCP67 Co-processor           | 6     |            | 1CEE50E485 |
| 10de:07da | 1462:7504 | Nvidia     | MCP73 Co-processor           | 6     |            | 53C7457A1D |
| 10de:0271 | 103c:30bf | Nvidia     | MCP51 PMU                    | 5     |            | BAD7484C1A |
| 10de:0753 | 1025:014d | Nvidia     | MCP78S [GeForce 8200] Co-... | 5     |            | 09694E2816 |
| 10de:0753 | 1025:0157 | Nvidia     | MCP78S [GeForce 8200] Co-... | 5     |            | 591C077E28 |
| 10de:07da | 1462:7366 | Nvidia     | MCP73 Co-processor           | 5     |            | ADA828F120 |
| 10de:07da | 1462:736b | Nvidia     | MCP73 Co-processor           | 5     |            | C554C3A77F |
| 10de:07da | 1849:07da | Nvidia     | MCP73 Co-processor           | 5     |            | 01E398A327 |
| 10de:0aa3 | 1071:9070 | Nvidia     | MCP79 Co-processor           | 5     | nvidia     | ABE849C090 |
| 10de:0aa3 | 1849:0aa3 | Nvidia     | MCP79 Co-processor           | 5     | nvidia     | B68D01F3AE |
| 10de:0271 | 1043:1367 | Nvidia     | MCP51 PMU                    | 4     |            | 7BD5FA25B3 |
| 10de:03f4 | 1849:03f4 | Nvidia     | MCP61 SMU                    | 4     |            | 5751926628 |
| 10de:0753 | 1025:0227 | Nvidia     | MCP78S [GeForce 8200] Co-... | 4     |            | 4D35606FF5 |
| 10de:0aa3 | 1028:0271 | Nvidia     | MCP79 Co-processor           | 4     |            | E54DAEA8F9 |
| 10de:0aa3 | 103c:2a95 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | 0E1FA2C583 |
| 10de:0aa3 | 1043:1fd7 | Nvidia     | MCP79 Co-processor           | 4     |            | AE8948A236 |
| 10de:0aa3 | 105b:0d52 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | 3F5D854E2F |
| 10de:0aa3 | 19da:0ae5 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | 5CA23CF3F6 |
| 10de:0271 | 103c:30e5 | Nvidia     | MCP51 PMU                    | 3     |            | A070611109 |
| 10de:0271 | 1462:373d | Nvidia     | MCP51 PMU                    | 3     |            | 154009C211 |
| 10de:0271 | 1734:110c | Nvidia     | MCP51 PMU                    | 3     |            | 79DCA1A7CC |
| 10de:0753 | 1025:0462 | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | BEB8F313F7 |
| 10de:0753 | 103c:2a9e | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | C1329912E7 |
| 10de:0753 | 1462:7612 | Nvidia     | MCP78S [GeForce 8200] Co-... | 3     |            | 905C03A3D4 |
| 10de:07da | 10de:07d7 | Nvidia     | MCP73 Co-processor           | 3     |            | 974A439CC4 |
| 10de:0aa3 | 103c:2aa1 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 622D9B0AE4 |
| 10de:0aa3 | 1043:1a87 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 03675A2262 |
| 10de:0aa3 | 1043:83e2 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 1452DE25DA |
| 10de:0aa3 | 1043:83e9 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 0D0D8B9925 |
| 10de:0aa3 | 1043:83f9 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 57C3CE82B7 |
| 10de:0aa3 | 1734:1151 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | E6A298846B |
| 10de:0aa3 | 17aa:38da | Nvidia     | MCP79 Co-processor           | 3     |            | D408DE645F |
| 10de:0aa3 | 19da:a108 | Nvidia     | MCP79 Co-processor           | 3     | nvidia     | 35A29512AC |
| 8086:19e2 | 8086:19e2 | Intel      | Atom Processor C3000 Seri... | 3     | qat_c3xxx  | 2B7A8BA5FC |
| 10de:0271 | 1734:10d4 | Nvidia     | MCP51 PMU                    | 2     |            | 00863FCEA8 |
| 10de:0543 | 1025:0127 | Nvidia     | MCP67 Co-processor           | 2     |            | 0D272A5910 |
| 10de:0753 | 1019:1b67 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 35BFD13207 |
| 10de:0753 | 1019:2646 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | BF975A328C |
| 10de:0753 | 1019:2666 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 5C15176A57 |
| 10de:0753 | 1043:8332 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | FC54031F7E |
| 10de:0753 | 107b:0173 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 23D6F05DAF |
| 10de:0753 | 10de:cb84 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 89EEF3C1A9 |
| 10de:0753 | 1462:7375 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 07A001660F |
| 10de:0753 | 1462:7578 | Nvidia     | MCP78S [GeForce 8200] Co-... | 2     |            | 9FC0813DDD |
| 10de:0aa3 | 1043:8356 | Nvidia     | MCP79 Co-processor           | 2     |            | AAF6FAFAD6 |
| 10de:0aa3 | 1458:0aa3 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | 545B983E7C |
| 10de:0aa3 | 1462:1019 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | 2054B3A4CC |
| 10de:0aa3 | 1462:4570 | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | 937655E17D |
| 10de:0aa3 | 1b0a:000f | Nvidia     | MCP79 Co-processor           | 2     | nvidia     | BF054CFF0C |
| 10de:0aa3 | 1b0a:4203 | Nvidia     | MCP79 Co-processor           | 2     |            | 3D1668F30A |
| 8086:19e2 | 8086:0000 | Intel      | Atom Processor C3000 Seri... | 2     | qat_c3xxx  | 40E07B4DAD |
| 8086:1f18 | 15d9:0820 | Intel      | Atom processor C2000 QAT     | 2     |            | B9AC0D657E |
| 8086:1f18 | 8086:0000 | Intel      | Atom processor C2000 QAT     | 2     |            | C1D37659C1 |
| 8086:225c | 8086:2500 | Intel      | Xeon Phi coprocessor SE10... | 2     | mic        | 9D9DA282F6 |
| 8086:2710 | 8086:0000 | Intel      | Co-processor                 | 2     |            | AEAD99F55D |
| 8086:37c8 | 8086:0000 | Intel      | C62x Chipset QuickAssist ... | 2     | qat_c62x   | 331227D869 |
| 8086:4940 | 8086:0000 | Intel      | Co-processor                 | 2     |            | AEAD99F55D |
| 10de:0271 | 1043:1322 | Nvidia     | MCP51 PMU                    | 1     |            | 71FE8FB963 |
| 10de:0271 | 1043:14b7 | Nvidia     | MCP51 PMU                    | 1     |            | AFE46A35A8 |
| 10de:0271 | 107b:0317 | Nvidia     | MCP51 PMU                    | 1     |            | 1178CC8597 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1c3a | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1128  | mei_me     | 278873FF66 |
| 8086:8c3a | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 903   | mei_me     | 735015DCE2 |
| 8086:1e3a | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 773   | mei_me     | 1575E2C682 |
| 8086:a13a | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 731   | mei_me     | 427C8B8D8F |
| 8086:1c3a | 1458:1c3a | Intel      | 6 Series/C200 Series Chip... | 717   | mei_me     | 042607D7F1 |
| 8086:8c3a | 1458:1c3a | Intel      | 8 Series/C220 Series Chip... | 593   | mei_me     | 3934A7E59D |
| 8086:1e3a | 1458:1c3a | Intel      | 7 Series/C216 Chipset Fam... | 569   | mei_me     | BB6DE8B3E0 |
| 8086:1e3a | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 567   | mei_me     | 16EBDC4388 |
| 8086:a2ba | 1043:8694 | Intel      | 200 Series PCH CSME HECI #1  | 463   | mei_me     | 381023907E |
| 8086:a2ba | 1458:1c3a | Intel      | 200 Series PCH CSME HECI #1  | 430   | mei_me     | 8C2B6CF453 |
| 8086:a13a | 1458:1c3a | Intel      | 100 Series/C230 Series Ch... | 418   | mei_me     | 36BF6DAB37 |
| 8086:a360 | 1043:8694 | Intel      | Cannon Lake PCH HECI Cont... | 375   | mei_me     | 22A32FC3F2 |
| 8086:3b64 | 17aa:215f | Intel      | 5 Series/3400 Series Chip... | 351   | mei_me     | 570863FD8C |
| 8086:8cba | 1043:8534 | Intel      | 9 Series Chipset Family M... | 329   | mei_me     | 5A5D3A54C3 |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 325   | mei_me     | 403E735C43 |
| 8086:1c3a | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 324   | mei_me     | ECC4515014 |
| 8086:1c3a | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 318   | mei_me     | D1D57448C4 |
| 8086:9c3a | 17aa:3978 | Intel      | 8 Series HECI #0             | 309   | mei_me     | 3CDDE1061C |
| 8086:a360 | 1458:1c3a | Intel      | Cannon Lake PCH HECI Cont... | 306   | mei_me     | 1C2A383C4F |
| 8086:319a | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 296   | mei_me     | 4DBC03E904 |
| 8086:9cba | 8086:7270 | Intel      | Wildcat Point-LP MEI Cont... | 292   | mei_me     | 5BE083EDAB |
| 8086:1e3a | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 280   | mei_me     | 783D081B5A |
| 8086:8c3a | 1849:8c3a | Intel      | 8 Series/C220 Series Chip... | 279   | mei_me     | 111E98DDEF |
| 8086:1c3a | 1849:1c3a | Intel      | 6 Series/C200 Series Chip... | 270   | mei_me     | 7070F2EAF3 |
| 8086:2a44 | 17aa:20e6 | Intel      | Mobile 4 Series Chipset M... | 264   | mei_me     | 9A7BE426F5 |
| 8086:8cba | 1458:1c3a | Intel      | 9 Series Chipset Family M... | 255   | mei_me     | 5EAD0CA3AD |
| 8086:a13a | 1849:a13a | Intel      | 100 Series/C230 Series Ch... | 202   | mei_me     | 6B4C3F811B |
| 8086:1e3a | 1849:1e3a | Intel      | 7 Series/C216 Chipset Fam... | 190   | mei_me     | F6F957DDF3 |
| 8086:3b64 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 188   | mei_me     | E3FC4E0622 |
| 8086:9d3a | 8086:7270 | Intel      | Sunrise Point-LP CSME HEC... | 187   | mei_me     | 6039985C3F |
| 8086:1e3a | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 186   | mei_me     | C9D8EFC9B9 |
| 8086:8c3a | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 186   | mei_me     | 0420EDF711 |
| 8086:1e3a | 1028:0577 | Intel      | 7 Series/C216 Chipset Fam... | 178   | mei_me     | E1B966B80D |
| 8086:a2ba | 1849:a2ba | Intel      | 200 Series PCH CSME HECI #1  | 178   | mei_me     | 79E6EF3655 |
| 8086:1c3a | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 171   | mei_me     | A75FFD5203 |
| 8086:8c3a | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 166   | mei_me     | 60FA5FF04C |
| 8086:1e3a | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 165   | mei_me     | A120083D3C |
| 8086:1c3a | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 163   | mei_me     | B96D5D5FDC |
| 8086:1e3a | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 163   | mei_me     | 82E60126C9 |
| 8086:1c3a | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 160   | mei_me     | 4C3C43DAAA |
| 8086:1c3a | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 158   | mei_me     | B66EB36016 |
| 8086:a2ba | 1043:872f | Intel      | 200 Series PCH CSME HECI #1  | 158   | mei_me     | F60A34FE5C |
| 8086:a328 | 1025:1331 | Intel      | Cannon Lake PCH Serial IO... | 157   | intel_lpss | BC9DC107D1 |
| 8086:a360 | 1025:1331 | Intel      | Cannon Lake PCH HECI Cont... | 157   | mei_me     | BC9DC107D1 |
| 8086:1d3a | 1043:84ef | Intel      | C600/X79 series chipset M... | 156   | mei_me     | 1BB97BC7DF |
| 8086:9d3a | 17aa:386e | Intel      | Sunrise Point-LP CSME HEC... | 147   | mei_me     | F86520F5A7 |
| 8086:319a | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 143   | mei_me     | 5C95C74B6C |
| 8086:a360 | 1028:0905 | Intel      | Cannon Lake PCH HECI Cont... | 142   | mei_me     | 58E43F0514 |
| 8086:1c3a | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 141   | mei_me     | 0A8E84DFAD |
| 8086:1e3a | 1028:0534 | Intel      | 7 Series/C216 Chipset Fam... | 141   | mei_me     | FA4D12994D |
| 8086:02e0 | 17aa:5079 | Intel      | Comet Lake Management Eng... | 138   | mei_me     | A35AAAEB6D |
| 8086:3b64 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 138   | mei_me     | A18FB33A6F |
| 8086:8c3a | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 137   | mei_me     | CC73A253B3 |
| 8086:9d3e |           | Intel      | Skylake-U/Y CSME: HECI #3    | 137   | mei_me     | 6039985C3F |
| 8086:1e3a | 1043:124d | Intel      | 7 Series/C216 Chipset Fam... | 136   | mei_me     | 3498166FA2 |
| 8086:3b64 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 136   | mei_me     | 77E0B6A916 |
| 8086:1c3a | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 133   | mei_me     | D6237E9949 |
| 8086:1c3a | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 132   | mei_me     | 532A1D3D01 |
| 8086:3b64 | 17aa:38a5 | Intel      | 5 Series/3400 Series Chip... | 131   | mei_me     | A31437072C |
| 8086:1e3a | 17aa:21f6 | Intel      | 7 Series/C216 Chipset Fam... | 130   | mei_me     | 69A252CCD6 |
| 8086:9c3a | 17aa:220c | Intel      | 8 Series HECI #0             | 130   | mei_me     | 415CC7FE56 |
| 8086:9de0 | 8086:2074 | Intel      | Cannon Point-LP MEI Contr... | 130   | mei_me     | 7EEEAAA250 |
| 8086:1e3a | 1025:064b | Intel      | 7 Series/C216 Chipset Fam... | 127   | mei_me     | D74C10F41F |
| 8086:9de0 | 17aa:2279 | Intel      | Cannon Point-LP MEI Contr... | 127   | mei_me     | A01E524A66 |
| 8086:8c3a | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 124   | mei_me     | EABB3946AD |
| 8086:a360 | 1849:a360 | Intel      | Cannon Lake PCH HECI Cont... | 124   | mei_me     | 2FF008A28D |
| 8086:9d3a | 103c:8079 | Intel      | Sunrise Point-LP CSME HEC... | 121   | mei_me     | 436E9BF227 |
| 8086:9d3a | 17aa:3801 | Intel      | Sunrise Point-LP CSME HEC... | 120   | mei_me     | 72617E5DD9 |
| 8086:8cba | 1849:8cba | Intel      | 9 Series Chipset Family M... | 119   | mei_me     | 8DE72FD346 |
| 8086:9d3a | 1025:1193 | Intel      | Sunrise Point-LP CSME HEC... | 119   | mei_me     | 43BFEF3BCD |
| 8086:1e3a | 10cf:16ea | Intel      | 7 Series/C216 Chipset Fam... | 118   | mei_me     | 4639F065C8 |
| 8086:9c3a | 8086:7270 | Intel      | 8 Series HECI #0             | 118   | mei_me     | 0C24CAF245 |
| 8086:8c3a | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 117   | mei_me     | 36F407C3AA |
| 8086:3b64 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 116   | mei_me     | C29EE7CA9F |
| 8086:1c3a | 103c:161c | Intel      | 6 Series/C200 Series Chip... | 114   | mei_me     | B6AC4539D1 |
| 8086:a360 | 1028:087c | Intel      | Cannon Lake PCH HECI Cont... | 114   | mei_me     | 0FA8C3ED0C |
| 8086:1c3a | 1043:1277 | Intel      | 6 Series/C200 Series Chip... | 113   | mei_me     | FC712846D9 |
| 8086:8d3a | 1043:8600 | Intel      | C610/X99 series chipset M... | 113   | mei_me     | D3A4772E4E |
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
| 8086:1e3a | 103c:3397 | Intel      | 7 Series/C216 Chipset Fam... | 104   | mei_me     | BF9875C5AC |
| 8086:29b4 | 1028:0211 | Intel      | 82Q35 Express MEI Controller | 104   | mei_me     | 7E7D0BC489 |
| 8086:1c3a | 144d:c606 | Intel      | 6 Series/C200 Series Chip... | 103   | mei_me     | 89DF37A291 |
| 8086:9de0 | 17aa:2292 | Intel      | Cannon Point-LP MEI Contr... | 103   | mei_me     | 26C62915E0 |
| 8086:1e3a | 1025:0647 | Intel      | 7 Series/C216 Chipset Fam... | 101   | mei_me     | 8BC152AA27 |
| 8086:1c3a | 1043:13c7 | Intel      | 6 Series/C200 Series Chip... | 100   | mei_me     | 966E771791 |
| 8086:8c3a | 1028:0612 | Intel      | 8 Series/C220 Series Chip... | 100   | mei_me     | 990123A52D |
| 8086:3b64 | 1458:3b64 | Intel      | 5 Series/3400 Series Chip... | 99    | mei_me     | 02DFFBFEA8 |
| 8086:9d3a | 1028:07e6 | Intel      | Sunrise Point-LP CSME HEC... | 99    | mei_me     | 5A56854746 |
| 8086:a13a | 1028:07be | Intel      | 100 Series/C230 Series Ch... | 99    | mei_me     | 69938C221E |

### Digitizer pen (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a0d0 | 8086:2097 | Intel      | Digitizer Pen                | 7     |            | 4BFFB79E7C |
| 8086:a0d0 | 1414:0056 | Intel      | Digitizer Pen                | 1     |            | A4AEFCD9B2 |

### Dma controller (eisa dma) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9ce0 | 8086:9ce0 | Intel      | Wildcat Point-LP Serial I... | 265   | dw_dmac... | 5BE083EDAB |
| 8086:9c60 |           | Intel      | 8 Series Low Power Sub-Sy... | 33    | dw_dmac... | 66F91918DC |
| 8086:22c0 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 19    | dw_dmac... | DCC1CCB590 |
| 8086:2286 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 12    | dw_dmac... | 44472E729C |
| 8086:22c0 | 1025:106d | Intel      | Atom/Celeron/Pentium Proc... | 12    | dw_dmac... | 44472E729C |
| 8086:9c60 | 1025:0a11 | Intel      | 8 Series Low Power Sub-Sy... | 7     | dw_dmac... | 9779F3CABD |
| 8086:9c60 | 103c:21ed | Intel      | 8 Series Low Power Sub-Sy... | 5     | dw_dmac... | 9BB0BF9AC8 |
| 8086:0f40 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 2     | dw_dmac... | 0994A3EEB3 |
| 8086:0f06 | 8086:0f06 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | A968EF1DD8 |
| 8086:0f06 | 8086:2056 | Intel      | Atom Processor Z36xxx/Z37... | 1     |            | D4408F7B0E |
| 8086:0f06 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | A211982E39 |
| 8086:0f40 |           | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | 5900E800AA |
| 8086:0f40 | 1025:0939 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | C431BDD246 |
| 8086:0f40 | 103c:8023 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | 49E4112B11 |
| 8086:0f40 | 1170:9991 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | B5C89FA6C1 |
| 8086:0f40 | 17aa:3908 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | 0128495D83 |
| 8086:0f40 | 8086:2056 | Intel      | Atom Processor Z36xxx/Z37... | 1     |            | D4408F7B0E |
| 8086:2286 | 1025:106c | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 09F6D20FE1 |
| 8086:2286 | 1025:1151 | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 7B7DB12037 |
| 8086:2286 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 10C1838B9D |
| 8086:22c0 | 1025:106c | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 09F6D20FE1 |
| 8086:22c0 | 1025:1151 | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 7B7DB12037 |
| 8086:22c0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 10C1838B9D |

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
| 1022:15df | 1022:15df | AMD        | Family 17h (Models 10h-1f... | 2000  | ccp        | B2D3620851 |
| 1022:1456 | 1022:1456 | AMD        | Family 17h (Models 00h-0f... | 1890  | ccp        | E52E9002D0 |
| 1022:1486 | 1022:1486 | AMD        | Starship/Matisse Cryptogr... | 1381  | ccp        | C537345CE8 |
| 1022:1486 | 1043:87c0 | AMD        | Starship/Matisse Cryptogr... | 728   | ccp        | 161865EDB0 |
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 659   | mei_txe    | 2FBF6F153B |
| 1022:1456 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 618   | ccp        | 491D1A96CC |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 480   |            | 34F2870A95 |
| 1022:1537 | 1022:1537 | AMD        | Kabini/Mullins PSP-Platfo... | 468   | ccp        | 65C122FE69 |
| 1022:15df | 1043:876b | AMD        | Family 17h (Models 10h-1f... | 262   | ccp        | 24974BE67E |
| 8086:0f18 | 8086:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 170   | mei_txe    | 1A0A5790B3 |
| 1022:1486 | 1043:8808 | AMD        | Starship/Matisse Cryptogr... | 164   | ccp        | A525C8911B |
| 1022:1537 | 17aa:3801 | AMD        | Kabini/Mullins PSP-Platfo... | 137   | ccp        | 0CDC6E9D84 |
| 8086:0f18 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 133   | mei_txe    | 7D6AB19F8D |
| 1022:1578 | 103c:8330 | AMD        | Carrizo Platform Security... | 120   |            | 18CEA74915 |
| 8086:0f18 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 110   | mei_txe    | 1387FAB9FE |
| 1022:1486 | 1462:7c02 | AMD        | Starship/Matisse Cryptogr... | 97    | ccp        | 9BCD3D5479 |
| 8086:0f18 | 17aa:3909 | Intel      | Atom Processor Z36xxx/Z37... | 96    | mei_txe    | 184B909FC0 |
| 1022:15df | 17aa:5081 | AMD        | Family 17h (Models 10h-1f... | 90    | ccp        | 273A5FF27D |
| 1022:1578 | 103c:84ac | AMD        | Carrizo Platform Security... | 87    |            | 3A06ECCCAA |
| 1022:15df | 19e5:3e19 | AMD        | Family 17h (Models 10h-1f... | 81    | ccp        | 1310B8ABF4 |
| 1022:1578 | 1025:1192 | AMD        | Carrizo Platform Security... | 79    |            | F5F4E2457B |
| 1022:15df | 17aa:507f | AMD        | Family 17h (Models 10h-1f... | 75    | ccp        | 8A34D739FD |
| 1022:1578 | 17aa:3810 | AMD        | Carrizo Platform Security... | 70    |            | D9D0DD7C3C |
| 1022:1486 | 1462:7b86 | AMD        | Starship/Matisse Cryptogr... | 66    | ccp        | 7E563A9D44 |
| 1022:15df | 17aa:381f | AMD        | Family 17h (Models 10h-1f... | 66    | ccp        | 8A6E0EE275 |
| 8086:0f18 | 1849:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 66    | mei_txe    | 1410D0FFB5 |
| 1022:15df | 1025:134d | AMD        | Family 17h (Models 10h-1f... | 63    | ccp        | 6134BF279A |
| 1022:15df | 17aa:3802 | AMD        | Family 17h (Models 10h-1f... | 63    | ccp        | 497BF56CC6 |
| 1022:15df | 1025:1366 | AMD        | Family 17h (Models 10h-1f... | 61    | ccp        | BCC833AC3C |
| 1022:15df | 17aa:5124 | AMD        | Family 17h (Models 10h-1f... | 61    | ccp        | 52BA950565 |
| 8086:2298 | 1025:1012 | Intel      | Atom/Celeron/Pentium Proc... | 61    | mei_txe    | DC6378E76B |
| 1022:1456 | 1462:7c02 | AMD        | Family 17h (Models 00h-0f... | 59    | ccp        | F50B61B450 |
| 8086:2298 | 1028:06ac | Intel      | Atom/Celeron/Pentium Proc... | 59    | mei_txe    | F1B660B91C |
| 8086:2298 | 103c:832c | Intel      | Atom/Celeron/Pentium Proc... | 59    | mei_txe    | 5B9D2833CC |
| 1022:15df | 103c:84ae | AMD        | Family 17h (Models 10h-1f... | 58    | ccp        | 2E3861AEF3 |
| 1022:15df | 17aa:380f | AMD        | Family 17h (Models 10h-1f... | 58    | ccp        | 3F7C00C1EF |
| 1022:15df | 17aa:3818 | AMD        | Family 17h (Models 10h-1f... | 57    | ccp        | 3CDC08297E |
| 8086:0f18 | 103c:2213 | Intel      | Atom Processor Z36xxx/Z37... | 57    | mei_txe    | 8D9A889ED5 |
| 1022:15df | 17aa:3811 | AMD        | Family 17h (Models 10h-1f... | 54    | ccp        | 8DB63E7A74 |
| 1022:1578 | 17aa:380f | AMD        | Carrizo Platform Security... | 53    |            | 0036C99447 |
| 8086:0f18 | 1297:2041 | Intel      | Atom Processor Z36xxx/Z37... | 53    | mei_txe    | 4BD1D4C963 |
| 1022:15df | 17aa:3816 | AMD        | Family 17h (Models 10h-1f... | 52    | ccp        | 88286C36E9 |
| 8086:0f18 | 1043:161d | Intel      | Atom Processor Z36xxx/Z37... | 52    | mei_txe    | 1FA3E8B296 |
| 1022:15df | 17aa:5082 | AMD        | Family 17h (Models 10h-1f... | 51    | ccp        | 037A558C7D |
| 8086:2298 | 1043:10c0 | Intel      | Atom/Celeron/Pentium Proc... | 51    | mei_txe    | 2CE3B8F43C |
| 1022:15df | 17aa:380d | AMD        | Family 17h (Models 10h-1f... | 47    | ccp        | 8C961555FE |
| 1022:15df | 17aa:3810 | AMD        | Family 17h (Models 10h-1f... | 47    | ccp        | 09ADDF2612 |
| 8086:0f18 | 17aa:3986 | Intel      | Atom Processor Z36xxx/Z37... | 47    | mei_txe    | 07D05077AF |
| 1022:1456 | 1462:7b86 | AMD        | Family 17h (Models 00h-0f... | 46    | ccp        | F17090E5D2 |
| 1022:15df | 1025:1259 | AMD        | Family 17h (Models 10h-1f... | 46    | ccp        | 3D5D3DDF84 |
| 8086:2298 | 17aa:3808 | Intel      | Atom/Celeron/Pentium Proc... | 46    | mei_txe    | 662ED28F07 |
| 1022:1486 | 1462:7b89 | AMD        | Starship/Matisse Cryptogr... | 45    | ccp        | A72102FDB0 |
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
| 1022:15df | 103c:876e | AMD        | Family 17h (Models 10h-1f... | 38    | ccp        | 28B152BB19 |
| 8086:0f18 | 1179:f91b | Intel      | Atom Processor Z36xxx/Z37... | 38    | mei_txe    | 0914AEED54 |
| 1022:15df | 1025:142b | AMD        | Family 17h (Models 10h-1f... | 37    | ccp        | BCE3E39F4C |
| 8086:0f18 | 1025:0936 | Intel      | Atom Processor Z36xxx/Z37... | 37    | mei_txe    | AA7DD43B73 |
| 8086:2298 | 17aa:380a | Intel      | Atom/Celeron/Pentium Proc... | 37    | mei_txe    | 71506FF3BD |
| 1022:15df | 103c:84e7 | AMD        | Family 17h (Models 10h-1f... | 36    | ccp        | CF69BD4423 |
| 1022:15df | 17aa:3809 | AMD        | Family 17h (Models 10h-1f... | 36    | ccp        | 0C3651AF28 |
| 8086:0f18 | 1458:1c3a | Intel      | Atom Processor Z36xxx/Z37... | 35    | mei_txe    | D34B6CFE65 |
| 8086:2298 | 17aa:380c | Intel      | Atom/Celeron/Pentium Proc... | 35    | mei_txe    | F45A93E403 |
| 8086:2298 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 35    | mei_txe    | 127B977658 |
| 1022:1537 | 1025:104b | AMD        | Kabini/Mullins PSP-Platfo... | 34    | ccp        | C6582BBA7D |
| 1022:15df | 103c:86fd | AMD        | Family 17h (Models 10h-1f... | 34    | ccp        | 5BB4E443F9 |
| 1022:15df | 103c:876f | AMD        | Family 17h (Models 10h-1f... | 34    | ccp        | 5F67B298AB |
| 1022:1537 | 1025:108a | AMD        | Kabini/Mullins PSP-Platfo... | 33    | ccp        | CFA7B4AF8F |
| 1022:1578 | 17aa:380c | AMD        | Carrizo Platform Security... | 33    |            | E4AA5740C5 |
| 1022:15df | 17aa:3804 | AMD        | Family 17h (Models 10h-1f... | 33    | ccp        | C3F376B088 |
| 8086:2298 | 103c:813e | Intel      | Atom/Celeron/Pentium Proc... | 33    | mei_txe    | 0A44B96544 |
| 8086:0f18 | 103c:21de | Intel      | Atom Processor Z36xxx/Z37... | 32    | mei_txe    | A9F0EC716F |
| 8086:2298 | 103c:80c5 | Intel      | Atom/Celeron/Pentium Proc... | 31    | mei_txe    | 2CF6464047 |
| 1022:1578 | 103c:8333 | AMD        | Carrizo Platform Security... | 30    |            | 57EE9BD872 |
| 1022:15df | 1025:134f | AMD        | Family 17h (Models 10h-1f... | 30    | ccp        | 5EDDDC1E2C |
| 1022:15df | 1025:1461 | AMD        | Family 17h (Models 10h-1f... | 30    | ccp        | 264BADF289 |
| 8086:0f18 | 1043:15bd | Intel      | Atom Processor Z36xxx/Z37... | 30    | mei_txe    | 7373CE3DBF |
| 1022:15df | 103c:85b3 | AMD        | Family 17h (Models 10h-1f... | 29    | ccp        | AE1811A242 |
| 1022:15df | 1462:7a38 | AMD        | Family 17h (Models 10h-1f... | 29    | ccp        | B914028CA9 |
| 8086:2298 | 103c:82bd | Intel      | Atom/Celeron/Pentium Proc... | 29    | mei_txe    | 09D2CE45B4 |
| 1022:1486 | 1462:7a38 | AMD        | Starship/Matisse Cryptogr... | 28    | ccp        | 11F7EC8B16 |
| 1022:1578 | 17aa:380b | AMD        | Carrizo Platform Security... | 28    |            | 85036968BB |
| 1022:15df | 1025:125c | AMD        | Family 17h (Models 10h-1f... | 28    | ccp        | 2FF605BDB0 |
| 8086:0f18 |           | Intel      | Atom Processor Z36xxx/Z37... | 28    | mei_txe    | 5900E800AA |
| 8086:2298 | 1043:12e0 | Intel      | Atom/Celeron/Pentium Proc... | 28    | mei_txe    | ED8BB15F60 |
| 8086:2298 | 1043:191d | Intel      | Atom/Celeron/Pentium Proc... | 28    | mei_txe    | 9B5B69452D |
| 1022:1456 | 1462:7a38 | AMD        | Family 17h (Models 00h-0f... | 27    | ccp        | 276D5FE9E3 |
| 1022:1578 | 103c:8331 | AMD        | Carrizo Platform Security... | 27    |            | F60949A3CC |
| 1022:15df | 17aa:5125 | AMD        | Family 17h (Models 10h-1f... | 27    | ccp        | 8E00E1F239 |
| 8086:2298 | 1849:2298 | Intel      | Atom/Celeron/Pentium Proc... | 27    | mei_txe    | 6E3084CF7F |
| 1022:1486 | 1462:7c94 | AMD        | Starship/Matisse Cryptogr... | 26    | ccp        | 08819513F2 |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1106:3044 | 1043:81fe | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 814   | firewir... | 588CEFB67B |
| 104c:8024 | 1458:1000 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 769   | firewir... | 370AD865CF |
| 11c1:5901 | 11c1:5900 | LSI        | FW643 [TrueFire] PCIe 139... | 735   | firewir... | 6E17FB6EA4 |
| 1180:0832 | 17aa:20c7 | Ricoh      | R5C832 IEEE 1394 Controller  | 294   | firewir... | 9A7BE426F5 |
| 1106:3044 | 1458:1000 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 272   | firewir... | 61D5F808B5 |
| 1106:3403 | 1043:8384 | VIA Tec... | VT6315 Series Firewire Co... | 269   | firewir... | 0C14FFD402 |
| 1106:3044 | 1106:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 222   | firewir... | AAE0C56D3A |
| 11c1:5811 | 1043:8294 | LSI        | FW322/323 [TrueFire] 1394... | 220   | firewir... | F6317B60DD |
| 104c:823f |           | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 201   | firewir... | BD1CB6F826 |
| 11c1:5811 | 11c1:5811 | LSI        | FW322/323 [TrueFire] 1394... | 182   | firewir... | D4C089BC2F |
| 1180:e832 | 17aa:2136 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 175   | firewir... | 8B21B7CFFE |
| 1102:4001 | 1102:0010 | Creativ... | SB Audigy FireWire Port      | 167   | firewir... | E04A41FC30 |
| 1180:e832 | 1028:040a | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 138   | firewir... | BA51FC9216 |
| 104c:803a | 1025:011f | Texas I... | PCIxx12 OHCI Compliant IE... | 135   | firewir... | 8592F1650F |
| 1106:3403 | 1849:3403 | VIA Tec... | VT6315 Series Firewire Co... | 132   | firewir... | 85B942A5C3 |
| 1180:0832 | 1028:0233 | Ricoh      | R5C832 IEEE 1394 Controller  | 124   | firewir... | 6B7EF9CAD5 |
| 197b:2380 | 103c:161c | JMicron... | IEEE 1394 Host Controller    | 112   | firewir... | B6AC4539D1 |
| 104c:803a | 1179:ff00 | Texas I... | PCIxx12 OHCI Compliant IE... | 103   | firewir... | 1BF61C0698 |
| 197b:2380 | 103c:179b | JMicron... | IEEE 1394 Host Controller    | 101   | firewir... | 1B2FBCDFA0 |
| 104c:8023 | 1043:808b | Texas I... | TSB43AB22A IEEE-1394a-200... | 100   | firewir... | 1B7F4401BE |
| 1180:e832 | 17aa:21cf | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 97    | firewir... | 4104E265EA |
| 1217:00f7 | 1028:01f9 | O2 Micro   | Firewire (IEEE 1394)         | 92    | firewir... | 6DBCD5A1C8 |
| 1180:0832 | 1028:022f | Ricoh      | R5C832 IEEE 1394 Controller  | 83    | firewir... | ED2467DC52 |
| 1180:e832 | 17aa:21f6 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 79    | firewir... | 69A252CCD6 |
| 1180:0832 | 103c:30cc | Ricoh      | R5C832 IEEE 1394 Controller  | 73    | firewir... | DD3C7EF3E7 |
| 197b:2380 | 1043:8313 | JMicron... | IEEE 1394 Host Controller    | 69    | firewir... | 0228A60CDE |
| 1180:0832 | 103c:172a | Ricoh      | R5C832 IEEE 1394 Controller  | 65    | firewir... | F527983CC9 |
| 1217:00f7 | 1179:ff50 | O2 Micro   | Firewire (IEEE 1394)         | 60    | firewir... | ABCF2EEE75 |
| 1217:13f7 | 1028:0494 | O2 Micro   | 1394 OHCI Compliant Host ... | 60    | firewir... | B84EF4472B |
| 11c1:5811 | 103c:2a6f | LSI        | FW322/323 [TrueFire] 1394... | 59    | firewir... | D5D1B22B75 |
| 1106:3403 | 103c:2a9c | VIA Tec... | VT6315 Series Firewire Co... | 58    | firewir... | 2F752A1A3E |
| 1106:3403 | 1043:8374 | VIA Tec... | VT6315 Series Firewire Co... | 55    | firewir... | 03B2C2E1AF |
| 104c:8023 | 1043:815b | Texas I... | TSB43AB22A IEEE-1394a-200... | 54    | firewir... | A402BB261D |
| 1180:e832 | 17aa:21ce | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 54    | firewir... | 002840EA37 |
| 1180:e832 | 1028:040b | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 53    | firewir... | 2AB208B5CD |
| 1217:00f7 | 1217:00f7 | O2 Micro   | Firewire (IEEE 1394)         | 53    | firewir... | F1770353A3 |
| 197b:2380 | 103c:3628 | JMicron... | IEEE 1394 Host Controller    | 49    | firewir... | 2992DD1DF0 |
| 1180:0832 | 1028:024f | Ricoh      | R5C832 IEEE 1394 Controller  | 48    | firewir... | E475348B1E |
| 104c:8025 |           | Texas I... | TSB82AA2 IEEE-1394b Link ... | 47    | firewir... | 1E34F92251 |
| 1180:0832 | 1025:011e | Ricoh      | R5C832 IEEE 1394 Controller  | 47    | firewir... | 6472272BF7 |
| 1180:0832 | 103c:7008 | Ricoh      | R5C832 IEEE 1394 Controller  | 47    | firewir... | F31AC36B11 |
| 11c1:5811 | 103c:1309 | LSI        | FW322/323 [TrueFire] 1394... | 47    | firewir... | EB0C052885 |
| 1106:3403 | 1106:3403 | VIA Tec... | VT6315 Series Firewire Co... | 45    | firewir... | 138DF954CB |
| 1180:0832 | 103c:30c0 | Ricoh      | R5C832 IEEE 1394 Controller  | 44    | firewir... | 51AB06C26F |
| 1180:0832 | 103c:30cf | Ricoh      | R5C832 IEEE 1394 Controller  | 44    | firewir... | 8774B51F01 |
| 11c1:5811 | 103c:1589 | LSI        | FW322/323 [TrueFire] 1394... | 43    | firewir... | 49C747EFAD |
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
| 104c:8023 | 8086:5044 | Texas I... | TSB43AB22A IEEE-1394a-200... | 34    | firewir... | A5121E1871 |
| 1180:0832 | 103c:30bb | Ricoh      | R5C832 IEEE 1394 Controller  | 34    | firewir... | 944D6AF89A |
| 1180:0832 | 1043:1877 | Ricoh      | R5C832 IEEE 1394 Controller  | 34    | firewir... | 843C7A8519 |
| 104c:823f | 3412:7856 | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 33    | firewir... | 6861CB8EBD |
| 197b:2380 | 103c:161d | JMicron... | IEEE 1394 Host Controller    | 33    | firewir... | 317C62DF4B |
| 1106:3044 | 1043:808a | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 32    | firewir... | B38568681E |
| 1106:3044 | 1849:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 32    | firewir... | C5E2E9E4A4 |
| 1180:0832 | 1025:0126 | Ricoh      | R5C832 IEEE 1394 Controller  | 31    | firewir... | AA6D721BF2 |
| 104c:803a | 104d:9015 | Texas I... | PCIxx12 OHCI Compliant IE... | 30    | firewir... | 538C03B235 |
| 1180:0832 | 1028:0263 | Ricoh      | R5C832 IEEE 1394 Controller  | 30    | firewir... | 286C99863B |
| 104c:8023 | 8086:514d | Texas I... | TSB43AB22A IEEE-1394a-200... | 28    | firewir... | D3F38DBF63 |
| 104c:803a | 104d:902d | Texas I... | PCIxx12 OHCI Compliant IE... | 28    | firewir... | F76AE4B159 |
| 11c1:5811 | 103c:130b | LSI        | FW322/323 [TrueFire] 1394... | 28    | firewir... | 665BAE2867 |
| 11c1:5811 | 103c:158a | LSI        | FW322/323 [TrueFire] 1394... | 28    | firewir... | 6C22E51BFC |
| 197b:2380 | 103c:3603 | JMicron... | IEEE 1394 Host Controller    | 28    | firewir... | 74CEE5B7A8 |
| 104c:803a | 1179:0001 | Texas I... | PCIxx12 OHCI Compliant IE... | 27    | firewir... | DF9FBBE08C |
| 197b:2380 | 103c:179c | JMicron... | IEEE 1394 Host Controller    | 27    | firewir... | 7AA667BA1A |
| 1180:0832 | 103c:30c5 | Ricoh      | R5C832 IEEE 1394 Controller  | 25    | firewir... | CBF5040FF7 |
| 197b:2380 | 103c:176b | JMicron... | IEEE 1394 Host Controller    | 25    | firewir... | 492907A363 |
| 1180:0832 | 1179:ff1e | Ricoh      | R5C832 IEEE 1394 Controller  | 24    | firewir... | C5391FAE24 |
| 1180:0832 | 17aa:2109 | Ricoh      | R5C832 IEEE 1394 Controller  | 24    | firewir... | BFBAB4F2DB |
| 11c1:5811 | 1028:5811 | LSI        | FW322/323 [TrueFire] 1394... | 24    | firewir... | FF796824D2 |
| 11c1:5811 | 103c:130a | LSI        | FW322/323 [TrueFire] 1394... | 24    | firewir... | 328FCB35ED |
| 197b:2380 | 103c:1631 | JMicron... | IEEE 1394 Host Controller    | 24    | firewir... | 98BD384A42 |
| 197b:2380 | 103c:30f4 | JMicron... | IEEE 1394 Host Controller    | 24    | firewir... | F4BFA397A6 |
| 197b:2380 | 103c:3659 | JMicron... | IEEE 1394 Host Controller    | 24    | firewir... | 4DD419063F |
| 1180:e832 | 1028:0429 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 23    | firewir... | A2E097AFE4 |
| 1180:e832 | 104d:9089 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 23    | firewir... | BCA5866F5E |
| 1217:00f7 | 1028:01fe | O2 Micro   | Firewire (IEEE 1394)         | 23    | firewir... | DAD4FD9AFE |
| 1217:00f7 | 10cf:14d7 | O2 Micro   | Firewire (IEEE 1394)         | 23    | firewir... | 08576DED50 |
| 104c:8023 | 8086:4257 | Texas I... | TSB43AB22A IEEE-1394a-200... | 22    | firewir... | D4B171DC3D |
| 1180:0832 | 1043:14e7 | Ricoh      | R5C832 IEEE 1394 Controller  | 22    | firewir... | 2494100ECB |
| 1180:0832 | 1179:ff1c | Ricoh      | R5C832 IEEE 1394 Controller  | 22    | firewir... | 8B7FBF3DE6 |
| 11c1:5811 | 1028:8010 | LSI        | FW322/323 [TrueFire] 1394... | 22    | firewir... | 25E00FC504 |
| 11c1:5811 | 103c:158b | LSI        | FW322/323 [TrueFire] 1394... | 22    | firewir... | 24399F4E69 |
| 104c:8023 | 1028:026d | Texas I... | TSB43AB22A IEEE-1394a-200... | 21    | firewir... | 2F188B606A |

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
| 1524:0510 | 1524:0510 | ENE Tec... | CB710 Memory Card Reader ... | 3     | cb710      | 1312407631 |
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
| 1524:0730 | 1558:0721 | ENE Tec... | ENE PCI Memory Stick Card... | 1     |            | A52F0F2D7C |
| 1524:0751 | 1025:012a | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | C95503E7D2 |
| 1524:0751 | 1558:0573 | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | 95780C2963 |
| 1524:0751 | 1558:0664 | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | 51E2E84C28 |
| 1524:0751 | 1558:0668 | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | 41C9811E8B |
| 1524:0751 | 1558:0721 | ENE Tec... | ENE PCI Secure Digital / ... | 1     | sdhci_pci  | A52F0F2D7C |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1451 | 1022:1451 | AMD        | Family 17h (Models 00h-0f... | 1448  |            | E52E9002D0 |
| 1022:1577 | 1022:1577 | AMD        | Family 15h (Models 60h-6f... | 571   |            | 34F2870A95 |
| 1002:5a23 | 1002:5a23 | AMD        | RD890S/RD990 I/O Memory M... | 474   |            | E648F33A2F |
| 1022:1419 | 1022:1419 | AMD        | Family 15h (Models 10h-1f... | 263   |            | 2BC95C7D30 |
| 1002:5a23 | 1462:7693 | AMD        | RD890S/RD990 I/O Memory M... | 151   |            | DEC7AC6A34 |
| 1022:1423 | 1022:1423 | AMD        | Family 15h (Models 30h-3f... | 88    |            | B676D9030A |
| 1022:1419 | 1462:7721 | AMD        | Family 15h (Models 10h-1f... | 55    |            | 69DA26C946 |
| 1022:1423 | 1462:7721 | AMD        | Family 15h (Models 30h-3f... | 39    |            | 3797338B82 |
| 1022:1577 | 103c:8331 | AMD        | Family 15h (Models 60h-6f... | 27    |            | F60949A3CC |
| 1022:1423 | 1043:85cb | AMD        | Family 15h (Models 30h-3f... | 24    |            | 00C624B592 |
| 1002:5a23 | 1458:5000 | AMD        | RD890S/RD990 I/O Memory M... | 17    |            | FACB3C762D |
| 1002:5a23 | 1462:7640 | AMD        | RD890S/RD990 I/O Memory M... | 17    |            | 6FE8EFAC3A |
| 1022:1419 | 1462:7895 | AMD        | Family 15h (Models 10h-1f... | 15    |            | 4DC951C5ED |
| 1022:1577 | 103c:81fa | AMD        | Family 15h (Models 60h-6f... | 14    |            | 11013F1334 |
| 1002:5a23 | 1462:7974 | AMD        | RD890S/RD990 I/O Memory M... | 11    |            | 854EEB3251 |
| 1022:1419 | 1043:8526 | AMD        | Family 15h (Models 10h-1f... | 9     |            | 4F9F3CBB83 |
| 1022:1423 | 1462:7895 | AMD        | Family 15h (Models 30h-3f... | 9     |            | 8CF59588A3 |
| 1022:1577 | 103c:80b5 | AMD        | Family 15h (Models 60h-6f... | 8     |            | 846B2E2A87 |
| 1022:1423 | 103c:812f | AMD        | Family 15h (Models 30h-3f... | 7     |            | 59A4CFC209 |
| 1022:1419 | 1019:7c8d | AMD        | Family 15h (Models 10h-1f... | 4     |            | F04221E5DE |
| 1022:1419 | 1025:070b | AMD        | Family 15h (Models 10h-1f... | 4     |            | C87047835B |
| 1022:1419 | 1462:7900 | AMD        | Family 15h (Models 10h-1f... | 3     |            | A0CBC39688 |
| 8086:19a2 | 8086:19a2 | Intel      | Atom Processor C3000 Seri... | 3     |            | 2B7A8BA5FC |
| 1022:1423 | 1462:7793 | AMD        | Family 15h (Models 30h-3f... | 2     |            | 709AAC26C8 |
| 1022:1577 | 103c:80b6 | AMD        | Family 15h (Models 60h-6f... | 2     |            | BEA3C73273 |
| 1022:1577 | 103c:8355 | AMD        | Family 15h (Models 60h-6f... | 2     |            | D6F5348EC7 |
| 8086:0b23 | 8086:0000 | Intel      | Generic system peripheral    | 2     | pcieport   | AEAD99F55D |
| 8086:0b23 | 8086:7270 | Intel      | Generic system peripheral    | 2     | pcieport   | AEAD99F55D |
| 8086:19a2 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 2     | pcieport   | 40E07B4DAD |
| 1022:1419 | 17aa:36a0 | AMD        | Family 15h (Models 10h-1f... | 1     |            | BA1A484E84 |
| 1022:1423 | 17aa:368f | AMD        | Family 15h (Models 30h-3f... | 1     |            | 58DDD6F565 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 606   | i915       | 2FBF6F153B |
| 8086:0412 | 1458:d000 | Intel      | Xeon E3-1200 v3/4th Gen C... | 452   | i915       | EB596B1774 |
| 10de:128b | 1462:8c93 | Nvidia     | GK208B [GeForce GT 710]      | 425   | nouveau    | 0233AE7054 |
| 8086:0412 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 304   | i915       | 2253D95E90 |
| 1002:67df | 1da2:e366 | AMD        | Ellesmere [Radeon RX 470/... | 262   | amdgpu     | 9FED362DDE |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics 500              | 251   | i915       | 6121781D85 |
| 8086:0046 | 17aa:215a | Intel      | Core Processor Integrated... | 240   | i915       | 570863FD8C |
| 8086:0f31 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 235   | i915       | D04BD787B3 |
| 8086:0102 | 1043:844d | Intel      | 2nd Generation Core Proce... | 225   | i915       | F31E6E3DD0 |
| 8086:0102 | 1458:d000 | Intel      | 2nd Generation Core Proce... | 212   | i915       | 9FC60B0BA8 |
| 1002:15d8 | 1002:15d8 | AMD        | Picasso                      | 210   | amdgpu     | 1FB86737FD |
| 8086:2a42 | 17aa:20e4 | Intel      | Mobile 4 Series Chipset I... | 206   | i915       | 9A7BE426F5 |
| 8086:2a43 | 17aa:20e4 | Intel      | Mobile 4 Series Chipset I... | 206   |            | 9A7BE426F5 |
| 1002:9616 | 1043:8388 | AMD        | RS780L [Radeon 3000]         | 199   | radeon     | 24FE21040D |
| 8086:1912 | 1043:8694 | Intel      | HD Graphics 530              | 195   | i915       | 07067FE66C |
| 1002:15dd | 1002:15dd | AMD        | Raven Ridge [Radeon Vega ... | 188   | amdgpu     | CF804488DD |
| 8086:0152 | 1458:d000 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 181   | i915       | 042607D7F1 |
| 1002:67df | 1682:c580 | AMD        | Ellesmere [Radeon RX 470/... | 165   | amdgpu     | 161865EDB0 |
| 8086:0166 | 17aa:21fa | Intel      | 3rd Gen Core processor Gr... | 164   | i915       | EC8AF5F350 |
| 8086:0166 | 17aa:21f3 | Intel      | 3rd Gen Core processor Gr... | 162   | i915       | C9D8EFC9B9 |
| 8086:3e9b | 1025:1331 | Intel      | CoffeeLake-H GT2 [UHD Gra... | 157   | i915       | BC9DC107D1 |
| 8086:3185 | 8086:2212 | Intel      | GeminiLake [UHD Graphics ... | 156   | i915       | F40D5FD5A7 |
| 8086:5912 | 1043:8694 | Intel      | HD Graphics 630              | 153   | i915       | BA3DDF870D |
| 1002:67df | 1da2:e353 | AMD        | Ellesmere [Radeon RX 470/... | 149   | amdgpu     | C483A48272 |
| 10de:1d01 | 1462:8c98 | Nvidia     | GP108 [GeForce GT 1030]      | 149   | nvidia     | 9753F223E2 |
| 8086:a011 | 1043:83ac | Intel      | Atom Processor D4xx/D5xx/... | 148   | i915       | E74DC83F0A |
| 8086:a012 | 1043:83ac | Intel      | Atom Processor D4xx/D5xx/... | 148   |            | E74DC83F0A |
| 10de:0a65 |           | Nvidia     | GT218 [GeForce 210]          | 144   | nouveau    | 0582E2316B |
| 10de:1c82 | 1462:8c96 | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 143   | nvidia     | E1B966B80D |
| 8086:3e9b | 1028:0905 | Intel      | CoffeeLake-H GT2 [UHD Gra... | 142   | i915       | 58E43F0514 |
| 8086:29c2 | 1043:82b0 | Intel      | 82G33/G31 Express Integra... | 140   | i915       | EE4F0F6F02 |
| 8086:2e32 | 1043:836d | Intel      | 4 Series Chipset Integrat... | 138   | i915       | FEAC57A6E7 |
| 10de:1f91 | 1025:1332 | Nvidia     | TU117M [GeForce GTX 1650 ... | 137   | nvidia     | BC9DC107D1 |
| 10de:1f91 | 1028:0905 | Nvidia     | TU117M [GeForce GTX 1650 ... | 133   | nvidia     | 58E43F0514 |
| 8086:0166 | 1028:0534 | Intel      | 3rd Gen Core processor Gr... | 133   | i915       | FA4D12994D |
| 8086:0126 | 17aa:21ce | Intel      | 2nd Generation Core Proce... | 132   | i915       | A75FFD5203 |
| 8086:0166 | 17aa:3977 | Intel      | 3rd Gen Core processor Gr... | 132   | i915       | 6B1D1F059F |
| 1002:9616 | 1458:d000 | AMD        | RS780L [Radeon 3000]         | 131   | radeon     | 545DC9A3E0 |
| 8086:2a42 | 1043:1862 | Intel      | Mobile 4 Series Chipset I... | 131   | i915       | 84F6267AD8 |
| 8086:2a43 | 1043:1862 | Intel      | Mobile 4 Series Chipset I... | 131   |            | 84F6267AD8 |
| 1002:67df | 1462:341b | AMD        | Ellesmere [Radeon RX 470/... | 130   | amdgpu     | 61823FB44E |
| 8086:3ea5 | 8086:2074 | Intel      | CoffeeLake-U GT3e [Iris P... | 130   | i915       | 7EEEAAA250 |
| 1002:15dd | 1043:876b | AMD        | Raven Ridge [Radeon Vega ... | 128   | amdgpu     | 19EBA77C24 |
| 8086:0a16 | 17aa:220c | Intel      | Haswell-ULT Integrated Gr... | 127   | i915       | 415CC7FE56 |
| 8086:0152 | 1043:844d | Intel      | Xeon E3-1200 v2/3rd Gen C... | 124   | i915       | E8AD89CB87 |
| 1002:67df | 1462:3418 | AMD        | Ellesmere [Radeon RX 470/... | 123   | amdgpu     | 1F83ADD647 |
| 10de:03d6 | 1849:03d6 | Nvidia     | C61 [GeForce 7025 / nForc... | 123   | nouveau    | 090662DCD6 |
| 8086:0126 | 1028:0493 | Intel      | 2nd Generation Core Proce... | 123   | i915       | DC9A1E9C1B |
| 8086:1916 | 103c:8079 | Intel      | Skylake GT2 [HD Graphics ... | 123   | i915       | 436E9BF227 |
| 8086:2a02 | 17aa:20b5 | Intel      | Mobile GM965/GL960 Integr... | 123   | i915       | EE90608B54 |
| 8086:2a03 | 17aa:20b5 | Intel      | Mobile GM965/GL960 Integr... | 123   |            | EE90608B54 |
| 8086:1626 | 106b:011b | Intel      | HD Graphics 6000             | 122   | i915       | 5BE083EDAB |
| 1002:98e4 | 103c:8330 | AMD        | Stoney [Radeon R2/R3/R4/R... | 120   | amdgpu     | 18CEA74915 |
| 8086:0126 | 17aa:21da | Intel      | 2nd Generation Core Proce... | 120   | i915       | 402DDBAA44 |
| 8086:0a16 | 17aa:3978 | Intel      | Haswell-ULT Integrated Gr... | 119   | i915       | 2519EFDF20 |
| 10de:0640 |           | Nvidia     | G96C [GeForce 9500 GT]       | 117   | nouveau    | 0F15DCBAA1 |
| 8086:2a42 | 17aa:3a02 | Intel      | Mobile 4 Series Chipset I... | 116   | i915       | B9412E1AB2 |
| 8086:2a43 | 17aa:3a02 | Intel      | Mobile 4 Series Chipset I... | 116   |            | B9412E1AB2 |
| 8086:0106 | 1025:0649 | Intel      | 2nd Generation Core Proce... | 115   | i915       | 82E60126C9 |
| 8086:0a16 | 103c:198f | Intel      | Haswell-ULT Integrated Gr... | 115   | i915       | CECD552E89 |
| 8086:3e9b | 1028:087c | Intel      | CoffeeLake-H GT2 [UHD Gra... | 114   | i915       | 0FA8C3ED0C |
| 8086:0116 | 1025:0504 | Intel      | 2nd Generation Core Proce... | 113   | i915       | B66EB36016 |
| 8086:a011 | 1025:0349 | Intel      | Atom Processor D4xx/D5xx/... | 112   | i915       | 09B8FC981C |
| 8086:a012 | 1025:0349 | Intel      | Atom Processor D4xx/D5xx/... | 112   |            | 09B8FC981C |
| 1002:15d8 | 1043:876b | AMD        | Picasso                      | 111   | amdgpu     | 24974BE67E |
| 8086:0162 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 111   | i915       | E59D042DA2 |
| 8086:0402 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 111   | i915       | 352946E177 |
| 8086:0402 | 1458:d000 | Intel      | Xeon E3-1200 v3/4th Gen C... | 111   | i915       | 5EAD0CA3AD |
| 8086:3ea0 | 103c:8549 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 111   | i915       | A814284F0B |
| 8086:0166 | 106b:00fa | Intel      | 3rd Gen Core processor Gr... | 110   | i915       | 783D081B5A |
| 8086:3185 | 1043:1261 | Intel      | GeminiLake [UHD Graphics ... | 109   | i915       | 985D10D314 |
| 8086:041e | 1458:d000 | Intel      | 4th Generation Core Proce... | 108   | i915       | CE787D81EF |
| 8086:29c2 | 1458:d000 | Intel      | 82G33/G31 Express Integra... | 108   | i915       | 370AD865CF |
| 8086:5917 | 1028:0810 | Intel      | UHD Graphics 620             | 108   | i915       | C01FA4B013 |
| 8086:0152 | 1028:0577 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 107   | i915       | 00FE3AD0A4 |
| 8086:0a16 | 1025:0866 | Intel      | Haswell-ULT Integrated Gr... | 107   | i915       | 11EBF2008B |
| 8086:2e32 | 1458:d000 | Intel      | 4 Series Chipset Integrat... | 107   | i915       | E77D7B4B45 |
| 8086:0f31 | 17aa:3905 | Intel      | Atom Processor Z36xxx/Z37... | 106   | i915       | 1387FAB9FE |
| 8086:2a42 | 1028:02aa | Intel      | Mobile 4 Series Chipset I... | 106   | i915       | E8E9A85406 |
| 8086:2a43 | 1028:02aa | Intel      | Mobile 4 Series Chipset I... | 106   |            | E8E9A85406 |
| 8086:2e12 | 1028:0420 | Intel      | 4 Series Chipset Integrat... | 106   | i915       | C67A8BB677 |
| 8086:2e13 | 1028:0420 | Intel      | 4 Series Chipset Integrat... | 106   |            | C67A8BB677 |
| 10de:1c8c | 1028:087c | Nvidia     | GP107M [GeForce GTX 1050 ... | 105   | nvidia     | 0FA8C3ED0C |
| 8086:0126 | 106b:00db | Intel      | 2nd Generation Core Proce... | 105   | i915       | 6E17FB6EA4 |
| 8086:2a02 | 1025:011f | Intel      | Mobile GM965/GL960 Integr... | 105   | i915       | 8592F1650F |
| 8086:2a03 | 1025:011f | Intel      | Mobile GM965/GL960 Integr... | 105   |            | 8592F1650F |
| 8086:0166 | 1025:0647 | Intel      | 3rd Gen Core processor Gr... | 103   | i915       | 8BC152AA27 |
| 8086:3ea0 | 17aa:2292 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 103   | i915       | 26C62915E0 |
| 10de:0a65 | 1462:8094 | Nvidia     | GT218 [GeForce 210]          | 102   | nouveau    | D9C192EA8C |
| 8086:3e92 | 1043:8694 | Intel      | CometLake-S GT2 [UHD Grap... | 101   | i915       | 9F69E439BC |
| 10de:0622 |           | Nvidia     | G94 [GeForce 9600 GT]        | 100   | nouveau    | 1157C2A82C |
| 8086:0412 | 1849:0412 | Intel      | Xeon E3-1200 v3/4th Gen C... | 100   | i915       | 111E98DDEF |
| 8086:041e | 1043:8534 | Intel      | 4th Generation Core Proce... | 100   | i915       | 7A6479DC2D |
| 1a03:2000 | 1a03:2000 | ASPEED ... | ASPEED Graphics Family       | 99    | ast        | BDE0BE6A50 |
| 8086:5917 | 1028:07e6 | Intel      | UHD Graphics 620             | 99    | i915       | 5A56854746 |
| 8086:591b | 1028:07be | Intel      | HD Graphics 630              | 99    | i915       | 69938C221E |
| 8086:0166 | 1043:124d | Intel      | 3rd Gen Core processor Gr... | 98    | i915       | 15E808F714 |
| 8086:0412 | 1028:05a4 | Intel      | Xeon E3-1200 v3/4th Gen C... | 98    | i915       | E04A41FC30 |
| 8086:2772 | 1043:817a | Intel      | 82945G/GZ Integrated Grap... | 97    | i915       | 6B722285DD |
| 10de:13c2 | 1462:3160 | Nvidia     | GM204 [GeForce GTX 970]      | 96    | nvidia     | 77006702F8 |

### Input device controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1102:7002 | 1102:0020 | Creativ... | SB Live! Game Port           | 180   | emu10k1_gp | 35D876D2DC |
| 1102:7003 | 1102:0040 | Creativ... | SB Audigy Game Port          | 129   | emu10k1_gp | 0E8D69E9B8 |
| 1102:7003 | 1102:0060 | Creativ... | SB Audigy Game Port          | 27    | emu10k1_gp | 4970AA3AFB |
| 1102:7004 | 1102:1003 | Creativ... | [SB Live! Value] Input de... | 10    | emu10k1_gp | 1661F6766F |
| 1319:0802 | 1319:1319 | Fortemedia | Xwave QS3000A [FM801 game... | 8     | fm801_gp   | CE881D4659 |
| 1102:7005 | 1102:1002 | Creativ... | SB Audigy LS Game Port       | 4     | emu10k1_gp | A0BD55A486 |
| 127a:4312 | 1235:4312 | Rockwel... | Riptide PCI Game Controller  | 1     | snd_rip... | 34867AD122 |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 2109  |            | D3A9F1CE6E |
| 1022:1481 | 1022:1481 | AMD        | Starship/Matisse IOMMU       | 1212  |            | 93DE1508CB |
| 1022:1451 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 800   |            | 491D1A96CC |
| 1022:1481 | 1043:87c0 | AMD        | Starship/Matisse IOMMU       | 733   |            | 161865EDB0 |
| 1022:1631 | 1022:1631 | AMD        | Renoir/Cezanne IOMMU         | 677   |            | 8948989999 |
| 1022:1481 | 1043:8808 | AMD        | Starship/Matisse IOMMU       | 164   |            | A525C8911B |
| 1022:1577 | 103c:8330 | AMD        | Family 15h (Models 60h-6f... | 120   |            | 18CEA74915 |
| 1022:15d1 | 1043:876b | AMD        | Raven/Raven2 IOMMU           | 111   |            | 24974BE67E |
| 1022:1481 | 1462:7c02 | AMD        | Starship/Matisse IOMMU       | 96    |            | 9BCD3D5479 |
| 1022:1631 | 17aa:5081 | AMD        | Renoir/Cezanne IOMMU         | 90    |            | 273A5FF27D |
| 1022:1577 | 103c:84ac | AMD        | Family 15h (Models 60h-6f... | 87    |            | 3A06ECCCAA |
| 1022:1577 | 1025:1192 | AMD        | Family 15h (Models 60h-6f... | 78    |            | F5F4E2457B |
| 1022:1631 | 17aa:507f | AMD        | Renoir/Cezanne IOMMU         | 75    |            | 8A34D739FD |
| 1022:1631 | 17aa:3803 | AMD        | Renoir/Cezanne IOMMU         | 70    |            | 3CDC08297E |
| 1022:1481 | 1462:7b86 | AMD        | Starship/Matisse IOMMU       | 65    |            | 7E563A9D44 |
| 1022:15d1 | 1025:1366 | AMD        | Raven/Raven2 IOMMU           | 61    |            | BCC833AC3C |
| 1022:1451 | 1462:7c02 | AMD        | Family 17h (Models 00h-0f... | 59    |            | F50B61B450 |
| 1022:15d1 | 1025:134d | AMD        | Raven/Raven2 IOMMU           | 59    |            | 6134BF279A |
| 1022:15d1 | 103c:84ae | AMD        | Raven/Raven2 IOMMU           | 58    |            | 2E3861AEF3 |
| 1022:15d1 | 17aa:380a | AMD        | Raven/Raven2 IOMMU           | 58    |            | 3F7C00C1EF |
| 1022:1577 | 17aa:380e | AMD        | Family 15h (Models 60h-6f... | 53    |            | 0036C99447 |
| 1022:1631 | 17aa:5082 | AMD        | Renoir/Cezanne IOMMU         | 51    |            | 037A558C7D |
| 1022:15d1 | 17aa:380b | AMD        | Raven/Raven2 IOMMU           | 47    |            | 09ADDF2612 |
| 1022:1451 | 1462:7b86 | AMD        | Family 17h (Models 00h-0f... | 46    |            | F17090E5D2 |
| 1022:1481 | 1462:7c35 | AMD        | Starship/Matisse IOMMU       | 46    |            | 8EA75A2EC0 |
| 1022:1481 | 1462:7b89 | AMD        | Starship/Matisse IOMMU       | 45    |            | A72102FDB0 |
| 1022:15d1 | 103c:8615 | AMD        | Raven/Raven2 IOMMU           | 45    |            | 406FCB6975 |
| 1022:1631 | 1d05:109f | AMD        | Renoir/Cezanne IOMMU         | 45    |            | 7242436545 |
| 1022:15d1 | 1025:1259 | AMD        | Raven/Raven2 IOMMU           | 44    |            | 3D5D3DDF84 |
| 1022:1631 | 17aa:380a | AMD        | Renoir/Cezanne IOMMU         | 40    |            | 86BC5DDC56 |
| 1022:1631 | 17aa:507e | AMD        | Renoir/Cezanne IOMMU         | 39    |            | E9A8FB1275 |
| 1022:1419 | 103c:1850 | AMD        | Family 15h (Models 10h-1f... | 38    |            | E8C750C4B9 |
| 1022:15d1 | 103c:85ea | AMD        | Raven/Raven2 IOMMU           | 38    |            | E8781DB5AB |
| 1022:1631 | 103c:876e | AMD        | Renoir/Cezanne IOMMU         | 38    |            | 28B152BB19 |
| 1022:1631 | 1025:142b | AMD        | Renoir/Cezanne IOMMU         | 37    |            | BCE3E39F4C |
| 1022:15d1 | 103c:84e7 | AMD        | Raven/Raven2 IOMMU           | 36    |            | CF69BD4423 |
| 1022:15d1 | 17aa:3804 | AMD        | Raven/Raven2 IOMMU           | 36    |            | 0C3651AF28 |
| 1022:15d1 | 103c:86fd | AMD        | Raven/Raven2 IOMMU           | 34    |            | 5BB4E443F9 |
| 1022:1631 | 103c:876f | AMD        | Renoir/Cezanne IOMMU         | 34    |            | 5F67B298AB |
| 1022:15d1 | 17aa:3809 | AMD        | Raven/Raven2 IOMMU           | 33    |            | C3F376B088 |
| 1022:1631 | 17aa:3808 | AMD        | Renoir/Cezanne IOMMU         | 31    |            | 8C961555FE |
| 1022:15d1 | 1025:134f | AMD        | Raven/Raven2 IOMMU           | 30    |            | 5EDDDC1E2C |
| 1022:1631 | 1025:1461 | AMD        | Renoir/Cezanne IOMMU         | 30    |            | 264BADF289 |
| 1022:15d1 | 103c:85b3 | AMD        | Raven/Raven2 IOMMU           | 29    |            | AE1811A242 |
| 1022:1481 | 1462:7a38 | AMD        | Starship/Matisse IOMMU       | 28    |            | 11F7EC8B16 |
| 1022:1451 | 1462:7a38 | AMD        | Family 17h (Models 00h-0f... | 27    |            | 276D5FE9E3 |
| 1022:15d1 | 1025:125c | AMD        | Raven/Raven2 IOMMU           | 27    |            | 2FF605BDB0 |
| 1022:1481 | 1462:7c94 | AMD        | Starship/Matisse IOMMU       | 26    |            | 08819513F2 |
| 1022:1631 | 103c:887a | AMD        | Renoir/Cezanne IOMMU         | 26    |            | 2BA5AE42BB |
| 1022:1631 | 1043:87e1 | AMD        | Renoir/Cezanne IOMMU         | 25    |            | 740C97FB1C |
| 1022:1451 | 1462:7b89 | AMD        | Family 17h (Models 00h-0f... | 24    |            | E8965C736D |
| 1022:1481 | 1043:87cb | AMD        | Starship/Matisse IOMMU       | 24    |            | 6E020F3AD1 |
| 1022:15d1 | 1025:1456 | AMD        | Raven/Raven2 IOMMU           | 24    |            | 09F6196E70 |
| 1022:15d1 | 103c:85e0 | AMD        | Raven/Raven2 IOMMU           | 24    |            | 1A23A6605B |
| 1022:1631 | 1025:1455 | AMD        | Renoir/Cezanne IOMMU         | 24    |            | F581CF8319 |
| 1022:1481 | 1462:7c95 | AMD        | Starship/Matisse IOMMU       | 23    |            | D06DD7E0EC |
| 1022:1577 | 1025:109f | AMD        | Family 15h (Models 60h-6f... | 23    |            | 70037BDDCB |
| 1022:1577 | 103c:81f9 | AMD        | Family 15h (Models 60h-6f... | 23    |            | F8A1A59318 |
| 1022:15d1 | 103c:85dd | AMD        | Raven/Raven2 IOMMU           | 23    |            | C4EA79E269 |
| 1022:1631 | 17aa:3815 | AMD        | Renoir/Cezanne IOMMU         | 23    |            | C7A45F22C5 |
| 1022:1631 | 1e83:3e33 | AMD        | Renoir/Cezanne IOMMU         | 23    |            | 1E059DB869 |
| 1022:1631 | 1d05:1100 | AMD        | Renoir/Cezanne IOMMU         | 22    |            | 97B2732F29 |
| 1022:1481 | 1462:7b85 | AMD        | Starship/Matisse IOMMU       | 20    |            | DB9BFA58F9 |
| 1022:15d1 | 103c:85de | AMD        | Raven/Raven2 IOMMU           | 19    |            | 3ADCB9ECF9 |
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
| 1022:15d1 | 103c:83c6 | AMD        | Raven/Raven2 IOMMU           | 16    |            | 5174E188C0 |
| 1022:15d1 | 103c:8497 | AMD        | Raven/Raven2 IOMMU           | 16    |            | 0DFE108C69 |
| 1022:1631 | 103c:87b1 | AMD        | Renoir/Cezanne IOMMU         | 16    |            | CB7D97FD9E |
| 1022:1631 | 17aa:380d | AMD        | Renoir/Cezanne IOMMU         | 16    |            | 594815BB9D |
| 1022:1451 | 1462:7b85 | AMD        | Family 17h (Models 00h-0f... | 15    |            | 429525379A |
| 1022:1577 | 103c:8324 | AMD        | Family 15h (Models 60h-6f... | 15    |            | 5856720999 |
| 1022:15d1 | 103c:8496 | AMD        | Raven/Raven2 IOMMU           | 15    |            | DFB9789AF2 |
| 1022:1481 | 1043:87e2 | AMD        | Starship/Matisse IOMMU       | 14    |            | EE6DBC679C |
| 1022:1577 | 103c:8333 | AMD        | Family 15h (Models 60h-6f... | 14    |            | 57EE9BD872 |
| 1022:1577 | 103c:85bb | AMD        | Family 15h (Models 60h-6f... | 14    |            | 7F3E3F1E51 |
| 1022:15d1 | 103c:86d5 | AMD        | Raven/Raven2 IOMMU           | 14    |            | 9B0872B3D4 |
| 1022:1423 | 17aa:36a0 | AMD        | Family 15h (Models 30h-3f... | 13    |            | AFBB381CF3 |
| 1022:1451 | 1028:07ee | AMD        | Family 17h (Models 00h-0f... | 13    |            | 5256B07A63 |
| 1022:1577 | 1028:0769 | AMD        | Family 15h (Models 60h-6f... | 13    |            | 9FCA078069 |
| 1022:1577 | 103c:8345 | AMD        | Family 15h (Models 60h-6f... | 13    |            | AE684ABD8C |
| 1022:1577 | 17aa:380d | AMD        | Family 15h (Models 60h-6f... | 13    |            | 6BABB58C51 |
| 1022:15d1 | 1028:0a12 | AMD        | Raven/Raven2 IOMMU           | 13    |            | 38D22B1058 |
| 1022:15d1 | 103c:879e | AMD        | Raven/Raven2 IOMMU           | 13    |            | A94D17F64B |
| 1022:1631 | 103c:87cf | AMD        | Renoir/Cezanne IOMMU         | 13    |            | EDE284A3A3 |
| 1022:1577 | 1025:1099 | AMD        | Family 15h (Models 60h-6f... | 12    |            | FB8D7A6A25 |
| 1022:1577 | 17aa:364f | AMD        | Family 15h (Models 60h-6f... | 12    |            | 95EDC1D588 |
| 1022:15d1 | 103c:84d2 | AMD        | Raven/Raven2 IOMMU           | 12    |            | 838188303A |
| 1022:1631 | 103c:87c5 | AMD        | Renoir/Cezanne IOMMU         | 12    |            | 55F8110D0E |
| 1022:1631 | 17aa:380b | AMD        | Renoir/Cezanne IOMMU         | 12    |            | DCE0B57CDC |
| 1022:1481 | 1462:7a40 | AMD        | Starship/Matisse IOMMU       | 11    |            | 1CA6C5085E |
| 1022:15d1 | 103c:86d4 | AMD        | Raven/Raven2 IOMMU           | 11    |            | 98874D48B2 |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816c | 17aa:5081 | Realtek... | RTL8111xP IPMI interface     | 88    |            | 273A5FF27D |
| 10ec:816c | 17aa:5082 | Realtek... | RTL8111xP IPMI interface     | 47    |            | 037A558C7D |
| 10ec:816c | 17aa:507e | Realtek... | RTL8111xP IPMI interface     | 31    |            | AC5C6A0DD6 |
| 10ec:816c | 17aa:5125 | Realtek... | RTL8111xP IPMI interface     | 27    |            | 8E00E1F239 |
| 10ec:816c | 17aa:5126 | Realtek... | RTL8111xP IPMI interface     | 27    |            | 6B6B00F95C |
| 10ec:816c | 1043:85b5 | Realtek... | RTL8111xP IPMI interface     | 16    |            | 9B5B350293 |
| 10ec:816c | 17aa:5122 | Realtek... | RTL8111xP IPMI interface     | 12    |            | 483690E890 |
| 10ec:816c | 103c:8584 | Realtek... | RTL8111xP IPMI interface     | 11    |            | 295112838E |
| 10ec:816c | 103c:83d5 | Realtek... | RTL8111xP IPMI interface     | 9     |            | 7154F86BD2 |
| 10ec:816c | 103c:8464 | Realtek... | RTL8111xP IPMI interface     | 6     |            | 7964501CA5 |
| 10ec:816c | 10ec:0123 | Realtek... | RTL8111xP IPMI interface     | 6     |            | 65F6D55CEC |
| 10ec:816c | 17aa:3151 | Realtek... | RTL8111xP IPMI interface     | 5     |            | 76152DDCE8 |
| 10ec:816c | 103c:8589 | Realtek... | RTL8111xP IPMI interface     | 4     |            | 4168E4F738 |
| 10ec:816c | 1849:8168 | Realtek... | RTL8111xP IPMI interface     | 4     | ipmi_si    | 9032E4C08A |
| 10ec:816c | 1025:080a | Realtek... | RTL8111xP IPMI interface     | 3     |            | C486FBF03F |
| 10ec:816c | 1025:1248 | Realtek... | RTL8111xP IPMI interface     | 3     |            | 7EE989172F |
| 10ec:816c | 103c:8401 | Realtek... | RTL8111xP IPMI interface     | 3     |            | 8167AD2172 |
| 10ec:816c | 103c:8463 | Realtek... | RTL8111xP IPMI interface     | 3     |            | F378108DC3 |
| 10ec:816c | 17aa:30fd | Realtek... | RTL8111xP IPMI interface     | 3     |            | C694A13B5A |
| 10ec:816c | 17aa:5123 | Realtek... | RTL8111xP IPMI interface     | 3     |            | 516554B4E7 |
| 10ec:816c | 1019:81ea | Realtek... | RTL8111xP IPMI interface     | 2     |            | DF6385E8C2 |
| 10ec:816c | 1025:1290 | Realtek... | RTL8111xP IPMI interface     | 2     |            | A27363041A |
| 10ec:816c | 1025:1291 | Realtek... | RTL8111xP IPMI interface     | 2     |            | 13496AAE5D |
| 10ec:816c | 103c:8461 | Realtek... | RTL8111xP IPMI interface     | 2     |            | 991B8A8A71 |
| 10ec:816c | 103c:8618 | Realtek... | RTL8111xP IPMI interface     | 2     |            | A021BE4E84 |
| 10ec:816c | 103c:8626 | Realtek... | RTL8111xP IPMI interface     | 2     |            | E92FA74B31 |
| 10ec:816c | 17aa:5094 | Realtek... | RTL8111xP IPMI interface     | 2     |            | 99DDEF5ED9 |
| 10ec:816c | 17aa:511e | Realtek... | RTL8111xP IPMI interface     | 2     |            | C58E41C382 |
| 10ec:816c | 1025:078d | Realtek... | RTL8111xP IPMI interface     | 1     |            | 504EC0D230 |
| 10ec:816c | 1025:1005 | Realtek... | RTL8111xP IPMI interface     | 1     |            | 8A65F68E82 |
| 10ec:816c | 1025:1180 | Realtek... | RTL8111xP IPMI interface     | 1     |            | 90D9292ABE |
| 10ec:816c | 1025:124c | Realtek... | RTL8111xP IPMI interface     | 1     |            | 8EB6F7795D |
| 10ec:816c | 103c:83da | Realtek... | RTL8111xP IPMI interface     | 1     |            | F0FD278615 |
| 10ec:816c | 103c:8523 | Realtek... | RTL8111xP IPMI interface     | 1     |            | BAB721D52E |
| 10ec:816c | 1734:1216 | Realtek... | RTL8111xP IPMI interface     | 1     |            | A960AEF3AE |
| 10ec:816c | 17aa:3141 | Realtek... | RTL8111xP IPMI interface     | 1     |            | F19B15E3D2 |
| 10ec:816c | 17aa:3181 | Realtek... | RTL8111xP IPMI interface     | 1     |            | A203CD8C57 |
| 10ec:816c | 17aa:5091 | Realtek... | RTL8111xP IPMI interface     | 1     |            | 6D351FEC42 |
| 10ec:816c | 17aa:511f | Realtek... | RTL8111xP IPMI interface     | 1     |            | DF8C3622E3 |
| 10ec:816c | 1b0a:00e5 | Realtek... | RTL8111xP IPMI interface     | 1     |            | 3DA36F7282 |
| 8086:108e | 1734:108d | Intel      | 82573E KCS (Active Manage... | 1     | ipmi_si    | CCA0170CC9 |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 103c:3302 | 103c:3305 | Hewlett... | Integrated Lights-Out Sta... | 49    | ipmi_si    | 9753F223E2 |
| 10ec:816c | 10ec:8168 | Realtek... | RTL8111xP IPMI interface     | 29    | ipmi_si    | 07A5B3C465 |
| 10ec:816c | 1458:e000 | Realtek... | RTL8111xP IPMI interface     | 11    | ipmi_si    | 3D75B079F5 |
| 10ec:816c | 17aa:3089 | Realtek... | RTL8111xP IPMI interface     | 10    | ipmi_si    | 2891FE25E6 |
| 10ec:816c | 17aa:3130 | Realtek... | RTL8111xP IPMI interface     | 9     |            | 5981A4A25B |
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
| 1244:0a00 | 1244:0a00 | AVM        | A1 ISDN [Fritz]              | 9     | fcpci      | 98C67DA00D |
| 1133:e00b | 1133:e00b | Dialogic   | Diva ISDN PCI 2.02           | 1     |            | AC7FD78AB8 |
| 1397:2bd0 | 1075:c101 | Cologne... | ISDN network controller [... | 1     | hfcpci     | BE977291B5 |
| 1397:2bd0 | 1397:2bd0 | Cologne... | ISDN network controller [... | 1     | hfcpci     | 83A7C8B23F |
| e159:0001 | 795e:0001 | Tiger J... | Tiger3XX Modem/ISDN inter... | 1     | wcte11xp   | FE13415AC0 |
| e159:0001 | 79fe:0001 | Tiger J... | Tiger3XX Modem/ISDN inter... | 1     | wcte11xp   | B6E88B98F7 |
| e159:0001 | 9100:0001 | Tiger J... | Tiger3XX Modem/ISDN inter... | 1     | netjet     | 74F31779A2 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a36f | 8086:7270 | Intel      | Cannon Lake PCH Shared SRAM  | 1237  |            | 2FC377709D |
| 8086:a121 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 755   |            | 427C8B8D8F |
| 8086:a2a1 | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 463   |            | 381023907E |
| 8086:a2a1 | 1458:5001 | Intel      | 200 Series/Z370 Chipset F... | 430   |            | 8C2B6CF453 |
| 10de:03f5 | 1849:03eb | Nvidia     | MCP61 Memory Controller      | 425   |            | 0F23350175 |
| 8086:a121 | 1458:5001 | Intel      | 100 Series/C230 Series Ch... | 420   |            | 36BF6DAB37 |
| 10de:03e2 | 1849:03e2 | Nvidia     | MCP61 Host Bridge            | 390   |            | 0F23350175 |
| 8086:a36f | 1043:8694 | Intel      | Cannon Lake PCH Shared SRAM  | 375   |            | 22A32FC3F2 |
| 8086:9def | 8086:7270 | Intel      | Cannon Point-LP Shared SRAM  | 358   |            | 67F0B45A7A |
| 8086:9d21 | 8086:7270 | Intel      | Sunrise Point-LP PMC         | 318   | intel_p... | 6039985C3F |
| 8086:06ef | 8086:7270 | Intel      | Comet Lake PCH Shared SRAM   | 294   |            | 32F01CCAAB |
| 10de:0a88 |           | Nvidia     | MCP79 Memory Controller      | 282   |            | 5CA23CF3F6 |
| 8086:9def |           | Intel      | Cannon Point-LP Shared SRAM  | 274   |            | 3678E02E46 |
| 10de:0a89 |           | Nvidia     | MCP79 Memory Controller      | 264   |            | 5CA23CF3F6 |
| 10de:0aa4 |           | Nvidia     | MCP79 Memory Controller      | 263   |            | 5CA23CF3F6 |
| 10de:0a98 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 255   |            | 5CA23CF3F6 |
| 8086:34ef |           | Intel      | Ice Lake-LP DRAM Controller  | 251   |            | 138EC046F1 |
| 10de:03f5 | 1458:0c11 | Nvidia     | MCP61 Memory Controller      | 213   |            | 701EE8CE26 |
| 8086:a121 | 1849:a121 | Intel      | 100 Series/C230 Series Ch... | 205   |            | 6B4C3F811B |
| 8086:02ef | 8086:7270 | Intel      | Comet Lake PCH-LP Shared ... | 196   |            | BA8F31C45F |
| 8086:a2a1 | 1849:a2a1 | Intel      | 200 Series/Z370 Chipset F... | 178   |            | 79E6EF3655 |
| 10de:03e2 | 1043:83a4 | Nvidia     | MCP61 Host Bridge            | 158   |            | 324F6E5FAD |
| 10de:03f5 | 1043:83a4 | Nvidia     | MCP61 Memory Controller      | 158   |            | 324F6E5FAD |
| 8086:a2a1 | 1043:872f | Intel      | 200 Series/Z370 Chipset F... | 158   |            | F60A34FE5C |
| 8086:a36f | 1025:1331 | Intel      | Cannon Lake PCH Shared SRAM  | 157   |            | BC9DC107D1 |
| 8086:9d21 | 17aa:3872 | Intel      | Sunrise Point-LP PMC         | 147   |            | F86520F5A7 |
| 8086:a36f | 1028:0905 | Intel      | Cannon Lake PCH Shared SRAM  | 142   |            | 58E43F0514 |
| 8086:02ef | 17aa:5079 | Intel      | Comet Lake PCH-LP Shared ... | 138   |            | A35AAAEB6D |
| 10de:03ea | 10de:cb84 | Nvidia     | MCP61 Memory Controller      | 133   |            | 0A4D7FB95D |
| 8086:9def | 8086:2074 | Intel      | Cannon Point-LP Shared SRAM  | 130   |            | 7EEEAAA250 |
| 8086:9d21 | 8086:9d21 | Intel      | Sunrise Point-LP PMC         | 127   | intel_p... | F3E5EBA0C2 |
| 8086:9def | 17aa:2279 | Intel      | Cannon Point-LP Shared SRAM  | 127   |            | A01E524A66 |
| 10de:03ea | 1043:8234 | Nvidia     | MCP61 Memory Controller      | 124   |            | 91FE7919BE |
| 10de:03f5 | 1043:8234 | Nvidia     | MCP61 Memory Controller      | 124   |            | 91FE7919BE |
| 8086:a36f | 1849:a36f | Intel      | Cannon Lake PCH Shared SRAM  | 124   |            | 2FF008A28D |
| 8086:9d21 | 103c:8079 | Intel      | Sunrise Point-LP PMC         | 123   |            | 436E9BF227 |
| 8086:9d21 | 1025:1193 | Intel      | Sunrise Point-LP PMC         | 119   | intel_p... | 43BFEF3BCD |
| 8086:a36f | 1028:087c | Intel      | Cannon Lake PCH Shared SRAM  | 114   |            | 0FA8C3ED0C |
| 10de:03ea | 1458:5001 | Nvidia     | MCP61 Memory Controller      | 113   |            | 7076F55128 |
| 8086:9def | 103c:8549 | Intel      | Cannon Point-LP Shared SRAM  | 111   |            | A814284F0B |
| 8086:9d21 | 1028:0810 | Intel      | Sunrise Point-LP PMC         | 110   |            | C01FA4B013 |
| 8086:9d21 | 17aa:225d | Intel      | Sunrise Point-LP PMC         | 109   |            | FEB7F2A285 |
| 10de:03e2 | 1458:5001 | Nvidia     | MCP61 Host Bridge            | 100   |            | 701EE8CE26 |
| 8086:43ef |           | Intel      | Tiger Lake-H Shared SRAM     | 99    |            | BE8B71D264 |
| 8086:9d21 | 1028:07e6 | Intel      | Sunrise Point-LP PMC         | 99    | intel_p... | 5A56854746 |
| 8086:a121 | 1028:07be | Intel      | 100 Series/C230 Series Ch... | 99    |            | 69938C221E |
| 8086:a0ef |           | Intel      | Tiger Lake-LP Shared SRAM    | 98    |            | 4BF23FF82D |
| 10de:005e | 1043:815a | Nvidia     | CK804 Memory Controller      | 97    |            | F9BFF20C4D |
| 10de:0d68 |           | Nvidia     | MCP89 Memory Controller      | 95    |            | 80E0B6AF9E |
| 10de:0d69 |           | Nvidia     | MCP89 Memory Controller      | 95    |            | 80E0B6AF9E |
| 10de:0d6d |           | Nvidia     | MCP89 Memory Controller      | 95    |            | 80E0B6AF9E |
| 10de:0d6e |           | Nvidia     | MCP89 Memory Controller      | 95    |            | 80E0B6AF9E |
| 10de:0d6f |           | Nvidia     | MCP89 Memory Controller      | 95    |            | 80E0B6AF9E |
| 10de:0d70 |           | Nvidia     | MCP89 Memory Controller      | 95    |            | 80E0B6AF9E |
| 10de:0d71 |           | Nvidia     | MCP89 Memory Controller      | 95    |            | 80E0B6AF9E |
| 10de:0d72 |           | Nvidia     | MCP89 Memory Controller      | 95    |            | 80E0B6AF9E |
| 10de:0d75 |           | Nvidia     | MCP89 Memory Controller      | 95    |            | 80E0B6AF9E |
| 10de:0d7b |           | Nvidia     | MCP89 Memory Controller      | 95    |            | 80E0B6AF9E |
| 8086:9d21 | 1043:12d1 | Intel      | Sunrise Point-LP PMC         | 95    | intel_p... | 703D0F2090 |
| 8086:a121 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 94    |            | 3F08FB0618 |
| 8086:9def | 1028:08af | Intel      | Cannon Point-LP Shared SRAM  | 92    |            | 52DEA66C52 |
| 8086:02ef | 1028:0962 | Intel      | Comet Lake PCH-LP Shared ... | 91    |            | 8956FEE2F3 |
| 8086:9d21 | 1028:078b | Intel      | Sunrise Point-LP PMC         | 91    |            | 35BCBD121B |
| 8086:9d21 | 17aa:3845 | Intel      | Sunrise Point-LP PMC         | 89    |            | 4EB6B00CAC |
| 8086:9def | 8086:9def | Intel      | Cannon Point-LP Shared SRAM  | 88    |            | 0E29003348 |
| 8086:9d21 | 17aa:225c | Intel      | Sunrise Point-LP PMC         | 86    |            | 2B4A1A20D9 |
| 8086:9d21 | 17aa:5068 | Intel      | Sunrise Point-LP PMC         | 86    |            | 2A70ED5588 |
| 8086:a36f | 1025:1264 | Intel      | Cannon Lake PCH Shared SRAM  | 86    |            | 7F70DE1771 |
| 8086:06ef | 1028:097d | Intel      | Comet Lake PCH Shared SRAM   | 84    |            | 994B96D25D |
| 8086:a3a1 | 1043:8694 | Intel      | Memory controller            | 82    |            | 7B62AD7C35 |
| 10de:0a88 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 81    |            | AE8948A236 |
| 10de:0a89 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 81    |            | AE8948A236 |
| 8086:9d21 | 103c:832a | Intel      | Sunrise Point-LP PMC         | 80    |            | C9FD6887D4 |
| 8086:06ef | 1043:8694 | Intel      | Comet Lake PCH Shared SRAM   | 79    |            | CAFC4421B2 |
| 8086:9d21 | 1025:1295 | Intel      | Sunrise Point-LP PMC         | 78    |            | 06114B7EB7 |
| 8086:a36f |           | Intel      | Cannon Lake PCH Shared SRAM  | 78    |            | 90E49546C2 |
| 10de:03f5 | 1462:7309 | Nvidia     | MCP61 Memory Controller      | 77    |            | 0A4D7FB95D |
| 8086:9d21 | 103c:83b2 | Intel      | Sunrise Point-LP PMC         | 76    |            | E64AEB5FA4 |
| 8086:9def | 17aa:3809 | Intel      | Cannon Point-LP Shared SRAM  | 76    |            | 2DB4EBB6EF |
| 8086:9d21 | 1025:115f | Intel      | Sunrise Point-LP PMC         | 74    | intel_p... | 7046D52A8D |
| 8086:9d21 | 17aa:2233 | Intel      | Sunrise Point-LP PMC         | 73    |            | 9EF824D802 |
| 8086:9d21 | 17aa:2245 | Intel      | Sunrise Point-LP PMC         | 73    | intel_p... | 80FB4514C5 |
| 8086:a36f | 17aa:3804 | Intel      | Cannon Lake PCH Shared SRAM  | 73    |            | EAF7694813 |
| 8086:9d21 | 8086:2068 | Intel      | Sunrise Point-LP PMC         | 71    |            | 82B124D8C4 |
| 8086:a121 | 1462:7996 | Intel      | 100 Series/C230 Series Ch... | 71    |            | EC7609239E |
| 8086:02ef | 8086:2081 | Intel      | Comet Lake PCH-LP Shared ... | 70    |            | 37E756FA81 |
| 8086:9d21 | 1028:081c | Intel      | Sunrise Point-LP PMC         | 70    |            | ADB96FACBB |
| 8086:9d21 | 17aa:2258 | Intel      | Sunrise Point-LP PMC         | 70    |            | EEB181F50B |
| 8086:9d21 | 103c:84a6 | Intel      | Sunrise Point-LP PMC         | 68    | intel_p... | F0A8FA5E7A |
| 8086:9d21 | 17aa:3851 | Intel      | Sunrise Point-LP PMC         | 67    |            | 08D287D2E2 |
| 8086:a121 | 1028:0798 | Intel      | 100 Series/C230 Series Ch... | 67    |            | 1B93E3C1C9 |
| 10de:0568 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 66    |            | 9005621271 |
| 10de:0751 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 66    |            | 9005621271 |
| 10de:0754 | 1043:82f2 | Nvidia     | MCP78S [GeForce 8200] Mem... | 66    |            | 9005621271 |
| 8086:9d21 | 1025:1085 | Intel      | Sunrise Point-LP PMC         | 66    | intel_p... | 36C622EABC |
| 8086:9d21 | 1028:06b2 | Intel      | Sunrise Point-LP PMC         | 66    |            | F7EE774D7E |
| 8086:9d21 | 17aa:3816 | Intel      | Sunrise Point-LP PMC         | 66    |            | 60B294879D |
| 8086:a36f | 1028:0949 | Intel      | Cannon Lake PCH Shared SRAM  | 65    |            | 3165D77A8E |
| 10de:03f5 | 1565:3407 | Nvidia     | MCP61 Memory Controller      | 64    |            | E16A5113BA |
| 8086:9d21 | 1028:075b | Intel      | Sunrise Point-LP PMC         | 63    |            | 8BB0307157 |

### Modem (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:266d | 14f1:5423 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 30    | snd_int... | F48BAD44CD |
| 1057:3052 | 1057:3020 | Motorola   | SM56 Data Fax Modem          | 24    |            | D342F4E0A4 |
| 8086:266d | 1179:0001 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 22    | snd_int... | 61FEA93E97 |
| 1106:3068 |           | VIA Tec... | AC'97 Modem Controller       | 18    | snd_via... | B38568681E |
| 11c1:044c | 11c1:044c | LSI        | LT WinModem                  | 15    |            | 7CA677A33C |
| 1039:7013 | 1025:0083 | Silicon... | AC'97 Modem Controller       | 13    | snd_int... | 5C114A6E41 |
| 8086:24c6 | 14f1:5422 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 13    | snd_int... | C4A1E26625 |
| 8086:266d | 1025:006a | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 11    | snd_int... | FC6953A3F9 |
| 8086:266d | 103c:099c | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 11    | snd_int... | F54C45AB89 |
| 1002:4378 | 103c:3085 | AMD        | IXP SB400 AC'97 Modem Con... | 9     | snd_ati... | 280B8AF5CC |
| 8086:266d | 1014:0574 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 9     | snd_int... | 67510CC1AA |
| 1039:7013 | 1043:1816 | Silicon... | AC'97 Modem Controller       | 8     | snd_int... | AA92B168C5 |
| 8086:266d | 103c:0944 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 8     | snd_int... | 7F042FAA64 |
| 1002:4378 | 103c:3091 | AMD        | IXP SB400 AC'97 Modem Con... | 7     | snd_ati... | F01F51C47C |
| 8086:1040 | 8086:1000 | Intel      | 536EP Data Fax Modem         | 7     |            | F2CC8FAE4D |
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
| 1106:3068 | 1019:0c04 | VIA Tec... | AC'97 Modem Controller       | 4     | snd_via... | CAAB4A3B82 |
| 134d:7892 | 134d:0001 | PCTel      | HSP MicroModem 56            | 4     | serial     | 6C9B4F5E0B |
| 1543:3052 | 1543:3000 | SILICON... | Intel 537 [Winmodem]         | 4     |            | B6ADDF8D7B |
| 8086:266d | 1014:0576 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 4     | snd_int... | E323E5FE53 |
| 8086:266d | 103c:30c4 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 4     | snd_int... | FE8A07348F |
| 8086:266d | 1179:ff31 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 4     | snd_int... | 875478A51A |
| 8086:266d | 144d:2115 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 4     | snd_int... | D7EE30EC16 |
| 1002:434d | 144d:2115 | AMD        | SB200 AC97 Modem Controller  | 3     | snd_ati... | F72BBFF4B7 |
| 1002:4378 | 1025:007e | AMD        | IXP SB400 AC'97 Modem Con... | 3     | snd_ati... | 60873D0A0E |
| 1002:4378 | 1025:0080 | AMD        | IXP SB400 AC'97 Modem Con... | 3     | snd_ati... | 8B304AF834 |
| 1039:7013 | 1025:0082 | Silicon... | AC'97 Modem Controller       | 3     |            | EDF0363AFE |
| 1039:7013 | 1584:4003 | Silicon... | AC'97 Modem Controller       | 3     | snd_int... | E9BC9B3C8A |
| 10b9:5457 | 104d:8158 | ULi Ele... | M5457 AC'97 Modem Controller | 3     |            | 7E4F74E16A |
| 10de:00d9 | 103c:006d | Nvidia     | nForce3 Audio                | 3     |            | 564B583FED |
| 1106:3068 | 1631:c015 | VIA Tec... | AC'97 Modem Controller       | 3     | snd_via... | C0B37BC3C3 |
| 1106:3068 | 1734:109b | VIA Tec... | AC'97 Modem Controller       | 3     | snd_via... | 2C34DEA0FC |
| 11c1:0440 | 11c1:0440 | LSI        | 56k WinModem                 | 3     |            | 2700C74BD9 |
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
| 11c1:0449 | 1468:0410 | LSI        | L56xM+S [Mars-2] WinModem... | 2     |            | A27652B00A |
| 11c1:044e | 11c1:044e | LSI        | LT WinModem                  | 2     |            | DA6AB84289 |
| 11c1:044e | 1235:044e | LSI        | LT WinModem                  | 2     |            | C22EB5394A |
| 134d:7890 | 134d:0001 | PCTel      | HSP MicroModem 56            | 2     | serial     | 332DDF27C1 |
| 2003:8800 | 1801:2800 | Smart Link | LM-I56N                      | 2     |            | 62AFB6C0F6 |
| 8086:1080 | 1028:1000 | Intel      | FA82537EP 56K V.92 Data/F... | 2     | serial     | DC13BE448C |
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
| 8086:27dd |           | Intel      | 82801G (ICH7 Family) AC'9... | 2     |            | 78AA035121 |
| 1002:434d | 1025:0052 | AMD        | SB200 AC97 Modem Controller  | 1     | snd_ati... | 856DF8910C |
| 1002:434d | 103c:006b | AMD        | SB200 AC97 Modem Controller  | 1     | snd_ati... | 5171D8BC33 |
| 1002:4378 | 1179:0001 | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 184C93E6DD |
| 1002:4378 | 1179:ff31 | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 654C60E971 |
| 1002:4378 | 1462:0131 | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | 21B7740691 |
| 1002:4378 | 17c0:10bc | AMD        | IXP SB400 AC'97 Modem Con... | 1     | snd_ati... | B115D6B061 |
| 1039:7013 | 1043:1696 | Silicon... | AC'97 Modem Controller       | 1     |            | D385784B22 |
| 1039:7013 | 104d:8128 | Silicon... | AC'97 Modem Controller       | 1     | snd_int... | 72A578315E |
| 1039:7013 | 1558:4201 | Silicon... | AC'97 Modem Controller       | 1     |            | 5B191FE82E |
| 1039:7013 | 1631:3003 | Silicon... | AC'97 Modem Controller       | 1     | snd_int... | A787298BDB |
| 1039:7013 | 1734:106c | Silicon... | AC'97 Modem Controller       | 1     |            | BFFEEEDE0D |
| 1057:3052 | 1631:3034 | Motorola   | SM56 Data Fax Modem          | 1     |            | B7CEC1644D |
| 10b9:5457 | 103c:0850 | ULi Ele... | M5457 AC'97 Modem Controller | 1     |            | 4E9D284D9C |
| 10b9:5457 | 10cf:130f | ULi Ele... | M5457 AC'97 Modem Controller | 1     |            | 347EB6B747 |
| 10b9:5459 | 10a5:5459 | ULi Ele... | SmartLink SmartPCI561 56K... | 1     | serial     | CA657531E4 |
| 10b9:545a | 2020:545a | ULi Ele... | SmartLink SmartPCI563 56K... | 1     | serial     | 2A51E0D9E9 |
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

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15e2 | 1022:15e2 | AMD        | Raven/Raven2/FireFlight/R... | 543   | snd_pci... | BEE34D8394 |
| 8086:22b8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 478   | intel_a... | 2FBF6F153B |
| 14e4:1570 | 14e4:1570 | Broadcom   | 720p FaceTime HD Camera      | 451   | bdc_pci    | 0C24CAF245 |
| 8086:1919 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 150   | ipu3_imgu  | 6039985C3F |
| 8086:9d32 | 8086:7270 | Intel      | CSI-2 Host Controller        | 139   | ipu3_cio2  | 6039985C3F |
| 1022:15e2 | 17aa:5081 | AMD        | Raven/Raven2/FireFlight/R... | 90    | snd_pci... | 273A5FF27D |
| 8086:5a88 |           | Intel      | Celeron N3350/Pentium N42... | 90    |            | 6121781D85 |
| 1022:15e2 | 19e5:3e19 | AMD        | Raven/Raven2/FireFlight/R... | 81    | snd_pci... | 1310B8ABF4 |
| 1022:15e2 | 17aa:507f | AMD        | Raven/Raven2/FireFlight/R... | 75    | snd_pci... | 8A34D739FD |
| 1022:15e2 | 17aa:3821 | AMD        | Raven/Raven2/FireFlight/R... | 66    | snd_pci... | 8A6E0EE275 |
| 1022:15e2 | 17aa:381b | AMD        | Raven/Raven2/FireFlight/R... | 64    | snd_pci... | F07B9B77F5 |
| 1022:15e2 | 1025:134d | AMD        | Raven/Raven2/FireFlight/R... | 63    | snd_pci... | 6134BF279A |
| 1022:15e2 | 17aa:3807 | AMD        | Raven/Raven2/FireFlight/R... | 63    | snd_pci... | 497BF56CC6 |
| 1022:15e2 | 17aa:5124 | AMD        | Raven/Raven2/FireFlight/R... | 61    | snd_pci... | 52BA950565 |
| 1022:15e2 | 103c:84ae | AMD        | Raven/Raven2/FireFlight/R... | 58    | snd_pci... | 2E3861AEF3 |
| 1022:15e2 | 17aa:3812 | AMD        | Raven/Raven2/FireFlight/R... | 58    | snd_pci... | 3F7C00C1EF |
| 1022:15e2 | 1e21:1043 | AMD        | Raven/Raven2/FireFlight/R... | 58    | snd_pci... | 3802A77D98 |
| 1022:15e2 | 17aa:381c | AMD        | Raven/Raven2/FireFlight/R... | 57    | snd_pci... | 3CDC08297E |
| 1022:15e2 | 17aa:3814 | AMD        | Raven/Raven2/FireFlight/R... | 54    | snd_pci... | 8DB63E7A74 |
| 1022:15e2 | 103c:8730 | AMD        | Raven/Raven2/FireFlight/R... | 53    | snd_pci... | 1719B2DC9D |
| 1022:15e2 | 17aa:3813 | AMD        | Raven/Raven2/FireFlight/R... | 47    | snd_pci... | 09ADDF2612 |
| 1022:15e2 | 1d05:109f | AMD        | Raven/Raven2/FireFlight/R... | 45    | snd_pci... | 7242436545 |
| 1022:15e2 | 19e5:3e18 | AMD        | Raven/Raven2/FireFlight/R... | 44    | snd_pci... | C0B80E3276 |
| 1022:15e2 | 103c:8760 | AMD        | Raven/Raven2/FireFlight/R... | 42    | snd_pci... | 9C1DFCB679 |
| 1022:15e2 | 17aa:3822 | AMD        | Raven/Raven2/FireFlight/R... | 40    | snd_pci... | 86BC5DDC56 |
| 1022:15e2 | 17aa:507e | AMD        | Raven/Raven2/FireFlight/R... | 39    | snd_pci... | E9A8FB1275 |
| 1022:15e2 | 103c:85ea | AMD        | Raven/Raven2/FireFlight/R... | 38    | snd_pci... | E8781DB5AB |
| 1022:15e2 | 103c:876e | AMD        | Raven/Raven2/FireFlight/R... | 38    | snd_pci... | 28B152BB19 |
| 1022:15e2 | 1025:142b | AMD        | Raven/Raven2/FireFlight/R... | 37    | snd_pci... | BCE3E39F4C |
| 8086:22b8 | 17aa:3809 | Intel      | Atom/Celeron/Pentium Proc... | 37    | intel_a... | 71506FF3BD |
| 8086:22b8 | 17aa:38e3 | Intel      | Atom/Celeron/Pentium Proc... | 35    | intel_a... | F45A93E403 |
| 1022:15e2 | 103c:86fd | AMD        | Raven/Raven2/FireFlight/R... | 34    | snd_pci... | 5BB4E443F9 |
| 1022:15e2 | 103c:876f | AMD        | Raven/Raven2/FireFlight/R... | 34    | snd_pci... | 5F67B298AB |
| 8086:22b8 | 103c:813e | Intel      | Atom/Celeron/Pentium Proc... | 33    | intel_a... | 0A44B96544 |
| 1022:15e2 | 17aa:380f | AMD        | Raven/Raven2/FireFlight/R... | 31    | snd_pci... | 8C961555FE |
| 1022:15e2 | 1025:134f | AMD        | Raven/Raven2/FireFlight/R... | 30    | snd_pci... | 5EDDDC1E2C |
| 1022:15e2 | 1025:1461 | AMD        | Raven/Raven2/FireFlight/R... | 30    | snd_pci... | 264BADF289 |
| 8086:9d32 |           | Intel      | CSI-2 Host Controller        | 30    | ipu3_cio2  | 5C64BFD9D4 |
| 1022:15e2 | 103c:85b3 | AMD        | Raven/Raven2/FireFlight/R... | 29    | snd_pci... | AE1811A242 |
| 1022:15e2 | 17aa:5084 | AMD        | Raven/Raven2/FireFlight/R... | 29    | snd_pci... | 037A558C7D |
| 109e:0878 |           | Brooktree  | Bt878 Audio Capture          | 28    | bt878      | 2B61653CEA |
| 1022:15e2 | 17aa:5125 | AMD        | Raven/Raven2/FireFlight/R... | 27    | snd_pci... | 8E00E1F239 |
| 1022:15e2 | 1025:1456 | AMD        | Raven/Raven2/FireFlight/R... | 26    | snd_pci... | 09F6196E70 |
| 1022:15e2 | 103c:887a | AMD        | Raven/Raven2/FireFlight/R... | 26    | snd_pci... | 2BA5AE42BB |
| 8086:1919 | 8086:1919 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 26    | ipu3_imgu  | 3B25F1B84A |
| 8086:22b8 | 1297:2063 | Intel      | Atom/Celeron/Pentium Proc... | 26    | intel_a... | 0D1AB84E09 |
| 1022:15e2 | 19e5:3e06 | AMD        | Raven/Raven2/FireFlight/R... | 25    | snd_pci... | 9BEA49D841 |
| 1022:15e2 | 1a0e:1043 | AMD        | Raven/Raven2/FireFlight/R... | 25    | snd_pci... | 9E88464633 |
| 1022:15e2 | 1025:1455 | AMD        | Raven/Raven2/FireFlight/R... | 24    | snd_pci... | F581CF8319 |
| 1022:15e2 | 17aa:3823 | AMD        | Raven/Raven2/FireFlight/R... | 24    | snd_pci... | 214D892F21 |
| 1022:15e2 | 103c:85dd | AMD        | Raven/Raven2/FireFlight/R... | 23    | snd_pci... | C4EA79E269 |
| 1022:15e2 | 1e83:3e33 | AMD        | Raven/Raven2/FireFlight/R... | 23    | snd_pci... | 1E059DB869 |
| 8086:8a19 | 1028:08b0 | Intel      | Image Signal Processor       | 23    |            | 138EC046F1 |
| 1022:15e2 | 19e5:3e14 | AMD        | Raven/Raven2/FireFlight/R... | 22    | snd_pci... | C62BB4ADC9 |
| 8086:22b8 | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 21    | intel_a... | AE0E0904DB |
| 1022:15e2 | 103c:85e0 | AMD        | Raven/Raven2/FireFlight/R... | 20    | snd_pci... | 1A23A6605B |
| 8086:22b8 | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 20    | intel_a... | 0A301456DC |
| 8086:9d32 | 8086:9d32 | Intel      | CSI-2 Host Controller        | 20    | ipu3_cio2  | 8C051A0CE9 |
| 1022:15e2 | 103c:85de | AMD        | Raven/Raven2/FireFlight/R... | 19    | snd_pci... | 3ADCB9ECF9 |
| 1022:15e2 | 17aa:5097 | AMD        | Raven/Raven2/FireFlight/R... | 19    | snd_pci... | 8D45D9544E |
| 1022:15e2 | 1028:09f5 | AMD        | Raven/Raven2/FireFlight/R... | 18    | snd_pci... | B11BD373D3 |
| 1022:15e2 | 1043:1f11 | AMD        | Raven/Raven2/FireFlight/R... | 18    | snd_pci... | 0F6D7BCF66 |
| 11bd:bede | 11bd:0022 | Pinnacl... | AV/DV Studio Capture Card    | 18    |            | 6CA0293F8E |
| 14e4:1615 | 14e4:1615 | Broadcom   | BCM70015 Video Decoder [C... | 18    | crystalhd  | 89BBAFA02E |
| 1022:15e2 | 103c:8433 | AMD        | Raven/Raven2/FireFlight/R... | 17    | snd_pci... | 6183F8775B |
| 1022:15e2 | 103c:8706 | AMD        | Raven/Raven2/FireFlight/R... | 17    | snd_pci... | D39BE3EDBA |
| 1022:15e2 | 152d:1273 | AMD        | Raven/Raven2/FireFlight/R... | 17    | snd_pci... | BBF16A7212 |
| 8086:22b8 | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 17    | intel_a... | 091F7C8FAE |
| 8086:8a19 | 8086:7270 | Intel      | Image Signal Processor       | 17    |            | 7C8422E762 |
| 1022:15e2 | 103c:87b1 | AMD        | Raven/Raven2/FireFlight/R... | 16    | snd_pci... | CB7D97FD9E |
| 1022:15e2 | 17aa:380d | AMD        | Raven/Raven2/FireFlight/R... | 16    | snd_pci... | 594815BB9D |
| 1131:7164 | 0070:8851 | Philips... | SAA7164                      | 16    | saa7164    | 75B8BCA0FA |
| 1022:15e2 | 1025:1378 | AMD        | Raven/Raven2/FireFlight/R... | 15    | snd_pci... | 589BEB7652 |
| 1022:15e2 | 103c:8735 | AMD        | Raven/Raven2/FireFlight/R... | 15    | snd_pci... | 4EE6C35B8F |
| 1022:15e2 | 17aa:381f | AMD        | Raven/Raven2/FireFlight/R... | 15    | snd_pci... | 8948989999 |
| 1022:15e2 | 17aa:5127 | AMD        | Raven/Raven2/FireFlight/R... | 15    | snd_pci... | 7065F7BB74 |
| 109e:0878 | 1461:0003 | Brooktree  | Bt878 Audio Capture          | 15    | snd_bt87x  | 59D57FE423 |
| 8086:1919 | 152d:1182 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 15    | ipu3_imgu  | 5C64BFD9D4 |
| 1022:15e2 | 103c:86d5 | AMD        | Raven/Raven2/FireFlight/R... | 14    | snd_pci... | 9B0872B3D4 |
| 1022:15e2 | 1043:1e8e | AMD        | Raven/Raven2/FireFlight/R... | 14    | snd_pci... | 3F7A2585FE |
| 8086:22b8 | 1043:1bdd | Intel      | Atom/Celeron/Pentium Proc... | 14    | atomisp    | C518746ECE |
| 1022:15e2 | 1028:0a12 | AMD        | Raven/Raven2/FireFlight/R... | 13    | snd_pci... | 38D22B1058 |
| 1022:15e2 | 103c:879e | AMD        | Raven/Raven2/FireFlight/R... | 13    | snd_pci... | A94D17F64B |
| 1022:15e2 | 103c:87cf | AMD        | Raven/Raven2/FireFlight/R... | 13    | snd_pci... | EDE284A3A3 |
| 1022:15e2 | 17aa:380b | AMD        | Raven/Raven2/FireFlight/R... | 13    | snd_pci... | 381F6460B0 |
| 1022:15e2 | 17aa:5082 | AMD        | Raven/Raven2/FireFlight/R... | 13    | snd_pci... | 534A4C683F |
| 1022:15e2 | 17aa:5126 | AMD        | Raven/Raven2/FireFlight/R... | 13    | snd_pci... | 6B6B00F95C |
| 1022:15e2 | 19e5:3e10 | AMD        | Raven/Raven2/FireFlight/R... | 13    | snd_pci... | 9C73A8D7D6 |
| 1022:15e2 | 103c:84d2 | AMD        | Raven/Raven2/FireFlight/R... | 12    | snd_pci... | 838188303A |
| 1022:15e2 | 103c:87c5 | AMD        | Raven/Raven2/FireFlight/R... | 12    | snd_pci... | 55F8110D0E |
| 1022:15e2 | 1558:a500 | AMD        | Raven/Raven2/FireFlight/R... | 12    | snd_pci... | 769328E65E |
| 1022:15e2 | 17aa:3824 | AMD        | Raven/Raven2/FireFlight/R... | 12    | snd_pci... | DCE0B57CDC |
| 8086:1919 | 103c:80fc | Intel      | Xeon E3-1200 v5/E3-1500 v... | 12    | ipu3_imgu  | 89E5AB8846 |
| 8086:9d32 | 103c:80fc | Intel      | CSI-2 Host Controller        | 12    | ipu3_cio2  | 89E5AB8846 |
| 1022:15e2 | 103c:86d4 | AMD        | Raven/Raven2/FireFlight/R... | 11    | snd_pci... | 98874D48B2 |
| 1022:15e2 | 17aa:382c | AMD        | Raven/Raven2/FireFlight/R... | 11    | snd_pci... | C7A45F22C5 |
| 1022:15e2 | 1d72:1953 | AMD        | Raven/Raven2/FireFlight/R... | 11    | snd_pci... | 23546F7A48 |
| 8086:0f38 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 11    | intel_a... | 06D0750E6E |
| 8086:22b8 | 1414:0009 | Intel      | Atom/Celeron/Pentium Proc... | 11    | intel_a... | ACF86AFB8C |
| 1022:15e2 | 1025:1233 | AMD        | Raven/Raven2/FireFlight/R... | 10    | snd_pci... | 8DF5E13FC0 |

### Multiport serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1fd4:1999 | 1fd4:0002 | SUNIX      | Multiport serial controller  | 7     | serial     | DF6B2FA3DE |
| 135a:08c1 | 135a:0413 | Brain B... | Multiport serial controller  | 1     |            | 0F6EBD3E93 |
| 135c:0170 | 135c:0170 | Quatech    | QSCLP-100                    | 1     | serial     | 05DF269988 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8168 | 1458:e000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5941  | r8169      | E52E9002D0 |
| 10ec:8168 | 1849:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2570  | r8169      | 42CD4D28BD |
| 10ec:8168 | 1043:8677 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1900  | r8169      | 24974BE67E |
| 10ec:8168 | 1043:8505 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1706  | r8169      | 1BB97BC7DF |
| 10ec:8168 | 1043:200f | Realtek... | RTL8111/8168/8411 PCI Exp... | 1576  | r8169      | B92CD04EE7 |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1351  | r8169      | 6978CD209F |
| 10ec:8168 | 1043:8432 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1276  | r8169      | 278873FF66 |
| 8086:15b8 | 1043:8672 | Intel      | Ethernet Connection (2) I... | 765   | e1000e     | 427C8B8D8F |
| 10ec:8168 | 1043:8554 | Realtek... | RTL8111/8168/8411 PCI Exp... | 721   | r8169      | 735015DCE2 |
| 10ec:8139 | 10ec:8139 | Realtek... | RTL-8100/8101L/8139 PCI F... | 697   | 8139too... | 892069341E |
| 10ec:8168 | 1043:83a3 | Realtek... | RTL8111/8168/8411 PCI Exp... | 579   | r8169      | 4E4391F329 |
| 10ec:8136 | 1043:200f | Realtek... | RTL810xE PCI Express Fast... | 541   | r8169      | 9B382500C5 |
| 10ec:8168 | 1043:208f | Realtek... | RTL8111/8168/8411 PCI Exp... | 478   | r8169      | 32F01CCAAB |
| 10ec:8168 | 1043:859e | Realtek... | RTL8111/8168/8411 PCI Exp... | 456   | r8169      | F7CE357637 |
| 14e4:16b4 | 14e4:16b4 | Broadcom   | NetXtreme BCM57765 Gigabi... | 421   | tg3        | 6E17FB6EA4 |
| 14e4:16b5 | 1025:0647 | Broadcom   | NetLink BCM57785 Gigabit ... | 410   | tg3        | 82E60126C9 |
| 10ec:8136 | 10ec:0123 | Realtek... | RTL810xE PCI Express Fast... | 392   | r8169      | 6978CD209F |
| 1969:1048 | 1043:8226 | Qualcom... | Attansic L1 Gigabit Ethernet | 368   | atl1       | D7FBB47C8B |
| 8086:15a1 | 1043:85c4 | Intel      | Ethernet Connection (2) I... | 346   | e1000e     | 5A5D3A54C3 |
| 8086:15b8 | 1458:e000 | Intel      | Ethernet Connection (2) I... | 343   | e1000e     | DD22D96D07 |
| 10ec:8168 | 7470:3468 | Realtek... | RTL8111/8168/8411 PCI Exp... | 333   | r8169      | 7A70FC2989 |
| 10ec:8168 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 323   | r8169      | 5E80D808A1 |
| 1969:1083 | 1458:e000 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 318   | atl1c      | F493A9D83B |
| 11ab:4364 | 1043:81f8 | Marvell... | 88E8056 PCI-E Gigabit Eth... | 295   | sky2       | 6C7ECC284B |
| 10ec:8169 | 10ec:8169 | Realtek... | RTL8169 PCI Gigabit Ether... | 293   | r8169      | DFA80F4B9F |
| 8086:15b8 | 1849:15b8 | Intel      | Ethernet Connection (2) I... | 278   | e1000e     | 5130E7EC94 |
| 10ec:8168 | 1043:16d5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 273   | r8169      | 9D10643A15 |
| 10ec:8168 | 1043:82c6 | Realtek... | RTL8111/8168/8411 PCI Exp... | 245   | r8169      | A0BD55A486 |
| 10de:0ab0 | 10de:cb79 | Nvidia     | MCP79 Ethernet               | 243   | forcedeth  | 25B2F96576 |
| 10ec:8136 | 1849:8136 | Realtek... | RTL810xE PCI Express Fast... | 241   | r8169      | C96A2AA7A8 |
| 8086:15bc | 1043:8672 | Intel      | Ethernet Connection (7) I... | 236   | e1000e     | 22A32FC3F2 |
| 197b:0250 | 1043:1905 | JMicron... | JMC250 PCI Express Gigabi... | 235   | jme        | D5A8ADB8C9 |
| 1969:2062 | 1043:8468 | Attansi... | AR8152 v2.0 Fast Ethernet    | 229   | atl1c      | 95653B7969 |
| 14e4:1686 | 14e4:1686 | Broadcom   | NetXtreme BCM57766 Gigabi... | 220   | tg3        | CA3C48F689 |
| 1969:1083 | 1043:1851 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 220   | atl1c      | 997A879973 |
| 1969:1091 | 1458:e000 | Qualcom... | AR8161 Gigabit Ethernet      | 219   | alx        | FB7BEB9612 |
| 8086:155a | 17aa:2214 | Intel      | Ethernet Connection I218-LM  | 214   | e1000e     | F802ABEF07 |
| 14e4:16b5 | 1025:0504 | Broadcom   | NetLink BCM57785 Gigabit ... | 213   | tg3        | F86CA58100 |
| 1106:3106 | 1186:1405 | VIA Tec... | VT6105/VT6106S [Rhine-III]   | 204   | via_rhine  | 8A6B85A2D2 |
| 8086:15bc | 1458:e000 | Intel      | Ethernet Connection (7) I... | 197   | e1000e     | 1C2A383C4F |
| 8086:153b | 1458:e000 | Intel      | Ethernet Connection I217-V   | 193   | e1000e     | CE787D81EF |
| 10ec:8168 | 1025:8000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 192   | r8169      | 01DBF1B5EC |
| 8086:15a2 | 17aa:2226 | Intel      | Ethernet Connection (3) I... | 187   | e1000e     | 55689E67B3 |
| 8086:153a | 1028:05a4 | Intel      | Ethernet Connection I217-LM  | 185   | e1000e     | 827CB9A77A |
| 11ab:436a | 11ab:00ba | Marvell... | 88E8058 PCI-E Gigabit Eth... | 184   | sky2       | 23D7C3ED4A |
| 10ec:8168 | 1043:87c3 | Realtek... | RTL8111/8168/8411 PCI Exp... | 183   | r8169      | A525C8911B |
| 14e4:1692 | 1025:036d | Broadcom   | NetLink BCM57780 Gigabit ... | 183   | tg3        | D9521929DA |
| 1969:1026 | 1043:8304 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 181   | atl1e      | 97A2C9D098 |
| 10ec:8168 | 1462:7817 | Realtek... | RTL8111/8168/8411 PCI Exp... | 180   | r8169      | 0420EDF711 |
| 8086:15f3 | 1043:87d2 | Intel      | Ethernet Controller I225-V   | 179   | igc        | 82E27C0415 |
| 8086:156f | 17aa:2233 | Intel      | Ethernet Connection I219-LM  | 178   | e1000e     | 623506F87F |
| 10ec:8168 | 1462:7c37 | Realtek... | RTL8111/8168/8411 PCI Exp... | 177   | r8169      | 6B0A992D9F |
| 10ec:8168 | 17aa:5002 | Realtek... | RTL8111/8168/8411 PCI Exp... | 177   | r8169      | 779684E41D |
| 10ec:8168 | 1462:7c02 | Realtek... | RTL8111/8168/8411 PCI Exp... | 173   | r8169      | 9BCD3D5479 |
| 1969:1063 | 1043:1820 | Qualcom... | AR8131 Gigabit Ethernet      | 166   | atl1c      | E3FC4E0622 |
| 10ec:8136 | 1179:ff00 | Realtek... | RTL810xE PCI Express Fast... | 163   | r8169      | 01EB2C3459 |
| 14e4:1693 | 1025:011c | Broadcom   | NetLink BCM5787M Gigabit ... | 160   | tg3        | 8592F1650F |
| 1969:1090 | 17aa:3979 | Qualcom... | AR8162 Fast Ethernet         | 156   | alx        | EE0A6FC9CA |
| 10ec:8168 | 1025:1331 | Realtek... | RTL8111/8168/8411 PCI Exp... | 151   | r8169      | BC9DC107D1 |
| 10ec:8168 | 17aa:3812 | Realtek... | RTL8111/8168/8411 PCI Exp... | 151   | r8169      | 0CDC6E9D84 |
| 1969:2062 | 17aa:3979 | Qualcom... | AR8152 v2.0 Fast Ethernet    | 151   | atl1c      | D1D57448C4 |
| 11ab:4320 | 1043:811a | Marvell... | 88E8001 Gigabit Ethernet ... | 150   | skge       | 1739E3B05D |
| 10ec:8168 | 17aa:38bb | Realtek... | RTL8111/8168/8411 PCI Exp... | 147   | r8169      | F86520F5A7 |
| 10ec:8136 | 1043:8347 | Realtek... | RTL810xE PCI Express Fast... | 146   | r8169      | 1D5227420F |
| 14e4:16b3 | 1025:0775 | Broadcom   | NetXtreme BCM57786 Gigabi... | 145   | tg3        | 921FC6B490 |
| 10ec:8168 | 1462:7721 | Realtek... | RTL8111/8168/8411 PCI Exp... | 141   | r8169      | 69DA26C946 |
| 8086:153b | 1043:859f | Intel      | Ethernet Connection I217-V   | 141   | e1000e     | F6DE3176E5 |
| 14e4:1698 | 1025:0207 | Broadcom   | NetLink BCM5784M Gigabit ... | 140   | tg3        | 9B324D7185 |
| 10ec:8168 | 1043:81aa | Realtek... | RTL8111/8168/8411 PCI Exp... | 139   | r8169      | 1207B5D281 |
| 10ec:8136 | 17aa:3975 | Realtek... | RTL810xE PCI Express Fast... | 137   | r8169      | 16EBDC4388 |
| 10ec:8168 | 17aa:5079 | Realtek... | RTL8111/8168/8411 PCI Exp... | 137   | r8169      | A35AAAEB6D |
| 11ab:4381 | 104d:9071 | Marvell... | Yukon Optima 88E8059 [PCI... | 137   | sky2       | A18FB33A6F |
| 10ec:8136 | 1179:ff1e | Realtek... | RTL810xE PCI Express Fast... | 131   | r8169      | A955D2E293 |
| 14e4:1684 | 14e4:1684 | Broadcom   | NetXtreme BCM5764M Gigabi... | 131   | tg3        | BD1CB6F826 |
| 10ec:8136 | 1028:04b0 | Realtek... | RTL810xE PCI Express Fast... | 129   | r8169      | 532A1D3D01 |
| 10ec:8168 | 1462:7b86 | Realtek... | RTL8111/8168/8411 PCI Exp... | 129   | r8169      | 7E563A9D44 |
| 8086:15be | 8086:2074 | Intel      | Ethernet Connection (6) I... | 129   | e1000e     | 7EEEAAA250 |
| 10ec:8168 | 1b0a:20d9 | Realtek... | RTL8111/8168/8411 PCI Exp... | 128   | r8169      | 1EDD4700FD |
| 1969:2048 | 1043:8233 | Qualcom... | Attansic L2 Fast Ethernet    | 128   | atl2       | FA7AD6E131 |
| 10ec:8136 | 10ec:8136 | Realtek... | RTL810xE PCI Express Fast... | 127   | r8169      | 1BF61C0698 |
| 1969:1026 | 1043:14f5 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 127   | atl1e      | 0DC4D38ED2 |
| 1969:1026 | 1043:8226 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 126   | atl1e      | F6317B60DD |
| 1969:e091 | 1458:e000 | Qualcom... | Killer E220x Gigabit Ethe... | 126   | alx        | 9A9B258736 |
| 1969:10a1 | 1849:10a1 | Qualcom... | QCA8171 Gigabit Ethernet     | 125   | alx        | B676D9030A |
| 10ec:8168 | 1025:1193 | Realtek... | RTL8111/8168/8411 PCI Exp... | 121   | r8169      | 43BFEF3BCD |
| 10ec:8168 | 1025:0866 | Realtek... | RTL8111/8168/8411 PCI Exp... | 118   | r8169      | 11EBF2008B |
| 10ec:8168 | 1043:205f | Realtek... | RTL8111/8168/8411 PCI Exp... | 118   | r8169      | 66B9CEA0F2 |
| 14e4:16b1 | 1849:96b1 | Broadcom   | NetLink BCM57781 Gigabit ... | 118   | tg3        | F6F957DDF3 |
| 8086:153a | 17aa:220e | Intel      | Ethernet Connection I217-LM  | 118   | e1000e     | 36F407C3AA |
| 10ec:8168 | 103c:8330 | Realtek... | RTL8111/8168/8411 PCI Exp... | 117   | r8169      | 18CEA74915 |
| 8086:15a1 | 1849:15a1 | Intel      | Ethernet Connection (2) I... | 117   | e1000e     | 2BF61F2EC6 |
| 1969:1062 | 1043:838a | Qualcom... | AR8132 Fast Ethernet         | 116   | atl1c      | E74DC83F0A |
| 10ec:8168 | 17aa:388a | Realtek... | RTL8111/8168/8411 PCI Exp... | 114   | r8169      | 4EB6B00CAC |
| 8086:155a | 103c:198f | Intel      | Ethernet Connection I218-LM  | 114   | e1000e     | CECD552E89 |
| 10ec:8168 | 1043:1277 | Realtek... | RTL8111/8168/8411 PCI Exp... | 112   | r8169      | FC712846D9 |
| 10ec:8168 | 1462:7a38 | Realtek... | RTL8111/8168/8411 PCI Exp... | 112   | r8169      | 11F7EC8B16 |
| 10ec:8136 | 1028:0810 | Realtek... | RTL810xE PCI Express Fast... | 110   | r8169      | C01FA4B013 |
| 14e4:1713 | 17aa:3a23 | Broadcom   | NetLink BCM5906M Fast Eth... | 110   | tg3        | C53BA56444 |
| 1969:1026 | 1043:831c | Qualcom... | AR8121/AR8113/AR8114 Giga... | 110   | atl1e      | 01EC64F498 |
| 10ec:8168 | 17aa:3816 | Realtek... | RTL8111/8168/8411 PCI Exp... | 109   | r8169      | 1387FAB9FE |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2723 | 8086:0084 | Intel      | Wi-Fi 6 AX200                | 2538  | iwlwifi    | F581CF8319 |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 1251  | iwlwifi    | C537345CE8 |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 1042  | iwlwifi    | 9C8BB9558A |
| 8086:0085 | 8086:1311 | Intel      | Centrino Advanced-N 6205 ... | 1036  | iwlwifi    | A120083D3C |
| 168c:002b | 1a3b:1089 | Qualcom... | AR9285 Wireless Network A... | 1016  | ath9k      | E3FC4E0622 |
| 8086:a370 | 8086:0034 | Intel      | Cannon Lake PCH CNVi WiFi    | 964   | iwlwifi    | 2FC377709D |
| 168c:0042 | 11ad:08a6 | Qualcom... | QCA9377 802.11ac Wireless... | 939   | ath10k_pci | CFA7B4AF8F |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 832   | rtl8821ce  | 3A06ECCCAA |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 817   | iwlwifi    | EEB181F50B |
| 8086:9df0 | 8086:0034 | Intel      | Cannon Point-LP CNVi [Wir... | 799   | iwlwifi    | 7EEEAAA250 |
| 8086:2526 | 8086:0014 | Intel      | Wireless-AC 9260             | 788   | iwlwifi    | 27E29303BC |
| 168c:0042 | 17aa:0901 | Qualcom... | QCA9377 802.11ac Wireless... | 770   | ath10k_pci | 5154E96ABE |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 733   | iwlwifi    | 4EB6B00CAC |
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 715   | iwlwifi    | 9347A8D008 |
| 168c:0042 | 1028:1810 | Qualcom... | QCA9377 802.11ac Wireless... | 657   | ath10k_pci | 60F4AC8CC5 |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 623   | iwlwifi    | 1069B24865 |
| 10ec:d723 | 103c:8319 | Realtek... | RTL8723DE Wireless Networ... | 620   | rtl8723de  | F4D2F1104E |
| 1814:3290 | 103c:18ec | Ralink     | RT3290 Wireless 802.11n 1... | 561   | rt2800pci  | FBF77D8C63 |
| 8086:02f0 | 8086:0074 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 543   | iwlwifi    | A35AAAEB6D |
| 8086:2723 | 8086:0080 | Intel      | Wi-Fi 6 AX200                | 511   | iwlwifi    | E9A8FB1275 |
| 8086:a0f0 | 8086:0074 | Intel      | Wi-Fi 6 AX201                | 457   | iwlwifi    | EFDB9E6636 |
| 168c:0036 | 1028:020c | Qualcom... | QCA9565 / AR9565 Wireless... | 455   | ath9k      | 0F2394B49D |
| 8086:088e | 8086:4060 | Intel      | Centrino Advanced-N 6235     | 437   | iwlwifi    | 95C381CCD9 |
| 8086:3165 | 8086:4410 | Intel      | Wireless 3165                | 430   | iwlwifi    | 8894639B19 |
| 168c:0036 | 1028:020e | Qualcom... | QCA9565 / AR9565 Wireless... | 429   | ath9k      | 5900E800AA |
| 168c:0036 | 11ad:0642 | Qualcom... | QCA9565 / AR9565 Wireless... | 425   | ath9k      | 269771FE3E |
| 10ec:b822 | 103c:831b | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 423   | rtwpci     | 6B8CF94EA2 |
| 168c:003e | 1a56:1535 | Qualcom... | QCA6174 802.11ac Wireless... | 403   | ath10k_pci | EDD545A455 |
| 8086:4237 | 8086:1211 | Intel      | PRO/Wireless 5100 AGN [Sh... | 397   | iwlwifi    | 9A7BE426F5 |
| 8086:06f0 | 8086:0074 | Intel      | Comet Lake PCH CNVi WiFi     | 393   | iwlwifi    | 32F01CCAAB |
| 8086:24f3 | 8086:0010 | Intel      | Wireless 8260                | 389   | iwlwifi    | 6E020F3AD1 |
| 10ec:c821 | 17aa:c024 | Realtek... | RTL8821CE 802.11ac PCIe W... | 387   | rtl8821ce  | 8DB63E7A74 |
| 168c:0032 | 1a3b:2c97 | Qualcom... | AR9485 Wireless Network A... | 381   | ath9k      | 58CC91ABA3 |
| 168c:0032 | 144d:4105 | Qualcom... | AR9485 Wireless Network A... | 372   | ath9k      | EC15C793BF |
| 8086:08b2 | 8086:c270 | Intel      | Wireless 7260                | 369   | iwlwifi    | F802ABEF07 |
| 8086:08b1 | 8086:4070 | Intel      | Wireless 7260                | 366   | iwlwifi    | 1BB97BC7DF |
| 8086:4232 | 8086:1201 | Intel      | WiFi Link 5100               | 365   | iwlwifi    | 9B324D7185 |
| 8086:4222 | 8086:1001 | Intel      | PRO/Wireless 3945ABG [Gol... | 364   | iwl3945    | 1517AC0D45 |
| 8086:4239 | 8086:1311 | Intel      | Centrino Advanced-N 6200     | 364   | iwlwifi    | 8B21B7CFFE |
| 8086:0082 | 8086:1321 | Intel      | Centrino Advanced-N 6205 ... | 353   | iwlwifi    | D040F874C9 |
| 14e4:4365 | 17aa:0611 | Broadcom   | BCM43142 802.11b/g/n         | 351   | wl         | 779684E41D |
| 8086:24fd | 8086:0050 | Intel      | Wireless 8265 / 8275         | 350   | iwlwifi    | 3D0FD285B6 |
| 168c:002b | 17aa:30a1 | Qualcom... | AR9285 Wireless Network A... | 341   | ath9k      | EE0A6FC9CA |
| 8086:0887 | 8086:4062 | Intel      | Centrino Wireless-N 2230     | 338   | iwlwifi    | EBEA056239 |
| 168c:002b | 1a3b:2c37 | Qualcom... | AR9285 Wireless Network A... | 327   | ath9k      | 997A879973 |
| 168c:003e | 11ad:0807 | Qualcom... | QCA6174 802.11ac Wireless... | 327   | ath10k_pci | 66255CA7B5 |
| 168c:0034 | 105b:e052 | Qualcom... | AR9462 Wireless Network A... | 325   | ath9k      | 7302DC6BE1 |
| 8086:4238 | 8086:1111 | Intel      | Centrino Ultimate-N 6300     | 317   | iwlwifi    | 69A252CCD6 |
| 8086:08b1 | 8086:4470 | Intel      | Wireless 7260                | 314   | iwlwifi    | EC8AF5F350 |
| 168c:003e | 1028:0310 | Qualcom... | QCA6174 802.11ac Wireless... | 311   | ath10k_pci | DA5E2F59CC |
| 168c:002e | 105b:e034 | Qualcom... | AR9287 Wireless Network A... | 306   | ath9k      | 7EAEAE034C |
| 8086:422b | 8086:1121 | Intel      | Centrino Ultimate-N 6300     | 301   | iwlwifi    | F442DF91A1 |
| 14e4:4315 | 1028:000c | Broadco... | BCM4312 802.11b/g LP-PHY     | 296   | wl         | E475348B1E |
| 8086:24fd | 8086:0110 | Intel      | Wireless 8265 / 8275         | 293   | iwlwifi    | 31B241368B |
| 14e4:4727 | 103c:1483 | Broadcom   | BCM4313 802.11bgn Wireles... | 292   | wl         | F696958F46 |
| 8086:0082 | 8086:1301 | Intel      | Centrino Advanced-N 6205 ... | 292   | iwlwifi    | 4639F065C8 |
| 10ec:b723 | 17aa:b736 | Realtek... | RTL8723BE PCIe Wireless N... | 291   | rtl8723be  | B76F24F640 |
| 8086:34f0 | 8086:0074 | Intel      | Ice Lake-LP PCH CNVi WiFi    | 290   | iwlwifi    | 7125C6F5DD |
| 10ec:c822 | 103c:85f7 | Realtek... | RTL8822CE 802.11ac PCIe W... | 284   | rtw88_8... | 2BA5AE42BB |
| 8086:3165 | 8086:8010 | Intel      | Wireless 3165                | 282   | iwlwifi    | 44ACFE85A5 |
| 168c:0032 | 11ad:6617 | Qualcom... | AR9485 Wireless Network A... | 281   | ath9k      | 5EBEDD4A1C |
| 8086:4229 | 8086:1101 | Intel      | PRO/Wireless 4965 AG or A... | 275   | iwl4965    | 3332A4C510 |
| 10ec:c821 | 1a3b:3040 | Realtek... | RTL8821CE 802.11ac PCIe W... | 273   | rtl8821ce  | 67F0B45A7A |
| 14e4:43a0 | 106b:0117 | Broadco... | BCM4360 802.11ac Wireless... | 269   | wl         | 5BE083EDAB |
| 168c:0036 | 17aa:4026 | Qualcom... | QCA9565 / AR9565 Wireless... | 269   | ath9k      | 07D05077AF |
| 8086:24f3 | 8086:0050 | Intel      | Wireless 8260                | 268   | iwlwifi    | E7A049A026 |
| 8086:095b | 8086:5210 | Intel      | Wireless 7265                | 265   | iwlwifi    | EB89BBEBFE |
| 168c:0032 | 1028:0209 | Qualcom... | AR9485 Wireless Network A... | 261   | ath9k      | D70E2B74D0 |
| 8086:24f3 | 8086:1010 | Intel      | Wireless 8260                | 261   | iwlwifi    | 767EB7C6D3 |
| 168c:0032 | 103c:1838 | Qualcom... | AR9485 Wireless Network A... | 258   | ath9k      | AB5E53C9ED |
| 8086:095a | 8086:5410 | Intel      | Wireless 7265                | 258   | iwlwifi    | 9834990221 |
| 8086:24fd | 8086:9010 | Intel      | Wireless 8265 / 8275         | 254   | iwlwifi    | 82B124D8C4 |
| 8086:0896 | 8086:5005 | Intel      | Centrino Wireless-N 130      | 252   | iwlwifi    | A83E302ABA |
| 10ec:b723 | 11ad:1723 | Realtek... | RTL8723BE PCIe Wireless N... | 248   | rtl8723be  | 4C2453C6A2 |
| 10ec:b723 | 103c:81c1 | Realtek... | RTL8723BE PCIe Wireless N... | 247   | rtl8723be  | 69C8804209 |
| 8086:0084 | 8086:1315 | Intel      | Centrino Wireless-N 1000 ... | 246   | iwlwifi    | 570863FD8C |
| 8086:24f3 | 8086:0130 | Intel      | Wireless 8260                | 242   | iwlwifi    | F45B082C14 |
| 168c:0032 | 1a3b:1186 | Qualcom... | AR9485 Wireless Network A... | 241   | ath9k      | 2E47DD4121 |
| 14e4:4727 | 1028:0010 | Broadcom   | BCM4313 802.11bgn Wireles... | 240   | wl         | 4AD73429AF |
| 8086:08b3 | 8086:0070 | Intel      | Wireless 3160                | 232   | iwlwifi    | 36ACEDB60B |
| 10ec:b822 | 17aa:b023 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 231   | rtwpci     | 8272A05168 |
| 10ec:c822 | 17aa:c123 | Realtek... | RTL8822CE 802.11ac PCIe W... | 231   | rtw88_8... | 497BF56CC6 |
| 14e4:4727 | 103c:145c | Broadcom   | BCM4313 802.11bgn Wireles... | 228   | wl         | 7312570938 |
| 8086:2723 | 1a56:1654 | Intel      | Wi-Fi 6 AX200                | 227   | iwlwifi    | 58E43F0514 |
| 10ec:8821 | 17aa:a814 | Realtek... | RTL8821AE 802.11ac PCIe W... | 225   | rtl8821ae  | 2BF6813AD9 |
| 168c:002b | 105b:e035 | Qualcom... | AR9285 Wireless Network A... | 223   | ath9k      | 55BA94A26E |
| 168c:002e | 168c:30a4 | Qualcom... | AR9287 Wireless Network A... | 223   | ath9k      | D04DAE2A56 |
| 10ec:8179 | 103c:197d | Realtek... | RTL8188EE Wireless Networ... | 222   | rtl8188ee  | 22807CB857 |
| 14e4:4365 | 103c:804a | Broadcom   | BCM43142 802.11b/g/n         | 217   | wl         | 65C122FE69 |
| 168c:0034 | 11ad:6621 | Qualcom... | AR9462 Wireless Network A... | 214   | ath9k      | B953B67D06 |
| 168c:001c | 1a3b:1026 | Qualcom... | AR242x / AR542x Wireless ... | 213   | ath5k      | 7A2E7C66E9 |
| 10ec:c822 | 1058:1e25 | Realtek... | RTL8822CE 802.11ac PCIe W... | 212   | rtw88_8... | C0B80E3276 |
| 168c:002b | 103c:3040 | Qualcom... | AR9285 Wireless Network A... | 212   | ath9k      | E84CD86EB0 |
| 168c:0032 | 11ad:6627 | Qualcom... | AR9485 Wireless Network A... | 211   | ath9k      | 50B1B1A6C5 |
| 8086:08b4 | 8086:8270 | Intel      | Wireless 3160                | 211   | iwlwifi    | 2ECC44141A |
| 8086:08b3 | 8086:8470 | Intel      | Wireless 3160                | 210   | iwlwifi    | D876CAAE1E |
| 8086:9df0 | 8086:0030 | Intel      | Cannon Point-LP CNVi [Wir... | 206   | iwlwifi    | F8024B89D4 |
| 168c:0032 | 168c:3118 | Qualcom... | AR9485 Wireless Network A... | 205   | ath9k      | 0FFE725912 |
| 168c:003e | 1a56:143a | Qualcom... | QCA6174 802.11ac Wireless... | 202   | ath10k_pci | 5A56854746 |
| 168c:0042 | 1a3b:2b31 | Qualcom... | QCA9377 802.11ac Wireless... | 196   | ath10k_pci | 363C1A3642 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1539 | 1043:85f0 | Intel      | I211 Gigabit Network Conn... | 914   | igb        | 6E020F3AD1 |
| 8086:1539 | 1458:e000 | Intel      | I211 Gigabit Network Conn... | 669   | igb        | 6B471BC42D |
| 8086:1502 | 17aa:21f3 | Intel      | 82579LM Gigabit Network C... | 570   | e1000e     | 69A252CCD6 |
| 8086:1539 | 1849:1539 | Intel      | I211 Gigabit Network Conn... | 511   | igb        | C537345CE8 |
| 8086:1502 | 17aa:21ce | Intel      | 82579LM Gigabit Network C... | 491   | e1000e     | 0A8E84DFAD |
| 8086:1503 | 1043:849c | Intel      | 82579V Gigabit Network Co... | 426   | e1000e     | EAF4F27F7A |
| 10de:03ef | 1849:03ef | Nvidia     | MCP61 Ethernet               | 391   | forcedeth  | 0F23350175 |
| 8086:10ea | 17aa:2153 | Intel      | 82577LM Gigabit Network C... | 306   | e1000e     | 8B21B7CFFE |
| 8086:1502 | 1028:052c | Intel      | 82579LM Gigabit Network C... | 260   | e1000e     | E1B966B80D |
| 8086:10f5 | 17aa:20ee | Intel      | 82567LM Gigabit Network C... | 224   | e1000e     | 9A7BE426F5 |
| 8086:1502 | 1028:047e | Intel      | 82579LM Gigabit Network C... | 223   | e1000e     | D6237E9949 |
| 10de:03ef | 1458:e000 | Nvidia     | MCP61 Ethernet               | 195   | forcedeth  | 701EE8CE26 |
| 10ec:8125 | 1458:e000 | Realtek... | RTL8125 2.5GbE Controller    | 185   | r8169      | 93B56B7543 |
| 8086:10de | 1028:0276 | Intel      | 82567LM-3 Gigabit Network... | 183   | e1000e     | C67A8BB677 |
| 8086:10d3 | 8086:a01f | Intel      | 82574L Gigabit Network Co... | 171   | e1000e     | B14C0E8DD2 |
| 8086:1502 | 1028:0493 | Intel      | 82579LM Gigabit Network C... | 158   | e1000e     | 4C3C43DAAA |
| 10de:03ef | 1043:83a4 | Nvidia     | MCP61 Ethernet               | 150   | forcedeth  | 324F6E5FAD |
| 8086:10ea | 1028:040a | Intel      | 82577LM Gigabit Network C... | 146   | e1000e     | BA51FC9216 |
| 8086:1502 | 1028:0534 | Intel      | 82579LM Gigabit Network C... | 137   | e1000e     | FA4D12994D |
| 8086:10f5 | 1028:0233 | Intel      | 82567LM Gigabit Network C... | 123   | e1000e     | 6B7EF9CAD5 |
| 10de:03ef | 1043:8234 | Nvidia     | MCP61 Ethernet               | 116   | forcedeth  | 91FE7919BE |
| 8086:1502 | 103c:161c | Intel      | 82579LM Gigabit Network C... | 115   | e1000e     | B6AC4539D1 |
| 8086:10bd | 1028:0211 | Intel      | 82566DM-2 Gigabit Network... | 109   | e1000e     | 7E7D0BC489 |
| 8086:1502 | 103c:179b | Intel      | 82579LM Gigabit Network C... | 109   | e1000e     | 1B2FBCDFA0 |
| 8086:1502 | 103c:3397 | Intel      | 82579LM Gigabit Network C... | 109   | e1000e     | BF9875C5AC |
| 8086:1049 | 17aa:20b9 | Intel      | 82566MM Gigabit Network C... | 99    | e1000e     | 87E69E1105 |
| 8086:1521 | 15d9:1521 | Intel      | I350 Gigabit Network Conn... | 98    | igb        | 9EFBA142DD |
| 10ec:8125 | 1043:87d7 | Realtek... | RTL8125 2.5GbE Controller    | 94    | r8169      | 4BA408D68C |
| 8086:10de | 1028:027f | Intel      | 82567LM-3 Gigabit Network... | 89    | e1000e     | AADCA45789 |
| 8086:1502 | 103c:339a | Intel      | 82579LM Gigabit Network C... | 89    | e1000e     | 28DA82FF00 |
| 8086:1539 | 8086:0000 | Intel      | I211 Gigabit Network Conn... | 87    | igb        | 7F5E602975 |
| 8086:1502 | 103c:1495 | Intel      | 82579LM Gigabit Network C... | 79    | e1000e     | 28835849F0 |
| 8086:1502 | 103c:1497 | Intel      | 82579LM Gigabit Network C... | 78    | e1000e     | C0FB875CA5 |
| 8086:10bd | 103c:2818 | Intel      | 82566DM-2 Gigabit Network... | 75    | e1000e     | 74CFC314C6 |
| 8086:1533 | 15d9:1533 | Intel      | I210 Gigabit Network Conn... | 75    | igb        | 6A333A499D |
| 8086:1533 | 1043:8557 | Intel      | I210 Gigabit Network Conn... | 72    | igb        | 2591B8710E |
| 10de:03ef | 1462:7309 | Nvidia     | MCP61 Ethernet               | 70    | forcedeth  | 0A4D7FB95D |
| 8086:1533 | ffff:0000 | Intel      | I210 Gigabit Network Conn... | 70    | igb        | CE3945EA8E |
| 8086:10de | 103c:3048 | Intel      | 82567LM-3 Gigabit Network... | 69    | e1000e     | B62359FCB1 |
| 8086:10ea | 103c:172a | Intel      | 82577LM Gigabit Network C... | 67    | e1000e     | F527983CC9 |
| 8086:1502 | 1028:0535 | Intel      | 82579LM Gigabit Network C... | 67    | e1000e     | FD1375D5F1 |
| 8086:10c0 | 1028:020d | Intel      | 82562V-2 10/100 Network C... | 65    | e1000e     | E77852D5C2 |
| 8086:1502 | 1028:0494 | Intel      | 82579LM Gigabit Network C... | 65    | e1000e     | B84EF4472B |
| 8086:1503 | 1458:e000 | Intel      | 82579V Gigabit Network Co... | 64    | e1000e     | 8D74DD99C7 |
| 8086:1502 | 10cf:161b | Intel      | 82579LM Gigabit Network C... | 61    | e1000e     | 7FAB4F85E2 |
| 10ec:8125 | 1849:8125 | Realtek... | RTL8125 2.5GbE Controller    | 60    | r8169      | 1FCC4E6895 |
| 8086:10d3 | 1043:8369 | Intel      | 82574L Gigabit Network Co... | 59    | e1000e     | F0983027EE |
| 8086:10c4 | 103c:30d8 | Intel      | 82562GT 10/100 Network Co... | 58    | e1000e     | E880C038EB |
| 10ec:8125 | 1462:7c91 | Realtek... | RTL8125 2.5GbE Controller    | 57    | r8169      | 27B0A66CEB |
| 8086:104a | 103c:2800 | Intel      | 82566DM Gigabit Network C... | 56    | e1000e     | D3B19636D9 |
| 8086:1503 | 1025:8000 | Intel      | 82579V Gigabit Network Co... | 56    | e1000e     | 967427D98C |
| 8086:10ea | 1028:040b | Intel      | 82577LM Gigabit Network C... | 55    | e1000e     | 2AB208B5CD |
| 8086:294c | 8086:0001 | Intel      | 82566DC-2 Gigabit Network... | 54    | e1000e     | A5121E1871 |
| 10de:0057 | 1043:812a | Nvidia     | CK804 Ethernet Controller    | 53    | forcedeth  | F9BFF20C4D |
| 14e4:170c | 1025:0090 | Broadcom   | BCM4401-B0 100Base-TX        | 52    | b44        | B09A0D7779 |
| 8086:10eb | 103c:1471 | Intel      | 82577LC Gigabit Network C... | 52    | e1000e     | 4DB59C8489 |
| 8086:10ea | 103c:7008 | Intel      | 82577LM Gigabit Network C... | 50    | e1000e     | F31AC36B11 |
| 8086:10f5 | 1028:024f | Intel      | 82567LM Gigabit Network C... | 49    | e1000e     | E475348B1E |
| 8086:1502 | 103c:162b | Intel      | 82579LM Gigabit Network C... | 49    | e1000e     | 28D13C49B3 |
| 8086:1502 | 10f7:8338 | Intel      | 82579LM Gigabit Network C... | 49    | e1000e     | 1AED5AEDC2 |
| 10de:0373 | 1043:8239 | Nvidia     | MCP55 Ethernet               | 47    | forcedeth  | 775AEB5400 |
| 8086:10d3 | 15d9:10d3 | Intel      | 82574L Gigabit Network Co... | 47    | e1000e     | 9CC6367D9F |
| 8086:10f0 | 8086:0036 | Intel      | 82578DC Gigabit Network C... | 47    | e1000e     | E5F7233230 |
| 8086:1502 | 103c:18df | Intel      | 82579LM Gigabit Network C... | 47    | e1000e     | F66BA65DC8 |
| 10ec:8125 | 1462:7c35 | Realtek... | RTL8125 2.5GbE Controller    | 46    | r8169      | 8EA75A2EC0 |
| 8086:1502 | 103c:1589 | Intel      | 82579LM Gigabit Network C... | 46    | e1000e     | 49C747EFAD |
| 8086:150c | 1043:8457 | Intel      | 82583V Gigabit Network Co... | 45    | e1000e     | 44DA1EA889 |
| 8086:10df | 1734:114d | Intel      | 82567LF-3 Gigabit Network... | 44    | e1000e     | 138CA0F31D |
| 8086:1502 | 103c:1618 | Intel      | 82579LM Gigabit Network C... | 44    | e1000e     | 48828AD0D3 |
| 8086:1502 | 17aa:3070 | Intel      | 82579LM Gigabit Network C... | 44    | e1000e     | 1ECB7A6910 |
| 8086:1503 | 10cf:161c | Intel      | 82579V Gigabit Network Co... | 44    | e1000e     | 4639F065C8 |
| 10ec:8125 | 1462:7c84 | Realtek... | RTL8125 2.5GbE Controller    | 43    | r8169      | 688A36C9DF |
| 8086:10ea | 103c:1521 | Intel      | 82577LM Gigabit Network C... | 43    | e1000e     | 40F54639E6 |
| 8086:1502 | 1028:0492 | Intel      | 82579LM Gigabit Network C... | 43    | e1000e     | E8538CE77D |
| 8086:157b | 8086:0000 | Intel      | I210 Gigabit Network Conn... | 43    | igb        | 507FBFC464 |
| 8086:10bd | 103c:281e | Intel      | 82566DM-2 Gigabit Network... | 42    | e1000e     | EAA60F7610 |
| 10de:03ef | 103c:2a6c | Nvidia     | MCP61 Ethernet               | 41    | forcedeth  | 929E48A398 |
| 14e4:170c | 1028:01f5 | Broadcom   | BCM4401-B0 100Base-TX        | 41    | b44        | 58A2EF72C9 |
| 8086:10c0 | 1028:0238 | Intel      | 82562V-2 10/100 Network C... | 41    | e1000e     | D879289E3A |
| 8086:10de | 17aa:3048 | Intel      | 82567LM-3 Gigabit Network... | 41    | e1000e     | ED1D55E70A |
| 8086:1539 | 1462:7a32 | Intel      | I211 Gigabit Network Conn... | 41    | igb        | 3ABF73FB8A |
| 10ec:8168 | 17aa:505b | Realtek... | RTL8111/8168/8411 PCI Exp... | 40    | r8169      | 4781A28617 |
| 14e4:170c | 1028:01af | Broadcom   | BCM4401-B0 100Base-TX        | 40    | b44        | FA750DAFE2 |
| 8086:1502 | 103c:1494 | Intel      | 82579LM Gigabit Network C... | 40    | e1000e     | AE5165603A |
| 8086:1503 | 8086:2017 | Intel      | 82579V Gigabit Network Co... | 40    | e1000e     | 43E3FCCC3D |
| 8086:1539 | 1462:7b85 | Intel      | I211 Gigabit Network Conn... | 40    | igb        | DB9BFA58F9 |
| 10de:03ef | 103c:2a99 | Nvidia     | MCP61 Ethernet               | 39    | forcedeth  | 29FD6EAE29 |
| 1106:3065 | 1043:80ed | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 39    | via_rhine  | BE5F9F33D4 |
| 8086:10de | 103c:3034 | Intel      | 82567LM-3 Gigabit Network... | 39    | e1000e     | D05CCA1A32 |
| 8086:10de | 103c:3646 | Intel      | 82567LM-3 Gigabit Network... | 39    | e1000e     | 60FB363058 |
| 8086:10f6 | 8086:0000 | Intel      | 82574L Gigabit Network Co... | 39    | e1000e     | EA3E45A8A7 |
| 8086:1502 | 17aa:3083 | Intel      | 82579LM Gigabit Network C... | 39    | e1000e     | DF15656FCE |
| 8086:1533 | 1849:1533 | Intel      | I210 Gigabit Network Conn... | 39    | igb        | ABF0E06A08 |
| 10ec:8136 | 103c:3567 | Realtek... | RTL810xE PCI Express Fast... | 38    | r8169      | 0585DD7016 |
| 14e4:170c | 103c:30a2 | Broadcom   | BCM4401-B0 100Base-TX        | 38    | b44        | 1E89CEC8EB |
| 8086:10ea | 10cf:1574 | Intel      | 82577LM Gigabit Network C... | 38    | e1000e     | 08576DED50 |
| 8086:1502 | 1028:04a3 | Intel      | 82579LM Gigabit Network C... | 38    | e1000e     | F442DF91A1 |
| 8086:1502 | 1028:0533 | Intel      | 82579LM Gigabit Network C... | 38    | e1000e     | 872CFFF7DA |
| 8086:1503 | 103c:17ab | Intel      | 82579V Gigabit Network Co... | 38    | e1000e     | 0BFBD31BA0 |
| 10de:03ef | 1025:8000 | Nvidia     | MCP61 Ethernet               | 37    | forcedeth  | 9DA4BEFF51 |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:145a | 1022:145a | AMD        | Zeppelin/Raven/Raven2 PCI... | 1925  |            | E52E9002D0 |
| 1022:1455 | 1022:1455 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1890  |            | E52E9002D0 |
| 1022:1485 | 1022:1485 | AMD        | Starship/Matisse Reserved... | 1650  |            | C537345CE8 |
| 1022:148a | 1022:148a | AMD        | Starship/Matisse PCIe Dum... | 1577  |            | C537345CE8 |
| 1022:1485 | 1043:87c0 | AMD        | Starship/Matisse Reserved... | 735   |            | 161865EDB0 |
| 1022:148a | 1043:87c0 | AMD        | Starship/Matisse PCIe Dum... | 735   |            | 161865EDB0 |
| 1022:1455 | 1043:8747 | AMD        | Zeppelin/Renoir PCIe Dumm... | 618   |            | 491D1A96CC |
| 1022:145a | 1043:8747 | AMD        | Zeppelin/Raven/Raven2 PCI... | 618   |            | 491D1A96CC |
| 1022:1485 | 1043:8808 | AMD        | Starship/Matisse Reserved... | 164   |            | A525C8911B |
| 1022:148a | 1043:8808 | AMD        | Starship/Matisse PCIe Dum... | 164   |            | A525C8911B |
| 1022:1485 | 1462:7c02 | AMD        | Starship/Matisse Reserved... | 97    |            | 9BCD3D5479 |
| 1022:148a | 1462:7c02 | AMD        | Starship/Matisse PCIe Dum... | 97    |            | 9BCD3D5479 |
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
| 8086:9d26 |           | Intel      | Skylake-U/Y Northpeak        | 27    | intel_t... | 874D25FF57 |
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
| 1022:1485 | 1558:50f0 | AMD        | Starship/Matisse Reserved... | 17    |            | D63FD746BE |
| 1022:148a | 1558:50f0 | AMD        | Starship/Matisse PCIe Dum... | 17    |            | D63FD746BE |
| 1022:145a | 1462:7b85 | AMD        | Zeppelin/Raven/Raven2 PCI... | 16    |            | 429525379A |
| 1022:1455 | 1462:7b85 | AMD        | Zeppelin/Renoir PCIe Dumm... | 15    |            | 429525379A |
| 1022:1485 | 1043:87e2 | AMD        | Starship/Matisse Reserved... | 14    |            | EE6DBC679C |
| 1022:148a | 1043:87e2 | AMD        | Starship/Matisse PCIe Dum... | 14    |            | EE6DBC679C |
| 8086:5a8e | 8086:7270 | Intel      | Non-Essential Instrumenta... | 14    | intel_t... | BE49BB64E0 |
| 1022:145a | 17aa:3803 | AMD        | Zeppelin/Raven/Raven2 PCI... | 13    |            | C7A45F22C5 |
| 1022:1485 | 1462:7a40 | AMD        | Starship/Matisse Reserved... | 11    |            | 1CA6C5085E |
| 1022:148a | 1462:7a40 | AMD        | Starship/Matisse PCIe Dum... | 11    |            | 1CA6C5085E |
| 1022:1455 | 1462:7a40 | AMD        | Zeppelin/Renoir PCIe Dumm... | 10    |            | 89BF33DB93 |
| 1022:145a | 1462:7a40 | AMD        | Zeppelin/Raven/Raven2 PCI... | 10    |            | 89BF33DB93 |
| 1022:1485 | 1043:876b | AMD        | Starship/Matisse Reserved... | 8     |            | FC6CC9B254 |
| 1022:145a | 1462:7b87 | AMD        | Zeppelin/Raven/Raven2 PCI... | 7     |            | 18FF34F941 |
| 8086:a126 |           | Intel      | 100 Series/C230 Series Ch... | 7     | intel_t... | CC099348C2 |
| 1022:1455 | 1462:7b87 | AMD        | Zeppelin/Renoir PCIe Dumm... | 6     |            | 18FF34F941 |
| 1022:1485 | 1462:7c34 | AMD        | Starship/Matisse Reserved... | 6     |            | 1440E244F6 |
| 1022:1485 | 17aa:1046 | AMD        | Starship/Matisse Reserved... | 6     |            | 136C409F1A |
| 1022:148a | 1462:7c34 | AMD        | Starship/Matisse PCIe Dum... | 6     |            | 1440E244F6 |
| 1022:148a | 17aa:1046 | AMD        | Starship/Matisse PCIe Dum... | 6     |            | 136C409F1A |
| 1022:1455 | 1025:1246 | AMD        | Zeppelin/Renoir PCIe Dumm... | 5     |            | 03FACC3040 |
| 1022:145a | 1002:1636 | AMD        | Zeppelin/Raven/Raven2 PCI... | 5     |            | AE854C2FF2 |
| 1022:145a | 1025:1246 | AMD        | Zeppelin/Raven/Raven2 PCI... | 5     |            | 03FACC3040 |
| 1022:145a | 1462:7b79 | AMD        | Zeppelin/Raven/Raven2 PCI... | 5     |            | 2119A5CDC5 |
| 1022:145a | 1462:7c52 | AMD        | Zeppelin/Raven/Raven2 PCI... | 5     |            | FDA90307D4 |
| 1022:1485 | 1458:1000 | AMD        | Starship/Matisse Reserved... | 5     |            | 96079334BD |
| 1022:1485 | 1462:7c36 | AMD        | Starship/Matisse Reserved... | 5     |            | F61BA12C20 |
| 1022:148a | 1458:1000 | AMD        | Starship/Matisse PCIe Dum... | 5     |            | 96079334BD |
| 1022:148a | 1462:7c36 | AMD        | Starship/Matisse PCIe Dum... | 5     |            | F61BA12C20 |
| 8086:318e |           | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_t... | D08EFA2EF3 |
| 1022:1455 | 1462:7b90 | AMD        | Zeppelin/Renoir PCIe Dumm... | 4     |            | 3642F15AB7 |
| 1022:145a | 103c:879c | AMD        | Zeppelin/Raven/Raven2 PCI... | 4     |            | 0071FAABAC |
| 1022:145a | 1462:7b90 | AMD        | Zeppelin/Raven/Raven2 PCI... | 4     |            | 3642F15AB7 |
| 1022:145a | 1565:170b | AMD        | Zeppelin/Raven/Raven2 PCI... | 4     |            | F0449B9946 |
| 1022:145a | 1d05:1111 | AMD        | Zeppelin/Raven/Raven2 PCI... | 4     |            | 985D394A66 |
| 1022:1485 | 1028:098e | AMD        | Starship/Matisse Reserved... | 4     |            | E1BC8D1CDD |
| 1022:1485 | 1043:8815 | AMD        | Starship/Matisse Reserved... | 4     |            | 8F7011B085 |
| 1022:1485 | 1462:7b87 | AMD        | Starship/Matisse Reserved... | 4     |            | 58A277F8E4 |
| 1022:148a | 1028:098e | AMD        | Starship/Matisse PCIe Dum... | 4     |            | E1BC8D1CDD |
| 1022:148a | 1043:8815 | AMD        | Starship/Matisse PCIe Dum... | 4     |            | 8F7011B085 |
| 1022:148a | 1462:7b87 | AMD        | Starship/Matisse PCIe Dum... | 4     |            | 58A277F8E4 |
| 1022:145a | 1022:7901 | AMD        | Zeppelin/Raven/Raven2 PCI... | 3     |            | 0FA72B5193 |
| 1022:145a | 1462:7a33 | AMD        | Zeppelin/Raven/Raven2 PCI... | 3     |            | 26F4437015 |
| 1022:145a | 1462:7b84 | AMD        | Zeppelin/Raven/Raven2 PCI... | 3     |            | 9644A0A56C |
| 1022:145a | 1462:7c51 | AMD        | Zeppelin/Raven/Raven2 PCI... | 3     |            | 987E9D49E0 |
| 1022:1485 | 1028:08ff | AMD        | Starship/Matisse Reserved... | 3     |            | A35E7D3EB0 |
| 1022:1485 | 1462:7c96 | AMD        | Starship/Matisse Reserved... | 3     |            | EB1233376B |
| 1022:148a | 1028:08ff | AMD        | Starship/Matisse PCIe Dum... | 3     |            | A35E7D3EB0 |
| 1022:148a | 1462:7c96 | AMD        | Starship/Matisse PCIe Dum... | 3     |            | EB1233376B |
| 1022:1455 | 103c:8399 | AMD        | Zeppelin/Renoir PCIe Dumm... | 2     |            | 733813E901 |
| 1022:1455 | 1458:1000 | AMD        | Zeppelin/Renoir PCIe Dumm... | 2     |            | 6D486A7EE9 |
| 1022:145a | 103c:8399 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 733813E901 |
| 1022:145a | 1043:87e1 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 63F68846BB |
| 1022:145a | 1458:1000 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 6D486A7EE9 |
| 1022:145a | 1462:7a34 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | CB6CAEFA10 |
| 1022:145a | 1462:7c37 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 90892D21E5 |
| 1022:1485 | 1028:0a8b | AMD        | Starship/Matisse Reserved... | 2     |            | 5EA23EBFB2 |
| 1022:1485 | 1043:1c81 | AMD        | Starship/Matisse Reserved... | 2     |            | 66B9CEA0F2 |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15e6 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Non-S... | 259   | i2c_amd... | 72CE248D0C |
| 106b:1801 | 106b:1801 | Apple      | T2 Bridge Controller         | 64    | apple_bce  | 7B3CDDA6E2 |
| 106b:1802 | 106b:1802 | Apple      | T2 Secure Enclave Processor  | 64    |            | 7B3CDDA6E2 |
| 8086:9d24 |           | Intel      | Skylake-U/Y SPI Controller   | 64    |            | F3E5EBA0C2 |
| 8086:9d35 | 17aa:2238 | Intel      | Sunrise Point-LP Integrat... | 56    | intel_i... | 623506F87F |
| 8086:9d35 | 8086:9d35 | Intel      | Sunrise Point-LP Integrat... | 56    | intel_i... | 84CEEEACF1 |
| 8086:9d35 | 8086:7270 | Intel      | Sunrise Point-LP Integrat... | 55    | intel_i... | 6039985C3F |
| 1022:15e6 | 103c:85ea | AMD        | Raven/Raven2/Renoir Non-S... | 38    | i2c_amd... | E8781DB5AB |
| 8086:22d8 | 103c:813e | Intel      | Integrated Sensor Solution   | 33    | intel_i... | 0A44B96544 |
| 8086:9d35 | 1028:0740 | Intel      | Sunrise Point-LP Integrat... | 27    | intel_i... | 5246EABC5F |
| 1022:15e6 | 1025:1456 | AMD        | Raven/Raven2/Renoir Non-S... | 26    | i2c_amd... | 09F6196E70 |
| 8086:9d35 | 103c:83b9 | Intel      | Sunrise Point-LP Integrat... | 26    | intel_i... | BBB2DB43B4 |
| 1022:15e4 | 103c:85dd | AMD        | Raven/Raven2/Renoir Senso... | 23    | amd_sfh    | C4EA79E269 |
| 8086:22d8 | 1043:13a0 | Intel      | Integrated Sensor Solution   | 21    | intel_i... | AE0E0904DB |
| 8086:22d8 | 1043:1400 | Intel      | Integrated Sensor Solution   | 21    | intel_i... | 0A301456DC |
| 8086:9d35 | 17aa:380d | Intel      | Sunrise Point-LP Integrat... | 21    | intel_i... | 72617E5DD9 |
| 1022:15e4 | 103c:85de | AMD        | Raven/Raven2/Renoir Senso... | 19    | amd_sfh    | 3ADCB9ECF9 |
| 8086:22d8 | 103c:827c | Intel      | Integrated Sensor Solution   | 18    | intel_i... | 091F7C8FAE |
| 8086:9d35 | 103c:827d | Intel      | Sunrise Point-LP Integrat... | 18    | intel_i... | 95D389BFE5 |
| 1022:15e4 | 103c:8497 | AMD        | Raven/Raven2/Renoir Senso... | 16    | pcie_mp... | 0DFE108C69 |
| 8086:a135 | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 16    | intel_i... | 27D7C254CC |
| 1022:15e4 | 103c:8496 | AMD        | Raven/Raven2/Renoir Senso... | 15    | amd_sfh    | DFB9789AF2 |
| 8086:9d35 | 1028:077a | Intel      | Sunrise Point-LP Integrat... | 15    | intel_i... | 8F7ADB6CD3 |
| 8086:9d35 | 103c:830f | Intel      | Sunrise Point-LP Integrat... | 15    | intel_i... | 3286ED83B9 |
| 8086:9d35 | 103c:8486 | Intel      | Sunrise Point-LP Integrat... | 15    | intel_i... | 7E241B1F69 |
| 8086:9d35 | 152d:1182 | Intel      | Sunrise Point-LP Integrat... | 15    | intel_i... | 5C64BFD9D4 |
| 8086:9d35 | 17aa:2259 | Intel      | Sunrise Point-LP Integrat... | 15    | intel_i... | 36DBFEF2B7 |
| 8086:22d8 | 1043:1bdd | Intel      | Integrated Sensor Solution   | 14    | intel_i... | C518746ECE |
| 8086:9d35 | 17aa:224e | Intel      | Sunrise Point-LP Integrat... | 14    | intel_i... | 3C24D27D51 |
| 8086:9d35 | 103c:827e | Intel      | Sunrise Point-LP Integrat... | 13    | intel_i... | CCA3E863F7 |
| 8086:a135 | 103c:83bb | Intel      | 100 Series/C230 Series Ch... | 13    | intel_i... | BA09E3B76F |
| 8086:9d35 | 103c:80fc | Intel      | Sunrise Point-LP Integrat... | 12    | intel_i... | 89E5AB8846 |
| 8086:9d35 | 103c:83b2 | Intel      | Sunrise Point-LP Integrat... | 12    | intel_i... | 1EEA89F8BB |
| 8086:9d35 | 1028:0804 | Intel      | Sunrise Point-LP Integrat... | 11    | intel_i... | 0E30997FF6 |
| 8086:9d35 | 103c:8488 | Intel      | Sunrise Point-LP Integrat... | 11    | intel_i... | 3AF23C8E87 |
| 8086:9d35 | 1043:1ab0 | Intel      | Sunrise Point-LP Integrat... | 11    | intel_i... | 06E7A51D6A |
| 8086:9d35 | 17aa:2237 | Intel      | Sunrise Point-LP Integrat... | 11    | intel_i... | 24D1BD52CC |
| 8086:9d35 | 17aa:506d | Intel      | Sunrise Point-LP Integrat... | 11    | intel_i... | 99C878CD5E |
| 8086:22d8 | 8086:7270 | Intel      | Integrated Sensor Solution   | 10    | intel_i... | D045383640 |
| 8086:9d35 | 103c:8438 | Intel      | Sunrise Point-LP Integrat... | 10    | intel_i... | AF74E3A1EA |
| 8086:9d35 | 17aa:506c | Intel      | Sunrise Point-LP Integrat... | 10    | intel_i... | B39CD022D3 |
| 8086:9d35 | 1028:07a4 | Intel      | Sunrise Point-LP Integrat... | 9     | intel_i... | 0FAD55C520 |
| 8086:9d35 | 103c:81a1 | Intel      | Sunrise Point-LP Integrat... | 9     | intel_i... | B37CBA5DF4 |
| 8086:9d35 | 1028:073b | Intel      | Sunrise Point-LP Integrat... | 8     | intel_i... | E14ACDFFAD |
| 8086:9d35 | 1028:0742 | Intel      | Sunrise Point-LP Integrat... | 8     | intel_i... | 1169A22F51 |
| 8086:9d35 | 103c:8470 | Intel      | Sunrise Point-LP Integrat... | 8     | intel_i... | 3AF4716969 |
| 8086:9d35 | 103c:8484 | Intel      | Sunrise Point-LP Integrat... | 8     | intel_i... | F3D65BB221 |
| 8086:9d35 | 1028:081d | Intel      | Sunrise Point-LP Integrat... | 7     | intel_i... | 293B45EDED |
| 8086:9d35 | 103c:81ad | Intel      | Sunrise Point-LP Integrat... | 7     | intel_i... | A6FF75E220 |
| 8086:9d35 | 103c:82ca | Intel      | Sunrise Point-LP Integrat... | 7     | intel_i... | D6AB5352B8 |
| 8086:9d35 | 17aa:5061 | Intel      | Sunrise Point-LP Integrat... | 7     | intel_i... | 16AC72B8EA |
| 8086:a2a4 |           | Intel      | 200 Series/Z370 Chipset F... | 7     |            | B59C9CF621 |
| 1022:15e4 | 1028:090c | AMD        | Raven/Raven2/Renoir Senso... | 6     |            | CDA45B1F3C |
| 8086:9d35 | 1028:06d6 | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | BF9CC483F0 |
| 8086:9d35 | 1028:0741 | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | 43F15F79DF |
| 8086:9d35 | 1028:07eb | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | 765C6838B2 |
| 8086:9d35 | 1028:0808 | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | 3C56EDEFE6 |
| 8086:9d35 | 1028:0823 | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | CCD587FDE5 |
| 8086:9d35 | 103c:828b | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | 5A85AB6B0F |
| 8086:9d35 | 103c:8313 | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | 5D0F309968 |
| 8086:9d35 | 103c:8483 | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | C48CB1FCCF |
| 8086:9d35 | 1043:1c90 | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | AED32F7A4D |
| 8086:9d35 | 17aa:3807 | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | E15A6F0B18 |
| 8086:9d35 | 17aa:3812 | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | 090E25B77C |
| 8086:9d35 | 17aa:504c | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | 4983586FE5 |
| 8086:22d8 | 103c:8042 | Intel      | Integrated Sensor Solution   | 5     | intel_i... | 0E503AAA16 |
| 8086:22d8 | 103c:82f4 | Intel      | Integrated Sensor Solution   | 5     | intel_i... | 1C188B150F |
| 8086:22d8 | 1043:1c60 | Intel      | Integrated Sensor Solution   | 5     | intel_i... | B2D1B00B0A |
| 8086:9d35 | 1028:06e6 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | D47AC58E2B |
| 8086:9d35 | 1028:0743 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 11E496D162 |
| 8086:9d35 | 1028:0809 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 2713F21DD7 |
| 8086:9d35 | 103c:81a9 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 0BB3F77C75 |
| 8086:9d35 | 103c:827f | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | BD5BDFD31F |
| 8086:9d35 | 103c:8487 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | CEBF94C181 |
| 8086:9d35 | 1179:0001 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | ED1722174A |
| 8086:9d35 | 152d:1237 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | B5A28C62AC |
| 8086:9d35 | 17aa:2244 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 55F51A3D6F |
| 12ab:0380 | 1cfa:0003 | YUAN Hi... | Game Capture 4K60 Pro        | 4     |            | A03E1FDB12 |
| 1b4b:9235 |           | Marvell... | 88SE9235 PCIe 2.0 x2 4-po... | 4     |            | 9A98A31681 |
| 8086:9d35 | 1025:111e | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 6C11DDAF17 |
| 8086:9d35 | 1028:07a5 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 5097E0F8C8 |
| 8086:9d35 | 1028:07aa | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 5492FDD780 |
| 8086:9d35 | 1028:07ec | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | FA3A8B9226 |
| 8086:9d35 | 103c:81a7 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | BC77E670A5 |
| 8086:9d35 | 103c:82c1 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | CF06BA276E |
| 8086:9d35 | 103c:83c4 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 3F62C672FB |
| 8086:9d35 | 103c:84d8 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 03FE12C3CC |
| 8086:9d35 | 17aa:2241 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 1C271464F4 |
| 8086:a135 | 15d9:089a | Intel      | 100 Series/C230 Series Ch... | 4     | intel_i... | 89CC93BB0F |
| 1022:15e6 | 103c:87ce | AMD        | Raven/Raven2/Renoir Non-S... | 3     | i2c_amd... | 28930B356E |
| 1022:15e6 | 103c:87d2 | AMD        | Raven/Raven2/Renoir Non-S... | 3     | i2c_amd... | A671B3AAE7 |
| 104c:9065 |           | Texas I... | TMS320DM642                  | 3     |            | 1AA3233F77 |
| 1b4b:1475 |           | Marvell... |                              | 3     |            | 9A98A31681 |
| 8086:1533 |           | Intel      | I210 Gigabit Network Conn... | 3     |            | 9A98A31681 |
| 8086:6f04 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     |            | 9A98A31681 |
| 8086:6f06 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     |            | 9A98A31681 |
| 8086:6f08 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     |            | 9A98A31681 |
| 8086:6f0a |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     |            | 9A98A31681 |
| 8086:8c54 |           | Intel      | C224 Series Chipset Famil... | 3     |            | 9A98A31681 |
| 8086:9d35 | 1028:0744 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 2CF1F86B67 |

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
| 9710:9865 | a000:2000 | MosChip... | PCI 9865 Multi-I/O Contro... | 27    | parport_pc | 715B40D8B6 |
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
| 8086:2f30 | 8086:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 398   | hswep_u... | 9D2A807F08 |
| 8086:2f34 | 8086:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 398   | hswep_u... | 9D2A807F08 |
| 8086:2f7d | 8086:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 398   |            | 9D2A807F08 |
| 8086:2f36 | 8086:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 363   | hswep_u... | 9D2A807F08 |
| 8086:2f37 | 8086:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 363   | hswep_u... | 9D2A807F08 |
| 8086:204c | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 217   | skx_uncore | EACC1E3F66 |
| 8086:204d | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 217   | skx_uncore | EACC1E3F66 |
| 8086:2015 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 213   |            | EACC1E3F66 |
| 8086:3c44 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to Q... | 178   | snbep_u... | 60F5B34BDD |
| 8086:3ce6 | 8086:0000 | Intel      | Xeon E5/Core i7 QuickPath... | 178   |            | 60F5B34BDD |
| 8086:3c43 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to P... | 172   | snbep_u... | 60F5B34BDD |
| 8086:0e36 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 133   | ivbep_u... | 97F8374A85 |
| 8086:6f30 | 8086:6f30 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 127   | bdx_uncore | 6EBA24CF71 |
| 8086:6f34 | 8086:6f34 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 127   | bdx_uncore | 6EBA24CF71 |
| 8086:6f7d | 8086:6f7d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 127   |            | 6EBA24CF71 |
| 8086:6f36 | 8086:6f36 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 115   | bdx_uncore | 6EBA24CF71 |
| 8086:6f37 | 8086:6f37 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 115   | bdx_uncore | 6EBA24CF71 |
| 8086:0e34 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 108   | ivbep_u... | 97F8374A85 |
| 8086:2058 | 8086:0000 | Intel      | Sky Lake-E KTI 0             | 108   | skx_uncore | E757687F86 |
| 8086:2f38 | 8086:2f38 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 99    | hswep_u... | F41F68A362 |
| 8086:3c43 | 1043:84ef | Intel      | Xeon E5/Core i7 Ring to P... | 90    | snbep_u... | EAF4F27F7A |
| 8086:3c44 | 1043:84ef | Intel      | Xeon E5/Core i7 Ring to Q... | 90    | snbep_u... | EAF4F27F7A |
| 8086:3c46 | 1043:84ef | Intel      | Xeon E5/Core i7 Processor... | 90    | snbep_u... | EAF4F27F7A |
| 8086:3ce6 | 1043:84ef | Intel      | Xeon E5/Core i7 QuickPath... | 90    |            | EAF4F27F7A |
| 8086:3c46 |           | Intel      | Xeon E5/Core i7 Processor... | 89    | snbep_u... | 49C747EFAD |
| 8086:3c46 | 8086:0000 | Intel      | Xeon E5/Core i7 Processor... | 87    | snbep_u... | 60F5B34BDD |
| 8086:27a3 |           | Intel      | 945GM/GU Chipset Hardware... | 83    |            | 0346BC764A |
| 8086:2088 | 8086:0000 | Intel      | Sky Lake-E DDRIO Registers   | 69    | skx_uncore | 30591F341D |
| 8086:2f32 | 8086:2f32 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 65    | hswep_u... | C7B39E92CA |
| 8086:2f33 | 8086:2f33 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 61    | hswep_u... | C7B39E92CA |
| 8086:0e30 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 60    | ivbep_u... | C720033D3A |
| 8086:0e30 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 52    | ivbep_u... | 1BB97BC7DF |
| 8086:0e34 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 52    | ivbep_u... | 1BB97BC7DF |
| 8086:0e36 | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 52    | ivbep_u... | 1BB97BC7DF |
| 8086:0e30 |           | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 48    | ivbep_u... | 97F8374A85 |
| 8086:3424 |           | Intel      | 7500/5520/5500/X58 Perfor... | 41    |            | EA3E45A8A7 |
| 8086:2f36 | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 31    | hswep_u... | 90189BED4E |
| 8086:2f37 | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 31    | hswep_u... | 90189BED4E |
| 8086:6f32 | 8086:6f32 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 31    | bdx_uncore | EB31EDBD6C |
| 8086:6f33 | 8086:6f33 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 31    | bdx_uncore | EB31EDBD6C |
| 8086:2f30 | 1849:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 30    | hswep_u... | B502D23978 |
| 8086:2f34 | 1849:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 30    | hswep_u... | B502D23978 |
| 8086:2f36 | 1849:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 30    | hswep_u... | B502D23978 |
| 8086:2f37 | 1849:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 30    | hswep_u... | B502D23978 |
| 8086:2f7d | 1849:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 30    |            | B502D23978 |
| 8086:3c43 | 1028:0497 | Intel      | Xeon E5/Core i7 Ring to P... | 29    | snbep_u... | 09302F3BB8 |
| 8086:3c44 | 1028:0497 | Intel      | Xeon E5/Core i7 Ring to Q... | 29    | snbep_u... | 09302F3BB8 |
| 8086:3c46 | 1028:0497 | Intel      | Xeon E5/Core i7 Processor... | 29    | snbep_u... | 09302F3BB8 |
| 8086:3ce6 | 1028:0497 | Intel      | Xeon E5/Core i7 QuickPath... | 29    |            | 09302F3BB8 |
| 8086:2088 |           | Intel      | Sky Lake-E DDRIO Registers   | 27    | skx_uncore | 30591F341D |
| 8086:3c43 | 103c:18a8 | Intel      | Xeon E5/Core i7 Ring to P... | 27    | snbep_u... | 5BFD235851 |
| 8086:3c44 | 103c:18a8 | Intel      | Xeon E5/Core i7 Ring to Q... | 27    | snbep_u... | 5BFD235851 |
| 8086:3c46 | 103c:18a8 | Intel      | Xeon E5/Core i7 Processor... | 27    | snbep_u... | 5BFD235851 |
| 8086:3ce6 | 103c:18a8 | Intel      | Xeon E5/Core i7 QuickPath... | 27    |            | 5BFD235851 |
| 8086:6f38 | 8086:6f38 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 24    | bdx_uncore | 17B2218DAB |
| 8086:3c43 | 1458:3c43 | Intel      | Xeon E5/Core i7 Ring to P... | 23    | snbep_u... | 853E99EEE4 |
| 8086:3c44 | 1458:3c44 | Intel      | Xeon E5/Core i7 Ring to Q... | 23    | snbep_u... | 853E99EEE4 |
| 8086:3c46 | 1458:3c46 | Intel      | Xeon E5/Core i7 Processor... | 23    | snbep_u... | 853E99EEE4 |
| 8086:3ce6 | 1458:3ce6 | Intel      | Xeon E5/Core i7 QuickPath... | 23    |            | 853E99EEE4 |
| 8086:2058 |           | Intel      | Sky Lake-E KTI 0             | 22    | skx_uncore | AD903545CE |
| 8086:2015 | 1028:0738 | Intel      | Sky Lake-E Ubox Registers    | 18    |            | 13718F9C0B |
| 8086:204c | 1028:0738 | Intel      | Sky Lake-E M3KTI Registers   | 18    | skx_uncore | 13718F9C0B |
| 8086:204d | 1028:0738 | Intel      | Sky Lake-E M3KTI Registers   | 18    | skx_uncore | 13718F9C0B |
| 8086:6f30 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 17    | bdx_uncore | AAEEE85BE7 |
| 8086:6f34 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 17    | bdx_uncore | AAEEE85BE7 |
| 8086:6f36 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 17    | bdx_uncore | AAEEE85BE7 |
| 8086:6f37 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 17    | bdx_uncore | AAEEE85BE7 |
| 8086:6f7d | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 17    |            | AAEEE85BE7 |
| 8086:0e37 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 16    | ivbep_u... | 97F8374A85 |
| 8086:6f32 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | AAEEE85BE7 |
| 8086:6f33 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | AAEEE85BE7 |
| 8086:0e30 | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 15    | ivbep_u... | 14CD659D3D |
| 8086:0e34 | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 15    | ivbep_u... | 14CD659D3D |
| 8086:3c43 | 1849:3c43 | Intel      | Xeon E5/Core i7 Ring to P... | 14    | snbep_u... | 4AE2BC6AFD |
| 8086:3c44 | 1849:3c44 | Intel      | Xeon E5/Core i7 Ring to Q... | 14    | snbep_u... | 4AE2BC6AFD |
| 8086:3c46 | 1849:3c46 | Intel      | Xeon E5/Core i7 Processor... | 14    | snbep_u... | 4AE2BC6AFD |
| 8086:3ce6 | 1849:3ce6 | Intel      | Xeon E5/Core i7 QuickPath... | 14    |            | 4AE2BC6AFD |
| 8086:0e30 | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 12    | ivbep_u... | DD93F62FFC |
| 8086:0e34 | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 12    | ivbep_u... | DD93F62FFC |
| 8086:0e36 | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 12    | ivbep_u... | DD93F62FFC |
| 8086:3c41 | 8086:0000 | Intel      | Sandy Bridge QPI Port 0 P... | 12    | snbep_u... | 1A5CF39F4F |
| 8086:3c42 | 8086:0000 | Intel      | Sandy Bridge QPI Port 1 P... | 12    | snbep_u... | 1A5CF39F4F |
| 8086:6f30 | 1849:6f30 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 12    | bdx_uncore | 2BF61F2EC6 |
| 8086:6f34 | 1849:6f34 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 12    | bdx_uncore | 2BF61F2EC6 |
| 8086:6f36 | 1849:6f36 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 12    | bdx_uncore | 2BF61F2EC6 |
| 8086:6f37 | 1849:6f37 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 12    | bdx_uncore | 2BF61F2EC6 |
| 8086:6f7d | 1849:6f7d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 12    |            | 2BF61F2EC6 |
| 8086:0e30 | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    | ivbep_u... | 7B579629BB |
| 8086:0e30 | 1458:3c46 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    | ivbep_u... | 349F8DBE53 |
| 8086:0e34 | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    | ivbep_u... | 7B579629BB |
| 8086:0e34 | 1458:3c43 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    | ivbep_u... | 349F8DBE53 |
| 8086:0e36 | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    | ivbep_u... | 7B579629BB |
| 8086:0e36 | 1458:3c44 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    | ivbep_u... | 349F8DBE53 |
| 8086:3c43 | 8086:4953 | Intel      | Xeon E5/Core i7 Ring to P... | 10    | snbep_u... | 380F10F479 |
| 8086:3c44 | 8086:4953 | Intel      | Xeon E5/Core i7 Ring to Q... | 10    | snbep_u... | 380F10F479 |
| 8086:3c46 | 8086:4953 | Intel      | Xeon E5/Core i7 Processor... | 10    | snbep_u... | 380F10F479 |
| 8086:3ce6 | 8086:4953 | Intel      | Xeon E5/Core i7 QuickPath... | 10    |            | 380F10F479 |
| 8086:3c43 | 1043:84f0 | Intel      | Xeon E5/Core i7 Ring to P... | 8     | snbep_u... | 874EAAB0BB |
| 8086:3c44 | 1043:84f0 | Intel      | Xeon E5/Core i7 Ring to Q... | 8     | snbep_u... | 874EAAB0BB |
| 8086:3c46 | 1043:84f0 | Intel      | Xeon E5/Core i7 Processor... | 8     | snbep_u... | 874EAAB0BB |

### Pic (8259) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:342e |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 786   | i7core_... | 40C84C9637 |
| 8086:3422 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 784   |            | 40C84C9637 |
| 8086:3423 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 784   |            | 40C84C9637 |
| 8086:3438 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 451   | i5500_temp | 6C7ECC284B |
| 8086:3425 |           | Intel      | 7500/5520/5500/X58 Physic... | 294   |            | 40C84C9637 |
| 8086:3426 |           | Intel      | 7500/5520/5500/X58 Routin... | 294   |            | 40C84C9637 |
| 8086:3427 |           | Intel      | 7500/5520/5500 Physical a... | 262   |            | 40C84C9637 |
| 8086:3428 |           | Intel      | 7500/5520/5500 Routing & ... | 262   |            | 40C84C9637 |
| 8086:3422 | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 66    |            | 59C0064E39 |
| 8086:3423 | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 66    |            | 59C0064E39 |
| 8086:342e | 0028:0093 | Intel      | 7500/5520/5500/X58 I/O Hu... | 66    | i7core_... | 59C0064E39 |
| 8086:3422 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 57    |            | 9753F223E2 |
| 8086:3423 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 57    |            | 9753F223E2 |
| 8086:342e | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 57    | i7core_... | 9753F223E2 |
| 8086:3422 | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 31    |            | FF796824D2 |
| 8086:3423 | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 31    |            | FF796824D2 |
| 8086:342e | 0028:006e | Intel      | 7500/5520/5500/X58 I/O Hu... | 31    | i7core_... | FF796824D2 |
| 8086:3422 | 0086:0022 | Intel      | 7500/5520/5500/X58 I/O Hu... | 24    |            | 849CA2DA3D |
| 8086:3423 | 0086:0023 | Intel      | 7500/5520/5500/X58 I/O Hu... | 24    |            | 849CA2DA3D |
| 8086:342e | 0086:002e | Intel      | 7500/5520/5500/X58 I/O Hu... | 24    | i7core_... | 849CA2DA3D |
| 8086:3422 | 0028:006d | Intel      | 7500/5520/5500/X58 I/O Hu... | 22    |            | 2F188B606A |
| 8086:3423 | 0028:006d | Intel      | 7500/5520/5500/X58 I/O Hu... | 22    |            | 2F188B606A |
| 8086:342e | 0028:006d | Intel      | 7500/5520/5500/X58 I/O Hu... | 22    | i7core_... | 2F188B606A |
| 8086:3422 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 8     |            | 1B777C6F08 |
| 8086:3423 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 8     |            | 1B777C6F08 |
| 8086:3425 | 0043:0063 | Intel      | 7500/5520/5500/X58 Physic... | 8     |            | 1B777C6F08 |
| 8086:3426 | 0043:0063 | Intel      | 7500/5520/5500/X58 Routin... | 8     |            | 1B777C6F08 |
| 8086:3427 | 0043:0063 | Intel      | 7500/5520/5500 Physical a... | 8     |            | 1B777C6F08 |
| 8086:3428 | 0043:0063 | Intel      | 7500/5520/5500 Routing & ... | 8     |            | 1B777C6F08 |
| 8086:342e | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 8     | i7core_... | 1B777C6F08 |
| 8086:3438 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 8     | i5500_temp | 1B777C6F08 |
| 8086:3422 | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     |            | 451F363726 |
| 8086:3423 | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     |            | 451F363726 |
| 8086:3425 | 0086:00dc | Intel      | 7500/5520/5500/X58 Physic... | 7     |            | 451F363726 |
| 8086:3426 | 0086:00dc | Intel      | 7500/5520/5500/X58 Routin... | 7     |            | 451F363726 |
| 8086:3427 | 0086:00dc | Intel      | 7500/5520/5500 Physical a... | 7     |            | 451F363726 |
| 8086:3428 | 0086:00dc | Intel      | 7500/5520/5500 Routing & ... | 7     |            | 451F363726 |
| 8086:342e | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     | i7core_... | 451F363726 |
| 8086:3438 | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     | i5500_temp | 451F363726 |
| 8086:3422 | 0034:0027 | Intel      | 7500/5520/5500/X58 I/O Hu... | 6     |            | 43C0756BA6 |
| 8086:3423 | 0034:0027 | Intel      | 7500/5520/5500/X58 I/O Hu... | 6     |            | 43C0756BA6 |
| 8086:3425 | 0034:0027 | Intel      | 7500/5520/5500/X58 Physic... | 6     |            | 43C0756BA6 |
| 8086:3426 | 0034:0027 | Intel      | 7500/5520/5500/X58 Routin... | 6     |            | 43C0756BA6 |
| 8086:3427 | 0034:0027 | Intel      | 7500/5520/5500 Physical a... | 6     |            | 43C0756BA6 |
| 8086:3428 | 0034:0027 | Intel      | 7500/5520/5500 Routing & ... | 6     |            | 43C0756BA6 |
| 8086:342e | 0034:0027 | Intel      | 7500/5520/5500/X58 I/O Hu... | 6     | i7core_... | 43C0756BA6 |
| 8086:3438 | 0034:0027 | Intel      | 7500/5520/5500/X58 I/O Hu... | 6     | i5500_temp | 43C0756BA6 |
| 8086:3422 | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 5     |            | F9F8DD79F5 |
| 8086:3422 | 0086:00e2 | Intel      | 7500/5520/5500/X58 I/O Hu... | 5     |            | FDCE629C37 |
| 8086:3423 | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 5     |            | F9F8DD79F5 |
| 8086:3423 | 0086:00e2 | Intel      | 7500/5520/5500/X58 I/O Hu... | 5     |            | FDCE629C37 |
| 8086:3425 | 0086:00da | Intel      | 7500/5520/5500/X58 Physic... | 5     |            | F9F8DD79F5 |
| 8086:3425 | 0086:00e2 | Intel      | 7500/5520/5500/X58 Physic... | 5     |            | FDCE629C37 |
| 8086:3426 | 0086:00da | Intel      | 7500/5520/5500/X58 Routin... | 5     |            | F9F8DD79F5 |
| 8086:3426 | 0086:00e2 | Intel      | 7500/5520/5500/X58 Routin... | 5     |            | FDCE629C37 |
| 8086:3427 | 0086:00da | Intel      | 7500/5520/5500 Physical a... | 5     |            | F9F8DD79F5 |
| 8086:3427 | 0086:00e2 | Intel      | 7500/5520/5500 Physical a... | 5     |            | FDCE629C37 |
| 8086:3428 | 0086:00da | Intel      | 7500/5520/5500 Routing & ... | 5     |            | F9F8DD79F5 |
| 8086:3428 | 0086:00e2 | Intel      | 7500/5520/5500 Routing & ... | 5     |            | FDCE629C37 |
| 8086:342e | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 5     | i7core_... | F9F8DD79F5 |
| 8086:342e | 0086:00e2 | Intel      | 7500/5520/5500/X58 I/O Hu... | 5     | i7core_... | FDCE629C37 |
| 8086:3438 | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 5     | i5500_temp | F9F8DD79F5 |
| 8086:3438 | 0086:00e2 | Intel      | 7500/5520/5500/X58 I/O Hu... | 5     | i5500_temp | FDCE629C37 |
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
| 8086:2f2c | 8086:0000 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 273   |            | 9D2A807F08 |
| 8086:342f |           | Intel      | 7500/5520/5500/X58 Truste... | 257   |            | 40C84C9637 |
| 8086:342d |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 204   |            | 40C84C9637 |
| 8086:2026 | 8086:2026 | Intel      | Sky Lake-E IOAPIC            | 199   |            | EACC1E3F66 |
| 8086:2036 | 8086:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 199   |            | EACC1E3F66 |
| 8086:3c2c | 8086:3c2c | Intel      | Xeon E5/Core i7 I/O APIC     | 167   |            | 60F5B34BDD |
| 8086:0e2c | 8086:0e2c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 102   |            | 6908407322 |
| 8086:3c2c | 1043:84ef | Intel      | Xeon E5/Core i7 I/O APIC     | 90    |            | EAF4F27F7A |
| 1106:5364 |           | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 89    |            | C61D7B8758 |
| 8086:6f2c | 8086:0000 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 79    |            | 17B2218DAB |
| 1106:5327 |           | VIA Tec... | P4M890 I/O APIC Interrupt... | 52    |            | C499580572 |
| 8086:0e2c | 1043:84ef | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 52    |            | 1BB97BC7DF |
| 8086:3c2c | 103c:18a8 | Intel      | Xeon E5/Core i7 I/O APIC     | 31    |            | 5BFD235851 |
| 8086:2f2c | 1849:2f2c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 30    |            | B502D23978 |
| 8086:3c2c | 1028:0497 | Intel      | Xeon E5/Core i7 I/O APIC     | 29    |            | 09302F3BB8 |
| 8086:2f2c | 1462:7885 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 28    |            | 90189BED4E |
| 8086:2f2c | 1028:0617 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 25    |            | CC3925F2E7 |
| 1106:5336 |           | VIA Tec... | K8M890CE I/O APIC Interru... | 24    |            | 4BE11BE3F6 |
| 8086:3c2c | 1458:5000 | Intel      | Xeon E5/Core i7 I/O APIC     | 23    |            | 853E99EEE4 |
| 1106:5308 | 1849:5308 | VIA Tec... | PT894 I/O APIC Interrupt ... | 21    |            | 6DF28D7EA1 |
| 8086:3504 |           | Intel      | 6311ESB/6321ESB I/OxAPIC ... | 21    |            | 1E34F92251 |
| 8086:2026 | 1028:0738 | Intel      | Sky Lake-E IOAPIC            | 18    |            | 13718F9C0B |
| 8086:2036 | 1028:0738 | Intel      | Sky Lake-E IOxAPIC Config... | 18    |            | 13718F9C0B |
| 8086:2026 | 8086:0000 | Intel      | Sky Lake-E IOAPIC            | 17    |            | 23D528F392 |
| 8086:2036 | 8086:0000 | Intel      | Sky Lake-E IOxAPIC Config... | 17    |            | 23D528F392 |
| 8086:6f2c | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 17    |            | AAEEE85BE7 |
| 8086:0e2c | 1028:05d2 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 15    |            | 14CD659D3D |
| 1106:5364 | 1106:5364 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 14    |            | B1490652D3 |
| 8086:3c2c | 1849:3c2c | Intel      | Xeon E5/Core i7 I/O APIC     | 14    |            | 4AE2BC6AFD |
| 8086:0e2c | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 13    |            | 97F8374A85 |
| 8086:0e2c | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 12    |            | DD93F62FFC |
| 8086:2f2c | 1028:0618 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 12    |            | 0E22588D46 |
| 8086:6f2c | 1849:6f2c | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 12    |            | 2BF61F2EC6 |
| 8086:0e2c | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    |            | 7B579629BB |
| 8086:0e2c | 1458:5000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    |            | 349F8DBE53 |
| 8086:3c2c | 8086:4953 | Intel      | Xeon E5/Core i7 I/O APIC     | 11    |            | 380F10F479 |
| 8086:6f2c | 1028:0617 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 10    |            | 6EBA24CF71 |
| 1106:5364 | 103c:3030 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 9     |            | E81CAC058D |
| 1106:5364 | 1734:10f7 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 8     |            | A61C777014 |
| 8086:2f2c | 15d9:0857 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 8     |            | 6A333A499D |
| 8086:3c2c | 1043:84f0 | Intel      | Xeon E5/Core i7 I/O APIC     | 8     |            | 874EAAB0BB |
| 8086:0e2c | 1028:05d4 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 7     |            | 3CF0EB9253 |
| 8086:2026 | 1590:18a9 | Intel      | Sky Lake-E IOAPIC            | 7     |            | 7AB4F05613 |
| 8086:2026 | 17aa:7808 | Intel      | Sky Lake-E IOAPIC            | 7     |            | CEE7ED2CE9 |
| 8086:2036 | 1590:18a9 | Intel      | Sky Lake-E IOxAPIC Config... | 7     |            | 7AB4F05613 |
| 8086:2036 | 17aa:7808 | Intel      | Sky Lake-E IOxAPIC Config... | 7     |            | CEE7ED2CE9 |
| 8086:2f2c | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 7     |            | CFFFE6AA63 |
| 8086:342d | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     |            | 451F363726 |
| 8086:342f | 0086:00dc | Intel      | 7500/5520/5500/X58 Truste... | 7     |            | 451F363726 |
| 8086:3c2c | 1028:0495 | Intel      | Xeon E5/Core i7 I/O APIC     | 7     |            | 0C3A459A0E |
| 8086:3c2c | 1734:11b5 | Intel      | Xeon E5/Core i7 I/O APIC     | 7     |            | E689B2DE7A |
| 8086:0e2c | 1043:84f0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 6     |            | A4C832AB44 |
| 8086:2026 | 1734:122f | Intel      | Sky Lake-E IOAPIC            | 6     |            | 33A89C4C5A |
| 8086:2036 | 1734:122f | Intel      | Sky Lake-E IOxAPIC Config... | 6     |            | 33A89C4C5A |
| 8086:342f | 0034:0027 | Intel      | 7500/5520/5500/X58 Truste... | 6     |            | 43C0756BA6 |
| 8086:3c2c | 1028:0496 | Intel      | Xeon E5/Core i7 I/O APIC     | 6     |            | 80E68A5C66 |
| 1106:5351 |           | VIA Tec... | VT3351 I/O APIC Interrupt... | 5     |            | 9B7D8BD5FF |
| 1106:5364 | 1849:5364 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 5     |            | 6410827A2F |
| 8086:0326 |           | Intel      | 6700/6702PXH I/OxAPIC Int... | 5     |            | 0511AEEAC6 |
| 8086:0e2c | 17aa:1026 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 5     |            | 99B572DE7F |
| 8086:0e2c | 1849:0e2c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 5     |            | D3383D57EF |
| 8086:2026 | 17aa:1036 | Intel      | Sky Lake-E IOAPIC            | 5     |            | 48145BEF99 |
| 8086:2026 | 1849:2026 | Intel      | Sky Lake-E IOAPIC            | 5     |            | 2244EB7809 |
| 8086:2036 | 17aa:1036 | Intel      | Sky Lake-E IOxAPIC Config... | 5     |            | 48145BEF99 |
| 8086:2036 | 1849:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 5     |            | 2244EB7809 |
| 8086:2f2c | 1028:0619 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 5     |            | D9E5820DB2 |
| 8086:342d | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 5     |            | F9F8DD79F5 |
| 8086:342d | 0086:00e2 | Intel      | 7500/5520/5500/X58 I/O Hu... | 5     |            | FDCE629C37 |
| 8086:342f | 0086:00da | Intel      | 7500/5520/5500/X58 Truste... | 5     |            | F9F8DD79F5 |
| 8086:342f | 0086:00e2 | Intel      | 7500/5520/5500/X58 Truste... | 5     |            | FDCE629C37 |
| 8086:6f2c | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 5     |            | 23F12250E5 |
| 8086:6f2c | 1462:7885 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 5     |            | 53F89BE1B8 |
| 1106:5238 |           | VIA Tec... | K8T890 I/O APIC Interrupt... | 4     |            | D9174E33E4 |
| 1106:5336 | 1043:8297 | VIA Tec... | K8M890CE I/O APIC Interru... | 4     |            | CED2DCBAC9 |
| 1106:5364 | 1019:2125 | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 4     |            | 814C427D36 |
| 8086:0326 | 103c:12f1 | Intel      | 6700/6702PXH I/OxAPIC Int... | 4     |            | AD9D1EDCBB |
| 8086:0327 | 103c:12f1 | Intel      | 6700PXH I/OxAPIC Interrup... | 4     |            | AD9D1EDCBB |
| 8086:0e2c | 1734:11b5 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     |            | 8E8715B0CD |
| 8086:0e2c | 8086:35a0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     |            | FE1E6CFF79 |
| 8086:2026 | 8086:35ce | Intel      | Sky Lake-E IOAPIC            | 4     |            | 36C4ACAC2D |
| 8086:2f2c | 1028:064c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | 82F399DFE3 |
| 8086:2f2c | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | FD108DE325 |
| 8086:3c2c | 1028:05d4 | Intel      | Xeon E5/Core i7 I/O APIC     | 4     |            | 12E7B4FF29 |
| 8086:3c2c | 17aa:1026 | Intel      | Xeon E5/Core i7 I/O APIC     | 4     |            | 7EB1F254C9 |
| 8086:3c2c | 17aa:1027 | Intel      | Xeon E5/Core i7 I/O APIC     | 4     |            | E3C6A7B793 |
| 8086:6f2c | 1028:0619 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     |            | 36E6C22CC6 |
| 1106:5327 | 1631:e035 | VIA Tec... | P4M890 I/O APIC Interrupt... | 3     |            | 089D020111 |
| 1106:5353 |           | VIA Tec... | VX800/VX820 APIC and Cent... | 3     |            | B5933FDE35 |
| 1106:5353 | 17aa:388a | VIA Tec... | VX800/VX820 APIC and Cent... | 3     |            | 4762847735 |
| 8086:0327 |           | Intel      | 6700PXH I/OxAPIC Interrup... | 3     |            | 0511AEEAC6 |
| 8086:0e2c | 1028:05d3 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     |            | 66630328B1 |
| 8086:0e2c | 15d9:062a | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     |            | 47401D66CE |
| 8086:0e2c | 15d9:062b | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     |            | FD24B5D375 |
| 8086:0e2c | 17aa:1028 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     |            | CD3EBA7A96 |
| 8086:2026 | 1028:0836 | Intel      | Sky Lake-E IOAPIC            | 3     |            | BF5947B943 |
| 8086:2026 | 1028:08b1 | Intel      | Sky Lake-E IOAPIC            | 3     |            | 42BF6B208E |
| 8086:2026 | 17aa:1038 | Intel      | Sky Lake-E IOAPIC            | 3     |            | 5658A2FB98 |
| 8086:2036 | 1028:08b1 | Intel      | Sky Lake-E IOxAPIC Config... | 3     |            | 42BF6B208E |
| 8086:2036 | 1028:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 3     |            | BF5947B943 |
| 8086:2036 | 17aa:1038 | Intel      | Sky Lake-E IOxAPIC Config... | 3     |            | 5658A2FB98 |

### Pic (io-apic) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:7451 | 1022:7450 | AMD        | AMD-8131 PCI-X IOAPIC        | 4     |            | A94946D561 |
| 1022:7451 | 10f1:2895 | AMD        | AMD-8131 PCI-X IOAPIC        | 1     |            | 768571B831 |
| 1022:7459 | 1022:7459 | AMD        | AMD-8132 PCI-X IOAPIC        | 1     |            | 68059DB0EE |

### Power pc (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1957:c006 | 1a56:1201 | Freesca... | MPC8308                      | 8     |            | 40C84C9637 |
| 1957:00b6 | 1a56:1103 | Freesca... | MPC8314E                     | 2     |            | B07AC7C26E |
| 1957:0085 | 110a:4046 | Freesca... | MPC8347 PBGA                 | 1     |            | 60A7685D8D |
| 1957:00b6 | 1a56:1101 | Freesca... | MPC8314E                     | 1     |            | FC18CDC2FD |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:16bc | 14e4:0000 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 530   | sdhci_pci  | 6E17FB6EA4 |
| 14e4:16bc | 1025:0647 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 410   | sdhci_pci  | 82E60126C9 |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 322   | sdhci_pci  | 6121781D85 |
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 266   | sdhci_pci  | 4DBC03E904 |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 252   | sdhci_pci  | 6121781D85 |
| 8086:31d0 | 8086:7270 | Intel      | SD Host Controller           | 240   | sdhci_pci  | 4DBC03E904 |
| 197b:2381 | 1043:1a07 | JMicron... | Standard SD Host Controller  | 235   | sdhci_pci  | D5A8ADB8C9 |
| 8086:9d2d | 8086:9d2d | Intel      | Sunrise Point-LP Secure D... | 226   | sdhci_pci  | F3511CB0AA |
| 1180:0822 | 17aa:20c8 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 224   | sdhci_pci  | 9A7BE426F5 |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 224   | sdhci_pci  | 6121781D85 |
| 14e4:16bc | 1025:0504 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 213   | sdhci_pci  | F86CA58100 |
| 1217:8221 | 1028:0493 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 154   | sdhci_pci  | 4C3C43DAAA |
| 1180:e822 | 1028:040a | Ricoh      | MMC/SD Host Controller       | 145   | sdhci_pci  | BA51FC9216 |
| 14e4:16bc | 1025:0775 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 145   | sdhci_pci  | 921FC6B490 |
| 1022:7813 | 17aa:3801 | AMD        | FCH SD Flash Controller      | 143   | sdhci_pci  | 0CDC6E9D84 |
| 1217:8221 | 1028:0534 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 141   | sdhci_pci  | FA4D12994D |
| 1022:7806 | 1022:7806 | AMD        | FCH SD Flash Controller      | 138   | sdhci_pci  | 3378B3C989 |
| 1180:e822 | 104d:9071 | Ricoh      | MMC/SD Host Controller       | 138   | sdhci_pci  | A18FB33A6F |
| 104c:803c | 1025:011f | Texas I... | PCIxx12 SDA Standard Comp... | 135   | sdhci_pci  | 8592F1650F |
| 1180:0822 | 1028:0233 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 124   | sdhci_pci  | 6B7EF9CAD5 |
| 197b:2391 | 103c:161c | JMicron... | Standard SD Host Controller  | 116   | sdhci_pci  | B6AC4539D1 |
| 197b:2391 | 103c:179b | JMicron... | Standard SD Host Controller  | 106   | sdhci_pci  | 1B2FBCDFA0 |
| 197b:2391 | 103c:17f6 | JMicron... | Standard SD Host Controller  | 97    | sdhci_pci  | E12D7E47E6 |
| 10ec:5209 | 10ec:5209 | Realtek... | RTS5209 PCI Express Card ... | 94    | rtsx_pci   | 314ABB1FF1 |
| 1217:8621 | 17aa:5068 | O2 Micro   | SD/MMC Card Reader Contro... | 86    | sdhci_pci  | 2A70ED5588 |
| 1180:0822 | 1028:022f | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 83    | sdhci_pci  | ED2467DC52 |
| 1217:8520 | 1028:05cb | O2 Micro   | SD/MMC Card Reader Contro... | 81    | sdhci_pci  | 98C988645F |
| 1217:8621 | 1217:0002 | O2 Micro   | SD/MMC Card Reader Contro... | 81    | sdhci_pci  | FD3AEFD54A |
| 1217:8520 | 1028:062e | O2 Micro   | SD/MMC Card Reader Contro... | 75    | sdhci_pci  | 91837758AC |
| 197b:2391 | 103c:167c | JMicron... | Standard SD Host Controller  | 75    | sdhci_pci  | 4808FF3A68 |
| 8086:9df5 | 8086:7270 | Intel      | BayHubTech Integrated SD ... | 74    | sdhci_pci  | 0E29003348 |
| 1180:0822 | 103c:30cc | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 73    | sdhci_pci  | DD3C7EF3E7 |
| 8086:9d2b | 8086:7270 | Intel      | Skylake-U/Y SCC: eMMC        | 72    | sdhci_pci  | DD20DE340C |
| 1217:8520 | 1028:05bd | O2 Micro   | SD/MMC Card Reader Contro... | 69    | sdhci_pci  | 00E8B6E3FD |
| 1217:8520 | 1028:05be | O2 Micro   | SD/MMC Card Reader Contro... | 68    | sdhci_pci  | 298AB39418 |
| 17a0:9755 | 8086:2081 | Genesys... | GL9755 SD Host Controller    | 68    | sdhci_pci  | 37E756FA81 |
| 1180:0822 | 103c:172a | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 66    | sdhci_pci  | F527983CC9 |
| 1217:8221 | 1028:0535 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 66    | sdhci_pci  | FD1375D5F1 |
| 1217:8321 | 1028:0494 | O2 Micro   | OZ600RJ0/OZ900RJ0/OZ600RJ... | 66    | sdhci_pci  | B84EF4472B |
| 1180:0843 | 1028:0233 | Ricoh      | R5C843 MMC Host Controller   | 64    | sdhci_pci  | 843B7BD830 |
| 17a0:9750 | 17aa:2279 | Genesys... | GL9750 SD Host Controller    | 61    | sdhci_pci  | A01E524A66 |
| 1217:7120 | 1179:ff50 | O2 Micro   | Integrated MMC/SD Controller | 60    | sdhci_pci  | ABCF2EEE75 |
| 14e4:16bc | 14e4:96bc | Broadco... | BCM57765/57785 SDXC/MMC C... | 58    | sdhci_pci  | D5BCF80B27 |
| 8086:9d2d | 8086:7270 | Intel      | Sunrise Point-LP Secure D... | 58    | sdhci_pci  | DD20DE340C |
| 1217:8520 | 1028:05ca | O2 Micro   | SD/MMC Card Reader Contro... | 57    | sdhci_pci  | DBF0FD04C3 |
| 1524:0550 | 1025:0090 | ENE Tec... | ENE PCI Secure Digital Ca... | 57    | sdhci_pci  | B09A0D7779 |
| 1217:8621 | 17aa:381f | O2 Micro   | SD/MMC Card Reader Contro... | 56    | sdhci_pci  | A7045DEFDF |
| 1180:e822 | 1028:040b | Ricoh      | MMC/SD Host Controller       | 55    | sdhci_pci  | 2AB208B5CD |
| 1217:8520 | 17aa:2211 | O2 Micro   | SD/MMC Card Reader Contro... | 55    | sdhci_pci  | 8DD2C7497E |
| 1022:7813 | 1025:104b | AMD        | FCH SD Flash Controller      | 54    | sdhci_pci  | C6582BBA7D |
| 104c:803c | 1179:ff00 | Texas I... | PCIxx12 SDA Standard Comp... | 54    | sdhci_pci  | 1BF61C0698 |
| 8086:2294 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 53    | sdhci_pci  | E9536CCBFB |
| 10ec:5209 | 103c:3388 | Realtek... | RTS5209 PCI Express Card ... | 51    | rtsx_pci   | 0392F507D0 |
| 197b:2391 | 103c:162b | JMicron... | Standard SD Host Controller  | 50    | sdhci_pci  | 28D13C49B3 |
| 1180:0822 | 103c:7008 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 49    | sdhci_pci  | F31AC36B11 |
| 1217:8621 | 17aa:3824 | O2 Micro   | SD/MMC Card Reader Contro... | 49    | sdhci_pci  | 3F7C00C1EF |
| 197b:2381 | 103c:3628 | JMicron... | Standard SD Host Controller  | 49    | sdhci_pci  | 2992DD1DF0 |
| 197b:2381 | 1297:2027 | JMicron... | Standard SD Host Controller  | 49    | sdhci_pci  | 9F3A43BC94 |
| 1180:0822 | 1028:024f | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 48    | sdhci_pci  | E475348B1E |
| 1969:3010 | 1025:076b | Qualcom... | Secure Digital Card Reader   | 48    | sdhci_pci  | DC7A02C862 |
| 197b:2391 | 103c:18df | JMicron... | Standard SD Host Controller  | 48    | sdhci_pci  | F66BA65DC8 |
| 8086:9d2b | 8086:9d2b | Intel      | Skylake-U/Y SCC: eMMC        | 48    | sdhci_pci  | 72DED95FAB |
| 1022:7906 | 1043:1291 | AMD        | FCH SD Flash Controller      | 47    | sdhci_pci  | 34F2870A95 |
| 1180:0822 | 1025:011e | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 47    | sdhci_pci  | 6472272BF7 |
| 197b:2381 | 17aa:212d | JMicron... | Standard SD Host Controller  | 47    | sdhci_pci  | 0BC832BD49 |
| 1217:8621 | 17aa:5072 | O2 Micro   | SD/MMC Card Reader Contro... | 46    | sdhci_pci  | 3678E02E46 |
| 1180:0822 | 10f7:8338 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 45    | sdhci_pci  | 3678F83BBA |
| 1217:8221 | 1028:0492 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 45    | sdhci_pci  | E8538CE77D |
| 197b:2391 | 103c:1618 | JMicron... | Standard SD Host Controller  | 45    | sdhci_pci  | 48828AD0D3 |
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
| 14e4:16bc | 1025:0742 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 40    | sdhci_pci  | 8068BE142E |
| 1180:0822 | 1028:01f5 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 39    | sdhci_pci  | 58A2EF72C9 |
| 1217:8320 | 1028:04a3 | O2 Micro   | OZ600RJ1/OZ900RJ1 SD/MMC ... | 39    | sdhci_pci  | F442DF91A1 |
| 104c:803c | 1179:ff10 | Texas I... | PCIxx12 SDA Standard Comp... | 38    | sdhci_pci  | 68AC15EEDA |
| 1180:e822 | 1028:0410 | Ricoh      | MMC/SD Host Controller       | 38    | sdhci_pci  | 5E7233F129 |
| 1217:8321 | 1028:049b | O2 Micro   | OZ600RJ0/OZ900RJ0/OZ600RJ... | 38    | sdhci_pci  | A1027F938F |
| 1217:8520 | 1028:05cc | O2 Micro   | SD/MMC Card Reader Contro... | 38    | sdhci_pci  | 87034ED159 |
| 197b:2391 | 103c:17ab | JMicron... | Standard SD Host Controller  | 38    | sdhci_pci  | 0BFBD31BA0 |
| 197b:2391 | 17aa:3976 | JMicron... | Standard SD Host Controller  | 38    | sdhci_pci  | 409FB80AE5 |
| 8086:2296 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 38    | sdhci_pci  | E9536CCBFB |
| 8086:9df5 | 103c:8538 | Intel      | BayHubTech Integrated SD ... | 38    | sdhci_pci  | E03D6BA4C2 |
| 1022:7813 | 103c:8137 | AMD        | FCH SD Flash Controller      | 37    | sdhci_pci  | FA33BFD7BC |
| 1180:0822 | 1028:01bd | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 37    | sdhci_pci  | FA750DAFE2 |
| 1180:0822 | 1028:024d | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 37    | sdhci_pci  | 127B65224F |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a324 | 8086:7270 | Intel      | Cannon Lake PCH SPI Contr... | 520   | intel_s... | 90E49546C2 |
| 8086:a324 | 1043:8694 | Intel      | Cannon Lake PCH SPI Contr... | 375   | intel_s... | 22A32FC3F2 |
| 8086:9da4 | 8086:7270 | Intel      | Cannon Point-LP SPI Contr... | 317   |            | 67F0B45A7A |
| 8086:9ce6 | 8086:9ce6 | Intel      | Wildcat Point-LP Serial I... | 265   | spi_pxa... | 5BE083EDAB |
| 8086:a324 | 1025:1331 | Intel      | Cannon Lake PCH SPI Contr... | 157   | intel_s... | BC9DC107D1 |
| 8086:a368 | 1025:1331 | Intel      | Cannon Lake PCH Serial IO... | 157   | intel_lpss | BC9DC107D1 |
| 8086:a369 | 1025:1331 | Intel      | Cannon Lake PCH Serial IO... | 157   | intel_lpss | BC9DC107D1 |
| 8086:a324 | 1028:0905 | Intel      | Cannon Lake PCH SPI Contr... | 142   | intel_s... | 58E43F0514 |
| 8086:a368 | 1028:0905 | Intel      | Cannon Lake PCH Serial IO... | 142   | intel_l... | 58E43F0514 |
| 8086:a369 | 1028:0905 | Intel      | Cannon Lake PCH Serial IO... | 142   | intel_l... | 58E43F0514 |
| 8086:02a4 | 17aa:5079 | Intel      | Comet Lake SPI (flash) Co... | 138   | intel_s... | A35AAAEB6D |
| 8086:9da4 | 8086:2074 | Intel      | Cannon Point-LP SPI Contr... | 130   |            | 7EEEAAA250 |
| 8086:9da4 | 17aa:2279 | Intel      | Cannon Point-LP SPI Contr... | 127   |            | A01E524A66 |
| 8086:9de8 | 17aa:2279 | Intel      | Cannon Point-LP Serial IO... | 126   | intel_l... | A01E524A66 |
| 8086:a324 | 1849:a324 | Intel      | Cannon Lake PCH SPI Contr... | 124   | intel_s... | 2FF008A28D |
| 8086:a324 | 1028:087c | Intel      | Cannon Lake PCH SPI Contr... | 114   | intel_spi  | 0FA8C3ED0C |
| 8086:a368 | 1028:087c | Intel      | Cannon Lake PCH Serial IO... | 114   | intel_l... | 0FA8C3ED0C |
| 8086:a369 | 1028:087c | Intel      | Cannon Lake PCH Serial IO... | 114   | intel_l... | 0FA8C3ED0C |
| 8086:9da4 | 103c:8549 | Intel      | Cannon Point-LP SPI Contr... | 111   |            | A814284F0B |
| 8086:9de8 | 103c:8549 | Intel      | Cannon Point-LP Serial IO... | 111   | intel_l... | A814284F0B |
| 8086:9de9 | 103c:8549 | Intel      | Cannon Point-LP Serial IO... | 111   | intel_l... | A814284F0B |
| 8086:02a4 | 8086:7270 | Intel      | Comet Lake SPI (flash) Co... | 108   | intel_s... | 1155D58828 |
| 8086:9da4 | 17aa:2292 | Intel      | Cannon Point-LP SPI Contr... | 103   |            | 26C62915E0 |
| 8086:9de8 | 17aa:2292 | Intel      | Cannon Point-LP Serial IO... | 103   | intel_l... | 26C62915E0 |
| 8086:9de9 | 17aa:2292 | Intel      | Cannon Point-LP Serial IO... | 102   | intel_l... | 26C62915E0 |
| 8086:06a4 | 8086:7270 | Intel      | Comet Lake PCH SPI Contro... | 93    | intel_s... | 32F01CCAAB |
| 10de:1adb | 10de:0000 | Nvidia     | TU106 USB Type-C UCSI Con... | 92    | i2c_nvi... | 2054D0DEE6 |
| 8086:9da4 | 1028:08af | Intel      | Cannon Point-LP SPI Contr... | 92    |            | 52DEA66C52 |
| 8086:9de8 | 1028:08af | Intel      | Cannon Point-LP Serial IO... | 92    | intel_l... | 52DEA66C52 |
| 8086:9de9 | 1028:08af | Intel      | Cannon Point-LP Serial IO... | 92    | intel_l... | 52DEA66C52 |
| 8086:02a4 | 1028:0962 | Intel      | Comet Lake SPI (flash) Co... | 91    | intel_spi  | 8956FEE2F3 |
| 8086:02e8 | 1028:0962 | Intel      | Serial IO I2C Host Contro... | 91    | intel_l... | 8956FEE2F3 |
| 8086:02e9 | 1028:0962 | Intel      | Comet Lake Serial IO I2C ... | 91    | intel_l... | 8956FEE2F3 |
| 8086:9da4 | 17aa:5072 | Intel      | Cannon Point-LP SPI Contr... | 89    |            | 3678E02E46 |
| 8086:a324 | 1025:1264 | Intel      | Cannon Lake PCH SPI Contr... | 86    | intel_s... | 7F70DE1771 |
| 8086:a368 | 1025:1264 | Intel      | Cannon Lake PCH Serial IO... | 86    | intel_lpss | 7F70DE1771 |
| 8086:a369 | 1025:1264 | Intel      | Cannon Lake PCH Serial IO... | 86    | intel_lpss | 7F70DE1771 |
| 8086:06a4 | 1028:097d | Intel      | Comet Lake PCH SPI Contro... | 84    | intel_s... | 994B96D25D |
| 8086:06e8 | 1028:097d | Intel      | Comet Lake PCH Serial IO ... | 84    | intel_l... | 994B96D25D |
| 8086:06e9 | 1028:097d | Intel      | Comet Lake PCH Serial IO ... | 84    | intel_l... | 994B96D25D |
| 8086:06a4 | 1043:8694 | Intel      | Comet Lake PCH SPI Contro... | 79    | intel_s... | CAFC4421B2 |
| 8086:9da4 | 17aa:380c | Intel      | Cannon Point-LP SPI Contr... | 76    |            | 2DB4EBB6EF |
| 8086:9de8 | 17aa:3813 | Intel      | Cannon Point-LP Serial IO... | 76    | intel_l... | 2DB4EBB6EF |
| 8086:06e8 | 1043:8694 | Intel      | Comet Lake PCH Serial IO ... | 75    | intel_l... | CAFC4421B2 |
| 8086:06e9 | 1043:8694 | Intel      | Comet Lake PCH Serial IO ... | 75    | intel_l... | CAFC4421B2 |
| 8086:a324 | 17aa:3803 | Intel      | Cannon Lake PCH SPI Contr... | 73    | intel_s... | EAF7694813 |
| 8086:a368 | 17aa:3805 | Intel      | Cannon Lake PCH Serial IO... | 73    | intel_l... | EAF7694813 |
| 8086:a369 | 17aa:380b | Intel      | Cannon Lake PCH Serial IO... | 73    | intel_l... | EAF7694813 |
| 8086:02a4 | 8086:2081 | Intel      | Comet Lake SPI (flash) Co... | 70    | intel_s... | 37E756FA81 |
| 8086:02e8 | 8086:2081 | Intel      | Serial IO I2C Host Contro... | 70    | intel_l... | 37E756FA81 |
| 8086:02ea | 8086:2081 | Intel      | Comet Lake PCH-LP LPSS: I... | 70    | intel_l... | 37E756FA81 |
| 8086:9da4 | 8086:9da4 | Intel      | Cannon Point-LP SPI Contr... | 69    |            | 4C9743CDD1 |
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
| 8086:a0a4 | 17aa:5089 | Intel      | Tiger Lake-LP SPI Controller | 61    | intel_s... | 1EC4861E97 |
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
| 8086:43a4 | 1043:8694 | Intel      | Tiger Lake-H SPI Controller  | 47    | intel_spi  | B9C2FEC8AA |
| 8086:43e8 | 1043:8694 | Intel      | Tiger Lake-H Serial IO I2... | 47    | intel_l... | B9C2FEC8AA |
| 8086:9daa | 1043:1961 | Intel      | Cannon Point-LP Serial IO... | 47    | intel_lpss | 67F0B45A7A |
| 8086:9dc5 | 1043:1961 | Intel      | Cannon Point-LP Serial IO... | 47    | intel_lpss | 67F0B45A7A |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8c3d | 1458:1c3a | Intel      | 8 Series/C220 Series Chip... | 147   | serial     | FB7BEB9612 |
| 8086:3b67 | 17aa:2162 | Intel      | 5 Series/3400 Series Chip... | 146   | serial     | 8B21B7CFFE |
| 8086:2a47 | 17aa:20ec | Intel      | Mobile 4 Series Chipset A... | 142   | serial     | 56E7FA3C9B |
| 8086:1c3d | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 125   | serial     | A75FFD5203 |
| 8086:1e3d | 17aa:21f3 | Intel      | 7 Series/C210 Series Chip... | 123   | serial     | B868085BFC |
| 8086:8c3d | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 120   | serial     | CC73A253B3 |
| 8086:1e3d | 103c:3397 | Intel      | 7 Series/C210 Series Chip... | 104   | serial     | BF9875C5AC |
| 8086:29b7 | 1028:0211 | Intel      | 82Q35 Express Serial KT C... | 104   | serial     | 7E7D0BC489 |
| 8086:1e3d | 1028:0577 | Intel      | 7 Series/C210 Series Chip... | 97    | serial     | E1B966B80D |
| 8086:2e17 | 1028:0420 | Intel      | 4 Series Chipset Serial K... | 96    | serial     | 476F78A010 |
| 8086:1e3d | 17aa:21fa | Intel      | 7 Series/C210 Series Chip... | 94    | serial     | A120083D3C |
| 10ec:816a | 17aa:5081 | Realtek... | RTL8111xP UART #1            | 88    | serial     | 273A5FF27D |
| 10ec:816b | 17aa:5081 | Realtek... | RTL8111xP UART #2            | 88    | serial     | 273A5FF27D |
| 8086:2e17 | 1028:027f | Intel      | 4 Series Chipset Serial K... | 87    | serial     | F27A29129F |
| 8086:9c3d | 103c:198f | Intel      | 8 Series HECI KT             | 87    | serial     | CECD552E89 |
| 8086:1e3d | 103c:339a | Intel      | 7 Series/C210 Series Chip... | 85    | serial     | 28DA82FF00 |
| 8086:06fc | 1028:097d | Intel      | 400 Series Chipset Family... | 84    | intel_i... | 994B96D25D |
| 8086:1c3d | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 82    | serial     | C5719C54C2 |
| 8086:1c3d | 1028:047e | Intel      | 6 Series/C200 Series Chip... | 80    | serial     | 6AF9EA19B5 |
| 8086:1c3d | 103c:161c | Intel      | 6 Series/C200 Series Chip... | 80    | serial     | B6AC4539D1 |
| 8086:1c3d | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 80    | serial     | 471414140C |
| 8086:8c3d | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 79    | serial     | B9E492678D |
| 8086:9d3d | 103c:8079 | Intel      | Sunrise Point-LP Active M... | 77    | serial     | 436E9BF227 |
| 8086:1c3d | 103c:1495 | Intel      | 6 Series/C200 Series Chip... | 72    | serial     | E7C0F59F92 |
| 8086:9c3d | 17aa:220c | Intel      | 8 Series HECI KT             | 72    | serial     | FC5E995432 |
| 8086:2e17 | 103c:3048 | Intel      | 4 Series Chipset Serial K... | 69    | serial     | B62359FCB1 |
| 8086:1c3d | 103c:1497 | Intel      | 6 Series/C200 Series Chip... | 67    | serial     | C0FB875CA5 |
| 8086:1e3d | 103c:179b | Intel      | 7 Series/C210 Series Chip... | 67    | serial     | 1B2FBCDFA0 |
| 8086:8c3d | 103c:18e7 | Intel      | 8 Series/C220 Series Chip... | 66    | serial     | 94C750BA4B |
| 8086:1e3d | 17aa:21f6 | Intel      | 7 Series/C210 Series Chip... | 65    | serial     | E80BBD929F |
| 8086:2e17 | 1734:114c | Intel      | 4 Series Chipset Serial K... | 64    | serial     | 6B08158329 |
| 8086:a0fc | 1028:0991 | Intel      | Tiger Lake-LP Integrated ... | 62    | intel_i... | 22BC284F45 |
| 8086:1c3d | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 60    | serial     | 4104E265EA |
| 8086:3b67 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 60    | serial     | DDD6E2A190 |
| 8086:a0fc | 17aa:5089 | Intel      | Tiger Lake-LP Integrated ... | 59    | intel_i... | 1EC4861E97 |
| 8086:8c3d | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 57    | serial     | 6E8CA97F4B |
| 8086:3b67 | 8086:0036 | Intel      | 5 Series/3400 Series Chip... | 55    | serial     | E5F7233230 |
| 8086:29b7 | 103c:2818 | Intel      | 82Q35 Express Serial KT C... | 53    | serial     | 40DA7A8AE9 |
| 8086:1e3d | 1028:0534 | Intel      | 7 Series/C210 Series Chip... | 49    | serial     | FA4D12994D |
| 8086:34fc | 1028:096d | Intel      | Ice Lake-LP Integrated Se... | 48    | intel_i... | B0CD53DB27 |
| 10ec:816a | 17aa:5082 | Realtek... | RTL8111xP UART #1            | 47    | serial     | 037A558C7D |
| 10ec:816b | 17aa:5082 | Realtek... | RTL8111xP UART #2            | 47    | serial     | 037A558C7D |
| 8086:1c3d | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 47    | serial     | 027441E6D4 |
| 8086:1e3d | 1028:052c | Intel      | 7 Series/C210 Series Chip... | 46    | serial     | 79E64FF0D3 |
| 8086:3b67 | 103c:172a | Intel      | 5 Series/3400 Series Chip... | 46    | serial     | F527983CC9 |
| 8086:2e17 | 17aa:3048 | Intel      | 4 Series Chipset Serial K... | 44    | serial     | ED1D55E70A |
| 8086:9c3d | 1028:05cb | Intel      | 8 Series HECI KT             | 43    | serial     | 98C988645F |
| 8086:9c3d | 17aa:2214 | Intel      | 8 Series HECI KT             | 43    | serial     | A7FA6A8110 |
| 8086:9dfc | 103c:8549 | Intel      | Cannon Point-LP Integrate... | 41    | intel_i... | BA581C25B0 |
| 8086:1d3d | 103c:1589 | Intel      | C600/X79 series chipset K... | 40    | serial     | 49C747EFAD |
| 8086:8c3d | 17aa:3097 | Intel      | 8 Series/C220 Series Chip... | 40    | serial     | A5026C4013 |
| 8086:9d3d | 1028:06dc | Intel      | Sunrise Point-LP Active M... | 40    | serial     | 69A251CC1F |
| 8086:06fc | 1028:098f | Intel      | 400 Series Chipset Family... | 39    | intel_i... | 5E25D50915 |
| 8086:2e17 | 103c:3646 | Intel      | 4 Series Chipset Serial K... | 39    | serial     | 60FB363058 |
| 8086:1c3d | 17aa:3070 | Intel      | 6 Series/C200 Series Chip... | 38    | serial     | 1ECB7A6910 |
| 8086:1e3d | 17aa:3083 | Intel      | 7 Series/C210 Series Chip... | 38    | serial     | DF15656FCE |
| 8086:2e17 | 103c:3034 | Intel      | 4 Series Chipset Serial K... | 38    | serial     | D05CCA1A32 |
| 8086:1c3d | 103c:162b | Intel      | 6 Series/C200 Series Chip... | 36    | serial     | D2BBA3F247 |
| 8086:1e3d | 17aa:21fb | Intel      | 7 Series/C210 Series Chip... | 36    | serial     | 319D0DD2FF |
| 8086:1e3d | 103c:3396 | Intel      | 7 Series/C210 Series Chip... | 35    | serial     | 147C8ED96C |
| 8086:1e3d | 10cf:16ed | Intel      | 7 Series/C210 Series Chip... | 35    | serial     | 7FAB4F85E2 |
| 8086:9d3d | 17aa:2245 | Intel      | Sunrise Point-LP Active M... | 35    | serial     | 80FB4514C5 |
| 8086:1c3d | 103c:1494 | Intel      | 6 Series/C200 Series Chip... | 34    | serial     | AE5165603A |
| 8086:3b67 | 103c:304a | Intel      | 5 Series/3400 Series Chip... | 34    | serial     | 311C6C4C69 |
| 8086:9de3 | 103c:8549 | Intel      | Cannon Point-LP Keyboard ... | 34    | serial     | CD2412D37E |
| 8086:02fc | 17aa:3804 | Intel      | Comet Lake Integrated Sen... | 33    | intel_i... | 6F6E5DAF18 |
| 8086:1c3d | 17aa:21d2 | Intel      | 6 Series/C200 Series Chip... | 33    | serial     | 4F47DC5C55 |
| 8086:3b67 | 103c:1521 | Intel      | 5 Series/3400 Series Chip... | 33    | serial     | A68000E142 |
| 8086:8c3d | 1028:05bd | Intel      | 8 Series/C220 Series Chip... | 33    | serial     | 00E8B6E3FD |
| 8086:9d3d | 17aa:2233 | Intel      | Sunrise Point-LP Active M... | 33    | serial     | 9EF824D802 |
| 8086:a13d | 1028:06b9 | Intel      | 100 Series/C230 Series Ch... | 33    | serial     | 92F15AEB4D |
| 8086:a13d | 17aa:222e | Intel      | 100 Series/C230 Series Ch... | 33    | serial     | BE24112A95 |
| 8086:1e3d | 103c:18df | Intel      | 7 Series/C210 Series Chip... | 32    | serial     | F66BA65DC8 |
| 8086:3b67 | 103c:7008 | Intel      | 5 Series/3400 Series Chip... | 32    | serial     | EB060CD2C4 |
| 8086:9c3d | 1028:05ca | Intel      | 8 Series HECI KT             | 32    | serial     | 7048AA6E8B |
| 10ec:816a | 17aa:507e | Realtek... | RTL8111xP UART #1            | 31    | serial     | AC5C6A0DD6 |
| 10ec:816b | 17aa:507e | Realtek... | RTL8111xP UART #2            | 31    | serial     | AC5C6A0DD6 |
| 8086:8c3d | 17aa:30a3 | Intel      | 8 Series/C220 Series Chip... | 31    | serial     | 068BEE7912 |
| 8086:9d3d | 1028:081c | Intel      | Sunrise Point-LP Active M... | 31    | serial     | F78358FED7 |
| 8086:2e17 | 103c:3035 | Intel      | 4 Series Chipset Serial K... | 30    | serial     | 6914386D3D |
| 8086:3b67 | 10cf:152f | Intel      | 5 Series/3400 Series Chip... | 30    | serial     | 08576DED50 |
| 8086:a37c | 1028:0949 | Intel      | VROC Virtual Controller      | 30    | intel_i... | CAAAB11F09 |
| 9710:9865 | a000:1000 | MosChip... | PCI 9865 Multi-I/O Contro... | 30    | parport_pc | 715B40D8B6 |
| 10ec:816a | 10ec:8168 | Realtek... | RTL8111xP UART #1            | 29    | serial     | 07A5B3C465 |
| 8086:2e17 | 1028:0276 | Intel      | 4 Series Chipset Serial K... | 29    | serial     | 5814B0C5B0 |
| 8086:9d3d | 17aa:5053 | Intel      | Sunrise Point-LP Active M... | 29    | serial     | 4DBC231901 |
| 8086:9de3 | 1028:08e1 | Intel      | Cannon Point-LP Keyboard ... | 29    | serial     | 2932112DCA |
| 8086:9de3 | 17aa:2279 | Intel      | Cannon Point-LP Keyboard ... | 29    | serial     | F8024B89D4 |
| 8086:02fc | 1028:0959 | Intel      | Comet Lake Integrated Sen... | 28    | intel_i... | 0A8AA1439F |
| 8086:8c3d | 1028:05be | Intel      | 8 Series/C220 Series Chip... | 28    | serial     | 298AB39418 |
| 8086:8d3d | 103c:212b | Intel      | C610/X99 series chipset K... | 28    | serial     | 9D2A807F08 |
| 8086:9c3d | 103c:1991 | Intel      | 8 Series HECI KT             | 28    | serial     | 278EC34902 |
| 8086:9d3d | 17aa:225c | Intel      | Sunrise Point-LP Active M... | 28    | serial     | 2B4A1A20D9 |
| 10ec:816a | 17aa:5125 | Realtek... | RTL8111xP UART #1            | 27    | serial     | 8E00E1F239 |
| 10ec:816a | 17aa:5126 | Realtek... | RTL8111xP UART #1            | 27    | serial     | 6B6B00F95C |
| 10ec:816b | 17aa:5125 | Realtek... | RTL8111xP UART #2            | 27    | serial     | 8E00E1F239 |
| 10ec:816b | 17aa:5126 | Realtek... | RTL8111xP UART #2            | 27    | serial     | 6B6B00F95C |
| 8086:1c3d | 103c:1618 | Intel      | 6 Series/C200 Series Chip... | 27    | serial     | 48828AD0D3 |
| 8086:2a47 | 1028:0233 | Intel      | Mobile 4 Series Chipset A... | 27    | serial     | EB47D36417 |
| 8086:9de3 | 17aa:2292 | Intel      | Cannon Point-LP Keyboard ... | 27    | serial     | ABEB038C57 |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 482   | process... | 2FBF6F153B |
| 8086:5a8c |           | Intel      | Atom/Celeron/Pentium Dyna... | 311   | process... | 6121781D85 |
| 8086:3b32 | 17aa:2190 | Intel      | 5 Series/3400 Series Chip... | 306   | intel_ips  | 570863FD8C |
| 8086:a379 | 1458:8888 | Intel      | Cannon Lake PCH Thermal C... | 306   | intel_p... | 1C2A383C4F |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 305   | intel_l... | 403E735C43 |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 297   | intel_l... | 6121781D85 |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 297   | intel_l... | 6121781D85 |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 297   | intel_l... | 6121781D85 |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 295   | intel_l... | 6121781D85 |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 292   | intel_l... | 403E735C43 |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 291   | intel_l... | 403E735C43 |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 289   | intel_l... | 403E735C43 |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 287   | intel_l... | 6121781D85 |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 284   | intel_l... | 403E735C43 |
| 8086:22dc | 7270:8086 | Intel      | Atom/Celeron/Pentium Proc... | 280   | process... | 43E493B8CF |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 276   | intel_l... | 403E735C43 |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 275   | intel_l... | 403E735C43 |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 273   | intel_l... | 6121781D85 |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 273   | intel_l... | 6121781D85 |
| 8086:9d27 | 1043:1d2d | Intel      | Sunrise Point-LP Serial I... | 273   | intel_lpss | F3511CB0AA |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 272   | intel_l... | 403E735C43 |
| 8086:9ca4 | 8086:7270 | Intel      | Wildcat Point-LP Thermal ... | 272   | intel_p... | 5BE083EDAB |
| 8086:9d29 | 1043:1d2d | Intel      | Sunrise Point-LP Serial I... | 258   | intel_lpss | F3511CB0AA |
| 8086:9d31 | 8086:7270 | Intel      | Sunrise Point-LP Thermal ... | 258   | intel_p... | 6039985C3F |
| 8086:31b4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 252   | intel_l... | 4DBC03E904 |
| 8086:318c | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 246   | process... | 4DBC03E904 |
| 8086:31be | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 243   | intel_l... | 4DBC03E904 |
| 8086:31ee | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 243   | intel_l... | 4DBC03E904 |
| 8086:31b6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 241   | intel_l... | 4DBC03E904 |
| 8086:31b8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 241   | intel_l... | 4DBC03E904 |
| 8086:31ba | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 241   | intel_l... | 4DBC03E904 |
| 8086:31bc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 236   | intel_l... | 4DBC03E904 |
| 8086:31c0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 234   | intel_l... | 4DBC03E904 |
| 8086:31c6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 231   | intel_l... | 4DBC03E904 |
| 8086:31c4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 230   | intel_l... | 4DBC03E904 |
| 8086:31c2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 228   | intel_l... | 4DBC03E904 |
| 8086:9d60 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 223   | intel_l... | 6039985C3F |
| 8086:31ac | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 221   | intel_l... | 4DBC03E904 |
| 8086:31ae | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 219   | intel_l... | 4DBC03E904 |
| 8086:31b0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 219   | intel_l... | 4DBC03E904 |
| 8086:31b2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 219   | intel_l... | 4DBC03E904 |
| 8086:a131 | 1849:a131 | Intel      | 100 Series/C230 Series Ch... | 205   | intel_p... | 6B4C3F811B |
| 8086:9d62 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 201   | intel_l... | 6039985C3F |
| 8086:9d27 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 190   | intel_l... | 6039985C3F |
| 8086:9d61 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 185   | intel_l... | 6039985C3F |
| 8086:a2b1 | 1849:a2b1 | Intel      | 200 Series PCH Thermal Su... | 178   |            | 79E6EF3655 |
| 8086:1903 | 8086:1903 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 160   | process... | 20123F6B2F |
| 8086:a379 | 1025:1331 | Intel      | Cannon Lake PCH Thermal C... | 157   | intel_p... | BC9DC107D1 |
| 8086:0a03 | 8086:2010 | Intel      | Haswell-ULT Thermal Subsy... | 152   | process... | B2CDA34B7E |
| 8086:9d31 | 17aa:3861 | Intel      | Sunrise Point-LP Thermal ... | 147   | intel_p... | F86520F5A7 |
| 8086:9d60 | 17aa:3865 | Intel      | Sunrise Point-LP Serial I... | 147   | intel_l... | F86520F5A7 |
| 8086:1903 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 146   | process... | F3E5EBA0C2 |
| 8086:3b32 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 145   | intel_ips  | BA51FC9216 |
| 8086:318c | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 143   | proc_th... | 5C95C74B6C |
| 8086:31b4 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 143   | intel_lpss | 5C95C74B6C |
| 8086:31b6 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 143   | intel_lpss | 5C95C74B6C |
| 8086:31bc | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 143   | intel_lpss | 5C95C74B6C |
| 8086:31be | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 143   | intel_lpss | 5C95C74B6C |
| 8086:31c0 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 143   | intel_lpss | 5C95C74B6C |
| 8086:31ee | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 143   | intel_lpss | 5C95C74B6C |
| 8086:9a0d |           | Intel      | Tigerlake Telemetry Aggre... | 143   | intel_pmt  | 8CDB34DBC8 |
| 8086:1903 | 1028:0905 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 142   | process... | 58E43F0514 |
| 8086:a379 | 1028:0905 | Intel      | Cannon Lake PCH Thermal C... | 142   | intel_p... | 58E43F0514 |
| 1022:15e4 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Senso... | 140   | amd_sfh    | 65A49B7280 |
| 8086:02f9 | 17aa:5079 | Intel      | Comet Lake Thermal Subsytem  | 138   | intel_p... | A35AAAEB6D |
| 8086:1903 | 17aa:5079 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 138   | process... | A35AAAEB6D |
| 8086:9d63 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 136   | intel_l... | 6039985C3F |
| 8086:1903 | 17aa:2292 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 131   | process... | 080C5280D0 |
| 8086:9df9 | 8086:2074 | Intel      | Cannon Point-LP Thermal C... | 130   | intel_p... | 7EEEAAA250 |
| 8086:1903 | 17aa:2279 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 127   | process... | A01E524A66 |
| 8086:9df9 | 17aa:2279 | Intel      | Cannon Point-LP Thermal C... | 127   | intel_p... | A01E524A66 |
| 8086:a379 | 1849:a379 | Intel      | Cannon Lake PCH Thermal C... | 124   | intel_p... | 2FF008A28D |
| 8086:9d31 | 103c:8079 | Intel      | Sunrise Point-LP Thermal ... | 123   | intel_p... | 436E9BF227 |
| 8086:9d60 | 103c:8079 | Intel      | Sunrise Point-LP Serial I... | 123   | intel_l... | 436E9BF227 |
| 8086:9d31 | 8086:9d31 | Intel      | Sunrise Point-LP Thermal ... | 122   | intel_p... | F3E5EBA0C2 |
| 8086:3b32 | 17aa:38c0 | Intel      | 5 Series/3400 Series Chip... | 120   | intel_ips  | 80B7F3E584 |
| 8086:9d60 | 1025:1193 | Intel      | Sunrise Point-LP Serial I... | 119   | intel_lpss | 43BFEF3BCD |
| 8086:9d61 | 1025:1193 | Intel      | Sunrise Point-LP Serial I... | 119   | intel_lpss | 43BFEF3BCD |
| 8086:a131 | 1458:8888 | Intel      | 100 Series/C230 Series Ch... | 117   | intel_p... | 36BF6DAB37 |
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
| 8086:9df9 | 17aa:2292 | Intel      | Cannon Point-LP Thermal C... | 103   | intel_p... | 26C62915E0 |
| 8086:2932 | 17aa:3a1f | Intel      | 82801I (ICH9 Family) Ther... | 102   |            | B9412E1AB2 |
| 8086:1903 | 1028:07be | Intel      | Xeon E3-1200 v5/E3-1500 v... | 99    | process... | 69938C221E |
| 8086:1903 | 1028:07e6 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 99    | process... | 5A56854746 |
| 8086:9d31 | 1028:07e6 | Intel      | Sunrise Point-LP Thermal ... | 99    | intel_p... | 5A56854746 |
| 8086:9d60 | 1028:07e6 | Intel      | Sunrise Point-LP Serial I... | 99    | intel_l... | 5A56854746 |
| 8086:9d61 | 1028:07e6 | Intel      | Sunrise Point-LP Serial I... | 99    | intel_l... | 5A56854746 |
| 8086:a131 | 1028:07be | Intel      | 100 Series/C230 Series Ch... | 99    | intel_p... | 69938C221E |
| 8086:a160 | 1028:07be | Intel      | 100 Series/C230 Series Ch... | 99    | intel_l... | 69938C221E |
| 8086:a161 | 1028:07be | Intel      | 100 Series/C230 Series Ch... | 99    | intel_l... | 69938C221E |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:790b | 1458:5001 | AMD        | FCH SMBus Controller         | 1714  | i2c_piix4  | E52E9002D0 |
| 1002:4385 | 1002:4385 | AMD        | SBx00 SMBus Controller       | 1294  | i2c_pii... | 588CEFB67B |
| 8086:1c22 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1139  | i2c_i801   | 278873FF66 |
| 1022:790b | 1043:87c0 | AMD        | FCH SMBus Controller         | 912   | piix4_s... | A525C8911B |
| 8086:8c22 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 905   | i2c_i801   | 735015DCE2 |
| 1002:4385 | 1043:8389 | AMD        | SBx00 SMBus Controller       | 860   | i2c_pii... | 6CA4F46D1B |
| 1022:790b | 1043:8747 | AMD        | FCH SMBus Controller         | 838   | i2c_piix4  | 491D1A96CC |
| 1002:4385 |           | AMD        | SBx00 SMBus Controller       | 817   | i2c_pii... | 5E80D808A1 |
| 1002:4385 | 1458:4385 | AMD        | SBx00 SMBus Controller       | 817   | i2c_pii... | 9CF8898973 |
| 8086:27da | 1458:5001 | Intel      | NM10/ICH7 Family SMBus Co... | 797   | i2c_i801   | 5AF4FEE0BA |
| 8086:1e22 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 785   | i2c_i801   | 1575E2C682 |
| 8086:a123 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 755   | i2c_i801   | 427C8B8D8F |
| 8086:27da | 1043:8179 | Intel      | NM10/ICH7 Family SMBus Co... | 735   | i2c_i801   | D7FBB47C8B |
| 8086:1c22 | 1458:5001 | Intel      | 6 Series/C200 Series Chip... | 725   | i2c_i801   | 042607D7F1 |
| 1022:790b | 1849:790b | AMD        | FCH SMBus Controller         | 692   | i2c_piix4  | 60FFB9D428 |
| 8086:3a30 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) SM... | 668   | i2c_i801   | 6C7ECC284B |
| 8086:8c22 | 1458:5001 | Intel      | 8 Series/C220 Series Chip... | 603   | i2c_i801   | 3934A7E59D |
| 8086:1e22 | 1458:5001 | Intel      | 7 Series/C216 Chipset Fam... | 597   | i2c_i801   | BB6DE8B3E0 |
| 8086:1e22 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 574   | i2c_i801   | 16EBDC4388 |
| 1002:4385 | 1849:4385 | AMD        | SBx00 SMBus Controller       | 548   | i2c_pii... | 85B942A5C3 |
| 1022:790b | 1022:790b | AMD        | FCH SMBus Controller         | 546   | i2c_piix4  | 93825976F1 |
| 1022:790b | 1849:ffff | AMD        | FCH SMBus Controller         | 501   | i2c_piix4  | C537345CE8 |
| 8086:27da | 1849:27da | Intel      | NM10/ICH7 Family SMBus Co... | 475   | i2c_i801   | 16C678627E |
| 8086:a2a3 | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 463   | i2c_i801   | 381023907E |
| 8086:a2a3 | 1458:5001 | Intel      | 200 Series/Z370 Chipset F... | 430   | i2c_i801   | 8C2B6CF453 |
| 10de:03eb | 1849:03eb | Nvidia     | MCP61 SMBus                  | 425   | i2c_nfo... | 0F23350175 |
| 1022:780b | 1022:780b | AMD        | FCH SMBus Controller         | 423   | i2c_piix4  | 2BC95C7D30 |
| 8086:a123 | 1458:5001 | Intel      | 100 Series/C230 Series Ch... | 420   | i2c_i801   | 36BF6DAB37 |
| 1022:780b | 1849:780b | AMD        | FCH SMBus Controller         | 383   | i2c_pii... | 42CD4D28BD |
| 8086:2930 | 1043:8277 | Intel      | 82801I (ICH9 Family) SMBu... | 379   | i2c_i801   | 80ADFF7646 |
| 8086:a323 | 1043:8694 | Intel      | Cannon Lake PCH SMBus Con... | 375   | i2c_i801   | 22A32FC3F2 |
| 8086:3b30 | 17aa:2167 | Intel      | 5 Series/3400 Series Chip... | 339   | i2c_i801   | 570863FD8C |
| 8086:1c22 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 333   | i2c_i801   | ECC4515014 |
| 8086:8ca2 | 1043:8534 | Intel      | 9 Series Chipset Family S... | 329   | i2c_i801   | 5A5D3A54C3 |
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 323   | i2c_i801   | 403E735C43 |
| 8086:1c22 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 320   | i2c_i801   | D1D57448C4 |
| 8086:9c22 | 17aa:3978 | Intel      | 8 Series SMBus Controller    | 314   | i2c_i801   | 3CDDE1061C |
| 8086:2930 | 17aa:20f9 | Intel      | 82801I (ICH9 Family) SMBu... | 312   | i2c_i801   | 9A7BE426F5 |
| 8086:9ca2 | 8086:7270 | Intel      | Wildcat Point-LP SMBus Co... | 312   | i2c_i801   | 5BE083EDAB |
| 8086:a323 | 1458:5001 | Intel      | Cannon Lake PCH SMBus Con... | 306   | i2c_i801   | 1C2A383C4F |
| 1022:790b | 1043:876b | AMD        | FCH SMBus Controller         | 305   | i2c_piix4  | 24974BE67E |
| 8086:3b30 | 1043:8383 | Intel      | 5 Series/3400 Series Chip... | 304   | i2c_i801   | 4E4391F329 |
| 8086:3a30 | 1458:5001 | Intel      | 82801JI (ICH10 Family) SM... | 302   | i2c_i801   | 40C84C9637 |
| 8086:31d4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 289   | i2c_i801   | 4DBC03E904 |
| 8086:1e22 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 281   | i2c_i801   | 783D081B5A |
| 8086:8c22 | 1849:8c22 | Intel      | 8 Series/C220 Series Chip... | 280   | i2c_i801   | 111E98DDEF |
| 8086:1c22 | 1849:1c22 | Intel      | 6 Series/C200 Series Chip... | 275   | i2c_i801   | 7070F2EAF3 |
| 8086:8ca2 | 1458:5001 | Intel      | 9 Series Chipset Family S... | 259   | i2c_i801   | 5EAD0CA3AD |
| 10de:0aa2 | 10de:cb79 | Nvidia     | MCP79 SMBus                  | 252   | i2c_nfo... | 25B2F96576 |
| 8086:8c22 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 227   | i2c_i801   | 60FA5FF04C |
| 8086:2930 | 1458:5001 | Intel      | 82801I (ICH9 Family) SMBu... | 220   | i2c_i801   | 01145B2627 |
| 8086:3b30 | 1458:5001 | Intel      | 5 Series/3400 Series Chip... | 216   | i2c_i801   | 02DFFBFEA8 |
| 10de:03eb | 1458:0c11 | Nvidia     | MCP61 SMBus                  | 213   | i2c_nfo... | 701EE8CE26 |
| 8086:1e22 | 1028:0577 | Intel      | 7 Series/C216 Chipset Fam... | 207   | i2c_i801   | E1B966B80D |
| 8086:a123 | 1849:a123 | Intel      | 100 Series/C230 Series Ch... | 205   | i2c_i801   | 6B4C3F811B |
| 8086:9d23 | 8086:7270 | Intel      | Sunrise Point-LP SMBus       | 199   | i2c_i801   | B5BD43E606 |
| 8086:1c22 | 8086:1c22 | Intel      | 6 Series/C200 Series Chip... | 194   | i2c_i801   | 6978CD209F |
| 8086:1e22 | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 194   | i2c_i801   | C9D8EFC9B9 |
| 8086:1e22 | 1849:1e22 | Intel      | 7 Series/C216 Chipset Fam... | 194   | i2c_i801   | F6F957DDF3 |
| 8086:27da | 1043:83ad | Intel      | NM10/ICH7 Family SMBus Co... | 194   | i2c_i801   | E74DC83F0A |
| 8086:8c22 | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 186   | i2c_i801   | 0420EDF711 |
| 1022:790b | 1462:7c37 | AMD        | FCH SMBus Controller         | 179   | i2c_piix4  | 6B0A992D9F |
| 8086:a2a3 | 1849:a2a3 | Intel      | 200 Series/Z370 Chipset F... | 178   | i2c_i801   | 79E6EF3655 |
| 1022:790b | 1462:7c02 | AMD        | FCH SMBus Controller         | 176   | i2c_piix4  | 9BCD3D5479 |
| 8086:1c22 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 173   | i2c_i801   | A75FFD5203 |
| 8086:1e22 | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 167   | i2c_i801   | EC8AF5F350 |
| 8086:1c22 | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 165   | i2c_i801   | B96D5D5FDC |
| 8086:1e22 | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 165   | i2c_i801   | 82E60126C9 |
| 8086:1c22 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 160   | i2c_i801   | 4C3C43DAAA |
| 10de:03eb | 1043:83a4 | Nvidia     | MCP61 SMBus                  | 158   | i2c_nfo... | 324F6E5FAD |
| 8086:1c22 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 158   | i2c_i801   | B66EB36016 |
| 8086:a2a3 | 1043:872f | Intel      | 200 Series/Z370 Chipset F... | 158   | i2c_i801   | F60A34FE5C |
| 8086:283e | 17aa:20a9 | Intel      | 82801H (ICH8 Family) SMBu... | 157   | i2c_i801   | 87E69E1105 |
| 8086:2930 | 17aa:3a1d | Intel      | 82801I (ICH9 Family) SMBu... | 157   | i2c_i801   | B9412E1AB2 |
| 8086:a323 | 1025:1331 | Intel      | Cannon Lake PCH SMBus Con... | 157   | i2c_i801   | BC9DC107D1 |
| 8086:1d22 | 1043:84ef | Intel      | C600/X79 series chipset S... | 156   | i2c_i801   | 1BB97BC7DF |
| 8086:3a60 | 1028:0420 | Intel      | 82801JD/DO (ICH10 Family)... | 154   | i2c_i801   | C67A8BB677 |
| 1002:4385 | 1462:7693 | AMD        | SBx00 SMBus Controller       | 151   | i2c_pii... | DEC7AC6A34 |
| 8086:3b30 | 1028:040a | Intel      | 5 Series/3400 Series Chip... | 150   | i2c_i801   | BA51FC9216 |
| 8086:3b30 | 17aa:38bf | Intel      | 5 Series/3400 Series Chip... | 148   | i2c_i801   | 80B7F3E584 |
| 8086:9d23 | 17aa:386f | Intel      | Sunrise Point-LP SMBus       | 147   | i2c_i801   | F86520F5A7 |
| 1022:780b | 1462:7721 | AMD        | FCH SMBus Controller         | 143   | i2c_piix4  | 69DA26C946 |
| 1022:780b | 17aa:3801 | AMD        | FCH SMBus Controller         | 143   | i2c_piix4  | 0CDC6E9D84 |
| 8086:31d4 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 143   | i2c_i801   | 5C95C74B6C |
| 8086:1e22 | 1028:0534 | Intel      | 7 Series/C216 Chipset Fam... | 142   | i2c_i801   | FA4D12994D |
| 8086:a323 | 1028:0905 | Intel      | Cannon Lake PCH SMBus Con... | 142   | i2c_i801   | 58E43F0514 |
| 8086:1c22 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 141   | i2c_i801   | 0A8E84DFAD |
| 8086:8c22 | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 140   | i2c_i801   | E04A41FC30 |
| 8086:02a3 | 17aa:5079 | Intel      | Comet Lake PCH-LP SMBus H... | 138   | i2c_i801   | A35AAAEB6D |
| 8086:1e22 | 1043:124d | Intel      | 7 Series/C216 Chipset Fam... | 138   | i2c_i801   | 3498166FA2 |
| 8086:3b30 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 138   | i2c_i801   | A18FB33A6F |
| 8086:27da | 8086:27da | Intel      | NM10/ICH7 Family SMBus Co... | 137   | i2c_i801   | CE791F779F |
| 8086:1c22 | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 136   | i2c_i801   | D6237E9949 |
| 8086:3b30 | 1025:0487 | Intel      | 5 Series/3400 Series Chip... | 136   | i2c_i801   | 77E0B6A916 |
| 8086:3b30 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 136   | i2c_i801   | E3FC4E0622 |
| 8086:8c22 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 136   | i2c_i801   | EABB3946AD |
| 8086:283e | 1025:011f | Intel      | 82801H (ICH8 Family) SMBu... | 135   | i2c_i801   | 8592F1650F |
| 8086:1c22 | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 132   | i2c_i801   | 532A1D3D01 |
| 8086:1e22 | 17aa:21f6 | Intel      | 7 Series/C216 Chipset Fam... | 131   | i2c_i801   | 69A252CCD6 |
| 8086:9c22 | 17aa:220c | Intel      | 8 Series SMBus Controller    | 130   | i2c_i801   | 415CC7FE56 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:15de | 1002:15de | AMD        | Raven/Raven2/Fenghuang HD... | 1049  | snd_hda... | B2D3620851 |
| 8086:0c0c | 8086:2010 | Intel      | Xeon E3-1200 v3/4th Gen C... | 1008  | snd_hda... | 5EAD0CA3AD |
| 1002:ab38 | 1002:ab38 | AMD        | Navi 10 HDMI Audio           | 697   | snd_hda... | C537345CE8 |
| 8086:27d8 | 1458:a002 | Intel      | NM10/ICH7 Family High Def... | 680   | snd_hda... | 5AF4FEE0BA |
| 8086:8c20 | 1043:8576 | Intel      | 8 Series/C220 Series Chip... | 631   | snd_hda... | 735015DCE2 |
| 1002:4383 | 1458:a002 | AMD        | SBx00 Azalia (Intel HDA)     | 593   | snd_hda... | 9CF8898973 |
| 8086:1c20 | 1458:a002 | Intel      | 6 Series/C200 Series Chip... | 593   | snd_hda... | 042607D7F1 |
| 8086:1e20 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 574   | snd_hda... | 16EBDC4388 |
| 10de:0bea |           | Nvidia     | GF108 High Definition Aud... | 547   | snd_hda... | 997A879973 |
| 8086:8c20 | 1458:a002 | Intel      | 8 Series/C220 Series Chip... | 531   | snd_hda... | 3934A7E59D |
| 1002:aaf0 | 1da2:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 509   | snd_hda... | C483A48272 |
| 1002:4383 | 1043:8445 | AMD        | SBx00 Azalia (Intel HDA)     | 437   | snd_hda... | 21C683ED97 |
| 10de:0e0f | 1462:8c93 | Nvidia     | GK208 HDMI/DP Audio Contr... | 424   | snd_hda... | 0233AE7054 |
| 1022:1457 | 1458:a182 | AMD        | Family 17h (Models 00h-0f... | 409   | snd_hda... | E52E9002D0 |
| 1002:aab0 | 174b:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 408   | snd_hda... | 0C14FFD402 |
| 8086:a170 | 1043:86c7 | Intel      | 100 Series/C230 Series Ch... | 392   | snd_hda... | 51862605EF |
| 1002:aaf0 | 1462:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 386   | snd_hda... | 6C7ECC284B |
| 1002:1637 | 1002:1637 | AMD        | Renoir Radeon High Defini... | 373   | snd_hda... | 3F7A2585FE |
| 8086:1e20 | 1458:a002 | Intel      | 7 Series/C216 Chipset Fam... | 362   | snd_hda... | BB6DE8B3E0 |
| 13f6:0111 | 13f6:0111 | C-Media... | CMI8738/CMI8768 PCI Audio    | 360   | snd_cmipci | 8FE0FCCC66 |
| 8086:0c0c | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 356   | snd_hda... | 352946E177 |
| 8086:1c20 | 1043:8445 | Intel      | 6 Series/C200 Series Chip... | 355   | snd_hda... | 6CEE757CF0 |
| 1022:1457 | 1043:86c7 | AMD        | Family 17h (Models 00h-0f... | 341   | snd_hda... | 491D1A96CC |
| 1002:4383 | 1043:836c | AMD        | SBx00 Azalia (Intel HDA)     | 339   | snd_hda... | B820B810C9 |
| 8086:a2f0 | 1458:a182 | Intel      | 200 Series PCH HD Audio      | 339   | snd_hda... | 8C2B6CF453 |
| 8086:293e | 17aa:20f2 | Intel      | 82801I (ICH9 Family) HD A... | 336   | snd_hda... | 9A7BE426F5 |
| 1002:aaf0 | 1682:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 333   | snd_hda... | 161865EDB0 |
| 8086:a170 | 1458:a182 | Intel      | 100 Series/C230 Series Ch... | 333   | snd_hda... | 36BF6DAB37 |
| 1002:aab0 | 1043:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 332   | snd_hda... | 15946036B1 |
| 10de:03f0 | 1849:0397 | Nvidia     | MCP61 High Definition Audio  | 321   | snd_hda... | 0F23350175 |
| 8086:3b56 | 17aa:215e | Intel      | 5 Series/3400 Series Chip... | 321   | snd_hda... | 570863FD8C |
| 8086:1c20 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 320   | snd_hda... | D1D57448C4 |
| 8086:0a0c | 17aa:3978 | Intel      | Haswell-ULT HD Audio Cont... | 314   | snd_hda... | 3CDDE1061C |
| 8086:9c20 | 17aa:3978 | Intel      | 8 Series HD Audio Controller | 314   | snd_hda... | 3CDDE1061C |
| 1002:4383 | 1458:a182 | AMD        | SBx00 Azalia (Intel HDA)     | 312   | snd_hda... | 545DC9A3E0 |
| 8086:1c20 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 312   | snd_hda... | ECC4515014 |
| 8086:1e20 | 1043:8445 | Intel      | 7 Series/C216 Chipset Fam... | 312   | snd_hda... | 0CC8CA1A78 |
| 8086:9ca0 | 8086:7270 | Intel      | Wildcat Point-LP High Def... | 309   | snd_hda... | 5BE083EDAB |
| 10de:0fb9 |           | Nvidia     | GP107GL High Definition A... | 305   | snd_hda... | D55AC505B9 |
| 8086:1c20 | 1043:8415 | Intel      | 6 Series/C200 Series Chip... | 282   | snd_hda... | 87ABF841B5 |
| 1022:15e3 | 1458:a182 | AMD        | Family 17h (Models 10h-1f... | 280   | snd_hda... | B2D3620851 |
| 1022:780d | 1458:a002 | AMD        | FCH Azalia Controller        | 274   | snd_hda... | 2BC95C7D30 |
| 8086:1e20 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 266   | snd_hda... | 783D081B5A |
| 1002:aaf0 | 1043:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 262   | snd_hda... | 307DA27696 |
| 1002:aaf8 | 1002:aaf8 | AMD        | Vega 10 HDMI Audio [Radeo... | 259   | snd_hda... | 91C5853577 |
| 1022:15e3 | 1043:86c7 | AMD        | Family 17h (Models 10h-1f... | 256   | snd_hda... | 24974BE67E |
| 10de:0ac0 | 10de:cb79 | Nvidia     | MCP79 High Definition Audio  | 251   | snd_hda... | 25B2F96576 |
| 8086:293e | 1043:829f | Intel      | 82801I (ICH9 Family) HD A... | 245   | snd_hda... | 109CB750A6 |
| 1022:780d | 1043:8576 | AMD        | FCH Azalia Controller        | 244   | snd_hda... | 33D5096A54 |
| 1022:1487 | 1043:8797 | AMD        | Starship/Matisse HD Audio... | 243   | snd_hda... | A525C8911B |
| 8086:27d8 | 1849:3662 | Intel      | NM10/ICH7 Family High Def... | 243   | snd_hda... | 17892FBF03 |
| 8086:a2f0 | 1043:86c7 | Intel      | 200 Series PCH HD Audio      | 241   | snd_hda... | DF0C058313 |
| 1002:aa98 | 174b:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 234   | snd_hda... | 7A70FC2989 |
| 1002:aa68 | 1043:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 230   | snd_hda... | 860BDE5935 |
| 1102:0012 | 1102:0010 | Creativ... | Sound Core3D [Sound Blast... | 229   | snd_hda... | EAF4F27F7A |
| 1002:15de | 1043:876b | AMD        | Raven/Raven2/Fenghuang HD... | 225   | snd_hda... | 24974BE67E |
| 1002:4383 | 1458:a102 | AMD        | SBx00 Azalia (Intel HDA)     | 223   | snd_hda... | D1CF1B316E |
| 10de:0be3 |           | Nvidia     | High Definition Audio Con... | 222   | snd_hda... | 1F00F6D692 |
| 1022:1487 | 1458:a0c3 | AMD        | Starship/Matisse HD Audio... | 212   | snd_hda... | 6B471BC42D |
| 8086:1e20 | 1028:0577 | Intel      | 7 Series/C216 Chipset Fam... | 206   | snd_hda... | E1B966B80D |
| 10de:03f0 | 1458:a002 | Nvidia     | MCP61 High Definition Audio  | 205   | snd_hda... | 701EE8CE26 |
| 8086:3a3e | 1043:82fe | Intel      | 82801JI (ICH10 Family) HD... | 202   | snd_hda... | A0BD55A486 |
| 8086:9d71 | 8086:7270 | Intel      | Sunrise Point-LP HD Audio    | 200   | snd_hda... | 6039985C3F |
| 1002:aaf0 | 1458:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 196   | snd_hda... | 0F4AE74D8E |
| 8086:1e20 | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 194   | snd_hda... | C9D8EFC9B9 |
| 8086:8ca0 | 1458:a182 | Intel      | 9 Series Chipset Family H... | 191   | snd_hda... | 5EAD0CA3AD |
| 8086:a348 | 1458:a182 | Intel      | Cannon Lake PCH cAVS         | 188   | snd_hda... | 1C2A383C4F |
| 1002:aa38 | 174b:aa38 | AMD        | RV710/730 HDMI Audio [Rad... | 187   | snd_hda... | C45A00B3D6 |
| 8086:3a3e | 1458:a002 | Intel      | 82801JI (ICH10 Family) HD... | 186   | snd_hda... | 0233AE7054 |
| 1002:4383 | 1043:8444 | AMD        | SBx00 Azalia (Intel HDA)     | 185   | snd_hda... | 2CE7E668C7 |
| 1002:aab0 | 1458:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 184   | snd_hda... | E4CB18707B |
| 8086:0a0c | 8086:2010 | Intel      | Haswell-ULT HD Audio Cont... | 179   | snd_hda... | 2CCAE0040C |
| 1002:aa68 | 174b:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 178   | snd_hda... | C7B95D7362 |
| 1002:aab0 | 1462:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 177   | snd_hda... | A9908463D8 |
| 8086:27d8 | 1043:8290 | Intel      | NM10/ICH7 Family High Def... | 176   | snd_hda... | 1FF7B16CE4 |
| 8086:293e | 1458:a002 | Intel      | 82801I (ICH9 Family) HD A... | 174   | snd_hda... | 01145B2627 |
| 8086:1c20 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 173   | snd_hda... | A75FFD5203 |
| 1002:4383 | 1849:7892 | AMD        | SBx00 Azalia (Intel HDA)     | 172   | snd_hda... | 85B942A5C3 |
| 1002:9840 | 1002:9840 | AMD        | Kabini HDMI/DP Audio         | 172   | snd_hda... | 2E8639BADA |
| 1002:aae0 | 1da2:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 171   | snd_hda... | 863C87266B |
| 8086:1c20 | 8086:1c20 | Intel      | 6 Series/C200 Series Chip... | 170   | snd_hda... | 6978CD209F |
| 8086:8c20 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 170   | snd_hda... | 60FA5FF04C |
| 8086:1e20 | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 167   | snd_hda... | EC8AF5F350 |
| 8086:0c0c | 17aa:3978 | Intel      | Xeon E3-1200 v3/4th Gen C... | 166   | snd_hda... | 60FA5FF04C |
| 1022:1457 | 1849:6893 | AMD        | Family 17h (Models 00h-0f... | 165   | snd_hda... | 54F331C0EC |
| 1022:780d | 1849:7662 | AMD        | FCH Azalia Controller        | 165   | snd_hda... | 42CD4D28BD |
| 8086:1e20 | 1025:0649 | Intel      | 7 Series/C216 Chipset Fam... | 165   | snd_hda... | 82E60126C9 |
| 8086:3b56 | 1458:a002 | Intel      | 5 Series/3400 Series Chip... | 165   | snd_hda... | 02DFFBFEA8 |
| 8086:1e20 | 1458:a014 | Intel      | 7 Series/C216 Chipset Fam... | 163   | snd_hda... | 05A84215D8 |
| 8086:293e | 17aa:3a0d | Intel      | 82801I (ICH9 Family) HD A... | 163   | snd_hda... | B9412E1AB2 |
| 1002:aab0 | 1787:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 162   | snd_hda... | F00A0A0903 |
| 1022:1457 | 1043:8723 | AMD        | Family 17h (Models 00h-0f... | 161   | snd_hda... | 867E533368 |
| 10de:10f1 |           | Nvidia     | GP106 High Definition Aud... | 161   | snd_hda... | A84248C5D5 |
| 1002:aa98 | 1043:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 159   | snd_hda... | 6AF9EA19B5 |
| 8086:1c20 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 159   | snd_hda... | 4C3C43DAAA |
| 1002:aae0 | 1002:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 158   | snd_hda... | 1161AF8368 |
| 8086:1c20 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 158   | snd_hda... | B66EB36016 |
| 8086:284b | 17aa:20ac | Intel      | 82801H (ICH8 Family) HD A... | 157   | snd_hda... | 87E69E1105 |
| 8086:a348 | 1025:1331 | Intel      | Cannon Lake PCH cAVS         | 157   | snd_hda... | BC9DC107D1 |
| 8086:8c20 | 1462:d817 | Intel      | 8 Series/C220 Series Chip... | 156   | snd_hda... | 0420EDF711 |

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
| 1283:8211 | 1043:8138 | Integra... | ITE 8211F Single Channel ... | 40    | pata_it... | 9E97498649 |
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
| 104c:8033 | 103c:3085 | Texas I... | PCIxx21/PCIxx11 Flash Med... | 6     | tifm_7xx1  | 280B8AF5CC |
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
| 104c:803b | 1025:006c | Texas I... | PCIxx12 Flash Media Contr... | 5     | tifm_7xx1  | 2D3698DEC2 |
| 104c:803b | 103c:309f | Texas I... | PCIxx12 Flash Media Contr... | 5     | tifm_7xx1  | 3FFD093A67 |
| 1077:2532 | 1077:015d | QLogic     | ISP2532-based 8Gb Fibre C... | 5     | qla2xxx    | 7A2B809CB8 |
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
| 105a:4d68 | 105a:4d68 | Promise... | PDC20268 [Ultra100 TX2]      | 4     | pata_pd... | 6967AF910D |
| 105a:4d69 | 105a:4d68 | Promise... | 20269                        | 4     | pata_pd... | 21833C414E |
| 1106:401a | 1028:02f5 | VIA Tec... | VIA Card Reader Host Cont... | 4     |            | DA767A9476 |
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
| 105a:3d17 | 105a:3d17 | Promise... | PDC40718 (SATA 300 TX4)      | 3     | sata_pr... | 50A778F706 |
| 105a:3d73 | 105a:3d73 | Promise... | PDC40775 (SATA 300 TX2plus)  | 3     | sata_pr... | 8FFB1720D8 |
| 1077:2432 | 103c:7040 | QLogic     | ISP2432-based 4Gb Fibre C... | 3     | qla2xxx    | 3A362598FB |
| 1077:2432 | 1077:0138 | QLogic     | ISP2432-based 4Gb Fibre C... | 3     | qla2xxx    | FB66D16E30 |
| 10df:f0e5 | 10df:f0e5 | Emulex     | Zephyr LightPulse Fibre C... | 3     | lpfc       | E36BFCD946 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:43c8 | 1b21:1062 | AMD        | 400 Series Chipset SATA C... | 2316  | ahci       | C537345CE8 |
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 1911  | ahci       | 8948989999 |
| 1022:7901 | 1458:b002 | AMD        | FCH SATA Controller [AHCI... | 1203  | ahci       | E52E9002D0 |
| 8086:8c02 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 874   | ahci       | 735015DCE2 |
| 1022:7901 | 1043:8747 | AMD        | FCH SATA Controller [AHCI... | 832   | ahci       | 491D1A96CC |
| 1002:4390 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 769   | ahci       | 9CF8898973 |
| 8086:a102 | 1043:8694 | Intel      | Q170/Q150/B150/H170/H110/... | 738   | ahci       | 427C8B8D8F |
| 1022:43b7 | 1b21:1062 | AMD        | 300 Series Chipset SATA C... | 717   | ahci       | 3AB561BBE8 |
| 1002:4391 | 1043:84dd | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 704   | ahci       | 588CEFB67B |
| 1002:4391 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 702   | ahci       | 5E80D808A1 |
| 1002:4390 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 700   | ahci       | 6CA4F46D1B |
| 1022:7901 | 1849:7901 | AMD        | FCH SATA Controller [AHCI... | 679   | ahci       | 60FFB9D428 |
| 1022:43eb | 1b21:1062 | AMD        | Starship/Matisse Chipset ... | 677   | ahci       | 82E27C0415 |
| 8086:1c02 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 649   | ahci       | 278873FF66 |
| 1022:43b8 | 1b21:1062 | AMD        | FCH SATA Controller D        | 624   | ahci       | 24974BE67E |
| 1b21:0612 | 1043:84b7 | ASMedia... | ASM1062 Serial ATA Contro... | 610   | ahci       | 1BB97BC7DF |
| 8086:1e02 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 586   | ahci       | 1575E2C682 |
| 8086:8c02 | 1458:b005 | Intel      | 8 Series/C220 Series Chip... | 571   | ahci       | 3934A7E59D |
| 1b21:0612 | 1849:0612 | ASMedia... | ASM1062 Serial ATA Contro... | 567   | ahci       | 86F08832C0 |
| 8086:1e03 | 17aa:3977 | Intel      | 7 Series Chipset Family 6... | 529   | ahci       | 16EBDC4388 |
| 1b21:0612 | 1b21:1060 | ASMedia... | ASM1062 Serial ATA Contro... | 447   | ahci       | 93DE1508CB |
| 8086:a282 | 1043:8694 | Intel      | 200 Series PCH SATA contr... | 417   | ahci       | 9F69E439BC |
| 8086:a102 | 1458:b005 | Intel      | Q170/Q150/B150/H170/H110/... | 412   | ahci       | 36BF6DAB37 |
| 8086:a282 | 1458:b005 | Intel      | 200 Series PCH SATA contr... | 412   | ahci       | 8C2B6CF453 |
| 1022:7901 | 1043:87c0 | AMD        | FCH SATA Controller [AHCI... | 400   | ahci       | D10E4364A0 |
| 1022:43b5 | 1b21:1062 | AMD        | X370 Series Chipset SATA ... | 384   | ahci       | 3ABF73FB8A |
| 1022:43c8 | 1849:43c8 | AMD        | 400 Series Chipset SATA C... | 365   | ahci       | 60FFB9D428 |
| 1002:4391 | 1849:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 326   | ahci       | 33FEFE9DE1 |
| 1022:7801 | 1849:7801 | AMD        | FCH SATA Controller [AHCI... | 322   | ahci       | 42CD4D28BD |
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 322   | ahci       | 403E735C43 |
| 8086:1e02 | 1458:b005 | Intel      | 7 Series/C210 Series Chip... | 321   | ahci       | BB6DE8B3E0 |
| 8086:a352 | 1043:8694 | Intel      | Cannon Lake PCH SATA AHCI... | 321   | ahci       | 22A32FC3F2 |
| 8086:9c03 | 17aa:3978 | Intel      | 8 Series SATA Controller ... | 308   | ahci       | 3CDDE1061C |
| 1022:7801 | 1458:b002 | AMD        | FCH SATA Controller [AHCI... | 301   | ahci       | 15946036B1 |
| 8086:8c82 | 1043:8534 | Intel      | 9 Series Chipset Family S... | 295   | ahci       | 5A5D3A54C3 |
| 8086:1c03 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 294   | ahci       | D1D57448C4 |
| 8086:2929 | 17aa:20f8 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 289   | ahci       | 59BE8CAA30 |
| 8086:31e3 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 289   | ahci       | 4DBC03E904 |
| 8086:1c02 | 1458:b005 | Intel      | 6 Series/C200 Series Chip... | 286   | ahci       | 863C87266B |
| 8086:3b2f | 17aa:2168 | Intel      | 5 Series/3400 Series Chip... | 279   | ahci       | 8B21B7CFFE |
| 8086:a352 | 1458:b005 | Intel      | Cannon Lake PCH SATA AHCI... | 279   | ahci       | 1C2A383C4F |
| 1022:7901 | 1043:876b | AMD        | FCH SATA Controller [AHCI... | 272   | ahci       | 24974BE67E |
| 1b4b:9172 | 1458:b000 | Marvell... | 88SE9172 SATA 6Gb/s Contr... | 269   | ahci       | 853E99EEE4 |
| 8086:8c02 | 1849:8c02 | Intel      | 8 Series/C220 Series Chip... | 261   | ahci       | 111E98DDEF |
| 144d:a801 | 144d:a801 | Samsung... | Electronics SATA controller  | 260   | ahci       | CA3C48F689 |
| 8086:27c1 | 1043:83ad | Intel      | NM10/ICH7 Family SATA Con... | 258   | ahci       | E74DC83F0A |
| 8086:1e03 | 8086:7270 | Intel      | 7 Series Chipset Family 6... | 252   | ahci       | 783D081B5A |
| 197b:2362 | 1043:8460 | JMicron... | JMB362 SATA Controller       | 248   | ahci       | 588CEFB67B |
| 8086:8c82 | 1458:b005 | Intel      | 9 Series Chipset Family S... | 245   | ahci       | 5EAD0CA3AD |
| 1b21:0612 | 1043:858d | ASMedia... | ASM1062 Serial ATA Contro... | 240   | ahci       | 0981774043 |
| 1002:4390 | 1849:4390 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 235   | ahci       | 85B942A5C3 |
| 8086:3a22 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) SA... | 231   | ahci       | 6C7ECC284B |
| 10de:0ab9 | 10de:cb79 | Nvidia     | MCP79 AHCI Controller        | 226   | ahci       | 25B2F96576 |
| 8086:1c03 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 225   | ahci       | ECC4515014 |
| 8086:a102 | 1849:a102 | Intel      | Q170/Q150/B150/H170/H110/... | 201   | ahci       | 6B4C3F811B |
| 8086:1e02 | 1028:0577 | Intel      | 7 Series/C210 Series Chip... | 197   | ahci       | E1B966B80D |
| 1022:7901 | 1849:ffff | AMD        | FCH SATA Controller [AHCI... | 194   | ahci       | 70D528A8FC |
| 8086:1e02 | 1849:1e02 | Intel      | 7 Series/C210 Series Chip... | 186   | ahci       | F6F957DDF3 |
| 8086:1e03 | 17aa:21f3 | Intel      | 7 Series Chipset Family 6... | 185   | ahci       | C9D8EFC9B9 |
| 8086:3b29 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 178   | ahci       | E3FC4E0622 |
| 8086:8c02 | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 177   | ahci       | 0420EDF711 |
| 1022:7800 | 1458:b002 | AMD        | FCH SATA Controller [IDE ... | 172   | ahci       | 2BC95C7D30 |
| 8086:a282 | 1849:a282 | Intel      | 200 Series PCH SATA contr... | 168   | ahci       | 79E6EF3655 |
| 8086:1c03 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 166   | ahci       | A75FFD5203 |
| 1022:43b6 | 1b21:1062 | AMD        | X399 Series Chipset SATA ... | 165   | ahci       | 70D528A8FC |
| 8086:1c02 | 1849:1c02 | Intel      | 6 Series/C200 Series Chip... | 165   | ahci       | 7070F2EAF3 |
| 1002:4390 | 1002:4390 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 162   | ahci       | C7B95D7362 |
| 8086:1e03 | 17aa:21fa | Intel      | 7 Series Chipset Family 6... | 162   | ahci       | EC8AF5F350 |
| 1b4b:9215 | 1b4b:9215 | Marvell... | 88SE9215 PCIe 2.0 x1 4-po... | 160   | ahci       | 93DE1508CB |
| 1022:7901 | 1462:7c02 | AMD        | FCH SATA Controller [AHCI... | 159   | ahci       | 97620628A8 |
| 1002:4391 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 158   | ahci       | CA800107FC |
| 8086:1c03 | 1043:1147 | Intel      | 6 Series/C200 Series Chip... | 158   | ahci       | B96D5D5FDC |
| 8086:8c03 | 17aa:3978 | Intel      | 8 Series/C220 Series Chip... | 156   | ahci       | 60FA5FF04C |
| 8086:1e03 | 1025:0649 | Intel      | 7 Series Chipset Family 6... | 155   | ahci       | 82E60126C9 |
| 8086:1c03 | 1025:0504 | Intel      | 6 Series/C200 Series Chip... | 152   | ahci       | B66EB36016 |
| 1002:4391 | 1002:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 150   | ahci       | FBCB5D8594 |
| 8086:1d02 | 1043:84ef | Intel      | C600/X79 series chipset 6... | 147   | ahci       | 1BB97BC7DF |
| 8086:9d03 | 17aa:386a | Intel      | Sunrise Point-LP SATA Con... | 146   | ahci       | F86520F5A7 |
| 8086:31e3 | 1043:1261 | Intel      | Celeron/Pentium Silver Pr... | 143   | ahci       | 5C95C74B6C |
| 1022:7801 | 1462:7721 | AMD        | FCH SATA Controller [AHCI... | 140   | ahci       | 69DA26C946 |
| 8086:a353 | 1028:0905 | Intel      | Cannon Lake Mobile PCH SA... | 140   | ahci       | 58E43F0514 |
| 8086:2929 | 17aa:3a1a | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 139   | ahci       | B9412E1AB2 |
| 8086:02d3 | 17aa:5079 | Intel      | Comet Lake SATA AHCI Cont... | 138   | ahci       | A35AAAEB6D |
| 8086:3b29 | 104d:9071 | Intel      | 5 Series/3400 Series Chip... | 138   | ahci       | A18FB33A6F |
| 8086:1c03 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 135   | ahci       | 0A8E84DFAD |
| 8086:3b29 | 17aa:38c1 | Intel      | 5 Series/3400 Series Chip... | 135   | ahci       | 80B7F3E584 |
| 8086:a282 | 1043:872f | Intel      | 200 Series PCH SATA contr... | 132   | ahci       | F60A34FE5C |
| 8086:1c02 | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 130   | ahci       | D6237E9949 |
| 1022:7801 | 17aa:3801 | AMD        | FCH SATA Controller [AHCI... | 129   | ahci       | 0CDC6E9D84 |
| 8086:1c03 | 1028:04b0 | Intel      | 6 Series/C200 Series Chip... | 129   | ahci       | 532A1D3D01 |
| 8086:9c03 | 17aa:220c | Intel      | 8 Series SATA Controller ... | 129   | ahci       | 415CC7FE56 |
| 8086:1e03 | 1043:124d | Intel      | 7 Series Chipset Family 6... | 128   | ahci       | 3498166FA2 |
| 8086:2829 | 17aa:20a7 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 128   | ahci       | 87E69E1105 |
| 1022:7801 | 1043:85ca | AMD        | FCH SATA Controller [AHCI... | 126   | ahci       | 82894BE7A8 |
| 8086:9dd3 | 8086:2074 | Intel      | Cannon Point-LP SATA Cont... | 126   | ahci       | 7EEEAAA250 |
| 8086:1e03 | 17aa:21f6 | Intel      | 7 Series Chipset Family 6... | 123   | ahci       | 69A252CCD6 |
| 8086:9d03 | 103c:8079 | Intel      | Sunrise Point-LP SATA Con... | 123   | ahci       | 436E9BF227 |
| 1b4b:9130 | 1043:8438 | Marvell... | 88SE9128 PCIe SATA 6 Gb/s... | 122   | ahci       | 0C14FFD402 |
| 1022:43b8 | 1849:43c8 | AMD        | FCH SATA Controller D        | 121   | ahci       | E5F58B5D76 |
| 1022:7904 | 103c:8330 | AMD        | FCH SATA Controller [AHCI... | 120   | ahci       | 18CEA74915 |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:439c | 1458:5002 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1192  | pata_at... | 9CF8898973 |
| 8086:27df | 1043:8179 | Intel      | 82801G (ICH7 Family) IDE ... | 1055  | ata_pii... | 4E4E73BA37 |
| 1002:439c | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 860   | pata_at... | 6CA4F46D1B |
| 8086:27c0 | 1458:b002 | Intel      | NM10/ICH7 Family SATA Con... | 791   | ata_pii... | 5AF4FEE0BA |
| 8086:27c0 | 1043:8179 | Intel      | NM10/ICH7 Family SATA Con... | 763   | ata_pii... | 4E4E73BA37 |
| 197b:2363 | 1458:b000 | JMicron... | JMB363 SATA/IDE Controller   | 525   | ahci       | 45661425FF |
| 1002:439c | 1849:439c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 521   | pata_at... | 85B942A5C3 |
| 8086:1c00 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 494   | ata_pii... | 6CEE757CF0 |
| 8086:1c08 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 494   | ata_pii... | 6CEE757CF0 |
| 8086:27c0 | 1849:27c0 | Intel      | NM10/ICH7 Family SATA Con... | 461   | ata_pii... | 16C678627E |
| 8086:27df | 1849:27df | Intel      | 82801G (ICH7 Family) IDE ... | 447   | ata_pii... | 16C678627E |
| 8086:3a20 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) 4 ... | 446   | ata_pii... | A0BD55A486 |
| 8086:3a26 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) 2 ... | 446   | ata_pii... | A0BD55A486 |
| 8086:1c08 | 1458:b002 | Intel      | 6 Series/C200 Series Chip... | 435   | ata_pii... | 042607D7F1 |
| 10de:03f6 | 1849:03f6 | Nvidia     | MCP61 SATA Controller        | 424   | sata_nv... | 0F23350175 |
| 10de:03ec | 1849:03ec | Nvidia     | MCP61 IDE                    | 392   | pata_am... | 0F23350175 |
| 197b:2363 | 1043:824f | JMicron... | JMB363 SATA/IDE Controller   | 334   | ahci       | 4E4391F329 |
| 8086:2926 | 1043:8277 | Intel      | 82801I (ICH9 Family) 2 po... | 326   | ata_pii... | 109CB750A6 |
| 197b:2368 | 1458:b000 | JMicron... | JMB368 IDE controller        | 311   | pata_jm... | 0233AE7054 |
| 8086:27c0 | 1043:2601 | Intel      | NM10/ICH7 Family SATA Con... | 297   | ata_pii... | D7FBB47C8B |
| 8086:1e00 | 1458:b005 | Intel      | 7 Series/C210 Series Chip... | 252   | pata_acpi  | A223391BC0 |
| 8086:1e08 | 1458:b002 | Intel      | 7 Series/C210 Series Chip... | 252   | pata_acpi  | A223391BC0 |
| 1022:780c | 1849:780c | AMD        | FCH IDE Controller           | 246   | pata_at... | 42CD4D28BD |
| 8086:1c00 | 1458:b005 | Intel      | 6 Series/C200 Series Chip... | 238   | ata_pii... | 042607D7F1 |
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
| 1002:439c | 1002:439c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 178   | pata_at... | C7B95D7362 |
| 8086:1e00 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 175   | ata_pii... | 2130C28D33 |
| 8086:1e08 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 175   | ata_pii... | 2130C28D33 |
| 8086:27c0 | 8086:27c0 | Intel      | NM10/ICH7 Family SATA Con... | 175   | pata_acpi  | 7CA61CA6E1 |
| 8086:27df | 1458:b001 | Intel      | 82801G (ICH7 Family) IDE ... | 168   | ata_pii... | 7F06FF456A |
| 8086:2926 | 1458:b002 | Intel      | 82801I (ICH9 Family) 2 po... | 168   | ata_pii... | 0582E2316B |
| 10de:03f6 | 1043:83a4 | Nvidia     | MCP61 SATA Controller        | 158   | sata_nv... | 324F6E5FAD |
| 10de:03ec | 1458:5002 | Nvidia     | MCP61 IDE                    | 155   | pata_am... | 7076F55128 |
| 10de:03ec | 1043:83a4 | Nvidia     | MCP61 IDE                    | 151   | pata_am... | 324F6E5FAD |
| 8086:27df | 8086:27df | Intel      | 82801G (ICH7 Family) IDE ... | 146   | pata_acpi  | 7CA61CA6E1 |
| 8086:2850 | 1025:011f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 135   | ata_pii... | 8592F1650F |
| 11ab:6101 | 1043:82e0 | Marvell... | 88SE6101/6102 single-port... | 134   | pata_ma... | 77B7D82F05 |
| 11ab:6101 | 11ab:6101 | Marvell... | 88SE6101/6102 single-port... | 133   | pata_ma... | A5121E1871 |
| 8086:2850 | 17aa:20a6 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 126   | pata_acpi  | 87E69E1105 |
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
| 8086:2850 | 1028:01f9 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 98    | pata_acpi  | 6DBCD5A1C8 |
| 8086:27df | 1462:7592 | Intel      | 82801G (ICH7 Family) IDE ... | 97    | pata_acpi  | 4EC5CDCBD1 |
| 8086:2e16 | 1028:0420 | Intel      | 4 Series Chipset PT IDER ... | 96    | pata_acpi  | 476F78A010 |
| 11ab:6121 | 1043:82a2 | Marvell... | 88SE6111/6121 SATA II / P... | 95    | pata_ma... | DF44856137 |
| 8086:2850 | 106b:00a0 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 94    | pata_acpi  | 23D7C3ED4A |
| 8086:2825 | 1043:81ec | Intel      | 82801HR/HO/HH (ICH8R/DO/D... | 92    | ata_pii... | A402BB261D |
| 8086:2820 | 1043:81ec | Intel      | 82801H (ICH8 Family) 4 po... | 91    | ata_pii... | A402BB261D |
| 8086:1c00 | 1028:04f5 | Intel      | 6 Series/C200 Series Chip... | 87    | pata_acpi  | 5131593DDF |
| 8086:1c08 | 1028:04f5 | Intel      | 6 Series/C200 Series Chip... | 87    | pata_acpi  | 5131593DDF |
| 8086:2e16 | 1028:027f | Intel      | 4 Series Chipset PT IDER ... | 87    | pata_acpi  | F27A29129F |
| 8086:27c0 | 1462:7529 | Intel      | NM10/ICH7 Family SATA Con... | 86    | ata_pii... | 1157C2A82C |
| 8086:2850 | 1028:022f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 86    | pata_acpi  | 38B4BA227C |
| 11ab:6121 | 1043:82e0 | Marvell... | 88SE6111/6121 SATA II / P... | 85    | pata_ma... | 70EE05A53E |
| 197b:2363 | 197b:2363 | JMicron... | JMB363 SATA/IDE Controller   | 85    | ahci       | 3AEEEBEB96 |
| 8086:27df | 1462:7529 | Intel      | 82801G (ICH7 Family) IDE ... | 84    | ata_pii... | 1157C2A82C |
| 8086:2920 | 1458:b002 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 84    | pata_acpi  | 555747351D |
| 8086:2921 | 1458:b002 | Intel      | 82801IB (ICH9) 2 port SAT... | 84    | ata_pii... | 0582E2316B |
| 1039:5513 | 1039:5513 | Silicon... | 5513 IDE Controller          | 83    | pata_acpi  | AE3220A328 |
| 8086:27df | 8086:7270 | Intel      | 82801G (ICH7 Family) IDE ... | 83    | pata_acpi  | 0346BC764A |
| 8086:2850 | 106b:00a1 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 83    | pata_acpi  | 34FC60E37E |
| 197b:2361 | 1043:824f | JMicron... | JMB361 AHCI/IDE              | 79    | ahci       | C7B95D7362 |
| 10de:03f6 | 1462:7309 | Nvidia     | MCP61 SATA Controller        | 78    | sata_nv... | 0A4D7FB95D |
| 1002:439c | 1043:8443 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 77    | pata_at... | 03B2C2E1AF |
| 8086:2820 | 1028:01da | Intel      | 82801H (ICH8 Family) 4 po... | 76    | pata_acpi  | 07965413DB |
| 8086:2825 | 1028:01da | Intel      | 82801HR/HO/HH (ICH8R/DO/D... | 76    | pata_acpi  | 07965413DB |
| 8086:27c0 | 1565:5202 | Intel      | NM10/ICH7 Family SATA Con... | 75    | ata_piix   | 94EFEDE651 |
| 8086:27df | 1565:3103 | Intel      | 82801G (ICH7 Family) IDE ... | 75    | ata_piix   | 94EFEDE651 |
| 8086:2828 | 1028:01f9 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 75    | pata_acpi  | 6DBCD5A1C8 |
| 8086:2850 | 103c:30cc | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 73    | pata_acpi  | DD3C7EF3E7 |
| 1002:439c | 1462:7641 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 72    | pata_at... | 1161AF8368 |
| 11ab:6121 | 1043:8212 | Marvell... | 88SE6111/6121 SATA II / P... | 71    | pata_ma... | 6C7ECC284B |
| 197b:2368 | 1043:824f | JMicron... | JMB368 IDE controller        | 70    | pata_jm... | A0BD55A486 |
| 1b4b:917a | 1458:b000 | Marvell... | 88SE9172 SATA III 6Gb/s R... | 69    | pata_ac... | E53E495032 |
| 1b4b:91a4 | 1b4b:91a4 | Marvell... | 88SE912x IDE Controller      | 68    | pata_ma... | 2A83508F22 |
| 8086:27c0 | 1028:01ad | Intel      | NM10/ICH7 Family SATA Con... | 67    | pata_acpi  | 79FDFFE8EC |
| 8086:27c4 | 8086:7270 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 67    | pata_acpi  | 0346BC764A |
| 8086:2828 | 1025:011f | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 67    | ata_pii... | 8592F1650F |
| 1106:0415 | 1849:0415 | VIA Tec... | VT6415 PATA IDE Host Cont... | 66    | pata_vi... | 98B11D2398 |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 5049  | nvme       | 27E29303BC |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 1403  | nvme       | EACC1E3F66 |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 958   | nvme       | 8CDB34DBC8 |
| 15b7:5006 | 15b7:5006 | Sandisk    | WD Black SN750 / PC SN730... | 841   | nvme       | 00AC329183 |
| 144d:a809 | 144d:a801 | Samsung... | NVMe SSD Controller 980      | 820   | nvme       | E58D33DF6B |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 781   | nvme       | 2FC377709D |
| 15b7:5009 | 15b7:5009 | Sandisk    | WD Blue SN550 NVMe SSD       | 632   | nvme       | F581CF8319 |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | BC501 NVMe Solid State Drive | 582   | nvme       | 307DA27696 |
| 15b7:5003 | 15b7:5003 | Sandisk    | WD Blue SN500 / PC SN520 ... | 571   | nvme       | 6B8CF94EA2 |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/SN750 / PC ... | 538   | nvme       | F1CA31B777 |
| 1e0f:0001 | 1e0f:0001 | KIOXIA     | Non-Volatile memory contr... | 496   | nvme       | DA5E2F59CC |
| 126f:2263 | 126f:2263 | Silicon... | SM2263EN/SM2263XT SSD Con... | 481   | nvme       | 70D528A8FC |
| 1179:011a | 1179:0001 | Toshiba... | XG6 NVMe SSD Controller      | 465   | nvme       | 2A2CFDB7D4 |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 421   | nvme       | 5B55E39C35 |
| 2646:2263 | 2646:2263 | Kingsto... | A2000 NVMe SSD               | 398   | nvme       | B2D3620851 |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 377   | nvme       | 667289D1B9 |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 372   | nvme       | 5A56854746 |
| 1c5c:1339 | 1c5c:0000 | SK Hynix   | BC511                        | 370   | nvme       | FF8C85568E |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 369   | nvme       | 32F01CCAAB |
| 1179:0113 | 1179:0001 | Toshiba... | BG3 NVMe SSD Controller      | 360   | nvme       | A35AAAEB6D |
| 1987:5016 | 1987:5016 | Phison ... | E16 PCIe4 NVMe Controller    | 344   | nvme       | A525C8911B |
| 2646:5008 | 2646:5008 | Kingsto... | U-SNS8154P3 NVMe SSD         | 334   | nvme       | 085EF9E58D |
| c0a9:2263 | c0a9:2263 | Micron/... | P1 NVMe PCIe SSD             | 320   | nvme       | 381023907E |
| 144d:a80a | 144d:a801 | Samsung... | NVMe SSD Controller PM9A1... | 316   | nvme       | 4BF23FF82D |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 253   | nvme       | 05087F89C1 |
| 1344:5410 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 231   | nvme       | EC802D2F0B |
| 8086:0000 |           | Intel      | PROSet/Wireless WiFi Soft... | 231   | nvme       | BC9DC107D1 |
| 1c5c:1527 | 1c5c:1527 | SK Hynix   | PC401 NVMe Solid State Dr... | 226   | nvme       | EF7D0F49E1 |
| 1c5c:1627 | 1c5c:1627 | SK Hynix   | Non-Volatile memory contr... | 202   | nvme       | 58E43F0514 |
| 15b7:5005 | 15b7:5005 | Sandisk    | PC SN520 NVMe SSD            | 195   | nvme       | 72617E5DD9 |
| 1c5c:174a | 1c5c:174a | SK Hynix   | Gold P31 SSD                 | 194   | nvme       | 3F7A2585FE |
| 126f:2262 | 126f:2262 | Silicon... | SM2262/SM2262EN SSD Contr... | 191   | nvme       | 3ABF73FB8A |
| 1179:0115 | 1179:0001 | Toshiba... | XG4 NVMe SSD Controller      | 178   | nvme       | AEA7D9561E |
| 1c5c:1639 | 1c5c:1639 | SK Hynix   | Non-Volatile memory contr... | 170   | nvme       | 6AE3033841 |
| 1344:5405 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 156   | nvme       | 3CDC08297E |
| 8086:0975 | 8086:8410 | Intel      | Non-Volatile memory contr... | 153   | nvme       | 22728E37FE |
| 8086:0975 | 8086:8510 | Intel      | Non-Volatile memory contr... | 149   | nvme       | 22728E37FE |
| 10ec:5762 | 10ec:5762 | Realtek... | RTS5763DL NVMe SSD Contro... | 143   | nvme       | 6B471BC42D |
| 2646:500c | 2646:500c | Kingsto... | Technology Company Non-Vo... | 140   | nvme       | A904DAF48D |
| c0a9:540a | c0a9:540a | Micron/... | P2 NVMe PCIe SSD             | 139   | nvme       | AE3E01FEF8 |
| 1987:5013 | 1987:5013 | Phison ... | PS5013 E13 NVMe Controller   | 136   | nvme       | 97B2732F29 |
| 15b7:5008 | 15b7:5008 | Sandisk    | Non-Volatile memory contr... | 128   | nvme       | CEC5669039 |
| 10ec:5763 | 10ec:5763 | Realtek... | Realtek Non-Volatile memo... | 106   | nvme       | DF8AB9EFFB |
| 106b:2001 | 106b:2001 | Apple      | S1X NVMe Controller          | 93    | nvme       | 22A831DB3D |
| 15b7:5004 | 15b7:5004 | Sandisk    | PC SN520 NVMe SSD            | 91    | nvme       | FEB7F2A285 |
| 1987:5008 | 1987:5008 | Phison ... | NVMe Storage Controller      | 88    | nvme       | B67EC8AF25 |
| 1cc4:5008 | 1cc4:5008 | Union M... | Non-Volatile memory contr... | 88    | nvme       | 139F682D03 |
| 1cc1:33f3 | 1cc1:33f3 | ADATA T... | Non-Volatile memory contr... | 83    | nvme       | 5434B808B5 |
| 1179:010f | 1179:0001 | Toshiba... | NVMe Controller              | 79    | nvme       | 4E8A3E6A15 |
| 1e95:9100 | 126f:2263 | Solid S... | Non-Volatile memory contr... | 76    | nvme       | 370DDA1922 |
| 1344:5404 | 1344:1100 | Micron ... | Non-Volatile memory contr... | 67    | nvme       | 47907AEC3E |
| 1987:5007 | 1987:5007 | Phison ... | E7 NVMe Controller           | 67    | nvme       | 0F4AE74D8E |
| 106b:2005 | 106b:1800 | Apple      | ANS2 NVMe Controller         | 64    | nvme       | 7B3CDDA6E2 |
| c0a9:5403 | c0a9:2100 | Micron/... | NVMe Controller              | 63    | nvme       | 080C5280D0 |
| 15b7:5011 | 15b7:5011 | Sandisk    | WD Black SN850               | 62    | nvme       | EEB181F50B |
| 15b7:5001 | 1b4b:1093 | Sandisk    | WD Black NVMe SSD            | 51    | nvme       | 12DB76B549 |
| 15b7:5007 | 15b7:5007 | Sandisk    | Non-Volatile memory contr... | 51    | nvme       | 062C3B976F |
| 144d:a806 | 144d:a801 | Samsung... | Electronics Non-Volatile ... | 48    | nvme       | 6039985C3F |
| 1cc1:33f8 | 1cc1:33f8 | ADATA T... | Non-Volatile memory contr... | 48    | nvme       | BCC833AC3C |
| 1cc4:6202 | 1cc4:1cc4 | Union M... | Non-Volatile memory contr... | 46    | nvme       | 4770866D46 |
| 14a4:2300 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 44    | nvme       | 4C18C08616 |
| 1bb1:5012 | 1bb1:5012 | Seagate... | FireCuda 510 SSD             | 40    | nvme       | 5C62EC0CE3 |
| 1bb1:5016 | 1bb1:5016 | Seagate... | FireCuda 520 SSD             | 40    | nvme       | FD95402AA1 |
| 8086:2522 | 8086:3810 | Intel      | NVMe Optane Memory Series    | 37    | nvme       | 9CCE6740BE |
| 106b:2003 | 106b:2003 | Apple      | S3X NVMe Controller          | 36    | nvme       | 68EBC1AF79 |
| c0a9:5412 | c0a9:0100 | Micron/... | Non-Volatile memory contr... | 36    | nvme       | 0184E22E18 |
| 14a4:9100 | 126f:2263 | Lite-On... | NVMe Controller              | 34    | nvme       | 8A880E6565 |
| 14a4:23f1 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 33    | nvme       | AD69186227 |
| 8086:faf0 | 8086:390e | Intel      | Non-Volatile memory contr... | 33    | nvme       | 91501CC801 |
| 17aa:0003 | 17aa:1003 | Lenovo     | Non-Volatile memory contr... | 30    | nvme       | 2EAC1BFC4F |
| 14a4:22f1 | 1b4b:1093 | Lite-On... | M8Pe Series NVMe SSD         | 29    | nvme       | F68A448D75 |
| 2646:500d | 2646:500d | Kingsto... | OM3PDP3 NVMe SSD             | 29    | nvme       | DA5E2F59CC |
| 17aa:0006 | 17aa:1006 | Lenovo     | Non-Volatile memory contr... | 28    | nvme       | D8DB7F3FBD |
| 1cc4:6203 | 1cc4:1cc4 | Union M... | Non-Volatile memory contr... | 28    | nvme       | 2B043D7A15 |
| 2646:2262 | 2646:2262 | Kingsto... | KC2000 NVMe SSD              | 28    | nvme       | 7FFCE9BBC2 |
| 1344:5404 | 1344:2100 | Micron ... | Non-Volatile memory contr... | 25    | nvme       | EFDB9E6636 |
| 17aa:0005 | 17aa:1005 | Lenovo     | Non-Volatile memory contr... | 24    | nvme       | B2CBCAA16B |
| 8086:2522 | 8086:3806 | Intel      | NVMe Optane Memory Series    | 24    | nvme       | 8FEE3106F7 |
| 1b85:6018 | 1b85:6018 | OCZ Tec... | RD400/400A SSD               | 23    | nvme       | CC51204B2C |
| 10ec:5760 | 5760:10ec | Realtek... | Realtek Non-Volatile memo... | 22    | nvme       | B0E10A4766 |
| 1d97:1160 | 1d97:1160 | Shenzhe... | Non-Volatile memory contr... | 22    | nvme       | CDF70E6D0F |
| 17aa:0004 | 17aa:1004 | Lenovo     | Non-Volatile memory contr... | 21    | nvme       | BE6EEE6FB4 |
| 126f:2260 | 126f:2260 | Silicon... | Non-Volatile memory contr... | 20    | nvme       | 5130E7EC94 |
| 14a4:2100 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 20    | nvme       | DEB206B64F |
| 1c5c:1284 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 20    | nvme       | BB6272E86B |
| 1c5c:1283 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 17    | nvme       | E7A049A026 |
| c0a9:5403 | c0a9:1100 | Micron/... | NVMe Controller              | 17    | nvme       | 7EEEAAA250 |
| 10ec:5765 | 10ec:5765 | Realtek... | Realtek Non-Volatile memo... | 15    | nvme       | 93B56B7543 |
| 14a4:2200 | 1b4b:1093 | Lite-On... | Lite-On Non-Volatile memo... | 15    | nvme       | 2B63473D5B |
| 1cc4:2263 | 1cc4:1cc4 | Union M... | Non-Volatile memory contr... | 15    | nvme       | 69243BA50F |
| 1d97:2263 | 1d97:2263 | Shenzhe... | SM2263EN/SM2263XT-based O... | 15    | nvme       | F7A082BF52 |
| 14a4:3500 | 1b4b:1092 | Lite-On... | Non-Volatile memory contr... | 14    | nvme       | F6768265BF |
| 1987:5018 | 1987:5018 | Phison ... | E18 PCIe4 NVMe Controller    | 14    | nvme       | 89C1A7F472 |
| 2646:500e | 2646:500e | Kingsto... | SNVS2000G [NV1 NVMe PCIe ... | 14    | nvme       | 84B1C46F3C |
| 1cc1:8201 | 1cc1:1cc1 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 13    | nvme       | 0D45D49199 |
| 2646:500f | 2646:500f | Kingsto... | Technology Company Non-Vo... | 13    | nvme       | A9C87C6C9C |
| 8086:0953 | 8086:370d | Intel      | PCIe Data Center SSD         | 13    | nvme       | 0569365EA0 |
| 8086:2700 | 8086:3900 | Intel      | Optane SSD 900P Series       | 13    | nvme       | 67338CD31A |
| 1e0f:0009 | 1e0f:0001 | KIOXIA     | NVMe SSD                     | 12    | nvme       | A1FFAD5B6D |
| 8086:f1aa | 8086:390f | Intel      | Non-Volatile memory contr... | 11    | nvme       | BCB48851FA |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2822 | 1043:8694 | Intel      | SATA Controller [RAID mode]  | 128   | ahci       | 381023907E |
| 8086:282a | 1025:1331 | Intel      | 82801 Mobile SATA Control... | 124   | intel_n... | BC9DC107D1 |
| 8086:9a0b | 8086:0000 | Intel      | Volume Management Device ... | 111   | vmd        | 8CDB34DBC8 |
| 8086:282a | 1028:0233 | Intel      | 82801 Mobile SATA Control... | 103   | ahci       | FBC4BFA1B0 |
| 8086:2822 | 1458:b005 | Intel      | SATA Controller [RAID mode]  | 96    | ahci       | 83857E3215 |
| 8086:282a | 1028:0493 | Intel      | 82801 Mobile SATA Control... | 94    | ahci       | 4C3C43DAAA |
| 8086:282a | 1028:0534 | Intel      | 82801 Mobile SATA Control... | 94    | ahci       | FA4D12994D |
| 8086:2822 | 1028:0420 | Intel      | SATA Controller [RAID mode]  | 84    | ahci       | 999FEEE9DC |
| 8086:282a | 1028:040a | Intel      | 82801 Mobile SATA Control... | 84    | ahci       | BA51FC9216 |
| 8086:2822 | 1028:05a4 | Intel      | SATA Controller [RAID mode]  | 82    | ahci       | E49216D0BB |
| 1106:3249 | 1106:3249 | VIA Tec... | VT6421 IDE/SATA Controller   | 72    | sata_via   | 863C87266B |
| 8086:282a | 1028:0810 | Intel      | 82801 Mobile SATA Control... | 68    | ahci       | C01FA4B013 |
| 8086:282a | 103c:84a6 | Intel      | 82801 Mobile SATA Control... | 68    | ahci       | F0A8FA5E7A |
| 8086:2822 | 1028:047e | Intel      | SATA Controller [RAID mode]  | 60    | ahci       | 6AF9EA19B5 |
| 103c:323a | 103c:3245 | Hewlett... | Smart Array G6 controllers   | 54    | hpsa       | 9753F223E2 |
| 8086:282a | 103c:1818 | Intel      | 82801 Mobile SATA Control... | 53    | ahci       | 31FF7DD229 |
| 8086:282a | 1028:05cb | Intel      | 82801 Mobile SATA Control... | 51    | ahci       | FE4153E816 |
| 8086:282a | 17aa:380f | Intel      | 82801 Mobile SATA Control... | 51    | ahci       | 3115478A9B |
| 8086:2822 | 103c:1309 | Intel      | SATA Controller [RAID mode]  | 48    | ahci       | EB0C052885 |
| 8086:282a | 1025:1264 | Intel      | 82801 Mobile SATA Control... | 48    | ahci       | E0579175C3 |
| 8086:282a | 1025:1333 | Intel      | 82801 Mobile SATA Control... | 48    | intel_n... | 271C2188CB |
| 8086:282a | 1028:062e | Intel      | 82801 Mobile SATA Control... | 46    | ahci       | 91837758AC |
| 8086:2822 | 103c:2a6f | Intel      | SATA Controller [RAID mode]  | 45    | ahci       | D5D1B22B75 |
| 1095:3114 | 1095:7114 | Silicon... | SiI 3114 [SATALink/SATARa... | 42    | sata_sil   | 497C824FD5 |
| 8086:282a | 103c:86c9 | Intel      | 82801 Mobile SATA Control... | 40    | ahci       | B81AB61049 |
| 8086:2822 | 1043:8534 | Intel      | SATA Controller [RAID mode]  | 39    | ahci       | 6476A95A04 |
| 8086:282a | 1028:0535 | Intel      | 82801 Mobile SATA Control... | 39    | ahci       | 41D65E59EB |
| 8086:282a | 103c:8532 | Intel      | 82801 Mobile SATA Control... | 39    | ahci       | B33C31B0CF |
| 1022:7916 | 1022:7901 | AMD        | RS690 PCI to PCI Bridge (... | 38    | ahci       | 6B471BC42D |
| 8086:2822 | 103c:2a9c | Intel      | SATA Controller [RAID mode]  | 38    | ahci       | 14712A07FB |
| 8086:9a0b | 8086:7270 | Intel      | Volume Management Device ... | 38    | vmd        | 7851B07853 |
| 8086:282a | 17aa:3814 | Intel      | 82801 Mobile SATA Control... | 37    | ahci       | DB1D64D8B0 |
| 8086:2822 | 1028:052c | Intel      | SATA Controller [RAID mode]  | 35    | ahci       | 79E64FF0D3 |
| 8086:282a | 1028:05be | Intel      | 82801 Mobile SATA Control... | 35    | ahci       | DF9262F810 |
| 8086:282a | 1028:040b | Intel      | 82801 Mobile SATA Control... | 34    | ahci       | 25C1BD8E0E |
| 8086:282a | 1028:05bd | Intel      | 82801 Mobile SATA Control... | 34    | ahci       | 3020581460 |
| 8086:282a | 1028:05ca | Intel      | 82801 Mobile SATA Control... | 34    | ahci       | DBF0FD04C3 |
| 8086:282a | 1028:06dc | Intel      | 82801 Mobile SATA Control... | 34    | ahci       | FDC6203A6E |
| 8086:282a | 1043:1311 | Intel      | 82801 Mobile SATA Control... | 34    | ahci       | F3511CB0AA |
| 8086:2822 | 103c:130a | Intel      | SATA Controller [RAID mode]  | 33    | ahci       | 328FCB35ED |
| 8086:282a | 1028:024f | Intel      | 82801 Mobile SATA Control... | 32    | ahci       | E475348B1E |
| 8086:282a | 1043:1961 | Intel      | 82801 Mobile SATA Control... | 32    | ahci       | 20A828B938 |
| 1022:43bd | 1b21:1062 | AMD        | FCH RAID Controller          | 31    | rcraid     | 1E61CC1252 |
| 8086:282a | 1028:053c | Intel      | 82801 Mobile SATA Control... | 31    | ahci       | E6D67EBC2E |
| 8086:282a | 17aa:3810 | Intel      | 82801 Mobile SATA Control... | 31    | ahci       | 2BF6813AD9 |
| 8086:9a0b | 1028:0991 | Intel      | Volume Management Device ... | 31    | vmd        | 22BC284F45 |
| 8086:282a | 1028:024d | Intel      | 82801 Mobile SATA Control... | 30    | ahci       | C486155F48 |
| 8086:282a | 1028:0494 | Intel      | 82801 Mobile SATA Control... | 30    | ahci       | E292C83E5F |
| 8086:282a | 1028:0798 | Intel      | 82801 Mobile SATA Control... | 30    | ahci       | 1B93E3C1C9 |
| 8086:2822 | 1458:b000 | Intel      | SATA Controller [RAID mode]  | 28    | ahci       | 54642E6EE3 |
| 8086:282a | 1028:081c | Intel      | 82801 Mobile SATA Control... | 28    | ahci       | 8462C89AD6 |
| 103c:323b | 103c:3354 | Hewlett... | Smart Array Gen8 Controllers | 27    | hpsa       | 7B579629BB |
| 1095:3132 | 1043:819f | Silicon... | SiI 3132 Serial ATA Raid ... | 27    | sata_sil24 | 1739E3B05D |
| 8086:2822 | 1028:0293 | Intel      | SATA Controller [RAID mode]  | 27    | ahci       | ECDA4970D8 |
| 8086:2822 | 1043:872f | Intel      | SATA Controller [RAID mode]  | 27    | ahci       | 37523E831D |
| 8086:2826 | 103c:1589 | Intel      | C600/X79 series chipset S... | 27    | ahci       | 46C635D9AB |
| 8086:282a | 1028:0533 | Intel      | 82801 Mobile SATA Control... | 27    | ahci       | 872CFFF7DA |
| 8086:282a | 103c:84a7 | Intel      | 82801 Mobile SATA Control... | 27    | ahci       | 20517EF47C |
| 8086:9a0b | 14c0:012d | Intel      | Volume Management Device ... | 27    | vmd        | 3D77CD95D3 |
| 1095:3132 | 1095:7132 | Silicon... | SiI 3132 Serial ATA Raid ... | 26    | sata_sil24 | C586C22B15 |
| 1095:3512 | 1095:6512 | Silicon... | SiI 3512 [SATALink/SATARa... | 26    | sata_sil   | EFDE12BE05 |
| 8086:282a | 1025:1345 | Intel      | 82801 Mobile SATA Control... | 26    | intel_n... | 7463FACB20 |
| 8086:282a | 1025:128d | Intel      | 82801 Mobile SATA Control... | 25    | ahci       | 1F5C815672 |
| 8086:282a | 1028:086f | Intel      | 82801 Mobile SATA Control... | 25    | ahci       | 28D725057F |
| 8086:282a | 103c:86c8 | Intel      | 82801 Mobile SATA Control... | 25    | ahci       | 1260542A5E |
| 8086:282a | 17aa:380e | Intel      | 82801 Mobile SATA Control... | 25    | ahci       | 3B7BF6FDEB |
| 8086:282a | 1028:06de | Intel      | 82801 Mobile SATA Control... | 24    | ahci       | 17D97E59DE |
| 8086:2822 | 1028:06b9 | Intel      | SATA Controller [RAID mode]  | 23    | ahci       | E4278D3243 |
| 8086:2822 | 103c:130b | Intel      | SATA Controller [RAID mode]  | 23    | ahci       | 665BAE2867 |
| 8086:2827 | 103c:212b | Intel      | C610/X99 series chipset s... | 23    | ahci       | 9D2A807F08 |
| 8086:282a | 1043:1fc0 | Intel      | 82801 Mobile SATA Control... | 23    | ahci       | 31B0B9087E |
| 8086:282a | 1028:0410 | Intel      | 82801 Mobile SATA Control... | 22    | ahci       | 75A9AA20F2 |
| 8086:282a | 1028:04a3 | Intel      | 82801 Mobile SATA Control... | 22    | ahci       | 6E09C36301 |
| 8086:282a | 1028:0532 | Intel      | 82801 Mobile SATA Control... | 22    | ahci       | D040F874C9 |
| 8086:282a | 1028:05de | Intel      | 82801 Mobile SATA Control... | 22    | ahci       | 22977AA779 |
| 8086:282a | 1028:062d | Intel      | 82801 Mobile SATA Control... | 22    | ahci       | 9834990221 |
| 8086:282a | 1028:0492 | Intel      | 82801 Mobile SATA Control... | 21    | ahci       | DC31C90631 |
| 8086:282a | 1028:07a7 | Intel      | 82801 Mobile SATA Control... | 21    | ahci       | 3ED90A1781 |
| 1000:0079 | 1028:1f17 | LSI Log... | MegaRAID SAS 2108 [Libera... | 20    | megarai... | 246F93C093 |
| 8086:282a | 1028:053d | Intel      | 82801 Mobile SATA Control... | 20    | ahci       | A377D34C0D |
| 8086:282a | 1028:062b | Intel      | 82801 Mobile SATA Control... | 20    | ahci       | FB61A77E5C |
| 8086:282a | 103c:8533 | Intel      | 82801 Mobile SATA Control... | 20    | ahci       | B16AD0BCB8 |
| 1095:0680 | 1095:3680 | Silicon... | PCI0680 Ultra ATA-133 Hos... | 19    | pata_si... | 07B9B49ADB |
| 8086:2822 | 1043:84ca | Intel      | SATA Controller [RAID mode]  | 19    | ahci       | 46987EB4C8 |
| 8086:2826 | 103c:212b | Intel      | C600/X79 series chipset S... | 19    | ahci       | 9D2A807F08 |
| 8086:282a | 1025:1357 | Intel      | 82801 Mobile SATA Control... | 19    | intel_n... | F06A523887 |
| 8086:282a | 1028:0572 | Intel      | 82801 Mobile SATA Control... | 19    | ahci       | 9A64D0961F |
| 8086:282a | 1028:05e0 | Intel      | 82801 Mobile SATA Control... | 19    | ahci       | 44B8F3A781 |
| 8086:282a | 1028:062c | Intel      | 82801 Mobile SATA Control... | 19    | ahci       | 974759ECDB |
| 8086:282a | 103c:85ef | Intel      | 82801 Mobile SATA Control... | 19    | ahci       | CB73E3814C |
| 8086:9a0b | 103c:87e1 | Intel      | Volume Management Device ... | 19    | vmd        | A92566EE89 |
| 1000:005d | 1000:9363 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 18    | megarai... | 2F38C3FD0E |
| 8086:2826 | 103c:158a | Intel      | C600/X79 series chipset S... | 18    | ahci       | 6C22E51BFC |
| 8086:282a | 1028:057e | Intel      | 82801 Mobile SATA Control... | 18    | ahci       | F31078AFD8 |
| 8086:282a | 1028:07a0 | Intel      | 82801 Mobile SATA Control... | 18    | ahci       | C639789B23 |
| 8086:282a | 1043:1501 | Intel      | 82801 Mobile SATA Control... | 18    | ahci       | 42BB3AA5DB |
| 1000:0060 | 1028:1f0c | LSI Log... | MegaRAID SAS 1078            | 17    | megarai... | 26944912D7 |
| 8086:2822 | 1028:02da | Intel      | SATA Controller [RAID mode]  | 17    | ahci       | 51D64C0798 |
| 8086:2822 | 1028:05a6 | Intel      | SATA Controller [RAID mode]  | 17    | ahci       | D41DEB84BF |
| 8086:2822 | 1028:07a3 | Intel      | SATA Controller [RAID mode]  | 17    | ahci       | 9D38BA75C7 |

### Storage/sas (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1d6b | 103c:1589 | Intel      | C602 chipset 4-Port SATA ... | 43    | isci       | 49C747EFAD |
| 1000:0086 | 103c:158b | Broadco... | SAS2308 PCI-Express Fusio... | 31    | mpt3sas    | 24399F4E69 |
| 8086:1d6b | 103c:158a | Intel      | C602 chipset 4-Port SATA ... | 29    | isci       | 6C22E51BFC |
| 1000:0072 | 1000:3020 | LSI Log... | SAS2008 PCI-Express Fusio... | 26    | mpt3sas    | 580838BF3C |
| 1000:0072 | 1028:1f1c | LSI Log... | SAS2008 PCI-Express Fusio... | 22    | mpt3sas    | 2F188B606A |
| 8086:1d6b | 103c:158b | Intel      | C602 chipset 4-Port SATA ... | 22    | isci       | 24399F4E69 |
| 8086:1d6b | 1028:0497 | Intel      | C602 chipset 4-Port SATA ... | 19    | isci       | 0B25532F6B |
| 1000:0072 | 15d9:0400 | Broadco... | SAS2008 PCI-Express Fusio... | 11    | mpt3sas    | DABCC72257 |
| 1000:0087 | 1028:05a1 | Broadco... | SAS2308 PCI-Express Fusio... | 11    | mpt3sas    | 3CF0EB9253 |
| 1000:0087 | 1000:3020 | LSI Log... | SAS2308 PCI-Express Fusio... | 10    | mpt3sas    | FB32FC7215 |
| 8086:1d6b | 1043:84ef | Intel      | C602 chipset 4-Port SATA ... | 10    | isci       | A4C832AB44 |
| 8086:1d6b | 1734:11b6 | Intel      | C602 chipset 4-Port SATA ... | 10    | isci       | E689B2DE7A |
| 1000:0072 | 1028:1f1d | LSI Log... | SAS2008 PCI-Express Fusio... | 8     | mpt3sas    | B23B38CFA6 |
| 1000:0097 | 1028:0619 | Broadco... | SAS3008 PCI-Express Fusio... | 8     | mpt3sas    | 36E6C22CC6 |
| 19e5:a230 |           | Huawei ... | HiSilicon SAS 3.0 HBA        | 7     | hisi_sa... | F548D0A0A9 |
| 8086:1d6b | 17aa:1026 | Intel      | C602 chipset 4-Port SATA ... | 7     | isci       | F8BE96C44A |
| 1000:0070 | 1000:3010 | LSI Log... | SAS2004 PCI-Express Fusio... | 6     | mpt3sas    | 60FF076C16 |
| 1000:0086 | 15d9:0691 | Broadco... | SAS2308 PCI-Express Fusio... | 6     | mpt3sas    | 0569365EA0 |
| 1000:0072 | 1000:3060 | Broadco... | SAS2008 PCI-Express Fusio... | 5     | mpt3sas    | 0D69EE2560 |
| 1000:0072 | 1028:1f1e | Broadco... | SAS2008 PCI-Express Fusio... | 5     | mpt3sas    | 0335142464 |
| 1000:0097 | 1000:30e0 | LSI Log... | SAS3008 PCI-Express Fusio... | 5     | mpt3sas    | 8EF7556453 |
| 8086:1d6b | 1849:1d6b | Intel      | C602 chipset 4-Port SATA ... | 5     | isci       | 957F68F2B7 |
| 1000:0064 | 1000:30c0 | Broadco... | SAS2116 PCI-Express Fusio... | 4     | mpt3sas    | E88E18FCCA |
| 1000:0087 | 1000:3060 | Broadco... | SAS2308 PCI-Express Fusio... | 4     | mpt3sas    | BD7193B93F |
| 1000:0097 | 1000:30a0 | Broadco... | SAS3008 PCI-Express Fusio... | 4     | mpt3sas    | 98EA3E97E6 |
| 1000:0097 | 15d9:0808 | Broadco... | SAS3008 PCI-Express Fusio... | 4     | mpt3sas    | 3CFD00A1CD |
| 8086:1d68 | 1028:0495 | Intel      | C606 chipset Dual 4-Port ... | 4     | isci       | 0C3A459A0E |
| 8086:1d6b | 15d9:062c | Intel      | C602 chipset 4-Port SATA ... | 4     | isci       | D8C9D41136 |
| 8086:1d6b | 8086:35a1 | Intel      | C602 chipset 4-Port SATA ... | 4     | isci       | FE1E6CFF79 |
| 9005:028f | 103c:0602 | Adaptec    | Smart Storage PQI SAS        | 4     | smartpqi   | 7AB4F05613 |
| 1000:0064 | 1000:3030 | Broadco... | SAS2116 PCI-Express Fusio... | 3     | mpt3sas    | BF66E1D281 |
| 1000:0072 | 1000:3040 | LSI Log... | SAS2008 PCI-Express Fusio... | 3     | mpt3sas    | 61DFD26E01 |
| 1000:0072 | 1000:30f0 | Broadco... | SAS2008 PCI-Express Fusio... | 3     | mpt3sas    | 3B97DD5D3E |
| 8086:1d60 | 1028:0497 | Intel      | C608 chipset Dual 4-Port ... | 3     | isci       | 113235448D |
| 8086:1d6b | 17aa:1028 | Intel      | C602 chipset 4-Port SATA ... | 3     | isci       | 8841F4EB25 |
| 1000:0064 | 1000:30d0 | Broadco... | SAS2116 PCI-Express Fusio... | 2     | mpt3sas    | 31EA0B6D96 |
| 1000:0072 | 1000:3080 | LSI Log... | SAS2008 PCI-Express Fusio... | 2     | mpt3sas    | 53B29EDC51 |
| 1000:0072 | 1000:30b0 | Broadco... | SAS2008 PCI-Express Fusio... | 2     | mpt3sas    | 33A89C4C5A |
| 1000:007e | 108e:050a | Broadco... | SSS6200 PCI-Express Flash... | 2     | mpt3sas    | 12E7B4FF29 |
| 1000:0086 | 1000:0086 | LSI Log... | SAS2308 PCI-Express Fusio... | 2     | mpt3sas    | 63B48DFA23 |
| 1000:0087 | 1000:3030 | Broadco... | SAS2308 PCI-Express Fusio... | 2     | mpt3sas    | 1D8E87502F |
| 1000:0087 | 1000:3040 | LSI Log... | SAS2308 PCI-Express Fusio... | 2     | mpt3sas    | 9FC500CA2E |
| 1000:0087 | 1590:0041 | Broadco... | SAS2308 PCI-Express Fusio... | 2     | mpt3sas    | DC85BB471A |
| 1000:0097 | 1000:0090 | Broadco... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | 2903921AEB |
| 1000:0097 | 1028:1f46 | Broadco... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | 3C396F0B59 |
| 1000:0097 | 1028:1f53 | Broadco... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | DF9A63BE43 |
| 1000:0097 | 1043:860c | Broadco... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | C934F8E023 |
| 1000:0097 | 1734:1214 | LSI Log... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | A7138E79C0 |
| 1000:00c4 | 1000:31a0 | Broadco... | SAS3224 PCI-Express Fusio... | 2     | mpt3sas    | 195F9748AD |
| 8086:1d68 | 15d9:0626 | Intel      | C606 chipset Dual 4-Port ... | 2     | isci       | 2B8813F5C4 |
| 8086:1d69 | 17aa:1026 | Intel      | C604/X79 series chipset 4... | 2     | isci       | 99B572DE7F |
| 8086:1d69 | 8086:1d69 | Intel      | C604/X79 series chipset 4... | 2     | isci       | E0EF143493 |
| 8086:1d6a | 17aa:1027 | Intel      | C600/X79 series chipset D... | 2     | isci       | 8D7A62CE1A |
| 8086:1d6b | 1028:0495 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | BC7C3F8C4D |
| 8086:1d6b | 1028:0496 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 80E68A5C66 |
| 8086:1d6b | 1170:0054 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 1B5977B024 |
| 8086:1d6b | 15d9:0628 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 6908407322 |
| 8086:1d6b | 15d9:062b | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | FD24B5D375 |
| 8086:1d6b | 15d9:0636 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | DD93F62FFC |
| 8086:1d6b | 15d9:0660 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | AFE42B7E58 |
| 8086:1d6b | 15d9:0709 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 7D84E25468 |
| 8086:1d6b | 15d9:070a | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 1F3561AA7D |
| 8086:1d6b | 17aa:1027 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | E3C6A7B793 |
| 1000:005d | 1000:9a63 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | megarai... | 8EFAF14886 |
| 1000:005d | 8086:3a1e | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | megarai... | 98C12554CB |
| 1000:0064 | 15d9:083c | LSI Log... | SAS2116 PCI-Express Fusio... | 1     | mpt3sas    | DB25C87154 |
| 1000:0070 | 1014:03f7 | LSI Log... | SAS2004 PCI-Express Fusio... | 1     | mpt2sas    | D7CBC31CEE |
| 1000:0070 | 1014:03f8 | Broadco... | SAS2004 PCI-Express Fusio... | 1     | mpt2sas    | 7C109612B9 |
| 1000:0072 | 1000:3050 | LSI Log... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | 0B2E10175B |
| 1000:0072 | 1014:03cb | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | 2B9980B42B |
| 1000:0072 | 1170:6019 | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | 395F17CE3F |
| 1000:007e | 1000:0507 | Broadco... | SSS6200 PCI-Express Flash... | 1     | mpt3sas    | BA4FFBDA6D |
| 1000:0087 | 1000:0087 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | BA0F3C3B41 |
| 1000:0087 | 1014:047a | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | B9E45DB0E3 |
| 1000:0087 | 1028:1f34 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | FBDF83F7FF |
| 1000:0087 | 1028:1f35 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | C9C876F0E7 |
| 1000:0087 | 1028:1f38 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | 29F49B3A79 |
| 1000:0087 | 1590:0042 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | A14015F487 |
| 1000:0087 | 1590:0043 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | AB5267E214 |
| 1000:0087 | 8086:3060 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | F2B18DC242 |
| 1000:0087 | 8086:3519 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | E70645D3E6 |
| 1000:0097 | 1849:0097 | Broadco... | SAS3008 PCI-Express Fusio... | 1     | mpt3sas    | FA8D061F8F |
| 1000:00ac | 1000:3000 | Broadco... | SAS3416 Fusion-MPT Tri-Mo... | 1     | mpt3sas    | 8C80B197C2 |
| 1000:00ac | 1d49:0203 | Broadco... | SAS3416 Fusion-MPT Tri-Mo... | 1     | mpt3sas    | 928EE22E71 |
| 1000:00af | 1000:3010 | Broadco... | SAS3408 Fusion-MPT Tri-Mo... | 1     | mpt3sas    | 1FCE0AB0E8 |
| 1000:00af | 1d49:0202 | Broadco... | SAS3408 Fusion-MPT Tri-Mo... | 1     | mpt3sas    | 928EE22E71 |
| 1000:00c4 | 1000:3190 | Broadco... | SAS3224 PCI-Express Fusio... | 1     | mpt3sas    | 00FDD71981 |
| 117c:0042 | 117c:0042 | ATTO Te... | ExpressSAS 6Gb/s SAS/SATA... | 1     | pm80xx     | 2DF53AC534 |
| 117c:0042 | 117c:0046 | ATTO Te... | ExpressSAS 6Gb/s SAS/SATA... | 1     | pm80xx     | 72B568A9B6 |
| 11f8:8001 |           | PMC-Sierra | SPC 8x6G SAS/SATA (storport) | 1     | pm80xx     | 4F5756D065 |
| 8086:1d60 | 1028:0496 | Intel      | C608 chipset Dual 4-Port ... | 1     | isci       | 1518FF90F9 |
| 8086:1d68 | 15d9:0628 | Intel      | C606 chipset Dual 4-Port ... | 1     | isci       | 74EFA61302 |
| 8086:1d68 | 15d9:0630 | Intel      | C606 chipset Dual 4-Port ... | 1     | isci       | 575A60EDC8 |
| 8086:1d68 | 8086:1d68 | Intel      | C606 chipset Dual 4-Port ... | 1     | isci       | EBA3BBC86D |
| 8086:1d69 | 1458:1d69 | Intel      | C604/X79 series chipset 4... | 1     | isci       | 0AC54E7FB4 |
| 8086:1d69 | 15d9:0706 | Intel      | C604/X79 series chipset 4... | 1     | isci       | AA3D8595BA |
| 8086:1d6a | 8086:3583 | Intel      | C600/X79 series chipset D... | 1     | isci       | 9F6D925B73 |
| 8086:1d6b |           | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 99E743CA9E |
| 8086:1d6b | 1014:0432 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | FC0558920D |
| 8086:1d6b | 15d9:0626 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 42A76FBC95 |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1000:0058 | 1028:021d | LSI Log... | SAS1068E PCI-Express Fusi... | 28    | mptsas     | 2F188B606A |
| 1000:0058 | 103c:130b | LSI Log... | SAS1068E PCI-Express Fusi... | 27    | mptsas     | 665BAE2867 |
| 1000:0058 | 1028:1f0e | LSI Log... | SAS1068E PCI-Express Fusi... | 18    | mptsas     | F1B8348661 |
| 1000:0056 | 1000:3090 | LSI Log... | SAS1064ET PCI-Express Fus... | 14    | mptsas     | 06EFEDBF24 |
| 9004:5078 | 9004:7850 | Adaptec    | AIC-7850T/7856T [AVA-2902... | 11    | aic7xxx    | ED9FEAB726 |
| 1000:0054 | 103c:0a98 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 10    | mptsas     | 4299904C4D |
| 9004:7178 |           | Adaptec    | AIC-7870P/7871 [AHA-2940/... | 8     | aic7xxx    | CAD3B9B0F1 |
| 1000:0056 | 1014:03bb | LSI Log... | SAS1064ET PCI-Express Fus... | 7     | mptsas     | A6FAE29097 |
| 1000:0058 | 1028:1f0f | LSI Log... | SAS1068E PCI-Express Fusi... | 6     | mptsas     | 24358FA4BD |
| 1000:0058 | 1028:1f10 | Broadco... | SAS1068E PCI-Express Fusi... | 6     | mptsas     | 5FBC90E0CD |
| 9004:8178 |           | Adaptec    | AIC-7870P/7881U [AHA-2940... | 6     | aic7xxx    | E4B76F9137 |
| 9004:8178 | 9004:7881 | Adaptec    | AIC-7870P/7881U [AHA-2940... | 6     | aic7xxx    | AB9C12AF26 |
| 9005:8017 | 9005:0045 | Adaptec    | ASC-29320ALP U320            | 6     | aic79xx    | 096D3E62FE |
| 1b85:1021 | 1b85:1021 | OCZ Tec... | OCZ SCSI storage controller  | 5     | mvsas      | 71E296F6E0 |
| 9004:6178 | 9004:7861 | Adaptec    | AIC-7861                     | 5     | aic7xxx    | 5416A71FEA |
| 1000:0001 |           | LSI Log... | 53c810                       | 4     | sym53c8xx  | F2C624A258 |
| 1000:0050 | 103c:3015 | Broadco... | SAS1064 PCI-X Fusion-MPT SAS | 4     | mptsas     | C20157D427 |
| 1000:0058 | 103c:12fe | LSI Log... | SAS1068E PCI-Express Fusi... | 4     | mptsas     | 6D6F2CE899 |
| 1000:0058 | 103c:3229 | LSI Log... | SAS1068E PCI-Express Fusi... | 4     | mptsas     | 078AB4C114 |
| 1de1:0391 | 1de1:0391 | Tekram ... | TRM-S1040 [DC-315 / DC-39... | 4     | dc395x     | 510A70AB34 |
| 1000:0030 | 1000:50c0 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 3     | mptspi     | 9844591CD4 |
| 1000:0030 | 103c:12f1 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 3     | mptspi     | AD9D1EDCBB |
| 1000:0030 | 103c:1500 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 3     | mptspi     | A94946D561 |
| 1000:0054 | 1028:1f08 | LSI Log... | SAS1068 PCI-X Fusion-MPT SAS | 3     | mptsas     | CB363A3342 |
| 1000:0058 | 1734:1130 | Broadco... | SAS1068E PCI-Express Fusi... | 3     | mptsas     | 43C0756BA6 |
| 10cd:1300 | 10cd:1310 | Advance... | ASC1300 / ASC3030 [ABP940... | 3     | advansys   | A978613702 |
| 9004:5078 |           | Adaptec    | AIC-7850T/7856T [AVA-2902... | 3     | aic7xxx    | 330F034C61 |
| 9004:6178 |           | Adaptec    | AIC-7861                     | 3     | aic7xxx    | A35B309960 |
| 9005:0010 | 9005:a180 | Adaptec    | AHA-2940U2/U2W               | 3     | aic7xxx    | F894ABD641 |
| 9005:0080 | 9005:62a0 | Adaptec    | AIC-7892A U160/m             | 3     | aic7xxx    | 0C6668DEE5 |
| 9005:8017 | 9005:0044 | Adaptec    | ASC-29320ALP U320            | 3     | aic79xx    | 14ACFD829D |
| 1000:000f | 1000:1000 | Broadco... | 53c875                       | 2     | sym53c8xx  | AE45AB5C00 |
| 1000:0030 | 103c:322a | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 2     | mptspi     | C156F0AB27 |
| 1000:0054 | 1028:1f09 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 2     | mptsas     | FF69AE3970 |
| 1000:0056 | 103c:322b | LSI Log... | SAS1064ET PCI-Express Fus... | 2     | mptsas     | 9974950D4A |
| 1000:0056 | 1734:1131 | Broadco... | SAS1064ET PCI-Express Fus... | 2     | mptsas     | 28EB3733CA |
| 1000:0056 | 8086:3486 | Broadco... | SAS1064ET PCI-Express Fus... | 2     | mptsas     | 7E72574FF4 |
| 1000:0058 | 1000:3140 | Broadco... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | 7DE05CDBC3 |
| 1000:0058 | 1014:0394 | LSI Log... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | 5C4A86988B |
| 1000:0058 | 1014:0396 | Broadco... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | E4B76F9137 |
| 1000:0058 | 15d9:0001 | Broadco... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | F645C4227C |
| 1000:0058 | 17aa:101d | Broadco... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | 8ADC2B3A82 |
| 11ab:7042 | 11ab:11ab | Marvell... | 88SX7042 PCI-e 4-port SAT... | 2     | sata_mv    | 40990F73A5 |
| 1b85:1041 | 1b85:1041 | OCZ Tec... | RevoDrive 3 X2 PCI-Expres... | 2     | mvsas      | E0FC243F47 |
| 9005:0010 | 9005:2180 | Adaptec    | AHA-2940U2/U2W               | 2     | aic7xxx    | 67C4745D3A |
| 9005:0080 | 9005:e2a0 | Adaptec    | AIC-7892A U160/m             | 2     | aic7xxx    | 04D9B1D5AC |
| 9005:8012 | 9005:0042 | Adaptec    | ASC-29320 U320               | 2     | aic79xx    | 5923C246C4 |
| 1000:000f | 0e11:7004 | Broadco... | 53c875                       | 1     | sym53c8xx  | AFF808A68F |
| 1000:0030 | 0e11:00f4 | Broadco... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 72330BE67D |
| 1000:0030 | 1014:026c | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 46973B5B05 |
| 1000:0030 | 1014:1000 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 659D759E6D |
| 1000:0030 | 1028:012c | Broadco... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 90378ABAC3 |
| 1000:0030 | 1028:016e | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 76EF1C8CA9 |
| 1000:0030 | 1028:1040 | Broadco... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | D83C8DDEDF |
| 1000:0030 | 103c:3108 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | A2995F5723 |
| 1000:0054 | 1000:30e0 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | E0E805180D |
| 1000:0054 | 103c:3228 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | B4F5FF56BD |
| 1000:0054 | 1734:1082 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | 872AE76863 |
| 1000:0054 | 1734:10b9 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | A0F9679F57 |
| 1000:0054 | 8086:3504 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | A61FFACB08 |
| 1000:0056 | 8086:346c | Broadco... | SAS1064ET PCI-Express Fus... | 1     | mptsas     | 390F15B7F9 |
| 1000:0058 | 1000:3002 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | 1E88FE8CBB |
| 1000:0058 | 1000:30a0 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | E5AEAF13AE |
| 1000:0058 | 1000:3150 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | 8F6E544820 |
| 1000:0058 | 10f1:2918 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | 032066549F |
| 1000:0058 | 1734:115a | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | AD12D1E2B9 |
| 1000:0059 | 1000:3002 | LSI Log... | MegaRAID SAS 8208ELP/8208ELP | 1     | mptsas     | 2985792735 |
| 1000:0059 | 15d9:0006 | Broadco... | MegaRAID SAS 8208ELP/8208ELP | 1     | mptsas     | 8F945E0A15 |
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
| 9004:8078 | 9004:7880 | Adaptec    | AIC-7880U                    | 1     | aic7xxx    | F379321C88 |
| 9004:8278 |           | Adaptec    | AHA-3940U/UW/UWD / AIC-7882U | 1     | aic7xxx    | 3A362598FB |
| 9004:8778 | 9004:7887 | Adaptec    | AHA-2940UW Pro / AIC-788x    | 1     | aic7xxx    | E2380E1CCE |
| 9005:0010 | 9005:a100 | Adaptec    | AHA-2940U2/U2W               | 1     | aic7xxx    | 0A58FAB188 |
| 9005:0011 | 9005:0181 | Adaptec    | AHA-2930U2                   | 1     | aic7xxx    | 86D356F643 |
| 9005:0081 | 9005:62a1 | Adaptec    | AIC-7892B U160/m             | 1     | aic7xxx    | 9854E43724 |
| 9005:00c0 | 9005:f620 | Adaptec    | AHA-3960D / AIC-7899A U160/m | 1     | aic7xxx    | A966231E0C |
| 9005:00cf | 15d9:9005 | Adaptec    | AIC-7899P U160/m             | 1     | aic7xxx    | 34867AD122 |
| 9005:8016 | 9005:0040 | Adaptec    | ASC-39320A U320              | 1     |            | 243DBA3B27 |
| 9005:801d | 10f1:2676 | Adaptec    | AIC-7902B U320               | 1     | aic79xx    | 219383F559 |
| 9005:801f | 8086:341a | Adaptec    | AIC-7902 U320                | 1     | aic79xx    | 37AA8C0E8E |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:d150 |           | Intel      | Core Processor QPI Link      | 567   |            | 9C8826C0D2 |
| 8086:d151 |           | Intel      | Core Processor QPI Routin... | 567   |            | 9C8826C0D2 |
| 8086:d158 |           | Intel      | Core Processor Miscellane... | 535   |            | 9C8826C0D2 |
| 8086:2f6e |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 453   |            | 9D2A807F08 |
| 8086:2f6f |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 453   |            | 9D2A807F08 |
| 8086:2f88 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 453   |            | 9D2A807F08 |
| 8086:2f8a |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 453   |            | 9D2A807F08 |
| 8086:2fae |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 453   |            | 9D2A807F08 |
| 8086:2faf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 453   |            | 9D2A807F08 |
| 8086:2fb8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 453   |            | 9D2A807F08 |
| 8086:2fb9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 453   |            | 9D2A807F08 |
| 8086:2fba |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 453   |            | 9D2A807F08 |
| 8086:2fbb |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 453   |            | 9D2A807F08 |
| 8086:2fbe |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 453   |            | 9D2A807F08 |
| 8086:2fbf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 453   |            | 9D2A807F08 |
| 8086:2ff8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 453   |            | 9D2A807F08 |
| 8086:2ff9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 453   |            | 9D2A807F08 |
| 8086:1911 | 1458:5000 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 412   |            | 8C2B6CF453 |
| 14e4:16be | 1025:0647 | Broadcom   | BCM57765/57785 MS Card Re... | 410   |            | 82E60126C9 |
| 14e4:16bf | 1025:0647 | Broadcom   | BCM57765/57785 xD-Picture... | 410   |            | 82E60126C9 |
| 8086:1513 | 2222:1111 | Intel      | CV82524 Thunderbolt Contr... | 406   | thunder... | 6E17FB6EA4 |
| 8086:2f1d | 8086:2f1d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 398   |            | 9D2A807F08 |
| 8086:2f1e | 8086:2f1e | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 398   |            | 9D2A807F08 |
| 8086:2f1f | 8086:2f1f | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 398   |            | 9D2A807F08 |
| 8086:2f71 | 8086:2f71 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 398   |            | 9D2A807F08 |
| 8086:2f98 | 8086:2f98 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 398   |            | 9D2A807F08 |
| 8086:2f99 | 8086:2f99 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 398   |            | 9D2A807F08 |
| 8086:2f9a | 8086:2f9a | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 398   |            | 9D2A807F08 |
| 8086:2f9c | 8086:2f9c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 398   |            | 9D2A807F08 |
| 8086:2fa0 | 8086:2fa0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 398   | sb_edac    | 9D2A807F08 |
| 8086:2fa8 | 8086:2fa8 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 398   |            | 9D2A807F08 |
| 8086:2faa | 8086:2faa | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 398   |            | 9D2A807F08 |
| 8086:2fab | 8086:2fab | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 398   |            | 9D2A807F08 |
| 8086:2fb0 | 8086:2fb0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 398   | hswep_u... | 9D2A807F08 |
| 8086:2fb1 | 8086:2fb1 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 398   | hswep_u... | 9D2A807F08 |
| 8086:2fb2 | 8086:2fb2 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 398   |            | 9D2A807F08 |
| 8086:2fb3 | 8086:2fb3 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 398   |            | 9D2A807F08 |
| 8086:2fc0 | 8086:2fc0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 398   | hswep_u... | 9D2A807F08 |
| 8086:d156 |           | Intel      | Core Processor Semaphore ... | 379   |            | 9C8826C0D2 |
| 8086:d155 |           | Intel      | Core Processor System Man... | 373   |            | 9C8826C0D2 |
| 8086:d157 |           | Intel      | Core Processor System Con... | 373   |            | 9C8826C0D2 |
| 8086:2f81 | 8086:2f81 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 363   |            | 9D2A807F08 |
| 8086:2fe0 | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 363   |            | 9D2A807F08 |
| 8086:2fe1 | 8086:2fe1 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 363   |            | 9D2A807F08 |
| 8086:2fe2 | 8086:2fe2 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 363   |            | 9D2A807F08 |
| 8086:2fe3 | 8086:2fe3 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 363   |            | 9D2A807F08 |
| 8086:2ffc | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 363   |            | 9D2A807F08 |
| 8086:2ffd | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 363   |            | 9D2A807F08 |
| 8086:2ffe | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 363   |            | 9D2A807F08 |
| 8086:2fbc |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 352   |            | F432BA24E0 |
| 8086:2fbd |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 352   |            | F432BA24E0 |
| 8086:2f68 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 336   |            | 9D2A807F08 |
| 8086:2fd0 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 336   | hswep_u... | 9D2A807F08 |
| 8086:2fe4 | 8086:2fe4 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 320   |            | 9D2A807F08 |
| 8086:2fe5 | 8086:2fe5 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 320   |            | 9D2A807F08 |
| 8086:2fac | 8086:2fac | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 299   |            | 9D2A807F08 |
| 8086:2fad | 8086:2fad | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 299   |            | 9D2A807F08 |
| 8086:2fb4 | 8086:2fb4 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 299   | hswep_u... | 9D2A807F08 |
| 8086:2fb5 | 8086:2fb5 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 299   | hswep_u... | 9D2A807F08 |
| 8086:2fb6 | 8086:2fb6 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 299   |            | 9D2A807F08 |
| 8086:2fb7 | 8086:2fb7 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 299   |            | 9D2A807F08 |
| 1180:e822 | 17aa:2133 | Ricoh      | MMC/SD Host Controller       | 276   | sdhci_pci  | 8B21B7CFFE |
| 8086:2576 |           | Intel      | 82865G/PE/P Processor to ... | 260   |            | 467C3682C1 |
| 8086:2f28 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 245   |            | 9D2A807F08 |
| 8086:2f29 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 245   |            | 9D2A807F08 |
| 8086:2f2a |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 245   |            | 9D2A807F08 |
| 8086:2035 |           | Intel      | Sky Lake-E RAS Configurat... | 239   |            | EACC1E3F66 |
| 197b:2382 | 1043:1a07 | JMicron... | SD/MMC Host Controller       | 235   | sdhci_pci  | D5A8ADB8C9 |
| 8086:2025 |           | Intel      | Sky Lake-E RAS               | 234   |            | EACC1E3F66 |
| 8086:1911 | 8086:2015 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 226   |            | F3E5EBA0C2 |
| 8086:204e | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 222   | skx_uncore | EACC1E3F66 |
| 8086:2018 | 8086:0000 | Intel      | Sky Lake-E M2PCI Registers   | 217   |            | EACC1E3F66 |
| 8086:2040 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 217   |            | EACC1E3F66 |
| 8086:2041 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 217   |            | EACC1E3F66 |
| 8086:2042 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 217   | skx_uncore | EACC1E3F66 |
| 8086:2043 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 217   |            | EACC1E3F66 |
| 8086:2044 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 217   |            | EACC1E3F66 |
| 8086:2045 | 8086:0000 | Intel      | Sky Lake-E LM Channel 1      | 217   |            | EACC1E3F66 |
| 8086:2046 | 8086:0000 | Intel      | Sky Lake-E LMS Channel 1     | 217   | skx_uncore | EACC1E3F66 |
| 8086:2047 | 8086:0000 | Intel      | Sky Lake-E LMDP Channel 1    | 217   |            | EACC1E3F66 |
| 8086:2048 | 8086:0000 | Intel      | Sky Lake-E DECS Channel 2    | 217   |            | EACC1E3F66 |
| 8086:2049 | 8086:0000 | Intel      | Sky Lake-E LM Channel 2      | 217   |            | EACC1E3F66 |
| 8086:204a | 8086:0000 | Intel      | Sky Lake-E LMS Channel 2     | 217   | skx_uncore | EACC1E3F66 |
| 8086:204b | 8086:0000 | Intel      | Sky Lake-E LMDP Channel 2    | 217   |            | EACC1E3F66 |
| 8086:2054 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 217   |            | EACC1E3F66 |
| 8086:2055 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 217   |            | EACC1E3F66 |
| 8086:2056 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 217   |            | EACC1E3F66 |
| 8086:2057 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 217   |            | EACC1E3F66 |
| 8086:2066 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 217   | skx_uncore | EACC1E3F66 |
| 8086:2080 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 217   |            | EACC1E3F66 |
| 8086:2081 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 217   |            | EACC1E3F66 |
| 8086:2082 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 217   |            | EACC1E3F66 |
| 8086:2083 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 217   |            | EACC1E3F66 |
| 8086:2084 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 217   |            | EACC1E3F66 |
| 8086:2085 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 217   |            | EACC1E3F66 |
| 8086:2086 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 217   |            | EACC1E3F66 |
| 8086:208d | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 217   |            | EACC1E3F66 |
| 8086:208e | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 217   |            | EACC1E3F66 |
| 8086:8a17 |           | Intel      | Ice Lake Thunderbolt 3 NH... | 216   | thunder... | 138EC046F1 |
| 14e4:16be | 1025:0504 | Broadcom   | BCM57765/57785 MS Card Re... | 213   |            | F86CA58100 |

### Tv card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 109e:036e |           | Brooktree  | Bt878 Video Capture          | 28    | bttv       | 2B61653CEA |
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
| 14f1:8880 | 0070:6a18 | Conexan... | CX23887/8 PCIe Broadcast ... | 8     | cx23885    | DD6513E107 |
| 14f1:8880 | 0070:6b18 | Conexan... | CX23887/8 PCIe Broadcast ... | 8     | cx23885    | DD6513E107 |
| 14f1:8880 | 0070:c138 | Conexan... | CX23887/8 PCIe Broadcast ... | 8     | cx23885    | D0A1BC0E01 |
| 1131:7133 | 1043:4876 | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | F9BFF20C4D |
| 1131:7133 | 11bd:002e | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 548AFBB702 |
| 1131:7133 | 1461:a11a | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 948B6142EC |
| 1131:7133 | 1461:a14b | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 0F5E8185C5 |
| 1131:7133 | 1461:a836 | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 14C016A2F9 |
| 1131:7133 | 1461:e836 | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 6D72715029 |
| 1131:7133 | 5ace:6193 | Philips... | SAA7131/SAA7133/SAA7135 V... | 7     | saa7134    | 01145B2627 |
| 1131:7134 | 16be:0003 | Philips... | SAA7134/SAA7135HL Video B... | 7     | saa7134    | F5D9A3BA0E |
| 14f1:8800 | 107d:6611 | Conexan... | CX23880/1/2/3 PCI Video a... | 7     | cx8800     | ACE5E495F5 |
| 14f1:8852 | 0070:6a28 | Conexan... | CX23885 PCI Video and Aud... | 7     | cx23885    | 517C6137A3 |
| 14f1:8852 | 0070:6b28 | Conexan... | CX23885 PCI Video and Aud... | 7     | cx23885    | 517C6137A3 |
| 14f1:8852 | 0070:71d3 | Conexan... | CX23885 PCI Video and Aud... | 7     | cx23885    | E7E7F905C7 |
| 14f1:8880 | 1461:d439 | Conexan... | CX23887/8 PCIe Broadcast ... | 7     | cx23885    | D8325626F2 |
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
| 4444:0803 | 0070:4000 | Interne... | iTVC15 (CX23415) Video De... | 6     | ivtv       | AD64896794 |
| 109e:036e | 107d:6606 | Brooktree  | Bt878 Video Capture          | 5     | bttv       | 89FD130FF2 |
| 109e:036e | 11bd:0012 | Brooktree  | Bt878 Video Capture          | 5     | bttv       | 237CA98302 |
| 109e:036e | 1822:0001 | Brooktree  | Bt878 Video Capture          | 5     | bttv       | 39FB7FBFDD |
| 1131:7130 | 0000:4051 | Philips... | SAA7130 Video Broadcast D... | 5     | saa7134    | 1ABE742CC8 |
| 1131:7133 | 0070:6701 | Philips... | SAA7131/SAA7133/SAA7135 V... | 5     | saa7134    | 3CEC37B610 |
| 1131:7133 | 1043:4845 | Philips... | SAA7131/SAA7133/SAA7135 V... | 5     | saa7134    | D288F0A8CD |
| 1131:7133 | 1461:f636 | Philips... | SAA7131/SAA7133/SAA7135 V... | 5     | saa7134    | 4A92B26339 |
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

### Unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:5aa2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 10    | intel_i... | 403E735C43 |
| 8086:31a2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 7     | intel_i... | 1A6758A371 |
| 8086:5aa2 | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 7     | intel_i... | 4FD337BCA7 |
| 8086:31a2 | 17aa:3801 | Intel      | Celeron/Pentium Silver Pr... | 6     | intel_i... | 17E78AF479 |
| 8086:31a2 | 1028:081f | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_i... | D11804DA19 |
| 8086:5aa2 | 1043:1c80 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_i... | 7F25CF70DD |
| 8086:31a2 | 17aa:3806 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_i... | EDA2FBC232 |
| 8086:5aa2 | 103c:82ee | Intel      | Celeron N3350/Pentium N42... | 2     | intel_i... | 90AEEA53CC |
| 8086:5aa2 | 103c:830d | Intel      | Celeron N3350/Pentium N42... | 2     | intel_i... | 27DC03B58E |
| 8086:5aa2 | 1043:1d90 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_i... | C8D3F204E5 |
| 1217:6120 | 0001:0000 | O2 Micro   |                              | 1     |            | B851103D78 |
| 13fe:1716 | 13fe:0001 | Advantech  |                              | 1     |            | 047EAD1D70 |
| 1684:0029 | 0008:0000 |            |                              | 1     |            | 3A2604A18A |
| 8086:1aa2 | 8086:7270 | Intel      | Integrated Sensor Solution   | 1     | intel_i... | 555A26F0D1 |
| 8086:31a2 | 103c:84fa | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_i... | 345648FE18 |
| 8086:31a2 | 103c:85ca | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_i... | 363C54D31F |
| 8086:31a2 | 103c:86cf | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_i... | 33D5688BFC |
| 8086:31a2 | 1043:1182 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_i... | DE1DE1FA76 |
| 8086:5aa2 |           | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | 49D345EC0B |
| 8086:5aa2 | 1028:07b3 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | 0BF27D0F8E |
| 8086:5aa2 | 1043:1930 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | B6FC10EFA8 |
| 8086:5aa2 | 1043:1d60 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | 45B1907784 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:43d5 | 1b21:1142 | AMD        | 400 Series Chipset USB 3.... | 1886  | xhci_hcd   | B2D3620851 |
| 1022:149c | 1022:148c | AMD        | Matisse USB 3.0 Host Cont... | 1476  | xhci_hcd   | 93DE1508CB |
| 1002:4397 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1466  | ohci_pci   | 5E80D808A1 |
| 1002:4399 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1466  | ohci_pci   | 5E80D808A1 |
| 1002:4396 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 1465  | ehci_pci   | 5E80D808A1 |
| 1b21:1042 | 1043:8488 | ASMedia... | ASM1042 SuperSpeed USB Ho... | 1402  | xhci_hcd   | 1BB97BC7DF |
| 1002:4396 | 1002:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 1238  | ehci_pci   | 588CEFB67B |
| 8086:1c26 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1139  | ehci_pci   | 278873FF66 |
| 8086:1c2d | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1139  | ehci_pci   | 278873FF66 |
| 1106:3483 | 1106:3483 | VIA Tec... | VL805/806 xHCI USB 3.0 Co... | 1131  | xhci_hcd   | D4EE4BA59F |
| 8086:27c8 | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 1072  | uhci_hcd   | 4E4E73BA37 |
| 8086:27c9 | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 1072  | uhci_hcd   | 4E4E73BA37 |
| 8086:27ca | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 1071  | uhci_hcd   | 4E4E73BA37 |
| 8086:27cb | 1043:8179 | Intel      | NM10/ICH7 Family USB UHCI... | 1070  | uhci_hcd   | 4E4E73BA37 |
| 8086:27cc | 1043:8179 | Intel      | NM10/ICH7 Family USB2 EHC... | 1056  | ehci_hc... | 4E4E73BA37 |
| 1002:4397 | 1002:4397 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1022  | ohci_pci   | 588CEFB67B |
| 8086:9d2f | 1043:201f | Intel      | Sunrise Point-LP USB 3.0 ... | 945   | xhci_hcd   | 02BA908575 |
| 1022:149c | 1043:87c0 | AMD        | Matisse USB 3.0 Host Cont... | 912   | xhci_hcd   | A525C8911B |
| 8086:8c26 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 905   | ehci_pci   | 735015DCE2 |
| 8086:8c31 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 900   | xhci_hcd   | 735015DCE2 |
| 8086:8c2d | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 894   | ehci_pci   | 735015DCE2 |
| 1002:4399 | 1002:4399 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 885   | ohci_pci   | 588CEFB67B |
| 1002:4396 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 860   | ehci_pci   | 6CA4F46D1B |
| 1002:4397 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 860   | ohci_pci   | 6CA4F46D1B |
| 1002:4398 | 1043:8389 | AMD        | SB7x0 USB OHCI1 Controller   | 858   | ohci_pci   | 6CA4F46D1B |
| 1002:4399 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 858   | ohci_pci   | 6CA4F46D1B |
| 1022:149c | 1022:1486 | AMD        | Matisse USB 3.0 Host Cont... | 841   | xhci_hcd   | 93DE1508CB |
| 8086:27c8 | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 797   | uhci_hcd   | 5AF4FEE0BA |
| 8086:27c9 | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 797   | uhci_hcd   | 5AF4FEE0BA |
| 8086:27ca | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 797   | uhci_hcd   | 5AF4FEE0BA |
| 8086:27cb | 1458:5004 | Intel      | NM10/ICH7 Family USB UHCI... | 797   | uhci_hcd   | 5AF4FEE0BA |
| 8086:27cc | 1458:5006 | Intel      | NM10/ICH7 Family USB2 EHC... | 796   | ehci_pci   | 5AF4FEE0BA |
| 8086:1e26 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 785   | ehci_pci   | 1575E2C682 |
| 8086:1e2d | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 785   | ehci_pci   | 1575E2C682 |
| 1b21:1142 | 1043:85bf | ASMedia... | ASM1042A USB 3.0 Host Con... | 781   | xhci_hcd   | 21C683ED97 |
| 8086:1e31 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 778   | xhci_hcd   | 1575E2C682 |
| 1002:4398 | 1458:5004 | AMD        | SB7x0 USB OHCI1 Controller   | 772   | ohci_pci   | 9CF8898973 |
| 8086:a12f | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 749   | xhci_hcd   | 427C8B8D8F |
| 8086:1c26 | 1458:5006 | Intel      | 6 Series/C200 Series Chip... | 725   | ehci_pci   | 042607D7F1 |
| 8086:1c2d | 1458:5006 | Intel      | 6 Series/C200 Series Chip... | 725   | ehci_pci   | 042607D7F1 |
| 1022:43bb | 1b21:1142 | AMD        | 300 Series Chipset USB 3.... | 719   | xhci_hcd   | 3AB561BBE8 |
| 8086:22b5 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 689   | xhci_hcd   | 2FBF6F153B |
| 8086:3a34 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 665   | uhci_hcd   | 6C7ECC284B |
| 8086:3a35 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 665   | uhci_hcd   | 6C7ECC284B |
| 8086:3a36 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 665   | uhci_hcd   | 6C7ECC284B |
| 8086:3a37 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 665   | uhci_hcd   | 6C7ECC284B |
| 8086:3a38 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 665   | uhci_hcd   | 6C7ECC284B |
| 8086:3a39 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 665   | uhci_hcd   | 6C7ECC284B |
| 8086:3a3c | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 665   | ehci_pci   | 6C7ECC284B |
| 8086:3a3a | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 664   | ehci_pci   | 6C7ECC284B |
| 1022:149c | 1458:5007 | AMD        | Matisse USB 3.0 Host Cont... | 661   | xhci_hcd   | 6B471BC42D |
| 1022:43ee | 1b21:1142 | AMD        | Starship/Matisse USB 3.0 ... | 654   | xhci_hcd   | 82E27C0415 |
| 1022:43bc | 1b21:1142 | AMD        | FCH USB 3.1 XHCI Host Con... | 625   | xhci_hcd   | 24974BE67E |
| 1b21:1242 | 1043:8675 | ASMedia... | ASM1142 USB 3.1 Host Cont... | 614   | xhci_hcd   | 381023907E |
| 8086:1e26 | 1458:5006 | Intel      | 7 Series/C216 Chipset Fam... | 597   | ehci_pci   | BB6DE8B3E0 |
| 8086:1e2d | 1458:5006 | Intel      | 7 Series/C216 Chipset Fam... | 596   | ehci_pci   | BB6DE8B3E0 |
| 8086:8c31 | 1458:5007 | Intel      | 8 Series/C220 Series Chip... | 585   | xhci_hcd   | 3934A7E59D |
| 8086:8c26 | 1458:5006 | Intel      | 8 Series/C220 Series Chip... | 583   | ehci_pci   | 3934A7E59D |
| 8086:8c2d | 1458:5006 | Intel      | 8 Series/C220 Series Chip... | 583   | ehci_pci   | 3934A7E59D |
| 1b6f:7023 | 1458:5007 | Etron T... | EJ168 USB 3.0 Host Contro... | 579   | xhci_hcd   | 61D5F808B5 |
| 8086:1e26 | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 574   | ehci_pci   | 16EBDC4388 |
| 8086:1e2d | 17aa:3977 | Intel      | 7 Series/C216 Chipset Fam... | 574   | ehci_pci   | 16EBDC4388 |
| 1106:3483 | 1458:5007 | VIA Tec... | VL805/806 xHCI USB 3.0 Co... | 564   | xhci_hcd   | C62F9B7A28 |
| 8086:1e31 | 17aa:3977 | Intel      | 7 Series/C210 Series Chip... | 562   | xhci_hcd   | 16EBDC4388 |
| 8086:1e31 | 1458:5007 | Intel      | 7 Series/C210 Series Chip... | 561   | xhci_hcd   | BB6DE8B3E0 |
| 1002:4396 | 1849:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 556   | ehci_pci   | 85B942A5C3 |
| 1002:4397 | 1849:4397 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 556   | ohci_pci   | 85B942A5C3 |
| 1002:4399 | 1849:4399 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 556   | ohci_pci   | 85B942A5C3 |
| 8086:27c8 | 1849:27c8 | Intel      | NM10/ICH7 Family USB UHCI... | 475   | uhci_hcd   | 16C678627E |
| 8086:27c9 | 1849:27c9 | Intel      | NM10/ICH7 Family USB UHCI... | 475   | uhci_hcd   | 16C678627E |
| 8086:27ca | 1849:27ca | Intel      | NM10/ICH7 Family USB UHCI... | 475   | uhci_hcd   | 16C678627E |
| 8086:27cb | 1849:27cb | Intel      | NM10/ICH7 Family USB UHCI... | 475   | uhci_hcd   | 16C678627E |
| 8086:27cc | 1849:27cc | Intel      | NM10/ICH7 Family USB2 EHC... | 474   | ehci_hc... | 16C678627E |
| 1022:7808 | 1458:5004 | AMD        | FCH USB EHCI Controller      | 468   | ehci_pci   | 2BC95C7D30 |
| 8086:9a1b | 2222:1111 | Intel      | Tiger Lake-LP Thunderbolt... | 467   | thunder... | DA5E2F59CC |
| 1022:7807 | 1458:5004 | AMD        | FCH USB OHCI Controller      | 464   | ohci_pci   | 2BC95C7D30 |
| 8086:a2af | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 464   | xhci_hcd   | 381023907E |
| 1022:145f | 1043:8747 | AMD        | Zeppelin USB 3.0 Host con... | 460   | xhci_hcd   | 491D1A96CC |
| 1033:0194 | 1043:8413 | NEC Com... | uPD720200 USB 3.0 Host Co... | 460   | xhci_hcd   | FBCB5D8594 |
| 1106:3038 | 1106:3038 | VIA Tec... | VT82xx/62xx/VX700/8x0/900... | 456   | uhci_hcd   | CB7602A2BD |
| 1022:7809 | 1458:5004 | AMD        | FCH USB OHCI Controller      | 442   | ohci_pci   | 2BC95C7D30 |
| 1106:3104 | 1106:3104 | VIA Tec... | USB 2.0 EHCI-Compliant Ho... | 437   | ehci_pci   | CB7602A2BD |
| 1022:43d0 | 1b21:1142 | AMD        | FCH USB 3.1 XHCI Host Con... | 434   | xhci_hcd   | 93FBAD33CF |
| 8086:a2af | 1458:5007 | Intel      | 200 Series/Z370 Chipset F... | 430   | xhci_hcd   | 8C2B6CF453 |
| 10de:03f1 | 1849:03f1 | Nvidia     | MCP61 USB 1.1 Controller     | 425   | ohci_pci   | 0F23350175 |
| 10de:03f2 | 1849:03f2 | Nvidia     | MCP61 USB 2.0 Controller     | 425   | ehci_pci   | 0F23350175 |
| 8086:a12f | 1458:5007 | Intel      | 100 Series/C230 Series Ch... | 420   | xhci_hcd   | 36BF6DAB37 |
| 1022:43b9 | 1b21:1142 | AMD        | X370 Series Chipset USB 3... | 385   | xhci_hcd   | 3ABF73FB8A |
| 8086:9a13 |           | Intel      | Tiger Lake-LP Thunderbolt... | 385   | xhci_pci   | DA5E2F59CC |
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
| 1022:145c | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 376   | xhci_hcd   | F20F2BFC32 |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8d7c | 1043:8600 | Intel      | C610/X99 series chipset SPSR | 114   |            | D3A4772E4E |
| 8086:8d7c | 8086:7270 | Intel      | C610/X99 series chipset SPSR | 87    |            | 17B2218DAB |
| 8086:8d7c | 1458:7270 | Intel      | C610/X99 series chipset SPSR | 44    |            | 347D6DF600 |
| 8086:8d7c | 1849:8d7c | Intel      | C610/X99 series chipset SPSR | 42    |            | 2BF61F2EC6 |
| 8086:8d7c | 103c:212b | Intel      | C610/X99 series chipset SPSR | 39    |            | 9D2A807F08 |
| 8086:8d7c | 1462:7885 | Intel      | C610/X99 series chipset SPSR | 36    |            | 90189BED4E |
| 10ec:816e | 10ec:8168 | Realtek... | RealManage BMC               | 35    |            | 07A5B3C465 |
| 8086:8d7c | 1028:0617 | Intel      | C610/X99 series chipset SPSR | 34    |            | 6EBA24CF71 |
| 8086:8d7c | 1043:85f6 | Intel      | C610/X99 series chipset SPSR | 22    |            | 2591B8710E |
| 8086:a1ec | 8086:7270 | Intel      | C620 Series Chipset Famil... | 18    |            | AD903545CE |
| 8086:8d7c | 15d9:0821 | Intel      | C610/X99 series chipset SPSR | 17    |            | AAEEE85BE7 |
| 1af2:a001 | 1af2:a001 | AVerMedia  | Live Gamer HD                | 16    |            | 8D2D37223F |
| 8086:a1ec | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    |            | 4391DFF8D2 |
| 8086:a1ed | 8086:7270 | Intel      | C620 Series Chipset Famil... | 14    |            | 0627DB12DF |
| 8086:8d7c | 1028:0618 | Intel      | C610/X99 series chipset SPSR | 13    |            | 0E22588D46 |
| 8086:8d7c | 103c:8030 | Intel      | C610/X99 series chipset SPSR | 12    |            | CFFFE6AA63 |
| 8086:8d7c | 103c:2129 | Intel      | C610/X99 series chipset SPSR | 10    |            | 8DE5BAE655 |
| 8086:a1ec | 1043:871e | Intel      | C620 Series Chipset Famil... | 10    |            | 55BDC0F976 |
| 10ec:5228 | 103c:888a | Realtek... |                              | 9     | rtsx_pci   | ED20604458 |
| 1eac:1001 | 1eac:2001 |            |                              | 9     | mhi_pci... | 11CD74E647 |
| 8086:8d7c | 1028:0619 | Intel      | C610/X99 series chipset SPSR | 9     |            | 36E6C22CC6 |
| 8086:8d7c | 15d9:0857 | Intel      | C610/X99 series chipset SPSR | 9     |            | 6A333A499D |
| 8086:8d7c | 17aa:102f | Intel      | C610/X99 series chipset SPSR | 8     |            | B6ECA9083A |
| 8086:8d7c | 8086:0000 | Intel      | C610/X99 series chipset SPSR | 8     |            | BA0F3C3B41 |
| 8086:a1ec | 1028:073a | Intel      | C620 Series Chipset Famil... | 8     |            | C7D795E2A5 |
| 8086:a1ed | 1028:073a | Intel      | C620 Series Chipset Famil... | 8     |            | C7D795E2A5 |
| 8086:8d7c | 1028:061b | Intel      | C610/X99 series chipset SPSR | 7     |            | BCD33A41F0 |
| 8086:a1ec | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 7     |            | 23D528F392 |
| 8086:a1ec | 1590:00eb | Intel      | C620 Series Chipset Famil... | 7     |            | 7AB4F05613 |
| 8086:a1ec | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     |            | CEE7ED2CE9 |
| 8086:a1ed | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 7     |            | 23D528F392 |
| 8086:a1ed | 1590:00eb | Intel      | C620 Series Chipset Famil... | 7     |            | 7AB4F05613 |
| 1002:6900 | 03ea:1af4 | AMD        | Topaz XT [Radeon R7 M260/... | 6     | amdgpu     | B48E22AF4A |
| 8086:8d7c | 1028:0601 | Intel      | C610/X99 series chipset SPSR | 6     |            | F90168C69D |
| 8086:8d7c | 1028:064c | Intel      | C610/X99 series chipset SPSR | 6     |            | E31C5F36AA |
| 8086:a1ec | 1028:0739 | Intel      | C620 Series Chipset Famil... | 6     |            | 9E01FD5E8C |
| 8086:a1ed | 1028:0739 | Intel      | C620 Series Chipset Famil... | 6     |            | 9E01FD5E8C |
| 8086:6ff2 | 8086:6ff2 | Intel      | Broadwell-E CBo Unicast R... | 5     |            | 3DB5DD7EA0 |
| 8086:6ff3 | 8086:6ff3 | Intel      | Broadwell-E CBo Unicast R... | 5     |            | 3DB5DD7EA0 |
| 8086:8d7c | 103c:212a | Intel      | C610/X99 series chipset SPSR | 5     |            | 7F51E384F7 |
| 8086:8d7c | 15d9:0831 | Intel      | C610/X99 series chipset SPSR | 5     |            | 64918C950D |
| 8086:8d7c | 15d9:0836 | Intel      | C610/X99 series chipset SPSR | 5     |            | 078AB4C114 |
| 8086:8d7c | 1734:1201 | Intel      | C610/X99 series chipset SPSR | 5     |            | 081130AC6F |
| 8086:a1ec | 15d9:096d | Intel      | C620 Series Chipset Famil... | 5     |            | C8195297A4 |
| 8086:a1ec | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 5     |            | 5E1947B31A |
| 8086:a1ec | 1849:a1ec | Intel      | C620 Series Chipset Famil... | 5     |            | 2244EB7809 |
| 8086:a1ed | 15d9:096d | Intel      | C620 Series Chipset Famil... | 5     |            | C8195297A4 |
| 8086:a1ed | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 5     |            | 5E1947B31A |
| 8086:a1ed | 1849:a1ed | Intel      | C620 Series Chipset Famil... | 5     |            | 2244EB7809 |
| 106b:003b |           | Apple      | UniNorth/Intrepid ATA/100    | 4     | pata_pc... | 711599EA49 |
| 106b:003e |           | Apple      | KeyLargo/Intrepid Mac I/O    | 4     | macio      | 711599EA49 |
| 8086:8d7c | 15d9:0834 | Intel      | C610/X99 series chipset SPSR | 4     |            | 72BAE0BDE8 |
| 8086:a1ec | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     |            | E9A1FC86F9 |
| 8086:a1ec | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 4     |            | 7AD1F5EB4E |
| 8086:a1ec | 8086:0000 | Intel      | C620 Series Chipset Famil... | 4     |            | 36C4ACAC2D |
| 8086:a1ed | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 4     |            | 7AD1F5EB4E |
| 8086:a1ed | 8086:35ce | Intel      | C620 Series Chipset Famil... | 4     |            | 36C4ACAC2D |
| 1912:001b | 1d49:0a02 | Renesas... | SH7758 PCIe End-Point [PBI]  | 3     |            | 3510DD7B10 |
| 1971:0000 | 105b:0003 | AGEIA T... | AGEIA PhysX 100 PCIe Card    | 3     |            | 5C4A880D42 |
| 8086:6ff4 | 8086:6ff4 | Intel      | Broadwell-E CBo Unicast R... | 3     |            | D6444EBF26 |
| 8086:6ff5 | 8086:6ff5 | Intel      | Broadwell-E CBo Unicast R... | 3     |            | D6444EBF26 |
| 8086:8d7c | 1028:0600 | Intel      | C610/X99 series chipset SPSR | 3     |            | A98D12AD3E |
| 8086:8d7c | 1028:0627 | Intel      | C610/X99 series chipset SPSR | 3     |            | C7B39E92CA |
| 8086:8d7c | 1028:0639 | Intel      | C610/X99 series chipset SPSR | 3     |            | E5766C8331 |
| 8086:8d7c | 1458:1000 | Intel      | C610/X99 series chipset SPSR | 3     |            | 2F69A2F89C |
| 8086:8d7c | 1462:7883 | Intel      | C610/X99 series chipset SPSR | 3     |            | 64A313C9E3 |
| 8086:8d7c | 1462:7a20 | Intel      | C610/X99 series chipset SPSR | 3     |            | B5DCAF3853 |
| 8086:8d7c | 15d9:0844 | Intel      | C610/X99 series chipset SPSR | 3     |            | 57BA944640 |
| 8086:8d7c | 15d9:0852 | Intel      | C610/X99 series chipset SPSR | 3     |            | 9EFBA142DD |
| 8086:8d7c | 1d49:0a00 | Intel      | C610/X99 series chipset SPSR | 3     |            | 3510DD7B10 |
| 8086:a1ec | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | E752263E49 |
| 8086:a1ec | 103c:81c6 | Intel      | C620 Series Chipset Famil... | 3     |            | 679871CFEC |
| 8086:a1ec | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     |            | C682299C13 |
| 8086:a1ec | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     |            | 5658A2FB98 |
| 8086:a1ed | 103c:81c6 | Intel      | C620 Series Chipset Famil... | 3     |            | 679871CFEC |
| 8086:a1ed | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     |            | C682299C13 |
| 8086:a1ed | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     |            | 5658A2FB98 |
| 1002:694e | 1002:694e | AMD        | Polaris 22 XL [Radeon RX ... | 2     | amdgpu     | 07A9851CD6 |
| 106b:0022 |           | Apple      | KeyLargo Mac I/O             | 2     | macio      | 23A8F5BBFB |
| 10de:0e1b | 0043:0000 | Nvidia     | GK107 HDMI Audio Controller  | 2     | snd_hda... | 17B6106770 |
| 10de:1f91 | 103c:8601 | Nvidia     | TU117M [GeForce GTX 1650 ... | 2     | nouveau    | 332EEAE951 |
| 10ec:5228 | 103c:88b5 | Realtek... |                              | 2     | rtsx_pci   | 12EBE0B845 |
| 10ec:5261 | 1462:12fb | Realtek... | PCIe Card Reader             | 2     | rtsx_pci   | CBF3C67BE2 |
| 10ec:5261 | 1462:1305 | Realtek... | PCIe Card Reader             | 2     | rtsx_pci   | D9BC3D0B56 |
| 1274:5880 | ffff:ffff | Ensoniq    | 5880B / Creative Labs CT5880 | 2     | snd_ens... | CC0925A796 |
| 8086:3591 | 1028:0173 | Intel      | E7525/E7520 Error Reporti... | 2     |            | CB7602A2BD |
| 8086:3591 | 1043:8145 | Intel      | E7525/E7520 Error Reporti... | 2     |            | C6EF12178F |
| 8086:8d7c | 1028:063a | Intel      | C610/X99 series chipset SPSR | 2     |            | E4DEE6FAF7 |
| 8086:8d7c | 1028:063b | Intel      | C610/X99 series chipset SPSR | 2     |            | DF26C4E8C4 |
| 8086:8d7c | 1462:7a21 | Intel      | C610/X99 series chipset SPSR | 2     |            | 6FAF6514F5 |
| 8086:8d7c | 1462:7a54 | Intel      | C610/X99 series chipset SPSR | 2     |            | 8A1C74B101 |
| 8086:8d7c | 15d9:0824 | Intel      | C610/X99 series chipset SPSR | 2     |            | 6C96E4A591 |
| 8086:8d7c | 15d9:0833 | Intel      | C610/X99 series chipset SPSR | 2     |            | 115F0BC999 |
| 8086:8d7c | 15d9:0860 | Intel      | C610/X99 series chipset SPSR | 2     |            | CC00646768 |
| 8086:8d7c | 17aa:1030 | Intel      | C610/X99 series chipset SPSR | 2     |            | A06764AF07 |
| 8086:a1ec | 1028:0718 | Intel      | C620 Series Chipset Famil... | 2     |            | 1CCB5D67C2 |
| 8086:a1ec | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     |            | DF9A63BE43 |
| 8086:a1ec | 1028:07cb | Intel      | C620 Series Chipset Famil... | 2     |            | FE43558C7A |
| 8086:a1ec | 1028:07e5 | Intel      | C620 Series Chipset Famil... | 2     |            | 4C88B2E09B |
| 8086:a1ec | 15d9:091c | Intel      | C620 Series Chipset Famil... | 2     |            | 748FB8054B |

