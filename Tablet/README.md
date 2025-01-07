Most popular PCI devices in Tablets
-----------------------------------

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Tablets ](#pci-devices)
   * [ Ai inference accelerator ](#ai-inference-accelerator-pci)
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
   * [ Non-essential instrumentation ](#non-essential-instrumentation-pci)
   * [ Non-vga unclassified device ](#non-vga-unclassified-device-pci)
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
   * [ System peripheral ](#system-peripheral-pci)
   * [ Unclassified device ](#unclassified-device-pci)
   * [ Usb controller ](#usb-controller-pci)
   * [ Others ](#others-pci)

PCI Devices
-----------

Count  - number of computers with this device installed,
Driver - driver in use for this device,
Probe  - latest probe ID of this device.

### Ai inference accelerator (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:6240 | 1414:0069 | Intel            | AI Inference Accelerator             | 1     |            | [DC4244CAAE](<Tablet/Microsoft/Surface/Surface Laptop Studio 2/442DCC14A3B5/DEBIAN-12/6.9.3-SURFACE-2/X86_64/DC4244CAAE>) |

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d18 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 425   | pcieport   | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:229c | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 249   | lpc_ich    | [496C93250D](<Tablet/Chuwi/Hi10/Hi10 pro tablet/D5A4927F3C98/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/496C93250D>) |
| 8086:9d14 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 237   | pcieport   | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:9d4e | 8086:7270 | Intel            | Sunrise Point LPC/eSPI Controller    | 208   |            | [EAF1BB652C](<Tablet/Microsoft/Surface/Surface Book 2/B870A7627396/ARCH-ROLLING/6.12.7-ARCH1-1-NSB2/X86_64/EAF1BB652C>) |
| 8086:2280 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 202   | iosf_mb... | [496C93250D](<Tablet/Chuwi/Hi10/Hi10 pro tablet/D5A4927F3C98/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/496C93250D>) |
| 8086:1904 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 179   | skl_uncore | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:9d48 | 8086:7270 | Intel            | Sunrise Point-LP LPC Controller      | 179   |            | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:9d13 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 164   | pcieport   | [FD805CEEB5](<Tablet/Microsoft/Surface/Surface Go 3/2F23800DE848/UBUNTU-24.10/6.12.3-SURFACE-2/X86_64/FD805CEEB5>) |
| 8086:3482 | 8086:7270 | Intel            | Ice Lake-LP LPC Controller           | 152   |            | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:0a04 | 1414:0a04 | Intel            | Haswell-ULT DRAM Controller          | 150   | hsw_uncore | [BB626D70B0](<Tablet/Microsoft/Surface/Surface Pro 3/217C1E4144F1/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/BB626D70B0>) |
| 8086:34b0 | 8086:7270 | Intel            | Ice Lake-LP PCI Express Root Port #9 | 150   | pcieport   | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:9c43 | 1414:9c43 | Intel            | 8 Series LPC Controller              | 150   | lpc_ich    | [BB626D70B0](<Tablet/Microsoft/Surface/Surface Pro 3/217C1E4144F1/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/BB626D70B0>) |
| 8086:22c8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 146   | pcieport   | [3C5D9B1B2B](<Tablet/Microsoft/Surface/Surface 3/59BC6F4C45B8/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/3C5D9B1B2B>) |
| 8086:8a12 | 8086:7270 | Intel            | Ice Lake-LP Processor Host Bridge... | 143   | icl_uncore | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:5904 | 8086:2015 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 122   | skl_uncore | [C9024275E0](<Tablet/Microsoft/Surface/Surface Pro/F31CC379A03C/UBUNTU-24.04/6.10.10-SURFACE-1/X86_64/C9024275E0>) |
| 8086:9c14 | 1414:9c14 | Intel            | 8 Series PCI Express Root Port 3     | 119   | pcieport   | [BB626D70B0](<Tablet/Microsoft/Surface/Surface Pro 3/217C1E4144F1/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/BB626D70B0>) |
| 8086:5914 | 8086:2015 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 99    | skl_uncore | [EAF1BB652C](<Tablet/Microsoft/Surface/Surface Book 2/B870A7627396/ARCH-ROLLING/6.12.7-ARCH1-1-NSB2/X86_64/EAF1BB652C>) |
| 8086:31e8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 90    |            | [1827AD6649](<Tablet/Microsoft/Surface/Surface Laptop SE/3C3B6159F009/ZORIN-17/6.8.0-49-GENERIC/X86_64/1827AD6649>) |
| 1022:14ea |           | AMD              | Phoenix Dummy Host Bridge            | 83    |            | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 8086:2280 | 17aa:38e3 | Intel            | Atom/Celeron/Pentium Processor x5... | 80    | iosf_mb... | [53BAB82FAE](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/384948008566/ALPINE-3.20.3/6.6.63-0-LTS/X86_64/53BAB82FAE>) |
| 8086:229c | 17aa:380d | Intel            | Atom/Celeron/Pentium Processor x5... | 80    | lpc_ich    | [53BAB82FAE](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/384948008566/ALPINE-3.20.3/6.6.63-0-LTS/X86_64/53BAB82FAE>) |
| 1022:14f0 |           | AMD              | Phoenix Data Fabric; Function 0      | 78    |            | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 1022:14f1 |           | AMD              | Phoenix Data Fabric; Function 1      | 78    |            | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 1022:14f2 |           | AMD              | Phoenix Data Fabric; Function 2      | 78    |            | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 1022:14f3 |           | AMD              | Phoenix Data Fabric; Function 3      | 78    | k10temp    | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 1022:14f4 |           | AMD              | Phoenix Data Fabric; Function 4      | 78    |            | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 1022:14f5 |           | AMD              | Phoenix Data Fabric; Function 5      | 78    |            | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 1022:14f6 |           | AMD              | Phoenix Data Fabric; Function 6      | 78    |            | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 1022:14f7 |           | AMD              | Phoenix Data Fabric; Function 7      | 78    |            | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 8086:31d8 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 72    | pcieport   | [D3AC0F6A92](<Tablet/AVITA/NS12/NS12T5/2D1154BB2648/ZORIN-17/6.8.0-47-GENERIC/X86_64/D3AC0F6A92>) |
| 1022:14eb | 1022:14eb | AMD              | Phoenix Internal GPP Bridge to Bu... | 65    | pcieport   | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 8086:2280 | 17aa:3809 | Intel            | Atom/Celeron/Pentium Processor x5... | 65    | iosf_mb... | [C377803591](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/FE4476C805C4/KDE-NEON-24.04/6.8.0-47-GENERIC/X86_64/C377803591>) |
| 8086:229c | 17aa:380a | Intel            | Atom/Celeron/Pentium Processor x5... | 65    | lpc_ich    | [C377803591](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/FE4476C805C4/KDE-NEON-24.04/6.8.0-47-GENERIC/X86_64/C377803591>) |
| 8086:31da | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 64    | pcieport   | [1827AD6649](<Tablet/Microsoft/Surface/Surface Laptop SE/3C3B6159F009/ZORIN-17/6.8.0-49-GENERIC/X86_64/1827AD6649>) |
| 8086:31d9 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 60    | pcieport   | [D3AC0F6A92](<Tablet/AVITA/NS12/NS12T5/2D1154BB2648/ZORIN-17/6.8.0-47-GENERIC/X86_64/D3AC0F6A92>) |
| 1022:790e | 1022:790e | AMD              | FCH LPC Bridge                       | 59    |            | [2183EB76B7](<Tablet/ONE-NETBOOK/ONEXPLAYER/ONEXPLAYER Mini Pro/F55453A23AA1/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/2183EB76B7>) |
| 8086:9d16 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 58    | pcieport   | [FD805CEEB5](<Tablet/Microsoft/Surface/Surface Go 3/2F23800DE848/UBUNTU-24.10/6.12.3-SURFACE-2/X86_64/FD805CEEB5>) |
| 8086:5af0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 57    |            | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:a082 | 8086:7270 | Intel            | Tiger Lake-LP LPC Controller         | 57    |            | [DA3534B096](<Tablet/Microsoft/Surface/Surface Pro 7+/87B1E5086B44/DEBIAN-12/6.1.0-28-AMD64/X86_64/DA3534B096>) |
| 8086:5ad7 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 56    | pcieport   | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:5ae8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 56    | lpc_ich    | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:9a09 | 8086:7270 | Intel            | 11th Gen Core Processor PCIe Cont... | 56    | pcieport   | [DA3534B096](<Tablet/Microsoft/Surface/Surface Pro 7+/87B1E5086B44/DEBIAN-12/6.1.0-28-AMD64/X86_64/DA3534B096>) |
| 8086:9a14 | 8086:7270 | Intel            | 11th Gen Core Processor Host Brid... | 55    | igen6_edac | [DA3534B096](<Tablet/Microsoft/Surface/Surface Pro 7+/87B1E5086B44/DEBIAN-12/6.1.0-28-AMD64/X86_64/DA3534B096>) |
| 8086:590c | 152d:1182 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 54    | skl_uncore | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 8086:9d12 | 152d:1182 | Intel            | Sunrise Point-LP PCI Express Root... | 54    | pcieport   | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 8086:9d4b | 152d:1182 | Intel            | Skylake-U/Y LPC/eSPI Controller      | 54    |            | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 8086:0f1c | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 52    | lpc_ich    | [0C43F7A18D](<Tablet/Wortmann AG/TERRA_PAD/TERRA_PAD_1061/2774F6C08D8F/UBUNTU-22.04/6.8.0-49-GENERIC/X86_64/0C43F7A18D>) |
| 8086:9d13 | 152d:1182 | Intel            | Sunrise Point-LP PCI Express Root... | 50    | pcieport   | [131E4B1570](<Tablet/Microsoft/Surface/Surface Go/DED51204263A/DEBIAN-12/6.1.0-28-AMD64/X86_64/131E4B1570>) |
| 8086:9d1b | 8086:7270 | Intel            | Skylake-U/Y PCIe Port #12            | 48    | pcieport   | [E334442819](<Tablet/Microsoft/Surface/Surface Book/D7F4D70DD18A/POP!_OS-22.04/6.12.3-SURFACE-2/X86_64/E334442819>) |
| 8086:9d10 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 47    | pcieport   | [EAF1BB652C](<Tablet/Microsoft/Surface/Surface Book 2/B870A7627396/ARCH-ROLLING/6.12.7-ARCH1-1-NSB2/X86_64/EAF1BB652C>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:525a | 10ec:525a | Realtek Semic... | RTS525A PCI Express Card Reader      | 59    | rtsx_pci   | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 10ec:522a | 152d:1182 | Realtek Semic... | RTS522A PCI Express Card Reader      | 50    | rtsx_pci   | [131E4B1570](<Tablet/Microsoft/Surface/Surface Go/DED51204263A/DEBIAN-12/6.1.0-28-AMD64/X86_64/131E4B1570>) |
| 10ec:522a | 152d:1237 | Realtek Semic... | RTS522A PCI Express Card Reader      | 47    | rtsx_pci   | [FD805CEEB5](<Tablet/Microsoft/Surface/Surface Go 3/2F23800DE848/UBUNTU-24.10/6.12.3-SURFACE-2/X86_64/FD805CEEB5>) |
| 10ec:522a | 103c:82ca | Realtek Semic... | RTS522A PCI Express Card Reader      | 36    | rtsx_pci   | [F0D42DF827](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/0C327DDF3EC7/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/F0D42DF827>) |
| 10ec:525a | 1028:081d | Realtek Semic... | RTS525A PCI Express Card Reader      | 27    | rtsx_pci   | [20E6DC4833](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/069C27C420D3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.12.6-1-DEFAULT/X86_64/20E6DC4833>) |
| 10ec:522a | 103c:828b | Realtek Semic... | RTS522A PCI Express Card Reader      | 26    | rtsx_pci   | [567E4C6343](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/53B866CA15BB/ZORIN-17/6.8.0-45-GENERIC/X86_64/567E4C6343>) |
| 10ec:522a | 10ec:522a | Realtek Semic... | RTS522A PCI Express Card Reader      | 26    | rtsx_pci   | [58F0C948E1](<Tablet/AYANEO/AIR/AIR 1S/CC615E1970CF/CHIMERAOS-46-2/6.9.12-CHOS7-CHIMERAOS-1/X86_64/58F0C948E1>) |
| 10ec:522a | 17aa:2244 | Realtek Semic... | RTS522A PCI Express Card Reader      | 24    | rtsx_pci   | [454126AC6E](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KKS0S901/980E2F97C968/ARCH-ROLLING/6.12.6-ZEN1-1-ZEN/X86_64/454126AC6E>) |
| 10ec:5229 | 17aa:3833 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 17    | rtsx_pci   | [9BE1FF58FB](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGM 81MD/672E3FB63585/UBUNTU-24.04/6.8.0-38-GENERIC/X86_64/9BE1FF58FB>) |
| 10ec:522a | 17aa:2243 | Realtek Semic... | RTS522A PCI Express Card Reader      | 17    | rtsx_pci   | [BA288E243C](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCS06N0D/45C0E5B583E8/NIXOS-24.05/6.6.66/X86_64/BA288E243C>) |
| 10ec:5229 | 10ec:5229 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 13    | rtsx_pci   | [E2281326E3](<Tablet/Chuwi/UBook/UBook X/D592012A6396/DEEPIN-23/6.1.11-AMD64-DESKTOP-HWE/X86_64/E2281326E3>) |
| 10ec:525a | 1028:07a4 | Realtek Semic... | RTS525A PCI Express Card Reader      | 13    | rtsx_pci   | [9BDEF7697E](<Tablet/Dell/Latitude/Latitude 5285/03AE783826C3/ZORIN-17/6.8.0-45-GENERIC/X86_64/9BDEF7697E>) |
| 10ec:522a | 17aa:2241 | Realtek Semic... | RTS522A PCI Express Card Reader      | 11    | rtsx_pci   | [047961B6D0](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/7D7EF3298D39/FEDORA-41/6.12.5-200.FC41.X86_64/X86_64/047961B6D0>) |
| 10ec:525a | 1028:06e6 | Realtek Semic... | RTS525A PCI Express Card Reader      | 11    | rtsx_pci   | [31A3C7AF1E](<Tablet/Dell/Latitude/Latitude 5175/CD1C9C82C174/FEDORA-41/6.11.11-300.FC41.X86_64/X86_64/31A3C7AF1E>) |
| 10ec:525a | 1028:06d6 | Realtek Semic... | RTS525A PCI Express Card Reader      | 8     | rtsx_pci   | [0FD89EC85A](<Tablet/Dell/Latitude/Latitude 7275/55EB4B609DF6/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/0FD89EC85A>) |
| 10ec:5229 | 17aa:382e | Realtek Semic... | RTS5229 PCI Express Card Reader      | 7     | rtsx_pci   | [D4E1FD3279](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 20M3/9A2627AE7E17/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/D4E1FD3279>) |
| 10ec:522a | 17aa:3823 | Realtek Semic... | RTS522A PCI Express Card Reader      | 7     | rtsx_pci   | [03E0FB2CF4](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 10IGL5 82AT/3CFD92916C27/FEDORA-40/6.9.4-200.FC40.X86_64/X86_64/03E0FB2CF4>) |
| 10ec:525a | 1028:09ba | Realtek Semic... | RTS525A PCI Express Card Reader      | 7     | rtsx_pci   | [657C7CAF3D](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/B6F2D71B615A/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/657C7CAF3D>) |
| 10ec:522a | 17aa:382a | Realtek Semic... | RTS522A PCI Express Card Reader      | 6     | rtsx_pci   | [AF8A5DF7BE](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/4236AA030B1D/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/AF8A5DF7BE>) |
| 10ec:525a | 1028:08e9 | Realtek Semic... | RTS525A PCI Express Card Reader      | 4     | rtsx_pci   | [8D53A4B7AB](<Tablet/Dell/Latitude/Latitude 7200 2-in-1/733991F40E18/MANJARO/6.9.0-1-MANJARO/X86_64/8D53A4B7AB>) |
| 10ec:522a | 103c:824c | Realtek Semic... | RTS522A PCI Express Card Reader      | 3     | rtsx_pci   | [6CA12FAB01](<Tablet/Hewlett-Packard/ZBook/ZBook x2 G4/E1BE91E1F9DE/ARCH-ROLLING/6.6.38-1-LTS/X86_64/6CA12FAB01>) |
| 10ec:522a | 103c:82cb | Realtek Semic... | RTS522A PCI Express Card Reader      | 3     | rtsx_pci   | [9DE6B65A45](<Tablet/Hewlett-Packard/Spectre/Spectre x2 Detachable 12-c0XX/107C5ABF10E7/ARCH-ROLLING/6.2.2-ARCH1-1/X86_64/9DE6B65A45>) |
| 10ec:525a | 1028:07d3 | Realtek Semic... | RTS525A PCI Express Card Reader      | 3     | rtsx_pci   | [72351CCF77](<Tablet/Dell/Latitude/Latitude 7212 Rugged Extreme Tablet/EDF0638A4664/FEDORA-40/6.9.4-201.FSYNC.FC40.X86_64/X86_64/72351CCF77>) |
| 10ec:522a | 1025:122b | Realtek Semic... | RTS522A PCI Express Card Reader      | 2     | rtsx_pci   | [46ECB88F1D](<Tablet/Acer/Switch/Switch SW713-51GNP/3C0AE30715BA/NIXOS-22.11/6.1.9/X86_64/46ECB88F1D>) |
| 10ec:525a | 1043:202f | Realtek Semic... | RTS525A PCI Express Card Reader      | 2     | rtsx_pci   | [E35C79DDE2](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301VU_GZ301VU/2F999BBF1AC8/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/E35C79DDE2>) |
| 10ec:5209 | 1854:0230 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 1     | rtsx_pci   | [15040C5EF1](<Tablet/LG Electronics/14U360/14U360-L.AJ12B6/AB26612096A1/UBUNTU-22.04/6.2.0-37-GENERIC/X86_64/15040C5EF1>) |
| 10ec:522a | 17aa:3816 | Realtek Semic... | RTS522A PCI Express Card Reader      | 1     | rtsx_pci   | [2C581034EB](<Tablet/Lenovo/Yoga/Yoga Duet 7 13IML05 82AS/6049DBFEB1C3/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/2C581034EB>) |
| 10ec:525a | 1028:0702 | Realtek Semic... | RTS525A PCI Express Card Reader      | 1     | rtsx_pci   | [CE9A3F2C74](<Tablet/Dell/XPS/XPS 12 9250/A04CD2743A76/CLEAR-LINUX-OS-35400/5.15.7-1106.NATIVE/X86_64/CE9A3F2C74>) |
| 10ec:525a | 1414:0081 | Realtek Semic... | RTS525A PCI Express Card Reader      | 1     | rtsx_pci   | [DC4244CAAE](<Tablet/Microsoft/Surface/Surface Laptop Studio 2/442DCC14A3B5/DEBIAN-12/6.9.3-SURFACE-2/X86_64/DC4244CAAE>) |
| 10ec:525a | 1462:143a | Realtek Semic... | RTS525A PCI Express Card Reader      | 1     | rtsx_pci   | [2EBDE0820D](<Tablet/MSI/Claw/Claw A1M/E9FB50149AEE/STEAMOS-ROLLING/6.11.1-1/X86_64/2EBDE0820D>) |
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
| 8086:9d3a | 8086:7270 | Intel            | Sunrise Point-LP CSME HECI #1        | 442   | mei_me     | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:9d3e |           | Intel            | iTouch Controller                    | 420   | mei_me     | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:34a8 | 8086:7270 | Intel            | Ice Lake-LP Serial IO UART Contro... | 152   | intel_l... | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:34e0 | 8086:7270 | Intel            | Ice Lake-LP Management Engine        | 152   | mei_me     | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:9c3a | 1414:9c3a | Intel            | 8 Series HECI #0                     | 120   | mei_me     | [BB626D70B0](<Tablet/Microsoft/Surface/Surface Pro 3/217C1E4144F1/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/BB626D70B0>) |
| 8086:319a | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 87    | mei_me     | [026269E60B](<Tablet/Others/Others/Others/B4F90A2AAF5D/LINUXMINT-22/6.8.0-50-GENERIC/X86_64/026269E60B>) |
| 8086:34e4 | 1414:0039 | Intel            | Precise Touch Device                 | 75    | mei_me     | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:5a9a | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 57    | mei_me     | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:a0e0 | 8086:7270 | Intel            | Tiger Lake-LP Management Engine I... | 57    | mei_me     | [DA3534B096](<Tablet/Microsoft/Surface/Surface Pro 7+/87B1E5086B44/DEBIAN-12/6.1.0-28-AMD64/X86_64/DA3534B096>) |
| 8086:a0a8 | 8086:7270 | Intel            | Tiger Lake-LP Serial IO UART Cont... | 56    | intel_l... | [DA3534B096](<Tablet/Microsoft/Surface/Surface Pro 7+/87B1E5086B44/DEBIAN-12/6.1.0-28-AMD64/X86_64/DA3534B096>) |
| 8086:9d3a | 152d:1182 | Intel            | Sunrise Point-LP CSME HECI #1        | 54    | mei_me     | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 8086:9d3a | 103c:82ca | Intel            | Sunrise Point-LP CSME HECI #1        | 35    | mei_me     | [F0D42DF827](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/0C327DDF3EC7/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/F0D42DF827>) |
| 8086:9c3a | 8086:9c3a | Intel            | 8 Series HECI #0                     | 30    | mei_me     | [964F81A59E](<Tablet/Microsoft/Surface/Surface Pro 2/9A502B2F7D5F/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/964F81A59E>) |
| 8086:9d3a | 1028:081d | Intel            | Sunrise Point-LP CSME HECI #1        | 27    | mei_me     | [20E6DC4833](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/069C27C420D3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.12.6-1-DEFAULT/X86_64/20E6DC4833>) |
| 8086:9d3a | 17aa:2244 | Intel            | Sunrise Point-LP CSME HECI #1        | 25    | mei_me     | [454126AC6E](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KKS0S901/980E2F97C968/ARCH-ROLLING/6.12.6-ZEN1-1-ZEN/X86_64/454126AC6E>) |
| 8086:51e0 | 1043:1c42 | Intel            | Alder Lake PCH HECI Controller       | 24    | mei_me     | [0A76D54F2A](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZE_GZ301ZE/E93163333EB2/UBUNTUSTUDIO-24.10/6.11.0-9-GENERIC/X86_64/0A76D54F2A>) |
| 8086:9d3a | 152d:1237 | Intel            | Sunrise Point-LP CSME HECI #1        | 24    | mei_me     | [51D7C66A4E](<Tablet/Microsoft/Surface/Surface Go 2/CC8450395E18/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/51D7C66A4E>) |
| 8086:9d3a | 103c:828b | Intel            | Sunrise Point-LP CSME HECI #1        | 23    | mei_me     | [567E4C6343](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/53B866CA15BB/ZORIN-17/6.8.0-45-GENERIC/X86_64/567E4C6343>) |
| 8086:9d3a | 17aa:3850 | Intel            | Sunrise Point-LP CSME HECI #1        | 21    | mei_me     | [C14BE2A0FF](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/A8FA91459A71/ZORIN-17/6.8.0-40-GENERIC/X86_64/C14BE2A0FF>) |
| 8086:1e3a | 1414:1e3a | Intel            | 7 Series/C216 Chipset Family MEI ... | 20    | mei_me     | [36F734B633](<Tablet/Microsoft/Surface/Surface with Windows 8 Pro/D5A3B8E8FDF9/NIXOS-24.11/6.10.5/X86_64/36F734B633>) |
| 8086:34e4 | 1414:0041 | Intel            | Precise Touch Device                 | 20    | mei_me     | [4F05C770AE](<Tablet/Microsoft/Surface/Surface Laptop 3/D38AB2951087/UBUNTU-22.04/5.15.0-110-LOWLATENCY/X86_64/4F05C770AE>) |
| 8086:319a | 17aa:3824 | Intel            | Celeron/Pentium Silver Processor ... | 17    | mei_me     | [9BE1FF58FB](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGM 81MD/672E3FB63585/UBUNTU-24.04/6.8.0-38-GENERIC/X86_64/9BE1FF58FB>) |
| 8086:9d3a | 17aa:2243 | Intel            | Sunrise Point-LP CSME HECI #1        | 17    | mei_me     | [BA288E243C](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCS06N0D/45C0E5B583E8/NIXOS-24.05/6.6.66/X86_64/BA288E243C>) |
| 8086:319a | 17aa:381f | Intel            | Celeron/Pentium Silver Processor ... | 13    | mei_me     | [5DAD085952](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 10IGL5 82AT/F87C264A0B49/FEDORA-40/6.11.4-201.FC40.X86_64/X86_64/5DAD085952>) |
| 8086:51a8 | 8086:7270 | Intel            | Alder Lake PCH UART #0               | 13    | intel_l... | [E6F037A5E8](<Tablet/Microsoft/Surface/Surface Pro 9/9EE1E883AC5A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E6F037A5E8>) |
| 8086:51e0 | 8086:7270 | Intel            | Alder Lake PCH HECI Controller       | 13    | mei_me     | [E6F037A5E8](<Tablet/Microsoft/Surface/Surface Pro 9/9EE1E883AC5A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E6F037A5E8>) |
| 8086:9d3a | 1028:07a4 | Intel            | Sunrise Point-LP CSME HECI #1        | 13    | mei_me     | [9BDEF7697E](<Tablet/Dell/Latitude/Latitude 5285/03AE783826C3/ZORIN-17/6.8.0-45-GENERIC/X86_64/9BDEF7697E>) |
| 8086:a0e0 | 1028:0a45 | Intel            | Tiger Lake-LP Management Engine I... | 13    | mei_me     | [88D7EDA3A3](<Tablet/Dell/Latitude/Latitude 7320 Detachable/2FA880CABA50/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/88D7EDA3A3>) |
| 8086:9d3a | 10f7:8338 | Intel            | Sunrise Point-LP CSME HECI #1        | 12    | mei_me     | [FAF64BB8A0](<Tablet/Panasonic/CF-33/CF-33-1/71D2DD20CB26/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/FAF64BB8A0>) |
| 8086:a0e0 | 17aa:508b | Intel            | Tiger Lake-LP Management Engine I... | 12    | mei_me     | [57D1EC52E3](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UW0013US/9FE17438E905/DEBIAN-12/6.1.0-27-AMD64/X86_64/57D1EC52E3>) |
| 8086:9d3a | 1028:06e6 | Intel            | Sunrise Point-LP CSME HECI #1        | 11    | mei_me     | [31A3C7AF1E](<Tablet/Dell/Latitude/Latitude 5175/CD1C9C82C174/FEDORA-41/6.11.11-300.FC41.X86_64/X86_64/31A3C7AF1E>) |
| 8086:9d3a | 103c:8414 | Intel            | Sunrise Point-LP CSME HECI #1        | 11    | mei_me     | [A1F8F4C528](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/92E2795CC5F7/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/A1F8F4C528>) |
| 8086:9d3a | 144d:c14f | Intel            | Sunrise Point-LP CSME HECI #1        | 11    | mei_me     | [EBD4E47906](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/EBD4E47906>) |
| 8086:9d3a | 17aa:2241 | Intel            | Sunrise Point-LP CSME HECI #1        | 11    | mei_me     | [047961B6D0](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/7D7EF3298D39/FEDORA-41/6.12.5-200.FC41.X86_64/X86_64/047961B6D0>) |
| 8086:9d3a | 17aa:3841 | Intel            | Sunrise Point-LP CSME HECI #1        | 11    | mei_me     | [00DE3D7E4C](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/248F2E7667A2/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/00DE3D7E4C>) |
| 8086:a0e0 | 1ec9:3e44 | Intel            | Tiger Lake-LP Management Engine I... | 11    | mei_me     | [2D0F2950BA](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/DFD066B5B806/FEDORA-41/6.11.7-300.FC41.X86_64/X86_64/2D0F2950BA>) |
| 8086:34e4 | 1414:0040 | Intel            | Precise Touch Device                 | 10    | mei_me     | [03611F8371](<Tablet/Microsoft/Surface/Surface Book 3/B4A23748E2D4/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/03611F8371>) |
| 8086:a0e0 | 17aa:381e | Intel            | Tiger Lake-LP Management Engine I... | 10    | mei_me     | [AF8A5DF7BE](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/4236AA030B1D/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/AF8A5DF7BE>) |
| 8086:51e0 | 17aa:381b | Intel            | Alder Lake PCH HECI Controller       | 9     | mei_me     | [F2B2FFBFFE](<Tablet/Lenovo/XiaoXinDuet/XiaoXinDuet IAU7 82TQ/5FF690C6ECBE/KYLIN-V10/6.8.0-45-GENERIC/X86_64/F2B2FFBFFE>) |
| 8086:7e25 | 1043:1c43 | Intel            | Meteor Lake-P Serial IO UART Cont... | 9     | intel_lpss | [DE52972775](<Tablet/ASUSTek Computer/ASUS/ASUS Zenbook Duo UX8406MA_UX8406MA/8A069640761E/ZORIN-17/6.8.0-50-GENERIC/X86_64/DE52972775>) |
| 8086:7e70 | 1043:1c43 | Intel            | Meteor Lake-P CSME HECI #1           | 9     | mei_me     | [DE52972775](<Tablet/ASUSTek Computer/ASUS/ASUS Zenbook Duo UX8406MA_UX8406MA/8A069640761E/ZORIN-17/6.8.0-50-GENERIC/X86_64/DE52972775>) |
| 8086:34e4 | 1414:0042 | Intel            | Precise Touch Device                 | 8     | mei_me     | [43EB88BC46](<Tablet/Microsoft/Surface/Surface Book 3/7640F4E38A0D/UBUNTU-22.04/6.5.0-21-GENERIC/X86_64/43EB88BC46>) |
| 8086:4de0 |           | Intel            | Management Engine Interface          | 8     | mei_me     | [E83E0E4EFA](<Tablet/RuggedPC/RuggedBookJ/RuggedBookJ61/3077AC07A524/FEDORA-40/6.11.3-200.FC40.X86_64/X86_64/E83E0E4EFA>) |
| 8086:9cba | 17aa:222b | Intel            | Wildcat Point-LP MEI Controller #1   | 8     | mei_me     | [DABF58331D](<Tablet/Lenovo/ThinkPad/ThinkPad Helix 2nd 20CGCTO1WW/C514BF421B7F/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/DABF58331D>) |
| 8086:9d3a | 1025:111e | Intel            | Sunrise Point-LP CSME HECI #1        | 8     | mei_me     | [E68A5B419E](<Tablet/Acer/Switch/Switch SA5-271/8143477D8A59/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/E68A5B419E>) |
| 8086:9d3a | 1028:06d6 | Intel            | Sunrise Point-LP CSME HECI #1        | 8     | mei_me     | [0FD89EC85A](<Tablet/Dell/Latitude/Latitude 7275/55EB4B609DF6/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/0FD89EC85A>) |
| 8086:9d3a | 144d:c135 | Intel            | Sunrise Point-LP CSME HECI #1        | 8     | mei_me     | [F27DFBBBFB](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/FEDORA-40/6.11.3-200.FC40.X86_64/X86_64/F27DFBBBFB>) |
| 8086:9d3a | 8086:9d3a | Intel            | Sunrise Point-LP CSME HECI #1        | 8     | mei_me     | [80F7F9C98A](<Tablet/RuggedPC/RuggedPadY/RuggedPadY22/665AAC6AB368/UBUNTU-MATE-22.04/6.2.0-39-GENERIC/X86_64/80F7F9C98A>) |
| 8086:9de0 | 103c:85b9 | Intel            | Cannon Point-LP MEI Controller #1    | 8     | mei_me     | [C43E6E357D](<Tablet/Hewlett-Packard/Elite/Elite x2 G4/28B313198BDD/OPENSUSE-LEAP-15.6/6.4.0-150600.23.25-DEFAULT/X86_64/C43E6E357D>) |
| 8086:02a8 | 1028:09ba | Intel            | Comet Lake PCH-LP LPSS: UART #0      | 7     | intel_l... | [657C7CAF3D](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/B6F2D71B615A/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/657C7CAF3D>) |

### Digitizer pen (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a0d0 | 1414:0055 | Intel            | Tiger Lake-LP Precise Touch and S... | 17    | ithc       | [0B901FDA6F](<Tablet/Microsoft/Surface/Surface Pro 8/2ECF330FF091/FEDORA-40/6.8.5-301.FC40.X86_64/X86_64/0B901FDA6F>) |
| 8086:a0d0 | 1414:0056 | Intel            | Tiger Lake-LP Precise Touch and S... | 10    | ithc       | [DA3534B096](<Tablet/Microsoft/Surface/Surface Pro 7+/87B1E5086B44/DEBIAN-12/6.1.0-28-AMD64/X86_64/DA3534B096>) |
| 8086:51d0 | 1414:0064 | Intel            | Alder Lake-U Smart Sound Technolo... | 9     | ithc       | [E6F037A5E8](<Tablet/Microsoft/Surface/Surface Pro 9/9EE1E883AC5A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E6F037A5E8>) |
| 8086:a0d0 | 1414:0049 | Intel            | Tiger Lake-LP Precise Touch and S... | 9     | ithc       | [79C895B3A3](<Tablet/Microsoft/Surface/Surface Laptop Studio/7EAF7CBE4A58/FEDORA-40/6.10.10-1.SURFACE.FC40.X86_64/X86_64/79C895B3A3>) |
| 8086:a0d0 | 1414:0052 | Intel            | Tiger Lake-LP Precise Touch and S... | 8     | ithc       | [1FA8DA20AD](<Tablet/Microsoft/Surface/Surface Laptop 4/FAA9CF059CA5/ZORIN-17/6.5.0-41-GENERIC/X86_64/1FA8DA20AD>) |
| 8086:a0d0 | 1414:0053 | Intel            | Tiger Lake-LP Precise Touch and S... | 4     |            | [70C6936CFC](<Tablet/Microsoft/Surface/Surface Laptop 4/A358A0E16EED/PARROT-5.3/6.1.0-1PARROT1-AMD64/X86_64/70C6936CFC>) |
| 8086:51d0 | 1414:0077 | Intel            | Alder Lake-U Smart Sound Technolo... | 1     | ithc       | [DC4244CAAE](<Tablet/Microsoft/Surface/Surface Laptop Studio 2/442DCC14A3B5/DEBIAN-12/6.9.3-SURFACE-2/X86_64/DC4244CAAE>) |
| 8086:51d1 | 8086:7270 | Intel            | Digitizer Pen                        | 1     | ithc       | [DC4244CAAE](<Tablet/Microsoft/Surface/Surface Laptop Studio 2/442DCC14A3B5/DEBIAN-12/6.9.3-SURFACE-2/X86_64/DC4244CAAE>) |
| 8086:98d0 |           | Intel            | Precise Touch and Stylus Port #1     | 1     |            | [A06677F6EA](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Fold Gen 1 20RL000GIX/E29339E09DD9/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/A06677F6EA>) |

### Dma controller (eisa dma) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0f40 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | dw_dmac... | [198C15E90A](<Tablet/System Mfg/Others/Others/AF6F46232DB6/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/198C15E90A>) |
| 8086:2286 | 10f7:8338 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | dw_dmac... | [BEEB215141](<Tablet/Panasonic/FZB2/FZB2-2/BA668A2C2665/ANTIX-23.1/6.1.105-ANTIX.1-AMD64-SMP/X86_64/BEEB215141>) |
| 8086:22c0 | 10f7:8338 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | dw_dmac... | [BEEB215141](<Tablet/Panasonic/FZB2/FZB2-2/BA668A2C2665/ANTIX-23.1/6.1.105-ANTIX.1-AMD64-SMP/X86_64/BEEB215141>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2298 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 246   | mei_txe    | [496C93250D](<Tablet/Chuwi/Hi10/Hi10 pro tablet/D5A4927F3C98/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/496C93250D>) |
| 8086:2298 | 17aa:380c | Intel            | Atom/Celeron/Pentium Processor x5... | 80    | mei_txe    | [53BAB82FAE](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/384948008566/ALPINE-3.20.3/6.6.63-0-LTS/X86_64/53BAB82FAE>) |
| 8086:2298 | 17aa:380a | Intel            | Atom/Celeron/Pentium Processor x5... | 65    | mei_txe    | [C377803591](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/FE4476C805C4/KDE-NEON-24.04/6.8.0-47-GENERIC/X86_64/C377803591>) |
| 8086:0f18 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 51    | mei_txe    | [0C43F7A18D](<Tablet/Wortmann AG/TERRA_PAD/TERRA_PAD_1061/2774F6C08D8F/UBUNTU-22.04/6.8.0-49-GENERIC/X86_64/0C43F7A18D>) |
| 8086:2298 | 1043:13a0 | Intel            | Atom/Celeron/Pentium Processor x5... | 42    | mei_txe    | [2AA1D5261D](<Tablet/ASUSTek Computer/T101/T101HA/302BE3A15A2C/LMDE-6/6.1.0-23-AMD64/X86_64/2AA1D5261D>) |
| 1022:15c7 | 1022:15c7 | AMD              | Phoenix CCP/PSP 3.0 Device           | 40    | ccp        | [FD3DE9EA5C](<Tablet/ASUSTek Computer/ROG/ROG Ally RC71L_RC71L/16B794CF2193/BAZZITE-41/6.11.10-304.BAZZITE.FC41.X86_64/X86_64/FD3DE9EA5C>) |
| 1022:15df | 1022:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 31    | ccp        | [F51B8777E8](<Tablet/ONE-NETBOOK TECHNOLOGY/ONE/ONE XPLAYER/B1E0FDA01E2B/CHIMERAOS-46-2/6.9.12-CHOS7-CHIMERAOS-1/X86_64/F51B8777E8>) |
| 8086:2298 | 103c:827c | Intel            | Atom/Celeron/Pentium Processor x5... | 30    | mei_txe    | [878A94CA7F](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/3D11A237BEFA/ZORIN-17/6.8.0-49-GENERIC/X86_64/878A94CA7F>) |
| 8086:0f18 | 1019:99a5 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 27    | mei_txe    | [DA6CE4B361](<Tablet/BANGHO/Suma/Suma 1025/DF80AD331B24/ZORIN-17/6.8.0-49-GENERIC/X86_64/DA6CE4B361>) |
| 8086:2298 | 1043:1400 | Intel            | Atom/Celeron/Pentium Processor x5... | 27    | mei_txe    | [073DCFBEFD](<Tablet/ASUSTek Computer/T102/T102HA/B8F0B026C483/ZORIN-17/6.5.0-25-GENERIC/X86_64/073DCFBEFD>) |
| 1022:15c7 | 17aa:3812 | AMD              | Phoenix CCP/PSP 3.0 Device           | 25    | ccp        | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 1022:1649 | 1022:1649 | AMD              | Family 19h PSP/CCP                   | 20    | ccp        | [2183EB76B7](<Tablet/ONE-NETBOOK/ONEXPLAYER/ONEXPLAYER Mini Pro/F55453A23AA1/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/2183EB76B7>) |
| 1022:15c7 | 1f4c:e001 | AMD              | Phoenix CCP/PSP 3.0 Device           | 18    | ccp        | [0BC6665145](<Tablet/Micro Computer (HK) Tech Limited/V/V3/F17AC0C7E80F/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/0BC6665145>) |
| 8086:2298 | 103c:82f4 | Intel            | Atom/Celeron/Pentium Processor x5... | 17    | mei_txe    | [042A3DA123](<Tablet/Hewlett-Packard/x2/x2 210 G2/EFBCD466DE81/KDE-NEON-22.04/6.8.0-49-GENERIC/X86_64/042A3DA123>) |
| 8086:0f18 | 103c:815d | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 15    | mei_txe    | [D7604BBC06](<Tablet/Hewlett-Packard/Pavilion/Pavilion x2 Detachable/165374AB7432/DEBIAN-12/6.1.0-27-686-PAE/I686/D7604BBC06>) |
| 8086:2298 | 1043:1c60 | Intel            | Atom/Celeron/Pentium Processor x5... | 12    | mei_txe    | [284559C037](<Tablet/ASUSTek Computer/T103/T103HAF/265AB1CA9D09/FEDORA-42/6.12.0-0.RC7.59.FC42.X86_64/X86_64/284559C037>) |
| 8086:0f18 | 17aa:390b | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 11    | mei_txe    | [811D729065](<Tablet/Lenovo/Others/Others/3647B31878D4/DEBIAN-12/6.1.0-25-AMD64/X86_64/811D729065>) |
| 8086:0f18 | 17aa:3906 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 9     | mei_txe    | [35AED6A35B](<Tablet/Lenovo/MIIX/MIIX 3-1030 80HV/1C9791F6C241/ARCH-ROLLING/6.6.32-1-LTS/X86_64/35AED6A35B>) |
| 8086:0f18 | 1019:99a1 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 7     | mei_txe    | [0AC4B868CB](<Tablet/Medion/P/P2212T/1CC59B4B188A/FEDORA-40/6.9.5-200.FC40.X86_64/X86_64/0AC4B868CB>) |
| 8086:0f18 | 8086:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 7     | mei_txe    | [21166D1DC5](<Tablet/Medion/S1219T/S1219T MD99667/B99C40ACD496/FEDORA-39/6.5.11-300.FC39.X86_64/X86_64/21166D1DC5>) |
| 8086:0f18 | 103c:8031 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | mei_txe    | [BD41D30E3B](<Tablet/Hewlett-Packard/Stream/Stream 7 Tablet/2CFECD3BB696/ALPINE-3.21.0_ALPHA20240807/6.6.52-1-LTS/I686/BD41D30E3B>) |
| 8086:2298 | 10cf:191b | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | mei_txe    | [A8C473704C](<Tablet/Fujitsu/FARQ/FARQ17004/CE7CF5AB9A17/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/A8C473704C>) |
| 8086:0f18 | 103c:8032 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     | mei_txe    | [211438A893](<Tablet/Hewlett-Packard/Stream/Stream 8 Tablet/54B442EB7035/DEBIAN-11/5.10.0-20-686/I686/211438A893>) |
| 8086:2298 | 1d72:1502 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | mei_txe    | [5F3A7B7A19](<Tablet/Xiaomi/Mipad/Mipad2/86E10DD4C731/FEDORA-40/6.8.5-301.FC40.X86_64/X86_64/5F3A7B7A19>) |
| 8086:0f18 | 1025:0949 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | mei_txe    | [47AC9C9778](<Tablet/Acer/Iconia/Iconia W1-810/96CAA6195904/GENTOO-2.15/6.6.32-GENTOO-DIST/X86_64/47AC9C9778>) |
| 8086:0f18 | 1509:7018 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | mei_txe    | [9347717861](<Tablet/Xplore/iX101/iX101B1/988A604FB8AB/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/9347717861>) |
| 8086:0f18 | 17aa:3900 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | mei_txe    | [4E4D2ED404](<Tablet/Lenovo/MIIX/MIIX 2 8 20326/0C23042EF88F/ENDLESS-4.0.7/5.11.0-35-GENERIC/X86_64/4E4D2ED404>) |
| 8086:0f18 | 17aa:3985 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | mei_txe    | [212388E78B](<Tablet/Lenovo/MIIX/MIIX 2 10 20359/516241B1CF51/DEBIAN-11/5.10.0-10-AMD64/X86_64/212388E78B>) |
| 8086:0f18 | 1854:0211 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | mei_txe    | [44AF16AC16](<Tablet/LG Electronics/15U340/15U340-L.BK55P1/96572D02BF5F/LINUXMINT-20/5.4.0-42-GENERIC/X86_64/44AF16AC16>) |
| 8086:2298 | 1071:a126 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | mei_txe    | [EDE8155598](<Tablet/Getac/T800/T800G2/A89C411CD27C/UBUNTU-23.10/6.5.0-5-GENERIC/X86_64/EDE8155598>) |
| 8086:0f18 | 1019:980b | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [B09FE8903A](<Tablet/Intel/Education/Education Tablet/DEFE34A6E3C6/ENDLESS-3.8.7/5.4.0-42-GENERIC/X86_64/B09FE8903A>) |
| 8086:0f18 | 1558:5470 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [DD65C5ABF7](<Tablet/Lanix/Neuron/Neuron A/9C81E684C8A4/ARCH-ROLLING/5.8.14-ARCH1-1/X86_64/DD65C5ABF7>) |
| 8086:0f18 | 17aa:3915 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [621742BA14](<Tablet/Lenovo/MIIX/MIIX 3-830 80JB/DF2D4D9C1EB5/ARCH/5.18.5-ARCH1-1/X86_64/621742BA14>) |
| 8086:0f18 | 17aa:6080 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [06FE78096E](<Tablet/NEC Computers/PC-TW508/PC-TW508CAS/825BA310157C/ZORIN-16/5.11.0-41-GENERIC/X86_64/06FE78096E>) |
| 8086:1198 |           | Intel            | Encryption controller                | 1     |            | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:2298 | 10f7:8338 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | mei_txe    | [BEEB215141](<Tablet/Panasonic/FZB2/FZB2-2/BA668A2C2665/ANTIX-23.1/6.1.105-ANTIX.1-AMD64-SMP/X86_64/BEEB215141>) |
| 8086:2298 | 1854:0230 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | mei_txe    | [15040C5EF1](<Tablet/LG Electronics/14U360/14U360-L.AJ12B6/AB26612096A1/UBUNTU-22.04/6.2.0-37-GENERIC/X86_64/15040C5EF1>) |
| 8086:2298 | 1854:0280 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | mei_txe    | [A6AB074BB5](<Tablet/LG Electronics/10T370/10T370-L860K/FC0AE2C9A307/ENDLESS-3.9.1/5.8.0-14-GENERIC/X86_64/A6AB074BB5>) |
| 8086:2298 | 1bfd:0001 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | mei_txe    | [1BA20022CB](<Tablet/Medion/E1239T/E1239T MD60791/B4344693BF47/ENDLESS-3.9.0/5.8.0-14-GENERIC/X86_64/1BA20022CB>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:22b0 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 201   | i915       | [496C93250D](<Tablet/Chuwi/Hi10/Hi10 pro tablet/D5A4927F3C98/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/496C93250D>) |
| 8086:1916 | 1414:0015 | Intel            | Skylake GT2 [HD Graphics 520]        | 104   | i915       | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:0a16 | 1414:0005 | Intel            | Haswell-ULT Integrated Graphics C... | 81    | i915       | [BB626D70B0](<Tablet/Microsoft/Surface/Surface Pro 3/217C1E4144F1/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/BB626D70B0>) |
| 8086:22b0 | 17aa:38e3 | Intel            | Atom/Celeron/Pentium Processor x5... | 80    | i915       | [53BAB82FAE](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/384948008566/ALPINE-3.20.3/6.6.63-0-LTS/X86_64/53BAB82FAE>) |
| 8086:5916 | 1414:0026 | Intel            | HD Graphics 620                      | 76    | i915       | [9102694F7E](<Tablet/Microsoft/Surface/Surface Pro/9A38A6808044/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/9102694F7E>) |
| 8086:22b0 | 17aa:3809 | Intel            | Atom/Celeron/Pentium Processor x5... | 65    | i915       | [C377803591](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/FE4476C805C4/KDE-NEON-24.04/6.8.0-47-GENERIC/X86_64/C377803591>) |
| 8086:591e | 152d:1182 | Intel            | HD Graphics 615                      | 54    | i915       | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 8086:1916 | 1414:0014 | Intel            | Skylake GT2 [HD Graphics 520]        | 48    | i915       | [E334442819](<Tablet/Microsoft/Surface/Surface Book/D7F4D70DD18A/POP!_OS-22.04/6.12.3-SURFACE-2/X86_64/E334442819>) |
| 8086:3185 | 8086:2212 | Intel            | GeminiLake [UHD Graphics 600]        | 45    | i915       | [BA2C5EBEB6](<Tablet/Chuwi/Hi10/Hi10 X/4B35B1C8A705/CLEAR-LINUX-OS-42100/6.10.1-1453.NATIVE/X86_64/BA2C5EBEB6>) |
| 8086:5917 | 1414:0026 | Intel            | UHD Graphics 620                     | 44    | i915       | [0BAD8A7035](<Tablet/Microsoft/Surface/Surface Pro 6/FB029469AE3E/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/0BAD8A7035>) |
| 8086:22b0 | 1043:13a0 | Intel            | Atom/Celeron/Pentium Processor x5... | 42    | i915       | [2AA1D5261D](<Tablet/ASUSTek Computer/T101/T101HA/302BE3A15A2C/LMDE-6/6.1.0-23-AMD64/X86_64/2AA1D5261D>) |
| 8086:8a5a | 1414:0037 | Intel            | Iris Plus Graphics G4 (Ice Lake)     | 41    | i915       | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:8a56 | 1414:0047 | Intel            | Iris Plus Graphics G1 (Ice Lake)     | 37    | i915       | [D8B0DBE711](<Tablet/Microsoft/Surface/Surface Laptop Go/F491C595F80D/ARCH-ROLLING/6.12.7-ZEN1-1-ZEN/X86_64/D8B0DBE711>) |
| 8086:5916 | 103c:82ca | Intel            | HD Graphics 620                      | 36    | i915       | [F0D42DF827](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/0C327DDF3EC7/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/F0D42DF827>) |
| 8086:22b0 | 1414:0009 | Intel            | Atom/Celeron/Pentium Processor x5... | 33    | i915       | [3C5D9B1B2B](<Tablet/Microsoft/Surface/Surface 3/59BC6F4C45B8/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/3C5D9B1B2B>) |
| 8086:0a16 | 1414:0a16 | Intel            | Haswell-ULT Integrated Graphics C... | 30    | i915       | [964F81A59E](<Tablet/Microsoft/Surface/Surface Pro 2/9A502B2F7D5F/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/964F81A59E>) |
| 8086:0a26 | 1414:0005 | Intel            | Haswell-ULT Integrated Graphics C... | 30    | i915       | [BE39955885](<Tablet/Microsoft/Surface/Surface Pro 3/CAC1EEEF0FA5/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/BE39955885>) |
| 8086:22b0 | 103c:827c | Intel            | Atom/Celeron/Pentium Processor x5... | 30    | i915       | [878A94CA7F](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/3D11A237BEFA/ZORIN-17/6.8.0-49-GENERIC/X86_64/878A94CA7F>) |
| 8086:5a85 | 8086:2212 | Intel            | HD Graphics 500                      | 29    | i915       | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:0f31 | 1019:99a5 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 27    | i915       | [DA6CE4B361](<Tablet/BANGHO/Suma/Suma 1025/DF80AD331B24/ZORIN-17/6.8.0-49-GENERIC/X86_64/DA6CE4B361>) |
| 8086:1926 | 1414:0015 | Intel            | Iris Graphics 540                    | 27    | i915       | [45E2DB1C09](<Tablet/Microsoft/Surface/Surface Pro 4/D21A8EAC61B0/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/45E2DB1C09>) |
| 8086:22b0 | 1043:1400 | Intel            | Atom/Celeron/Pentium Processor x5... | 27    | i915       | [073DCFBEFD](<Tablet/ASUSTek Computer/T102/T102HA/B8F0B026C483/ZORIN-17/6.5.0-25-GENERIC/X86_64/073DCFBEFD>) |
| 8086:5917 | 1028:081d | Intel            | UHD Graphics 620                     | 27    | i915       | [20E6DC4833](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/069C27C420D3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.12.6-1-DEFAULT/X86_64/20E6DC4833>) |
| 8086:591e | 103c:828b | Intel            | HD Graphics 615                      | 26    | i915       | [567E4C6343](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/53B866CA15BB/ZORIN-17/6.8.0-45-GENERIC/X86_64/567E4C6343>) |
| 1002:15bf | 17aa:3812 | AMD              | Phoenix1                             | 25    | amdgpu     | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 8086:5917 | 17aa:2244 | Intel            | UHD Graphics 620                     | 25    | i915       | [454126AC6E](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KKS0S901/980E2F97C968/ARCH-ROLLING/6.12.6-ZEN1-1-ZEN/X86_64/454126AC6E>) |
| 8086:8a52 | 1414:0037 | Intel            | Iris Plus Graphics G7                | 25    | i915       | [38D39ED934](<Tablet/Microsoft/Surface/Surface Pro 7/6A6CF6229D52/KDE-NEON-22.04/6.8.0-45-GENERIC/X86_64/38D39ED934>) |
| 1002:15bf | 1043:17f3 | AMD              | Phoenix1                             | 24    | amdgpu     | [FD3DE9EA5C](<Tablet/ASUSTek Computer/ROG/ROG Ally RC71L_RC71L/16B794CF2193/BAZZITE-41/6.11.10-304.BAZZITE.FC41.X86_64/X86_64/FD3DE9EA5C>) |
| 8086:591c | 152d:1237 | Intel            | UHD Graphics 615                     | 24    | i915       | [51D7C66A4E](<Tablet/Microsoft/Surface/Surface Go 2/CC8450395E18/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/51D7C66A4E>) |
| 8086:0f31 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 23    | i915       | [0C43F7A18D](<Tablet/Wortmann AG/TERRA_PAD/TERRA_PAD_1061/2774F6C08D8F/UBUNTU-22.04/6.8.0-49-GENERIC/X86_64/0C43F7A18D>) |
| 8086:5917 | 1414:0027 | Intel            | UHD Graphics 620                     | 23    | i915       | [EAF1BB652C](<Tablet/Microsoft/Surface/Surface Book 2/B870A7627396/ARCH-ROLLING/6.12.7-ARCH1-1-NSB2/X86_64/EAF1BB652C>) |
| 8086:8a52 | 1414:0035 | Intel            | Iris Plus Graphics G7                | 22    | i915       | [9B9453F5A7](<Tablet/Microsoft/Surface/Surface Laptop 3/8211324321C7/KUBUNTU-2.1/5.4.0-125-GENERIC/X86_64/9B9453F5A7>) |
| 8086:0166 | 1414:0166 | Intel            | 3rd Gen Core processor Graphics C... | 21    | i915       | [09BDD29B6C](<Tablet/Microsoft/Surface/Surface Pro 2/DD2937B6F574/VANILLA-2.0/6.11.6-AMD64/X86_64/09BDD29B6C>) |
| 8086:0f31 | 17aa:221b | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 21    | i915       | [16806FC7D9](<Tablet/Lenovo/ThinkPad/ThinkPad 10 20C3S0Q200/2F0407CF54D5/FEDORA-40/6.10.9-200.FC40.X86_64/X86_64/16806FC7D9>) |
| 8086:5917 | 17aa:397a | Intel            | UHD Graphics 620                     | 19    | i915       | [C14BE2A0FF](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/A8FA91459A71/ZORIN-17/6.8.0-40-GENERIC/X86_64/C14BE2A0FF>) |
| 8086:591c | 152d:1339 | Intel            | UHD Graphics 615                     | 19    | i915       | [FD805CEEB5](<Tablet/Microsoft/Surface/Surface Go 3/2F23800DE848/UBUNTU-24.10/6.12.3-SURFACE-2/X86_64/FD805CEEB5>) |
| 1002:1681 | 1002:0124 | AMD              | Rembrandt [Radeon 680M]              | 18    | amdgpu     | [A09E8B0E7B](<Tablet/GPD/G1618/G1618-04/DC5F4D01ABCF/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/A09E8B0E7B>) |
| 1002:1900 | 1f4c:e001 | AMD              | Phoenix3                             | 18    | amdgpu     | [0BC6665145](<Tablet/Micro Computer (HK) Tech Limited/V/V3/F17AC0C7E80F/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/0BC6665145>) |
| 8086:8a52 | 1414:0043 | Intel            | Iris Plus Graphics G7                | 18    | i915       | [03611F8371](<Tablet/Microsoft/Surface/Surface Book 3/B4A23748E2D4/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/03611F8371>) |
| 8086:22b0 | 103c:82f4 | Intel            | Atom/Celeron/Pentium Processor x5... | 17    | i915       | [042A3DA123](<Tablet/Hewlett-Packard/x2/x2 210 G2/EFBCD466DE81/KDE-NEON-22.04/6.8.0-49-GENERIC/X86_64/042A3DA123>) |
| 8086:46a6 | 1043:1c42 | Intel            | Alder Lake-P GT2 [Iris Xe Graphics]  | 17    | i915       | [0A76D54F2A](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZE_GZ301ZE/E93163333EB2/UBUNTUSTUDIO-24.10/6.11.0-9-GENERIC/X86_64/0A76D54F2A>) |
| 8086:5916 | 1414:0025 | Intel            | HD Graphics 620                      | 17    | i915       | [4E489A30F1](<Tablet/Microsoft/Surface/Surface Laptop/CDD11658960B/ZORIN-17/6.10.5-SURFACE-1/X86_64/4E489A30F1>) |
| 8086:5917 | 1414:0028 | Intel            | UHD Graphics 620                     | 17    | i915       | [E9EC9E62A2](<Tablet/Microsoft/Surface/Surface Book 2/2B7E0582A8AD/ENDEAVOUROS-ROLLING/6.11.4-ARCH1-1-SURFACE/X86_64/E9EC9E62A2>) |
| 8086:591e | 17aa:2243 | Intel            | HD Graphics 615                      | 17    | i915       | [BA288E243C](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCS06N0D/45C0E5B583E8/NIXOS-24.05/6.6.66/X86_64/BA288E243C>) |
| 8086:9a49 | 1414:0046 | Intel            | TigerLake-LP GT2 [Iris Xe Graphics]  | 17    | i915       | [0B901FDA6F](<Tablet/Microsoft/Surface/Surface Pro 8/2ECF330FF091/FEDORA-40/6.8.5-301.FC40.X86_64/X86_64/0B901FDA6F>) |
| 10de:1c8d | 1414:0024 | Nvidia           | GP107M [GeForce GTX 1050 Mobile]     | 16    | nvidia     | [722BCD469D](<Tablet/Microsoft/Surface/Surface Book 2/DD49815CEE0C/KDE-NEON-22.04/6.8.8-SURFACE-1/X86_64/722BCD469D>) |
| 10de:25a0 | 1043:1c42 | Nvidia           | GA107M [GeForce RTX 3050 Ti Mobile]  | 16    | nvidia     | [0A76D54F2A](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZE_GZ301ZE/E93163333EB2/UBUNTUSTUDIO-24.10/6.11.0-9-GENERIC/X86_64/0A76D54F2A>) |
| 1002:9804 | 1025:0577 | AMD              | Wrestler [Radeon HD 6250]            | 15    | radeon     | [AC15CCA834](<Tablet/Acer/Iconia/Iconia Tab W500/00630A96A0A7/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/AC15CCA834>) |
| 8086:0f31 | 103c:815d | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 15    | i915       | [D7604BBC06](<Tablet/Hewlett-Packard/Pavilion/Pavilion x2 Detachable/165374AB7432/DEBIAN-12/6.1.0-27-686-PAE/I686/D7604BBC06>) |
| 8086:5917 | 1414:0025 | Intel            | UHD Graphics 620                     | 15    | i915       | [16F55FA716](<Tablet/Microsoft/Surface/Surface Laptop 2/7BC6E0F5617F/ZORIN-17/6.8.0-40-GENERIC/X86_64/16F55FA716>) |

### Iommu (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:14e9 | 1022:14e9 | AMD              | Phoenix IOMMU                        | 40    |            | [FD3DE9EA5C](<Tablet/ASUSTek Computer/ROG/ROG Ally RC71L_RC71L/16B794CF2193/BAZZITE-41/6.11.10-304.BAZZITE.FC41.X86_64/X86_64/FD3DE9EA5C>) |
| 1022:14e9 | 17aa:3812 | AMD              | Phoenix IOMMU                        | 25    |            | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 1022:14b6 | 1022:14b6 | AMD              | Family 17h-19h IOMMU                 | 20    |            | [2183EB76B7](<Tablet/ONE-NETBOOK/ONEXPLAYER/ONEXPLAYER Mini Pro/F55453A23AA1/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/2183EB76B7>) |
| 1022:1631 | 1022:1631 | AMD              | Renoir/Cezanne IOMMU                 | 20    |            | [F51B8777E8](<Tablet/ONE-NETBOOK TECHNOLOGY/ONE/ONE XPLAYER/B1E0FDA01E2B/CHIMERAOS-46-2/6.9.12-CHOS7-CHIMERAOS-1/X86_64/F51B8777E8>) |
| 1022:14e9 | 1f4c:e001 | AMD              | Phoenix IOMMU                        | 18    |            | [0BC6665145](<Tablet/Micro Computer (HK) Tech Limited/V/V3/F17AC0C7E80F/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/0BC6665145>) |
| 1022:15d1 | 1022:15d1 | AMD              | Raven/Raven2 IOMMU                   | 11    |            | [B575C6A898](<Tablet/ayn/Loki/Loki Zero/D5E63EAE79B0/BAZZITE-40/6.9.12-205.FSYNC.FC40.X86_64/X86_64/B575C6A898>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d21 | 8086:7270 | Intel            | Sunrise Point-LP PMC                 | 448   |            | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:34ef |           | Intel            | Ice Lake-LP DRAM Controller          | 152   |            | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:a0ef | 8086:7270 | Intel            | Tiger Lake-LP Shared SRAM            | 57    |            | [DA3534B096](<Tablet/Microsoft/Surface/Surface Pro 7+/87B1E5086B44/DEBIAN-12/6.1.0-28-AMD64/X86_64/DA3534B096>) |
| 8086:9d21 | 152d:1182 | Intel            | Sunrise Point-LP PMC                 | 54    |            | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 8086:9d21 | 103c:82ca | Intel            | Sunrise Point-LP PMC                 | 36    |            | [F0D42DF827](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/0C327DDF3EC7/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/F0D42DF827>) |
| 8086:9d21 | 1028:081d | Intel            | Sunrise Point-LP PMC                 | 27    |            | [20E6DC4833](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/069C27C420D3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.12.6-1-DEFAULT/X86_64/20E6DC4833>) |
| 8086:9d21 | 103c:828b | Intel            | Sunrise Point-LP PMC                 | 26    |            | [567E4C6343](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/53B866CA15BB/ZORIN-17/6.8.0-45-GENERIC/X86_64/567E4C6343>) |
| 8086:9d21 | 17aa:2244 | Intel            | Sunrise Point-LP PMC                 | 25    |            | [454126AC6E](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KKS0S901/980E2F97C968/ARCH-ROLLING/6.12.6-ZEN1-1-ZEN/X86_64/454126AC6E>) |
| 8086:51ef | 1043:1c42 | Intel            | Alder Lake PCH Shared SRAM           | 24    |            | [0A76D54F2A](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZE_GZ301ZE/E93163333EB2/UBUNTUSTUDIO-24.10/6.11.0-9-GENERIC/X86_64/0A76D54F2A>) |
| 8086:9d21 | 152d:1237 | Intel            | Sunrise Point-LP PMC                 | 24    |            | [51D7C66A4E](<Tablet/Microsoft/Surface/Surface Go 2/CC8450395E18/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/51D7C66A4E>) |
| 8086:9d21 | 17aa:3853 | Intel            | Sunrise Point-LP PMC                 | 21    |            | [C14BE2A0FF](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/A8FA91459A71/ZORIN-17/6.8.0-40-GENERIC/X86_64/C14BE2A0FF>) |
| 8086:9d21 | 17aa:2243 | Intel            | Sunrise Point-LP PMC                 | 17    |            | [BA288E243C](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCS06N0D/45C0E5B583E8/NIXOS-24.05/6.6.66/X86_64/BA288E243C>) |
| 8086:51ef | 8086:7270 | Intel            | Alder Lake PCH Shared SRAM           | 13    |            | [E6F037A5E8](<Tablet/Microsoft/Surface/Surface Pro 9/9EE1E883AC5A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E6F037A5E8>) |
| 8086:9d21 | 1028:07a4 | Intel            | Sunrise Point-LP PMC                 | 13    |            | [9BDEF7697E](<Tablet/Dell/Latitude/Latitude 5285/03AE783826C3/ZORIN-17/6.8.0-45-GENERIC/X86_64/9BDEF7697E>) |
| 8086:a0ef | 1028:0a45 | Intel            | Tiger Lake-LP Shared SRAM            | 13    |            | [88D7EDA3A3](<Tablet/Dell/Latitude/Latitude 7320 Detachable/2FA880CABA50/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/88D7EDA3A3>) |
| 8086:9d21 | 10f7:8338 | Intel            | Sunrise Point-LP PMC                 | 12    |            | [FAF64BB8A0](<Tablet/Panasonic/CF-33/CF-33-1/71D2DD20CB26/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/FAF64BB8A0>) |
| 8086:a0ef | 17aa:508b | Intel            | Tiger Lake-LP Shared SRAM            | 12    |            | [57D1EC52E3](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UW0013US/9FE17438E905/DEBIAN-12/6.1.0-27-AMD64/X86_64/57D1EC52E3>) |
| 8086:9d21 | 1028:06e6 | Intel            | Sunrise Point-LP PMC                 | 11    |            | [31A3C7AF1E](<Tablet/Dell/Latitude/Latitude 5175/CD1C9C82C174/FEDORA-41/6.11.11-300.FC41.X86_64/X86_64/31A3C7AF1E>) |
| 8086:9d21 | 103c:8414 | Intel            | Sunrise Point-LP PMC                 | 11    |            | [A1F8F4C528](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/92E2795CC5F7/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/A1F8F4C528>) |
| 8086:9d21 | 144d:c14f | Intel            | Sunrise Point-LP PMC                 | 11    |            | [EBD4E47906](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/EBD4E47906>) |
| 8086:9d21 | 17aa:2241 | Intel            | Sunrise Point-LP PMC                 | 11    |            | [047961B6D0](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/7D7EF3298D39/FEDORA-41/6.12.5-200.FC41.X86_64/X86_64/047961B6D0>) |
| 8086:9d21 | 17aa:3842 | Intel            | Sunrise Point-LP PMC                 | 11    |            | [00DE3D7E4C](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/248F2E7667A2/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/00DE3D7E4C>) |
| 8086:a0ef | 1ec9:3e44 | Intel            | Tiger Lake-LP Shared SRAM            | 11    |            | [2D0F2950BA](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/DFD066B5B806/FEDORA-41/6.11.7-300.FC41.X86_64/X86_64/2D0F2950BA>) |
| 8086:9d21 | 8086:9d21 | Intel            | Sunrise Point-LP PMC                 | 10    |            | [E19CC56E22](<Tablet/Google/Nocturne/Nocturne/8D21A3664295/FEDORA-40/5.10.165+/X86_64/E19CC56E22>) |
| 8086:a0ef | 17aa:3829 | Intel            | Tiger Lake-LP Shared SRAM            | 10    |            | [AF8A5DF7BE](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/4236AA030B1D/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/AF8A5DF7BE>) |
| 8086:51ef | 17aa:3828 | Intel            | Alder Lake PCH Shared SRAM           | 9     |            | [F2B2FFBFFE](<Tablet/Lenovo/XiaoXinDuet/XiaoXinDuet IAU7 82TQ/5FF690C6ECBE/KYLIN-V10/6.8.0-45-GENERIC/X86_64/F2B2FFBFFE>) |
| 8086:7e7f | 1043:1c43 | Intel            | RAM memory                           | 9     |            | [DE52972775](<Tablet/ASUSTek Computer/ASUS/ASUS Zenbook Duo UX8406MA_UX8406MA/8A069640761E/ZORIN-17/6.8.0-50-GENERIC/X86_64/DE52972775>) |
| 8086:9def | 103c:85b9 | Intel            | Cannon Point-LP Shared SRAM          | 9     |            | [C43E6E357D](<Tablet/Hewlett-Packard/Elite/Elite x2 G4/28B313198BDD/OPENSUSE-LEAP-15.6/6.4.0-150600.23.25-DEFAULT/X86_64/C43E6E357D>) |
| 8086:4def |           | Intel            | Jasper Lake Shared SRAM              | 8     |            | [E83E0E4EFA](<Tablet/RuggedPC/RuggedBookJ/RuggedBookJ61/3077AC07A524/FEDORA-40/6.11.3-200.FC40.X86_64/X86_64/E83E0E4EFA>) |
| 8086:9d21 | 1025:111e | Intel            | Sunrise Point-LP PMC                 | 8     |            | [E68A5B419E](<Tablet/Acer/Switch/Switch SA5-271/8143477D8A59/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/E68A5B419E>) |
| 8086:9d21 | 1028:06d6 | Intel            | Sunrise Point-LP PMC                 | 8     |            | [0FD89EC85A](<Tablet/Dell/Latitude/Latitude 7275/55EB4B609DF6/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/0FD89EC85A>) |
| 8086:9d21 | 144d:c135 | Intel            | Sunrise Point-LP PMC                 | 8     |            | [F27DFBBBFB](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/FEDORA-40/6.11.3-200.FC40.X86_64/X86_64/F27DFBBBFB>) |
| 8086:02ef | 1028:09ba | Intel            | Comet Lake PCH-LP Shared SRAM        | 7     |            | [657C7CAF3D](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/B6F2D71B615A/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/657C7CAF3D>) |
| 8086:4def | 8086:7270 | Intel            | Jasper Lake Shared SRAM              | 7     |            | [7780E6CD50](<Tablet/DERE/Others/Others/D328C1D92331/KUBUNTU-23.04/6.2.0-39-GENERIC/X86_64/7780E6CD50>) |
| 8086:9d21 | 17aa:3829 | Intel            | Sunrise Point-LP PMC                 | 7     |            | [F5A5189E2A](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/1940EF4E595D/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.11.8-1-DEFAULT/X86_64/F5A5189E2A>) |
| 8086:02ef | 17aa:380d | Intel            | Comet Lake PCH-LP Shared SRAM        | 6     |            | [BE1F1A236B](<Tablet/Lenovo/Yoga/Yoga Duet IML 2020 82E9/B664B47B9CE3/FEDORA-40/6.8.8-300.FC40.X86_64/X86_64/BE1F1A236B>) |
| 8086:4def | 103c:8966 | Intel            | Jasper Lake Shared SRAM              | 6     |            | [5A15B249A5](<Tablet/Hewlett-Packard/Tablet/Tablet 11m-be0xxx/442C1D1B1DB4/FEDORA-41/6.11.0-63.FC41.X86_64/X86_64/5A15B249A5>) |
| 8086:51ef | 1043:1573 | Intel            | Alder Lake PCH Shared SRAM           | 6     |            | [E35C79DDE2](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301VU_GZ301VU/2F999BBF1AC8/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/E35C79DDE2>) |
| 8086:54ef | 8086:7270 | Intel            | Alder Lake-N PCH Shared SRAM         | 6     |            | [B6FE8E3FC9](<Tablet/Star Labs/StarLite/StarLite/7A06CE2A951A/ZORIN-17/6.8.0-49-GENERIC/X86_64/B6FE8E3FC9>) |
| 8086:54ef |           | Intel            | Alder Lake-N PCH Shared SRAM         | 5     |            | [2AF3E8F0C5](<Tablet/Chuwi/Hi10/Hi10 Max/73DD33C3A827/ALT-11.0/6.12.6-6.12-ALT1/X86_64/2AF3E8F0C5>) |
| 8086:9d21 | 19e5:3e00 | Intel            | Sunrise Point-LP PMC                 | 5     |            | [B1081AA326](<Tablet/HUAWEI/MateBook/MateBook HZ-W09/6BBFC8BC312B/ZORIN-17/6.5.0-35-GENERIC/X86_64/B1081AA326>) |
| 8086:51ef | 1028:0b34 | Intel            | Alder Lake PCH Shared SRAM           | 4     |            | [91717BA12B](<Tablet/Dell/XPS/XPS 13 9315 2-in-1/1EF842C3A2C1/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/91717BA12B>) |
| 8086:9d21 | 1028:07a5 | Intel            | Sunrise Point-LP PMC                 | 4     |            | [3C7AF58DAF](<Tablet/Dell/Latitude/Latitude 7285/35CB641DDB78/REBORNOS/6.6.8-ARCH1-1/X86_64/3C7AF58DAF>) |
| 8086:9d21 | 1043:13c0 | Intel            | Sunrise Point-LP PMC                 | 4     |            | [503D57F0A5](<Tablet/ASUSTek Computer/T303/T303UA/946329037C37/UBUNTU-22.04/6.5.0-18-GENERIC/X86_64/503D57F0A5>) |
| 8086:9d21 | 1043:1410 | Intel            | Sunrise Point-LP PMC                 | 4     |            | [6A0B2C7D45](<Tablet/ASUSTek Computer/T305/T305CA/B85AFA7C6015/FEDORA-39/6.7.4-200.FC39.X86_64/X86_64/6A0B2C7D45>) |
| 8086:9d21 | 1043:16c0 | Intel            | Sunrise Point-LP PMC                 | 4     |            | [6563B69541](<Tablet/ASUSTek Computer/T304/T304UA/6F8CE3816A91/KDE-NEON-24.04/6.8.0-50-GENERIC/X86_64/6563B69541>) |
| 8086:9d21 | 17aa:3834 | Intel            | Sunrise Point-LP PMC                 | 4     |            | [40771F27EC](<Tablet/Lenovo/MIIX/MIIX 720-12IKB 80VV/890D2C33C909/ROCKY-9.4/5.14.0-427.13.1.EL9_4.X86_64/X86_64/40771F27EC>) |
| 8086:9def | 1028:08e9 | Intel            | Cannon Point-LP Shared SRAM          | 4     |            | [8D53A4B7AB](<Tablet/Dell/Latitude/Latitude 7200 2-in-1/733991F40E18/MANJARO/6.9.0-1-MANJARO/X86_64/8D53A4B7AB>) |
| 8086:a0ef |           | Intel            | Tiger Lake-LP Shared SRAM            | 4     |            | [0BDD83D289](<Tablet/SHIFT/SHIFT13/SHIFT13mi/0FEB33EB190A/FEDORA-40/6.10.12-200.FC40.X86_64/X86_64/0BDD83D289>) |
| 8086:54ef | 17aa:382d | Intel            | Alder Lake-N PCH Shared SRAM         | 3     |            | [EFDBD13C32](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 11IAN8 82XK/EAC815E6BF54/UBUNTU-24.04/6.8.0-1005-OEM/X86_64/EFDBD13C32>) |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1919 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 432   | ipu3_imgu  | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:9d32 | 8086:7270 | Intel            | CSI-2 Host Controller                | 424   | ipu3_cio2  | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:22b8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 199   | intel_a... | [496C93250D](<Tablet/Chuwi/Hi10/Hi10 pro tablet/D5A4927F3C98/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/496C93250D>) |
| 8086:9d32 |           | Intel            | CSI-2 Host Controller                | 89    | ipu3_cio2  | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 8086:8a19 | 8086:7270 | Intel            | Image Signal Processor               | 87    |            | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:22b8 | 17aa:38e3 | Intel            | Atom/Celeron/Pentium Processor x5... | 80    | intel_a... | [53BAB82FAE](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/384948008566/ALPINE-3.20.3/6.6.63-0-LTS/X86_64/53BAB82FAE>) |
| 8086:22b8 | 17aa:3809 | Intel            | Atom/Celeron/Pentium Processor x5... | 65    | intel_a... | [C377803591](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/FE4476C805C4/KDE-NEON-24.04/6.8.0-47-GENERIC/X86_64/C377803591>) |
| 1022:15e2 | 1022:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 55    | snd_pci... | [2183EB76B7](<Tablet/ONE-NETBOOK/ONEXPLAYER/ONEXPLAYER Mini Pro/F55453A23AA1/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/2183EB76B7>) |
| 8086:1919 | 152d:1182 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 54    | ipu3_imgu  | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 8086:22b8 | 1043:13a0 | Intel            | Atom/Celeron/Pentium Processor x5... | 42    | intel_a... | [2AA1D5261D](<Tablet/ASUSTek Computer/T101/T101HA/302BE3A15A2C/LMDE-6/6.1.0-23-AMD64/X86_64/2AA1D5261D>) |
| 8086:5a88 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 40    |            | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:1919 | 103c:82ca | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 36    | ipu3_imgu  | [F0D42DF827](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/0C327DDF3EC7/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/F0D42DF827>) |
| 8086:9d32 | 103c:82ca | Intel            | CSI-2 Host Controller                | 36    | ipu3_cio2  | [F0D42DF827](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/0C327DDF3EC7/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/F0D42DF827>) |
| 8086:22b8 | 1414:0009 | Intel            | Atom/Celeron/Pentium Processor x5... | 33    | intel_a... | [3C5D9B1B2B](<Tablet/Microsoft/Surface/Surface 3/59BC6F4C45B8/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/3C5D9B1B2B>) |
| 1022:15e2 | 1043:17f3 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 29    | snd_pci_ps | [FD3DE9EA5C](<Tablet/ASUSTek Computer/ROG/ROG Ally RC71L_RC71L/16B794CF2193/BAZZITE-41/6.11.10-304.BAZZITE.FC41.X86_64/X86_64/FD3DE9EA5C>) |
| 8086:22b8 | 103c:827c | Intel            | Atom/Celeron/Pentium Processor x5... | 29    | intel_a... | [878A94CA7F](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/3D11A237BEFA/ZORIN-17/6.8.0-49-GENERIC/X86_64/878A94CA7F>) |
| 8086:1919 | 1028:081d | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 27    | ipu3_imgu  | [20E6DC4833](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/069C27C420D3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.12.6-1-DEFAULT/X86_64/20E6DC4833>) |
| 8086:9d32 | 1028:081d | Intel            | CSI-2 Host Controller                | 27    | ipu3_cio2  | [20E6DC4833](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/069C27C420D3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.12.6-1-DEFAULT/X86_64/20E6DC4833>) |
| 8086:1919 | 103c:828b | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 26    | ipu3_imgu  | [567E4C6343](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/53B866CA15BB/ZORIN-17/6.8.0-45-GENERIC/X86_64/567E4C6343>) |
| 8086:22b8 | 1043:1400 | Intel            | Atom/Celeron/Pentium Processor x5... | 26    | intel_a... | [073DCFBEFD](<Tablet/ASUSTek Computer/T102/T102HA/B8F0B026C483/ZORIN-17/6.5.0-25-GENERIC/X86_64/073DCFBEFD>) |
| 8086:9a19 | 8086:7270 | Intel            | Core i9/i7/i5/Xeon Imaging Signal... | 26    | intel_ipu6 | [DA3534B096](<Tablet/Microsoft/Surface/Surface Pro 7+/87B1E5086B44/DEBIAN-12/6.1.0-28-AMD64/X86_64/DA3534B096>) |
| 8086:9d32 | 103c:828b | Intel            | CSI-2 Host Controller                | 26    | ipu3_cio2  | [567E4C6343](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/53B866CA15BB/ZORIN-17/6.8.0-45-GENERIC/X86_64/567E4C6343>) |
| 1022:15e2 | 17aa:3812 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 25    | snd_pci_ps | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 8086:1919 | 17aa:2244 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 25    | ipu3_imgu  | [454126AC6E](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KKS0S901/980E2F97C968/ARCH-ROLLING/6.12.6-ZEN1-1-ZEN/X86_64/454126AC6E>) |
| 8086:9d32 | 17aa:2244 | Intel            | CSI-2 Host Controller                | 25    | ipu3_cio2  | [454126AC6E](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KKS0S901/980E2F97C968/ARCH-ROLLING/6.12.6-ZEN1-1-ZEN/X86_64/454126AC6E>) |
| 8086:1919 | 152d:1237 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 24    | ipu3_imgu  | [51D7C66A4E](<Tablet/Microsoft/Surface/Surface Go 2/CC8450395E18/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/51D7C66A4E>) |
| 8086:1919 | 17aa:382f | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 21    | ipu3_imgu  | [C14BE2A0FF](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/A8FA91459A71/ZORIN-17/6.8.0-40-GENERIC/X86_64/C14BE2A0FF>) |
| 8086:9d32 | 17aa:380c | Intel            | CSI-2 Host Controller                | 21    | ipu3_cio2  | [C14BE2A0FF](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/A8FA91459A71/ZORIN-17/6.8.0-40-GENERIC/X86_64/C14BE2A0FF>) |
| 1022:15e2 | 1f4c:e001 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 18    | snd_pci_ps | [0BC6665145](<Tablet/Micro Computer (HK) Tech Limited/V/V3/F17AC0C7E80F/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/0BC6665145>) |
| 8086:1919 | 17aa:2243 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 17    | ipu3_imgu  | [BA288E243C](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCS06N0D/45C0E5B583E8/NIXOS-24.05/6.6.66/X86_64/BA288E243C>) |
| 8086:1919 | 8086:1919 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 17    | ipu3_imgu  | [F5A5189E2A](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/1940EF4E595D/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.11.8-1-DEFAULT/X86_64/F5A5189E2A>) |
| 8086:22b8 | 103c:82f4 | Intel            | Atom/Celeron/Pentium Processor x5... | 17    | intel_a... | [042A3DA123](<Tablet/Hewlett-Packard/x2/x2 210 G2/EFBCD466DE81/KDE-NEON-22.04/6.8.0-49-GENERIC/X86_64/042A3DA123>) |
| 8086:9d32 | 17aa:2243 | Intel            | CSI-2 Host Controller                | 17    | ipu3_cio2  | [BA288E243C](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCS06N0D/45C0E5B583E8/NIXOS-24.05/6.6.66/X86_64/BA288E243C>) |
| 8086:1919 | 1028:07a4 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 13    | ipu3_imgu  | [9BDEF7697E](<Tablet/Dell/Latitude/Latitude 5285/03AE783826C3/ZORIN-17/6.8.0-45-GENERIC/X86_64/9BDEF7697E>) |
| 8086:9a19 | 1028:0a45 | Intel            | Core i9/i7/i5/Xeon Imaging Signal... | 13    | intel_i... | [88D7EDA3A3](<Tablet/Dell/Latitude/Latitude 7320 Detachable/2FA880CABA50/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/88D7EDA3A3>) |
| 8086:9d32 | 1028:07a4 | Intel            | CSI-2 Host Controller                | 13    | ipu3_cio2  | [9BDEF7697E](<Tablet/Dell/Latitude/Latitude 5285/03AE783826C3/ZORIN-17/6.8.0-45-GENERIC/X86_64/9BDEF7697E>) |
| 8086:22b8 | 1043:1c60 | Intel            | Atom/Celeron/Pentium Processor x5... | 12    | intel_a... | [284559C037](<Tablet/ASUSTek Computer/T103/T103HAF/265AB1CA9D09/FEDORA-42/6.12.0-0.RC7.59.FC42.X86_64/X86_64/284559C037>) |
| 8086:9a19 | 17aa:508b | Intel            | Core i9/i7/i5/Xeon Imaging Signal... | 12    | intel_ipu6 | [57D1EC52E3](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UW0013US/9FE17438E905/DEBIAN-12/6.1.0-27-AMD64/X86_64/57D1EC52E3>) |
| 8086:1919 | 1028:06e6 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 11    | ipu3_imgu  | [31A3C7AF1E](<Tablet/Dell/Latitude/Latitude 5175/CD1C9C82C174/FEDORA-41/6.11.11-300.FC41.X86_64/X86_64/31A3C7AF1E>) |
| 8086:1919 | 103c:8414 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 11    | ipu3_imgu  | [A1F8F4C528](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/92E2795CC5F7/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/A1F8F4C528>) |
| 8086:1919 | 10f7:8338 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 11    | ipu3_imgu  | [FAF64BB8A0](<Tablet/Panasonic/CF-33/CF-33-1/71D2DD20CB26/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/FAF64BB8A0>) |
| 8086:1919 | 144d:c14f | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 11    | ipu3_imgu  | [EBD4E47906](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/EBD4E47906>) |
| 8086:1919 | 17aa:2241 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 11    | ipu3_imgu  | [047961B6D0](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/7D7EF3298D39/FEDORA-41/6.12.5-200.FC41.X86_64/X86_64/047961B6D0>) |
| 8086:1919 | 17aa:382c | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 11    | ipu3_imgu  | [00DE3D7E4C](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/248F2E7667A2/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/00DE3D7E4C>) |
| 8086:9a19 | 1ec9:3e44 | Intel            | Core i9/i7/i5/Xeon Imaging Signal... | 11    | intel_i... | [2D0F2950BA](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/DFD066B5B806/FEDORA-41/6.11.7-300.FC41.X86_64/X86_64/2D0F2950BA>) |
| 8086:9d32 | 1028:06e6 | Intel            | CSI-2 Host Controller                | 11    | ipu3_cio2  | [31A3C7AF1E](<Tablet/Dell/Latitude/Latitude 5175/CD1C9C82C174/FEDORA-41/6.11.11-300.FC41.X86_64/X86_64/31A3C7AF1E>) |
| 8086:9d32 | 103c:8414 | Intel            | CSI-2 Host Controller                | 11    | ipu3_cio2  | [A1F8F4C528](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/92E2795CC5F7/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/A1F8F4C528>) |
| 8086:9d32 | 10f7:8338 | Intel            | CSI-2 Host Controller                | 11    | ipu3_cio2  | [FAF64BB8A0](<Tablet/Panasonic/CF-33/CF-33-1/71D2DD20CB26/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/FAF64BB8A0>) |
| 8086:9d32 | 144d:c14f | Intel            | CSI-2 Host Controller                | 11    | ipu3_cio2  | [EBD4E47906](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/EBD4E47906>) |
| 8086:9d32 | 17aa:2241 | Intel            | CSI-2 Host Controller                | 11    | ipu3_cio2  | [047961B6D0](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/7D7EF3298D39/FEDORA-41/6.12.5-200.FC41.X86_64/X86_64/047961B6D0>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:8136 | 1019:99fa | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 12    | r8169      | [DA6CE4B361](<Tablet/BANGHO/Suma/Suma 1025/DF80AD331B24/ZORIN-17/6.8.0-49-GENERIC/X86_64/DA6CE4B361>) |
| 8086:15d7 | 10f7:8338 | Intel            | Ethernet Connection (4) I219-LM      | 8     | e1000e     | [FAF64BB8A0](<Tablet/Panasonic/CF-33/CF-33-1/71D2DD20CB26/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/FAF64BB8A0>) |
| 10ec:8168 | 1019:99fa | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 7     | r8169      | [0545CC60DE](<Tablet/Intel/powered/powered classmate PC/F373FE00C042/ARCHCRAFT/6.10.8-ARCH1-1/X86_64/0545CC60DE>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 6     | r8169      | [F456628E1B](<Tablet/Others/Others/Others/1E0FA7F9B01D/UBUNTU-20.04/5.4.0-182-GENERIC/X86_64/F456628E1B>) |
| 10ec:8136 | 1019:99da | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 5     | r8169      | [628E83BE54](<Tablet/BANGHO/Suma/Suma 1025/FEDBC36EBBC3/ZORIN-17/6.5.0-41-GENERIC/X86_64/628E83BE54>) |
| 8086:15f3 | 8086:0000 | Intel            | Ethernet Controller I225-V           | 4     | igc        | [5F97496A76](<Tablet/retsamarret/000/000-F4423-FBA004-2000-N/371AE0288EED/NIXOS-23.11/6.1.58/X86_64/5F97496A76>) |
| 10ec:8136 | 10ec:0123 | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 2     | r8169      | [343B7EE8FA](<Tablet/BANGHO/Suma/Suma 1025/24B635A1544E/ZORIN-17/6.5.0-28-GENERIC/X86_64/343B7EE8FA>) |
| 10ec:8136 | 1854:0211 | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 2     | r8169      | [44AF16AC16](<Tablet/LG Electronics/15U340/15U340-L.BK55P1/96572D02BF5F/LINUXMINT-20/5.4.0-42-GENERIC/X86_64/44AF16AC16>) |
| 10ec:8168 | 1509:7018 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 2     | r8169      | [9347717861](<Tablet/Xplore/iX101/iX101B1/988A604FB8AB/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/9347717861>) |
| 8086:156f | 1b0a:01d3 | Intel            | Ethernet Connection I219-LM          | 2     | e1000e     | [60C93DDC01](<Tablet/Xplore/iX125/iX125R1/9DCB305AD004/PUPPY_IMPPUP64-9.6.1/5.15.11-LXPUP64/X86_64/60C93DDC01>) |
| 10ec:8136 | 10ec:8136 | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 1     | r8169      | [FD3953ACEE](<Tablet/BANGHO/Suma/Suma 1025/3C94E9E25E13/KALI-2022.4/6.0.0-KALI3-AMD64/X86_64/FD3953ACEE>) |
| 10ec:8136 | 1558:5470 | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 1     | r8169      | [DD65C5ABF7](<Tablet/Lanix/Neuron/Neuron A/9C81E684C8A4/ARCH-ROLLING/5.8.14-ARCH1-1/X86_64/DD65C5ABF7>) |
| 10ec:8168 | 1071:a126 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 1     | r8169      | [FE815F3C1F](<Tablet/Getac/T800/T800G2/9876536A7026/DEBIAN-12/6.1.0-10-AMD64/X86_64/FE815F3C1F>) |
| 8086:0d4e | 10f7:8338 | Intel            | Ethernet Connection (10) I219-LM     | 1     | e1000e     | [2295DE0CC3](<Tablet/Panasonic/CF-33/CF-33-2/F3304BC32864/OPENSUSE-LEAP-15.4/5.14.21-150400.24.97-DEFAULT/X86_64/2295DE0CC3>) |
| 8086:0dc5 | 1071:a125 | Intel            | Ethernet Connection (23) I219-LM     | 1     | e1000e     | [CBCDE33E6C](<Tablet/Getac/K120/K120G3/834E85EFA531/OPENSUSE-LEAP-15.6/6.4.0-150600.23.7-DEFAULT/X86_64/CBCDE33E6C>) |
| 8086:156f | 10f7:8338 | Intel            | Ethernet Connection I219-LM          | 1     | e1000e     | [272B446271](<Tablet/Panasonic/CF-33/CF-33S-1/3A0062175D5E/ARCH-ROLLING/6.7.9-ARCH1-1/X86_64/272B446271>) |
| 8086:15a2 | 10cf:17e9 | Intel            | Ethernet Connection (3) I218-LM      | 1     | e1000e     | [9BC073F366](<Tablet/Fujitsu/STYLISTIC/STYLISTIC Q665/0A32CF1AA569/ZORIN-16/5.15.0-97-GENERIC/X86_64/9BC073F366>) |
| 8086:15d7 | 10cf:192c | Intel            | Ethernet Connection (4) I219-LM      | 1     | e1000e     | [CF0A931BC4](<Tablet/Fujitsu/FARQ/FARQ16011/0AA1C154091E/ZORIN-17/6.8.0-50-GENERIC/X86_64/CF0A931BC4>) |
| 8086:15fb | 1071:a121 | Intel            | Ethernet Connection (13) I219-LM     | 1     |            | [5D9E3F3501](<Tablet/Getac/K120/K120G2/9B90212BD0E9/UBUNTU-18.04/5.4.0-84-GENERIC/X86_64/5D9E3F3501>) |
| 8086:15fb | 1071:e207 | Intel            | Ethernet Connection (13) I219-LM     | 1     | e1000e     | [2A05772CB6](<Tablet/Getac/F110/F110G6/36F31BBCD939/RELD-7.9/5.15.33-1.RES7.X86_64/X86_64/2A05772CB6>) |
| 8086:15fb | 8086:0000 | Intel            | Ethernet Connection (13) I219-LM     | 1     | e1000e     | [0AD09DEE4F](<Tablet/Zebra Technologies/ET85/ET85B/B5661B10FE6A/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/0AD09DEE4F>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:34f0 | 8086:0074 | Intel            | Ice Lake-LP PCH CNVi WiFi            | 152   | iwlwifi    | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:3165 | 8086:8010 | Intel            | Wireless 3165                        | 144   | iwlwifi    | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 11ab:2b38 | 0003:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 139   | mwifiex... | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 11ab:2b38 | 0008:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 128   | mwifiex... | [C9024275E0](<Tablet/Microsoft/Surface/Surface Pro/F31CC379A03C/UBUNTU-24.04/6.10.10-SURFACE-1/X86_64/C9024275E0>) |
| 11ab:2b38 | 0001:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 118   | mwifiex... | [BB626D70B0](<Tablet/Microsoft/Surface/Surface Pro 3/217C1E4144F1/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/BB626D70B0>) |
| 168c:0042 | 1a3b:2a51 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 81    | ath10k_pci | [284559C037](<Tablet/ASUSTek Computer/T103/T103HAF/265AB1CA9D09/FEDORA-42/6.12.0-0.RC7.59.FC42.X86_64/X86_64/284559C037>) |
| 8086:095a | 8086:9010 | Intel            | Wireless 7265                        | 68    | iwlwifi    | [A8C473704C](<Tablet/Fujitsu/FARQ/FARQ17004/CE7CF5AB9A17/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/A8C473704C>) |
| 8086:a0f0 | 8086:0074 | Intel            | Wi-Fi 6 AX201                        | 68    | iwlwifi    | [0B901FDA6F](<Tablet/Microsoft/Surface/Surface Pro 8/2ECF330FF091/FEDORA-40/6.8.5-301.FC40.X86_64/X86_64/0B901FDA6F>) |
| 8086:2723 | 8086:008c | Intel            | Wi-Fi 6 AX200                        | 56    | iwlwifi    | [FD805CEEB5](<Tablet/Microsoft/Surface/Surface Go 3/2F23800DE848/UBUNTU-24.10/6.12.3-SURFACE-2/X86_64/FD805CEEB5>) |
| 168c:003e | 168c:3370 | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 50    | ath10k_pci | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 11ab:2b38 | 0004:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 48    | mwifiex... | [E334442819](<Tablet/Microsoft/Surface/Surface Book/D7F4D70DD18A/POP!_OS-22.04/6.12.3-SURFACE-2/X86_64/E334442819>) |
| 8086:2725 | 8086:0024 | Intel            | Wi-Fi 6E(802.11ax) AX210/AX1675* ... | 43    | iwlwifi    | [2183EB76B7](<Tablet/ONE-NETBOOK/ONEXPLAYER/ONEXPLAYER Mini Pro/F55453A23AA1/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/2183EB76B7>) |
| 8086:51f0 | 8086:0094 | Intel            | Alder Lake-P PCH CNVi WiFi           | 42    | iwlwifi    | [E6F037A5E8](<Tablet/Microsoft/Surface/Surface Pro 9/9EE1E883AC5A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E6F037A5E8>) |
| 11ab:2b38 | 0006:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 41    | mwifiex... | [FB45B5BA78](<Tablet/Microsoft/Surface/Surface Laptop/F3F7BF2B5D64/LINUXMINT-22/6.10.10-SURFACE-1/X86_64/FB45B5BA78>) |
| 8086:24fd | 8086:0150 | Intel            | Wireless 8265 / 8275                 | 40    | iwlwifi    | [20E6DC4833](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/069C27C420D3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.12.6-1-DEFAULT/X86_64/20E6DC4833>) |
| 10ec:c821 | 10ec:c821 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 33    | rtw88_8... | [56CA392159](<Tablet/SK hynix/10WWA464/10WWA464B/A08A683656BD/ELEMENTARY-8/6.8.0-49-GENERIC/X86_64/56CA392159>) |
| 8086:24fd | 8086:9010 | Intel            | Wireless 8265 / 8275                 | 33    | iwlwifi    | [A1F8F4C528](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/92E2795CC5F7/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/A1F8F4C528>) |
| 11ab:2b38 | 0002:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 32    | mwifiex... | [3C5D9B1B2B](<Tablet/Microsoft/Surface/Surface 3/59BC6F4C45B8/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/3C5D9B1B2B>) |
| 14c3:0616 | 105b:e0de | MediaTek         | MT7922 802.11ax PCI Express Wirel... | 32    | mt7921e    | [FD3DE9EA5C](<Tablet/ASUSTek Computer/ROG/ROG Ally RC71L_RC71L/16B794CF2193/BAZZITE-41/6.11.10-304.BAZZITE.FC41.X86_64/X86_64/FD3DE9EA5C>) |
| 11ab:2b38 | 0009:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 31    | mwifiex... | [EAF1BB652C](<Tablet/Microsoft/Surface/Surface Book 2/B870A7627396/ARCH-ROLLING/6.12.7-ARCH1-1-NSB2/X86_64/EAF1BB652C>) |
| 8086:24fd | 8086:1010 | Intel            | Wireless 8265 / 8275                 | 31    | iwlwifi    | [75E354C291](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/E70BC33C4084/FEDORA-41/6.11.5-300.FC41.X86_64/X86_64/75E354C291>) |
| 10ec:b723 | 10ec:b737 | Realtek Semic... | RTL8723BE PCIe Wireless Network A... | 26    | rtl8723be  | [DA6CE4B361](<Tablet/BANGHO/Suma/Suma 1025/DF80AD331B24/ZORIN-17/6.8.0-49-GENERIC/X86_64/DA6CE4B361>) |
| 8086:31dc | 8086:0264 | Intel            | Gemini Lake PCH CNVi WiFi            | 26    | iwlwifi    | [026269E60B](<Tablet/Others/Others/Others/B4F90A2AAF5D/LINUXMINT-22/6.8.0-50-GENERIC/X86_64/026269E60B>) |
| 14c3:0616 | 17aa:e0c7 | MediaTek         | MT7922 802.11ax PCI Express Wirel... | 25    | mt7921e    | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 8086:24fd | 8086:8110 | Intel            | Wireless 8265 / 8275                 | 24    | iwlwifi    | [BA288E243C](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCS06N0D/45C0E5B583E8/NIXOS-24.05/6.6.66/X86_64/BA288E243C>) |
| 8086:24fd | 8086:8010 | Intel            | Wireless 8265 / 8275                 | 22    | iwlwifi    | [0ADCE1D7C2](<Tablet/Panasonic/CFXZ6/CFXZ6-1/1D35807ACBEA/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/0ADCE1D7C2>) |
| 14c3:0608 | 14c3:0608 | MediaTek         | MT7921K (RZ608) Wi-Fi 6E 80MHz       | 19    | mt7921e    | [811AF91E75](<Tablet/AYANEO/2/2/959EFBE7A1CC/STEAMOS-20241225.0928/6.12.6-2/X86_64/811AF91E75>) |
| 8086:24f3 | 8086:8110 | Intel            | Wireless 8260                        | 19    | iwlwifi    | [047961B6D0](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/7D7EF3298D39/FEDORA-41/6.12.5-200.FC41.X86_64/X86_64/047961B6D0>) |
| 8086:24fd | 8086:0010 | Intel            | Wireless 8265 / 8275                 | 19    | iwlwifi    | [F0D42DF827](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/0C327DDF3EC7/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/F0D42DF827>) |
| 8086:24f3 | 8086:0150 | Intel            | Wireless 8260                        | 18    | iwlwifi    | [0FD89EC85A](<Tablet/Dell/Latitude/Latitude 7275/55EB4B609DF6/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/0FD89EC85A>) |
| 8086:24fd | 8086:9110 | Intel            | Wireless 8265 / 8275                 | 18    | iwlwifi    | [55D05F5E93](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JBCTO1WW/F7EE02EECD69/UBUNTU-24.10/6.11.0-13-GENERIC/X86_64/55D05F5E93>) |
| 8086:3165 | 8086:8110 | Intel            | Wireless 3165                        | 18    | iwlwifi    | [2E2C1099E7](<Tablet/Fusion5/FWIN232/FWIN232 PRO N4/EE6C76DEF50B/UBUNTU-16.04/4.15.0-112-GENERIC/X86_64/2E2C1099E7>) |
| 11ab:2b38 | 0007:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 16    | mwifiex... | [E9EC9E62A2](<Tablet/Microsoft/Surface/Surface Book 2/2B7E0582A8AD/ENDEAVOUROS-ROLLING/6.11.4-ARCH1-1-SURFACE/X86_64/E9EC9E62A2>) |
| 168c:002b | 105b:e031 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 16    | ath9k      | [AC15CCA834](<Tablet/Acer/Iconia/Iconia Tab W500/00630A96A0A7/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/AC15CCA834>) |
| 8086:a0f0 | 8086:0070 | Intel            | Wi-Fi 6 AX201                        | 15    | iwlwifi    | [57D1EC52E3](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UW0013US/9FE17438E905/DEBIAN-12/6.1.0-27-AMD64/X86_64/57D1EC52E3>) |
| 11ab:2b38 | 000a:045e | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 14    | mwifiex... | [E30F026FAC](<Tablet/Microsoft/Surface/Surface Pro/5D1B150D0A95/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/E30F026FAC>) |
| 168c:003e | 17aa:0827 | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 13    | ath10k_pci | [C14BE2A0FF](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/A8FA91459A71/ZORIN-17/6.8.0-40-GENERIC/X86_64/C14BE2A0FF>) |
| 8086:31dc | 8086:0234 | Intel            | Gemini Lake PCH CNVi WiFi            | 13    | iwlwifi    | [5DAD085952](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 10IGL5 82AT/F87C264A0B49/FEDORA-40/6.11.4-201.FC40.X86_64/X86_64/5DAD085952>) |
| 8086:a0f0 | 8086:4070 | Intel            | Wi-Fi 6 AX201                        | 13    | iwlwifi    | [88D7EDA3A3](<Tablet/Dell/Latitude/Latitude 7320 Detachable/2FA880CABA50/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/88D7EDA3A3>) |
| 168c:003e | 144d:c14f | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 11    | ath10k_pci | [EBD4E47906](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/EBD4E47906>) |
| 168c:0042 | 1a3b:2b51 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 11    | ath10k_pci | [D3AC0F6A92](<Tablet/AVITA/NS12/NS12T5/2D1154BB2648/ZORIN-17/6.8.0-47-GENERIC/X86_64/D3AC0F6A92>) |
| 8086:2723 | 8086:0080 | Intel            | Wi-Fi 6 AX200                        | 11    | iwlwifi    | [79C895B3A3](<Tablet/Microsoft/Surface/Surface Laptop Studio/7EAF7CBE4A58/FEDORA-40/6.10.10-1.SURFACE.FC40.X86_64/X86_64/79C895B3A3>) |
| 14e4:43ec | 105b:e095 | Broadcom         | BCM4356 802.11ac Wireless Network... | 10    | brcmfmac   | [8E0B9DF2EE](<Tablet/Lenovo/ThinkPad/ThinkPad 10 2nd 20E4S0SQ00/7A1E61DB3A8D/UBUNTU-24.04/6.8.0-40-GENERIC/X86_64/8E0B9DF2EE>) |
| 168c:003e | 045e:0001 | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 9     | ath10k_pci | [9151EDDCF9](<Tablet/Microsoft/Surface/Surface Laptop 3/E807460CD8AC/KDE-NEON-22.04/6.5.0-45-GENERIC/X86_64/9151EDDCF9>) |
| 8086:7e40 | 8086:0094 | Intel            | Meteor Lake PCH CNVi WiFi            | 9     | iwlwifi    | [DE52972775](<Tablet/ASUSTek Computer/ASUS/ASUS Zenbook Duo UX8406MA_UX8406MA/8A069640761E/ZORIN-17/6.8.0-50-GENERIC/X86_64/DE52972775>) |
| 168c:003e | 144d:c135 | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 8     | ath10k_pci | [F27DFBBBFB](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/FEDORA-40/6.11.3-200.FC40.X86_64/X86_64/F27DFBBBFB>) |
| 8086:08b3 | 8086:8070 | Intel            | Wireless 3160                        | 8     | iwlwifi    | [0AC4B868CB](<Tablet/Medion/P/P2212T/1CC59B4B188A/FEDORA-40/6.9.5-200.FC40.X86_64/X86_64/0AC4B868CB>) |
| 8086:4df0 | 8086:0074 | Intel            | Wi-Fi 6 AX201 160MHz                 | 8     | iwlwifi    | [1F850C6012](<Tablet/ASUSTek Computer/Vivobook/Vivobook Slate T3300KA_T3300KA/5E4B2F9BE565/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/1F850C6012>) |
| 8086:51f1 | 8086:0094 | Intel            | Raptor Lake PCH CNVi WiFi            | 8     | iwlwifi    | [E35C79DDE2](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301VU_GZ301VU/2F999BBF1AC8/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/E35C79DDE2>) |
| 8086:24fd | 8086:0110 | Intel            | Wireless 8265 / 8275                 | 7     | iwlwifi    | [FAF64BB8A0](<Tablet/Panasonic/CF-33/CF-33-1/71D2DD20CB26/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/FAF64BB8A0>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1533 | ffff:0000 | Intel            | I210 Gigabit Network Connection      | 3     | igb        | [198C15E90A](<Tablet/System Mfg/Others/Others/AF6F46232DB6/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/198C15E90A>) |
| 8086:1502 | 10f7:8338 | Intel            | 82579LM Gigabit Network Connectio... | 1     | e1000e     | [50E0A85FD3](<Tablet/Panasonic/CF-H2/CF-H2BJJHZDE/E17482358B17/LMDE-5/5.10.0-13-AMD64/X86_64/50E0A85FD3>) |
| 8086:2526 | 8086:e014 | Intel            | Wi-Fi 5(802.11ac) Wireless-AC 9x6... | 1     | iwlwifi    | [9C632DF9A1](<Tablet/Juniper Systems/Mesa/Mesa Pro/6FD4B0D409A4/UBUNTU-MATE-22.04/5.15.0-91-GENERIC/X86_64/9C632DF9A1>) |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:14ec | 1022:14ec | AMD              | Phoenix Dummy Function               | 40    |            | [FD3DE9EA5C](<Tablet/ASUSTek Computer/ROG/ROG Ally RC71L_RC71L/16B794CF2193/BAZZITE-41/6.11.10-304.BAZZITE.FC41.X86_64/X86_64/FD3DE9EA5C>) |
| 1022:14ec | 17aa:3812 | AMD              | Phoenix Dummy Function               | 25    |            | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 1022:14ec | 1f4c:e001 | AMD              | Phoenix Dummy Function               | 18    |            | [0BC6665145](<Tablet/Micro Computer (HK) Tech Limited/V/V3/F17AC0C7E80F/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/0BC6665145>) |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d35 | 8086:7270 | Intel            | Sunrise Point-LP Integrated Senso... | 216   | intel_i... | [EAF1BB652C](<Tablet/Microsoft/Surface/Surface Book 2/B870A7627396/ARCH-ROLLING/6.12.7-ARCH1-1-NSB2/X86_64/EAF1BB652C>) |
| 8086:9d35 | 152d:1182 | Intel            | Sunrise Point-LP Integrated Senso... | 54    | intel_i... | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 8086:22d8 | 1043:13a0 | Intel            | Integrated Sensor Solution           | 42    | intel_i... | [2AA1D5261D](<Tablet/ASUSTek Computer/T101/T101HA/302BE3A15A2C/LMDE-6/6.1.0-23-AMD64/X86_64/2AA1D5261D>) |
| 8086:9d35 | 103c:82ca | Intel            | Sunrise Point-LP Integrated Senso... | 36    | intel_i... | [F0D42DF827](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/0C327DDF3EC7/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/F0D42DF827>) |
| 8086:22d8 | 103c:827c | Intel            | Integrated Sensor Solution           | 30    | intel_i... | [878A94CA7F](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/3D11A237BEFA/ZORIN-17/6.8.0-49-GENERIC/X86_64/878A94CA7F>) |
| 8086:22d8 | 1043:1400 | Intel            | Integrated Sensor Solution           | 27    | intel_i... | [073DCFBEFD](<Tablet/ASUSTek Computer/T102/T102HA/B8F0B026C483/ZORIN-17/6.5.0-25-GENERIC/X86_64/073DCFBEFD>) |
| 8086:9d35 | 1028:081d | Intel            | Sunrise Point-LP Integrated Senso... | 27    | intel_i... | [20E6DC4833](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/069C27C420D3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.12.6-1-DEFAULT/X86_64/20E6DC4833>) |
| 8086:9d35 | 103c:828b | Intel            | Sunrise Point-LP Integrated Senso... | 26    | intel_i... | [567E4C6343](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/53B866CA15BB/ZORIN-17/6.8.0-45-GENERIC/X86_64/567E4C6343>) |
| 8086:9d35 | 17aa:2244 | Intel            | Sunrise Point-LP Integrated Senso... | 25    | intel_i... | [454126AC6E](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KKS0S901/980E2F97C968/ARCH-ROLLING/6.12.6-ZEN1-1-ZEN/X86_64/454126AC6E>) |
| 8086:9d35 | 152d:1237 | Intel            | Sunrise Point-LP Integrated Senso... | 24    | intel_i... | [51D7C66A4E](<Tablet/Microsoft/Surface/Surface Go 2/CC8450395E18/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/51D7C66A4E>) |
| 8086:9d35 | 17aa:3807 | Intel            | Sunrise Point-LP Integrated Senso... | 21    | intel_i... | [C14BE2A0FF](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/A8FA91459A71/ZORIN-17/6.8.0-40-GENERIC/X86_64/C14BE2A0FF>) |
| 8086:22d8 | 103c:82f4 | Intel            | Integrated Sensor Solution           | 17    | intel_i... | [042A3DA123](<Tablet/Hewlett-Packard/x2/x2 210 G2/EFBCD466DE81/KDE-NEON-22.04/6.8.0-49-GENERIC/X86_64/042A3DA123>) |
| 8086:9d35 | 17aa:2243 | Intel            | Sunrise Point-LP Integrated Senso... | 17    | intel_i... | [BA288E243C](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCS06N0D/45C0E5B583E8/NIXOS-24.05/6.6.66/X86_64/BA288E243C>) |
| 8086:22d8 | 8086:7270 | Intel            | Integrated Sensor Solution           | 16    | intel_i... | [8E0B9DF2EE](<Tablet/Lenovo/ThinkPad/ThinkPad 10 2nd 20E4S0SQ00/7A1E61DB3A8D/UBUNTU-24.04/6.8.0-40-GENERIC/X86_64/8E0B9DF2EE>) |
| 8086:9d35 | 1028:07a4 | Intel            | Sunrise Point-LP Integrated Senso... | 13    | intel_i... | [9BDEF7697E](<Tablet/Dell/Latitude/Latitude 5285/03AE783826C3/ZORIN-17/6.8.0-45-GENERIC/X86_64/9BDEF7697E>) |
| 8086:22d8 | 1043:1c60 | Intel            | Integrated Sensor Solution           | 12    | intel_i... | [284559C037](<Tablet/ASUSTek Computer/T103/T103HAF/265AB1CA9D09/FEDORA-42/6.12.0-0.RC7.59.FC42.X86_64/X86_64/284559C037>) |
| 8086:9d35 | 10f7:8338 | Intel            | Sunrise Point-LP Integrated Senso... | 12    | intel_i... | [FAF64BB8A0](<Tablet/Panasonic/CF-33/CF-33-1/71D2DD20CB26/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/FAF64BB8A0>) |
| 8086:9d35 | 1028:06e6 | Intel            | Sunrise Point-LP Integrated Senso... | 11    | intel_i... | [31A3C7AF1E](<Tablet/Dell/Latitude/Latitude 5175/CD1C9C82C174/FEDORA-41/6.11.11-300.FC41.X86_64/X86_64/31A3C7AF1E>) |
| 8086:9d35 | 103c:8414 | Intel            | Sunrise Point-LP Integrated Senso... | 11    | intel_i... | [A1F8F4C528](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/92E2795CC5F7/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/A1F8F4C528>) |
| 8086:9d35 | 17aa:2241 | Intel            | Sunrise Point-LP Integrated Senso... | 11    | intel_i... | [047961B6D0](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/7D7EF3298D39/FEDORA-41/6.12.5-200.FC41.X86_64/X86_64/047961B6D0>) |
| 1022:15e6 | 1022:15e4 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 9     | i2c_amd... | [9151EDDCF9](<Tablet/Microsoft/Surface/Surface Laptop 3/E807460CD8AC/KDE-NEON-22.04/6.5.0-45-GENERIC/X86_64/9151EDDCF9>) |
| 8086:9d35 | 1025:111e | Intel            | Sunrise Point-LP Integrated Senso... | 8     | intel_i... | [E68A5B419E](<Tablet/Acer/Switch/Switch SA5-271/8143477D8A59/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/E68A5B419E>) |
| 8086:9d35 | 1028:06d6 | Intel            | Sunrise Point-LP Integrated Senso... | 8     | intel_i... | [0FD89EC85A](<Tablet/Dell/Latitude/Latitude 7275/55EB4B609DF6/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/0FD89EC85A>) |
| 8086:9d35 | 8086:9d35 | Intel            | Sunrise Point-LP Integrated Senso... | 8     | intel_i... | [6563B69541](<Tablet/ASUSTek Computer/T304/T304UA/6F8CE3816A91/KDE-NEON-24.04/6.8.0-50-GENERIC/X86_64/6563B69541>) |
| 8086:22d8 | 10cf:191b | Intel            | Integrated Sensor Solution           | 5     | intel_i... | [A8C473704C](<Tablet/Fujitsu/FARQ/FARQ17004/CE7CF5AB9A17/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/A8C473704C>) |
| 8086:9d35 | 19e5:3e00 | Intel            | Sunrise Point-LP Integrated Senso... | 5     | intel_i... | [B1081AA326](<Tablet/HUAWEI/MateBook/MateBook HZ-W09/6BBFC8BC312B/ZORIN-17/6.5.0-35-GENERIC/X86_64/B1081AA326>) |
| 8086:9d35 | 1028:07a5 | Intel            | Sunrise Point-LP Integrated Senso... | 4     | intel_i... | [3C7AF58DAF](<Tablet/Dell/Latitude/Latitude 7285/35CB641DDB78/REBORNOS/6.6.8-ARCH1-1/X86_64/3C7AF58DAF>) |
| 8086:9d35 | 1043:13c0 | Intel            | Sunrise Point-LP Integrated Senso... | 4     | intel_i... | [503D57F0A5](<Tablet/ASUSTek Computer/T303/T303UA/946329037C37/UBUNTU-22.04/6.5.0-18-GENERIC/X86_64/503D57F0A5>) |
| 8086:22d8 | 1d72:1502 | Intel            | Integrated Sensor Solution           | 3     | intel_i... | [5F3A7B7A19](<Tablet/Xiaomi/Mipad/Mipad2/86E10DD4C731/FEDORA-40/6.8.5-301.FC40.X86_64/X86_64/5F3A7B7A19>) |
| 8086:9d24 |           | Intel            | Skylake-U/Y SPI Controller           | 3     |            | [E19CC56E22](<Tablet/Google/Nocturne/Nocturne/8D21A3664295/FEDORA-40/5.10.165+/X86_64/E19CC56E22>) |
| 8086:9d35 | 1025:1171 | Intel            | Sunrise Point-LP Integrated Senso... | 3     | intel_i... | [7D44E4C760](<Tablet/Acer/Switch/Switch SW512-52/9061A4CB688E/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/7D44E4C760>) |
| 8086:9d35 | 1028:07d3 | Intel            | Sunrise Point-LP Integrated Senso... | 3     | intel_i... | [72351CCF77](<Tablet/Dell/Latitude/Latitude 7212 Rugged Extreme Tablet/EDF0638A4664/FEDORA-40/6.9.4-201.FSYNC.FC40.X86_64/X86_64/72351CCF77>) |
| 8086:9d35 | 103c:824c | Intel            | Sunrise Point-LP Integrated Senso... | 3     | intel_i... | [6CA12FAB01](<Tablet/Hewlett-Packard/ZBook/ZBook x2 G4/E1BE91E1F9DE/ARCH-ROLLING/6.6.38-1-LTS/X86_64/6CA12FAB01>) |
| 8086:9d35 | 103c:82cb | Intel            | Sunrise Point-LP Integrated Senso... | 3     | intel_i... | [9DE6B65A45](<Tablet/Hewlett-Packard/Spectre/Spectre x2 Detachable 12-c0XX/107C5ABF10E7/ARCH-ROLLING/6.2.2-ARCH1-1/X86_64/9DE6B65A45>) |
| 8086:22d8 | 1071:a126 | Intel            | Integrated Sensor Solution           | 2     | intel_i... | [EDE8155598](<Tablet/Getac/T800/T800G2/A89C411CD27C/UBUNTU-23.10/6.5.0-5-GENERIC/X86_64/EDE8155598>) |
| 8086:9d35 | 1025:122b | Intel            | Sunrise Point-LP Integrated Senso... | 2     | intel_i... | [46ECB88F1D](<Tablet/Acer/Switch/Switch SW713-51GNP/3C0AE30715BA/NIXOS-22.11/6.1.9/X86_64/46ECB88F1D>) |
| 8086:22d8 | 10f7:8338 | Intel            | Integrated Sensor Solution           | 1     | intel_i... | [BEEB215141](<Tablet/Panasonic/FZB2/FZB2-2/BA668A2C2665/ANTIX-23.1/6.1.105-ANTIX.1-AMD64-SMP/X86_64/BEEB215141>) |
| 8086:9d35 | 1028:0702 | Intel            | Sunrise Point-LP Integrated Senso... | 1     | intel_i... | [CE9A3F2C74](<Tablet/Dell/XPS/XPS 12 9250/A04CD2743A76/CLEAR-LINUX-OS-35400/5.15.7-1106.NATIVE/X86_64/CE9A3F2C74>) |
| 8086:9d35 | 10cf:1955 | Intel            | Sunrise Point-LP Integrated Senso... | 1     | intel_i... | [CF0A931BC4](<Tablet/Fujitsu/FARQ/FARQ16011/0AA1C154091E/ZORIN-17/6.8.0-50-GENERIC/X86_64/CF0A931BC4>) |
| 8086:9d35 | 1179:0001 | Intel            | Sunrise Point-LP Integrated Senso... | 1     | intel_i... | [2942C2E2D5](<Tablet/Toshiba/PORTEGE/PORTEGE X30T-E/41C9BB76C341/UBUNTU-23.04/6.2.0-24-GENERIC/X86_64/2942C2E2D5>) |
| 8086:9d35 | 17aa:3805 | Intel            | Sunrise Point-LP Integrated Senso... | 1     | intel_i... | [50D3528425](<Tablet/Lenovo/MIIX710-12IKB/MIIX710-12IKB 80W1/2FB91DC53770/LINUXMINT-20.3/5.15.0-33-GENERIC/X86_64/50D3528425>) |
| 8086:9d35 | 19e5:3e01 | Intel            | Sunrise Point-LP Integrated Senso... | 1     | intel_i... | [072689DF7B](<Tablet/HUAWEI/MateBook/MateBook E/AE4CFFA107F9/KALI-2022.4/6.0.0-KALI6-AMD64/X86_64/072689DF7B>) |

### Processing accelerators (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:7d1d | 1043:20bf | Intel            | Meteor Lake NPU                      | 9     | intel_vpu  | [DE52972775](<Tablet/ASUSTek Computer/ASUS/ASUS Zenbook Duo UX8406MA_UX8406MA/8A069640761E/ZORIN-17/6.8.0-50-GENERIC/X86_64/DE52972775>) |
| 8086:7d1d | 1462:143a | Intel            | Meteor Lake NPU                      | 1     | intel_vpu  | [2EBDE0820D](<Tablet/MSI/Claw/Claw A1M/E9FB50149AEE/STEAMOS-ROLLING/6.11.1-1/X86_64/2EBDE0820D>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:31d0 | 8086:7270 | Intel            | Celeron/Pentium Silver SD Host Co... | 90    | sdhci_pci  | [1827AD6649](<Tablet/Microsoft/Surface/Surface Laptop SE/3C3B6159F009/ZORIN-17/6.8.0-49-GENERIC/X86_64/1827AD6649>) |
| 8086:31cc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 84    | sdhci_pci  | [1827AD6649](<Tablet/Microsoft/Surface/Surface Laptop SE/3C3B6159F009/ZORIN-17/6.8.0-49-GENERIC/X86_64/1827AD6649>) |
| 17a0:9755 | 1043:202f | Genesys Logic    | GL9755 SD Host Controller            | 58    | sdhci_pci  | [FD3DE9EA5C](<Tablet/ASUSTek Computer/ROG/ROG Ally RC71L_RC71L/16B794CF2193/BAZZITE-41/6.11.10-304.BAZZITE.FC41.X86_64/X86_64/FD3DE9EA5C>) |
| 8086:5aca | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 56    | sdhci_pci  | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 56    | sdhci_pci  | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:5ad0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 46    | sdhci_pci  | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:31cc | 17aa:381f | Intel            | Celeron/Pentium Silver Processor ... | 17    | sdhci_pci  | [9BE1FF58FB](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGM 81MD/672E3FB63585/UBUNTU-24.04/6.8.0-38-GENERIC/X86_64/9BE1FF58FB>) |
| 8086:31cc | 17aa:3826 | Intel            | Celeron/Pentium Silver Processor ... | 13    | sdhci_pci  | [5DAD085952](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 10IGL5 82AT/F87C264A0B49/FEDORA-40/6.11.4-201.FC40.X86_64/X86_64/5DAD085952>) |
| 8086:9d2b | 152d:1182 | Intel            | Skylake-U/Y SCC: eMMC                | 13    | sdhci_pci  | [131E4B1570](<Tablet/Microsoft/Surface/Surface Go/DED51204263A/DEBIAN-12/6.1.0-28-AMD64/X86_64/131E4B1570>) |
| 8086:9d2d | 144d:c14f | Intel            | Sunrise Point-LP Secure Digital I... | 11    | sdhci_pci  | [EBD4E47906](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/EBD4E47906>) |
| 1217:8621 | 10f7:8338 | O2 Micro         | SD/MMC Card Reader Controller        | 10    | sdhci_pci  | [FAF64BB8A0](<Tablet/Panasonic/CF-33/CF-33-1/71D2DD20CB26/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/FAF64BB8A0>) |
| 8086:9d2b | 152d:1237 | Intel            | Skylake-U/Y SCC: eMMC                | 10    | sdhci_pci  | [B5609DF256](<Tablet/Microsoft/Surface/Surface Go 2/75A7DD72AE5E/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/B5609DF256>) |
| 8086:9d2b | 8086:9d2b | Intel            | Skylake-U/Y SCC: eMMC                | 10    | sdhci_pci  | [E19CC56E22](<Tablet/Google/Nocturne/Nocturne/8D21A3664295/FEDORA-40/5.10.165+/X86_64/E19CC56E22>) |
| 8086:9d2d | 8086:9d2d | Intel            | Sunrise Point-LP Secure Digital I... | 9     | sdhci_pci  | [80F7F9C98A](<Tablet/RuggedPC/RuggedPadY/RuggedPadY22/665AAC6AB368/UBUNTU-MATE-22.04/6.2.0-39-GENERIC/X86_64/80F7F9C98A>) |
| 8086:4dc4 |           | Intel            | Jasper Lake eMMC Controller          | 8     | sdhci_pci  | [E83E0E4EFA](<Tablet/RuggedPC/RuggedBookJ/RuggedBookJ61/3077AC07A524/FEDORA-40/6.11.3-200.FC40.X86_64/X86_64/E83E0E4EFA>) |
| 8086:4df8 |           | Intel            | Jasper Lake SD Controller            | 8     | sdhci_pci  | [E83E0E4EFA](<Tablet/RuggedPC/RuggedBookJ/RuggedBookJ61/3077AC07A524/FEDORA-40/6.11.3-200.FC40.X86_64/X86_64/E83E0E4EFA>) |
| 8086:31cc | 8086:31cc | Intel            | Celeron/Pentium Silver Processor ... | 7     | sdhci_pci  | [63FD3737DE](<Tablet/Tactus/GeoPad/GeoPad 110/0F02FAE679C1/ZORIN-17/6.5.0-35-GENERIC/X86_64/63FD3737DE>) |
| 8086:31d0 | 8086:31d0 | Intel            | Celeron/Pentium Silver SD Host Co... | 7     | sdhci_pci  | [63FD3737DE](<Tablet/Tactus/GeoPad/GeoPad 110/0F02FAE679C1/ZORIN-17/6.5.0-35-GENERIC/X86_64/63FD3737DE>) |
| 8086:5aca | 8086:5aca | Intel            | Celeron N3350/Pentium N4200/Atom ... | 7     | sdhci_pci  | [4D20F47175](<Tablet/ZoomSmart/A/A8006/BE4A5F803E00/ROSA-12.4/5.15.117-GENERIC-1ROSA2021.1-X86_64/X86_64/4D20F47175>) |
| 8086:5acc | 8086:5acc | Intel            | Celeron N3350/Pentium N4200/Atom ... | 7     | sdhci_pci  | [4D20F47175](<Tablet/ZoomSmart/A/A8006/BE4A5F803E00/ROSA-12.4/5.15.117-GENERIC-1ROSA2021.1-X86_64/X86_64/4D20F47175>) |
| 8086:5ad0 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 7     | sdhci_pci  | [4D20F47175](<Tablet/ZoomSmart/A/A8006/BE4A5F803E00/ROSA-12.4/5.15.117-GENERIC-1ROSA2021.1-X86_64/X86_64/4D20F47175>) |
| 8086:9d2b | 8086:7270 | Intel            | Skylake-U/Y SCC: eMMC                | 7     | sdhci_pci  | [72FE932E5D](<Tablet/Microsoft/Surface/Surface Go 3/5F79CE7ED6A9/ENDEAVOUROS-ROLLING/6.7.6-ARCH1-1-SURFACE/X86_64/72FE932E5D>) |
| 1217:8621 | 17aa:3825 | O2 Micro         | SD/MMC Card Reader Controller        | 6     | sdhci_pci  | [5DAD085952](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 10IGL5 82AT/F87C264A0B49/FEDORA-40/6.11.4-201.FC40.X86_64/X86_64/5DAD085952>) |
| 1217:8621 | 17aa:3822 | O2 Micro         | SD/MMC Card Reader Controller        | 5     | sdhci_pci  | [BE1F1A236B](<Tablet/Lenovo/Yoga/Yoga Duet IML 2020 82E9/B664B47B9CE3/FEDORA-40/6.8.8-300.FC40.X86_64/X86_64/BE1F1A236B>) |
| 8086:2295 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | sdhci_pci  | [EA5517388B](<Tablet/Hampoo/I1/I1D6_C109S_Hi10Pro/8F753D037AF0/BLENDOS/6.3.9-ZEN1-1-ZEN/X86_64/EA5517388B>) |
| 8086:54c4 |           | Intel            | Alder Lake-N SD Host Controller      | 5     | sdhci_pci  | [2AF3E8F0C5](<Tablet/Chuwi/Hi10/Hi10 Max/73DD33C3A827/ALT-11.0/6.12.6-6.12-ALT1/X86_64/2AF3E8F0C5>) |
| 1217:8621 | 17aa:3801 | O2 Micro         | SD/MMC Card Reader Controller        | 4     | sdhci_pci  | [40771F27EC](<Tablet/Lenovo/MIIX/MIIX 720-12IKB 80VV/890D2C33C909/ROCKY-9.4/5.14.0-427.13.1.EL9_4.X86_64/X86_64/40771F27EC>) |
| 1217:8621 | 17aa:3841 | O2 Micro         | SD/MMC Card Reader Controller        | 4     | sdhci_pci  | [CC0DBECE31](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/FA8378B128F2/ENDEAVOUROS-ROLLING/6.6.7-ARCH1-1/X86_64/CC0DBECE31>) |
| 17a0:9755 | 17a0:9755 | Genesys Logic    | GL9755 SD Host Controller            | 4     | sdhci_pci  | [00A92F4595](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/1BF345B071B6/BAZZITE-41/6.11.9-303.BAZZITE.FC41.X86_64/X86_64/00A92F4595>) |
| 10ec:5209 | 10ec:5209 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 3     | rtsx_pci   | [44AF16AC16](<Tablet/LG Electronics/15U340/15U340-L.BK55P1/96572D02BF5F/LINUXMINT-20/5.4.0-42-GENERIC/X86_64/44AF16AC16>) |
| 1217:8621 | 17aa:2261 | O2 Micro         | SD/MMC Card Reader Controller        | 3     | sdhci_pci  | [CBFF1B04E0](<Tablet/Lenovo/Tablet/Tablet 10 20L3000RGE/BBF4DFDD3007/UBUNTU-23.10/6.5.0-15-GENERIC/X86_64/CBFF1B04E0>) |
| 17a0:9755 | ffff:ffff | Genesys Logic    | GL9755 SD Host Controller            | 3     | sdhci_pci  | [CC5D5A528B](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZE/D3C6075AA186/ARCH-ROLLING/6.11.4-ARCH1-1/X86_64/CC5D5A528B>) |
| 8086:31cc | 17aa:2261 | Intel            | Celeron/Pentium Silver Processor ... | 3     | sdhci_pci  | [CBFF1B04E0](<Tablet/Lenovo/Tablet/Tablet 10 20L3000RGE/BBF4DFDD3007/UBUNTU-23.10/6.5.0-15-GENERIC/X86_64/CBFF1B04E0>) |
| 8086:31d0 | 17aa:2261 | Intel            | Celeron/Pentium Silver SD Host Co... | 3     | sdhci_pci  | [CBFF1B04E0](<Tablet/Lenovo/Tablet/Tablet 10 20L3000RGE/BBF4DFDD3007/UBUNTU-23.10/6.5.0-15-GENERIC/X86_64/CBFF1B04E0>) |
| 8086:4dc4 | 8086:7270 | Intel            | Jasper Lake eMMC Controller          | 3     | sdhci_pci  | [7780E6CD50](<Tablet/DERE/Others/Others/D328C1D92331/KUBUNTU-23.04/6.2.0-39-GENERIC/X86_64/7780E6CD50>) |
| 8086:4df8 | 8086:7270 | Intel            | Jasper Lake SD Controller            | 3     | sdhci_pci  | [5F97496A76](<Tablet/retsamarret/000/000-F4423-FBA004-2000-N/371AE0288EED/NIXOS-23.11/6.1.58/X86_64/5F97496A76>) |
| 8086:0f16 | 1509:7018 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | sdhci_pci  | [9347717861](<Tablet/Xplore/iX101/iX101B1/988A604FB8AB/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/9347717861>) |
| 8086:2294 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | sdhci_pci  | [50F89C1F2C](<Tablet/AXDIA International/PRIMO/PRIMO WIN 10/74DBACF4D9C5/ARCH-ROLLING/6.5.7-ARCH1-1/X86_64/50F89C1F2C>) |
| 8086:34c4 | 8086:7270 | Intel            | Ice Lake-LP SD Host Controller       | 2     | sdhci_pci  | [A2C1FD19AA](<Tablet/Microsoft/Surface/Surface Laptop Go/AFA5E6AAAFA6/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/A2C1FD19AA>) |
| 8086:4dc4 | 1043:1d02 | Intel            | Jasper Lake eMMC Controller          | 2     | sdhci_pci  | [1F850C6012](<Tablet/ASUSTek Computer/Vivobook/Vivobook Slate T3300KA_T3300KA/5E4B2F9BE565/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/1F850C6012>) |
| 8086:4df8 | 1043:1d02 | Intel            | Jasper Lake SD Controller            | 2     | sdhci_pci  | [1F850C6012](<Tablet/ASUSTek Computer/Vivobook/Vivobook Slate T3300KA_T3300KA/5E4B2F9BE565/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/1F850C6012>) |
| 1217:8621 | 1071:a125 | O2 Micro         | SD/MMC Card Reader Controller        | 1     | sdhci_pci  | [CBCDE33E6C](<Tablet/Getac/K120/K120G3/834E85EFA531/OPENSUSE-LEAP-15.6/6.4.0-150600.23.7-DEFAULT/X86_64/CBCDE33E6C>) |
| 1217:8621 | 10cf:1883 | O2 Micro         | SD/MMC Card Reader Controller        | 1     | sdhci_pci  | [9BC073F366](<Tablet/Fujitsu/STYLISTIC/STYLISTIC Q665/0A32CF1AA569/ZORIN-16/5.15.0-97-GENERIC/X86_64/9BC073F366>) |
| 1217:8621 | 10cf:1942 | O2 Micro         | SD/MMC Card Reader Controller        | 1     | sdhci_pci  | [CF0A931BC4](<Tablet/Fujitsu/FARQ/FARQ16011/0AA1C154091E/ZORIN-17/6.8.0-50-GENERIC/X86_64/CF0A931BC4>) |
| 1217:8621 | 17aa:3802 | O2 Micro         | SD/MMC Card Reader Controller        | 1     | sdhci_pci  | [50D3528425](<Tablet/Lenovo/MIIX710-12IKB/MIIX710-12IKB 80W1/2FB91DC53770/LINUXMINT-20.3/5.15.0-33-GENERIC/X86_64/50D3528425>) |
| 1217:8621 | 1e26:001d | O2 Micro         | SD/MMC Card Reader Controller        | 1     | sdhci_pci  | [E7DB77A1CE](<Tablet/Fujitsu/STYLISTIC/STYLISTIC Q7310/33C6B5DEF022/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/E7DB77A1CE>) |
| 8086:0f15 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | sdhci_pci  | [198C15E90A](<Tablet/System Mfg/Others/Others/AF6F46232DB6/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/198C15E90A>) |
| 8086:0f16 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | sdhci_pci  | [198C15E90A](<Tablet/System Mfg/Others/Others/AF6F46232DB6/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/198C15E90A>) |
| 8086:1190 |           | Intel            | Merrifield SD/SDIO/eMMC Controller   | 1     | sdhci_pci  | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:1aca | 8086:7270 | Intel            | SD Host Controller                   | 1     | sdhci_pci  | [555A26F0D1](<Tablet/Intel/570x/570x DVT3/469D9CAF87D4/UBUNTU-CORE-20/5.4.0-62-GENERIC/X86_64/555A26F0D1>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:34a4 | 8086:7270 | Intel            | Ice Lake-LP SPI Controller           | 152   | spi_int... | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:34c5 | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2c Control... | 152   | intel_l... | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:34e8 | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2C Control... | 152   | intel_l... | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:34ea | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2C Control... | 122   | intel_l... | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:34eb | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2C Control... | 87    | intel_l... | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:a0a4 | 8086:7270 | Intel            | Tiger Lake-LP SPI Controller         | 57    | spi_int... | [DA3534B096](<Tablet/Microsoft/Surface/Surface Pro 7+/87B1E5086B44/DEBIAN-12/6.1.0-28-AMD64/X86_64/DA3534B096>) |
| 8086:a0e8 | 8086:7270 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 57    | intel_l... | [DA3534B096](<Tablet/Microsoft/Surface/Surface Pro 7+/87B1E5086B44/DEBIAN-12/6.1.0-28-AMD64/X86_64/DA3534B096>) |
| 8086:a0c5 | 8086:7270 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 48    | intel_l... | [DA3534B096](<Tablet/Microsoft/Surface/Surface Pro 7+/87B1E5086B44/DEBIAN-12/6.1.0-28-AMD64/X86_64/DA3534B096>) |
| 8086:a0d8 | 8086:7270 | Intel            | Tiger Lake-LP Serial IO I2C Host ... | 48    | intel_lpss | [DA3534B096](<Tablet/Microsoft/Surface/Surface Pro 7+/87B1E5086B44/DEBIAN-12/6.1.0-28-AMD64/X86_64/DA3534B096>) |
| 8086:a0ea | 8086:7270 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 34    | intel_l... | [DA3534B096](<Tablet/Microsoft/Surface/Surface Pro 7+/87B1E5086B44/DEBIAN-12/6.1.0-28-AMD64/X86_64/DA3534B096>) |
| 8086:34e9 | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2C Control... | 33    | intel_l... | [03611F8371](<Tablet/Microsoft/Surface/Surface Book 3/B4A23748E2D4/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/03611F8371>) |
| 8086:a0eb | 8086:7270 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 26    | intel_lpss | [DA3534B096](<Tablet/Microsoft/Surface/Surface Pro 7+/87B1E5086B44/DEBIAN-12/6.1.0-28-AMD64/X86_64/DA3534B096>) |
| 8086:51a4 | 1043:1c42 | Intel            | Alder Lake-P PCH SPI Controller      | 24    | intel_spi  | [0A76D54F2A](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZE_GZ301ZE/E93163333EB2/UBUNTUSTUDIO-24.10/6.11.0-9-GENERIC/X86_64/0A76D54F2A>) |
| 8086:51e8 | 1043:1c42 | Intel            | Alder Lake PCH Serial IO I2C Cont... | 24    | intel_lpss | [0A76D54F2A](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZE_GZ301ZE/E93163333EB2/UBUNTUSTUDIO-24.10/6.11.0-9-GENERIC/X86_64/0A76D54F2A>) |
| 8086:51e9 | 1043:1c42 | Intel            | Alder Lake PCH Serial IO I2C Cont... | 24    | intel_lpss | [0A76D54F2A](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZE_GZ301ZE/E93163333EB2/UBUNTUSTUDIO-24.10/6.11.0-9-GENERIC/X86_64/0A76D54F2A>) |
| 8086:51a4 | 8086:7270 | Intel            | Alder Lake-P PCH SPI Controller      | 13    | spi_int... | [E6F037A5E8](<Tablet/Microsoft/Surface/Surface Pro 9/9EE1E883AC5A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E6F037A5E8>) |
| 8086:51e8 | 8086:7270 | Intel            | Alder Lake PCH Serial IO I2C Cont... | 13    | intel_l... | [E6F037A5E8](<Tablet/Microsoft/Surface/Surface Pro 9/9EE1E883AC5A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E6F037A5E8>) |
| 8086:a0a4 | 1028:0a45 | Intel            | Tiger Lake-LP SPI Controller         | 13    | spi_int... | [88D7EDA3A3](<Tablet/Dell/Latitude/Latitude 7320 Detachable/2FA880CABA50/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/88D7EDA3A3>) |
| 8086:a0e8 | 1028:0a45 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 13    | intel_l... | [88D7EDA3A3](<Tablet/Dell/Latitude/Latitude 7320 Detachable/2FA880CABA50/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/88D7EDA3A3>) |
| 8086:a0e9 | 1028:0a45 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 13    | intel_l... | [88D7EDA3A3](<Tablet/Dell/Latitude/Latitude 7320 Detachable/2FA880CABA50/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/88D7EDA3A3>) |
| 8086:a0ea | 1028:0a45 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 13    | intel_l... | [88D7EDA3A3](<Tablet/Dell/Latitude/Latitude 7320 Detachable/2FA880CABA50/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/88D7EDA3A3>) |
| 8086:a0a4 | 17aa:508b | Intel            | Tiger Lake-LP SPI Controller         | 12    | spi_int... | [57D1EC52E3](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UW0013US/9FE17438E905/DEBIAN-12/6.1.0-27-AMD64/X86_64/57D1EC52E3>) |
| 8086:a0e8 | 17aa:508b | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 12    | intel_lpss | [57D1EC52E3](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UW0013US/9FE17438E905/DEBIAN-12/6.1.0-27-AMD64/X86_64/57D1EC52E3>) |
| 8086:a0e9 | 17aa:508b | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 12    | intel_lpss | [57D1EC52E3](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UW0013US/9FE17438E905/DEBIAN-12/6.1.0-27-AMD64/X86_64/57D1EC52E3>) |
| 8086:a0eb | 17aa:508b | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 12    | intel_lpss | [57D1EC52E3](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UW0013US/9FE17438E905/DEBIAN-12/6.1.0-27-AMD64/X86_64/57D1EC52E3>) |
| 8086:a0a4 | 1ec9:3e44 | Intel            | Tiger Lake-LP SPI Controller         | 11    | intel_spi  | [2D0F2950BA](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/DFD066B5B806/FEDORA-41/6.11.7-300.FC41.X86_64/X86_64/2D0F2950BA>) |
| 8086:a0c5 | 1ec9:3e44 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 11    | intel_l... | [2D0F2950BA](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/DFD066B5B806/FEDORA-41/6.11.7-300.FC41.X86_64/X86_64/2D0F2950BA>) |
| 8086:a0e8 | 1ec9:3e44 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 11    | intel_l... | [2D0F2950BA](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/DFD066B5B806/FEDORA-41/6.11.7-300.FC41.X86_64/X86_64/2D0F2950BA>) |
| 8086:a0e9 | 1ec9:3e44 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 11    | intel_l... | [2D0F2950BA](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/DFD066B5B806/FEDORA-41/6.11.7-300.FC41.X86_64/X86_64/2D0F2950BA>) |
| 8086:a0ea | 1ec9:3e44 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 11    | intel_l... | [2D0F2950BA](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/DFD066B5B806/FEDORA-41/6.11.7-300.FC41.X86_64/X86_64/2D0F2950BA>) |
| 8086:a0eb | 1ec9:3e44 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 11    | intel_l... | [2D0F2950BA](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/DFD066B5B806/FEDORA-41/6.11.7-300.FC41.X86_64/X86_64/2D0F2950BA>) |
| 8086:51d8 | 8086:7270 | Intel            | Alder Lake-P Serial IO I2C Contro... | 10    | intel_l... | [E6F037A5E8](<Tablet/Microsoft/Surface/Surface Pro 9/9EE1E883AC5A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E6F037A5E8>) |
| 8086:a0a4 | 17aa:380b | Intel            | Tiger Lake-LP SPI Controller         | 10    | spi_int... | [AF8A5DF7BE](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/4236AA030B1D/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/AF8A5DF7BE>) |
| 8086:a0e8 | 17aa:3823 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 10    | intel_l... | [AF8A5DF7BE](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/4236AA030B1D/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/AF8A5DF7BE>) |
| 8086:a0e9 | 17aa:3824 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 10    | intel_l... | [AF8A5DF7BE](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/4236AA030B1D/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/AF8A5DF7BE>) |
| 8086:a0e9 | 8086:7270 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 10    | intel_l... | [79C895B3A3](<Tablet/Microsoft/Surface/Surface Laptop Studio/7EAF7CBE4A58/FEDORA-40/6.10.10-1.SURFACE.FC40.X86_64/X86_64/79C895B3A3>) |
| 8086:a0ea | 17aa:3825 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 10    | intel_l... | [AF8A5DF7BE](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/4236AA030B1D/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/AF8A5DF7BE>) |
| 8086:a0eb | 17aa:3828 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 10    | intel_l... | [AF8A5DF7BE](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/4236AA030B1D/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/AF8A5DF7BE>) |
| 8086:51a4 | 17aa:381f | Intel            | Alder Lake-P PCH SPI Controller      | 9     | spi_int... | [F2B2FFBFFE](<Tablet/Lenovo/XiaoXinDuet/XiaoXinDuet IAU7 82TQ/5FF690C6ECBE/KYLIN-V10/6.8.0-45-GENERIC/X86_64/F2B2FFBFFE>) |
| 8086:51c5 | 17aa:3815 | Intel            | Alder Lake-P Serial IO I2C Contro... | 9     | intel_l... | [F2B2FFBFFE](<Tablet/Lenovo/XiaoXinDuet/XiaoXinDuet IAU7 82TQ/5FF690C6ECBE/KYLIN-V10/6.8.0-45-GENERIC/X86_64/F2B2FFBFFE>) |
| 8086:51c6 | 17aa:3812 | Intel            | Alder Lake-P Serial IO I2C Contro... | 9     | intel_l... | [F2B2FFBFFE](<Tablet/Lenovo/XiaoXinDuet/XiaoXinDuet IAU7 82TQ/5FF690C6ECBE/KYLIN-V10/6.8.0-45-GENERIC/X86_64/F2B2FFBFFE>) |
| 8086:51e8 | 17aa:3824 | Intel            | Alder Lake PCH Serial IO I2C Cont... | 9     | intel_l... | [F2B2FFBFFE](<Tablet/Lenovo/XiaoXinDuet/XiaoXinDuet IAU7 82TQ/5FF690C6ECBE/KYLIN-V10/6.8.0-45-GENERIC/X86_64/F2B2FFBFFE>) |
| 8086:51e9 | 17aa:3830 | Intel            | Alder Lake PCH Serial IO I2C Cont... | 9     | intel_l... | [F2B2FFBFFE](<Tablet/Lenovo/XiaoXinDuet/XiaoXinDuet IAU7 82TQ/5FF690C6ECBE/KYLIN-V10/6.8.0-45-GENERIC/X86_64/F2B2FFBFFE>) |
| 8086:51ea | 8086:7270 | Intel            | Alder Lake PCH Serial IO I2C Cont... | 9     | intel_l... | [E6F037A5E8](<Tablet/Microsoft/Surface/Surface Pro 9/9EE1E883AC5A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E6F037A5E8>) |
| 8086:51eb | 8086:7270 | Intel            | Alder Lake PCH Serial IO I2C Cont... | 9     | intel_l... | [E6F037A5E8](<Tablet/Microsoft/Surface/Surface Pro 9/9EE1E883AC5A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E6F037A5E8>) |
| 8086:7e23 | 1043:1c43 | Intel            | Meteor Lake-P SPI Controller         | 9     | spi_int... | [DE52972775](<Tablet/ASUSTek Computer/ASUS/ASUS Zenbook Duo UX8406MA_UX8406MA/8A069640761E/ZORIN-17/6.8.0-50-GENERIC/X86_64/DE52972775>) |
| 8086:7e30 | 1043:1c43 | Intel            | Meteor Lake-P Serial IO SPI Contr... | 9     | intel_lpss | [DE52972775](<Tablet/ASUSTek Computer/ASUS/ASUS Zenbook Duo UX8406MA_UX8406MA/8A069640761E/ZORIN-17/6.8.0-50-GENERIC/X86_64/DE52972775>) |
| 8086:7e50 | 1043:1c43 | Intel            | Meteor Lake-P Serial IO I2C Contr... | 9     | intel_lpss | [DE52972775](<Tablet/ASUSTek Computer/ASUS/ASUS Zenbook Duo UX8406MA_UX8406MA/8A069640761E/ZORIN-17/6.8.0-50-GENERIC/X86_64/DE52972775>) |
| 8086:7e51 | 1043:1c43 | Intel            | Meteor Lake-P Serial IO I2C Contr... | 9     | intel_lpss | [DE52972775](<Tablet/ASUSTek Computer/ASUS/ASUS Zenbook Duo UX8406MA_UX8406MA/8A069640761E/ZORIN-17/6.8.0-50-GENERIC/X86_64/DE52972775>) |
| 8086:7e78 | 1043:1c43 | Intel            | Meteor Lake-P Serial IO I2C Contr... | 9     | intel_lpss | [DE52972775](<Tablet/ASUSTek Computer/ASUS/ASUS Zenbook Duo UX8406MA_UX8406MA/8A069640761E/ZORIN-17/6.8.0-50-GENERIC/X86_64/DE52972775>) |

### Serial controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:34fc | 8086:7270 | Intel            | Ice Lake-LP Integrated Sensor Sol... | 93    | intel_i... | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:9d3d | 1028:081d | Intel            | Sunrise Point-LP Active Managemen... | 15    | serial     | [20E6DC4833](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/069C27C420D3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.12.6-1-DEFAULT/X86_64/20E6DC4833>) |
| 8086:9d3d | 103c:82ca | Intel            | Sunrise Point-LP Active Managemen... | 14    | serial     | [F0D42DF827](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/0C327DDF3EC7/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/F0D42DF827>) |
| 8086:a0fc | 1028:0a45 | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 13    | intel_i... | [88D7EDA3A3](<Tablet/Dell/Latitude/Latitude 7320 Detachable/2FA880CABA50/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/88D7EDA3A3>) |
| 8086:9d3d | 10f7:8338 | Intel            | Sunrise Point-LP Active Managemen... | 12    | serial     | [FAF64BB8A0](<Tablet/Panasonic/CF-33/CF-33-1/71D2DD20CB26/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/FAF64BB8A0>) |
| 8086:9d3d | 17aa:2244 | Intel            | Sunrise Point-LP Active Managemen... | 12    | serial     | [454126AC6E](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KKS0S901/980E2F97C968/ARCH-ROLLING/6.12.6-ZEN1-1-ZEN/X86_64/454126AC6E>) |
| 8086:a0fc | 17aa:508b | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 12    | intel_i... | [57D1EC52E3](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UW0013US/9FE17438E905/DEBIAN-12/6.1.0-27-AMD64/X86_64/57D1EC52E3>) |
| 8086:9d3d | 1028:07a4 | Intel            | Sunrise Point-LP Active Managemen... | 11    | serial     | [9BDEF7697E](<Tablet/Dell/Latitude/Latitude 5285/03AE783826C3/ZORIN-17/6.8.0-45-GENERIC/X86_64/9BDEF7697E>) |
| 8086:a0fc | 1ec9:3e44 | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 11    | intel_i... | [2D0F2950BA](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/DFD066B5B806/FEDORA-41/6.11.7-300.FC41.X86_64/X86_64/2D0F2950BA>) |
| 8086:a0fc | 8086:7270 | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 11    | intel_i... | [DA3534B096](<Tablet/Microsoft/Surface/Surface Pro 7+/87B1E5086B44/DEBIAN-12/6.1.0-28-AMD64/X86_64/DA3534B096>) |
| 8086:a0fc | 17aa:382d | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 10    | intel_i... | [AF8A5DF7BE](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/4236AA030B1D/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/AF8A5DF7BE>) |
| 8086:51fc | 8086:7270 | Intel            | Alder Lake-P Integrated Sensor Hub   | 9     | intel_i... | [F2B2FFBFFE](<Tablet/Lenovo/XiaoXinDuet/XiaoXinDuet IAU7 82TQ/5FF690C6ECBE/KYLIN-V10/6.8.0-45-GENERIC/X86_64/F2B2FFBFFE>) |
| 8086:7e45 | 1043:1c43 | Intel            | Meteor Lake-P Integrated Sensor Hub  | 9     | intel_i... | [DE52972775](<Tablet/ASUSTek Computer/ASUS/ASUS Zenbook Duo UX8406MA_UX8406MA/8A069640761E/ZORIN-17/6.8.0-50-GENERIC/X86_64/DE52972775>) |
| 8086:9dfc | 103c:85b9 | Intel            | Cannon Point-LP Integrated Sensor... | 9     | intel_i... | [C43E6E357D](<Tablet/Hewlett-Packard/Elite/Elite x2 G4/28B313198BDD/OPENSUSE-LEAP-15.6/6.4.0-150600.23.25-DEFAULT/X86_64/C43E6E357D>) |
| 8086:a0e3 | 1028:0a45 | Intel            | Tiger Lake-LP Active Management T... | 9     | serial     | [DF9A5FCA61](<Tablet/Dell/Latitude/Latitude 7320 Detachable/32531BC5FA64/UBUNTU-24.10/6.11.0-8-GENERIC/X86_64/DF9A5FCA61>) |
| 8086:02fc | 1028:09ba | Intel            | Comet Lake Integrated Sensor Solu... | 7     | intel_i... | [657C7CAF3D](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/B6F2D71B615A/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/657C7CAF3D>) |
| 8086:9d3d | 1028:06e6 | Intel            | Sunrise Point-LP Active Managemen... | 7     | serial     | [3D35015785](<Tablet/Dell/Latitude/Latitude 5175/C19D3E088A8A/UBUNTU-24.04/6.8.0-36-GENERIC/X86_64/3D35015785>) |
| 8086:9d3d | 103c:828b | Intel            | Sunrise Point-LP Active Managemen... | 7     | serial     | [801E7F0D37](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/511DCA1BED34/LMDE-5/6.1.0-23-AMD64/X86_64/801E7F0D37>) |
| 8086:9d3d | 17aa:2241 | Intel            | Sunrise Point-LP Active Managemen... | 7     | serial     | [047961B6D0](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/7D7EF3298D39/FEDORA-41/6.12.5-200.FC41.X86_64/X86_64/047961B6D0>) |
| 8086:02fc | 17aa:380c | Intel            | Comet Lake Integrated Sensor Solu... | 6     | intel_i... | [BE1F1A236B](<Tablet/Lenovo/Yoga/Yoga Duet IML 2020 82E9/B664B47B9CE3/FEDORA-40/6.8.8-300.FC40.X86_64/X86_64/BE1F1A236B>) |
| 8086:9d3d | 17aa:2243 | Intel            | Sunrise Point-LP Active Managemen... | 6     | serial     | [BA288E243C](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCS06N0D/45C0E5B583E8/NIXOS-24.05/6.6.66/X86_64/BA288E243C>) |
| 8086:02e3 | 1028:09ba | Intel            | Comet Lake AMT SOL Redirection       | 5     | serial     | [657C7CAF3D](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/B6F2D71B615A/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/657C7CAF3D>) |
| 8086:51fc | 1028:0b34 | Intel            | Alder Lake-P Integrated Sensor Hub   | 4     | intel_i... | [91717BA12B](<Tablet/Dell/XPS/XPS 13 9315 2-in-1/1EF842C3A2C1/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/91717BA12B>) |
| 8086:9d3d | 1028:07a5 | Intel            | Sunrise Point-LP Active Managemen... | 4     | serial     | [3C7AF58DAF](<Tablet/Dell/Latitude/Latitude 7285/35CB641DDB78/REBORNOS/6.6.8-ARCH1-1/X86_64/3C7AF58DAF>) |
| 8086:9de3 | 103c:85b9 | Intel            | Cannon Point-LP Keyboard and Text... | 4     | serial     | [457690EA99](<Tablet/Hewlett-Packard/Elite/Elite x2 G4/1423EFB79A8C/FEDORA-39/6.5.12-300.FC39.X86_64/X86_64/457690EA99>) |
| 8086:9dfc | 1028:08e9 | Intel            | Cannon Point-LP Integrated Sensor... | 4     | intel_i... | [8D53A4B7AB](<Tablet/Dell/Latitude/Latitude 7200 2-in-1/733991F40E18/MANJARO/6.9.0-1-MANJARO/X86_64/8D53A4B7AB>) |
| 8086:54fc | 17aa:382f | Intel            | Alder Lake-N Integrated Sensor So... | 3     | intel_i... | [EFDBD13C32](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 11IAN8 82XK/EAC815E6BF54/UBUNTU-24.04/6.8.0-1005-OEM/X86_64/EFDBD13C32>) |
| 8086:9d3d | 1028:06d6 | Intel            | Sunrise Point-LP Active Managemen... | 3     | serial     | [FDEBA04A06](<Tablet/Dell/Latitude/Latitude 7275/63AAFB074631/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/FDEBA04A06>) |
| 8086:9de3 | 1028:08e9 | Intel            | Cannon Point-LP Keyboard and Text... | 3     | serial     | [5720C32C5F](<Tablet/Dell/Latitude/Latitude 7200 2-in-1/445C94F28B92/FEDORA-39/6.7.10-200.FC39.X86_64/X86_64/5720C32C5F>) |
| 8086:a0e3 | 103c:870d | Intel            | Tiger Lake-LP Active Management T... | 3     | serial     | [1C35A7F11B](<Tablet/Hewlett-Packard/Elite/Elite x2 G8 Tablet/6D7618F54734/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/1C35A7F11B>) |
| 8086:a0e3 | 17aa:508b | Intel            | Tiger Lake-LP Active Management T... | 3     | serial     | [47BA2BFFD7](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UVS3KP00/3E0712FB5649/UBUNTU-24.04/6.8.0-47-GENERIC/X86_64/47BA2BFFD7>) |
| 8086:a0fc | 103c:870d | Intel            | Tiger Lake-LP Integrated Sensor Hub  | 3     | intel_i... | [1C35A7F11B](<Tablet/Hewlett-Packard/Elite/Elite x2 G8 Tablet/6D7618F54734/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/1C35A7F11B>) |
| 8086:1e3d | 10f7:8338 | Intel            | 7 Series/C210 Series Chipset Fami... | 2     | serial     | [06F11C0449](<Tablet/Panasonic/FZ-G1/FZ-G1ASH39E3/6F2FB083615E/ELEMENTARY-6/5.11.0-37-GENERIC/X86_64/06F11C0449>) |
| 8086:51e3 | 17aa:2301 | Intel            | Alder Lake AMT SOL Redirection       | 2     | serial     | [CF313FDFA9](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Fold 16 Gen 1 21ESCTO1WW/F09CE9BCB863/ARCH-ROLLING/6.10.10-ARCH1-1/X86_64/CF313FDFA9>) |
| 8086:51fc | 17aa:2301 | Intel            | Alder Lake-P Integrated Sensor Hub   | 2     | intel_i... | [CF313FDFA9](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Fold 16 Gen 1 21ESCTO1WW/F09CE9BCB863/ARCH-ROLLING/6.10.10-ARCH1-1/X86_64/CF313FDFA9>) |
| 8086:51fc | 1ec9:3e65 | Intel            | Alder Lake-P Integrated Sensor Hub   | 2     | intel_i... | [A19D185643](<Tablet/HUAWEI/DRR-WXX/DRR-WXX/C1EB6A918CD1/ALT-10.3/6.1.81-UN-DEF-ALT1/X86_64/A19D185643>) |
| 8086:54fc |           | Intel            | Alder Lake-N Integrated Sensor So... | 2     | intel_i... | [5818AF4069](<Tablet/ASUSTek Computer/Vivobook/Vivobook Slate T3304GA_T3304GA/5E90379EE4A3/VANILLA-2.0/6.11.6-AMD64/X86_64/5818AF4069>) |
| 8086:9d3d | 103c:8414 | Intel            | Sunrise Point-LP Active Managemen... | 2     | serial     | [F6B59B1EE6](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/37102CAB5FCF/LINUXMINT-21.3/5.15.0-122-GENERIC/X86_64/F6B59B1EE6>) |
| 8086:02e3 | 10f7:8338 | Intel            | Comet Lake AMT SOL Redirection       | 1     | serial     | [2295DE0CC3](<Tablet/Panasonic/CF-33/CF-33-2/F3304BC32864/OPENSUSE-LEAP-15.4/5.14.21-150400.24.97-DEFAULT/X86_64/2295DE0CC3>) |
| 8086:02e3 | 1e26:003f | Intel            | Comet Lake AMT SOL Redirection       | 1     | serial     | [E7DB77A1CE](<Tablet/Fujitsu/STYLISTIC/STYLISTIC Q7310/33C6B5DEF022/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/E7DB77A1CE>) |
| 8086:02fc | 1071:d301 | Intel            | Comet Lake Integrated Sensor Solu... | 1     | intel_i... | [6F57AB0251](<Tablet/Getac/UX10/UX10G2/9B2D92B11BC9/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/6F57AB0251>) |
| 8086:02fc | 10f7:8338 | Intel            | Comet Lake Integrated Sensor Solu... | 1     | intel_i... | [2295DE0CC3](<Tablet/Panasonic/CF-33/CF-33-2/F3304BC32864/OPENSUSE-LEAP-15.4/5.14.21-150400.24.97-DEFAULT/X86_64/2295DE0CC3>) |
| 8086:02fc | 1e26:003f | Intel            | Comet Lake Integrated Sensor Solu... | 1     | intel_i... | [E7DB77A1CE](<Tablet/Fujitsu/STYLISTIC/STYLISTIC Q7310/33C6B5DEF022/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/E7DB77A1CE>) |
| 8086:1191 |           | Intel            | Merrifield Serial IO HSUART Contr... | 1     |            | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:1192 |           | Intel            | Merrifield Serial IO HSUART DMA C... | 1     |            | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:1c3d | 10f7:8338 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | serial     | [50E0A85FD3](<Tablet/Panasonic/CF-H2/CF-H2BJJHZDE/E17482358B17/LMDE-5/5.10.0-13-AMD64/X86_64/50E0A85FD3>) |
| 8086:51fc | 1071:a125 | Intel            | Alder Lake-P Integrated Sensor Hub   | 1     | intel_i... | [CBCDE33E6C](<Tablet/Getac/K120/K120G3/834E85EFA531/OPENSUSE-LEAP-15.6/6.4.0-150600.23.7-DEFAULT/X86_64/CBCDE33E6C>) |
| 8086:54fc | 8086:7270 | Intel            | Alder Lake-N Integrated Sensor So... | 1     | intel_i... | [DE1603934E](<Tablet/Microsoft/Surface/Surface Go 4/EB7135250A70/OPENMANDRIVA-24.07/6.9.7-DESKTOP-1OMV2490/X86_64/DE1603934E>) |
| 8086:7e45 | 1462:143a | Intel            | Meteor Lake-P Integrated Sensor Hub  | 1     | intel_i... | [2EBDE0820D](<Tablet/MSI/Claw/Claw A1M/E9FB50149AEE/STEAMOS-ROLLING/6.11.1-1/X86_64/2EBDE0820D>) |
| 8086:98fc | 17aa:22c6 | Intel            | Integrated Sensor Device             | 1     |            | [A06677F6EA](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Fold Gen 1 20RL000GIX/E29339E09DD9/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/A06677F6EA>) |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d31 | 8086:7270 | Intel            | Sunrise Point-LP Thermal subsystem   | 448   | intel_p... | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:9d60 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 448   | intel_l... | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:9d61 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 448   | intel_l... | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:9d63 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 422   | intel_l... | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:9d62 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 420   | intel_l... | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:9d27 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO UART C... | 243   | intel_l... | [EAF1BB652C](<Tablet/Microsoft/Surface/Surface Book 2/B870A7627396/ARCH-ROLLING/6.12.7-ARCH1-1-NSB2/X86_64/EAF1BB652C>) |
| 8086:1903 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 237   | process... | [EAF1BB652C](<Tablet/Microsoft/Surface/Surface Book 2/B870A7627396/ARCH-ROLLING/6.12.7-ARCH1-1-NSB2/X86_64/EAF1BB652C>) |
| 8086:22dc | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 146   | process... | [496C93250D](<Tablet/Chuwi/Hi10/Hi10 pro tablet/D5A4927F3C98/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/496C93250D>) |
| 8086:8a03 | 8086:7270 | Intel            | Processor Power and Thermal Contr... | 97    | proc_th... | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:31b4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 90    | intel_l... | [1827AD6649](<Tablet/Microsoft/Surface/Surface Laptop SE/3C3B6159F009/ZORIN-17/6.8.0-49-GENERIC/X86_64/1827AD6649>) |
| 8086:31b6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 90    | intel_l... | [1827AD6649](<Tablet/Microsoft/Surface/Surface Laptop SE/3C3B6159F009/ZORIN-17/6.8.0-49-GENERIC/X86_64/1827AD6649>) |
| 8086:31b8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 90    | intel_l... | [1827AD6649](<Tablet/Microsoft/Surface/Surface Laptop SE/3C3B6159F009/ZORIN-17/6.8.0-49-GENERIC/X86_64/1827AD6649>) |
| 8086:31bc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 90    | intel_l... | [1827AD6649](<Tablet/Microsoft/Surface/Surface Laptop SE/3C3B6159F009/ZORIN-17/6.8.0-49-GENERIC/X86_64/1827AD6649>) |
| 8086:31c0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 90    | intel_l... | [1827AD6649](<Tablet/Microsoft/Surface/Surface Laptop SE/3C3B6159F009/ZORIN-17/6.8.0-49-GENERIC/X86_64/1827AD6649>) |
| 8086:318c | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 87    | process... | [026269E60B](<Tablet/Others/Others/Others/B4F90A2AAF5D/LINUXMINT-22/6.8.0-50-GENERIC/X86_64/026269E60B>) |
| 8086:31ac | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 87    | intel_l... | [026269E60B](<Tablet/Others/Others/Others/B4F90A2AAF5D/LINUXMINT-22/6.8.0-50-GENERIC/X86_64/026269E60B>) |
| 8086:31ae | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 87    | intel_l... | [026269E60B](<Tablet/Others/Others/Others/B4F90A2AAF5D/LINUXMINT-22/6.8.0-50-GENERIC/X86_64/026269E60B>) |
| 8086:31b0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 87    | intel_l... | [026269E60B](<Tablet/Others/Others/Others/B4F90A2AAF5D/LINUXMINT-22/6.8.0-50-GENERIC/X86_64/026269E60B>) |
| 8086:31b2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 87    | intel_l... | [026269E60B](<Tablet/Others/Others/Others/B4F90A2AAF5D/LINUXMINT-22/6.8.0-50-GENERIC/X86_64/026269E60B>) |
| 8086:31ba | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 87    | intel_l... | [026269E60B](<Tablet/Others/Others/Others/B4F90A2AAF5D/LINUXMINT-22/6.8.0-50-GENERIC/X86_64/026269E60B>) |
| 8086:31be | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 87    | intel_l... | [026269E60B](<Tablet/Others/Others/Others/B4F90A2AAF5D/LINUXMINT-22/6.8.0-50-GENERIC/X86_64/026269E60B>) |
| 8086:31c2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 87    | intel_l... | [026269E60B](<Tablet/Others/Others/Others/B4F90A2AAF5D/LINUXMINT-22/6.8.0-50-GENERIC/X86_64/026269E60B>) |
| 8086:31c4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 87    | intel_l... | [026269E60B](<Tablet/Others/Others/Others/B4F90A2AAF5D/LINUXMINT-22/6.8.0-50-GENERIC/X86_64/026269E60B>) |
| 8086:31c6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 87    | intel_l... | [026269E60B](<Tablet/Others/Others/Others/B4F90A2AAF5D/LINUXMINT-22/6.8.0-50-GENERIC/X86_64/026269E60B>) |
| 8086:31ee | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 87    | intel_l... | [026269E60B](<Tablet/Others/Others/Others/B4F90A2AAF5D/LINUXMINT-22/6.8.0-50-GENERIC/X86_64/026269E60B>) |
| 8086:22dc | 17aa:3809 | Intel            | Atom/Celeron/Pentium Processor x5... | 80    | proc_th... | [53BAB82FAE](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/384948008566/ALPINE-3.20.3/6.6.63-0-LTS/X86_64/53BAB82FAE>) |
| 8086:22dc | 17aa:3808 | Intel            | Atom/Celeron/Pentium Processor x5... | 65    | proc_th... | [C377803591](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/FE4476C805C4/KDE-NEON-24.04/6.8.0-47-GENERIC/X86_64/C377803591>) |
| 8086:22dc | 7270:8086 | Intel            | Atom/Celeron/Pentium Processor x5... | 59    | process... | [C8EB4963E5](<Tablet/OEM/M882/M882CWP/9C7F836ED3EA/FEDORA-40/6.10.10-200.FC40.X86_64/X86_64/C8EB4963E5>) |
| 8086:9a0d | 8086:7270 | Intel            | Tigerlake Telemetry Aggregator       | 57    | intel_vsec | [DA3534B096](<Tablet/Microsoft/Surface/Surface Pro 7+/87B1E5086B44/DEBIAN-12/6.1.0-28-AMD64/X86_64/DA3534B096>) |
| 8086:5aac | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 56    | intel_l... | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:5aae | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 56    | intel_l... | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:5ab2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 56    | intel_l... | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:5ab4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 56    | intel_l... | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:5ab6 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 56    | intel_l... | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:1903 | 152d:1182 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 54    | process... | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 8086:9d27 | 152d:1182 | Intel            | Sunrise Point-LP Serial IO UART C... | 54    | intel_l... | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 8086:9d31 | 152d:1182 | Intel            | Sunrise Point-LP Thermal subsystem   | 54    | intel_p... | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 8086:9d60 | 152d:1182 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 54    | intel_l... | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 8086:9d61 | 152d:1182 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 54    | intel_l... | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 8086:9d62 | 152d:1182 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 54    | intel_l... | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 8086:9d63 | 152d:1182 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 54    | intel_l... | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 8086:9d64 | 152d:1182 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 54    | intel_l... | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 8086:9d66 | 152d:1182 | Intel            | Sunrise Point-LP Serial IO UART C... | 54    | intel_l... | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 8086:1903 | 8086:1903 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 49    | proc_th... | [F5A5189E2A](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/1940EF4E595D/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.11.8-1-DEFAULT/X86_64/F5A5189E2A>) |
| 8086:5ab0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 46    | intel_l... | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:5ab8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 46    | intel_l... | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:5aba | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 46    | intel_l... | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:5ac2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 46    | intel_l... | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:5ac4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 46    | intel_l... | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:5ac6 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 46    | intel_l... | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9c22 | 1414:9c22 | Intel            | 8 Series SMBus Controller            | 150   | i2c_i801   | [BB626D70B0](<Tablet/Microsoft/Surface/Surface Pro 3/217C1E4144F1/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/BB626D70B0>) |
| 8086:31d4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 87    | i2c_i801   | [026269E60B](<Tablet/Others/Others/Others/B4F90A2AAF5D/LINUXMINT-22/6.8.0-50-GENERIC/X86_64/026269E60B>) |
| 1022:790b | 1022:790b | AMD              | FCH SMBus Controller                 | 59    | piix4_s... | [2183EB76B7](<Tablet/ONE-NETBOOK/ONEXPLAYER/ONEXPLAYER Mini Pro/F55453A23AA1/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/2183EB76B7>) |
| 8086:5ad4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 56    | i2c_i801   | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:9d23 | 8086:7270 | Intel            | Sunrise Point-LP SMBus               | 50    | i801_smbus | [EAF1BB652C](<Tablet/Microsoft/Surface/Surface Book 2/B870A7627396/ARCH-ROLLING/6.12.7-ARCH1-1-NSB2/X86_64/EAF1BB652C>) |
| 8086:9d23 | 103c:82ca | Intel            | Sunrise Point-LP SMBus               | 36    | i2c_i801   | [F0D42DF827](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/0C327DDF3EC7/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/F0D42DF827>) |
| 1022:790b | 1043:17f3 | AMD              | FCH SMBus Controller                 | 29    | piix4_s... | [FD3DE9EA5C](<Tablet/ASUSTek Computer/ROG/ROG Ally RC71L_RC71L/16B794CF2193/BAZZITE-41/6.11.10-304.BAZZITE.FC41.X86_64/X86_64/FD3DE9EA5C>) |
| 8086:0f12 | 1019:99a5 | Intel            | Atom Processor E3800/CE2700 Serie... | 27    | i2c_i801   | [DA6CE4B361](<Tablet/BANGHO/Suma/Suma 1025/DF80AD331B24/ZORIN-17/6.8.0-49-GENERIC/X86_64/DA6CE4B361>) |
| 8086:9d23 | 1028:081d | Intel            | Sunrise Point-LP SMBus               | 27    | i801_smbus | [20E6DC4833](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/069C27C420D3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.12.6-1-DEFAULT/X86_64/20E6DC4833>) |
| 8086:9d23 | 103c:828b | Intel            | Sunrise Point-LP SMBus               | 26    | i2c_i801   | [567E4C6343](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/53B866CA15BB/ZORIN-17/6.8.0-45-GENERIC/X86_64/567E4C6343>) |
| 1022:790b | 17aa:3812 | AMD              | FCH SMBus Controller                 | 25    | piix4_s... | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 8086:9d23 | 17aa:2244 | Intel            | Sunrise Point-LP SMBus               | 25    | i2c_i801   | [454126AC6E](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KKS0S901/980E2F97C968/ARCH-ROLLING/6.12.6-ZEN1-1-ZEN/X86_64/454126AC6E>) |
| 8086:51a3 | 1043:1c42 | Intel            | Alder Lake PCH-P SMBus Host Contr... | 24    | i801_smbus | [0A76D54F2A](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZE_GZ301ZE/E93163333EB2/UBUNTUSTUDIO-24.10/6.11.0-9-GENERIC/X86_64/0A76D54F2A>) |
| 8086:1e22 | 1414:1e22 | Intel            | 7 Series/C216 Chipset Family SMBu... | 21    | i801_smbus | [09BDD29B6C](<Tablet/Microsoft/Surface/Surface Pro 2/DD2937B6F574/VANILLA-2.0/6.11.6-AMD64/X86_64/09BDD29B6C>) |
| 8086:9d23 | 17aa:384f | Intel            | Sunrise Point-LP SMBus               | 21    | i801_smbus | [C14BE2A0FF](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/A8FA91459A71/ZORIN-17/6.8.0-40-GENERIC/X86_64/C14BE2A0FF>) |
| 1002:4385 | 1025:0577 | AMD              | SBx00 SMBus Controller               | 19    | i2c_pii... | [AC15CCA834](<Tablet/Acer/Iconia/Iconia Tab W500/00630A96A0A7/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/AC15CCA834>) |
| 1022:790b | 1f4c:e001 | AMD              | FCH SMBus Controller                 | 18    | piix4_s... | [0BC6665145](<Tablet/Micro Computer (HK) Tech Limited/V/V3/F17AC0C7E80F/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/0BC6665145>) |
| 8086:31d4 | 17aa:3823 | Intel            | Celeron/Pentium Silver Processor ... | 17    | i2c_i801   | [9BE1FF58FB](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGM 81MD/672E3FB63585/UBUNTU-24.04/6.8.0-38-GENERIC/X86_64/9BE1FF58FB>) |
| 8086:9d23 | 17aa:2243 | Intel            | Sunrise Point-LP SMBus               | 17    | i2c_i801   | [BA288E243C](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCS06N0D/45C0E5B583E8/NIXOS-24.05/6.6.66/X86_64/BA288E243C>) |
| 8086:31d4 | 17aa:3829 | Intel            | Celeron/Pentium Silver Processor ... | 13    | i2c_i801   | [5DAD085952](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 10IGL5 82AT/F87C264A0B49/FEDORA-40/6.11.4-201.FC40.X86_64/X86_64/5DAD085952>) |
| 8086:9d23 | 1028:07a4 | Intel            | Sunrise Point-LP SMBus               | 13    | i2c_i801   | [9BDEF7697E](<Tablet/Dell/Latitude/Latitude 5285/03AE783826C3/ZORIN-17/6.8.0-45-GENERIC/X86_64/9BDEF7697E>) |
| 8086:a0a3 | 1028:0a45 | Intel            | Tiger Lake-LP SMBus Controller       | 13    | i2c_i801   | [88D7EDA3A3](<Tablet/Dell/Latitude/Latitude 7320 Detachable/2FA880CABA50/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/88D7EDA3A3>) |
| 8086:9d23 | 10f7:8338 | Intel            | Sunrise Point-LP SMBus               | 12    | i2c_i801   | [FAF64BB8A0](<Tablet/Panasonic/CF-33/CF-33-1/71D2DD20CB26/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/FAF64BB8A0>) |
| 8086:a0a3 | 17aa:508b | Intel            | Tiger Lake-LP SMBus Controller       | 12    | i2c_i801   | [57D1EC52E3](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UW0013US/9FE17438E905/DEBIAN-12/6.1.0-27-AMD64/X86_64/57D1EC52E3>) |
| 8086:9d23 | 1028:06e6 | Intel            | Sunrise Point-LP SMBus               | 11    | i2c_i801   | [31A3C7AF1E](<Tablet/Dell/Latitude/Latitude 5175/CD1C9C82C174/FEDORA-41/6.11.11-300.FC41.X86_64/X86_64/31A3C7AF1E>) |
| 8086:9d23 | 103c:8414 | Intel            | Sunrise Point-LP SMBus               | 11    | i2c_i801   | [A1F8F4C528](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/92E2795CC5F7/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/A1F8F4C528>) |
| 8086:9d23 | 144d:c14f | Intel            | Sunrise Point-LP SMBus               | 11    | i2c_i801   | [EBD4E47906](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/EBD4E47906>) |
| 8086:9d23 | 17aa:2241 | Intel            | Sunrise Point-LP SMBus               | 11    | i2c_i801   | [047961B6D0](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/7D7EF3298D39/FEDORA-41/6.12.5-200.FC41.X86_64/X86_64/047961B6D0>) |
| 8086:9d23 | 17aa:3844 | Intel            | Sunrise Point-LP SMBus               | 11    | i2c_i801   | [00DE3D7E4C](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/248F2E7667A2/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/00DE3D7E4C>) |
| 8086:a0a3 | 1ec9:3e44 | Intel            | Tiger Lake-LP SMBus Controller       | 11    | i2c_i801   | [2D0F2950BA](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/DFD066B5B806/FEDORA-41/6.11.7-300.FC41.X86_64/X86_64/2D0F2950BA>) |
| 8086:9d23 | 8086:9d23 | Intel            | Sunrise Point-LP SMBus               | 10    | i2c_i801   | [E19CC56E22](<Tablet/Google/Nocturne/Nocturne/8D21A3664295/FEDORA-40/5.10.165+/X86_64/E19CC56E22>) |
| 8086:a0a3 | 17aa:3805 | Intel            | Tiger Lake-LP SMBus Controller       | 10    | i2c_i801   | [AF8A5DF7BE](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/4236AA030B1D/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/AF8A5DF7BE>) |
| 8086:51a3 | 17aa:381d | Intel            | Alder Lake PCH-P SMBus Host Contr... | 9     | i2c_i801   | [F2B2FFBFFE](<Tablet/Lenovo/XiaoXinDuet/XiaoXinDuet IAU7 82TQ/5FF690C6ECBE/KYLIN-V10/6.8.0-45-GENERIC/X86_64/F2B2FFBFFE>) |
| 8086:7e22 | 1043:1c43 | Intel            | Meteor Lake-P SMBus Controller       | 9     | i801_smbus | [DE52972775](<Tablet/ASUSTek Computer/ASUS/ASUS Zenbook Duo UX8406MA_UX8406MA/8A069640761E/ZORIN-17/6.8.0-50-GENERIC/X86_64/DE52972775>) |
| 8086:9da3 | 103c:85b9 | Intel            | Cannon Point-LP SMBus Controller     | 9     | i2c_i801   | [C43E6E357D](<Tablet/Hewlett-Packard/Elite/Elite x2 G4/28B313198BDD/OPENSUSE-LEAP-15.6/6.4.0-150600.23.25-DEFAULT/X86_64/C43E6E357D>) |
| 8086:4da3 |           | Intel            | Jasper Lake SMBus                    | 8     | i2c_i801   | [E83E0E4EFA](<Tablet/RuggedPC/RuggedBookJ/RuggedBookJ61/3077AC07A524/FEDORA-40/6.11.3-200.FC40.X86_64/X86_64/E83E0E4EFA>) |
| 8086:9ca2 | 17aa:222b | Intel            | Wildcat Point-LP SMBus Controller    | 8     | i2c_i801   | [DABF58331D](<Tablet/Lenovo/ThinkPad/ThinkPad Helix 2nd 20CGCTO1WW/C514BF421B7F/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/DABF58331D>) |
| 8086:9d23 | 1025:111e | Intel            | Sunrise Point-LP SMBus               | 8     | i801_smbus | [E68A5B419E](<Tablet/Acer/Switch/Switch SA5-271/8143477D8A59/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/E68A5B419E>) |
| 8086:9d23 | 1028:06d6 | Intel            | Sunrise Point-LP SMBus               | 8     | i801_smbus | [0FD89EC85A](<Tablet/Dell/Latitude/Latitude 7275/55EB4B609DF6/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/0FD89EC85A>) |
| 8086:9d23 | 144d:c135 | Intel            | Sunrise Point-LP SMBus               | 8     | i801_smbus | [F27DFBBBFB](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/FEDORA-40/6.11.3-200.FC40.X86_64/X86_64/F27DFBBBFB>) |
| 8086:02a3 | 1028:09ba | Intel            | Comet Lake PCH-LP SMBus Host Cont... | 7     | i2c_i801   | [657C7CAF3D](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/B6F2D71B615A/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/657C7CAF3D>) |
| 8086:0f12 | 1019:99a1 | Intel            | Atom Processor E3800/CE2700 Serie... | 7     | i2c_i801   | [0AC4B868CB](<Tablet/Medion/P/P2212T/1CC59B4B188A/FEDORA-40/6.9.5-200.FC40.X86_64/X86_64/0AC4B868CB>) |
| 8086:31d4 | 8086:31d4 | Intel            | Celeron/Pentium Silver Processor ... | 7     | i2c_i801   | [63FD3737DE](<Tablet/Tactus/GeoPad/GeoPad 110/0F02FAE679C1/ZORIN-17/6.5.0-35-GENERIC/X86_64/63FD3737DE>) |
| 8086:4da3 | 8086:7270 | Intel            | Jasper Lake SMBus                    | 7     | i2c_i801   | [7780E6CD50](<Tablet/DERE/Others/Others/D328C1D92331/KUBUNTU-23.04/6.2.0-39-GENERIC/X86_64/7780E6CD50>) |
| 8086:5ad4 | 8086:5ad4 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 7     | i2c_i801   | [4D20F47175](<Tablet/ZoomSmart/A/A8006/BE4A5F803E00/ROSA-12.4/5.15.117-GENERIC-1ROSA2021.1-X86_64/X86_64/4D20F47175>) |
| 8086:9d23 | 17aa:3829 | Intel            | Sunrise Point-LP SMBus               | 7     | i2c_i801   | [F5A5189E2A](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/1940EF4E595D/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.11.8-1-DEFAULT/X86_64/F5A5189E2A>) |
| 8086:31d4 |           | Intel            | Celeron/Pentium Silver Processor ... | 6     | i2c_i801   | [1827AD6649](<Tablet/Microsoft/Surface/Surface Laptop SE/3C3B6159F009/ZORIN-17/6.8.0-49-GENERIC/X86_64/1827AD6649>) |
| 8086:4da3 | 103c:8966 | Intel            | Jasper Lake SMBus                    | 6     | i801_smbus | [5A15B249A5](<Tablet/Hewlett-Packard/Tablet/Tablet 11m-be0xxx/442C1D1B1DB4/FEDORA-41/6.11.0-63.FC41.X86_64/X86_64/5A15B249A5>) |
| 8086:51a3 | 1043:1573 | Intel            | Alder Lake PCH-P SMBus Host Contr... | 6     | i801_smbus | [E35C79DDE2](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301VU_GZ301VU/2F999BBF1AC8/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/E35C79DDE2>) |
| 8086:9c22 | 17aa:3978 | Intel            | 8 Series SMBus Controller            | 6     | i801_smbus | [52FB0884A3](<Tablet/Lenovo/MIIX/MIIX 2 11 20327/735EB204853B/ZORIN-17/6.8.0-40-GENERIC/X86_64/52FB0884A3>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d71 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 256   | snd_hda... | [EAF1BB652C](<Tablet/Microsoft/Surface/Surface Book 2/B870A7627396/ARCH-ROLLING/6.12.7-ARCH1-1-NSB2/X86_64/EAF1BB652C>) |
| 8086:9d70 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 188   | snd_hda... | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:34c8 | 8086:7270 | Intel            | Ice Lake-LP Smart Sound Technolog... | 151   | snd_hda... | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:9c20 | 1414:9c20 | Intel            | 8 Series HD Audio Controller         | 150   | snd_hda... | [BB626D70B0](<Tablet/Microsoft/Surface/Surface Pro 3/217C1E4144F1/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/BB626D70B0>) |
| 8086:0a0c | 8086:0a0c | Intel            | Haswell-ULT HD Audio Controller      | 120   | snd_hda... | [BB626D70B0](<Tablet/Microsoft/Surface/Surface Pro 3/217C1E4144F1/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/BB626D70B0>) |
| 1002:1640 | 1002:1640 | AMD              | Rembrandt Radeon High Definition ... | 60    | snd_hda... | [2183EB76B7](<Tablet/ONE-NETBOOK/ONEXPLAYER/ONEXPLAYER Mini Pro/F55453A23AA1/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/2183EB76B7>) |
| 8086:a0c8 | 8086:7270 | Intel            | Tiger Lake-LP Smart Sound Technol... | 56    | snd_hda... | [DA3534B096](<Tablet/Microsoft/Surface/Surface Pro 7+/87B1E5086B44/DEBIAN-12/6.1.0-28-AMD64/X86_64/DA3534B096>) |
| 8086:9d71 | 152d:1182 | Intel            | Sunrise Point-LP HD Audio            | 53    | snd_hda... | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 8086:3198 | 1c6c:122a | Intel            | Celeron/Pentium Silver Processor ... | 45    | snd_hda... | [D3AC0F6A92](<Tablet/AVITA/NS12/NS12T5/2D1154BB2648/ZORIN-17/6.8.0-47-GENERIC/X86_64/D3AC0F6A92>) |
| 8086:9d71 | 103c:82ca | Intel            | Sunrise Point-LP HD Audio            | 35    | snd_hda... | [F0D42DF827](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/0C327DDF3EC7/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/F0D42DF827>) |
| 8086:0a0c | 8086:2010 | Intel            | Haswell-ULT HD Audio Controller      | 30    | snd_hda... | [964F81A59E](<Tablet/Microsoft/Surface/Surface Pro 2/9A502B2F7D5F/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/964F81A59E>) |
| 1022:15e3 | 1043:17f3 | AMD              | Family 17h/19h/1ah HD Audio Contr... | 29    | snd_hda... | [FD3DE9EA5C](<Tablet/ASUSTek Computer/ROG/ROG Ally RC71L_RC71L/16B794CF2193/BAZZITE-41/6.11.10-304.BAZZITE.FC41.X86_64/X86_64/FD3DE9EA5C>) |
| 8086:0f04 | 1019:99fa | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 27    | snd_hda... | [DA6CE4B361](<Tablet/BANGHO/Suma/Suma 1025/DF80AD331B24/ZORIN-17/6.8.0-49-GENERIC/X86_64/DA6CE4B361>) |
| 8086:9d71 | 1028:081d | Intel            | Sunrise Point-LP HD Audio            | 27    | snd_hda... | [20E6DC4833](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/069C27C420D3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.12.6-1-DEFAULT/X86_64/20E6DC4833>) |
| 8086:9d71 | 103c:828b | Intel            | Sunrise Point-LP HD Audio            | 26    | snd_hda... | [567E4C6343](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/53B866CA15BB/ZORIN-17/6.8.0-45-GENERIC/X86_64/567E4C6343>) |
| 1002:1640 | 17aa:3812 | AMD              | Rembrandt Radeon High Definition ... | 25    | snd_hda... | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 1022:15e3 | 17aa:3c26 | AMD              | Family 17h/19h/1ah HD Audio Contr... | 25    | snd_hda... | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 8086:9d71 | 17aa:2244 | Intel            | Sunrise Point-LP HD Audio            | 25    | snd_hda... | [454126AC6E](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KKS0S901/980E2F97C968/ARCH-ROLLING/6.12.6-ZEN1-1-ZEN/X86_64/454126AC6E>) |
| 8086:51c8 | 1043:1c42 | Intel            | Alder Lake PCH-P High Definition ... | 24    | snd_hda... | [0A76D54F2A](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZE_GZ301ZE/E93163333EB2/UBUNTUSTUDIO-24.10/6.11.0-9-GENERIC/X86_64/0A76D54F2A>) |
| 8086:9d71 | 152d:1237 | Intel            | Sunrise Point-LP HD Audio            | 24    | snd_hda... | [51D7C66A4E](<Tablet/Microsoft/Surface/Surface Go 2/CC8450395E18/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/51D7C66A4E>) |
| 8086:1e20 | 1414:1e20 | Intel            | 7 Series/C216 Chipset Family High... | 21    | snd_hda... | [09BDD29B6C](<Tablet/Microsoft/Surface/Surface Pro 2/DD2937B6F574/VANILLA-2.0/6.11.6-AMD64/X86_64/09BDD29B6C>) |
| 8086:9d71 | 17aa:3817 | Intel            | Sunrise Point-LP HD Audio            | 21    | snd_hda... | [C14BE2A0FF](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/A8FA91459A71/ZORIN-17/6.8.0-40-GENERIC/X86_64/C14BE2A0FF>) |
| 1002:1637 | 1002:1637 | AMD              | Renoir Radeon High Definition Aud... | 20    | snd_hda... | [F51B8777E8](<Tablet/ONE-NETBOOK TECHNOLOGY/ONE/ONE XPLAYER/B1E0FDA01E2B/CHIMERAOS-46-2/6.9.12-CHOS7-CHIMERAOS-1/X86_64/F51B8777E8>) |
| 1002:1314 | 1025:0577 | AMD              | Wrestler HDMI Audio                  | 19    | snd_hda... | [AC15CCA834](<Tablet/Acer/Iconia/Iconia Tab W500/00630A96A0A7/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/AC15CCA834>) |
| 1002:4383 | 1025:0577 | AMD              | SBx00 Azalia (Intel HDA)             | 19    | snd_hda... | [AC15CCA834](<Tablet/Acer/Iconia/Iconia Tab W500/00630A96A0A7/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/AC15CCA834>) |
| 1002:1640 | 1f4c:e001 | AMD              | Rembrandt Radeon High Definition ... | 18    | snd_hda... | [0BC6665145](<Tablet/Micro Computer (HK) Tech Limited/V/V3/F17AC0C7E80F/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/0BC6665145>) |
| 1022:15e3 | 1f4c:e001 | AMD              | Family 17h/19h/1ah HD Audio Contr... | 18    | snd_hda... | [0BC6665145](<Tablet/Micro Computer (HK) Tech Limited/V/V3/F17AC0C7E80F/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/0BC6665145>) |
| 8086:3198 | 17aa:3809 | Intel            | Celeron/Pentium Silver Processor ... | 17    | snd_hda... | [9BE1FF58FB](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGM 81MD/672E3FB63585/UBUNTU-24.04/6.8.0-38-GENERIC/X86_64/9BE1FF58FB>) |
| 8086:9d71 | 17aa:2243 | Intel            | Sunrise Point-LP HD Audio            | 17    | snd_hda... | [BA288E243C](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCS06N0D/45C0E5B583E8/NIXOS-24.05/6.6.66/X86_64/BA288E243C>) |
| 10de:2291 | 1043:1c42 | Nvidia           | GA107 High Definition Audio Contr... | 16    | snd_hda... | [0A76D54F2A](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZE_GZ301ZE/E93163333EB2/UBUNTUSTUDIO-24.10/6.11.0-9-GENERIC/X86_64/0A76D54F2A>) |
| 1022:15e3 | 10ec:0000 | AMD              | Family 17h/19h/1ah HD Audio Contr... | 14    | snd_hda... | [F51B8777E8](<Tablet/ONE-NETBOOK TECHNOLOGY/ONE/ONE XPLAYER/B1E0FDA01E2B/CHIMERAOS-46-2/6.9.12-CHOS7-CHIMERAOS-1/X86_64/F51B8777E8>) |
| 8086:3198 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 14    | snd_hda... | [1827AD6649](<Tablet/Microsoft/Surface/Surface Laptop SE/3C3B6159F009/ZORIN-17/6.8.0-49-GENERIC/X86_64/1827AD6649>) |
| 8086:3198 | 17aa:3811 | Intel            | Celeron/Pentium Silver Processor ... | 13    | snd_hda... | [5DAD085952](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 10IGL5 82AT/F87C264A0B49/FEDORA-40/6.11.4-201.FC40.X86_64/X86_64/5DAD085952>) |
| 8086:9d71 | 1028:07a4 | Intel            | Sunrise Point-LP HD Audio            | 13    | snd_hda... | [9BDEF7697E](<Tablet/Dell/Latitude/Latitude 5285/03AE783826C3/ZORIN-17/6.8.0-45-GENERIC/X86_64/9BDEF7697E>) |
| 8086:a0c8 | 1028:0a45 | Intel            | Tiger Lake-LP Smart Sound Technol... | 13    | snd_hda... | [88D7EDA3A3](<Tablet/Dell/Latitude/Latitude 7320 Detachable/2FA880CABA50/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/88D7EDA3A3>) |
| 8086:51c8 | 8086:7270 | Intel            | Alder Lake PCH-P High Definition ... | 12    | snd_hda... | [E6F037A5E8](<Tablet/Microsoft/Surface/Surface Pro 9/9EE1E883AC5A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E6F037A5E8>) |
| 8086:a0c8 | 17aa:508b | Intel            | Tiger Lake-LP Smart Sound Technol... | 12    | snd_hda... | [57D1EC52E3](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UW0013US/9FE17438E905/DEBIAN-12/6.1.0-27-AMD64/X86_64/57D1EC52E3>) |
| 1002:15de | 1002:15de | AMD              | Raven/Raven2/Fenghuang HDMI/DP Au... | 11    | snd_hda... | [B575C6A898](<Tablet/ayn/Loki/Loki Zero/D5E63EAE79B0/BAZZITE-40/6.9.12-205.FSYNC.FC40.X86_64/X86_64/B575C6A898>) |
| 1022:15e3 | 1f75:0201 | AMD              | Family 17h/19h/1ah HD Audio Contr... | 11    | snd_hda... | [2183EB76B7](<Tablet/ONE-NETBOOK/ONEXPLAYER/ONEXPLAYER Mini Pro/F55453A23AA1/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/2183EB76B7>) |
| 8086:9d70 | 17aa:2241 | Intel            | Sunrise Point-LP HD Audio            | 11    | snd_hda... | [047961B6D0](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/7D7EF3298D39/FEDORA-41/6.12.5-200.FC41.X86_64/X86_64/047961B6D0>) |
| 8086:9d71 | 103c:8414 | Intel            | Sunrise Point-LP HD Audio            | 11    | snd_hda... | [A1F8F4C528](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/92E2795CC5F7/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/A1F8F4C528>) |
| 8086:9d71 | 10f7:8338 | Intel            | Sunrise Point-LP HD Audio            | 11    | snd_hda... | [FAF64BB8A0](<Tablet/Panasonic/CF-33/CF-33-1/71D2DD20CB26/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/FAF64BB8A0>) |
| 8086:9d71 | 144d:c14f | Intel            | Sunrise Point-LP HD Audio            | 11    | snd_hda... | [EBD4E47906](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/EBD4E47906>) |
| 8086:9d71 | 17aa:380c | Intel            | Sunrise Point-LP HD Audio            | 11    | snd_hda... | [00DE3D7E4C](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/248F2E7667A2/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/00DE3D7E4C>) |
| 8086:a0c8 | 1ec9:3e44 | Intel            | Tiger Lake-LP Smart Sound Technol... | 11    | snd_hda... | [2D0F2950BA](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/DFD066B5B806/FEDORA-41/6.11.7-300.FC41.X86_64/X86_64/2D0F2950BA>) |
| 1022:15e3 | 1f66:0101 | AMD              | Family 17h/19h/1ah HD Audio Contr... | 10    | snd_hda... | [811AF91E75](<Tablet/AYANEO/2/2/959EFBE7A1CC/STEAMOS-20241225.0928/6.12.6-2/X86_64/811AF91E75>) |
| 8086:3198 | 02f3:f000 | Intel            | Celeron/Pentium Silver Processor ... | 10    | snd_hda... | [F9C62EB2B3](<Tablet/LTD Delovoy Office/EVE/EVE 1494E ES1280EW/E66E92B5050A/ULTRAMARINE-40/6.8.10-300.FC40.X86_64/X86_64/F9C62EB2B3>) |
| 8086:54c8 | 1e50:7038 | Intel            | Alder Lake-N PCH High Definition ... | 10    | snd_hda... | [2AF3E8F0C5](<Tablet/Chuwi/Hi10/Hi10 Max/73DD33C3A827/ALT-11.0/6.12.6-6.12-ALT1/X86_64/2AF3E8F0C5>) |
| 8086:5a98 | 1025:1209 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 10    | snd_hda... | [E7FE09D066](<Tablet/Acer/Switch/Switch SW312-31/FE82CC5F52F1/OPENMANDRIVA-23.08/6.4.11-DESKTOP-1OMV2390/X86_64/E7FE09D066>) |
| 8086:a0c8 | 17aa:3820 | Intel            | Tiger Lake-LP Smart Sound Technol... | 10    | snd_hda... | [AF8A5DF7BE](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/4236AA030B1D/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/AF8A5DF7BE>) |

### Storage (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:54ff | 17aa:3831 | Intel            | Alder Lake-N Universal Flash Stor... | 3     | ufshcd     | [EFDBD13C32](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 11IAN8 82XK/EAC815E6BF54/UBUNTU-24.04/6.8.0-1005-OEM/X86_64/EFDBD13C32>) |
| 8086:54ff |           | Intel            | Alder Lake-N Universal Flash Stor... | 2     | ufshcd     | [5818AF4069](<Tablet/ASUSTek Computer/Vivobook/Vivobook Slate T3304GA_T3304GA/5E90379EE4A3/VANILLA-2.0/6.11.6-AMD64/X86_64/5818AF4069>) |
| 8086:54ff | 8086:7270 | Intel            | Alder Lake-N Universal Flash Stor... | 1     | ufshcd_pci | [DE1603934E](<Tablet/Microsoft/Surface/Surface Go 4/EB7135250A70/OPENMANDRIVA-24.07/6.9.7-DESKTOP-1OMV2490/X86_64/DE1603934E>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9c03 | 1414:9c03 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 149   | ahci       | [BB626D70B0](<Tablet/Microsoft/Surface/Surface Pro 3/217C1E4144F1/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/BB626D70B0>) |
| 8086:31e3 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 86    | ahci       | [026269E60B](<Tablet/Others/Others/Others/B4F90A2AAF5D/LINUXMINT-22/6.8.0-50-GENERIC/X86_64/026269E60B>) |
| 8086:5ae3 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 56    | ahci       | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:0f23 | 1019:99a5 | Intel            | Atom Processor E3800 Series SATA ... | 27    | ahci       | [DA6CE4B361](<Tablet/BANGHO/Suma/Suma 1025/DF80AD331B24/ZORIN-17/6.8.0-49-GENERIC/X86_64/DA6CE4B361>) |
| 8086:1e03 | 1414:1e03 | Intel            | 7 Series Chipset Family 6-port SA... | 21    | ahci       | [09BDD29B6C](<Tablet/Microsoft/Surface/Surface Pro 2/DD2937B6F574/VANILLA-2.0/6.11.6-AMD64/X86_64/09BDD29B6C>) |
| 8086:9d03 | 17aa:384d | Intel            | Sunrise Point-LP SATA Controller ... | 21    | ahci       | [C14BE2A0FF](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/A8FA91459A71/ZORIN-17/6.8.0-40-GENERIC/X86_64/C14BE2A0FF>) |
| 1002:4391 | 1025:0577 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 19    | ahci       | [AC15CCA834](<Tablet/Acer/Iconia/Iconia Tab W500/00630A96A0A7/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/AC15CCA834>) |
| 8086:9d03 | 10f7:8338 | Intel            | Sunrise Point-LP SATA Controller ... | 12    | ahci       | [FAF64BB8A0](<Tablet/Panasonic/CF-33/CF-33-1/71D2DD20CB26/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/FAF64BB8A0>) |
| 8086:9d03 | 144d:c14f | Intel            | Sunrise Point-LP SATA Controller ... | 11    | ahci       | [EBD4E47906](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/EBD4E47906>) |
| 8086:9d03 | 17aa:383e | Intel            | Sunrise Point-LP SATA Controller ... | 11    | ahci       | [00DE3D7E4C](<Tablet/Lenovo/MIIX/MIIX 510-12IKB 80XE/248F2E7667A2/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/00DE3D7E4C>) |
| 8086:9d03 | 103c:828b | Intel            | Sunrise Point-LP SATA Controller ... | 10    | ahci       | [567E4C6343](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/53B866CA15BB/ZORIN-17/6.8.0-45-GENERIC/X86_64/567E4C6343>) |
| 8086:9d03 | 103c:82ca | Intel            | Sunrise Point-LP SATA Controller ... | 10    | ahci       | [75E354C291](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/E70BC33C4084/FEDORA-41/6.11.5-300.FC41.X86_64/X86_64/75E354C291>) |
| 8086:9d03 | 1028:081d | Intel            | Sunrise Point-LP SATA Controller ... | 9     | ahci       | [20E6DC4833](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/069C27C420D3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.12.6-1-DEFAULT/X86_64/20E6DC4833>) |
| 8086:4dd3 |           | Intel            | Jasper Lake SATA AHCI Controller     | 8     | ahci       | [E83E0E4EFA](<Tablet/RuggedPC/RuggedBookJ/RuggedBookJ61/3077AC07A524/FEDORA-40/6.11.3-200.FC40.X86_64/X86_64/E83E0E4EFA>) |
| 8086:9c83 | 17aa:222b | Intel            | Wildcat Point-LP SATA Controller ... | 8     | ahci       | [DABF58331D](<Tablet/Lenovo/ThinkPad/ThinkPad Helix 2nd 20CGCTO1WW/C514BF421B7F/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/DABF58331D>) |
| 8086:9d03 | 1025:111e | Intel            | Sunrise Point-LP SATA Controller ... | 8     | ahci       | [E68A5B419E](<Tablet/Acer/Switch/Switch SA5-271/8143477D8A59/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/E68A5B419E>) |
| 8086:9d03 | 1028:06e6 | Intel            | Sunrise Point-LP SATA Controller ... | 8     | ahci       | [31A3C7AF1E](<Tablet/Dell/Latitude/Latitude 5175/CD1C9C82C174/FEDORA-41/6.11.11-300.FC41.X86_64/X86_64/31A3C7AF1E>) |
| 8086:9d03 | 144d:c135 | Intel            | Sunrise Point-LP SATA Controller ... | 8     | ahci       | [F27DFBBBFB](<Tablet/Samsung Electronics/Galaxy/Galaxy Book 12/FDC421BFCB03/FEDORA-40/6.11.3-200.FC40.X86_64/X86_64/F27DFBBBFB>) |
| 8086:0f23 | 1019:99a1 | Intel            | Atom Processor E3800 Series SATA ... | 7     | ahci       | [0AC4B868CB](<Tablet/Medion/P/P2212T/1CC59B4B188A/FEDORA-40/6.9.5-200.FC40.X86_64/X86_64/0AC4B868CB>) |
| 8086:31e3 | 8086:31e3 | Intel            | Celeron/Pentium Silver Processor ... | 7     | ahci       | [63FD3737DE](<Tablet/Tactus/GeoPad/GeoPad 110/0F02FAE679C1/ZORIN-17/6.5.0-35-GENERIC/X86_64/63FD3737DE>) |
| 8086:5ae3 | 8086:5ae3 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 7     | ahci       | [4D20F47175](<Tablet/ZoomSmart/A/A8006/BE4A5F803E00/ROSA-12.4/5.15.117-GENERIC-1ROSA2021.1-X86_64/X86_64/4D20F47175>) |
| 8086:9d03 | 17aa:3827 | Intel            | Sunrise Point-LP SATA Controller ... | 7     | ahci       | [F5A5189E2A](<Tablet/Lenovo/MIIX/MIIX 510-12ISK 80U1/1940EF4E595D/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.11.8-1-DEFAULT/X86_64/F5A5189E2A>) |
| 8086:9d03 | 8086:9d03 | Intel            | Sunrise Point-LP SATA Controller ... | 7     | ahci       | [80F7F9C98A](<Tablet/RuggedPC/RuggedPadY/RuggedPadY22/665AAC6AB368/UBUNTU-MATE-22.04/6.2.0-39-GENERIC/X86_64/80F7F9C98A>) |
| 8086:4dd3 | 8086:7270 | Intel            | Jasper Lake SATA AHCI Controller     | 6     | ahci       | [7780E6CD50](<Tablet/DERE/Others/Others/D328C1D92331/KUBUNTU-23.04/6.2.0-39-GENERIC/X86_64/7780E6CD50>) |
| 8086:9c03 | 8086:7270 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 6     | ahci       | [52FB0884A3](<Tablet/Lenovo/MIIX/MIIX 2 11 20327/735EB204853B/ZORIN-17/6.8.0-40-GENERIC/X86_64/52FB0884A3>) |
| 8086:9d03 | 17aa:2241 | Intel            | Sunrise Point-LP SATA Controller ... | 6     | ahci       | [E932F6C04D](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GG001KUS/C7BF93D9464E/POP!_OS-22.04/6.8.0-76060800DAILY20240311-GENERIC/X86_64/E932F6C04D>) |
| 8086:9d03 | 1028:06d6 | Intel            | Sunrise Point-LP SATA Controller ... | 5     | ahci       | [FDEBA04A06](<Tablet/Dell/Latitude/Latitude 7275/63AAFB074631/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/FDEBA04A06>) |
| 8086:9d03 | 1028:07a4 | Intel            | Sunrise Point-LP SATA Controller ... | 5     | ahci       | [C39DE3B4A0](<Tablet/Dell/Latitude/Latitude 5285/313DBFB261E2/FEDORA-40/6.10.10-350.VANILLA.FC40.X86_64/X86_64/C39DE3B4A0>) |
| 8086:9d03 | 19e5:3e00 | Intel            | Sunrise Point-LP SATA Controller ... | 5     | ahci       | [B1081AA326](<Tablet/HUAWEI/MateBook/MateBook HZ-W09/6BBFC8BC312B/ZORIN-17/6.5.0-35-GENERIC/X86_64/B1081AA326>) |
| 8086:9d03 | 103c:8414 | Intel            | Sunrise Point-LP SATA Controller ... | 4     | ahci       | [3428068151](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/1ECF6C0DA234/FEDORA-40/6.11.3-200.FC40.X86_64/X86_64/3428068151>) |
| 8086:9d03 | 1043:13c0 | Intel            | Sunrise Point-LP SATA Controller ... | 4     | ahci       | [503D57F0A5](<Tablet/ASUSTek Computer/T303/T303UA/946329037C37/UBUNTU-22.04/6.5.0-18-GENERIC/X86_64/503D57F0A5>) |
| 8086:9d03 | 1043:1410 | Intel            | Sunrise Point-LP SATA Controller ... | 4     | ahci       | [6A0B2C7D45](<Tablet/ASUSTek Computer/T305/T305CA/B85AFA7C6015/FEDORA-39/6.7.4-200.FC39.X86_64/X86_64/6A0B2C7D45>) |
| 8086:9d03 | 1043:16c0 | Intel            | Sunrise Point-LP SATA Controller ... | 4     | ahci       | [6563B69541](<Tablet/ASUSTek Computer/T304/T304UA/6F8CE3816A91/KDE-NEON-24.04/6.8.0-50-GENERIC/X86_64/6563B69541>) |
| 8086:0f23 | 8086:7270 | Intel            | Atom Processor E3800 Series SATA ... | 3     | ahci       | [198C15E90A](<Tablet/System Mfg/Others/Others/AF6F46232DB6/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/198C15E90A>) |
| 1022:7901 | 1022:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 2     | ahci       | [B575C6A898](<Tablet/ayn/Loki/Loki Zero/D5E63EAE79B0/BAZZITE-40/6.9.12-205.FSYNC.FC40.X86_64/X86_64/B575C6A898>) |
| 1b21:0612 | 1b21:1060 | ASMedia Techn... | ASM1061/ASM1062 Serial ATA Contro... | 2     | ahci       | [5F97496A76](<Tablet/retsamarret/000/000-F4423-FBA004-2000-N/371AE0288EED/NIXOS-23.11/6.1.58/X86_64/5F97496A76>) |
| 8086:0f23 | 1509:7018 | Intel            | Atom Processor E3800 Series SATA ... | 2     | ahci       | [9347717861](<Tablet/Xplore/iX101/iX101B1/988A604FB8AB/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/9347717861>) |
| 8086:0f23 | 1854:0211 | Intel            | Atom Processor E3800 Series SATA ... | 2     | ahci       | [44AF16AC16](<Tablet/LG Electronics/15U340/15U340-L.BK55P1/96572D02BF5F/LINUXMINT-20/5.4.0-42-GENERIC/X86_64/44AF16AC16>) |
| 8086:1e03 | 10f7:8338 | Intel            | 7 Series Chipset Family 6-port SA... | 2     | ahci       | [06F11C0449](<Tablet/Panasonic/FZ-G1/FZ-G1ASH39E3/6F2FB083615E/ELEMENTARY-6/5.11.0-37-GENERIC/X86_64/06F11C0449>) |
| 8086:9d03 | 1025:122b | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [46ECB88F1D](<Tablet/Acer/Switch/Switch SW713-51GNP/3C0AE30715BA/NIXOS-22.11/6.1.9/X86_64/46ECB88F1D>) |
| 8086:9d03 | 17aa:2243 | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [B3223F3163](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCA02AJP/DB0837ED9475/UBUNTU-24.04/6.8.0-35-GENERIC/X86_64/B3223F3163>) |
| 8086:9d03 | 17aa:3831 | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [4684DBCC91](<Tablet/Lenovo/MIIX/MIIX 720-12IKB 80VV/E890E1333285/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/4684DBCC91>) |
| 8086:9d03 | 1b0a:01d3 | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [60C93DDC01](<Tablet/Xplore/iX125/iX125R1/9DCB305AD004/PUPPY_IMPPUP64-9.6.1/5.15.11-LXPUP64/X86_64/60C93DDC01>) |
| 1c28:0122 | 1b4b:9183 | Lite-On IT Co... | M6e PCI Express SSD [Marvell 88SS... | 1     | ahci       | [568757F9F8](<Tablet/Dell/Latitude/Latitude 5285/9BC7EC024B34/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/568757F9F8>) |
| 8086:0f23 | 1558:5470 | Intel            | Atom Processor E3800 Series SATA ... | 1     | ahci       | [DD65C5ABF7](<Tablet/Lanix/Neuron/Neuron A/9C81E684C8A4/ARCH-ROLLING/5.8.14-ARCH1-1/X86_64/DD65C5ABF7>) |
| 8086:1e03 | 1b0a:017b | Intel            | 7 Series Chipset Family 6-port SA... | 1     | ahci       | [5A97B2A1A7](<Tablet/Wacom/Citiq/Citiq Companion/47415E406255/LINUXMINT-19.2/5.0.0-27-GENERIC/X86_64/5A97B2A1A7>) |
| 8086:22a3 | 1854:0230 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | ahci       | [15040C5EF1](<Tablet/LG Electronics/14U360/14U360-L.AJ12B6/AB26612096A1/UBUNTU-22.04/6.2.0-37-GENERIC/X86_64/15040C5EF1>) |
| 8086:22a3 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | ahci       | [009BEE9446](<Tablet/Intel/Braswell/Braswell Platform/1E35D60EBB32/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/009BEE9446>) |
| 8086:27c1 | 14c0:006c | Intel            | NM10/ICH7 Family SATA Controller ... | 1     | ahci       | [8FF8AE3115](<Tablet/Motion Computing/CL/CL910/CC59C0B6971E/LINUXMINT-19.3/5.4.0-42-GENERIC/I686/8FF8AE3115>) |
| 8086:5ae3 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | ahci       | [49D345EC0B](<Tablet/Xplore/iX101/iX101L1/1592B2F5F479/UBUNTU-20.04/5.6.0-1028-OEM/X86_64/49D345EC0B>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c01 | 10f7:8338 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ata_piix   | [50E0A85FD3](<Tablet/Panasonic/CF-H2/CF-H2BJJHZDE/E17482358B17/LMDE-5/5.10.0-13-AMD64/X86_64/50E0A85FD3>) |
| 8086:1c09 | 10f7:8338 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ata_piix   | [50E0A85FD3](<Tablet/Panasonic/CF-H2/CF-H2BJJHZDE/E17482358B17/LMDE-5/5.10.0-13-AMD64/X86_64/50E0A85FD3>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 150   | nvme       | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 1c5c:1327 | 1c5c:0000 | SK hynix         | BC501 NVMe Solid State Drive         | 141   | nvme       | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 1179:0113 | 1179:0001 | Toshiba Ameri... | BG3 x2 NVMe SSD Controller (DRAM-... | 111   | nvme       | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 1e0f:0001 | 1e0f:0001 | KIOXIA           | NVMe SSD Controller BG4 (DRAM-less)  | 105   | nvme       | [2EA57D017C](<Tablet/Microsoft/Surface/Surface Go 3/7C9D6824082F/UBUNTU-24.04/6.9.3-SURFACE-2/X86_64/2EA57D017C>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 97    | nvme       | [EAF1BB652C](<Tablet/Microsoft/Surface/Surface Book 2/B870A7627396/ARCH-ROLLING/6.12.7-ARCH1-1-NSB2/X86_64/EAF1BB652C>) |
| 144d:a806 | 144d:a801 | Samsung Elect... | NVMe SSD SM0032L                     | 74    | nvme       | [C9024275E0](<Tablet/Microsoft/Surface/Surface Pro/F31CC379A03C/UBUNTU-24.04/6.10.10-SURFACE-1/X86_64/C9024275E0>) |
| 1179:010f | 1179:0001 | Toshiba Ameri... | XG3 NVMe SSD Controller              | 33    | nvme       | [15EBC4270F](<Tablet/Microsoft/Surface/Surface Pro 4/69C4796592E0/ZORIN-17/6.8.0-45-GENERIC/X86_64/15EBC4270F>) |
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 29    | nvme       | [AAB1A2C43E](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJ001BUS/1A6AAAB15025/UBUNTU-24.10/6.11.0-13-GENERIC/X86_64/AAB1A2C43E>) |
| 1179:0116 | 1179:0001 | Toshiba Ameri... | XG5 NVMe SSD Controller              | 26    | nvme       | [F0D42DF827](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/0C327DDF3EC7/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/F0D42DF827>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980 (DRAM-less)  | 26    | nvme       | [DA3534B096](<Tablet/Microsoft/Surface/Surface Pro 7+/87B1E5086B44/DEBIAN-12/6.1.0-28-AMD64/X86_64/DA3534B096>) |
| 1c5c:174a | 1c5c:174a | SK hynix         | Gold P31/BC711/PC711 NVMe Solid S... | 26    | nvme       | [BA288E243C](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCS06N0D/45C0E5B583E8/NIXOS-24.05/6.6.66/X86_64/BA288E243C>) |
| 1c5c:1527 | 1c5c:1527 | SK hynix         | PC401 NVMe Solid State Drive 256GB   | 24    | nvme       | [58861DC8F9](<Tablet/Microsoft/Surface/Surface Book 2/94F3ABD37803/ZORIN-17/6.8.0-45-GENERIC/X86_64/58861DC8F9>) |
| 1344:5413 | 1344:1100 | Micron Techno... | 2400 NVMe SSD (DRAM-less)            | 21    | nvme       | [6F1320DB5C](<Tablet/ASUSTek Computer/ROG/ROG Ally RC71L_RC71L/615679BE41C6/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/6F1320DB5C>) |
| 8086:f1a5 | 8086:390a | Intel            | SSD 600P Series                      | 21    | nvme       | [E30F026FAC](<Tablet/Microsoft/Surface/Surface Pro/5D1B150D0A95/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/E30F026FAC>) |
| 2646:501b | 2646:501b | Kingston Tech... | OM8PGP4 NVMe PCIe SSD (DRAM-less)    | 18    | nvme       | [0BC6665145](<Tablet/Micro Computer (HK) Tech Limited/V/V3/F17AC0C7E80F/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/0BC6665145>) |
| 1344:5411 | 1344:2100 | Micron Techno... | 2450 NVMe SSD [HendrixV] (DRAM-less) | 14    | nvme       | [91717BA12B](<Tablet/Dell/XPS/XPS 13 9315 2-in-1/1EF842C3A2C1/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/91717BA12B>) |
| 15b7:5017 | 15b7:5017 | SanDisk          | WD Black SN770 / PC SN740 256GB /... | 14    | nvme       | [DE52972775](<Tablet/ASUSTek Computer/ASUS/ASUS Zenbook Duo UX8406MA_UX8406MA/8A069640761E/ZORIN-17/6.8.0-50-GENERIC/X86_64/DE52972775>) |
| 15b7:5015 | 15b7:5015 | Sandisk          | PC SN740 NVMe SSD (DRAM-less)        | 12    | nvme       | [88D7EDA3A3](<Tablet/Dell/Latitude/Latitude 7320 Detachable/2FA880CABA50/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/88D7EDA3A3>) |
| 15b7:5016 | 15b7:5016 | Sandisk          | WD PC SN740 NVMe SSD 512GB (DRAM-... | 12    | nvme       | [498786C044](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/DAAFD9B673D6/BAZZITE-41/6.11.10-304.BAZZITE.FC41.X86_64/X86_64/498786C044>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013-E13 PCIe3 NVMe Controller ... | 12    | nvme       | [F51B8777E8](<Tablet/ONE-NETBOOK TECHNOLOGY/ONE/ONE XPLAYER/B1E0FDA01E2B/CHIMERAOS-46-2/6.9.12-CHOS7-CHIMERAOS-1/X86_64/F51B8777E8>) |
| 1987:5021 | 1987:5021 | Phison Electr... | PS5021-E21 PCIe4 NVMe Controller ... | 12    | nvme       | [D8B0DBE711](<Tablet/Microsoft/Surface/Surface Laptop Go/F491C595F80D/ARCH-ROLLING/6.12.7-ZEN1-1-ZEN/X86_64/D8B0DBE711>) |
| 1179:011a | 1179:0001 | Toshiba Ameri... | XG6 NVMe SSD Controller              | 11    | nvme       | [ADAF073B87](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/C888DD06D570/FEDORA-40/6.9.4-200.FC40.X86_64/X86_64/ADAF073B87>) |
| 15b7:5007 | 15b7:5007 | SanDisk          | IX SN530 NVMe SSD (DRAM-less)        | 11    | nvme       | [E6F037A5E8](<Tablet/Microsoft/Surface/Surface Pro 9/9EE1E883AC5A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E6F037A5E8>) |
| 1dee:5216 | 1dee:5216 | Biwin Storage... | KingSpec NX series NVMe SSD (DRAM... | 11    | nvme       | [2183EB76B7](<Tablet/ONE-NETBOOK/ONEXPLAYER/ONEXPLAYER Mini Pro/F55453A23AA1/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/2183EB76B7>) |
| 1e4b:1202 | 1e4b:1202 | MAXIO Technol... | NVMe SSD Controller MAP1202 (DRAM... | 11    | nvme       | [2AF3E8F0C5](<Tablet/Chuwi/Hi10/Hi10 Max/73DD33C3A827/ALT-11.0/6.12.6-6.12-ALT1/X86_64/2AF3E8F0C5>) |
| 8086:f1a6 | 8086:390b | Intel            | SSD DC P4101/Pro 7600p/760p/E 610... | 10    | nvme       | [83F266708A](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/6EA5BFBBECD8/FEDORA-40/6.10.3-200.FC40.X86_64/X86_64/83F266708A>) |
| 1d97:1602 | 1d97:1602 | Shenzhen Long... | Lexar NM790 NVME SSD (DRAM-less)     | 9     | nvme       | [811AF91E75](<Tablet/AYANEO/2/2/959EFBE7A1CC/STEAMOS-20241225.0928/6.12.6-2/X86_64/811AF91E75>) |
| 1c5c:1339 | 1c5c:0000 | SK hynix         | BC511 NVMe SSD                       | 8     | nvme       | [657C7CAF3D](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/B6F2D71B615A/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/657C7CAF3D>) |
| 1344:5411 | 1344:1100 | Micron Techno... | 2450 NVMe SSD [HendrixV] (DRAM-less) | 7     | nvme       | [73ED774ED4](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZA_GZ301ZA/FC618DEF962D/MANJARO/6.10.3-MANJAR1/X86_64/73ED774ED4>) |
| 15b7:5009 | 15b7:5009 | SanDisk          | Ultra 3D / WD PC SN530, IX SN530,... | 7     | nvme       | [E7DB77A1CE](<Tablet/Fujitsu/STYLISTIC/STYLISTIC Q7310/33C6B5DEF022/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/E7DB77A1CE>) |
| 144d:a80b | 144d:a80b | Samsung Elect... | NVMe SSD Controller PM9B1 (DRAM-l... | 6     | nvme       | [13716B091E](<Tablet/Microsoft/Surface/Surface Laptop Go 3/B9C569F80F17/FEDORA-40/6.10.12-200.FC40.X86_64/X86_64/13716B091E>) |
| 15b7:5004 | 15b7:5004 | SanDisk          | PC SN520 x2 M.2 2230 NVMe SSD        | 6     | nvme       | [5A15B249A5](<Tablet/Hewlett-Packard/Tablet/Tablet 11m-be0xxx/442C1D1B1DB4/FEDORA-41/6.11.0-63.FC41.X86_64/X86_64/5A15B249A5>) |
| 15b7:5008 | 15b7:5008 | SanDisk          | PC SN530 NVMe SSD (DRAM-less)        | 6     | nvme       | [25B2CD256F](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UW006RUS/EE9A174A21FB/FEDORA-40/6.9.4-200.FC40.X86_64/X86_64/25B2CD256F>) |
| 1e0f:000c | 1e0f:0001 | KIOXIA           | NVMe SSD Controller BG5 (DRAM-less)  | 6     | nvme       | [2EBDE0820D](<Tablet/MSI/Claw/Claw A1M/E9FB50149AEE/STEAMOS-ROLLING/6.11.1-1/X86_64/2EBDE0820D>) |
| 1e4b:1602 | 1e4b:1602 | MAXIO Technol... | NVMe SSD Controller MAP1602 (DRAM... | 6     | nvme       | [4A55769E54](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/A1BDD5915B5A/BAZZITE-41/6.11.9-303.BAZZITE.FC41.X86_64/X86_64/4A55769E54>) |
| 126f:1001 | 126f:2262 | Silicon Motion   | Non-Volatile memory controller       | 5     | nvme       | [B663CED92D](<Tablet/HUAWEI/DRC-WXX/DRC-WXX/996049F82306/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/B663CED92D>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT (DRAM-less) NVM... | 5     | nvme       | [0BD93DC5E1](<Tablet/Star Labs/StarLite/StarLite/C7AC4F3EB91D/KDE-NEON-22.04/6.8.0-40-GENERIC/X86_64/0BD93DC5E1>) |
| 1c5c:1d59 | 1c5c:1d59 | SK hynix         | BC901 NVMe Solid State Drive (DRA... | 5     | nvme       | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 1179:0115 | 1179:0001 | Toshiba Ameri... | XG4 NVMe SSD Controller              | 4     | nvme       | [0FD89EC85A](<Tablet/Dell/Latitude/Latitude 7275/55EB4B609DF6/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/0FD89EC85A>) |
| 1344:5413 | 1344:2100 | Micron Techno... | 2400 NVMe SSD (DRAM-less)            | 4     | nvme       | [E35C79DDE2](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301VU_GZ301VU/2F999BBF1AC8/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/E35C79DDE2>) |
| 15b7:5026 | 15b7:5026 | Sandisk          | WD PC SN735 NVMe SSD 1TB (DRAM-less) | 4     | nvme       | [9E216696E0](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZC_GZ301ZC/5AC295558513/KALI-2024.2/6.6.9-AMD64/X86_64/9E216696E0>) |
| 2646:500f | 2646:500f | Kingston Tech... | NV1 NVMe SSD [SM2263XT] (DRAM-less)  | 4     | nvme       | [C14BE2A0FF](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/A8FA91459A71/ZORIN-17/6.8.0-40-GENERIC/X86_64/C14BE2A0FF>) |
| c0a9:540a | c0a9:5021 | Micron/Crucia... | P2 [Nick P2] / P3 / P3 Plus NVMe ... | 4     | nvme       | [A09E8B0E7B](<Tablet/GPD/G1618/G1618-04/DC5F4D01ABCF/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/A09E8B0E7B>) |
| 10ec:5765 | 10ec:5765 | Realtek Semic... | RTS5765DL NVMe SSD Controller (DR... | 3     | nvme       | [3CA2E47B48](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/F28751AA77AA/KALI-2024.4/6.11.2-AMD64/X86_64/3CA2E47B48>) |
| 1344:5410 | 1344:0100 | Micron Techno... | 2200S NVMe SSD [Cassandra]           | 3     | nvme       | [5214D7970E](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/66949842BD8A/KALI-2024.1/6.6.9-AMD64/X86_64/5214D7970E>) |
| 144d:a80a | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 3     | nvme       | [DC4244CAAE](<Tablet/Microsoft/Surface/Surface Laptop Studio 2/442DCC14A3B5/DEBIAN-12/6.9.3-SURFACE-2/X86_64/DC4244CAAE>) |
| 15b7:5030 | 15b7:5030 | Sandisk          | WD Black SN850X NVMe SSD             | 3     | nvme       | [4A110CBE5E](<Tablet/AYANEO/GEEK/GEEK/2C6AA4940FA2/CACHYOS-ROLLING/6.12.1-2-CACHYOS-DECKIFY-LTO/X86_64/4A110CBE5E>) |
| 15b7:5042 | 15b7:5042 | Sandisk          | WD Black SN770M NVMe SSD (DRAM-less) | 3     | nvme       | [C3E2A3C803](<Tablet/Microsoft/Surface/Surface Pro 8/F38239038177/GARUDA-ROLLING/6.10.10-ZEN1-1-ZEN/X86_64/C3E2A3C803>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 3     | nvme       | [12499C1F9E](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/6D0FC2F85F21/FEDORA-39/6.6.9-200.FC39.X86_64/X86_64/12499C1F9E>) |
| 1cc4:6201 | 1cc4:1cc4 | Union Memory ... | AM620 PCIe 3.0 NVMe SSD 128GB        | 3     | nvme       | [B359E67D9E](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 5 12IAU7 82TQ/26D6905F63F4/FEDORA-40/6.8.6-300.FC40.X86_64/X86_64/B359E67D9E>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:467f | 8086:0000 | Intel            | Volume Management Device NVMe RAI... | 21    | vmd        | [0A76D54F2A](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZE_GZ301ZE/E93163333EB2/UBUNTUSTUDIO-24.10/6.11.0-9-GENERIC/X86_64/0A76D54F2A>) |
| 8086:7d0b | 1043:1c43 | Intel            | Volume Management Device NVMe RAI... | 5     | vmd        | [DE52972775](<Tablet/ASUSTek Computer/ASUS/ASUS Zenbook Duo UX8406MA_UX8406MA/8A069640761E/ZORIN-17/6.8.0-50-GENERIC/X86_64/DE52972775>) |
| 8086:a77f | 8086:0000 | Intel            | Volume Management Device NVMe RAI... | 5     | vmd        | [63A4375691](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301VIC_GZ301VIC/C9818F24B41D/CACHYOS-ROLLING/6.11.7-1-CACHYOS/X86_64/63A4375691>) |
| 8086:9a0b | 1028:0a45 | Intel            | Volume Management Device NVMe RAI... | 4     | vmd        | [90B1049E2A](<Tablet/Dell/Latitude/Latitude 7320 Detachable/FC9FB9A34453/MANJARO/6.1.38-1-MANJARO/X86_64/90B1049E2A>) |
| 8086:282a | 1025:1171 | Intel            | 82801 Mobile SATA Controller [RAI... | 3     | ahci       | [7D44E4C760](<Tablet/Acer/Switch/Switch SW512-52/9061A4CB688E/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/7D44E4C760>) |
| 8086:467f | 1028:0b34 | Intel            | Volume Management Device NVMe RAI... | 3     | ahci, vmd  | [91717BA12B](<Tablet/Dell/XPS/XPS 13 9315 2-in-1/1EF842C3A2C1/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/91717BA12B>) |
| 8086:9a0b | 103c:870d | Intel            | Volume Management Device NVMe RAI... | 3     | vmd        | [1C35A7F11B](<Tablet/Hewlett-Packard/Elite/Elite x2 G8 Tablet/6D7618F54734/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/1C35A7F11B>) |
| 8086:282a | 17aa:3831 | Intel            | 82801 Mobile SATA Controller [RAI... | 2     | ahci       | [40771F27EC](<Tablet/Lenovo/MIIX/MIIX 720-12IKB 80VV/890D2C33C909/ROCKY-9.4/5.14.0-427.13.1.EL9_4.X86_64/X86_64/40771F27EC>) |
| 8086:282a | 1028:07a4 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [1717754347](<Tablet/Dell/Latitude/Latitude 5285/D75F67E269AD/UBUNTU-22.10/5.19.10-SURFACE/X86_64/1717754347>) |
| 8086:282a | 1028:07d3 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [2CA57FD969](<Tablet/Dell/Latitude/Latitude 7212 Rugged Extreme Tablet/CF5A809D78D0/FEDORA-39/6.7.4-200.FC39.X86_64/X86_64/2CA57FD969>) |
| 8086:282a | 8086:9d03 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [0F05F12004](<Tablet/Teclast/X5/X5 Pro/B130987D6E6A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0F05F12004>) |
| 8086:7d0b | 1462:143a | Intel            | Volume Management Device NVMe RAI... | 1     | vmd        | [2EBDE0820D](<Tablet/MSI/Claw/Claw A1M/E9FB50149AEE/STEAMOS-ROLLING/6.11.1-1/X86_64/2EBDE0820D>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1911 | 8086:2015 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 190   |            | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:09ab |           | Intel            | RST VMD Managed Controller           | 40    |            | [DE52972775](<Tablet/ASUSTek Computer/ASUS/ASUS Zenbook Duo UX8406MA_UX8406MA/8A069640761E/ZORIN-17/6.8.0-50-GENERIC/X86_64/DE52972775>) |
| 8086:1911 | 17aa:2244 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 25    |            | [454126AC6E](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KKS0S901/980E2F97C968/ARCH-ROLLING/6.12.6-ZEN1-1-ZEN/X86_64/454126AC6E>) |
| 8086:464f | 1043:1c42 | Intel            | 12th Gen Core Processor Gaussian ... | 24    |            | [0A76D54F2A](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZE_GZ301ZE/E93163333EB2/UBUNTUSTUDIO-24.10/6.11.0-9-GENERIC/X86_64/0A76D54F2A>) |
| 8086:15d2 | 2222:1111 | Intel            | JHL6540 Thunderbolt 3 NHI (C step... | 19    | thunder... | [454126AC6E](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KKS0S901/980E2F97C968/ARCH-ROLLING/6.12.6-ZEN1-1-ZEN/X86_64/454126AC6E>) |
| 8086:1911 | 17aa:2243 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 17    |            | [BA288E243C](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 2 20JCS06N0D/45C0E5B583E8/NIXOS-24.05/6.6.66/X86_64/BA288E243C>) |
| 8086:3190 | 17aa:3802 | Intel            | Celeron/Pentium Silver Processor ... | 17    |            | [9BE1FF58FB](<Tablet/Lenovo/IdeaPad/IdeaPad D330-10IGM 81MD/672E3FB63585/UBUNTU-24.04/6.8.0-38-GENERIC/X86_64/9BE1FF58FB>) |
| 8086:3190 | 17aa:380e | Intel            | Celeron/Pentium Silver Processor ... | 13    |            | [5DAD085952](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 10IGL5 82AT/F87C264A0B49/FEDORA-40/6.11.4-201.FC40.X86_64/X86_64/5DAD085952>) |
| 8086:464f | 8086:7270 | Intel            | 12th Gen Core Processor Gaussian ... | 12    |            | [E6F037A5E8](<Tablet/Microsoft/Surface/Surface Pro 9/9EE1E883AC5A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E6F037A5E8>) |
| 8086:9a11 | 17aa:508b | Intel            | GNA Scoring Accelerator module       | 12    |            | [57D1EC52E3](<Tablet/Lenovo/ThinkPad/ThinkPad X12 Detachable Gen 1 20UW0013US/9FE17438E905/DEBIAN-12/6.1.0-27-AMD64/X86_64/57D1EC52E3>) |
| 8086:15d2 | 103c:8414 | Intel            | JHL6540 Thunderbolt 3 NHI (C step... | 11    | thunder... | [A1F8F4C528](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/92E2795CC5F7/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/A1F8F4C528>) |
| 8086:1911 | 17aa:2241 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 11    |            | [047961B6D0](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet 20GGS02600/7D7EF3298D39/FEDORA-41/6.12.5-200.FC41.X86_64/X86_64/047961B6D0>) |
| 8086:9a11 | 1028:0a45 | Intel            | GNA Scoring Accelerator module       | 10    |            | [88D7EDA3A3](<Tablet/Dell/Latitude/Latitude 7320 Detachable/2FA880CABA50/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/88D7EDA3A3>) |
| 8086:9a11 | 17aa:382f | Intel            | GNA Scoring Accelerator module       | 10    |            | [AF8A5DF7BE](<Tablet/Lenovo/Yoga/Yoga Duet 7 13ITL6 82MA/4236AA030B1D/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/AF8A5DF7BE>) |
| 8086:15eb | 103c:85b9 | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 9     | thunder... | [C43E6E357D](<Tablet/Hewlett-Packard/Elite/Elite x2 G4/28B313198BDD/OPENSUSE-LEAP-15.6/6.4.0-150600.23.25-DEFAULT/X86_64/C43E6E357D>) |
| 8086:464f | 17aa:3839 | Intel            | 12th Gen Core Processor Gaussian ... | 9     |            | [F2B2FFBFFE](<Tablet/Lenovo/XiaoXinDuet/XiaoXinDuet IAU7 82TQ/5FF690C6ECBE/KYLIN-V10/6.8.0-45-GENERIC/X86_64/F2B2FFBFFE>) |
| 8086:7e4c | 1043:1c43 | Intel            | Meteor Lake-P Gaussian & Neural-N... | 9     |            | [DE52972775](<Tablet/ASUSTek Computer/ASUS/ASUS Zenbook Duo UX8406MA_UX8406MA/8A069640761E/ZORIN-17/6.8.0-50-GENERIC/X86_64/DE52972775>) |
| 8086:1911 | 8086:1911 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 8     |            | [80F7F9C98A](<Tablet/RuggedPC/RuggedPadY/RuggedPadY22/665AAC6AB368/UBUNTU-MATE-22.04/6.2.0-39-GENERIC/X86_64/80F7F9C98A>) |
| 8086:15eb | 1028:09ba | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 7     | thunder... | [657C7CAF3D](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/B6F2D71B615A/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/657C7CAF3D>) |
| 8086:1911 | 1028:09ba | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 7     |            | [657C7CAF3D](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/B6F2D71B615A/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/657C7CAF3D>) |
| 8086:1911 | 17aa:3883 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 6     |            | [BE1F1A236B](<Tablet/Lenovo/Yoga/Yoga Duet IML 2020 82E9/B664B47B9CE3/FEDORA-40/6.8.8-300.FC40.X86_64/X86_64/BE1F1A236B>) |
| 8086:467e | 8086:7270 | Intel            | Core i9/i7/i5/i3 System Peripheral   | 6     |            | [B6FE8E3FC9](<Tablet/Star Labs/StarLite/StarLite/7A06CE2A951A/ZORIN-17/6.8.0-49-GENERIC/X86_64/B6FE8E3FC9>) |
| 8086:a74f | 1043:1573 | Intel            | GNA Scoring Accelerator module       | 6     |            | [E35C79DDE2](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301VU_GZ301VU/2F999BBF1AC8/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/E35C79DDE2>) |
| 8086:4e11 | 8086:7270 | Intel            | Jasper Lake System Peripheral        | 5     |            | [7780E6CD50](<Tablet/DERE/Others/Others/D328C1D92331/KUBUNTU-23.04/6.2.0-39-GENERIC/X86_64/7780E6CD50>) |
| 8086:15d2 | 1028:08e9 | Intel            | JHL6540 Thunderbolt 3 NHI (C step... | 4     | thunder... | [8D53A4B7AB](<Tablet/Dell/Latitude/Latitude 7200 2-in-1/733991F40E18/MANJARO/6.9.0-1-MANJARO/X86_64/8D53A4B7AB>) |
| 8086:1911 | 1028:08e9 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 4     |            | [8D53A4B7AB](<Tablet/Dell/Latitude/Latitude 7200 2-in-1/733991F40E18/MANJARO/6.9.0-1-MANJARO/X86_64/8D53A4B7AB>) |
| 8086:464f | 1028:0b34 | Intel            | 12th Gen Core Processor Gaussian ... | 4     |            | [91717BA12B](<Tablet/Dell/XPS/XPS 13 9315 2-in-1/1EF842C3A2C1/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/91717BA12B>) |
| 8086:9a11 |           | Intel            | GNA Scoring Accelerator module       | 4     |            | [0BDD83D289](<Tablet/SHIFT/SHIFT13/SHIFT13mi/0FEB33EB190A/FEDORA-40/6.10.12-200.FC40.X86_64/X86_64/0BDD83D289>) |
| 8086:3190 | 17aa:2261 | Intel            | Celeron/Pentium Silver Processor ... | 3     |            | [CBFF1B04E0](<Tablet/Lenovo/Tablet/Tablet 10 20L3000RGE/BBF4DFDD3007/UBUNTU-23.10/6.5.0-15-GENERIC/X86_64/CBFF1B04E0>) |
| 8086:467e | 17aa:3808 | Intel            | Core i9/i7/i5/i3 System Peripheral   | 3     |            | [EFDBD13C32](<Tablet/Lenovo/IdeaPad/IdeaPad Duet 3 11IAN8 82XK/EAC815E6BF54/UBUNTU-24.04/6.8.0-1005-OEM/X86_64/EFDBD13C32>) |
| 8086:9a11 | 103c:870d | Intel            | GNA Scoring Accelerator module       | 3     |            | [1C35A7F11B](<Tablet/Hewlett-Packard/Elite/Elite x2 G8 Tablet/6D7618F54734/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/1C35A7F11B>) |
| 8086:1911 | 1b0a:01d3 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [60C93DDC01](<Tablet/Xplore/iX125/iX125R1/9DCB305AD004/PUPPY_IMPPUP64-9.6.1/5.15.11-LXPUP64/X86_64/60C93DDC01>) |
| 8086:464f | 17aa:2301 | Intel            | 12th Gen Core Processor Gaussian ... | 2     |            | [CF313FDFA9](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Fold 16 Gen 1 21ESCTO1WW/F09CE9BCB863/ARCH-ROLLING/6.10.10-ARCH1-1/X86_64/CF313FDFA9>) |
| 8086:464f | 1ec9:3e65 | Intel            | 12th Gen Core Processor Gaussian ... | 2     |            | [A19D185643](<Tablet/HUAWEI/DRR-WXX/DRR-WXX/C1EB6A918CD1/ALT-10.3/6.1.81-UN-DEF-ALT1/X86_64/A19D185643>) |
| 8086:467e | 1043:1713 | Intel            | Core i9/i7/i5/i3 System Peripheral   | 2     |            | [5818AF4069](<Tablet/ASUSTek Computer/Vivobook/Vivobook Slate T3304GA_T3304GA/5E90379EE4A3/VANILLA-2.0/6.11.6-AMD64/X86_64/5818AF4069>) |
| 8086:4e11 | 1043:1d02 | Intel            | Jasper Lake System Peripheral        | 2     |            | [1F850C6012](<Tablet/ASUSTek Computer/Vivobook/Vivobook Slate T3300KA_T3300KA/5E4B2F9BE565/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/1F850C6012>) |
| 8086:1193 |           | Intel            | System peripheral                    | 1     |            | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:1194 |           | Intel            | Merrifield Serial IO SPI Controller  | 1     | intel_m... | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:1199 |           | Intel            | Merrifield GPIO Controller           | 1     | langwel... | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:119b |           | Intel            | System peripheral                    | 1     | intel_m... | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:11a2 |           | Intel            | Merrifield Serial IO DMA Controller  | 1     | intel_m... | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:11a5 |           | Intel            | Merrifield Serial IO PWM Controller  | 1     | pwm_int... | [D1F5E15D8C](<Tablet/Intel/Merrifield/Merrifield/F7CC68FA4F16/ALPINE-3.12.0_RC1/3.10.98-POKY-EDISON+/I686/D1F5E15D8C>) |
| 8086:15d2 | 8086:0000 | Intel            | JHL6540 Thunderbolt 3 NHI (C step... | 1     | thunder... | [79847C1412](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/99D142FA3EDF/UBUNTU-22.04/6.2.0-32-GENERIC/X86_64/79847C1412>) |
| 8086:4e11 | 3100:0001 | Intel            | Jasper Lake System Peripheral        | 1     |            | [A59B175278](<Tablet/Dynabook/P1/P1-K2XP-TB/B2EA9AB5349F/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/A59B175278>) |
| 8086:7e4c | 1462:143a | Intel            | Meteor Lake-P Gaussian & Neural-N... | 1     |            | [2EBDE0820D](<Tablet/MSI/Claw/Claw A1M/E9FB50149AEE/STEAMOS-ROLLING/6.11.1-1/X86_64/2EBDE0820D>) |
| 8086:9a11 | 8086:7270 | Intel            | GNA Scoring Accelerator module       | 1     |            | [9C632DF9A1](<Tablet/Juniper Systems/Mesa/Mesa Pro/6FD4B0D409A4/UBUNTU-MATE-22.04/5.15.0-91-GENERIC/X86_64/9C632DF9A1>) |
| 8086:a74f | 1043:15b3 | Intel            | GNA Scoring Accelerator module       | 1     |            | [63A4375691](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301VIC_GZ301VIC/C9818F24B41D/CACHYOS-ROLLING/6.11.7-1-CACHYOS/X86_64/63A4375691>) |
| 8086:a74f | 1071:a125 | Intel            | GNA Scoring Accelerator module       | 1     |            | [CBCDE33E6C](<Tablet/Getac/K120/K120G3/834E85EFA531/OPENSUSE-LEAP-15.6/6.4.0-150600.23.7-DEFAULT/X86_64/CBCDE33E6C>) |
| 8086:a74f | 8086:7270 | Intel            | GNA Scoring Accelerator module       | 1     |            | [DC4244CAAE](<Tablet/Microsoft/Surface/Surface Laptop Studio 2/442DCC14A3B5/DEBIAN-12/6.9.3-SURFACE-2/X86_64/DC4244CAAE>) |

### Unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:31a2 | 17aa:2261 | Intel            | Celeron/Pentium Silver Processor ... | 3     | intel_i... | [CBFF1B04E0](<Tablet/Lenovo/Tablet/Tablet 10 20L3000RGE/BBF4DFDD3007/UBUNTU-23.10/6.5.0-15-GENERIC/X86_64/CBFF1B04E0>) |
| 8086:31a2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 2     | intel_i... | [D476F875D2](<Tablet/Teclast/X6/X6 plus/D578D72C0F87/UBUNTU-BUDGIE-21.10/5.13.0-19-GENERIC/X86_64/D476F875D2>) |
| 8086:1aa2 | 8086:7270 | Intel            | Integrated Sensor Solution           | 1     | intel_i... | [555A26F0D1](<Tablet/Intel/570x/570x DVT3/469D9CAF87D4/UBUNTU-CORE-20/5.4.0-62-GENERIC/X86_64/555A26F0D1>) |
| 8086:5aa2 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | intel_i... | [49D345EC0B](<Tablet/Xplore/iX101/iX101L1/1592B2F5F479/UBUNTU-20.04/5.6.0-1028-OEM/X86_64/49D345EC0B>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d2f | 8086:7270 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 448   | xhci_hcd   | [01D92157CD](<Tablet/Microsoft/Surface/Surface Pro 4/CB8635E9B024/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/01D92157CD>) |
| 8086:22b5 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 210   | xhci_hcd   | [496C93250D](<Tablet/Chuwi/Hi10/Hi10 pro tablet/D5A4927F3C98/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/496C93250D>) |
| 8086:34ed | 8086:7270 | Intel            | Ice Lake-LP USB 3.1 xHCI Host Con... | 152   | xhci_pci   | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:8a13 |           | Intel            | Ice Lake Thunderbolt 3 USB Contro... | 152   | xhci_pci   | [1226114F62](<Tablet/Microsoft/Surface/Surface Pro 7/9B8B66B22476/FEDORA-41/6.12.7-1.SURFACE.FC41.X86_64/X86_64/1226114F62>) |
| 8086:9c31 | 1414:9c31 | Intel            | 8 Series USB xHCI HC                 | 150   | xhci_pci   | [BB626D70B0](<Tablet/Microsoft/Surface/Surface Pro 3/217C1E4144F1/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/BB626D70B0>) |
| 8086:31a8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 81    | xhci_pci   | [1827AD6649](<Tablet/Microsoft/Surface/Surface Laptop SE/3C3B6159F009/ZORIN-17/6.8.0-49-GENERIC/X86_64/1827AD6649>) |
| 8086:22b5 | 17aa:380b | Intel            | Atom/Celeron/Pentium Processor x5... | 80    | xhci_hcd   | [53BAB82FAE](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/384948008566/ALPINE-3.20.3/6.6.63-0-LTS/X86_64/53BAB82FAE>) |
| 8086:22b5 | 17aa:3806 | Intel            | Atom/Celeron/Pentium Processor x5... | 65    | xhci_hcd   | [C377803591](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/FE4476C805C4/KDE-NEON-24.04/6.8.0-47-GENERIC/X86_64/C377803591>) |
| 8086:5aa8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 56    | xhci_pci   | [3044720FE2](<Tablet/Others/Others/Others/AFAAA3B0F2B5/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/3044720FE2>) |
| 8086:9a13 | 8086:7270 | Intel            | Tiger Lake-LP Thunderbolt 4 USB C... | 56    | xhci_pci   | [DA3534B096](<Tablet/Microsoft/Surface/Surface Pro 7+/87B1E5086B44/DEBIAN-12/6.1.0-28-AMD64/X86_64/DA3534B096>) |
| 8086:a0ed | 8086:7270 | Intel            | Tiger Lake-LP USB 3.2 Gen 2x1 xHC... | 55    | xhci_pci   | [DA3534B096](<Tablet/Microsoft/Surface/Surface Pro 7+/87B1E5086B44/DEBIAN-12/6.1.0-28-AMD64/X86_64/DA3534B096>) |
| 8086:22b7 | 8086:7270 | Intel            | USB Synopsys Controller              | 54    | dwc3_pci   | [BFAA80CD30](<Tablet/Hampoo/D4/D4D6_Hi8Pro_hnh/E4B64BCB46D2/ZORIN-17/6.5.0-41-GENERIC/X86_64/BFAA80CD30>) |
| 8086:9d2f | 152d:1182 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 54    | xhci_pci   | [9D75FA5900](<Tablet/Microsoft/Surface/Surface Go/AF397ED83516/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9D75FA5900>) |
| 8086:0f35 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 50    | xhci_hcd   | [0C43F7A18D](<Tablet/Wortmann AG/TERRA_PAD/TERRA_PAD_1061/2774F6C08D8F/UBUNTU-22.04/6.8.0-49-GENERIC/X86_64/0C43F7A18D>) |
| 8086:22b5 | 1043:13a0 | Intel            | Atom/Celeron/Pentium Processor x5... | 42    | xhci_hcd   | [2AA1D5261D](<Tablet/ASUSTek Computer/T101/T101HA/302BE3A15A2C/LMDE-6/6.1.0-23-AMD64/X86_64/2AA1D5261D>) |
| 8086:22b5 |           | Intel            | Atom/Celeron/Pentium Processor x5... | 36    | xhci_hcd   | [C8EB4963E5](<Tablet/OEM/M882/M882CWP/9C7F836ED3EA/FEDORA-40/6.10.10-200.FC40.X86_64/X86_64/C8EB4963E5>) |
| 8086:9d2f | 103c:82ca | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 36    | xhci_hcd   | [F0D42DF827](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/0C327DDF3EC7/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/F0D42DF827>) |
| 1022:15c0 | 1022:15c0 | AMD              | Family 19h USB XHCI Host Controller  | 35    | xhci_hcd   | [FD3DE9EA5C](<Tablet/ASUSTek Computer/ROG/ROG Ally RC71L_RC71L/16B794CF2193/BAZZITE-41/6.11.10-304.BAZZITE.FC41.X86_64/X86_64/FD3DE9EA5C>) |
| 1022:15c1 | 1022:15c1 | AMD              | Family 19h USB XHCI Host Controller  | 35    | xhci_hcd   | [FD3DE9EA5C](<Tablet/ASUSTek Computer/ROG/ROG Ally RC71L_RC71L/16B794CF2193/BAZZITE-41/6.11.10-304.BAZZITE.FC41.X86_64/X86_64/FD3DE9EA5C>) |
| 8086:51ed | 1043:201f | Intel            | Alder Lake PCH USB 3.2 xHCI Host ... | 31    | xhci_hcd   | [E35C79DDE2](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301VU_GZ301VU/2F999BBF1AC8/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/E35C79DDE2>) |
| 8086:22b5 | 103c:827c | Intel            | Atom/Celeron/Pentium Processor x5... | 30    | xhci_hcd   | [878A94CA7F](<Tablet/Hewlett-Packard/x2/x2 Detachable 10-p0XX/3D11A237BEFA/ZORIN-17/6.8.0-49-GENERIC/X86_64/878A94CA7F>) |
| 8086:9c26 | 1414:9c26 | Intel            | 8 Series USB EHCI #1                 | 30    | ehci_pci   | [964F81A59E](<Tablet/Microsoft/Surface/Surface Pro 2/9A502B2F7D5F/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/964F81A59E>) |
| 8086:15d4 | 2222:1111 | Intel            | JHL6540 Thunderbolt 3 USB Control... | 29    | xhci_hcd   | [454126AC6E](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KKS0S901/980E2F97C968/ARCH-ROLLING/6.12.6-ZEN1-1-ZEN/X86_64/454126AC6E>) |
| 1022:15b9 | 1043:201f | AMD              | Family 19h USB XHCI Host Controller  | 27    | xhci_hcd   | [FD3DE9EA5C](<Tablet/ASUSTek Computer/ROG/ROG Ally RC71L_RC71L/16B794CF2193/BAZZITE-41/6.11.10-304.BAZZITE.FC41.X86_64/X86_64/FD3DE9EA5C>) |
| 1022:15ba | 1043:201f | AMD              | Family 19h USB XHCI Host Controller  | 27    | xhci_hcd   | [FD3DE9EA5C](<Tablet/ASUSTek Computer/ROG/ROG Ally RC71L_RC71L/16B794CF2193/BAZZITE-41/6.11.10-304.BAZZITE.FC41.X86_64/X86_64/FD3DE9EA5C>) |
| 8086:22b5 | 1043:1400 | Intel            | Atom/Celeron/Pentium Processor x5... | 27    | xhci_hcd   | [073DCFBEFD](<Tablet/ASUSTek Computer/T102/T102HA/B8F0B026C483/ZORIN-17/6.5.0-25-GENERIC/X86_64/073DCFBEFD>) |
| 8086:9d2f | 1028:081d | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 27    | xhci_hcd   | [20E6DC4833](<Tablet/Dell/Latitude/Latitude 5290 2-in-1/069C27C420D3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.12.6-1-DEFAULT/X86_64/20E6DC4833>) |
| 8086:22b7 | 17aa:380a | Intel            | USB Synopsys Controller              | 26    | dwc3_pci   | [C377803591](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/FE4476C805C4/KDE-NEON-24.04/6.8.0-47-GENERIC/X86_64/C377803591>) |
| 8086:9a1b | 8086:7270 | Intel            | Tiger Lake-LP Thunderbolt 4 NHI #0   | 26    | thunder... | [0B901FDA6F](<Tablet/Microsoft/Surface/Surface Pro 8/2ECF330FF091/FEDORA-40/6.8.5-301.FC40.X86_64/X86_64/0B901FDA6F>) |
| 8086:9d2f | 103c:828b | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 26    | xhci_hcd   | [567E4C6343](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/53B866CA15BB/ZORIN-17/6.8.0-45-GENERIC/X86_64/567E4C6343>) |
| 1022:15b9 | 17aa:3812 | AMD              | Family 19h USB XHCI Host Controller  | 25    | xhci_hcd   | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 1022:15ba | 17aa:3812 | AMD              | Family 19h USB XHCI Host Controller  | 25    | xhci_hcd   | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 1022:15c0 | 17aa:3812 | AMD              | Family 19h USB XHCI Host Controller  | 25    | xhci_hcd   | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 1022:15c1 | 17aa:3812 | AMD              | Family 19h USB XHCI Host Controller  | 25    | xhci_hcd   | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 1022:1668 | 17aa:3812 | AMD              | Pink Sardine USB4/Thunderbolt NHI... | 25    | thunder... | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 1022:1669 | 17aa:3812 | AMD              | Pink Sardine USB4/Thunderbolt NHI... | 25    | thunder... | [1245987788](<Tablet/Lenovo/Legion/Legion Go 8APU1 83E1/3C8DDCAE57B1/BAZZITE-41/6.12.6-203.BAZZITE.FC41.X86_64/X86_64/1245987788>) |
| 8086:9d2f | 17aa:2244 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 25    | xhci_hcd   | [454126AC6E](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KKS0S901/980E2F97C968/ARCH-ROLLING/6.12.6-ZEN1-1-ZEN/X86_64/454126AC6E>) |
| 8086:0f35 | 1019:99a5 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 24    | xhci_hcd   | [DA6CE4B361](<Tablet/BANGHO/Suma/Suma 1025/DF80AD331B24/ZORIN-17/6.8.0-49-GENERIC/X86_64/DA6CE4B361>) |
| 8086:461e |           | Intel            | Alder Lake-P Thunderbolt 4 USB Co... | 24    | xhci_hcd   | [0A76D54F2A](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZE_GZ301ZE/E93163333EB2/UBUNTUSTUDIO-24.10/6.11.0-9-GENERIC/X86_64/0A76D54F2A>) |
| 8086:463e | 2222:1111 | Intel            | Alder Lake-P Thunderbolt 4 NHI #0    | 24    | thunder... | [0A76D54F2A](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301ZE_GZ301ZE/E93163333EB2/UBUNTUSTUDIO-24.10/6.11.0-9-GENERIC/X86_64/0A76D54F2A>) |
| 8086:9d2f | 152d:1237 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 24    | xhci_pci   | [51D7C66A4E](<Tablet/Microsoft/Surface/Surface Go 2/CC8450395E18/BLACKPANTHER-OS-22.1/6.6.32-POWER-1BP/X86_64/51D7C66A4E>) |
| 8086:1e26 | 1414:1e26 | Intel            | 7 Series/C216 Chipset Family USB ... | 21    | ehci_pci   | [09BDD29B6C](<Tablet/Microsoft/Surface/Surface Pro 2/DD2937B6F574/VANILLA-2.0/6.11.6-AMD64/X86_64/09BDD29B6C>) |
| 8086:1e2d | 1414:1e2d | Intel            | 7 Series/C216 Chipset Family USB ... | 21    | ehci_pci   | [09BDD29B6C](<Tablet/Microsoft/Surface/Surface Pro 2/DD2937B6F574/VANILLA-2.0/6.11.6-AMD64/X86_64/09BDD29B6C>) |
| 8086:1e31 | 1414:1e31 | Intel            | 7 Series/C210 Series Chipset Fami... | 21    | xhci_hcd   | [09BDD29B6C](<Tablet/Microsoft/Surface/Surface Pro 2/DD2937B6F574/VANILLA-2.0/6.11.6-AMD64/X86_64/09BDD29B6C>) |
| 8086:9d2f | 17aa:3851 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 21    | xhci_hcd   | [C14BE2A0FF](<Tablet/Lenovo/MIIX/MIIX 520-12IKB 81CG/A8FA91459A71/ZORIN-17/6.8.0-40-GENERIC/X86_64/C14BE2A0FF>) |
| 1022:15d6 | 1022:15d6 | AMD              | Rembrandt USB4 XHCI controller #5    | 20    | xhci_hcd   | [2183EB76B7](<Tablet/ONE-NETBOOK/ONEXPLAYER/ONEXPLAYER Mini Pro/F55453A23AA1/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/2183EB76B7>) |
| 1022:15d7 | 1022:15d7 | AMD              | Rembrandt USB4 XHCI controller #6    | 20    | xhci_hcd   | [2183EB76B7](<Tablet/ONE-NETBOOK/ONEXPLAYER/ONEXPLAYER Mini Pro/F55453A23AA1/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/2183EB76B7>) |
| 1022:161d | 1022:163a | AMD              | Rembrandt USB4 XHCI controller #3    | 20    | xhci_hcd   | [2183EB76B7](<Tablet/ONE-NETBOOK/ONEXPLAYER/ONEXPLAYER Mini Pro/F55453A23AA1/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/2183EB76B7>) |
| 1022:161e | 1022:163a | AMD              | Rembrandt USB4 XHCI controller #4    | 20    | xhci_hcd   | [2183EB76B7](<Tablet/ONE-NETBOOK/ONEXPLAYER/ONEXPLAYER Mini Pro/F55453A23AA1/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/2183EB76B7>) |
| 1022:161f | 1022:163a | AMD              | Rembrandt USB4 XHCI controller #8    | 20    | xhci_hcd   | [2183EB76B7](<Tablet/ONE-NETBOOK/ONEXPLAYER/ONEXPLAYER Mini Pro/F55453A23AA1/NOBARA-40/6.11.9-200.FSYNC.FC40.X86_64/X86_64/2183EB76B7>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 17cb:0304 | 17cb:0307 | Qualcomm Tech... | SDX24 [Snapdragon X24 4G]            | 1     | mhi_pci... | [0AD09DEE4F](<Tablet/Zebra Technologies/ET85/ET85B/B5661B10FE6A/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/0AD09DEE4F>) |

