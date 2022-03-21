Most popular PCI devices in Tablets
===================================

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Tablets ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Digitizer pen ](#digitizer-pen-pci)
   * [ Dma controller (eisa dma) ](#dma-controller-eisa-dma-pci)
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
| 8086:9d18 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 171   | pcieport   | [26A4220432](<Tablet/Microsoft/Surface/Surface Pro 4/5171E94FBA49/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/26A4220432>) |
| 8086:229c | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 148   | lpc_ich    | [D8EA22EFF5](<Tablet/Microsoft/Surface/Surface 3/DEBCA8820BEF/DEBIAN-TESTING/5.16.11-SURFACE/X86_64/D8EA22EFF5>) |
| 8086:2280 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 128   | iosf_mb... | [23FBC9A6EE](<Tablet/RCA/W101/W101AS23T2/BBCA95A1C67D/FEDORA-35/5.16.8-200.FC35.X86_64/X86_64/23FBC9A6EE>) |
| 8086:9d14 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 106   | pcieport   | [26A4220432](<Tablet/Microsoft/Surface/Surface Pro 4/5171E94FBA49/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/26A4220432>) |
| 8086:1904 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 82    | skl_uncore | [26A4220432](<Tablet/Microsoft/Surface/Surface Pro 4/5171E94FBA49/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/26A4220432>) |
| 8086:9d48 | 8086:7270 | Intel            | Sunrise Point-LP LPC Controller      | 82    |            | [26A4220432](<Tablet/Microsoft/Surface/Surface Pro 4/5171E94FBA49/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/26A4220432>) |
| 8086:22c8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 71    | pcieport   | [4758B6520C](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/6D0C35E280B8/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/4758B6520C>) |
| 8086:9d4e | 8086:7270 | Intel            | Sunrise Point LPC Controller/eSPI... | 70    |            | [50420D6D58](<Tablet/Microsoft/Surface/Surface Pro 6/DE921958CD9C/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/50420D6D58>) |
| 8086:0a04 | 1414:0a04 | Intel            | Haswell-ULT DRAM Controller          | 67    | hsw_uncore | [92F8B5CBFA](<Tablet/Microsoft/Surface/Surface Pro 3/0558715ED322/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/92F8B5CBFA>) |
| 8086:9c43 | 1414:9c43 | Intel            | 8 Series LPC Controller              | 67    | lpc_ich    | [92F8B5CBFA](<Tablet/Microsoft/Surface/Surface Pro 3/0558715ED322/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/92F8B5CBFA>) |
| 8086:9c14 | 1414:9c14 | Intel            | 8 Series PCI Express Root Port 3     | 51    | pcieport   | [92F8B5CBFA](<Tablet/Microsoft/Surface/Surface Pro 3/0558715ED322/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/92F8B5CBFA>) |
| 8086:9d13 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 50    | pcieport   | [50420D6D58](<Tablet/Microsoft/Surface/Surface Pro 6/DE921958CD9C/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/50420D6D58>) |
| 8086:5914 | 8086:2015 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 44    | skl_uncore | [50420D6D58](<Tablet/Microsoft/Surface/Surface Pro 6/DE921958CD9C/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/50420D6D58>) |
| 8086:2280 | 17aa:38e3 | Intel            | Atom/Celeron/Pentium Processor x5... | 43    | iosf_mb... | [4758B6520C](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/6D0C35E280B8/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/4758B6520C>) |
| 8086:229c | 17aa:380d | Intel            | Atom/Celeron/Pentium Processor x5... | 43    | lpc_ich    | [4758B6520C](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/6D0C35E280B8/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/4758B6520C>) |
| 8086:2280 | 17aa:3809 | Intel            | Atom/Celeron/Pentium Processor x5... | 40    | iosf_mb... | [FB183BFD9B](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/056649DD334F/MANJARO/5.15.25-1-MANJARO/X86_64/FB183BFD9B>) |
| 8086:229c | 17aa:380a | Intel            | Atom/Celeron/Pentium Processor x5... | 40    | lpc_ich    | [FB183BFD9B](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/056649DD334F/MANJARO/5.15.25-1-MANJARO/X86_64/FB183BFD9B>) |
| 8086:3482 | 8086:7270 | Intel            | Ice Lake-LP LPC Controller           | 37    |            | [A4E86F6259](<Tablet/Microsoft/Surface/Surface Pro 7/4B1F7148A63A/ZORIN-16/5.16.5-SURFACE/X86_64/A4E86F6259>) |
| 8086:34b0 | 8086:7270 | Intel            | Ice Lake-LP PCI Express Root Port #9 | 36    | pcieport   | [A4E86F6259](<Tablet/Microsoft/Surface/Surface Pro 7/4B1F7148A63A/ZORIN-16/5.16.5-SURFACE/X86_64/A4E86F6259>) |
| 8086:8a12 | 8086:7270 | Intel            | Ice Lake-LP Processor Host Bridge... | 35    | icl_uncore | [A4E86F6259](<Tablet/Microsoft/Surface/Surface Pro 7/4B1F7148A63A/ZORIN-16/5.16.5-SURFACE/X86_64/A4E86F6259>) |
| 8086:9d1b | 8086:7270 | Intel            | Skylake-U/Y PCIe Port #12            | 31    | pcieport   | [DC0E450D2C](<Tablet/Microsoft/Surface/Surface Book/A32707B0D7C9/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/DC0E450D2C>) |
| 8086:0f1c | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 30    | lpc_ich    | [A7034FD62E](<Tablet/Lenovo/ThinkPad/ThinkPad 10 20C3S0P900/F580C65F2E19/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/A7034FD62E>) |
| 8086:5904 | 8086:2015 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 30    | skl_uncore | [1A4F0D32AB](<Tablet/Microsoft/Surface/Surface Pro/39E8C6A4CD9F/FEDORA-35/5.16.10-1.SURFACE.FC35.X86_64/X86_64/1A4F0D32AB>) |
| 8086:31e8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    |            | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:5af0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 22    |            | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |
| 8086:5ad7 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 21    | pcieport   | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |
| 8086:5ae8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 21    | lpc_ich    | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |
| 8086:2280 | 103c:827c | Intel            | Atom/Celeron/Pentium Processor x5... | 20    | iosf_mb... | [9A03FDA057](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/E1DE173C5065/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/9A03FDA057>) |
| 8086:2280 | 1043:13a0 | Intel            | Atom/Celeron/Pentium Processor x5... | 20    | iosf_mb... | [05983A1E06](<Tablet/ASUSTek Computer/T101/T101HA/AC331E492606/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/05983A1E06>) |
| 8086:229c | 103c:827c | Intel            | Atom/Celeron/Pentium Processor x5... | 20    | lpc_ich    | [9A03FDA057](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/E1DE173C5065/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/9A03FDA057>) |
| 8086:229c | 1043:13a0 | Intel            | Atom/Celeron/Pentium Processor x5... | 20    | lpc_ich    | [05983A1E06](<Tablet/ASUSTek Computer/T101/T101HA/AC331E492606/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/05983A1E06>) |
| 8086:22c8 | 1043:13a0 | Intel            | Atom/Celeron/Pentium Processor x5... | 20    | pcieport   | [05983A1E06](<Tablet/ASUSTek Computer/T101/T101HA/AC331E492606/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/05983A1E06>) |
| 8086:590c | 152d:1182 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 20    | skl_uncore | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:9d10 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 20    | pcieport   | [730558C6BD](<Tablet/Microsoft/Surface/Surface Book 2/451432DF4DF7/ELEMENTARY-6.1/5.15.6-SURFACE/X86_64/730558C6BD>) |
| 8086:9d12 | 152d:1182 | Intel            | Sunrise Point-LP PCI Express Root... | 20    | pcieport   | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:9d13 | 152d:1182 | Intel            | Sunrise Point-LP PCI Express Root... | 20    | pcieport   | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:9d4b | 152d:1182 | Intel            | Skylake-U/Y LPC/eSPI Controller      | 20    |            | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:22c8 | 103c:827c | Intel            | Atom/Celeron/Pentium Processor x5... | 19    | pcieport   | [9A03FDA057](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/E1DE173C5065/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/9A03FDA057>) |
| 8086:31d8 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 19    | pcieport   | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:9d16 | 152d:1182 | Intel            | Sunrise Point-LP PCI Express Root... | 17    | pcieport   | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:2280 | 1043:1400 | Intel            | Atom/Celeron/Pentium Processor x5... | 16    | iosf_mb... | [ECC5AD7332](<Tablet/ASUSTek Computer/T102/T102HA/C13EDC224850/MX-19/4.19.0-18-AMD64/X86_64/ECC5AD7332>) |
| 8086:2280 | 1414:0009 | Intel            | Atom/Celeron/Pentium Processor x5... | 16    | iosf_mb... | [D8EA22EFF5](<Tablet/Microsoft/Surface/Surface 3/DEBCA8820BEF/DEBIAN-TESTING/5.16.11-SURFACE/X86_64/D8EA22EFF5>) |
| 8086:229c | 1043:1400 | Intel            | Atom/Celeron/Pentium Processor x5... | 16    | lpc_ich    | [ECC5AD7332](<Tablet/ASUSTek Computer/T102/T102HA/C13EDC224850/MX-19/4.19.0-18-AMD64/X86_64/ECC5AD7332>) |
| 8086:22c8 | 1043:1400 | Intel            | Atom/Celeron/Pentium Processor x5... | 16    | pcieport   | [ECC5AD7332](<Tablet/ASUSTek Computer/T102/T102HA/C13EDC224850/MX-19/4.19.0-18-AMD64/X86_64/ECC5AD7332>) |
| 8086:31d9 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 16    | pcieport   | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:31da | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 16    | pcieport   | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:31f0 | 8086:7270 | Intel            | Gemini Lake Host Bridge              | 15    |            | [6350A05DF4](<Tablet/Linx/LAMINALTT8/LAMINALTT8W4G-HBN/3A8211B5B143/ARCH-ROLLING/5.16.3-ARCH1-1/X86_64/6350A05DF4>) |
| 8086:9d16 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 15    | pcieport   | [70703DE094](<Tablet/Microsoft/Surface/Surface Go 3/D83311C5A47C/ANDROID/5.10.31-ANDROID-X86_64-G0B8B6BBDB155-DIRTY/X86_64/70703DE094>) |
| 1002:4384 |           | AMD              | SBx00 PCI to PCI Bridge              | 14    |            | [5984A91751](<Tablet/Acer/Iconia/Iconia Tab W500/99578EB02374/ELEMENTARY-6/5.11.0-40-GENERIC/X86_64/5984A91751>) |
| 1002:439d | 1025:0577 | AMD              | SB7x0/SB8x0/SB9x0 LPC host contro... | 14    |            | [5984A91751](<Tablet/Acer/Iconia/Iconia Tab W500/99578EB02374/ELEMENTARY-6/5.11.0-40-GENERIC/X86_64/5984A91751>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:522a | 152d:1182 | Realtek Semic... | RTS522A PCI Express Card Reader      | 20    | rtsx_pci   | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 10ec:522a | 103c:82ca | Realtek Semic... | RTS522A PCI Express Card Reader      | 10    | rtsx_pci   | [BEEB081772](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/945D2246773B/UBUNTU-MATE-20.04/5.13.0-30-GENERIC/X86_64/BEEB081772>) |
| 10ec:5229 | 17aa:3833 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 8     | rtsx_pci   | [C9D8BB9BD9](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGM 81H3/689B95560E77/MANJARO-21.2.3/5.16.7-1-MANJARO/X86_64/C9D8BB9BD9>) |
| 10ec:522a | 152d:1237 | Realtek Semic... | RTS522A PCI Express Card Reader      | 8     | rtsx_pci   | [E530D905DA](<Tablet/Microsoft/Surface/Surface Go 2/356E9AC2E762/ARCH/5.15.11-ARCH2-1-SURFACE/X86_64/E530D905DA>) |
| 10ec:522a | 103c:828b | Realtek Semic... | RTS522A PCI Express Card Reader      | 6     | rtsx_pci   | [5A85AB6B0F](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/608A6BF05466/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/5A85AB6B0F>) |
| 10ec:525a | 1028:06e6 | Realtek Semic... | RTS525A PCI Express Card Reader      | 6     | rtsx_pci   | [6430380D5B](<Tablet/Dell/Latitude/Latitude 5179/597547DCB08C/POP!_OS-20.04/5.16.11-76051611-GENERIC/X86_64/6430380D5B>) |
| 10ec:525a | 1028:07a4 | Realtek Semic... | RTS525A PCI Express Card Reader      | 6     | rtsx_pci   | [568757F9F8](<Tablet/Dell/Latitude/Latitude 5285/9BC7EC024B34/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/568757F9F8>) |
| 10ec:5229 | 10ec:5229 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 5     | rtsx_pci   | [5D34718515](<Tablet/Chuwi/UBook/UBook/16BCEDE93936/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/5D34718515>) |
| 10ec:522a | 17aa:2244 | Realtek Semic... | RTS522A PCI Express Card Reader      | 5     | rtsx_pci   | [55F51A3D6F](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJ0011US/7240D66F8895/POP!_OS-21.04/5.13.0-7614-GENERIC/X86_64/55F51A3D6F>) |
| 10ec:525a | 1028:081d | Realtek Semic... | RTS525A PCI Express Card Reader      | 5     | rtsx_pci   | [9CFD9C7142](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/39E24435C9D2/ELEMENTARY-6.1/5.13.0-30-GENERIC/X86_64/9CFD9C7142>) |
| 10ec:5229 | 17aa:382e | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx_pci   | [2825AD59D4](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/904DB6C5A19D/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/2825AD59D4>) |
| 10ec:522a | 17aa:2241 | Realtek Semic... | RTS522A PCI Express Card Reader      | 4     | rtsx_pci   | [923CCB09A5](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GHCTO1WW/70707A835AE8/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/923CCB09A5>) |
| 10ec:525a | 1028:06d6 | Realtek Semic... | RTS525A PCI Express Card Reader      | 4     | rtsx_pci   | [14BCC9219C](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-21.10/5.16.10-XANMOD1/X86_64/14BCC9219C>) |
| 10ec:522a | 17aa:382a | Realtek Semic... | RTS522A PCI Express Card Reader      | 3     | rtsx_pci   | [047FF4AD80](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/37FF40E14E4D/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/047FF4AD80>) |
| 10ec:522a | 103c:82cb | Realtek Semic... | RTS522A PCI Express Card Reader      | 2     | rtsx_pci   | [EFC4C63AC7](<Tablet/Hewlett-Packard/Spectre/Spectre x2 Detachable 12-c0XX/09798ACE135C/DEEPIN-20.2.2/5.10.36-AMD64-DESKTOP/X86_64/EFC4C63AC7>) |
| 10ec:522a | 17aa:2243 | Realtek Semic... | RTS522A PCI Express Card Reader      | 2     | rtsx_pci   | [39C0680056](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JB003LMX/2CEEE337E2A9/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/39C0680056>) |
| 10ec:522a | 103c:824c | Realtek Semic... | RTS522A PCI Express Card Reader      | 1     | rtsx_pci   | [A557059CBA](<Tablet/Hewlett-Packard/ZBook/ZBook x2 G4/9B15D9768480/UBUNTU-20.04/5.4.0-54-GENERIC/X86_64/A557059CBA>) |
| 10ec:522a | 10ec:522a | Realtek Semic... | RTS522A PCI Express Card Reader      | 1     | rtsx_pci   | [5A15D9B82A](<Tablet/Chuwi/UBook/UBook X/91314AF7605E/FEDORA-34/5.13.10-200.FC34.X86_64/X86_64/5A15D9B82A>) |
| 10ec:522a | 17aa:3823 | Realtek Semic... | RTS522A PCI Express Card Reader      | 1     | rtsx_pci   | [FD98FD839E](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 10IGL5 82AT/DCC92275F773/FEDORA-34/5.11.21-300.FC34.X86_64/X86_64/FD98FD839E>) |
| 10ec:525a | 1028:0702 | Realtek Semic... | RTS525A PCI Express Card Reader      | 1     | rtsx_pci   | [CE9A3F2C74](<Tablet/Dell/XPS/XPS 12 9250/A04CD2743A76/CLEAR-LINUX-OS-35400/5.15.7-1106.NATIVE/X86_64/CE9A3F2C74>) |
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
| 8086:9d3a | 8086:7270 | Intel            | Sunrise Point-LP CSME HECI #1        | 171   | mei_me     | [26A4220432](<Tablet/Microsoft/Surface/Surface Pro 4/5171E94FBA49/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/26A4220432>) |
| 8086:9d3e |           | Intel            | iTouch Controller                    | 169   | mei_me     | [26A4220432](<Tablet/Microsoft/Surface/Surface Pro 4/5171E94FBA49/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/26A4220432>) |
| 8086:9c3a | 1414:9c3a | Intel            | 8 Series HECI #0                     | 51    | mei_me     | [92F8B5CBFA](<Tablet/Microsoft/Surface/Surface Pro 3/0558715ED322/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/92F8B5CBFA>) |
| 8086:34a8 | 8086:7270 | Intel            | Ice Lake-LP Serial IO UART Contro... | 37    | intel_l... | [A4E86F6259](<Tablet/Microsoft/Surface/Surface Pro 7/4B1F7148A63A/ZORIN-16/5.16.5-SURFACE/X86_64/A4E86F6259>) |
| 8086:34e0 | 8086:7270 | Intel            | Ice Lake-LP Management Engine        | 37    | mei_me     | [A4E86F6259](<Tablet/Microsoft/Surface/Surface Pro 7/4B1F7148A63A/ZORIN-16/5.16.5-SURFACE/X86_64/A4E86F6259>) |
| 8086:319a | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    | mei_me     | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:5a9a | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 22    | mei_me     | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |
| 8086:34e4 | 1414:0039 | Intel            | Communication controller             | 20    | mei_me     | [A4E86F6259](<Tablet/Microsoft/Surface/Surface Pro 7/4B1F7148A63A/ZORIN-16/5.16.5-SURFACE/X86_64/A4E86F6259>) |
| 8086:9d3a | 152d:1182 | Intel            | Sunrise Point-LP CSME HECI #1        | 20    | mei_me     | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:9c3a | 8086:9c3a | Intel            | 8 Series HECI #0                     | 16    | mei_me     | [275B20283F](<Tablet/Microsoft/Surface/Surface Pro 2/DF18662C511A/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/275B20283F>) |
| 8086:9d3a | 103c:82ca | Intel            | Sunrise Point-LP CSME HECI #1        | 9     | mei_me     | [BEEB081772](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/945D2246773B/UBUNTU-MATE-20.04/5.13.0-30-GENERIC/X86_64/BEEB081772>) |
| 8086:1e3a | 1414:1e3a | Intel            | 7 Series/C216 Chipset Family MEI ... | 8     | mei_me     | [F1D0D25B44](<Tablet/Microsoft/Surface/Surface with Windows 8 Pro/EC94C82618D5/UBUNTU-20.04/5.15.13-051513-GENERIC/X86_64/F1D0D25B44>) |
| 8086:319a | 17aa:3824 | Intel            | Celeron/Pentium Silver Processor ... | 8     | mei_me     | [C9D8BB9BD9](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGM 81H3/689B95560E77/MANJARO-21.2.3/5.16.7-1-MANJARO/X86_64/C9D8BB9BD9>) |
| 8086:9d3a | 144d:c14f | Intel            | Sunrise Point-LP CSME HECI #1        | 8     | mei_me     | [63CAA45089](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12 LTE/F81EBA4C8217/ZORIN-16/5.13.0-30-GENERIC/X86_64/63CAA45089>) |
| 8086:9d3a | 17aa:3850 | Intel            | Sunrise Point-LP CSME HECI #1        | 7     | mei_me     | [8B9FA8F425](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/A89FAAAFC012/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/8B9FA8F425>) |
| 8086:9d3a | 8086:9d3a | Intel            | Sunrise Point-LP CSME HECI #1        | 7     | mei_me     | [0F05F12004](<Tablet/Teclast/X5/X5 Pro/B130987D6E6A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0F05F12004>) |
| 8086:9d3a | 1028:06e6 | Intel            | Sunrise Point-LP CSME HECI #1        | 6     | mei_me     | [6430380D5B](<Tablet/Dell/Latitude/Latitude 5179/597547DCB08C/POP!_OS-20.04/5.16.11-76051611-GENERIC/X86_64/6430380D5B>) |
| 8086:9d3a | 1028:07a4 | Intel            | Sunrise Point-LP CSME HECI #1        | 6     | mei_me     | [568757F9F8](<Tablet/Dell/Latitude/Latitude 5285/9BC7EC024B34/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/568757F9F8>) |
| 8086:9d3a | 144d:c135 | Intel            | Sunrise Point-LP CSME HECI #1        | 6     | mei_me     | [3ADAAACD83](<Tablet/Samsung Electronics/Galaxy/Galaxy TabPro S/7232B6211ED3/POP!_OS-21.04/5.13.0-7614-GENERIC/X86_64/3ADAAACD83>) |
| 8086:9d3a | 152d:1237 | Intel            | Sunrise Point-LP CSME HECI #1        | 6     | mei_me     | [E530D905DA](<Tablet/Microsoft/Surface/Surface Go 2/356E9AC2E762/ARCH/5.15.11-ARCH2-1-SURFACE/X86_64/E530D905DA>) |
| 8086:9d3a | 17aa:2244 | Intel            | Sunrise Point-LP CSME HECI #1        | 6     | mei_me     | [F92AE76FED](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJCTO1WW/3D3FB636D7D4/DEVUAN-4/5.10.0-11-AMD64/X86_64/F92AE76FED>) |
| 8086:9d3a | 1028:081d | Intel            | Sunrise Point-LP CSME HECI #1        | 5     | mei_me     | [9CFD9C7142](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/39E24435C9D2/ELEMENTARY-6.1/5.13.0-30-GENERIC/X86_64/9CFD9C7142>) |
| 8086:9d3a | 103c:828b | Intel            | Sunrise Point-LP CSME HECI #1        | 5     | mei_me     | [5A85AB6B0F](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/608A6BF05466/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/5A85AB6B0F>) |
| 8086:9d3a | 1025:111e | Intel            | Sunrise Point-LP CSME HECI #1        | 4     | mei_me     | [C6DC41A2A5](<Tablet/Acer/Switch/Switch SA5-271/7F70B3D37585/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C6DC41A2A5>) |
| 8086:9d3a | 1028:06d6 | Intel            | Sunrise Point-LP CSME HECI #1        | 4     | mei_me     | [14BCC9219C](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-21.10/5.16.10-XANMOD1/X86_64/14BCC9219C>) |
| 8086:9d3a | 1028:07a5 | Intel            | Sunrise Point-LP CSME HECI #1        | 4     | mei_me     | [78F2672479](<Tablet/Dell/Latitude/Latitude 7285/35CB641DDB78/CLEAR-LINUX-OS-35940/5.16.11-1128.NATIVE/X86_64/78F2672479>) |
| 8086:9d3a | 17aa:2241 | Intel            | Sunrise Point-LP CSME HECI #1        | 4     | mei_me     | [923CCB09A5](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GHCTO1WW/70707A835AE8/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/923CCB09A5>) |
| 8086:9d3a | 17aa:382b | Intel            | Sunrise Point-LP CSME HECI #1        | 4     | mei_me     | [E1BEE3CD30](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/63E5CC1D8A4F/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/E1BEE3CD30>) |
| 8086:a0e0 | 17aa:381e | Intel            | Tiger Lake-LP Management Engine I... | 4     | mei_me     | [047FF4AD80](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/37FF40E14E4D/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/047FF4AD80>) |
| 8086:02e0 | 17aa:3811 | Intel            | Comet Lake Management Engine Inte... | 3     | mei_me     | [927ED071B3](<Tablet/Lenovo/Yoga/Yoga Duet IML 2020 82E9/8FFE2F20194E/ARCH-ROLLING/5.16.2-ARCH1-1/X86_64/927ED071B3>) |
| 8086:34e4 | 1414:0040 | Intel            | Communication controller             | 3     | mei_me     | [462CF49FDA](<Tablet/Microsoft/Surface/Surface Book 3/5F8FFB6F8EE7/ARCH-ROLLING/5.14.5-ARCH1-1-SURFACE/X86_64/462CF49FDA>) |
| 8086:34e4 | 1414:0041 | Intel            | Communication controller             | 3     |            | [162DA90CC6](<Tablet/Microsoft/Surface/Surface Laptop 3/1C7E565DCB2D/MANJARO-21.2.0/5.15.7-1-MANJARO/X86_64/162DA90CC6>) |
| 8086:5a9a | 8086:5a9a | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | mei_me     | [07C752AA8C](<Tablet/ZoomSmart/A/A1002/F1BBB3E02B52/ROSA-2019.05/5.4.60-NICKEL-2ROSA2019.05-X86_64/X86_64/07C752AA8C>) |
| 8086:9c3a | 8086:7270 | Intel            | 8 Series HECI #0                     | 3     | mei_me     | [2D356053D3](<Tablet/Lenovo/MIIX/MIIX 2 11 20327/880F55D78695/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/2D356053D3>) |
| 8086:9cba | 17aa:222b | Intel            | Wildcat Point-LP MEI Controller #1   | 3     | mei_me     | [5BADA8B921](<Tablet/Lenovo/ThinkPad/ThinkPad Helix 2nd 20CHS1NG03/BD286A22C079/FEDORA-33/5.10.21-200.FC33.X86_64/X86_64/5BADA8B921>) |
| 8086:9d3a | 17aa:3834 | Intel            | Sunrise Point-LP CSME HECI #1        | 3     | mei_me     | [67E1BDD5F1](<Tablet/Lenovo/MIIX/MIIX 720-12IKB 80VV/F45F8CE4052D/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/67E1BDD5F1>) |
| 8086:9d3a | 17aa:3841 | Intel            | Sunrise Point-LP CSME HECI #1        | 3     | mei_me     | [D249085990](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/A4295A395509/POP!_OS-21.10/5.15.8-76051508-GENERIC/X86_64/D249085990>) |
| 8086:9d3a | 19e5:3e00 | Intel            | Sunrise Point-LP CSME HECI #1        | 3     | mei_me     | [904DECFD32](<Tablet/HUAWEI/MateBook/MateBook HZ-W19/F902238EFB24/LMDE-4/4.19.0-17-AMD64/X86_64/904DECFD32>) |
| 8086:a0a8 | 8086:7270 | Intel            | Tiger Lake-LP Serial IO UART Cont... | 3     | intel_lpss | [BD290BC56D](<Tablet/Microsoft/Surface/Surface Laptop Studio/AD9CE584B5E1/MANJARO-21.1.6/5.13.19-2-MANJARO/X86_64/BD290BC56D>) |
| 8086:a0e0 | 8086:7270 | Intel            | Tiger Lake-LP Management Engine I... | 3     | mei_me     | [BD290BC56D](<Tablet/Microsoft/Surface/Surface Laptop Studio/AD9CE584B5E1/MANJARO-21.1.6/5.13.19-2-MANJARO/X86_64/BD290BC56D>) |
| 8086:1e3a | 10f7:8338 | Intel            | 7 Series/C216 Chipset Family MEI ... | 2     | mei_me     | [06F11C0449](<Tablet/Panasonic/FZ-G1/FZ-G1ASH39E3/6F2FB083615E/ELEMENTARY-6/5.11.0-37-GENERIC/X86_64/06F11C0449>) |
| 8086:9cba | 8086:7270 | Intel            | Wildcat Point-LP MEI Controller #1   | 2     | mei_me     | [9E5A5DC6CF](<Tablet/Microsoft/Surface/Surface Pro 6/DE921958CD9C/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/9E5A5DC6CF>) |
| 8086:9d3a | 1025:1171 | Intel            | Sunrise Point-LP CSME HECI #1        | 2     | mei_me     | [4B0ED624FA](<Tablet/Acer/Switch/Switch SW512-52/8FD5C8AAAFE9/ARCH-ROLLING/5.8.12-ARCH1-1/X86_64/4B0ED624FA>) |
| 8086:9d3a | 103c:82cb | Intel            | Sunrise Point-LP CSME HECI #1        | 2     | mei_me     | [EFC4C63AC7](<Tablet/Hewlett-Packard/Spectre/Spectre x2 Detachable 12-c0XX/09798ACE135C/DEEPIN-20.2.2/5.10.36-AMD64-DESKTOP/X86_64/EFC4C63AC7>) |
| 8086:9d3a | 103c:8414 | Intel            | Sunrise Point-LP CSME HECI #1        | 2     | mei_me     | [6EE77ED959](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/3DD573867AA0/UBUNTU-20.04/5.8.0-36-GENERIC/X86_64/6EE77ED959>) |
| 8086:9d3a | 1043:13c0 | Intel            | Sunrise Point-LP CSME HECI #1        | 2     | mei_me     | [4363CA1BD6](<Tablet/ASUSTek Computer/T303/T303UA/C8223D9D63FE/UBUNTU-20.04/5.4.0-33-GENERIC/X86_64/4363CA1BD6>) |
| 8086:9d3a | 1043:1410 | Intel            | Sunrise Point-LP CSME HECI #1        | 2     | mei_me     | [C66E4999F0](<Tablet/ASUSTek Computer/T305/T305CA/70CB67E36043/UBUNTU-20.04/5.8.0-50-GENERIC/X86_64/C66E4999F0>) |
| 8086:9d3a | 1043:16c0 | Intel            | Sunrise Point-LP CSME HECI #1        | 2     | mei_me     | [D33E67BDF4](<Tablet/ASUSTek Computer/T304/T304UA/8F97F461C23D/UBUNTU-20.04/5.4.0-29-GENERIC/X86_64/D33E67BDF4>) |
| 8086:9d3a | 17aa:2243 | Intel            | Sunrise Point-LP CSME HECI #1        | 2     | mei_me     | [39C0680056](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JB003LMX/2CEEE337E2A9/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/39C0680056>) |
| 8086:9d3a | 1b0a:01d3 | Intel            | Sunrise Point-LP CSME HECI #1        | 2     | mei_me     | [60C93DDC01](<Tablet/Xplore/iX125/iX125R1/9DCB305AD004/PUPPY_IMPPUP64-9.6.1/5.15.11-LXPUP64/X86_64/60C93DDC01>) |

### Digitizer pen (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a0d0 | 1414:0049 | Intel            | Digitizer Pen                        | 1     |            | [BD290BC56D](<Tablet/Microsoft/Surface/Surface Laptop Studio/AD9CE584B5E1/MANJARO-21.1.6/5.13.19-2-MANJARO/X86_64/BD290BC56D>) |
| 8086:a0d0 | 1414:0053 | Intel            | Digitizer Pen                        | 1     |            | [51711F9018](<Tablet/Microsoft/Surface/Surface Laptop 4/3C3A49F2525B/ZORIN-16/5.15.3-SURFACE/X86_64/51711F9018>) |
| 8086:a0d0 | 1414:0056 | Intel            | Digitizer Pen                        | 1     |            | [A4AEFCD9B2](<Tablet/Microsoft/Surface/Surface Pro 7+/B513B8EA5A0E/FEDORA-32/5.10.10-1.SURFACE.FC32.X86_64/X86_64/A4AEFCD9B2>) |

### Dma controller (eisa dma) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9ce0 | 8086:9ce0 | Intel            | Wildcat Point-LP Serial IO DMA Co... | 2     | dw_dmac... | [9E5A5DC6CF](<Tablet/Microsoft/Surface/Surface Pro 6/DE921958CD9C/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/9E5A5DC6CF>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2298 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 148   | mei_txe    | [D8EA22EFF5](<Tablet/Microsoft/Surface/Surface 3/DEBCA8820BEF/DEBIAN-TESTING/5.16.11-SURFACE/X86_64/D8EA22EFF5>) |
| 8086:2298 | 17aa:380c | Intel            | Atom/Celeron/Pentium Processor x5... | 43    | mei_txe    | [4758B6520C](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/6D0C35E280B8/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/4758B6520C>) |
| 8086:2298 | 17aa:380a | Intel            | Atom/Celeron/Pentium Processor x5... | 40    | mei_txe    | [FB183BFD9B](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/056649DD334F/MANJARO/5.15.25-1-MANJARO/X86_64/FB183BFD9B>) |
| 8086:0f18 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 29    | mei_txe    | [A7034FD62E](<Tablet/Lenovo/ThinkPad/ThinkPad 10 20C3S0P900/F580C65F2E19/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/A7034FD62E>) |
| 8086:2298 | 103c:827c | Intel            | Atom/Celeron/Pentium Processor x5... | 20    | mei_txe    | [9A03FDA057](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/E1DE173C5065/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/9A03FDA057>) |
| 8086:2298 | 1043:13a0 | Intel            | Atom/Celeron/Pentium Processor x5... | 20    | mei_txe    | [05983A1E06](<Tablet/ASUSTek Computer/T101/T101HA/AC331E492606/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/05983A1E06>) |
| 8086:2298 | 1043:1400 | Intel            | Atom/Celeron/Pentium Processor x5... | 16    | mei_txe    | [ECC5AD7332](<Tablet/ASUSTek Computer/T102/T102HA/C13EDC224850/MX-19/4.19.0-18-AMD64/X86_64/ECC5AD7332>) |
| 8086:0f18 | 1019:99a5 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 12    | mei_txe    | [A2B7A04DFA](<Tablet/Intel/powered/powered classmate PC/E3EDE14D59EF/LINUXMINT-20.2/5.4.0-100-GENERIC/X86_64/A2B7A04DFA>) |
| 8086:0f18 | 103c:815d | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 7     | mei_txe    | [16B7C17050](<Tablet/Hewlett-Packard/Pavilion/Pavilion x2 Detachable/800BF9CCC703/FEDORA-35/5.14.10-300.FC35.X86_64/X86_64/16B7C17050>) |
| 1022:15df | 1022:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 6     | ccp        | [D55F23484E](<Tablet/Microsoft/Surface/Surface Laptop 3/6407F7577C70/ELEMENTARY-6.1/5.16.11-SURFACE/X86_64/D55F23484E>) |
| 8086:0f18 | 1019:99a1 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | mei_txe    | [C61A96D514](<Tablet/Medion/P/P2212T/71C4E4B2F18A/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/C61A96D514>) |
| 8086:0f18 | 17aa:3906 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | mei_txe    | [BE55ABE40D](<Tablet/Lenovo/MIIX/MIIX 3-1030 80HV/6B8420DF8C02/KALI-2020.2/5.5.0-KALI2-686-PAE/I686/BE55ABE40D>) |
| 8086:0f18 | 17aa:390b | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | mei_txe    | [92D4603EA8](<Tablet/Lenovo/MIIX/MIIX 300-10IBY 80NR/F1574B822916/ARCH/5.6.17/X86_64/92D4603EA8>) |
| 8086:2298 | 103c:82f4 | Intel            | Atom/Celeron/Pentium Processor x5... | 6     | mei_txe    | [6CAB74E68A](<Tablet/Hewlett-Packard/x2/x2 210 G2/9F303DEBAE52/XUBUNTU-21.10/5.13.0-28-GENERIC/X86_64/6CAB74E68A>) |
| 8086:2298 | 1043:1c60 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | mei_txe    | [B2D1B00B0A](<Tablet/ASUSTek Computer/T103/T103HAF/F93497AB5707/ZORIN-12/4.13.0-37-GENERIC/X86_64/B2D1B00B0A>) |
| 8086:0f18 | 103c:8031 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 4     | mei_txe    | [0297D0F732](<Tablet/Hewlett-Packard/Stream/Stream 7 Tablet/2CFECD3BB696/ALPINE-3.15.0_ALPHA20210804/5.10.72-1-LTS/I686/0297D0F732>) |
| 8086:0f18 | 8086:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 4     | mei_txe    | [3B331BB4AF](<Tablet/TrekStor/SurfTab/SurfTab wintron 7.0/6B2D27EED579/DEBIAN-TESTING/4.19.0-5-AMD64/X86_64/3B331BB4AF>) |
| 8086:0f18 | 1509:7018 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | mei_txe    | [9347717861](<Tablet/Xplore/iX101/iX101B1/988A604FB8AB/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/9347717861>) |
| 8086:0f18 | 1854:0211 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | mei_txe    | [44AF16AC16](<Tablet/LG Electronics/15U340/15U340-L.BK55P1/96572D02BF5F/LINUXMINT-20/5.4.0-42-GENERIC/X86_64/44AF16AC16>) |
| 8086:0f18 | 1019:980b | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [B09FE8903A](<Tablet/Intel/Education/Education Tablet/DEFE34A6E3C6/ENDLESS-3.8.7/5.4.0-42-GENERIC/X86_64/B09FE8903A>) |
| 8086:0f18 | 1025:0949 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [4784D8BAAE](<Tablet/Acer/Iconia/Iconia W1-810/A5F3CE2357F6/LINUXMINT-20.1/5.4.0-73-GENERIC/X86_64/4784D8BAAE>) |
| 8086:0f18 | 103c:8032 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [379E9A74C2](<Tablet/Hewlett-Packard/Stream/Stream 8 Tablet/743FE191FDCC/UBUNTU-21.04/5.11.0-31-GENERIC/X86_64/379E9A74C2>) |
| 8086:0f18 | 1558:5470 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [DD65C5ABF7](<Tablet/Lanix/Neuron/Neuron A/9C81E684C8A4/ARCH-ROLLING/5.8.14-ARCH1-1/X86_64/DD65C5ABF7>) |
| 8086:0f18 | 17aa:3900 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [205A7C853A](<Tablet/Lenovo/MIIX/MIIX 2 8 20326/B37FA4DC61DF/UBUNTU-20.04/5.8.0-43-GENERIC/X86_64/205A7C853A>) |
| 8086:0f18 | 17aa:3985 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [EDFF48D58F](<Tablet/Lenovo/MIIX/MIIX 2 10 20359/FD917461E5C6/FEDORA-33/5.10.21-200.FC33.X86_64/X86_64/EDFF48D58F>) |
| 8086:0f18 | 17aa:6080 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [06FE78096E](<Tablet/NEC Computers/PC-TW508/PC-TW508CAS/825BA310157C/ZORIN-16/5.11.0-41-GENERIC/X86_64/06FE78096E>) |
| 8086:1198 |           | Intel            | Encryption controller                | 1     |            | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:2298 | 1854:0280 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | mei_txe    | [A6AB074BB5](<Tablet/LG Electronics/10T370/10T370-L860K/FC0AE2C9A307/ENDLESS-3.9.1/5.8.0-14-GENERIC/X86_64/A6AB074BB5>) |
| 8086:2298 | 1bfd:0001 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | mei_txe    | [1BA20022CB](<Tablet/Medion/E1239T/E1239T MD60791/B4344693BF47/ENDLESS-3.9.0/5.8.0-14-GENERIC/X86_64/1BA20022CB>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:22b0 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 127   | i915       | [23FBC9A6EE](<Tablet/RCA/W101/W101AS23T2/BBCA95A1C67D/FEDORA-35/5.16.8-200.FC35.X86_64/X86_64/23FBC9A6EE>) |
| 8086:22b0 | 17aa:38e3 | Intel            | Atom/Celeron/Pentium Processor x5... | 43    | i915       | [4758B6520C](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/6D0C35E280B8/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/4758B6520C>) |
| 8086:22b0 | 17aa:3809 | Intel            | Atom/Celeron/Pentium Processor x5... | 40    | i915       | [FB183BFD9B](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/056649DD334F/MANJARO/5.15.25-1-MANJARO/X86_64/FB183BFD9B>) |
| 8086:1916 | 1414:0015 | Intel            | Skylake GT2 [HD Graphics 520]        | 38    | i915       | [26A4220432](<Tablet/Microsoft/Surface/Surface Pro 4/5171E94FBA49/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/26A4220432>) |
| 8086:1916 | 1414:0014 | Intel            | Skylake GT2 [HD Graphics 520]        | 31    | i915       | [DC0E450D2C](<Tablet/Microsoft/Surface/Surface Book/A32707B0D7C9/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/DC0E450D2C>) |
| 8086:0a16 | 1414:0005 | Intel            | Haswell-ULT Integrated Graphics C... | 30    | i915       | [8F4B5410AD](<Tablet/Microsoft/Surface/Surface Pro 3/E24ADCEEFFDC/DEBIAN-5/5.14.0-9PARROT1-AMD64/X86_64/8F4B5410AD>) |
| 8086:22b0 | 103c:827c | Intel            | Atom/Celeron/Pentium Processor x5... | 20    | i915       | [9A03FDA057](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/E1DE173C5065/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/9A03FDA057>) |
| 8086:22b0 | 1043:13a0 | Intel            | Atom/Celeron/Pentium Processor x5... | 20    | i915       | [05983A1E06](<Tablet/ASUSTek Computer/T101/T101HA/AC331E492606/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/05983A1E06>) |
| 8086:591e | 152d:1182 | Intel            | HD Graphics 615                      | 20    | i915       | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:5917 | 1414:0026 | Intel            | UHD Graphics 620                     | 19    | i915       | [50420D6D58](<Tablet/Microsoft/Surface/Surface Pro 6/DE921958CD9C/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/50420D6D58>) |
| 8086:5916 | 1414:0026 | Intel            | HD Graphics 620                      | 18    | i915       | [1A4F0D32AB](<Tablet/Microsoft/Surface/Surface Pro/39E8C6A4CD9F/FEDORA-35/5.16.10-1.SURFACE.FC35.X86_64/X86_64/1A4F0D32AB>) |
| 8086:0a16 | 1414:0a16 | Intel            | Haswell-ULT Integrated Graphics C... | 16    | i915       | [275B20283F](<Tablet/Microsoft/Surface/Surface Pro 2/DF18662C511A/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/275B20283F>) |
| 8086:22b0 | 1043:1400 | Intel            | Atom/Celeron/Pentium Processor x5... | 16    | i915       | [ECC5AD7332](<Tablet/ASUSTek Computer/T102/T102HA/C13EDC224850/MX-19/4.19.0-18-AMD64/X86_64/ECC5AD7332>) |
| 8086:22b0 | 1414:0009 | Intel            | Atom/Celeron/Pentium Processor x5... | 16    | i915       | [D8EA22EFF5](<Tablet/Microsoft/Surface/Surface 3/DEBCA8820BEF/DEBIAN-TESTING/5.16.11-SURFACE/X86_64/D8EA22EFF5>) |
| 8086:3185 | 8086:2212 | Intel            | GeminiLake [UHD Graphics 600]        | 15    | i915       | [6350A05DF4](<Tablet/Linx/LAMINALTT8/LAMINALTT8W4G-HBN/3A8211B5B143/ARCH-ROLLING/5.16.3-ARCH1-1/X86_64/6350A05DF4>) |
| 8086:0a26 | 1414:0005 | Intel            | Haswell-ULT Integrated Graphics C... | 13    | i915       | [92F8B5CBFA](<Tablet/Microsoft/Surface/Surface Pro 3/0558715ED322/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/92F8B5CBFA>) |
| 8086:1926 | 1414:0015 | Intel            | Iris Graphics 540                    | 13    | i915       | [836AF3B8C6](<Tablet/Microsoft/Surface/Surface Pro 4/4FE923E500E7/ZORIN-16/5.15.0-051500-GENERIC/X86_64/836AF3B8C6>) |
| 8086:0f31 | 1019:99a5 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 12    | i915       | [A2B7A04DFA](<Tablet/Intel/powered/powered classmate PC/E3EDE14D59EF/LINUXMINT-20.2/5.4.0-100-GENERIC/X86_64/A2B7A04DFA>) |
| 8086:0f31 | 17aa:221b | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 12    | i915       | [A7034FD62E](<Tablet/Lenovo/ThinkPad/ThinkPad 10 20C3S0P900/F580C65F2E19/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/A7034FD62E>) |
| 8086:0f31 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 12    | i915       | [4997E0CA93](<Tablet/3E/Education/Education PC by 3E/E31A80098684/ELEMENTARY-5.1.7/5.4.0-77-GENERIC/X86_64/4997E0CA93>) |
| 8086:5917 | 1414:0028 | Intel            | UHD Graphics 620                     | 11    | i915       | [B4A346E899](<Tablet/Microsoft/Surface/Surface Book 2/0BE3401C9A96/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/B4A346E899>) |
| 8086:5a85 | 8086:2212 | Intel            | HD Graphics 500                      | 11    | i915       | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |
| 1002:9804 | 1025:0577 | AMD              | Wrestler [Radeon HD 6250]            | 10    | radeon     | [5984A91751](<Tablet/Acer/Iconia/Iconia Tab W500/99578EB02374/ELEMENTARY-6/5.11.0-40-GENERIC/X86_64/5984A91751>) |
| 8086:5916 | 103c:82ca | Intel            | HD Graphics 620                      | 10    | i915       | [BEEB081772](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/945D2246773B/UBUNTU-MATE-20.04/5.13.0-30-GENERIC/X86_64/BEEB081772>) |
| 8086:5917 | 1414:0027 | Intel            | UHD Graphics 620                     | 10    | i915       | [730558C6BD](<Tablet/Microsoft/Surface/Surface Book 2/451432DF4DF7/ELEMENTARY-6.1/5.15.6-SURFACE/X86_64/730558C6BD>) |
| 8086:8a56 | 1414:0047 | Intel            | Iris Plus Graphics G1 (Ice Lake)     | 10    | i915       | [E86F28CD8F](<Tablet/Microsoft/Surface/Surface Laptop Go/B7794AB59EF0/LINUXMINT-20.2/5.15.6-SURFACE/X86_64/E86F28CD8F>) |
| 8086:8a5a | 1414:0037 | Intel            | Iris Plus Graphics G4 (Ice Lake)     | 10    | i915       | [A4E86F6259](<Tablet/Microsoft/Surface/Surface Pro 7/4B1F7148A63A/ZORIN-16/5.16.5-SURFACE/X86_64/A4E86F6259>) |
| 8086:0166 | 1414:0166 | Intel            | 3rd Gen Core processor Graphics C... | 8     | i915       | [F1D0D25B44](<Tablet/Microsoft/Surface/Surface with Windows 8 Pro/EC94C82618D5/UBUNTU-20.04/5.15.13-051513-GENERIC/X86_64/F1D0D25B44>) |
| 8086:0a1e | 1414:0005 | Intel            | Haswell-ULT High Definition Audio... | 8     | i915       | [F4C9D49611](<Tablet/Microsoft/Surface/Surface Pro 3/8481DC1AC1F1/POP!_OS-21.10/5.15.8-76051508-GENERIC/X86_64/F4C9D49611>) |
| 8086:5916 | 144d:c14f | Intel            | HD Graphics 620                      | 8     | i915       | [63CAA45089](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12 LTE/F81EBA4C8217/ZORIN-16/5.13.0-30-GENERIC/X86_64/63CAA45089>) |
| 8086:591e | 1414:0026 | Intel            | HD Graphics 615                      | 8     | i915       | [56C75F9229](<Tablet/Microsoft/Surface/Surface Pro/30C30BAC02B4/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/56C75F9229>) |
| 8086:8a52 | 1414:0037 | Intel            | Iris Plus Graphics G7                | 8     | i915       | [C9587DEB57](<Tablet/Microsoft/Surface/Surface Pro 7/8414647CDA1A/UBUNTU-20.04/5.15.12-SURFACE/X86_64/C9587DEB57>) |
| 10de:1c20 | 1414:0024 | Nvidia           | GP106M [GeForce GTX 1060 Mobile]     | 7     | nouveau    | [C864CCE720](<Tablet/Microsoft/Surface/Surface Book 2/44CB94E9B7BC/ARCH-ROLLING/5.14.11-ARCH1-1/X86_64/C864CCE720>) |
| 8086:0f31 | 103c:815d | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 7     | i915       | [16B7C17050](<Tablet/Hewlett-Packard/Pavilion/Pavilion x2 Detachable/800BF9CCC703/FEDORA-35/5.14.10-300.FC35.X86_64/X86_64/16B7C17050>) |
| 10de:1c8d | 1414:0024 | Nvidia           | GP107M [GeForce GTX 1050 Mobile]     | 6     | nouveau    | [730558C6BD](<Tablet/Microsoft/Surface/Surface Book 2/451432DF4DF7/ELEMENTARY-6.1/5.15.6-SURFACE/X86_64/730558C6BD>) |
| 8086:0f31 | 1019:99a1 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | i915       | [C61A96D514](<Tablet/Medion/P/P2212T/71C4E4B2F18A/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/C61A96D514>) |
| 8086:0f31 | 17aa:3906 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | i915       | [BE55ABE40D](<Tablet/Lenovo/MIIX/MIIX 3-1030 80HV/6B8420DF8C02/KALI-2020.2/5.5.0-KALI2-686-PAE/I686/BE55ABE40D>) |
| 8086:0f31 | 17aa:390b | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | i915       | [92D4603EA8](<Tablet/Lenovo/MIIX/MIIX 300-10IBY 80NR/F1574B822916/ARCH/5.6.17/X86_64/92D4603EA8>) |
| 8086:191e | 1028:06e6 | Intel            | HD Graphics 515                      | 6     | i915       | [6430380D5B](<Tablet/Dell/Latitude/Latitude 5179/597547DCB08C/POP!_OS-20.04/5.16.11-76051611-GENERIC/X86_64/6430380D5B>) |
| 8086:191e | 144d:c135 | Intel            | HD Graphics 515                      | 6     | i915       | [3ADAAACD83](<Tablet/Samsung Electronics/Galaxy/Galaxy TabPro S/7232B6211ED3/POP!_OS-21.04/5.13.0-7614-GENERIC/X86_64/3ADAAACD83>) |
| 8086:22b0 | 103c:82f4 | Intel            | Atom/Celeron/Pentium Processor x5... | 6     | i915       | [6CAB74E68A](<Tablet/Hewlett-Packard/x2/x2 210 G2/9F303DEBAE52/XUBUNTU-21.10/5.13.0-28-GENERIC/X86_64/6CAB74E68A>) |
| 8086:5916 | 1028:07a4 | Intel            | HD Graphics 620                      | 6     | i915       | [568757F9F8](<Tablet/Dell/Latitude/Latitude 5285/9BC7EC024B34/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/568757F9F8>) |
| 8086:5916 | 1414:0025 | Intel            | HD Graphics 620                      | 6     | i915       | [ACC1031944](<Tablet/Microsoft/Surface/Surface Laptop/0AAFEF8EFED9/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/ACC1031944>) |
| 8086:5917 | 17aa:2244 | Intel            | UHD Graphics 620                     | 6     | i915       | [F92AE76FED](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJCTO1WW/3D3FB636D7D4/DEVUAN-4/5.10.0-11-AMD64/X86_64/F92AE76FED>) |
| 8086:5917 | 17aa:397a | Intel            | UHD Graphics 620                     | 6     | i915       | [E15A6F0B18](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/9B85342702DA/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/E15A6F0B18>) |
| 8086:591c | 152d:1237 | Intel            | UHD Graphics 615                     | 6     | i915       | [E530D905DA](<Tablet/Microsoft/Surface/Surface Go 2/356E9AC2E762/ARCH/5.15.11-ARCH2-1-SURFACE/X86_64/E530D905DA>) |
| 8086:591e | 103c:828b | Intel            | HD Graphics 615                      | 6     | i915       | [5A85AB6B0F](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/608A6BF05466/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/5A85AB6B0F>) |
| 8086:0f31 | 17aa:221c | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 5     | i915       | [59C522169B](<Tablet/Lenovo/ThinkPad/ThinkPad 8 20BN0036GE/C9BED08A54DA/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/59C522169B>) |
| 8086:22b0 | 1043:1c60 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | i915       | [B2D1B00B0A](<Tablet/ASUSTek Computer/T103/T103HAF/F93497AB5707/ZORIN-12/4.13.0-37-GENERIC/X86_64/B2D1B00B0A>) |
| 8086:5917 | 1028:081d | Intel            | UHD Graphics 620                     | 5     | i915       | [9CFD9C7142](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/39E24435C9D2/ELEMENTARY-6.1/5.13.0-30-GENERIC/X86_64/9CFD9C7142>) |

### Iommu (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15d1 | 1022:15d1 | AMD              | Raven/Raven2 IOMMU                   | 3     |            | [D55F23484E](<Tablet/Microsoft/Surface/Surface Laptop 3/6407F7577C70/ELEMENTARY-6.1/5.16.11-SURFACE/X86_64/D55F23484E>) |
| 1022:1631 | 1022:1631 | AMD              | Renoir/Cezanne IOMMU                 | 3     |            | [C039BD54B8](<Tablet/AYADEVICE/AYA/AYA NEO FOUNDER/49BCDD789BF3/ARCH-ROLLING/5.14.11-ARCH1-1/X86_64/C039BD54B8>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d21 | 8086:7270 | Intel            | Sunrise Point-LP PMC                 | 173   |            | [26A4220432](<Tablet/Microsoft/Surface/Surface Pro 4/5171E94FBA49/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/26A4220432>) |
| 8086:34ef |           | Intel            | Ice Lake-LP DRAM Controller          | 37    |            | [A4E86F6259](<Tablet/Microsoft/Surface/Surface Pro 7/4B1F7148A63A/ZORIN-16/5.16.5-SURFACE/X86_64/A4E86F6259>) |
| 8086:9d21 | 152d:1182 | Intel            | Sunrise Point-LP PMC                 | 20    |            | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:9d21 | 103c:82ca | Intel            | Sunrise Point-LP PMC                 | 10    |            | [BEEB081772](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/945D2246773B/UBUNTU-MATE-20.04/5.13.0-30-GENERIC/X86_64/BEEB081772>) |
| 8086:9d21 | 144d:c14f | Intel            | Sunrise Point-LP PMC                 | 8     |            | [63CAA45089](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12 LTE/F81EBA4C8217/ZORIN-16/5.13.0-30-GENERIC/X86_64/63CAA45089>) |
| 8086:9d21 | 8086:9d21 | Intel            | Sunrise Point-LP PMC                 | 8     |            | [0F05F12004](<Tablet/Teclast/X5/X5 Pro/B130987D6E6A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0F05F12004>) |
| 8086:9d21 | 17aa:3853 | Intel            | Sunrise Point-LP PMC                 | 7     |            | [8B9FA8F425](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/A89FAAAFC012/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/8B9FA8F425>) |
| 8086:9d21 | 1028:06e6 | Intel            | Sunrise Point-LP PMC                 | 6     |            | [6430380D5B](<Tablet/Dell/Latitude/Latitude 5179/597547DCB08C/POP!_OS-20.04/5.16.11-76051611-GENERIC/X86_64/6430380D5B>) |
| 8086:9d21 | 1028:07a4 | Intel            | Sunrise Point-LP PMC                 | 6     |            | [568757F9F8](<Tablet/Dell/Latitude/Latitude 5285/9BC7EC024B34/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/568757F9F8>) |
| 8086:9d21 | 103c:828b | Intel            | Sunrise Point-LP PMC                 | 6     |            | [5A85AB6B0F](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/608A6BF05466/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/5A85AB6B0F>) |
| 8086:9d21 | 144d:c135 | Intel            | Sunrise Point-LP PMC                 | 6     |            | [3ADAAACD83](<Tablet/Samsung Electronics/Galaxy/Galaxy TabPro S/7232B6211ED3/POP!_OS-21.04/5.13.0-7614-GENERIC/X86_64/3ADAAACD83>) |
| 8086:9d21 | 152d:1237 | Intel            | Sunrise Point-LP PMC                 | 6     |            | [E530D905DA](<Tablet/Microsoft/Surface/Surface Go 2/356E9AC2E762/ARCH/5.15.11-ARCH2-1-SURFACE/X86_64/E530D905DA>) |
| 8086:9d21 | 17aa:2244 | Intel            | Sunrise Point-LP PMC                 | 6     |            | [F92AE76FED](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJCTO1WW/3D3FB636D7D4/DEVUAN-4/5.10.0-11-AMD64/X86_64/F92AE76FED>) |
| 8086:9d21 | 1028:081d | Intel            | Sunrise Point-LP PMC                 | 5     |            | [9CFD9C7142](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/39E24435C9D2/ELEMENTARY-6.1/5.13.0-30-GENERIC/X86_64/9CFD9C7142>) |
| 8086:9d21 | 1025:111e | Intel            | Sunrise Point-LP PMC                 | 4     |            | [C6DC41A2A5](<Tablet/Acer/Switch/Switch SA5-271/7F70B3D37585/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C6DC41A2A5>) |
| 8086:9d21 | 1028:06d6 | Intel            | Sunrise Point-LP PMC                 | 4     |            | [14BCC9219C](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-21.10/5.16.10-XANMOD1/X86_64/14BCC9219C>) |
| 8086:9d21 | 1028:07a5 | Intel            | Sunrise Point-LP PMC                 | 4     |            | [78F2672479](<Tablet/Dell/Latitude/Latitude 7285/35CB641DDB78/CLEAR-LINUX-OS-35940/5.16.11-1128.NATIVE/X86_64/78F2672479>) |
| 8086:9d21 | 17aa:2241 | Intel            | Sunrise Point-LP PMC                 | 4     |            | [923CCB09A5](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GHCTO1WW/70707A835AE8/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/923CCB09A5>) |
| 8086:9d21 | 17aa:3829 | Intel            | Sunrise Point-LP PMC                 | 4     |            | [E1BEE3CD30](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/63E5CC1D8A4F/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/E1BEE3CD30>) |
| 8086:a0ef | 17aa:3829 | Intel            | Tiger Lake-LP Shared SRAM            | 4     |            | [047FF4AD80](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/37FF40E14E4D/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/047FF4AD80>) |
| 8086:02ef | 17aa:380d | Intel            | Comet Lake PCH-LP Shared SRAM        | 3     |            | [927ED071B3](<Tablet/Lenovo/Yoga/Yoga Duet IML 2020 82E9/8FFE2F20194E/ARCH-ROLLING/5.16.2-ARCH1-1/X86_64/927ED071B3>) |
| 8086:9d21 | 17aa:3834 | Intel            | Sunrise Point-LP PMC                 | 3     |            | [67E1BDD5F1](<Tablet/Lenovo/MIIX/MIIX 720-12IKB 80VV/F45F8CE4052D/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/67E1BDD5F1>) |
| 8086:9d21 | 17aa:3842 | Intel            | Sunrise Point-LP PMC                 | 3     |            | [D249085990](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/A4295A395509/POP!_OS-21.10/5.15.8-76051508-GENERIC/X86_64/D249085990>) |
| 8086:9d21 | 19e5:3e00 | Intel            | Sunrise Point-LP PMC                 | 3     |            | [904DECFD32](<Tablet/HUAWEI/MateBook/MateBook HZ-W19/F902238EFB24/LMDE-4/4.19.0-17-AMD64/X86_64/904DECFD32>) |
| 8086:a0ef | 8086:7270 | Intel            | Tiger Lake-LP Shared SRAM            | 3     |            | [BD290BC56D](<Tablet/Microsoft/Surface/Surface Laptop Studio/AD9CE584B5E1/MANJARO-21.1.6/5.13.19-2-MANJARO/X86_64/BD290BC56D>) |
| 8086:9d21 | 1025:1171 | Intel            | Sunrise Point-LP PMC                 | 2     |            | [4B0ED624FA](<Tablet/Acer/Switch/Switch SW512-52/8FD5C8AAAFE9/ARCH-ROLLING/5.8.12-ARCH1-1/X86_64/4B0ED624FA>) |
| 8086:9d21 | 103c:82cb | Intel            | Sunrise Point-LP PMC                 | 2     |            | [EFC4C63AC7](<Tablet/Hewlett-Packard/Spectre/Spectre x2 Detachable 12-c0XX/09798ACE135C/DEEPIN-20.2.2/5.10.36-AMD64-DESKTOP/X86_64/EFC4C63AC7>) |
| 8086:9d21 | 103c:8414 | Intel            | Sunrise Point-LP PMC                 | 2     |            | [6EE77ED959](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/3DD573867AA0/UBUNTU-20.04/5.8.0-36-GENERIC/X86_64/6EE77ED959>) |
| 8086:9d21 | 1043:13c0 | Intel            | Sunrise Point-LP PMC                 | 2     |            | [4363CA1BD6](<Tablet/ASUSTek Computer/T303/T303UA/C8223D9D63FE/UBUNTU-20.04/5.4.0-33-GENERIC/X86_64/4363CA1BD6>) |
| 8086:9d21 | 1043:1410 | Intel            | Sunrise Point-LP PMC                 | 2     |            | [C66E4999F0](<Tablet/ASUSTek Computer/T305/T305CA/70CB67E36043/UBUNTU-20.04/5.8.0-50-GENERIC/X86_64/C66E4999F0>) |
| 8086:9d21 | 1043:16c0 | Intel            | Sunrise Point-LP PMC                 | 2     |            | [D33E67BDF4](<Tablet/ASUSTek Computer/T304/T304UA/8F97F461C23D/UBUNTU-20.04/5.4.0-29-GENERIC/X86_64/D33E67BDF4>) |
| 8086:9d21 | 17aa:2243 | Intel            | Sunrise Point-LP PMC                 | 2     |            | [39C0680056](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JB003LMX/2CEEE337E2A9/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/39C0680056>) |
| 8086:9d21 | 1b0a:01d3 | Intel            | Sunrise Point-LP PMC                 | 2     |            | [60C93DDC01](<Tablet/Xplore/iX125/iX125R1/9DCB305AD004/PUPPY_IMPPUP64-9.6.1/5.15.11-LXPUP64/X86_64/60C93DDC01>) |
| 8086:9def | 103c:85b9 | Intel            | Cannon Point-LP Shared SRAM          | 2     |            | [09F8C72D80](<Tablet/Hewlett-Packard/Elite/Elite x2 G4/0472416698D9/UBUNTU-21.04/5.11.0-25-GENERIC/X86_64/09F8C72D80>) |
| 8086:a0ef | 1028:0a45 | Intel            | Tiger Lake-LP Shared SRAM            | 2     |            | [255FFC0493](<Tablet/Dell/Latitude/Latitude 7320 Detachable/B080FA5912AF/KUBUNTU-21.10/5.16.0/X86_64/255FFC0493>) |
| 8086:02ef | 1071:d301 | Intel            | Comet Lake PCH-LP Shared SRAM        | 1     |            | [6F57AB0251](<Tablet/Getac/UX10/UX10G2/9B2D92B11BC9/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/6F57AB0251>) |
| 8086:9d21 | 1028:0702 | Intel            | Sunrise Point-LP PMC                 | 1     |            | [CE9A3F2C74](<Tablet/Dell/XPS/XPS 12 9250/A04CD2743A76/CLEAR-LINUX-OS-35400/5.15.7-1106.NATIVE/X86_64/CE9A3F2C74>) |
| 8086:9d21 | 103c:824c | Intel            | Sunrise Point-LP PMC                 | 1     |            | [A557059CBA](<Tablet/Hewlett-Packard/ZBook/ZBook x2 G4/9B15D9768480/UBUNTU-20.04/5.4.0-54-GENERIC/X86_64/A557059CBA>) |
| 8086:9d21 | 10f7:8338 | Intel            | Sunrise Point-LP PMC                 | 1     |            | [94539C6DB9](<Tablet/Panasonic/CF-33/CF-33-1/AE1D638EDC9E/UBUNTU-12.02/5.11.0-38-GENERIC/X86_64/94539C6DB9>) |
| 8086:a0ef | 1071:a121 | Intel            | Tiger Lake-LP Shared SRAM            | 1     |            | [5D9E3F3501](<Tablet/Getac/K120/K120G2/9B90212BD0E9/UBUNTU-18.04/5.4.0-84-GENERIC/X86_64/5D9E3F3501>) |
| 8086:a0ef | 17aa:508b | Intel            | Tiger Lake-LP Shared SRAM            | 1     |            | [AAC22AF3A1](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UWCTO1WW/3B7CEBE290BA/DEBIAN-TESTING/5.10.19/X86_64/AAC22AF3A1>) |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1919 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 168   | ipu3_imgu  | [26A4220432](<Tablet/Microsoft/Surface/Surface Pro 4/5171E94FBA49/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/26A4220432>) |
| 8086:9d32 | 8086:7270 | Intel            | CSI-2 Host Controller                | 164   | ipu3_cio2  | [26A4220432](<Tablet/Microsoft/Surface/Surface Pro 4/5171E94FBA49/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/26A4220432>) |
| 8086:22b8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 126   | intel_a... | [23FBC9A6EE](<Tablet/RCA/W101/W101AS23T2/BBCA95A1C67D/FEDORA-35/5.16.8-200.FC35.X86_64/X86_64/23FBC9A6EE>) |
| 8086:22b8 | 17aa:38e3 | Intel            | Atom/Celeron/Pentium Processor x5... | 43    | intel_a... | [4758B6520C](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/6D0C35E280B8/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/4758B6520C>) |
| 8086:22b8 | 17aa:3809 | Intel            | Atom/Celeron/Pentium Processor x5... | 40    | intel_a... | [FB183BFD9B](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/056649DD334F/MANJARO/5.15.25-1-MANJARO/X86_64/FB183BFD9B>) |
| 8086:9d32 |           | Intel            | CSI-2 Host Controller                | 31    | ipu3_cio2  | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:8a19 | 8086:7270 | Intel            | Image Signal Processor               | 23    |            | [A4E86F6259](<Tablet/Microsoft/Surface/Surface Pro 7/4B1F7148A63A/ZORIN-16/5.16.5-SURFACE/X86_64/A4E86F6259>) |
| 8086:1919 | 152d:1182 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 20    | ipu3_imgu  | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:22b8 | 1043:13a0 | Intel            | Atom/Celeron/Pentium Processor x5... | 20    | intel_a... | [05983A1E06](<Tablet/ASUSTek Computer/T101/T101HA/AC331E492606/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/05983A1E06>) |
| 8086:22b8 | 103c:827c | Intel            | Atom/Celeron/Pentium Processor x5... | 19    | intel_a... | [9A03FDA057](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/E1DE173C5065/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/9A03FDA057>) |
| 8086:5a88 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    |            | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |
| 8086:22b8 | 1414:0009 | Intel            | Atom/Celeron/Pentium Processor x5... | 16    | intel_a... | [D8EA22EFF5](<Tablet/Microsoft/Surface/Surface 3/DEBCA8820BEF/DEBIAN-TESTING/5.16.11-SURFACE/X86_64/D8EA22EFF5>) |
| 8086:22b8 | 1043:1400 | Intel            | Atom/Celeron/Pentium Processor x5... | 15    | atomisp    | [ECC5AD7332](<Tablet/ASUSTek Computer/T102/T102HA/C13EDC224850/MX-19/4.19.0-18-AMD64/X86_64/ECC5AD7332>) |
| 8086:1919 | 8086:1919 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 12    | ipu3_imgu  | [0F05F12004](<Tablet/Teclast/X5/X5 Pro/B130987D6E6A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0F05F12004>) |
| 8086:1919 | 103c:82ca | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 10    | ipu3_imgu  | [BEEB081772](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/945D2246773B/UBUNTU-MATE-20.04/5.13.0-30-GENERIC/X86_64/BEEB081772>) |
| 8086:9d32 | 103c:82ca | Intel            | CSI-2 Host Controller                | 10    | ipu3_cio2  | [BEEB081772](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/945D2246773B/UBUNTU-MATE-20.04/5.13.0-30-GENERIC/X86_64/BEEB081772>) |
| 8086:1919 | 144d:c14f | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 8     | ipu3_imgu  | [63CAA45089](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12 LTE/F81EBA4C8217/ZORIN-16/5.13.0-30-GENERIC/X86_64/63CAA45089>) |
| 8086:9d32 | 144d:c14f | Intel            | CSI-2 Host Controller                | 8     | ipu3_cio2  | [63CAA45089](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12 LTE/F81EBA4C8217/ZORIN-16/5.13.0-30-GENERIC/X86_64/63CAA45089>) |
| 8086:1919 | 17aa:382f | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 7     | ipu3_imgu  | [8B9FA8F425](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/A89FAAAFC012/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/8B9FA8F425>) |
| 8086:9d32 | 17aa:380c | Intel            | CSI-2 Host Controller                | 7     | ipu3_cio2  | [8B9FA8F425](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/A89FAAAFC012/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/8B9FA8F425>) |
| 8086:9d32 | 8086:9d32 | Intel            | CSI-2 Host Controller                | 7     | ipu3_cio2  | [0F05F12004](<Tablet/Teclast/X5/X5 Pro/B130987D6E6A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0F05F12004>) |
| 1022:15e2 | 1022:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 6     | snd_pci... | [D55F23484E](<Tablet/Microsoft/Surface/Surface Laptop 3/6407F7577C70/ELEMENTARY-6.1/5.16.11-SURFACE/X86_64/D55F23484E>) |
| 8086:1919 | 1028:06e6 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 6     | ipu3_imgu  | [6430380D5B](<Tablet/Dell/Latitude/Latitude 5179/597547DCB08C/POP!_OS-20.04/5.16.11-76051611-GENERIC/X86_64/6430380D5B>) |
| 8086:1919 | 1028:07a4 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 6     | ipu3_imgu  | [568757F9F8](<Tablet/Dell/Latitude/Latitude 5285/9BC7EC024B34/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/568757F9F8>) |
| 8086:1919 | 103c:828b | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 6     | ipu3_imgu  | [5A85AB6B0F](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/608A6BF05466/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/5A85AB6B0F>) |
| 8086:1919 | 144d:c135 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 6     | ipu3_imgu  | [3ADAAACD83](<Tablet/Samsung Electronics/Galaxy/Galaxy TabPro S/7232B6211ED3/POP!_OS-21.04/5.13.0-7614-GENERIC/X86_64/3ADAAACD83>) |
| 8086:1919 | 152d:1237 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 6     | ipu3_imgu  | [E530D905DA](<Tablet/Microsoft/Surface/Surface Go 2/356E9AC2E762/ARCH/5.15.11-ARCH2-1-SURFACE/X86_64/E530D905DA>) |
| 8086:1919 | 17aa:2244 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 6     | ipu3_imgu  | [F92AE76FED](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJCTO1WW/3D3FB636D7D4/DEVUAN-4/5.10.0-11-AMD64/X86_64/F92AE76FED>) |
| 8086:22b8 | 103c:82f4 | Intel            | Atom/Celeron/Pentium Processor x5... | 6     | atomisp    | [6CAB74E68A](<Tablet/Hewlett-Packard/x2/x2 210 G2/9F303DEBAE52/XUBUNTU-21.10/5.13.0-28-GENERIC/X86_64/6CAB74E68A>) |
| 8086:9d32 | 1028:06e6 | Intel            | CSI-2 Host Controller                | 6     | ipu3_cio2  | [6430380D5B](<Tablet/Dell/Latitude/Latitude 5179/597547DCB08C/POP!_OS-20.04/5.16.11-76051611-GENERIC/X86_64/6430380D5B>) |
| 8086:9d32 | 1028:07a4 | Intel            | CSI-2 Host Controller                | 6     | ipu3_cio2  | [568757F9F8](<Tablet/Dell/Latitude/Latitude 5285/9BC7EC024B34/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/568757F9F8>) |
| 8086:9d32 | 103c:828b | Intel            | CSI-2 Host Controller                | 6     | ipu3_cio2  | [5A85AB6B0F](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/608A6BF05466/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/5A85AB6B0F>) |
| 8086:9d32 | 144d:c135 | Intel            | CSI-2 Host Controller                | 6     | ipu3_cio2  | [3ADAAACD83](<Tablet/Samsung Electronics/Galaxy/Galaxy TabPro S/7232B6211ED3/POP!_OS-21.04/5.13.0-7614-GENERIC/X86_64/3ADAAACD83>) |
| 8086:9d32 | 17aa:2244 | Intel            | CSI-2 Host Controller                | 6     | ipu3_cio2  | [F92AE76FED](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJCTO1WW/3D3FB636D7D4/DEVUAN-4/5.10.0-11-AMD64/X86_64/F92AE76FED>) |
| 8086:1919 | 1028:081d | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 5     | ipu3_imgu  | [9CFD9C7142](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/39E24435C9D2/ELEMENTARY-6.1/5.13.0-30-GENERIC/X86_64/9CFD9C7142>) |
| 8086:22b8 | 1043:1c60 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | intel_a... | [B2D1B00B0A](<Tablet/ASUSTek Computer/T103/T103HAF/F93497AB5707/ZORIN-12/4.13.0-37-GENERIC/X86_64/B2D1B00B0A>) |
| 8086:9d32 | 1028:081d | Intel            | CSI-2 Host Controller                | 5     | ipu3_cio2  | [9CFD9C7142](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/39E24435C9D2/ELEMENTARY-6.1/5.13.0-30-GENERIC/X86_64/9CFD9C7142>) |
| 8086:1919 | 1025:111e | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 4     | ipu3_imgu  | [C6DC41A2A5](<Tablet/Acer/Switch/Switch SA5-271/7F70B3D37585/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C6DC41A2A5>) |
| 8086:1919 | 1028:06d6 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 4     | ipu3_imgu  | [14BCC9219C](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-21.10/5.16.10-XANMOD1/X86_64/14BCC9219C>) |
| 8086:1919 | 1028:07a5 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 4     | ipu3_imgu  | [78F2672479](<Tablet/Dell/Latitude/Latitude 7285/35CB641DDB78/CLEAR-LINUX-OS-35940/5.16.11-1128.NATIVE/X86_64/78F2672479>) |
| 8086:1919 | 17aa:2241 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 4     | ipu3_imgu  | [923CCB09A5](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GHCTO1WW/70707A835AE8/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/923CCB09A5>) |
| 8086:9a19 | 17aa:382f | Intel            | Multimedia controller                | 4     |            | [047FF4AD80](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/37FF40E14E4D/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/047FF4AD80>) |
| 8086:9d32 | 1028:06d6 | Intel            | CSI-2 Host Controller                | 4     | ipu3_cio2  | [14BCC9219C](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-21.10/5.16.10-XANMOD1/X86_64/14BCC9219C>) |
| 8086:9d32 | 1028:07a5 | Intel            | CSI-2 Host Controller                | 4     | ipu3_cio2  | [78F2672479](<Tablet/Dell/Latitude/Latitude 7285/35CB641DDB78/CLEAR-LINUX-OS-35940/5.16.11-1128.NATIVE/X86_64/78F2672479>) |
| 8086:9d32 | 17aa:2241 | Intel            | CSI-2 Host Controller                | 4     | ipu3_cio2  | [923CCB09A5](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GHCTO1WW/70707A835AE8/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/923CCB09A5>) |
| 8086:9d32 | 17aa:3804 | Intel            | CSI-2 Host Controller                | 4     | ipu3_cio2  | [E1BEE3CD30](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/63E5CC1D8A4F/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/E1BEE3CD30>) |
| 8086:0f38 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     | atomisp... | [F19C34B72D](<Tablet/Lenovo/Yoga/Yoga/4DDD6802F5A2/ANDROID/3.10.20-X86_64_BYT-G9FF829D/X86_64/F19C34B72D>) |
| 8086:1919 | 17aa:3825 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 3     | ipu3_imgu  | [67E1BDD5F1](<Tablet/Lenovo/MIIX/MIIX 720-12IKB 80VV/F45F8CE4052D/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/67E1BDD5F1>) |
| 8086:1919 | 17aa:382c | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 3     | ipu3_imgu  | [D249085990](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/A4295A395509/POP!_OS-21.10/5.15.8-76051508-GENERIC/X86_64/D249085990>) |
| 8086:1919 | 19e5:3e00 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 3     | ipu3_imgu  | [904DECFD32](<Tablet/HUAWEI/MateBook/MateBook HZ-W19/F902238EFB24/LMDE-4/4.19.0-17-AMD64/X86_64/904DECFD32>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:8136 | 1019:99fa | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 6     | r8169      | [585EA8C657](<Tablet/BANGHO/Suma/Suma 1025/C11649ABA4A3/ELEMENTARY-6.1/5.13.0-28-GENERIC/X86_64/585EA8C657>) |
| 10ec:8168 | 1019:99fa | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 4     | r8169      | [A2B7A04DFA](<Tablet/Intel/powered/powered classmate PC/E3EDE14D59EF/LINUXMINT-20.2/5.4.0-100-GENERIC/X86_64/A2B7A04DFA>) |
| 10ec:8136 | 1854:0211 | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 2     | r8169      | [44AF16AC16](<Tablet/LG Electronics/15U340/15U340-L.BK55P1/96572D02BF5F/LINUXMINT-20/5.4.0-42-GENERIC/X86_64/44AF16AC16>) |
| 10ec:8168 | 1509:7018 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 2     | r8169      | [9347717861](<Tablet/Xplore/iX101/iX101B1/988A604FB8AB/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/9347717861>) |
| 8086:156f | 1b0a:01d3 | Intel            | Ethernet Connection I219-LM          | 2     | e1000e     | [60C93DDC01](<Tablet/Xplore/iX125/iX125R1/9DCB305AD004/PUPPY_IMPPUP64-9.6.1/5.15.11-LXPUP64/X86_64/60C93DDC01>) |
| 10ec:8136 | 1019:99da | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 1     | r8169      | [90B1418DAB](<Tablet/BANGHO/Suma/Suma 1025/09043A0DA8CE/UBUNTU-18.04/5.3.0-28-GENERIC/X86_64/90B1418DAB>) |
| 10ec:8136 | 10ec:0123 | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 1     | r8169      | [BA303FB8FF](<Tablet/BANGHO/Suma/Suma 1025/C706A46832B0/UBUNTU-18.04/5.0.0-32-GENERIC/X86_64/BA303FB8FF>) |
| 10ec:8136 | 1558:5470 | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 1     | r8169      | [DD65C5ABF7](<Tablet/Lanix/Neuron/Neuron A/9C81E684C8A4/ARCH-ROLLING/5.8.14-ARCH1-1/X86_64/DD65C5ABF7>) |
| 8086:15d7 | 10f7:8338 | Intel            | Ethernet Connection (4) I219-LM      | 1     | e1000e     | [94539C6DB9](<Tablet/Panasonic/CF-33/CF-33-1/AE1D638EDC9E/UBUNTU-12.02/5.11.0-38-GENERIC/X86_64/94539C6DB9>) |
| 8086:15fb | 1071:a121 | Intel            | Ethernet Connection (13) I219-LM     | 1     |            | [5D9E3F3501](<Tablet/Getac/K120/K120G2/9B90212BD0E9/UBUNTU-18.04/5.4.0-84-GENERIC/X86_64/5D9E3F3501>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:3165 | 8086:8010 | Intel            | Wireless 3165                        | 75    | iwlwifi    | [4758B6520C](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/6D0C35E280B8/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/4758B6520C>) |
| 11ab:2b38 | 0003:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 54    | mwifiex... | [26A4220432](<Tablet/Microsoft/Surface/Surface Pro 4/5171E94FBA49/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/26A4220432>) |
| 11ab:2b38 | 0001:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 51    | mwifiex... | [92F8B5CBFA](<Tablet/Microsoft/Surface/Surface Pro 3/0558715ED322/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/92F8B5CBFA>) |
| 11ab:2b38 | 0008:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 47    | mwifiex... | [50420D6D58](<Tablet/Microsoft/Surface/Surface Pro 6/DE921958CD9C/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/50420D6D58>) |
| 168c:0042 | 1a3b:2a51 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 41    | ath10k_pci | [05983A1E06](<Tablet/ASUSTek Computer/T101/T101HA/AC331E492606/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/05983A1E06>) |
| 8086:34f0 | 8086:0074 | Intel            | Ice Lake-LP PCH CNVi WiFi            | 37    | iwlwifi    | [A4E86F6259](<Tablet/Microsoft/Surface/Surface Pro 7/4B1F7148A63A/ZORIN-16/5.16.5-SURFACE/X86_64/A4E86F6259>) |
| 11ab:2b38 | 0004:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 31    | mwifiex... | [DC0E450D2C](<Tablet/Microsoft/Surface/Surface Book/A32707B0D7C9/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/DC0E450D2C>) |
| 8086:095a | 8086:9010 | Intel            | Wireless 7265                        | 22    | iwlwifi    | [6CAB74E68A](<Tablet/Hewlett-Packard/x2/x2 210 G2/9F303DEBAE52/XUBUNTU-21.10/5.13.0-28-GENERIC/X86_64/6CAB74E68A>) |
| 168c:003e | 168c:3370 | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 20    | ath10k_pci | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 11ab:2b38 | 0002:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 15    | mwifiex... | [D8EA22EFF5](<Tablet/Microsoft/Surface/Surface 3/DEBCA8820BEF/DEBIAN-TESTING/5.16.11-SURFACE/X86_64/D8EA22EFF5>) |
| 11ab:2b38 | 0006:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 14    | mwifiex... | [ACC1031944](<Tablet/Microsoft/Surface/Surface Laptop/0AAFEF8EFED9/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/ACC1031944>) |
| 8086:31dc | 8086:0264 | Intel            | Gemini Lake PCH CNVi WiFi            | 14    | iwlwifi    | [6350A05DF4](<Tablet/Linx/LAMINALTT8/LAMINALTT8W4G-HBN/3A8211B5B143/ARCH-ROLLING/5.16.3-ARCH1-1/X86_64/6350A05DF4>) |
| 8086:24fd | 8086:9010 | Intel            | Wireless 8265 / 8275                 | 13    | iwlwifi    | [6EE77ED959](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/3DD573867AA0/UBUNTU-20.04/5.8.0-36-GENERIC/X86_64/6EE77ED959>) |
| 8086:3165 | 8086:8110 | Intel            | Wireless 3165                        | 13    | iwlwifi    | [0F05F12004](<Tablet/Teclast/X5/X5 Pro/B130987D6E6A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0F05F12004>) |
| 10ec:b723 | 10ec:b737 | Realtek Semic... | RTL8723BE PCIe Wireless Network A... | 11    | rtl8723be  | [A2B7A04DFA](<Tablet/Intel/powered/powered classmate PC/E3EDE14D59EF/LINUXMINT-20.2/5.4.0-100-GENERIC/X86_64/A2B7A04DFA>) |
| 168c:002b | 105b:e031 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 11    | ath9k      | [5984A91751](<Tablet/Acer/Iconia/Iconia Tab W500/99578EB02374/ELEMENTARY-6/5.11.0-40-GENERIC/X86_64/5984A91751>) |
| 11ab:2b38 | 0007:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 10    | mwifiex... | [B4A346E899](<Tablet/Microsoft/Surface/Surface Book 2/0BE3401C9A96/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/B4A346E899>) |
| 11ab:2b38 | 0009:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 10    | mwifiex... | [730558C6BD](<Tablet/Microsoft/Surface/Surface Book 2/451432DF4DF7/ELEMENTARY-6.1/5.15.6-SURFACE/X86_64/730558C6BD>) |
| 8086:24f3 | 8086:0150 | Intel            | Wireless 8260                        | 10    | iwlwifi    | [6430380D5B](<Tablet/Dell/Latitude/Latitude 5179/597547DCB08C/POP!_OS-20.04/5.16.11-76051611-GENERIC/X86_64/6430380D5B>) |
| 8086:24fd | 8086:0150 | Intel            | Wireless 8265 / 8275                 | 10    | iwlwifi    | [9CFD9C7142](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/39E24435C9D2/ELEMENTARY-6.1/5.13.0-30-GENERIC/X86_64/9CFD9C7142>) |
| 8086:24fd | 8086:1010 | Intel            | Wireless 8265 / 8275                 | 9     | iwlwifi    | [BEEB081772](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/945D2246773B/UBUNTU-MATE-20.04/5.13.0-30-GENERIC/X86_64/BEEB081772>) |
| 8086:2723 | 8086:008c | Intel            | Wi-Fi 6 AX200                        | 9     | iwlwifi    | [E530D905DA](<Tablet/Microsoft/Surface/Surface Go 2/356E9AC2E762/ARCH/5.15.11-ARCH2-1-SURFACE/X86_64/E530D905DA>) |
| 10ec:c821 | 10ec:c821 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 8     | rtw88_8... | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 168c:003e | 144d:c14f | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 8     | ath10k_pci | [63CAA45089](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12 LTE/F81EBA4C8217/ZORIN-16/5.13.0-30-GENERIC/X86_64/63CAA45089>) |
| 8086:24f3 | 8086:8110 | Intel            | Wireless 8260                        | 8     | iwlwifi    | [923CCB09A5](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GHCTO1WW/70707A835AE8/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/923CCB09A5>) |
| 8086:a0f0 | 8086:0074 | Intel            | Wi-Fi 6 AX201                        | 7     | iwlwifi    | [047FF4AD80](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/37FF40E14E4D/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/047FF4AD80>) |
| 168c:003e | 144d:c135 | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 6     | ath10k_pci | [3ADAAACD83](<Tablet/Samsung Electronics/Galaxy/Galaxy TabPro S/7232B6211ED3/POP!_OS-21.04/5.13.0-7614-GENERIC/X86_64/3ADAAACD83>) |
| 8086:08b3 | 8086:8070 | Intel            | Wireless 3160                        | 6     | iwlwifi    | [C61A96D514](<Tablet/Medion/P/P2212T/71C4E4B2F18A/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/C61A96D514>) |
| 8086:24fd | 8086:0010 | Intel            | Wireless 8265 / 8275                 | 5     | iwlwifi    | [47D816D00F](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/C9B530F954DE/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/47D816D00F>) |
| 8086:24fd | 8086:8110 | Intel            | Wireless 8265 / 8275                 | 5     | iwlwifi    | [39C0680056](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JB003LMX/2CEEE337E2A9/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/39C0680056>) |
| 8086:24f3 | 8086:1010 | Intel            | Wireless 8260                        | 4     | iwlwifi    | [E1BEE3CD30](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/63E5CC1D8A4F/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/E1BEE3CD30>) |
| 8086:24fd | 8086:0050 | Intel            | Wireless 8265 / 8275                 | 4     | iwlwifi    | [78F2672479](<Tablet/Dell/Latitude/Latitude 7285/35CB641DDB78/CLEAR-LINUX-OS-35940/5.16.11-1128.NATIVE/X86_64/78F2672479>) |
| 14e4:43ec | 105b:e095 | Broadcom         | BCM4356 802.11ac Wireless Network... | 3     | brcmfmac   | [42B9111B9B](<Tablet/Lenovo/ThinkPad/ThinkPad 10 2nd 20E4S0UD01/9194D3407BFF/POP!_OS-20.10/5.11.0-7614-GENERIC/X86_64/42B9111B9B>) |
| 14e4:43ec | 19e5:3100 | Broadcom         | BCM4356 802.11ac Wireless Network... | 3     | brcmfmac   | [904DECFD32](<Tablet/HUAWEI/MateBook/MateBook HZ-W19/F902238EFB24/LMDE-4/4.19.0-17-AMD64/X86_64/904DECFD32>) |
| 168c:0034 | 17aa:3214 | Qualcomm Atheros | AR9462 Wireless Network Adapter      | 3     | ath9k      | [2D356053D3](<Tablet/Lenovo/MIIX/MIIX 2 11 20327/880F55D78695/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/2D356053D3>) |
| 168c:003e | 045e:0001 | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 3     | ath10k_pci | [D55F23484E](<Tablet/Microsoft/Surface/Surface Laptop 3/6407F7577C70/ELEMENTARY-6.1/5.16.11-SURFACE/X86_64/D55F23484E>) |
| 168c:0042 | 1a3b:2b51 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 3     | ath10k_pci | [DCA4D50A5C](<Tablet/Teclast/X6/X6 plus/C159F9AADE83/MANJARO/5.15.16-1-MANJARO/X86_64/DCA4D50A5C>) |
| 8086:02f0 | 8086:0074 | Intel            | Comet Lake PCH-LP CNVi WiFi          | 3     | iwlwifi    | [927ED071B3](<Tablet/Lenovo/Yoga/Yoga Duet IML 2020 82E9/8FFE2F20194E/ARCH-ROLLING/5.16.2-ARCH1-1/X86_64/927ED071B3>) |
| 8086:088e | 8086:4060 | Intel            | Centrino Advanced-N 6235             | 3     | iwlwifi    | [06F11C0449](<Tablet/Panasonic/FZ-G1/FZ-G1ASH39E3/6F2FB083615E/ELEMENTARY-6/5.11.0-37-GENERIC/X86_64/06F11C0449>) |
| 8086:24fd | 8086:8010 | Intel            | Wireless 8265 / 8275                 | 3     | iwlwifi    | [A557059CBA](<Tablet/Hewlett-Packard/ZBook/ZBook x2 G4/9B15D9768480/UBUNTU-20.04/5.4.0-54-GENERIC/X86_64/A557059CBA>) |
| 8086:24fd | 8086:9110 | Intel            | Wireless 8265 / 8275                 | 3     | iwlwifi    | [F92AE76FED](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJCTO1WW/3D3FB636D7D4/DEVUAN-4/5.10.0-11-AMD64/X86_64/F92AE76FED>) |
| 8086:3166 | 8086:4210 | Intel            | Dual Band Wireless-AC 3165 Plus B... | 3     | iwlwifi    | [1DD80D33E5](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/F73B26475AA0/UBUNTU-18.04/4.18.0-15-GENERIC/X86_64/1DD80D33E5>) |
| 14e4:43a0 | 106b:0117 | Broadcom Limited | BCM4360 802.11ac Wireless Network... | 2     | bcma       | [9E5A5DC6CF](<Tablet/Microsoft/Surface/Surface Pro 6/DE921958CD9C/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/9E5A5DC6CF>) |
| 168c:003e | 105b:e09d | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 2     | ath10k_pci | [2D71938FC4](<Tablet/Acer/Switch/Switch SA5-271/41C4B2CD6934/NOVOS-31/5.3.16-300.FC31.X86_64/X86_64/2D71938FC4>) |
| 168c:003e | 11ad:0807 | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 2     | ath10k_pci | [C6DC41A2A5](<Tablet/Acer/Switch/Switch SA5-271/7F70B3D37585/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C6DC41A2A5>) |
| 168c:003e | 17aa:0827 | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 2     | ath10k_pci | [E15A6F0B18](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/9B85342702DA/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/E15A6F0B18>) |
| 168c:0042 | 17aa:4025 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 2     | ath10k_pci | [851F20CB74](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGM 81H3/9A1BA892E7C8/KUBUNTU-20.04/5.8.0-55-GENERIC/X86_64/851F20CB74>) |
| 8086:08b1 | 8086:4070 | Intel            | Wireless 7260                        | 2     | iwlwifi    | [9347717861](<Tablet/Xplore/iX101/iX101B1/988A604FB8AB/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/9347717861>) |
| 8086:08b3 | 8086:0070 | Intel            | Wireless 3160                        | 2     | iwlwifi    | [44AF16AC16](<Tablet/LG Electronics/15U340/15U340-L.BK55P1/96572D02BF5F/LINUXMINT-20/5.4.0-42-GENERIC/X86_64/44AF16AC16>) |
| 8086:095a | 8086:9110 | Intel            | Wireless 7265                        | 2     | iwlwifi    | [4363CA1BD6](<Tablet/ASUSTek Computer/T303/T303UA/C8223D9D63FE/UBUNTU-20.04/5.4.0-33-GENERIC/X86_64/4363CA1BD6>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1533 | ffff:0000 | Intel            | I210 Gigabit Network Connection      | 2     | igb        | [49D345EC0B](<Tablet/Xplore/iX101/iX101L1/1592B2F5F479/UBUNTU-20.04/5.6.0-1028-OEM/X86_64/49D345EC0B>) |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d35 | 8086:7270 | Intel            | Sunrise Point-LP Integrated Senso... | 72    | intel_i... | [50420D6D58](<Tablet/Microsoft/Surface/Surface Pro 6/DE921958CD9C/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/50420D6D58>) |
| 8086:22d8 | 103c:827c | Intel            | Integrated Sensor Solution           | 20    | intel_i... | [9A03FDA057](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/E1DE173C5065/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/9A03FDA057>) |
| 8086:22d8 | 1043:13a0 | Intel            | Integrated Sensor Solution           | 20    | intel_i... | [05983A1E06](<Tablet/ASUSTek Computer/T101/T101HA/AC331E492606/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/05983A1E06>) |
| 8086:9d35 | 152d:1182 | Intel            | Sunrise Point-LP Integrated Senso... | 20    | intel_i... | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:22d8 | 1043:1400 | Intel            | Integrated Sensor Solution           | 16    | intel_i... | [ECC5AD7332](<Tablet/ASUSTek Computer/T102/T102HA/C13EDC224850/MX-19/4.19.0-18-AMD64/X86_64/ECC5AD7332>) |
| 8086:9d35 | 103c:82ca | Intel            | Sunrise Point-LP Integrated Senso... | 10    | intel_i... | [BEEB081772](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/945D2246773B/UBUNTU-MATE-20.04/5.13.0-30-GENERIC/X86_64/BEEB081772>) |
| 8086:9d35 | 17aa:3807 | Intel            | Sunrise Point-LP Integrated Senso... | 7     | intel_i... | [8B9FA8F425](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/A89FAAAFC012/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/8B9FA8F425>) |
| 8086:22d8 | 103c:82f4 | Intel            | Integrated Sensor Solution           | 6     | intel_i... | [6CAB74E68A](<Tablet/Hewlett-Packard/x2/x2 210 G2/9F303DEBAE52/XUBUNTU-21.10/5.13.0-28-GENERIC/X86_64/6CAB74E68A>) |
| 8086:9d35 | 1028:06e6 | Intel            | Sunrise Point-LP Integrated Senso... | 6     | intel_i... | [6430380D5B](<Tablet/Dell/Latitude/Latitude 5179/597547DCB08C/POP!_OS-20.04/5.16.11-76051611-GENERIC/X86_64/6430380D5B>) |
| 8086:9d35 | 1028:07a4 | Intel            | Sunrise Point-LP Integrated Senso... | 6     | intel_i... | [568757F9F8](<Tablet/Dell/Latitude/Latitude 5285/9BC7EC024B34/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/568757F9F8>) |
| 8086:9d35 | 103c:828b | Intel            | Sunrise Point-LP Integrated Senso... | 6     | intel_i... | [5A85AB6B0F](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/608A6BF05466/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/5A85AB6B0F>) |
| 8086:9d35 | 152d:1237 | Intel            | Sunrise Point-LP Integrated Senso... | 6     | intel_i... | [E530D905DA](<Tablet/Microsoft/Surface/Surface Go 2/356E9AC2E762/ARCH/5.15.11-ARCH2-1-SURFACE/X86_64/E530D905DA>) |
| 8086:9d35 | 17aa:2244 | Intel            | Sunrise Point-LP Integrated Senso... | 6     | intel_i... | [F92AE76FED](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJCTO1WW/3D3FB636D7D4/DEVUAN-4/5.10.0-11-AMD64/X86_64/F92AE76FED>) |
| 8086:22d8 | 1043:1c60 | Intel            | Integrated Sensor Solution           | 5     | intel_i... | [B2D1B00B0A](<Tablet/ASUSTek Computer/T103/T103HAF/F93497AB5707/ZORIN-12/4.13.0-37-GENERIC/X86_64/B2D1B00B0A>) |
| 8086:9d35 | 1028:081d | Intel            | Sunrise Point-LP Integrated Senso... | 5     | intel_i... | [9CFD9C7142](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/39E24435C9D2/ELEMENTARY-6.1/5.13.0-30-GENERIC/X86_64/9CFD9C7142>) |
| 8086:9d35 | 1025:111e | Intel            | Sunrise Point-LP Integrated Senso... | 4     | intel_i... | [C6DC41A2A5](<Tablet/Acer/Switch/Switch SA5-271/7F70B3D37585/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C6DC41A2A5>) |
| 8086:9d35 | 1028:06d6 | Intel            | Sunrise Point-LP Integrated Senso... | 4     | intel_i... | [14BCC9219C](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-21.10/5.16.10-XANMOD1/X86_64/14BCC9219C>) |
| 8086:9d35 | 1028:07a5 | Intel            | Sunrise Point-LP Integrated Senso... | 4     | intel_i... | [78F2672479](<Tablet/Dell/Latitude/Latitude 7285/35CB641DDB78/CLEAR-LINUX-OS-35940/5.16.11-1128.NATIVE/X86_64/78F2672479>) |
| 8086:9d35 | 17aa:2241 | Intel            | Sunrise Point-LP Integrated Senso... | 4     | intel_i... | [923CCB09A5](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GHCTO1WW/70707A835AE8/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/923CCB09A5>) |
| 8086:9d35 | 8086:9d35 | Intel            | Sunrise Point-LP Integrated Senso... | 4     | intel_i... | [C66E4999F0](<Tablet/ASUSTek Computer/T305/T305CA/70CB67E36043/UBUNTU-20.04/5.8.0-50-GENERIC/X86_64/C66E4999F0>) |
| 1022:15e6 | 1022:15e4 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 3     | i2c_amd... | [D55F23484E](<Tablet/Microsoft/Surface/Surface Laptop 3/6407F7577C70/ELEMENTARY-6.1/5.16.11-SURFACE/X86_64/D55F23484E>) |
| 8086:22d8 | 8086:7270 | Intel            | Integrated Sensor Solution           | 3     | intel_i... | [42B9111B9B](<Tablet/Lenovo/ThinkPad/ThinkPad 10 2nd 20E4S0UD01/9194D3407BFF/POP!_OS-20.10/5.11.0-7614-GENERIC/X86_64/42B9111B9B>) |
| 8086:9d35 | 19e5:3e00 | Intel            | Sunrise Point-LP Integrated Senso... | 3     | intel_i... | [904DECFD32](<Tablet/HUAWEI/MateBook/MateBook HZ-W19/F902238EFB24/LMDE-4/4.19.0-17-AMD64/X86_64/904DECFD32>) |
| 8086:9d35 | 1025:1171 | Intel            | Sunrise Point-LP Integrated Senso... | 2     | intel_i... | [4B0ED624FA](<Tablet/Acer/Switch/Switch SW512-52/8FD5C8AAAFE9/ARCH-ROLLING/5.8.12-ARCH1-1/X86_64/4B0ED624FA>) |
| 8086:9d35 | 103c:82cb | Intel            | Sunrise Point-LP Integrated Senso... | 2     | intel_i... | [EFC4C63AC7](<Tablet/Hewlett-Packard/Spectre/Spectre x2 Detachable 12-c0XX/09798ACE135C/DEEPIN-20.2.2/5.10.36-AMD64-DESKTOP/X86_64/EFC4C63AC7>) |
| 8086:9d35 | 103c:8414 | Intel            | Sunrise Point-LP Integrated Senso... | 2     | intel_i... | [6EE77ED959](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/3DD573867AA0/UBUNTU-20.04/5.8.0-36-GENERIC/X86_64/6EE77ED959>) |
| 8086:9d35 | 1043:13c0 | Intel            | Sunrise Point-LP Integrated Senso... | 2     | intel_i... | [4363CA1BD6](<Tablet/ASUSTek Computer/T303/T303UA/C8223D9D63FE/UBUNTU-20.04/5.4.0-33-GENERIC/X86_64/4363CA1BD6>) |
| 8086:9d35 | 17aa:2243 | Intel            | Sunrise Point-LP Integrated Senso... | 2     | intel_i... | [39C0680056](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JB003LMX/2CEEE337E2A9/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/39C0680056>) |
| 8086:9d24 |           | Intel            | Skylake-U/Y SPI Controller           | 1     |            | [72CCAD3AA6](<Tablet/Google/Soraka/Soraka/9F4CCB101BA6/KUBUNTU-20.04/5.4.0-90-GENERIC/X86_64/72CCAD3AA6>) |
| 8086:9d35 | 1028:0702 | Intel            | Sunrise Point-LP Integrated Senso... | 1     | intel_i... | [CE9A3F2C74](<Tablet/Dell/XPS/XPS 12 9250/A04CD2743A76/CLEAR-LINUX-OS-35400/5.15.7-1106.NATIVE/X86_64/CE9A3F2C74>) |
| 8086:9d35 | 103c:824c | Intel            | Sunrise Point-LP Integrated Senso... | 1     | intel_i... | [A557059CBA](<Tablet/Hewlett-Packard/ZBook/ZBook x2 G4/9B15D9768480/UBUNTU-20.04/5.4.0-54-GENERIC/X86_64/A557059CBA>) |
| 8086:9d35 | 10f7:8338 | Intel            | Sunrise Point-LP Integrated Senso... | 1     | intel_i... | [94539C6DB9](<Tablet/Panasonic/CF-33/CF-33-1/AE1D638EDC9E/UBUNTU-12.02/5.11.0-38-GENERIC/X86_64/94539C6DB9>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:31d0 | 8086:7270 | Intel            | SD Host Controller                   | 25    | sdhci_pci  | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:31cc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 22    | sdhci_pci  | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:5aca | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 21    | sdhci_pci  | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 21    | sdhci_pci  | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |
| 8086:5ad0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 15    | sdhci_pci  | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |
| 8086:31cc | 17aa:381f | Intel            | Celeron/Pentium Silver Processor ... | 8     | sdhci_pci  | [C9D8BB9BD9](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGM 81H3/689B95560E77/MANJARO-21.2.3/5.16.7-1-MANJARO/X86_64/C9D8BB9BD9>) |
| 8086:9d2b | 8086:9d2b | Intel            | Skylake-U/Y SCC: eMMC                | 8     | sdhci_pci  | [0F05F12004](<Tablet/Teclast/X5/X5 Pro/B130987D6E6A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0F05F12004>) |
| 8086:9d2d | 144d:c14f | Intel            | Sunrise Point-LP Secure Digital I... | 8     | sdhci_pci  | [63CAA45089](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12 LTE/F81EBA4C8217/ZORIN-16/5.13.0-30-GENERIC/X86_64/63CAA45089>) |
| 8086:9d2d | 8086:9d2d | Intel            | Sunrise Point-LP Secure Digital I... | 8     | sdhci_pci  | [0F05F12004](<Tablet/Teclast/X5/X5 Pro/B130987D6E6A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0F05F12004>) |
| 10ec:5209 | 10ec:5209 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 3     | rtsx_pci   | [44AF16AC16](<Tablet/LG Electronics/15U340/15U340-L.BK55P1/96572D02BF5F/LINUXMINT-20/5.4.0-42-GENERIC/X86_64/44AF16AC16>) |
| 1217:8621 | 17aa:3801 | O2 Micro         | SD/MMC Card Reader Controller        | 3     | sdhci_pci  | [67E1BDD5F1](<Tablet/Lenovo/MIIX/MIIX 720-12IKB 80VV/F45F8CE4052D/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/67E1BDD5F1>) |
| 1217:8621 | 17aa:3822 | O2 Micro         | SD/MMC Card Reader Controller        | 3     | sdhci_pci  | [927ED071B3](<Tablet/Lenovo/Yoga/Yoga Duet IML 2020 82E9/8FFE2F20194E/ARCH-ROLLING/5.16.2-ARCH1-1/X86_64/927ED071B3>) |
| 8086:5aca | 8086:5aca | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | sdhci_pci  | [07C752AA8C](<Tablet/ZoomSmart/A/A1002/F1BBB3E02B52/ROSA-2019.05/5.4.60-NICKEL-2ROSA2019.05-X86_64/X86_64/07C752AA8C>) |
| 8086:5acc | 8086:5acc | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | sdhci_pci  | [07C752AA8C](<Tablet/ZoomSmart/A/A1002/F1BBB3E02B52/ROSA-2019.05/5.4.60-NICKEL-2ROSA2019.05-X86_64/X86_64/07C752AA8C>) |
| 8086:5ad0 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | sdhci_pci  | [07C752AA8C](<Tablet/ZoomSmart/A/A1002/F1BBB3E02B52/ROSA-2019.05/5.4.60-NICKEL-2ROSA2019.05-X86_64/X86_64/07C752AA8C>) |
| 8086:9d2b | 152d:1182 | Intel            | Skylake-U/Y SCC: eMMC                | 3     | sdhci_pci  | [4D43BCA615](<Tablet/Microsoft/Surface/Surface Go/F8CB5F6F7B97/DEBIAN-11/5.10.0-8-AMD64/X86_64/4D43BCA615>) |
| 8086:0f16 | 1509:7018 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | sdhci_pci  | [9347717861](<Tablet/Xplore/iX101/iX101B1/988A604FB8AB/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/9347717861>) |
| 8086:9d2b | 8086:7270 | Intel            | Skylake-U/Y SCC: eMMC                | 2     | sdhci_pci  | [E9C76DBCA4](<Tablet/Microsoft/Surface/Surface Go 3/B8A90451B7E4/ZORIN-16/5.11.0-43-GENERIC/X86_64/E9C76DBCA4>) |
| 1217:8621 | 10f7:8338 | O2 Micro         | SD/MMC Card Reader Controller        | 1     | sdhci_pci  | [94539C6DB9](<Tablet/Panasonic/CF-33/CF-33-1/AE1D638EDC9E/UBUNTU-12.02/5.11.0-38-GENERIC/X86_64/94539C6DB9>) |
| 1217:8621 | 17aa:3841 | O2 Micro         | SD/MMC Card Reader Controller        | 1     | sdhci_pci  | [19173612AF](<Tablet/Lenovo/Yoga/Yoga DuetITL 2021 82MA/9480FE2494B3/ARCO-ROLLING/5.14.5-ZEN1-1-ZEN/X86_64/19173612AF>) |
| 8086:1190 |           | Intel            | Merrifield SD/SDIO/eMMC Controller   | 1     | sdhci_pci  | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:1aca | 8086:7270 | Intel            | SD Host Controller                   | 1     | sdhci_pci  | [555A26F0D1](<Tablet/Intel/570x/570x DVT3/469D9CAF87D4/UBUNTU-CORE-20/5.4.0-62-GENERIC/X86_64/555A26F0D1>) |
| 8086:1acc | 8086:7270 | Intel            | SD Host Controller                   | 1     | sdhci_pci  | [555A26F0D1](<Tablet/Intel/570x/570x DVT3/469D9CAF87D4/UBUNTU-CORE-20/5.4.0-62-GENERIC/X86_64/555A26F0D1>) |
| 8086:2294 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | sdhci_pci  | [0BBA28B672](<Tablet/Kiano/IntelectX3/IntelectX3HD/07656EC371DC/UBUNTU-21.04/5.11.0-37-GENERIC/X86_64/0BBA28B672>) |
| 8086:2295 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | sdhci_pci  | [BEF5E99067](<Tablet/Hampoo/E4/E4D6_HI-122LP/DD6842E526A2/ROSA-2016.1/4.11.0-NRJ-LAPTOP-2.JWR20170418ROSA-X86_64/X86_64/BEF5E99067>) |
| 8086:2296 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | sdhci_pci  | [14D1D84766](<Tablet/Kiano/IntelectX3/IntelectX3HD+/295C5BCA71A8/ROSA-2016.1/4.15.0-DESKTOP-94.1ROSA-X86_64/X86_64/14D1D84766>) |
| 8086:31cc | 17aa:3826 | Intel            | Celeron/Pentium Silver Processor ... | 1     | sdhci_pci  | [FD98FD839E](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 10IGL5 82AT/DCC92275F773/FEDORA-34/5.11.21-300.FC34.X86_64/X86_64/FD98FD839E>) |
| 8086:31cc | 8086:31cc | Intel            | Celeron/Pentium Silver Processor ... | 1     | sdhci_pci  | [E35EF99862](<Tablet/ALLDOCUBE/i1022/i1022d/2568497DA66E/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/E35EF99862>) |
| 8086:31d0 | 8086:31d0 | Intel            | SD Host Controller                   | 1     | sdhci_pci  | [E35EF99862](<Tablet/ALLDOCUBE/i1022/i1022d/2568497DA66E/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/E35EF99862>) |
| 8086:34c4 | 8086:7270 | Intel            | Ice Lake-LP SD Host Controller       | 1     | sdhci_pci  | [9DEEF5A64E](<Tablet/Microsoft/Surface/Surface Laptop Go/7D06E21A462C/ARCH-ROLLING/5.15.6-ARCH2-1-SURFACE/X86_64/9DEEF5A64E>) |
| 8086:5aca |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | sdhci_pci  | [49D345EC0B](<Tablet/Xplore/iX101/iX101L1/1592B2F5F479/UBUNTU-20.04/5.6.0-1028-OEM/X86_64/49D345EC0B>) |
| 8086:9d2b | 152d:1237 | Intel            | Skylake-U/Y SCC: eMMC                | 1     | sdhci_pci  | [8BBA41EDDE](<Tablet/Microsoft/Surface/Surface Go 2/00CE7062B224/FEDORA-32/5.7.15-200.XBODY_KERNEL.FC32.X86_64/X86_64/8BBA41EDDE>) |
| 8086:9d2d | 8086:7270 | Intel            | Sunrise Point-LP Secure Digital I... | 1     | sdhci_pci  | [ED972212E1](<Tablet/Teclast/X6/X6 Pro/F6A57BF3E09B/ARCH/5.10.55-1-LTS/X86_64/ED972212E1>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:34a4 | 8086:7270 | Intel            | Ice Lake-LP SPI Controller           | 37    | intel_s... | [A4E86F6259](<Tablet/Microsoft/Surface/Surface Pro 7/4B1F7148A63A/ZORIN-16/5.16.5-SURFACE/X86_64/A4E86F6259>) |
| 8086:34c5 | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2c Control... | 37    | intel_l... | [A4E86F6259](<Tablet/Microsoft/Surface/Surface Pro 7/4B1F7148A63A/ZORIN-16/5.16.5-SURFACE/X86_64/A4E86F6259>) |
| 8086:34e8 | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2C Control... | 37    | intel_l... | [A4E86F6259](<Tablet/Microsoft/Surface/Surface Pro 7/4B1F7148A63A/ZORIN-16/5.16.5-SURFACE/X86_64/A4E86F6259>) |
| 8086:34ea | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2C Control... | 33    | intel_l... | [A4E86F6259](<Tablet/Microsoft/Surface/Surface Pro 7/4B1F7148A63A/ZORIN-16/5.16.5-SURFACE/X86_64/A4E86F6259>) |
| 8086:34eb | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2C Control... | 23    | intel_l... | [A4E86F6259](<Tablet/Microsoft/Surface/Surface Pro 7/4B1F7148A63A/ZORIN-16/5.16.5-SURFACE/X86_64/A4E86F6259>) |
| 8086:a0a4 | 17aa:380b | Intel            | Tiger Lake-LP SPI Controller         | 4     | intel_s... | [047FF4AD80](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/37FF40E14E4D/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/047FF4AD80>) |
| 8086:a0e8 | 17aa:3823 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 4     | intel_l... | [047FF4AD80](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/37FF40E14E4D/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/047FF4AD80>) |
| 8086:a0e9 | 17aa:3824 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 4     | intel_l... | [047FF4AD80](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/37FF40E14E4D/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/047FF4AD80>) |
| 8086:a0ea | 17aa:3825 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 4     | intel_l... | [047FF4AD80](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/37FF40E14E4D/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/047FF4AD80>) |
| 8086:a0eb | 17aa:3828 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 4     | intel_l... | [047FF4AD80](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/37FF40E14E4D/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/047FF4AD80>) |
| 8086:02a4 | 17aa:3813 | Intel            | Comet Lake SPI (flash) Controller    | 3     | intel_s... | [927ED071B3](<Tablet/Lenovo/Yoga/Yoga Duet IML 2020 82E9/8FFE2F20194E/ARCH-ROLLING/5.16.2-ARCH1-1/X86_64/927ED071B3>) |
| 8086:02c5 | 17aa:3804 | Intel            | Comet Lake Serial IO I2C Host Con... | 3     | intel_l... | [927ED071B3](<Tablet/Lenovo/Yoga/Yoga Duet IML 2020 82E9/8FFE2F20194E/ARCH-ROLLING/5.16.2-ARCH1-1/X86_64/927ED071B3>) |
| 8086:02e8 | 17aa:380f | Intel            | Serial IO I2C Host Controller        | 3     | intel_l... | [927ED071B3](<Tablet/Lenovo/Yoga/Yoga Duet IML 2020 82E9/8FFE2F20194E/ARCH-ROLLING/5.16.2-ARCH1-1/X86_64/927ED071B3>) |
| 8086:34e9 | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2C Control... | 3     | intel_l... | [162DA90CC6](<Tablet/Microsoft/Surface/Surface Laptop 3/1C7E565DCB2D/MANJARO-21.2.0/5.15.7-1-MANJARO/X86_64/162DA90CC6>) |
| 8086:a0a4 | 8086:7270 | Intel            | Tiger Lake-LP SPI Controller         | 3     | intel_s... | [BD290BC56D](<Tablet/Microsoft/Surface/Surface Laptop Studio/AD9CE584B5E1/MANJARO-21.1.6/5.13.19-2-MANJARO/X86_64/BD290BC56D>) |
| 8086:a0d8 | 8086:7270 | Intel            | Tiger Lake-LP Serial IO I2C Host ... | 3     | intel_lpss | [BD290BC56D](<Tablet/Microsoft/Surface/Surface Laptop Studio/AD9CE584B5E1/MANJARO-21.1.6/5.13.19-2-MANJARO/X86_64/BD290BC56D>) |
| 8086:a0e8 | 8086:7270 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 3     | intel_lpss | [BD290BC56D](<Tablet/Microsoft/Surface/Surface Laptop Studio/AD9CE584B5E1/MANJARO-21.1.6/5.13.19-2-MANJARO/X86_64/BD290BC56D>) |
| 8086:5ac8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | pwm_lpss   | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |
| 8086:9ce6 | 8086:9ce6 | Intel            | Wildcat Point-LP Serial IO GSPI C... | 2     | spi_pxa... | [9E5A5DC6CF](<Tablet/Microsoft/Surface/Surface Pro 6/DE921958CD9C/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/9E5A5DC6CF>) |
| 8086:9da4 | 103c:85b9 | Intel            | Cannon Point-LP SPI Controller       | 2     |            | [09F8C72D80](<Tablet/Hewlett-Packard/Elite/Elite x2 G4/0472416698D9/UBUNTU-21.04/5.11.0-25-GENERIC/X86_64/09F8C72D80>) |
| 8086:9de8 | 103c:85b9 | Intel            | Cannon Point-LP Serial IO I2C Con... | 2     | intel_l... | [09F8C72D80](<Tablet/Hewlett-Packard/Elite/Elite x2 G4/0472416698D9/UBUNTU-21.04/5.11.0-25-GENERIC/X86_64/09F8C72D80>) |
| 8086:a0a4 | 1028:0a45 | Intel            | Tiger Lake-LP SPI Controller         | 2     |            | [255FFC0493](<Tablet/Dell/Latitude/Latitude 7320 Detachable/B080FA5912AF/KUBUNTU-21.10/5.16.0/X86_64/255FFC0493>) |
| 8086:a0c5 | 8086:7270 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 2     | intel_lpss | [51711F9018](<Tablet/Microsoft/Surface/Surface Laptop 4/3C3A49F2525B/ZORIN-16/5.15.3-SURFACE/X86_64/51711F9018>) |
| 8086:a0e8 | 1028:0a45 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 2     | intel_l... | [255FFC0493](<Tablet/Dell/Latitude/Latitude 7320 Detachable/B080FA5912AF/KUBUNTU-21.10/5.16.0/X86_64/255FFC0493>) |
| 8086:a0e9 | 1028:0a45 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 2     | intel_l... | [255FFC0493](<Tablet/Dell/Latitude/Latitude 7320 Detachable/B080FA5912AF/KUBUNTU-21.10/5.16.0/X86_64/255FFC0493>) |
| 8086:a0ea | 1028:0a45 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 2     | intel_l... | [255FFC0493](<Tablet/Dell/Latitude/Latitude 7320 Detachable/B080FA5912AF/KUBUNTU-21.10/5.16.0/X86_64/255FFC0493>) |
| 8086:02a4 | 1071:d301 | Intel            | Comet Lake SPI (flash) Controller    | 1     |            | [6F57AB0251](<Tablet/Getac/UX10/UX10G2/9B2D92B11BC9/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/6F57AB0251>) |
| 8086:02e8 | 1071:d301 | Intel            | Serial IO I2C Host Controller        | 1     | intel_l... | [6F57AB0251](<Tablet/Getac/UX10/UX10G2/9B2D92B11BC9/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/6F57AB0251>) |
| 8086:02e9 | 1071:d301 | Intel            | Comet Lake Serial IO I2C Host Con... | 1     | intel_l... | [6F57AB0251](<Tablet/Getac/UX10/UX10G2/9B2D92B11BC9/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/6F57AB0251>) |
| 8086:02ea | 1071:d301 | Intel            | Comet Lake PCH-LP LPSS: I2C Contr... | 1     | intel_l... | [6F57AB0251](<Tablet/Getac/UX10/UX10G2/9B2D92B11BC9/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/6F57AB0251>) |
| 8086:1ac8 | 8086:7270 | Intel            | Serial bus controller                | 1     | pwm_lpss   | [555A26F0D1](<Tablet/Intel/570x/570x DVT3/469D9CAF87D4/UBUNTU-CORE-20/5.4.0-62-GENERIC/X86_64/555A26F0D1>) |
| 8086:a0a4 | 1071:a121 | Intel            | Tiger Lake-LP SPI Controller         | 1     |            | [5D9E3F3501](<Tablet/Getac/K120/K120G2/9B90212BD0E9/UBUNTU-18.04/5.4.0-84-GENERIC/X86_64/5D9E3F3501>) |
| 8086:a0a4 | 17aa:508b | Intel            | Tiger Lake-LP SPI Controller         | 1     |            | [AAC22AF3A1](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UWCTO1WW/3B7CEBE290BA/DEBIAN-TESTING/5.10.19/X86_64/AAC22AF3A1>) |
| 8086:a0c5 | 17aa:508b | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 1     | intel_l... | [AAC22AF3A1](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UWCTO1WW/3B7CEBE290BA/DEBIAN-TESTING/5.10.19/X86_64/AAC22AF3A1>) |
| 8086:a0e8 | 1071:a121 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 1     | intel_l... | [5D9E3F3501](<Tablet/Getac/K120/K120G2/9B90212BD0E9/UBUNTU-18.04/5.4.0-84-GENERIC/X86_64/5D9E3F3501>) |
| 8086:a0e8 | 17aa:508b | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 1     | intel_l... | [AAC22AF3A1](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UWCTO1WW/3B7CEBE290BA/DEBIAN-TESTING/5.10.19/X86_64/AAC22AF3A1>) |
| 8086:a0e9 | 1071:a121 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 1     | intel_l... | [5D9E3F3501](<Tablet/Getac/K120/K120G2/9B90212BD0E9/UBUNTU-18.04/5.4.0-84-GENERIC/X86_64/5D9E3F3501>) |
| 8086:a0e9 | 17aa:508b | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 1     | intel_l... | [AAC22AF3A1](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UWCTO1WW/3B7CEBE290BA/DEBIAN-TESTING/5.10.19/X86_64/AAC22AF3A1>) |
| 8086:a0e9 | 8086:7270 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 1     | intel_l... | [BD290BC56D](<Tablet/Microsoft/Surface/Surface Laptop Studio/AD9CE584B5E1/MANJARO-21.1.6/5.13.19-2-MANJARO/X86_64/BD290BC56D>) |
| 8086:a0eb | 17aa:508b | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 1     | intel_l... | [AAC22AF3A1](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UWCTO1WW/3B7CEBE290BA/DEBIAN-TESTING/5.10.19/X86_64/AAC22AF3A1>) |

### Serial controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:34fc | 8086:7270 | Intel            | Ice Lake-LP Integrated Sensor Sol... | 24    | intel_i... | [A4E86F6259](<Tablet/Microsoft/Surface/Surface Pro 7/4B1F7148A63A/ZORIN-16/5.16.5-SURFACE/X86_64/A4E86F6259>) |
| 8086:9d3d | 1028:07a4 | Intel            | Sunrise Point-LP Active Managemen... | 5     | serial     | [568757F9F8](<Tablet/Dell/Latitude/Latitude 5285/9BC7EC024B34/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/568757F9F8>) |
| 8086:9d3d | 1028:06e6 | Intel            | Sunrise Point-LP Active Managemen... | 4     | serial     | [6430380D5B](<Tablet/Dell/Latitude/Latitude 5179/597547DCB08C/POP!_OS-20.04/5.16.11-76051611-GENERIC/X86_64/6430380D5B>) |
| 8086:9d3d | 1028:07a5 | Intel            | Sunrise Point-LP Active Managemen... | 4     | serial     | [78F2672479](<Tablet/Dell/Latitude/Latitude 7285/35CB641DDB78/CLEAR-LINUX-OS-35940/5.16.11-1128.NATIVE/X86_64/78F2672479>) |
| 8086:9d3d | 17aa:2244 | Intel            | Sunrise Point-LP Active Managemen... | 4     | serial     | [55F51A3D6F](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJ0011US/7240D66F8895/POP!_OS-21.04/5.13.0-7614-GENERIC/X86_64/55F51A3D6F>) |
| 8086:a0fc | 17aa:382d | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 4     | intel_i... | [047FF4AD80](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/37FF40E14E4D/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/047FF4AD80>) |
| 8086:02fc | 17aa:380c | Intel            | Comet Lake Integrated Sensor Solu... | 3     | intel_i... | [927ED071B3](<Tablet/Lenovo/Yoga/Yoga Duet IML 2020 82E9/8FFE2F20194E/ARCH-ROLLING/5.16.2-ARCH1-1/X86_64/927ED071B3>) |
| 8086:9d3d | 1028:081d | Intel            | Sunrise Point-LP Active Managemen... | 3     | serial     | [9CFD9C7142](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/39E24435C9D2/ELEMENTARY-6.1/5.13.0-30-GENERIC/X86_64/9CFD9C7142>) |
| 8086:9d3d | 103c:82ca | Intel            | Sunrise Point-LP Active Managemen... | 3     | serial     | [47D816D00F](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/C9B530F954DE/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/47D816D00F>) |
| 8086:1e3d | 10f7:8338 | Intel            | 7 Series/C210 Series Chipset Fami... | 2     | serial     | [06F11C0449](<Tablet/Panasonic/FZ-G1/FZ-G1ASH39E3/6F2FB083615E/ELEMENTARY-6/5.11.0-37-GENERIC/X86_64/06F11C0449>) |
| 8086:9d3d | 1028:06d6 | Intel            | Sunrise Point-LP Active Managemen... | 2     | serial     | [14BCC9219C](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-21.10/5.16.10-XANMOD1/X86_64/14BCC9219C>) |
| 8086:9d3d | 17aa:2241 | Intel            | Sunrise Point-LP Active Managemen... | 2     | serial     | [1C271464F4](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/E0C95B0360EB/DEBIAN-11/5.10.0-6-AMD64/X86_64/1C271464F4>) |
| 8086:9de3 | 103c:85b9 | Intel            | Cannon Point-LP Keyboard and Text... | 2     | serial     | [09F8C72D80](<Tablet/Hewlett-Packard/Elite/Elite x2 G4/0472416698D9/UBUNTU-21.04/5.11.0-25-GENERIC/X86_64/09F8C72D80>) |
| 8086:9dfc | 103c:85b9 | Intel            | Cannon Point-LP Integrated Sensor... | 2     | intel_i... | [09F8C72D80](<Tablet/Hewlett-Packard/Elite/Elite x2 G4/0472416698D9/UBUNTU-21.04/5.11.0-25-GENERIC/X86_64/09F8C72D80>) |
| 8086:a0fc | 1028:0a45 | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 2     | intel_i... | [255FFC0493](<Tablet/Dell/Latitude/Latitude 7320 Detachable/B080FA5912AF/KUBUNTU-21.10/5.16.0/X86_64/255FFC0493>) |
| 8086:02fc | 1071:d301 | Intel            | Comet Lake Integrated Sensor Solu... | 1     | intel_i... | [6F57AB0251](<Tablet/Getac/UX10/UX10G2/9B2D92B11BC9/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/6F57AB0251>) |
| 8086:1191 |           | Intel            | Merrifield Serial IO HSUART Contr... | 1     |            | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:1192 |           | Intel            | Merrifield Serial IO HSUART DMA C... | 1     |            | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:9d3d | 10f7:8338 | Intel            | Sunrise Point-LP Active Managemen... | 1     | serial     | [94539C6DB9](<Tablet/Panasonic/CF-33/CF-33-1/AE1D638EDC9E/UBUNTU-12.02/5.11.0-38-GENERIC/X86_64/94539C6DB9>) |
| 8086:9d3d | 17aa:2243 | Intel            | Sunrise Point-LP Active Managemen... | 1     | serial     | [39C0680056](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JB003LMX/2CEEE337E2A9/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/39C0680056>) |
| 8086:a0e3 | 1028:0a45 | Intel            | Tiger Lake-LP Active Management T... | 1     | serial     | [255FFC0493](<Tablet/Dell/Latitude/Latitude 7320 Detachable/B080FA5912AF/KUBUNTU-21.10/5.16.0/X86_64/255FFC0493>) |
| 8086:a0fc | 1071:a121 | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 1     | intel_i... | [5D9E3F3501](<Tablet/Getac/K120/K120G2/9B90212BD0E9/UBUNTU-18.04/5.4.0-84-GENERIC/X86_64/5D9E3F3501>) |
| 8086:a0fc | 17aa:508b | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 1     | intel_i... | [AAC22AF3A1](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UWCTO1WW/3B7CEBE290BA/DEBIAN-TESTING/5.10.19/X86_64/AAC22AF3A1>) |
| 8086:a0fc | 8086:7270 | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 1     | intel_i... | [A4AEFCD9B2](<Tablet/Microsoft/Surface/Surface Pro 7+/B513B8EA5A0E/FEDORA-32/5.10.10-1.SURFACE.FC32.X86_64/X86_64/A4AEFCD9B2>) |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d31 | 8086:7270 | Intel            | Sunrise Point-LP Thermal subsystem   | 173   | intel_p... | [26A4220432](<Tablet/Microsoft/Surface/Surface Pro 4/5171E94FBA49/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/26A4220432>) |
| 8086:9d60 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 173   | intel_l... | [26A4220432](<Tablet/Microsoft/Surface/Surface Pro 4/5171E94FBA49/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/26A4220432>) |
| 8086:9d61 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 173   | intel_l... | [26A4220432](<Tablet/Microsoft/Surface/Surface Pro 4/5171E94FBA49/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/26A4220432>) |
| 8086:9d63 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 163   | intel_l... | [26A4220432](<Tablet/Microsoft/Surface/Surface Pro 4/5171E94FBA49/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/26A4220432>) |
| 8086:9d62 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 160   | intel_l... | [26A4220432](<Tablet/Microsoft/Surface/Surface Pro 4/5171E94FBA49/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/26A4220432>) |
| 8086:22dc | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 95    | process... | [23FBC9A6EE](<Tablet/RCA/W101/W101AS23T2/BBCA95A1C67D/FEDORA-35/5.16.8-200.FC35.X86_64/X86_64/23FBC9A6EE>) |
| 8086:9d27 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO UART C... | 86    | intel_l... | [50420D6D58](<Tablet/Microsoft/Surface/Surface Pro 6/DE921958CD9C/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/50420D6D58>) |
| 8086:1903 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 85    | process... | [50420D6D58](<Tablet/Microsoft/Surface/Surface Pro 6/DE921958CD9C/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/50420D6D58>) |
| 8086:22dc | 17aa:3809 | Intel            | Atom/Celeron/Pentium Processor x5... | 43    | process... | [4758B6520C](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/6D0C35E280B8/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/4758B6520C>) |
| 8086:22dc | 17aa:3808 | Intel            | Atom/Celeron/Pentium Processor x5... | 40    | process... | [FB183BFD9B](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/056649DD334F/MANJARO/5.15.25-1-MANJARO/X86_64/FB183BFD9B>) |
| 8086:22dc | 7270:8086 | Intel            | Atom/Celeron/Pentium Processor x5... | 33    | process... | [E88252DB3F](<Tablet/Acer/One/One S1003/9D8E7D4E8A41/UBUNTU-16.04/4.15.0-142-GENERIC/X86_64/E88252DB3F>) |
| 8086:318c | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    | process... | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:31ac | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    | intel_l... | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:31ae | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    | intel_l... | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:31b0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    | intel_l... | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:31b2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    | intel_l... | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:31b4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    | intel_l... | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:31b6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    | intel_l... | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:31b8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    | intel_l... | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:31ba | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    | intel_l... | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:31bc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    | intel_l... | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:31be | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    | intel_l... | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:31c0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    | intel_l... | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:31c2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    | intel_l... | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:31c4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    | intel_l... | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:31c6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    | intel_l... | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:31ee | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    | intel_l... | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:8a03 | 8086:7270 | Intel            | Ice Lake Dynamic Platform and The... | 23    | process... | [A4E86F6259](<Tablet/Microsoft/Surface/Surface Pro 7/4B1F7148A63A/ZORIN-16/5.16.5-SURFACE/X86_64/A4E86F6259>) |
| 8086:1903 | 8086:1903 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 22    | process... | [0F05F12004](<Tablet/Teclast/X5/X5 Pro/B130987D6E6A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0F05F12004>) |
| 8086:5aac | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 21    | intel_l... | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |
| 8086:5aae | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 21    | intel_l... | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |
| 8086:5ab2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 21    | intel_l... | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |
| 8086:5ab4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 21    | intel_l... | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |
| 8086:5ab6 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 21    | intel_l... | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |
| 8086:1903 | 152d:1182 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 20    | proc_th... | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:22dc | 103c:827c | Intel            | Atom/Celeron/Pentium Processor x5... | 20    | process... | [9A03FDA057](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/E1DE173C5065/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/9A03FDA057>) |
| 8086:22dc | 1043:13a0 | Intel            | Atom/Celeron/Pentium Processor x5... | 20    | process... | [05983A1E06](<Tablet/ASUSTek Computer/T101/T101HA/AC331E492606/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/05983A1E06>) |
| 8086:9d27 | 152d:1182 | Intel            | Sunrise Point-LP Serial IO UART C... | 20    | intel_lpss | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:9d31 | 152d:1182 | Intel            | Sunrise Point-LP Thermal subsystem   | 20    | intel_p... | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:9d60 | 152d:1182 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 20    | intel_lpss | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:9d61 | 152d:1182 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 20    | intel_lpss | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:9d62 | 152d:1182 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 20    | intel_lpss | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:9d63 | 152d:1182 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 20    | intel_lpss | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:9d64 | 152d:1182 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 20    | intel_l... | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:9d66 | 152d:1182 | Intel            | Sunrise Point-LP Serial IO UART C... | 20    | intel_lpss | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:22dc | 1043:1400 | Intel            | Atom/Celeron/Pentium Processor x5... | 16    | process... | [ECC5AD7332](<Tablet/ASUSTek Computer/T102/T102HA/C13EDC224850/MX-19/4.19.0-18-AMD64/X86_64/ECC5AD7332>) |
| 8086:22dc | 1414:0009 | Intel            | Atom/Celeron/Pentium Processor x5... | 16    | process... | [D8EA22EFF5](<Tablet/Microsoft/Surface/Surface 3/DEBCA8820BEF/DEBIAN-TESTING/5.16.11-SURFACE/X86_64/D8EA22EFF5>) |
| 8086:5ab0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 15    | intel_l... | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |
| 8086:5ab8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 15    | intel_l... | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |
| 8086:5aba | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 15    | intel_l... | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9c22 | 1414:9c22 | Intel            | 8 Series SMBus Controller            | 67    | i2c_i801   | [92F8B5CBFA](<Tablet/Microsoft/Surface/Surface Pro 3/0558715ED322/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/92F8B5CBFA>) |
| 8086:31d4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    | i2c_i801   | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:9d23 | 8086:7270 | Intel            | Sunrise Point-LP SMBus               | 23    | i801_smbus | [730558C6BD](<Tablet/Microsoft/Surface/Surface Book 2/451432DF4DF7/ELEMENTARY-6.1/5.15.6-SURFACE/X86_64/730558C6BD>) |
| 8086:5ad4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 21    | i2c_i801   | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |
| 1002:4385 | 1025:0577 | AMD              | SBx00 SMBus Controller               | 14    | i2c_pii... | [5984A91751](<Tablet/Acer/Iconia/Iconia Tab W500/99578EB02374/ELEMENTARY-6/5.11.0-40-GENERIC/X86_64/5984A91751>) |
| 8086:0f12 | 1019:99a5 | Intel            | Atom Processor E3800/CE2700 Serie... | 12    | i2c_i801   | [A2B7A04DFA](<Tablet/Intel/powered/powered classmate PC/E3EDE14D59EF/LINUXMINT-20.2/5.4.0-100-GENERIC/X86_64/A2B7A04DFA>) |
| 8086:9d23 | 103c:82ca | Intel            | Sunrise Point-LP SMBus               | 10    | i2c_i801   | [BEEB081772](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/945D2246773B/UBUNTU-MATE-20.04/5.13.0-30-GENERIC/X86_64/BEEB081772>) |
| 8086:1e22 | 1414:1e22 | Intel            | 7 Series/C216 Chipset Family SMBu... | 8     | i2c_i801   | [F1D0D25B44](<Tablet/Microsoft/Surface/Surface with Windows 8 Pro/EC94C82618D5/UBUNTU-20.04/5.15.13-051513-GENERIC/X86_64/F1D0D25B44>) |
| 8086:31d4 | 17aa:3823 | Intel            | Celeron/Pentium Silver Processor ... | 8     | i2c_i801   | [C9D8BB9BD9](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGM 81H3/689B95560E77/MANJARO-21.2.3/5.16.7-1-MANJARO/X86_64/C9D8BB9BD9>) |
| 8086:9d23 | 144d:c14f | Intel            | Sunrise Point-LP SMBus               | 8     | i2c_i801   | [63CAA45089](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12 LTE/F81EBA4C8217/ZORIN-16/5.13.0-30-GENERIC/X86_64/63CAA45089>) |
| 8086:9d23 | 8086:9d23 | Intel            | Sunrise Point-LP SMBus               | 8     | i2c_i801   | [0F05F12004](<Tablet/Teclast/X5/X5 Pro/B130987D6E6A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0F05F12004>) |
| 8086:9d23 | 17aa:384f | Intel            | Sunrise Point-LP SMBus               | 7     | i2c_i801   | [8B9FA8F425](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/A89FAAAFC012/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/8B9FA8F425>) |
| 1022:790b | 1022:790b | AMD              | FCH SMBus Controller                 | 6     | i2c_piix4  | [D55F23484E](<Tablet/Microsoft/Surface/Surface Laptop 3/6407F7577C70/ELEMENTARY-6.1/5.16.11-SURFACE/X86_64/D55F23484E>) |
| 8086:0f12 | 1019:99a1 | Intel            | Atom Processor E3800/CE2700 Serie... | 6     | i2c_i801   | [C61A96D514](<Tablet/Medion/P/P2212T/71C4E4B2F18A/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/C61A96D514>) |
| 8086:9d23 | 1028:06e6 | Intel            | Sunrise Point-LP SMBus               | 6     | i2c_i801   | [6430380D5B](<Tablet/Dell/Latitude/Latitude 5179/597547DCB08C/POP!_OS-20.04/5.16.11-76051611-GENERIC/X86_64/6430380D5B>) |
| 8086:9d23 | 1028:07a4 | Intel            | Sunrise Point-LP SMBus               | 6     | i2c_i801   | [568757F9F8](<Tablet/Dell/Latitude/Latitude 5285/9BC7EC024B34/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/568757F9F8>) |
| 8086:9d23 | 103c:828b | Intel            | Sunrise Point-LP SMBus               | 6     | i2c_i801   | [5A85AB6B0F](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/608A6BF05466/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/5A85AB6B0F>) |
| 8086:9d23 | 144d:c135 | Intel            | Sunrise Point-LP SMBus               | 6     | i2c_i801   | [3ADAAACD83](<Tablet/Samsung Electronics/Galaxy/Galaxy TabPro S/7232B6211ED3/POP!_OS-21.04/5.13.0-7614-GENERIC/X86_64/3ADAAACD83>) |
| 8086:9d23 | 17aa:2244 | Intel            | Sunrise Point-LP SMBus               | 6     | i801_smbus | [F92AE76FED](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJCTO1WW/3D3FB636D7D4/DEVUAN-4/5.10.0-11-AMD64/X86_64/F92AE76FED>) |
| 8086:9d23 | 1028:081d | Intel            | Sunrise Point-LP SMBus               | 5     | i2c_i801   | [9CFD9C7142](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/39E24435C9D2/ELEMENTARY-6.1/5.13.0-30-GENERIC/X86_64/9CFD9C7142>) |
| 8086:9d23 | 1025:111e | Intel            | Sunrise Point-LP SMBus               | 4     | i801_smbus | [C6DC41A2A5](<Tablet/Acer/Switch/Switch SA5-271/7F70B3D37585/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C6DC41A2A5>) |
| 8086:9d23 | 1028:06d6 | Intel            | Sunrise Point-LP SMBus               | 4     | i801_smbus | [14BCC9219C](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-21.10/5.16.10-XANMOD1/X86_64/14BCC9219C>) |
| 8086:9d23 | 1028:07a5 | Intel            | Sunrise Point-LP SMBus               | 4     | i801_smbus | [78F2672479](<Tablet/Dell/Latitude/Latitude 7285/35CB641DDB78/CLEAR-LINUX-OS-35940/5.16.11-1128.NATIVE/X86_64/78F2672479>) |
| 8086:9d23 | 17aa:2241 | Intel            | Sunrise Point-LP SMBus               | 4     | i2c_i801   | [923CCB09A5](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GHCTO1WW/70707A835AE8/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/923CCB09A5>) |
| 8086:9d23 | 17aa:3829 | Intel            | Sunrise Point-LP SMBus               | 4     | i2c_i801   | [E1BEE3CD30](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/63E5CC1D8A4F/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/E1BEE3CD30>) |
| 8086:a0a3 | 17aa:3805 | Intel            | Tiger Lake-LP SMBus Controller       | 4     | i2c_i801   | [047FF4AD80](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/37FF40E14E4D/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/047FF4AD80>) |
| 8086:5ad4 | 8086:5ad4 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | i2c_i801   | [07C752AA8C](<Tablet/ZoomSmart/A/A1002/F1BBB3E02B52/ROSA-2019.05/5.4.60-NICKEL-2ROSA2019.05-X86_64/X86_64/07C752AA8C>) |
| 8086:9c22 | 17aa:3978 | Intel            | 8 Series SMBus Controller            | 3     | i2c_i801   | [2D356053D3](<Tablet/Lenovo/MIIX/MIIX 2 11 20327/880F55D78695/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/2D356053D3>) |
| 8086:9ca2 | 17aa:222b | Intel            | Wildcat Point-LP SMBus Controller    | 3     | i2c_i801   | [5BADA8B921](<Tablet/Lenovo/ThinkPad/ThinkPad Helix 2nd 20CHS1NG03/BD286A22C079/FEDORA-33/5.10.21-200.FC33.X86_64/X86_64/5BADA8B921>) |
| 8086:9d23 | 17aa:3833 | Intel            | Sunrise Point-LP SMBus               | 3     | i2c_i801   | [67E1BDD5F1](<Tablet/Lenovo/MIIX/MIIX 720-12IKB 80VV/F45F8CE4052D/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/67E1BDD5F1>) |
| 8086:9d23 | 17aa:3844 | Intel            | Sunrise Point-LP SMBus               | 3     | i2c_i801   | [D249085990](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/A4295A395509/POP!_OS-21.10/5.15.8-76051508-GENERIC/X86_64/D249085990>) |
| 8086:0f12 | 1509:7018 | Intel            | Atom Processor E3800/CE2700 Serie... | 2     | i2c_i801   | [9347717861](<Tablet/Xplore/iX101/iX101B1/988A604FB8AB/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/9347717861>) |
| 8086:0f12 | 1854:0211 | Intel            | Atom Processor E3800/CE2700 Serie... | 2     | i2c_i801   | [44AF16AC16](<Tablet/LG Electronics/15U340/15U340-L.BK55P1/96572D02BF5F/LINUXMINT-20/5.4.0-42-GENERIC/X86_64/44AF16AC16>) |
| 8086:1e22 | 10f7:8338 | Intel            | 7 Series/C216 Chipset Family SMBu... | 2     | i801_smbus | [06F11C0449](<Tablet/Panasonic/FZ-G1/FZ-G1ASH39E3/6F2FB083615E/ELEMENTARY-6/5.11.0-37-GENERIC/X86_64/06F11C0449>) |
| 8086:9ca2 | 8086:7270 | Intel            | Wildcat Point-LP SMBus Controller    | 2     | i2c_i801   | [9E5A5DC6CF](<Tablet/Microsoft/Surface/Surface Pro 6/DE921958CD9C/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/9E5A5DC6CF>) |
| 8086:9d23 | 1025:1171 | Intel            | Sunrise Point-LP SMBus               | 2     | i2c_i801   | [4B0ED624FA](<Tablet/Acer/Switch/Switch SW512-52/8FD5C8AAAFE9/ARCH-ROLLING/5.8.12-ARCH1-1/X86_64/4B0ED624FA>) |
| 8086:9d23 | 103c:82cb | Intel            | Sunrise Point-LP SMBus               | 2     | i2c_i801   | [EFC4C63AC7](<Tablet/Hewlett-Packard/Spectre/Spectre x2 Detachable 12-c0XX/09798ACE135C/DEEPIN-20.2.2/5.10.36-AMD64-DESKTOP/X86_64/EFC4C63AC7>) |
| 8086:9d23 | 103c:8414 | Intel            | Sunrise Point-LP SMBus               | 2     | i2c_i801   | [6EE77ED959](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/3DD573867AA0/UBUNTU-20.04/5.8.0-36-GENERIC/X86_64/6EE77ED959>) |
| 8086:9d23 | 1043:13c0 | Intel            | Sunrise Point-LP SMBus               | 2     | i2c_i801   | [4363CA1BD6](<Tablet/ASUSTek Computer/T303/T303UA/C8223D9D63FE/UBUNTU-20.04/5.4.0-33-GENERIC/X86_64/4363CA1BD6>) |
| 8086:9d23 | 1043:1410 | Intel            | Sunrise Point-LP SMBus               | 2     | i2c_i801   | [C66E4999F0](<Tablet/ASUSTek Computer/T305/T305CA/70CB67E36043/UBUNTU-20.04/5.8.0-50-GENERIC/X86_64/C66E4999F0>) |
| 8086:9d23 | 1043:16c0 | Intel            | Sunrise Point-LP SMBus               | 2     | i2c_i801   | [D33E67BDF4](<Tablet/ASUSTek Computer/T304/T304UA/8F97F461C23D/UBUNTU-20.04/5.4.0-29-GENERIC/X86_64/D33E67BDF4>) |
| 8086:9d23 | 17aa:2243 | Intel            | Sunrise Point-LP SMBus               | 2     | i2c_i801   | [39C0680056](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JB003LMX/2CEEE337E2A9/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/39C0680056>) |
| 8086:9d23 | 1b0a:01d3 | Intel            | Sunrise Point-LP SMBus               | 2     | i2c_i801   | [60C93DDC01](<Tablet/Xplore/iX125/iX125R1/9DCB305AD004/PUPPY_IMPPUP64-9.6.1/5.15.11-LXPUP64/X86_64/60C93DDC01>) |
| 8086:9da3 | 103c:85b9 | Intel            | Cannon Point-LP SMBus Controller     | 2     | i2c_i801   | [09F8C72D80](<Tablet/Hewlett-Packard/Elite/Elite x2 G4/0472416698D9/UBUNTU-21.04/5.11.0-25-GENERIC/X86_64/09F8C72D80>) |
| 8086:a0a3 | 1028:0a45 | Intel            | Tiger Lake-LP SMBus Controller       | 2     | i2c_i801   | [255FFC0493](<Tablet/Dell/Latitude/Latitude 7320 Detachable/B080FA5912AF/KUBUNTU-21.10/5.16.0/X86_64/255FFC0493>) |
| 8086:02a3 | 1071:d301 | Intel            | Comet Lake PCH-LP SMBus Host Cont... | 1     | i2c_i801   | [6F57AB0251](<Tablet/Getac/UX10/UX10G2/9B2D92B11BC9/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/6F57AB0251>) |
| 8086:0f12 | 1558:5470 | Intel            | Atom Processor E3800/CE2700 Serie... | 1     | i2c_i801   | [DD65C5ABF7](<Tablet/Lanix/Neuron/Neuron A/9C81E684C8A4/ARCH-ROLLING/5.8.14-ARCH1-1/X86_64/DD65C5ABF7>) |
| 8086:0f12 | 8086:7270 | Intel            | Atom Processor E3800/CE2700 Serie... | 1     | i2c_i801   | [8F2478944C](<Tablet/Wortmann AG/TERRA_PAD/TERRA_PAD_1060/B40099ED7FF5/FEDORA-31/5.11.0-RC6+/X86_64/8F2478944C>) |
| 8086:1e22 | 1b0a:017b | Intel            | 7 Series/C216 Chipset Family SMBu... | 1     |            | [5A97B2A1A7](<Tablet/Wacom/Citiq/Citiq Companion/47415E406255/LINUXMINT-19.2/5.0.0-27-GENERIC/X86_64/5A97B2A1A7>) |
| 8086:2292 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | i2c_i801   | [009BEE9446](<Tablet/Intel/Braswell/Braswell Platform/1E35D60EBB32/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/009BEE9446>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d70 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 86    | snd_hda... | [26A4220432](<Tablet/Microsoft/Surface/Surface Pro 4/5171E94FBA49/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/26A4220432>) |
| 8086:9d71 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 86    | snd_hda... | [50420D6D58](<Tablet/Microsoft/Surface/Surface Pro 6/DE921958CD9C/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/50420D6D58>) |
| 8086:9c20 | 1414:9c20 | Intel            | 8 Series HD Audio Controller         | 67    | snd_hda... | [92F8B5CBFA](<Tablet/Microsoft/Surface/Surface Pro 3/0558715ED322/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/92F8B5CBFA>) |
| 8086:0a0c | 8086:0a0c | Intel            | Haswell-ULT HD Audio Controller      | 51    | snd_hda... | [92F8B5CBFA](<Tablet/Microsoft/Surface/Surface Pro 3/0558715ED322/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/92F8B5CBFA>) |
| 8086:34c8 | 8086:7270 | Intel            | Ice Lake-LP Smart Sound Technolog... | 37    | snd_hda... | [A4E86F6259](<Tablet/Microsoft/Surface/Surface Pro 7/4B1F7148A63A/ZORIN-16/5.16.5-SURFACE/X86_64/A4E86F6259>) |
| 8086:9d71 | 152d:1182 | Intel            | Sunrise Point-LP HD Audio            | 20    | snd_hda... | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:0a0c | 8086:2010 | Intel            | Haswell-ULT HD Audio Controller      | 16    | snd_hda... | [275B20283F](<Tablet/Microsoft/Surface/Surface Pro 2/DF18662C511A/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/275B20283F>) |
| 8086:3198 | 1c6c:122a | Intel            | Celeron/Pentium Silver Processor ... | 15    | snd_hda... | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 1002:1314 | 1025:0577 | AMD              | Wrestler HDMI Audio                  | 14    | snd_hda... | [5984A91751](<Tablet/Acer/Iconia/Iconia Tab W500/99578EB02374/ELEMENTARY-6/5.11.0-40-GENERIC/X86_64/5984A91751>) |
| 1002:4383 | 1025:0577 | AMD              | SBx00 Azalia (Intel HDA)             | 14    | snd_hda... | [5984A91751](<Tablet/Acer/Iconia/Iconia Tab W500/99578EB02374/ELEMENTARY-6/5.11.0-40-GENERIC/X86_64/5984A91751>) |
| 8086:0f04 | 1019:99fa | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 12    | snd_hda... | [A2B7A04DFA](<Tablet/Intel/powered/powered classmate PC/E3EDE14D59EF/LINUXMINT-20.2/5.4.0-100-GENERIC/X86_64/A2B7A04DFA>) |
| 8086:9d71 | 103c:82ca | Intel            | Sunrise Point-LP HD Audio            | 10    | snd_hda... | [BEEB081772](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/945D2246773B/UBUNTU-MATE-20.04/5.13.0-30-GENERIC/X86_64/BEEB081772>) |
| 8086:1e20 | 1414:1e20 | Intel            | 7 Series/C216 Chipset Family High... | 8     | snd_hda... | [F1D0D25B44](<Tablet/Microsoft/Surface/Surface with Windows 8 Pro/EC94C82618D5/UBUNTU-20.04/5.15.13-051513-GENERIC/X86_64/F1D0D25B44>) |
| 8086:3198 | 17aa:3809 | Intel            | Celeron/Pentium Silver Processor ... | 8     | snd_hda... | [C9D8BB9BD9](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGM 81H3/689B95560E77/MANJARO-21.2.3/5.16.7-1-MANJARO/X86_64/C9D8BB9BD9>) |
| 8086:9d71 | 144d:c14f | Intel            | Sunrise Point-LP HD Audio            | 8     | snd_hda... | [63CAA45089](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12 LTE/F81EBA4C8217/ZORIN-16/5.13.0-30-GENERIC/X86_64/63CAA45089>) |
| 8086:9d71 | 17aa:3817 | Intel            | Sunrise Point-LP HD Audio            | 7     | snd_hda... | [8B9FA8F425](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/A89FAAAFC012/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/8B9FA8F425>) |
| 8086:0f04 | 1019:99a6 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | snd_hda... | [C61A96D514](<Tablet/Medion/P/P2212T/71C4E4B2F18A/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/C61A96D514>) |
| 8086:5a98 | 1025:1209 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 6     | snd_hda... | [AF71CFF698](<Tablet/Acer/Switch/Switch SW312-31/BBD489037843/DEBIAN-11/5.10.0-9-AMD64/X86_64/AF71CFF698>) |
| 8086:9d70 | 144d:c135 | Intel            | Sunrise Point-LP HD Audio            | 6     | snd_hda... | [3ADAAACD83](<Tablet/Samsung Electronics/Galaxy/Galaxy TabPro S/7232B6211ED3/POP!_OS-21.04/5.13.0-7614-GENERIC/X86_64/3ADAAACD83>) |
| 8086:9d71 | 1028:07a4 | Intel            | Sunrise Point-LP HD Audio            | 6     | snd_hda... | [568757F9F8](<Tablet/Dell/Latitude/Latitude 5285/9BC7EC024B34/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/568757F9F8>) |
| 8086:9d71 | 103c:828b | Intel            | Sunrise Point-LP HD Audio            | 6     | snd_hda... | [5A85AB6B0F](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/608A6BF05466/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/5A85AB6B0F>) |
| 8086:9d71 | 152d:1237 | Intel            | Sunrise Point-LP HD Audio            | 6     | snd_hda... | [E530D905DA](<Tablet/Microsoft/Surface/Surface Go 2/356E9AC2E762/ARCH/5.15.11-ARCH2-1-SURFACE/X86_64/E530D905DA>) |
| 8086:9d71 | 17aa:2244 | Intel            | Sunrise Point-LP HD Audio            | 6     | snd_hda... | [F92AE76FED](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJCTO1WW/3D3FB636D7D4/DEVUAN-4/5.10.0-11-AMD64/X86_64/F92AE76FED>) |
| 8086:22a8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     |            | [0BBA28B672](<Tablet/Kiano/IntelectX3/IntelectX3HD/07656EC371DC/UBUNTU-21.04/5.11.0-37-GENERIC/X86_64/0BBA28B672>) |
| 8086:5a98 | 1c6c:122a | Intel            | Celeron N3350/Pentium N4200/Atom ... | 5     | snd_hda... | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |
| 8086:9d71 | 1028:081d | Intel            | Sunrise Point-LP HD Audio            | 5     | snd_hda... | [9CFD9C7142](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/39E24435C9D2/ELEMENTARY-6.1/5.13.0-30-GENERIC/X86_64/9CFD9C7142>) |
| 8086:3198 | 2782:0303 | Intel            | Celeron/Pentium Silver Processor ... | 4     | snd_hda... | [5D8B5E0C8E](<Tablet/Chuwi/Hi10/Hi10 X/BC490CF09E12/OPENSUSE-TUMBLEWEED-20220103/5.15.12-1-DEFAULT/X86_64/5D8B5E0C8E>) |
| 8086:9d70 | 1025:111e | Intel            | Sunrise Point-LP HD Audio            | 4     | snd_hda... | [C6DC41A2A5](<Tablet/Acer/Switch/Switch SA5-271/7F70B3D37585/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C6DC41A2A5>) |
| 8086:9d70 | 1028:06d6 | Intel            | Sunrise Point-LP HD Audio            | 4     | snd_hda... | [14BCC9219C](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-21.10/5.16.10-XANMOD1/X86_64/14BCC9219C>) |
| 8086:9d70 | 1028:06e6 | Intel            | Sunrise Point-LP HD Audio            | 4     | snd_hda... | [D47AC58E2B](<Tablet/Dell/Latitude/Latitude 5175/AE5B4A894C5E/DEBIAN-10/5.10.0-8MX-AMD64/X86_64/D47AC58E2B>) |
| 8086:9d70 | 17aa:2241 | Intel            | Sunrise Point-LP HD Audio            | 4     | snd_hda... | [923CCB09A5](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GHCTO1WW/70707A835AE8/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/923CCB09A5>) |
| 8086:9d70 | 17aa:3829 | Intel            | Sunrise Point-LP HD Audio            | 4     | snd_hda... | [E1BEE3CD30](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/63E5CC1D8A4F/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/E1BEE3CD30>) |
| 8086:9d71 | 1028:07a5 | Intel            | Sunrise Point-LP HD Audio            | 4     | snd_hda... | [78F2672479](<Tablet/Dell/Latitude/Latitude 7285/35CB641DDB78/CLEAR-LINUX-OS-35940/5.16.11-1128.NATIVE/X86_64/78F2672479>) |
| 8086:a0c8 | 17aa:3820 | Intel            | Tiger Lake-LP Smart Sound Technol... | 4     | snd_hda... | [047FF4AD80](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/37FF40E14E4D/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/047FF4AD80>) |
| 1002:15de | 1002:15de | AMD              | Raven/Raven2/Fenghuang HDMI/DP Au... | 3     | snd_hda... | [D55F23484E](<Tablet/Microsoft/Surface/Surface Laptop 3/6407F7577C70/ELEMENTARY-6.1/5.16.11-SURFACE/X86_64/D55F23484E>) |
| 1002:1637 | 1002:1637 | AMD              | Renoir Radeon High Definition Aud... | 3     | snd_hda... | [C039BD54B8](<Tablet/AYADEVICE/AYA/AYA NEO FOUNDER/49BCDD789BF3/ARCH-ROLLING/5.14.11-ARCH1-1/X86_64/C039BD54B8>) |
| 1022:15e3 | 1022:d001 | AMD              | Family 17h/19h HD Audio Controller   | 3     | snd_hda... | [D55F23484E](<Tablet/Microsoft/Surface/Surface Laptop 3/6407F7577C70/ELEMENTARY-6.1/5.16.11-SURFACE/X86_64/D55F23484E>) |
| 8086:02c8 | 17aa:380a | Intel            | Comet Lake PCH-LP cAVS               | 3     | snd_hda... | [927ED071B3](<Tablet/Lenovo/Yoga/Yoga Duet IML 2020 82E9/8FFE2F20194E/ARCH-ROLLING/5.16.2-ARCH1-1/X86_64/927ED071B3>) |
| 8086:0a0c | 17aa:3978 | Intel            | Haswell-ULT HD Audio Controller      | 3     | snd_hda... | [2D356053D3](<Tablet/Lenovo/MIIX/MIIX 2 11 20327/880F55D78695/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/2D356053D3>) |
| 8086:160c | 17aa:222b | Intel            | Broadwell-U Audio Controller         | 3     | snd_hda... | [5BADA8B921](<Tablet/Lenovo/ThinkPad/ThinkPad Helix 2nd 20CHS1NG03/BD286A22C079/FEDORA-33/5.10.21-200.FC33.X86_64/X86_64/5BADA8B921>) |
| 8086:3198 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 3     | snd_hda... | [DCA4D50A5C](<Tablet/Teclast/X6/X6 plus/C159F9AADE83/MANJARO/5.15.16-1-MANJARO/X86_64/DCA4D50A5C>) |
| 8086:5a98 | 02f3:f101 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | snd_hda... | [4FAC8E2CB1](<Tablet/Digma/EVE/EVE 10 C301T ES1043EW/4F919B905270/LMDE-4/5.15.0-KALI2-AMD64/X86_64/4FAC8E2CB1>) |
| 8086:5a98 | 10ec:11ca | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | snd_hda... | [7D5490C589](<Tablet/Kogan/KAL11/KAL11D600PA/29024B380C2E/UBUNTU-21.04/5.11.0-24-GENERIC/X86_64/7D5490C589>) |
| 8086:5a98 | 8086:5a98 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | snd_hda... | [07C752AA8C](<Tablet/ZoomSmart/A/A1002/F1BBB3E02B52/ROSA-2019.05/5.4.60-NICKEL-2ROSA2019.05-X86_64/X86_64/07C752AA8C>) |
| 8086:9c20 | 17aa:3978 | Intel            | 8 Series HD Audio Controller         | 3     | snd_hda... | [2D356053D3](<Tablet/Lenovo/MIIX/MIIX 2 11 20327/880F55D78695/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/2D356053D3>) |
| 8086:9d70 | 10ec:114a | Intel            | Sunrise Point-LP HD Audio            | 3     | snd_hda... | [F00B37ABE2](<Tablet/RuggedPC/RuggedPadY/RuggedPadY16/172173240BE4/RELS-7.9/4.19.184-1.MPTCP.RES7.X86_64/X86_64/F00B37ABE2>) |
| 8086:9d70 | 19e5:3e00 | Intel            | Sunrise Point-LP HD Audio            | 3     | snd_hda... | [904DECFD32](<Tablet/HUAWEI/MateBook/MateBook HZ-W19/F902238EFB24/LMDE-4/4.19.0-17-AMD64/X86_64/904DECFD32>) |
| 8086:9d71 | 17aa:3806 | Intel            | Sunrise Point-LP HD Audio            | 3     | snd_hda... | [67E1BDD5F1](<Tablet/Lenovo/MIIX/MIIX 720-12IKB 80VV/F45F8CE4052D/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/67E1BDD5F1>) |
| 8086:9d71 | 17aa:380c | Intel            | Sunrise Point-LP HD Audio            | 3     | snd_hda... | [D249085990](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/A4295A395509/POP!_OS-21.10/5.15.8-76051508-GENERIC/X86_64/D249085990>) |
| 8086:a0c8 | 8086:7270 | Intel            | Tiger Lake-LP Smart Sound Technol... | 3     | snd_hda... | [BD290BC56D](<Tablet/Microsoft/Surface/Surface Laptop Studio/AD9CE584B5E1/MANJARO-21.1.6/5.13.19-2-MANJARO/X86_64/BD290BC56D>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9c03 | 1414:9c03 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 67    | ahci       | [92F8B5CBFA](<Tablet/Microsoft/Surface/Surface Pro 3/0558715ED322/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/92F8B5CBFA>) |
| 8086:31e3 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    | ahci       | [74B4233584](<Tablet/AVITA/NS12/NS12T5/1E88FAD8F7A9/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/74B4233584>) |
| 8086:5ae3 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 21    | ahci       | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |
| 1002:4391 | 1025:0577 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 14    | ahci       | [5984A91751](<Tablet/Acer/Iconia/Iconia Tab W500/99578EB02374/ELEMENTARY-6/5.11.0-40-GENERIC/X86_64/5984A91751>) |
| 8086:0f23 | 1019:99a5 | Intel            | Atom Processor E3800 Series SATA ... | 12    | ahci       | [A2B7A04DFA](<Tablet/Intel/powered/powered classmate PC/E3EDE14D59EF/LINUXMINT-20.2/5.4.0-100-GENERIC/X86_64/A2B7A04DFA>) |
| 8086:1e03 | 1414:1e03 | Intel            | 7 Series Chipset Family 6-port SA... | 8     | ahci       | [F1D0D25B44](<Tablet/Microsoft/Surface/Surface with Windows 8 Pro/EC94C82618D5/UBUNTU-20.04/5.15.13-051513-GENERIC/X86_64/F1D0D25B44>) |
| 8086:9d03 | 144d:c14f | Intel            | Sunrise Point-LP SATA Controller ... | 8     | ahci       | [63CAA45089](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12 LTE/F81EBA4C8217/ZORIN-16/5.13.0-30-GENERIC/X86_64/63CAA45089>) |
| 8086:9d03 | 17aa:384d | Intel            | Sunrise Point-LP SATA Controller ... | 7     | ahci       | [8B9FA8F425](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/A89FAAAFC012/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/8B9FA8F425>) |
| 8086:0f23 | 1019:99a1 | Intel            | Atom Processor E3800 Series SATA ... | 6     | ahci       | [C61A96D514](<Tablet/Medion/P/P2212T/71C4E4B2F18A/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/C61A96D514>) |
| 8086:9d03 | 144d:c135 | Intel            | Sunrise Point-LP SATA Controller ... | 6     | ahci       | [3ADAAACD83](<Tablet/Samsung Electronics/Galaxy/Galaxy TabPro S/7232B6211ED3/POP!_OS-21.04/5.13.0-7614-GENERIC/X86_64/3ADAAACD83>) |
| 8086:9d03 | 8086:9d03 | Intel            | Sunrise Point-LP SATA Controller ... | 6     | ahci       | [F00B37ABE2](<Tablet/RuggedPC/RuggedPadY/RuggedPadY16/172173240BE4/RELS-7.9/4.19.184-1.MPTCP.RES7.X86_64/X86_64/F00B37ABE2>) |
| 8086:9d03 | 1028:06e6 | Intel            | Sunrise Point-LP SATA Controller ... | 5     | ahci       | [6430380D5B](<Tablet/Dell/Latitude/Latitude 5179/597547DCB08C/POP!_OS-20.04/5.16.11-76051611-GENERIC/X86_64/6430380D5B>) |
| 8086:9d03 | 1025:111e | Intel            | Sunrise Point-LP SATA Controller ... | 4     | ahci       | [C6DC41A2A5](<Tablet/Acer/Switch/Switch SA5-271/7F70B3D37585/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C6DC41A2A5>) |
| 8086:9d03 | 1028:06d6 | Intel            | Sunrise Point-LP SATA Controller ... | 4     | ahci       | [14BCC9219C](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-21.10/5.16.10-XANMOD1/X86_64/14BCC9219C>) |
| 8086:9d03 | 103c:828b | Intel            | Sunrise Point-LP SATA Controller ... | 4     | ahci       | [5A85AB6B0F](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/608A6BF05466/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/5A85AB6B0F>) |
| 8086:9d03 | 17aa:3827 | Intel            | Sunrise Point-LP SATA Controller ... | 4     | ahci       | [E1BEE3CD30](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/63E5CC1D8A4F/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/E1BEE3CD30>) |
| 8086:5ae3 | 8086:5ae3 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | ahci       | [07C752AA8C](<Tablet/ZoomSmart/A/A1002/F1BBB3E02B52/ROSA-2019.05/5.4.60-NICKEL-2ROSA2019.05-X86_64/X86_64/07C752AA8C>) |
| 8086:9c03 | 8086:7270 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 3     | ahci       | [2D356053D3](<Tablet/Lenovo/MIIX/MIIX 2 11 20327/880F55D78695/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/2D356053D3>) |
| 8086:9c83 | 17aa:222b | Intel            | Wildcat Point-LP SATA Controller ... | 3     | ahci       | [5BADA8B921](<Tablet/Lenovo/ThinkPad/ThinkPad Helix 2nd 20CHS1NG03/BD286A22C079/FEDORA-33/5.10.21-200.FC33.X86_64/X86_64/5BADA8B921>) |
| 8086:9d03 | 17aa:383e | Intel            | Sunrise Point-LP SATA Controller ... | 3     | ahci       | [D249085990](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/A4295A395509/POP!_OS-21.10/5.15.8-76051508-GENERIC/X86_64/D249085990>) |
| 8086:9d03 | 19e5:3e00 | Intel            | Sunrise Point-LP SATA Controller ... | 3     | ahci       | [904DECFD32](<Tablet/HUAWEI/MateBook/MateBook HZ-W19/F902238EFB24/LMDE-4/4.19.0-17-AMD64/X86_64/904DECFD32>) |
| 8086:0f23 | 1509:7018 | Intel            | Atom Processor E3800 Series SATA ... | 2     | ahci       | [9347717861](<Tablet/Xplore/iX101/iX101B1/988A604FB8AB/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/9347717861>) |
| 8086:0f23 | 1854:0211 | Intel            | Atom Processor E3800 Series SATA ... | 2     | ahci       | [44AF16AC16](<Tablet/LG Electronics/15U340/15U340-L.BK55P1/96572D02BF5F/LINUXMINT-20/5.4.0-42-GENERIC/X86_64/44AF16AC16>) |
| 8086:1e03 | 10f7:8338 | Intel            | 7 Series Chipset Family 6-port SA... | 2     | ahci       | [06F11C0449](<Tablet/Panasonic/FZ-G1/FZ-G1ASH39E3/6F2FB083615E/ELEMENTARY-6/5.11.0-37-GENERIC/X86_64/06F11C0449>) |
| 8086:9d03 | 1028:081d | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [2A2BCC9FFA](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/80C1F2BB8F15/UBUNTU-20.10/5.8.0-63-GENERIC/X86_64/2A2BCC9FFA>) |
| 8086:9d03 | 103c:82ca | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [A73A640600](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/04DF3D4F2975/DEBIAN-11/5.14.0-4MX-AMD64/X86_64/A73A640600>) |
| 8086:9d03 | 1043:13c0 | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [4363CA1BD6](<Tablet/ASUSTek Computer/T303/T303UA/C8223D9D63FE/UBUNTU-20.04/5.4.0-33-GENERIC/X86_64/4363CA1BD6>) |
| 8086:9d03 | 1043:1410 | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [C66E4999F0](<Tablet/ASUSTek Computer/T305/T305CA/70CB67E36043/UBUNTU-20.04/5.8.0-50-GENERIC/X86_64/C66E4999F0>) |
| 8086:9d03 | 1043:16c0 | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [D33E67BDF4](<Tablet/ASUSTek Computer/T304/T304UA/8F97F461C23D/UBUNTU-20.04/5.4.0-29-GENERIC/X86_64/D33E67BDF4>) |
| 8086:9d03 | 17aa:2241 | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [923CCB09A5](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GHCTO1WW/70707A835AE8/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/923CCB09A5>) |
| 8086:9d03 | 17aa:3831 | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [4684DBCC91](<Tablet/Lenovo/MIIX/MIIX 720-12IKB 80VV/E890E1333285/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/4684DBCC91>) |
| 8086:9d03 | 1b0a:01d3 | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [60C93DDC01](<Tablet/Xplore/iX125/iX125R1/9DCB305AD004/PUPPY_IMPPUP64-9.6.1/5.15.11-LXPUP64/X86_64/60C93DDC01>) |
| 1c28:0122 | 1b4b:9183 | Lite-On IT Co... | M6e PCI Express SSD [Marvell 88SS... | 1     | ahci       | [568757F9F8](<Tablet/Dell/Latitude/Latitude 5285/9BC7EC024B34/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/568757F9F8>) |
| 8086:0f23 | 1558:5470 | Intel            | Atom Processor E3800 Series SATA ... | 1     | ahci       | [DD65C5ABF7](<Tablet/Lanix/Neuron/Neuron A/9C81E684C8A4/ARCH-ROLLING/5.8.14-ARCH1-1/X86_64/DD65C5ABF7>) |
| 8086:0f23 | 8086:7270 | Intel            | Atom Processor E3800 Series SATA ... | 1     | ahci       | [8F2478944C](<Tablet/Wortmann AG/TERRA_PAD/TERRA_PAD_1060/B40099ED7FF5/FEDORA-31/5.11.0-RC6+/X86_64/8F2478944C>) |
| 8086:1e03 | 1b0a:017b | Intel            | 7 Series Chipset Family 6-port SA... | 1     | ahci       | [5A97B2A1A7](<Tablet/Wacom/Citiq/Citiq Companion/47415E406255/LINUXMINT-19.2/5.0.0-27-GENERIC/X86_64/5A97B2A1A7>) |
| 8086:22a3 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | ahci       | [009BEE9446](<Tablet/Intel/Braswell/Braswell Platform/1E35D60EBB32/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/009BEE9446>) |
| 8086:27c1 | 14c0:006c | Intel            | NM10/ICH7 Family SATA Controller ... | 1     | ahci       | [8FF8AE3115](<Tablet/Motion Computing/CL/CL910/CC59C0B6971E/LINUXMINT-19.3/5.4.0-42-GENERIC/I686/8FF8AE3115>) |
| 8086:31e3 | 8086:31e3 | Intel            | Celeron/Pentium Silver Processor ... | 1     | ahci       | [E35EF99862](<Tablet/ALLDOCUBE/i1022/i1022d/2568497DA66E/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/E35EF99862>) |
| 8086:5ae3 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | ahci       | [49D345EC0B](<Tablet/Xplore/iX101/iX101L1/1592B2F5F479/UBUNTU-20.04/5.6.0-1028-OEM/X86_64/49D345EC0B>) |
| 8086:9d03 | 1028:0702 | Intel            | Sunrise Point-LP SATA Controller ... | 1     | ahci       | [CE9A3F2C74](<Tablet/Dell/XPS/XPS 12 9250/A04CD2743A76/CLEAR-LINUX-OS-35400/5.15.7-1106.NATIVE/X86_64/CE9A3F2C74>) |
| 8086:9d03 | 1028:07a4 | Intel            | Sunrise Point-LP SATA Controller ... | 1     | ahci       | [45B102BEAF](<Tablet/Dell/Latitude/Latitude 5285/BC9528581D40/UBUNTU-20.04/5.4.0-67-LOWLATENCY/X86_64/45B102BEAF>) |
| 8086:9d03 | 103c:8414 | Intel            | Sunrise Point-LP SATA Controller ... | 1     | ahci       | [6EE77ED959](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/3DD573867AA0/UBUNTU-20.04/5.8.0-36-GENERIC/X86_64/6EE77ED959>) |
| 8086:9d03 | 10f7:8338 | Intel            | Sunrise Point-LP SATA Controller ... | 1     | ahci       | [94539C6DB9](<Tablet/Panasonic/CF-33/CF-33-1/AE1D638EDC9E/UBUNTU-12.02/5.11.0-38-GENERIC/X86_64/94539C6DB9>) |
| 8086:9d03 | 8086:7270 | Intel            | Sunrise Point-LP SATA Controller ... | 1     | ahci       | [ED972212E1](<Tablet/Teclast/X6/X6 Pro/F6A57BF3E09B/ARCH/5.10.55-1-LTS/X86_64/ED972212E1>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 70    | nvme       | [04EE5A06F2](<Tablet/Microsoft/Surface/Surface Pro 4/56E5A6DAD16F/KDE-NEON-20.04/5.16.11-SURFACE/X86_64/04EE5A06F2>) |
| 1179:0113 | 1179:0001 | Toshiba Ameri... | BG3 NVMe SSD Controller              | 45    | nvme       | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 39    | nvme       | [D249085990](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/A4295A395509/POP!_OS-21.10/5.15.8-76051508-GENERIC/X86_64/D249085990>) |
| 1c5c:1327 | 1c5c:0000 | SK Hynix         | BC501 NVMe Solid State Drive         | 37    | nvme       | [D55F23484E](<Tablet/Microsoft/Surface/Surface Laptop 3/6407F7577C70/ELEMENTARY-6.1/5.16.11-SURFACE/X86_64/D55F23484E>) |
| 144d:a806 | 144d:a801 | Samsung Elect... | Electronics Non-Volatile memory c... | 20    | nvme       | [1A4F0D32AB](<Tablet/Microsoft/Surface/Surface Pro/39E8C6A4CD9F/FEDORA-35/5.16.10-1.SURFACE.FC35.X86_64/X86_64/1A4F0D32AB>) |
| 1e0f:0001 | 1e0f:0001 | KIOXIA           | Non-Volatile memory controller       | 17    | nvme       | [94E7C9E1ED](<Tablet/Microsoft/Surface/Surface Pro 7/CE57076A28FD/ARCH-ROLLING/5.16.0-ARCH1-1-SURFACE/X86_64/94E7C9E1ED>) |
| 1179:010f | 1179:0001 | Toshiba Ameri... | NVMe Controller                      | 13    | nvme       | [26A4220432](<Tablet/Microsoft/Surface/Surface Pro 4/5171E94FBA49/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/26A4220432>) |
| 8086:f1a5 | 8086:390a | Intel            | SSD 600P Series                      | 11    | nvme       | [56C75F9229](<Tablet/Microsoft/Surface/Surface Pro/30C30BAC02B4/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/56C75F9229>) |
| 1c5c:1527 | 1c5c:1527 | SK Hynix         | PC401 NVMe Solid State Drive 256GB   | 10    | nvme       | [730558C6BD](<Tablet/Microsoft/Surface/Surface Book 2/451432DF4DF7/ELEMENTARY-6.1/5.15.6-SURFACE/X86_64/730558C6BD>) |
| 1179:0116 | 1179:0001 | Toshiba Ameri... | Toshiba America Info Non-Volatile... | 6     | nvme       | [BEEB081772](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/945D2246773B/UBUNTU-MATE-20.04/5.13.0-30-GENERIC/X86_64/BEEB081772>) |
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 5     | nvme       | [55F51A3D6F](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJ0011US/7240D66F8895/POP!_OS-21.04/5.13.0-7614-GENERIC/X86_64/55F51A3D6F>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980              | 5     | nvme       | [BD290BC56D](<Tablet/Microsoft/Surface/Surface Laptop Studio/AD9CE584B5E1/MANJARO-21.1.6/5.13.19-2-MANJARO/X86_64/BD290BC56D>) |
| 15b7:5008 | 15b7:5008 | Sandisk          | Non-Volatile memory controller       | 4     | nvme       | [047FF4AD80](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/37FF40E14E4D/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/047FF4AD80>) |
| 15b7:5009 | 15b7:5009 | Sandisk          | WD Blue SN550 NVMe SSD               | 4     | nvme       | [C039BD54B8](<Tablet/AYADEVICE/AYA/AYA NEO FOUNDER/49BCDD789BF3/ARCH-ROLLING/5.14.11-ARCH1-1/X86_64/C039BD54B8>) |
| 1179:011a | 1179:0001 | Toshiba Ameri... | XG6 NVMe SSD Controller              | 3     | nvme       | [9CFD9C7142](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/39E24435C9D2/ELEMENTARY-6.1/5.13.0-30-GENERIC/X86_64/9CFD9C7142>) |
| 15b7:5007 | 15b7:5007 | Sandisk          | Non-Volatile memory controller       | 3     | nvme       | [255FFC0493](<Tablet/Dell/Latitude/Latitude 7320 Detachable/B080FA5912AF/KUBUNTU-21.10/5.16.0/X86_64/255FFC0493>) |
| 106b:2001 | 106b:2001 | Apple            | S1X NVMe Controller                  | 2     | nvme       | [9E5A5DC6CF](<Tablet/Microsoft/Surface/Surface Pro 6/DE921958CD9C/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/9E5A5DC6CF>) |
| 1179:0115 | 1179:0001 | Toshiba Ameri... | XG4 NVMe SSD Controller              | 2     | nvme       | [6CE5523274](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/D39789DC846A/UBUNTU-20.10/5.8.0-41-GENERIC/X86_64/6CE5523274>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 2     | nvme       | [D47AC58E2B](<Tablet/Dell/Latitude/Latitude 5175/AE5B4A894C5E/DEBIAN-10/5.10.0-8MX-AMD64/X86_64/D47AC58E2B>) |
| 1e95:3500 | 1b4b:1092 | Solid State S... | Non-Volatile memory controller       | 2     | nvme       | [5D9E3F3501](<Tablet/Getac/K120/K120G2/9B90212BD0E9/UBUNTU-18.04/5.4.0-84-GENERIC/X86_64/5D9E3F3501>) |
| 8086:f1a6 | 8086:390b | Intel            | SSD Pro 7600p/760p/E 6100p Series    | 2     | nvme       | [7A3A0603E5](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJ0010US/A3C0804D3B42/FEDORA-33/5.11.7-200.FC33.X86_64/X86_64/7A3A0603E5>) |
| 1344:5410 | 1344:0100 | Micron Techno... | Non-Volatile memory controller       | 1     | nvme       | [1ABEA9314A](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/9C5DA16E7FE7/POP!_OS-20.10/5.11.0-7614-GENERIC/X86_64/1ABEA9314A>) |
| 15b7:5003 | 15b7:5003 | Sandisk          | WD Blue SN500 / PC SN520 NVMe SSD    | 1     | nvme       | [4937A2C0A8](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/6CE16237A9C8/ARCH/5.9.12-ARCH1-1/X86_64/4937A2C0A8>) |
| 15b7:5006 | 15b7:5006 | Sandisk          | WD Black SN750 / PC SN730 NVMe SSD   | 1     | nvme       | [09F8C72D80](<Tablet/Hewlett-Packard/Elite/Elite x2 G4/0472416698D9/UBUNTU-21.04/5.11.0-25-GENERIC/X86_64/09F8C72D80>) |
| 17aa:0003 | 17aa:1003 | Lenovo           | Non-Volatile memory controller       | 1     | nvme       | [F92AE76FED](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJCTO1WW/3D3FB636D7D4/DEVUAN-4/5.10.0-11-AMD64/X86_64/F92AE76FED>) |
| 1c5c:1283 | 1c5c:0000 | SK Hynix         | PC300 NVMe Solid State Drive 256GB   | 1     | nvme       | [71F48F75D2](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/E23B3AA76824/POP!_OS-20.04/5.4.0-7642-GENERIC/X86_64/71F48F75D2>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 1     | nvme       | [F590550713](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/B40E17CB6AAF/MANJARO/5.8.18-1-MANJARO/X86_64/F590550713>) |
| 1cc4:6203 | 1cc4:1cc4 | Union Memory ... | Non-Volatile memory controller       | 1     | nvme       | [927ED071B3](<Tablet/Lenovo/Yoga/Yoga Duet IML 2020 82E9/8FFE2F20194E/ARCH-ROLLING/5.16.2-ARCH1-1/X86_64/927ED071B3>) |
| 1cc4:6204 | 1cc4:1cc4 | Union Memory ... | Non-Volatile memory controller       | 1     | nvme       | [6F0E0FCC43](<Tablet/Lenovo/Yoga/Yoga Duet 7 13IML05 82AS/53D01D6A216A/UBUNTU-20.10/5.8.0-50-GENERIC/X86_64/6F0E0FCC43>) |
| 8086:0975 | 8086:8410 | Intel            | Non-Volatile memory controller       | 1     | nvme       | [EBD997CB1A](<Tablet/Microsoft/Surface/Surface Laptop Go/2C31D4563FEB/ELEMENTARY-6/5.11.0-27-LOWLATENCY/X86_64/EBD997CB1A>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:282a | 1025:1171 | Intel            | 82801 Mobile SATA Controller [RAI... | 2     | ahci       | [4B0ED624FA](<Tablet/Acer/Switch/Switch SW512-52/8FD5C8AAAFE9/ARCH-ROLLING/5.8.12-ARCH1-1/X86_64/4B0ED624FA>) |
| 8086:282a | 17aa:3831 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [67E1BDD5F1](<Tablet/Lenovo/MIIX/MIIX 720-12IKB 80VV/F45F8CE4052D/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/67E1BDD5F1>) |
| 8086:282a | 8086:9d03 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [0F05F12004](<Tablet/Teclast/X5/X5 Pro/B130987D6E6A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0F05F12004>) |
| 8086:9a0b | 1028:0a45 | Intel            | Volume Management Device NVMe RAI... | 1     | vmd        | [21C50317B2](<Tablet/Dell/Latitude/Latitude 7320 Detachable/B080FA5912AF/KUBUNTU-21.04/5.11.0-34-GENERIC/X86_64/21C50317B2>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1911 | 8086:2015 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 87    |            | [26A4220432](<Tablet/Microsoft/Surface/Surface Pro 4/5171E94FBA49/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/26A4220432>) |
| 8086:3190 | 17aa:3802 | Intel            | Celeron/Pentium Silver Processor ... | 8     |            | [C9D8BB9BD9](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGM 81H3/689B95560E77/MANJARO-21.2.3/5.16.7-1-MANJARO/X86_64/C9D8BB9BD9>) |
| 8086:1911 | 8086:1911 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 7     |            | [0F05F12004](<Tablet/Teclast/X5/X5 Pro/B130987D6E6A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0F05F12004>) |
| 8086:1911 | 17aa:2244 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 6     |            | [F92AE76FED](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJCTO1WW/3D3FB636D7D4/DEVUAN-4/5.10.0-11-AMD64/X86_64/F92AE76FED>) |
| 8086:15d2 | 2222:1111 | Intel            | JHL6540 Thunderbolt 3 NHI (C step... | 4     | thunder... | [F92AE76FED](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJCTO1WW/3D3FB636D7D4/DEVUAN-4/5.10.0-11-AMD64/X86_64/F92AE76FED>) |
| 8086:1911 | 17aa:2241 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 4     |            | [923CCB09A5](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GHCTO1WW/70707A835AE8/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/923CCB09A5>) |
| 8086:9a11 | 17aa:382f | Intel            | GNA Scoring Accelerator module       | 4     |            | [047FF4AD80](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/37FF40E14E4D/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/047FF4AD80>) |
| 8086:1911 | 17aa:3883 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 3     |            | [927ED071B3](<Tablet/Lenovo/Yoga/Yoga Duet IML 2020 82E9/8FFE2F20194E/ARCH-ROLLING/5.16.2-ARCH1-1/X86_64/927ED071B3>) |
| 8086:156a |           | Intel            | DSL5320 Thunderbolt 2 NHI [Falcon... | 2     | thunder... | [9E5A5DC6CF](<Tablet/Microsoft/Surface/Surface Pro 6/DE921958CD9C/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/9E5A5DC6CF>) |
| 8086:15d2 | 103c:8414 | Intel            | JHL6540 Thunderbolt 3 NHI (C step... | 2     | thunder... | [6EE77ED959](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/3DD573867AA0/UBUNTU-20.04/5.8.0-36-GENERIC/X86_64/6EE77ED959>) |
| 8086:15eb | 103c:85b9 | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 2     | thunder... | [09F8C72D80](<Tablet/Hewlett-Packard/Elite/Elite x2 G4/0472416698D9/UBUNTU-21.04/5.11.0-25-GENERIC/X86_64/09F8C72D80>) |
| 8086:1911 | 17aa:2243 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [39C0680056](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JB003LMX/2CEEE337E2A9/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/39C0680056>) |
| 8086:1911 | 1b0a:01d3 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [60C93DDC01](<Tablet/Xplore/iX125/iX125R1/9DCB305AD004/PUPPY_IMPPUP64-9.6.1/5.15.11-LXPUP64/X86_64/60C93DDC01>) |
| 8086:09ab |           | Intel            | System peripheral                    | 1     |            | [21C50317B2](<Tablet/Dell/Latitude/Latitude 7320 Detachable/B080FA5912AF/KUBUNTU-21.04/5.11.0-34-GENERIC/X86_64/21C50317B2>) |
| 8086:1193 |           | Intel            | System peripheral                    | 1     |            | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:1194 |           | Intel            | Merrifield Serial IO SPI Controller  | 1     | intel_m... | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:1199 |           | Intel            | Merrifield GPIO Controller           | 1     | langwel... | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:119b |           | Intel            | System peripheral                    | 1     | intel_m... | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:11a2 |           | Intel            | Merrifield Serial IO DMA Controller  | 1     | intel_m... | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:11a5 |           | Intel            | Merrifield Serial IO PWM Controller  | 1     | pwm_int... | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:3190 | 17aa:380e | Intel            | Celeron/Pentium Silver Processor ... | 1     |            | [FD98FD839E](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 10IGL5 82AT/DCC92275F773/FEDORA-34/5.11.21-300.FC34.X86_64/X86_64/FD98FD839E>) |
| 8086:9a11 | 17aa:508b | Intel            | GNA Scoring Accelerator module       | 1     |            | [AAC22AF3A1](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UWCTO1WW/3B7CEBE290BA/DEBIAN-TESTING/5.10.19/X86_64/AAC22AF3A1>) |

### Unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:31a2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 2     | intel_i... | [D476F875D2](<Tablet/Teclast/X6/X6 plus/D578D72C0F87/UBUNTU-BUDGIE-21.10/5.13.0-19-GENERIC/X86_64/D476F875D2>) |
| 8086:1aa2 | 8086:7270 | Intel            | Integrated Sensor Solution           | 1     | intel_i... | [555A26F0D1](<Tablet/Intel/570x/570x DVT3/469D9CAF87D4/UBUNTU-CORE-20/5.4.0-62-GENERIC/X86_64/555A26F0D1>) |
| 8086:5aa2 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | intel_i... | [49D345EC0B](<Tablet/Xplore/iX101/iX101L1/1592B2F5F479/UBUNTU-20.04/5.6.0-1028-OEM/X86_64/49D345EC0B>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d2f | 8086:7270 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 173   | xhci_hcd   | [26A4220432](<Tablet/Microsoft/Surface/Surface Pro 4/5171E94FBA49/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/26A4220432>) |
| 8086:22b5 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 130   | xhci_hcd   | [D8EA22EFF5](<Tablet/Microsoft/Surface/Surface 3/DEBCA8820BEF/DEBIAN-TESTING/5.16.11-SURFACE/X86_64/D8EA22EFF5>) |
| 8086:9c31 | 1414:9c31 | Intel            | 8 Series USB xHCI HC                 | 67    | xhci_hcd   | [92F8B5CBFA](<Tablet/Microsoft/Surface/Surface Pro 3/0558715ED322/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/92F8B5CBFA>) |
| 8086:22b5 | 17aa:380b | Intel            | Atom/Celeron/Pentium Processor x5... | 43    | xhci_hcd   | [4758B6520C](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/6D0C35E280B8/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/4758B6520C>) |
| 8086:22b5 | 17aa:3806 | Intel            | Atom/Celeron/Pentium Processor x5... | 40    | xhci_hcd   | [FB183BFD9B](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/056649DD334F/MANJARO/5.15.25-1-MANJARO/X86_64/FB183BFD9B>) |
| 8086:34ed | 8086:7270 | Intel            | Ice Lake-LP USB 3.1 xHCI Host Con... | 37    | xhci_hcd   | [A4E86F6259](<Tablet/Microsoft/Surface/Surface Pro 7/4B1F7148A63A/ZORIN-16/5.16.5-SURFACE/X86_64/A4E86F6259>) |
| 8086:8a13 |           | Intel            | Ice Lake Thunderbolt 3 USB Contro... | 37    | xhci_hcd   | [A4E86F6259](<Tablet/Microsoft/Surface/Surface Pro 7/4B1F7148A63A/ZORIN-16/5.16.5-SURFACE/X86_64/A4E86F6259>) |
| 8086:22b7 | 8086:7270 | Intel            | USB Synopsys Controller              | 32    | dwc3_pci   | [566A6BEAB3](<Tablet/Teclast/TbooK/TbooK 16 Power/1A1BEDEB4755/KDE-NEON-20.04/5.11.0-41-GENERIC/X86_64/566A6BEAB3>) |
| 8086:0f35 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 29    | xhci_hcd   | [A7034FD62E](<Tablet/Lenovo/ThinkPad/ThinkPad 10 20C3S0P900/F580C65F2E19/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/A7034FD62E>) |
| 8086:31a8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 22    | xhci_hcd   | [DCA4D50A5C](<Tablet/Teclast/X6/X6 plus/C159F9AADE83/MANJARO/5.15.16-1-MANJARO/X86_64/DCA4D50A5C>) |
| 8086:5aa8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 21    | xhci_pci   | [172FC399F5](<Tablet/TrekStor/Primetab/Primetab T13B/2E7402628992/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/172FC399F5>) |
| 8086:22b5 | 103c:827c | Intel            | Atom/Celeron/Pentium Processor x5... | 20    | xhci_hcd   | [9A03FDA057](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/E1DE173C5065/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/9A03FDA057>) |
| 8086:22b5 | 1043:13a0 | Intel            | Atom/Celeron/Pentium Processor x5... | 20    | xhci_hcd   | [05983A1E06](<Tablet/ASUSTek Computer/T101/T101HA/AC331E492606/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/05983A1E06>) |
| 8086:9d2f | 152d:1182 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 20    | xhci_hcd   | [FD978B3F7B](<Tablet/Microsoft/Surface/Surface Go/E701EDF5F7CD/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FD978B3F7B>) |
| 8086:22b5 |           | Intel            | Atom/Celeron/Pentium Processor x5... | 18    | xhci_hcd   | [E88252DB3F](<Tablet/Acer/One/One S1003/9D8E7D4E8A41/UBUNTU-16.04/4.15.0-142-GENERIC/X86_64/E88252DB3F>) |
| 8086:22b7 | 17aa:380a | Intel            | USB Synopsys Controller              | 17    | dwc3_pci   | [FB183BFD9B](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/056649DD334F/MANJARO/5.15.25-1-MANJARO/X86_64/FB183BFD9B>) |
| 8086:22b5 | 1043:1400 | Intel            | Atom/Celeron/Pentium Processor x5... | 16    | xhci_pci   | [ECC5AD7332](<Tablet/ASUSTek Computer/T102/T102HA/C13EDC224850/MX-19/4.19.0-18-AMD64/X86_64/ECC5AD7332>) |
| 8086:9c26 | 1414:9c26 | Intel            | 8 Series USB EHCI #1                 | 16    | ehci_pci   | [275B20283F](<Tablet/Microsoft/Surface/Surface Pro 2/DF18662C511A/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/275B20283F>) |
| 1002:4396 | 1025:0577 | AMD              | SB7x0/SB8x0/SB9x0 USB EHCI Contro... | 14    | ehci_hc... | [5984A91751](<Tablet/Acer/Iconia/Iconia Tab W500/99578EB02374/ELEMENTARY-6/5.11.0-40-GENERIC/X86_64/5984A91751>) |
| 1002:4397 | 1025:0577 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI0 Contr... | 14    | ohci_hc... | [5984A91751](<Tablet/Acer/Iconia/Iconia Tab W500/99578EB02374/ELEMENTARY-6/5.11.0-40-GENERIC/X86_64/5984A91751>) |
| 8086:0f35 | 1019:99a5 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 11    | xhci_hcd   | [A2B7A04DFA](<Tablet/Intel/powered/powered classmate PC/E3EDE14D59EF/LINUXMINT-20.2/5.4.0-100-GENERIC/X86_64/A2B7A04DFA>) |
| 8086:9d2f | 103c:82ca | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 10    | xhci_hcd   | [BEEB081772](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/945D2246773B/UBUNTU-MATE-20.04/5.13.0-30-GENERIC/X86_64/BEEB081772>) |
| 8086:15d4 | 2222:1111 | Intel            | JHL6540 Thunderbolt 3 USB Control... | 8     | xhci_hcd   | [78F2672479](<Tablet/Dell/Latitude/Latitude 7285/35CB641DDB78/CLEAR-LINUX-OS-35940/5.16.11-1128.NATIVE/X86_64/78F2672479>) |
| 8086:1e26 | 1414:1e26 | Intel            | 7 Series/C216 Chipset Family USB ... | 8     | ehci_pci   | [F1D0D25B44](<Tablet/Microsoft/Surface/Surface with Windows 8 Pro/EC94C82618D5/UBUNTU-20.04/5.15.13-051513-GENERIC/X86_64/F1D0D25B44>) |
| 8086:1e2d | 1414:1e2d | Intel            | 7 Series/C216 Chipset Family USB ... | 8     | ehci_pci   | [F1D0D25B44](<Tablet/Microsoft/Surface/Surface with Windows 8 Pro/EC94C82618D5/UBUNTU-20.04/5.15.13-051513-GENERIC/X86_64/F1D0D25B44>) |
| 8086:1e31 | 1414:1e31 | Intel            | 7 Series/C210 Series Chipset Fami... | 8     | xhci_hcd   | [F1D0D25B44](<Tablet/Microsoft/Surface/Surface with Windows 8 Pro/EC94C82618D5/UBUNTU-20.04/5.15.13-051513-GENERIC/X86_64/F1D0D25B44>) |
| 8086:31a8 | 17aa:3812 | Intel            | Celeron/Pentium Silver Processor ... | 8     | xhci_pci   | [C9D8BB9BD9](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGM 81H3/689B95560E77/MANJARO-21.2.3/5.16.7-1-MANJARO/X86_64/C9D8BB9BD9>) |
| 8086:9a1b | 2222:1111 | Intel            | Tiger Lake-LP Thunderbolt 4 NHI #0   | 8     | thunder... | [047FF4AD80](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/37FF40E14E4D/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/047FF4AD80>) |
| 8086:9d2f | 144d:c14f | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 8     | xhci_hcd   | [63CAA45089](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12 LTE/F81EBA4C8217/ZORIN-16/5.13.0-30-GENERIC/X86_64/63CAA45089>) |
| 8086:0f35 | 103c:815d | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 7     | xhci_hcd   | [16B7C17050](<Tablet/Hewlett-Packard/Pavilion/Pavilion x2 Detachable/800BF9CCC703/FEDORA-35/5.14.10-300.FC35.X86_64/X86_64/16B7C17050>) |
| 8086:9d2f | 17aa:3851 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 7     | xhci_hcd   | [8B9FA8F425](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/A89FAAAFC012/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/8B9FA8F425>) |
| 8086:9d2f | 8086:9d2f | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 7     | xhci_hcd   | [0F05F12004](<Tablet/Teclast/X5/X5 Pro/B130987D6E6A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0F05F12004>) |
| 8086:0f35 | 1019:99a1 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 6     | xhci_hcd   | [C61A96D514](<Tablet/Medion/P/P2212T/71C4E4B2F18A/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/C61A96D514>) |
| 8086:0f35 | 17aa:3906 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 6     | xhci_hcd   | [BE55ABE40D](<Tablet/Lenovo/MIIX/MIIX 3-1030 80HV/6B8420DF8C02/KALI-2020.2/5.5.0-KALI2-686-PAE/I686/BE55ABE40D>) |
| 8086:0f35 | 17aa:390b | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 6     | xhci_hcd   | [92D4603EA8](<Tablet/Lenovo/MIIX/MIIX 300-10IBY 80NR/F1574B822916/ARCH/5.6.17/X86_64/92D4603EA8>) |
| 8086:22b5 | 103c:82f4 | Intel            | Atom/Celeron/Pentium Processor x5... | 6     | xhci_pci   | [6CAB74E68A](<Tablet/Hewlett-Packard/x2/x2 210 G2/9F303DEBAE52/XUBUNTU-21.10/5.13.0-28-GENERIC/X86_64/6CAB74E68A>) |
| 8086:9d2f | 1028:06e6 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 6     | xhci_hcd   | [6430380D5B](<Tablet/Dell/Latitude/Latitude 5179/597547DCB08C/POP!_OS-20.04/5.16.11-76051611-GENERIC/X86_64/6430380D5B>) |
| 8086:9d2f | 1028:07a4 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 6     | xhci_hcd   | [568757F9F8](<Tablet/Dell/Latitude/Latitude 5285/9BC7EC024B34/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/568757F9F8>) |
| 8086:9d2f | 103c:828b | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 6     | xhci_hcd   | [5A85AB6B0F](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/608A6BF05466/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/5A85AB6B0F>) |
| 8086:9d2f | 1043:201f | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 6     | xhci_hcd   | [C66E4999F0](<Tablet/ASUSTek Computer/T305/T305CA/70CB67E36043/UBUNTU-20.04/5.8.0-50-GENERIC/X86_64/C66E4999F0>) |
| 8086:9d2f | 144d:c135 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 6     | xhci_hcd   | [3ADAAACD83](<Tablet/Samsung Electronics/Galaxy/Galaxy TabPro S/7232B6211ED3/POP!_OS-21.04/5.13.0-7614-GENERIC/X86_64/3ADAAACD83>) |
| 8086:9d2f | 152d:1237 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 6     | xhci_hcd   | [E530D905DA](<Tablet/Microsoft/Surface/Surface Go 2/356E9AC2E762/ARCH/5.15.11-ARCH2-1-SURFACE/X86_64/E530D905DA>) |
| 8086:9d2f | 17aa:2244 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 6     | xhci_hcd   | [F92AE76FED](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJCTO1WW/3D3FB636D7D4/DEVUAN-4/5.10.0-11-AMD64/X86_64/F92AE76FED>) |
| 8086:22b5 | 1043:1c60 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | xhci_hcd   | [B2D1B00B0A](<Tablet/ASUSTek Computer/T103/T103HAF/F93497AB5707/ZORIN-12/4.13.0-37-GENERIC/X86_64/B2D1B00B0A>) |
| 8086:9d2f | 1028:081d | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 5     | xhci_pci   | [9CFD9C7142](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/39E24435C9D2/ELEMENTARY-6.1/5.13.0-30-GENERIC/X86_64/9CFD9C7142>) |
| 8086:0f35 | 103c:8031 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 4     | xhci_hcd   | [0297D0F732](<Tablet/Hewlett-Packard/Stream/Stream 7 Tablet/2CFECD3BB696/ALPINE-3.15.0_ALPHA20210804/5.10.72-1-LTS/I686/0297D0F732>) |
| 8086:0f35 | 8086:0f35 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 4     | xhci_pci   | [3B331BB4AF](<Tablet/TrekStor/SurfTab/SurfTab wintron 7.0/6B2D27EED579/DEBIAN-TESTING/4.19.0-5-AMD64/X86_64/3B331BB4AF>) |
| 8086:0f37 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 4     | dwc3_pci   | [F19C34B72D](<Tablet/Lenovo/Yoga/Yoga/4DDD6802F5A2/ANDROID/3.10.20-X86_64_BYT-G9FF829D/X86_64/F19C34B72D>) |
| 8086:15b6 | 2222:1111 | Intel            | DSL6540 USB 3.1 Controller [Alpin... | 4     | xhci_hcd   | [14BCC9219C](<Tablet/Dell/Latitude/Latitude 7275/745FAA820535/POP!_OS-21.10/5.16.10-XANMOD1/X86_64/14BCC9219C>) |
| 8086:15db | 2222:1111 | Intel            | JHL6340 Thunderbolt 3 USB 3.1 Con... | 4     | xhci_hcd   | [BEEB081772](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/945D2246773B/UBUNTU-MATE-20.04/5.13.0-30-GENERIC/X86_64/BEEB081772>) |

