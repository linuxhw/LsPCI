Most popular PCI devices in All In Ones
---------------------------------------

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in All In Ones ](#pci-devices)
   * [ Bluetooth ](#bluetooth-pci)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Firewire controller ](#firewire-controller-pci)
   * [ Generic system peripheral ](#generic-system-peripheral-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Iommu ](#iommu-pci)
   * [ Ipmi interface (kcs) ](#ipmi-interface-kcs-pci)
   * [ Ipmi smic interface ](#ipmi-smic-interface-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Multimedia controller ](#multimedia-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Non-essential instrumentation ](#non-essential-instrumentation-pci)
   * [ Non-vga unclassified device ](#non-vga-unclassified-device-pci)
   * [ Parallel controller (bidir) ](#parallel-controller-bidir-pci)
   * [ Performance counters ](#performance-counters-pci)
   * [ Pic (8259) ](#pic-8259-pci)
   * [ Pic (io(x)-apic) ](#pic-iox-apic-pci)
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
   * [ Tv card ](#tv-card-pci)
   * [ Usb controller ](#usb-controller-pci)
   * [ Others ](#others-pci)

PCI Devices
-----------

Count  - number of computers with this device installed,
Driver - driver in use for this device,
Probe  - latest probe ID of this device.

### Bluetooth (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1814:3298 | 103c:18ec | Ralink           | RT3290 Bluetooth                     | 2     |            | [19BE50FBCA](<All In One/Hewlett-Packard/205/205 G1 AiO Business PC/964AEC45753A/LOC-OS-22/5.10.142-LOC-OS/X86_64/19BE50FBCA>) |

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c10 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 290   | pcieport   | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 8086:1c14 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 290   | pcieport   | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 8086:1c44 | 8086:7270 | Intel            | Z68 Express Chipset LPC Controller   | 290   | lpc_ich    | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 8086:2448 |           | Intel            | 82801 Mobile PCI Bridge              | 290   |            | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 8086:1513 |           | Intel            | CV82524 Thunderbolt Controller [L... | 289   | pcieport   | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 8086:1c12 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 289   | pcieport   | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 8086:1c18 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 288   | pcieport   | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 104c:823e |           | Texas Instrum... | XIO2213A/B/XIO2221 PCI Express to... | 266   | shpchp     | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 8086:1547 | 2222:1111 | Intel            | DSL3510 Thunderbolt Controller [C... | 246   | pcieport   | [8485C9B6A3](<All In One/Apple/iMac14/iMac14,2/DE6A385E2C03/ARCH-ROLLING/6.10.14-273-TKG-EEVDF/X86_64/8485C9B6A3>) |
| 8086:2815 | 106b:00a0 | Intel            | 82801HM (ICH8M) LPC Interface Con... | 244   | lpc_ich    | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 8086:283f |           | Intel            | 82801H (ICH8 Family) PCI Express ... | 244   | pcieport   | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 8086:2845 |           | Intel            | 82801H (ICH8 Family) PCI Express ... | 244   | pcieport   | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 8086:2a00 | 106b:00a0 | Intel            | Mobile PM965/GM965/GL960 Memory C... | 244   | intel_agp  | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 8086:2a01 | 8086:0000 | Intel            | Mobile PM965/GM965/GL960 PCI Expr... | 244   | pcieport   | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 8086:2847 |           | Intel            | 82801H (ICH8 Family) PCI Express ... | 243   | pcieport   | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 8086:2849 |           | Intel            | 82801H (ICH8 Family) PCI Express ... | 243   | pcieport   | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 8086:244e | 8086:7270 | Intel            | 82801 PCI Bridge                     | 241   |            | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 10de:0aab | 10de:cb79 | Nvidia           | MCP79 PCI Bridge                     | 211   |            | [E82B0C22FB](<All In One/Apple/iMac10/iMac10,1/99E4987A298C/DEBIAN-12/6.1.0-28-AMD64/X86_64/E82B0C22FB>) |
| 10de:0ac4 | 10de:0000 | Nvidia           | MCP79 PCI Express Bridge             | 211   | pcieport   | [E82B0C22FB](<All In One/Apple/iMac10/iMac10,1/99E4987A298C/DEBIAN-12/6.1.0-28-AMD64/X86_64/E82B0C22FB>) |
| 10de:0ac6 | 10de:0000 | Nvidia           | MCP79 PCI Express Bridge             | 211   | pcieport   | [E82B0C22FB](<All In One/Apple/iMac10/iMac10,1/99E4987A298C/DEBIAN-12/6.1.0-28-AMD64/X86_64/E82B0C22FB>) |
| 10de:0ac7 | 10de:0000 | Nvidia           | MCP79 PCI Express Bridge             | 211   | pcieport   | [E82B0C22FB](<All In One/Apple/iMac10/iMac10,1/99E4987A298C/DEBIAN-12/6.1.0-28-AMD64/X86_64/E82B0C22FB>) |
| 8086:1578 | 8086:0000 | Intel            | DSL6540 Thunderbolt 3 Bridge [Alp... | 210   | pcieport   | [9C21FDA832](<All In One/Apple/iMac18/iMac18,2/9742FAAE1644/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9C21FDA832>) |
| 8086:8c10 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 188   | pcieport   | [8485C9B6A3](<All In One/Apple/iMac14/iMac14,2/DE6A385E2C03/ARCH-ROLLING/6.10.14-273-TKG-EEVDF/X86_64/8485C9B6A3>) |
| 8086:8c16 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 187   | pcieport   | [8485C9B6A3](<All In One/Apple/iMac14/iMac14,2/DE6A385E2C03/ARCH-ROLLING/6.10.14-273-TKG-EEVDF/X86_64/8485C9B6A3>) |
| 8086:8c14 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 185   | pcieport   | [8485C9B6A3](<All In One/Apple/iMac14/iMac14,2/DE6A385E2C03/ARCH-ROLLING/6.10.14-273-TKG-EEVDF/X86_64/8485C9B6A3>) |
| 8086:8c18 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 185   | pcieport   | [8485C9B6A3](<All In One/Apple/iMac14/iMac14,2/DE6A385E2C03/ARCH-ROLLING/6.10.14-273-TKG-EEVDF/X86_64/8485C9B6A3>) |
| 8086:a110 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 162   | pcieport   | [9C21FDA832](<All In One/Apple/iMac18/iMac18,2/9742FAAE1644/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9C21FDA832>) |
| 8086:a145 | 8086:7270 | Intel            | Z170 Chipset LPC/eSPI Controller     | 162   |            | [9C21FDA832](<All In One/Apple/iMac18/iMac18,2/9742FAAE1644/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9C21FDA832>) |
| 8086:a111 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 160   | pcieport   | [9C21FDA832](<All In One/Apple/iMac18/iMac18,2/9742FAAE1644/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9C21FDA832>) |
| 8086:0100 | 8086:2010 | Intel            | 2nd Generation Core Processor Fam... | 154   | snb_uncore | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 8086:0101 | 8086:2010 | Intel            | Xeon E3-1200/2nd Generation Core ... | 154   | pcieport   | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 8086:3b02 | 8086:7270 | Intel            | P55 Chipset LPC Interface Controller | 152   | lpc_ich    | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 8086:3b42 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset PCI ... | 152   | pcieport   | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 8086:3b44 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset PCI ... | 152   | pcieport   | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 8086:3b46 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset PCI ... | 152   | pcieport   | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 8086:0101 | 106b:0000 | Intel            | Xeon E3-1200/2nd Generation Core ... | 136   | pcieport   | [8B589149FB](<All In One/Apple/iMac12/iMac12,2/CB916DA645BF/KUBUNTU-24.04/6.8.0-50-GENERIC/X86_64/8B589149FB>) |
| 8086:0100 | 106b:0000 | Intel            | 2nd Generation Core Processor Fam... | 135   | snb_uncore | [8B589149FB](<All In One/Apple/iMac12/iMac12,2/CB916DA645BF/KUBUNTU-24.04/6.8.0-50-GENERIC/X86_64/8B589149FB>) |
| 8086:15d3 | 8086:0000 | Intel            | JHL6540 Thunderbolt 3 Bridge (C s... | 131   | pcieport   | [9C21FDA832](<All In One/Apple/iMac18/iMac18,2/9742FAAE1644/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9C21FDA832>) |
| 8086:156d |           | Intel            | DSL5520 Thunderbolt 2 Bridge [Fal... | 130   | pcieport   | [500ACCCF00](<All In One/Apple/iMac16/iMac16,2/D9F8E706C1F9/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/500ACCCF00>) |
| 10de:0aa0 | 10de:0000 | Nvidia           | MCP79 PCI Express Bridge             | 128   | shpchp     | [F3660A5D7B](<All In One/Apple/iMac9/iMac9,1/50AE0E9B32CE/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/F3660A5D7B>) |
| 8086:8c44 | 8086:7270 | Intel            | Z87 Express LPC Controller           | 126   | lpc_ich    | [8485C9B6A3](<All In One/Apple/iMac14/iMac14,2/DE6A385E2C03/ARCH-ROLLING/6.10.14-273-TKG-EEVDF/X86_64/8485C9B6A3>) |
| 10de:0aac | 10de:cb79 | Nvidia           | MCP79 LPC Bridge                     | 112   |            | [E82B0C22FB](<All In One/Apple/iMac10/iMac10,1/99E4987A298C/DEBIAN-12/6.1.0-28-AMD64/X86_64/E82B0C22FB>) |
| 8086:2d01 | 8086:8086 | Intel            | Core Processor QuickPath Architec... | 108   |            | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 8086:2d10 | 8086:8086 | Intel            | Core Processor QPI Link 0            | 108   |            | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 8086:2d11 | 8086:8086 | Intel            | 1st Generation Core i3/5/7 Proces... | 108   |            | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 8086:2d12 | 8086:8086 | Intel            | 1st Generation Core i3/5/7 Proces... | 108   |            | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 8086:2d13 | 8086:8086 | Intel            | 1st Generation Core i3/5/7 Proces... | 108   |            | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 8086:a114 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 107   | pcieport   | [EDA26270C4](<All In One/Apple/iMac18/iMac18,3/BEED7205CB3E/ARCH-ROLLING/6.12.6-ARCH1-1/X86_64/EDA26270C4>) |
| 8086:2c61 | 8086:8086 | Intel            | Core Processor QuickPath Architec... | 104   |            | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 10de:0aae | 10de:cb79 | Nvidia           | MCP79 LPC Bridge                     | 99    |            | [F3660A5D7B](<All In One/Apple/iMac9/iMac9,1/50AE0E9B32CE/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/F3660A5D7B>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:5209 | 1025:8020 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 21    | rtsx_pci   | [E81865186B](<All In One/Acer/Aspire/Aspire ZS600/0F176167F7F4/FEDORA-40/6.10.6-200.FC40.X86_64/X86_64/E81865186B>) |
| 10ec:5229 | 17aa:365e | Realtek Semic... | RTS5229 PCI Express Card Reader      | 21    | rtsx_pci   | [DBA1D52306](<All In One/Lenovo/C340/C340 10102/8204E1CC8521/ZORIN-17/6.8.0-48-GENERIC/X86_64/DBA1D52306>) |
| 10ec:5209 | 1028:0543 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 20    | rtsx_pci   | [A552EB99EE](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/B658E6C46850/ZORIN-17/6.8.0-49-GENERIC/X86_64/A552EB99EE>) |
| 10ec:5209 | 1028:0548 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 20    | rtsx_pci   | [939EFC4955](<All In One/Dell/Inspiron/Inspiron One 2330/DA27CAF94DE9/ELEMENTARY-7.1/6.8.0-48-GENERIC/X86_64/939EFC4955>) |
| 10ec:5209 | 1028:05a7 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 19    | rtsx_pci   | [F866E174C2](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/5BD2C4C72DD4/FEDORA-40/6.10.8-200.FC40.X86_64/X86_64/F866E174C2>) |
| 10ec:525a | 1028:06c5 | Realtek Semic... | RTS525A PCI Express Card Reader      | 18    | rtsx_pci   | [CCDA6EA567](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/2A418C925C5B/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/CCDA6EA567>) |
| 10ec:5209 | 1028:05db | Realtek Semic... | RTS5209 PCI Express Card Reader      | 16    | rtsx_pci   | [AAD8987195](<All In One/Dell/Inspiron/Inspiron 2350/537D2F43CC7A/MX-23/6.1.0-10-AMD64/X86_64/AAD8987195>) |
| 10ec:5229 | 103c:2b3e | Realtek Semic... | RTS5229 PCI Express Card Reader      | 16    | rtsx_pci   | [72FDDCCE30](<All In One/Hewlett-Packard/27/27-p014/5E43D288C796/OPENSUSE-LEAP-15.6/6.4.0-150600.23.30-DEFAULT/X86_64/72FDDCCE30>) |
| 10ec:522a | 1854:0308 | Realtek Semic... | RTS522A PCI Express Card Reader      | 15    | rtsx_pci   | [A595C7B829](<All In One/LG Electronics/22V280/22V280-L.BJ31P1/BE8548B5DD51/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/A595C7B829>) |
| 10ec:525a | 1028:079c | Realtek Semic... | RTS525A PCI Express Card Reader      | 14    | rtsx_pci   | [D019C812B7](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/360F073CECA0/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/D019C812B7>) |
| 10ec:5209 | 103c:2ac5 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 12    | rtsx_pci   | [B32F35A4B1](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/C0BF0A16B6D4/FEDORA-36/5.18.19-200.FC36.X86_64/X86_64/B32F35A4B1>) |
| 10ec:5229 | 10ec:5229 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 11    | rtsx_pci   | [DDF5E843A5](<All In One/Positivo/C4120/C4120N20A-21/29C4D24B28C4/XUBUNTU-24.04/6.8.0-45-GENERIC/X86_64/DDF5E843A5>) |
| 10ec:5229 | 17aa:366c | Realtek Semic... | RTS5229 PCI Express Card Reader      | 11    | rtsx_pci   | [71F424691E](<All In One/Lenovo/C540/C540 10110/5F044C149ED0/LINUXMINT-22/6.8.0-49-GENERIC/X86_64/71F424691E>) |
| 10ec:5229 | 103c:2b0d | Realtek Semic... | RTS5229 PCI Express Card Reader      | 10    | rtsx_pci   | [5AED288755](<All In One/Hewlett-Packard/23/23-g350nf/1938D3668F06/FEDORA-40/6.12.6-100.FC40.X86_64/X86_64/5AED288755>) |
| 10ec:5229 | 103c:82dc | Realtek Semic... | RTS5229 PCI Express Card Reader      | 10    | rtsx_pci   | [4F6CBB3D87](<All In One/Hewlett-Packard/440G3PONA-i37100T-1Thq-4C-8f/440G3PONA-i37100T-1Thq-4C-8f PC/4649228EBB87/OPENMANDRIVA-24.01/6.6.2-DESKTOP-1OMV2390/X86_64/4F6CBB3D87>) |
| 10ec:5229 | 103c:81b7 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 9     | rtsx_pci   | [5EE96C131D](<All In One/Hewlett-Packard/24/24-b104nf/DAEF4DA1C3B6/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/5EE96C131D>) |
| 10ec:5229 | 17aa:3686 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 9     | rtsx_pci   | [F2AD5B1C81](<All In One/Lenovo/C560/C560 10150/F42ADFFAA517/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/F2AD5B1C81>) |
| 10ec:522a | 1028:0754 | Realtek Semic... | RTS522A PCI Express Card Reader      | 9     | rtsx_pci   | [274DC30D2C](<All In One/Dell/Inspiron/Inspiron 3464 AIO/31AD17DDDC01/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/274DC30D2C>) |
| 10ec:5209 | 1028:05b0 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 8     | rtsx_pci   | [441BD970BB](<All In One/Dell/XPS/XPS 2720/AD0C6D85F139/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/441BD970BB>) |
| 10ec:5209 | 1854:0167 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 8     | rtsx_pci   | [83A2F4A1F0](<All In One/LG Electronics/V320/V320-M.BK33P1/6AC49E86F00A/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/83A2F4A1F0>) |
| 10ec:5229 | 17aa:367b | Realtek Semic... | RTS5229 PCI Express Card Reader      | 8     | rtsx_pci   | [4EB5763E89](<All In One/Lenovo/IdeaCentre/IdeaCentre B550 10135/3FCD9E436CF5/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/4EB5763E89>) |
| 10ec:5229 | 17aa:36ab | Realtek Semic... | RTS5229 PCI Express Card Reader      | 8     | rtsx_pci   | [74820C3666](<All In One/Lenovo/C40-05/C40-05 F0B5004EUK/3ED6D2F5B3CF/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/74820C3666>) |
| 10ec:522a | 103c:83eb | Realtek Semic... | RTS522A PCI Express Card Reader      | 8     | rtsx_pci   | [F655DC8E65](<All In One/Hewlett-Packard/ProOne/ProOne 440 G4 AiO/46615EAD4BA5/UBUNTU-22.04/6.2.0-34-GENERIC/X86_64/F655DC8E65>) |
| 10ec:522a | 103c:85a2 | Realtek Semic... | RTS522A PCI Express Card Reader      | 8     | rtsx_pci   | [4C618F5DDE](<All In One/Hewlett-Packard/ProOne/ProOne 440 G5 23.8-in All-in-One/AC4148A4D238/RED-OS-8.0/6.6.6-1.RED80.X86_64/X86_64/4C618F5DDE>) |
| 10ec:5209 | 103c:2aed | Realtek Semic... | RTS5209 PCI Express Card Reader      | 7     | rtsx_pci   | [1F00336F45](<All In One/Hewlett-Packard/HP3520/HP3520 Aio/8D65D89E25F7/UBUNTU-22.04/6.5.0-21-GENERIC/X86_64/1F00336F45>) |
| 10ec:5229 | 17aa:3685 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 7     | rtsx_pci   | [90A6071C01](<All In One/Lenovo/C460/C460 10149/221F4E3D13B3/BLACKPANTHER-OS-18.1/5.15.85-DESKTOP-1BP/X86_64/90A6071C01>) |
| 10ec:522a | 10ec:522a | Realtek Semic... | RTS522A PCI Express Card Reader      | 7     | rtsx_pci   | [04D33628A1](<All In One/LG Electronics/22V270/22V270-L.BJ31P1/8E73444ADF98/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/04D33628A1>) |
| 10ec:5209 | 17aa:3629 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 6     | rtsx_pci   | [85283E62FD](<All In One/Lenovo/C/C225/BCF3261CFAE4/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/85283E62FD>) |
| 10ec:5229 | 1025:085f | Realtek Semic... | RTS5229 PCI Express Card Reader      | 6     | rtsx_pci   | [59FB4C7892](<All In One/Acer/Aspire/Aspire ZC-606/9D356332373D/VOID-ROLLING/6.6.52_1/X86_64/59FB4C7892>) |
| 10ec:5229 | 103c:2b0a | Realtek Semic... | RTS5229 PCI Express Card Reader      | 6     | rtsx_pci   | [94D8A9C118](<All In One/Hewlett-Packard/20/20-2120ns/D12CB9D4CC39/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/94D8A9C118>) |
| 10ec:5229 | 103c:2b3b | Realtek Semic... | RTS5229 PCI Express Card Reader      | 6     | rtsx_pci   | [83AF71F2E9](<All In One/Hewlett-Packard/23/23-r159la/D01B9A9B3593/ELEMENTARY-7.1/6.8.0-47-GENERIC/X86_64/83AF71F2E9>) |
| 10ec:525a | 1028:084b | Realtek Semic... | RTS525A PCI Express Card Reader      | 6     | rtsx_pci   | [9352E7ED07](<All In One/Dell/OptiPlex/OptiPlex 7460 AIO/AAD8696E4652/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9352E7ED07>) |
| 10ec:5289 | 17aa:3671 | Realtek Semic... | RTL8411 PCI Express Card Reader      | 6     | rtsx_pci   | [5CCA2E9488](<All In One/Lenovo/C240/C240 10113/2D80C338F776/ELEMENTARY-7.1/6.8.0-45-GENERIC/X86_64/5CCA2E9488>) |
| 10ec:5209 | 1028:054b | Realtek Semic... | RTS5209 PCI Express Card Reader      | 5     | rtsx_pci   | [384D13D228](<All In One/Dell/XPS/XPS One 2710/B7601389FED4/MX-23/6.1.0-25-AMD64/X86_64/384D13D228>) |
| 10ec:5229 | 103c:2b2f | Realtek Semic... | RTS5229 PCI Express Card Reader      | 5     | rtsx_pci   | [006B770F80](<All In One/Hewlett-Packard/18/18-4415la/B52844F55842/ZORIN-17/6.8.0-47-GENERIC/X86_64/006B770F80>) |
| 10ec:5229 | 17aa:3630 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 5     | rtsx_pci   | [9C73644CD4](<All In One/Lenovo/S500z/S500z 10HC0024MT/064AAC1B5C8B/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/9C73644CD4>) |
| 10ec:5229 | 17aa:3633 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 5     | rtsx_pci   | [7855BD3EAB](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 300-23ACL F0BC0018CF/1DF10EDA030E/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/7855BD3EAB>) |
| 10ec:5229 | 17aa:369c | Realtek Semic... | RTS5229 PCI Express Card Reader      | 5     | rtsx_pci   | [0B2D7F5616](<All In One/Lenovo/B50-30/B50-30 F0AU00EEIX/B1C1DD126C40/UBUNTU-23.10/6.5.0-26-GENERIC/X86_64/0B2D7F5616>) |
| 10ec:5229 | 17aa:36bd | Realtek Semic... | RTS5229 PCI Express Card Reader      | 5     | rtsx_pci   | [D68501A3D9](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 510-23ASR F0CE002DAU/3B2CB02D55FF/DEBIAN-12/6.1.0-13-AMD64/X86_64/D68501A3D9>) |
| 10ec:5229 | 17aa:36ed | Realtek Semic... | RTS5229 PCI Express Card Reader      | 5     | rtsx_pci   | [C6B2DB5F7B](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 330-20IGM F0D70043CK/77A4D86B366E/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/C6B2DB5F7B>) |
| 10ec:524a | 103c:805e | Realtek Semic... | RTS524A PCI Express Card Reader      | 5     | rtsx_pci   | [EB19C3207D](<All In One/Hewlett-Packard/ProOne/ProOne 600 G2 21.5-in Non-Touch AiO/95CE8F95FEA5/LINUXMINT-21.3/5.15.0-124-GENERIC/X86_64/EB19C3207D>) |
| 10ec:524a | 103c:829b | Realtek Semic... | RTS524A PCI Express Card Reader      | 5     | rtsx_pci   | [349DDEFD63](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G3 23.8-in Non-Touch AiO/DCF7AC139838/DEBIAN-12/6.1.0-27-AMD64/X86_64/349DDEFD63>) |
| 10ec:525a | 1028:075c | Realtek Semic... | RTS525A PCI Express Card Reader      | 5     | rtsx_pci   | [62F71BAABE](<All In One/Dell/XPS/XPS 7760 AIO/AC856E6CD9D7/ZORIN-17/6.8.0-49-GENERIC/X86_64/62F71BAABE>) |
| 10ec:5287 | 1297:2053 | Realtek Semic... | RTL8411B PCI Express Card Reader     | 5     | rtsx_pci   | [95E8BED16F](<All In One/Positivo/DH8/DH8BW01/5F022083C428/KDE-NEON-20.04/5.15.0-50-GENERIC/X86_64/95E8BED16F>) |
| 10ec:5289 | 17aa:3670 | Realtek Semic... | RTL8411 PCI Express Card Reader      | 5     | rtsx_pci   | [492077995D](<All In One/Lenovo/C245/C245 10114/397EE5A8B1C2/DEBIAN-23/5.10.203-LOC-OS/X86_64/492077995D>) |
| 10ec:5229 | 103c:2b0c | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx_pci   | [CE31398BF7](<All In One/Hewlett-Packard/18/18-4221la/473D2B4042C4/OPENMANDRIVA-23.08/6.4.11-DESKTOP-1OMV2390/X86_64/CE31398BF7>) |
| 10ec:5229 | 103c:2b13 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx_pci   | [884D3AFF6D](<All In One/Hewlett-Packard/21/21-h014/1736AC03735D/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/884D3AFF6D>) |
| 10ec:5229 | 17aa:365a | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx_pci   | [DFE01FA6DD](<All In One/Lenovo/IdeaCentre/IdeaCentre B540 Product/D2EAAA70F6B6/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/DFE01FA6DD>) |
| 10ec:5229 | 17aa:369e | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx_pci   | [EBA82837D7](<All In One/Lenovo/C470/C470 10170/32BC7A770BF8/ARCO-ROLLING/6.10.4-1-CACHYOS/X86_64/EBA82837D7>) |
| 10ec:5229 | 17aa:36bc | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx_pci   | [D22FF7B37D](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 510-22ISH F0CB00H9BP/40B560126C98/FEDORA-39/6.6.3-200.FC39.X86_64/X86_64/D22FF7B37D>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10de:0aa3 | 10de:cb79 | Nvidia           | MCP79 Co-processor                   | 211   | nvidia     | [E82B0C22FB](<All In One/Apple/iMac10/iMac10,1/99E4987A298C/DEBIAN-12/6.1.0-28-AMD64/X86_64/E82B0C22FB>) |
| 10de:0753 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 12    |            | [63D0351E00](<All In One/Acer/Aspire/Aspire Z5101/8569CA5B9C9A/LINUXMINT-22/6.8.0-45-GENERIC/X86_64/63D0351E00>) |
| 10de:0aa3 | 1462:4570 | Nvidia           | MCP79 Co-processor                   | 9     | nvidia     | [F7CB25FE9C](<All In One/MSI/MS/MS-6657/91327E5DD924/ZORIN-17/6.8.0-48-GENERIC/X86_64/F7CB25FE9C>) |
| 10de:0aa3 | 1043:8379 | Nvidia           | MCP79 Co-processor                   | 2     |            | [72365E4985](<All In One/ASUSTek Computer/ET/ET2002/9AD492BE589B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/72365E4985>) |
| 10de:0753 | 1025:0462 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 1     |            | [C98E028454](<All In One/Gateway/ZX/ZX4351/9B8510AE2122/MX-23/6.1.0-26-AMD64/X86_64/C98E028454>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c3a | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 290   | mei_me     | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 8086:8c3a | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 187   | mei_me     | [8485C9B6A3](<All In One/Apple/iMac14/iMac14,2/DE6A385E2C03/ARCH-ROLLING/6.10.14-273-TKG-EEVDF/X86_64/8485C9B6A3>) |
| 8086:a13a | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 162   | mei_me     | [9C21FDA832](<All In One/Apple/iMac18/iMac18,2/9742FAAE1644/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9C21FDA832>) |
| 8086:1e3a | 8086:7270 | Intel            | 7 Series/C216 Chipset Family MEI ... | 89    | mei_me     | [0BB2743C5F](<All In One/Apple/iMac13/iMac13,1/9790142699C8/ZORIN-17/6.8.0-49-GENERIC/X86_64/0BB2743C5F>) |
| 8086:a360 | 8086:7270 | Intel            | Cannon Lake PCH HECI Controller      | 82    | mei_me     | [0C36BC1E93](<All In One/Apple/iMac19/iMac19,2/C074723931A0/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/0C36BC1E93>) |
| 8086:a328 | 8086:7270 | Intel            | Cannon Lake PCH Serial IO UART Ho... | 79    | intel_l... | [0C36BC1E93](<All In One/Apple/iMac19/iMac19,2/C074723931A0/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/0C36BC1E93>) |
| 8086:a329 | 8086:7270 | Intel            | 300 Series Chipset Family            | 79    | intel_l... | [0C36BC1E93](<All In One/Apple/iMac19/iMac19,2/C074723931A0/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/0C36BC1E93>) |
| 8086:43e0 |           | Intel            | Tiger Lake-H Management Engine In... | 62    | mei_me     | [F969D9FB85](<All In One/ICL/RAY/RAY Si105.Mi/2E3E3E31C611/ROSA-12/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/F969D9FB85>) |
| 8086:8cba | 8086:7270 | Intel            | 9 Series Chipset Family ME Interf... | 44    | mei_me     | [500ACCCF00](<All In One/Apple/iMac16/iMac16,2/D9F8E706C1F9/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/500ACCCF00>) |
| 8086:9c3a | 8086:7270 | Intel            | 8 Series HECI #0                     | 26    | mei_me     | [9F2B2370D2](<All In One/Apple/iMac14/iMac14,4/C04E3A92385A/DEBIAN/6.11.10-AMD64/X86_64/9F2B2370D2>) |
| 8086:a2ba | 1019:a5a1 | Intel            | 200 Series PCH CSME HECI #1          | 24    | mei_me     | [46658F67D3](<All In One/ICL/H310/H310SB-TM/298E8E81F4C1/ROSA-12/6.1.81-GENERIC-2ROSA2021.1-X86_64/X86_64/46658F67D3>) |
| 8086:a360 | 103c:84ee | Intel            | Cannon Lake PCH HECI Controller      | 23    | mei_me     | [597321B19E](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/07E9499C7A2C/KDE-NEON-24.04/6.8.0-49-GENERIC/X86_64/597321B19E>) |
| 8086:1c3a | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 21    | mei_me     | [DBA1D52306](<All In One/Lenovo/C340/C340 10102/8204E1CC8521/ZORIN-17/6.8.0-48-GENERIC/X86_64/DBA1D52306>) |
| 8086:9d3a | 8086:7270 | Intel            | Sunrise Point-LP CSME HECI #1        | 21    | mei_me     | [727B7184C9](<All In One/Apple/iMac18/iMac18,1/169F9C1861CD/DEBIAN-12/6.1.0-27-AMD64/X86_64/727B7184C9>) |
| 8086:1e3a | 1028:0543 | Intel            | 7 Series/C216 Chipset Family MEI ... | 20    | mei_me     | [A552EB99EE](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/B658E6C46850/ZORIN-17/6.8.0-49-GENERIC/X86_64/A552EB99EE>) |
| 8086:1e3a | 1028:0548 | Intel            | 7 Series/C216 Chipset Family MEI ... | 20    | mei_me     | [939EFC4955](<All In One/Dell/Inspiron/Inspiron One 2330/DA27CAF94DE9/ELEMENTARY-7.1/6.8.0-48-GENERIC/X86_64/939EFC4955>) |
| 8086:8c3a | 1028:05a7 | Intel            | 8 Series/C220 Series Chipset Fami... | 19    | mei_me     | [F866E174C2](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/5BD2C4C72DD4/FEDORA-40/6.10.8-200.FC40.X86_64/X86_64/F866E174C2>) |
| 8086:9d3a | 103c:84de | Intel            | Sunrise Point-LP CSME HECI #1        | 19    | mei_me     | [A7F55BE076](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/F6FC816725AE/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/A7F55BE076>) |
| 8086:1c3a | 1028:0511 | Intel            | 6 Series/C200 Series Chipset Fami... | 18    | mei_me     | [EC101E6744](<All In One/Dell/Inspiron/Inspiron One 2320/3D9ADF185AD6/ARCH-ROLLING/6.12.7-ARCH1-1/X86_64/EC101E6744>) |
| 8086:a13a | 1028:06c5 | Intel            | 100 Series/C230 Series Chipset Fa... | 17    | mei_me     | [CCDA6EA567](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/2A418C925C5B/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/CCDA6EA567>) |
| 8086:8c3a | 1028:05db | Intel            | 8 Series/C220 Series Chipset Fami... | 16    | mei_me     | [AAD8987195](<All In One/Dell/Inspiron/Inspiron 2350/537D2F43CC7A/MX-23/6.1.0-10-AMD64/X86_64/AAD8987195>) |
| 8086:a13a | 103c:2b3e | Intel            | 100 Series/C230 Series Chipset Fa... | 16    | mei_me     | [72FDDCCE30](<All In One/Hewlett-Packard/27/27-p014/5E43D288C796/OPENSUSE-LEAP-15.6/6.4.0-150600.23.30-DEFAULT/X86_64/72FDDCCE30>) |
| 8086:319a | 1854:0308 | Intel            | Celeron/Pentium Silver Processor ... | 15    | mei_me     | [A595C7B829](<All In One/LG Electronics/22V280/22V280-L.BJ31P1/BE8548B5DD51/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/A595C7B829>) |
| 8086:9d3a | 1025:1287 | Intel            | Sunrise Point-LP CSME HECI #1        | 15    | mei_me     | [08963EC448](<All In One/Acer/Aspire/Aspire C24-865/78DC8340D315/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/08963EC448>) |
| 8086:9d3a | 8086:9d3a | Intel            | Sunrise Point-LP CSME HECI #1        | 15    | mei_me     | [555F0208DB](<All In One/ASUSTek Computer/V241/V241IC-R/86B3953D53F1/UBUNTU-22.04/6.2.0-39-GENERIC/X86_64/555F0208DB>) |
| 8086:7ae8 |           | Intel            | Alder Lake-S PCH HECI Controller #1  | 14    | mei_me     | [0DAAF7E4B7](<All In One/DEPO Computers/DPH/DPH610T/1B53DCFC22E5/RED-OS-7.3/6.1.52-1.EL7.3.X86_64/X86_64/0DAAF7E4B7>) |
| 8086:a2ba | 1028:079c | Intel            | 200 Series PCH CSME HECI #1          | 14    | mei_me     | [D019C812B7](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/360F073CECA0/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/D019C812B7>) |
| 8086:2e24 | 104d:9060 | Intel            | 4 Series Chipset HECI Controller     | 13    | mei_me     | [18C8665A8A](<All In One/Sony/VPCL14/VPCL14S1E/05E16BA420D0/LINUXMINT-21.3/5.15.0-121-GENERIC/X86_64/18C8665A8A>) |
| 8086:7aa8 |           | Intel            | Alder Lake-S PCH Serial IO UART #0   | 13    | intel_lpss | [0DAAF7E4B7](<All In One/DEPO Computers/DPH/DPH610T/1B53DCFC22E5/RED-OS-7.3/6.1.52-1.EL7.3.X86_64/X86_64/0DAAF7E4B7>) |
| 8086:8c3a | 1028:0626 | Intel            | 8 Series/C220 Series Chipset Fami... | 13    | mei_me     | [1F361B3518](<All In One/Dell/Inspiron/Inspiron 23 Model 5348/D34B13017CE6/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/1F361B3518>) |
| 8086:a0e0 | 1028:0a06 | Intel            | Tiger Lake-LP Management Engine I... | 13    | mei_me     | [078A22F745](<All In One/Dell/Inspiron/Inspiron 5400 AIO/D5D2451D1C1C/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/078A22F745>) |
| 8086:1c3a | 103c:2ac5 | Intel            | 6 Series/C200 Series Chipset Fami... | 12    | mei_me     | [B32F35A4B1](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/C0BF0A16B6D4/FEDORA-36/5.18.19-200.FC36.X86_64/X86_64/B32F35A4B1>) |
| 8086:319a | 1025:1304 | Intel            | Celeron/Pentium Silver Processor ... | 12    | mei_me     | [31F323613D](<All In One/Acer/Aspire/Aspire C22-820/D247EFB9442C/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/31F323613D>) |
| 8086:8c3a | 1028:0625 | Intel            | 8 Series/C220 Series Chipset Fami... | 12    | mei_me     | [C125805F0D](<All In One/Dell/OptiPlex/OptiPlex 9030 AIO/2EE105977E12/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/C125805F0D>) |
| 8086:9cba | 8086:7270 | Intel            | Wildcat Point-LP MEI Controller #1   | 12    | mei_me     | [E9F3801A74](<All In One/Apple/iMac16/iMac16,1/A877523A0FA6/LINUXMINT-22/6.8.0-45-GENERIC/X86_64/E9F3801A74>) |
| 8086:1c3a | 17aa:366c | Intel            | 6 Series/C200 Series Chipset Fami... | 11    | mei_me     | [71F424691E](<All In One/Lenovo/C540/C540 10110/5F044C149ED0/LINUXMINT-22/6.8.0-49-GENERIC/X86_64/71F424691E>) |
| 8086:3b64 | 17aa:306a | Intel            | 5 Series/3400 Series Chipset HECI... | 11    | mei_me     | [B562DA927A](<All In One/Lenovo/ThinkCentre/ThinkCentre M90z 3429D3U/93DF0426D130/UBUNTU-22.04/5.4.0-156-GENERIC/X86_64/B562DA927A>) |
| 8086:9cba | 8086:9cba | Intel            | Wildcat Point-LP MEI Controller #1   | 11    | mei_me     | [864CBD6A4C](<All In One/BESSTAR Tech/U/U700/6D4EDF1058E5/UBUNTU-22.04/6.5.0-14-GENERIC/X86_64/864CBD6A4C>) |
| 8086:a360 | 103c:8446 | Intel            | Cannon Lake PCH HECI Controller      | 11    | mei_me     | [C5B5B31A25](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/7EFF5EC8D014/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/C5B5B31A25>) |
| 8086:1c3a | 104d:907e | Intel            | 6 Series/C200 Series Chipset Fami... | 10    | mei_me     | [A8F1E64B41](<All In One/Sony/VPCL236/VPCL236FX/7D6F7AF3086A/ZORIN-17/6.8.0-49-GENERIC/X86_64/A8F1E64B41>) |
| 8086:1c3a | 144d:b092 | Intel            | 6 Series/C200 Series Chipset Fami... | 10    | mei_me     | [B2DD874812](<All In One/Samsung Electronics/P500/P500A2D/6CBEFCF9E89C/UBUNTU-22.04/6.8.0-47-GENERIC/X86_64/B2DD874812>) |
| 8086:319a | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 10    | mei_me     | [BD9F5DD3DE](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/BD9F5DD3DE>) |
| 8086:5a9a | 17aa:36c4 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 10    | mei_me     | [321FD04E93](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 310-20IAP F0CL0014LD/4155E31B2EFA/OPENMANDRIVA-23.08/6.4.11-DESKTOP-1OMV2390/X86_64/321FD04E93>) |
| 8086:8c3a | 103c:2b0d | Intel            | 8 Series/C220 Series Chipset Fami... | 10    | mei_me     | [5AED288755](<All In One/Hewlett-Packard/23/23-g350nf/1938D3668F06/FEDORA-40/6.12.6-100.FC40.X86_64/X86_64/5AED288755>) |
| 8086:9de0 | 1043:17b1 | Intel            | Cannon Point-LP MEI Controller #1    | 10    | mei_me     | [DBDFEC80AC](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/9D86375D22FA/LINUXMINT-21.2/5.15.0-91-GENERIC/X86_64/DBDFEC80AC>) |
| 8086:9de0 | 17aa:3145 | Intel            | Cannon Point-LP MEI Controller #1    | 10    | mei_me     | [4FAC5AC06A](<All In One/Lenovo/V540-24IWL/V540-24IWL AIO 10YS0031RU/BC9666104DD6/ROSA-12/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/4FAC5AC06A>) |
| 8086:a13a | 8086:a13a | Intel            | 100 Series/C230 Series Chipset Fa... | 10    | mei_me     | [B9F363DA1B](<All In One/ASUSTek Computer/Z240/Z240IC-H170/BD8C045F6FC1/FEDORA-40/6.9.10-200.FC40.X86_64/X86_64/B9F363DA1B>) |
| 8086:1e3a | 144d:b091 | Intel            | 7 Series/C216 Chipset Family MEI ... | 9     | mei_me     | [7DDB4BB85E](<All In One/Samsung Electronics/DP700/DP700A3D-DM700A3D-DB701A3D-DP700A7D/F8AB47648274/ELEMENTARY-7.1/6.5.0-28-GENERIC/X86_64/7DDB4BB85E>) |
| 8086:34e0 | 1025:1434 | Intel            | Ice Lake-LP Management Engine        | 9     | mei_me     | [DB7DFE3AC4](<All In One/Acer/Aspire/Aspire C22-963/468F69A6EF00/LINUX-LITE-5.6/5.4.0-182-GENERIC/X86_64/DB7DFE3AC4>) |
| 8086:8c3a | 1028:0623 | Intel            | 8 Series/C220 Series Chipset Fami... | 9     | mei_me     | [F50F82AA00](<All In One/Dell/OptiPlex/OptiPlex 3030 AIO/366444499BD4/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/F50F82AA00>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1537 | 1022:1537 | AMD              | Kabini/Mullins PSP-Platform Secur... | 32    | ccp        | [7855BD3EAB](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 300-23ACL F0BC0018CF/1DF10EDA030E/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/7855BD3EAB>) |
| 1022:1537 | 103c:8245 | AMD              | Kabini/Mullins PSP-Platform Secur... | 24    | ccp        | [544F0D3076](<All In One/Hewlett-Packard/20/20-c002a/4A3792E1E976/LINUXMINT-22/6.8.0-49-GENERIC/X86_64/544F0D3076>) |
| 1022:15df | 103c:86f3 | AMD              | Family 17h (Models 10h-1fh) Platf... | 20    | ccp        | [2F05B30C3F](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-dp0xxx/E1C03E22AF48/OPENMANDRIVA-24.03/6.8.1-DESKTOP-3OMV2490/X86_64/2F05B30C3F>) |
| 1022:1578 | 103c:8430 | AMD              | Carrizo Platform Security Processor  | 19    |            | [3EA46622E6](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/E4E878423146/OPENMANDRIVA-24.08/6.10.1-DESKTOP-1OMV2490/X86_64/3EA46622E6>) |
| 8086:2298 | 103c:81bb | Intel            | Atom/Celeron/Pentium Processor x5... | 17    | mei_txe    | [A802D08306](<All In One/Hewlett-Packard/22/22-b015ur/5883A5C263EF/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/A802D08306>) |
| 1022:15df | 1022:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 16    | ccp        | [837B2CFE99](<All In One/Others/Others/Others/58E4FC6F62D5/MANJARO-24.0.8/6.9.12-3-MANJARO/X86_64/837B2CFE99>) |
| 1022:1537 | 103c:2b3b | AMD              | Kabini/Mullins PSP-Platform Secur... | 13    | ccp        | [83AF71F2E9](<All In One/Hewlett-Packard/23/23-r159la/D01B9A9B3593/ELEMENTARY-7.1/6.8.0-47-GENERIC/X86_64/83AF71F2E9>) |
| 1022:1578 | 1022:1578 | AMD              | Carrizo Platform Security Processor  | 13    |            | [F781FACD17](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-22AST F0D6000PLD/3E21F3CA09A6/UBUNTU-24.10/6.11.0-8-GENERIC/X86_64/F781FACD17>) |
| 1022:1578 | 103c:8381 | AMD              | Carrizo Platform Security Processor  | 13    |            | [6745FD4BAC](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/EF305E495BCA/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/6745FD4BAC>) |
| 8086:0f18 | 17aa:3695 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 10    | mei_txe    | [462E531E2A](<All In One/Lenovo/C260/C260 10160/87949A5BD7F7/XUBUNTU-24.04/6.8.0-31-GENERIC/X86_64/462E531E2A>) |
| 8086:0f18 | 1028:0690 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 9     | mei_txe    | [0FBDE604E6](<All In One/Dell/Inspiron/Inspiron 20 Model 3043/C7C0ED241602/ZORIN-17/6.8.0-50-GENERIC/X86_64/0FBDE604E6>) |
| 1022:15df | 1028:0b83 | AMD              | Family 17h (Models 10h-1fh) Platf... | 8     | ccp        | [D19E3017AD](<All In One/Dell/Inspiron/Inspiron 24 5415 All-in-One/5E02E56F3BDD/DEBIAN-12/6.1.0-26-AMD64/X86_64/D19E3017AD>) |
| 1022:15df | 103c:8924 | AMD              | Family 17h (Models 10h-1fh) Platf... | 8     | ccp        | [67175C1B82](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One Desktop 24-ca0xxx/15CC8A5959D7/DEBIAN-12/6.1.0-27-AMD64/X86_64/67175C1B82>) |
| 8086:2298 | 1028:06cc | Intel            | Atom/Celeron/Pentium Processor x5... | 8     | mei_txe    | [B62E73BAB2](<All In One/Dell/Inspiron/Inspiron 20-3052/862CDCFFAAFA/FEDORA-39/6.7.6-200.FC39.X86_64/X86_64/B62E73BAB2>) |
| 1022:15df | 17aa:371c | AMD              | Family 17h (Models 10h-1fh) Platf... | 7     | ccp        | [E1B1540113](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 24ARE05 F0EW004WUK/5E9CA431A68F/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E1B1540113>) |
| 8086:0f18 | 1854:0200 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 7     | mei_txe    | [163C52FD3C](<All In One/LG Electronics/22V240/22V240-L.AK35B2/3689BD3EEE5E/MANJARO-22.0.4/6.1.12-1-MANJARO/X86_64/163C52FD3C>) |
| 8086:2298 | 8086:2298 | Intel            | Atom/Celeron/Pentium Processor x5... | 7     | mei_txe    | [15B08C9C89](<All In One/ASUSTek Computer/A/A4110/C1D49E58397F/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-X86_64/X86_64/15B08C9C89>) |
| 1022:1456 | 1022:1456 | AMD              | Family 17h (Models 00h-0fh) Platf... | 6     | ccp        | [D05A394FC8](<All In One/Acidanthera/iMacPro1/iMacPro1,1/9C6521899F59/CHIMERAOS-46/6.8.0-RC2-CHOS1-CHIMERAOS-1/X86_64/D05A394FC8>) |
| 1022:1578 | 1028:0854 | AMD              | Carrizo Platform Security Processor  | 6     |            | [DDBB319D93](<All In One/Dell/Inspiron/Inspiron 3475 AIO/B6D9BD539D6C/DEBIAN-12/6.1.0-21-AMD64/X86_64/DDBB319D93>) |
| 1022:15df | 103c:84ef | AMD              | Family 17h (Models 10h-1fh) Platf... | 6     | ccp        | [C7427AE782](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/4CBC289D180C/ZORIN-17/6.8.0-40-GENERIC/X86_64/C7427AE782>) |
| 1022:15df | 103c:86f1 | AMD              | Family 17h (Models 10h-1fh) Platf... | 6     | ccp        | [B322E697B4](<All In One/Hewlett-Packard/All-in-One/All-in-One 27-dp0xxx/AA0F57A357A5/ZORIN-17/6.5.0-26-GENERIC/X86_64/B322E697B4>) |
| 8086:0f18 |           | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | mei_txe    | [DD0DFFA557](<All In One/Acer/Aspire/Aspire Z1-601/F2C9FDE7700C/ROSA-12.3/5.10.155-GENERIC-1ROSA2021.1-X86_64/X86_64/DD0DFFA557>) |
| 8086:0f18 | 1025:085f | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | mei_txe    | [59FB4C7892](<All In One/Acer/Aspire/Aspire ZC-606/9D356332373D/VOID-ROLLING/6.6.52_1/X86_64/59FB4C7892>) |
| 1022:1537 | 103c:2b2f | AMD              | Kabini/Mullins PSP-Platform Secur... | 5     | ccp        | [006B770F80](<All In One/Hewlett-Packard/18/18-4415la/B52844F55842/ZORIN-17/6.8.0-47-GENERIC/X86_64/006B770F80>) |
| 1022:1578 | 1028:07e3 | AMD              | Carrizo Platform Security Processor  | 5     |            | [DFAE42FB86](<All In One/Dell/Inspiron/Inspiron 24 5475/F5AB492D9E00/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/DFAE42FB86>) |
| 1022:1578 | 17aa:36bd | AMD              | Carrizo Platform Security Processor  | 5     |            | [D68501A3D9](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 510-23ASR F0CE002DAU/3B2CB02D55FF/DEBIAN-12/6.1.0-13-AMD64/X86_64/D68501A3D9>) |
| 1022:15df | 103c:86ee | AMD              | Family 17h (Models 10h-1fh) Platf... | 5     | ccp        | [B32F215A0E](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-d0xxx/CF27A731CFBC/ARCO-ROLLING/6.11.2-2-CACHYOS/X86_64/B32F215A0E>) |
| 1022:15df | 17aa:3746 | AMD              | Family 17h (Models 10h-1fh) Platf... | 5     | ccp        | [E9064CFEFC](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 27ALC6 F0FY006NPG/65AA3F0EC3FC/LMDE-5/5.10.0-28-AMD64/X86_64/E9064CFEFC>) |
| 8086:0f18 | 1297:2041 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 5     | mei_txe    | [02E77E625F](<All In One/Positivo/DC8/DC8BT11TV/CC98101BF15F/LUBUNTU-22.10/5.19.0-26-GENERIC/X86_64/02E77E625F>) |
| 8086:0f18 | 17aa:36a8 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 5     | mei_txe    | [837C6C4BE9](<All In One/Lenovo/S20-00/S20-00 F0AY007RRK/A53BFEE0ED22/POP!_OS-22.04/6.0.6-76060006-GENERIC/X86_64/837C6C4BE9>) |
| 8086:2298 | 1025:1065 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | mei_txe    | [7C92D3C678](<All In One/Acer/Aspire/Aspire C20-720/D3D94E225FA6/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/7C92D3C678>) |
| 8086:2298 | 1297:2053 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | mei_txe    | [95E8BED16F](<All In One/Positivo/DH8/DH8BW01/5F022083C428/KDE-NEON-20.04/5.15.0-50-GENERIC/X86_64/95E8BED16F>) |
| 8086:0f18 | 103c:2b0c | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 4     | mei_txe    | [CE31398BF7](<All In One/Hewlett-Packard/18/18-4221la/473D2B4042C4/OPENMANDRIVA-23.08/6.4.11-DESKTOP-1OMV2390/X86_64/CE31398BF7>) |
| 8086:2298 | 1025:0992 | Intel            | Atom/Celeron/Pentium Processor x5... | 4     | mei_txe    | [1485AD36A9](<All In One/Acer/Aspire/Aspire ZC-700G/1E352591F189/ARCH-ROLLING/6.1.2-ARCH1-1/X86_64/1485AD36A9>) |
| 1022:1537 | 103c:2b42 | AMD              | Kabini/Mullins PSP-Platform Secur... | 3     | ccp        | [7F7AA21ABC](<All In One/Hewlett-Packard/23/23-q012a/F2A4DC9FD55D/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/7F7AA21ABC>) |
| 1022:1578 | 1028:0855 | AMD              | Carrizo Platform Security Processor  | 3     |            | [148CAF0684](<All In One/Dell/Inspiron/Inspiron 3275 AIO/B05F589A0D42/XERO-ROLLING/6.6.4-ARCH1-1/X86_64/148CAF0684>) |
| 1022:1578 | 103c:81b9 | AMD              | Carrizo Platform Security Processor  | 3     |            | [CB43F1497C](<All In One/Hewlett-Packard/24/24-b014a/AA21B089568A/ULTRAMARINE-39/6.8.4-200.FC39.X86_64/X86_64/CB43F1497C>) |
| 1022:1578 | 103c:8374 | AMD              | Carrizo Platform Security Processor  | 3     |            | [9FE1F0456A](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-r0xx/F5CD64159772/GARUDA-ROLLING/6.12.1-ZEN1-1-ZEN/X86_64/9FE1F0456A>) |
| 1022:1578 | 17aa:36be | AMD              | Carrizo Platform Security Processor  | 3     |            | [0759C30DD9](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 510-22ASR F0CC001BIX/E61608155EDF/UBUNTU-22.10/5.19.0-31-GENERIC/X86_64/0759C30DD9>) |
| 1022:15df | 103c:8449 | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     | ccp        | [FA5E880618](<All In One/Hewlett-Packard/8449/8449 00100/7A57A62DAD2D/OPENMANDRIVA-23.09/6.5.0-DESKTOP-1OMV2390/X86_64/FA5E880618>) |
| 1022:15df | 103c:8582 | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     | ccp        | [4977F9D91D](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c1xx/674AC15919F3/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/4977F9D91D>) |
| 1022:15df | 1043:1832 | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     | ccp        | [F6285D1100](<All In One/ASUSTek Computer/ASUS/ASUS ZEN AIO M5401WUA_M5401WUA/525FB10EAB16/DEBIAN-UNSTABLE/6.2.9-4-LIQUORIX-AMD64/X86_64/F6285D1100>) |
| 1022:15df | 17aa:36f5 | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     | ccp        | [EB38810FB8](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-24ARR F0DN006KGE/1D5E59C5CB5F/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/EB38810FB8>) |
| 1022:15df | 17aa:371d | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     | ccp        | [7EBF0B1DD0](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 22ADA05 F0EX0081IN/99B2864404AC/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/7EBF0B1DD0>) |
| 1022:1649 | 1022:1649 | AMD              | Family 19h PSP/CCP                   | 3     | ccp        | [7C37FCE41A](<All In One/Others/FP7/FP7R2AIO/73A1EB679CBF/DEBIAN-12/6.12.8-X64V3-XANMOD1/X86_64/7C37FCE41A>) |
| 8086:0f18 | 1019:7ece | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     | mei_txe    | [075A439EBE](<All In One/Medion/BTDD-TI/BTDD-TI/C4D39B85284A/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/075A439EBE>) |
| 8086:0f18 | 1025:0994 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     | mei_txe    | [6247D83BAB](<All In One/Acer/Aspire/Aspire Z1-611/A6EFF7123453/LINUXMINT-19.1/4.15.0-128-GENERIC/X86_64/6247D83BAB>) |
| 8086:2298 | 8086:1e8b | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | mei_txe    | [EC8A440630](<All In One/Multilaser/UB82/UB82X/29A5540764F5/ZORIN-17/6.8.0-49-GENERIC/X86_64/EC8A440630>) |
| 1022:1486 | 1022:1486 | AMD              | Starship/Matisse Cryptographic Co... | 2     | ccp        | [7D0089CC2A](<All In One/Acidanthera/iMacPro1/iMacPro1,1/E475E9B777A3/ENDEAVOUROS-ROLLING/6.9.3-ARCH1-1/X86_64/7D0089CC2A>) |
| 1022:1537 | 103c:2b54 | AMD              | Kabini/Mullins PSP-Platform Secur... | 2     | ccp        | [B47807A201](<All In One/Hewlett-Packard/20/20-e001la/E3C43A35761C/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/B47807A201>) |

### Firewire controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 11c1:5901 | 11c1:5900 | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 631   | firewir... | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 104c:823f |           | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 266   | firewir... | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 11c1:5811 | 11c1:5811 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 41    | firewir... | [DE3A243820](<All In One/Apple/iMac5/iMac5,1/1F7269B01AAF/DEBIAN-11/5.10.0-33-686-PAE/I686/DE3A243820>) |
| 1180:e832 | 104d:9060 | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 13    | firewir... | [18C8665A8A](<All In One/Sony/VPCL14/VPCL14S1E/05E16BA420D0/LINUXMINT-21.3/5.15.0-121-GENERIC/X86_64/18C8665A8A>) |
| 1180:e832 | 104d:907e | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 10    | firewir... | [A8F1E64B41](<All In One/Sony/VPCL236/VPCL236FX/7D6F7AF3086A/ZORIN-17/6.8.0-49-GENERIC/X86_64/A8F1E64B41>) |
| 1180:e832 | 104d:9097 | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 7     | firewir... | [2EBADEA317](<All In One/Sony/SVL2411/SVL24117FLB/B337A07B7653/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/2EBADEA317>) |
| 197b:2380 | 103c:1489 | JMicron Techn... | IEEE 1394 Host Controller            | 7     | firewir... | [C53E87BCE8](<All In One/Hewlett-Packard/Compaq/Compaq 6000 Pro AiO Brazil PC/FB69A2D0E244/LINUXMINT-20.3/5.4.0-159-GENERIC/X86_64/C53E87BCE8>) |
| 1180:e832 | 104d:9074 | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 6     | firewir... | [5BB2E62791](<All In One/Sony/VPCJ115/VPCJ115FX/D5A02AFB0F0F/FEDORA-40/6.10.11-200.FC40.X86_64/X86_64/5BB2E62791>) |
| 104c:8025 |           | Texas Instrum... | TSB82AA2 IEEE-1394b Link Layer Co... | 5     | firewir... | [598F3CFE61](<All In One/Apple/iMac6/iMac6,1/06954601F29C/UBUNTU-24.04/6.8.0-47-GENERIC/X86_64/598F3CFE61>) |
| 1180:0832 | 104d:9044 | Ricoh            | R5C832 IEEE 1394 Controller          | 5     | firewir... | [5CD160EA53](<All In One/Sony/VGC-JS1/VGC-JS1E_S/2F2CC13FD639/FEDORA-38/6.4.15-200.FC38.X86_64/X86_64/5CD160EA53>) |
| 197b:2380 | 17aa:3602 | JMicron Techn... | IEEE 1394 Host Controller            | 5     | firewir... | [195EC7CB8C](<All In One/Lenovo/10051/10051/11244BE45969/LINUXMINT-20.3/5.4.0-126-GENERIC/X86_64/195EC7CB8C>) |
| 1180:0832 | 104d:9043 | Ricoh            | R5C832 IEEE 1394 Controller          | 4     | firewir... | [653A82E6B9](<All In One/Sony/VGC-LV180/VGC-LV180ME/8D99388DD758/XEROLINUX-KDE-ROLLING/6.4.11-ARCH2-1/X86_64/653A82E6B9>) |
| 11c1:5901 | c111:0159 | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 4     | firewir... | [04577F93C3](<All In One/Apple/iMac14/iMac14,2/1A7707A79A3C/FEDORA-39/6.7.7-200.FC39.X86_64/X86_64/04577F93C3>) |
| 197b:2380 | 103c:3561 | JMicron Techn... | IEEE 1394 Host Controller            | 3     | firewir... | [AEF249E21A](<All In One/Hewlett-Packard/Z1/Z1 Workstation/8DD1D695BD68/ZORIN-16/5.15.0-88-GENERIC/X86_64/AEF249E21A>) |
| 1180:e832 | 104d:908e | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 2     | firewir... | [E43A2C01EB](<All In One/Sony/VPCL22/VPCL22Z1R/BC94F4FEC1E7/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/E43A2C01EB>) |
| 1217:10f7 | 17aa:3068 | O2 Micro         | 1394 OHCI Compliant Host Controller  | 2     | firewir... | [988ED124EE](<All In One/Lenovo/xxxx/xxxx IdeaCentre A300/598D74A4FC33/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/988ED124EE>) |
| 1217:13f7 | 1bcf:a013 | O2 Micro         | 1394 OHCI Compliant Host Controller  | 2     | firewir... | [1494683BB9](<All In One/NEC Computers/PC-VN770/PC-VN770DS3ER/18CEF0AA43DB/UBUNTU-20.04/5.8.0-48-GENERIC/X86_64/1494683BB9>) |
| 104c:8024 | 1458:1000 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 1     | firewir... | [1786CF3D3D](<All In One/Gigabyte Technology/X58/X58A-UD3R/37288E45C1AD/ROSA-13.0/6.6.20-GENERIC-3ROSA2023.1-X86_64/X86_64/1786CF3D3D>) |
| 104c:8024 | 9005:0030 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 1     | firewir... | [098FE372A3](<All In One/Acidanthera/iMac14/iMac14,4/E2C69985CC45/GENTOO-2.6/5.4.97-GENTOO_DQ87PG/X86_64/098FE372A3>) |
| 104c:8029 | 107b:4009 | Texas Instrum... | PCI4510 IEEE-1394 Controller         | 1     | firewir... | [0213C3A21C](<All In One/Gateway/PROFILE5/PROFILE5.5/89C7C3620F05/UBUNTU-18.04/4.15.0-122-GENERIC/I686/0213C3A21C>) |
| 1106:3401 | 17aa:3603 | VIA Technologies | FireWire (IEEE 1394)                 | 1     | firewir... | [8399296D51](<All In One/Lenovo/IdeaCentre/IdeaCentre B305 10052/A8184A7A8382/UBUNTU-20.04/5.8.0-55-GENERIC/X86_64/8399296D51>) |
| 1106:3401 | 17aa:3608 | VIA Technologies | FireWire (IEEE 1394)                 | 1     | firewir... | [69574214D7](<All In One/Lenovo/IdeaCentre/IdeaCentre A700 10050/51968677EC4C/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/69574214D7>) |
| 1180:0552 | 1033:886f | Ricoh            | R5C552 IEEE 1394 Controller          | 1     | firewir... | [86771347FB](<All In One/NEC Computers/PC-GV58/PC-GV58ZYCAA/96538F2FC249/UBUNTU-19.04/5.0.0-13-GENERIC/X86_64/86771347FB>) |
| 1217:10f7 | 1033:8959 | O2 Micro         | 1394 OHCI Compliant Host Controller  | 1     | firewir... | [6F4A2D24C1](<All In One/NEC Computers/PC-VW770/PC-VW770CS6B/CD4FBB5FF80F/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/6F4A2D24C1>) |
| 197b:2380 | 17aa:360f | JMicron Techn... | IEEE 1394 Host Controller            | 1     | firewir... | [7CCE3E46D0](<All In One/Lenovo/IdeaCentre/IdeaCentre B310/F1C31A285B2C/ARCH-ROLLING/6.8.1-ARCH1-1/X86_64/7CCE3E46D0>) |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1577 | 1022:1577 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 26    |            | [F781FACD17](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-22AST F0D6000PLD/3E21F3CA09A6/UBUNTU-24.10/6.11.0-8-GENERIC/X86_64/F781FACD17>) |
| 1022:1451 | 1022:1451 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 2     |            | [D05A394FC8](<All In One/Acidanthera/iMacPro1/iMacPro1,1/9C6521899F59/CHIMERAOS-46/6.8.0-RC2-CHOS1-CHIMERAOS-1/X86_64/D05A394FC8>) |
| 1022:1419 | 1022:1419 | AMD              | Family 15h (Models 10h-1fh) I/O M... | 1     |            | [53E73F6DD7](<All In One/Gigabyte Technology/GB-A5/GB-A5DNK-RH/2D59EF3CA1FB/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/53E73F6DD7>) |
| 1022:1423 | 1022:1423 | AMD              | Family 15h (Models 30h-3fh) I/O M... | 1     |            | [1ACDBB1C74](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 700-24AGR F0BG000DGE/D2D68382813A/LINUXMINT-20.3/5.4.0-169-GENERIC/X86_64/1ACDBB1C74>) |
| 1022:1423 | 17aa:368f | AMD              | Family 15h (Models 30h-3fh) I/O M... | 1     |            | [58DDD6F565](<All In One/Lenovo/B50-35/B50-35 F0AV0025GE/7D201658F55F/ROSA-2014.1/4.9.76-NRJ-DESKTOP-1ROSA-X86_64/X86_64/58DDD6F565>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0102 | 8086:2010 | Intel            | 2nd Generation Core Processor Fam... | 152   | i915       | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 1002:9583 | 106b:0083 | AMD              | RV630/M76 [Mobility Radeon HD 260... | 143   | radeon     | [03D550B439](<All In One/Apple/iMac7/iMac7,1/04551A46F1B0/ELEMENTARY-7.1/6.8.0-49-GENERIC/X86_64/03D550B439>) |
| 8086:0102 | 106b:0000 | Intel            | 2nd Generation Core Processor Fam... | 134   | i915       | [8B589149FB](<All In One/Apple/iMac12/iMac12,2/CB916DA645BF/KUBUNTU-24.04/6.8.0-50-GENERIC/X86_64/8B589149FB>) |
| 1002:6741 | 106b:6741 | AMD              | Whistler [Radeon HD 6630M/6650M/6... | 119   | radeon     | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 1002:9488 | 106b:00b6 | AMD              | RV730/M96-XT [Mobility Radeon HD ... | 107   | radeon     | [E82B0C22FB](<All In One/Apple/iMac10/iMac10,1/99E4987A298C/DEBIAN-12/6.1.0-28-AMD64/X86_64/E82B0C22FB>) |
| 1002:6740 | 106b:6740 | AMD              | Whistler [Radeon HD 6730M/6770M/7... | 97    | radeon     | [8B589149FB](<All In One/Apple/iMac12/iMac12,2/CB916DA645BF/KUBUNTU-24.04/6.8.0-50-GENERIC/X86_64/8B589149FB>) |
| 1002:94c8 | 106b:0084 | AMD              | RV610/M74 [Mobility Radeon HD 240... | 87    | radeon     | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 10de:0867 | 106b:00ad | Nvidia           | C79 [GeForce 9400]                   | 76    | nouveau    | [F3660A5D7B](<All In One/Apple/iMac9/iMac9,1/50AE0E9B32CE/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/F3660A5D7B>) |
| 1002:6720 | 106b:0b00 | AMD              | Blackcomb [Radeon HD 6970M/6990M]    | 67    | radeon     | [C4F94E8617](<All In One/Apple/iMac12/iMac12,2/40C413A46753/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/C4F94E8617>) |
| 8086:9bc8 |           | Intel            | CometLake-S GT2 [UHD Graphics 630]   | 60    | i915       | [F969D9FB85](<All In One/ICL/RAY/RAY Si105.Mi/2E3E3E31C611/ROSA-12/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/F969D9FB85>) |
| 8086:0d22 | 106b:0122 | Intel            | Crystal Well Integrated Iris Pro ... | 59    | i915       | [8230B0CF45](<All In One/Apple/iMac14/iMac14,1/4D0F5DF66177/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/8230B0CF45>) |
| 10de:0869 | 106b:00b4 | Nvidia           | MCP7A [GeForce 9400]                 | 52    | nouveau    | [77CD5B5988](<All In One/Apple/iMac10/iMac10,1/4DB25FD3E39F/ZORIN-17/6.8.0-45-GENERIC/X86_64/77CD5B5988>) |
| 8086:1622 | 106b:014f | Intel            | Iris Pro Graphics 6200               | 44    | i915       | [500ACCCF00](<All In One/Apple/iMac16/iMac16,2/D9F8E706C1F9/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/500ACCCF00>) |
| 1002:944a | 106b:00b5 | AMD              | RV770/M98L [Mobility Radeon HD 4850] | 38    | radeon     | [46FEFF6CC6](<All In One/Apple/iMac11/iMac11,1/8EA27F558F5E/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/46FEFF6CC6>) |
| 1002:68a1 | 106b:00cc | AMD              | Broadway PRO [Mobility Radeon HD ... | 37    | radeon     | [5E464458DB](<All In One/Apple/iMac11/iMac11,3/1626D13A06C7/UBUNTU-20.04/5.15.0-130-GENERIC/X86_64/5E464458DB>) |
| 10de:0fea | 106b:011f | Nvidia           | GK107M [GeForce GT 755M Mac Edition] | 37    | nouveau    | [8485C9B6A3](<All In One/Apple/iMac14/iMac14,2/DE6A385E2C03/ARCH-ROLLING/6.10.14-273-TKG-EEVDF/X86_64/8485C9B6A3>) |
| 1002:67ef | 106b:016b | AMD              | Baffin [Radeon RX 460/560D / Pro ... | 36    | amdgpu     | [9C21FDA832](<All In One/Apple/iMac18/iMac18,2/9742FAAE1644/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9C21FDA832>) |
| 1002:71c5 | 106b:0080 | AMD              | RV530/M56-P [Mobility Radeon X1600]  | 36    | radeon     | [DE3A243820](<All In One/Apple/iMac5/iMac5,1/1F7269B01AAF/DEBIAN-11/5.10.0-33-686-PAE/I686/DE3A243820>) |
| 10de:0fd8 | 106b:0109 | Nvidia           | GK107M [GeForce GT 640M Mac Edition] | 34    | nvidia     | [0BB2743C5F](<All In One/Apple/iMac13/iMac13,1/9790142699C8/ZORIN-17/6.8.0-49-GENERIC/X86_64/0BB2743C5F>) |
| 1002:68c0 | 106b:00d2 | AMD              | Madison [Mobility Radeon HD 5730 ... | 28    | radeon     | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 8086:0a26 | 106b:013c | Intel            | Haswell-ULT Integrated Graphics C... | 26    | i915       | [9F2B2370D2](<All In One/Apple/iMac14/iMac14,4/C04E3A92385A/DEBIAN/6.11.10-AMD64/X86_64/9F2B2370D2>) |
| 10de:0fe9 | 106b:011e | Nvidia           | GK107M [GeForce GT 750M Mac Edition] | 24    | nouveau    | [EFEE186DC5](<All In One/Apple/iMac14/iMac14,3/0EF811D6D010/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.11.8-1-DEFAULT/X86_64/EFEE186DC5>) |
| 10de:119d | 106b:0120 | Nvidia           | GK104M [GeForce GTX 775M Mac Edit... | 24    | nouveau    | [4AE0FF6BB2](<All In One/Apple/iMac14/iMac14,2/466DEE2DECC3/ZORIN-17/6.8.0-49-GENERIC/X86_64/4AE0FF6BB2>) |
| 1002:67df | 106b:0163 | AMD              | Ellesmere [Radeon RX 470/480/570/... | 23    | amdgpu     | [6FEA2B9985](<All In One/Apple/iMac18/iMac18,3/7BB91A8EC37E/ARCH-ROLLING/6.12.4-ARCH1-1/X86_64/6FEA2B9985>) |
| 1002:6640 | 106b:014b | AMD              | Saturn XT [FirePro M6100]            | 21    | radeon     | [B9F265012B](<All In One/Apple/iMac17/iMac17,1/2B3F1AF30BB3/ELEMENTARY-7.1/6.8.0-45-GENERIC/X86_64/B9F265012B>) |
| 8086:5926 | 106b:017e | Intel            | Iris Plus Graphics 640               | 21    | i915       | [727B7184C9](<All In One/Apple/iMac18/iMac18,1/169F9C1861CD/DEBIAN-12/6.1.0-27-AMD64/X86_64/727B7184C9>) |
| 1002:15d8 | 103c:86f3 | AMD              | Picasso/Raven 2 [Radeon Vega Seri... | 20    | amdgpu     | [2F05B30C3F](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-dp0xxx/E1C03E22AF48/OPENMANDRIVA-24.03/6.8.1-DESKTOP-3OMV2490/X86_64/2F05B30C3F>) |
| 1002:67df | 106b:0161 | AMD              | Ellesmere [Radeon RX 470/480/570/... | 20    | amdgpu     | [EDA26270C4](<All In One/Apple/iMac18/iMac18,3/BEED7205CB3E/ARCH-ROLLING/6.12.6-ARCH1-1/X86_64/EDA26270C4>) |
| 1002:67ef | 106b:0197 | AMD              | Baffin [Radeon RX 460/560D / Pro ... | 20    | amdgpu     | [166D603A90](<All In One/Apple/iMac19/iMac19,2/FBA23128DEDB/MANJARO/6.10.13-3-MANJARO/X86_64/166D603A90>) |
| 1002:67ef | 106b:019f | AMD              | Baffin [Radeon RX 460/560D / Pro ... | 20    | amdgpu     | [0C36BC1E93](<All In One/Apple/iMac19/iMac19,2/C074723931A0/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/0C36BC1E93>) |
| 1002:67ef | 106b:016a | AMD              | Baffin [Radeon RX 460/560D / Pro ... | 19    | amdgpu     | [5F72A32D95](<All In One/Apple/iMac18/iMac18,2/AB2959FA96D2/OPENSUSE-MICROOS-XXXXXXXX/6.11.0-1-DEFAULT/X86_64/5F72A32D95>) |
| 1002:98e4 | 103c:8430 | AMD              | Stoney [Radeon R2/R3/R4/R5 Graphics] | 19    | amdgpu     | [3EA46622E6](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/E4E878423146/OPENMANDRIVA-24.08/6.10.1-DESKTOP-1OMV2490/X86_64/3EA46622E6>) |
| 8086:0102 | 1028:0511 | Intel            | 2nd Generation Core Processor Fam... | 19    | i915       | [EC101E6744](<All In One/Dell/Inspiron/Inspiron One 2320/3D9ADF185AD6/ARCH-ROLLING/6.12.7-ARCH1-1/X86_64/EC101E6744>) |
| 8086:0412 | 1028:05a7 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 19    | i915       | [F866E174C2](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/5BD2C4C72DD4/FEDORA-40/6.10.8-200.FC40.X86_64/X86_64/F866E174C2>) |
| 8086:5917 | 103c:84de | Intel            | UHD Graphics 620                     | 19    | i915       | [A7F55BE076](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/F6FC816725AE/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/A7F55BE076>) |
| 8086:1912 | 1028:06c5 | Intel            | HD Graphics 530                      | 18    | i915       | [CCDA6EA567](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/2A418C925C5B/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/CCDA6EA567>) |
| 8086:3e92 | 103c:84ee | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 18    | i915       | [597321B19E](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/07E9499C7A2C/KDE-NEON-24.04/6.8.0-49-GENERIC/X86_64/597321B19E>) |
| 1002:6819 | 106b:014e | AMD              | Pitcairn PRO [Radeon HD 7850 / R7... | 17    | radeon     | [B63F41C5EA](<All In One/Apple/iMac17/iMac17,1/F3A6F67D4FE6/ZORIN-17/6.8.0-40-GENERIC/X86_64/B63F41C5EA>) |
| 10de:119e | 106b:0121 | Nvidia           | GK104M [GeForce GTX 780M Mac Edit... | 17    | nouveau    | [114CAB1A48](<All In One/Apple/iMac14/iMac14,2/B6E03FF5EBE4/ELEMENTARY-7.1/6.8.0-49-GENERIC/X86_64/114CAB1A48>) |
| 8086:22b1 | 103c:81bb | Intel            | Atom/Celeron/Pentium Processor x5... | 17    | i915       | [A802D08306](<All In One/Hewlett-Packard/22/22-b015ur/5883A5C263EF/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/A802D08306>) |
| 1002:67df | 106b:019e | AMD              | Ellesmere [Radeon RX 470/480/570/... | 16    | amdgpu     | [1877B2792F](<All In One/Apple/iMac19/iMac19,1/016A1F8C4B8D/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/1877B2792F>) |
| 8086:0416 | 1028:05db | Intel            | 4th Gen Core Processor Integrated... | 16    | i915       | [AAD8987195](<All In One/Dell/Inspiron/Inspiron 2350/537D2F43CC7A/MX-23/6.1.0-10-AMD64/X86_64/AAD8987195>) |
| 8086:1912 | 103c:2b3e | Intel            | HD Graphics 530                      | 16    | i915       | [72FDDCCE30](<All In One/Hewlett-Packard/27/27-p014/5E43D288C796/OPENSUSE-LEAP-15.6/6.4.0-150600.23.30-DEFAULT/X86_64/72FDDCCE30>) |
| 8086:3185 | 1854:0308 | Intel            | GeminiLake [UHD Graphics 600]        | 15    | i915       | [A595C7B829](<All In One/LG Electronics/22V280/22V280-L.BJ31P1/BE8548B5DD51/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/A595C7B829>) |
| 8086:3e92 | 1019:a5a1 | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 15    | i915       | [B97AB9E5CA](<All In One/3Logic Group/Graviton/Graviton/223493B1237A/KOMETA-P10/5.10.109-STD-DEF-ALT1/X86_64/B97AB9E5CA>) |
| 8086:5917 | 1025:1287 | Intel            | UHD Graphics 620                     | 15    | i915       | [08963EC448](<All In One/Acer/Aspire/Aspire C24-865/78DC8340D315/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/08963EC448>) |
| 1002:67df | 106b:0162 | AMD              | Ellesmere [Radeon RX 470/480/570/... | 14    | amdgpu     | [62CC8983B2](<All In One/Apple/iMac18/iMac18,3/EF1FC4364571/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/62CC8983B2>) |
| 10de:0609 | 106b:00a7 | Nvidia           | G92M [GeForce 8800M GTS]             | 14    | nouveau    | [1D1DAF9285](<All In One/Apple/iMac8/iMac8,1/14F211319CBB/ZORIN-12/4.15.0-142-GENERIC/X86_64/1D1DAF9285>) |
| 10de:0fd5 | 106b:010a | Nvidia           | GK107M [GeForce GT 650M Mac Edition] | 14    | nouveau    | [5EF202CE64](<All In One/Apple/iMac13/iMac13,1/090F2294A5E2/DEBIAN-12/6.1.0-18-AMD64/X86_64/5EF202CE64>) |
| 10de:11a3 | 106b:010d | Nvidia           | GK104M [GeForce GTX 680MX]           | 14    | nvidia     | [1FAF24F4B7](<All In One/Apple/iMac13/iMac13,2/7FD86058EEE9/LUBUNTU-22.04/6.8.0-40-GENERIC/X86_64/1FAF24F4B7>) |

### Iommu (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15d1 | 1022:15d1 | AMD              | Raven/Raven2 IOMMU                   | 54    |            | [7EBF0B1DD0](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 22ADA05 F0EX0081IN/99B2864404AC/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/7EBF0B1DD0>) |
| 1022:1631 | 1022:1631 | AMD              | Renoir/Cezanne IOMMU                 | 9     |            | [837B2CFE99](<All In One/Others/Others/Others/58E4FC6F62D5/MANJARO-24.0.8/6.9.12-3-MANJARO/X86_64/837B2CFE99>) |
| 1022:1631 | 103c:8924 | AMD              | Renoir/Cezanne IOMMU                 | 8     |            | [67175C1B82](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One Desktop 24-ca0xxx/15CC8A5959D7/DEBIAN-12/6.1.0-27-AMD64/X86_64/67175C1B82>) |
| 1022:1631 | 1028:0b83 | AMD              | Renoir/Cezanne IOMMU                 | 7     |            | [D19E3017AD](<All In One/Dell/Inspiron/Inspiron 24 5415 All-in-One/5E02E56F3BDD/DEBIAN-12/6.1.0-26-AMD64/X86_64/D19E3017AD>) |
| 1022:1631 | 17aa:371c | AMD              | Renoir/Cezanne IOMMU                 | 7     |            | [E1B1540113](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 24ARE05 F0EW004WUK/5E9CA431A68F/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E1B1540113>) |
| 1022:1577 | 1028:0854 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 6     |            | [DDBB319D93](<All In One/Dell/Inspiron/Inspiron 3475 AIO/B6D9BD539D6C/DEBIAN-12/6.1.0-21-AMD64/X86_64/DDBB319D93>) |
| 1022:1481 | 1022:1481 | AMD              | Starship/Matisse IOMMU               | 5     |            | [7D0089CC2A](<All In One/Acidanthera/iMacPro1/iMacPro1,1/E475E9B777A3/ENDEAVOUROS-ROLLING/6.9.3-ARCH1-1/X86_64/7D0089CC2A>) |
| 1022:1577 | 1028:07e3 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 5     |            | [DFAE42FB86](<All In One/Dell/Inspiron/Inspiron 24 5475/F5AB492D9E00/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/DFAE42FB86>) |
| 1022:1631 | 103c:86ee | AMD              | Renoir/Cezanne IOMMU                 | 5     |            | [B32F215A0E](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-d0xxx/CF27A731CFBC/ARCO-ROLLING/6.11.2-2-CACHYOS/X86_64/B32F215A0E>) |
| 1022:1631 | 17aa:3746 | AMD              | Renoir/Cezanne IOMMU                 | 5     |            | [E9064CFEFC](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 27ALC6 F0FY006NPG/65AA3F0EC3FC/LMDE-5/5.10.0-28-AMD64/X86_64/E9064CFEFC>) |
| 1022:1451 | 1028:07e4 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 4     |            | [C15583FC1C](<All In One/Dell/Inspiron/Inspiron 27 7775/66E01AABAA85/FEDORA-38/6.4.12-200.FC38.X86_64/X86_64/C15583FC1C>) |
| 1022:14b6 | 1022:14b6 | AMD              | Family 17h-19h IOMMU                 | 3     |            | [7C37FCE41A](<All In One/Others/FP7/FP7R2AIO/73A1EB679CBF/DEBIAN-12/6.12.8-X64V3-XANMOD1/X86_64/7C37FCE41A>) |
| 1022:1577 | 1028:0855 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 3     |            | [148CAF0684](<All In One/Dell/Inspiron/Inspiron 3275 AIO/B05F589A0D42/XERO-ROLLING/6.6.4-ARCH1-1/X86_64/148CAF0684>) |
| 1022:1631 | 1043:1832 | AMD              | Renoir/Cezanne IOMMU                 | 3     |            | [F6285D1100](<All In One/ASUSTek Computer/ASUS/ASUS ZEN AIO M5401WUA_M5401WUA/525FB10EAB16/DEBIAN-UNSTABLE/6.2.9-4-LIQUORIX-AMD64/X86_64/F6285D1100>) |
| 1022:1577 | 17aa:36c6 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 2     |            | [8A4DFA9648](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 310-20ASR F0CK001JID/8799A4447AF9/OPENMANDRIVA-23.10/6.5.5-DESKTOP-1OMV2390/X86_64/8A4DFA9648>) |
| 1022:1577 | 17aa:36ec | AMD              | Family 15h (Models 60h-6fh) I/O M... | 2     |            | [2CFA2D338E](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 330-20AST F0D8001LUS/36DA6D8B2B0D/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/2CFA2D338E>) |
| 1022:1631 | 103c:89dc | AMD              | Renoir/Cezanne IOMMU                 | 2     |            | [8DE41C667E](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One Desktop 24-ca1xxx/8D49B03A4AB2/UBUNTU-22.04/6.2.0-36-GENERIC/X86_64/8DE41C667E>) |
| 1022:1631 | 17aa:3734 | AMD              | Renoir/Cezanne IOMMU                 | 2     |            | [B153378DAB](<All In One/Lenovo/Yoga/Yoga AIO 7 27ARH6 F0FN000NMT/C9B8617D0FC8/ENDEAVOUROS-ROLLING/6.5.9-ARCH2-1/X86_64/B153378DAB>) |
| 1022:1631 | 17aa:3744 | AMD              | Renoir/Cezanne IOMMU                 | 2     |            | [765A9D56C1](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 24ALC6 F0G100NALD/E6B295C3FD14/DEBIAN-12/6.1.0-13-AMD64/X86_64/765A9D56C1>) |
| 1022:1481 | 1043:87c0 | AMD              | Starship/Matisse IOMMU               | 1     |            | [577AD83B8F](<All In One/Acidanthera/iMacPro1/iMacPro1,1/6286842FEC0E/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/577AD83B8F>) |
| 1022:14b6 | 1043:223b | AMD              | Family 17h-19h IOMMU                 | 1     |            | [0FFCB537C4](<All In One/ASUSTek Computer/ASUS/ASUS AIO M3402WFA_M3402WFA/ACAF112F1845/UBUNTU-22.04/6.5.0-35-GENERIC/X86_64/0FFCB537C4>) |
| 1022:14b6 | 1043:224b | AMD              | Family 17h-19h IOMMU                 | 1     |            | [CC3338DA7A](<All In One/ASUSTek Computer/ASUS/ASUS AIO M3702WFA_M3702WFA/D9B0B1FE5477/LINUXMINT-22/6.8.0-39-GENERIC/X86_64/CC3338DA7A>) |
| 1022:14b6 | 17aa:3763 | AMD              | Family 17h-19h IOMMU                 | 1     |            | [8DF8DCD26B](<All In One/Lenovo/Yoga/Yoga AIO 7 27ARH7 F0GS0056TX/6B2FAAF53605/UBUNTU-22.04/6.5.0-18-GENERIC/X86_64/8DF8DCD26B>) |
| 1022:1631 | 1043:1a72 | AMD              | Renoir/Cezanne IOMMU                 | 1     |            | [E593179048](<All In One/ASUSTek Computer/ASUS/ASUS AIO M3400WUA_M3400WUA/C57F5A924964/ROSA-12.3/5.10.155-GENERIC-1ROSA2021.1-X86_64/X86_64/E593179048>) |
| 1022:1631 | 1043:87e1 | AMD              | Renoir/Cezanne IOMMU                 | 1     |            | [FCD01E22D7](<All In One/ASUSTek Computer/PRIME/PRIME B450M-A II/E71284EECA39/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/FCD01E22D7>) |
| 1022:1631 | 17aa:3751 | AMD              | Renoir/Cezanne IOMMU                 | 1     |            | [78D918F4D0](<All In One/Lenovo/Yoga/Yoga AIO 7 27ACH6 F0G7001MUS/DCDD76EB4114/FEDORA-40/6.9.11-200.FC40.X86_64/X86_64/78D918F4D0>) |
| 1022:1631 | 17aa:3777 | AMD              | Renoir/Cezanne IOMMU                 | 1     |            | [ED33639BE3](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 27ALC6 F0FY00NNUK/1B1EC250F927/ARCO-ROLLING/6.12.4-ZEN1-1-ZEN/X86_64/ED33639BE3>) |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:816c | 1025:1291 | Realtek Semic... | RTL8111xP IPMI interface             | 3     |            | [9949F21F98](<All In One/Acer/Veriton/Veriton Z4660G/D6F2FD870657/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/9949F21F98>) |
| 10ec:816c | 1025:1290 | Realtek Semic... | RTL8111xP IPMI interface             | 2     |            | [A27363041A](<All In One/Acer/Veriton/Veriton Z4860G/8955EDC1BE49/ENDLESS-3.9.1/5.8.0-14-GENERIC/X86_64/A27363041A>) |
| 10ec:816c | 10ec:0123 | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [2278A5C6EA](<All In One/Samsung Electronics/SUR/SUR40/9A8E67BB1389/DEBIAN-11/5.19.0-2-AMD64/X86_64/2278A5C6EA>) |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:816c | 1025:1071 | Realtek Semic... | RTL8111xP IPMI interface             | 3     |            | [910DA2B318](<All In One/Acer/Veriton/Veriton Z4820G/F80CAA7F129B/DEBIAN-12/6.1.0-4-AMD64/X86_64/910DA2B318>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10de:0a88 |           | Nvidia           | MCP79 Memory Controller              | 211   |            | [E82B0C22FB](<All In One/Apple/iMac10/iMac10,1/99E4987A298C/DEBIAN-12/6.1.0-28-AMD64/X86_64/E82B0C22FB>) |
| 10de:0a89 |           | Nvidia           | MCP79 Memory Controller              | 211   |            | [E82B0C22FB](<All In One/Apple/iMac10/iMac10,1/99E4987A298C/DEBIAN-12/6.1.0-28-AMD64/X86_64/E82B0C22FB>) |
| 10de:0a98 | 10de:cb79 | Nvidia           | MCP79 Memory Controller              | 211   |            | [E82B0C22FB](<All In One/Apple/iMac10/iMac10,1/99E4987A298C/DEBIAN-12/6.1.0-28-AMD64/X86_64/E82B0C22FB>) |
| 10de:0aa4 |           | Nvidia           | MCP79 Memory Controller              | 211   |            | [E82B0C22FB](<All In One/Apple/iMac10/iMac10,1/99E4987A298C/DEBIAN-12/6.1.0-28-AMD64/X86_64/E82B0C22FB>) |
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 162   |            | [9C21FDA832](<All In One/Apple/iMac18/iMac18,2/9742FAAE1644/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9C21FDA832>) |
| 8086:a36f |           | Intel            | Cannon Lake PCH Shared SRAM          | 79    |            | [0C36BC1E93](<All In One/Apple/iMac19/iMac19,2/C074723931A0/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/0C36BC1E93>) |
| 8086:43ef |           | Intel            | Tiger Lake-H Shared SRAM             | 73    |            | [F969D9FB85](<All In One/ICL/RAY/RAY Si105.Mi/2E3E3E31C611/ROSA-12/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/F969D9FB85>) |
| 8086:a36f | 8086:7270 | Intel            | Cannon Lake PCH Shared SRAM          | 64    |            | [9352E7ED07](<All In One/Dell/OptiPlex/OptiPlex 7460 AIO/AAD8696E4652/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9352E7ED07>) |
| 8086:a0ef |           | Intel            | Tiger Lake-LP Shared SRAM            | 31    |            | [8C98F96505](<All In One/Medion/E/E23405/C126BD27298A/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/8C98F96505>) |
| 8086:a2a1 | 1019:a5a1 | Intel            | 200 Series/Z370 Chipset Family Po... | 24    |            | [46658F67D3](<All In One/ICL/H310/H310SB-TM/298E8E81F4C1/ROSA-12/6.1.81-GENERIC-2ROSA2021.1-X86_64/X86_64/46658F67D3>) |
| 8086:9d21 | 8086:7270 | Intel            | Sunrise Point-LP PMC                 | 22    |            | [727B7184C9](<All In One/Apple/iMac18/iMac18,1/169F9C1861CD/DEBIAN-12/6.1.0-27-AMD64/X86_64/727B7184C9>) |
| 8086:34ef | 8086:7270 | Intel            | Ice Lake-LP DRAM Controller          | 21    |            | [C485E8AA2A](<All In One/iRU/P/P233/818E165023EF/ROSA-12.5.1/6.6.27-GENERIC-3ROSA2021.1-X86_64/X86_64/C485E8AA2A>) |
| 8086:7aa7 |           | Intel            | Alder Lake-S PCH Shared SRAM         | 21    |            | [B0BDA7B10B](<All In One/Acer/Veriton/Veriton Z2694G/992B643355D9/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/B0BDA7B10B>) |
| 8086:9d21 | 103c:84de | Intel            | Sunrise Point-LP PMC                 | 19    |            | [A7F55BE076](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/F6FC816725AE/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/A7F55BE076>) |
| 8086:a121 | 1028:06c5 | Intel            | 100 Series/C230 Series Chipset Fa... | 18    |            | [CCDA6EA567](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/2A418C925C5B/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/CCDA6EA567>) |
| 8086:51ef |           | Intel            | Alder Lake PCH Shared SRAM           | 17    |            | [24EB20636B](<All In One/Hewlett-Packard/All-in-One/All-in-One Desktop 24-cr0xxx/ECB3533431C4/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/24EB20636B>) |
| 8086:a121 | 103c:2b3e | Intel            | 100 Series/C230 Series Chipset Fa... | 16    |            | [72FDDCCE30](<All In One/Hewlett-Packard/27/27-p014/5E43D288C796/OPENSUSE-LEAP-15.6/6.4.0-150600.23.30-DEFAULT/X86_64/72FDDCCE30>) |
| 8086:9d21 | 1025:1287 | Intel            | Sunrise Point-LP PMC                 | 15    | intel_p... | [08963EC448](<All In One/Acer/Aspire/Aspire C24-865/78DC8340D315/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/08963EC448>) |
| 8086:9d21 | 8086:9d21 | Intel            | Sunrise Point-LP PMC                 | 15    | intel_p... | [555F0208DB](<All In One/ASUSTek Computer/V241/V241IC-R/86B3953D53F1/UBUNTU-22.04/6.2.0-39-GENERIC/X86_64/555F0208DB>) |
| 8086:a2a1 | 1028:079c | Intel            | 200 Series/Z370 Chipset Family Po... | 14    |            | [D019C812B7](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/360F073CECA0/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/D019C812B7>) |
| 10de:0568 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] Memory Cont... | 12    |            | [63D0351E00](<All In One/Acer/Aspire/Aspire Z5101/8569CA5B9C9A/LINUXMINT-22/6.8.0-45-GENERIC/X86_64/63D0351E00>) |
| 10de:0751 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] Memory Cont... | 12    |            | [63D0351E00](<All In One/Acer/Aspire/Aspire Z5101/8569CA5B9C9A/LINUXMINT-22/6.8.0-45-GENERIC/X86_64/63D0351E00>) |
| 10de:0754 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] Memory Cont... | 12    |            | [63D0351E00](<All In One/Acer/Aspire/Aspire Z5101/8569CA5B9C9A/LINUXMINT-22/6.8.0-45-GENERIC/X86_64/63D0351E00>) |
| 8086:06ef | 8086:7270 | Intel            | Comet Lake PCH Shared SRAM           | 12    |            | [D613941D95](<All In One/Dell/OptiPlex/OptiPlex 7480 AIO/203C46736888/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/D613941D95>) |
| 8086:9def | 17aa:3145 | Intel            | Cannon Point-LP Shared SRAM          | 10    |            | [4FAC5AC06A](<All In One/Lenovo/V540-24IWL/V540-24IWL AIO 10YS0031RU/BC9666104DD6/ROSA-12/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/4FAC5AC06A>) |
| 8086:9def | 8086:7270 | Intel            | Cannon Point-LP Shared SRAM          | 10    |            | [DBDFEC80AC](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/9D86375D22FA/LINUXMINT-21.2/5.15.0-91-GENERIC/X86_64/DBDFEC80AC>) |
| 8086:a121 | 103c:82dc | Intel            | 100 Series/C230 Series Chipset Fa... | 10    |            | [4F6CBB3D87](<All In One/Hewlett-Packard/440G3PONA-i37100T-1Thq-4C-8f/440G3PONA-i37100T-1Thq-4C-8f PC/4649228EBB87/OPENMANDRIVA-24.01/6.6.2-DESKTOP-1OMV2390/X86_64/4F6CBB3D87>) |
| 8086:a121 | 8086:a121 | Intel            | 100 Series/C230 Series Chipset Fa... | 10    |            | [B9F363DA1B](<All In One/ASUSTek Computer/Z240/Z240IC-H170/BD8C045F6FC1/FEDORA-40/6.9.10-200.FC40.X86_64/X86_64/B9F363DA1B>) |
| 10de:0a88 | 1462:4570 | Nvidia           | MCP79 Memory Controller              | 9     |            | [F7CB25FE9C](<All In One/MSI/MS/MS-6657/91327E5DD924/ZORIN-17/6.8.0-48-GENERIC/X86_64/F7CB25FE9C>) |
| 10de:0a89 | 1462:4570 | Nvidia           | MCP79 Memory Controller              | 9     |            | [F7CB25FE9C](<All In One/MSI/MS/MS-6657/91327E5DD924/ZORIN-17/6.8.0-48-GENERIC/X86_64/F7CB25FE9C>) |
| 10de:0aa4 | 1462:4570 | Nvidia           | MCP79 Memory Controller              | 9     |            | [F7CB25FE9C](<All In One/MSI/MS/MS-6657/91327E5DD924/ZORIN-17/6.8.0-48-GENERIC/X86_64/F7CB25FE9C>) |
| 8086:34ef | 1025:1434 | Intel            | Ice Lake-LP DRAM Controller          | 9     |            | [DB7DFE3AC4](<All In One/Acer/Aspire/Aspire C22-963/468F69A6EF00/LINUX-LITE-5.6/5.4.0-182-GENERIC/X86_64/DB7DFE3AC4>) |
| 8086:9d21 | 1028:0754 | Intel            | Sunrise Point-LP PMC                 | 9     |            | [274DC30D2C](<All In One/Dell/Inspiron/Inspiron 3464 AIO/31AD17DDDC01/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/274DC30D2C>) |
| 8086:a121 | 103c:81b7 | Intel            | 100 Series/C230 Series Chipset Fa... | 9     |            | [5EE96C131D](<All In One/Hewlett-Packard/24/24-b104nf/DAEF4DA1C3B6/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/5EE96C131D>) |
| 8086:7aa7 | 8086:7270 | Intel            | Alder Lake-S PCH Shared SRAM         | 8     |            | [5AFCA2AEA2](<All In One/Others/A23/A23H66/95FE00C67093/ASTRA-1.7_X86-64/6.1.90-1-GENERIC/X86_64/5AFCA2AEA2>) |
| 8086:9d21 | 103c:82dd | Intel            | Sunrise Point-LP PMC                 | 8     |            | [B0BF9DECAA](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/943856427979/LINUXMINT-21.3/5.15.0-113-GENERIC/X86_64/B0BF9DECAA>) |
| 8086:a121 | 1462:b090 | Intel            | 100 Series/C230 Series Chipset Fa... | 8     |            | [D80B4E7372](<All In One/MSI/MS-B/MS-B09012/AFC51AE1EE8A/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/D80B4E7372>) |
| 8086:a36f | 103c:83eb | Intel            | Cannon Lake PCH Shared SRAM          | 8     |            | [F655DC8E65](<All In One/Hewlett-Packard/ProOne/ProOne 440 G4 AiO/46615EAD4BA5/UBUNTU-22.04/6.2.0-34-GENERIC/X86_64/F655DC8E65>) |
| 8086:a36f | 103c:85a2 | Intel            | Cannon Lake PCH Shared SRAM          | 8     |            | [4C618F5DDE](<All In One/Hewlett-Packard/ProOne/ProOne 440 G5 23.8-in All-in-One/AC4148A4D238/RED-OS-8.0/6.6.6-1.RED80.X86_64/X86_64/4C618F5DDE>) |
| 8086:a36f | 17aa:3123 | Intel            | Cannon Lake PCH Shared SRAM          | 7     |            | [9C31B501B0](<All In One/Lenovo/ThinkCentre/ThinkCentre M820z 10SDS01600/548A01155066/ROSA-12/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/9C31B501B0>) |
| 8086:4def |           | Intel            | Jasper Lake Shared SRAM              | 6     |            | [E3E47B4811](<All In One/ASUSTek Computer/ASUS/ASUS EXPERTCENTER AIO E1600WKA_E1600WKA/145D881596F7/TUXEDO-24.04/6.11.0-105009-TUXEDO/X86_64/E3E47B4811>) |
| 8086:9d21 | 17aa:3630 | Intel            | Sunrise Point-LP PMC                 | 6     |            | [9C73644CD4](<All In One/Lenovo/S500z/S500z 10HC0024MT/064AAC1B5C8B/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/9C73644CD4>) |
| 8086:9d21 | 17aa:36dc | Intel            | Sunrise Point-LP PMC                 | 6     |            | [CFE8A83DE3](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-24IKU F0D2008MRK/8BFA9C2A34B0/RED-OS-7.3/6.1.94-1.EL7.3.X86_64/X86_64/CFE8A83DE3>) |
| 8086:a0ef | 1043:1482 | Intel            | Tiger Lake-LP Shared SRAM            | 6     |            | [E02555BD07](<All In One/ASUSTek Computer/ASUS/ASUS Vivo AIO V241EA_V241EA/68A1C9B65FAA/LMDE-6/6.10.6+BPO-AMD64/X86_64/E02555BD07>) |
| 8086:02ef | 8086:7270 | Intel            | Comet Lake PCH-LP Shared SRAM        | 5     |            | [2B67657736](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222FA_V222FA/0339F667E27D/ARCO-ROLLING/6.7.4-ARCH1-1/X86_64/2B67657736>) |
| 8086:9d21 | 103c:81ba | Intel            | Sunrise Point-LP PMC                 | 5     |            | [A731B2FB23](<All In One/Hewlett-Packard/24/24-g051ng/3F23DC4EFFEA/DEBIAN-12/6.1.0-18-AMD64/X86_64/A731B2FB23>) |
| 8086:a121 | 1025:1063 | Intel            | 100 Series/C230 Series Chipset Fa... | 5     |            | [03C59534F5](<All In One/Acer/Aspire/Aspire Z3-715/D5B0F6B5EA52/FEDORA-36/5.18.8-200.FSYNC.FC36.X86_64/X86_64/03C59534F5>) |
| 8086:a121 | 1028:075c | Intel            | 100 Series/C230 Series Chipset Fa... | 5     |            | [62F71BAABE](<All In One/Dell/XPS/XPS 7760 AIO/AC856E6CD9D7/ZORIN-17/6.8.0-49-GENERIC/X86_64/62F71BAABE>) |
| 8086:a121 | 103c:805e | Intel            | 100 Series/C230 Series Chipset Fa... | 5     |            | [EB19C3207D](<All In One/Hewlett-Packard/ProOne/ProOne 600 G2 21.5-in Non-Touch AiO/95CE8F95FEA5/LINUXMINT-21.3/5.15.0-124-GENERIC/X86_64/EB19C3207D>) |
| 8086:a121 | 17aa:30ba | Intel            | 100 Series/C230 Series Chipset Fa... | 5     |            | [FE3F87CD1C](<All In One/Lenovo/ThinkCentre/ThinkCentre M900z 10F4S0FW00/F174AA1FA46B/BIG/6.9.10-X64V2-XANMOD1-1/X86_64/FE3F87CD1C>) |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15e2 | 1022:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 12    | snd_pci... | [7C37FCE41A](<All In One/Others/FP7/FP7R2AIO/73A1EB679CBF/DEBIAN-12/6.12.8-X64V3-XANMOD1/X86_64/7C37FCE41A>) |
| 1131:7231 | 1461:2b0f | Philips Semic... | SAA7231                              | 12    |            | [4EB5763E89](<All In One/Lenovo/IdeaCentre/IdeaCentre B550 10135/3FCD9E436CF5/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/4EB5763E89>) |
| 1131:7231 | 1461:2a0f | Philips Semic... | SAA7231                              | 11    |            | [2DBA377315](<All In One/Acer/Aspire/Aspire Z3751/B1AF8B7D0810/ROSA-2016.1/5.4.107-GENERIC-0.1ROSA-X86_64/X86_64/2DBA377315>) |
| 1022:15e2 | 17aa:371c | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 7     | snd_pci... | [E1B1540113](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 24ARE05 F0EW004WUK/5E9CA431A68F/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E1B1540113>) |
| 1002:ac12 | 12ab:0003 | AMD              | Theater HD T507 (DVB-T) TV tuner/... | 5     |            | [8F25ED4108](<All In One/Lenovo/IdeaCentre/IdeaCentre A310 10056/1F51DDDCDF1C/LINUXMINT-19.3/5.4.0-77-GENERIC/X86_64/8F25ED4108>) |
| 1022:15e2 | 17aa:3746 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 5     | snd_pci... | [E9064CFEFC](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 27ALC6 F0FY006NPG/65AA3F0EC3FC/LMDE-5/5.10.0-28-AMD64/X86_64/E9064CFEFC>) |
| 1022:15e2 | 1043:1832 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 3     | snd_pci... | [F6285D1100](<All In One/ASUSTek Computer/ASUS/ASUS ZEN AIO M5401WUA_M5401WUA/525FB10EAB16/DEBIAN-UNSTABLE/6.2.9-4-LIQUORIX-AMD64/X86_64/F6285D1100>) |
| 1022:15e2 | 17aa:36f5 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 3     | snd_pci... | [EB38810FB8](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-24ARR F0DN006KGE/1D5E59C5CB5F/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/EB38810FB8>) |
| 1022:15e2 | 17aa:371d | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 3     | snd_pci... | [7EBF0B1DD0](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 22ADA05 F0EX0081IN/99B2864404AC/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/7EBF0B1DD0>) |
| 8086:9a39 | 1043:1aa2 | Intel            | Imaging Signal Processor             | 3     |            | [E39C0B0B4F](<All In One/ASUSTek Computer/ASUS/ASUS EXPERTCENTER AIO E5402WHA_A5402WHA/B39572768AFF/FEDORA-41/6.11.5-300.FC41.X86_64/X86_64/E39C0B0B4F>) |
| 1002:ac12 | 1002:b539 | AMD              | Theater HD T507 (DVB-T) TV tuner/... | 2     |            | [7CCE3E46D0](<All In One/Lenovo/IdeaCentre/IdeaCentre B310/F1C31A285B2C/ARCH-ROLLING/6.8.1-ARCH1-1/X86_64/7CCE3E46D0>) |
| 1022:15e2 | 17aa:3734 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     | snd_pci... | [B153378DAB](<All In One/Lenovo/Yoga/Yoga AIO 7 27ARH6 F0FN000NMT/C9B8617D0FC8/ENDEAVOUROS-ROLLING/6.5.9-ARCH2-1/X86_64/B153378DAB>) |
| 1022:15e2 | 17aa:3744 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     | snd_pci... | [765A9D56C1](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 24ALC6 F0G100NALD/E6B295C3FD14/DEBIAN-12/6.1.0-13-AMD64/X86_64/765A9D56C1>) |
| 10cf:2030 | 104d:9053 | Fujitsu Limited. | PIX                                  | 2     |            | [AFA509714D](<All In One/Sony/VGC-LN52/VGC-LN52JGB/54F15FF48E03/UBUNTU-20.04/5.8.0-54-GENERIC/X86_64/AFA509714D>) |
| 10cf:2030 | 104d:9062 | Fujitsu Limited. | PIX                                  | 2     |            | [71AE1045DA](<All In One/Sony/VPCL129/VPCL129FJ/ECBBF017B776/OPENMANDRIVA-4.90/5.18.12-DESKTOP-3OMV4090/X86_64/71AE1045DA>) |
| 10cf:2036 | 104d:906e | Fujitsu Limited. | DT-XXX                               | 2     |            | [2DEFAA2F88](<All In One/Sony/VPCJ118/VPCJ118FJ/356CC6106273/UBUNTU-20.04/5.15.0-43-GENERIC/X86_64/2DEFAA2F88>) |
| 1131:7231 | 1461:2b07 | Philips Semic... | SAA7231                              | 2     |            | [225E42D432](<All In One/Dell/Inspiron/Inspiron One 2320/D8B99273D539/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/225E42D432>) |
| 1745:3000 | 104d:9049 | ViXS Systems     | Colossus Encoder                     | 2     |            | [71AE1045DA](<All In One/Sony/VPCL129/VPCL129FJ/ECBBF017B776/OPENMANDRIVA-4.90/5.18.12-DESKTOP-3OMV4090/X86_64/71AE1045DA>) |
| 1745:5000 | 17aa:6034 | ViXS Systems     | PureTV-U ISDB-T Tuner                | 2     |            | [219795E31D](<All In One/NEC Computers/PC-VN770/PC-VN770SSR-KS/9E7D8CED55FA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/219795E31D>) |
| 1022:15e2 | 1043:1a72 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     | snd_pci... | [E593179048](<All In One/ASUSTek Computer/ASUS/ASUS AIO M3400WUA_M3400WUA/C57F5A924964/ROSA-12.3/5.10.155-GENERIC-1ROSA2021.1-X86_64/X86_64/E593179048>) |
| 1022:15e2 | 17aa:3751 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [78D918F4D0](<All In One/Lenovo/Yoga/Yoga AIO 7 27ACH6 F0G7001MUS/DCDD76EB4114/FEDORA-40/6.9.11-200.FC40.X86_64/X86_64/78D918F4D0>) |
| 1022:15e2 | 17aa:3777 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     | snd_pci... | [ED33639BE3](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 27ALC6 F0FY00NNUK/1B1EC250F927/ARCO-ROLLING/6.12.4-ZEN1-1-ZEN/X86_64/ED33639BE3>) |
| 10cf:2036 | 1154:0550 | Fujitsu Limited. | DT-XXX                               | 1     |            | [540C821D0F](<All In One/Toshiba/dynabook/dynabook REGZA PC D713-T7JW/ED6E0BFD4B9F/DEBIAN-11/5.10.10-64/X86_64/540C821D0F>) |
| 1131:7160 | 1461:2155 | Philips Semic... | SAA7160                              | 1     |            | [27E7D42D53](<All In One/Lenovo/Others/Others/18DB28A21724/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/27E7D42D53>) |
| 1131:7160 | 1461:2a55 | Philips Semic... | SAA7160                              | 1     |            | [18C8665A8A](<All In One/Sony/VPCL14/VPCL14S1E/05E16BA420D0/LINUXMINT-21.3/5.15.0-121-GENERIC/X86_64/18C8665A8A>) |
| 1131:7231 | 12ab:0163 | Philips Semic... | SAA7231                              | 1     |            | [988ED124EE](<All In One/Lenovo/xxxx/xxxx IdeaCentre A300/598D74A4FC33/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/988ED124EE>) |
| 1131:7231 | 1461:2a07 | Philips Semic... | SAA7231                              | 1     |            | [953740388E](<All In One/Gateway/ZX/ZX4931/4903C3285F3E/ELEMENTARY-7/6.2.0-26-GENERIC/X86_64/953740388E>) |
| 1745:3000 | 1033:895c | ViXS Systems     | Colossus Encoder                     | 1     |            | [6F4A2D24C1](<All In One/NEC Computers/PC-VW770/PC-VW770CS6B/CD4FBB5FF80F/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/6F4A2D24C1>) |
| 1745:3000 | 104d:90a7 | ViXS Systems     | Colossus Encoder                     | 1     |            | [87CD8E5F0A](<All In One/NEC Computers/PC-VN370/PC-VN370HS1KSR/00D74F6C7777/UBUNTU-23.10/6.5.0-44-GENERIC/X86_64/87CD8E5F0A>) |
| 1745:3000 | 1bcf:a023 | ViXS Systems     | Colossus Encoder                     | 1     |            | [1494683BB9](<All In One/NEC Computers/PC-VN770/PC-VN770DS3ER/18CEF0AA43DB/UBUNTU-20.04/5.8.0-48-GENERIC/X86_64/1494683BB9>) |
| 8086:1919 | 17aa:3825 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 1     | ipu3_imgu  | [105D641565](<All In One/Acidanthera/iMac18/iMac18,1/244EC7A3F367/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/105D641565>) |
| 8086:465d | 1025:162e | Intel            | Alder Lake Imaging Signal Processor  | 1     | icamera... | [6E8D78BCE8](<All In One/Acer/Aspire/Aspire S27-1755/C3B02C9B2D35/FEDORA-41/6.11.11-300.FC41.X86_64/X86_64/6E8D78BCE8>) |
| 8086:9d32 | 17aa:3807 | Intel            | CSI-2 Host Controller                | 1     | ipu3_cio2  | [105D641565](<All In One/Acidanthera/iMac18/iMac18,1/244EC7A3F367/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/105D641565>) |
| 8086:a75d | 1025:1700 | Intel            | Raptor Lake IPU                      | 1     |            | [3460649DA4](<All In One/Acer/Aspire/Aspire S32-1856/83E39AF333D6/RED-OS-7.3/6.1.110-1.EL7.3.X86_64/X86_64/3460649DA4>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14e4:1686 | 14e4:1686 | Broadcom         | NetXtreme BCM57766 Gigabit Ethern... | 580   | tg3        | [500ACCCF00](<All In One/Apple/iMac16/iMac16,2/D9F8E706C1F9/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/500ACCCF00>) |
| 14e4:16b4 | 14e4:16b4 | Broadcom         | NetXtreme BCM57765 Gigabit Ethern... | 288   | tg3        | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 11ab:436a | 11ab:00ba | Marvell Techn... | 88E8058 PCI-E Gigabit Ethernet Co... | 243   | sky2       | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 10de:0ab0 | 10de:cb79 | Nvidia           | MCP79 Ethernet                       | 211   | forcedeth  | [E82B0C22FB](<All In One/Apple/iMac10/iMac10,1/99E4987A298C/DEBIAN-12/6.1.0-28-AMD64/X86_64/E82B0C22FB>) |
| 14e4:1684 | 14e4:1684 | Broadcom         | NetXtreme BCM5764M Gigabit Ethern... | 152   | tg3        | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 80    | r8169      | [5AFCA2AEA2](<All In One/Others/A23/A23H66/95FE00C67093/ASTRA-1.7_X86-64/6.1.90-1-GENERIC/X86_64/5AFCA2AEA2>) |
| 10ec:8168 | 10ec:8117 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 57    | r8168      | [F969D9FB85](<All In One/ICL/RAY/RAY Si105.Mi/2E3E3E31C611/ROSA-12/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/F969D9FB85>) |
| 10ec:8168 | 1043:205f | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 43    | r8169      | [E3E47B4811](<All In One/ASUSTek Computer/ASUS/ASUS EXPERTCENTER AIO E1600WKA_E1600WKA/145D881596F7/TUXEDO-24.04/6.11.0-105009-TUXEDO/X86_64/E3E47B4811>) |
| 11ab:4362 | 11ab:5321 | Marvell Techn... | 88E8053 PCI-E Gigabit Ethernet Co... | 42    | sky2       | [385C17B3D5](<All In One/Apple/iMac5/iMac5,1/36F0382E5A3A/ZORIN-17/6.8.0-48-GENERIC/X86_64/385C17B3D5>) |
| 14e4:1686 | 106b:0110 | Broadcom         | NetXtreme BCM57766 Gigabit Ethern... | 38    | tg3        | [9D0D676179](<All In One/Apple/iMac13/iMac13,2/A3BD8470C792/ELEMENTARY-7.1/6.8.0-48-GENERIC/X86_64/9D0D676179>) |
| 10ec:8168 | 1025:8000 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 32    | r8169      | [AA23301E4B](<All In One/Acer/Aspire/Aspire Z3751/A435CE6B49D1/ZORIN-17/6.8.0-49-GENERIC/X86_64/AA23301E4B>) |
| 10ec:8168 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 32    | r8169      | [EC8A440630](<All In One/Multilaser/UB82/UB82X/29A5540764F5/ZORIN-17/6.8.0-49-GENERIC/X86_64/EC8A440630>) |
| 10ec:8168 | 103c:8245 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 24    | r8169      | [544F0D3076](<All In One/Hewlett-Packard/20/20-c002a/4A3792E1E976/LINUXMINT-22/6.8.0-49-GENERIC/X86_64/544F0D3076>) |
| 10ec:8168 | 103c:84ee | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 23    | r8169      | [597321B19E](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/07E9499C7A2C/KDE-NEON-24.04/6.8.0-49-GENERIC/X86_64/597321B19E>) |
| 10ec:8168 | 1b50:4606 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 22    | r8169      | [702F3F3BC5](<All In One/Medion/E23201/E23201 MD61575/ADEBFF0ED21D/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/702F3F3BC5>) |
| 10ec:8168 | 17aa:365e | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 21    | r8169      | [DBA1D52306](<All In One/Lenovo/C340/C340 10102/8204E1CC8521/ZORIN-17/6.8.0-48-GENERIC/X86_64/DBA1D52306>) |
| 10ec:8168 | 103c:86f3 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 20    | r8169      | [2F05B30C3F](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-dp0xxx/E1C03E22AF48/OPENMANDRIVA-24.03/6.8.1-DESKTOP-3OMV2490/X86_64/2F05B30C3F>) |
| 10ec:8168 | 103c:8430 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 19    | r8169      | [3EA46622E6](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/E4E878423146/OPENMANDRIVA-24.08/6.10.1-DESKTOP-1OMV2490/X86_64/3EA46622E6>) |
| 10ec:8168 | 103c:84de | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 19    | r8169      | [A7F55BE076](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/F6FC816725AE/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/A7F55BE076>) |
| 1969:1091 | 1028:0548 | Qualcomm Atheros | AR8161 Gigabit Ethernet              | 19    | alx        | [939EFC4955](<All In One/Dell/Inspiron/Inspiron One 2330/DA27CAF94DE9/ELEMENTARY-7.1/6.8.0-48-GENERIC/X86_64/939EFC4955>) |
| 8086:153a | 1028:05a7 | Intel            | Ethernet Connection I217-LM          | 19    | e1000e     | [F866E174C2](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/5BD2C4C72DD4/FEDORA-40/6.10.8-200.FC40.X86_64/X86_64/F866E174C2>) |
| 10ec:8168 | 1028:0511 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 18    | r8169      | [EC101E6744](<All In One/Dell/Inspiron/Inspiron One 2320/3D9ADF185AD6/ARCH-ROLLING/6.12.7-ARCH1-1/X86_64/EC101E6744>) |
| 8086:15b7 | 1028:06c5 | Intel            | Ethernet Connection (2) I219-LM      | 18    | e1000e     | [CCDA6EA567](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/2A418C925C5B/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/CCDA6EA567>) |
| 10ec:8168 | 103c:81bb | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 17    | r8169      | [A802D08306](<All In One/Hewlett-Packard/22/22-b015ur/5883A5C263EF/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/A802D08306>) |
| 10ec:8168 | 1b50:4607 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 17    | r8169      | [3460649DA4](<All In One/Acer/Aspire/Aspire S32-1856/83E39AF333D6/RED-OS-7.3/6.1.110-1.EL7.3.X86_64/X86_64/3460649DA4>) |
| 10ec:8168 | 1028:05db | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 16    | r8169      | [AAD8987195](<All In One/Dell/Inspiron/Inspiron 2350/537D2F43CC7A/MX-23/6.1.0-10-AMD64/X86_64/AAD8987195>) |
| 10ec:8168 | 103c:2b3e | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 16    | r8169      | [72FDDCCE30](<All In One/Hewlett-Packard/27/27-p014/5E43D288C796/OPENSUSE-LEAP-15.6/6.4.0-150600.23.30-DEFAULT/X86_64/72FDDCCE30>) |
| 10ec:8168 | 1043:204f | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 16    | r8169      | [E39C0B0B4F](<All In One/ASUSTek Computer/ASUS/ASUS EXPERTCENTER AIO E5402WHA_A5402WHA/B39572768AFF/FEDORA-41/6.11.5-300.FC41.X86_64/X86_64/E39C0B0B4F>) |
| 10ec:8168 | 1025:0266 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 15    | r8169      | [9D826BCE47](<All In One/Acer/Aspire/Aspire Z5610/F8851F6F2232/LUBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9D826BCE47>) |
| 10ec:8168 | 1025:1287 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 15    | r8169      | [08963EC448](<All In One/Acer/Aspire/Aspire C24-865/78DC8340D315/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/08963EC448>) |
| 10ec:8168 | 1854:0308 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 15    | r8169      | [A595C7B829](<All In One/LG Electronics/22V280/22V280-L.BJ31P1/BE8548B5DD51/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/A595C7B829>) |
| 8086:15e3 | 1028:079c | Intel            | Ethernet Connection (5) I219-LM      | 14    | e1000e     | [D019C812B7](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/360F073CECA0/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/D019C812B7>) |
| 10de:0760 | 1025:8000 | Nvidia           | MCP77 Ethernet                       | 13    | forcedeth  | [C98E028454](<All In One/Gateway/ZX/ZX4351/9B8510AE2122/MX-23/6.1.0-26-AMD64/X86_64/C98E028454>) |
| 10ec:8136 | 10ec:8136 | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 13    | r8169      | [0FBDE604E6](<All In One/Dell/Inspiron/Inspiron 20 Model 3043/C7C0ED241602/ZORIN-17/6.8.0-50-GENERIC/X86_64/0FBDE604E6>) |
| 10ec:8168 | 103c:2b3b | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 13    | r8169      | [83AF71F2E9](<All In One/Hewlett-Packard/23/23-r159la/D01B9A9B3593/ELEMENTARY-7.1/6.8.0-47-GENERIC/X86_64/83AF71F2E9>) |
| 10ec:8168 | 103c:8381 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 13    | r8169      | [6745FD4BAC](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/EF305E495BCA/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/6745FD4BAC>) |
| 10ec:8168 | 1043:200f | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 13    | r8169      | [D1891AF126](<All In One/ASUSTek Computer/Vivo/Vivo AIO 16 V161GA_V161GA/AD72AFEBE798/XERO-ROLLING/6.6.4-ARCH1-1/X86_64/D1891AF126>) |
| 10ec:8168 | 1043:858f | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 13    | r8169      | [B9F363DA1B](<All In One/ASUSTek Computer/Z240/Z240IC-H170/BD8C045F6FC1/FEDORA-40/6.9.10-200.FC40.X86_64/X86_64/B9F363DA1B>) |
| 10ec:8168 | 103c:2ac5 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 12    | r8169      | [B32F35A4B1](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/C0BF0A16B6D4/FEDORA-36/5.18.19-200.FC36.X86_64/X86_64/B32F35A4B1>) |
| 8086:1a1d | 8086:0000 | Intel            | Ethernet Connection (17) I219-V      | 12    | e1000e     | [B0BDA7B10B](<All In One/Acer/Veriton/Veriton Z2694G/992B643355D9/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/B0BDA7B10B>) |
| 10ec:8168 | 1028:0a06 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 11    | r8169      | [078A22F745](<All In One/Dell/Inspiron/Inspiron 5400 AIO/D5D2451D1C1C/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/078A22F745>) |
| 10ec:8168 | 103c:8446 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 11    | r8169      | [C5B5B31A25](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/7EFF5EC8D014/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/C5B5B31A25>) |
| 10ec:8168 | 144d:b091 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 11    | r8169      | [7DDB4BB85E](<All In One/Samsung Electronics/DP700/DP700A3D-DM700A3D-DB701A3D-DP700A7D/F8AB47648274/ELEMENTARY-7.1/6.5.0-28-GENERIC/X86_64/7DDB4BB85E>) |
| 10ec:8168 | 17aa:366c | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 11    | r8169      | [71F424691E](<All In One/Lenovo/C540/C540 10110/5F044C149ED0/LINUXMINT-22/6.8.0-49-GENERIC/X86_64/71F424691E>) |
| 8086:153a | 1028:0625 | Intel            | Ethernet Connection I217-LM          | 11    | e1000e     | [8FE8D8B38E](<All In One/Dell/OptiPlex/OptiPlex 9030 AIO/6D792C13AB31/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/8FE8D8B38E>) |
| 10ec:8168 | 1019:8117 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 10    | r8169      | [46658F67D3](<All In One/ICL/H310/H310SB-TM/298E8E81F4C1/ROSA-12/6.1.81-GENERIC-2ROSA2021.1-X86_64/X86_64/46658F67D3>) |
| 10ec:8168 | 103c:82dc | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 10    | r8169      | [4F6CBB3D87](<All In One/Hewlett-Packard/440G3PONA-i37100T-1Thq-4C-8f/440G3PONA-i37100T-1Thq-4C-8f PC/4649228EBB87/OPENMANDRIVA-24.01/6.6.2-DESKTOP-1OMV2390/X86_64/4F6CBB3D87>) |
| 10ec:8168 | 1043:84cd | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 10    | r8169      | [7F4B778E2E](<All In One/ASUSTek Computer/EB/EB1035/761B03C3DC6E/DEBIAN-12/6.1.0-25-AMD64/X86_64/7F4B778E2E>) |
| 10ec:8168 | 144d:b092 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 10    | r8169      | [B2DD874812](<All In One/Samsung Electronics/P500/P500A2D/6CBEFCF9E89C/UBUNTU-22.04/6.8.0-47-GENERIC/X86_64/B2DD874812>) |
| 10ec:8168 | 1458:e000 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 10    | r8169      | [53E73F6DD7](<All In One/Gigabyte Technology/GB-A5/GB-A5DNK-RH/2D59EF3CA1FB/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/53E73F6DD7>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 168c:0030 | 106b:009a | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 288   | ath9k      | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 168c:002a | 106b:008f | Qualcomm Atheros | AR928X Wireless Network Adapter (... | 263   | ath9k      | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 14e4:43a0 | 106b:0111 | Broadcom         | BCM4360 802.11ac Dual Band Wirele... | 198   | wl         | [8485C9B6A3](<All In One/Apple/iMac14/iMac14,2/DE6A385E2C03/ARCH-ROLLING/6.10.14-273-TKG-EEVDF/X86_64/8485C9B6A3>) |
| 14e4:4328 | 106b:0088 | Broadcom         | BCM4321 802.11a/b/g/n                | 123   | wl         | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 10ec:c821 | 103c:831a | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 122   | rtw88_8... | [C5B5B31A25](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/7EFF5EC8D014/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/C5B5B31A25>) |
| 14e4:4328 | 106b:008c | Broadcom         | BCM4321 802.11a/b/g/n                | 120   | wl         | [1D1DAF9285](<All In One/Apple/iMac8/iMac8,1/14F211319CBB/ZORIN-12/4.15.0-142-GENERIC/X86_64/1D1DAF9285>) |
| 14e4:432b | 106b:008e | Broadcom         | BCM4322 802.11a/b/g/n Wireless LA... | 97    | wl         | [F3660A5D7B](<All In One/Apple/iMac9/iMac9,1/50AE0E9B32CE/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/F3660A5D7B>) |
| 14e4:4331 | 106b:00f4 | Broadcom Limited | BCM4331 802.11a/b/g/n                | 91    | wl         | [0BB2743C5F](<All In One/Apple/iMac13/iMac13,1/9790142699C8/ZORIN-17/6.8.0-49-GENERIC/X86_64/0BB2743C5F>) |
| 8086:3165 | 8086:4010 | Intel            | Wireless 3165                        | 87    | iwlwifi    | [F969D9FB85](<All In One/ICL/RAY/RAY Si105.Mi/2E3E3E31C611/ROSA-12/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/F969D9FB85>) |
| 8086:24fb | 8086:2110 | Intel            | Dual Band Wireless-AC 3168NGW [St... | 85    | iwlwifi    | [2C96529FBD](<All In One/Hewlett-Packard/24/24-b247c/4A533C88C34A/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/2C96529FBD>) |
| 14e4:4464 | 106b:07bf | Broadcom         | BCM4364 802.11ac Wireless Network... | 81    | brcmfmac   | [0C36BC1E93](<All In One/Apple/iMac19/iMac19,2/C074723931A0/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/0C36BC1E93>) |
| 14e4:43ba | 106b:016f | Broadcom         | BCM43602 802.11ac Wireless LAN SoC   | 57    | brcmfmac   | [EDA26270C4](<All In One/Apple/iMac18/iMac18,3/BEED7205CB3E/ARCH-ROLLING/6.12.6-ARCH1-1/X86_64/EDA26270C4>) |
| 14e4:43ba | 106b:016e | Broadcom         | BCM43602 802.11ac Wireless LAN SoC   | 55    | brcmfmac   | [9C21FDA832](<All In One/Apple/iMac18/iMac18,2/9742FAAE1644/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9C21FDA832>) |
| 10ec:b723 | 103c:81c1 | Realtek Semic... | RTL8723BE PCIe Wireless Network A... | 52    | rtl8723be  | [A802D08306](<All In One/Hewlett-Packard/22/22-b015ur/5883A5C263EF/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/A802D08306>) |
| 14e4:43ba | 106b:014a | Broadcom         | BCM43602 802.11ac Wireless LAN SoC   | 50    | brcmfmac   | [65F3216D32](<All In One/Apple/iMac17/iMac17,1/2DEE4DEFC615/LINUXMINT-22/6.8.0-45-GENERIC/X86_64/65F3216D32>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 50    | iwlwifi    | [BD9F5DD3DE](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/BD9F5DD3DE>) |
| 8086:3166 | 8086:4210 | Intel            | Dual Band Wireless-AC 3165 Plus B... | 48    | iwlwifi    | [F571A11FB7](<All In One/Lenovo/V130-20IGM/V130-20IGM AIO 10RX0058UM/D90EC36AC673/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/F571A11FB7>) |
| 14e4:43ba | 106b:0156 | Broadcom         | BCM43602 802.11ac Wireless LAN SoC   | 43    | brcmfmac   | [500ACCCF00](<All In One/Apple/iMac16/iMac16,2/D9F8E706C1F9/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/500ACCCF00>) |
| 10ec:b822 | 103c:831b | Realtek Semic... | RTL8822BE 802.11a/b/g/n/ac WiFi a... | 42    | rtw88_8... | [597321B19E](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/07E9499C7A2C/KDE-NEON-24.04/6.8.0-49-GENERIC/X86_64/597321B19E>) |
| 10ec:c821 | 17aa:c024 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 38    | rtw88_8... | [9043416985](<All In One/Lenovo/IdeaCentre/IdeaCentre A340-24ICB F0E600A6MT/A7BEADF711C0/LINUXMINT-22/6.8.0-48-GENERIC/X86_64/9043416985>) |
| 10ec:8179 | 17aa:0179 | Realtek Semic... | RTL8188EE Wireless Network Adapter   | 32    | rtl8188ee  | [F2AD5B1C81](<All In One/Lenovo/C560/C560 10150/F42ADFFAA517/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/F2AD5B1C81>) |
| 168c:0042 | 17aa:0901 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 32    | ath10k_pci | [F781FACD17](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-22AST F0D6000PLD/3E21F3CA09A6/UBUNTU-24.10/6.11.0-8-GENERIC/X86_64/F781FACD17>) |
| 14e4:4328 | 106b:0087 | Broadcom Limited | BCM4321 802.11a/b/g/n                | 30    | ssb        | [DE3A243820](<All In One/Apple/iMac5/iMac5,1/1F7269B01AAF/DEBIAN-11/5.10.0-33-686-PAE/I686/DE3A243820>) |
| 1814:3090 | 11ad:6622 | Ralink           | RT3090 Wireless 802.11n 1T/1R PCIe   | 30    | rt2800pci  | [713041DC45](<All In One/Acer/Aspire/Aspire Z5710/D89AB47419E8/UBUNTU-24.10/6.11.0-8-GENERIC/X86_64/713041DC45>) |
| 10ec:8176 | 10ec:8176 | Realtek Semic... | RTL8188CE 802.11b/g/n WiFi Adapter   | 29    | rtl8192ce  | [85283E62FD](<All In One/Lenovo/C/C225/BCF3261CFAE4/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/85283E62FD>) |
| 168c:0034 | 11ad:6621 | Qualcomm Atheros | AR9462 Wireless Network Adapter      | 29    | ath9k      | [678D72F8E1](<All In One/Acer/Aspire/Aspire Z3-105/7B4FECB4D8AA/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/678D72F8E1>) |
| 168c:0036 | 1028:020e | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 29    | ath9k      | [1F361B3518](<All In One/Dell/Inspiron/Inspiron 23 Model 5348/D34B13017CE6/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/1F361B3518>) |
| 168c:0042 | 1a3b:2231 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 29    | ath10k_pci | [555F0208DB](<All In One/ASUSTek Computer/V241/V241IC-R/86B3953D53F1/UBUNTU-22.04/6.2.0-39-GENERIC/X86_64/555F0208DB>) |
| 168c:0032 | 17aa:3118 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 27    | ath9k      | [DBA1D52306](<All In One/Lenovo/C340/C340 10102/8204E1CC8521/ZORIN-17/6.8.0-48-GENERIC/X86_64/DBA1D52306>) |
| 8086:2723 | 8086:0084 | Intel            | Wi-Fi 6 AX200                        | 27    | iwlwifi    | [105D641565](<All In One/Acidanthera/iMac18/iMac18,1/244EC7A3F367/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/105D641565>) |
| 8086:08b3 | 8086:8070 | Intel            | Wireless 3160                        | 26    | iwlwifi    | [AA064D4B06](<All In One/MSI/MS-B/MS-B09611/3C74325DC6D6/ZORIN-17/6.5.0-15-GENERIC/X86_64/AA064D4B06>) |
| 168c:0032 | 103c:1838 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 25    | ath9k      | [1FEA98FBC3](<All In One/Hewlett-Packard/23/23-g005br/277F333BCD64/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/1FEA98FBC3>) |
| 10ec:c822 | 103c:85f7 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 24    | rtw88_8... | [176BF6C346](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-k1xxx/2EE7EFF5A190/FEDORA-38/6.8.9-100.FC38.X86_64/X86_64/176BF6C346>) |
| 14e4:43a0 | 106b:0142 | Broadcom         | BCM4360 802.11ac Dual Band Wirele... | 23    | wl         | [EDA8CE1D0B](<All In One/Apple/iMac15/iMac15,1/B19C5732AF8F/FEDORA-40/6.10.6-200.FC40.X86_64/X86_64/EDA8CE1D0B>) |
| 168c:0032 | 1028:0209 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 23    | ath9k      | [384D13D228](<All In One/Dell/XPS/XPS One 2710/B7601389FED4/MX-23/6.1.0-25-AMD64/X86_64/384D13D228>) |
| 168c:0042 | 11ad:08a6 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 23    | ath10k_pci | [DB7DFE3AC4](<All In One/Acer/Aspire/Aspire C22-963/468F69A6EF00/LINUX-LITE-5.6/5.4.0-182-GENERIC/X86_64/DB7DFE3AC4>) |
| 8086:a370 | 8086:0034 | Intel            | Cannon Lake PCH CNVi WiFi            | 23    | iwlwifi    | [DEAB701B6F](<All In One/Hewlett-Packard/ProOne/ProOne 440 G5 23.8-in All-in-One/9A1C0A03BF4A/ARCO-ROLLING/6.7.9-ARCH1-1/X86_64/DEAB701B6F>) |
| 14e4:43ba | 106b:016d | Broadcom         | BCM43602 802.11ac Wireless LAN SoC   | 21    | brcmfmac   | [727B7184C9](<All In One/Apple/iMac18/iMac18,1/169F9C1861CD/DEBIAN-12/6.1.0-27-AMD64/X86_64/727B7184C9>) |
| 168c:0036 | 1028:020c | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 21    | ath9k      | [0FBDE604E6](<All In One/Dell/Inspiron/Inspiron 20 Model 3043/C7C0ED241602/ZORIN-17/6.8.0-50-GENERIC/X86_64/0FBDE604E6>) |
| 168c:002b | 1a3b:1089 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 20    | ath9k      | [CBCA24B14A](<All In One/ASUSTek Computer/ET/ET2410/1D7A78AA84D4/MANJARO/6.10.13-3-MANJARO/X86_64/CBCA24B14A>) |
| 8086:24f3 | 8086:0050 | Intel            | Wireless 8260                        | 20    | iwlwifi    | [CCDA6EA567](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/2A418C925C5B/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/CCDA6EA567>) |
| 168c:002b | 105b:e017 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 19    | ath9k      | [44A108150C](<All In One/Sony/VPCJ21/VPCJ21S1E/6EEEF8B3CFB2/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/44A108150C>) |
| 8086:9df0 | 8086:0034 | Intel            | Cannon Point-LP CNVi [Wireless-AC]   | 19    | iwlwifi    | [DBDFEC80AC](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/9D86375D22FA/LINUXMINT-21.2/5.15.0-91-GENERIC/X86_64/DBDFEC80AC>) |
| 168c:0036 | 11ad:0642 | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 17    | ath9k      | [1CDBFBB642](<All In One/Acer/Aspire/Aspire Z3-615/C570F0334B4B/LINUXMINT-22/6.8.0-49-GENERIC/X86_64/1CDBFBB642>) |
| 168c:0036 | 17aa:3026 | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 16    | ath9k      | [4EB5763E89](<All In One/Lenovo/IdeaCentre/IdeaCentre B550 10135/3FCD9E436CF5/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/4EB5763E89>) |
| 168c:0042 | 1028:1810 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 16    | ath10k_pci | [DDBB319D93](<All In One/Dell/Inspiron/Inspiron 3475 AIO/B6D9BD539D6C/DEBIAN-12/6.1.0-21-AMD64/X86_64/DDBB319D93>) |
| 10ec:8179 | 1a3b:1f38 | Realtek Semic... | RTL8188EE Wireless Network Adapter   | 15    | rtl8188ee  | [02E77E625F](<All In One/Positivo/DC8/DC8BT11TV/CC98101BF15F/LUBUNTU-22.10/5.19.0-26-GENERIC/X86_64/02E77E625F>) |
| 168c:002a | 105b:e007 | Qualcomm Atheros | AR928X Wireless Network Adapter (... | 15    | ath9k      | [653A82E6B9](<All In One/Sony/VGC-LV180/VGC-LV180ME/8D99388DD758/XEROLINUX-KDE-ROLLING/6.4.11-ARCH2-1/X86_64/653A82E6B9>) |
| 8086:a0f0 | 8086:4070 | Intel            | Wi-Fi 6 AX201                        | 15    | iwlwifi    | [078A22F745](<All In One/Dell/Inspiron/Inspiron 5400 AIO/D5D2451D1C1C/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/078A22F745>) |
| 14e4:4312 | 106b:0089 | Broadcom         | BCM4311 802.11a/b/g                  | 14    | ssb        | [073A03BEAA](<All In One/Apple/iMac4/iMac4,1/539080C6C5E4/UBUNTU-UNITY-18.04/4.15.0-213-GENERIC/I686/073A03BEAA>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1502 | 1028:0543 | Intel            | 82579LM Gigabit Network Connectio... | 19    | e1000e     | [A552EB99EE](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/B658E6C46850/ZORIN-17/6.8.0-49-GENERIC/X86_64/A552EB99EE>) |
| 8086:10ce | 104d:9060 | Intel            | 82567V-2 Gigabit Network Connection  | 13    | e1000e     | [18C8665A8A](<All In One/Sony/VPCL14/VPCL14S1E/05E16BA420D0/LINUXMINT-21.3/5.15.0-121-GENERIC/X86_64/18C8665A8A>) |
| 8086:10ef | 17aa:306a | Intel            | 82578DM Gigabit Network Connection   | 11    | e1000e     | [B562DA927A](<All In One/Lenovo/ThinkCentre/ThinkCentre M90z 3429D3U/93DF0426D130/UBUNTU-22.04/5.4.0-156-GENERIC/X86_64/B562DA927A>) |
| 8086:10de | 103c:1489 | Intel            | 82567LM-3 Gigabit Network Connection | 7     | e1000e     | [C53E87BCE8](<All In One/Hewlett-Packard/Compaq/Compaq 6000 Pro AiO Brazil PC/FB69A2D0E244/LINUXMINT-20.3/5.4.0-159-GENERIC/X86_64/C53E87BCE8>) |
| 8086:10ce | 1025:048f | Intel            | 82567V-2 Gigabit Network Connection  | 6     | e1000e     | [6A55579055](<All In One/Acer/Aspire/Aspire Z3730/F33B88B5C1F8/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/6A55579055>) |
| 8086:10f0 | 1025:8000 | Intel            | 82578DC Gigabit Network Connection   | 6     | e1000e     | [713041DC45](<All In One/Acer/Aspire/Aspire Z5710/D89AB47419E8/UBUNTU-24.10/6.11.0-8-GENERIC/X86_64/713041DC45>) |
| 8086:1502 | 103c:3395 | Intel            | 82579LM Gigabit Network Connectio... | 6     | e1000e     | [1DC6B38792](<All In One/Hewlett-Packard/Compaq/Compaq 8200 Elite AiO Business PC/C2F2EF898782/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/1DC6B38792>) |
| 8086:1503 | 1025:8000 | Intel            | 82579V Gigabit Network Connection    | 6     | e1000e     | [350574F592](<All In One/Gateway/ZX/ZX6961/55D3DADE7EB6/KALI-2024.4/6.11.10-AMD64/X86_64/350574F592>) |
| 8086:10ce | 104d:9044 | Intel            | 82567V-2 Gigabit Network Connection  | 5     | e1000e     | [5CD160EA53](<All In One/Sony/VGC-JS1/VGC-JS1E_S/2F2CC13FD639/FEDORA-38/6.4.15-200.FC38.X86_64/X86_64/5CD160EA53>) |
| 8086:10fe | 17aa:3610 | Intel            | 82552 10/100 Network Connection      | 5     | e100       | [124088A101](<All In One/Lenovo/C/C200/8F5A7DCC36E9/ROSA-12.6/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/124088A101>) |
| 8086:10ce | 104d:9043 | Intel            | 82567V-2 Gigabit Network Connection  | 4     | e1000e     | [653A82E6B9](<All In One/Sony/VGC-LV180/VGC-LV180ME/8D99388DD758/XEROLINUX-KDE-ROLLING/6.4.11-ARCH2-1/X86_64/653A82E6B9>) |
| 8086:1502 | 8086:0000 | Intel            | 82579LM Gigabit Network Connectio... | 3     | e1000e     | [4E2FFC0DB7](<All In One/InFocus/INF/INF5520/89A8A2E44A06/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/4E2FFC0DB7>) |
| 8086:1539 | 1458:e000 | Intel            | I211 Gigabit Network Connection      | 3     | igb        | [D05A394FC8](<All In One/Acidanthera/iMacPro1/iMacPro1,1/9C6521899F59/CHIMERAOS-46/6.8.0-RC2-CHOS1-CHIMERAOS-1/X86_64/D05A394FC8>) |
| 8086:1539 | 1043:85f0 | Intel            | I211 Gigabit Network Connection      | 2     | igb        | [577AD83B8F](<All In One/Acidanthera/iMacPro1/iMacPro1,1/6286842FEC0E/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/577AD83B8F>) |
| 8086:1539 | 8086:0000 | Intel            | I211 Gigabit Network Connection      | 2     | igb        | [BB02F5BA31](<All In One/Touch Dynamic/Breeze/Breeze Performance Haswell/70A0D6F289D5/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/BB02F5BA31>) |
| 10ec:8125 | 1458:e000 | Realtek Semic... | RTL8125 2.5GbE Controller            | 1     | r8169      | [ABFE7C3F74](<All In One/Acidanthera/iMacPro1/iMacPro1,1/28D78D8770E0/LINUXMINT-21.2/6.2.0-31-GENERIC/X86_64/ABFE7C3F74>) |
| 10ec:8125 | 1462:7c84 | Realtek Semic... | RTL8125 2.5GbE Controller            | 1     | r8169      | [7D0089CC2A](<All In One/Acidanthera/iMacPro1/iMacPro1,1/E475E9B777A3/ENDEAVOUROS-ROLLING/6.9.3-ARCH1-1/X86_64/7D0089CC2A>) |
| 10ec:8168 | ffff:ffff | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 1     | r8169      | [B5DBE70538](<All In One/Lenovo/V50a-24IMB/V50a-24IMB 11FJ0026RU/3131AC26568F/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/B5DBE70538>) |
| 10ee:2017 | 10ee:2017 | Xilinx           | Network controller                   | 1     |            | [401238AE67](<All In One/Graviton/M55/M55i/A2D620B78C13/RED-OS-7.3/6.1.52-1.EL7.3.X86_64/X86_64/401238AE67>) |
| 8086:10d3 | 8086:0000 | Intel            | 82574L Gigabit Network Connection    | 1     | e1000e     | [4E2FFC0DB7](<All In One/InFocus/INF/INF5520/89A8A2E44A06/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/4E2FFC0DB7>) |
| 8086:10eb | 17aa:3608 | Intel            | 82577LC Gigabit Network Connection   | 1     | e1000e     | [69574214D7](<All In One/Lenovo/IdeaCentre/IdeaCentre A700 10050/51968677EC4C/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/69574214D7>) |
| 8086:1502 | 1028:052c | Intel            | 82579LM Gigabit Network Connectio... | 1     | e1000e     | [E7CE3F2F38](<All In One/Acidanthera/iMacPro1/iMacPro1,1/C2AEF029DC5F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E7CE3F2F38>) |
| 8086:1502 | 103c:3397 | Intel            | 82579LM Gigabit Network Connectio... | 1     | e1000e     | [DA2B320CD5](<All In One/Acidanthera/iMacPro1/iMacPro1,1/3A3FCACBB40C/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/DA2B320CD5>) |
| 8086:1503 | 1043:849c | Intel            | 82579V Gigabit Network Connection    | 1     | e1000e     | [259158AB96](<All In One/Acidanthera/iMacPro1/iMacPro1,1/F1829F0BF600/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/259158AB96>) |
| 8086:1503 | 17aa:3620 | Intel            | 82579V Gigabit Network Connection    | 1     | e1000e     | [520F0EF994](<All In One/Lenovo/IdeaCentre/IdeaCentre B520 7745/71BD816847A0/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/520F0EF994>) |
| 8086:1533 | 1ab6:0214 | Intel            | I210 Gigabit Network Connection      | 1     | igb        | [B9E0FD4223](<All In One/Acidanthera/iMac20/iMac20,2/66E649C7E121/ARCO-ROLLING/6.3.7-ARCH1-1/X86_64/B9E0FD4223>) |
| 8086:1539 | 1849:1539 | Intel            | I211 Gigabit Network Connection      | 1     | igb        | [991A74F3E5](<All In One/Acidanthera/iMacPro1/iMacPro1,1/068603353593/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/991A74F3E5>) |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1455 | 1022:1455 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 6     |            | [D05A394FC8](<All In One/Acidanthera/iMacPro1/iMacPro1,1/9C6521899F59/CHIMERAOS-46/6.8.0-RC2-CHOS1-CHIMERAOS-1/X86_64/D05A394FC8>) |
| 1022:145a | 1022:145a | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 6     |            | [D05A394FC8](<All In One/Acidanthera/iMacPro1/iMacPro1,1/9C6521899F59/CHIMERAOS-46/6.8.0-RC2-CHOS1-CHIMERAOS-1/X86_64/D05A394FC8>) |
| 1022:1485 | 1022:1485 | AMD              | Starship/Matisse Reserved SPP        | 6     |            | [7D0089CC2A](<All In One/Acidanthera/iMacPro1/iMacPro1,1/E475E9B777A3/ENDEAVOUROS-ROLLING/6.9.3-ARCH1-1/X86_64/7D0089CC2A>) |
| 1022:148a | 1022:148a | AMD              | Starship/Matisse PCIe Dummy Function | 5     |            | [7D0089CC2A](<All In One/Acidanthera/iMacPro1/iMacPro1,1/E475E9B777A3/ENDEAVOUROS-ROLLING/6.9.3-ARCH1-1/X86_64/7D0089CC2A>) |
| 1022:145a | 17aa:3751 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 1     |            | [78D918F4D0](<All In One/Lenovo/Yoga/Yoga AIO 7 27ACH6 F0G7001MUS/DCDD76EB4114/FEDORA-40/6.9.11-200.FC40.X86_64/X86_64/78D918F4D0>) |
| 1022:1485 | 1043:87c0 | AMD              | Starship/Matisse Reserved SPP        | 1     |            | [577AD83B8F](<All In One/Acidanthera/iMacPro1/iMacPro1,1/6286842FEC0E/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/577AD83B8F>) |
| 1022:148a | 1043:87c0 | AMD              | Starship/Matisse PCIe Dummy Function | 1     |            | [577AD83B8F](<All In One/Acidanthera/iMacPro1/iMacPro1,1/6286842FEC0E/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/577AD83B8F>) |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15e6 | 1022:15e4 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 2     | i2c_amd... | [B4C4E14837](<All In One/Acer/Aspire/Aspire C24-420/6DFDBBE394EB/RED-OS-7.3/5.10.29-3.EL7.X86_64/X86_64/B4C4E14837>) |
| 106b:1801 | 106b:1801 | Apple            | T2 Bridge Controller                 | 2     | apple_bce  | [E4774620DA](<All In One/Apple/iMac20/iMac20,1/4FE23979BC61/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/E4774620DA>) |
| 106b:1802 | 106b:1802 | Apple            | T2 Secure Enclave Processor          | 2     |            | [E4774620DA](<All In One/Apple/iMac20/iMac20,1/4FE23979BC61/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/E4774620DA>) |
| 11d9:a002 | 11d9:a003 | TEC              |                                      | 1     |            | [43275B430F](<All In One/Toshiba/4810360/4810360/EACF7DEC4786/UBUNTU-UNITY-22.04/5.15.0-83-GENERIC/X86_64/43275B430F>) |

### Parallel controller (bidir) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ee:8034 | 10ee:0007 | Xilinx           | Parallel controller                  | 1     | xdma       | [87EF2CAB75](<All In One/Intel/N5095-AIO/N5095-AIO T1/CB74E1346431/UBUNTU-20.04/5.15.0-107-GENERIC/X86_64/87EF2CAB75>) |

### Performance counters (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:27a3 |           | Intel            | 945GM/GU Chipset Hardware Monitor... | 46    |            | [DE3A243820](<All In One/Apple/iMac5/iMac5,1/1F7269B01AAF/DEBIAN-11/5.10.0-33-686-PAE/I686/DE3A243820>) |
| 8086:2f30 | 8086:2f30 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 2     | hswep_u... | [A9E76C81D7](<All In One/Acidanthera/iMacPro1/iMacPro1,1/9366E8057370/ROSA-12.4/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/A9E76C81D7>) |
| 8086:2f34 | 8086:2f34 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 PCI... | 2     | hswep_u... | [A9E76C81D7](<All In One/Acidanthera/iMacPro1/iMacPro1,1/9366E8057370/ROSA-12.4/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/A9E76C81D7>) |
| 8086:2f36 | 8086:2f36 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 2     | hswep_u... | [A9E76C81D7](<All In One/Acidanthera/iMacPro1/iMacPro1,1/9366E8057370/ROSA-12.4/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/A9E76C81D7>) |
| 8086:2f37 | 8086:2f37 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 2     | hswep_u... | [A9E76C81D7](<All In One/Acidanthera/iMacPro1/iMacPro1,1/9366E8057370/ROSA-12.4/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/A9E76C81D7>) |
| 8086:2f38 | 8086:2f38 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 2     | hswep_u... | [A9E76C81D7](<All In One/Acidanthera/iMacPro1/iMacPro1,1/9366E8057370/ROSA-12.4/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/A9E76C81D7>) |
| 8086:2f7d | 8086:2f7d | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 2     |            | [A9E76C81D7](<All In One/Acidanthera/iMacPro1/iMacPro1,1/9366E8057370/ROSA-12.4/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/A9E76C81D7>) |
| 8086:0e30 | 1043:84ef | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 1     | ivbep_u... | [259158AB96](<All In One/Acidanthera/iMacPro1/iMacPro1,1/F1829F0BF600/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/259158AB96>) |
| 8086:0e30 | 1458:3c46 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 1     | ivbep_u... | [A8D4959FDE](<All In One/Acidanthera/iMacPro1/iMacPro1,1/44B50065E23C/ELEMENTARY-6/5.11.0-25-GENERIC/X86_64/A8D4959FDE>) |
| 8086:0e34 | 1043:84ef | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 1     | ivbep_u... | [259158AB96](<All In One/Acidanthera/iMacPro1/iMacPro1,1/F1829F0BF600/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/259158AB96>) |
| 8086:0e34 | 1458:3c43 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 1     | ivbep_u... | [A8D4959FDE](<All In One/Acidanthera/iMacPro1/iMacPro1,1/44B50065E23C/ELEMENTARY-6/5.11.0-25-GENERIC/X86_64/A8D4959FDE>) |
| 8086:0e36 | 1043:84ef | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 1     | ivbep_u... | [259158AB96](<All In One/Acidanthera/iMacPro1/iMacPro1,1/F1829F0BF600/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/259158AB96>) |
| 8086:0e36 | 1458:3c44 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 1     | ivbep_u... | [A8D4959FDE](<All In One/Acidanthera/iMacPro1/iMacPro1,1/44B50065E23C/ELEMENTARY-6/5.11.0-25-GENERIC/X86_64/A8D4959FDE>) |
| 8086:2f32 | 8086:2f32 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 QPI... | 1     | hswep_u... | [B2AD449201](<All In One/Acidanthera/iMacPro1/iMacPro1,1/02ABD56D98BC/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/B2AD449201>) |
| 8086:2f33 | 8086:2f33 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 QPI... | 1     | hswep_u... | [B2AD449201](<All In One/Acidanthera/iMacPro1/iMacPro1,1/02ABD56D98BC/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/B2AD449201>) |

### Pic (8259) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:3422 |           | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 1     |            | [1786CF3D3D](<All In One/Gigabyte Technology/X58/X58A-UD3R/37288E45C1AD/ROSA-13.0/6.6.20-GENERIC-3ROSA2023.1-X86_64/X86_64/1786CF3D3D>) |
| 8086:3423 |           | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 1     |            | [1786CF3D3D](<All In One/Gigabyte Technology/X58/X58A-UD3R/37288E45C1AD/ROSA-13.0/6.6.20-GENERIC-3ROSA2023.1-X86_64/X86_64/1786CF3D3D>) |
| 8086:3425 |           | Intel            | 7500/5520/5500/X58 Physical and L... | 1     |            | [1786CF3D3D](<All In One/Gigabyte Technology/X58/X58A-UD3R/37288E45C1AD/ROSA-13.0/6.6.20-GENERIC-3ROSA2023.1-X86_64/X86_64/1786CF3D3D>) |
| 8086:3426 |           | Intel            | 7500/5520/5500/X58 Routing and Pr... | 1     |            | [1786CF3D3D](<All In One/Gigabyte Technology/X58/X58A-UD3R/37288E45C1AD/ROSA-13.0/6.6.20-GENERIC-3ROSA2023.1-X86_64/X86_64/1786CF3D3D>) |
| 8086:3427 |           | Intel            | 7500/5520/5500 Physical and Link ... | 1     |            | [1786CF3D3D](<All In One/Gigabyte Technology/X58/X58A-UD3R/37288E45C1AD/ROSA-13.0/6.6.20-GENERIC-3ROSA2023.1-X86_64/X86_64/1786CF3D3D>) |
| 8086:3428 |           | Intel            | 7500/5520/5500 Routing & Protocol... | 1     |            | [1786CF3D3D](<All In One/Gigabyte Technology/X58/X58A-UD3R/37288E45C1AD/ROSA-13.0/6.6.20-GENERIC-3ROSA2023.1-X86_64/X86_64/1786CF3D3D>) |
| 8086:342e |           | Intel            | 7500/5520/5500/X58 I/O Hub System... | 1     | i7core_... | [1786CF3D3D](<All In One/Gigabyte Technology/X58/X58A-UD3R/37288E45C1AD/ROSA-13.0/6.6.20-GENERIC-3ROSA2023.1-X86_64/X86_64/1786CF3D3D>) |

### Pic (io(x)-apic) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2f2c | 8086:0000 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 2     |            | [A9E76C81D7](<All In One/Acidanthera/iMacPro1/iMacPro1,1/9366E8057370/ROSA-12.4/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/A9E76C81D7>) |
| 8086:0e2c | 1043:84ef | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 1     |            | [259158AB96](<All In One/Acidanthera/iMacPro1/iMacPro1,1/F1829F0BF600/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/259158AB96>) |
| 8086:0e2c | 1458:5000 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 1     |            | [A8D4959FDE](<All In One/Acidanthera/iMacPro1/iMacPro1,1/44B50065E23C/ELEMENTARY-6/5.11.0-25-GENERIC/X86_64/A8D4959FDE>) |
| 8086:342d |           | Intel            | 7500/5520/5500/X58 I/O Hub I/OxAP... | 1     |            | [1786CF3D3D](<All In One/Gigabyte Technology/X58/X58A-UD3R/37288E45C1AD/ROSA-13.0/6.6.20-GENERIC-3ROSA2023.1-X86_64/X86_64/1786CF3D3D>) |
| 8086:342f |           | Intel            | 7500/5520/5500/X58 Trusted Execut... | 1     |            | [1786CF3D3D](<All In One/Gigabyte Technology/X58/X58A-UD3R/37288E45C1AD/ROSA-13.0/6.6.20-GENERIC-3ROSA2023.1-X86_64/X86_64/1786CF3D3D>) |

### Processing accelerators (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:7d1d | 1462:af01 | Intel            | Meteor Lake NPU                      | 1     |            | [552A70EE5C](<All In One/MSI/Modern/Modern MTL-U AM273Q/20D9DB06AD2F/RED-OS-7.3/6.1.110-1.EL7.3.X86_64/X86_64/552A70EE5C>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14e4:16bc | 14e4:0000 | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 475   | sdhci_pci  | [500ACCCF00](<All In One/Apple/iMac16/iMac16,2/D9F8E706C1F9/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/500ACCCF00>) |
| 14e4:16bc | 14e4:96bc | Broadcom Limited | BCM57765/57785 SDXC/MMC Card Reader  | 103   | sdhci_pci  | [8485C9B6A3](<All In One/Apple/iMac14/iMac14,2/DE6A385E2C03/ARCH-ROLLING/6.10.14-273-TKG-EEVDF/X86_64/8485C9B6A3>) |
| 14e4:16bc | 106b:0000 | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 38    | sdhci_pci  | [9D0D676179](<All In One/Apple/iMac13/iMac13,2/A3BD8470C792/ELEMENTARY-7.1/6.8.0-48-GENERIC/X86_64/9D0D676179>) |
| 8086:a375 | 103c:84ee | Intel            | 300 Series Chipset Family SD Host... | 23    | sdhci_pci  | [597321B19E](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/07E9499C7A2C/KDE-NEON-24.04/6.8.0-49-GENERIC/X86_64/597321B19E>) |
| 1217:8621 | 1217:0002 | O2 Micro         | SD/MMC Card Reader Controller        | 20    | sdhci_pci  | [F50F82AA00](<All In One/Dell/OptiPlex/OptiPlex 3030 AIO/366444499BD4/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/F50F82AA00>) |
| 10ec:5209 | 10ec:5209 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 15    | rtsx_pci   | [D364581A07](<All In One/LG Electronics/24V360/24V360-L.BJ55P1/D3E30446B8FF/LINUXMINT-21.2/5.15.0-89-GENERIC/X86_64/D364581A07>) |
| 197b:2381 | 1025:0266 | JMicron Techn... | Standard SD Host Controller          | 15    | sdhci_pci  | [9D826BCE47](<All In One/Acer/Aspire/Aspire Z5610/F8851F6F2232/LUBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9D826BCE47>) |
| 1180:e822 | 104d:9060 | Ricoh            | MMC/SD Host Controller               | 13    | sdhci_pci  | [18C8665A8A](<All In One/Sony/VPCL14/VPCL14S1E/05E16BA420D0/LINUXMINT-21.3/5.15.0-121-GENERIC/X86_64/18C8665A8A>) |
| 1217:8520 | 1028:0626 | O2 Micro         | SD/MMC Card Reader Controller        | 13    | sdhci_pci  | [1F361B3518](<All In One/Dell/Inspiron/Inspiron 23 Model 5348/D34B13017CE6/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/1F361B3518>) |
| 1217:8520 | 1028:0625 | O2 Micro         | SD/MMC Card Reader Controller        | 12    | sdhci_pci  | [C125805F0D](<All In One/Dell/OptiPlex/OptiPlex 9030 AIO/2EE105977E12/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/C125805F0D>) |
| 8086:31cc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 10    | sdhci_pci  | [BD9F5DD3DE](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/BD9F5DD3DE>) |
| 8086:5aca | 17aa:36c4 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 10    | sdhci_pci  | [321FD04E93](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 310-20IAP F0CL0014LD/4155E31B2EFA/OPENMANDRIVA-23.08/6.4.11-DESKTOP-1OMV2390/X86_64/321FD04E93>) |
| 8086:31d0 | 8086:7270 | Intel            | Celeron/Pentium Silver SD Host Co... | 8     | sdhci_pci  | [BD9F5DD3DE](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/BD9F5DD3DE>) |
| 1022:7813 | 103c:2b3b | AMD              | FCH SD Flash Controller              | 7     | sdhci_pci  | [6B7B46FFEF](<All In One/Hewlett-Packard/20/20-r118/91F17826BF90/UBUNTU-22.04/5.15.0-89-GENERIC/X86_64/6B7B46FFEF>) |
| 1180:e823 | 104d:907e | Ricoh            | PCIe SDXC/MMC Host Controller        | 7     | sdhci_pci  | [CB7D9BE78B](<All In One/Sony/VPCL236/VPCL236FX/7D6F7AF3086A/ZORIN-17/6.8.0-48-GENERIC/X86_64/CB7D9BE78B>) |
| 197b:2381 | 103c:1489 | JMicron Techn... | Standard SD Host Controller          | 7     | sdhci_pci  | [C53E87BCE8](<All In One/Hewlett-Packard/Compaq/Compaq 6000 Pro AiO Brazil PC/FB69A2D0E244/LINUXMINT-20.3/5.4.0-159-GENERIC/X86_64/C53E87BCE8>) |
| 8086:5acc | 1854:0267 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 7     | sdhci_pci  | [04D33628A1](<All In One/LG Electronics/22V270/22V270-L.BJ31P1/8E73444ADF98/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/04D33628A1>) |
| 1022:7813 | 1028:06d1 | AMD              | FCH SD Flash Controller              | 6     | sdhci_pci  | [5A7898E291](<All In One/Dell/Inspiron/Inspiron 24-3455/B6C810956CD7/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/5A7898E291>) |
| 1022:7906 | 1028:0854 | AMD              | FCH SD Flash Controller              | 6     | sdhci_pci  | [DDBB319D93](<All In One/Dell/Inspiron/Inspiron 3475 AIO/B6D9BD539D6C/DEBIAN-12/6.1.0-21-AMD64/X86_64/DDBB319D93>) |
| 1180:e822 | 104d:9074 | Ricoh            | MMC/SD Host Controller               | 6     | sdhci_pci  | [5BB2E62791](<All In One/Sony/VPCJ115/VPCJ115FX/D5A02AFB0F0F/FEDORA-40/6.10.11-200.FC40.X86_64/X86_64/5BB2E62791>) |
| 1180:e822 | 104d:907e | Ricoh            | MMC/SD Host Controller               | 6     | sdhci_pci  | [A8F1E64B41](<All In One/Sony/VPCL236/VPCL236FX/7D6F7AF3086A/ZORIN-17/6.8.0-49-GENERIC/X86_64/A8F1E64B41>) |
| 1180:e822 | 104d:9097 | Ricoh            | MMC/SD Host Controller               | 6     | sdhci_pci  | [0967107206](<All In One/Sony/SVL2412/SVL2412M1EB/A408433B792E/FEDORA-40/6.8.10-300.FC40.X86_64/X86_64/0967107206>) |
| 197b:2381 | 1025:0275 | JMicron Techn... | Standard SD Host Controller          | 6     | sdhci_pci  | [CF417581C6](<All In One/Packard Bell/ONETWO/ONETWO M3700/3C877DEEF801/LINUXMINT-22/6.8.0-47-GENERIC/X86_64/CF417581C6>) |
| 8086:31cc | 1043:1ea0 | Intel            | Celeron/Pentium Silver Processor ... | 6     | sdhci_pci  | [D1891AF126](<All In One/ASUSTek Computer/Vivo/Vivo AIO 16 V161GA_V161GA/AD72AFEBE798/XERO-ROLLING/6.6.4-ARCH1-1/X86_64/D1891AF126>) |
| 1022:7806 | 17aa:3670 | AMD              | FCH SD Flash Controller              | 5     | sdhci_pci  | [492077995D](<All In One/Lenovo/C245/C245 10114/397EE5A8B1C2/DEBIAN-23/5.10.203-LOC-OS/X86_64/492077995D>) |
| 1022:7906 | 17aa:36bd | AMD              | FCH SD Flash Controller              | 5     | sdhci_pci  | [D68501A3D9](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 510-23ASR F0CE002DAU/3B2CB02D55FF/DEBIAN-12/6.1.0-13-AMD64/X86_64/D68501A3D9>) |
| 1180:0822 | 104d:9044 | Ricoh            | R5C822 SD/SDIO/MMC/MS/MSPro Host ... | 5     | sdhci_pci  | [5CD160EA53](<All In One/Sony/VGC-JS1/VGC-JS1E_S/2F2CC13FD639/FEDORA-38/6.4.15-200.FC38.X86_64/X86_64/5CD160EA53>) |
| 1180:e822 | 104d:9083 | Ricoh            | MMC/SD Host Controller               | 5     | sdhci_pci  | [1F521568E1](<All In One/Sony/VPCJ23/VPCJ23S1R/38825FA7D374/ZORIN-16/5.15.0-57-GENERIC/X86_64/1F521568E1>) |
| 1180:e823 | 104d:9083 | Ricoh            | PCIe SDXC/MMC Host Controller        | 5     | sdhci_pci  | [44A108150C](<All In One/Sony/VPCJ21/VPCJ21S1E/6EEEF8B3CFB2/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/44A108150C>) |
| 197b:2381 | 17aa:3602 | JMicron Techn... | Standard SD Host Controller          | 5     | sdhci_pci  | [195EC7CB8C](<All In One/Lenovo/10051/10051/11244BE45969/LINUXMINT-20.3/5.4.0-126-GENERIC/X86_64/195EC7CB8C>) |
| 1180:0822 | 104d:9043 | Ricoh            | R5C822 SD/SDIO/MMC/MS/MSPro Host ... | 4     | sdhci_pci  | [653A82E6B9](<All In One/Sony/VGC-LV180/VGC-LV180ME/8D99388DD758/XEROLINUX-KDE-ROLLING/6.4.11-ARCH2-1/X86_64/653A82E6B9>) |
| 197b:2381 | 1025:0608 | JMicron Techn... | Standard SD Host Controller          | 4     | sdhci_pci  | [96FEDBC73A](<All In One/Acer/Aspire/Aspire Z3620/C16BEF866F4A/RED-OS-7.3/5.10.29-3.EL7.X86_64/X86_64/96FEDBC73A>) |
| 197b:2381 | 1043:842d | JMicron Techn... | Standard SD Host Controller          | 4     | sdhci_pci  | [34F80EF918](<All In One/ASUSTek Computer/ET2010/ET2010AG/82EF51037C47/UBUNTU-23.10/6.5.0-14-GENERIC/X86_64/34F80EF918>) |
| 197b:2381 | 1043:84c1 | JMicron Techn... | Standard SD Host Controller          | 4     | sdhci_pci  | [CBCA24B14A](<All In One/ASUSTek Computer/ET/ET2410/1D7A78AA84D4/MANJARO/6.10.13-3-MANJARO/X86_64/CBCA24B14A>) |
| 8086:31cc | 1043:1632 | Intel            | Celeron/Pentium Silver Processor ... | 4     | sdhci_pci  | [E0032832BD](<All In One/ASUSTek Computer/Vivo/Vivo AIO 16 V161GAR_V161GAR/6E27D5B514B0/ENDLESS-5.0.6/5.15.0-47-GENERIC/X86_64/E0032832BD>) |
| 8086:5aca | 8086:1e8b | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | sdhci_pci  | [2368B40C21](<All In One/Intel/AB2/AB2L/36E055E2A5D8/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/2368B40C21>) |
| 8086:5aca | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | sdhci_pci  | [D2C6F51FF8](<All In One/CSL-Computer/UNITY/UNITY F24B/D60F8F6679D1/ARCO-ROLLING/6.4.12-ARCH1-1/X86_64/D2C6F51FF8>) |
| 8086:5acc | 8086:1e8b | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | sdhci_pci  | [2368B40C21](<All In One/Intel/AB2/AB2L/36E055E2A5D8/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/2368B40C21>) |
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | sdhci_pci  | [D2C6F51FF8](<All In One/CSL-Computer/UNITY/UNITY F24B/D60F8F6679D1/ARCO-ROLLING/6.4.12-ARCH1-1/X86_64/D2C6F51FF8>) |
| 8086:5ad0 | 8086:1e8b | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | sdhci_pci  | [2368B40C21](<All In One/Intel/AB2/AB2L/36E055E2A5D8/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/2368B40C21>) |
| 8086:5ad0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | sdhci_pci  | [D2C6F51FF8](<All In One/CSL-Computer/UNITY/UNITY F24B/D60F8F6679D1/ARCO-ROLLING/6.4.12-ARCH1-1/X86_64/D2C6F51FF8>) |
| 1022:7806 | 1462:aa5e | AMD              | FCH SD Flash Controller              | 3     | sdhci_pci  | [70AECFA805](<All In One/MSI/MS-AA5/MS-AA5E/7189D63B22F7/UBUNTU-22.04/6.2.0-36-GENERIC/X86_64/70AECFA805>) |
| 1022:7906 | 1028:0855 | AMD              | FCH SD Flash Controller              | 3     | sdhci_pci  | [148CAF0684](<All In One/Dell/Inspiron/Inspiron 3275 AIO/B05F589A0D42/XERO-ROLLING/6.6.4-ARCH1-1/X86_64/148CAF0684>) |
| 1022:7906 | 17aa:36be | AMD              | FCH SD Flash Controller              | 3     | sdhci_pci  | [0759C30DD9](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 510-22ASR F0CC001BIX/E61608155EDF/UBUNTU-22.10/5.19.0-31-GENERIC/X86_64/0759C30DD9>) |
| 1022:7906 | 17aa:36e0 | AMD              | FCH SD Flash Controller              | 3     | sdhci_pci  | [F781FACD17](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-22AST F0D6000PLD/3E21F3CA09A6/UBUNTU-24.10/6.11.0-8-GENERIC/X86_64/F781FACD17>) |
| 10ec:5209 | 1b0a:0188 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 3     | sdhci_pci  | [0C24A93146](<All In One/Pegatron/H81/H81-P2/12407774A62B/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/0C24A93146>) |
| 1180:e823 | 104d:9097 | Ricoh            | PCIe SDXC/MMC Host Controller        | 3     | sdhci_pci  | [2EBADEA317](<All In One/Sony/SVL2411/SVL24117FLB/B337A07B7653/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/2EBADEA317>) |
| 197b:2391 | 103c:3561 | JMicron Techn... | Standard SD Host Controller          | 3     | sdhci_pci  | [AEF249E21A](<All In One/Hewlett-Packard/Z1/Z1 Workstation/8DD1D695BD68/ZORIN-16/5.15.0-88-GENERIC/X86_64/AEF249E21A>) |
| 197b:2391 | 1043:84c1 | JMicron Techn... | Standard SD Host Controller          | 3     | sdhci_pci  | [27D0310272](<All In One/ASUSTek Computer/ET2411/ET2411_W8/55B530902FB8/SPARKY-7.0/6.3.0-1-AMD64/X86_64/27D0310272>) |
| 8086:31cc | 8086:31cc | Intel            | Celeron/Pentium Silver Processor ... | 3     | sdhci_pci  | [702F3F3BC5](<All In One/Medion/E23201/E23201 MD61575/ADEBFF0ED21D/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/702F3F3BC5>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a324 | 8086:7270 | Intel            | Cannon Lake PCH SPI Controller       | 89    | spi_int... | [0C36BC1E93](<All In One/Apple/iMac19/iMac19,2/C074723931A0/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/0C36BC1E93>) |
| 8086:43a4 |           | Intel            | Tiger Lake-H SPI Controller          | 64    | intel_s... | [F969D9FB85](<All In One/ICL/RAY/RAY Si105.Mi/2E3E3E31C611/ROSA-12/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/F969D9FB85>) |
| 8086:43e8 |           | Intel            | Tiger Lake-H Serial IO I2C Contro... | 62    | intel_l... | [F969D9FB85](<All In One/ICL/RAY/RAY Si105.Mi/2E3E3E31C611/ROSA-12/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/F969D9FB85>) |
| 8086:43ea |           | Intel            | 500 Series Chipset Family LPSS: I... | 62    | intel_l... | [F969D9FB85](<All In One/ICL/RAY/RAY Si105.Mi/2E3E3E31C611/ROSA-12/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/F969D9FB85>) |
| 8086:43e9 |           | Intel            | Tiger Lake-H Serial IO I2C Contro... | 61    | intel_l... | [F969D9FB85](<All In One/ICL/RAY/RAY Si105.Mi/2E3E3E31C611/ROSA-12/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/F969D9FB85>) |
| 8086:a324 | 103c:84ee | Intel            | Cannon Lake PCH SPI Controller       | 23    | spi_int... | [597321B19E](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/07E9499C7A2C/KDE-NEON-24.04/6.8.0-49-GENERIC/X86_64/597321B19E>) |
| 8086:7aa4 |           | Intel            | Alder Lake-S PCH SPI Controller      | 14    | intel_s... | [0DAAF7E4B7](<All In One/DEPO Computers/DPH/DPH610T/1B53DCFC22E5/RED-OS-7.3/6.1.52-1.EL7.3.X86_64/X86_64/0DAAF7E4B7>) |
| 8086:7aab |           | Intel            | Alder Lake-S PCH Serial IO SPI Co... | 13    | intel_lpss | [0DAAF7E4B7](<All In One/DEPO Computers/DPH/DPH610T/1B53DCFC22E5/RED-OS-7.3/6.1.52-1.EL7.3.X86_64/X86_64/0DAAF7E4B7>) |
| 8086:a0a4 | 1028:0a06 | Intel            | Tiger Lake-LP SPI Controller         | 13    | intel_spi  | [078A22F745](<All In One/Dell/Inspiron/Inspiron 5400 AIO/D5D2451D1C1C/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/078A22F745>) |
| 8086:7acc |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 12    | intel_lpss | [0DAAF7E4B7](<All In One/DEPO Computers/DPH/DPH610T/1B53DCFC22E5/RED-OS-7.3/6.1.52-1.EL7.3.X86_64/X86_64/0DAAF7E4B7>) |
| 8086:7ace |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 12    | intel_lpss | [0DAAF7E4B7](<All In One/DEPO Computers/DPH/DPH610T/1B53DCFC22E5/RED-OS-7.3/6.1.52-1.EL7.3.X86_64/X86_64/0DAAF7E4B7>) |
| 8086:7acf |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 12    | intel_lpss | [0DAAF7E4B7](<All In One/DEPO Computers/DPH/DPH610T/1B53DCFC22E5/RED-OS-7.3/6.1.52-1.EL7.3.X86_64/X86_64/0DAAF7E4B7>) |
| 8086:7afc |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 12    | intel_lpss | [0DAAF7E4B7](<All In One/DEPO Computers/DPH/DPH610T/1B53DCFC22E5/RED-OS-7.3/6.1.52-1.EL7.3.X86_64/X86_64/0DAAF7E4B7>) |
| 8086:7afd |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 12    | intel_lpss | [0DAAF7E4B7](<All In One/DEPO Computers/DPH/DPH610T/1B53DCFC22E5/RED-OS-7.3/6.1.52-1.EL7.3.X86_64/X86_64/0DAAF7E4B7>) |
| 8086:a324 | 103c:8446 | Intel            | Cannon Lake PCH SPI Controller       | 11    | intel_spi  | [C5B5B31A25](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/7EFF5EC8D014/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/C5B5B31A25>) |
| 8086:9da4 | 17aa:3145 | Intel            | Cannon Point-LP SPI Controller       | 10    |            | [4FAC5AC06A](<All In One/Lenovo/V540-24IWL/V540-24IWL AIO 10YS0031RU/BC9666104DD6/ROSA-12/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/4FAC5AC06A>) |
| 8086:9da4 | 8086:7270 | Intel            | Cannon Point-LP SPI Controller       | 10    |            | [DBDFEC80AC](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/9D86375D22FA/LINUXMINT-21.2/5.15.0-91-GENERIC/X86_64/DBDFEC80AC>) |
| 8086:9dc5 | 1043:17b1 | Intel            | Cannon Point-LP Serial IO I2C Hos... | 10    | intel_lpss | [DBDFEC80AC](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/9D86375D22FA/LINUXMINT-21.2/5.15.0-91-GENERIC/X86_64/DBDFEC80AC>) |
| 8086:9de8 | 1043:17b1 | Intel            | Cannon Point-LP Serial IO I2C Con... | 10    | intel_lpss | [DBDFEC80AC](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/9D86375D22FA/LINUXMINT-21.2/5.15.0-91-GENERIC/X86_64/DBDFEC80AC>) |
| 8086:9de9 | 1043:17b1 | Intel            | Cannon Point-LP Serial IO I2C Con... | 10    | intel_lpss | [DBDFEC80AC](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/9D86375D22FA/LINUXMINT-21.2/5.15.0-91-GENERIC/X86_64/DBDFEC80AC>) |
| 8086:34a4 | 1025:1434 | Intel            | Ice Lake-LP SPI Controller           | 9     | intel_spi  | [DB7DFE3AC4](<All In One/Acer/Aspire/Aspire C22-963/468F69A6EF00/LINUX-LITE-5.6/5.4.0-182-GENERIC/X86_64/DB7DFE3AC4>) |
| 8086:34a4 | 1025:1418 | Intel            | Ice Lake-LP SPI Controller           | 8     | spi_int... | [A82A90955E](<All In One/Acer/Aspire/Aspire C27-962/563F493FD77F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/A82A90955E>) |
| 8086:7aa4 | 8086:7270 | Intel            | Alder Lake-S PCH SPI Controller      | 8     | spi_int... | [5AFCA2AEA2](<All In One/Others/A23/A23H66/95FE00C67093/ASTRA-1.7_X86-64/6.1.90-1-GENERIC/X86_64/5AFCA2AEA2>) |
| 8086:a324 | 103c:83eb | Intel            | Cannon Lake PCH SPI Controller       | 8     | intel_s... | [F655DC8E65](<All In One/Hewlett-Packard/ProOne/ProOne 440 G4 AiO/46615EAD4BA5/UBUNTU-22.04/6.2.0-34-GENERIC/X86_64/F655DC8E65>) |
| 8086:a324 | 103c:85a2 | Intel            | Cannon Lake PCH SPI Controller       | 8     | intel_spi  | [4C618F5DDE](<All In One/Hewlett-Packard/ProOne/ProOne 440 G5 23.8-in All-in-One/AC4148A4D238/RED-OS-8.0/6.6.6-1.RED80.X86_64/X86_64/4C618F5DDE>) |
| 8086:7acd |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 7     | intel_lpss | [6284551B74](<All In One/Graviton/D12/D12i/E65E993A1E87/ALT-10.1/6.1.38-UN-DEF-ALT1/X86_64/6284551B74>) |
| 8086:a324 | 17aa:3123 | Intel            | Cannon Lake PCH SPI Controller       | 7     |            | [9C31B501B0](<All In One/Lenovo/ThinkCentre/ThinkCentre M820z 10SDS01600/548A01155066/ROSA-12/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/9C31B501B0>) |
| 8086:43a4 | 1043:1aa2 | Intel            | Tiger Lake-H SPI Controller          | 6     | spi_int... | [E39C0B0B4F](<All In One/ASUSTek Computer/ASUS/ASUS EXPERTCENTER AIO E5402WHA_A5402WHA/B39572768AFF/FEDORA-41/6.11.5-300.FC41.X86_64/X86_64/E39C0B0B4F>) |
| 8086:43aa | 1043:1aa2 | Intel            | 500 Series Chipset Family LPSS: S... | 6     | intel_l... | [E39C0B0B4F](<All In One/ASUSTek Computer/ASUS/ASUS EXPERTCENTER AIO E5402WHA_A5402WHA/B39572768AFF/FEDORA-41/6.11.5-300.FC41.X86_64/X86_64/E39C0B0B4F>) |
| 8086:43ad | 1043:1aa2 | Intel            | 500 Series Chipset Family PCIe Po... | 6     | intel_l... | [E39C0B0B4F](<All In One/ASUSTek Computer/ASUS/ASUS EXPERTCENTER AIO E5402WHA_A5402WHA/B39572768AFF/FEDORA-41/6.11.5-300.FC41.X86_64/X86_64/E39C0B0B4F>) |
| 8086:43ae | 1043:1aa2 | Intel            | 500 Series Chipset Family PCIe Po... | 6     | intel_l... | [E39C0B0B4F](<All In One/ASUSTek Computer/ASUS/ASUS EXPERTCENTER AIO E5402WHA_A5402WHA/B39572768AFF/FEDORA-41/6.11.5-300.FC41.X86_64/X86_64/E39C0B0B4F>) |
| 8086:43e8 | 1043:1aa2 | Intel            | Tiger Lake-H Serial IO I2C Contro... | 6     | intel_l... | [E39C0B0B4F](<All In One/ASUSTek Computer/ASUS/ASUS EXPERTCENTER AIO E5402WHA_A5402WHA/B39572768AFF/FEDORA-41/6.11.5-300.FC41.X86_64/X86_64/E39C0B0B4F>) |
| 8086:43e9 | 1043:1aa2 | Intel            | Tiger Lake-H Serial IO I2C Contro... | 6     | intel_l... | [E39C0B0B4F](<All In One/ASUSTek Computer/ASUS/ASUS EXPERTCENTER AIO E5402WHA_A5402WHA/B39572768AFF/FEDORA-41/6.11.5-300.FC41.X86_64/X86_64/E39C0B0B4F>) |
| 8086:43ea | 1043:1aa2 | Intel            | 500 Series Chipset Family LPSS: I... | 6     | intel_l... | [E39C0B0B4F](<All In One/ASUSTek Computer/ASUS/ASUS EXPERTCENTER AIO E5402WHA_A5402WHA/B39572768AFF/FEDORA-41/6.11.5-300.FC41.X86_64/X86_64/E39C0B0B4F>) |
| 8086:43eb | 1043:1aa2 | Intel            | 500 Series Chipset Family LPSS: I... | 6     | intel_l... | [E39C0B0B4F](<All In One/ASUSTek Computer/ASUS/ASUS EXPERTCENTER AIO E5402WHA_A5402WHA/B39572768AFF/FEDORA-41/6.11.5-300.FC41.X86_64/X86_64/E39C0B0B4F>) |
| 8086:a0a4 | 1043:1482 | Intel            | Tiger Lake-LP SPI Controller         | 6     | spi_int... | [E02555BD07](<All In One/ASUSTek Computer/ASUS/ASUS Vivo AIO V241EA_V241EA/68A1C9B65FAA/LMDE-6/6.10.6+BPO-AMD64/X86_64/E02555BD07>) |
| 8086:a324 | 1028:084b | Intel            | Cannon Lake PCH SPI Controller       | 6     | spi_int... | [9352E7ED07](<All In One/Dell/OptiPlex/OptiPlex 7460 AIO/AAD8696E4652/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9352E7ED07>) |
| 8086:06a4 | 8086:7270 | Intel            | Comet Lake PCH SPI Controller        | 5     | spi_int... | [E4774620DA](<All In One/Apple/iMac20/iMac20,1/4FE23979BC61/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/E4774620DA>) |
| 8086:34a4 | 103c:87a4 | Intel            | Ice Lake-LP SPI Controller           | 5     | spi_int... | [AC3D0DEECE](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-dp0xxx/118251C361CB/UBUNTU-22.04/5.19.0-50-GENERIC/X86_64/AC3D0DEECE>) |
| 8086:a0a4 | 103c:87f3 | Intel            | Tiger Lake-LP SPI Controller         | 5     | spi_int... | [5738460F11](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-df1xxx/FD9660C572E0/DEBIAN-12/6.1.0-18-AMD64/X86_64/5738460F11>) |
| 8086:06a4 | 1028:0984 | Intel            | Comet Lake PCH SPI Controller        | 4     | spi_int... | [D613941D95](<All In One/Dell/OptiPlex/OptiPlex 7480 AIO/203C46736888/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/D613941D95>) |
| 8086:4da4 |           | Intel            | Jasper Lake SPI Controller           | 4     | intel_s... | [87EF2CAB75](<All In One/Intel/N5095-AIO/N5095-AIO T1/CB74E1346431/UBUNTU-20.04/5.15.0-107-GENERIC/X86_64/87EF2CAB75>) |
| 8086:4dab |           | Intel            | Jasper Lake Serial IO SPI Control... | 4     | intel_l... | [87EF2CAB75](<All In One/Intel/N5095-AIO/N5095-AIO T1/CB74E1346431/UBUNTU-20.04/5.15.0-107-GENERIC/X86_64/87EF2CAB75>) |
| 8086:4dc5 |           | Intel            | Jasper Lake Serial IO I2C Host Co... | 4     | intel_l... | [87EF2CAB75](<All In One/Intel/N5095-AIO/N5095-AIO T1/CB74E1346431/UBUNTU-20.04/5.15.0-107-GENERIC/X86_64/87EF2CAB75>) |
| 8086:4de8 |           | Intel            | Jasper Lake Serial IO I2C Host Co... | 4     | intel_l... | [87EF2CAB75](<All In One/Intel/N5095-AIO/N5095-AIO T1/CB74E1346431/UBUNTU-20.04/5.15.0-107-GENERIC/X86_64/87EF2CAB75>) |
| 8086:4dea |           | Intel            | Jasper Lake Serial IO I2C Host Co... | 4     | intel_l... | [87EF2CAB75](<All In One/Intel/N5095-AIO/N5095-AIO T1/CB74E1346431/UBUNTU-20.04/5.15.0-107-GENERIC/X86_64/87EF2CAB75>) |
| 8086:9da4 | 17aa:36fe | Intel            | Cannon Point-LP SPI Controller       | 4     | intel_spi  | [135BA52D4B](<All In One/Lenovo/IdeaCentre/IdeaCentre A340-22IWL F0EB00AETX/A0CAC1147F41/ZORIN-17/6.8.0-45-GENERIC/X86_64/135BA52D4B>) |
| 8086:a0a4 |           | Intel            | Tiger Lake-LP SPI Controller         | 4     | intel_spi  | [8C98F96505](<All In One/Medion/E/E23405/C126BD27298A/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/8C98F96505>) |
| 8086:a0a4 | 1025:1475 | Intel            | Tiger Lake-LP SPI Controller         | 4     |            | [B2AB898336](<All In One/Acer/Aspire/Aspire C24-1650/378838E43C4A/ASTRA-1.7_X86-64/6.1.50-1-GENERIC/X86_64/B2AB898336>) |
| 8086:a0a4 | 1025:150f | Intel            | Tiger Lake-LP SPI Controller         | 4     | intel_s... | [4FE6CA7F88](<All In One/Acer/Aspire/Aspire C27-1655/38F1D8798E6E/RED-OS-7.3.2/5.15.87-1.EL7.3.X86_64/X86_64/4FE6CA7F88>) |

### Serial controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1e3d | 1028:0543 | Intel            | 7 Series/C210 Series Chipset Fami... | 18    | serial     | [A552EB99EE](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/B658E6C46850/ZORIN-17/6.8.0-49-GENERIC/X86_64/A552EB99EE>) |
| 8086:8c3d | 1028:05a7 | Intel            | 8 Series/C220 Series Chipset Fami... | 12    | serial     | [F866E174C2](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/5BD2C4C72DD4/FEDORA-40/6.10.8-200.FC40.X86_64/X86_64/F866E174C2>) |
| 8086:a13d | 1028:06c5 | Intel            | 100 Series/C230 Series Chipset Fa... | 9     | serial     | [48FC1B98F3](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/3270F32DC629/UBUNTU-22.04/6.8.0-40-GENERIC/X86_64/48FC1B98F3>) |
| 8086:a363 | 103c:83eb | Intel            | Cannon Lake PCH Active Management... | 8     | serial     | [F655DC8E65](<All In One/Hewlett-Packard/ProOne/ProOne 440 G4 AiO/46615EAD4BA5/UBUNTU-22.04/6.2.0-34-GENERIC/X86_64/F655DC8E65>) |
| 8086:2e17 | 103c:1489 | Intel            | 4 Series Chipset Serial KT Contro... | 7     | serial     | [C53E87BCE8](<All In One/Hewlett-Packard/Compaq/Compaq 6000 Pro AiO Brazil PC/FB69A2D0E244/LINUXMINT-20.3/5.4.0-159-GENERIC/X86_64/C53E87BCE8>) |
| 8086:a363 | 103c:85a2 | Intel            | Cannon Lake PCH Active Management... | 7     | serial     | [4C618F5DDE](<All In One/Hewlett-Packard/ProOne/ProOne 440 G5 23.8-in All-in-One/AC4148A4D238/RED-OS-8.0/6.6.6-1.RED80.X86_64/X86_64/4C618F5DDE>) |
| 8086:1c3d | 103c:3395 | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | serial     | [1DC6B38792](<All In One/Hewlett-Packard/Compaq/Compaq 8200 Elite AiO Business PC/C2F2EF898782/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/1DC6B38792>) |
| 8086:a13d | 103c:805e | Intel            | 100 Series/C230 Series Chipset Fa... | 5     | serial     | [EB19C3207D](<All In One/Hewlett-Packard/ProOne/ProOne 600 G2 21.5-in Non-Touch AiO/95CE8F95FEA5/LINUXMINT-21.3/5.15.0-124-GENERIC/X86_64/EB19C3207D>) |
| 8086:a13d | 17aa:30ba | Intel            | 100 Series/C230 Series Chipset Fa... | 5     | serial     | [FE3F87CD1C](<All In One/Lenovo/ThinkCentre/ThinkCentre M900z 10F4S0FW00/F174AA1FA46B/BIG/6.9.10-X64V2-XANMOD1-1/X86_64/FE3F87CD1C>) |
| 8086:a2bd | 1028:079c | Intel            | 200 Series Chipset Family KT Redi... | 5     | serial     | [19034B5BCD](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/0C6402FD4D76/FEDORA-40/6.9.5-200.FC40.X86_64/X86_64/19034B5BCD>) |
| 8086:a2bd | 103c:829b | Intel            | 200 Series Chipset Family KT Redi... | 5     | serial     | [349DDEFD63](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G3 23.8-in Non-Touch AiO/DCF7AC139838/DEBIAN-12/6.1.0-27-AMD64/X86_64/349DDEFD63>) |
| 8086:8c3d | 1028:0625 | Intel            | 8 Series/C220 Series Chipset Fami... | 4     | serial     | [8FE8D8B38E](<All In One/Dell/OptiPlex/OptiPlex 9030 AIO/6D792C13AB31/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/8FE8D8B38E>) |
| 8086:a13d | 103c:8058 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     | serial     | [2A0C07D92F](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G2 23-in Non-Touch AiO/793E2F6A2AAF/UBUNTU-BUDGIE-22.04/6.5.0-25-GENERIC/X86_64/2A0C07D92F>) |
| 8086:a363 | 1028:084b | Intel            | Cannon Lake PCH Active Management... | 4     | serial     | [9352E7ED07](<All In One/Dell/OptiPlex/OptiPlex 7460 AIO/AAD8696E4652/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9352E7ED07>) |
| 10ec:816a | 1025:1071 | Realtek Semic... | RTL8111xP UART #1                    | 3     | serial     | [910DA2B318](<All In One/Acer/Veriton/Veriton Z4820G/F80CAA7F129B/DEBIAN-12/6.1.0-4-AMD64/X86_64/910DA2B318>) |
| 10ec:816a | 1025:1291 | Realtek Semic... | RTL8111xP UART #1                    | 3     | serial     | [9949F21F98](<All In One/Acer/Veriton/Veriton Z4660G/D6F2FD870657/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/9949F21F98>) |
| 10ec:816b | 1025:1071 | Realtek Semic... | RTL8111xP UART #2                    | 3     | serial     | [910DA2B318](<All In One/Acer/Veriton/Veriton Z4820G/F80CAA7F129B/DEBIAN-12/6.1.0-4-AMD64/X86_64/910DA2B318>) |
| 10ec:816b | 1025:1291 | Realtek Semic... | RTL8111xP UART #2                    | 3     | serial     | [9949F21F98](<All In One/Acer/Veriton/Veriton Z4660G/D6F2FD870657/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/9949F21F98>) |
| 8086:1c3d | 103c:3561 | Intel            | 6 Series/C200 Series Chipset Fami... | 3     | serial     | [AEF249E21A](<All In One/Hewlett-Packard/Z1/Z1 Workstation/8DD1D695BD68/ZORIN-16/5.15.0-88-GENERIC/X86_64/AEF249E21A>) |
| 8086:7aeb | 103c:895f | Intel            | Alder Lake-S Keyboard and Text (K... | 3     | serial     | [9322FD4F07](<All In One/Hewlett-Packard/EliteOne/EliteOne 840 23.8 inch G9 All-in-One Desktop PC/498408D620FC/DEBIAN-12/6.1.0-13-AMD64/X86_64/9322FD4F07>) |
| 8086:a363 | 1028:0935 | Intel            | Cannon Lake PCH Active Management... | 3     | 8250_pci   | [24F4FE0749](<All In One/Dell/OptiPlex/OptiPlex 7470 AIO/FAB31B65ADDC/OPENMANDRIVA-24.08/6.10.1-DESKTOP-1OMV2490/X86_64/24F4FE0749>) |
| 8086:a363 | 17aa:3122 | Intel            | Cannon Lake PCH Active Management... | 3     | serial     | [1CEDCA3D56](<All In One/Lenovo/ThinkCentre/ThinkCentre M920z 10S6002CUS/1A24639ED68C/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/1CEDCA3D56>) |
| 10ec:816a | 1025:1290 | Realtek Semic... | RTL8111xP UART #1                    | 2     |            | [A27363041A](<All In One/Acer/Veriton/Veriton Z4860G/8955EDC1BE49/ENDLESS-3.9.1/5.8.0-14-GENERIC/X86_64/A27363041A>) |
| 10ec:816b | 1025:1290 | Realtek Semic... | RTL8111xP UART #2                    | 2     |            | [A27363041A](<All In One/Acer/Veriton/Veriton Z4860G/8955EDC1BE49/ENDLESS-3.9.1/5.8.0-14-GENERIC/X86_64/A27363041A>) |
| 8086:06e3 | 103c:871c | Intel            | Comet Lake Keyboard and Text (KT)... | 2     | serial     | [4EBF5AEE4D](<All In One/Hewlett-Packard/ProOne/ProOne 440 G6 24 All-in-One PC/296F5C66A419/FEDORA-29/6.2.9-300.FC38.X86_64/X86_64/4EBF5AEE4D>) |
| 8086:43fc | 1043:1aa2 | Intel            | Tiger Lake-H Integrated Sensor Hub   | 2     | intel_i... | [F9654565DB](<All In One/ASUSTek Computer/ASUS/ASUS EXPERTCENTER AIO E5402WHA_E5402WHA/2F927D8C21DD/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/F9654565DB>) |
| 8086:7af8 | 103c:895f | Intel            | Alder Lake-S Integrated Sensor Hub   | 2     | intel_i... | [1F8AE4F41B](<All In One/Hewlett-Packard/EliteOne/EliteOne 870 27 inch G9 All-in-One Desktop PC/B3DBA47ACDD5/RED-OS-7.3.2/5.15.87-1.EL7.3.X86_64/X86_64/1F8AE4F41B>) |
| 8086:a13d | 1028:075d | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | serial     | [404A8B3A68](<All In One/Dell/Precision/Precision 5720 AIO/20C5601ED4D8/FEDORA-30/5.2.16-200.FC30.X86_64/X86_64/404A8B3A68>) |
| 8086:a2bd | 17aa:3110 | Intel            | 200 Series Chipset Family KT Redi... | 2     | serial     | [CDE94F0C8E](<All In One/Lenovo/ThinkCentre/ThinkCentre M910z 10NS0003US/D3A4B2847E9F/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/CDE94F0C8E>) |
| 8086:a363 | 1028:084a | Intel            | Cannon Lake PCH Active Management... | 2     | serial     | [1B26CA48D1](<All In One/Dell/OptiPlex/OptiPlex 7760 AIO/9D965492255A/MANJARO/6.7.0-3-RT6-MANJARO/X86_64/1B26CA48D1>) |
| 8086:a363 | 103c:83e5 | Intel            | Cannon Lake PCH Active Management... | 2     | serial     | [1C613CDC9D](<All In One/Hewlett-Packard/EliteOne/EliteOne 1000 G2 34-in Curved AiO/1A5E72A90EE1/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/1C613CDC9D>) |
| 8086:a363 | 103c:85a0 | Intel            | Cannon Lake PCH Active Management... | 2     | serial     | [E4CA5EE60C](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G5 23.8-in All-in-One/5E3FC1B9F803/KALI-2024.3/6.10.11-AMD64/X86_64/E4CA5EE60C>) |
| 10ec:816a | 10ec:0123 | Realtek Semic... | RTL8111xP UART #1                    | 1     | serial     | [2278A5C6EA](<All In One/Samsung Electronics/SUR/SUR40/9A8E67BB1389/DEBIAN-11/5.19.0-2-AMD64/X86_64/2278A5C6EA>) |
| 10ec:816b | 10ec:0123 | Realtek Semic... | RTL8111xP UART #2                    | 1     | serial     | [2278A5C6EA](<All In One/Samsung Electronics/SUR/SUR40/9A8E67BB1389/DEBIAN-11/5.19.0-2-AMD64/X86_64/2278A5C6EA>) |
| 13a8:0354 |           | Exar             | Exar's 4-Port UART PCIe Card         | 1     | 8250_exar  | [B5FBC6A19B](<All In One/Lenovo/IdeaCentre/IdeaCentre B540p 3363/9976329CE6AE/UBUNTU-20.04/5.4.0-31-GENERIC/X86_64/B5FBC6A19B>) |
| 8086:06e3 | 1028:0984 | Intel            | Comet Lake Keyboard and Text (KT)... | 1     | serial     | [D613941D95](<All In One/Dell/OptiPlex/OptiPlex 7480 AIO/203C46736888/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/D613941D95>) |
| 8086:06e3 | 103c:871b | Intel            | Comet Lake Keyboard and Text (KT)... | 1     | serial     | [EB4B572A21](<All In One/Hewlett-Packard/ProOne/ProOne 440 G6 24 All-in-One PC/99C228B86E44/DEBIAN-11/5.10.0-16-AMD64/X86_64/EB4B572A21>) |
| 8086:1c3d | 1c1d:0001 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | serial     | [4E2FFC0DB7](<All In One/InFocus/INF/INF5520/89A8A2E44A06/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/4E2FFC0DB7>) |
| 8086:1e3d | 1028:0577 | Intel            | 7 Series/C210 Series Chipset Fami... | 1     | serial     | [E7CE3F2F38](<All In One/Acidanthera/iMacPro1/iMacPro1,1/C2AEF029DC5F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E7CE3F2F38>) |
| 8086:1e3d | 103c:3397 | Intel            | 7 Series/C210 Series Chipset Fami... | 1     | 8250_pci   | [DA2B320CD5](<All In One/Acidanthera/iMacPro1/iMacPro1,1/3A3FCACBB40C/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/DA2B320CD5>) |
| 8086:1e3d | 1854:f004 | Intel            | 7 Series/C210 Series Chipset Fami... | 1     | serial     | [81CF385125](<All In One/LG Electronics/SUPERSIGN/SUPERSIGN/3DF362B44399/ROSA-2012.0/3.0.28-NRJ-DESKTOP-2ROSA.LTS/X86_64/81CF385125>) |
| 8086:51fc | 17aa:3767 | Intel            | Alder Lake-P Integrated Sensor Hub   | 1     | intel_i... | [F9F38488A8](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 5 27IAH7 F0GQ0001US/D9930DEAC59F/POP!_OS-22.04/6.0.12-76060006-GENERIC/X86_64/F9F38488A8>) |
| 8086:7aeb | 1028:0bca | Intel            | Alder Lake-S Keyboard and Text (K... | 1     | serial     | [DE2DB89E95](<All In One/Dell/OptiPlex/OptiPlex AIO Plus 7410/2B12100B99B3/DEBIAN-12/6.1.0-18-AMD64/X86_64/DE2DB89E95>) |
| 8086:7aeb | 103c:8959 | Intel            | Alder Lake-S Keyboard and Text (K... | 1     | 8250_pci   | [68870F0170](<All In One/Hewlett-Packard/ProOne/ProOne 440 23.8 inch G9 All-in-One Desktop PC/3551A8213F41/OPENMANDRIVA-23.10/6.5.5-DESKTOP-1OMV2390/X86_64/68870F0170>) |
| 8086:7aeb | 17aa:3306 | Intel            | Alder Lake-S Keyboard and Text (K... | 1     | serial     | [06B63083C7](<All In One/Lenovo/ThinkCentre/ThinkCentre M90a Gen 3 11VH001XIF/40E704AA128F/FEDORA-39/6.7.6-200.FC39.X86_64/X86_64/06B63083C7>) |
| 8086:7aeb | 8086:0000 | Intel            | Alder Lake-S Keyboard and Text (K... | 1     | serial     | [401238AE67](<All In One/Graviton/M55/M55i/A2D620B78C13/RED-OS-7.3/6.1.52-1.EL7.3.X86_64/X86_64/401238AE67>) |
| 8086:7af8 | 1028:0bca | Intel            | Alder Lake-S Integrated Sensor Hub   | 1     | intel_i... | [DE2DB89E95](<All In One/Dell/OptiPlex/OptiPlex AIO Plus 7410/2B12100B99B3/DEBIAN-12/6.1.0-18-AMD64/X86_64/DE2DB89E95>) |
| 8086:7af8 | 17aa:3306 | Intel            | Alder Lake-S Integrated Sensor Hub   | 1     | intel_i... | [06B63083C7](<All In One/Lenovo/ThinkCentre/ThinkCentre M90a Gen 3 11VH001XIF/40E704AA128F/FEDORA-39/6.7.6-200.FC39.X86_64/X86_64/06B63083C7>) |
| 8086:8c3d | 8086:204c | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | serial     | [098FE372A3](<All In One/Acidanthera/iMac14/iMac14,4/E2C69985CC45/GENTOO-2.6/5.4.97-GENTOO_DQ87PG/X86_64/098FE372A3>) |
| 8086:8c3d | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | serial     | [9521B934FE](<All In One/4POS/POS-560/POS-560 WidePOS GT II/DB050BAEAD82/FEDORA-37/6.2.9-200.FC37.X86_64/X86_64/9521B934FE>) |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:3b32 | 8086:0000 | Intel            | 5 Series/3400 Series Chipset Ther... | 152   | intel_ips  | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 8086:a379 | 8086:7270 | Intel            | Cannon Lake PCH Thermal Controller   | 82    | intel_p... | [0C36BC1E93](<All In One/Apple/iMac19/iMac19,2/C074723931A0/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/0C36BC1E93>) |
| 8086:8ca4 | 8086:7270 | Intel            | 9 Series Chipset Family Thermal C... | 44    |            | [500ACCCF00](<All In One/Apple/iMac16/iMac16,2/D9F8E706C1F9/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/500ACCCF00>) |
| 8086:9a0d |           | Intel            | Tigerlake Telemetry Aggregator       | 38    | intel_vsec | [E39C0B0B4F](<All In One/ASUSTek Computer/ASUS/ASUS EXPERTCENTER AIO E5402WHA_A5402WHA/B39572768AFF/FEDORA-41/6.11.5-300.FC41.X86_64/X86_64/E39C0B0B4F>) |
| 8086:467d |           | Intel            | Platform Monitoring Technology       | 30    | intel_vsec | [7A69DE9AC1](<All In One/Minix/NEO/NEO Z100-0dB/4F3A1C899285/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/7A69DE9AC1>) |
| 8086:9d61 | 8086:9d61 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 30    | intel_lpss | [A7F55BE076](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/F6FC816725AE/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/A7F55BE076>) |
| 8086:a2b1 | 1019:a5a1 | Intel            | 200 Series PCH Thermal Subsystem     | 24    |            | [46658F67D3](<All In One/ICL/H310/H310SB-TM/298E8E81F4C1/ROSA-12/6.1.81-GENERIC-2ROSA2021.1-X86_64/X86_64/46658F67D3>) |
| 8086:a379 | 103c:84ee | Intel            | Cannon Lake PCH Thermal Controller   | 23    | intel_p... | [597321B19E](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/07E9499C7A2C/KDE-NEON-24.04/6.8.0-49-GENERIC/X86_64/597321B19E>) |
| 8086:9d60 | 103c:84de | Intel            | Sunrise Point-LP Serial IO I2C Co... | 19    | intel_lpss | [A7F55BE076](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/F6FC816725AE/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/A7F55BE076>) |
| 8086:a131 | 1028:06c5 | Intel            | 100 Series/C230 Series Chipset Fa... | 18    | intel_p... | [CCDA6EA567](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/2A418C925C5B/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/CCDA6EA567>) |
| 8086:318c | 1854:0308 | Intel            | Celeron/Pentium Silver Processor ... | 15    | process... | [A595C7B829](<All In One/LG Electronics/22V280/22V280-L.BJ31P1/BE8548B5DD51/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/A595C7B829>) |
| 8086:3a32 | 1025:0266 | Intel            | 82801JI (ICH10 Family) Thermal Su... | 15    |            | [9D826BCE47](<All In One/Acer/Aspire/Aspire Z5610/F8851F6F2232/LUBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9D826BCE47>) |
| 8086:9d31 | 1025:1287 | Intel            | Sunrise Point-LP Thermal subsystem   | 15    | intel_p... | [08963EC448](<All In One/Acer/Aspire/Aspire C24-865/78DC8340D315/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/08963EC448>) |
| 8086:22dc |           | Intel            | Atom/Celeron/Pentium Processor x5... | 14    | proc_th... | [B62E73BAB2](<All In One/Dell/Inspiron/Inspiron 20-3052/862CDCFFAAFA/FEDORA-39/6.7.6-200.FC39.X86_64/X86_64/B62E73BAB2>) |
| 8086:9d31 | 8086:9d31 | Intel            | Sunrise Point-LP Thermal subsystem   | 14    | intel_p... | [555F0208DB](<All In One/ASUSTek Computer/V241/V241IC-R/86B3953D53F1/UBUNTU-22.04/6.2.0-39-GENERIC/X86_64/555F0208DB>) |
| 8086:a2b1 | 1028:079c | Intel            | 200 Series PCH Thermal Subsystem     | 14    |            | [D019C812B7](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/360F073CECA0/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/D019C812B7>) |
| 8086:a2e0 | 1028:079c | Intel            | 200 Series PCH Serial IO I2C Cont... | 14    | intel_l... | [D019C812B7](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/360F073CECA0/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/D019C812B7>) |
| 8086:318c | 1025:1304 | Intel            | Celeron/Pentium Silver Processor ... | 12    | proc_th... | [31F323613D](<All In One/Acer/Aspire/Aspire C22-820/D247EFB9442C/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/31F323613D>) |
| 8086:9ca4 | 8086:7270 | Intel            | Wildcat Point-LP Thermal Manageme... | 12    | intel_p... | [E9F3801A74](<All In One/Apple/iMac16/iMac16,1/A877523A0FA6/LINUXMINT-22/6.8.0-45-GENERIC/X86_64/E9F3801A74>) |
| 8086:9d60 | 8086:9d60 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 11    | intel_lpss | [555F0208DB](<All In One/ASUSTek Computer/V241/V241IC-R/86B3953D53F1/UBUNTU-22.04/6.2.0-39-GENERIC/X86_64/555F0208DB>) |
| 8086:a379 | 103c:8446 | Intel            | Cannon Lake PCH Thermal Controller   | 11    | intel_p... | [C5B5B31A25](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/7EFF5EC8D014/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/C5B5B31A25>) |
| 8086:1903 | 1043:17b1 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 10    | proc_th... | [DBDFEC80AC](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/9D86375D22FA/LINUXMINT-21.2/5.15.0-91-GENERIC/X86_64/DBDFEC80AC>) |
| 8086:1903 | 8086:1903 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 10    | proc_th... | [555F0208DB](<All In One/ASUSTek Computer/V241/V241IC-R/86B3953D53F1/UBUNTU-22.04/6.2.0-39-GENERIC/X86_64/555F0208DB>) |
| 8086:5a8c | 17aa:36c4 | Intel            | Atom/Celeron/Pentium Dynamic Plat... | 10    | process... | [321FD04E93](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 310-20IAP F0CL0014LD/4155E31B2EFA/OPENMANDRIVA-23.08/6.4.11-DESKTOP-1OMV2390/X86_64/321FD04E93>) |
| 8086:9df9 | 1043:17b1 | Intel            | Cannon Point-LP Thermal Controller   | 10    | intel_p... | [DBDFEC80AC](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/9D86375D22FA/LINUXMINT-21.2/5.15.0-91-GENERIC/X86_64/DBDFEC80AC>) |
| 8086:9df9 | 17aa:3145 | Intel            | Cannon Point-LP Thermal Controller   | 10    | intel_p... | [4FAC5AC06A](<All In One/Lenovo/V540-24IWL/V540-24IWL AIO 10YS0031RU/BC9666104DD6/ROSA-12/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/4FAC5AC06A>) |
| 8086:a131 | 8086:a131 | Intel            | 100 Series/C230 Series Chipset Fa... | 10    | intel_p... | [B9F363DA1B](<All In One/ASUSTek Computer/Z240/Z240IC-H170/BD8C045F6FC1/FEDORA-40/6.9.10-200.FC40.X86_64/X86_64/B9F363DA1B>) |
| 8086:5a8c |           | Intel            | Atom/Celeron/Pentium Dynamic Plat... | 9     | process... | [D2C6F51FF8](<All In One/CSL-Computer/UNITY/UNITY F24B/D60F8F6679D1/ARCO-ROLLING/6.4.12-ARCH1-1/X86_64/D2C6F51FF8>) |
| 8086:9d31 | 1028:0754 | Intel            | Sunrise Point-LP Thermal subsystem   | 9     | intel_p... | [274DC30D2C](<All In One/Dell/Inspiron/Inspiron 3464 AIO/31AD17DDDC01/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/274DC30D2C>) |
| 8086:9d60 | 1028:0754 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 9     | intel_l... | [274DC30D2C](<All In One/Dell/Inspiron/Inspiron 3464 AIO/31AD17DDDC01/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/274DC30D2C>) |
| 8086:9d61 | 1028:0754 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 9     | intel_l... | [274DC30D2C](<All In One/Dell/Inspiron/Inspiron 3464 AIO/31AD17DDDC01/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/274DC30D2C>) |
| 8086:a3b1 | 8086:7270 | Intel            | Comet Lake PCH-V Thermal Subsystem   | 9     |            | [D958890B05](<All In One/MSI/H410/H410 PRO 22X 10M/C99FDE38C032/RED-OS-7.3.2/6.1.20-2.EL7.3.X86_64/X86_64/D958890B05>) |
| 8086:a127 | 1462:b090 | Intel            | 100 Series/C230 Series Chipset Fa... | 8     | intel_lpss | [D80B4E7372](<All In One/MSI/MS-B/MS-B09012/AFC51AE1EE8A/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/D80B4E7372>) |
| 8086:a131 | 1462:b090 | Intel            | 100 Series/C230 Series Chipset Fa... | 8     | intel_p... | [D80B4E7372](<All In One/MSI/MS-B/MS-B09012/AFC51AE1EE8A/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/D80B4E7372>) |
| 8086:a160 | 1462:b090 | Intel            | 100 Series/C230 Series Chipset Fa... | 8     | intel_lpss | [D80B4E7372](<All In One/MSI/MS-B/MS-B09012/AFC51AE1EE8A/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/D80B4E7372>) |
| 8086:a161 | 1462:b090 | Intel            | 100 Series/C230 Series Chipset Fa... | 8     | intel_lpss | [D80B4E7372](<All In One/MSI/MS-B/MS-B09012/AFC51AE1EE8A/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/D80B4E7372>) |
| 8086:a379 | 103c:83eb | Intel            | Cannon Lake PCH Thermal Controller   | 8     | intel_p... | [F655DC8E65](<All In One/Hewlett-Packard/ProOne/ProOne 440 G4 AiO/46615EAD4BA5/UBUNTU-22.04/6.2.0-34-GENERIC/X86_64/F655DC8E65>) |
| 8086:a379 | 103c:85a2 | Intel            | Cannon Lake PCH Thermal Controller   | 8     | intel_p... | [4C618F5DDE](<All In One/Hewlett-Packard/ProOne/ProOne 440 G5 23.8-in All-in-One/AC4148A4D238/RED-OS-8.0/6.6.6-1.RED80.X86_64/X86_64/4C618F5DDE>) |
| 8086:1e24 | 1462:b062 | Intel            | 7 Series/C210 Series Chipset Fami... | 7     |            | [3D6C67056E](<All In One/MSI/MS-B/MS-B06211/8A065298C446/LUBUNTU-22.04/6.8.0-45-GENERIC/X86_64/3D6C67056E>) |
| 8086:318c | 103c:86f0 | Intel            | Celeron/Pentium Silver Processor ... | 7     | process... | [45026F50EF](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-df0xxx/34F078141D24/KUBUNTU-22.04/5.15.0-73-LOWLATENCY/X86_64/45026F50EF>) |
| 8086:318c | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 7     | process... | [BD9F5DD3DE](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/BD9F5DD3DE>) |
| 8086:31ac | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 7     | intel_l... | [BD9F5DD3DE](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/BD9F5DD3DE>) |
| 8086:31ae | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 7     | intel_l... | [BD9F5DD3DE](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/BD9F5DD3DE>) |
| 8086:31b0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 7     | intel_l... | [BD9F5DD3DE](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/BD9F5DD3DE>) |
| 8086:31b2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 7     | intel_l... | [BD9F5DD3DE](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/BD9F5DD3DE>) |
| 8086:31b4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 7     | intel_l... | [BD9F5DD3DE](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/BD9F5DD3DE>) |
| 8086:31b6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 7     | intel_l... | [BD9F5DD3DE](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/BD9F5DD3DE>) |
| 8086:a379 | 17aa:3123 | Intel            | Cannon Lake PCH Thermal Controller   | 7     | intel_p... | [9C31B501B0](<All In One/Lenovo/ThinkCentre/ThinkCentre M820z 10SDS01600/548A01155066/ROSA-12/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/9C31B501B0>) |
| 8086:1603 | 8086:2010 | Intel            | Broadwell-U Processor Thermal Sub... | 6     | proc_th... | [91204C1C19](<All In One/LG Electronics/27V750/27V750-G.BK71P1/BE4C5CBDF89C/UBUNTU-23.04/6.2.0-27-GENERIC/X86_64/91204C1C19>) |
| 8086:318c | 1043:1ea0 | Intel            | Celeron/Pentium Silver Processor ... | 6     | proc_th... | [D1891AF126](<All In One/ASUSTek Computer/Vivo/Vivo AIO 16 V161GA_V161GA/AD72AFEBE798/XERO-ROLLING/6.6.4-ARCH1-1/X86_64/D1891AF126>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c22 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 290   | i2c_i801   | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 8086:283e | 106b:00a0 | Intel            | 82801H (ICH8 Family) SMBus Contro... | 244   | i2c_i801   | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 10de:0aa2 | 10de:cb79 | Nvidia           | MCP79 SMBus                          | 211   | i2c_nfo... | [E82B0C22FB](<All In One/Apple/iMac10/iMac10,1/99E4987A298C/DEBIAN-12/6.1.0-28-AMD64/X86_64/E82B0C22FB>) |
| 8086:8c22 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 189   | i2c_i801   | [8485C9B6A3](<All In One/Apple/iMac14/iMac14,2/DE6A385E2C03/ARCH-ROLLING/6.10.14-273-TKG-EEVDF/X86_64/8485C9B6A3>) |
| 8086:a123 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 162   | i2c_i801   | [9C21FDA832](<All In One/Apple/iMac18/iMac18,2/9742FAAE1644/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9C21FDA832>) |
| 8086:3b30 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset SMBu... | 152   | i2c_i801   | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 8086:1e22 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family SMBu... | 89    | i2c_i801   | [0BB2743C5F](<All In One/Apple/iMac13/iMac13,1/9790142699C8/ZORIN-17/6.8.0-49-GENERIC/X86_64/0BB2743C5F>) |
| 8086:a323 | 8086:7270 | Intel            | Cannon Lake PCH SMBus Controller     | 82    | i2c_i801   | [0C36BC1E93](<All In One/Apple/iMac19/iMac19,2/C074723931A0/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/0C36BC1E93>) |
| 8086:43a3 |           | Intel            | Tiger Lake-H SMBus Controller        | 62    | i2c_i801   | [F969D9FB85](<All In One/ICL/RAY/RAY Si105.Mi/2E3E3E31C611/ROSA-12/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/F969D9FB85>) |
| 8086:27da | 8086:7270 | Intel            | NM10/ICH7 Family SMBus Controller    | 46    | i2c_i801   | [DE3A243820](<All In One/Apple/iMac5/iMac5,1/1F7269B01AAF/DEBIAN-11/5.10.0-33-686-PAE/I686/DE3A243820>) |
| 8086:8ca2 | 8086:7270 | Intel            | 9 Series Chipset Family SMBus Con... | 44    | i2c_i801   | [500ACCCF00](<All In One/Apple/iMac16/iMac16,2/D9F8E706C1F9/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/500ACCCF00>) |
| 8086:9c22 | 8086:7270 | Intel            | 8 Series SMBus Controller            | 26    | i2c_i801   | [9F2B2370D2](<All In One/Apple/iMac14/iMac14,4/C04E3A92385A/DEBIAN/6.11.10-AMD64/X86_64/9F2B2370D2>) |
| 1022:780b | 103c:8245 | AMD              | FCH SMBus Controller                 | 24    | i2c_piix4  | [544F0D3076](<All In One/Hewlett-Packard/20/20-c002a/4A3792E1E976/LINUXMINT-22/6.8.0-49-GENERIC/X86_64/544F0D3076>) |
| 8086:a2a3 | 1019:a5a1 | Intel            | 200 Series/Z370 Chipset Family SM... | 24    | i2c_i801   | [46658F67D3](<All In One/ICL/H310/H310SB-TM/298E8E81F4C1/ROSA-12/6.1.81-GENERIC-2ROSA2021.1-X86_64/X86_64/46658F67D3>) |
| 8086:a323 | 103c:84ee | Intel            | Cannon Lake PCH SMBus Controller     | 23    | i2c_i801   | [597321B19E](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/07E9499C7A2C/KDE-NEON-24.04/6.8.0-49-GENERIC/X86_64/597321B19E>) |
| 8086:9d23 | 8086:7270 | Intel            | Sunrise Point-LP SMBus               | 22    | i2c_i801   | [727B7184C9](<All In One/Apple/iMac18/iMac18,1/169F9C1861CD/DEBIAN-12/6.1.0-27-AMD64/X86_64/727B7184C9>) |
| 8086:1c22 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 21    | i2c_i801   | [DBA1D52306](<All In One/Lenovo/C340/C340 10102/8204E1CC8521/ZORIN-17/6.8.0-48-GENERIC/X86_64/DBA1D52306>) |
| 1022:790b | 103c:86f3 | AMD              | FCH SMBus Controller                 | 20    | i2c_piix4  | [2F05B30C3F](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-dp0xxx/E1C03E22AF48/OPENMANDRIVA-24.03/6.8.1-DESKTOP-3OMV2490/X86_64/2F05B30C3F>) |
| 8086:1e22 | 1028:0543 | Intel            | 7 Series/C216 Chipset Family SMBu... | 20    | i801_smbus | [A552EB99EE](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/B658E6C46850/ZORIN-17/6.8.0-49-GENERIC/X86_64/A552EB99EE>) |
| 8086:1e22 | 1028:0548 | Intel            | 7 Series/C216 Chipset Family SMBu... | 20    | i801_smbus | [939EFC4955](<All In One/Dell/Inspiron/Inspiron One 2330/DA27CAF94DE9/ELEMENTARY-7.1/6.8.0-48-GENERIC/X86_64/939EFC4955>) |
| 1022:790b | 103c:8430 | AMD              | FCH SMBus Controller                 | 19    | i2c_piix4  | [3EA46622E6](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/E4E878423146/OPENMANDRIVA-24.08/6.10.1-DESKTOP-1OMV2490/X86_64/3EA46622E6>) |
| 8086:1c22 | 1028:0511 | Intel            | 6 Series/C200 Series Chipset Fami... | 19    | i2c_i801   | [EC101E6744](<All In One/Dell/Inspiron/Inspiron One 2320/3D9ADF185AD6/ARCH-ROLLING/6.12.7-ARCH1-1/X86_64/EC101E6744>) |
| 8086:8c22 | 1028:05a7 | Intel            | 8 Series/C220 Series Chipset Fami... | 19    | i2c_i801   | [F866E174C2](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/5BD2C4C72DD4/FEDORA-40/6.10.8-200.FC40.X86_64/X86_64/F866E174C2>) |
| 8086:9d23 | 103c:84de | Intel            | Sunrise Point-LP SMBus               | 19    | i2c_i801   | [A7F55BE076](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/F6FC816725AE/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/A7F55BE076>) |
| 8086:a123 | 1028:06c5 | Intel            | 100 Series/C230 Series Chipset Fa... | 18    | i2c_i801   | [CCDA6EA567](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/2A418C925C5B/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/CCDA6EA567>) |
| 8086:2292 | 103c:81bb | Intel            | Atom/Celeron/Pentium Processor x5... | 17    | i801_smbus | [A802D08306](<All In One/Hewlett-Packard/22/22-b015ur/5883A5C263EF/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/A802D08306>) |
| 1022:790b | 1022:790b | AMD              | FCH SMBus Controller                 | 16    | i2c_pii... | [7C37FCE41A](<All In One/Others/FP7/FP7R2AIO/73A1EB679CBF/DEBIAN-12/6.12.8-X64V3-XANMOD1/X86_64/7C37FCE41A>) |
| 8086:8c22 | 1028:05db | Intel            | 8 Series/C220 Series Chipset Fami... | 16    | i2c_i801   | [AAD8987195](<All In One/Dell/Inspiron/Inspiron 2350/537D2F43CC7A/MX-23/6.1.0-10-AMD64/X86_64/AAD8987195>) |
| 8086:a123 | 103c:2b3e | Intel            | 100 Series/C230 Series Chipset Fa... | 16    | i2c_i801   | [72FDDCCE30](<All In One/Hewlett-Packard/27/27-p014/5E43D288C796/OPENSUSE-LEAP-15.6/6.4.0-150600.23.30-DEFAULT/X86_64/72FDDCCE30>) |
| 8086:31d4 | 1854:0308 | Intel            | Celeron/Pentium Silver Processor ... | 15    | i2c_i801   | [A595C7B829](<All In One/LG Electronics/22V280/22V280-L.BJ31P1/BE8548B5DD51/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/A595C7B829>) |
| 8086:3a30 | 1025:0266 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 15    | i2c_i801   | [9D826BCE47](<All In One/Acer/Aspire/Aspire Z5610/F8851F6F2232/LUBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9D826BCE47>) |
| 8086:9d23 | 1025:1287 | Intel            | Sunrise Point-LP SMBus               | 15    | i2c_i801   | [08963EC448](<All In One/Acer/Aspire/Aspire C24-865/78DC8340D315/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/08963EC448>) |
| 8086:9d23 | 8086:9d23 | Intel            | Sunrise Point-LP SMBus               | 15    | i2c_i801   | [555F0208DB](<All In One/ASUSTek Computer/V241/V241IC-R/86B3953D53F1/UBUNTU-22.04/6.2.0-39-GENERIC/X86_64/555F0208DB>) |
| 8086:7aa3 |           | Intel            | Alder Lake-S PCH SMBus Controller    | 14    | i2c_i801   | [0DAAF7E4B7](<All In One/DEPO Computers/DPH/DPH610T/1B53DCFC22E5/RED-OS-7.3/6.1.52-1.EL7.3.X86_64/X86_64/0DAAF7E4B7>) |
| 8086:a2a3 | 1028:079c | Intel            | 200 Series/Z370 Chipset Family SM... | 14    | i2c_i801   | [D019C812B7](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/360F073CECA0/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/D019C812B7>) |
| 1022:780b | 103c:2b3b | AMD              | FCH SMBus Controller                 | 13    | i2c_piix4  | [83AF71F2E9](<All In One/Hewlett-Packard/23/23-r159la/D01B9A9B3593/ELEMENTARY-7.1/6.8.0-47-GENERIC/X86_64/83AF71F2E9>) |
| 1022:790b | 103c:8381 | AMD              | FCH SMBus Controller                 | 13    | i2c_piix4  | [6745FD4BAC](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/EF305E495BCA/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/6745FD4BAC>) |
| 8086:3a30 | 104d:9060 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 13    | i2c_i801   | [18C8665A8A](<All In One/Sony/VPCL14/VPCL14S1E/05E16BA420D0/LINUXMINT-21.3/5.15.0-121-GENERIC/X86_64/18C8665A8A>) |
| 8086:8c22 | 1028:0626 | Intel            | 8 Series/C220 Series Chipset Fami... | 13    | i2c_i801   | [1F361B3518](<All In One/Dell/Inspiron/Inspiron 23 Model 5348/D34B13017CE6/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/1F361B3518>) |
| 8086:a0a3 | 1028:0a06 | Intel            | Tiger Lake-LP SMBus Controller       | 13    | i801_smbus | [078A22F745](<All In One/Dell/Inspiron/Inspiron 5400 AIO/D5D2451D1C1C/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/078A22F745>) |
| 10de:0752 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] SMBus          | 12    | i2c_nfo... | [63D0351E00](<All In One/Acer/Aspire/Aspire Z5101/8569CA5B9C9A/LINUXMINT-22/6.8.0-45-GENERIC/X86_64/63D0351E00>) |
| 8086:1c22 | 103c:2ac5 | Intel            | 6 Series/C200 Series Chipset Fami... | 12    | i2c_i801   | [B32F35A4B1](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/C0BF0A16B6D4/FEDORA-36/5.18.19-200.FC36.X86_64/X86_64/B32F35A4B1>) |
| 8086:31d4 | 1025:1304 | Intel            | Celeron/Pentium Silver Processor ... | 12    | i2c_i801   | [31F323613D](<All In One/Acer/Aspire/Aspire C22-820/D247EFB9442C/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/31F323613D>) |
| 8086:3b30 | 17aa:306a | Intel            | 5 Series/3400 Series Chipset SMBu... | 12    | i2c_i801   | [B562DA927A](<All In One/Lenovo/ThinkCentre/ThinkCentre M90z 3429D3U/93DF0426D130/UBUNTU-22.04/5.4.0-156-GENERIC/X86_64/B562DA927A>) |
| 8086:8c22 | 1028:0625 | Intel            | 8 Series/C220 Series Chipset Fami... | 12    | i801_smbus | [C125805F0D](<All In One/Dell/OptiPlex/OptiPlex 9030 AIO/2EE105977E12/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/C125805F0D>) |
| 8086:9ca2 | 8086:7270 | Intel            | Wildcat Point-LP SMBus Controller    | 12    | i2c_i801   | [E9F3801A74](<All In One/Apple/iMac16/iMac16,1/A877523A0FA6/LINUXMINT-22/6.8.0-45-GENERIC/X86_64/E9F3801A74>) |
| 1002:4385 |           | AMD              | SBx00 SMBus Controller               | 11    | i2c_piix4  | [E0FD42AC99](<All In One/Dell/Inspiron/Inspiron One 2305/CCF514D6F2CB/UBUNTU-22.10/5.19.0-31-GENERIC/X86_64/E0FD42AC99>) |
| 8086:1c22 | 17aa:366c | Intel            | 6 Series/C200 Series Chipset Fami... | 11    | i2c_i801   | [71F424691E](<All In One/Lenovo/C540/C540 10110/5F044C149ED0/LINUXMINT-22/6.8.0-49-GENERIC/X86_64/71F424691E>) |
| 8086:9ca2 | 8086:9ca2 | Intel            | Wildcat Point-LP SMBus Controller    | 11    | i2c_i801   | [864CBD6A4C](<All In One/BESSTAR Tech/U/U700/6D4EDF1058E5/UBUNTU-22.04/6.5.0-14-GENERIC/X86_64/864CBD6A4C>) |
| 8086:a323 | 103c:8446 | Intel            | Cannon Lake PCH SMBus Controller     | 11    | i2c_i801   | [C5B5B31A25](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/7EFF5EC8D014/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/C5B5B31A25>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c20 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 290   | snd_hda... | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 8086:284b | 106b:00a0 | Intel            | 82801H (ICH8 Family) HD Audio Con... | 244   | snd_hda... | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 1002:aa90 | 106b:aa90 | AMD              | Turks HDMI Audio [Radeon HD 6500/... | 216   | snd_hda... | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 10de:0ac0 | 10de:cb79 | Nvidia           | MCP79 High Definition Audio          | 211   | snd_hda... | [E82B0C22FB](<All In One/Apple/iMac10/iMac10,1/99E4987A298C/DEBIAN-12/6.1.0-28-AMD64/X86_64/E82B0C22FB>) |
| 8086:8c20 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset High... | 188   | snd_hda... | [8485C9B6A3](<All In One/Apple/iMac14/iMac14,2/DE6A385E2C03/ARCH-ROLLING/6.10.14-273-TKG-EEVDF/X86_64/8485C9B6A3>) |
| 8086:a170 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 162   | snd_hda... | [9C21FDA832](<All In One/Apple/iMac18/iMac18,2/9742FAAE1644/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9C21FDA832>) |
| 8086:3b56 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset High... | 152   | snd_hda... | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 1002:aa38 | 106b:aa38 | AMD              | RV710/730 HDMI Audio [Radeon HD 4... | 107   | snd_hda... | [E82B0C22FB](<All In One/Apple/iMac10/iMac10,1/99E4987A298C/DEBIAN-12/6.1.0-28-AMD64/X86_64/E82B0C22FB>) |
| 1002:aae0 | 1002:aae0 | AMD              | Baffin HDMI/DP Audio [Radeon RX 5... | 95    | snd_hda... | [9C21FDA832](<All In One/Apple/iMac18/iMac18,2/9742FAAE1644/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9C21FDA832>) |
| 1002:aaf0 | 1002:aaf0 | AMD              | Ellesmere HDMI Audio [Radeon RX 4... | 93    | snd_hda... | [EDA26270C4](<All In One/Apple/iMac18/iMac18,3/BEED7205CB3E/ARCH-ROLLING/6.12.6-ARCH1-1/X86_64/EDA26270C4>) |
| 8086:1e20 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family High... | 89    | snd_hda... | [0BB2743C5F](<All In One/Apple/iMac13/iMac13,1/9790142699C8/ZORIN-17/6.8.0-49-GENERIC/X86_64/0BB2743C5F>) |
| 8086:a348 | 8086:7270 | Intel            | Cannon Lake PCH cAVS                 | 82    | snd_hda... | [0C36BC1E93](<All In One/Apple/iMac19/iMac19,2/C074723931A0/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/0C36BC1E93>) |
| 1002:aa88 | 106b:aa88 | AMD              | Barts HDMI Audio [Radeon HD 6790/... | 67    | snd_hda... | [C4F94E8617](<All In One/Apple/iMac12/iMac12,2/40C413A46753/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/C4F94E8617>) |
| 10de:0e1b |           | Nvidia           | GK107 HDMI Audio Controller          | 61    | snd_hda... | [8485C9B6A3](<All In One/Apple/iMac14/iMac14,2/DE6A385E2C03/ARCH-ROLLING/6.10.14-273-TKG-EEVDF/X86_64/8485C9B6A3>) |
| 8086:0d0c | 106b:0122 | Intel            | Crystal Well HD Audio Controller     | 59    | snd_hda... | [8230B0CF45](<All In One/Apple/iMac14/iMac14,1/4D0F5DF66177/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/8230B0CF45>) |
| 8086:f0c8 | 10ec:0897 | Intel            | Smart Sound Technology (SST) Audi... | 57    | snd_hda... | [F969D9FB85](<All In One/ICL/RAY/RAY Si105.Mi/2E3E3E31C611/ROSA-12/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/F969D9FB85>) |
| 8086:160c | 106b:014f | Intel            | Broadwell-U Audio Controller         | 44    | snd_hda... | [500ACCCF00](<All In One/Apple/iMac16/iMac16,2/D9F8E706C1F9/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/500ACCCF00>) |
| 8086:8ca0 | 8086:7270 | Intel            | 9 Series Chipset Family HD Audio ... | 44    | snd_hda... | [500ACCCF00](<All In One/Apple/iMac16/iMac16,2/D9F8E706C1F9/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/500ACCCF00>) |
| 10de:0e0a |           | Nvidia           | GK104 HDMI Audio Controller          | 41    | snd_hda... | [114CAB1A48](<All In One/Apple/iMac14/iMac14,2/B6E03FF5EBE4/ELEMENTARY-7.1/6.8.0-49-GENERIC/X86_64/114CAB1A48>) |
| 8086:27d8 | 8384:7680 | Intel            | NM10/ICH7 Family High Definition ... | 41    | snd_hda... | [DE3A243820](<All In One/Apple/iMac5/iMac5,1/1F7269B01AAF/DEBIAN-11/5.10.0-33-686-PAE/I686/DE3A243820>) |
| 1002:aa30 | 106b:aa30 | AMD              | RV770 HDMI Audio [Radeon HD 4850/... | 39    | snd_hda... | [46FEFF6CC6](<All In One/Apple/iMac11/iMac11,1/8EA27F558F5E/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/46FEFF6CC6>) |
| 1002:aa58 | 106b:aa58 | AMD              | Juniper HDMI Audio [Radeon HD 570... | 37    | snd_hda... | [5E464458DB](<All In One/Apple/iMac11/iMac11,3/1626D13A06C7/UBUNTU-20.04/5.15.0-130-GENERIC/X86_64/5E464458DB>) |
| 10de:0e1b | 106b:0109 | Nvidia           | GK107 HDMI Audio Controller          | 34    | snd_hda... | [0BB2743C5F](<All In One/Apple/iMac13/iMac13,1/9790142699C8/ZORIN-17/6.8.0-49-GENERIC/X86_64/0BB2743C5F>) |
| 1002:aab0 | 0000:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 32    | snd_hda... | [B63F41C5EA](<All In One/Apple/iMac17/iMac17,1/F3A6F67D4FE6/ZORIN-17/6.8.0-40-GENERIC/X86_64/B63F41C5EA>) |
| 1002:aa60 | 106b:aa60 | AMD              | Redwood HDMI Audio [Radeon HD 500... | 28    | snd_hda... | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 8086:0a0c | 106b:013c | Intel            | Haswell-ULT HD Audio Controller      | 26    | snd_hda... | [9F2B2370D2](<All In One/Apple/iMac14/iMac14,4/C04E3A92385A/DEBIAN/6.11.10-AMD64/X86_64/9F2B2370D2>) |
| 8086:9c20 | 8086:7270 | Intel            | 8 Series HD Audio Controller         | 26    | snd_hda... | [9F2B2370D2](<All In One/Apple/iMac14/iMac14,4/C04E3A92385A/DEBIAN/6.11.10-AMD64/X86_64/9F2B2370D2>) |
| 1002:9840 | 103c:8245 | AMD              | Kabini HDMI/DP Audio                 | 24    | snd_hda... | [544F0D3076](<All In One/Hewlett-Packard/20/20-c002a/4A3792E1E976/LINUXMINT-22/6.8.0-49-GENERIC/X86_64/544F0D3076>) |
| 1022:780d | 103c:8245 | AMD              | FCH Azalia Controller                | 24    | snd_hda... | [544F0D3076](<All In One/Hewlett-Packard/20/20-c002a/4A3792E1E976/LINUXMINT-22/6.8.0-49-GENERIC/X86_64/544F0D3076>) |
| 8086:a2f0 | 1019:a5a1 | Intel            | 200 Series PCH HD Audio              | 24    | snd_hda... | [46658F67D3](<All In One/ICL/H310/H310SB-TM/298E8E81F4C1/ROSA-12/6.1.81-GENERIC-2ROSA2021.1-X86_64/X86_64/46658F67D3>) |
| 8086:a348 | 103c:84ee | Intel            | Cannon Lake PCH cAVS                 | 23    | snd_hda... | [597321B19E](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/07E9499C7A2C/KDE-NEON-24.04/6.8.0-49-GENERIC/X86_64/597321B19E>) |
| 1002:aac0 | 0000:aac0 | AMD              | Tobago HDMI Audio [Radeon R7 360 ... | 21    | snd_hda... | [B9F265012B](<All In One/Apple/iMac17/iMac17,1/2B3F1AF30BB3/ELEMENTARY-7.1/6.8.0-45-GENERIC/X86_64/B9F265012B>) |
| 1002:aad8 | 1002:aad8 | AMD              | Tonga HDMI Audio [Radeon R9 285/380] | 21    | snd_hda... | [65F3216D32](<All In One/Apple/iMac17/iMac17,1/2DEE4DEFC615/LINUXMINT-22/6.8.0-45-GENERIC/X86_64/65F3216D32>) |
| 8086:1c20 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 21    | snd_hda... | [DBA1D52306](<All In One/Lenovo/C340/C340 10102/8204E1CC8521/ZORIN-17/6.8.0-48-GENERIC/X86_64/DBA1D52306>) |
| 8086:9d71 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 21    | snd_hda... | [727B7184C9](<All In One/Apple/iMac18/iMac18,1/169F9C1861CD/DEBIAN-12/6.1.0-27-AMD64/X86_64/727B7184C9>) |
| 1002:15de | 103c:86f3 | AMD              | Raven/Raven2/Fenghuang HDMI/DP Au... | 20    | snd_hda... | [2F05B30C3F](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-dp0xxx/E1C03E22AF48/OPENMANDRIVA-24.03/6.8.1-DESKTOP-3OMV2490/X86_64/2F05B30C3F>) |
| 1022:15e3 | 103c:86f3 | AMD              | Family 17h/19h/1ah HD Audio Contr... | 20    | snd_hda... | [2F05B30C3F](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-dp0xxx/E1C03E22AF48/OPENMANDRIVA-24.03/6.8.1-DESKTOP-3OMV2490/X86_64/2F05B30C3F>) |
| 8086:1e20 | 1028:0543 | Intel            | 7 Series/C216 Chipset Family High... | 20    | snd_hda... | [A552EB99EE](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/B658E6C46850/ZORIN-17/6.8.0-49-GENERIC/X86_64/A552EB99EE>) |
| 8086:1e20 | 1028:0548 | Intel            | 7 Series/C216 Chipset Family High... | 20    | snd_hda... | [939EFC4955](<All In One/Dell/Inspiron/Inspiron One 2330/DA27CAF94DE9/ELEMENTARY-7.1/6.8.0-48-GENERIC/X86_64/939EFC4955>) |
| 1002:15b3 | 103c:8430 | AMD              | High Definition Audio Controller     | 19    | snd_hda... | [3EA46622E6](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/E4E878423146/OPENMANDRIVA-24.08/6.10.1-DESKTOP-1OMV2490/X86_64/3EA46622E6>) |
| 1022:157a | 103c:8430 | AMD              | Family 15h (Models 60h-6fh) Audio... | 19    | snd_hda... | [3EA46622E6](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/E4E878423146/OPENMANDRIVA-24.08/6.10.1-DESKTOP-1OMV2490/X86_64/3EA46622E6>) |
| 8086:0c0c | 1028:05a7 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 19    | snd_hda... | [F866E174C2](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/5BD2C4C72DD4/FEDORA-40/6.10.8-200.FC40.X86_64/X86_64/F866E174C2>) |
| 8086:1c20 | 1028:0511 | Intel            | 6 Series/C200 Series Chipset Fami... | 19    | snd_hda... | [EC101E6744](<All In One/Dell/Inspiron/Inspiron One 2320/3D9ADF185AD6/ARCH-ROLLING/6.12.7-ARCH1-1/X86_64/EC101E6744>) |
| 8086:8c20 | 1028:05a7 | Intel            | 8 Series/C220 Series Chipset High... | 19    | snd_hda... | [F866E174C2](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/5BD2C4C72DD4/FEDORA-40/6.10.8-200.FC40.X86_64/X86_64/F866E174C2>) |
| 8086:9d71 | 103c:84de | Intel            | Sunrise Point-LP HD Audio            | 19    | snd_hda... | [A7F55BE076](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/F6FC816725AE/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/A7F55BE076>) |
| 8086:a170 | 1028:06c5 | Intel            | 100 Series/C230 Series Chipset Fa... | 18    | snd_hda... | [CCDA6EA567](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/2A418C925C5B/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/CCDA6EA567>) |
| 8086:0c0c | 8086:2010 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 17    | snd_hda... | [0B2D7F5616](<All In One/Lenovo/B50-30/B50-30 F0AU00EEIX/B1C1DD126C40/UBUNTU-23.10/6.5.0-26-GENERIC/X86_64/0B2D7F5616>) |
| 8086:2284 | 103c:81bb | Intel            | Atom/Celeron/Pentium Processor x5... | 17    | snd_hda... | [A802D08306](<All In One/Hewlett-Packard/22/22-b015ur/5883A5C263EF/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/A802D08306>) |
| 8086:0c0c | 1028:05db | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 16    | snd_hda... | [AAD8987195](<All In One/Dell/Inspiron/Inspiron 2350/537D2F43CC7A/MX-23/6.1.0-10-AMD64/X86_64/AAD8987195>) |
| 8086:8c20 | 1028:05db | Intel            | 8 Series/C220 Series Chipset High... | 16    | snd_hda... | [AAD8987195](<All In One/Dell/Inspiron/Inspiron 2350/537D2F43CC7A/MX-23/6.1.0-10-AMD64/X86_64/AAD8987195>) |

### Storage (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1217:8130 | 17aa:3068 | O2 Micro         | Integrated MS/MSPRO/xD Controller    | 2     |            | [988ED124EE](<All In One/Lenovo/xxxx/xxxx IdeaCentre A300/598D74A4FC33/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/988ED124EE>) |
| 1217:8331 | 1bcf:a013 | O2 Micro         | O2 Flash Memory Card                 | 2     |            | [1494683BB9](<All In One/NEC Computers/PC-VN770/PC-VN770DS3ER/18CEF0AA43DB/UBUNTU-20.04/5.8.0-48-GENERIC/X86_64/1494683BB9>) |
| 1106:401a | 17aa:3603 | VIA Technologies | Card Reader Host Controller          | 1     |            | [8399296D51](<All In One/Lenovo/IdeaCentre/IdeaCentre B305 10052/A8184A7A8382/UBUNTU-20.04/5.8.0-55-GENERIC/X86_64/8399296D51>) |
| 1106:401a | 17aa:3608 | VIA Technologies | Card Reader Host Controller          | 1     |            | [69574214D7](<All In One/Lenovo/IdeaCentre/IdeaCentre A700 10050/51968677EC4C/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/69574214D7>) |
| 1217:8130 | 1033:8959 | O2 Micro         | Integrated MS/MSPRO/xD Controller    | 1     |            | [6F4A2D24C1](<All In One/NEC Computers/PC-VW770/PC-VW770CS6B/CD4FBB5FF80F/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/6F4A2D24C1>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c02 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 285   | ahci       | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 8086:2829 | 106b:00a0 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) SATA ... | 228   | ahci       | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 10de:0ab9 | 10de:cb79 | Nvidia           | MCP79 AHCI Controller                | 198   | ahci       | [E82B0C22FB](<All In One/Apple/iMac10/iMac10,1/99E4987A298C/DEBIAN-12/6.1.0-28-AMD64/X86_64/E82B0C22FB>) |
| 8086:a102 | 8086:7270 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 162   | ahci       | [9C21FDA832](<All In One/Apple/iMac18/iMac18,2/9742FAAE1644/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9C21FDA832>) |
| 8086:3b22 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset 6 po... | 148   | ahci       | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 8086:8c02 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 111   | ahci       | [8485C9B6A3](<All In One/Apple/iMac14/iMac14,2/DE6A385E2C03/ARCH-ROLLING/6.10.14-273-TKG-EEVDF/X86_64/8485C9B6A3>) |
| 8086:1e02 | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 89    | ahci       | [0BB2743C5F](<All In One/Apple/iMac13/iMac13,1/9790142699C8/ZORIN-17/6.8.0-49-GENERIC/X86_64/0BB2743C5F>) |
| 8086:a352 | 8086:7270 | Intel            | Cannon Lake PCH SATA AHCI Controller | 82    | ahci       | [0C36BC1E93](<All In One/Apple/iMac19/iMac19,2/C074723931A0/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/0C36BC1E93>) |
| 8086:43d2 |           | Intel            | 500 Series Chipset Family SATA AH... | 62    | ahci       | [F969D9FB85](<All In One/ICL/RAY/RAY Si105.Mi/2E3E3E31C611/ROSA-12/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/F969D9FB85>) |
| 8086:8c03 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 56    | ahci       | [D829862429](<All In One/Apple/iMac14/iMac14,1/96EB6536BF1E/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/D829862429>) |
| 8086:8c83 | 8086:7270 | Intel            | 9 Series Chipset Family SATA Cont... | 41    | ahci       | [500ACCCF00](<All In One/Apple/iMac16/iMac16,2/D9F8E706C1F9/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/500ACCCF00>) |
| 144d:a801 | 144d:a801 | Samsung Elect... | S4LN058A01[SSUBX] AHCI SSD Contro... | 39    | ahci       | [65F3216D32](<All In One/Apple/iMac17/iMac17,1/2DEE4DEFC615/LINUXMINT-22/6.8.0-45-GENERIC/X86_64/65F3216D32>) |
| 1b4b:9183 | 1b4b:9183 | Marvell Techn... | 88SS9183 PCIe SSD Controller         | 32    | ahci       | [114CAB1A48](<All In One/Apple/iMac14/iMac14,2/B6E03FF5EBE4/ELEMENTARY-7.1/6.8.0-49-GENERIC/X86_64/114CAB1A48>) |
| 1022:7801 | 103c:8245 | AMD              | FCH SATA Controller [AHCI mode]      | 24    | ahci       | [544F0D3076](<All In One/Hewlett-Packard/20/20-c002a/4A3792E1E976/LINUXMINT-22/6.8.0-49-GENERIC/X86_64/544F0D3076>) |
| 8086:a282 | 1019:a5a1 | Intel            | 200 Series PCH SATA controller [A... | 24    | ahci       | [46658F67D3](<All In One/ICL/H310/H310SB-TM/298E8E81F4C1/ROSA-12/6.1.81-GENERIC-2ROSA2021.1-X86_64/X86_64/46658F67D3>) |
| 8086:9c03 | 8086:7270 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 22    | ahci       | [9F2B2370D2](<All In One/Apple/iMac14/iMac14,4/C04E3A92385A/DEBIAN/6.11.10-AMD64/X86_64/9F2B2370D2>) |
| 8086:9d03 | 8086:7270 | Intel            | Sunrise Point-LP SATA Controller ... | 22    | ahci       | [727B7184C9](<All In One/Apple/iMac18/iMac18,1/169F9C1861CD/DEBIAN-12/6.1.0-27-AMD64/X86_64/727B7184C9>) |
| 8086:1e02 | 1028:0543 | Intel            | 7 Series/C210 Series Chipset Fami... | 20    | ahci       | [A552EB99EE](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/B658E6C46850/ZORIN-17/6.8.0-49-GENERIC/X86_64/A552EB99EE>) |
| 8086:a352 | 103c:84ee | Intel            | Cannon Lake PCH SATA AHCI Controller | 20    | ahci       | [E4C2ABA747](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/D815810E2D99/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/E4C2ABA747>) |
| 1022:7901 | 103c:8430 | AMD              | FCH SATA Controller [AHCI mode]      | 19    | ahci       | [3EA46622E6](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/E4E878423146/OPENMANDRIVA-24.08/6.10.1-DESKTOP-1OMV2490/X86_64/3EA46622E6>) |
| 8086:1c02 | 1028:0511 | Intel            | 6 Series/C200 Series Chipset Fami... | 19    | ahci       | [EC101E6744](<All In One/Dell/Inspiron/Inspiron One 2320/3D9ADF185AD6/ARCH-ROLLING/6.12.7-ARCH1-1/X86_64/EC101E6744>) |
| 8086:1c02 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 19    | ahci       | [DBA1D52306](<All In One/Lenovo/C340/C340 10102/8204E1CC8521/ZORIN-17/6.8.0-48-GENERIC/X86_64/DBA1D52306>) |
| 8086:1e02 | 1028:0548 | Intel            | 7 Series/C210 Series Chipset Fami... | 19    | ahci       | [939EFC4955](<All In One/Dell/Inspiron/Inspiron One 2330/DA27CAF94DE9/ELEMENTARY-7.1/6.8.0-48-GENERIC/X86_64/939EFC4955>) |
| 144d:1600 |           | Samsung Elect... | S4LN053X01 AHCI SSD Controller(Ap... | 18    | ahci       | [8230B0CF45](<All In One/Apple/iMac14/iMac14,1/4D0F5DF66177/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/8230B0CF45>) |
| 1022:7901 | 1022:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 17    | ahci       | [837B2CFE99](<All In One/Others/Others/Others/58E4FC6F62D5/MANJARO-24.0.8/6.9.12-3-MANJARO/X86_64/837B2CFE99>) |
| 1022:7901 | 103c:86f3 | AMD              | FCH SATA Controller [AHCI mode]      | 17    | ahci       | [2F05B30C3F](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-dp0xxx/E1C03E22AF48/OPENMANDRIVA-24.03/6.8.1-DESKTOP-3OMV2490/X86_64/2F05B30C3F>) |
| 8086:22a3 | 103c:81bb | Intel            | Atom/Celeron/Pentium Processor x5... | 17    | ahci       | [A802D08306](<All In One/Hewlett-Packard/22/22-b015ur/5883A5C263EF/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/A802D08306>) |
| 8086:a102 | 103c:2b3e | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 16    | ahci       | [72FDDCCE30](<All In One/Hewlett-Packard/27/27-p014/5E43D288C796/OPENSUSE-LEAP-15.6/6.4.0-150600.23.30-DEFAULT/X86_64/72FDDCCE30>) |
| 8086:31e3 | 1854:0308 | Intel            | Celeron/Pentium Silver Processor ... | 15    | ahci       | [A595C7B829](<All In One/LG Electronics/22V280/22V280-L.BJ31P1/BE8548B5DD51/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/A595C7B829>) |
| 8086:3a22 | 1025:0266 | Intel            | 82801JI (ICH10 Family) SATA AHCI ... | 15    | ahci       | [9D826BCE47](<All In One/Acer/Aspire/Aspire Z5610/F8851F6F2232/LUBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9D826BCE47>) |
| 8086:9d03 | 1025:1287 | Intel            | Sunrise Point-LP SATA Controller ... | 15    | ahci       | [08963EC448](<All In One/Acer/Aspire/Aspire C24-865/78DC8340D315/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/08963EC448>) |
| 8086:7ae2 |           | Intel            | Alder Lake-S PCH SATA Controller ... | 14    | ahci       | [0DAAF7E4B7](<All In One/DEPO Computers/DPH/DPH610T/1B53DCFC22E5/RED-OS-7.3/6.1.52-1.EL7.3.X86_64/X86_64/0DAAF7E4B7>) |
| 8086:9d03 | 103c:84de | Intel            | Sunrise Point-LP SATA Controller ... | 14    | ahci       | [A7F55BE076](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/F6FC816725AE/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/A7F55BE076>) |
| 8086:9d03 | 8086:9d03 | Intel            | Sunrise Point-LP SATA Controller ... | 14    | ahci       | [555F0208DB](<All In One/ASUSTek Computer/V241/V241IC-R/86B3953D53F1/UBUNTU-22.04/6.2.0-39-GENERIC/X86_64/555F0208DB>) |
| 1022:7801 | 103c:2b3b | AMD              | FCH SATA Controller [AHCI mode]      | 13    | ahci       | [83AF71F2E9](<All In One/Hewlett-Packard/23/23-r159la/D01B9A9B3593/ELEMENTARY-7.1/6.8.0-47-GENERIC/X86_64/83AF71F2E9>) |
| 8086:8c03 | 1028:05db | Intel            | 8 Series/C220 Series Chipset Fami... | 13    | ahci       | [AAD8987195](<All In One/Dell/Inspiron/Inspiron 2350/537D2F43CC7A/MX-23/6.1.0-10-AMD64/X86_64/AAD8987195>) |
| 8086:a0d3 | 1028:0a06 | Intel            | Tiger Lake-LP SATA Controller        | 13    | ahci       | [078A22F745](<All In One/Dell/Inspiron/Inspiron 5400 AIO/D5D2451D1C1C/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/078A22F745>) |
| 1022:7901 | 103c:8381 | AMD              | FCH SATA Controller [AHCI mode]      | 12    | ahci       | [6745FD4BAC](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/EF305E495BCA/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/6745FD4BAC>) |
| 10de:0ad4 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] AHCI Contro... | 12    | ahci       | [63D0351E00](<All In One/Acer/Aspire/Aspire Z5101/8569CA5B9C9A/LINUXMINT-22/6.8.0-45-GENERIC/X86_64/63D0351E00>) |
| 8086:1c02 | 103c:2ac5 | Intel            | 6 Series/C200 Series Chipset Fami... | 12    | ahci       | [B32F35A4B1](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/C0BF0A16B6D4/FEDORA-36/5.18.19-200.FC36.X86_64/X86_64/B32F35A4B1>) |
| 8086:27c5 | 8086:7270 | Intel            | 82801GBM/GHM (ICH7-M Family) SATA... | 12    | ahci       | [DE3A243820](<All In One/Apple/iMac5/iMac5,1/1F7269B01AAF/DEBIAN-11/5.10.0-33-686-PAE/I686/DE3A243820>) |
| 8086:31e3 | 1025:1304 | Intel            | Celeron/Pentium Silver Processor ... | 12    | ahci       | [31F323613D](<All In One/Acer/Aspire/Aspire C22-820/D247EFB9442C/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/31F323613D>) |
| 8086:9c83 | 8086:7270 | Intel            | Wildcat Point-LP SATA Controller ... | 12    | ahci       | [E9F3801A74](<All In One/Apple/iMac16/iMac16,1/A877523A0FA6/LINUXMINT-22/6.8.0-45-GENERIC/X86_64/E9F3801A74>) |
| 8086:3b22 | 17aa:306a | Intel            | 5 Series/3400 Series Chipset 6 po... | 11    | ahci       | [B562DA927A](<All In One/Lenovo/ThinkCentre/ThinkCentre M90z 3429D3U/93DF0426D130/UBUNTU-22.04/5.4.0-156-GENERIC/X86_64/B562DA927A>) |
| 8086:8c02 | 1028:0626 | Intel            | 8 Series/C220 Series Chipset Fami... | 11    | ahci       | [1F361B3518](<All In One/Dell/Inspiron/Inspiron 23 Model 5348/D34B13017CE6/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/1F361B3518>) |
| 8086:9c83 | 8086:9c83 | Intel            | Wildcat Point-LP SATA Controller ... | 11    | ahci       | [864CBD6A4C](<All In One/BESSTAR Tech/U/U700/6D4EDF1058E5/UBUNTU-22.04/6.5.0-14-GENERIC/X86_64/864CBD6A4C>) |
| 8086:a352 | 103c:8446 | Intel            | Cannon Lake PCH SATA AHCI Controller | 11    | ahci       | [C5B5B31A25](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/7EFF5EC8D014/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/C5B5B31A25>) |
| 8086:0f23 | 17aa:3695 | Intel            | Atom Processor E3800 Series SATA ... | 10    | ahci       | [462E531E2A](<All In One/Lenovo/C260/C260 10160/87949A5BD7F7/XUBUNTU-24.04/6.8.0-31-GENERIC/X86_64/462E531E2A>) |
| 8086:1c02 | 144d:b092 | Intel            | 6 Series/C200 Series Chipset Fami... | 10    | ahci       | [B2DD874812](<All In One/Samsung Electronics/P500/P500A2D/6CBEFCF9E89C/UBUNTU-22.04/6.8.0-47-GENERIC/X86_64/B2DD874812>) |
| 8086:1c02 | 17aa:366c | Intel            | 6 Series/C200 Series Chipset Fami... | 10    | ahci       | [71F424691E](<All In One/Lenovo/C540/C540 10110/5F044C149ED0/LINUXMINT-22/6.8.0-49-GENERIC/X86_64/71F424691E>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2850 | 106b:00a0 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) IDE C... | 244   | pata_acpi  | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 8086:27df | 8086:7270 | Intel            | 82801G (ICH7 Family) IDE Controller  | 46    | pata_acpi  | [DE3A243820](<All In One/Apple/iMac5/iMac5,1/1F7269B01AAF/DEBIAN-11/5.10.0-33-686-PAE/I686/DE3A243820>) |
| 8086:27c4 | 8086:7270 | Intel            | 82801GBM/GHM (ICH7-M Family) SATA... | 35    | pata_acpi  | [385C17B3D5](<All In One/Apple/iMac5/iMac5,1/36F0382E5A3A/ZORIN-17/6.8.0-48-GENERIC/X86_64/385C17B3D5>) |
| 8086:2828 | 106b:00a0 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) SATA ... | 19    | pata_acpi  | [D17F61DD3A](<All In One/Apple/iMac8/iMac8,1/24EF72050587/UBUNTU-UNITY-18.04/4.15.0-213-GENERIC/I686/D17F61DD3A>) |
| 10de:0ab5 | 10de:cb79 | Nvidia           | MCP79 SATA Controller                | 14    | ahci, p... | [B3B751A603](<All In One/Apple/iMac10/iMac10,1/883FBE5ED935/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/B3B751A603>) |
| 8086:3a20 | 104d:9060 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 13    | pata_acpi  | [18C8665A8A](<All In One/Sony/VPCL14/VPCL14S1E/05E16BA420D0/LINUXMINT-21.3/5.15.0-121-GENERIC/X86_64/18C8665A8A>) |
| 1002:439c | 1002:439c | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 10    | pata_at... | [34F80EF918](<All In One/ASUSTek Computer/ET2010/ET2010AG/82EF51037C47/UBUNTU-23.10/6.5.0-14-GENERIC/X86_64/34F80EF918>) |
| 1002:439c | 17aa:3629 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 6     | pata_at... | [85283E62FD](<All In One/Lenovo/C/C225/BCF3261CFAE4/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/85283E62FD>) |
| 8086:1c00 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | ata_piix   | [1D4057A5C0](<All In One/Apple/iMac12/iMac12,1/2EB25A28BA03/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.9.7-1-DEFAULT/X86_64/1D4057A5C0>) |
| 8086:27c0 | 17aa:3602 | Intel            | NM10/ICH7 Family SATA Controller ... | 5     | ata_pii... | [195EC7CB8C](<All In One/Lenovo/10051/10051/11244BE45969/LINUXMINT-20.3/5.4.0-126-GENERIC/X86_64/195EC7CB8C>) |
| 8086:27c0 | 17aa:3610 | Intel            | NM10/ICH7 Family SATA Controller ... | 5     | ata_pii... | [124088A101](<All In One/Lenovo/C/C200/8F5A7DCC36E9/ROSA-12.6/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/124088A101>) |
| 8086:3a20 | 104d:9044 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 5     | pata_acpi  | [5CD160EA53](<All In One/Sony/VGC-JS1/VGC-JS1E_S/2F2CC13FD639/FEDORA-38/6.4.15-200.FC38.X86_64/X86_64/5CD160EA53>) |
| 8086:3b20 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset 4 po... | 5     | pata_acpi  | [15FB5D0BAF](<All In One/Apple/iMac11/iMac11,3/6C398251D49D/UBUNTU-BUDGIE-22.04/5.19.0-50-GENERIC/X86_64/15FB5D0BAF>) |
| 10de:0759 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] IDE            | 4     | pata_am... | [63D0351E00](<All In One/Acer/Aspire/Aspire Z5101/8569CA5B9C9A/LINUXMINT-22/6.8.0-45-GENERIC/X86_64/63D0351E00>) |
| 8086:3a20 | 104d:9043 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 4     | ata_pii... | [653A82E6B9](<All In One/Sony/VGC-LV180/VGC-LV180ME/8D99388DD758/XEROLINUX-KDE-ROLLING/6.4.11-ARCH2-1/X86_64/653A82E6B9>) |
| 8086:1c3c | 103c:3561 | Intel            | 6 Series/C200 Series Chipset Fami... | 3     | ata_gen... | [AEF249E21A](<All In One/Hewlett-Packard/Z1/Z1 Workstation/8DD1D695BD68/ZORIN-16/5.15.0-88-GENERIC/X86_64/AEF249E21A>) |
| 8086:2928 | 1043:833f | Intel            | 82801IBM/IEM (ICH9M/ICH9M-E) 2 po... | 3     | ata_pii... | [42410B955D](<All In One/ASUSTek Computer/ET/ET2203T/8F38022B9DCF/LINUXMINT-22/6.8.0-41-GENERIC/X86_64/42410B955D>) |
| 1022:780c | 103c:2b26 | AMD              | FCH IDE Controller                   | 2     | pata_at... | [41DE8F48F0](<All In One/Hewlett-Packard/23/23-p101la/6D5E7FACBB8C/REBORNOS-ROLLING/6.4.3-ARCH1-2/X86_64/41DE8F48F0>) |
| 8086:1c00 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | ata_pii... | [D97ECB484D](<All In One/Lenovo/C340/C340 10102/6C3A5C533001/DEBIAN-12/6.1.0-13-AMD64/X86_64/D97ECB484D>) |
| 8086:1c01 | 1bcf:a013 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | pata_acpi  | [1494683BB9](<All In One/NEC Computers/PC-VN770/PC-VN770DS3ER/18CEF0AA43DB/UBUNTU-20.04/5.8.0-48-GENERIC/X86_64/1494683BB9>) |
| 8086:1c08 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | ata_pii... | [D97ECB484D](<All In One/Lenovo/C340/C340 10102/6C3A5C533001/DEBIAN-12/6.1.0-13-AMD64/X86_64/D97ECB484D>) |
| 8086:1e01 | 17aa:3671 | Intel            | 7 Series Chipset Family 4-port SA... | 2     | ata_pii... | [906A62D75E](<All In One/Lenovo/C240/C240 10113/52E2D6BDB71D/UBUNTU-16.04/4.15.0-55-GENERIC/I686/906A62D75E>) |
| 8086:1e09 | 17aa:3671 | Intel            | 7 Series Chipset Family 2-port SA... | 2     | ata_pii... | [906A62D75E](<All In One/Lenovo/C240/C240 10113/52E2D6BDB71D/UBUNTU-16.04/4.15.0-55-GENERIC/I686/906A62D75E>) |
| 8086:27c0 | 1462:a912 | Intel            | NM10/ICH7 Family SATA Controller ... | 2     | pata_acpi  | [B8B4472592](<All In One/MSI/MS-A/MS-A912/F92BE636D295/DEBIAN-10/4.8.0-2-AMD64/X86_64/B8B4472592>) |
| 8086:27c0 | 1462:a923 | Intel            | NM10/ICH7 Family SATA Controller ... | 2     | pata_acpi  | [0B09957195](<All In One/MSI/MS-A/MS-A923/EF48FE4550DD/LINUXMINT-22/6.8.0-47-GENERIC/X86_64/0B09957195>) |
| 8086:27c4 | 1025:025a | Intel            | 82801GBM/GHM (ICH7-M Family) SATA... | 2     | pata_acpi  | [CA89C2F311](<All In One/eMachines/EZ/EZ1600/E4B9D799E916/UBUNTU-MATE-18.04/5.4.0-65-GENERIC/I686/CA89C2F311>) |
| 8086:3b20 | 1025:045c | Intel            | 5 Series/3400 Series Chipset 4 po... | 2     | ata_piix   | [AA23301E4B](<All In One/Acer/Aspire/Aspire Z3751/A435CE6B49D1/ZORIN-17/6.8.0-49-GENERIC/X86_64/AA23301E4B>) |
| 8086:3b26 | 1025:045c | Intel            | 5 Series/3400 Series Chipset 2 po... | 2     | ata_piix   | [AA23301E4B](<All In One/Acer/Aspire/Aspire Z3751/A435CE6B49D1/ZORIN-17/6.8.0-49-GENERIC/X86_64/AA23301E4B>) |
| 8086:3b28 | 17aa:360e | Intel            | 5 Series/3400 Series Chipset 4 po... | 2     | ata_piix   | [8F25ED4108](<All In One/Lenovo/IdeaCentre/IdeaCentre A310 10056/1F51DDDCDF1C/LINUXMINT-19.3/5.4.0-77-GENERIC/X86_64/8F25ED4108>) |
| 8086:8c00 | 1028:0626 | Intel            | 8 Series/C220 Series Chipset Fami... | 2     | ata_piix   | [7C368B59B2](<All In One/Dell/Inspiron/Inspiron 23 Model 5348/3C5294CCE601/STORM-OS-20.7/5.16.13-ARCH1-1/X86_64/7C368B59B2>) |
| 8086:8c00 | 1b0a:0183 | Intel            | 8 Series/C220 Series Chipset Fami... | 2     | ata_pii... | [78D39E18EF](<All In One/Pegatron/H81/H81-P1/1DBAFEC13877/UBUNTU-18.04/4.15.0-43-GENERIC/X86_64/78D39E18EF>) |
| 8086:8c08 | 1b0a:0183 | Intel            | 8 Series/C220 Series Chipset Fami... | 2     | ata_pii... | [78D39E18EF](<All In One/Pegatron/H81/H81-P1/1DBAFEC13877/UBUNTU-18.04/4.15.0-43-GENERIC/X86_64/78D39E18EF>) |
| 1002:438c | 1033:886f | AMD              | SB600 IDE                            | 1     | pata_at... | [86771347FB](<All In One/NEC Computers/PC-GV58/PC-GV58ZYCAA/96538F2FC249/UBUNTU-19.04/5.0.0-13-GENERIC/X86_64/86771347FB>) |
| 1002:439c | 1462:aa53 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 1     | pata_at... | [7BD55BD71D](<All In One/MSI/MS-AA/MS-AA53/738F36889CD9/MANJARO/4.19.34-1-MANJARO/X86_64/7BD55BD71D>) |
| 1022:780c | 1043:8589 | AMD              | FCH IDE Controller                   | 1     | pata_at... | [C8D8836613](<All In One/ASUSTek Computer/ET2221/ET2221A/27768DCF5E7B/UBUNTU-18.04/4.15.0-54-GENERIC/X86_64/C8D8836613>) |
| 1022:780c | 1458:b001 | AMD              | FCH IDE Controller                   | 1     | pata_at... | [53E73F6DD7](<All In One/Gigabyte Technology/GB-A5/GB-A5DNK-RH/2D59EF3CA1FB/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/53E73F6DD7>) |
| 10de:0ab5 | 1043:8379 | Nvidia           | MCP79 SATA Controller                | 1     | ahci, p... | [72365E4985](<All In One/ASUSTek Computer/ET/ET2002/9AD492BE589B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/72365E4985>) |
| 197b:2363 | 1458:b000 | JMicron Techn... | JMB363 SATA/IDE Controller           | 1     | pata_jm... | [1786CF3D3D](<All In One/Gigabyte Technology/X58/X58A-UD3R/37288E45C1AD/ROSA-13.0/6.6.20-GENERIC-3ROSA2023.1-X86_64/X86_64/1786CF3D3D>) |
| 197b:2363 | 1462:ae11 | JMicron Techn... | JMB363 SATA/IDE Controller           | 1     | ahci       | [17AD880F72](<All In One/MSI/MS-AE/MS-AE1111/D998FCCDF4CE/ROSA-2016.1/4.9.124-NRJ-DESKTOP-1ROSA-X86_64/X86_64/17AD880F72>) |
| 197b:2363 | 197b:2363 | JMicron Techn... | JMB363 SATA/IDE Controller           | 1     | ahci       | [8ADEBB44D3](<All In One/Acer/Veriton/Veriton Z4860G/87F793395C72/ALT-9.1/5.4.51-STD-DEF-ALT1/X86_64/8ADEBB44D3>) |
| 8086:0f21 |           | Intel            | Atom Processor E3800 Series SATA ... | 1     | ata_piix   | [B3E778A640](<All In One/Acer/Aspire/Aspire Z1-601/502836ED0FF7/POP!_OS-20.04/5.4.0-7634-GENERIC/X86_64/B3E778A640>) |
| 8086:0f21 | 1025:085f | Intel            | Atom Processor E3800 Series SATA ... | 1     | ata_pii... | [7923ACCECA](<All In One/Acer/Aspire/Aspire ZC-606/5D8E49197BD5/ROSA-2014.1/3.14.44-NRJ-DESKTOP-2ROSA-X86_64/X86_64/7923ACCECA>) |
| 8086:1c00 | 1019:7c94 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pata_acpi  | [6A421EFDCA](<All In One/ECS/H61/H61H2-TI/92D8F0EB3874/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/6A421EFDCA>) |
| 8086:1c00 | 1025:0593 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pata_acpi  | [139C780029](<All In One/Acer/Z/Z2621G/98000EE3CE57/UBUNTU-22.04/5.15.0-30-GENERIC/X86_64/139C780029>) |
| 8086:1c00 | 1025:0618 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pata_acpi  | [B8E61A53BD](<All In One/Gateway/ZX/ZX6971/2A2802F2406C/UBUNTU-18.04/5.3.0-45-GENERIC/X86_64/B8E61A53BD>) |
| 8086:1c00 | 1025:0641 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pata_acpi  | [0B0D526E89](<All In One/Acer/Veriton/Veriton Z4630G/310398820220/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/0B0D526E89>) |
| 8086:1c00 | 103c:2aed | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ata_pii... | [E2ADA83EE9](<All In One/Hewlett-Packard/HP3520/HP3520 Aio/85A474C6BFEC/ROSA-2016.1/4.9.20-NRJ-DESKTOP-1ROSA-X86_64/X86_64/E2ADA83EE9>) |
| 8086:1c00 | 1043:1c02 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ata_piix   | [CBCA24B14A](<All In One/ASUSTek Computer/ET/ET2410/1D7A78AA84D4/MANJARO/6.10.13-3-MANJARO/X86_64/CBCA24B14A>) |
| 8086:1c00 | 1458:b005 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ata_pii... | [A965900724](<All In One/Gigabyte Technology/H61/H61M-DS2/763FAF752932/MANJARO-21.2.1/5.10.81-1-MULTIMEDIA-LTS/X86_64/A965900724>) |
| 8086:1c00 | 17aa:365a | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pata_acpi  | [DFE01FA6DD](<All In One/Lenovo/IdeaCentre/IdeaCentre B540 Product/D2EAAA70F6B6/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/DFE01FA6DD>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 89    | nvme       | [5EAE5397CF](<All In One/Hewlett-Packard/ProOne/ProOne 600 G3 21.5-in Non-Touch AiO/BD849639E3C0/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/5EAE5397CF>) |
| 144d:a806 | 144d:a801 | Samsung Elect... | NVMe SSD SM0032L                     | 71    | nvme       | [6FEA2B9985](<All In One/Apple/iMac18/iMac18,3/7BB91A8EC37E/ARCH-ROLLING/6.12.4-ARCH1-1/X86_64/6FEA2B9985>) |
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 39    | nvme       | [9043416985](<All In One/Lenovo/IdeaCentre/IdeaCentre A340-24ICB F0E600A6MT/A7BEADF711C0/LINUXMINT-22/6.8.0-48-GENERIC/X86_64/9043416985>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980 (DRAM-less)  | 37    | nvme       | [E1B1540113](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 24ARE05 F0EW004WUK/5E9CA431A68F/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/E1B1540113>) |
| 15b7:5009 | 15b7:5009 | SanDisk          | Ultra 3D / WD PC SN530, IX SN530,... | 27    | nvme       | [E3E47B4811](<All In One/ASUSTek Computer/ASUS/ASUS EXPERTCENTER AIO E1600WKA_E1600WKA/145D881596F7/TUXEDO-24.04/6.11.0-105009-TUXEDO/X86_64/E3E47B4811>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013-E13 PCIe3 NVMe Controller ... | 22    | nvme       | [39462264B1](<All In One/Graviton/M53/M53i/C37044692190/ROSA-12/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/39462264B1>) |
| 1e0f:0001 | 1e0f:0001 | KIOXIA           | NVMe SSD Controller BG4 (DRAM-less)  | 21    | nvme       | [C04639E869](<All In One/Dell/Inspiron/Inspiron 5400 AIO/F000C0A13ECA/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/C04639E869>) |
| 15b7:5003 | 15b7:5003 | SanDisk          | WD Blue SN500 / PC SN520 x2 M.2 2... | 20    | nvme       | [2F05B30C3F](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-dp0xxx/E1C03E22AF48/OPENMANDRIVA-24.03/6.8.1-DESKTOP-3OMV2490/X86_64/2F05B30C3F>) |
| 1c5c:1327 | 1c5c:0000 | SK hynix         | BC501 NVMe Solid State Drive         | 20    | nvme       | [05F47FC062](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-xa0xxx/ED5BF7729E72/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/05F47FC062>) |
| 106b:2001 | 106b:2001 | Apple            | S1X NVMe Controller                  | 19    | nvme       | [A3EF563F3F](<All In One/Apple/iMac16/iMac16,2/B2A04F9053FA/DEBIAN-12/6.1.0-26-AMD64/X86_64/A3EF563F3F>) |
| 1c5c:174a | 1c5c:174a | SK hynix         | Gold P31/BC711/PC711 NVMe Solid S... | 16    | nvme       | [8DFE1E306A](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-dd2xxx/4AC1F2ECECE0/DEBIAN-12/6.1.0-22-AMD64/X86_64/8DFE1E306A>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT (DRAM-less) NVM... | 13    | nvme       | [5AFCA2AEA2](<All In One/Others/A23/A23H66/95FE00C67093/ASTRA-1.7_X86-64/6.1.90-1-GENERIC/X86_64/5AFCA2AEA2>) |
| 1c5c:1627 | 1c5c:1627 | SK hynix         | PC601 NVMe Solid State Drive         | 11    | nvme       | [38A2509046](<All In One/Hewlett-Packard/EliteOne/EliteOne 1000 G2 34-in Curved AiO/7924B71B72CD/LINUXMINT-19.3/5.4.0-150-GENERIC/X86_64/38A2509046>) |
| 1e4b:1202 | 1e4b:1202 | MAXIO Technol... | NVMe SSD Controller MAP1202 (DRAM... | 11    | nvme       | [7A69DE9AC1](<All In One/Minix/NEO/NEO Z100-0dB/4F3A1C899285/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/7A69DE9AC1>) |
| 126f:2262 | 126f:2262 | Silicon Motion   | SM2262/SM2262EN SSD Controller       | 10    | nvme       | [019C2EA5E0](<All In One/Apple/iMac14/iMac14,2/FF69359479C7/UBUNTU-22.04/6.5.0-27-GENERIC/X86_64/019C2EA5E0>) |
| 15b7:5008 | 15b7:5008 | SanDisk          | PC SN530 NVMe SSD (DRAM-less)        | 10    | nvme       | [346A96DAF6](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 24ARE05 F0EW0043IX/DC5142F2BD5F/GARUDA-ROLLING/6.10.9-ZEN1-2-ZEN/X86_64/346A96DAF6>) |
| 8086:f1a8 | 8086:390d | Intel            | SSD 660P Series                      | 10    | nvme       | [07E4FB51E4](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-xa0xxx/3D1EAA09543A/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/07E4FB51E4>) |
| 15b7:5006 | 15b7:5006 | SanDisk          | Extreme Pro / WD Black SN750 / PC... | 9     | nvme       | [1CEDCA3D56](<All In One/Lenovo/ThinkCentre/ThinkCentre M920z 10S6002CUS/1A24639ED68C/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/1CEDCA3D56>) |
| 2646:5008 | 2646:5008 | Kingston Tech... | A1000/U-SNS8154P3 x2 NVMe SSD        | 9     | nvme       | [45437C3235](<All In One/Acer/Aspire/Aspire C24-963/8C1209775B93/RED-OS-7.3/6.1.52-1.EL7.3.X86_64/X86_64/45437C3235>) |
| 1179:0113 | 1179:0001 | Toshiba Ameri... | BG3 x2 NVMe SSD Controller (DRAM-... | 8     | nvme       | [B60CB3BA3D](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-k0xxx/6D68EA13409E/MX-23/6.1.0-17-AMD64/X86_64/B60CB3BA3D>) |
| 8086:f1aa | 8086:390f | Intel            | SSD 670p Series [Keystone Harbor]    | 8     | nvme       | [B01211CAA0](<All In One/ASUSTek Computer/ASUS/ASUS AIO A3402WBA_A3402WBA/2D9E05A16C0F/ROSA-12.5.1/6.6.27-GENERIC-3ROSA2021.1-X86_64/X86_64/B01211CAA0>) |
| 1344:5410 | 1344:0100 | Micron Techno... | 2200S NVMe SSD [Cassandra]           | 7     | nvme       | [4C618F5DDE](<All In One/Hewlett-Packard/ProOne/ProOne 440 G5 23.8-in All-in-One/AC4148A4D238/RED-OS-8.0/6.6.6-1.RED80.X86_64/X86_64/4C618F5DDE>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 7     | nvme       | [D16F5CA08A](<All In One/Acidanthera/iMac20/iMac20,1/1EB5BA2AB9E0/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/D16F5CA08A>) |
| 1c5c:1339 | 1c5c:0000 | SK hynix         | BC511 NVMe SSD                       | 7     | nvme       | [3D82B7B8E6](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-df0xxx/B4BA819F140A/ZORIN-17/6.5.0-14-GENERIC/X86_64/3D82B7B8E6>) |
| 144d:a80b | 144d:a80b | Samsung Elect... | NVMe SSD Controller PM9B1 (DRAM-l... | 6     | nvme       | [ED33639BE3](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 27ALC6 F0FY00NNUK/1B1EC250F927/ARCO-ROLLING/6.12.4-ZEN1-1-ZEN/X86_64/ED33639BE3>) |
| 1179:0116 | 1179:0001 | Toshiba Ameri... | XG5 NVMe SSD Controller              | 5     | nvme       | [9352E7ED07](<All In One/Dell/OptiPlex/OptiPlex 7460 AIO/AAD8696E4652/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9352E7ED07>) |
| 15b7:5002 | 15b7:5002 | SanDisk          | Extreme Pro / WD Black 2018/SN750... | 5     | nvme       | [EED1F038FE](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/F093DF0A7E91/ENDEAVOUROS-ROLLING/6.7.1-ARCH1-1/X86_64/EED1F038FE>) |
| 2646:500c | 2646:500c | Kingston Tech... | OM8PCP Design-In PCIe 3 NVMe SSD ... | 5     | nvme       | [AD4578A321](<All In One/ASUSTek Computer/ASUS/ASUS Vivo AIO V241DA_M241DA/3FEBF400F4CB/KALI-2023.2/6.1.0-KALI9-AMD64/X86_64/AD4578A321>) |
| 1344:5404 | 1344:1100 | Micron Techno... | 2210 NVMe SSD [Cobain]               | 4     | nvme       | [0B7B86898A](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 5 27IOB6 F0G40013UK/CE391868DD87/LINUXMINT-22/6.8.0-45-GENERIC/X86_64/0B7B86898A>) |
| 1344:5411 | 1344:1100 | Micron Techno... | 2450 NVMe SSD [HendrixV] (DRAM-less) | 4     | nvme       | [B0BDA7B10B](<All In One/Acer/Veriton/Veriton Z2694G/992B643355D9/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/B0BDA7B10B>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 4     | nvme       | [105D641565](<All In One/Acidanthera/iMac18/iMac18,1/244EC7A3F367/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/105D641565>) |
| 144d:a80a | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 4     | nvme       | [D05A394FC8](<All In One/Acidanthera/iMacPro1/iMacPro1,1/9C6521899F59/CHIMERAOS-46/6.8.0-RC2-CHOS1-CHIMERAOS-1/X86_64/D05A394FC8>) |
| 15b7:501a | 15b7:501a | SanDisk          | Ultra 3D / WD Blue SN570 NVMe SSD... | 4     | nvme       | [9C789EDD52](<All In One/Acidanthera/iMac19/iMac19,1/A2155AB4F2C5/ZORIN-16/5.15.0-78-GENERIC/X86_64/9C789EDD52>) |
| 1cc1:5766 | 1cc1:5766 | ADATA Technology | XPG GAMMIXS1 1L, XPG GAMMIX S5, L... | 4     | nvme       | [160FE857EF](<All In One/Others/Others/Others/454EBAE8C4FA/ROSA-12/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/160FE857EF>) |
| 1cc4:2263 | 1cc4:1cc4 | Union Memory ... | AM611 PCIe 3.0 x2 NVMe SSD 256GB     | 4     | nvme       | [135BA52D4B](<All In One/Lenovo/IdeaCentre/IdeaCentre A340-22IWL F0EB00AETX/A0CAC1147F41/ZORIN-17/6.8.0-45-GENERIC/X86_64/135BA52D4B>) |
| 1e0f:000c | 1e0f:0001 | KIOXIA           | NVMe SSD Controller BG5 (DRAM-less)  | 4     | nvme       | [547E78E56D](<All In One/Dell/Inspiron/Inspiron 24 5415 All-in-One/8851D6165FDA/MANJARO/6.9.10-1-MANJARO/X86_64/547E78E56D>) |
| 1e95:9100 | 126f:2263 | Solid State S... | CL1-3D256-Q11 NVMe SSD M.2           | 4     | nvme       | [681D2000F3](<All In One/Dell/Inspiron/Inspiron 5400 AIO/9A7047B5BC8F/ZORIN-16/5.13.0-30-GENERIC/X86_64/681D2000F3>) |
| 8086:0975 | 8086:8410 | Intel            | Optane NVME SSD H10 with Solid St... | 4     | nvme       | [A36307E124](<All In One/Hewlett-Packard/24/24-n014/01F3A10FEF73/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/A36307E124>) |
| 10ec:5762 | 10ec:5762 | Realtek Semic... | RTS5762 NVMe SSD Controller          | 3     | nvme       | [2E31C0E1D5](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-r0xx/27EA4D544A61/ALT-10.1/5.15.72-UN-DEF-ALT1/X86_64/2E31C0E1D5>) |
| 1179:011a | 1179:0001 | Toshiba Ameri... | XG6 NVMe SSD Controller              | 3     | nvme       | [31E93CFAD3](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-24IKU F0D2/2E37BB47AECB/FEDORA-40/6.9.11-200.FC40.X86_64/X86_64/31E93CFAD3>) |
| 1344:5411 | 1344:2100 | Micron Techno... | 2450 NVMe SSD [HendrixV] (DRAM-less) | 3     | nvme       | [3460649DA4](<All In One/Acer/Aspire/Aspire S32-1856/83E39AF333D6/RED-OS-7.3/6.1.110-1.EL7.3.X86_64/X86_64/3460649DA4>) |
| 1344:5413 | 1344:1100 | Micron Techno... | 2400 NVMe SSD (DRAM-less)            | 3     | nvme       | [CC3338DA7A](<All In One/ASUSTek Computer/ASUS/ASUS AIO M3702WFA_M3702WFA/D9B0B1FE5477/LINUXMINT-22/6.8.0-39-GENERIC/X86_64/CC3338DA7A>) |
| 1f03:1202 | 1f03:1202 | Shenzhen Shic... | MAP1202-Based NVMe SSD (DRAM-less)   | 3     | nvme       | [9AA9C859CE](<All In One/DIGMA PRO/AiO/AiO 27i DM27P7-ADXW03/192DC2B6DDE7/ROSA-12.4/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/9AA9C859CE>) |
| 2646:500d | 2646:500d | Kingston Tech... | OM3PDP3 NVMe SSD                     | 3     | nvme       | [078A22F745](<All In One/Dell/Inspiron/Inspiron 5400 AIO/D5D2451D1C1C/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/078A22F745>) |
| 2646:500e | 2646:500e | Kingston Tech... | NV1 NVMe SSD [E13T] (DRAM-less)      | 3     | nvme       | [894963056C](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 24IIL5 F0FR004QRK/F614B1A4DADD/RED-OS-7.3/5.10.29-3.EL7.X86_64/X86_64/894963056C>) |
| 2646:5017 | 2646:5017 | Kingston Tech... | NV2 NVMe SSD [SM2267XT] (DRAM-less)  | 3     | nvme       | [7C37FCE41A](<All In One/Others/FP7/FP7R2AIO/73A1EB679CBF/DEBIAN-12/6.12.8-X64V3-XANMOD1/X86_64/7C37FCE41A>) |
| 8086:0975 | 8086:8510 | Intel            | Optane NVME SSD H10 with Solid St... | 3     | nvme       | [1A9DF16F39](<All In One/Hewlett-Packard/ENVY/ENVY All-in-One 32-a0xxx/EB775B5A3ECA/UBUNTU-23.04/6.2.0-32-GENERIC/X86_64/1A9DF16F39>) |
| 025e:f1ab | 025e:3910 | Solidigm         | P41 Plus NVMe SSD (DRAM-less) [Ec... | 2     | nvme       | [24EB20636B](<All In One/Hewlett-Packard/All-in-One/All-in-One Desktop 24-cr0xxx/ECB3533431C4/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/24EB20636B>) |
| 106b:2005 | 106b:1800 | Apple            | ANS2 NVMe Controller                 | 2     | nvme       | [E4774620DA](<All In One/Apple/iMac20/iMac20,1/4FE23979BC61/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/E4774620DA>) |
| 10ec:5765 | 10ec:5765 | Realtek Semic... | RTS5765DL NVMe SSD Controller (DR... | 2     | nvme       | [A7F55BE076](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/F6FC816725AE/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/A7F55BE076>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9a0b | 8086:0000 | Intel            | Volume Management Device NVMe RAI... | 15    | vmd        | [8C98F96505](<All In One/Medion/E/E23405/C126BD27298A/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/8C98F96505>) |
| 8086:2822 | 1028:05a7 | Intel            | SATA Controller [RAID mode]          | 13    | ahci       | [6AC88ACF00](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/88830B82808C/LUBUNTU-22.04/5.15.0-117-GENERIC/X86_64/6AC88ACF00>) |
| 8086:467f | 8086:0000 | Intel            | Volume Management Device NVMe RAI... | 11    | vmd        | [6E8D78BCE8](<All In One/Acer/Aspire/Aspire S27-1755/C3B02C9B2D35/FEDORA-41/6.11.11-300.FC41.X86_64/X86_64/6E8D78BCE8>) |
| 8086:2822 | 1028:06c5 | Intel            | SATA Controller [RAID mode]          | 10    | ahci       | [CCDA6EA567](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/2A418C925C5B/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/CCDA6EA567>) |
| 8086:282a | 1043:17b1 | Intel            | 82801 Mobile SATA Controller [RAI... | 10    | ahci       | [DBDFEC80AC](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/9D86375D22FA/LINUXMINT-21.2/5.15.0-91-GENERIC/X86_64/DBDFEC80AC>) |
| 8086:2822 | 1028:079c | Intel            | SATA Controller [RAID mode]          | 8     | ahci       | [D019C812B7](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/360F073CECA0/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/D019C812B7>) |
| 8086:282a | 1025:1418 | Intel            | 82801 Mobile SATA Controller [RAI... | 8     | ahci       | [A82A90955E](<All In One/Acer/Aspire/Aspire C27-962/563F493FD77F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/A82A90955E>) |
| 8086:2822 | 1028:0625 | Intel            | SATA Controller [RAID mode]          | 7     | ahci       | [C125805F0D](<All In One/Dell/OptiPlex/OptiPlex 9030 AIO/2EE105977E12/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/C125805F0D>) |
| 8086:282a | 103c:84de | Intel            | 82801 Mobile SATA Controller [RAI... | 5     | ahci       | [B9C011F515](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/604FAEC2B63D/LINUXMINT-21.3/5.15.0-91-GENERIC/X86_64/B9C011F515>) |
| 8086:9a0b | 1043:1aa2 | Intel            | Volume Management Device NVMe RAI... | 5     | vmd        | [E39C0B0B4F](<All In One/ASUSTek Computer/ASUS/ASUS EXPERTCENTER AIO E5402WHA_A5402WHA/B39572768AFF/FEDORA-41/6.11.5-300.FC41.X86_64/X86_64/E39C0B0B4F>) |
| 8086:282a | 103c:87a4 | Intel            | 82801 Mobile SATA Controller [RAI... | 4     | ahci       | [AC3D0DEECE](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-dp0xxx/118251C361CB/UBUNTU-22.04/5.19.0-50-GENERIC/X86_64/AC3D0DEECE>) |
| 8086:282a | 152d:0924 | Intel            | 82801 Mobile SATA Controller [RAI... | 4     | ahci       | [6CE5FAF821](<All In One/Vizio/CA/CA27/FCA4878A3D40/ZORIN-17/6.8.0-47-GENERIC/X86_64/6CE5FAF821>) |
| 8086:2822 | 1028:05b0 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [441BD970BB](<All In One/Dell/XPS/XPS 2720/AD0C6D85F139/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/441BD970BB>) |
| 8086:2822 | 103c:3561 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [AEF249E21A](<All In One/Hewlett-Packard/Z1/Z1 Workstation/8DD1D695BD68/ZORIN-16/5.15.0-88-GENERIC/X86_64/AEF249E21A>) |
| 8086:2822 | 103c:84ee | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [597321B19E](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/07E9499C7A2C/KDE-NEON-24.04/6.8.0-49-GENERIC/X86_64/597321B19E>) |
| 8086:2822 | 103c:86f7 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [C6437188E6](<All In One/Hewlett-Packard/All-in-One/All-in-One 27-dp0xxx/1B38D1EFE767/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/C6437188E6>) |
| 8086:282a | 1028:05db | Intel            | 82801 Mobile SATA Controller [RAI... | 3     | ahci       | [DB76245A52](<All In One/Dell/Inspiron/Inspiron 2350/818B766C76B7/UBUNTU-22.04/6.2.0-39-GENERIC/X86_64/DB76245A52>) |
| 8086:2822 | 1028:075c | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [62F71BAABE](<All In One/Dell/XPS/XPS 7760 AIO/AC856E6CD9D7/ZORIN-17/6.8.0-49-GENERIC/X86_64/62F71BAABE>) |
| 8086:2822 | 1028:075d | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [BCBE597C6D](<All In One/Dell/Precision/Precision 5720 AIO/A0C3AA03EF0F/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/BCBE597C6D>) |
| 8086:2822 | 1028:084b | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [31BA2279F2](<All In One/Dell/OptiPlex/OptiPlex 7460 AIO/E64EA0C7340F/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/31BA2279F2>) |
| 8086:2822 | 1028:0935 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [24F4FE0749](<All In One/Dell/OptiPlex/OptiPlex 7470 AIO/FAB31B65ADDC/OPENMANDRIVA-24.08/6.10.1-DESKTOP-1OMV2490/X86_64/24F4FE0749>) |
| 8086:2822 | 103c:86c7 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [EFB6906A46](<All In One/Hewlett-Packard/ENVY/ENVY All-in-One 32-a11xxx/AC2CB5057523/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/EFB6906A46>) |
| 8086:2822 | 103c:86ed | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [E86753F364](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-d0xxx/C8F5FD68E798/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/E86753F364>) |
| 8086:282a | 1028:05d1 | Intel            | 82801 Mobile SATA Controller [RAI... | 2     | ahci       | [B16F310CF3](<All In One/Dell/XPS/XPS 18/23347FF7233D/UBUNTU-24.04/6.8.0-47-GENERIC/X86_64/B16F310CF3>) |
| 8086:282a | 1028:0853 | Intel            | 82801 Mobile SATA Controller [RAI... | 2     | ahci       | [515F746557](<All In One/Dell/Inspiron/Inspiron 3277 AIO/31B12D6ABF76/LINUXMINT-20.3/5.4.0-109-GENERIC/X86_64/515F746557>) |
| 8086:282a | 1028:08f9 | Intel            | 82801 Mobile SATA Controller [RAI... | 2     | ahci       | [81D84C83F2](<All In One/Dell/Inspiron/Inspiron 3280 AIO/223E75362C2E/DEBIAN-12/6.1.0-27-AMD64/X86_64/81D84C83F2>) |
| 8086:282a | 1028:0954 | Intel            | 82801 Mobile SATA Controller [RAI... | 2     | ahci       | [51D212B73F](<All In One/Dell/Inspiron/Inspiron 7790 AIO/5226FB806DAF/MAKULU-2020/5.8.0-44-GENERIC/X86_64/51D212B73F>) |
| 8086:282a | 8086:7270 | Intel            | 82801 Mobile SATA Controller [RAI... | 2     | ahci       | [B1F6B771C8](<All In One/Medion/E/E23403/657DEE2BDC65/UBUNTU-22.04/6.5.0-14-GENERIC/X86_64/B1F6B771C8>) |
| 8086:06d6 | 1043:1992 | Intel            | Comet Lake PCH-H RAID                | 1     | ahci       | [354C1DC0BA](<All In One/ASUSTek Computer/ASUS/ASUS ZEN AIO A5401WRP_A5401WRP/869C495C1CDC/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/354C1DC0BA>) |
| 8086:2822 | 1025:1189 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [7DF055CFAC](<All In One/Acer/Aspire/Aspire Z24-880/CBD0ED9CC044/UBUNTU-20.04/5.13.0-37-GENERIC/X86_64/7DF055CFAC>) |
| 8086:2822 | 1025:126c | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [D988A440F0](<All In One/Acer/Aspire/Aspire Z24-890/B8AC56F92465/LINUXMINT-21.1/5.15.0-76-GENERIC/X86_64/D988A440F0>) |
| 8086:2822 | 1025:1291 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [13496AAE5D](<All In One/Acer/Veriton/Veriton Z4660G/A736A6205FE1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/13496AAE5D>) |
| 8086:2822 | 1028:054b | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [FCD0EF9F0E](<All In One/Dell/XPS/XPS One 2710/E83BF6F5E12A/POP!_OS-21.04/5.13.0-7614-GENERIC/X86_64/FCD0EF9F0E>) |
| 8086:2822 | 1028:079e | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [2BF103DD36](<All In One/Dell/OptiPlex/OptiPlex 3050 AIO/6E8B4AA4839E/UBUNTU-18.04/4.18.0-15-GENERIC/X86_64/2BF103DD36>) |
| 8086:2822 | 1028:084c | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [A059134B9B](<All In One/Dell/OptiPlex/OptiPlex 5260 AIO/F49D2C138AA3/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/A059134B9B>) |
| 8086:2822 | 1028:0850 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [B70BF5282E](<All In One/Dell/Inspiron/Inspiron 7777 AIO/18A38D86A830/DEBIAN-12/6.1.0-11-AMD64/X86_64/B70BF5282E>) |
| 8086:2822 | 103c:8115 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [076151ED70](<All In One/Hewlett-Packard/Z1/Z1 G3 Workstation/4C33CAD406DE/ROSA-12/6.6.27-GENERIC-3ROSA2021.1-X86_64/X86_64/076151ED70>) |
| 8086:2822 | 103c:82a6 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [DD3E2FA2B5](<All In One/Hewlett-Packard/ProOne/ProOne 400 G3 20.0-in Non-Touch AiO/A09511605F07/MANJARO-18.1.5/5.4.6-2-MANJARO/X86_64/DD3E2FA2B5>) |
| 8086:2822 | 103c:838b | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [AC62725ABE](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-r0xx/7DE2EBF070ED/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/AC62725ABE>) |
| 8086:2822 | 103c:83eb | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [F655DC8E65](<All In One/Hewlett-Packard/ProOne/ProOne 440 G4 AiO/46615EAD4BA5/UBUNTU-22.04/6.2.0-34-GENERIC/X86_64/F655DC8E65>) |
| 8086:2822 | 103c:85a1 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [DEAB701B6F](<All In One/Hewlett-Packard/ProOne/ProOne 440 G5 23.8-in All-in-One/9A1C0A03BF4A/ARCO-ROLLING/6.7.9-ARCH1-1/X86_64/DEAB701B6F>) |
| 8086:2822 | 103c:86c6 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [1A9DF16F39](<All In One/Hewlett-Packard/ENVY/ENVY All-in-One 32-a0xxx/EB775B5A3ECA/UBUNTU-23.04/6.2.0-32-GENERIC/X86_64/1A9DF16F39>) |
| 8086:2822 | 103c:885e | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [6B6DD9140A](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-d1xxx/1DA1FD0FD208/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/6B6DD9140A>) |
| 8086:2822 | 1462:b106 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [6A736E8849](<All In One/MSI/MS-B/MS-B10611/54D0884E1335/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/6A736E8849>) |
| 8086:2822 | 17aa:36dd | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [7EBBF6AAD0](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-27IKL F0D0001BCK/4FB1AC9C7D60/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/7EBBF6AAD0>) |
| 8086:282a | 1025:1230 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [A255155F98](<All In One/Acer/Aspire/Aspire S24-880/00A232C06A58/OPENMANDRIVA-4.50/5.19.12-DESKTOP-2OMV4090/X86_64/A255155F98>) |
| 8086:282a | 1028:0953 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [D77787D6EC](<All In One/Dell/Inspiron/Inspiron 5490 AIO/DED288B166FA/POP!_OS-20.10/5.8.0-7642-GENERIC/X86_64/D77787D6EC>) |
| 8086:282a | 1462:acb3 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [FFE63DC278](<All In One/MSI/MS-ACB/MS-ACB311/370F0276A1EC/MX-21/5.10.0-26-AMD64/X86_64/FFE63DC278>) |
| 8086:282a | 17aa:36dc | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [A4AFD5181F](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-24IKU F0D200E2LD/E39A5F0652F6/ARCH-ROLLING/5.6.13.A-1-HARDENED/X86_64/A4AFD5181F>) |
| 8086:467f | 1043:8694 | Intel            | Volume Management Device NVMe RAI... | 1     | vmd        | [01866FA067](<All In One/ASUSTek Computer/PRIME/PRIME H610T2-CSM D4/E6481F5F1AA5/LINUXMINT-21.3/6.5.0-14-GENERIC/X86_64/01866FA067>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1513 | 2222:1111 | Intel            | CV82524 Thunderbolt Controller [L... | 288   | thunder... | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 8086:15d2 | 8086:0000 | Intel            | JHL6540 Thunderbolt 3 NHI (C step... | 131   | thunder... | [9C21FDA832](<All In One/Apple/iMac18/iMac18,2/9742FAAE1644/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9C21FDA832>) |
| 8086:156c |           | Intel            | DSL5520 Thunderbolt 2 NHI [Falcon... | 130   | thunder... | [500ACCCF00](<All In One/Apple/iMac16/iMac16,2/D9F8E706C1F9/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/500ACCCF00>) |
| 8086:15eb | 8086:0000 | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 81    | thunder... | [0C36BC1E93](<All In One/Apple/iMac19/iMac19,2/C074723931A0/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/0C36BC1E93>) |
| 8086:d150 |           | Intel            | Core Processor QPI Link              | 78    |            | [5E464458DB](<All In One/Apple/iMac11/iMac11,3/1626D13A06C7/UBUNTU-20.04/5.15.0-130-GENERIC/X86_64/5E464458DB>) |
| 8086:d151 |           | Intel            | Core Processor QPI Routing and Pr... | 78    |            | [5E464458DB](<All In One/Apple/iMac11/iMac11,3/1626D13A06C7/UBUNTU-20.04/5.15.0-130-GENERIC/X86_64/5E464458DB>) |
| 8086:d155 |           | Intel            | Core Processor System Management ... | 78    |            | [5E464458DB](<All In One/Apple/iMac11/iMac11,3/1626D13A06C7/UBUNTU-20.04/5.15.0-130-GENERIC/X86_64/5E464458DB>) |
| 8086:d156 |           | Intel            | Core Processor Semaphore and Scra... | 78    |            | [5E464458DB](<All In One/Apple/iMac11/iMac11,3/1626D13A06C7/UBUNTU-20.04/5.15.0-130-GENERIC/X86_64/5E464458DB>) |
| 8086:d157 |           | Intel            | Core Processor System Control and... | 78    |            | [5E464458DB](<All In One/Apple/iMac11/iMac11,3/1626D13A06C7/UBUNTU-20.04/5.15.0-130-GENERIC/X86_64/5E464458DB>) |
| 8086:d158 |           | Intel            | Core Processor Miscellaneous Regi... | 78    |            | [5E464458DB](<All In One/Apple/iMac11/iMac11,3/1626D13A06C7/UBUNTU-20.04/5.15.0-130-GENERIC/X86_64/5E464458DB>) |
| 8086:1568 | 2222:1111 | Intel            | DSL4510 Thunderbolt NHI [Redwood ... | 26    |            | [9F2B2370D2](<All In One/Apple/iMac14/iMac14,4/C04E3A92385A/DEBIAN/6.11.10-AMD64/X86_64/9F2B2370D2>) |
| 8086:1911 | 1019:a5a1 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 24    |            | [46658F67D3](<All In One/ICL/H310/H310SB-TM/298E8E81F4C1/ROSA-12/6.1.81-GENERIC-2ROSA2021.1-X86_64/X86_64/46658F67D3>) |
| 8086:1911 | 103c:84ee | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 23    |            | [597321B19E](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/07E9499C7A2C/KDE-NEON-24.04/6.8.0-49-GENERIC/X86_64/597321B19E>) |
| 8086:3190 |           | Intel            | Celeron/Pentium Silver Processor ... | 16    |            | [D1891AF126](<All In One/ASUSTek Computer/Vivo/Vivo AIO 16 V161GA_V161GA/AD72AFEBE798/XERO-ROLLING/6.6.4-ARCH1-1/X86_64/D1891AF126>) |
| 197b:2382 | 1025:0266 | JMicron Techn... | SD/MMC Host Controller               | 15    | sdhci_pci  | [9D826BCE47](<All In One/Acer/Aspire/Aspire Z5610/F8851F6F2232/LUBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9D826BCE47>) |
| 197b:2383 | 1025:0266 | JMicron Techn... | MS Host Controller                   | 15    | jmb38x_ms  | [9D826BCE47](<All In One/Acer/Aspire/Aspire Z5610/F8851F6F2232/LUBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9D826BCE47>) |
| 8086:1911 | 1025:1287 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 15    |            | [08963EC448](<All In One/Acer/Aspire/Aspire C24-865/78DC8340D315/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/08963EC448>) |
| 8086:09ab |           | Intel            | RST VMD Managed Controller           | 14    |            | [6E8D78BCE8](<All In One/Acer/Aspire/Aspire S27-1755/C3B02C9B2D35/FEDORA-41/6.11.11-300.FC41.X86_64/X86_64/6E8D78BCE8>) |
| 1180:e230 | 104d:9060 | Ricoh            | R5U2xx (R5U230 / R5U231 / R5U241)... | 13    |            | [18C8665A8A](<All In One/Sony/VPCL14/VPCL14S1E/05E16BA420D0/LINUXMINT-21.3/5.15.0-121-GENERIC/X86_64/18C8665A8A>) |
| 8086:464f |           | Intel            | 12th Gen Core Processor Gaussian ... | 13    |            | [0DAAF7E4B7](<All In One/DEPO Computers/DPH/DPH610T/1B53DCFC22E5/RED-OS-7.3/6.1.52-1.EL7.3.X86_64/X86_64/0DAAF7E4B7>) |
| 8086:1911 | 8086:1911 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 12    |            | [555F0208DB](<All In One/ASUSTek Computer/V241/V241IC-R/86B3953D53F1/UBUNTU-22.04/6.2.0-39-GENERIC/X86_64/555F0208DB>) |
| 8086:3190 | 1025:1304 | Intel            | Celeron/Pentium Silver Processor ... | 12    |            | [31F323613D](<All In One/Acer/Aspire/Aspire C22-820/D247EFB9442C/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/31F323613D>) |
| 8086:1911 | 103c:8446 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 11    |            | [C5B5B31A25](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/7EFF5EC8D014/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/C5B5B31A25>) |
| 1180:e232 | 104d:907e | Ricoh            | PCIe Memory Stick Host Controller    | 10    |            | [A8F1E64B41](<All In One/Sony/VPCL236/VPCL236FX/7D6F7AF3086A/ZORIN-17/6.8.0-49-GENERIC/X86_64/A8F1E64B41>) |
| 8086:1911 | 1043:17b1 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 10    |            | [DBDFEC80AC](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/9D86375D22FA/LINUXMINT-21.2/5.15.0-91-GENERIC/X86_64/DBDFEC80AC>) |
| 8086:1911 | 17aa:3145 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 10    |            | [4FAC5AC06A](<All In One/Lenovo/V540-24IWL/V540-24IWL AIO 10YS0031RU/BC9666104DD6/ROSA-12/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/4FAC5AC06A>) |
| 8086:1911 | 1028:0754 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 9     |            | [274DC30D2C](<All In One/Dell/Inspiron/Inspiron 3464 AIO/31AD17DDDC01/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/274DC30D2C>) |
| 1180:e232 | 104d:9083 | Ricoh            | PCIe Memory Stick Host Controller    | 8     |            | [44A108150C](<All In One/Sony/VPCJ21/VPCJ21S1E/6EEEF8B3CFB2/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/44A108150C>) |
| 8086:1911 | 1462:b090 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 8     |            | [D80B4E7372](<All In One/MSI/MS-B/MS-B09012/AFC51AE1EE8A/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/D80B4E7372>) |
| 1180:e232 | 104d:9097 | Ricoh            | PCIe Memory Stick Host Controller    | 7     |            | [2EBADEA317](<All In One/Sony/SVL2411/SVL24117FLB/B337A07B7653/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/2EBADEA317>) |
| 197b:2382 | 103c:1489 | JMicron Techn... | SD/MMC Host Controller               | 7     | sdhci_pci  | [C53E87BCE8](<All In One/Hewlett-Packard/Compaq/Compaq 6000 Pro AiO Brazil PC/FB69A2D0E244/LINUXMINT-20.3/5.4.0-159-GENERIC/X86_64/C53E87BCE8>) |
| 197b:2383 | 103c:1489 | JMicron Techn... | MS Host Controller                   | 7     | jmb38x_ms  | [C53E87BCE8](<All In One/Hewlett-Packard/Compaq/Compaq 6000 Pro AiO Brazil PC/FB69A2D0E244/LINUXMINT-20.3/5.4.0-159-GENERIC/X86_64/C53E87BCE8>) |
| 197b:2384 | 103c:1489 | JMicron Techn... | xD Host Controller                   | 7     |            | [C53E87BCE8](<All In One/Hewlett-Packard/Compaq/Compaq 6000 Pro AiO Brazil PC/FB69A2D0E244/LINUXMINT-20.3/5.4.0-159-GENERIC/X86_64/C53E87BCE8>) |
| 8086:1911 | 17aa:3123 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 7     |            | [9C31B501B0](<All In One/Lenovo/ThinkCentre/ThinkCentre M820z 10SDS01600/548A01155066/ROSA-12/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/9C31B501B0>) |
| 8086:3190 | 103c:8431 | Intel            | Celeron/Pentium Silver Processor ... | 7     |            | [A0646A07E1](<All In One/Hewlett-Packard/8431/8431/6B9F8D15AA6C/RED-OS-7.2/4.19.204-2.EL7.X86_64/X86_64/A0646A07E1>) |
| 8086:3190 | 103c:86f0 | Intel            | Celeron/Pentium Silver Processor ... | 7     |            | [45026F50EF](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-df0xxx/34F078141D24/KUBUNTU-22.04/5.15.0-73-LOWLATENCY/X86_64/45026F50EF>) |
| 1180:e230 | 104d:9074 | Ricoh            | R5U2xx (R5U230 / R5U231 / R5U241)... | 6     |            | [5BB2E62791](<All In One/Sony/VPCJ115/VPCJ115FX/D5A02AFB0F0F/FEDORA-40/6.10.11-200.FC40.X86_64/X86_64/5BB2E62791>) |
| 197b:2382 | 1025:0275 | JMicron Techn... | SD/MMC Host Controller               | 6     | sdhci_pci  | [CF417581C6](<All In One/Packard Bell/ONETWO/ONETWO M3700/3C877DEEF801/LINUXMINT-22/6.8.0-47-GENERIC/X86_64/CF417581C6>) |
| 197b:2383 | 1025:0275 | JMicron Techn... | MS Host Controller                   | 6     | jmb38x_ms  | [CF417581C6](<All In One/Packard Bell/ONETWO/ONETWO M3700/3C877DEEF801/LINUXMINT-22/6.8.0-47-GENERIC/X86_64/CF417581C6>) |
| 8086:09ab | 1043:1482 | Intel            | RST VMD Managed Controller           | 6     |            | [E02555BD07](<All In One/ASUSTek Computer/ASUS/ASUS Vivo AIO V241EA_V241EA/68A1C9B65FAA/LMDE-6/6.10.6+BPO-AMD64/X86_64/E02555BD07>) |
| 8086:1911 | 1028:084b | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 6     |            | [9352E7ED07](<All In One/Dell/OptiPlex/OptiPlex 7460 AIO/AAD8696E4652/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/9352E7ED07>) |
| 8086:1911 | 8086:7270 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 6     |            | [6B8F089361](<All In One/Others/Others/Others/C322895BC9CC/DEBIAN-12/6.1.0-25-AMD64/X86_64/6B8F089361>) |
| 8086:9a11 | 1043:1482 | Intel            | GNA Scoring Accelerator module       | 6     |            | [E02555BD07](<All In One/ASUSTek Computer/ASUS/ASUS Vivo AIO V241EA_V241EA/68A1C9B65FAA/LMDE-6/6.10.6+BPO-AMD64/X86_64/E02555BD07>) |
| 8086:9a11 | 1043:1aa2 | Intel            | GNA Scoring Accelerator module       | 6     |            | [E39C0B0B4F](<All In One/ASUSTek Computer/ASUS/ASUS EXPERTCENTER AIO E5402WHA_A5402WHA/B39572768AFF/FEDORA-41/6.11.5-300.FC41.X86_64/X86_64/E39C0B0B4F>) |
| 1180:0592 | 104d:9044 | Ricoh            | R5C592 Memory Stick Bus Host Adapter | 5     | r592       | [5CD160EA53](<All In One/Sony/VGC-JS1/VGC-JS1E_S/2F2CC13FD639/FEDORA-38/6.4.15-200.FC38.X86_64/X86_64/5CD160EA53>) |
| 197b:2382 | 17aa:3602 | JMicron Techn... | SD/MMC Host Controller               | 5     | sdhci_pci  | [195EC7CB8C](<All In One/Lenovo/10051/10051/11244BE45969/LINUXMINT-20.3/5.4.0-126-GENERIC/X86_64/195EC7CB8C>) |
| 197b:2383 | 17aa:3602 | JMicron Techn... | MS Host Controller                   | 5     | jmb38x_ms  | [195EC7CB8C](<All In One/Lenovo/10051/10051/11244BE45969/LINUXMINT-20.3/5.4.0-126-GENERIC/X86_64/195EC7CB8C>) |
| 197b:2384 | 17aa:3602 | JMicron Techn... | xD Host Controller                   | 5     |            | [195EC7CB8C](<All In One/Lenovo/10051/10051/11244BE45969/LINUXMINT-20.3/5.4.0-126-GENERIC/X86_64/195EC7CB8C>) |
| 8086:09ab | 103c:87f3 | Intel            | RST VMD Managed Controller           | 5     |            | [5738460F11](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-df1xxx/FD9660C572E0/DEBIAN-12/6.1.0-18-AMD64/X86_64/5738460F11>) |
| 8086:09ab | 1043:1aa2 | Intel            | RST VMD Managed Controller           | 5     |            | [E39C0B0B4F](<All In One/ASUSTek Computer/ASUS/ASUS EXPERTCENTER AIO E5402WHA_A5402WHA/B39572768AFF/FEDORA-41/6.11.5-300.FC41.X86_64/X86_64/E39C0B0B4F>) |

### Tv card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1131:7134 | 16be:5000 | Philips Semic... | SAA7134/SAA7135HL Video Broadcast... | 1     | saa7134    | [098FE372A3](<All In One/Acidanthera/iMac14/iMac14,4/E2C69985CC45/GENTOO-2.6/5.4.97-GENTOO_DQ87PG/X86_64/098FE372A3>) |
| 14f1:8880 | 0070:7801 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 1     | cx23885    | [FCD01E22D7](<All In One/ASUSTek Computer/PRIME/PRIME B450M-A II/E71284EECA39/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/FCD01E22D7>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c26 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 290   | ehci_pci   | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 8086:1c27 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 290   | uhci_hcd   | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 8086:1c2c | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 290   | uhci_hcd   | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 8086:1c2d | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 290   | ehci_pci   | [895F91D18F](<All In One/Apple/iMac12/iMac12,1/F30EE535881A/MANJARO/6.12.4-1-MANJARO/X86_64/895F91D18F>) |
| 8086:2830 | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 244   | uhci_hcd   | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 8086:2831 | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 244   | uhci_hcd   | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 8086:2832 | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 244   | uhci_hcd   | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 8086:2834 |           | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 244   | uhci_hcd   | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 8086:2835 | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 244   | uhci_hcd   | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 8086:2836 | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB2 EHCI Co... | 244   | ehci_pci   | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 8086:283a | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB2 EHCI Co... | 244   | ehci_pci   | [A532955DB4](<All In One/Apple/iMac7/iMac7,1/1E6B2F3BB73A/OPENMANDRIVA-24.12/6.12.6-DESKTOP-1OMV2490/X86_64/A532955DB4>) |
| 10de:0aa5 | 10de:cb79 | Nvidia           | MCP79 OHCI USB 1.1 Controller        | 211   | ohci_pci   | [E82B0C22FB](<All In One/Apple/iMac10/iMac10,1/99E4987A298C/DEBIAN-12/6.1.0-28-AMD64/X86_64/E82B0C22FB>) |
| 10de:0aa6 | 10de:cb79 | Nvidia           | MCP79 EHCI USB 2.0 Controller        | 211   | ehci_pci   | [E82B0C22FB](<All In One/Apple/iMac10/iMac10,1/99E4987A298C/DEBIAN-12/6.1.0-28-AMD64/X86_64/E82B0C22FB>) |
| 10de:0aa7 | 10de:cb79 | Nvidia           | MCP79 OHCI USB 1.1 Controller        | 211   | ohci_pci   | [E82B0C22FB](<All In One/Apple/iMac10/iMac10,1/99E4987A298C/DEBIAN-12/6.1.0-28-AMD64/X86_64/E82B0C22FB>) |
| 10de:0aa9 | 10de:cb79 | Nvidia           | MCP79 EHCI USB 2.0 Controller        | 211   | ehci_pci   | [E82B0C22FB](<All In One/Apple/iMac10/iMac10,1/99E4987A298C/DEBIAN-12/6.1.0-28-AMD64/X86_64/E82B0C22FB>) |
| 8086:8c31 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 187   | xhci_hcd   | [8485C9B6A3](<All In One/Apple/iMac14/iMac14,2/DE6A385E2C03/ARCH-ROLLING/6.10.14-273-TKG-EEVDF/X86_64/8485C9B6A3>) |
| 8086:a12f | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 162   | xhci_hcd   | [9C21FDA832](<All In One/Apple/iMac18/iMac18,2/9742FAAE1644/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9C21FDA832>) |
| 8086:3b34 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset USB2... | 152   | ehci_pci   | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 8086:3b36 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset USB ... | 152   | uhci_hcd   | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 8086:3b3b | 8086:7270 | Intel            | 5 Series/3400 Series Chipset USB ... | 152   | uhci_hcd   | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 8086:3b3c | 8086:7270 | Intel            | 5 Series/3400 Series Chipset USB2... | 152   | ehci_pci   | [ACF991024F](<All In One/Apple/iMac11/iMac11,2/E798501AF772/UBUNTU-BUDGIE-24.04/6.8.0-51-GENERIC/X86_64/ACF991024F>) |
| 8086:15d4 | 8086:0000 | Intel            | JHL6540 Thunderbolt 3 USB Control... | 131   | xhci_hcd   | [9C21FDA832](<All In One/Apple/iMac18/iMac18,2/9742FAAE1644/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/9C21FDA832>) |
| 8086:1e26 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family USB ... | 89    | ehci_pci   | [0BB2743C5F](<All In One/Apple/iMac13/iMac13,1/9790142699C8/ZORIN-17/6.8.0-49-GENERIC/X86_64/0BB2743C5F>) |
| 8086:1e2d | 8086:7270 | Intel            | 7 Series/C216 Chipset Family USB ... | 89    | ehci_pci   | [0BB2743C5F](<All In One/Apple/iMac13/iMac13,1/9790142699C8/ZORIN-17/6.8.0-49-GENERIC/X86_64/0BB2743C5F>) |
| 8086:1e31 | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 89    | xhci_hcd   | [0BB2743C5F](<All In One/Apple/iMac13/iMac13,1/9790142699C8/ZORIN-17/6.8.0-49-GENERIC/X86_64/0BB2743C5F>) |
| 8086:a36d | 8086:7270 | Intel            | Cannon Lake PCH USB 3.1 xHCI Host... | 82    | xhci_pci   | [0C36BC1E93](<All In One/Apple/iMac19/iMac19,2/C074723931A0/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/0C36BC1E93>) |
| 8086:15ec | 8086:0000 | Intel            | JHL7540 Thunderbolt 3 USB Control... | 81    | xhci_pci   | [0C36BC1E93](<All In One/Apple/iMac19/iMac19,2/C074723931A0/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/0C36BC1E93>) |
| 8086:43ed |           | Intel            | Tiger Lake-H USB 3.2 Gen 2x1 xHCI... | 62    | xhci_pci   | [F969D9FB85](<All In One/ICL/RAY/RAY Si105.Mi/2E3E3E31C611/ROSA-12/6.1.58-GENERIC-1ROSA2021.1-X86_64/X86_64/F969D9FB85>) |
| 8086:27c8 | 8086:7270 | Intel            | NM10/ICH7 Family USB UHCI Control... | 46    | uhci_hcd   | [DE3A243820](<All In One/Apple/iMac5/iMac5,1/1F7269B01AAF/DEBIAN-11/5.10.0-33-686-PAE/I686/DE3A243820>) |
| 8086:27c9 | 8086:7270 | Intel            | NM10/ICH7 Family USB UHCI Control... | 46    | uhci_hcd   | [DE3A243820](<All In One/Apple/iMac5/iMac5,1/1F7269B01AAF/DEBIAN-11/5.10.0-33-686-PAE/I686/DE3A243820>) |
| 8086:27ca | 8086:7270 | Intel            | NM10/ICH7 Family USB UHCI Control... | 46    | uhci_hcd   | [DE3A243820](<All In One/Apple/iMac5/iMac5,1/1F7269B01AAF/DEBIAN-11/5.10.0-33-686-PAE/I686/DE3A243820>) |
| 8086:27cb | 8086:7270 | Intel            | NM10/ICH7 Family USB UHCI Control... | 46    | uhci_hcd   | [DE3A243820](<All In One/Apple/iMac5/iMac5,1/1F7269B01AAF/DEBIAN-11/5.10.0-33-686-PAE/I686/DE3A243820>) |
| 8086:27cc | 8086:7270 | Intel            | NM10/ICH7 Family USB2 EHCI Contro... | 46    | ehci_pci   | [DE3A243820](<All In One/Apple/iMac5/iMac5,1/1F7269B01AAF/DEBIAN-11/5.10.0-33-686-PAE/I686/DE3A243820>) |
| 8086:8cb1 | 8086:7270 | Intel            | 9 Series Chipset Family USB xHCI ... | 44    | xhci_hcd   | [500ACCCF00](<All In One/Apple/iMac16/iMac16,2/D9F8E706C1F9/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/500ACCCF00>) |
| 8086:9a13 |           | Intel            | Tiger Lake-LP Thunderbolt 4 USB C... | 34    | xhci_pci   | [8C98F96505](<All In One/Medion/E/E23405/C126BD27298A/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/8C98F96505>) |
| 8086:9c31 | 8086:7270 | Intel            | 8 Series USB xHCI HC                 | 26    | xhci_pci   | [9F2B2370D2](<All In One/Apple/iMac14/iMac14,4/C04E3A92385A/DEBIAN/6.11.10-AMD64/X86_64/9F2B2370D2>) |
| 1022:7808 | 103c:8245 | AMD              | FCH USB EHCI Controller              | 24    | ehci_pci   | [544F0D3076](<All In One/Hewlett-Packard/20/20-c002a/4A3792E1E976/LINUXMINT-22/6.8.0-49-GENERIC/X86_64/544F0D3076>) |
| 1022:7814 | 103c:8245 | AMD              | FCH USB XHCI Controller              | 24    | xhci_hcd   | [544F0D3076](<All In One/Hewlett-Packard/20/20-c002a/4A3792E1E976/LINUXMINT-22/6.8.0-49-GENERIC/X86_64/544F0D3076>) |
| 8086:a2af | 1019:a5a1 | Intel            | 200 Series/Z370 Chipset Family US... | 24    | xhci_pci   | [46658F67D3](<All In One/ICL/H310/H310SB-TM/298E8E81F4C1/ROSA-12/6.1.81-GENERIC-2ROSA2021.1-X86_64/X86_64/46658F67D3>) |
| 8086:a36d | 103c:84ee | Intel            | Cannon Lake PCH USB 3.1 xHCI Host... | 23    | xhci_hcd   | [597321B19E](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/07E9499C7A2C/KDE-NEON-24.04/6.8.0-49-GENERIC/X86_64/597321B19E>) |
| 8086:9d2f | 8086:7270 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 22    | xhci_pci   | [727B7184C9](<All In One/Apple/iMac18/iMac18,1/169F9C1861CD/DEBIAN-12/6.1.0-27-AMD64/X86_64/727B7184C9>) |
| 1b6f:7023 | 1025:8030 | Etron Technology | EJ168 USB 3.0 Host Controller        | 21    | xhci_pci   | [E81865186B](<All In One/Acer/Aspire/Aspire ZS600/0F176167F7F4/FEDORA-40/6.10.6-200.FC40.X86_64/X86_64/E81865186B>) |
| 8086:1c26 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 21    | ehci_pci   | [DBA1D52306](<All In One/Lenovo/C340/C340 10102/8204E1CC8521/ZORIN-17/6.8.0-48-GENERIC/X86_64/DBA1D52306>) |
| 8086:1c2d | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 21    | ehci_pci   | [DBA1D52306](<All In One/Lenovo/C340/C340 10102/8204E1CC8521/ZORIN-17/6.8.0-48-GENERIC/X86_64/DBA1D52306>) |
| 8086:1e26 | 1028:0543 | Intel            | 7 Series/C216 Chipset Family USB ... | 20    | ehci_pci   | [A552EB99EE](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/B658E6C46850/ZORIN-17/6.8.0-49-GENERIC/X86_64/A552EB99EE>) |
| 8086:1e26 | 1028:0548 | Intel            | 7 Series/C216 Chipset Family USB ... | 20    | ehci_pci   | [939EFC4955](<All In One/Dell/Inspiron/Inspiron One 2330/DA27CAF94DE9/ELEMENTARY-7.1/6.8.0-48-GENERIC/X86_64/939EFC4955>) |
| 8086:1e2d | 1028:0543 | Intel            | 7 Series/C216 Chipset Family USB ... | 20    | ehci_pci   | [A552EB99EE](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/B658E6C46850/ZORIN-17/6.8.0-49-GENERIC/X86_64/A552EB99EE>) |
| 8086:1e2d | 1028:0548 | Intel            | 7 Series/C216 Chipset Family USB ... | 20    | ehci_pci   | [939EFC4955](<All In One/Dell/Inspiron/Inspiron One 2330/DA27CAF94DE9/ELEMENTARY-7.1/6.8.0-48-GENERIC/X86_64/939EFC4955>) |
| 8086:1e31 | 1028:0543 | Intel            | 7 Series/C210 Series Chipset Fami... | 20    | xhci_hcd   | [A552EB99EE](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/B658E6C46850/ZORIN-17/6.8.0-49-GENERIC/X86_64/A552EB99EE>) |
| 8086:1e31 | 1028:0548 | Intel            | 7 Series/C210 Series Chipset Fami... | 20    | xhci_hcd   | [939EFC4955](<All In One/Dell/Inspiron/Inspiron One 2330/DA27CAF94DE9/ELEMENTARY-7.1/6.8.0-48-GENERIC/X86_64/939EFC4955>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:8d7c | 8086:7270 | Intel            | C610/X99 series chipset SPSR         | 1     |            | [B2AD449201](<All In One/Acidanthera/iMacPro1/iMacPro1,1/02ABD56D98BC/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/B2AD449201>) |

