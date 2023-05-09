Most popular PCI devices in Tablets
-----------------------------------

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Tablets ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Digitizer pen ](#digitizer-pen-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Iommu ](#iommu-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Multimedia controller ](#multimedia-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Non-vga unclassified device ](#non-vga-unclassified-device-pci)
   * [ Sd host controller ](#sd-host-controller-pci)
   * [ Serial bus controller ](#serial-bus-controller-pci)
   * [ Serial controller ](#serial-controller-pci)
   * [ Signal processing controller ](#signal-processing-controller-pci)
   * [ Smbus ](#smbus-pci)
   * [ Sound ](#sound-pci)
   * [ Storage/ata ](#storageata-pci)
   * [ Storage/ide ](#storageide-pci)
   * [ Storage/nvme ](#storagenvme-pci)
   * [ Storage/raid ](#storageraid-pci)
   * [ System peripheral ](#system-peripheral-pci)
   * [ Unclassified device ](#unclassified-device-pci)
   * [ Usb controller ](#usb-controller-pci)

PCI Devices
-----------

Count  - number of computers with this device installed,
Driver - driver in use for this device,
Probe  - latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d18 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 258   | pcieport   | [0332AF656C](<Tablet/Microsoft/Surface/Surface Pro/F1C987F0D508/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/0332AF656C>) |
| 8086:229c | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 190   | lpc_ich    | [40D1BBA9E2](<Tablet/Hampoo/I1/I1D6_C109S_Hi10Pro/8F753D037AF0/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/40D1BBA9E2>) |
| 8086:2280 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 161   | iosf_mb... | [40D1BBA9E2](<Tablet/Hampoo/I1/I1D6_C109S_Hi10Pro/8F753D037AF0/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/40D1BBA9E2>) |
| 8086:9d14 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 153   | pcieport   | [7FD9FD4619](<Tablet/Microsoft/Surface/Surface Pro 4/11BB44FDB753/POP!_OS-22.04/6.2.14-SURFACE/X86_64/7FD9FD4619>) |
| 8086:1904 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 117   | skl_uncore | [7FD9FD4619](<Tablet/Microsoft/Surface/Surface Pro 4/11BB44FDB753/POP!_OS-22.04/6.2.14-SURFACE/X86_64/7FD9FD4619>) |
| 8086:9d48 | 8086:7270 | Intel            | Sunrise Point-LP LPC Controller      | 117   |            | [7FD9FD4619](<Tablet/Microsoft/Surface/Surface Pro 4/11BB44FDB753/POP!_OS-22.04/6.2.14-SURFACE/X86_64/7FD9FD4619>) |
| 8086:9d4e | 8086:7270 | Intel            | Sunrise Point LPC Controller/eSPI... | 117   |            | [0332AF656C](<Tablet/Microsoft/Surface/Surface Pro/F1C987F0D508/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/0332AF656C>) |
| 8086:22c8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 106   | pcieport   | [5B5EBA537A](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/E141169A4B3D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/5B5EBA537A>) |
| 8086:0a04 | 1414:0a04 | Intel            | Haswell-ULT DRAM Controller          | 98    | hsw_uncore | [27A1A2533B](<Tablet/Microsoft/Surface/Surface Pro 3/CD0693C63FAF/DEBIAN-12/6.1.0-7-AMD64/X86_64/27A1A2533B>) |
| 8086:9c43 | 1414:9c43 | Intel            | 8 Series LPC Controller              | 98    | lpc_ich    | [27A1A2533B](<Tablet/Microsoft/Surface/Surface Pro 3/CD0693C63FAF/DEBIAN-12/6.1.0-7-AMD64/X86_64/27A1A2533B>) |
| 8086:3482 | 8086:7270 | Intel            | Ice Lake-LP LPC Controller           | 92    |            | [FD7A2486F2](<Tablet/Microsoft/Surface/Surface Laptop Go/83C5E1166CAF/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/FD7A2486F2>) |
| 8086:34b0 | 8086:7270 | Intel            | Ice Lake-LP PCI Express Root Port #9 | 91    | pcieport   | [FD7A2486F2](<Tablet/Microsoft/Surface/Surface Laptop Go/83C5E1166CAF/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/FD7A2486F2>) |
| 8086:9d13 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 89    | pcieport   | [0332AF656C](<Tablet/Microsoft/Surface/Surface Pro/F1C987F0D508/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/0332AF656C>) |
| 8086:8a12 | 8086:7270 | Intel            | Ice Lake-LP Processor Host Bridge... | 85    | icl_uncore | [FD7A2486F2](<Tablet/Microsoft/Surface/Surface Laptop Go/83C5E1166CAF/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/FD7A2486F2>) |
| 8086:9c14 | 1414:9c14 | Intel            | 8 Series PCI Express Root Port 3     | 78    | pcieport   | [27A1A2533B](<Tablet/Microsoft/Surface/Surface Pro 3/CD0693C63FAF/DEBIAN-12/6.1.0-7-AMD64/X86_64/27A1A2533B>) |
| 8086:5914 | 8086:2015 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 64    | skl_uncore | [4ECEAEB7C1](<Tablet/Microsoft/Surface/Surface Book 2/1987F55FAE3C/LINUXMINT-21.1/6.2.8-SURFACE/X86_64/4ECEAEB7C1>) |
| 8086:2280 | 17aa:38e3 | Intel            | Atom/Celeron/Pentium Processor x5... | 62    | iosf_mb... | [5B5EBA537A](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/E141169A4B3D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/5B5EBA537A>) |
| 8086:229c | 17aa:380d | Intel            | Atom/Celeron/Pentium Processor x5... | 62    | lpc_ich    | [5B5EBA537A](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/E141169A4B3D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/5B5EBA537A>) |
| 8086:5904 | 8086:2015 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 60    | skl_uncore | [0332AF656C](<Tablet/Microsoft/Surface/Surface Pro/F1C987F0D508/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/0332AF656C>) |
| 8086:2280 | 17aa:3809 | Intel            | Atom/Celeron/Pentium Processor x5... | 53    | iosf_mb... | [3F12350D47](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/2E38E9723355/POP!_OS-21.04/5.15.5-76051505-GENERIC/X86_64/3F12350D47>) |
| 8086:229c | 17aa:380a | Intel            | Atom/Celeron/Pentium Processor x5... | 53    | lpc_ich    | [3F12350D47](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/2E38E9723355/POP!_OS-21.04/5.15.5-76051505-GENERIC/X86_64/3F12350D47>) |
| 8086:31e8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 48    |            | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:0f1c | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 41    | lpc_ich    | [1133B0413B](<Tablet/Lenovo/ThinkPad/ThinkPad 10 20C1002PUK/FDCBFB580589/ARCH-ROLLING/6.2.10-ARCH1-1/X86_64/1133B0413B>) |
| 8086:31d8 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 40    | pcieport   | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:9d1b | 8086:7270 | Intel            | Skylake-U/Y PCIe Port #12            | 39    | pcieport   | [13C23678AA](<Tablet/Microsoft/Surface/Surface Book/44D9147EE1C2/ZORIN-16/5.15.0-69-GENERIC/X86_64/13C23678AA>) |
| 8086:5af0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 38    |            | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |
| 8086:590c | 152d:1182 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 37    | skl_uncore | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:5ad7 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 37    | pcieport   | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |
| 8086:5ae8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 37    | lpc_ich    | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |
| 8086:9d12 | 152d:1182 | Intel            | Sunrise Point-LP PCI Express Root... | 37    | pcieport   | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:9d4b | 152d:1182 | Intel            | Skylake-U/Y LPC/eSPI Controller      | 37    |            | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:9d13 | 152d:1182 | Intel            | Sunrise Point-LP PCI Express Root... | 35    | pcieport   | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:31d9 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 34    | pcieport   | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:31da | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 34    | pcieport   | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:2280 | 1043:13a0 | Intel            | Atom/Celeron/Pentium Processor x5... | 32    | iosf_mb... | [60962892BC](<Tablet/ASUSTek Computer/T101/T101HA/5F2FAE88E834/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/60962892BC>) |
| 8086:229c | 1043:13a0 | Intel            | Atom/Celeron/Pentium Processor x5... | 32    | lpc_ich    | [60962892BC](<Tablet/ASUSTek Computer/T101/T101HA/5F2FAE88E834/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/60962892BC>) |
| 8086:22c8 | 1043:13a0 | Intel            | Atom/Celeron/Pentium Processor x5... | 32    | pcieport   | [60962892BC](<Tablet/ASUSTek Computer/T101/T101HA/5F2FAE88E834/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/60962892BC>) |
| 8086:9d16 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 31    | pcieport   | [0A26798F02](<Tablet/Microsoft/Surface/Surface Go 3/A72AEB11E982/FEDORA-38/6.2.10-1.SURFACE.FC38.X86_64/X86_64/0A26798F02>) |
| 8086:9d10 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 30    | pcieport   | [5A5E168C99](<Tablet/Microsoft/Surface/Surface Book 2/E6819C0E6E6D/KALI-2023.1/6.2.10-SURFACE/X86_64/5A5E168C99>) |
| 8086:31f0 | 8086:7270 | Intel            | Gemini Lake Host Bridge              | 29    |            | [AD63D006B6](<Tablet/Chuwi/Hi10/Hi10 XR/75B0305701C2/KDE-NEON-22.04/5.19.0-38-GENERIC/X86_64/AD63D006B6>) |
| 8086:9d16 | 152d:1182 | Intel            | Sunrise Point-LP PCI Express Root... | 28    | pcieport   | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:2280 | 103c:827c | Intel            | Atom/Celeron/Pentium Processor x5... | 24    | iosf_mb... | [815D54B61B](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/E1DE173C5065/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/815D54B61B>) |
| 8086:229c | 103c:827c | Intel            | Atom/Celeron/Pentium Processor x5... | 24    | lpc_ich    | [815D54B61B](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/E1DE173C5065/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/815D54B61B>) |
| 8086:22c8 | 103c:827c | Intel            | Atom/Celeron/Pentium Processor x5... | 23    | pcieport   | [815D54B61B](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/E1DE173C5065/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/815D54B61B>) |
| 8086:590c | 8086:2015 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 23    | skl_uncore | [0A26798F02](<Tablet/Microsoft/Surface/Surface Go 3/A72AEB11E982/FEDORA-38/6.2.10-1.SURFACE.FC38.X86_64/X86_64/0A26798F02>) |
| 8086:9d4b | 8086:7270 | Intel            | Skylake-U/Y LPC/eSPI Controller      | 23    |            | [0A26798F02](<Tablet/Microsoft/Surface/Surface Go 3/A72AEB11E982/FEDORA-38/6.2.10-1.SURFACE.FC38.X86_64/X86_64/0A26798F02>) |
| 1022:790e | 1022:790e | AMD              | FCH LPC Bridge                       | 22    |            | [672B480B96](<Tablet/AYANEO/2/2/4246C8CCCDD5/CHIMERAOS-41/6.1.21-1-LTS/X86_64/672B480B96>) |
| 8086:2280 | 1414:0009 | Intel            | Atom/Celeron/Pentium Processor x5... | 22    | iosf_mb... | [540A259700](<Tablet/Microsoft/Surface/Surface 3/78C63CBEC2C3/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/540A259700>) |
| 8086:31db | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 22    | pcieport   | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:2280 | 1043:1400 | Intel            | Atom/Celeron/Pentium Processor x5... | 21    | iosf_mb... | [3EC331DA1F](<Tablet/ASUSTek Computer/T102/T102HA/2F5B8C8AE51D/FEDORA-36/5.18.10-200.FC36.X86_64/X86_64/3EC331DA1F>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:522a | 152d:1182 | Realtek Semic... | RTS522A PCI Express Card Reader      | 35    | rtsx_pci   | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 10ec:522a | 152d:1237 | Realtek Semic... | RTS522A PCI Express Card Reader      | 24    | rtsx_pci   | [EDCDEDD65A](<Tablet/Microsoft/Surface/Surface Go 2/5B20BDF3E76F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/EDCDEDD65A>) |
| 10ec:522a | 103c:82ca | Realtek Semic... | RTS522A PCI Express Card Reader      | 21    | rtsx_pci   | [F76DC1B9B7](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/9B3C72E9E186/ARCH-ROLLING/6.2.12-ARCH1-1/X86_64/F76DC1B9B7>) |
| 10ec:5229 | 17aa:3833 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 13    | rtsx_pci   | [42DA57CF53](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGL 82H0/66D15DFB427C/UBUNTU-20.04/5.15.0-52-GENERIC/X86_64/42DA57CF53>) |
| 10ec:522a | 10ec:522a | Realtek Semic... | RTS522A PCI Express Card Reader      | 11    | rtsx_pci   | [2E70372D4B](<Tablet/Chuwi/UBook/UBook X/6D0D62C17BDF/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/2E70372D4B>) |
| 10ec:522a | 17aa:2244 | Realtek Semic... | RTS522A PCI Express Card Reader      | 11    | rtsx_pci   | [ABA0D29DD8](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJ001NFR/32F606BCA186/UBUNTU-22.10/5.19.0-29-GENERIC/X86_64/ABA0D29DD8>) |
| 10ec:5229 | 10ec:5229 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 9     | rtsx_pci   | [B756EC6728](<Tablet/Chuwi/UBook/UBook Pro/C7459ABAF3CD/DEBIAN-11/5.10.0-20-AMD64/X86_64/B756EC6728>) |
| 10ec:522a | 103c:828b | Realtek Semic... | RTS522A PCI Express Card Reader      | 9     | rtsx_pci   | [6ECC8F0BAD](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/7A82B39E3BAF/FEDORA-37/6.1.15-200.FC37.X86_64/X86_64/6ECC8F0BAD>) |
| 10ec:525a | 1028:07a4 | Realtek Semic... | RTS525A PCI Express Card Reader      | 9     | rtsx_pci   | [1717754347](<Tablet/Dell/Latitude/Latitude 5285/D75F67E269AD/UBUNTU-22.10/5.19.10-SURFACE/X86_64/1717754347>) |
| 10ec:525a | 1028:081d | Realtek Semic... | RTS525A PCI Express Card Reader      | 8     | rtsx_pci   | [88900A37B9](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/172279AB141B/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/88900A37B9>) |
| 10ec:5229 | 17aa:382e | Realtek Semic... | RTS5229 PCI Express Card Reader      | 7     | rtsx_pci   | [D4E1FD3279](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 20M3/9A2627AE7E17/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/D4E1FD3279>) |
| 10ec:525a | 1028:06e6 | Realtek Semic... | RTS525A PCI Express Card Reader      | 7     | rtsx_pci   | [C751321AB1](<Tablet/Dell/Latitude/Latitude 5175/725A65699078/FEDORA-36/5.18.18-200.FC36.X86_64/X86_64/C751321AB1>) |
| 10ec:522a | 17aa:2241 | Realtek Semic... | RTS522A PCI Express Card Reader      | 6     | rtsx_pci   | [CC6FE2D666](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/8D924D4AA03C/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/CC6FE2D666>) |
| 10ec:522a | 17aa:2243 | Realtek Semic... | RTS522A PCI Express Card Reader      | 6     | rtsx_pci   | [149C782883](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCA016JP/4766889E4D51/SIDUCTION-12/6.2.2-3-SIDUCTION-AMD64/X86_64/149C782883>) |
| 10ec:525a | 1028:06d6 | Realtek Semic... | RTS525A PCI Express Card Reader      | 6     | rtsx_pci   | [C118CA04BC](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/C118CA04BC>) |
| 10ec:525a | 10ec:525a | Realtek Semic... | RTS525A PCI Express Card Reader      | 6     | rtsx_pci   | [672B480B96](<Tablet/AYANEO/2/2/4246C8CCCDD5/CHIMERAOS-41/6.1.21-1-LTS/X86_64/672B480B96>) |
| 10ec:522a | 17aa:3823 | Realtek Semic... | RTS522A PCI Express Card Reader      | 4     | rtsx_pci   | [C81361E795](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 10IGL5 82AT/605931C0A403/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/C81361E795>) |
| 10ec:522a | 103c:82cb | Realtek Semic... | RTS522A PCI Express Card Reader      | 3     | rtsx_pci   | [9DE6B65A45](<Tablet/Hewlett-Packard/Spectre/Spectre x2 Detachable 12-c0XX/107C5ABF10E7/ARCH-ROLLING/6.2.2-ARCH1-1/X86_64/9DE6B65A45>) |
| 10ec:522a | 17aa:382a | Realtek Semic... | RTS522A PCI Express Card Reader      | 3     | rtsx_pci   | [ACF8952E47](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/37FF40E14E4D/UBUNTU-22.04/5.17.0-1015-OEM/X86_64/ACF8952E47>) |
| 10ec:525a | 1028:09ba | Realtek Semic... | RTS525A PCI Express Card Reader      | 3     | rtsx_pci   | [2DE1D6F6F5](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/7A5FB94B1DE2/ARCH-ROLLING/6.2.12-ZEN1-1-ZEN/X86_64/2DE1D6F6F5>) |
| 10ec:522a | 1025:122b | Realtek Semic... | RTS522A PCI Express Card Reader      | 2     | rtsx_pci   | [46ECB88F1D](<Tablet/Acer/Switch/Switch SW713-51GNP/3C0AE30715BA/NIXOS-22.11/6.1.9/X86_64/46ECB88F1D>) |
| 10ec:522a | 103c:824c | Realtek Semic... | RTS522A PCI Express Card Reader      | 2     | rtsx_pci   | [F2799F616C](<Tablet/Hewlett-Packard/ZBook/ZBook x2 G4/3743B487B588/ARCH-ROLLING/5.15.79-1-LTS/X86_64/F2799F616C>) |
| 10ec:522a | 17aa:3816 | Realtek Semic... | RTS522A PCI Express Card Reader      | 1     | rtsx_pci   | [2C581034EB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13IML05 82AS/6049DBFEB1C3/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/2C581034EB>) |
| 10ec:525a | 1028:0702 | Realtek Semic... | RTS525A PCI Express Card Reader      | 1     | rtsx_pci   | [CE9A3F2C74](<Tablet/Dell/XPS/XPS 12 9250/A04CD2743A76/CLEAR-LINUX-OS-35400/5.15.7-1106.NATIVE/X86_64/CE9A3F2C74>) |
| 10ec:525a | 1028:08e9 | Realtek Semic... | RTS525A PCI Express Card Reader      | 1     | rtsx_pci   | [2DD1504CF8](<Tablet/Dell/Latitude/Latitude 7200 2-in-1/420B18298724/UBUNTU-20.04/5.8.0-43-GENERIC/X86_64/2DD1504CF8>) |
| 10ec:5286 | 1558:5470 | Realtek Semic... | RTL8402 Integrated 1-LUN Card Reader | 1     | rtsx_pci   | [DD65C5ABF7](<Tablet/Lanix/Neuron/Neuron A/9C81E684C8A4/ARCH-ROLLING/5.8.14-ARCH1-1/X86_64/DD65C5ABF7>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:11a0 |           | Intel            | Merrifield SCU IPC                   | 1     | intel_s... | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:11a1 |           | Intel            | Merrifield Power Management Unit     | 1     | intel_p... | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:11a3 |           | Intel            | Co-processor                         | 1     | intel_p... | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:11a4 |           | Intel            | Co-processor                         | 1     | intel_mcu  | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d3a | 8086:7270 | Intel            | Sunrise Point-LP CSME HECI #1        | 266   | mei_me     | [0332AF656C](<Tablet/Microsoft/Surface/Surface Pro/F1C987F0D508/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/0332AF656C>) |
| 8086:9d3e |           | Intel            | iTouch Controller                    | 254   | mei_me     | [0332AF656C](<Tablet/Microsoft/Surface/Surface Pro/F1C987F0D508/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/0332AF656C>) |
| 8086:34a8 | 8086:7270 | Intel            | Ice Lake-LP Serial IO UART Contro... | 92    | intel_l... | [FD7A2486F2](<Tablet/Microsoft/Surface/Surface Laptop Go/83C5E1166CAF/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/FD7A2486F2>) |
| 8086:34e0 | 8086:7270 | Intel            | Ice Lake-LP Management Engine        | 92    | mei_me     | [FD7A2486F2](<Tablet/Microsoft/Surface/Surface Laptop Go/83C5E1166CAF/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/FD7A2486F2>) |
| 8086:9c3a | 1414:9c3a | Intel            | 8 Series HECI #0                     | 79    | mei_me     | [27A1A2533B](<Tablet/Microsoft/Surface/Surface Pro 3/CD0693C63FAF/DEBIAN-12/6.1.0-7-AMD64/X86_64/27A1A2533B>) |
| 8086:319a | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 48    | mei_me     | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:34e4 | 1414:0039 | Intel            | Precise Touch Device                 | 44    | mei_me     | [7C8D87170F](<Tablet/Microsoft/Surface/Surface Pro 7/FDDF58D50F30/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/7C8D87170F>) |
| 8086:5a9a | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 38    | mei_me     | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |
| 8086:9d3a | 152d:1182 | Intel            | Sunrise Point-LP CSME HECI #1        | 37    | mei_me     | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:9d3a | 103c:82ca | Intel            | Sunrise Point-LP CSME HECI #1        | 20    | mei_me     | [F76DC1B9B7](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/9B3C72E9E186/ARCH-ROLLING/6.2.12-ARCH1-1/X86_64/F76DC1B9B7>) |
| 8086:9c3a | 8086:9c3a | Intel            | 8 Series HECI #0                     | 19    | mei_me     | [3237FF6784](<Tablet/Microsoft/Surface/Surface Pro 2/7DF1C7B40ADE/ELEMENTARY-6.1/5.15.0-56-GENERIC/X86_64/3237FF6784>) |
| 8086:a0a8 | 8086:7270 | Intel            | Tiger Lake-LP Serial IO UART Cont... | 14    | intel_lpss | [3C50D5D61C](<Tablet/Microsoft/Surface/Surface Pro 8/C4CEE7E26DF5/MANJARO/6.2.12-ARCH1-1-SURFACE/X86_64/3C50D5D61C>) |
| 8086:a0e0 | 8086:7270 | Intel            | Tiger Lake-LP Management Engine I... | 14    | mei_me     | [3C50D5D61C](<Tablet/Microsoft/Surface/Surface Pro 8/C4CEE7E26DF5/MANJARO/6.2.12-ARCH1-1-SURFACE/X86_64/3C50D5D61C>) |
| 8086:319a | 17aa:3824 | Intel            | Celeron/Pentium Silver Processor ... | 13    | mei_me     | [42DA57CF53](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGL 82H0/66D15DFB427C/UBUNTU-20.04/5.15.0-52-GENERIC/X86_64/42DA57CF53>) |
| 8086:34e4 | 1414:0041 | Intel            | Precise Touch Device                 | 13    | mei_me     | [86291F499E](<Tablet/Microsoft/Surface/Surface Laptop 3/E40BAAC0547D/FEDORA-37/6.0.7-301.FC37.X86_64/X86_64/86291F499E>) |
| 8086:1e3a | 1414:1e3a | Intel            | 7 Series/C216 Chipset Family MEI ... | 12    | mei_me     | [0E56C5B9F7](<Tablet/Microsoft/Surface/Surface with Windows 8 Pro/F2C38254ABB9/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/0E56C5B9F7>) |
| 8086:9d3a | 152d:1237 | Intel            | Sunrise Point-LP CSME HECI #1        | 12    | mei_me     | [EDCDEDD65A](<Tablet/Microsoft/Surface/Surface Go 2/5B20BDF3E76F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/EDCDEDD65A>) |
| 8086:9d3a | 17aa:2244 | Intel            | Sunrise Point-LP CSME HECI #1        | 12    | mei_me     | [ABA0D29DD8](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJ001NFR/32F606BCA186/UBUNTU-22.10/5.19.0-29-GENERIC/X86_64/ABA0D29DD8>) |
| 8086:9d3a | 17aa:3850 | Intel            | Sunrise Point-LP CSME HECI #1        | 12    | mei_me     | [6FF1D34454](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 20M3/154D3B05B100/UBUNTU-20.04/5.15.0-58-GENERIC/X86_64/6FF1D34454>) |
| 8086:9d3a | 144d:c14f | Intel            | Sunrise Point-LP CSME HECI #1        | 11    | mei_me     | [167229560A](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/KUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/167229560A>) |
| 8086:51e0 | 1043:1c42 | Intel            | Alder Lake PCH HECI Controller       | 9     | mei_me     | [E5644591DE](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZC_GZ301ZC/D9321FF7F56A/FEDORA-37/6.2.8-300.FC37.X86_64/X86_64/E5644591DE>) |
| 8086:9d3a | 1028:07a4 | Intel            | Sunrise Point-LP CSME HECI #1        | 9     | mei_me     | [1717754347](<Tablet/Dell/Latitude/Latitude 5285/D75F67E269AD/UBUNTU-22.10/5.19.10-SURFACE/X86_64/1717754347>) |
| 8086:9d3a | 1028:081d | Intel            | Sunrise Point-LP CSME HECI #1        | 8     | mei_me     | [88900A37B9](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/172279AB141B/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/88900A37B9>) |
| 8086:9d3a | 103c:828b | Intel            | Sunrise Point-LP CSME HECI #1        | 8     | mei_me     | [6ECC8F0BAD](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/7A82B39E3BAF/FEDORA-37/6.1.15-200.FC37.X86_64/X86_64/6ECC8F0BAD>) |
| 8086:34e4 | 1414:0040 | Intel            | Precise Touch Device                 | 7     | mei_me     | [E2B8EA3F14](<Tablet/Microsoft/Surface/Surface Book 3/888400FE1CAB/LINUXMINT-21.1/5.15.0-67-GENERIC/X86_64/E2B8EA3F14>) |
| 8086:9cba | 17aa:222b | Intel            | Wildcat Point-LP MEI Controller #1   | 7     | mei_me     | [E6190D3469](<Tablet/Lenovo/ThinkPad/ThinkPad Helix 2nd 20CHS0JK00/2C8F871AAAFD/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E6190D3469>) |
| 8086:9d3a | 1028:06e6 | Intel            | Sunrise Point-LP CSME HECI #1        | 7     | mei_me     | [C751321AB1](<Tablet/Dell/Latitude/Latitude 5175/725A65699078/FEDORA-36/5.18.18-200.FC36.X86_64/X86_64/C751321AB1>) |
| 8086:9d3a | 144d:c135 | Intel            | Sunrise Point-LP CSME HECI #1        | 7     | mei_me     | [25DEDA3E27](<Tablet/Samsung Electronics/Galaxy/Galaxy TabPro S/A1DD930DF301/UBUNTU-20.04/5.4.0-90-GENERIC/X86_64/25DEDA3E27>) |
| 8086:9d3a | 17aa:3841 | Intel            | Sunrise Point-LP CSME HECI #1        | 7     | mei_me     | [D88BD74ACF](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/B632F2BAF8BF/FEDORA-38/6.2.0-0.RC0.20221221GITB6BB9676F216.10.FC38.X86_64/X86_64/D88BD74ACF>) |
| 8086:9d3a | 8086:9d3a | Intel            | Sunrise Point-LP CSME HECI #1        | 7     | mei_me     | [0F05F12004](<Tablet/Teclast/X5/X5 Pro/B130987D6E6A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0F05F12004>) |
| 8086:a0e0 | 1028:0a45 | Intel            | Tiger Lake-LP Management Engine I... | 7     | mei_me     | [5E287BBD8B](<Tablet/Dell/Latitude/Latitude 7320 Detachable/089CE6269F10/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/5E287BBD8B>) |
| 8086:a0e0 | 17aa:381e | Intel            | Tiger Lake-LP Management Engine I... | 7     | mei_me     | [5C0467F4CB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/FA8378B128F2/ZORIN-16/5.15.0-69-GENERIC/X86_64/5C0467F4CB>) |
| 8086:a0e0 | 1ec9:3e44 | Intel            | Tiger Lake-LP Management Engine I... | 7     | mei_me     | [F348E93361](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/4B50F0906809/UBUNTU-22.10/6.1.4-060104-GENERIC/X86_64/F348E93361>) |
| 8086:319a | 17aa:381f | Intel            | Celeron/Pentium Silver Processor ... | 6     | mei_me     | [C81361E795](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 10IGL5 82AT/605931C0A403/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/C81361E795>) |
| 8086:5a9a | 8086:5a9a | Intel            | Celeron N3350/Pentium N4200/Atom ... | 6     | mei_me     | [F8733FFC4D](<Tablet/ZoomSmart/A/A1002/766C759236A3/ROSA-12.3/5.15.79-GENERIC-1ROSA2021.1-X86_64/X86_64/F8733FFC4D>) |
| 8086:9d3a | 1028:06d6 | Intel            | Sunrise Point-LP CSME HECI #1        | 6     | mei_me     | [C118CA04BC](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/C118CA04BC>) |
| 8086:9d3a | 17aa:2241 | Intel            | Sunrise Point-LP CSME HECI #1        | 6     | mei_me     | [CC6FE2D666](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/8D924D4AA03C/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/CC6FE2D666>) |
| 8086:9d3a | 17aa:2243 | Intel            | Sunrise Point-LP CSME HECI #1        | 6     | mei_me     | [149C782883](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCA016JP/4766889E4D51/SIDUCTION-12/6.2.2-3-SIDUCTION-AMD64/X86_64/149C782883>) |
| 8086:02e0 | 17aa:3811 | Intel            | Comet Lake Management Engine Inte... | 5     | mei_me     | [2C581034EB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13IML05 82AS/6049DBFEB1C3/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/2C581034EB>) |
| 8086:319a | 8086:319a | Intel            | Celeron/Pentium Silver Processor ... | 5     | mei_me     | [810D937888](<Tablet/Tactus/GeoPad/GeoPad 110/0F02FAE679C1/ZORIN-16/5.15.0-56-GENERIC/X86_64/810D937888>) |
| 8086:34e4 | 1414:0042 | Intel            | Precise Touch Device                 | 5     | mei_me     | [804306660E](<Tablet/Microsoft/Surface/Surface Book 3/EC36A40ED0B3/UBUNTU-22.10/6.1.12-SURFACE/X86_64/804306660E>) |
| 8086:9c3a | 8086:7270 | Intel            | 8 Series HECI #0                     | 5     | mei_me     | [69E83BCD80](<Tablet/Lenovo/MIIX/MIIX 2 11 20327/7DF5CB4D666D/ZORIN-16/5.15.0-56-GENERIC/X86_64/69E83BCD80>) |
| 8086:9d3a | 1025:111e | Intel            | Sunrise Point-LP CSME HECI #1        | 5     | mei_me     | [C9900A8E2F](<Tablet/Acer/Switch/Switch SA5-271P/DFFCE0790341/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C9900A8E2F>) |
| 8086:9d3a | 103c:8414 | Intel            | Sunrise Point-LP CSME HECI #1        | 5     | mei_me     | [E8D1866113](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/AC04F34CD8CA/DEBIAN/6.0.0-5-AMD64/X86_64/E8D1866113>) |
| 8086:a0e0 | 17aa:508b | Intel            | Tiger Lake-LP Management Engine I... | 5     | mei_me     | [89ADCCAE04](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UVS1RL00/ECF244BC1E85/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/89ADCCAE04>) |
| 8086:4de0 | 103c:8966 | Intel            | Management Engine Interface          | 4     | mei_me     | [169454762C](<Tablet/Hewlett-Packard/Tablet/Tablet 11m-be0xxx/535A9A46FE41/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/169454762C>) |
| 8086:9d3a | 1028:07a5 | Intel            | Sunrise Point-LP CSME HECI #1        | 4     | mei_me     | [0EC990AB1E](<Tablet/Dell/Latitude/Latitude 7285/D6569A451159/ZORIN-16/5.13.0-40-GENERIC/X86_64/0EC990AB1E>) |
| 8086:9d3a | 17aa:382b | Intel            | Sunrise Point-LP CSME HECI #1        | 4     | mei_me     | [D43709B2F7](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/B40E17CB6AAF/UBUNTU-22.10/5.19.0-26-GENERIC/X86_64/D43709B2F7>) |
| 8086:9d3a | 19e5:3e00 | Intel            | Sunrise Point-LP CSME HECI #1        | 4     | mei_me     | [1DE7D37B18](<Tablet/HUAWEI/MateBook/MateBook HZ-W09/8B29CCECA159/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/1DE7D37B18>) |
| 8086:02a8 | 1028:09ba | Intel            | Comet Lake PCH-LP LPSS: UART #0      | 3     | intel_l... | [2DE1D6F6F5](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/7A5FB94B1DE2/ARCH-ROLLING/6.2.12-ZEN1-1-ZEN/X86_64/2DE1D6F6F5>) |

### Digitizer pen (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a0d0 | 1414:0055 | Intel            | Tiger Lake-LP Precise Touch and S... | 5     | ithc       | [3C50D5D61C](<Tablet/Microsoft/Surface/Surface Pro 8/C4CEE7E26DF5/MANJARO/6.2.12-ARCH1-1-SURFACE/X86_64/3C50D5D61C>) |
| 8086:a0d0 | 1414:0049 | Intel            | Tiger Lake-LP Precise Touch and S... | 3     | ithc       | [084F1CF7CB](<Tablet/Microsoft/Surface/Surface Laptop Studio/150859BACF06/FEDORA-37/6.0.12-1.SURFACE.FC37.X86_64/X86_64/084F1CF7CB>) |
| 8086:a0d0 | 1414:0053 | Intel            | Tiger Lake-LP Precise Touch and S... | 3     |            | [A721B1B9D6](<Tablet/Microsoft/Surface/Surface Laptop 4/6FFF009110F6/ARCH-ROLLING/6.2.6-ARCH1-1/X86_64/A721B1B9D6>) |
| 8086:a0d0 | 1414:0052 | Intel            | Tiger Lake-LP Precise Touch and S... | 1     |            | [78DDF23352](<Tablet/Microsoft/Surface/Surface Laptop 4/91B62F4C70C1/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/78DDF23352>) |
| 8086:a0d0 | 1414:0056 | Intel            | Tiger Lake-LP Precise Touch and S... | 1     |            | [A4AEFCD9B2](<Tablet/Microsoft/Surface/Surface Pro 7+/B513B8EA5A0E/FEDORA-32/5.10.10-1.SURFACE.FC32.X86_64/X86_64/A4AEFCD9B2>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2298 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 190   | mei_txe    | [40D1BBA9E2](<Tablet/Hampoo/I1/I1D6_C109S_Hi10Pro/8F753D037AF0/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/40D1BBA9E2>) |
| 8086:2298 | 17aa:380c | Intel            | Atom/Celeron/Pentium Processor x5... | 62    | mei_txe    | [5B5EBA537A](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/E141169A4B3D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/5B5EBA537A>) |
| 8086:2298 | 17aa:380a | Intel            | Atom/Celeron/Pentium Processor x5... | 53    | mei_txe    | [3F12350D47](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/2E38E9723355/POP!_OS-21.04/5.15.5-76051505-GENERIC/X86_64/3F12350D47>) |
| 8086:0f18 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 40    | mei_txe    | [1133B0413B](<Tablet/Lenovo/ThinkPad/ThinkPad 10 20C1002PUK/FDCBFB580589/ARCH-ROLLING/6.2.10-ARCH1-1/X86_64/1133B0413B>) |
| 8086:2298 | 1043:13a0 | Intel            | Atom/Celeron/Pentium Processor x5... | 32    | mei_txe    | [60962892BC](<Tablet/ASUSTek Computer/T101/T101HA/5F2FAE88E834/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/60962892BC>) |
| 8086:2298 | 103c:827c | Intel            | Atom/Celeron/Pentium Processor x5... | 24    | mei_txe    | [815D54B61B](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/E1DE173C5065/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/815D54B61B>) |
| 8086:2298 | 1043:1400 | Intel            | Atom/Celeron/Pentium Processor x5... | 21    | mei_txe    | [3EC331DA1F](<Tablet/ASUSTek Computer/T102/T102HA/2F5B8C8AE51D/FEDORA-36/5.18.10-200.FC36.X86_64/X86_64/3EC331DA1F>) |
| 1022:15df | 1022:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 16    | ccp        | [88EA27E220](<Tablet/Microsoft/Surface/Surface Laptop 3/49F309623B33/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/88EA27E220>) |
| 8086:0f18 | 1019:99a5 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 13    | mei_txe    | [C35A8D75CE](<Tablet/Intel/powered/powered classmate PC/E3EDE14D59EF/LINUXMINT-20.2/5.4.0-135-GENERIC/X86_64/C35A8D75CE>) |
| 8086:0f18 | 103c:815d | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 11    | mei_txe    | [EC3A161D36](<Tablet/Hewlett-Packard/Pavilion/Pavilion x2 Detachable/ACF95D095277/FEDORA-38/6.2.7-300.FC38.X86_64/X86_64/EC3A161D36>) |
| 8086:2298 | 103c:82f4 | Intel            | Atom/Celeron/Pentium Processor x5... | 9     | mei_txe    | [863136882E](<Tablet/Hewlett-Packard/x2/x2 210 G2/F90A1440D6C0/LINUXMINT-20.2/5.4.0-137-GENERIC/X86_64/863136882E>) |
| 8086:2298 | 1043:1c60 | Intel            | Atom/Celeron/Pentium Processor x5... | 9     | mei_txe    | [961E13C584](<Tablet/ASUSTek Computer/T103/T103HAF/DC30228D2ADB/LINUXMINT-20.3/5.4.0-148-GENERIC/X86_64/961E13C584>) |
| 8086:0f18 | 17aa:3906 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 8     | mei_txe    | [7F6BE7CFFE](<Tablet/Lenovo/MIIX/MIIX 3-1030 80HV/A62D4DE83290/KDE-NEON-22.04/5.15.0-56-GENERIC/X86_64/7F6BE7CFFE>) |
| 8086:0f18 | 17aa:390b | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 8     | mei_txe    | [B9E3C45CAA](<Tablet/Lenovo/MIIX/MIIX 300-10IBY 80NR/F1574B822916/ARCH-ROLLING/6.0.10-ARCH2-1/X86_64/B9E3C45CAA>) |
| 1022:1649 | 1022:1649 | AMD              | VanGogh PSP/CCP                      | 6     | ccp        | [672B480B96](<Tablet/AYANEO/2/2/4246C8CCCDD5/CHIMERAOS-41/6.1.21-1-LTS/X86_64/672B480B96>) |
| 8086:0f18 | 1019:99a1 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | mei_txe    | [C61A96D514](<Tablet/Medion/P/P2212T/71C4E4B2F18A/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/C61A96D514>) |
| 8086:0f18 | 103c:8031 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | mei_txe    | [D1FC8D3488](<Tablet/Hewlett-Packard/Stream/Stream 7 Tablet/D587623494BA/UBUNTU-18.04/5.4.0-99-GENERIC/I686/D1FC8D3488>) |
| 8086:0f18 | 8086:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | mei_txe    | [7502CE9679](<Tablet/Medion/S1219T/S1219T MD99922/505B03FFDB41/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/7502CE9679>) |
| 8086:0f18 | 103c:8032 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     | mei_txe    | [211438A893](<Tablet/Hewlett-Packard/Stream/Stream 8 Tablet/54B442EB7035/DEBIAN-11/5.10.0-20-686/I686/211438A893>) |
| 8086:0f18 | 1509:7018 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | mei_txe    | [9347717861](<Tablet/Xplore/iX101/iX101B1/988A604FB8AB/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/9347717861>) |
| 8086:0f18 | 17aa:3900 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | mei_txe    | [4E4D2ED404](<Tablet/Lenovo/MIIX/MIIX 2 8 20326/0C23042EF88F/ENDLESS-4.0.7/5.11.0-35-GENERIC/X86_64/4E4D2ED404>) |
| 8086:0f18 | 17aa:3985 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | mei_txe    | [212388E78B](<Tablet/Lenovo/MIIX/MIIX 2 10 20359/516241B1CF51/DEBIAN-11/5.10.0-10-AMD64/X86_64/212388E78B>) |
| 8086:0f18 | 1854:0211 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | mei_txe    | [44AF16AC16](<Tablet/LG Electronics/15U340/15U340-L.BK55P1/96572D02BF5F/LINUXMINT-20/5.4.0-42-GENERIC/X86_64/44AF16AC16>) |
| 1022:1537 | 103c:22ea | AMD              | Kabini/Mullins PSP-Platform Secur... | 1     | ccp        | [4618D27B09](<Tablet/Zinox Technologies/x64-Based/x64-Based PC/B8682FC1F33D/ZORIN-16/5.15.0-46-GENERIC/X86_64/4618D27B09>) |
| 8086:0f18 | 1019:980b | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [B09FE8903A](<Tablet/Intel/Education/Education Tablet/DEFE34A6E3C6/ENDLESS-3.8.7/5.4.0-42-GENERIC/X86_64/B09FE8903A>) |
| 8086:0f18 | 1025:0949 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [4784D8BAAE](<Tablet/Acer/Iconia/Iconia W1-810/A5F3CE2357F6/LINUXMINT-20.1/5.4.0-73-GENERIC/X86_64/4784D8BAAE>) |
| 8086:0f18 | 1558:5470 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [DD65C5ABF7](<Tablet/Lanix/Neuron/Neuron A/9C81E684C8A4/ARCH-ROLLING/5.8.14-ARCH1-1/X86_64/DD65C5ABF7>) |
| 8086:0f18 | 17aa:3915 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [621742BA14](<Tablet/Lenovo/MIIX/MIIX 3-830 80JB/DF2D4D9C1EB5/ARCH/5.18.5-ARCH1-1/X86_64/621742BA14>) |
| 8086:0f18 | 17aa:6080 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [06FE78096E](<Tablet/NEC Computers/PC-TW508/PC-TW508CAS/825BA310157C/ZORIN-16/5.11.0-41-GENERIC/X86_64/06FE78096E>) |
| 8086:1198 |           | Intel            | Encryption controller                | 1     |            | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:2298 | 10cf:191b | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | mei_txe    | [50862798B5](<Tablet/Fujitsu/STYLISTIC/STYLISTIC Q508/AB22D0A4D65B/ZORIN-16/5.15.0-69-GENERIC/X86_64/50862798B5>) |
| 8086:2298 | 1854:0280 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | mei_txe    | [A6AB074BB5](<Tablet/LG Electronics/10T370/10T370-L860K/FC0AE2C9A307/ENDLESS-3.9.1/5.8.0-14-GENERIC/X86_64/A6AB074BB5>) |
| 8086:2298 | 1bfd:0001 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | mei_txe    | [1BA20022CB](<Tablet/Medion/E1239T/E1239T MD60791/B4344693BF47/ENDLESS-3.9.0/5.8.0-14-GENERIC/X86_64/1BA20022CB>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:22b0 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 160   | i915       | [40D1BBA9E2](<Tablet/Hampoo/I1/I1D6_C109S_Hi10Pro/8F753D037AF0/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/40D1BBA9E2>) |
| 8086:22b0 | 17aa:38e3 | Intel            | Atom/Celeron/Pentium Processor x5... | 62    | i915       | [5B5EBA537A](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/E141169A4B3D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/5B5EBA537A>) |
| 8086:1916 | 1414:0015 | Intel            | Skylake GT2 [HD Graphics 520]        | 61    | i915       | [7FD9FD4619](<Tablet/Microsoft/Surface/Surface Pro 4/11BB44FDB753/POP!_OS-22.04/6.2.14-SURFACE/X86_64/7FD9FD4619>) |
| 8086:0a16 | 1414:0005 | Intel            | Haswell-ULT Integrated Graphics C... | 53    | i915       | [27A1A2533B](<Tablet/Microsoft/Surface/Surface Pro 3/CD0693C63FAF/DEBIAN-12/6.1.0-7-AMD64/X86_64/27A1A2533B>) |
| 8086:22b0 | 17aa:3809 | Intel            | Atom/Celeron/Pentium Processor x5... | 53    | i915       | [3F12350D47](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/2E38E9723355/POP!_OS-21.04/5.15.5-76051505-GENERIC/X86_64/3F12350D47>) |
| 8086:1916 | 1414:0014 | Intel            | Skylake GT2 [HD Graphics 520]        | 39    | i915       | [13C23678AA](<Tablet/Microsoft/Surface/Surface Book/44D9147EE1C2/ZORIN-16/5.15.0-69-GENERIC/X86_64/13C23678AA>) |
| 8086:591e | 152d:1182 | Intel            | HD Graphics 615                      | 37    | i915       | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:5916 | 1414:0026 | Intel            | HD Graphics 620                      | 35    | i915       | [8B89FFD983](<Tablet/Microsoft/Surface/Surface Pro/40EF290D863C/ZORIN-16/5.15.0-71-GENERIC/X86_64/8B89FFD983>) |
| 8086:22b0 | 1043:13a0 | Intel            | Atom/Celeron/Pentium Processor x5... | 32    | i915       | [60962892BC](<Tablet/ASUSTek Computer/T101/T101HA/5F2FAE88E834/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/60962892BC>) |
| 8086:3185 | 8086:2212 | Intel            | GeminiLake [UHD Graphics 600]        | 29    | i915       | [AD63D006B6](<Tablet/Chuwi/Hi10/Hi10 XR/75B0305701C2/KDE-NEON-22.04/5.19.0-38-GENERIC/X86_64/AD63D006B6>) |
| 8086:5917 | 1414:0026 | Intel            | UHD Graphics 620                     | 28    | i915       | [82ECC9AC72](<Tablet/Microsoft/Surface/Surface Pro 6/289D8715C794/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/82ECC9AC72>) |
| 8086:22b0 | 103c:827c | Intel            | Atom/Celeron/Pentium Processor x5... | 24    | i915       | [815D54B61B](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/E1DE173C5065/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/815D54B61B>) |
| 8086:22b0 | 1414:0009 | Intel            | Atom/Celeron/Pentium Processor x5... | 22    | i915       | [540A259700](<Tablet/Microsoft/Surface/Surface 3/78C63CBEC2C3/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/540A259700>) |
| 8086:8a56 | 1414:0047 | Intel            | Iris Plus Graphics G1 (Ice Lake)     | 22    | i915       | [FD7A2486F2](<Tablet/Microsoft/Surface/Surface Laptop Go/83C5E1166CAF/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/FD7A2486F2>) |
| 8086:22b0 | 1043:1400 | Intel            | Atom/Celeron/Pentium Processor x5... | 21    | i915       | [3EC331DA1F](<Tablet/ASUSTek Computer/T102/T102HA/2F5B8C8AE51D/FEDORA-36/5.18.10-200.FC36.X86_64/X86_64/3EC331DA1F>) |
| 8086:5916 | 103c:82ca | Intel            | HD Graphics 620                      | 21    | i915       | [F76DC1B9B7](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/9B3C72E9E186/ARCH-ROLLING/6.2.12-ARCH1-1/X86_64/F76DC1B9B7>) |
| 8086:8a5a | 1414:0037 | Intel            | Iris Plus Graphics G4 (Ice Lake)     | 20    | i915       | [6AC02F43F2](<Tablet/Microsoft/Surface/Surface Pro 7/B56D9702AD9F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/6AC02F43F2>) |
| 8086:0a16 | 1414:0a16 | Intel            | Haswell-ULT Integrated Graphics C... | 19    | i915       | [3237FF6784](<Tablet/Microsoft/Surface/Surface Pro 2/7DF1C7B40ADE/ELEMENTARY-6.1/5.15.0-56-GENERIC/X86_64/3237FF6784>) |
| 8086:0a26 | 1414:0005 | Intel            | Haswell-ULT Integrated Graphics C... | 18    | i915       | [EEDAF9F548](<Tablet/Microsoft/Surface/Surface Pro 3/3E05E7344F39/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/EEDAF9F548>) |
| 8086:0f31 | 17aa:221b | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 17    | i915       | [1133B0413B](<Tablet/Lenovo/ThinkPad/ThinkPad 10 20C1002PUK/FDCBFB580589/ARCH-ROLLING/6.2.10-ARCH1-1/X86_64/1133B0413B>) |
| 8086:0f31 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 17    | i915       | [3DCF212C95](<Tablet/Intel/VALLEYVIEW/VALLEYVIEW C0 PLATFORM/62CB1AFCD4CA/FEDORA-35/6.3.0-RC4+/X86_64/3DCF212C95>) |
| 8086:1926 | 1414:0015 | Intel            | Iris Graphics 540                    | 17    | i915       | [DBA0167A53](<Tablet/Microsoft/Surface/Surface Pro 4/F2CBD99647FA/ZORIN-16/5.15.0-60-GENERIC/X86_64/DBA0167A53>) |
| 8086:5a85 | 8086:2212 | Intel            | HD Graphics 500                      | 17    | i915       | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |
| 8086:8a52 | 1414:0037 | Intel            | Iris Plus Graphics G7                | 17    | i915       | [A2B5435974](<Tablet/Microsoft/Surface/Surface Pro 7/108401A4F56A/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/A2B5435974>) |
| 1002:9804 | 1025:0577 | AMD              | Wrestler [Radeon HD 6250]            | 14    | radeon     | [C3D132FB91](<Tablet/Acer/Iconia/Iconia Tab W501/B59AD5DD817B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C3D132FB91>) |
| 8086:5917 | 1414:0027 | Intel            | UHD Graphics 620                     | 14    | i915       | [4ECEAEB7C1](<Tablet/Microsoft/Surface/Surface Book 2/1987F55FAE3C/LINUXMINT-21.1/6.2.8-SURFACE/X86_64/4ECEAEB7C1>) |
| 8086:5917 | 1414:0028 | Intel            | UHD Graphics 620                     | 14    | i915       | [4D293DA8B1](<Tablet/Microsoft/Surface/Surface Book 2/75D314F90E98/LINUXMINT-21.1/5.15.0-67-GENERIC/X86_64/4D293DA8B1>) |
| 8086:8a52 | 1414:0035 | Intel            | Iris Plus Graphics G7                | 14    | i915       | [86291F499E](<Tablet/Microsoft/Surface/Surface Laptop 3/E40BAAC0547D/FEDORA-37/6.0.7-301.FC37.X86_64/X86_64/86291F499E>) |
| 8086:0f31 | 1019:99a5 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 13    | i915       | [C35A8D75CE](<Tablet/Intel/powered/powered classmate PC/E3EDE14D59EF/LINUXMINT-20.2/5.4.0-135-GENERIC/X86_64/C35A8D75CE>) |
| 8086:0166 | 1414:0166 | Intel            | 3rd Gen Core processor Graphics C... | 12    | i915       | [0E56C5B9F7](<Tablet/Microsoft/Surface/Surface with Windows 8 Pro/F2C38254ABB9/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/0E56C5B9F7>) |
| 8086:5917 | 17aa:2244 | Intel            | UHD Graphics 620                     | 12    | i915       | [ABA0D29DD8](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJ001NFR/32F606BCA186/UBUNTU-22.10/5.19.0-29-GENERIC/X86_64/ABA0D29DD8>) |
| 8086:591c | 152d:1237 | Intel            | UHD Graphics 615                     | 12    | i915       | [EDCDEDD65A](<Tablet/Microsoft/Surface/Surface Go 2/5B20BDF3E76F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/EDCDEDD65A>) |
| 8086:8a52 | 1414:0043 | Intel            | Iris Plus Graphics G7                | 12    | i915       | [E2B8EA3F14](<Tablet/Microsoft/Surface/Surface Book 3/888400FE1CAB/LINUXMINT-21.1/5.15.0-67-GENERIC/X86_64/E2B8EA3F14>) |
| 8086:0f31 | 103c:815d | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 11    | i915       | [EC3A161D36](<Tablet/Hewlett-Packard/Pavilion/Pavilion x2 Detachable/ACF95D095277/FEDORA-38/6.2.7-300.FC38.X86_64/X86_64/EC3A161D36>) |
| 8086:5916 | 144d:c14f | Intel            | HD Graphics 620                      | 11    | i915       | [167229560A](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/KUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/167229560A>) |
| 8086:5917 | 17aa:397a | Intel            | UHD Graphics 620                     | 11    | i915       | [6FF1D34454](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 20M3/154D3B05B100/UBUNTU-20.04/5.15.0-58-GENERIC/X86_64/6FF1D34454>) |
| 10de:1c20 | 1414:0024 | Nvidia           | GP106M [GeForce GTX 1060 Mobile]     | 10    | nvidia     | [4D293DA8B1](<Tablet/Microsoft/Surface/Surface Book 2/75D314F90E98/LINUXMINT-21.1/5.15.0-67-GENERIC/X86_64/4D293DA8B1>) |
| 10de:1c8d | 1414:0024 | Nvidia           | GP107M [GeForce GTX 1050 Mobile]     | 10    | nvidia     | [4ECEAEB7C1](<Tablet/Microsoft/Surface/Surface Book 2/1987F55FAE3C/LINUXMINT-21.1/6.2.8-SURFACE/X86_64/4ECEAEB7C1>) |
| 8086:5916 | 1414:0025 | Intel            | HD Graphics 620                      | 10    | i915       | [391D13C7BA](<Tablet/Microsoft/Surface/Surface Laptop/CE57AD890443/KUBUNTU-22.04/5.15.0-56-GENERIC/X86_64/391D13C7BA>) |
| 8086:591c | 152d:1339 | Intel            | UHD Graphics 615                     | 10    | i915       | [0A26798F02](<Tablet/Microsoft/Surface/Surface Go 3/A72AEB11E982/FEDORA-38/6.2.10-1.SURFACE.FC38.X86_64/X86_64/0A26798F02>) |
| 8086:22b0 | 103c:82f4 | Intel            | Atom/Celeron/Pentium Processor x5... | 9     | i915       | [863136882E](<Tablet/Hewlett-Packard/x2/x2 210 G2/F90A1440D6C0/LINUXMINT-20.2/5.4.0-137-GENERIC/X86_64/863136882E>) |
| 8086:22b0 | 1043:1c60 | Intel            | Atom/Celeron/Pentium Processor x5... | 9     | i915       | [961E13C584](<Tablet/ASUSTek Computer/T103/T103HAF/DC30228D2ADB/LINUXMINT-20.3/5.4.0-148-GENERIC/X86_64/961E13C584>) |
| 8086:3185 | 17aa:39ff | Intel            | GeminiLake [UHD Graphics 600]        | 9     | i915       | [42DA57CF53](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGL 82H0/66D15DFB427C/UBUNTU-20.04/5.15.0-52-GENERIC/X86_64/42DA57CF53>) |
| 8086:5916 | 1028:07a4 | Intel            | HD Graphics 620                      | 9     | i915       | [1717754347](<Tablet/Dell/Latitude/Latitude 5285/D75F67E269AD/UBUNTU-22.10/5.19.10-SURFACE/X86_64/1717754347>) |
| 8086:591e | 103c:828b | Intel            | HD Graphics 615                      | 9     | i915       | [6ECC8F0BAD](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/7A82B39E3BAF/FEDORA-37/6.1.15-200.FC37.X86_64/X86_64/6ECC8F0BAD>) |
| 8086:0a1e | 1414:0005 | Intel            | Haswell-ULT Integrated Graphics C... | 8     | i915       | [F4C9D49611](<Tablet/Microsoft/Surface/Surface Pro 3/8481DC1AC1F1/POP!_OS-21.10/5.15.8-76051508-GENERIC/X86_64/F4C9D49611>) |
| 8086:0f31 | 17aa:3906 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 8     | i915       | [7F6BE7CFFE](<Tablet/Lenovo/MIIX/MIIX 3-1030 80HV/A62D4DE83290/KDE-NEON-22.04/5.15.0-56-GENERIC/X86_64/7F6BE7CFFE>) |
| 8086:0f31 | 17aa:390b | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 8     | i915       | [B9E3C45CAA](<Tablet/Lenovo/MIIX/MIIX 300-10IBY 80NR/F1574B822916/ARCH-ROLLING/6.0.10-ARCH2-1/X86_64/B9E3C45CAA>) |
| 8086:5917 | 1028:081d | Intel            | UHD Graphics 620                     | 8     | i915       | [88900A37B9](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/172279AB141B/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/88900A37B9>) |
| 8086:5917 | 1414:0025 | Intel            | UHD Graphics 620                     | 8     | i915       | [58900F0CAA](<Tablet/Microsoft/Surface/Surface Laptop 2/1236055B02AE/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/58900F0CAA>) |

### Iommu (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1631 | 1022:1631 | AMD              | Renoir/Cezanne IOMMU                 | 10    |            | [D721C7AE17](<Tablet/ONE-NETBOOK TECHNOLOGY/ONE/ONE XPLAYER/B9BDBF250081/CHIMERAOS-37/6.0.8-ARCH1-1/X86_64/D721C7AE17>) |
| 1022:14b6 | 1022:14b6 | AMD              | Family 17h-19h IOMMU                 | 6     |            | [672B480B96](<Tablet/AYANEO/2/2/4246C8CCCDD5/CHIMERAOS-41/6.1.21-1-LTS/X86_64/672B480B96>) |
| 1022:15d1 | 1022:15d1 | AMD              | Raven/Raven2 IOMMU                   | 6     |            | [88EA27E220](<Tablet/Microsoft/Surface/Surface Laptop 3/49F309623B33/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/88EA27E220>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d21 | 8086:7270 | Intel            | Sunrise Point-LP PMC                 | 270   |            | [0332AF656C](<Tablet/Microsoft/Surface/Surface Pro/F1C987F0D508/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/0332AF656C>) |
| 8086:34ef |           | Intel            | Ice Lake-LP DRAM Controller          | 92    |            | [FD7A2486F2](<Tablet/Microsoft/Surface/Surface Laptop Go/83C5E1166CAF/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/FD7A2486F2>) |
| 8086:9d21 | 152d:1182 | Intel            | Sunrise Point-LP PMC                 | 37    |            | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:9d21 | 103c:82ca | Intel            | Sunrise Point-LP PMC                 | 21    |            | [F76DC1B9B7](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/9B3C72E9E186/ARCH-ROLLING/6.2.12-ARCH1-1/X86_64/F76DC1B9B7>) |
| 8086:a0ef | 8086:7270 | Intel            | Tiger Lake-LP Shared SRAM            | 14    |            | [3C50D5D61C](<Tablet/Microsoft/Surface/Surface Pro 8/C4CEE7E26DF5/MANJARO/6.2.12-ARCH1-1-SURFACE/X86_64/3C50D5D61C>) |
| 8086:9d21 | 152d:1237 | Intel            | Sunrise Point-LP PMC                 | 12    |            | [EDCDEDD65A](<Tablet/Microsoft/Surface/Surface Go 2/5B20BDF3E76F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/EDCDEDD65A>) |
| 8086:9d21 | 17aa:2244 | Intel            | Sunrise Point-LP PMC                 | 12    |            | [ABA0D29DD8](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJ001NFR/32F606BCA186/UBUNTU-22.10/5.19.0-29-GENERIC/X86_64/ABA0D29DD8>) |
| 8086:9d21 | 17aa:3853 | Intel            | Sunrise Point-LP PMC                 | 12    |            | [6FF1D34454](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 20M3/154D3B05B100/UBUNTU-20.04/5.15.0-58-GENERIC/X86_64/6FF1D34454>) |
| 8086:9d21 | 144d:c14f | Intel            | Sunrise Point-LP PMC                 | 11    |            | [167229560A](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/KUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/167229560A>) |
| 8086:51ef | 1043:1c42 | Intel            | Alder Lake PCH Shared SRAM           | 9     |            | [E5644591DE](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZC_GZ301ZC/D9321FF7F56A/FEDORA-37/6.2.8-300.FC37.X86_64/X86_64/E5644591DE>) |
| 8086:9d21 | 1028:07a4 | Intel            | Sunrise Point-LP PMC                 | 9     |            | [1717754347](<Tablet/Dell/Latitude/Latitude 5285/D75F67E269AD/UBUNTU-22.10/5.19.10-SURFACE/X86_64/1717754347>) |
| 8086:9d21 | 103c:828b | Intel            | Sunrise Point-LP PMC                 | 9     |            | [6ECC8F0BAD](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/7A82B39E3BAF/FEDORA-37/6.1.15-200.FC37.X86_64/X86_64/6ECC8F0BAD>) |
| 8086:9d21 | 1028:081d | Intel            | Sunrise Point-LP PMC                 | 8     |            | [88900A37B9](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/172279AB141B/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/88900A37B9>) |
| 8086:9d21 | 8086:9d21 | Intel            | Sunrise Point-LP PMC                 | 8     |            | [0F05F12004](<Tablet/Teclast/X5/X5 Pro/B130987D6E6A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0F05F12004>) |
| 8086:9d21 | 1028:06e6 | Intel            | Sunrise Point-LP PMC                 | 7     |            | [C751321AB1](<Tablet/Dell/Latitude/Latitude 5175/725A65699078/FEDORA-36/5.18.18-200.FC36.X86_64/X86_64/C751321AB1>) |
| 8086:9d21 | 144d:c135 | Intel            | Sunrise Point-LP PMC                 | 7     |            | [25DEDA3E27](<Tablet/Samsung Electronics/Galaxy/Galaxy TabPro S/A1DD930DF301/UBUNTU-20.04/5.4.0-90-GENERIC/X86_64/25DEDA3E27>) |
| 8086:9d21 | 17aa:3842 | Intel            | Sunrise Point-LP PMC                 | 7     |            | [D88BD74ACF](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/B632F2BAF8BF/FEDORA-38/6.2.0-0.RC0.20221221GITB6BB9676F216.10.FC38.X86_64/X86_64/D88BD74ACF>) |
| 8086:a0ef | 1028:0a45 | Intel            | Tiger Lake-LP Shared SRAM            | 7     |            | [5E287BBD8B](<Tablet/Dell/Latitude/Latitude 7320 Detachable/089CE6269F10/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/5E287BBD8B>) |
| 8086:a0ef | 17aa:3829 | Intel            | Tiger Lake-LP Shared SRAM            | 7     |            | [5C0467F4CB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/FA8378B128F2/ZORIN-16/5.15.0-69-GENERIC/X86_64/5C0467F4CB>) |
| 8086:a0ef | 1ec9:3e44 | Intel            | Tiger Lake-LP Shared SRAM            | 7     |            | [F348E93361](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/4B50F0906809/UBUNTU-22.10/6.1.4-060104-GENERIC/X86_64/F348E93361>) |
| 8086:9d21 | 1028:06d6 | Intel            | Sunrise Point-LP PMC                 | 6     |            | [C118CA04BC](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/C118CA04BC>) |
| 8086:9d21 | 17aa:2241 | Intel            | Sunrise Point-LP PMC                 | 6     |            | [CC6FE2D666](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/8D924D4AA03C/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/CC6FE2D666>) |
| 8086:9d21 | 17aa:2243 | Intel            | Sunrise Point-LP PMC                 | 6     |            | [149C782883](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCA016JP/4766889E4D51/SIDUCTION-12/6.2.2-3-SIDUCTION-AMD64/X86_64/149C782883>) |
| 8086:02ef | 17aa:380d | Intel            | Comet Lake PCH-LP Shared SRAM        | 5     |            | [2C581034EB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13IML05 82AS/6049DBFEB1C3/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/2C581034EB>) |
| 8086:9d21 | 1025:111e | Intel            | Sunrise Point-LP PMC                 | 5     |            | [C9900A8E2F](<Tablet/Acer/Switch/Switch SA5-271P/DFFCE0790341/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C9900A8E2F>) |
| 8086:9d21 | 103c:8414 | Intel            | Sunrise Point-LP PMC                 | 5     |            | [E8D1866113](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/AC04F34CD8CA/DEBIAN/6.0.0-5-AMD64/X86_64/E8D1866113>) |
| 8086:a0ef | 17aa:508b | Intel            | Tiger Lake-LP Shared SRAM            | 5     |            | [89ADCCAE04](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UVS1RL00/ECF244BC1E85/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/89ADCCAE04>) |
| 8086:4def | 103c:8966 | Intel            | Jasper Lake Shared SRAM Controller   | 4     |            | [169454762C](<Tablet/Hewlett-Packard/Tablet/Tablet 11m-be0xxx/535A9A46FE41/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/169454762C>) |
| 8086:9d21 | 1028:07a5 | Intel            | Sunrise Point-LP PMC                 | 4     |            | [0EC990AB1E](<Tablet/Dell/Latitude/Latitude 7285/D6569A451159/ZORIN-16/5.13.0-40-GENERIC/X86_64/0EC990AB1E>) |
| 8086:9d21 | 17aa:3829 | Intel            | Sunrise Point-LP PMC                 | 4     |            | [D43709B2F7](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/B40E17CB6AAF/UBUNTU-22.10/5.19.0-26-GENERIC/X86_64/D43709B2F7>) |
| 8086:9d21 | 19e5:3e00 | Intel            | Sunrise Point-LP PMC                 | 4     |            | [1DE7D37B18](<Tablet/HUAWEI/MateBook/MateBook HZ-W09/8B29CCECA159/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/1DE7D37B18>) |
| 8086:02ef | 1028:09ba | Intel            | Comet Lake PCH-LP Shared SRAM        | 3     |            | [2DE1D6F6F5](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/7A5FB94B1DE2/ARCH-ROLLING/6.2.12-ZEN1-1-ZEN/X86_64/2DE1D6F6F5>) |
| 8086:51ef | 17aa:3828 | Intel            | Alder Lake PCH Shared SRAM           | 3     |            | [ED4AEB2282](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 5 12IAU7 82TQ/75AEF6B37790/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/ED4AEB2282>) |
| 8086:9d21 | 1025:1171 | Intel            | Sunrise Point-LP PMC                 | 3     |            | [7D44E4C760](<Tablet/Acer/Switch/Switch SW512-52/9061A4CB688E/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/7D44E4C760>) |
| 8086:9d21 | 103c:82cb | Intel            | Sunrise Point-LP PMC                 | 3     |            | [9DE6B65A45](<Tablet/Hewlett-Packard/Spectre/Spectre x2 Detachable 12-c0XX/107C5ABF10E7/ARCH-ROLLING/6.2.2-ARCH1-1/X86_64/9DE6B65A45>) |
| 8086:9d21 | 1043:1410 | Intel            | Sunrise Point-LP PMC                 | 3     |            | [B945137346](<Tablet/ASUSTek Computer/T305/T305CA/E8B080C97665/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/B945137346>) |
| 8086:9d21 | 17aa:3834 | Intel            | Sunrise Point-LP PMC                 | 3     |            | [67E1BDD5F1](<Tablet/Lenovo/MIIX/MIIX 720-12IKB 80VV/F45F8CE4052D/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/67E1BDD5F1>) |
| 8086:9def | 103c:85b9 | Intel            | Cannon Point-LP Shared SRAM          | 3     |            | [D49CBA4016](<Tablet/Hewlett-Packard/Elite/Elite x2 G4/D4F39DF208E2/LINUXMINT-21.1/6.0.0-1012-OEM/X86_64/D49CBA4016>) |
| 8086:4def |           | Intel            | Jasper Lake Shared SRAM Controller   | 2     |            | [74D39D268F](<Tablet/RuggedPC/RuggedBookJ/RuggedBookJ87/CA3F17B45E07/MANJARO-21.2.6/5.15.32-1-MANJARO/X86_64/74D39D268F>) |
| 8086:9d21 | 1025:122b | Intel            | Sunrise Point-LP PMC                 | 2     |            | [46ECB88F1D](<Tablet/Acer/Switch/Switch SW713-51GNP/3C0AE30715BA/NIXOS-22.11/6.1.9/X86_64/46ECB88F1D>) |
| 8086:9d21 | 103c:824c | Intel            | Sunrise Point-LP PMC                 | 2     |            | [F2799F616C](<Tablet/Hewlett-Packard/ZBook/ZBook x2 G4/3743B487B588/ARCH-ROLLING/5.15.79-1-LTS/X86_64/F2799F616C>) |
| 8086:9d21 | 1043:13c0 | Intel            | Sunrise Point-LP PMC                 | 2     |            | [4363CA1BD6](<Tablet/ASUSTek Computer/T303/T303UA/C8223D9D63FE/UBUNTU-20.04/5.4.0-33-GENERIC/X86_64/4363CA1BD6>) |
| 8086:9d21 | 1043:16c0 | Intel            | Sunrise Point-LP PMC                 | 2     |            | [D33E67BDF4](<Tablet/ASUSTek Computer/T304/T304UA/8F97F461C23D/UBUNTU-20.04/5.4.0-29-GENERIC/X86_64/D33E67BDF4>) |
| 8086:9d21 | 1b0a:01d3 | Intel            | Sunrise Point-LP PMC                 | 2     |            | [60C93DDC01](<Tablet/Xplore/iX125/iX125R1/9DCB305AD004/PUPPY_IMPPUP64-9.6.1/5.15.11-LXPUP64/X86_64/60C93DDC01>) |
| 8086:02ef | 1071:d301 | Intel            | Comet Lake PCH-LP Shared SRAM        | 1     |            | [6F57AB0251](<Tablet/Getac/UX10/UX10G2/9B2D92B11BC9/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/6F57AB0251>) |
| 8086:4def | 1043:1d02 | Intel            | Jasper Lake Shared SRAM Controller   | 1     |            | [CF1735BF9E](<Tablet/ASUSTek Computer/Vivobook/Vivobook Slate T3300KA_T3300KA/CB77B9CC66FB/ELEMENTARY-6.1/5.15.0-50-GENERIC/X86_64/CF1735BF9E>) |
| 8086:4def | 8086:7270 | Intel            | Jasper Lake Shared SRAM Controller   | 1     |            | [C24B5A1F84](<Tablet/retsamarret/000/000-F4423-UK000-2000/5D4FAE7FB346/DEBIAN-11/5.10.0-21-AMD64/X86_64/C24B5A1F84>) |
| 8086:51ef | 1028:0b34 | Intel            | Alder Lake PCH Shared SRAM           | 1     |            | [6049494197](<Tablet/Dell/XPS/XPS 13 9315 2-in-1/1EF842C3A2C1/UBUNTU-22.04/6.1.0-1007-OEM/X86_64/6049494197>) |
| 8086:51ef | 1043:1573 | Intel            | Alder Lake PCH Shared SRAM           | 1     |            | [679DC6CBC8](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301VV_GZ301VV/7B1518D4CC86/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/679DC6CBC8>) |
| 8086:9d21 | 1028:0702 | Intel            | Sunrise Point-LP PMC                 | 1     |            | [CE9A3F2C74](<Tablet/Dell/XPS/XPS 12 9250/A04CD2743A76/CLEAR-LINUX-OS-35400/5.15.7-1106.NATIVE/X86_64/CE9A3F2C74>) |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1919 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 263   | ipu3_imgu  | [0332AF656C](<Tablet/Microsoft/Surface/Surface Pro/F1C987F0D508/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/0332AF656C>) |
| 8086:9d32 | 8086:7270 | Intel            | CSI-2 Host Controller                | 258   | ipu3_cio2  | [0332AF656C](<Tablet/Microsoft/Surface/Surface Pro/F1C987F0D508/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/0332AF656C>) |
| 8086:22b8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 159   | intel_a... | [40D1BBA9E2](<Tablet/Hampoo/I1/I1D6_C109S_Hi10Pro/8F753D037AF0/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/40D1BBA9E2>) |
| 8086:22b8 | 17aa:38e3 | Intel            | Atom/Celeron/Pentium Processor x5... | 62    | intel_a... | [5B5EBA537A](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/E141169A4B3D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/5B5EBA537A>) |
| 8086:9d32 |           | Intel            | CSI-2 Host Controller                | 55    | ipu3_cio2  | [EDCDEDD65A](<Tablet/Microsoft/Surface/Surface Go 2/5B20BDF3E76F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/EDCDEDD65A>) |
| 8086:22b8 | 17aa:3809 | Intel            | Atom/Celeron/Pentium Processor x5... | 53    | intel_a... | [3F12350D47](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/2E38E9723355/POP!_OS-21.04/5.15.5-76051505-GENERIC/X86_64/3F12350D47>) |
| 8086:8a19 | 8086:7270 | Intel            | Image Signal Processor               | 53    |            | [7C8D87170F](<Tablet/Microsoft/Surface/Surface Pro 7/FDDF58D50F30/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/7C8D87170F>) |
| 8086:1919 | 152d:1182 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 37    | ipu3_imgu  | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:22b8 | 1043:13a0 | Intel            | Atom/Celeron/Pentium Processor x5... | 32    | intel_a... | [60962892BC](<Tablet/ASUSTek Computer/T101/T101HA/5F2FAE88E834/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/60962892BC>) |
| 8086:5a88 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 28    |            | [E9E77E2E77](<Tablet/MECER/MW10/MW10Q16+S/D37A9D99B412/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/E9E77E2E77>) |
| 8086:22b8 | 103c:827c | Intel            | Atom/Celeron/Pentium Processor x5... | 23    | intel_a... | [815D54B61B](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/E1DE173C5065/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/815D54B61B>) |
| 8086:22b8 | 1414:0009 | Intel            | Atom/Celeron/Pentium Processor x5... | 22    | intel_a... | [540A259700](<Tablet/Microsoft/Surface/Surface 3/78C63CBEC2C3/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/540A259700>) |
| 1022:15e2 | 1022:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 21    | snd_pci... | [672B480B96](<Tablet/AYANEO/2/2/4246C8CCCDD5/CHIMERAOS-41/6.1.21-1-LTS/X86_64/672B480B96>) |
| 8086:1919 | 103c:82ca | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 21    | ipu3_imgu  | [F76DC1B9B7](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/9B3C72E9E186/ARCH-ROLLING/6.2.12-ARCH1-1/X86_64/F76DC1B9B7>) |
| 8086:9d32 | 103c:82ca | Intel            | CSI-2 Host Controller                | 21    | ipu3_cio2  | [F76DC1B9B7](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/9B3C72E9E186/ARCH-ROLLING/6.2.12-ARCH1-1/X86_64/F76DC1B9B7>) |
| 8086:22b8 | 1043:1400 | Intel            | Atom/Celeron/Pentium Processor x5... | 20    | atomisp    | [3EC331DA1F](<Tablet/ASUSTek Computer/T102/T102HA/2F5B8C8AE51D/FEDORA-36/5.18.10-200.FC36.X86_64/X86_64/3EC331DA1F>) |
| 8086:1919 | 152d:1237 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 12    | ipu3_imgu  | [EDCDEDD65A](<Tablet/Microsoft/Surface/Surface Go 2/5B20BDF3E76F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/EDCDEDD65A>) |
| 8086:1919 | 17aa:2244 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 12    | ipu3_imgu  | [ABA0D29DD8](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJ001NFR/32F606BCA186/UBUNTU-22.10/5.19.0-29-GENERIC/X86_64/ABA0D29DD8>) |
| 8086:1919 | 17aa:382f | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 12    | ipu3_imgu  | [6FF1D34454](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 20M3/154D3B05B100/UBUNTU-20.04/5.15.0-58-GENERIC/X86_64/6FF1D34454>) |
| 8086:1919 | 8086:1919 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 12    | ipu3_imgu  | [D43709B2F7](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/B40E17CB6AAF/UBUNTU-22.10/5.19.0-26-GENERIC/X86_64/D43709B2F7>) |
| 8086:9d32 | 17aa:2244 | Intel            | CSI-2 Host Controller                | 12    | ipu3_cio2  | [ABA0D29DD8](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJ001NFR/32F606BCA186/UBUNTU-22.10/5.19.0-29-GENERIC/X86_64/ABA0D29DD8>) |
| 8086:9d32 | 17aa:380c | Intel            | CSI-2 Host Controller                | 12    | ipu3_cio2  | [6FF1D34454](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 20M3/154D3B05B100/UBUNTU-20.04/5.15.0-58-GENERIC/X86_64/6FF1D34454>) |
| 8086:1919 | 144d:c14f | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 11    | ipu3_imgu  | [167229560A](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/KUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/167229560A>) |
| 8086:9d32 | 144d:c14f | Intel            | CSI-2 Host Controller                | 11    | ipu3_cio2  | [167229560A](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/KUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/167229560A>) |
| 8086:1919 | 1028:07a4 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 9     | ipu3_imgu  | [1717754347](<Tablet/Dell/Latitude/Latitude 5285/D75F67E269AD/UBUNTU-22.10/5.19.10-SURFACE/X86_64/1717754347>) |
| 8086:1919 | 103c:828b | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 9     | ipu3_imgu  | [6ECC8F0BAD](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/7A82B39E3BAF/FEDORA-37/6.1.15-200.FC37.X86_64/X86_64/6ECC8F0BAD>) |
| 8086:22b8 | 103c:82f4 | Intel            | Atom/Celeron/Pentium Processor x5... | 9     | intel_a... | [863136882E](<Tablet/Hewlett-Packard/x2/x2 210 G2/F90A1440D6C0/LINUXMINT-20.2/5.4.0-137-GENERIC/X86_64/863136882E>) |
| 8086:22b8 | 1043:1c60 | Intel            | Atom/Celeron/Pentium Processor x5... | 9     | intel_a... | [961E13C584](<Tablet/ASUSTek Computer/T103/T103HAF/DC30228D2ADB/LINUXMINT-20.3/5.4.0-148-GENERIC/X86_64/961E13C584>) |
| 8086:9d32 | 1028:07a4 | Intel            | CSI-2 Host Controller                | 9     | ipu3_cio2  | [1717754347](<Tablet/Dell/Latitude/Latitude 5285/D75F67E269AD/UBUNTU-22.10/5.19.10-SURFACE/X86_64/1717754347>) |
| 8086:9d32 | 103c:828b | Intel            | CSI-2 Host Controller                | 9     | ipu3_cio2  | [6ECC8F0BAD](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/7A82B39E3BAF/FEDORA-37/6.1.15-200.FC37.X86_64/X86_64/6ECC8F0BAD>) |
| 8086:1919 | 1028:081d | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 8     | ipu3_imgu  | [88900A37B9](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/172279AB141B/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/88900A37B9>) |
| 8086:9d32 | 1028:081d | Intel            | CSI-2 Host Controller                | 8     | ipu3_cio2  | [88900A37B9](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/172279AB141B/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/88900A37B9>) |
| 8086:1919 | 1028:06e6 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 7     | ipu3_imgu  | [C751321AB1](<Tablet/Dell/Latitude/Latitude 5175/725A65699078/FEDORA-36/5.18.18-200.FC36.X86_64/X86_64/C751321AB1>) |
| 8086:1919 | 144d:c135 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 7     | ipu3_imgu  | [25DEDA3E27](<Tablet/Samsung Electronics/Galaxy/Galaxy TabPro S/A1DD930DF301/UBUNTU-20.04/5.4.0-90-GENERIC/X86_64/25DEDA3E27>) |
| 8086:1919 | 17aa:382c | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 7     | ipu3_imgu  | [D88BD74ACF](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/B632F2BAF8BF/FEDORA-38/6.2.0-0.RC0.20221221GITB6BB9676F216.10.FC38.X86_64/X86_64/D88BD74ACF>) |
| 8086:9a19 | 1028:0a45 | Intel            | Core i9/i7/i5/Xeon Imaging Signal... | 7     | intel_i... | [5E287BBD8B](<Tablet/Dell/Latitude/Latitude 7320 Detachable/089CE6269F10/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/5E287BBD8B>) |
| 8086:9a19 | 17aa:382f | Intel            | Core i9/i7/i5/Xeon Imaging Signal... | 7     | intel_i... | [5C0467F4CB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/FA8378B128F2/ZORIN-16/5.15.0-69-GENERIC/X86_64/5C0467F4CB>) |
| 8086:9a19 | 1ec9:3e44 | Intel            | Core i9/i7/i5/Xeon Imaging Signal... | 7     | intel_i... | [F348E93361](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/4B50F0906809/UBUNTU-22.10/6.1.4-060104-GENERIC/X86_64/F348E93361>) |
| 8086:9d32 | 1028:06e6 | Intel            | CSI-2 Host Controller                | 7     | ipu3_cio2  | [C751321AB1](<Tablet/Dell/Latitude/Latitude 5175/725A65699078/FEDORA-36/5.18.18-200.FC36.X86_64/X86_64/C751321AB1>) |
| 8086:9d32 | 144d:c135 | Intel            | CSI-2 Host Controller                | 7     | ipu3_cio2  | [25DEDA3E27](<Tablet/Samsung Electronics/Galaxy/Galaxy TabPro S/A1DD930DF301/UBUNTU-20.04/5.4.0-90-GENERIC/X86_64/25DEDA3E27>) |
| 8086:9d32 | 17aa:3808 | Intel            | CSI-2 Host Controller                | 7     | ipu3_cio2  | [D88BD74ACF](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/B632F2BAF8BF/FEDORA-38/6.2.0-0.RC0.20221221GITB6BB9676F216.10.FC38.X86_64/X86_64/D88BD74ACF>) |
| 8086:9d32 | 8086:9d32 | Intel            | CSI-2 Host Controller                | 7     | ipu3_cio2  | [0F05F12004](<Tablet/Teclast/X5/X5 Pro/B130987D6E6A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0F05F12004>) |
| 8086:1919 | 1028:06d6 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 6     | ipu3_imgu  | [C118CA04BC](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/C118CA04BC>) |
| 8086:1919 | 17aa:2241 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 6     | ipu3_imgu  | [CC6FE2D666](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/8D924D4AA03C/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/CC6FE2D666>) |
| 8086:1919 | 17aa:2243 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 6     | ipu3_imgu  | [149C782883](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCA016JP/4766889E4D51/SIDUCTION-12/6.2.2-3-SIDUCTION-AMD64/X86_64/149C782883>) |
| 8086:22b8 | 17aa:222a | Intel            | Atom/Celeron/Pentium Processor x5... | 6     | intel_a... | [4BCAFF2F2B](<Tablet/Lenovo/ThinkPad/ThinkPad 10 2nd 20E30013GE/A04B191DFFD6/POP!_OS-22.04/6.0.12-76060006-GENERIC/X86_64/4BCAFF2F2B>) |
| 8086:9d32 | 1028:06d6 | Intel            | CSI-2 Host Controller                | 6     | ipu3_cio2  | [C118CA04BC](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/C118CA04BC>) |
| 8086:9d32 | 17aa:2241 | Intel            | CSI-2 Host Controller                | 6     | ipu3_cio2  | [CC6FE2D666](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/8D924D4AA03C/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/CC6FE2D666>) |
| 8086:9d32 | 17aa:2243 | Intel            | CSI-2 Host Controller                | 6     | ipu3_cio2  | [149C782883](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCA016JP/4766889E4D51/SIDUCTION-12/6.2.2-3-SIDUCTION-AMD64/X86_64/149C782883>) |
| 8086:1919 | 1025:111e | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 5     | ipu3_imgu  | [C9900A8E2F](<Tablet/Acer/Switch/Switch SA5-271P/DFFCE0790341/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C9900A8E2F>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:8136 | 1019:99fa | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 6     | r8169      | [585EA8C657](<Tablet/BANGHO/Suma/Suma 1025/C11649ABA4A3/ELEMENTARY-6.1/5.13.0-28-GENERIC/X86_64/585EA8C657>) |
| 10ec:8168 | 1019:99fa | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 4     | r8169      | [C35A8D75CE](<Tablet/Intel/powered/powered classmate PC/E3EDE14D59EF/LINUXMINT-20.2/5.4.0-135-GENERIC/X86_64/C35A8D75CE>) |
| 10ec:8136 | 1019:99da | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 2     | r8169      | [61790801C2](<Tablet/Intel/powered/powered classmate PC/92E9A98C551E/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/61790801C2>) |
| 10ec:8136 | 1854:0211 | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 2     | r8169      | [44AF16AC16](<Tablet/LG Electronics/15U340/15U340-L.BK55P1/96572D02BF5F/LINUXMINT-20/5.4.0-42-GENERIC/X86_64/44AF16AC16>) |
| 10ec:8168 | 1509:7018 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 2     | r8169      | [9347717861](<Tablet/Xplore/iX101/iX101B1/988A604FB8AB/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/9347717861>) |
| 8086:156f | 1b0a:01d3 | Intel            | Ethernet Connection I219-LM          | 2     | e1000e     | [60C93DDC01](<Tablet/Xplore/iX125/iX125R1/9DCB305AD004/PUPPY_IMPPUP64-9.6.1/5.15.11-LXPUP64/X86_64/60C93DDC01>) |
| 8086:15f3 | 8086:0000 | Intel            | Ethernet Controller I225-V           | 2     | igc        | [C24B5A1F84](<Tablet/retsamarret/000/000-F4423-UK000-2000/5D4FAE7FB346/DEBIAN-11/5.10.0-21-AMD64/X86_64/C24B5A1F84>) |
| 10ec:8136 | 10ec:0123 | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 1     | r8169      | [BA303FB8FF](<Tablet/BANGHO/Suma/Suma 1025/C706A46832B0/UBUNTU-18.04/5.0.0-32-GENERIC/X86_64/BA303FB8FF>) |
| 10ec:8136 | 1558:5470 | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 1     | r8169      | [DD65C5ABF7](<Tablet/Lanix/Neuron/Neuron A/9C81E684C8A4/ARCH-ROLLING/5.8.14-ARCH1-1/X86_64/DD65C5ABF7>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | r8169      | [A018825B67](<Tablet/CAKE/POS/POS V3/6B0F662D72A6/UBUNTU-18.04/5.4.0-128-GENERIC/X86_64/A018825B67>) |
| 8086:15d7 | 10f7:8338 | Intel            | Ethernet Connection (4) I219-LM      | 1     | e1000e     | [94539C6DB9](<Tablet/Panasonic/CF-33/CF-33-1/AE1D638EDC9E/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/94539C6DB9>) |
| 8086:15fb | 1071:a121 | Intel            | Ethernet Connection (13) I219-LM     | 1     |            | [5D9E3F3501](<Tablet/Getac/K120/K120G2/9B90212BD0E9/UBUNTU-18.04/5.4.0-84-GENERIC/X86_64/5D9E3F3501>) |
| 8086:15fb | 1071:e207 | Intel            | Ethernet Connection (13) I219-LM     | 1     | e1000e     | [2A05772CB6](<Tablet/Getac/F110/F110G6/36F31BBCD939/RELD-7.9/5.15.33-1.RES7.X86_64/X86_64/2A05772CB6>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:3165 | 8086:8010 | Intel            | Wireless 3165                        | 108   | iwlwifi    | [83ABB6A8E0](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/9E722A5CCA1E/ZORIN-16/5.15.0-71-GENERIC/X86_64/83ABB6A8E0>) |
| 8086:34f0 | 8086:0074 | Intel            | Ice Lake-LP PCH CNVi WiFi            | 92    | iwlwifi    | [FD7A2486F2](<Tablet/Microsoft/Surface/Surface Laptop Go/83C5E1166CAF/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/FD7A2486F2>) |
| 11ab:2b38 | 0003:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 83    | mwifiex... | [7FD9FD4619](<Tablet/Microsoft/Surface/Surface Pro 4/11BB44FDB753/POP!_OS-22.04/6.2.14-SURFACE/X86_64/7FD9FD4619>) |
| 11ab:2b38 | 0001:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 77    | mwifiex... | [27A1A2533B](<Tablet/Microsoft/Surface/Surface Pro 3/CD0693C63FAF/DEBIAN-12/6.1.0-7-AMD64/X86_64/27A1A2533B>) |
| 11ab:2b38 | 0008:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 75    | mwifiex... | [0332AF656C](<Tablet/Microsoft/Surface/Surface Pro/F1C987F0D508/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/0332AF656C>) |
| 168c:0042 | 1a3b:2a51 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 62    | ath10k_pci | [961E13C584](<Tablet/ASUSTek Computer/T103/T103HAF/DC30228D2ADB/LINUXMINT-20.3/5.4.0-148-GENERIC/X86_64/961E13C584>) |
| 11ab:2b38 | 0004:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 39    | mwifiex... | [13C23678AA](<Tablet/Microsoft/Surface/Surface Book/44D9147EE1C2/ZORIN-16/5.15.0-69-GENERIC/X86_64/13C23678AA>) |
| 8086:095a | 8086:9010 | Intel            | Wireless 7265                        | 39    | iwlwifi    | [46ECB88F1D](<Tablet/Acer/Switch/Switch SW713-51GNP/3C0AE30715BA/NIXOS-22.11/6.1.9/X86_64/46ECB88F1D>) |
| 168c:003e | 168c:3370 | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 35    | ath10k_pci | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:a0f0 | 8086:0074 | Intel            | Wi-Fi 6 AX201                        | 27    | iwlwifi    | [3C50D5D61C](<Tablet/Microsoft/Surface/Surface Pro 8/C4CEE7E26DF5/MANJARO/6.2.12-ARCH1-1-SURFACE/X86_64/3C50D5D61C>) |
| 8086:2723 | 8086:008c | Intel            | Wi-Fi 6 AX200                        | 26    | iwlwifi    | [EDCDEDD65A](<Tablet/Microsoft/Surface/Surface Go 2/5B20BDF3E76F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/EDCDEDD65A>) |
| 11ab:2b38 | 0006:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 24    | mwifiex... | [58900F0CAA](<Tablet/Microsoft/Surface/Surface Laptop 2/1236055B02AE/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/58900F0CAA>) |
| 11ab:2b38 | 0002:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 21    | mwifiex... | [540A259700](<Tablet/Microsoft/Surface/Surface 3/78C63CBEC2C3/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/540A259700>) |
| 8086:31dc | 8086:0264 | Intel            | Gemini Lake PCH CNVi WiFi            | 21    | iwlwifi    | [AD63D006B6](<Tablet/Chuwi/Hi10/Hi10 XR/75B0305701C2/KDE-NEON-22.04/5.19.0-38-GENERIC/X86_64/AD63D006B6>) |
| 10ec:c821 | 10ec:c821 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 19    | rtw88_8... | [2E70372D4B](<Tablet/Chuwi/UBook/UBook X/6D0D62C17BDF/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/2E70372D4B>) |
| 8086:24fd | 8086:1010 | Intel            | Wireless 8265 / 8275                 | 18    | iwlwifi    | [F76DC1B9B7](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/9B3C72E9E186/ARCH-ROLLING/6.2.12-ARCH1-1/X86_64/F76DC1B9B7>) |
| 8086:24fd | 8086:9010 | Intel            | Wireless 8265 / 8275                 | 18    | iwlwifi    | [5B5EBA537A](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/E141169A4B3D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/5B5EBA537A>) |
| 11ab:2b38 | 0009:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 17    | mwifiex... | [5A5E168C99](<Tablet/Microsoft/Surface/Surface Book 2/E6819C0E6E6D/KALI-2023.1/6.2.10-SURFACE/X86_64/5A5E168C99>) |
| 8086:24fd | 8086:0150 | Intel            | Wireless 8265 / 8275                 | 16    | iwlwifi    | [88900A37B9](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/172279AB141B/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/88900A37B9>) |
| 8086:3165 | 8086:8110 | Intel            | Wireless 3165                        | 16    | iwlwifi    | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 168c:002b | 105b:e031 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 15    | ath9k      | [C3D132FB91](<Tablet/Acer/Iconia/Iconia Tab W501/B59AD5DD817B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C3D132FB91>) |
| 11ab:2b38 | 0007:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 13    | mwifiex... | [4D293DA8B1](<Tablet/Microsoft/Surface/Surface Book 2/75D314F90E98/LINUXMINT-21.1/5.15.0-67-GENERIC/X86_64/4D293DA8B1>) |
| 10ec:b723 | 10ec:b737 | Realtek Semic... | RTL8723BE PCIe Wireless Network A... | 12    | rtl8723be  | [C35A8D75CE](<Tablet/Intel/powered/powered classmate PC/E3EDE14D59EF/LINUXMINT-20.2/5.4.0-135-GENERIC/X86_64/C35A8D75CE>) |
| 8086:24f3 | 8086:0150 | Intel            | Wireless 8260                        | 12    | iwlwifi    | [C118CA04BC](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/C118CA04BC>) |
| 8086:51f0 | 8086:0094 | Intel            | Alder Lake-P PCH CNVi WiFi           | 12    | iwlwifi    | [ED4AEB2282](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 5 12IAU7 82TQ/75AEF6B37790/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/ED4AEB2282>) |
| 168c:003e | 144d:c14f | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 11    | ath10k_pci | [167229560A](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/KUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/167229560A>) |
| 8086:24f3 | 8086:8110 | Intel            | Wireless 8260                        | 11    | iwlwifi    | [CC6FE2D666](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/8D924D4AA03C/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/CC6FE2D666>) |
| 14c3:0608 | 14c3:0608 | MediaTek         | MT7921K (RZ608) Wi-Fi 6E 80MHz       | 10    | mt7921e    | [FE54ACC90F](<Tablet/AOKZOE/A1/A1 AR07/AD925682010C/STEAMOS-3.4/6.1.1-VALVE1-1-NEPTUNE-61/X86_64/FE54ACC90F>) |
| 8086:24fd | 8086:0010 | Intel            | Wireless 8265 / 8275                 | 9     | iwlwifi    | [DBBCF4A29A](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/5C54BEB47475/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/DBBCF4A29A>) |
| 8086:24fd | 8086:8110 | Intel            | Wireless 8265 / 8275                 | 9     | iwlwifi    | [9FCC670422](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCS1D501/58AF402AD059/UBUNTU-22.04/5.15.0-47-GENERIC/X86_64/9FCC670422>) |
| 8086:24fd | 8086:9110 | Intel            | Wireless 8265 / 8275                 | 9     | iwlwifi    | [149C782883](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCA016JP/4766889E4D51/SIDUCTION-12/6.2.2-3-SIDUCTION-AMD64/X86_64/149C782883>) |
| 8086:24fd | 8086:8010 | Intel            | Wireless 8265 / 8275                 | 8     | iwlwifi    | [6ECC8F0BAD](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/7A82B39E3BAF/FEDORA-37/6.1.15-200.FC37.X86_64/X86_64/6ECC8F0BAD>) |
| 168c:003e | 144d:c135 | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 7     | ath10k_pci | [25DEDA3E27](<Tablet/Samsung Electronics/Galaxy/Galaxy TabPro S/A1DD930DF301/UBUNTU-20.04/5.4.0-90-GENERIC/X86_64/25DEDA3E27>) |
| 168c:003e | 17aa:0827 | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 7     | ath10k_pci | [6FF1D34454](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 20M3/154D3B05B100/UBUNTU-20.04/5.15.0-58-GENERIC/X86_64/6FF1D34454>) |
| 8086:a0f0 | 8086:4070 | Intel            | Wi-Fi 6 AX201                        | 7     | iwlwifi    | [5E287BBD8B](<Tablet/Dell/Latitude/Latitude 7320 Detachable/089CE6269F10/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/5E287BBD8B>) |
| 14e4:43ec | 105b:e095 | Broadcom         | BCM4356 802.11ac Wireless Network... | 6     | brcmfmac   | [4BCAFF2F2B](<Tablet/Lenovo/ThinkPad/ThinkPad 10 2nd 20E30013GE/A04B191DFFD6/POP!_OS-22.04/6.0.12-76060006-GENERIC/X86_64/4BCAFF2F2B>) |
| 168c:003e | 045e:0001 | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 6     | ath10k_pci | [88EA27E220](<Tablet/Microsoft/Surface/Surface Laptop 3/49F309623B33/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/88EA27E220>) |
| 168c:0042 | 1a3b:2b51 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 6     | ath10k_pci | [6CBFC99F43](<Tablet/Chuwi/UBook/UBook/A58C8FBC70DA/OPENMANDRIVA-23.03/6.2.1-DESKTOP-1OMV2390/X86_64/6CBFC99F43>) |
| 8086:08b3 | 8086:8070 | Intel            | Wireless 3160                        | 6     | iwlwifi    | [C61A96D514](<Tablet/Medion/P/P2212T/71C4E4B2F18A/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/C61A96D514>) |
| 8086:31dc | 8086:0234 | Intel            | Gemini Lake PCH CNVi WiFi            | 6     | iwlwifi    | [C81361E795](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 10IGL5 82AT/605931C0A403/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/C81361E795>) |
| 8086:a0f0 | 8086:0070 | Intel            | Wi-Fi 6 AX201                        | 6     | iwlwifi    | [89ADCCAE04](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UVS1RL00/ECF244BC1E85/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/89ADCCAE04>) |
| 168c:0034 | 17aa:3214 | Qualcomm Atheros | AR9462 Wireless Network Adapter      | 5     | ath9k      | [69E83BCD80](<Tablet/Lenovo/MIIX/MIIX 2 11 20327/7DF5CB4D666D/ZORIN-16/5.15.0-56-GENERIC/X86_64/69E83BCD80>) |
| 8086:02f0 | 8086:0074 | Intel            | Comet Lake PCH-LP CNVi WiFi          | 5     | iwlwifi    | [2C581034EB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13IML05 82AS/6049DBFEB1C3/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/2C581034EB>) |
| 8086:3166 | 8086:4210 | Intel            | Dual Band Wireless-AC 3165 Plus B... | 5     | iwlwifi    | [D88BD74ACF](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/B632F2BAF8BF/FEDORA-38/6.2.0-0.RC0.20221221GITB6BB9676F216.10.FC38.X86_64/X86_64/D88BD74ACF>) |
| 8086:4df0 | 8086:0074 | Intel            | Wi-Fi 6 AX201 160MHz                 | 5     | iwlwifi    | [169454762C](<Tablet/Hewlett-Packard/Tablet/Tablet 11m-be0xxx/535A9A46FE41/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/169454762C>) |
| 14e4:43ec | 19e5:3100 | Broadcom         | BCM4356 802.11ac Wireless Network... | 4     | brcmfmac   | [1DE7D37B18](<Tablet/HUAWEI/MateBook/MateBook HZ-W09/8B29CCECA159/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/1DE7D37B18>) |
| 8086:24f3 | 8086:1010 | Intel            | Wireless 8260                        | 4     | iwlwifi    | [D43709B2F7](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/B40E17CB6AAF/UBUNTU-22.10/5.19.0-26-GENERIC/X86_64/D43709B2F7>) |
| 8086:24fd | 8086:0050 | Intel            | Wireless 8265 / 8275                 | 4     | iwlwifi    | [0EC990AB1E](<Tablet/Dell/Latitude/Latitude 7285/D6569A451159/ZORIN-16/5.13.0-40-GENERIC/X86_64/0EC990AB1E>) |
| 8086:2723 | 8086:0080 | Intel            | Wi-Fi 6 AX200                        | 4     | iwlwifi    | [084F1CF7CB](<Tablet/Microsoft/Surface/Surface Laptop Studio/150859BACF06/FEDORA-37/6.0.12-1.SURFACE.FC37.X86_64/X86_64/084F1CF7CB>) |
| 10ec:b822 | 17aa:b023 | Realtek Semic... | RTL8822BE 802.11a/b/g/n/ac WiFi a... | 3     | rtw88_8... | [05EDD845DF](<Tablet/Lenovo/Tablet/Tablet 10 20L3000KGE/7130A0BB6850/UBUNTU-22.10/5.19.0-40-GENERIC/X86_64/05EDD845DF>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1533 | ffff:0000 | Intel            | I210 Gigabit Network Connection      | 2     | igb        | [49D345EC0B](<Tablet/Xplore/iX101/iX101L1/1592B2F5F479/UBUNTU-20.04/5.6.0-1028-OEM/X86_64/49D345EC0B>) |
| 8086:1502 | 10f7:8338 | Intel            | 82579LM Gigabit Network Connectio... | 1     | e1000e     | [50E0A85FD3](<Tablet/Panasonic/CF-H2/CF-H2BJJHZDE/E17482358B17/LMDE-5/5.10.0-13-AMD64/X86_64/50E0A85FD3>) |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d35 | 8086:7270 | Intel            | Sunrise Point-LP Integrated Senso... | 122   | intel_i... | [0332AF656C](<Tablet/Microsoft/Surface/Surface Pro/F1C987F0D508/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/0332AF656C>) |
| 8086:9d35 | 152d:1182 | Intel            | Sunrise Point-LP Integrated Senso... | 37    | intel_i... | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:22d8 | 1043:13a0 | Intel            | Integrated Sensor Solution           | 32    | intel_i... | [60962892BC](<Tablet/ASUSTek Computer/T101/T101HA/5F2FAE88E834/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/60962892BC>) |
| 8086:22d8 | 103c:827c | Intel            | Integrated Sensor Solution           | 24    | intel_i... | [815D54B61B](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/E1DE173C5065/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/815D54B61B>) |
| 8086:22d8 | 1043:1400 | Intel            | Integrated Sensor Solution           | 21    | intel_i... | [3EC331DA1F](<Tablet/ASUSTek Computer/T102/T102HA/2F5B8C8AE51D/FEDORA-36/5.18.10-200.FC36.X86_64/X86_64/3EC331DA1F>) |
| 8086:9d35 | 103c:82ca | Intel            | Sunrise Point-LP Integrated Senso... | 21    | intel_i... | [F76DC1B9B7](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/9B3C72E9E186/ARCH-ROLLING/6.2.12-ARCH1-1/X86_64/F76DC1B9B7>) |
| 8086:9d35 | 152d:1237 | Intel            | Sunrise Point-LP Integrated Senso... | 12    | intel_i... | [EDCDEDD65A](<Tablet/Microsoft/Surface/Surface Go 2/5B20BDF3E76F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/EDCDEDD65A>) |
| 8086:9d35 | 17aa:2244 | Intel            | Sunrise Point-LP Integrated Senso... | 12    | intel_i... | [ABA0D29DD8](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJ001NFR/32F606BCA186/UBUNTU-22.10/5.19.0-29-GENERIC/X86_64/ABA0D29DD8>) |
| 8086:9d35 | 17aa:3807 | Intel            | Sunrise Point-LP Integrated Senso... | 12    | intel_i... | [6FF1D34454](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 20M3/154D3B05B100/UBUNTU-20.04/5.15.0-58-GENERIC/X86_64/6FF1D34454>) |
| 8086:22d8 | 103c:82f4 | Intel            | Integrated Sensor Solution           | 9     | intel_i... | [863136882E](<Tablet/Hewlett-Packard/x2/x2 210 G2/F90A1440D6C0/LINUXMINT-20.2/5.4.0-137-GENERIC/X86_64/863136882E>) |
| 8086:22d8 | 1043:1c60 | Intel            | Integrated Sensor Solution           | 9     | intel_i... | [961E13C584](<Tablet/ASUSTek Computer/T103/T103HAF/DC30228D2ADB/LINUXMINT-20.3/5.4.0-148-GENERIC/X86_64/961E13C584>) |
| 8086:22d8 | 8086:7270 | Intel            | Integrated Sensor Solution           | 9     | intel_i... | [3316360D7A](<Tablet/Lenovo/YB1/YB1-X91F/68EFD6F91FDD/FEDORA-35/6.3.0-RC6+/X86_64/3316360D7A>) |
| 8086:9d35 | 1028:07a4 | Intel            | Sunrise Point-LP Integrated Senso... | 9     | intel_i... | [1717754347](<Tablet/Dell/Latitude/Latitude 5285/D75F67E269AD/UBUNTU-22.10/5.19.10-SURFACE/X86_64/1717754347>) |
| 8086:9d35 | 103c:828b | Intel            | Sunrise Point-LP Integrated Senso... | 9     | intel_i... | [6ECC8F0BAD](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/7A82B39E3BAF/FEDORA-37/6.1.15-200.FC37.X86_64/X86_64/6ECC8F0BAD>) |
| 8086:9d35 | 1028:081d | Intel            | Sunrise Point-LP Integrated Senso... | 8     | intel_i... | [88900A37B9](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/172279AB141B/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/88900A37B9>) |
| 8086:9d35 | 1028:06e6 | Intel            | Sunrise Point-LP Integrated Senso... | 7     | intel_i... | [C751321AB1](<Tablet/Dell/Latitude/Latitude 5175/725A65699078/FEDORA-36/5.18.18-200.FC36.X86_64/X86_64/C751321AB1>) |
| 1022:15e6 | 1022:15e4 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 6     | i2c_amd... | [88EA27E220](<Tablet/Microsoft/Surface/Surface Laptop 3/49F309623B33/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/88EA27E220>) |
| 8086:9d35 | 1028:06d6 | Intel            | Sunrise Point-LP Integrated Senso... | 6     | intel_i... | [C118CA04BC](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/C118CA04BC>) |
| 8086:9d35 | 17aa:2241 | Intel            | Sunrise Point-LP Integrated Senso... | 6     | intel_i... | [CC6FE2D666](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/8D924D4AA03C/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/CC6FE2D666>) |
| 8086:9d35 | 17aa:2243 | Intel            | Sunrise Point-LP Integrated Senso... | 6     | intel_i... | [149C782883](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCA016JP/4766889E4D51/SIDUCTION-12/6.2.2-3-SIDUCTION-AMD64/X86_64/149C782883>) |
| 8086:9d35 | 1025:111e | Intel            | Sunrise Point-LP Integrated Senso... | 5     | intel_i... | [C9900A8E2F](<Tablet/Acer/Switch/Switch SA5-271P/DFFCE0790341/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C9900A8E2F>) |
| 8086:9d35 | 103c:8414 | Intel            | Sunrise Point-LP Integrated Senso... | 5     | intel_i... | [E8D1866113](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/AC04F34CD8CA/DEBIAN/6.0.0-5-AMD64/X86_64/E8D1866113>) |
| 8086:9d35 | 8086:9d35 | Intel            | Sunrise Point-LP Integrated Senso... | 5     | intel_i... | [B945137346](<Tablet/ASUSTek Computer/T305/T305CA/E8B080C97665/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/B945137346>) |
| 8086:9d35 | 1028:07a5 | Intel            | Sunrise Point-LP Integrated Senso... | 4     | intel_i... | [0EC990AB1E](<Tablet/Dell/Latitude/Latitude 7285/D6569A451159/ZORIN-16/5.13.0-40-GENERIC/X86_64/0EC990AB1E>) |
| 8086:9d35 | 19e5:3e00 | Intel            | Sunrise Point-LP Integrated Senso... | 4     | intel_i... | [1DE7D37B18](<Tablet/HUAWEI/MateBook/MateBook HZ-W09/8B29CCECA159/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/1DE7D37B18>) |
| 8086:9d35 | 1025:1171 | Intel            | Sunrise Point-LP Integrated Senso... | 3     | intel_i... | [7D44E4C760](<Tablet/Acer/Switch/Switch SW512-52/9061A4CB688E/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/7D44E4C760>) |
| 8086:9d35 | 103c:82cb | Intel            | Sunrise Point-LP Integrated Senso... | 3     | intel_i... | [9DE6B65A45](<Tablet/Hewlett-Packard/Spectre/Spectre x2 Detachable 12-c0XX/107C5ABF10E7/ARCH-ROLLING/6.2.2-ARCH1-1/X86_64/9DE6B65A45>) |
| 8086:9d35 | 1025:122b | Intel            | Sunrise Point-LP Integrated Senso... | 2     | intel_i... | [46ECB88F1D](<Tablet/Acer/Switch/Switch SW713-51GNP/3C0AE30715BA/NIXOS-22.11/6.1.9/X86_64/46ECB88F1D>) |
| 8086:9d35 | 103c:824c | Intel            | Sunrise Point-LP Integrated Senso... | 2     | intel_i... | [F2799F616C](<Tablet/Hewlett-Packard/ZBook/ZBook x2 G4/3743B487B588/ARCH-ROLLING/5.15.79-1-LTS/X86_64/F2799F616C>) |
| 8086:9d35 | 1043:13c0 | Intel            | Sunrise Point-LP Integrated Senso... | 2     | intel_i... | [4363CA1BD6](<Tablet/ASUSTek Computer/T303/T303UA/C8223D9D63FE/UBUNTU-20.04/5.4.0-33-GENERIC/X86_64/4363CA1BD6>) |
| 8086:22d8 | 10cf:191b | Intel            | Integrated Sensor Solution           | 1     | intel_i... | [50862798B5](<Tablet/Fujitsu/STYLISTIC/STYLISTIC Q508/AB22D0A4D65B/ZORIN-16/5.15.0-69-GENERIC/X86_64/50862798B5>) |
| 8086:9d24 |           | Intel            | Skylake-U/Y SPI Controller           | 1     |            | [72CCAD3AA6](<Tablet/Google/Soraka/Soraka/9F4CCB101BA6/KUBUNTU-20.04/5.4.0-90-GENERIC/X86_64/72CCAD3AA6>) |
| 8086:9d35 | 1028:0702 | Intel            | Sunrise Point-LP Integrated Senso... | 1     | intel_i... | [CE9A3F2C74](<Tablet/Dell/XPS/XPS 12 9250/A04CD2743A76/CLEAR-LINUX-OS-35400/5.15.7-1106.NATIVE/X86_64/CE9A3F2C74>) |
| 8086:9d35 | 10f7:8338 | Intel            | Sunrise Point-LP Integrated Senso... | 1     | intel_i... | [94539C6DB9](<Tablet/Panasonic/CF-33/CF-33-1/AE1D638EDC9E/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/94539C6DB9>) |
| 8086:9d35 | 17aa:3805 | Intel            | Sunrise Point-LP Integrated Senso... | 1     | intel_i... | [50D3528425](<Tablet/Lenovo/MIIX710-12IKB/MIIX710-12IKB 80W1/2FB91DC53770/LINUXMINT-20.3/5.15.0-33-GENERIC/X86_64/50D3528425>) |
| 8086:9d35 | 19e5:3e01 | Intel            | Sunrise Point-LP Integrated Senso... | 1     | intel_i... | [072689DF7B](<Tablet/HUAWEI/MateBook/MateBook E/AE4CFFA107F9/KALI-2022.4/6.0.0-KALI6-AMD64/X86_64/072689DF7B>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:31d0 | 8086:7270 | Intel            | Celeron/Pentium Silver SD Host Co... | 48    | sdhci_pci  | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:31cc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 45    | sdhci_pci  | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:5aca | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 37    | sdhci_pci  | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 37    | sdhci_pci  | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |
| 8086:5ad0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 29    | sdhci_pci  | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |
| 8086:31cc | 17aa:381f | Intel            | Celeron/Pentium Silver Processor ... | 13    | sdhci_pci  | [42DA57CF53](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGL 82H0/66D15DFB427C/UBUNTU-20.04/5.15.0-52-GENERIC/X86_64/42DA57CF53>) |
| 8086:9d2d | 144d:c14f | Intel            | Sunrise Point-LP Secure Digital I... | 11    | sdhci_pci  | [167229560A](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/KUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/167229560A>) |
| 17a0:9755 | 1043:202f | Genesys Logic    | GL9755 SD Host Controller            | 9     | sdhci_pci  | [679DC6CBC8](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301VV_GZ301VV/7B1518D4CC86/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/679DC6CBC8>) |
| 8086:9d2b | 152d:1182 | Intel            | Skylake-U/Y SCC: eMMC                | 9     | sdhci_pci  | [02B5CA6C7E](<Tablet/Microsoft/Surface/Surface Go/96D7BDBFD826/KALI-2023.1/6.1.0-KALI5-AMD64/X86_64/02B5CA6C7E>) |
| 8086:9d2b | 8086:9d2b | Intel            | Skylake-U/Y SCC: eMMC                | 8     | sdhci_pci  | [0F05F12004](<Tablet/Teclast/X5/X5 Pro/B130987D6E6A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0F05F12004>) |
| 8086:9d2d | 8086:9d2d | Intel            | Sunrise Point-LP Secure Digital I... | 8     | sdhci_pci  | [0F05F12004](<Tablet/Teclast/X5/X5 Pro/B130987D6E6A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0F05F12004>) |
| 8086:31cc | 17aa:3826 | Intel            | Celeron/Pentium Silver Processor ... | 6     | sdhci_pci  | [C81361E795](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 10IGL5 82AT/605931C0A403/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/C81361E795>) |
| 8086:5aca | 8086:5aca | Intel            | Celeron N3350/Pentium N4200/Atom ... | 6     | sdhci_pci  | [F8733FFC4D](<Tablet/ZoomSmart/A/A1002/766C759236A3/ROSA-12.3/5.15.79-GENERIC-1ROSA2021.1-X86_64/X86_64/F8733FFC4D>) |
| 8086:5acc | 8086:5acc | Intel            | Celeron N3350/Pentium N4200/Atom ... | 6     | sdhci_pci  | [F8733FFC4D](<Tablet/ZoomSmart/A/A1002/766C759236A3/ROSA-12.3/5.15.79-GENERIC-1ROSA2021.1-X86_64/X86_64/F8733FFC4D>) |
| 8086:5ad0 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 6     | sdhci_pci  | [F8733FFC4D](<Tablet/ZoomSmart/A/A1002/766C759236A3/ROSA-12.3/5.15.79-GENERIC-1ROSA2021.1-X86_64/X86_64/F8733FFC4D>) |
| 8086:9d2b | 8086:7270 | Intel            | Skylake-U/Y SCC: eMMC                | 6     | sdhci_pci  | [D6D1AB6C61](<Tablet/Microsoft/Surface/Surface Go 3/DF0E3BC6859C/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D6D1AB6C61>) |
| 8086:31cc | 8086:31cc | Intel            | Celeron/Pentium Silver Processor ... | 5     | sdhci_pci  | [810D937888](<Tablet/Tactus/GeoPad/GeoPad 110/0F02FAE679C1/ZORIN-16/5.15.0-56-GENERIC/X86_64/810D937888>) |
| 8086:31d0 | 8086:31d0 | Intel            | Celeron/Pentium Silver SD Host Co... | 5     | sdhci_pci  | [810D937888](<Tablet/Tactus/GeoPad/GeoPad 110/0F02FAE679C1/ZORIN-16/5.15.0-56-GENERIC/X86_64/810D937888>) |
| 8086:9d2b | 152d:1237 | Intel            | Skylake-U/Y SCC: eMMC                | 5     | sdhci_pci  | [EDCDEDD65A](<Tablet/Microsoft/Surface/Surface Go 2/5B20BDF3E76F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/EDCDEDD65A>) |
| 1217:8621 | 17aa:3822 | O2 Micro         | SD/MMC Card Reader Controller        | 4     | sdhci_pci  | [63EAB4A6B5](<Tablet/Lenovo/Yoga/Yoga Duet IML 2020 82E9/8FFE2F20194E/ARCH/5.18.0-ARCH1-1/X86_64/63EAB4A6B5>) |
| 1217:8621 | 17aa:3841 | O2 Micro         | SD/MMC Card Reader Controller        | 4     | sdhci_pci  | [5C0467F4CB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/FA8378B128F2/ZORIN-16/5.15.0-69-GENERIC/X86_64/5C0467F4CB>) |
| 10ec:5209 | 10ec:5209 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 3     | rtsx_pci   | [44AF16AC16](<Tablet/LG Electronics/15U340/15U340-L.BK55P1/96572D02BF5F/LINUXMINT-20/5.4.0-42-GENERIC/X86_64/44AF16AC16>) |
| 1217:8621 | 17aa:2261 | O2 Micro         | SD/MMC Card Reader Controller        | 3     | sdhci_pci  | [05EDD845DF](<Tablet/Lenovo/Tablet/Tablet 10 20L3000KGE/7130A0BB6850/UBUNTU-22.10/5.19.0-40-GENERIC/X86_64/05EDD845DF>) |
| 1217:8621 | 17aa:3801 | O2 Micro         | SD/MMC Card Reader Controller        | 3     | sdhci_pci  | [67E1BDD5F1](<Tablet/Lenovo/MIIX/MIIX 720-12IKB 80VV/F45F8CE4052D/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/67E1BDD5F1>) |
| 8086:2295 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | sdhci_pci  | [40D1BBA9E2](<Tablet/Hampoo/I1/I1D6_C109S_Hi10Pro/8F753D037AF0/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/40D1BBA9E2>) |
| 8086:31cc | 17aa:2261 | Intel            | Celeron/Pentium Silver Processor ... | 3     | sdhci_pci  | [05EDD845DF](<Tablet/Lenovo/Tablet/Tablet 10 20L3000KGE/7130A0BB6850/UBUNTU-22.10/5.19.0-40-GENERIC/X86_64/05EDD845DF>) |
| 8086:31d0 | 17aa:2261 | Intel            | Celeron/Pentium Silver SD Host Co... | 3     | sdhci_pci  | [05EDD845DF](<Tablet/Lenovo/Tablet/Tablet 10 20L3000KGE/7130A0BB6850/UBUNTU-22.10/5.19.0-40-GENERIC/X86_64/05EDD845DF>) |
| 1217:8621 | 17aa:3825 | O2 Micro         | SD/MMC Card Reader Controller        | 2     | sdhci_pci  | [4471C4A012](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 10IGL5 82AT/CB9A9143DB96/ROSA-12.3/5.17.11-GENERIC-2ROSA2021.1-X86_64/X86_64/4471C4A012>) |
| 8086:0f16 | 1509:7018 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | sdhci_pci  | [9347717861](<Tablet/Xplore/iX101/iX101B1/988A604FB8AB/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/9347717861>) |
| 8086:4dc4 |           | Intel            | Jasper Lake SCS1: eMMC Controller    | 2     | sdhci_pci  | [74D39D268F](<Tablet/RuggedPC/RuggedBookJ/RuggedBookJ87/CA3F17B45E07/MANJARO-21.2.6/5.15.32-1-MANJARO/X86_64/74D39D268F>) |
| 8086:4df8 |           | Intel            | SD Host Controller                   | 2     | sdhci_pci  | [74D39D268F](<Tablet/RuggedPC/RuggedBookJ/RuggedBookJ87/CA3F17B45E07/MANJARO-21.2.6/5.15.32-1-MANJARO/X86_64/74D39D268F>) |
| 1022:7813 | 103c:22ea | AMD              | FCH SD Flash Controller              | 1     | sdhci_pci  | [4618D27B09](<Tablet/Zinox Technologies/x64-Based/x64-Based PC/B8682FC1F33D/ZORIN-16/5.15.0-46-GENERIC/X86_64/4618D27B09>) |
| 1217:8621 | 10f7:8338 | O2 Micro         | SD/MMC Card Reader Controller        | 1     | sdhci_pci  | [94539C6DB9](<Tablet/Panasonic/CF-33/CF-33-1/AE1D638EDC9E/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/94539C6DB9>) |
| 1217:8621 | 17aa:3802 | O2 Micro         | SD/MMC Card Reader Controller        | 1     | sdhci_pci  | [50D3528425](<Tablet/Lenovo/MIIX710-12IKB/MIIX710-12IKB 80W1/2FB91DC53770/LINUXMINT-20.3/5.15.0-33-GENERIC/X86_64/50D3528425>) |
| 17a0:9755 | ffff:ffff | Genesys Logic    | GL9755 SD Host Controller            | 1     | sdhci_pci  | [7A8FEE05AA](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZE_GZ301ZE/79E763C46EBB/MANJARO-21.3.7/5.15.60-1-MANJARO/X86_64/7A8FEE05AA>) |
| 8086:1190 |           | Intel            | Merrifield SD/SDIO/eMMC Controller   | 1     | sdhci_pci  | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:1aca | 8086:7270 | Intel            | SD Host Controller                   | 1     | sdhci_pci  | [555A26F0D1](<Tablet/Intel/570x/570x DVT3/469D9CAF87D4/UBUNTU-CORE-20/5.4.0-62-GENERIC/X86_64/555A26F0D1>) |
| 8086:1acc | 8086:7270 | Intel            | SD Host Controller                   | 1     | sdhci_pci  | [555A26F0D1](<Tablet/Intel/570x/570x DVT3/469D9CAF87D4/UBUNTU-CORE-20/5.4.0-62-GENERIC/X86_64/555A26F0D1>) |
| 8086:2294 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | sdhci_pci  | [0BBA28B672](<Tablet/Kiano/IntelectX3/IntelectX3HD/07656EC371DC/UBUNTU-21.04/5.11.0-37-GENERIC/X86_64/0BBA28B672>) |
| 8086:2296 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | sdhci_pci  | [14D1D84766](<Tablet/Kiano/IntelectX3/IntelectX3HD+/295C5BCA71A8/ROSA-2016.1/4.15.0-DESKTOP-94.1ROSA-X86_64/X86_64/14D1D84766>) |
| 8086:34c4 | 8086:7270 | Intel            | Ice Lake-LP SD Host Controller       | 1     | sdhci_pci  | [EFDE420A70](<Tablet/Microsoft/Surface/Surface Laptop Go/7D06E21A462C/ARCH/5.19.7-ARCH1-1/X86_64/EFDE420A70>) |
| 8086:4dc4 | 1043:1d02 | Intel            | Jasper Lake SCS1: eMMC Controller    | 1     | sdhci_pci  | [CF1735BF9E](<Tablet/ASUSTek Computer/Vivobook/Vivobook Slate T3300KA_T3300KA/CB77B9CC66FB/ELEMENTARY-6.1/5.15.0-50-GENERIC/X86_64/CF1735BF9E>) |
| 8086:4df8 | 1043:1d02 | Intel            | SD Host Controller                   | 1     | sdhci_pci  | [CF1735BF9E](<Tablet/ASUSTek Computer/Vivobook/Vivobook Slate T3300KA_T3300KA/CB77B9CC66FB/ELEMENTARY-6.1/5.15.0-50-GENERIC/X86_64/CF1735BF9E>) |
| 8086:4df8 | 8086:7270 | Intel            | SD Host Controller                   | 1     | sdhci_pci  | [C24B5A1F84](<Tablet/retsamarret/000/000-F4423-UK000-2000/5D4FAE7FB346/DEBIAN-11/5.10.0-21-AMD64/X86_64/C24B5A1F84>) |
| 8086:5aca |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | sdhci_pci  | [49D345EC0B](<Tablet/Xplore/iX101/iX101L1/1592B2F5F479/UBUNTU-20.04/5.6.0-1028-OEM/X86_64/49D345EC0B>) |
| 8086:9d2b | 17aa:382d | Intel            | Skylake-U/Y SCC: eMMC                | 1     | sdhci_pci  | [50D3528425](<Tablet/Lenovo/MIIX710-12IKB/MIIX710-12IKB 80W1/2FB91DC53770/LINUXMINT-20.3/5.15.0-33-GENERIC/X86_64/50D3528425>) |
| 8086:9d2d | 17aa:3812 | Intel            | Sunrise Point-LP Secure Digital I... | 1     | sdhci_pci  | [50D3528425](<Tablet/Lenovo/MIIX710-12IKB/MIIX710-12IKB 80W1/2FB91DC53770/LINUXMINT-20.3/5.15.0-33-GENERIC/X86_64/50D3528425>) |
| 8086:9d2d | 8086:7270 | Intel            | Sunrise Point-LP Secure Digital I... | 1     | sdhci_pci  | [ED972212E1](<Tablet/Teclast/X6/X6 Pro/F6A57BF3E09B/ARCH/5.10.55-1-LTS/X86_64/ED972212E1>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:34a4 | 8086:7270 | Intel            | Ice Lake-LP SPI Controller           | 92    | spi_int... | [FD7A2486F2](<Tablet/Microsoft/Surface/Surface Laptop Go/83C5E1166CAF/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/FD7A2486F2>) |
| 8086:34c5 | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2c Control... | 92    | intel_l... | [FD7A2486F2](<Tablet/Microsoft/Surface/Surface Laptop Go/83C5E1166CAF/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/FD7A2486F2>) |
| 8086:34e8 | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2C Control... | 92    | intel_l... | [FD7A2486F2](<Tablet/Microsoft/Surface/Surface Laptop Go/83C5E1166CAF/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/FD7A2486F2>) |
| 8086:34ea | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2C Control... | 75    | intel_l... | [FD7A2486F2](<Tablet/Microsoft/Surface/Surface Laptop Go/83C5E1166CAF/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/FD7A2486F2>) |
| 8086:34eb | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2C Control... | 53    | intel_l... | [7C8D87170F](<Tablet/Microsoft/Surface/Surface Pro 7/FDDF58D50F30/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/7C8D87170F>) |
| 8086:34e9 | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2C Control... | 19    | intel_l... | [86291F499E](<Tablet/Microsoft/Surface/Surface Laptop 3/E40BAAC0547D/FEDORA-37/6.0.7-301.FC37.X86_64/X86_64/86291F499E>) |
| 8086:a0a4 | 8086:7270 | Intel            | Tiger Lake-LP SPI Controller         | 14    | intel_spi  | [3C50D5D61C](<Tablet/Microsoft/Surface/Surface Pro 8/C4CEE7E26DF5/MANJARO/6.2.12-ARCH1-1-SURFACE/X86_64/3C50D5D61C>) |
| 8086:a0e8 | 8086:7270 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 14    | intel_lpss | [3C50D5D61C](<Tablet/Microsoft/Surface/Surface Pro 8/C4CEE7E26DF5/MANJARO/6.2.12-ARCH1-1-SURFACE/X86_64/3C50D5D61C>) |
| 8086:a0d8 | 8086:7270 | Intel            | Tiger Lake-LP Serial IO I2C Host ... | 13    | intel_lpss | [3C50D5D61C](<Tablet/Microsoft/Surface/Surface Pro 8/C4CEE7E26DF5/MANJARO/6.2.12-ARCH1-1-SURFACE/X86_64/3C50D5D61C>) |
| 8086:a0c5 | 8086:7270 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 11    | intel_lpss | [3C50D5D61C](<Tablet/Microsoft/Surface/Surface Pro 8/C4CEE7E26DF5/MANJARO/6.2.12-ARCH1-1-SURFACE/X86_64/3C50D5D61C>) |
| 8086:51a4 | 1043:1c42 | Intel            | Alder Lake-P PCH SPI Controller      | 9     | intel_spi  | [E5644591DE](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZC_GZ301ZC/D9321FF7F56A/FEDORA-37/6.2.8-300.FC37.X86_64/X86_64/E5644591DE>) |
| 8086:51e8 | 1043:1c42 | Intel            | Alder Lake PCH Serial IO I2C Cont... | 9     | intel_l... | [E5644591DE](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZC_GZ301ZC/D9321FF7F56A/FEDORA-37/6.2.8-300.FC37.X86_64/X86_64/E5644591DE>) |
| 8086:51e9 | 1043:1c42 | Intel            | Alder Lake PCH Serial IO I2C Cont... | 9     | intel_l... | [E5644591DE](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZC_GZ301ZC/D9321FF7F56A/FEDORA-37/6.2.8-300.FC37.X86_64/X86_64/E5644591DE>) |
| 8086:a0a4 | 1028:0a45 | Intel            | Tiger Lake-LP SPI Controller         | 7     | spi_int... | [5E287BBD8B](<Tablet/Dell/Latitude/Latitude 7320 Detachable/089CE6269F10/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/5E287BBD8B>) |
| 8086:a0a4 | 17aa:380b | Intel            | Tiger Lake-LP SPI Controller         | 7     | intel_spi  | [5C0467F4CB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/FA8378B128F2/ZORIN-16/5.15.0-69-GENERIC/X86_64/5C0467F4CB>) |
| 8086:a0a4 | 1ec9:3e44 | Intel            | Tiger Lake-LP SPI Controller         | 7     | intel_spi  | [F348E93361](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/4B50F0906809/UBUNTU-22.10/6.1.4-060104-GENERIC/X86_64/F348E93361>) |
| 8086:a0c5 | 1ec9:3e44 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 7     | intel_l... | [F348E93361](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/4B50F0906809/UBUNTU-22.10/6.1.4-060104-GENERIC/X86_64/F348E93361>) |
| 8086:a0e8 | 1028:0a45 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 7     | intel_l... | [5E287BBD8B](<Tablet/Dell/Latitude/Latitude 7320 Detachable/089CE6269F10/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/5E287BBD8B>) |
| 8086:a0e8 | 17aa:3823 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 7     | intel_l... | [5C0467F4CB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/FA8378B128F2/ZORIN-16/5.15.0-69-GENERIC/X86_64/5C0467F4CB>) |
| 8086:a0e8 | 1ec9:3e44 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 7     | intel_l... | [F348E93361](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/4B50F0906809/UBUNTU-22.10/6.1.4-060104-GENERIC/X86_64/F348E93361>) |
| 8086:a0e9 | 1028:0a45 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 7     | intel_l... | [5E287BBD8B](<Tablet/Dell/Latitude/Latitude 7320 Detachable/089CE6269F10/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/5E287BBD8B>) |
| 8086:a0e9 | 17aa:3824 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 7     | intel_l... | [5C0467F4CB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/FA8378B128F2/ZORIN-16/5.15.0-69-GENERIC/X86_64/5C0467F4CB>) |
| 8086:a0e9 | 1ec9:3e44 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 7     | intel_l... | [F348E93361](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/4B50F0906809/UBUNTU-22.10/6.1.4-060104-GENERIC/X86_64/F348E93361>) |
| 8086:a0ea | 1028:0a45 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 7     | intel_l... | [5E287BBD8B](<Tablet/Dell/Latitude/Latitude 7320 Detachable/089CE6269F10/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/5E287BBD8B>) |
| 8086:a0ea | 17aa:3825 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 7     | intel_l... | [5C0467F4CB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/FA8378B128F2/ZORIN-16/5.15.0-69-GENERIC/X86_64/5C0467F4CB>) |
| 8086:a0ea | 1ec9:3e44 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 7     | intel_l... | [F348E93361](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/4B50F0906809/UBUNTU-22.10/6.1.4-060104-GENERIC/X86_64/F348E93361>) |
| 8086:a0eb | 17aa:3828 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 7     | intel_l... | [5C0467F4CB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/FA8378B128F2/ZORIN-16/5.15.0-69-GENERIC/X86_64/5C0467F4CB>) |
| 8086:a0eb | 1ec9:3e44 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 7     | intel_l... | [F348E93361](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/4B50F0906809/UBUNTU-22.10/6.1.4-060104-GENERIC/X86_64/F348E93361>) |
| 8086:a0ea | 8086:7270 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 6     | intel_lpss | [3C50D5D61C](<Tablet/Microsoft/Surface/Surface Pro 8/C4CEE7E26DF5/MANJARO/6.2.12-ARCH1-1-SURFACE/X86_64/3C50D5D61C>) |
| 8086:02a4 | 17aa:3813 | Intel            | Comet Lake SPI (flash) Controller    | 5     | intel_s... | [2C581034EB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13IML05 82AS/6049DBFEB1C3/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/2C581034EB>) |
| 8086:02c5 | 17aa:3804 | Intel            | Comet Lake Serial IO I2C Host Con... | 5     | intel_l... | [2C581034EB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13IML05 82AS/6049DBFEB1C3/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/2C581034EB>) |
| 8086:02e8 | 17aa:380f | Intel            | Serial IO I2C Host Controller        | 5     | intel_l... | [2C581034EB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13IML05 82AS/6049DBFEB1C3/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/2C581034EB>) |
| 8086:a0a4 | 17aa:508b | Intel            | Tiger Lake-LP SPI Controller         | 5     | intel_spi  | [89ADCCAE04](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UVS1RL00/ECF244BC1E85/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/89ADCCAE04>) |
| 8086:a0e8 | 17aa:508b | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 5     | intel_lpss | [89ADCCAE04](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UVS1RL00/ECF244BC1E85/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/89ADCCAE04>) |
| 8086:a0e9 | 17aa:508b | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 5     | intel_lpss | [89ADCCAE04](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UVS1RL00/ECF244BC1E85/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/89ADCCAE04>) |
| 8086:a0eb | 17aa:508b | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 5     | intel_lpss | [89ADCCAE04](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UVS1RL00/ECF244BC1E85/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/89ADCCAE04>) |
| 8086:a0eb | 8086:7270 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 5     | intel_lpss | [3C50D5D61C](<Tablet/Microsoft/Surface/Surface Pro 8/C4CEE7E26DF5/MANJARO/6.2.12-ARCH1-1-SURFACE/X86_64/3C50D5D61C>) |
| 8086:4da4 | 103c:8966 | Intel            | Jasper Lake SPI Controller           | 4     | intel_spi  | [169454762C](<Tablet/Hewlett-Packard/Tablet/Tablet 11m-be0xxx/535A9A46FE41/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/169454762C>) |
| 8086:4dc5 | 103c:8966 | Intel            | Jasper Lake LPSS: I2C Controller #4  | 4     | intel_l... | [169454762C](<Tablet/Hewlett-Packard/Tablet/Tablet 11m-be0xxx/535A9A46FE41/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/169454762C>) |
| 8086:4dc6 | 103c:8966 | Intel            | Jasper Lake LPSS: I2C Controller #5  | 4     | intel_l... | [169454762C](<Tablet/Hewlett-Packard/Tablet/Tablet 11m-be0xxx/535A9A46FE41/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/169454762C>) |
| 8086:4de8 | 103c:8966 | Intel            | Serial IO I2C Host Controller        | 4     | intel_l... | [169454762C](<Tablet/Hewlett-Packard/Tablet/Tablet 11m-be0xxx/535A9A46FE41/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/169454762C>) |
| 8086:4de9 | 103c:8966 | Intel            | Serial IO I2C Host Controller        | 4     | intel_l... | [169454762C](<Tablet/Hewlett-Packard/Tablet/Tablet 11m-be0xxx/535A9A46FE41/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/169454762C>) |
| 8086:4dea | 103c:8966 | Intel            | Jasper Lake LPSS: I2C Controller #2  | 4     | intel_l... | [169454762C](<Tablet/Hewlett-Packard/Tablet/Tablet 11m-be0xxx/535A9A46FE41/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/169454762C>) |
| 8086:02a4 | 1028:09ba | Intel            | Comet Lake SPI (flash) Controller    | 3     | spi_int... | [2DE1D6F6F5](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/7A5FB94B1DE2/ARCH-ROLLING/6.2.12-ZEN1-1-ZEN/X86_64/2DE1D6F6F5>) |
| 8086:02e8 | 1028:09ba | Intel            | Serial IO I2C Host Controller        | 3     | intel_l... | [2DE1D6F6F5](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/7A5FB94B1DE2/ARCH-ROLLING/6.2.12-ZEN1-1-ZEN/X86_64/2DE1D6F6F5>) |
| 8086:51a4 | 17aa:381f | Intel            | Alder Lake-P PCH SPI Controller      | 3     | spi_int... | [ED4AEB2282](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 5 12IAU7 82TQ/75AEF6B37790/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/ED4AEB2282>) |
| 8086:51c5 | 17aa:3815 | Intel            | Alder Lake-P Serial IO I2C Contro... | 3     | intel_l... | [ED4AEB2282](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 5 12IAU7 82TQ/75AEF6B37790/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/ED4AEB2282>) |
| 8086:51c6 | 17aa:3812 | Intel            | Alder Lake-P Serial IO I2C Contro... | 3     | intel_l... | [ED4AEB2282](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 5 12IAU7 82TQ/75AEF6B37790/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/ED4AEB2282>) |
| 8086:51e8 | 17aa:3824 | Intel            | Alder Lake PCH Serial IO I2C Cont... | 3     | intel_l... | [ED4AEB2282](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 5 12IAU7 82TQ/75AEF6B37790/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/ED4AEB2282>) |
| 8086:51e9 | 17aa:3830 | Intel            | Alder Lake PCH Serial IO I2C Cont... | 3     | intel_l... | [ED4AEB2282](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 5 12IAU7 82TQ/75AEF6B37790/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/ED4AEB2282>) |

### Serial controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:34fc | 8086:7270 | Intel            | Ice Lake-LP Integrated Sensor Sol... | 56    | intel_i... | [7C8D87170F](<Tablet/Microsoft/Surface/Surface Pro 7/FDDF58D50F30/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/7C8D87170F>) |
| 8086:9d3d | 1028:07a4 | Intel            | Sunrise Point-LP Active Managemen... | 8     | serial     | [1717754347](<Tablet/Dell/Latitude/Latitude 5285/D75F67E269AD/UBUNTU-22.10/5.19.10-SURFACE/X86_64/1717754347>) |
| 8086:a0fc | 1028:0a45 | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 7     | intel_i... | [5E287BBD8B](<Tablet/Dell/Latitude/Latitude 7320 Detachable/089CE6269F10/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/5E287BBD8B>) |
| 8086:a0fc | 17aa:382d | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 7     | intel_i... | [5C0467F4CB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/FA8378B128F2/ZORIN-16/5.15.0-69-GENERIC/X86_64/5C0467F4CB>) |
| 8086:a0fc | 1ec9:3e44 | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 7     | intel_i... | [F348E93361](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/4B50F0906809/UBUNTU-22.10/6.1.4-060104-GENERIC/X86_64/F348E93361>) |
| 8086:9d3d | 103c:82ca | Intel            | Sunrise Point-LP Active Managemen... | 6     | serial     | [1D79D6F224](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/34E1707F855F/FEDORA-37/6.0.7-301.FC37.X86_64/X86_64/1D79D6F224>) |
| 8086:9d3d | 17aa:2244 | Intel            | Sunrise Point-LP Active Managemen... | 6     | serial     | [87F6FCCF0A](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJ001QUS/5E8450A1BEE8/UBUNTU-22.04/5.15.0-46-GENERIC/X86_64/87F6FCCF0A>) |
| 8086:a0e3 | 1028:0a45 | Intel            | Tiger Lake-LP Active Management T... | 6     | serial     | [5E287BBD8B](<Tablet/Dell/Latitude/Latitude 7320 Detachable/089CE6269F10/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/5E287BBD8B>) |
| 8086:02fc | 17aa:380c | Intel            | Comet Lake Integrated Sensor Solu... | 5     | intel_i... | [2C581034EB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13IML05 82AS/6049DBFEB1C3/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/2C581034EB>) |
| 8086:9d3d | 1028:081d | Intel            | Sunrise Point-LP Active Managemen... | 5     | serial     | [1840C57073](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/96D5F5EB923F/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/1840C57073>) |
| 8086:a0fc | 17aa:508b | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 5     | intel_i... | [89ADCCAE04](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UVS1RL00/ECF244BC1E85/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/89ADCCAE04>) |
| 8086:9d3d | 1028:06e6 | Intel            | Sunrise Point-LP Active Managemen... | 4     | serial     | [E2E7D9CE38](<Tablet/Dell/Latitude/Latitude 5179/597547DCB08C/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/E2E7D9CE38>) |
| 8086:9d3d | 1028:07a5 | Intel            | Sunrise Point-LP Active Managemen... | 4     | serial     | [0EC990AB1E](<Tablet/Dell/Latitude/Latitude 7285/D6569A451159/ZORIN-16/5.13.0-40-GENERIC/X86_64/0EC990AB1E>) |
| 8086:02fc | 1028:09ba | Intel            | Comet Lake Integrated Sensor Solu... | 3     | intel_i... | [2DE1D6F6F5](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/7A5FB94B1DE2/ARCH-ROLLING/6.2.12-ZEN1-1-ZEN/X86_64/2DE1D6F6F5>) |
| 8086:51fc | 8086:7270 | Intel            | Alder Lake-P Integrated Sensor Hub   | 3     | intel_i... | [ED4AEB2282](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 5 12IAU7 82TQ/75AEF6B37790/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/ED4AEB2282>) |
| 8086:9d3d | 17aa:2241 | Intel            | Sunrise Point-LP Active Managemen... | 3     | serial     | [6F25E83AF0](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GHS23Y00/84A0B6937CD1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/6F25E83AF0>) |
| 8086:9de3 | 103c:85b9 | Intel            | Cannon Point-LP Keyboard and Text... | 3     | serial     | [D49CBA4016](<Tablet/Hewlett-Packard/Elite/Elite x2 G4/D4F39DF208E2/LINUXMINT-21.1/6.0.0-1012-OEM/X86_64/D49CBA4016>) |
| 8086:9dfc | 103c:85b9 | Intel            | Cannon Point-LP Integrated Sensor... | 3     | intel_i... | [D49CBA4016](<Tablet/Hewlett-Packard/Elite/Elite x2 G4/D4F39DF208E2/LINUXMINT-21.1/6.0.0-1012-OEM/X86_64/D49CBA4016>) |
| 8086:02e3 | 1028:09ba | Intel            | Comet Lake PCH-LP Keyboard and Te... | 2     | serial     | [2DE1D6F6F5](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/7A5FB94B1DE2/ARCH-ROLLING/6.2.12-ZEN1-1-ZEN/X86_64/2DE1D6F6F5>) |
| 8086:1e3d | 10f7:8338 | Intel            | 7 Series/C210 Series Chipset Fami... | 2     | serial     | [06F11C0449](<Tablet/Panasonic/FZ-G1/FZ-G1ASH39E3/6F2FB083615E/ELEMENTARY-6/5.11.0-37-GENERIC/X86_64/06F11C0449>) |
| 8086:9d3d | 1028:06d6 | Intel            | Sunrise Point-LP Active Managemen... | 2     | serial     | [C118CA04BC](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/C118CA04BC>) |
| 8086:9d3d | 17aa:2243 | Intel            | Sunrise Point-LP Active Managemen... | 2     | serial     | [E770166097](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JB002BUS/210F53E293F4/UBUNTU-20.04/5.15.0-46-GENERIC/X86_64/E770166097>) |
| 8086:02fc | 1071:d301 | Intel            | Comet Lake Integrated Sensor Solu... | 1     | intel_i... | [6F57AB0251](<Tablet/Getac/UX10/UX10G2/9B2D92B11BC9/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/6F57AB0251>) |
| 8086:1191 |           | Intel            | Merrifield Serial IO HSUART Contr... | 1     |            | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:1192 |           | Intel            | Merrifield Serial IO HSUART DMA C... | 1     |            | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:1c3d | 10f7:8338 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | serial     | [50E0A85FD3](<Tablet/Panasonic/CF-H2/CF-H2BJJHZDE/E17482358B17/LMDE-5/5.10.0-13-AMD64/X86_64/50E0A85FD3>) |
| 8086:51fc | 1028:0b34 | Intel            | Alder Lake-P Integrated Sensor Hub   | 1     | intel_i... | [6049494197](<Tablet/Dell/XPS/XPS 13 9315 2-in-1/1EF842C3A2C1/UBUNTU-22.04/6.1.0-1007-OEM/X86_64/6049494197>) |
| 8086:9d3d | 103c:828b | Intel            | Sunrise Point-LP Active Managemen... | 1     | serial     | [6ECC8F0BAD](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/7A82B39E3BAF/FEDORA-37/6.1.15-200.FC37.X86_64/X86_64/6ECC8F0BAD>) |
| 8086:9d3d | 103c:8414 | Intel            | Sunrise Point-LP Active Managemen... | 1     | serial     | [A7B40883C3](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/8986075330AF/FEDORA-36/5.19.6-200.FC36.X86_64/X86_64/A7B40883C3>) |
| 8086:9d3d | 10f7:8338 | Intel            | Sunrise Point-LP Active Managemen... | 1     | serial     | [94539C6DB9](<Tablet/Panasonic/CF-33/CF-33-1/AE1D638EDC9E/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/94539C6DB9>) |
| 8086:9de3 | 1028:08e9 | Intel            | Cannon Point-LP Keyboard and Text... | 1     | serial     | [2DD1504CF8](<Tablet/Dell/Latitude/Latitude 7200 2-in-1/420B18298724/UBUNTU-20.04/5.8.0-43-GENERIC/X86_64/2DD1504CF8>) |
| 8086:9dfc | 1028:08e9 | Intel            | Cannon Point-LP Integrated Sensor... | 1     | intel_i... | [2DD1504CF8](<Tablet/Dell/Latitude/Latitude 7200 2-in-1/420B18298724/UBUNTU-20.04/5.8.0-43-GENERIC/X86_64/2DD1504CF8>) |
| 8086:a0e3 | 17aa:508b | Intel            | Tiger Lake-LP Active Management T... | 1     | serial     | [89ADCCAE04](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UVS1RL00/ECF244BC1E85/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/89ADCCAE04>) |
| 8086:a0fc | 103c:870d | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 1     | intel_i... | [D6BA8E665C](<Tablet/Hewlett-Packard/Elite/Elite x2 G8 Tablet/6D7618F54734/UBUNTU-21.10/5.13.0-40-GENERIC/X86_64/D6BA8E665C>) |
| 8086:a0fc | 1071:a121 | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 1     | intel_i... | [5D9E3F3501](<Tablet/Getac/K120/K120G2/9B90212BD0E9/UBUNTU-18.04/5.4.0-84-GENERIC/X86_64/5D9E3F3501>) |
| 8086:a0fc | 1071:e207 | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 1     |            | [2A05772CB6](<Tablet/Getac/F110/F110G6/36F31BBCD939/RELD-7.9/5.15.33-1.RES7.X86_64/X86_64/2A05772CB6>) |
| 8086:a0fc | 8086:7270 | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 1     | intel_i... | [A4AEFCD9B2](<Tablet/Microsoft/Surface/Surface Pro 7+/B513B8EA5A0E/FEDORA-32/5.10.10-1.SURFACE.FC32.X86_64/X86_64/A4AEFCD9B2>) |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d31 | 8086:7270 | Intel            | Sunrise Point-LP Thermal subsystem   | 270   | intel_p... | [0332AF656C](<Tablet/Microsoft/Surface/Surface Pro/F1C987F0D508/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/0332AF656C>) |
| 8086:9d60 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 270   | intel_l... | [0332AF656C](<Tablet/Microsoft/Surface/Surface Pro/F1C987F0D508/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/0332AF656C>) |
| 8086:9d61 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 270   | intel_l... | [0332AF656C](<Tablet/Microsoft/Surface/Surface Pro/F1C987F0D508/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/0332AF656C>) |
| 8086:9d63 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 256   | intel_l... | [0332AF656C](<Tablet/Microsoft/Surface/Surface Pro/F1C987F0D508/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/0332AF656C>) |
| 8086:9d62 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 253   | intel_l... | [0332AF656C](<Tablet/Microsoft/Surface/Surface Pro/F1C987F0D508/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/0332AF656C>) |
| 8086:9d27 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO UART C... | 140   | intel_l... | [0332AF656C](<Tablet/Microsoft/Surface/Surface Pro/F1C987F0D508/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/0332AF656C>) |
| 8086:1903 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 135   | process... | [0332AF656C](<Tablet/Microsoft/Surface/Surface Pro/F1C987F0D508/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/0332AF656C>) |
| 8086:22dc | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 116   | process... | [40D1BBA9E2](<Tablet/Hampoo/I1/I1D6_C109S_Hi10Pro/8F753D037AF0/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/40D1BBA9E2>) |
| 8086:22dc | 17aa:3809 | Intel            | Atom/Celeron/Pentium Processor x5... | 62    | process... | [5B5EBA537A](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/E141169A4B3D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/5B5EBA537A>) |
| 8086:8a03 | 8086:7270 | Intel            | Processor Power and Thermal Contr... | 58    | process... | [7C8D87170F](<Tablet/Microsoft/Surface/Surface Pro 7/FDDF58D50F30/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/7C8D87170F>) |
| 8086:22dc | 17aa:3808 | Intel            | Atom/Celeron/Pentium Processor x5... | 53    | proc_th... | [3F12350D47](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/2E38E9723355/POP!_OS-21.04/5.15.5-76051505-GENERIC/X86_64/3F12350D47>) |
| 8086:318c | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 48    | process... | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:31ac | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 48    | intel_l... | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:31ae | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 48    | intel_l... | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:31b0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 48    | intel_l... | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:31b2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 48    | intel_l... | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:31b4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 48    | intel_l... | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:31b6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 48    | intel_l... | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:31b8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 48    | intel_l... | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:31ba | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 48    | intel_l... | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:31bc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 48    | intel_l... | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:31be | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 48    | intel_l... | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:31c0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 48    | intel_l... | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:31c2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 48    | intel_l... | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:31c4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 48    | intel_l... | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:31c6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 48    | intel_l... | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:31ee | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 48    | intel_l... | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:22dc | 7270:8086 | Intel            | Atom/Celeron/Pentium Processor x5... | 45    | process... | [3316360D7A](<Tablet/Lenovo/YB1/YB1-X91F/68EFD6F91FDD/FEDORA-35/6.3.0-RC6+/X86_64/3316360D7A>) |
| 8086:1903 | 152d:1182 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 37    | process... | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:5aac | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 37    | intel_l... | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |
| 8086:5aae | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 37    | intel_l... | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |
| 8086:5ab2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 37    | intel_l... | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |
| 8086:5ab4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 37    | intel_l... | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |
| 8086:5ab6 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 37    | intel_l... | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |
| 8086:9d27 | 152d:1182 | Intel            | Sunrise Point-LP Serial IO UART C... | 37    | intel_l... | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:9d31 | 152d:1182 | Intel            | Sunrise Point-LP Thermal subsystem   | 37    | intel_p... | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:9d60 | 152d:1182 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 37    | intel_l... | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:9d61 | 152d:1182 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 37    | intel_l... | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:9d62 | 152d:1182 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 37    | intel_l... | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:9d63 | 152d:1182 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 37    | intel_l... | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:9d64 | 152d:1182 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 37    | intel_l... | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:9d66 | 152d:1182 | Intel            | Sunrise Point-LP Serial IO UART C... | 37    | intel_l... | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:22dc | 1043:13a0 | Intel            | Atom/Celeron/Pentium Processor x5... | 32    | process... | [60962892BC](<Tablet/ASUSTek Computer/T101/T101HA/5F2FAE88E834/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/60962892BC>) |
| 8086:1903 | 8086:1903 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 31    | process... | [6FF1D34454](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 20M3/154D3B05B100/UBUNTU-20.04/5.15.0-58-GENERIC/X86_64/6FF1D34454>) |
| 8086:5ab0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 29    | intel_l... | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |
| 8086:5ab8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 29    | intel_l... | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |
| 8086:5aba | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 29    | intel_l... | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |
| 8086:5abc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 29    | intel_l... | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |
| 8086:5abe | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 29    | intel_l... | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |
| 8086:5ac0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 29    | intel_l... | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9c22 | 1414:9c22 | Intel            | 8 Series SMBus Controller            | 98    | i2c_i801   | [27A1A2533B](<Tablet/Microsoft/Surface/Surface Pro 3/CD0693C63FAF/DEBIAN-12/6.1.0-7-AMD64/X86_64/27A1A2533B>) |
| 8086:31d4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 48    | i2c_i801   | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:5ad4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 37    | i2c_i801   | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |
| 8086:9d23 | 8086:7270 | Intel            | Sunrise Point-LP SMBus               | 33    | i801_smbus | [5A5E168C99](<Tablet/Microsoft/Surface/Surface Book 2/E6819C0E6E6D/KALI-2023.1/6.2.10-SURFACE/X86_64/5A5E168C99>) |
| 1022:790b | 1022:790b | AMD              | FCH SMBus Controller                 | 22    | piix4_s... | [672B480B96](<Tablet/AYANEO/2/2/4246C8CCCDD5/CHIMERAOS-41/6.1.21-1-LTS/X86_64/672B480B96>) |
| 8086:9d23 | 103c:82ca | Intel            | Sunrise Point-LP SMBus               | 21    | i2c_i801   | [F76DC1B9B7](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/9B3C72E9E186/ARCH-ROLLING/6.2.12-ARCH1-1/X86_64/F76DC1B9B7>) |
| 1002:4385 | 1025:0577 | AMD              | SBx00 SMBus Controller               | 18    | i2c_pii... | [C3D132FB91](<Tablet/Acer/Iconia/Iconia Tab W501/B59AD5DD817B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C3D132FB91>) |
| 8086:0f12 | 1019:99a5 | Intel            | Atom Processor E3800/CE2700 Serie... | 13    | i801_smbus | [C35A8D75CE](<Tablet/Intel/powered/powered classmate PC/E3EDE14D59EF/LINUXMINT-20.2/5.4.0-135-GENERIC/X86_64/C35A8D75CE>) |
| 8086:31d4 | 17aa:3823 | Intel            | Celeron/Pentium Silver Processor ... | 13    | i2c_i801   | [42DA57CF53](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGL 82H0/66D15DFB427C/UBUNTU-20.04/5.15.0-52-GENERIC/X86_64/42DA57CF53>) |
| 8086:1e22 | 1414:1e22 | Intel            | 7 Series/C216 Chipset Family SMBu... | 12    | i2c_i801   | [0E56C5B9F7](<Tablet/Microsoft/Surface/Surface with Windows 8 Pro/F2C38254ABB9/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/0E56C5B9F7>) |
| 8086:9d23 | 17aa:2244 | Intel            | Sunrise Point-LP SMBus               | 12    | i2c_i801   | [ABA0D29DD8](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJ001NFR/32F606BCA186/UBUNTU-22.10/5.19.0-29-GENERIC/X86_64/ABA0D29DD8>) |
| 8086:9d23 | 17aa:384f | Intel            | Sunrise Point-LP SMBus               | 12    | i2c_i801   | [6FF1D34454](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 20M3/154D3B05B100/UBUNTU-20.04/5.15.0-58-GENERIC/X86_64/6FF1D34454>) |
| 8086:9d23 | 144d:c14f | Intel            | Sunrise Point-LP SMBus               | 11    | i2c_i801   | [167229560A](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/KUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/167229560A>) |
| 8086:51a3 | 1043:1c42 | Intel            | Alder Lake PCH-P SMBus Host Contr... | 9     | i2c_i801   | [E5644591DE](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZC_GZ301ZC/D9321FF7F56A/FEDORA-37/6.2.8-300.FC37.X86_64/X86_64/E5644591DE>) |
| 8086:9d23 | 1028:07a4 | Intel            | Sunrise Point-LP SMBus               | 9     | i2c_i801   | [1717754347](<Tablet/Dell/Latitude/Latitude 5285/D75F67E269AD/UBUNTU-22.10/5.19.10-SURFACE/X86_64/1717754347>) |
| 8086:9d23 | 103c:828b | Intel            | Sunrise Point-LP SMBus               | 9     | i2c_i801   | [6ECC8F0BAD](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/7A82B39E3BAF/FEDORA-37/6.1.15-200.FC37.X86_64/X86_64/6ECC8F0BAD>) |
| 8086:9d23 | 1028:081d | Intel            | Sunrise Point-LP SMBus               | 8     | i801_smbus | [88900A37B9](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/172279AB141B/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/88900A37B9>) |
| 8086:9d23 | 8086:9d23 | Intel            | Sunrise Point-LP SMBus               | 8     | i2c_i801   | [0F05F12004](<Tablet/Teclast/X5/X5 Pro/B130987D6E6A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0F05F12004>) |
| 8086:9ca2 | 17aa:222b | Intel            | Wildcat Point-LP SMBus Controller    | 7     | i2c_i801   | [E6190D3469](<Tablet/Lenovo/ThinkPad/ThinkPad Helix 2nd 20CHS0JK00/2C8F871AAAFD/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E6190D3469>) |
| 8086:9d23 | 1028:06e6 | Intel            | Sunrise Point-LP SMBus               | 7     | i2c_i801   | [C751321AB1](<Tablet/Dell/Latitude/Latitude 5175/725A65699078/FEDORA-36/5.18.18-200.FC36.X86_64/X86_64/C751321AB1>) |
| 8086:9d23 | 144d:c135 | Intel            | Sunrise Point-LP SMBus               | 7     | i2c_i801   | [25DEDA3E27](<Tablet/Samsung Electronics/Galaxy/Galaxy TabPro S/A1DD930DF301/UBUNTU-20.04/5.4.0-90-GENERIC/X86_64/25DEDA3E27>) |
| 8086:9d23 | 17aa:3844 | Intel            | Sunrise Point-LP SMBus               | 7     | i2c_i801   | [D88BD74ACF](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/B632F2BAF8BF/FEDORA-38/6.2.0-0.RC0.20221221GITB6BB9676F216.10.FC38.X86_64/X86_64/D88BD74ACF>) |
| 8086:a0a3 | 1028:0a45 | Intel            | Tiger Lake-LP SMBus Controller       | 7     | i2c_i801   | [5E287BBD8B](<Tablet/Dell/Latitude/Latitude 7320 Detachable/089CE6269F10/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/5E287BBD8B>) |
| 8086:a0a3 | 17aa:3805 | Intel            | Tiger Lake-LP SMBus Controller       | 7     | i2c_i801   | [5C0467F4CB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/FA8378B128F2/ZORIN-16/5.15.0-69-GENERIC/X86_64/5C0467F4CB>) |
| 8086:a0a3 | 1ec9:3e44 | Intel            | Tiger Lake-LP SMBus Controller       | 7     | i2c_i801   | [F348E93361](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/4B50F0906809/UBUNTU-22.10/6.1.4-060104-GENERIC/X86_64/F348E93361>) |
| 8086:0f12 | 1019:99a1 | Intel            | Atom Processor E3800/CE2700 Serie... | 6     | i2c_i801   | [C61A96D514](<Tablet/Medion/P/P2212T/71C4E4B2F18A/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/C61A96D514>) |
| 8086:31d4 | 17aa:3829 | Intel            | Celeron/Pentium Silver Processor ... | 6     | i2c_i801   | [C81361E795](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 10IGL5 82AT/605931C0A403/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/C81361E795>) |
| 8086:5ad4 | 8086:5ad4 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 6     | i2c_i801   | [F8733FFC4D](<Tablet/ZoomSmart/A/A1002/766C759236A3/ROSA-12.3/5.15.79-GENERIC-1ROSA2021.1-X86_64/X86_64/F8733FFC4D>) |
| 8086:9d23 | 1028:06d6 | Intel            | Sunrise Point-LP SMBus               | 6     | i801_smbus | [C118CA04BC](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/C118CA04BC>) |
| 8086:9d23 | 17aa:2241 | Intel            | Sunrise Point-LP SMBus               | 6     | i2c_i801   | [CC6FE2D666](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/8D924D4AA03C/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/CC6FE2D666>) |
| 8086:9d23 | 17aa:2243 | Intel            | Sunrise Point-LP SMBus               | 6     | i2c_i801   | [149C782883](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCA016JP/4766889E4D51/SIDUCTION-12/6.2.2-3-SIDUCTION-AMD64/X86_64/149C782883>) |
| 8086:31d4 | 8086:31d4 | Intel            | Celeron/Pentium Silver Processor ... | 5     | i2c_i801   | [810D937888](<Tablet/Tactus/GeoPad/GeoPad 110/0F02FAE679C1/ZORIN-16/5.15.0-56-GENERIC/X86_64/810D937888>) |
| 8086:9c22 | 17aa:3978 | Intel            | 8 Series SMBus Controller            | 5     | i2c_i801   | [69E83BCD80](<Tablet/Lenovo/MIIX/MIIX 2 11 20327/7DF5CB4D666D/ZORIN-16/5.15.0-56-GENERIC/X86_64/69E83BCD80>) |
| 8086:9d23 | 1025:111e | Intel            | Sunrise Point-LP SMBus               | 5     | i801_smbus | [C9900A8E2F](<Tablet/Acer/Switch/Switch SA5-271P/DFFCE0790341/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C9900A8E2F>) |
| 8086:9d23 | 103c:8414 | Intel            | Sunrise Point-LP SMBus               | 5     | i2c_i801   | [E8D1866113](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/AC04F34CD8CA/DEBIAN/6.0.0-5-AMD64/X86_64/E8D1866113>) |
| 8086:a0a3 | 17aa:508b | Intel            | Tiger Lake-LP SMBus Controller       | 5     | i2c_i801   | [89ADCCAE04](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UVS1RL00/ECF244BC1E85/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/89ADCCAE04>) |
| 8086:4da3 | 103c:8966 | Intel            | Jasper Lake SMBus                    | 4     | i2c_i801   | [169454762C](<Tablet/Hewlett-Packard/Tablet/Tablet 11m-be0xxx/535A9A46FE41/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/169454762C>) |
| 8086:9d23 | 1028:07a5 | Intel            | Sunrise Point-LP SMBus               | 4     | i801_smbus | [0EC990AB1E](<Tablet/Dell/Latitude/Latitude 7285/D6569A451159/ZORIN-16/5.13.0-40-GENERIC/X86_64/0EC990AB1E>) |
| 8086:9d23 | 17aa:3829 | Intel            | Sunrise Point-LP SMBus               | 4     | i2c_i801   | [D43709B2F7](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/B40E17CB6AAF/UBUNTU-22.10/5.19.0-26-GENERIC/X86_64/D43709B2F7>) |
| 8086:02a3 | 1028:09ba | Intel            | Comet Lake PCH-LP SMBus Host Cont... | 3     | i2c_i801   | [2DE1D6F6F5](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/7A5FB94B1DE2/ARCH-ROLLING/6.2.12-ZEN1-1-ZEN/X86_64/2DE1D6F6F5>) |
| 8086:31d4 |           | Intel            | Celeron/Pentium Silver Processor ... | 3     | i2c_i801   | [05EDD845DF](<Tablet/Lenovo/Tablet/Tablet 10 20L3000KGE/7130A0BB6850/UBUNTU-22.10/5.19.0-40-GENERIC/X86_64/05EDD845DF>) |
| 8086:51a3 | 17aa:381d | Intel            | Alder Lake PCH-P SMBus Host Contr... | 3     | i2c_i801   | [ED4AEB2282](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 5 12IAU7 82TQ/75AEF6B37790/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/ED4AEB2282>) |
| 8086:9d23 | 1025:1171 | Intel            | Sunrise Point-LP SMBus               | 3     | i2c_i801   | [7D44E4C760](<Tablet/Acer/Switch/Switch SW512-52/9061A4CB688E/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/7D44E4C760>) |
| 8086:9d23 | 103c:82cb | Intel            | Sunrise Point-LP SMBus               | 3     | i2c_i801   | [9DE6B65A45](<Tablet/Hewlett-Packard/Spectre/Spectre x2 Detachable 12-c0XX/107C5ABF10E7/ARCH-ROLLING/6.2.2-ARCH1-1/X86_64/9DE6B65A45>) |
| 8086:9d23 | 1043:1410 | Intel            | Sunrise Point-LP SMBus               | 3     | i2c_i801   | [B945137346](<Tablet/ASUSTek Computer/T305/T305CA/E8B080C97665/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/B945137346>) |
| 8086:9d23 | 17aa:3833 | Intel            | Sunrise Point-LP SMBus               | 3     | i2c_i801   | [67E1BDD5F1](<Tablet/Lenovo/MIIX/MIIX 720-12IKB 80VV/F45F8CE4052D/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/67E1BDD5F1>) |
| 8086:9da3 | 103c:85b9 | Intel            | Cannon Point-LP SMBus Controller     | 3     | i2c_i801   | [D49CBA4016](<Tablet/Hewlett-Packard/Elite/Elite x2 G4/D4F39DF208E2/LINUXMINT-21.1/6.0.0-1012-OEM/X86_64/D49CBA4016>) |
| 8086:0f12 | 1509:7018 | Intel            | Atom Processor E3800/CE2700 Serie... | 2     | i2c_i801   | [9347717861](<Tablet/Xplore/iX101/iX101B1/988A604FB8AB/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/9347717861>) |
| 8086:0f12 | 1854:0211 | Intel            | Atom Processor E3800/CE2700 Serie... | 2     | i2c_i801   | [44AF16AC16](<Tablet/LG Electronics/15U340/15U340-L.BK55P1/96572D02BF5F/LINUXMINT-20/5.4.0-42-GENERIC/X86_64/44AF16AC16>) |
| 8086:0f12 | 8086:7270 | Intel            | Atom Processor E3800/CE2700 Serie... | 2     | i2c_i801   | [A018825B67](<Tablet/CAKE/POS/POS V3/6B0F662D72A6/UBUNTU-18.04/5.4.0-128-GENERIC/X86_64/A018825B67>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d71 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 146   | snd_hda... | [0332AF656C](<Tablet/Microsoft/Surface/Surface Pro/F1C987F0D508/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/0332AF656C>) |
| 8086:9d70 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 123   | snd_hda... | [7FD9FD4619](<Tablet/Microsoft/Surface/Surface Pro 4/11BB44FDB753/POP!_OS-22.04/6.2.14-SURFACE/X86_64/7FD9FD4619>) |
| 8086:9c20 | 1414:9c20 | Intel            | 8 Series HD Audio Controller         | 98    | snd_hda... | [27A1A2533B](<Tablet/Microsoft/Surface/Surface Pro 3/CD0693C63FAF/DEBIAN-12/6.1.0-7-AMD64/X86_64/27A1A2533B>) |
| 8086:34c8 | 8086:7270 | Intel            | Ice Lake-LP Smart Sound Technolog... | 92    | snd_hda... | [FD7A2486F2](<Tablet/Microsoft/Surface/Surface Laptop Go/83C5E1166CAF/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/FD7A2486F2>) |
| 8086:0a0c | 8086:0a0c | Intel            | Haswell-ULT HD Audio Controller      | 79    | snd_hda... | [27A1A2533B](<Tablet/Microsoft/Surface/Surface Pro 3/CD0693C63FAF/DEBIAN-12/6.1.0-7-AMD64/X86_64/27A1A2533B>) |
| 8086:9d71 | 152d:1182 | Intel            | Sunrise Point-LP HD Audio            | 36    | snd_hda... | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:3198 | 1c6c:122a | Intel            | Celeron/Pentium Silver Processor ... | 31    | snd_hda... | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:9d71 | 103c:82ca | Intel            | Sunrise Point-LP HD Audio            | 20    | snd_hda... | [F76DC1B9B7](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/9B3C72E9E186/ARCH-ROLLING/6.2.12-ARCH1-1/X86_64/F76DC1B9B7>) |
| 8086:0a0c | 8086:2010 | Intel            | Haswell-ULT HD Audio Controller      | 19    | snd_hda... | [3237FF6784](<Tablet/Microsoft/Surface/Surface Pro 2/7DF1C7B40ADE/ELEMENTARY-6.1/5.15.0-56-GENERIC/X86_64/3237FF6784>) |
| 1002:1314 | 1025:0577 | AMD              | Wrestler HDMI Audio                  | 18    | snd_hda... | [C3D132FB91](<Tablet/Acer/Iconia/Iconia Tab W501/B59AD5DD817B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C3D132FB91>) |
| 1002:4383 | 1025:0577 | AMD              | SBx00 Azalia (Intel HDA)             | 18    | snd_hda... | [C3D132FB91](<Tablet/Acer/Iconia/Iconia Tab W501/B59AD5DD817B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C3D132FB91>) |
| 8086:a0c8 | 8086:7270 | Intel            | Tiger Lake-LP Smart Sound Technol... | 14    | snd_hda... | [3C50D5D61C](<Tablet/Microsoft/Surface/Surface Pro 8/C4CEE7E26DF5/MANJARO/6.2.12-ARCH1-1-SURFACE/X86_64/3C50D5D61C>) |
| 8086:0f04 | 1019:99fa | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 13    | snd_hda... | [C35A8D75CE](<Tablet/Intel/powered/powered classmate PC/E3EDE14D59EF/LINUXMINT-20.2/5.4.0-135-GENERIC/X86_64/C35A8D75CE>) |
| 8086:3198 | 17aa:3809 | Intel            | Celeron/Pentium Silver Processor ... | 13    | snd_hda... | [42DA57CF53](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGL 82H0/66D15DFB427C/UBUNTU-20.04/5.15.0-52-GENERIC/X86_64/42DA57CF53>) |
| 8086:1e20 | 1414:1e20 | Intel            | 7 Series/C216 Chipset Family High... | 12    | snd_hda... | [0E56C5B9F7](<Tablet/Microsoft/Surface/Surface with Windows 8 Pro/F2C38254ABB9/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/0E56C5B9F7>) |
| 8086:9d71 | 152d:1237 | Intel            | Sunrise Point-LP HD Audio            | 12    | snd_hda... | [EDCDEDD65A](<Tablet/Microsoft/Surface/Surface Go 2/5B20BDF3E76F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/EDCDEDD65A>) |
| 8086:9d71 | 17aa:2244 | Intel            | Sunrise Point-LP HD Audio            | 12    | snd_hda... | [ABA0D29DD8](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJ001NFR/32F606BCA186/UBUNTU-22.10/5.19.0-29-GENERIC/X86_64/ABA0D29DD8>) |
| 8086:9d71 | 17aa:3817 | Intel            | Sunrise Point-LP HD Audio            | 12    | snd_hda... | [6FF1D34454](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 20M3/154D3B05B100/UBUNTU-20.04/5.15.0-58-GENERIC/X86_64/6FF1D34454>) |
| 8086:9d71 | 144d:c14f | Intel            | Sunrise Point-LP HD Audio            | 11    | snd_hda... | [167229560A](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/KUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/167229560A>) |
| 1002:1637 | 1002:1637 | AMD              | Renoir Radeon High Definition Aud... | 10    | snd_hda... | [D721C7AE17](<Tablet/ONE-NETBOOK TECHNOLOGY/ONE/ONE XPLAYER/B9BDBF250081/CHIMERAOS-37/6.0.8-ARCH1-1/X86_64/D721C7AE17>) |
| 8086:51c8 | 1043:1c42 | Intel            | Alder Lake PCH-P High Definition ... | 9     | snd_hda... | [E5644591DE](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZC_GZ301ZC/D9321FF7F56A/FEDORA-37/6.2.8-300.FC37.X86_64/X86_64/E5644591DE>) |
| 8086:9d71 | 1028:07a4 | Intel            | Sunrise Point-LP HD Audio            | 9     | snd_hda... | [1717754347](<Tablet/Dell/Latitude/Latitude 5285/D75F67E269AD/UBUNTU-22.10/5.19.10-SURFACE/X86_64/1717754347>) |
| 8086:9d71 | 103c:828b | Intel            | Sunrise Point-LP HD Audio            | 9     | snd_hda... | [6ECC8F0BAD](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/7A82B39E3BAF/FEDORA-37/6.1.15-200.FC37.X86_64/X86_64/6ECC8F0BAD>) |
| 8086:5a98 | 1025:1209 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 8     | snd_hda... | [282EF194E5](<Tablet/Acer/Switch/Switch SW312-31/46CE66B2E570/XUBUNTU-22.04/5.15.0-48-GENERIC/X86_64/282EF194E5>) |
| 8086:9d71 | 1028:081d | Intel            | Sunrise Point-LP HD Audio            | 8     | snd_hda... | [88900A37B9](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/172279AB141B/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/88900A37B9>) |
| 1022:15e3 | 10ec:0000 | AMD              | Family 17h/19h HD Audio Controller   | 7     | snd_hda... | [D721C7AE17](<Tablet/ONE-NETBOOK TECHNOLOGY/ONE/ONE XPLAYER/B9BDBF250081/CHIMERAOS-37/6.0.8-ARCH1-1/X86_64/D721C7AE17>) |
| 10de:2291 | 1043:1c42 | Nvidia           | Audio device                         | 7     | snd_hda... | [DEE13EAC1D](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZE_GZ301ZE/81FF0FC471FE/ARCH-ROLLING/5.15.74-1-LTS/X86_64/DEE13EAC1D>) |
| 8086:160c | 17aa:222b | Intel            | Broadwell-U Audio Controller         | 7     | snd_hda... | [E6190D3469](<Tablet/Lenovo/ThinkPad/ThinkPad Helix 2nd 20CHS0JK00/2C8F871AAAFD/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E6190D3469>) |
| 8086:5a98 | 1c6c:122a | Intel            | Celeron N3350/Pentium N4200/Atom ... | 7     | snd_hda... | [DE64A1E585](<Tablet/Zinox Technologies/x64-Based/x64-Based PC/B8682FC1F33D/FEDORA-36/5.17.5-300.FC36.X86_64/X86_64/DE64A1E585>) |
| 8086:9d70 | 144d:c135 | Intel            | Sunrise Point-LP HD Audio            | 7     | snd_hda... | [25DEDA3E27](<Tablet/Samsung Electronics/Galaxy/Galaxy TabPro S/A1DD930DF301/UBUNTU-20.04/5.4.0-90-GENERIC/X86_64/25DEDA3E27>) |
| 8086:9d71 | 17aa:380c | Intel            | Sunrise Point-LP HD Audio            | 7     | snd_hda... | [D88BD74ACF](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/B632F2BAF8BF/FEDORA-38/6.2.0-0.RC0.20221221GITB6BB9676F216.10.FC38.X86_64/X86_64/D88BD74ACF>) |
| 8086:a0c8 | 1028:0a45 | Intel            | Tiger Lake-LP Smart Sound Technol... | 7     | snd_hda... | [5E287BBD8B](<Tablet/Dell/Latitude/Latitude 7320 Detachable/089CE6269F10/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/5E287BBD8B>) |
| 8086:a0c8 | 17aa:3820 | Intel            | Tiger Lake-LP Smart Sound Technol... | 7     | snd_hda... | [5C0467F4CB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/FA8378B128F2/ZORIN-16/5.15.0-69-GENERIC/X86_64/5C0467F4CB>) |
| 8086:a0c8 | 1ec9:3e44 | Intel            | Tiger Lake-LP Smart Sound Technol... | 7     | snd_hda... | [F348E93361](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/4B50F0906809/UBUNTU-22.10/6.1.4-060104-GENERIC/X86_64/F348E93361>) |
| 1002:15de | 1002:15de | AMD              | Raven/Raven2/Fenghuang HDMI/DP Au... | 6     | snd_hda... | [88EA27E220](<Tablet/Microsoft/Surface/Surface Laptop 3/49F309623B33/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/88EA27E220>) |
| 1002:1640 | 1002:1640 | AMD              | Rembrandt Radeon High Definition ... | 6     | snd_hda... | [672B480B96](<Tablet/AYANEO/2/2/4246C8CCCDD5/CHIMERAOS-41/6.1.21-1-LTS/X86_64/672B480B96>) |
| 1022:15e3 | 1022:d001 | AMD              | Family 17h/19h HD Audio Controller   | 6     | snd_hda... | [88EA27E220](<Tablet/Microsoft/Surface/Surface Laptop 3/49F309623B33/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/88EA27E220>) |
| 8086:0f04 | 1019:99a6 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | snd_hda... | [C61A96D514](<Tablet/Medion/P/P2212T/71C4E4B2F18A/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/C61A96D514>) |
| 8086:22a8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 6     |            | [9DEB58B002](<Tablet/Hampoo/I1/I1D6_C189A/7C76997E762A/CLEAR-LINUX-OS-36010/5.16.13-1132.NATIVE/X86_64/9DEB58B002>) |
| 8086:3198 | 17aa:3811 | Intel            | Celeron/Pentium Silver Processor ... | 6     | snd_hda... | [C81361E795](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 10IGL5 82AT/605931C0A403/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/C81361E795>) |
| 8086:3198 | 2782:0303 | Intel            | Celeron/Pentium Silver Processor ... | 6     | snd_hda... | [876EC3C7C3](<Tablet/Chuwi/Hi10/Hi10 X/759BE25598DF/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/876EC3C7C3>) |
| 8086:3198 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 6     | snd_hda... | [D4ACDF3439](<Tablet/ALLDOCUBE/i1025/i1025P/DE41324AFD53/DEBIAN-11/5.10.0-21-AMD64/X86_64/D4ACDF3439>) |
| 8086:5a98 | 02f3:f101 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 6     | snd_hda... | [873AA1A6BB](<Tablet/Digma/EVE/EVE 10 C301T ES1043EW/A789B35F7961/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/873AA1A6BB>) |
| 8086:5a98 | 10ec:11ca | Intel            | Celeron N3350/Pentium N4200/Atom ... | 6     | snd_hda... | [EB1B68E059](<Tablet/Irbis/TW/TW100/73CD97D2A4E1/UBUNTU-22.10/5.19.0-29-GENERIC/X86_64/EB1B68E059>) |
| 8086:5a98 | 8086:5a98 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 6     | snd_hda... | [F8733FFC4D](<Tablet/ZoomSmart/A/A1002/766C759236A3/ROSA-12.3/5.15.79-GENERIC-1ROSA2021.1-X86_64/X86_64/F8733FFC4D>) |
| 8086:9d70 | 1028:06d6 | Intel            | Sunrise Point-LP HD Audio            | 6     | snd_hda... | [C118CA04BC](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/C118CA04BC>) |
| 8086:9d70 | 17aa:2241 | Intel            | Sunrise Point-LP HD Audio            | 6     | snd_hda... | [CC6FE2D666](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/8D924D4AA03C/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/CC6FE2D666>) |
| 8086:9d71 | 17aa:2243 | Intel            | Sunrise Point-LP HD Audio            | 6     | snd_hda... | [149C782883](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCA016JP/4766889E4D51/SIDUCTION-12/6.2.2-3-SIDUCTION-AMD64/X86_64/149C782883>) |
| 8086:02c8 | 17aa:380a | Intel            | Comet Lake PCH-LP cAVS               | 5     | snd_hda... | [2C581034EB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13IML05 82AS/6049DBFEB1C3/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/2C581034EB>) |
| 8086:0a0c | 17aa:3978 | Intel            | Haswell-ULT HD Audio Controller      | 5     | snd_hda... | [69E83BCD80](<Tablet/Lenovo/MIIX/MIIX 2 11 20327/7DF5CB4D666D/ZORIN-16/5.15.0-56-GENERIC/X86_64/69E83BCD80>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9c03 | 1414:9c03 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 97    | ahci       | [27A1A2533B](<Tablet/Microsoft/Surface/Surface Pro 3/CD0693C63FAF/DEBIAN-12/6.1.0-7-AMD64/X86_64/27A1A2533B>) |
| 8086:31e3 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 48    | ahci       | [16D09653EC](<Tablet/VENTURER/WT9/WT9L10C44GD1E/B1E656276267/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/16D09653EC>) |
| 8086:5ae3 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 37    | ahci       | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |
| 1002:4391 | 1025:0577 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 18    | ahci       | [C3D132FB91](<Tablet/Acer/Iconia/Iconia Tab W501/B59AD5DD817B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C3D132FB91>) |
| 8086:0f23 | 1019:99a5 | Intel            | Atom Processor E3800 Series SATA ... | 13    | ahci       | [C35A8D75CE](<Tablet/Intel/powered/powered classmate PC/E3EDE14D59EF/LINUXMINT-20.2/5.4.0-135-GENERIC/X86_64/C35A8D75CE>) |
| 8086:1e03 | 1414:1e03 | Intel            | 7 Series Chipset Family 6-port SA... | 12    | ahci       | [0E56C5B9F7](<Tablet/Microsoft/Surface/Surface with Windows 8 Pro/F2C38254ABB9/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/0E56C5B9F7>) |
| 8086:9d03 | 17aa:384d | Intel            | Sunrise Point-LP SATA Controller ... | 12    | ahci       | [6FF1D34454](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 20M3/154D3B05B100/UBUNTU-20.04/5.15.0-58-GENERIC/X86_64/6FF1D34454>) |
| 8086:9d03 | 144d:c14f | Intel            | Sunrise Point-LP SATA Controller ... | 11    | ahci       | [167229560A](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/KUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/167229560A>) |
| 8086:9c83 | 17aa:222b | Intel            | Wildcat Point-LP SATA Controller ... | 7     | ahci       | [E6190D3469](<Tablet/Lenovo/ThinkPad/ThinkPad Helix 2nd 20CHS0JK00/2C8F871AAAFD/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E6190D3469>) |
| 8086:9d03 | 144d:c135 | Intel            | Sunrise Point-LP SATA Controller ... | 7     | ahci       | [25DEDA3E27](<Tablet/Samsung Electronics/Galaxy/Galaxy TabPro S/A1DD930DF301/UBUNTU-20.04/5.4.0-90-GENERIC/X86_64/25DEDA3E27>) |
| 8086:9d03 | 17aa:383e | Intel            | Sunrise Point-LP SATA Controller ... | 7     | ahci       | [D88BD74ACF](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/B632F2BAF8BF/FEDORA-38/6.2.0-0.RC0.20221221GITB6BB9676F216.10.FC38.X86_64/X86_64/D88BD74ACF>) |
| 8086:0f23 | 1019:99a1 | Intel            | Atom Processor E3800 Series SATA ... | 6     | ahci       | [C61A96D514](<Tablet/Medion/P/P2212T/71C4E4B2F18A/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/C61A96D514>) |
| 8086:5ae3 | 8086:5ae3 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 6     | ahci       | [F8733FFC4D](<Tablet/ZoomSmart/A/A1002/766C759236A3/ROSA-12.3/5.15.79-GENERIC-1ROSA2021.1-X86_64/X86_64/F8733FFC4D>) |
| 8086:9d03 | 1028:06e6 | Intel            | Sunrise Point-LP SATA Controller ... | 6     | ahci       | [C751321AB1](<Tablet/Dell/Latitude/Latitude 5175/725A65699078/FEDORA-36/5.18.18-200.FC36.X86_64/X86_64/C751321AB1>) |
| 8086:9d03 | 8086:9d03 | Intel            | Sunrise Point-LP SATA Controller ... | 6     | ahci       | [F00B37ABE2](<Tablet/RuggedPC/RuggedPadY/RuggedPadY16/172173240BE4/RELS-7.9/4.19.184-1.MPTCP.RES7.X86_64/X86_64/F00B37ABE2>) |
| 8086:31e3 | 8086:31e3 | Intel            | Celeron/Pentium Silver Processor ... | 5     | ahci       | [810D937888](<Tablet/Tactus/GeoPad/GeoPad 110/0F02FAE679C1/ZORIN-16/5.15.0-56-GENERIC/X86_64/810D937888>) |
| 8086:9c03 | 8086:7270 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 5     | ahci       | [69E83BCD80](<Tablet/Lenovo/MIIX/MIIX 2 11 20327/7DF5CB4D666D/ZORIN-16/5.15.0-56-GENERIC/X86_64/69E83BCD80>) |
| 8086:9d03 | 1025:111e | Intel            | Sunrise Point-LP SATA Controller ... | 5     | ahci       | [C9900A8E2F](<Tablet/Acer/Switch/Switch SA5-271P/DFFCE0790341/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C9900A8E2F>) |
| 8086:9d03 | 103c:82ca | Intel            | Sunrise Point-LP SATA Controller ... | 5     | ahci       | [F76DC1B9B7](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/9B3C72E9E186/ARCH-ROLLING/6.2.12-ARCH1-1/X86_64/F76DC1B9B7>) |
| 8086:9d03 | 1028:06d6 | Intel            | Sunrise Point-LP SATA Controller ... | 4     | ahci       | [C118CA04BC](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/C118CA04BC>) |
| 8086:9d03 | 103c:828b | Intel            | Sunrise Point-LP SATA Controller ... | 4     | ahci       | [5A85AB6B0F](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/608A6BF05466/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/5A85AB6B0F>) |
| 8086:9d03 | 17aa:3827 | Intel            | Sunrise Point-LP SATA Controller ... | 4     | ahci       | [D43709B2F7](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/B40E17CB6AAF/UBUNTU-22.10/5.19.0-26-GENERIC/X86_64/D43709B2F7>) |
| 8086:9d03 | 19e5:3e00 | Intel            | Sunrise Point-LP SATA Controller ... | 4     | ahci       | [1DE7D37B18](<Tablet/HUAWEI/MateBook/MateBook HZ-W09/8B29CCECA159/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/1DE7D37B18>) |
| 8086:9d03 | 1028:07a4 | Intel            | Sunrise Point-LP SATA Controller ... | 3     | ahci       | [4E75BEC854](<Tablet/Dell/Latitude/Latitude 5285/4F234F7C7201/UBUNTU-MATE-22.04/5.15.0-46-GENERIC/X86_64/4E75BEC854>) |
| 8086:9d03 | 1028:081d | Intel            | Sunrise Point-LP SATA Controller ... | 3     | ahci       | [88900A37B9](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/172279AB141B/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/88900A37B9>) |
| 8086:9d03 | 1043:1410 | Intel            | Sunrise Point-LP SATA Controller ... | 3     | ahci       | [B945137346](<Tablet/ASUSTek Computer/T305/T305CA/E8B080C97665/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/B945137346>) |
| 8086:9d03 | 17aa:2241 | Intel            | Sunrise Point-LP SATA Controller ... | 3     | ahci       | [6F25E83AF0](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GHS23Y00/84A0B6937CD1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/6F25E83AF0>) |
| 8086:0f23 | 1509:7018 | Intel            | Atom Processor E3800 Series SATA ... | 2     | ahci       | [9347717861](<Tablet/Xplore/iX101/iX101B1/988A604FB8AB/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/9347717861>) |
| 8086:0f23 | 1854:0211 | Intel            | Atom Processor E3800 Series SATA ... | 2     | ahci       | [44AF16AC16](<Tablet/LG Electronics/15U340/15U340-L.BK55P1/96572D02BF5F/LINUXMINT-20/5.4.0-42-GENERIC/X86_64/44AF16AC16>) |
| 8086:0f23 | 8086:7270 | Intel            | Atom Processor E3800 Series SATA ... | 2     | ahci       | [A018825B67](<Tablet/CAKE/POS/POS V3/6B0F662D72A6/UBUNTU-18.04/5.4.0-128-GENERIC/X86_64/A018825B67>) |
| 8086:1e03 | 10f7:8338 | Intel            | 7 Series Chipset Family 6-port SA... | 2     | ahci       | [06F11C0449](<Tablet/Panasonic/FZ-G1/FZ-G1ASH39E3/6F2FB083615E/ELEMENTARY-6/5.11.0-37-GENERIC/X86_64/06F11C0449>) |
| 8086:4dd3 |           | Intel            | Jasper Lake SATA AHCI Controller     | 2     | ahci       | [74D39D268F](<Tablet/RuggedPC/RuggedBookJ/RuggedBookJ87/CA3F17B45E07/MANJARO-21.2.6/5.15.32-1-MANJARO/X86_64/74D39D268F>) |
| 8086:9d03 | 1025:122b | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [46ECB88F1D](<Tablet/Acer/Switch/Switch SW713-51GNP/3C0AE30715BA/NIXOS-22.11/6.1.9/X86_64/46ECB88F1D>) |
| 8086:9d03 | 1043:13c0 | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [4363CA1BD6](<Tablet/ASUSTek Computer/T303/T303UA/C8223D9D63FE/UBUNTU-20.04/5.4.0-33-GENERIC/X86_64/4363CA1BD6>) |
| 8086:9d03 | 1043:16c0 | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [D33E67BDF4](<Tablet/ASUSTek Computer/T304/T304UA/8F97F461C23D/UBUNTU-20.04/5.4.0-29-GENERIC/X86_64/D33E67BDF4>) |
| 8086:9d03 | 17aa:3831 | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [4684DBCC91](<Tablet/Lenovo/MIIX/MIIX 720-12IKB 80VV/E890E1333285/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/4684DBCC91>) |
| 8086:9d03 | 1b0a:01d3 | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [60C93DDC01](<Tablet/Xplore/iX125/iX125R1/9DCB305AD004/PUPPY_IMPPUP64-9.6.1/5.15.11-LXPUP64/X86_64/60C93DDC01>) |
| 1022:7804 | 103c:22ea | AMD              | FCH SATA Controller [AHCI mode]      | 1     | ahci       | [4618D27B09](<Tablet/Zinox Technologies/x64-Based/x64-Based PC/B8682FC1F33D/ZORIN-16/5.15.0-46-GENERIC/X86_64/4618D27B09>) |
| 1b21:0612 | 1b21:1060 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 1     | ahci       | [C24B5A1F84](<Tablet/retsamarret/000/000-F4423-UK000-2000/5D4FAE7FB346/DEBIAN-11/5.10.0-21-AMD64/X86_64/C24B5A1F84>) |
| 1c28:0122 | 1b4b:9183 | Lite-On IT Co... | M6e PCI Express SSD [Marvell 88SS... | 1     | ahci       | [568757F9F8](<Tablet/Dell/Latitude/Latitude 5285/9BC7EC024B34/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/568757F9F8>) |
| 8086:0f23 | 1558:5470 | Intel            | Atom Processor E3800 Series SATA ... | 1     | ahci       | [DD65C5ABF7](<Tablet/Lanix/Neuron/Neuron A/9C81E684C8A4/ARCH-ROLLING/5.8.14-ARCH1-1/X86_64/DD65C5ABF7>) |
| 8086:1e03 | 1b0a:017b | Intel            | 7 Series Chipset Family 6-port SA... | 1     | ahci       | [5A97B2A1A7](<Tablet/Wacom/Citiq/Citiq Companion/47415E406255/LINUXMINT-19.2/5.0.0-27-GENERIC/X86_64/5A97B2A1A7>) |
| 8086:22a3 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | ahci       | [009BEE9446](<Tablet/Intel/Braswell/Braswell Platform/1E35D60EBB32/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/009BEE9446>) |
| 8086:27c1 | 14c0:006c | Intel            | NM10/ICH7 Family SATA Controller ... | 1     | ahci       | [8FF8AE3115](<Tablet/Motion Computing/CL/CL910/CC59C0B6971E/LINUXMINT-19.3/5.4.0-42-GENERIC/I686/8FF8AE3115>) |
| 8086:4dd3 | 8086:7270 | Intel            | Jasper Lake SATA AHCI Controller     | 1     | ahci       | [C24B5A1F84](<Tablet/retsamarret/000/000-F4423-UK000-2000/5D4FAE7FB346/DEBIAN-11/5.10.0-21-AMD64/X86_64/C24B5A1F84>) |
| 8086:5ae3 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | ahci       | [49D345EC0B](<Tablet/Xplore/iX101/iX101L1/1592B2F5F479/UBUNTU-20.04/5.6.0-1028-OEM/X86_64/49D345EC0B>) |
| 8086:9d03 | 1028:0702 | Intel            | Sunrise Point-LP SATA Controller ... | 1     | ahci       | [CE9A3F2C74](<Tablet/Dell/XPS/XPS 12 9250/A04CD2743A76/CLEAR-LINUX-OS-35400/5.15.7-1106.NATIVE/X86_64/CE9A3F2C74>) |
| 8086:9d03 | 103c:8414 | Intel            | Sunrise Point-LP SATA Controller ... | 1     | ahci       | [6EE77ED959](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/3DD573867AA0/UBUNTU-20.04/5.8.0-36-GENERIC/X86_64/6EE77ED959>) |
| 8086:9d03 | 10f7:8338 | Intel            | Sunrise Point-LP SATA Controller ... | 1     | ahci       | [94539C6DB9](<Tablet/Panasonic/CF-33/CF-33-1/AE1D638EDC9E/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/94539C6DB9>) |
| 8086:9d03 | 17aa:2243 | Intel            | Sunrise Point-LP SATA Controller ... | 1     | ahci       | [BDB2F1C4AD](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCS1470B/5437FDE37124/FEDORA-35/5.17.4-200.FC35.X86_64/X86_64/BDB2F1C4AD>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c01 | 10f7:8338 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ata_piix   | [50E0A85FD3](<Tablet/Panasonic/CF-H2/CF-H2BJJHZDE/E17482358B17/LMDE-5/5.10.0-13-AMD64/X86_64/50E0A85FD3>) |
| 8086:1c09 | 10f7:8338 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ata_piix   | [50E0A85FD3](<Tablet/Panasonic/CF-H2/CF-H2BJJHZDE/E17482358B17/LMDE-5/5.10.0-13-AMD64/X86_64/50E0A85FD3>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 98    | nvme       | [7FD9FD4619](<Tablet/Microsoft/Surface/Surface Pro 4/11BB44FDB753/POP!_OS-22.04/6.2.14-SURFACE/X86_64/7FD9FD4619>) |
| 1c5c:1327 | 1c5c:0000 | SK hynix         | BC501 NVMe Solid State Drive         | 84    | nvme       | [FD7A2486F2](<Tablet/Microsoft/Surface/Surface Laptop Go/83C5E1166CAF/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/FD7A2486F2>) |
| 1179:0113 | 1179:0001 | Toshiba Ameri... | BG3 NVMe SSD Controller              | 70    | nvme       | [8B89FFD983](<Tablet/Microsoft/Surface/Surface Pro/40EF290D863C/ZORIN-16/5.15.0-71-GENERIC/X86_64/8B89FFD983>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 60    | nvme       | [2FB43E55C2](<Tablet/Microsoft/Surface/Surface Pro 4/5359C2968C9C/KDE-NEON-22.04/5.19.0-32-GENERIC/X86_64/2FB43E55C2>) |
| 1e0f:0001 | 1e0f:0001 | KIOXIA           | NVMe SSD Controller BG4              | 50    | nvme       | [7C8D87170F](<Tablet/Microsoft/Surface/Surface Pro 7/FDDF58D50F30/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/7C8D87170F>) |
| 144d:a806 | 144d:a801 | Samsung Elect... | Surface NVMe Controller              | 39    | nvme       | [0332AF656C](<Tablet/Microsoft/Surface/Surface Pro/F1C987F0D508/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/0332AF656C>) |
| 1179:010f | 1179:0001 | Toshiba Ameri... | NVMe Controller                      | 20    | nvme       | [CC6FE2D666](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/8D924D4AA03C/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/CC6FE2D666>) |
| 1179:0116 | 1179:0001 | Toshiba Ameri... | XG5 NVMe SSD Controller              | 14    | nvme       | [6ECC8F0BAD](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/7A82B39E3BAF/FEDORA-37/6.1.15-200.FC37.X86_64/X86_64/6ECC8F0BAD>) |
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 14    | nvme       | [1840C57073](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/96D5F5EB923F/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/1840C57073>) |
| 1c5c:1527 | 1c5c:1527 | SK hynix         | PC401 NVMe Solid State Drive 256GB   | 14    | nvme       | [5A5E168C99](<Tablet/Microsoft/Surface/Surface Book 2/E6819C0E6E6D/KALI-2023.1/6.2.10-SURFACE/X86_64/5A5E168C99>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980              | 13    | nvme       | [E49682836A](<Tablet/Microsoft/Surface/Surface Laptop Go/1E7E9BBF3B2A/ENDEAVOUROS-ROLLING/6.2.13-ARCH1-2-SURFACE/X86_64/E49682836A>) |
| 8086:f1a5 | 8086:390a | Intel            | SSD 600P Series                      | 11    | nvme       | [56C75F9229](<Tablet/Microsoft/Surface/Surface Pro/30C30BAC02B4/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/56C75F9229>) |
| 15b7:5007 | 15b7:5007 | SanDisk          | Non-Volatile memory controller       | 9     | nvme       | [E5644591DE](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZC_GZ301ZC/D9321FF7F56A/FEDORA-37/6.2.8-300.FC37.X86_64/X86_64/E5644591DE>) |
| 1c5c:174a | 1c5c:174a | SK hynix         | Gold P31/PC711 NVMe Solid State D... | 8     | nvme       | [89ADCCAE04](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UVS1RL00/ECF244BC1E85/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/89ADCCAE04>) |
| 1344:5411 | 1344:2100 | Micron Techno... | NVMe Storage Controller              | 7     | nvme       | [6049494197](<Tablet/Dell/XPS/XPS 13 9315 2-in-1/1EF842C3A2C1/UBUNTU-22.04/6.1.0-1007-OEM/X86_64/6049494197>) |
| 1179:011a | 1179:0001 | Toshiba Ameri... | XG6 NVMe SSD Controller              | 5     | nvme       | [3A14639664](<Tablet/Microsoft/Surface/Surface Book 3/E34BE71769BC/UBUNTU-22.10/6.1.13-SURFACE/X86_64/3A14639664>) |
| 15b7:5008 | 15b7:5008 | SanDisk          | NVMe Controller                      | 5     | nvme       | [0FB09C29CB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/BE6A61880EF2/LINUXMINT-20.3/5.19.0-35-GENERIC/X86_64/0FB09C29CB>) |
| 15b7:5009 | 15b7:5009 | SanDisk          | WD Blue SN550 NVMe SSD               | 4     | nvme       | [C039BD54B8](<Tablet/AYADEVICE/AYA/AYA NEO FOUNDER/49BCDD789BF3/ARCH-ROLLING/5.14.11-ARCH1-1/X86_64/C039BD54B8>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013 E13 NVMe Controller           | 4     | nvme       | [B598F4182C](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/3619386421C4/POP!_OS-22.04/6.0.12-76060006-GENERIC/X86_64/B598F4182C>) |
| 1dee:5216 | 1dee:5216 | Biwin Storage... | Non-Volatile memory controller       | 4     | nvme       | [FE54ACC90F](<Tablet/AOKZOE/A1/A1 AR07/AD925682010C/STEAMOS-3.4/6.1.1-VALVE1-1-NEPTUNE-61/X86_64/FE54ACC90F>) |
| 8086:f1a6 | 8086:390b | Intel            | SSD Pro 7600p/760p/E 6100p Series    | 4     | nvme       | [ABA0D29DD8](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJ001NFR/32F606BCA186/UBUNTU-22.10/5.19.0-29-GENERIC/X86_64/ABA0D29DD8>) |
| 126f:1001 | 126f:2262 | Silicon Motion   | Non-Volatile memory controller       | 3     | nvme       | [F348E93361](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/4B50F0906809/UBUNTU-22.10/6.1.4-060104-GENERIC/X86_64/F348E93361>) |
| 15b7:5004 | 15b7:5004 | SanDisk          | PC SN520 NVMe SSD                    | 3     | nvme       | [169454762C](<Tablet/Hewlett-Packard/Tablet/Tablet 11m-be0xxx/535A9A46FE41/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/169454762C>) |
| 1e95:3500 | 1b4b:1092 | Solid State S... | Non-Volatile memory controller       | 3     | nvme       | [2A05772CB6](<Tablet/Getac/F110/F110G6/36F31BBCD939/RELD-7.9/5.15.33-1.RES7.X86_64/X86_64/2A05772CB6>) |
| 1179:0115 | 1179:0001 | Toshiba Ameri... | XG4 NVMe SSD Controller              | 2     | nvme       | [6CE5523274](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/D39789DC846A/UBUNTU-20.10/5.8.0-41-GENERIC/X86_64/6CE5523274>) |
| 15b7:5003 | 15b7:5003 | SanDisk          | WD Blue SN500 / PC SN520 NVMe SSD    | 2     | nvme       | [7D44E4C760](<Tablet/Acer/Switch/Switch SW512-52/9061A4CB688E/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/7D44E4C760>) |
| 15b7:501a | 15b7:501a | SanDisk          | WD Blue SN570 NVMe SSD               | 2     | nvme       | [3C50D5D61C](<Tablet/Microsoft/Surface/Surface Pro 8/C4CEE7E26DF5/MANJARO/6.2.12-ARCH1-1-SURFACE/X86_64/3C50D5D61C>) |
| 17aa:0003 | 17aa:1003 | Lenovo           | Non-Volatile memory controller       | 2     | nvme       | [149C782883](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCA016JP/4766889E4D51/SIDUCTION-12/6.2.2-3-SIDUCTION-AMD64/X86_64/149C782883>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 2     | nvme       | [D47AC58E2B](<Tablet/Dell/Latitude/Latitude 5175/AE5B4A894C5E/DEBIAN-10/5.10.0-8MX-AMD64/X86_64/D47AC58E2B>) |
| 1cc4:6201 | 1cc4:1cc4 | Union Memory ... | Non-Volatile memory controller       | 2     | nvme       | [ED4AEB2282](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 5 12IAU7 82TQ/75AEF6B37790/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/ED4AEB2282>) |
| 2646:500f | 2646:500f | Kingston Tech... | NVMe Controller                      | 2     | nvme       | [9BEC9E1625](<Tablet/ONE-NETBOOK TECHNOLOGY/ONE/ONE XPLAYER/CE6599010102/CHIMERAOS-35/5.19.6-ARCH1-1/X86_64/9BEC9E1625>) |
| 126f:2262 | 126f:2262 | Silicon Motion   | SM2262/SM2262EN SSD Controller       | 1     | nvme       | [12B2EDE47C](<Tablet/AYANEO/NEXT/NEXT Pro/6CADB80BD4FB/STEAMOS-3.2 (STEAMDECK-MAIN)/5.13.0-VALVE10.1-2-NEPTUNE-DRI-02144-G7FFFAF925DFB/X86_64/12B2EDE47C>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT SSD Controller     | 1     | nvme       | [A5E36506B9](<Tablet/AYANEO/AIR/AIR/9436EABA7EC5/BUILDROOT-2022.08.1/5.19.8/X86_64/A5E36506B9>) |
| 1344:5410 | 1344:0100 | Micron Techno... | NVMe Storage Controller              | 1     | nvme       | [1ABEA9314A](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/9C5DA16E7FE7/POP!_OS-20.10/5.11.0-7614-GENERIC/X86_64/1ABEA9314A>) |
| 1344:5411 | 1344:1100 | Micron Techno... | NVMe Storage Controller              | 1     | nvme       | [C0C3232FAD](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZC_GZ301ZC/4550248EB59F/UBUNTU-22.04/5.15.0-46-GENERIC/X86_64/C0C3232FAD>) |
| 15b7:5006 | 15b7:5006 | SanDisk          | WD Black SN750 / PC SN730 NVMe SSD   | 1     | nvme       | [09F8C72D80](<Tablet/Hewlett-Packard/Elite/Elite x2 G4/0472416698D9/UBUNTU-21.04/5.11.0-25-GENERIC/X86_64/09F8C72D80>) |
| 15b7:5015 | 15b7:5015 | Sandisk          | Non-Volatile memory controller       | 1     | nvme       | [679DC6CBC8](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301VV_GZ301VV/7B1518D4CC86/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/679DC6CBC8>) |
| 15b7:5019 | 15b7:5019 | SanDisk          | Non-Volatile memory controller       | 1     | nvme       | [C24B5A1F84](<Tablet/retsamarret/000/000-F4423-UK000-2000/5D4FAE7FB346/DEBIAN-11/5.10.0-21-AMD64/X86_64/C24B5A1F84>) |
| 15b7:5026 | 15b7:5026 | Sandisk          | Non-Volatile memory controller       | 1     | nvme       | [DEE13EAC1D](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZE_GZ301ZE/81FF0FC471FE/ARCH-ROLLING/5.15.74-1-LTS/X86_64/DEE13EAC1D>) |
| 1987:5019 | 1987:5019 | Phison Electr... | Electronics Non-Volatile memory c... | 1     | nvme       | [672B480B96](<Tablet/AYANEO/2/2/4246C8CCCDD5/CHIMERAOS-41/6.1.21-1-LTS/X86_64/672B480B96>) |
| 1987:5021 | 1987:5021 | Phison Electr... | Electronics Non-Volatile memory c... | 1     | nvme       | [840F96A7DF](<Tablet/Microsoft/Surface/Surface Pro 8/4618AEDA291D/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.9-1-DEFAULT/X86_64/840F96A7DF>) |
| 1c5c:1283 | 1c5c:0000 | SK hynix         | PC300 NVMe Solid State Drive 256GB   | 1     | nvme       | [71F48F75D2](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/E23B3AA76824/POP!_OS-20.04/5.4.0-7642-GENERIC/X86_64/71F48F75D2>) |
| 1c5c:1339 | 1c5c:0000 | SK hynix         | BC511                                | 1     | nvme       | [4BFF3B131D](<Tablet/Microsoft/Surface/Surface Laptop 4/EC858985CDD3/ARCH-ROLLING/6.0.3-ARCH1-1-SURFACE/X86_64/4BFF3B131D>) |
| 1c5c:1739 | 1c5c:1739 | SK hynix         | Non-Volatile memory controller       | 1     | nvme       | [25909CF566](<Tablet/Microsoft/Surface/Surface Laptop Go/8F51C51A1339/UBUNTU-20.04/5.13.0-44-GENERIC/X86_64/25909CF566>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 1     | nvme       | [D43709B2F7](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/B40E17CB6AAF/UBUNTU-22.10/5.19.0-26-GENERIC/X86_64/D43709B2F7>) |
| 1cc4:6202 | 1cc4:1cc4 | Union Memory ... | Non-Volatile memory controller       | 1     | nvme       | [2C581034EB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13IML05 82AS/6049DBFEB1C3/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/2C581034EB>) |
| 1cc4:6203 | 1cc4:1cc4 | Union Memory ... | Non-Volatile memory controller       | 1     | nvme       | [63EAB4A6B5](<Tablet/Lenovo/Yoga/Yoga Duet IML 2020 82E9/8FFE2F20194E/ARCH/5.18.0-ARCH1-1/X86_64/63EAB4A6B5>) |
| 1cc4:6204 | 1cc4:1cc4 | Union Memory ... | Non-Volatile memory controller       | 1     | nvme       | [6F0E0FCC43](<Tablet/Lenovo/Yoga/Yoga Duet 7 13IML05 82AS/53D01D6A216A/UBUNTU-20.10/5.8.0-50-GENERIC/X86_64/6F0E0FCC43>) |
| 1d97:1602 | 1d97:1602 | Shenzhen Long... | Non-Volatile memory controller       | 1     | nvme       | [4DB5D91519](<Tablet/AYANEO/2/2/B4D86F481CC0/CHIMERAOS-41/6.1.21-1-LTS/X86_64/4DB5D91519>) |
| 1e0f:000c | 1e0f:0001 | KIOXIA           | Non-Volatile memory controller       | 1     | nvme       | [44D3B06704](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 5 12IAU7 82TQ/C6D3824DB7FE/POP!_OS-22.04/6.0.12-76060006-GENERIC/X86_64/44D3B06704>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:467f | 8086:0000 | Intel            | Volume Management Device NVMe RAI... | 9     | vmd        | [E5644591DE](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZC_GZ301ZC/D9321FF7F56A/FEDORA-37/6.2.8-300.FC37.X86_64/X86_64/E5644591DE>) |
| 8086:282a | 1025:1171 | Intel            | 82801 Mobile SATA Controller [RAI... | 3     | ahci       | [7D44E4C760](<Tablet/Acer/Switch/Switch SW512-52/9061A4CB688E/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/7D44E4C760>) |
| 8086:9a0b | 1028:0a45 | Intel            | Volume Management Device NVMe RAI... | 3     | vmd        | [5F1B339A57](<Tablet/Dell/Latitude/Latitude 7320 Detachable/3152C9CEBBAA/UBUNTU-MATE-22.04/5.15.0-40-GENERIC/X86_64/5F1B339A57>) |
| 8086:282a | 1028:07a4 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [1717754347](<Tablet/Dell/Latitude/Latitude 5285/D75F67E269AD/UBUNTU-22.10/5.19.10-SURFACE/X86_64/1717754347>) |
| 8086:282a | 17aa:3831 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [67E1BDD5F1](<Tablet/Lenovo/MIIX/MIIX 720-12IKB 80VV/F45F8CE4052D/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/67E1BDD5F1>) |
| 8086:282a | 8086:9d03 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [0F05F12004](<Tablet/Teclast/X5/X5 Pro/B130987D6E6A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0F05F12004>) |
| 8086:467f | 1028:0b34 | Intel            | Volume Management Device NVMe RAI... | 1     | ahci, vmd  | [6049494197](<Tablet/Dell/XPS/XPS 13 9315 2-in-1/1EF842C3A2C1/UBUNTU-22.04/6.1.0-1007-OEM/X86_64/6049494197>) |
| 8086:9a0b | 103c:870d | Intel            | Volume Management Device NVMe RAI... | 1     | vmd        | [D6BA8E665C](<Tablet/Hewlett-Packard/Elite/Elite x2 G8 Tablet/6D7618F54734/UBUNTU-21.10/5.13.0-40-GENERIC/X86_64/D6BA8E665C>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1911 | 8086:2015 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 124   |            | [7FD9FD4619](<Tablet/Microsoft/Surface/Surface Pro 4/11BB44FDB753/POP!_OS-22.04/6.2.14-SURFACE/X86_64/7FD9FD4619>) |
| 8086:09ab |           | Intel            | RST VMD Managed Controller           | 14    |            | [E5644591DE](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZC_GZ301ZC/D9321FF7F56A/FEDORA-37/6.2.8-300.FC37.X86_64/X86_64/E5644591DE>) |
| 8086:3190 | 17aa:3802 | Intel            | Celeron/Pentium Silver Processor ... | 13    |            | [42DA57CF53](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGL 82H0/66D15DFB427C/UBUNTU-20.04/5.15.0-52-GENERIC/X86_64/42DA57CF53>) |
| 8086:1911 | 17aa:2244 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 12    |            | [ABA0D29DD8](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJ001NFR/32F606BCA186/UBUNTU-22.10/5.19.0-29-GENERIC/X86_64/ABA0D29DD8>) |
| 8086:464f | 1043:1c42 | Intel            | 12th Gen Core Processor Gaussian ... | 9     |            | [E5644591DE](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZC_GZ301ZC/D9321FF7F56A/FEDORA-37/6.2.8-300.FC37.X86_64/X86_64/E5644591DE>) |
| 8086:15d2 | 2222:1111 | Intel            | JHL6540 Thunderbolt 3 NHI (C step... | 7     | thunder... | [ABA0D29DD8](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJ001NFR/32F606BCA186/UBUNTU-22.10/5.19.0-29-GENERIC/X86_64/ABA0D29DD8>) |
| 8086:1911 | 8086:1911 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 7     |            | [0F05F12004](<Tablet/Teclast/X5/X5 Pro/B130987D6E6A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0F05F12004>) |
| 8086:9a11 | 17aa:382f | Intel            | GNA Scoring Accelerator module       | 7     |            | [5C0467F4CB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/FA8378B128F2/ZORIN-16/5.15.0-69-GENERIC/X86_64/5C0467F4CB>) |
| 8086:1911 | 17aa:2241 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 6     |            | [CC6FE2D666](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/8D924D4AA03C/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/CC6FE2D666>) |
| 8086:1911 | 17aa:2243 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 6     |            | [149C782883](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCA016JP/4766889E4D51/SIDUCTION-12/6.2.2-3-SIDUCTION-AMD64/X86_64/149C782883>) |
| 8086:3190 | 17aa:380e | Intel            | Celeron/Pentium Silver Processor ... | 6     |            | [C81361E795](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 10IGL5 82AT/605931C0A403/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/C81361E795>) |
| 8086:15d2 | 103c:8414 | Intel            | JHL6540 Thunderbolt 3 NHI (C step... | 5     | thunder... | [E8D1866113](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/AC04F34CD8CA/DEBIAN/6.0.0-5-AMD64/X86_64/E8D1866113>) |
| 8086:1911 | 17aa:3883 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 5     |            | [2C581034EB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13IML05 82AS/6049DBFEB1C3/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/2C581034EB>) |
| 8086:9a11 | 1028:0a45 | Intel            | GNA Scoring Accelerator module       | 5     |            | [5E287BBD8B](<Tablet/Dell/Latitude/Latitude 7320 Detachable/089CE6269F10/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/5E287BBD8B>) |
| 8086:9a11 | 17aa:508b | Intel            | GNA Scoring Accelerator module       | 5     |            | [89ADCCAE04](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UVS1RL00/ECF244BC1E85/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/89ADCCAE04>) |
| 8086:15eb | 1028:09ba | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 3     | thunder... | [2DE1D6F6F5](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/7A5FB94B1DE2/ARCH-ROLLING/6.2.12-ZEN1-1-ZEN/X86_64/2DE1D6F6F5>) |
| 8086:15eb | 103c:85b9 | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 3     | thunder... | [D49CBA4016](<Tablet/Hewlett-Packard/Elite/Elite x2 G4/D4F39DF208E2/LINUXMINT-21.1/6.0.0-1012-OEM/X86_64/D49CBA4016>) |
| 8086:1911 | 1028:09ba | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 3     |            | [2DE1D6F6F5](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/7A5FB94B1DE2/ARCH-ROLLING/6.2.12-ZEN1-1-ZEN/X86_64/2DE1D6F6F5>) |
| 8086:3190 | 17aa:2261 | Intel            | Celeron/Pentium Silver Processor ... | 3     |            | [05EDD845DF](<Tablet/Lenovo/Tablet/Tablet 10 20L3000KGE/7130A0BB6850/UBUNTU-22.10/5.19.0-40-GENERIC/X86_64/05EDD845DF>) |
| 8086:464f | 17aa:3839 | Intel            | 12th Gen Core Processor Gaussian ... | 3     |            | [ED4AEB2282](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 5 12IAU7 82TQ/75AEF6B37790/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/ED4AEB2282>) |
| 8086:1911 | 1b0a:01d3 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [60C93DDC01](<Tablet/Xplore/iX125/iX125R1/9DCB305AD004/PUPPY_IMPPUP64-9.6.1/5.15.11-LXPUP64/X86_64/60C93DDC01>) |
| 8086:1193 |           | Intel            | System peripheral                    | 1     |            | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:1194 |           | Intel            | Merrifield Serial IO SPI Controller  | 1     | intel_m... | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:1199 |           | Intel            | Merrifield GPIO Controller           | 1     | langwel... | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:119b |           | Intel            | System peripheral                    | 1     | intel_m... | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:11a2 |           | Intel            | Merrifield Serial IO DMA Controller  | 1     | intel_m... | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:11a5 |           | Intel            | Merrifield Serial IO PWM Controller  | 1     | pwm_int... | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:15d2 | 1028:08e9 | Intel            | JHL6540 Thunderbolt 3 NHI (C step... | 1     | thunder... | [2DD1504CF8](<Tablet/Dell/Latitude/Latitude 7200 2-in-1/420B18298724/UBUNTU-20.04/5.8.0-43-GENERIC/X86_64/2DD1504CF8>) |
| 8086:1911 | 1028:08e9 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [2DD1504CF8](<Tablet/Dell/Latitude/Latitude 7200 2-in-1/420B18298724/UBUNTU-20.04/5.8.0-43-GENERIC/X86_64/2DD1504CF8>) |
| 8086:464f | 1028:0b34 | Intel            | 12th Gen Core Processor Gaussian ... | 1     |            | [6049494197](<Tablet/Dell/XPS/XPS 13 9315 2-in-1/1EF842C3A2C1/UBUNTU-22.04/6.1.0-1007-OEM/X86_64/6049494197>) |
| 8086:4e11 | 1043:1d02 | Intel            | Jasper Lake System Peripheral        | 1     |            | [CF1735BF9E](<Tablet/ASUSTek Computer/Vivobook/Vivobook Slate T3300KA_T3300KA/CB77B9CC66FB/ELEMENTARY-6.1/5.15.0-50-GENERIC/X86_64/CF1735BF9E>) |
| 8086:4e11 | 8086:7270 | Intel            | Jasper Lake System Peripheral        | 1     |            | [C24B5A1F84](<Tablet/retsamarret/000/000-F4423-UK000-2000/5D4FAE7FB346/DEBIAN-11/5.10.0-21-AMD64/X86_64/C24B5A1F84>) |
| 8086:9a11 | 103c:870d | Intel            | GNA Scoring Accelerator module       | 1     |            | [D6BA8E665C](<Tablet/Hewlett-Packard/Elite/Elite x2 G8 Tablet/6D7618F54734/UBUNTU-21.10/5.13.0-40-GENERIC/X86_64/D6BA8E665C>) |
| 8086:a74f | 1043:1573 | Intel            | Core i9/i7/i5/i3 GNA Scoring Acce... | 1     |            | [679DC6CBC8](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301VV_GZ301VV/7B1518D4CC86/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/679DC6CBC8>) |

### Unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:31a2 | 17aa:2261 | Intel            | Celeron/Pentium Silver Processor ... | 3     | intel_i... | [05EDD845DF](<Tablet/Lenovo/Tablet/Tablet 10 20L3000KGE/7130A0BB6850/UBUNTU-22.10/5.19.0-40-GENERIC/X86_64/05EDD845DF>) |
| 8086:31a2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 2     | intel_i... | [D476F875D2](<Tablet/Teclast/X6/X6 plus/D578D72C0F87/UBUNTU-BUDGIE-21.10/5.13.0-19-GENERIC/X86_64/D476F875D2>) |
| 8086:1aa2 | 8086:7270 | Intel            | Integrated Sensor Solution           | 1     | intel_i... | [555A26F0D1](<Tablet/Intel/570x/570x DVT3/469D9CAF87D4/UBUNTU-CORE-20/5.4.0-62-GENERIC/X86_64/555A26F0D1>) |
| 8086:5aa2 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | intel_i... | [49D345EC0B](<Tablet/Xplore/iX101/iX101L1/1592B2F5F479/UBUNTU-20.04/5.6.0-1028-OEM/X86_64/49D345EC0B>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d2f | 8086:7270 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 270   | xhci_hcd   | [0332AF656C](<Tablet/Microsoft/Surface/Surface Pro/F1C987F0D508/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/0332AF656C>) |
| 8086:22b5 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 165   | xhci_hcd   | [40D1BBA9E2](<Tablet/Hampoo/I1/I1D6_C109S_Hi10Pro/8F753D037AF0/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/40D1BBA9E2>) |
| 8086:9c31 | 1414:9c31 | Intel            | 8 Series USB xHCI HC                 | 98    | xhci_hcd   | [27A1A2533B](<Tablet/Microsoft/Surface/Surface Pro 3/CD0693C63FAF/DEBIAN-12/6.1.0-7-AMD64/X86_64/27A1A2533B>) |
| 8086:34ed | 8086:7270 | Intel            | Ice Lake-LP USB 3.1 xHCI Host Con... | 92    | xhci_pci   | [FD7A2486F2](<Tablet/Microsoft/Surface/Surface Laptop Go/83C5E1166CAF/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/FD7A2486F2>) |
| 8086:8a13 |           | Intel            | Ice Lake Thunderbolt 3 USB Contro... | 92    | xhci_pci   | [FD7A2486F2](<Tablet/Microsoft/Surface/Surface Laptop Go/83C5E1166CAF/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/FD7A2486F2>) |
| 8086:22b5 | 17aa:380b | Intel            | Atom/Celeron/Pentium Processor x5... | 62    | xhci_hcd   | [5B5EBA537A](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/E141169A4B3D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/5B5EBA537A>) |
| 8086:22b5 | 17aa:3806 | Intel            | Atom/Celeron/Pentium Processor x5... | 53    | xhci_hcd   | [3F12350D47](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/2E38E9723355/POP!_OS-21.04/5.15.5-76051505-GENERIC/X86_64/3F12350D47>) |
| 8086:22b7 | 8086:7270 | Intel            | USB Synopsys Controller              | 44    | dwc3_pci   | [40D1BBA9E2](<Tablet/Hampoo/I1/I1D6_C109S_Hi10Pro/8F753D037AF0/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/40D1BBA9E2>) |
| 8086:31a8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 41    | xhci_pci   | [AD63D006B6](<Tablet/Chuwi/Hi10/Hi10 XR/75B0305701C2/KDE-NEON-22.04/5.19.0-38-GENERIC/X86_64/AD63D006B6>) |
| 8086:0f35 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 39    | xhci_hcd   | [1133B0413B](<Tablet/Lenovo/ThinkPad/ThinkPad 10 20C1002PUK/FDCBFB580589/ARCH-ROLLING/6.2.10-ARCH1-1/X86_64/1133B0413B>) |
| 8086:5aa8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 37    | xhci_pci   | [745BABB415](<Tablet/MicroByte/ezpad/ezpad/11DA1020AF59/DEBIAN-11/5.10.0-21-AMD64/X86_64/745BABB415>) |
| 8086:9d2f | 152d:1182 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 37    | xhci_pci   | [38C117EE87](<Tablet/Microsoft/Surface/Surface Go/09E0163388C3/MANJARO/6.1.25-1-MANJARO/X86_64/38C117EE87>) |
| 8086:22b5 | 1043:13a0 | Intel            | Atom/Celeron/Pentium Processor x5... | 32    | xhci_hcd   | [60962892BC](<Tablet/ASUSTek Computer/T101/T101HA/5F2FAE88E834/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/60962892BC>) |
| 8086:22b5 |           | Intel            | Atom/Celeron/Pentium Processor x5... | 25    | xhci_hcd   | [140992E52D](<Tablet/Acer/One/One S1003/B46527D9300A/ARCH-ROLLING/6.1.8-ARCH1-1/X86_64/140992E52D>) |
| 8086:22b5 | 103c:827c | Intel            | Atom/Celeron/Pentium Processor x5... | 24    | xhci_hcd   | [815D54B61B](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/E1DE173C5065/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/815D54B61B>) |
| 8086:22b5 | 1043:1400 | Intel            | Atom/Celeron/Pentium Processor x5... | 21    | xhci_pci   | [3EC331DA1F](<Tablet/ASUSTek Computer/T102/T102HA/2F5B8C8AE51D/FEDORA-36/5.18.10-200.FC36.X86_64/X86_64/3EC331DA1F>) |
| 8086:9d2f | 103c:82ca | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 21    | xhci_hcd   | [F76DC1B9B7](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/9B3C72E9E186/ARCH-ROLLING/6.2.12-ARCH1-1/X86_64/F76DC1B9B7>) |
| 8086:22b7 | 17aa:380a | Intel            | USB Synopsys Controller              | 20    | dwc3_pci   | [3F12350D47](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/2E38E9723355/POP!_OS-21.04/5.15.5-76051505-GENERIC/X86_64/3F12350D47>) |
| 8086:9c26 | 1414:9c26 | Intel            | 8 Series USB EHCI #1                 | 19    | ehci_pci   | [3237FF6784](<Tablet/Microsoft/Surface/Surface Pro 2/7DF1C7B40ADE/ELEMENTARY-6.1/5.15.0-56-GENERIC/X86_64/3237FF6784>) |
| 1002:4396 | 1025:0577 | AMD              | SB7x0/SB8x0/SB9x0 USB EHCI Contro... | 18    | ehci_hc... | [C3D132FB91](<Tablet/Acer/Iconia/Iconia Tab W501/B59AD5DD817B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C3D132FB91>) |
| 1002:4397 | 1025:0577 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI0 Contr... | 18    | ohci_hc... | [C3D132FB91](<Tablet/Acer/Iconia/Iconia Tab W501/B59AD5DD817B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C3D132FB91>) |
| 8086:31a8 | 17aa:3812 | Intel            | Celeron/Pentium Silver Processor ... | 13    | xhci_hcd   | [42DA57CF53](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGL 82H0/66D15DFB427C/UBUNTU-20.04/5.15.0-52-GENERIC/X86_64/42DA57CF53>) |
| 8086:9a13 | 8086:7270 | Intel            | Tiger Lake-LP Thunderbolt 4 USB C... | 13    | xhci_hcd   | [3C50D5D61C](<Tablet/Microsoft/Surface/Surface Pro 8/C4CEE7E26DF5/MANJARO/6.2.12-ARCH1-1-SURFACE/X86_64/3C50D5D61C>) |
| 8086:9a1b | 2222:1111 | Intel            | Tiger Lake-LP Thunderbolt 4 NHI #0   | 13    | thunder... | [5C0467F4CB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/FA8378B128F2/ZORIN-16/5.15.0-69-GENERIC/X86_64/5C0467F4CB>) |
| 8086:a0ed | 8086:7270 | Intel            | Tiger Lake-LP USB 3.2 Gen 2x1 xHC... | 13    | xhci_hcd   | [3C50D5D61C](<Tablet/Microsoft/Surface/Surface Pro 8/C4CEE7E26DF5/MANJARO/6.2.12-ARCH1-1-SURFACE/X86_64/3C50D5D61C>) |
| 8086:0f35 | 1019:99a5 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 12    | xhci_hcd   | [61790801C2](<Tablet/Intel/powered/powered classmate PC/92E9A98C551E/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/61790801C2>) |
| 8086:15d4 | 2222:1111 | Intel            | JHL6540 Thunderbolt 3 USB Control... | 12    | xhci_hcd   | [F2799F616C](<Tablet/Hewlett-Packard/ZBook/ZBook x2 G4/3743B487B588/ARCH-ROLLING/5.15.79-1-LTS/X86_64/F2799F616C>) |
| 8086:1e26 | 1414:1e26 | Intel            | 7 Series/C216 Chipset Family USB ... | 12    | ehci_pci   | [0E56C5B9F7](<Tablet/Microsoft/Surface/Surface with Windows 8 Pro/F2C38254ABB9/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/0E56C5B9F7>) |
| 8086:1e2d | 1414:1e2d | Intel            | 7 Series/C216 Chipset Family USB ... | 12    | ehci_pci   | [0E56C5B9F7](<Tablet/Microsoft/Surface/Surface with Windows 8 Pro/F2C38254ABB9/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/0E56C5B9F7>) |
| 8086:1e31 | 1414:1e31 | Intel            | 7 Series/C210 Series Chipset Fami... | 12    | xhci_hcd   | [0E56C5B9F7](<Tablet/Microsoft/Surface/Surface with Windows 8 Pro/F2C38254ABB9/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/0E56C5B9F7>) |
| 8086:9d2f | 152d:1237 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 12    | xhci_pci   | [EDCDEDD65A](<Tablet/Microsoft/Surface/Surface Go 2/5B20BDF3E76F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/EDCDEDD65A>) |
| 8086:9d2f | 17aa:2244 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 12    | xhci_hcd   | [ABA0D29DD8](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJ001NFR/32F606BCA186/UBUNTU-22.10/5.19.0-29-GENERIC/X86_64/ABA0D29DD8>) |
| 8086:9d2f | 17aa:3851 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 12    | xhci_hcd   | [6FF1D34454](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 20M3/154D3B05B100/UBUNTU-20.04/5.15.0-58-GENERIC/X86_64/6FF1D34454>) |
| 8086:0f35 | 103c:815d | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 11    | xhci_hcd   | [EC3A161D36](<Tablet/Hewlett-Packard/Pavilion/Pavilion x2 Detachable/ACF95D095277/FEDORA-38/6.2.7-300.FC38.X86_64/X86_64/EC3A161D36>) |
| 8086:9d2f | 144d:c14f | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 11    | xhci_hcd   | [167229560A](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/KUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/167229560A>) |
| 1022:1639 | 1022:1639 | AMD              | Renoir/Cezanne USB 3.1               | 10    | xhci_hcd   | [D721C7AE17](<Tablet/ONE-NETBOOK TECHNOLOGY/ONE/ONE XPLAYER/B9BDBF250081/CHIMERAOS-37/6.0.8-ARCH1-1/X86_64/D721C7AE17>) |
| 8086:51ed | 1043:201f | Intel            | Alder Lake PCH USB 3.2 xHCI Host ... | 10    | xhci_pci   | [679DC6CBC8](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301VV_GZ301VV/7B1518D4CC86/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/679DC6CBC8>) |
| 8086:22b5 | 103c:82f4 | Intel            | Atom/Celeron/Pentium Processor x5... | 9     | xhci_hcd   | [863136882E](<Tablet/Hewlett-Packard/x2/x2 210 G2/F90A1440D6C0/LINUXMINT-20.2/5.4.0-137-GENERIC/X86_64/863136882E>) |
| 8086:22b5 | 1043:1c60 | Intel            | Atom/Celeron/Pentium Processor x5... | 9     | xhci_hcd   | [961E13C584](<Tablet/ASUSTek Computer/T103/T103HAF/DC30228D2ADB/LINUXMINT-20.3/5.4.0-148-GENERIC/X86_64/961E13C584>) |
| 8086:461e |           | Intel            | Alder Lake-P Thunderbolt 4 USB Co... | 9     | xhci_pci   | [E5644591DE](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZC_GZ301ZC/D9321FF7F56A/FEDORA-37/6.2.8-300.FC37.X86_64/X86_64/E5644591DE>) |
| 8086:463e | 2222:1111 | Intel            | Alder Lake-P Thunderbolt 4 NHI #0    | 9     | thunder... | [E5644591DE](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZC_GZ301ZC/D9321FF7F56A/FEDORA-37/6.2.8-300.FC37.X86_64/X86_64/E5644591DE>) |
| 8086:9d2f | 1028:07a4 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 9     | xhci_hcd   | [1717754347](<Tablet/Dell/Latitude/Latitude 5285/D75F67E269AD/UBUNTU-22.10/5.19.10-SURFACE/X86_64/1717754347>) |
| 8086:9d2f | 103c:828b | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 9     | xhci_hcd   | [6ECC8F0BAD](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/7A82B39E3BAF/FEDORA-37/6.1.15-200.FC37.X86_64/X86_64/6ECC8F0BAD>) |
| 8086:0f35 | 17aa:3906 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 8     | xhci_hcd   | [7F6BE7CFFE](<Tablet/Lenovo/MIIX/MIIX 3-1030 80HV/A62D4DE83290/KDE-NEON-22.04/5.15.0-56-GENERIC/X86_64/7F6BE7CFFE>) |
| 8086:0f35 | 17aa:390b | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 8     | xhci_hcd   | [B9E3C45CAA](<Tablet/Lenovo/MIIX/MIIX 300-10IBY 80NR/F1574B822916/ARCH-ROLLING/6.0.10-ARCH2-1/X86_64/B9E3C45CAA>) |
| 8086:9a1b | 8086:7270 | Intel            | Tiger Lake-LP Thunderbolt 4 NHI #0   | 8     | thunder... | [3C50D5D61C](<Tablet/Microsoft/Surface/Surface Pro 8/C4CEE7E26DF5/MANJARO/6.2.12-ARCH1-1-SURFACE/X86_64/3C50D5D61C>) |
| 8086:9d2f | 1028:081d | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 8     | xhci_hcd   | [88900A37B9](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/172279AB141B/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/88900A37B9>) |
| 8086:a0ed |           | Intel            | Tiger Lake-LP USB 3.2 Gen 2x1 xHC... | 8     | xhci_pci   | [F348E93361](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/4B50F0906809/UBUNTU-22.10/6.1.4-060104-GENERIC/X86_64/F348E93361>) |
| 8086:9a13 | 1028:0a45 | Intel            | Tiger Lake-LP Thunderbolt 4 USB C... | 7     | xhci_pci   | [5E287BBD8B](<Tablet/Dell/Latitude/Latitude 7320 Detachable/089CE6269F10/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/5E287BBD8B>) |
| 8086:9a13 | 17aa:382f | Intel            | Tiger Lake-LP Thunderbolt 4 USB C... | 7     | xhci_pci   | [5C0467F4CB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/FA8378B128F2/ZORIN-16/5.15.0-69-GENERIC/X86_64/5C0467F4CB>) |

