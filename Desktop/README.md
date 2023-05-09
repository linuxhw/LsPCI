Most popular PCI devices in Desktops
------------------------------------

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
   * [ Dma controller (8237) ](#dma-controller-8237-pci)
   * [ Dma controller (eisa dma) ](#dma-controller-eisa-dma-pci)
   * [ Docking station ](#docking-station-pci)
   * [ Dpio module ](#dpio-module-pci)
   * [ Dvb card ](#dvb-card-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Entertainment encryption device ](#entertainment-encryption-device-pci)
   * [ Ethernet controller ](#ethernet-controller-pci)
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
   * [ Network and computing encryption device ](#network-and-computing-encryption-device-pci)
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
   * [ Ssa ](#ssa-pci)
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

Count  - number of computers with this device installed,
Driver - driver in use for this device,
Probe  - latest probe ID of this device.

### Access bus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1106:303a | 1106:3038 | VIA Technologies | ACCESS Bus                           | 1     |            | [C9A1706533](<Desktop/ASUSTek Computer/M4A88TD-V/M4A88TD-V EVO-USB3/CF1A7A010A44/ROSA-2016.1/4.9.155-NRJ-DESKTOP-1ROSA-X86_64/X86_64/C9A1706533>) |

### Bluetooth (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1814:3298 | 103c:18ec | Ralink           | RT3290 Bluetooth                     | 27    | rtbt       | [DBA335076C](<Desktop/Hewlett-Packard/500/500-056/E2533044BC09/LINUXMINT-21.1/5.15.0-58-GENERIC/X86_64/DBA335076C>) |
| 1814:3298 | 1a3b:2787 | Ralink           | RT3290 Bluetooth                     | 5     |            | [1FBEA29754](<Desktop/Intel/Tiger/Tiger Hill/939EBA8DDE94/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/1FBEA29754>) |
| 1814:3298 | 1a3b:2987 | Ralink           | RT3290 Bluetooth                     | 3     |            | [2FDC29D4FD](<Desktop/ZOTAC/H77/H77ITX-A-E/6BC1D4A5693B/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/2FDC29D4FD>) |
| 1814:3298 | 1a3b:2f87 | Ralink           | RT3290 Bluetooth                     | 2     |            | [0D7E8C7568](<Desktop/AIO/H61/H61H-G11/80341B910781/ROSA-12.2/5.10.71-GENERIC-1ROSA2021.1-X86_64/X86_64/0D7E8C7568>) |
| 1814:3298 | 103c:191c | Ralink           | RT3290 Bluetooth                     | 1     |            | [3CF5084317](<Desktop/Huanan/X99-F8/X99-F8 GAMING V5.0/D435EDE9327F/KUBUNTU-20.10/5.10.4-XANMOD1-CACULE/X86_64/3CF5084317>) |
| 1814:3298 | 1814:3298 | Ralink           | RT3290 Bluetooth                     | 1     |            | [EF1E6295A8](<Desktop/Others/Pine/Pine Trail - M CRB/29B2E182872A/UBUNTU-19.10/5.3.0-19-GENERIC/X86_64/EF1E6295A8>) |

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1002:4384 |           | AMD              | SBx00 PCI to PCI Bridge              | 7264  |            | [8E4CBC4837](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer/5EE6E0F2768B/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/8E4CBC4837>) |
| 1022:1482 |           | AMD              | Starship/Matisse PCIe Dummy Host ... | 6231  | vfio_pci   | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 1022:1452 |           | AMD              | Family 17h (Models 00h-1fh) PCIe ... | 6057  |            | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 1022:1440 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 6034  |            | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 1022:1441 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 6034  |            | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 1022:1442 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 6034  |            | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 1022:1443 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 6034  | k10temp    | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 1022:1444 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 6034  |            | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 1022:1445 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 6034  |            | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 1022:1446 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 6034  |            | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 1022:1447 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 6034  |            | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 1022:1200 |           | AMD              | Family 10h Processor HyperTranspo... | 4776  |            | [FB7920C5F9](<Desktop/ASUSTek Computer/M3N/M3N WS/208D21EEB6BD/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/FB7920C5F9>) |
| 1022:1201 |           | AMD              | Family 10h Processor Address Map     | 4776  |            | [FB7920C5F9](<Desktop/ASUSTek Computer/M3N/M3N WS/208D21EEB6BD/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/FB7920C5F9>) |
| 1022:1202 |           | AMD              | Family 10h Processor DRAM Controller | 4776  | amd64_e... | [FB7920C5F9](<Desktop/ASUSTek Computer/M3N/M3N WS/208D21EEB6BD/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/FB7920C5F9>) |
| 1022:1203 |           | AMD              | Family 10h Processor Miscellaneou... | 4776  | k10temp    | [FB7920C5F9](<Desktop/ASUSTek Computer/M3N/M3N WS/208D21EEB6BD/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/FB7920C5F9>) |
| 1022:1204 |           | AMD              | Family 10h Processor Link Control    | 4776  |            | [FB7920C5F9](<Desktop/ASUSTek Computer/M3N/M3N WS/208D21EEB6BD/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/FB7920C5F9>) |
| 1022:43c7 | 1b21:3306 | AMD              | 400 Series Chipset PCIe Port         | 4537  | pcieport   | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 1022:43c6 | 1b21:0201 | AMD              | 400 Series Chipset PCIe Bridge       | 4183  | pcieport   | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 1022:1460 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 4068  |            | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 1022:1461 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 4068  |            | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 1022:1462 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 4068  |            | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 1022:1463 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 4068  | k10temp    | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 1022:1464 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 4068  |            | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 1022:1465 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 4068  |            | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 1022:1466 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 4068  |            | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 1022:1467 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 4068  |            | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 1022:1484 | 1022:1484 | AMD              | Starship/Matisse Internal PCIe GP... | 3910  | pcieport   | [53D91DCA3C](<Desktop/ASRock/B450M/B450M Steel Legend/57EFD5B4322B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/53D91DCA3C>) |
| 1022:1600 |           | AMD              | Family 15h Processor Function 0      | 3346  |            | [ACF61A6132](<Desktop/Gigabyte Technology/970/970A-DS3P/4209CEC662D2/OPENMANDRIVA-23.03/6.2.10-DESKTOP-2.0OMV4.9MJN/X86_64/ACF61A6132>) |
| 1022:1601 |           | AMD              | Family 15h Processor Function 1      | 3346  |            | [ACF61A6132](<Desktop/Gigabyte Technology/970/970A-DS3P/4209CEC662D2/OPENMANDRIVA-23.03/6.2.10-DESKTOP-2.0OMV4.9MJN/X86_64/ACF61A6132>) |
| 1022:1602 |           | AMD              | Family 15h Processor Function 2      | 3346  |            | [ACF61A6132](<Desktop/Gigabyte Technology/970/970A-DS3P/4209CEC662D2/OPENMANDRIVA-23.03/6.2.10-DESKTOP-2.0OMV4.9MJN/X86_64/ACF61A6132>) |
| 1022:1603 |           | AMD              | Family 15h Processor Function 3      | 3346  | k10temp    | [ACF61A6132](<Desktop/Gigabyte Technology/970/970A-DS3P/4209CEC662D2/OPENMANDRIVA-23.03/6.2.10-DESKTOP-2.0OMV4.9MJN/X86_64/ACF61A6132>) |
| 1022:1604 |           | AMD              | Family 15h Processor Function 4      | 3346  | fam15h_... | [ACF61A6132](<Desktop/Gigabyte Technology/970/970A-DS3P/4209CEC662D2/OPENMANDRIVA-23.03/6.2.10-DESKTOP-2.0OMV4.9MJN/X86_64/ACF61A6132>) |
| 1022:1605 |           | AMD              | Family 15h Processor Function 5      | 3346  |            | [ACF61A6132](<Desktop/Gigabyte Technology/970/970A-DS3P/4209CEC662D2/OPENMANDRIVA-23.03/6.2.10-DESKTOP-2.0OMV4.9MJN/X86_64/ACF61A6132>) |
| 1022:43b4 | 1b21:3306 | AMD              | 300 Series Chipset PCIe Port         | 3268  | pcieport   | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 1022:790e | 1458:5001 | AMD              | FCH LPC Bridge                       | 3224  |            | [E6EAD6E953](<Desktop/Gigabyte Technology/B450/B450 AORUS ELITE/9C8C09595939/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/E6EAD6E953>) |
| 1002:439d | 1002:439d | AMD              | SB7x0/SB8x0/SB9x0 LPC host contro... | 3122  |            | [ACF61A6132](<Desktop/Gigabyte Technology/970/970A-DS3P/4209CEC662D2/OPENMANDRIVA-23.03/6.2.10-DESKTOP-2.0OMV4.9MJN/X86_64/ACF61A6132>) |
| 1022:57ad |           | AMD              | Matisse Switch Upstream              | 2822  | pcieport   | [4E424E0AD2](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/2E14927B3139/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/4E424E0AD2>) |
| 1022:1454 | 1022:1454 | AMD              | Family 17h (Models 00h-0fh) Inter... | 2793  | pcieport   | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 1022:780f |           | AMD              | FCH PCI Bridge                       | 2559  |            | [97986B63AD](<Desktop/Gigabyte Technology/F2/F2A68HM-H/458432F727D5/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/97986B63AD>) |
| 1002:1478 |           | AMD              | Navi 10 XL Upstream Port of PCI E... | 2503  | pcieport   | [53D91DCA3C](<Desktop/ASRock/B450M/B450M Steel Legend/57EFD5B4322B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/53D91DCA3C>) |
| 1002:1479 | 1002:1479 | AMD              | Navi 10 XL Downstream Port of PCI... | 2502  | pcieport   | [53D91DCA3C](<Desktop/ASRock/B450M/B450M Steel Legend/57EFD5B4322B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/53D91DCA3C>) |
| 1022:1483 | 1022:1453 | AMD              | Starship/Matisse GPP Bridge          | 2360  | pcieport   | [19C318242F](<Desktop/Others/Others/Others/C3C1AB1B873D/UBUNTU-20.04/5.15.0-1023-NVIDIA/X86_64/19C318242F>) |
| 1022:43ea | 1b21:3308 | AMD              | FCH PCIe Switch Downstream Port      | 2306  | pcieport   | [DC43E4A7E3](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PRO/1FF7B8E0562A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/DC43E4A7E3>) |
| 1022:43e9 | 1b21:0201 | AMD              | 500 Series Chipset Switch Upstrea... | 2303  | pcieport   | [DC43E4A7E3](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PRO/1FF7B8E0562A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/DC43E4A7E3>) |
| 1022:1453 | 1022:1453 | AMD              | Family 17h (Models 00h-0fh) PCIe ... | 2298  | pcieport   | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 1b21:1080 | 1043:8489 | ASMedia Techn... | ASM1083/1085 PCIe to PCI Bridge      | 2264  | shpchp     | [386D7C9DE4](<Desktop/ASUSTek Computer/P8/P8P67-M/D3654512534B/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/386D7C9DE4>) |
| 8086:244e | 1458:5000 | Intel            | 82801 PCI Bridge                     | 2141  |            | [E7B77F5CF0](<Desktop/Gigabyte Technology/Z68/Z68MA-D2H-B3/99DA8E367A7A/OPENMANDRIVA-23.03/5.16.13-DESKTOP-1OMV4003/X86_64/E7B77F5CF0>) |
| 8086:1901 | 1043:8694 | Intel            | 6th-10th Gen Core Processor PCIe ... | 2081  | pcieport   | [BBFD29FB88](<Desktop/ASUSTek Computer/D320/D320SF/A7E6ADB389B1/UBUNTU-20.04/5.4.0-148-GENERIC/X86_64/BBFD29FB88>) |
| 1022:790e | 1043:87c0 | AMD              | FCH LPC Bridge                       | 2065  |            | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 1022:1100 |           | AMD              | K8 [Athlon64/Opteron] HyperTransp... | 2032  |            | [EB257B146F](<Desktop/Hewlett-Packard/Compaq/Compaq dc5750 Small Form Factor/B641F6E550EF/UBUNTU-20.04/5.15.0-59-GENERIC/X86_64/EB257B146F>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:522a | 1458:1000 | Realtek Semic... | RTS522A PCI Express Card Reader      | 37    | rtsx_pci   | [5356D2A0EF](<Desktop/Gigabyte Technology/GB-BACE/GB-BACE-3160/50364049E8CE/UBUNTU-20.04/5.4.0-144-GENERIC/X86_64/5356D2A0EF>) |
| 10ec:5209 | 103c:2ac3 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 21    | rtsx_pci   | [3CFB7D9E7C](<Desktop/Hewlett-Packard/420/420-1010br/B5181DB91459/FEDORA-37/6.0.11-300.FC37.X86_64/X86_64/3CFB7D9E7C>) |
| 10ec:525a | 10ec:525a | Realtek Semic... | RTS525A PCI Express Card Reader      | 20    | rtsx_pci   | [E0A30BF441](<Desktop/Dell/XPS/XPS 8960/09303F92F8F5/DEBIAN-11/5.10.0-21-AMD64/X86_64/E0A30BF441>) |
| 10ec:525a | 1028:07ee | Realtek Semic... | RTS525A PCI Express Card Reader      | 19    | rtsx_pci   | [E6F49BBE8A](<Desktop/Dell/Inspiron/Inspiron 5675/3F0EB1245B68/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/E6F49BBE8A>) |
| 10ec:5209 | 103c:2adc | Realtek Semic... | RTS5209 PCI Express Card Reader      | 15    | rtsx_pci   | [1326AD508E](<Desktop/Hewlett-Packard/23/23-d018d/4F01668247B3/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/1326AD508E>) |
| 10ec:5229 | 103c:2b38 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 15    | rtsx_pci   | [BF99202E8B](<Desktop/Hewlett-Packard/200/200-010/D6D0FF95D912/DEBIAN-11/5.10.0-22-AMD64/X86_64/BF99202E8B>) |
| 10ec:5209 | 103c:2af0 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 11    | rtsx_pci   | [77768FEFF6](<Desktop/Hewlett-Packard/20/20-b010/1C4E78DFAB8F/XERO-ROLLING/5.19.9-ARCH1-1/X86_64/77768FEFF6>) |
| 10ec:5289 | 10ec:5289 | Realtek Semic... | RTL8411 PCI Express Card Reader      | 11    | rtsx_pci   | [137FDA9BC6](<Desktop/Shuttle/XS35/XS35V4/A86A56720C78/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/137FDA9BC6>) |
| 10ec:5229 | 17aa:366b | Realtek Semic... | RTS5229 PCI Express Card Reader      | 10    | rtsx_pci   | [7028629B85](<Desktop/Lenovo/IdeaCenter/IdeaCenter Q190 10115/7ADC6EEE8CF0/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/7028629B85>) |
| 10ec:525a | 1734:122e | Realtek Semic... | RTS525A PCI Express Card Reader      | 10    | rtsx_pci   | [F20338E169](<Desktop/Fujitsu/CELSIUS/CELSIUS M770/97AA6CA11B9F/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/F20338E169>) |
| 10ec:5209 | 103c:2ac5 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 7     | rtsx_pci   | [7F253A82DC](<Desktop/Hewlett-Packard/120/120-1104er/582FF8EF063D/RED-OS-7.3/6.1.11-1.EL7.3.X86_64/X86_64/7F253A82DC>) |
| 10ec:5209 | 103c:3399 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 7     | rtsx_pci   | [BCE6DF1FFB](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 All-in-One PC/7E81C8391F51/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/BCE6DF1FFB>) |
| 10ec:5229 | 103c:2179 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 7     | rtsx_pci   | [AD75CC2104](<Desktop/Hewlett-Packard/ProOne/ProOne 400 G1 AiO/20B3908EBBFE/ENDEAVOUROS-ROLLING/6.1.4-ARCH1-1/X86_64/AD75CC2104>) |
| 10ec:5229 | 103c:2b43 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 7     | rtsx_pci   | [AA5FB69F7E](<Desktop/Hewlett-Packard/23/23-q101ur/1FBE26C849CE/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/AA5FB69F7E>) |
| 10ec:5249 | 103c:18e6 | Realtek Semic... | RTS5249 PCI Express Card Reader      | 7     | rtsx_pci   | [A406DC2463](<Desktop/Hewlett-Packard/EliteOne/EliteOne 800 G1 Touch AiO/060266EE9A82/DEBIAN-11/6.0.0-0.DEB11.6-AMD64/X86_64/A406DC2463>) |
| 10ec:5229 | 1025:1073 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 6     | rtsx_pci   | [0D7671EF18](<Desktop/Acer/Revo/Revo M1-601/E1DB4422DEC6/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/0D7671EF18>) |
| 10ec:525a | 1028:0a9f | Realtek Semic... | RTS525A PCI Express Card Reader      | 6     | rtsx_pci   | [A8E8000610](<Desktop/Dell/Precision/Precision 3660/1F97B971E059/DEBIAN-11/6.1.0-0.DEB11.6-AMD64/X86_64/A8E8000610>) |
| 10ec:5229 | 103c:2afa | Realtek Semic... | RTS5229 PCI Express Card Reader      | 5     | rtsx_pci   | [D177838277](<Desktop/Hewlett-Packard/23/23-m202eg/CD6424CDF4E4/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D177838277>) |
| 10ec:522a | 10ec:522a | Realtek Semic... | RTS522A PCI Express Card Reader      | 5     | rtsx_pci   | [5E52F1B520](<Desktop/ASRock/FP6/FP6D4-P1/9EA5B1FFFE39/ZORIN-16/5.15.0-53-GENERIC/X86_64/5E52F1B520>) |
| 1aea:6621 | 1aea:6621 | Alcor Micro      | AU6621 PCI-E Flash card reader co... | 5     | alcor_pci  | [28FC5F92BC](<Desktop/Gigabyte Technology/Z170/Z170X-GamingG1/17EEA57D76DF/UBUNTU-22.04/5.15.0-25-GENERIC/X86_64/28FC5F92BC>) |
| 10ec:5209 | 103c:2aee | Realtek Semic... | RTS5209 PCI Express Card Reader      | 4     | rtsx_pci   | [1C59133176](<Desktop/Hewlett-Packard/23/23-b022a/A4BE5C787CFD/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/1C59133176>) |
| 10ec:5229 | 103c:2af8 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx_pci   | [54BF4B18BA](<Desktop/Hewlett-Packard/23/23-f213w/CE08BE1652CE/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/54BF4B18BA>) |
| 10ec:5229 | 103c:2af9 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx_pci   | [005B85E6BB](<Desktop/Hewlett-Packard/23/23-f391la/33F639FAA6FA/LINUXMINT-20.3/5.4.0-117-GENERIC/X86_64/005B85E6BB>) |
| 10ec:5229 | 1b0a:016c | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx_pci   | [0DF79259C1](<Desktop/Pegatron/NM70/NM70-P1-ODM/7722D432045A/ROSA-2016.1/4.9.124-NRJ-DESKTOP-1ROSA-X86_64/X86_64/0DF79259C1>) |
| 10ec:5209 | 1025:8020 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 3     | rtsx_pci   | [BEB207E679](<Desktop/Acer/Revo/Revo 70/BDADC17DFF32/DEBIAN-11/5.10.0-7-AMD64/X86_64/BEB207E679>) |
| 10ec:5209 | 103c:2aed | Realtek Semic... | RTS5209 PCI Express Card Reader      | 3     | rtsx_pci   | [8EDD69E862](<Desktop/Hewlett-Packard/23/23-1015/F4165B477CA5/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/8EDD69E862>) |
| 10ec:5209 | 17aa:3623 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 3     | rtsx_pci   | [E5E08BD1ED](<Desktop/Lenovo/IdeaCentre/IdeaCentre B320/33939298A5DF/UBUNTU-18.04/4.15.0-136-LOWLATENCY/X86_64/E5E08BD1ED>) |
| 10ec:5229 | 1025:0946 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [D99B7CB71E](<Desktop/Acer/Revo/Revo One RL85/E995154D3FBA/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D99B7CB71E>) |
| 10ec:5229 | 103c:2b0b | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [58CDA381E2](<Desktop/Hewlett-Packard/23/23-h024/EF34EC1B0440/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/58CDA381E2>) |
| 10ec:5229 | 103c:2b15 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [CA58E13D8F](<Desktop/Hewlett-Packard/19/19-2113w/665DE0283B82/ZORIN-16/5.13.0-28-GENERIC/X86_64/CA58E13D8F>) |
| 10ec:5229 | 103c:2b3c | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [5E60EFC4A4](<Desktop/Hewlett-Packard/20/20-r124d/6F9AF45F4754/CENTOS-8/4.18.0-305.12.1.EL8_4.X86_64/X86_64/5E60EFC4A4>) |
| 10ec:5249 | 103c:18e8 | Realtek Semic... | RTS5249 PCI Express Card Reader      | 3     | rtsx_pci   | [BF7C3C9080](<Desktop/Hewlett-Packard/ProOne/ProOne 600 G1 AiO/B74EA484FA69/ARCO-ROLLING/6.2.6-ZEN1-1-ZEN/X86_64/BF7C3C9080>) |
| 10ec:525a | 1028:085a | Realtek Semic... | RTS525A PCI Express Card Reader      | 3     | rtsx_pci   | [171959AC44](<Desktop/Dell/OptiPlex/OptiPlex 7060/E3FEF02964B7/FEDORA-37/6.1.12-200.FC37.X86_64/X86_64/171959AC44>) |
| 10ec:525a | 1734:1249 | Realtek Semic... | RTS525A PCI Express Card Reader      | 3     | rtsx_pci   | [756ECCB961](<Desktop/Fujitsu/CELSIUS/CELSIUS W580/0EA48F919DB1/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/756ECCB961>) |
| 10ec:5209 | 103c:2ac7 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 2     | rtsx_pci   | [3505FADB68](<Desktop/Hewlett-Packard/120/120-1134la/A71A532D6042/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/3505FADB68>) |
| 10ec:5209 | 103c:2ae9 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 2     | rtsx_pci   | [2F1276F263](<Desktop/Hewlett-Packard/120/120-1136/2FBEA2509EA6/LINUXMINT-19.3/5.4.0-37-GENERIC/X86_64/2F1276F263>) |
| 10ec:5209 | 103c:2af5 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 2     | rtsx_pci   | [EF6CD0EBCE](<Desktop/Quanta/2AF5/2AF5 011/4AC455A1BD5F/UBUNTU-22.10/5.19.0-31-GENERIC/X86_64/EF6CD0EBCE>) |
| 10ec:5229 | 103c:18ea | Realtek Semic... | RTS5229 PCI Express Card Reader      | 2     | rtsx_pci   | [FFBC26C0F1](<Desktop/Hewlett-Packard/ProOne/ProOne 400 G1 AiO/950E0229189F/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/FFBC26C0F1>) |
| 10ec:5229 | 103c:2b2b | Realtek Semic... | RTS5229 PCI Express Card Reader      | 2     | rtsx_pci   | [14CEFCF857](<Desktop/Hewlett-Packard/23/23-k300np/DF383D406EBE/UBUNTU-22.04/5.15.0-41-GENERIC/X86_64/14CEFCF857>) |
| 10ec:5229 | 10ec:5229 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 2     | rtsx_pci   | [89FF2D84F4](<Desktop/Others/Rev/Rev.00/49135B197DD3/ZORIN-16/5.15.0-67-GENERIC/X86_64/89FF2D84F4>) |
| 10ec:525a | 1028:07a1 | Realtek Semic... | RTS525A PCI Express Card Reader      | 2     | rtsx_pci   | [8FAD928E72](<Desktop/Dell/OptiPlex/OptiPlex 7050/41901DA4F90D/XUBUNTU-22.10/5.19.0-23-GENERIC/X86_64/8FAD928E72>) |
| 10ec:525a | 1028:09a4 | Realtek Semic... | RTS525A PCI Express Card Reader      | 2     | rtsx_pci   | [73E69DEBD9](<Desktop/Dell/OptiPlex/OptiPlex 7080/C00E5FD4B78E/FEDORA-36/5.19.11-200.FC36.X86_64/X86_64/73E69DEBD9>) |
| 10ec:525a | 1028:09aa | Realtek Semic... | RTS525A PCI Express Card Reader      | 2     | rtsx_pci   | [6E4A864CEA](<Desktop/Dell/Precision/Precision 3440/B33B2B94FB2C/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/6E4A864CEA>) |
| 10ec:5209 | 103c:2b02 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 1     | rtsx_pci   | [D7C68E4767](<Desktop/Hewlett-Packard/23/23-b231/A14699E0FA5F/LINUXMINT-20.3/5.4.0-113-GENERIC/X86_64/D7C68E4767>) |
| 10ec:5209 | 10cf:15e0 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 1     | rtsx_pci   | [15202A6CAE](<Desktop/Fujitsu/FMVF56/FMVF56GDR/9836C4851E4C/UBUNTU-20.04/5.4.0-37-GENERIC/X86_64/15202A6CAE>) |
| 10ec:5209 | 17aa:3620 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 1     | rtsx_pci   | [0C3E26BCE7](<Desktop/Lenovo/IdeaCentre/IdeaCentre B520 7745/5AE10D02FDBB/ROSA-2014.1/4.1.16-NRJ-DESKTOP-1ROSA-X86_64/X86_64/0C3E26BCE7>) |
| 10ec:5209 | 1b0a:015e | Realtek Semic... | RTS5209 PCI Express Card Reader      | 1     | rtsx_pci   | [EA65434637](<Desktop/Pegatron/IPPCR-DB/IPPCR-DB/D08E18A2D081/ROSA-2016.1/4.9.155-NRJ-DESKTOP-1ROSA-X86_64/X86_64/EA65434637>) |
| 10ec:5229 | 103c:2af6 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 1     | rtsx_pci   | [824A23BF00](<Desktop/Hewlett-Packard/23/23-a300a/7B1180C4ABDE/UBUNTU-20.04/5.8.0-53-GENERIC/X86_64/824A23BF00>) |
| 10ec:5229 | 103c:2b09 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 1     | rtsx_pci   | [44E3728303](<Desktop/Hewlett-Packard/23/23-h132la/56D106DFF57C/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/44E3728303>) |
| 10ec:5229 | 103c:2b44 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 1     | rtsx_pci   | [B62DF43777](<Desktop/Hewlett-Packard/23/23-q145d/C780395FC0D4/ZORIN-16/5.11.0-41-GENERIC/X86_64/B62DF43777>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10de:0753 | 1043:82f2 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 88    |            | [246492391C](<Desktop/ASUSTek Computer/M3/M3N78-VM/D58483C6966C/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/246492391C>) |
| 10de:03f4 | 1462:7597 | Nvidia           | MCP61 SMU                            | 48    |            | [F64F988A79](<Desktop/MSI/MS/MS-7597/7A3BD8C4DF79/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/F64F988A79>) |
| 10de:0753 | 1849:0753 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 43    |            | [618073D9E9](<Desktop/ASRock/M3N78D/M3N78D FX/B2B9E7C08585/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/618073D9E9>) |
| 10de:03f4 | 1462:7309 | Nvidia           | MCP61 SMU                            | 42    |            | [FE0FAE3528](<Desktop/MSI/MS/MS-7309/6A09B01BC304/UBUNTU-22.04/5.15.0-53-GENERIC/X86_64/FE0FAE3528>) |
| 10de:0753 | 1043:82e2 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 27    |            | [FB7920C5F9](<Desktop/ASUSTek Computer/M3N/M3N WS/208D21EEB6BD/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/FB7920C5F9>) |
| 10de:0aa3 | 1025:0222 | Nvidia           | MCP79 Co-processor                   | 20    | nvidia     | [4567C6A09C](<Desktop/Acer/Aspire/Aspire R3610/57B014A6CE4A/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/4567C6A09C>) |
| 10de:07da | 1025:0137 | Nvidia           | MCP73 Co-processor                   | 16    |            | [840102FA91](<Desktop/Acer/Aspire/Aspire M1641/7EAED14E4FB3/LINUXMINT-21.1/5.15.0-58-GENERIC/X86_64/840102FA91>) |
| 10de:0aa3 | 1462:7621 | Nvidia           | MCP79 Co-processor                   | 16    | nvidia     | [83C862DA24](<Desktop/Medion/MS/MS-7621/B7D24A17624E/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/83C862DA24>) |
| 10de:0753 | 1025:0228 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 15    |            | [093B0A0239](<Desktop/Acer/Aspire/Aspire X3400/F3DF4913E2F4/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/093B0A0239>) |
| 10de:0753 | 1025:0153 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 14    |            | [93EAD8D396](<Desktop/Packard Bell/IMEDIA/IMEDIA S3210/6653009DB244/UBUNTU-20.04/5.4.0-126-GENERIC/X86_64/93EAD8D396>) |
| 10de:0753 | 1043:82e8 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 14    |            | [30DEED8E5A](<Desktop/ASUSTek Computer/M4/M4N72-E/53E639627E9E/ARCH-ROLLING/6.2.2-ARCH2-1/X86_64/30DEED8E5A>) |
| 10de:03f4 |           | Nvidia           | MCP61 SMU                            | 13    |            | [36D5FF9438](<Desktop/JW Technology/JW-A61PM-D3/JW-A61PM-D3 Ver1.0/D6D5D6A3D313/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/36D5FF9438>) |
| 10de:0aa3 | 1025:0168 | Nvidia           | MCP79 Co-processor                   | 13    | nvidia     | [0CB51F3E6F](<Desktop/Gateway/LX4800/LX4800-LX6810/C01856F4DDC4/ZORIN-16/5.13.0-40-GENERIC/X86_64/0CB51F3E6F>) |
| 10de:07da | 1462:7504 | Nvidia           | MCP73 Co-processor                   | 12    |            | [58DE65FDBD](<Desktop/Fujitsu Siemens/AMILO/AMILO Desktop Pi3620A/B546F6B2BCF4/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/58DE65FDBD>) |
| 10de:0753 | 1565:340b | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 11    |            | [E42AE4DEEF](<Desktop/Biostar/GF8200C/GF8200C M2+/E6FCC317BD33/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-X86_64/X86_64/E42AE4DEEF>) |
| 8086:19e2 | 8086:0000 | Intel            | Atom Processor C3000 Series Quick... | 11    | qat_c3xxx  | [7D87907153](<Desktop/Supermicro/SYS-5019/SYS-5019A-FTN4/61D6B32F418F/ARCO-ROLLING/5.16.11-ARCH1-1/X86_64/7D87907153>) |
| 10de:03f4 | 1043:8234 | Nvidia           | MCP61 SMU                            | 9     |            | [56DB54E530](<Desktop/ASUSTek Computer/M2/M2N/64A18C11057B/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/56DB54E530>) |
| 10de:0543 | 1849:0543 | Nvidia           | MCP67 Co-processor                   | 9     |            | [BD8595032E](<Desktop/ASRock/N68/N68PV-GS/6BB6DCC2C405/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/BD8595032E>) |
| 10de:0753 | 103c:2a81 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 9     |            | [F0F25E6854](<Desktop/Hewlett-Packard/NF333AA-UUZ/NF333AA-UUZ m9555ch/49A36DD90031/UBUNTU-22.04/5.15.0-53-GENERIC/X86_64/F0F25E6854>) |
| 10de:0753 | 1043:82e7 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 9     |            | [A2423B5193](<Desktop/ASUSTek Computer/M4N98TD/M4N98TD EVO/F9E65A2C3C9E/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/A2423B5193>) |
| 10de:0aa3 | 1849:0aa3 | Nvidia           | MCP79 Co-processor                   | 8     | nvidia     | [339F0E7944](<Desktop/ASRock/AMCP7/AMCP7A-ION/8BB82D0566AD/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/339F0E7944>) |
| 10de:0aa3 | 1b0a:0074 | Nvidia           | MCP79 Co-processor                   | 8     | nvidia     | [037350830E](<Desktop/Iskratel, Kranj/IN6011/IN6011AX/5EBBBEAF3D80/DEBIAN-10/4.19.272/X86_64/037350830E>) |
| 10de:0753 | 1025:0227 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 7     |            | [CD9DCCABAF](<Desktop/Acer/Aspire/Aspire X3300/A00C677D19C4/ARCO-ROLLING/6.1.9-ARCH1-1/X86_64/CD9DCCABAF>) |
| 10de:07da | 1462:736b | Nvidia           | MCP73 Co-processor                   | 7     |            | [206AB01C63](<Desktop/Medion/MS/MS-7366/CDA38A6BDEAA/ZORIN-16/5.13.0-39-GENERIC/X86_64/206AB01C63>) |
| 10de:0aa3 | 105b:0d52 | Nvidia           | MCP79 Co-processor                   | 7     | nvidia     | [E4B99289C7](<Desktop/Foxconn/nT-330/nT-330i/68041A465A50/ROSA-12.3/5.10.155-GENERIC-1ROSA2021.1-X86_64/X86_64/E4B99289C7>) |
| 10de:03f4 | 1849:03f4 | Nvidia           | MCP61 SMU                            | 6     |            | [6A810D253C](<Desktop/ASRock/AM2/AM2NF6G-VSTA/A1C2D50C1B85/DEBIAN-11/5.10.0-18-AMD64/X86_64/6A810D253C>) |
| 10de:0753 | 1019:1b67 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 6     |            | [9B536F16BE](<Desktop/ECS/GF8100/GF8100VM-M5/3CC8944A1E74/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/9B536F16BE>) |
| 10de:0753 | 1025:0157 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 6     |            | [F4E3945DEA](<Desktop/Acer/Aspire/Aspire X3200/F0AE21053981/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F4E3945DEA>) |
| 10de:0753 | 103c:2a9e | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 6     |            | [2C7B59F70B](<Desktop/Hewlett-Packard/Pro/Pro 3015 Microtower PC/8AA3ED187E3A/LMDE-5/5.10.0-17-AMD64/X86_64/2C7B59F70B>) |
| 10de:07da | 1462:7366 | Nvidia           | MCP73 Co-processor                   | 6     |            | [97443C2383](<Desktop/PowerSpec/B/B701/627C03666188/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/97443C2383>) |
| 10de:07da | 1849:07da | Nvidia           | MCP73 Co-processor                   | 6     |            | [F64B92D5B2](<Desktop/Others/Phitronics/Phitronics PN73PVS-M/507301E280B4/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/F64B92D5B2>) |
| 10de:0aa3 | 103c:2a95 | Nvidia           | MCP79 Co-processor                   | 6     | nvidia     | [C1ABA90F51](<Desktop/Hewlett-Packard/AY690AA-ABM/AY690AA-ABM 600-1120la/1CD99EDF30E4/UBUNTU-22.04/5.15.0-46-GENERIC/X86_64/C1ABA90F51>) |
| 10de:0753 | 1043:8332 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 5     |            | [4B705B9DCA](<Desktop/ASUSTek Computer/CROSSHAIR/CROSSHAIR II FORMULA/4ADEED4021BD/UBUNTU-20.04/5.4.0-144-GENERIC/X86_64/4B705B9DCA>) |
| 10de:0aa3 | 1043:83e2 | Nvidia           | MCP79 Co-processor                   | 5     | nvidia     | [16680C5211](<Desktop/ASUSTek Computer/AT3IONT-I/AT3IONT-I DELUXE/BC54D2BC4CB0/ROSA-12.3/5.15.79-GENERIC-1ROSA2021.1-X86_64/X86_64/16680C5211>) |
| 10de:0aa3 | 1043:83e9 | Nvidia           | MCP79 Co-processor                   | 5     | nvidia     | [B53C22C83B](<Desktop/ASUSTek Computer/EB/EB1501/68A350696A97/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/B53C22C83B>) |
| 10de:0753 | 1019:2646 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 4     |            | [32E951A2CA](<Desktop/ECS/GeForce/GeForce 8000 series/7AD893FBA673/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/32E951A2CA>) |
| 10de:0753 | 1462:7612 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 4     |            | [81348124FF](<Desktop/MSI/MS/MS-7612/147E1DD16356/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/81348124FF>) |
| 10de:0aa3 | 1043:8356 | Nvidia           | MCP79 Co-processor                   | 4     | nvidia     | [E8AC8A9926](<Desktop/ASUSTek Computer/P5/P5N7A-VM/BF87A5581C11/LINUXMINT-20.1/5.4.0-126-GENERIC/X86_64/E8AC8A9926>) |
| 10de:0aa3 | 1043:83f9 | Nvidia           | MCP79 Co-processor                   | 4     | nvidia     | [59DE62AAC5](<Desktop/ASUSTek Computer/AT3/AT3N7A-I/985994B45E9B/DEBIAN-11/5.10.0-21-AMD64/X86_64/59DE62AAC5>) |
| 10de:0aa3 | 19da:0ae5 | Nvidia           | MCP79 Co-processor                   | 4     | nvidia     | [26AB83FFCB](<Desktop/Nvidia/MCP7/MCP7A/3C999689FBD9/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/26AB83FFCB>) |
| 10de:0aa3 | 19da:a108 | Nvidia           | MCP79 Co-processor                   | 4     | nvidia     | [D7811DBD43](<Desktop/Others/Others/Others/6D252B38811E/UBUNTU-MATE-18.04/4.15.0-175-GENERIC/X86_64/D7811DBD43>) |
| 8086:19e2 | 8086:19e2 | Intel            | Atom Processor C3000 Series Quick... | 4     | qat_c3xxx  | [D563EB82AE](<Desktop/ASRockRack/C3558/C3558D4I-4L/DF49EDAF85B3/DEBIAN-11/5.10.0-9-AMD64/X86_64/D563EB82AE>) |
| 10de:0753 | 1025:0462 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 3     |            | [BEB8F313F7](<Desktop/Packard Bell/ONETWO/ONETWO L5351/87BFB44376B9/UBUNTU-20.04/5.4.0-40-GENERIC/X86_64/BEB8F313F7>) |
| 10de:0753 | 10de:cb84 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 3     |            | [0265FC0430](<Desktop/Others/NF-MCP/NF-MCP78/8DA840843CBF/LINUXMINT-20.2/5.4.0-110-GENERIC/X86_64/0265FC0430>) |
| 10de:07da | 10de:07d7 | Nvidia           | MCP73 Co-processor                   | 3     |            | [974A439CC4](<Desktop/Biostar/GF7050V-M7/GF7050V-M7 SE/36EF12E941C9/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/974A439CC4>) |
| 10de:07da | 1462:736a | Nvidia           | MCP73 Co-processor                   | 3     |            | [C8138F4FFE](<Desktop/Medion/MS/MS-7366/BE9DB880847E/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/C8138F4FFE>) |
| 10de:0aa3 | 103c:2aa1 | Nvidia           | MCP79 Co-processor                   | 3     | nvidia     | [622D9B0AE4](<Desktop/Hewlett-Packard/9100/9100/CDF41627BA43/KDE-NEON-20.04/5.11.0-27-GENERIC/X86_64/622D9B0AE4>) |
| 10de:0aa3 | 10de:cb79 | Nvidia           | MCP79 Co-processor                   | 3     | nvidia     | [879EB33660](<Desktop/Gigabyte Technology/GA-E7/GA-E7AUM-DS2H/393596BF6BD9/LINUXMINT-20.2/5.4.0-84-GENERIC/X86_64/879EB33660>) |
| 10de:0aa3 | 1458:0aa3 | Nvidia           | MCP79 Co-processor                   | 3     | nvidia     | [825B26708C](<Desktop/Gigabyte Technology/GA-E7/GA-E7AUM-DS2H/DD178E96535A/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/825B26708C>) |
| 8086:0435 | 8086:0000 | Intel            | DH895XCC Series QAT                  | 3     | qat_dh8... | [43EC5396F3](<Desktop/Others/FT2000plus/FT2000plus Generic Borad & Memsize 128G/0700A2AB6EAB/DEBIAN-10/4.19.0-23-ARM64/AARCH64/43EC5396F3>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c3a | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 1518  | mei_me     | [386D7C9DE4](<Desktop/ASUSTek Computer/P8/P8P67-M/D3654512534B/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/386D7C9DE4>) |
| 8086:8c3a | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 1287  | mei_me     | [E146C82A49](<Desktop/ASUSTek Computer/All/All Series/D75C393B8A2E/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/E146C82A49>) |
| 8086:a13a | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 1074  | mei_me     | [BBFD29FB88](<Desktop/ASUSTek Computer/D320/D320SF/A7E6ADB389B1/UBUNTU-20.04/5.4.0-148-GENERIC/X86_64/BBFD29FB88>) |
| 8086:1e3a | 1043:84ca | Intel            | 7 Series/C216 Chipset Family MEI ... | 1046  | mei_me     | [92B5951471](<Desktop/ASUSTek Computer/Z77/Z77-A/7F8B426D3C22/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/92B5951471>) |
| 8086:1c3a | 1458:1c3a | Intel            | 6 Series/C200 Series Chipset Fami... | 919   | mei_me     | [E7B77F5CF0](<Desktop/Gigabyte Technology/Z68/Z68MA-D2H-B3/99DA8E367A7A/OPENMANDRIVA-23.03/5.16.13-DESKTOP-1OMV4003/X86_64/E7B77F5CF0>) |
| 8086:8c3a | 1458:1c3a | Intel            | 8 Series/C220 Series Chipset Fami... | 862   | mei_me     | [22BD54D6D1](<Desktop/Gigabyte Technology/Z87/Z87X-UD3H/F9D737247AAE/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/22BD54D6D1>) |
| 8086:1e3a | 1458:1c3a | Intel            | 7 Series/C216 Chipset Family MEI ... | 776   | mei_me     | [A72531BD2D](<Desktop/MouseComputer/B75/B75M-D3V-JP/041627593BC4/LINUXMINT-18.3/4.8.0-58-GENERIC/X86_64/A72531BD2D>) |
| 8086:a2ba | 1043:8694 | Intel            | 200 Series PCH CSME HECI #1          | 774   | mei_me     | [536E6E7CC9](<Desktop/ASUSTek Computer/STRIX/STRIX B250I GAMING/BB9A16765525/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/536E6E7CC9>) |
| 8086:a2ba | 1458:1c3a | Intel            | 200 Series PCH CSME HECI #1          | 688   | mei_me     | [E44F7DFAC5](<Desktop/Punch Technology/PDT-702/PDT-702-1020/29C76CB9E8B7/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/E44F7DFAC5>) |
| 8086:a13a | 1458:1c3a | Intel            | 100 Series/C230 Series Chipset Fa... | 626   | mei_me     | [8C5B603452](<Desktop/Gigabyte Technology/Z170X-Gaming/Z170X-Gaming 7/F95579DE4AF1/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/8C5B603452>) |
| 8086:a360 | 1043:8694 | Intel            | Cannon Lake PCH HECI Controller      | 607   | mei_me     | [14C71828CA](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-F GAMING/5D29F2B9EBFF/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/14C71828CA>) |
| 8086:8cba | 1043:8534 | Intel            | 9 Series Chipset Family ME Interf... | 516   | mei_me     | [C47205C3CB](<Desktop/ASUSTek Computer/All/All Series/0A37A7D15166/STEAMOS-4/6.1.21-VALVE1-1-NEPTUNE-61/X86_64/C47205C3CB>) |
| 8086:a360 | 1458:1c3a | Intel            | Cannon Lake PCH HECI Controller      | 489   | mei_me     | [19D78D1685](<Desktop/Gigabyte Technology/Z390/Z390 UD/8E72A411386D/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/19D78D1685>) |
| 8086:8cba | 1458:1c3a | Intel            | 9 Series Chipset Family ME Interf... | 389   | mei_me     | [2CBFF804D8](<Desktop/Gigabyte Technology/Z97X-Gaming/Z97X-Gaming 3/EEB9D6F73B6D/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/2CBFF804D8>) |
| 8086:8c3a | 1849:8c3a | Intel            | 8 Series/C220 Series Chipset Fami... | 388   | mei_me     | [E3971068B6](<Desktop/ASRock/Z87/Z87 Pro4/7D116E456DAE/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/E3971068B6>) |
| 8086:1c3a | 1849:1c3a | Intel            | 6 Series/C200 Series Chipset Fami... | 368   | mei_me     | [13B1131BEF](<Desktop/ASRock/H67/H67DE3-SI/ED18AAFC18F5/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/13B1131BEF>) |
| 8086:43e0 | 1043:8694 | Intel            | Tiger Lake-H Management Engine In... | 338   | mei_me     | [DE65A79BF1](<Desktop/ASUSTek Computer/TUF/TUF Gaming B560M-PLUS/929B4939E2C7/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/DE65A79BF1>) |
| 8086:1e3a | 1028:0577 | Intel            | 7 Series/C216 Chipset Family MEI ... | 322   | mei_me     | [F0F22D5D3F](<Desktop/Dell/OptiPlex/OptiPlex 7010/D7591CF7C8EA/UBUNTU-20.04/5.4.0-148-GENERIC/X86_64/F0F22D5D3F>) |
| 8086:a2ba | 1849:a2ba | Intel            | 200 Series PCH CSME HECI #1          | 292   | mei_me     | [D905BABC43](<Desktop/ASRock/B250/B250M-HDV/A65B4BC89A4A/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/D905BABC43>) |
| 8086:a13a | 1849:a13a | Intel            | 100 Series/C230 Series Chipset Fa... | 288   | mei_me     | [A38BF561F7](<Desktop/ASRock/Z170/Z170 Gaming K4/19138DC977DF/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/A38BF561F7>) |
| 8086:8c3a | 1462:7817 | Intel            | 8 Series/C220 Series Chipset Fami... | 286   | mei_me     | [B5C0679341](<Desktop/MSI/MS/MS-7817/73BC5E06C84D/GENTOO-2.13/6.3.1-GENTOO/X86_64/B5C0679341>) |
| 8086:1e3a | 1849:1e3a | Intel            | 7 Series/C216 Chipset Family MEI ... | 275   | mei_me     | [0DA080327F](<Desktop/ASRock/Z77/Z77 Extreme3/7F778DC75AC8/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/0DA080327F>) |
| 8086:43e0 | 1458:1c3a | Intel            | Tiger Lake-H Management Engine In... | 273   | mei_me     | [25C4B5FE60](<Desktop/Gigabyte Technology/Z590/Z590 AORUS ELITE AX/B68CA193B4B0/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/25C4B5FE60>) |
| 8086:8c3a | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 247   | mei_me     | [5BC5CCDCAD](<Desktop/Dell/OptiPlex/OptiPlex 9020/E9FD17DAA8B2/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/5BC5CCDCAD>) |
| 8086:7ae8 | 1043:8694 | Intel            | Alder Lake-S PCH HECI Controller #1  | 246   | mei_me     | [401DB07B93](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z690-A GAMING WIFI D4/46556BD3958D/DEBIAN-12/6.1.0-7-AMD64/X86_64/401DB07B93>) |
| 8086:a2ba | 1043:872f | Intel            | 200 Series PCH CSME HECI #1          | 245   | mei_me     | [D53CE13AA3](<Desktop/ASUSTek Computer/STRIX/STRIX Z270F GAMING/6DEFE4E23C63/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/D53CE13AA3>) |
| 8086:1c3a | 1028:04ad | Intel            | 6 Series/C200 Series Chipset Fami... | 212   | mei_me     | [A8D4348329](<Desktop/Dell/OptiPlex/OptiPlex 790/803B6B05C26E/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/A8D4348329>) |
| 8086:1d3a | 1043:84ef | Intel            | C600/X79 series chipset MEI Contr... | 203   | mei_me     | [F9D2B57C91](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X79/F79B74A5FAD0/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/F9D2B57C91>) |
| 8086:8c3a | 1028:0612 | Intel            | 8 Series/C220 Series Chipset Fami... | 192   | mei_me     | [2F6FD9E5B0](<Desktop/Dell/OptiPlex/OptiPlex 3020/6E94400CAA49/XUBUNTU-23.04/6.2.0-20-GENERIC/X86_64/2F6FD9E5B0>) |
| 8086:a360 | 1849:a360 | Intel            | Cannon Lake PCH HECI Controller      | 192   | mei_me     | [AC982522AB](<Desktop/ASRock/B360M/B360M IB-R1/6EDAE1870B25/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/AC982522AB>) |
| 8086:8d3a | 1043:8600 | Intel            | C610/X99 series chipset MEI Contr... | 177   | mei_me     | [6505E46B86](<Desktop/ASUSTek Computer/All/All Series/5486940BFA29/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/6505E46B86>) |
| 8086:1e3a | 103c:3397 | Intel            | 7 Series/C216 Chipset Family MEI ... | 176   | mei_me     | [8B84766D3D](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/EAE7702EADF9/DEBIAN-11/6.1.15-1-PVE/X86_64/8B84766D3D>) |
| 8086:8cba | 1849:8cba | Intel            | 9 Series Chipset Family ME Interf... | 171   | mei_me     | [7B83DEF3E1](<Desktop/ASRock/Z97/Z97 Extreme4/0931B22FD179/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/7B83DEF3E1>) |
| 8086:a3ba | 1043:8694 | Intel            | Comet Lake PCH-V HECI Controller     | 168   | mei_me     | [147006A71F](<Desktop/ASUSTek Computer/PRIME/PRIME H410M-A/A5F891271BF2/LINUXMINT-20.2/5.4.0-137-GENERIC/X86_64/147006A71F>) |
| 8086:3b64 | 1043:8383 | Intel            | 5 Series/3400 Series Chipset HECI... | 165   | mei_me     | [897FC61B8C](<Desktop/ASUSTek Computer/P7Q57-M/P7Q57-M DO/6AEA267E7346/LMDE-5/5.10.0-22-AMD64/X86_64/897FC61B8C>) |
| 8086:319a | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 156   | mei_me     | [22D1FBDEEE](<Desktop/Others/Others/Others/7E2DCAD143A6/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/22D1FBDEEE>) |
| 8086:29b4 | 1028:0211 | Intel            | 82Q35 Express MEI Controller         | 154   | mei_me     | [03C6B8486E](<Desktop/Dell/OptiPlex/OptiPlex 755/F8A80185DE25/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/03C6B8486E>) |
| 8086:06e0 | 1043:8694 | Intel            | Comet Lake HECI Controller           | 151   | mei_me     | [1EDDB3203A](<Desktop/ASUSTek Computer/PRIME/PRIME Z490-A/27EB1FCAC7E3/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/1EDDB3203A>) |
| 8086:1c3a | 1028:0585 | Intel            | 6 Series/C200 Series Chipset Fami... | 150   | mei_me     | [DE394C8663](<Desktop/Dell/OptiPlex/OptiPlex 3010/D899A78989BD/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/DE394C8663>) |
| 8086:2e14 | 1028:0420 | Intel            | 4 Series Chipset HECI Controller     | 148   | mei_me     | [B585380BC4](<Desktop/Dell/OptiPlex/OptiPlex 780/8DA70E0A4BDE/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/B585380BC4>) |
| 8086:1e3a | 103c:339a | Intel            | 7 Series/C216 Chipset Family MEI ... | 145   | mei_me     | [8B646A0FA1](<Desktop/Hewlett-Packard/Compaq/Compaq Pro 6300 MT/C7D9D31D8078/ZORIN-16/5.15.0-71-GENERIC/X86_64/8B646A0FA1>) |
| 8086:8c3a | 103c:1998 | Intel            | 8 Series/C220 Series Chipset Fami... | 141   | mei_me     | [2ED500D3E9](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/4A54E9E0D620/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/2ED500D3E9>) |
| 8086:8c3a | 103c:18e7 | Intel            | 8 Series/C220 Series Chipset Fami... | 139   | mei_me     | [C6A760CB50](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 SFF/E9FD6C026940/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/C6A760CB50>) |
| 8086:3b64 | 1458:3b64 | Intel            | 5 Series/3400 Series Chipset HECI... | 138   | mei_me     | [F44B68CF93](<Desktop/Gigabyte Technology/H55/H55M-S2H/9BD2EEAC32E7/OPENSUSE-LEAP-15.4/5.14.21-150400.24.55-DEFAULT/X86_64/F44B68CF93>) |
| 8086:1c3a | 1028:04f5 | Intel            | 6 Series/C200 Series Chipset Fami... | 135   | mei_me     | [70862B2870](<Desktop/Dell/OptiPlex/OptiPlex 390/D98A1DAB1265/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/70862B2870>) |
| 8086:8c3a | 1734:11ea | Intel            | 8 Series/C220 Series Chipset Fami... | 133   | mei_me     | [9B6F7CEA89](<Desktop/Fujitsu/ESPRIMO/ESPRIMO Q520/707B73345F8F/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/9B6F7CEA89>) |
| 8086:1c3a | 1028:047e | Intel            | 6 Series/C200 Series Chipset Fami... | 132   | mei_me     | [EC04C034D3](<Desktop/Dell/OptiPlex/OptiPlex 990/D0B1671560CE/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/EC04C034D3>) |
| 8086:a2ba | 1043:873c | Intel            | 200 Series PCH CSME HECI #1          | 131   | mei_me     | [1C9E5EE2A6](<Desktop/ASUSTek Computer/WS/WS X299 SAGE/7F377E5958FC/LINUXMINT-20.3/5.19.0-17.2-LIQUORIX-AMD64/X86_64/1C9E5EE2A6>) |
| 8086:a13a | 1462:7996 | Intel            | 100 Series/C230 Series Chipset Fa... | 129   | mei_me     | [D63BC9AECA](<Desktop/MSI/MS/MS-7996/30F694CCEC2B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D63BC9AECA>) |
| 8086:1c3a | 8086:1c3a | Intel            | 6 Series/C200 Series Chipset Fami... | 128   | mei_me     | [CD89C5B708](<Desktop/Intel/H/H61/75D9EAFF3D08/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/CD89C5B708>) |

### Dma controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1311:0801 | 0000:ffff | Videoserver      | DMA controller                       | 1     |            | [EAD04A61E4](<Desktop/Others/Others/Others/5311168F852E/ROSA-2016.1/4.15.0-DESKTOP-68.5ROSA-I586/I686/EAD04A61E4>) |

### Dma controller (8237) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10b5:2715 | 10b5:2715 | PLX Technology   | DMA controller                       | 1     | plx_pci    | [9AB077CEAD](<Desktop/Gigabyte Technology/Z77/Z77-DS3H/8181011A0A1F/LINUXMINT-20.3/5.13.0-30-GENERIC/X86_64/9AB077CEAD>) |
| 15b3:c2d3 | 15b3:0127 | Mellanox Tech... | MT42822 BlueField-2 SoC Managemen... | 1     | vfio_pci   | [19C318242F](<Desktop/Others/Others/Others/C3C1AB1B873D/UBUNTU-20.04/5.15.0-1023-NVIDIA/X86_64/19C318242F>) |

### Dma controller (eisa dma) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0f06 | 8086:2056 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     |            | [D4408F7B0E](<Desktop/Intel/DE3815TYKH/DE3815TYKH H26998-403/3CECC7AD024C/DEBIAN-10/4.19.0-14-AMD64/X86_64/D4408F7B0E>) |
| 8086:0f06 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | dw_dmac... | [A211982E39](<Desktop/MPL/CEC10/CEC10 Family/DF56F838D597/UBUNTU-18.04/4.15.0-29-GENERIC/X86_64/A211982E39>) |
| 8086:0f40 | 8086:2056 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     |            | [D4408F7B0E](<Desktop/Intel/DE3815TYKH/DE3815TYKH H26998-403/3CECC7AD024C/DEBIAN-10/4.19.0-14-AMD64/X86_64/D4408F7B0E>) |
| 8086:0f40 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | dw_dmac... | [A211982E39](<Desktop/MPL/CEC10/CEC10 Family/DF56F838D597/UBUNTU-18.04/4.15.0-29-GENERIC/X86_64/A211982E39>) |

### Docking station (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 168c:0829 | 1186:3a7c | Qualcomm Atheros | Docking Station                      | 1     |            | [544F0D2A23](<Desktop/ASUSTek Computer/P5/P5GV-MX/8F24B4F00214/ROSA-2016.1/4.9.155-NRJ-DESKTOP-1ROSA-I586/I686/544F0D2A23>) |

### Dpio module (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 012d:4d4c | 10b5:9080 |                  | DPIO module                          | 1     |            | [D88A4D7D31](<Desktop/OEM/Others/Others/2CCC9BBC64D0/UBUNTU-19.04/5.0.0-15-GENERIC/X86_64/D88A4D7D31>) |
| 10b5:9050 | ddd1:0001 | PLX Technology   | PCI <-> IOBus Bridge                 | 1     |            | [117638721D](<Desktop/Gigabyte Technology/8IK1100/8IK1100/7972F89846AB/ROSA-2016.1/4.9.20-NRJ-DESKTOP-1ROSA-I586/I686/117638721D>) |
| 2718:5125 | 2718:5125 |                  | DPIO module                          | 1     |            | [B8D373B07E](<Desktop/ASUSTek Computer/H170I-PLUS/H170I-PLUS D3/17849F8BF79E/DEBIAN-9/4.9.0-19-RT-AMD64/X86_64/B8D373B07E>) |

### Dvb card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 13d0:2103 | 13d0:2103 | Techsan Elect... | B2C2 FlexCopII DVB chip / Technis... | 81    | b2c2_fl... | [B561C005C5](<Desktop/ASUSTek Computer/M4/M4A78LT-M-LE/6D321C87E95D/UBUNTU-18.04/4.15.0-210-GENERIC/I686/B561C005C5>) |
| 1131:7146 | 13c2:1018 | Philips Semic... | SAA7146                              | 28    | budget     | [2C8298A0A8](<Desktop/ASUSTek Computer/P5/P5K-VM/8729F07DF78D/ROSA-2016.1/4.9.155-NRJ-DESKTOP-1ROSA-I586/I686/2C8298A0A8>) |
| 109e:0878 | 1822:0001 | Brooktree        | Bt878 Audio Capture                  | 7     | bt878      | [8CE355C181](<Desktop/ASUSTek Computer/Commando/Commando/A6F0BB02EDAA/UBUNTU-20.04/5.11.0-44-GENERIC/X86_64/8CE355C181>) |
| 1131:7146 | 13c2:101a | Philips Semic... | SAA7146                              | 7     | budget_ci  | [1B275899D5](<Desktop/Supermicro/C2/C2SBX/7D054759F288/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/1B275899D5>) |
| 1131:7146 | 13c2:1019 | Philips Semic... | SAA7146                              | 6     | budget_ci  | [4468C0FCB9](<Desktop/ASRock/FM2/FM2A68M-HD+/D53DE27D2523/UBUNTU-22.10/5.19.0-31-GENERIC/X86_64/4468C0FCB9>) |
| 14f1:8802 | 0070:9002 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 6     | cx88_dvb   | [363AC45AF6](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/C4E9F5816A58/OPENMANDRIVA-4.50/5.19.12-DESKTOP-2OMV4090/X86_64/363AC45AF6>) |
| 109e:0878 | 11bd:001c | Brooktree        | Bt878 Audio Capture                  | 4     | bt878      | [17A2F79F3F](<Desktop/Hewlett-Packard/Compaq/Compaq 6200 Pro MT PC/7AF3849C0C3B/LINUXMINT-21/5.15.0-48-GENERIC/X86_64/17A2F79F3F>) |
| 1131:7146 | 13c2:0003 | Philips Semic... | SAA7146                              | 3     | dvb_ttpci  | [30C75DB366](<Desktop/MSI/MS/MS-7721/56828EC55E82/OPENMANDRIVA-23.01/6.1.4-DESKTOP-1OMV2301/X86_64/30C75DB366>) |
| 109e:0878 | 1461:0771 | Brooktree        | Bt878 Audio Capture                  | 2     | bt878      | [AB87264048](<Desktop/Gigabyte Technology/GA-990/GA-990FXA-UD3/E8619E62E43B/KDE-NEON-20.04/5.4.0-73-GENERIC/X86_64/AB87264048>) |
| 1131:7146 | 153b:1156 | Philips Semic... | SAA7146                              | 2     | budget_av  | [5714C771CF](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 6.0/6AA7E1DCE287/KDE-NEON-20.04/5.11.0-46-GENERIC/X86_64/5714C771CF>) |
| 1131:7146 | 1894:0022 | Philips Semic... | SAA7146                              | 2     | budget_av  | [B4ED754106](<Desktop/ASRock/P4/P4i945GC/0305A6A5F9A5/UBUNTU-18.04/4.15.0-162-GENERIC/I686/B4ED754106>) |
| 14f1:8802 | 17de:08a6 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 2     | cx88_dv... | [D932872569](<Desktop/ASUSTek Computer/M5/M5A78L-M-USB3/0025C6AEE254/UBUNTU-20.04/5.4.0-29-GENERIC/X86_64/D932872569>) |
| 195d:1105 | 195d:1105 |                  | PCI 2002 DVB-S BDA Device            | 2     | dm1105     | [4AEC213A10](<Desktop/H61M/5123660003/5123660003/7801115B9A5D/UBUNTU-MATE-18.04/5.4.0-66-GENERIC/X86_64/4AEC213A10>) |
| 1131:7146 | 1131:4f56 | Philips Semic... | SAA7146                              | 1     | budget_av  | [B220FD9C11](<Desktop/Fujitsu Siemens/SCENIC/SCENIC T/942B46D683B9/UBUNTU-18.04/4.15.0-65-GENERIC/I686/B220FD9C11>) |
| 1131:7146 | 13c2:000a | Philips Semic... | SAA7146                              | 1     | dvb_ttpci  | [9A76597218](<Desktop/Gigabyte Technology/Z77/Z77X-D3H/0FB804072D9B/UBUNTU-20.04/5.8.0-59-LOWLATENCY/X86_64/9A76597218>) |
| 1131:7146 | 13c2:000e | Philips Semic... | SAA7146                              | 1     | dvb_ttpci  | [2A21A99A38](<Desktop/ASUSTek Computer/All/All Series/F0C3AA9AE2B7/ROSA-2014.1/4.1.19-NRJ-DESKTOP-2ROSA-X86_64/X86_64/2A21A99A38>) |
| 1131:7146 | 153b:1154 | Philips Semic... | SAA7146                              | 1     | budget_av  | [D949336ED1](<Desktop/ASUSTek Computer/P5/P5KPL-C/986174DB578E/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/D949336ED1>) |
| 1131:7146 | 153b:1176 | Philips Semic... | SAA7146                              | 1     | budget_av  | [E2EE931DF2](<Desktop/ASUSTek Computer/A78/A78M-A/FBD31929FB69/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.12-1-DEFAULT/X86_64/E2EE931DF2>) |
| 13d0:2103 | ffff:ffff | Techsan Elect... | B2C2 FlexCopII DVB chip / Technis... | 1     | b2c2_fl... | [7609423845](<Desktop/Olidata/ALICON/ALICON 4/554D1F80B624/UBUNTU-20.04/5.8.0-44-GENERIC/X86_64/7609423845>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1486 | 1022:1486 | AMD              | Starship/Matisse Cryptographic Co... | 2904  | ccp        | [53D91DCA3C](<Desktop/ASRock/B450M/B450M Steel Legend/57EFD5B4322B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/53D91DCA3C>) |
| 1022:1456 | 1022:1456 | AMD              | Family 17h (Models 00h-0fh) Platf... | 2780  | ccp        | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 1022:15df | 1022:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 1944  | ccp        | [2A09FB1D81](<Desktop/Gigabyte Technology/B450M/B450M DS3H/93E61F10B914/LINUXMINT-20.3/5.4.0-148-GENERIC/X86_64/2A09FB1D81>) |
| 1022:1486 | 1043:87c0 | AMD              | Starship/Matisse Cryptographic Co... | 1290  | ccp        | [4A8C2101E8](<Desktop/ASUSTek Computer/PRIME/PRIME X570-PRO/D1E7CA404339/DEBIAN-11/5.10.0-22-AMD64/X86_64/4A8C2101E8>) |
| 1022:1456 | 1043:8747 | AMD              | Family 17h (Models 00h-0fh) Platf... | 973   | ccp        | [D9A3AFA732](<Desktop/ASUSTek Computer/ROG/ROG STRIX X470-I GAMING/133421F6DBD4/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/D9A3AFA732>) |
| 1022:1486 | 1043:8808 | AMD              | Starship/Matisse Cryptographic Co... | 738   | ccp        | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 1022:15df | 1043:876b | AMD              | Family 17h (Models 10h-1fh) Platf... | 422   | ccp        | [369BF3DC68](<Desktop/CMS Computers/7200/7200-5413A/68D04878595E/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/369BF3DC68>) |
| 1022:1578 | 1022:1578 | AMD              | Carrizo Platform Security Processor  | 361   |            | [A241837604](<Desktop/LTD Delovoy Office/320A3SM/320A3SM MT/67FBE1AE8CE6/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/A241837604>) |
| 1022:15df | 1043:8809 | AMD              | Family 17h (Models 10h-1fh) Platf... | 250   | ccp        | [D58E08C9AB](<Desktop/ASUSTek Computer/PRIME/PRIME B550-PLUS/1C885144C28F/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/D58E08C9AB>) |
| 1022:1486 | 1462:7c02 | AMD              | Starship/Matisse Cryptographic Co... | 176   | ccp        | [3A7E1532DA](<Desktop/MSI/MS-7/MS-7C02/ACF3D9051F49/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/3A7E1532DA>) |
| 1022:1649 | 1043:8877 | AMD              | VanGogh PSP/CCP                      | 124   | ccp        | [29B2378B4B](<Desktop/ASUSTek Computer/ROG/ROG STRIX B650E-F GAMING WIFI/B82AA0B20AA7/NIXOS-22.11/6.1.27/X86_64/29B2378B4B>) |
| 8086:2298 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 122   | mei_txe    | [0B5731F838](<Desktop/AAEON/MF/MF-001/22E58F437338/UBUNTU-20.04/5.15.0-69-GENERIC/X86_64/0B5731F838>) |
| 1022:1486 | 1462:7b86 | AMD              | Starship/Matisse Cryptographic Co... | 120   | ccp        | [8AA973E0F5](<Desktop/MSI/MS-7/MS-7B86/E575FEE21E0B/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/8AA973E0F5>) |
| 1022:1649 | 1022:1649 | AMD              | VanGogh PSP/CCP                      | 104   | ccp        | [ED03DF615E](<Desktop/ASRock/B650E/B650E PG Riptide WiFi/E45FD3D55523/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/ED03DF615E>) |
| 1022:1456 | 1462:7c02 | AMD              | Family 17h (Models 00h-0fh) Platf... | 94    | ccp        | [0B4FAAA32E](<Desktop/MSI/MS-7/MS-7C02/1C6B1A3D4456/ARCH-ROLLING/6.2.9-273-TKG-CFS/X86_64/0B4FAAA32E>) |
| 8086:0f18 | 1849:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 94    | mei_txe    | [6FF7177033](<Desktop/ASRock/Q1900/Q1900M/2D1AE02DAE04/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/6FF7177033>) |
| 1022:1537 | 1022:1537 | AMD              | Kabini/Mullins PSP-Platform Secur... | 89    | ccp        | [CCAEAAE27B](<Desktop/Biostar/A68/A68N-5600E/37B56DD69E13/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/CCAEAAE27B>) |
| 1022:1456 | 1462:7b86 | AMD              | Family 17h (Models 00h-0fh) Platf... | 79    | ccp        | [51EF82C2FD](<Desktop/MSI/MS-7/MS-7B86/F09A19A83CF0/MANJARO/5.13.19-2-MANJARO/X86_64/51EF82C2FD>) |
| 1022:1486 | 1462:7b89 | AMD              | Starship/Matisse Cryptographic Co... | 77    | ccp        | [7560923404](<Desktop/MSI/MS-7/MS-7B89/9DE5683930C4/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/7560923404>) |
| 1022:1486 | 1462:7c94 | AMD              | Starship/Matisse Cryptographic Co... | 59    | ccp        | [26C158DF39](<Desktop/MSI/MS-7/MS-7C94/DD638739FE3A/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/26C158DF39>) |
| 1022:1486 | 1462:7c95 | AMD              | Starship/Matisse Cryptographic Co... | 56    | ccp        | [76748DA9CD](<Desktop/MSI/MS-7/MS-7C95/E2E66E37A3EB/FEDORA-38/6.2.12-300.FC38.X86_64/X86_64/76748DA9CD>) |
| 1022:1456 | 1462:7a38 | AMD              | Family 17h (Models 00h-0fh) Platf... | 54    | ccp        | [A9D1794EEC](<Desktop/MSI/MS-7/MS-7A38/C3487D76EFD3/FEDORA-36/6.1.8-100.FC36.X86_64/X86_64/A9D1794EEC>) |
| 1022:15df | 1043:87e1 | AMD              | Family 17h (Models 10h-1fh) Platf... | 54    | ccp        | [812906148B](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550M-PLUS/205744F95212/KUBUNTU-22.04/5.15.0-70-GENERIC/X86_64/812906148B>) |
| 1022:1486 | 1043:87cb | AMD              | Starship/Matisse Cryptographic Co... | 48    | ccp        | [B2AC72F8D9](<Desktop/ASUSTek Computer/PRIME/PRIME TRX40-PRO S/777303348731/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/B2AC72F8D9>) |
| 1022:15df | 1462:7a38 | AMD              | Family 17h (Models 10h-1fh) Platf... | 48    | ccp        | [7888E091F7](<Desktop/MSI/MS-7/MS-7A38/88082760C5B3/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/7888E091F7>) |
| 1022:1486 | 1462:7a38 | AMD              | Starship/Matisse Cryptographic Co... | 47    | ccp        | [A05BD1FFA7](<Desktop/MSI/MS-7/MS-7A38/D9678E934A75/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/A05BD1FFA7>) |
| 8086:0f18 | 8086:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 47    | mei_txe    | [3A5977AD04](<Desktop/ASL/BayTrail/BayTrail JHS773/D31A41ADF8D9/ZORIN-16/5.15.0-69-GENERIC/X86_64/3A5977AD04>) |
| 1022:1486 | 1043:87e2 | AMD              | Starship/Matisse Cryptographic Co... | 39    | ccp        | [98FFA037D9](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550M-PLUS/00BADF5270D7/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/98FFA037D9>) |
| 8086:0f18 | 1043:8534 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 39    | mei_txe    | [0A58F3FA51](<Desktop/ASUSTek Computer/All/All Series/C4CA4EEAC39B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/0A58F3FA51>) |
| 1022:1456 | 1462:7b89 | AMD              | Family 17h (Models 00h-0fh) Platf... | 38    | ccp        | [691239A442](<Desktop/MSI/MS-7/MS-7B89/D27AFC4010A4/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/691239A442>) |
| 8086:0f18 | 1458:1c3a | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 38    | mei_txe    | [F743E9293E](<Desktop/Gigabyte Technology/J1900/J1900M-D2P/AE8A76C72599/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/F743E9293E>) |
| 8086:2298 | 1458:1000 | Intel            | Atom/Celeron/Pentium Processor x5... | 38    | mei_txe    | [5356D2A0EF](<Desktop/Gigabyte Technology/GB-BACE/GB-BACE-3160/50364049E8CE/UBUNTU-20.04/5.4.0-144-GENERIC/X86_64/5356D2A0EF>) |
| 1022:1486 | 1462:7b85 | AMD              | Starship/Matisse Cryptographic Co... | 37    | ccp        | [B2782D28F7](<Desktop/MSI/MS-7/MS-7B85/A1797BB6666C/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/B2782D28F7>) |
| 1022:15df | 1462:7b86 | AMD              | Family 17h (Models 10h-1fh) Platf... | 34    | ccp        | [017222D810](<Desktop/MSI/MS-7/MS-7B86/C33D0282BB9A/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/017222D810>) |
| 8086:2298 | 1849:2298 | Intel            | Atom/Celeron/Pentium Processor x5... | 33    | mei_txe    | [5775B2C94F](<Desktop/ASRock/N3150/N3150-NUC/2743C66A2BAB/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/5775B2C94F>) |
| 1022:15df | 1462:7b89 | AMD              | Family 17h (Models 10h-1fh) Platf... | 31    | ccp        | [E2CFFB810B](<Desktop/MSI/MS-7/MS-7B89/A5E73A397722/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/E2CFFB810B>) |
| 1022:15df | 1462:7c02 | AMD              | Family 17h (Models 10h-1fh) Platf... | 30    | ccp        | [1404923301](<Desktop/MSI/MS-7/MS-7C02/B01E786348F2/FEDORA-38/6.2.12-300.FC38.X86_64/X86_64/1404923301>) |
| 8086:0f18 | 8086:2055 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 30    | mei_txe    | [CFE5E305C8](<Desktop/Intel/DN2820FYK/DN2820FYK H24582-201/21D3CC8EAEDE/DEBIAN-11/5.10.0-20-AMD64/X86_64/CFE5E305C8>) |
| 8086:0f18 | 1025:085e | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 28    | mei_txe    | [FFF64928E8](<Desktop/Acer/Aspire/Aspire XC-603/D79579C39EEC/UBUNTU-20.04/5.15.0-57-GENERIC/X86_64/FFF64928E8>) |
| 1022:1486 | 1043:8815 | AMD              | Starship/Matisse Cryptographic Co... | 27    | ccp        | [A82D805AD2](<Desktop/ASUSTek Computer/Pro/Pro WS WRX80E-SAGE SE WIFI/9D10B05EF80F/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/A82D805AD2>) |
| 1022:15df | 1462:7c95 | AMD              | Family 17h (Models 10h-1fh) Platf... | 26    | ccp        | [F677EC7E51](<Desktop/MSI/MS-7/MS-7C95/C18CCD313E94/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/F677EC7E51>) |
| 1022:1578 | 17aa:364f | AMD              | Carrizo Platform Security Processor  | 25    |            | [3AC194E77A](<Desktop/Lenovo/IdeaCentre/IdeaCentre 310S-08ASR 90G90059MW/22FBEB97AB40/LINUXMINT-21.1/5.19.0-41-GENERIC/X86_64/3AC194E77A>) |
| 8086:0f18 | 1019:7ed4 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 24    | mei_txe    | [57E454FC85](<Desktop/PCWare/IPX1800/IPX1800E2/47BCF6B10692/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/57E454FC85>) |
| 8086:2298 | 1043:8534 | Intel            | Atom/Celeron/Pentium Processor x5... | 24    | mei_txe    | [6C977806A1](<Desktop/ASUSTek Computer/All/All Series/230B95F6C08A/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/6C977806A1>) |
| 1022:1456 | 1462:7b85 | AMD              | Family 17h (Models 00h-0fh) Platf... | 22    | ccp        | [E1DA556A0B](<Desktop/MSI/MS-7/MS-7B85/ED1B7710703C/DEBIAN-12/6.2.11-3-LIQUORIX-AMD64/X86_64/E1DA556A0B>) |
| 1022:15df | 103c:8906 | AMD              | Family 17h (Models 10h-1fh) Platf... | 22    | ccp        | [3FC2C4E9D9](<Desktop/Hewlett-Packard/Pavilion/Pavilion Gaming Desktop TG01-2xxx/7E1E0DFA8D7A/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/3FC2C4E9D9>) |
| 1022:15df | 103c:87d6 | AMD              | Family 17h (Models 10h-1fh) Platf... | 20    | ccp        | [423AAC2B6F](<Desktop/Hewlett-Packard/Desktop/Desktop M01-F1xxx/8B73D4C41ECD/OPENMANDRIVA-23.90/6.2.1-DESKTOP-1OMV2390/X86_64/423AAC2B6F>) |
| 1022:1456 | 1462:7a40 | AMD              | Family 17h (Models 00h-0fh) Platf... | 17    | ccp        | [E34683F5F0](<Desktop/MSI/MS-7/MS-7A40/E158191C5B13/FEDORA-37/6.2.9-200.FC37.X86_64/X86_64/E34683F5F0>) |
| 1022:1486 | 1462:7a40 | AMD              | Starship/Matisse Cryptographic Co... | 16    | ccp        | [36574D4502](<Desktop/MSI/MS-7/MS-7A40/55163FF4F8C8/KUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/36574D4502>) |
| 1022:1578 | 103c:8265 | AMD              | Carrizo Platform Security Processor  | 16    |            | [B2C0B909F0](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 705 G3 SFF/87822041A075/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/B2C0B909F0>) |

### Entertainment encryption device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:2082 | 1022:2082 | AMD              | Geode LX AES Security Block          | 2     | geode_r... | [C256A73072](<Desktop/CompuLab/AMD/AMD CM-iGLX Geode LX-CS5536/78A905588BF8/DEBIAN-11/5.10.0-21-686/I586/C256A73072>) |

### Ethernet controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1af4:1041 | 1af4:1100 | Red Hat          | Virtio network device                | 1     | virtio_pci | [D62625A751](<Desktop/Optimized Hosting/KVM/KVM/9112EC3CC44C/ALMA-8.7/4.18.0-425.3.1.EL8.X86_64/X86_64/D62625A751>) |

### Firewire controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1106:3044 | 1043:81fe | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 1057  | firewir... | [F5499886E9](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/D04FB50B5F37/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/F5499886E9>) |
| 104c:8024 | 1458:1000 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 971   | firewir... | [FD830A3568](<Desktop/Gigabyte Technology/P35/P35-DS4/7541C3B6BD81/LINUXMINT-21/5.15.0-71-GENERIC/X86_64/FD830A3568>) |
| 1106:3044 | 1458:1000 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 374   | firewir... | [F1DEC1F586](<Desktop/Gigabyte Technology/GA-970/GA-970A-UD3/9A8304B2EB9E/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-X86_64/X86_64/F1DEC1F586>) |
| 1106:3403 | 1043:8384 | VIA Technologies | VT6315 Series Firewire Controller    | 346   | firewir... | [288E495C16](<Desktop/ASUSTek Computer/P8Z68/P8Z68 DELUXE-GEN3/21E15FDA0A80/ZORIN-16/5.15.0-71-GENERIC/X86_64/288E495C16>) |
| 1106:3044 | 1106:3044 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 304   | firewir... | [E44F7DFAC5](<Desktop/Punch Technology/PDT-702/PDT-702-1020/29C76CB9E8B7/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/E44F7DFAC5>) |
| 11c1:5811 | 1043:8294 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 281   | firewir... | [6DAA7002C8](<Desktop/ASUSTek Computer/P5/P5Q/36027F8271C2/XUBUNTU-20.04/5.4.0-146-GENERIC/X86_64/6DAA7002C8>) |
| 1102:4001 | 1102:0010 | Creative Labs    | SB Audigy FireWire Port              | 216   | firewir... | [F64F988A79](<Desktop/MSI/MS/MS-7597/7A3BD8C4DF79/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/F64F988A79>) |
| 1106:3403 | 1849:3403 | VIA Technologies | VT6315 Series Firewire Controller    | 171   | firewir... | [E8721751C6](<Desktop/ASRock/P55/P55 Extreme/450FA45F5E15/MX-21/5.10.0-22-AMD64/X86_64/E8721751C6>) |
| 104c:823f |           | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 133   | firewir... | [B68D1B92DE](<Desktop/Apple/MacPro5/MacPro5,1/E3007916032F/BLENDOS/6.2.13-ARCH1-1/X86_64/B68D1B92DE>) |
| 104c:8023 | 1043:808b | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 120   | firewir... | [FAF81C22AE](<Desktop/ASUSTek Computer/A8N-SLI/A8N-SLI Premium/8E3BF597111D/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/FAF81C22AE>) |
| 197b:2380 | 1043:8313 | JMicron Techn... | IEEE 1394 Host Controller            | 95    | firewir... | [DD2D3443A9](<Desktop/ASUSTek Computer/M4A785TD-M/M4A785TD-M EVO/B0237F5D425B/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/DD2D3443A9>) |
| 1106:3403 | 103c:2a9c | VIA Technologies | VT6315 Series Firewire Controller    | 84    | firewir... | [4ACB37F728](<Desktop/Hewlett-Packard/PPPPP-CCC#MMMMMMMM/PPPPP-CCC#MMMMMMMM/52B2452D254D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/4ACB37F728>) |
| 11c1:5811 | 103c:2a6f | LSI              | FW322/323 [TrueFire] 1394a Contro... | 84    | firewir... | [FF6049B22E](<Desktop/Hewlett-Packard/FQ515AA-ABA/FQ515AA-ABA a6620f/F964AF1529FA/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/FF6049B22E>) |
| 104c:8023 | 1043:815b | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 73    | firewir... | [D0D3458299](<Desktop/ASUSTek Computer/P5/P5B-Deluxe/8D97A918D165/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/D0D3458299>) |
| 11c1:5811 | 103c:1589 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 73    | firewir... | [BE15D33D32](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/EE9F1FE423DF/DEBIAN-12/6.1.0-8-AMD64/X86_64/BE15D33D32>) |
| 11c1:5811 | 103c:1309 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 70    | firewir... | [69C613B55F](<Desktop/Hewlett-Packard/Z400/Z400 Workstation/E7ECFF068003/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/69C613B55F>) |
| 1106:3403 | 1043:8374 | VIA Technologies | VT6315 Series Firewire Controller    | 68    | firewir... | [C174FCC2D8](<Desktop/ASUSTek Computer/M5A88-V/M5A88-V EVO/8D4188F1156E/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/C174FCC2D8>) |
| 1106:3403 | 1106:3403 | VIA Technologies | VT6315 Series Firewire Controller    | 64    | firewir... | [C6CD36EAED](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/9B277EB9411C/LINUXMINT-21.1/5.15.0-70-GENERIC/X86_64/C6CD36EAED>) |
| 104c:823f | 3412:7856 | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 52    | firewir... | [FE75C98B15](<Desktop/Gigabyte Technology/B560M/B560M DS3H V2/2C9125D64301/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/FE75C98B15>) |
| 11c1:5811 | 103c:158a | LSI              | FW322/323 [TrueFire] 1394a Contro... | 47    | firewir... | [FB7AEF7883](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/9F156C69101A/XUBUNTU-20.04/5.15.0-71-LOWLATENCY/X86_64/FB7AEF7883>) |
| 11c1:5811 | 103c:130b | LSI              | FW322/323 [TrueFire] 1394a Contro... | 45    | firewir... | [C9E99B3F8C](<Desktop/Hewlett-Packard/Z800/Z800 Workstation/5D76221FDFDA/FEDORA-37/6.2.11-200.FC37.X86_64/X86_64/C9E99B3F8C>) |
| 104c:8023 | 8086:5044 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 43    | firewir... | [C597415419](<Desktop/Intel/DP35DP/DP35DP AAD81073-207/DD3D47581CBF/UBUNTU-22.04/5.15.0-52-GENERIC/X86_64/C597415419>) |
| 1106:3044 | 1849:3044 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 42    | firewir... | [FE7531D450](<Desktop/ASRock/H55M/H55M Pro/D52431521FB2/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/FE7531D450>) |
| 11c1:5811 | 103c:130a | LSI              | FW322/323 [TrueFire] 1394a Contro... | 39    | firewir... | [49C56C77AF](<Desktop/Hewlett-Packard/Z600/Z600 Workstation/C8C77CC6EAAE/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/49C56C77AF>) |
| 1106:3044 | 1043:808a | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 35    | firewir... | [4521F2B9B4](<Desktop/ASUSTek Computer/P4/P4C800-E/52FDED7A661E/UBUNTU-UNITY-18.04/4.15.0-209-GENERIC/I686/4521F2B9B4>) |
| 11c1:5811 | 103c:158b | LSI              | FW322/323 [TrueFire] 1394a Contro... | 35    | firewir... | [EE0297B0BA](<Desktop/Hewlett-Packard/Z820/Z820 Workstation/B02938969DD1/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/EE0297B0BA>) |
| 104c:8023 | 8086:514d | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 34    | firewir... | [0A153DF418](<Desktop/Intel/DG965RY/DG965RY AAD41691-301/8F5EB35E4F9E/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/0A153DF418>) |
| 11c1:5811 | 11c1:5811 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 34    | firewir... | [1C2D1949FD](<Desktop/Gigabyte Technology/F2/F2A88XM-D3HP/0EB734537A5B/LUBUNTU-22.10/5.19.0-31-GENERIC/X86_64/1C2D1949FD>) |
| 11c1:5811 | 1028:5811 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 33    | firewir... | [1859AF08FF](<Desktop/Dell/Precision/Precision WorkStation T3500/29E352915625/LINUXMINT-19.3/5.4.0-107-GENERIC/X86_64/1859AF08FF>) |
| 11c1:5811 | 1028:8010 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 32    | firewir... | [5F16A97F99](<Desktop/Dell/Vostro/Vostro 410/22BAC971B359/ELEMENTARY-6.1/5.15.0-60-GENERIC/X86_64/5F16A97F99>) |
| 104c:8025 |           | Texas Instrum... | TSB82AA2 IEEE-1394b Link Layer Co... | 31    | firewir... | [16CAC427E3](<Desktop/Apple/MacPro1/MacPro1,1/35AFB7E133B4/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/16CAC427E3>) |
| 104c:8023 | 8086:4257 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 29    | firewir... | [0DD9E12F5A](<Desktop/Intel/DP55WB/DP55WB AAE64798-207/AAA5A40E796A/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/0DD9E12F5A>) |
| 1106:3044 | 103c:2a92 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 29    | firewir... | [F92A9CC141](<Desktop/Hewlett-Packard/AY614AA-ABA/AY614AA-ABA p6347c/F102B32DA51F/LINUXMINT-21.1/5.15.0-70-GENERIC/X86_64/F92A9CC141>) |
| 104c:8024 | 1019:8056 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 28    | firewir... | [9C746EE546](<Desktop/Acer/Aspire/Aspire T180/594F18D577C1/LINUXMINT-21.1/5.15.0-67-GENERIC/X86_64/9C746EE546>) |
| 1106:3044 | 1025:8010 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 28    | firewir... | [3CDF8244EF](<Desktop/Acer/Aspire/Aspire M5811/BD71CFB0AF65/UBUNTU-22.10/5.19.0-40-GENERIC/X86_64/3CDF8244EF>) |
| 104c:8023 | 1028:026d | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 26    | firewir... | [7AEF52516B](<Desktop/Dell/Precision/Precision WorkStation T7500/5BA9A5976E40/KUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/7AEF52516B>) |
| 197b:2380 | 197b:2380 | JMicron Techn... | IEEE 1394 Host Controller            | 26    | firewir... | [6AAEB06F9A](<Desktop/Acer/Aspire/Aspire M1200/E7440680EDB2/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/6AAEB06F9A>) |
| 11c1:5811 | 8086:2008 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 25    | firewir... | [B7B8F92DF1](<Desktop/Viglen/DQ67/DQ67SW/26E0C41D7A57/POP!_OS-22.04/6.0.12-76060006-GENERIC/X86_64/B7B8F92DF1>) |
| 104c:8023 | 1028:021d | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 24    | firewir... | [8C41F4FF91](<Desktop/Dell/Precision/Precision WorkStation T7400/FCAC0B6786A5/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/8C41F4FF91>) |
| 1106:3403 | 1025:0250 | VIA Technologies | VT6315 Series Firewire Controller    | 24    | firewir... | [A3A49836F9](<Desktop/Acer/Aspire/Aspire X3812/C5BD4A3DAADD/DEBIAN-12/6.1.0-7-AMD64/X86_64/A3A49836F9>) |
| 1106:3403 | 1028:040d | VIA Technologies | VT6315 Series Firewire Controller    | 24    | firewir... | [33723C8B80](<Desktop/Dell/Studio/Studio XPS 8100/B9889E374664/XERO-ROLLING/6.1.12-ARCH1-1/X86_64/33723C8B80>) |
| 11bd:0015 | 11bd:0022 | Pinnacle Systems | FireWire IEEE1394                    | 23    | firewir... | [2A4B061B07](<Desktop/ASUSTek Computer/P8H77-M/P8H77-M LE/959B5013F863/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.12-1-DEFAULT/X86_64/2A4B061B07>) |
| 11c1:5811 | 103c:2a6c | LSI              | FW322/323 [TrueFire] 1394a Contro... | 22    | firewir... | [75050A4D2E](<Desktop/Hewlett-Packard/KQ496AA-ABA/KQ496AA-ABA a6530f/36D7EE2F44F6/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/75050A4D2E>) |
| 1033:00f2 | 1033:00f2 | NEC Computers    | uPD72874 [Firewarden] IEEE1394a O... | 21    | firewir... | [3D6078552C](<Desktop/Medion/MS/MS-7728/A0D564B77366/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/3D6078552C>) |
| 1106:3044 | 1462:502d | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 20    | firewir... | [9126E1035F](<Desktop/Medion/MS/MS-7502/1A70778DF821/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/9126E1035F>) |
| 1106:3403 | 1025:024c | VIA Technologies | VT6315 Series Firewire Controller    | 19    | firewir... | [50EE9C3423](<Desktop/Acer/Aspire/Aspire M3800/6063C8DDD2C6/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/50EE9C3423>) |
| 197b:2380 | 2810:ac02 | JMicron Techn... | IEEE 1394 Host Controller            | 19    | firewir... | [30965E948D](<Desktop/Dell/Studio/Studio 540/A3BA6198939B/ARCH-ROLLING/6.1.10-ARCH1-1/X86_64/30965E948D>) |
| 104c:8023 | 10de:c55e | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 18    | firewir... | [91B3144C5C](<Desktop/EVGA/122/122-CK-NF68/95CF4D572FCC/KUBUNTU-22.10/5.19.0-1009-LOWLATENCY/X86_64/91B3144C5C>) |
| 1106:3044 | 1019:3044 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 18    | firewir... | [E074C61884](<Desktop/ECS/X58/X58B-A/C3427C407290/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/E074C61884>) |
| 11c1:5811 | 103c:2a50 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 18    | firewir... | [2739B3325C](<Desktop/Hewlett-Packard/GL314AA-ABZ/GL314AA-ABZ a6095.it/A22819AB8765/UBUNTU-22.10/5.19.0-31-GENERIC/X86_64/2739B3325C>) |

### Flash memory (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1524:0510 | 1524:0510 | ENE Technology   | CB710 Memory Card Reader Controller  | 2     | cb710      | [932FA70B29](<Desktop/ASUSTek Computer/P4/P4R8L/59D0EE220B98/UBUNTU-16.04/4.15.0-62-GENERIC/I686/932FA70B29>) |
| 1106:9530 | 1106:9530 | VIA Technologies | VX800/820/900 Series Secure Digit... | 1     | via_sdmmc  | [935D6B4B24](<Desktop/VXL/TC7520/TC7520d/47918240CEA7/ANTIX-22/5.10.142-ANTIX.2-AMD64-SMP/X86_64/935D6B4B24>) |
| 1524:0510 | 1043:1724 | ENE Technology   | CB710 Memory Card Reader Controller  | 1     | cb710      | [9FE6163CA2](<Desktop/ASUSTek Computer/P4/P4S8L/E8D8E2F409F1/XUBUNTU-18.04/4.15.0-74-LOWLATENCY/I686/9FE6163CA2>) |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1451 | 1022:1451 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 2136  |            | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 1002:5a23 | 1002:5a23 | AMD              | RD890S/RD990 I/O Memory Managemen... | 646   |            | [ACF61A6132](<Desktop/Gigabyte Technology/970/970A-DS3P/4209CEC662D2/OPENMANDRIVA-23.03/6.2.10-DESKTOP-2.0OMV4.9MJN/X86_64/ACF61A6132>) |
| 1022:1419 | 1022:1419 | AMD              | Family 15h (Models 10h-1fh) I/O M... | 350   |            | [53C03D6942](<Desktop/ASRock/FM2A88X/FM2A88X Extreme6+/061803342427/FEDORA-37/6.0.11-300.FC37.X86_64/X86_64/53C03D6942>) |
| 1022:1577 | 1022:1577 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 223   |            | [9369ACB33C](<Desktop/Acer/Aspire/Aspire XC-330/880DD70E3811/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/9369ACB33C>) |
| 1002:5a23 | 1462:7693 | AMD              | RD890S/RD990 I/O Memory Managemen... | 212   |            | [37F3DA239A](<Desktop/MSI/MS/MS-7693/C85B0030F9F4/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/37F3DA239A>) |
| 1022:1423 | 1022:1423 | AMD              | Family 15h (Models 30h-3fh) I/O M... | 98    |            | [850EA7C843](<Desktop/Gigabyte Technology/F2/F2A88XM-D3H/BF3B2C86ADDB/ATZ-11.7/5.10.0-22-RT-AMD64/X86_64/850EA7C843>) |
| 1022:1419 | 1462:7721 | AMD              | Family 15h (Models 10h-1fh) I/O M... | 80    |            | [14A87BC11A](<Desktop/MSI/MS/MS-7721/89882A257F09/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/14A87BC11A>) |
| 1022:1423 | 1462:7721 | AMD              | Family 15h (Models 30h-3fh) I/O M... | 69    |            | [BF4C16404E](<Desktop/MSI/MS/MS-7721/D025F0A8C3E3/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/BF4C16404E>) |
| 1022:1423 | 1043:85cb | AMD              | Family 15h (Models 30h-3fh) I/O M... | 29    |            | [7F1747C3E3](<Desktop/ASUSTek Computer/A88/A88X-PLUS/279BA270C61D/SLACKWARE-CURRENT/6.2.9-SLACK/X86_64/7F1747C3E3>) |
| 1002:5a23 | 1458:5000 | AMD              | RD890S/RD990 I/O Memory Managemen... | 24    |            | [30822E6E18](<Desktop/Gigabyte Technology/GA-990/GA-990FXA-D3/A2B3F5F4BD06/LINUXMINT-21.1/5.19.0-28-GENERIC/X86_64/30822E6E18>) |
| 1002:5a23 | 1462:7640 | AMD              | RD890S/RD990 I/O Memory Managemen... | 21    |            | [E79ACDA971](<Desktop/MSI/MS/MS-7640/31D863043AB4/GENTOO-2.13/6.2.2-GENTOO/X86_64/E79ACDA971>) |
| 1022:1419 | 1462:7895 | AMD              | Family 15h (Models 10h-1fh) I/O M... | 17    |            | [35AAFBB9DB](<Desktop/MSI/MS/MS-7895/876B7F03401A/ROSA-12.2/5.10.118-GENERIC-2ROSA2021.1-X86_64/X86_64/35AAFBB9DB>) |
| 1002:5a23 | 1462:7974 | AMD              | RD890S/RD990 I/O Memory Managemen... | 15    |            | [399DEEA7B9](<Desktop/MSI/MS/MS-7974/6E2D9DB43053/LMDE-5/5.10.0-14-AMD64/X86_64/399DEEA7B9>) |
| 1022:1419 | 1043:8526 | AMD              | Family 15h (Models 10h-1fh) I/O M... | 12    |            | [1140B33D95](<Desktop/ASUSTek Computer/K30/K30BF_M32BF_A_F_K31BF/7E70979EB61E/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/1140B33D95>) |
| 1022:1423 | 1462:7895 | AMD              | Family 15h (Models 30h-3fh) I/O M... | 11    |            | [4231780B0B](<Desktop/MSI/MS/MS-7895/4EE881F8ACA6/OPENMANDRIVA-4.90/5.18.12-DESKTOP-3OMV4090/X86_64/4231780B0B>) |
| 8086:19a2 | 15d9:0969 | Intel            | Atom Processor C3000 Series Root ... | 10    | pcieport   | [7D87907153](<Desktop/Supermicro/SYS-5019/SYS-5019A-FTN4/61D6B32F418F/ARCO-ROLLING/5.16.11-ARCH1-1/X86_64/7D87907153>) |
| 1022:1419 | 1019:7c8d | AMD              | Family 15h (Models 10h-1fh) I/O M... | 6     |            | [2D00BA463B](<Desktop/Acer/Veriton/Veriton M2110G/254C55A8EF27/FEDORA-36/5.19.8-200.FC36.X86_64/X86_64/2D00BA463B>) |
| 1022:1419 | 1025:070b | AMD              | Family 15h (Models 10h-1fh) I/O M... | 6     |            | [638079E113](<Desktop/Acer/Aspire/Aspire TC-105/540A96111DD9/LUBUNTU-20.04/5.4.0-42-GENERIC/X86_64/638079E113>) |
| 8086:19a2 | 8086:19a2 | Intel            | Atom Processor C3000 Series Root ... | 4     | pcieport   | [873CADC069](<Desktop/teleplatforms/D4/D4E4S16P8/918532270EDC/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/873CADC069>) |
| 1022:1419 | 1462:7900 | AMD              | Family 15h (Models 10h-1fh) I/O M... | 3     |            | [A0CBC39688](<Desktop/MSI/MS/MS-7900/EA733492996E/MANJARO/5.14.2-1-MANJARO/X86_64/A0CBC39688>) |
| 1022:1423 | 1462:7793 | AMD              | Family 15h (Models 30h-3fh) I/O M... | 2     |            | [709AAC26C8](<Desktop/MSI/MS/MS-7793/042C82450FB8/OPENMANDRIVA-4.50/5.12.4-DESKTOP-1OMV4050/X86_64/709AAC26C8>) |
| 1022:1419 | 17aa:36a0 | AMD              | Family 15h (Models 10h-1fh) I/O M... | 1     |            | [BA1A484E84](<Desktop/Lenovo/H50-55/H50-55 90BG000XRS/94482FE57B53/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-I586/I686/BA1A484E84>) |
| 8086:19a2 | 1849:19a2 | Intel            | Atom Processor C3000 Series Root ... | 1     |            | [D563EB82AE](<Desktop/ASRockRack/C3558/C3558D4I-4L/DF49EDAF85B3/DEBIAN-11/5.10.0-9-AMD64/X86_64/D563EB82AE>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0412 | 1458:d000 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 678   | i915       | [22BD54D6D1](<Desktop/Gigabyte Technology/Z87/Z87X-UD3H/F9D737247AAE/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/22BD54D6D1>) |
| 10de:128b | 1462:8c93 | Nvidia           | GK208B [GeForce GT 710]              | 639   | nvidia     | [33B7A6BA7C](<Desktop/MSI/MS-7/MS-7B33/34289ECA4E14/LINUXMINT-21.1/5.19.0-41-GENERIC/X86_64/33B7A6BA7C>) |
| 8086:0412 | 1043:8534 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 465   | i915       | [2DA8FF7129](<Desktop/ASUSTek Computer/All/All Series/55E374A7ECC4/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/2DA8FF7129>) |
| 1002:67df | 1da2:e366 | AMD              | Ellesmere [Radeon RX 470/480/570/... | 420   | amdgpu     | [F5499886E9](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/D04FB50B5F37/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/F5499886E9>) |
| 1002:15d8 | 1002:15d8 | AMD              | Picasso/Raven 2 [Radeon Vega Seri... | 327   | amdgpu     | [2B273EE426](<Desktop/ASRock/A320M-DVS/A320M-DVS R4.0/E6ECD35BA999/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/2B273EE426>) |
| 8086:1912 | 1043:8694 | Intel            | HD Graphics 530                      | 318   | i915       | [BBFD29FB88](<Desktop/ASUSTek Computer/D320/D320SF/A7E6ADB389B1/UBUNTU-20.04/5.4.0-148-GENERIC/X86_64/BBFD29FB88>) |
| 8086:0102 | 1043:844d | Intel            | 2nd Generation Core Processor Fam... | 309   | i915       | [6C96DBE3F3](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX/CC2C86F5F25E/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/6C96DBE3F3>) |
| 1002:15dd | 1002:15dd | AMD              | Raven Ridge [Radeon Vega Series /... | 279   | amdgpu     | [B650F0A26E](<Desktop/MSI/MS-7/MS-7B84/484C99892AE1/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/B650F0A26E>) |
| 1002:9616 | 1043:8388 | AMD              | RS780L [Radeon 3000]                 | 274   | radeon     | [B561C005C5](<Desktop/ASUSTek Computer/M4/M4A78LT-M-LE/6D321C87E95D/UBUNTU-18.04/4.15.0-210-GENERIC/I686/B561C005C5>) |
| 8086:0152 | 1458:d000 | Intel            | Xeon E3-1200 v2/3rd Gen Core proc... | 272   | i915       | [6DA1DDCEF5](<Desktop/Gigabyte Technology/Z77/Z77M-D3H/49F546000BB1/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/6DA1DDCEF5>) |
| 8086:0102 | 1458:d000 | Intel            | 2nd Generation Core Processor Fam... | 267   | i915       | [CD95F8EC71](<Desktop/Gigabyte Technology/H61/H61M-S2-B3/D90805DD4D74/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/CD95F8EC71>) |
| 1002:67df | 1682:c580 | AMD              | Ellesmere [Radeon RX 470/480/570/... | 266   | amdgpu     | [F86E67C005](<Desktop/Gigabyte Technology/Z97/Z97-D3H/A009D543E318/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/F86E67C005>) |
| 10de:1c82 | 1462:8c96 | Nvidia           | GP107 [GeForce GTX 1050 Ti]          | 248   | nvidia     | [A72531BD2D](<Desktop/MouseComputer/B75/B75M-D3V-JP/041627593BC4/LINUXMINT-18.3/4.8.0-58-GENERIC/X86_64/A72531BD2D>) |
| 10de:1d01 | 1462:8c98 | Nvidia           | GP108 [GeForce GT 1030]              | 248   | nvidia     | [9A420C42DE](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3/ABA4EBB5D0B8/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-X86_64/X86_64/9A420C42DE>) |
| 1002:67df | 1da2:e353 | AMD              | Ellesmere [Radeon RX 470/480/570/... | 229   | amdgpu     | [B9D976AE11](<Desktop/ASUSTek Computer/ROG/ROG STRIX X570-E GAMING/8CED5CE61807/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/B9D976AE11>) |
| 1002:1638 | 1002:1636 | AMD              | Cezanne [Radeon Vega Series / Rad... | 221   | amdgpu     | [F677EC7E51](<Desktop/MSI/MS-7/MS-7C95/C18CCD313E94/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/F677EC7E51>) |
| 8086:5912 | 1043:8694 | Intel            | HD Graphics 630                      | 220   | i915       | [45B0EB3060](<Desktop/ASUSTek Computer/H110/H110M-A-M.2/9F16281D8B3C/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/45B0EB3060>) |
| 1002:67df | 1462:3418 | AMD              | Ellesmere [Radeon RX 470/480/570/... | 207   | amdgpu     | [A9D1794EEC](<Desktop/MSI/MS-7/MS-7A38/C3487D76EFD3/FEDORA-36/6.1.8-100.FC36.X86_64/X86_64/A9D1794EEC>) |
| 8086:3e92 | 1043:8694 | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 207   | i915       | [4E928C0B98](<Desktop/ByteSpeed/Value/Value H310I/338311B6F6FC/LINUXMINT-21/5.15.0-71-GENERIC/X86_64/4E928C0B98>) |
| 1002:15d8 | 1043:876b | AMD              | Picasso/Raven 2 [Radeon Vega Seri... | 198   | amdgpu     | [CAF5CBC634](<Desktop/ASUSTek Computer/PRIME/PRIME B550-PLUS/271CDE20E3D3/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/CAF5CBC634>) |
| 1002:15dd | 1043:876b | AMD              | Raven Ridge [Radeon Vega Series /... | 192   | amdgpu     | [A375533DAA](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-K/A2EE7FB360B4/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/A375533DAA>) |
| 8086:0152 | 1028:0577 | Intel            | Xeon E3-1200 v2/3rd Gen Core proc... | 191   | i915       | [B8281F77A3](<Desktop/Dell/OptiPlex/OptiPlex 7010/F3C38BD709A2/BLENDOS/6.3.1-ARCH1-1/X86_64/B8281F77A3>) |
| 8086:2e32 | 1043:836d | Intel            | 4 Series Chipset Integrated Graph... | 180   | i915       | [D5456946BB](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LE/8FE632A39CF5/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D5456946BB>) |
| 1002:9616 | 1458:d000 | AMD              | RS780L [Radeon 3000]                 | 177   | radeon     | [6873C6D2AA](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 6.0/1A43554F5A40/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/6873C6D2AA>) |
| 8086:0412 | 1028:05a4 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 177   | i915       | [5BC5CCDCAD](<Desktop/Dell/OptiPlex/OptiPlex 9020/E9FD17DAA8B2/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/5BC5CCDCAD>) |
| 8086:0152 | 1043:844d | Intel            | Xeon E3-1200 v2/3rd Gen Core proc... | 176   | i915       | [425F1A3E08](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LE-BR/6CEFD305F134/LINUXMINT-19.3/4.15.0-209-GENERIC/X86_64/425F1A3E08>) |
| 1002:1638 | 1043:8809 | AMD              | Cezanne [Radeon Vega Series / Rad... | 174   | amdgpu     | [D58E08C9AB](<Desktop/ASUSTek Computer/PRIME/PRIME B550-PLUS/1C885144C28F/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/D58E08C9AB>) |
| 1002:67df | 1462:341b | AMD              | Ellesmere [Radeon RX 470/480/570/... | 174   | amdgpu     | [C88845AE9B](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/F6418012BC03/GENTOO-2.13/6.3.1-GENTOO-POLARIS/X86_64/C88845AE9B>) |
| 8086:29c2 | 1043:82b0 | Intel            | 82G33/G31 Express Integrated Grap... | 172   | i915       | [F48937493D](<Desktop/ASUSTek Computer/P5/P5KPL-AM/6DBC48DA6B2A/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-X86_64/X86_64/F48937493D>) |
| 10de:0a65 |           | Nvidia           | GT218 [GeForce 210]                  | 169   | nouveau    | [B927834A03](<Desktop/Hewlett-Packard/Compaq/Compaq dc7800 Small Form Factor/A3D50758DB46/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B927834A03>) |
| 10de:1c82 | 10de:1c82 | Nvidia           | GP107 [GeForce GTX 1050 Ti]          | 163   | nvidia     | [87E972803C](<Desktop/Gigabyte Technology/B450/B450 AORUS M/0E4430B16F5F/MANJARO-22.1.1/6.1.26-1-MANJARO/X86_64/87E972803C>) |
| 10de:13c2 | 1462:3160 | Nvidia           | GM204 [GeForce GTX 970]              | 159   | nvidia     | [7F20E3160B](<Desktop/ASUSTek Computer/P6X58D/P6X58D PREMIUM/7F3ECE887101/GENTOO-2.13/6.1.19-GENTOO-X86_64/X86_64/7F20E3160B>) |
| 10de:03d6 | 1849:03d6 | Nvidia           | C61 [GeForce 7025 / nForce 630a]     | 157   | nouveau    | [1F3953650C](<Desktop/ASRock/N68-VS3/N68-VS3 FX/D968CA13888E/LOC-OS-22/5.10.165-LOC-OS/X86_64/1F3953650C>) |
| 8086:2e12 | 1028:0420 | Intel            | 4 Series Chipset Integrated Graph... | 157   | i915       | [B585380BC4](<Desktop/Dell/OptiPlex/OptiPlex 780/8DA70E0A4BDE/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/B585380BC4>) |
| 8086:2e13 | 1028:0420 | Intel            | 4 Series Chipset Integrated Graph... | 157   |            | [B585380BC4](<Desktop/Dell/OptiPlex/OptiPlex 780/8DA70E0A4BDE/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/B585380BC4>) |
| 8086:041e | 1458:d000 | Intel            | 4th Generation Core Processor Fam... | 155   | i915       | [92C9651E22](<Desktop/Gigabyte Technology/H81/H81M-H/ED2F93691993/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/92C9651E22>) |
| 8086:0402 | 1458:d000 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 154   | i915       | [3D24B75A10](<Desktop/Gigabyte Technology/B85/B85M-HD3/2B9E52E4DAC8/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/3D24B75A10>) |
| 8086:0412 | 1849:0412 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 153   | i915       | [E85B3E34B0](<Desktop/ASRock/H87/H87 Pro4/52E5D87FB454/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/E85B3E34B0>) |
| 8086:0402 | 1043:8534 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 150   | i915       | [46A27A7551](<Desktop/ASUSTek Computer/All/All Series/BFB1E6375FB0/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.10-1-DEFAULT/X86_64/46A27A7551>) |
| 10de:0640 |           | Nvidia           | G96C [GeForce 9500 GT]               | 149   | nouveau    | [077CED1A40](<Desktop/Gigabyte Technology/G41/G41M-Combo/C0AF1F15163C/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/077CED1A40>) |
| 8086:0162 | 1043:84ca | Intel            | IvyBridge GT2 [HD Graphics 4000]     | 146   | i915       | [2E828158E5](<Desktop/ASUSTek Computer/P8Z77-M/P8Z77-M PRO/280EA6CE3F5C/UBUNTU-18.04/5.4.0-135-GENERIC/X86_64/2E828158E5>) |
| 8086:29c2 | 1458:d000 | Intel            | 82G33/G31 Express Integrated Grap... | 146   | i915       | [0C45FC6929](<Desktop/Gigabyte Technology/G31/G31M-ES2C/52FE3FCEB44F/OPENMANDRIVA-4.50/5.19.5-DESKTOP-1OMV4090/X86_64/0C45FC6929>) |
| 8086:1912 | 1458:d000 | Intel            | HD Graphics 530                      | 144   | i915       | [61D04B0E4C](<Desktop/Gigabyte Technology/H110/H110M-S2V-CF/336397A7FCB2/BLACKPANTHER-OS-18.1/5.15.85-DESKTOP-1BP/X86_64/61D04B0E4C>) |
| 10de:0a65 | 1462:8094 | Nvidia           | GT218 [GeForce 210]                  | 143   | nouveau    | [7FFA9C83D7](<Desktop/Acer/Extensa/Extensa M2610/B0C498D142D4/FEDORA-36/6.0.15-200.FC36.X86_64/X86_64/7FFA9C83D7>) |
| 8086:041e | 1043:8534 | Intel            | 4th Generation Core Processor Fam... | 139   | i915       | [01578538EB](<Desktop/ASUSTek Computer/All/All Series/ECE87AAEEF53/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/01578538EB>) |
| 8086:0412 | 103c:1998 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 138   | i915       | [2ED500D3E9](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/4A54E9E0D620/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/2ED500D3E9>) |
| 8086:3e92 | 1458:d000 | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 138   | i915       | [E44F7DFAC5](<Desktop/Punch Technology/PDT-702/PDT-702-1020/29C76CB9E8B7/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/E44F7DFAC5>) |
| 8086:2e32 | 1458:d000 | Intel            | 4 Series Chipset Integrated Graph... | 137   | i915       | [89464DDC07](<Desktop/Gigabyte Technology/G41/G41MT-S2/8D8C36115671/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/89464DDC07>) |
| 8086:0152 | 1043:84ca | Intel            | Xeon E3-1200 v2/3rd Gen Core proc... | 133   | i915       | [623FF14300](<Desktop/ASUSTek Computer/P8H77-V/P8H77-V LE/EA0A5CA24B56/ROSA-12.3/5.15.79-GENERIC-1ROSA2021.1-X86_64/X86_64/623FF14300>) |
| 10de:128b | 10de:118b | Nvidia           | GK208B [GeForce GT 710]              | 130   | nouveau    | [93A11302FB](<Desktop/Others/Others/Others/0FF37B6BAA24/DEBIAN-11/5.10.0-22-AMD64/X86_64/93A11302FB>) |

### I/o card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10e8:80d8 |           | Applied Micro... | PCI-7200 40MB/s 32-channels Digit... | 1     |            | [3864E6C70F](<Desktop/ASUSTek Computer/All/All Series/D016B43870A7/ROSA-2014.1/3.14.25-NRJ-DESKTOP-1ROSA/I686/3864E6C70F>) |

### Input device controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1102:7002 | 1102:0020 | Creative Labs    | SB Live! Game Port                   | 234   | emu10k1_gp | [46A87A6448](<Desktop/Compaq/NP185AAR-ABA/NP185AAR-ABA CQ5110F/0B653A0F876B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/46A87A6448>) |
| 1102:7003 | 1102:0040 | Creative Labs    | SB Audigy Game Port                  | 169   | emu10k1_gp | [F64F988A79](<Desktop/MSI/MS/MS-7597/7A3BD8C4DF79/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/F64F988A79>) |
| 1102:7003 | 1102:0060 | Creative Labs    | SB Audigy Game Port                  | 27    | emu10k1_gp | [B872A779AF](<Desktop/Others/775i65/775i65G/93452C525705/ZORIN-15/5.4.0-131-GENERIC/I686/B872A779AF>) |
| 1102:7004 | 1102:1003 | Creative Labs    | [SB Live! Value] Input device con... | 11    | emu10k1_gp | [657F888891](<Desktop/Hewlett-Packard/xw4600/xw4600 Workstation/4EA5596F6352/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/657F888891>) |
| 1319:0802 | 1319:1319 | Fortemedia       | Xwave QS3000A [FM801 game port]      | 9     | fm801_gp   | [66223D6EF0](<Desktop/ASUSTek Computer/P5/P5KPL-VM-S/0FDF3772C4F4/ELEMENTARY-5.1.7/5.4.0-113-GENERIC/X86_64/66223D6EF0>) |
| 1102:7005 | 1102:1002 | Creative Labs    | SB Audigy LS Game Port               | 7     | emu10k1_gp | [07A45BCFEF](<Desktop/ASUSTek Computer/All/All Series/0C2401AC106C/DEBIAN-11/5.10.0-15-AMD64/X86_64/07A45BCFEF>) |
| 127a:4312 | 1235:4312 | Rockwell Inte... | Riptide PCI Game Controller          | 1     | snd_rip... | [34867AD122](<Desktop/Supermicro/P4/P4DMS/7EDE05DEDB9F/LINUXMINT-19.1/4.15.0-139-GENERIC/I686/34867AD122>) |

### Iommu (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1481 | 1022:1481 | AMD              | Starship/Matisse IOMMU               | 2599  |            | [19C318242F](<Desktop/Others/Others/Others/C3C1AB1B873D/UBUNTU-20.04/5.15.0-1023-NVIDIA/X86_64/19C318242F>) |
| 1022:15d1 | 1022:15d1 | AMD              | Raven/Raven2 IOMMU                   | 1437  |            | [2A09FB1D81](<Desktop/Gigabyte Technology/B450M/B450M DS3H/93E61F10B914/LINUXMINT-20.3/5.4.0-148-GENERIC/X86_64/2A09FB1D81>) |
| 1022:1481 | 1043:87c0 | AMD              | Starship/Matisse IOMMU               | 1298  |            | [4A8C2101E8](<Desktop/ASUSTek Computer/PRIME/PRIME X570-PRO/D1E7CA404339/DEBIAN-11/5.10.0-22-AMD64/X86_64/4A8C2101E8>) |
| 1022:1451 | 1043:8747 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 1209  |            | [D9A3AFA732](<Desktop/ASUSTek Computer/ROG/ROG STRIX X470-I GAMING/133421F6DBD4/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/D9A3AFA732>) |
| 1022:1481 | 1043:8808 | AMD              | Starship/Matisse IOMMU               | 737   |            | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 1022:1631 | 1022:1631 | AMD              | Renoir/Cezanne IOMMU                 | 503   |            | [AE040331E6](<Desktop/Gigabyte Technology/B550M/B550M DS3H/BD5F281A2678/LINUXMINT-20.3/5.15.0-56-GENERIC/X86_64/AE040331E6>) |
| 1022:1631 | 1043:8809 | AMD              | Renoir/Cezanne IOMMU                 | 248   |            | [D58E08C9AB](<Desktop/ASUSTek Computer/PRIME/PRIME B550-PLUS/1C885144C28F/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/D58E08C9AB>) |
| 1022:15d1 | 1043:876b | AMD              | Raven/Raven2 IOMMU                   | 240   |            | [369BF3DC68](<Desktop/CMS Computers/7200/7200-5413A/68D04878595E/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/369BF3DC68>) |
| 1022:1481 | 1462:7c02 | AMD              | Starship/Matisse IOMMU               | 174   |            | [3A7E1532DA](<Desktop/MSI/MS-7/MS-7C02/ACF3D9051F49/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/3A7E1532DA>) |
| 1022:14d9 | 1043:8877 | AMD              | Family 19h IOMMU Controller          | 124   |            | [29B2378B4B](<Desktop/ASUSTek Computer/ROG/ROG STRIX B650E-F GAMING WIFI/B82AA0B20AA7/NIXOS-22.11/6.1.27/X86_64/29B2378B4B>) |
| 1022:1481 | 1462:7b86 | AMD              | Starship/Matisse IOMMU               | 119   |            | [8AA973E0F5](<Desktop/MSI/MS-7/MS-7B86/E575FEE21E0B/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/8AA973E0F5>) |
| 1022:1451 | 1462:7c02 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 94    |            | [0B4FAAA32E](<Desktop/MSI/MS-7/MS-7C02/1C6B1A3D4456/ARCH-ROLLING/6.2.9-273-TKG-CFS/X86_64/0B4FAAA32E>) |
| 1022:1451 | 1462:7b86 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 79    |            | [51EF82C2FD](<Desktop/MSI/MS-7/MS-7B86/F09A19A83CF0/MANJARO/5.13.19-2-MANJARO/X86_64/51EF82C2FD>) |
| 1022:1481 | 1462:7b89 | AMD              | Starship/Matisse IOMMU               | 77    |            | [7560923404](<Desktop/MSI/MS-7/MS-7B89/9DE5683930C4/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/7560923404>) |
| 1022:1481 | 1462:7c35 | AMD              | Starship/Matisse IOMMU               | 74    |            | [B2311E7CAC](<Desktop/MSI/MS-7/MS-7C35/CB298ECF07E8/ZORIN-16/5.15.0-69-GENERIC/X86_64/B2311E7CAC>) |
| 1022:1419 | 103c:1850 | AMD              | Family 15h (Models 10h-1fh) I/O M... | 62    |            | [FA2FA68792](<Desktop/Hewlett-Packard/Compaq/Compaq Pro 6305 MT/0B6D065E23A2/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/FA2FA68792>) |
| 1022:1481 | 1462:7c94 | AMD              | Starship/Matisse IOMMU               | 59    |            | [26C158DF39](<Desktop/MSI/MS-7/MS-7C94/DD638739FE3A/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/26C158DF39>) |
| 1022:1481 | 1462:7c95 | AMD              | Starship/Matisse IOMMU               | 56    |            | [76748DA9CD](<Desktop/MSI/MS-7/MS-7C95/E2E66E37A3EB/FEDORA-38/6.2.12-300.FC38.X86_64/X86_64/76748DA9CD>) |
| 1022:1451 | 1462:7a38 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 54    |            | [A9D1794EEC](<Desktop/MSI/MS-7/MS-7A38/C3487D76EFD3/FEDORA-36/6.1.8-100.FC36.X86_64/X86_64/A9D1794EEC>) |
| 1022:1631 | 1043:87e1 | AMD              | Renoir/Cezanne IOMMU                 | 53    |            | [812906148B](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550M-PLUS/205744F95212/KUBUNTU-22.04/5.15.0-70-GENERIC/X86_64/812906148B>) |
| 1022:1481 | 1043:87cb | AMD              | Starship/Matisse IOMMU               | 48    |            | [B2AC72F8D9](<Desktop/ASUSTek Computer/PRIME/PRIME TRX40-PRO S/777303348731/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/B2AC72F8D9>) |
| 1022:1481 | 1462:7a38 | AMD              | Starship/Matisse IOMMU               | 47    |            | [A05BD1FFA7](<Desktop/MSI/MS-7/MS-7A38/D9678E934A75/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/A05BD1FFA7>) |
| 1022:1481 | 1043:87e2 | AMD              | Starship/Matisse IOMMU               | 39    |            | [98FFA037D9](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550M-PLUS/00BADF5270D7/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/98FFA037D9>) |
| 1022:1451 | 1462:7b89 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 38    |            | [691239A442](<Desktop/MSI/MS-7/MS-7B89/D27AFC4010A4/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/691239A442>) |
| 1022:1481 | 1462:7b85 | AMD              | Starship/Matisse IOMMU               | 36    |            | [B2782D28F7](<Desktop/MSI/MS-7/MS-7B85/A1797BB6666C/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/B2782D28F7>) |
| 1022:1631 | 1462:7c95 | AMD              | Renoir/Cezanne IOMMU                 | 26    |            | [F677EC7E51](<Desktop/MSI/MS-7/MS-7C95/C18CCD313E94/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/F677EC7E51>) |
| 1022:1577 | 17aa:364f | AMD              | Family 15h (Models 60h-6fh) I/O M... | 25    |            | [3AC194E77A](<Desktop/Lenovo/IdeaCentre/IdeaCentre 310S-08ASR 90G90059MW/22FBEB97AB40/LINUXMINT-21.1/5.19.0-41-GENERIC/X86_64/3AC194E77A>) |
| 1022:14d9 | 1022:14d9 | AMD              | Family 19h IOMMU Controller          | 24    |            | [A17449F761](<Desktop/ASRock/X670E/X670E Pro RS/F993F20C9215/GENTOO-2.13/6.3.1-GENTOO-X86_64/X86_64/A17449F761>) |
| 1022:1451 | 1462:7b85 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 22    |            | [E1DA556A0B](<Desktop/MSI/MS-7/MS-7B85/ED1B7710703C/DEBIAN-12/6.2.11-3-LIQUORIX-AMD64/X86_64/E1DA556A0B>) |
| 1022:14b6 | 1022:14b6 | AMD              | Family 17h-19h IOMMU                 | 22    |            | [BB189B2507](<Desktop/Micro Computer (HK) Tech Limited/UM/UM690/74269EC20F30/GARUDA-SOARING/6.2.11-ZEN1-1-ZEN/X86_64/BB189B2507>) |
| 1022:1423 | 17aa:36a0 | AMD              | Family 15h (Models 30h-3fh) I/O M... | 21    |            | [562426633D](<Desktop/Lenovo/H50-55/H50-55 90BF005HAU/6CCC9060F12E/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/562426633D>) |
| 1022:15d1 | 1462:7b86 | AMD              | Raven/Raven2 IOMMU                   | 19    |            | [21091D13E4](<Desktop/MSI/MS-7/MS-7B86/A8F7FD200798/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/21091D13E4>) |
| 1022:1423 | 103c:2215 | AMD              | Family 15h (Models 30h-3fh) I/O M... | 18    |            | [27B339EFE1](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 705 G1 SFF/1DEB913965B9/LINUXMINT-20.3/5.4.0-147-GENERIC/X86_64/27B339EFE1>) |
| 1022:1451 | 1028:07ee | AMD              | Family 17h (Models 00h-0fh) I/O M... | 18    |            | [E6F49BBE8A](<Desktop/Dell/Inspiron/Inspiron 5675/3F0EB1245B68/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/E6F49BBE8A>) |
| 1022:1451 | 1462:7a40 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 17    |            | [E34683F5F0](<Desktop/MSI/MS-7/MS-7A40/E158191C5B13/FEDORA-37/6.2.9-200.FC37.X86_64/X86_64/E34683F5F0>) |
| 1022:1481 | 1043:8815 | AMD              | Starship/Matisse IOMMU               | 16    |            | [B9D321C70E](<Desktop/ASUSTek Computer/Pro/Pro WS WRX80E-SAGE SE WIFI/B272374D9B3C/DEBIAN-11/5.13.19-6-PVE/X86_64/B9D321C70E>) |
| 1022:1481 | 1462:7a40 | AMD              | Starship/Matisse IOMMU               | 16    |            | [36574D4502](<Desktop/MSI/MS-7/MS-7A40/55163FF4F8C8/KUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/36574D4502>) |
| 1022:1631 | 1458:1000 | AMD              | Renoir/Cezanne IOMMU                 | 16    |            | [9D7F6DE46C](<Desktop/Gigabyte Technology/GB-BRR7/GB-BRR7H-4700/11B5F2106D43/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/9D7F6DE46C>) |
| 1022:1631 | 1462:7c96 | AMD              | Renoir/Cezanne IOMMU                 | 16    |            | [B5F4A1670F](<Desktop/MSI/MS-7/MS-7C96/1A1D3A52C6E9/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/B5F4A1670F>) |
| 1022:1481 | 17aa:1046 | AMD              | Starship/Matisse IOMMU               | 15    |            | [B9C30FBAF8](<Desktop/Lenovo/ThinkStation/ThinkStation P620 30E0CTO1WW/9520CD2366BB/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/B9C30FBAF8>) |
| 1022:1631 | 1462:7c94 | AMD              | Renoir/Cezanne IOMMU                 | 15    |            | [F91AC46CFD](<Desktop/MSI/MS-7/MS-7C94/2A845C780ADD/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/F91AC46CFD>) |
| 1022:15d1 | 1462:7b89 | AMD              | Raven/Raven2 IOMMU                   | 13    |            | [0335729036](<Desktop/MSI/MS-7/MS-7B89/1228469F9CD7/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/0335729036>) |
| 1022:1451 | 1462:7b87 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 11    |            | [CB57237789](<Desktop/MSI/MS-7/MS-7B87/8E7CD7B47843/KDE-NEON-22.04/5.19.0-38-GENERIC/X86_64/CB57237789>) |
| 1022:1481 | 1462:7c34 | AMD              | Starship/Matisse IOMMU               | 11    |            | [DE10599614](<Desktop/MSI/MS-7/MS-7C34/5D2513ABB3B1/GENTOO-2.9/6.0.8-GENTOO-HARAMBE-EDITION/X86_64/DE10599614>) |
| 1022:1631 | 1462:7a38 | AMD              | Renoir/Cezanne IOMMU                 | 11    |            | [76338F95EA](<Desktop/MSI/MS-7/MS-7A38/2D6303B1B082/DEBIAN-11/6.2.6-1-PVE/X86_64/76338F95EA>) |
| 1022:164f | 1043:8815 | AMD              | Milan IOMMU                          | 11    |            | [A82D805AD2](<Desktop/ASUSTek Computer/Pro/Pro WS WRX80E-SAGE SE WIFI/9D10B05EF80F/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/A82D805AD2>) |
| 1022:1423 | 1025:0904 | AMD              | Family 15h (Models 30h-3fh) I/O M... | 10    |            | [A3D030FDC2](<Desktop/Acer/Aspire/Aspire TC-280/D55FFCCC274D/UBUNTU-22.10/5.19.0-26-GENERIC/X86_64/A3D030FDC2>) |
| 1022:1451 | 103c:8433 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 10    |            | [E885F0469C](<Desktop/Hewlett-Packard/595/595-P0569NG/95CC7F0B57CC/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.10-1-DEFAULT/X86_64/E885F0469C>) |
| 1022:1481 | 1462:7d53 | AMD              | Starship/Matisse IOMMU               | 10    |            | [DF59296148](<Desktop/MSI/MS-7/MS-7D53/97B840A65E4D/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/DF59296148>) |
| 1022:14d9 | 1462:7d75 | AMD              | Family 19h IOMMU Controller          | 10    |            | [99745BE007](<Desktop/MSI/MS-7/MS-7D75/EAD3B1F0F0E8/CACHYOS/6.3.0-4-CACHYOS-BORE/X86_64/99745BE007>) |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:816c | 103c:8464 | Realtek Semic... | RTL8111xP IPMI interface             | 14    |            | [AC8AD5D3D5](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 705 G4 DM 35W/7A68E0F037A1/FEDORA-38/6.2.12-300.FC38.X86_64/X86_64/AC8AD5D3D5>) |
| 10ec:816c | 1849:8168 | Realtek Semic... | RTL8111xP IPMI interface             | 11    | ipmi_si    | [DF056EC6F1](<Desktop/ASRock/4X4-4000/4X4-4000 Series/512CE5A79924/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/DF056EC6F1>) |
| 10ec:816c | 10ec:0123 | Realtek Semic... | RTL8111xP IPMI interface             | 7     |            | [71C0A5ABE5](<Desktop/ASRock/B85M/B85M DASH-OL R2.0/1E8B2DFD9FC0/CACHYOS/6.1.7-ZEN1-1.1-ZEN/X86_64/71C0A5ABE5>) |
| 10ec:816c | 1025:1248 | Realtek Semic... | RTL8111xP IPMI interface             | 5     |            | [8F27F893B1](<Desktop/Acer/Veriton/Veriton N4660G/1D0217C4F432/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/8F27F893B1>) |
| 10ec:816c | 103c:8461 | Realtek Semic... | RTL8111xP IPMI interface             | 4     |            | [078E151AFC](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 705 G4 MT/6C77281AB913/REBORNOS/6.1.8-ARCH1-1/X86_64/078E151AFC>) |
| 10ec:816c | 103c:8463 | Realtek Semic... | RTL8111xP IPMI interface             | 4     |            | [A2DC0FC924](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 705 G4 SFF/EE1C1FE97CD1/OPENMANDRIVA-4.3/5.16.13-DESKTOP-1OMV4003/X86_64/A2DC0FC924>) |
| 10ec:816c | 1019:81ea | Realtek Semic... | RTL8111xP IPMI interface             | 3     |            | [1B14CACE5C](<Desktop/Positivo/POS-EAA75/POS-EAA75DE/F1E3C68C2143/DEBIAN-11/5.10.0-10-AMD64/X86_64/1B14CACE5C>) |
| 10ec:816c | 1025:080a | Realtek Semic... | RTL8111xP IPMI interface             | 3     |            | [C486FBF03F](<Desktop/Acer/Veriton/Veriton L4630G/D6F20EC5AD21/ARCH/5.13.4-ARCH2-1/X86_64/C486FBF03F>) |
| 10ec:816c | 1025:1166 | Realtek Semic... | RTL8111xP IPMI interface             | 3     |            | [3392DD3C90](<Desktop/Acer/Veriton/Veriton N4640G/F3B546A66DF5/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/3392DD3C90>) |
| 10ec:816c | 103c:8618 | Realtek Semic... | RTL8111xP IPMI interface             | 3     |            | [6976CAF9ED](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 705 G5 SFF/DCCF39A2F7DA/MANJARO-21.2.3/5.15.19-1-MANJARO/X86_64/6976CAF9ED>) |
| 10ec:816c | 103c:8626 | Realtek Semic... | RTL8111xP IPMI interface             | 3     |            | [F2098A2414](<Desktop/Hewlett-Packard/ProDesk/ProDesk 405 G4 Desktop Mini/1EE5229291BF/STEAMOS-3.4/5.13.0-VALVE21.3-1-NEPTUNE/X86_64/F2098A2414>) |
| 10ec:816c | 17aa:30fd | Realtek Semic... | RTL8111xP IPMI interface             | 3     |            | [07E9099105](<Desktop/Lenovo/ThinkCentre/ThinkCentre M715q 10M2A00YLS/0B86B5EDCD5F/ZORIN-16/5.15.0-71-GENERIC/X86_64/07E9099105>) |
| 10ec:816c | 17aa:3148 | Realtek Semic... | RTL8111xP IPMI interface             | 3     |            | [F66C33020E](<Desktop/Lenovo/ThinkCentre/ThinkCentre M75s-1 11AAS24H00/05EB42D84A2A/KUBUNTU-22.10/5.19.0-30-GENERIC/X86_64/F66C33020E>) |
| 10ec:816c | 1b0a:00e5 | Realtek Semic... | RTL8111xP IPMI interface             | 3     |            | [1ECE615E2D](<Desktop/Pegatron/SM/SM 3330B/DF938F1DF66F/UBUNTU-22.10/5.19.0-37-GENERIC/X86_64/1ECE615E2D>) |
| 10ec:816c | 1025:1005 | Realtek Semic... | RTL8111xP IPMI interface             | 2     |            | [DD3E15FEEE](<Desktop/Acer/Veriton/Veriton X4640G/8169F352B6C1/OPENMANDRIVA-23.03/6.2.2-DESKTOP-1OMV2390/X86_64/DD3E15FEEE>) |
| 10ec:816c | 1043:85b5 | Realtek Semic... | RTL8111xP IPMI interface             | 2     |            | [B2ACFA6E70](<Desktop/Medion/Pentino_H-Series/Pentino_H-Series A_SFF_B85-2/EE1FB1D878EB/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/B2ACFA6E70>) |
| 10ec:816c | 1b0a:01bb | Realtek Semic... | RTL8111xP IPMI interface             | 2     |            | [0842FC186B](<Desktop/Positivo/Master/Master D610/D9B156D6A27B/LINUXMINT-21/5.15.0-67-GENERIC/X86_64/0842FC186B>) |
| 10ec:816c | 1025:074c | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [5AE13B415D](<Desktop/Acer/Veriton/Veriton N4620G/C783DEDB4A53/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/5AE13B415D>) |
| 10ec:816c | 1025:078d | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [504EC0D230](<Desktop/Acer/Veriton/Veriton X4630G/5F5430A7A7A0/XUBUNTU-20.04/5.4.0-39-GENERIC/X86_64/504EC0D230>) |
| 10ec:816c | 1025:1001 | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [0ACD5D08F8](<Desktop/Acer/Veriton/Veriton X4110G/ED941D450F51/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/0ACD5D08F8>) |
| 10ec:816c | 1025:1069 | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [CCA454D1BD](<Desktop/Acer/Veriton/Veriton NBU/967CB3582FEC/XUBUNTU-22.04/5.15.0-56-GENERIC/X86_64/CCA454D1BD>) |
| 10ec:816c | 1025:1180 | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [8BB734CD2F](<Desktop/Acer/Veriton/Veriton M4650G/3878CC2A668F/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/8BB734CD2F>) |
| 10ec:816c | 1025:124c | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [8EB6F7795D](<Desktop/Acer/Veriton/Veriton X4660G/5BB5028F59A0/UBUNTU-20.10/5.8.0-29-GENERIC/X86_64/8EB6F7795D>) |
| 10ec:816c | 1025:1427 | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [0B85F95C4C](<Desktop/Acer/Veriton/Veriton N4670G/DD62274C13C5/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/0B85F95C4C>) |
| 10ec:816c | 1025:1514 | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [4198835011](<Desktop/Acer/Veriton/Veriton N4680GT/61E19777E3BE/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.1.10-1-DEFAULT/X86_64/4198835011>) |
| 10ec:816c | 103c:83e8 | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [C79A0CC45E](<Desktop/Hewlett-Packard/ProDesk/ProDesk 405 G4 SFF/8E8EA5F25068/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/C79A0CC45E>) |
| 10ec:816c | 1462:7830 | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [F52A53F4A7](<Desktop/MSI/MS/MS-7830/6AD0194C1A8F/OPENMANDRIVA-4.50/5.19.5-DESKTOP-1OMV4090/X86_64/F52A53F4A7>) |
| 10ec:816c | 1734:1216 | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [A960AEF3AE](<Desktop/Fujitsu/ESPRIMO/ESPRIMO Q556/1AD973A9C5ED/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/A960AEF3AE>) |
| 10ec:816c | 17aa:3141 | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [F19B15E3D2](<Desktop/Lenovo/ThinkCentre/ThinkCentre M725s 10VTCTO1WW/7A4167EEDFF1/UBUNTU-20.04/5.8.0-38-GENERIC/X86_64/F19B15E3D2>) |
| 10ec:816c | 17aa:318e | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [436D55C73E](<Desktop/Lenovo/ThinkCentre/ThinkCentre M75t Gen 2 11KC000RCK/8624D4E3709B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/436D55C73E>) |
| 8086:108e | 1734:108d | Intel            | 82573E KCS (Active Management)       | 1     | ipmi_si    | [CCA0170CC9](<Desktop/Fujitsu Siemens/ESPRIMO/ESPRIMO E/93AC91EE8165/XUBUNTU-16.04/4.15.0-88-GENERIC/I686/CCA0170CC9>) |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:816c | 10ec:8168 | Realtek Semic... | RTL8111xP IPMI interface             | 36    | ipmi_si    | [895855ED9A](<Desktop/ASUSTek Computer/Pro/Pro WS X570-ACE/7D768ECED733/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/895855ED9A>) |
| 103c:3302 | 103c:3305 | Hewlett-Packard  | Integrated Lights-Out Standard KC... | 32    | ipmi_si    | [B0000FC633](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML350 G5/77953FD39EDF/UBUNTU-20.04/5.4.0-144-GENERIC/X86_64/B0000FC633>) |
| 10ec:816c | 1458:e000 | Realtek Semic... | RTL8111xP IPMI interface             | 17    | ipmi_si    | [26E8D46D94](<Desktop/Itautec/Infoway/Infoway ST-4265/DF39346CA0E8/FEDORA-37/6.0.7-301.FC37.X86_64/X86_64/26E8D46D94>) |
| 10ec:816c | 17aa:3089 | Realtek Semic... | RTL8111xP IPMI interface             | 16    | ipmi_si    | [C4603A155E](<Desktop/Lenovo/ThinkCentre/ThinkCentre M78 10BS0006MS/087ADC9A1A8C/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/C4603A155E>) |
| 10ec:816c | 1734:1178 | Realtek Semic... | RTL8111xP IPMI interface             | 13    | ipmi_si    | [BDB1E8C4A7](<Desktop/Fujitsu/CELSIUS/CELSIUS R670-2/82B2C619D946/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/BDB1E8C4A7>) |
| 10ec:816c | 1025:078b | Realtek Semic... | RTL8111xP IPMI interface             | 9     |            | [7FBA52EF43](<Desktop/Acer/Veriton/Veriton M4630G/E4696C88AC98/OPENMANDRIVA-4.50/5.19.12-DESKTOP-2OMV4090/X86_64/7FBA52EF43>) |
| 10ec:816c | 17aa:30b2 | Realtek Semic... | RTL8111xP IPMI interface             | 7     | ipmi_si    | [14C0F082D8](<Desktop/Lenovo/ThinkCentre/ThinkCentre M79 10CTS07500/6A9BC77472F0/UBUNTU-22.10/5.19.0-23-GENERIC/X86_64/14C0F082D8>) |
| 8086:108e | 8086:0000 | Intel            | 82573E KCS (Active Management)       | 6     | ipmi_si    | [2ACFD9617B](<Desktop/Intel/S3000AHLX/S3000AHLX D40858-208/2922366B6C9A/UBUNTU-20.04/5.4.0-77-GENERIC/X86_64/2ACFD9617B>) |
| 10ec:816c | 1043:8578 | Realtek Semic... | RTL8111xP IPMI interface             | 1     | ipmi_si    | [C248800623](<Desktop/ASUSTek Computer/F2/F2A85-M2/7651312890DC/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/C248800623>) |
| 10ec:816c | 10ec:816c | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [A3ECB14C0C](<Desktop/Fujitsu/CELSIUS/CELSIUS M470/7B545C06267B/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/A3ECB14C0C>) |

### Isdn adapter (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1244:0e00 | 1244:0e00 | AVM              | Fritz!Card PCI v2.0 ISDN             | 11    | fcpci      | [4548DE054F](<Desktop/ASRock/Z68/Z68 Extreme4 Gen3/C7DB098F4720/LINUXMINT-20.3/5.15.0-58-GENERIC/X86_64/4548DE054F>) |
| 1244:0a00 | 1244:0a00 | AVM              | A1 ISDN [Fritz]                      | 9     | fcpci      | [B342CD8FE0](<Desktop/Gigabyte Technology/GA-78/GA-78LMT-S2P/3519BE130F38/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/B342CD8FE0>) |
| 1048:1000 | 1048:1000 | Elsa             | QuickStep 1000                       | 1     |            | [4622016059](<Desktop/Medion/MS/MS-7318/04DDF3A09383/DEBIAN-11/5.10.0-19-AMD64/X86_64/4622016059>) |
| 1050:6692 | 16ec:3409 | Winbond Elect... | W6692                                | 1     | w6692      | [B67E414D65](<Desktop/ASUSTek Computer/M2/M2N-TE/FE36EC0A6334/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/B67E414D65>) |
| 1133:e00b | 1133:e00b | Dialogic         | Diva ISDN PCI 2.02                   | 1     |            | [AC7FD78AB8](<Desktop/Gigabyte Technology/965/965P-DS3/49A022364CAD/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/AC7FD78AB8>) |
| 1397:2bd0 | 1075:c101 | Cologne Chip ... | ISDN network controller [HFC-PCI]    | 1     | hfcpci     | [BE977291B5](<Desktop/Biostar/GF8200C/GF8200C M2+/6FA0FEDC4385/LINUXMINT-19.3/5.4.0-86-GENERIC/X86_64/BE977291B5>) |
| 1397:2bd0 | 1397:2bd0 | Cologne Chip ... | ISDN network controller [HFC-PCI]    | 1     | hfcpci     | [83A7C8B23F](<Desktop/ASRock/970/970 Pro3 R2.0/6B5CB24CB9EB/ROSA-2016.1/4.15.0-DESKTOP-60.7ROSA-X86_64/X86_64/83A7C8B23F>) |
| e159:0001 | 795e:0001 | Tiger Jet Net... | Tiger3XX Modem/ISDN interface        | 1     | wcte11xp   | [FE13415AC0](<Desktop/Dell/Vostro/Vostro 3670/6972435545F1/UBUNTU-18.04/4.15.0-135-GENERIC/X86_64/FE13415AC0>) |
| e159:0001 | 79fe:0001 | Tiger Jet Net... | Tiger3XX Modem/ISDN interface        | 1     | wcte11xp   | [B6E88B98F7](<Desktop/Dell/Vostro/Vostro 3670/62A337642D43/UBUNTU-18.04/4.15.0-1065-OEM/X86_64/B6E88B98F7>) |
| e159:0001 | 9100:0001 | Tiger Jet Net... | Tiger3XX Modem/ISDN interface        | 1     | netjet     | [74F31779A2](<Desktop/Gigabyte Technology/M68/M68MT-S2P/7C8ED4277CFD/XUBUNTU-20.04/5.8.0-43-GENERIC/X86_64/74F31779A2>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a36f | 8086:7270 | Intel            | Cannon Lake PCH Shared SRAM          | 1117  |            | [19D78D1685](<Desktop/Gigabyte Technology/Z390/Z390 UD/8E72A411386D/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/19D78D1685>) |
| 8086:a121 | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 1112  |            | [BBFD29FB88](<Desktop/ASUSTek Computer/D320/D320SF/A7E6ADB389B1/UBUNTU-20.04/5.4.0-148-GENERIC/X86_64/BBFD29FB88>) |
| 8086:a2a1 | 1043:8694 | Intel            | 200 Series/Z370 Chipset Family Po... | 776   |            | [536E6E7CC9](<Desktop/ASUSTek Computer/STRIX/STRIX B250I GAMING/BB9A16765525/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/536E6E7CC9>) |
| 8086:a2a1 | 1458:5001 | Intel            | 200 Series/Z370 Chipset Family Po... | 689   |            | [E44F7DFAC5](<Desktop/Punch Technology/PDT-702/PDT-702-1020/29C76CB9E8B7/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/E44F7DFAC5>) |
| 8086:a121 | 1458:5001 | Intel            | 100 Series/C230 Series Chipset Fa... | 628   |            | [8C5B603452](<Desktop/Gigabyte Technology/Z170X-Gaming/Z170X-Gaming 7/F95579DE4AF1/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/8C5B603452>) |
| 8086:a36f | 1043:8694 | Intel            | Cannon Lake PCH Shared SRAM          | 608   |            | [14C71828CA](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-F GAMING/5D29F2B9EBFF/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/14C71828CA>) |
| 8086:43ef |           | Intel            | Tiger Lake-H Shared SRAM             | 589   |            | [80B16A8567](<Desktop/ASRock/B560/B560M-ITX-ac/43B5A145EA88/FEDORA-37/6.2.14-200.FC37.X86_64/X86_64/80B16A8567>) |
| 10de:03f5 | 1849:03eb | Nvidia           | MCP61 Memory Controller              | 538   |            | [DCF5CD4CA2](<Desktop/ASRock/N68C-GS/N68C-GS FX/CD0566A64BB2/FEDORA-37/6.2.14-200.FC37.X86_64/X86_64/DCF5CD4CA2>) |
| 10de:03e2 | 1849:03e2 | Nvidia           | MCP61 Host Bridge                    | 495   |            | [DCF5CD4CA2](<Desktop/ASRock/N68C-GS/N68C-GS FX/CD0566A64BB2/FEDORA-37/6.2.14-200.FC37.X86_64/X86_64/DCF5CD4CA2>) |
| 8086:7aa7 |           | Intel            | Alder Lake-S PCH Shared SRAM         | 356   | vfio_pci   | [1F232288D7](<Desktop/ASRock/Z690/Z690M-ITX-ax/FA892D909FAE/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/1F232288D7>) |
| 8086:43ef | 1043:8694 | Intel            | Tiger Lake-H Shared SRAM             | 338   |            | [DE65A79BF1](<Desktop/ASUSTek Computer/TUF/TUF Gaming B560M-PLUS/929B4939E2C7/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/DE65A79BF1>) |
| 8086:a2a1 | 1849:a2a1 | Intel            | 200 Series/Z370 Chipset Family Po... | 293   |            | [D905BABC43](<Desktop/ASRock/B250/B250M-HDV/A65B4BC89A4A/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/D905BABC43>) |
| 8086:a121 | 1849:a121 | Intel            | 100 Series/C230 Series Chipset Fa... | 292   |            | [A38BF561F7](<Desktop/ASRock/Z170/Z170 Gaming K4/19138DC977DF/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/A38BF561F7>) |
| 10de:03f5 | 1458:0c11 | Nvidia           | MCP61 Memory Controller              | 275   |            | [D571B75547](<Desktop/Gigabyte Technology/M68/M68MT-S2/333806208DA6/ZORIN-16/5.15.0-71-GENERIC/X86_64/D571B75547>) |
| 8086:06ef | 8086:7270 | Intel            | Comet Lake PCH Shared SRAM           | 255   |            | [655BBE4068](<Desktop/Gigabyte Technology/H470M/H470M K/8DA375D4ED1A/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/655BBE4068>) |
| 8086:7aa7 | 1043:8694 | Intel            | Alder Lake-S PCH Shared SRAM         | 246   |            | [401DB07B93](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z690-A GAMING WIFI D4/46556BD3958D/DEBIAN-12/6.1.0-7-AMD64/X86_64/401DB07B93>) |
| 8086:a2a1 | 1043:872f | Intel            | 200 Series/Z370 Chipset Family Po... | 245   |            | [D53CE13AA3](<Desktop/ASUSTek Computer/STRIX/STRIX Z270F GAMING/6DEFE4E23C63/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/D53CE13AA3>) |
| 8086:a36f | 1849:a36f | Intel            | Cannon Lake PCH Shared SRAM          | 192   |            | [AC982522AB](<Desktop/ASRock/B360M/B360M IB-R1/6EDAE1870B25/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/AC982522AB>) |
| 10de:03e2 | 1043:83a4 | Nvidia           | MCP61 Host Bridge                    | 187   |            | [0C3F2AF7AD](<Desktop/ASUSTek Computer/M4N68T-M/M4N68T-M LE/7BD4E80F3F5C/LINUXMINT-18.3/4.10.0-38-GENERIC/X86_64/0C3F2AF7AD>) |
| 10de:03f5 | 1043:83a4 | Nvidia           | MCP61 Memory Controller              | 187   |            | [0C3F2AF7AD](<Desktop/ASUSTek Computer/M4N68T-M/M4N68T-M LE/7BD4E80F3F5C/LINUXMINT-18.3/4.10.0-38-GENERIC/X86_64/0C3F2AF7AD>) |
| 8086:a3a1 | 1043:8694 | Intel            | Cannon Lake PCH Power Management ... | 168   |            | [147006A71F](<Desktop/ASUSTek Computer/PRIME/PRIME H410M-A/A5F891271BF2/LINUXMINT-20.2/5.4.0-137-GENERIC/X86_64/147006A71F>) |
| 8086:06ef | 1043:8694 | Intel            | Comet Lake PCH Shared SRAM           | 152   |            | [1EDDB3203A](<Desktop/ASUSTek Computer/PRIME/PRIME Z490-A/27EB1FCAC7E3/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/1EDDB3203A>) |
| 10de:03ea | 1458:5001 | Nvidia           | MCP61 Memory Controller              | 146   |            | [25D436D2CB](<Desktop/Gigabyte Technology/M61/M61SME-S2/4E8023AF4AAC/KUBUNTU-22.04/5.15.0-43-GENERIC/X86_64/25D436D2CB>) |
| 10de:03ea | 10de:cb84 | Nvidia           | MCP61 Memory Controller              | 145   |            | [46995D58EB](<Desktop/MSI/MS/MS-7309/DD03196ECF8C/XUBUNTU-22.10/5.19.0-1017-LOWLATENCY/X86_64/46995D58EB>) |
| 10de:03ea | 1043:8234 | Nvidia           | MCP61 Memory Controller              | 138   |            | [7EEAD8BD18](<Desktop/ASUSTek Computer/M2/M2N-MX/8AF34A7AE9F0/ROSA-12.3/5.10.150-GENERIC-1ROSA2021.1-X86_64/X86_64/7EEAD8BD18>) |
| 10de:03f5 | 1043:8234 | Nvidia           | MCP61 Memory Controller              | 138   |            | [7EEAD8BD18](<Desktop/ASUSTek Computer/M2/M2N-MX/8AF34A7AE9F0/ROSA-12.3/5.10.150-GENERIC-1ROSA2021.1-X86_64/X86_64/7EEAD8BD18>) |
| 8086:a2a1 | 1043:873c | Intel            | 200 Series/Z370 Chipset Family Po... | 131   |            | [1C9E5EE2A6](<Desktop/ASUSTek Computer/WS/WS X299 SAGE/7F377E5958FC/LINUXMINT-20.3/5.19.0-17.2-LIQUORIX-AMD64/X86_64/1C9E5EE2A6>) |
| 10de:03e2 | 1458:5001 | Nvidia           | MCP61 Host Bridge                    | 130   |            | [D571B75547](<Desktop/Gigabyte Technology/M68/M68MT-S2/333806208DA6/ZORIN-16/5.15.0-71-GENERIC/X86_64/D571B75547>) |
| 8086:a121 | 1462:7996 | Intel            | 100 Series/C230 Series Chipset Fa... | 130   |            | [D63BC9AECA](<Desktop/MSI/MS/MS-7996/30F694CCEC2B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D63BC9AECA>) |
| 10de:005e | 1043:815a | Nvidia           | CK804 Memory Controller              | 108   |            | [870BBA0C09](<Desktop/ASUSTek Computer/M2/M2N4-SLI/6C43B2D62FB4/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/870BBA0C09>) |
| 8086:a3a1 | 1458:5001 | Intel            | Cannon Lake PCH Power Management ... | 97    |            | [6116C0DF52](<Desktop/Gigabyte Technology/H410M/H410M H/370152E34E95/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/6116C0DF52>) |
| 8086:a121 | 1734:121d | Intel            | 100 Series/C230 Series Chipset Fa... | 94    |            | [77150D1166](<Desktop/Fujitsu/ESPRIMO/ESPRIMO P557/9D728F491894/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/77150D1166>) |
| 8086:a121 | 1028:06b9 | Intel            | 100 Series/C230 Series Chipset Fa... | 90    |            | [08DF3C35EE](<Desktop/Dell/OptiPlex/OptiPlex 7040/74B9A8608B3A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/08DF3C35EE>) |
| 10de:03f5 | 1462:7309 | Nvidia           | MCP61 Memory Controller              | 89    |            | [D7C60C4667](<Desktop/MSI/MS/MS-7309/E6B9DC0A77FA/LINUXMINT-20.3/5.4.0-148-GENERIC/X86_64/D7C60C4667>) |
| 10de:0568 | 1043:82f2 | Nvidia           | MCP78S [GeForce 8200] Memory Cont... | 88    |            | [246492391C](<Desktop/ASUSTek Computer/M3/M3N78-VM/D58483C6966C/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/246492391C>) |
| 10de:0751 | 1043:82f2 | Nvidia           | MCP78S [GeForce 8200] Memory Cont... | 88    |            | [246492391C](<Desktop/ASUSTek Computer/M3/M3N78-VM/D58483C6966C/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/246492391C>) |
| 10de:0754 | 1043:82f2 | Nvidia           | MCP78S [GeForce 8200] Memory Cont... | 88    |            | [246492391C](<Desktop/ASUSTek Computer/M3/M3N78-VM/D58483C6966C/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/246492391C>) |
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 87    |            | [68E1C1B5A4](<Desktop/Others/Others/Others/0401B4CF51F2/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/68E1C1B5A4>) |
| 8086:4def | 8086:7270 | Intel            | Jasper Lake Shared SRAM Controller   | 78    |            | [D7EE12A01B](<Desktop/AZW/MINI/MINI S/53CF20A09429/ROCKY-9.1/5.14.0-70.26.1.EL9_0.X86_64/X86_64/D7EE12A01B>) |
| 10de:03f5 | 1565:3407 | Nvidia           | MCP61 Memory Controller              | 74    |            | [3B25AAD650](<Desktop/Biostar/N68/N68S3B/5854B17EC602/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/3B25AAD650>) |
| 8086:a2a1 | 1028:07a1 | Intel            | 200 Series/Z370 Chipset Family Po... | 74    |            | [11E8FB1ECD](<Desktop/Dell/OptiPlex/OptiPlex 7050/460F8DE765A3/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/11E8FB1ECD>) |
| 8086:a121 | 1462:7971 | Intel            | 100 Series/C230 Series Chipset Fa... | 71    |            | [DA2D2D3D5C](<Desktop/MSI/MS/MS-7971/14F264169A02/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/DA2D2D3D5C>) |
| 8086:a121 | 1462:7a15 | Intel            | 100 Series/C230 Series Chipset Fa... | 71    |            | [AF27E2497A](<Desktop/MSI/MS-7/MS-7A15/C35BC5B871B3/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/AF27E2497A>) |
| 8086:a2a1 | 1028:07a3 | Intel            | 200 Series/Z370 Chipset Family Po... | 70    |            | [974CB924D5](<Desktop/Dell/OptiPlex/OptiPlex 3050/0A14953B346E/SIDUCTION-12/6.2.13-1-SIDUCTION-AMD64/X86_64/974CB924D5>) |
| 8086:9d21 | 8086:7270 | Intel            | Sunrise Point-LP PMC                 | 69    |            | [18DCBA612C](<Desktop/Others/Others/Others/9654B0B310BA/DEBIAN-11/5.10.0-22-AMD64/X86_64/18DCBA612C>) |
| 10de:03a9 |           | Nvidia           | C55 Memory Controller                | 68    |            | [70D5FD7A1D](<Desktop/ASUSTek Computer/P5NT/P5NT WS/C5D5F5260F3A/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/70D5FD7A1D>) |
| 10de:03aa |           | Nvidia           | C55 Memory Controller                | 68    |            | [70D5FD7A1D](<Desktop/ASUSTek Computer/P5NT/P5NT WS/C5D5F5260F3A/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/70D5FD7A1D>) |
| 10de:03ab |           | Nvidia           | C55 Memory Controller                | 68    |            | [70D5FD7A1D](<Desktop/ASUSTek Computer/P5NT/P5NT WS/C5D5F5260F3A/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/70D5FD7A1D>) |
| 10de:03b4 |           | Nvidia           | C55 Memory Controller                | 68    |            | [70D5FD7A1D](<Desktop/ASUSTek Computer/P5NT/P5NT WS/C5D5F5260F3A/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/70D5FD7A1D>) |
| 10de:03bc |           | Nvidia           | C55 Memory Controller                | 68    |            | [70D5FD7A1D](<Desktop/ASUSTek Computer/P5NT/P5NT WS/C5D5F5260F3A/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/70D5FD7A1D>) |

### Modem (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1057:3052 | 1057:3020 | Motorola         | SM56 Data Fax Modem                  | 35    |            | [0399613500](<Desktop/Dell/OptiPlex/OptiPlex 380/4453CDB166E7/ZORIN-16/5.15.0-58-GENERIC/X86_64/0399613500>) |
| 1106:3068 |           | VIA Technologies | AC'97 Modem Controller               | 19    | snd_via... | [504CBC919C](<Desktop/ASUSTek Computer/K8/K8V-MXG/2F9455B0679A/XUBUNTU-18.04/4.15.0-166-GENERIC/I686/504CBC919C>) |
| 11c1:044c | 11c1:044c | LSI              | LT WinModem                          | 18    |            | [D975325F4B](<Desktop/Supermicro/C7/C7H61/FD27E1E53D44/KUBUNTU-22.04/5.19.0-40-GENERIC/X86_64/D975325F4B>) |
| 8086:1040 | 8086:1000 | Intel            | 536EP Data Fax Modem                 | 7     |            | [F2CC8FAE4D](<Desktop/Gigabyte Technology/GA-990/GA-990FXA-UD3/F46DFB4BD862/LINUXMINT-18.3/4.15.0-136-GENERIC/X86_64/F2CC8FAE4D>) |
| 1106:3068 | 1019:0c04 | VIA Technologies | AC'97 Modem Controller               | 4     | snd_via... | [CAAB4A3B82](<Desktop/ECS/P4/P4M800-M/16B269C3988B/ZORIN-15/5.0.0-37-GENERIC/I686/CAAB4A3B82>) |
| 134d:7892 | 134d:0001 | PCTel            | HSP MicroModem 56                    | 4     | serial     | [6C9B4F5E0B](<Desktop/ASUSTek Computer/M4/M4A78LT-M-LE/D489B8FA6164/LINUXMINT-19.1/4.15.0-55-GENERIC/I686/6C9B4F5E0B>) |
| 1543:3052 | 1543:3000 | SILICON Labor... | Intel 537 [Winmodem]                 | 4     |            | [B6ADDF8D7B](<Desktop/Intel/DG31PR/DG31PR AAE39516-304/12C2AC77223D/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/B6ADDF8D7B>) |
| 11c1:0440 | 11c1:0440 | LSI              | 56k WinModem                         | 3     |            | [2700C74BD9](<Desktop/MSI/MS/MS-7142/3021660CC547/LMDE-4/4.19.0-17-686/I686/2700C74BD9>) |
| 11c1:044e | 1235:044e | LSI              | LT WinModem                          | 3     |            | [B7C62FC4A8](<Desktop/Intel/D410PT/D410PT AAE76528-404/6BAB04DC1328/CENTOS-7/3.10.0-1160.66.1.EL7.X86_64/X86_64/B7C62FC4A8>) |
| 2003:8800 | 16ef:2800 | Smart Link       | LM-I56N                              | 3     |            | [38A44BB08B](<Desktop/Dell/OptiPlex/OptiPlex 380/448D0EBB2689/ZORIN-15/5.4.0-136-GENERIC/I686/38A44BB08B>) |
| 1039:7013 | 1584:4003 | Silicon Integ... | AC'97 Modem Controller               | 2     |            | [E9BC9B3C8A](<Desktop/Uniwill/255KI-259KI/255KI-259KI Series/EEB62031AFFE/UBUNTU-UNITY-18.04/4.15.0-136-GENERIC/I686/E9BC9B3C8A>) |
| 10b9:5459 | 10a5:5459 | ULi Electronics  | SmartLink SmartPCI561 56K Modem      | 2     | serial     | [03C53827B5](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/DBFA4C837F96/UBUNTU-22.10/5.19.0-29-GENERIC/X86_64/03C53827B5>) |
| 11c1:044e | 11c1:044e | LSI              | LT WinModem                          | 2     |            | [DA6AB84289](<Desktop/Gigabyte Technology/P35/P35-S3G/EAF9127EDADE/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/DA6AB84289>) |
| 134d:7890 | 134d:0001 | PCTel            | HSP MicroModem 56                    | 2     | serial     | [332DDF27C1](<Desktop/Dell/OptiPlex/OptiPlex GX520/EE629D2C3445/UBUNTU-20.04/5.8.0-44-GENERIC/X86_64/332DDF27C1>) |
| 2003:8800 | 1801:2800 | Smart Link       | LM-I56N                              | 2     |            | [62AFB6C0F6](<Desktop/ASUSTek Computer/P5/P5LD2/A299608340A5/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/62AFB6C0F6>) |
| 8086:1080 | 1028:1000 | Intel            | FA82537EP 56K V.92 Data/Fax Modem... | 2     | serial     | [DC13BE448C](<Desktop/Dell/Dimension/Dimension 8400/3CFC1B6A6425/KDE-NEON-20.04/5.4.0-64-GENERIC/X86_64/DC13BE448C>) |
| 8086:27dd |           | Intel            | 82801G (ICH7 Family) AC'97 Modem ... | 2     |            | [78AA035121](<Desktop/Acer/Veriton/Veriton M275/D4328CAC9A6E/LINUXMINT-19.3/5.4.0-77-GENERIC/X86_64/78AA035121>) |
| 1002:4378 | 103c:3085 | AMD              | IXP SB400 AC'97 Modem Controller     | 1     | snd_ati... | [46E47F957D](<Desktop/Hewlett-Packard/Presario/Presario R4100/36F4F69E2F33/XUBUNTU-18.04/5.3.0-40-GENERIC/I686/46E47F957D>) |
| 1039:7013 | 1025:0083 | Silicon Integ... | AC'97 Modem Controller               | 1     |            | [985DA6D3F5](<Desktop/Acer/Aspire/Aspire 5000/02E4136BFB6D/UBUNTU-18.04/5.0.0-25-GENERIC/X86_64/985DA6D3F5>) |
| 1039:7013 | 104d:8128 | Silicon Integ... | AC'97 Modem Controller               | 1     | snd_int... | [72A578315E](<Desktop/Sony/PCV-RZ/PCV-RZ22G/EC12851CCD15/ROSA-2014.1/4.1.13-NRJ-DESKTOP-1ROSA-I586/I686/72A578315E>) |
| 1039:7013 | 1631:3003 | Silicon Integ... | AC'97 Modem Controller               | 1     | snd_int... | [A787298BDB](<Desktop/NEC Computers/SiS/SiS650/7CE5CC095A09/ROSA-2016.1/5.4.32-GENERIC-2ROSA-I586/I686/A787298BDB>) |
| 1039:7013 | 1849:9739 | Silicon Integ... | AC'97 Modem Controller               | 1     | snd_int... | [B311270C22](<Desktop/American Megatrends/K7/K7S41GX/BCE17FAE0D5C/DEBIAN-9/4.9.0-18-686-PAE/I686/B311270C22>) |
| 1057:3052 | 1631:3034 | Motorola         | SM56 Data Fax Modem                  | 1     |            | [B7CEC1644D](<Desktop/Packard Bell/ISTART/ISTART 2057/A338E4EBDE41/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-I586/I686/B7CEC1644D>) |
| 10b9:5457 | 10cf:130f | ULi Electronics  | M5457 AC'97 Modem Controller         | 1     |            | [347EB6B747](<Desktop/Fujitsu/FMVCE50/FMVCE50M7/9040365FD95B/XUBUNTU-18.04/4.15.0-20-LOWLATENCY/I686/347EB6B747>) |
| 10b9:545a | 2020:545a | ULi Electronics  | SmartLink SmartPCI563 56K Modem      | 1     | serial     | [2A51E0D9E9](<Desktop/ASUSTek Computer/All/All Series/D5864207F64F/ARCH-ROLLING/5.12.14-ZEN1-1-ZEN/X86_64/2A51E0D9E9>) |
| 1106:3068 | 1019:2122 | VIA Technologies | AC'97 Modem Controller               | 1     | snd_via... | [25BB71984B](<Desktop/ECS/P4/P4M800PRO-M2/7738DCAC02BA/ROSA-2014.1/4.1.15-NRJ-DESKTOP-1ROSA-I586/I686/25BB71984B>) |
| 11c1:0441 | 122d:4100 | LSI              | 56k WinModem                         | 1     |            | [FF00693839](<Desktop/eMachines/ET/ET1331G/0231998FA6F8/ZORIN-16/5.15.0-67-GENERIC/X86_64/FF00693839>) |
| 11c1:0449 | 1468:0410 | LSI              | L56xM+S [Mars-2] WinModem 56k        | 1     |            | [A8A13EFBA0](<Desktop/ASUSTek Computer/Rampage/Rampage III GENE/8C776A32D051/ROSA-2012.1/3.10.34-NRJ-DESKTOP-3ROSA/X86_64/A8A13EFBA0>) |
| 11c1:044e | 11c1:044c | LSI              | LT WinModem                          | 1     |            | [EF7F30CC40](<Desktop/Gigabyte Technology/945/945PL-S3/4E59D9F0C11A/ZORIN-15/5.4.0-107-GENERIC/I686/EF7F30CC40>) |
| 11c1:044e | 13e0:0401 | LSI              | LT WinModem                          | 1     |            | [E9ACA9663F](<Desktop/Hewlett-Packard/Compaq/Compaq dc5100 SFF/27389494A67A/LINUXMINT-19.2/4.15.0-72-GENERIC/I686/E9ACA9663F>) |
| 11c1:0450 | 144f:1515 | LSI              | LT WinModem                          | 1     |            | [32D5B1A614](<Desktop/Compaq/Evo/Evo D310/13A7627BC6B9/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-I586/I686/32D5B1A614>) |
| 134d:2189 | 134d:1002 | PCTel            | HSP56 MicroModem                     | 1     | serial     | [348AF6C202](<Desktop/ASUSTek Computer/PRIME/PRIME H310-PLUS R2.0/90A887D251E7/UBUNTU-18.04/5.4.0-107-GENERIC/X86_64/348AF6C202>) |
| 134d:7897 | 134d:0001 | PCTel            | HSP MicroModem 56                    | 1     | serial     | [329D1B25C3](<Desktop/Compaq/5410/5410US/BC54498BE203/DEBIAN-11/5.10.0-13-686-PAE/I686/329D1B25C3>) |
| 163c:3052 | 14fe:0005 | Smart Link       | SmartLink SmartPCI562 56K Modem      | 1     | serial     | [9939882441](<Desktop/Gateway/GT3022/GT3022B/3883F2A482E8/UBUNTU-18.04/4.15.0-65-GENERIC/I686/9939882441>) |
| 2000:2800 | 122d:2800 | Smart Link       | SmartPCI2800 V.92 PCI Soft DFT       | 1     |            | [3BC558699A](<Desktop/ASUSTek Computer/P5KPL-AM/P5KPL-AM SE/C6F9622C38FE/UBUNTU-20.04/5.4.0-70-GENERIC/X86_64/3BC558699A>) |
| 2000:2800 | 163c:2800 | Smart Link       | SmartPCI2800 V.92 PCI Soft DFT       | 1     |            | [9DEE04D2CB](<Desktop/ASUSTek Computer/P5/P5LD2-TVM-SE/BB9F1005A687/UBUNTU-18.04/4.15.0-62-GENERIC/X86_64/9DEE04D2CB>) |
| 8086:1040 | 16be:1040 | Intel            | 536EP Data Fax Modem                 | 1     |            | [8853D92523](<Desktop/MSI/MS/MS-6701/A877AE1FD01A/ZORIN-15/5.4.0-109-GENERIC/I686/8853D92523>) |
| 8086:1080 | 8086:1000 | Intel            | FA82537EP 56K V.92 Data/Fax Modem... | 1     | serial     | [6DF95E6042](<Desktop/ASUSTek Computer/M4/M4N68T-M-LE-V2/A3BAF3C7689D/ROSA-2014.1/4.1.25-NRJ-DESKTOP-1ROSA-X86_64/X86_64/6DF95E6042>) |
| 8086:24d6 | 104d:816f | Intel            | 82801EB/ER (ICH5/ICH5R) AC'97 Mod... | 1     |            | [AB742E4CF2](<Desktop/Sony/VGC-V2/VGC-V2S/F8D5977D285E/ZORIN-15/5.4.0-58-GENERIC/I686/AB742E4CF2>) |
| 8086:266d |           | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 1     |            | [D8653C0683](<Desktop/Others/Others/Others/547B1B1EA048/UBUNTU-MATE-18.04/5.3.0-62-GENERIC/I686/D8653C0683>) |
| 8086:266d | 14f1:5423 | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 1     | snd_int... | [1D936DA792](<Desktop/Dell/Dimension/Dimension 4700c/7F5C89E3867E/DEBIAN-TESTING/5.9.0-5-686-PAE/I686/1D936DA792>) |

### Multimedia (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0002:8290 | 0004:0000 |                  |                                      | 1     |            | [95D420F37F](<Desktop/ASUSTek Computer/P5/P5L1394/FCA97337163E/UBUNTU-18.10/4.18.0-10-GENERIC/X86_64/95D420F37F>) |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15e2 | 1022:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 227   | snd_pci... | [B9F947FEC3](<Desktop/BESSTAR Tech/DMAF/DMAF5/E2C64EAEE3A5/DEBIAN-11/5.15.94-X86/X86_64/B9F947FEC3>) |
| 109e:0878 |           | Brooktree        | Bt878 Audio Capture                  | 36    |            | [D0847FB118](<Desktop/ASUSTek Computer/A7/A7N8X-E/1BD0885D5B4D/LUBUNTU-18.04/4.15.0-206-GENERIC/I686/D0847FB118>) |
| 1022:15e2 | 103c:8433 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 29    | snd_pci... | [911F2844C9](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop 590-p0xxx/417C4293D639/POP!_OS-22.04/6.2.8-060208-GENERIC/X86_64/911F2844C9>) |
| 11bd:bede | 11bd:0022 | Pinnacle Systems | AV/DV Studio Capture Card            | 24    |            | [2A4B061B07](<Desktop/ASUSTek Computer/P8H77-M/P8H77-M LE/959B5013F863/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.12-1-DEFAULT/X86_64/2A4B061B07>) |
| 1131:7164 | 0070:8851 | Philips Semic... | SAA7164                              | 22    | saa7164    | [AB7B403321](<Desktop/Apple/MacPro3/MacPro3,1/3212D6A73605/UBUNTU-18.04/5.4.0-1472304060810-GENERIC/X86_64/AB7B403321>) |
| 12ab:0380 | 1cfa:0006 | YUAN High-Tec... | Game Capture 4K60 Pro                | 19    |            | [85EF5EAF43](<Desktop/Gigabyte Technology/970A-DS3P/970A-DS3P FX/9B3DEDFACB7F/STEAMOS-3.4/5.13.0-VALVE21.3-1-NEPTUNE/X86_64/85EF5EAF43>) |
| 109e:0878 | 1461:0003 | Brooktree        | Bt878 Audio Capture                  | 17    | snd_bt87x  | [C9AC6EB940](<Desktop/Gigabyte Technology/M52/M52S-S3P/9FD6650D13F4/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/C9AC6EB940>) |
| 8086:22b8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 17    | intel_a... | [7070BF387D](<Desktop/AMI/Cherry/Cherry Trail FFD/27D81DDA8104/LINUXMINT-20.3/5.4.0-135-GENERIC/X86_64/7070BF387D>) |
| 1131:7231 | 16be:0008 | Philips Semic... | SAA7231                              | 15    |            | [83C862DA24](<Desktop/Medion/MS/MS-7621/B7D24A17624E/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/83C862DA24>) |
| 109e:0878 | 0070:13eb | Brooktree        | Bt878 Audio Capture                  | 13    | snd_bt87x  | [2DC41C0B99](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite CMT PC/E54CED74845D/UBUNTU-20.04/5.13.0-51-GENERIC/X86_64/2DC41C0B99>) |
| 1822:4e35 | 1ae4:0003 | Twinhan Techn... | Mantis DTV PCI Bridge Controller ... | 13    | mantis     | [B830D8001E](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX/CF2FED6C45D4/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/B830D8001E>) |
| 8086:5a88 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 13    |            | [BE28C34DA3](<Desktop/Others/Others/Others/0D6A7512D490/UBUNTU-22.04/5.15.0-52-GENERIC/X86_64/BE28C34DA3>) |
| 11bd:bede | 11bd:0023 | Pinnacle Systems | AV/DV Studio Capture Card            | 12    |            | [C6215EC2F3](<Desktop/ASUSTek Computer/Maximus/Maximus Extreme/41CC782371DA/LINUXMINT-20.3/5.4.0-144-GENERIC/X86_64/C6215EC2F3>) |
| 1022:15e2 | 17aa:3708 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 11    | snd_pci... | [E84598D67C](<Desktop/Lenovo/IdeaCentre/IdeaCentre 3 07ADA05 90MV008VAU/2016408AD82F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/E84598D67C>) |
| 1022:15e2 | 1849:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 11    | snd_pci... | [DF056EC6F1](<Desktop/ASRock/4X4-4000/4X4-4000 Series/512CE5A79924/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/DF056EC6F1>) |
| 1131:7160 | 1461:1455 | Philips Semic... | SAA7160                              | 10    |            | [2D08F702CF](<Desktop/ASUSTek Computer/ROG/ROG STRIX B450-F GAMING/5983AE90C26C/ARCH/5.10.10-ARCH1-1/X86_64/2D08F702CF>) |
| 1131:7160 | 1ae4:0700 | Philips Semic... | SAA7160                              | 10    | saa716x... | [57865D6CEA](<Desktop/ASRock/J4125/J4125M/BD0FBF639942/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/57865D6CEA>) |
| 1131:7164 | 0070:f111 | Philips Semic... | SAA7164                              | 10    | saa7164    | [862BD68D6F](<Desktop/Lenovo/IdeaCentre/IdeaCentre K330B/CBD80DABB0C6/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/862BD68D6F>) |
| 12ab:0710 | 1cfa:000e | YUAN High-Tec... | SC0710 PCI                           | 10    |            | [36F1AA431D](<Desktop/ASUSTek Computer/ROG/ROG STRIX X570-F GAMING/C7CA1B973424/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/36F1AA431D>) |
| 1822:4e35 | 153b:1178 | Twinhan Techn... | Mantis DTV PCI Bridge Controller ... | 9     | mantis     | [FE6EB0FF04](<Desktop/Gigabyte Technology/Z77/Z77-DS3H/E2DECE2E8DCF/DEBIAN-11/5.10.0-14-AMD64/X86_64/FE6EB0FF04>) |
| 1022:15e2 | 103c:8434 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 8     | snd_pci... | [2F4023E5F3](<Desktop/Hewlett-Packard/Desktop/Desktop Pro A MT/2C35BF3FF42F/OPENMANDRIVA-23.01/6.1.4-DESKTOP-1OMV2301/X86_64/2F4023E5F3>) |
| 109e:0878 | 11bd:0012 | Brooktree        | Bt878 Audio Capture                  | 8     | snd_bt87x  | [7F1747C3E3](<Desktop/ASUSTek Computer/A88/A88X-PLUS/279BA270C61D/SLACKWARE-CURRENT/6.2.9-SLACK/X86_64/7F1747C3E3>) |
| 1131:7231 | 16be:0013 | Philips Semic... | SAA7231                              | 8     |            | [639A660B02](<Desktop/Medion/P961/P961x/954B2DC792ED/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/639A660B02>) |
| 1131:7231 | 5ace:8000 | Philips Semic... | SAA7231                              | 8     |            | [FA070462FC](<Desktop/ASRock/Z68/Z68 Extreme4 Gen3/71936AAC6BA1/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/FA070462FC>) |
| 1822:4e35 | 153b:1179 | Twinhan Techn... | Mantis DTV PCI Bridge Controller ... | 8     | mantis     | [CEC0830928](<Desktop/ASUSTek Computer/P5/P5Q-PRO/A7048BCCA383/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/CEC0830928>) |
| 109e:0878 | 107d:6606 | Brooktree        | Bt878 Audio Capture                  | 7     | snd_bt87x  | [D04747E05B](<Desktop/ASUSTek Computer/M4/M4A78/88CDF84023B7/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D04747E05B>) |
| 109e:0878 | ffff:ffff | Brooktree        | Bt878 Audio Capture                  | 7     |            | [2D599510B8](<Desktop/Gigabyte Technology/X570S/X570S UD/16DF58F2FA45/MANJARO-22.1.0/6.3.0-1-MANJARO/X86_64/2D599510B8>) |
| 1822:4e35 | 1ae4:0002 | Twinhan Techn... | Mantis DTV PCI Bridge Controller ... | 7     | mantis     | [0047E2DE0E](<Desktop/MSI/MS-7/MS-7C37/300BB945314B/ARCH/5.15.70-1-LTS/X86_64/0047E2DE0E>) |
| 109e:0878 | 107d:6609 | Brooktree        | Bt878 Audio Capture                  | 6     |            | [31DFECDF4A](<Desktop/ASUSTek Computer/P5/P5K/7ADE8DD442B2/BUNSENLABS-10.5/4.19.0-10-AMD64/X86_64/31DFECDF4A>) |
| 109e:0878 | bd11:1200 | Brooktree        | Bt878 Audio Capture                  | 6     | snd_bt87x  | [06C110E6F1](<Desktop/Gigabyte Technology/GA-MA785/GA-MA785GMT-UD2H/BAB1917DBE50/LINUXMINT-21.1/5.15.0-60-GENERIC/X86_64/06C110E6F1>) |
| 10ee:222a | ef11:ddd5 | Xilinx           | Multimedia controller                | 6     | earth_pt1  | [A97C12B513](<Desktop/ASUSTek Computer/PRO/PRO H410M-C/ABEF71E577AC/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/A97C12B513>) |
| 1131:7231 | 0070:0810 | Philips Semic... | SAA7231                              | 6     |            | [9A2BEBB3BA](<Desktop/Hewlett-Packard/HPE-510/HPE-510f/DAC3D213E3CA/KDE-NEON-20.04/5.11.0-27-GENERIC/X86_64/9A2BEBB3BA>) |
| 1131:7231 | 1461:1400 | Philips Semic... | SAA7231                              | 6     |            | [70C319B3C6](<Desktop/MSI/MS-7/MS-7A72/525C60694331/ROSA-2016.1/5.4.40-GENERIC-1ROSA-X86_64/X86_64/70C319B3C6>) |
| 1131:7231 | 16be:0002 | Philips Semic... | SAA7231                              | 6     |            | [D1CC36D216](<Desktop/Medion/MS/MS-7366/43FC9A5C4FB6/UBUNTU-20.04/5.4.0-110-GENERIC/X86_64/D1CC36D216>) |
| 14f1:8804 | 0070:6902 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 6     |            | [30B776E4E8](<Desktop/ASUSTek Computer/B150/B150-PLUS/84FDC9B2D6EA/UBUNTU-18.04/5.4.0-136-GENERIC/X86_64/30B776E4E8>) |
| 14f1:8804 | 0070:9002 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 6     |            | [363AC45AF6](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/C4E9F5816A58/OPENMANDRIVA-4.50/5.19.12-DESKTOP-2OMV4090/X86_64/363AC45AF6>) |
| 1745:3000 | 0070:d180 | ViXS Systems     | Colossus Encoder                     | 6     |            | [32DFB5EBE2](<Desktop/ASUSTek Computer/CROSSHAIR/CROSSHAIR V FORMULA-Z/6FEEC75CFB08/OPENSUSE-LEAP-15.4/5.14.21-150400.24.41-DEFAULT/X86_64/32DFB5EBE2>) |
| 1131:7160 | 1131:0002 | Philips Semic... | SAA7160                              | 5     |            | [4852DDE595](<Desktop/ASUSTek Computer/All/All Series/AB1F0969A8DC/UBUNTU-MATE-20.04/5.4.0-107-GENERIC/X86_64/4852DDE595>) |
| 1131:7160 | 1461:0955 | Philips Semic... | SAA7160                              | 5     |            | [1320F35331](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 PLUS R2.0/7A91309FCC86/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/1320F35331>) |
| 1131:7164 | 0070:8880 | Philips Semic... | SAA7164                              | 5     | saa7164    | [37F3DA239A](<Desktop/MSI/MS/MS-7693/C85B0030F9F4/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/37F3DA239A>) |
| 1131:7164 | 1043:48c3 | Philips Semic... | SAA7164                              | 5     | saa7164    | [A6084E8904](<Desktop/Hewlett-Packard/p7/p7-1110/53D15D922ECD/OPENMANDRIVA-4.3/5.16.13-DESKTOP-1OMV4050/X86_64/A6084E8904>) |
| 1131:7231 | 1461:7983 | Philips Semic... | SAA7231                              | 5     |            | [277212BFC3](<Desktop/ASUSTek Computer/P8H67-M/P8H67-M LX/79239C5DA043/DEBIAN-10/4.19.0-22-AMD64/X86_64/277212BFC3>) |
| 1131:7231 | 5ace:8201 | Philips Semic... | SAA7231                              | 5     |            | [1A9B30AF2A](<Desktop/Gigabyte Technology/X470/X470 AORUS GAMING 7 WIFI/2ABCB3BAC2B5/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/1A9B30AF2A>) |
| 14e4:1615 | 14e4:1615 | Broadcom         | BCM70015 Video Decoder [Crystal HD]  | 5     |            | [17E652ED06](<Desktop/ASUSTek Computer/All/All Series/0CEDFC564A50/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/17E652ED06>) |
| 14f1:8804 | 0070:1402 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 5     |            | [BC782F5E67](<Desktop/Acer/Veriton/Veriton E430/8B2BCFA5614B/UBUNTU-20.10/5.8.0-43-GENERIC/X86_64/BC782F5E67>) |
| 14f1:8804 | 0070:6906 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 5     |            | [BA28960B69](<Desktop/MSI/MS/MS-7850/4ED77D8D3780/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/BA28960B69>) |
| 1822:4e35 | 1822:0031 | Twinhan Techn... | Mantis DTV PCI Bridge Controller ... | 5     | mantis     | [778B7898E3](<Desktop/Gigabyte Technology/H87/H87M-HD3/43A49BCC58C2/OPENMANDRIVA-4.3/5.16.13-DESKTOP-1OMV4003/X86_64/778B7898E3>) |
| 544d:6178 | 6205:0001 | TBS Technologies | DVB Tuner PCIe Card                  | 5     | tbsecp3    | [4FAC3DDF27](<Desktop/ASUSTek Computer/PRIME/PRIME H570M-PLUS/4865817EDA98/GENTOO-2.9/6.1.12-GENTOO/X86_64/4FAC3DDF27>) |
| 544d:6178 | 6281:0002 | TBS Technologies | DVB Tuner PCIe Card                  | 5     | tbsecp3    | [FBCDD4ED13](<Desktop/ASUSTek Computer/ROG/ROG STRIX TRX40-E GAMING/F64291DFA9A1/DEBIAN-11/5.10.0-21-AMD64/X86_64/FBCDD4ED13>) |
| 544d:6178 | 6902:0002 | TBS Technologies | DVB Tuner PCIe Card                  | 5     |            | [7A58CEB644](<Desktop/Gigabyte Technology/H270/H270M-D3H/D57980EEEB55/DEBIAN-11/5.10.0-21-AMD64/X86_64/7A58CEB644>) |

### Multiport serial controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1fd4:1999 | 1fd4:0002 | SUNIX            | Multiport serial controller          | 7     | serial     | [DF6B2FA3DE](<Desktop/Acer/Veriton/Veriton S490G/DC3A279E3E3B/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/DF6B2FA3DE>) |
| 1fff:8018 |           | MCST             | I2C SPI                              | 3     | i2c_spi    | [3F51BE2653](<Desktop/Others/Others/Others/72BC38F883EE/ROSA-12.2/5.4.182-GENERIC-1ROSA2021.1-E2KV4/E2K/3F51BE2653>) |
| 135a:08c1 | 135a:0413 | Brain Boxes      | Multiport serial controller          | 1     |            | [0F6EBD3E93](<Desktop/ASRock/G31/G31M-GS/0169A977538A/LINUXMINT-19.3/5.0.0-32-GENERIC/X86_64/0F6EBD3E93>) |
| 135c:0170 | 135c:0170 | Quatech          | QSCLP-100                            | 1     | serial     | [05DF269988](<Desktop/Hewlett-Packard/Evo/Evo D530/4AA9ADFB04B0/ROSA-2014.1/4.1.34-NRJ-DESKTOP-2ROSA-I586/I686/05DF269988>) |
| 1fff:8028 |           | MCST             | I2C SPI Crystall                     | 1     | 8250_pci   | [5AD56CAB50](<Desktop/Others/Others/Others/FC75BEA27F4E/ALT-P10/5.4.193-MCST-E16C-ALT5.9.4/E2K/5AD56CAB50>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:8168 | 1458:e000 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 8693  | r8169      | [E44F7DFAC5](<Desktop/Punch Technology/PDT-702/PDT-702-1020/29C76CB9E8B7/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/E44F7DFAC5>) |
| 10ec:8168 | 1849:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 3812  | r8169      | [13B1131BEF](<Desktop/ASRock/H67/H67DE3-SI/ED18AAFC18F5/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/13B1131BEF>) |
| 10ec:8168 | 1043:8677 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 3229  | r8169      | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 10ec:8168 | 1043:8505 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 2290  | r8169      | [9A420C42DE](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3/ABA4EBB5D0B8/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-X86_64/X86_64/9A420C42DE>) |
| 10ec:8168 | 1043:8432 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1687  | r8169      | [F5499886E9](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/D04FB50B5F37/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/F5499886E9>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1686  | r8169      | [8E4CBC4837](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer/5EE6E0F2768B/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/8E4CBC4837>) |
| 8086:15b8 | 1043:8672 | Intel            | Ethernet Connection (2) I219-V       | 1185  | e1000e     | [BBFD29FB88](<Desktop/ASUSTek Computer/D320/D320SF/A7E6ADB389B1/UBUNTU-20.04/5.4.0-148-GENERIC/X86_64/BBFD29FB88>) |
| 10ec:8168 | 1043:8554 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1016  | r8169      | [870A49D90C](<Desktop/ASUSTek Computer/A88/A88XM-PLUS/40D45C4AF68F/UBUNTU-22.04/5.13.0-30-GENERIC/X86_64/870A49D90C>) |
| 10ec:8139 | 10ec:8139 | Realtek Semic... | RTL-8100/8101L/8139 PCI Fast Ethe... | 821   | 8139too... | [C7D1EAC585](<Desktop/ASUSTek Computer/P5Q/P5Q SE2/3FD6E4DB1ED2/XUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/C7D1EAC585>) |
| 10ec:8168 | 1043:83a3 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 759   | r8169      | [CBF9D11153](<Desktop/ASUSTek Computer/M4/M4A785-M/23278E631048/UBUNTUSTUDIO-22.04/5.15.0-71-LOWLATENCY/X86_64/CBF9D11153>) |
| 8086:15f3 | 1043:87d2 | Intel            | Ethernet Controller I225-V           | 753   | igc        | [401DB07B93](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z690-A GAMING WIFI D4/46556BD3958D/DEBIAN-12/6.1.0-7-AMD64/X86_64/401DB07B93>) |
| 10ec:8168 | 1043:859e | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 679   | r8169      | [FAABFF7B74](<Desktop/ASUSTek Computer/A88/A88X-PRO/1D7F35C4CBE8/ARCO-ROLLING/6.1.23-X64V1-XANMOD1-1-LTS/X86_64/FAABFF7B74>) |
| 8086:15b8 | 1458:e000 | Intel            | Ethernet Connection (2) I219-V       | 529   | e1000e     | [8C5B603452](<Desktop/Gigabyte Technology/Z170X-Gaming/Z170X-Gaming 7/F95579DE4AF1/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/8C5B603452>) |
| 8086:15a1 | 1043:85c4 | Intel            | Ethernet Connection (2) I218-V       | 527   | e1000e     | [C47205C3CB](<Desktop/ASUSTek Computer/All/All Series/0A37A7D15166/STEAMOS-4/6.1.21-VALVE1-1-NEPTUNE-61/X86_64/C47205C3CB>) |
| 10ec:8136 | 10ec:0123 | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 496   | r8169      | [CD89C5B708](<Desktop/Intel/H/H61/75D9EAFF3D08/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/CD89C5B708>) |
| 10ec:8168 | 7470:3468 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 482   | r8169      | [FB7920C5F9](<Desktop/ASUSTek Computer/M3N/M3N WS/208D21EEB6BD/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/FB7920C5F9>) |
| 1969:1048 | 1043:8226 | Qualcomm Atheros | Attansic L1 Gigabit Ethernet         | 436   | atl1       | [D15B9FB438](<Desktop/ASUSTek Computer/P5/P5K/0772711AD395/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/D15B9FB438>) |
| 1969:1083 | 1458:e000 | Qualcomm Atheros | AR8151 v2.0 Gigabit Ethernet         | 420   | atl1c      | [0458D9F44B](<Desktop/Gigabyte Technology/G41/G41MT-S2/EF1568975525/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/0458D9F44B>) |
| 8086:15b8 | 1849:15b8 | Intel            | Ethernet Connection (2) I219-V       | 416   | e1000e     | [D905BABC43](<Desktop/ASRock/B250/B250M-HDV/A65B4BC89A4A/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/D905BABC43>) |
| 8086:15bc | 1043:8672 | Intel            | Ethernet Connection (7) I219-V       | 393   | e1000e     | [14C71828CA](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-F GAMING/5D29F2B9EBFF/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/14C71828CA>) |
| 10ec:8169 | 10ec:8169 | Realtek Semic... | RTL8169 PCI Gigabit Ethernet Cont... | 383   | r8169      | [4D78DBBDC6](<Desktop/ASUSTek Computer/P5Q/P5Q SE-R/2575946B74AB/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/4D78DBBDC6>) |
| 10ec:8168 | 1043:87c3 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 380   | r8169      | [4E424E0AD2](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/2E14927B3139/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/4E424E0AD2>) |
| 11ab:4364 | 1043:81f8 | Marvell Techn... | 88E8056 PCI-E Gigabit Ethernet Co... | 379   | sky2       | [4B705B9DCA](<Desktop/ASUSTek Computer/CROSSHAIR/CROSSHAIR II FORMULA/4ADEED4021BD/UBUNTU-20.04/5.4.0-144-GENERIC/X86_64/4B705B9DCA>) |
| 8086:153a | 1028:05a4 | Intel            | Ethernet Connection I217-LM          | 344   | e1000e     | [5BC5CCDCAD](<Desktop/Dell/OptiPlex/OptiPlex 9020/E9FD17DAA8B2/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/5BC5CCDCAD>) |
| 10ec:8168 | 1462:7c37 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 336   | r8169      | [46894747B1](<Desktop/MSI/MS-7/MS-7C37/9E9208EB0239/ZORIN-16/5.15.0-71-GENERIC/X86_64/46894747B1>) |
| 10ec:8168 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 329   | r8169      | [5D6AA6C0DF](<Desktop/Google/Zako/Zako/00B4B1A8953E/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/5D6AA6C0DF>) |
| 8086:15bc | 1458:e000 | Intel            | Ethernet Connection (7) I219-V       | 310   | e1000e     | [AA2AF0A4BC](<Desktop/Gigabyte Technology/Z390/Z390 GAMING X/94E45CAB4EE0/GENTOO-2.13/6.1.19-GENTOO/X86_64/AA2AF0A4BC>) |
| 10ec:8168 | 1043:82c6 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 301   | r8169      | [FB7920C5F9](<Desktop/ASUSTek Computer/M3N/M3N WS/208D21EEB6BD/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/FB7920C5F9>) |
| 10ec:8136 | 1849:8136 | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 300   | r8169      | [940D88BFCE](<Desktop/ASRock/945/945GCM-S/9995C9213664/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/940D88BFCE>) |
| 10ec:8168 | 1462:7c02 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 296   | r8169      | [3A7E1532DA](<Desktop/MSI/MS-7/MS-7C02/ACF3D9051F49/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/3A7E1532DA>) |
| 1969:1091 | 1458:e000 | Qualcomm Atheros | AR8161 Gigabit Ethernet              | 290   | alx        | [456582ED94](<Desktop/Gigabyte Technology/GA-78/GA-78LMT-S2P/A37FF96A9494/UBUNTU-MATE-20.04/5.4.0-148-GENERIC/X86_64/456582ED94>) |
| 8086:153b | 1458:e000 | Intel            | Ethernet Connection I217-V           | 282   | e1000e     | [22BD54D6D1](<Desktop/Gigabyte Technology/Z87/Z87X-UD3H/F9D737247AAE/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/22BD54D6D1>) |
| 10ec:8168 | 1462:7817 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 279   | r8169      | [B5C0679341](<Desktop/MSI/MS/MS-7817/73BC5E06C84D/GENTOO-2.13/6.3.1-GENTOO/X86_64/B5C0679341>) |
| 10ec:8168 | 1025:8000 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 253   | r8169      | [712A246CE4](<Desktop/Acer/Aspire/Aspire M1930/0EDA29407810/LINUXMINT-21/5.15.0-56-GENERIC/X86_64/712A246CE4>) |
| 8086:15f3 | 8086:0000 | Intel            | Ethernet Controller I225-V           | 239   | igc        | [22D1FBDEEE](<Desktop/Others/Others/Others/7E2DCAD143A6/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/22D1FBDEEE>) |
| 10ec:8168 | 1462:7b86 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 232   | r8169      | [017222D810](<Desktop/MSI/MS-7/MS-7B86/C33D0282BB9A/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/017222D810>) |
| 1969:1026 | 1043:8304 | Qualcomm Atheros | AR8121/AR8113/AR8114 Gigabit or F... | 232   | atl1e      | [C2A0653C52](<Desktop/ASUSTek Computer/P5QLD/P5QLD PRO/0678AB1FB908/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/C2A0653C52>) |
| 1106:3106 | 1186:1405 | VIA Technologies | VT6105/VT6106S [Rhine-III]           | 230   | via_rhine  | [32F708C916](<Desktop/ASUSTek Computer/All/All Series/20E98994CFBF/KUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/32F708C916>) |
| 10ec:8168 | 1462:7721 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 210   | r8169      | [14A87BC11A](<Desktop/MSI/MS/MS-7721/89882A257F09/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/14A87BC11A>) |
| 8086:153b | 1043:859f | Intel            | Ethernet Connection I217-V           | 210   | e1000e     | [7477BE45F8](<Desktop/ASUSTek Computer/All/All Series/B8CE54389268/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/7477BE45F8>) |
| 10ec:8125 | 1043:879b | Realtek Semic... | RTL8125 2.5GbE Controller            | 209   | r8169      | [B9D976AE11](<Desktop/ASUSTek Computer/ROG/ROG STRIX X570-E GAMING/8CED5CE61807/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/B9D976AE11>) |
| 10ec:8168 | 1028:0612 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 191   | r8169      | [2F6FD9E5B0](<Desktop/Dell/OptiPlex/OptiPlex 3020/6E94400CAA49/XUBUNTU-23.04/6.2.0-20-GENERIC/X86_64/2F6FD9E5B0>) |
| 10ec:8168 | 1462:7a38 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 190   | r8169      | [A9D1794EEC](<Desktop/MSI/MS-7/MS-7A38/C3487D76EFD3/FEDORA-36/6.1.8-100.FC36.X86_64/X86_64/A9D1794EEC>) |
| 1969:e091 | 1458:e000 | Qualcomm Atheros | Killer E220x Gigabit Ethernet Con... | 183   | alx        | [2CBFF804D8](<Desktop/Gigabyte Technology/Z97X-Gaming/Z97X-Gaming 3/EEB9D6F73B6D/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/2CBFF804D8>) |
| 11ab:4320 | 1043:811a | Marvell Techn... | 88E8001 Gigabit Ethernet Controller  | 182   | skge       | [D0D3458299](<Desktop/ASUSTek Computer/P5/P5B-Deluxe/8D97A918D165/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/D0D3458299>) |
| 10ec:8136 | 1043:8347 | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 178   | r8169      | [F48937493D](<Desktop/ASUSTek Computer/P5/P5KPL-AM/6DBC48DA6B2A/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-X86_64/X86_64/F48937493D>) |
| 10ec:8168 | 1462:7b79 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 178   | r8169      | [A5D42A7B78](<Desktop/MSI/MS-7/MS-7B79/39AF0874D973/FEDORA-38/6.2.12-300.FC38.X86_64/X86_64/A5D42A7B78>) |
| 10ec:8168 | 1565:2312 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 176   | r8169      | [95B25BA480](<Desktop/Biostar/H110/H110MHV3/BA39A6E39188/XERO-ROLLING/6.2.12-ARCH1-1/X86_64/95B25BA480>) |
| 8086:15a1 | 1849:15a1 | Intel            | Ethernet Connection (2) I218-V       | 174   | e1000e     | [7B83DEF3E1](<Desktop/ASRock/Z97/Z97 Extreme4/0931B22FD179/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/7B83DEF3E1>) |
| 1969:10a1 | 1849:10a1 | Qualcomm Atheros | QCA8171 Gigabit Ethernet             | 172   | alx        | [53C03D6942](<Desktop/ASRock/FM2A88X/FM2A88X Extreme6+/061803342427/FEDORA-37/6.0.11-300.FC37.X86_64/X86_64/53C03D6942>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2723 | 8086:0084 | Intel            | Wi-Fi 6 AX200                        | 2650  | iwlwifi    | [AD66608CF0](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/E039702D1078/CHIMERAOS-41/6.1.21-1-LTS/X86_64/AD66608CF0>) |
| 8086:24fb | 8086:2110 | Intel            | Dual Band Wireless-AC 3168NGW [St... | 1094  | iwlwifi    | [80B16A8567](<Desktop/ASRock/B560/B560M-ITX-ac/43B5A145EA88/FEDORA-37/6.2.14-200.FC37.X86_64/X86_64/80B16A8567>) |
| 8086:2526 | 8086:0014 | Intel            | Wireless-AC 9260                     | 730   | iwlwifi    | [4E424E0AD2](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/2E14927B3139/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/4E424E0AD2>) |
| 8086:2725 | 8086:0024 | Intel            | Wi-Fi 6 AX210/AX211/AX411 160MHz     | 469   | iwlwifi    | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 8086:a370 | 8086:0034 | Intel            | Cannon Lake PCH CNVi WiFi            | 338   | iwlwifi    | [DBEB828B17](<Desktop/Gigabyte Technology/Z390/Z390 I AORUS PRO WIFI/29952FD8445D/ARCO-ROLLING/6.2.11-ARCH1-1/X86_64/DBEB828B17>) |
| 168c:002e | 168c:30a4 | Qualcomm Atheros | AR9287 Wireless Network Adapter (... | 321   | ath9k      | [89AE1A3E9D](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/1DCD288DE1CB/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/89AE1A3E9D>) |
| 10ec:818b | 10ec:8196 | Realtek Semic... | RTL8192EE PCIe Wireless Network A... | 288   | rtl8192ee  | [13B1131BEF](<Desktop/ASRock/H67/H67DE3-SI/ED18AAFC18F5/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/13B1131BEF>) |
| 168c:0032 | 168c:3118 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 278   | ath9k      | [927EFC8106](<Desktop/ASUSTek Computer/A55/A55M-E/CD09A74895A0/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/927EFC8106>) |
| 168c:0030 | 168c:3112 | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 273   | ath9k      | [DDB48A2DEF](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/D4594317D339/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/DDB48A2DEF>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 264   | iwlwifi    | [ACF61A6132](<Desktop/Gigabyte Technology/970/970A-DS3P/4209CEC662D2/OPENMANDRIVA-23.03/6.2.10-DESKTOP-2.0OMV4.9MJN/X86_64/ACF61A6132>) |
| 14e4:43a0 | 14e4:0619 | Broadcom         | BCM4360 802.11ac Wireless Network... | 244   | wl         | [E11B4303D3](<Desktop/MSI/MS-7/MS-7C37/8E76E3D563B5/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/E11B4303D3>) |
| 10ec:c821 | 103c:831a | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 217   | rtw88_8... | [E885F0469C](<Desktop/Hewlett-Packard/595/595-P0569NG/95CC7F0B57CC/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.10-1-DEFAULT/X86_64/E885F0469C>) |
| 8086:3165 | 8086:4010 | Intel            | Wireless 3165                        | 208   | iwlwifi    | [5E5011BDD3](<Desktop/ECS/LIVA/LIVA One H410/8A17C18B544A/UBUNTUSTUDIO-22.10/5.19.0-1023-LOWLATENCY/X86_64/5E5011BDD3>) |
| 14c3:0608 | 14c3:0608 | MediaTek         | MT7921K (RZ608) Wi-Fi 6E 80MHz       | 206   | mt7921e    | [47388F4553](<Desktop/Gigabyte Technology/X570S/X570S AORUS PRO AX/82196083E848/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/47388F4553>) |
| 10ec:b822 | 1043:8746 | Realtek Semic... | RTL8822BE 802.11a/b/g/n/ac WiFi a... | 202   | r8822be    | [553A101CF8](<Desktop/ASUSTek Computer/ROG/ROG STRIX X299-E GAMING/C1F57B2F0914/MANJARO/6.1.25-1-MANJARO/X86_64/553A101CF8>) |
| 168c:002d | 168c:0300 | Qualcomm Atheros | AR9227 Wireless Network Adapter      | 199   | ath9k      | [CBE978CC34](<Desktop/Others/G/G41/35512FE42E4F/ZORIN-16/5.15.0-69-GENERIC/X86_64/CBE978CC34>) |
| 8086:08b1 | 8086:4070 | Intel            | Wireless 7260                        | 185   | iwlwifi    | [99FBD772E8](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/5CD9D1C7363B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/99FBD772E8>) |
| 8086:24f3 | 8086:0010 | Intel            | Wireless 8260                        | 185   | iwlwifi    | [3C7546E88A](<Desktop/ASRock/B450M/B450M Pro4/2FB451C26D0F/LMDE-5/5.10.0-22-AMD64/X86_64/3C7546E88A>) |
| 8086:24fd | 8086:1010 | Intel            | Wireless 8265 / 8275                 | 184   | iwlwifi    | [E47AE2080C](<Desktop/Gigabyte Technology/X399/X399 DESIGNARE EX/1C77CFB17589/MANJARO/6.2.12-1-MANJARO/X86_64/E47AE2080C>) |
| 8086:7af0 | 8086:0074 | Intel            | Alder Lake-S PCH CNVi WiFi           | 181   | iwlwifi    | [401DB07B93](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z690-A GAMING WIFI D4/46556BD3958D/DEBIAN-12/6.1.0-7-AMD64/X86_64/401DB07B93>) |
| 8086:06f0 | 8086:0074 | Intel            | Comet Lake PCH CNVi WiFi             | 167   | iwlwifi    | [9EF46F7F3E](<Desktop/Acer/Predator/Predator PO3-620/877F4FBC5AE0/KDE-NEON-22.04/5.19.0-41-GENERIC/X86_64/9EF46F7F3E>) |
| 168c:002d | 168c:0301 | Qualcomm Atheros | AR9227 Wireless Network Adapter      | 146   | ath9k      | [B1FB1BDECF](<Desktop/Gigabyte Technology/GA-890/GA-890GPA-UD3H/196D4EF3C39F/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/B1FB1BDECF>) |
| 10ec:8179 | 10ec:8197 | Realtek Semic... | RTL8188EE Wireless Network Adapter   | 132   | rtl8188ee  | [C350F5ED12](<Desktop/Intel/D946GZIS/D946GZIS AAD66165-301/7C5BABF74716/ZORIN-16/5.15.0-71-GENERIC/X86_64/C350F5ED12>) |
| 1814:5390 | 1814:f051 | Ralink           | RT5390 Wireless 802.11n 1T/1R PCIe   | 122   | rt2800pci  | [245DB62C73](<Desktop/Hewlett-Packard/h8/h8-1350eo/735D2351FEA5/UBUNTU-22.10/5.19.0-40-GENERIC/X86_64/245DB62C73>) |
| 10ec:8178 | 1043:84b6 | Realtek Semic... | RTL8192CE PCIe Wireless Network A... | 112   | rtl8192ce  | [64E06D7111](<Desktop/ASUSTek Computer/TUF/TUF Z390-PRO GAMING/5DB2AC2E0F4E/UBUNTU-20.04/5.4.0-146-GENERIC/X86_64/64E06D7111>) |
| 168c:0032 | 1028:0209 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 107   | ath9k      | [D1084F0D90](<Desktop/Dell/XPS/XPS 8700/BA9189F58C61/NOBARA-37/6.2.10-200.FSYNC.FC37.X86_64/X86_64/D1084F0D90>) |
| 8086:43f0 | 8086:0074 | Intel            | Tiger Lake PCH CNVi WiFi             | 103   | iwlwifi    | [25C4B5FE60](<Desktop/Gigabyte Technology/Z590/Z590 AORUS ELITE AX/B68CA193B4B0/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/25C4B5FE60>) |
| 14e4:43a0 | 1043:85df | Broadcom         | BCM4360 802.11ac Wireless Network... | 102   | wl         | [EA9DD842C0](<Desktop/ASUSTek Computer/ROG/ROG STRIX X670E-E GAMING WIFI/91442269DA97/LINUXMINT-21.1/6.2.12-060212-GENERIC/X86_64/EA9DD842C0>) |
| 168c:0034 | 11ad:6621 | Qualcomm Atheros | AR9462 Wireless Network Adapter      | 102   | ath9k      | [DCD0BBB01A](<Desktop/Gateway/DX/DX4870/8D9AF1C14D30/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/DCD0BBB01A>) |
| 168c:002b | 168c:30a1 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 98    | ath9k      | [FF6049B22E](<Desktop/Hewlett-Packard/FQ515AA-ABA/FQ515AA-ABA a6620f/F964AF1529FA/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/FF6049B22E>) |
| 10ec:8812 | 10ec:8203 | Realtek Semic... | RTL8812AE 802.11ac PCIe Wireless ... | 95    | rtl8821ae  | [7B0B45831C](<Desktop/MSI/MS-7/MS-7C95/2DEDCC12A3E3/ZORIN-16/5.15.0-71-GENERIC/X86_64/7B0B45831C>) |
| 168c:0036 | 1028:020c | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 93    | ath9k      | [129ED2A520](<Desktop/Dell/Inspiron/Inspiron 3847/0FA41014D6FD/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/129ED2A520>) |
| 8086:08b3 | 8086:8070 | Intel            | Wireless 3160                        | 91    | iwlwifi    | [5F3EB929B7](<Desktop/ASRock/z270/z270 Taichi/10487916EA57/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/5F3EB929B7>) |
| 10ec:8176 | 1043:84b5 | Realtek Semic... | RTL8188CE 802.11b/g/n WiFi Adapter   | 90    | rtl8192ce  | [DE394C8663](<Desktop/Dell/OptiPlex/OptiPlex 3010/D899A78989BD/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/DE394C8663>) |
| 1814:3090 | 11ad:7601 | Ralink           | RT3090 Wireless 802.11n 1T/1R PCIe   | 90    | rt2800pci  | [B3DE61F1B3](<Desktop/Gateway/FX/FX6860/CFD8BE11C762/LINUXMINT-20.3/5.4.0-146-GENERIC/X86_64/B3DE61F1B3>) |
| 8086:a370 | 8086:02a4 | Intel            | Cannon Lake PCH CNVi WiFi            | 90    | iwlwifi    | [894029CC14](<Desktop/Acer/Aspire/Aspire TC-885/084A5D543ADF/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/894029CC14>) |
| 10ec:8821 | 1a3b:2161 | Realtek Semic... | RTL8821AE 802.11ac PCIe Wireless ... | 89    | rtl8821ae  | [FD91075868](<Desktop/ASUSTek Computer/K30/K30AD_M31AD_M51AD/83E1EAE17C96/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/FD91075868>) |
| 168c:0032 | 1028:0208 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 88    | ath9k      | [C8EE51395B](<Desktop/Dell/Inspiron/Inspiron 660/43EB38433518/LINUXMINT-20.1/5.4.0-144-GENERIC/X86_64/C8EE51395B>) |
| 168c:0036 | 1028:020e | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 88    | ath9k      | [7B9A0196B1](<Desktop/Dell/Inspiron/Inspiron 3471/32A22E68B813/POP!_OS-22.04/6.0.2-76060002-GENERIC/X86_64/7B9A0196B1>) |
| 168c:0042 | 1028:1810 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 86    | ath10k_pci | [C6DBE0270A](<Desktop/Alienware/Aurora/Aurora R8/32367D40A9B5/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/C6DBE0270A>) |
| 10ec:8185 | 10ec:8225 | Realtek Semic... | RTL-8185 IEEE 802.11a/b/g Wireles... | 85    | rtl818x... | [234E0D0738](<Desktop/ASUSTek Computer/F1A55-M/F1A55-M LK R2.0/82A0775D615D/LUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/234E0D0738>) |
| 14e4:43b1 | 1043:855c | Broadcom         | BCM4352 802.11ac Wireless Network... | 84    | wl         | [0D45B24479](<Desktop/ASUSTek Computer/All/All Series/CA48333AA32A/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/0D45B24479>) |
| 10ec:c821 | 10ec:c821 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 83    | rtw88_8... | [76FF5C3BD7](<Desktop/Intel/Jasper/Jasper Lake Client Platform/5E67453FB64F/ELEMENTARY-7/5.19.0-41-GENERIC/X86_64/76FF5C3BD7>) |
| 1814:0301 | 1814:2561 | Ralink           | RT2561/RT61 802.11g PCI              | 82    | rt61pci    | [ABF277EC59](<Desktop/Mustek6376 mst6376/P5/P5GC-VM/4154E83FB2CF/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/ABF277EC59>) |
| 168c:0032 | 1043:850d | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 81    | ath9k      | [E1D6888EAD](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V PRO/80A679F54C56/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/E1D6888EAD>) |
| 14e4:43b1 | 1043:85ba | Broadcom         | BCM4352 802.11ac Wireless Network... | 80    | wl         | [369C3CFDB2](<Desktop/Gigabyte Technology/X79/X79-UD5/DC786257E4FF/KDE-NEON-22.04/5.19.0-38-GENERIC/X86_64/369C3CFDB2>) |
| 168c:003e | 1043:86cd | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 79    | ath10k_pci | [536E6E7CC9](<Desktop/ASUSTek Computer/STRIX/STRIX B250I GAMING/BB9A16765525/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/536E6E7CC9>) |
| 8086:24f3 | 8086:1010 | Intel            | Wireless 8260                        | 78    | iwlwifi    | [EC8586E070](<Desktop/MSI/MS-7/MS-7A71/AA428BA484D8/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/EC8586E070>) |
| 10ec:8812 | 1043:86dd | Realtek Semic... | RTL8812AE 802.11ac PCIe Wireless ... | 77    | rtl8821ae  | [1404923301](<Desktop/MSI/MS-7/MS-7C02/B01E786348F2/FEDORA-38/6.2.12-300.FC38.X86_64/X86_64/1404923301>) |
| 8086:3166 | 8086:4210 | Intel            | Dual Band Wireless-AC 3165 Plus B... | 77    | iwlwifi    | [2A26D32CC3](<Desktop/Lenovo/IdeaCentre/IdeaCentre 510S-08ISH 90FN0059MB/550988BD50B4/DEBIAN-11/5.10.0-20-AMD64/X86_64/2A26D32CC3>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1539 | 1043:85f0 | Intel            | I211 Gigabit Network Connection      | 1571  | igb        | [4A8C2101E8](<Desktop/ASUSTek Computer/PRIME/PRIME X570-PRO/D1E7CA404339/DEBIAN-11/5.10.0-22-AMD64/X86_64/4A8C2101E8>) |
| 8086:1539 | 1458:e000 | Intel            | I211 Gigabit Network Connection      | 1061  | igb        | [9B013EBF89](<Desktop/Gigabyte Technology/X570/X570 AORUS MASTER/D4AAC9699323/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/9B013EBF89>) |
| 8086:1539 | 1849:1539 | Intel            | I211 Gigabit Network Connection      | 779   | igb        | [4681975F9D](<Desktop/ASRock/X570/X570 Phantom Gaming X/A0A588B9313C/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/4681975F9D>) |
| 10ec:8125 | 1458:e000 | Realtek Semic... | RTL8125 2.5GbE Controller            | 626   | r8169      | [25C4B5FE60](<Desktop/Gigabyte Technology/Z590/Z590 AORUS ELITE AX/B68CA193B4B0/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/25C4B5FE60>) |
| 8086:1503 | 1043:849c | Intel            | 82579V Gigabit Network Connection    | 586   | e1000e     | [288E495C16](<Desktop/ASUSTek Computer/P8Z68/P8Z68 DELUXE-GEN3/21E15FDA0A80/ZORIN-16/5.15.0-71-GENERIC/X86_64/288E495C16>) |
| 10ec:8125 | 1043:87d7 | Realtek Semic... | RTL8125 2.5GbE Controller            | 522   | r8169      | [DC43E4A7E3](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PRO/1FF7B8E0562A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/DC43E4A7E3>) |
| 10de:03ef | 1849:03ef | Nvidia           | MCP61 Ethernet                       | 489   | forcedeth  | [1F3953650C](<Desktop/ASRock/N68-VS3/N68-VS3 FX/D968CA13888E/LOC-OS-22/5.10.165-LOC-OS/X86_64/1F3953650C>) |
| 8086:1502 | 1028:052c | Intel            | 82579LM Gigabit Network Connectio... | 469   | e1000e     | [F0F22D5D3F](<Desktop/Dell/OptiPlex/OptiPlex 7010/D7591CF7C8EA/UBUNTU-20.04/5.4.0-148-GENERIC/X86_64/F0F22D5D3F>) |
| 8086:1502 | 1028:047e | Intel            | 82579LM Gigabit Network Connectio... | 349   | e1000e     | [EC04C034D3](<Desktop/Dell/OptiPlex/OptiPlex 990/D0B1671560CE/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/EC04C034D3>) |
| 8086:10de | 1028:0276 | Intel            | 82567LM-3 Gigabit Network Connection | 269   | e1000e     | [B585380BC4](<Desktop/Dell/OptiPlex/OptiPlex 780/8DA70E0A4BDE/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/B585380BC4>) |
| 10de:03ef | 1458:e000 | Nvidia           | MCP61 Ethernet                       | 253   | forcedeth  | [D571B75547](<Desktop/Gigabyte Technology/M68/M68MT-S2/333806208DA6/ZORIN-16/5.15.0-71-GENERIC/X86_64/D571B75547>) |
| 8086:10d3 | 8086:a01f | Intel            | 82574L Gigabit Network Connection    | 251   | e1000e     | [CBF9D11153](<Desktop/ASUSTek Computer/M4/M4A785-M/23278E631048/UBUNTUSTUDIO-22.04/5.15.0-71-LOWLATENCY/X86_64/CBF9D11153>) |
| 10ec:8125 | 1849:8125 | Realtek Semic... | RTL8125 2.5GbE Controller            | 182   | r8169      | [CF7CF903C0](<Desktop/ASRock/B760/B760 Pro RS-D4/22BCEB943676/DEBIAN-12/6.1.0-8-AMD64/X86_64/CF7CF903C0>) |
| 8086:1502 | 103c:3397 | Intel            | 82579LM Gigabit Network Connectio... | 181   | e1000e     | [8B84766D3D](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/EAE7702EADF9/DEBIAN-11/6.1.15-1-PVE/X86_64/8B84766D3D>) |
| 10de:03ef | 1043:83a4 | Nvidia           | MCP61 Ethernet                       | 179   | forcedeth  | [0C3F2AF7AD](<Desktop/ASUSTek Computer/M4N68T-M/M4N68T-M LE/7BD4E80F3F5C/LINUXMINT-18.3/4.10.0-38-GENERIC/X86_64/0C3F2AF7AD>) |
| 10ec:8125 | 1462:7c91 | Realtek Semic... | RTL8125 2.5GbE Controller            | 172   | r8169      | [F0BC6CA2DD](<Desktop/MSI/MS-7/MS-7C91/E8FA683D3AE7/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/F0BC6CA2DD>) |
| 8086:10bd | 1028:0211 | Intel            | 82566DM-2 Gigabit Network Connection | 163   | e1000e     | [03C6B8486E](<Desktop/Dell/OptiPlex/OptiPlex 755/F8A80185DE25/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/03C6B8486E>) |
| 8086:1502 | 103c:339a | Intel            | 82579LM Gigabit Network Connectio... | 152   | e1000e     | [3B40B9B869](<Desktop/Hewlett-Packard/Compaq/Compaq Pro 6300 MT/43C25A9EA8C2/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/3B40B9B869>) |
| 8086:1502 | 103c:1495 | Intel            | 82579LM Gigabit Network Connectio... | 135   | e1000e     | [D6E629523F](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite SFF PC/236BDABDB798/UBUNTUSTUDIO-22.04/5.15.0-71-LOWLATENCY/X86_64/D6E629523F>) |
| 10de:03ef | 1043:8234 | Nvidia           | MCP61 Ethernet                       | 129   | forcedeth  | [7EEAD8BD18](<Desktop/ASUSTek Computer/M2/M2N-MX/8AF34A7AE9F0/ROSA-12.3/5.10.150-GENERIC-1ROSA2021.1-X86_64/X86_64/7EEAD8BD18>) |
| 8086:1502 | 103c:1497 | Intel            | 82579LM Gigabit Network Connectio... | 119   | e1000e     | [3E285F4AE4](<Desktop/Hewlett-Packard/Compaq/Compaq 6200 Pro MT PC/DDB8E3F48862/UBUNTU-22.10/5.19.0-1024-LOWLATENCY/X86_64/3E285F4AE4>) |
| 8086:10de | 1028:027f | Intel            | 82567LM-3 Gigabit Network Connection | 115   | e1000e     | [16611A8ED6](<Desktop/Dell/OptiPlex/OptiPlex 760/7440761DE40F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/16611A8ED6>) |
| 8086:10bd | 103c:2818 | Intel            | 82566DM-2 Gigabit Network Connection | 107   | e1000e     | [B927834A03](<Desktop/Hewlett-Packard/Compaq/Compaq dc7800 Small Form Factor/A3D50758DB46/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B927834A03>) |
| 10ec:8125 | 10ec:0123 | Realtek Semic... | RTL8125 2.5GbE Controller            | 102   | r8169      | [087681F84E](<Desktop/Gigabyte Technology/GA-880/GA-880GMA-UD2H/D2B9BEC00498/UBUNTU-20.04/5.4.0-148-GENERIC/X86_64/087681F84E>) |
| 8086:1533 | 1043:8557 | Intel            | I210 Gigabit Network Connection      | 98    | igb        | [1C9E5EE2A6](<Desktop/ASUSTek Computer/WS/WS X299 SAGE/7F377E5958FC/LINUXMINT-20.3/5.19.0-17.2-LIQUORIX-AMD64/X86_64/1C9E5EE2A6>) |
| 8086:1539 | 8086:0000 | Intel            | I211 Gigabit Network Connection      | 95    | igb        | [18DCBA612C](<Desktop/Others/Others/Others/9654B0B310BA/DEBIAN-11/5.10.0-22-AMD64/X86_64/18DCBA612C>) |
| 8086:10de | 103c:3048 | Intel            | 82567LM-3 Gigabit Network Connection | 94    | e1000e     | [C771C0B0A7](<Desktop/Hewlett-Packard/Compaq/Compaq 6000 Pro SFF PC/78D2ECED4802/LINUXMINT-18.3/4.10.0-38-GENERIC/X86_64/C771C0B0A7>) |
| 8086:1503 | 1025:8000 | Intel            | 82579V Gigabit Network Connection    | 88    | e1000e     | [DCD0BBB01A](<Desktop/Gateway/DX/DX4870/8D9AF1C14D30/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/DCD0BBB01A>) |
| 8086:10c0 | 1028:020d | Intel            | 82562V-2 10/100 Network Connection   | 83    | e1000e     | [3EC4846DE7](<Desktop/Dell/Inspiron/Inspiron 530/F169934B5897/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/3EC4846DE7>) |
| 8086:10f6 | 8086:0000 | Intel            | 82574L Gigabit Network Connection    | 82    | e1000e     | [B68D1B92DE](<Desktop/Apple/MacPro5/MacPro5,1/E3007916032F/BLENDOS/6.2.13-ARCH1-1/X86_64/B68D1B92DE>) |
| 10de:03ef | 1462:7309 | Nvidia           | MCP61 Ethernet                       | 80    | forcedeth  | [E88DF81D6F](<Desktop/MSI/MS/MS-7309/B18EB79A9CB6/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/E88DF81D6F>) |
| 8086:1503 | 1458:e000 | Intel            | 82579V Gigabit Network Connection    | 80    | e1000e     | [369C3CFDB2](<Desktop/Gigabyte Technology/X79/X79-UD5/DC786257E4FF/KDE-NEON-22.04/5.19.0-38-GENERIC/X86_64/369C3CFDB2>) |
| 10ec:8125 | 1462:7c84 | Realtek Semic... | RTL8125 2.5GbE Controller            | 78    | r8169      | [3A39BF574B](<Desktop/MSI/MS-7/MS-7C84/BB81B9983F93/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/3A39BF574B>) |
| 8086:1502 | 103c:1589 | Intel            | 82579LM Gigabit Network Connectio... | 78    | e1000e     | [BE15D33D32](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/EE9F1FE423DF/DEBIAN-12/6.1.0-8-AMD64/X86_64/BE15D33D32>) |
| 10ec:8125 | 1462:7c35 | Realtek Semic... | RTL8125 2.5GbE Controller            | 76    | r8169      | [B2311E7CAC](<Desktop/MSI/MS-7/MS-7C35/CB298ECF07E8/ZORIN-16/5.15.0-69-GENERIC/X86_64/B2311E7CAC>) |
| 10ec:8125 | 1462:7c94 | Realtek Semic... | RTL8125 2.5GbE Controller            | 74    | r8169      | [26C158DF39](<Desktop/MSI/MS-7/MS-7C94/DD638739FE3A/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/26C158DF39>) |
| 8086:10f0 | 8086:0036 | Intel            | 82578DC Gigabit Network Connection   | 72    | e1000e     | [1CA0E70D0E](<Desktop/Equus Computer Systems/Nobilis/Nobilis/CBE725B8CBF2/LINUXMINT-21.1/5.15.0-67-GENERIC/X86_64/1CA0E70D0E>) |
| 8086:1502 | 17aa:3083 | Intel            | 82579LM Gigabit Network Connectio... | 69    | e1000e     | [7AC436D763](<Desktop/Lenovo/ThinkCentre/ThinkCentre M92P 3227BD2/791575E45E29/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/7AC436D763>) |
| 8086:150c | 1043:8457 | Intel            | 82583V Gigabit Network Connection    | 69    | e1000e     | [267C5B8075](<Desktop/ASUSTek Computer/CROSSHAIR/CROSSHAIR V FORMULA-Z/4DDB77B7D947/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/267C5B8075>) |
| 8086:1533 | 1849:1533 | Intel            | I210 Gigabit Network Connection      | 69    | igb        | [136A9303C0](<Desktop/ASRockRack/D1521/D1521D4I2/E866121B6A2E/ZORIN-16/5.15.0-71-GENERIC/X86_64/136A9303C0>) |
| 8086:104a | 103c:2800 | Intel            | 82566DM Gigabit Network Connection   | 68    | e1000e     | [636D94A346](<Desktop/Hewlett-Packard/Compaq/Compaq dc7700 Ultra-slim Desktop/7D505C9E7E8E/SPARKY-7/6.1.0-7-AMD64/X86_64/636D94A346>) |
| 8086:1539 | 1462:7b85 | Intel            | I211 Gigabit Network Connection      | 68    | igb        | [B2782D28F7](<Desktop/MSI/MS-7/MS-7B85/A1797BB6666C/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/B2782D28F7>) |
| 8086:1502 | 17aa:3070 | Intel            | 82579LM Gigabit Network Connectio... | 64    | e1000e     | [EAD0ECFB3A](<Desktop/Lenovo/ThinkCentre/ThinkCentre M91p 4518RH1/E30F2C4B8797/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/EAD0ECFB3A>) |
| 8086:294c | 8086:0001 | Intel            | 82566DC-2 Gigabit Network Connection | 64    | e1000e     | [C597415419](<Desktop/Intel/DP35DP/DP35DP AAD81073-207/DD3D47581CBF/UBUNTU-22.04/5.15.0-52-GENERIC/X86_64/C597415419>) |
| 8086:10de | 17aa:3048 | Intel            | 82567LM-3 Gigabit Network Connection | 62    | e1000e     | [2BE395131F](<Desktop/Lenovo/ThinkCentre/ThinkCentre M58p 7220A72/79C1B7350DAA/FEDORA-37/6.2.9-200.FC37.X86_64/X86_64/2BE395131F>) |
| 8086:10d3 | 1043:8369 | Intel            | 82574L Gigabit Network Connection    | 61    | e1000e     | [04E9CD2455](<Desktop/ASUSTek Computer/P9X79/P9X79 WS/F417701E2BAB/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/04E9CD2455>) |
| 8086:1502 | 103c:1494 | Intel            | 82579LM Gigabit Network Connectio... | 61    | e1000e     | [625373A1DE](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite CMT PC/76F58926807D/UBUNTU-22.04/5.15.0-70-GENERIC/X86_64/625373A1DE>) |
| 8086:10de | 103c:3034 | Intel            | 82567LM-3 Gigabit Network Connection | 59    | e1000e     | [DC7B257F83](<Desktop/Hewlett-Packard/Compaq/Compaq dc7900 Small Form Factor/56CDA0F2FEEF/DEBIAN-11/5.10.0-22-AMD64/X86_64/DC7B257F83>) |
| 8086:1521 | 15d9:1521 | Intel            | I350 Gigabit Network Connection      | 59    | igb        | [701907636A](<Desktop/Supermicro/PIO-617/PIO-617R-TLN4F+-ST031/842942F67EF1/DEBIAN-11/5.10.164.2/X86_64/701907636A>) |
| 10de:03ef | 103c:2a6c | Nvidia           | MCP61 Ethernet                       | 58    | forcedeth  | [4C8BB5EFF0](<Desktop/Hewlett-Packard/VC902AA-ABF/VC902AA-ABF p6136fr/84F05A2DC0B4/ANTIX-22/4.9.0-326-ANTIX.1-AMD64-SMP/X86_64/4C8BB5EFF0>) |

### Network and computing encryption device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19e5:a255 |           | Huawei Techno... | HiSilicon SEC Engine                 | 1     | hisi_sec2  | [BD05C84564](<Desktop/HUAWEI/W510/W510 PGU-WBY0/5583E74879DC/UBUNTU-21.04/5.8.0-36-GENERIC/AARCH64/BD05C84564>) |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1485 | 1022:1485 | AMD              | Starship/Matisse Reserved SPP        | 3420  |            | [53D91DCA3C](<Desktop/ASRock/B450M/B450M Steel Legend/57EFD5B4322B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/53D91DCA3C>) |
| 1022:148a | 1022:148a | AMD              | Starship/Matisse PCIe Dummy Function | 3286  |            | [53D91DCA3C](<Desktop/ASRock/B450M/B450M Steel Legend/57EFD5B4322B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/53D91DCA3C>) |
| 1022:1455 | 1022:1455 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 2780  |            | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 1022:145a | 1022:145a | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 2780  |            | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 1022:1485 | 1043:87c0 | AMD              | Starship/Matisse Reserved SPP        | 1302  | vfio_pci   | [4A8C2101E8](<Desktop/ASUSTek Computer/PRIME/PRIME X570-PRO/D1E7CA404339/DEBIAN-11/5.10.0-22-AMD64/X86_64/4A8C2101E8>) |
| 1022:148a | 1043:87c0 | AMD              | Starship/Matisse PCIe Dummy Function | 1302  |            | [4A8C2101E8](<Desktop/ASUSTek Computer/PRIME/PRIME X570-PRO/D1E7CA404339/DEBIAN-11/5.10.0-22-AMD64/X86_64/4A8C2101E8>) |
| 1022:1455 | 1043:8747 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 973   |            | [D9A3AFA732](<Desktop/ASUSTek Computer/ROG/ROG STRIX X470-I GAMING/133421F6DBD4/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/D9A3AFA732>) |
| 1022:145a | 1043:8747 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 973   |            | [D9A3AFA732](<Desktop/ASUSTek Computer/ROG/ROG STRIX X470-I GAMING/133421F6DBD4/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/D9A3AFA732>) |
| 1022:1485 | 1043:8808 | AMD              | Starship/Matisse Reserved SPP        | 738   |            | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 1022:148a | 1043:8808 | AMD              | Starship/Matisse PCIe Dummy Function | 738   |            | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 1022:1485 | 1462:7c02 | AMD              | Starship/Matisse Reserved SPP        | 176   |            | [3A7E1532DA](<Desktop/MSI/MS-7/MS-7C02/ACF3D9051F49/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/3A7E1532DA>) |
| 1022:148a | 1462:7c02 | AMD              | Starship/Matisse PCIe Dummy Function | 176   |            | [3A7E1532DA](<Desktop/MSI/MS-7/MS-7C02/ACF3D9051F49/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/3A7E1532DA>) |
| 1022:145a | 1458:d000 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 157   |            | [E8C596445B](<Desktop/Gigabyte Technology/B550M/B550M DS3H/401B5C2F5C04/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/E8C596445B>) |
| 1022:1485 | 1462:7b86 | AMD              | Starship/Matisse Reserved SPP        | 120   |            | [8AA973E0F5](<Desktop/MSI/MS-7/MS-7B86/E575FEE21E0B/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/8AA973E0F5>) |
| 1022:148a | 1462:7b86 | AMD              | Starship/Matisse PCIe Dummy Function | 120   |            | [8AA973E0F5](<Desktop/MSI/MS-7/MS-7B86/E575FEE21E0B/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/8AA973E0F5>) |
| 1022:145a | 1043:876b | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 109   |            | [369BF3DC68](<Desktop/CMS Computers/7200/7200-5413A/68D04878595E/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/369BF3DC68>) |
| 1022:145a | 1462:7c02 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 97    |            | [0B4FAAA32E](<Desktop/MSI/MS-7/MS-7C02/1C6B1A3D4456/ARCH-ROLLING/6.2.9-273-TKG-CFS/X86_64/0B4FAAA32E>) |
| 1022:1455 | 1462:7c02 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 94    |            | [0B4FAAA32E](<Desktop/MSI/MS-7/MS-7C02/1C6B1A3D4456/ARCH-ROLLING/6.2.9-273-TKG-CFS/X86_64/0B4FAAA32E>) |
| 1022:145a | 1462:7b86 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 87    |            | [51EF82C2FD](<Desktop/MSI/MS-7/MS-7B86/F09A19A83CF0/MANJARO/5.13.19-2-MANJARO/X86_64/51EF82C2FD>) |
| 1022:145a | 1043:8809 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 82    |            | [493BC0B894](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/06DDB3B546A2/NIXOS-23.05/6.2.11/X86_64/493BC0B894>) |
| 1022:1455 | 1462:7b86 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 79    |            | [51EF82C2FD](<Desktop/MSI/MS-7/MS-7B86/F09A19A83CF0/MANJARO/5.13.19-2-MANJARO/X86_64/51EF82C2FD>) |
| 1022:1485 | 1462:7b89 | AMD              | Starship/Matisse Reserved SPP        | 77    |            | [7560923404](<Desktop/MSI/MS-7/MS-7B89/9DE5683930C4/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/7560923404>) |
| 1022:1485 | 1462:7c35 | AMD              | Starship/Matisse Reserved SPP        | 77    |            | [B2311E7CAC](<Desktop/MSI/MS-7/MS-7C35/CB298ECF07E8/ZORIN-16/5.15.0-69-GENERIC/X86_64/B2311E7CAC>) |
| 1022:148a | 1462:7b89 | AMD              | Starship/Matisse PCIe Dummy Function | 77    |            | [7560923404](<Desktop/MSI/MS-7/MS-7B89/9DE5683930C4/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/7560923404>) |
| 1022:148a | 1462:7c35 | AMD              | Starship/Matisse PCIe Dummy Function | 76    |            | [B2311E7CAC](<Desktop/MSI/MS-7/MS-7C35/CB298ECF07E8/ZORIN-16/5.15.0-69-GENERIC/X86_64/B2311E7CAC>) |
| 1022:145a | 1002:15d8 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 65    |            | [117D914E84](<Desktop/Gigabyte Technology/AB350M-DS3H/AB350M-DS3H V2/0A7D4511AD2F/BLACKPANTHER-OS-18.1/5.15.85-DESKTOP-1BP/X86_64/117D914E84>) |
| 1022:145a | 1002:15dd | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 65    |            | [1909560F36](<Desktop/ASRock/A320M-HDV/A320M-HDV R4.0/C783BB75D523/MANJARO/6.1.25-1-MANJARO/X86_64/1909560F36>) |
| 1022:145a | 1462:7a38 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 63    |            | [A9D1794EEC](<Desktop/MSI/MS-7/MS-7A38/C3487D76EFD3/FEDORA-36/6.1.8-100.FC36.X86_64/X86_64/A9D1794EEC>) |
| 1022:1485 | 1462:7c94 | AMD              | Starship/Matisse Reserved SPP        | 59    |            | [26C158DF39](<Desktop/MSI/MS-7/MS-7C94/DD638739FE3A/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/26C158DF39>) |
| 1022:148a | 1462:7c94 | AMD              | Starship/Matisse PCIe Dummy Function | 59    |            | [26C158DF39](<Desktop/MSI/MS-7/MS-7C94/DD638739FE3A/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/26C158DF39>) |
| 1022:1485 | 1462:7c95 | AMD              | Starship/Matisse Reserved SPP        | 56    |            | [76748DA9CD](<Desktop/MSI/MS-7/MS-7C95/E2E66E37A3EB/FEDORA-38/6.2.12-300.FC38.X86_64/X86_64/76748DA9CD>) |
| 1022:148a | 1462:7c95 | AMD              | Starship/Matisse PCIe Dummy Function | 56    |            | [76748DA9CD](<Desktop/MSI/MS-7/MS-7C95/E2E66E37A3EB/FEDORA-38/6.2.12-300.FC38.X86_64/X86_64/76748DA9CD>) |
| 1022:1455 | 1462:7a38 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 54    |            | [A9D1794EEC](<Desktop/MSI/MS-7/MS-7A38/C3487D76EFD3/FEDORA-36/6.1.8-100.FC36.X86_64/X86_64/A9D1794EEC>) |
| 1022:145a | 1002:1636 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 49    |            | [408CBD96C0](<Desktop/ASRock/B550/B550M-HDV/892814B13024/ZORIN-16/5.15.0-71-GENERIC/X86_64/408CBD96C0>) |
| 1022:1485 | 1043:87cb | AMD              | Starship/Matisse Reserved SPP        | 48    |            | [B2AC72F8D9](<Desktop/ASUSTek Computer/PRIME/PRIME TRX40-PRO S/777303348731/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/B2AC72F8D9>) |
| 1022:148a | 1043:87cb | AMD              | Starship/Matisse PCIe Dummy Function | 48    |            | [B2AC72F8D9](<Desktop/ASUSTek Computer/PRIME/PRIME TRX40-PRO S/777303348731/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/B2AC72F8D9>) |
| 1022:1485 | 1462:7a38 | AMD              | Starship/Matisse Reserved SPP        | 47    |            | [A05BD1FFA7](<Desktop/MSI/MS-7/MS-7A38/D9678E934A75/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/A05BD1FFA7>) |
| 1022:148a | 1462:7a38 | AMD              | Starship/Matisse PCIe Dummy Function | 47    |            | [A05BD1FFA7](<Desktop/MSI/MS-7/MS-7A38/D9678E934A75/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/A05BD1FFA7>) |
| 1022:1485 | 1043:8747 | AMD              | Starship/Matisse Reserved SPP        | 46    |            | [FB4C86B0C4](<Desktop/ASUSTek Computer/ROG/ROG STRIX X570-F GAMING/C9A6AB1C0DF9/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/FB4C86B0C4>) |
| 1022:145a | 1462:7b89 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 42    |            | [691239A442](<Desktop/MSI/MS-7/MS-7B89/D27AFC4010A4/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/691239A442>) |
| 1022:1485 | 1043:87e2 | AMD              | Starship/Matisse Reserved SPP        | 39    |            | [98FFA037D9](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550M-PLUS/00BADF5270D7/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/98FFA037D9>) |
| 1022:148a | 1043:87e2 | AMD              | Starship/Matisse PCIe Dummy Function | 39    |            | [98FFA037D9](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550M-PLUS/00BADF5270D7/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/98FFA037D9>) |
| 1022:1455 | 1462:7b89 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 38    |            | [691239A442](<Desktop/MSI/MS-7/MS-7B89/D27AFC4010A4/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/691239A442>) |
| 1022:1485 | 1043:8809 | AMD              | Starship/Matisse Reserved SPP        | 37    |            | [5E9F89E556](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS_BR/3A2AF313A349/ZORIN-16/6.1.8-060108-GENERIC/X86_64/5E9F89E556>) |
| 1022:1485 | 1462:7b85 | AMD              | Starship/Matisse Reserved SPP        | 37    |            | [B2782D28F7](<Desktop/MSI/MS-7/MS-7B85/A1797BB6666C/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/B2782D28F7>) |
| 1022:148a | 1462:7b85 | AMD              | Starship/Matisse PCIe Dummy Function | 37    |            | [B2782D28F7](<Desktop/MSI/MS-7/MS-7B85/A1797BB6666C/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/B2782D28F7>) |
| 1022:1485 | 1043:8815 | AMD              | Starship/Matisse Reserved SPP        | 27    |            | [A82D805AD2](<Desktop/ASUSTek Computer/Pro/Pro WS WRX80E-SAGE SE WIFI/9D10B05EF80F/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/A82D805AD2>) |
| 1022:148a | 1043:8815 | AMD              | Starship/Matisse PCIe Dummy Function | 27    |            | [A82D805AD2](<Desktop/ASUSTek Computer/Pro/Pro WS WRX80E-SAGE SE WIFI/9D10B05EF80F/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/A82D805AD2>) |
| 1022:14de | 1043:8877 | AMD              | Family 19h PCIe Dummy Function Co... | 24    |            | [86B607E7D4](<Desktop/ASUSTek Computer/PRIME/PRIME X670-P WIFI/EBDEB86FD0FB/DEBIAN-11/6.1.20-BOOTES0-P-1000/X86_64/86B607E7D4>) |
| 1022:145a | 1462:7b85 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 23    |            | [E1DA556A0B](<Desktop/MSI/MS-7/MS-7B85/ED1B7710703C/DEBIAN-12/6.2.11-3-LIQUORIX-AMD64/X86_64/E1DA556A0B>) |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15e6 | 1022:15e4 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 89    | i2c_amd... | [B9F947FEC3](<Desktop/BESSTAR Tech/DMAF/DMAF5/E2C64EAEE3A5/DEBIAN-11/5.15.94-X86/X86_64/B9F947FEC3>) |
| 8086:9d24 |           | Intel            | Skylake-U/Y SPI Controller           | 15    |            | [3E60B11752](<Desktop/Google/Teemo/Teemo/01333B2152DC/DEBIAN-11/6.0.0-0.DEB11.6-AMD64/X86_64/3E60B11752>) |
| 8086:a2a4 |           | Intel            | 200 Series/Z370 Chipset Family SP... | 12    |            | [554BE8C07B](<Desktop/Hewlett-Packard/Z4/Z4 G4 Workstation/FA137FCBED0D/ASTRA-1.7_X86-64/5.15.0-33-GENERIC/X86_64/554BE8C07B>) |
| 106b:1801 | 106b:1801 | Apple            | T2 Bridge Controller                 | 8     |            | [015C7769F4](<Desktop/Apple/iMacPro1/iMacPro1,1/C0756435A022/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/015C7769F4>) |
| 106b:1802 | 106b:1802 | Apple            | T2 Secure Enclave Processor          | 8     |            | [015C7769F4](<Desktop/Apple/iMacPro1/iMacPro1,1/C0756435A022/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/015C7769F4>) |
| 8086:a3a4 |           | Intel            | Comet Lake PCH-V SPI (flash) Cont... | 7     | intel_s... | [AEEB40C393](<Desktop/Aquarius/Pro/Pro P30 K43 R53/5EC2E4B7136B/RED-OS-7.3.2/5.15.87-1.EL7.3.X86_64/X86_64/AEEB40C393>) |
| 104c:9065 |           | Texas Instrum... | TMS320DM642                          | 6     |            | [D1C982B241](<Desktop/Dell/OptiPlex/OptiPlex 790/04ECC3DB9661/DEBIAN-11/5.10.0-21-AMD64/X86_64/D1C982B241>) |
| 12ab:0380 | 1cfa:0003 | YUAN High-Tec... | Game Capture 4K60 Pro                | 5     |            | [54EA6926A0](<Desktop/ASUSTek Computer/All/All Series/1262EEC38CBB/STEAMOS/5.13.0-VALVE21-1-NEPTUNE-02209-G2A5BDC1102A0/X86_64/54EA6926A0>) |
| 1022:15e6 | 1849:15e6 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 4     | i2c_amd... | [56AF110EE1](<Desktop/ASRock/4X4/4X4-R1000/12F7C4CC0029/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/56AF110EE1>) |
| 1fff:800e |           | MCST             | System Power Managment (SPMC)        | 4     |            | [5AD56CAB50](<Desktop/Others/Others/Others/FC75BEA27F4E/ALT-P10/5.4.193-MCST-E16C-ALT5.9.4/E2K/5AD56CAB50>) |
| 1b4b:1475 |           | Marvell Techn... |                                      | 3     |            | [9A98A31681](<Desktop/Shuttle/DS81/DS81D/0F649945051C/ALPINE-3.11.2/3.10.105/X86_64/9A98A31681>) |
| 8086:6f06 |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 3     |            | [9A98A31681](<Desktop/Shuttle/DS81/DS81D/0F649945051C/ALPINE-3.11.2/3.10.105/X86_64/9A98A31681>) |
| 8086:8c54 |           | Intel            | C224 Series Chipset Family Server... | 3     |            | [9A98A31681](<Desktop/Shuttle/DS81/DS81D/0F649945051C/ALPINE-3.11.2/3.10.105/X86_64/9A98A31681>) |
| 1ae0:001a | 1ae0:1ae0 | Google           |                                      | 2     |            | [D026C0565D](<Desktop/Google/Guado/Guado/48AA9E819E44/MANJARO/5.17.9-1-MANJARO/X86_64/D026C0565D>) |
| 8086:8c22 |           | Intel            | 8 Series/C220 Series Chipset Fami... | 2     |            | [7F5766D5DA](<Desktop/Others/Others/Others/C3C1AB1B873D/UBUNTU-16.04/3.10.105/X86_64/7F5766D5DA>) |
| 8086:a135 | 8086:a135 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | intel_i... | [C65085AE62](<Desktop/ASUSTek Computer/VC65/VC65R/9C6529D8181C/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/C65085AE62>) |
| 0000:8290 | 0004:0000 |                  |                                      | 1     |            | [2E828331F3](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX-BR/E2EBA532F2BD/DEBIAN-11/5.10.0-12-AMD64/X86_64/2E828331F3>) |
| 0040:0000 | 0040:0000 |                  |                                      | 1     |            | [0FB21440B5](<Desktop/ASUSTek Computer/P5/P5Q-PRO/257E51133C6E/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/0FB21440B5>) |
| 004c:8400 | 0026:0000 |                  |                                      | 1     |            | [2C3F07791C](<Desktop/RM/DESKTOP/DESKTOP 310/A44BD7E77EFE/ENDLESS-3.8.6/5.4.0-42-GENERIC/X86_64/2C3F07791C>) |
| 0090:0000 | 0090:0000 |                  |                                      | 1     |            | [B562E609ED](<Desktop/Gigabyte Technology/GA-970/GA-970A-D3/227EE74CB73B/ROSA-2014.1/4.1.25-NRJ-DESKTOP-1ROSA-X86_64/X86_64/B562E609ED>) |
| 0301:8290 | 14f5:2004 |                  |                                      | 1     |            | [8852623D3D](<Desktop/Gigabyte Technology/GA-MA790/GA-MA790FXT-UD5P/24FF15704A75/UBUNTU-20.04/5.13.0-48-GENERIC/X86_64/8852623D3D>) |
| 0702:82b0 | 168c:2091 |                  |                                      | 1     |            | [DD64B76A65](<Desktop/Gigabyte Technology/H55/H55M-S2H/2BF733EF24FA/UBUNTU-20.04/5.4.0-29-GENERIC/X86_64/DD64B76A65>) |
| 1001:0013 |           | Kolter Electr... | PCI-OPTO-RELAIS Digital I/O board... | 1     |            | [0C8ACC8327](<Desktop/ICP-iEi/SA/SA28/01AF86E623CC/UBUNTU-20.04/5.4.0-29-GENERIC/X86_64/0C8ACC8327>) |
| 1001:0017 |           | Kolter Electr... | PROTO-3 PCI Prototyping board        | 1     |            | [0C8ACC8327](<Desktop/ICP-iEi/SA/SA28/01AF86E623CC/UBUNTU-20.04/5.4.0-29-GENERIC/X86_64/0C8ACC8327>) |
| 100c:8023 | 103c:12f1 | Tseng Labs       |                                      | 1     |            | [AD9D1EDCBB](<Desktop/Hewlett-Packard/workstation/workstation xw8200/42877D7CC761/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/AD9D1EDCBB>) |
| 1106:3038 |           | VIA Technologies | VT82xx/62xx/VX700/8x0/900 UHCI US... | 1     |            | [C9A1706533](<Desktop/ASUSTek Computer/M4A88TD-V/M4A88TD-V EVO-USB3/CF1A7A010A44/ROSA-2016.1/4.9.155-NRJ-DESKTOP-1ROSA-X86_64/X86_64/C9A1706533>) |
| 1274:5882 |           | Ensoniq          |                                      | 1     |            | [3F25A03C59](<Desktop/Gigabyte Technology/8I915PC/8I915PC Duo/D8917D01A4F3/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-I586/I686/3F25A03C59>) |
| 12f4:5000 |           | Megatel          |                                      | 1     |            | [F9A4969283](<Desktop/ASUSTek Computer/M2A-VM/M2A-VM HDMI/DCFAF768DF22/UBUNTU-18.04/4.13.0-46-GENERIC/X86_64/F9A4969283>) |
| 168c:0009 | 118e:305a | Qualcomm Atheros |                                      | 1     |            | [926C7C752C](<Desktop/Dell/Inspiron/Inspiron 537s/45DC7D2BF9EE/UBUNTU-22.04/5.15.0-46-GENERIC/X86_64/926C7C752C>) |
| 168c:0013 | 1186:3813 | Qualcomm Atheros | AR5212/5213/2414 Wireless Network... | 1     | ath5k      | [AADAA92671](<Desktop/ASUSTek Computer/M4N68T-M/M4N68T-M LE/8C4A07736CCD/UBUNTU-18.04/5.3.0-47-GENERIC/X86_64/AADAA92671>) |
| 1814:0203 |           | Ralink           |                                      | 1     |            | [3634FDCD0C](<Desktop/Gigabyte Technology/Z68/Z68XP-UD3/4AB0BCBA6198/UBUNTU-18.04/4.15.0-96-GENERIC/X86_64/3634FDCD0C>) |
| 1a39:0004 | 1a39:e020 |                  |                                      | 1     |            | [93A39661EC](<Desktop/Intel/DQ67EP/DQ67EP AAG12529-308/3D01B542DCD4/UBUNTU-18.04/4.18.0-15-GENERIC/X86_64/93A39661EC>) |
| 1f30:130f | 0030:0000 | Edelweiss        |                                      | 1     |            | [B054EB3BDB](<Desktop/ASUSTek Computer/P7/P7H55-M/0FABBCFE05CF/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/B054EB3BDB>) |
| 4348:3453 |           | WCH.CN           | CH353 PCI Quad Serial Port Contro... | 1     | serial     | [4235BC9196](<Desktop/ASUSTek Computer/H110/H110M-C/36A9E754115A/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-X86_64/X86_64/4235BC9196>) |
| 5555:3b00 | 1a39:0004 | Genroco          | Epiphan DVI2PCIe video capture card  | 1     |            | [7B434E7D8F](<Desktop/ASRockRack/E3/E3C232D4U/04D61E0B2034/LINUXMINT-19.3/5.0.0-32-GENERIC/X86_64/7B434E7D8F>) |
| 8005:0000 |           |                  |                                      | 1     |            | [77F07D2D69](<Desktop/MSI/MS/MS-7641/F496ACA0A489/UBUNTU-18.04/4.18.0-15-GENERIC/X86_64/77F07D2D69>) |
| 8086:22d8 | 8086:7270 | Intel            | Integrated Sensor Solution           | 1     | intel_i... | [61D45F784C](<Desktop/AMI/Cherry/Cherry Trail CR/1690FE8CCA4E/UBUNTU-21.10/5.13.0-40-GENERIC/X86_64/61D45F784C>) |
| 8086:9d35 | 8086:7270 | Intel            | Sunrise Point-LP Integrated Senso... | 1     | intel_i... | [B1128F0534](<Desktop/TECHNOPC/NANO/NANO 5/9DAB26046868/LINUXMINT-20.1/5.4.0-72-GENERIC/X86_64/B1128F0534>) |
| 8086:a135 | 15d9:0884 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | intel_i... | [0D475E91F3](<Desktop/Supermicro/SYS-5019/SYS-5019S-MR/C005568BC543/DEBIAN-11/5.10.0-13-AMD64/X86_64/0D475E91F3>) |
| 8086:a135 | 15d9:089a | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | intel_i... | [4AFDC738DE](<Desktop/Supermicro/SYS-5019/SYS-5019S-L/AD03E66B5687/UBUNTU-18.04/4.15.0-88-GENERIC/X86_64/4AFDC738DE>) |
| a411:0000 | 011b:0808 |                  |                                      | 1     |            | [E79C952746](<Desktop/Prosys/P5/P5GD1-VM/016CE21CE64E/UBUNTU-18.04/5.0.0-37-GENERIC/X86_64/E79C952746>) |
| f810:ffff | ffff:ffff |                  |                                      | 1     |            | [67CBAFF497](<Desktop/Acer/Aspire/Aspire T180/2FE562455A16/UBUNTU-18.04/4.15.0-88-GENERIC/I686/67CBAFF497>) |

### Parallel controller (bidir) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1c00:2170 | 1c00:2170 | WCH              | PCI                                  | 8     |            | [6FB463806F](<Desktop/Gigabyte Technology/Z68/Z68A-D3-B3/1DB45A29F259/DEBIAN-12/6.1.0-6-RT-AMD64/X86_64/6FB463806F>) |
| 1407:8000 |           | Lava Computer... | Lava Parallel                        | 1     | parport_pc | [1733DC0809](<Desktop/ASUSTek Computer/M5/M5A78L-M-USB3/FD5A0CD3675B/DEBIAN-9/5.4.11/X86_64/1733DC0809>) |
| 1415:9523 | 1415:0001 | Oxford Semico... | OX16PCI952 Integrated Parallel Port  | 1     | parport_pc | [AB95A02DA7](<Desktop/Gigabyte Technology/Z77/Z77-DS3H/130931CEF97D/UBUNTU-18.04/4.15.0-99-GENERIC/X86_64/AB95A02DA7>) |
| 1415:9523 | 1415:1201 | Oxford Semico... | OX16PCI952 Integrated Parallel Port  | 1     | parport_pc | [217BFD48BD](<Desktop/Intel/DG33FB/DG33FB AAD81072-309/C69B68BCED37/LMDE-4/4.19.0-10-AMD64/X86_64/217BFD48BD>) |

### Parallel controller (ecp) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1415:c110 | 1415:c110 | Oxford Semico... | OXPCIe952 Parallel Port              | 22    | parport_pc | [39E1F031D9](<Desktop/Dell/Vostro/Vostro 470/5F9483FE6181/UBUNTU-20.04/5.15.0-67-GENERIC/X86_64/39E1F031D9>) |
| 1409:7268 | 1409:0103 | Timedia Techn... | SUN1888 (Dual IEEE1284 parallel p... | 6     | parport_pc | [6872AE9FB4](<Desktop/Packard Bell/IMEDIA/IMEDIA X5705 GE/21629797DC7A/GENTOO-2.7/5.10.52-GENTOO/X86_64/6872AE9FB4>) |
| 1409:7268 | 1409:0104 | Timedia Techn... | SUN1888 (Dual IEEE1284 parallel p... | 1     | parport_pc | [A989D3CA5D](<Desktop/Dell/DV/DV051/1466C2B4297D/UBUNTU-18.04/5.0.0-29-GENERIC/X86_64/A989D3CA5D>) |
| 1415:c11c | 1415:c11c | Oxford Semico... | OXPCIe952 Parallel Port              | 1     | parport_pc | [9D66F53103](<Desktop/Hewlett-Packard/Compaq/Compaq 6000 Pro MT PC/D92123525F26/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/9D66F53103>) |

### Parallel controller (ieee1284) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 9710:9865 | a000:2000 | MosChip Semic... | PCI 9865 Multi-I/O Controller        | 35    | parport_pc | [AA81655AF9](<Desktop/Hewlett-Packard/Compaq/Compaq Pro 6300 SFF/6C84003478A6/LINUXMINT-21.1/5.15.0-70-GENERIC/X86_64/AA81655AF9>) |
| 9710:9912 | a000:2000 | MosChip Semic... | PCIe 9912 Multi-I/O Controller       | 34    | parport... | [5439790362](<Desktop/Gigabyte Technology/AX370-Gaming/AX370-Gaming K7/61FC9FE089AC/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/5439790362>) |
| 1fd4:1999 | 1fd4:0100 | SUNIX            | Multiport serial controller          | 25    | parport... | [DE40052F4C](<Desktop/Hewlett-Packard/Desktop/Desktop Pro A G3/CECBAE87AFA1/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/DE40052F4C>) |
| ffff:9865 | a000:2000 | Illegal Vendo... | Parallel controller                  | 10    |            | [E64A3C2DA5](<Desktop/ASUSTek Computer/P5/P5N73-CM/CC5555A4549D/ZORIN-15/5.4.0-47-GENERIC/X86_64/E64A3C2DA5>) |
| 125b:9100 | a000:2000 | ASIX Electronics | AX99100 PCIe to Multi I/O Controller | 6     |            | [1BE48A395D](<Desktop/Hewlett-Packard/Compaq/Compaq Pro 6300 MT/DB23802515B6/UBUNTU-20.04/5.15.0-69-GENERIC/X86_64/1BE48A395D>) |
| 1415:8403 | 1415:0000 | Oxford Semico... | OX9162 Mode 0 (parallel port)        | 4     | parport_pc | [53C03D6942](<Desktop/ASRock/FM2A88X/FM2A88X Extreme6+/061803342427/FEDORA-37/6.0.11-300.FC37.X86_64/X86_64/53C03D6942>) |
| 9710:9901 | a000:2000 | MosChip Semic... | PCIe 9901 Multi-I/O Controller       | 2     | parport_pc | [5C67654ACF](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH 55i/D5636E96350F/OPENSUSE-TUMBLEWEED-XXXXXXXX/5.16.0-1-DEFAULT/X86_64/5C67654ACF>) |
| 1fd4:1999 | 17aa:0100 | SUNIX            | Multiport serial controller          | 1     |            | [14449A705A](<Desktop/Lenovo/ThinkCentre/ThinkCentre M58p 6234CL2/A2A0A6007D1B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/14449A705A>) |
| 9710:8925 | a000:2100 | MosChip Semic... | MosChip Parallel controller          | 1     |            | [4EDB22DA2D](<Desktop/ASUSTek Computer/V-P8/V-P8H67E/BCC9C221429D/DEBIAN-10/4.19.0-9-AMD64/X86_64/4EDB22DA2D>) |

### Performance counters (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2f30 | 8086:2f30 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 649   | hswep_u... | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2f34 | 8086:2f34 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 PCI... | 649   | hswep_u... | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2f7d | 8086:2f7d | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 649   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2f36 | 8086:2f36 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 601   | hswep_u... | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2f37 | 8086:2f37 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 601   | hswep_u... | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:3c44 | 8086:0000 | Intel            | Xeon E5/Core i7 Ring to QuickPath... | 280   | snbep_u... | [BE15D33D32](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/EE9F1FE423DF/DEBIAN-12/6.1.0-8-AMD64/X86_64/BE15D33D32>) |
| 8086:3ce6 | 8086:0000 | Intel            | Xeon E5/Core i7 QuickPath Interco... | 280   |            | [BE15D33D32](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/EE9F1FE423DF/DEBIAN-12/6.1.0-8-AMD64/X86_64/BE15D33D32>) |
| 8086:3c43 | 8086:0000 | Intel            | Xeon E5/Core i7 Ring to PCI Expre... | 271   | snbep_u... | [BE15D33D32](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/EE9F1FE423DF/DEBIAN-12/6.1.0-8-AMD64/X86_64/BE15D33D32>) |
| 8086:204c | 8086:0000 | Intel            | Sky Lake-E M3KTI Registers           | 249   | skx_uncore | [1C9E5EE2A6](<Desktop/ASUSTek Computer/WS/WS X299 SAGE/7F377E5958FC/LINUXMINT-20.3/5.19.0-17.2-LIQUORIX-AMD64/X86_64/1C9E5EE2A6>) |
| 8086:204d | 8086:0000 | Intel            | Sky Lake-E M3KTI Registers           | 249   | skx_uncore | [1C9E5EE2A6](<Desktop/ASUSTek Computer/WS/WS X299 SAGE/7F377E5958FC/LINUXMINT-20.3/5.19.0-17.2-LIQUORIX-AMD64/X86_64/1C9E5EE2A6>) |
| 8086:0e36 | 8086:0000 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 247   | ivbep_u... | [DD3E55B423](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/86BF2E3E1379/ENDEAVOUROS-ROLLING/6.2.11-ARCH1-1/X86_64/DD3E55B423>) |
| 8086:2015 | 8086:0000 | Intel            | Sky Lake-E Ubox Registers            | 246   |            | [1C9E5EE2A6](<Desktop/ASUSTek Computer/WS/WS X299 SAGE/7F377E5958FC/LINUXMINT-20.3/5.19.0-17.2-LIQUORIX-AMD64/X86_64/1C9E5EE2A6>) |
| 8086:6f30 | 8086:6f30 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 213   | bdx_uncore | [BC30B63CE3](<Desktop/MSI/MS/MS-7885/34D003A502BB/FEDORA-36/6.0.7-200.FC36.X86_64/X86_64/BC30B63CE3>) |
| 8086:6f34 | 8086:6f34 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 213   | bdx_uncore | [BC30B63CE3](<Desktop/MSI/MS/MS-7885/34D003A502BB/FEDORA-36/6.0.7-200.FC36.X86_64/X86_64/BC30B63CE3>) |
| 8086:6f7d | 8086:6f7d | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 213   |            | [BC30B63CE3](<Desktop/MSI/MS/MS-7885/34D003A502BB/FEDORA-36/6.0.7-200.FC36.X86_64/X86_64/BC30B63CE3>) |
| 8086:2f38 | 8086:2f38 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 206   | hswep_u... | [22B0B37A19](<Desktop/MACHINIST/E5-RS9/E5-RS9 V1.11/00E110563FEF/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/22B0B37A19>) |
| 8086:0e34 | 8086:0000 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 196   | ivbep_u... | [DD3E55B423](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/86BF2E3E1379/ENDEAVOUROS-ROLLING/6.2.11-ARCH1-1/X86_64/DD3E55B423>) |
| 8086:6f36 | 8086:6f36 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 188   | bdx_uncore | [7A44B651F4](<Desktop/MACHINIST/E5/E5 MR9A PRO MAX V1.1/3F29047E23B6/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/7A44B651F4>) |
| 8086:6f37 | 8086:6f37 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 188   | bdx_uncore | [7A44B651F4](<Desktop/MACHINIST/E5/E5 MR9A PRO MAX V1.1/3F29047E23B6/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/7A44B651F4>) |
| 8086:3c46 | 8086:0000 | Intel            | Xeon E5/Core i7 Processor Home Ag... | 142   | snbep_u... | [6B1DDBD923](<Desktop/Others/Intel/Intel X79/55A21A587AF6/XERO-ROLLING/6.2.13-ARCH1-1/X86_64/6B1DDBD923>) |
| 8086:3c46 |           | Intel            | Xeon E5/Core i7 Processor Home Ag... | 135   | snbep_u... | [BE15D33D32](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/EE9F1FE423DF/DEBIAN-12/6.1.0-8-AMD64/X86_64/BE15D33D32>) |
| 8086:3c43 | 1043:84ef | Intel            | Xeon E5/Core i7 Ring to PCI Expre... | 130   | snbep_u... | [F9D2B57C91](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X79/F79B74A5FAD0/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/F9D2B57C91>) |
| 8086:3c44 | 1043:84ef | Intel            | Xeon E5/Core i7 Ring to QuickPath... | 130   | snbep_u... | [F9D2B57C91](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X79/F79B74A5FAD0/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/F9D2B57C91>) |
| 8086:3c46 | 1043:84ef | Intel            | Xeon E5/Core i7 Processor Home Ag... | 130   | snbep_u... | [F9D2B57C91](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X79/F79B74A5FAD0/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/F9D2B57C91>) |
| 8086:3ce6 | 1043:84ef | Intel            | Xeon E5/Core i7 QuickPath Interco... | 130   |            | [F9D2B57C91](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X79/F79B74A5FAD0/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/F9D2B57C91>) |
| 8086:0e30 | 8086:0000 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 107   | ivbep_u... | [5070A0A7A7](<Desktop/G7-2011/X/X79/AAAA9989C3C3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/5070A0A7A7>) |
| 8086:0e30 |           | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 91    | ivbep_u... | [DD3E55B423](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/86BF2E3E1379/ENDEAVOUROS-ROLLING/6.2.11-ARCH1-1/X86_64/DD3E55B423>) |
| 8086:3424 |           | Intel            | 7500/5520/5500/X58 Performance Mo... | 84    |            | [B68D1B92DE](<Desktop/Apple/MacPro5/MacPro5,1/E3007916032F/BLENDOS/6.2.13-ARCH1-1/X86_64/B68D1B92DE>) |
| 8086:0e30 | 1043:84ef | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 74    | ivbep_u... | [04E9CD2455](<Desktop/ASUSTek Computer/P9X79/P9X79 WS/F417701E2BAB/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/04E9CD2455>) |
| 8086:0e34 | 1043:84ef | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 74    | ivbep_u... | [04E9CD2455](<Desktop/ASUSTek Computer/P9X79/P9X79 WS/F417701E2BAB/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/04E9CD2455>) |
| 8086:0e36 | 1043:84ef | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 74    | ivbep_u... | [04E9CD2455](<Desktop/ASUSTek Computer/P9X79/P9X79 WS/F417701E2BAB/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/04E9CD2455>) |
| 8086:2f32 | 8086:2f32 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 QPI... | 70    | hswep_u... | [B8C2462ADA](<Desktop/Huanan/X99/X99 F8D V2.2/E58F0A6F2159/ROSA-12.4/6.1.20.XM1-1.KLP-XANMOD-ROSA2021.1-X86_64/X86_64/B8C2462ADA>) |
| 8086:2f33 | 8086:2f33 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 QPI... | 66    | hswep_u... | [B8C2462ADA](<Desktop/Huanan/X99/X99 F8D V2.2/E58F0A6F2159/ROSA-12.4/6.1.20.XM1-1.KLP-XANMOD-ROSA2021.1-X86_64/X86_64/B8C2462ADA>) |
| 8086:6f32 | 8086:6f32 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 55    | bdx_uncore | [65F96586EC](<Desktop/Huanan/X99-F8D/X99-F8D V2.6/F269F65269B2/FEDORA-37/6.2.7-200.FC37.X86_64/X86_64/65F96586EC>) |
| 8086:6f33 | 8086:6f33 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 55    | bdx_uncore | [65F96586EC](<Desktop/Huanan/X99-F8D/X99-F8D V2.6/F269F65269B2/FEDORA-37/6.2.7-200.FC37.X86_64/X86_64/65F96586EC>) |
| 8086:6f38 | 8086:6f38 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 55    | bdx_uncore | [7A44B651F4](<Desktop/MACHINIST/E5/E5 MR9A PRO MAX V1.1/3F29047E23B6/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/7A44B651F4>) |
| 8086:2088 |           | Intel            | Sky Lake-E DDRIO Registers           | 53    | skx_uncore | [553A101CF8](<Desktop/ASUSTek Computer/ROG/ROG STRIX X299-E GAMING/C1F57B2F0914/MANJARO/6.1.25-1-MANJARO/X86_64/553A101CF8>) |
| 8086:3c43 | 1028:0497 | Intel            | Xeon E5/Core i7 Ring to PCI Expre... | 51    | snbep_u... | [04F68362D5](<Desktop/Dell/Precision/Precision T3600/801970AB4520/DEBIAN-10/4.19.0-23-AMD64/X86_64/04F68362D5>) |
| 8086:3c44 | 1028:0497 | Intel            | Xeon E5/Core i7 Ring to QuickPath... | 51    | snbep_u... | [04F68362D5](<Desktop/Dell/Precision/Precision T3600/801970AB4520/DEBIAN-10/4.19.0-23-AMD64/X86_64/04F68362D5>) |
| 8086:3c46 | 1028:0497 | Intel            | Xeon E5/Core i7 Processor Home Ag... | 51    | snbep_u... | [04F68362D5](<Desktop/Dell/Precision/Precision T3600/801970AB4520/DEBIAN-10/4.19.0-23-AMD64/X86_64/04F68362D5>) |
| 8086:3ce6 | 1028:0497 | Intel            | Xeon E5/Core i7 QuickPath Interco... | 51    |            | [04F68362D5](<Desktop/Dell/Precision/Precision T3600/801970AB4520/DEBIAN-10/4.19.0-23-AMD64/X86_64/04F68362D5>) |
| 8086:2f30 | 1849:2f30 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 43    | hswep_u... | [E375BE2EA6](<Desktop/ASRock/X99/X99 Extreme4/1B995760A330/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/E375BE2EA6>) |
| 8086:2f34 | 1849:2f34 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 PCI... | 43    | hswep_u... | [E375BE2EA6](<Desktop/ASRock/X99/X99 Extreme4/1B995760A330/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/E375BE2EA6>) |
| 8086:2f36 | 1462:7885 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 43    | hswep_u... | [A459849BF7](<Desktop/MSI/MS/MS-7885/4916606B25CB/UBUNTU-18.04/5.4.0-107-GENERIC/X86_64/A459849BF7>) |
| 8086:2f36 | 1849:2f36 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 43    | hswep_u... | [E375BE2EA6](<Desktop/ASRock/X99/X99 Extreme4/1B995760A330/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/E375BE2EA6>) |
| 8086:2f37 | 1462:7885 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 43    | hswep_u... | [A459849BF7](<Desktop/MSI/MS/MS-7885/4916606B25CB/UBUNTU-18.04/5.4.0-107-GENERIC/X86_64/A459849BF7>) |
| 8086:2f37 | 1849:2f37 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 43    | hswep_u... | [E375BE2EA6](<Desktop/ASRock/X99/X99 Extreme4/1B995760A330/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/E375BE2EA6>) |
| 8086:2f7d | 1849:2f7d | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 43    |            | [E375BE2EA6](<Desktop/ASRock/X99/X99 Extreme4/1B995760A330/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/E375BE2EA6>) |
| 8086:2088 | 8086:0000 | Intel            | Sky Lake-E DDRIO Registers           | 37    | skx_uncore | [553A101CF8](<Desktop/ASUSTek Computer/ROG/ROG STRIX X299-E GAMING/C1F57B2F0914/MANJARO/6.1.25-1-MANJARO/X86_64/553A101CF8>) |
| 8086:2015 | 1028:0738 | Intel            | Sky Lake-E Ubox Registers            | 29    |            | [EE53C6F627](<Desktop/Dell/Precision/Precision 5820 Tower/BA6A02EAEA31/UBUNTU-20.04/5.14.0-1024-OEM/X86_64/EE53C6F627>) |

### Pic (8259) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:3422 |           | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 971   |            | [7C1ACC3B84](<Desktop/Intel/Thurley/Thurley/39FB9806A69E/DEEPIN-23/5.15.45-AMD64-DESKTOP/X86_64/7C1ACC3B84>) |
| 8086:3423 |           | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 971   |            | [7C1ACC3B84](<Desktop/Intel/Thurley/Thurley/39FB9806A69E/DEEPIN-23/5.15.45-AMD64-DESKTOP/X86_64/7C1ACC3B84>) |
| 8086:342e |           | Intel            | 7500/5520/5500/X58 I/O Hub System... | 971   | i7core_... | [7C1ACC3B84](<Desktop/Intel/Thurley/Thurley/39FB9806A69E/DEEPIN-23/5.15.45-AMD64-DESKTOP/X86_64/7C1ACC3B84>) |
| 8086:3438 |           | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 559   | i5500_temp | [7C1ACC3B84](<Desktop/Intel/Thurley/Thurley/39FB9806A69E/DEEPIN-23/5.15.45-AMD64-DESKTOP/X86_64/7C1ACC3B84>) |
| 8086:3425 |           | Intel            | 7500/5520/5500/X58 Physical and L... | 451   |            | [1F8F3C96A5](<Desktop/Gigabyte Technology/EX58/EX58-UD5/83BDC69E9789/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/1F8F3C96A5>) |
| 8086:3426 |           | Intel            | 7500/5520/5500/X58 Routing and Pr... | 451   |            | [1F8F3C96A5](<Desktop/Gigabyte Technology/EX58/EX58-UD5/83BDC69E9789/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/1F8F3C96A5>) |
| 8086:3427 |           | Intel            | 7500/5520/5500 Physical and Link ... | 400   |            | [1F8F3C96A5](<Desktop/Gigabyte Technology/EX58/EX58-UD5/83BDC69E9789/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/1F8F3C96A5>) |
| 8086:3428 |           | Intel            | 7500/5520/5500 Routing & Protocol... | 400   |            | [1F8F3C96A5](<Desktop/Gigabyte Technology/EX58/EX58-UD5/83BDC69E9789/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/1F8F3C96A5>) |
| 8086:3422 | 0028:0093 | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 99    |            | [6089DFDEAB](<Desktop/Dell/Precision/Precision WorkStation T3500/D5036B82E444/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6089DFDEAB>) |
| 8086:3423 | 0028:0093 | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 99    |            | [6089DFDEAB](<Desktop/Dell/Precision/Precision WorkStation T3500/D5036B82E444/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6089DFDEAB>) |
| 8086:342e | 0028:0093 | Intel            | 7500/5520/5500/X58 I/O Hub System... | 99    | i7core_... | [6089DFDEAB](<Desktop/Dell/Precision/Precision WorkStation T3500/D5036B82E444/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6089DFDEAB>) |
| 8086:3422 | 0028:006e | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 50    |            | [CBB78E1785](<Desktop/Dell/Precision/Precision WorkStation T5500/DC574BF9309D/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/CBB78E1785>) |
| 8086:3423 | 0028:006e | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 50    |            | [CBB78E1785](<Desktop/Dell/Precision/Precision WorkStation T5500/DC574BF9309D/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/CBB78E1785>) |
| 8086:342e | 0028:006e | Intel            | 7500/5520/5500/X58 I/O Hub System... | 50    | i7core_... | [CBB78E1785](<Desktop/Dell/Precision/Precision WorkStation T5500/DC574BF9309D/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/CBB78E1785>) |
| 8086:3422 | 0086:0022 | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 39    |            | [8C80FD3109](<Desktop/Lenovo/ThinkStation/ThinkStation D20 4158AF8/EF4EEEE3E2FB/BLACKPANTHER-OS-22.1/6.2.9-DESKTOP-1BP/X86_64/8C80FD3109>) |
| 8086:3423 | 0086:0023 | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 39    |            | [8C80FD3109](<Desktop/Lenovo/ThinkStation/ThinkStation D20 4158AF8/EF4EEEE3E2FB/BLACKPANTHER-OS-22.1/6.2.9-DESKTOP-1BP/X86_64/8C80FD3109>) |
| 8086:342e | 0086:002e | Intel            | 7500/5520/5500/X58 I/O Hub System... | 39    | i7core_... | [8C80FD3109](<Desktop/Lenovo/ThinkStation/ThinkStation D20 4158AF8/EF4EEEE3E2FB/BLACKPANTHER-OS-22.1/6.2.9-DESKTOP-1BP/X86_64/8C80FD3109>) |
| 8086:3422 | 0028:006d | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 28    |            | [7AEF52516B](<Desktop/Dell/Precision/Precision WorkStation T7500/5BA9A5976E40/KUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/7AEF52516B>) |
| 8086:3423 | 0028:006d | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 28    |            | [7AEF52516B](<Desktop/Dell/Precision/Precision WorkStation T7500/5BA9A5976E40/KUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/7AEF52516B>) |
| 8086:342e | 0028:006d | Intel            | 7500/5520/5500/X58 I/O Hub System... | 28    | i7core_... | [7AEF52516B](<Desktop/Dell/Precision/Precision WorkStation T7500/5BA9A5976E40/KUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/7AEF52516B>) |
| 8086:3422 | 003c:000b | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 25    |            | [76DC3DB16A](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML150 G6/4CC82A74846D/DEBIAN-12/6.1.0-5-AMD64/X86_64/76DC3DB16A>) |
| 8086:3423 | 003c:000b | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 25    |            | [76DC3DB16A](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML150 G6/4CC82A74846D/DEBIAN-12/6.1.0-5-AMD64/X86_64/76DC3DB16A>) |
| 8086:342e | 003c:000b | Intel            | 7500/5520/5500/X58 I/O Hub System... | 25    | i7core_... | [76DC3DB16A](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML150 G6/4CC82A74846D/DEBIAN-12/6.1.0-5-AMD64/X86_64/76DC3DB16A>) |
| 8086:3422 | 0043:0063 | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 10    |            | [1CD6DA46F3](<Desktop/ASUSTek Computer/Z8/Z8NA-D6/06CAAFFC2726/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/1CD6DA46F3>) |
| 8086:3423 | 0043:0063 | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 10    |            | [1CD6DA46F3](<Desktop/ASUSTek Computer/Z8/Z8NA-D6/06CAAFFC2726/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/1CD6DA46F3>) |
| 8086:3425 | 0043:0063 | Intel            | 7500/5520/5500/X58 Physical and L... | 10    |            | [1CD6DA46F3](<Desktop/ASUSTek Computer/Z8/Z8NA-D6/06CAAFFC2726/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/1CD6DA46F3>) |
| 8086:3426 | 0043:0063 | Intel            | 7500/5520/5500/X58 Routing and Pr... | 10    |            | [1CD6DA46F3](<Desktop/ASUSTek Computer/Z8/Z8NA-D6/06CAAFFC2726/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/1CD6DA46F3>) |
| 8086:3427 | 0043:0063 | Intel            | 7500/5520/5500 Physical and Link ... | 10    |            | [1CD6DA46F3](<Desktop/ASUSTek Computer/Z8/Z8NA-D6/06CAAFFC2726/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/1CD6DA46F3>) |
| 8086:3428 | 0043:0063 | Intel            | 7500/5520/5500 Routing & Protocol... | 10    |            | [1CD6DA46F3](<Desktop/ASUSTek Computer/Z8/Z8NA-D6/06CAAFFC2726/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/1CD6DA46F3>) |
| 8086:342e | 0043:0063 | Intel            | 7500/5520/5500/X58 I/O Hub System... | 10    | i7core_... | [1CD6DA46F3](<Desktop/ASUSTek Computer/Z8/Z8NA-D6/06CAAFFC2726/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/1CD6DA46F3>) |
| 8086:3438 | 0043:0063 | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 10    | i5500_temp | [1CD6DA46F3](<Desktop/ASUSTek Computer/Z8/Z8NA-D6/06CAAFFC2726/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/1CD6DA46F3>) |
| 8086:3422 | 0043:0064 | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 1     |            | [A085ED0138](<Desktop/ASUSTek Computer/Z8/Z8P/10681C290374/FEDORA-33/5.14.18-100.FC33.X86_64/X86_64/A085ED0138>) |
| 8086:3423 | 0043:0064 | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 1     |            | [A085ED0138](<Desktop/ASUSTek Computer/Z8/Z8P/10681C290374/FEDORA-33/5.14.18-100.FC33.X86_64/X86_64/A085ED0138>) |
| 8086:3425 | 0043:0064 | Intel            | 7500/5520/5500/X58 Physical and L... | 1     |            | [A085ED0138](<Desktop/ASUSTek Computer/Z8/Z8P/10681C290374/FEDORA-33/5.14.18-100.FC33.X86_64/X86_64/A085ED0138>) |
| 8086:3426 | 0043:0064 | Intel            | 7500/5520/5500/X58 Routing and Pr... | 1     |            | [A085ED0138](<Desktop/ASUSTek Computer/Z8/Z8P/10681C290374/FEDORA-33/5.14.18-100.FC33.X86_64/X86_64/A085ED0138>) |
| 8086:3427 | 0043:0064 | Intel            | 7500/5520/5500 Physical and Link ... | 1     |            | [A085ED0138](<Desktop/ASUSTek Computer/Z8/Z8P/10681C290374/FEDORA-33/5.14.18-100.FC33.X86_64/X86_64/A085ED0138>) |
| 8086:3428 | 0043:0064 | Intel            | 7500/5520/5500 Routing & Protocol... | 1     |            | [A085ED0138](<Desktop/ASUSTek Computer/Z8/Z8P/10681C290374/FEDORA-33/5.14.18-100.FC33.X86_64/X86_64/A085ED0138>) |
| 8086:342e | 0043:0064 | Intel            | 7500/5520/5500/X58 I/O Hub System... | 1     | i7core_... | [A085ED0138](<Desktop/ASUSTek Computer/Z8/Z8P/10681C290374/FEDORA-33/5.14.18-100.FC33.X86_64/X86_64/A085ED0138>) |
| 8086:3438 | 0043:0064 | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 1     |            | [A085ED0138](<Desktop/ASUSTek Computer/Z8/Z8P/10681C290374/FEDORA-33/5.14.18-100.FC33.X86_64/X86_64/A085ED0138>) |

### Pic (io(x)-apic) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2f2c | 8086:0000 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 478   |            | [22B0B37A19](<Desktop/MACHINIST/E5-RS9/E5-RS9 V1.11/00E110563FEF/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/22B0B37A19>) |
| 8086:342f |           | Intel            | 7500/5520/5500/X58 Trusted Execut... | 399   |            | [1F8F3C96A5](<Desktop/Gigabyte Technology/EX58/EX58-UD5/83BDC69E9789/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/1F8F3C96A5>) |
| 8086:3c2c | 8086:3c2c | Intel            | Xeon E5/Core i7 I/O APIC             | 277   |            | [BE15D33D32](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/EE9F1FE423DF/DEBIAN-12/6.1.0-8-AMD64/X86_64/BE15D33D32>) |
| 8086:342d |           | Intel            | 7500/5520/5500/X58 I/O Hub I/OxAP... | 238   |            | [1F8F3C96A5](<Desktop/Gigabyte Technology/EX58/EX58-UD5/83BDC69E9789/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/1F8F3C96A5>) |
| 8086:2026 | 8086:2026 | Intel            | Sky Lake-E IOAPIC                    | 231   |            | [1C9E5EE2A6](<Desktop/ASUSTek Computer/WS/WS X299 SAGE/7F377E5958FC/LINUXMINT-20.3/5.19.0-17.2-LIQUORIX-AMD64/X86_64/1C9E5EE2A6>) |
| 8086:2036 | 8086:2036 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 231   |            | [1C9E5EE2A6](<Desktop/ASUSTek Computer/WS/WS X299 SAGE/7F377E5958FC/LINUXMINT-20.3/5.19.0-17.2-LIQUORIX-AMD64/X86_64/1C9E5EE2A6>) |
| 8086:0e2c | 8086:0e2c | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 186   |            | [DD3E55B423](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/86BF2E3E1379/ENDEAVOUROS-ROLLING/6.2.11-ARCH1-1/X86_64/DD3E55B423>) |
| 8086:6f2c | 8086:0000 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 148   |            | [7A44B651F4](<Desktop/MACHINIST/E5/E5 MR9A PRO MAX V1.1/3F29047E23B6/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/7A44B651F4>) |
| 8086:3c2c | 1043:84ef | Intel            | Xeon E5/Core i7 I/O APIC             | 130   |            | [F9D2B57C91](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X79/F79B74A5FAD0/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/F9D2B57C91>) |
| 8086:0e2c | 1043:84ef | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 74    |            | [04E9CD2455](<Desktop/ASUSTek Computer/P9X79/P9X79 WS/F417701E2BAB/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/04E9CD2455>) |
| 1106:5327 |           | VIA Technologies | P4M890 I/O APIC Interrupt Controller | 60    |            | [3D02816B24](<Desktop/Medion/MS/MS-7318/04DDF3A09383/DEBIAN-11/5.10.0-21-AMD64/X86_64/3D02816B24>) |
| 1106:5364 |           | VIA Technologies | CN896/VN896/P4M900 I/O APIC Inter... | 56    |            | [8CBD1DCE35](<Desktop/IBM/4800743/4800743/42C6A9D2CCE8/UBUNTU-18.04/5.3.0-28-GENERIC/X86_64/8CBD1DCE35>) |
| 8086:3c2c | 1028:0497 | Intel            | Xeon E5/Core i7 I/O APIC             | 51    |            | [04F68362D5](<Desktop/Dell/Precision/Precision T3600/801970AB4520/DEBIAN-10/4.19.0-23-AMD64/X86_64/04F68362D5>) |
| 8086:2f2c | 1028:0617 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 47    |            | [33517B7BFE](<Desktop/Dell/Precision/Precision Tower 5810/4630C280B407/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/33517B7BFE>) |
| 8086:2f2c | 1849:2f2c | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 43    |            | [E375BE2EA6](<Desktop/ASRock/X99/X99 Extreme4/1B995760A330/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/E375BE2EA6>) |
| 8086:2f2c | 1462:7885 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 38    |            | [A459849BF7](<Desktop/MSI/MS/MS-7885/4916606B25CB/UBUNTU-18.04/5.4.0-107-GENERIC/X86_64/A459849BF7>) |
| 8086:3504 |           | Intel            | 6311ESB/6321ESB I/OxAPIC Interrup... | 31    |            | [16CAC427E3](<Desktop/Apple/MacPro1/MacPro1,1/35AFB7E133B4/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/16CAC427E3>) |
| 8086:2026 | 1028:0738 | Intel            | Sky Lake-E IOAPIC                    | 29    |            | [EE53C6F627](<Desktop/Dell/Precision/Precision 5820 Tower/BA6A02EAEA31/UBUNTU-20.04/5.14.0-1024-OEM/X86_64/EE53C6F627>) |
| 8086:2036 | 1028:0738 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 29    |            | [EE53C6F627](<Desktop/Dell/Precision/Precision 5820 Tower/BA6A02EAEA31/UBUNTU-20.04/5.14.0-1024-OEM/X86_64/EE53C6F627>) |
| 8086:3c2c | 1458:5000 | Intel            | Xeon E5/Core i7 I/O APIC             | 29    |            | [1DD1BCD00E](<Desktop/Gigabyte Technology/X79/X79-UD3/31785A783625/EURO-9.1/5.14.0-162.23.1.EL9_1.X86_64/X86_64/1DD1BCD00E>) |
| 8086:0e2c | 1028:05d2 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 28    |            | [17D5390549](<Desktop/Dell/Precision/Precision T3610/0F1E300DF42D/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/17D5390549>) |
| 1106:5308 | 1849:5308 | VIA Technologies | PT894 I/O APIC Interrupt Controller  | 24    |            | [89CCDD7262](<Desktop/ASRock/775/775Dual-VSTA/C993403882F6/LMDE-5/5.10.0-22-AMD64/X86_64/89CCDD7262>) |
| 8086:0e2c | 8086:0000 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 24    |            | [80EA529A18](<Desktop/Apple/MacPro6/MacPro6,1/B437B08EC19A/FEDORA-37/6.2.12-200.FC37.X86_64/X86_64/80EA529A18>) |
| 8086:2f2c | 1028:0618 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 23    |            | [08502CDA27](<Desktop/Dell/Precision/Precision Tower 7810/46536ED933CB/UBUNTU-MATE-20.04/5.4.0-126-GENERIC/X86_64/08502CDA27>) |
| 8086:6f2c | 1849:6f2c | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 22    |            | [136A9303C0](<Desktop/ASRockRack/D1521/D1521D4I2/E866121B6A2E/ZORIN-16/5.15.0-71-GENERIC/X86_64/136A9303C0>) |
| 1106:5336 |           | VIA Technologies | K8M890CE I/O APIC Interrupt Contr... | 20    |            | [1B9074E1AC](<Desktop/MSI/MS/MS-7253/68BDCC55CDD4/DEBIAN-11/5.10.0-21-AMD64/X86_64/1B9074E1AC>) |
| 8086:0e2c | 1458:5000 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 20    |            | [8F9B60CAF3](<Desktop/Gigabyte Technology/X79/X79-UP4/98516C2BB9F9/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/8F9B60CAF3>) |
| 8086:3c2c | 1849:3c2c | Intel            | Xeon E5/Core i7 I/O APIC             | 19    |            | [1287699F09](<Desktop/ASRock/X79/X79 Extreme6/9951D6C7C041/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/1287699F09>) |
| 8086:3c2c | 8086:4953 | Intel            | Xeon E5/Core i7 I/O APIC             | 16    |            | [9D21F71F9D](<Desktop/Intel/DX79TO/DX79TO AAG28805-402/EEFE3A6B3960/UBUNTU-20.04/5.4.0-144-GENERIC/X86_64/9D21F71F9D>) |
| 8086:6f2c | 1028:0617 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 16    |            | [73CC9E48A0](<Desktop/Dell/Precision/Precision Tower 5810/42058049234F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/73CC9E48A0>) |
| 1106:5364 | 1106:5364 | VIA Technologies | CN896/VN896/P4M900 I/O APIC Inter... | 15    |            | [1F49477ABF](<Desktop/MSI/MS/MS-7387/66739E36F2FF/XUBUNTU-20.04/5.4.0-125-GENERIC/X86_64/1F49477ABF>) |
| 8086:2026 | 8086:0000 | Intel            | Sky Lake-E IOAPIC                    | 15    |            | [554BE8C07B](<Desktop/Hewlett-Packard/Z4/Z4 G4 Workstation/FA137FCBED0D/ASTRA-1.7_X86-64/5.15.0-33-GENERIC/X86_64/554BE8C07B>) |
| 8086:2036 | 8086:0000 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 15    |            | [554BE8C07B](<Desktop/Hewlett-Packard/Z4/Z4 G4 Workstation/FA137FCBED0D/ASTRA-1.7_X86-64/5.15.0-33-GENERIC/X86_64/554BE8C07B>) |
| 8086:3c2c | 17aa:1026 | Intel            | Xeon E5/Core i7 I/O APIC             | 15    |            | [EA3855CCA5](<Desktop/Lenovo/ThinkStation/ThinkStation S30 0568E8G/80EBD2E9BDCA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/EA3855CCA5>) |
| 8086:3c2c | 1028:0496 | Intel            | Xeon E5/Core i7 I/O APIC             | 14    |            | [E48D83D96D](<Desktop/Dell/Precision/Precision T5600/757ABB1D6B63/LMDE-5/5.10.0-21-AMD64/X86_64/E48D83D96D>) |
| 8086:3c2c | 1028:0495 | Intel            | Xeon E5/Core i7 I/O APIC             | 13    |            | [6316886F98](<Desktop/Dell/Precision/Precision T7600/571CD65BB927/LINUXMINT-21.1/5.15.0-70-GENERIC/X86_64/6316886F98>) |
| 8086:0e2c | 1028:05d3 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 12    |            | [CC1233B9B9](<Desktop/Dell/Precision/Precision T5610/B67B29961B2E/MANJARO-22.1.0/5.15.106-1-MANJARO/X86_64/CC1233B9B9>) |
| 8086:0e2c | 1028:05d4 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 11    |            | [7C5F606C7D](<Desktop/Dell/Precision/Precision T7610/48D158544983/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/7C5F606C7D>) |
| 8086:0e2c | 17aa:1026 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 11    |            | [06086E6112](<Desktop/Lenovo/ThinkStation/ThinkStation S30 4352D1M/25D3482F0C54/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/06086E6112>) |
| 8086:2026 | 17aa:1036 | Intel            | Sky Lake-E IOAPIC                    | 10    |            | [EEB37C9C4F](<Desktop/Lenovo/ThinkStation/ThinkStation P520 30BE008VGE/23EB6AE8CDFC/OPENSUSE-LEAP-15.4/5.14.21-150400.24.60-DEFAULT/X86_64/EEB37C9C4F>) |
| 8086:2036 | 17aa:1036 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 10    |            | [EEB37C9C4F](<Desktop/Lenovo/ThinkStation/ThinkStation P520 30BE008VGE/23EB6AE8CDFC/OPENSUSE-LEAP-15.4/5.14.21-150400.24.60-DEFAULT/X86_64/EEB37C9C4F>) |
| 8086:3c2c | 1734:11b5 | Intel            | Xeon E5/Core i7 I/O APIC             | 10    |            | [64B9978ED0](<Desktop/Fujitsu/CELSIUS/CELSIUS M720/D4C7881F195A/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/64B9978ED0>) |
| 8086:6f2c | 1028:0619 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 10    |            | [F76BC64EE4](<Desktop/Dell/Precision/Precision Tower 7910/96D37272A606/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/F76BC64EE4>) |
| 8086:2026 | 1028:08b1 | Intel            | Sky Lake-E IOAPIC                    | 9     |            | [B3C31072BB](<Desktop/Dell/Precision/Precision 5820 Tower X-Series/5201489B82F8/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/B3C31072BB>) |
| 8086:2036 | 1028:08b1 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 9     |            | [B3C31072BB](<Desktop/Dell/Precision/Precision 5820 Tower X-Series/5201489B82F8/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/B3C31072BB>) |
| 8086:6f2c | 1462:7885 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 9     |            | [BC30B63CE3](<Desktop/MSI/MS/MS-7885/34D003A502BB/FEDORA-36/6.0.7-200.FC36.X86_64/X86_64/BC30B63CE3>) |
| 8086:2026 | 1734:122f | Intel            | Sky Lake-E IOAPIC                    | 8     |            | [F20338E169](<Desktop/Fujitsu/CELSIUS/CELSIUS M770/97AA6CA11B9F/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/F20338E169>) |
| 8086:2036 | 1734:122f | Intel            | Sky Lake-E IOxAPIC Configuration ... | 8     |            | [F20338E169](<Desktop/Fujitsu/CELSIUS/CELSIUS M770/97AA6CA11B9F/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/F20338E169>) |
| 8086:2f2c | 1028:0619 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 8     |            | [960E8817BF](<Desktop/Dell/Precision/Precision Tower 7910/9A6D97868F75/UBUNTU-22.04/5.15.0-25-GENERIC/X86_64/960E8817BF>) |
| 8086:0e2c | 1849:0e2c | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 7     |            | [2B3F00AC79](<Desktop/ASRock/X79/X79 Extreme6/6813C1E7BD55/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/2B3F00AC79>) |

### Pic (io-apic) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:7451 | 1022:7450 | AMD              | AMD-8131 PCI-X IOAPIC                | 4     |            | [A94946D561](<Desktop/Hewlett-Packard/xw9300/xw9300 Workstation/796D0561C4B4/LUBUNTU-20.04/5.8.0-53-GENERIC/X86_64/A94946D561>) |
| 1022:7459 | 1022:7459 | AMD              | AMD-8132 PCI-X IOAPIC                | 1     |            | [68059DB0EE](<Desktop/Supermicro/H8/H8QM8/1DAD0B606684/KDE-NEON-20.04/5.11.0-25-GENERIC/X86_64/68059DB0EE>) |
| 1104:0844 | 1043:89ff | RasterOps        | PIC                                  | 1     |            | [5C55046F50](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/2609B3602999/PARROT-4.11/5.14.0-9PARROT1-AMD64/X86_64/5C55046F50>) |

### Power pc (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1957:c006 | 1a56:1201 | Freescale Sem... | MPC8308                              | 9     |            | [59B1AE56DD](<Desktop/Gigabyte Technology/G1/G1.Sniper/0CB7455705A6/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/59B1AE56DD>) |
| 1957:00b6 | 1a56:1103 | Freescale Sem... | MPC8314E                             | 3     |            | [AC26E59E63](<Desktop/ASRock/X58/X58 Extreme/5C2A22D48369/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/AC26E59E63>) |
| 1957:0085 | 110a:4046 | Freescale Sem... | MPC8347 PBGA                         | 1     |            | [60A7685D8D](<Desktop/SIEMENS/SIMATIC/SIMATIC IPC547D/A5B87CC67308/UBUNTU-18.04/4.15.0-20-GENERIC/X86_64/60A7685D8D>) |
| 1957:00b6 | 1a56:1101 | Freescale Sem... | MPC8314E                             | 1     |            | [FC18CDC2FD](<Desktop/ASUSTek Computer/All/All Series/CEA802D185FD/UBUNTU-20.04/5.8.0-43-GENERIC/X86_64/FC18CDC2FD>) |

### Processing accelerators (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ee:5000 | 10ee:000e | Xilinx           | Alveo U200 XDMA Platform             | 1     | xclmgmt    | [774E748AB4](<Desktop/ASUSTek Computer/H370/H370 MINING MASTER/4CCB446388B7/UBUNTU-18.04/4.15.0-42-GENERIC/X86_64/774E748AB4>) |
| 10ee:5001 | 10ee:000e | Xilinx           | Processing accelerators              | 1     | xocl       | [774E748AB4](<Desktop/ASUSTek Computer/H370/H370 MINING MASTER/4CCB446388B7/UBUNTU-18.04/4.15.0-42-GENERIC/X86_64/774E748AB4>) |
| 10ee:d020 | 10ee:000e | Xilinx           | Alveo U50 Golden Image               | 1     | xclmgmt    | [7C4EF83797](<Desktop/Dell/Precision/Precision 3640 Tower/9FD6CBA97203/UBUNTU-18.04/5.4.0-54-GENERIC/X86_64/7C4EF83797>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:31cc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 137   | sdhci_pci  | [22D1FBDEEE](<Desktop/Others/Others/Others/7E2DCAD143A6/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/22D1FBDEEE>) |
| 1022:7806 | 1022:7806 | AMD              | FCH SD Flash Controller              | 93    | sdhci_pci  | [6ECB91213C](<Desktop/MSI/MS/MS-7695/0F3620AFC39E/OPENMANDRIVA-4.2/5.11.12-DESKTOP-1OMV4002/X86_64/6ECB91213C>) |
| 8086:31d0 | 8086:7270 | Intel            | Celeron/Pentium Silver SD Host Co... | 81    | sdhci_pci  | [22D1FBDEEE](<Desktop/Others/Others/Others/7E2DCAD143A6/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/22D1FBDEEE>) |
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 72    | sdhci_pci  | [5F99EBEED7](<Desktop/Others/1/1.0/0C5E2BF873F0/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/5F99EBEED7>) |
| 8086:5aca | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 57    | sdhci_pci  | [5F99EBEED7](<Desktop/Others/1/1.0/0C5E2BF873F0/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/5F99EBEED7>) |
| 8086:5ad0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 51    | sdhci_pci  | [5F99EBEED7](<Desktop/Others/1/1.0/0C5E2BF873F0/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/5F99EBEED7>) |
| 8086:9d2b | 8086:7270 | Intel            | Skylake-U/Y SCC: eMMC                | 27    | sdhci_pci  | [9CD0292459](<Desktop/Others/SKYBAY/SKYBAY/4A23938B85BE/OPENMANDRIVA-23.01/6.1.4-DESKTOP-1OMV2301/X86_64/9CD0292459>) |
| 8086:06f5 | 103c:8767 | Intel            | 400 Series Chipset Family SD Host... | 26    | sdhci_pci  | [186BAD76B7](<Desktop/Hewlett-Packard/ENVY/ENVY TE01-1xxx/78901717D0EA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/186BAD76B7>) |
| 8086:9d2d | 8086:7270 | Intel            | Sunrise Point-LP Secure Digital I... | 24    | sdhci_pci  | [9CD0292459](<Desktop/Others/SKYBAY/SKYBAY/4A23938B85BE/OPENMANDRIVA-23.01/6.1.4-DESKTOP-1OMV2301/X86_64/9CD0292459>) |
| 8086:4dc4 |           | Intel            | Jasper Lake SCS1: eMMC Controller    | 23    | sdhci_pci  | [2389FCEA33](<Desktop/Others/Others/Others/F7930C54D6D6/POP!_OS-22.04/6.2.0-76060200-GENERIC/X86_64/2389FCEA33>) |
| 8086:4dc4 | 8086:7270 | Intel            | Jasper Lake SCS1: eMMC Controller    | 22    | sdhci_pci  | [76FF5C3BD7](<Desktop/Intel/Jasper/Jasper Lake Client Platform/5E67453FB64F/ELEMENTARY-7/5.19.0-41-GENERIC/X86_64/76FF5C3BD7>) |
| 8086:a375 | 103c:843f | Intel            | 300 Series Chipset Family SD Host... | 19    | sdhci_pci  | [0060103F89](<Desktop/Hewlett-Packard/Slim/Slim Desktop 290-p0xxx/CA367B3BCB81/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/0060103F89>) |
| 8086:4df8 |           | Intel            | SD Host Controller                   | 18    | sdhci_pci  | [169B9F8BAB](<Desktop/BESSTAR Tech/JB/JB95/BC308EB944C7/LINUXMINT-21.1/5.15.0-67-GENERIC/X86_64/169B9F8BAB>) |
| 8086:9dc4 | 8086:7270 | Intel            | Cannon Point-LP SD Host Controller   | 18    | sdhci_pci  | [5D06AF8741](<Desktop/Others/Others/Others/C67655D87C52/ALT-10.1/5.15.102-UN-DEF-ALT1/X86_64/5D06AF8741>) |
| 10ec:5209 | 10ec:5209 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 16    | rtsx_pci   | [23EE51B834](<Desktop/Acer/Revo/Revo RL80/4302B4AE6F85/ZORIN-16/5.15.0-67-GENERIC/X86_64/23EE51B834>) |
| 8086:31cc | 1458:1000 | Intel            | Celeron/Pentium Silver Processor ... | 16    | sdhci_pci  | [C9427F4873](<Desktop/Gigabyte Technology/MZGLKDP/MZGLKDP-00/8F7D16F85552/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/C9427F4873>) |
| 8086:31d0 | 1458:1000 | Intel            | Celeron/Pentium Silver SD Host Co... | 16    | sdhci_pci  | [C9427F4873](<Desktop/Gigabyte Technology/MZGLKDP/MZGLKDP-00/8F7D16F85552/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/C9427F4873>) |
| 8086:a375 | 103c:8653 | Intel            | 300 Series Chipset Family SD Host... | 16    | sdhci_pci  | [5854A10EB0](<Desktop/Hewlett-Packard/ENVY/ENVY TE01-0xxx/9314F9E0DC42/LINUXMINT-20.1/5.4.0-139-GENERIC/X86_64/5854A10EB0>) |
| 8086:a375 | 103c:843b | Intel            | 300 Series Chipset Family SD Host... | 15    | sdhci_pci  | [2E7BF7FF44](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop 590-p0xxx/B02432335DCA/CLEAR-LINUX-OS-38520/6.2.2-1285.NATIVE/X86_64/2E7BF7FF44>) |
| 8086:9df5 | 8086:7270 | Intel            | BayHubTech Integrated SD controller  | 14    | sdhci_pci  | [5D06AF8741](<Desktop/Others/Others/Others/C67655D87C52/ALT-10.1/5.15.102-UN-DEF-ALT1/X86_64/5D06AF8741>) |
| 1022:7813 | 1022:7806 | AMD              | FCH SD Flash Controller              | 12    | sdhci_pci  | [269FA69513](<Desktop/PC Engines/APU/APU2/77E626F5EF1E/DEBIAN-11/5.10.0-11-AMD64/X86_64/269FA69513>) |
| 197b:2381 | 103c:2aa2 | JMicron Techn... | Standard SD Host Controller          | 11    | sdhci_pci  | [28C42FC95F](<Desktop/Hewlett-Packard/200/200-5112za/08FF896C77FB/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/28C42FC95F>) |
| 8086:2294 | 1458:1000 | Intel            | Atom/Celeron/Pentium Processor x5... | 11    | sdhci_pci  | [525AC20362](<Desktop/Gigabyte Technology/GB-BACE/GB-BACE-3150/B48405EE0C5D/XUBUNTU-22.04/5.19.0-32-GENERIC/X86_64/525AC20362>) |
| 8086:9d2d | 8086:9d2d | Intel            | Sunrise Point-LP Secure Digital I... | 11    | sdhci_pci  | [3E60B11752](<Desktop/Google/Teemo/Teemo/01333B2152DC/DEBIAN-11/6.0.0-0.DEB11.6-AMD64/X86_64/3E60B11752>) |
| 8086:a375 | 103c:844c | Intel            | 300 Series Chipset Family SD Host... | 11    | sdhci_pci  | [8270D682A8](<Desktop/Hewlett-Packard/Pavilion/Pavilion Gaming Desktop 790-08xx/977BC50E66E3/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/8270D682A8>) |
| 8086:a375 | 1849:a375 | Intel            | 300 Series Chipset Family SD Host... | 11    | sdhci_pci  | [9988BC063A](<Desktop/ASRock/H310/H310M-STX/9A2F70205900/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/9988BC063A>) |
| 197b:2381 | 1297:2005 | JMicron Techn... | Standard SD Host Controller          | 10    | sdhci_pci  | [9888356D3D](<Desktop/Standard/XS/XS35/AA102333E166/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/9888356D3D>) |
| 1022:7906 | 17aa:3100 | AMD              | FCH SD Flash Controller              | 9     | sdhci_pci  | [96F24866E0](<Desktop/Lenovo/IdeaCentre/IdeaCentre 510-15ABR 90G7002RGE/F3B5E391CD2C/ZORIN-16/5.15.0-58-GENERIC/X86_64/96F24866E0>) |
| 8086:4df8 | 8086:7270 | Intel            | SD Host Controller                   | 9     | sdhci_pci  | [429D6F994A](<Desktop/Others/iKoolCore/iKoolCore R1 iKoolCore R1/AFB94C24C7FD/DEBIAN-11/5.10.0-21-AMD64/X86_64/429D6F994A>) |
| 1022:7906 | 103c:8459 | AMD              | FCH SD Flash Controller              | 8     | sdhci_pci  | [5E71F95F59](<Desktop/Hewlett-Packard/Slim/Slim Desktop 290-a0xxx/73E3B59EA36C/LINUXMINT-21.1/5.15.0-58-GENERIC/X86_64/5E71F95F59>) |
| 197b:2381 | 1297:2020 | JMicron Techn... | Standard SD Host Controller          | 8     | sdhci_pci  | [D8A4F4A923](<Desktop/Standard/AHV/AHV/5D079E63806B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D8A4F4A923>) |
| 8086:5acc | 8086:5acc | Intel            | Celeron N3350/Pentium N4200/Atom ... | 6     | sdhci_pci  | [33A7FAD816](<Desktop/IceWhale Technology/ZimaBoard/ZimaBoard 216 ZMB/70C9EE3DF516/DEBIAN-11/5.15.79+TRUENAS/X86_64/33A7FAD816>) |
| 8086:a375 | 103c:843c | Intel            | 300 Series Chipset Family SD Host... | 6     | sdhci_pci  | [E27595D303](<Desktop/Hewlett-Packard/290/290 G2 MT Business PC/309A43248DEA/ZORIN-16/5.15.0-48-GENERIC/X86_64/E27595D303>) |
| 1022:7813 | 1022:7813 | AMD              | FCH SD Flash Controller              | 5     | sdhci_pci  | [07E2F38566](<Desktop/Others/Others/Others/9E339E78FF10/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/07E2F38566>) |
| 1022:7906 | 103c:8436 | AMD              | FCH SD Flash Controller              | 5     | sdhci_pci  | [01C0C7E212](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop 590-a0xxx/D4D1E53EBEC6/UBUNTU-22.10/5.19.0-29-GENERIC/X86_64/01C0C7E212>) |
| 197b:2381 | 103c:2aa6 | JMicron Techn... | Standard SD Host Controller          | 5     | sdhci_pci  | [965700558A](<Desktop/Hewlett-Packard/200/200-5130ch/53947D0ABDCA/LINUXMINT-20.3/5.4.0-121-GENERIC/X86_64/965700558A>) |
| 8086:a375 | 8086:7270 | Intel            | 300 Series Chipset Family SD Host... | 5     | sdhci_pci  | [59D18B7284](<Desktop/Others/Others/Others/F7C3D93DB6D4/ROSA-12/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/59D18B7284>) |
| 1022:7806 | 103c:2b60 | AMD              | FCH SD Flash Controller              | 4     | sdhci_pci  | [092E063471](<Desktop/Hewlett-Packard/285/285 G2 MT/3F341271CF5F/ZORIN-16/5.15.0-48-GENERIC/X86_64/092E063471>) |
| 1106:401b | 1028:02f5 | VIA Technologies | Secure Digital host Controller       | 4     | sdhci_pci  | [749DC04756](<Desktop/Dell/Vostro/Vostro 320/D38BEB53BFB6/UBUNTU-UNITY-16.04/4.15.0-142-GENERIC/I686/749DC04756>) |
| 197b:2381 | 1297:3189 | JMicron Techn... | Standard SD Host Controller          | 4     | sdhci_pci  | [69B7593670](<Desktop/Standard/X50/X50-V2/099D16230485/ZORIN-15/5.4.0-136-GENERIC/I686/69B7593670>) |
| 197b:2381 | 1297:4012 | JMicron Techn... | Standard SD Host Controller          | 4     | sdhci_pci  | [1F391B4852](<Desktop/Shuttle/XS35/XS35V3/C7E35AB11FE6/ROSA-12.3/5.15.79-GENERIC-1ROSA2021.1-X86_64/X86_64/1F391B4852>) |
| 8086:0f50 |           | Intel            | Atom Processor E3800 Series eMMC ... | 4     | sdhci_pci  | [D4408F7B0E](<Desktop/Intel/DE3815TYKH/DE3815TYKH H26998-403/3CECC7AD024C/DEBIAN-10/4.19.0-14-AMD64/X86_64/D4408F7B0E>) |
| 8086:31cc | 1e39:d024 | Intel            | Celeron/Pentium Silver Processor ... | 4     | sdhci_pci  | [583B49089E](<Desktop/Medion/S/S23003/763FD1B7340F/LMDE-5/5.10.0-22-AMD64/X86_64/583B49089E>) |
| 8086:31d0 | 1e39:d024 | Intel            | Celeron/Pentium Silver SD Host Co... | 4     | sdhci_pci  | [583B49089E](<Desktop/Medion/S/S23003/763FD1B7340F/LMDE-5/5.10.0-22-AMD64/X86_64/583B49089E>) |
| 8086:5aca | 1458:1000 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | sdhci_pci  | [B043125D6E](<Desktop/Gigabyte Technology/GB-BPCE/GB-BPCE-3455/3B80FAD74B9B/OPENMANDRIVA-4.3/5.16.13-DESKTOP-1OMV4003/X86_64/B043125D6E>) |
| 8086:9d2b | 8086:2065 | Intel            | Skylake-U/Y SCC: eMMC                | 4     | sdhci_pci  | [5386CC221B](<Desktop/Intel Client Systems/STK2/STK2M3W64CC/3AC9BE3E0176/DEBIAN-12/6.1.0-6-AMD64/X86_64/5386CC221B>) |
| 8086:9d2d | 8086:2065 | Intel            | Sunrise Point-LP Secure Digital I... | 4     | sdhci_pci  | [5386CC221B](<Desktop/Intel Client Systems/STK2/STK2M3W64CC/3AC9BE3E0176/DEBIAN-12/6.1.0-6-AMD64/X86_64/5386CC221B>) |
| 1106:401b | 1028:0408 | VIA Technologies | Secure Digital host Controller       | 3     | sdhci_pci  | [924B0C6AC0](<Desktop/Dell/Inspiron/Inspiron One 19A/DEFB3954302F/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/924B0C6AC0>) |
| 1180:0822 | 1509:4780 | Ricoh            | R5C822 SD/SDIO/MMC/MS/MSPro Host ... | 3     | sdhci_pci  | [9BB3496465](<Desktop/FIC/GE2/GE2 Series/FE1DFC3AB0F4/UBUNTU-20.04/5.13.0-32-GENERIC/X86_64/9BB3496465>) |
| 1217:8620 | 1217:0002 | O2 Micro         | Integrated MMC/SD Controller         | 3     | sdhci_pci  | [745C41CC7D](<Desktop/Others/Others/Others/54595AE71140/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/745C41CC7D>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a324 | 1043:8694 | Intel            | Cannon Lake PCH SPI Controller       | 608   | intel_s... | [14C71828CA](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-F GAMING/5D29F2B9EBFF/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/14C71828CA>) |
| 8086:a324 | 8086:7270 | Intel            | Cannon Lake PCH SPI Controller       | 516   | intel_s... | [19D78D1685](<Desktop/Gigabyte Technology/Z390/Z390 UD/8E72A411386D/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/19D78D1685>) |
| 8086:43a4 | 1043:8694 | Intel            | Tiger Lake-H SPI Controller          | 338   | spi_int... | [DE65A79BF1](<Desktop/ASUSTek Computer/TUF/TUF Gaming B560M-PLUS/929B4939E2C7/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/DE65A79BF1>) |
| 8086:43e8 | 1043:8694 | Intel            | Tiger Lake-H Serial IO I2C Contro... | 335   | intel_l... | [DE65A79BF1](<Desktop/ASUSTek Computer/TUF/TUF Gaming B560M-PLUS/929B4939E2C7/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/DE65A79BF1>) |
| 8086:43a4 |           | Intel            | Tiger Lake-H SPI Controller          | 274   | intel_s... | [25C4B5FE60](<Desktop/Gigabyte Technology/Z590/Z590 AORUS ELITE AX/B68CA193B4B0/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/25C4B5FE60>) |
| 8086:7aa4 | 1043:8694 | Intel            | Alder Lake-S PCH SPI Controller      | 246   | spi_int... | [401DB07B93](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z690-A GAMING WIFI D4/46556BD3958D/DEBIAN-12/6.1.0-7-AMD64/X86_64/401DB07B93>) |
| 8086:7acc | 1043:8694 | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 246   | intel_l... | [401DB07B93](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z690-A GAMING WIFI D4/46556BD3958D/DEBIAN-12/6.1.0-7-AMD64/X86_64/401DB07B93>) |
| 8086:7acd | 1043:8694 | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 209   | intel_l... | [401DB07B93](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z690-A GAMING WIFI D4/46556BD3958D/DEBIAN-12/6.1.0-7-AMD64/X86_64/401DB07B93>) |
| 8086:7ace | 1043:8694 | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 208   | intel_lpss | [401DB07B93](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z690-A GAMING WIFI D4/46556BD3958D/DEBIAN-12/6.1.0-7-AMD64/X86_64/401DB07B93>) |
| 8086:a324 | 1849:a324 | Intel            | Cannon Lake PCH SPI Controller       | 192   | intel_s... | [AC982522AB](<Desktop/ASRock/B360M/B360M IB-R1/6EDAE1870B25/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/AC982522AB>) |
| 8086:43e9 | 1043:8694 | Intel            | Tiger Lake-H Serial IO I2C Contro... | 153   | intel_l... | [5D12A9965B](<Desktop/ASUSTek Computer/PRIME/PRIME Z590-P WIFI/8ACB5F662D94/ARCO-ROLLING/6.1.27-HARDENED1-2-HARDENED/X86_64/5D12A9965B>) |
| 8086:06a4 | 1043:8694 | Intel            | Comet Lake PCH SPI Controller        | 152   | spi_int... | [1EDDB3203A](<Desktop/ASUSTek Computer/PRIME/PRIME Z490-A/27EB1FCAC7E3/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/1EDDB3203A>) |
| 8086:06e8 | 1043:8694 | Intel            | Comet Lake PCH Serial IO I2C Cont... | 134   | intel_l... | [1EDDB3203A](<Desktop/ASUSTek Computer/PRIME/PRIME Z490-A/27EB1FCAC7E3/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/1EDDB3203A>) |
| 8086:06e9 | 1043:8694 | Intel            | Comet Lake PCH Serial IO I2C Cont... | 134   | intel_l... | [1EDDB3203A](<Desktop/ASUSTek Computer/PRIME/PRIME Z490-A/27EB1FCAC7E3/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/1EDDB3203A>) |
| 8086:7aa4 |           | Intel            | Alder Lake-S PCH SPI Controller      | 128   | spi_int... | [7673380766](<Desktop/Gigabyte Technology/Z690/Z690 AERO G/65E936DD740C/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/7673380766>) |
| 8086:7acc |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 127   | intel_l... | [7673380766](<Desktop/Gigabyte Technology/Z690/Z690 AERO G/65E936DD740C/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/7673380766>) |
| 8086:7acd |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 127   | intel_l... | [7673380766](<Desktop/Gigabyte Technology/Z690/Z690 AERO G/65E936DD740C/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/7673380766>) |
| 8086:7ace |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 127   | intel_l... | [7673380766](<Desktop/Gigabyte Technology/Z690/Z690 AERO G/65E936DD740C/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/7673380766>) |
| 8086:7acf |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 127   | intel_l... | [7673380766](<Desktop/Gigabyte Technology/Z690/Z690 AERO G/65E936DD740C/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/7673380766>) |
| 8086:7afc |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 127   | intel_l... | [7673380766](<Desktop/Gigabyte Technology/Z690/Z690 AERO G/65E936DD740C/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/7673380766>) |
| 8086:7afd |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 127   | intel_l... | [7673380766](<Desktop/Gigabyte Technology/Z690/Z690 AERO G/65E936DD740C/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/7673380766>) |
| 1002:73a4 | 1002:0408 | AMD              | Navi 21 USB                          | 108   | i2c_des... | [D85B7A2592](<Desktop/ASUSTek Computer/ProArt/ProArt X670E-CREATOR WIFI/C425BBBA7D68/DEBIAN-12/6.1.0-8-AMD64/X86_64/D85B7A2592>) |
| 8086:43a4 | 1849:43a4 | Intel            | Tiger Lake-H SPI Controller          | 100   | intel_spi  | [80B16A8567](<Desktop/ASRock/B560/B560M-ITX-ac/43B5A145EA88/FEDORA-37/6.2.14-200.FC37.X86_64/X86_64/80B16A8567>) |
| 8086:06a4 | 8086:7270 | Intel            | Comet Lake PCH SPI Controller        | 99    | intel_s... | [655BBE4068](<Desktop/Gigabyte Technology/H470M/H470M K/8DA375D4ED1A/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/655BBE4068>) |
| 8086:4da4 | 8086:7270 | Intel            | Jasper Lake SPI Controller           | 78    | spi_int... | [D7EE12A01B](<Desktop/AZW/MINI/MINI S/53CF20A09429/ROCKY-9.1/5.14.0-70.26.1.EL9_0.X86_64/X86_64/D7EE12A01B>) |
| 8086:a324 | 1462:7b98 | Intel            | Cannon Lake PCH SPI Controller       | 72    | intel_s... | [0501F3A43B](<Desktop/MSI/MS-7/MS-7B98/EEF8D4397F8E/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/0501F3A43B>) |
| 8086:06a4 | 1849:06a4 | Intel            | Comet Lake PCH SPI Controller        | 68    | intel_s... | [C1F349F579](<Desktop/ASRock/H470/H470M-STX/F6FC8585A545/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/C1F349F579>) |
| 8086:4de8 | 8086:7270 | Intel            | Serial IO I2C Host Controller        | 68    | intel_l... | [D7EE12A01B](<Desktop/AZW/MINI/MINI S/53CF20A09429/ROCKY-9.1/5.14.0-70.26.1.EL9_0.X86_64/X86_64/D7EE12A01B>) |
| 8086:4dea | 8086:7270 | Intel            | Jasper Lake LPSS: I2C Controller #2  | 63    | intel_l... | [D7EE12A01B](<Desktop/AZW/MINI/MINI S/53CF20A09429/ROCKY-9.1/5.14.0-70.26.1.EL9_0.X86_64/X86_64/D7EE12A01B>) |
| 8086:4de9 | 8086:7270 | Intel            | Serial IO I2C Host Controller        | 60    | intel_l... | [D7EE12A01B](<Desktop/AZW/MINI/MINI S/53CF20A09429/ROCKY-9.1/5.14.0-70.26.1.EL9_0.X86_64/X86_64/D7EE12A01B>) |
| 8086:4dab | 8086:7270 | Intel            | Jasper Lake LPSS: SPI Controller #1  | 57    | intel_l... | [D7EE12A01B](<Desktop/AZW/MINI/MINI S/53CF20A09429/ROCKY-9.1/5.14.0-70.26.1.EL9_0.X86_64/X86_64/D7EE12A01B>) |
| 8086:4dc5 | 8086:7270 | Intel            | Jasper Lake LPSS: I2C Controller #4  | 57    | intel_l... | [D7EE12A01B](<Desktop/AZW/MINI/MINI S/53CF20A09429/ROCKY-9.1/5.14.0-70.26.1.EL9_0.X86_64/X86_64/D7EE12A01B>) |
| 8086:4dc6 | 8086:7270 | Intel            | Jasper Lake LPSS: I2C Controller #5  | 57    | intel_l... | [D7EE12A01B](<Desktop/AZW/MINI/MINI S/53CF20A09429/ROCKY-9.1/5.14.0-70.26.1.EL9_0.X86_64/X86_64/D7EE12A01B>) |
| 10de:1aed | 1458:4013 | Nvidia           | TU116 USB Type-C UCSI Controller     | 53    | i2c_nvi... | [D8C1BE05AF](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/FC4BAF1B3D39/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/D8C1BE05AF>) |
| 8086:06a4 | 1462:7c75 | Intel            | Comet Lake PCH SPI Controller        | 52    | intel_spi  | [7603784FCE](<Desktop/MSI/MS-7/MS-7C75/0F6CB069BB25/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/7603784FCE>) |
| 8086:7aa4 | 1462:7d25 | Intel            | Alder Lake-S PCH SPI Controller      | 52    | spi_int... | [C2956FD204](<Desktop/MSI/MS-7/MS-7D25/FFF598BA3748/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/C2956FD204>) |
| 10de:1aed | 1458:3fc8 | Nvidia           | TU116 USB Type-C UCSI Controller     | 51    | i2c_nvi... | [B650F0A26E](<Desktop/MSI/MS-7/MS-7B84/484C99892AE1/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/B650F0A26E>) |
| 10de:1aed | 1462:c75a | Nvidia           | TU116 USB Type-C UCSI Controller     | 48    | i2c_nvi... | [E4C737A64D](<Desktop/ASUSTek Computer/PRIME/PRIME B550M-A/6D9EE28FFBBC/LINUXMINT-21.1/5.15.0-70-GENERIC/X86_64/E4C737A64D>) |
| 8086:a324 | 1025:1238 | Intel            | Cannon Lake PCH SPI Controller       | 46    | intel_s... | [894029CC14](<Desktop/Acer/Aspire/Aspire TC-885/084A5D543ADF/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/894029CC14>) |
| 8086:a324 | 1462:7b17 | Intel            | Cannon Lake PCH SPI Controller       | 45    | spi_int... | [586E9D4FEC](<Desktop/MSI/MS-7/MS-7B17/D633DBE98B18/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/586E9D4FEC>) |
| 10de:1adb | 1458:3fc1 | Nvidia           | TU106 USB Type-C UCSI Controller     | 44    | i2c_nvi... | [0501F3A43B](<Desktop/MSI/MS-7/MS-7B98/EEF8D4397F8E/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/0501F3A43B>) |
| 8086:4deb | 8086:7270 | Intel            | Jasper Lake LPSS: I2C Controller #3  | 43    | intel_lpss | [D7EE12A01B](<Desktop/AZW/MINI/MINI S/53CF20A09429/ROCKY-9.1/5.14.0-70.26.1.EL9_0.X86_64/X86_64/D7EE12A01B>) |
| 10de:1ad9 | 1458:4001 | Nvidia           | TU104 USB Type-C UCSI Controller     | 41    | i2c_nvi... | [CDCED725A6](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-P/A2C4DE3BDEEF/UBUNTU-22.10/5.19.0-31-GENERIC/X86_64/CDCED725A6>) |
| 10de:1adb | 1462:3755 | Nvidia           | TU106 USB Type-C UCSI Controller     | 40    | i2c_nvi... | [60F7987AF4](<Desktop/ASUSTek Computer/TUF/TUF B450-PLUS GAMING/420F60296E16/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/60F7987AF4>) |
| 8086:7aa4 | 1849:7aa4 | Intel            | Alder Lake-S PCH SPI Controller      | 40    | spi_int... | [1F232288D7](<Desktop/ASRock/Z690/Z690M-ITX-ax/FA892D909FAE/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/1F232288D7>) |
| 8086:7acc | 1849:7acc | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 40    | intel_l... | [1F232288D7](<Desktop/ASRock/Z690/Z690M-ITX-ax/FA892D909FAE/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/1F232288D7>) |
| 8086:43a4 | 1462:7d22 | Intel            | Tiger Lake-H SPI Controller          | 38    | intel_s... | [F580FDA8F1](<Desktop/MSI/MS-7/MS-7D22/5B0080DADBEC/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/F580FDA8F1>) |
| 10de:1aed | 1462:3792 | Nvidia           | TU116 USB Type-C UCSI Controller     | 37    | i2c_nvi... | [20267BE489](<Desktop/MSI/MS-7/MS-7C37/D425B43D51A1/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/20267BE489>) |
| 8086:a324 | 1028:085c | Intel            | Cannon Lake PCH SPI Controller       | 37    | intel_spi  | [1945CCD76D](<Desktop/Dell/OptiPlex/OptiPlex 3060/0AA7CB57BEDA/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/1945CCD76D>) |
| 8086:43a4 | 1462:7d09 | Intel            | Tiger Lake-H SPI Controller          | 36    | intel_spi  | [AD6A144DB9](<Desktop/MSI/MS-7/MS-7D09/AC92341239B6/MAGEIA-8/5.15.98-DESKTOP-1.MGA8/X86_64/AD6A144DB9>) |

### Serial controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:8c3d | 1458:1c3a | Intel            | 8 Series/C220 Series Chipset Fami... | 231   | serial     | [7D861ACBD6](<Desktop/Gigabyte Technology/Q87/Q87M-D2H/DEF7B8B0BDF0/LMDE-5/5.10.0-22-AMD64/X86_64/7D861ACBD6>) |
| 8086:8c3d | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 196   | serial     | [5BC5CCDCAD](<Desktop/Dell/OptiPlex/OptiPlex 9020/E9FD17DAA8B2/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/5BC5CCDCAD>) |
| 8086:1e3d | 1028:0577 | Intel            | 7 Series/C210 Series Chipset Fami... | 179   | serial     | [B8281F77A3](<Desktop/Dell/OptiPlex/OptiPlex 7010/F3C38BD709A2/BLENDOS/6.3.1-ARCH1-1/X86_64/B8281F77A3>) |
| 8086:1e3d | 103c:3397 | Intel            | 7 Series/C210 Series Chipset Fami... | 176   | serial     | [8B84766D3D](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/EAE7702EADF9/DEBIAN-11/6.1.15-1-PVE/X86_64/8B84766D3D>) |
| 8086:29b7 | 1028:0211 | Intel            | 82Q35 Express Serial KT Controller   | 154   | serial     | [03C6B8486E](<Desktop/Dell/OptiPlex/OptiPlex 755/F8A80185DE25/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/03C6B8486E>) |
| 8086:2e17 | 1028:0420 | Intel            | 4 Series Chipset Serial KT Contro... | 148   | serial     | [B585380BC4](<Desktop/Dell/OptiPlex/OptiPlex 780/8DA70E0A4BDE/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/B585380BC4>) |
| 8086:1e3d | 103c:339a | Intel            | 7 Series/C210 Series Chipset Fami... | 145   | serial     | [8B646A0FA1](<Desktop/Hewlett-Packard/Compaq/Compaq Pro 6300 MT/C7D9D31D8078/ZORIN-16/5.15.0-71-GENERIC/X86_64/8B646A0FA1>) |
| 8086:8c3d | 103c:1998 | Intel            | 8 Series/C220 Series Chipset Fami... | 141   | serial     | [2ED500D3E9](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/4A54E9E0D620/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/2ED500D3E9>) |
| 8086:8c3d | 103c:18e7 | Intel            | 8 Series/C220 Series Chipset Fami... | 132   | serial     | [C6A760CB50](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 SFF/E9FD6C026940/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/C6A760CB50>) |
| 8086:1c3d | 1028:04ad | Intel            | 6 Series/C200 Series Chipset Fami... | 125   | serial     | [2EC196DD79](<Desktop/Dell/OptiPlex/OptiPlex 790/F9C720B92D19/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/2EC196DD79>) |
| 8086:1c3d | 103c:1495 | Intel            | 6 Series/C200 Series Chipset Fami... | 124   | serial     | [D6E629523F](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite SFF PC/236BDABDB798/UBUNTUSTUDIO-22.04/5.15.0-71-LOWLATENCY/X86_64/D6E629523F>) |
| 8086:1c3d | 1028:047e | Intel            | 6 Series/C200 Series Chipset Fami... | 123   | serial     | [EC04C034D3](<Desktop/Dell/OptiPlex/OptiPlex 990/D0B1671560CE/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/EC04C034D3>) |
| 8086:2e17 | 1028:027f | Intel            | 4 Series Chipset Serial KT Contro... | 110   | serial     | [16611A8ED6](<Desktop/Dell/OptiPlex/OptiPlex 760/7440761DE40F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/16611A8ED6>) |
| 8086:1c3d | 103c:1497 | Intel            | 6 Series/C200 Series Chipset Fami... | 103   | serial     | [3E285F4AE4](<Desktop/Hewlett-Packard/Compaq/Compaq 6200 Pro MT PC/DDB8E3F48862/UBUNTU-22.10/5.19.0-1024-LOWLATENCY/X86_64/3E285F4AE4>) |
| 8086:2e17 | 103c:3048 | Intel            | 4 Series Chipset Serial KT Contro... | 94    | serial     | [C771C0B0A7](<Desktop/Hewlett-Packard/Compaq/Compaq 6000 Pro SFF PC/78D2ECED4802/LINUXMINT-18.3/4.10.0-38-GENERIC/X86_64/C771C0B0A7>) |
| 8086:3b67 | 8086:0036 | Intel            | 5 Series/3400 Series Chipset KT C... | 82    | serial     | [1CA0E70D0E](<Desktop/Equus Computer Systems/Nobilis/Nobilis/CBE725B8CBF2/LINUXMINT-21.1/5.15.0-67-GENERIC/X86_64/1CA0E70D0E>) |
| 8086:2e17 | 1734:114c | Intel            | 4 Series Chipset Serial KT Contro... | 80    | serial     | [4278EFC4CA](<Desktop/Fujitsu Siemens/ESPRIMO/ESPRIMO C5730/8C051342A6B5/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/4278EFC4CA>) |
| 8086:1e3d | 1028:052c | Intel            | 7 Series/C210 Series Chipset Fami... | 73    | serial     | [F2B702B631](<Desktop/Dell/OptiPlex/OptiPlex 9010/E884F88EE11B/LINUXMINT-18/4.4.0-140-GENERIC/X86_64/F2B702B631>) |
| 8086:8c3d | 17aa:3097 | Intel            | 8 Series/C220 Series Chipset Fami... | 71    | serial     | [E694779B17](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10A6A0BBFR/F200014F7E05/FEDORA-38/6.2.12-300.FC38.X86_64/X86_64/E694779B17>) |
| 8086:8c3d | 17aa:30a3 | Intel            | 8 Series/C220 Series Chipset Fami... | 69    | serial     | [F4E56E51D7](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93 10A50002GE/7723232D19D0/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/F4E56E51D7>) |
| 8086:1d3d | 103c:1589 | Intel            | C600/X79 series chipset KT Contro... | 67    | serial     | [BE15D33D32](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/EE9F1FE423DF/DEBIAN-12/6.1.0-8-AMD64/X86_64/BE15D33D32>) |
| 8086:1e3d | 17aa:3083 | Intel            | 7 Series/C210 Series Chipset Fami... | 67    | serial     | [7AC436D763](<Desktop/Lenovo/ThinkCentre/ThinkCentre M92P 3227BD2/791575E45E29/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/7AC436D763>) |
| 8086:29b7 | 103c:2818 | Intel            | 82Q35 Express Serial KT Controller   | 66    | serial     | [B927834A03](<Desktop/Hewlett-Packard/Compaq/Compaq dc7800 Small Form Factor/A3D50758DB46/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B927834A03>) |
| 8086:2e17 | 17aa:3048 | Intel            | 4 Series Chipset Serial KT Contro... | 65    | serial     | [2BE395131F](<Desktop/Lenovo/ThinkCentre/ThinkCentre M58p 7220A72/79C1B7350DAA/FEDORA-37/6.2.9-200.FC37.X86_64/X86_64/2BE395131F>) |
| 8086:8c3d | 1028:05a5 | Intel            | 8 Series/C220 Series Chipset Fami... | 64    | serial     | [6EA350C49D](<Desktop/Dell/OptiPlex/OptiPlex 7020/60BD17C27531/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6EA350C49D>) |
| 8086:a13d | 1028:06b9 | Intel            | 100 Series/C230 Series Chipset Fa... | 60    | serial     | [08DF3C35EE](<Desktop/Dell/OptiPlex/OptiPlex 7040/74B9A8608B3A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/08DF3C35EE>) |
| 8086:2e17 | 103c:3034 | Intel            | 4 Series Chipset Serial KT Contro... | 58    | serial     | [DC7B257F83](<Desktop/Hewlett-Packard/Compaq/Compaq dc7900 Small Form Factor/56CDA0F2FEEF/DEBIAN-11/5.10.0-22-AMD64/X86_64/DC7B257F83>) |
| 8086:1e3d | 103c:3396 | Intel            | 7 Series/C210 Series Chipset Fami... | 57    | serial     | [25EAC72561](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 CMT/3A9DF5F55034/UBUNTU-UNITY-22.04/5.19.0-38-GENERIC/X86_64/25EAC72561>) |
| 8086:1c3d | 17aa:3070 | Intel            | 6 Series/C200 Series Chipset Fami... | 56    | serial     | [EAD0ECFB3A](<Desktop/Lenovo/ThinkCentre/ThinkCentre M91p 4518RH1/E30F2C4B8797/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/EAD0ECFB3A>) |
| 8086:1c3d | 103c:1494 | Intel            | 6 Series/C200 Series Chipset Fami... | 54    | serial     | [625373A1DE](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite CMT PC/76F58926807D/UBUNTU-22.04/5.15.0-70-GENERIC/X86_64/625373A1DE>) |
| 8086:3b67 | 103c:304a | Intel            | 5 Series/3400 Series Chipset KT C... | 51    | serial     | [D9A160845C](<Desktop/Hewlett-Packard/Compaq/Compaq 8100 Elite SFF PC/53E507FC9A2B/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.3.1-1-DEFAULT/X86_64/D9A160845C>) |
| 8086:8d3d | 103c:212b | Intel            | C610/X99 series chipset KT Contro... | 49    | serial     | [343F1F5EBA](<Desktop/Hewlett-Packard/Z440/Z440 Workstation/64A1F327266A/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/343F1F5EBA>) |
| 8086:2e17 | 103c:3646 | Intel            | 4 Series Chipset Serial KT Contro... | 48    | serial     | [C36653D824](<Desktop/Hewlett-Packard/3646/3646h/AA660EC218E2/MX-21/5.10.0-21-AMD64/X86_64/C36653D824>) |
| 8086:8c3d | 17aa:309f | Intel            | 8 Series/C220 Series Chipset Fami... | 47    | serial     | [7A1FFD8BD2](<Desktop/Lenovo/ThinkCentre/ThinkCentre M83 10AHS0W300/4DD5319CB14B/ENDEAVOUROS-ROLLING/6.3.1-ARCH1-1/X86_64/7A1FFD8BD2>) |
| 8086:a2bd | 1028:07a1 | Intel            | 200 Series Chipset Family KT Redi... | 47    | serial     | [D2F5E578EE](<Desktop/Dell/OptiPlex/OptiPlex 7050/E65A755FB4E6/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/D2F5E578EE>) |
| 8086:8c3d | 103c:18e4 | Intel            | 8 Series/C220 Series Chipset Fami... | 42    | serial     | [D1344E36DD](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 TWR/AE205CE4F972/ENDEAVOUROS-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/D1344E36DD>) |
| 8086:8c3d | 103c:1905 | Intel            | 8 Series/C220 Series Chipset Fami... | 41    | serial     | [7B15EC2D7D](<Desktop/Hewlett-Packard/Z230/Z230 Tower Workstation/3B22E13D6BA1/UBUNTU-23.04/5.19.0-42-GENERIC/X86_64/7B15EC2D7D>) |
| 8086:1d3d | 103c:158a | Intel            | C600/X79 series chipset KT Contro... | 40    | serial     | [FB7AEF7883](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/9F156C69101A/XUBUNTU-20.04/5.15.0-71-LOWLATENCY/X86_64/FB7AEF7883>) |
| 8086:1e3d | 17aa:3084 | Intel            | 7 Series/C210 Series Chipset Fami... | 39    | serial     | [97CC4E0A84](<Desktop/Lenovo/ThinkCentre/ThinkCentre M82 3392C4S/30D510CE75D9/UBUNTU-20.04/5.15.0-69-GENERIC/X86_64/97CC4E0A84>) |
| 9710:9865 | a000:1000 | MosChip Semic... | PCI 9865 Multi-I/O Controller        | 39    | parport_pc | [E64A3C2DA5](<Desktop/ASUSTek Computer/P5/P5N73-CM/CC5555A4549D/ZORIN-15/5.4.0-47-GENERIC/X86_64/E64A3C2DA5>) |
| 8086:1e3d | 103c:3398 | Intel            | 7 Series/C210 Series Chipset Fami... | 38    | serial     | [ED9F84A231](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 USDT/BC65BBEE89FA/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/ED9F84A231>) |
| 8086:3b67 | 1028:02da | Intel            | 5 Series/3400 Series Chipset KT C... | 38    | serial     | [1563E26AE3](<Desktop/Dell/OptiPlex/OptiPlex 980/D45EAD5377A1/LINUXMINT-21.1/5.15.0-67-GENERIC/X86_64/1563E26AE3>) |
| 8086:a13d | 103c:805d | Intel            | 100 Series/C230 Series Chipset Fa... | 38    | serial     | [091E90CAE0](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G2 SFF/B5C4FE941F6E/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/091E90CAE0>) |
| 8086:2e17 | 1028:0276 | Intel            | 4 Series Chipset Serial KT Contro... | 37    | serial     | [F63F67F28F](<Desktop/Dell/OptiPlex/OptiPlex 960/5CAA26888260/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/F63F67F28F>) |
| 8086:2e17 | 103c:3035 | Intel            | 4 Series Chipset Serial KT Contro... | 37    | serial     | [824604840A](<Desktop/Hewlett-Packard/Compaq/Compaq dc7900 Convertible Minitower/497BB85D72B3/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/824604840A>) |
| 8086:a13d | 1734:121d | Intel            | 100 Series/C230 Series Chipset Fa... | 37    | serial     | [FBEDBCB213](<Desktop/Fujitsu/CELSIUS/CELSIUS W570/872C5F0E2916/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/FBEDBCB213>) |
| 10ec:816a | 10ec:8168 | Realtek Semic... | RTL8111xP UART #1                    | 36    | serial     | [895855ED9A](<Desktop/ASUSTek Computer/Pro/Pro WS X570-ACE/7D768ECED733/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/895855ED9A>) |
| 8086:8c3d | 103c:18e5 | Intel            | 8 Series/C220 Series Chipset Fami... | 35    | serial     | [0437B3DEB1](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 USDT/69A6781598B0/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/0437B3DEB1>) |
| 8086:a13d | 103c:8054 | Intel            | 100 Series/C230 Series Chipset Fa... | 35    | serial     | [81A57B4A2F](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G2 SFF/77D8C4611D60/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/81A57B4A2F>) |
| 8086:1e3d | 17aa:3086 | Intel            | 7 Series/C210 Series Chipset Fami... | 34    | serial     | [3BF5FD0CFD](<Desktop/Lenovo/ThinkCentre/ThinkCentre M92P 32371D5/0F1450D88DCD/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/3BF5FD0CFD>) |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a379 | 1458:8888 | Intel            | Cannon Lake PCH Thermal Controller   | 490   | intel_p... | [19D78D1685](<Desktop/Gigabyte Technology/Z390/Z390 UD/8E72A411386D/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/19D78D1685>) |
| 8086:a2b1 | 1849:a2b1 | Intel            | 200 Series PCH Thermal Subsystem     | 293   |            | [D905BABC43](<Desktop/ASRock/B250/B250M-HDV/A65B4BC89A4A/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/D905BABC43>) |
| 8086:a131 | 1849:a131 | Intel            | 100 Series/C230 Series Chipset Fa... | 292   | intel_p... | [A38BF561F7](<Desktop/ASRock/Z170/Z170 Gaming K4/19138DC977DF/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/A38BF561F7>) |
| 8086:467d |           | Intel            | Platform Monitoring Technology       | 254   | intel_pmt  | [13E08DA76D](<Desktop/MSI/MS-7/MS-7D43/5645B8FC5581/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/13E08DA76D>) |
| 8086:467d | 1043:8694 | Intel            | Platform Monitoring Technology       | 237   | intel_vsec | [401DB07B93](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z690-A GAMING WIFI D4/46556BD3958D/DEBIAN-12/6.1.0-7-AMD64/X86_64/401DB07B93>) |
| 8086:a3b1 | 8086:7270 | Intel            | Comet Lake PCH-V Thermal Subsystem   | 200   |            | [6116C0DF52](<Desktop/Gigabyte Technology/H410M/H410M H/370152E34E95/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/6116C0DF52>) |
| 8086:a379 | 1849:a379 | Intel            | Cannon Lake PCH Thermal Controller   | 192   | intel_p... | [AC982522AB](<Desktop/ASRock/B360M/B360M IB-R1/6EDAE1870B25/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/AC982522AB>) |
| 8086:a131 | 1458:8888 | Intel            | 100 Series/C230 Series Chipset Fa... | 188   | intel_p... | [8C5B603452](<Desktop/Gigabyte Technology/Z170X-Gaming/Z170X-Gaming 7/F95579DE4AF1/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/8C5B603452>) |
| 8086:8c24 | 1734:11ea | Intel            | 8 Series Chipset Family Thermal M... | 135   | intel_p... | [9B6F7CEA89](<Desktop/Fujitsu/ESPRIMO/ESPRIMO Q520/707B73345F8F/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/9B6F7CEA89>) |
| 8086:a2b1 | 1043:873c | Intel            | 200 Series PCH Thermal Subsystem     | 131   |            | [1C9E5EE2A6](<Desktop/ASUSTek Computer/WS/WS X299 SAGE/7F377E5958FC/LINUXMINT-20.3/5.19.0-17.2-LIQUORIX-AMD64/X86_64/1C9E5EE2A6>) |
| 8086:a131 | 1462:7996 | Intel            | 100 Series/C230 Series Chipset Fa... | 130   | intel_p... | [D63BC9AECA](<Desktop/MSI/MS/MS-7996/30F694CCEC2B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D63BC9AECA>) |
| 8086:06f9 | 1458:8888 | Intel            | Comet Lake PCH Thermal Controller    | 95    | intel_p... | [655BBE4068](<Desktop/Gigabyte Technology/H470M/H470M K/8DA375D4ED1A/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/655BBE4068>) |
| 8086:a131 | 1734:121d | Intel            | 100 Series/C230 Series Chipset Fa... | 94    | intel_p... | [77150D1166](<Desktop/Fujitsu/ESPRIMO/ESPRIMO P557/9D728F491894/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/77150D1166>) |
| 8086:1e24 | 1734:11d6 | Intel            | 7 Series/C210 Series Chipset Fami... | 90    |            | [78BB45767D](<Desktop/Fujitsu/ESPRIMO/ESPRIMO P910/099BA1BA05B3/BLACKPANTHER-OS-18.1/5.15.85-DESKTOP-1BP/X86_64/78BB45767D>) |
| 8086:a131 | 1028:06b9 | Intel            | 100 Series/C230 Series Chipset Fa... | 90    | intel_p... | [08DF3C35EE](<Desktop/Dell/OptiPlex/OptiPlex 7040/74B9A8608B3A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/08DF3C35EE>) |
| 8086:a131 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 86    | intel_p... | [68E1C1B5A4](<Desktop/Others/Others/Others/0401B4CF51F2/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/68E1C1B5A4>) |
| 8086:31b4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 78    | intel_l... | [22D1FBDEEE](<Desktop/Others/Others/Others/7E2DCAD143A6/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/22D1FBDEEE>) |
| 1022:15e4 | 1022:15e4 | AMD              | Sensor Fusion Hub                    | 76    | amd_sfh    | [8454DAED68](<Desktop/Others/HX/HX90/1FE0593076B3/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/8454DAED68>) |
| 8086:22dc | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 75    | process... | [58DEA5F209](<Desktop/CSL-Computer/Narrow/Narrow Box 4K 4GB/4D92FAFC10A2/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/58DEA5F209>) |
| 8086:a2b1 | 1028:07a1 | Intel            | 200 Series PCH Thermal Subsystem     | 74    |            | [11E8FB1ECD](<Desktop/Dell/OptiPlex/OptiPlex 7050/460F8DE765A3/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/11E8FB1ECD>) |
| 8086:a2e0 | 1028:07a1 | Intel            | 200 Series PCH Serial IO I2C Cont... | 74    | intel_l... | [11E8FB1ECD](<Desktop/Dell/OptiPlex/OptiPlex 7050/460F8DE765A3/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/11E8FB1ECD>) |
| 8086:a379 | 1462:7b98 | Intel            | Cannon Lake PCH Thermal Controller   | 72    | intel_p... | [0501F3A43B](<Desktop/MSI/MS-7/MS-7B98/EEF8D4397F8E/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/0501F3A43B>) |
| 8086:31b6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 71    | intel_l... | [22D1FBDEEE](<Desktop/Others/Others/Others/7E2DCAD143A6/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/22D1FBDEEE>) |
| 8086:4e03 | 8086:7270 | Intel            | Dynamic Tuning service               | 71    | process... | [D7EE12A01B](<Desktop/AZW/MINI/MINI S/53CF20A09429/ROCKY-9.1/5.14.0-70.26.1.EL9_0.X86_64/X86_64/D7EE12A01B>) |
| 8086:a131 | 1462:7971 | Intel            | 100 Series/C230 Series Chipset Fa... | 71    | intel_p... | [DA2D2D3D5C](<Desktop/MSI/MS/MS-7971/14F264169A02/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/DA2D2D3D5C>) |
| 8086:a131 | 1462:7a15 | Intel            | 100 Series/C230 Series Chipset Fa... | 71    | intel_p... | [AF27E2497A](<Desktop/MSI/MS-7/MS-7A15/C35BC5B871B3/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/AF27E2497A>) |
| 8086:a2b1 | 1028:07a3 | Intel            | 200 Series PCH Thermal Subsystem     | 70    |            | [974CB924D5](<Desktop/Dell/OptiPlex/OptiPlex 3050/0A14953B346E/SIDUCTION-12/6.2.13-1-SIDUCTION-AMD64/X86_64/974CB924D5>) |
| 8086:31b8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 69    | intel_l... | [22D1FBDEEE](<Desktop/Others/Others/Others/7E2DCAD143A6/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/22D1FBDEEE>) |
| 8086:06f9 | 1849:06f9 | Intel            | Comet Lake PCH Thermal Controller    | 68    | intel_p... | [C1F349F579](<Desktop/ASRock/H470/H470M-STX/F6FC8585A545/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/C1F349F579>) |
| 8086:31bc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 67    | intel_l... | [22D1FBDEEE](<Desktop/Others/Others/Others/7E2DCAD143A6/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/22D1FBDEEE>) |
| 8086:31be | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 67    | intel_l... | [22D1FBDEEE](<Desktop/Others/Others/Others/7E2DCAD143A6/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/22D1FBDEEE>) |
| 8086:31c0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 67    | intel_l... | [22D1FBDEEE](<Desktop/Others/Others/Others/7E2DCAD143A6/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/22D1FBDEEE>) |
| 8086:31ee | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 67    | intel_l... | [22D1FBDEEE](<Desktop/Others/Others/Others/7E2DCAD143A6/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/22D1FBDEEE>) |
| 8086:318c | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 65    | process... | [62D06B215E](<Desktop/AMI/Intel/Intel/B18EF87BD20B/REGATAOS-23/6.2.10-LP154.5-DEFAULT/X86_64/62D06B215E>) |
| 8086:9d31 | 8086:7270 | Intel            | Sunrise Point-LP Thermal subsystem   | 60    | intel_p... | [18DCBA612C](<Desktop/Others/Others/Others/9654B0B310BA/DEBIAN-11/5.10.0-22-AMD64/X86_64/18DCBA612C>) |
| 8086:a160 | 1462:7996 | Intel            | 100 Series/C230 Series Chipset Fa... | 60    | intel_l... | [D63BC9AECA](<Desktop/MSI/MS/MS-7996/30F694CCEC2B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D63BC9AECA>) |
| 8086:a161 | 1462:7996 | Intel            | 100 Series/C230 Series Chipset Fa... | 60    | intel_l... | [D63BC9AECA](<Desktop/MSI/MS/MS-7996/30F694CCEC2B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D63BC9AECA>) |
| 8086:31ba | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 57    | intel_l... | [22D1FBDEEE](<Desktop/Others/Others/Others/7E2DCAD143A6/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/22D1FBDEEE>) |
| 8086:a3b1 | 1849:a3b1 | Intel            | Comet Lake PCH-V Thermal Subsystem   | 55    |            | [7F388965D7](<Desktop/MATERIEL.NET/CUSTOM/CUSTOM/1365F60F2877/DEBIAN-11/5.10.0-21-AMD64/X86_64/7F388965D7>) |
| 8086:318c | 1849:318c | Intel            | Celeron/Pentium Silver Processor ... | 54    | process... | [A702DF382B](<Desktop/ASRock/J4125/J4125M/BD0FBF639942/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/A702DF382B>) |
| 8086:a127 | 1462:7996 | Intel            | 100 Series/C230 Series Chipset Fa... | 54    | intel_l... | [D63BC9AECA](<Desktop/MSI/MS/MS-7996/30F694CCEC2B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D63BC9AECA>) |
| 8086:06f9 | 1462:7c75 | Intel            | Comet Lake PCH Thermal Controller    | 52    | intel_p... | [7603784FCE](<Desktop/MSI/MS-7/MS-7C75/0F6CB069BB25/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/7603784FCE>) |
| 8086:8c24 | 1025:0750 | Intel            | 8 Series Chipset Family Thermal M... | 50    | intel_p... | [B9DCC7F752](<Desktop/Acer/Aspire/Aspire TC-605/3460E220333A/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/B9DCC7F752>) |
| 8086:a2b1 | 1462:7a70 | Intel            | 200 Series PCH Thermal Subsystem     | 49    |            | [123883B7DD](<Desktop/MSI/MS-7/MS-7A70/0F6885F5F653/ARCH-ROLLING/6.2.9-ARCH1-1/X86_64/123883B7DD>) |
| 8086:a131 | 1028:06bb | Intel            | 100 Series/C230 Series Chipset Fa... | 46    | intel_p... | [ED13B58A51](<Desktop/Dell/OptiPlex/OptiPlex 3040/3D992B11D5FE/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/ED13B58A51>) |
| 8086:a379 | 1025:1238 | Intel            | Cannon Lake PCH Thermal Controller   | 46    | intel_p... | [894029CC14](<Desktop/Acer/Aspire/Aspire TC-885/084A5D543ADF/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/894029CC14>) |
| 8086:a379 | 1462:7b17 | Intel            | Cannon Lake PCH Thermal Controller   | 45    | intel_p... | [586E9D4FEC](<Desktop/MSI/MS-7/MS-7B17/D633DBE98B18/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/586E9D4FEC>) |
| 8086:a131 | 103c:805d | Intel            | 100 Series/C230 Series Chipset Fa... | 43    | intel_p... | [091E90CAE0](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G2 SFF/B5C4FE941F6E/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/091E90CAE0>) |
| 8086:31ac | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 42    | intel_l... | [22D1FBDEEE](<Desktop/Others/Others/Others/7E2DCAD143A6/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/22D1FBDEEE>) |
| 8086:a2a7 | 103c:82f2 | Intel            | 200 Series/Z370 Chipset Family Se... | 41    | intel_l... | [EA8F7364DB](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop PC 570-p5xx/1EEFF6255E0E/ARCH-ROLLING/6.1.25-1-LTS/X86_64/EA8F7364DB>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:790b | 1458:5001 | AMD              | FCH SMBus Controller                 | 3224  | i2c_piix4  | [E6EAD6E953](<Desktop/Gigabyte Technology/B450/B450 AORUS ELITE/9C8C09595939/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/E6EAD6E953>) |
| 1022:790b | 1043:87c0 | AMD              | FCH SMBus Controller                 | 2065  | piix4_s... | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 1002:4385 | 1002:4385 | AMD              | SBx00 SMBus Controller               | 1678  | i2c_pii... | [ACF61A6132](<Desktop/Gigabyte Technology/970/970A-DS3P/4209CEC662D2/OPENMANDRIVA-23.03/6.2.10-DESKTOP-2.0OMV4.9MJN/X86_64/ACF61A6132>) |
| 8086:1c22 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 1534  | i2c_i801   | [386D7C9DE4](<Desktop/ASUSTek Computer/P8/P8P67-M/D3654512534B/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/386D7C9DE4>) |
| 8086:8c22 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 1290  | i2c_i801   | [E146C82A49](<Desktop/ASUSTek Computer/All/All Series/D75C393B8A2E/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/E146C82A49>) |
| 1022:790b | 1043:8747 | AMD              | FCH SMBus Controller                 | 1256  | i2c_piix4  | [D9A3AFA732](<Desktop/ASUSTek Computer/ROG/ROG STRIX X470-I GAMING/133421F6DBD4/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/D9A3AFA732>) |
| 1002:4385 | 1043:8389 | AMD              | SBx00 SMBus Controller               | 1124  | i2c_pii... | [E3DC27EEE1](<Desktop/ASUSTek Computer/M5A78L/M5A78L LE/E8B8C04727FE/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/E3DC27EEE1>) |
| 8086:a123 | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 1112  | i2c_i801   | [BBFD29FB88](<Desktop/ASUSTek Computer/D320/D320SF/A7E6ADB389B1/UBUNTU-20.04/5.4.0-148-GENERIC/X86_64/BBFD29FB88>) |
| 1022:790b | 1849:ffff | AMD              | FCH SMBus Controller                 | 1075  | i2c_piix4  | [53D91DCA3C](<Desktop/ASRock/B450M/B450M Steel Legend/57EFD5B4322B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/53D91DCA3C>) |
| 8086:1e22 | 1043:84ca | Intel            | 7 Series/C216 Chipset Family SMBu... | 1065  | i2c_i801   | [92B5951471](<Desktop/ASUSTek Computer/Z77/Z77-A/7F8B426D3C22/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/92B5951471>) |
| 1002:4385 | 1458:4385 | AMD              | SBx00 SMBus Controller               | 1059  | i2c_pii... | [631317F909](<Desktop/Gigabyte Technology/GA-78/GA-78LMT-S2/A7640481CED2/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/631317F909>) |
| 1022:790b | 1849:790b | AMD              | FCH SMBus Controller                 | 1023  | i2c_piix4  | [28A1F44A1E](<Desktop/ASRockRack/X470/X470D4U2-2T/EEF286979D7B/ALMA-8.7/4.18.0-425.19.2.EL8_7.X86_64/X86_64/28A1F44A1E>) |
| 8086:27da | 1458:5001 | Intel            | NM10/ICH7 Family SMBus Controller    | 984   | i2c_i801   | [0458D9F44B](<Desktop/Gigabyte Technology/G41/G41MT-S2/EF1568975525/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/0458D9F44B>) |
| 8086:1c22 | 1458:5001 | Intel            | 6 Series/C200 Series Chipset Fami... | 934   | i2c_i801   | [E7B77F5CF0](<Desktop/Gigabyte Technology/Z68/Z68MA-D2H-B3/99DA8E367A7A/OPENMANDRIVA-23.03/5.16.13-DESKTOP-1OMV4003/X86_64/E7B77F5CF0>) |
| 8086:8c22 | 1458:5001 | Intel            | 8 Series/C220 Series Chipset Fami... | 876   | i2c_i801   | [22BD54D6D1](<Desktop/Gigabyte Technology/Z87/Z87X-UD3H/F9D737247AAE/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/22BD54D6D1>) |
| 8086:27da | 1043:8179 | Intel            | NM10/ICH7 Family SMBus Controller    | 870   | i2c_i801   | [A5C1634444](<Desktop/ASUSTek Computer/P5/P5KPL-AM-PS/229B6B131E2A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/A5C1634444>) |
| 8086:3a30 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 845   | i2c_i801   | [C2A0653C52](<Desktop/ASUSTek Computer/P5QLD/P5QLD PRO/0678AB1FB908/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/C2A0653C52>) |
| 1002:4385 |           | AMD              | SBx00 SMBus Controller               | 829   | i2c_piix4  | [8E4CBC4837](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer/5EE6E0F2768B/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/8E4CBC4837>) |
| 8086:1e22 | 1458:5001 | Intel            | 7 Series/C216 Chipset Family SMBu... | 812   | i2c_i801   | [A72531BD2D](<Desktop/MouseComputer/B75/B75M-D3V-JP/041627593BC4/LINUXMINT-18.3/4.8.0-58-GENERIC/X86_64/A72531BD2D>) |
| 8086:a2a3 | 1043:8694 | Intel            | 200 Series/Z370 Chipset Family SM... | 776   | i2c_i801   | [536E6E7CC9](<Desktop/ASUSTek Computer/STRIX/STRIX B250I GAMING/BB9A16765525/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/536E6E7CC9>) |
| 1002:4385 | 1849:4385 | AMD              | SBx00 SMBus Controller               | 713   | i2c_pii... | [A68D009BD1](<Desktop/ASRock/970M/970M Pro3/6BAC82210FE1/UBUNTU-20.04/5.15.0-72-GENERIC/X86_64/A68D009BD1>) |
| 8086:a2a3 | 1458:5001 | Intel            | 200 Series/Z370 Chipset Family SM... | 689   | i2c_i801   | [E44F7DFAC5](<Desktop/Punch Technology/PDT-702/PDT-702-1020/29C76CB9E8B7/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/E44F7DFAC5>) |
| 1022:790b | 1022:790b | AMD              | FCH SMBus Controller                 | 660   | i2c_piix4  | [19C318242F](<Desktop/Others/Others/Others/C3C1AB1B873D/UBUNTU-20.04/5.15.0-1023-NVIDIA/X86_64/19C318242F>) |
| 8086:a123 | 1458:5001 | Intel            | 100 Series/C230 Series Chipset Fa... | 628   | i2c_i801   | [8C5B603452](<Desktop/Gigabyte Technology/Z170X-Gaming/Z170X-Gaming 7/F95579DE4AF1/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/8C5B603452>) |
| 8086:a323 | 1043:8694 | Intel            | Cannon Lake PCH SMBus Controller     | 608   | i2c_i801   | [14C71828CA](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-F GAMING/5D29F2B9EBFF/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/14C71828CA>) |
| 1022:780b | 1022:780b | AMD              | FCH SMBus Controller                 | 571   | i2c_piix4  | [97986B63AD](<Desktop/Gigabyte Technology/F2/F2A68HM-H/458432F727D5/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/97986B63AD>) |
| 8086:27da | 1849:27da | Intel            | NM10/ICH7 Family SMBus Controller    | 565   | i2c_i801   | [E9A4F752C5](<Desktop/ASRock/G41/G41M-VS3/21B774A42A5B/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/E9A4F752C5>) |
| 10de:03eb | 1849:03eb | Nvidia           | MCP61 SMBus                          | 538   | i2c_nfo... | [DCF5CD4CA2](<Desktop/ASRock/N68C-GS/N68C-GS FX/CD0566A64BB2/FEDORA-37/6.2.14-200.FC37.X86_64/X86_64/DCF5CD4CA2>) |
| 8086:8ca2 | 1043:8534 | Intel            | 9 Series Chipset Family SMBus Con... | 516   | i2c_i801   | [C47205C3CB](<Desktop/ASUSTek Computer/All/All Series/0A37A7D15166/STEAMOS-4/6.1.21-VALVE1-1-NEPTUNE-61/X86_64/C47205C3CB>) |
| 1022:780b | 1849:780b | AMD              | FCH SMBus Controller                 | 510   | i2c_pii... | [53C03D6942](<Desktop/ASRock/FM2A88X/FM2A88X Extreme6+/061803342427/FEDORA-37/6.0.11-300.FC37.X86_64/X86_64/53C03D6942>) |
| 8086:a323 | 1458:5001 | Intel            | Cannon Lake PCH SMBus Controller     | 490   | i2c_i801   | [19D78D1685](<Desktop/Gigabyte Technology/Z390/Z390 UD/8E72A411386D/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/19D78D1685>) |
| 1022:790b | 1043:876b | AMD              | FCH SMBus Controller                 | 485   | i2c_piix4  | [369BF3DC68](<Desktop/CMS Computers/7200/7200-5413A/68D04878595E/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/369BF3DC68>) |
| 8086:2930 | 1043:8277 | Intel            | 82801I (ICH9 Family) SMBus Contro... | 462   | i2c_i801   | [D15B9FB438](<Desktop/ASUSTek Computer/P5/P5K/0772711AD395/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/D15B9FB438>) |
| 8086:3b30 | 1043:8383 | Intel            | 5 Series/3400 Series Chipset SMBu... | 408   | i2c_i801   | [897FC61B8C](<Desktop/ASUSTek Computer/P7Q57-M/P7Q57-M DO/6AEA267E7346/LMDE-5/5.10.0-22-AMD64/X86_64/897FC61B8C>) |
| 8086:8ca2 | 1458:5001 | Intel            | 9 Series Chipset Family SMBus Con... | 393   | i2c_i801   | [2CBFF804D8](<Desktop/Gigabyte Technology/Z97X-Gaming/Z97X-Gaming 3/EEB9D6F73B6D/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/2CBFF804D8>) |
| 8086:3a30 | 1458:5001 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 391   | i2c_i801   | [1095D1EF7F](<Desktop/Gigabyte Technology/P43/P43-ES3G/A4BFA139B00C/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/1095D1EF7F>) |
| 8086:8c22 | 1849:8c22 | Intel            | 8 Series/C220 Series Chipset Fami... | 389   | i2c_i801   | [E3971068B6](<Desktop/ASRock/Z87/Z87 Pro4/7D116E456DAE/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/E3971068B6>) |
| 8086:1e22 | 1028:0577 | Intel            | 7 Series/C216 Chipset Family SMBu... | 377   | i2c_i801   | [F0F22D5D3F](<Desktop/Dell/OptiPlex/OptiPlex 7010/D7591CF7C8EA/UBUNTU-20.04/5.4.0-148-GENERIC/X86_64/F0F22D5D3F>) |
| 8086:1c22 | 1849:1c22 | Intel            | 6 Series/C200 Series Chipset Fami... | 375   | i2c_i801   | [13B1131BEF](<Desktop/ASRock/H67/H67DE3-SI/ED18AAFC18F5/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/13B1131BEF>) |
| 1022:790b | 1462:7c37 | AMD              | FCH SMBus Controller                 | 340   | i2c_piix4  | [46894747B1](<Desktop/MSI/MS-7/MS-7C37/9E9208EB0239/ZORIN-16/5.15.0-71-GENERIC/X86_64/46894747B1>) |
| 8086:1c22 | 8086:1c22 | Intel            | 6 Series/C200 Series Chipset Fami... | 338   | i2c_i801   | [C359F42A22](<Desktop/Intel/H/H61/3D6C0125E768/MANJARO/6.1.25-1-MANJARO/X86_64/C359F42A22>) |
| 8086:43a3 | 1043:8694 | Intel            | Tiger Lake-H SMBus Controller        | 338   | i2c_i801   | [DE65A79BF1](<Desktop/ASUSTek Computer/TUF/TUF Gaming B560M-PLUS/929B4939E2C7/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/DE65A79BF1>) |
| 1022:790b | 1043:87e1 | AMD              | FCH SMBus Controller                 | 304   | i2c_piix4  | [D58E08C9AB](<Desktop/ASUSTek Computer/PRIME/PRIME B550-PLUS/1C885144C28F/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/D58E08C9AB>) |
| 1022:790b | 1462:7c02 | AMD              | FCH SMBus Controller                 | 300   | i2c_piix4  | [3A7E1532DA](<Desktop/MSI/MS-7/MS-7C02/ACF3D9051F49/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/3A7E1532DA>) |
| 8086:a2a3 | 1849:a2a3 | Intel            | 200 Series/Z370 Chipset Family SM... | 293   | i2c_i801   | [D905BABC43](<Desktop/ASRock/B250/B250M-HDV/A65B4BC89A4A/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/D905BABC43>) |
| 8086:a123 | 1849:a123 | Intel            | 100 Series/C230 Series Chipset Fa... | 292   | i2c_i801   | [A38BF561F7](<Desktop/ASRock/Z170/Z170 Gaming K4/19138DC977DF/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/A38BF561F7>) |
| 8086:3b30 | 1458:5001 | Intel            | 5 Series/3400 Series Chipset SMBu... | 290   | i2c_i801   | [A07A7CF773](<Desktop/Gigabyte Technology/P55/P55M-UD2/B36DC4286599/OPENMANDRIVA-4.90/5.18.12-DESKTOP-3OMV4090/X86_64/A07A7CF773>) |
| 8086:8c22 | 1462:7817 | Intel            | 8 Series/C220 Series Chipset Fami... | 286   | i2c_i801   | [B5C0679341](<Desktop/MSI/MS/MS-7817/73BC5E06C84D/GENTOO-2.13/6.3.1-GENTOO/X86_64/B5C0679341>) |
| 8086:1e22 | 1849:1e22 | Intel            | 7 Series/C216 Chipset Family SMBu... | 279   | i2c_i801   | [0DA080327F](<Desktop/ASRock/Z77/Z77 Extreme3/7F778DC75AC8/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/0DA080327F>) |
| 10de:03eb | 1458:0c11 | Nvidia           | MCP61 SMBus                          | 275   | i2c_nfo... | [D571B75547](<Desktop/Gigabyte Technology/M68/M68MT-S2/333806208DA6/ZORIN-16/5.15.0-71-GENERIC/X86_64/D571B75547>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1002:ab28 | 1002:ab28 | AMD              | Navi 21/23 HDMI/DP Audio Controller  | 1212  | snd_hda... | [4A8C2101E8](<Desktop/ASUSTek Computer/PRIME/PRIME X570-PRO/D1E7CA404339/DEBIAN-11/5.10.0-22-AMD64/X86_64/4A8C2101E8>) |
| 1002:15de | 1002:15de | AMD              | Raven/Raven2/Fenghuang HDMI/DP Au... | 1116  | snd_hda... | [2A09FB1D81](<Desktop/Gigabyte Technology/B450M/B450M DS3H/93E61F10B914/LINUXMINT-20.3/5.4.0-148-GENERIC/X86_64/2A09FB1D81>) |
| 1002:ab38 | 1002:ab38 | AMD              | Navi 10 HDMI Audio                   | 1071  | snd_hda... | [53D91DCA3C](<Desktop/ASRock/B450M/B450M Steel Legend/57EFD5B4322B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/53D91DCA3C>) |
| 8086:0c0c | 8086:2010 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 1043  | snd_hda... | [22BD54D6D1](<Desktop/Gigabyte Technology/Z87/Z87X-UD3H/F9D737247AAE/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/22BD54D6D1>) |
| 8086:8c20 | 1043:8576 | Intel            | 8 Series/C220 Series Chipset High... | 897   | snd_hda... | [E146C82A49](<Desktop/ASUSTek Computer/All/All Series/D75C393B8A2E/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/E146C82A49>) |
| 8086:27d8 | 1458:a002 | Intel            | NM10/ICH7 Family High Definition ... | 839   | snd_hda... | [0458D9F44B](<Desktop/Gigabyte Technology/G41/G41MT-S2/EF1568975525/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/0458D9F44B>) |
| 1002:aaf0 | 1da2:aaf0 | AMD              | Ellesmere HDMI Audio [Radeon RX 4... | 803   | snd_hda... | [F5499886E9](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/D04FB50B5F37/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/F5499886E9>) |
| 8086:8c20 | 1458:a002 | Intel            | 8 Series/C220 Series Chipset High... | 781   | snd_hda... | [22BD54D6D1](<Desktop/Gigabyte Technology/Z87/Z87X-UD3H/F9D737247AAE/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/22BD54D6D1>) |
| 8086:1c20 | 1458:a002 | Intel            | 6 Series/C200 Series Chipset Fami... | 769   | snd_hda... | [E7B77F5CF0](<Desktop/Gigabyte Technology/Z68/Z68MA-D2H-B3/99DA8E367A7A/OPENMANDRIVA-23.03/5.16.13-DESKTOP-1OMV4003/X86_64/E7B77F5CF0>) |
| 1002:4383 | 1458:a002 | AMD              | SBx00 Azalia (Intel HDA)             | 759   | snd_hda... | [631317F909](<Desktop/Gigabyte Technology/GA-78/GA-78LMT-S2/A7640481CED2/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/631317F909>) |
| 10de:0e0f | 1462:8c93 | Nvidia           | GK208 HDMI/DP Audio Controller       | 638   | snd_hda... | [33B7A6BA7C](<Desktop/MSI/MS-7/MS-7B33/34289ECA4E14/LINUXMINT-21.1/5.19.0-41-GENERIC/X86_64/33B7A6BA7C>) |
| 1022:1457 | 1458:a182 | AMD              | Family 17h (Models 00h-0fh) HD Au... | 618   | snd_hda... | [E6EAD6E953](<Desktop/Gigabyte Technology/B450/B450 AORUS ELITE/9C8C09595939/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/E6EAD6E953>) |
| 1002:aaf0 | 1462:aaf0 | AMD              | Ellesmere HDMI Audio [Radeon RX 4... | 588   | snd_hda... | [C88845AE9B](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/F6418012BC03/GENTOO-2.13/6.3.1-GENTOO-POLARIS/X86_64/C88845AE9B>) |
| 8086:a170 | 1043:86c7 | Intel            | 100 Series/C230 Series Chipset Fa... | 579   | snd_hda... | [756E372A11](<Desktop/ASUSTek Computer/Z170/Z170-P/BC9CF352F91A/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/756E372A11>) |
| 1002:4383 | 1043:8445 | AMD              | SBx00 Azalia (Intel HDA)             | 566   | snd_hda... | [E3DC27EEE1](<Desktop/ASUSTek Computer/M5A78L/M5A78L LE/E8B8C04727FE/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/E3DC27EEE1>) |
| 1002:1637 | 1002:1637 | AMD              | Renoir Radeon High Definition Aud... | 555   | snd_hda... | [AE040331E6](<Desktop/Gigabyte Technology/B550M/B550M DS3H/BD5F281A2678/LINUXMINT-20.3/5.15.0-56-GENERIC/X86_64/AE040331E6>) |
| 1002:aab0 | 174b:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 549   | snd_hda... | [E8C596445B](<Desktop/Gigabyte Technology/B550M/B550M DS3H/401B5C2F5C04/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/E8C596445B>) |
| 1022:1487 | 1043:8797 | AMD              | Starship/Matisse HD Audio Controller | 545   | snd_hda... | [4E424E0AD2](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/2E14927B3139/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/4E424E0AD2>) |
| 1002:aaf0 | 1682:aaf0 | AMD              | Ellesmere HDMI Audio [Radeon RX 4... | 540   | snd_hda... | [F86E67C005](<Desktop/Gigabyte Technology/Z97/Z97-D3H/A009D543E318/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/F86E67C005>) |
| 8086:0c0c | 1043:8534 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 539   | snd_hda... | [2DA8FF7129](<Desktop/ASUSTek Computer/All/All Series/55E374A7ECC4/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/2DA8FF7129>) |
| 8086:a2f0 | 1458:a182 | Intel            | 200 Series PCH HD Audio              | 535   | snd_hda... | [E44F7DFAC5](<Desktop/Punch Technology/PDT-702/PDT-702-1020/29C76CB9E8B7/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/E44F7DFAC5>) |
| 1022:1457 | 1043:86c7 | AMD              | Family 17h (Models 00h-0fh) HD Au... | 521   | snd_hda... | [B6EC076CC6](<Desktop/ASUSTek Computer/PRIME/PRIME B350-PLUS/0870723C67EE/UBUNTU-MATE-22.04/5.15.0-48-GENERIC/X86_64/B6EC076CC6>) |
| 8086:a170 | 1458:a182 | Intel            | 100 Series/C230 Series Chipset Fa... | 504   | snd_hda... | [61D04B0E4C](<Desktop/Gigabyte Technology/H110/H110M-S2V-CF/336397A7FCB2/BLACKPANTHER-OS-18.1/5.15.85-DESKTOP-1BP/X86_64/61D04B0E4C>) |
| 8086:1e20 | 1458:a002 | Intel            | 7 Series/C216 Chipset Family High... | 495   | snd_hda... | [A72531BD2D](<Desktop/MouseComputer/B75/B75M-D3V-JP/041627593BC4/LINUXMINT-18.3/4.8.0-58-GENERIC/X86_64/A72531BD2D>) |
| 8086:1c20 | 1043:8445 | Intel            | 6 Series/C200 Series Chipset Fami... | 480   | snd_hda... | [6C96DBE3F3](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX/CC2C86F5F25E/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/6C96DBE3F3>) |
| 8086:a2f0 | 1043:86c7 | Intel            | 200 Series PCH HD Audio              | 447   | snd_hda... | [77ECF9C05D](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-K/C1DFDE9A944B/ARCHLABSX-ROLLING/6.2.14-1-CLEAR/X86_64/77ECF9C05D>) |
| 1002:4383 | 1043:836c | AMD              | SBx00 Azalia (Intel HDA)             | 445   | snd_hda... | [CBF9D11153](<Desktop/ASUSTek Computer/M4/M4A785-M/23278E631048/UBUNTUSTUDIO-22.04/5.15.0-71-LOWLATENCY/X86_64/CBF9D11153>) |
| 1022:15e3 | 1458:a182 | AMD              | Family 17h/19h HD Audio Controller   | 445   | snd_hda... | [2A09FB1D81](<Desktop/Gigabyte Technology/B450M/B450M DS3H/93E61F10B914/LINUXMINT-20.3/5.4.0-148-GENERIC/X86_64/2A09FB1D81>) |
| 13f6:0111 | 13f6:0111 | C-Media Elect... | CMI8738/CMI8768 PCI Audio            | 442   | snd_cmipci | [37F3DA239A](<Desktop/MSI/MS/MS-7693/C85B0030F9F4/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/37F3DA239A>) |
| 1002:4383 | 1458:a182 | AMD              | SBx00 Azalia (Intel HDA)             | 435   | snd_hda... | [ACF61A6132](<Desktop/Gigabyte Technology/970/970A-DS3P/4209CEC662D2/OPENMANDRIVA-23.03/6.2.10-DESKTOP-2.0OMV4.9MJN/X86_64/ACF61A6132>) |
| 1022:15e3 | 1043:86c7 | AMD              | Family 17h/19h HD Audio Controller   | 433   | snd_hda... | [369BF3DC68](<Desktop/CMS Computers/7200/7200-5413A/68D04878595E/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/369BF3DC68>) |
| 1002:aab0 | 1043:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 427   | snd_hda... | [19D78D1685](<Desktop/Gigabyte Technology/Z390/Z390 UD/8E72A411386D/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/19D78D1685>) |
| 8086:1e20 | 1043:8445 | Intel            | 7 Series/C216 Chipset Family High... | 409   | snd_hda... | [92B5951471](<Desktop/ASUSTek Computer/Z77/Z77-A/7F8B426D3C22/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/92B5951471>) |
| 10de:03f0 | 1849:0397 | Nvidia           | MCP61 High Definition Audio          | 399   | snd_hda... | [DCF5CD4CA2](<Desktop/ASRock/N68C-GS/N68C-GS FX/CD0566A64BB2/FEDORA-37/6.2.14-200.FC37.X86_64/X86_64/DCF5CD4CA2>) |
| 1022:1487 | 1458:a0c3 | AMD              | Starship/Matisse HD Audio Controller | 398   | snd_hda... | [BDAFBE06AA](<Desktop/Gigabyte Technology/X570S/X570S AORUS ELITE AX/9F1A18147C09/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/BDAFBE06AA>) |
| 1002:aaf0 | 1043:aaf0 | AMD              | Ellesmere HDMI Audio [Radeon RX 4... | 388   | snd_hda... | [C47205C3CB](<Desktop/ASUSTek Computer/All/All Series/0A37A7D15166/STEAMOS-4/6.1.21-VALVE1-1-NEPTUNE-61/X86_64/C47205C3CB>) |
| 8086:1c20 | 1043:8415 | Intel            | 6 Series/C200 Series Chipset Fami... | 385   | snd_hda... | [9A420C42DE](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3/ABA4EBB5D0B8/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-X86_64/X86_64/9A420C42DE>) |
| 8086:1e20 | 1028:0577 | Intel            | 7 Series/C216 Chipset Family High... | 376   | snd_hda... | [F0F22D5D3F](<Desktop/Dell/OptiPlex/OptiPlex 7010/D7591CF7C8EA/UBUNTU-20.04/5.4.0-148-GENERIC/X86_64/F0F22D5D3F>) |
| 1002:15de | 1043:876b | AMD              | Raven/Raven2/Fenghuang HDMI/DP Au... | 370   | snd_hda... | [A375533DAA](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-K/A2EE7FB360B4/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/A375533DAA>) |
| 1102:0012 | 1102:0010 | Creative Labs    | CA0132 Sound Core3D [Sound Blaste... | 370   | snd_hda... | [19D78D1685](<Desktop/Gigabyte Technology/Z390/Z390 UD/8E72A411386D/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/19D78D1685>) |
| 1022:1487 | 1043:87c5 | AMD              | Starship/Matisse HD Audio Controller | 367   | snd_hda... | [AD66608CF0](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/E039702D1078/CHIMERAOS-41/6.1.21-1-LTS/X86_64/AD66608CF0>) |
| 1022:780d | 1458:a002 | AMD              | FCH Azalia Controller                | 363   | snd_hda... | [850EA7C843](<Desktop/Gigabyte Technology/F2/F2A88XM-D3H/BF3B2C86ADDB/ATZ-11.7/5.10.0-22-RT-AMD64/X86_64/850EA7C843>) |
| 1002:aaf8 | 1002:aaf8 | AMD              | Vega 10 HDMI Audio [Radeon Vega 5... | 344   | snd_hda... | [421F2DE1C3](<Desktop/Gigabyte Technology/Z370/Z370 AORUS Gaming 5/69B7F7EE2BF7/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/421F2DE1C3>) |
| 1022:780d | 1043:8576 | AMD              | FCH Azalia Controller                | 344   | snd_hda... | [870A49D90C](<Desktop/ASUSTek Computer/A88/A88XM-PLUS/40D45C4AF68F/UBUNTU-22.04/5.13.0-30-GENERIC/X86_64/870A49D90C>) |
| 1002:aa98 | 174b:aa98 | AMD              | Caicos HDMI Audio [Radeon HD 6450... | 320   | snd_hda... | [DE394C8663](<Desktop/Dell/OptiPlex/OptiPlex 3010/D899A78989BD/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/DE394C8663>) |
| 1022:1487 | 1458:a0cf | AMD              | Starship/Matisse HD Audio Controller | 309   | snd_hda... | [60C407B4E4](<Desktop/Gigabyte Technology/B550/B550 AORUS ELITE V2/0FF3A56B8BAA/KDE-NEON-22.04/5.19.0-35-GENERIC/X86_64/60C407B4E4>) |
| 8086:1c20 | 8086:1c20 | Intel            | 6 Series/C200 Series Chipset Fami... | 309   | snd_hda... | [C359F42A22](<Desktop/Intel/H/H61/3D6C0125E768/MANJARO/6.1.25-1-MANJARO/X86_64/C359F42A22>) |
| 1002:aaf0 | 1458:aaf0 | AMD              | Ellesmere HDMI Audio [Radeon RX 4... | 304   | snd_hda... | [DCF5CD4CA2](<Desktop/ASRock/N68C-GS/N68C-GS FX/CD0566A64BB2/FEDORA-37/6.2.14-200.FC37.X86_64/X86_64/DCF5CD4CA2>) |
| 8086:a348 | 1458:a182 | Intel            | Cannon Lake PCH cAVS                 | 300   | snd_hda... | [19D78D1685](<Desktop/Gigabyte Technology/Z390/Z390 UD/8E72A411386D/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/19D78D1685>) |
| 1002:4383 | 1458:a102 | AMD              | SBx00 Azalia (Intel HDA)             | 298   | snd_hda... | [B1FB1BDECF](<Desktop/Gigabyte Technology/GA-890/GA-890GPA-UD3H/196D4EF3C39F/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/B1FB1BDECF>) |

### Ssa (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1033:0030 | 1631:0030 | NEC Computers    | SSA                                  | 1     |            | [77CC2BD640](<Desktop/ASUSTek Computer/P5QL/P5QL PRO/E31D58098942/LINUXMINT-21.1/5.15.0-58-GENERIC/X86_64/77CC2BD640>) |

### Storage (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1283:8211 | 1043:8138 | Integrated Te... | ITE 8211F Single Channel UDMA 133    | 47    | pata_it... | [B2AE663FEC](<Desktop/ASUSTek Computer/P5/P5LD2-VM/0A0C7A5450D3/LINUXMINT-21/5.15.0-56-GENERIC/X86_64/B2AE663FEC>) |
| 105a:4d69 | 105a:4d68 | Promise Techn... | 20269                                | 7     | pata_pd... | [E054BB7F91](<Desktop/Biostar/B150/B150GT5/BD6B8AC5D3D3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/E054BB7F91>) |
| 1283:8211 | 1283:8211 | Integrated Te... | ITE 8211F Single Channel UDMA 133    | 5     | pata_it... | [9BF45B492E](<Desktop/Gateway/DX442/DX442X/7D677660B6C0/LINUXMINT-20.3/5.4.0-96-GENERIC/X86_64/9BF45B492E>) |
| 105a:3d17 | 105a:3d17 | Promise Techn... | PDC40718 (SATA 300 TX4)              | 4     | sata_pr... | [B416C587AF](<Desktop/ASUSTek Computer/Z77/Z77-A/82788F68F9BC/DEBIAN-11/5.15.35-2-PVE/X86_64/B416C587AF>) |
| 105a:3d73 | 105a:3d73 | Promise Techn... | PDC40775 (SATA 300 TX2plus)          | 4     | sata_pr... | [CA1D7DD61B](<Desktop/ASUSTek Computer/M5A97/M5A97 EVO R2.0/707628D0CD7C/DEBIAN-11/5.10.0-16-AMD64/X86_64/CA1D7DD61B>) |
| 105a:4d68 | 105a:4d68 | Promise Techn... | PDC20268 [Ultra100 TX2]              | 4     | pata_pd... | [822D0F1C17](<Desktop/Dell/Inspiron/Inspiron 531/D5CC5324C255/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/822D0F1C17>) |
| 1077:2432 | 1077:0138 | QLogic           | ISP2432-based 4Gb Fibre Channel t... | 4     | qla2xxx    | [D00EBFBC62](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/8A70BC1B82BA/GENTOO-2.13/6.2.11-GENTOO-X86_64/X86_64/D00EBFBC62>) |
| 1106:401a | 1028:02f5 | VIA Technologies | Card Reader Host Controller          | 4     |            | [749DC04756](<Desktop/Dell/Vostro/Vostro 320/D38BEB53BFB6/UBUNTU-UNITY-16.04/4.15.0-142-GENERIC/I686/749DC04756>) |
| 1077:2432 | 103c:7040 | QLogic           | ISP2432-based 4Gb Fibre Channel t... | 3     | qla2xxx    | [4201144CAA](<Desktop/Hewlett-Packard/Z400/Z400 Workstation/45E8FD871842/POP!_OS-20.04/5.15.5-76051505-GENERIC/X86_64/4201144CAA>) |
| 1077:2432 | 1077:0137 | QLogic           | ISP2432-based 4Gb Fibre Channel t... | 3     | qla2xxx    | [B26AB9FC5D](<Desktop/Hewlett-Packard/Z200/Z200 Workstation/5CE500608C15/OPENMANDRIVA-23.01/6.2.0-DESKTOP-0.RC2.1OMV2301/X86_64/B26AB9FC5D>) |
| 1106:401a | 1028:0408 | VIA Technologies | Card Reader Host Controller          | 3     |            | [924B0C6AC0](<Desktop/Dell/Inspiron/Inspiron One 19A/DEFB3954302F/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/924B0C6AC0>) |
| 1000:0646 | 1000:1240 | Broadcom / LSI   | FC949ES Fibre Channel Adapter        | 2     | mptfc      | [1CAF5C85D9](<Desktop/MSI/MS/MS-7900/4C9F4DF4B430/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/1CAF5C85D9>) |
| 105a:1275 | 105a:1275 | Promise Techn... | 20275                                | 2     | pata_pd... | [AA1A843244](<Desktop/Others/Others/Others/7994F07888CD/DEBIAN-8/4.1.42-RIVOREO-POWERPC64/PPC64/AA1A843244>) |
| 105a:3375 | 105a:3375 | Promise Techn... | PDC20375 (SATA150 TX2plus)           | 2     | sata_pr... | [2A0863DD05](<Desktop/MSI/MS/MS-7369/5B88DBFE2DF0/UBUNTU-20.04/5.8.0-53-GENERIC/X86_64/2A0863DD05>) |
| 1077:2532 | 103c:3263 | QLogic           | ISP2532-based 8Gb Fibre Channel t... | 2     | qla2xxx    | [D018E3FE5A](<Desktop/Fujitsu/D3128/D3128-B2/B615571144A4/UBUNTU-20.04/5.8.0-53-GENERIC/X86_64/D018E3FE5A>) |
| 1077:2532 | 1077:015d | QLogic           | ISP2532-based 8Gb Fibre Channel t... | 2     | qla2xxx    | [2E37B66578](<Desktop/ASRock/X399/X399 Taichi/62F5196F4764/ZORIN-16/5.13.0-39-GENERIC/X86_64/2E37B66578>) |
| 1095:0680 | 1095:0680 | Silicon Image    | PCI0680 Ultra ATA-133 Host Contro... | 2     | pata_si... | [583A217093](<Desktop/ASUSTek Computer/PRIME/PRIME B350-PLUS/7EC94B9F5DB8/UBUNTU-18.04/4.15.0-29-GENERIC/X86_64/583A217093>) |
| 10df:f0e5 | 10df:f0e5 | Emulex           | Zephyr LightPulse Fibre Channel H... | 2     | lpfc       | [E16021B874](<Desktop/ASUSTek Computer/P9X79-E/P9X79-E WS/56C6B4096368/OPENMANDRIVA-23.01/6.2.0-DESKTOP-0.RC2.1OMV2301/X86_64/E16021B874>) |
| 10df:f100 | 1014:038a | Emulex           | LPe12000 Series 8Gb Fibre Channel... | 2     | lpfc       | [0767C99ABB](<Desktop/ASUSTek Computer/All/All Series/F96B22E24271/FEDORA-34/5.11.12-300.FC34.X86_64/X86_64/0767C99ABB>) |
| 10df:fe00 | 10df:fe00 | Emulex           | Zephyr-X LightPulse Fibre Channel... | 2     | lpfc       | [F930BC123E](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/63F68F9C401C/GENTOO-2.6/5.0.2-GENTOO/X86_64/F930BC123E>) |
| 1106:401a | 1106:401a | VIA Technologies | Card Reader Host Controller          | 2     |            | [FF6AA83006](<Desktop/ASUSTek Computer/P-P5/P-P5G41/8BAA9027C3D5/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/FF6AA83006>) |
| 0000:8000 |           |                  | Storage controller                   | 1     |            | [5F653AFDFF](<Desktop/Arquimedes Automacao Inf./ARQ/ARQ78/9F57B289538E/KDE-NEON-20.04/5.15.0-46-GENERIC/X86_64/5F653AFDFF>) |
| 1000:0646 | 1000:1020 | Broadcom / LSI   | FC949ES Fibre Channel Adapter        | 1     | mptfc      | [557131B1DD](<Desktop/Hewlett-Packard/Z200/Z200 Workstation/5CE500608C15/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/557131B1DD>) |
| 1000:c010 | 1000:00b2 | Broadcom / LSI   | PEX880xx PCIe Gen 4 Switch           | 1     |            | [19C318242F](<Desktop/Others/Others/Others/C3C1AB1B873D/UBUNTU-20.04/5.15.0-1023-NVIDIA/X86_64/19C318242F>) |
| 104c:8033 | 103c:3085 | Texas Instrum... | PCIxx21/PCIxx11 Flash Media Contr... | 1     | tifm_7xx1  | [46E47F957D](<Desktop/Hewlett-Packard/Presario/Presario R4100/36F4F69E2F33/XUBUNTU-18.04/5.3.0-40-GENERIC/I686/46E47F957D>) |
| 104c:803b | 104d:9030 | Texas Instrum... | PCIxx12 Flash Media Controller       | 1     | tifm_7xx1  | [6A92AB4681](<Desktop/Sony/VGX-TP20/VGX-TP20E/685D27836E46/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/6A92AB4681>) |
| 104c:803b | 152d:0754 | Texas Instrum... | PCIxx12 Flash Media Controller       | 1     | tifm_7xx1  | [79905DEFFE](<Desktop/Semp Toshiba/IS/IS-1451/6FBAA5A8B2B6/UBUNTU-18.04/5.3.0-28-GENERIC/X86_64/79905DEFFE>) |
| 105a:3d75 | 105a:3d75 | Promise Techn... | PDC20575 (SATAII150 TX2plus)         | 1     | sata_pr... | [8693B86435](<Desktop/ASUSTek Computer/P5/P5Q/0A80C42BEFF3/ZORIN-16/5.11.0-34-GENERIC/X86_64/8693B86435>) |
| 105a:4d30 | 105a:4d33 | Promise Techn... | PDC20267 (FastTrak100/Ultra100)      | 1     | pata_pd... | [1B02673A1A](<Desktop/ASUSTek Computer/M2/M2N-E/91A4233E1631/ZORIN-15/5.4.0-81-GENERIC/X86_64/1B02673A1A>) |
| 1077:2312 | 1077:0100 | QLogic           | ISP2312-based 2Gb Fibre Channel t... | 1     | qla2xxx    | [17333FB7FD](<Desktop/Gigabyte Technology/GA-MA74/GA-MA74GM-S2H/B8A41E7E7177/KUBUNTU-20.04/5.4.0-56-GENERIC/X86_64/17333FB7FD>) |
| 1077:2422 | 1077:0134 | QLogic           | ISP2422-based 4Gb Fibre Channel t... | 1     | qla2xxx    | [073427BC3C](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML350 G5/846BA65D22AB/ROSA-12.3/5.15.79-GENERIC-1ROSA2021.1-X86_64/X86_64/073427BC3C>) |
| 1077:2432 | 103c:7041 | QLogic           | ISP2432-based 4Gb Fibre Channel t... | 1     | qla2xxx    | [14ACFD829D](<Desktop/ASUSTek Computer/CM6330/CM6330_CM6630_CM6730_CM6830_M11AA-8/68B88257D7E1/LINUXMINT-20.2/5.10.0-1049-OEM/X86_64/14ACFD829D>) |
| 10b9:5289 | 1043:816b | ULi Electronics  | ULi 5289 SATA                        | 1     | sata_uli   | [1473488491](<Desktop/ASUSTek Computer/K8/K8U-X/24AB02D5F71C/ROSA-2014.1/4.1.15-NRJ-DESKTOP-1ROSA-I586/I686/1473488491>) |
| 10df:0724 | 10df:e86b | Emulex           | OneConnect FCoE Initiator (Skyhawk)  | 1     | lpfc       | [68F608CA5B](<Desktop/Gigabyte Technology/G41/G41M-Combo/CF1CDFE6DF79/UBUNTU-18.04/4.15.0-96-GENERIC/X86_64/68F608CA5B>) |
| 10df:fa00 | 10df:fa00 | Emulex           | Thor-X LightPulse Fibre Channel H... | 1     | lpfc       | [EFE38992BD](<Desktop/ASRock/FM2/FM2A55M-DGS/3356090000D2/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/EFE38992BD>) |
| 10df:fc20 | 10df:fc22 | Emulex           | Zephyr-X LightPulse Fibre Channel... | 1     | lpfc       | [6181F2FD4A](<Desktop/ASUSTek Computer/PRIME/PRIME Z690-P/7CD4E2556D2A/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/6181F2FD4A>) |
| 10df:fe00 | 10df:fe01 | Emulex           | Zephyr-X LightPulse Fibre Channel... | 1     | lpfc       | [CAEF8BBDD2](<Desktop/ASUSTek Computer/All/All Series/F96B22E24271/FEDORA-31/5.8.10-100.FC31.X86_64/X86_64/CAEF8BBDD2>) |
| 1103:0004 | 1103:0005 | HighPoint Tec... | HPT366/368/370/370A/372/372N         | 1     | pata_hp... | [254FDA14C1](<Desktop/Lenovo/ThinkCentre/ThinkCentre A57 98517HG/D1ABDBF6BE80/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/254FDA14C1>) |
| 11f8:8032 |           | PMC-Sierra       | PM8032 Tachyon QE8                   | 1     |            | [B80429C5FE](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3/8CC6840142A2/DEBIAN-11/5.10.0-11-AMD64/X86_64/B80429C5FE>) |
| 11f8:8032 | 117c:003c | PMC-Sierra       | PM8032 Tachyon QE8                   | 1     |            | [E21E07827D](<Desktop/Lenovo/ThinkStation/ThinkStation P620 30E0S0PR00/C849C069B5E8/ROCKY-8.5/4.18.0-348.20.1.EL8_5.X86_64/X86_64/E21E07827D>) |
| 1217:7130 | 1025:0124 | O2 Micro         | Integrated MS/xD Controller          | 1     |            | [1F2C670EC4](<Desktop/Acer/TravelMate/TravelMate 7520/07648081A013/ROSA-2016.1/4.9.20-NRJ-DESKTOP-1ROSA-I586/I686/1F2C670EC4>) |
| 1217:7130 | 14ff:a003 | O2 Micro         | Integrated MS/xD Controller          | 1     |            | [6647A9CB02](<Desktop/Dixonsxp/Others/Others/0CFC1CA145C2/UBUNTU-18.04/4.15.0-50-GENERIC/I686/6647A9CB02>) |
| 1425:4607 | 1425:0000 | Chelsio Commu... | T420-SO Unified Wire Storage Cont... | 1     | csiostor   | [304C12788B](<Desktop/ASUSTek Computer/PRIME/PRIME X399-A/925C69D7A644/DEVUAN-4/5.10.0-18-AMD64/X86_64/304C12788B>) |
| 1425:4609 | 1425:0000 | Chelsio Commu... | T420-BT Unified Wire Storage Cont... | 1     | csiostor   | [5499373552](<Desktop/Gigabyte Technology/Z77/Z77X-UD3H/50D737B61145/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/5499373552>) |
| 1425:5610 | 1425:0000 | Chelsio Commu... | T580-LP-CR Unified Wire Storage C... | 1     |            | [9076954881](<Desktop/ASUSTek Computer/ESC4000/ESC4000 G3 Series/5BB30550A6BE/DEBIAN-9/4.9.35-DYVI/X86_64/9076954881>) |
| 19a2:0704 | 10df:e602 | Emulex           | OneConnect OCe10100/OCe10102 Seri... | 1     | lpfc       | [456CDA8C49](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/8FB50DAECFA2/UBUNTU-18.04/4.15.0-50-GENERIC/X86_64/456CDA8C49>) |
| 1aed:2001 | 1014:0432 | SanDisk          | ioDrive2                             | 1     |            | [C3D0C5DA79](<Desktop/ASUSTek Computer/ROG/ROG STRIX X570-F GAMING/890E8E7CC7D7/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/C3D0C5DA79>) |
| 1aed:2001 | 1590:006d | SanDisk          | ioDrive2                             | 1     |            | [4A5147AC07](<Desktop/MSI/MS-7/MS-7B79/C192C1FFEB81/FEDORA-32/5.6.16-300.FC32.X86_64/X86_64/4A5147AC07>) |
| 1aed:2001 | 1aed:2001 | SanDisk          | ioDrive2                             | 1     | iomemor... | [80E12BBDD7](<Desktop/Apple/MacPro5/MacPro5,1/10D8EDAEC2EB/XUBUNTU-18.04/4.15.0-121-GENERIC/X86_64/80E12BBDD7>) |
| 1aed:3002 | 1014:04d3 | SanDisk          | ioMemory HHHL                        | 1     |            | [FB0D0A1860](<Desktop/Dell/OptiPlex/OptiPlex 9020/AFB33DEF23DE/UBUNTU-18.04/4.18.0-15-GENERIC/X86_64/FB0D0A1860>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:43c8 | 1b21:1062 | AMD              | 400 Series Chipset SATA Controller   | 4156  | ahci       | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 1022:7901 | 1022:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 3246  | ahci       | [4E424E0AD2](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/2E14927B3139/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/4E424E0AD2>) |
| 1022:43eb | 1b21:1062 | AMD              | 500 Series Chipset SATA Controller   | 2258  | ahci       | [DC43E4A7E3](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PRO/1FF7B8E0562A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/DC43E4A7E3>) |
| 1022:7901 | 1458:b002 | AMD              | FCH SATA Controller [AHCI mode]      | 1852  | ahci       | [E6EAD6E953](<Desktop/Gigabyte Technology/B450/B450 AORUS ELITE/9C8C09595939/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/E6EAD6E953>) |
| 1022:7901 | 1043:8747 | AMD              | FCH SATA Controller [AHCI mode]      | 1248  | ahci       | [D9A3AFA732](<Desktop/ASUSTek Computer/ROG/ROG STRIX X470-I GAMING/133421F6DBD4/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/D9A3AFA732>) |
| 8086:8c02 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 1243  | ahci       | [E146C82A49](<Desktop/ASUSTek Computer/All/All Series/D75C393B8A2E/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/E146C82A49>) |
| 8086:a102 | 1043:8694 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 1081  | ahci       | [BBFD29FB88](<Desktop/ASUSTek Computer/D320/D320SF/A7E6ADB389B1/UBUNTU-20.04/5.4.0-148-GENERIC/X86_64/BBFD29FB88>) |
| 1022:43b8 | 1b21:1062 | AMD              | FCH SATA Controller D                | 1069  | ahci       | [A241837604](<Desktop/LTD Delovoy Office/320A3SM/320A3SM MT/67FBE1AE8CE6/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/A241837604>) |
| 1022:43b7 | 1b21:1062 | AMD              | 300 Series Chipset SATA Controller   | 1048  | ahci       | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 1002:4391 | 1458:b002 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 988   | ahci       | [ACF61A6132](<Desktop/Gigabyte Technology/970/970A-DS3P/4209CEC662D2/OPENMANDRIVA-23.03/6.2.10-DESKTOP-2.0OMV4.9MJN/X86_64/ACF61A6132>) |
| 1002:4390 | 1458:b002 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 986   | ahci       | [631317F909](<Desktop/Gigabyte Technology/GA-78/GA-78LMT-S2/A7640481CED2/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/631317F909>) |
| 1022:7901 | 1849:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 960   | ahci       | [28A1F44A1E](<Desktop/ASRockRack/X470/X470D4U2-2T/EEF286979D7B/ALMA-8.7/4.18.0-425.19.2.EL8_7.X86_64/X86_64/28A1F44A1E>) |
| 1002:4391 | 1043:84dd | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 946   | ahci       | [F5499886E9](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/D04FB50B5F37/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/F5499886E9>) |
| 1002:4390 | 1043:8389 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 922   | ahci       | [31123C256D](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/58F18DE5017C/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/31123C256D>) |
| 1b21:0612 | 1849:0612 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 881   | ahci       | [ED03DF615E](<Desktop/ASRock/B650E/B650E PG Riptide WiFi/E45FD3D55523/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/ED03DF615E>) |
| 1b21:0612 | 1043:84b7 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 871   | ahci       | [F9D2B57C91](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X79/F79B74A5FAD0/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/F9D2B57C91>) |
| 8086:1c02 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 864   | ahci       | [386D7C9DE4](<Desktop/ASUSTek Computer/P8/P8P67-M/D3654512534B/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/386D7C9DE4>) |
| 1b21:0612 | 1b21:1060 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 837   | ahci       | [AED14C1E20](<Desktop/Acer/Aspire/Aspire M3920/25FDE4FC074D/KUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/AED14C1E20>) |
| 8086:8c02 | 1458:b005 | Intel            | 8 Series/C220 Series Chipset Fami... | 833   | ahci       | [22BD54D6D1](<Desktop/Gigabyte Technology/Z87/Z87X-UD3H/F9D737247AAE/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/22BD54D6D1>) |
| 8086:1e02 | 1043:84ca | Intel            | 7 Series/C210 Series Chipset Fami... | 794   | ahci       | [92B5951471](<Desktop/ASUSTek Computer/Z77/Z77-A/7F8B426D3C22/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/92B5951471>) |
| 8086:a282 | 1043:8694 | Intel            | 200 Series PCH SATA controller [A... | 694   | ahci       | [77ECF9C05D](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-K/C1DFDE9A944B/ARCHLABSX-ROLLING/6.2.14-1-CLEAR/X86_64/77ECF9C05D>) |
| 8086:a282 | 1458:b005 | Intel            | 200 Series PCH SATA controller [A... | 651   | ahci       | [E44F7DFAC5](<Desktop/Punch Technology/PDT-702/PDT-702-1020/29C76CB9E8B7/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/E44F7DFAC5>) |
| 8086:a102 | 1458:b005 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 617   | ahci       | [8C5B603452](<Desktop/Gigabyte Technology/Z170X-Gaming/Z170X-Gaming 7/F95579DE4AF1/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/8C5B603452>) |
| 1022:43b5 | 1b21:1062 | AMD              | X370 Series Chipset SATA Controller  | 566   | ahci       | [CA84298B9D](<Desktop/Gigabyte Technology/AX370-Gaming/AX370-Gaming K7/21420EC89867/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/CA84298B9D>) |
| 1022:7901 | 1043:87c0 | AMD              | FCH SATA Controller [AHCI mode]      | 564   | ahci       | [A4F7FC7B31](<Desktop/ASUSTek Computer/ROG/ROG STRIX B450-F GAMING II/D242E68778A8/ARCO-ROLLING/6.1.27-1-LTS/X86_64/A4F7FC7B31>) |
| 8086:a352 | 1043:8694 | Intel            | Cannon Lake PCH SATA AHCI Controller | 521   | ahci       | [14C71828CA](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-F GAMING/5D29F2B9EBFF/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/14C71828CA>) |
| 1022:43c8 | 1849:43c8 | AMD              | 400 Series Chipset SATA Controller   | 489   | ahci       | [3C7546E88A](<Desktop/ASRock/B450M/B450M Pro4/2FB451C26D0F/LMDE-5/5.10.0-22-AMD64/X86_64/3C7546E88A>) |
| 8086:8c82 | 1043:8534 | Intel            | 9 Series Chipset Family SATA Cont... | 468   | ahci       | [2DA8FF7129](<Desktop/ASUSTek Computer/All/All Series/55E374A7ECC4/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/2DA8FF7129>) |
| 8086:1e02 | 1458:b005 | Intel            | 7 Series/C210 Series Chipset Fami... | 444   | ahci       | [A72531BD2D](<Desktop/MouseComputer/B75/B75M-D3V-JP/041627593BC4/LINUXMINT-18.3/4.8.0-58-GENERIC/X86_64/A72531BD2D>) |
| 1002:4391 | 1849:4391 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 441   | ahci       | [A68D009BD1](<Desktop/ASRock/970M/970M Pro3/6BAC82210FE1/UBUNTU-20.04/5.15.0-72-GENERIC/X86_64/A68D009BD1>) |
| 8086:a352 | 1458:b005 | Intel            | Cannon Lake PCH SATA AHCI Controller | 438   | ahci       | [19D78D1685](<Desktop/Gigabyte Technology/Z390/Z390 UD/8E72A411386D/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/19D78D1685>) |
| 1b21:0612 | 1043:858d | ASMedia Techn... | ASM1062 Serial ATA Controller        | 437   | ahci       | [401DB07B93](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z690-A GAMING WIFI D4/46556BD3958D/DEBIAN-12/6.1.0-7-AMD64/X86_64/401DB07B93>) |
| 1022:7801 | 1849:7801 | AMD              | FCH SATA Controller [AHCI mode]      | 431   | ahci       | [53C03D6942](<Desktop/ASRock/FM2A88X/FM2A88X Extreme6+/061803342427/FEDORA-37/6.0.11-300.FC37.X86_64/X86_64/53C03D6942>) |
| 1022:7801 | 1458:b002 | AMD              | FCH SATA Controller [AHCI mode]      | 412   | ahci       | [B37927B9D4](<Desktop/Gigabyte Technology/F2/F2A88XM-D3H/BF3B2C86ADDB/ATZ-11.7/5.10.0-22-RT-AMD64/X86_64/B37927B9D4>) |
| 1b4b:9172 | 1458:b000 | Marvell Techn... | 88SE9172 SATA 6Gb/s Controller       | 391   | ahci       | [22BD54D6D1](<Desktop/Gigabyte Technology/Z87/Z87X-UD3H/F9D737247AAE/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/22BD54D6D1>) |
| 1022:7901 | 1043:876b | AMD              | FCH SATA Controller [AHCI mode]      | 384   | ahci       | [A375533DAA](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-K/A2EE7FB360B4/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/A375533DAA>) |
| 8086:8c82 | 1458:b005 | Intel            | 9 Series Chipset Family SATA Cont... | 375   | ahci       | [2CBFF804D8](<Desktop/Gigabyte Technology/Z97X-Gaming/Z97X-Gaming 3/EEB9D6F73B6D/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/2CBFF804D8>) |
| 8086:1c02 | 1458:b005 | Intel            | 6 Series/C200 Series Chipset Fami... | 372   | ahci       | [FE207B0DF1](<Desktop/Gigabyte Technology/H61/H61M-S2PH/7932DFB49C79/ROSA-12.4/5.10.155-GENERIC-1ROSA2021.1-X86_64/X86_64/FE207B0DF1>) |
| 8086:1e02 | 1028:0577 | Intel            | 7 Series/C210 Series Chipset Fami... | 366   | ahci       | [F0F22D5D3F](<Desktop/Dell/OptiPlex/OptiPlex 7010/D7591CF7C8EA/UBUNTU-20.04/5.4.0-148-GENERIC/X86_64/F0F22D5D3F>) |
| 8086:8c02 | 1849:8c02 | Intel            | 8 Series/C220 Series Chipset Fami... | 366   | ahci       | [E3971068B6](<Desktop/ASRock/Z87/Z87 Pro4/7D116E456DAE/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/E3971068B6>) |
| 1022:7901 | 1849:ffff | AMD              | FCH SATA Controller [AHCI mode]      | 347   | ahci       | [1A811619BF](<Desktop/ASRock/B450/B450 Gaming K4/1B36F0DF1999/ROSA-12.4/6.2.12.XM1-1.KLP-XANMOD-ROSA2021.1-X86_64/X86_64/1A811619BF>) |
| 197b:2362 | 1043:8460 | JMicron Techn... | JMB362 SATA Controller               | 339   | ahci       | [F5499886E9](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/D04FB50B5F37/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/F5499886E9>) |
| 8086:43d2 | 1043:8694 | Intel            | 500 Series Chipset Family SATA AH... | 329   | ahci       | [DE65A79BF1](<Desktop/ASUSTek Computer/TUF/TUF Gaming B560M-PLUS/929B4939E2C7/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/DE65A79BF1>) |
| 8086:3a22 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) SATA AHCI ... | 311   | ahci       | [57E3CFA7DC](<Desktop/ASUSTek Computer/P5/P5Q/5FA3807D02EE/ZORIN-16/5.15.0-58-GENERIC/X86_64/57E3CFA7DC>) |
| 1002:4390 | 1849:4390 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 295   | ahci       | [392492C032](<Desktop/ASRock/960GM-GS3/960GM-GS3 FX/6E4C5D76A734/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/392492C032>) |
| 8086:a102 | 1849:a102 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 286   | ahci       | [A38BF561F7](<Desktop/ASRock/Z170/Z170 Gaming K4/19138DC977DF/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/A38BF561F7>) |
| 8086:a282 | 1849:a282 | Intel            | 200 Series PCH SATA controller [A... | 274   | ahci       | [D905BABC43](<Desktop/ASRock/B250/B250M-HDV/A65B4BC89A4A/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/D905BABC43>) |
| 8086:8c02 | 1462:7817 | Intel            | 8 Series/C220 Series Chipset Fami... | 273   | ahci       | [B5C0679341](<Desktop/MSI/MS/MS-7817/73BC5E06C84D/GENTOO-2.13/6.3.1-GENTOO/X86_64/B5C0679341>) |
| 8086:1e02 | 1849:1e02 | Intel            | 7 Series/C210 Series Chipset Fami... | 268   | ahci       | [0DA080327F](<Desktop/ASRock/Z77/Z77 Extreme3/7F778DC75AC8/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/0DA080327F>) |
| 8086:43d2 | 1458:b005 | Intel            | 500 Series Chipset Family SATA AH... | 264   | ahci       | [6EC1762E12](<Desktop/Gigabyte Technology/Z590/Z590 AORUS ULTRA/AA0705BC8FAC/DEBIAN-11/5.10.0-22-AMD64/X86_64/6EC1762E12>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1002:439c | 1458:5002 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 1576  | pata_at... | [ACF61A6132](<Desktop/Gigabyte Technology/970/970A-DS3P/4209CEC662D2/OPENMANDRIVA-23.03/6.2.10-DESKTOP-2.0OMV4.9MJN/X86_64/ACF61A6132>) |
| 8086:27df | 1043:8179 | Intel            | 82801G (ICH7 Family) IDE Controller  | 1281  | ata_pii... | [D5456946BB](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LE/8FE632A39CF5/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D5456946BB>) |
| 1002:439c | 1043:8389 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 1124  | pata_at... | [E3DC27EEE1](<Desktop/ASUSTek Computer/M5A78L/M5A78L LE/E8B8C04727FE/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/E3DC27EEE1>) |
| 8086:27c0 | 1458:b002 | Intel            | NM10/ICH7 Family SATA Controller ... | 976   | pata_acpi  | [0458D9F44B](<Desktop/Gigabyte Technology/G41/G41MT-S2/EF1568975525/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/0458D9F44B>) |
| 8086:27c0 | 1043:8179 | Intel            | NM10/ICH7 Family SATA Controller ... | 935   | ata_pii... | [D5456946BB](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LE/8FE632A39CF5/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D5456946BB>) |
| 197b:2363 | 1458:b000 | JMicron Techn... | JMB363 SATA/IDE Controller           | 692   | ahci       | [FD830A3568](<Desktop/Gigabyte Technology/P35/P35-DS4/7541C3B6BD81/LINUXMINT-21/5.15.0-71-GENERIC/X86_64/FD830A3568>) |
| 1002:439c | 1849:439c | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 683   | pata_at... | [A68D009BD1](<Desktop/ASRock/970M/970M Pro3/6BAC82210FE1/UBUNTU-20.04/5.15.0-72-GENERIC/X86_64/A68D009BD1>) |
| 8086:1c00 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 674   | pata_acpi  | [9A420C42DE](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3/ABA4EBB5D0B8/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-X86_64/X86_64/9A420C42DE>) |
| 8086:1c08 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 674   | pata_acpi  | [9A420C42DE](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3/ABA4EBB5D0B8/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-X86_64/X86_64/9A420C42DE>) |
| 8086:1c08 | 1458:b002 | Intel            | 6 Series/C200 Series Chipset Fami... | 558   | pata_acpi  | [E7B77F5CF0](<Desktop/Gigabyte Technology/Z68/Z68MA-D2H-B3/99DA8E367A7A/OPENMANDRIVA-23.03/5.16.13-DESKTOP-1OMV4003/X86_64/E7B77F5CF0>) |
| 8086:27c0 | 1849:27c0 | Intel            | NM10/ICH7 Family SATA Controller ... | 552   | ata_pii... | [E9A4F752C5](<Desktop/ASRock/G41/G41M-VS3/21B774A42A5B/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/E9A4F752C5>) |
| 8086:3a20 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 542   | pata_acpi  | [C2A0653C52](<Desktop/ASUSTek Computer/P5QLD/P5QLD PRO/0678AB1FB908/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/C2A0653C52>) |
| 8086:3a26 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 542   | pata_acpi  | [C2A0653C52](<Desktop/ASUSTek Computer/P5QLD/P5QLD PRO/0678AB1FB908/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/C2A0653C52>) |
| 10de:03f6 | 1849:03f6 | Nvidia           | MCP61 SATA Controller                | 537   | sata_nv... | [DCF5CD4CA2](<Desktop/ASRock/N68C-GS/N68C-GS FX/CD0566A64BB2/FEDORA-37/6.2.14-200.FC37.X86_64/X86_64/DCF5CD4CA2>) |
| 8086:27df | 1849:27df | Intel            | 82801G (ICH7 Family) IDE Controller  | 532   | ata_pii... | [E9A4F752C5](<Desktop/ASRock/G41/G41M-VS3/21B774A42A5B/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/E9A4F752C5>) |
| 10de:03ec | 1849:03ec | Nvidia           | MCP61 IDE                            | 495   | pata_am... | [1F3953650C](<Desktop/ASRock/N68-VS3/N68-VS3 FX/D968CA13888E/LOC-OS-22/5.10.165-LOC-OS/X86_64/1F3953650C>) |
| 197b:2363 | 1043:824f | JMicron Techn... | JMB363 SATA/IDE Controller           | 421   | ahci       | [D15B9FB438](<Desktop/ASUSTek Computer/P5/P5K/0772711AD395/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/D15B9FB438>) |
| 8086:2926 | 1043:8277 | Intel            | 82801I (ICH9 Family) 2 port SATA ... | 393   | ata_pii... | [D15B9FB438](<Desktop/ASUSTek Computer/P5/P5K/0772711AD395/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/D15B9FB438>) |
| 197b:2368 | 1458:b000 | JMicron Techn... | JMB368 IDE controller                | 381   | pata_jm... | [087681F84E](<Desktop/Gigabyte Technology/GA-880/GA-880GMA-UD2H/D2B9BEC00498/UBUNTU-20.04/5.4.0-148-GENERIC/X86_64/087681F84E>) |
| 8086:27c0 | 1043:2601 | Intel            | NM10/ICH7 Family SATA Controller ... | 352   | ata_pii... | [E0E655F63C](<Desktop/ASUSTek Computer/P5/P5LD2-X-1333/6FD957931C69/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/E0E655F63C>) |
| 8086:1e00 | 1458:b005 | Intel            | 7 Series/C210 Series Chipset Fami... | 341   | pata_acpi  | [6DA1DDCEF5](<Desktop/Gigabyte Technology/Z77/Z77M-D3H/49F546000BB1/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/6DA1DDCEF5>) |
| 8086:1e08 | 1458:b002 | Intel            | 7 Series/C210 Series Chipset Fami... | 341   | pata_acpi  | [6DA1DDCEF5](<Desktop/Gigabyte Technology/Z77/Z77M-D3H/49F546000BB1/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/6DA1DDCEF5>) |
| 1022:780c | 1849:780c | AMD              | FCH IDE Controller                   | 331   | pata_at... | [53C03D6942](<Desktop/ASRock/FM2A88X/FM2A88X Extreme6+/061803342427/FEDORA-37/6.0.11-300.FC37.X86_64/X86_64/53C03D6942>) |
| 8086:1c00 | 1458:b005 | Intel            | 6 Series/C200 Series Chipset Fami... | 311   | pata_acpi  | [3ED55D530A](<Desktop/Gigabyte Technology/H61/H61M-S2PV/DE2D1C5C4F5E/ALT-10.1/5.10.179-STD-DEF-ALT1/X86_64/3ED55D530A>) |
| 10de:03f6 | 1458:b002 | Nvidia           | MCP61 SATA Controller                | 275   | sata_nv... | [D571B75547](<Desktop/Gigabyte Technology/M68/M68MT-S2/333806208DA6/ZORIN-16/5.15.0-71-GENERIC/X86_64/D571B75547>) |
| 1106:0415 | 1043:838f | VIA Technologies | VT6415 PATA IDE Host Controller      | 268   | pata_vi... | [C174FCC2D8](<Desktop/ASUSTek Computer/M5A88-V/M5A88-V EVO/8D4188F1156E/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/C174FCC2D8>) |
| 8086:3b20 | 1043:8383 | Intel            | 5 Series/3400 Series Chipset 4 po... | 264   | pata_acpi  | [8EE190D352](<Desktop/ASUSTek Computer/P7/P7H55/EE327E9417A2/DEBIAN-12/6.1.0-4-AMD64/X86_64/8EE190D352>) |
| 8086:3b26 | 1043:8383 | Intel            | 5 Series/3400 Series Chipset 2 po... | 264   | pata_acpi  | [8EE190D352](<Desktop/ASUSTek Computer/P7/P7H55/EE327E9417A2/DEBIAN-12/6.1.0-4-AMD64/X86_64/8EE190D352>) |
| 8086:2921 | 1043:8277 | Intel            | 82801IB (ICH9) 2 port SATA Contro... | 260   | ata_pii... | [D15B9FB438](<Desktop/ASUSTek Computer/P5/P5K/0772711AD395/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/D15B9FB438>) |
| 8086:3a20 | 1458:b002 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 252   | ata_pii... | [36F4134C6B](<Desktop/Gigabyte Technology/X58/X58A-UD3R/A32313BCFA15/XUBUNTU-22.04/5.15.0-57-GENERIC/X86_64/36F4134C6B>) |
| 8086:3a26 | 1458:b002 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 252   | ata_pii... | [36F4134C6B](<Desktop/Gigabyte Technology/X58/X58A-UD3R/A32313BCFA15/XUBUNTU-22.04/5.15.0-57-GENERIC/X86_64/36F4134C6B>) |
| 8086:1c00 | 1458:b002 | Intel            | 6 Series/C200 Series Chipset Fami... | 251   | ata_pii... | [E7B77F5CF0](<Desktop/Gigabyte Technology/Z68/Z68MA-D2H-B3/99DA8E367A7A/OPENMANDRIVA-23.03/5.16.13-DESKTOP-1OMV4003/X86_64/E7B77F5CF0>) |
| 197b:2363 | 1043:81e4 | JMicron Techn... | JMB363 SATA/IDE Controller           | 246   | ahci       | [D0D3458299](<Desktop/ASUSTek Computer/P5/P5B-Deluxe/8D97A918D165/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/D0D3458299>) |
| 1022:780c | 1458:5002 | AMD              | FCH IDE Controller                   | 243   | pata_at... | [A56CC8AB0E](<Desktop/Gigabyte Technology/GA-A55/GA-A55M-S2HP/77EBC1829450/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/A56CC8AB0E>) |
| 8086:1e00 | 1043:84ca | Intel            | 7 Series/C210 Series Chipset Fami... | 240   | pata_acpi  | [2A4B061B07](<Desktop/ASUSTek Computer/P8H77-M/P8H77-M LE/959B5013F863/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.12-1-DEFAULT/X86_64/2A4B061B07>) |
| 8086:1e08 | 1043:84ca | Intel            | 7 Series/C210 Series Chipset Fami... | 240   | pata_acpi  | [2A4B061B07](<Desktop/ASUSTek Computer/P8H77-M/P8H77-M LE/959B5013F863/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.12-1-DEFAULT/X86_64/2A4B061B07>) |
| 197b:2368 | 1043:827e | JMicron Techn... | JMB368 IDE controller                | 224   | pata_jm... | [C2A0653C52](<Desktop/ASUSTek Computer/P5QLD/P5QLD PRO/0678AB1FB908/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/C2A0653C52>) |
| 1002:439c | 1002:439c | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 218   | pata_at... | [94F2408A63](<Desktop/Others/RS780/RS780-SB700/9EA5FE457EA9/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/94F2408A63>) |
| 8086:27c0 | 8086:27c0 | Intel            | NM10/ICH7 Family SATA Controller ... | 207   | pata_acpi  | [5B46ED614A](<Desktop/Others/Others/Others/87AAFB261E8C/ZORIN-16/5.15.0-69-GENERIC/X86_64/5B46ED614A>) |
| 10de:03ec | 1458:5002 | Nvidia           | MCP61 IDE                            | 200   | pata_am... | [25D436D2CB](<Desktop/Gigabyte Technology/M61/M61SME-S2/4E8023AF4AAC/KUBUNTU-22.04/5.15.0-43-GENERIC/X86_64/25D436D2CB>) |
| 8086:27df | 1458:b001 | Intel            | 82801G (ICH7 Family) IDE Controller  | 198   | ata_pii... | [0244194778](<Desktop/PCF/G31/G31M-ES2L/E42847C66954/OPENMANDRIVA-4.3/5.16.13-DESKTOP-1OMV4003/X86_64/0244194778>) |
| 8086:27df | 8086:27df | Intel            | 82801G (ICH7 Family) IDE Controller  | 189   | pata_acpi  | [5B46ED614A](<Desktop/Others/Others/Others/87AAFB261E8C/ZORIN-16/5.15.0-69-GENERIC/X86_64/5B46ED614A>) |
| 8086:2926 | 1458:b002 | Intel            | 82801I (ICH9 Family) 2 port SATA ... | 188   | ata_pii... | [FD830A3568](<Desktop/Gigabyte Technology/P35/P35-DS4/7541C3B6BD81/LINUXMINT-21/5.15.0-71-GENERIC/X86_64/FD830A3568>) |
| 10de:03f6 | 1043:83a4 | Nvidia           | MCP61 SATA Controller                | 187   | sata_nv... | [0C3F2AF7AD](<Desktop/ASUSTek Computer/M4N68T-M/M4N68T-M LE/7BD4E80F3F5C/LINUXMINT-18.3/4.10.0-38-GENERIC/X86_64/0C3F2AF7AD>) |
| 10de:03ec | 1043:83a4 | Nvidia           | MCP61 IDE                            | 178   | pata_am... | [0C3F2AF7AD](<Desktop/ASUSTek Computer/M4N68T-M/M4N68T-M LE/7BD4E80F3F5C/LINUXMINT-18.3/4.10.0-38-GENERIC/X86_64/0C3F2AF7AD>) |
| 11ab:6101 | 1043:82e0 | Marvell Techn... | 88SE6101/6102 single-port PATA133... | 162   | pata_ma... | [C7D1EAC585](<Desktop/ASUSTek Computer/P5Q/P5Q SE2/3FD6E4DB1ED2/XUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/C7D1EAC585>) |
| 11ab:6101 | 11ab:6101 | Marvell Techn... | 88SE6101/6102 single-port PATA133... | 158   | pata_ma... | [E0F10DF0F9](<Desktop/Intel/DG43GT/DG43GT AAE62768-300/656BCFA44494/ARCO-ROLLING/6.2.12-ZEN1-1-ZEN/X86_64/E0F10DF0F9>) |
| 8086:3b20 | 1458:b002 | Intel            | 5 Series/3400 Series Chipset 4 po... | 158   | pata_acpi  | [CB8885F205](<Desktop/Gigabyte Technology/P55/P55-UD3/86D202F94DE0/UBUNTU-MATE-22.04/5.19.0-40-GENERIC/X86_64/CB8885F205>) |
| 8086:3b26 | 1458:b002 | Intel            | 5 Series/3400 Series Chipset 2 po... | 158   | pata_acpi  | [CB8885F205](<Desktop/Gigabyte Technology/P55/P55-UD3/86D202F94DE0/UBUNTU-MATE-22.04/5.19.0-40-GENERIC/X86_64/CB8885F205>) |
| 8086:29b6 | 1028:0211 | Intel            | 82Q35 Express PT IDER Controller     | 154   | pata_acpi  | [03C6B8486E](<Desktop/Dell/OptiPlex/OptiPlex 755/F8A80185DE25/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/03C6B8486E>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 3918  | nvme       | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 1014  | nvme       | [9430B8C328](<Desktop/Gigabyte Technology/X570/X570 GAMING X/856FFDCD7D13/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.3.1-1-VANILLA/X86_64/9430B8C328>) |
| 144d:a80a | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 977   | nvme       | [4A8C2101E8](<Desktop/ASUSTek Computer/PRIME/PRIME X570-PRO/D1E7CA404339/DEBIAN-11/5.10.0-22-AMD64/X86_64/4A8C2101E8>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 975   | nvme       | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT SSD Controller     | 695   | nvme       | [AD66608CF0](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/E039702D1078/CHIMERAOS-41/6.1.21-1-LTS/X86_64/AD66608CF0>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980              | 616   | nvme       | [DC43E4A7E3](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PRO/1FF7B8E0562A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/DC43E4A7E3>) |
| 15b7:5009 | 15b7:5009 | SanDisk          | WD Blue SN550 NVMe SSD               | 600   | nvme       | [AE040331E6](<Desktop/Gigabyte Technology/B550M/B550M DS3H/BD5F281A2678/LINUXMINT-20.3/5.15.0-56-GENERIC/X86_64/AE040331E6>) |
| 1987:5016 | 1987:5016 | Phison Electr... | E16 PCIe4 NVMe Controller            | 585   | nvme       | [B9D976AE11](<Desktop/ASUSTek Computer/ROG/ROG STRIX X570-E GAMING/8CED5CE61807/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/B9D976AE11>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 549   | nvme       | [E42327B375](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z590-E GAMING WIFI/402936B429DF/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/E42327B375>) |
| 2646:2263 | 2646:2263 | Kingston Tech... | A2000 NVMe SSD                       | 546   | nvme       | [11A0E59867](<Desktop/Gigabyte Technology/B550/B550 GAMING X V2/C76C25FBD854/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/11A0E59867>) |
| 8086:f1a8 | 8086:390d | Intel            | SSD 660P Series                      | 446   | nvme       | [1445A9B10D](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/D8A0958EB618/GETFREEOS-ROLLING/6.3.1-ARCH1-1/X86_64/1445A9B10D>) |
| 15b7:5006 | 15b7:5006 | SanDisk          | WD Black SN750 / PC SN730 NVMe SSD   | 435   | nvme       | [77ECF9C05D](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-K/C1DFDE9A944B/ARCHLABSX-ROLLING/6.2.14-1-CLEAR/X86_64/77ECF9C05D>) |
| 15b7:5002 | 15b7:5002 | SanDisk          | WD Black 2018/SN750 / PC SN720 NV... | 369   | nvme       | [9430B8C328](<Desktop/Gigabyte Technology/X570/X570 GAMING X/856FFDCD7D13/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.3.1-1-VANILLA/X86_64/9430B8C328>) |
| c0a9:2263 | c0a9:2263 | Micron/Crucia... | P1 NVMe PCIe SSD                     | 311   | nvme       | [DBEB828B17](<Desktop/Gigabyte Technology/Z390/Z390 I AORUS PRO WIFI/29952FD8445D/ARCO-ROLLING/6.2.11-ARCH1-1/X86_64/DBEB828B17>) |
| c0a9:540a | c0a9:540a | Micron/Crucia... | P2 NVMe PCIe SSD                     | 311   | nvme       | [5D12A9965B](<Desktop/ASUSTek Computer/PRIME/PRIME Z590-P WIFI/8ACB5F662D94/ARCO-ROLLING/6.1.27-HARDENED1-2-HARDENED/X86_64/5D12A9965B>) |
| 126f:2262 | 126f:2262 | Silicon Motion   | SM2262/SM2262EN SSD Controller       | 252   | nvme       | [28A1F44A1E](<Desktop/ASRockRack/X470/X470D4U2-2T/EEF286979D7B/ALMA-8.7/4.18.0-425.19.2.EL8_7.X86_64/X86_64/28A1F44A1E>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013 E13 NVMe Controller           | 245   | nvme       | [76748DA9CD](<Desktop/MSI/MS-7/MS-7C95/E2E66E37A3EB/FEDORA-38/6.2.12-300.FC38.X86_64/X86_64/76748DA9CD>) |
| 15b7:5011 | 15b7:5011 | SanDisk          | WD PC SN810 / Black SN850 NVMe SSD   | 228   | nvme       | [401DB07B93](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z690-A GAMING WIFI D4/46556BD3958D/DEBIAN-12/6.1.0-7-AMD64/X86_64/401DB07B93>) |
| 10ec:5762 | 10ec:5762 | Realtek Semic... | RTS5763DL NVMe SSD Controller        | 193   | nvme       | [95F75E1344](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z370-G GAMING/B647CF3822F1/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/95F75E1344>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 191   | nvme       | [756E372A11](<Desktop/ASUSTek Computer/Z170/Z170-P/BC9CF352F91A/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/756E372A11>) |
| 15b7:501a | 15b7:501a | SanDisk          | WD Blue SN570 NVMe SSD               | 165   | nvme       | [60C407B4E4](<Desktop/Gigabyte Technology/B550/B550 AORUS ELITE V2/0FF3A56B8BAA/KDE-NEON-22.04/5.19.0-35-GENERIC/X86_64/60C407B4E4>) |
| 2646:500f | 2646:500f | Kingston Tech... | NVMe Controller                      | 160   | nvme       | [1F232288D7](<Desktop/ASRock/Z690/Z690M-ITX-ax/FA892D909FAE/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/1F232288D7>) |
| 10ec:5763 | 10ec:5763 | Realtek Semic... | NVMe Controller                      | 148   | nvme       | [E4C8218911](<Desktop/ASRock/B365/B365M-ITX-ac/1987BE765E33/RED-OS-7.3/5.15.87-1.EL7.3.X86_64/X86_64/E4C8218911>) |
| 8086:f1a5 | 8086:390a | Intel            | SSD 600P Series                      | 145   | nvme       | [64AA7FB49B](<Desktop/Gigabyte Technology/X670/X670 AORUS ELITE AX/930BBBF0F00C/ANTERGOS-ROLLING/6.2.13-ARCH1-1/X86_64/64AA7FB49B>) |
| 8086:f1a6 | 8086:390b | Intel            | SSD Pro 7600p/760p/E 6100p Series    | 127   | nvme       | [E11B4303D3](<Desktop/MSI/MS-7/MS-7C37/8E76E3D563B5/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/E11B4303D3>) |
| 15b7:5003 | 15b7:5003 | SanDisk          | WD Blue SN500 / PC SN520 NVMe SSD    | 125   | nvme       | [5C0B7B180D](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G3 SFF/D03AB5FF3F68/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/5C0B7B180D>) |
| 15b7:5017 | 15b7:5017 | SanDisk          | NVMe Controller                      | 108   | nvme       | [E2CE1C3D6C](<Desktop/ASUSTek Computer/ROG/ROG STRIX B650E-I GAMING WIFI/A4A0572A25ED/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/E2CE1C3D6C>) |
| 2646:5013 | 2646:5013 | Kingston Tech... | Technology Company Non-Volatile m... | 108   | nvme       | [1F232288D7](<Desktop/ASRock/Z690/Z690M-ITX-ax/FA892D909FAE/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/1F232288D7>) |
| 2646:5008 | 2646:5008 | Kingston Tech... | U-SNS8154P3 NVMe SSD                 | 105   | nvme       | [9539CCFD4D](<Desktop/Acer/Aspire/Aspire TC-885/4A920D2C080B/XUBUNTU-20.04/5.4.0-131-GENERIC/X86_64/9539CCFD4D>) |
| 1c5c:174a | 1c5c:174a | SK hynix         | Gold P31/PC711 NVMe Solid State D... | 103   | nvme       | [13E08DA76D](<Desktop/MSI/MS-7/MS-7D43/5645B8FC5581/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/13E08DA76D>) |
| c0a9:540a | c0a9:5021 | Micron/Crucia... | P2 NVMe PCIe SSD                     | 103   | nvme       | [CF7CF903C0](<Desktop/ASRock/B760/B760 Pro RS-D4/22BCEB943676/DEBIAN-12/6.1.0-8-AMD64/X86_64/CF7CF903C0>) |
| 1c5c:1327 | 1c5c:0000 | SK hynix         | BC501 NVMe Solid State Drive         | 96    | nvme       | [9EF46F7F3E](<Desktop/Acer/Predator/Predator PO3-620/877F4FBC5AE0/KDE-NEON-22.04/5.19.0-41-GENERIC/X86_64/9EF46F7F3E>) |
| 15b7:5019 | 15b7:5019 | SanDisk          | Non-Volatile memory controller       | 94    | nvme       | [D817C9A53F](<Desktop/Gigabyte Technology/Z170X-Gaming/Z170X-Gaming 7/7044218255D7/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/D817C9A53F>) |
| c0a9:5403 | c0a9:2100 | Micron/Crucia... | NVMe Storage Controller              | 94    | nvme       | [E1D1BDEF81](<Desktop/Gigabyte Technology/X99-Gaming/X99-Gaming 5/FD256B0D0F49/MANJARO-22.1.0/6.1.25-1-MANJARO/X86_64/E1D1BDEF81>) |
| 1344:5405 | 1344:0100 | Micron Techno... | NVMe Storage Controller              | 87    | nvme       | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| c0a9:5407 | c0a9:0100 | Micron/Crucia... | P5 Plus NVMe PCIe SSD                | 83    | nvme       | [47388F4553](<Desktop/Gigabyte Technology/X570S/X570S AORUS PRO AX/82196083E848/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/47388F4553>) |
| 2646:500e | 2646:500e | Kingston Tech... | SNVS2000G [NV1 NVMe PCIe SSD 2TB]    | 82    | nvme       | [7673380766](<Desktop/Gigabyte Technology/Z690/Z690 AERO G/65E936DD740C/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/7673380766>) |
| 1987:5018 | 1987:5018 | Phison Electr... | E18 PCIe4 NVMe Controller            | 81    | nvme       | [FFAB85A31A](<Desktop/ASUSTek Computer/ROG/ROG STRIX B450-F GAMING/6760883EC8F1/MANJARO/5.15.108-1-MANJARO/X86_64/FFAB85A31A>) |
| 1e4b:1202 | 1e4b:1202 | MAXIO Technol... | NVMe SSD Controller MAP1202          | 80    | nvme       | [B661127BB7](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/D65A67B00DDE/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.12-1-DEFAULT/X86_64/B661127BB7>) |
| 1987:5007 | 1987:5007 | Phison Electr... | E7 NVMe Controller                   | 79    | nvme       | [912A7F830B](<Desktop/ASRock/X370/X370 Killer SLI/B9A26CBD16BF/XUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/912A7F830B>) |
| 1179:011a | 1179:0001 | Toshiba Ameri... | XG6 NVMe SSD Controller              | 73    | nvme       | [9F81660D12](<Desktop/MSI/MS-7/MS-7B18/27D60A9E5108/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/9F81660D12>) |
| 1987:5008 | 1987:5008 | Phison Electr... | NVMe Storage Controller              | 70    | nvme       | [E6F49BBE8A](<Desktop/Dell/Inspiron/Inspiron 5675/3F0EB1245B68/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/E6F49BBE8A>) |
| 2646:2262 | 2646:2262 | Kingston Tech... | KC2000 NVMe SSD                      | 70    | nvme       | [961EC7671C](<Desktop/Gigabyte Technology/B450/B450 AORUS ELITE/348836DC6639/FEDORA-37/6.2.13-200.FC37.X86_64/X86_64/961EC7671C>) |
| 10ec:5765 | 10ec:5765 | Realtek Semic... | NVMe Controller                      | 67    | nvme       | [DC317AB270](<Desktop/ASRock/B450M/B450M Steel Legend/405CEAE381D2/ARCH-ROLLING/6.2.10-X64V1-XANMOD1-1/X86_64/DC317AB270>) |
| 1179:0116 | 1179:0001 | Toshiba Ameri... | XG5 NVMe SSD Controller              | 67    | nvme       | [ED92305DA6](<Desktop/Alienware/Aurora/Aurora R7/BA70207ED366/KUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/ED92305DA6>) |
| 1bb1:5016 | 1bb1:5016 | Seagate Techn... | FireCuda 520 SSD                     | 67    | nvme       | [B979325EEA](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-I GAMING/EDB7A2296562/ROSA-12.4/6.3.1.XM1-1.KLP-XANMOD-ROSA2021.1-X86_64/X86_64/B979325EEA>) |
| 15b7:501e | 15b7:501e | SanDisk          | Non-Volatile memory controller       | 64    | nvme       | [B668E7BFAC](<Desktop/Gigabyte Technology/B550/B550 UD AC/CB49E900708B/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/B668E7BFAC>) |
| c0a9:5412 | c0a9:0100 | Micron/Crucia... | NVMe Storage Controller              | 63    | nvme       | [DB1AD69341](<Desktop/MSI/MS-7/MS-7D17/0B3A86521786/REBORNOS-ROLLING/6.3.1-ARCH1-1/X86_64/DB1AD69341>) |
| 15b7:5030 | 15b7:5030 | Sandisk          | NVMe Controller                      | 61    | nvme       | [F115308631](<Desktop/Gigabyte Technology/X670E/X670E AORUS MASTER/3BF5FA76FD15/LINUXMINT-21.1/6.2.13-060213-GENERIC/X86_64/F115308631>) |
| 1e0f:0001 | 1e0f:0001 | KIOXIA           | NVMe SSD Controller BG4              | 61    | nvme       | [A062CB2AB6](<Desktop/ASUSTek Computer/M5A97/M5A97 PLUS/FD81EB82FF97/KUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/A062CB2AB6>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:467f | 1043:8694 | Intel            | Volume Management Device NVMe RAI... | 218   | vmd        | [401DB07B93](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z690-A GAMING WIFI D4/46556BD3958D/DEBIAN-12/6.1.0-7-AMD64/X86_64/401DB07B93>) |
| 8086:2822 | 1043:8694 | Intel            | SATA Controller [RAID mode]          | 213   | ahci       | [536E6E7CC9](<Desktop/ASUSTek Computer/STRIX/STRIX B250I GAMING/BB9A16765525/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/536E6E7CC9>) |
| 8086:2822 | 1458:b005 | Intel            | SATA Controller [RAID mode]          | 169   | ahci       | [A62E386EAE](<Desktop/Gigabyte Technology/Z97/Z97-D3H/B918E5FAC02C/MAGEIA-8/5.15.106-DESKTOP-2.MGA8/X86_64/A62E386EAE>) |
| 8086:2822 | 1028:05a4 | Intel            | SATA Controller [RAID mode]          | 136   | ahci       | [86CB104CEB](<Desktop/Dell/OptiPlex/OptiPlex 9020/562569DFC222/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/86CB104CEB>) |
| 8086:2822 | 1028:0420 | Intel            | SATA Controller [RAID mode]          | 133   | ahci       | [2499C633A5](<Desktop/Dell/OptiPlex/OptiPlex 780/9F4EC98D5072/MANJARO/6.0.6-1-MANJARO/X86_64/2499C633A5>) |
| 1106:3249 | 1106:3249 | VIA Technologies | VT6421 IDE/SATA Controller           | 92    | sata_via   | [60A7DC4C2E](<Desktop/Gigabyte Technology/P43/P43-ES3G/B3F2FDB13FD5/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/60A7DC4C2E>) |
| 8086:2822 | 1028:047e | Intel            | SATA Controller [RAID mode]          | 88    | ahci       | [EC04C034D3](<Desktop/Dell/OptiPlex/OptiPlex 990/D0B1671560CE/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/EC04C034D3>) |
| 8086:2822 | 103c:1309 | Intel            | SATA Controller [RAID mode]          | 74    | ahci       | [69C613B55F](<Desktop/Hewlett-Packard/Z400/Z400 Workstation/E7ECFF068003/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/69C613B55F>) |
| 1022:7916 | 1022:7901 | AMD              | RS690 PCI to PCI Bridge (PCI Expr... | 68    | ahci       | [8234CD55A8](<Desktop/ASUSTek Computer/PRIME/PRIME X570-P/B7CE4837A17F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/8234CD55A8>) |
| 8086:2822 | 103c:2a6f | Intel            | SATA Controller [RAID mode]          | 67    | ahci       | [FF6049B22E](<Desktop/Hewlett-Packard/FQ515AA-ABA/FQ515AA-ABA a6620f/F964AF1529FA/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/FF6049B22E>) |
| 8086:2822 | 1028:052c | Intel            | SATA Controller [RAID mode]          | 64    | ahci       | [F2B702B631](<Desktop/Dell/OptiPlex/OptiPlex 9010/E884F88EE11B/LINUXMINT-18/4.4.0-140-GENERIC/X86_64/F2B702B631>) |
| 1022:43bd | 1b21:1062 | AMD              | FCH RAID Controller                  | 58    | rcraid     | [DCBCF69A04](<Desktop/ASUSTek Computer/TUF/TUF B450M-PLUS GAMING/36D18B1D666E/ZORIN-16/5.15.0-67-GENERIC/X86_64/DCBCF69A04>) |
| 8086:2822 | 103c:2a9c | Intel            | SATA Controller [RAID mode]          | 58    | ahci       | [4ACB37F728](<Desktop/Hewlett-Packard/PPPPP-CCC#MMMMMMMM/PPPPP-CCC#MMMMMMMM/52B2452D254D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/4ACB37F728>) |
| 1095:3114 | 1095:7114 | Silicon Image    | SiI 3114 [SATALink/SATARaid] Seri... | 56    | sata_sil   | [BBAC197D5D](<Desktop/MSI/MS/MS-7721/B27F20E82284/XUBUNTU-22.04/6.2.10-060210-GENERIC/X86_64/BBAC197D5D>) |
| 8086:2822 | 1043:8534 | Intel            | SATA Controller [RAID mode]          | 53    | ahci       | [C47205C3CB](<Desktop/ASUSTek Computer/All/All Series/0A37A7D15166/STEAMOS-4/6.1.21-VALVE1-1-NEPTUNE-61/X86_64/C47205C3CB>) |
| 8086:2822 | 103c:130a | Intel            | SATA Controller [RAID mode]          | 50    | ahci       | [49C56C77AF](<Desktop/Hewlett-Packard/Z600/Z600 Workstation/C8C77CC6EAAE/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/49C56C77AF>) |
| 8086:2826 | 103c:1589 | Intel            | C600/X79 series chipset SATA RAID... | 49    | ahci       | [BE15D33D32](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/EE9F1FE423DF/DEBIAN-12/6.1.0-8-AMD64/X86_64/BE15D33D32>) |
| 8086:2822 | 1028:06b9 | Intel            | SATA Controller [RAID mode]          | 47    | ahci       | [08DF3C35EE](<Desktop/Dell/OptiPlex/OptiPlex 7040/74B9A8608B3A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/08DF3C35EE>) |
| 8086:2822 | 1028:0293 | Intel            | SATA Controller [RAID mode]          | 44    | ahci       | [6089DFDEAB](<Desktop/Dell/Precision/Precision WorkStation T3500/D5036B82E444/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6089DFDEAB>) |
| 8086:2822 | 1043:872f | Intel            | SATA Controller [RAID mode]          | 43    | ahci       | [25C46B6F70](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-A/341FBFD9B58B/LINUXMINT-21.1/5.15.0-60-GENERIC/X86_64/25C46B6F70>) |
| 8086:2822 | 103c:130b | Intel            | SATA Controller [RAID mode]          | 40    | ahci       | [C9E99B3F8C](<Desktop/Hewlett-Packard/Z800/Z800 Workstation/5D76221FDFDA/FEDORA-37/6.2.11-200.FC37.X86_64/X86_64/C9E99B3F8C>) |
| 8086:2822 | 1458:b000 | Intel            | SATA Controller [RAID mode]          | 38    | ahci       | [3B263C29FC](<Desktop/Gigabyte Technology/EX58/EX58-EXTREME/1C0A90BFBBBA/FEDORA-37/6.2.12-200.FC37.X86_64/X86_64/3B263C29FC>) |
| 1095:3132 | 1043:819f | Silicon Image    | SiI 3132 Serial ATA Raid II Contr... | 37    | sata_sil24 | [B324AFC6F8](<Desktop/ASUSTek Computer/A8R32-MVP/A8R32-MVP Deluxe/63540AA3FB2C/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/B324AFC6F8>) |
| 1095:3512 | 1095:6512 | Silicon Image    | SiI 3512 [SATALink/SATARaid] Seri... | 36    | sata_sil   | [4B705B9DCA](<Desktop/ASUSTek Computer/CROSSHAIR/CROSSHAIR II FORMULA/4ADEED4021BD/UBUNTU-20.04/5.4.0-144-GENERIC/X86_64/4B705B9DCA>) |
| 8086:2822 | 1028:07a3 | Intel            | SATA Controller [RAID mode]          | 35    | ahci       | [25BC3AA225](<Desktop/Dell/OptiPlex/OptiPlex 3050/ACCFBCE5B4BD/ZORIN-16/5.15.0-69-GENERIC/X86_64/25BC3AA225>) |
| 8086:2827 | 103c:212b | Intel            | C610/X99 series chipset sSATA Con... | 34    | ahci       | [D71B834A1C](<Desktop/Hewlett-Packard/Z440/Z440 Workstation/4440A0D853F2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/D71B834A1C>) |
| 8086:2822 | 1028:05a6 | Intel            | SATA Controller [RAID mode]          | 33    | ahci       | [890EA0FD78](<Desktop/Dell/Precision/Precision T1700/A437DC3CA2DD/LINUXMINT-21.1/5.15.0-70-GENERIC/X86_64/890EA0FD78>) |
| 8086:2822 | 1028:02da | Intel            | SATA Controller [RAID mode]          | 32    | ahci       | [926D18B722](<Desktop/Dell/OptiPlex/OptiPlex 980/2A37373EE576/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/926D18B722>) |
| 8086:2826 | 103c:158a | Intel            | C600/X79 series chipset SATA RAID... | 32    | ahci       | [FB7AEF7883](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/9F156C69101A/XUBUNTU-20.04/5.15.0-71-LOWLATENCY/X86_64/FB7AEF7883>) |
| 8086:2826 | 103c:212b | Intel            | C600/X79 series chipset SATA RAID... | 32    | ahci       | [D71B834A1C](<Desktop/Hewlett-Packard/Z440/Z440 Workstation/4440A0D853F2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/D71B834A1C>) |
| 1095:3132 | 1095:7132 | Silicon Image    | SiI 3132 Serial ATA Raid II Contr... | 31    | sata_sil24 | [2409DC15B4](<Desktop/ASUSTek Computer/H110/H110M-R/50398B77DB29/LINUXMINT-20.3/5.15.0-60-GENERIC/X86_64/2409DC15B4>) |
| 8086:2822 | 103c:1905 | Intel            | SATA Controller [RAID mode]          | 29    | ahci       | [9E047F751D](<Desktop/Hewlett-Packard/Z230/Z230 Tower Workstation/23A703662176/UBUNTU-20.04/5.15.0-69-GENERIC/X86_64/9E047F751D>) |
| 8086:2826 | 103c:158b | Intel            | C600/X79 series chipset SATA RAID... | 28    | ahci       | [EE0297B0BA](<Desktop/Hewlett-Packard/Z820/Z820 Workstation/B02938969DD1/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/EE0297B0BA>) |
| 8086:467f | 8086:0000 | Intel            | Volume Management Device NVMe RAI... | 28    | vmd        | [1F232288D7](<Desktop/ASRock/Z690/Z690M-ITX-ax/FA892D909FAE/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/1F232288D7>) |
| 8086:2822 | 1043:84ca | Intel            | SATA Controller [RAID mode]          | 25    | ahci       | [B6A0D45508](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LE/07981250007C/DEBIAN-11/5.10.0-21-AMD64/X86_64/B6A0D45508>) |
| 1095:0680 | 1095:3680 | Silicon Image    | PCI0680 Ultra ATA-133 Host Contro... | 24    | pata_si... | [E877A9F9E3](<Desktop/ASUSTek Computer/M5A97/M5A97 R2.0/2B67B44F9B65/MANJARO-22.0.0/5.16.20-2-MANJARO/X86_64/E877A9F9E3>) |
| 8086:2822 | 1028:07a1 | Intel            | SATA Controller [RAID mode]          | 24    | ahci       | [11E8FB1ECD](<Desktop/Dell/OptiPlex/OptiPlex 7050/460F8DE765A3/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/11E8FB1ECD>) |
| 8086:2822 | 1028:085c | Intel            | SATA Controller [RAID mode]          | 24    | ahci       | [1945CCD76D](<Desktop/Dell/OptiPlex/OptiPlex 3060/0AA7CB57BEDA/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/1945CCD76D>) |
| 1002:4392 | 103c:2a92 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 23    | ahci       | [F92A9CC141](<Desktop/Hewlett-Packard/AY614AA-ABA/AY614AA-ABA p6347c/F102B32DA51F/LINUXMINT-21.1/5.15.0-70-GENERIC/X86_64/F92A9CC141>) |
| 8086:06d6 | 1043:8694 | Intel            | Comet Lake PCH-H RAID                | 23    | ahci       | [9088AE517A](<Desktop/ASUSTek Computer/PRIME/PRIME Z490-A/67D18DF81868/FEDORA-38/6.2.12-300.FC38.X86_64/X86_64/9088AE517A>) |
| 8086:201d | 1028:0738 | Intel            | Volume Management Device NVMe RAI... | 23    | vmd        | [EE53C6F627](<Desktop/Dell/Precision/Precision 5820 Tower/BA6A02EAEA31/UBUNTU-20.04/5.14.0-1024-OEM/X86_64/EE53C6F627>) |
| 8086:2822 | 103c:8767 | Intel            | SATA Controller [RAID mode]          | 23    | ahci       | [1E76ECBAA7](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop TP01-1xxx/82CCFF03A0EE/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/1E76ECBAA7>) |
| 8086:2826 | 1028:0617 | Intel            | C600/X79 series chipset SATA RAID... | 23    | ahci       | [33517B7BFE](<Desktop/Dell/Precision/Precision Tower 5810/4630C280B407/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/33517B7BFE>) |
| 8086:2826 | 1028:0738 | Intel            | C600/X79 series chipset SATA RAID... | 23    | ahci       | [EE53C6F627](<Desktop/Dell/Precision/Precision 5820 Tower/BA6A02EAEA31/UBUNTU-20.04/5.14.0-1024-OEM/X86_64/EE53C6F627>) |
| 8086:2822 | 1043:844d | Intel            | SATA Controller [RAID mode]          | 22    | ahci       | [C033C311F3](<Desktop/ASUSTek Computer/P8P67/P8P67 EVO/77FFBC270AFE/ARCH-ROLLING/6.0.8-ARCH1-1/X86_64/C033C311F3>) |
| 8086:2822 | 1849:a282 | Intel            | SATA Controller [RAID mode]          | 21    | ahci       | [E4C8218911](<Desktop/ASRock/B365/B365M-ITX-ac/1987BE765E33/RED-OS-7.3/5.15.87-1.EL7.3.X86_64/X86_64/E4C8218911>) |
| 8086:a386 | 1043:8694 | Intel            | 300 Series Chipset Family SATA RA... | 21    | ahci       | [B2616EA409](<Desktop/ASUSTek Computer/TUF/TUF Gaming B460-PLUS/84A50B630509/NOBARA-37/6.2.11-202.FSYNC.FC37.X86_64/X86_64/B2616EA409>) |
| 103c:323a | 103c:3245 | Hewlett-Packard  | Smart Array G6 controllers           | 20    | hpsa       | [58113862EE](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML350 G6/9AF898FA883B/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/58113862EE>) |
| 11ab:6440 | 1043:82e4 | Marvell Techn... | 88SE6440 SAS/SATA PCIe controller    | 20    | mvsas      | [DC155CE308](<Desktop/ASUSTek Computer/P6T/P6T DELUXE/E5115F4DBF6F/LINUXMINT-20.3/5.15.0-69-GENERIC/X86_64/DC155CE308>) |
| 1000:0073 | 1028:1f78 | LSI Logic / S... | MegaRAID SAS 2008 [Falcon]           | 19    | megarai... | [6316886F98](<Desktop/Dell/Precision/Precision T7600/571CD65BB927/LINUXMINT-21.1/5.15.0-70-GENERIC/X86_64/6316886F98>) |

### Storage/sas (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1d6b | 103c:1589 | Intel            | C602 chipset 4-Port SATA Storage ... | 75    | isci       | [BE15D33D32](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/EE9F1FE423DF/DEBIAN-12/6.1.0-8-AMD64/X86_64/BE15D33D32>) |
| 1000:0086 | 103c:158b | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 54    | mpt3sas    | [EE0297B0BA](<Desktop/Hewlett-Packard/Z820/Z820 Workstation/B02938969DD1/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/EE0297B0BA>) |
| 8086:1d6b | 103c:158a | Intel            | C602 chipset 4-Port SATA Storage ... | 48    | isci       | [FB7AEF7883](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/9F156C69101A/XUBUNTU-20.04/5.15.0-71-LOWLATENCY/X86_64/FB7AEF7883>) |
| 1000:0072 | 1000:3020 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 47    | mpt3sas    | [59C5A88B80](<Desktop/ASUSTek Computer/M4A79/M4A79 Deluxe/119D444B2C57/LINUXMINT-21.1/5.19.0-38-GENERIC/X86_64/59C5A88B80>) |
| 8086:1d6b | 1028:0497 | Intel            | C602 chipset 4-Port SATA Storage ... | 38    | isci       | [04F68362D5](<Desktop/Dell/Precision/Precision T3600/801970AB4520/DEBIAN-10/4.19.0-23-AMD64/X86_64/04F68362D5>) |
| 8086:1d6b | 103c:158b | Intel            | C602 chipset 4-Port SATA Storage ... | 36    | isci       | [EE0297B0BA](<Desktop/Hewlett-Packard/Z820/Z820 Workstation/B02938969DD1/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/EE0297B0BA>) |
| 8086:1d6b | 17aa:1026 | Intel            | C602 chipset 4-Port SATA Storage ... | 23    | isci       | [EA3855CCA5](<Desktop/Lenovo/ThinkStation/ThinkStation S30 0568E8G/80EBD2E9BDCA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/EA3855CCA5>) |
| 1000:0072 | 1028:1f1c | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 21    | mpt3sas    | [24B14FA9BB](<Desktop/Gigabyte Technology/H77/H77N-WIFI/4173F9C1605A/CENTOS-8/4.18.0-240.10.1.EL8_3.X86_64/X86_64/24B14FA9BB>) |
| 1000:0097 | 1028:0619 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 17    | mpt3sas    | [F76BC64EE4](<Desktop/Dell/Precision/Precision Tower 7910/96D37272A606/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/F76BC64EE4>) |
| 1000:0087 | 1028:05a1 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 15    | mpt3sas    | [7C5F606C7D](<Desktop/Dell/Precision/Precision T7610/48D158544983/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/7C5F606C7D>) |
| 1000:0087 | 1000:3020 | LSI Logic / S... | SAS2308 PCI-Express Fusion-MPT SAS-2 | 14    | mpt3sas    | [113406ACD8](<Desktop/MSI/MS-7/MS-7D25/EEF9454960EB/ROCKY-9.1/5.14.0-162.18.1.EL9_1.X86_64/X86_64/113406ACD8>) |
| 8086:1d6b | 1734:11b6 | Intel            | C602 chipset 4-Port SATA Storage ... | 11    | isci       | [AD24DC05A0](<Desktop/Fujitsu/CELSIUS/CELSIUS M720/E4A703C9979C/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/AD24DC05A0>) |
| 1000:0086 | 15d9:0691 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 9     | mpt3sas    | [90AAABB4B2](<Desktop/ASRock/B450/B450 Pro4 R2.0/7D419FDECA8F/UBUNTU-20.04/5.4.0-128-GENERIC/X86_64/90AAABB4B2>) |
| 1000:0070 | 1000:3010 | LSI Logic / S... | SAS2004 PCI-Express Fusion-MPT SA... | 8     | mpt3sas    | [A4C5E58EEC](<Desktop/Dell/Precision/Precision WorkStation T3500/2B5473C76A7D/DEBIAN-11/5.10.0-20-AMD64/X86_64/A4C5E58EEC>) |
| 1000:0087 | 1000:3060 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 8     | mpt3sas    | [15CC4335C7](<Desktop/Lenovo/ThinkStation/ThinkStation P410 30B3003SUS/53840422D466/MANJARO-22.1.0/6.1.23-1-MANJARO/X86_64/15CC4335C7>) |
| 8086:1d6b | 15d9:062c | Intel            | C602 chipset 4-Port SATA Storage ... | 8     | isci       | [F3B00D12F2](<Desktop/Novatte/M/M20/D798A35ED81C/UBUNTU-20.04/5.15.0-60-GENERIC/X86_64/F3B00D12F2>) |
| 8086:1d6b | 1849:1d6b | Intel            | C602 chipset 4-Port SATA Storage ... | 8     | isci       | [2D1D53F993](<Desktop/ASRockRack/EPC602/EPC602D8A/DDAB8EFC060B/UBUNTU-22.10/5.19.0-28-GENERIC/X86_64/2D1D53F993>) |
| 1000:0087 | 1000:3030 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 7     | mpt3sas    | [4D48B829CA](<Desktop/ASRock/X570/X570 Taichi/ABF4E532BDC9/GENTOO-2.13/5.15.91-GENTOO/X86_64/4D48B829CA>) |
| 1000:0097 | 15d9:0808 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 7     | mpt3sas    | [3AA5AEBAEE](<Desktop/Supermicro/SSG-6048/SSG-6048R-E1CR36N/222ACB66D393/DEBIAN-11/5.15.83-1-PVE/X86_64/3AA5AEBAEE>) |
| 8086:1d6b | 15d9:0628 | Intel            | C602 chipset 4-Port SATA Storage ... | 7     | isci       | [977BE97551](<Desktop/Supermicro/X9/X9DR3-F/B968461DBB87/DEBIAN-11/5.15.83-1-PVE/X86_64/977BE97551>) |
| 8086:1d6b | 17aa:1028 | Intel            | C602 chipset 4-Port SATA Storage ... | 7     | isci       | [0EB86A808A](<Desktop/Lenovo/ThinkStation/ThinkStation C30 1097A34/71F87D06198F/BLACKPANTHER-OS-18.1/5.15.85-DESKTOP-1BP/X86_64/0EB86A808A>) |
| 1000:0064 | 1000:30c0 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 6     | mpt3sas    | [AFDE7DB629](<Desktop/Supermicro/PIO-648/PIO-648R-E1CR36L+-ST031/EA518C59FF9D/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/AFDE7DB629>) |
| 1000:0097 | 1000:30a0 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 6     | mpt3sas    | [C0EA09EF3C](<Desktop/Gigabyte Technology/X570/X570 AORUS MASTER/523585CFC834/FEDORA-37/6.1.5-200.FC37.X86_64/X86_64/C0EA09EF3C>) |
| 8086:1d6b | 1028:0496 | Intel            | C602 chipset 4-Port SATA Storage ... | 6     | isci       | [390FBAACA7](<Desktop/Dell/Precision/Precision T5600/BD138815AF95/UBUNTU-22.04/5.15.0-25-GENERIC/X86_64/390FBAACA7>) |
| 8086:1d6b | 15d9:0626 | Intel            | C602 chipset 4-Port SATA Storage ... | 6     | isci       | [701907636A](<Desktop/Supermicro/PIO-617/PIO-617R-TLN4F+-ST031/842942F67EF1/DEBIAN-11/5.10.164.2/X86_64/701907636A>) |
| 1000:0072 | 1000:3060 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 5     | mpt3sas    | [4B5EC389D9](<Desktop/Gigabyte Technology/Z390/Z390 GAMING X/32C49C4A7667/LINUXMINT-20.3/5.4.0-131-GENERIC/X86_64/4B5EC389D9>) |
| 1000:0072 | 1000:30f0 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 5     | mpt3sas    | [EA1D17F234](<Desktop/ASUSTek Computer/All/All Series/1048CC944682/UBUNTU-18.04/5.4.0-113-GENERIC/X86_64/EA1D17F234>) |
| 1000:0072 | 1028:1f1d | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 5     | mpt3sas    | [978D27CA8B](<Desktop/Gigabyte Technology/AB350M-Gaming/AB350M-Gaming 3/CD516A852BB5/UBUNTU-22.04/5.15.0-40-GENERIC/X86_64/978D27CA8B>) |
| 1000:0097 | 1000:30e0 | LSI Logic / S... | SAS3008 PCI-Express Fusion-MPT SAS-3 | 5     | mpt3sas    | [F33074A4C8](<Desktop/Gigabyte Technology/Z790/Z790 AERO G/2560D41F5C57/ANTIX-21/6.2.9-1-LIQUORIX-AMD64/X86_64/F33074A4C8>) |
| 1000:00ac | 1000:3000 | Broadcom / LSI   | SAS3416 Fusion-MPT Tri-Mode I/O C... | 5     | mpt3sas    | [69DD85D8CF](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-E GAMING/F0F14334E1E4/DEBIAN-11/6.1.10-1-PVE/X86_64/69DD85D8CF>) |
| 8086:1d68 | 1028:0495 | Intel            | C606 chipset Dual 4-Port SATA/SAS... | 5     | isci       | [F97F117502](<Desktop/Dell/Precision/Precision T7600/2A480A2DFD1D/ENDLESS-4.0.14/5.11.0-35-GENERIC/X86_64/F97F117502>) |
| 1000:0064 | 1000:3030 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 4     | mpt2sas    | [6DF318E1D4](<Desktop/Dell/Precision/Precision T3610/728695CB21CE/UBUNTU-22.04/6.0.0-060000-GENERIC/X86_64/6DF318E1D4>) |
| 1000:0064 | 1000:30d0 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 4     | mpt3sas    | [CC1233B9B9](<Desktop/Dell/Precision/Precision T5610/B67B29961B2E/MANJARO-22.1.0/5.15.106-1-MANJARO/X86_64/CC1233B9B9>) |
| 1000:0072 | 1000:3040 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 4     | mpt3sas    | [F177EA06E6](<Desktop/Gigabyte Technology/Z97X-Gaming/Z97X-Gaming 3/796C2B08329D/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/F177EA06E6>) |
| 1000:0072 | 1000:3080 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 4     | mpt2sas    | [36C6A137FB](<Desktop/Dell/Precision/Precision Tower 3420/75DAF1532C65/CENTOS-7/3.10.0-1160.45.1.EL7.X86_64/X86_64/36C6A137FB>) |
| 8086:1d60 | 1028:0497 | Intel            | C608 chipset Dual 4-Port SATA/SAS... | 4     | isci       | [21BDE061E9](<Desktop/Dell/Precision/Precision T3600/8BFF60BD0536/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/21BDE061E9>) |
| 1000:0087 | 1000:3040 | LSI Logic / S... | SAS2308 PCI-Express Fusion-MPT SAS-2 | 3     | mpt3sas    | [DF59296148](<Desktop/MSI/MS-7/MS-7D53/97B840A65E4D/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/DF59296148>) |
| 1000:0097 | 1734:1214 | LSI Logic / S... | SAS3008 PCI-Express Fusion-MPT SAS-3 | 3     | mpt3sas    | [8FC8FEE94A](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PLUS/7FCC2AD36BDE/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/8FC8FEE94A>) |
| 1000:0097 | 1849:0097 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 3     | mpt3sas    | [012C10AE8C](<Desktop/ASRockRack/D1541/D1541D4U-2T8R/A7AA4EDAE527/DEBIAN-11/5.15.102-1-PVE/X86_64/012C10AE8C>) |
| 19e5:a230 |           | Huawei Techno... | HiSilicon SAS 3.0 HBA                | 3     | hisi_sa... | [2A8B1A08BC](<Desktop/Others/Kunpeng/Kunpeng Desktop Board D920S10/CA52484FDDC1/REDFLAG-11.0/4.19.0-16-ARM64/AARCH64/2A8B1A08BC>) |
| 8086:1d60 | 1028:0496 | Intel            | C608 chipset Dual 4-Port SATA/SAS... | 3     | isci       | [E48D83D96D](<Desktop/Dell/Precision/Precision T5600/757ABB1D6B63/LMDE-5/5.10.0-21-AMD64/X86_64/E48D83D96D>) |
| 8086:1d69 | 1734:11b6 | Intel            | C604/X79 series chipset 4-Port SA... | 3     | isci       | [64B9978ED0](<Desktop/Fujitsu/CELSIUS/CELSIUS M720/D4C7881F195A/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/64B9978ED0>) |
| 8086:1d69 | 17aa:1026 | Intel            | C604/X79 series chipset 4-Port SA... | 3     | isci       | [62BF350F96](<Desktop/Lenovo/ThinkStation/ThinkStation S30 4351FE5/84050DE81BBB/OPENMANDRIVA-4.50/5.12.4-DESKTOP-1OMV4050/X86_64/62BF350F96>) |
| 8086:1d6b | 1028:0495 | Intel            | C602 chipset 4-Port SATA Storage ... | 3     | isci       | [AB3DAD5A31](<Desktop/Dell/Precision/Precision T7600/1CC39A45F802/UBUNTU-22.04/5.15.0-52-GENERIC/X86_64/AB3DAD5A31>) |
| 8086:1d6b | 15d9:0709 | Intel            | C602 chipset 4-Port SATA Storage ... | 3     | isci       | [3FC1EF2B58](<Desktop/Supermicro/X9/X9DA7-E/023C52794E0C/SLACKWARE-14.2/5.10.28-UNRAID/X86_64/3FC1EF2B58>) |
| 8086:1d6b | 17aa:1027 | Intel            | C602 chipset 4-Port SATA Storage ... | 3     | isci       | [7730EB04FA](<Desktop/Lenovo/ThinkStation/ThinkStation D30 42234T7/7EB1100D92AD/DEBIAN-11/5.15.104-1-PVE/X86_64/7730EB04FA>) |
| 1000:0072 | 1000:3050 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mpt3sas    | [4BCB73E1BF](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/316FF7FEEF2B/FEDORA-36/5.17.5-300.FC36.X86_64/X86_64/4BCB73E1BF>) |
| 1000:0072 | 1000:30b0 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mpt3sas    | [33A89C4C5A](<Desktop/Fujitsu/D3598/D3598-B1/21A35A2A8BEF/UBUNTU-20.04/5.4.0-88-GENERIC/X86_64/33A89C4C5A>) |
| 1000:0072 | 1014:03cb | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mpt3sas    | [360866BCC5](<Desktop/MSI/MS-7/MS-7C37/AB7B20FD3E5D/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/360866BCC5>) |
| 1000:0072 | 15d9:0400 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mpt3sas    | [74A68EBA33](<Desktop/NetGear/ReadyDATA/ReadyDATA 5200/2E63D7AE698C/DEBIAN-11/5.15.79+TRUENAS/X86_64/74A68EBA33>) |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1000:0058 | 103c:130b | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 45    | mptsas     | [C9E99B3F8C](<Desktop/Hewlett-Packard/Z800/Z800 Workstation/5D76221FDFDA/FEDORA-37/6.2.11-200.FC37.X86_64/X86_64/C9E99B3F8C>) |
| 1000:0058 | 1028:021d | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 38    | mptsas     | [7AEF52516B](<Desktop/Dell/Precision/Precision WorkStation T7500/5BA9A5976E40/KUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/7AEF52516B>) |
| 1000:0056 | 1000:3090 | LSI Logic / S... | SAS1064ET PCI-Express Fusion-MPT SAS | 20    | mptsas     | [846F31DE3E](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550M-PLUS/EE8294F715D5/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/846F31DE3E>) |
| 1000:0058 | 1028:1f0e | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 20    | mptsas     | [7730EB04FA](<Desktop/Lenovo/ThinkStation/ThinkStation D30 42234T7/7EB1100D92AD/DEBIAN-11/5.15.104-1-PVE/X86_64/7730EB04FA>) |
| 1000:0054 | 103c:0a98 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 16    | mptsas     | [DB84CA1038](<Desktop/Hewlett-Packard/xw8600/xw8600 Workstation/435DD46A15AB/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/DB84CA1038>) |
| 9004:5078 | 9004:7850 | Adaptec          | AIC-7850T/7856T [AVA-2902/4/6 / A... | 14    | aic7xxx    | [FA5C9707DE](<Desktop/Lenovo/ThinkCentre/ThinkCentre M58 7637AD4/8B9544628B05/LINUXMINT-21/5.15.0-56-GENERIC/X86_64/FA5C9707DE>) |
| 9004:8178 | 9004:7881 | Adaptec          | AIC-7870P/7881U [AHA-2940U/UW/D/S76] | 9     | aic7xxx    | [B638694274](<Desktop/Dell/Vostro/Vostro 400/9FEBBAB61593/DEBIAN-11/5.10.0-20-AMD64/X86_64/B638694274>) |
| 9004:7178 |           | Adaptec          | AIC-7870P/7871 [AHA-2940/W/S76]      | 8     | aic7xxx    | [E1A81EDEA7](<Desktop/ASRock/4/4CoreDual-SATA2/C4F6D8A146F0/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E1A81EDEA7>) |
| 9004:8178 |           | Adaptec          | AIC-7870P/7881U [AHA-2940U/UW/D/S76] | 8     | aic7xxx    | [7539F3648F](<Desktop/Gigabyte Technology/GA-970/GA-970A-D3/B4B69547D91F/UBUNTU-20.04/5.11.0-44-GENERIC/X86_64/7539F3648F>) |
| 1000:0058 | 103c:3229 | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 6     | mptsas     | [8C0A201199](<Desktop/ASUSTek Computer/P5Q/P5Q Premium/C394E5A30DBE/LINUXMINT-19.3/5.4.0-125-GENERIC/X86_64/8C0A201199>) |
| 1b85:1021 | 1b85:1021 | OCZ Technolog... | 10xx SCSI Controller                 | 6     | mvsas      | [DC63E03D48](<Desktop/ASUSTek Computer/CM/CM1630/600622A69569/ZORIN-16/5.15.0-48-GENERIC/X86_64/DC63E03D48>) |
| 1de1:0391 | 1de1:0391 | Tekram Techno... | TRM-S1040 [DC-315 / DC-395 series]   | 6     | dc395x     | [F4AEFCD670](<Desktop/Dell/OptiPlex/OptiPlex 790/C2D4C0854C04/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/F4AEFCD670>) |
| 1000:0001 |           | LSI Logic / S... | 53c810                               | 5     | sym53c8xx  | [357911A814](<Desktop/Hewlett-Packard/d530/d530 CMT/6D542C172E73/DEBIAN-11/5.10.0-14-686-PAE/I686/357911A814>) |
| 1000:0030 | 103c:12f1 | LSI Logic / S... | 53c1030 PCI-X Fusion-MPT Dual Ult... | 5     | mptspi     | [8FF662507A](<Desktop/Hewlett-Packard/workstation/workstation xw8200/3B155B11885F/LINUXMINT-20.3/5.4.0-122-GENERIC/X86_64/8FF662507A>) |
| 1000:0050 | 103c:3015 | Broadcom / LSI   | SAS1064 PCI-X Fusion-MPT SAS         | 5     | mptsas     | [F9B0168DE1](<Desktop/Hewlett-Packard/xw8400/xw8400 Workstation/DB680909DD9F/XUBUNTU-22.10/5.19.0-1015-LOWLATENCY/X86_64/F9B0168DE1>) |
| 1000:0054 | 1028:1f08 | LSI Logic / S... | SAS1068 PCI-X Fusion-MPT SAS         | 5     | mptsas     | [9500786A21](<Desktop/Dell/Precision/Precision WorkStation 690/B0E5BCD0FEB2/UBUNTU-22.04/5.15.0-25-GENERIC/X86_64/9500786A21>) |
| 9004:6178 | 9004:7861 | Adaptec          | AIC-7861                             | 5     | aic7xxx    | [5416A71FEA](<Desktop/Fujitsu/ESPRIMO/ESPRIMO E900/AB398264C536/UBUNTU-18.04/5.4.0-58-GENERIC/X86_64/5416A71FEA>) |
| 9005:8017 | 9005:0045 | Adaptec          | ASC-29320ALP U320                    | 5     | aic79xx    | [F007AB3692](<Desktop/Dell/Precision/Precision 3650 Tower/EE588C08844C/CENTOS-8/5.10.10/X86_64/F007AB3692>) |
| 1000:0058 | 103c:12fe | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 4     | mptsas     | [6D6F2CE899](<Desktop/Hewlett-Packard/xw9400/xw9400 Workstation/929CBE5567A0/LUBUNTU-20.04/5.8.0-59-GENERIC/X86_64/6D6F2CE899>) |
| 11ab:7042 | 11ab:11ab | Marvell Techn... | 88SX7042 PCI-e 4-port SATA-II        | 4     | sata_mv    | [3D9AD6B8B1](<Desktop/ASUSTek Computer/KCMA-D/KCMA-D8/4B25A3EF9140/UBUNTU-22.04/5.15.0-52-GENERIC/X86_64/3D9AD6B8B1>) |
| 9005:0080 | 9005:62a0 | Adaptec          | AIC-7892A U160/m                     | 4     | aic7xxx    | [1B275899D5](<Desktop/Supermicro/C2/C2SBX/7D054759F288/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/1B275899D5>) |
| 9005:8017 | 9005:0044 | Adaptec          | ASC-29320ALP U320                    | 4     | aic79xx    | [C4041B26F3](<Desktop/IBM/eServer/eServer x3500-[7977G2G]/A6DB44627AC3/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/C4041B26F3>) |
| 1000:0030 | 1000:50c0 | LSI Logic / S... | 53c1030 PCI-X Fusion-MPT Dual Ult... | 3     | mptspi     | [FA38931F1F](<Desktop/Hewlett-Packard/Z600/Z600 Workstation/F4DBE56256E0/OPENSUSE-LEAP-15.4/5.14.21-150400.24.41-DEFAULT/X86_64/FA38931F1F>) |
| 1000:0030 | 103c:1500 | LSI Logic / S... | 53c1030 PCI-X Fusion-MPT Dual Ult... | 3     | mptspi     | [A94946D561](<Desktop/Hewlett-Packard/xw9300/xw9300 Workstation/796D0561C4B4/LUBUNTU-20.04/5.8.0-53-GENERIC/X86_64/A94946D561>) |
| 1000:0030 | 103c:322a | LSI Logic / S... | 53c1030 PCI-X Fusion-MPT Dual Ult... | 3     | mptspi     | [76CF2B62DB](<Desktop/Supermicro/C7/C7SIM-Q/AF731F0BAA05/DEBIAN-11/5.10.0-9-AMD64/X86_64/76CF2B62DB>) |
| 1000:0056 | 103c:322b | LSI Logic / S... | SAS1064ET PCI-Express Fusion-MPT SAS | 3     | mptsas     | [AF8E129ECD](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/B756A6667304/SPARKY-6.6/5.10.0-21-AMD64/X86_64/AF8E129ECD>) |
| 1000:0058 | 1014:0396 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 3     | mptsas     | [4DD5CEEF26](<Desktop/Dell/OptiPlex/OptiPlex 7010/6523DBCF8579/ARCH-ROLLING/5.18.1-ARCH1-1/X86_64/4DD5CEEF26>) |
| 10cd:1300 | 10cd:1310 | Advanced Syst... | ASC1300 / ASC3030 [ABP940-U / ABP... | 3     | advansys   | [A978613702](<Desktop/MSI/MS/MS-7641/F994C2FBE23A/UBUNTU-18.04/4.15.0-96-GENERIC/X86_64/A978613702>) |
| 1191:8040 | 1191:8040 | Artop Electronic | AEC6712D SCSI                        | 3     | atp870u    | [5D61DEB4D4](<Desktop/MSI/MS-7/MS-7A33/251C93855B45/DEBIAN-12/6.1.0-7-AMD64/X86_64/5D61DEB4D4>) |
| 9004:5078 |           | Adaptec          | AIC-7850T/7856T [AVA-2902/4/6 / A... | 3     | aic7xxx    | [330F034C61](<Desktop/Intel/DG31PR/DG31PR AAD97573-302/D96BE6B0F495/XUBUNTU-18.04/4.15.0-140-LOWLATENCY/I686/330F034C61>) |
| 9004:6178 |           | Adaptec          | AIC-7861                             | 3     | aic7xxx    | [A35B309960](<Desktop/Medion/MS/MS-7012/E487A3FBE9F6/XUBUNTU-18.04/4.15.0-123-GENERIC/I686/A35B309960>) |
| 9005:0010 | 9005:a180 | Adaptec          | AHA-2940U2/U2W                       | 3     | aic7xxx    | [F894ABD641](<Desktop/ASUSTek Computer/P5/P5KPL-SE/7F2E04977419/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/F894ABD641>) |
| 9005:0080 | 9005:e2a0 | Adaptec          | AIC-7892A U160/m                     | 3     | aic7xxx    | [2E2EF200F8](<Desktop/Fujitsu Siemens/CELSIUS/CELSIUS R630/A7D0C7CB05EE/LINUXMINT-19.3/5.0.0-32-GENERIC/X86_64/2E2EF200F8>) |
| 9005:0081 | 9005:62a1 | Adaptec          | AIC-7892B U160/m                     | 3     | aic7xxx    | [6F97813144](<Desktop/ASUSTek Computer/P5K/P5K Deluxe/DA82DB227041/FEDORA-36/6.0.5-200.FC36.X86_64/X86_64/6F97813144>) |
| 1000:000f | 1000:1000 | Broadcom / LSI   | 53c875                               | 2     | sym53c8xx  | [AE45AB5C00](<Desktop/MSI/P35/P35 Platinum/11849318E8A0/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/AE45AB5C00>) |
| 1000:0030 | 103c:3108 | LSI Logic / S... | 53c1030 PCI-X Fusion-MPT Dual Ult... | 2     | mptspi     | [47FD974AFD](<Desktop/Dell/Precision/Precision WorkStation 690/E43C5B330772/SLACKWARE-15.0/6.1.20/X86_64/47FD974AFD>) |
| 1000:0054 | 1000:30e0 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 2     | mptsas     | [AAC8A6F7E4](<Desktop/Others/Others/Others/7649ED3709F2/DEBIAN-7/4.1.42-RIVOREO-POWERPC64/PPC64/AAC8A6F7E4>) |
| 1000:0054 | 103c:3228 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 2     | mptsas     | [94AD27E346](<Desktop/Dell/Precision/Precision WorkStation 670/AE967E487843/LMDE-5/5.10.0-18-AMD64/X86_64/94AD27E346>) |
| 1000:0056 | 1014:03bb | LSI Logic / S... | SAS1064ET PCI-Express Fusion-MPT SAS | 2     | mptsas     | [A6FAE29097](<Desktop/IBM/System/System x3200 M3 -[7328AC1]-/F0FC4FE15FCC/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/A6FAE29097>) |
| 1000:0058 | 1000:3140 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 2     | mptsas     | [7DE05CDBC3](<Desktop/Gigabyte Technology/970/970A-DS3P/2B5C19A99151/ZORIN-16/5.11.0-37-GENERIC/X86_64/7DE05CDBC3>) |
| 1000:0058 | 1734:1130 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 2     | mptsas     | [2A000E48F4](<Desktop/CSL-Computer/A/A0000001/92D2E62459B8/ARCH/5.11.4-ARCH1-1/X86_64/2A000E48F4>) |
| 1000:0058 | 17aa:101d | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 2     | mptsas     | [8ADC2B3A82](<Desktop/Lenovo/ThinkStation/ThinkStation D10 6493RT8/564A075E25A7/UBUNTU-21.04/5.11.0-22-GENERIC/X86_64/8ADC2B3A82>) |
| 1022:2020 |           | AMD              | 53c974 [PCscsi]                      | 2     | am53c974   | [E720741A00](<Desktop/Gigabyte Technology/P55/P55-UD3R/30FA31F70A91/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/E720741A00>) |
| 1069:b166 | 1014:02d3 | Mylex            | AcceleRAID 600/500/400/Sapphire s... | 2     | ipr        | [AA1A843244](<Desktop/Others/Others/Others/7994F07888CD/DEBIAN-8/4.1.42-RIVOREO-POWERPC64/PPC64/AA1A843244>) |
| 1b85:1041 | 1b85:1041 | OCZ Technolog... | RevoDrive 3 X2 PCI-Express SSD 24... | 2     | mvsas      | [E0FC243F47](<Desktop/Hewlett-Packard/Z230/Z230 Tower Workstation/085844A04935/ARCH/5.10.30-1-LTS/X86_64/E0FC243F47>) |
| 9004:3860 | 9004:3869 | Adaptec          | AHA-2930CU                           | 2     | aic7xxx    | [275BC51AAF](<Desktop/Gigabyte Technology/H370/H370HD3/30B00256751D/XUBUNTU-18.04/5.4.0-131-GENERIC/X86_64/275BC51AAF>) |
| 9005:0010 | 9005:2180 | Adaptec          | AHA-2940U2/U2W                       | 2     | aic7xxx    | [67C4745D3A](<Desktop/ASUSTek Computer/M5/M5A78L-USB3/4A4CC8335017/ZORIN-15/5.3.0-59-GENERIC/X86_64/67C4745D3A>) |
| 9005:00c0 | 9005:f620 | Adaptec          | AHA-3960D / AIC-7899A U160/m         | 2     | aic7xxx    | [CDBF34FA56](<Desktop/Hewlett-Packard/workstation/workstation xw8200/7EBF00E71082/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/CDBF34FA56>) |
| 9005:8012 | 9005:0042 | Adaptec          | ASC-29320 U320                       | 2     | aic79xx    | [5923C246C4](<Desktop/ATComputers/AC/AC OFFICEPRO/63C4FEDBE783/UBUNTU-19.04/5.0.0-13-GENERIC/X86_64/5923C246C4>) |
| 9005:8016 | 9005:0040 | Adaptec          | ASC-39320A U320                      | 2     | aic79xx    | [5D9DA072F0](<Desktop/Biostar/B550/B550GTA/1C68140D01A1/UBUNTU-20.04/5.13.0-51-GENERIC/X86_64/5D9DA072F0>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2f88 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 VCU    | 703   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2f8a |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 VCU    | 703   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fae |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 703   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2faf |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 703   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fbe |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 703   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fbf |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 703   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2ff8 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Buf... | 703   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2ff9 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Buf... | 703   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2f6e |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 702   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2f6f |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 702   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fb8 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 702   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fb9 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 702   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fba |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 702   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fbb |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 702   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2f1d | 8086:2f1d | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 PCI... | 649   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2f1e | 8086:2f1e | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 649   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2f1f | 8086:2f1f | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 649   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2f71 | 8086:2f71 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 649   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2f98 | 8086:2f98 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Pow... | 649   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2f99 | 8086:2f99 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Pow... | 649   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2f9a | 8086:2f9a | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Pow... | 649   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2f9c | 8086:2f9c | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Pow... | 649   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fa0 | 8086:2fa0 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 649   | sb_edac    | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fa8 | 8086:2fa8 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 649   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2faa | 8086:2faa | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 649   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fab | 8086:2fab | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 649   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fb0 | 8086:2fb0 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 649   | hswep_u... | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fb1 | 8086:2fb1 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 649   | hswep_u... | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fb2 | 8086:2fb2 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 649   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fb3 | 8086:2fb3 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 649   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fc0 | 8086:2fc0 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Pow... | 649   | hswep_u... | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:1911 | 1458:5000 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 646   |            | [E44F7DFAC5](<Desktop/Punch Technology/PDT-702/PDT-702-1020/29C76CB9E8B7/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/E44F7DFAC5>) |
| 8086:2f81 | 8086:2f81 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 601   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fe0 | 8086:2fe0 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Uni... | 601   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fe1 | 8086:2fe1 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Uni... | 601   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fe2 | 8086:2fe2 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Uni... | 601   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fe3 | 8086:2fe3 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Uni... | 601   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2ffc | 8086:2fe0 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Sys... | 601   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2ffd | 8086:2fe0 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Sys... | 601   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2ffe | 8086:2fe0 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Sys... | 601   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fbc |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 550   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fbd |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 550   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fe4 | 8086:2fe4 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Uni... | 532   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fe5 | 8086:2fe5 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Uni... | 532   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2f68 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 485   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:2fd0 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 485   | hswep_u... | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:d150 |           | Intel            | Core Processor QPI Link              | 485   |            | [A07A7CF773](<Desktop/Gigabyte Technology/P55/P55M-UD2/B36DC4286599/OPENMANDRIVA-4.90/5.18.12-DESKTOP-3OMV4090/X86_64/A07A7CF773>) |
| 8086:d151 |           | Intel            | Core Processor QPI Routing and Pr... | 485   |            | [A07A7CF773](<Desktop/Gigabyte Technology/P55/P55M-UD2/B36DC4286599/OPENMANDRIVA-4.90/5.18.12-DESKTOP-3OMV4090/X86_64/A07A7CF773>) |
| 8086:d158 |           | Intel            | Core Processor Miscellaneous Regi... | 485   |            | [A07A7CF773](<Desktop/Gigabyte Technology/P55/P55M-UD2/B36DC4286599/OPENMANDRIVA-4.90/5.18.12-DESKTOP-3OMV4090/X86_64/A07A7CF773>) |
| 8086:2fac | 8086:2fac | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 445   |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |

### Tv card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 109e:036e |           | Brooktree        | Bt878 Video Capture                  | 36    | bttv       | [D0847FB118](<Desktop/ASUSTek Computer/A7/A7N8X-E/1BD0885D5B4D/LUBUNTU-18.04/4.15.0-206-GENERIC/I686/D0847FB118>) |
| 1131:7133 | 1461:a11b | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 24    | saa7134    | [D16B44B442](<Desktop/MSI/MS/MS-7519/66657F17E1FD/ARCH-ROLLING/6.2.8-ARCH1-1/X86_64/D16B44B442>) |
| 4444:0016 | 0070:8801 | Internext Com... | iTVC16 (CX23416) Video Decoder       | 23    | ivtv       | [CF4FE3C8D7](<Desktop/Hewlett-Packard/GN652AA-ABM/GN652AA-ABM m9050la/7772946DA47F/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/CF4FE3C8D7>) |
| 1131:7130 | 5ace:5050 | Philips Semic... | SAA7130 Video Broadcast Decoder      | 21    | saa7134    | [8BF7660808](<Desktop/ASUSTek Computer/A68/A68HM-K/65396CBF1888/FEDORA-35/5.14.18-300.FC35.X86_64/X86_64/8BF7660808>) |
| 14f1:8880 | 0070:7801 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 21    | cx23885    | [96BA9B6040](<Desktop/Hewlett-Packard/KQ497AA-A2L/KQ497AA-A2L m9340f/E7E55583567B/DEBIAN-10/5.3.5-64/X86_64/96BA9B6040>) |
| 1131:7133 | 5ace:5090 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 20    | saa7134    | [7234642CDE](<Desktop/MSI/MS/MS-7599/DE4F8FBDB651/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/7234642CDE>) |
| 14f1:8880 | 0070:f038 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 18    | cx23885    | [2FCCBC61E2](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/4A0B5FE6078A/GENTOO-2.9/6.2.0-GENTOO-X86_64/X86_64/2FCCBC61E2>) |
| 109e:036e | 1461:0003 | Brooktree        | Bt878 Video Capture                  | 17    | bttv       | [C9AC6EB940](<Desktop/Gigabyte Technology/M52/M52S-S3P/9FD6650D13F4/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/C9AC6EB940>) |
| 1131:7133 | 1461:4255 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 17    | saa7134    | [AC602A38EC](<Desktop/ASUSTek Computer/F1/F1A75-V/7854EA01C399/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/AC602A38EC>) |
| 1131:7134 | 1461:9715 | Philips Semic... | SAA7134/SAA7135HL Video Broadcast... | 17    | saa7134    | [32366172E4](<Desktop/ASRock/880/880GM-LE/06F093AF73B9/ROSA-12.3/5.15.79-GENERIC-1ROSA2021.1-X86_64/X86_64/32366172E4>) |
| 1131:7134 | 5ace:5070 | Philips Semic... | SAA7134/SAA7135HL Video Broadcast... | 17    | saa7134    | [B6FCAC82E8](<Desktop/ASUSTek Computer/P5/P5K/5106DAC25189/UBUNTU-18.04/5.3.0-28-GENERIC/X86_64/B6FCAC82E8>) |
| 1131:7133 | 16be:000d | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 15    | saa7134    | [9B80139ACA](<Desktop/Medion/MS/MS-7502/6116E95A7F06/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/9B80139ACA>) |
| 14f1:8852 | 0070:7911 | Conexant Systems | CX23885 PCI Video and Audio Decoder  | 15    | cx23885    | [DEF987E32C](<Desktop/ASRock/B365/B365M-HDV/F0C269B393DF/ARCH-ROLLING/6.2.1-ARCH1-1/X86_64/DEF987E32C>) |
| 109e:036e | 0070:13eb | Brooktree        | Bt878 Video Capture                  | 13    | bttv       | [2DC41C0B99](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite CMT PC/E54CED74845D/UBUNTU-20.04/5.13.0-51-GENERIC/X86_64/2DC41C0B99>) |
| 1131:7130 | 1131:0000 | Philips Semic... | SAA7130 Video Broadcast Decoder      | 13    | saa7134    | [499346B7AB](<Desktop/ASUSTek Computer/M2N-CM/M2N-CM DVI/4D1F5E205475/LINUXMINT-20.1/5.4.0-72-GENERIC/X86_64/499346B7AB>) |
| 1131:7134 | 185b:c200 | Philips Semic... | SAA7134/SAA7135HL Video Broadcast... | 13    | saa7134    | [F386A19D48](<Desktop/Acer/Veriton/Veriton S2610G/5436FDB2A2BB/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/F386A19D48>) |
| 1131:7134 | 1131:0000 | Philips Semic... | SAA7134/SAA7135HL Video Broadcast... | 12    | saa7134    | [ABF277EC59](<Desktop/Mustek6376 mst6376/P5/P5GC-VM/4154E83FB2CF/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/ABF277EC59>) |
| 11de:6057 | 1031:7efe | Zoran            | ZR36057PQC Video cutting chipset     | 12    | zr36067    | [451C626830](<Desktop/ASRock/Z97/Z97 Pro4/BAF192DD9D15/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/451C626830>) |
| 14f1:8880 | 1461:e139 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 12    | cx23885    | [4E2CD40175](<Desktop/Intel/DH55TC/DH55TC AAE70932-303/BF3C1B5EA92F/UBUNTU-20.04/5.15.0-60-GENERIC/X86_64/4E2CD40175>) |
| 1131:7133 | 11bd:002f | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 11    | saa7134    | [9BC1AEC0DC](<Desktop/Gigabyte Technology/GA-970/GA-970A-D3/0E585D7FA74B/LINUXMINT-20/5.4.0-135-GENERIC/X86_64/9BC1AEC0DC>) |
| 14f1:8800 |           | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 11    | cx8800     | [E80788F790](<Desktop/ASRock/775/775XFire-VSTA/16EC5FDAAED3/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E80788F790>) |
| 14f1:8880 | 0070:6a18 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 11    | cx23885    | [482C922BBC](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/3B3C1B7ED59B/MX-21/5.18.0-4MX-AMD64/X86_64/482C922BBC>) |
| 14f1:8880 | 0070:6b18 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 11    | cx23885    | [482C922BBC](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/3B3C1B7ED59B/MX-21/5.18.0-4MX-AMD64/X86_64/482C922BBC>) |
| 14f1:8880 | 0070:f02a | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 11    | cx23885    | [97620AC3E7](<Desktop/MSI/MS-7/MS-7C56/6D5C43A6D204/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/97620AC3E7>) |
| 1131:7130 | 1461:2115 | Philips Semic... | SAA7130 Video Broadcast Decoder      | 10    | saa7134    | [417D975CD9](<Desktop/ASUSTek Computer/P4/P4P800/92967C173382/ROSA-2016.1/4.15.0-DESKTOP-60.7ROSA-I586/I686/417D975CD9>) |
| 1131:7133 | 0000:4091 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 10    | saa7134    | [E7042308E9](<Desktop/MSI/MS/MS-7693/96A89E57BA55/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-X86_64/X86_64/E7042308E9>) |
| 1131:7133 | 1043:4871 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 10    | saa7134    | [B29A792D69](<Desktop/Hewlett-Packard/RJ083AA-ABZ/RJ083AA-ABZ t3630.it/63042232D530/LMDE-5/5.10.0-12-AMD64/X86_64/B29A792D69>) |
| 1131:7133 | 1131:0000 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 10    | saa7134    | [60E1A81B56](<Desktop/Hewlett-Packard/Compaq/Compaq dc7600 Small Form Factor/0F9F9361BFB3/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/60E1A81B56>) |
| 14f1:5b7a | 0070:7400 | Conexant Systems | CX23418 Single-Chip MPEG-2 Encode... | 10    | cx18       | [D71F476C72](<Desktop/Hewlett-Packard/GC674AA-ABA/GC674AA-ABA m8120n/C56B655BFAFE/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/D71F476C72>) |
| 14f1:8852 | 0070:6a28 | Conexant Systems | CX23885 PCI Video and Audio Decoder  | 10    | cx23885    | [ED86450031](<Desktop/ASUSTek Computer/Z170/Z170-A/FB70EE04C826/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/ED86450031>) |
| 14f1:8852 | 0070:6b28 | Conexant Systems | CX23885 PCI Video and Audio Decoder  | 10    | cx23885    | [ED86450031](<Desktop/ASUSTek Computer/Z170/Z170-A/FB70EE04C826/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/ED86450031>) |
| 14f1:8880 | 0070:6a28 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 10    | cx23885    | [7C54133B32](<Desktop/Hewlett-Packard/Compaq/Compaq 8000 Elite CMT PC/651AEBA8CAA9/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/7C54133B32>) |
| 14f1:8880 | 0070:6b28 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 10    | cx23885    | [7C54133B32](<Desktop/Hewlett-Packard/Compaq/Compaq 8000 Elite CMT PC/651AEBA8CAA9/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/7C54133B32>) |
| 14f1:8880 | 0070:c138 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 10    | cx23885    | [51017515BE](<Desktop/Intel/DG965WH/DG965WH AAD41692-304/2B564A04772E/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/51017515BE>) |
| 1131:7130 | 1461:a11b | Philips Semic... | SAA7130 Video Broadcast Decoder      | 9     | saa7134    | [08DA43BE7F](<Desktop/ASRock/P43/P43DE/CF9CAC13052E/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/08DA43BE7F>) |
| 1131:7133 | 1461:0155 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 9     | saa7134    | [3ED55D530A](<Desktop/Gigabyte Technology/H61/H61M-S2PV/DE2D1C5C4F5E/ALT-10.1/5.10.179-STD-DEF-ALT1/X86_64/3ED55D530A>) |
| 1131:7133 | 5ace:6090 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 9     | saa7134    | [14E5916050](<Desktop/ASRock/H67/H67DE3/E9603C970E1C/KUBUNTU-20.04/5.8.0-45-GENERIC/X86_64/14E5916050>) |
| 1131:7133 | 5ace:7290 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 9     | saa7134    | [60AB9AF8C6](<Desktop/ASUSTek Computer/All/All Series/E56B922DEFFA/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/60AB9AF8C6>) |
| 1131:7134 | 16be:0003 | Philips Semic... | SAA7134/SAA7135HL Video Broadcast... | 9     | saa7134    | [670E89DA85](<Desktop/MSI/MS/MS-7721/803EA27852BF/POP!_OS-22.04/6.2.0-76060200-GENERIC/X86_64/670E89DA85>) |
| 14f1:8800 | 107d:6611 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 9     | cx8800     | [870BBA0C09](<Desktop/ASUSTek Computer/M2/M2N4-SLI/6C43B2D62FB4/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/870BBA0C09>) |
| 4444:0016 | 1461:c439 | Internext Com... | iTVC16 (CX23416) Video Decoder       | 9     | ivtv       | [0C38152A55](<Desktop/Gigabyte Technology/M720/M720-US3/29B4253C4CCA/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/0C38152A55>) |
| 109e:036e | 11bd:0012 | Brooktree        | Bt878 Video Capture                  | 8     | bttv       | [7F1747C3E3](<Desktop/ASUSTek Computer/A88/A88X-PLUS/279BA270C61D/SLACKWARE-CURRENT/6.2.9-SLACK/X86_64/7F1747C3E3>) |
| 1131:7130 | 1a7f:2008 | Philips Semic... | SAA7130 Video Broadcast Decoder      | 8     | saa7134    | [744091DCAA](<Desktop/Gigabyte Technology/970/970A-DS3P/630B78A34EC4/DEBIAN-11/5.10.0-18-AMD64/X86_64/744091DCAA>) |
| 1131:7133 | 1043:4876 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 8     | saa7134    | [4DB9E36520](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX2/AAC10DE05D08/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/4DB9E36520>) |
| 1131:7133 | 11bd:002e | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 8     | saa7134    | [877FF67A70](<Desktop/Soncview/G41/G41D3C/5172625CFC8D/ZORIN-16/5.15.0-67-GENERIC/X86_64/877FF67A70>) |
| 1131:7133 | 1461:a14b | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 8     | saa7134    | [E6ED8A0215](<Desktop/ASUSTek Computer/P7/P7H55-USB3/EA607FC0E374/ROSA-12.4/5.15.103-GENERIC-1ROSA2021.1-X86_64/X86_64/E6ED8A0215>) |
| 1131:7133 | 1461:f11d | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 8     | saa7134    | [818EC10EC8](<Desktop/ASRock/M3/M3A790GXH-128M/AC45BB389319/ELEMENTARY-6/5.11.0-27-GENERIC/X86_64/818EC10EC8>) |
| 1131:7133 | 185b:c100 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 8     | saa7134    | [4BEF3EFCAE](<Desktop/MSI/MS-7/MS-7A34/415BB315446E/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/4BEF3EFCAE>) |
| 1131:7133 | 5ace:7595 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 8     | saa7134    | [8CA76C1F85](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LE-USB3/4EC0A28D4A72/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-I586/I686/8CA76C1F85>) |
| 1131:7134 | 5168:0138 | Philips Semic... | SAA7134/SAA7135HL Video Broadcast... | 8     | saa7134    | [69A029F975](<Desktop/Biostar/H61/H61MU3/EBA2C01EE0DE/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/69A029F975>) |

### Unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:31a2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 7     | intel_i... | [B5FFB4EE22](<Desktop/MW/GMLK-2/GMLK-2_5G4L/9C5515728C9C/DEBIAN-11/5.15.83-1-PVE/X86_64/B5FFB4EE22>) |
| 8086:5aa2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 5     | intel_i... | [4EF4F86A2E](<Desktop/AAEON/PICO-APL/PICO-APL3/C612505C44CA/LINUXMINT-21.1/5.15.0-60-GENERIC/X86_64/4EF4F86A2E>) |
| 13fe:1716 | 13fe:0001 | Advantech        |                                      | 1     |            | [047EAD1D70](<Desktop/Intel/SKYBAY/SKYBAY/9321BED375C6/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/047EAD1D70>) |
| 1af4:1044 | 1af4:1100 | Red Hat          | Virtio RNG                           | 1     | virtio_pci | [D62625A751](<Desktop/Optimized Hosting/KVM/KVM/9112EC3CC44C/ALMA-8.7/4.18.0-425.3.1.EL8.X86_64/X86_64/D62625A751>) |
| 1af4:1045 | 1af4:1100 | Red Hat          | Virtio memory balloon                | 1     | virtio_pci | [D62625A751](<Desktop/Optimized Hosting/KVM/KVM/9112EC3CC44C/ALMA-8.7/4.18.0-425.3.1.EL8.X86_64/X86_64/D62625A751>) |
| 8086:5aa2 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | intel_i... | [4A2F4F8CB1](<Desktop/Others/Others/Others/FBC02BEEE3C4/FEDORA-35/5.17.7-200.FC35.X86_64/X86_64/4A2F4F8CB1>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:43d5 | 1b21:1142 | AMD              | 400 Series Chipset USB 3.1 xHCI C... | 3428  | xhci_hcd   | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 1022:149c | 1022:148c | AMD              | Matisse USB 3.0 Host Controller      | 2942  | xhci_hcd   | [4E424E0AD2](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/2E14927B3139/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/4E424E0AD2>) |
| 1022:43ee | 1b21:1142 | AMD              | 500 Series Chipset USB 3.1 XHCI C... | 2109  | xhci_pci   | [DC43E4A7E3](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PRO/1FF7B8E0562A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/DC43E4A7E3>) |
| 1022:149c | 1043:87c0 | AMD              | Matisse USB 3.0 Host Controller      | 2065  | xhci_hcd   | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 1002:4397 | 1458:5004 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI0 Contr... | 1968  | ohci_pci   | [ACF61A6132](<Desktop/Gigabyte Technology/970/970A-DS3P/4209CEC662D2/OPENMANDRIVA-23.03/6.2.10-DESKTOP-2.0OMV4.9MJN/X86_64/ACF61A6132>) |
| 1002:4399 | 1458:5004 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI2 Contr... | 1968  | ohci_pci   | [ACF61A6132](<Desktop/Gigabyte Technology/970/970A-DS3P/4209CEC662D2/OPENMANDRIVA-23.03/6.2.10-DESKTOP-2.0OMV4.9MJN/X86_64/ACF61A6132>) |
| 1002:4396 | 1458:5004 | AMD              | SB7x0/SB8x0/SB9x0 USB EHCI Contro... | 1966  | ehci_pci   | [ACF61A6132](<Desktop/Gigabyte Technology/970/970A-DS3P/4209CEC662D2/OPENMANDRIVA-23.03/6.2.10-DESKTOP-2.0OMV4.9MJN/X86_64/ACF61A6132>) |
| 1b21:1042 | 1043:8488 | ASMedia Techn... | ASM1042 SuperSpeed USB Host Contr... | 1839  | xhci_hcd   | [F5499886E9](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/D04FB50B5F37/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/F5499886E9>) |
| 1002:4396 | 1002:4396 | AMD              | SB7x0/SB8x0/SB9x0 USB EHCI Contro... | 1555  | ehci_pci   | [F5499886E9](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/D04FB50B5F37/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/F5499886E9>) |
| 1022:149c | 1022:1486 | AMD              | Matisse USB 3.0 Host Controller      | 1541  | xhci_hcd   | [9430B8C328](<Desktop/Gigabyte Technology/X570/X570 GAMING X/856FFDCD7D13/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.3.1-1-VANILLA/X86_64/9430B8C328>) |
| 8086:1c26 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 1534  | ehci_pci   | [386D7C9DE4](<Desktop/ASUSTek Computer/P8/P8P67-M/D3654512534B/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/386D7C9DE4>) |
| 8086:1c2d | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 1534  | ehci_pci   | [386D7C9DE4](<Desktop/ASUSTek Computer/P8/P8P67-M/D3654512534B/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/386D7C9DE4>) |
| 1022:149c | 1458:5007 | AMD              | Matisse USB 3.0 Host Controller      | 1404  | xhci_hcd   | [9430B8C328](<Desktop/Gigabyte Technology/X570/X570 GAMING X/856FFDCD7D13/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.3.1-1-VANILLA/X86_64/9430B8C328>) |
| 8086:27c8 | 1043:8179 | Intel            | NM10/ICH7 Family USB UHCI Control... | 1301  | uhci_hcd   | [D5456946BB](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LE/8FE632A39CF5/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D5456946BB>) |
| 8086:27c9 | 1043:8179 | Intel            | NM10/ICH7 Family USB UHCI Control... | 1301  | uhci_hcd   | [D5456946BB](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LE/8FE632A39CF5/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D5456946BB>) |
| 8086:27ca | 1043:8179 | Intel            | NM10/ICH7 Family USB UHCI Control... | 1300  | uhci_hcd   | [D5456946BB](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LE/8FE632A39CF5/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D5456946BB>) |
| 8086:27cb | 1043:8179 | Intel            | NM10/ICH7 Family USB UHCI Control... | 1299  | uhci_hcd   | [D5456946BB](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LE/8FE632A39CF5/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D5456946BB>) |
| 1002:4397 | 1002:4397 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI0 Contr... | 1294  | ohci_pci   | [F5499886E9](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/D04FB50B5F37/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/F5499886E9>) |
| 8086:8c26 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 1290  | ehci_pci   | [E146C82A49](<Desktop/ASUSTek Computer/All/All Series/D75C393B8A2E/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/E146C82A49>) |
| 8086:8c31 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 1283  | xhci_hcd   | [E146C82A49](<Desktop/ASUSTek Computer/All/All Series/D75C393B8A2E/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/E146C82A49>) |
| 8086:27cc | 1043:8179 | Intel            | NM10/ICH7 Family USB2 EHCI Contro... | 1282  | ehci_pci   | [D5456946BB](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LE/8FE632A39CF5/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D5456946BB>) |
| 8086:8c2d | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 1271  | ehci_pci   | [E146C82A49](<Desktop/ASUSTek Computer/All/All Series/D75C393B8A2E/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/E146C82A49>) |
| 1002:4399 | 1002:4399 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI2 Contr... | 1184  | ohci_pci   | [F5499886E9](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/D04FB50B5F37/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/F5499886E9>) |
| 1002:4396 | 1043:8389 | AMD              | SB7x0/SB8x0/SB9x0 USB EHCI Contro... | 1124  | ehci_pci   | [E3DC27EEE1](<Desktop/ASUSTek Computer/M5A78L/M5A78L LE/E8B8C04727FE/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/E3DC27EEE1>) |
| 1002:4397 | 1043:8389 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI0 Contr... | 1124  | ohci_pci   | [E3DC27EEE1](<Desktop/ASUSTek Computer/M5A78L/M5A78L LE/E8B8C04727FE/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/E3DC27EEE1>) |
| 1002:4398 | 1043:8389 | AMD              | SB7x0 USB OHCI1 Controller           | 1121  | ohci_pci   | [E3DC27EEE1](<Desktop/ASUSTek Computer/M5A78L/M5A78L LE/E8B8C04727FE/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/E3DC27EEE1>) |
| 1002:4399 | 1043:8389 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI2 Contr... | 1121  | ohci_pci   | [E3DC27EEE1](<Desktop/ASUSTek Computer/M5A78L/M5A78L LE/E8B8C04727FE/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/E3DC27EEE1>) |
| 8086:a12f | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 1105  | xhci_hcd   | [BBFD29FB88](<Desktop/ASUSTek Computer/D320/D320SF/A7E6ADB389B1/UBUNTU-20.04/5.4.0-148-GENERIC/X86_64/BBFD29FB88>) |
| 1022:43bc | 1b21:1142 | AMD              | A320 USB 3.1 XHCI Host Controller    | 1070  | xhci_hcd   | [A241837604](<Desktop/LTD Delovoy Office/320A3SM/320A3SM MT/67FBE1AE8CE6/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/A241837604>) |
| 8086:1e26 | 1043:84ca | Intel            | 7 Series/C216 Chipset Family USB ... | 1065  | ehci_pci   | [92B5951471](<Desktop/ASUSTek Computer/Z77/Z77-A/7F8B426D3C22/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/92B5951471>) |
| 8086:1e2d | 1043:84ca | Intel            | 7 Series/C216 Chipset Family USB ... | 1065  | ehci_pci   | [92B5951471](<Desktop/ASUSTek Computer/Z77/Z77-A/7F8B426D3C22/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/92B5951471>) |
| 8086:1e31 | 1043:84ca | Intel            | 7 Series/C210 Series Chipset Fami... | 1056  | xhci_pci   | [92B5951471](<Desktop/ASUSTek Computer/Z77/Z77-A/7F8B426D3C22/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/92B5951471>) |
| 1022:43bb | 1b21:1142 | AMD              | 300 Series Chipset USB 3.1 xHCI C... | 1051  | xhci_hcd   | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 1106:3483 | 1106:3483 | VIA Technologies | VL805/806 xHCI USB 3.0 Controller    | 1030  | xhci_hcd   | [13B1131BEF](<Desktop/ASRock/H67/H67DE3-SI/ED18AAFC18F5/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/13B1131BEF>) |
| 1b21:1142 | 1043:85bf | ASMedia Techn... | ASM1042A USB 3.0 Host Controller     | 1024  | xhci_hcd   | [31123C256D](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/58F18DE5017C/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/31123C256D>) |
| 1002:4398 | 1458:5004 | AMD              | SB7x0 USB OHCI1 Controller           | 1006  | ohci_pci   | [631317F909](<Desktop/Gigabyte Technology/GA-78/GA-78LMT-S2/A7640481CED2/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/631317F909>) |
| 8086:27c8 | 1458:5004 | Intel            | NM10/ICH7 Family USB UHCI Control... | 984   | uhci_hcd   | [0458D9F44B](<Desktop/Gigabyte Technology/G41/G41MT-S2/EF1568975525/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/0458D9F44B>) |
| 8086:27c9 | 1458:5004 | Intel            | NM10/ICH7 Family USB UHCI Control... | 984   | uhci_hcd   | [0458D9F44B](<Desktop/Gigabyte Technology/G41/G41MT-S2/EF1568975525/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/0458D9F44B>) |
| 8086:27ca | 1458:5004 | Intel            | NM10/ICH7 Family USB UHCI Control... | 984   | uhci_hcd   | [0458D9F44B](<Desktop/Gigabyte Technology/G41/G41MT-S2/EF1568975525/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/0458D9F44B>) |
| 8086:27cb | 1458:5004 | Intel            | NM10/ICH7 Family USB UHCI Control... | 984   | uhci_hcd   | [0458D9F44B](<Desktop/Gigabyte Technology/G41/G41MT-S2/EF1568975525/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/0458D9F44B>) |
| 8086:27cc | 1458:5006 | Intel            | NM10/ICH7 Family USB2 EHCI Contro... | 982   | ehci_pci   | [0458D9F44B](<Desktop/Gigabyte Technology/G41/G41MT-S2/EF1568975525/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/0458D9F44B>) |
| 8086:1c26 | 1458:5006 | Intel            | 6 Series/C200 Series Chipset Fami... | 934   | ehci_pci   | [E7B77F5CF0](<Desktop/Gigabyte Technology/Z68/Z68MA-D2H-B3/99DA8E367A7A/OPENMANDRIVA-23.03/5.16.13-DESKTOP-1OMV4003/X86_64/E7B77F5CF0>) |
| 8086:1c2d | 1458:5006 | Intel            | 6 Series/C200 Series Chipset Fami... | 934   | ehci_pci   | [E7B77F5CF0](<Desktop/Gigabyte Technology/Z68/Z68MA-D2H-B3/99DA8E367A7A/OPENMANDRIVA-23.03/5.16.13-DESKTOP-1OMV4003/X86_64/E7B77F5CF0>) |
| 1b21:1242 | 1043:8675 | ASMedia Techn... | ASM1142 USB 3.1 Host Controller      | 898   | xhci_hcd   | [77ECF9C05D](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-K/C1DFDE9A944B/ARCHLABSX-ROLLING/6.2.14-1-CLEAR/X86_64/77ECF9C05D>) |
| 8086:8c31 | 1458:5007 | Intel            | 8 Series/C220 Series Chipset Fami... | 854   | xhci_hcd   | [22BD54D6D1](<Desktop/Gigabyte Technology/Z87/Z87X-UD3H/F9D737247AAE/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/22BD54D6D1>) |
| 8086:8c26 | 1458:5006 | Intel            | 8 Series/C220 Series Chipset Fami... | 848   | ehci_pci   | [22BD54D6D1](<Desktop/Gigabyte Technology/Z87/Z87X-UD3H/F9D737247AAE/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/22BD54D6D1>) |
| 8086:8c2d | 1458:5006 | Intel            | 8 Series/C220 Series Chipset Fami... | 848   | ehci_pci   | [22BD54D6D1](<Desktop/Gigabyte Technology/Z87/Z87X-UD3H/F9D737247AAE/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/22BD54D6D1>) |
| 8086:3a34 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 845   | uhci_hcd   | [C2A0653C52](<Desktop/ASUSTek Computer/P5QLD/P5QLD PRO/0678AB1FB908/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/C2A0653C52>) |
| 8086:3a35 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 845   | uhci_hcd   | [C2A0653C52](<Desktop/ASUSTek Computer/P5QLD/P5QLD PRO/0678AB1FB908/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/C2A0653C52>) |
| 8086:3a36 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 845   | uhci_hcd   | [C2A0653C52](<Desktop/ASUSTek Computer/P5QLD/P5QLD PRO/0678AB1FB908/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/C2A0653C52>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:8d7c | 1043:8600 | Intel            | C610/X99 series chipset SPSR         | 178   |            | [6505E46B86](<Desktop/ASUSTek Computer/All/All Series/5486940BFA29/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/6505E46B86>) |
| 8086:8d7c | 8086:7270 | Intel            | C610/X99 series chipset SPSR         | 150   |            | [B8C2462ADA](<Desktop/Huanan/X99/X99 F8D V2.2/E58F0A6F2159/ROSA-12.4/6.1.20.XM1-1.KLP-XANMOD-ROSA2021.1-X86_64/X86_64/B8C2462ADA>) |
| 8086:8d7c | 103c:212b | Intel            | C610/X99 series chipset SPSR         | 63    |            | [D71B834A1C](<Desktop/Hewlett-Packard/Z440/Z440 Workstation/4440A0D853F2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/D71B834A1C>) |
| 8086:8d7c | 1849:8d7c | Intel            | C610/X99 series chipset SPSR         | 63    |            | [E375BE2EA6](<Desktop/ASRock/X99/X99 Extreme4/1B995760A330/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/E375BE2EA6>) |
| 8086:8d7c | 1028:0617 | Intel            | C610/X99 series chipset SPSR         | 62    |            | [33517B7BFE](<Desktop/Dell/Precision/Precision Tower 5810/4630C280B407/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/33517B7BFE>) |
| 8086:8d7c | 1458:7270 | Intel            | C610/X99 series chipset SPSR         | 61    |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 8086:8d7c | 1462:7885 | Intel            | C610/X99 series chipset SPSR         | 54    |            | [BC30B63CE3](<Desktop/MSI/MS/MS-7885/34D003A502BB/FEDORA-36/6.0.7-200.FC36.X86_64/X86_64/BC30B63CE3>) |
| 10ec:816e | 10ec:8168 | Realtek Semic... | RealManage BMC                       | 39    |            | [895855ED9A](<Desktop/ASUSTek Computer/Pro/Pro WS X570-ACE/7D768ECED733/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/895855ED9A>) |
| 8086:8d7c | 1028:0618 | Intel            | C610/X99 series chipset SPSR         | 27    |            | [08502CDA27](<Desktop/Dell/Precision/Precision Tower 7810/46536ED933CB/UBUNTU-MATE-20.04/5.4.0-126-GENERIC/X86_64/08502CDA27>) |
| 1af2:a001 | 1af2:a001 | AVerMedia        | Live Gamer HD                        | 23    |            | [3D79F67248](<Desktop/MSI/MS/MS-7882/CB1D1EC610B0/UBUNTU-22.04/6.1.0-1008-OEM/X86_64/3D79F67248>) |
| 8086:8d7c | 1043:85f6 | Intel            | C610/X99 series chipset SPSR         | 22    |            | [DD74CB518B](<Desktop/ASUSTek Computer/Z10PE-D16/Z10PE-D16 WS/CAA4B6326775/ARCO-ROLLING/5.15.93-1-LTS/X86_64/DD74CB518B>) |
| 8086:8d7c | 17aa:102f | Intel            | C610/X99 series chipset SPSR         | 22    |            | [15CC4335C7](<Desktop/Lenovo/ThinkStation/ThinkStation P410 30B3003SUS/53840422D466/MANJARO-22.1.0/6.1.23-1-MANJARO/X86_64/15CC4335C7>) |
| 8086:8d7c | 1028:0619 | Intel            | C610/X99 series chipset SPSR         | 18    |            | [F76BC64EE4](<Desktop/Dell/Precision/Precision Tower 7910/96D37272A606/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/F76BC64EE4>) |
| 8086:8d7c | 103c:2129 | Intel            | C610/X99 series chipset SPSR         | 18    |            | [5118EB06D4](<Desktop/Hewlett-Packard/Z840/Z840 Workstation/A1C1A0E7C94F/ZORIN-16/5.15.0-56-GENERIC/X86_64/5118EB06D4>) |
| 8086:8d7c | 103c:212a | Intel            | C610/X99 series chipset SPSR         | 17    |            | [178F3B9C05](<Desktop/Hewlett-Packard/Z640/Z640 Workstation/76188D60CA15/DEVUAN-4/5.10.0-21-AMD64/X86_64/178F3B9C05>) |
| 8086:6ff2 | 8086:6ff2 | Intel            | Broadwell-E CBo Unicast Registers 0  | 11    |            | [DD74CB518B](<Desktop/ASUSTek Computer/Z10PE-D16/Z10PE-D16 WS/CAA4B6326775/ARCO-ROLLING/5.15.93-1-LTS/X86_64/DD74CB518B>) |
| 8086:6ff3 | 8086:6ff3 | Intel            | Broadwell-E CBo Unicast Registers 1  | 11    |            | [DD74CB518B](<Desktop/ASUSTek Computer/Z10PE-D16/Z10PE-D16 WS/CAA4B6326775/ARCO-ROLLING/5.15.93-1-LTS/X86_64/DD74CB518B>) |
| 8086:8d7c | 1734:1201 | Intel            | C610/X99 series chipset SPSR         | 10    |            | [96D5A26185](<Desktop/Fujitsu/CELSIUS/CELSIUS M740/A518D19E460A/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/96D5A26185>) |
| 8086:8d7c | 103c:8030 | Intel            | C610/X99 series chipset SPSR         | 8     |            | [2AC4801793](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML110 Gen9/2EB1953A265E/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/2AC4801793>) |
| 8086:8d7c | 15d9:0836 | Intel            | C610/X99 series chipset SPSR         | 8     |            | [B777ED256F](<Desktop/Supermicro/X10/X10DAi/50E866E4C839/CENTOS-7/3.10.0-1160.62.1.EL7.X86_64/X86_64/B777ED256F>) |
| 8086:8d7c | 1028:061b | Intel            | C610/X99 series chipset SPSR         | 7     |            | [BCD33A41F0](<Desktop/Dell/PowerEdge/PowerEdge FC630/513B47FCFD6E/OL-7.4/3.10.0-693.11.6.EL7.X86_64/X86_64/BCD33A41F0>) |
| 8086:8d7c | 1028:064c | Intel            | C610/X99 series chipset SPSR         | 7     |            | [AE3A750F2E](<Desktop/Alienware/Area-51/Area-51 R2/FC654B5565AC/UBUNTU-22.04/5.15.0-33-GENERIC/X86_64/AE3A750F2E>) |
| 8086:8d7c | 1462:7a20 | Intel            | C610/X99 series chipset SPSR         | 7     |            | [F526447F78](<Desktop/MSI/MS-7/MS-7A20/FFD3A5DE2318/DEBIAN-10/4.19.0-21-AMD64/X86_64/F526447F78>) |
| 8086:6ff4 | 8086:6ff4 | Intel            | Broadwell-E CBo Unicast Registers 2  | 5     |            | [C2430965A1](<Desktop/MACHINIST/X99-D8-MAX/X99-D8-MAX V1.0/05392AD3DE5C/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C2430965A1>) |
| 8086:6ff5 | 8086:6ff5 | Intel            | Broadwell-E CBo Unicast Registers 3  | 5     |            | [C2430965A1](<Desktop/MACHINIST/X99-D8-MAX/X99-D8-MAX V1.0/05392AD3DE5C/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C2430965A1>) |
| 8086:8d7c | 17aa:1030 | Intel            | C610/X99 series chipset SPSR         | 5     |            | [0FF94735BD](<Desktop/Lenovo/ThinkStation/ThinkStation P910 30B8S0EN00/96AB81C58D41/UBUNTU-22.10/5.19.0-26-GENERIC/X86_64/0FF94735BD>) |
| 8086:8d7c | 17aa:1031 | Intel            | C610/X99 series chipset SPSR         | 5     |            | [DAED0124F0](<Desktop/Lenovo/ThinkStation/ThinkStation P700 30A9CTO1WW/72EA0E4F8B9C/DEBIAN-11/5.10.0-21-AMD64/X86_64/DAED0124F0>) |
| 8086:8d7c | 15d9:0844 | Intel            | C610/X99 series chipset SPSR         | 4     |            | [E55EDCE907](<Desktop/Supermicro/SYS-1028/SYS-1028U-TRT+/DD6BB69425C7/UBUNTU-20.04/5.4.0-132-GENERIC/X86_64/E55EDCE907>) |
| 8086:8d7c | 15d9:0852 | Intel            | C610/X99 series chipset SPSR         | 4     |            | [5AF331BC84](<Desktop/Supermicro/SYS-7048/SYS-7048GR-TR/EDF23ABA9696/FEDORA-33/5.14.18-100.FC33.X86_64/X86_64/5AF331BC84>) |
| 106b:003b |           | Apple            | UniNorth/Intrepid ATA/100            | 3     | ide_pmac   | [C6F9883076](<Desktop/Others/Others/Others/EC08DE5C12C4/GENTOO-2.8/5.15.41-GENTOO/PPC/C6F9883076>) |
| 106b:003e |           | Apple            | KeyLargo/Intrepid Mac I/O            | 3     | macio      | [C6F9883076](<Desktop/Others/Others/Others/EC08DE5C12C4/GENTOO-2.8/5.15.41-GENTOO/PPC/C6F9883076>) |
| 8086:3591 | 1028:0173 | Intel            | E7525/E7520 Error Reporting Regis... | 3     |            | [C729382738](<Desktop/Dell/PowerEdge/PowerEdge SC1420/85A333307EF2/UBUNTU-18.04/4.15.0-200-GENERIC/I686/C729382738>) |
| 8086:8d7c | 1462:7882 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [3D79F67248](<Desktop/MSI/MS/MS-7882/CB1D1EC610B0/UBUNTU-22.04/6.1.0-1008-OEM/X86_64/3D79F67248>) |
| 8086:8d7c | 1462:7883 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [64A313C9E3](<Desktop/MSI/MS/MS-7883/C0DD3B72C922/UBUNTU-20.04/5.4.0-29-GENERIC/X86_64/64A313C9E3>) |
| 8086:8d7c | 1462:7a21 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [E764729EEB](<Desktop/MSI/MS-7/MS-7A21/64652FD2B499/KUBUNTU-22.04/5.15.0-41-GENERIC/X86_64/E764729EEB>) |
| 8086:8d7c | 1462:7a54 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [731716B865](<Desktop/MSI/MS-7/MS-7A54/C333FA83CAC2/KDE-NEON-20.04/5.15.0-43-GENERIC/X86_64/731716B865>) |
| 8086:8d7c | 15d9:0835 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [3AA5AEBAEE](<Desktop/Supermicro/SSG-6048/SSG-6048R-E1CR36N/222ACB66D393/DEBIAN-11/5.15.83-1-PVE/X86_64/3AA5AEBAEE>) |
| 8086:8d7c | 3842:1038 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [B293ADE39D](<Desktop/EVGA/151/151-HE-E999/EB84918A34B3/POP!_OS-22.04/6.2.0-76060200-GENERIC/X86_64/B293ADE39D>) |
| 8086:a1ec | 1028:0739 | Intel            | C620 Series Chipset Family MROM 0    | 3     |            | [4619F572C5](<Desktop/Dell/Precision/Precision 7820 Tower/72B53570A2A3/DEBIAN/6.1.0-1-AMD64/X86_64/4619F572C5>) |
| 8086:a1ec | 103c:81c7 | Intel            | C620 Series Chipset Family MROM 0    | 3     |            | [23D528F392](<Desktop/Hewlett-Packard/Z8/Z8 G4 Workstation/845EF22B0CE6/ZORIN-16/5.11.0-37-GENERIC/X86_64/23D528F392>) |
| 8086:a1ec | 1043:871e | Intel            | C620 Series Chipset Family MROM 0    | 3     |            | [4EBF4D9CC8](<Desktop/ASUSTek Computer/Pro/Pro E800 G4_WS950T/DE05676A6A87/UBUNTU-22.04/5.15.0-27-GENERIC/X86_64/4EBF4D9CC8>) |
| 8086:a1ed | 103c:81c7 | Intel            | C620 Series Chipset Family MROM 1    | 3     |            | [23D528F392](<Desktop/Hewlett-Packard/Z8/Z8 G4 Workstation/845EF22B0CE6/ZORIN-16/5.11.0-37-GENERIC/X86_64/23D528F392>) |
| 106b:004f |           | Apple            | Shasta Mac I/O                       | 2     | macio      | [49C235AA0D](<Desktop/Others/Others/Others/4F0261A213DC/VOID-ROLLING/5.18.16_1/PPC64/49C235AA0D>) |
| 106b:0050 |           | Apple            | Shasta IDE                           | 2     | ide_pmac   | [49C235AA0D](<Desktop/Others/Others/Others/4F0261A213DC/VOID-ROLLING/5.18.16_1/PPC64/49C235AA0D>) |
| 1102:0002 | ffff:ffff | Creative Labs    | EMU10k1 [Sound Blaster Live! Series] | 2     | snd_emu... | [4521F2B9B4](<Desktop/ASUSTek Computer/P4/P4C800-E/52FDED7A661E/UBUNTU-UNITY-18.04/4.15.0-209-GENERIC/I686/4521F2B9B4>) |
| 1102:0004 | ffff:ffff | Creative Labs    | EMU10k2/CA0100/CA0102/CA10200 [So... | 2     | snd_emu... | [3DB646F782](<Desktop/ASUSTek Computer/P7/P7P55D-E/3EEF910514D4/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/3DB646F782>) |
| 1274:5880 | ffff:ffff | Ensoniq          | 5880B / Creative Labs CT5880         | 2     | snd_ens... | [CC0925A796](<Desktop/Gigabyte Technology/965/965P-S3/9860CF669FDC/ZORIN-15/5.3.0-61-GENERIC/X86_64/CC0925A796>) |
| 8086:3591 | 1043:8145 | Intel            | E7525/E7520 Error Reporting Regis... | 2     |            | [E078564242](<Desktop/ASUSTek Computer/NCL-DS/NCL-DS/5404271617FE/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/E078564242>) |
| 8086:3593 | 8086:345e | Intel            | E7320 Error Reporting Registers      | 2     |            | [AD1A126878](<Desktop/Intel/SE7320EP2/SE7320EP2 D11950-402/3262F56CD032/DEBIAN-11/5.10.0-20-AMD64/X86_64/AD1A126878>) |
| 8086:6ff2 | 15d9:0835 | Intel            | Broadwell-E CBo Unicast Registers 0  | 2     |            | [3AA5AEBAEE](<Desktop/Supermicro/SSG-6048/SSG-6048R-E1CR36N/222ACB66D393/DEBIAN-11/5.15.83-1-PVE/X86_64/3AA5AEBAEE>) |

