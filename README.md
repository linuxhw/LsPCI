Most popular PCI devices
========================

This is a project to identify most popular PCI devices in modern computers and
share detailed lspci reports collected by Linux users at https://linux-hardware.org.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Total reports: 465566.

Contents
--------

1. [ About ](#about)
2. [ PCI Devices ](#pci-devices)
   * [ Bluetooth ](#bluetooth-pci)
   * [ Bridge ](#bridge-pci)
   * [ Canbus ](#canbus-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Digitizer pen ](#digitizer-pen-pci)
   * [ Dma controller (eisa dma) ](#dma-controller-eisa-dma-pci)
   * [ Dpio module ](#dpio-module-pci)
   * [ Dvb card ](#dvb-card-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Entertainment encryption device ](#entertainment-encryption-device-pci)
   * [ Ethernet controller ](#ethernet-controller-pci)
   * [ Firewire controller ](#firewire-controller-pci)
   * [ Flash memory ](#flash-memory-pci)
   * [ Generic system peripheral ](#generic-system-peripheral-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Input device controller ](#input-device-controller-pci)
   * [ Iommu ](#iommu-pci)
   * [ Ipmi interface (kcs) ](#ipmi-interface-kcs-pci)
   * [ Ipmi smic interface ](#ipmi-smic-interface-pci)
   * [ Isdn adapter ](#isdn-adapter-pci)
   * [ Keyboard controller ](#keyboard-controller-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Modem ](#modem-pci)
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
   * [ Rf controller ](#rf-controller-pci)
   * [ Scsi storage controller ](#scsi-storage-controller-pci)
   * [ Sd host controller ](#sd-host-controller-pci)
   * [ Serial bus controller ](#serial-bus-controller-pci)
   * [ Serial controller ](#serial-controller-pci)
   * [ Signal processing ](#signal-processing-pci)
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
   * [ Wireless controller ](#wireless-controller-pci)
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

Top 50 most popular devices in each category.

Count  - number of computers with this device installed,
Driver - driver in use for this device,
Probe  - latest probe ID of this device.

### Bluetooth (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1814:3298 | 103c:18ec | Ralink           | RT3290 Bluetooth                     | 989   | rtbth      | [E8728549F4](<Notebook/Hewlett-Packard/655/655/7C80AF022F04/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E8728549F4>) |
| 1814:3298 | 105b:e056 | Ralink           | RT3290 Bluetooth                     | 180   | rtbth      | [952D22573D](<Notebook/ASUSTek Computer/N56/N56JN/953A084BBABB/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/952D22573D>) |
| 1814:3298 | 103c:191c | Ralink           | RT3290 Bluetooth                     | 48    | rtbth      | [8A01DA4323](<Notebook/Hewlett-Packard/Pavilion/Pavilion G4-2265BR NB PC/78C972F1A8D6/LINUXMINT-22/6.8.0-47-GENERIC/X86_64/8A01DA4323>) |
| 1814:3298 | 1a3b:2f87 | Ralink           | RT3290 Bluetooth                     | 20    |            | [2924888CAC](<Desktop/ZOOSTORM/9876/9876-2577A/C318CE68C7DA/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/2924888CAC>) |
| 1814:3298 | 1a3b:2787 | Ralink           | RT3290 Bluetooth                     | 19    |            | [D74ABF8D8A](<Notebook/Acer/Aspire/Aspire 5742Z/FB5BE93A69D6/ROSA-12.5/6.6.21-GENERIC-8ROSA2021.1-X86_64/X86_64/D74ABF8D8A>) |
| 1814:3298 | 1814:3298 | Ralink           | RT3290 Bluetooth                     | 10    |            | [202F89C024](<Notebook/ASUSTek Computer/X550/X550JK/F4BBACAE7F03/UBUNTU-CORE-22/6.8.0-40-GENERIC/X86_64/202F89C024>) |
| 1814:3298 | 1a3b:2987 | Ralink           | RT3290 Bluetooth                     | 9     |            | [FFCD5B9FA5](<Desktop/GuoGuang/IC2/IC2M1028N/FB1E1BD517AD/ZORIN-16/5.15.0-79-GENERIC/X86_64/FFCD5B9FA5>) |
| 8086:a876 | 8086:000e | Intel            | Bluetooth                            | 8     | btintel... | [5F2A3C878A](<Convertible/Hewlett-Packard/OmniBook/OmniBook Ultra Flip Laptop 14-fh0xxx/76D672E0E745/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/5F2A3C878A>) |
| 1814:3298 | 10cf:1772 | Ralink           | RT3290 Bluetooth                     | 2     |            | [2DC30249B7](<Notebook/Fujitsu/FMVA33/FMVA33LB2/6669A168BD57/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2DC30249B7>) |
| 14c3:8650 | 14c3:8650 | MediaTek         | MT7650 Bluetooth                     | 1     |            | [CC5250290B](<Desktop/Others/Others/Others/C58CA0A5CE09/OPENWRT-23.05.3/5.15.150/MIPS/CC5250290B>) |
| 1814:3298 | 103c:0080 | Ralink           | RT3290 Bluetooth                     | 1     | rtbth      | [60660DB51F](<Desktop/Hewlett-Packard/20/20-d038d/F9B5ADA5FB1F/LINUXMINT-21.3/5.15.0-97-GENERIC/X86_64/60660DB51F>) |
| 1814:3298 | 1a3b:210b | Ralink           | RT3290 Bluetooth                     | 1     |            | [2333E930AF](<Notebook/ASUSTek Computer/UX31/UX31E/DDB4E3347FB6/ROSA-2016.1/4.9.124-NRJ-DESKTOP-1ROSA-X86_64/X86_64/2333E930AF>) |

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1632 |           | AMD              | Renoir PCIe Dummy Host Bridge        | 14501 | vfio_pci   | [DFF6A36E92](<Notebook/Valve/Galileo/Galileo/3D6CF2B6536D/STEAMOS-3.6.20/6.5.0-VALVE22-1-NEPTUNE-65-G9A338ED8A75E/X86_64/DFF6A36E92>) |
| 1022:1452 |           | AMD              | Family 17h (Models 00h-1fh) PCIe ... | 12955 |            | [A23FC83EDD](<Desktop/Gigabyte Technology/AB350/AB350-Gaming/B5A158869F92/GENTOO-2.17/6.6.67-GENTOO/X86_64/A23FC83EDD>) |
| 1002:4384 |           | AMD              | SBx00 PCI to PCI Bridge              | 11655 | shpchp     | [E4674EED04](<Notebook/eMachines/E/E625/7B695C056FAD/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/E4674EED04>) |
| 1022:1482 |           | AMD              | Starship/Matisse PCIe Dummy Host ... | 10125 | vfio_pci   | [FDA84AF6B6](<Desktop/MSI/MS-7/MS-7A40/DC07AAAD39A3/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/FDA84AF6B6>) |
| 1022:1440 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 9745  |            | [FDA84AF6B6](<Desktop/MSI/MS-7/MS-7A40/DC07AAAD39A3/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/FDA84AF6B6>) |
| 1022:1441 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 9745  |            | [FDA84AF6B6](<Desktop/MSI/MS-7/MS-7A40/DC07AAAD39A3/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/FDA84AF6B6>) |
| 1022:1442 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 9745  |            | [FDA84AF6B6](<Desktop/MSI/MS-7/MS-7A40/DC07AAAD39A3/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/FDA84AF6B6>) |
| 1022:1443 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 9745  | k10temp    | [FDA84AF6B6](<Desktop/MSI/MS-7/MS-7A40/DC07AAAD39A3/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/FDA84AF6B6>) |
| 1022:1444 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 9745  |            | [FDA84AF6B6](<Desktop/MSI/MS-7/MS-7A40/DC07AAAD39A3/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/FDA84AF6B6>) |
| 1022:1445 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 9745  |            | [FDA84AF6B6](<Desktop/MSI/MS-7/MS-7A40/DC07AAAD39A3/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/FDA84AF6B6>) |
| 1022:1446 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 9745  |            | [FDA84AF6B6](<Desktop/MSI/MS-7/MS-7A40/DC07AAAD39A3/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/FDA84AF6B6>) |
| 1022:1447 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 9745  |            | [FDA84AF6B6](<Desktop/MSI/MS-7/MS-7A40/DC07AAAD39A3/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/FDA84AF6B6>) |
| 1022:1635 | 1022:1635 | AMD              | Renoir Internal PCIe GPP Bridge t... | 9741  | pcieport   | [69FF87B949](<Desktop/Gigabyte Technology/A520/A520 AORUS ELITE/81AB90394B6C/GENTOO-2.17/6.6.67-GENTOO/X86_64/69FF87B949>) |
| 1022:15e8 |           | AMD              | Raven/Raven2 Device 24: Function 0   | 7721  |            | [C5C9A457AA](<Notebook/Lenovo/V15-ADA/V15-ADA 82C7/DF20D99E1E88/DEBIAN-12/6.1.0-28-AMD64/X86_64/C5C9A457AA>) |
| 1022:15e9 |           | AMD              | Raven/Raven2 Device 24: Function 1   | 7721  |            | [C5C9A457AA](<Notebook/Lenovo/V15-ADA/V15-ADA 82C7/DF20D99E1E88/DEBIAN-12/6.1.0-28-AMD64/X86_64/C5C9A457AA>) |
| 1022:15ea |           | AMD              | Raven/Raven2 Device 24: Function 2   | 7721  |            | [C5C9A457AA](<Notebook/Lenovo/V15-ADA/V15-ADA 82C7/DF20D99E1E88/DEBIAN-12/6.1.0-28-AMD64/X86_64/C5C9A457AA>) |
| 1022:15eb |           | AMD              | Raven/Raven2 Device 24: Function 3   | 7721  | k10temp    | [C5C9A457AA](<Notebook/Lenovo/V15-ADA/V15-ADA 82C7/DF20D99E1E88/DEBIAN-12/6.1.0-28-AMD64/X86_64/C5C9A457AA>) |
| 1022:15ec |           | AMD              | Raven/Raven2 Device 24: Function 4   | 7721  |            | [C5C9A457AA](<Notebook/Lenovo/V15-ADA/V15-ADA 82C7/DF20D99E1E88/DEBIAN-12/6.1.0-28-AMD64/X86_64/C5C9A457AA>) |
| 1022:15ed |           | AMD              | Raven/Raven2 Device 24: Function 5   | 7721  |            | [C5C9A457AA](<Notebook/Lenovo/V15-ADA/V15-ADA 82C7/DF20D99E1E88/DEBIAN-12/6.1.0-28-AMD64/X86_64/C5C9A457AA>) |
| 1022:15ee |           | AMD              | Raven/Raven2 Device 24: Function 6   | 7721  |            | [C5C9A457AA](<Notebook/Lenovo/V15-ADA/V15-ADA 82C7/DF20D99E1E88/DEBIAN-12/6.1.0-28-AMD64/X86_64/C5C9A457AA>) |
| 1022:15ef |           | AMD              | Raven/Raven2 Device 24: Function 7   | 7721  |            | [C5C9A457AA](<Notebook/Lenovo/V15-ADA/V15-ADA 82C7/DF20D99E1E88/DEBIAN-12/6.1.0-28-AMD64/X86_64/C5C9A457AA>) |
| 1022:1634 | 1022:1453 | AMD              | Renoir/Cezanne PCIe GPP Bridge       | 7678  | pcieport   | [69FF87B949](<Desktop/Gigabyte Technology/A520/A520 AORUS ELITE/81AB90394B6C/GENTOO-2.17/6.6.67-GENTOO/X86_64/69FF87B949>) |
| 1022:1448 |           | AMD              | Renoir Device 24: Function 0         | 6869  |            | [84DECD497D](<Desktop/BESSTAR Tech/HM/HM80/641CA314EE82/NOBARA-39/6.8.12-200.FSYNC.FC39.X86_64/X86_64/84DECD497D>) |
| 1022:1449 |           | AMD              | Renoir Device 24: Function 1         | 6869  |            | [84DECD497D](<Desktop/BESSTAR Tech/HM/HM80/641CA314EE82/NOBARA-39/6.8.12-200.FSYNC.FC39.X86_64/X86_64/84DECD497D>) |
| 1022:144a |           | AMD              | Renoir Device 24: Function 2         | 6869  |            | [84DECD497D](<Desktop/BESSTAR Tech/HM/HM80/641CA314EE82/NOBARA-39/6.8.12-200.FSYNC.FC39.X86_64/X86_64/84DECD497D>) |
| 1022:144b |           | AMD              | Renoir Device 24: Function 3         | 6869  | k10temp    | [84DECD497D](<Desktop/BESSTAR Tech/HM/HM80/641CA314EE82/NOBARA-39/6.8.12-200.FSYNC.FC39.X86_64/X86_64/84DECD497D>) |
| 1022:144c |           | AMD              | Renoir Device 24: Function 4         | 6869  |            | [84DECD497D](<Desktop/BESSTAR Tech/HM/HM80/641CA314EE82/NOBARA-39/6.8.12-200.FSYNC.FC39.X86_64/X86_64/84DECD497D>) |
| 1022:144d |           | AMD              | Renoir Device 24: Function 5         | 6869  |            | [84DECD497D](<Desktop/BESSTAR Tech/HM/HM80/641CA314EE82/NOBARA-39/6.8.12-200.FSYNC.FC39.X86_64/X86_64/84DECD497D>) |
| 1022:144e |           | AMD              | Renoir Device 24: Function 6         | 6869  |            | [84DECD497D](<Desktop/BESSTAR Tech/HM/HM80/641CA314EE82/NOBARA-39/6.8.12-200.FSYNC.FC39.X86_64/X86_64/84DECD497D>) |
| 1022:144f |           | AMD              | Renoir Device 24: Function 7         | 6869  |            | [84DECD497D](<Desktop/BESSTAR Tech/HM/HM80/641CA314EE82/NOBARA-39/6.8.12-200.FSYNC.FC39.X86_64/X86_64/84DECD497D>) |
| 1022:1200 |           | AMD              | Family 10h Processor HyperTranspo... | 6520  |            | [617C102331](<Desktop/Gigabyte Technology/GA-MA770/GA-MA770T-UD3/8220651D2E86/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/617C102331>) |
| 1022:1201 |           | AMD              | Family 10h Processor Address Map     | 6520  |            | [617C102331](<Desktop/Gigabyte Technology/GA-MA770/GA-MA770T-UD3/8220651D2E86/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/617C102331>) |
| 1022:1202 |           | AMD              | Family 10h Processor DRAM Controller | 6520  | amd64_e... | [617C102331](<Desktop/Gigabyte Technology/GA-MA770/GA-MA770T-UD3/8220651D2E86/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/617C102331>) |
| 1022:1203 |           | AMD              | Family 10h Processor Miscellaneou... | 6520  | k10temp    | [617C102331](<Desktop/Gigabyte Technology/GA-MA770/GA-MA770T-UD3/8220651D2E86/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/617C102331>) |
| 1022:1204 |           | AMD              | Family 10h Processor Link Control    | 6520  |            | [617C102331](<Desktop/Gigabyte Technology/GA-MA770/GA-MA770T-UD3/8220651D2E86/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/617C102331>) |
| 1022:43c7 | 1b21:3306 | AMD              | 400 Series Chipset PCIe Port         | 6520  | pcieport   | [FDA84AF6B6](<Desktop/MSI/MS-7/MS-7A40/DC07AAAD39A3/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/FDA84AF6B6>) |
| 1002:1478 |           | AMD              | Navi 10 XL Upstream Port of PCI E... | 6436  | pcieport   | [1FF9C9F7CB](<Desktop/MSI/MS-7/MS-7E26/771CE98DF000/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/1FF9C9F7CB>) |
| 1002:1479 | 1002:1479 | AMD              | Navi 10 XL Downstream Port of PCI... | 6434  | pcieport   | [1FF9C9F7CB](<Desktop/MSI/MS-7/MS-7E26/771CE98DF000/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/1FF9C9F7CB>) |
| 1022:15db | 1022:0000 | AMD              | Raven/Raven2 Internal PCIe GPP Br... | 6133  | pcieport   | [C5C9A457AA](<Notebook/Lenovo/V15-ADA/V15-ADA 82C7/DF20D99E1E88/DEBIAN-12/6.1.0-28-AMD64/X86_64/C5C9A457AA>) |
| 1022:43c6 | 1b21:0201 | AMD              | 400 Series Chipset PCIe Bridge       | 6060  | pcieport   | [FDA84AF6B6](<Desktop/MSI/MS-7/MS-7A40/DC07AAAD39A3/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/FDA84AF6B6>) |
| 1022:1484 | 1022:1484 | AMD              | Starship/Matisse Internal PCIe GP... | 6002  | pcieport   | [726B65D6E8](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.10/4.18.0-553.27.1.EL8_10.X86_64/X86_64/726B65D6E8>) |
| 1022:166a |           | AMD              | Cezanne Data Fabric; Function 0      | 5890  |            | [69FF87B949](<Desktop/Gigabyte Technology/A520/A520 AORUS ELITE/81AB90394B6C/GENTOO-2.17/6.6.67-GENTOO/X86_64/69FF87B949>) |
| 1022:166b |           | AMD              | Cezanne Data Fabric; Function 1      | 5890  |            | [69FF87B949](<Desktop/Gigabyte Technology/A520/A520 AORUS ELITE/81AB90394B6C/GENTOO-2.17/6.6.67-GENTOO/X86_64/69FF87B949>) |
| 1022:166c |           | AMD              | Cezanne Data Fabric; Function 2      | 5890  |            | [69FF87B949](<Desktop/Gigabyte Technology/A520/A520 AORUS ELITE/81AB90394B6C/GENTOO-2.17/6.6.67-GENTOO/X86_64/69FF87B949>) |
| 1022:166d |           | AMD              | Cezanne Data Fabric; Function 3      | 5890  | k10temp    | [69FF87B949](<Desktop/Gigabyte Technology/A520/A520 AORUS ELITE/81AB90394B6C/GENTOO-2.17/6.6.67-GENTOO/X86_64/69FF87B949>) |
| 1022:166e |           | AMD              | Cezanne Data Fabric; Function 4      | 5890  |            | [69FF87B949](<Desktop/Gigabyte Technology/A520/A520 AORUS ELITE/81AB90394B6C/GENTOO-2.17/6.6.67-GENTOO/X86_64/69FF87B949>) |
| 1022:166f |           | AMD              | Cezanne Data Fabric; Function 5      | 5890  |            | [69FF87B949](<Desktop/Gigabyte Technology/A520/A520 AORUS ELITE/81AB90394B6C/GENTOO-2.17/6.6.67-GENTOO/X86_64/69FF87B949>) |
| 1022:1670 |           | AMD              | Cezanne Data Fabric; Function 6      | 5890  |            | [69FF87B949](<Desktop/Gigabyte Technology/A520/A520 AORUS ELITE/81AB90394B6C/GENTOO-2.17/6.6.67-GENTOO/X86_64/69FF87B949>) |
| 1022:1671 |           | AMD              | Cezanne Data Fabric; Function 7      | 5890  |            | [69FF87B949](<Desktop/Gigabyte Technology/A520/A520 AORUS ELITE/81AB90394B6C/GENTOO-2.17/6.6.67-GENTOO/X86_64/69FF87B949>) |
| 1022:780f |           | AMD              | FCH PCI Bridge                       | 5708  | shpchp     | [0B29006A62](<Desktop/ASUSTek Computer/K30/K30BF_M32BF_A_F_K31BF_6/AF04F3B51155/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/0B29006A62>) |

### Canbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:4bc1 | 8086:7270 | Intel            | CANBUS                               | 5     | m_can_pci  | [53A2979277](<Mini Pc/Dell EMC/Edge/Edge Gateway 3200/688BB18AF5F8/UBUNTU-20.04/5.15.0-72-GENERIC/X86_64/53A2979277>) |
| 8086:4bc2 | 8086:7270 | Intel            | CANBUS                               | 3     | m_can_pci  | [53A2979277](<Mini Pc/Dell EMC/Edge/Edge Gateway 3200/688BB18AF5F8/UBUNTU-20.04/5.15.0-72-GENERIC/X86_64/53A2979277>) |
| 1a07:0011 | 1a07:0011 | Kvaser AB        | Mini PCIe 2xHS v2                    | 1     | kvaser_... | [196C8EB317](<Server/Neousys Technology/Nuvo-7100VTC/Nuvo-7100VTC Series/E44E3E216941/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/196C8EB317>) |
| 1c29:1703 | 1c29:0000 |                  | CANBUS                               | 1     |            | [3F9A3BADB0](<Notebook/SINTRONES/AMB-5000/AMB-5000G1/946AE3F5AEBD/UBUNTU-UNITY-16.04/4.15.0-112-GENERIC/X86_64/3F9A3BADB0>) |
| 1c29:2004 | 1c29:0001 |                  | CANBUS                               | 1     | f81601     | [789CBBC90C](<Desktop/Others/Others/Others/00379E206AA3/UBUNTU-22.04/5.15.0-1040-INTEL-IOTG/X86_64/789CBBC90C>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:5287 | 1043:202f | Realtek Semic... | RTL8411B PCI Express Card Reader     | 593   | rtsx_pci   | [11D8D9B891](<Notebook/ASUSTek Computer/X751/X751SA/6960612BD44A/OPENSUSE-LEAP-15.5/5.14.21-150500.55.88-DEFAULT/X86_64/11D8D9B891>) |
| 10ec:522a | 10ec:522a | Realtek Semic... | RTS522A PCI Express Card Reader      | 469   | rtsx_pci   | [046BBB97DB](<Notebook/Lenovo/IdeaPad/IdeaPad Pro 5 14APH8 83AM/E902B3B08EDD/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/046BBB97DB>) |
| 10ec:5286 | 1043:202f | Realtek Semic... | RTL8402 Integrated 1-LUN Card Reader | 399   | rtsx_pci   | [5D46DEDC86](<Notebook/ASUSTek Computer/X541/X541UJ/E2DE5B9001B2/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/5D46DEDC86>) |
| 10ec:522a | 1043:202f | Realtek Semic... | RTS522A PCI Express Card Reader      | 390   | rtsx_pci   | [2EE9B0919F](<Notebook/ASUSTek Computer/ZenBook/ZenBook UX425EA_UX425EA/595F3683B808/FEDORA-41/6.12.5-200.FC41.X86_64/X86_64/2EE9B0919F>) |
| 10ec:5289 | 1043:202f | Realtek Semic... | RTL8411 PCI Express Card Reader      | 322   | rtsx_pci   | [F39F501A7F](<Notebook/ASUSTek Computer/X550/X550VL/73E673B38E27/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/F39F501A7F>) |
| 10ec:522a | 17aa:5082 | Realtek Semic... | RTS522A PCI Express Card Reader      | 302   | rtsx_pci   | [C68A17F027](<Notebook/Lenovo/ThinkPad/ThinkPad T14s Gen 1 20UH002LUK/3790C38E2827/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/C68A17F027>) |
| 10ec:522a | 103c:8079 | Realtek Semic... | RTS522A PCI Express Card Reader      | 300   | rtsx_pci   | [DA5C26013C](<Notebook/Hewlett-Packard/ZBook/ZBook 15u G3/5C8D48F3C0A5/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/DA5C26013C>) |
| 10ec:5286 | 10ec:5286 | Realtek Semic... | RTL8402 Integrated 1-LUN Card Reader | 282   | rtsx_pci   | [B5CB158E93](<Notebook/Positivo/W940/W940TU/3CDFDFEDA432/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/B5CB158E93>) |
| 10ec:5227 | 17aa:5034 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 274   | rtsx_pci   | [10131EA72A](<Notebook/Lenovo/ThinkPad/ThinkPad T450s 20BXCTO1WW/C77FFBE2C387/ARCH-ROLLING/6.12.8-ARCH1-1/X86_64/10131EA72A>) |
| 10ec:525a | 10ec:525a | Realtek Semic... | RTS525A PCI Express Card Reader      | 254   | rtsx_pci   | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 10ec:5227 | 17aa:220c | Realtek Semic... | RTS5227 PCI Express Card Reader      | 253   | rtsx_pci   | [17AC336E9C](<Notebook/Lenovo/ThinkPad/ThinkPad T440s 20ARS46M00/DD9FCCD73F49/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/17AC336E9C>) |
| 10ec:5229 | 1043:202f | Realtek Semic... | RTS5229 PCI Express Card Reader      | 249   | rtsx_pci   | [3CF042BF3F](<Notebook/ASUSTek Computer/Strix/Strix 15 GL503GE/2E7CE511186E/ARCO-ROLLING/6.12.7-ZEN1-1-ZEN/X86_64/3CF042BF3F>) |
| 10ec:522a | 8086:2074 | Realtek Semic... | RTS522A PCI Express Card Reader      | 242   | rtsx_pci   | [CC4E4FFE1A](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/6C0029DC8B93/DEBIAN-12/6.1.0-26-AMD64/X86_64/CC4E4FFE1A>) |
| 10ec:525a | 1028:0905 | Realtek Semic... | RTS525A PCI Express Card Reader      | 242   | rtsx_pci   | [C74F2A3D62](<Notebook/Dell/XPS/XPS 15 7590/26B1B8DF46EC/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/C74F2A3D62>) |
| 10ec:5227 | 103c:198f | Realtek Semic... | RTS5227 PCI Express Card Reader      | 234   | rtsx_pci   | [F298C84729](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G1/EA6A0969E96A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/F298C84729>) |
| 10ec:525a | 1028:087c | Realtek Semic... | RTS525A PCI Express Card Reader      | 232   | rtsx_pci   | [5EB1399D1E](<Notebook/Dell/XPS/XPS 15 9570/45E4548EA4E7/ARCH-ROLLING/6.12.7-ARCH1-1/X86_64/5EB1399D1E>) |
| 10ec:5227 | 17aa:220e | Realtek Semic... | RTS5227 PCI Express Card Reader      | 230   | rtsx_pci   | [DBDFF3AB95](<Notebook/Lenovo/ThinkPad/ThinkPad T440p 20AN0069US/0478FECF01E5/LINUXMINT-21.2/5.15.0-130-GENERIC/X86_64/DBDFF3AB95>) |
| 10ec:522a | 17aa:2233 | Realtek Semic... | RTS522A PCI Express Card Reader      | 229   | rtsx_pci   | [00BB35DD31](<Notebook/Lenovo/ThinkPad/ThinkPad T560 20FH001RUS/B528951A4C78/DEBIAN-12/6.1.0-28-AMD64/X86_64/00BB35DD31>) |
| 10ec:5289 | 10ec:5289 | Realtek Semic... | RTL8411 PCI Express Card Reader      | 227   | rtsx_pci   | [C0F17443E2](<Notebook/Acer/Aspire/Aspire V5-431P/2DF735D20C2C/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/C0F17443E2>) |
| 10ec:5287 | 1025:1193 | Realtek Semic... | RTL8411B PCI Express Card Reader     | 217   | rtsx_pci   | [6D732C3B4D](<Notebook/Acer/Aspire/Aspire A515-51G/A64C288A0498/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/6D732C3B4D>) |
| 10ec:525a | 1028:081c | Realtek Semic... | RTS525A PCI Express Card Reader      | 216   | rtsx_pci   | [5781936456](<Notebook/Dell/Latitude/Latitude 7490/FCD718DFC39C/RHEL-9/5.14.0-503.19.1.EL9_5.X86_64/X86_64/5781936456>) |
| 10ec:5287 | 1025:1094 | Realtek Semic... | RTL8411B PCI Express Card Reader     | 212   | rtsx_pci   | [8A7B632B3F](<Notebook/Acer/Aspire/Aspire E5-575/2F74F452914E/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/8A7B632B3F>) |
| 10ec:5260 | 1028:097d | Realtek Semic... | RTS5260 PCI Express Card Reader      | 204   | rtsx_pci   | [2A60673D8C](<Notebook/Dell/XPS/XPS 15 9500/C1F125F74882/KALI-2024.4/6.11.2-AMD64/X86_64/2A60673D8C>) |
| 10ec:5287 | 1025:0866 | Realtek Semic... | RTL8411B PCI Express Card Reader     | 204   | rtsx_pci   | [DCA3176D13](<Notebook/Acer/Aspire/Aspire E5-572G/119C96C6F625/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/DCA3176D13>) |
| 10ec:5229 | 10ec:5229 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 202   | rtsx_pci   | [B458C0587B](<Notebook/Lenovo/IdeaPad/IdeaPad 120S-14IAP 81A5/49258B986E1F/DEBIAN-12/6.1.0-28-AMD64/X86_64/B458C0587B>) |
| 10ec:5227 | 103c:1993 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 190   | rtsx_pci   | [2E0D9756FE](<Notebook/Hewlett-Packard/ProBook/ProBook 650 G1/2A79D22D0FF9/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/2E0D9756FE>) |
| 10ec:5227 | 17aa:2214 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 182   | rtsx_pci   | [6441794672](<Notebook/Lenovo/ThinkPad/ThinkPad X240 20AL009CUS/212531206609/VANILLA-2.0/6.11.6-AMD64/X86_64/6441794672>) |
| 10ec:525a | 1028:07e6 | Realtek Semic... | RTS525A PCI Express Card Reader      | 182   | rtsx_pci   | [6B3D0134AB](<Notebook/Dell/XPS/XPS 13 9370/81DD97A09733/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/6B3D0134AB>) |
| 10ec:5209 | 104d:908b | Realtek Semic... | RTS5209 PCI Express Card Reader      | 174   | rtsx_pci   | [11625E4A3C](<Notebook/Sony/VPCEJ2/VPCEJ2E1E/510E1D6ED21D/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/11625E4A3C>) |
| 10ec:5227 | 103c:2216 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 174   | rtsx_pci   | [69146BEEEB](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G2/8D975FE03272/ZORIN-17/6.8.0-50-GENERIC/X86_64/69146BEEEB>) |
| 10ec:522a | 17aa:2279 | Realtek Semic... | RTS522A PCI Express Card Reader      | 171   | rtsx_pci   | [B9E31A2832](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N3S82N1P/72B74810F0E9/ARCH-ROLLING/6.12.8-ARCH1-1/X86_64/B9E31A2832>) |
| 10ec:522a | 17aa:5053 | Realtek Semic... | RTS522A PCI Express Card Reader      | 171   | rtsx_pci   | [438781676D](<Notebook/Lenovo/ThinkPad/ThinkPad T460 20FMS0EP00/B451AF080516/DEBIAN/6.12.6-AMD64/X86_64/438781676D>) |
| 10ec:525a | 1028:07be | Realtek Semic... | RTS525A PCI Express Card Reader      | 171   | rtsx_pci   | [924D90CDCC](<Notebook/Dell/XPS/XPS 15 9560/EC3726E4E16E/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/924D90CDCC>) |
| 10ec:5227 | 17aa:2226 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 167   | rtsx_pci   | [23C3A522F9](<Notebook/Lenovo/ThinkPad/ThinkPad X250 20CLS45J00/50C13FEE08DD/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/23C3A522F9>) |
| 10ec:522a | 17aa:5062 | Realtek Semic... | RTS522A PCI Express Card Reader      | 164   | rtsx_pci   | [E45E264430](<Notebook/Lenovo/ThinkPad/ThinkPad X270 20K5S1A524/707A3D8F2480/MANJARO-24.2.1/6.6.65-1-MANJARO/X86_64/E45E264430>) |
| 10ec:5229 | 17aa:3808 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 159   | rtsx_pci   | [EAA8DD18D4](<Notebook/Lenovo/IdeaPad/IdeaPad 100-15IBY 80MJ/30B76AD22206/ROSA-12.5.1/6.6.27-GENERIC-3ROSA2021.1-X86_64/X86_64/EAA8DD18D4>) |
| 10ec:522a | 17aa:5089 | Realtek Semic... | RTS522A PCI Express Card Reader      | 157   | rtsx_pci   | [179A63F113](<Convertible/Lenovo/ThinkPad/ThinkPad L13 Yoga Gen 2 20VKS0ME00/614558C26FAF/FEDORA-40/6.12.4-100.FC40.X86_64/X86_64/179A63F113>) |
| 10ec:525a | 17aa:222e | Realtek Semic... | RTS525A PCI Express Card Reader      | 157   | rtsx_pci   | [A5ACB19495](<Notebook/Lenovo/ThinkPad/ThinkPad P50 20EN0013US/7E6BF26E35AA/KALI-2024.4/6.11.2-AMD64/X86_64/A5ACB19495>) |
| 10ec:525a | 1028:0962 | Realtek Semic... | RTS525A PCI Express Card Reader      | 156   | rtsx_pci   | [66950741D8](<Notebook/Dell/XPS/XPS 13 7390/B56C8E9067D6/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/66950741D8>) |
| 10ec:525a | 1028:08af | Realtek Semic... | RTS525A PCI Express Card Reader      | 149   | rtsx_pci   | [063A26FA4D](<Notebook/Dell/XPS/XPS 13 9380/31234F1B5EDE/UBUNTU-18.04/5.4.0-150-GENERIC/X86_64/063A26FA4D>) |
| 10ec:525a | 1028:0a20 | Realtek Semic... | RTS525A PCI Express Card Reader      | 148   | rtsx_pci   | [1D2EC04557](<Notebook/Dell/Latitude/Latitude 5420/BC912D9B0DFC/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/1D2EC04557>) |
| 10ec:5260 | 1028:0991 | Realtek Semic... | RTS5260 PCI Express Card Reader      | 147   | rtsx_pci   | [31EB7F33DB](<Notebook/Dell/XPS/XPS 13 9310/6BD6176CC7AD/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/31EB7F33DB>) |
| 10ec:5287 | 1025:1264 | Realtek Semic... | RTL8411B PCI Express Card Reader     | 147   | rtsx_pci   | [9FD3688418](<Notebook/Acer/Nitro/Nitro AN515-52/C38CC2F8D5DC/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/9FD3688418>) |
| 10ec:5229 | 8086:2068 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 146   | rtsx_pci   | [D06ADF16E1](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/AEB46873549B/DEBIAN-12/6.1.0-28-AMD64/X86_64/D06ADF16E1>) |
| 10ec:525a | 1028:06de | Realtek Semic... | RTS525A PCI Express Card Reader      | 146   | rtsx_pci   | [57A956FE26](<Notebook/Dell/Latitude/Latitude E5470/4DA2C327C00A/NOBARA-39/6.8.12-200.FSYNC.FC39.X86_64/X86_64/57A956FE26>) |
| 10ec:5229 | 10cf:176b | Realtek Semic... | RTS5229 PCI Express Card Reader      | 145   | rtsx_pci   | [6299219A54](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK E752/FFFA626358E2/UBUNTU-18.04/5.4.0-150-GENERIC/X86_64/6299219A54>) |
| 10ec:525a | 1028:06dc | Realtek Semic... | RTS525A PCI Express Card Reader      | 143   | rtsx_pci   | [448C4C5D6E](<Notebook/Dell/Latitude/Latitude E7470/E6EA2D9D8448/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/448C4C5D6E>) |
| 10ec:525a | 1028:07a0 | Realtek Semic... | RTS525A PCI Express Card Reader      | 139   | rtsx_pci   | [FAA26E30D0](<Notebook/Dell/Latitude/Latitude 7480/DDDC98D1B760/DEBIAN-12/6.1.0-28-AMD64/X86_64/FAA26E30D0>) |
| 10ec:5287 | 10ec:5287 | Realtek Semic... | RTL8411B PCI Express Card Reader     | 139   | rtsx_pci   | [BEECCB21E7](<Notebook/ASUSTek Computer/TP500/TP500LN/0F5976C2EE60/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/BEECCB21E7>) |
| 10ec:525a | 1028:075b | Realtek Semic... | RTS525A PCI Express Card Reader      | 138   | rtsx_pci   | [4E5B03BFD7](<Notebook/Dell/XPS/XPS 13 9360/FB39A8254748/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/4E5B03BFD7>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10de:0aa3 | 10de:cb79 | Nvidia           | MCP79 Co-processor                   | 1080  | nvidia     | [DE39DE3147](<Notebook/Apple/MacBookPro5/MacBookPro5,5/AE9A7F9028B1/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/DE39DE3147>) |
| 10de:0d7a | 10de:cb89 | Nvidia           | MCP89 Co-Processor                   | 278   |            | [7961299452](<Notebook/Apple/MacBookPro7/MacBookPro7,1/55DEE2A47303/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/7961299452>) |
| 10de:0753 | 103c:360a | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 97    |            | [1CF492F425](<Notebook/Hewlett-Packard/Compaq/Compaq Presario CQ60/9D837B366E46/UBUNTU-20.04/5.15.0-126-GENERIC/X86_64/1CF492F425>) |
| 10de:0753 | 1043:82f2 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 97    |            | [C6B776D706](<Desktop/ASUSTek Computer/M4/M4N78-AM/12259A7FFE25/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/C6B776D706>) |
| 10de:03f4 | 1462:7597 | Nvidia           | MCP61 SMU                            | 58    |            | [DF34126457](<Desktop/MSI/MS/MS-7597/10C76749B1C9/ZORIN-17/6.8.0-49-GENERIC/X86_64/DF34126457>) |
| 10de:0543 | 1025:0126 | Nvidia           | MCP67 Co-processor                   | 47    |            | [8633B8AD2A](<Notebook/Acer/Aspire/Aspire 7520/AE449E677566/LINUXMINT-21.3/5.15.0-130-GENERIC/X86_64/8633B8AD2A>) |
| 10de:0543 | 103c:30cf | Nvidia           | MCP67 Co-processor                   | 47    |            | [FB46ED47A1](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv6700/A930AF0C1A9B/LINUXMINT-21.3/5.15.0-102-GENERIC/X86_64/FB46ED47A1>) |
| 10de:0753 | 1849:0753 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 46    |            | [AC75A8CAA6](<Desktop/ASRock/M3N78D/M3N78D FX/EC69AE0ED6A9/FEDORA-39/6.7.9-204.FSYNC.FC39.X86_64/X86_64/AC75A8CAA6>) |
| 10de:03f4 | 1462:7309 | Nvidia           | MCP61 SMU                            | 45    |            | [0683637148](<Desktop/MSI/MS/MS-7309/17A7C47F1CAC/ROSA-12.5/6.1.86-GENERIC-1ROSA2021.1-X86_64/X86_64/0683637148>) |
| 10de:0aa3 | 1043:1fa7 | Nvidia           | MCP79 Co-processor                   | 44    | nvidia     | [FF1622416C](<Notebook/ASUSTek Computer/K50/K50IE/4E5D16650878/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/FF1622416C>) |
| 10de:0aa3 | 1043:1cf7 | Nvidia           | MCP79 Co-processor                   | 38    | nvidia     | [707377026F](<Notebook/ASUSTek Computer/K50/K50IN/E86107BF68EA/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/707377026F>) |
| 10de:0271 | 103c:30b7 | Nvidia           | MCP51 PMU                            | 36    |            | [7C10ABFBFF](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv6000/70E7F8480EB2/LINUXMINT-21.2/5.15.0-117-GENERIC/X86_64/7C10ABFBFF>) |
| 10de:0aa3 | 1043:1d17 | Nvidia           | MCP79 Co-processor                   | 30    | nvidia     | [1442626988](<Notebook/ASUSTek Computer/K61/K61IC/AC28E4846CC1/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/1442626988>) |
| 10de:0753 | 1043:82e2 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 28    |            | [C6B3363B76](<Desktop/ASUSTek Computer/M3N/M3N WS/E9D16F45B60B/UBUNTU-20.04/5.4.0-177-GENERIC/X86_64/C6B3363B76>) |
| 10de:0447 | 103c:30cf | Nvidia           | MCP65 SMU                            | 24    |            | [B5885A14DB](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv6500/15A688104855/ROSA-12.5.1/6.6.27-GENERIC-3ROSA2021.1-X86_64/X86_64/B5885A14DB>) |
| 8086:19e2 | 8086:0000 | Intel            | Atom Processor C3000 Series Quick... | 23    | qat_c3xxx  | [C799DC9A8C](<Desktop/Others/QDNV/QDNV01/635BCF0BB811/NIXOS-24.05/6.6.36/X86_64/C799DC9A8C>) |
| 10de:0aa3 | 1025:0222 | Nvidia           | MCP79 Co-processor                   | 22    | nvidia     | [6416D4370C](<Desktop/Packard Bell/imax/imax mini N3600/3ACD5CD736E3/ROSA-12.5/6.6.21-GENERIC-8ROSA2021.1-X86_64/X86_64/6416D4370C>) |
| 10de:0753 | 1025:0153 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 19    |            | [194DD31946](<Desktop/Acer/Aspire/Aspire X1301/907531B62DE2/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/194DD31946>) |
| 10de:0753 | 1025:0228 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 18    |            | [2E0ACC59A4](<Desktop/Acer/Aspire/Aspire X3400G/2343059D5B7C/OPENMANDRIVA-24.06/6.10.0-DESKTOP-0.RC3.1OMV2490/X86_64/2E0ACC59A4>) |
| 10de:07da | 1025:0137 | Nvidia           | MCP73 Co-processor                   | 17    |            | [904775A387](<Desktop/Gateway/MS/MS-7399/F1ECA84CF59B/GENTOO-2.13/6.1.38-GENTOO/X86_64/904775A387>) |
| 10de:0aa3 | 1043:8402 | Nvidia           | MCP79 Co-processor                   | 17    | nvidia     | [6466D5CE59](<Notebook/ASUSTek Computer/1201/1201N/B974E4A75428/LMDE-6/6.1.0-21-686/I686/6466D5CE59>) |
| 10de:0aa3 | 1462:7621 | Nvidia           | MCP79 Co-processor                   | 17    | nvidia     | [A020FE8C37](<Desktop/Medion/MS/MS-7621/526DE489C9BC/OPENSUSE-LEAP-15.6/6.4.0-150600.23.22-DEFAULT/X86_64/A020FE8C37>) |
| 10de:0543 | 1043:16a7 | Nvidia           | MCP67 Co-processor                   | 16    |            | [B04FAC9072](<Notebook/ASUSTek Computer/F5/F5N/B23EBA207D91/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/B04FAC9072>) |
| 10de:0753 | 1043:82e8 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 15    |            | [BF131F9DEF](<Desktop/ASUSTek Computer/M4/M4N72-E/1B3EFF03F1B9/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/BF131F9DEF>) |
| 10de:03f4 |           | Nvidia           | MCP61 SMU                            | 14    |            | [B22DECF77F](<Desktop/EMAXX TECHNOLOGY/EMX-MCP61D3-iCafe/EMX-MCP61D3-iCafe V2.0/24117E2C5F27/FEDORA-40/6.8.11-300.FC40.X86_64/X86_64/B22DECF77F>) |
| 10de:07da | 1462:7504 | Nvidia           | MCP73 Co-processor                   | 13    |            | [463B74620D](<Desktop/Fujitsu Siemens/MS-7504/MS-7504VP/8F73CC4E597A/DEBIAN-12/6.1.0-18-AMD64/X86_64/463B74620D>) |
| 10de:0aa3 | 1025:0168 | Nvidia           | MCP79 Co-processor                   | 13    | nvidia     | [0CB51F3E6F](<Desktop/Gateway/LX4800/LX4800-LX6810/C01856F4DDC4/ZORIN-16/5.13.0-40-GENERIC/X86_64/0CB51F3E6F>) |
| 10de:0aa3 | 103c:3651 | Nvidia           | MCP79 Co-processor                   | 13    |            | [BB10D0F283](<Notebook/Hewlett-Packard/Compaq/Compaq Mini 311-1100/BFDA6EC83E3A/DEBIAN/6.1.0-28-686-PAE/I686/BB10D0F283>) |
| 10de:0753 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 12    |            | [63D0351E00](<All In One/Acer/Aspire/Aspire Z5101/8569CA5B9C9A/LINUXMINT-22/6.8.0-45-GENERIC/X86_64/63D0351E00>) |
| 10de:0753 | 1462:6720 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 12    |            | [0F4FCA97B4](<Notebook/MSI/VR/VR630/83FCB86AC0B3/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/0F4FCA97B4>) |
| 10de:0753 | 1565:340b | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 12    |            | [07B481323C](<Desktop/Biostar/GF8200C/GF8200C M2+/962217D3B2CB/ZORIN-17/6.8.0-49-GENERIC/X86_64/07B481323C>) |
| 10de:0271 | 1025:0112 | Nvidia           | MCP51 PMU                            | 11    |            | [3094B549C5](<Notebook/Acer/Aspire/Aspire 9300/84C4AB6FB9A7/LUBUNTU-20.04/5.4.0-165-GENERIC/X86_64/3094B549C5>) |
| 10de:0753 | 1025:014d | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 11    |            | [EAF2BCC73A](<Notebook/Acer/Aspire/Aspire 7530G/1D4F56008F4B/ARCH-ROLLING/6.12.8-ARCH1-1/X86_64/EAF2BCC73A>) |
| 10de:0753 | 103c:2a81 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 11    |            | [94FE59184C](<Desktop/Hewlett-Packard/NF574AA-ABZ/NF574AA-ABZ a6734it/29F03646948B/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/94FE59184C>) |
| 10de:0753 | 1043:82e7 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 11    |            | [85960CDC58](<Desktop/ASUSTek Computer/M3N-HT/M3N-HT DELUXE/7FF10008444D/OPENSUSE-LEAP-15.6/6.4.0-150600.23.25-DEFAULT/X86_64/85960CDC58>) |
| 10de:0aa3 | 1025:0160 | Nvidia           | MCP79 Co-processor                   | 11    | nvidia     | [842AA57FAF](<Notebook/Acer/Aspire/Aspire 5737Z/364564FDA66B/UBUNTU-22.04/5.19.0-46-GENERIC/X86_64/842AA57FAF>) |
| 10de:0aa3 | 1734:1151 | Nvidia           | MCP79 Co-processor                   | 10    | nvidia     | [291861D530](<Notebook/Fujitsu Siemens/ESPRIMO/ESPRIMO Mobile V6555/30D8C3FBA8F6/LUBUNTU-24.10/6.11.0-9-GENERIC/X86_64/291861D530>) |
| 10de:0aa3 | 1b0a:0074 | Nvidia           | MCP79 Co-processor                   | 10    | nvidia     | [63778AC6E1](<Desktop/Nvidia/MCP/MCP79/182CA2CE1B78/ROSA-12.5.1/6.6.27-GENERIC-3ROSA2021.1-X86_64/X86_64/63778AC6E1>) |
| 19a2:0800 | 1734:11cc | Emulex           | ServerView iRMC HTI                  | 10    |            | [ED6A47B6F9](<Server/Fujitsu/PRIMERGY/PRIMERGY TX2540 M1/6D63F93EE5A2/DEBIAN-12/6.11.10+BPO-AMD64/X86_64/ED6A47B6F9>) |
| 10de:03f4 | 1043:8234 | Nvidia           | MCP61 SMU                            | 9     |            | [56DB54E530](<Desktop/ASUSTek Computer/M2/M2N/64A18C11057B/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/56DB54E530>) |
| 10de:0543 | 1849:0543 | Nvidia           | MCP67 Co-processor                   | 9     |            | [D9171BEDD5](<Desktop/ASRock/N68/N68PV-GS/6BB6DCC2C405/ROSA-12.4/6.1.38-GENERIC-1ROSA2021.1-X86_64/X86_64/D9171BEDD5>) |
| 10de:0aa3 | 1462:1012 | Nvidia           | MCP79 Co-processor                   | 9     | nvidia     | [28EEB3BD71](<Notebook/MSI/CR/CR500/6DF9B5823E93/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/28EEB3BD71>) |
| 10de:0aa3 | 1462:4570 | Nvidia           | MCP79 Co-processor                   | 9     | nvidia     | [F7CB25FE9C](<All In One/MSI/MS/MS-6657/91327E5DD924/ZORIN-17/6.8.0-48-GENERIC/X86_64/F7CB25FE9C>) |
| 10de:0aa3 | 1849:0aa3 | Nvidia           | MCP79 Co-processor                   | 9     | nvidia     | [60C4DBCB14](<Desktop/ASRock/AMCP7/AMCP7A-ION/85645E42E981/UBUNTU-22.04/6.5.0-21-GENERIC/X86_64/60C4DBCB14>) |
| 8086:2710 | 8086:0000 | Intel            | HQM/DLB                              | 9     |            | [4CE14B1603](<Desktop/Supermicro/SYS-121/SYS-121H-TNR/7BBB90FD1FB9/DEBIAN-12/6.1.0-26-AMD64/X86_64/4CE14B1603>) |
| 10de:0543 | 103c:30d6 | Nvidia           | MCP67 Co-processor                   | 8     |            | [957EC4CC30](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv2700/C599A83AE3C7/MX-23/6.1.0-17-686-PAE/I686/957EC4CC30>) |
| 10de:0753 | 1025:0227 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 8     |            | [2374672493](<Desktop/Acer/Aspire/Aspire X3300/D87EE4549015/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/2374672493>) |
| 10de:07da | 1462:736b | Nvidia           | MCP73 Co-processor                   | 8     |            | [0FE38A33D1](<Desktop/Medion/MS/MS-7366/42E0B4424A0F/ZORIN-17/6.8.0-47-GENERIC/X86_64/0FE38A33D1>) |
| 10de:0aa3 | 105b:0d52 | Nvidia           | MCP79 Co-processor                   | 8     | nvidia     | [E20A015B3A](<Desktop/Foxconn/nT-330/nT-330i/17BF34BFC5F8/UBUNTU-22.04/6.2.0-37-GENERIC/X86_64/E20A015B3A>) |
| 10de:0271 | 103c:30b5 | Nvidia           | MCP51 PMU                            | 7     |            | [1FBCCB2F58](<Notebook/Hewlett-Packard/Presario/Presario V3000/C635D3859D05/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/1FBCCB2F58>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c3a | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 1834  | mei_me     | [2B21C81822](<Desktop/ASUSTek Computer/P8Z68-V/P8Z68-V LX/4130A0D4D84A/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/2B21C81822>) |
| 8086:8c3a | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 1633  | mei_me     | [C4C2F7FE89](<Desktop/ASUSTek Computer/All/All Series/09DD706491D9/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/C4C2F7FE89>) |
| 8086:319a | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1460  | mei_me     | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:a13a | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 1389  | mei_me     | [FF2E84AB02](<Desktop/ASUSTek Computer/H110/H110M-E-M.2/4907896789F3/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/FF2E84AB02>) |
| 8086:1e3a | 1043:84ca | Intel            | 7 Series/C216 Chipset Family MEI ... | 1268  | mei_me     | [69679C9A35](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/05DEE4E22315/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/69679C9A35>) |
| 8086:1c3a | 1458:1c3a | Intel            | 6 Series/C200 Series Chipset Fami... | 1136  | mei_me     | [2EF34839F4](<Desktop/Gigabyte Technology/H61/H61M-DS2/29D58848E162/ZORIN-17/6.5.0-18-GENERIC/X86_64/2EF34839F4>) |
| 8086:8c3a | 1458:1c3a | Intel            | 8 Series/C220 Series Chipset Fami... | 1107  | mei_me     | [27053CA724](<Desktop/Gigabyte Technology/B85/B85M-D3H/C42183E26685/DEBIAN-12/6.1.0-28-AMD64/X86_64/27053CA724>) |
| 8086:a2ba | 1043:8694 | Intel            | 200 Series PCH CSME HECI #1          | 1028  | mei_me     | [10FD8EF9DD](<Desktop/ASUSTek Computer/TUF/TUF Z370-PLUS GAMING II/76981D36E1E4/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/10FD8EF9DD>) |
| 8086:1c3a | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 982   | mei_me     | [705713446F](<Notebook/Apple/MacBookAir4/MacBookAir4,1/0A918C18E48D/MANJARO/6.12.4-1-MANJARO/X86_64/705713446F>) |
| 8086:1e3a | 8086:7270 | Intel            | 7 Series/C216 Chipset Family MEI ... | 966   | mei_me     | [AE5A71DDE0](<Notebook/Apple/MacBookPro9/MacBookPro9,1/04AD065CAD6F/LINUXMINT-20.3/5.4.0-204-GENERIC/X86_64/AE5A71DDE0>) |
| 8086:1e3a | 1458:1c3a | Intel            | 7 Series/C216 Chipset Family MEI ... | 961   | mei_me     | [139B1D261D](<Desktop/Gigabyte Technology/B75/B75M-D3H/1C75C0A003F1/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/139B1D261D>) |
| 8086:a2ba | 1458:1c3a | Intel            | 200 Series PCH CSME HECI #1          | 939   | mei_me     | [A49FDE4DF3](<Desktop/Gigabyte Technology/B365M/B365M DS3H/406A103EBD76/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/A49FDE4DF3>) |
| 8086:1e3a | 17aa:3977 | Intel            | 7 Series/C216 Chipset Family MEI ... | 926   | mei_me     | [516947871E](<Notebook/Lenovo/IdeaPad/IdeaPad Z400 VIWZ1/2725496AFD2D/ZORIN-17/6.8.0-50-GENERIC/X86_64/516947871E>) |
| 8086:5a9a | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 864   | mei_me     | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 8086:a360 | 1043:8694 | Intel            | Cannon Lake PCH HECI Controller      | 825   | mei_me     | [D6E8F1EE6C](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-P/DD926E3C669B/LMDE-6/6.11.10+BPO-AMD64/X86_64/D6E8F1EE6C>) |
| 8086:a13a | 1458:1c3a | Intel            | 100 Series/C230 Series Chipset Fa... | 813   | mei_me     | [AD40DB7F67](<Desktop/Gigabyte Technology/Z170X-Gaming/Z170X-Gaming 7/4DE1A28702A7/ZORIN-17/6.8.0-50-GENERIC/X86_64/AD40DB7F67>) |
| 8086:9cba | 8086:7270 | Intel            | Wildcat Point-LP MEI Controller #1   | 755   | mei_me     | [0699689325](<Notebook/Apple/MacBookPro12/MacBookPro12,1/B130D1C2EC2D/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/0699689325>) |
| 8086:9d3a | 8086:7270 | Intel            | Sunrise Point-LP CSME HECI #1        | 703   | mei_me     | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:a360 | 1458:1c3a | Intel            | Cannon Lake PCH HECI Controller      | 679   | mei_me     | [639EB0E4FC](<Desktop/Gigabyte Technology/H370M/H370M D3H GSM/D391F95DF729/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/639EB0E4FC>) |
| 8086:8cba | 1043:8534 | Intel            | 9 Series Chipset Family ME Interf... | 662   | mei_me     | [BA47136806](<Desktop/ASUSTek Computer/All/All Series/651BB16BD9C9/UBUNTU-24.10/6.12.3-061203-GENERIC/X86_64/BA47136806>) |
| 8086:3b64 | 17aa:215f | Intel            | 5 Series/3400 Series Chipset HECI... | 630   | mei_me     | [ECF4A20D48](<Notebook/Lenovo/ThinkPad/ThinkPad T510 4313A11/2CE2156B4537/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/ECF4A20D48>) |
| 8086:9c3a | 17aa:3978 | Intel            | 8 Series HECI #0                     | 604   | mei_me     | [666751867C](<Notebook/Lenovo/G50-70/G50-70 20351/1934A760E88D/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/666751867C>) |
| 8086:9c3a | 8086:7270 | Intel            | 8 Series HECI #0                     | 590   | mei_me     | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 8086:8c3a | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 573   | mei_me     | [5DCD5ABFD5](<Notebook/Apple/MacBookPro11/MacBookPro11,3/C815F183754B/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/5DCD5ABFD5>) |
| 8086:7ae8 | 1043:8694 | Intel            | Alder Lake-S PCH HECI Controller #1  | 561   | mei_me     | [F8371D3425](<Desktop/ASUSTek Computer/PRIME/PRIME B660M-A WIFI D4/08AB6A0E635D/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/F8371D3425>) |
| 8086:43e0 | 1043:8694 | Intel            | Tiger Lake-H Management Engine In... | 555   | mei_me     | [63751B6A23](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z590-E GAMING WIFI/802DD0234B9E/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/63751B6A23>) |
| 8086:8c3a | 1849:8c3a | Intel            | 8 Series/C220 Series Chipset Fami... | 485   | mei_me     | [63308A03E7](<Desktop/ASRock/H81/H81M-DG4/317D2002702A/ARCH-ROLLING/6.12.7-ARCH1-1/X86_64/63308A03E7>) |
| 8086:1c3a | 17aa:3975 | Intel            | 6 Series/C200 Series Chipset Fami... | 484   | mei_me     | [E12DDDCD7F](<Notebook/Lenovo/IdeaPad/IdeaPad Z570 HuronRiver Platform/D2573C3CE84C/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/E12DDDCD7F>) |
| 8086:8cba | 1458:1c3a | Intel            | 9 Series Chipset Family ME Interf... | 482   | mei_me     | [381B6FC010](<Desktop/Gigabyte Technology/Z97/Z97X-UD5H/5500A52DF6D9/ZORIN-17/6.8.0-50-GENERIC/X86_64/381B6FC010>) |
| 8086:43e0 | 1458:1c3a | Intel            | Tiger Lake-H Management Engine In... | 460   | mei_me     | [F43945B8DD](<Desktop/Gigabyte Technology/B560M/B560M AORUS PRO/81CCD1D8C2D3/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/F43945B8DD>) |
| 8086:1e3a | 1028:0577 | Intel            | 7 Series/C216 Chipset Family MEI ... | 453   | mei_me     | [734E205226](<Desktop/Dell/OptiPlex/OptiPlex 7010/1CD0F71C8C43/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/734E205226>) |
| 8086:1c3a | 1849:1c3a | Intel            | 6 Series/C200 Series Chipset Fami... | 450   | mei_me     | [313D81DA9F](<Desktop/ASRock/H61/H61M-S/3EA1E0670831/LINUXMINT-22/6.12.8-1-LIQUORIX-AMD64/X86_64/313D81DA9F>) |
| 8086:2a44 | 17aa:20e6 | Intel            | Mobile 4 Series Chipset MEI Contr... | 442   | mei_me     | [DD61C503C2](<Notebook/Lenovo/ThinkPad/ThinkPad R400 7440EL1/F1D459BBE0DA/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/DD61C503C2>) |
| 8086:a2ba | 1849:a2ba | Intel            | 200 Series PCH CSME HECI #1          | 432   | mei_me     | [DC5750E7FC](<Desktop/ASRock/B250/B250 Gaming K4/31792D99A259/UBUNTU-20.04/5.4.0-204-GENERIC/X86_64/DC5750E7FC>) |
| 8086:9d3e |           | Intel            | iTouch Controller                    | 420   | mei_me     | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:8c3a | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 381   | mei_me     | [F722EDF7A9](<Desktop/Dell/OptiPlex/OptiPlex 9020/DEAD93BBE620/LUBUNTU-22.04/6.8.0-50-GENERIC/X86_64/F722EDF7A9>) |
| 8086:9d3a | 17aa:225d | Intel            | Sunrise Point-LP CSME HECI #1        | 371   | mei_me     | [C35541E56B](<Notebook/Lenovo/ThinkPad/ThinkPad T480 20L5S1S000/9025AC5E126D/DEBIAN-12/6.1.0-28-AMD64/X86_64/C35541E56B>) |
| 8086:1e3a | 17aa:21f3 | Intel            | 7 Series/C216 Chipset Family MEI ... | 369   | mei_me     | [AFCCA700DA](<Notebook/Lenovo/ThinkPad/ThinkPad T430 2349H2G/B337DB6D1388/ZORIN-17/6.8.0-50-GENERIC/X86_64/AFCCA700DA>) |
| 8086:8c3a | 1462:7817 | Intel            | 8 Series/C220 Series Chipset Fami... | 352   | mei_me     | [CE0086EC71](<Desktop/MSI/MS/MS-7817/CD2BE804A24A/UBUNTU-24.10/6.11.0-13-GENERIC/X86_64/CE0086EC71>) |
| 8086:a13a | 1849:a13a | Intel            | 100 Series/C230 Series Chipset Fa... | 350   | mei_me     | [D9985EBE4E](<Desktop/ASRock/H110/H110M-ITX/F42E4DEE3FF9/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/D9985EBE4E>) |
| 8086:1e3a | 17aa:21fa | Intel            | 7 Series/C216 Chipset Family MEI ... | 346   | mei_me     | [D8B0ADF8FB](<Notebook/Lenovo/ThinkPad/ThinkPad X230 23252UG/EAF4136FB502/ARCH-ROLLING/6.6.54-1-LTS/X86_64/D8B0ADF8FB>) |
| 8086:1e3a | 1849:1e3a | Intel            | 7 Series/C216 Chipset Family MEI ... | 343   | mei_me     | [91580064A4](<Desktop/ASRock/Z75/Z75 Pro3/6FC61F332167/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/91580064A4>) |
| 8086:1c3a | 17aa:21ce | Intel            | 6 Series/C200 Series Chipset Fami... | 341   | mei_me     | [DF34CF20B9](<Notebook/Lenovo/ThinkPad/ThinkPad T420 4236PFG/968339B1DFE6/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/DF34CF20B9>) |
| 8086:a360 | 8086:7270 | Intel            | Cannon Lake PCH HECI Controller      | 340   | mei_me     | [BA278C0390](<Notebook/Apple/MacBookPro16/MacBookPro16,1/08604154B492/ALT-11.0/6.6.69-6.6-ALT1/X86_64/BA278C0390>) |
| 8086:a2ba | 1043:872f | Intel            | 200 Series PCH CSME HECI #1          | 332   | mei_me     | [026EE0FACD](<Desktop/ASUSTek Computer/Maximus/Maximus IX CODE/5FE64CFA3244/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/026EE0FACD>) |
| 8086:7a68 | 1043:8882 | Intel            | Raptor Lake CSME HECI #1             | 331   | mei_me     | [826DC3E0F2](<Desktop/iBUYPOWER/Intel/Intel Core i7-14700F/0C1A211F1578/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/826DC3E0F2>) |
| 8086:1c3a | 1028:0493 | Intel            | 6 Series/C200 Series Chipset Fami... | 304   | mei_me     | [46C2760E4E](<Notebook/Dell/Latitude/Latitude E6420/27A84812735F/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/46C2760E4E>) |
| 8086:9d3a | 103c:8079 | Intel            | Sunrise Point-LP CSME HECI #1        | 297   | mei_me     | [DA5C26013C](<Notebook/Hewlett-Packard/ZBook/ZBook 15u G3/5C8D48F3C0A5/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/DA5C26013C>) |
| 8086:8c3a | 17aa:3978 | Intel            | 8 Series/C220 Series Chipset Fami... | 296   | mei_me     | [A18BD92542](<Notebook/Lenovo/Others/Others/82BC79342496/UBUNTU-24.10/6.11.0-13-GENERIC/X86_64/A18BD92542>) |
| 8086:a328 | 8086:7270 | Intel            | Cannon Lake PCH Serial IO UART Ho... | 295   | intel_l... | [BA278C0390](<Notebook/Apple/MacBookPro16/MacBookPro16,1/08604154B492/ALT-11.0/6.6.69-6.6-ALT1/X86_64/BA278C0390>) |

### Digitizer pen (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a0d0 | 8086:2097 | Intel            | Tiger Lake-LP Precise Touch and S... | 53    | ithc       | [27E1A6B6C4](<Notebook/Intel Client Systems/LAPBC/LAPBC710/51F1A07EBDE7/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/27E1A6B6C4>) |
| 8086:51d0 | 103c:8a28 | Intel            | Alder Lake-U Smart Sound Technolo... | 22    | ithc       | [34BC9A0466](<Convertible/Hewlett-Packard/ENVY/ENVY x360 2-in-1 Laptop 13-bf0xxx/3757185C9397/NIXOS-24.11/6.11.0/X86_64/34BC9A0466>) |
| 8086:a0d0 | 1414:0055 | Intel            | Tiger Lake-LP Precise Touch and S... | 17    | ithc       | [0B901FDA6F](<Tablet/Microsoft/Surface/Surface Pro 8/2ECF330FF091/FEDORA-40/6.8.5-301.FC40.X86_64/X86_64/0B901FDA6F>) |
| 8086:a0d0 | 1414:0056 | Intel            | Tiger Lake-LP Precise Touch and S... | 10    | ithc       | [DA3534B096](<Tablet/Microsoft/Surface/Surface Pro 7+/87B1E5086B44/DEBIAN-12/6.1.0-28-AMD64/X86_64/DA3534B096>) |
| 8086:51d0 | 1414:0064 | Intel            | Alder Lake-U Smart Sound Technolo... | 9     | ithc       | [E6F037A5E8](<Tablet/Microsoft/Surface/Surface Pro 9/9EE1E883AC5A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E6F037A5E8>) |
| 8086:a0d0 | 1414:0049 | Intel            | Tiger Lake-LP Precise Touch and S... | 9     | ithc       | [79C895B3A3](<Tablet/Microsoft/Surface/Surface Laptop Studio/7EAF7CBE4A58/FEDORA-40/6.10.10-1.SURFACE.FC40.X86_64/X86_64/79C895B3A3>) |
| 8086:51d0 |           | Intel            | Alder Lake-U Smart Sound Technolo... | 8     |            | [79A6B9C168](<Notebook/Intel Client Systems/LAPRC/LAPRC710/AA001D00E680/FEDORA-40/6.8.8-300.FC40.X86_64/X86_64/79A6B9C168>) |
| 8086:a0d0 | 1414:0052 | Intel            | Tiger Lake-LP Precise Touch and S... | 8     | ithc       | [1FA8DA20AD](<Tablet/Microsoft/Surface/Surface Laptop 4/FAA9CF059CA5/ZORIN-17/6.5.0-41-GENERIC/X86_64/1FA8DA20AD>) |
| 8086:a0d0 | 1414:0053 | Intel            | Tiger Lake-LP Precise Touch and S... | 4     |            | [70C6936CFC](<Tablet/Microsoft/Surface/Surface Laptop 4/A358A0E16EED/PARROT-5.3/6.1.0-1PARROT1-AMD64/X86_64/70C6936CFC>) |
| 8086:51d0 | 1414:0077 | Intel            | Alder Lake-U Smart Sound Technolo... | 1     | ithc       | [DC4244CAAE](<Tablet/Microsoft/Surface/Surface Laptop Studio 2/442DCC14A3B5/DEBIAN-12/6.9.3-SURFACE-2/X86_64/DC4244CAAE>) |
| 8086:51d1 | 8086:7270 | Intel            | Digitizer Pen                        | 1     | ithc       | [DC4244CAAE](<Tablet/Microsoft/Surface/Surface Laptop Studio 2/442DCC14A3B5/DEBIAN-12/6.9.3-SURFACE-2/X86_64/DC4244CAAE>) |
| 8086:7e49 | 8086:7270 | Intel            | Digitizer Pen                        | 1     |            | [EFACE5275D](<Notebook/Lenovo/ThinkBook/ThinkBook 13x G4 IMH 21KR/29272013E591/FEDORA-41/6.9.0-0.RC5.20240426GITC942A0CD3603.48.FC41.X86_64/X86_64/EFACE5275D>) |
| 8086:98d0 |           | Intel            | Precise Touch and Stylus Port #1     | 1     |            | [A06677F6EA](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Fold Gen 1 20RL000GIX/E29339E09DD9/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/A06677F6EA>) |

### Dma controller (eisa dma) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9ce0 | 8086:9ce0 | Intel            | Wildcat Point-LP Serial IO DMA Co... | 691   | dw_dmac... | [0699689325](<Notebook/Apple/MacBookPro12/MacBookPro12,1/B130D1C2EC2D/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/0699689325>) |
| 8086:9c60 |           | Intel            | 8 Series Low Power Sub-System DMA    | 215   | dw_dmac... | [DFB4117F5C](<Notebook/Apple/MacBookAir6/MacBookAir6,2/BBD1819D044E/FEDORA-41/6.8.5-301.FC40.X86_64/X86_64/DFB4117F5C>) |
| 8086:22c0 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 37    | dw_dmac... | [7A4E426512](<Mini Pc/Intel/NUC5PGYB/NUC5PGYB H78167-102/E551A2C0F3DD/VANILLA-2.0/6.10.9-AMD64/X86_64/7A4E426512>) |
| 8086:2286 | 1025:106d | Intel            | Atom/Celeron/Pentium Processor x5... | 14    | dw_dmac... | [C27978FDC4](<Notebook/Acer/Aspire/Aspire one 1-431/D0580E255C52/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C27978FDC4>) |
| 8086:22c0 | 1025:106d | Intel            | Atom/Celeron/Pentium Processor x5... | 14    | dw_dmac... | [C27978FDC4](<Notebook/Acer/Aspire/Aspire one 1-431/D0580E255C52/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C27978FDC4>) |
| 8086:9c60 | 1025:0a11 | Intel            | 8 Series Low Power Sub-System DMA    | 14    | dw_dmac... | [E797F3CCB1](<Notebook/Acer/Peppy/Peppy/618C60308675/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/E797F3CCB1>) |
| 8086:9c60 | 103c:21ed | Intel            | 8 Series Low Power Sub-System DMA    | 5     | dw_dmac... | [F270F62D2C](<Notebook/Hewlett-Packard/Falco/Falco/AA55B2374927/ALMA-9.4/5.14.0-427.42.1.EL9_4.X86_64/X86_64/F270F62D2C>) |
| 8086:0f40 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 4     | dw_dmac... | [B02AD54B70](<Desktop/Intel/Minnow/Minnow Max/D50A99A428B9/DTS-DISTRO-1.2.21/6.6.21-YOCTO-STANDARD/X86_64/B02AD54B70>) |
| 8086:2286 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 4     | dw_dmac... | [AF10F30C79](<Notebook/Synology/DS216/DS216+/7B444A3AFE7A/DSM-7/3.10.108/X86_64/AF10F30C79>) |
| 8086:0f40 | 8086:0f40 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     | dw_dmac... | [62ECBE2F01](<Mini Pc/AMI/Aptio/Aptio CRB/A98F6B3CA080/LUBUNTU-18.04/5.4.0-150-GENERIC/X86_64/62ECBE2F01>) |
| 8086:2286 | 1025:106c | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | dw_dmac... | [EA5065EF8F](<Notebook/Acer/Aspire/Aspire one 1-131/216FCF05E9ED/LUBUNTU-22.04/5.19.0-35-GENERIC/X86_64/EA5065EF8F>) |
| 8086:22c0 | 1025:106c | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | dw_dmac... | [EA5065EF8F](<Notebook/Acer/Aspire/Aspire one 1-131/216FCF05E9ED/LUBUNTU-22.04/5.19.0-35-GENERIC/X86_64/EA5065EF8F>) |
| 8086:22c0 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | dw_dmac... | [B31E10D01B](<Desktop/WesternDigital/WDBNFA0000/WDBNFA0000NBK-00/20416017F55E/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B31E10D01B>) |
| 8086:0f06 |           | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | dw_dmac... | [8FE291470D](<Mini Pc/NEXCOM/VTC/VTC1010/03C726F79B18/LUBUNTU-22.04/5.15.0-33-GENERIC/X86_64/8FE291470D>) |
| 8086:0f06 | 8086:0f06 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | dw_dmac... | [62ECBE2F01](<Mini Pc/AMI/Aptio/Aptio CRB/A98F6B3CA080/LUBUNTU-18.04/5.4.0-150-GENERIC/X86_64/62ECBE2F01>) |
| 8086:0f06 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | dw_dmac... | [B02AD54B70](<Desktop/Intel/Minnow/Minnow Max/D50A99A428B9/DTS-DISTRO-1.2.21/6.6.21-YOCTO-STANDARD/X86_64/B02AD54B70>) |
| 8086:2286 | 1025:1151 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | dw_dmac... | [9D7F73242E](<Notebook/Acer/Swift/Swift SF114-31/74FE02757B84/KUBUNTU-22.10/5.19.0-31-GENERIC/X86_64/9D7F73242E>) |
| 8086:22c0 | 1025:1151 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | dw_dmac... | [9D7F73242E](<Notebook/Acer/Swift/Swift SF114-31/74FE02757B84/KUBUNTU-22.10/5.19.0-31-GENERIC/X86_64/9D7F73242E>) |
| 8086:0f06 | 8086:2056 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     |            | [D4408F7B0E](<Desktop/Intel/DE3815TYKH/DE3815TYKH H26998-403/3CECC7AD024C/DEBIAN-10/4.19.0-14-AMD64/X86_64/D4408F7B0E>) |
| 8086:0f40 |           | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | dw_dmac... | [6B1A282C17](<Notebook/Dell/Inspiron/Inspiron 11 - 3147/CACF61202444/UBUNTU-22.04/5.13.0-19-GENERIC/X86_64/6B1A282C17>) |
| 8086:0f40 | 1025:0936 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | dw_dmac... | [F0ED67E309](<Notebook/Acer/Aspire/Aspire ES1-512/47D40775F1A1/XUBUNTU-22.04/5.15.0-27-GENERIC/X86_64/F0ED67E309>) |
| 8086:0f40 | 1025:0939 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | dw_dmac... | [C431BDD246](<Notebook/Packard Bell/EasyNote/EasyNote ENLG71BM/08568073F730/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/C431BDD246>) |
| 8086:0f40 | 1025:093f | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | dw_dmac... | [9A69B50D97](<Notebook/Acer/Aspire/Aspire E5-411G/06C473B1276E/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/9A69B50D97>) |
| 8086:0f40 | 1028:06d7 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | dw_dmac... | [480A5F421A](<Notebook/Dell/Inspiron/Inspiron 5551/EF07C2A9A218/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/480A5F421A>) |
| 8086:0f40 | 103c:8023 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | dw_dmac... | [49E4112B11](<Notebook/Hewlett-Packard/Stream/Stream Notebook PC 11/3E7C464CEDB5/UBUNTU-18.04/5.4.0-87-GENERIC/X86_64/49E4112B11>) |
| 8086:0f40 | 1170:9991 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | dw_dmac... | [B5C89FA6C1](<Notebook/Medion/Akoya/Akoya THE TOUCH 10/EA70D95D695A/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/B5C89FA6C1>) |
| 8086:0f40 | 17aa:3908 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | dw_dmac... | [0128495D83](<Notebook/Lenovo/Yoga/Yoga 300-11IBY 80M0/7BE67AE249B2/LINUXMINT-20.2/5.4.0-88-GENERIC/X86_64/0128495D83>) |
| 8086:0f40 | 8086:2056 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     |            | [D4408F7B0E](<Desktop/Intel/DE3815TYKH/DE3815TYKH H26998-403/3CECC7AD024C/DEBIAN-10/4.19.0-14-AMD64/X86_64/D4408F7B0E>) |
| 8086:2286 | 10f7:8338 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | dw_dmac... | [BEEB215141](<Tablet/Panasonic/FZB2/FZB2-2/BA668A2C2665/ANTIX-23.1/6.1.105-ANTIX.1-AMD64-SMP/X86_64/BEEB215141>) |
| 8086:22c0 | 1025:0998 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | dw_dmac... | [D6FE7992F3](<Notebook/Acer/Aspire/Aspire E5-432G/AC90092C4CCA/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/D6FE7992F3>) |
| 8086:22c0 | 10f7:8338 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | dw_dmac... | [BEEB215141](<Tablet/Panasonic/FZB2/FZB2-2/BA668A2C2665/ANTIX-23.1/6.1.105-ANTIX.1-AMD64-SMP/X86_64/BEEB215141>) |
| 8086:9c60 | 1028:0a35 | Intel            | 8 Series Low Power Sub-System DMA    | 1     | dw_dmac... | [8FC168EBA7](<Notebook/Dell/Wolf/Wolf/D968E70C0BBE/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/8FC168EBA7>) |

### Dpio module (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 012d:4d4c | 10b5:9080 |                  | DPIO module                          | 1     |            | [D88A4D7D31](<Desktop/OEM/Others/Others/2CCC9BBC64D0/UBUNTU-19.04/5.0.0-15-GENERIC/X86_64/D88A4D7D31>) |
| 10b5:9050 | ddd1:0001 | PLX Technology   | PCI <-> IOBus Bridge                 | 1     |            | [117638721D](<Desktop/Gigabyte Technology/8IK1100/8IK1100/7972F89846AB/ROSA-2016.1/4.9.20-NRJ-DESKTOP-1ROSA-I586/I686/117638721D>) |
| 144a:7250 | 144a:7250 | ADLINK Techno... | PCI-7250                             | 1     |            | [A3C369DB65](<Desktop/ASUSTek Computer/P7P55/P7P55 WS SUPERCOMPUTER/E76C5BB93D82/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/A3C369DB65>) |
| 2718:5125 | 2718:5125 |                  | DPIO module                          | 1     |            | [B8D373B07E](<Desktop/ASUSTek Computer/H170I-PLUS/H170I-PLUS D3/17849F8BF79E/DEBIAN-9/4.9.0-19-RT-AMD64/X86_64/B8D373B07E>) |

### Dvb card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 13d0:2103 | 13d0:2103 | Techsan Elect... | B2C2 FlexCopII DVB chip / Technis... | 91    | b2c2_fl... | [26E848809D](<Desktop/ASUSTek Computer/P8/P8P67/8020FC643B81/PEPPERMINT-12/6.1.0-28-AMD64/X86_64/26E848809D>) |
| 1131:7146 | 13c2:1018 | Philips Semic... | SAA7146                              | 28    | budget     | [3470A0F79B](<Desktop/Gigabyte Technology/P41/P41T-D3P/6D9A707E2A5C/OPENSUSE-LEAP-15.6/6.4.0-150600.4-DEFAULT/X86_64/3470A0F79B>) |
| 1131:7146 | 13c2:0003 | Philips Semic... | SAA7146                              | 8     | dvb_ttpci  | [EBD8E172D8](<Desktop/ASUSTek Computer/M5A97/M5A97 R2.0/272A6CE917E4/POP!_OS-22.04/6.8.0-76060800DAILY20240311-GENERIC/X86_64/EBD8E172D8>) |
| 1131:7146 | 13c2:101a | Philips Semic... | SAA7146                              | 8     | budget_ci  | [EA20CECD28](<Desktop/ASUSTek Computer/M2N-VM/M2N-VM HDMI/A1035B0C9DEA/ROSA-12.4/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/EA20CECD28>) |
| 109e:0878 | 1822:0001 | Brooktree        | Bt878 Audio Capture                  | 7     | bt878      | [8CE355C181](<Desktop/ASUSTek Computer/Commando/Commando/A6F0BB02EDAA/UBUNTU-20.04/5.11.0-44-GENERIC/X86_64/8CE355C181>) |
| 14f1:8802 | 0070:9002 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 7     | cx88_dvb   | [921F2AAC12](<Desktop/Gigabyte Technology/H170-HD3/H170-HD3 DDR3-CF/5A37201BF35B/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/921F2AAC12>) |
| 1131:7146 | 13c2:1019 | Philips Semic... | SAA7146                              | 6     | budget_ci  | [42F7ED38BB](<Desktop/ASUSTek Computer/M5/M5A78L-USB3/D53DE27D2523/UBUNTU-24.04/6.8.0-40-GENERIC/X86_64/42F7ED38BB>) |
| 109e:0878 | 11bd:001c | Brooktree        | Bt878 Audio Capture                  | 4     | bt878      | [17A2F79F3F](<Desktop/Hewlett-Packard/Compaq/Compaq 6200 Pro MT PC/7AF3849C0C3B/LINUXMINT-21/5.15.0-48-GENERIC/X86_64/17A2F79F3F>) |
| 1131:7146 | 1894:0022 | Philips Semic... | SAA7146                              | 3     | budget_av  | [B7CC817ED7](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LE/0ED84C66B2B9/LINUXMINT-22/6.8.0-41-GENERIC/X86_64/B7CC817ED7>) |
| 109e:0878 | 1461:0771 | Brooktree        | Bt878 Audio Capture                  | 2     | bt878      | [AB87264048](<Desktop/Gigabyte Technology/GA-990/GA-990FXA-UD3/E8619E62E43B/KDE-NEON-20.04/5.4.0-73-GENERIC/X86_64/AB87264048>) |
| 1131:7146 | 153b:1156 | Philips Semic... | SAA7146                              | 2     | budget_av  | [5714C771CF](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 6.0/6AA7E1DCE287/KDE-NEON-20.04/5.11.0-46-GENERIC/X86_64/5714C771CF>) |
| 14f1:8802 | 17de:08a6 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 2     | cx88_dv... | [D932872569](<Desktop/ASUSTek Computer/M5/M5A78L-M-USB3/0025C6AEE254/UBUNTU-20.04/5.4.0-29-GENERIC/X86_64/D932872569>) |
| 195d:1105 | 195d:1105 |                  | PCI 2002 DVB-S BDA Device            | 2     | dm1105     | [4AEC213A10](<Desktop/H61M/5123660003/5123660003/7801115B9A5D/UBUNTU-MATE-18.04/5.4.0-66-GENERIC/X86_64/4AEC213A10>) |
| 1131:7146 | 1131:4f56 | Philips Semic... | SAA7146                              | 1     | budget_av  | [B220FD9C11](<Desktop/Fujitsu Siemens/SCENIC/SCENIC T/942B46D683B9/UBUNTU-18.04/4.15.0-65-GENERIC/I686/B220FD9C11>) |
| 1131:7146 | 13c2:000a | Philips Semic... | SAA7146                              | 1     | dvb_ttpci  | [9A76597218](<Desktop/Gigabyte Technology/Z77/Z77X-D3H/0FB804072D9B/UBUNTU-20.04/5.8.0-59-LOWLATENCY/X86_64/9A76597218>) |
| 1131:7146 | 13c2:000e | Philips Semic... | SAA7146                              | 1     | dvb_ttpci  | [2A21A99A38](<Desktop/ASUSTek Computer/All/All Series/F0C3AA9AE2B7/ROSA-2014.1/4.1.19-NRJ-DESKTOP-2ROSA-X86_64/X86_64/2A21A99A38>) |
| 1131:7146 | 13c2:1013 | Philips Semic... | SAA7146                              | 1     | budget     | [9FAA5F07EB](<Desktop/EVGA/Z790/Z790 DARK KINGPIN/C941F62BEA43/VOID-ROLLING/6.5.7_1/X86_64/9FAA5F07EB>) |
| 1131:7146 | 13c2:101c | Philips Semic... | SAA7146                              | 1     | budget     | [2E1316FB48](<Desktop/ASUSTek Computer/M5A97/M5A97 R2.0/387895D156D4/MANJARO-23.0.2/6.5.3-1-MANJARO/X86_64/2E1316FB48>) |
| 1131:7146 | 153b:1154 | Philips Semic... | SAA7146                              | 1     | budget_av  | [D949336ED1](<Desktop/ASUSTek Computer/P5/P5KPL-C/986174DB578E/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/D949336ED1>) |
| 1131:7146 | 153b:1176 | Philips Semic... | SAA7146                              | 1     | budget_av  | [E2EE931DF2](<Desktop/ASUSTek Computer/A78/A78M-A/FBD31929FB69/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.12-1-DEFAULT/X86_64/E2EE931DF2>) |
| 1131:7146 | 1894:0014 | Philips Semic... | SAA7146                              | 1     | budget_av  | [18E1DA8CCE](<Desktop/Biostar/B350/B350GT5/6B57AAE9A1B9/LINUXMINT-21.1/5.19.0-43-GENERIC/X86_64/18E1DA8CCE>) |
| 1131:7146 | 1894:0021 | Philips Semic... | SAA7146                              | 1     | budget_av  | [0FF4F2CB79](<Desktop/Gigabyte Technology/GA-MA790/GA-MA790GPT-UD3H/AB6C890BFEA0/UBUNTU-23.10/6.5.0-14-GENERIC/X86_64/0FF4F2CB79>) |
| 1131:7146 | 1894:0023 | Philips Semic... | SAA7146                              | 1     | budget_av  | [89B2CF7E4F](<Desktop/ABIT/KN8/KN8 Series/21B36BD60D6B/UBUNTU-22.04/5.15.0-94-GENERIC/X86_64/89B2CF7E4F>) |
| 13d0:2103 | ffff:ffff | Techsan Elect... | B2C2 FlexCopII DVB chip / Technis... | 1     | b2c2_fl... | [7609423845](<Desktop/Olidata/ALICON/ALICON 4/554D1F80B624/UBUNTU-20.04/5.8.0-44-GENERIC/X86_64/7609423845>) |
| 14f1:8802 | 7063:3000 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 1     | cx8802     | [DFC53E2C91](<Desktop/Hewlett-Packard/Z400/Z400 Workstation/CF3391D75B57/DEBIAN-12/6.1.0-12-AMD64/X86_64/DFC53E2C91>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15df | 1022:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 7360  | ccp        | [69FF87B949](<Desktop/Gigabyte Technology/A520/A520 AORUS ELITE/81AB90394B6C/GENTOO-2.17/6.6.67-GENTOO/X86_64/69FF87B949>) |
| 1022:1486 | 1022:1486 | AMD              | Starship/Matisse Cryptographic Co... | 4685  | ccp        | [726B65D6E8](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.10/4.18.0-553.27.1.EL8_10.X86_64/X86_64/726B65D6E8>) |
| 1022:1456 | 1022:1456 | AMD              | Family 17h (Models 00h-0fh) Platf... | 3536  | ccp        | [A23FC83EDD](<Desktop/Gigabyte Technology/AB350/AB350-Gaming/B5A158869F92/GENTOO-2.17/6.6.67-GENTOO/X86_64/A23FC83EDD>) |
| 1022:1486 | 1043:87c0 | AMD              | Starship/Matisse Cryptographic Co... | 1788  | ccp        | [88B1C0C262](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING WIFI II/B8760FB55781/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/88B1C0C262>) |
| 1022:1649 | 1e44:1776 | AMD              | Family 19h PSP/CCP                   | 1747  | ccp        | [DFF6A36E92](<Notebook/Valve/Galileo/Galileo/3D6CF2B6536D/STEAMOS-3.6.20/6.5.0-VALVE22-1-NEPTUNE-65-G9A338ED8A75E/X86_64/DFF6A36E92>) |
| 1022:1486 | 1043:8808 | AMD              | Starship/Matisse Cryptographic Co... | 1460  | ccp        | [DF3BBDD6E6](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/5A876E9931EF/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/DF3BBDD6E6>) |
| 1022:1649 | 1022:1649 | AMD              | Family 19h PSP/CCP                   | 1411  | ccp        | [2183EB76B7](<Tablet/ONE-NETBOOK/ONEXPLAYER/ONEXPLAYER Mini Pro/F55453A23AA1/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/2183EB76B7>) |
| 1022:1456 | 1043:8747 | AMD              | Family 17h (Models 00h-0fh) Platf... | 1259  | ccp        | [CF7D50FAE1](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-K II/24E629ECD716/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/CF7D50FAE1>) |
| 8086:2298 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1251  | mei_txe    | [496C93250D](<Tablet/Chuwi/Hi10/Hi10 pro tablet/D5A4927F3C98/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/496C93250D>) |
| 1022:1578 | 1022:1578 | AMD              | Carrizo Platform Security Processor  | 1176  |            | [B8F7C2D75A](<Notebook/Google/Treeya/Treeya/8FA4145A1303/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/B8F7C2D75A>) |
| 1022:1537 | 1022:1537 | AMD              | Kabini/Mullins PSP-Platform Secur... | 910   | ccp        | [BFA66C5393](<Desktop/PC Engines/apu/apu4/E5703BF41520/DTS-DISTRO-2.1.2/6.6.21-YOCTO-STANDARD/X86_64/BFA66C5393>) |
| 1022:1649 | 1043:8877 | AMD              | Family 19h PSP/CCP                   | 767   | ccp        | [04F9FFDAB4](<Desktop/ASUSTek Computer/ROG/ROG STRIX B650-A GAMING WIFI/848E93DF68A9/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/04F9FFDAB4>) |
| 1022:15df | 1043:8809 | AMD              | Family 17h (Models 10h-1fh) Platf... | 564   | ccp        | [989A72852C](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PLUS/4495A9F18FCB/ZORIN-17/6.8.0-50-GENERIC/X86_64/989A72852C>) |
| 1022:15df | 1043:876b | AMD              | Family 17h (Models 10h-1fh) Platf... | 558   | ccp        | [4CB02F7CED](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-K/EF4B140B96CA/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/4CB02F7CED>) |
| 1022:15c7 | 1022:15c7 | AMD              | Phoenix CCP/PSP 3.0 Device           | 488   | ccp        | [046BBB97DB](<Notebook/Lenovo/IdeaPad/IdeaPad Pro 5 14APH8 83AM/E902B3B08EDD/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/046BBB97DB>) |
| 8086:0f18 | 8086:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 333   | mei_txe    | [BB72B25BF7](<Notebook/Medion/Akoya/Akoya E6240T/98F105C11F7F/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/BB72B25BF7>) |
| 1022:15df | 17aa:382a | AMD              | Family 17h (Models 10h-1fh) Platf... | 278   | ccp        | [E544B8E949](<Notebook/Lenovo/Legion/Legion 5 15ACH6H 82JU/6D4B0B0F9308/ARCO-ROLLING/6.12.6-ARCH1-1/X86_64/E544B8E949>) |
| 1022:15df | 17aa:382b | AMD              | Family 17h (Models 10h-1fh) Platf... | 270   | ccp        | [E428436322](<Notebook/Lenovo/IdeaPad/IdeaPad 3 15ALC6 82KU/EAE67903063F/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/E428436322>) |
| 8086:0f18 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 256   | mei_txe    | [0C43F7A18D](<Tablet/Wortmann AG/TERRA_PAD/TERRA_PAD_1061/2774F6C08D8F/UBUNTU-22.04/6.8.0-49-GENERIC/X86_64/0C43F7A18D>) |
| 1022:1486 | 1462:7c02 | AMD              | Starship/Matisse Cryptographic Co... | 248   | ccp        | [77E32DABCD](<Desktop/MSI/MS-7/MS-7C02/AE386F556A9D/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/77E32DABCD>) |
| 1022:15df | 17aa:3802 | AMD              | Family 17h (Models 10h-1fh) Platf... | 219   | ccp        | [C5C9A457AA](<Notebook/Lenovo/V15-ADA/V15-ADA 82C7/DF20D99E1E88/DEBIAN-12/6.1.0-28-AMD64/X86_64/C5C9A457AA>) |
| 1022:1537 | 17aa:3801 | AMD              | Kabini/Mullins PSP-Platform Secur... | 212   | ccp        | [AC16ADA090](<Notebook/Lenovo/G40-45/G40-45 80E1/9A279D34AA5C/MANJARO-24.2.1/5.15.173-1-MANJARO/X86_64/AC16ADA090>) |
| 1022:15df | 17aa:5081 | AMD              | Family 17h (Models 10h-1fh) Platf... | 212   | ccp        | [7BFAD25E97](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 1 20UES5NA00/65C9066BF452/FEDORA-40/6.8.5-301.FC40.X86_64/X86_64/7BFAD25E97>) |
| 1022:1578 | 103c:8330 | AMD              | Carrizo Platform Security Processor  | 200   |            | [57B6786860](<Notebook/Hewlett-Packard/255/255 G6 Notebook PC/59F98AE9BF7D/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/57B6786860>) |
| 1022:15df | 103c:887a | AMD              | Family 17h (Models 10h-1fh) Platf... | 190   | ccp        | [37B47880BB](<Notebook/Hewlett-Packard/Laptop/Laptop 15s-eq2xxx/911EAE7EAD9B/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/37B47880BB>) |
| 1022:15df | 17aa:5097 | AMD              | Family 17h (Models 10h-1fh) Platf... | 186   | ccp        | [46361A1B83](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20Y70038US/1722BB93FF17/ARCH-ROLLING/6.12.7-ARCH1-1/X86_64/46361A1B83>) |
| 8086:0f18 | 17aa:3905 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 182   | mei_txe    | [398CB6B840](<Notebook/Lenovo/G40-30/G40-30 80FY/0A8F1D380049/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/398CB6B840>) |
| 1022:1486 | 1462:7b86 | AMD              | Starship/Matisse Cryptographic Co... | 180   | ccp        | [89CD372074](<Desktop/MSI/MS-7/MS-7B86/3FF968BBEDE3/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/89CD372074>) |
| 1022:1578 | 103c:84ac | AMD              | Carrizo Platform Security Processor  | 167   |            | [15039E5101](<Notebook/Hewlett-Packard/Laptop/Laptop 15-db0xxx/38F1157DCC54/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/15039E5101>) |
| 1022:15df | 19e5:3e19 | AMD              | Family 17h (Models 10h-1fh) Platf... | 161   | ccp        | [287C370D01](<Notebook/HUAWEI/NBLK-WAX9/NBLK-WAX9X/20B1F2B5A2F3/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/287C370D01>) |
| 8086:0f18 | 17aa:3909 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 159   | mei_txe    | [EAA8DD18D4](<Notebook/Lenovo/IdeaPad/IdeaPad 100-15IBY 80MJ/30B76AD22206/ROSA-12.5.1/6.6.27-GENERIC-3ROSA2021.1-X86_64/X86_64/EAA8DD18D4>) |
| 1022:15df | 17aa:380d | AMD              | Family 17h (Models 10h-1fh) Platf... | 153   | ccp        | [F598642EE7](<Notebook/Lenovo/IdeaPad/IdeaPad Gaming 3 15ARH05 82EY/6FBB4CF9718F/ARCH-ROLLING/6.12.7-ZEN1-1-ZEN/X86_64/F598642EE7>) |
| 1022:15df | 1025:1455 | AMD              | Family 17h (Models 10h-1fh) Platf... | 139   | ccp        | [5D0C074A0F](<Notebook/Acer/Nitro/Nitro AN515-44/FCBB9CDE2DD2/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/5D0C074A0F>) |
| 1022:15df | 17aa:507f | AMD              | Family 17h (Models 10h-1fh) Platf... | 132   | ccp        | [F6852CBDBB](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 2 20T6002LUS/C5DF2A83869A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/F6852CBDBB>) |
| 1022:1578 | 1025:1192 | AMD              | Carrizo Platform Security Processor  | 131   |            | [48FA2FD34A](<Notebook/Acer/Aspire/Aspire A315-21/2E415FCD1FD1/UBUNTU-18.04/5.4.0-150-GENERIC/X86_64/48FA2FD34A>) |
| 1022:15df | 152d:1365 | AMD              | Family 17h (Models 10h-1fh) Platf... | 129   | ccp        | [030B263131](<Notebook/HUAWEI/BOM-WXX/BOM-WXX9/D1030F56CEDE/UBUNTU-22.04/5.15.0-25-GENERIC/X86_64/030B263131>) |
| 1022:15df | 17aa:380f | AMD              | Family 17h (Models 10h-1fh) Platf... | 129   | ccp        | [5804FCEFEE](<Notebook/Lenovo/XiaoXinAir-14API/XiaoXinAir-14API 2019 81NJ/2F8A5EE9D05E/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/5804FCEFEE>) |
| 1022:15df | 17aa:3816 | AMD              | Family 17h (Models 10h-1fh) Platf... | 129   | ccp        | [1DF5680B90](<Notebook/Lenovo/IdeaPad/IdeaPad S145-15API 81V7/06596604B5C1/ENDEAVOUROS-ROLLING/6.12.8-ARCH1-1/X86_64/1DF5680B90>) |
| 1022:15df | 17aa:3836 | AMD              | Family 17h (Models 10h-1fh) Platf... | 129   | ccp        | [271C85B332](<Notebook/Lenovo/IdeaPad/IdeaPad Gaming 3 15ACH6 82K2/139E64F0F5B5/STEAMOS-3.6.20/6.5.0-VALVE22-1-NEPTUNE-65-G9A338ED8A75E/X86_64/271C85B332>) |
| 1022:1456 | 1462:7c02 | AMD              | Family 17h (Models 00h-0fh) Platf... | 126   | ccp        | [88D10A1126](<Desktop/MSI/MS-7/MS-7C02/DD7D36D47449/LMDE-6/6.1.0-28-AMD64/X86_64/88D10A1126>) |
| 1022:1486 | 1462:7c95 | AMD              | Starship/Matisse Cryptographic Co... | 125   | ccp        | [A3C4D34290](<Desktop/MSI/MS-7/MS-7C95/D9235FBE7F06/ARCH-ROLLING/6.11.5-X64V3-XANMOD1-1-EDGE-X64V3/X86_64/A3C4D34290>) |
| 1022:15df | 1025:134d | AMD              | Family 17h (Models 10h-1fh) Platf... | 120   | ccp        | [734FD13848](<Notebook/Acer/Aspire/Aspire A315-42/3035086EFC0B/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/734FD13848>) |
| 1022:1578 | 17aa:3810 | AMD              | Carrizo Platform Security Processor  | 119   |            | [145B300A77](<Notebook/Lenovo/IdeaPad/IdeaPad 330-17AST 81D7/1F61C1F86DDD/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/145B300A77>) |
| 1022:15df | 17aa:381f | AMD              | Family 17h (Models 10h-1fh) Platf... | 119   | ccp        | [0FCBBF148B](<Notebook/Lenovo/IdeaPad/IdeaPad 5 15ARE05 81YQ/D925A5940B1E/DEBIAN-12/6.1.0-23-AMD64/X86_64/0FCBBF148B>) |
| 1022:15df | 17aa:5082 | AMD              | Family 17h (Models 10h-1fh) Platf... | 118   | ccp        | [C68A17F027](<Notebook/Lenovo/ThinkPad/ThinkPad T14s Gen 1 20UH002LUK/3790C38E2827/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/C68A17F027>) |
| 1022:15df | 1d05:109f | AMD              | Family 17h (Models 10h-1fh) Platf... | 118   | ccp        | [D1FE4C6194](<Notebook/TUXEDO/Pulse/Pulse 14 Gen1/4BA1C6A378B0/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/D1FE4C6194>) |
| 1022:15df | 17aa:3810 | AMD              | Family 17h (Models 10h-1fh) Platf... | 116   | ccp        | [33DAD31E6E](<Notebook/Lenovo/IdeaPad/IdeaPad S340-15API 81NC/8942D56644CD/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/33DAD31E6E>) |
| 1022:15df | 17aa:5094 | AMD              | Family 17h (Models 10h-1fh) Platf... | 116   | ccp        | [0BB2FA170C](<Notebook/Lenovo/ThinkPad/ThinkPad P14s Gen 2a 21A0005RUS/B39DC970E8A6/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/0BB2FA170C>) |
| 1022:1486 | 1462:7b89 | AMD              | Starship/Matisse Cryptographic Co... | 114   | ccp        | [597E16BA37](<Desktop/MSI/MS-7/MS-7B89/716384C17A3C/LINUXMINT-21.3/6.2.0-39-GENERIC/X86_64/597E16BA37>) |
| 8086:0f18 | 1849:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 114   | mei_txe    | [402FD3B060](<Desktop/ASRock/D1800/D1800B-ITX/1704145F6CB5/ROSA-12.5.1/6.9.8.XM1-ML2.K.1-XANMOD-ROSA2021.1-X86_64/X86_64/402FD3B060>) |

### Entertainment encryption device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:2082 | 1022:2082 | AMD              | Geode LX AES Security Block          | 3     | geode_r... | [9F933E3704](<Desktop/Others/Others/Others/53404B789C2F/DEBIAN-10/4.19.0-27-686/I586/9F933E3704>) |

### Ethernet controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1af4:1041 | 1af4:1100 | Red Hat          | Virtio 1.0 network device            | 15    | virtio_pci | [79EC6F96E4](<Desktop/Bochs/Others/Others/BE32418C1D7C/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/79EC6F96E4>) |

### Firewire controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 11c1:5901 | 11c1:5900 | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 2311  | firewir... | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 1106:3044 | 1043:81fe | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 1259  | firewir... | [26E848809D](<Desktop/ASUSTek Computer/P8/P8P67/8020FC643B81/PEPPERMINT-12/6.1.0-28-AMD64/X86_64/26E848809D>) |
| 104c:8024 | 1458:1000 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 1151  | firewir... | [617C102331](<Desktop/Gigabyte Technology/GA-MA770/GA-MA770T-UD3/8220651D2E86/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/617C102331>) |
| 104c:823f |           | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 606   | firewir... | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 1180:0832 | 17aa:20c7 | Ricoh            | R5C832 IEEE 1394 Controller          | 510   | firewir... | [DD61C503C2](<Notebook/Lenovo/ThinkPad/ThinkPad R400 7440EL1/F1D459BBE0DA/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/DD61C503C2>) |
| 1106:3044 | 1458:1000 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 446   | firewir... | [92B3EE2679](<Desktop/Gigabyte Technology/GA-970/GA-970A-UD3/76B14B1E4C2A/DEBIAN/6.11.10-AMD64/X86_64/92B3EE2679>) |
| 1106:3403 | 1043:8384 | VIA Technologies | VT6315 Series Firewire Controller    | 422   | firewir... | [CA1A55B77D](<Desktop/ASUSTek Computer/M4A89TD/M4A89TD PRO USB3/2F9EA67A0B11/UBUNTU-24.04/6.8.0-50-GENERIC/X86_64/CA1A55B77D>) |
| 11c1:5903 | 11c1:5900 | LSI              | FW533 [TrueFire] PCIe 1394a Contr... | 388   | firewir... | [3E1D6CE785](<Notebook/Apple/MacBook5/MacBook5,2/7D2F05FAEBD0/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/3E1D6CE785>) |
| 1106:3044 | 1106:3044 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 383   | firewir... | [2B21C81822](<Desktop/ASUSTek Computer/P8Z68-V/P8Z68-V LX/4130A0D4D84A/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/2B21C81822>) |
| 11c1:5811 | 11c1:5811 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 364   | firewir... | [BE78213991](<Notebook/Apple/MacBook3/MacBook3,1/419B94273288/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/BE78213991>) |
| 11c1:5811 | 1043:8294 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 330   | firewir... | [94F08A5066](<Desktop/ASUSTek Computer/M3A32-MVP/M3A32-MVP DELUXE/0B8C006F5B52/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/94F08A5066>) |
| 1180:e832 | 17aa:2136 | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 309   | firewir... | [ECF4A20D48](<Notebook/Lenovo/ThinkPad/ThinkPad T510 4313A11/2CE2156B4537/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/ECF4A20D48>) |
| 1102:4001 | 1102:0010 | Creative Labs    | SB Audigy FireWire Port              | 260   | firewir... | [F13D7B03F6](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V PRO/1A3FD181C749/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/F13D7B03F6>) |
| 1180:e832 | 1028:040a | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 246   | firewir... | [CE431D6DEF](<Notebook/Dell/Latitude/Latitude E6410/008BAA37A996/ZORIN-17/6.8.0-50-GENERIC/X86_64/CE431D6DEF>) |
| 1180:0832 | 1028:0233 | Ricoh            | R5C832 IEEE 1394 Controller          | 226   | firewir... | [D5DCFBC839](<Notebook/Dell/Latitude/Latitude E6400/429F04A48EEB/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/D5DCFBC839>) |
| 1106:3403 | 1849:3403 | VIA Technologies | VT6315 Series Firewire Controller    | 212   | firewir... | [86FD341A89](<Desktop/ASRock/A75/A75 Extreme6/B47300C092A7/ZORIN-17/6.8.0-50-GENERIC/X86_64/86FD341A89>) |
| 197b:2380 | 103c:161c | JMicron Techn... | IEEE 1394 Host Controller            | 207   | firewir... | [0A8D680CF0](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8460p/636CD01ADFA4/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/0A8D680CF0>) |
| 197b:2380 | 103c:179b | JMicron Techn... | IEEE 1394 Host Controller            | 196   | firewir... | [63E91F06EF](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8470p/C1D8318F6F12/BLACKPANTHER-OS-18.1/5.15.85-DESKTOP-1BP/X86_64/63E91F06EF>) |
| 1180:e832 | 17aa:21cf | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 193   | firewir... | [A7AA110E08](<Notebook/Lenovo/ThinkPad/ThinkPad W520 428426U/CD5DD673A9D6/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A7AA110E08>) |
| 104c:803a | 1025:011f | Texas Instrum... | PCIxx12 OHCI Compliant IEEE 1394 ... | 180   | firewir... | [864E664760](<Notebook/Acer/Extensa/Extensa 5220/847E4B65162A/LMDE-6/6.1.0-28-686/I686/864E664760>) |
| 104c:803a | 1179:ff00 | Texas Instrum... | PCIxx12 OHCI Compliant IEEE 1394 ... | 166   | firewir... | [A07857C808](<Notebook/Toshiba/Satellite/Satellite P200/503912185CC9/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A07857C808>) |
| 1180:e832 | 17aa:21f6 | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 157   | firewir... | [20E239CB8A](<Notebook/Lenovo/ThinkPad/ThinkPad W530 2441AG6/157AE4F689F0/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/20E239CB8A>) |
| 1217:00f7 | 1028:01f9 | O2 Micro         | Firewire (IEEE 1394)                 | 157   | firewir... | [2C3411042A](<Notebook/Dell/Latitude/Latitude D630/A07A5CFCEFD8/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/2C3411042A>) |
| 1180:0832 | 1028:022f | Ricoh            | R5C832 IEEE 1394 Controller          | 145   | firewir... | [89A2A2261A](<Notebook/Dell/Inspiron/Inspiron 1525/C0BA8A575BF5/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/89A2A2261A>) |
| 1217:13f7 | 1028:0494 | O2 Micro         | 1394 OHCI Compliant Host Controller  | 141   | firewir... | [C3A5CF03A9](<Notebook/Dell/Latitude/Latitude E6520/E350D4696CE5/FEDORA-41/6.12.4-200.FC41.X86_64/X86_64/C3A5CF03A9>) |
| 104c:8023 | 1043:808b | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 130   | firewir... | [03BB592C4A](<Desktop/ASUSTek Computer/P5/P5LD2-VM/7242344F4289/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/03BB592C4A>) |
| 1180:0832 | 103c:30cc | Ricoh            | R5C832 IEEE 1394 Controller          | 125   | firewir... | [D9CCD55FD5](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv6700/1D2546BCE857/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/D9CCD55FD5>) |
| 1180:e832 | 17aa:21ce | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 113   | firewir... | [FBC061A72A](<Notebook/Lenovo/ThinkPad/ThinkPad T420 4236N36/16EB6B514DB5/UBUNTU-20.04/5.15.0-127-GENERIC/X86_64/FBC061A72A>) |
| 1180:e832 | 1028:040b | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 110   | firewir... | [532AFB1E7D](<Notebook/Dell/Latitude/Latitude E6510/CFD329EF96CE/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/532AFB1E7D>) |
| 11c1:5811 | 103c:2a6f | LSI              | FW322/323 [TrueFire] 1394a Contro... | 109   | firewir... | [E061C1CADC](<Desktop/Hewlett-Packard/FQ516AA-A2L/FQ516AA-A2L a6648f/303E05C1DFDD/FEDORA-39/6.7.4-200.FC39.X86_64/X86_64/E061C1CADC>) |
| 197b:2380 | 1043:8313 | JMicron Techn... | IEEE 1394 Host Controller            | 108   | firewir... | [DAB12A66EC](<Desktop/ASUSTek Computer/M4A785TD-M/M4A785TD-M EVO/2C4B418A0839/NOBARA-40/6.11.7-201.FSYNC.FC40.X86_64/X86_64/DAB12A66EC>) |
| 1180:0832 | 103c:172a | Ricoh            | R5C832 IEEE 1394 Controller          | 107   | firewir... | [3F3A213537](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8440p/465E180740A0/UBUNTU-18.04/5.4.0-150-GENERIC/X86_64/3F3A213537>) |
| 11c1:5811 | 103c:1589 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 106   | firewir... | [DD5A66147D](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/05F06043C621/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/DD5A66147D>) |
| 1106:3403 | 103c:2a9c | VIA Technologies | VT6315 Series Firewire Controller    | 103   | firewir... | [E552D93303](<Desktop/Hewlett-Packard/PPPPP-CCC#MMMMMMMM/PPPPP-CCC#MMMMMMMM/21CF9A145DB2/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/E552D93303>) |
| 104c:8025 |           | Texas Instrum... | TSB82AA2 IEEE-1394b Link Layer Co... | 95    | firewir... | [4DBA947354](<Notebook/Apple/MacBookPro4/MacBookPro4,1/2C9AA5484CF5/FEDORA-39/6.11.9-100.FC39.X86_64/X86_64/4DBA947354>) |
| 11c1:5811 | 103c:1309 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 95    | firewir... | [689BB32B5C](<Desktop/Hewlett-Packard/Z400/Z400 Workstation/5A549A7CFEB6/DEBIAN-12/6.1.0-28-AMD64/X86_64/689BB32B5C>) |
| 1106:3403 | 1106:3403 | VIA Technologies | VT6315 Series Firewire Controller    | 90    | firewir... | [BF00D0C5CC](<Desktop/MSI/MS/MS-7900/793D1F29C8B7/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/BF00D0C5CC>) |
| 1217:00f7 | 1179:ff50 | O2 Micro         | Firewire (IEEE 1394)                 | 88    | firewir... | [3174FC3F7E](<Notebook/Toshiba/Satellite/Satellite P300/0CDBF2DE5F7B/ZORIN-17/6.8.0-50-GENERIC/X86_64/3174FC3F7E>) |
| 1180:0832 | 103c:1521 | Ricoh            | R5C832 IEEE 1394 Controller          | 85    | firewir... | [3FBA3EBC56](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8540p/51E585CB7F05/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/3FBA3EBC56>) |
| 1106:3403 | 1043:8374 | VIA Technologies | VT6315 Series Firewire Controller    | 84    | firewir... | [6F3A9094FE](<Desktop/ASUSTek Computer/M4A88TD-V/M4A88TD-V EVO-USB3/8C361D61CA81/LINUXMINT-22/6.8.0-50-GENERIC/X86_64/6F3A9094FE>) |
| 197b:2380 | 103c:17a7 | JMicron Techn... | IEEE 1394 Host Controller            | 84    | firewir... | [212F338F8A](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8570p/0C8B66868A9D/ZORIN-17/6.8.0-48-GENERIC/X86_64/212F338F8A>) |
| 104c:8023 | 1043:815b | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 83    | firewir... | [1026F82971](<Desktop/ASUSTek Computer/P5B-E/P5B-E Plus/0571CE0D8632/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-X86_64/X86_64/1026F82971>) |
| 1180:0832 | 1028:024f | Ricoh            | R5C832 IEEE 1394 Controller          | 82    | firewir... | [16D283695D](<Notebook/Dell/Latitude/Latitude E6500/91D4FA24ADBE/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/16D283695D>) |
| 197b:2380 | 103c:17ab | JMicron Techn... | IEEE 1394 Host Controller            | 81    | firewir... | [70DBE6620B](<Notebook/Hewlett-Packard/ProBook/ProBook 6570b/5066F13EE8E2/ELEMENTARY-7.1/6.2.0-33-GENERIC/X86_64/70DBE6620B>) |
| 1217:00f7 | 1217:00f7 | O2 Micro         | Firewire (IEEE 1394)                 | 79    | firewir... | [F73A0DC2F2](<Notebook/Packard Bell/EasyNote/EasyNote ML65/7D3E8CB7704B/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/F73A0DC2F2>) |
| 1180:e832 | 103c:146d | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 75    | firewir... | [1DBB3A5DD9](<Notebook/Hewlett-Packard/ProBook/ProBook 6450b/71B9FE887DD3/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/1DBB3A5DD9>) |
| 11c1:5811 | 103c:30dd | LSI              | FW322/323 [TrueFire] 1394a Contro... | 75    | firewir... | [2DB6BF65E8](<Notebook/Hewlett-Packard/Compaq/Compaq 6530b/66F63B340309/ELEMENTARY-7.1/6.8.0-45-GENERIC/X86_64/2DB6BF65E8>) |
| 104c:823f | 3412:7856 | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 74    | firewir... | [C7A92E755D](<Desktop/ASUSTek Computer/PRIME/PRIME Z490-A/4874AB7394AB/OL-9.5/5.14.0-503.16.1.EL9_5.X86_64/X86_64/C7A92E755D>) |
| 1180:0832 | 103c:7008 | Ricoh            | R5C832 IEEE 1394 Controller          | 72    | firewir... | [1F59B3E296](<Notebook/Hewlett-Packard/EliteBook/EliteBook 2540p/BB53DD4ACB6A/XUBUNTU-24.04/6.8.0-47-GENERIC/X86_64/1F59B3E296>) |
| 1180:0832 | 104d:9035 | Ricoh            | R5C832 IEEE 1394 Controller          | 72    | firewir... | [946ECEAC16](<Notebook/Sony/VGN-FW51/VGN-FW51ZF_H/A9A53F230022/DEBIAN-12/6.1.0-28-AMD64/X86_64/946ECEAC16>) |

### Flash memory (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1524:0520 | 1025:0090 | ENE Technology   | FLASH memory: ENE Technology Inc:    | 74    |            | [404C14F822](<Notebook/Acer/Aspire/Aspire 5680/66FEFFA14FC2/LINUXMINT-21.3/5.15.0-130-GENERIC/X86_64/404C14F822>) |
| 1524:0530 | 1025:0090 | ENE Technology   | ENE PCI Memory Stick Card Reader ... | 74    |            | [404C14F822](<Notebook/Acer/Aspire/Aspire 5680/66FEFFA14FC2/LINUXMINT-21.3/5.15.0-130-GENERIC/X86_64/404C14F822>) |
| 1524:0551 | 1025:0090 | ENE Technology   | SD/MMC Card Reader Controller        | 74    | sdhci_pci  | [404C14F822](<Notebook/Acer/Aspire/Aspire 5680/66FEFFA14FC2/LINUXMINT-21.3/5.15.0-130-GENERIC/X86_64/404C14F822>) |
| 1524:0551 | 1025:009f | ENE Technology   | SD/MMC Card Reader Controller        | 61    | sdhci_pci  | [379E44855F](<Notebook/Acer/TravelMate/TravelMate 5210/C7A082DE6BC6/ZORIN-16/5.15.0-130-GENERIC/X86_64/379E44855F>) |
| 1524:0520 | 1025:009f | ENE Technology   | FLASH memory: ENE Technology Inc:    | 60    |            | [379E44855F](<Notebook/Acer/TravelMate/TravelMate 5210/C7A082DE6BC6/ZORIN-16/5.15.0-130-GENERIC/X86_64/379E44855F>) |
| 1524:0530 | 1025:009f | ENE Technology   | ENE PCI Memory Stick Card Reader ... | 60    |            | [379E44855F](<Notebook/Acer/TravelMate/TravelMate 5210/C7A082DE6BC6/ZORIN-16/5.15.0-130-GENERIC/X86_64/379E44855F>) |
| 1524:0720 | 1025:012e | ENE Technology   | Memory Stick Card Reader Controller  | 25    |            | [7639BD1FE6](<Notebook/Acer/Aspire/Aspire 5310/F9E10A1A9712/ARCH-ROLLING/6.9.8-ARCH1-1/X86_64/7639BD1FE6>) |
| 1524:0730 | 1025:012e | ENE Technology   | ENE PCI Memory Stick Card Reader ... | 25    |            | [7639BD1FE6](<Notebook/Acer/Aspire/Aspire 5310/F9E10A1A9712/ARCH-ROLLING/6.9.8-ARCH1-1/X86_64/7639BD1FE6>) |
| 1524:0751 | 1025:012e | ENE Technology   | ENE PCI Secure Digital / MMC Card... | 25    | sdhci_pci  | [7639BD1FE6](<Notebook/Acer/Aspire/Aspire 5310/F9E10A1A9712/ARCH-ROLLING/6.9.8-ARCH1-1/X86_64/7639BD1FE6>) |
| 1524:0520 | 1025:010f | ENE Technology   | FLASH memory: ENE Technology Inc:    | 24    |            | [EAC5CC26A2](<Notebook/Acer/Aspire/Aspire 5050/EB82ED617D88/UBUNTU-MATE-22.04/6.5.0-28-GENERIC/X86_64/EAC5CC26A2>) |
| 1524:0530 | 1025:010f | ENE Technology   | ENE PCI Memory Stick Card Reader ... | 24    |            | [EAC5CC26A2](<Notebook/Acer/Aspire/Aspire 5050/EB82ED617D88/UBUNTU-MATE-22.04/6.5.0-28-GENERIC/X86_64/EAC5CC26A2>) |
| 1524:0551 | 1025:010f | ENE Technology   | SD/MMC Card Reader Controller        | 24    | sdhci_pci  | [EAC5CC26A2](<Notebook/Acer/Aspire/Aspire 5050/EB82ED617D88/UBUNTU-MATE-22.04/6.5.0-28-GENERIC/X86_64/EAC5CC26A2>) |
| 1524:0530 | 1734:10c1 | ENE Technology   | ENE PCI Memory Stick Card Reader ... | 16    |            | [70148436E1](<Notebook/Fujitsu Siemens/AMILO/AMILO Pro Edition V3505/A9163707E165/ROSA-12.5.1/5.15.127-GENERIC-1ROSA2021.1-I686/I686/70148436E1>) |
| 1524:0551 | 1734:10c1 | ENE Technology   | SD/MMC Card Reader Controller        | 16    | sdhci_pci  | [70148436E1](<Notebook/Fujitsu Siemens/AMILO/AMILO Pro Edition V3505/A9163707E165/ROSA-12.5.1/5.15.127-GENERIC-1ROSA2021.1-I686/I686/70148436E1>) |
| 1524:0530 | 14c0:0020 | ENE Technology   | ENE PCI Memory Stick Card Reader ... | 13    |            | [1DAC5D5236](<Notebook/Compal/Olidata/Olidata cw3700/F4D60C63E9BB/DEBIAN-12/6.1.0-18-686-PAE/I686/1DAC5D5236>) |
| 1524:0551 | 14c0:0020 | ENE Technology   | SD/MMC Card Reader Controller        | 13    | sdhci_pci  | [1DAC5D5236](<Notebook/Compal/Olidata/Olidata cw3700/F4D60C63E9BB/DEBIAN-12/6.1.0-18-686-PAE/I686/1DAC5D5236>) |
| 1524:0720 | 1025:011b | ENE Technology   | Memory Stick Card Reader Controller  | 9     |            | [A81468385B](<Notebook/Acer/TravelMate/TravelMate 6292/C6C289849FAF/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/A81468385B>) |
| 1524:0730 | 1025:011b | ENE Technology   | ENE PCI Memory Stick Card Reader ... | 9     |            | [A81468385B](<Notebook/Acer/TravelMate/TravelMate 6292/C6C289849FAF/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/A81468385B>) |
| 1524:0730 | 1558:0801 | ENE Technology   | ENE PCI Memory Stick Card Reader ... | 9     |            | [167AF55BAF](<Notebook/Clevo/M7/M7x0S/046A0E120E5B/UBUNTU-24.04/6.8.0-47-GENERIC/X86_64/167AF55BAF>) |
| 1524:0751 | 1025:011b | ENE Technology   | ENE PCI Secure Digital / MMC Card... | 9     | sdhci_pci  | [A81468385B](<Notebook/Acer/TravelMate/TravelMate 6292/C6C289849FAF/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/A81468385B>) |
| 1524:0751 | 1558:0801 | ENE Technology   | ENE PCI Secure Digital / MMC Card... | 9     | sdhci_pci  | [167AF55BAF](<Notebook/Clevo/M7/M7x0S/046A0E120E5B/UBUNTU-24.04/6.8.0-47-GENERIC/X86_64/167AF55BAF>) |
| 1524:0520 | 1179:ff01 | ENE Technology   | FLASH memory: ENE Technology Inc:    | 8     |            | [1D2307C817](<Notebook/Toshiba/Satellite/Satellite A110/C971DDF096ED/ZORIN-15/5.4.0-150-GENERIC/I686/1D2307C817>) |
| 1524:0530 | 1179:ff01 | ENE Technology   | ENE PCI Memory Stick Card Reader ... | 8     |            | [1D2307C817](<Notebook/Toshiba/Satellite/Satellite A110/C971DDF096ED/ZORIN-15/5.4.0-150-GENERIC/I686/1D2307C817>) |
| 1524:0551 | 1179:ff02 | ENE Technology   | SD/MMC Card Reader Controller        | 8     | sdhci_pci  | [1D2307C817](<Notebook/Toshiba/Satellite/Satellite A110/C971DDF096ED/ZORIN-15/5.4.0-150-GENERIC/I686/1D2307C817>) |
| 1524:0730 | 1558:0722 | ENE Technology   | ENE PCI Memory Stick Card Reader ... | 6     |            | [C0F6248EDD](<Notebook/Clevo/M720/M720SRS/D3D903574E1C/LINUXMINT-19.2/4.15.0-213-GENERIC/I686/C0F6248EDD>) |
| 1524:0730 | 1558:5409 | ENE Technology   | ENE PCI Memory Stick Card Reader ... | 6     |            | [00EBCAC258](<Notebook/Clevo/M540/M540SR/F98886333E76/LINUXMINT-20/5.4.0-47-GENERIC/X86_64/00EBCAC258>) |
| 1524:0751 | 1558:0722 | ENE Technology   | ENE PCI Secure Digital / MMC Card... | 6     | sdhci_pci  | [C0F6248EDD](<Notebook/Clevo/M720/M720SRS/D3D903574E1C/LINUXMINT-19.2/4.15.0-213-GENERIC/I686/C0F6248EDD>) |
| 1524:0751 | 1558:5409 | ENE Technology   | ENE PCI Secure Digital / MMC Card... | 6     | sdhci_pci  | [00EBCAC258](<Notebook/Clevo/M540/M540SR/F98886333E76/LINUXMINT-20/5.4.0-47-GENERIC/X86_64/00EBCAC258>) |
| 1106:9530 | 17aa:3891 | VIA Technologies | VX800/820/900/VT8261 Series Secur... | 4     | via_sdmmc  | [34CB8EA20B](<Notebook/Lenovo/IdeaPad/IdeaPad S12 20021,2959/02175018541C/ANTIX-22/5.10.142-ANTIX.2-AMD64-SMP/X86_64/34CB8EA20B>) |
| 1524:0720 | 1462:2fb3 | ENE Technology   | Memory Stick Card Reader Controller  | 4     |            | [4B6EF74EE5](<Notebook/MSI/PR/PR200/C86BAC5C390E/OPENMANDRIVA-24.06/6.9.3-DESKTOP-2OMV2490/X86_64/4B6EF74EE5>) |
| 1524:0730 | 1462:2fb3 | ENE Technology   | ENE PCI Memory Stick Card Reader ... | 4     |            | [4B6EF74EE5](<Notebook/MSI/PR/PR200/C86BAC5C390E/OPENMANDRIVA-24.06/6.9.3-DESKTOP-2OMV2490/X86_64/4B6EF74EE5>) |
| 1524:0730 | 1558:0664 | ENE Technology   | ENE PCI Memory Stick Card Reader ... | 4     |            | [225361B7C3](<Notebook/Wortmann AG/M660/M660SE/2471F70288DA/ALPINE-3.19.0/6.6.9-0-LTS/I686/225361B7C3>) |
| 1524:0730 | 1558:0669 | ENE Technology   | ENE PCI Memory Stick Card Reader ... | 4     |            | [56F8AB01F9](<Notebook/Clevo/M660/M660SR/6A65712FDBAC/LINUXMINT-20.3/5.4.0-165-GENERIC/X86_64/56F8AB01F9>) |
| 1524:0730 | 1558:0802 | ENE Technology   | ENE PCI Memory Stick Card Reader ... | 4     |            | [A9638079C6](<Notebook/Clevo/M7/M7X0SU/8E6C9AD6B199/POP!_OS-20.04/5.13.0-7620-GENERIC/X86_64/A9638079C6>) |
| 1524:0751 | 1462:2fb3 | ENE Technology   | ENE PCI Secure Digital / MMC Card... | 4     | sdhci_pci  | [4B6EF74EE5](<Notebook/MSI/PR/PR200/C86BAC5C390E/OPENMANDRIVA-24.06/6.9.3-DESKTOP-2OMV2490/X86_64/4B6EF74EE5>) |
| 1524:0751 | 1558:0664 | ENE Technology   | ENE PCI Secure Digital / MMC Card... | 4     | sdhci_pci  | [225361B7C3](<Notebook/Wortmann AG/M660/M660SE/2471F70288DA/ALPINE-3.19.0/6.6.9-0-LTS/I686/225361B7C3>) |
| 1524:0751 | 1558:0669 | ENE Technology   | ENE PCI Secure Digital / MMC Card... | 4     | sdhci_pci  | [56F8AB01F9](<Notebook/Clevo/M660/M660SR/6A65712FDBAC/LINUXMINT-20.3/5.4.0-165-GENERIC/X86_64/56F8AB01F9>) |
| 1524:0751 | 1558:0802 | ENE Technology   | ENE PCI Secure Digital / MMC Card... | 4     | sdhci_pci  | [A9638079C6](<Notebook/Clevo/M7/M7X0SU/8E6C9AD6B199/POP!_OS-20.04/5.13.0-7620-GENERIC/X86_64/A9638079C6>) |
| 1524:0510 | 1524:0510 | ENE Technology   | CB710 Memory Card Reader Controller  | 3     | cb710      | [1312407631](<Notebook/Acer/Aspire/Aspire 5100/26D84FEE45B7/UBUNTU-18.10/4.18.0-10-GENERIC/X86_64/1312407631>) |
| 1524:0530 | 1734:10d7 | ENE Technology   | ENE PCI Memory Stick Card Reader ... | 3     |            | [6272F76B0B](<Notebook/Fujitsu Siemens/AMILO/AMILO Pro Series V3525/28DB48CA5C87/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/6272F76B0B>) |
| 1524:0551 | 1734:10d7 | ENE Technology   | SD/MMC Card Reader Controller        | 3     | sdhci_pci  | [6272F76B0B](<Notebook/Fujitsu Siemens/AMILO/AMILO Pro Series V3525/28DB48CA5C87/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/6272F76B0B>) |
| 1524:0720 | 1462:2fbd | ENE Technology   | Memory Stick Card Reader Controller  | 3     |            | [4D793C3846](<Notebook/AVERATEC/2500/2500 Series/0C5362D1F418/LINUXMINT-20.3/5.4.0-121-GENERIC/X86_64/4D793C3846>) |
| 1524:0730 | 1462:2fbd | ENE Technology   | ENE PCI Memory Stick Card Reader ... | 3     |            | [4D793C3846](<Notebook/AVERATEC/2500/2500 Series/0C5362D1F418/LINUXMINT-20.3/5.4.0-121-GENERIC/X86_64/4D793C3846>) |
| 1524:0730 | 1558:0721 | ENE Technology   | ENE PCI Memory Stick Card Reader ... | 3     |            | [7E0CF9341B](<Notebook/Clevo/M720/M720R/955F77FF3F0B/LINUXMINT-22/6.8.0-40-GENERIC/X86_64/7E0CF9341B>) |
| 1524:0730 | 1558:5408 | ENE Technology   | ENE PCI Memory Stick Card Reader ... | 3     |            | [17B00479C7](<Notebook/Positivo/Mobile/Mobile/213EFE5F5668/LINUXMINT-19.2/4.15.0-161-GENERIC/I686/17B00479C7>) |
| 1524:0751 | 1462:2fbd | ENE Technology   | ENE PCI Secure Digital / MMC Card... | 3     | sdhci_pci  | [4D793C3846](<Notebook/AVERATEC/2500/2500 Series/0C5362D1F418/LINUXMINT-20.3/5.4.0-121-GENERIC/X86_64/4D793C3846>) |
| 1524:0751 | 1558:0721 | ENE Technology   | ENE PCI Secure Digital / MMC Card... | 3     | sdhci_pci  | [7E0CF9341B](<Notebook/Clevo/M720/M720R/955F77FF3F0B/LINUXMINT-22/6.8.0-40-GENERIC/X86_64/7E0CF9341B>) |
| 1524:0751 | 1558:5408 | ENE Technology   | ENE PCI Secure Digital / MMC Card... | 3     | sdhci_pci  | [17B00479C7](<Notebook/Positivo/Mobile/Mobile/213EFE5F5668/LINUXMINT-19.2/4.15.0-161-GENERIC/I686/17B00479C7>) |
| 1106:9530 | 144d:c04e | VIA Technologies | VX800/820/900/VT8261 Series Secur... | 2     | via_sdmmc  | [085B83A79C](<Notebook/Samsung Electronics/NC20/NC20-NB20/36A849851FB8/XUBUNTU-20.04/5.4.0-29-GENERIC/X86_64/085B83A79C>) |
| 1524:0510 | 1043:1724 | ENE Technology   | CB710 Memory Card Reader Controller  | 2     | cb710      | [C26269028E](<Desktop/ASUSTek Computer/P4/P4S8L/191F66899DAB/DEBIAN-11/5.10.0-23-686-PAE/I686/C26269028E>) |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1451 | 1022:1451 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 2694  |            | [A23FC83EDD](<Desktop/Gigabyte Technology/AB350/AB350-Gaming/B5A158869F92/GENTOO-2.17/6.6.67-GENTOO/X86_64/A23FC83EDD>) |
| 1022:1577 | 1022:1577 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 1327  |            | [69908D16CA](<Notebook/Lenovo/ThinkPad/ThinkPad E475 20H40006US/ACBB63787D0E/DEBIAN-12/6.1.0-27-AMD64/X86_64/69908D16CA>) |
| 1002:5a23 | 1002:5a23 | AMD              | RD890S/RD990 I/O Memory Managemen... | 790   |            | [92B3EE2679](<Desktop/Gigabyte Technology/GA-970/GA-970A-UD3/76B14B1E4C2A/DEBIAN/6.11.10-AMD64/X86_64/92B3EE2679>) |
| 1022:1419 | 1022:1419 | AMD              | Family 15h (Models 10h-1fh) I/O M... | 414   |            | [491ADF615A](<Desktop/MSI/MS/MS-7721/12FD0D2A30C9/OPENMANDRIVA-23.08/6.4.11-DESKTOP-1OMV2390/X86_64/491ADF615A>) |
| 1002:5a23 | 1462:7693 | AMD              | RD890S/RD990 I/O Memory Managemen... | 258   |            | [4DA1F27374](<Desktop/MSI/MS/MS-7693/FA04784F890C/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/4DA1F27374>) |
| 1022:1423 | 1022:1423 | AMD              | Family 15h (Models 30h-3fh) I/O M... | 189   |            | [06248FDAC7](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 705 G2 SFF/D44B1405BD6E/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/06248FDAC7>) |
| 1022:1419 | 1462:7721 | AMD              | Family 15h (Models 10h-1fh) I/O M... | 92    |            | [37ED0BFC1F](<Desktop/MSI/MS/MS-7721/ED4D6EF8E4A6/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/37ED0BFC1F>) |
| 1022:1423 | 1462:7721 | AMD              | Family 15h (Models 30h-3fh) I/O M... | 88    |            | [D3DF8A394A](<Desktop/MSI/MS/MS-7721/068BEFB73DAA/ELEMENTARY-8/6.8.0-49-GENERIC/X86_64/D3DF8A394A>) |
| 1022:1577 | 103c:8331 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 42    |            | [D4DE478530](<Notebook/Hewlett-Packard/Laptop/Laptop 15-bw0xx/8C7E04D7380F/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/D4DE478530>) |
| 1022:1423 | 1043:85cb | AMD              | Family 15h (Models 30h-3fh) I/O M... | 35    |            | [F234970CC5](<Desktop/ASUSTek Computer/A68/A68HM-PLUS/DF4467CCEA6E/LINUXMINT-22/6.8.0-49-GENERIC/X86_64/F234970CC5>) |
| 1022:14a6 | 1022:14a6 | AMD              | Genoa/Bergamo RCEC                   | 35    | pcieport   | [806CBDE5A6](<Desktop/Gigabyte Technology/TRX50/TRX50 AERO D/958E707E7355/NIXOS-24.11/6.12.3/X86_64/806CBDE5A6>) |
| 1022:1577 | 103c:81fa | AMD              | Family 15h (Models 60h-6fh) I/O M... | 31    |            | [06877F4048](<Notebook/Hewlett-Packard/Notebook/Notebook/095D82F00230/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/06877F4048>) |
| 1002:5a23 | 1458:5000 | AMD              | RD890S/RD990 I/O Memory Managemen... | 29    |            | [7D81A61C55](<Desktop/Gigabyte Technology/GA-990/GA-990XA-UD3/A319A4DF5970/OPENSUSE-LEAP-15.6/6.4.0-150600.23.25-DEFAULT/X86_64/7D81A61C55>) |
| 1002:5a23 | 1462:7640 | AMD              | RD890S/RD990 I/O Memory Managemen... | 25    |            | [8B2F125314](<Desktop/MSI/MS/MS-7640/DDA08AE152EA/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/8B2F125314>) |
| 8086:0b23 | 8086:0000 | Intel            | Xeon Root Event Collector            | 23    | pcieport   | [9018A2AC09](<Desktop/Dell/Precision/Precision 7960 Tower/8110AA44DF4F/RHEL-8/4.18.0-477.10.1.EL8_8.X86_64/X86_64/9018A2AC09>) |
| 1022:1419 | 1043:8526 | AMD              | Family 15h (Models 10h-1fh) I/O M... | 19    |            | [A2BB2FEB80](<Desktop/ASUSTek Computer/A88/A88XM-PLUS/6A0A25F1B9A9/OPENSUSE-LEAP-15.6/6.4.0-150600.23.17-DEFAULT/X86_64/A2BB2FEB80>) |
| 1022:1577 | 103c:80b5 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 19    |            | [C382838A7E](<Notebook/Hewlett-Packard/Pavilion/Pavilion Notebook/6CD5F0F3E1DB/NITRUX-3.7.1/6.11.5-1-LIQUORIX-AMD64/X86_64/C382838A7E>) |
| 1022:1419 | 1462:7895 | AMD              | Family 15h (Models 10h-1fh) I/O M... | 18    |            | [4F11205FD5](<Desktop/MSI/MS/MS-7895/D4E090DAC3EA/UBUNTU-22.04/6.2.0-39-GENERIC/X86_64/4F11205FD5>) |
| 1002:5a23 | 1462:7974 | AMD              | RD890S/RD990 I/O Memory Managemen... | 16    |            | [133D4B58C9](<Desktop/MSI/MS/MS-7974/049E54E03897/GENTOO-2.13/6.1.38-GENTOO-X86_64/X86_64/133D4B58C9>) |
| 1022:1423 | 103c:812f | AMD              | Family 15h (Models 30h-3fh) I/O M... | 14    |            | [3719FA55D8](<Notebook/Hewlett-Packard/Notebook/Notebook/3BAE0A52E96E/LINUXMINT-21.1/5.15.0-102-GENERIC/X86_64/3719FA55D8>) |
| 8086:19a2 | 15d9:0969 | Intel            | Atom Processor C3000 Series Root ... | 14    | pcieport   | [CDCA826585](<Server/Supermicro/Super/Super Server/67F50154C8D4/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/CDCA826585>) |
| 1022:1423 | 1462:7895 | AMD              | Family 15h (Models 30h-3fh) I/O M... | 12    |            | [FB213FE215](<Desktop/MSI/MS/MS-7895/DF0D38A7C09D/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/FB213FE215>) |
| 8086:0b23 | 8086:7270 | Intel            | Xeon Root Event Collector            | 9     | pcieport   | [18F894CDC8](<Desktop/Intel/AvenueCityM/AvenueCityM/6BCBEE6D0C72/UBUNTU-24.10/6.13.0-061300RC1-GENERIC/X86_64/18F894CDC8>) |
| 1022:1419 | 1025:070b | AMD              | Family 15h (Models 10h-1fh) I/O M... | 7     |            | [7ECC002FC3](<Desktop/Acer/Aspire/Aspire TC-105/CAF796A635BB/POP!_OS-22.04/6.8.0-76060800DAILY20240311-GENERIC/X86_64/7ECC002FC3>) |
| 1022:1419 | 1019:7c8d | AMD              | Family 15h (Models 10h-1fh) I/O M... | 6     |            | [2D00BA463B](<Desktop/Acer/Veriton/Veriton M2110G/254C55A8EF27/FEDORA-36/5.19.8-200.FC36.X86_64/X86_64/2D00BA463B>) |
| 8086:19a2 | 8086:0000 | Intel            | Atom Processor C3000 Series Root ... | 6     | pcieport   | [C799DC9A8C](<Desktop/Others/QDNV/QDNV01/635BCF0BB811/NIXOS-24.05/6.6.36/X86_64/C799DC9A8C>) |
| 8086:19a2 | 8086:19a2 | Intel            | Atom Processor C3000 Series Root ... | 6     | pcieport   | [3DA4BB5017](<Desktop/newplatforms/NP-1008/NP-1008i/1A90336463DB/DEBIAN-12/6.1.0-15-AMD64/X86_64/3DA4BB5017>) |
| 1022:1577 | 103c:80b6 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 5     |            | [3FF032130B](<Notebook/Hewlett-Packard/Pavilion/Pavilion Notebook/7F8A0929FED6/DEBIAN-12/6.1.0-26-AMD64/X86_64/3FF032130B>) |
| 1022:1577 | 103c:8355 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 4     |            | [6D31B35E19](<Notebook/Hewlett-Packard/Pavilion/Pavilion Laptop 15-cd0xx/4C288AFDC2A8/ELEMENTARY-7.1/6.5.0-18-GENERIC/X86_64/6D31B35E19>) |
| 1022:1419 | 1462:7900 | AMD              | Family 15h (Models 10h-1fh) I/O M... | 3     |            | [A0CBC39688](<Desktop/MSI/MS/MS-7900/EA733492996E/MANJARO/5.14.2-1-MANJARO/X86_64/A0CBC39688>) |
| 1022:1423 | 1462:7793 | AMD              | Family 15h (Models 30h-3fh) I/O M... | 3     |            | [ED81DDD35F](<Desktop/MSI/MS/MS-7793/549E3EB089E6/OPENSUSE-LEAP-15.6/6.4.0-150600.23.25-DEFAULT/X86_64/ED81DDD35F>) |
| 8086:0b23 | 15d9:1c51 | Intel            | Xeon Root Event Collector            | 3     | pcieport   | [96962C9FAC](<Server/Supermicro/SYS-511/SYS-511E-WR/4D3CCDFB3187/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/96962C9FAC>) |
| 1022:14e9 | 103c:8cbd | AMD              | Phoenix IOMMU                        | 2     |            | [CA7BD9EECA](<Notebook/Hewlett-Packard/Pavilion/Pavilion Aero Laptop 13-bg0xxx/14DA292256A6/FINNIX-DEV/6.10.11-AMD64/X86_64/CA7BD9EECA>) |
| 8086:0b23 | 1028:0a3a | Intel            | Xeon Root Event Collector            | 2     | pcieport   | [9018A2AC09](<Desktop/Dell/Precision/Precision 7960 Tower/8110AA44DF4F/RHEL-8/4.18.0-477.10.1.EL8_8.X86_64/X86_64/9018A2AC09>) |
| 8086:0b23 | 15d9:1c82 | Intel            | Xeon Root Event Collector            | 2     | pcieport   | [ADC9050B3F](<Server/Supermicro/Super/Super Server/A5DA019EA0BE/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/ADC9050B3F>) |
| 1022:1419 | 17aa:36a0 | AMD              | Family 15h (Models 10h-1fh) I/O M... | 1     |            | [BA1A484E84](<Desktop/Lenovo/H50-55/H50-55 90BG000XRS/94482FE57B53/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-I586/I686/BA1A484E84>) |
| 1022:1423 | 17aa:368f | AMD              | Family 15h (Models 30h-3fh) I/O M... | 1     |            | [58DDD6F565](<All In One/Lenovo/B50-35/B50-35 F0AV0025GE/7D201658F55F/ROSA-2014.1/4.9.76-NRJ-DESKTOP-1ROSA-X86_64/X86_64/58DDD6F565>) |
| 1022:14e9 | 1462:7d73 | AMD              | Phoenix IOMMU                        | 1     |            | [9F7CF29DD9](<Desktop/MSI/MS-7/MS-7D73/0F8E8F044D1A/NIXOS-24.11/6.6.67/X86_64/9F7CF29DD9>) |
| 8086:0b23 | 1028:0a3c | Intel            | Xeon Root Event Collector            | 1     | pcieport   | [906A276432](<Desktop/Dell/Precision/Precision 5860 Tower/865F92E471F6/GENTOO-2.15/6.10.11-GENTOO/X86_64/906A276432>) |
| 8086:0b23 | 1028:0a6b | Intel            | Xeon Root Event Collector            | 1     | pcieport   | [8826988040](<Server/Others/0024FG/0024FG A01/FF97E492C16F/DEBIAN-12/6.8.8-2-PVE/X86_64/8826988040>) |
| 8086:0b23 | 1028:0aaa | Intel            | Xeon Root Event Collector            | 1     | pcieport   | [45477E743D](<Server/Dell/Precision/Precision 7960 Rack/A4F90226C97E/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/45477E743D>) |
| 8086:0b23 | 1028:0b9d | Intel            | Xeon Root Event Collector            | 1     |            | [1524F37BBF](<Server/Dell/PowerEdge/PowerEdge R660xs/46E84777EA42/CENTOS-7/3.10.0-1160.119.1.EL7.X86_64/X86_64/1524F37BBF>) |
| 8086:0b23 | 103c:8962 | Intel            | Xeon Root Event Collector            | 1     | pcieport   | [501FF86B46](<Desktop/Hewlett-Packard/Z4/Z4 G5 Workstation Desktop PC/87C19F63AFA8/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/501FF86B46>) |
| 8086:0b23 | 1043:8694 | Intel            | Xeon Root Event Collector            | 1     | pcieport   | [68F88E3B88](<Desktop/ASUSTek Computer/Pro/Pro WS W790E-SAGE SE/126AD6636E7B/ARCH-ROLLING/6.10.10-2-CUSTOM-ULTIMATE/X86_64/68F88E3B88>) |
| 8086:0b23 | 15d9:1c30 | Intel            | Xeon Root Event Collector            | 1     | pcieport   | [4CE14B1603](<Desktop/Supermicro/SYS-121/SYS-121H-TNR/7BBB90FD1FB9/DEBIAN-12/6.1.0-26-AMD64/X86_64/4CE14B1603>) |
| 8086:0b23 | 15d9:1c87 | Intel            | Xeon Root Event Collector            | 1     | pcieport   | [7A000004A8](<Server/Supermicro/SYS-751/SYS-751A-I/A896A4C21B30/UBUNTU-22.04/6.5.0-35-GENERIC/X86_64/7A000004A8>) |
| 8086:0b23 | 17aa:104e | Intel            | Xeon Root Event Collector            | 1     | pcieport   | [791DC0869D](<Server/Lenovo/ThinkStation/ThinkStation PX 30EUA0EG00/8A299C9A2065/DEBIAN-12/6.10.11+BPO-AMD64/X86_64/791DC0869D>) |
| 8086:0b23 | 17aa:1055 | Intel            | Xeon Root Event Collector            | 1     | pcieport   | [5900FFB655](<Desktop/Lenovo/ThinkStation/ThinkStation P5 30GACTO1WW/090D72A32F5F/FEDORA-40/6.8.11-300.FC40.X86_64/X86_64/5900FFB655>) |
| 8086:0b23 | 17aa:1056 | Intel            | Xeon Root Event Collector            | 1     | pcieport   | [9F23DE610A](<Desktop/Lenovo/ThinkStation/ThinkStation P7 30F3000UGE/F1DC4383B466/DEBIAN-12/6.1.0-28-AMD64/X86_64/9F23DE610A>) |
| 8086:0b23 | 17aa:7830 | Intel            | Xeon Root Event Collector            | 1     | pcieport   | [80A2F3D367](<Server/Lenovo/ThinkSystem/ThinkSystem SR950 V3/80C0A7FFD0E3/RHEL-9/5.14.0-70.22.1.EL9_0.X86_64/X86_64/80A2F3D367>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1002:163f | 1002:0123 | AMD              | VanGogh [AMD Custom GPU 0405]        | 1549  | amdgpu     | [586CABC574](<Notebook/Valve/Jupiter/Jupiter/917F916A860A/STEAMOS-3.6.20/6.5.0-VALVE22-1-NEPTUNE-65-G9A338ED8A75E/X86_64/586CABC574>) |
| 8086:22b0 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1123  | i915       | [496C93250D](<Tablet/Chuwi/Hi10/Hi10 pro tablet/D5A4927F3C98/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/496C93250D>) |
| 8086:0412 | 1458:d000 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 889   | i915       | [94525B433D](<Notebook/Gigabyte Technology/Z97/Z97N-WIFI/A4280F903AB0/FEDORA-39/6.7.9-204.FSYNC.FC39.X86_64/X86_64/94525B433D>) |
| 10de:128b | 1462:8c93 | Nvidia           | GK208B [GeForce GT 710]              | 828   | nouveau    | [76CFDE7DC3](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-K/D65E7197EDD5/DEBIAN/6.1.0-28-AMD64/X86_64/76CFDE7DC3>) |
| 8086:5a85 | 8086:2212 | Intel            | HD Graphics 500                      | 679   | i915       | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:0412 | 1043:8534 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 631   | i915       | [BA47136806](<Desktop/ASUSTek Computer/All/All Series/651BB16BD9C9/UBUNTU-24.10/6.12.3-061203-GENERIC/X86_64/BA47136806>) |
| 8086:3185 | 8086:2212 | Intel            | GeminiLake [UHD Graphics 600]        | 572   | i915       | [D506EFC726](<Desktop/Seeed Studio/ODYSSEY-X86J41X5/ODYSSEY-X86J41X5 CJ41GV2-410-O.C 12-02-2022 15:01:15/6C4A4010567B/UBUNTU-20.04/5.4.0-204-GENERIC/X86_64/D506EFC726>) |
| 1002:67df | 1da2:e366 | AMD              | Ellesmere [Radeon RX 470/480/570/... | 568   | amdgpu     | [FDA84AF6B6](<Desktop/MSI/MS-7/MS-7A40/DC07AAAD39A3/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/FDA84AF6B6>) |
| 1002:164e | 1043:8877 | AMD              | Raphael                              | 537   | amdgpu     | [04F9FFDAB4](<Desktop/ASUSTek Computer/ROG/ROG STRIX B650-A GAMING WIFI/848E93DF68A9/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/04F9FFDAB4>) |
| 1002:1638 | 1002:1636 | AMD              | Cezanne [Radeon Vega Series / Rad... | 528   | amdgpu     | [55ED055BF7](<Desktop/ASRock/A520M/A520M Phantom Gaming 4/C09535CF4E8E/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/55ED055BF7>) |
| 1002:15d8 | 1002:15d8 | AMD              | Picasso/Raven 2 [Radeon Vega Seri... | 490   | amdgpu     | [7D00280570](<Desktop/ASRock/A300/A300M-STX/547EBBC1A567/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.12.6-1-DEFAULT/X86_64/7D00280570>) |
| 8086:0f31 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 461   | i915       | [9CD761EAD3](<Notebook/Google/Candy/Candy/B00D93A16696/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9CD761EAD3>) |
| 8086:0046 | 17aa:215a | Intel            | Core Processor Integrated Graphic... | 442   | i915       | [ECF4A20D48](<Notebook/Lenovo/ThinkPad/ThinkPad T510 4313A11/2CE2156B4537/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/ECF4A20D48>) |
| 8086:3185 |           | Intel            | GeminiLake [UHD Graphics 600]        | 426   | i915       | [3D87931055](<Desktop/AZW/GK/GK mini/C6AE74B57D03/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/3D87931055>) |
| 8086:1912 | 1043:8694 | Intel            | HD Graphics 530                      | 401   | i915       | [3F76019E9E](<Desktop/ASUSTek Computer/G20/G20CB/3C0F57476362/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/3F76019E9E>) |
| 10de:0866 | 106b:00b1 | Nvidia           | C79 [GeForce 9400M G]                | 390   | nouveau    | [3E1D6CE785](<Notebook/Apple/MacBook5/MacBook5,2/7D2F05FAEBD0/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/3E1D6CE785>) |
| 1002:15dd | 1002:15dd | AMD              | Raven Ridge [Radeon Vega Series /... | 374   | amdgpu     | [15B1774620](<Desktop/MSI/MS-7/MS-7B86/5DD0AA5D5056/ZORIN-17/6.8.0-50-GENERIC/X86_64/15B1774620>) |
| 1002:67df | 1682:c580 | AMD              | Ellesmere [Radeon RX 470/480/570/... | 373   | amdgpu     | [A24D68CA3C](<Desktop/MSI/MS-7/MS-7C95/389A9DE31DED/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/A24D68CA3C>) |
| 8086:0166 | 106b:00fa | Intel            | 3rd Gen Core processor Graphics C... | 371   | i915       | [CFA406503C](<Notebook/Apple/MacBookPro9/MacBookPro9,2/7FA59624BF13/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/CFA406503C>) |
| 8086:0102 | 1043:844d | Intel            | 2nd Generation Core Processor Fam... | 370   | i915       | [E6075ADFC0](<Desktop/ASUSTek Computer/CM6630/CM6630_CM6730_CM6830/64DE23EC7F13/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/E6075ADFC0>) |
| 1002:1638 | 1043:8809 | AMD              | Cezanne [Radeon Vega Series / Rad... | 360   | amdgpu     | [989A72852C](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PLUS/4495A9F18FCB/ZORIN-17/6.8.0-50-GENERIC/X86_64/989A72852C>) |
| 1a03:2000 | 1a03:2000 | ASPEED Techno... | ASPEED Graphics Family               | 347   | ast        | [122B21A8E4](<Server/Others/Others/Others/DB0155950DC6/DEBIAN-12/6.8.12-5-PVE/X86_64/122B21A8E4>) |
| 8086:2a42 | 17aa:20e4 | Intel            | Mobile 4 Series Chipset Integrate... | 347   | i915       | [0C0F6EF206](<Notebook/Lenovo/ThinkPad/ThinkPad SL400 2743A48/24276C7B5960/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/0C0F6EF206>) |
| 8086:2a43 | 17aa:20e4 | Intel            | Mobile 4 Series Chipset Integrate... | 347   |            | [0C0F6EF206](<Notebook/Lenovo/ThinkPad/ThinkPad SL400 2743A48/24276C7B5960/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/0C0F6EF206>) |
| 8086:0166 | 17aa:21fa | Intel            | 3rd Gen Core processor Graphics C... | 344   | i915       | [D8B0ADF8FB](<Notebook/Lenovo/ThinkPad/ThinkPad X230 23252UG/EAF4136FB502/ARCH-ROLLING/6.6.54-1-LTS/X86_64/D8B0ADF8FB>) |
| 8086:0152 | 1458:d000 | Intel            | Xeon E3-1200 v2/3rd Gen Core proc... | 343   | i915       | [58BE9BACFD](<Desktop/Gigabyte Technology/H61/H61M-S2PV/0261B0DCD705/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/58BE9BACFD>) |
| 8086:1626 | 106b:011b | Intel            | HD Graphics 6000                     | 341   | i915       | [0B5DBC9283](<Notebook/Apple/MacBookAir7/MacBookAir7,2/7D9EECEFFC2B/UBUNTU-24.10/6.11.0-13-GENERIC/X86_64/0B5DBC9283>) |
| 1002:1638 | 1002:0123 | AMD              | Cezanne [Radeon Vega Series / Rad... | 339   | amdgpu     | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 8086:0102 | 1458:d000 | Intel            | 2nd Generation Core Processor Fam... | 333   | i915       | [2EF34839F4](<Desktop/Gigabyte Technology/H61/H61M-DS2/29D58848E162/ZORIN-17/6.5.0-18-GENERIC/X86_64/2EF34839F4>) |
| 8086:22b1 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 332   | i915       | [8013360F66](<Notebook/Others/Others/Others/D09E1F76F2EF/ENDEAVOUROS-ROLLING/6.6.65-1-LTS/X86_64/8013360F66>) |
| 10de:1d01 | 1462:8c98 | Nvidia           | GP108 [GeForce GT 1030]              | 329   | nvidia     | [C841518658](<Desktop/Gigabyte Technology/B550/B550 AORUS ELITE V2/0F1A36F2B74D/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/C841518658>) |
| 8086:0126 | 106b:00db | Intel            | 2nd Generation Core Processor Fam... | 329   | i915       | [C208215B7F](<Notebook/Apple/MacBookPro8/MacBookPro8,1/D3B2EF57FDD2/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/C208215B7F>) |
| 10de:1c82 | 1462:8c96 | Nvidia           | GP107 [GeForce GTX 1050 Ti]          | 324   | nvidia     | [3B654F1020](<Desktop/ASUSTek Computer/H110/H110M-E-M.2/3A3D2B8BCE07/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/3B654F1020>) |
| 1002:9616 | 1043:8388 | AMD              | RS780L [Radeon 3000]                 | 323   | radeon     | [35ECDF468A](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LE/F39DBE376494/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/35ECDF468A>) |
| 8086:0166 | 17aa:21f3 | Intel            | 3rd Gen Core processor Graphics C... | 322   | i915       | [654DBCABAB](<Notebook/Lenovo/ThinkPad/ThinkPad T430 2349SVA/42DC7F4F1F2E/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/654DBCABAB>) |
| 1002:164c | 17aa:3f95 | AMD              | Lucienne                             | 321   | amdgpu     | [E428436322](<Notebook/Lenovo/IdeaPad/IdeaPad 3 15ALC6 82KU/EAE67903063F/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/E428436322>) |
| 8086:1916 | 103c:8079 | Intel            | Skylake GT2 [HD Graphics 520]        | 309   | i915       | [DA5C26013C](<Notebook/Hewlett-Packard/ZBook/ZBook 15u G3/5C8D48F3C0A5/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/DA5C26013C>) |
| 8086:3185 | 0100:2782 | Intel            | GeminiLake [UHD Graphics 600]        | 307   | i915       | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:5912 | 1043:8694 | Intel            | HD Graphics 630                      | 298   | i915       | [5A05AC75D9](<Desktop/Wortmann AG/1009498/1009498_2111067/94145E52AA70/CACHYOS/6.12.8-2-CACHYOS/X86_64/5A05AC75D9>) |
| 8086:5917 | 17aa:225d | Intel            | UHD Graphics 620                     | 289   | i915       | [C35541E56B](<Notebook/Lenovo/ThinkPad/ThinkPad T480 20L5S1S000/9025AC5E126D/DEBIAN-12/6.1.0-28-AMD64/X86_64/C35541E56B>) |
| 1002:67df | 1da2:e353 | AMD              | Ellesmere [Radeon RX 470/480/570/... | 288   | amdgpu     | [C9CF4100BB](<Desktop/MSI/MS-7/MS-7B86/B861024B00A8/FEDORA-42/6.13.0-0.RC5.42.FC42.X86_64/X86_64/C9CF4100BB>) |
| 1002:67df | 1462:3418 | AMD              | Ellesmere [Radeon RX 470/480/570/... | 286   | amdgpu     | [BADFE83ED3](<Desktop/ASUSTek Computer/M5A97/M5A97 LE R2.0/25917080F8AD/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/BADFE83ED3>) |
| 102b:0533 | 103c:3381 | Matrox Electr... | MGA G200EH                           | 283   | mgag200    | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:0152 | 1028:0577 | Intel            | Xeon E3-1200 v2/3rd Gen Core proc... | 278   | i915       | [CEDF8AEE7E](<Desktop/Dell/OptiPlex/OptiPlex 7010/D5C9F81B8701/ARCH-ROLLING/6.6.65-1-LTS/X86_64/CEDF8AEE7E>) |
| 8086:0412 | 1028:05a4 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 275   | i915       | [F722EDF7A9](<Desktop/Dell/OptiPlex/OptiPlex 9020/DEAD93BBE620/LUBUNTU-22.04/6.8.0-50-GENERIC/X86_64/F722EDF7A9>) |
| 1002:164e | 1458:d000 | AMD              | Raphael                              | 274   | amdgpu     | [0D0A62D437](<Desktop/Gigabyte Technology/B650M/B650M D3HP/09BE719645F6/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/0D0A62D437>) |
| 8086:0166 | 1028:0534 | Intel            | 3rd Gen Core processor Graphics C... | 268   | i915       | [860E215DAF](<Notebook/Dell/Latitude/Latitude E6430/A0E982126F70/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/860E215DAF>) |
| 1002:15d8 | 1043:876b | AMD              | Picasso/Raven 2 [Radeon Vega Seri... | 267   | amdgpu     | [9A1D5CEFD0](<Desktop/CSL-Computer/T/T8186/9C4BEE3F5B7B/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9A1D5CEFD0>) |
| 8086:3e92 | 1043:8694 | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 266   | i915       | [79752B904B](<Desktop/ASUSTek Computer/PRIME/PRIME H310M-E R2.0/7D532FED2934/ELEMENTARY-8/6.8.0-49-GENERIC/X86_64/79752B904B>) |
| 8086:3ea0 | 103c:8549 | Intel            | WhiskeyLake-U GT2 [UHD Graphics 620] | 262   | i915       | [6781E260B0](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G6/6565E10C0338/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/6781E260B0>) |

### Input device controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1102:7002 | 1102:0020 | Creative Labs    | SB Live! Game Port                   | 267   | emu10k1_gp | [7EF8ACC2EB](<Desktop/MSI/MS/MS-7673/2B43C2F1A304/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.11.8-1-DEFAULT/X86_64/7EF8ACC2EB>) |
| 1102:7003 | 1102:0040 | Creative Labs    | SB Audigy Game Port                  | 203   | emu10k1_gp | [15EC08433F](<Desktop/Dell/OptiPlex/OptiPlex 790/A5A860ACB243/DEBIAN-12/6.1.0-26-AMD64/X86_64/15EC08433F>) |
| 1102:7003 | 1102:0060 | Creative Labs    | SB Audigy Game Port                  | 34    | emu10k1_gp | [2D3C35E364](<Server/Fujitsu/PRIMERGY/PRIMERGY TX2540 M1/25DC1F84A0CF/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/2D3C35E364>) |
| 1102:7004 | 1102:1003 | Creative Labs    | [SB Live! Value] Input device con... | 13    | emu10k1_gp | [C311ED8B76](<Desktop/Gigabyte Technology/970/970A-DS3P/0451DECC9D68/DRAUGEROS-7.7/6.9.10/X86_64/C311ED8B76>) |
| 1102:7005 | 1102:1002 | Creative Labs    | SB Audigy LS Game Port               | 10    | emu10k1_gp | [D110BB4405](<Desktop/Gigabyte Technology/H87/H87-D3H/91387BA22866/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/D110BB4405>) |
| 1319:0802 | 1319:1319 | Fortemedia       | Xwave QS3000A [FM801 game port]      | 9     | fm801_gp   | [66223D6EF0](<Desktop/ASUSTek Computer/P5/P5KPL-VM-S/0FDF3772C4F4/ELEMENTARY-5.1.7/5.4.0-113-GENERIC/X86_64/66223D6EF0>) |
| 127a:4312 | 1235:4312 | Rockwell Inte... | Riptide PCI Game Controller          | 1     | snd_rip... | [34867AD122](<Desktop/Supermicro/P4/P4DMS/7EDE05DEDB9F/LINUXMINT-19.1/4.15.0-139-GENERIC/I686/34867AD122>) |

### Iommu (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1631 | 1022:1631 | AMD              | Renoir/Cezanne IOMMU                 | 4613  |            | [69FF87B949](<Desktop/Gigabyte Technology/A520/A520 AORUS ELITE/81AB90394B6C/GENTOO-2.17/6.6.67-GENTOO/X86_64/69FF87B949>) |
| 1022:15d1 | 1022:15d1 | AMD              | Raven/Raven2 IOMMU                   | 4562  |            | [C5C9A457AA](<Notebook/Lenovo/V15-ADA/V15-ADA 82C7/DF20D99E1E88/DEBIAN-12/6.1.0-28-AMD64/X86_64/C5C9A457AA>) |
| 1022:1481 | 1022:1481 | AMD              | Starship/Matisse IOMMU               | 4088  |            | [726B65D6E8](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.10/4.18.0-553.27.1.EL8_10.X86_64/X86_64/726B65D6E8>) |
| 1022:1481 | 1043:87c0 | AMD              | Starship/Matisse IOMMU               | 1795  |            | [88B1C0C262](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING WIFI II/B8760FB55781/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/88B1C0C262>) |
| 1022:1451 | 1043:8747 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 1528  |            | [CF7D50FAE1](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-K II/24E629ECD716/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/CF7D50FAE1>) |
| 1022:1481 | 1043:8808 | AMD              | Starship/Matisse IOMMU               | 1454  |            | [DF3BBDD6E6](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/5A876E9931EF/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/DF3BBDD6E6>) |
| 1022:14d9 | 1043:8877 | AMD              | Raphael/Granite Ridge IOMMU          | 766   |            | [04F9FFDAB4](<Desktop/ASUSTek Computer/ROG/ROG STRIX B650-A GAMING WIFI/848E93DF68A9/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/04F9FFDAB4>) |
| 1022:14b6 | 1022:14b6 | AMD              | Family 17h-19h IOMMU                 | 743   |            | [2183EB76B7](<Tablet/ONE-NETBOOK/ONEXPLAYER/ONEXPLAYER Mini Pro/F55453A23AA1/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/2183EB76B7>) |
| 1022:1631 | 1043:8809 | AMD              | Renoir/Cezanne IOMMU                 | 562   |            | [989A72852C](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PLUS/4495A9F18FCB/ZORIN-17/6.8.0-50-GENERIC/X86_64/989A72852C>) |
| 1022:14e9 | 1022:14e9 | AMD              | Phoenix IOMMU                        | 472   |            | [046BBB97DB](<Notebook/Lenovo/IdeaPad/IdeaPad Pro 5 14APH8 83AM/E902B3B08EDD/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/046BBB97DB>) |
| 1022:15d1 | 1043:876b | AMD              | Raven/Raven2 IOMMU                   | 352   |            | [DAE8BF9671](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-K/234F8AC2996B/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/DAE8BF9671>) |
| 1022:1631 | 17aa:3815 | AMD              | Renoir/Cezanne IOMMU                 | 278   |            | [E544B8E949](<Notebook/Lenovo/Legion/Legion 5 15ACH6H 82JU/6D4B0B0F9308/ARCO-ROLLING/6.12.6-ARCH1-1/X86_64/E544B8E949>) |
| 1022:14d9 | 1022:14d9 | AMD              | Raphael/Granite Ridge IOMMU          | 252   |            | [7DB2107E2A](<Desktop/ASRock/B650/B650M-HDV-M.2/9DE4309FD01E/ARCH-ROLLING/6.12.8-ARCH1-1/X86_64/7DB2107E2A>) |
| 1022:1481 | 1462:7c02 | AMD              | Starship/Matisse IOMMU               | 243   |            | [77E32DABCD](<Desktop/MSI/MS-7/MS-7C02/AE386F556A9D/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/77E32DABCD>) |
| 1022:1631 | 17aa:5081 | AMD              | Renoir/Cezanne IOMMU                 | 212   |            | [7BFAD25E97](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 1 20UES5NA00/65C9066BF452/FEDORA-40/6.8.5-301.FC40.X86_64/X86_64/7BFAD25E97>) |
| 1022:14d9 | 1458:d000 | AMD              | Raphael/Granite Ridge IOMMU          | 209   |            | [0D0A62D437](<Desktop/Gigabyte Technology/B650M/B650M D3HP/09BE719645F6/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/0D0A62D437>) |
| 1022:1577 | 103c:8330 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 200   |            | [57B6786860](<Notebook/Hewlett-Packard/255/255 G6 Notebook PC/59F98AE9BF7D/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/57B6786860>) |
| 1022:1631 | 103c:887a | AMD              | Renoir/Cezanne IOMMU                 | 190   |            | [37B47880BB](<Notebook/Hewlett-Packard/Laptop/Laptop 15s-eq2xxx/911EAE7EAD9B/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/37B47880BB>) |
| 1022:1631 | 17aa:5097 | AMD              | Renoir/Cezanne IOMMU                 | 186   |            | [46361A1B83](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20Y70038US/1722BB93FF17/ARCH-ROLLING/6.12.7-ARCH1-1/X86_64/46361A1B83>) |
| 1022:1481 | 1462:7b86 | AMD              | Starship/Matisse IOMMU               | 179   |            | [89CD372074](<Desktop/MSI/MS-7/MS-7B86/3FF968BBEDE3/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/89CD372074>) |
| 1022:1577 | 103c:84ac | AMD              | Family 15h (Models 60h-6fh) I/O M... | 167   |            | [15039E5101](<Notebook/Hewlett-Packard/Laptop/Laptop 15-db0xxx/38F1157DCC54/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/15039E5101>) |
| 1022:1631 | 17aa:3803 | AMD              | Renoir/Cezanne IOMMU                 | 151   |            | [572F922D7C](<Notebook/Lenovo/Legion/Legion 5 15ARH05 82B5/5A86BFCF6422/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/572F922D7C>) |
| 1022:1631 | 1025:1455 | AMD              | Renoir/Cezanne IOMMU                 | 139   |            | [5D0C074A0F](<Notebook/Acer/Nitro/Nitro AN515-44/FCBB9CDE2DD2/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/5D0C074A0F>) |
| 1022:1631 | 17aa:507f | AMD              | Renoir/Cezanne IOMMU                 | 132   |            | [F6852CBDBB](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 2 20T6002LUS/C5DF2A83869A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/F6852CBDBB>) |
| 1022:15d1 | 17aa:380a | AMD              | Raven/Raven2 IOMMU                   | 129   |            | [5804FCEFEE](<Notebook/Lenovo/XiaoXinAir-14API/XiaoXinAir-14API 2019 81NJ/2F8A5EE9D05E/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/5804FCEFEE>) |
| 1022:1631 | 152d:1365 | AMD              | Renoir/Cezanne IOMMU                 | 129   |            | [030B263131](<Notebook/HUAWEI/BOM-WXX/BOM-WXX9/D1030F56CEDE/UBUNTU-22.04/5.15.0-25-GENERIC/X86_64/030B263131>) |
| 1022:1631 | 17aa:381d | AMD              | Renoir/Cezanne IOMMU                 | 129   |            | [271C85B332](<Notebook/Lenovo/IdeaPad/IdeaPad Gaming 3 15ACH6 82K2/139E64F0F5B5/STEAMOS-3.6.20/6.5.0-VALVE22-1-NEPTUNE-65-G9A338ED8A75E/X86_64/271C85B332>) |
| 1022:1577 | 1025:1192 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 127   |            | [48FA2FD34A](<Notebook/Acer/Aspire/Aspire A315-21/2E415FCD1FD1/UBUNTU-18.04/5.4.0-150-GENERIC/X86_64/48FA2FD34A>) |
| 1022:1451 | 1462:7c02 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 126   |            | [88D10A1126](<Desktop/MSI/MS-7/MS-7C02/DD7D36D47449/LMDE-6/6.1.0-28-AMD64/X86_64/88D10A1126>) |
| 1022:1481 | 1462:7c95 | AMD              | Starship/Matisse IOMMU               | 125   |            | [A3C4D34290](<Desktop/MSI/MS-7/MS-7C95/D9235FBE7F06/ARCH-ROLLING/6.11.5-X64V3-XANMOD1-1-EDGE-X64V3/X86_64/A3C4D34290>) |
| 1022:1631 | 17aa:5082 | AMD              | Renoir/Cezanne IOMMU                 | 118   |            | [C68A17F027](<Notebook/Lenovo/ThinkPad/ThinkPad T14s Gen 1 20UH002LUK/3790C38E2827/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/C68A17F027>) |
| 1022:1631 | 1d05:109f | AMD              | Renoir/Cezanne IOMMU                 | 118   |            | [D1FE4C6194](<Notebook/TUXEDO/Pulse/Pulse 14 Gen1/4BA1C6A378B0/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/D1FE4C6194>) |
| 1022:15d1 | 17aa:380b | AMD              | Raven/Raven2 IOMMU                   | 116   |            | [33DAD31E6E](<Notebook/Lenovo/IdeaPad/IdeaPad S340-15API 81NC/8942D56644CD/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/33DAD31E6E>) |
| 1022:1631 | 17aa:5094 | AMD              | Renoir/Cezanne IOMMU                 | 116   |            | [0BB2FA170C](<Notebook/Lenovo/ThinkPad/ThinkPad P14s Gen 2a 21A0005RUS/B39DC970E8A6/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/0BB2FA170C>) |
| 1022:1481 | 1462:7b89 | AMD              | Starship/Matisse IOMMU               | 114   |            | [597E16BA37](<Desktop/MSI/MS-7/MS-7B89/716384C17A3C/LINUXMINT-21.3/6.2.0-39-GENERIC/X86_64/597E16BA37>) |
| 1022:15d1 | 1025:134d | AMD              | Raven/Raven2 IOMMU                   | 114   |            | [734FD13848](<Notebook/Acer/Aspire/Aspire A315-42/3035086EFC0B/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/734FD13848>) |
| 1022:1451 | 1462:7b86 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 113   |            | [2A3140FF53](<Desktop/MSI/MS-7/MS-7B86/10FCED84DE65/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/2A3140FF53>) |
| 1022:15d1 | 103c:84ae | AMD              | Raven/Raven2 IOMMU                   | 112   |            | [DC26AE6F85](<Notebook/Hewlett-Packard/Laptop/Laptop 15-db0xxx/6098CDB2FF28/LIBERTYOS/5.6.15-ARCH1-1/X86_64/DC26AE6F85>) |
| 1022:1631 | 17aa:507e | AMD              | Renoir/Cezanne IOMMU                 | 112   |            | [031C8D3940](<Notebook/Lenovo/ThinkPad/ThinkPad L14 Gen 1 20U6001ABO/11626807B73D/ARCH-ROLLING/6.10.6-ARCH1-1/X86_64/031C8D3940>) |
| 1022:1481 | 1462:7c56 | AMD              | Starship/Matisse IOMMU               | 111   |            | [93AFAFB17B](<Desktop/MSI/MS-7/MS-7C56/6AF597F49A57/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/93AFAFB17B>) |
| 1022:1631 | 17aa:3808 | AMD              | Renoir/Cezanne IOMMU                 | 107   |            | [F598642EE7](<Notebook/Lenovo/IdeaPad/IdeaPad Gaming 3 15ARH05 82EY/6FBB4CF9718F/ARCH-ROLLING/6.12.7-ZEN1-1-ZEN/X86_64/F598642EE7>) |
| 1022:1631 | 1e83:3e30 | AMD              | Renoir/Cezanne IOMMU                 | 107   |            | [5B9314F900](<Notebook/HUAWEI/HVY-WXX/HVY-WXX9/5686157B09BB/ARTIX-ROLLING/6.12.4-ARTIX1-1/X86_64/5B9314F900>) |
| 1022:1631 | 1043:87e1 | AMD              | Renoir/Cezanne IOMMU                 | 105   |            | [61D14E44B2](<Desktop/CSL-Computer/V2888/V28880w/27C9C6FA7847/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/61D14E44B2>) |
| 1022:1577 | 17aa:380e | AMD              | Family 15h (Models 60h-6fh) I/O M... | 103   |            | [65A80C8AE1](<Notebook/Lenovo/V145-15AST/V145-15AST 81MT/A2FAC127452C/XUBUNTU-22.04/6.8.0-49-GENERIC/X86_64/65A80C8AE1>) |
| 1022:1481 | 1462:7c94 | AMD              | Starship/Matisse IOMMU               | 101   |            | [F7C8A6C602](<Desktop/MSI/MS-7/MS-7C94/96058053E9EC/ENDEAVOUROS-ROLLING/6.6.69-1-LTS/X86_64/F7C8A6C602>) |
| 1022:1631 | 103c:876e | AMD              | Renoir/Cezanne IOMMU                 | 101   |            | [36C7B8CBCF](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 13-ay0xxx/AD61E4338E34/KDE-NEON-24.04/6.8.0-48-GENERIC/X86_64/36C7B8CBCF>) |
| 1022:1481 | 1462:7c35 | AMD              | Starship/Matisse IOMMU               | 100   |            | [FC581D20C5](<Desktop/MSI/MS-7/MS-7C35/313CF5DF8E4B/NIXOS-25.05/6.12.2-ZEN1/X86_64/FC581D20C5>) |
| 1022:1631 | 1e83:3e33 | AMD              | Renoir/Cezanne IOMMU                 | 99    |            | [50D20229D8](<Notebook/HUAWEI/KLVL-WXX/KLVL-WXX9/75C49E26FFD1/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/50D20229D8>) |
| 1022:14e9 | f111:0006 | AMD              | Phoenix IOMMU                        | 95    |            | [041F977A25](<Notebook/Framework/Laptop/Laptop 13/621585FACCFA/NIXOS-25.05/6.6.67-HARDENED1/X86_64/041F977A25>) |
| 1022:1631 | 1043:1602 | AMD              | Renoir/Cezanne IOMMU                 | 94    |            | [EB57D61B77](<Notebook/ASUSTek Computer/ROG/ROG Strix G533QS_G533QS/4D51933FBEE0/FEDORA-40/6.11.3-200.FC40.X86_64/X86_64/EB57D61B77>) |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:816c | 17aa:5081 | Realtek Semic... | RTL8111xP IPMI interface             | 210   |            | [7BFAD25E97](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 1 20UES5NA00/65C9066BF452/FEDORA-40/6.8.5-301.FC40.X86_64/X86_64/7BFAD25E97>) |
| 10ec:816c | 17aa:5082 | Realtek Semic... | RTL8111xP IPMI interface             | 110   |            | [C68A17F027](<Notebook/Lenovo/ThinkPad/ThinkPad T14s Gen 1 20UH002LUK/3790C38E2827/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/C68A17F027>) |
| 10ec:816c | 17aa:507e | Realtek Semic... | RTL8111xP IPMI interface             | 82    |            | [07D669F90A](<Notebook/Lenovo/ThinkPad/ThinkPad L15 Gen 1 20U8S1CA01/70DC9DC07D38/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/07D669F90A>) |
| 10ec:816c | 17aa:5125 | Realtek Semic... | RTL8111xP IPMI interface             | 74    |            | [31A4026530](<Notebook/Lenovo/ThinkPad/ThinkPad T495 20NKS2JD00/9A72CAFFBFD7/ARCH-ROLLING/6.12.4-ARCH1-1/X86_64/31A4026530>) |
| 10ec:816c | 17aa:5126 | Realtek Semic... | RTL8111xP IPMI interface             | 61    |            | [7FF6BAE738](<Notebook/Lenovo/ThinkPad/ThinkPad X395 20NLS0J400/AFAC9413838A/ARCO-ROLLING/6.12.8-ZEN1-1-ZEN/X86_64/7FF6BAE738>) |
| 10ec:816c | 1043:85b5 | Realtek Semic... | RTL8111xP IPMI interface             | 49    |            | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 10ec:816c | 103c:8584 | Realtek Semic... | RTL8111xP IPMI interface             | 33    |            | [B46FF16EA8](<Notebook/Hewlett-Packard/EliteBook/EliteBook 745 G6/8A2E53C57700/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/B46FF16EA8>) |
| 10ec:816c | 103c:8464 | Realtek Semic... | RTL8111xP IPMI interface             | 31    |            | [EE42824C61](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 705 G4 DM 65W/512883705066/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/EE42824C61>) |
| 10ec:816c | 17aa:5122 | Realtek Semic... | RTL8111xP IPMI interface             | 29    |            | [DC1B85E281](<Notebook/Lenovo/ThinkPad/ThinkPad A485 20RUTOEIIT/10E9FB511960/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/DC1B85E281>) |
| 10ec:816c | 103c:83d5 | Realtek Semic... | RTL8111xP IPMI interface             | 27    |            | [307803B17E](<Notebook/Hewlett-Packard/EliteBook/EliteBook 755 G5/ACA8D4D2B4B3/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/307803B17E>) |
| 10ec:816c | 17aa:5094 | Realtek Semic... | RTL8111xP IPMI interface             | 27    |            | [0BB2FA170C](<Notebook/Lenovo/ThinkPad/ThinkPad P14s Gen 2a 21A0005RUS/B39DC970E8A6/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/0BB2FA170C>) |
| 10ec:816c | 1849:8168 | Realtek Semic... | RTL8111xP IPMI interface             | 25    | ipmi_si    | [1FF935C41C](<Desktop/ASRock/4X4-5000/4X4-5000 Series/AE999B4C36E9/ARCO-ROLLING/6.12.6-1-CACHYOS/X86_64/1FF935C41C>) |
| 10ec:816c | 10ec:0123 | Realtek Semic... | RTL8111xP IPMI interface             | 12    |            | [71C0A5ABE5](<Desktop/ASRock/B85M/B85M DASH-OL R2.0/1E8B2DFD9FC0/CACHYOS/6.1.7-ZEN1-1.1-ZEN/X86_64/71C0A5ABE5>) |
| 10ec:816c | 1025:1166 | Realtek Semic... | RTL8111xP IPMI interface             | 10    |            | [316499457A](<Desktop/Acer/Veriton/Veriton N4640G/C7441F36CF0D/OPENMANDRIVA-23.08/6.4.11-DESKTOP-1OMV2390/X86_64/316499457A>) |
| 10ec:816c | 1025:1248 | Realtek Semic... | RTL8111xP IPMI interface             | 10    |            | [2C0D5D89B6](<Desktop/Acer/Veriton/Veriton N4660G/E79EECC2BCF0/ROSA-12.5.1/6.6.27-GENERIC-3ROSA2021.1-X86_64/X86_64/2C0D5D89B6>) |
| 10ec:816c | 103c:83da | Realtek Semic... | RTL8111xP IPMI interface             | 10    |            | [747AE84F9E](<Notebook/Hewlett-Packard/EliteBook/EliteBook 735 G5/80DE54A8AB92/FEDORA-41/6.11.11-300.FC41.X86_64/X86_64/747AE84F9E>) |
| 10ec:816c | 103c:8401 | Realtek Semic... | RTL8111xP IPMI interface             | 10    |            | [FD6948A4E9](<Notebook/Hewlett-Packard/ProBook/ProBook 645 G4/8AB39897C21D/LINUXMINT-22/6.11.7-X64V3-XANMOD1/X86_64/FD6948A4E9>) |
| 10ec:816c | 103c:8463 | Realtek Semic... | RTL8111xP IPMI interface             | 10    |            | [77D40D025A](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 705 G4 SFF/5F7D3A2437C5/ELEMENTARY-8/6.8.0-50-GENERIC/X86_64/77D40D025A>) |
| 10ec:816c | 103c:8589 | Realtek Semic... | RTL8111xP IPMI interface             | 10    |            | [5074DE8248](<Notebook/Hewlett-Packard/EliteBook/EliteBook 735 G6/46668BBF2992/MANJARO-24.2.0/6.10.13-3-MANJARO/X86_64/5074DE8248>) |
| 10ec:816c | 17aa:30fd | Realtek Semic... | RTL8111xP IPMI interface             | 9     |            | [C41E4D04F8](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10M30009US/2E7C2ABFFDEE/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/C41E4D04F8>) |
| 10ec:816c | 17aa:3151 | Realtek Semic... | RTL8111xP IPMI interface             | 9     |            | [46204EEB51](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A40011US/467E9C948DD7/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/46204EEB51>) |
| 10ec:816c | 17aa:511f | Realtek Semic... | RTL8111xP IPMI interface             | 9     |            | [2432557E37](<Notebook/Lenovo/ThinkPad/ThinkPad A275 20KDS01T00/02AA87249F0F/OPENMANDRIVA-24.07/6.9.7-DESKTOP-1OMV2490/X86_64/2432557E37>) |
| 10ec:816c | 17aa:5123 | Realtek Semic... | RTL8111xP IPMI interface             | 8     |            | [AB309A9EB4](<Notebook/Lenovo/ThinkPad/ThinkPad A285 20MXS0AE00/86672CB6EF1A/UBUNTU-22.04/6.8.0-49-GENERIC/X86_64/AB309A9EB4>) |
| 10ec:816c | 103c:83dd | Realtek Semic... | RTL8111xP IPMI interface             | 7     |            | [A000EF7E0E](<Mini Pc/Hewlett-Packard/mt44/mt44 Mobile Thin Client/44702C600CC4/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/A000EF7E0E>) |
| 10ec:816c | 103c:8461 | Realtek Semic... | RTL8111xP IPMI interface             | 7     |            | [F7C5ABE471](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 705 G4 MT/BB5ADCA48A7A/OPENMANDRIVA-24.08/6.10.1-DESKTOP-1OMV2490/X86_64/F7C5ABE471>) |
| 10ec:816c | 17aa:5095 | Realtek Semic... | RTL8111xP IPMI interface             | 7     |            | [C71041FA59](<Notebook/Lenovo/ThinkPad/ThinkPad X13 Gen 2a 20XH001KPB/36BD3967D86C/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.6.3-1-DEFAULT/X86_64/C71041FA59>) |
| 10ec:816c | 1025:1069 | Realtek Semic... | RTL8111xP IPMI interface             | 6     |            | [3713DBB1E6](<Desktop/Acer/Veriton/Veriton N4640G/A6EA8D157CCF/LINUXMINT-21.1/5.15.0-125-GENERIC/X86_64/3713DBB1E6>) |
| 10ec:816c | 103c:8617 | Realtek Semic... | RTL8111xP IPMI interface             | 6     |            | [C91CF51CF3](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 705 G5 SFF/C2DC8B4E70D9/ARCH-ROLLING/6.10.8-ZEN1-1-ZEN/X86_64/C91CF51CF3>) |
| 10ec:816c | 103c:8619 | Realtek Semic... | RTL8111xP IPMI interface             | 6     |            | [A916110AD9](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 705 G5 Desktop Mini/6CA0427F2801/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/A916110AD9>) |
| 10ec:816c | 17aa:5091 | Realtek Semic... | RTL8111xP IPMI interface             | 6     |            | [0E240E7A70](<Notebook/Lenovo/ThinkPad/ThinkPad L14 Gen 2a 20X6S1DS0P/AFEAC727552D/POP!_OS-22.04/6.8.0-76060800DAILY20240311-GENERIC/X86_64/0E240E7A70>) |
| 10ec:816c | 17aa:511e | Realtek Semic... | RTL8111xP IPMI interface             | 6     |            | [57D3147D55](<Notebook/Lenovo/ThinkPad/ThinkPad A475 20KMS0MR00/1E615D3F0286/XUBUNTU-22.04/6.11.0-061100-GENERIC/X86_64/57D3147D55>) |
| 10ec:816c | 1019:81ea | Realtek Semic... | RTL8111xP IPMI interface             | 5     |            | [3307527ADA](<Desktop/Positivo/POS-EAA75/POS-EAA75DE/4F0A2C672B2A/LINUXMINT-21.1/5.15.0-76-GENERIC/X86_64/3307527ADA>) |
| 10ec:816c | 103c:8618 | Realtek Semic... | RTL8111xP IPMI interface             | 5     |            | [6F804C5758](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 705 G5 SFF/7E25878F2263/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/6F804C5758>) |
| 10ec:816c | 103c:8626 | Realtek Semic... | RTL8111xP IPMI interface             | 5     |            | [9376D144C5](<Desktop/Hewlett-Packard/ProDesk/ProDesk 405 G4 Desktop Mini/2DAAAA00B6F3/ARCH-ROLLING/6.10.6-ZEN1-1-ZEN/X86_64/9376D144C5>) |
| 10ec:816c | 17aa:3148 | Realtek Semic... | RTL8111xP IPMI interface             | 5     |            | [90245DEC30](<Desktop/Lenovo/ThinkCentre/ThinkCentre M75s-1 11AAS0YS00/45BA73D1677A/KUBUNTU-24.04/6.8.0-47-GENERIC/X86_64/90245DEC30>) |
| 10ec:816c | 1b0a:01bb | Realtek Semic... | RTL8111xP IPMI interface             | 5     |            | [C3A85EA71C](<Desktop/Positivo/D/D2200/3E48AA77F6A4/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/C3A85EA71C>) |
| 10ec:816c | 103c:83e8 | Realtek Semic... | RTL8111xP IPMI interface             | 4     |            | [E2F0A2A950](<Desktop/Hewlett-Packard/ProDesk/ProDesk 405 G4 SFF/2ABDD5A2BEDA/ENDLESS-6.0.3/6.5.0-10-GENERIC/X86_64/E2F0A2A950>) |
| 10ec:816c | 103c:8523 | Realtek Semic... | RTL8111xP IPMI interface             | 4     |            | [3DD5227110](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/9AC0AB63F3A5/ARCH-ROLLING/6.9.7-ARCH1-1/X86_64/3DD5227110>) |
| 10ec:816c | 17aa:50b6 | Realtek Semic... | RTL8111xP IPMI interface             | 4     |            | [E6F2754930](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 3 21CGS03K00/8F708CCA5431/FEDORA-40/6.8.10-300.FC40.X86_64/X86_64/E6F2754930>) |
| 10ec:816c | 1b0a:00e5 | Realtek Semic... | RTL8111xP IPMI interface             | 4     |            | [290983AC13](<Desktop/Pegatron/SM/SM 3330/2776FC1DCCA6/UBUNTU-22.04/6.2.0-33-GENERIC/X86_64/290983AC13>) |
| 10ec:816c | 1025:074c | Realtek Semic... | RTL8111xP IPMI interface             | 3     |            | [F438D41562](<Desktop/Acer/Veriton/Veriton N4620G/25BD0D09E552/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/F438D41562>) |
| 10ec:816c | 1025:080a | Realtek Semic... | RTL8111xP IPMI interface             | 3     |            | [4EE96F70B9](<Desktop/Acer/Veriton/Veriton L4630G/25962A0C08AF/UBUNTU-22.04/5.15.0-83-GENERIC/X86_64/4EE96F70B9>) |
| 10ec:816c | 1025:1291 | Realtek Semic... | RTL8111xP IPMI interface             | 3     |            | [9949F21F98](<All In One/Acer/Veriton/Veriton Z4660G/D6F2FD870657/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/9949F21F98>) |
| 10ec:816c | 17aa:3141 | Realtek Semic... | RTL8111xP IPMI interface             | 3     |            | [AEEE08EFEA](<Desktop/Lenovo/ThinkCentre/ThinkCentre M725s 10VUS19H00/7310E084D4F7/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/AEEE08EFEA>) |
| 10ec:816c | 17aa:3181 | Realtek Semic... | RTL8111xP IPMI interface             | 3     |            | [D7B1A6E8B1](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75n 11GW000BUS/63BF4E6C46E3/DEBIAN-12/6.1.0-18-AMD64/X86_64/D7B1A6E8B1>) |
| 10ec:816c | 1025:078d | Realtek Semic... | RTL8111xP IPMI interface             | 2     |            | [4BA25709B1](<Desktop/Acer/Veriton/Veriton X4630G/52225C29D1DE/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/4BA25709B1>) |
| 10ec:816c | 1025:1001 | Realtek Semic... | RTL8111xP IPMI interface             | 2     |            | [85C69E6034](<Desktop/Acer/Veriton/Veriton X4110G/3098E7004883/FEDORA-39/6.6.6-200.FC39.X86_64/X86_64/85C69E6034>) |
| 10ec:816c | 1025:1005 | Realtek Semic... | RTL8111xP IPMI interface             | 2     |            | [DD3E15FEEE](<Desktop/Acer/Veriton/Veriton X4640G/8169F352B6C1/OPENMANDRIVA-23.03/6.2.2-DESKTOP-1OMV2390/X86_64/DD3E15FEEE>) |
| 10ec:816c | 1025:1290 | Realtek Semic... | RTL8111xP IPMI interface             | 2     |            | [A27363041A](<All In One/Acer/Veriton/Veriton Z4860G/8955EDC1BE49/ENDLESS-3.9.1/5.8.0-14-GENERIC/X86_64/A27363041A>) |
| 10ec:816c | 1025:1519 | Realtek Semic... | RTL8111xP IPMI interface             | 2     |            | [54D0A278B8](<Desktop/Acer/Veriton/Veriton S2680G/E3D66AB41010/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/54D0A278B8>) |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 103c:3302 | 103c:3305 | Hewlett-Packard  | Integrated Lights-Out Standard KC... | 79    | ipmi_si    | [55EEC713DB](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML350 G5/AB611AC3CA00/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/55EEC713DB>) |
| 10ec:816c | 10ec:8168 | Realtek Semic... | RTL8111xP IPMI interface             | 77    | ipmi_si    | [05481678BA](<Desktop/Lenovo/ThinkCentre/ThinkCentre M75s Gen 5 12TACTO1WW/149D669D5DE2/DEBIAN-12/6.8.12-4-PVE/X86_64/05481678BA>) |
| 10ec:816c | 1458:e000 | Realtek Semic... | RTL8111xP IPMI interface             | 34    | ipmi_si    | [EB235E849D](<Desktop/Daten Tecnologia/DB85/DB85PRO/D015DA85E79D/FEDORA-37/6.0.7-301.FC37.X86_64/X86_64/EB235E849D>) |
| 10ec:816c | 17aa:3130 | Realtek Semic... | RTL8111xP IPMI interface             | 29    |            | [3F2770B9FE](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VHS2DL00/E4809D71F4E7/DEVUAN-6/6.11.4-AMD64/X86_64/3F2770B9FE>) |
| 10ec:816c | 17aa:30b2 | Realtek Semic... | RTL8111xP IPMI interface             | 25    | ipmi_si    | [A97FBD8B52](<Desktop/Lenovo/ThinkCentre/ThinkCentre M79 10CTA00VLS/F90C2646AF96/MANJARO-24.2.1/6.12.4-1-MANJARO/X86_64/A97FBD8B52>) |
| 10ec:816c | 1734:1178 | Realtek Semic... | RTL8111xP IPMI interface             | 19    | ipmi_si    | [1F2539C425](<Desktop/Fujitsu/CELSIUS/CELSIUS M470-2/21D1272FECDC/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/1F2539C425>) |
| 10ec:816c | 17aa:3089 | Realtek Semic... | RTL8111xP IPMI interface             | 19    | ipmi_si    | [3DA6BD30AF](<Desktop/Lenovo/ThinkCentre/ThinkCentre M78 10BNS02900/E7C330C06E6B/BLACKPANTHER-OS-18.1/5.15.85-DESKTOP-1BP/X86_64/3DA6BD30AF>) |
| 10ec:816c | 1025:078b | Realtek Semic... | RTL8111xP IPMI interface             | 13    |            | [E53C39772B](<Desktop/Acer/Veriton/Veriton M4630G/5658EE9D6BD4/LINUXMINT-22/6.8.0-49-GENERIC/X86_64/E53C39772B>) |
| 10ec:816c | 17aa:36c7 | Realtek Semic... | RTL8111xP IPMI interface             | 7     |            | [D113DEFBE8](<Desktop/Lenovo/ThinkCentre/ThinkCentre M715s 10MCS03C00/5A31A652747A/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/D113DEFBE8>) |
| 8086:108e | 8086:0000 | Intel            | 82573E KCS (Active Management)       | 6     | ipmi_si    | [2ACFD9617B](<Desktop/Intel/S3000AHLX/S3000AHLX D40858-208/2922366B6C9A/UBUNTU-20.04/5.4.0-77-GENERIC/X86_64/2ACFD9617B>) |
| 10ec:816c | 1025:1071 | Realtek Semic... | RTL8111xP IPMI interface             | 3     |            | [910DA2B318](<All In One/Acer/Veriton/Veriton Z4820G/F80CAA7F129B/DEBIAN-12/6.1.0-4-AMD64/X86_64/910DA2B318>) |
| 10ec:816c | 1043:8578 | Realtek Semic... | RTL8111xP IPMI interface             | 2     | ipmi_si    | [B6E3DBB57A](<Desktop/ASUSTek Computer/F2/F2A85-M2/BD5BF4399DAA/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/B6E3DBB57A>) |
| 10ec:816c | 10ec:816c | Realtek Semic... | RTL8111xP IPMI interface             | 2     |            | [C043DF4EFB](<Desktop/Fujitsu/CELSIUS/CELSIUS M470/8622786E631E/XUBUNTU-20.04/5.15.0-67-GENERIC/X86_64/C043DF4EFB>) |

### Isdn adapter (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1244:0e00 | 1244:0e00 | AVM              | Fritz!Card PCI v2.0 ISDN             | 14    | fcpci      | [697BAF484F](<Desktop/Tarox/X48/X48-DS4/52C8F2591573/UBUNTU-24.04/6.8.0-47-GENERIC/X86_64/697BAF484F>) |
| 1244:0a00 | 1244:0a00 | AVM              | A1 ISDN [Fritz]                      | 11    | fcpci      | [4817937B18](<Desktop/Gigabyte Technology/GA-880/GA-880GM-USB3/291D91B2C115/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.5.4-1-DEFAULT/X86_64/4817937B18>) |
| 1397:2bd0 | 1397:2bd0 | Cologne Chip ... | ISDN network controller [HFC-PCI]    | 2     | hfcpci     | [D356DEB17B](<Desktop/MSI/MS/MS-6701/592887AB254B/UBUNTU-MATE-18.04/4.15.0-213-GENERIC/I686/D356DEB17B>) |
| e159:0001 | b1d9:0003 | Tiger Jet Net... | Tiger3XX Modem/ISDN interface        | 2     | wctdm      | [55AD7B2405](<Desktop/Others/Others/Others/6E6FB0F4EED3/DEBIAN-12/6.1.0-23-POWERPC64LE/PPC64LE/55AD7B2405>) |
| 1048:1000 | 1048:1000 | Elsa             | QuickStep 1000                       | 1     |            | [4622016059](<Desktop/Medion/MS/MS-7318/04DDF3A09383/DEBIAN-11/5.10.0-19-AMD64/X86_64/4622016059>) |
| 1050:6692 | 16ec:3409 | Winbond Elect... | W6692 PCI ISDN S/T-Controller        | 1     | w6692      | [B67E414D65](<Desktop/ASUSTek Computer/M2/M2N-TE/FE36EC0A6334/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/B67E414D65>) |
| 1133:e00b | 1133:e00b | Dialogic         | Diva ISDN PCI 2.02                   | 1     |            | [AC7FD78AB8](<Desktop/Gigabyte Technology/965/965P-DS3/49A022364CAD/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/AC7FD78AB8>) |
| 1397:2bd0 | 1075:c101 | Cologne Chip ... | ISDN network controller [HFC-PCI]    | 1     | hfcpci     | [BE977291B5](<Desktop/Biostar/GF8200C/GF8200C M2+/6FA0FEDC4385/LINUXMINT-19.3/5.4.0-86-GENERIC/X86_64/BE977291B5>) |
| e159:0001 | 795e:0001 | Tiger Jet Net... | Tiger3XX Modem/ISDN interface        | 1     | wcte11xp   | [FE13415AC0](<Desktop/Dell/Vostro/Vostro 3670/6972435545F1/UBUNTU-18.04/4.15.0-135-GENERIC/X86_64/FE13415AC0>) |
| e159:0001 | 79fe:0001 | Tiger Jet Net... | Tiger3XX Modem/ISDN interface        | 1     | wcte11xp   | [B6E88B98F7](<Desktop/Dell/Vostro/Vostro 3670/62A337642D43/UBUNTU-18.04/4.15.0-1065-OEM/X86_64/B6E88B98F7>) |
| e159:0001 | 9100:0001 | Tiger Jet Net... | Tiger3XX Modem/ISDN interface        | 1     | netjet     | [74F31779A2](<Desktop/Gigabyte Technology/M68/M68MT-S2P/7C8ED4277CFD/XUBUNTU-20.04/5.8.0-43-GENERIC/X86_64/74F31779A2>) |

### Keyboard controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1af4:1052 | 1af4:1100 | Red Hat          | Virtio 1.0 input                     | 3     | virtio_pci | [D237816BD5](<Desktop/QEMU/Standard/Standard PC/418878F10378/DEBIAN-12/6.1.0-28-AMD64/X86_64/D237816BD5>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a36f | 8086:7270 | Intel            | Cannon Lake PCH Shared SRAM          | 2985  |            | [639EB0E4FC](<Desktop/Gigabyte Technology/H370M/H370M D3H GSM/D391F95DF729/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/639EB0E4FC>) |
| 8086:51ef |           | Intel            | Alder Lake PCH Shared SRAM           | 1632  |            | [9A04090DED](<Notebook/MSI/Katana/Katana 17 B12UCR/B0AD73F94A60/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/9A04090DED>) |
| 8086:43ef |           | Intel            | Tiger Lake-H Shared SRAM             | 1579  |            | [D0DCE2F4FE](<Notebook/MSI/Sword/Sword 15 A11UD/546EC6D8F99C/FSL/6.12.7-ARCH1-1/X86_64/D0DCE2F4FE>) |
| 8086:a121 | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 1450  | vfio_pci   | [FF2E84AB02](<Desktop/ASUSTek Computer/H110/H110M-E-M.2/4907896789F3/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/FF2E84AB02>) |
| 10de:0a88 |           | Nvidia           | MCP79 Memory Controller              | 1126  |            | [DE39DE3147](<Notebook/Apple/MacBookPro5/MacBookPro5,5/AE9A7F9028B1/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/DE39DE3147>) |
| 8086:06ef | 8086:7270 | Intel            | Comet Lake PCH Shared SRAM           | 1103  |            | [98506E2506](<Notebook/ASUSTek Computer/ROG/ROG Strix G712LV_G712LV/5B2C2374494E/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/98506E2506>) |
| 10de:0a89 |           | Nvidia           | MCP79 Memory Controller              | 1098  |            | [DE39DE3147](<Notebook/Apple/MacBookPro5/MacBookPro5,5/AE9A7F9028B1/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/DE39DE3147>) |
| 10de:0aa4 |           | Nvidia           | MCP79 Memory Controller              | 1097  |            | [DE39DE3147](<Notebook/Apple/MacBookPro5/MacBookPro5,5/AE9A7F9028B1/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/DE39DE3147>) |
| 10de:0a98 | 10de:cb79 | Nvidia           | MCP79 Memory Controller              | 1078  |            | [DE39DE3147](<Notebook/Apple/MacBookPro5/MacBookPro5,5/AE9A7F9028B1/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/DE39DE3147>) |
| 8086:a2a1 | 1043:8694 | Intel            | 200 Series/Z370 Chipset Family Po... | 1032  |            | [10FD8EF9DD](<Desktop/ASUSTek Computer/TUF/TUF Z370-PLUS GAMING II/76981D36E1E4/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/10FD8EF9DD>) |
| 8086:9d21 | 8086:7270 | Intel            | Sunrise Point-LP PMC                 | 968   | intel_p... | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:a2a1 | 1458:5001 | Intel            | 200 Series/Z370 Chipset Family Po... | 940   |            | [A49FDE4DF3](<Desktop/Gigabyte Technology/B365M/B365M DS3H/406A103EBD76/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/A49FDE4DF3>) |
| 8086:7aa7 |           | Intel            | Alder Lake-S PCH Shared SRAM         | 931   | vfio_pci   | [BBBB62D243](<Desktop/ASRock/Z690/Z690M-ITX-ax/7E8E76A3D17C/KUBUNTU-22.04/6.5.0-41-LOWLATENCY/X86_64/BBBB62D243>) |
| 8086:a36f | 1043:8694 | Intel            | Cannon Lake PCH Shared SRAM          | 826   |            | [D6E8F1EE6C](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-P/DD926E3C669B/LMDE-6/6.11.10+BPO-AMD64/X86_64/D6E8F1EE6C>) |
| 8086:a121 | 1458:5001 | Intel            | 100 Series/C230 Series Chipset Fa... | 815   | vfio_pci   | [AD40DB7F67](<Desktop/Gigabyte Technology/Z170X-Gaming/Z170X-Gaming 7/4DE1A28702A7/ZORIN-17/6.8.0-50-GENERIC/X86_64/AD40DB7F67>) |
| 8086:7a27 |           | Intel            | Raptor Lake-S PCH Shared SRAM        | 772   |            | [8404FEEF08](<Desktop/ASRock/Z790/Z790 PG SONIC/CBBFEFF3B8F7/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/8404FEEF08>) |
| 8086:a0ef |           | Intel            | Tiger Lake-LP Shared SRAM            | 772   |            | [5CB8B93A47](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/87502A19E545/NOBARA-41/6.12.8-200.FSYNC.FC41.X86_64/X86_64/5CB8B93A47>) |
| 8086:9def | 8086:7270 | Intel            | Cannon Point-LP Shared SRAM          | 698   |            | [50FF12C678](<Notebook/ASUSTek Computer/VivoBook/VivoBook S13 X330FN_S330FN/5D11FE94E7EF/DEBIAN-12/6.1.0-28-AMD64/X86_64/50FF12C678>) |
| 8086:34ef |           | Intel            | Ice Lake-LP DRAM Controller          | 668   |            | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 10de:03f5 | 1849:03eb | Nvidia           | MCP61 Memory Controller              | 601   |            | [CB76400A00](<Desktop/ASRock/N68-S/N68-S UCC/3C232072D095/NEPTUNE-8.1/6.1.0-18-AMD64/X86_64/CB76400A00>) |
| 8086:02ef | 8086:7270 | Intel            | Comet Lake PCH-LP Shared SRAM        | 589   |            | [4EE757E2C0](<Notebook/Positivo Bahia - VAIO/VJFE52/VJFE52F11X-B2511H/9DDB403A7827/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/4EE757E2C0>) |
| 8086:9def |           | Intel            | Cannon Point-LP Shared SRAM          | 577   |            | [61FE1222C2](<Notebook/Lenovo/ThinkPad/ThinkPad E490 20N8CTO1WW/E5006ED04FFC/DEBIAN-12/6.1.0-28-AMD64/X86_64/61FE1222C2>) |
| 8086:7aa7 | 1043:8694 | Intel            | Alder Lake-S PCH Shared SRAM         | 561   |            | [F8371D3425](<Desktop/ASUSTek Computer/PRIME/PRIME B660M-A WIFI D4/08AB6A0E635D/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/F8371D3425>) |
| 8086:43ef | 1043:8694 | Intel            | Tiger Lake-H Shared SRAM             | 555   |            | [63751B6A23](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z590-E GAMING WIFI/802DD0234B9E/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/63751B6A23>) |
| 10de:03e2 | 1849:03e2 | Nvidia           | MCP61 Host Bridge                    | 553   |            | [CB76400A00](<Desktop/ASRock/N68-S/N68-S UCC/3C232072D095/NEPTUNE-8.1/6.1.0-18-AMD64/X86_64/CB76400A00>) |
| 8086:a2a1 | 1849:a2a1 | Intel            | 200 Series/Z370 Chipset Family Po... | 434   |            | [DC5750E7FC](<Desktop/ASRock/B250/B250 Gaming K4/31792D99A259/UBUNTU-20.04/5.4.0-204-GENERIC/X86_64/DC5750E7FC>) |
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 376   |            | [DA4BCC0047](<Desktop/MACHINIST/H/H110/291DFB83749B/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/DA4BCC0047>) |
| 8086:9d21 | 17aa:225d | Intel            | Sunrise Point-LP PMC                 | 374   |            | [C35541E56B](<Notebook/Lenovo/ThinkPad/ThinkPad T480 20L5S1S000/9025AC5E126D/DEBIAN-12/6.1.0-28-AMD64/X86_64/C35541E56B>) |
| 8086:a121 | 1849:a121 | Intel            | 100 Series/C230 Series Chipset Fa... | 354   |            | [D9985EBE4E](<Desktop/ASRock/H110/H110M-ITX/F42E4DEE3FF9/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/D9985EBE4E>) |
| 8086:4def |           | Intel            | Jasper Lake Shared SRAM              | 342   |            | [8D772F9E5A](<Notebook/UNOWHY/Y13/Y13G113S4EI/23A28EB0728F/DEBIAN-12/6.1.0-28-AMD64/X86_64/8D772F9E5A>) |
| 8086:9d21 | 8086:9d21 | Intel            | Sunrise Point-LP PMC                 | 342   | intel_p... | [165F302BE9](<Notebook/Google/Chell/Chell/D809DC2934A8/DEBIAN/6.12.6-AMD64/X86_64/165F302BE9>) |
| 8086:a2a1 | 1043:872f | Intel            | 200 Series/Z370 Chipset Family Po... | 333   |            | [026EE0FACD](<Desktop/ASUSTek Computer/Maximus/Maximus IX CODE/5FE64CFA3244/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/026EE0FACD>) |
| 8086:7a27 | 1043:8882 | Intel            | Raptor Lake-S PCH Shared SRAM        | 331   |            | [826DC3E0F2](<Desktop/iBUYPOWER/Intel/Intel Core i7-14700F/0C1A211F1578/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/826DC3E0F2>) |
| 8086:9d21 | 103c:8079 | Intel            | Sunrise Point-LP PMC                 | 309   |            | [DA5C26013C](<Notebook/Hewlett-Packard/ZBook/ZBook 15u G3/5C8D48F3C0A5/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/DA5C26013C>) |
| 10de:03f5 | 1458:0c11 | Nvidia           | MCP61 Memory Controller              | 303   |            | [4040206002](<Desktop/Gigabyte Technology/M68/M68MT-S2/8DE8D73FA1FF/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/4040206002>) |
| 8086:4def | 8086:7270 | Intel            | Jasper Lake Shared SRAM              | 296   | vfio_pci   | [BC8E7EDAC4](<Notebook/Google/Cret/Cret/3C9CF67F812D/KUBUNTU-24.10/6.11.0-13-GENERIC/X86_64/BC8E7EDAC4>) |
| 8086:9def | 17aa:2279 | Intel            | Cannon Point-LP Shared SRAM          | 291   |            | [B9E31A2832](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N3S82N1P/72B74810F0E9/ARCH-ROLLING/6.12.8-ARCH1-1/X86_64/B9E31A2832>) |
| 8086:a36f |           | Intel            | Cannon Lake PCH Shared SRAM          | 284   |            | [BA278C0390](<Notebook/Apple/MacBookPro16/MacBookPro16,1/08604154B492/ALT-11.0/6.6.69-6.6-ALT1/X86_64/BA278C0390>) |
| 10de:0d68 |           | Nvidia           | MCP89 Memory Controller              | 278   |            | [7961299452](<Notebook/Apple/MacBookPro7/MacBookPro7,1/55DEE2A47303/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/7961299452>) |
| 10de:0d69 |           | Nvidia           | MCP89 Memory Controller              | 278   |            | [7961299452](<Notebook/Apple/MacBookPro7/MacBookPro7,1/55DEE2A47303/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/7961299452>) |
| 10de:0d6d |           | Nvidia           | MCP89 Memory Controller              | 278   |            | [7961299452](<Notebook/Apple/MacBookPro7/MacBookPro7,1/55DEE2A47303/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/7961299452>) |
| 10de:0d6e |           | Nvidia           | MCP89 Memory Controller              | 278   |            | [7961299452](<Notebook/Apple/MacBookPro7/MacBookPro7,1/55DEE2A47303/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/7961299452>) |
| 10de:0d6f |           | Nvidia           | MCP89 Memory Controller              | 278   |            | [7961299452](<Notebook/Apple/MacBookPro7/MacBookPro7,1/55DEE2A47303/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/7961299452>) |
| 10de:0d70 |           | Nvidia           | MCP89 Memory Controller              | 278   |            | [7961299452](<Notebook/Apple/MacBookPro7/MacBookPro7,1/55DEE2A47303/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/7961299452>) |
| 10de:0d71 |           | Nvidia           | MCP89 Memory Controller              | 278   |            | [7961299452](<Notebook/Apple/MacBookPro7/MacBookPro7,1/55DEE2A47303/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/7961299452>) |
| 10de:0d72 |           | Nvidia           | MCP89 Memory Controller              | 278   |            | [7961299452](<Notebook/Apple/MacBookPro7/MacBookPro7,1/55DEE2A47303/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/7961299452>) |
| 10de:0d75 |           | Nvidia           | MCP89 Memory Controller              | 278   |            | [7961299452](<Notebook/Apple/MacBookPro7/MacBookPro7,1/55DEE2A47303/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/7961299452>) |
| 10de:0d7b |           | Nvidia           | MCP89 Memory Controller              | 278   |            | [7961299452](<Notebook/Apple/MacBookPro7/MacBookPro7,1/55DEE2A47303/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/7961299452>) |
| 8086:54ef | 8086:7270 | Intel            | Alder Lake-N PCH Shared SRAM         | 278   |            | [FA69A9BFBC](<Desktop/Others/Others/Others/7F97178EED74/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/FA69A9BFBC>) |
| 8086:9def | 103c:8549 | Intel            | Cannon Point-LP Shared SRAM          | 262   |            | [6781E260B0](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G6/6565E10C0338/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/6781E260B0>) |

### Modem (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:266d | 14f1:5423 | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 39    | snd_int... | [270C26C018](<Notebook/Dell/Latitude/Latitude D610/0EFB96F39054/VOID-ROLLING/6.3.12_1/I686/270C26C018>) |
| 1057:3052 | 1057:3020 | Motorola         | SM56 Data Fax Modem                  | 37    |            | [8FB15C7579](<Desktop/Acer/Aspire/Aspire T180/C555F4C87777/DEBIAN-12/6.1.0-22-AMD64/X86_64/8FB15C7579>) |
| 8086:266d | 1179:0001 | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 28    | snd_int... | [64195764A9](<Notebook/Toshiba/Satellite/Satellite M40X/41415AE422D0/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.10.3-1-DEFAULT/I686/64195764A9>) |
| 1106:3068 |           | VIA Technologies | AC'97 Modem Controller               | 21    | snd_via... | [64054E7BF3](<Desktop/ASUSTek Computer/K8/K8V-MX/6253586A8539/OPENMANDRIVA-23.08/6.4.11-DESKTOP-1OMV2390/X86_64/64054E7BF3>) |
| 11c1:044c | 11c1:044c | LSI              | LT WinModem                          | 19    |            | [5C9A33D3EF](<Desktop/ECS/RS480/RS480-M/8E7D20B200CF/LUBUNTU-24.04/6.8.0-1016-OEM/X86_64/5C9A33D3EF>) |
| 1039:7013 | 1025:0083 | Silicon Integ... | AC'97 Modem Controller               | 17    | snd_int... | [1D2FAD06C8](<Notebook/Acer/Aspire/Aspire 3000/7C6B897C57EF/LUBUNTU-18.04/4.15.0-213-GENERIC/I686/1D2FAD06C8>) |
| 8086:266d | 103c:099c | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 17    | snd_int... | [0E4AB723D6](<Notebook/Hewlett-Packard/Compaq/Compaq nx6120/E5900DD3AADB/UBUNTU-18.04/4.15.0-213-GENERIC/I686/0E4AB723D6>) |
| 8086:24c6 | 14f1:5422 | Intel            | 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4... | 16    | snd_int... | [5BE797C401](<Notebook/Dell/Inspiron/Inspiron 510m/75AA7CCDF8DB/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.11.5-1-DEFAULT/I686/5BE797C401>) |
| 8086:266d | 1025:006a | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 16    | snd_int... | [EFF3C1A864](<Notebook/Acer/Aspire/Aspire 3610/1FA3E38CA2E4/ROSA-12.5.1/5.15.127-GENERIC-1ROSA2021.1-I686/I686/EFF3C1A864>) |
| 1002:4378 | 103c:3091 | AMD              | IXP SB400 AC'97 Modem Controller     | 12    | snd_ati... | [AF3A09EA38](<Notebook/Hewlett-Packard/Presario/Presario V2000/E4E154279E6B/DEBIAN-11/5.10.0-28-686-PAE/I686/AF3A09EA38>) |
| 1039:7013 | 1043:1816 | Silicon Integ... | AC'97 Modem Controller               | 12    | snd_int... | [3E313BB71A](<Notebook/ASUSTek Computer/A/A9T/10FAFD506F05/UBUNTU-18.04/4.15.0-202-GENERIC/I686/3E313BB71A>) |
| 8086:266d | 1014:0574 | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 12    | snd_int... | [AF59841E31](<Notebook/IBM/ThinkPad/ThinkPad T43 2668F5G/374CCA0C080D/XUBUNTU-18.04/5.4.0-110-GENERIC/I686/AF59841E31>) |
| 8086:266d | 1014:0576 | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 12    | snd_int... | [879C92E2CB](<Notebook/IBM/ThinkPad/ThinkPad T43 2668BU7/EA920109D1B4/DEBIAN-12/6.1.0-23-686-PAE/I686/879C92E2CB>) |
| 8086:24c6 | 1014:0524 | Intel            | 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4... | 11    | snd_int... | [3E03052246](<Notebook/IBM/ThinkPad/ThinkPad T41 23737JU/A85732887FB9/GENTOO-2.14/6.6.21-GENTOO-DIST/I686/3E03052246>) |
| 1002:4378 | 103c:3085 | AMD              | IXP SB400 AC'97 Modem Controller     | 10    | snd_ati... | [C6FCC7764F](<Notebook/Hewlett-Packard/Pavilion/Pavilion ZV6100/E2253C9A9EFB/LINUXMINT-20.2/5.4.0-132-GENERIC/X86_64/C6FCC7764F>) |
| 1002:4378 | 103c:30a4 | AMD              | IXP SB400 AC'97 Modem Controller     | 9     | snd_ati... | [B269162F6F](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv5000/B693CB6148EA/KALI-2021.3/5.14.0-KALI2-AMD64/X86_64/B269162F6F>) |
| 8086:24c6 | 1014:0559 | Intel            | 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4... | 9     | snd_int... | [32A349AB97](<Notebook/IBM/ThinkPad/ThinkPad R50e 1842QDU/8FE008B3F07A/DEBIAN-12/6.1.0-15-686-PAE/I686/32A349AB97>) |
| 8086:24c6 | 1014:055a | Intel            | 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4... | 9     | snd_int... | [79787555B2](<Notebook/IBM/ThinkPad/ThinkPad T42 2373CS8/969DF64E002B/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.6.2-1-DEFAULT/I686/79787555B2>) |
| 8086:24c6 | 14e4:4d64 | Intel            | 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4... | 9     | snd_int... | [F83D4681A5](<Notebook/Dell/Inspiron/Inspiron 5100/C91BBC192D39/DEBIAN-11/5.10.0-13-686-PAE/I686/F83D4681A5>) |
| 8086:266d | 103c:0944 | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 8     | snd_int... | [7F042FAA64](<Notebook/Hewlett-Packard/Compaq/Compaq nc6220/1E605B144200/UBUNTU-UNITY-16.04/4.15.0-45-GENERIC/I686/7F042FAA64>) |
| 8086:266d | 103c:3082 | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 8     |            | [423DEE7CE8](<Notebook/Hewlett-Packard/Compaq/Compaq nx9600/139F12D874E7/XUBUNTU-18.04/5.4.0-150-GENERIC/I686/423DEE7CE8>) |
| 1002:4378 | 103c:309b | AMD              | IXP SB400 AC'97 Modem Controller     | 7     | snd_ati... | [B743CE445F](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv8000/15770A50D430/LINUXMINT-21/5.15.0-89-GENERIC/X86_64/B743CE445F>) |
| 8086:1040 | 8086:1000 | Intel            | 536EP Data Fax Modem                 | 7     |            | [0DAAE7DCB4](<Desktop/Gigabyte Technology/GA-990/GA-990FXA-UD3/F46DFB4BD862/LINUXMINT-21.2/5.15.0-79-GENERIC/X86_64/0DAAE7DCB4>) |
| 8086:266d | 1025:0066 | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 7     | snd_int... | [10A0D7E3A2](<Notebook/Acer/Aspire/Aspire 1650/16CD0687C8D0/XUBUNTU-16.04/4.4.0-186-LOWLATENCY/I686/10A0D7E3A2>) |
| 1002:4378 | 103c:308b | AMD              | IXP SB400 AC'97 Modem Controller     | 5     | snd_ati... | [BBA6B8D33D](<Notebook/Hewlett-Packard/Compaq/Compaq nx6125/2785164F5E40/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/BBA6B8D33D>) |
| 8086:24c6 | 1043:1826 | Intel            | 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4... | 5     | snd_int... | [E4C4A500B8](<Notebook/ASUSTek Computer/S3/S3N/8679CB23CA24/ANTIX-22/4.9.0-326-ANTIX.1-486-SMP/I686/E4C4A500B8>) |
| 8086:266d | 103c:0934 | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 5     |            | [60C7204131](<Notebook/Hewlett-Packard/Compaq/Compaq nx8220/79FBFFF388C7/ZORIN-15/5.4.0-84-GENERIC/I686/60C7204131>) |
| 8086:266d | 103c:30c4 | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 5     | snd_int... | [94571F879E](<Notebook/Hewlett-Packard/510/510 Notebook PC/0574C0166714/LILIDOG-23/6.1.0-18-686-PAE/I686/94571F879E>) |
| 1002:434d | 144d:2115 | AMD              | SB200 AC97 Modem Controller          | 4     | snd_ati... | [15D449DA5D](<Notebook/Samsung Electronics/P29/P29-28-26/D1D65BE24E49/ROSA-12.4/5.15.103-GENERIC-1ROSA2021.1-I686/I686/15D449DA5D>) |
| 1002:4378 | 1043:1186 | AMD              | IXP SB400 AC'97 Modem Controller     | 4     | snd_ati... | [E298B642F1](<Notebook/ASUSTek Computer/A6/A6R/607DA210CA9A/LUBUNTU-18.04/5.3.0-46-GENERIC/I686/E298B642F1>) |
| 1002:4378 | 1734:1092 | AMD              | IXP SB400 AC'97 Modem Controller     | 4     | snd_ati... | [EC61A60044](<Notebook/Fujitsu Siemens/AMILO/AMILO A1650G/0CFC24E3B4B9/MX-21/5.10.0-20-AMD64/X86_64/EC61A60044>) |
| 1039:7013 | 1025:0082 | Silicon Integ... | AC'97 Modem Controller               | 4     |            | [22D43C833D](<Notebook/Acer/Aspire/Aspire 3630/6310FC44A3FD/UBUNTU-18.04/4.15.0-213-GENERIC/I686/22D43C833D>) |
| 1039:7013 | 104d:814e | Silicon Integ... | AC'97 Modem Controller               | 4     | snd_int... | [0A7C76DA78](<Notebook/Sony/PCG-GRT/PCG-GRT230/5016654AC711/GENTOO-2.9/5.15.74-GENTOO-X86/I686/0A7C76DA78>) |
| 1106:3068 | 1019:0c04 | VIA Technologies | AC'97 Modem Controller               | 4     | snd_via... | [CAAB4A3B82](<Desktop/ECS/P4/P4M800-M/16B269C3988B/ZORIN-15/5.0.0-37-GENERIC/I686/CAAB4A3B82>) |
| 1106:3068 | 1734:109b | VIA Technologies | AC'97 Modem Controller               | 4     | snd_via... | [BC3DC03AB8](<Notebook/Fujitsu Siemens/AMILO/AMILO Pro V2030/51F7C82EC42E/LINUXMINT-19.3/5.0.0-32-GENERIC/I686/BC3DC03AB8>) |
| 134d:7892 | 134d:0001 | PCTel            | HSP MicroModem 56                    | 4     | serial     | [6C9B4F5E0B](<Desktop/ASUSTek Computer/M4/M4A78LT-M-LE/D489B8FA6164/LINUXMINT-19.1/4.15.0-55-GENERIC/I686/6C9B4F5E0B>) |
| 1543:3052 | 1543:3000 | SILICON Labor... | Intel 537 [Winmodem]                 | 4     |            | [B6ADDF8D7B](<Desktop/Intel/DG31PR/DG31PR AAE39516-304/12C2AC77223D/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/B6ADDF8D7B>) |
| 2003:8800 | 16ef:2800 | Smart Link       | LM-I56N                              | 4     | 8250_pci   | [A0E36B103B](<Desktop/ASUSTek Computer/H61/H61M-C/9EE35ABFAE35/OPENMANDRIVA-23.08/6.4.11-DESKTOP-1OMV2390/X86_64/A0E36B103B>) |
| 8086:24c6 | 1014:0525 | Intel            | 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4... | 4     | snd_int... | [F9C1EE57FA](<Notebook/IBM/ThinkPad/ThinkPad T40p 2373CG6/D514C3EA8220/ZORIN-15/5.4.0-150-GENERIC/I686/F9C1EE57FA>) |
| 8086:24c6 | 1179:0001 | Intel            | 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4... | 4     | snd_int... | [E11F5448D4](<Notebook/Toshiba/TECRA/TECRA A2/BA6825D730AD/DEBIAN-12/6.9.7+BPO-686-PAE/I686/E11F5448D4>) |
| 8086:266d | 103c:309d | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 4     | snd_int... | [F462D80B2A](<Notebook/Hewlett-Packard/Presario/Presario V4000/8D2374099587/ALPINE-3.17_ALPHA20220809/5.15.59-0-LTS/I686/F462D80B2A>) |
| 8086:266d | 1179:ff31 | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 4     | snd_int... | [875478A51A](<Notebook/Toshiba/Satellite/Satellite L20/7E44156CDD20/ROSA-2016.1/5.4.83-GENERIC-2ROSA-I586/I686/875478A51A>) |
| 8086:266d | 144d:2115 | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 4     | snd_int... | [D7EE30EC16](<Notebook/Samsung Electronics/SX20/SX20S/CC589C886A23/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-I586/I686/D7EE30EC16>) |
| 1002:4378 | 1025:007e | AMD              | IXP SB400 AC'97 Modem Controller     | 3     | snd_ati... | [60873D0A0E](<Notebook/Acer/Ferrari/Ferrari 4000/C3757E42E4DF/XUBUNTU-20.04/5.4.0-66-GENERIC/X86_64/60873D0A0E>) |
| 1002:4378 | 1025:0080 | AMD              | IXP SB400 AC'97 Modem Controller     | 3     | snd_ati... | [8B304AF834](<Notebook/Acer/TravelMate/TravelMate 4400/37CF67CDFEA7/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/8B304AF834>) |
| 1039:7013 | 1584:4003 | Silicon Integ... | AC'97 Modem Controller               | 3     | snd_int... | [E9BC9B3C8A](<Desktop/Uniwill/255KI-259KI/255KI-259KI Series/EEB62031AFFE/UBUNTU-UNITY-18.04/4.15.0-136-GENERIC/I686/E9BC9B3C8A>) |
| 1039:7013 | 1734:106c | Silicon Integ... | AC'97 Modem Controller               | 3     |            | [82B3B117C2](<Notebook/Fujitsu Siemens/AMILO/AMILO A7645/F43D07DB773C/LUBUNTU-18.04/4.15.0-213-GENERIC/X86_64/82B3B117C2>) |
| 10b9:5457 | 104d:8158 | ULi Electronics  | M5457 AC'97 Modem Controller         | 3     |            | [7E4F74E16A](<Notebook/Sony/PCG-FRV/PCG-FRV27/10A6C3FF3280/FEDORA-28/5.0.16-100.FC28.I686/I686/7E4F74E16A>) |
| 10b9:5457 | 1071:8351 | ULi Electronics  | M5457 AC'97 Modem Controller         | 3     |            | [300A622D96](<Notebook/Notebook/MAM/MAM2120/72A8B7BAE733/DEBIAN-11/5.10.0-20-AMD64/X86_64/300A622D96>) |
| 10de:00d9 | 103c:006d | Nvidia           | nForce3 Audio                        | 3     |            | [564B583FED](<Notebook/Hewlett-Packard/Presario/Presario R3200/D9B4B9C98737/UBUNTU-20.10/5.8.0-31-GENERIC/X86_64/564B583FED>) |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15e2 | 1022:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2509  | snd_pci... | [84DECD497D](<Desktop/BESSTAR Tech/HM/HM80/641CA314EE82/NOBARA-39/6.8.12-200.FSYNC.FC39.X86_64/X86_64/84DECD497D>) |
| 1022:15e2 | 1e44:1776 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1747  | snd_pci... | [DFF6A36E92](<Notebook/Valve/Galileo/Galileo/3D6CF2B6536D/STEAMOS-3.6.20/6.5.0-VALVE22-1-NEPTUNE-65-G9A338ED8A75E/X86_64/DFF6A36E92>) |
| 14e4:1570 | 14e4:1570 | Broadcom         | 720p FaceTime HD Camera              | 1630  | facetimehd | [DFB4117F5C](<Notebook/Apple/MacBookAir6/MacBookAir6,2/BBD1819D044E/FEDORA-41/6.8.5-301.FC40.X86_64/X86_64/DFB4117F5C>) |
| 8086:22b8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 886   | intel_a... | [496C93250D](<Tablet/Chuwi/Hi10/Hi10 pro tablet/D5A4927F3C98/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/496C93250D>) |
| 8086:1919 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 457   | ipu3_imgu  | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:9d32 | 8086:7270 | Intel            | CSI-2 Host Controller                | 439   | ipu3_cio2  | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 1022:15e2 | 17aa:3829 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 270   | snd_pci... | [E428436322](<Notebook/Lenovo/IdeaPad/IdeaPad 3 15ALC6 82KU/EAE67903063F/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/E428436322>) |
| 1022:15e2 | 17aa:382c | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 228   | snd_pci... | [E544B8E949](<Notebook/Lenovo/Legion/Legion 5 15ACH6H 82JU/6D4B0B0F9308/ARCO-ROLLING/6.12.6-ARCH1-1/X86_64/E544B8E949>) |
| 8086:5a88 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 225   |            | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 1022:15e2 | 17aa:3807 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 219   | snd_pci... | [C5C9A457AA](<Notebook/Lenovo/V15-ADA/V15-ADA 82C7/DF20D99E1E88/DEBIAN-12/6.1.0-28-AMD64/X86_64/C5C9A457AA>) |
| 1022:15e2 | 17aa:5081 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 212   | snd_pci... | [7BFAD25E97](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 1 20UES5NA00/65C9066BF452/FEDORA-40/6.8.5-301.FC40.X86_64/X86_64/7BFAD25E97>) |
| 1022:15e2 | 103c:887a | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 190   | snd_rn_... | [37B47880BB](<Notebook/Hewlett-Packard/Laptop/Laptop 15s-eq2xxx/911EAE7EAD9B/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/37B47880BB>) |
| 1022:15e2 | 17aa:5097 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 186   | snd_pci... | [46361A1B83](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20Y70038US/1722BB93FF17/ARCH-ROLLING/6.12.7-ARCH1-1/X86_64/46361A1B83>) |
| 1022:15e2 | 19e5:3e19 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 161   | snd_pci... | [287C370D01](<Notebook/HUAWEI/NBLK-WAX9/NBLK-WAX9X/20B1F2B5A2F3/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/287C370D01>) |
| 1022:15e2 | 17aa:3812 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 154   | snd_pci... | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 1022:15e2 | 1e21:1043 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 143   | snd_pci... | [C80C3ADBE0](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Gaming A15 FA506IU_FA506IU/0954DC4AE0D5/FEDORA-40/6.9.6-200.FC40.X86_64/X86_64/C80C3ADBE0>) |
| 1022:15e2 | 1025:1455 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 139   | snd_pci... | [5D0C074A0F](<Notebook/Acer/Nitro/Nitro AN515-44/FCBB9CDE2DD2/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/5D0C074A0F>) |
| 1022:15e2 | 17aa:507f | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 132   | snd_pci... | [F6852CBDBB](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 2 20T6002LUS/C5DF2A83869A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/F6852CBDBB>) |
| 1022:15e2 | 152d:1365 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 129   | snd_pci... | [030B263131](<Notebook/HUAWEI/BOM-WXX/BOM-WXX9/D1030F56CEDE/UBUNTU-22.04/5.15.0-25-GENERIC/X86_64/030B263131>) |
| 1022:15e2 | 17aa:381b | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 129   | snd_pci... | [D502F19368](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5 14ARE05 81X2/34FBC94B9A9A/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/D502F19368>) |
| 1022:15e2 | 17aa:3838 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 129   | snd_pci... | [271C85B332](<Notebook/Lenovo/IdeaPad/IdeaPad Gaming 3 15ACH6 82K2/139E64F0F5B5/STEAMOS-3.6.20/6.5.0-VALVE22-1-NEPTUNE-65-G9A338ED8A75E/X86_64/271C85B332>) |
| 1022:15e2 | 1025:134d | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 120   | snd_pci... | [734FD13848](<Notebook/Acer/Aspire/Aspire A315-42/3035086EFC0B/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/734FD13848>) |
| 1022:15e2 | 1043:1f11 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 119   | snd_pci... | [47B95E50DC](<Notebook/ASUSTek Computer/ROG/ROG Zephyrus G14 GA401QM_GA401QM/278113D373AB/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/47B95E50DC>) |
| 1022:15e2 | 17aa:3821 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 119   | snd_pci... | [0FCBBF148B](<Notebook/Lenovo/IdeaPad/IdeaPad 5 15ARE05 81YQ/D925A5940B1E/DEBIAN-12/6.1.0-23-AMD64/X86_64/0FCBBF148B>) |
| 1022:15e2 | 1d05:109f | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 118   | snd_pci... | [D1FE4C6194](<Notebook/TUXEDO/Pulse/Pulse 14 Gen1/4BA1C6A378B0/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/D1FE4C6194>) |
| 1022:15e2 | 17aa:3813 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 116   | snd_pci... | [33DAD31E6E](<Notebook/Lenovo/IdeaPad/IdeaPad S340-15API 81NC/8942D56644CD/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/33DAD31E6E>) |
| 1022:15e2 | 17aa:5094 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 116   | snd_rn_... | [0BB2FA170C](<Notebook/Lenovo/ThinkPad/ThinkPad P14s Gen 2a 21A0005RUS/B39DC970E8A6/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/0BB2FA170C>) |
| 1022:15e2 | 103c:84ae | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 112   | snd_pci... | [DC26AE6F85](<Notebook/Hewlett-Packard/Laptop/Laptop 15-db0xxx/6098CDB2FF28/LIBERTYOS/5.6.15-ARCH1-1/X86_64/DC26AE6F85>) |
| 1022:15e2 | 17aa:507e | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 112   | snd_pci... | [031C8D3940](<Notebook/Lenovo/ThinkPad/ThinkPad L14 Gen 1 20U6001ABO/11626807B73D/ARCH-ROLLING/6.10.6-ARCH1-1/X86_64/031C8D3940>) |
| 1022:15e2 | 19e5:3e18 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 112   | snd_pci... | [3B12D86F3D](<Notebook/HUAWEI/BOHK-WAX9/BOHK-WAX9X/EB58F64E2F99/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/3B12D86F3D>) |
| 8086:9d32 |           | Intel            | CSI-2 Host Controller                | 108   | ipu3_cio2  | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 1022:15e2 | 17aa:380f | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 107   | snd_pci... | [F598642EE7](<Notebook/Lenovo/IdeaPad/IdeaPad Gaming 3 15ARH05 82EY/6FBB4CF9718F/ARCH-ROLLING/6.12.7-ZEN1-1-ZEN/X86_64/F598642EE7>) |
| 1022:15e2 | 1e83:3e30 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 107   | snd_pci... | [5B9314F900](<Notebook/HUAWEI/HVY-WXX/HVY-WXX9/5686157B09BB/ARTIX-ROLLING/6.12.4-ARTIX1-1/X86_64/5B9314F900>) |
| 1022:15e2 | 17aa:5124 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 106   | snd_pci... | [690A841928](<Notebook/Lenovo/ThinkPad/ThinkPad E495 20NE0002US/CFA9E0B66F24/LMDE-6/6.1.0-28-AMD64/X86_64/690A841928>) |
| 1022:15e2 | 103c:876e | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 101   | snd_pci... | [36C7B8CBCF](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 13-ay0xxx/AD61E4338E34/KDE-NEON-24.04/6.8.0-48-GENERIC/X86_64/36C7B8CBCF>) |
| 1022:15e2 | 1e83:3e33 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 99    | snd_pci... | [50D20229D8](<Notebook/HUAWEI/KLVL-WXX/KLVL-WXX9/75C49E26FFD1/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/50D20229D8>) |
| 1022:15e2 | 17aa:3814 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 98    | snd_pci... | [145938B91B](<Notebook/Lenovo/V155-15API/V155-15API 81V5/8FC22A51E748/UBUNTU-23.10/6.5.0-9-GENERIC/X86_64/145938B91B>) |
| 1022:15e2 | 17aa:381c | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 95    | snd_pci... | [572F922D7C](<Notebook/Lenovo/Legion/Legion 5 15ARH05 82B5/5A86BFCF6422/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/572F922D7C>) |
| 1022:15e2 | f111:0006 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 95    | snd_pci_ps | [041F977A25](<Notebook/Framework/Laptop/Laptop 13/621585FACCFA/NIXOS-25.05/6.6.67-HARDENED1/X86_64/041F977A25>) |
| 1022:15e2 | 103c:8895 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 94    | snd_pci... | [1D6BF9301C](<Notebook/Hewlett-Packard/EliteBook/EliteBook 855 G8 Notebook PC/6BD4A3CD146F/FEDORA-41/6.12.5-200.FC41.X86_64/X86_64/1D6BF9301C>) |
| 1022:15e2 | 103c:8730 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 92    | snd_pci... | [30F8996B5F](<Notebook/Hewlett-Packard/ProBook/ProBook 445 G7/EFABE841E44E/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/30F8996B5F>) |
| 1022:15e2 | 17aa:3830 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 90    | snd_pci... | [678BAC446F](<Notebook/Lenovo/ThinkBook/ThinkBook 15 G3 ACL 21A4/B19C67654C78/FEDORA-41/6.12.5-200.FC41.X86_64/X86_64/678BAC446F>) |
| 1022:15e2 | 1025:152b | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 88    | snd_pci... | [1A20EF9A3C](<Notebook/Acer/Aspire/Aspire A515-45/2FAB158946A7/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/1A20EF9A3C>) |
| 1022:15e2 | 17aa:3828 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 87    | snd_pci... | [25AF48DDF7](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5 14ALC05 82HU/F3B4772C45D9/FEDORA-40/6.8.5-301.FC40.X86_64/X86_64/25AF48DDF7>) |
| 8086:8a19 | 8086:7270 | Intel            | Image Signal Processor               | 87    |            | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 1022:15e2 | 103c:85ea | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 85    | snd_pci... | [7BC8AEBA55](<Notebook/Hewlett-Packard/Laptop/Laptop 15-db1xxx/293499430D89/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/7BC8AEBA55>) |
| 1022:15e2 | 1043:1dcf | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 85    | snd_pci... | [832D6F219E](<Notebook/ASUSTek Computer/Vivobook/Vivobook Go E1504FA_E1504FA/0D7BA2DDE23F/ARCH-ROLLING/6.11.10-X64V3-XANMOD1/X86_64/832D6F219E>) |
| 1022:15e2 | 103c:8760 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 81    | snd_pci... | [33A984A2DF](<Notebook/Hewlett-Packard/EliteBook/EliteBook 845 G7 Notebook PC/FB463BF8E012/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/33A984A2DF>) |
| 1022:15e2 | 17aa:3823 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 81    | snd_pci... | [C5DF6B1606](<Notebook/Lenovo/Legion/Legion 5 15ARH05H 82B1/D1DBBE8F62C6/UBUNTU-24.10/6.11.0-13-GENERIC/X86_64/C5DF6B1606>) |
| 1022:15e2 | 17aa:50b1 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 81    | snd_pci... | [1A707FD487](<Notebook/Lenovo/ThinkPad/ThinkPad E15 Gen 4 21ED004NGE/324F305C5ADE/MANJARO/6.11.11-1-MANJARO/X86_64/1A707FD487>) |

### Multiport serial controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1fd4:1999 | 1fd4:0002 | SUNIX            | Multiport serial controller          | 9     | serial     | [5F788A9DF0](<Desktop/Gigabyte Technology/H61/H61M-S2PV/C4CEF8A66CB5/UBUNTU-20.04/5.15.0-48-GENERIC/X86_64/5F788A9DF0>) |
| 1fff:8018 |           | MCST             | I2C SPI                              | 5     | 8250_pci   | [68755125F3](<Desktop/Others/Others/Others/72BC38F883EE/ROSA-12.4/5.4.193-GENERIC-4ROSA2021.1-E2KV4/E2K/68755125F3>) |
| 135a:08c1 | 135a:0413 | Brain Boxes      | UC-310 2 port RS-422/485 Opto Iso... | 1     |            | [0F6EBD3E93](<Desktop/ASRock/G31/G31M-GS/0169A977538A/LINUXMINT-19.3/5.0.0-32-GENERIC/X86_64/0F6EBD3E93>) |
| 135c:0170 | 135c:0170 | Quatech          | QSCLP-100                            | 1     | serial     | [05DF269988](<Desktop/Hewlett-Packard/Evo/Evo D530/4AA9ADFB04B0/ROSA-2014.1/4.1.34-NRJ-DESKTOP-2ROSA-I586/I686/05DF269988>) |
| 1fff:8028 |           | MCST             | I2C SPI Crystall                     | 1     | 8250_pci   | [5AD56CAB50](<Desktop/Others/Others/Others/FC75BEA27F4E/ALT-P10/5.4.193-MCST-E16C-ALT5.9.4/E2K/5AD56CAB50>) |
| 8086:0002 |           | Intel            | Multiport serial controller          | 1     | i2c_spi    | [72915FD0DD](<Desktop/Others/Others/Others/8EF5BEC3DFC3/ALT-10.2/5.4.163-ELBRUS-DEF-ALT2.23.5/E2K/72915FD0DD>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:8168 | 1458:e000 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 11423 | r8169      | [27053CA724](<Desktop/Gigabyte Technology/B85/B85M-D3H/C42183E26685/DEBIAN-12/6.1.0-28-AMD64/X86_64/27053CA724>) |
| 10ec:8168 | 1849:8168 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 5089  | r8169      | [8EDA0B8FBF](<Desktop/ASRock/970M/970M Pro3/7CFC618F7557/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/8EDA0B8FBF>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 4968  | r8169      | [537A11AE44](<Desktop/PELADN/WI/WI-6/A87F09289266/LMDE-6/6.1.0-28-AMD64/X86_64/537A11AE44>) |
| 10ec:8168 | 1043:8677 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 4691  | r8169      | [5FB39D6837](<Desktop/ASUSTek Computer/PRIME/PRIME H510M-K R2.0/DF149F43E30B/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/5FB39D6837>) |
| 10ec:8168 | 1043:200f | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 3043  | r8169      | [C587210FDB](<Notebook/ASUSTek Computer/Q550/Q550LF/D49F84D80E98/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/C587210FDB>) |
| 10ec:8168 | 1043:8505 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 2794  | r8169      | [02A12F94E1](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX V2/63B73941E98E/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/02A12F94E1>) |
| 10ec:8168 | 1043:8432 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 1995  | r8169      | [2B21C81822](<Desktop/ASUSTek Computer/P8Z68-V/P8Z68-V LX/4130A0D4D84A/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/2B21C81822>) |
| 10ec:8168 | 1043:208f | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 1741  | r8169      | [98506E2506](<Notebook/ASUSTek Computer/ROG/ROG Strix G712LV_G712LV/5B2C2374494E/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/98506E2506>) |
| 8086:15f3 | 1043:87d2 | Intel            | Ethernet Controller I225-V           | 1584  | igc        | [88B1C0C262](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING WIFI II/B8760FB55781/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/88B1C0C262>) |
| 8086:15b8 | 1043:8672 | Intel            | Ethernet Connection (2) I219-V       | 1562  | e1000e     | [10FD8EF9DD](<Desktop/ASUSTek Computer/TUF/TUF Z370-PLUS GAMING II/76981D36E1E4/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/10FD8EF9DD>) |
| 14e4:16b4 | 14e4:16b4 | Broadcom         | NetXtreme BCM57765 Gigabit Ethern... | 1367  | tg3        | [AE5A71DDE0](<Notebook/Apple/MacBookPro9/MacBookPro9,1/04AD065CAD6F/LINUXMINT-20.3/5.4.0-204-GENERIC/X86_64/AE5A71DDE0>) |
| 10ec:8168 | 1043:8554 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 1258  | r8169      | [0B29006A62](<Desktop/ASUSTek Computer/K30/K30BF_M32BF_A_F_K31BF_6/AF04F3B51155/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/0B29006A62>) |
| 10de:0ab0 | 10de:cb79 | Nvidia           | MCP79 Ethernet                       | 1058  | forcedeth  | [DE39DE3147](<Notebook/Apple/MacBookPro5/MacBookPro5,5/AE9A7F9028B1/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/DE39DE3147>) |
| 10ec:8136 | 10ec:0123 | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 984   | r8169      | [778B3689C2](<Desktop/MAXSUN/MS-A86FX/MS-A86FX FS M.3/D0EC83BEBF32/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/778B3689C2>) |
| 10ec:8139 | 10ec:8139 | Realtek Semic... | RTL-8100/8101L/8139 PCI Fast Ethe... | 928   | 8139too... | [7BEF4FBF53](<Desktop/MSI/MS/MS-7551/11F48F5F9B28/FEDORA-40/6.12.5-100.FC40.X86_64/X86_64/7BEF4FBF53>) |
| 10ec:8168 | 1043:83a3 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 902   | r8169      | [12D33EE44D](<Desktop/ASUSTek Computer/P7P55D/P7P55D DELUXE/A9FD80849547/LINUXMINT-22.1/6.8.0-49-GENERIC/X86_64/12D33EE44D>) |
| 14e4:1686 | 14e4:1686 | Broadcom         | NetXtreme BCM57766 Gigabit Ethern... | 898   | tg3        | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 10ec:8136 | 1043:200f | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 870   | r8169      | [FFFC36417C](<Notebook/ASUSTek Computer/X540/X540SA/AD7E2D21FE1A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/FFFC36417C>) |
| 10ec:8168 | 1043:859e | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 837   | r8169      | [BA47136806](<Desktop/ASUSTek Computer/All/All Series/651BB16BD9C9/UBUNTU-24.10/6.12.3-061203-GENERIC/X86_64/BA47136806>) |
| 10ec:8168 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 789   | r8169      | [EEEA3C518D](<Notebook/Positivo Bahia - VAIO/VJFE59/VJFE59F11X-B1011H/306F1CDE613A/DEBIAN-12/6.1.0-28-AMD64/X86_64/EEEA3C518D>) |
| 8086:15b8 | 1458:e000 | Intel            | Ethernet Connection (2) I219-V       | 705   | e1000e     | [AD40DB7F67](<Desktop/Gigabyte Technology/Z170X-Gaming/Z170X-Gaming 7/4DE1A28702A7/ZORIN-17/6.8.0-50-GENERIC/X86_64/AD40DB7F67>) |
| 8086:15f3 | 8086:0000 | Intel            | Ethernet Controller I225-V           | 695   | igc        | [B4C4D726E4](<Desktop/Others/HX/HX90/6CC015460597/UBUNTU-24.10/6.11.0-13-GENERIC/X86_64/B4C4D726E4>) |
| 8086:15a1 | 1043:85c4 | Intel            | Ethernet Connection (2) I218-V       | 673   | e1000e     | [CC569301FD](<Desktop/ASUSTek Computer/All/All Series/CB641D7A502D/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/CC569301FD>) |
| 10ec:8168 | 7470:3468 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 661   | r8169      | [248853B59C](<Desktop/ASUSTek Computer/TUF/TUF Gaming A620M-PLUS/AA5C795A4F42/LINUXMINT-21.3/5.15.0-130-GENERIC/X86_64/248853B59C>) |
| 14e4:16b5 | 1025:0647 | Broadcom         | NetLink BCM57785 Gigabit Ethernet... | 626   | tg3        | [1BE16A65FF](<Notebook/Acer/Aspire/Aspire E1-571/5E9809648D6E/ARCH-ROLLING/6.12.8-ARCH1-1/X86_64/1BE16A65FF>) |
| 10ec:8168 | 1043:87c3 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 565   | r8169      | [FE84B3D431](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/0FF6AE87406B/ORG.KDE.PLATFORM-5.15-21.08/6.12.1-ZEN1/X86_64/FE84B3D431>) |
| 8086:15b8 | 1849:15b8 | Intel            | Ethernet Connection (2) I219-V       | 563   | e1000e     | [D9985EBE4E](<Desktop/ASRock/H110/H110M-ITX/F42E4DEE3FF9/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/D9985EBE4E>) |
| 8086:15bc | 1043:8672 | Intel            | Ethernet Connection (7) I219-V       | 543   | e1000e     | [558ED56269](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-F GAMING/3CDF356CA9A8/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/558ED56269>) |
| 1969:1083 | 1458:e000 | Qualcomm Atheros | AR8151 v2.0 Gigabit Ethernet         | 521   | atl1c      | [CA83315819](<Desktop/Gigabyte Technology/H61/H61M-S2P-B3/3275C3CD0166/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/CA83315819>) |
| 8086:153a | 1028:05a4 | Intel            | Ethernet Connection I217-LM          | 520   | e1000e     | [F722EDF7A9](<Desktop/Dell/OptiPlex/OptiPlex 9020/DEAD93BBE620/LUBUNTU-22.04/6.8.0-50-GENERIC/X86_64/F722EDF7A9>) |
| 8086:156f | 17aa:2233 | Intel            | Ethernet Connection I219-LM          | 509   | e1000e     | [00BB35DD31](<Notebook/Lenovo/ThinkPad/ThinkPad T560 20FH001RUS/B528951A4C78/DEBIAN-12/6.1.0-28-AMD64/X86_64/00BB35DD31>) |
| 1969:1048 | 1043:8226 | Qualcomm Atheros | Attansic L1 Gigabit Ethernet         | 479   | atl1       | [35DD91FA94](<Desktop/ASUSTek Computer/M3/M3A/4C070E755C3C/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/35DD91FA94>) |
| 10ec:8168 | 1462:7c37 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 465   | r8169      | [364AB4800D](<Desktop/MSI/MS-7/MS-7C37/DB0B0F216E27/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/364AB4800D>) |
| 11ab:4364 | 1043:81f8 | Marvell Techn... | 88E8056 PCI-E Gigabit Ethernet Co... | 458   | sky2       | [1026F82971](<Desktop/ASUSTek Computer/P5B-E/P5B-E Plus/0571CE0D8632/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-X86_64/X86_64/1026F82971>) |
| 10ec:8169 | 10ec:8169 | Realtek Semic... | RTL8169 PCI Gigabit Ethernet Cont... | 453   | r8169      | [0705F8159C](<Desktop/ASUSTek Computer/M5A78L/M5A78L LE/2E9EE4E6A0D6/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/0705F8159C>) |
| 8086:155a | 17aa:2214 | Intel            | Ethernet Connection I218-LM          | 450   | e1000e     | [17AC336E9C](<Notebook/Lenovo/ThinkPad/ThinkPad T440s 20ARS46M00/DD9FCCD73F49/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/17AC336E9C>) |
| 11ab:436a | 11ab:00ba | Marvell Techn... | 88E8058 PCI-E Gigabit Ethernet Co... | 447   | sky2       | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 10ec:8168 | 1043:16d5 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 438   | r8169      | [FF1622416C](<Notebook/ASUSTek Computer/K50/K50IE/4E5D16650878/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/FF1622416C>) |
| 8086:15bc | 1458:e000 | Intel            | Ethernet Connection (7) I219-V       | 430   | e1000e     | [639EB0E4FC](<Desktop/Gigabyte Technology/H370M/H370M D3H GSM/D391F95DF729/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/639EB0E4FC>) |
| 8086:15a2 | 17aa:2226 | Intel            | Ethernet Connection (3) I218-LM      | 412   | e1000e     | [23C3A522F9](<Notebook/Lenovo/ThinkPad/ThinkPad X250 20CLS45J00/50C13FEE08DD/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/23C3A522F9>) |
| 10ec:8168 | 1462:7c02 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 403   | r8169      | [88D10A1126](<Desktop/MSI/MS-7/MS-7C02/DD7D36D47449/LMDE-6/6.1.0-28-AMD64/X86_64/88D10A1126>) |
| 14e4:1684 | 14e4:1684 | Broadcom         | NetXtreme BCM5764M Gigabit Ethern... | 387   | tg3        | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 14e4:16b5 | 1025:0504 | Broadcom         | NetLink BCM57785 Gigabit Ethernet... | 377   | tg3        | [68404201A9](<Notebook/Acer/Aspire/Aspire 5750G/8E9ECAF23BC7/ZORIN-17/6.8.0-50-GENERIC/X86_64/68404201A9>) |
| 10ec:8168 | 1043:205f | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 364   | r8169      | [208B3336EB](<Notebook/ASUSTek Computer/VivoBook/VivoBook E14 E402WAS/EB762741F005/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/208B3336EB>) |
| 1969:1083 | 1043:1851 | Qualcomm Atheros | AR8151 v2.0 Gigabit Ethernet         | 363   | atl1c      | [E777C929C0](<Notebook/ASUSTek Computer/U56/U56E/9D524C9E9755/DEBIAN-12/6.1.0-28-AMD64/X86_64/E777C929C0>) |
| 10ec:8168 | 1043:82c6 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 353   | r8169      | [2E5A12A36B](<Desktop/ASUSTek Computer/P5Q/P5Q SE PLUS/423D0CB53C57/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/2E5A12A36B>) |
| 10ec:8168 | 1462:7b86 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 351   | r8169      | [89CD372074](<Desktop/MSI/MS-7/MS-7B86/3FF968BBEDE3/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/89CD372074>) |
| 8086:153b | 1458:e000 | Intel            | Ethernet Connection I217-V           | 348   | e1000e     | [381B6FC010](<Desktop/Gigabyte Technology/Z97/Z97X-UD5H/5500A52DF6D9/ZORIN-17/6.8.0-50-GENERIC/X86_64/381B6FC010>) |
| 197b:0250 | 1043:1905 | JMicron Techn... | JMC250 PCI Express Gigabit Ethern... | 344   | jme        | [35095B2B4C](<Notebook/ASUSTek Computer/K42/K42JY/7D0DF9CB1CBF/DEBIAN-12/6.1.0-28-AMD64/X86_64/35095B2B4C>) |
| 10ec:8168 | 1462:7817 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 342   | r8169      | [CE0086EC71](<Desktop/MSI/MS/MS-7817/CD2BE804A24A/UBUNTU-24.10/6.11.0-13-GENERIC/X86_64/CE0086EC71>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2723 | 8086:0084 | Intel            | Wi-Fi 6 AX200                        | 7460  | iwlwifi    | [105D641565](<All In One/Acidanthera/iMac18/iMac18,1/244EC7A3F367/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/105D641565>) |
| 8086:a0f0 | 8086:0074 | Intel            | Wi-Fi 6 AX201                        | 3219  | iwlwifi    | [F10A2B06FD](<Notebook/HUAWEI/MACHD-WXX/MACHD-WXX9/FDA3F3F89271/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/F10A2B06FD>) |
| 8086:24fb | 8086:2110 | Intel            | Dual Band Wireless-AC 3168NGW [St... | 2923  | iwlwifi    | [FDA84AF6B6](<Desktop/MSI/MS-7/MS-7A40/DC07AAAD39A3/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/FDA84AF6B6>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 2676  | iwlwifi    | [83A930718F](<Notebook/Hewlett-Packard/Pavilion/Pavilion Power Laptop 15-cb0xx/FD49ADAE5091/ARCH-ROLLING/6.12.8-ARCH1-1/X86_64/83A930718F>) |
| 8086:2725 | 8086:0024 | Intel            | Wi-Fi 6E(802.11ax) AX210/AX1675* ... | 2467  | iwlwifi    | [2183EB76B7](<Tablet/ONE-NETBOOK/ONEXPLAYER/ONEXPLAYER Mini Pro/F55453A23AA1/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/2183EB76B7>) |
| 8086:24fd | 8086:0010 | Intel            | Wireless 8265 / 8275                 | 2296  | iwlwifi    | [F43357E57A](<Notebook/Lenovo/ThinkPad/ThinkPad P51 20HJS0D201/C052B2ADD09F/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/F43357E57A>) |
| 8086:a370 | 8086:0034 | Intel            | Cannon Lake PCH CNVi WiFi            | 2055  | iwlwifi    | [CC86C7E5C1](<Notebook/Hewlett-Packard/Pavilion/Pavilion Gaming Laptop 15-dk0xxx/B0063B9A6EDF/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/CC86C7E5C1>) |
| 8086:0085 | 8086:1311 | Intel            | Centrino Advanced-N 6205 [Taylor ... | 1999  | iwlwifi    | [20E239CB8A](<Notebook/Lenovo/ThinkPad/ThinkPad W530 2441AG6/157AE4F689F0/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/20E239CB8A>) |
| 10ec:c821 | 103c:831a | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 1964  | rtw88_8... | [0562D753F2](<Notebook/Hewlett-Packard/250/250 G7 Notebook PC/AA67D28E662F/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/0562D753F2>) |
| 8086:2526 | 8086:0014 | Intel            | Wi-Fi 5(802.11ac) Wireless-AC 9x6... | 1805  | iwlwifi    | [F10A0EDBDF](<Notebook/Lenovo/ThinkPad/ThinkPad 11e 5th Gen 20LRS02900/C75190EF9624/ARCH-ROLLING/6.12.8-ARCH1-1/X86_64/F10A0EDBDF>) |
| 168c:0042 | 11ad:08a6 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 1754  | ath10k_pci | [8A7B632B3F](<Notebook/Acer/Aspire/Aspire E5-575/2F74F452914E/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/8A7B632B3F>) |
| 8086:24fd | 8086:1010 | Intel            | Wireless 8265 / 8275                 | 1661  | iwlwifi    | [EC0EAF35EF](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G5/50A93566162E/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/EC0EAF35EF>) |
| 168c:0042 | 17aa:0901 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 1638  | ath10k_pci | [69908D16CA](<Notebook/Lenovo/ThinkPad/ThinkPad E475 20H40006US/ACBB63787D0E/DEBIAN-12/6.1.0-27-AMD64/X86_64/69908D16CA>) |
| 10ec:c822 | 1a3b:4210 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 1561  | rtw_8822ce | [586CABC574](<Notebook/Valve/Jupiter/Jupiter/917F916A860A/STEAMOS-3.6.20/6.5.0-VALVE22-1-NEPTUNE-65-G9A338ED8A75E/X86_64/586CABC574>) |
| 168c:002b | 1a3b:1089 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 1534  | ath9k      | [6D8DA5AC74](<Notebook/Dell/Precision/Precision M4400/CD6EFB755DAE/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/6D8DA5AC74>) |
| 8086:9df0 | 8086:0034 | Intel            | Cannon Point-LP CNVi [Wireless-AC]   | 1471  | iwlwifi    | [572616A1D9](<Notebook/Acer/Aspire/Aspire A515-52G/15F6846BC187/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/572616A1D9>) |
| 8086:3166 | 8086:4210 | Intel            | Dual Band Wireless-AC 3165 Plus B... | 1468  | iwlwifi    | [75606D7596](<Desktop/Lenovo/IdeaCentre/IdeaCentre 510S-08ISH 90FN00BAGE/B2C06C493079/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/75606D7596>) |
| 10ec:c822 | 103c:85f7 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 1450  | rtw88_8... | [963FCDD477](<Notebook/Hewlett-Packard/ProBook/ProBook 455 G8 Notebook PC/8B9D95062911/OPENMANDRIVA-24.07/6.9.7-DESKTOP-1OMV2490/X86_64/963FCDD477>) |
| 8086:3165 | 8086:4010 | Intel            | Wireless 3165                        | 1446  | iwlwifi    | [EB8CC11CC5](<Notebook/Hewlett-Packard/Pavilion/Pavilion Notebook/2654011C99FE/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/EB8CC11CC5>) |
| 8086:06f0 | 8086:0074 | Intel            | Comet Lake PCH CNVi WiFi             | 1337  | iwlwifi    | [98506E2506](<Notebook/ASUSTek Computer/ROG/ROG Strix G712LV_G712LV/5B2C2374494E/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/98506E2506>) |
| 168c:0042 | 1028:1810 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 1316  | ath10k_pci | [C661F75C0F](<Notebook/Dell/Inspiron/Inspiron 15-3567/2B3C08638F5D/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/C661F75C0F>) |
| 8086:02f0 | 8086:0074 | Intel            | Comet Lake PCH-LP CNVi WiFi          | 1313  | iwlwifi    | [F1B89F85CF](<Notebook/Hewlett-Packard/ProBook/ProBook 430 G7/CDF0295CF7D9/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/F1B89F85CF>) |
| 8086:2723 | 8086:0080 | Intel            | Wi-Fi 6 AX200                        | 1272  | iwlwifi    | [B0B56EC993](<Notebook/Lenovo/ThinkPad/ThinkPad L15 Gen 1 20U30035UK/AB423BC9175F/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/B0B56EC993>) |
| 14c3:7961 | 1a3b:4680 | MediaTek         | MT7921 802.11ax PCI Express Wirel... | 1139  | mt7921e    | [BBC74E0C64](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550M-PLUS WIFI II/417DA912186A/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/BBC74E0C64>) |
| 8086:24fd | 8086:0050 | Intel            | Wireless 8265 / 8275                 | 1125  | iwlwifi    | [D019C812B7](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/360F073CECA0/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/D019C812B7>) |
| 10ec:d723 | 103c:8319 | Realtek Semic... | RTL8723DE Wireless Network Adapter   | 1106  | rtw88_8... | [63A7238333](<Notebook/Hewlett-Packard/Laptop/Laptop 15-bw0xx/85728BFCAE03/LINUXMINT-22.1/6.8.0-51-GENERIC/X86_64/63A7238333>) |
| 8086:24f3 | 8086:0010 | Intel            | Wireless 8260                        | 1104  | iwlwifi    | [CF0A931BC4](<Tablet/Fujitsu/FARQ/FARQ16011/0AA1C154091E/ZORIN-17/6.8.0-50-GENERIC/X86_64/CF0A931BC4>) |
| 10ec:c822 | 17aa:c123 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 1080  | rtw88_8... | [04C0C560D4](<Desktop/Lenovo/IdeaCentre/IdeaCentre 5 14ARE05 90Q3004YMH/13F55D11E08F/UBUNTUSTUDIO-24.04/6.8.0-47-LOWLATENCY/X86_64/04C0C560D4>) |
| 8086:51f0 | 8086:0094 | Intel            | Alder Lake-P PCH CNVi WiFi           | 1057  | iwlwifi    | [331B79E990](<Convertible/Lenovo/Yoga/Yoga 9 14IAP7 82LU/B13215F8E1CA/ZORIN-17/6.8.0-50-GENERIC/X86_64/331B79E990>) |
| 1814:3290 | 103c:18ec | Ralink           | RT3290 Wireless 802.11n 1T/1R PCIe   | 989   | rt2800pci  | [E8728549F4](<Notebook/Hewlett-Packard/655/655/7C80AF022F04/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E8728549F4>) |
| 14c3:0608 | 14c3:0608 | MediaTek         | MT7921K (RZ608) Wi-Fi 6E 80MHz       | 988   | mt7921e    | [84DECD497D](<Desktop/BESSTAR Tech/HM/HM80/641CA314EE82/NOBARA-39/6.8.12-200.FSYNC.FC39.X86_64/X86_64/84DECD497D>) |
| 10ec:c821 | 10ec:c821 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 897   | rtw88_8... | [537A11AE44](<Desktop/PELADN/WI/WI-6/A87F09289266/LMDE-6/6.1.0-28-AMD64/X86_64/537A11AE44>) |
| 168c:0036 | 1028:020e | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 886   | ath9k      | [1F361B3518](<All In One/Dell/Inspiron/Inspiron 23 Model 5348/D34B13017CE6/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/1F361B3518>) |
| 10ec:b822 | 103c:831b | Realtek Semic... | RTL8822BE 802.11a/b/g/n/ac WiFi a... | 851   | rtw88_8... | [19193380D7](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15-ds0xxx/41FB038B6EDB/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/19193380D7>) |
| 8086:3165 | 8086:4410 | Intel            | Wireless 3165                        | 836   | iwlwifi    | [954D7D9768](<Desktop/Dell/OptiPlex/OptiPlex 3050/921BD90327E1/LINUXMINT-21.3/5.15.0-130-GENERIC/X86_64/954D7D9768>) |
| 168c:003e | 1a56:1535 | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 834   | ath10k_pci | [FC246315B0](<Notebook/Dell/XPS/XPS 13 9360/E2287EB6796E/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/FC246315B0>) |
| 8086:088e | 8086:4060 | Intel            | Centrino Advanced-N 6235             | 834   | iwlwifi    | [CBE6ED9631](<Notebook/Samsung Electronics/900X3/900X3C-900X4C-900X4D/F7E452426C39/ELEMENTARY-7.1/6.8.0-49-GENERIC/X86_64/CBE6ED9631>) |
| 168c:0036 | 1028:020c | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 808   | ath9k      | [206872A37F](<Notebook/Dell/Inspiron/Inspiron 3541/6C61E57816DF/UBUNTU-24.04/6.8.0-50-GENERIC/X86_64/206872A37F>) |
| 10ec:c822 | 1058:1e25 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 785   | rtw88_8... | [3B12D86F3D](<Notebook/HUAWEI/BOHK-WAX9/BOHK-WAX9X/EB58F64E2F99/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/3B12D86F3D>) |
| 14c3:7961 | 17aa:e0bc | MediaTek         | MT7921 802.11ax PCI Express Wirel... | 778   | mt7921e    | [928B89625A](<Notebook/Lenovo/ThinkPad/ThinkPad L15 Gen 2 20X4S4LM01/2F9E509B2799/DEBIAN-12/6.1.0-27-AMD64/X86_64/928B89625A>) |
| 8086:a0f0 | 8086:4070 | Intel            | Wi-Fi 6 AX201                        | 772   | iwlwifi    | [C7F4EADA6C](<Notebook/Dell/Latitude/Latitude 5320/AA520611DCFE/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/C7F4EADA6C>) |
| 14e4:43a0 | 106b:0117 | Broadcom Limited | BCM4360 802.11ac Dual Band Wirele... | 770   | wl         | [DFB4117F5C](<Notebook/Apple/MacBookAir6/MacBookAir6,2/BBD1819D044E/FEDORA-41/6.8.5-301.FC40.X86_64/X86_64/DFB4117F5C>) |
| 8086:08b2 | 8086:c270 | Intel            | Wireless 7260                        | 770   | iwlwifi    | [17AC336E9C](<Notebook/Lenovo/ThinkPad/ThinkPad T440s 20ARS46M00/DD9FCCD73F49/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/17AC336E9C>) |
| 8086:51f0 | 8086:0074 | Intel            | Alder Lake-P PCH CNVi WiFi           | 769   | iwlwifi    | [9A04090DED](<Notebook/MSI/Katana/Katana 17 B12UCR/B0AD73F94A60/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/9A04090DED>) |
| 8086:34f0 | 8086:0074 | Intel            | Ice Lake-LP PCH CNVi WiFi            | 762   | iwlwifi    | [88E5DA8B9D](<Notebook/Acer/Aspire/Aspire A514-53/AB357CF0BF61/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/88E5DA8B9D>) |
| 168c:003e | 1028:0310 | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 756   | ath10k_pci | [6FD5C30874](<Convertible/Dell/Latitude/Latitude 5310 2-in-1/C73804ACA57C/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/6FD5C30874>) |
| 168c:0036 | 11ad:0642 | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 751   | ath9k      | [DCA3176D13](<Notebook/Acer/Aspire/Aspire E5-572G/119C96C6F625/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/DCA3176D13>) |
| 10ec:c821 | 17aa:c024 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 743   | rtw88_8... | [7A8E2CD7ED](<Notebook/Lenovo/IdeaPad/IdeaPad 330-15ARR 81D2/DBC2B68A558A/ENDEAVOUROS-ROLLING/6.12.7-ARCH1-1/X86_64/7A8E2CD7ED>) |
| 8086:08b1 | 8086:4470 | Intel            | Wireless 7260                        | 736   | iwlwifi    | [1C0ABB00B2](<Notebook/Sony/VPCF236/VPCF236FM/E0F4C306B36B/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/1C0ABB00B2>) |
| 8086:3165 | 8086:8010 | Intel            | Wireless 3165                        | 734   | iwlwifi    | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1539 | 1043:85f0 | Intel            | I211 Gigabit Network Connection      | 2151  | igb        | [29A8B52EEC](<Desktop/ASUSTek Computer/ROG/ROG STRIX B450-F GAMING II/62CA3E70EFA5/CACHYOS/6.12.7-2-CACHYOS/X86_64/29A8B52EEC>) |
| 10ec:8125 | 1458:e000 | Realtek Semic... | RTL8125 2.5GbE Controller            | 1479  | r8169      | [0D0A62D437](<Desktop/Gigabyte Technology/B650M/B650M D3HP/09BE719645F6/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/0D0A62D437>) |
| 8086:1539 | 1458:e000 | Intel            | I211 Gigabit Network Connection      | 1418  | igb        | [D80A8FD406](<Desktop/Gigabyte Technology/X570/X570 AORUS ELITE WIFI/CC478A15F194/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/D80A8FD406>) |
| 10ec:8125 | 1043:87d7 | Realtek Semic... | RTL8125 2.5GbE Controller            | 1398  | r8169      | [7FEA0BB2A1](<Desktop/ASUSTek Computer/PRIME/PRIME B650M-A AX II/561F5C99198B/FEDORA-40/6.10.5-200.FC40.X86_64/X86_64/7FEA0BB2A1>) |
| 8086:1502 | 17aa:21f3 | Intel            | 82579LM Gigabit Network Connectio... | 1160  | e1000e     | [20E239CB8A](<Notebook/Lenovo/ThinkPad/ThinkPad W530 2441AG6/157AE4F689F0/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/20E239CB8A>) |
| 8086:1539 | 1849:1539 | Intel            | I211 Gigabit Network Connection      | 1037  | igb        | [2B29FC224E](<Desktop/ASRock/X570/X570 Steel Legend/21EE1EAB75AF/RHEL-9/5.14.0-427.22.1.EL9_4.X86_64/X86_64/2B29FC224E>) |
| 8086:1502 | 17aa:21ce | Intel            | 82579LM Gigabit Network Connectio... | 936   | e1000e     | [8873DFC3AC](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4290RV1/DE3C8C09D42A/ROSA-12.6/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/8873DFC3AC>) |
| 8086:1503 | 1043:849c | Intel            | 82579V Gigabit Network Connection    | 713   | e1000e     | [A007041CBD](<Desktop/ASUSTek Computer/Maximus/Maximus V GENE/7F15450C5584/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/A007041CBD>) |
| 8086:1502 | 1028:052c | Intel            | 82579LM Gigabit Network Connectio... | 674   | e1000e     | [734E205226](<Desktop/Dell/OptiPlex/OptiPlex 7010/1CD0F71C8C43/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/734E205226>) |
| 10de:03ef | 1849:03ef | Nvidia           | MCP61 Ethernet                       | 546   | forcedeth  | [CB76400A00](<Desktop/ASRock/N68-S/N68-S UCC/3C232072D095/NEPTUNE-8.1/6.1.0-18-AMD64/X86_64/CB76400A00>) |
| 8086:10ea | 17aa:2153 | Intel            | 82577LM Gigabit Network Connection   | 525   | e1000e     | [ECF4A20D48](<Notebook/Lenovo/ThinkPad/ThinkPad T510 4313A11/2CE2156B4537/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/ECF4A20D48>) |
| 10ec:8125 | 1849:8125 | Realtek Semic... | RTL8125 2.5GbE Controller            | 496   | r8169      | [7DB2107E2A](<Desktop/ASRock/B650/B650M-HDV-M.2/9DE4309FD01E/ARCH-ROLLING/6.12.8-ARCH1-1/X86_64/7DB2107E2A>) |
| 8086:1502 | 1028:047e | Intel            | 82579LM Gigabit Network Connectio... | 463   | e1000e     | [3047D18F75](<Desktop/Dell/OptiPlex/OptiPlex 790/4A8B08DA18B5/ZORIN-17/6.8.0-50-GENERIC/X86_64/3047D18F75>) |
| 8086:10f5 | 17aa:20ee | Intel            | 82567LM Gigabit Network Connection   | 371   | e1000e     | [7B16EB5229](<Notebook/Lenovo/ThinkPad/ThinkPad T500 2241WKY/6679B8A41DC3/ZORIN-17/6.8.0-50-GENERIC/X86_64/7B16EB5229>) |
| 8086:10d3 | 8086:a01f | Intel            | 82574L Gigabit Network Connection    | 326   | e1000e     | [0B63013A2A](<Desktop/ASUSTek Computer/M4A79T/M4A79T Deluxe/BE3CF50E786D/LINUXMINT-21.3/5.15.0-130-GENERIC/X86_64/0B63013A2A>) |
| 10ec:8125 | 1462:7c91 | Realtek Semic... | RTL8125 2.5GbE Controller            | 325   | r8169      | [6D22883B06](<Desktop/MSI/MS-7/MS-7C91/207441CF8DA8/CACHYOS/6.12.0-1-AMD-STAGING-DRM-NEXT-GIT-G16B8B0512423/X86_64/6D22883B06>) |
| 8086:10de | 1028:0276 | Intel            | 82567LM-3 Gigabit Network Connection | 321   | e1000e     | [8FB7D29EDA](<Desktop/Dell/OptiPlex/OptiPlex 960/9D40226D0DC5/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/8FB7D29EDA>) |
| 8086:1502 | 1028:0493 | Intel            | 82579LM Gigabit Network Connectio... | 303   | e1000e     | [46C2760E4E](<Notebook/Dell/Latitude/Latitude E6420/27A84812735F/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/46C2760E4E>) |
| 8086:1502 | 1028:0534 | Intel            | 82579LM Gigabit Network Connectio... | 282   | e1000e     | [860E215DAF](<Notebook/Dell/Latitude/Latitude E6430/A0E982126F70/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/860E215DAF>) |
| 10de:03ef | 1458:e000 | Nvidia           | MCP61 Ethernet                       | 279   | forcedeth  | [4040206002](<Desktop/Gigabyte Technology/M68/M68MT-S2/8DE8D73FA1FF/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/4040206002>) |
| 8086:1521 | 15d9:1521 | Intel            | I350 Gigabit Network Connection      | 272   | igb        | [F3D2F362E8](<Server/Supermicro/X9/X9SRE-X9SRE-3F-X9SRi-X9SRi-3F/55A635F4E92C/DEBIAN-12/6.8.8-2-PVE/X86_64/F3D2F362E8>) |
| 8086:10ea | 1028:040a | Intel            | 82577LM Gigabit Network Connection   | 257   | e1000e     | [CE431D6DEF](<Notebook/Dell/Latitude/Latitude E6410/008BAA37A996/ZORIN-17/6.8.0-50-GENERIC/X86_64/CE431D6DEF>) |
| 8086:1502 | 103c:3397 | Intel            | 82579LM Gigabit Network Connectio... | 253   | e1000e     | [95CC9C1997](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/3653D99842D3/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/95CC9C1997>) |
| 8086:10f5 | 1028:0233 | Intel            | 82567LM Gigabit Network Connection   | 223   | e1000e     | [D5DCFBC839](<Notebook/Dell/Latitude/Latitude E6400/429F04A48EEB/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/D5DCFBC839>) |
| 8086:1533 | 15d9:1533 | Intel            | I210 Gigabit Network Connection      | 222   | igb        | [A8188B3AF2](<Desktop/Supermicro/SYS-5018/SYS-5018D-MTF/E60ABF2B5C02/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/A8188B3AF2>) |
| 8086:1539 | 8086:0000 | Intel            | I211 Gigabit Network Connection      | 219   | igb        | [BFA66C5393](<Desktop/PC Engines/apu/apu4/E5703BF41520/DTS-DISTRO-2.1.2/6.6.21-YOCTO-STANDARD/X86_64/BFA66C5393>) |
| 8086:1502 | 103c:161c | Intel            | 82579LM Gigabit Network Connectio... | 217   | e1000e     | [0A8D680CF0](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8460p/636CD01ADFA4/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/0A8D680CF0>) |
| 8086:1502 | 103c:179b | Intel            | 82579LM Gigabit Network Connectio... | 208   | e1000e     | [63E91F06EF](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8470p/C1D8318F6F12/BLACKPANTHER-OS-18.1/5.15.85-DESKTOP-1BP/X86_64/63E91F06EF>) |
| 8086:1502 | 103c:339a | Intel            | 82579LM Gigabit Network Connectio... | 207   | e1000e     | [7FC68E979E](<Desktop/Hewlett-Packard/Compaq/Compaq Pro 6300 SFF/38CD5472725E/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/7FC68E979E>) |
| 10de:03ef | 1043:83a4 | Nvidia           | MCP61 Ethernet                       | 203   | forcedeth  | [8B53C864FE](<Desktop/ASUSTek Computer/M2N68-AM/M2N68-AM SE2/64710A5B1916/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/8B53C864FE>) |
| 8086:10bd | 1028:0211 | Intel            | 82566DM-2 Gigabit Network Connection | 203   | e1000e     | [5DBB155AB6](<Desktop/Dell/OptiPlex/OptiPlex 755/A76EFDE815CB/LINUXMINT-21.3/5.15.0-130-GENERIC/X86_64/5DBB155AB6>) |
| 8086:1502 | 103c:1495 | Intel            | 82579LM Gigabit Network Connectio... | 194   | e1000e     | [F9588CF3EB](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite SFF PC/5841A5CB694F/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/F9588CF3EB>) |
| 8086:1533 | ffff:0000 | Intel            | I210 Gigabit Network Connection      | 184   | igb        | [1D7C3F988E](<Desktop/Advantech/MiC-770/MiC-770 v2/AA3D3FF0AC3F/UBUNTU-24.10/6.11.0-13-GENERIC/X86_64/1D7C3F988E>) |
| 8086:1533 | 1043:8557 | Intel            | I210 Gigabit Network Connection      | 176   | igb        | [E805BE0AAC](<Server/Kraftway/GEG/GEG/C4E325834440/DEBIAN-12/6.1.0-27-AMD64/X86_64/E805BE0AAC>) |
| 8086:1049 | 17aa:20b9 | Intel            | 82566MM Gigabit Network Connection   | 165   | e1000e     | [C395B3E28C](<Notebook/Lenovo/ThinkPad/ThinkPad T61 7658CTO/9C38978E46CF/LUBUNTU-24.04/6.8.0-31-GENERIC/X86_64/C395B3E28C>) |
| 8086:1502 | 103c:1497 | Intel            | 82579LM Gigabit Network Connectio... | 162   | e1000e     | [256C3DEF88](<Desktop/Hewlett-Packard/Compaq/Compaq 6200 Pro SFF PC/2EF617BBD3CB/ZORIN-17/6.8.0-50-GENERIC/X86_64/256C3DEF88>) |
| 8086:1502 | 1028:0494 | Intel            | 82579LM Gigabit Network Connectio... | 146   | e1000e     | [C3A5CF03A9](<Notebook/Dell/Latitude/Latitude E6520/E350D4696CE5/FEDORA-41/6.12.4-200.FC41.X86_64/X86_64/C3A5CF03A9>) |
| 8086:10f6 | 8086:0000 | Intel            | 82574L Gigabit Network Connection    | 138   | e1000e     | [05DE585A46](<Desktop/Apple/MacPro5/MacPro5,1/9F24DF913B5F/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/05DE585A46>) |
| 10de:03ef | 1043:8234 | Nvidia           | MCP61 Ethernet                       | 136   | forcedeth  | [EE0520CC79](<Desktop/ASUSTek Computer/M2N-X/M2N-X Plus/E0B6FE1ED3E2/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/EE0520CC79>) |
| 8086:10de | 1028:027f | Intel            | 82567LM-3 Gigabit Network Connection | 134   | e1000e     | [8378333655](<Desktop/Dell/OptiPlex/OptiPlex 760/A0C6A78B617B/UBUNTU-MATE-24.04/6.8.0-51-GENERIC/X86_64/8378333655>) |
| 8086:1533 | 1849:1533 | Intel            | I210 Gigabit Network Connection      | 123   | igb        | [EE0C91380E](<Server/ASRockRack/B650/B650D4U-2L2T-BCM/4E50B00275AF/ALMA-8.10/4.18.0-553.33.1.EL8_10.X86_64/X86_64/EE0C91380E>) |
| 8086:10bd | 103c:2818 | Intel            | 82566DM-2 Gigabit Network Connection | 121   | e1000e     | [5F76CB932B](<Desktop/Hewlett-Packard/Compaq/Compaq dc7800p Small Form Factor/7242AFDF6A2C/PARROT-6.2/5.15.158-0515158-GENERIC/X86_64/5F76CB932B>) |
| 10ec:8125 | 1462:7c94 | Realtek Semic... | RTL8125 2.5GbE Controller            | 120   | r8169      | [F7C8A6C602](<Desktop/MSI/MS-7/MS-7C94/96058053E9EC/ENDEAVOUROS-ROLLING/6.6.69-1-LTS/X86_64/F7C8A6C602>) |
| 8086:1502 | 10f7:8338 | Intel            | 82579LM Gigabit Network Connectio... | 117   | e1000e     | [E3EAD6C710](<Notebook/Panasonic/CF-NX2/CF-NX2AWLCS/44E8C18EED68/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E3EAD6C710>) |
| 8086:1502 | 1028:0535 | Intel            | 82579LM Gigabit Network Connectio... | 116   | e1000e     | [819B23DD43](<Notebook/Dell/Latitude/Latitude E6530/3C602EA06DBE/KUBUNTU-24.10/6.11.0-8-GENERIC/X86_64/819B23DD43>) |
| 8086:1503 | 1025:8000 | Intel            | 82579V Gigabit Network Connection    | 116   | e1000e     | [935796FBB9](<Desktop/Acer/Aspire/Aspire X3960/7E03858EEA3B/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/935796FBB9>) |
| 8086:1502 | 10cf:161b | Intel            | 82579LM Gigabit Network Connectio... | 115   | e1000e     | [DE007DA665](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK S762/D56B6CFC56AC/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/DE007DA665>) |
| 8086:10ea | 1028:040b | Intel            | 82577LM Gigabit Network Connection   | 111   | e1000e     | [532AFB1E7D](<Notebook/Dell/Latitude/Latitude E6510/CFD329EF96CE/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/532AFB1E7D>) |
| 8086:1502 | 103c:1589 | Intel            | 82579LM Gigabit Network Connectio... | 111   | e1000e     | [DD5A66147D](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/05F06043C621/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/DD5A66147D>) |
| 10ec:8125 | 1462:7c84 | Realtek Semic... | RTL8125 2.5GbE Controller            | 110   | r8169      | [1A60E8FB7A](<Desktop/MSI/MS-7/MS-7C84/506C44FC6B16/UBUNTU-22.04/6.8.0-49-GENERIC/X86_64/1A60E8FB7A>) |

### Network and computing encryption device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19e5:a255 |           | Huawei Techno... | HiSilicon SEC Engine                 | 4     | hisi_sec2  | [29BDE967FC](<Server/HUAWEI/TaiShan/TaiShan 2280 V2/2603C7B2E57E/UBUNTU-22.04/5.15.0-88-GENERIC/AARCH64/29BDE967FC>) |
| 177d:0010 | 1137:00a0 | Cavium           | CN15XX/CN16XX [Nitrox PX]            | 1     |            | [26B9C3ADB7](<Desktop/Cisco/WAVE-694/WAVE-694-K9/7A7FA3E1DC65/OL-9.2/5.15.0-102.110.5.1.EL9UEK.X86_64/X86_64/26B9C3ADB7>) |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1485 | 1022:1485 | AMD              | Starship/Matisse Reserved SPP        | 5415  |            | [726B65D6E8](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.10/4.18.0-553.27.1.EL8_10.X86_64/X86_64/726B65D6E8>) |
| 1022:148a | 1022:148a | AMD              | Starship/Matisse PCIe Dummy Function | 5221  |            | [726B65D6E8](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.10/4.18.0-553.27.1.EL8_10.X86_64/X86_64/726B65D6E8>) |
| 1022:145a | 1022:145a | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 3619  |            | [A23FC83EDD](<Desktop/Gigabyte Technology/AB350/AB350-Gaming/B5A158869F92/GENTOO-2.17/6.6.67-GENTOO/X86_64/A23FC83EDD>) |
| 1022:1455 | 1022:1455 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 3536  |            | [A23FC83EDD](<Desktop/Gigabyte Technology/AB350/AB350-Gaming/B5A158869F92/GENTOO-2.17/6.6.67-GENTOO/X86_64/A23FC83EDD>) |
| 1022:1485 | 1043:87c0 | AMD              | Starship/Matisse Reserved SPP        | 1802  | vfio_pci   | [88B1C0C262](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING WIFI II/B8760FB55781/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/88B1C0C262>) |
| 1022:148a | 1043:87c0 | AMD              | Starship/Matisse PCIe Dummy Function | 1802  |            | [88B1C0C262](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING WIFI II/B8760FB55781/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/88B1C0C262>) |
| 1022:145a | 1e44:1776 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 1747  |            | [DFF6A36E92](<Notebook/Valve/Galileo/Galileo/3D6CF2B6536D/STEAMOS-3.6.20/6.5.0-VALVE22-1-NEPTUNE-65-G9A338ED8A75E/X86_64/DFF6A36E92>) |
| 1022:1485 | 1043:8808 | AMD              | Starship/Matisse Reserved SPP        | 1460  | vfio_pci   | [DF3BBDD6E6](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/5A876E9931EF/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/DF3BBDD6E6>) |
| 1022:148a | 1043:8808 | AMD              | Starship/Matisse PCIe Dummy Function | 1460  |            | [DF3BBDD6E6](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/5A876E9931EF/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/DF3BBDD6E6>) |
| 1022:1455 | 1043:8747 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 1259  |            | [CF7D50FAE1](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-K II/24E629ECD716/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/CF7D50FAE1>) |
| 1022:145a | 1043:8747 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 1259  |            | [CF7D50FAE1](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-K II/24E629ECD716/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/CF7D50FAE1>) |
| 1022:14ec | 1022:14ec | AMD              | Phoenix Dummy Function               | 563   |            | [046BBB97DB](<Notebook/Lenovo/IdeaPad/IdeaPad Pro 5 14APH8 83AM/E902B3B08EDD/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/046BBB97DB>) |
| 1022:145a | 1458:d000 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 334   |            | [B725853875](<Desktop/Gigabyte Technology/A520M/A520M K/8D8852C521BF/ARCH-ROLLING/6.12.8-ARCH1-1/X86_64/B725853875>) |
| 1022:1485 | 1462:7c02 | AMD              | Starship/Matisse Reserved SPP        | 248   |            | [77E32DABCD](<Desktop/MSI/MS-7/MS-7C02/AE386F556A9D/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/77E32DABCD>) |
| 1022:148a | 1462:7c02 | AMD              | Starship/Matisse PCIe Dummy Function | 248   |            | [77E32DABCD](<Desktop/MSI/MS-7/MS-7C02/AE386F556A9D/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/77E32DABCD>) |
| 1022:145a | 1002:1636 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 233   |            | [17C782DE89](<Desktop/MSI/MS-7/MS-7C96/67FA9E65B084/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/17C782DE89>) |
| 1022:145a | 1043:8809 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 215   |            | [8012F9A21D](<Desktop/ASUSTek Computer/TUF/TUF Gaming B450M-PRO II/DF88FDDCCB65/ROSA-12.5.1/6.6.21-GENERIC-8ROSA2021.1-X86_64/X86_64/8012F9A21D>) |
| 1022:1485 | 1462:7b86 | AMD              | Starship/Matisse Reserved SPP        | 180   |            | [89CD372074](<Desktop/MSI/MS-7/MS-7B86/3FF968BBEDE3/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/89CD372074>) |
| 1022:148a | 1462:7b86 | AMD              | Starship/Matisse PCIe Dummy Function | 180   |            | [89CD372074](<Desktop/MSI/MS-7/MS-7B86/3FF968BBEDE3/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/89CD372074>) |
| 1022:14de | 1043:8877 | AMD              | Raphael/Granite Ridge PCIe Dummy ... | 171   |            | [FE9EE8D0B4](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR X670E HERO/C8BA3CD03BE3/KUBUNTU-24.10/6.11.0-13-GENERIC/X86_64/FE9EE8D0B4>) |
| 1022:145a | 1043:876b | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 151   |            | [4CB02F7CED](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-K/EF4B140B96CA/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/4CB02F7CED>) |
| 1022:145a | 17aa:3803 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 151   |            | [539C61EB30](<Notebook/Lenovo/Legion/Legion 5 Pro 16ACH6H 82JQ/82DA0831A7C3/CACHYOS/6.12.4-2-CACHYOS/X86_64/539C61EB30>) |
| 1022:145a | 1462:7c02 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 129   |            | [88D10A1126](<Desktop/MSI/MS-7/MS-7C02/DD7D36D47449/LMDE-6/6.1.0-28-AMD64/X86_64/88D10A1126>) |
| 1022:1455 | 1462:7c02 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 126   |            | [88D10A1126](<Desktop/MSI/MS-7/MS-7C02/DD7D36D47449/LMDE-6/6.1.0-28-AMD64/X86_64/88D10A1126>) |
| 1022:1485 | 1462:7c95 | AMD              | Starship/Matisse Reserved SPP        | 125   |            | [A3C4D34290](<Desktop/MSI/MS-7/MS-7C95/D9235FBE7F06/ARCH-ROLLING/6.11.5-X64V3-XANMOD1-1-EDGE-X64V3/X86_64/A3C4D34290>) |
| 1022:148a | 1462:7c95 | AMD              | Starship/Matisse PCIe Dummy Function | 125   |            | [A3C4D34290](<Desktop/MSI/MS-7/MS-7C95/D9235FBE7F06/ARCH-ROLLING/6.11.5-X64V3-XANMOD1-1-EDGE-X64V3/X86_64/A3C4D34290>) |
| 1022:145a | 1462:7b86 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 121   |            | [2A3140FF53](<Desktop/MSI/MS-7/MS-7B86/10FCED84DE65/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/2A3140FF53>) |
| 1022:1485 | 1462:7b89 | AMD              | Starship/Matisse Reserved SPP        | 114   |            | [597E16BA37](<Desktop/MSI/MS-7/MS-7B89/716384C17A3C/LINUXMINT-21.3/6.2.0-39-GENERIC/X86_64/597E16BA37>) |
| 1022:148a | 1462:7b89 | AMD              | Starship/Matisse PCIe Dummy Function | 114   |            | [597E16BA37](<Desktop/MSI/MS-7/MS-7B89/716384C17A3C/LINUXMINT-21.3/6.2.0-39-GENERIC/X86_64/597E16BA37>) |
| 1022:1455 | 1462:7b86 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 113   |            | [2A3140FF53](<Desktop/MSI/MS-7/MS-7B86/10FCED84DE65/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/2A3140FF53>) |
| 1022:1485 | 1462:7c56 | AMD              | Starship/Matisse Reserved SPP        | 111   |            | [93AFAFB17B](<Desktop/MSI/MS-7/MS-7C56/6AF597F49A57/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/93AFAFB17B>) |
| 1022:148a | 1462:7c56 | AMD              | Starship/Matisse PCIe Dummy Function | 111   |            | [93AFAFB17B](<Desktop/MSI/MS-7/MS-7C56/6AF597F49A57/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/93AFAFB17B>) |
| 1022:1485 | 1462:7c35 | AMD              | Starship/Matisse Reserved SPP        | 104   |            | [FC581D20C5](<Desktop/MSI/MS-7/MS-7C35/313CF5DF8E4B/NIXOS-25.05/6.12.2-ZEN1/X86_64/FC581D20C5>) |
| 1022:148a | 1462:7c35 | AMD              | Starship/Matisse PCIe Dummy Function | 102   |            | [FC581D20C5](<Desktop/MSI/MS-7/MS-7C35/313CF5DF8E4B/NIXOS-25.05/6.12.2-ZEN1/X86_64/FC581D20C5>) |
| 1022:1485 | 1462:7c94 | AMD              | Starship/Matisse Reserved SPP        | 101   |            | [F7C8A6C602](<Desktop/MSI/MS-7/MS-7C94/96058053E9EC/ENDEAVOUROS-ROLLING/6.6.69-1-LTS/X86_64/F7C8A6C602>) |
| 1022:148a | 1462:7c94 | AMD              | Starship/Matisse PCIe Dummy Function | 101   |            | [F7C8A6C602](<Desktop/MSI/MS-7/MS-7C94/96058053E9EC/ENDEAVOUROS-ROLLING/6.6.69-1-LTS/X86_64/F7C8A6C602>) |
| 1022:14ec | f111:0006 | AMD              | Phoenix Dummy Function               | 95    |            | [041F977A25](<Notebook/Framework/Laptop/Laptop 13/621585FACCFA/NIXOS-25.05/6.6.67-HARDENED1/X86_64/041F977A25>) |
| 1022:145a | 1002:15d8 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 89    |            | [6E86EC71A9](<Desktop/ASRock/B450/B450 Gaming K4/FDCFCF022864/ALT-10.4/5.10.228-STD-DEF-ALT1/X86_64/6E86EC71A9>) |
| 1022:145a | 1462:7a38 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 88    |            | [EB51FEDFEE](<Desktop/MSI/MS-7/MS-7A38/C65578E3E760/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/EB51FEDFEE>) |
| 1022:1485 | 1462:7c91 | AMD              | Starship/Matisse Reserved SPP        | 84    |            | [6D22883B06](<Desktop/MSI/MS-7/MS-7C91/207441CF8DA8/CACHYOS/6.12.0-1-AMD-STAGING-DRM-NEXT-GIT-G16B8B0512423/X86_64/6D22883B06>) |
| 1022:148a | 1462:7c91 | AMD              | Starship/Matisse PCIe Dummy Function | 84    |            | [6D22883B06](<Desktop/MSI/MS-7/MS-7C91/207441CF8DA8/CACHYOS/6.12.0-1-AMD-STAGING-DRM-NEXT-GIT-G16B8B0512423/X86_64/6D22883B06>) |
| 1022:14ec | 17aa:50d9 | AMD              | Phoenix Dummy Function               | 84    |            | [419E7B4071](<Notebook/Lenovo/ThinkPad/ThinkPad P14s Gen 4 21K5CTO1WW/3EBE01F10FDA/DEBIAN/6.13.0-RC4-TWI/X86_64/419E7B4071>) |
| 1022:145a | 1022:7901 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 83    |            | [0F2438BC90](<Notebook/GPU Company/GWNR7/GWNR7L1749/85771B969A63/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/0F2438BC90>) |
| 1022:145a | 1002:15dd | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 82    |            | [BE8F18E2AD](<Desktop/ASRock/B450/B450 Gaming-ITX-ac/72D68185C16C/DEBIAN-12/6.1.0-28-AMD64/X86_64/BE8F18E2AD>) |
| 1022:150d | 1022:150d | AMD              | Strix PCIe Dummy function            | 82    |            | [0338B4E237](<Convertible/ASUSTek Computer/ProArt/ProArt PX13 HN7306WU_HN7306WU/2DCB92D5D222/ARCH-ROLLING/6.12.8-ARCH1-1/X86_64/0338B4E237>) |
| 1022:1485 | 1462:7a38 | AMD              | Starship/Matisse Reserved SPP        | 79    |            | [9D27B3438A](<Desktop/MSI/MS-7/MS-7A38/E344D20AF2B0/ARCH-ROLLING/6.12.7-ARCH1-1/X86_64/9D27B3438A>) |
| 1022:148a | 1462:7a38 | AMD              | Starship/Matisse PCIe Dummy Function | 79    |            | [9D27B3438A](<Desktop/MSI/MS-7/MS-7A38/E344D20AF2B0/ARCH-ROLLING/6.12.7-ARCH1-1/X86_64/9D27B3438A>) |
| 1022:1455 | 1462:7a38 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 77    |            | [EB51FEDFEE](<Desktop/MSI/MS-7/MS-7A38/C65578E3E760/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/EB51FEDFEE>) |
| 1022:1485 | 1043:87e2 | AMD              | Starship/Matisse Reserved SPP        | 72    |            | [C8C490C383](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/93DC5F7B5AAA/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/C8C490C383>) |
| 1022:148a | 1043:87e2 | AMD              | Starship/Matisse PCIe Dummy Function | 72    |            | [C8C490C383](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/93DC5F7B5AAA/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/C8C490C383>) |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15e6 | 1022:15e4 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 662   | i2c_amd... | [08C2C8D3A6](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X509DA_M509DA/59E9D67B5FC0/ROSA-12.5.1/6.6.27-GENERIC-3ROSA2021.1-X86_64/X86_64/08C2C8D3A6>) |
| 106b:1801 | 106b:1801 | Apple            | T2 Bridge Controller                 | 335   | apple_bce  | [BA278C0390](<Notebook/Apple/MacBookPro16/MacBookPro16,1/08604154B492/ALT-11.0/6.6.69-6.6-ALT1/X86_64/BA278C0390>) |
| 106b:1802 | 106b:1802 | Apple            | T2 Secure Enclave Processor          | 335   |            | [BA278C0390](<Notebook/Apple/MacBookPro16/MacBookPro16,1/08604154B492/ALT-11.0/6.6.69-6.6-ALT1/X86_64/BA278C0390>) |
| 8086:9d24 |           | Intel            | Skylake-U/Y SPI Controller           | 226   | spi_int... | [165F302BE9](<Notebook/Google/Chell/Chell/D809DC2934A8/DEBIAN/6.12.6-AMD64/X86_64/165F302BE9>) |
| 8086:9d35 | 8086:7270 | Intel            | Sunrise Point-LP Integrated Senso... | 218   | intel_i... | [EAF1BB652C](<Tablet/Microsoft/Surface/Surface Book 2/B870A7627396/ARCH-ROLLING/6.12.7-ARCH1-1-NSB2/X86_64/EAF1BB652C>) |
| 8086:9d35 | 17aa:2238 | Intel            | Sunrise Point-LP Integrated Senso... | 136   | intel_i... | [8D1FC60351](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 4th 20FBCTO1WW/8838B54EE893/DEBIAN/6.12.6-AMD64/X86_64/8D1FC60351>) |
| 8086:9d35 | 8086:9d35 | Intel            | Sunrise Point-LP Integrated Senso... | 117   | intel_i... | [361E80801B](<Convertible/ASUSTek Computer/VivoBook/VivoBook Flip 14 TP401CAE/AA86663ADD46/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/361E80801B>) |
| 1022:15e6 | 1025:1456 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 78    | i2c_amd... | [E51FCF8215](<Notebook/Acer/Aspire/Aspire A315-23/172B98B38ECC/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/E51FCF8215>) |
| 1022:15e6 | 103c:85ea | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 75    | i2c_amd... | [7BC8AEBA55](<Notebook/Hewlett-Packard/Laptop/Laptop 15-db1xxx/293499430D89/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/7BC8AEBA55>) |
| 8086:9d35 | 103c:827d | Intel            | Sunrise Point-LP Integrated Senso... | 65    | intel_i... | [1640751A75](<Convertible/Hewlett-Packard/EliteBook/EliteBook x360 1030 G2/71D7E3B63BF6/ARCH-ROLLING/6.12.7-ARCH1-1/X86_64/1640751A75>) |
| 8086:9d35 | 1028:081d | Intel            | Sunrise Point-LP Integrated Senso... | 54    | intel_i... | [CEE01AB926](<Notebook/Dell/Latitude/Latitude 5290 2-in-1/962B30484F7C/CACHYOS-ROLLING/6.12.8-2-CACHYOS/X86_64/CEE01AB926>) |
| 8086:9d35 | 152d:1182 | Intel            | Sunrise Point-LP Integrated Senso... | 54    | intel_i... | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 8086:9d35 | 17aa:380d | Intel            | Sunrise Point-LP Integrated Senso... | 54    | intel_i... | [72F62139AD](<Convertible/Lenovo/Yoga/Yoga 530-14IKB 81EK/6F663D01DC7B/DEBIAN-12/6.1.0-27-AMD64/X86_64/72F62139AD>) |
| 8086:9d35 | 103c:83b9 | Intel            | Sunrise Point-LP Integrated Senso... | 52    | intel_i... | [AF6818A82D](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-ae0xx/DE9C1EA4683F/ARCH-ROLLING/6.12.4-ARCH1-1/X86_64/AF6818A82D>) |
| 8086:9d35 | 1028:0740 | Intel            | Sunrise Point-LP Integrated Senso... | 51    | intel_i... | [47282D0230](<Notebook/Dell/Inspiron/Inspiron 13-5378/380E3DB1C307/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/47282D0230>) |
| 8086:9d35 | 17aa:2259 | Intel            | Sunrise Point-LP Integrated Senso... | 51    | intel_i... | [8AD221E4E7](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES17E0Z/81C8148F2637/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/8AD221E4E7>) |
| 8086:9d35 | 17aa:224e | Intel            | Sunrise Point-LP Integrated Senso... | 50    | intel_i... | [04D4E1D228](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 2nd 20JDCTO1WW/F5D2CA36B13A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/04D4E1D228>) |
| 8086:9d35 | 1028:077a | Intel            | Sunrise Point-LP Integrated Senso... | 47    | intel_i... | [92DCE0F9AC](<Convertible/Dell/XPS/XPS 13 9365/E7B7DFCD9CA4/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/92DCE0F9AC>) |
| 8086:22d8 | 103c:813e | Intel            | Integrated Sensor Solution           | 46    | intel_i... | [F5FB19DB6B](<Notebook/Hewlett-Packard/Pavilion/Pavilion x2 Detachable/12080E64C2FE/LUBUNTU-22.04/6.5.0-45-GENERIC/X86_64/F5FB19DB6B>) |
| 8086:22d8 | 1043:13a0 | Intel            | Integrated Sensor Solution           | 46    | intel_i... | [2AA1D5261D](<Tablet/ASUSTek Computer/T101/T101HA/302BE3A15A2C/LMDE-6/6.1.0-23-AMD64/X86_64/2AA1D5261D>) |
| 8086:9d35 | 17aa:5061 | Intel            | Sunrise Point-LP Integrated Senso... | 43    | intel_i... | [9711BE4BFB](<Convertible/Lenovo/ThinkPad/ThinkPad Yoga 370 20JH0017AU/0DBC76052C6D/ZORIN-17/6.8.0-50-GENERIC/X86_64/9711BE4BFB>) |
| 8086:9d35 | 17aa:506d | Intel            | Sunrise Point-LP Integrated Senso... | 41    | intel_i... | [1516A75783](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga 20LJS2R900/741AADCD3E87/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/1516A75783>) |
| 8086:22d8 | 8086:7270 | Intel            | Integrated Sensor Solution           | 40    | intel_i... | [DC120E3257](<Convertible/Lenovo/YB1/YB1-X91F/9D7F159A248D/UBUNTU-22.04/6.8.0-40-GENERIC/X86_64/DC120E3257>) |
| 8086:9d35 | 103c:82ca | Intel            | Sunrise Point-LP Integrated Senso... | 36    | intel_i... | [F0D42DF827](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/0C327DDF3EC7/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/F0D42DF827>) |
| 8086:9d35 | 17aa:2237 | Intel            | Sunrise Point-LP Integrated Senso... | 35    | intel_i... | [237D42F7FC](<Convertible/Lenovo/ThinkPad/ThinkPad Yoga 260 20FES2FE0E/725E774A42BE/ARCH-ROLLING/6.11.6-ARCH1-1/X86_64/237D42F7FC>) |
| 1022:15e4 | 103c:85dd | AMD              | Sensor Fusion Hub                    | 34    | amd_sfh    | [19193380D7](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15-ds0xxx/41FB038B6EDB/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/19193380D7>) |
| 8086:22d8 | 1043:1400 | Intel            | Integrated Sensor Solution           | 34    | intel_i... | [073DCFBEFD](<Tablet/ASUSTek Computer/T102/T102HA/B8F0B026C483/ZORIN-17/6.5.0-25-GENERIC/X86_64/073DCFBEFD>) |
| 8086:22d8 | 1043:1bdd | Intel            | Integrated Sensor Solution           | 34    | intel_i... | [6F00D9AB57](<Notebook/ASUSTek Computer/T100/T100HAN/5746BA874981/ZORIN-17/6.8.0-40-GENERIC/X86_64/6F00D9AB57>) |
| 8086:9d35 | 103c:8438 | Intel            | Sunrise Point-LP Integrated Senso... | 34    | intel_i... | [7965F306A8](<Convertible/Hewlett-Packard/EliteBook/EliteBook x360 1030 G3/ECCAA55C8EFE/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/7965F306A8>) |
| 8086:9d35 | 1028:073b | Intel            | Sunrise Point-LP Integrated Senso... | 33    | intel_i... | [BC5F8753E8](<Notebook/Dell/Inspiron/Inspiron 13-5368/433CD88E3B45/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/BC5F8753E8>) |
| 8086:9d35 | 103c:80fc | Intel            | Sunrise Point-LP Integrated Senso... | 33    | intel_i... | [03F386BA3C](<Notebook/Hewlett-Packard/Elite/Elite x2 1012 G1/F99F3D5C9BC0/ARCH-ROLLING/6.10.6-ARCH1-1/X86_64/03F386BA3C>) |
| 8086:9d35 | 103c:830f | Intel            | Sunrise Point-LP Integrated Senso... | 33    | intel_i... | [4F874E00D3](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible 14-ba0xx/7C3559929E8C/LINUXMINT-22/6.12.6-1-LIQUORIX-AMD64/X86_64/4F874E00D3>) |
| 1022:15e4 | 103c:8496 | AMD              | Sensor Fusion Hub                    | 32    | amd_sfh    | [8BF9B1CE8C](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 13-ag0xxx/BCD79CA6C5AF/DEBIAN-12/6.1.0-28-AMD64/X86_64/8BF9B1CE8C>) |
| 1022:15e4 | 103c:85de | AMD              | Sensor Fusion Hub                    | 32    | amd_sfh    | [9930026B7C](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 13-ar0xxx/677A3E89A120/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/9930026B7C>) |
| 8086:9d35 | 1028:07a4 | Intel            | Sunrise Point-LP Integrated Senso... | 32    | intel_i... | [9BDEF7697E](<Tablet/Dell/Latitude/Latitude 5285/03AE783826C3/ZORIN-17/6.8.0-45-GENERIC/X86_64/9BDEF7697E>) |
| 8086:a135 | 1028:080d | Intel            | 100 Series/C230 Series Chipset Fa... | 32    | intel_i... | [0795B7D84F](<Convertible/Dell/XPS/XPS 15 9575/DB54F1A2F501/LINUXMINT-22/6.8.0-31-GENERIC/X86_64/0795B7D84F>) |
| 8086:22d8 | 103c:827c | Intel            | Integrated Sensor Solution           | 30    | intel_i... | [878A94CA7F](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/3D11A237BEFA/ZORIN-17/6.8.0-49-GENERIC/X86_64/878A94CA7F>) |
| 8086:a2a4 |           | Intel            | 200 Series/Z370 Chipset Family SP... | 30    | spi_int... | [AF63B5BA1C](<Desktop/Hewlett-Packard/Z4/Z4 G4 Workstation/5CFDD07CE006/DEBIAN/6.12.6-AMD64/X86_64/AF63B5BA1C>) |
| 8086:9d35 | 103c:83b2 | Intel            | Sunrise Point-LP Integrated Senso... | 29    | intel_i... | [639F1B214F](<Notebook/Hewlett-Packard/ZBook/ZBook 15u G5/BB41E7A4FC58/BAZZITE-41/6.11.9-303.BAZZITE.FC41.X86_64/X86_64/639F1B214F>) |
| 8086:9d35 | 17aa:506c | Intel            | Sunrise Point-LP Integrated Senso... | 28    | intel_i... | [C500A9DCB9](<Convertible/Lenovo/ThinkPad/ThinkPad S2 Yoga 3rd Gen 20L2A002CD/DC1CAB23DD29/ARCH-ROLLING/6.11.7-ARCH1-1/X86_64/C500A9DCB9>) |
| 1022:15e4 | 103c:8497 | AMD              | Sensor Fusion Hub                    | 26    | amd_sfh    | [1E2FEEA3CE](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15-cp0xxx/0E01F520D3DD/KDE-NEON-22.04/6.5.0-26-GENERIC/X86_64/1E2FEEA3CE>) |
| 8086:9d35 | 103c:828b | Intel            | Sunrise Point-LP Integrated Senso... | 26    | intel_i... | [567E4C6343](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/53B866CA15BB/ZORIN-17/6.8.0-45-GENERIC/X86_64/567E4C6343>) |
| 8086:9d35 | 17aa:2244 | Intel            | Sunrise Point-LP Integrated Senso... | 25    | intel_i... | [454126AC6E](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KKS0S901/980E2F97C968/ARCH-ROLLING/6.12.6-ZEN1-1-ZEN/X86_64/454126AC6E>) |
| 8086:9d35 | 1028:0823 | Intel            | Sunrise Point-LP Integrated Senso... | 24    | intel_i... | [0837722DEA](<Notebook/Dell/Latitude/Latitude 7390 2-in-1/D06ECE8FBB9A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/0837722DEA>) |
| 8086:9d35 | 103c:8470 | Intel            | Sunrise Point-LP Integrated Senso... | 24    | intel_i... | [997D557B49](<Notebook/Hewlett-Packard/EliteBook/EliteBook x360 1040 G5/B5D34DFEFBCA/ARTIX/6.12.7-ARTIX1-1/X86_64/997D557B49>) |
| 8086:9d35 | 152d:1237 | Intel            | Sunrise Point-LP Integrated Senso... | 24    | intel_i... | [51D7C66A4E](<Tablet/Microsoft/Surface/Surface Go 2/CC8450395E18/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/51D7C66A4E>) |
| 8086:9d35 | 103c:827e | Intel            | Sunrise Point-LP Integrated Senso... | 23    | intel_i... | [F3F5DE25BA](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible/BF7B85E755BE/ZORIN-17/6.8.0-50-GENERIC/X86_64/F3F5DE25BA>) |
| 8086:9d35 | 1028:0804 | Intel            | Sunrise Point-LP Integrated Senso... | 22    | intel_i... | [53D1209311](<Notebook/Dell/Inspiron/Inspiron 5379/466BF53289C1/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/53D1209311>) |
| 8086:9d35 | 103c:8486 | Intel            | Sunrise Point-LP Integrated Senso... | 22    | intel_i... | [982670955F](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible 14-cd0xxx/8CB890109E13/ZORIN-17/6.8.0-40-GENERIC/X86_64/982670955F>) |
| 8086:9d35 | 103c:81a1 | Intel            | Sunrise Point-LP Integrated Senso... | 21    | intel_i... | [B1647E295A](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible/D41F5A2F0987/UBUNTU-22.04/6.8.0-49-GENERIC/X86_64/B1647E295A>) |

### Parallel controller (bidir) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1c00:2170 | 1c00:2170 | WCH              | CH351 PCIe Parallel Port Adapter     | 11    |            | [04FA6A24EE](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 MT/F87673EB97C3/ALT-10.4/5.10.198-STD-DEF-ALT1/X86_64/04FA6A24EE>) |
| 10ee:8034 | 10ee:0007 | Xilinx           | Parallel controller                  | 1     | xdma       | [87EF2CAB75](<All In One/Intel/N5095-AIO/N5095-AIO T1/CB74E1346431/UBUNTU-20.04/5.15.0-107-GENERIC/X86_64/87EF2CAB75>) |
| 1407:8000 |           | Lava Computer... | Lava Parallel                        | 1     | parport_pc | [1733DC0809](<Desktop/ASUSTek Computer/M5/M5A78L-M-USB3/FD5A0CD3675B/DEBIAN-9/5.4.11/X86_64/1733DC0809>) |
| 1415:9523 | 1415:0001 | Oxford Semico... | OX16PCI952 Integrated Parallel Port  | 1     | parport_pc | [AB95A02DA7](<Desktop/Gigabyte Technology/Z77/Z77-DS3H/130931CEF97D/UBUNTU-18.04/4.15.0-99-GENERIC/X86_64/AB95A02DA7>) |
| 1415:9523 | 1415:1201 | Oxford Semico... | OX16PCI952 Integrated Parallel Port  | 1     | parport_pc | [217BFD48BD](<Desktop/Intel/DG33FB/DG33FB AAD81072-309/C69B68BCED37/LMDE-4/4.19.0-10-AMD64/X86_64/217BFD48BD>) |

### Parallel controller (ecp) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1415:c110 | 1415:c110 | Oxford Semico... | OXPCIe952 Parallel Port              | 28    | parport_pc | [74D8354490](<Desktop/ASUSTek Computer/P6T/P6T DELUXE V2/1E91E02A8F1F/MANJARO/6.10.13-3-MANJARO/X86_64/74D8354490>) |
| 1409:7268 | 1409:0103 | Timedia Techn... | SUN1888 (Dual IEEE1284 parallel p... | 6     | parport_pc | [6872AE9FB4](<Desktop/Packard Bell/IMEDIA/IMEDIA X5705 GE/21629797DC7A/GENTOO-2.7/5.10.52-GENTOO/X86_64/6872AE9FB4>) |
| 1409:7268 | 1409:0104 | Timedia Techn... | SUN1888 (Dual IEEE1284 parallel p... | 3     | parport_pc | [FCE4597AD2](<Desktop/Dell/Precision/Precision T5600/CD5FD08D4152/KUBUNTU-24.10/6.11.0-12-GENERIC/X86_64/FCE4597AD2>) |
| 1409:3268 | 1409:0101 | Timedia Techn... | Parallel controller                  | 1     |            | [F00FF7EF01](<Desktop/Intel/DH55PJ/DH55PJ AAE93812-302/ED2E697C6EB0/OPENMANDRIVA-23.08/6.4.11-DESKTOP-1OMV2390/X86_64/F00FF7EF01>) |
| 1415:9513 | 1415:9513 | Oxford Semico... | OX16PCI954 (Quad 16950 UART) func... | 1     | parport_pc | [3B5585BEC8](<Server/Supermicro/X9/X9SRA-X9SRA-3/E73ED86A7227/DEBIAN-11/5.10.0-33-AMD64/X86_64/3B5585BEC8>) |
| 1415:c100 | 1415:c100 | Oxford Semico... | OXPCIe952 Parallel Port              | 1     | parport_pc | [D3A4404A9C](<Desktop/MSI/MS-7/MS-7E47/262F77DE3A38/FEDORA-41/6.11.5-300.FC41.X86_64/X86_64/D3A4404A9C>) |
| 1415:c11c | 1415:c11c | Oxford Semico... | OXPCIe952 Parallel Port              | 1     | parport_pc | [9D66F53103](<Desktop/Hewlett-Packard/Compaq/Compaq 6000 Pro MT PC/D92123525F26/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/9D66F53103>) |

### Parallel controller (ieee1284) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 9710:9865 | a000:2000 | MosChip Semic... | PCI 9865 Multi-I/O Controller        | 46    | parport_pc | [D20EA9B845](<Desktop/Hewlett-Packard/Compaq/Compaq Pro 6300 SFF/6C84003478A6/LINUXMINT-21.3/5.15.0-124-GENERIC/X86_64/D20EA9B845>) |
| 9710:9912 | a000:2000 | MosChip Semic... | PCIe 9912 Multi-I/O Controller       | 43    | parport... | [07CDF58410](<Desktop/MSI/MS-7/MS-7C95/6F01E4570CEF/FEDORA-31/5.8.18-100.FC31.X86_64/X86_64/07CDF58410>) |
| 1fd4:1999 | 1fd4:0100 | SUNIX            | Multiport serial controller          | 38    | parport... | [2864D95F71](<Desktop/Dell/OptiPlex/OptiPlex 3060/FF03180619B4/DEBIAN-12/6.8.12-4-PVE/X86_64/2864D95F71>) |
| ffff:9865 | a000:2000 | Illegal Vendo... | Parallel controller                  | 13    |            | [6A961E6E3E](<Desktop/Gigabyte Technology/H61/H61M-S2PV/0E7775900DC2/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/6A961E6E3E>) |
| 125b:9100 | a000:2000 | ASIX Electronics | AX99100 PCIe to Multi I/O Controller | 9     | parport_pc | [53DF068708](<Desktop/Intel/X79-VG2/X79-VG2 V2.2/5FBA233F6B1E/DEBIAN-12/6.1.0-25-RT-AMD64/X86_64/53DF068708>) |
| 1415:8403 | 1415:0000 | Oxford Semico... | OX9162 Mode 0 (parallel port)        | 5     | parport_pc | [88CFEF1DA9](<Desktop/Fujitsu Siemens/ESPRIMO/ESPRIMO E/22D79658C326/DEBIAN-12/6.1.0-28-AMD64/X86_64/88CFEF1DA9>) |
| 9710:9901 | a000:2000 | MosChip Semic... | PCIe 9901 Multi-I/O Controller       | 3     | parport_pc | [310F3D9EE4](<Desktop/Hewlett-Packard/Pavilion/Pavilion Gaming Desktop TG01-2xxx/7E1E0DFA8D7A/ARCH-ROLLING/6.11.9-ARCH1-1/X86_64/310F3D9EE4>) |
| 1fd4:1999 | 17aa:0100 | SUNIX            | Multiport serial controller          | 2     |            | [024BB5EA7E](<Desktop/Lenovo/ThinkCentre/ThinkCentre M58p 6234CL2/24B7AF7B12C9/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/024BB5EA7E>) |
| 9710:8925 | a000:2100 | MosChip Semic... | MosChip Parallel controller          | 1     |            | [4EDB22DA2D](<Desktop/ASUSTek Computer/V-P8/V-P8H67E/BCC9C221429D/DEBIAN-10/4.19.0-9-AMD64/X86_64/4EDB22DA2D>) |

### Performance counters (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2f30 | 8086:2f30 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 1157  | hswep_u... | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2f34 | 8086:2f34 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 PCI... | 1157  | hswep_u... | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2f7d | 8086:2f7d | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 1157  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2f36 | 8086:2f36 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 1094  | hswep_u... | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2f37 | 8086:2f37 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 1094  | hswep_u... | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:204c | 8086:0000 | Intel            | Sky Lake-E M3KTI Registers           | 653   | skx_uncore | [AF63B5BA1C](<Desktop/Hewlett-Packard/Z4/Z4 G4 Workstation/5CFDD07CE006/DEBIAN/6.12.6-AMD64/X86_64/AF63B5BA1C>) |
| 8086:204d | 8086:0000 | Intel            | Sky Lake-E M3KTI Registers           | 653   | skx_uncore | [AF63B5BA1C](<Desktop/Hewlett-Packard/Z4/Z4 G4 Workstation/5CFDD07CE006/DEBIAN/6.12.6-AMD64/X86_64/AF63B5BA1C>) |
| 8086:2015 | 8086:0000 | Intel            | Sky Lake-E Ubox Registers            | 648   |            | [AF63B5BA1C](<Desktop/Hewlett-Packard/Z4/Z4 G4 Workstation/5CFDD07CE006/DEBIAN/6.12.6-AMD64/X86_64/AF63B5BA1C>) |
| 8086:6f30 | 8086:6f30 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 596   | bdx_uncore | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6f34 | 8086:6f34 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 596   | bdx_uncore | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6f7d | 8086:6f7d | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 596   |            | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6f36 | 8086:6f36 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 564   | bdx_uncore | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6f37 | 8086:6f37 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 564   | bdx_uncore | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:2f38 | 8086:2f38 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 465   | hswep_u... | [2CD6888290](<Desktop/MACHINIST/E5-MR9A/E5-MR9A V1.0/A16E88B1E292/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/2CD6888290>) |
| 8086:0e36 | 8086:0000 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 409   | ivbep_u... | [ECFA27B66D](<Desktop/Apple/MacPro6/MacPro6,1/F0AE965F0330/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/ECFA27B66D>) |
| 8086:3c44 | 8086:0000 | Intel            | Xeon E5/Core i7 Ring to QuickPath... | 385   | snbep_u... | [DD5A66147D](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/05F06043C621/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/DD5A66147D>) |
| 8086:3ce6 | 8086:0000 | Intel            | Xeon E5/Core i7 QuickPath Interco... | 385   |            | [DD5A66147D](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/05F06043C621/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/DD5A66147D>) |
| 8086:3c43 | 8086:0000 | Intel            | Xeon E5/Core i7 Ring to PCI Expre... | 372   | snbep_u... | [DD5A66147D](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/05F06043C621/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/DD5A66147D>) |
| 8086:0e34 | 8086:0000 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 341   | ivbep_u... | [ECFA27B66D](<Desktop/Apple/MacPro6/MacPro6,1/F0AE965F0330/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/ECFA27B66D>) |
| 8086:2058 | 8086:0000 | Intel            | Sky Lake-E KTI 0                     | 296   | skx_uncore | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:6f38 | 8086:6f38 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 276   | bdx_uncore | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:2088 | 8086:0000 | Intel            | Sky Lake-E DDRIO Registers           | 248   | skx_uncore | [82572A2F0C](<Desktop/ASUSTek Computer/Pro/Pro WS X299 SAGE II/05AB15F81B71/MANJARO/6.12.4-1-MANJARO/X86_64/82572A2F0C>) |
| 8086:2f32 | 8086:2f32 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 QPI... | 204   | hswep_u... | [AAB2F96127](<Desktop/Lenovo/30A8/30A8/7FC11C4D5CAB/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/AAB2F96127>) |
| 8086:6f32 | 8086:6f32 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 203   | bdx_uncore | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6f33 | 8086:6f33 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 203   | bdx_uncore | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:3c46 |           | Intel            | Xeon E5/Core i7 Processor Home Ag... | 199   | snbep_u... | [DD5A66147D](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/05F06043C621/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/DD5A66147D>) |
| 8086:2f33 | 8086:2f33 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 QPI... | 191   | hswep_u... | [8BE65C83BD](<Desktop/Supermicro/X10/X10DAi/3AC93BECC1C3/UBUNTU-22.04/5.15.0-125-GENERIC/X86_64/8BE65C83BD>) |
| 8086:27a3 |           | Intel            | 945GM/GU Chipset Hardware Monitor... | 180   |            | [DE3A243820](<All In One/Apple/iMac5/iMac5,1/1F7269B01AAF/DEBIAN-11/5.10.0-33-686-PAE/I686/DE3A243820>) |
| 8086:3c46 | 8086:0000 | Intel            | Xeon E5/Core i7 Processor Home Ag... | 180   | snbep_u... | [D721436769](<Desktop/Others/X/X79/2577916637DB/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/D721436769>) |
| 8086:0e30 | 8086:0000 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 175   | ivbep_u... | [54EA7EE329](<Desktop/OEM/X/X79G/915E60C38A8F/ROSA-12.5.1/6.6.27-GENERIC-3ROSA2021.1-X86_64/X86_64/54EA7EE329>) |
| 8086:0e30 |           | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 169   | ivbep_u... | [ECFA27B66D](<Desktop/Apple/MacPro6/MacPro6,1/F0AE965F0330/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/ECFA27B66D>) |
| 8086:3c43 | 1043:84ef | Intel            | Xeon E5/Core i7 Ring to PCI Expre... | 156   | snbep_u... | [19D479AA20](<Desktop/ASUSTek Computer/Rampage/Rampage IV FORMULA/E37343E0894F/UBUNTU-23.04/6.2.0-39-GENERIC/X86_64/19D479AA20>) |
| 8086:3c44 | 1043:84ef | Intel            | Xeon E5/Core i7 Ring to QuickPath... | 156   | snbep_u... | [19D479AA20](<Desktop/ASUSTek Computer/Rampage/Rampage IV FORMULA/E37343E0894F/UBUNTU-23.04/6.2.0-39-GENERIC/X86_64/19D479AA20>) |
| 8086:3c46 | 1043:84ef | Intel            | Xeon E5/Core i7 Processor Home Ag... | 156   | snbep_u... | [19D479AA20](<Desktop/ASUSTek Computer/Rampage/Rampage IV FORMULA/E37343E0894F/UBUNTU-23.04/6.2.0-39-GENERIC/X86_64/19D479AA20>) |
| 8086:3ce6 | 1043:84ef | Intel            | Xeon E5/Core i7 QuickPath Interco... | 156   |            | [19D479AA20](<Desktop/ASUSTek Computer/Rampage/Rampage IV FORMULA/E37343E0894F/UBUNTU-23.04/6.2.0-39-GENERIC/X86_64/19D479AA20>) |
| 8086:3424 |           | Intel            | 7500/5520/5500/X58 Performance Mo... | 141   |            | [05DE585A46](<Desktop/Apple/MacPro5/MacPro5,1/9F24DF913B5F/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/05DE585A46>) |
| 8086:2088 |           | Intel            | Sky Lake-E DDRIO Registers           | 93    | skx_uncore | [82572A2F0C](<Desktop/ASUSTek Computer/Pro/Pro WS X299 SAGE II/05AB15F81B71/MANJARO/6.12.4-1-MANJARO/X86_64/82572A2F0C>) |
| 8086:2058 |           | Intel            | Sky Lake-E KTI 0                     | 91    | skx_uncore | [BE48E1A4CD](<Server/HPE/ProLiant/ProLiant DL380 Gen10/4A81CFAB7E9A/UBUNTU-20.04/5.15.0-127-GENERIC/X86_64/BE48E1A4CD>) |
| 8086:0e30 | 1043:84ef | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 90    | ivbep_u... | [382EC4FFCB](<Desktop/ASUSTek Computer/Rampage/Rampage IV EXTREME/9AB2C632EC6F/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/382EC4FFCB>) |
| 8086:0e34 | 1043:84ef | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 90    | ivbep_u... | [382EC4FFCB](<Desktop/ASUSTek Computer/Rampage/Rampage IV EXTREME/9AB2C632EC6F/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/382EC4FFCB>) |
| 8086:0e36 | 1043:84ef | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 90    | ivbep_u... | [382EC4FFCB](<Desktop/ASUSTek Computer/Rampage/Rampage IV EXTREME/9AB2C632EC6F/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/382EC4FFCB>) |
| 8086:6f30 | 103c:21ea | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 75    | bdx_uncore | [34E5B43715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/07607C1620F7/DEBIAN-12/6.8.8-4-PVE/X86_64/34E5B43715>) |
| 8086:6f34 | 103c:21ea | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 75    | bdx_uncore | [34E5B43715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/07607C1620F7/DEBIAN-12/6.8.8-4-PVE/X86_64/34E5B43715>) |
| 8086:6f36 | 103c:21ea | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 75    | bdx_uncore | [34E5B43715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/07607C1620F7/DEBIAN-12/6.8.8-4-PVE/X86_64/34E5B43715>) |
| 8086:6f37 | 103c:21ea | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 75    | bdx_uncore | [34E5B43715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/07607C1620F7/DEBIAN-12/6.8.8-4-PVE/X86_64/34E5B43715>) |
| 8086:6f7d | 103c:21ea | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 75    |            | [34E5B43715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/07607C1620F7/DEBIAN-12/6.8.8-4-PVE/X86_64/34E5B43715>) |
| 8086:3c43 | 103c:18a8 | Intel            | Xeon E5/Core i7 Ring to PCI Expre... | 69    | snbep_u... | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |
| 8086:3c44 | 103c:18a8 | Intel            | Xeon E5/Core i7 Ring to QuickPath... | 69    | snbep_u... | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |
| 8086:3c46 | 103c:18a8 | Intel            | Xeon E5/Core i7 Processor Home Ag... | 69    | snbep_u... | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |
| 8086:3ce6 | 103c:18a8 | Intel            | Xeon E5/Core i7 QuickPath Interco... | 69    |            | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |

### Pic (8259) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:342e |           | Intel            | 7500/5520/5500/X58 I/O Hub System... | 1613  | i7core_... | [05DE585A46](<Desktop/Apple/MacPro5/MacPro5,1/9F24DF913B5F/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/05DE585A46>) |
| 8086:3422 |           | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 1610  |            | [05DE585A46](<Desktop/Apple/MacPro5/MacPro5,1/9F24DF913B5F/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/05DE585A46>) |
| 8086:3423 |           | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 1610  |            | [05DE585A46](<Desktop/Apple/MacPro5/MacPro5,1/9F24DF913B5F/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/05DE585A46>) |
| 8086:3438 |           | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 936   | i5500_temp | [05DE585A46](<Desktop/Apple/MacPro5/MacPro5,1/9F24DF913B5F/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/05DE585A46>) |
| 8086:3425 |           | Intel            | 7500/5520/5500/X58 Physical and L... | 637   |            | [05DE585A46](<Desktop/Apple/MacPro5/MacPro5,1/9F24DF913B5F/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/05DE585A46>) |
| 8086:3426 |           | Intel            | 7500/5520/5500/X58 Routing and Pr... | 637   |            | [05DE585A46](<Desktop/Apple/MacPro5/MacPro5,1/9F24DF913B5F/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/05DE585A46>) |
| 8086:3427 |           | Intel            | 7500/5520/5500 Physical and Link ... | 570   |            | [05DE585A46](<Desktop/Apple/MacPro5/MacPro5,1/9F24DF913B5F/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/05DE585A46>) |
| 8086:3428 |           | Intel            | 7500/5520/5500 Routing & Protocol... | 570   |            | [05DE585A46](<Desktop/Apple/MacPro5/MacPro5,1/9F24DF913B5F/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/05DE585A46>) |
| 8086:3422 | 0028:0093 | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 130   |            | [D2A1DE9DC7](<Desktop/Dell/Precision/Precision WorkStation T3500/15A248424810/DEBIAN-11/5.10.0-33-AMD64/X86_64/D2A1DE9DC7>) |
| 8086:3423 | 0028:0093 | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 130   |            | [D2A1DE9DC7](<Desktop/Dell/Precision/Precision WorkStation T3500/15A248424810/DEBIAN-11/5.10.0-33-AMD64/X86_64/D2A1DE9DC7>) |
| 8086:342e | 0028:0093 | Intel            | 7500/5520/5500/X58 I/O Hub System... | 130   | i7core_... | [D2A1DE9DC7](<Desktop/Dell/Precision/Precision WorkStation T3500/15A248424810/DEBIAN-11/5.10.0-33-AMD64/X86_64/D2A1DE9DC7>) |
| 8086:3422 | 003c:000b | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 105   |            | [B076CBF109](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/416C8912B3CC/DEBIAN/6.11.10-AMD64/X86_64/B076CBF109>) |
| 8086:3423 | 003c:000b | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 105   |            | [B076CBF109](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/416C8912B3CC/DEBIAN/6.11.10-AMD64/X86_64/B076CBF109>) |
| 8086:342e | 003c:000b | Intel            | 7500/5520/5500/X58 I/O Hub System... | 105   | i7core_... | [B076CBF109](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/416C8912B3CC/DEBIAN/6.11.10-AMD64/X86_64/B076CBF109>) |
| 8086:3422 | 0028:006e | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 65    |            | [99948B5B1E](<Desktop/Dell/Precision/Precision WorkStation T5500/470ABAB9F17B/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/99948B5B1E>) |
| 8086:3423 | 0028:006e | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 65    |            | [99948B5B1E](<Desktop/Dell/Precision/Precision WorkStation T5500/470ABAB9F17B/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/99948B5B1E>) |
| 8086:342e | 0028:006e | Intel            | 7500/5520/5500/X58 I/O Hub System... | 65    | i7core_... | [99948B5B1E](<Desktop/Dell/Precision/Precision WorkStation T5500/470ABAB9F17B/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/99948B5B1E>) |
| 8086:3422 | 0086:0022 | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 51    |            | [8AF2B2F494](<Desktop/Lenovo/ThinkStation/ThinkStation D20 4158GK1/67C974340904/UBUNTU-MATE-22.04/5.15.0-119-GENERIC/X86_64/8AF2B2F494>) |
| 8086:3423 | 0086:0023 | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 51    |            | [8AF2B2F494](<Desktop/Lenovo/ThinkStation/ThinkStation D20 4158GK1/67C974340904/UBUNTU-MATE-22.04/5.15.0-119-GENERIC/X86_64/8AF2B2F494>) |
| 8086:342e | 0086:002e | Intel            | 7500/5520/5500/X58 I/O Hub System... | 51    | i7core_... | [8AF2B2F494](<Desktop/Lenovo/ThinkStation/ThinkStation D20 4158GK1/67C974340904/UBUNTU-MATE-22.04/5.15.0-119-GENERIC/X86_64/8AF2B2F494>) |
| 8086:3422 | 0028:006d | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 37    |            | [42C00B7A8A](<Desktop/Dell/Precision/Precision WorkStation T7500/C583DCA51C63/ZORIN-17/6.8.0-50-GENERIC/X86_64/42C00B7A8A>) |
| 8086:3423 | 0028:006d | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 37    |            | [42C00B7A8A](<Desktop/Dell/Precision/Precision WorkStation T7500/C583DCA51C63/ZORIN-17/6.8.0-50-GENERIC/X86_64/42C00B7A8A>) |
| 8086:342e | 0028:006d | Intel            | 7500/5520/5500/X58 I/O Hub System... | 37    | i7core_... | [42C00B7A8A](<Desktop/Dell/Precision/Precision WorkStation T7500/C583DCA51C63/ZORIN-17/6.8.0-50-GENERIC/X86_64/42C00B7A8A>) |
| 8086:3422 | 0086:00dc | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 14    |            | [BD871B1C6F](<Server/Intel/S5520/S5520HC/256D70541E78/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/BD871B1C6F>) |
| 8086:3423 | 0086:00dc | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 14    |            | [BD871B1C6F](<Server/Intel/S5520/S5520HC/256D70541E78/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/BD871B1C6F>) |
| 8086:3425 | 0086:00dc | Intel            | 7500/5520/5500/X58 Physical and L... | 14    |            | [BD871B1C6F](<Server/Intel/S5520/S5520HC/256D70541E78/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/BD871B1C6F>) |
| 8086:3426 | 0086:00dc | Intel            | 7500/5520/5500/X58 Routing and Pr... | 14    |            | [BD871B1C6F](<Server/Intel/S5520/S5520HC/256D70541E78/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/BD871B1C6F>) |
| 8086:3427 | 0086:00dc | Intel            | 7500/5520/5500 Physical and Link ... | 14    |            | [BD871B1C6F](<Server/Intel/S5520/S5520HC/256D70541E78/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/BD871B1C6F>) |
| 8086:3428 | 0086:00dc | Intel            | 7500/5520/5500 Routing & Protocol... | 14    |            | [BD871B1C6F](<Server/Intel/S5520/S5520HC/256D70541E78/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/BD871B1C6F>) |
| 8086:342e | 0086:00dc | Intel            | 7500/5520/5500/X58 I/O Hub System... | 14    | i7core_... | [BD871B1C6F](<Server/Intel/S5520/S5520HC/256D70541E78/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/BD871B1C6F>) |
| 8086:3438 | 0086:00dc | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 14    | i5500_temp | [BD871B1C6F](<Server/Intel/S5520/S5520HC/256D70541E78/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/BD871B1C6F>) |
| 8086:3422 | 0043:0063 | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 12    |            | [93FBAEAD82](<Desktop/ASUSTek Computer/Z8/Z8NA-D6/C48616086C0A/FEDORA-40/6.10.11-200.FC40.X86_64/X86_64/93FBAEAD82>) |
| 8086:3423 | 0043:0063 | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 12    |            | [93FBAEAD82](<Desktop/ASUSTek Computer/Z8/Z8NA-D6/C48616086C0A/FEDORA-40/6.10.11-200.FC40.X86_64/X86_64/93FBAEAD82>) |
| 8086:3425 | 0043:0063 | Intel            | 7500/5520/5500/X58 Physical and L... | 12    |            | [93FBAEAD82](<Desktop/ASUSTek Computer/Z8/Z8NA-D6/C48616086C0A/FEDORA-40/6.10.11-200.FC40.X86_64/X86_64/93FBAEAD82>) |
| 8086:3426 | 0043:0063 | Intel            | 7500/5520/5500/X58 Routing and Pr... | 12    |            | [93FBAEAD82](<Desktop/ASUSTek Computer/Z8/Z8NA-D6/C48616086C0A/FEDORA-40/6.10.11-200.FC40.X86_64/X86_64/93FBAEAD82>) |
| 8086:3427 | 0043:0063 | Intel            | 7500/5520/5500 Physical and Link ... | 12    |            | [93FBAEAD82](<Desktop/ASUSTek Computer/Z8/Z8NA-D6/C48616086C0A/FEDORA-40/6.10.11-200.FC40.X86_64/X86_64/93FBAEAD82>) |
| 8086:3428 | 0043:0063 | Intel            | 7500/5520/5500 Routing & Protocol... | 12    |            | [93FBAEAD82](<Desktop/ASUSTek Computer/Z8/Z8NA-D6/C48616086C0A/FEDORA-40/6.10.11-200.FC40.X86_64/X86_64/93FBAEAD82>) |
| 8086:342e | 0043:0063 | Intel            | 7500/5520/5500/X58 I/O Hub System... | 12    | i7core_... | [93FBAEAD82](<Desktop/ASUSTek Computer/Z8/Z8NA-D6/C48616086C0A/FEDORA-40/6.10.11-200.FC40.X86_64/X86_64/93FBAEAD82>) |
| 8086:3438 | 0043:0063 | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 12    | i5500_temp | [93FBAEAD82](<Desktop/ASUSTek Computer/Z8/Z8NA-D6/C48616086C0A/FEDORA-40/6.10.11-200.FC40.X86_64/X86_64/93FBAEAD82>) |
| 8086:3422 | 0034:0027 | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 9     |            | [DF81B53B94](<Server/Fujitsu/PRIMERGY/PRIMERGY TX300 S5/C75C8D396A0B/DEBIAN-11/5.15.158-2-PVE/X86_64/DF81B53B94>) |
| 8086:3423 | 0034:0027 | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 9     |            | [DF81B53B94](<Server/Fujitsu/PRIMERGY/PRIMERGY TX300 S5/C75C8D396A0B/DEBIAN-11/5.15.158-2-PVE/X86_64/DF81B53B94>) |
| 8086:3425 | 0034:0027 | Intel            | 7500/5520/5500/X58 Physical and L... | 9     |            | [DF81B53B94](<Server/Fujitsu/PRIMERGY/PRIMERGY TX300 S5/C75C8D396A0B/DEBIAN-11/5.15.158-2-PVE/X86_64/DF81B53B94>) |
| 8086:3426 | 0034:0027 | Intel            | 7500/5520/5500/X58 Routing and Pr... | 9     |            | [DF81B53B94](<Server/Fujitsu/PRIMERGY/PRIMERGY TX300 S5/C75C8D396A0B/DEBIAN-11/5.15.158-2-PVE/X86_64/DF81B53B94>) |
| 8086:3427 | 0034:0027 | Intel            | 7500/5520/5500 Physical and Link ... | 9     |            | [DF81B53B94](<Server/Fujitsu/PRIMERGY/PRIMERGY TX300 S5/C75C8D396A0B/DEBIAN-11/5.15.158-2-PVE/X86_64/DF81B53B94>) |
| 8086:3428 | 0034:0027 | Intel            | 7500/5520/5500 Routing & Protocol... | 9     |            | [DF81B53B94](<Server/Fujitsu/PRIMERGY/PRIMERGY TX300 S5/C75C8D396A0B/DEBIAN-11/5.15.158-2-PVE/X86_64/DF81B53B94>) |
| 8086:342e | 0034:0027 | Intel            | 7500/5520/5500/X58 I/O Hub System... | 9     | i7core_... | [DF81B53B94](<Server/Fujitsu/PRIMERGY/PRIMERGY TX300 S5/C75C8D396A0B/DEBIAN-11/5.15.158-2-PVE/X86_64/DF81B53B94>) |
| 8086:3438 | 0034:0027 | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 9     | i5500_temp | [DF81B53B94](<Server/Fujitsu/PRIMERGY/PRIMERGY TX300 S5/C75C8D396A0B/DEBIAN-11/5.15.158-2-PVE/X86_64/DF81B53B94>) |
| 8086:3422 | 0086:00da | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 7     |            | [D7D5249BC9](<Server/Intel/S5500/S5500BC/49891E2271E6/UBUNTU-22.04/6.2.0-31-GENERIC/X86_64/D7D5249BC9>) |
| 8086:3423 | 0086:00da | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 7     |            | [D7D5249BC9](<Server/Intel/S5500/S5500BC/49891E2271E6/UBUNTU-22.04/6.2.0-31-GENERIC/X86_64/D7D5249BC9>) |
| 8086:3425 | 0086:00da | Intel            | 7500/5520/5500/X58 Physical and L... | 7     |            | [D7D5249BC9](<Server/Intel/S5500/S5500BC/49891E2271E6/UBUNTU-22.04/6.2.0-31-GENERIC/X86_64/D7D5249BC9>) |

### Pic (io(x)-apic) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2f2c | 8086:0000 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 885   |            | [0179690CC0](<Desktop/Intel/X/X99/4D99FA41EB21/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/0179690CC0>) |
| 8086:2026 | 8086:2026 | Intel            | Sky Lake-E IOAPIC                    | 614   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2036 | 8086:2036 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 614   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:342f |           | Intel            | 7500/5520/5500/X58 Trusted Execut... | 563   |            | [05DE585A46](<Desktop/Apple/MacPro5/MacPro5,1/9F24DF913B5F/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/05DE585A46>) |
| 8086:342d |           | Intel            | 7500/5520/5500/X58 I/O Hub I/OxAP... | 480   |            | [05DE585A46](<Desktop/Apple/MacPro5/MacPro5,1/9F24DF913B5F/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/05DE585A46>) |
| 8086:6f2c | 8086:0000 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 476   |            | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:3c2c | 8086:3c2c | Intel            | Xeon E5/Core i7 I/O APIC             | 370   |            | [DD5A66147D](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/05F06043C621/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/DD5A66147D>) |
| 8086:0e2c | 8086:0e2c | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 300   |            | [CA71A1B4D6](<Server/Supermicro/X9/X9DRH-7TF-7F-iTF-iF/EC8C275F9BA3/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/CA71A1B4D6>) |
| 8086:3c2c | 1043:84ef | Intel            | Xeon E5/Core i7 I/O APIC             | 156   |            | [19D479AA20](<Desktop/ASUSTek Computer/Rampage/Rampage IV FORMULA/E37343E0894F/UBUNTU-23.04/6.2.0-39-GENERIC/X86_64/19D479AA20>) |
| 1106:5364 |           | VIA Technologies | CN896/VN896/P4M900 I/O APIC Inter... | 118   |            | [861A2B8A1D](<Desktop/Foxconn/OEM/OEM/FC02A886F4A0/LINUXMINT-22/6.8.0-50-GENERIC/X86_64/861A2B8A1D>) |
| 8086:0e2c | 1043:84ef | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 90    |            | [382EC4FFCB](<Desktop/ASUSTek Computer/Rampage/Rampage IV EXTREME/9AB2C632EC6F/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/382EC4FFCB>) |
| 8086:2f2c | 1028:0617 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 86    |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:6f2c | 103c:21ea | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 75    |            | [34E5B43715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/07607C1620F7/DEBIAN-12/6.8.8-4-PVE/X86_64/34E5B43715>) |
| 8086:3c2c | 103c:18a8 | Intel            | Xeon E5/Core i7 I/O APIC             | 73    |            | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |
| 8086:3c2c | 1028:0497 | Intel            | Xeon E5/Core i7 I/O APIC             | 66    |            | [230E7069EA](<Desktop/Dell/Precision/Precision T3600/9F0EF57D3E16/FEDORA-40/6.11.4-201.FC40.X86_64/X86_64/230E7069EA>) |
| 1106:5327 |           | VIA Technologies | P4M890 I/O APIC Interrupt Controller | 65    |            | [79F2DC1F44](<Desktop/ASUSTek Computer/P5VD2-MX/P5VD2-MX SE/6CFB16D67B19/DEVUAN-5/6.1.0-28-AMD64/X86_64/79F2DC1F44>) |
| 8086:0e2c | 8086:0000 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 56    |            | [ECFA27B66D](<Desktop/Apple/MacPro6/MacPro6,1/F0AE965F0330/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/ECFA27B66D>) |
| 8086:2026 | 8086:0000 | Intel            | Sky Lake-E IOAPIC                    | 49    |            | [AF63B5BA1C](<Desktop/Hewlett-Packard/Z4/Z4 G4 Workstation/5CFDD07CE006/DEBIAN/6.12.6-AMD64/X86_64/AF63B5BA1C>) |
| 8086:2036 | 8086:0000 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 49    |            | [AF63B5BA1C](<Desktop/Hewlett-Packard/Z4/Z4 G4 Workstation/5CFDD07CE006/DEBIAN/6.12.6-AMD64/X86_64/AF63B5BA1C>) |
| 8086:2f2c | 1849:2f2c | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 49    |            | [E7C9CA40FA](<Desktop/ASRock/X99/X99 Extreme3/146BD814D95B/KDE-NEON-22.04/6.8.0-40-GENERIC/X86_64/E7C9CA40FA>) |
| 8086:2f2c | 1462:7885 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 48    |            | [9FF7B1C7A1](<Desktop/MSI/MS/MS-7885/DC2ED24074AF/UBUNTU-24.04/6.8.0-50-GENERIC/X86_64/9FF7B1C7A1>) |
| 8086:2026 | 1028:0738 | Intel            | Sky Lake-E IOAPIC                    | 46    |            | [C5943809D9](<Desktop/Dell/Precision/Precision 5820 Tower/AC79B5FA084D/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/C5943809D9>) |
| 8086:2036 | 1028:0738 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 46    |            | [C5943809D9](<Desktop/Dell/Precision/Precision 5820 Tower/AC79B5FA084D/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/C5943809D9>) |
| 8086:0e2c | 103c:18a8 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 41    |            | [62172231BE](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/A6B377D0F4D1/DEBIAN-12/6.8.8-2-PVE/X86_64/62172231BE>) |
| 8086:2f2c | 103c:21ea | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 39    |            | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:0e2c | 15d9:0636 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 38    |            | [86B4E152AD](<Server/Supermicro/X9/X9DRW/D2C6B0237967/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/86B4E152AD>) |
| 8086:3504 |           | Intel            | 6311ESB/6321ESB I/OxAPIC Interrup... | 36    |            | [BCE380880A](<Desktop/Apple/MacPro2/MacPro2,1/5B43734CD6F2/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/BCE380880A>) |
| 8086:3c2c | 1458:5000 | Intel            | Xeon E5/Core i7 I/O APIC             | 36    |            | [B3EF558527](<Desktop/Gigabyte Technology/X79/X79-UP4/D0FDFAED38DC/ULTRAMARINE-39/6.7.4-200.FC39.X86_64/X86_64/B3EF558527>) |
| 8086:0e2c | 1028:05d2 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 35    |            | [8154C94D2D](<Desktop/Dell/Precision/Precision T3610/1C227B01DB2C/ULTRAMARINE-40/6.10.4-200.FC40.X86_64/X86_64/8154C94D2D>) |
| 8086:2f2c | 1028:0618 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 34    |            | [E89C3FD1E0](<Desktop/Dell/Precision/Precision Tower 7810/5EE8A2BCE45A/UBUNTU-20.04/5.15.0-1059-ORACLE/X86_64/E89C3FD1E0>) |
| 1106:5336 |           | VIA Technologies | K8M890CE I/O APIC Interrupt Contr... | 30    |            | [06A8A5402F](<Desktop/MSI/MS/MS-7253/100489DC4331/MANJARO-24.2.0/6.11.10-2-MANJARO/X86_64/06A8A5402F>) |
| 8086:0e2c | 1458:5000 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 28    |            | [CE9F23992D](<Desktop/Gigabyte Technology/X79/X79-UD3/B06049E10C7B/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/CE9F23992D>) |
| 8086:6f2c | 1849:6f2c | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 28    |            | [168D757821](<Desktop/ASRock/X99/X99 Extreme4/F2B979B31843/UBUNTU-22.04/6.8.4-3-PVE/X86_64/168D757821>) |
| 1106:5308 | 1849:5308 | VIA Technologies | PT894 I/O APIC Interrupt Controller  | 27    |            | [469A404C91](<Desktop/ASRock/4/4CoreDual-SATA2/C4F6D8A146F0/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/469A404C91>) |
| 8086:0e2c | 152d:899b | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 25    |            | [7E09CCDA22](<Server/ETegro Technologies/Hyperion/Hyperion RS125 G4/5259A72AB62F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/7E09CCDA22>) |
| 8086:2026 | 17aa:1036 | Intel            | Sky Lake-E IOAPIC                    | 25    |            | [315F389132](<Desktop/Lenovo/ThinkStation/ThinkStation P520 30BFS4GK0A/C432E0CC3C47/ZORIN-17/6.8.0-49-GENERIC/X86_64/315F389132>) |
| 8086:2036 | 17aa:1036 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 25    |            | [315F389132](<Desktop/Lenovo/ThinkStation/ThinkStation P520 30BFS4GK0A/C432E0CC3C47/ZORIN-17/6.8.0-49-GENERIC/X86_64/315F389132>) |
| 8086:3c2c | 8086:4953 | Intel            | Xeon E5/Core i7 I/O APIC             | 23    |            | [4B26BC3324](<Desktop/Intel/DX79TO/DX79TO AAG28805-402/BEA03539854D/ZORIN-17/6.8.0-49-GENERIC/X86_64/4B26BC3324>) |
| 8086:3c2c | 1849:3c2c | Intel            | Xeon E5/Core i7 I/O APIC             | 22    |            | [5360F41672](<Desktop/ASRock/X79/X79 Extreme4/91E7106AFD63/MAGEIA-9/6.6.52-DESKTOP-1.MGA9/X86_64/5360F41672>) |
| 8086:6f2c | 1028:0617 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 22    |            | [36A5D324C6](<Desktop/Dell/Precision/Precision Tower 5810/C7D9A4DE0C7E/RHEL-9/5.14.0-503.14.1.EL9_5.X86_64/X86_64/36A5D324C6>) |
| 8086:2026 | 1590:18a9 | Intel            | Sky Lake-E IOAPIC                    | 21    |            | [D9F97B2071](<Server/HPE/ProLiant/ProLiant DL380 Gen10/6D60567E7E8D/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/D9F97B2071>) |
| 8086:2036 | 1590:18a9 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 21    |            | [D9F97B2071](<Server/HPE/ProLiant/ProLiant DL380 Gen10/6D60567E7E8D/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/D9F97B2071>) |
| 8086:3c2c | 1028:0496 | Intel            | Xeon E5/Core i7 I/O APIC             | 20    |            | [FCE4597AD2](<Desktop/Dell/Precision/Precision T5600/CD5FD08D4152/KUBUNTU-24.10/6.11.0-12-GENERIC/X86_64/FCE4597AD2>) |
| 8086:6f2c | 15d9:0821 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 19    |            | [34DDE21779](<Server/transtec/CALLEO/CALLEO/ABD07D26A4AA/RHCOS-4.16/5.14.0-427.24.1.EL9_4.X86_64/X86_64/34DDE21779>) |
| 8086:6f2c | 15d9:0911 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 19    |            | [E33D406712](<Desktop/Inspur/SA5248/SA5248M4/624F01ED21C2/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/E33D406712>) |
| 8086:0e2c | 1028:05d3 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 18    |            | [B20D2D0198](<Desktop/Dell/Precision/Precision T5610/93F75649C56F/BAZZITE-41/6.11.10-304.BAZZITE.FC41.X86_64/X86_64/B20D2D0198>) |
| 8086:3c2c | 17aa:1026 | Intel            | Xeon E5/Core i7 I/O APIC             | 18    |            | [319423B279](<Desktop/Lenovo/ThinkStation/ThinkStation S30 43518H6/A99944236890/DEBIAN/6.1.0-26-AMD64/X86_64/319423B279>) |
| 8086:0e2c | 1043:84f0 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 17    |            | [E805BE0AAC](<Server/Kraftway/GEG/GEG/C4E325834440/DEBIAN-12/6.1.0-27-AMD64/X86_64/E805BE0AAC>) |
| 8086:3c2c | 1028:0495 | Intel            | Xeon E5/Core i7 I/O APIC             | 17    |            | [2AF24C92CD](<Desktop/Dell/Precision/Precision T7600/A42466AF5FDA/OPENMANDRIVA-23.08/6.4.11-DESKTOP-1OMV2390/X86_64/2AF24C92CD>) |
| 8086:6f2c | 15d9:0844 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 17    |            | [6AC9EF200B](<Desktop/Silicon Mechanics/Rackform/Rackform U633.v6/E42F237DB52E/DEBIAN-12/6.1.0-28-AMD64/X86_64/6AC9EF200B>) |

### Pic (io-apic) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:7451 | 1022:7450 | AMD              | AMD-8131 PCI-X IOAPIC                | 4     |            | [A94946D561](<Desktop/Hewlett-Packard/xw9300/xw9300 Workstation/796D0561C4B4/LUBUNTU-20.04/5.8.0-53-GENERIC/X86_64/A94946D561>) |
| 1022:7451 | 1022:7451 | AMD              | AMD-8131 PCI-X IOAPIC                | 1     |            | [18B25AC51A](<Server/TYAN Computer/S/S4882/84BBA0EA52AC/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/18B25AC51A>) |
| 1022:7451 | 10f1:2895 | AMD              | AMD-8131 PCI-X IOAPIC                | 1     |            | [768571B831](<Server/TYAN Computer/S/S2895/4B5DFCDB09B6/LINUXMINT-20/5.4.0-58-GENERIC/X86_64/768571B831>) |
| 1022:7459 | 1022:7459 | AMD              | AMD-8132 PCI-X IOAPIC                | 1     |            | [68059DB0EE](<Desktop/Supermicro/H8/H8QM8/1DAD0B606684/KDE-NEON-20.04/5.11.0-25-GENERIC/X86_64/68059DB0EE>) |
| 1104:0844 | 1043:89ff | RasterOps        | PIC                                  | 1     |            | [5C55046F50](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/2609B3602999/PARROT-4.11/5.14.0-9PARROT1-AMD64/X86_64/5C55046F50>) |

### Power pc (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1957:c006 | 1a56:1201 | Freescale Sem... | MPC8308                              | 11    |            | [73EF034954](<Desktop/Gigabyte Technology/G1/G1.Guerrilla/3448AB75F67E/MANJARO/6.11.2-4-MANJARO/X86_64/73EF034954>) |
| 1957:00b6 | 1a56:1103 | Freescale Sem... | MPC8314E                             | 3     |            | [AC26E59E63](<Desktop/ASRock/X58/X58 Extreme/5C2A22D48369/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/AC26E59E63>) |
| 1957:00b6 | 1a56:1101 | Freescale Sem... | MPC8314E                             | 2     |            | [9ACDB88F98](<Desktop/MSI/MS/MS-7750/8196B511C2BF/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/9ACDB88F98>) |
| 1957:0085 | 110a:4046 | Freescale Sem... | MPC8347 PBGA                         | 1     |            | [60A7685D8D](<Desktop/SIEMENS/SIMATIC/SIMATIC IPC547D/A5B87CC67308/UBUNTU-18.04/4.15.0-20-GENERIC/X86_64/60A7685D8D>) |

### Processing accelerators (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:7d1d | 1043:20bf | Intel            | Meteor Lake NPU                      | 64    | intel_vpu  | [7B915687FC](<Notebook/ASUSTek Computer/ASUS/ASUS Vivobook Pro 15 N6506MJ_Q543MJ/456D11CB3487/OPENSUSE-LEAP-15.6/6.4.0-150600.23.30-DEFAULT/X86_64/7B915687FC>) |
| 8086:7d1d | 17aa:231e | Intel            | Meteor Lake NPU                      | 24    | intel_vpu  | [AE6FBEFD79](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon Gen 12 21KC002QAU/AC9C95A418D7/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/AE6FBEFD79>) |
| 8086:7d1d | 17aa:50e1 | Intel            | Meteor Lake NPU                      | 22    | intel_vpu  | [32CAFE357C](<Notebook/Lenovo/ThinkPad/ThinkPad E16 Gen 2 21MA000BGR/53CCCBC359B7/LINUXMINT-22/6.8.0-49-GENERIC/X86_64/32CAFE357C>) |
| 8086:7d1d | 17aa:380b | Intel            | Meteor Lake NPU                      | 16    | intel_vpu  | [E72190A7D6](<Notebook/Lenovo/Yoga/Yoga Pro 9 16IMH9 83DN/5FEA2464BE41/KUBUNTU-24.10/6.11.0-8-GENERIC/X86_64/E72190A7D6>) |
| 8086:7d1d | 1d72:2307 | Intel            | Meteor Lake NPU                      | 16    | intel_vpu  | [677A093651](<Notebook/XIAOMI/Redmi/Redmi Book Pro 14 2024/703FC3395E3B/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/677A093651>) |
| 8086:643e | 1043:20bf | Intel            | Lunar Lake NPU                       | 13    | intel_vpu  | [689364573C](<Notebook/ASUSTek Computer/ASUS/ASUS Zenbook S 14 UX5406SA_UX5406SA/2D2F3DC76EB7/KUBUNTU-24.10/6.12.3-061203-GENERIC/X86_64/689364573C>) |
| 8086:7d1d | 19e5:3e70 | Intel            | Meteor Lake NPU                      | 13    | intel_vpu  | [7EF14DBA16](<Notebook/HUAWEI/VGHH-XX/VGHH-XX/DE66551D8404/ARCH-ROLLING/6.12.6-ARCH1-1/X86_64/7EF14DBA16>) |
| 8086:7d1d | 19e5:3e71 | Intel            | Meteor Lake NPU                      | 13    | intel_vpu  | [00D586DA79](<Notebook/HUAWEI/FLMH-XX/FLMH-XX/EBF827B5B03A/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/00D586DA79>) |
| 8086:7d1d | 1025:171f | Intel            | Meteor Lake NPU                      | 12    | intel_vpu  | [D07BF77AA4](<Notebook/Acer/Swift/Swift SFG14-72/8994EEEBB3B2/UBUNTU-24.10/6.11.0-13-GENERIC/X86_64/D07BF77AA4>) |
| 8086:7d1d | 1028:0c87 | Intel            | Meteor Lake NPU                      | 11    | intel_vpu  | [914BE0C9E8](<Notebook/Dell/XPS/XPS 13 9340/39F11093D638/UBUNTU-22.04/6.8.0-49-GENERIC/X86_64/914BE0C9E8>) |
| 8086:7d1d | 1028:0cc7 | Intel            | Meteor Lake NPU                      | 11    | intel_vpu  | [EE16CC2886](<Notebook/Dell/Precision/Precision 5490/01D6061690B5/ARCH-ROLLING/6.12.4-ARCH1-1/X86_64/EE16CC2886>) |
| 8086:7d1d | 1d72:2309 | Intel            | Meteor Lake NPU                      | 11    | intel_vpu  | [F10CB62820](<Notebook/XIAOMI/Redmi/Redmi Book Pro 16 2024/B854F1949F3A/ROSA-12.5.1/6.9.8.XM1-ML2.K.1-XANMOD-ROSA2021.1-X86_64/X86_64/F10CB62820>) |
| 8086:7d1d | 1028:0c6b | Intel            | Meteor Lake NPU                      | 9     | intel_vpu  | [E2339B154A](<Notebook/Dell/XPS/XPS 14 9440/200088F74C61/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/E2339B154A>) |
| 8086:7d1d | 17aa:2327 | Intel            | Meteor Lake NPU                      | 9     | intel_vpu  | [DE8CFA5271](<Notebook/Lenovo/ThinkPad/ThinkPad T16 Gen 3 21MN005RUS/AAD3892460CB/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.12.6-1-DEFAULT/X86_64/DE8CFA5271>) |
| 8086:7d1d | 17aa:3812 | Intel            | Meteor Lake NPU                      | 9     | intel_vpu  | [EA461F99C2](<Notebook/Lenovo/Yoga/Yoga Pro 7 14IMH9 83E2/95AA8C81A334/UBUNTU-24.10/6.11.0-13-GENERIC/X86_64/EA461F99C2>) |
| 8086:7d1d | 17aa:3846 | Intel            | Meteor Lake NPU                      | 9     | intel_vpu  | [C80DDE07D0](<Notebook/Lenovo/ThinkBook/ThinkBook 16 G6+ IMH 21LE/769536EE0B76/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/C80DDE07D0>) |
| 8086:7d1d | 1028:0c62 | Intel            | Meteor Lake NPU                      | 8     | intel_vpu  | [58D3A3677B](<Notebook/Dell/XPS/XPS 16 9640/169585507813/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/58D3A3677B>) |
| 8086:7d1d | 1028:0cc1 | Intel            | Meteor Lake NPU                      | 8     | intel_vpu  | [41B698BBA3](<Notebook/Dell/Latitude/Latitude 7450/9197F2214930/OL-9.5/5.14.0-503.16.1.EL9_5.X86_64/X86_64/41B698BBA3>) |
| 8086:7d1d | 1028:0cc8 | Intel            | Meteor Lake NPU                      | 8     | intel_vpu  | [5219297C0D](<Notebook/Dell/Precision/Precision 5690/EA7396EE0136/NIXOS-24.11/6.6.67/X86_64/5219297C0D>) |
| 8086:7d1d | 17aa:3802 | Intel            | Meteor Lake NPU                      | 8     | intel_vpu  | [79B9B179EF](<Notebook/Lenovo/ThinkBook/ThinkBook 16 G7 IML 21MS/8E22EE39311F/UBUNTU-24.04/6.8.0-50-GENERIC/X86_64/79B9B179EF>) |
| 8086:7d1d | 1d05:1382 | Intel            | Meteor Lake NPU                      | 8     | intel_vpu  | [A950475B3C](<Notebook/TUXEDO/InfinityBook/InfinityBook Pro Intel Gen9/C549ACEFD62A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/A950475B3C>) |
| 8086:7d1d | 1028:0cbb | Intel            | Meteor Lake NPU                      | 7     | intel_vpu  | [E1C2DD2DCE](<Notebook/Dell/Precision/Precision 3591/8E17E2BC6459/DEBIAN-12/6.1.0-28-AMD64/X86_64/E1C2DD2DCE>) |
| 8086:7d1d | 144d:ca07 | Intel            | Meteor Lake NPU                      | 7     | intel_vpu  | [7E994928CF](<Notebook/Samsung Electronics/940/940XGK/CB274195F873/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/7E994928CF>) |
| 8086:7d1d | 17aa:380c | Intel            | Meteor Lake NPU                      | 7     | intel_vpu  | [E237CB84ED](<Notebook/Lenovo/ThinkBook/ThinkBook 13x G4 IMH 21KR/6070380C6F37/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/E237CB84ED>) |
| 8086:7d1d | 17aa:3811 | Intel            | Meteor Lake NPU                      | 7     | intel_vpu  | [1482125B7F](<Notebook/Lenovo/IdeaPad/IdeaPad Pro 5 14IMH9 83D2/B291FCFFB28A/UBUNTUDDE-24.04/6.8.0-49-GENERIC/X86_64/1482125B7F>) |
| 8086:7d1d | 17aa:3813 | Intel            | Meteor Lake NPU                      | 7     | intel_vpu  | [3841765926](<Convertible/Lenovo/Yoga/Yoga 9 2-in-1 14IMH9 83AC/E1193337DB34/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/3841765926>) |
| 8086:7d1d | 17aa:50e9 | Intel            | Meteor Lake NPU                      | 7     | intel_vpu  | [F1A3B79F94](<Notebook/Lenovo/ThinkPad/ThinkPad P14s Gen 5 21G2CTO1WW/6B49AC2E5F66/FEDORA-40/6.11.10-200.FC40.X86_64/X86_64/F1A3B79F94>) |
| 8086:7d1d | 8086:7270 | Intel            | Meteor Lake NPU                      | 7     | intel_vpu  | [28E079A0DB](<Mini Pc/AZW/GTi/GTi14/BF2DD5B4D222/MX-23/6.11.10-1-LIQUORIX-AMD64/X86_64/28E079A0DB>) |
| 8086:7d1d | 1028:0cb9 | Intel            | Meteor Lake NPU                      | 6     | intel_vpu  | [EE6572422C](<Notebook/Dell/Latitude/Latitude 5550/5D00010C4927/UBUNTU-24.10/6.11.0-13-GENERIC/X86_64/EE6572422C>) |
| 8086:7d1d | 103c:8c15 | Intel            | Meteor Lake NPU                      | 6     | intel_vpu  | [9E9A469284](<Convertible/Hewlett-Packard/Spectre/Spectre x360 2-in-1 Laptop 14t-eu000/6CD8DA66DC8B/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9E9A469284>) |
| 8086:7d1d | 103c:8c26 | Intel            | Meteor Lake NPU                      | 6     | intel_vpu  | [759B2993D7](<Convertible/Hewlett-Packard/Elite/Elite x360 830 13 inch G11 2-in-1 Notebook PC/59493A3B3413/ROCKY-9.5/5.14.0-503.14.1.EL9_5.X86_64/X86_64/759B2993D7>) |
| 8086:7d1d | 17aa:380f | Intel            | Meteor Lake NPU                      | 6     | intel_vpu  | [1F7E53A59E](<Convertible/Lenovo/Yoga/Yoga 7 2-in-1 14IML9 83DJ/38BFA92704CB/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/1F7E53A59E>) |
| 8086:643e | 1028:0cc9 | Intel            | Lunar Lake NPU                       | 5     | intel_vpu  | [896EB3972D](<Notebook/Dell/XPS/XPS 13 9350/C0FA87081B1D/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/896EB3972D>) |
| 8086:7d1d | 103c:8c87 | Intel            | Meteor Lake NPU                      | 5     | intel_vpu  | [97A21CD2B9](<Notebook/Hewlett-Packard/EliteBook/EliteBook 660 16 inch G11 Notebook PC/6A71E9297A1E/DEBIAN-12/6.1.0-28-AMD64/X86_64/97A21CD2B9>) |
| 8086:7d1d | 144d:c1d8 | Intel            | Meteor Lake NPU                      | 5     | intel_vpu  | [020D5B8C25](<Notebook/Samsung Electronics/960/960XGL/6DE2434422CF/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/020D5B8C25>) |
| 8086:7d1d | 1558:a741 | Intel            | Meteor Lake NPU                      | 5     |            | [FDD2309E0B](<Notebook/Notebook/V5/V5xTNC_TND_TNE/7A7B2DCFAFB6/DTS-DISTRO-2.0.0/6.6.21-YOCTO-STANDARD/X86_64/FDD2309E0B>) |
| 8086:7d1d | 17aa:380e | Intel            | Meteor Lake NPU                      | 5     | intel_vpu  | [EFA06F4775](<Notebook/Lenovo/Yoga/Yoga Slim 7 14IMH9 83CV/3C4B36BCC0F0/DEBIAN/6.12.6-AMD64/X86_64/EFA06F4775>) |
| 8086:7d1d | 1028:0c91 | Intel            | Meteor Lake NPU                      | 4     | intel_vpu  | [5FE417E971](<Notebook/Alienware/m16/m16 R2/4BD0637A6228/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/5FE417E971>) |
| 8086:7d1d | 1028:0c93 | Intel            | Meteor Lake NPU                      | 4     | intel_vpu  | [B0C9087A18](<Notebook/Dell/Inspiron/Inspiron 14 Plus 7440/C3C1AB1B873D/ALPINE-3.15.4/6.8.0-49-GENERIC/X86_64/B0C9087A18>) |
| 8086:7d1d | 103c:8c17 | Intel            | Meteor Lake NPU                      | 4     | intel_vpu  | [EC52AE183B](<Convertible/Hewlett-Packard/Spectre/Spectre x360 2-in-1 Laptop 16-aa0xxx/C6E4AC3F61C0/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/EC52AE183B>) |
| 8086:7d1d | 103c:8c66 | Intel            | Meteor Lake NPU                      | 4     | intel_vpu  | [22428153EA](<Convertible/Hewlett-Packard/ENVY/ENVY x360 2-in-1 Laptop 16-ac0xxx/48AF4FEC9097/SLACKWARE-15.0/6.11.6/X86_64/22428153EA>) |
| 8086:7d1d | 1043:88c8 | Intel            | Meteor Lake NPU                      | 4     | intel_vpu  | [517ED86059](<Mini Pc/ASUSTek Computer/NUC14/NUC14RVK-B/460C79B95F2B/DEBIAN/6.11.4-AMD64/X86_64/517ED86059>) |
| 8086:7d1d | 144d:c892 | Intel            | Meteor Lake NPU                      | 4     | intel_vpu  | [E2A7E5A12A](<Convertible/Samsung Electronics/960/960QGK/104BA094FD05/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E2A7E5A12A>) |
| 8086:7d1d | 17aa:3847 | Intel            | Meteor Lake NPU                      | 4     | intel_vpu  | [455AF071A7](<Notebook/Lenovo/IdeaPad/IdeaPad Slim 5 14IMH9 83DA/A25C392C7FFE/UBUNTU-24.10/6.11.0-13-GENERIC/X86_64/455AF071A7>) |
| 10ee:5000 | 10ee:000e | Xilinx           | Alveo U200 XDMA Platform             | 3     | xclmgmt    | [AE0B8A9E36](<Server/ASUSTek Computer/WS-C621E-SAGE/WS-C621E-SAGE Series/E269F7C9BB0F/UBUNTU-22.04/5.19.0-50-GENERIC/X86_64/AE0B8A9E36>) |
| 10ee:5001 | 10ee:000e | Xilinx           | Processing accelerators              | 3     | xocl       | [AE0B8A9E36](<Server/ASUSTek Computer/WS-C621E-SAGE/WS-C621E-SAGE Series/E269F7C9BB0F/UBUNTU-22.04/5.19.0-50-GENERIC/X86_64/AE0B8A9E36>) |
| 1db7:dc24 |           | Phytium Techn... | NPU Controller [X100 Series]         | 3     |            | [497220C5DD](<Server/Phytium/D/D2000/E78D0AE566AE/ATZ-11.6/5.10.0-20-ARM64/AARCH64/497220C5DD>) |
| 8086:643e | 103c:8cde | Intel            | Lunar Lake NPU                       | 3     | intel_vpu  | [5F2A3C878A](<Convertible/Hewlett-Packard/OmniBook/OmniBook Ultra Flip Laptop 14-fh0xxx/76D672E0E745/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/5F2A3C878A>) |
| 8086:643e | 1462:1464 | Intel            | Lunar Lake NPU                       | 3     | intel_vpu  | [E0EF8014CC](<Notebook/MSI/Prestige/Prestige 13 AI+ Evo A2VMG/774EA8A43370/UBUNTUSTUDIO-24.10/6.11.0-13-GENERIC/X86_64/E0EF8014CC>) |
| 8086:7d1d | 1028:0c63 | Intel            | Meteor Lake NPU                      | 3     | intel_vpu  | [2928B6CEB0](<Notebook/Dell/XPS/XPS 16 9640/D8EE0FB191DB/UBUNTU-24.04/6.9.9-060909-GENERIC/X86_64/2928B6CEB0>) |

### Rf controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:7305 | 10ec:7305 | Realtek Semic... | UWB Radio Device                     | 3     | whci, w... | [BB018988D6](<Notebook/Fujitsu Siemens/AMILO/AMILO Xi 3670/72F931A40CE0/UBUNTU-CORE-18/5.19.0-35-GENERIC/X86_64/BB018988D6>) |
| 10ee:9038 | 10ee:0007 | Xilinx           | RF controller                        | 1     | sdr        | [D617CC1B4B](<Server/HOU/Whitestone-A/Whitestone-A PVT 5262C5330051/5CE342FC93F6/UBUNTU-22.04/5.15.0-122-GENERIC/X86_64/D617CC1B4B>) |

### Scsi storage controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1af4:1042 | 1af4:1100 | Red Hat          | Virtio 1.0 block device              | 11    | virtio_pci | [79EC6F96E4](<Desktop/Bochs/Others/Others/BE32418C1D7C/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/79EC6F96E4>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14e4:16bc | 14e4:0000 | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 1833  | sdhci_pci  | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 1217:8621 | 1e44:1776 | O2 Micro         | SD/MMC Card Reader Controller        | 1746  | sdhci_pci  | [DFF6A36E92](<Notebook/Valve/Galileo/Galileo/3D6CF2B6536D/STEAMOS-3.6.20/6.5.0-VALVE22-1-NEPTUNE-65-G9A338ED8A75E/X86_64/DFF6A36E92>) |
| 8086:31cc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1408  | sdhci_pci  | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:31d0 | 8086:7270 | Intel            | Celeron/Pentium Silver SD Host Co... | 1288  | sdhci_pci  | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 963   | sdhci_pci  | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 1217:8621 | 1217:0002 | O2 Micro         | SD/MMC Card Reader Controller        | 755   | sdhci_pci  | [370EBBC151](<Notebook/Lenovo/IdeaPad/IdeaPad Slim 5 14AHP9 83DB/53383E7902F5/POP!_OS-24.04/6.9.3-76060903-GENERIC/X86_64/370EBBC151>) |
| 8086:5aca | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 722   | sdhci_pci  | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 14e4:16bc | 1025:0647 | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 626   | sdhci_pci  | [1BE16A65FF](<Notebook/Acer/Aspire/Aspire E1-571/5E9809648D6E/ARCH-ROLLING/6.12.8-ARCH1-1/X86_64/1BE16A65FF>) |
| 8086:5ad0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 584   | sdhci_pci  | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 8086:9d2d | 8086:9d2d | Intel            | Sunrise Point-LP Secure Digital I... | 411   | sdhci_pci  | [4AEF1F789F](<Notebook/Google/Caroline/Caroline/32DCDB645978/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/4AEF1F789F>) |
| 1180:0822 | 17aa:20c8 | Ricoh            | R5C822 SD/SDIO/MMC/MS/MSPro Host ... | 394   | sdhci_pci  | [7B16EB5229](<Notebook/Lenovo/ThinkPad/ThinkPad T500 2241WKY/6679B8A41DC3/ZORIN-17/6.8.0-50-GENERIC/X86_64/7B16EB5229>) |
| 14e4:16bc | 1025:0504 | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 377   | sdhci_pci  | [68404201A9](<Notebook/Acer/Aspire/Aspire 5750G/8E9ECAF23BC7/ZORIN-17/6.8.0-50-GENERIC/X86_64/68404201A9>) |
| 197b:2381 | 1043:1a07 | JMicron Techn... | Standard SD Host Controller          | 345   | sdhci_pci  | [35095B2B4C](<Notebook/ASUSTek Computer/K42/K42JY/7D0DF9CB1CBF/DEBIAN-12/6.1.0-28-AMD64/X86_64/35095B2B4C>) |
| 17a0:9755 | 1043:202f | Genesys Logic    | GL9755 SD Host Controller            | 320   | sdhci_pci  | [7B915687FC](<Notebook/ASUSTek Computer/ASUS/ASUS Vivobook Pro 15 N6506MJ_Q543MJ/456D11CB3487/OPENSUSE-LEAP-15.6/6.4.0-150600.23.30-DEFAULT/X86_64/7B915687FC>) |
| 1217:8221 | 1028:0534 | O2 Micro         | OZ600FJ0/OZ900FJ0/OZ600FJS SD/MMC... | 291   | sdhci_pci  | [860E215DAF](<Notebook/Dell/Latitude/Latitude E6430/A0E982126F70/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/860E215DAF>) |
| 1217:8221 | 1028:0493 | O2 Micro         | OZ600FJ0/OZ900FJ0/OZ600FJS SD/MMC... | 290   | sdhci_pci  | [46C2760E4E](<Notebook/Dell/Latitude/Latitude E6420/27A84812735F/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/46C2760E4E>) |
| 8086:31cc | 8086:31cc | Intel            | Celeron/Pentium Silver Processor ... | 282   | sdhci_pci  | [DAE997FEE3](<Notebook/Others/Others/Others/8EB9EBE3F85A/LUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/DAE997FEE3>) |
| 14e4:16bc | 1025:0775 | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 272   | sdhci_pci  | [E825292593](<Notebook/Acer/Aspire/Aspire E1-572/F3FEBABE531A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E825292593>) |
| 1180:e822 | 1028:040a | Ricoh            | MMC/SD Host Controller               | 255   | sdhci_pci  | [CE431D6DEF](<Notebook/Dell/Latitude/Latitude E6410/008BAA37A996/ZORIN-17/6.8.0-50-GENERIC/X86_64/CE431D6DEF>) |
| 1180:e822 | 104d:9071 | Ricoh            | MMC/SD Host Controller               | 244   | sdhci_pci  | [B2006D7959](<Notebook/Sony/VPCEB24/VPCEB24FX/9086550513E1/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/B2006D7959>) |
| 8086:2294 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 244   | sdhci_pci  | [07D137B1C9](<Notebook/Google/Cyan/Cyan/7764460C686F/ARCO-ROLLING/6.11.7-ZEN1-1-ZEN/X86_64/07D137B1C9>) |
| 14e4:16bc | 14e4:96bc | Broadcom Limited | BCM57765/57785 SDXC/MMC Card Reader  | 242   | sdhci_pci  | [8485C9B6A3](<All In One/Apple/iMac14/iMac14,2/DE6A385E2C03/ARCH-ROLLING/6.10.14-273-TKG-EEVDF/X86_64/8485C9B6A3>) |
| 1022:7806 | 1022:7806 | AMD              | FCH SD Flash Controller              | 226   | sdhci_pci  | [579117E933](<Notebook/Samsung Electronics/305V4/305V4A-305V5A/780A6550E89A/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/579117E933>) |
| 1180:0822 | 1028:0233 | Ricoh            | R5C822 SD/SDIO/MMC/MS/MSPro Host ... | 226   | sdhci_pci  | [D5DCFBC839](<Notebook/Dell/Latitude/Latitude E6400/429F04A48EEB/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/D5DCFBC839>) |
| 1022:7813 | 17aa:3801 | AMD              | FCH SD Flash Controller              | 221   | sdhci_pci  | [AC16ADA090](<Notebook/Lenovo/G40-45/G40-45 80E1/9A279D34AA5C/MANJARO-24.2.1/5.15.173-1-MANJARO/X86_64/AC16ADA090>) |
| 197b:2391 | 103c:161c | JMicron Techn... | Standard SD Host Controller          | 214   | sdhci_pci  | [0A8D680CF0](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8460p/636CD01ADFA4/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/0A8D680CF0>) |
| 8086:2296 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 214   | sdhci_pci  | [07D137B1C9](<Notebook/Google/Cyan/Cyan/7764460C686F/ARCO-ROLLING/6.11.7-ZEN1-1-ZEN/X86_64/07D137B1C9>) |
| 197b:2391 | 103c:179b | JMicron Techn... | Standard SD Host Controller          | 203   | sdhci_pci  | [63E91F06EF](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8470p/C1D8318F6F12/BLACKPANTHER-OS-18.1/5.15.85-DESKTOP-1BP/X86_64/63E91F06EF>) |
| 1217:8520 | 1028:05cb | O2 Micro         | SD/MMC Card Reader Controller        | 187   | sdhci_pci  | [E25716EB4B](<Notebook/Dell/Latitude/Latitude E7440/6D8BFD9B5EF2/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/E25716EB4B>) |
| 8086:9d2b | 8086:9d2b | Intel            | Skylake-U/Y SCC: eMMC                | 185   | sdhci_pci  | [165F302BE9](<Notebook/Google/Chell/Chell/D809DC2934A8/DEBIAN/6.12.6-AMD64/X86_64/165F302BE9>) |
| 8086:9df5 | 8086:7270 | Intel            | BayHubTech Integrated SD controller  | 184   | sdhci_pci  | [01E6C282DA](<Notebook/AZW/GTi/GTi/35F650C71804/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/01E6C282DA>) |
| 104c:803c | 1025:011f | Texas Instrum... | PCIxx12 SDA Standard Compliant SD... | 180   | sdhci_pci  | [864E664760](<Notebook/Acer/Extensa/Extensa 5220/847E4B65162A/LMDE-6/6.1.0-28-686/I686/864E664760>) |
| 197b:2391 | 103c:17f6 | JMicron Techn... | Standard SD Host Controller          | 171   | sdhci_pci  | [0646F227A6](<Notebook/Hewlett-Packard/ProBook/ProBook 4540s/E16F0E397D33/SIDUCTION/6.12.7-1-SIDUCTION-AMD64/X86_64/0646F227A6>) |
| 1217:8520 | 1028:05be | O2 Micro         | SD/MMC Card Reader Controller        | 164   | sdhci_pci  | [4198198679](<Notebook/Dell/Latitude/Latitude E6540/94FAB7E724C4/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/4198198679>) |
| 10ec:5209 | 10ec:5209 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 159   | rtsx_pci   | [BB26B30A98](<Notebook/Hewlett-Packard/Pavilion/Pavilion g4/0B286D85C2E3/ZORIN-17/6.8.0-49-GENERIC/X86_64/BB26B30A98>) |
| 1217:8621 | 17aa:5068 | O2 Micro         | SD/MMC Card Reader Controller        | 157   | sdhci_pci  | [220C6D82F3](<Notebook/Lenovo/ThinkPad/ThinkPad E580 20KTS0TF00/16D343F59ED9/LINUXMINT-22.1/6.8.0-51-GENERIC/X86_64/220C6D82F3>) |
| 1217:8520 | 1028:062e | O2 Micro         | SD/MMC Card Reader Controller        | 156   | sdhci_pci  | [03B4F85891](<Notebook/Dell/Latitude/Latitude E7450/1AB2CC232E55/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/03B4F85891>) |
| 8086:4dc4 | 8086:7270 | Intel            | Jasper Lake eMMC Controller          | 152   | sdhci_pci  | [BC8E7EDAC4](<Notebook/Google/Cret/Cret/3C9CF67F812D/KUBUNTU-24.10/6.11.0-13-GENERIC/X86_64/BC8E7EDAC4>) |
| 17a0:9755 | 8086:2081 | Genesys Logic    | GL9755 SD Host Controller            | 149   | sdhci_pci  | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 1217:8520 | 1028:05bd | O2 Micro         | SD/MMC Card Reader Controller        | 148   | sdhci_pci  | [8EF2131731](<Notebook/Dell/Latitude/Latitude E6440/A14DF7303D79/MX-23/6.1.0-28-AMD64/X86_64/8EF2131731>) |
| 8086:9d2b | 8086:7270 | Intel            | Skylake-U/Y SCC: eMMC                | 148   | sdhci_pci  | [BD56FC3A14](<Notebook/Hewlett-Packard/Nami/Nami/5AED72819B0E/FEDORA-41/6.13.0-0.RC4.20241227GITD6EF8B40D075.39.FC42.X86_64/X86_64/BD56FC3A14>) |
| 1217:8321 | 1028:0494 | O2 Micro         | OZ600RJ0/OZ900RJ0/OZ600RJS SD/MMC... | 147   | sdhci_pci  | [C3A5CF03A9](<Notebook/Dell/Latitude/Latitude E6520/E350D4696CE5/FEDORA-41/6.12.4-200.FC41.X86_64/X86_64/C3A5CF03A9>) |
| 1180:0822 | 1028:022f | Ricoh            | R5C822 SD/SDIO/MMC/MS/MSPro Host ... | 145   | sdhci_pci  | [89A2A2261A](<Notebook/Dell/Inspiron/Inspiron 1525/C0BA8A575BF5/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/89A2A2261A>) |
| 8086:54c4 |           | Intel            | Alder Lake-N SD Host Controller      | 145   | sdhci_pci  | [537A11AE44](<Desktop/PELADN/WI/WI-6/A87F09289266/LMDE-6/6.1.0-28-AMD64/X86_64/537A11AE44>) |
| 8086:4dc4 |           | Intel            | Jasper Lake eMMC Controller          | 144   | sdhci_pci  | [8D772F9E5A](<Notebook/UNOWHY/Y13/Y13G113S4EI/23A28EB0728F/DEBIAN-12/6.1.0-28-AMD64/X86_64/8D772F9E5A>) |
| 197b:2391 | 103c:167c | JMicron Techn... | Standard SD Host Controller          | 135   | sdhci_pci  | [0B185E0E1F](<Notebook/Hewlett-Packard/ProBook/ProBook 4730s/699F0DC1E65F/UBUNTU-22.04/6.5.0-35-GENERIC/X86_64/0B185E0E1F>) |
| 1217:8520 | 1043:202f | O2 Micro         | SD/MMC Card Reader Controller        | 131   | sdhci_pci  | [39F2B622BF](<Notebook/ASUSTek Computer/ROG/ROG Zephyrus G14 GA402RJ/0DDF8DCE97E0/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/39F2B622BF>) |
| 1217:8520 | 17aa:2211 | O2 Micro         | SD/MMC Card Reader Controller        | 131   | sdhci_pci  | [6F758495B3](<Notebook/Lenovo/ThinkPad/ThinkPad W541 20EGS1FB00/3AD5035804BF/ARCH-ROLLING/6.12.4-ARCH1-1/X86_64/6F758495B3>) |
| 1217:8620 | 1217:0002 | O2 Micro         | Integrated MMC/SD Controller         | 129   | sdhci_pci  | [B8F7C2D75A](<Notebook/Google/Treeya/Treeya/8FA4145A1303/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/B8F7C2D75A>) |
| 17a0:9755 | 17a0:9755 | Genesys Logic    | GL9755 SD Host Controller            | 128   | sdhci_pci  | [A8EF875C26](<Notebook/Dell/Latitude/Latitude 5530/B1F1312B081E/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/A8EF875C26>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a324 | 8086:7270 | Intel            | Cannon Lake PCH SPI Controller       | 1266  | spi_int... | [639EB0E4FC](<Desktop/Gigabyte Technology/H370M/H370M D3H GSM/D391F95DF729/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/639EB0E4FC>) |
| 8086:a324 | 1043:8694 | Intel            | Cannon Lake PCH SPI Controller       | 826   | spi_int... | [D6E8F1EE6C](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-P/DD926E3C669B/LMDE-6/6.11.10+BPO-AMD64/X86_64/D6E8F1EE6C>) |
| 8086:9ce6 | 8086:9ce6 | Intel            | Wildcat Point-LP Serial IO GSPI C... | 691   | spi_pxa... | [0699689325](<Notebook/Apple/MacBookPro12/MacBookPro12,1/B130D1C2EC2D/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/0699689325>) |
| 8086:9da4 | 8086:7270 | Intel            | Cannon Point-LP SPI Controller       | 671   | spi_int... | [50FF12C678](<Notebook/ASUSTek Computer/VivoBook/VivoBook S13 X330FN_S330FN/5D11FE94E7EF/DEBIAN-12/6.1.0-28-AMD64/X86_64/50FF12C678>) |
| 8086:7aa4 | 1043:8694 | Intel            | Alder Lake-S PCH SPI Controller      | 561   | spi_int... | [F8371D3425](<Desktop/ASUSTek Computer/PRIME/PRIME B660M-A WIFI D4/08AB6A0E635D/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/F8371D3425>) |
| 8086:7acc | 1043:8694 | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 561   | intel_l... | [F8371D3425](<Desktop/ASUSTek Computer/PRIME/PRIME B660M-A WIFI D4/08AB6A0E635D/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/F8371D3425>) |
| 8086:43a4 | 1043:8694 | Intel            | Tiger Lake-H SPI Controller          | 555   | spi_int... | [63751B6A23](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z590-E GAMING WIFI/802DD0234B9E/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/63751B6A23>) |
| 8086:43e8 | 1043:8694 | Intel            | Tiger Lake-H Serial IO I2C Contro... | 552   | intel_l... | [63751B6A23](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z590-E GAMING WIFI/802DD0234B9E/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/63751B6A23>) |
| 8086:43a4 |           | Intel            | Tiger Lake-H SPI Controller          | 532   | spi_int... | [F43945B8DD](<Desktop/Gigabyte Technology/B560M/B560M AORUS PRO/81CCD1D8C2D3/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/F43945B8DD>) |
| 8086:7acd | 1043:8694 | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 423   | intel_lpss | [A2A616FA46](<Desktop/ASUSTek Computer/PRIME/PRIME Z690-A/D5C3CB3583FB/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/A2A616FA46>) |
| 8086:7ace | 1043:8694 | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 419   | intel_lpss | [A2A616FA46](<Desktop/ASUSTek Computer/PRIME/PRIME Z690-A/D5C3CB3583FB/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/A2A616FA46>) |
| 8086:06a4 | 8086:7270 | Intel            | Comet Lake PCH SPI Controller        | 345   | spi_int... | [98506E2506](<Notebook/ASUSTek Computer/ROG/ROG Strix G712LV_G712LV/5B2C2374494E/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/98506E2506>) |
| 8086:02a4 | 8086:7270 | Intel            | Comet Lake SPI (flash) Controller    | 343   | spi_int... | [4EE757E2C0](<Notebook/Positivo Bahia - VAIO/VJFE52/VJFE52F11X-B2511H/9DDB403A7827/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/4EE757E2C0>) |
| 8086:7a24 | 1043:8882 | Intel            | Raptor Lake SPI (flash) Controller   | 331   | spi_int... | [826DC3E0F2](<Desktop/iBUYPOWER/Intel/Intel Core i7-14700F/0C1A211F1578/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/826DC3E0F2>) |
| 8086:7a4c | 1043:8882 | Intel            | Raptor Lake Serial IO I2C Host Co... | 331   | intel_l... | [826DC3E0F2](<Desktop/iBUYPOWER/Intel/Intel Core i7-14700F/0C1A211F1578/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/826DC3E0F2>) |
| 8086:7aa4 |           | Intel            | Alder Lake-S PCH SPI Controller      | 302   | spi_int... | [FC2486E691](<Desktop/Gigabyte Technology/Z690/Z690 UD DDR4/3179CEF8985A/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/FC2486E691>) |
| 8086:7acc |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 298   | intel_l... | [FC2486E691](<Desktop/Gigabyte Technology/Z690/Z690 UD DDR4/3179CEF8985A/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/FC2486E691>) |
| 8086:7acf |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 298   | intel_l... | [FC2486E691](<Desktop/Gigabyte Technology/Z690/Z690 UD DDR4/3179CEF8985A/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/FC2486E691>) |
| 8086:4da4 | 8086:7270 | Intel            | Jasper Lake SPI Controller           | 296   | spi_int... | [BC8E7EDAC4](<Notebook/Google/Cret/Cret/3C9CF67F812D/KUBUNTU-24.10/6.11.0-13-GENERIC/X86_64/BC8E7EDAC4>) |
| 8086:7ace |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 295   | intel_l... | [FC2486E691](<Desktop/Gigabyte Technology/Z690/Z690 UD DDR4/3179CEF8985A/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/FC2486E691>) |
| 8086:7afc |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 295   | intel_l... | [FC2486E691](<Desktop/Gigabyte Technology/Z690/Z690 UD DDR4/3179CEF8985A/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/FC2486E691>) |
| 8086:7afd |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 295   | intel_l... | [FC2486E691](<Desktop/Gigabyte Technology/Z690/Z690 UD DDR4/3179CEF8985A/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/FC2486E691>) |
| 8086:9da4 | 17aa:2279 | Intel            | Cannon Point-LP SPI Controller       | 291   | spi_int... | [B9E31A2832](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N3S82N1P/72B74810F0E9/ARCH-ROLLING/6.12.8-ARCH1-1/X86_64/B9E31A2832>) |
| 8086:7acd |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 290   | intel_l... | [FC2486E691](<Desktop/Gigabyte Technology/Z690/Z690 UD DDR4/3179CEF8985A/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/FC2486E691>) |
| 8086:9de8 | 17aa:2279 | Intel            | Cannon Point-LP Serial IO I2C Con... | 290   | intel_l... | [B9E31A2832](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N3S82N1P/72B74810F0E9/ARCH-ROLLING/6.12.8-ARCH1-1/X86_64/B9E31A2832>) |
| 8086:7a4d | 1043:8882 | Intel            | Raptor Lake Serial IO I2C Host Co... | 288   | intel_l... | [E8F18DE27B](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z790-F GAMING WIFI/BC34C87A4019/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/E8F18DE27B>) |
| 8086:7a4e | 1043:8882 | Intel            | Raptor Lake Serial IO I2C Host Co... | 288   | intel_l... | [E8F18DE27B](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z790-F GAMING WIFI/BC34C87A4019/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/E8F18DE27B>) |
| 8086:54a4 | 8086:7270 | Intel            | Alder Lake-N SPI (flash) Controller  | 278   | spi_int... | [FA69A9BFBC](<Desktop/Others/Others/Others/7F97178EED74/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/FA69A9BFBC>) |
| 8086:4de8 | 8086:7270 | Intel            | Jasper Lake Serial IO I2C Host Co... | 272   | intel_l... | [BC8E7EDAC4](<Notebook/Google/Cret/Cret/3C9CF67F812D/KUBUNTU-24.10/6.11.0-13-GENERIC/X86_64/BC8E7EDAC4>) |
| 8086:9da4 | 103c:8549 | Intel            | Cannon Point-LP SPI Controller       | 262   | spi_int... | [6781E260B0](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G6/6565E10C0338/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/6781E260B0>) |
| 8086:9de8 | 103c:8549 | Intel            | Cannon Point-LP Serial IO I2C Con... | 262   | intel_l... | [6781E260B0](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G6/6565E10C0338/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/6781E260B0>) |
| 8086:9de9 | 103c:8549 | Intel            | Cannon Point-LP Serial IO I2C Con... | 262   | intel_l... | [6781E260B0](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G6/6565E10C0338/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/6781E260B0>) |
| 8086:02a4 | 17aa:5079 | Intel            | Comet Lake SPI (flash) Controller    | 254   | spi_int... | [A88F8BDDF3](<Notebook/Lenovo/ThinkPad/ThinkPad E14 20RA004WUS/B3667E308BA8/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/A88F8BDDF3>) |
| 8086:a324 | 1849:a324 | Intel            | Cannon Lake PCH SPI Controller       | 252   | spi_int... | [1E63738ABB](<Desktop/ASRock/B360M/B360M Performance/921D799278F1/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/1E63738ABB>) |
| 8086:4dea | 8086:7270 | Intel            | Jasper Lake Serial IO I2C Host Co... | 250   | intel_l... | [BC8E7EDAC4](<Notebook/Google/Cret/Cret/3C9CF67F812D/KUBUNTU-24.10/6.11.0-13-GENERIC/X86_64/BC8E7EDAC4>) |
| 8086:34a4 | 8086:7270 | Intel            | Ice Lake-LP SPI Controller           | 249   | spi_int... | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:34e8 | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2C Control... | 249   | intel_l... | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:9da4 | 8086:2074 | Intel            | Cannon Point-LP SPI Controller       | 248   | spi_int... | [CC4E4FFE1A](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/6C0029DC8B93/DEBIAN-12/6.1.0-26-AMD64/X86_64/CC4E4FFE1A>) |
| 8086:4de9 | 8086:7270 | Intel            | Jasper Lake Serial IO I2C Host Co... | 247   | intel_l... | [E05536561B](<Desktop/AZW/MINI/MINI S/9A4014CDA6EF/UBUNTU-22.04/6.8.0-49-GENERIC/X86_64/E05536561B>) |
| 8086:a324 | 1025:1331 | Intel            | Cannon Lake PCH SPI Controller       | 246   | intel_spi  | [3EAE42086A](<Notebook/Acer/Nitro/Nitro AN515-54/390A99DE1F7D/ARCH-ROLLING/6.12.7-ARCH1-1/X86_64/3EAE42086A>) |
| 8086:a368 | 1025:1331 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 246   | intel_lpss | [3EAE42086A](<Notebook/Acer/Nitro/Nitro AN515-54/390A99DE1F7D/ARCH-ROLLING/6.12.7-ARCH1-1/X86_64/3EAE42086A>) |
| 8086:a369 | 1025:1331 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 246   | intel_lpss | [3EAE42086A](<Notebook/Acer/Nitro/Nitro AN515-54/390A99DE1F7D/ARCH-ROLLING/6.12.7-ARCH1-1/X86_64/3EAE42086A>) |
| 8086:a0a4 | 8086:7270 | Intel            | Tiger Lake-LP SPI Controller         | 245   | spi_int... | [32B3903455](<Notebook/Google/Voxel/Voxel/04919FA7D2EE/KUBUNTU-24.10/6.11.0-13-GENERIC/X86_64/32B3903455>) |
| 8086:a324 | 1028:0905 | Intel            | Cannon Lake PCH SPI Controller       | 244   | spi_int... | [C74F2A3D62](<Notebook/Dell/XPS/XPS 15 7590/26B1B8DF46EC/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/C74F2A3D62>) |
| 8086:a368 | 1028:0905 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 244   | intel_l... | [C74F2A3D62](<Notebook/Dell/XPS/XPS 15 7590/26B1B8DF46EC/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/C74F2A3D62>) |
| 8086:a369 | 1028:0905 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 244   | intel_l... | [C74F2A3D62](<Notebook/Dell/XPS/XPS 15 7590/26B1B8DF46EC/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/C74F2A3D62>) |
| 8086:4dc5 | 8086:7270 | Intel            | Jasper Lake Serial IO I2C Host Co... | 240   | intel_l... | [BC8E7EDAC4](<Notebook/Google/Cret/Cret/3C9CF67F812D/KUBUNTU-24.10/6.11.0-13-GENERIC/X86_64/BC8E7EDAC4>) |
| 8086:43e9 | 1043:8694 | Intel            | Tiger Lake-H Serial IO I2C Contro... | 237   | intel_l... | [63751B6A23](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z590-E GAMING WIFI/802DD0234B9E/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/63751B6A23>) |
| 8086:06a4 | 1043:8694 | Intel            | Comet Lake PCH SPI Controller        | 236   | spi_int... | [5FB39D6837](<Desktop/ASUSTek Computer/PRIME/PRIME H510M-K R2.0/DF149F43E30B/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/5FB39D6837>) |
| 8086:a324 | 1028:087c | Intel            | Cannon Lake PCH SPI Controller       | 234   | spi_int... | [5EB1399D1E](<Notebook/Dell/XPS/XPS 15 9570/45E4548EA4E7/ARCH-ROLLING/6.12.7-ARCH1-1/X86_64/5EB1399D1E>) |

### Serial controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:8c3d | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 300   | serial     | [772D84BC08](<Desktop/Dell/OptiPlex/OptiPlex 9020/89A433DBAC77/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/772D84BC08>) |
| 8086:8c3d | 1458:1c3a | Intel            | 8 Series/C220 Series Chipset Fami... | 279   | serial     | [27053CA724](<Desktop/Gigabyte Technology/B85/B85M-D3H/C42183E26685/DEBIAN-12/6.1.0-28-AMD64/X86_64/27053CA724>) |
| 8086:1e3d | 1028:0577 | Intel            | 7 Series/C210 Series Chipset Fami... | 263   | serial     | [734E205226](<Desktop/Dell/OptiPlex/OptiPlex 7010/1CD0F71C8C43/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/734E205226>) |
| 8086:3b67 | 17aa:2162 | Intel            | 5 Series/3400 Series Chipset KT C... | 250   | serial     | [ECF4A20D48](<Notebook/Lenovo/ThinkPad/ThinkPad T510 4313A11/2CE2156B4537/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/ECF4A20D48>) |
| 8086:1e3d | 103c:3397 | Intel            | 7 Series/C210 Series Chipset Fami... | 246   | serial     | [918FCA6EDA](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/EF4D3B639C52/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/918FCA6EDA>) |
| 8086:1e3d | 17aa:21f3 | Intel            | 7 Series/C210 Series Chipset Fami... | 242   | serial     | [AFCCA700DA](<Notebook/Lenovo/ThinkPad/ThinkPad T430 2349H2G/B337DB6D1388/ZORIN-17/6.8.0-50-GENERIC/X86_64/AFCCA700DA>) |
| 8086:1c3d | 17aa:21ce | Intel            | 6 Series/C200 Series Chipset Fami... | 240   | serial     | [DF34CF20B9](<Notebook/Lenovo/ThinkPad/ThinkPad T420 4236PFG/968339B1DFE6/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/DF34CF20B9>) |
| 8086:2a47 | 17aa:20ec | Intel            | Mobile 4 Series Chipset AMT SOL R... | 239   | serial     | [7B16EB5229](<Notebook/Lenovo/ThinkPad/ThinkPad T500 2241WKY/6679B8A41DC3/ZORIN-17/6.8.0-50-GENERIC/X86_64/7B16EB5229>) |
| 10ec:816a | 17aa:5081 | Realtek Semic... | RTL8111xP UART #1                    | 210   | serial     | [7BFAD25E97](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 1 20UES5NA00/65C9066BF452/FEDORA-40/6.8.5-301.FC40.X86_64/X86_64/7BFAD25E97>) |
| 10ec:816b | 17aa:5081 | Realtek Semic... | RTL8111xP UART #2                    | 210   | serial     | [7BFAD25E97](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 1 20UES5NA00/65C9066BF452/FEDORA-40/6.8.5-301.FC40.X86_64/X86_64/7BFAD25E97>) |
| 8086:06fc | 1028:097d | Intel            | Comet Lake PCH Integrated Sensor ... | 206   | intel_i... | [2A60673D8C](<Notebook/Dell/XPS/XPS 15 9500/C1F125F74882/KALI-2024.4/6.11.2-AMD64/X86_64/2A60673D8C>) |
| 8086:8c3d | 103c:1998 | Intel            | 8 Series/C220 Series Chipset Fami... | 200   | serial     | [CCCF71A69C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/D43107022D9F/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/CCCF71A69C>) |
| 8086:1e3d | 103c:339a | Intel            | 7 Series/C210 Series Chipset Fami... | 194   | serial     | [7FC68E979E](<Desktop/Hewlett-Packard/Compaq/Compaq Pro 6300 SFF/38CD5472725E/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/7FC68E979E>) |
| 8086:29b7 | 1028:0211 | Intel            | 82Q35 Express Serial KT Controller   | 192   | serial     | [5DBB155AB6](<Desktop/Dell/OptiPlex/OptiPlex 755/A76EFDE815CB/LINUXMINT-21.3/5.15.0-130-GENERIC/X86_64/5DBB155AB6>) |
| 8086:1e3d | 17aa:21fa | Intel            | 7 Series/C210 Series Chipset Fami... | 187   | serial     | [D8B0ADF8FB](<Notebook/Lenovo/ThinkPad/ThinkPad X230 23252UG/EAF4136FB502/ARCH-ROLLING/6.6.54-1-LTS/X86_64/D8B0ADF8FB>) |
| 8086:8c3d | 103c:18e7 | Intel            | 8 Series/C220 Series Chipset Fami... | 187   | serial     | [B0312CEA7A](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 TWR/50E8B6DB82B3/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/B0312CEA7A>) |
| 8086:2e17 | 1028:0420 | Intel            | 4 Series Chipset Serial KT Contro... | 184   | serial     | [048527009C](<Desktop/Dell/OptiPlex/OptiPlex 780/464B9B861FE4/ZORIN-17/6.8.0-50-GENERIC/X86_64/048527009C>) |
| 8086:9c3d | 103c:198f | Intel            | 8 Series HECI KT                     | 182   | serial     | [F298C84729](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G1/EA6A0969E96A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/F298C84729>) |
| 8086:9d3d | 103c:8079 | Intel            | Sunrise Point-LP Active Managemen... | 179   | serial     | [F1BC5970F8](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G3/C21CC8AC7701/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/F1BC5970F8>) |
| 8086:1c3d | 103c:1495 | Intel            | 6 Series/C200 Series Chipset Fami... | 176   | serial     | [F9588CF3EB](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite SFF PC/5841A5CB694F/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/F9588CF3EB>) |
| 8086:1c3d | 1028:04ad | Intel            | 6 Series/C200 Series Chipset Fami... | 163   | serial     | [3047D18F75](<Desktop/Dell/OptiPlex/OptiPlex 790/4A8B08DA18B5/ZORIN-17/6.8.0-50-GENERIC/X86_64/3047D18F75>) |
| 8086:1c3d | 1028:047e | Intel            | 6 Series/C200 Series Chipset Fami... | 158   | serial     | [EB43DEACF0](<Desktop/Dell/OptiPlex/OptiPlex 990/CFDD4C279189/LINUXMINT-21.3/5.15.0-1074-GCP/X86_64/EB43DEACF0>) |
| 8086:a0fc | 1028:0991 | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 150   | intel_i... | [31EB7F33DB](<Notebook/Dell/XPS/XPS 13 9310/6BD6176CC7AD/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/31EB7F33DB>) |
| 8086:a0fc | 1028:0a20 | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 149   | intel_i... | [1D2EC04557](<Notebook/Dell/Latitude/Latitude 5420/BC912D9B0DFC/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/1D2EC04557>) |
| 8086:1c3d | 103c:161c | Intel            | 6 Series/C200 Series Chipset Fami... | 147   | serial     | [0A8D680CF0](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8460p/636CD01ADFA4/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/0A8D680CF0>) |
| 8086:1c3d | 103c:1497 | Intel            | 6 Series/C200 Series Chipset Fami... | 144   | serial     | [256C3DEF88](<Desktop/Hewlett-Packard/Compaq/Compaq 6200 Pro SFF PC/2EF617BBD3CB/ZORIN-17/6.8.0-50-GENERIC/X86_64/256C3DEF88>) |
| 8086:51fc |           | Intel            | Alder Lake-P Integrated Sensor Hub   | 143   | intel_i... | [13A15ED2A6](<Notebook/Infinix/ZERO/ZERO BOOK 13/7153EA28EBD6/ARCH-ROLLING/6.12.7-1-CACHYOS-RT-BORE-LTO/X86_64/13A15ED2A6>) |
| 8086:9c3d | 17aa:220c | Intel            | 8 Series HECI KT                     | 140   | serial     | [17AC336E9C](<Notebook/Lenovo/ThinkPad/ThinkPad T440s 20ARS46M00/DD9FCCD73F49/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/17AC336E9C>) |
| 8086:a0fc | 17aa:5089 | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 137   | intel_i... | [179A63F113](<Convertible/Lenovo/ThinkPad/ThinkPad L13 Yoga Gen 2 20VKS0ME00/614558C26FAF/FEDORA-40/6.12.4-100.FC40.X86_64/X86_64/179A63F113>) |
| 8086:1e3d | 17aa:21f6 | Intel            | 7 Series/C210 Series Chipset Fami... | 135   | serial     | [1259802E27](<Notebook/Lenovo/ThinkPad/ThinkPad W530 2447L96/1468DD3B3A2B/LINUXMINT-21/6.8.0-49-GENERIC/X86_64/1259802E27>) |
| 8086:1c3d | 17aa:21da | Intel            | 6 Series/C200 Series Chipset Fami... | 134   | serial     | [FFD4949FC5](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4291QZ1/F148A7085FCF/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/FFD4949FC5>) |
| 8086:1c3d | 17aa:21cf | Intel            | 6 Series/C200 Series Chipset Fami... | 128   | serial     | [A7AA110E08](<Notebook/Lenovo/ThinkPad/ThinkPad W520 428426U/CD5DD673A9D6/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A7AA110E08>) |
| 8086:1e3d | 103c:179b | Intel            | 7 Series/C210 Series Chipset Fami... | 128   | serial     | [FE744F8173](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8470p/39EC752D7DE1/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/FE744F8173>) |
| 8086:2e17 | 1028:027f | Intel            | 4 Series Chipset Serial KT Contro... | 128   | serial     | [8378333655](<Desktop/Dell/OptiPlex/OptiPlex 760/A0C6A78B617B/UBUNTU-MATE-24.04/6.8.0-51-GENERIC/X86_64/8378333655>) |
| 8086:a0fc | f111:0001 | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 125   | intel_i... | [A74FD192F3](<Notebook/Framework/Laptop/Laptop/D157C5BC95B7/NIXOS-25.05/6.12.1/X86_64/A74FD192F3>) |
| 8086:9d3d | 17aa:225d | Intel            | Sunrise Point-LP Active Managemen... | 114   | serial     | [89C4986258](<Notebook/Lenovo/ThinkPad/ThinkPad T480 20L6SA0X00/A0EFE4802237/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.12.6-1-DEFAULT/X86_64/89C4986258>) |
| 8086:8c3d | 17aa:30a3 | Intel            | 8 Series/C220 Series Chipset Fami... | 113   | serial     | [612E46A0E7](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10AAS0EJ00/77062BFB4FAC/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/612E46A0E7>) |
| 10ec:816a | 17aa:5082 | Realtek Semic... | RTL8111xP UART #1                    | 110   | serial     | [C68A17F027](<Notebook/Lenovo/ThinkPad/ThinkPad T14s Gen 1 20UH002LUK/3790C38E2827/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/C68A17F027>) |
| 10ec:816b | 17aa:5082 | Realtek Semic... | RTL8111xP UART #2                    | 110   | serial     | [C68A17F027](<Notebook/Lenovo/ThinkPad/ThinkPad T14s Gen 1 20UH002LUK/3790C38E2827/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/C68A17F027>) |
| 8086:1e3d | 1028:0534 | Intel            | 7 Series/C210 Series Chipset Fami... | 110   | serial     | [860E215DAF](<Notebook/Dell/Latitude/Latitude E6430/A0E982126F70/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/860E215DAF>) |
| 8086:2e17 | 103c:3048 | Intel            | 4 Series Chipset Serial KT Contro... | 110   | serial     | [8984B9B0FF](<Desktop/Hewlett-Packard/Compaq/Compaq 6000 Pro SFF PC/8BA3D68DF3A9/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/8984B9B0FF>) |
| 8086:a13d | 1028:06b9 | Intel            | 100 Series/C230 Series Chipset Fa... | 108   | serial     | [A6858E47C5](<Desktop/Dell/OptiPlex/OptiPlex 7040/D7A84FA1BD75/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/A6858E47C5>) |
| 8086:9c3d | 1028:05cb | Intel            | 8 Series HECI KT                     | 103   | serial     | [E25716EB4B](<Notebook/Dell/Latitude/Latitude E7440/6D8BFD9B5EF2/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/E25716EB4B>) |
| 8086:9d3d | 1028:06dc | Intel            | Sunrise Point-LP Active Managemen... | 101   | serial     | [448C4C5D6E](<Notebook/Dell/Latitude/Latitude E7470/E6EA2D9D8448/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/448C4C5D6E>) |
| 8086:3b67 | 1028:040a | Intel            | 5 Series/3400 Series Chipset KT C... | 100   | serial     | [B51666DD6F](<Notebook/Dell/Latitude/Latitude E6410/9FE658EF0EE7/DEBIAN-11/5.10.0-15-AMD64/X86_64/B51666DD6F>) |
| 8086:8c3d | 17aa:3097 | Intel            | 8 Series/C220 Series Chipset Fami... | 100   | serial     | [1E479B232E](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10A8001HUS/1C5AB6350E06/ZORIN-17/6.8.0-49-GENERIC/X86_64/1E479B232E>) |
| 8086:3b67 | 8086:0036 | Intel            | 5 Series/3400 Series Chipset KT C... | 99    | serial     | [1F0E503F99](<Desktop/Mikrolog/PRO/PRO H55-J9/6BC42700AC25/UBUNTU-22.04/5.15.0-126-GENERIC/X86_64/1F0E503F99>) |
| 8086:43fc | 1028:0a61 | Intel            | Tiger Lake-H Integrated Sensor Hub   | 99    | intel_i... | [F66CE0B3EE](<Notebook/Dell/XPS/XPS 15 9510/5165526BE54E/LINUXMINT-22/6.8.0-48-GENERIC/X86_64/F66CE0B3EE>) |
| 8086:9d3d | 103c:83b2 | Intel            | Sunrise Point-LP Active Managemen... | 99    | serial     | [85CAA6254A](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G5/AA944F47D2BF/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/85CAA6254A>) |
| 8086:9d3d | 17aa:2245 | Intel            | Sunrise Point-LP Active Managemen... | 99    | serial     | [128DFC3B06](<Notebook/Lenovo/ThinkPad/ThinkPad T470 W10DG 20JNS1XT00/6F7A39DEDBCE/BLUEFIN-40/6.11.3-200.FC40.X86_64/X86_64/128DFC3B06>) |

### Signal processing (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0e30 | 1028:04f6 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 3     | ivbep_u... | [B06AB09EE7](<Server/Dell/PowerEdge/PowerEdge R520/CE26586B1628/ROCKY-9.3/5.14.0-362.24.1.EL9_3.X86_64/X86_64/B06AB09EE7>) |
| 8086:0e34 | 1028:04f6 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 3     | ivbep_u... | [B06AB09EE7](<Server/Dell/PowerEdge/PowerEdge R520/CE26586B1628/ROCKY-9.3/5.14.0-362.24.1.EL9_3.X86_64/X86_64/B06AB09EE7>) |
| 8086:0e36 | 1028:04f6 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 3     | ivbep_u... | [B06AB09EE7](<Server/Dell/PowerEdge/PowerEdge R520/CE26586B1628/ROCKY-9.3/5.14.0-362.24.1.EL9_3.X86_64/X86_64/B06AB09EE7>) |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9a0d |           | Intel            | Tigerlake Telemetry Aggregator       | 1789  | intel_vsec | [D0DCE2F4FE](<Notebook/MSI/Sword/Sword 15 A11UD/546EC6D8F99C/FSL/6.12.7-ARCH1-1/X86_64/D0DCE2F4FE>) |
| 8086:467d |           | Intel            | Platform Monitoring Technology       | 1750  | intel_vsec | [537A11AE44](<Desktop/PELADN/WI/WI-6/A87F09289266/LMDE-6/6.1.0-28-AMD64/X86_64/537A11AE44>) |
| 8086:31b4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1350  | intel_l... | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:31ac | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1295  | intel_l... | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:31ba | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1293  | intel_l... | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:318c | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1287  | process... | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:31b6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1284  | intel_l... | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:31b8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1279  | intel_l... | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:31bc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1279  | intel_l... | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:31c0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1274  | intel_l... | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:31be | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1236  | intel_l... | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:31ee | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1236  | intel_l... | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:31c6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1233  | intel_l... | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:31c2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1230  | intel_l... | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:31ae | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1194  | intel_l... | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:31b0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1179  | intel_l... | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:31b2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1179  | intel_l... | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:31c4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1175  | intel_l... | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:22dc | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1000  | process... | [496C93250D](<Tablet/Chuwi/Hi10/Hi10 pro tablet/D5A4927F3C98/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/496C93250D>) |
| 8086:5aac | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 911   | intel_l... | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 8086:5a8c |           | Intel            | Atom/Celeron/Pentium Dynamic Plat... | 894   | process... | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 8086:5ab4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 891   | intel_l... | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 8086:5ab2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 889   | intel_l... | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 8086:5ab6 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 888   | intel_l... | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 8086:5aae | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 886   | intel_l... | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 8086:5ac2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 873   | intel_l... | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 8086:5ab0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 871   | intel_l... | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 8086:5abc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 866   | intel_l... | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 8086:5abe | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 827   | intel_l... | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 8086:5ac0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 821   | intel_l... | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 1022:15e4 | 1022:15e4 | AMD              | Sensor Fusion Hub                    | 813   | amd_sfh    | [84DECD497D](<Desktop/BESSTAR Tech/HM/HM80/641CA314EE82/NOBARA-39/6.8.12-200.FSYNC.FC39.X86_64/X86_64/84DECD497D>) |
| 8086:5ac6 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 770   | intel_l... | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 8086:5ac4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 769   | intel_l... | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 8086:5ab8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 768   | intel_l... | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 8086:5aba | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 768   | intel_l... | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 8086:9d60 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 763   | intel_l... | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:5aee | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 756   | intel_l... | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 8086:a77d |           | Intel            | Raptor Lake Crashlog and Telemetry   | 741   | intel_vsec | [0F5C50A01C](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X1504VA_A1504VA/031205FB4B63/ARCH-ROLLING/6.12.8-ARCH1-1/X86_64/0F5C50A01C>) |
| 8086:9ca4 | 8086:7270 | Intel            | Wildcat Point-LP Thermal Manageme... | 709   | intel_p... | [0699689325](<Notebook/Apple/MacBookPro12/MacBookPro12,1/B130D1C2EC2D/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/0699689325>) |
| 8086:9d62 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 705   | intel_l... | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:9d31 | 8086:7270 | Intel            | Sunrise Point-LP Thermal subsystem   | 693   | intel_p... | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:a379 | 1458:8888 | Intel            | Cannon Lake PCH Thermal Controller   | 680   | intel_p... | [639EB0E4FC](<Desktop/Gigabyte Technology/H370M/H370M D3H GSM/D391F95DF729/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/639EB0E4FC>) |
| 8086:9d27 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO UART C... | 639   | intel_l... | [EAF1BB652C](<Tablet/Microsoft/Surface/Surface Book 2/B870A7627396/ARCH-ROLLING/6.12.7-ARCH1-1-NSB2/X86_64/EAF1BB652C>) |
| 8086:9d61 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 559   | intel_l... | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:3b32 | 17aa:2190 | Intel            | 5 Series/3400 Series Chipset Ther... | 553   | intel_ips  | [ECF4A20D48](<Notebook/Lenovo/ThinkPad/ThinkPad T510 4313A11/2CE2156B4537/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/ECF4A20D48>) |
| 8086:467d | 1043:8694 | Intel            | Platform Monitoring Technology       | 493   | intel_vsec | [A2A616FA46](<Desktop/ASUSTek Computer/PRIME/PRIME Z690-A/D5C3CB3583FB/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/A2A616FA46>) |
| 8086:22dc | 7270:8086 | Intel            | Atom/Celeron/Pentium Processor x5... | 477   | process... | [DC120E3257](<Convertible/Lenovo/YB1/YB1-X91F/9D7F159A248D/UBUNTU-22.04/6.8.0-40-GENERIC/X86_64/DC120E3257>) |
| 8086:1903 | 8086:1903 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 460   | process... | [165F302BE9](<Notebook/Google/Chell/Chell/D809DC2934A8/DEBIAN/6.12.6-AMD64/X86_64/165F302BE9>) |
| 8086:9d27 | 1043:1d2d | Intel            | Sunrise Point-LP Serial IO UART C... | 447   | intel_l... | [54B1993E1C](<Notebook/ASUSTek Computer/VivoBook/VivoBook 14_ASUS Laptop X442UF/0A38CA59E073/ENDEAVOUROS-ROLLING/6.12.7-ARCH1-1/X86_64/54B1993E1C>) |
| 8086:9d63 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 440   | intel_l... | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:790b | 1458:5001 | AMD              | FCH SMBus Controller                 | 5169  | i2c_piix4  | [A23FC83EDD](<Desktop/Gigabyte Technology/AB350/AB350-Gaming/B5A158869F92/GENTOO-2.17/6.6.67-GENTOO/X86_64/A23FC83EDD>) |
| 1022:790b | 1022:790b | AMD              | FCH SMBus Controller                 | 3598  | i2c_piix4  | [84DECD497D](<Desktop/BESSTAR Tech/HM/HM80/641CA314EE82/NOBARA-39/6.8.12-200.FSYNC.FC39.X86_64/X86_64/84DECD497D>) |
| 1022:790b | 1043:87c0 | AMD              | FCH SMBus Controller                 | 3304  | piix4_s... | [88B1C0C262](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING WIFI II/B8760FB55781/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/88B1C0C262>) |
| 1002:4385 | 1002:4385 | AMD              | SBx00 SMBus Controller               | 2119  | i2c_pii... | [0B63013A2A](<Desktop/ASUSTek Computer/M4A79T/M4A79T Deluxe/BE3CF50E786D/LINUXMINT-21.3/5.15.0-130-GENERIC/X86_64/0B63013A2A>) |
| 1022:790b | 1849:ffff | AMD              | FCH SMBus Controller                 | 1891  | piix4_s... | [55ED055BF7](<Desktop/ASRock/A520M/A520M Phantom Gaming 4/C09535CF4E8E/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/55ED055BF7>) |
| 8086:1c22 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 1859  | i2c_i801   | [2B21C81822](<Desktop/ASUSTek Computer/P8Z68-V/P8Z68-V LX/4130A0D4D84A/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/2B21C81822>) |
| 1022:790b | 1e44:1776 | AMD              | FCH SMBus Controller                 | 1747  | piix4_s... | [DFF6A36E92](<Notebook/Valve/Galileo/Galileo/3D6CF2B6536D/STEAMOS-3.6.20/6.5.0-VALVE22-1-NEPTUNE-65-G9A338ED8A75E/X86_64/DFF6A36E92>) |
| 8086:8c22 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 1639  | i2c_i801   | [C4C2F7FE89](<Desktop/ASUSTek Computer/All/All Series/09DD706491D9/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/C4C2F7FE89>) |
| 1022:790b | 1043:8747 | AMD              | FCH SMBus Controller                 | 1582  | i2c_piix4  | [CF7D50FAE1](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-K II/24E629ECD716/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/CF7D50FAE1>) |
| 1022:790b | 1849:790b | AMD              | FCH SMBus Controller                 | 1479  | i2c_piix4  | [0D776677A7](<Desktop/ASRock/AB350/AB350 Pro4/801653C6BD48/KUBUNTU-24.10/6.11.0-13-GENERIC/X86_64/0D776677A7>) |
| 8086:a123 | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 1450  | i2c_i801   | [FF2E84AB02](<Desktop/ASUSTek Computer/H110/H110M-E-M.2/4907896789F3/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/FF2E84AB02>) |
| 8086:31d4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1449  | i2c_i801   | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 1002:4385 |           | AMD              | SBx00 SMBus Controller               | 1343  | i2c_pii... | [CD33AA866C](<Desktop/Gigabyte Technology/GA-970/GA-970A-D3/0098B4B2B0F6/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/CD33AA866C>) |
| 1002:4385 | 1043:8389 | AMD              | SBx00 SMBus Controller               | 1310  | i2c_piix4  | [02A12F94E1](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX V2/63B73941E98E/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/02A12F94E1>) |
| 8086:1e22 | 1043:84ca | Intel            | 7 Series/C216 Chipset Family SMBu... | 1294  | i2c_i801   | [69679C9A35](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/05DEE4E22315/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/69679C9A35>) |
| 1002:4385 | 1458:4385 | AMD              | SBx00 SMBus Controller               | 1257  | i2c_pii... | [617C102331](<Desktop/Gigabyte Technology/GA-MA770/GA-MA770T-UD3/8220651D2E86/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/617C102331>) |
| 8086:1c22 | 1458:5001 | Intel            | 6 Series/C200 Series Chipset Fami... | 1157  | i2c_i801   | [2EF34839F4](<Desktop/Gigabyte Technology/H61/H61M-DS2/29D58848E162/ZORIN-17/6.5.0-18-GENERIC/X86_64/2EF34839F4>) |
| 8086:8c22 | 1458:5001 | Intel            | 8 Series/C220 Series Chipset Fami... | 1128  | i2c_i801   | [27053CA724](<Desktop/Gigabyte Technology/B85/B85M-D3H/C42183E26685/DEBIAN-12/6.1.0-28-AMD64/X86_64/27053CA724>) |
| 8086:27da | 1458:5001 | Intel            | NM10/ICH7 Family SMBus Controller    | 1108  | i2c_i801   | [D4592A5F61](<Desktop/Gigabyte Technology/G41/G41MT-S2PT/AF9C7E0168B7/UBUNTU-24.10/6.11.0-13-GENERIC/X86_64/D4592A5F61>) |
| 10de:0aa2 | 10de:cb79 | Nvidia           | MCP79 SMBus                          | 1078  | i2c_nfo... | [DE39DE3147](<Notebook/Apple/MacBookPro5/MacBookPro5,5/AE9A7F9028B1/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/DE39DE3147>) |
| 8086:a2a3 | 1043:8694 | Intel            | 200 Series/Z370 Chipset Family SM... | 1032  | i2c_i801   | [10FD8EF9DD](<Desktop/ASUSTek Computer/TUF/TUF Z370-PLUS GAMING II/76981D36E1E4/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/10FD8EF9DD>) |
| 8086:3a30 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 1019  | i2c_i801   | [2E5A12A36B](<Desktop/ASUSTek Computer/P5Q/P5Q SE PLUS/423D0CB53C57/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/2E5A12A36B>) |
| 8086:1e22 | 1458:5001 | Intel            | 7 Series/C216 Chipset Family SMBu... | 1009  | i2c_i801   | [139B1D261D](<Desktop/Gigabyte Technology/B75/B75M-D3H/1C75C0A003F1/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/139B1D261D>) |
| 8086:1c22 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 1004  | i2c_i801   | [705713446F](<Notebook/Apple/MacBookAir4/MacBookAir4,1/0A918C18E48D/MANJARO/6.12.4-1-MANJARO/X86_64/705713446F>) |
| 8086:1e22 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family SMBu... | 968   | i2c_i801   | [AE5A71DDE0](<Notebook/Apple/MacBookPro9/MacBookPro9,1/04AD065CAD6F/LINUXMINT-20.3/5.4.0-204-GENERIC/X86_64/AE5A71DDE0>) |
| 8086:27da | 1043:8179 | Intel            | NM10/ICH7 Family SMBus Controller    | 945   | i2c_i801   | [62E974EBEE](<Desktop/ASUSTek Computer/P5/P5GZ-MX/399311230F6E/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/62E974EBEE>) |
| 8086:1e22 | 17aa:3977 | Intel            | 7 Series/C216 Chipset Family SMBu... | 941   | i2c_i801   | [516947871E](<Notebook/Lenovo/IdeaPad/IdeaPad Z400 VIWZ1/2725496AFD2D/ZORIN-17/6.8.0-50-GENERIC/X86_64/516947871E>) |
| 8086:a2a3 | 1458:5001 | Intel            | 200 Series/Z370 Chipset Family SM... | 940   | i2c_i801   | [A49FDE4DF3](<Desktop/Gigabyte Technology/B365M/B365M DS3H/406A103EBD76/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/A49FDE4DF3>) |
| 8086:5ad4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 902   | i2c_i801   | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 8086:8c22 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 841   | i2c_i801   | [2CD6888290](<Desktop/MACHINIST/E5-MR9A/E5-MR9A V1.0/A16E88B1E292/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/2CD6888290>) |
| 8086:a323 | 1043:8694 | Intel            | Cannon Lake PCH SMBus Controller     | 826   | i2c_i801   | [D6E8F1EE6C](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-P/DD926E3C669B/LMDE-6/6.11.10+BPO-AMD64/X86_64/D6E8F1EE6C>) |
| 1002:4385 | 1849:4385 | AMD              | SBx00 SMBus Controller               | 824   | i2c_pii... | [8EDA0B8FBF](<Desktop/ASRock/970M/970M Pro3/7CFC618F7557/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/8EDA0B8FBF>) |
| 8086:a123 | 1458:5001 | Intel            | 100 Series/C230 Series Chipset Fa... | 815   | i2c_i801   | [AD40DB7F67](<Desktop/Gigabyte Technology/Z170X-Gaming/Z170X-Gaming 7/4DE1A28702A7/ZORIN-17/6.8.0-50-GENERIC/X86_64/AD40DB7F67>) |
| 1022:790b | 1043:8877 | AMD              | FCH SMBus Controller                 | 794   | piix4_s... | [04F9FFDAB4](<Desktop/ASUSTek Computer/ROG/ROG STRIX B650-A GAMING WIFI/848E93DF68A9/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/04F9FFDAB4>) |
| 8086:9ca2 | 8086:7270 | Intel            | Wildcat Point-LP SMBus Controller    | 781   | i2c_i801   | [0699689325](<Notebook/Apple/MacBookPro12/MacBookPro12,1/B130D1C2EC2D/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/0699689325>) |
| 1022:780b | 1022:780b | AMD              | FCH SMBus Controller                 | 752   | i2c_piix4  | [778B3689C2](<Desktop/MAXSUN/MS-A86FX/MS-A86FX FS M.3/D0EC83BEBF32/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/778B3689C2>) |
| 8086:a323 | 1458:5001 | Intel            | Cannon Lake PCH SMBus Controller     | 680   | i2c_i801   | [639EB0E4FC](<Desktop/Gigabyte Technology/H370M/H370M D3H GSM/D391F95DF729/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/639EB0E4FC>) |
| 1022:790b | 1043:87e1 | AMD              | FCH SMBus Controller                 | 669   | i2c_piix4  | [989A72852C](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PLUS/4495A9F18FCB/ZORIN-17/6.8.0-50-GENERIC/X86_64/989A72852C>) |
| 8086:8ca2 | 1043:8534 | Intel            | 9 Series Chipset Family SMBus Con... | 663   | i2c_i801   | [BA47136806](<Desktop/ASUSTek Computer/All/All Series/651BB16BD9C9/UBUNTU-24.10/6.12.3-061203-GENERIC/X86_64/BA47136806>) |
| 8086:27da | 1849:27da | Intel            | NM10/ICH7 Family SMBus Controller    | 635   | i2c_i801   | [9B8BA4CB2C](<Desktop/ASRock/G31/G31M-S/B3DA2B9DAB10/PUPPY-9/5.4.53/X86_64/9B8BA4CB2C>) |
| 1022:790b | 1043:876b | AMD              | FCH SMBus Controller                 | 632   | i2c_piix4  | [4CB02F7CED](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-K/EF4B140B96CA/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/4CB02F7CED>) |
| 8086:9c22 | 17aa:3978 | Intel            | 8 Series SMBus Controller            | 620   | i2c_i801   | [666751867C](<Notebook/Lenovo/G50-70/G50-70 20351/1934A760E88D/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/666751867C>) |
| 8086:9c22 | 8086:7270 | Intel            | 8 Series SMBus Controller            | 612   | i2c_i801   | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 8086:3b30 | 17aa:2167 | Intel            | 5 Series/3400 Series Chipset SMBu... | 608   | i2c_i801   | [ECF4A20D48](<Notebook/Lenovo/ThinkPad/ThinkPad T510 4313A11/2CE2156B4537/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/ECF4A20D48>) |
| 10de:03eb | 1849:03eb | Nvidia           | MCP61 SMBus                          | 601   | i2c_nfo... | [CB76400A00](<Desktop/ASRock/N68-S/N68-S UCC/3C232072D095/NEPTUNE-8.1/6.1.0-18-AMD64/X86_64/CB76400A00>) |
| 1022:780b | 1849:780b | AMD              | FCH SMBus Controller                 | 589   | i2c_pii... | [86FD341A89](<Desktop/ASRock/A75/A75 Extreme6/B47300C092A7/ZORIN-17/6.8.0-50-GENERIC/X86_64/86FD341A89>) |
| 8086:9d23 | 8086:7270 | Intel            | Sunrise Point-LP SMBus               | 570   | i2c_i801   | [EAF1BB652C](<Tablet/Microsoft/Surface/Surface Book 2/B870A7627396/ARCH-ROLLING/6.12.7-ARCH1-1-NSB2/X86_64/EAF1BB652C>) |
| 8086:7aa3 | 1043:8694 | Intel            | Alder Lake-S PCH SMBus Controller    | 561   | i2c_i801   | [F8371D3425](<Desktop/ASUSTek Computer/PRIME/PRIME B660M-A WIFI D4/08AB6A0E635D/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/F8371D3425>) |
| 8086:43a3 | 1043:8694 | Intel            | Tiger Lake-H SMBus Controller        | 555   | i2c_i801   | [63751B6A23](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z590-E GAMING WIFI/802DD0234B9E/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/63751B6A23>) |
| 8086:1c22 | 8086:1c22 | Intel            | 6 Series/C200 Series Chipset Fami... | 543   | i2c_i801   | [2A8FF4B81A](<Desktop/Intel/H/H61/B6CD4A1B0883/ZORIN-17/6.8.0-50-GENERIC/X86_64/2A8FF4B81A>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1002:1637 | 1002:1637 | AMD              | Renoir Radeon High Definition Aud... | 3464  | snd_hda... | [69FF87B949](<Desktop/Gigabyte Technology/A520/A520 AORUS ELITE/81AB90394B6C/GENTOO-2.17/6.6.67-GENTOO/X86_64/69FF87B949>) |
| 1002:ab28 | 1002:ab28 | AMD              | Navi 21/23 HDMI/DP Audio Controller  | 3150  | snd_hda... | [1FF9C9F7CB](<Desktop/MSI/MS-7/MS-7E26/771CE98DF000/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/1FF9C9F7CB>) |
| 1002:15de | 1002:15de | AMD              | Raven/Raven2/Fenghuang HDMI/DP Au... | 2376  | snd_hda... | [D80A8FD406](<Desktop/Gigabyte Technology/X570/X570 AORUS ELITE WIFI/CC478A15F194/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/D80A8FD406>) |
| 8086:0c0c | 8086:2010 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 1933  | snd_hda... | [27053CA724](<Desktop/Gigabyte Technology/B85/B85M-D3H/C42183E26685/DEBIAN-12/6.1.0-28-AMD64/X86_64/27053CA724>) |
| 1002:1640 | 1002:1640 | AMD              | Rembrandt Radeon High Definition ... | 1799  | snd_hda... | [2183EB76B7](<Tablet/ONE-NETBOOK/ONEXPLAYER/ONEXPLAYER Mini Pro/F55453A23AA1/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/2183EB76B7>) |
| 1002:1640 | 1e44:1776 | AMD              | Rembrandt Radeon High Definition ... | 1747  | snd_hda... | [DFF6A36E92](<Notebook/Valve/Galileo/Galileo/3D6CF2B6536D/STEAMOS-3.6.20/6.5.0-VALVE22-1-NEPTUNE-65-G9A338ED8A75E/X86_64/DFF6A36E92>) |
| 1002:ab38 | 1002:ab38 | AMD              | Navi 10 HDMI Audio                   | 1570  | snd_hda... | [E6A453B673](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/A57EFA49F51F/MANJARO-24.2.1/6.11.11-1-MANJARO/X86_64/E6A453B673>) |
| 8086:8c20 | 1043:8576 | Intel            | 8 Series/C220 Series Chipset High... | 1125  | snd_hda... | [37BADC0CFD](<Desktop/ASUSTek Computer/All/All Series/43F35A65508C/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/37BADC0CFD>) |
| 10de:0ac0 | 10de:cb79 | Nvidia           | MCP79 High Definition Audio          | 1077  | snd_hda... | [DE39DE3147](<Notebook/Apple/MacBookPro5/MacBookPro5,5/AE9A7F9028B1/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/DE39DE3147>) |
| 1002:aaf0 | 1da2:aaf0 | AMD              | Ellesmere HDMI Audio [Radeon RX 4... | 1066  | snd_hda... | [FDA84AF6B6](<Desktop/MSI/MS-7/MS-7A40/DC07AAAD39A3/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/FDA84AF6B6>) |
| 8086:8c20 | 1458:a002 | Intel            | 8 Series/C220 Series Chipset High... | 1010  | snd_hda... | [27053CA724](<Desktop/Gigabyte Technology/B85/B85M-D3H/C42183E26685/DEBIAN-12/6.1.0-28-AMD64/X86_64/27053CA724>) |
| 1002:ab30 | 1002:ab30 | AMD              | Navi 31 HDMI/DP Audio                | 1004  | snd_hda... | [04F9FFDAB4](<Desktop/ASUSTek Computer/ROG/ROG STRIX B650-A GAMING WIFI/848E93DF68A9/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/04F9FFDAB4>) |
| 10de:0bea |           | Nvidia           | GF108 High Definition Audio Contr... | 989   | snd_hda... | [01D0EFAF46](<Notebook/ASUSTek Computer/K93/K93SV/C5B295015EB7/ZORIN-17/6.8.0-50-GENERIC/X86_64/01D0EFAF46>) |
| 8086:1c20 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 965   | snd_hda... | [705713446F](<Notebook/Apple/MacBookAir4/MacBookAir4,1/0A918C18E48D/MANJARO/6.12.4-1-MANJARO/X86_64/705713446F>) |
| 8086:1c20 | 1458:a002 | Intel            | 6 Series/C200 Series Chipset Fami... | 952   | snd_hda... | [2EF34839F4](<Desktop/Gigabyte Technology/H61/H61M-DS2/29D58848E162/ZORIN-17/6.5.0-18-GENERIC/X86_64/2EF34839F4>) |
| 8086:27d8 | 1458:a002 | Intel            | NM10/ICH7 Family High Definition ... | 946   | snd_hda... | [D4592A5F61](<Desktop/Gigabyte Technology/G41/G41MT-S2PT/AF9C7E0168B7/UBUNTU-24.10/6.11.0-13-GENERIC/X86_64/D4592A5F61>) |
| 8086:1e20 | 17aa:3977 | Intel            | 7 Series/C216 Chipset Family High... | 941   | snd_hda... | [516947871E](<Notebook/Lenovo/IdeaPad/IdeaPad Z400 VIWZ1/2725496AFD2D/ZORIN-17/6.8.0-50-GENERIC/X86_64/516947871E>) |
| 8086:1e20 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family High... | 936   | snd_hda... | [AE5A71DDE0](<Notebook/Apple/MacBookPro9/MacBookPro9,1/04AD065CAD6F/LINUXMINT-20.3/5.4.0-204-GENERIC/X86_64/AE5A71DDE0>) |
| 1002:4383 | 1458:a002 | AMD              | SBx00 Azalia (Intel HDA)             | 882   | snd_hda... | [617C102331](<Desktop/Gigabyte Technology/GA-MA770/GA-MA770T-UD3/8220651D2E86/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/617C102331>) |
| 1022:1487 | 1043:8797 | AMD              | Starship/Matisse HD Audio Controller | 872   | snd_hda... | [A7C3662AEC](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550M-PLUS/6E0B28BC4A8B/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/A7C3662AEC>) |
| 10de:0e0f | 1462:8c93 | Nvidia           | GK208 HDMI/DP Audio Controller       | 827   | snd_hda... | [76CFDE7DC3](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-K/D65E7197EDD5/DEBIAN/6.1.0-28-AMD64/X86_64/76CFDE7DC3>) |
| 8086:8c20 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset High... | 821   | snd_hda... | [2CD6888290](<Desktop/MACHINIST/E5-MR9A/E5-MR9A V1.0/A16E88B1E292/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/2CD6888290>) |
| 1002:aaf0 | 1462:aaf0 | AMD              | Ellesmere HDMI Audio [Radeon RX 4... | 794   | snd_hda... | [BADFE83ED3](<Desktop/ASUSTek Computer/M5A97/M5A97 LE R2.0/25917080F8AD/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/BADFE83ED3>) |
| 1022:1457 | 1458:a182 | AMD              | Family 17h (Models 00h-0fh) HD Au... | 775   | snd_hda... | [A23FC83EDD](<Desktop/Gigabyte Technology/AB350/AB350-Gaming/B5A158869F92/GENTOO-2.17/6.6.67-GENTOO/X86_64/A23FC83EDD>) |
| 8086:9ca0 | 8086:7270 | Intel            | Wildcat Point-LP High Definition ... | 764   | snd_hda... | [0699689325](<Notebook/Apple/MacBookPro12/MacBookPro12,1/B130D1C2EC2D/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/0699689325>) |
| 1002:aaf0 | 1682:aaf0 | AMD              | Ellesmere HDMI Audio [Radeon RX 4... | 759   | snd_hda... | [A24D68CA3C](<Desktop/MSI/MS-7/MS-7C95/389A9DE31DED/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/A24D68CA3C>) |
| 8086:a2f0 | 1458:a182 | Intel            | 200 Series PCH HD Audio              | 744   | snd_hda... | [A49FDE4DF3](<Desktop/Gigabyte Technology/B365M/B365M DS3H/406A103EBD76/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/A49FDE4DF3>) |
| 8086:a170 | 1043:86c7 | Intel            | 100 Series/C230 Series Chipset Fa... | 739   | snd_hda... | [FF2E84AB02](<Desktop/ASUSTek Computer/H110/H110M-E-M.2/4907896789F3/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/FF2E84AB02>) |
| 8086:0c0c | 1043:8534 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 726   | snd_hda... | [BA47136806](<Desktop/ASUSTek Computer/All/All Series/651BB16BD9C9/UBUNTU-24.10/6.12.3-061203-GENERIC/X86_64/BA47136806>) |
| 1002:aab0 | 174b:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 680   | snd_hda... | [BB11DE9504](<Desktop/ASUSTek Computer/M5A97/M5A97 R2.0/C0891D2BC714/DEBIAN-12/6.1.0-28-AMD64/X86_64/BB11DE9504>) |
| 1002:4383 | 1043:8445 | AMD              | SBx00 Azalia (Intel HDA)             | 674   | snd_hda... | [02A12F94E1](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX V2/63B73941E98E/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/02A12F94E1>) |
| 10de:0fb9 |           | Nvidia           | GP107GL High Definition Audio Con... | 665   | snd_hda... | [CA3162CF4A](<Notebook/Avell High Performance/Avell/Avell G1513 MUV-A52 MUV/6C12B4D62FB4/ZORIN-17/6.8.0-50-GENERIC/X86_64/CA3162CF4A>) |
| 1022:1457 | 1043:86c7 | AMD              | Family 17h (Models 00h-0fh) HD Au... | 647   | snd_hda... | [E6A453B673](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/A57EFA49F51F/MANJARO-24.2.1/6.11.11-1-MANJARO/X86_64/E6A453B673>) |
| 8086:a170 | 1458:a182 | Intel            | 100 Series/C230 Series Chipset Fa... | 647   | snd_hda... | [1B9078C7D8](<Desktop/Gigabyte Technology/H110/H110M-S2/D1D4EB80AD1A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/1B9078C7D8>) |
| 8086:9d71 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 641   | snd_hda... | [EAF1BB652C](<Tablet/Microsoft/Surface/Surface Book 2/B870A7627396/ARCH-ROLLING/6.12.7-ARCH1-1-NSB2/X86_64/EAF1BB652C>) |
| 8086:0a0c | 17aa:3978 | Intel            | Haswell-ULT HD Audio Controller      | 620   | snd_hda... | [666751867C](<Notebook/Lenovo/G50-70/G50-70 20351/1934A760E88D/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/666751867C>) |
| 8086:9c20 | 17aa:3978 | Intel            | 8 Series HD Audio Controller         | 620   | snd_hda... | [666751867C](<Notebook/Lenovo/G50-70/G50-70 20351/1934A760E88D/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/666751867C>) |
| 8086:1e20 | 1458:a002 | Intel            | 7 Series/C216 Chipset Family High... | 615   | snd_hda... | [139B1D261D](<Desktop/Gigabyte Technology/B75/B75M-D3H/1C75C0A003F1/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/139B1D261D>) |
| 1022:1487 | 1458:a0c3 | AMD              | Starship/Matisse HD Audio Controller | 607   | snd_hda... | [1F3CF34C48](<Desktop/Gigabyte Technology/X570/X570 AORUS ULTRA/828B77066DE5/MANJARO/6.12.4-1-MANJARO/X86_64/1F3CF34C48>) |
| 8086:9c20 | 8086:7270 | Intel            | 8 Series HD Audio Controller         | 607   | snd_hda... | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 1022:15e3 | 1043:86c7 | AMD              | Family 17h/19h/1ah HD Audio Contr... | 599   | snd_hda... | [4CB02F7CED](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-K/EF4B140B96CA/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/4CB02F7CED>) |
| 8086:a2f0 | 1043:86c7 | Intel            | 200 Series PCH HD Audio              | 595   | snd_hda... | [79752B904B](<Desktop/ASUSTek Computer/PRIME/PRIME H310M-E R2.0/7D532FED2934/ELEMENTARY-8/6.8.0-49-GENERIC/X86_64/79752B904B>) |
| 1022:1487 | 1043:87c5 | AMD              | Starship/Matisse HD Audio Controller | 589   | snd_hda... | [88B1C0C262](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING WIFI II/B8760FB55781/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/88B1C0C262>) |
| 1002:1640 | 1043:8877 | AMD              | Rembrandt Radeon High Definition ... | 584   | snd_hda... | [04F9FFDAB4](<Desktop/ASUSTek Computer/ROG/ROG STRIX B650-A GAMING WIFI/848E93DF68A9/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/04F9FFDAB4>) |
| 1022:15e3 | 1458:a182 | AMD              | Family 17h/19h/1ah HD Audio Contr... | 582   | snd_hda... | [69968FADE5](<Desktop/Gigabyte Technology/B450M/B450M DS3H/7EFFF0688F78/MAGEIA-9/6.6.65-DESKTOP-2.MGA9/X86_64/69968FADE5>) |
| 8086:3b56 | 17aa:215e | Intel            | 5 Series/3400 Series Chipset High... | 581   | snd_hda... | [ECF4A20D48](<Notebook/Lenovo/ThinkPad/ThinkPad T510 4313A11/2CE2156B4537/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/ECF4A20D48>) |
| 8086:1c20 | 1043:8445 | Intel            | 6 Series/C200 Series Chipset Fami... | 577   | snd_hda... | [F975C50855](<Desktop/ASUSTek Computer/H61/H61M-E/6EA9558F7670/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/F975C50855>) |
| 8086:293e | 17aa:20f2 | Intel            | 82801I (ICH9 Family) HD Audio Con... | 573   | snd_hda... | [0C0F6EF206](<Notebook/Lenovo/ThinkPad/ThinkPad SL400 2743A48/24276C7B5960/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/0C0F6EF206>) |
| 1022:15e3 | 1458:a194 | AMD              | Family 17h/19h/1ah HD Audio Contr... | 565   | snd_hda... | [0D0A62D437](<Desktop/Gigabyte Technology/B650M/B650M D3HP/09BE719645F6/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/0D0A62D437>) |
| 1002:1637 | 1043:8809 | AMD              | Renoir Radeon High Definition Aud... | 562   | snd_hda... | [989A72852C](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PLUS/4495A9F18FCB/ZORIN-17/6.8.0-50-GENERIC/X86_64/989A72852C>) |

### Storage (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1217:8231 | 1028:0493 | O2 Micro         | Integrated MS/MSPRO Controller       | 290   |            | [46C2760E4E](<Notebook/Dell/Latitude/Latitude E6420/27A84812735F/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/46C2760E4E>) |
| 104c:803b | 1025:011f | Texas Instrum... | PCIxx12 Flash Media Controller       | 180   | tifm_7xx1  | [864E664760](<Notebook/Acer/Extensa/Extensa 5220/847E4B65162A/LMDE-6/6.1.0-28-686/I686/864E664760>) |
| 1217:8331 | 1028:0494 | O2 Micro         | O2 Flash Memory Card                 | 147   |            | [C3A5CF03A9](<Notebook/Dell/Latitude/Latitude E6520/E350D4696CE5/FEDORA-41/6.12.4-200.FC41.X86_64/X86_64/C3A5CF03A9>) |
| 1217:7130 | 1179:ff50 | O2 Micro         | Integrated MS/xD Controller          | 88    |            | [3174FC3F7E](<Notebook/Toshiba/Satellite/Satellite P300/0CDBF2DE5F7B/ZORIN-17/6.8.0-50-GENERIC/X86_64/3174FC3F7E>) |
| 1217:8331 | 1028:049a | O2 Micro         | O2 Flash Memory Card                 | 75    |            | [5DD3CBC6A3](<Notebook/Dell/Latitude/Latitude E5520/8E74C46DF70D/KALI-2024.3/6.11.2-AMD64/X86_64/5DD3CBC6A3>) |
| 104c:803b | 1179:ff00 | Texas Instrum... | PCIxx12 Flash Media Controller       | 74    | tifm_7xx1  | [655A407DD2](<Notebook/Toshiba/Satellite/Satellite M100/73D5B6123FE1/LMDE-6/6.1.0-27-686/I686/655A407DD2>) |
| 1217:7130 | 10cf:143d | O2 Micro         | Integrated MS/xD Controller          | 73    |            | [7AA92E6DAF](<Notebook/Fujitsu Siemens/LIFEBOOK/LIFEBOOK S7220/BB6DF8A26F70/ZORIN-16/5.15.0-125-GENERIC/X86_64/7AA92E6DAF>) |
| 1217:8330 | 1028:04a3 | O2 Micro         | OZ600 MS/xD Controller               | 73    |            | [B5825AB65B](<Notebook/Dell/Precision/Precision M4600/6FB518DD8032/LINUXMINT-21.3/6.8.0-49-GENERIC/X86_64/B5825AB65B>) |
| 1217:8331 | 1028:049b | O2 Micro         | O2 Flash Memory Card                 | 72    |            | [E1A5C8FD29](<Notebook/Dell/Latitude/Latitude E5420/3CBB5C8A0106/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/E1A5C8FD29>) |
| 104c:803b | 104d:9005 | Texas Instrum... | PCIxx12 Flash Media Controller       | 67    | tifm_7xx1  | [25EC238DEC](<Notebook/Sony/VGN-FZ11/VGN-FZ11M/80040909FA74/MX-23/6.1.0-28-686-PAE/I686/25EC238DEC>) |
| 104c:803b | 1179:ff02 | Texas Instrum... | PCIxx12 Flash Media Controller       | 64    | tifm_7xx1  | [9A071C6521](<Notebook/Toshiba/Satellite/Satellite A200/858974F4ACD0/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/9A071C6521>) |
| 1217:7130 | 1025:013c | O2 Micro         | Integrated MS/xD Controller          | 57    |            | [F522D51182](<Notebook/Acer/Extensa/Extensa 5630/AFC17E6B9EDB/LINUXMINT-21/5.15.0-130-GENERIC/X86_64/F522D51182>) |
| 104c:803b | 1179:ff10 | Texas Instrum... | PCIxx12 Flash Media Controller       | 50    | tifm_7xx1  | [F95E411124](<Notebook/Toshiba/Satellite/Satellite A100/AC99315BC1FF/ROSA-2016.1/4.9.155-NRJ-DESKTOP-1ROSA-I586/I686/F95E411124>) |
| 1283:8211 | 1043:8138 | Integrated Te... | ITE 8211F Single Channel UDMA 133    | 49    | pata_it... | [BD58FBF1E1](<Desktop/ASUSTek Computer/P5/P5LD2/4E7D2FD2547F/LINUXMINT-21.2/5.15.0-76-GENERIC/X86_64/BD58FBF1E1>) |
| 1217:7130 | 10cf:14d6 | O2 Micro         | Integrated MS/xD Controller          | 44    |            | [B41DA32715](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK E780/455604315DAA/KUBUNTU-24.04/6.8.0-48-GENERIC/X86_64/B41DA32715>) |
| 1217:8231 | 1028:04a9 | O2 Micro         | Integrated MS/MSPRO Controller       | 44    |            | [B93B3B88D1](<Notebook/Dell/Latitude/Latitude E6220/8721BA59F35E/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/B93B3B88D1>) |
| 104c:803b | 104d:902d | Texas Instrum... | PCIxx12 Flash Media Controller       | 41    | tifm_7xx1  | [0ED147C4FB](<Notebook/Sony/VGN-NR21/VGN-NR21E_S/EBA045FFBA41/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/0ED147C4FB>) |
| 104c:803b | 104d:9015 | Texas Instrum... | PCIxx12 Flash Media Controller       | 40    | tifm_7xx1  | [29A2C1F90E](<Notebook/Sony/VGN-CR21/VGN-CR21S_W/5909D707E3B2/ZORIN-17/6.8.0-50-GENERIC/X86_64/29A2C1F90E>) |
| 1217:8330 | 1028:04a4 | O2 Micro         | OZ600 MS/xD Controller               | 34    |            | [071A23FB58](<Notebook/Dell/Precision/Precision M6600/6320B38B7B61/MANJARO-24.2.1/6.12.4-1-MANJARO/X86_64/071A23FB58>) |
| 104c:803b | 1028:02ef | Texas Instrum... | PCIxx12 Flash Media Controller       | 32    | tifm_7xx1  | [84F6A1C29F](<Notebook/Dell/Precision/Precision M6500/FC09A0B44983/UBUNTU-BUDGIE-24.04/6.8.0-48-GENERIC/X86_64/84F6A1C29F>) |
| 104c:803b | 1179:ff03 | Texas Instrum... | PCIxx12 Flash Media Controller       | 28    | tifm_7xx1  | [A07857C808](<Notebook/Toshiba/Satellite/Satellite P200/503912185CC9/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A07857C808>) |
| 104c:803b | 1025:0107 | Texas Instrum... | PCIxx12 Flash Media Controller       | 26    | tifm_7xx1  | [AC85F8E229](<Notebook/Acer/Aspire/Aspire 9420/08CE085EDF3A/ZORIN-17/6.5.0-25-GENERIC/X86_64/AC85F8E229>) |
| 1217:7130 | 1028:0273 | O2 Micro         | Integrated MS/xD Controller          | 26    |            | [E65FD8A402](<Notebook/Dell/Vostro/Vostro 1510/3D057773F881/UBUNTU-24.04/6.8.0-50-GENERIC/X86_64/E65FD8A402>) |
| 104c:803b | 103c:30aa | Texas Instrum... | PCIxx12 Flash Media Controller       | 25    | tifm_7xx1  | [FCEDE7C172](<Notebook/Hewlett-Packard/Compaq/Compaq nc6320/E36EDCA6128F/PEPPERMINT-12/6.1.0-21-686-PAE/I686/FCEDE7C172>) |
| 104c:803b | 104d:9016 | Texas Instrum... | PCIxx12 Flash Media Controller       | 25    | tifm_7xx1  | [D41CBF35F9](<Notebook/Sony/VGN-AR41/VGN-AR41S/A797934B2F04/ZORIN-17/6.8.0-47-GENERIC/X86_64/D41CBF35F9>) |
| 104c:803b | 1179:0001 | Texas Instrum... | PCIxx12 Flash Media Controller       | 25    | tifm_7xx1  | [1F1490F08A](<Notebook/Toshiba/Satellite/Satellite Pro U200/AD43028151F7/BLACKPANTHER-OS-18.1/5.15.85-DESKTOP-1BP/X86_64/1F1490F08A>) |
| 1077:2532 | 1077:015d | QLogic           | ISP2532-based 8Gb Fibre Channel t... | 25    | qla2xxx    | [40BB0B1415](<Server/Fujitsu/PRIMERGY/PRIMERGY RX200 S8/1DC23A737F38/DEBIAN-12/6.8.12-4-PVE/X86_64/40BB0B1415>) |
| 8086:54ff |           | Intel            | Alder Lake-N Universal Flash Stor... | 25    | ufshcd_pci | [DFD9D16913](<Notebook/Hewlett-Packard/Laptop/Laptop 15-fd0xxx/774F89FDB183/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/DFD9D16913>) |
| 104c:803b | 1025:0110 | Texas Instrum... | PCIxx12 Flash Media Controller       | 23    | tifm_7xx1  | [1B24527BDF](<Notebook/Acer/Extensa/Extensa 4210/4F660A23E929/DEBIAN-12/6.1.0-13-686-PAE/I686/1B24527BDF>) |
| 1217:8130 | 1028:02bc | O2 Micro         | Integrated MS/MSPRO/xD Controller    | 23    |            | [AC1C78D3A4](<Notebook/Dell/Vostro/Vostro 1520/F6CDACF91C01/ENDLESS-5.1.0/6.5.0-10-GENERIC/X86_64/AC1C78D3A4>) |
| 1217:8130 | 1179:ff50 | O2 Micro         | Integrated MS/MSPRO/xD Controller    | 22    |            | [27D3CF680A](<Notebook/Toshiba/QOSMIO/QOSMIO X505/32437AA627D4/ZORIN-17/6.5.0-44-GENERIC/X86_64/27D3CF680A>) |
| 104c:803b | 104d:81ef | Texas Instrum... | PCIxx12 Flash Media Controller       | 20    | tifm_7xx1  | [926EF7ABAA](<Notebook/Sony/VGN-FE41/VGN-FE41M/CDDED19FC7C9/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/926EF7ABAA>) |
| 104c:803b | 104d:81e6 | Texas Instrum... | PCIxx12 Flash Media Controller       | 18    | tifm_7xx1  | [78F33888AA](<Notebook/Sony/VGN-SZ38/VGN-SZ38GP_C/1B14AFACCD81/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/78F33888AA>) |
| 104c:803b | 1179:ff31 | Texas Instrum... | PCIxx12 Flash Media Controller       | 17    | tifm_7xx1  | [74A9B7015C](<Notebook/Toshiba/Satellite/Satellite P105/A347CD99816A/LMDE-6/6.1.0-27-686/I686/74A9B7015C>) |
| 104c:803b | 103c:30ad | Texas Instrum... | PCIxx12 Flash Media Controller       | 16    | tifm_7xx1  | [3A7873EFE4](<Notebook/Hewlett-Packard/Compaq/Compaq nc6400/199D172E6F9D/SOLUS-4.5/6.8.10-291.CURRENT/X86_64/3A7873EFE4>) |
| 104c:803b | 104d:9008 | Texas Instrum... | PCIxx12 Flash Media Controller       | 16    | tifm_7xx1  | [E6371D68A7](<Notebook/Sony/VGN-SZ7/VGN-SZ7RXN_C/2F3C16A12CB8/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/E6371D68A7>) |
| 1217:8130 | 1028:02eb | O2 Micro         | Integrated MS/MSPRO/xD Controller    | 16    |            | [1159E24F15](<Notebook/Dell/Studio/Studio 1747/9EB8B75CE903/KDE-NEON-24.04/6.8.0-45-GENERIC/X86_64/1159E24F15>) |
| 1217:8130 | 1028:041b | O2 Micro         | Integrated MS/MSPRO/xD Controller    | 14    |            | [D74513A21F](<Notebook/Dell/Studio/Studio 1749/44526C5008AC/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/D74513A21F>) |
| 104c:8033 | 1179:ff05 | Texas Instrum... | PCIxx21/PCIxx11 Flash Media Contr... | 13    | tifm_7xx1  | [616DBDFA63](<Notebook/Toshiba/Satellite/Satellite M70/9C7FB8CE8CA5/MX-21/5.10.0-9-686-PAE/I686/616DBDFA63>) |
| 104c:803b | 1025:011c | Texas Instrum... | PCIxx12 Flash Media Controller       | 13    | tifm_7xx1  | [2AE17ABD07](<Notebook/Acer/Extensa/Extensa 4220/B40D64E1CB26/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/2AE17ABD07>) |
| 104c:803b | 104d:8212 | Texas Instrum... | PCIxx12 Flash Media Controller       | 13    | tifm_7xx1  | [6FF4658440](<Notebook/Sony/VGN-N21/VGN-N21S_W/0579BEB19444/LINUXMINT-21.2/5.15.0-88-GENERIC/X86_64/6FF4658440>) |
| 104c:ac8f | 104d:8190 | Texas Instrum... | PCI7420/7620 SD/MS-Pro Controller    | 12    | tifm_7xx1  | [4619D1639E](<Notebook/Sony/VGN-FS315/VGN-FS315M/51FF4436A01A/XUBUNTU-18.04/4.15.0-29-GENERIC/I686/4619D1639E>) |
| 104c:803b | 1025:0112 | Texas Instrum... | PCIxx12 Flash Media Controller       | 11    | tifm_7xx1  | [3094B549C5](<Notebook/Acer/Aspire/Aspire 9300/84C4AB6FB9A7/LUBUNTU-20.04/5.4.0-165-GENERIC/X86_64/3094B549C5>) |
| 1217:7130 | 1028:0275 | O2 Micro         | Integrated MS/xD Controller          | 11    |            | [811CEF5FAC](<Notebook/Dell/Vostro/Vostro1710/05984B80D4CC/FEDORA-40/6.8.4-300.FC40.X86_64/X86_64/811CEF5FAC>) |
| 1217:7130 | 1462:3ff3 | O2 Micro         | Integrated MS/xD Controller          | 11    |            | [AE78FA3936](<Notebook/MSI/PR/PR600/F1C8AF2E4C16/ZORIN-17/6.5.0-26-GENERIC/X86_64/AE78FA3936>) |
| 104c:803b | 1025:0102 | Texas Instrum... | PCIxx12 Flash Media Controller       | 10    | tifm_7xx1  | [02813AB0F6](<Notebook/Acer/Aspire/Aspire 5600/7C28F487841A/UBUNTU-18.04/5.4.0-159-GENERIC/I686/02813AB0F6>) |
| 104c:803b | 103c:309f | Texas Instrum... | PCIxx12 Flash Media Controller       | 10    | tifm_7xx1  | [1B7C441369](<Notebook/Hewlett-Packard/Compaq/Compaq nx9420/081DAD125FC6/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/1B7C441369>) |
| 104c:803b | 103c:30a3 | Texas Instrum... | PCIxx12 Flash Media Controller       | 10    | tifm_7xx1  | [1A3426F4B6](<Notebook/Hewlett-Packard/Compaq/Compaq nw8440/5D1E60E29716/ARCH-ROLLING/6.12.8-ARCH1-1/X86_64/1A3426F4B6>) |
| 104c:803b | 17aa:207c | Texas Instrum... | PCIxx12 Flash Media Controller       | 10    | tifm_7xx1  | [2B158C1A28](<Notebook/Lenovo/ThinkPad/ThinkPad Z61m 94529JG/B1FE385E6033/MX-23/6.1.0-25-686-PAE/I686/2B158C1A28>) |
| 1077:2432 | 1077:0137 | QLogic           | ISP2432-based 4Gb Fibre Channel t... | 10    | qla2xxx    | [0516914D99](<Desktop/Gigabyte Technology/GA-880/GA-880GM-UD2H/2E9EEACBC93C/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/0516914D99>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:7901 | 1022:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 6065  | ahci       | [84DECD497D](<Desktop/BESSTAR Tech/HM/HM80/641CA314EE82/NOBARA-39/6.8.12-200.FSYNC.FC39.X86_64/X86_64/84DECD497D>) |
| 1022:43c8 | 1b21:1062 | AMD              | 400 Series Chipset SATA Controller   | 6025  | ahci       | [FDA84AF6B6](<Desktop/MSI/MS-7/MS-7A40/DC07AAAD39A3/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/FDA84AF6B6>) |
| 1022:43eb | 1b21:1062 | AMD              | 500 Series Chipset SATA Controller   | 4597  | ahci       | [69FF87B949](<Desktop/Gigabyte Technology/A520/A520 AORUS ELITE/81AB90394B6C/GENTOO-2.17/6.6.67-GENTOO/X86_64/69FF87B949>) |
| 1022:7901 | 1458:b002 | AMD              | FCH SATA Controller [AHCI mode]      | 2394  | ahci       | [A23FC83EDD](<Desktop/Gigabyte Technology/AB350/AB350-Gaming/B5A158869F92/GENTOO-2.17/6.6.67-GENTOO/X86_64/A23FC83EDD>) |
| 1022:43f6 | 1b21:1062 | AMD              | 600 Series Chipset SATA Controller   | 1712  | ahci       | [1FF9C9F7CB](<Desktop/MSI/MS-7/MS-7E26/771CE98DF000/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/1FF9C9F7CB>) |
| 8086:8c02 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 1583  | ahci       | [C4C2F7FE89](<Desktop/ASUSTek Computer/All/All Series/09DD706491D9/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/C4C2F7FE89>) |
| 1022:7901 | 1043:8747 | AMD              | FCH SATA Controller [AHCI mode]      | 1570  | ahci       | [CF7D50FAE1](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-K II/24E629ECD716/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/CF7D50FAE1>) |
| 1022:43b8 | 1b21:1062 | AMD              | A320 Chipset SATA Controller [AHC... | 1526  | ahci       | [A6F434CC49](<Desktop/Biostar/A320/A320MH/0E6DEFD22F3E/ARCH-ROLLING/6.12.8-ARCH1-1/X86_64/A6F434CC49>) |
| 1b21:0612 | 1b21:1060 | ASMedia Techn... | ASM1061/ASM1062 Serial ATA Contro... | 1460  | ahci       | [30EF92BBFC](<Desktop/MSI/MS-7/MS-7A70/E5129624DA6A/MX-23/6.1.0-28-AMD64/X86_64/30EF92BBFC>) |
| 8086:31e3 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1450  | ahci       | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:a102 | 1043:8694 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 1404  | ahci       | [FF2E84AB02](<Desktop/ASUSTek Computer/H110/H110M-E-M.2/4907896789F3/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/FF2E84AB02>) |
| 1022:43b7 | 1b21:1062 | AMD              | 300 Series Chipset SATA Controller   | 1394  | ahci       | [A23FC83EDD](<Desktop/Gigabyte Technology/AB350/AB350-Gaming/B5A158869F92/GENTOO-2.17/6.6.67-GENTOO/X86_64/A23FC83EDD>) |
| 1b21:0612 | 1849:0612 | ASMedia Techn... | ASM1061/ASM1062 Serial ATA Contro... | 1246  | ahci       | [0D776677A7](<Desktop/ASRock/AB350/AB350 Pro4/801653C6BD48/KUBUNTU-24.10/6.11.0-13-GENERIC/X86_64/0D776677A7>) |
| 1002:4391 | 1458:b002 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 1218  | ahci       | [617C102331](<Desktop/Gigabyte Technology/GA-MA770/GA-MA770T-UD3/8220651D2E86/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/617C102331>) |
| 1002:4390 | 1458:b002 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 1169  | ahci       | [CD33AA866C](<Desktop/Gigabyte Technology/GA-970/GA-970A-D3/0098B4B2B0F6/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/CD33AA866C>) |
| 1022:7901 | 1849:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 1153  | ahci       | [0D776677A7](<Desktop/ASRock/AB350/AB350 Pro4/801653C6BD48/KUBUNTU-24.10/6.11.0-13-GENERIC/X86_64/0D776677A7>) |
| 1002:4391 | 1043:84dd | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 1141  | ahci       | [BADFE83ED3](<Desktop/ASUSTek Computer/M5A97/M5A97 LE R2.0/25917080F8AD/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/BADFE83ED3>) |
| 8086:8c02 | 1458:b005 | Intel            | 8 Series/C220 Series Chipset Fami... | 1079  | ahci       | [27053CA724](<Desktop/Gigabyte Technology/B85/B85M-D3H/C42183E26685/DEBIAN-12/6.1.0-28-AMD64/X86_64/27053CA724>) |
| 8086:1c02 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 1074  | ahci       | [2B21C81822](<Desktop/ASUSTek Computer/P8Z68-V/P8Z68-V LX/4130A0D4D84A/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/2B21C81822>) |
| 1002:4390 | 1043:8389 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 1070  | ahci       | [02A12F94E1](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX V2/63B73941E98E/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/02A12F94E1>) |
| 1b21:0612 | 1043:84b7 | ASMedia Techn... | ASM1061/ASM1062 Serial ATA Contro... | 1052  | ahci       | [E6075ADFC0](<Desktop/ASUSTek Computer/CM6630/CM6630_CM6730_CM6830/64DE23EC7F13/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/E6075ADFC0>) |
| 10de:0ab9 | 10de:cb79 | Nvidia           | MCP79 AHCI Controller                | 1029  | ahci       | [DE39DE3147](<Notebook/Apple/MacBookPro5/MacBookPro5,5/AE9A7F9028B1/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/DE39DE3147>) |
| 8086:1e02 | 1043:84ca | Intel            | 7 Series/C210 Series Chipset Fami... | 964   | ahci       | [69679C9A35](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/05DEE4E22315/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/69679C9A35>) |
| 8086:a282 | 1043:8694 | Intel            | 200 Series PCH SATA controller [A... | 928   | ahci       | [10FD8EF9DD](<Desktop/ASUSTek Computer/TUF/TUF Z370-PLUS GAMING II/76981D36E1E4/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/10FD8EF9DD>) |
| 8086:5ae3 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 903   | ahci       | [D7DE8BEE56](<Convertible/Positivo/C464/C464C/3233D7E527FE/ZORIN-17/6.8.0-50-GENERIC/X86_64/D7DE8BEE56>) |
| 8086:a282 | 1458:b005 | Intel            | 200 Series PCH SATA controller [A... | 885   | ahci       | [A49FDE4DF3](<Desktop/Gigabyte Technology/B365M/B365M DS3H/406A103EBD76/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/A49FDE4DF3>) |
| 8086:1e03 | 8086:7270 | Intel            | 7 Series Chipset Family 6-port SA... | 878   | ahci       | [AE5A71DDE0](<Notebook/Apple/MacBookPro9/MacBookPro9,1/04AD065CAD6F/LINUXMINT-20.3/5.4.0-204-GENERIC/X86_64/AE5A71DDE0>) |
| 8086:1e03 | 17aa:3977 | Intel            | 7 Series Chipset Family 6-port SA... | 865   | ahci       | [516947871E](<Notebook/Lenovo/IdeaPad/IdeaPad Z400 VIWZ1/2725496AFD2D/ZORIN-17/6.8.0-50-GENERIC/X86_64/516947871E>) |
| 8086:a102 | 1458:b005 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 801   | ahci       | [AD40DB7F67](<Desktop/Gigabyte Technology/Z170X-Gaming/Z170X-Gaming 7/4DE1A28702A7/ZORIN-17/6.8.0-50-GENERIC/X86_64/AD40DB7F67>) |
| 144d:a801 | 144d:a801 | Samsung Elect... | S4LN058A01[SSUBX] AHCI SSD Contro... | 778   | ahci       | [C226449CA2](<Notebook/Apple/MacBookPro12/MacBookPro12,1/B9F35BD8D62D/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/C226449CA2>) |
| 1b21:0612 | 1043:858d | ASMedia Techn... | ASM1061/ASM1062 Serial ATA Contro... | 735   | ahci       | [7FEA0BB2A1](<Desktop/ASUSTek Computer/PRIME/PRIME B650M-A AX II/561F5C99198B/FEDORA-40/6.10.5-200.FC40.X86_64/X86_64/7FEA0BB2A1>) |
| 8086:a352 | 1043:8694 | Intel            | Cannon Lake PCH SATA AHCI Controller | 710   | ahci       | [D6A1F13AD7](<Desktop/ASUSTek Computer/PRIME/PRIME H310I-PLUS/0F9C63DCE4D3/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/D6A1F13AD7>) |
| 1022:43b5 | 1b21:1062 | AMD              | X370 Series Chipset SATA Controller  | 708   | ahci       | [86C0B9C6D4](<Desktop/ASUSTek Computer/PRIME/PRIME X370-A/F47BA23D67F5/UBUNTU-22.04/5.15.0-130-GENERIC/X86_64/86C0B9C6D4>) |
| 1022:7901 | 1043:87c0 | AMD              | FCH SATA Controller [AHCI mode]      | 687   | ahci       | [4233786E9F](<Desktop/ASUSTek Computer/PRIME/PRIME B450-PLUS/82EDCDE4B749/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/4233786E9F>) |
| 8086:1c03 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 659   | ahci       | [705713446F](<Notebook/Apple/MacBookAir4/MacBookAir4,1/0A918C18E48D/MANJARO/6.12.4-1-MANJARO/X86_64/705713446F>) |
| 8086:9c03 | 17aa:3978 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 609   | ahci       | [666751867C](<Notebook/Lenovo/G50-70/G50-70 20351/1934A760E88D/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/666751867C>) |
| 8086:a352 | 1458:b005 | Intel            | Cannon Lake PCH SATA AHCI Controller | 608   | ahci       | [639EB0E4FC](<Desktop/Gigabyte Technology/H370M/H370M D3H GSM/D391F95DF729/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/639EB0E4FC>) |
| 8086:8c82 | 1043:8534 | Intel            | 9 Series Chipset Family SATA Cont... | 599   | ahci       | [BA47136806](<Desktop/ASUSTek Computer/All/All Series/651BB16BD9C9/UBUNTU-24.10/6.12.3-061203-GENERIC/X86_64/BA47136806>) |
| 1022:43c8 | 1849:43c8 | AMD              | 400 Series Chipset SATA Controller   | 583   | ahci       | [F0FAC8B3F2](<Desktop/ASRock/B450/B450 Pro4/900DCDF409D3/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/F0FAC8B3F2>) |
| 1022:7901 | 1849:ffff | AMD              | FCH SATA Controller [AHCI mode]      | 570   | ahci       | [A049693DCF](<Desktop/ASRock/X570M/X570M Pro4/58C6CFF9F5D0/LINUXMINT-21.3/5.15.0-130-GENERIC/X86_64/A049693DCF>) |
| 8086:1e02 | 1458:b005 | Intel            | 7 Series/C210 Series Chipset Fami... | 562   | ahci       | [E22CDDB5FD](<Desktop/Gigabyte Technology/H77/H77N-WIFI/1984A05C643F/FEDORA-42/6.13.0-0.RC4.36.FC42.X86_64/X86_64/E22CDDB5FD>) |
| 8086:7ae2 | 1043:8694 | Intel            | Alder Lake-S PCH SATA Controller ... | 555   | ahci       | [F8371D3425](<Desktop/ASUSTek Computer/PRIME/PRIME B660M-A WIFI D4/08AB6A0E635D/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/F8371D3425>) |
| 8086:43d2 | 1043:8694 | Intel            | 500 Series Chipset Family SATA AH... | 537   | ahci       | [63751B6A23](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z590-E GAMING WIFI/802DD0234B9E/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/63751B6A23>) |
| 8086:1e02 | 1028:0577 | Intel            | 7 Series/C210 Series Chipset Fami... | 525   | ahci       | [734E205226](<Desktop/Dell/OptiPlex/OptiPlex 7010/1CD0F71C8C43/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/734E205226>) |
| 8086:a0d3 |           | Intel            | Tiger Lake-LP SATA Controller        | 520   | ahci       | [A5D99B38FE](<Desktop/AMI/Intel/Intel/17B15FAF0DE0/FEDORA-40/6.12.5-100.FC40.X86_64/X86_64/A5D99B38FE>) |
| 1002:4391 | 1849:4391 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 518   | ahci       | [8EDA0B8FBF](<Desktop/ASRock/970M/970M Pro3/7CFC618F7557/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/8EDA0B8FBF>) |
| 1b4b:9172 | 1458:b000 | Marvell Techn... | 88SE9172 SATA 6Gb/s Controller       | 513   | ahci       | [381B6FC010](<Desktop/Gigabyte Technology/Z97/Z97X-UD5H/5500A52DF6D9/ZORIN-17/6.8.0-50-GENERIC/X86_64/381B6FC010>) |
| 8086:2929 | 17aa:20f8 | Intel            | 82801IBM/IEM (ICH9M/ICH9M-E) 4 po... | 504   | ahci       | [0C0F6EF206](<Notebook/Lenovo/ThinkPad/ThinkPad SL400 2743A48/24276C7B5960/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/0C0F6EF206>) |
| 1022:7801 | 1849:7801 | AMD              | FCH SATA Controller [AHCI mode]      | 499   | ahci       | [338593F255](<Desktop/ASRock/QC5000/QC5000-ITX-PH/D66CBF70B2EC/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/338593F255>) |
| 1022:7801 | 1458:b002 | AMD              | FCH SATA Controller [AHCI mode]      | 492   | ahci       | [0AF9E3885F](<Desktop/Gigabyte Technology/F2/F2A88XM-D3H/B705A7B35AA1/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/0AF9E3885F>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1002:439c | 1458:5002 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 1898  | pata_at... | [617C102331](<Desktop/Gigabyte Technology/GA-MA770/GA-MA770T-UD3/8220651D2E86/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/617C102331>) |
| 8086:27df | 1043:8179 | Intel            | 82801G (ICH7 Family) IDE Controller  | 1427  | pata_acpi  | [61C106BD12](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX2-GB/B37417979A6E/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/61C106BD12>) |
| 1002:439c | 1043:8389 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 1310  | pata_at... | [02A12F94E1](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX V2/63B73941E98E/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/02A12F94E1>) |
| 8086:27c0 | 1458:b002 | Intel            | NM10/ICH7 Family SATA Controller ... | 1099  | pata_acpi  | [D4592A5F61](<Desktop/Gigabyte Technology/G41/G41MT-S2PT/AF9C7E0168B7/UBUNTU-24.10/6.11.0-13-GENERIC/X86_64/D4592A5F61>) |
| 8086:27c0 | 1043:8179 | Intel            | NM10/ICH7 Family SATA Controller ... | 1057  | pata_acpi  | [61C106BD12](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX2-GB/B37417979A6E/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/61C106BD12>) |
| 197b:2363 | 1458:b000 | JMicron Techn... | JMB363 SATA/IDE Controller           | 831   | ahci       | [7D033B5974](<Desktop/Gigabyte Technology/965/965GM-S2/322F3D6D1870/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/7D033B5974>) |
| 8086:1c00 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 799   | pata_acpi  | [B3B2DF2FE7](<Desktop/ASUSTek Computer/P8H61-MX/P8H61-MX USB3/E2DA6937433E/UBUNTU-24.04/6.5.0-9-GENERIC/X86_64/B3B2DF2FE7>) |
| 8086:1c08 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 799   | pata_acpi  | [B3B2DF2FE7](<Desktop/ASUSTek Computer/P8H61-MX/P8H61-MX USB3/E2DA6937433E/UBUNTU-24.04/6.5.0-9-GENERIC/X86_64/B3B2DF2FE7>) |
| 1002:439c | 1849:439c | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 782   | pata_at... | [8EDA0B8FBF](<Desktop/ASRock/970M/970M Pro3/7CFC618F7557/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/8EDA0B8FBF>) |
| 8086:1c08 | 1458:b002 | Intel            | 6 Series/C200 Series Chipset Fami... | 697   | pata_acpi  | [58BE9BACFD](<Desktop/Gigabyte Technology/H61/H61M-S2PV/0261B0DCD705/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/58BE9BACFD>) |
| 8086:3a20 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 656   | pata_acpi  | [3269BF4415](<Desktop/ASUSTek Computer/P6T/P6T SE/86190855C748/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/3269BF4415>) |
| 8086:3a26 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 656   | pata_acpi  | [3269BF4415](<Desktop/ASUSTek Computer/P6T/P6T SE/86190855C748/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/3269BF4415>) |
| 8086:27c0 | 1849:27c0 | Intel            | NM10/ICH7 Family SATA Controller ... | 622   | ata_pii... | [9B8BA4CB2C](<Desktop/ASRock/G31/G31M-S/B3DA2B9DAB10/PUPPY-9/5.4.53/X86_64/9B8BA4CB2C>) |
| 10de:03f6 | 1849:03f6 | Nvidia           | MCP61 SATA Controller                | 600   | sata_nv... | [CB76400A00](<Desktop/ASRock/N68-S/N68-S UCC/3C232072D095/NEPTUNE-8.1/6.1.0-18-AMD64/X86_64/CB76400A00>) |
| 8086:27df | 1849:27df | Intel            | 82801G (ICH7 Family) IDE Controller  | 599   | ata_pii... | [9B8BA4CB2C](<Desktop/ASRock/G31/G31M-S/B3DA2B9DAB10/PUPPY-9/5.4.53/X86_64/9B8BA4CB2C>) |
| 10de:03ec | 1849:03ec | Nvidia           | MCP61 IDE                            | 550   | pata_am... | [CB76400A00](<Desktop/ASRock/N68-S/N68-S UCC/3C232072D095/NEPTUNE-8.1/6.1.0-18-AMD64/X86_64/CB76400A00>) |
| 197b:2363 | 1043:824f | JMicron Techn... | JMB363 SATA/IDE Controller           | 498   | ahci       | [12D33EE44D](<Desktop/ASUSTek Computer/P7P55D/P7P55D DELUXE/A9FD80849547/LINUXMINT-22.1/6.8.0-49-GENERIC/X86_64/12D33EE44D>) |
| 197b:2368 | 1458:b000 | JMicron Techn... | JMB368 IDE controller                | 440   | pata_jm... | [244BA13E5E](<Desktop/Gigabyte Technology/EP45/EP45-UD3LR/968077F99E6A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/244BA13E5E>) |
| 8086:2926 | 1043:8277 | Intel            | 82801I (ICH9 Family) 2 port SATA ... | 427   | ata_pii... | [241C643172](<Desktop/ASUSTek Computer/P5E-VM/P5E-VM HDMI/5CF7197BE3AE/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/241C643172>) |
| 8086:1e00 | 1458:b005 | Intel            | 7 Series/C210 Series Chipset Fami... | 414   | pata_acpi  | [139B1D261D](<Desktop/Gigabyte Technology/B75/B75M-D3H/1C75C0A003F1/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/139B1D261D>) |
| 8086:1e08 | 1458:b002 | Intel            | 7 Series/C210 Series Chipset Fami... | 414   | pata_acpi  | [139B1D261D](<Desktop/Gigabyte Technology/B75/B75M-D3H/1C75C0A003F1/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/139B1D261D>) |
| 8086:1c00 | 1458:b005 | Intel            | 6 Series/C200 Series Chipset Fami... | 396   | pata_acpi  | [2EF34839F4](<Desktop/Gigabyte Technology/H61/H61M-DS2/29D58848E162/ZORIN-17/6.5.0-18-GENERIC/X86_64/2EF34839F4>) |
| 8086:27c0 | 1043:2601 | Intel            | NM10/ICH7 Family SATA Controller ... | 377   | pata_acpi  | [62E974EBEE](<Desktop/ASUSTek Computer/P5/P5GZ-MX/399311230F6E/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/62E974EBEE>) |
| 1022:780c | 1849:780c | AMD              | FCH IDE Controller                   | 364   | pata_at... | [86FD341A89](<Desktop/ASRock/A75/A75 Extreme6/B47300C092A7/ZORIN-17/6.8.0-50-GENERIC/X86_64/86FD341A89>) |
| 1106:0415 | 1043:838f | VIA Technologies | VT6415 PATA IDE Host Controller      | 327   | pata_vi... | [987844D0B8](<Desktop/ASUSTek Computer/P8H67-M/P8H67-M PRO/D489C53AC6F3/ELEMENTARY-8/6.8.0-50-GENERIC/X86_64/987844D0B8>) |
| 8086:3b20 | 1043:8383 | Intel            | 5 Series/3400 Series Chipset 4 po... | 312   | pata_acpi  | [12D33EE44D](<Desktop/ASUSTek Computer/P7P55D/P7P55D DELUXE/A9FD80849547/LINUXMINT-22.1/6.8.0-49-GENERIC/X86_64/12D33EE44D>) |
| 8086:3b26 | 1043:8383 | Intel            | 5 Series/3400 Series Chipset 2 po... | 312   | pata_acpi  | [12D33EE44D](<Desktop/ASUSTek Computer/P7P55D/P7P55D DELUXE/A9FD80849547/LINUXMINT-22.1/6.8.0-49-GENERIC/X86_64/12D33EE44D>) |
| 8086:1c00 | 1458:b002 | Intel            | 6 Series/C200 Series Chipset Fami... | 306   | pata_acpi  | [ED0AD529D4](<Desktop/Gigabyte Technology/Z68/Z68AP-D3/C00617837B96/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/ED0AD529D4>) |
| 10de:03f6 | 1458:b002 | Nvidia           | MCP61 SATA Controller                | 303   | sata_nv... | [4040206002](<Desktop/Gigabyte Technology/M68/M68MT-S2/8DE8D73FA1FF/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/4040206002>) |
| 8086:1e00 | 1043:84ca | Intel            | 7 Series/C210 Series Chipset Fami... | 296   | pata_acpi  | [A4C88ACD7F](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/3A58D4CD81AB/ARCH-ROLLING/6.12.7-ZEN1-1-ZEN/X86_64/A4C88ACD7F>) |
| 8086:1e08 | 1043:84ca | Intel            | 7 Series/C210 Series Chipset Fami... | 296   | pata_acpi  | [A4C88ACD7F](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/3A58D4CD81AB/ARCH-ROLLING/6.12.7-ZEN1-1-ZEN/X86_64/A4C88ACD7F>) |
| 1002:439c | 1002:439c | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 292   | pata_at... | [0B63013A2A](<Desktop/ASUSTek Computer/M4A79T/M4A79T Deluxe/BE3CF50E786D/LINUXMINT-21.3/5.15.0-130-GENERIC/X86_64/0B63013A2A>) |
| 1022:780c | 1458:5002 | AMD              | FCH IDE Controller                   | 292   | pata_at... | [476CA1CA6D](<Desktop/Gigabyte Technology/GA-A55/GA-A55M-S2V/76D3138EF50B/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/476CA1CA6D>) |
| 8086:3a20 | 1458:b002 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 281   | pata_acpi  | [A27723C275](<Desktop/Gigabyte Technology/EP45/EP45-DS3R/398EA2406CC3/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/A27723C275>) |
| 8086:3a26 | 1458:b002 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 281   | pata_acpi  | [A27723C275](<Desktop/Gigabyte Technology/EP45/EP45-DS3R/398EA2406CC3/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/A27723C275>) |
| 8086:2921 | 1043:8277 | Intel            | 82801IB (ICH9) 2 port SATA Contro... | 277   | ata_pii... | [DFDB2CF6EE](<Desktop/ASUSTek Computer/P5/P5K/3FF6D4F51877/ZORIN-17/6.8.0-48-GENERIC/X86_64/DFDB2CF6EE>) |
| 197b:2368 | 1043:827e | JMicron Techn... | JMB368 IDE controller                | 275   | pata_jm... | [241C643172](<Desktop/ASUSTek Computer/P5E-VM/P5E-VM HDMI/5CF7197BE3AE/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/241C643172>) |
| 197b:2363 | 1043:81e4 | JMicron Techn... | JMB363 SATA/IDE Controller           | 273   | ahci       | [1026F82971](<Desktop/ASUSTek Computer/P5B-E/P5B-E Plus/0571CE0D8632/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-X86_64/X86_64/1026F82971>) |
| 8086:2850 | 106b:00a0 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) IDE C... | 260   | pata_acpi  | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 8086:27c0 | 8086:27c0 | Intel            | NM10/ICH7 Family SATA Controller ... | 254   | pata_acpi  | [55868F7894](<Desktop/Others/Others/Others/BB36C372A161/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/55868F7894>) |
| 8086:2850 | 17aa:20a6 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) IDE C... | 226   | pata_acpi  | [A7030C8AFC](<Notebook/Lenovo/ThinkPad/ThinkPad R61 8918DFG/31DA5DFD1FE3/XUBUNTU-22.04/6.8.0-50-GENERIC/X86_64/A7030C8AFC>) |
| 8086:27df | 8086:27df | Intel            | 82801G (ICH7 Family) IDE Controller  | 224   | pata_acpi  | [55868F7894](<Desktop/Others/Others/Others/BB36C372A161/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/55868F7894>) |
| 10de:03ec | 1458:5002 | Nvidia           | MCP61 IDE                            | 215   | pata_am... | [4439CAAB2A](<Desktop/Gigabyte Technology/M61/M61PME-S2P/0E48BD079D74/OPENMANDRIVA-24.07/6.10.1-DESKTOP-1OMV2490/X86_64/4439CAAB2A>) |
| 8086:27df | 1458:b001 | Intel            | 82801G (ICH7 Family) IDE Controller  | 215   | ata_pii... | [47CCE301DB](<Desktop/Gigabyte Technology/945/945P-S3/B47A67413332/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/47CCE301DB>) |
| 10de:03f6 | 1043:83a4 | Nvidia           | MCP61 SATA Controller                | 212   | sata_nv... | [8B53C864FE](<Desktop/ASUSTek Computer/M2N68-AM/M2N68-AM SE2/64710A5B1916/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/8B53C864FE>) |
| 8086:2926 | 1458:b002 | Intel            | 82801I (ICH9 Family) 2 port SATA ... | 210   | pata_acpi  | [BEAA8307E1](<Desktop/Gigabyte Technology/P35/P35-DS3L/8EEDF5361E7C/KUBUNTU-24.04/6.8.0-48-GENERIC/X86_64/BEAA8307E1>) |
| 10de:03ec | 1043:83a4 | Nvidia           | MCP61 IDE                            | 202   | pata_am... | [8B53C864FE](<Desktop/ASUSTek Computer/M2N68-AM/M2N68-AM SE2/64710A5B1916/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/8B53C864FE>) |
| 8086:29b6 | 1028:0211 | Intel            | 82Q35 Express PT IDER Controller     | 192   | pata_acpi  | [5DBB155AB6](<Desktop/Dell/OptiPlex/OptiPlex 755/A76EFDE815CB/LINUXMINT-21.3/5.15.0-130-GENERIC/X86_64/5DBB155AB6>) |
| 11ab:6101 | 11ab:6101 | Marvell Techn... | 88SE6101/6102 single-port PATA133... | 191   | pata_ma... | [F33D4BE91E](<Desktop/Intel/DG43GT/DG43GT AAE62768-300/9F12A9DAA38D/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/F33D4BE91E>) |
| 8086:3b20 | 1458:b002 | Intel            | 5 Series/3400 Series Chipset 4 po... | 191   | pata_acpi  | [1D3D66F3AC](<Desktop/Gigabyte Technology/P55/P55-UD3L/25684EA958F4/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/1D3D66F3AC>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 13511 | nvme       | [F10A2B06FD](<Notebook/HUAWEI/MACHD-WXX/MACHD-WXX9/FDA3F3F89271/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/F10A2B06FD>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980 (DRAM-less)  | 5964  | nvme       | [5B06A32FEA](<Notebook/Dell/XPS/XPS 13 9305/6C3197359FDA/PARROT-6.2/6.10.11-AMD64/X86_64/5B06A32FEA>) |
| 144d:a80a | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 4966  | nvme       | [27E1A6B6C4](<Notebook/Intel Client Systems/LAPBC/LAPBC710/51F1A07EBDE7/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/27E1A6B6C4>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 3239  | nvme       | [F43357E57A](<Notebook/Lenovo/ThinkPad/ThinkPad P51 20HJS0D201/C052B2ADD09F/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/F43357E57A>) |
| 15b7:5009 | 15b7:5009 | SanDisk          | Ultra 3D / WD PC SN530, IX SN530,... | 2871  | nvme       | [963FCDD477](<Notebook/Hewlett-Packard/ProBook/ProBook 455 G8 Notebook PC/8B9D95062911/OPENMANDRIVA-24.07/6.9.7-DESKTOP-1OMV2490/X86_64/963FCDD477>) |
| 15b7:5006 | 15b7:5006 | SanDisk          | Extreme Pro / WD Black SN750 / PC... | 2725  | nvme       | [C68A17F027](<Notebook/Lenovo/ThinkPad/ThinkPad T14s Gen 1 20UH002LUK/3790C38E2827/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/C68A17F027>) |
| 1c5c:174a | 1c5c:174a | SK hynix         | Gold P31/BC711/PC711 NVMe Solid S... | 2503  | nvme       | [77F98C4014](<Notebook/Dell/XPS/XPS 13 9305/5A3C91A8308D/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/77F98C4014>) |
| 8086:f1a8 | 8086:390d | Intel            | SSD 660P Series                      | 2341  | nvme       | [1AE33FB974](<Notebook/Acer/Predator/Predator PH315-52/FDF26A55E80E/BAZZITE-41/6.12.8-201.BAZZITE.FC41.X86_64/X86_64/1AE33FB974>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 2191  | nvme       | [BEAAF37101](<Desktop/ASUSTek Computer/PRIME/PRIME Z690M-PLUS D4/DA8C15B23752/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/BEAAF37101>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT (DRAM-less) NVM... | 2074  | nvme       | [7E994928CF](<Notebook/Samsung Electronics/940/940XGK/CB274195F873/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/7E994928CF>) |
| 1e0f:0001 | 1e0f:0001 | KIOXIA           | NVMe SSD Controller BG4 (DRAM-less)  | 1953  | nvme       | [C7F4EADA6C](<Notebook/Dell/Latitude/Latitude 5320/AA520611DCFE/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/C7F4EADA6C>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013-E13 PCIe3 NVMe Controller ... | 1630  | nvme       | [DBC98C4F9D](<Desktop/MSI/MS-7/MS-7D07/C77E6E673468/NOBARA-41/6.12.8-201.FSYNC.FC41.X86_64/X86_64/DBC98C4F9D>) |
| 15b7:5017 | 15b7:5017 | SanDisk          | WD Black SN770 / PC SN740 256GB /... | 1603  | nvme       | [657A86FEE0](<Notebook/Acer/Nitro/Nitro ANV15-51/7DDAD88FECE6/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/657A86FEE0>) |
| 1c5c:1327 | 1c5c:0000 | SK hynix         | BC501 NVMe Solid State Drive         | 1355  | nvme       | [88E5DA8B9D](<Notebook/Acer/Aspire/Aspire A514-53/AB357CF0BF61/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/88E5DA8B9D>) |
| 1179:011a | 1179:0001 | Toshiba Ameri... | XG6 NVMe SSD Controller              | 1349  | nvme       | [928B89625A](<Notebook/Lenovo/ThinkPad/ThinkPad L15 Gen 2 20X4S4LM01/2F9E509B2799/DEBIAN-12/6.1.0-27-AMD64/X86_64/928B89625A>) |
| 8086:f1aa | 8086:390f | Intel            | SSD 670p Series [Keystone Harbor]    | 1288  | nvme       | [F7C8A6C602](<Desktop/MSI/MS-7/MS-7C94/96058053E9EC/ENDEAVOUROS-ROLLING/6.6.69-1-LTS/X86_64/F7C8A6C602>) |
| c0a9:540a | c0a9:5021 | Micron/Crucia... | P2 [Nick P2] / P3 / P3 Plus NVMe ... | 1214  | nvme       | [B725853875](<Desktop/Gigabyte Technology/A520M/A520M K/8D8852C521BF/ARCH-ROLLING/6.12.8-ARCH1-1/X86_64/B725853875>) |
| 15b7:5003 | 15b7:5003 | SanDisk          | WD Blue SN500 / PC SN520 x2 M.2 2... | 1132  | nvme       | [50FF12C678](<Notebook/ASUSTek Computer/VivoBook/VivoBook S13 X330FN_S330FN/5D11FE94E7EF/DEBIAN-12/6.1.0-28-AMD64/X86_64/50FF12C678>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 1125  | nvme       | [FDA84AF6B6](<Desktop/MSI/MS-7/MS-7A40/DC07AAAD39A3/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/FDA84AF6B6>) |
| 15b7:5002 | 15b7:5002 | SanDisk          | Extreme Pro / WD Black 2018/SN750... | 1097  | nvme       | [1AE33FB974](<Notebook/Acer/Predator/Predator PH315-52/FDF26A55E80E/BAZZITE-41/6.12.8-201.BAZZITE.FC41.X86_64/X86_64/1AE33FB974>) |
| 1987:5016 | 1987:5016 | Phison Electr... | E16 PCIe4 NVMe Controller            | 1066  | nvme       | [5C8BB1062F](<Desktop/ASRock/X870E/X870E Taichi Lite/1DE31EA97D2B/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/5C8BB1062F>) |
| 2646:2263 | 2646:2263 | Kingston Tech... | A2000 NVMe SSD [SM2263EN]            | 1034  | nvme       | [01012C9B3B](<Desktop/ASUSTek Computer/ROG/ROG STRIX B365-F GAMING/20C2574A6786/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/01012C9B3B>) |
| 1c5c:1339 | 1c5c:0000 | SK hynix         | BC511 NVMe SSD                       | 1020  | nvme       | [33A984A2DF](<Notebook/Hewlett-Packard/EliteBook/EliteBook 845 G7 Notebook PC/FB463BF8E012/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/33A984A2DF>) |
| 1e4b:1202 | 1e4b:1202 | MAXIO Technol... | NVMe SSD Controller MAP1202 (DRAM... | 978   | nvme       | [F43945B8DD](<Desktop/Gigabyte Technology/B560M/B560M AORUS PRO/81CCD1D8C2D3/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/F43945B8DD>) |
| 2646:500d | 2646:500d | Kingston Tech... | OM3PDP3 NVMe SSD                     | 910   | nvme       | [D0DCE2F4FE](<Notebook/MSI/Sword/Sword 15 A11UD/546EC6D8F99C/FSL/6.12.7-ARCH1-1/X86_64/D0DCE2F4FE>) |
| 15b7:5011 | 15b7:5011 | SanDisk          | WD PC SN810 / Black SN850 NVMe SSD   | 906   | nvme       | [9018A2AC09](<Desktop/Dell/Precision/Precision 7960 Tower/8110AA44DF4F/RHEL-8/4.18.0-477.10.1.EL8_8.X86_64/X86_64/9018A2AC09>) |
| 144d:a80c | 144d:a801 | Samsung Elect... | NVMe SSD Controller S4LV008[Pascal]  | 901   | nvme       | [88B1C0C262](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING WIFI II/B8760FB55781/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/88B1C0C262>) |
| c0a9:540a | c0a9:540a | Micron/Crucia... | P2 [Nick P2] / P3 / P3 Plus NVMe ... | 879   | nvme       | [A2A616FA46](<Desktop/ASUSTek Computer/PRIME/PRIME Z690-A/D5C3CB3583FB/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/A2A616FA46>) |
| 8086:f1a6 | 8086:390b | Intel            | SSD DC P4101/Pro 7600p/760p/E 610... | 859   | nvme       | [FC246315B0](<Notebook/Dell/XPS/XPS 13 9360/E2287EB6796E/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/FC246315B0>) |
| 2646:5017 | 2646:5017 | Kingston Tech... | NV2 NVMe SSD [SM2267XT] (DRAM-less)  | 852   | nvme       | [72D4614EAF](<Desktop/MSI/PRO/PRO H510 DP21/6E7070B49E88/ZORIN-17/6.8.0-50-GENERIC/X86_64/72D4614EAF>) |
| 1179:0116 | 1179:0001 | Toshiba Ameri... | XG5 NVMe SSD Controller              | 817   | nvme       | [9352E7ED07](<All In One/Dell/OptiPlex/OptiPlex 7460 AIO/AAD8696E4652/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9352E7ED07>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 804   | nvme       | [105D641565](<All In One/Acidanthera/iMac18/iMac18,1/244EC7A3F367/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/105D641565>) |
| 1179:0113 | 1179:0001 | Toshiba Ameri... | BG3 x2 NVMe SSD Controller (DRAM-... | 801   | nvme       | [F10A0EDBDF](<Notebook/Lenovo/ThinkPad/ThinkPad 11e 5th Gen 20LRS02900/C75190EF9624/ARCH-ROLLING/6.12.8-ARCH1-1/X86_64/F10A0EDBDF>) |
| 15b7:501a | 15b7:501a | SanDisk          | Ultra 3D / WD Blue SN570 NVMe SSD... | 742   | nvme       | [381B6FC010](<Desktop/Gigabyte Technology/Z97/Z97X-UD5H/5500A52DF6D9/ZORIN-17/6.8.0-50-GENERIC/X86_64/381B6FC010>) |
| 144d:a80b | 144d:a80b | Samsung Elect... | NVMe SSD Controller PM9B1 (DRAM-l... | 739   | nvme       | [7373F056B3](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop M3604YA/CE1DCBE08790/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/7373F056B3>) |
| 1c5c:1959 | 1c5c:1959 | SK hynix         | Platinum P41/PC801 NVMe Solid Sta... | 714   | nvme       | [1C78D58AAB](<Notebook/Lenovo/ThinkPad/ThinkPad T14s Gen 4 21F8CTO1WW/A75ADDBD8E38/ARCH-ROLLING/6.12.8-ARCH1-1/X86_64/1C78D58AAB>) |
| 2646:5013 | 2646:5013 | Kingston Tech... | KC3000/FURY Renegade NVMe SSD [E18]  | 713   | nvme       | [30D29839DC](<Desktop/Gigabyte Technology/X670E/X670E AORUS MASTER/CC871162DE43/LINUXMINT-22.1/6.12.8/X86_64/30D29839DC>) |
| 2646:5008 | 2646:5008 | Kingston Tech... | A1000/U-SNS8154P3 x2 NVMe SSD        | 690   | nvme       | [1A9F6C2B88](<Desktop/Acer/Aspire/Aspire XC-830/D0549EF73FD6/ENDLESS-6.0.4/6.5.0-10-GENERIC/X86_64/1A9F6C2B88>) |
| 15b7:5030 | 15b7:5030 | Sandisk          | WD Black SN850X NVMe SSD             | 678   | nvme       | [F5E1468F62](<Notebook/Lenovo/ThinkPad/ThinkPad P14s Gen 3 21J50033GE/FD10BF8DCDAE/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/F5E1468F62>) |
| 2646:500f | 2646:500f | Kingston Tech... | NV1 NVMe SSD [SM2263XT] (DRAM-less)  | 633   | nvme       | [F0C2F6B640](<Convertible/Lenovo/Yoga/Yoga 520-14IKB 80YM/17B74590BE1D/ZORIN-17/6.8.0-50-GENERIC/X86_64/F0C2F6B640>) |
| 1344:5410 | 1344:0100 | Micron Techno... | 2200S NVMe SSD [Cassandra]           | 631   | nvme       | [F2DE07E3EF](<Notebook/Hewlett-Packard/Pavilion/Pavilion Gaming Laptop 15-ec1xxx/2670AE1AC8EA/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/F2DE07E3EF>) |
| c0a9:2263 | c0a9:2263 | Micron/Crucia... | P1 NVMe PCIe SSD[Frampton]           | 616   | nvme       | [849E3021F2](<Desktop/Gigabyte Technology/B450/B450 AORUS ELITE/BFC73DF76473/POP!_OS-22.04/6.6.10-76060610-GENERIC/X86_64/849E3021F2>) |
| 1344:5405 | 1344:0100 | Micron Techno... | 2300 NVMe SSD [Santana]              | 615   | nvme       | [D5B66FAF28](<Notebook/Hewlett-Packard/250/250 G8 Notebook PC/AFB9CE9F8E79/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/D5B66FAF28>) |
| 1344:5404 | 1344:1100 | Micron Techno... | 2210 NVMe SSD [Cobain]               | 610   | nvme       | [6BAB72D854](<Notebook/Lenovo/V15/V15 G3 IAP 82TT/0185BF067EBB/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/6BAB72D854>) |
| 1344:5407 | 1344:0100 | Micron Techno... | 3400 NVMe SSD [Hendrix]              | 576   | nvme       | [9ACB68FEFA](<Notebook/Lenovo/Slim/Slim Pro 7 14ARP8 83AX/43162561BEB2/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9ACB68FEFA>) |
| 8086:f1a5 | 8086:390a | Intel            | SSD 600P Series                      | 554   | nvme       | [1B1018C49E](<Notebook/Lenovo/ThinkPad/ThinkPad E570 20H5S0CF00/19288C8FC1B0/MX-23/6.12.6-1-LIQUORIX-AMD64/X86_64/1B1018C49E>) |
| 1344:5411 | 1344:1100 | Micron Techno... | 2450 NVMe SSD [HendrixV] (DRAM-less) | 550   | nvme       | [22702A56ED](<Notebook/Lenovo/IdeaPad/IdeaPad 5 15ABA7 82SG/35C8281C0493/TUXEDO-24.04/6.11.0-108013-TUXEDO/X86_64/22702A56ED>) |
| 126f:2262 | 126f:2262 | Silicon Motion   | SM2262/SM2262EN SSD Controller       | 544   | nvme       | [D19C6CFD10](<Desktop/ASUSTek Computer/PRIME/PRIME X570-P/944D114EB25D/LINUXMINT-22/6.8.0-49-GENERIC/X86_64/D19C6CFD10>) |
| 15b7:5008 | 15b7:5008 | SanDisk          | PC SN530 NVMe SSD (DRAM-less)        | 537   | nvme       | [25AF48DDF7](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5 14ALC05 82HU/F3B4772C45D9/FEDORA-40/6.8.5-301.FC40.X86_64/X86_64/25AF48DDF7>) |
| 1e0f:000c | 1e0f:0001 | KIOXIA           | NVMe SSD Controller BG5 (DRAM-less)  | 503   | nvme       | [12732AA34D](<Convertible/Dell/Inspiron/Inspiron 14 7430 2-in-1/3231F723D54C/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/12732AA34D>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9a0b | 8086:0000 | Intel            | Volume Management Device NVMe RAI... | 1190  | vmd        | [63B427416A](<Notebook/Hewlett-Packard/Laptop/Laptop 17-cn0xxx/56CBC8038B88/PARROT-6.2/6.10.11-AMD64/X86_64/63B427416A>) |
| 8086:467f | 8086:0000 | Intel            | Volume Management Device NVMe RAI... | 667   | vmd        | [5E3D055319](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X1504ZA_X1504ZA/218306087561/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/5E3D055319>) |
| 8086:467f | 1043:8694 | Intel            | Volume Management Device NVMe RAI... | 451   | vmd        | [A2A616FA46](<Desktop/ASUSTek Computer/PRIME/PRIME Z690-A/D5C3CB3583FB/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/A2A616FA46>) |
| 8086:a77f | 8086:0000 | Intel            | Volume Management Device NVMe RAI... | 397   | vmd        | [ADEC02CBC1](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop K3604VA_S3604VA/1639923317A5/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/ADEC02CBC1>) |
| 8086:9a0b | 8086:7270 | Intel            | Volume Management Device NVMe RAI... | 314   | vmd        | [58DE0987C9](<Notebook/Lenovo/IdeaPad/IdeaPad 3-15ITL6 82H8/5E575D80AEC4/BLACKPANTHER-OS-18.1/5.15.85-DESKTOP-1BP/X86_64/58DE0987C9>) |
| 8086:2822 | 1043:8694 | Intel            | SATA Controller [RAID mode]          | 282   | ahci       | [D6E8F1EE6C](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-P/DD926E3C669B/LMDE-6/6.11.10+BPO-AMD64/X86_64/D6E8F1EE6C>) |
| 8086:2822 | 1458:b005 | Intel            | SATA Controller [RAID mode]          | 242   | ahci       | [52F8310052](<Desktop/Gigabyte Technology/Z390/Z390 AORUS PRO/3DA736100CD9/MANJARO/6.6.65-1-MANJARO/X86_64/52F8310052>) |
| 8086:a77f | 1043:8882 | Intel            | Volume Management Device NVMe RAI... | 214   | vmd        | [826DC3E0F2](<Desktop/iBUYPOWER/Intel/Intel Core i7-14700F/0C1A211F1578/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/826DC3E0F2>) |
| 8086:2822 | 1028:05a4 | Intel            | SATA Controller [RAID mode]          | 210   | ahci       | [0133BA1278](<Desktop/Dell/OptiPlex/OptiPlex 9020/B8F5739E5C0D/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/0133BA1278>) |
| 8086:282a | 1028:0534 | Intel            | 82801 Mobile SATA Controller [RAI... | 197   | ahci       | [860E215DAF](<Notebook/Dell/Latitude/Latitude E6430/A0E982126F70/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/860E215DAF>) |
| 8086:282a | 1028:0493 | Intel            | 82801 Mobile SATA Controller [RAI... | 191   | ahci       | [46C2760E4E](<Notebook/Dell/Latitude/Latitude E6420/27A84812735F/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/46C2760E4E>) |
| 8086:282a | 1028:0233 | Intel            | 82801 Mobile SATA Controller [RAI... | 186   | ahci       | [D5DCFBC839](<Notebook/Dell/Latitude/Latitude E6400/429F04A48EEB/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/D5DCFBC839>) |
| 8086:282a | 1028:040a | Intel            | 82801 Mobile SATA Controller [RAI... | 160   | ahci       | [CE431D6DEF](<Notebook/Dell/Latitude/Latitude E6410/008BAA37A996/ZORIN-17/6.8.0-50-GENERIC/X86_64/CE431D6DEF>) |
| 8086:2822 | 1028:0420 | Intel            | SATA Controller [RAID mode]          | 159   | ahci       | [048527009C](<Desktop/Dell/OptiPlex/OptiPlex 780/464B9B861FE4/ZORIN-17/6.8.0-50-GENERIC/X86_64/048527009C>) |
| 8086:282a | 1025:1331 | Intel            | 82801 Mobile SATA Controller [RAI... | 152   | intel_n... | [D5A56DAB35](<Notebook/Acer/Nitro/Nitro AN515-54/EF283E0591B9/KALI-2024.4/6.11.2-AMD64/X86_64/D5A56DAB35>) |
| 8086:9a0b | 14c0:012d | Intel            | Volume Management Device NVMe RAI... | 149   | vmd        | [6A8E47F57B](<Notebook/Lenovo/ThinkBook/ThinkBook 14 G2 ITL 20VD/0C6CB3798539/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/6A8E47F57B>) |
| 8086:282a | 103c:84a6 | Intel            | 82801 Mobile SATA Controller [RAI... | 147   | ahci       | [0562D753F2](<Notebook/Hewlett-Packard/250/250 G7 Notebook PC/AA67D28E662F/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/0562D753F2>) |
| 8086:282a | 1028:05cb | Intel            | 82801 Mobile SATA Controller [RAI... | 123   | ahci       | [F9518BB970](<Notebook/Dell/Latitude/Latitude E7440/799F110E9BFD/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/F9518BB970>) |
| 8086:2822 | 1028:047e | Intel            | SATA Controller [RAID mode]          | 119   | ahci       | [EB43DEACF0](<Desktop/Dell/OptiPlex/OptiPlex 990/CFDD4C279189/LINUXMINT-21.3/5.15.0-1074-GCP/X86_64/EB43DEACF0>) |
| 8086:9a0b | 1025:1464 | Intel            | Volume Management Device NVMe RAI... | 115   | vmd        | [88B474ACAC](<Notebook/Acer/Aspire/Aspire A515-56/9A3914A5AA37/UBUNTU-24.10/6.11.0-13-GENERIC/X86_64/88B474ACAC>) |
| 8086:282a | 103c:1818 | Intel            | 82801 Mobile SATA Controller [RAI... | 114   | ahci       | [592CAB3725](<Notebook/Hewlett-Packard/ENVY/ENVY dv6/BBDD2F4A75B6/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/592CAB3725>) |
| 1022:43bd | 1b21:1062 | AMD              | FCH RAID Controller                  | 109   | ahci       | [6CA07FCDFB](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-A GAMING/FA638760780B/ARCH-ROLLING/6.12.4-ARCH1-1/X86_64/6CA07FCDFB>) |
| 1106:3249 | 1106:3249 | VIA Technologies | VT6421 IDE/SATA Controller           | 108   | sata_via   | [AD4A8C30FA](<Desktop/ASRock/H97M/H97M Pro4/7FEEF03E61DF/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/AD4A8C30FA>) |
| 8086:282a | 1028:0810 | Intel            | 82801 Mobile SATA Controller [RAI... | 108   | ahci       | [CE371A4F66](<Notebook/Dell/Inspiron/Inspiron 5570/3203336A2B46/UBUNTU-18.04/4.15.0-231-GENERIC/X86_64/CE371A4F66>) |
| 8086:282a | 17aa:380f | Intel            | 82801 Mobile SATA Controller [RAI... | 107   | ahci       | [B90F085315](<Notebook/Lenovo/IdeaPad/IdeaPad 320-15IKB 80XL/34FFC4D254FE/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/B90F085315>) |
| 8086:9a0b | 103c:881d | Intel            | Volume Management Device NVMe RAI... | 101   | vmd        | [6B8CE5850B](<Notebook/Hewlett-Packard/Laptop/Laptop 15-dw3xxx/6E11CAF9F10E/FEDORA-40/6.11.10-200.FC40.X86_64/X86_64/6B8CE5850B>) |
| 8086:2822 | 103c:1309 | Intel            | SATA Controller [RAID mode]          | 99    | ahci       | [689BB32B5C](<Desktop/Hewlett-Packard/Z400/Z400 Workstation/5A549A7CFEB6/DEBIAN-12/6.1.0-28-AMD64/X86_64/689BB32B5C>) |
| 8086:282a | 103c:86c9 | Intel            | 82801 Mobile SATA Controller [RAI... | 99    | ahci       | [062F7792DC](<Notebook/Hewlett-Packard/Laptop/Laptop 15s-fq1xxx/7369735EE530/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/062F7792DC>) |
| 8086:282a | 1028:062e | Intel            | 82801 Mobile SATA Controller [RAI... | 98    | ahci       | [18A5E779B9](<Notebook/Dell/Latitude/Latitude E7450/0088E8CFF869/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/18A5E779B9>) |
| 8086:282a | 1028:05be | Intel            | 82801 Mobile SATA Controller [RAI... | 94    | ahci       | [4198198679](<Notebook/Dell/Latitude/Latitude E6540/94FAB7E724C4/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/4198198679>) |
| 8086:467f | 1025:1616 | Intel            | Volume Management Device NVMe RAI... | 94    | vmd        | [A91C16B9C4](<Notebook/Acer/Aspire/Aspire A515-57/77DBFC2A6E52/LMDE-6/6.12.6-1-LIQUORIX-AMD64/X86_64/A91C16B9C4>) |
| 103c:323a | 103c:3245 | Hewlett-Packard  | Smart Array G6 controllers           | 92    | hpsa       | [B076CBF109](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/416C8912B3CC/DEBIAN/6.11.10-AMD64/X86_64/B076CBF109>) |
| 1022:7916 | 1022:7901 | AMD              | RS690 PCI to PCI Bridge (PCI Expr... | 91    | ahci       | [FE84B3D431](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/0FF6AE87406B/ORG.KDE.PLATFORM-5.15-21.08/6.12.1-ZEN1/X86_64/FE84B3D431>) |
| 8086:2822 | 1028:052c | Intel            | SATA Controller [RAID mode]          | 91    | ahci       | [2A4AD29EF8](<Desktop/Dell/OptiPlex/OptiPlex 9010/3FDC3C580FA7/DEBIAN/6.12.5-AMD64/X86_64/2A4AD29EF8>) |
| 8086:282a | 1028:0494 | Intel            | 82801 Mobile SATA Controller [RAI... | 91    | ahci       | [C3A5CF03A9](<Notebook/Dell/Latitude/Latitude E6520/E350D4696CE5/FEDORA-41/6.12.4-200.FC41.X86_64/X86_64/C3A5CF03A9>) |
| 8086:2822 | 103c:2a6f | Intel            | SATA Controller [RAID mode]          | 89    | ahci       | [E061C1CADC](<Desktop/Hewlett-Packard/FQ516AA-A2L/FQ516AA-A2L a6648f/303E05C1DFDD/FEDORA-39/6.7.4-200.FC39.X86_64/X86_64/E061C1CADC>) |
| 8086:282a | 1028:053c | Intel            | 82801 Mobile SATA Controller [RAI... | 86    | ahci       | [BBF6D05761](<Notebook/Dell/Latitude/Latitude E5430 non-vPro/D8CC8A46F7D5/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/BBF6D05761>) |
| 8086:282a | 1028:05bd | Intel            | 82801 Mobile SATA Controller [RAI... | 85    | ahci       | [8EF2131731](<Notebook/Dell/Latitude/Latitude E6440/A14DF7303D79/MX-23/6.1.0-28-AMD64/X86_64/8EF2131731>) |
| 8086:282a | 103c:8532 | Intel            | 82801 Mobile SATA Controller [RAI... | 85    | ahci       | [1E42EBB662](<Notebook/Hewlett-Packard/Laptop/Laptop 15-da1xxx/B1C92AABE077/UBUNTU-23.10/6.2.0-36-GENERIC/X86_64/1E42EBB662>) |
| 8086:467f | 1043:8882 | Intel            | Volume Management Device NVMe RAI... | 83    | vmd        | [AEA60B12C3](<Desktop/ASUSTek Computer/PRIME/PRIME B760-PLUS D4/907535587FC5/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/AEA60B12C3>) |
| 103c:3239 | 103c:21c0 | Hewlett-Packard  | Smart Array Gen9 Controllers         | 80    | hpsa       | [0B10A476DB](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/334260409128/DEBIAN/6.1.0-17-AMD64/X86_64/0B10A476DB>) |
| 8086:2822 | 1028:06b9 | Intel            | SATA Controller [RAID mode]          | 80    | ahci       | [A6858E47C5](<Desktop/Dell/OptiPlex/OptiPlex 7040/D7A84FA1BD75/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/A6858E47C5>) |
| 103c:323b | 103c:3354 | Hewlett-Packard  | Smart Array Gen8 Controllers         | 78    | hpsa       | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |
| 8086:282a | 1025:1264 | Intel            | 82801 Mobile SATA Controller [RAI... | 77    | ahci       | [9FD3688418](<Notebook/Acer/Nitro/Nitro AN515-52/C38CC2F8D5DC/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/9FD3688418>) |
| 8086:282a | 1028:06dc | Intel            | 82801 Mobile SATA Controller [RAI... | 77    | ahci       | [448C4C5D6E](<Notebook/Dell/Latitude/Latitude E7470/E6EA2D9D8448/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/448C4C5D6E>) |
| 8086:9a0b | 103c:8846 | Intel            | Volume Management Device NVMe RAI... | 77    | vmd        | [514CD1A8A0](<Notebook/Hewlett-Packard/EliteBook/EliteBook 850 G8 Notebook PC/6D5053E3849E/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/514CD1A8A0>) |
| 8086:282a | 1028:0535 | Intel            | 82801 Mobile SATA Controller [RAI... | 76    | ahci       | [D95AC73C9E](<Notebook/Dell/Latitude/Latitude E6530/3EB14946F97C/ZORIN-17/6.8.0-40-GENERIC/X86_64/D95AC73C9E>) |
| 8086:467f | 1025:161d | Intel            | Volume Management Device NVMe RAI... | 76    | vmd        | [FC29D8C8B1](<Notebook/Acer/Extensa/Extensa 215-55/F856833318DD/UBUNTU-24.10/6.11.0-13-GENERIC/X86_64/FC29D8C8B1>) |
| 8086:9a0b | 103c:880d | Intel            | Volume Management Device NVMe RAI... | 75    | vmd        | [A322D502B8](<Notebook/Hewlett-Packard/ZBook/ZBook Firefly 14 inch G8 Mobile Workstation PC/D01B35E1EEF7/MX-21/6.1.0-0.DEB11.21-AMD64/X86_64/A322D502B8>) |
| 1095:3114 | 1095:7114 | Silicon Image    | SiI 3114 [SATALink/SATARaid] Seri... | 73    | sata_sil   | [7EB3A63B51](<Desktop/ASUSTek Computer/M5A97/M5A97 R2.0/B18557B0A02C/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/7EB3A63B51>) |

### Storage/sas (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1d6b | 103c:1589 | Intel            | C602 chipset 4-Port SATA Storage ... | 108   | isci       | [DD5A66147D](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/05F06043C621/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/DD5A66147D>) |
| 1000:0086 | 103c:158b | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 83    | mpt3sas    | [C9A23E32F8](<Desktop/Hewlett-Packard/Z820/Z820 Workstation/9FEC03A5A744/GENTOO-2.17/6.11.11-GENTOO-HPZ820-MGREENE/X86_64/C9A23E32F8>) |
| 1000:0072 | 1000:3020 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 75    | mpt3sas    | [CA71A1B4D6](<Server/Supermicro/X9/X9DRH-7TF-7F-iTF-iF/EC8C275F9BA3/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/CA71A1B4D6>) |
| 8086:1d6b | 103c:158a | Intel            | C602 chipset 4-Port SATA Storage ... | 74    | isci       | [BA061366CC](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/19250B0EBE76/UBUNTU-MATE-24.10/6.11.0-1005-LOWLATENCY/X86_64/BA061366CC>) |
| 1000:0072 | 1028:1f1c | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 58    | mpt3sas    | [22CE816D89](<Server/Dell/PowerEdge/PowerEdge R630/D53C4C379040/ALMA-9.4/5.14.0-427.31.1.EL9_4.X86_64/X86_64/22CE816D89>) |
| 8086:1d6b | 1028:0497 | Intel            | C602 chipset 4-Port SATA Storage ... | 48    | isci       | [DFF53AF38F](<Desktop/Dell/Precision/Precision T3600/FF6AA0778F87/POP!_OS-24.04/6.9.3-76060903-GENERIC/X86_64/DFF53AF38F>) |
| 8086:1d6b | 103c:158b | Intel            | C602 chipset 4-Port SATA Storage ... | 48    | isci       | [C9A23E32F8](<Desktop/Hewlett-Packard/Z820/Z820 Workstation/9FEC03A5A744/GENTOO-2.17/6.11.11-GENTOO-HPZ820-MGREENE/X86_64/C9A23E32F8>) |
| 1000:0097 | 15d9:0808 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 37    | mpt3sas    | [3B1B28CFC7](<Server/Supermicro/Super/Super Server/CD7B912FA9C9/ROSA-12.5.1/6.6.27-GENERIC-3ROSA2021.1-X86_64/X86_64/3B1B28CFC7>) |
| 1000:0070 | 1000:3010 | LSI Logic / S... | SAS2004 PCI-Express Fusion-MPT SA... | 35    | mpt3sas    | [B66E4C113A](<Server/DEPO Computers/X8/X8DTU/732C5C269461/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/B66E4C113A>) |
| 1000:0087 | 1000:3020 | LSI Logic / S... | SAS2308 PCI-Express Fusion-MPT SAS-2 | 32    | mpt3sas    | [67FDA65F1A](<Desktop/MSI/MS-7/MS-7D30/45EA562A62D3/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/67FDA65F1A>) |
| 1000:0097 | 1028:0619 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 29    | mpt3sas    | [31A63822F9](<Desktop/Dell/Precision/Precision Tower 7910/BED0597F573A/UBUNTU-20.04/5.4.0-128-GENERIC/X86_64/31A63822F9>) |
| 8086:1d6b | 15d9:0636 | Intel            | C602 chipset 4-Port SATA Storage ... | 29    | isci       | [86B4E152AD](<Server/Supermicro/X9/X9DRW/D2C6B0237967/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/86B4E152AD>) |
| 8086:1d6b | 17aa:1026 | Intel            | C602 chipset 4-Port SATA Storage ... | 29    | isci       | [319423B279](<Desktop/Lenovo/ThinkStation/ThinkStation S30 43518H6/A99944236890/DEBIAN/6.1.0-26-AMD64/X86_64/319423B279>) |
| 1000:0086 | 15d9:0691 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 27    | mpt3sas    | [18E84EAC28](<Server/Supermicro/X9/X9DRD-7LN4F-X9DRD-EF/B9F8C820757C/SLACKWARE-15.0/6.1.106-UNRAID/X86_64/18E84EAC28>) |
| 8086:1d6b | 152d:899b | Intel            | C602 chipset 4-Port SATA Storage ... | 24    | isci       | [7E09CCDA22](<Server/ETegro Technologies/Hyperion/Hyperion RS125 G4/5259A72AB62F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/7E09CCDA22>) |
| 1000:0072 | 1028:1f1d | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 19    | mpt3sas    | [1E51138D9B](<Server/Dell/PowerEdge/PowerEdge T110 II/A23024949A59/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/1E51138D9B>) |
| 1000:0097 | 1000:30e0 | LSI Logic / S... | SAS3008 PCI-Express Fusion-MPT SAS-3 | 19    | mpt3sas    | [1128E2A9FA](<Server/Supermicro/X8/X8DTU/D85AACC2195B/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/1128E2A9FA>) |
| 8086:1d6b | 1734:11b6 | Intel            | C602 chipset 4-Port SATA Storage ... | 19    | isci       | [ED6A47B6F9](<Server/Fujitsu/PRIMERGY/PRIMERGY TX2540 M1/6D63F93EE5A2/DEBIAN-12/6.11.10+BPO-AMD64/X86_64/ED6A47B6F9>) |
| 1000:0087 | 1028:05a1 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 18    | mpt3sas    | [33C83F5D6F](<Desktop/Dell/Precision/Precision T7610/9FD1B6F0D3C9/ROCKY-8.10/4.18.0-553.22.1.EL8_10.X86_64/X86_64/33C83F5D6F>) |
| 8086:1d6b | 15d9:0626 | Intel            | C602 chipset 4-Port SATA Storage ... | 18    | isci       | [39232DFDE3](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/B0C1ED30C610/DEBIAN-12/6.1.0-25-AMD64/X86_64/39232DFDE3>) |
| 8086:1d6b | 1043:84ef | Intel            | C602 chipset 4-Port SATA Storage ... | 17    | isci       | [F922090BB9](<Server/ASUSTek Computer/RS700/RS700-X7-PS4/FFF77E8C316C/DEBIAN-12/6.8.4-2-PVE/X86_64/F922090BB9>) |
| 1000:0072 | 15d9:0400 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 15    | mpt3sas    | [C96E63C738](<Desktop/NetGear/ReadyDATA/ReadyDATA 5200/2E63D7AE698C/DEBIAN-11/5.15.107+TRUENAS/X86_64/C96E63C738>) |
| 1000:0087 | 1000:3060 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 15    | mpt3sas    | [61293BB319](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/821958141DC2/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/61293BB319>) |
| 1000:0072 | 1028:1f1e | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 14    | mpt3sas    | [36A5D324C6](<Desktop/Dell/Precision/Precision Tower 5810/C7D9A4DE0C7E/RHEL-9/5.14.0-503.14.1.EL9_5.X86_64/X86_64/36A5D324C6>) |
| 9005:028f | 103c:0602 | Adaptec          | Smart Storage PQI SAS                | 13    | smartpqi   | [D9F97B2071](<Server/HPE/ProLiant/ProLiant DL380 Gen10/6D60567E7E8D/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/D9F97B2071>) |
| 8086:1d6b | 15d9:062c | Intel            | C602 chipset 4-Port SATA Storage ... | 12    | isci       | [F84F7E7927](<Desktop/Supermicro/X9/X9DAi/D9A3CE1F1A0F/RHEL-8/4.18.0-553.16.1.EL8_10.X86_64/X86_64/F84F7E7927>) |
| 1000:0072 | 1000:3040 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 11    | mpt3sas    | [6BE191DAD3](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/213E402D3EC3/ZORIN-17/6.8.0-48-GENERIC/X86_64/6BE191DAD3>) |
| 19e5:a230 |           | Huawei Techno... | HiSilicon SAS 3.0 HBA                | 11    | hisi_sa... | [29BDE967FC](<Server/HUAWEI/TaiShan/TaiShan 2280 V2/2603C7B2E57E/UBUNTU-22.04/5.15.0-88-GENERIC/AARCH64/29BDE967FC>) |
| 8086:1d6b | 1028:0496 | Intel            | C602 chipset 4-Port SATA Storage ... | 11    | isci       | [FCE4597AD2](<Desktop/Dell/Precision/Precision T5600/CD5FD08D4152/KUBUNTU-24.10/6.11.0-12-GENERIC/X86_64/FCE4597AD2>) |
| 8086:1d6b | 15d9:0628 | Intel            | C602 chipset 4-Port SATA Storage ... | 11    | isci       | [27EB6B749C](<Desktop/Supermicro/X9/X9DR3-F/8BA7A98B76A9/DEBIAN-12/6.8.8-2-PVE/X86_64/27EB6B749C>) |
| 8086:1d6b | 17aa:1028 | Intel            | C602 chipset 4-Port SATA Storage ... | 11    | isci       | [55C567C63A](<Desktop/Lenovo/ThinkStation/ThinkStation C30 11361V9/43BACEDE76CA/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/55C567C63A>) |
| 1000:0064 | 1000:30d0 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 10    | mpt3sas    | [85AD08C5DB](<Desktop/Dell/Precision/Precision 5820 Tower/F6B348C07A96/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/85AD08C5DB>) |
| 1000:0072 | 1000:3060 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 10    | mpt3sas    | [1000CE7D88](<Notebook/Lenovo/ThinkPad/ThinkPad P51 20HJS16Q0K/22083ACDB057/ARCH-ROLLING/6.10.10-ARCH1-1/X86_64/1000CE7D88>) |
| 1000:0072 | 1000:30f0 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 10    | mpt3sas    | [563FFCE561](<Desktop/ASRock/970/970 Extreme3/5D248EB605FE/ZORIN-17/6.5.0-35-GENERIC/X86_64/563FFCE561>) |
| 1000:0072 | 1014:03cb | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 10    | mpt3sas    | [B1D404980D](<Desktop/ASRock/Z77/Z77 Extreme4/3A566FB1EF1C/DEBIAN-12/6.1.0-25-AMD64/X86_64/B1D404980D>) |
| 1000:0097 | 1028:1f53 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 10    | mpt3sas    | [152599CE84](<Server/Dell/PowerEdge/PowerEdge R730xd/6779A47FD98B/DEBIAN-10/4.19.147-RIVOREO-AMD64/X86_64/152599CE84>) |
| 8086:1d6b | 1849:1d6b | Intel            | C602 chipset 4-Port SATA Storage ... | 10    | isci       | [2229D803E9](<Desktop/ASRock/EP2/EP2C602/F286E3B2EC37/FEDORA-36/5.19.14-200.FC36.X86_64/X86_64/2229D803E9>) |
| 1000:0087 | 1000:3040 | LSI Logic / S... | SAS2308 PCI-Express Fusion-MPT SAS-2 | 9     | mpt3sas    | [7B51710FD1](<Server/Supermicro/Super/Super Server/717CACBD4C9C/UBUNTU-22.04/5.15.0-84-GENERIC/X86_64/7B51710FD1>) |
| 1000:0097 | 1000:30a0 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 9     | mpt3sas    | [FD86EE3128](<Server/Dell/PowerEdge/PowerEdge R740/437663FE9CF6/UBUNTU-24.04/6.8.0-47-GENERIC/X86_64/FD86EE3128>) |
| 1000:0064 | 1000:30c0 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 8     | mpt3sas    | [81652D9AB3](<Desktop/Gigabyte Technology/Z390/Z390 UD/35203D33BD09/UBUNTU-22.04/5.15.0-125-GENERIC/X86_64/81652D9AB3>) |
| 1000:0072 | 1000:3080 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 8     | mpt3sas    | [2D71FECB6D](<Server/Sun Microsystems/Sun/Sun Fire X2200 M2 with Quad Core Processor/D0B8300B5254/DEBIAN-12/6.1.0-18-AMD64/X86_64/2D71FECB6D>) |
| 1000:0097 | 1000:3130 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 8     | mpt3sas    | [86ADD53690](<Desktop/MSI/MS-7/MS-7D07/7B5BB4E03ACA/DEBIAN-12/6.6.44-PRODUCTION+TRUENAS/X86_64/86ADD53690>) |
| 1000:0087 | 1000:3030 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 7     | mpt3sas    | [D19B59B30D](<Desktop/ASRock/X570/X570 Taichi/ABF4E532BDC9/GENTOO-2.15/6.1.84-GENTOO/X86_64/D19B59B30D>) |
| 1000:0087 | 1590:0044 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 7     | mpt3sas    | [A0B680D2AC](<Desktop/Hewlett-Packard/ProLiant/ProLiant SL230s Gen8/6FFA10F98438/ALT-10.1/5.10.166-STD-DEF-ALT1/X86_64/A0B680D2AC>) |
| 1000:0072 | 1014:03ca | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 6     | mpt3sas    | [33C83F5D6F](<Desktop/Dell/Precision/Precision T7610/9FD1B6F0D3C9/ROCKY-8.10/4.18.0-553.22.1.EL8_10.X86_64/X86_64/33C83F5D6F>) |
| 1000:0097 | 1000:3090 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 6     | mpt3sas    | [122B21A8E4](<Server/Others/Others/Others/DB0155950DC6/DEBIAN-12/6.8.12-5-PVE/X86_64/122B21A8E4>) |
| 1000:00ac | 1000:3000 | Broadcom / LSI   | SAS3416 Fusion-MPT Tri-Mode I/O C... | 6     | mpt3sas    | [B9701CD43C](<Desktop/ASUSTek Computer/ROG/ROG STRIX B650E-E GAMING WIFI/D0C477A1B432/UBUNTU-23.04/6.2.0-27-GENERIC/X86_64/B9701CD43C>) |
| 1000:00af | 1000:3010 | Broadcom / LSI   | SAS3408 Fusion-MPT Tri-Mode I/O C... | 6     | mpt3sas    | [731C46B566](<Server/3Logic Group/Server/Server Graviton/7A144CAF308D/CYBER-INFRASTRUCTURE-6.0.0/3.10.0-1160.105.1.AIP7.214.3/X86_64/731C46B566>) |
| 8086:1d6b | 15d9:062b | Intel            | C602 chipset 4-Port SATA Storage ... | 6     | isci       | [F3D2F362E8](<Server/Supermicro/X9/X9SRE-X9SRE-3F-X9SRi-X9SRi-3F/55A635F4E92C/DEBIAN-12/6.8.8-2-PVE/X86_64/F3D2F362E8>) |
| 1000:0064 | 1000:3030 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 5     | mpt3sas    | [6DF318E1D4](<Desktop/Dell/Precision/Precision T3610/728695CB21CE/UBUNTU-22.04/6.0.0-060000-GENERIC/X86_64/6DF318E1D4>) |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1000:0058 | 103c:130b | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 60    | mptsas     | [9306B507F4](<Desktop/Hewlett-Packard/Z800/Z800 Workstation/97D4F3B37559/UBUNTU-22.04/6.8.0-49-GENERIC/X86_64/9306B507F4>) |
| 1000:0058 | 1028:021d | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 48    | mptsas     | [42C00B7A8A](<Desktop/Dell/Precision/Precision WorkStation T7500/C583DCA51C63/ZORIN-17/6.8.0-50-GENERIC/X86_64/42C00B7A8A>) |
| 1000:0056 | 1000:3090 | LSI Logic / S... | SAS1064ET PCI-Express Fusion-MPT SAS | 44    | mptsas     | [B79574C0C8](<Server/DEPO Computers/X8/X8DTU/3FF996EC5B0F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/B79574C0C8>) |
| 1000:0058 | 1028:1f0e | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 35    | mptsas     | [53891C4E7E](<Desktop/Dell/PowerEdge/PowerEdge T100/F2ABBCB868A8/UBUNTU-MATE-22.04/5.15.0-125-GENERIC/X86_64/53891C4E7E>) |
| 1000:0054 | 103c:0a98 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 21    | mptsas     | [68E6A9636C](<Desktop/Hewlett-Packard/xw8600/xw8600 Workstation/65298BD3AD52/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/68E6A9636C>) |
| 9004:5078 | 9004:7850 | Adaptec          | AIC-7850T/7856T [AVA-2902/4/6 / A... | 18    | aic7xxx    | [963DC3B162](<Desktop/Gigabyte Technology/P85/P85-D3/8A0958FE5941/FEDORA-38/6.8.9-100.FC38.X86_64/X86_64/963DC3B162>) |
| 1000:0058 | 1028:1f0f | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 12    | mptsas     | [B6E4EA8841](<Server/Dell/PowerEdge/PowerEdge R410/904CC8DF7D0A/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/B6E4EA8841>) |
| 9004:7178 |           | Adaptec          | AIC-7870P/7871 [AHA-2940/W/S76]      | 11    | aic7xxx    | [7E1C269806](<Desktop/Hewlett-Packard/NP201AA-ABA/NP201AA-ABA a6814y/0B611AE65EFF/UBUNTU-22.04/6.5.0-45-GENERIC/X86_64/7E1C269806>) |
| 1000:0058 | 1028:1f10 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 10    | mptsas     | [BAC383D8EC](<Server/Dell/PowerEdge/PowerEdge R710/9120169A2D61/UBUNTU-22.04/5.15.0-88-GENERIC/X86_64/BAC383D8EC>) |
| 1000:0056 | 1014:03bb | LSI Logic / S... | SAS1064ET PCI-Express Fusion-MPT SAS | 9     | mptsas     | [133F7BC9A5](<Server/IBM/System/System x3250 M3 -[4252K4G]-/76E08604766E/DEBIAN-11/6.2.16-20-BPO11-PVE/X86_64/133F7BC9A5>) |
| 1000:0058 | 103c:3229 | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 9     | mptsas     | [7CC6270F3F](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G7/92B0219DC6F1/OL-9.4/5.15.0-206.153.7.EL9UEK.X86_64/X86_64/7CC6270F3F>) |
| 1b85:1021 | 1b85:1021 | OCZ Technolog... | RevoDrive 3 X2 PCIe SSD 240 GB (M... | 9     | mvsas      | [D8B58EEDF8](<Desktop/ASUSTek Computer/TUF/TUF Gaming X670E-PLUS WIFI/EDF2CD849D06/ALT-0.9.2/6.9.6-6.9-ALT1/X86_64/D8B58EEDF8>) |
| 9004:8178 | 9004:7881 | Adaptec          | AIC-7870P/7881U [AHA-2940U/UW/D/S76] | 9     | aic7xxx    | [17392605BB](<Desktop/Dell/Vostro/Vostro 400/9FEBBAB61593/DEBIAN-12/6.1.0-13-AMD64/X86_64/17392605BB>) |
| 1000:0030 | 1000:50c0 | LSI Logic / S... | 53c1030 PCI-X Fusion-MPT Dual Ult... | 8     | mptspi     | [200F681617](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 TWR/D9C9ECD926E4/KDE-NEON-24.04/6.8.0-49-GENERIC/X86_64/200F681617>) |
| 9004:8178 |           | Adaptec          | AIC-7870P/7881U [AHA-2940U/UW/D/S76] | 8     | aic7xxx    | [7539F3648F](<Desktop/Gigabyte Technology/GA-970/GA-970A-D3/B4B69547D91F/UBUNTU-20.04/5.11.0-44-GENERIC/X86_64/7539F3648F>) |
| 9005:8017 | 9005:0045 | Adaptec          | ASC-29320ALP U320                    | 8     | aic79xx    | [755D1F8C03](<Desktop/Dell/Inspiron/Inspiron 3847/B2A09C32DDA7/FEDORA-38/6.3.6-200.FC38.X86_64/X86_64/755D1F8C03>) |
| 1000:0001 |           | LSI Logic / S... | 53c810                               | 6     | sym53c8xx  | [647A30FF09](<Desktop/ASUSTek Computer/ROG/ROG STRIX X399-E GAMING/90D71D812761/LINUXMINT-21.1/5.15.0-72-GENERIC/X86_64/647A30FF09>) |
| 1000:0050 | 103c:3015 | Broadcom / LSI   | SAS1064 PCI-X Fusion-MPT SAS         | 6     | mptsas     | [4B76EEAC51](<Desktop/Hewlett-Packard/xw8400/xw8400 Workstation/DB680909DD9F/UBUNTU-24.04/6.8.0-50-GENERIC/X86_64/4B76EEAC51>) |
| 10cd:1300 | 10cd:1310 | Advanced Syst... | ASC1300 / ASC3030 [ABP940-U / ABP... | 6     | advansys   | [46C54039D4](<Desktop/ASRock/4Core1600/4Core1600Twins-P35/91DEAADFBF98/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/46C54039D4>) |
| 11ab:7042 | 11ab:11ab | Marvell Techn... | 88SX7042 PCIe 4-port SATA-II cont... | 6     | sata_mv    | [2A477B71F7](<Desktop/MSI/MS-7/MS-7B86/36FB29EAC319/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.5.3-1-DEFAULT/X86_64/2A477B71F7>) |
| 1af4:1048 | 1af4:1100 | Red Hat          | Virtio 1.0 SCSI                      | 6     | virtio_pci | [D237816BD5](<Desktop/QEMU/Standard/Standard PC/418878F10378/DEBIAN-12/6.1.0-28-AMD64/X86_64/D237816BD5>) |
| 1de1:0391 | 1de1:0391 | Tekram Techno... | TRM-S1040 [DC-315 / DC-395 series]   | 6     | dc395x     | [F4AEFCD670](<Desktop/Dell/OptiPlex/OptiPlex 790/C2D4C0854C04/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/F4AEFCD670>) |
| 9004:6178 | 9004:7861 | Adaptec          | AIC-7861                             | 6     | aic7xxx    | [647A30FF09](<Desktop/ASUSTek Computer/ROG/ROG STRIX X399-E GAMING/90D71D812761/LINUXMINT-21.1/5.15.0-72-GENERIC/X86_64/647A30FF09>) |
| 9005:00c0 | 9005:f620 | Adaptec          | AHA-3960D / AIC-7899A U160/m         | 6     | aic7xxx    | [51F6C29054](<Desktop/Gigabyte Technology/B450/B450 AORUS ELITE/D178DC2602AD/OL-9.5/5.15.0-303.171.5.2.EL9UEK.X86_64/X86_64/51F6C29054>) |
| 1000:0030 | 103c:12f1 | LSI Logic / S... | 53c1030 PCI-X Fusion-MPT Dual Ult... | 5     | mptspi     | [8FF662507A](<Desktop/Hewlett-Packard/workstation/workstation xw8200/3B155B11885F/LINUXMINT-20.3/5.4.0-122-GENERIC/X86_64/8FF662507A>) |
| 1000:0054 | 1028:1f08 | LSI Logic / S... | SAS1068 PCI-X Fusion-MPT SAS         | 5     | mptsas     | [9500786A21](<Desktop/Dell/Precision/Precision WorkStation 690/B0E5BCD0FEB2/UBUNTU-22.04/5.15.0-25-GENERIC/X86_64/9500786A21>) |
| 9004:5078 |           | Adaptec          | AIC-7850T/7856T [AVA-2902/4/6 / A... | 5     | aic7xxx    | [1750E9CB64](<Desktop/ASUSTek Computer/All/All Series/715F809EF15E/UBUNTU-22.04/6.8.0-48-GENERIC/X86_64/1750E9CB64>) |
| 9004:6178 |           | Adaptec          | AIC-7861                             | 5     | aic7xxx    | [3DB7E99C4A](<Desktop/Dell/PowerEdge/PowerEdge T20/7EFFCB3E513D/DEBIAN-12/6.1.0-13-AMD64/X86_64/3DB7E99C4A>) |
| 1000:000f | 1000:1000 | Broadcom / LSI   | 53c875                               | 4     | sym53c8xx  | [544DE4F6E5](<Desktop/Dell/OptiPlex/OptiPlex 5040/FA62AA11285A/OPENSUSE-LEAP-15.6/6.4.0-150600.21-DEFAULT/X86_64/544DE4F6E5>) |
| 1000:0030 | 103c:322a | LSI Logic / S... | 53c1030 PCI-X Fusion-MPT Dual Ult... | 4     | mptspi     | [6F3897ABD9](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML10 v2/C9AA3309C846/CENTOS-7/3.10.0-1160.108.1.EL7.X86_64/X86_64/6F3897ABD9>) |
| 1000:0054 | 1028:1f09 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 4     | mptsas     | [4EB39C2CF0](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/1B857F86D4CB/FEDORA-39/6.7.9-200.FC39.X86_64/X86_64/4EB39C2CF0>) |
| 1000:0056 | 103c:322b | LSI Logic / S... | SAS1064ET PCI-Express Fusion-MPT SAS | 4     | mptsas     | [9106155D17](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML150 G5/BD0AC182580A/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/9106155D17>) |
| 1000:0058 | 1000:3140 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 4     | mptsas     | [09C71F9FAA](<Server/Supermicro/X8/X8DTU/1ABD2AAE69B0/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/09C71F9FAA>) |
| 1000:0058 | 103c:12fe | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 4     | mptsas     | [6D6F2CE899](<Desktop/Hewlett-Packard/xw9400/xw9400 Workstation/929CBE5567A0/LUBUNTU-20.04/5.8.0-59-GENERIC/X86_64/6D6F2CE899>) |
| 1000:0058 | 1734:1130 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 4     | mptsas     | [C4C0B53877](<Server/Fujitsu/PRIMERGY/PRIMERGY TX150 S7/4BE064DA92A3/OL-9.0/5.15.0-0.30.19.EL9UEK.X86_64/X86_64/C4C0B53877>) |
| 1191:8040 | 1191:8040 | Artop Electronic | AEC6712D SCSI                        | 4     | atp870u    | [375A0A6487](<Desktop/MSI/MS/MS-7846/54D7D14E4E4D/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/375A0A6487>) |
| 9004:3860 | 9004:3869 | Adaptec          | AHA-2930CU                           | 4     | aic7xxx    | [75D4601793](<Desktop/Lenovo/70A4000HUX/70A4000HUX ThinkServer TS140/5F6EF056FA19/FEDORA-40/6.9.6-200.FC40.X86_64/X86_64/75D4601793>) |
| 9005:0080 | 9005:62a0 | Adaptec          | AIC-7892A U160/m                     | 4     | aic7xxx    | [1B275899D5](<Desktop/Supermicro/C2/C2SBX/7D054759F288/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/1B275899D5>) |
| 9005:0080 | 9005:e2a0 | Adaptec          | AIC-7892A U160/m                     | 4     | aic7xxx    | [18E1DA8CCE](<Desktop/Biostar/B350/B350GT5/6B57AAE9A1B9/LINUXMINT-21.1/5.19.0-43-GENERIC/X86_64/18E1DA8CCE>) |
| 9005:8017 | 9005:0044 | Adaptec          | ASC-29320ALP U320                    | 4     | aic79xx    | [C4041B26F3](<Desktop/IBM/eServer/eServer x3500-[7977G2G]/A6DB44627AC3/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/C4041B26F3>) |
| 1000:0030 | 103c:1500 | LSI Logic / S... | 53c1030 PCI-X Fusion-MPT Dual Ult... | 3     | mptspi     | [A94946D561](<Desktop/Hewlett-Packard/xw9300/xw9300 Workstation/796D0561C4B4/LUBUNTU-20.04/5.8.0-53-GENERIC/X86_64/A94946D561>) |
| 1000:0056 | 8086:3486 | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 3     | mptsas     | [EC199DC348](<Server/Intel/S5000/S5000VSA/20C09D0041D0/DEBIAN-11/5.15.158-2-PVE/X86_64/EC199DC348>) |
| 1000:0058 | 1000:3150 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 3     | mptsas     | [EA845EC5EA](<Server/Sun Microsystems/Sun/Sun Fire X4170 M2 SERVER/DD45CBFD7301/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/EA845EC5EA>) |
| 1000:0058 | 1014:0394 | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 3     | mptsas     | [B85DBD88F5](<Server/IBM/System/System x3650 M2 -[7947AC1]-/B4AFB5C90D39/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/B85DBD88F5>) |
| 1000:0058 | 1014:0396 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 3     | mptsas     | [4DD5CEEF26](<Desktop/Dell/OptiPlex/OptiPlex 7010/6523DBCF8579/ARCH-ROLLING/5.18.1-ARCH1-1/X86_64/4DD5CEEF26>) |
| 1022:2020 |           | AMD              | AM53/79C974 [PC-SCSI]                | 3     | am53c974   | [126C347AC7](<Desktop/Gigabyte Technology/H67/H67M-D2-B3/CAC920FDF3F3/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/126C347AC7>) |
| 9005:0010 | 9005:a180 | Adaptec          | AHA-2940U2/U2W                       | 3     | aic7xxx    | [F894ABD641](<Desktop/ASUSTek Computer/P5/P5KPL-SE/7F2E04977419/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/F894ABD641>) |
| 9005:0081 | 9005:62a1 | Adaptec          | AIC-7892B U160/m                     | 3     | aic7xxx    | [6F97813144](<Desktop/ASUSTek Computer/P5K/P5K Deluxe/DA82DB227041/FEDORA-36/6.0.5-200.FC36.X86_64/X86_64/6F97813144>) |
| 1000:0030 | 103c:3108 | LSI Logic / S... | 53c1030 PCI-X Fusion-MPT Dual Ult... | 2     | mptspi     | [47FD974AFD](<Desktop/Dell/Precision/Precision WorkStation 690/E43C5B330772/SLACKWARE-15.0/6.1.20/X86_64/47FD974AFD>) |
| 1000:0054 | 1000:30e0 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 2     | mptsas     | [AAC8A6F7E4](<Desktop/Others/Others/Others/7649ED3709F2/DEBIAN-7/4.1.42-RIVOREO-POWERPC64/PPC64/AAC8A6F7E4>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:09ab |           | Intel            | RST VMD Managed Controller           | 3397  |            | [22D073249B](<Notebook/MSI/Prestige/Prestige 16 AI Studio B1VFG/81BEB162FA34/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/22D073249B>) |
| 8086:1513 | 2222:1111 | Intel            | CV82524 Thunderbolt Controller [L... | 1321  | thunder... | [AE5A71DDE0](<Notebook/Apple/MacBookPro9/MacBookPro9,1/04AD065CAD6F/LINUXMINT-20.3/5.4.0-204-GENERIC/X86_64/AE5A71DDE0>) |
| 8086:2f88 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 VCU    | 1290  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2f8a |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 VCU    | 1290  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fae |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 1290  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2faf |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 1290  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fbe |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 1290  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fbf |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 1290  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2ff8 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Buf... | 1290  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2ff9 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Buf... | 1290  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2f6e |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 1287  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2f6f |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 1287  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fb8 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 1287  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fb9 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 1287  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fba |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 1287  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fbb |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 1287  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2f1d | 8086:2f1d | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 PCI... | 1157  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2f1e | 8086:2f1e | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 1157  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2f1f | 8086:2f1f | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 1157  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2f71 | 8086:2f71 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 1157  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2f98 | 8086:2f98 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Pow... | 1157  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2f99 | 8086:2f99 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Pow... | 1157  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2f9a | 8086:2f9a | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Pow... | 1157  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2f9c | 8086:2f9c | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Pow... | 1157  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fa0 | 8086:2fa0 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 1157  | sb_edac    | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fa8 | 8086:2fa8 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 1157  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2faa | 8086:2faa | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 1157  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fab | 8086:2fab | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 1157  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fb0 | 8086:2fb0 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 1157  | hswep_u... | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fb1 | 8086:2fb1 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 1157  | hswep_u... | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fb2 | 8086:2fb2 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 1157  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fb3 | 8086:2fb3 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 1157  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fc0 | 8086:2fc0 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Pow... | 1157  | hswep_u... | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2f81 | 8086:2f81 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 1094  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fe0 | 8086:2fe0 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Uni... | 1094  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fe1 | 8086:2fe1 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Uni... | 1094  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fe2 | 8086:2fe2 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Uni... | 1094  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fe3 | 8086:2fe3 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Uni... | 1094  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2ffc | 8086:2fe0 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Sys... | 1094  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2ffd | 8086:2fe0 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Sys... | 1094  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2ffe | 8086:2fe0 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Sys... | 1094  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fbc |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 1053  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fbd |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 1053  |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fe4 | 8086:2fe4 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Uni... | 983   |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:2fe5 | 8086:2fe5 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Uni... | 983   |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:d150 |           | Intel            | Core Processor QPI Link              | 977   |            | [48E00D403A](<Server/Dell/PowerEdge/PowerEdge T310/0EAF01173A25/DEBIAN-12/6.6.32-PRODUCTION+TRUENAS/X86_64/48E00D403A>) |
| 8086:d151 |           | Intel            | Core Processor QPI Routing and Pr... | 977   |            | [48E00D403A](<Server/Dell/PowerEdge/PowerEdge T310/0EAF01173A25/DEBIAN-12/6.6.32-PRODUCTION+TRUENAS/X86_64/48E00D403A>) |
| 8086:d158 |           | Intel            | Core Processor Miscellaneous Regi... | 923   |            | [48E00D403A](<Server/Dell/PowerEdge/PowerEdge T310/0EAF01173A25/DEBIAN-12/6.6.32-PRODUCTION+TRUENAS/X86_64/48E00D403A>) |
| 8086:1911 | 1458:5000 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 884   |            | [A49FDE4DF3](<Desktop/Gigabyte Technology/B365M/B365M DS3H/406A103EBD76/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/A49FDE4DF3>) |
| 8086:6f76 |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 826   |            | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |

### Tv card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 109e:036e |           | Brooktree        | Bt878 Video Capture                  | 41    | bttv       | [067B12DD29](<Desktop/ASUSTek Computer/P5N72-T/P5N72-T PREMIUM/4681DBCDC019/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/067B12DD29>) |
| 14f1:8880 | 0070:7801 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 32    | cx23885    | [72DF4952B1](<Desktop/Hewlett-Packard/KQ497AA-ABA/KQ497AA-ABA m9340f/407BB1C2DDDC/UBUNTU-22.04/6.5.0-45-GENERIC/X86_64/72DF4952B1>) |
| 4444:0016 | 0070:8801 | Internext Com... | iTVC16 (CX23416) Video Decoder       | 29    | ivtv       | [725AF27634](<Desktop/Hewlett-Packard/GN652AA-ABM/GN652AA-ABM m9050la/7772946DA47F/LINUXMINT-22/6.8.0-49-GENERIC/X86_64/725AF27634>) |
| 1131:7133 | 1461:a11b | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 26    | saa7134    | [A652572CF4](<Desktop/Sapphire/PI-AM3/PI-AM3RS760G2/E09823B9E3B0/DEBIAN-12/6.6.15-AMD64/X86_64/A652572CF4>) |
| 1131:7130 | 5ace:5050 | Philips Semic... | SAA7130 Video Broadcast Decoder      | 21    | saa7134    | [8BF7660808](<Desktop/ASUSTek Computer/A68/A68HM-K/65396CBF1888/FEDORA-35/5.14.18-300.FC35.X86_64/X86_64/8BF7660808>) |
| 1131:7133 | 5ace:5090 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 21    | saa7134    | [D85165218E](<Desktop/ASUSTek Computer/P7P55D/P7P55D PRO/B02E570AD1B7/ROSA-12.5.1/5.15.127-GENERIC-1ROSA2021.1-X86_64/X86_64/D85165218E>) |
| 14f1:8880 | 0070:f038 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 21    | cx23885    | [47E2EE96E9](<Desktop/Gigabyte Technology/Z270X-Gaming/Z270X-Gaming 7/3CD6E6343FF0/ARCO-ROLLING/6.12.1-ARCH1-1/X86_64/47E2EE96E9>) |
| 14f1:8880 | 0070:6a18 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 20    | cx23885    | [AD40DB7F67](<Desktop/Gigabyte Technology/Z170X-Gaming/Z170X-Gaming 7/4DE1A28702A7/ZORIN-17/6.8.0-50-GENERIC/X86_64/AD40DB7F67>) |
| 14f1:8880 | 0070:6b18 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 20    | cx23885    | [AD40DB7F67](<Desktop/Gigabyte Technology/Z170X-Gaming/Z170X-Gaming 7/4DE1A28702A7/ZORIN-17/6.8.0-50-GENERIC/X86_64/AD40DB7F67>) |
| 1131:7133 | 1461:4255 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 19    | saa7134    | [EFE2537D0F](<Desktop/Positivo/POS-EINM10/POS-EINM10CB/36D1F71A217A/SOLUS-4.5/6.6.12-271.CURRENT/X86_64/EFE2537D0F>) |
| 14f1:8852 | 0070:7911 | Conexant Systems | CX23885 PCI Video and Audio Decoder  | 19    | cx23885    | [A26110A2F5](<Desktop/ASUSTek Computer/PRIME/PRIME H470M-PLUS/820BCAED8BA6/FEDORA-38/6.6.14-100.FC38.X86_64/X86_64/A26110A2F5>) |
| 109e:036e | 1461:0003 | Brooktree        | Bt878 Video Capture                  | 18    | bttv       | [052BA36722](<Desktop/Gigabyte Technology/8IPE1000/8IPE1000P-G/8B09BF0F0D60/XUBUNTU-16.04/4.15.0-142-GENERIC/I686/052BA36722>) |
| 1131:7130 | 1131:0000 | Philips Semic... | SAA7130 Video Broadcast Decoder      | 18    | saa7134    | [BF30D86827](<Desktop/Gigabyte Technology/GA-MA785/GA-MA785GT-UD3H/0021FB1675B9/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/BF30D86827>) |
| 1131:7134 | 1131:0000 | Philips Semic... | SAA7134/SAA7135HL Video Broadcast... | 18    | saa7134    | [43EDAE3BCA](<Desktop/ASRock/G31/G31M-GS/81195834A38A/XUBUNTU-24.04/6.8.0-49-GENERIC/X86_64/43EDAE3BCA>) |
| 1131:7134 | 1461:9715 | Philips Semic... | SAA7134/SAA7135HL Video Broadcast... | 17    | saa7134    | [32366172E4](<Desktop/ASRock/880/880GM-LE/06F093AF73B9/ROSA-12.3/5.15.79-GENERIC-1ROSA2021.1-X86_64/X86_64/32366172E4>) |
| 1131:7134 | 5ace:5070 | Philips Semic... | SAA7134/SAA7135HL Video Broadcast... | 17    | saa7134    | [B6FCAC82E8](<Desktop/ASUSTek Computer/P5/P5K/5106DAC25189/UBUNTU-18.04/5.3.0-28-GENERIC/X86_64/B6FCAC82E8>) |
| 14f1:8880 | 1461:e139 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 17    | cx23885    | [A0EAD70204](<Desktop/MACHINIST/X99/X99 PR9-H/7C657E140B4A/OPENMANDRIVA-24.07/6.11.0-DESKTOP-2OMV2490/X86_64/A0EAD70204>) |
| 109e:036e | 0070:13eb | Brooktree        | Bt878 Video Capture                  | 16    | bttv       | [CA4265A41B](<Desktop/ASUSTek Computer/P8/P8H67-V/99D06917D672/UBUNTU-20.04/5.4.0-187-GENERIC/X86_64/CA4265A41B>) |
| 1131:7133 | 16be:000d | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 16    | saa7134    | [94581471DA](<Desktop/Medion/MS/MS-7318/FFB9DA089C4F/DEBIAN-12/6.1.0-23-AMD64/X86_64/94581471DA>) |
| 1131:7134 | 185b:c200 | Philips Semic... | SAA7134/SAA7135HL Video Broadcast... | 13    | saa7134    | [F386A19D48](<Desktop/Acer/Veriton/Veriton S2610G/5436FDB2A2BB/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/F386A19D48>) |
| 14f1:5b7a | 0070:7400 | Conexant Systems | CX23418 Single-Chip MPEG-2 Encode... | 13    | cx18       | [B7A885758D](<Desktop/Hewlett-Packard/RK569AA-ABA/RK569AA-ABA m7750n/8E21E3107BC4/UBUNTU-22.04/6.5.0-15-GENERIC/X86_64/B7A885758D>) |
| 14f1:8880 | 0070:f02a | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 13    | cx23885    | [069D1B64D4](<Desktop/MSI/MS-7/MS-7C56/6D5C43A6D204/LINUXMINT-22/6.8.0-47-GENERIC/X86_64/069D1B64D4>) |
| 1131:7133 | 1043:4871 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 12    | saa7134    | [A50F5F9E3A](<Desktop/Hewlett-Packard/RZ482AA-ABF/RZ482AA-ABF m8090.fr/51C8E0BDD6BD/LINUXMINT-21.3/5.15.0-106-GENERIC/X86_64/A50F5F9E3A>) |
| 1131:7133 | 11bd:002f | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 12    | saa7134    | [697B22A027](<Desktop/Gigabyte Technology/GA-990X-Gaming/GA-990X-Gaming SLI-CF/ABD3A81F101D/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/697B22A027>) |
| 1131:7134 | 16be:0003 | Philips Semic... | SAA7134/SAA7135HL Video Broadcast... | 12    | saa7134    | [35DD91FA94](<Desktop/ASUSTek Computer/M3/M3A/4C070E755C3C/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/35DD91FA94>) |
| 11de:6057 | 1031:7efe | Zoran            | ZR36057PQC Video cutting chipset     | 12    | zr36067    | [451C626830](<Desktop/ASRock/Z97/Z97 Pro4/BAF192DD9D15/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/451C626830>) |
| 14f1:8880 | 0070:6a28 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 12    | cx23885    | [48D7C58756](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-E GAMING/6DF84209F002/DEBIAN-12/6.1.0-17-AMD64/X86_64/48D7C58756>) |
| 14f1:8880 | 0070:6b28 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 12    | cx23885    | [48D7C58756](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-E GAMING/6DF84209F002/DEBIAN-12/6.1.0-17-AMD64/X86_64/48D7C58756>) |
| 14f1:8880 | 0070:c138 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 12    | cx23885    | [081CB592E3](<Desktop/ASUSTek Computer/P8H61-MX/P8H61-MX USB3/4635344B0B5E/LINUXMINT-21.2/5.15.0-122-GENERIC/X86_64/081CB592E3>) |
| 14f1:8800 |           | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 11    | cx8800     | [E80788F790](<Desktop/ASRock/775/775XFire-VSTA/16EC5FDAAED3/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E80788F790>) |
| 14f1:8800 | 107d:6611 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 11    | cx8800     | [DC2914021F](<Desktop/ASUSTek Computer/P7/P7P55D-E/72B7CF300BA2/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/DC2914021F>) |
| 14f1:8852 | 0070:6a28 | Conexant Systems | CX23885 PCI Video and Audio Decoder  | 11    | cx23885    | [2551062F30](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-A/B497EE155147/DEBIAN-12/6.3.9-I7/X86_64/2551062F30>) |
| 14f1:8852 | 0070:6b28 | Conexant Systems | CX23885 PCI Video and Audio Decoder  | 11    | cx23885    | [2551062F30](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-A/B497EE155147/DEBIAN-12/6.3.9-I7/X86_64/2551062F30>) |
| 1131:7130 | 1461:2115 | Philips Semic... | SAA7130 Video Broadcast Decoder      | 10    | saa7134    | [417D975CD9](<Desktop/ASUSTek Computer/P4/P4P800/92967C173382/ROSA-2016.1/4.15.0-DESKTOP-60.7ROSA-I586/I686/417D975CD9>) |
| 1131:7133 | 0000:4091 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 10    | saa7134    | [E7042308E9](<Desktop/MSI/MS/MS-7693/96A89E57BA55/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-X86_64/X86_64/E7042308E9>) |
| 1131:7133 | 1043:4876 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 10    | saa7134    | [BF22B887F8](<Desktop/Others/P4/P4M800CE-8237/6EE6B0DFCE83/LMDE-6/6.1.0-12-686/I686/BF22B887F8>) |
| 1131:7133 | 1131:0000 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 10    | saa7134    | [60E1A81B56](<Desktop/Hewlett-Packard/Compaq/Compaq dc7600 Small Form Factor/0F9F9361BFB3/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/60E1A81B56>) |
| 1131:7134 | 5168:0138 | Philips Semic... | SAA7134/SAA7135HL Video Broadcast... | 10    | saa7134    | [5A62C5D679](<Desktop/Fujitsu/ESPRIMO/ESPRIMO P710/7664229DE514/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/5A62C5D679>) |
| 14f1:8852 | 0070:71d3 | Conexant Systems | CX23885 PCI Video and Audio Decoder  | 10    | cx23885    | [30F065CD2E](<Desktop/Hewlett-Packard/Pavilion/Pavilion Gaming Desktop TG01-0xxx/FC776FB96899/OPENMANDRIVA-24.01/6.6.2-DESKTOP-1OMV2390/X86_64/30F065CD2E>) |
| 14f1:8880 | 0070:53f2 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 10    | cx23885    | [2EC9D89DD5](<Desktop/Acer/Aspire/Aspire M3800/DC717B183C69/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/2EC9D89DD5>) |
| 14f1:8880 | 1461:d439 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 10    | cx23885    | [F778045427](<Desktop/Gateway/945/945G-M3/4B59FC0BA54F/FEDORA-40/6.9.12-200.FC40.X86_64/X86_64/F778045427>) |
| 109e:036e | 11bd:0012 | Brooktree        | Bt878 Video Capture                  | 9     | bttv       | [7F8C8E496A](<Desktop/Lenovo/ThinkCentre/ThinkCentre M55e 9645W2C/B30B5EDE8E66/UBUNTU-MATE-22.04/6.2.0-39-GENERIC/X86_64/7F8C8E496A>) |
| 109e:036e | ffff:ffff | Brooktree        | Bt878 Video Capture                  | 9     | bttv       | [CA8808DB77](<Desktop/ASRock/B450/B450 Pro4/0A5C9C10BAC1/LMDE-6/6.1.0-28-AMD64/X86_64/CA8808DB77>) |
| 1131:7130 | 1461:a11b | Philips Semic... | SAA7130 Video Broadcast Decoder      | 9     | saa7134    | [08DA43BE7F](<Desktop/ASRock/P43/P43DE/CF9CAC13052E/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/08DA43BE7F>) |
| 1131:7133 | 11bd:002e | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 9     | saa7134    | [EE56912AAB](<Desktop/Gigabyte Technology/H110/H110M-S2PV/38A5CDD36960/ROSA-12.4/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/EE56912AAB>) |
| 1131:7133 | 1461:0155 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 9     | saa7134    | [3ED55D530A](<Desktop/Gigabyte Technology/H61/H61M-S2PV/DE2D1C5C4F5E/ALT-10.1/5.10.179-STD-DEF-ALT1/X86_64/3ED55D530A>) |
| 1131:7133 | 1461:e836 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 9     | saa7134    | [D41CBF35F9](<Notebook/Sony/VGN-AR41/VGN-AR41S/A797934B2F04/ZORIN-17/6.8.0-47-GENERIC/X86_64/D41CBF35F9>) |
| 1131:7133 | 1461:f11d | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 9     | saa7134    | [4B37AE65F2](<Desktop/ASRock/990FX/990FX Extreme4/43702275B2AC/DEBIAN-12/6.11.10+BPO-AMD64/X86_64/4B37AE65F2>) |
| 1131:7133 | 5ace:6090 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 9     | saa7134    | [14E5916050](<Desktop/ASRock/H67/H67DE3/E9603C970E1C/KUBUNTU-20.04/5.8.0-45-GENERIC/X86_64/14E5916050>) |
| 1131:7133 | 5ace:7290 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 9     | saa7134    | [60AB9AF8C6](<Desktop/ASUSTek Computer/All/All Series/E56B922DEFFA/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/60AB9AF8C6>) |

### Unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:31a2 | 1028:081f | Intel            | Celeron/Pentium Silver Processor ... | 55    | intel_i... | [7A2E256A73](<Convertible/Dell/Latitude/Latitude 3190 2-in-1/754F0A1763FB/FEDORA-40/6.10.11-200.FC40.X86_64/X86_64/7A2E256A73>) |
| 8086:31a2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 18    | intel_i... | [E8C1DC7DBF](<Desktop/AMI/Intel/Intel/95C86D2339A8/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/E8C1DC7DBF>) |
| 8086:5aa2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    | intel_i... | [C3707F019E](<Desktop/Others/AB07/AB07C/8D88931D4FEF/ZORIN-17/6.5.0-35-GENERIC/X86_64/C3707F019E>) |
| 8086:5aa2 | 1028:07b3 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 17    | intel_i... | [881F99BC57](<Notebook/Dell/Latitude/Latitude 3189/274E1EBA3FFC/KALI-2024.4/6.11.2-AMD64/X86_64/881F99BC57>) |
| 1af4:1045 | 1af4:1100 | Red Hat          | Virtio 1.0 memory balloon            | 15    | virtio_pci | [79EC6F96E4](<Desktop/Bochs/Others/Others/BE32418C1D7C/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/79EC6F96E4>) |
| 8086:31a2 | 17aa:3801 | Intel            | Celeron/Pentium Silver Processor ... | 15    | intel_i... | [8FAA95CC75](<Convertible/Lenovo/Flex/Flex 6-11IGM 81A7/B6E5CCD178A4/KDE-NEON-22.04/6.8.0-45-GENERIC/X86_64/8FAA95CC75>) |
| 1af4:1044 | 1af4:1100 | Red Hat          | Virtio 1.0 RNG                       | 14    | virtio_pci | [D237816BD5](<Desktop/QEMU/Standard/Standard PC/418878F10378/DEBIAN-12/6.1.0-28-AMD64/X86_64/D237816BD5>) |
| 8086:5aa2 | 17aa:3804 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 12    | intel_i... | [79A906A0FE](<Convertible/Lenovo/Yoga/Yoga 310-11IAP 80U2/3CCA21F039D3/OPENMANDRIVA-24.08/6.10.1-DESKTOP-1OMV2490/X86_64/79A906A0FE>) |
| 8086:31a2 | 103c:86cf | Intel            | Celeron/Pentium Silver Processor ... | 11    | intel_i... | [3CF2D45223](<Convertible/Hewlett-Packard/ProBook/ProBook x360 11 G5 EE/0CD0E81DFE3F/ELEMENTARY-7.1/6.8.0-47-GENERIC/X86_64/3CF2D45223>) |
| 8086:31a2 | 1043:1182 | Intel            | Celeron/Pentium Silver Processor ... | 9     | intel_i... | [026638D09E](<Convertible/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop TP401MAR_TP401MA/E63811D02DA8/UBUNTU-22.04/6.2.0-39-GENERIC/X86_64/026638D09E>) |
| 8086:31a2 | 17aa:3806 | Intel            | Celeron/Pentium Silver Processor ... | 7     | intel_i... | [54B92E3341](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 3 11IGL05 82B2/554DDD86EB20/TUXEDO-24.04/6.8.0-105041-TUXEDO/X86_64/54B92E3341>) |
| 8086:5aa2 | 103c:82ee | Intel            | Celeron N3350/Pentium N4200/Atom ... | 6     | intel_i... | [C191463E94](<Notebook/Hewlett-Packard/ProBook/ProBook x360 11 G1 EE/4B634C2A066D/ARCH-ROLLING/6.10.7-ARCH1-1/X86_64/C191463E94>) |
| 8086:31a2 | 103c:84fa | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_i... | [61FCA6914F](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible 11m-ad1xx/EBD850DC5C48/UBUNTU-22.04/6.5.0-18-GENERIC/X86_64/61FCA6914F>) |
| 8086:31a2 | 103c:8521 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_i... | [5CA009FAF3](<Convertible/Hewlett-Packard/ProBook/ProBook x360 11 G3 EE/2FB500F37CFD/KUBUNTU-23.10/6.5.0-14-GENERIC/X86_64/5CA009FAF3>) |
| 8086:31a2 | 103c:85ca | Intel            | Celeron/Pentium Silver Processor ... | 4     | intel_i... | [387885BCF8](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible 11m-ap0xxx/2F58C1072CDE/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/387885BCF8>) |
| 1af4:1049 | 1af4:1100 | Red Hat          | Virtio 1.0 filesystem                | 3     | virtio_pci | [D237816BD5](<Desktop/QEMU/Standard/Standard PC/418878F10378/DEBIAN-12/6.1.0-28-AMD64/X86_64/D237816BD5>) |
| 8086:31a2 | 1043:1231 | Intel            | Celeron/Pentium Silver Processor ... | 3     | intel_i... | [CFEA5CE0FE](<Convertible/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop TP401MAS_TP401MA/66F96CB0E389/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/CFEA5CE0FE>) |
| 8086:31a2 | 17aa:2261 | Intel            | Celeron/Pentium Silver Processor ... | 3     | intel_i... | [CBFF1B04E0](<Tablet/Lenovo/Tablet/Tablet 10 20L3000RGE/BBF4DFDD3007/UBUNTU-23.10/6.5.0-15-GENERIC/X86_64/CBFF1B04E0>) |
| 8086:31a2 | 7270:8086 | Intel            | Celeron/Pentium Silver Processor ... | 3     | intel_i... | [DF7E9AF6A4](<Notebook/Insyde/GeminiLake/GeminiLake/5EC02687D66E/DEBIAN-11/5.10.0-32-AMD64/X86_64/DF7E9AF6A4>) |
| 8086:5aa2 | 103c:830d | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | intel_i... | [9BFD668093](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible 11-ad0xx/43ECB5D0C231/FEDORA-37/6.0.11-300.FC37.X86_64/X86_64/9BFD668093>) |
| 8086:5aa2 | 1043:1930 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | intel_i... | [0B2979CA7F](<Convertible/ASUSTek Computer/TP203/TP203NAH/D22DC9FB1815/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/0B2979CA7F>) |
| 8086:5aa2 | 1043:1c80 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | intel_i... | [7F25CF70DD](<Convertible/ASUSTek Computer/TP401/TP401NA/9A78E9AF609C/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/7F25CF70DD>) |
| 8086:5aa2 | 1043:1d90 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | intel_i... | [C8494C780F](<Convertible/ASUSTek Computer/TP401/TP401NAS/82D4BDC28CF9/ZORIN-17/6.2.0-39-GENERIC/X86_64/C8494C780F>) |
| 8086:31a2 | 1043:1221 | Intel            | Celeron/Pentium Silver Processor ... | 2     | intel_i... | [B66FE97C5F](<Convertible/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop TP401MA_TP401MA/D546DE8A4575/LINUXMINT-21.3/5.15.0-91-GENERIC/X86_64/B66FE97C5F>) |
| 8086:5aa2 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | intel_i... | [4A2F4F8CB1](<Desktop/Others/Others/Others/FBC02BEEE3C4/FEDORA-35/5.17.7-200.FC35.X86_64/X86_64/4A2F4F8CB1>) |
| 1137:0042 | 1137:012e | Cisco Systems    | VIC Management Controller            | 1     |            | [BAF3069CD7](<Server/Cisco Systems/UCSC-C220/UCSC-C220-M4S/9D3781D2096F/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/BAF3069CD7>) |
| 1217:6120 | 0001:0000 | O2 Micro         |                                      | 1     |            | [B851103D78](<Notebook/LG Electronics/F1/F1-2A78R/54F5BC734838/LINUXMINT-19.3/5.3.0-51-GENERIC/I686/B851103D78>) |
| 13fe:1716 | 13fe:0001 | Advantech        |                                      | 1     |            | [047EAD1D70](<Desktop/Intel/SKYBAY/SKYBAY/9321BED375C6/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/047EAD1D70>) |
| 14e4:4118 | 14e4:0449 | Broadcom         |                                      | 1     |            | [C5AF84EE59](<Desktop/Gigabyte Technology/GA-MA770/GA-MA770T-UD3P/C732BBC88C3B/NOBARA-39/6.8.12-200.FSYNC.FC39.X86_64/X86_64/C5AF84EE59>) |
| 8086:1aa2 | 8086:7270 | Intel            | Integrated Sensor Solution           | 1     | intel_i... | [555A26F0D1](<Tablet/Intel/570x/570x DVT3/469D9CAF87D4/UBUNTU-CORE-20/5.4.0-62-GENERIC/X86_64/555A26F0D1>) |
| 8086:31a2 | 1025:129f | Intel            | Celeron/Pentium Silver Processor ... | 1     | intel_i... | [49FB79C000](<Notebook/Acer/TravelMate/TravelMate B118-M/C101A48C0FE2/ROSA-2016.1/5.4.32-GENERIC-2ROSA-X86_64/X86_64/49FB79C000>) |
| 8086:31a2 | 103c:85c1 | Intel            | Celeron/Pentium Silver Processor ... | 1     | intel_i... | [65FB648DF4](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible 11-ap0xxx/5EC48296BEA7/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/65FB648DF4>) |
| 8086:31a2 | 1043:1df2 | Intel            | Celeron/Pentium Silver Processor ... | 1     | intel_i... | [20B96224F6](<Convertible/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop TP401MARB_TP401MA/DB5AA69C7E43/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/20B96224F6>) |
| 8086:31a2 | 17aa:380c | Intel            | Celeron/Pentium Silver Processor ... | 1     | intel_i... | [D36B6385D2](<Convertible/Lenovo/300e/300e 2nd Gen 81M9/C7FDC6E45ED6/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/D36B6385D2>) |
| 8086:31a2 | 8086:31a2 | Intel            | Celeron/Pentium Silver Processor ... | 1     | intel_i... | [6358B586AC](<Desktop/XDO.AI/Pantera/Pantera Pico PC/9E9CB9D1352E/UBUNTU-22.04/6.2.0-39-GENERIC/X86_64/6358B586AC>) |
| 8086:5aa2 | 1043:1d60 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | intel_i... | [45B1907784](<Convertible/ASUSTek Computer/TP203/TP203NAS/D92D607D906A/FEDORA-33/5.7.0-1.FC33.X86_64/X86_64/45B1907784>) |
| 8086:5aa2 | 8086:5aa2 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | intel_i... | [81F53ABE10](<Desktop/AAEON/UP-APL/UP-APL03/C8437EC8BF3C/UBUNTU-22.04/5.15.0-97-GENERIC/X86_64/81F53ABE10>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:43d5 | 1b21:1142 | AMD              | 400 Series Chipset USB 3.1 xHCI C... | 5014  | xhci_hcd   | [FDA84AF6B6](<Desktop/MSI/MS-7/MS-7A40/DC07AAAD39A3/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/FDA84AF6B6>) |
| 1022:149c | 1022:148c | AMD              | Matisse USB 3.0 Host Controller      | 4271  | xhci_hcd   | [D80A8FD406](<Desktop/Gigabyte Technology/X570/X570 AORUS ELITE WIFI/CC478A15F194/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/D80A8FD406>) |
| 1022:43ee | 1b21:1142 | AMD              | 500 Series Chipset USB 3.1 XHCI C... | 4144  | xhci_pci   | [88B1C0C262](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING WIFI II/B8760FB55781/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/88B1C0C262>) |
| 1022:149c | 1043:87c0 | AMD              | Matisse USB 3.0 Host Controller      | 3304  | xhci_hcd   | [88B1C0C262](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING WIFI II/B8760FB55781/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/88B1C0C262>) |
| 1106:3483 | 1106:3483 | VIA Technologies | VL805/806 xHCI USB 3.0 Controller    | 2538  | xhci_hcd   | [2B21C81822](<Desktop/ASUSTek Computer/P8Z68-V/P8Z68-V LX/4130A0D4D84A/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/2B21C81822>) |
| 8086:9a1b | 2222:1111 | Intel            | Tiger Lake-LP Thunderbolt 4 NHI #0   | 2407  | thunder... | [F10A2B06FD](<Notebook/HUAWEI/MACHD-WXX/MACHD-WXX9/FDA3F3F89271/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/F10A2B06FD>) |
| 1002:4397 | 1458:5004 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI0 Contr... | 2374  | ohci_pci   | [617C102331](<Desktop/Gigabyte Technology/GA-MA770/GA-MA770T-UD3/8220651D2E86/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/617C102331>) |
| 1002:4399 | 1458:5004 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI2 Contr... | 2374  | ohci_pci   | [617C102331](<Desktop/Gigabyte Technology/GA-MA770/GA-MA770T-UD3/8220651D2E86/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/617C102331>) |
| 1002:4396 | 1458:5004 | AMD              | SB7x0/SB8x0/SB9x0 USB EHCI Contro... | 2372  | ehci_pci   | [617C102331](<Desktop/Gigabyte Technology/GA-MA770/GA-MA770T-UD3/8220651D2E86/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/617C102331>) |
| 1022:149c | 1458:5007 | AMD              | Matisse USB 3.0 Host Controller      | 2297  | xhci_hcd   | [65B4884505](<Desktop/Gigabyte Technology/B450/B450 AORUS M/BBF1D3947E2C/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/65B4884505>) |
| 1b21:1042 | 1043:8488 | ASMedia Techn... | ASM1042 SuperSpeed USB Host Contr... | 2279  | xhci_hcd   | [2B21C81822](<Desktop/ASUSTek Computer/P8Z68-V/P8Z68-V LX/4130A0D4D84A/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/2B21C81822>) |
| 1022:149c | 1022:1486 | AMD              | Matisse USB 3.0 Host Controller      | 2234  | xhci_hcd   | [D80A8FD406](<Desktop/Gigabyte Technology/X570/X570 AORUS ELITE WIFI/CC478A15F194/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/D80A8FD406>) |
| 8086:9a13 |           | Intel            | Tiger Lake-LP Thunderbolt 4 USB C... | 2108  | xhci_pci   | [0EC4580AD5](<Convertible/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop TP470EA_TP470EA/0382B4D49694/ARCO-ROLLING/6.6.68-1-LTS/X86_64/0EC4580AD5>) |
| 1002:4396 | 1002:4396 | AMD              | SB7x0/SB8x0/SB9x0 USB EHCI Contro... | 2012  | ehci_pci   | [93D5FBC0A8](<Desktop/MSI/MS/MS-7641/FB355C80CE3D/LINUXMINT-22.1/6.8.0-51-GENERIC/X86_64/93D5FBC0A8>) |
| 8086:1c26 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 1859  | ehci_pci   | [2B21C81822](<Desktop/ASUSTek Computer/P8Z68-V/P8Z68-V LX/4130A0D4D84A/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/2B21C81822>) |
| 8086:1c2d | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 1859  | ehci_pci   | [2B21C81822](<Desktop/ASUSTek Computer/P8Z68-V/P8Z68-V LX/4130A0D4D84A/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/2B21C81822>) |
| 1022:163b | 1e44:1776 | AMD              | VanGogh USB1                         | 1747  | xhci_hcd   | [DFF6A36E92](<Notebook/Valve/Galileo/Galileo/3D6CF2B6536D/STEAMOS-3.6.20/6.5.0-VALVE22-1-NEPTUNE-65-G9A338ED8A75E/X86_64/DFF6A36E92>) |
| 8086:9d2f | 1043:201f | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 1671  | xhci_hcd   | [54B1993E1C](<Notebook/ASUSTek Computer/VivoBook/VivoBook 14_ASUS Laptop X442UF/0A38CA59E073/ENDEAVOUROS-ROLLING/6.12.7-ARCH1-1/X86_64/54B1993E1C>) |
| 1002:4397 | 1002:4397 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI0 Contr... | 1662  | ohci_pci   | [0B63013A2A](<Desktop/ASUSTek Computer/M4A79T/M4A79T Deluxe/BE3CF50E786D/LINUXMINT-21.3/5.15.0-130-GENERIC/X86_64/0B63013A2A>) |
| 8086:8c26 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 1639  | ehci_pci   | [C4C2F7FE89](<Desktop/ASUSTek Computer/All/All Series/09DD706491D9/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/C4C2F7FE89>) |
| 8086:8c31 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 1630  | xhci_hcd   | [C4C2F7FE89](<Desktop/ASUSTek Computer/All/All Series/09DD706491D9/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/C4C2F7FE89>) |
| 8086:8c2d | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 1612  | ehci_pci   | [C4C2F7FE89](<Desktop/ASUSTek Computer/All/All Series/09DD706491D9/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/C4C2F7FE89>) |
| 1022:43f7 | 1b21:1142 | AMD              | 600 Series Chipset USB 3.2 Contro... | 1586  | xhci_hcd   | [1FF9C9F7CB](<Desktop/MSI/MS-7/MS-7E26/771CE98DF000/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/1FF9C9F7CB>) |
| 1022:43bc | 1b21:1142 | AMD              | A320 USB 3.1 XHCI Host Controller    | 1528  | xhci_pci   | [A6F434CC49](<Desktop/Biostar/A320/A320MH/0E6DEFD22F3E/ARCH-ROLLING/6.12.8-ARCH1-1/X86_64/A6F434CC49>) |
| 1002:4399 | 1002:4399 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI2 Contr... | 1455  | ohci_pci   | [B2B5AA8EEC](<Desktop/ASUSTek Computer/M4/M4A89GTD-PRO-USB3/6765BA7F6E86/ZORIN-17/6.8.0-50-GENERIC/X86_64/B2B5AA8EEC>) |
| 8086:22b5 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1453  | xhci_hcd   | [496C93250D](<Tablet/Chuwi/Hi10/Hi10 pro tablet/D5A4927F3C98/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/496C93250D>) |
| 8086:27c8 | 1043:8179 | Intel            | NM10/ICH7 Family USB UHCI Control... | 1448  | uhci_hcd   | [61C106BD12](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX2-GB/B37417979A6E/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/61C106BD12>) |
| 8086:27c9 | 1043:8179 | Intel            | NM10/ICH7 Family USB UHCI Control... | 1448  | uhci_hcd   | [61C106BD12](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX2-GB/B37417979A6E/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/61C106BD12>) |
| 8086:27ca | 1043:8179 | Intel            | NM10/ICH7 Family USB UHCI Control... | 1447  | uhci_hcd   | [61C106BD12](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX2-GB/B37417979A6E/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/61C106BD12>) |
| 8086:27cb | 1043:8179 | Intel            | NM10/ICH7 Family USB UHCI Control... | 1446  | uhci_hcd   | [61C106BD12](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX2-GB/B37417979A6E/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/61C106BD12>) |
| 8086:a12f | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 1442  | xhci_hcd   | [FF2E84AB02](<Desktop/ASUSTek Computer/H110/H110M-E-M.2/4907896789F3/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/FF2E84AB02>) |
| 8086:31a8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1434  | xhci_pci   | [CB3AE7CB2A](<Notebook/Chuwi/GemiBook/GemiBook Pro/04AC8271E8B8/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CB3AE7CB2A>) |
| 8086:27cc | 1043:8179 | Intel            | NM10/ICH7 Family USB2 EHCI Contro... | 1428  | ehci_pci   | [61C106BD12](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX2-GB/B37417979A6E/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/61C106BD12>) |
| 1022:1639 | 1043:201f | AMD              | Renoir/Cezanne USB 3.1               | 1421  | xhci_pci   | [7373F056B3](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop M3604YA/CE1DCBE08790/KDE-NEON-24.04/6.8.0-51-GENERIC/X86_64/7373F056B3>) |
| 1022:43bb | 1b21:1142 | AMD              | 300 Series Chipset USB 3.1 xHCI C... | 1400  | xhci_hcd   | [A23FC83EDD](<Desktop/Gigabyte Technology/AB350/AB350-Gaming/B5A158869F92/GENTOO-2.17/6.6.67-GENTOO/X86_64/A23FC83EDD>) |
| 8086:a0ed |           | Intel            | Tiger Lake-LP USB 3.2 Gen 2x1 xHC... | 1400  | xhci_pci   | [A301B43994](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 2 20TB0003BO/B387A307D817/ARCH-ROLLING/6.12.7-ARCH1-1/X86_64/A301B43994>) |
| 1022:162c | 1e44:1776 | AMD              | VanGogh USB2                         | 1325  | xhci_hcd   | [DFF6A36E92](<Notebook/Valve/Galileo/Galileo/3D6CF2B6536D/STEAMOS-3.6.20/6.5.0-VALVE22-1-NEPTUNE-65-G9A338ED8A75E/X86_64/DFF6A36E92>) |
| 1022:1639 | 1022:1639 | AMD              | Renoir/Cezanne USB 3.1               | 1316  | xhci_pci   | [84DECD497D](<Desktop/BESSTAR Tech/HM/HM80/641CA314EE82/NOBARA-39/6.8.12-200.FSYNC.FC39.X86_64/X86_64/84DECD497D>) |
| 1b21:1142 | 1043:85bf | ASMedia Techn... | ASM1042A USB 3.0 Host Controller     | 1312  | xhci_hcd   | [BADFE83ED3](<Desktop/ASUSTek Computer/M5A97/M5A97 LE R2.0/25917080F8AD/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/BADFE83ED3>) |
| 1002:4396 | 1043:8389 | AMD              | SB7x0/SB8x0/SB9x0 USB EHCI Contro... | 1310  | ehci_pci   | [02A12F94E1](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX V2/63B73941E98E/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/02A12F94E1>) |
| 1002:4397 | 1043:8389 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI0 Contr... | 1310  | ohci_pci   | [02A12F94E1](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX V2/63B73941E98E/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/02A12F94E1>) |
| 1002:4398 | 1043:8389 | AMD              | SB7x0 USB OHCI1 Controller           | 1305  | ohci_pci   | [02A12F94E1](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX V2/63B73941E98E/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/02A12F94E1>) |
| 1002:4399 | 1043:8389 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI2 Contr... | 1305  | ohci_pci   | [02A12F94E1](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX V2/63B73941E98E/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/02A12F94E1>) |
| 8086:1e26 | 1043:84ca | Intel            | 7 Series/C216 Chipset Family USB ... | 1294  | ehci_pci   | [69679C9A35](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/05DEE4E22315/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/69679C9A35>) |
| 8086:1e2d | 1043:84ca | Intel            | 7 Series/C216 Chipset Family USB ... | 1294  | ehci_pci   | [69679C9A35](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/05DEE4E22315/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/69679C9A35>) |
| 8086:1e31 | 1043:84ca | Intel            | 7 Series/C210 Series Chipset Fami... | 1283  | xhci_pci   | [69679C9A35](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/05DEE4E22315/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/69679C9A35>) |
| 1b21:1242 | 1043:8675 | ASMedia Techn... | ASM1142 USB 3.1 Host Controller      | 1205  | xhci_hcd   | [10FD8EF9DD](<Desktop/ASUSTek Computer/TUF/TUF Z370-PLUS GAMING II/76981D36E1E4/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/10FD8EF9DD>) |
| 1002:4398 | 1458:5004 | AMD              | SB7x0 USB OHCI1 Controller           | 1193  | ohci_pci   | [617C102331](<Desktop/Gigabyte Technology/GA-MA770/GA-MA770T-UD3/8220651D2E86/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/617C102331>) |
| 8086:1c26 | 1458:5006 | Intel            | 6 Series/C200 Series Chipset Fami... | 1156  | ehci_pci   | [2EF34839F4](<Desktop/Gigabyte Technology/H61/H61M-DS2/29D58848E162/ZORIN-17/6.5.0-18-GENERIC/X86_64/2EF34839F4>) |
| 8086:1c2d | 1458:5006 | Intel            | 6 Series/C200 Series Chipset Fami... | 1156  | ehci_pci   | [2EF34839F4](<Desktop/Gigabyte Technology/H61/H61M-DS2/29D58848E162/ZORIN-17/6.5.0-18-GENERIC/X86_64/2EF34839F4>) |

### Wireless controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:7560 | 103c:893b | Intel            | XMM7560 LTE Advanced Pro Modem       | 19    | iosm       | [2C77E00968](<Notebook/Hewlett-Packard/EliteBook/EliteBook 650 15.6 inch G9 Notebook PC/88BF00AE57D0/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/2C77E00968>) |
| 8086:7560 | 1cf8:8653 | Intel            | XMM7560 LTE Advanced Pro Modem       | 6     | iosm       | [513FE36C72](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga Gen 7 21CDCTO1WW/DC4C857688DB/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/513FE36C72>) |
| 8086:7560 | 1028:5823 | Intel            | XMM7560 LTE Advanced Pro Modem       | 5     | iosm       | [05A5E1EF0F](<Notebook/Dell/Precision/Precision 3581/9E7390457F74/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/05A5E1EF0F>) |
| 14c3:4d75 | 1028:5931 | MediaTek         | T700 5G Modem [5G Solution 5000]     | 4     | mtk_t7xx   | [18C0535AA3](<Notebook/Dell/Latitude/Latitude 5440/26FCAA20C408/FEDORA-41/6.12.7-CB1.0.FC41.X86_64/X86_64/18C0535AA3>) |
| 14c3:4d75 | 1cf8:3507 | MediaTek         | T700 5G Modem [5G Solution 5000]     | 4     | mtk_t7xx   | [77BD529AE3](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon Gen 11 21HM0072UK/958E9E99CB6A/UBUNTU-23.10/6.5.0-17-GENERIC/X86_64/77BD529AE3>) |
| 14c3:4d75 | 103c:8c57 | MediaTek         | T700 5G Modem [5G Solution 5000]     | 3     | mtk_t7xx   | [97A21CD2B9](<Notebook/Hewlett-Packard/EliteBook/EliteBook 660 16 inch G11 Notebook PC/6A71E9297A1E/DEBIAN-12/6.1.0-28-AMD64/X86_64/97A21CD2B9>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:8d7c | 8086:7270 | Intel            | C610/X99 series chipset SPSR         | 368   |            | [0179690CC0](<Desktop/Intel/X/X99/4D99FA41EB21/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/0179690CC0>) |
| 8086:8d7c | 1043:8600 | Intel            | C610/X99 series chipset SPSR         | 236   |            | [A4BAA76691](<Desktop/ASUSTek Computer/All/All Series/CF381D2E06DA/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A4BAA76691>) |
| 8086:8d7c | 103c:8030 | Intel            | C610/X99 series chipset SPSR         | 114   |            | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:8d7c | 103c:212b | Intel            | C610/X99 series chipset SPSR         | 110   |            | [3CB08B6D4F](<Desktop/Hewlett-Packard/Z440/Z440 Workstation/CFB4DC644493/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/3CB08B6D4F>) |
| 10ec:816e | 10ec:8168 | Realtek Semic... | RealManage BMC                       | 109   | vfio_pci   | [6278369011](<Notebook/Hewlett-Packard/EliteBook/EliteBook 655 15.6 inch G10 Notebook PC/BF9B7A5BDB15/LINUXMINT-21.3/6.8.0-49-GENERIC/X86_64/6278369011>) |
| 8086:8d7c | 1028:0617 | Intel            | C610/X99 series chipset SPSR         | 107   |            | [CD6BA4805B](<Desktop/Dell/Precision/Precision Tower 5810/4996778B344C/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/CD6BA4805B>) |
| 8086:a1ec | 8086:7270 | Intel            | C620 Series Chipset Family MROM 0    | 93    |            | [122B21A8E4](<Server/Others/Others/Others/DB0155950DC6/DEBIAN-12/6.8.12-5-PVE/X86_64/122B21A8E4>) |
| 8086:8d7c | 1458:7270 | Intel            | C610/X99 series chipset SPSR         | 78    |            | [381EDC9377](<Desktop/Gigabyte Technology/X99-Gaming/X99-Gaming 5P/5DFC5EA98407/NOBARA-40/6.11.7-201.FSYNC.FC40.X86_64/X86_64/381EDC9377>) |
| 8086:8d7c | 1849:8d7c | Intel            | C610/X99 series chipset SPSR         | 75    |            | [168D757821](<Desktop/ASRock/X99/X99 Extreme4/F2B979B31843/UBUNTU-22.04/6.8.4-3-PVE/X86_64/168D757821>) |
| 1eac:1001 | 1eac:2001 | Quectel Wirel... | EM120R-GL LTE Modem                  | 71    | mhi_pci... | [A9E7B0DF46](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 2 20W9S3UF00/761E21263655/FEDORA-41/6.12.5-200.FC41.X86_64/X86_64/A9E7B0DF46>) |
| 8086:8d7c | 1462:7885 | Intel            | C610/X99 series chipset SPSR         | 69    |            | [9FF7B1C7A1](<Desktop/MSI/MS/MS-7885/DC2ED24074AF/UBUNTU-24.04/6.8.0-50-GENERIC/X86_64/9FF7B1C7A1>) |
| 10ec:5228 | 103c:888a | Realtek Semic... | PCIe Card Reader                     | 59    | rtsx_pci   | [4BF83CE5DC](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15-eu0xxx/AE4A7812BDFF/MANJARO-24.1.2/6.6.54-2-MANJARO/X86_64/4BF83CE5DC>) |
| 8086:a1ed | 8086:7270 | Intel            | C620 Series Chipset Family MROM 1    | 57    |            | [122B21A8E4](<Server/Others/Others/Others/DB0155950DC6/DEBIAN-12/6.8.12-5-PVE/X86_64/122B21A8E4>) |
| 10ec:5228 | 103c:8a31 | Realtek Semic... | PCIe Card Reader                     | 53    | rtsx_pci   | [CE25A532EE](<Convertible/Hewlett-Packard/ENVY/ENVY x360 2-in-1 Laptop 15-ey0xxx/366F08297125/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/CE25A532EE>) |
| 8086:8d7c | 1043:85f6 | Intel            | C610/X99 series chipset SPSR         | 44    |            | [9D140D5C3A](<Desktop/ASUSTek Computer/Z10PA-D8/Z10PA-D8 Series/1FB67FC105D9/ZORIN-17/6.5.0-45-GENERIC/X86_64/9D140D5C3A>) |
| 8086:8d7c | 1028:0618 | Intel            | C610/X99 series chipset SPSR         | 38    |            | [E89C3FD1E0](<Desktop/Dell/Precision/Precision Tower 7810/5EE8A2BCE45A/UBUNTU-20.04/5.15.0-1059-ORACLE/X86_64/E89C3FD1E0>) |
| 8086:6ff2 | 8086:6ff2 | Intel            | Broadwell-E CBo Unicast Registers 0  | 36    |            | [D27995C12E](<Desktop/ASUSTek Computer/All/All Series/EB610CEBAA80/NIXOS-25.05/6.6.64/X86_64/D27995C12E>) |
| 8086:6ff3 | 8086:6ff3 | Intel            | Broadwell-E CBo Unicast Registers 1  | 36    |            | [D27995C12E](<Desktop/ASUSTek Computer/All/All Series/EB610CEBAA80/NIXOS-25.05/6.6.64/X86_64/D27995C12E>) |
| 8086:8d7c | 103c:2129 | Intel            | C610/X99 series chipset SPSR         | 36    |            | [7C281863FB](<Desktop/Hewlett-Packard/Z840/Z840 Workstation/E41828699192/MANJARO/6.11.11-1-MANJARO/X86_64/7C281863FB>) |
| 8086:8d7c | 17aa:102f | Intel            | C610/X99 series chipset SPSR         | 36    |            | [B5F2869B8A](<Desktop/Lenovo/ThinkStation/ThinkStation P500 30A6S2UY00/462DE1B775B5/DEBIAN-12/6.1.0-26-AMD64/X86_64/B5F2869B8A>) |
| 10ec:5228 | 103c:8a29 | Realtek Semic... | PCIe Card Reader                     | 32    | rtsx_pci   | [96E3D3F74C](<Convertible/Hewlett-Packard/ENVY/ENVY x360 2-in-1 Laptop 15-ew0xxx/D64A48F4B179/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/96E3D3F74C>) |
| 1af2:a001 | 1af2:a001 | AVerMedia        | Live Gamer HD                        | 31    |            | [DD95266CF8](<Desktop/MSI/MS/MS-7882/BB04CAB02883/ARCH-ROLLING/6.12.5-ARCH1-1-61205-01/X86_64/DD95266CF8>) |
| 8086:8d7c | 1028:0619 | Intel            | C610/X99 series chipset SPSR         | 31    |            | [31A63822F9](<Desktop/Dell/Precision/Precision Tower 7910/BED0597F573A/UBUNTU-20.04/5.4.0-128-GENERIC/X86_64/31A63822F9>) |
| 8086:a1ec | 1028:073a | Intel            | C620 Series Chipset Family MROM 0    | 30    |            | [B75294443B](<Server/Dell/Precision/Precision 7920 Tower/5E36FA18A2AE/KUBUNTU-20.04/5.15.0-84-GENERIC/X86_64/B75294443B>) |
| 8086:8d7c | 8086:0000 | Intel            | C610/X99 series chipset SPSR         | 29    |            | [30659AA37A](<Server/HUAWEI/RH2288/RH2288 V3/C95D9CCBAF34/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/30659AA37A>) |
| 8086:8d7c | 103c:212a | Intel            | C610/X99 series chipset SPSR         | 27    |            | [DF1CE0A841](<Desktop/Hewlett-Packard/Z640/Z640 Workstation/013BF91BD52E/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/DF1CE0A841>) |
| 8086:a1ec | 15d9:0967 | Intel            | C620 Series Chipset Family MROM 0    | 27    |            | [01602FD84E](<Server/Supermicro/SYS-6019/SYS-6019P-WTR/0C2A376E8BE8/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/01602FD84E>) |
| 8086:8d7c | 1028:0601 | Intel            | C610/X99 series chipset SPSR         | 24    |            | [44126F8D86](<Server/Dell/PowerEdge/PowerEdge R630/23D674735CB9/GENTOO-2.15/6.6.38-GENTOO-MANS/X86_64/44126F8D86>) |
| 10ec:5228 | 103c:8a28 | Realtek Semic... | PCIe Card Reader                     | 22    | rtsx_pci   | [34BC9A0466](<Convertible/Hewlett-Packard/ENVY/ENVY x360 2-in-1 Laptop 13-bf0xxx/3757185C9397/NIXOS-24.11/6.11.0/X86_64/34BC9A0466>) |
| 8086:a1ec | 1590:00eb | Intel            | C620 Series Chipset Family MROM 0    | 22    |            | [D9F97B2071](<Server/HPE/ProLiant/ProLiant DL380 Gen10/6D60567E7E8D/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/D9F97B2071>) |
| 8086:6ff4 | 8086:6ff4 | Intel            | Broadwell-E CBo Unicast Registers 2  | 21    |            | [D27995C12E](<Desktop/ASUSTek Computer/All/All Series/EB610CEBAA80/NIXOS-25.05/6.6.64/X86_64/D27995C12E>) |
| 8086:6ff5 | 8086:6ff5 | Intel            | Broadwell-E CBo Unicast Registers 3  | 21    |            | [D27995C12E](<Desktop/ASUSTek Computer/All/All Series/EB610CEBAA80/NIXOS-25.05/6.6.64/X86_64/D27995C12E>) |
| 8086:8d7c | 15d9:0821 | Intel            | C610/X99 series chipset SPSR         | 21    |            | [98EF58F80D](<Server/Supermicro/SYS-6018/SYS-6018R-WTR/4A5A129EA8CA/CENTOS-7/3.10.0-1160.83.1.EL7.X86_64/X86_64/98EF58F80D>) |
| 8086:8d7c | 15d9:0831 | Intel            | C610/X99 series chipset SPSR         | 21    |            | [2BAD48B8D4](<Server/Silicon Mechanics/Rackform/Rackform R309.v5/8442C8D36737/DEBIAN-12/6.1.0-21-AMD64/X86_64/2BAD48B8D4>) |
| 8086:8d7c | 15d9:0844 | Intel            | C610/X99 series chipset SPSR         | 21    |            | [6AC9EF200B](<Desktop/Silicon Mechanics/Rackform/Rackform U633.v6/E42F237DB52E/DEBIAN-12/6.1.0-28-AMD64/X86_64/6AC9EF200B>) |
| 10ec:5228 | 103c:8a4f | Realtek Semic... | PCIe Card Reader                     | 20    | rtsx_pci   | [B90FC163EF](<Notebook/Hewlett-Packard/Victus/Victus by Gaming Laptop 15-fa0xxx/F52B28B7DC85/UBUNTU-22.04/6.8.0-48-GENERIC/X86_64/B90FC163EF>) |
| 8086:8d7c | 1028:0627 | Intel            | C610/X99 series chipset SPSR         | 20    |            | [72A4F63713](<Server/Dell/PowerEdge/PowerEdge R730XD/1A3F6F422946/DEBIAN-12/6.8.12-4-PVE/X86_64/72A4F63713>) |
| 10ec:5228 | 103c:8a3f | Realtek Semic... | PCIe Card Reader                     | 19    | rtsx_pci   | [4B1A134723](<Notebook/Hewlett-Packard/Victus/Victus by Gaming Laptop 15-fb0xxx/4365BB593556/FEDORA-41/6.11.5-300.FC41.X86_64/X86_64/4B1A134723>) |
| 1eac:1001 | 1eac:2003 | Quectel Wirel... | EM120R-GL LTE Modem                  | 19    | mhi_pci... | [4B6D9E080E](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon Gen 9 20XW00GNIX/9D9482659A59/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/4B6D9E080E>) |
| 8086:8d7c | 15d9:0911 | Intel            | C610/X99 series chipset SPSR         | 19    |            | [E33D406712](<Desktop/Inspur/SA5248/SA5248M4/624F01ED21C2/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/E33D406712>) |
| 8086:a1ec | 1028:0715 | Intel            | C620 Series Chipset Family MROM 0    | 19    |            | [2EA3B6BA11](<Server/Dell/PowerEdge/PowerEdge R740/102E11A0DB9A/DEBIAN-12/6.8.4-2-PVE/X86_64/2EA3B6BA11>) |
| 8086:a1ec | 1028:0739 | Intel            | C620 Series Chipset Family MROM 0    | 19    |            | [BA0626CE0A](<Server/Dell/Precision/Precision 7820 Tower/3792A2743A38/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/BA0626CE0A>) |
| 8086:a1ec | 1043:871e | Intel            | C620 Series Chipset Family MROM 0    | 18    |            | [664827DD6C](<Server/ASUSTek Computer/Pro/Pro WS C621-64L SAGE-10G Series/A1C444FAB774/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/664827DD6C>) |
| 8086:a1ec | 1458:1000 | Intel            | C620 Series Chipset Family MROM 0    | 17    |            | [F76FC4031D](<Server/PSSC Labs/SS4000/SS4000HD/13084E646FAA/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/F76FC4031D>) |
| 8086:a1ec | 8086:35ce | Intel            | C620 Series Chipset Family MROM 0    | 17    |            | [97B57F8628](<Server/YADRO/VEGMAN/VEGMAN S220 Server/91703340854B/RED-OS-7.3.1/5.15.10-1.EL7.X86_64/X86_64/97B57F8628>) |
| 8086:a1ed | 1028:073a | Intel            | C620 Series Chipset Family MROM 1    | 17    |            | [45516ED3A7](<Server/Dell/Precision/Precision 7920 Tower/4910BAFAEC76/UBUNTU-22.04/5.15.0-106-GENERIC/X86_64/45516ED3A7>) |
| 8086:8d7c | 1028:0600 | Intel            | C610/X99 series chipset SPSR         | 16    |            | [888A235104](<Server/Dell/PowerEdge/PowerEdge R730/B44B0E51BDB3/DEBIAN-12/6.8.12-4-PVE/X86_64/888A235104>) |
| 8086:8d7c | 1734:1201 | Intel            | C610/X99 series chipset SPSR         | 15    |            | [7C45C3FDC9](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2530 M1/3CE2488F0609/UBUNTU-24.04/6.8.0-40-GENERIC/X86_64/7C45C3FDC9>) |
| 10ec:5228 | 103c:8a50 | Realtek Semic... | PCIe Card Reader                     | 14    | rtsx_pci   | [6A8043A39F](<Notebook/Hewlett-Packard/Victus/Victus by Gaming Laptop 15-fa0xxx/298F274C91B4/DEVUAN-6/6.10.9-AMD64/X86_64/6A8043A39F>) |
| 10ec:5228 | 103c:8c30 | Realtek Semic... | PCIe Card Reader                     | 14    | rtsx_pci   | [E3ECDFE665](<Notebook/Hewlett-Packard/Victus/Victus by Gaming Laptop 15-fb1xxx/7D684F15C00E/FEDORA-41/6.12.4-200.FC41.X86_64/X86_64/E3ECDFE665>) |

