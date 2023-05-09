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
   * [ Performance counters ](#performance-counters-pci)
   * [ Pic (io(x)-apic) ](#pic-iox-apic-pci)
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
| 1814:3298 | 103c:18ec | Ralink           | RT3290 Bluetooth                     | 1     |            | [B6CF0A1651](<All In One/Hewlett-Packard/205/205 G1 AiO Business PC/5EDA8801C3DD/ELEMENTARY-6/5.11.0-40-GENERIC/X86_64/B6CF0A1651>) |

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2448 |           | Intel            | 82801 Mobile PCI Bridge              | 185   |            | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 8086:1c10 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 170   | pcieport   | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 8086:1c14 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 170   | pcieport   | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 8086:1c44 | 8086:7270 | Intel            | Z68 Express Chipset LPC Controller   | 170   | lpc_ich    | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 8086:1513 |           | Intel            | CV82524 Thunderbolt Controller [L... | 169   | pcieport   | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 8086:1c12 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 169   | pcieport   | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 8086:1c18 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 169   | pcieport   | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 8086:2815 | 106b:00a0 | Intel            | 82801HM (ICH8M) LPC Interface Con... | 155   | lpc_ich    | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 8086:283f |           | Intel            | 82801H (ICH8 Family) PCI Express ... | 155   | pcieport   | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 8086:2845 |           | Intel            | 82801H (ICH8 Family) PCI Express ... | 155   | pcieport   | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 8086:2847 |           | Intel            | 82801H (ICH8 Family) PCI Express ... | 155   | pcieport   | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 8086:2849 |           | Intel            | 82801H (ICH8 Family) PCI Express ... | 155   | pcieport   | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 8086:2a00 | 106b:00a0 | Intel            | Mobile PM965/GM965/GL960 Memory C... | 155   | intel_agp  | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 8086:2a01 | 8086:0000 | Intel            | Mobile PM965/GM965/GL960 PCI Expr... | 155   | pcieport   | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 104c:823e |           | Texas Instrum... | XIO2213A/B/XIO2221 PCI Express to... | 154   | shpchp     | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 8086:244e | 8086:7270 | Intel            | 82801 PCI Bridge                     | 135   |            | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 10de:0aab | 10de:cb79 | Nvidia           | MCP79 PCI Bridge                     | 128   |            | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 10de:0ac4 | 10de:0000 | Nvidia           | MCP79 PCI Express Bridge             | 128   | pcieport   | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 10de:0ac6 | 10de:0000 | Nvidia           | MCP79 PCI Express Bridge             | 128   | pcieport   | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 10de:0ac7 | 10de:0000 | Nvidia           | MCP79 PCI Express Bridge             | 128   | pcieport   | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 8086:1547 | 2222:1111 | Intel            | DSL3510 Thunderbolt Controller [C... | 122   | pcieport   | [C8C9C1E591](<All In One/Apple/iMac13/iMac13,1/ED988FB747CF/DEBIAN-11/5.10.0-21-AMD64/X86_64/C8C9C1E591>) |
| 8086:1578 | 8086:0000 | Intel            | DSL6540 Thunderbolt 3 Bridge [Alp... | 119   | pcieport   | [EE288626F4](<All In One/Apple/iMac18/iMac18,3/85F2F89AFF57/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/EE288626F4>) |
| 8086:0100 | 8086:2010 | Intel            | 2nd Generation Core Processor Fam... | 95    | snb_uncore | [E4718D8B12](<All In One/Apple/iMac12/iMac12,1/6CEFAE063257/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/E4718D8B12>) |
| 8086:0101 | 8086:2010 | Intel            | Xeon E3-1200/2nd Generation Core ... | 95    | pcieport   | [E4718D8B12](<All In One/Apple/iMac12/iMac12,1/6CEFAE063257/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/E4718D8B12>) |
| 8086:8c10 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 89    | pcieport   | [00D8186404](<All In One/Apple/iMac14/iMac14,2/6ABD34C5E7DF/UBUNTU-22.04/5.15.0-33-GENERIC/X86_64/00D8186404>) |
| 8086:8c16 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 89    | pcieport   | [00D8186404](<All In One/Apple/iMac14/iMac14,2/6ABD34C5E7DF/UBUNTU-22.04/5.15.0-33-GENERIC/X86_64/00D8186404>) |
| 8086:8c18 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 89    | pcieport   | [00D8186404](<All In One/Apple/iMac14/iMac14,2/6ABD34C5E7DF/UBUNTU-22.04/5.15.0-33-GENERIC/X86_64/00D8186404>) |
| 8086:a110 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 89    | pcieport   | [EE288626F4](<All In One/Apple/iMac18/iMac18,3/85F2F89AFF57/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/EE288626F4>) |
| 8086:a145 | 8086:7270 | Intel            | Z170 Chipset LPC/eSPI Controller     | 89    |            | [EE288626F4](<All In One/Apple/iMac18/iMac18,3/85F2F89AFF57/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/EE288626F4>) |
| 8086:8c14 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 88    | pcieport   | [00D8186404](<All In One/Apple/iMac14/iMac14,2/6ABD34C5E7DF/UBUNTU-22.04/5.15.0-33-GENERIC/X86_64/00D8186404>) |
| 8086:a111 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 88    | pcieport   | [CA4C9D7E6C](<All In One/Apple/iMac18/iMac18,3/C69792706D66/UBUNTU-22.10/5.19.0-40-GENERIC/X86_64/CA4C9D7E6C>) |
| 8086:3b02 | 8086:7270 | Intel            | P55 Chipset LPC Interface Controller | 86    | lpc_ich    | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 8086:3b42 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset PCI ... | 86    | pcieport   | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 8086:3b44 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset PCI ... | 86    | pcieport   | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 8086:3b46 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset PCI ... | 86    | pcieport   | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 10de:0aa0 | 10de:0000 | Nvidia           | MCP79 PCI Express Bridge             | 78    | shpchp     | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 8086:0101 | 106b:0000 | Intel            | Xeon E3-1200/2nd Generation Core ... | 75    | pcieport   | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 8086:0100 | 106b:0000 | Intel            | 2nd Generation Core Processor Fam... | 74    | snb_uncore | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 8086:15d3 | 8086:0000 | Intel            | JHL6540 Thunderbolt 3 Bridge (C s... | 70    | pcieport   | [EE288626F4](<All In One/Apple/iMac18/iMac18,3/85F2F89AFF57/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/EE288626F4>) |
| 10de:0aac | 10de:cb79 | Nvidia           | MCP79 LPC Bridge                     | 67    |            | [3165AB3194](<All In One/Apple/iMac10/iMac10,1/97AFDCCBEBDE/KUBUNTU-23.04/6.2.0-1003-LOWLATENCY/X86_64/3165AB3194>) |
| 8086:156d |           | Intel            | DSL5520 Thunderbolt 2 Bridge [Fal... | 66    | pcieport   | [570077AA64](<All In One/Apple/iMac16/iMac16,2/2D4E89D37302/ZORIN-16/5.15.0-69-GENERIC/X86_64/570077AA64>) |
| 8086:2d01 | 8086:8086 | Intel            | Core Processor QuickPath Architec... | 64    |            | [F0EA43F3FD](<All In One/Apple/iMac11/iMac11,2/40AA4B37D450/ZORIN-15/5.4.0-146-GENERIC/X86_64/F0EA43F3FD>) |
| 8086:2d10 | 8086:8086 | Intel            | Core Processor QPI Link 0            | 64    |            | [F0EA43F3FD](<All In One/Apple/iMac11/iMac11,2/40AA4B37D450/ZORIN-15/5.4.0-146-GENERIC/X86_64/F0EA43F3FD>) |
| 8086:2d11 | 8086:8086 | Intel            | 1st Generation Core i3/5/7 Proces... | 64    |            | [F0EA43F3FD](<All In One/Apple/iMac11/iMac11,2/40AA4B37D450/ZORIN-15/5.4.0-146-GENERIC/X86_64/F0EA43F3FD>) |
| 8086:2d12 | 8086:8086 | Intel            | 1st Generation Core i3/5/7 Proces... | 64    |            | [F0EA43F3FD](<All In One/Apple/iMac11/iMac11,2/40AA4B37D450/ZORIN-15/5.4.0-146-GENERIC/X86_64/F0EA43F3FD>) |
| 8086:2d13 | 8086:8086 | Intel            | 1st Generation Core i3/5/7 Proces... | 64    |            | [F0EA43F3FD](<All In One/Apple/iMac11/iMac11,2/40AA4B37D450/ZORIN-15/5.4.0-146-GENERIC/X86_64/F0EA43F3FD>) |
| 8086:8c44 | 8086:7270 | Intel            | Z87 Express LPC Controller           | 63    | lpc_ich    | [00D8186404](<All In One/Apple/iMac14/iMac14,2/6ABD34C5E7DF/UBUNTU-22.04/5.15.0-33-GENERIC/X86_64/00D8186404>) |
| 1022:156b |           | AMD              | Family 16h (Models 30h-3fh) Host ... | 61    |            | [CB25C51987](<All In One/Hewlett-Packard/23/23-r155la/F1B498CB86AC/ZORIN-16/5.15.0-60-GENERIC/X86_64/CB25C51987>) |
| 1022:1580 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 61    |            | [CB25C51987](<All In One/Hewlett-Packard/23/23-r155la/F1B498CB86AC/ZORIN-16/5.15.0-60-GENERIC/X86_64/CB25C51987>) |
| 1022:1581 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 61    |            | [CB25C51987](<All In One/Hewlett-Packard/23/23-r155la/F1B498CB86AC/ZORIN-16/5.15.0-60-GENERIC/X86_64/CB25C51987>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:5209 | 1025:8020 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 16    | rtsx_pci   | [2E34D8A2CC](<All In One/Acer/Aspire/Aspire Z5770/1DB05CC1D29C/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/2E34D8A2CC>) |
| 10ec:5229 | 17aa:365e | Realtek Semic... | RTS5229 PCI Express Card Reader      | 16    | rtsx_pci   | [D75E472005](<All In One/Lenovo/C440/C440 10104/983B023892A1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/D75E472005>) |
| 10ec:5209 | 1028:05a7 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 15    | rtsx_pci   | [757AE6AA73](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/099C9C0A02A0/DEBIAN-11/5.10.0-20-AMD64/X86_64/757AE6AA73>) |
| 10ec:5209 | 1028:0543 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 14    | rtsx_pci   | [00CB2D66A8](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/42A1DEC89484/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/00CB2D66A8>) |
| 10ec:5209 | 1028:0548 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 14    | rtsx_pci   | [22CBD67F5D](<All In One/Dell/Inspiron/Inspiron One 2330/C959D85DE508/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/22CBD67F5D>) |
| 10ec:5209 | 1028:05db | Realtek Semic... | RTS5209 PCI Express Card Reader      | 13    | rtsx_pci   | [323E28FDED](<All In One/Dell/Inspiron/Inspiron 2350/07DCD03E083E/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/323E28FDED>) |
| 10ec:5209 | 103c:2ac5 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 12    | rtsx_pci   | [B32F35A4B1](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/C0BF0A16B6D4/FEDORA-36/5.18.19-200.FC36.X86_64/X86_64/B32F35A4B1>) |
| 10ec:522a | 1854:0308 | Realtek Semic... | RTS522A PCI Express Card Reader      | 10    | rtsx_pci   | [EC912EFB6F](<All In One/LG Electronics/22V280/22V280-L.BJ31P1/925F8D37ECFF/FEDORA-37/6.0.12-300.FC37.X86_64/X86_64/EC912EFB6F>) |
| 10ec:525a | 1028:06c5 | Realtek Semic... | RTS525A PCI Express Card Reader      | 10    | rtsx_pci   | [5B29ED7213](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/BE925566CC9F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5B29ED7213>) |
| 10ec:5229 | 17aa:366c | Realtek Semic... | RTS5229 PCI Express Card Reader      | 9     | rtsx_pci   | [55C11B6B87](<All In One/Lenovo/C540/C540 10110/D5261210E56A/OPENMANDRIVA-4.50/5.12.4-DESKTOP-1OMV4050/X86_64/55C11B6B87>) |
| 10ec:5229 | 103c:2b3e | Realtek Semic... | RTS5229 PCI Express Card Reader      | 8     | rtsx_pci   | [70F8CE05B6](<All In One/Hewlett-Packard/24/24-n000ny/C2F705DD30EA/UBUNTU-20.04/5.15.0-69-GENERIC/X86_64/70F8CE05B6>) |
| 10ec:5229 | 10ec:5229 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 8     | rtsx_pci   | [EA620E0681](<All In One/Acer/Aspire/Aspire Z3-600/BD66BD02AA7B/LINUX-LITE-6.4/5.15.0-71-GENERIC/X86_64/EA620E0681>) |
| 10ec:5229 | 103c:81b7 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 7     | rtsx_pci   | [7B1F1044AE](<All In One/Hewlett-Packard/27/27-a154ng/BDD291411CF6/REBORNOS/5.19.2-ARCH1-1/X86_64/7B1F1044AE>) |
| 10ec:5229 | 103c:82dc | Realtek Semic... | RTS5229 PCI Express Card Reader      | 7     | rtsx_pci   | [4C1C2F908B](<All In One/Hewlett-Packard/27/27-a271ny/689111B5E631/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/4C1C2F908B>) |
| 10ec:5229 | 17aa:367b | Realtek Semic... | RTS5229 PCI Express Card Reader      | 7     | rtsx_pci   | [4CC2E8CADD](<All In One/Lenovo/IdeaCentre/IdeaCentre B550 10135/0A3ACDFA18A3/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/4CC2E8CADD>) |
| 10ec:5229 | 17aa:3686 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 7     | rtsx_pci   | [A079D28341](<All In One/Lenovo/C560/C560 10150/6C9E3A129538/LINUXMINT-21.1/5.15.0-58-GENERIC/X86_64/A079D28341>) |
| 10ec:522a | 1028:0754 | Realtek Semic... | RTS522A PCI Express Card Reader      | 7     | rtsx_pci   | [348BC23246](<All In One/Dell/Inspiron/Inspiron 3464 AIO/00109263052E/ENDEAVOUROS-ROLLING/5.15.71-1-LTS/X86_64/348BC23246>) |
| 10ec:522a | 10ec:522a | Realtek Semic... | RTS522A PCI Express Card Reader      | 7     | rtsx_pci   | [04D33628A1](<All In One/LG Electronics/22V270/22V270-L.BJ31P1/8E73444ADF98/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/04D33628A1>) |
| 10ec:525a | 1028:079c | Realtek Semic... | RTS525A PCI Express Card Reader      | 7     | rtsx_pci   | [1940C6417C](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/A9167F8393F4/DEBIAN-11/5.10.0-21-AMD64/X86_64/1940C6417C>) |
| 10ec:5209 | 1028:05b0 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 6     | rtsx_pci   | [EFA9D9069D](<All In One/Dell/XPS/XPS 2720/CB861C53F8DC/KUBUNTU-22.10/6.2.1-060201-GENERIC/X86_64/EFA9D9069D>) |
| 10ec:5229 | 103c:2b0d | Realtek Semic... | RTS5229 PCI Express Card Reader      | 6     | rtsx_pci   | [43B3FD0FD4](<All In One/Hewlett-Packard/21/21-h013w/231F14BA7F4C/UBUNTU-MATE-20.04/5.13.0-48-GENERIC/X86_64/43B3FD0FD4>) |
| 10ec:5229 | 17aa:3685 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 6     | rtsx_pci   | [F27DF86FDA](<All In One/Lenovo/C360/C360 10147/9E90E0E6AD04/FEDORA-36/5.18.10-200.FC36.X86_64/X86_64/F27DF86FDA>) |
| 10ec:5229 | 17aa:36ab | Realtek Semic... | RTS5229 PCI Express Card Reader      | 6     | rtsx_pci   | [4891D8306B](<All In One/Lenovo/C40-05/C40-05 F0B5004EUK/84C5083CE2E4/LINUXMINT-20.2/5.4.0-139-GENERIC/X86_64/4891D8306B>) |
| 10ec:5209 | 103c:2aed | Realtek Semic... | RTS5209 PCI Express Card Reader      | 5     | rtsx_pci   | [9A324C230D](<All In One/Hewlett-Packard/HP3520/HP3520 Aio/C82F204C8001/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/9A324C230D>) |
| 10ec:5209 | 17aa:3629 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 5     | rtsx_pci   | [861AF1FD97](<All In One/Lenovo/C/C325/A63CECA79035/DEBIAN-11/5.10.0-18-AMD64/X86_64/861AF1FD97>) |
| 10ec:5229 | 1025:085f | Realtek Semic... | RTS5229 PCI Express Card Reader      | 5     | rtsx_pci   | [FF4762D139](<All In One/Acer/Aspire/Aspire ZC-606/A2FBE9AD3965/KDE-NEON-22.04/5.15.0-57-GENERIC/X86_64/FF4762D139>) |
| 10ec:5229 | 17aa:3633 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 5     | rtsx_pci   | [489592E334](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 300-23ACL F0BC0018CF/1DF10EDA030E/UBUNTU-22.04/5.15.0-52-GENERIC/X86_64/489592E334>) |
| 10ec:522a | 103c:83eb | Realtek Semic... | RTS522A PCI Express Card Reader      | 5     | rtsx_pci   | [1011557C31](<All In One/Hewlett-Packard/ProOne/ProOne 440 G4 23.8-in NT AiO/EC8129DD680A/RED-OS-7.3/5.15.35-5.EL7.3.X86_64/X86_64/1011557C31>) |
| 10ec:522a | 103c:85a2 | Realtek Semic... | RTS522A PCI Express Card Reader      | 5     | rtsx_pci   | [C9F6D95FB2](<All In One/Hewlett-Packard/ProOne/ProOne 440 G5 23.8-in All-in-One/3714C25A2744/UBUNTU-MATE-22.10/5.19.0-31-GENERIC/X86_64/C9F6D95FB2>) |
| 10ec:5287 | 1297:2053 | Realtek Semic... | RTL8411B PCI Express Card Reader     | 5     | rtsx_pci   | [95E8BED16F](<All In One/Positivo/DH8/DH8BW01/5F022083C428/KDE-NEON-20.04/5.15.0-50-GENERIC/X86_64/95E8BED16F>) |
| 10ec:5289 | 17aa:3671 | Realtek Semic... | RTL8411 PCI Express Card Reader      | 5     | rtsx_pci   | [2A92010AD3](<All In One/Lenovo/C240/C240 10113/2C9D687CEE76/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/2A92010AD3>) |
| 10ec:5229 | 103c:2b2f | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx_pci   | [13AEF3E1EF](<All In One/Hewlett-Packard/205/205 G2 AiO Business PC/5629DB684FCA/KALI-2022.1/5.18.0-KALI5-AMD64/X86_64/13AEF3E1EF>) |
| 10ec:5229 | 103c:2b3b | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx_pci   | [CB25C51987](<All In One/Hewlett-Packard/23/23-r155la/F1B498CB86AC/ZORIN-16/5.15.0-60-GENERIC/X86_64/CB25C51987>) |
| 10ec:5229 | 17aa:369c | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx_pci   | [9A6102422F](<All In One/Lenovo/B50-30/B50-30 F0AU00EEIX/B1C1DD126C40/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/9A6102422F>) |
| 10ec:5229 | 17aa:36ed | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx_pci   | [6481787B51](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 330-20IGM F0D7001PLD/4248D7BD5C39/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/6481787B51>) |
| 10ec:524a | 103c:829b | Realtek Semic... | RTS524A PCI Express Card Reader      | 4     | rtsx_pci   | [23122CBA32](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G3 23.8-in Non-Touch AiO/E6CDD7190196/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.3-1-DEFAULT/X86_64/23122CBA32>) |
| 10ec:525a | 1028:084b | Realtek Semic... | RTS525A PCI Express Card Reader      | 4     | rtsx_pci   | [5F63C2FD15](<All In One/Dell/OptiPlex/OptiPlex 7460 AIO/81D9C9B1F509/GENTOO-2.9/6.1.1/X86_64/5F63C2FD15>) |
| 10ec:5209 | 1854:0167 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 3     | rtsx_pci   | [15D027D68F](<All In One/LG Electronics/V320/V320-M.BG31P1/B2985A63DB99/UBUNTU-18.04/4.15.0-189-GENERIC/X86_64/15D027D68F>) |
| 10ec:5229 | 103c:2b0a | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [35F88E8F33](<All In One/Hewlett-Packard/20/20-2010es/BA8E3BA7C39D/ROSA-12.3/5.15.79-GENERIC-1ROSA2021.1-X86_64/X86_64/35F88E8F33>) |
| 10ec:5229 | 103c:2b21 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [2EEC2836C7](<All In One/Hewlett-Packard/23/23-p100br/884153A84576/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/2EEC2836C7>) |
| 10ec:5229 | 103c:838b | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [A8811301BC](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-r0xx/67514D08A17D/UBUNTU-20.10/5.8.0-45-GENERIC/X86_64/A8811301BC>) |
| 10ec:5229 | 17aa:362f | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [F68E55CABC](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 700-24ISH F0BE001FUK/7632963F3D46/BLENDOS/6.2.12-ARCH1-1/X86_64/F68E55CABC>) |
| 10ec:5229 | 17aa:3630 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [C27DA0FAA9](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 300-23ISU F0BY00DMPB/0FB4A4AA4C0E/ENDEAVOUROS-ROLLING/5.15.44-1-LTS/X86_64/C27DA0FAA9>) |
| 10ec:5229 | 17aa:365a | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [057EEED322](<All In One/Lenovo/IdeaCentre/IdeaCentre B540 10099/372D40F76422/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/057EEED322>) |
| 10ec:5229 | 17aa:3696 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [E18CF3C9D1](<All In One/Lenovo/S40-40/S40-40 F0AX0053PB/A9A8B8D300C2/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E18CF3C9D1>) |
| 10ec:5229 | 17aa:369e | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [E23317D53C](<All In One/Lenovo/C470/C470 10170/5548781AD8E3/ENDLESS-4.0.4/5.11.0-35-GENERIC/X86_64/E23317D53C>) |
| 10ec:5229 | 17aa:36a6 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [529C1ED52A](<All In One/Lenovo/C40-30/C40-30 F0B400HEUK/36D58D1F4DE3/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/529C1ED52A>) |
| 10ec:5229 | 17aa:36a9 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [D222B1E86E](<All In One/Lenovo/C20-30/C20-30 F0B2002MIN/14B56D60C6D7/POP!_OS-22.04/5.17.5-76051705-GENERIC/X86_64/D222B1E86E>) |
| 10ec:5229 | 17aa:36bc | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [810692EB45](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 510-22ISH F0CB00GMRK/9393738F2617/MANJARO-22.1.0/6.2.9-1-MANJARO/X86_64/810692EB45>) |
| 10ec:5229 | 17aa:36bd | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [8408512E28](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 510-23ASR F0CE002FPB/5E3418497EEF/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/8408512E28>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10de:0aa3 | 10de:cb79 | Nvidia           | MCP79 Co-processor                   | 128   | nvidia     | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 10de:0753 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 11    |            | [E0B8F5D54B](<All In One/Acer/Aspire/Aspire Z3101/B30C614DB765/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/E0B8F5D54B>) |
| 10de:0aa3 | 1462:4570 | Nvidia           | MCP79 Co-processor                   | 5     | nvidia     | [71C47135FC](<All In One/MSI/MS-AA/MS-AA1511/7E1B74B959FB/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/71C47135FC>) |
| 10de:0aa3 | 1043:8379 | Nvidia           | MCP79 Co-processor                   | 2     |            | [72365E4985](<All In One/ASUSTek Computer/ET/ET2002/9AD492BE589B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/72365E4985>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c3a | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 170   | mei_me     | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 8086:8c3a | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 89    | mei_me     | [00D8186404](<All In One/Apple/iMac14/iMac14,2/6ABD34C5E7DF/UBUNTU-22.04/5.15.0-33-GENERIC/X86_64/00D8186404>) |
| 8086:a13a | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 89    | mei_me     | [EE288626F4](<All In One/Apple/iMac18/iMac18,3/85F2F89AFF57/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/EE288626F4>) |
| 8086:a360 | 8086:7270 | Intel            | Cannon Lake PCH HECI Controller      | 51    | mei_me     | [0F3F45F8E9](<All In One/Apple/iMac19/iMac19,2/5322EAC8B99B/PARROT-5.2/6.0.0-12PARROT1-AMD64/X86_64/0F3F45F8E9>) |
| 8086:1e3a | 8086:7270 | Intel            | 7 Series/C216 Chipset Family MEI ... | 49    | mei_me     | [C8C9C1E591](<All In One/Apple/iMac13/iMac13,1/ED988FB747CF/DEBIAN-11/5.10.0-21-AMD64/X86_64/C8C9C1E591>) |
| 8086:a328 | 8086:7270 | Intel            | Cannon Lake PCH Serial IO UART Ho... | 49    | intel_l... | [0F3F45F8E9](<All In One/Apple/iMac19/iMac19,2/5322EAC8B99B/PARROT-5.2/6.0.0-12PARROT1-AMD64/X86_64/0F3F45F8E9>) |
| 8086:a329 | 8086:7270 | Intel            | 300 Series Chipset Family            | 49    | intel_l... | [0F3F45F8E9](<All In One/Apple/iMac19/iMac19,2/5322EAC8B99B/PARROT-5.2/6.0.0-12PARROT1-AMD64/X86_64/0F3F45F8E9>) |
| 8086:a2ba | 1019:a5a1 | Intel            | 200 Series PCH CSME HECI #1          | 22    | mei_me     | [63DBB9394E](<All In One/ICL/RAY/RAY S122.Mi/767FFC5AB7B5/ALT-8.4/5.10.83-STD-DEF-ALT0.C9F.2/X86_64/63DBB9394E>) |
| 8086:8cba | 8086:7270 | Intel            | 9 Series Chipset Family ME Interf... | 19    | mei_me     | [570077AA64](<All In One/Apple/iMac16/iMac16,2/2D4E89D37302/ZORIN-16/5.15.0-69-GENERIC/X86_64/570077AA64>) |
| 8086:9d3a | 103c:84de | Intel            | Sunrise Point-LP CSME HECI #1        | 17    | mei_me     | [CDB6233482](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/13576610145B/DEBIAN-11/5.10.0-18-AMD64/X86_64/CDB6233482>) |
| 8086:1c3a | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 16    | mei_me     | [D75E472005](<All In One/Lenovo/C440/C440 10104/983B023892A1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/D75E472005>) |
| 8086:8c3a | 1028:05a7 | Intel            | 8 Series/C220 Series Chipset Fami... | 15    | mei_me     | [757AE6AA73](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/099C9C0A02A0/DEBIAN-11/5.10.0-20-AMD64/X86_64/757AE6AA73>) |
| 8086:1c3a | 1028:0511 | Intel            | 6 Series/C200 Series Chipset Fami... | 14    | mei_me     | [225E42D432](<All In One/Dell/Inspiron/Inspiron One 2320/D8B99273D539/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/225E42D432>) |
| 8086:1e3a | 1028:0543 | Intel            | 7 Series/C216 Chipset Family MEI ... | 14    | mei_me     | [00CB2D66A8](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/42A1DEC89484/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/00CB2D66A8>) |
| 8086:1e3a | 1028:0548 | Intel            | 7 Series/C216 Chipset Family MEI ... | 14    | mei_me     | [22CBD67F5D](<All In One/Dell/Inspiron/Inspiron One 2330/C959D85DE508/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/22CBD67F5D>) |
| 8086:a360 | 103c:84ee | Intel            | Cannon Lake PCH HECI Controller      | 14    | mei_me     | [8E1245836B](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/B6DE3C8A8AED/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/8E1245836B>) |
| 8086:8c3a | 1028:05db | Intel            | 8 Series/C220 Series Chipset Fami... | 13    | mei_me     | [323E28FDED](<All In One/Dell/Inspiron/Inspiron 2350/07DCD03E083E/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/323E28FDED>) |
| 8086:9c3a | 8086:7270 | Intel            | 8 Series HECI #0                     | 13    | mei_me     | [6976F884E6](<All In One/Apple/iMac14/iMac14,4/6E7600BFDA83/LUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6976F884E6>) |
| 8086:9d3a | 1025:1287 | Intel            | Sunrise Point-LP CSME HECI #1        | 13    | mei_me     | [EB0191F969](<All In One/Acer/Aspire/Aspire C22-865/2C5B66C0839A/MANJARO/6.1.1-1-MANJARO/X86_64/EB0191F969>) |
| 8086:9d3a | 8086:9d3a | Intel            | Sunrise Point-LP CSME HECI #1        | 13    | mei_me     | [557E50987C](<All In One/ASUSTek Computer/ZN240/ZN240IC/A4EB8493DB43/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/557E50987C>) |
| 8086:1c3a | 103c:2ac5 | Intel            | 6 Series/C200 Series Chipset Fami... | 12    | mei_me     | [B32F35A4B1](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/C0BF0A16B6D4/FEDORA-36/5.18.19-200.FC36.X86_64/X86_64/B32F35A4B1>) |
| 8086:319a | 1025:1304 | Intel            | Celeron/Pentium Silver Processor ... | 12    | mei_me     | [07D4BF17AA](<All In One/Acer/Aspire/Aspire C22-820/D247EFB9442C/ROSA-12.3/5.10.155-GENERIC-1ROSA2021.1-X86_64/X86_64/07D4BF17AA>) |
| 8086:2e24 | 104d:9060 | Intel            | 4 Series Chipset HECI Controller     | 10    | mei_me     | [57E0224FFD](<All In One/Sony/VPCL13/VPCL13M1R/82175A598A60/RELD-7.9/5.15.33-1.RES7.X86_64/X86_64/57E0224FFD>) |
| 8086:319a | 1854:0308 | Intel            | Celeron/Pentium Silver Processor ... | 10    | mei_me     | [EC912EFB6F](<All In One/LG Electronics/22V280/22V280-L.BJ31P1/925F8D37ECFF/FEDORA-37/6.0.12-300.FC37.X86_64/X86_64/EC912EFB6F>) |
| 8086:8c3a | 1028:0626 | Intel            | 8 Series/C220 Series Chipset Fami... | 10    | mei_me     | [9348834E54](<All In One/Dell/Inspiron/Inspiron 23 Model 5348/5251BCB7D469/FEDORA-37/6.2.9-200.FC37.X86_64/X86_64/9348834E54>) |
| 8086:9cba | 8086:9cba | Intel            | Wildcat Point-LP MEI Controller #1   | 10    | mei_me     | [DEB1C6D3C8](<All In One/BESSTAR Tech/U/U700/DA83D1618698/OPENMANDRIVA-23.01/6.1.4-DESKTOP-1OMV2301/X86_64/DEB1C6D3C8>) |
| 8086:9de0 | 17aa:3145 | Intel            | Cannon Point-LP MEI Controller #1    | 10    | mei_me     | [FAEB46556E](<All In One/Lenovo/V540-24IWL/V540-24IWL AIO 10YS0031RU/886440AA02F6/KOMETA-P10/5.10.102-STD-DEF-ALT1/X86_64/FAEB46556E>) |
| 8086:1c3a | 17aa:366c | Intel            | 6 Series/C200 Series Chipset Fami... | 9     | mei_me     | [55C11B6B87](<All In One/Lenovo/C540/C540 10110/D5261210E56A/OPENMANDRIVA-4.50/5.12.4-DESKTOP-1OMV4050/X86_64/55C11B6B87>) |
| 8086:7ae8 |           | Intel            | Alder Lake-S PCH HECI Controller #1  | 9     | mei_me     | [E734B33010](<All In One/Graviton/D12/D12i/E65E993A1E87/ALT-10.1/5.15.104-UN-DEF-ALT1/X86_64/E734B33010>) |
| 8086:9d3a | 8086:7270 | Intel            | Sunrise Point-LP CSME HECI #1        | 9     | mei_me     | [426C7D7939](<All In One/Apple/iMac18/iMac18,1/61AC5215756C/XUBUNTU-22.04/5.19.0-35-GENERIC/X86_64/426C7D7939>) |
| 8086:a13a | 1028:06c5 | Intel            | 100 Series/C230 Series Chipset Fa... | 9     | mei_me     | [5B29ED7213](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/BE925566CC9F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5B29ED7213>) |
| 8086:1c3a | 104d:907e | Intel            | 6 Series/C200 Series Chipset Fami... | 8     | mei_me     | [0451CAEB29](<All In One/Sony/VPCL212/VPCL212FX/01EE677E7F92/UBUNTU-21.10/5.13.0-22-GENERIC/X86_64/0451CAEB29>) |
| 8086:34e0 | 1025:1418 | Intel            | Ice Lake-LP Management Engine        | 8     | mei_me     | [A82A90955E](<All In One/Acer/Aspire/Aspire C27-962/563F493FD77F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/A82A90955E>) |
| 8086:3b64 | 17aa:306a | Intel            | 5 Series/3400 Series Chipset HECI... | 8     | mei_me     | [ED812A8A26](<All In One/Lenovo/ThinkCentre/ThinkCentre M90z 5205W5Q/2D0BC11CA89A/LINUXMINT-21.1/5.15.0-58-GENERIC/X86_64/ED812A8A26>) |
| 8086:7aa8 |           | Intel            | Alder Lake-S PCH Serial IO UART #0   | 8     | intel_lpss | [E734B33010](<All In One/Graviton/D12/D12i/E65E993A1E87/ALT-10.1/5.15.104-UN-DEF-ALT1/X86_64/E734B33010>) |
| 8086:9cba | 8086:7270 | Intel            | Wildcat Point-LP MEI Controller #1   | 8     | mei_me     | [44B9054B8C](<All In One/Apple/iMac16/iMac16,1/FCCB3A22541B/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/44B9054B8C>) |
| 8086:a13a | 103c:2b3e | Intel            | 100 Series/C230 Series Chipset Fa... | 8     | mei_me     | [70F8CE05B6](<All In One/Hewlett-Packard/24/24-n000ny/C2F705DD30EA/UBUNTU-20.04/5.15.0-69-GENERIC/X86_64/70F8CE05B6>) |
| 8086:1e3a | 144d:b091 | Intel            | 7 Series/C216 Chipset Family MEI ... | 7     | mei_me     | [DD513D338C](<All In One/Samsung Electronics/DP700/DP700A3D-DM700A3D-DB701A3D-DP700A7D/F34D6AA53F0D/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/DD513D338C>) |
| 8086:319a | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 7     | mei_me     | [38C2A94BAA](<All In One/Positivo/C464/C464A-21/1A925F871EA8/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/38C2A94BAA>) |
| 8086:43e0 |           | Intel            | Tiger Lake-H Management Engine In... | 7     | mei_me     | [A61FFC94F5](<All In One/ICL/RAY/RAY Si105.Mi/F9B3F6AA07E6/MOS-10/5.10.136-STD-DEF-ALT1/X86_64/A61FFC94F5>) |
| 8086:5a9a | 17aa:36c4 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 7     | mei_me     | [5D5EB8D675](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 310-20IAP F0CL0014LD/4155E31B2EFA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/5D5EB8D675>) |
| 8086:5a9a | 1854:0267 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 7     | mei_me     | [04D33628A1](<All In One/LG Electronics/22V270/22V270-L.BJ31P1/8E73444ADF98/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/04D33628A1>) |
| 8086:8c3a | 17aa:367b | Intel            | 8 Series/C220 Series Chipset Fami... | 7     | mei_me     | [4CC2E8CADD](<All In One/Lenovo/IdeaCentre/IdeaCentre B550 10135/0A3ACDFA18A3/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/4CC2E8CADD>) |
| 8086:8c3a | 17aa:3686 | Intel            | 8 Series/C220 Series Chipset Fami... | 7     | mei_me     | [A079D28341](<All In One/Lenovo/C560/C560 10150/6C9E3A129538/LINUXMINT-21.1/5.15.0-58-GENERIC/X86_64/A079D28341>) |
| 8086:9d3a | 1028:0754 | Intel            | Sunrise Point-LP CSME HECI #1        | 7     | mei_me     | [348BC23246](<All In One/Dell/Inspiron/Inspiron 3464 AIO/00109263052E/ENDEAVOUROS-ROLLING/5.15.71-1-LTS/X86_64/348BC23246>) |
| 8086:9de0 | 1043:17b1 | Intel            | Cannon Point-LP MEI Controller #1    | 7     | mei_me     | [24ED481783](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_A6521FA/262E2C088492/RED-OS-7.3.2/5.15.72-1.EL7.3.X86_64/X86_64/24ED481783>) |
| 8086:a0e0 | 1028:0a06 | Intel            | Tiger Lake-LP Management Engine I... | 7     | mei_me     | [39994ACDE2](<All In One/Dell/Inspiron/Inspiron 5400 AIO/A2D2F4CB9A93/LINUXMINT-20.3/5.13.0-25-GENERIC/X86_64/39994ACDE2>) |
| 8086:a2ba |           | Intel            | 200 Series PCH CSME HECI #1          | 7     | mei_me     | [01458C55A9](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-24IKL F0D1009MRI/71B1EDB2A2DC/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/01458C55A9>) |
| 8086:a2ba | 1028:079c | Intel            | 200 Series PCH CSME HECI #1          | 7     | mei_me     | [1940C6417C](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/A9167F8393F4/DEBIAN-11/5.10.0-21-AMD64/X86_64/1940C6417C>) |
| 8086:1c3a | 1043:1c3a | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | mei_me     | [1775D6A140](<All In One/ASUSTek Computer/ET2411/ET2411_W8/55B530902FB8/LINUXMINT-21/5.15.0-50-GENERIC/X86_64/1775D6A140>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1537 | 1022:1537 | AMD              | Kabini/Mullins PSP-Platform Secur... | 26    | ccp        | [4891D8306B](<All In One/Lenovo/C40-05/C40-05 F0B5004EUK/84C5083CE2E4/LINUXMINT-20.2/5.4.0-139-GENERIC/X86_64/4891D8306B>) |
| 1022:1537 | 103c:8245 | AMD              | Kabini/Mullins PSP-Platform Secur... | 17    | ccp        | [81F625006B](<All In One/Hewlett-Packard/24/24-g020/310803ED8E33/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/81F625006B>) |
| 1022:1578 | 103c:8381 | AMD              | Carrizo Platform Security Processor  | 13    |            | [6745FD4BAC](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/EF305E495BCA/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/6745FD4BAC>) |
| 1022:1578 | 103c:8430 | AMD              | Carrizo Platform Security Processor  | 13    |            | [B813F95C6F](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/3A989707384A/ZORIN-16/5.15.0-69-GENERIC/X86_64/B813F95C6F>) |
| 8086:2298 | 103c:81bb | Intel            | Atom/Celeron/Pentium Processor x5... | 13    | mei_txe    | [8C50716D55](<All In One/Hewlett-Packard/20/20-c012a/A9551DF58B53/LINUXMINT-20.3/5.4.0-148-GENERIC/X86_64/8C50716D55>) |
| 1022:15df | 1022:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 11    | ccp        | [98E5C0BA37](<All In One/iRU/P2320/P2320P/D2E5AC71120D/RED-OS-7.3.2/5.15.87-1.EL7.3.X86_64/X86_64/98E5C0BA37>) |
| 1022:15df | 103c:86f3 | AMD              | Family 17h (Models 10h-1fh) Platf... | 11    | ccp        | [DC3ADE850C](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-df0xxx/149EB6B30B69/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/DC3ADE850C>) |
| 1022:1537 | 103c:2b3b | AMD              | Kabini/Mullins PSP-Platform Secur... | 10    | ccp        | [CB25C51987](<All In One/Hewlett-Packard/23/23-r155la/F1B498CB86AC/ZORIN-16/5.15.0-60-GENERIC/X86_64/CB25C51987>) |
| 1022:1578 | 1022:1578 | AMD              | Carrizo Platform Security Processor  | 8     |            | [F320BC5964](<All In One/Acer/Aspire/Aspire C24-320/B5B117AAD478/ARCH-ROLLING/6.2.6-ZEN1-1-ZEN/X86_64/F320BC5964>) |
| 8086:0f18 | 17aa:3695 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 7     | mei_txe    | [B6C7B47859](<All In One/Lenovo/C260/C260 10160/399A2B69BAD6/LINUXMINT-21/5.15.0-56-GENERIC/X86_64/B6C7B47859>) |
| 8086:0f18 | 1854:0200 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 7     | mei_txe    | [163C52FD3C](<All In One/LG Electronics/22V240/22V240-L.AK35B2/3689BD3EEE5E/MANJARO-22.0.4/6.1.12-1-MANJARO/X86_64/163C52FD3C>) |
| 8086:0f18 |           | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | mei_txe    | [DD0DFFA557](<All In One/Acer/Aspire/Aspire Z1-601/F2C9FDE7700C/ROSA-12.3/5.10.155-GENERIC-1ROSA2021.1-X86_64/X86_64/DD0DFFA557>) |
| 8086:0f18 | 1028:0690 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | mei_txe    | [8A25091E19](<All In One/Dell/Inspiron/Inspiron 20 Model 3043/302C3227E59B/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/8A25091E19>) |
| 8086:2298 | 1028:06cc | Intel            | Atom/Celeron/Pentium Processor x5... | 6     | mei_txe    | [3AC5DA5F93](<All In One/Dell/Inspiron/Inspiron 20-3052/E44132686405/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/3AC5DA5F93>) |
| 8086:2298 | 8086:2298 | Intel            | Atom/Celeron/Pentium Processor x5... | 6     | mei_txe    | [69F378F0B5](<All In One/ASUSTek Computer/A/A4110/B91604D5677F/UBUNTU-20.04/5.15.0-60-GENERIC/X86_64/69F378F0B5>) |
| 8086:0f18 | 1025:085f | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 5     | mei_txe    | [FF4762D139](<All In One/Acer/Aspire/Aspire ZC-606/A2FBE9AD3965/KDE-NEON-22.04/5.15.0-57-GENERIC/X86_64/FF4762D139>) |
| 8086:0f18 | 17aa:36a8 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 5     | mei_txe    | [837C6C4BE9](<All In One/Lenovo/S20-00/S20-00 F0AY007RRK/A53BFEE0ED22/POP!_OS-22.04/6.0.6-76060006-GENERIC/X86_64/837C6C4BE9>) |
| 8086:2298 | 1297:2053 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | mei_txe    | [95E8BED16F](<All In One/Positivo/DH8/DH8BW01/5F022083C428/KDE-NEON-20.04/5.15.0-50-GENERIC/X86_64/95E8BED16F>) |
| 1022:1456 | 1022:1456 | AMD              | Family 17h (Models 00h-0fh) Platf... | 4     | ccp        | [CBAE954ECC](<All In One/Dell/Inspiron/Inspiron 27 7775/ACE5205CCA5D/NIXOS-22.11/5.15.86/X86_64/CBAE954ECC>) |
| 1022:1537 | 103c:2b2f | AMD              | Kabini/Mullins PSP-Platform Secur... | 4     | ccp        | [13AEF3E1EF](<All In One/Hewlett-Packard/205/205 G2 AiO Business PC/5629DB684FCA/KALI-2022.1/5.18.0-KALI5-AMD64/X86_64/13AEF3E1EF>) |
| 1022:15df | 1028:0b83 | AMD              | Family 17h (Models 10h-1fh) Platf... | 4     | ccp        | [D7ED216BE7](<All In One/Dell/Inspiron/Inspiron 24 5415 All-in-One/FBE2C11F8067/ARCH-22.10/6.3.1-ARCH1-1/X86_64/D7ED216BE7>) |
| 1022:15df | 103c:86ee | AMD              | Family 17h (Models 10h-1fh) Platf... | 4     | ccp        | [2632541785](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-d0xxx/CF27A731CFBC/ENDEAVOUROS-ROLLING/6.1.7-ARCH1-1/X86_64/2632541785>) |
| 1022:15df | 103c:86f1 | AMD              | Family 17h (Models 10h-1fh) Platf... | 4     | ccp        | [4160198447](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-dp0xxx/C4EA82C77997/UBUNTU-20.04/5.15.0-60-GENERIC/X86_64/4160198447>) |
| 1022:15df | 17aa:371c | AMD              | Family 17h (Models 10h-1fh) Platf... | 4     | ccp        | [02248F5982](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 24ARE05 F0EW00GRSP/2AC57BE6BCD7/OPENMANDRIVA-23.01/6.1.4-DESKTOP-1OMV2301/X86_64/02248F5982>) |
| 1022:15df | 17aa:3746 | AMD              | Family 17h (Models 10h-1fh) Platf... | 4     | ccp        | [EC07BB84CF](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 27ALC6 F0FY0055GE/634764CAF8D6/SIDUCTION-12/6.2.8-1-SIDUCTION-AMD64/X86_64/EC07BB84CF>) |
| 8086:2298 | 1025:0992 | Intel            | Atom/Celeron/Pentium Processor x5... | 4     | mei_txe    | [1485AD36A9](<All In One/Acer/Aspire/Aspire ZC-700G/1E352591F189/ARCH-ROLLING/6.1.2-ARCH1-1/X86_64/1485AD36A9>) |
| 1022:1578 | 1028:07e3 | AMD              | Carrizo Platform Security Processor  | 3     |            | [87A4F1E989](<All In One/Dell/Inspiron/Inspiron 24 5475/44B04AE381C1/UBUNTU-18.04/5.4.0-89-GENERIC/X86_64/87A4F1E989>) |
| 1022:1578 | 1028:0854 | AMD              | Carrizo Platform Security Processor  | 3     |            | [1629350AA9](<All In One/Dell/Inspiron/Inspiron 3475 AIO/33D749C2D2FC/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/1629350AA9>) |
| 1022:1578 | 17aa:36bd | AMD              | Carrizo Platform Security Processor  | 3     |            | [8408512E28](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 510-23ASR F0CE002FPB/5E3418497EEF/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/8408512E28>) |
| 1022:1578 | 17aa:36be | AMD              | Carrizo Platform Security Processor  | 3     |            | [0759C30DD9](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 510-22ASR F0CC001BIX/E61608155EDF/UBUNTU-22.10/5.19.0-31-GENERIC/X86_64/0759C30DD9>) |
| 1022:15df | 103c:84ef | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     | ccp        | [D69B1AAB65](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-xa0xxx/6A8FC1FFC319/FEDORA-37/6.0.7-301.FC37.X86_64/X86_64/D69B1AAB65>) |
| 1022:15df | 103c:8582 | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     | ccp        | [4977F9D91D](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c1xx/674AC15919F3/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/4977F9D91D>) |
| 1022:15df | 103c:8924 | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     | ccp        | [53F993BF5D](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One Desktop 24-ca0xxx/B50333765A75/LINUXMINT-21/6.0.0-060000-GENERIC/X86_64/53F993BF5D>) |
| 1022:15df | 1043:1832 | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     | ccp        | [F6285D1100](<All In One/ASUSTek Computer/ASUS/ASUS ZEN AIO M5401WUA_M5401WUA/525FB10EAB16/DEBIAN-UNSTABLE/6.2.9-4-LIQUORIX-AMD64/X86_64/F6285D1100>) |
| 1022:15df | 17aa:36f5 | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     | ccp        | [EB38810FB8](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-24ARR F0DN006KGE/1D5E59C5CB5F/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/EB38810FB8>) |
| 8086:0f18 | 1025:0994 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     | mei_txe    | [6247D83BAB](<All In One/Acer/Aspire/Aspire Z1-611/A6EFF7123453/LINUXMINT-19.1/4.15.0-128-GENERIC/X86_64/6247D83BAB>) |
| 8086:0f18 | 1297:2041 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     | mei_txe    | [8184754BDE](<All In One/Positivo/DC8/DC8BT11/F752C6629913/UBUNTU-22.04/5.15.0-39-GENERIC/X86_64/8184754BDE>) |
| 8086:2298 | 1025:1065 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | mei_txe    | [19582F3331](<All In One/Acer/Aspire/Aspire Z1-612/3EB132BE1DF2/ROSA-2016.1/5.4.32-GENERIC-2ROSA-X86_64/X86_64/19582F3331>) |
| 1022:1537 | 103c:2b54 | AMD              | Kabini/Mullins PSP-Platform Secur... | 2     | ccp        | [B47807A201](<All In One/Hewlett-Packard/20/20-e001la/E3C43A35761C/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/B47807A201>) |
| 1022:1578 | 103c:8374 | AMD              | Carrizo Platform Security Processor  | 2     |            | [68015B73D0](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-r0xx/27EA4D544A61/ALT-10.1/5.15.72-UN-DEF-ALT1/X86_64/68015B73D0>) |
| 1022:1578 | 17aa:36ec | AMD              | Carrizo Platform Security Processor  | 2     |            | [2CFA2D338E](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 330-20AST F0D8001LUS/36DA6D8B2B0D/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/2CFA2D338E>) |
| 1022:15df | 103c:8449 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     | ccp        | [A1CB66A671](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-r0xx/117890FC2D25/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/A1CB66A671>) |
| 1022:15df | 103c:85ba | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     | ccp        | [A67C97653F](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa1xxx/99B46DAA2CED/ARCH-ROLLING/6.0.8-ARCH1-1/X86_64/A67C97653F>) |
| 1022:15df | 17aa:3703 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     | ccp        | [5DA493DE55](<All In One/Lenovo/IdeaCentre/IdeaCentre A540-24API F0EM0000UK/93E2EABF69EE/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/5DA493DE55>) |
| 1022:15df | 17aa:371d | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     | ccp        | [2BD3CDBC37](<All In One/Lenovo/AIO/AIO 3-22ADA05 F0EX003JRK/BA9C03EB4E8E/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/2BD3CDBC37>) |
| 8086:0f18 | 1025:084d | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | mei_txe    | [EA620E0681](<All In One/Acer/Aspire/Aspire Z3-600/BD66BD02AA7B/LINUX-LITE-6.4/5.15.0-71-GENERIC/X86_64/EA620E0681>) |
| 8086:0f18 | 17aa:368a | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | mei_txe    | [08057029E5](<All In One/Lenovo/N300/N300 10161/C819A7104F2E/KDE-NEON-18.04/5.4.0-42-GENERIC/X86_64/08057029E5>) |
| 8086:2298 | 1025:098f | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | mei_txe    | [350CC83AC7](<All In One/Acer/Aspire/Aspire Z1-622/12DC70B153E8/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/350CC83AC7>) |
| 8086:2298 | 8086:1e8b | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | mei_txe    | [3796D857B1](<All In One/Multilaser/UB82/UB82X/0D4FF609D328/MANJARO/6.2.12-1-MANJARO/X86_64/3796D857B1>) |
| 1022:1486 | 1022:1486 | AMD              | Starship/Matisse Cryptographic Co... | 1     | ccp        | [991A74F3E5](<All In One/Acidanthera/iMacPro1/iMacPro1,1/068603353593/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/991A74F3E5>) |

### Firewire controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 11c1:5901 | 11c1:5900 | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 385   | firewir... | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 104c:823f |           | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 154   | firewir... | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 11c1:5811 | 11c1:5811 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 28    | firewir... | [C7444AC7F0](<All In One/Apple/iMac5/iMac5,1/104264B0BD86/XUBUNTU-22.04/5.15.0-70-GENERIC/X86_64/C7444AC7F0>) |
| 1180:e832 | 104d:9060 | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 10    | firewir... | [57E0224FFD](<All In One/Sony/VPCL13/VPCL13M1R/82175A598A60/RELD-7.9/5.15.33-1.RES7.X86_64/X86_64/57E0224FFD>) |
| 1180:e832 | 104d:907e | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 8     | firewir... | [0451CAEB29](<All In One/Sony/VPCL212/VPCL212FX/01EE677E7F92/UBUNTU-21.10/5.13.0-22-GENERIC/X86_64/0451CAEB29>) |
| 1180:e832 | 104d:9097 | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 6     | firewir... | [CEFAD415D0](<All In One/Sony/SVL2411/SVL24117FLB/B337A07B7653/POP!_OS-22.04/6.0.2-76060002-GENERIC/X86_64/CEFAD415D0>) |
| 197b:2380 | 103c:1489 | JMicron Techn... | IEEE 1394 Host Controller            | 6     | firewir... | [EBD3760355](<All In One/Hewlett-Packard/Compaq/Compaq 6000 Pro AiO Business PC/F6BD16E86080/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/EBD3760355>) |
| 197b:2380 | 17aa:3602 | JMicron Techn... | IEEE 1394 Host Controller            | 5     | firewir... | [195EC7CB8C](<All In One/Lenovo/10051/10051/11244BE45969/LINUXMINT-20.3/5.4.0-126-GENERIC/X86_64/195EC7CB8C>) |
| 1180:0832 | 104d:9044 | Ricoh            | R5C832 IEEE 1394 Controller          | 4     | firewir... | [3ED1AD79E4](<All In One/Sony/VGC-JS54/VGC-JS54FB_W/1013B0577913/LINUX-LITE-6.0/5.16.9/X86_64/3ED1AD79E4>) |
| 1180:e832 | 104d:9074 | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 4     | firewir... | [2DEFAA2F88](<All In One/Sony/VPCJ118/VPCJ118FJ/356CC6106273/UBUNTU-20.04/5.15.0-43-GENERIC/X86_64/2DEFAA2F88>) |
| 104c:8025 |           | Texas Instrum... | TSB82AA2 IEEE-1394b Link Layer Co... | 2     | firewir... | [2BAA39FB91](<All In One/Apple/iMac6/iMac6,1/06954601F29C/UBUNTU-UNITY-16.04/4.15.0-88-GENERIC/X86_64/2BAA39FB91>) |
| 1180:0832 | 104d:9043 | Ricoh            | R5C832 IEEE 1394 Controller          | 2     | firewir... | [AFA509714D](<All In One/Sony/VGC-LN52/VGC-LN52JGB/54F15FF48E03/UBUNTU-20.04/5.8.0-54-GENERIC/X86_64/AFA509714D>) |
| 1180:e832 | 104d:908e | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 2     | firewir... | [E43A2C01EB](<All In One/Sony/VPCL22/VPCL22Z1R/BC94F4FEC1E7/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/E43A2C01EB>) |
| 11c1:5901 | c111:0159 | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 2     | firewir... | [CE6F6FCAAD](<All In One/Apple/iMac12/iMac12,2/39781DFD6EA7/POP!_OS-22.04/6.0.6-76060006-GENERIC/X86_64/CE6F6FCAAD>) |
| 1217:13f7 | 1bcf:a013 | O2 Micro         | 1394 OHCI Compliant Host Controller  | 2     | firewir... | [1494683BB9](<All In One/NEC Computers/PC-VN770/PC-VN770DS3ER/18CEF0AA43DB/UBUNTU-20.04/5.8.0-48-GENERIC/X86_64/1494683BB9>) |
| 197b:2380 | 103c:3561 | JMicron Techn... | IEEE 1394 Host Controller            | 2     | firewir... | [7AF1912AB7](<All In One/Hewlett-Packard/Z1/Z1 Workstation/4089A5726DF1/FEDORA-37/6.0.9-300.FC37.X86_64/X86_64/7AF1912AB7>) |
| 104c:8024 | 9005:0030 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 1     | firewir... | [098FE372A3](<All In One/Acidanthera/iMac14/iMac14,4/E2C69985CC45/GENTOO-2.6/5.4.97-GENTOO_DQ87PG/X86_64/098FE372A3>) |
| 104c:8029 | 107b:4009 | Texas Instrum... | PCI4510 IEEE-1394 Controller         | 1     | firewir... | [0213C3A21C](<All In One/Gateway/PROFILE5/PROFILE5.5/89C7C3620F05/UBUNTU-18.04/4.15.0-122-GENERIC/I686/0213C3A21C>) |
| 1106:3401 | 17aa:3603 | VIA Technologies | FireWire (IEEE 1394)                 | 1     | firewir... | [8399296D51](<All In One/Lenovo/IdeaCentre/IdeaCentre B305 10052/A8184A7A8382/UBUNTU-20.04/5.8.0-55-GENERIC/X86_64/8399296D51>) |
| 1106:3401 | 17aa:3608 | VIA Technologies | FireWire (IEEE 1394)                 | 1     | firewir... | [69574214D7](<All In One/Lenovo/IdeaCentre/IdeaCentre A700 10050/51968677EC4C/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/69574214D7>) |
| 1180:0552 | 1033:886f | Ricoh            | R5C552 IEEE 1394 Controller          | 1     | firewir... | [86771347FB](<All In One/NEC Computers/PC-GV58/PC-GV58ZYCAA/96538F2FC249/UBUNTU-19.04/5.0.0-13-GENERIC/X86_64/86771347FB>) |
| 1217:10f7 | 1033:8959 | O2 Micro         | 1394 OHCI Compliant Host Controller  | 1     | firewir... | [6F4A2D24C1](<All In One/NEC Computers/PC-VW770/PC-VW770CS6B/CD4FBB5FF80F/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/6F4A2D24C1>) |
| 1217:10f7 | 17aa:3068 | O2 Micro         | 1394 OHCI Compliant Host Controller  | 1     | firewir... | [27E7D42D53](<All In One/Lenovo/Others/Others/18DB28A21724/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/27E7D42D53>) |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1577 | 1022:1577 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 19    |            | [F320BC5964](<All In One/Acer/Aspire/Aspire C24-320/B5B117AAD478/ARCH-ROLLING/6.2.6-ZEN1-1-ZEN/X86_64/F320BC5964>) |
| 1022:1419 | 1022:1419 | AMD              | Family 15h (Models 10h-1fh) I/O M... | 1     |            | [1DC2419A21](<All In One/Gigabyte Technology/GB-A5/GB-A5DNK-RH/2D59EF3CA1FB/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/1DC2419A21>) |
| 1022:1423 | 17aa:368f | AMD              | Family 15h (Models 30h-3fh) I/O M... | 1     |            | [58DDD6F565](<All In One/Lenovo/B50-35/B50-35 F0AV0025GE/7D201658F55F/ROSA-2014.1/4.9.76-NRJ-DESKTOP-1ROSA-X86_64/X86_64/58DDD6F565>) |
| 1022:1451 | 1022:1451 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 1     |            | [42B182D5F0](<All In One/Acidanthera/iMacPro1/iMacPro1,1/9A30E1010885/ARCH/5.9.10-ARCH1-1/X86_64/42B182D5F0>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0102 | 8086:2010 | Intel            | 2nd Generation Core Processor Fam... | 93    | i915       | [E4718D8B12](<All In One/Apple/iMac12/iMac12,1/6CEFAE063257/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/E4718D8B12>) |
| 1002:9583 | 106b:0083 | AMD              | RV630/M76 [Mobility Radeon HD 260... | 90    | radeon     | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 8086:0102 | 106b:0000 | Intel            | 2nd Generation Core Processor Fam... | 73    | i915       | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 1002:6741 | 106b:6741 | AMD              | Whistler [Radeon HD 6630M/6650M/6... | 71    | radeon     | [E4718D8B12](<All In One/Apple/iMac12/iMac12,1/6CEFAE063257/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/E4718D8B12>) |
| 1002:9488 | 106b:00b6 | AMD              | RV730/M96-XT [Mobility Radeon HD ... | 59    | radeon     | [F0EA43F3FD](<All In One/Apple/iMac11/iMac11,2/40AA4B37D450/ZORIN-15/5.4.0-146-GENERIC/X86_64/F0EA43F3FD>) |
| 1002:94c8 | 106b:0084 | AMD              | RV610/M74 [Mobility Radeon HD 240... | 58    | radeon     | [7521D3D742](<All In One/Apple/iMac8/iMac8,1/8403D7AC4B00/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/7521D3D742>) |
| 1002:6740 | 106b:6740 | AMD              | Whistler [Radeon HD 6730M/6770M/7... | 56    | radeon     | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 10de:0867 | 106b:00ad | Nvidia           | C79 [GeForce 9400]                   | 45    | nouveau    | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 1002:6720 | 106b:0b00 | AMD              | Blackcomb [Radeon HD 6970M/6990M]    | 40    | radeon     | [081ECD2050](<All In One/Apple/iMac12/iMac12,2/E37CB5F9125E/LINUXMINT-21.1/5.15.0-67-GENERIC/X86_64/081ECD2050>) |
| 10de:0869 | 106b:00b4 | Nvidia           | MCP7A [GeForce 9400]                 | 33    | nouveau    | [3165AB3194](<All In One/Apple/iMac10/iMac10,1/97AFDCCBEBDE/KUBUNTU-23.04/6.2.0-1003-LOWLATENCY/X86_64/3165AB3194>) |
| 8086:0d22 | 106b:0122 | Intel            | Crystal Well Integrated Iris Pro ... | 26    | i915       | [0A7DBD4CC4](<All In One/Apple/iMac14/iMac14,1/BBFFFA015602/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/0A7DBD4CC4>) |
| 1002:68a1 | 106b:00cc | AMD              | Broadway PRO [Mobility Radeon HD ... | 25    | radeon     | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 1002:71c5 | 106b:0080 | AMD              | RV530/M56-P [Mobility Radeon X1600]  | 24    | radeon     | [C7444AC7F0](<All In One/Apple/iMac5/iMac5,1/104264B0BD86/XUBUNTU-22.04/5.15.0-70-GENERIC/X86_64/C7444AC7F0>) |
| 10de:0fd8 | 106b:0109 | Nvidia           | GK107M [GeForce GT 640M Mac Edition] | 24    | nvidia     | [D458AE07B2](<All In One/Apple/iMac13/iMac13,1/151F107DD0F7/CLEAR-LINUX-OS-37980/6.1.2-1232.NATIVE/X86_64/D458AE07B2>) |
| 1002:67ef | 106b:016b | AMD              | Baffin [Radeon RX 460/560D / Pro ... | 22    | amdgpu     | [3F40AAB3D2](<All In One/Apple/iMac18/iMac18,2/87B5E6EFECC5/LINUXMINT-21.1/5.17.0-1027-OEM/X86_64/3F40AAB3D2>) |
| 1002:944a | 106b:00b5 | AMD              | RV770/M98L [Mobility Radeon HD 4850] | 20    | radeon     | [8D37E3E327](<All In One/Apple/iMac11/iMac11,1/60F7DB707519/UBUNTU-22.04/5.15.0-53-GENERIC/X86_64/8D37E3E327>) |
| 10de:0fea | 106b:011f | Nvidia           | GK107M [GeForce GT 755M Mac Edition] | 19    | nvidia     | [00D8186404](<All In One/Apple/iMac14/iMac14,2/6ABD34C5E7DF/UBUNTU-22.04/5.15.0-33-GENERIC/X86_64/00D8186404>) |
| 8086:1622 | 106b:014f | Intel            | Iris Pro Graphics 6200               | 19    | i915       | [570077AA64](<All In One/Apple/iMac16/iMac16,2/2D4E89D37302/ZORIN-16/5.15.0-69-GENERIC/X86_64/570077AA64>) |
| 8086:5917 | 103c:84de | Intel            | UHD Graphics 620                     | 17    | i915       | [CDB6233482](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/13576610145B/DEBIAN-11/5.10.0-18-AMD64/X86_64/CDB6233482>) |
| 8086:0102 | 1028:0511 | Intel            | 2nd Generation Core Processor Fam... | 15    | i915       | [225E42D432](<All In One/Dell/Inspiron/Inspiron One 2320/D8B99273D539/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/225E42D432>) |
| 8086:0412 | 1028:05a7 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 15    | i915       | [757AE6AA73](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/099C9C0A02A0/DEBIAN-11/5.10.0-20-AMD64/X86_64/757AE6AA73>) |
| 8086:3e92 | 1019:a5a1 | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 15    | i915       | [B97AB9E5CA](<All In One/3Logic Group/Graviton/Graviton/223493B1237A/KOMETA-P10/5.10.109-STD-DEF-ALT1/X86_64/B97AB9E5CA>) |
| 1002:67ef | 106b:0197 | AMD              | Baffin [Radeon RX 460/560D / Pro ... | 14    | amdgpu     | [0A3F1269F7](<All In One/Apple/iMac19/iMac19,2/B35B52C73C57/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/0A3F1269F7>) |
| 1002:68c0 | 106b:00d2 | AMD              | Madison [Mobility Radeon HD 5730 ... | 14    | radeon     | [DBB3F8FA6F](<All In One/Apple/iMac11/iMac11,3/689DE043DB5E/ULTRAMARINE-37/6.2.9-200.FC37.X86_64/X86_64/DBB3F8FA6F>) |
| 1002:98e4 | 103c:8381 | AMD              | Stoney [Radeon R2/R3/R4/R5 Graphics] | 13    | amdgpu     | [6745FD4BAC](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/EF305E495BCA/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/6745FD4BAC>) |
| 1002:98e4 | 103c:8430 | AMD              | Stoney [Radeon R2/R3/R4/R5 Graphics] | 13    | amdgpu     | [B813F95C6F](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/3A989707384A/ZORIN-16/5.15.0-69-GENERIC/X86_64/B813F95C6F>) |
| 10de:119d | 106b:0120 | Nvidia           | GK104M [GeForce GTX 775M Mac Edit... | 13    | nouveau    | [94468C31E6](<All In One/Apple/iMac14/iMac14,2/112420488415/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/94468C31E6>) |
| 8086:0416 | 1028:05db | Intel            | 4th Gen Core Processor Integrated... | 13    | i915       | [323E28FDED](<All In One/Dell/Inspiron/Inspiron 2350/07DCD03E083E/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/323E28FDED>) |
| 8086:0a26 | 106b:013c | Intel            | Haswell-ULT Integrated Graphics C... | 13    | i915       | [6976F884E6](<All In One/Apple/iMac14/iMac14,4/6E7600BFDA83/LUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6976F884E6>) |
| 8086:22b1 | 103c:81bb | Intel            | Atom/Celeron/Pentium Processor x5... | 13    | i915       | [8C50716D55](<All In One/Hewlett-Packard/20/20-c012a/A9551DF58B53/LINUXMINT-20.3/5.4.0-148-GENERIC/X86_64/8C50716D55>) |
| 8086:5917 | 1025:1287 | Intel            | UHD Graphics 620                     | 13    | i915       | [EB0191F969](<All In One/Acer/Aspire/Aspire C22-865/2C5B66C0839A/MANJARO/6.1.1-1-MANJARO/X86_64/EB0191F969>) |
| 1002:6640 | 106b:014b | AMD              | Saturn XT [FirePro M6100]            | 12    | radeon     | [8DD4721BD1](<All In One/Apple/iMac17/iMac17,1/4EE67D79224F/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/8DD4721BD1>) |
| 1002:67ef | 106b:016a | AMD              | Baffin [Radeon RX 460/560D / Pro ... | 12    | amdgpu     | [AE30B95CD8](<All In One/Apple/iMac18/iMac18,2/0EF9CA00225E/NOBARA-36/6.0.9-202.FC36.X86_64/X86_64/AE30B95CD8>) |
| 8086:0102 | 103c:2ac5 | Intel            | 2nd Generation Core Processor Fam... | 12    | i915       | [B32F35A4B1](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/C0BF0A16B6D4/FEDORA-36/5.18.19-200.FC36.X86_64/X86_64/B32F35A4B1>) |
| 1002:15d8 | 103c:86f3 | AMD              | Picasso/Raven 2 [Radeon Vega Seri... | 11    | amdgpu     | [DC3ADE850C](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-df0xxx/149EB6B30B69/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/DC3ADE850C>) |
| 1002:67df | 106b:0163 | AMD              | Ellesmere [Radeon RX 470/480/570/... | 11    | amdgpu     | [EE288626F4](<All In One/Apple/iMac18/iMac18,3/85F2F89AFF57/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/EE288626F4>) |
| 1002:67ef | 106b:019f | AMD              | Baffin [Radeon RX 460/560D / Pro ... | 11    | amdgpu     | [0F3F45F8E9](<All In One/Apple/iMac19/iMac19,2/5322EAC8B99B/PARROT-5.2/6.0.0-12PARROT1-AMD64/X86_64/0F3F45F8E9>) |
| 10de:11a3 | 106b:010d | Nvidia           | GK104M [GeForce GTX 680MX]           | 11    | nouveau    | [6A8C52FAA7](<All In One/Apple/iMac13/iMac13,2/77F54E6C9FB5/DEBIAN-11/5.10.0-21-AMD64/X86_64/6A8C52FAA7>) |
| 1002:6660 | 1028:05db | AMD              | Sun XT [Radeon HD 8670A/8670M/869... | 10    | radeon     | [323E28FDED](<All In One/Dell/Inspiron/Inspiron 2350/07DCD03E083E/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/323E28FDED>) |
| 1002:6751 | 1028:0548 | AMD              | Turks [Radeon HD 7650A/7670A]        | 10    | radeon     | [6F705F4121](<All In One/Dell/Inspiron/Inspiron One 2330/0EA596C6EBB5/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/6F705F4121>) |
| 1002:67df | 106b:0161 | AMD              | Ellesmere [Radeon RX 470/480/570/... | 10    | amdgpu     | [19B2AE81FF](<All In One/Apple/iMac18/iMac18,3/0C2D99DF49CC/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/19B2AE81FF>) |
| 8086:1912 | 1028:06c5 | Intel            | HD Graphics 530                      | 10    | i915       | [5B29ED7213](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/BE925566CC9F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5B29ED7213>) |
| 8086:3185 | 1854:0308 | Intel            | GeminiLake [UHD Graphics 600]        | 10    | i915       | [EC912EFB6F](<All In One/LG Electronics/22V280/22V280-L.BJ31P1/925F8D37ECFF/FEDORA-37/6.0.12-300.FC37.X86_64/X86_64/EC912EFB6F>) |
| 8086:3e92 | 103c:84ee | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 10    | i915       | [79C81FCFB5](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-xa0xxx/172DC93717BB/ROSA-12.3/6.0.7.XM1-1.KLP-XANMOD-ROSA2021.1-X86_64/X86_64/79C81FCFB5>) |
| 8086:3ea0 | 17aa:3145 | Intel            | WhiskeyLake-U GT2 [UHD Graphics 620] | 10    | i915       | [FAEB46556E](<All In One/Lenovo/V540-24IWL/V540-24IWL AIO 10YS0031RU/886440AA02F6/KOMETA-P10/5.10.102-STD-DEF-ALT1/X86_64/FAEB46556E>) |
| 1002:9851 | 103c:8245 | AMD              | Mullins [Radeon R4/R5 Graphics]      | 9     | radeon     | [81F625006B](<All In One/Hewlett-Packard/24/24-g020/310803ED8E33/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/81F625006B>) |
| 10de:0dea | 17aa:365e | Nvidia           | GF108M [GeForce 610M]                | 9     | nouveau    | [4B37B09299](<All In One/Lenovo/C440/C440 10104/948D7D25173C/MANJARO-22.0.0/5.10.148-1-MANJARO/X86_64/4B37B09299>) |
| 10de:0df5 | 1028:0511 | Nvidia           | GF108M [GeForce GT 525M]             | 9     | nvidia     | [225E42D432](<All In One/Dell/Inspiron/Inspiron One 2320/D8B99273D539/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/225E42D432>) |
| 10de:0fe9 | 106b:011e | Nvidia           | GK107M [GeForce GT 750M Mac Edition] | 9     | nouveau    | [C53A69BD72](<All In One/Apple/iMac14/iMac14,3/CCC253970520/ARCH-ROLLING/6.2.12-ARCH1-1/X86_64/C53A69BD72>) |
| 10de:119e | 106b:0121 | Nvidia           | GK104M [GeForce GTX 780M Mac Edit... | 9     | nvidia     | [3C681075FB](<All In One/Apple/iMac14/iMac14,2/F570A992C7CF/UBUNTU-BUDGIE-22.10/5.19.0-35-GENERIC/X86_64/3C681075FB>) |

### Iommu (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15d1 | 1022:15d1 | AMD              | Raven/Raven2 IOMMU                   | 38    |            | [DC3ADE850C](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-df0xxx/149EB6B30B69/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/DC3ADE850C>) |
| 1022:1481 | 1022:1481 | AMD              | Starship/Matisse IOMMU               | 4     |            | [13A42307A4](<All In One/Acidanthera/iMacPro1/iMacPro1,1/CCEF88A1D848/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/13A42307A4>) |
| 1022:1631 | 1022:1631 | AMD              | Renoir/Cezanne IOMMU                 | 4     |            | [4160198447](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-dp0xxx/C4EA82C77997/UBUNTU-20.04/5.15.0-60-GENERIC/X86_64/4160198447>) |
| 1022:1631 | 103c:86ee | AMD              | Renoir/Cezanne IOMMU                 | 4     |            | [2632541785](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-d0xxx/CF27A731CFBC/ENDEAVOUROS-ROLLING/6.1.7-ARCH1-1/X86_64/2632541785>) |
| 1022:1631 | 17aa:371c | AMD              | Renoir/Cezanne IOMMU                 | 4     |            | [02248F5982](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 24ARE05 F0EW00GRSP/2AC57BE6BCD7/OPENMANDRIVA-23.01/6.1.4-DESKTOP-1OMV2301/X86_64/02248F5982>) |
| 1022:1631 | 17aa:3746 | AMD              | Renoir/Cezanne IOMMU                 | 4     |            | [EC07BB84CF](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 27ALC6 F0FY0055GE/634764CAF8D6/SIDUCTION-12/6.2.8-1-SIDUCTION-AMD64/X86_64/EC07BB84CF>) |
| 1022:1451 | 1028:07e4 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 3     |            | [CBAE954ECC](<All In One/Dell/Inspiron/Inspiron 27 7775/ACE5205CCA5D/NIXOS-22.11/5.15.86/X86_64/CBAE954ECC>) |
| 1022:1577 | 1028:07e3 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 3     |            | [87A4F1E989](<All In One/Dell/Inspiron/Inspiron 24 5475/44B04AE381C1/UBUNTU-18.04/5.4.0-89-GENERIC/X86_64/87A4F1E989>) |
| 1022:1577 | 1028:0854 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 3     |            | [1629350AA9](<All In One/Dell/Inspiron/Inspiron 3475 AIO/33D749C2D2FC/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/1629350AA9>) |
| 1022:1631 | 1028:0b83 | AMD              | Renoir/Cezanne IOMMU                 | 3     |            | [D7ED216BE7](<All In One/Dell/Inspiron/Inspiron 24 5415 All-in-One/FBE2C11F8067/ARCH-22.10/6.3.1-ARCH1-1/X86_64/D7ED216BE7>) |
| 1022:1631 | 103c:8924 | AMD              | Renoir/Cezanne IOMMU                 | 3     |            | [53F993BF5D](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One Desktop 24-ca0xxx/B50333765A75/LINUXMINT-21/6.0.0-060000-GENERIC/X86_64/53F993BF5D>) |
| 1022:1631 | 1043:1832 | AMD              | Renoir/Cezanne IOMMU                 | 3     |            | [F6285D1100](<All In One/ASUSTek Computer/ASUS/ASUS ZEN AIO M5401WUA_M5401WUA/525FB10EAB16/DEBIAN-UNSTABLE/6.2.9-4-LIQUORIX-AMD64/X86_64/F6285D1100>) |
| 1022:1577 | 17aa:36ec | AMD              | Family 15h (Models 60h-6fh) I/O M... | 2     |            | [2CFA2D338E](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 330-20AST F0D8001LUS/36DA6D8B2B0D/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/2CFA2D338E>) |
| 1022:1481 | 1043:87c0 | AMD              | Starship/Matisse IOMMU               | 1     |            | [577AD83B8F](<All In One/Acidanthera/iMacPro1/iMacPro1,1/6286842FEC0E/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/577AD83B8F>) |
| 1022:14b6 | 1022:14b6 | AMD              | Family 17h-19h IOMMU                 | 1     |            | [1AC75759CE](<All In One/GPD/G1618/G1618-04/62DB29AA1271/DEBIAN-12/6.1.0-7-AMD64/X86_64/1AC75759CE>) |
| 1022:1577 | 1028:0855 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 1     |            | [DACA9432F8](<All In One/Dell/Inspiron/Inspiron 3275 AIO/6D40C1FA2274/LINUXMINT-19.2/4.15.0-65-GENERIC/X86_64/DACA9432F8>) |
| 1022:1577 | 17aa:36c6 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 1     |            | [5DA9F63B49](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 310-20ASR F0CK001ERK/FC84FC5E58C9/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/5DA9F63B49>) |
| 1022:1631 | 103c:89dc | AMD              | Renoir/Cezanne IOMMU                 | 1     |            | [D8AFBB81F9](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One Desktop 27-ca1xxx/14CB272FDF67/LUBUNTU-22.10/5.19.0-35-GENERIC/X86_64/D8AFBB81F9>) |
| 1022:1631 | 1043:1a72 | AMD              | Renoir/Cezanne IOMMU                 | 1     |            | [E593179048](<All In One/ASUSTek Computer/ASUS/ASUS AIO M3400WUA_M3400WUA/C57F5A924964/ROSA-12.3/5.10.155-GENERIC-1ROSA2021.1-X86_64/X86_64/E593179048>) |
| 1022:1631 | 1043:87e1 | AMD              | Renoir/Cezanne IOMMU                 | 1     |            | [FCD01E22D7](<All In One/ASUSTek Computer/PRIME/PRIME B450M-A II/E71284EECA39/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/FCD01E22D7>) |
| 1022:1631 | 17aa:3734 | AMD              | Renoir/Cezanne IOMMU                 | 1     |            | [53462F848A](<All In One/Lenovo/Yoga/Yoga 27-ARH F0FN0002CP/61F8ED84D9C7/XUBUNTU-20.04/5.11.0-40-GENERIC/X86_64/53462F848A>) |
| 1022:1631 | 17aa:3744 | AMD              | Renoir/Cezanne IOMMU                 | 1     |            | [B3EDFBFEE7](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 24ALC6 F0G1002YUK/C0099F4B4E0C/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/B3EDFBFEE7>) |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:816c | 1025:1291 | Realtek Semic... | RTL8111xP IPMI interface             | 3     |            | [9949F21F98](<All In One/Acer/Veriton/Veriton Z4660G/D6F2FD870657/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/9949F21F98>) |
| 10ec:816c | 1025:1290 | Realtek Semic... | RTL8111xP IPMI interface             | 2     |            | [A27363041A](<All In One/Acer/Veriton/Veriton Z4860G/8955EDC1BE49/ENDLESS-3.9.1/5.8.0-14-GENERIC/X86_64/A27363041A>) |
| 10ec:816c | 10ec:0123 | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [2278A5C6EA](<All In One/Samsung Electronics/SUR/SUR40/9A8E67BB1389/DEBIAN-11/5.19.0-2-AMD64/X86_64/2278A5C6EA>) |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:816c | 1025:1071 | Realtek Semic... | RTL8111xP IPMI interface             | 2     |            | [651D569B66](<All In One/Acer/Veriton/Veriton Z4820G/A079770A155B/KOMETA-P10/5.10.109-STD-DEF-ALT1/X86_64/651D569B66>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10de:0a88 |           | Nvidia           | MCP79 Memory Controller              | 128   |            | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 10de:0a89 |           | Nvidia           | MCP79 Memory Controller              | 128   |            | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 10de:0a98 | 10de:cb79 | Nvidia           | MCP79 Memory Controller              | 128   |            | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 10de:0aa4 |           | Nvidia           | MCP79 Memory Controller              | 128   |            | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 89    |            | [EE288626F4](<All In One/Apple/iMac18/iMac18,3/85F2F89AFF57/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/EE288626F4>) |
| 8086:a36f |           | Intel            | Cannon Lake PCH Shared SRAM          | 49    |            | [0F3F45F8E9](<All In One/Apple/iMac19/iMac19,2/5322EAC8B99B/PARROT-5.2/6.0.0-12PARROT1-AMD64/X86_64/0F3F45F8E9>) |
| 8086:a36f | 8086:7270 | Intel            | Cannon Lake PCH Shared SRAM          | 37    |            | [8E1245836B](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/B6DE3C8A8AED/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/8E1245836B>) |
| 8086:a2a1 | 1019:a5a1 | Intel            | 200 Series/Z370 Chipset Family Po... | 22    |            | [63DBB9394E](<All In One/ICL/RAY/RAY S122.Mi/767FFC5AB7B5/ALT-8.4/5.10.83-STD-DEF-ALT0.C9F.2/X86_64/63DBB9394E>) |
| 8086:9d21 | 103c:84de | Intel            | Sunrise Point-LP PMC                 | 17    |            | [CDB6233482](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/13576610145B/DEBIAN-11/5.10.0-18-AMD64/X86_64/CDB6233482>) |
| 8086:a0ef |           | Intel            | Tiger Lake-LP Shared SRAM            | 17    |            | [C87417466C](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 27ITL6 F0FW00Q2RU/E4E2B81CA7F6/DEBIAN-11/5.10.0-21-AMD64/X86_64/C87417466C>) |
| 8086:34ef | 8086:7270 | Intel            | Ice Lake-LP DRAM Controller          | 14    |            | [A82A90955E](<All In One/Acer/Aspire/Aspire C27-962/563F493FD77F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/A82A90955E>) |
| 8086:9d21 | 1025:1287 | Intel            | Sunrise Point-LP PMC                 | 13    | intel_p... | [EB0191F969](<All In One/Acer/Aspire/Aspire C22-865/2C5B66C0839A/MANJARO/6.1.1-1-MANJARO/X86_64/EB0191F969>) |
| 8086:9d21 | 8086:9d21 | Intel            | Sunrise Point-LP PMC                 | 13    | intel_p... | [557E50987C](<All In One/ASUSTek Computer/ZN240/ZN240IC/A4EB8493DB43/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/557E50987C>) |
| 10de:0568 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] Memory Cont... | 11    |            | [E0B8F5D54B](<All In One/Acer/Aspire/Aspire Z3101/B30C614DB765/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/E0B8F5D54B>) |
| 10de:0751 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] Memory Cont... | 11    |            | [E0B8F5D54B](<All In One/Acer/Aspire/Aspire Z3101/B30C614DB765/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/E0B8F5D54B>) |
| 10de:0754 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] Memory Cont... | 11    |            | [E0B8F5D54B](<All In One/Acer/Aspire/Aspire Z3101/B30C614DB765/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/E0B8F5D54B>) |
| 8086:43ef |           | Intel            | Tiger Lake-H Shared SRAM             | 10    |            | [332429FC14](<All In One/Acidanthera/iMac20/iMac20,1/812DAF8F2884/ARCH-ROLLING/6.2.12-ZEN1-1-ZEN/X86_64/332429FC14>) |
| 8086:7aa7 |           | Intel            | Alder Lake-S PCH Shared SRAM         | 10    |            | [E734B33010](<All In One/Graviton/D12/D12i/E65E993A1E87/ALT-10.1/5.15.104-UN-DEF-ALT1/X86_64/E734B33010>) |
| 8086:9def | 17aa:3145 | Intel            | Cannon Point-LP Shared SRAM          | 10    |            | [FAEB46556E](<All In One/Lenovo/V540-24IWL/V540-24IWL AIO 10YS0031RU/886440AA02F6/KOMETA-P10/5.10.102-STD-DEF-ALT1/X86_64/FAEB46556E>) |
| 8086:a121 | 1028:06c5 | Intel            | 100 Series/C230 Series Chipset Fa... | 10    |            | [5B29ED7213](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/BE925566CC9F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5B29ED7213>) |
| 8086:06ef | 8086:7270 | Intel            | Comet Lake PCH Shared SRAM           | 9     |            | [88D774DF0D](<All In One/Acidanthera/iMac20/iMac20,1/C13BE88FDE86/DEBIAN-12/6.1.0-7-AMD64/X86_64/88D774DF0D>) |
| 8086:9d21 | 8086:7270 | Intel            | Sunrise Point-LP PMC                 | 9     |            | [426C7D7939](<All In One/Apple/iMac18/iMac18,1/61AC5215756C/XUBUNTU-22.04/5.19.0-35-GENERIC/X86_64/426C7D7939>) |
| 8086:a121 | 103c:2b3e | Intel            | 100 Series/C230 Series Chipset Fa... | 8     |            | [70F8CE05B6](<All In One/Hewlett-Packard/24/24-n000ny/C2F705DD30EA/UBUNTU-20.04/5.15.0-69-GENERIC/X86_64/70F8CE05B6>) |
| 8086:9d21 | 1028:0754 | Intel            | Sunrise Point-LP PMC                 | 7     |            | [348BC23246](<All In One/Dell/Inspiron/Inspiron 3464 AIO/00109263052E/ENDEAVOUROS-ROLLING/5.15.71-1-LTS/X86_64/348BC23246>) |
| 8086:9def | 8086:7270 | Intel            | Cannon Point-LP Shared SRAM          | 7     |            | [24ED481783](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_A6521FA/262E2C088492/RED-OS-7.3.2/5.15.72-1.EL7.3.X86_64/X86_64/24ED481783>) |
| 8086:a121 | 103c:81b7 | Intel            | 100 Series/C230 Series Chipset Fa... | 7     |            | [7B1F1044AE](<All In One/Hewlett-Packard/27/27-a154ng/BDD291411CF6/REBORNOS/5.19.2-ARCH1-1/X86_64/7B1F1044AE>) |
| 8086:a121 | 103c:82dc | Intel            | 100 Series/C230 Series Chipset Fa... | 7     |            | [4C1C2F908B](<All In One/Hewlett-Packard/27/27-a271ny/689111B5E631/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/4C1C2F908B>) |
| 8086:a2a1 | 1028:079c | Intel            | 200 Series/Z370 Chipset Family Po... | 7     |            | [1940C6417C](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/A9167F8393F4/DEBIAN-11/5.10.0-21-AMD64/X86_64/1940C6417C>) |
| 8086:34ef | 1025:1434 | Intel            | Ice Lake-LP DRAM Controller          | 6     |            | [7B4EEEBDBC](<All In One/Acer/Aspire/Aspire C24-963/E4A4E93BCF0A/RED-OS-7.3/5.15.87-1.EL7.3.X86_64/X86_64/7B4EEEBDBC>) |
| 8086:a121 | 8086:a121 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     |            | [BAC1E9869D](<All In One/ASUSTek Computer/V230/V230IC/388C8BB5ED5C/OPENMANDRIVA-4.90/5.18.12-DESKTOP-3OMV4090/X86_64/BAC1E9869D>) |
| 10de:0a88 | 1462:4570 | Nvidia           | MCP79 Memory Controller              | 5     |            | [71C47135FC](<All In One/MSI/MS-AA/MS-AA1511/7E1B74B959FB/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/71C47135FC>) |
| 10de:0a89 | 1462:4570 | Nvidia           | MCP79 Memory Controller              | 5     |            | [71C47135FC](<All In One/MSI/MS-AA/MS-AA1511/7E1B74B959FB/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/71C47135FC>) |
| 10de:0aa4 | 1462:4570 | Nvidia           | MCP79 Memory Controller              | 5     |            | [71C47135FC](<All In One/MSI/MS-AA/MS-AA1511/7E1B74B959FB/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/71C47135FC>) |
| 8086:9d21 | 103c:82dd | Intel            | Sunrise Point-LP PMC                 | 5     |            | [9A741FF95B](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/775B76A28FB4/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/9A741FF95B>) |
| 8086:a121 | 1025:1063 | Intel            | 100 Series/C230 Series Chipset Fa... | 5     |            | [03C59534F5](<All In One/Acer/Aspire/Aspire Z3-715/D5B0F6B5EA52/FEDORA-36/5.18.8-200.FSYNC.FC36.X86_64/X86_64/03C59534F5>) |
| 8086:a36f | 103c:83eb | Intel            | Cannon Lake PCH Shared SRAM          | 5     |            | [1011557C31](<All In One/Hewlett-Packard/ProOne/ProOne 440 G4 23.8-in NT AiO/EC8129DD680A/RED-OS-7.3/5.15.35-5.EL7.3.X86_64/X86_64/1011557C31>) |
| 8086:a36f | 103c:85a2 | Intel            | Cannon Lake PCH Shared SRAM          | 5     |            | [C9F6D95FB2](<All In One/Hewlett-Packard/ProOne/ProOne 440 G5 23.8-in All-in-One/3714C25A2744/UBUNTU-MATE-22.10/5.19.0-31-GENERIC/X86_64/C9F6D95FB2>) |
| 8086:9d21 | 1028:0852 | Intel            | Sunrise Point-LP PMC                 | 4     |            | [F373C43A01](<All In One/Dell/Inspiron/Inspiron 3477 AIO/6B758C37D517/POP!_OS-22.04/5.17.5-76051705-GENERIC/X86_64/F373C43A01>) |
| 8086:9d21 | 1043:12a1 | Intel            | Sunrise Point-LP PMC                 | 4     |            | [0ED5F3ECCD](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222UA/B404F454B226/BOSS-9/5.10.0-11-AMD64/X86_64/0ED5F3ECCD>) |
| 8086:9d21 | 17aa:3630 | Intel            | Sunrise Point-LP PMC                 | 4     |            | [C27DA0FAA9](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 300-23ISU F0BY00DMPB/0FB4A4AA4C0E/ENDEAVOUROS-ROLLING/5.15.44-1-LTS/X86_64/C27DA0FAA9>) |
| 8086:9d21 | 17aa:36dc | Intel            | Sunrise Point-LP PMC                 | 4     |            | [4A07474FA4](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-24IKU F0D2006BAR/1CD093E87B7E/MX-21/5.10.0-20-AMD64/X86_64/4A07474FA4>) |
| 8086:a0ef | 1043:1482 | Intel            | Tiger Lake-LP Shared SRAM            | 4     |            | [FFB4ED2207](<All In One/ASUSTek Computer/ASUS/ASUS Vivo AIO V241EA_V241EA/69C580FE0877/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/FFB4ED2207>) |
| 8086:a2a1 | 103c:829b | Intel            | 200 Series/Z370 Chipset Family Po... | 4     |            | [23122CBA32](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G3 23.8-in Non-Touch AiO/E6CDD7190196/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.3-1-DEFAULT/X86_64/23122CBA32>) |
| 8086:a36f | 17aa:36f4 | Intel            | Cannon Lake PCH Shared SRAM          | 4     |            | [C129F7C9B1](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-27ICB F0DE00EJRI/E74066EE0DE7/UBUNTUSTUDIO-22.04/5.15.0-47-LOWLATENCY/X86_64/C129F7C9B1>) |
| 8086:a3a1 | 103c:86f7 | Intel            | Cannon Lake PCH Power Management ... | 4     |            | [C6437188E6](<All In One/Hewlett-Packard/All-in-One/All-in-One 27-dp0xxx/1B38D1EFE767/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/C6437188E6>) |
| 8086:02ef | 1028:0953 | Intel            | Comet Lake PCH-LP Shared SRAM        | 3     |            | [EA8027E95B](<All In One/Dell/Inspiron/Inspiron 5490 AIO/DED288B166FA/UBUNTU-MATE-22.04/5.19.0-32-GENERIC/X86_64/EA8027E95B>) |
| 8086:02ef | 1028:0954 | Intel            | Comet Lake PCH-LP Shared SRAM        | 3     |            | [CA76B3A899](<All In One/Dell/Inspiron/Inspiron 7790 AIO/2F9AB0C8681A/UBUNTU-BUDGIE-21.10/5.13.0-35-GENERIC/X86_64/CA76B3A899>) |
| 8086:02ef | 17aa:370c | Intel            | Comet Lake PCH-LP Shared SRAM        | 3     |            | [AE16B78FA0](<All In One/Lenovo/IdeaCentre/IdeaCentre A340-24IWL F0E800PTRK/69EE34C2CE07/ROSA-12.3/6.0.7.XM1-1.KLP-XANMOD-ROSA2021.1-X86_64/X86_64/AE16B78FA0>) |
| 8086:02ef | 8086:7270 | Intel            | Comet Lake PCH-LP Shared SRAM        | 3     |            | [E541CD3043](<All In One/MSI/CML-U/CML-U PRO 24X 10M/6A9F598F2D57/KUBUNTU-22.04/5.15.0-56-GENERIC/X86_64/E541CD3043>) |
| 8086:4def |           | Intel            | Jasper Lake Shared SRAM Controller   | 3     |            | [4AF4017DA0](<All In One/Intel/N5095-AIO/N5095-AIO T1/F4CC94597FDD/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/4AF4017DA0>) |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1131:7231 | 1461:2a0f | Philips Semic... | SAA7231                              | 11    |            | [7A6B0E67F0](<All In One/Acer/Aspire/Aspire Z3751/5E8E30E2DE1C/ZORIN-16/5.15.0-67-GENERIC/X86_64/7A6B0E67F0>) |
| 1131:7231 | 1461:2b0f | Philips Semic... | SAA7231                              | 7     |            | [092F9C7F2B](<All In One/Dell/Inspiron/Inspiron One 2320/B0A3A3458D1D/LINUXMINT-21/5.15.0-48-GENERIC/X86_64/092F9C7F2B>) |
| 1022:15e2 | 1022:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 6     | snd_pci... | [1AC75759CE](<All In One/GPD/G1618/G1618-04/62DB29AA1271/DEBIAN-12/6.1.0-7-AMD64/X86_64/1AC75759CE>) |
| 1002:ac12 | 12ab:0003 | AMD              | Theater HD T507 (DVB-T) TV tuner/... | 5     |            | [8F25ED4108](<All In One/Lenovo/IdeaCentre/IdeaCentre A310 10056/1F51DDDCDF1C/LINUXMINT-19.3/5.4.0-77-GENERIC/X86_64/8F25ED4108>) |
| 1022:15e2 | 17aa:371c | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 4     | snd_pci... | [02248F5982](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 24ARE05 F0EW00GRSP/2AC57BE6BCD7/OPENMANDRIVA-23.01/6.1.4-DESKTOP-1OMV2301/X86_64/02248F5982>) |
| 1022:15e2 | 17aa:3746 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 4     | snd_pci... | [EC07BB84CF](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 27ALC6 F0FY0055GE/634764CAF8D6/SIDUCTION-12/6.2.8-1-SIDUCTION-AMD64/X86_64/EC07BB84CF>) |
| 1022:15e2 | 1043:1832 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 3     | snd_pci... | [F6285D1100](<All In One/ASUSTek Computer/ASUS/ASUS ZEN AIO M5401WUA_M5401WUA/525FB10EAB16/DEBIAN-UNSTABLE/6.2.9-4-LIQUORIX-AMD64/X86_64/F6285D1100>) |
| 1022:15e2 | 17aa:36f5 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 3     | snd_pci... | [EB38810FB8](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-24ARR F0DN006KGE/1D5E59C5CB5F/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/EB38810FB8>) |
| 1022:15e2 | 17aa:371d | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     | snd_pci... | [2BD3CDBC37](<All In One/Lenovo/AIO/AIO 3-22ADA05 F0EX003JRK/BA9C03EB4E8E/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/2BD3CDBC37>) |
| 10cf:2030 | 104d:9053 | Fujitsu Limited. | PIX                                  | 2     |            | [AFA509714D](<All In One/Sony/VGC-LN52/VGC-LN52JGB/54F15FF48E03/UBUNTU-20.04/5.8.0-54-GENERIC/X86_64/AFA509714D>) |
| 10cf:2030 | 104d:9062 | Fujitsu Limited. | PIX                                  | 2     |            | [71AE1045DA](<All In One/Sony/VPCL129/VPCL129FJ/ECBBF017B776/OPENMANDRIVA-4.90/5.18.12-DESKTOP-3OMV4090/X86_64/71AE1045DA>) |
| 10cf:2036 | 104d:906e | Fujitsu Limited. | DT-XXX                               | 2     |            | [2DEFAA2F88](<All In One/Sony/VPCJ118/VPCJ118FJ/356CC6106273/UBUNTU-20.04/5.15.0-43-GENERIC/X86_64/2DEFAA2F88>) |
| 1131:7231 | 1461:2b07 | Philips Semic... | SAA7231                              | 2     |            | [225E42D432](<All In One/Dell/Inspiron/Inspiron One 2320/D8B99273D539/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/225E42D432>) |
| 1745:3000 | 104d:9049 | ViXS Systems     | Colossus Encoder                     | 2     |            | [71AE1045DA](<All In One/Sony/VPCL129/VPCL129FJ/ECBBF017B776/OPENMANDRIVA-4.90/5.18.12-DESKTOP-3OMV4090/X86_64/71AE1045DA>) |
| 1002:ac12 | 1002:b539 | AMD              | Theater HD T507 (DVB-T) TV tuner/... | 1     |            | [DD5E0979B0](<All In One/Lenovo/IdeaCentre/IdeaCentre B300 10051/CECF63D85737/ROSA-2014.1/3.14.44-NRJ-DESKTOP-2ROSA-X86_64/X86_64/DD5E0979B0>) |
| 1022:15e2 | 1043:1a72 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     | snd_pci... | [E593179048](<All In One/ASUSTek Computer/ASUS/ASUS AIO M3400WUA_M3400WUA/C57F5A924964/ROSA-12.3/5.10.155-GENERIC-1ROSA2021.1-X86_64/X86_64/E593179048>) |
| 1022:15e2 | 17aa:3734 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     | snd_pci... | [53462F848A](<All In One/Lenovo/Yoga/Yoga 27-ARH F0FN0002CP/61F8ED84D9C7/XUBUNTU-20.04/5.11.0-40-GENERIC/X86_64/53462F848A>) |
| 1022:15e2 | 17aa:3744 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     | snd_pci... | [B3EDFBFEE7](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 24ALC6 F0G1002YUK/C0099F4B4E0C/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/B3EDFBFEE7>) |
| 1131:7160 | 1461:2155 | Philips Semic... | SAA7160                              | 1     |            | [27E7D42D53](<All In One/Lenovo/Others/Others/18DB28A21724/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/27E7D42D53>) |
| 1745:3000 | 1033:895c | ViXS Systems     | Colossus Encoder                     | 1     |            | [6F4A2D24C1](<All In One/NEC Computers/PC-VW770/PC-VW770CS6B/CD4FBB5FF80F/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/6F4A2D24C1>) |
| 1745:3000 | 1bcf:a023 | ViXS Systems     | Colossus Encoder                     | 1     |            | [1494683BB9](<All In One/NEC Computers/PC-VN770/PC-VN770DS3ER/18CEF0AA43DB/UBUNTU-20.04/5.8.0-48-GENERIC/X86_64/1494683BB9>) |
| 1745:5000 | 17aa:6034 | ViXS Systems     | PureTV-U ISDB-T Tuner                | 1     |            | [6F613E9791](<All In One/NEC Computers/PC-VN770/PC-VN770MSW/3A3ABC9E5BB2/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/6F613E9791>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14e4:1686 | 14e4:1686 | Broadcom         | NetXtreme BCM57766 Gigabit Ethern... | 308   | tg3        | [C8C9C1E591](<All In One/Apple/iMac13/iMac13,1/ED988FB747CF/DEBIAN-11/5.10.0-21-AMD64/X86_64/C8C9C1E591>) |
| 14e4:16b4 | 14e4:16b4 | Broadcom         | NetXtreme BCM57765 Gigabit Ethern... | 170   | tg3        | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 11ab:436a | 11ab:00ba | Marvell Techn... | 88E8058 PCI-E Gigabit Ethernet Co... | 155   | sky2       | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 10de:0ab0 | 10de:cb79 | Nvidia           | MCP79 Ethernet                       | 128   | forcedeth  | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 14e4:1684 | 14e4:1684 | Broadcom         | NetXtreme BCM5764M Gigabit Ethern... | 86    | tg3        | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 52    | r8169      | [38C2A94BAA](<All In One/Positivo/C464/C464A-21/1A925F871EA8/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/38C2A94BAA>) |
| 10ec:8168 | 1043:205f | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 31    | r8169      | [F6285D1100](<All In One/ASUSTek Computer/ASUS/ASUS ZEN AIO M5401WUA_M5401WUA/525FB10EAB16/DEBIAN-UNSTABLE/6.2.9-4-LIQUORIX-AMD64/X86_64/F6285D1100>) |
| 11ab:4362 | 11ab:5321 | Marvell Techn... | 88E8053 PCI-E Gigabit Ethernet Co... | 27    | sky2       | [C7444AC7F0](<All In One/Apple/iMac5/iMac5,1/104264B0BD86/XUBUNTU-22.04/5.15.0-70-GENERIC/X86_64/C7444AC7F0>) |
| 10ec:8168 | 1025:8000 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 26    | r8169      | [2E34D8A2CC](<All In One/Acer/Aspire/Aspire Z5770/1DB05CC1D29C/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/2E34D8A2CC>) |
| 10ec:8168 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 23    | r8169      | [3796D857B1](<All In One/Multilaser/UB82/UB82X/0D4FF609D328/MANJARO/6.2.12-1-MANJARO/X86_64/3796D857B1>) |
| 10ec:8168 | 1b50:4606 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 22    | r8169      | [55CAB5C7FA](<All In One/Medion/E23201/E23201 MD61575/ADEBFF0ED21D/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/55CAB5C7FA>) |
| 14e4:1686 | 106b:0110 | Broadcom         | NetXtreme BCM57766 Gigabit Ethern... | 18    | tg3        | [6A8C52FAA7](<All In One/Apple/iMac13/iMac13,2/77F54E6C9FB5/DEBIAN-11/5.10.0-21-AMD64/X86_64/6A8C52FAA7>) |
| 10ec:8168 | 103c:8245 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 17    | r8169      | [81F625006B](<All In One/Hewlett-Packard/24/24-g020/310803ED8E33/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/81F625006B>) |
| 10ec:8168 | 103c:84de | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 17    | r8169      | [CDB6233482](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/13576610145B/DEBIAN-11/5.10.0-18-AMD64/X86_64/CDB6233482>) |
| 10ec:8168 | 17aa:365e | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 16    | r8169      | [D75E472005](<All In One/Lenovo/C440/C440 10104/983B023892A1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/D75E472005>) |
| 8086:153a | 1028:05a7 | Intel            | Ethernet Connection I217-LM          | 15    | e1000e     | [757AE6AA73](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/099C9C0A02A0/DEBIAN-11/5.10.0-20-AMD64/X86_64/757AE6AA73>) |
| 10ec:8168 | 1028:0511 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 14    | r8169      | [225E42D432](<All In One/Dell/Inspiron/Inspiron One 2320/D8B99273D539/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/225E42D432>) |
| 10ec:8168 | 103c:84ee | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 14    | r8169      | [8E1245836B](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/B6DE3C8A8AED/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/8E1245836B>) |
| 10ec:8168 | 1b50:4607 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 14    | r8169      | [A82A90955E](<All In One/Acer/Aspire/Aspire C27-962/563F493FD77F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/A82A90955E>) |
| 10ec:8168 | 1025:1287 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 13    | r8169      | [EB0191F969](<All In One/Acer/Aspire/Aspire C22-865/2C5B66C0839A/MANJARO/6.1.1-1-MANJARO/X86_64/EB0191F969>) |
| 10ec:8168 | 1028:05db | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 13    | r8169      | [323E28FDED](<All In One/Dell/Inspiron/Inspiron 2350/07DCD03E083E/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/323E28FDED>) |
| 10ec:8168 | 103c:81bb | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 13    | r8169      | [8C50716D55](<All In One/Hewlett-Packard/20/20-c012a/A9551DF58B53/LINUXMINT-20.3/5.4.0-148-GENERIC/X86_64/8C50716D55>) |
| 10ec:8168 | 103c:8381 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 13    | r8169      | [6745FD4BAC](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/EF305E495BCA/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/6745FD4BAC>) |
| 10ec:8168 | 103c:8430 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 13    | r8169      | [B813F95C6F](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/3A989707384A/ZORIN-16/5.15.0-69-GENERIC/X86_64/B813F95C6F>) |
| 1969:1091 | 1028:0548 | Qualcomm Atheros | AR8161 Gigabit Ethernet              | 13    | alx        | [22CBD67F5D](<All In One/Dell/Inspiron/Inspiron One 2330/C959D85DE508/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/22CBD67F5D>) |
| 10ec:8168 | 1025:0266 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 12    | r8169      | [8A9EDF5A44](<All In One/Acer/Aspire/Aspire Z5600/021BA2DCCB15/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/8A9EDF5A44>) |
| 10ec:8168 | 103c:2ac5 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 12    | r8169      | [B32F35A4B1](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/C0BF0A16B6D4/FEDORA-36/5.18.19-200.FC36.X86_64/X86_64/B32F35A4B1>) |
| 10de:0760 | 1025:8000 | Nvidia           | MCP77 Ethernet                       | 11    | forcedeth  | [E0B8F5D54B](<All In One/Acer/Aspire/Aspire Z3101/B30C614DB765/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/E0B8F5D54B>) |
| 10ec:8168 | 103c:86f3 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 11    | r8169      | [DC3ADE850C](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-df0xxx/149EB6B30B69/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/DC3ADE850C>) |
| 10ec:8168 | 1043:200f | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 11    | r8169      | [2F11E3E79D](<All In One/ASUSTek Computer/Vivo/Vivo AIO 16 V161GA_V161GA/733A41D44410/ENDLESS-4.0.14/5.11.0-35-GENERIC/X86_64/2F11E3E79D>) |
| 10ec:8168 | 1043:858f | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 11    | r8169      | [557E50987C](<All In One/ASUSTek Computer/ZN240/ZN240IC/A4EB8493DB43/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/557E50987C>) |
| 10ec:8168 | 103c:2b3b | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 10    | r8169      | [CB25C51987](<All In One/Hewlett-Packard/23/23-r155la/F1B498CB86AC/ZORIN-16/5.15.0-60-GENERIC/X86_64/CB25C51987>) |
| 10ec:8168 | 17aa:3145 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 10    | r8169      | [FAEB46556E](<All In One/Lenovo/V540-24IWL/V540-24IWL AIO 10YS0031RU/886440AA02F6/KOMETA-P10/5.10.102-STD-DEF-ALT1/X86_64/FAEB46556E>) |
| 10ec:8168 | 1854:0308 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 10    | r8169      | [EC912EFB6F](<All In One/LG Electronics/22V280/22V280-L.BJ31P1/925F8D37ECFF/FEDORA-37/6.0.12-300.FC37.X86_64/X86_64/EC912EFB6F>) |
| 8086:15b7 | 1028:06c5 | Intel            | Ethernet Connection (2) I219-LM      | 10    | e1000e     | [5B29ED7213](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/BE925566CC9F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5B29ED7213>) |
| 10ec:8136 | 10ec:8136 | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 9     | r8169      | [8A25091E19](<All In One/Dell/Inspiron/Inspiron 20 Model 3043/302C3227E59B/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/8A25091E19>) |
| 10ec:8168 | 1043:84cd | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 9     | r8169      | [344A27F223](<All In One/ASUSTek Computer/ET2013/ET2013I/BBF580F35D8F/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/344A27F223>) |
| 10ec:8168 | 144d:b091 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 9     | r8169      | [DD513D338C](<All In One/Samsung Electronics/DP700/DP700A3D-DM700A3D-DB701A3D-DP700A7D/F34D6AA53F0D/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/DD513D338C>) |
| 10ec:8168 | 17aa:366c | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 9     | r8169      | [55C11B6B87](<All In One/Lenovo/C540/C540 10110/D5261210E56A/OPENMANDRIVA-4.50/5.12.4-DESKTOP-1OMV4050/X86_64/55C11B6B87>) |
| 8086:153a | 1028:0626 | Intel            | Ethernet Connection I217-LM          | 9     | e1000e     | [9348834E54](<All In One/Dell/Inspiron/Inspiron 23 Model 5348/5251BCB7D469/FEDORA-37/6.2.9-200.FC37.X86_64/X86_64/9348834E54>) |
| 10ec:8168 | 103c:2b3e | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 8     | r8169      | [70F8CE05B6](<All In One/Hewlett-Packard/24/24-n000ny/C2F705DD30EA/UBUNTU-20.04/5.15.0-69-GENERIC/X86_64/70F8CE05B6>) |
| 10ec:8168 | 1043:8432 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 8     | r8169      | [C65E5F04D0](<All In One/ASUSTek Computer/ET2400/ET2400IN-1G/34D8B01527FB/KUBUNTU-22.04/5.15.0-60-GENERIC/X86_64/C65E5F04D0>) |
| 10ec:8168 | 17aa:36ab | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 8     | r8169      | [4891D8306B](<All In One/Lenovo/C40-05/C40-05 F0B5004EUK/84C5083CE2E4/LINUXMINT-20.2/5.4.0-139-GENERIC/X86_64/4891D8306B>) |
| 8086:1a1d | 8086:0000 | Intel            | Ethernet Connection (17) I219-V      | 8     | e1000e     | [E734B33010](<All In One/Graviton/D12/D12i/E65E993A1E87/ALT-10.1/5.15.104-UN-DEF-ALT1/X86_64/E734B33010>) |
| 10ec:8136 | 1028:0754 | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 7     | r8169      | [348BC23246](<All In One/Dell/Inspiron/Inspiron 3464 AIO/00109263052E/ENDEAVOUROS-ROLLING/5.15.71-1-LTS/X86_64/348BC23246>) |
| 10ec:8168 | 1019:8117 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 7     | r8169      | [63DBB9394E](<All In One/ICL/RAY/RAY S122.Mi/767FFC5AB7B5/ALT-8.4/5.10.83-STD-DEF-ALT0.C9F.2/X86_64/63DBB9394E>) |
| 10ec:8168 | 1028:0479 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 7     | r8169      | [E0FD42AC99](<All In One/Dell/Inspiron/Inspiron One 2305/CCF514D6F2CB/UBUNTU-22.10/5.19.0-31-GENERIC/X86_64/E0FD42AC99>) |
| 10ec:8168 | 103c:81b7 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 7     | r8169      | [7B1F1044AE](<All In One/Hewlett-Packard/27/27-a154ng/BDD291411CF6/REBORNOS/5.19.2-ARCH1-1/X86_64/7B1F1044AE>) |
| 10ec:8168 | 103c:82dc | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 7     | r8169      | [4C1C2F908B](<All In One/Hewlett-Packard/27/27-a271ny/689111B5E631/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/4C1C2F908B>) |
| 10ec:8168 | 104d:907e | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 7     | r8169      | [0451CAEB29](<All In One/Sony/VPCL212/VPCL212FX/01EE677E7F92/UBUNTU-21.10/5.13.0-22-GENERIC/X86_64/0451CAEB29>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 168c:0030 | 106b:009a | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 168   | ath9k      | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 168c:002a | 106b:008f | Qualcomm Atheros | AR928X Wireless Network Adapter (... | 154   | ath9k      | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 14e4:43a0 | 106b:0111 | Broadcom         | BCM4360 802.11ac Wireless Network... | 97    | wl         | [6976F884E6](<All In One/Apple/iMac14/iMac14,4/6E7600BFDA83/LUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6976F884E6>) |
| 10ec:c821 | 103c:831a | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 90    | rtl8821ce  | [DC3ADE850C](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-df0xxx/149EB6B30B69/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/DC3ADE850C>) |
| 14e4:4328 | 106b:008c | Broadcom         | BCM4321 802.11a/b/g/n                | 83    | wl         | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 14e4:4328 | 106b:0088 | Broadcom         | BCM4321 802.11a/b/g/n                | 72    | wl         | [B80D03BE6D](<All In One/Apple/iMac7/iMac7,1/0FB0AF60FB29/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/B80D03BE6D>) |
| 8086:24fb | 8086:2110 | Intel            | Dual Band Wireless-AC 3168NGW [St... | 66    | iwlwifi    | [55CAB5C7FA](<All In One/Medion/E23201/E23201 MD61575/ADEBFF0ED21D/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/55CAB5C7FA>) |
| 14e4:432b | 106b:008e | Broadcom         | BCM4322 802.11a/b/g/n Wireless LA... | 60    | wl         | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 14e4:4464 | 106b:07bf | Broadcom         | BCM4364 802.11ac Wireless Network... | 51    | brcmfmac   | [0F3F45F8E9](<All In One/Apple/iMac19/iMac19,2/5322EAC8B99B/PARROT-5.2/6.0.0-12PARROT1-AMD64/X86_64/0F3F45F8E9>) |
| 14e4:4331 | 106b:00f4 | Broadcom Limited | BCM4331 802.11a/b/g/n                | 49    | wl         | [C8C9C1E591](<All In One/Apple/iMac13/iMac13,1/ED988FB747CF/DEBIAN-11/5.10.0-21-AMD64/X86_64/C8C9C1E591>) |
| 10ec:b723 | 103c:81c1 | Realtek Semic... | RTL8723BE PCIe Wireless Network A... | 38    | rtl8723be  | [8C50716D55](<All In One/Hewlett-Packard/20/20-c012a/A9551DF58B53/LINUXMINT-20.3/5.4.0-148-GENERIC/X86_64/8C50716D55>) |
| 14e4:43ba | 106b:016e | Broadcom         | BCM43602 802.11ac Wireless LAN SoC   | 34    | brcmfmac   | [3F40AAB3D2](<All In One/Apple/iMac18/iMac18,2/87B5E6EFECC5/LINUXMINT-21.1/5.17.0-1027-OEM/X86_64/3F40AAB3D2>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 32    | iwlwifi    | [70F8CE05B6](<All In One/Hewlett-Packard/24/24-n000ny/C2F705DD30EA/UBUNTU-20.04/5.15.0-69-GENERIC/X86_64/70F8CE05B6>) |
| 10ec:c821 | 17aa:c024 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 30    | rtw88_8... | [01458C55A9](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-24IKL F0D1009MRI/71B1EDB2A2DC/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/01458C55A9>) |
| 14e4:43ba | 106b:016f | Broadcom         | BCM43602 802.11ac Wireless LAN SoC   | 29    | brcmfmac   | [EE288626F4](<All In One/Apple/iMac18/iMac18,3/85F2F89AFF57/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/EE288626F4>) |
| 168c:0042 | 1a3b:2231 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 27    | ath10k_pci | [557E50987C](<All In One/ASUSTek Computer/ZN240/ZN240IC/A4EB8493DB43/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/557E50987C>) |
| 8086:3166 | 8086:4210 | Intel            | Dual Band Wireless-AC 3165 Plus B... | 27    | iwlwifi    | [8CF49B59A5](<All In One/Lenovo/V130-20IGM/V130-20IGM AIO 10RX004PSP/516826CB41E7/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/8CF49B59A5>) |
| 10ec:b822 | 103c:831b | Realtek Semic... | RTL8822BE 802.11a/b/g/n/ac WiFi a... | 26    | rtw88_8... | [8E1245836B](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/B6DE3C8A8AED/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/8E1245836B>) |
| 14e4:43ba | 106b:014a | Broadcom         | BCM43602 802.11ac Wireless LAN SoC   | 26    | brcmfmac   | [F1227EA669](<All In One/Apple/iMac17/iMac17,1/F277E8B7B5D8/UBUNTU-22.04/6.2.12-060212-GENERIC/X86_64/F1227EA669>) |
| 10ec:8179 | 17aa:0179 | Realtek Semic... | RTL8188EE Wireless Network Adapter   | 25    | rtl8188ee  | [A079D28341](<All In One/Lenovo/C560/C560 10150/6C9E3A129538/LINUXMINT-21.1/5.15.0-58-GENERIC/X86_64/A079D28341>) |
| 1814:3090 | 11ad:6622 | Ralink           | RT3090 Wireless 802.11n 1T/1R PCIe   | 25    | rt2800pci  | [2E34D8A2CC](<All In One/Acer/Aspire/Aspire Z5770/1DB05CC1D29C/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/2E34D8A2CC>) |
| 168c:0042 | 17aa:0901 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 24    | ath10k_pci | [5D5EB8D675](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 310-20IAP F0CL0014LD/4155E31B2EFA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/5D5EB8D675>) |
| 8086:3165 | 8086:4010 | Intel            | Wireless 3165                        | 24    | iwlwifi    | [A61FFC94F5](<All In One/ICL/RAY/RAY Si105.Mi/F9B3F6AA07E6/MOS-10/5.10.136-STD-DEF-ALT1/X86_64/A61FFC94F5>) |
| 10ec:8176 | 10ec:8176 | Realtek Semic... | RTL8188CE 802.11b/g/n WiFi Adapter   | 23    | rtl8192ce  | [55C11B6B87](<All In One/Lenovo/C540/C540 10110/D5261210E56A/OPENMANDRIVA-4.50/5.12.4-DESKTOP-1OMV4050/X86_64/55C11B6B87>) |
| 168c:0034 | 11ad:6621 | Qualcomm Atheros | AR9462 Wireless Network Adapter      | 22    | ath9k      | [EA620E0681](<All In One/Acer/Aspire/Aspire Z3-600/BD66BD02AA7B/LINUX-LITE-6.4/5.15.0-71-GENERIC/X86_64/EA620E0681>) |
| 8086:08b3 | 8086:8070 | Intel            | Wireless 3160                        | 22    | iwlwifi    | [5F73A9E985](<All In One/LG Electronics/24V550/24V550-G.BJ31P1/8316E85EE90C/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/5F73A9E985>) |
| 168c:0036 | 1028:020e | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 21    | ath9k      | [9348834E54](<All In One/Dell/Inspiron/Inspiron 23 Model 5348/5251BCB7D469/FEDORA-37/6.2.9-200.FC37.X86_64/X86_64/9348834E54>) |
| 8086:2723 | 8086:0084 | Intel            | Wi-Fi 6 AX200                        | 21    | iwlwifi    | [332429FC14](<All In One/Acidanthera/iMac20/iMac20,1/812DAF8F2884/ARCH-ROLLING/6.2.12-ZEN1-1-ZEN/X86_64/332429FC14>) |
| 168c:0032 | 17aa:3118 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 19    | ath9k      | [057EEED322](<All In One/Lenovo/IdeaCentre/IdeaCentre B540 10099/372D40F76422/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/057EEED322>) |
| 14e4:4328 | 106b:0087 | Broadcom Limited | BCM4321 802.11a/b/g/n                | 18    | wl         | [C7444AC7F0](<All In One/Apple/iMac5/iMac5,1/104264B0BD86/XUBUNTU-22.04/5.15.0-70-GENERIC/X86_64/C7444AC7F0>) |
| 14e4:43ba | 106b:0156 | Broadcom         | BCM43602 802.11ac Wireless LAN SoC   | 18    | brcmfmac   | [570077AA64](<All In One/Apple/iMac16/iMac16,2/2D4E89D37302/ZORIN-16/5.15.0-69-GENERIC/X86_64/570077AA64>) |
| 168c:0036 | 1028:020c | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 18    | ath9k      | [8A25091E19](<All In One/Dell/Inspiron/Inspiron 20 Model 3043/302C3227E59B/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/8A25091E19>) |
| 168c:0042 | 11ad:08a6 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 18    | ath10k_pci | [7B4EEEBDBC](<All In One/Acer/Aspire/Aspire C24-963/E4A4E93BCF0A/RED-OS-7.3/5.15.87-1.EL7.3.X86_64/X86_64/7B4EEEBDBC>) |
| 168c:002b | 1a3b:1089 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 16    | ath9k      | [1775D6A140](<All In One/ASUSTek Computer/ET2411/ET2411_W8/55B530902FB8/LINUXMINT-21/5.15.0-50-GENERIC/X86_64/1775D6A140>) |
| 8086:9df0 | 8086:0034 | Intel            | Cannon Point-LP CNVi [Wireless-AC]   | 16    | iwlwifi    | [FAEB46556E](<All In One/Lenovo/V540-24IWL/V540-24IWL AIO 10YS0031RU/886440AA02F6/KOMETA-P10/5.10.102-STD-DEF-ALT1/X86_64/FAEB46556E>) |
| 168c:0032 | 103c:1838 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 15    | ath9k      | [2EEC2836C7](<All In One/Hewlett-Packard/23/23-p100br/884153A84576/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/2EEC2836C7>) |
| 8086:a370 | 8086:0034 | Intel            | Cannon Lake PCH CNVi WiFi            | 15    | iwlwifi    | [C9F6D95FB2](<All In One/Hewlett-Packard/ProOne/ProOne 440 G5 23.8-in All-in-One/3714C25A2744/UBUNTU-MATE-22.10/5.19.0-31-GENERIC/X86_64/C9F6D95FB2>) |
| 168c:002b | 105b:e017 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 14    | ath9k      | [57E0224FFD](<All In One/Sony/VPCL13/VPCL13M1R/82175A598A60/RELD-7.9/5.15.33-1.RES7.X86_64/X86_64/57E0224FFD>) |
| 168c:0036 | 17aa:3026 | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 14    | ath9k      | [4CC2E8CADD](<All In One/Lenovo/IdeaCentre/IdeaCentre B550 10135/0A3ACDFA18A3/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/4CC2E8CADD>) |
| 10ec:c822 | 103c:85f7 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 13    | rtw88_8... | [E86753F364](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-d0xxx/C8F5FD68E798/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/E86753F364>) |
| 168c:0032 | 1028:0209 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 13    | ath9k      | [22CBD67F5D](<All In One/Dell/Inspiron/Inspiron One 2330/C959D85DE508/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/22CBD67F5D>) |
| 14e4:43a0 | 106b:0142 | Broadcom         | BCM4360 802.11ac Wireless Network... | 12    | wl         | [0CFAF0934D](<All In One/Apple/iMac15/iMac15,1/2D28A46CFADB/KUBUNTU-22.10/5.19.0-35-GENERIC/X86_64/0CFAF0934D>) |
| 14e4:4727 | 1028:0010 | Broadcom         | BCM4313 802.11bgn Wireless Networ... | 12    | wl         | [EB106FA5D3](<All In One/Dell/Inspiron/Inspiron One 2310/E46F3B774446/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/EB106FA5D3>) |
| 168c:002a | 105b:e007 | Qualcomm Atheros | AR928X Wireless Network Adapter (... | 12    | ath9k      | [C5D91EE042](<All In One/Sony/VPCL116/VPCL116FX/8B44AA80F3CD/UBUNTU-20.04/5.4.0-144-GENERIC/X86_64/C5D91EE042>) |
| 10ec:8179 | 1a3b:1f38 | Realtek Semic... | RTL8188EE Wireless Network Adapter   | 11    | rtl8188ee  | [8184754BDE](<All In One/Positivo/DC8/DC8BT11/F752C6629913/UBUNTU-22.04/5.15.0-39-GENERIC/X86_64/8184754BDE>) |
| 14e4:4312 | 106b:0089 | Broadcom         | BCM4311 802.11a/b/g                  | 11    | ssb        | [FE5CFBCD29](<All In One/Apple/iMac5/iMac5,2/1D9C8744DFA0/MANJARO/5.15.102-1-MANJARO/X86_64/FE5CFBCD29>) |
| 168c:0036 | 11ad:0642 | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 11    | ath9k      | [FF4762D139](<All In One/Acer/Aspire/Aspire ZC-606/A2FBE9AD3965/KDE-NEON-22.04/5.15.0-57-GENERIC/X86_64/FF4762D139>) |
| 168c:0042 | 1028:1810 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 11    | ath10k_pci | [1629350AA9](<All In One/Dell/Inspiron/Inspiron 3475 AIO/33D749C2D2FC/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/1629350AA9>) |
| 1814:5390 | 1814:f051 | Ralink           | RT5390 Wireless 802.11n 1T/1R PCIe   | 11    | rt2800pci  | [DF20701C5E](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/2B14E403FA28/DEBIAN-10/5.10.0-0.BPO.3-AMD64/X86_64/DF20701C5E>) |
| 8086:24f3 | 8086:0050 | Intel            | Wireless 8260                        | 11    | iwlwifi    | [40C3CEE77A](<All In One/Dell/Precision/Precision 5720 AIO/64251E8FEE77/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/40C3CEE77A>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1502 | 1028:0543 | Intel            | 82579LM Gigabit Network Connectio... | 13    | e1000e     | [00CB2D66A8](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/42A1DEC89484/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/00CB2D66A8>) |
| 8086:10ce | 104d:9060 | Intel            | 82567V-2 Gigabit Network Connection  | 10    | e1000e     | [57E0224FFD](<All In One/Sony/VPCL13/VPCL13M1R/82175A598A60/RELD-7.9/5.15.33-1.RES7.X86_64/X86_64/57E0224FFD>) |
| 8086:10ef | 17aa:306a | Intel            | 82578DM Gigabit Network Connection   | 8     | e1000e     | [ED812A8A26](<All In One/Lenovo/ThinkCentre/ThinkCentre M90z 5205W5Q/2D0BC11CA89A/LINUXMINT-21.1/5.15.0-58-GENERIC/X86_64/ED812A8A26>) |
| 8086:10de | 103c:1489 | Intel            | 82567LM-3 Gigabit Network Connection | 6     | e1000e     | [EBD3760355](<All In One/Hewlett-Packard/Compaq/Compaq 6000 Pro AiO Business PC/F6BD16E86080/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/EBD3760355>) |
| 8086:10f0 | 1025:8000 | Intel            | 82578DC Gigabit Network Connection   | 5     | e1000e     | [83A5F64B3F](<All In One/Gateway/ZX/ZX6900/AE040A272759/FEDORA-35/5.18.16-100.FC35.X86_64/X86_64/83A5F64B3F>) |
| 8086:1502 | 103c:3395 | Intel            | 82579LM Gigabit Network Connectio... | 5     | e1000e     | [DAEDB871F5](<All In One/Hewlett-Packard/Compaq/Compaq 8200 Elite AiO Business PC/AF5919835808/LINUXMINT-20.3/5.15.0-56-GENERIC/X86_64/DAEDB871F5>) |
| 8086:1503 | 1025:8000 | Intel            | 82579V Gigabit Network Connection    | 5     | e1000e     | [03AA683A29](<All In One/Gateway/ZX/ZX6961/6D42C8D36EBE/LINUXMINT-21.1/5.15.0-60-GENERIC/X86_64/03AA683A29>) |
| 8086:10ce | 104d:9044 | Intel            | 82567V-2 Gigabit Network Connection  | 4     | e1000e     | [3ED1AD79E4](<All In One/Sony/VGC-JS54/VGC-JS54FB_W/1013B0577913/LINUX-LITE-6.0/5.16.9/X86_64/3ED1AD79E4>) |
| 8086:10fe | 17aa:3610 | Intel            | 82552 10/100 Network Connection      | 4     | e100       | [F5E3B18B7B](<All In One/Lenovo/C/C200/E2BB4B1443B8/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/F5E3B18B7B>) |
| 8086:10ce | 1025:048f | Intel            | 82567V-2 Gigabit Network Connection  | 3     | e1000e     | [6FDF5D94D7](<All In One/Acer/Aspire/Aspire Z3730/91F9AA1A6170/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/6FDF5D94D7>) |
| 8086:1502 | 8086:0000 | Intel            | 82579LM Gigabit Network Connectio... | 3     | e1000e     | [4E2FFC0DB7](<All In One/InFocus/INF/INF5520/89A8A2E44A06/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/4E2FFC0DB7>) |
| 8086:10ce | 104d:9043 | Intel            | 82567V-2 Gigabit Network Connection  | 2     | e1000e     | [AFA509714D](<All In One/Sony/VGC-LN52/VGC-LN52JGB/54F15FF48E03/UBUNTU-20.04/5.8.0-54-GENERIC/X86_64/AFA509714D>) |
| 8086:1539 | 1043:85f0 | Intel            | I211 Gigabit Network Connection      | 2     | igb        | [577AD83B8F](<All In One/Acidanthera/iMacPro1/iMacPro1,1/6286842FEC0E/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/577AD83B8F>) |
| 8086:1539 | 1458:e000 | Intel            | I211 Gigabit Network Connection      | 2     | igb        | [70BD257F2C](<All In One/Acidanthera/iMac18/iMac18,3/5F24E52E7730/LINUXMINT-21.1/5.15.0-58-GENERIC/X86_64/70BD257F2C>) |
| 10ec:8125 | 10ec:0123 | Realtek Semic... | RTL8125 2.5GbE Controller            | 1     | r8169      | [61E26A269D](<All In One/Teclast/H610-AIO/H610-AIO T1/E1558131F3BD/ROSA-12.2/5.10.118-GENERIC-2ROSA2021.1-X86_64/X86_64/61E26A269D>) |
| 10ec:8168 | ffff:ffff | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | r8169      | [B5DBE70538](<All In One/Lenovo/V50a-24IMB/V50a-24IMB 11FJ0026RU/3131AC26568F/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/B5DBE70538>) |
| 8086:10d3 | 8086:0000 | Intel            | 82574L Gigabit Network Connection    | 1     | e1000e     | [4E2FFC0DB7](<All In One/InFocus/INF/INF5520/89A8A2E44A06/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/4E2FFC0DB7>) |
| 8086:10eb | 17aa:3608 | Intel            | 82577LC Gigabit Network Connection   | 1     | e1000e     | [69574214D7](<All In One/Lenovo/IdeaCentre/IdeaCentre A700 10050/51968677EC4C/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/69574214D7>) |
| 8086:1502 | 1028:052c | Intel            | 82579LM Gigabit Network Connectio... | 1     | e1000e     | [E7CE3F2F38](<All In One/Acidanthera/iMacPro1/iMacPro1,1/C2AEF029DC5F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E7CE3F2F38>) |
| 8086:1503 | 1043:849c | Intel            | 82579V Gigabit Network Connection    | 1     | e1000e     | [259158AB96](<All In One/Acidanthera/iMacPro1/iMacPro1,1/F1829F0BF600/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/259158AB96>) |
| 8086:1503 | 17aa:3620 | Intel            | 82579V Gigabit Network Connection    | 1     | e1000e     | [520F0EF994](<All In One/Lenovo/IdeaCentre/IdeaCentre B520 7745/71BD816847A0/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/520F0EF994>) |
| 8086:1539 | 1849:1539 | Intel            | I211 Gigabit Network Connection      | 1     | igb        | [991A74F3E5](<All In One/Acidanthera/iMacPro1/iMacPro1,1/068603353593/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/991A74F3E5>) |
| 8086:1539 | 8086:0000 | Intel            | I211 Gigabit Network Connection      | 1     | igb        | [4ED51200E5](<All In One/iRU/A/A2313/9007113D5706/ROSA-12/5.10.71-GENERIC-1ROSA2021.1-X86_64/X86_64/4ED51200E5>) |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1485 | 1022:1485 | AMD              | Starship/Matisse Reserved SPP        | 5     |            | [13A42307A4](<All In One/Acidanthera/iMacPro1/iMacPro1,1/CCEF88A1D848/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/13A42307A4>) |
| 1022:1455 | 1022:1455 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 4     |            | [CBAE954ECC](<All In One/Dell/Inspiron/Inspiron 27 7775/ACE5205CCA5D/NIXOS-22.11/5.15.86/X86_64/CBAE954ECC>) |
| 1022:145a | 1022:145a | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 4     |            | [CBAE954ECC](<All In One/Dell/Inspiron/Inspiron 27 7775/ACE5205CCA5D/NIXOS-22.11/5.15.86/X86_64/CBAE954ECC>) |
| 1022:148a | 1022:148a | AMD              | Starship/Matisse PCIe Dummy Function | 4     |            | [13A42307A4](<All In One/Acidanthera/iMacPro1/iMacPro1,1/CCEF88A1D848/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/13A42307A4>) |
| 1022:1485 | 1043:87c0 | AMD              | Starship/Matisse Reserved SPP        | 1     |            | [577AD83B8F](<All In One/Acidanthera/iMacPro1/iMacPro1,1/6286842FEC0E/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/577AD83B8F>) |
| 1022:148a | 1043:87c0 | AMD              | Starship/Matisse PCIe Dummy Function | 1     |            | [577AD83B8F](<All In One/Acidanthera/iMacPro1/iMacPro1,1/6286842FEC0E/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/577AD83B8F>) |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 106b:1801 | 106b:1801 | Apple            | T2 Bridge Controller                 | 2     | apple_bce  | [B54C61BEA2](<All In One/Apple/iMac20/iMac20,1/4FE23979BC61/UBUNTU-22.04/5.19.10-T2/X86_64/B54C61BEA2>) |
| 106b:1802 | 106b:1802 | Apple            | T2 Secure Enclave Processor          | 2     |            | [B54C61BEA2](<All In One/Apple/iMac20/iMac20,1/4FE23979BC61/UBUNTU-22.04/5.19.10-T2/X86_64/B54C61BEA2>) |
| 1022:15e6 | 1022:15e4 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 1     | i2c_amd... | [04C483EE9B](<All In One/Acer/Aspire/Aspire C24-420/1D8955841971/ENDLESS-3.9.7/5.8.0-14-GENERIC/X86_64/04C483EE9B>) |

### Performance counters (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:27a3 |           | Intel            | 945GM/GU Chipset Hardware Monitor... | 30    |            | [C7444AC7F0](<All In One/Apple/iMac5/iMac5,1/104264B0BD86/XUBUNTU-22.04/5.15.0-70-GENERIC/X86_64/C7444AC7F0>) |
| 8086:0e30 | 1043:84ef | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 1     | ivbep_u... | [259158AB96](<All In One/Acidanthera/iMacPro1/iMacPro1,1/F1829F0BF600/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/259158AB96>) |
| 8086:0e30 | 1458:3c46 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 1     | ivbep_u... | [A8D4959FDE](<All In One/Acidanthera/iMacPro1/iMacPro1,1/44B50065E23C/ELEMENTARY-6/5.11.0-25-GENERIC/X86_64/A8D4959FDE>) |
| 8086:0e34 | 1043:84ef | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 1     | ivbep_u... | [259158AB96](<All In One/Acidanthera/iMacPro1/iMacPro1,1/F1829F0BF600/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/259158AB96>) |
| 8086:0e34 | 1458:3c43 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 1     | ivbep_u... | [A8D4959FDE](<All In One/Acidanthera/iMacPro1/iMacPro1,1/44B50065E23C/ELEMENTARY-6/5.11.0-25-GENERIC/X86_64/A8D4959FDE>) |
| 8086:0e36 | 1043:84ef | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 1     | ivbep_u... | [259158AB96](<All In One/Acidanthera/iMacPro1/iMacPro1,1/F1829F0BF600/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/259158AB96>) |
| 8086:0e36 | 1458:3c44 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 1     | ivbep_u... | [A8D4959FDE](<All In One/Acidanthera/iMacPro1/iMacPro1,1/44B50065E23C/ELEMENTARY-6/5.11.0-25-GENERIC/X86_64/A8D4959FDE>) |
| 8086:2f30 | 8086:2f30 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 1     | hswep_u... | [B2AD449201](<All In One/Acidanthera/iMacPro1/iMacPro1,1/02ABD56D98BC/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/B2AD449201>) |
| 8086:2f32 | 8086:2f32 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 QPI... | 1     | hswep_u... | [B2AD449201](<All In One/Acidanthera/iMacPro1/iMacPro1,1/02ABD56D98BC/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/B2AD449201>) |
| 8086:2f33 | 8086:2f33 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 QPI... | 1     | hswep_u... | [B2AD449201](<All In One/Acidanthera/iMacPro1/iMacPro1,1/02ABD56D98BC/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/B2AD449201>) |
| 8086:2f34 | 8086:2f34 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 PCI... | 1     | hswep_u... | [B2AD449201](<All In One/Acidanthera/iMacPro1/iMacPro1,1/02ABD56D98BC/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/B2AD449201>) |
| 8086:2f36 | 8086:2f36 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 1     | hswep_u... | [B2AD449201](<All In One/Acidanthera/iMacPro1/iMacPro1,1/02ABD56D98BC/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/B2AD449201>) |
| 8086:2f37 | 8086:2f37 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 1     | hswep_u... | [B2AD449201](<All In One/Acidanthera/iMacPro1/iMacPro1,1/02ABD56D98BC/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/B2AD449201>) |
| 8086:2f38 | 8086:2f38 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 1     | hswep_u... | [B2AD449201](<All In One/Acidanthera/iMacPro1/iMacPro1,1/02ABD56D98BC/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/B2AD449201>) |
| 8086:2f7d | 8086:2f7d | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 1     |            | [B2AD449201](<All In One/Acidanthera/iMacPro1/iMacPro1,1/02ABD56D98BC/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/B2AD449201>) |

### Pic (io(x)-apic) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0e2c | 1043:84ef | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 1     |            | [259158AB96](<All In One/Acidanthera/iMacPro1/iMacPro1,1/F1829F0BF600/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/259158AB96>) |
| 8086:0e2c | 1458:5000 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 1     |            | [A8D4959FDE](<All In One/Acidanthera/iMacPro1/iMacPro1,1/44B50065E23C/ELEMENTARY-6/5.11.0-25-GENERIC/X86_64/A8D4959FDE>) |
| 8086:2f2c | 8086:0000 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 1     |            | [B2AD449201](<All In One/Acidanthera/iMacPro1/iMacPro1,1/02ABD56D98BC/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/B2AD449201>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14e4:16bc | 14e4:0000 | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 258   | sdhci_pci  | [C8C9C1E591](<All In One/Apple/iMac13/iMac13,1/ED988FB747CF/DEBIAN-11/5.10.0-21-AMD64/X86_64/C8C9C1E591>) |
| 14e4:16bc | 14e4:96bc | Broadcom Limited | BCM57765/57785 SDXC/MMC Card Reader  | 48    | sdhci_pci  | [00D8186404](<All In One/Apple/iMac14/iMac14,2/6ABD34C5E7DF/UBUNTU-22.04/5.15.0-33-GENERIC/X86_64/00D8186404>) |
| 14e4:16bc | 106b:0000 | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 18    | sdhci_pci  | [6A8C52FAA7](<All In One/Apple/iMac13/iMac13,2/77F54E6C9FB5/DEBIAN-11/5.10.0-21-AMD64/X86_64/6A8C52FAA7>) |
| 1217:8621 | 1217:0002 | O2 Micro         | SD/MMC Card Reader Controller        | 16    | sdhci_pci  | [03C59534F5](<All In One/Acer/Aspire/Aspire Z3-715/D5B0F6B5EA52/FEDORA-36/5.18.8-200.FSYNC.FC36.X86_64/X86_64/03C59534F5>) |
| 8086:a375 | 103c:84ee | Intel            | 300 Series Chipset Family SD Host... | 14    | sdhci_pci  | [8E1245836B](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/B6DE3C8A8AED/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/8E1245836B>) |
| 10ec:5209 | 10ec:5209 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 13    | rtsx_pci   | [5F73A9E985](<All In One/LG Electronics/24V550/24V550-G.BJ31P1/8316E85EE90C/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/5F73A9E985>) |
| 197b:2381 | 1025:0266 | JMicron Techn... | Standard SD Host Controller          | 12    | sdhci_pci  | [8A9EDF5A44](<All In One/Acer/Aspire/Aspire Z5600/021BA2DCCB15/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/8A9EDF5A44>) |
| 1180:e822 | 104d:9060 | Ricoh            | MMC/SD Host Controller               | 10    | sdhci_pci  | [57E0224FFD](<All In One/Sony/VPCL13/VPCL13M1R/82175A598A60/RELD-7.9/5.15.33-1.RES7.X86_64/X86_64/57E0224FFD>) |
| 1217:8520 | 1028:0626 | O2 Micro         | SD/MMC Card Reader Controller        | 10    | sdhci_pci  | [9348834E54](<All In One/Dell/Inspiron/Inspiron 23 Model 5348/5251BCB7D469/FEDORA-37/6.2.9-200.FC37.X86_64/X86_64/9348834E54>) |
| 8086:31cc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 7     | sdhci_pci  | [38C2A94BAA](<All In One/Positivo/C464/C464A-21/1A925F871EA8/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/38C2A94BAA>) |
| 8086:31d0 | 8086:7270 | Intel            | Celeron/Pentium Silver SD Host Co... | 7     | sdhci_pci  | [38C2A94BAA](<All In One/Positivo/C464/C464A-21/1A925F871EA8/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/38C2A94BAA>) |
| 8086:5aca | 17aa:36c4 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 7     | sdhci_pci  | [5D5EB8D675](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 310-20IAP F0CL0014LD/4155E31B2EFA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/5D5EB8D675>) |
| 8086:5acc | 1854:0267 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 7     | sdhci_pci  | [04D33628A1](<All In One/LG Electronics/22V270/22V270-L.BJ31P1/8E73444ADF98/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/04D33628A1>) |
| 1022:7813 | 103c:2b3b | AMD              | FCH SD Flash Controller              | 6     | sdhci_pci  | [06799F4C58](<All In One/Hewlett-Packard/23/23-r117c/0110999D5E5B/UBUNTU-22.04/5.15.0-53-GENERIC/X86_64/06799F4C58>) |
| 1180:e823 | 104d:907e | Ricoh            | PCIe SDXC/MMC Host Controller        | 6     | sdhci_pci  | [0451CAEB29](<All In One/Sony/VPCL212/VPCL212FX/01EE677E7F92/UBUNTU-21.10/5.13.0-22-GENERIC/X86_64/0451CAEB29>) |
| 1217:8520 | 1028:0625 | O2 Micro         | SD/MMC Card Reader Controller        | 6     | sdhci_pci  | [235831E22A](<All In One/Dell/OptiPlex/OptiPlex 9030 AIO/CC35AD545B7D/MANJARO/6.1.12-1-MANJARO/X86_64/235831E22A>) |
| 197b:2381 | 103c:1489 | JMicron Techn... | Standard SD Host Controller          | 6     | sdhci_pci  | [EBD3760355](<All In One/Hewlett-Packard/Compaq/Compaq 6000 Pro AiO Business PC/F6BD16E86080/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/EBD3760355>) |
| 1180:e822 | 104d:9083 | Ricoh            | MMC/SD Host Controller               | 5     | sdhci_pci  | [1F521568E1](<All In One/Sony/VPCJ23/VPCJ23S1R/38825FA7D374/ZORIN-16/5.15.0-57-GENERIC/X86_64/1F521568E1>) |
| 1180:e822 | 104d:9097 | Ricoh            | MMC/SD Host Controller               | 5     | sdhci_pci  | [4D477A343A](<All In One/Sony/SVL2411/SVL24117FLB/B337A07B7653/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/4D477A343A>) |
| 197b:2381 | 17aa:3602 | JMicron Techn... | Standard SD Host Controller          | 5     | sdhci_pci  | [195EC7CB8C](<All In One/Lenovo/10051/10051/11244BE45969/LINUXMINT-20.3/5.4.0-126-GENERIC/X86_64/195EC7CB8C>) |
| 8086:31cc | 1043:1ea0 | Intel            | Celeron/Pentium Silver Processor ... | 5     | sdhci_pci  | [2F11E3E79D](<All In One/ASUSTek Computer/Vivo/Vivo AIO 16 V161GA_V161GA/733A41D44410/ENDLESS-4.0.14/5.11.0-35-GENERIC/X86_64/2F11E3E79D>) |
| 1022:7813 | 1028:06d1 | AMD              | FCH SD Flash Controller              | 4     | sdhci_pci  | [9E4D225CCC](<All In One/Dell/Inspiron/Inspiron 24-3455/DEA204A2B4BF/PIKAOS-22.10/6.1.0-1-X64V2-XANMOD-AMD64/X86_64/9E4D225CCC>) |
| 1180:0822 | 104d:9044 | Ricoh            | R5C822 SD/SDIO/MMC/MS/MSPro Host ... | 4     | sdhci_pci  | [3ED1AD79E4](<All In One/Sony/VGC-JS54/VGC-JS54FB_W/1013B0577913/LINUX-LITE-6.0/5.16.9/X86_64/3ED1AD79E4>) |
| 1180:e822 | 104d:9074 | Ricoh            | MMC/SD Host Controller               | 4     | sdhci_pci  | [2DEFAA2F88](<All In One/Sony/VPCJ118/VPCJ118FJ/356CC6106273/UBUNTU-20.04/5.15.0-43-GENERIC/X86_64/2DEFAA2F88>) |
| 1180:e822 | 104d:907e | Ricoh            | MMC/SD Host Controller               | 4     | sdhci_pci  | [2F2E7E4A62](<All In One/Sony/VPCL22/VPCL22S1E/A460018969DD/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/2F2E7E4A62>) |
| 8086:31cc | 1043:1632 | Intel            | Celeron/Pentium Silver Processor ... | 4     | sdhci_pci  | [E8277425A5](<All In One/ASUSTek Computer/Vivo/Vivo AIO 16 V161GAR_V161GAR/6E27D5B514B0/ENDLESS-3.8.3-NEXTHW1/5.6.0-7-GENERIC/X86_64/E8277425A5>) |
| 8086:5aca | 8086:1e8b | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | sdhci_pci  | [2368B40C21](<All In One/Intel/AB2/AB2L/36E055E2A5D8/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/2368B40C21>) |
| 8086:5aca | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | sdhci_pci  | [F31F5F63B9](<All In One/Primux Tech/PrimuxIoxAIO/PrimuxIoxAIO/460B3E745F56/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/F31F5F63B9>) |
| 8086:5acc | 8086:1e8b | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | sdhci_pci  | [2368B40C21](<All In One/Intel/AB2/AB2L/36E055E2A5D8/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/2368B40C21>) |
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | sdhci_pci  | [F31F5F63B9](<All In One/Primux Tech/PrimuxIoxAIO/PrimuxIoxAIO/460B3E745F56/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/F31F5F63B9>) |
| 8086:5ad0 | 8086:1e8b | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | sdhci_pci  | [2368B40C21](<All In One/Intel/AB2/AB2L/36E055E2A5D8/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/2368B40C21>) |
| 8086:5ad0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | sdhci_pci  | [F31F5F63B9](<All In One/Primux Tech/PrimuxIoxAIO/PrimuxIoxAIO/460B3E745F56/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/F31F5F63B9>) |
| 1022:7806 | 1462:aa5e | AMD              | FCH SD Flash Controller              | 3     | sdhci_pci  | [36D66AD0A2](<All In One/MSI/MS-AA5/MS-AA5E/7189D63B22F7/UBUNTU-MATE-22.04/5.19.0-38-GENERIC/X86_64/36D66AD0A2>) |
| 1022:7806 | 17aa:3670 | AMD              | FCH SD Flash Controller              | 3     | sdhci_pci  | [225E0C36DC](<All In One/Lenovo/C245/C245 10114/D4553E683441/XUBUNTU-18.04/5.3.0-28-GENERIC/I686/225E0C36DC>) |
| 1022:7906 | 1028:0854 | AMD              | FCH SD Flash Controller              | 3     | sdhci_pci  | [1629350AA9](<All In One/Dell/Inspiron/Inspiron 3475 AIO/33D749C2D2FC/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/1629350AA9>) |
| 1022:7906 | 17aa:36bd | AMD              | FCH SD Flash Controller              | 3     | sdhci_pci  | [8408512E28](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 510-23ASR F0CE002FPB/5E3418497EEF/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/8408512E28>) |
| 1022:7906 | 17aa:36be | AMD              | FCH SD Flash Controller              | 3     | sdhci_pci  | [0759C30DD9](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 510-22ASR F0CC001BIX/E61608155EDF/UBUNTU-22.10/5.19.0-31-GENERIC/X86_64/0759C30DD9>) |
| 10ec:5209 | 1b0a:0188 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 3     | sdhci_pci  | [0C24A93146](<All In One/Pegatron/H81/H81-P2/12407774A62B/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/0C24A93146>) |
| 1180:e823 | 104d:9083 | Ricoh            | PCIe SDXC/MMC Host Controller        | 3     | sdhci_pci  | [EEB433BF77](<All In One/Sony/VPCJ21/VPCJ21S1E/704C84A1D492/LINUXMINT-20.1/5.8.0-53-GENERIC/X86_64/EEB433BF77>) |
| 197b:2381 | 1025:0275 | JMicron Techn... | Standard SD Host Controller          | 3     | sdhci_pci  | [49DF2710DC](<All In One/Packard Bell/ONETWO/ONETWO M3700/3096674A954A/UBUNTU-18.04/5.0.0-37-GENERIC/X86_64/49DF2710DC>) |
| 197b:2381 | 1025:0608 | JMicron Techn... | Standard SD Host Controller          | 3     | sdhci_pci  | [33937E8F75](<All In One/Acer/Aspire/Aspire Z1620/19DE00291955/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/33937E8F75>) |
| 197b:2381 | 1043:842d | JMicron Techn... | Standard SD Host Controller          | 3     | sdhci_pci  | [86CD4A72D1](<All In One/ASUSTek Computer/ET2010/ET2010AG/03DD34D94A32/XUBUNTU-21.04/5.11.0-37-GENERIC/X86_64/86CD4A72D1>) |
| 197b:2381 | 1043:84c1 | JMicron Techn... | Standard SD Host Controller          | 3     | sdhci_pci  | [6E7BDBDE11](<All In One/ASUSTek Computer/ET/ET2410/9BB26012F0C8/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/6E7BDBDE11>) |
| 197b:2391 | 1043:84c1 | JMicron Techn... | Standard SD Host Controller          | 3     | sdhci_pci  | [1775D6A140](<All In One/ASUSTek Computer/ET2411/ET2411_W8/55B530902FB8/LINUXMINT-21/5.15.0-50-GENERIC/X86_64/1775D6A140>) |
| 1022:7813 | 1028:0628 | AMD              | FCH SD Flash Controller              | 2     | sdhci_pci  | [BB462BF2F6](<All In One/Dell/Inspiron/Inspiron 20 Model 3045/ABA0519402D4/KUBUNTU-20.04/5.4.0-40-GENERIC/X86_64/BB462BF2F6>) |
| 1022:7813 | 1028:074a | AMD              | FCH SD Flash Controller              | 2     | sdhci_pci  | [D796AAC0EB](<All In One/Dell/Inspiron/Inspiron 22-3265/E7FC4DDE8BBC/UBUNTU-22.04/5.15.0-46-GENERIC/X86_64/D796AAC0EB>) |
| 1022:7906 | 17aa:36ec | AMD              | FCH SD Flash Controller              | 2     | sdhci_pci  | [2CFA2D338E](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 330-20AST F0D8001LUS/36DA6D8B2B0D/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/2CFA2D338E>) |
| 1180:0822 | 104d:9043 | Ricoh            | R5C822 SD/SDIO/MMC/MS/MSPro Host ... | 2     | sdhci_pci  | [AFA509714D](<All In One/Sony/VGC-LN52/VGC-LN52JGB/54F15FF48E03/UBUNTU-20.04/5.8.0-54-GENERIC/X86_64/AFA509714D>) |
| 1180:e822 | 104d:908e | Ricoh            | MMC/SD Host Controller               | 2     | sdhci_pci  | [FE0F4C11DF](<All In One/Sony/VPCL22/VPCL22Z1R/FBA23D249ABB/ROSA-2016.1/4.9.76-NRJ-DESKTOP-1ROSA-X86_64/X86_64/FE0F4C11DF>) |
| 1180:e823 | 104d:908e | Ricoh            | PCIe SDXC/MMC Host Controller        | 2     | sdhci_pci  | [E43A2C01EB](<All In One/Sony/VPCL22/VPCL22Z1R/BC94F4FEC1E7/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/E43A2C01EB>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a324 | 8086:7270 | Intel            | Cannon Lake PCH SPI Controller       | 55    | spi_int... | [0F3F45F8E9](<All In One/Apple/iMac19/iMac19,2/5322EAC8B99B/PARROT-5.2/6.0.0-12PARROT1-AMD64/X86_64/0F3F45F8E9>) |
| 8086:a324 | 103c:84ee | Intel            | Cannon Lake PCH SPI Controller       | 14    | spi_int... | [8E1245836B](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/B6DE3C8A8AED/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/8E1245836B>) |
| 8086:9da4 | 17aa:3145 | Intel            | Cannon Point-LP SPI Controller       | 10    |            | [FAEB46556E](<All In One/Lenovo/V540-24IWL/V540-24IWL AIO 10YS0031RU/886440AA02F6/KOMETA-P10/5.10.102-STD-DEF-ALT1/X86_64/FAEB46556E>) |
| 8086:7aa4 |           | Intel            | Alder Lake-S PCH SPI Controller      | 9     | intel_s... | [E734B33010](<All In One/Graviton/D12/D12i/E65E993A1E87/ALT-10.1/5.15.104-UN-DEF-ALT1/X86_64/E734B33010>) |
| 8086:34a4 | 1025:1418 | Intel            | Ice Lake-LP SPI Controller           | 8     | spi_int... | [A82A90955E](<All In One/Acer/Aspire/Aspire C27-962/563F493FD77F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/A82A90955E>) |
| 8086:43a4 |           | Intel            | Tiger Lake-H SPI Controller          | 8     | intel_s... | [332429FC14](<All In One/Acidanthera/iMac20/iMac20,1/812DAF8F2884/ARCH-ROLLING/6.2.12-ZEN1-1-ZEN/X86_64/332429FC14>) |
| 8086:7aab |           | Intel            | Alder Lake-S PCH Serial IO SPI Co... | 8     | intel_lpss | [E734B33010](<All In One/Graviton/D12/D12i/E65E993A1E87/ALT-10.1/5.15.104-UN-DEF-ALT1/X86_64/E734B33010>) |
| 8086:43e8 |           | Intel            | Tiger Lake-H Serial IO I2C Contro... | 7     | intel_l... | [A61FFC94F5](<All In One/ICL/RAY/RAY Si105.Mi/F9B3F6AA07E6/MOS-10/5.10.136-STD-DEF-ALT1/X86_64/A61FFC94F5>) |
| 8086:43e9 |           | Intel            | Tiger Lake-H Serial IO I2C Contro... | 7     | intel_l... | [A61FFC94F5](<All In One/ICL/RAY/RAY Si105.Mi/F9B3F6AA07E6/MOS-10/5.10.136-STD-DEF-ALT1/X86_64/A61FFC94F5>) |
| 8086:43ea |           | Intel            | 500 Series Chipset Family LPSS: I... | 7     | intel_l... | [A61FFC94F5](<All In One/ICL/RAY/RAY Si105.Mi/F9B3F6AA07E6/MOS-10/5.10.136-STD-DEF-ALT1/X86_64/A61FFC94F5>) |
| 8086:7acc |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 7     | intel_lpss | [E734B33010](<All In One/Graviton/D12/D12i/E65E993A1E87/ALT-10.1/5.15.104-UN-DEF-ALT1/X86_64/E734B33010>) |
| 8086:7acd |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 7     | intel_lpss | [E734B33010](<All In One/Graviton/D12/D12i/E65E993A1E87/ALT-10.1/5.15.104-UN-DEF-ALT1/X86_64/E734B33010>) |
| 8086:7ace |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 7     | intel_lpss | [E734B33010](<All In One/Graviton/D12/D12i/E65E993A1E87/ALT-10.1/5.15.104-UN-DEF-ALT1/X86_64/E734B33010>) |
| 8086:7acf |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 7     | intel_lpss | [E734B33010](<All In One/Graviton/D12/D12i/E65E993A1E87/ALT-10.1/5.15.104-UN-DEF-ALT1/X86_64/E734B33010>) |
| 8086:7afc |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 7     | intel_lpss | [E734B33010](<All In One/Graviton/D12/D12i/E65E993A1E87/ALT-10.1/5.15.104-UN-DEF-ALT1/X86_64/E734B33010>) |
| 8086:7afd |           | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 7     | intel_lpss | [E734B33010](<All In One/Graviton/D12/D12i/E65E993A1E87/ALT-10.1/5.15.104-UN-DEF-ALT1/X86_64/E734B33010>) |
| 8086:9da4 | 8086:7270 | Intel            | Cannon Point-LP SPI Controller       | 7     |            | [24ED481783](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_A6521FA/262E2C088492/RED-OS-7.3.2/5.15.72-1.EL7.3.X86_64/X86_64/24ED481783>) |
| 8086:9dc5 | 1043:17b1 | Intel            | Cannon Point-LP Serial IO I2C Hos... | 7     | intel_lpss | [24ED481783](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_A6521FA/262E2C088492/RED-OS-7.3.2/5.15.72-1.EL7.3.X86_64/X86_64/24ED481783>) |
| 8086:9de8 | 1043:17b1 | Intel            | Cannon Point-LP Serial IO I2C Con... | 7     | intel_lpss | [24ED481783](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_A6521FA/262E2C088492/RED-OS-7.3.2/5.15.72-1.EL7.3.X86_64/X86_64/24ED481783>) |
| 8086:9de9 | 1043:17b1 | Intel            | Cannon Point-LP Serial IO I2C Con... | 7     | intel_lpss | [24ED481783](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_A6521FA/262E2C088492/RED-OS-7.3.2/5.15.72-1.EL7.3.X86_64/X86_64/24ED481783>) |
| 8086:a0a4 | 1028:0a06 | Intel            | Tiger Lake-LP SPI Controller         | 7     | intel_spi  | [39994ACDE2](<All In One/Dell/Inspiron/Inspiron 5400 AIO/A2D2F4CB9A93/LINUXMINT-20.3/5.13.0-25-GENERIC/X86_64/39994ACDE2>) |
| 8086:34a4 | 1025:1434 | Intel            | Ice Lake-LP SPI Controller           | 6     |            | [7B4EEEBDBC](<All In One/Acer/Aspire/Aspire C24-963/E4A4E93BCF0A/RED-OS-7.3/5.15.87-1.EL7.3.X86_64/X86_64/7B4EEEBDBC>) |
| 8086:a324 | 103c:8446 | Intel            | Cannon Lake PCH SPI Controller       | 6     | intel_spi  | [AD79D02FF6](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/FED3FEB2A294/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/AD79D02FF6>) |
| 8086:a324 | 103c:83eb | Intel            | Cannon Lake PCH SPI Controller       | 5     | intel_s... | [1011557C31](<All In One/Hewlett-Packard/ProOne/ProOne 440 G4 23.8-in NT AiO/EC8129DD680A/RED-OS-7.3/5.15.35-5.EL7.3.X86_64/X86_64/1011557C31>) |
| 8086:a324 | 103c:85a2 | Intel            | Cannon Lake PCH SPI Controller       | 5     | spi_int... | [C9F6D95FB2](<All In One/Hewlett-Packard/ProOne/ProOne 440 G5 23.8-in All-in-One/3714C25A2744/UBUNTU-MATE-22.10/5.19.0-31-GENERIC/X86_64/C9F6D95FB2>) |
| 8086:06a4 | 8086:7270 | Intel            | Comet Lake PCH SPI Controller        | 4     | intel_s... | [88D774DF0D](<All In One/Acidanthera/iMac20/iMac20,1/C13BE88FDE86/DEBIAN-12/6.1.0-7-AMD64/X86_64/88D774DF0D>) |
| 8086:a0a4 | 1025:150f | Intel            | Tiger Lake-LP SPI Controller         | 4     | intel_s... | [4FE6CA7F88](<All In One/Acer/Aspire/Aspire C27-1655/38F1D8798E6E/RED-OS-7.3.2/5.15.87-1.EL7.3.X86_64/X86_64/4FE6CA7F88>) |
| 8086:a0a4 | 1043:1482 | Intel            | Tiger Lake-LP SPI Controller         | 4     |            | [FFB4ED2207](<All In One/ASUSTek Computer/ASUS/ASUS Vivo AIO V241EA_V241EA/69C580FE0877/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/FFB4ED2207>) |
| 8086:a324 | 1028:084b | Intel            | Cannon Lake PCH SPI Controller       | 4     | intel_s... | [5F63C2FD15](<All In One/Dell/OptiPlex/OptiPlex 7460 AIO/81D9C9B1F509/GENTOO-2.9/6.1.1/X86_64/5F63C2FD15>) |
| 8086:a324 | 17aa:36f4 | Intel            | Cannon Lake PCH SPI Controller       | 4     | intel_s... | [C129F7C9B1](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-27ICB F0DE00EJRI/E74066EE0DE7/UBUNTUSTUDIO-22.04/5.15.0-47-LOWLATENCY/X86_64/C129F7C9B1>) |
| 8086:02a4 | 1028:0953 | Intel            | Comet Lake SPI (flash) Controller    | 3     | spi_int... | [EA8027E95B](<All In One/Dell/Inspiron/Inspiron 5490 AIO/DED288B166FA/UBUNTU-MATE-22.04/5.19.0-32-GENERIC/X86_64/EA8027E95B>) |
| 8086:02a4 | 1028:0954 | Intel            | Comet Lake SPI (flash) Controller    | 3     |            | [CA76B3A899](<All In One/Dell/Inspiron/Inspiron 7790 AIO/2F9AB0C8681A/UBUNTU-BUDGIE-21.10/5.13.0-35-GENERIC/X86_64/CA76B3A899>) |
| 8086:02a4 | 17aa:370c | Intel            | Comet Lake SPI (flash) Controller    | 3     | spi_int... | [AE16B78FA0](<All In One/Lenovo/IdeaCentre/IdeaCentre A340-24IWL F0E800PTRK/69EE34C2CE07/ROSA-12.3/6.0.7.XM1-1.KLP-XANMOD-ROSA2021.1-X86_64/X86_64/AE16B78FA0>) |
| 8086:06a4 | 1028:0984 | Intel            | Comet Lake PCH SPI Controller        | 3     |            | [EA489D447C](<All In One/Dell/OptiPlex/OptiPlex 7480 AIO/AA453186B2B9/LINUXMINT-20.1/5.4.0-104-GENERIC/X86_64/EA489D447C>) |
| 8086:34a4 | 103c:87a4 | Intel            | Ice Lake-LP SPI Controller           | 3     | intel_s... | [6B92AEDE76](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-df0xxx/2DAE71242922/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/6B92AEDE76>) |
| 8086:4da4 |           | Intel            | Jasper Lake SPI Controller           | 3     | intel_s... | [4AF4017DA0](<All In One/Intel/N5095-AIO/N5095-AIO T1/F4CC94597FDD/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/4AF4017DA0>) |
| 8086:4dab |           | Intel            | Jasper Lake LPSS: SPI Controller #1  | 3     | intel_l... | [4AF4017DA0](<All In One/Intel/N5095-AIO/N5095-AIO T1/F4CC94597FDD/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/4AF4017DA0>) |
| 8086:4dc5 |           | Intel            | Jasper Lake LPSS: I2C Controller #4  | 3     | intel_l... | [4AF4017DA0](<All In One/Intel/N5095-AIO/N5095-AIO T1/F4CC94597FDD/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/4AF4017DA0>) |
| 8086:4de8 |           | Intel            | Serial IO I2C Host Controller        | 3     | intel_l... | [4AF4017DA0](<All In One/Intel/N5095-AIO/N5095-AIO T1/F4CC94597FDD/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/4AF4017DA0>) |
| 8086:4dea |           | Intel            | Jasper Lake LPSS: I2C Controller #2  | 3     | intel_l... | [4AF4017DA0](<All In One/Intel/N5095-AIO/N5095-AIO T1/F4CC94597FDD/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/4AF4017DA0>) |
| 8086:a0a4 | 1025:1475 | Intel            | Tiger Lake-LP SPI Controller         | 3     |            | [9F1A2EDF3B](<All In One/Acer/Aspire/Aspire C24-1650/6C7EDB39C36C/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/9F1A2EDF3B>) |
| 8086:a324 | 1025:1291 | Intel            | Cannon Lake PCH SPI Controller       | 3     | intel_s... | [9949F21F98](<All In One/Acer/Veriton/Veriton Z4660G/D6F2FD870657/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/9949F21F98>) |
| 8086:a368 | 1025:1291 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 3     | intel_l... | [9949F21F98](<All In One/Acer/Veriton/Veriton Z4660G/D6F2FD870657/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/9949F21F98>) |
| 8086:02a4 | 8086:7270 | Intel            | Comet Lake SPI (flash) Controller    | 2     |            | [9E72716F96](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222FA_A6432FA/9F429A9552E8/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/9E72716F96>) |
| 8086:02c5 | 1043:1f51 | Intel            | Comet Lake Serial IO I2C Host Con... | 2     | intel_lpss | [9E72716F96](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222FA_A6432FA/9F429A9552E8/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/9E72716F96>) |
| 8086:02e8 | 1043:1f51 | Intel            | Serial IO I2C Host Controller        | 2     | intel_lpss | [9E72716F96](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222FA_A6432FA/9F429A9552E8/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/9E72716F96>) |
| 8086:02e9 | 1043:1f51 | Intel            | Comet Lake Serial IO I2C Host Con... | 2     | intel_lpss | [9E72716F96](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222FA_A6432FA/9F429A9552E8/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/9E72716F96>) |
| 8086:06a4 | 103c:86c7 | Intel            | Comet Lake PCH SPI Controller        | 2     | intel_spi  | [EFB6906A46](<All In One/Hewlett-Packard/ENVY/ENVY All-in-One 32-a11xxx/AC2CB5057523/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/EFB6906A46>) |
| 8086:06a4 | 103c:86ed | Intel            | Comet Lake PCH SPI Controller        | 2     | spi_int... | [E86753F364](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-d0xxx/C8F5FD68E798/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/E86753F364>) |
| 8086:4dc6 |           | Intel            | Jasper Lake LPSS: I2C Controller #5  | 2     | intel_l... | [4AF4017DA0](<All In One/Intel/N5095-AIO/N5095-AIO T1/F4CC94597FDD/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/4AF4017DA0>) |

### Serial controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1e3d | 1028:0543 | Intel            | 7 Series/C210 Series Chipset Fami... | 12    | serial     | [F92FA1F111](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/04BEB2B29F37/CLEAR-LINUX-OS-35190/5.13.13-1070.NATIVE/X86_64/F92FA1F111>) |
| 8086:8c3d | 1028:05a7 | Intel            | 8 Series/C220 Series Chipset Fami... | 11    | serial     | [757AE6AA73](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/099C9C0A02A0/DEBIAN-11/5.10.0-20-AMD64/X86_64/757AE6AA73>) |
| 8086:2e17 | 103c:1489 | Intel            | 4 Series Chipset Serial KT Contro... | 6     | serial     | [EBD3760355](<All In One/Hewlett-Packard/Compaq/Compaq 6000 Pro AiO Business PC/F6BD16E86080/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/EBD3760355>) |
| 8086:1c3d | 103c:3395 | Intel            | 6 Series/C200 Series Chipset Fami... | 5     | serial     | [DAEDB871F5](<All In One/Hewlett-Packard/Compaq/Compaq 8200 Elite AiO Business PC/AF5919835808/LINUXMINT-20.3/5.15.0-56-GENERIC/X86_64/DAEDB871F5>) |
| 8086:a363 | 103c:83eb | Intel            | Cannon Lake PCH Active Management... | 5     | serial     | [1011557C31](<All In One/Hewlett-Packard/ProOne/ProOne 440 G4 23.8-in NT AiO/EC8129DD680A/RED-OS-7.3/5.15.35-5.EL7.3.X86_64/X86_64/1011557C31>) |
| 8086:a2bd | 103c:829b | Intel            | 200 Series Chipset Family KT Redi... | 4     | serial     | [23122CBA32](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G3 23.8-in Non-Touch AiO/E6CDD7190196/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.3-1-DEFAULT/X86_64/23122CBA32>) |
| 8086:a363 | 103c:85a2 | Intel            | Cannon Lake PCH Active Management... | 4     | serial     | [C9F6D95FB2](<All In One/Hewlett-Packard/ProOne/ProOne 440 G5 23.8-in All-in-One/3714C25A2744/UBUNTU-MATE-22.10/5.19.0-31-GENERIC/X86_64/C9F6D95FB2>) |
| 10ec:816a | 1025:1291 | Realtek Semic... | RTL8111xP UART #1                    | 3     | serial     | [9949F21F98](<All In One/Acer/Veriton/Veriton Z4660G/D6F2FD870657/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/9949F21F98>) |
| 10ec:816b | 1025:1291 | Realtek Semic... | RTL8111xP UART #2                    | 3     | serial     | [9949F21F98](<All In One/Acer/Veriton/Veriton Z4660G/D6F2FD870657/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/9949F21F98>) |
| 8086:a13d | 1028:06c5 | Intel            | 100 Series/C230 Series Chipset Fa... | 3     | serial     | [5FA9B60268](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/190D4C0148F8/OPENSUSE-LEAP-15.2/5.3.18-LP152.106-DEFAULT/X86_64/5FA9B60268>) |
| 8086:a13d | 17aa:30ba | Intel            | 100 Series/C230 Series Chipset Fa... | 3     | serial     | [F3E9E0B2F5](<All In One/Lenovo/ThinkCentre/ThinkCentre M900z 10F3000DGE/DDF891FE5172/ROSA-2016.1/4.15.0-DESKTOP-68.5ROSA-X86_64/X86_64/F3E9E0B2F5>) |
| 10ec:816a | 1025:1071 | Realtek Semic... | RTL8111xP UART #1                    | 2     | serial     | [651D569B66](<All In One/Acer/Veriton/Veriton Z4820G/A079770A155B/KOMETA-P10/5.10.109-STD-DEF-ALT1/X86_64/651D569B66>) |
| 10ec:816a | 1025:1290 | Realtek Semic... | RTL8111xP UART #1                    | 2     |            | [A27363041A](<All In One/Acer/Veriton/Veriton Z4860G/8955EDC1BE49/ENDLESS-3.9.1/5.8.0-14-GENERIC/X86_64/A27363041A>) |
| 10ec:816b | 1025:1071 | Realtek Semic... | RTL8111xP UART #2                    | 2     | serial     | [651D569B66](<All In One/Acer/Veriton/Veriton Z4820G/A079770A155B/KOMETA-P10/5.10.109-STD-DEF-ALT1/X86_64/651D569B66>) |
| 10ec:816b | 1025:1290 | Realtek Semic... | RTL8111xP UART #2                    | 2     |            | [A27363041A](<All In One/Acer/Veriton/Veriton Z4860G/8955EDC1BE49/ENDLESS-3.9.1/5.8.0-14-GENERIC/X86_64/A27363041A>) |
| 8086:1c3d | 103c:3561 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | serial     | [7AF1912AB7](<All In One/Hewlett-Packard/Z1/Z1 Workstation/4089A5726DF1/FEDORA-37/6.0.9-300.FC37.X86_64/X86_64/7AF1912AB7>) |
| 8086:a13d | 1028:075d | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | serial     | [404A8B3A68](<All In One/Dell/Precision/Precision 5720 AIO/20C5601ED4D8/FEDORA-30/5.2.16-200.FC30.X86_64/X86_64/404A8B3A68>) |
| 8086:a13d | 103c:8058 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | serial     | [09B55E64F6](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G2 23-in Non-Touch AiO/0E4D816E1F73/UBUNTU-20.04/5.4.0-31-GENERIC/X86_64/09B55E64F6>) |
| 8086:a13d | 103c:805e | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | serial     | [FDD688E64E](<All In One/Hewlett-Packard/ProOne/ProOne 600 G2 21.5-in Non-Touch AiO/7B6639DBD126/UBUNTU-22.10/5.19.0-23-GENERIC/X86_64/FDD688E64E>) |
| 8086:a2bd | 1028:079c | Intel            | 200 Series Chipset Family KT Redi... | 2     | serial     | [0B0F9A42CD](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/F87DB1F1F5AC/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/0B0F9A42CD>) |
| 8086:a2bd | 17aa:3110 | Intel            | 200 Series Chipset Family KT Redi... | 2     | serial     | [CDE94F0C8E](<All In One/Lenovo/ThinkCentre/ThinkCentre M910z 10NS0003US/D3A4B2847E9F/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/CDE94F0C8E>) |
| 8086:a363 | 1028:084b | Intel            | Cannon Lake PCH Active Management... | 2     | serial     | [5F63C2FD15](<All In One/Dell/OptiPlex/OptiPlex 7460 AIO/81D9C9B1F509/GENTOO-2.9/6.1.1/X86_64/5F63C2FD15>) |
| 10ec:816a | 10ec:0123 | Realtek Semic... | RTL8111xP UART #1                    | 1     | serial     | [2278A5C6EA](<All In One/Samsung Electronics/SUR/SUR40/9A8E67BB1389/DEBIAN-11/5.19.0-2-AMD64/X86_64/2278A5C6EA>) |
| 10ec:816b | 10ec:0123 | Realtek Semic... | RTL8111xP UART #2                    | 1     | serial     | [2278A5C6EA](<All In One/Samsung Electronics/SUR/SUR40/9A8E67BB1389/DEBIAN-11/5.19.0-2-AMD64/X86_64/2278A5C6EA>) |
| 13a8:0354 |           | Exar             | Exar's 4-Port UART PCIe Card         | 1     | 8250_exar  | [B5FBC6A19B](<All In One/Lenovo/IdeaCentre/IdeaCentre B540p 3363/9976329CE6AE/UBUNTU-20.04/5.4.0-31-GENERIC/X86_64/B5FBC6A19B>) |
| 8086:06e3 | 103c:871b | Intel            | Comet Lake Keyboard and Text (KT)... | 1     | serial     | [EB4B572A21](<All In One/Hewlett-Packard/ProOne/ProOne 440 G6 24 All-in-One PC/99C228B86E44/DEBIAN-11/5.10.0-16-AMD64/X86_64/EB4B572A21>) |
| 8086:06e3 | 103c:871c | Intel            | Comet Lake Keyboard and Text (KT)... | 1     | serial     | [2F7FD6200F](<All In One/Hewlett-Packard/ProOne/ProOne 440 G6 24 All-in-One PC/E75014542A4C/CENTOS-7/3.10.0-1160.11.1.EL7.X86_64/X86_64/2F7FD6200F>) |
| 8086:1c3d | 1c1d:0001 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | serial     | [4E2FFC0DB7](<All In One/InFocus/INF/INF5520/89A8A2E44A06/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/4E2FFC0DB7>) |
| 8086:1e3d | 1028:0577 | Intel            | 7 Series/C210 Series Chipset Fami... | 1     | serial     | [E7CE3F2F38](<All In One/Acidanthera/iMacPro1/iMacPro1,1/C2AEF029DC5F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E7CE3F2F38>) |
| 8086:1e3d | 1854:f004 | Intel            | 7 Series/C210 Series Chipset Fami... | 1     | serial     | [81CF385125](<All In One/LG Electronics/SUPERSIGN/SUPERSIGN/3DF362B44399/ROSA-2012.0/3.0.28-NRJ-DESKTOP-2ROSA.LTS/X86_64/81CF385125>) |
| 8086:51fc | 17aa:3767 | Intel            | Alder Lake-P Integrated Sensor Hub   | 1     | intel_i... | [F9F38488A8](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 5 27IAH7 F0GQ0001US/D9930DEAC59F/POP!_OS-22.04/6.0.12-76060006-GENERIC/X86_64/F9F38488A8>) |
| 8086:7aeb | 103c:8959 | Intel            | 600 Series Chipset Family Managem... | 1     | 8250_pci   | [A44D50AE5C](<All In One/Hewlett-Packard/ProOne/ProOne 440 23.8 inch G9 All-in-One Desktop PC/3551A8213F41/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/A44D50AE5C>) |
| 8086:7aeb | 103c:895f | Intel            | 600 Series Chipset Family Managem... | 1     | serial     | [0C23DF771F](<All In One/Hewlett-Packard/EliteOne/EliteOne 870 27 inch G9 All-in-One Desktop PC/3F38BA670890/RED-OS-7.3.2/5.15.87-1.EL7.3.X86_64/X86_64/0C23DF771F>) |
| 8086:7af8 | 103c:895f | Intel            | 600 Series Chipset Family Integra... | 1     | intel_i... | [0C23DF771F](<All In One/Hewlett-Packard/EliteOne/EliteOne 870 27 inch G9 All-in-One Desktop PC/3F38BA670890/RED-OS-7.3.2/5.15.87-1.EL7.3.X86_64/X86_64/0C23DF771F>) |
| 8086:8c3d | 1028:0625 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | serial     | [399D367F06](<All In One/Dell/OptiPlex/OptiPlex 9030 AIO/4D03114CF02D/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/399D367F06>) |
| 8086:8c3d | 8086:204c | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | serial     | [098FE372A3](<All In One/Acidanthera/iMac14/iMac14,4/E2C69985CC45/GENTOO-2.6/5.4.97-GENTOO_DQ87PG/X86_64/098FE372A3>) |
| 8086:8d3d | 8086:7270 | Intel            | C610/X99 series chipset KT Contro... | 1     | serial     | [B2AD449201](<All In One/Acidanthera/iMacPro1/iMacPro1,1/02ABD56D98BC/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/B2AD449201>) |
| 8086:a13d | 103c:8139 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | serial     | [453674ECA2](<All In One/Hewlett-Packard/RP9/RP9 G1 AiO Retail System, Model 9015/2AA49223DF93/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/453674ECA2>) |
| 8086:a2bd | 103c:829c | Intel            | 200 Series Chipset Family KT Redi... | 1     | serial     | [91F5A10BA1](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G3 23.8-in NT GPU AiO/67C5374EC0C9/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/91F5A10BA1>) |
| 8086:a2bd | 103c:82b5 | Intel            | 200 Series Chipset Family KT Redi... | 1     | serial     | [59FE255866](<All In One/Hewlett-Packard/ProOne/ProOne 600 G3 21.5-in Non-Touch AiO/BD849639E3C0/ZORIN-16/5.15.0-56-GENERIC/X86_64/59FE255866>) |
| 8086:a363 | 1028:0935 | Intel            | Cannon Lake PCH Active Management... | 1     | serial     | [3C361F58E8](<All In One/Dell/OptiPlex/OptiPlex 7470 AIO/4A5BE5FE2538/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/3C361F58E8>) |
| 8086:a363 | 103c:83e4 | Intel            | Cannon Lake PCH Active Management... | 1     | serial     | [CDEFBA9E55](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G4 23.8-in Non-Touch AiO/EA730404E3BF/FEDORA-37/6.0.7-301.FC37.X86_64/X86_64/CDEFBA9E55>) |
| 8086:a363 | 103c:85a0 | Intel            | Cannon Lake PCH Active Management... | 1     | serial     | [8B7CFBA471](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G5 23.8-in All-in-One/69F404274F15/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/8B7CFBA471>) |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:3b32 | 8086:0000 | Intel            | 5 Series/3400 Series Chipset Ther... | 86    | intel_ips  | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 8086:a379 | 8086:7270 | Intel            | Cannon Lake PCH Thermal Controller   | 51    | intel_p... | [0F3F45F8E9](<All In One/Apple/iMac19/iMac19,2/5322EAC8B99B/PARROT-5.2/6.0.0-12PARROT1-AMD64/X86_64/0F3F45F8E9>) |
| 8086:9d61 | 8086:9d61 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 26    | intel_lpss | [CDB6233482](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/13576610145B/DEBIAN-11/5.10.0-18-AMD64/X86_64/CDB6233482>) |
| 8086:a2b1 | 1019:a5a1 | Intel            | 200 Series PCH Thermal Subsystem     | 22    |            | [63DBB9394E](<All In One/ICL/RAY/RAY S122.Mi/767FFC5AB7B5/ALT-8.4/5.10.83-STD-DEF-ALT0.C9F.2/X86_64/63DBB9394E>) |
| 8086:8ca4 | 8086:7270 | Intel            | 9 Series Chipset Family Thermal C... | 19    |            | [570077AA64](<All In One/Apple/iMac16/iMac16,2/2D4E89D37302/ZORIN-16/5.15.0-69-GENERIC/X86_64/570077AA64>) |
| 8086:9a0d |           | Intel            | Tigerlake Telemetry Aggregator       | 19    | intel_pmt  | [C87417466C](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 27ITL6 F0FW00Q2RU/E4E2B81CA7F6/DEBIAN-11/5.10.0-21-AMD64/X86_64/C87417466C>) |
| 8086:9d60 | 103c:84de | Intel            | Sunrise Point-LP Serial IO I2C Co... | 17    | intel_lpss | [CDB6233482](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/13576610145B/DEBIAN-11/5.10.0-18-AMD64/X86_64/CDB6233482>) |
| 8086:a379 | 103c:84ee | Intel            | Cannon Lake PCH Thermal Controller   | 14    | intel_p... | [8E1245836B](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/B6DE3C8A8AED/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/8E1245836B>) |
| 8086:9d31 | 1025:1287 | Intel            | Sunrise Point-LP Thermal subsystem   | 13    | intel_p... | [EB0191F969](<All In One/Acer/Aspire/Aspire C22-865/2C5B66C0839A/MANJARO/6.1.1-1-MANJARO/X86_64/EB0191F969>) |
| 8086:318c | 1025:1304 | Intel            | Celeron/Pentium Silver Processor ... | 12    | proc_th... | [07D4BF17AA](<All In One/Acer/Aspire/Aspire C22-820/D247EFB9442C/ROSA-12.3/5.10.155-GENERIC-1ROSA2021.1-X86_64/X86_64/07D4BF17AA>) |
| 8086:3a32 | 1025:0266 | Intel            | 82801JI (ICH10 Family) Thermal Su... | 12    |            | [8A9EDF5A44](<All In One/Acer/Aspire/Aspire Z5600/021BA2DCCB15/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/8A9EDF5A44>) |
| 8086:9d31 | 8086:9d31 | Intel            | Sunrise Point-LP Thermal subsystem   | 12    | intel_p... | [557E50987C](<All In One/ASUSTek Computer/ZN240/ZN240IC/A4EB8493DB43/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/557E50987C>) |
| 8086:22dc |           | Intel            | Atom/Celeron/Pentium Processor x5... | 11    | proc_th... | [69F378F0B5](<All In One/ASUSTek Computer/A/A4110/B91604D5677F/UBUNTU-20.04/5.15.0-60-GENERIC/X86_64/69F378F0B5>) |
| 8086:467d |           | Intel            | Platform Monitoring Technology       | 11    | intel_pmt  | [E734B33010](<All In One/Graviton/D12/D12i/E65E993A1E87/ALT-10.1/5.15.104-UN-DEF-ALT1/X86_64/E734B33010>) |
| 8086:318c | 1854:0308 | Intel            | Celeron/Pentium Silver Processor ... | 10    | process... | [EC912EFB6F](<All In One/LG Electronics/22V280/22V280-L.BJ31P1/925F8D37ECFF/FEDORA-37/6.0.12-300.FC37.X86_64/X86_64/EC912EFB6F>) |
| 8086:9df9 | 17aa:3145 | Intel            | Cannon Point-LP Thermal Controller   | 10    | intel_p... | [FAEB46556E](<All In One/Lenovo/V540-24IWL/V540-24IWL AIO 10YS0031RU/886440AA02F6/KOMETA-P10/5.10.102-STD-DEF-ALT1/X86_64/FAEB46556E>) |
| 8086:a131 | 1028:06c5 | Intel            | 100 Series/C230 Series Chipset Fa... | 10    | intel_p... | [5B29ED7213](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/BE925566CC9F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5B29ED7213>) |
| 8086:5a8c |           | Intel            | Atom/Celeron/Pentium Dynamic Plat... | 9     | process... | [F31F5F63B9](<All In One/Primux Tech/PrimuxIoxAIO/PrimuxIoxAIO/460B3E745F56/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/F31F5F63B9>) |
| 8086:9d60 | 8086:9d60 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 9     | intel_lpss | [48ADD8DC01](<All In One/ASUSTek Computer/V241/V241IC-R/D782169DBFD0/RED-OS-7.3.1/5.15.35-1.EL7.3.X86_64/X86_64/48ADD8DC01>) |
| 8086:1903 | 8086:1903 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 8     | proc_th... | [48ADD8DC01](<All In One/ASUSTek Computer/V241/V241IC-R/D782169DBFD0/RED-OS-7.3.1/5.15.35-1.EL7.3.X86_64/X86_64/48ADD8DC01>) |
| 8086:9ca4 | 8086:7270 | Intel            | Wildcat Point-LP Thermal Manageme... | 8     | intel_p... | [44B9054B8C](<All In One/Apple/iMac16/iMac16,1/FCCB3A22541B/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/44B9054B8C>) |
| 8086:a3b1 | 8086:7270 | Intel            | Comet Lake PCH-V Thermal Subsystem   | 8     |            | [C6437188E6](<All In One/Hewlett-Packard/All-in-One/All-in-One 27-dp0xxx/1B38D1EFE767/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/C6437188E6>) |
| 8086:1903 | 1043:17b1 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 7     | proc_th... | [24ED481783](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_A6521FA/262E2C088492/RED-OS-7.3.2/5.15.72-1.EL7.3.X86_64/X86_64/24ED481783>) |
| 8086:5a8c | 17aa:36c4 | Intel            | Atom/Celeron/Pentium Dynamic Plat... | 7     | process... | [5D5EB8D675](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 310-20IAP F0CL0014LD/4155E31B2EFA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/5D5EB8D675>) |
| 8086:9d31 | 1028:0754 | Intel            | Sunrise Point-LP Thermal subsystem   | 7     | intel_p... | [348BC23246](<All In One/Dell/Inspiron/Inspiron 3464 AIO/00109263052E/ENDEAVOUROS-ROLLING/5.15.71-1-LTS/X86_64/348BC23246>) |
| 8086:9d60 | 1028:0754 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 7     | intel_l... | [348BC23246](<All In One/Dell/Inspiron/Inspiron 3464 AIO/00109263052E/ENDEAVOUROS-ROLLING/5.15.71-1-LTS/X86_64/348BC23246>) |
| 8086:9d61 | 1028:0754 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 7     | intel_l... | [348BC23246](<All In One/Dell/Inspiron/Inspiron 3464 AIO/00109263052E/ENDEAVOUROS-ROLLING/5.15.71-1-LTS/X86_64/348BC23246>) |
| 8086:9df9 | 1043:17b1 | Intel            | Cannon Point-LP Thermal Controller   | 7     | intel_p... | [24ED481783](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_A6521FA/262E2C088492/RED-OS-7.3.2/5.15.72-1.EL7.3.X86_64/X86_64/24ED481783>) |
| 8086:a2b1 | 1028:079c | Intel            | 200 Series PCH Thermal Subsystem     | 7     |            | [1940C6417C](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/A9167F8393F4/DEBIAN-11/5.10.0-21-AMD64/X86_64/1940C6417C>) |
| 8086:a2e0 | 1028:079c | Intel            | 200 Series PCH Serial IO I2C Cont... | 7     | intel_l... | [1940C6417C](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/A9167F8393F4/DEBIAN-11/5.10.0-21-AMD64/X86_64/1940C6417C>) |
| 8086:318c | 103c:86f0 | Intel            | Celeron/Pentium Silver Processor ... | 6     | process... | [2FAB63E976](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-df0xxx/0229793D3988/KUBUNTU-22.04/5.15.0-60-LOWLATENCY/X86_64/2FAB63E976>) |
| 8086:a131 | 8086:a131 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     | intel_p... | [BAC1E9869D](<All In One/ASUSTek Computer/V230/V230IC/388C8BB5ED5C/OPENMANDRIVA-4.90/5.18.12-DESKTOP-3OMV4090/X86_64/BAC1E9869D>) |
| 8086:a379 | 103c:8446 | Intel            | Cannon Lake PCH Thermal Controller   | 6     | intel_p... | [AD79D02FF6](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/FED3FEB2A294/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/AD79D02FF6>) |
| 8086:1603 | 8086:2010 | Intel            | Broadwell-U Processor Thermal Sub... | 5     | proc_th... | [5F73A9E985](<All In One/LG Electronics/24V550/24V550-G.BJ31P1/8316E85EE90C/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/5F73A9E985>) |
| 8086:1e24 | 1462:b062 | Intel            | 7 Series/C210 Series Chipset Fami... | 5     |            | [2884F81FA1](<All In One/MSI/MS-B/MS-B06211/5E5CC6822A01/UBUNTU-22.04/5.15.0-25-GENERIC/X86_64/2884F81FA1>) |
| 8086:318c | 1043:1e80 | Intel            | Celeron/Pentium Silver Processor ... | 5     | process... | [23082AB8CA](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222GA_V222GA/30DB3562CA34/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/23082AB8CA>) |
| 8086:318c | 1043:1ea0 | Intel            | Celeron/Pentium Silver Processor ... | 5     | proc_th... | [2F11E3E79D](<All In One/ASUSTek Computer/Vivo/Vivo AIO 16 V161GA_V161GA/733A41D44410/ENDLESS-4.0.14/5.11.0-35-GENERIC/X86_64/2F11E3E79D>) |
| 8086:31b4 | 1043:1e80 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_lpss | [23082AB8CA](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222GA_V222GA/30DB3562CA34/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/23082AB8CA>) |
| 8086:31b4 | 1043:1ea0 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_lpss | [2F11E3E79D](<All In One/ASUSTek Computer/Vivo/Vivo AIO 16 V161GA_V161GA/733A41D44410/ENDLESS-4.0.14/5.11.0-35-GENERIC/X86_64/2F11E3E79D>) |
| 8086:31b6 | 1043:1e80 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_lpss | [23082AB8CA](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222GA_V222GA/30DB3562CA34/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/23082AB8CA>) |
| 8086:31b6 | 1043:1ea0 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_lpss | [2F11E3E79D](<All In One/ASUSTek Computer/Vivo/Vivo AIO 16 V161GA_V161GA/733A41D44410/ENDLESS-4.0.14/5.11.0-35-GENERIC/X86_64/2F11E3E79D>) |
| 8086:31c2 | 1043:1e80 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_lpss | [23082AB8CA](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222GA_V222GA/30DB3562CA34/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/23082AB8CA>) |
| 8086:31c2 | 1043:1ea0 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_lpss | [2F11E3E79D](<All In One/ASUSTek Computer/Vivo/Vivo AIO 16 V161GA_V161GA/733A41D44410/ENDLESS-4.0.14/5.11.0-35-GENERIC/X86_64/2F11E3E79D>) |
| 8086:a131 | 1025:1063 | Intel            | 100 Series/C230 Series Chipset Fa... | 5     | intel_p... | [03C59534F5](<All In One/Acer/Aspire/Aspire Z3-715/D5B0F6B5EA52/FEDORA-36/5.18.8-200.FSYNC.FC36.X86_64/X86_64/03C59534F5>) |
| 8086:a379 | 103c:83eb | Intel            | Cannon Lake PCH Thermal Controller   | 5     | intel_p... | [1011557C31](<All In One/Hewlett-Packard/ProOne/ProOne 440 G4 23.8-in NT AiO/EC8129DD680A/RED-OS-7.3/5.15.35-5.EL7.3.X86_64/X86_64/1011557C31>) |
| 8086:a379 | 103c:85a2 | Intel            | Cannon Lake PCH Thermal Controller   | 5     | intel_p... | [C9F6D95FB2](<All In One/Hewlett-Packard/ProOne/ProOne 440 G5 23.8-in All-in-One/3714C25A2744/UBUNTU-MATE-22.10/5.19.0-31-GENERIC/X86_64/C9F6D95FB2>) |
| 8086:1903 | 103c:86f7 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 4     | proc_th... | [C6437188E6](<All In One/Hewlett-Packard/All-in-One/All-in-One 27-dp0xxx/1B38D1EFE767/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/C6437188E6>) |
| 8086:1903 | 1043:12a1 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 4     | proc_th... | [0ED5F3ECCD](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222UA/B404F454B226/BOSS-9/5.10.0-11-AMD64/X86_64/0ED5F3ECCD>) |
| 8086:318c | 1043:1632 | Intel            | Celeron/Pentium Silver Processor ... | 4     | proc_th... | [E8277425A5](<All In One/ASUSTek Computer/Vivo/Vivo AIO 16 V161GAR_V161GAR/6E27D5B514B0/ENDLESS-3.8.3-NEXTHW1/5.6.0-7-GENERIC/X86_64/E8277425A5>) |
| 8086:318c | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 4     | process... | [38C2A94BAA](<All In One/Positivo/C464/C464A-21/1A925F871EA8/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/38C2A94BAA>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c22 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 170   | i2c_i801   | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 8086:283e | 106b:00a0 | Intel            | 82801H (ICH8 Family) SMBus Contro... | 155   | i2c_i801   | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 10de:0aa2 | 10de:cb79 | Nvidia           | MCP79 SMBus                          | 128   | i2c_nfo... | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 8086:8c22 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 89    | i2c_i801   | [00D8186404](<All In One/Apple/iMac14/iMac14,2/6ABD34C5E7DF/UBUNTU-22.04/5.15.0-33-GENERIC/X86_64/00D8186404>) |
| 8086:a123 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 89    | i2c_i801   | [EE288626F4](<All In One/Apple/iMac18/iMac18,3/85F2F89AFF57/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/EE288626F4>) |
| 8086:3b30 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset SMBu... | 86    | i2c_i801   | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 8086:a323 | 8086:7270 | Intel            | Cannon Lake PCH SMBus Controller     | 51    | i2c_i801   | [0F3F45F8E9](<All In One/Apple/iMac19/iMac19,2/5322EAC8B99B/PARROT-5.2/6.0.0-12PARROT1-AMD64/X86_64/0F3F45F8E9>) |
| 8086:1e22 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family SMBu... | 49    | i2c_i801   | [C8C9C1E591](<All In One/Apple/iMac13/iMac13,1/ED988FB747CF/DEBIAN-11/5.10.0-21-AMD64/X86_64/C8C9C1E591>) |
| 8086:27da | 8086:7270 | Intel            | NM10/ICH7 Family SMBus Controller    | 30    | i2c_i801   | [C7444AC7F0](<All In One/Apple/iMac5/iMac5,1/104264B0BD86/XUBUNTU-22.04/5.15.0-70-GENERIC/X86_64/C7444AC7F0>) |
| 8086:a2a3 | 1019:a5a1 | Intel            | 200 Series/Z370 Chipset Family SM... | 22    | i2c_i801   | [63DBB9394E](<All In One/ICL/RAY/RAY S122.Mi/767FFC5AB7B5/ALT-8.4/5.10.83-STD-DEF-ALT0.C9F.2/X86_64/63DBB9394E>) |
| 8086:8ca2 | 8086:7270 | Intel            | 9 Series Chipset Family SMBus Con... | 19    | i2c_i801   | [570077AA64](<All In One/Apple/iMac16/iMac16,2/2D4E89D37302/ZORIN-16/5.15.0-69-GENERIC/X86_64/570077AA64>) |
| 1022:780b | 103c:8245 | AMD              | FCH SMBus Controller                 | 17    | i2c_piix4  | [81F625006B](<All In One/Hewlett-Packard/24/24-g020/310803ED8E33/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/81F625006B>) |
| 8086:9d23 | 103c:84de | Intel            | Sunrise Point-LP SMBus               | 17    | i2c_i801   | [CDB6233482](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/13576610145B/DEBIAN-11/5.10.0-18-AMD64/X86_64/CDB6233482>) |
| 8086:1c22 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 16    | i2c_i801   | [D75E472005](<All In One/Lenovo/C440/C440 10104/983B023892A1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/D75E472005>) |
| 8086:1c22 | 1028:0511 | Intel            | 6 Series/C200 Series Chipset Fami... | 15    | i2c_i801   | [225E42D432](<All In One/Dell/Inspiron/Inspiron One 2320/D8B99273D539/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/225E42D432>) |
| 8086:8c22 | 1028:05a7 | Intel            | 8 Series/C220 Series Chipset Fami... | 15    | i2c_i801   | [757AE6AA73](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/099C9C0A02A0/DEBIAN-11/5.10.0-20-AMD64/X86_64/757AE6AA73>) |
| 8086:1e22 | 1028:0543 | Intel            | 7 Series/C216 Chipset Family SMBu... | 14    | i2c_i801   | [00CB2D66A8](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/42A1DEC89484/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/00CB2D66A8>) |
| 8086:1e22 | 1028:0548 | Intel            | 7 Series/C216 Chipset Family SMBu... | 14    | i2c_i801   | [22CBD67F5D](<All In One/Dell/Inspiron/Inspiron One 2330/C959D85DE508/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/22CBD67F5D>) |
| 8086:a323 | 103c:84ee | Intel            | Cannon Lake PCH SMBus Controller     | 14    | i801_smbus | [8E1245836B](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/B6DE3C8A8AED/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/8E1245836B>) |
| 1022:790b | 103c:8381 | AMD              | FCH SMBus Controller                 | 13    | i2c_piix4  | [6745FD4BAC](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/EF305E495BCA/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/6745FD4BAC>) |
| 1022:790b | 103c:8430 | AMD              | FCH SMBus Controller                 | 13    | i2c_piix4  | [B813F95C6F](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/3A989707384A/ZORIN-16/5.15.0-69-GENERIC/X86_64/B813F95C6F>) |
| 8086:2292 | 103c:81bb | Intel            | Atom/Celeron/Pentium Processor x5... | 13    | i801_smbus | [8C50716D55](<All In One/Hewlett-Packard/20/20-c012a/A9551DF58B53/LINUXMINT-20.3/5.4.0-148-GENERIC/X86_64/8C50716D55>) |
| 8086:8c22 | 1028:05db | Intel            | 8 Series/C220 Series Chipset Fami... | 13    | i2c_i801   | [323E28FDED](<All In One/Dell/Inspiron/Inspiron 2350/07DCD03E083E/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/323E28FDED>) |
| 8086:9c22 | 8086:7270 | Intel            | 8 Series SMBus Controller            | 13    | i2c_i801   | [6976F884E6](<All In One/Apple/iMac14/iMac14,4/6E7600BFDA83/LUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6976F884E6>) |
| 8086:9d23 | 1025:1287 | Intel            | Sunrise Point-LP SMBus               | 13    | i2c_i801   | [EB0191F969](<All In One/Acer/Aspire/Aspire C22-865/2C5B66C0839A/MANJARO/6.1.1-1-MANJARO/X86_64/EB0191F969>) |
| 8086:9d23 | 8086:9d23 | Intel            | Sunrise Point-LP SMBus               | 13    | i2c_i801   | [557E50987C](<All In One/ASUSTek Computer/ZN240/ZN240IC/A4EB8493DB43/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/557E50987C>) |
| 8086:1c22 | 103c:2ac5 | Intel            | 6 Series/C200 Series Chipset Fami... | 12    | i2c_i801   | [B32F35A4B1](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/C0BF0A16B6D4/FEDORA-36/5.18.19-200.FC36.X86_64/X86_64/B32F35A4B1>) |
| 8086:31d4 | 1025:1304 | Intel            | Celeron/Pentium Silver Processor ... | 12    | i2c_i801   | [07D4BF17AA](<All In One/Acer/Aspire/Aspire C22-820/D247EFB9442C/ROSA-12.3/5.10.155-GENERIC-1ROSA2021.1-X86_64/X86_64/07D4BF17AA>) |
| 8086:3a30 | 1025:0266 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 12    | i2c_i801   | [8A9EDF5A44](<All In One/Acer/Aspire/Aspire Z5600/021BA2DCCB15/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/8A9EDF5A44>) |
| 1002:4385 |           | AMD              | SBx00 SMBus Controller               | 11    | i2c_piix4  | [E0FD42AC99](<All In One/Dell/Inspiron/Inspiron One 2305/CCF514D6F2CB/UBUNTU-22.10/5.19.0-31-GENERIC/X86_64/E0FD42AC99>) |
| 1022:790b | 103c:86f3 | AMD              | FCH SMBus Controller                 | 11    | i2c_piix4  | [DC3ADE850C](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-df0xxx/149EB6B30B69/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/DC3ADE850C>) |
| 10de:0752 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] SMBus          | 11    | i2c_nfo... | [E0B8F5D54B](<All In One/Acer/Aspire/Aspire Z3101/B30C614DB765/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/E0B8F5D54B>) |
| 1022:780b | 103c:2b3b | AMD              | FCH SMBus Controller                 | 10    | i2c_piix4  | [CB25C51987](<All In One/Hewlett-Packard/23/23-r155la/F1B498CB86AC/ZORIN-16/5.15.0-60-GENERIC/X86_64/CB25C51987>) |
| 8086:31d4 | 1854:0308 | Intel            | Celeron/Pentium Silver Processor ... | 10    | i2c_i801   | [EC912EFB6F](<All In One/LG Electronics/22V280/22V280-L.BJ31P1/925F8D37ECFF/FEDORA-37/6.0.12-300.FC37.X86_64/X86_64/EC912EFB6F>) |
| 8086:3a30 | 104d:9060 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 10    | i2c_i801   | [57E0224FFD](<All In One/Sony/VPCL13/VPCL13M1R/82175A598A60/RELD-7.9/5.15.33-1.RES7.X86_64/X86_64/57E0224FFD>) |
| 8086:8c22 | 1028:0626 | Intel            | 8 Series/C220 Series Chipset Fami... | 10    | i2c_i801   | [9348834E54](<All In One/Dell/Inspiron/Inspiron 23 Model 5348/5251BCB7D469/FEDORA-37/6.2.9-200.FC37.X86_64/X86_64/9348834E54>) |
| 8086:9ca2 | 8086:9ca2 | Intel            | Wildcat Point-LP SMBus Controller    | 10    | i2c_i801   | [DEB1C6D3C8](<All In One/BESSTAR Tech/U/U700/DA83D1618698/OPENMANDRIVA-23.01/6.1.4-DESKTOP-1OMV2301/X86_64/DEB1C6D3C8>) |
| 8086:9da3 | 17aa:3145 | Intel            | Cannon Point-LP SMBus Controller     | 10    | i2c_i801   | [FAEB46556E](<All In One/Lenovo/V540-24IWL/V540-24IWL AIO 10YS0031RU/886440AA02F6/KOMETA-P10/5.10.102-STD-DEF-ALT1/X86_64/FAEB46556E>) |
| 8086:a123 | 1028:06c5 | Intel            | 100 Series/C230 Series Chipset Fa... | 10    | i2c_i801   | [5B29ED7213](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/BE925566CC9F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5B29ED7213>) |
| 1022:790b | 1022:790b | AMD              | FCH SMBus Controller                 | 9     | i2c_pii... | [1AC75759CE](<All In One/GPD/G1618/G1618-04/62DB29AA1271/DEBIAN-12/6.1.0-7-AMD64/X86_64/1AC75759CE>) |
| 8086:1c22 | 17aa:366c | Intel            | 6 Series/C200 Series Chipset Fami... | 9     | i2c_i801   | [55C11B6B87](<All In One/Lenovo/C540/C540 10110/D5261210E56A/OPENMANDRIVA-4.50/5.12.4-DESKTOP-1OMV4050/X86_64/55C11B6B87>) |
| 8086:3b30 | 17aa:306a | Intel            | 5 Series/3400 Series Chipset SMBu... | 9     | i2c_i801   | [ED812A8A26](<All In One/Lenovo/ThinkCentre/ThinkCentre M90z 5205W5Q/2D0BC11CA89A/LINUXMINT-21.1/5.15.0-58-GENERIC/X86_64/ED812A8A26>) |
| 8086:7aa3 |           | Intel            | Alder Lake-S PCH SMBus Controller    | 9     | i2c_i801   | [E734B33010](<All In One/Graviton/D12/D12i/E65E993A1E87/ALT-10.1/5.15.104-UN-DEF-ALT1/X86_64/E734B33010>) |
| 8086:9d23 | 8086:7270 | Intel            | Sunrise Point-LP SMBus               | 9     | i2c_i801   | [426C7D7939](<All In One/Apple/iMac18/iMac18,1/61AC5215756C/XUBUNTU-22.04/5.19.0-35-GENERIC/X86_64/426C7D7939>) |
| 8086:1c22 | 104d:907e | Intel            | 6 Series/C200 Series Chipset Fami... | 8     | i2c_i801   | [0451CAEB29](<All In One/Sony/VPCL212/VPCL212FX/01EE677E7F92/UBUNTU-21.10/5.13.0-22-GENERIC/X86_64/0451CAEB29>) |
| 8086:34a3 | 1025:1418 | Intel            | Ice Lake-LP SMBus Controller         | 8     | i2c_i801   | [A82A90955E](<All In One/Acer/Aspire/Aspire C27-962/563F493FD77F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/A82A90955E>) |
| 8086:9ca2 | 8086:7270 | Intel            | Wildcat Point-LP SMBus Controller    | 8     | i2c_i801   | [44B9054B8C](<All In One/Apple/iMac16/iMac16,1/FCCB3A22541B/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/44B9054B8C>) |
| 8086:a123 | 103c:2b3e | Intel            | 100 Series/C230 Series Chipset Fa... | 8     | i2c_i801   | [70F8CE05B6](<All In One/Hewlett-Packard/24/24-n000ny/C2F705DD30EA/UBUNTU-20.04/5.15.0-69-GENERIC/X86_64/70F8CE05B6>) |
| 8086:0f12 | 17aa:3695 | Intel            | Atom Processor E3800/CE2700 Serie... | 7     | i2c_i801   | [B6C7B47859](<All In One/Lenovo/C260/C260 10160/399A2B69BAD6/LINUXMINT-21/5.15.0-56-GENERIC/X86_64/B6C7B47859>) |
| 8086:0f12 | 1854:0200 | Intel            | Atom Processor E3800/CE2700 Serie... | 7     | i2c_i801   | [163C52FD3C](<All In One/LG Electronics/22V240/22V240-L.AK35B2/3689BD3EEE5E/MANJARO-22.0.4/6.1.12-1-MANJARO/X86_64/163C52FD3C>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c20 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 170   | snd_hda... | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 8086:284b | 106b:00a0 | Intel            | 82801H (ICH8 Family) HD Audio Con... | 155   | snd_hda... | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 10de:0ac0 | 10de:cb79 | Nvidia           | MCP79 High Definition Audio          | 128   | snd_hda... | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 1002:aa90 | 106b:aa90 | AMD              | Turks HDMI Audio [Radeon HD 6500/... | 127   | snd_hda... | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 8086:8c20 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset High... | 89    | snd_hda... | [00D8186404](<All In One/Apple/iMac14/iMac14,2/6ABD34C5E7DF/UBUNTU-22.04/5.15.0-33-GENERIC/X86_64/00D8186404>) |
| 8086:a170 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 89    | snd_hda... | [EE288626F4](<All In One/Apple/iMac18/iMac18,3/85F2F89AFF57/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/EE288626F4>) |
| 8086:3b56 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset High... | 86    | snd_hda... | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 1002:aa38 | 106b:aa38 | AMD              | RV710/730 HDMI Audio [Radeon HD 4... | 59    | snd_hda... | [F0EA43F3FD](<All In One/Apple/iMac11/iMac11,2/40AA4B37D450/ZORIN-15/5.4.0-146-GENERIC/X86_64/F0EA43F3FD>) |
| 1002:aae0 | 1002:aae0 | AMD              | Baffin HDMI/DP Audio [Radeon RX 5... | 59    | snd_hda... | [0F3F45F8E9](<All In One/Apple/iMac19/iMac19,2/5322EAC8B99B/PARROT-5.2/6.0.0-12PARROT1-AMD64/X86_64/0F3F45F8E9>) |
| 8086:a348 | 8086:7270 | Intel            | Cannon Lake PCH cAVS                 | 51    | snd_hda... | [0F3F45F8E9](<All In One/Apple/iMac19/iMac19,2/5322EAC8B99B/PARROT-5.2/6.0.0-12PARROT1-AMD64/X86_64/0F3F45F8E9>) |
| 1002:aaf0 | 1002:aaf0 | AMD              | Ellesmere HDMI Audio [Radeon RX 4... | 50    | snd_hda... | [EE288626F4](<All In One/Apple/iMac18/iMac18,3/85F2F89AFF57/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/EE288626F4>) |
| 8086:1e20 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family High... | 49    | snd_hda... | [C8C9C1E591](<All In One/Apple/iMac13/iMac13,1/ED988FB747CF/DEBIAN-11/5.10.0-21-AMD64/X86_64/C8C9C1E591>) |
| 1002:aa88 | 106b:aa88 | AMD              | Barts HDMI Audio [Radeon HD 6790/... | 40    | snd_hda... | [081ECD2050](<All In One/Apple/iMac12/iMac12,2/E37CB5F9125E/LINUXMINT-21.1/5.15.0-67-GENERIC/X86_64/081ECD2050>) |
| 10de:0e1b |           | Nvidia           | GK107 HDMI Audio Controller          | 28    | snd_hda... | [00D8186404](<All In One/Apple/iMac14/iMac14,2/6ABD34C5E7DF/UBUNTU-22.04/5.15.0-33-GENERIC/X86_64/00D8186404>) |
| 8086:27d8 | 8384:7680 | Intel            | NM10/ICH7 Family High Definition ... | 28    | snd_hda... | [C7444AC7F0](<All In One/Apple/iMac5/iMac5,1/104264B0BD86/XUBUNTU-22.04/5.15.0-70-GENERIC/X86_64/C7444AC7F0>) |
| 8086:0d0c | 106b:0122 | Intel            | Crystal Well HD Audio Controller     | 26    | snd_hda... | [0A7DBD4CC4](<All In One/Apple/iMac14/iMac14,1/BBFFFA015602/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/0A7DBD4CC4>) |
| 1002:aa58 | 106b:aa58 | AMD              | Juniper HDMI Audio [Radeon HD 570... | 25    | snd_hda... | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 10de:0e1b | 106b:0109 | Nvidia           | GK107 HDMI Audio Controller          | 24    | snd_hda... | [D458AE07B2](<All In One/Apple/iMac13/iMac13,1/151F107DD0F7/CLEAR-LINUX-OS-37980/6.1.2-1232.NATIVE/X86_64/D458AE07B2>) |
| 10de:0e0a |           | Nvidia           | GK104 HDMI Audio Controller          | 22    | snd_hda... | [94468C31E6](<All In One/Apple/iMac14/iMac14,2/112420488415/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/94468C31E6>) |
| 8086:a2f0 | 1019:a5a1 | Intel            | 200 Series PCH HD Audio              | 22    | snd_hda... | [63DBB9394E](<All In One/ICL/RAY/RAY S122.Mi/767FFC5AB7B5/ALT-8.4/5.10.83-STD-DEF-ALT0.C9F.2/X86_64/63DBB9394E>) |
| 1002:aa30 | 106b:aa30 | AMD              | RV770 HDMI Audio [Radeon HD 4850/... | 21    | snd_hda... | [8D37E3E327](<All In One/Apple/iMac11/iMac11,1/60F7DB707519/UBUNTU-22.04/5.15.0-53-GENERIC/X86_64/8D37E3E327>) |
| 8086:160c | 106b:014f | Intel            | Broadwell-U Audio Controller         | 19    | snd_hda... | [570077AA64](<All In One/Apple/iMac16/iMac16,2/2D4E89D37302/ZORIN-16/5.15.0-69-GENERIC/X86_64/570077AA64>) |
| 8086:8ca0 | 8086:7270 | Intel            | 9 Series Chipset Family HD Audio ... | 19    | snd_hda... | [570077AA64](<All In One/Apple/iMac16/iMac16,2/2D4E89D37302/ZORIN-16/5.15.0-69-GENERIC/X86_64/570077AA64>) |
| 1002:9840 | 103c:8245 | AMD              | Kabini HDMI/DP Audio                 | 17    | snd_hda... | [81F625006B](<All In One/Hewlett-Packard/24/24-g020/310803ED8E33/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/81F625006B>) |
| 1022:780d | 103c:8245 | AMD              | FCH Azalia Controller                | 17    | snd_hda... | [81F625006B](<All In One/Hewlett-Packard/24/24-g020/310803ED8E33/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/81F625006B>) |
| 8086:9d71 | 103c:84de | Intel            | Sunrise Point-LP HD Audio            | 17    | snd_hda... | [CDB6233482](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/13576610145B/DEBIAN-11/5.10.0-18-AMD64/X86_64/CDB6233482>) |
| 1002:aab0 | 0000:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 16    | snd_hda... | [BEE60F5725](<All In One/Apple/iMac15/iMac15,1/35F88A3CD118/ZORIN-16/5.15.0-43-GENERIC/X86_64/BEE60F5725>) |
| 8086:1c20 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 16    | snd_hda... | [D75E472005](<All In One/Lenovo/C440/C440 10104/983B023892A1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/D75E472005>) |
| 8086:0c0c | 1028:05a7 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 15    | snd_hda... | [757AE6AA73](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/099C9C0A02A0/DEBIAN-11/5.10.0-20-AMD64/X86_64/757AE6AA73>) |
| 8086:1c20 | 1028:0511 | Intel            | 6 Series/C200 Series Chipset Fami... | 15    | snd_hda... | [225E42D432](<All In One/Dell/Inspiron/Inspiron One 2320/D8B99273D539/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/225E42D432>) |
| 8086:8c20 | 1028:05a7 | Intel            | 8 Series/C220 Series Chipset High... | 15    | snd_hda... | [757AE6AA73](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/099C9C0A02A0/DEBIAN-11/5.10.0-20-AMD64/X86_64/757AE6AA73>) |
| 1002:aa60 | 106b:aa60 | AMD              | Redwood HDMI Audio [Radeon HD 500... | 14    | snd_hda... | [DBB3F8FA6F](<All In One/Apple/iMac11/iMac11,3/689DE043DB5E/ULTRAMARINE-37/6.2.9-200.FC37.X86_64/X86_64/DBB3F8FA6F>) |
| 8086:1e20 | 1028:0543 | Intel            | 7 Series/C216 Chipset Family High... | 14    | snd_hda... | [00CB2D66A8](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/42A1DEC89484/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/00CB2D66A8>) |
| 8086:1e20 | 1028:0548 | Intel            | 7 Series/C216 Chipset Family High... | 14    | snd_hda... | [22CBD67F5D](<All In One/Dell/Inspiron/Inspiron One 2330/C959D85DE508/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/22CBD67F5D>) |
| 8086:a348 | 103c:84ee | Intel            | Cannon Lake PCH cAVS                 | 14    | snd_hda... | [8E1245836B](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/B6DE3C8A8AED/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/8E1245836B>) |
| 1002:15b3 | 103c:8381 | AMD              | High Definition Audio Controller     | 13    | snd_hda... | [6745FD4BAC](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/EF305E495BCA/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/6745FD4BAC>) |
| 1002:15b3 | 103c:8430 | AMD              | High Definition Audio Controller     | 13    | snd_hda... | [B813F95C6F](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/3A989707384A/ZORIN-16/5.15.0-69-GENERIC/X86_64/B813F95C6F>) |
| 1022:157a | 103c:8381 | AMD              | Family 15h (Models 60h-6fh) Audio... | 13    | snd_hda... | [6745FD4BAC](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/EF305E495BCA/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/6745FD4BAC>) |
| 1022:157a | 103c:8430 | AMD              | Family 15h (Models 60h-6fh) Audio... | 13    | snd_hda... | [B813F95C6F](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/3A989707384A/ZORIN-16/5.15.0-69-GENERIC/X86_64/B813F95C6F>) |
| 8086:0a0c | 106b:013c | Intel            | Haswell-ULT HD Audio Controller      | 13    | snd_hda... | [6976F884E6](<All In One/Apple/iMac14/iMac14,4/6E7600BFDA83/LUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6976F884E6>) |
| 8086:0c0c | 1028:05db | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 13    | snd_hda... | [323E28FDED](<All In One/Dell/Inspiron/Inspiron 2350/07DCD03E083E/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/323E28FDED>) |
| 8086:2284 | 103c:81bb | Intel            | Atom/Celeron/Pentium Processor x5... | 13    | snd_hda... | [8C50716D55](<All In One/Hewlett-Packard/20/20-c012a/A9551DF58B53/LINUXMINT-20.3/5.4.0-148-GENERIC/X86_64/8C50716D55>) |
| 8086:8c20 | 1028:05db | Intel            | 8 Series/C220 Series Chipset High... | 13    | snd_hda... | [323E28FDED](<All In One/Dell/Inspiron/Inspiron 2350/07DCD03E083E/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/323E28FDED>) |
| 8086:9c20 | 8086:7270 | Intel            | 8 Series HD Audio Controller         | 13    | snd_hda... | [6976F884E6](<All In One/Apple/iMac14/iMac14,4/6E7600BFDA83/LUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6976F884E6>) |
| 8086:9d71 | 1025:1287 | Intel            | Sunrise Point-LP HD Audio            | 13    | snd_hda... | [EB0191F969](<All In One/Acer/Aspire/Aspire C22-865/2C5B66C0839A/MANJARO/6.1.1-1-MANJARO/X86_64/EB0191F969>) |
| 1002:15de | 1002:15de | AMD              | Raven/Raven2/Fenghuang HDMI/DP Au... | 12    | snd_hda... | [98E5C0BA37](<All In One/iRU/P2320/P2320P/D2E5AC71120D/RED-OS-7.3.2/5.15.87-1.EL7.3.X86_64/X86_64/98E5C0BA37>) |
| 1002:aac0 | 0000:aac0 | AMD              | Tobago HDMI Audio [Radeon R7 360 ... | 12    | snd_hda... | [8DD4721BD1](<All In One/Apple/iMac17/iMac17,1/4EE67D79224F/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/8DD4721BD1>) |
| 8086:0c0c | 8086:2010 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 12    | snd_hda... | [9A6102422F](<All In One/Lenovo/B50-30/B50-30 F0AU00EEIX/B1C1DD126C40/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/9A6102422F>) |
| 8086:1c20 | 103c:2ac5 | Intel            | 6 Series/C200 Series Chipset Fami... | 12    | snd_hda... | [B32F35A4B1](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/C0BF0A16B6D4/FEDORA-36/5.18.19-200.FC36.X86_64/X86_64/B32F35A4B1>) |
| 8086:3a3e | 1025:0266 | Intel            | 82801JI (ICH10 Family) HD Audio C... | 12    | snd_hda... | [8A9EDF5A44](<All In One/Acer/Aspire/Aspire Z5600/021BA2DCCB15/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/8A9EDF5A44>) |

### Storage (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1217:8331 | 1bcf:a013 | O2 Micro         | O2 Flash Memory Card                 | 2     |            | [1494683BB9](<All In One/NEC Computers/PC-VN770/PC-VN770DS3ER/18CEF0AA43DB/UBUNTU-20.04/5.8.0-48-GENERIC/X86_64/1494683BB9>) |
| 1106:401a | 17aa:3603 | VIA Technologies | Card Reader Host Controller          | 1     |            | [8399296D51](<All In One/Lenovo/IdeaCentre/IdeaCentre B305 10052/A8184A7A8382/UBUNTU-20.04/5.8.0-55-GENERIC/X86_64/8399296D51>) |
| 1106:401a | 17aa:3608 | VIA Technologies | Card Reader Host Controller          | 1     |            | [69574214D7](<All In One/Lenovo/IdeaCentre/IdeaCentre A700 10050/51968677EC4C/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/69574214D7>) |
| 1217:8130 | 1033:8959 | O2 Micro         | Integrated MS/MSPRO/xD Controller    | 1     |            | [6F4A2D24C1](<All In One/NEC Computers/PC-VW770/PC-VW770CS6B/CD4FBB5FF80F/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/6F4A2D24C1>) |
| 1217:8130 | 17aa:3068 | O2 Micro         | Integrated MS/MSPRO/xD Controller    | 1     |            | [27E7D42D53](<All In One/Lenovo/Others/Others/18DB28A21724/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/27E7D42D53>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c02 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 166   | ahci       | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 8086:2829 | 106b:00a0 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) SATA ... | 142   | ahci       | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 10de:0ab9 | 10de:cb79 | Nvidia           | MCP79 AHCI Controller                | 116   | ahci       | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 8086:a102 | 8086:7270 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 89    | ahci       | [EE288626F4](<All In One/Apple/iMac18/iMac18,3/85F2F89AFF57/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/EE288626F4>) |
| 8086:3b22 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset 6 po... | 83    | ahci       | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 8086:8c02 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 57    | ahci       | [00D8186404](<All In One/Apple/iMac14/iMac14,2/6ABD34C5E7DF/UBUNTU-22.04/5.15.0-33-GENERIC/X86_64/00D8186404>) |
| 8086:a352 | 8086:7270 | Intel            | Cannon Lake PCH SATA AHCI Controller | 51    | ahci       | [0F3F45F8E9](<All In One/Apple/iMac19/iMac19,2/5322EAC8B99B/PARROT-5.2/6.0.0-12PARROT1-AMD64/X86_64/0F3F45F8E9>) |
| 8086:1e02 | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 49    | ahci       | [C8C9C1E591](<All In One/Apple/iMac13/iMac13,1/ED988FB747CF/DEBIAN-11/5.10.0-21-AMD64/X86_64/C8C9C1E591>) |
| 8086:8c03 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 26    | ahci       | [0A7DBD4CC4](<All In One/Apple/iMac14/iMac14,1/BBFFFA015602/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/0A7DBD4CC4>) |
| 144d:a801 | 144d:a801 | Samsung Elect... | Electronics SATA controller          | 22    | ahci       | [F1227EA669](<All In One/Apple/iMac17/iMac17,1/F277E8B7B5D8/UBUNTU-22.04/6.2.12-060212-GENERIC/X86_64/F1227EA669>) |
| 8086:a282 | 1019:a5a1 | Intel            | 200 Series PCH SATA controller [A... | 22    | ahci       | [63DBB9394E](<All In One/ICL/RAY/RAY S122.Mi/767FFC5AB7B5/ALT-8.4/5.10.83-STD-DEF-ALT0.C9F.2/X86_64/63DBB9394E>) |
| 1b4b:9183 | 1b4b:9183 | Marvell Techn... | 88SS9183 PCIe SSD Controller         | 19    | ahci       | [DC411C9CE3](<All In One/Apple/iMac14/iMac14,1/039462E853A9/POP!_OS-22.04/6.2.0-76060200-GENERIC/X86_64/DC411C9CE3>) |
| 1022:7801 | 103c:8245 | AMD              | FCH SATA Controller [AHCI mode]      | 17    | ahci       | [81F625006B](<All In One/Hewlett-Packard/24/24-g020/310803ED8E33/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/81F625006B>) |
| 8086:8c83 | 8086:7270 | Intel            | 9 Series Chipset Family SATA Cont... | 17    | ahci       | [570077AA64](<All In One/Apple/iMac16/iMac16,2/2D4E89D37302/ZORIN-16/5.15.0-69-GENERIC/X86_64/570077AA64>) |
| 8086:1c02 | 1028:0511 | Intel            | 6 Series/C200 Series Chipset Fami... | 15    | ahci       | [225E42D432](<All In One/Dell/Inspiron/Inspiron One 2320/D8B99273D539/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/225E42D432>) |
| 8086:1c02 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 15    | ahci       | [D75E472005](<All In One/Lenovo/C440/C440 10104/983B023892A1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/D75E472005>) |
| 8086:1e02 | 1028:0543 | Intel            | 7 Series/C210 Series Chipset Fami... | 14    | ahci       | [00CB2D66A8](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/42A1DEC89484/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/00CB2D66A8>) |
| 1022:7901 | 103c:8430 | AMD              | FCH SATA Controller [AHCI mode]      | 13    | ahci       | [B813F95C6F](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/3A989707384A/ZORIN-16/5.15.0-69-GENERIC/X86_64/B813F95C6F>) |
| 8086:1e02 | 1028:0548 | Intel            | 7 Series/C210 Series Chipset Fami... | 13    | ahci       | [22CBD67F5D](<All In One/Dell/Inspiron/Inspiron One 2330/C959D85DE508/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/22CBD67F5D>) |
| 8086:22a3 | 103c:81bb | Intel            | Atom/Celeron/Pentium Processor x5... | 13    | ahci       | [8C50716D55](<All In One/Hewlett-Packard/20/20-c012a/A9551DF58B53/LINUXMINT-20.3/5.4.0-148-GENERIC/X86_64/8C50716D55>) |
| 8086:9d03 | 1025:1287 | Intel            | Sunrise Point-LP SATA Controller ... | 13    | ahci       | [EB0191F969](<All In One/Acer/Aspire/Aspire C22-865/2C5B66C0839A/MANJARO/6.1.1-1-MANJARO/X86_64/EB0191F969>) |
| 8086:9d03 | 103c:84de | Intel            | Sunrise Point-LP SATA Controller ... | 13    | ahci       | [CDB6233482](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/13576610145B/DEBIAN-11/5.10.0-18-AMD64/X86_64/CDB6233482>) |
| 1022:7901 | 1022:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 12    | ahci       | [13A42307A4](<All In One/Acidanthera/iMacPro1/iMacPro1,1/CCEF88A1D848/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/13A42307A4>) |
| 1022:7901 | 103c:8381 | AMD              | FCH SATA Controller [AHCI mode]      | 12    | ahci       | [6745FD4BAC](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/EF305E495BCA/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/6745FD4BAC>) |
| 8086:1c02 | 103c:2ac5 | Intel            | 6 Series/C200 Series Chipset Fami... | 12    | ahci       | [B32F35A4B1](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/C0BF0A16B6D4/FEDORA-36/5.18.19-200.FC36.X86_64/X86_64/B32F35A4B1>) |
| 8086:31e3 | 1025:1304 | Intel            | Celeron/Pentium Silver Processor ... | 12    | ahci       | [07D4BF17AA](<All In One/Acer/Aspire/Aspire C22-820/D247EFB9442C/ROSA-12.3/5.10.155-GENERIC-1ROSA2021.1-X86_64/X86_64/07D4BF17AA>) |
| 8086:3a22 | 1025:0266 | Intel            | 82801JI (ICH10 Family) SATA AHCI ... | 12    | ahci       | [8A9EDF5A44](<All In One/Acer/Aspire/Aspire Z5600/021BA2DCCB15/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/8A9EDF5A44>) |
| 8086:9d03 | 8086:9d03 | Intel            | Sunrise Point-LP SATA Controller ... | 12    | ahci       | [557E50987C](<All In One/ASUSTek Computer/ZN240/ZN240IC/A4EB8493DB43/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/557E50987C>) |
| 8086:a352 | 103c:84ee | Intel            | Cannon Lake PCH SATA AHCI Controller | 12    | ahci       | [8E1245836B](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/B6DE3C8A8AED/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/8E1245836B>) |
| 10de:0ad4 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] AHCI Contro... | 11    | ahci       | [E0B8F5D54B](<All In One/Acer/Aspire/Aspire Z3101/B30C614DB765/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/E0B8F5D54B>) |
| 8086:8c03 | 1028:05db | Intel            | 8 Series/C220 Series Chipset Fami... | 11    | ahci       | [D32909E1A4](<All In One/Dell/Inspiron/Inspiron 2350/537D2F43CC7A/MX-21/5.10.0-19-AMD64/X86_64/D32909E1A4>) |
| 8086:9c03 | 8086:7270 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 11    | ahci       | [6976F884E6](<All In One/Apple/iMac14/iMac14,4/6E7600BFDA83/LUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6976F884E6>) |
| 1022:7801 | 103c:2b3b | AMD              | FCH SATA Controller [AHCI mode]      | 10    | ahci       | [CB25C51987](<All In One/Hewlett-Packard/23/23-r155la/F1B498CB86AC/ZORIN-16/5.15.0-60-GENERIC/X86_64/CB25C51987>) |
| 1022:7901 | 103c:86f3 | AMD              | FCH SATA Controller [AHCI mode]      | 10    | ahci       | [DC3ADE850C](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-df0xxx/149EB6B30B69/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/DC3ADE850C>) |
| 8086:31e3 | 1854:0308 | Intel            | Celeron/Pentium Silver Processor ... | 10    | ahci       | [EC912EFB6F](<All In One/LG Electronics/22V280/22V280-L.BJ31P1/925F8D37ECFF/FEDORA-37/6.0.12-300.FC37.X86_64/X86_64/EC912EFB6F>) |
| 8086:9c83 | 8086:9c83 | Intel            | Wildcat Point-LP SATA Controller ... | 10    | ahci       | [DEB1C6D3C8](<All In One/BESSTAR Tech/U/U700/DA83D1618698/OPENMANDRIVA-23.01/6.1.4-DESKTOP-1OMV2301/X86_64/DEB1C6D3C8>) |
| 8086:9dd3 | 17aa:3145 | Intel            | Cannon Point-LP SATA Controller [... | 10    | ahci       | [FAEB46556E](<All In One/Lenovo/V540-24IWL/V540-24IWL AIO 10YS0031RU/886440AA02F6/KOMETA-P10/5.10.102-STD-DEF-ALT1/X86_64/FAEB46556E>) |
| 8086:7ae2 |           | Intel            | Alder Lake-S PCH SATA Controller ... | 9     | ahci       | [E734B33010](<All In One/Graviton/D12/D12i/E65E993A1E87/ALT-10.1/5.15.104-UN-DEF-ALT1/X86_64/E734B33010>) |
| 8086:9d03 | 8086:7270 | Intel            | Sunrise Point-LP SATA Controller ... | 9     | ahci       | [426C7D7939](<All In One/Apple/iMac18/iMac18,1/61AC5215756C/XUBUNTU-22.04/5.19.0-35-GENERIC/X86_64/426C7D7939>) |
| 8086:1c02 | 17aa:366c | Intel            | 6 Series/C200 Series Chipset Fami... | 8     | ahci       | [55C11B6B87](<All In One/Lenovo/C540/C540 10110/D5261210E56A/OPENMANDRIVA-4.50/5.12.4-DESKTOP-1OMV4050/X86_64/55C11B6B87>) |
| 8086:1c03 | 104d:907e | Intel            | 6 Series/C200 Series Chipset Fami... | 8     | ahci       | [0451CAEB29](<All In One/Sony/VPCL212/VPCL212FX/01EE677E7F92/UBUNTU-21.10/5.13.0-22-GENERIC/X86_64/0451CAEB29>) |
| 8086:3b22 | 17aa:306a | Intel            | 5 Series/3400 Series Chipset 6 po... | 8     | ahci       | [ED812A8A26](<All In One/Lenovo/ThinkCentre/ThinkCentre M90z 5205W5Q/2D0BC11CA89A/LINUXMINT-21.1/5.15.0-58-GENERIC/X86_64/ED812A8A26>) |
| 8086:8c02 | 1028:0626 | Intel            | 8 Series/C220 Series Chipset Fami... | 8     | ahci       | [9348834E54](<All In One/Dell/Inspiron/Inspiron 23 Model 5348/5251BCB7D469/FEDORA-37/6.2.9-200.FC37.X86_64/X86_64/9348834E54>) |
| 8086:9c83 | 8086:7270 | Intel            | Wildcat Point-LP SATA Controller ... | 8     | ahci       | [44B9054B8C](<All In One/Apple/iMac16/iMac16,1/FCCB3A22541B/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/44B9054B8C>) |
| 8086:a102 | 103c:2b3e | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 8     | ahci       | [70F8CE05B6](<All In One/Hewlett-Packard/24/24-n000ny/C2F705DD30EA/UBUNTU-20.04/5.15.0-69-GENERIC/X86_64/70F8CE05B6>) |
| 1002:4391 | 1028:0479 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 7     | ahci       | [E0FD42AC99](<All In One/Dell/Inspiron/Inspiron One 2305/CCF514D6F2CB/UBUNTU-22.10/5.19.0-31-GENERIC/X86_64/E0FD42AC99>) |
| 8086:0f23 | 17aa:3695 | Intel            | Atom Processor E3800 Series SATA ... | 7     | ahci       | [B6C7B47859](<All In One/Lenovo/C260/C260 10160/399A2B69BAD6/LINUXMINT-21/5.15.0-56-GENERIC/X86_64/B6C7B47859>) |
| 8086:0f23 | 1854:0200 | Intel            | Atom Processor E3800 Series SATA ... | 7     | ahci       | [163C52FD3C](<All In One/LG Electronics/22V240/22V240-L.AK35B2/3689BD3EEE5E/MANJARO-22.0.4/6.1.12-1-MANJARO/X86_64/163C52FD3C>) |
| 8086:1e02 | 144d:b091 | Intel            | 7 Series/C210 Series Chipset Fami... | 7     | ahci       | [DD513D338C](<All In One/Samsung Electronics/DP700/DP700A3D-DM700A3D-DB701A3D-DP700A7D/F34D6AA53F0D/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/DD513D338C>) |
| 8086:31e3 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 7     | ahci       | [38C2A94BAA](<All In One/Positivo/C464/C464A-21/1A925F871EA8/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/38C2A94BAA>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2850 | 106b:00a0 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) IDE C... | 155   | pata_acpi  | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 8086:27df | 8086:7270 | Intel            | 82801G (ICH7 Family) IDE Controller  | 30    | pata_acpi  | [C7444AC7F0](<All In One/Apple/iMac5/iMac5,1/104264B0BD86/XUBUNTU-22.04/5.15.0-70-GENERIC/X86_64/C7444AC7F0>) |
| 8086:27c4 | 8086:7270 | Intel            | 82801GBM/GHM (ICH7-M Family) SATA... | 27    | pata_acpi  | [C7444AC7F0](<All In One/Apple/iMac5/iMac5,1/104264B0BD86/XUBUNTU-22.04/5.15.0-70-GENERIC/X86_64/C7444AC7F0>) |
| 8086:2828 | 106b:00a0 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) SATA ... | 16    | pata_acpi  | [2362D1FD43](<All In One/Apple/iMac8/iMac8,1/9D1566A14C73/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/2362D1FD43>) |
| 10de:0ab5 | 10de:cb79 | Nvidia           | MCP79 SATA Controller                | 12    | ahci, p... | [61EFBD972C](<All In One/Apple/iMac10/iMac10,1/CAF53DC8E408/UBUNTU-20.04/4.15.0-206-GENERIC/X86_64/61EFBD972C>) |
| 8086:3a20 | 104d:9060 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 10    | pata_acpi  | [57E0224FFD](<All In One/Sony/VPCL13/VPCL13M1R/82175A598A60/RELD-7.9/5.15.33-1.RES7.X86_64/X86_64/57E0224FFD>) |
| 1002:439c | 1002:439c | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 8     | pata_at... | [2278A5C6EA](<All In One/Samsung Electronics/SUR/SUR40/9A8E67BB1389/DEBIAN-11/5.19.0-2-AMD64/X86_64/2278A5C6EA>) |
| 1002:439c | 17aa:3629 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 5     | pata_at... | [861AF1FD97](<All In One/Lenovo/C/C325/A63CECA79035/DEBIAN-11/5.10.0-18-AMD64/X86_64/861AF1FD97>) |
| 8086:27c0 | 17aa:3602 | Intel            | NM10/ICH7 Family SATA Controller ... | 5     | ata_pii... | [195EC7CB8C](<All In One/Lenovo/10051/10051/11244BE45969/LINUXMINT-20.3/5.4.0-126-GENERIC/X86_64/195EC7CB8C>) |
| 8086:1c00 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 4     | ata_piix   | [B31C3EE2D6](<All In One/Apple/iMac12/iMac12,2/A10E03582323/OPENSUSE-LEAP-15.3/5.3.18-59.27-PREEMPT/X86_64/B31C3EE2D6>) |
| 8086:27c0 | 17aa:3610 | Intel            | NM10/ICH7 Family SATA Controller ... | 4     | ata_pii... | [5D8EF57728](<All In One/Lenovo/C/C200/3278BC0AB6A5/ROSA-2016.1/4.15.0-DESKTOP-94.1ROSA-I586/I686/5D8EF57728>) |
| 8086:3a20 | 104d:9044 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 4     | pata_acpi  | [3ED1AD79E4](<All In One/Sony/VGC-JS54/VGC-JS54FB_W/1013B0577913/LINUX-LITE-6.0/5.16.9/X86_64/3ED1AD79E4>) |
| 8086:3b20 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset 4 po... | 4     | ata_piix   | [DCA4C898F8](<All In One/Apple/iMac11/iMac11,2/64489F9C6F44/ELEMENTARY-6.1/5.15.0-41-GENERIC/X86_64/DCA4C898F8>) |
| 10de:0759 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] IDE            | 3     | pata_am... | [E0B8F5D54B](<All In One/Acer/Aspire/Aspire Z3101/B30C614DB765/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/E0B8F5D54B>) |
| 8086:1c01 | 1bcf:a013 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | pata_acpi  | [1494683BB9](<All In One/NEC Computers/PC-VN770/PC-VN770DS3ER/18CEF0AA43DB/UBUNTU-20.04/5.8.0-48-GENERIC/X86_64/1494683BB9>) |
| 8086:1c3c | 103c:3561 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | ata_gen... | [7AF1912AB7](<All In One/Hewlett-Packard/Z1/Z1 Workstation/4089A5726DF1/FEDORA-37/6.0.9-300.FC37.X86_64/X86_64/7AF1912AB7>) |
| 8086:1e01 | 17aa:3671 | Intel            | 7 Series Chipset Family 4-port SA... | 2     | ata_pii... | [906A62D75E](<All In One/Lenovo/C240/C240 10113/52E2D6BDB71D/UBUNTU-16.04/4.15.0-55-GENERIC/I686/906A62D75E>) |
| 8086:1e09 | 17aa:3671 | Intel            | 7 Series Chipset Family 2-port SA... | 2     | ata_pii... | [906A62D75E](<All In One/Lenovo/C240/C240 10113/52E2D6BDB71D/UBUNTU-16.04/4.15.0-55-GENERIC/I686/906A62D75E>) |
| 8086:27c0 | 1462:a912 | Intel            | NM10/ICH7 Family SATA Controller ... | 2     | pata_acpi  | [B8B4472592](<All In One/MSI/MS-A/MS-A912/F92BE636D295/DEBIAN-10/4.8.0-2-AMD64/X86_64/B8B4472592>) |
| 8086:27c4 | 1025:025a | Intel            | 82801GBM/GHM (ICH7-M Family) SATA... | 2     | pata_acpi  | [CA89C2F311](<All In One/eMachines/EZ/EZ1600/E4B9D799E916/UBUNTU-MATE-18.04/5.4.0-65-GENERIC/I686/CA89C2F311>) |
| 8086:3a20 | 104d:9043 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 2     | pata_acpi  | [AFA509714D](<All In One/Sony/VGC-LN52/VGC-LN52JGB/54F15FF48E03/UBUNTU-20.04/5.8.0-54-GENERIC/X86_64/AFA509714D>) |
| 8086:3b28 | 17aa:360e | Intel            | 5 Series/3400 Series Chipset 4 po... | 2     | ata_piix   | [8F25ED4108](<All In One/Lenovo/IdeaCentre/IdeaCentre A310 10056/1F51DDDCDF1C/LINUXMINT-19.3/5.4.0-77-GENERIC/X86_64/8F25ED4108>) |
| 8086:8c00 | 1028:0626 | Intel            | 8 Series/C220 Series Chipset Fami... | 2     | ata_piix   | [7C368B59B2](<All In One/Dell/Inspiron/Inspiron 23 Model 5348/3C5294CCE601/STORM-OS-20.7/5.16.13-ARCH1-1/X86_64/7C368B59B2>) |
| 8086:8c00 | 1b0a:0183 | Intel            | 8 Series/C220 Series Chipset Fami... | 2     | ata_pii... | [78D39E18EF](<All In One/Pegatron/H81/H81-P1/1DBAFEC13877/UBUNTU-18.04/4.15.0-43-GENERIC/X86_64/78D39E18EF>) |
| 8086:8c08 | 1b0a:0183 | Intel            | 8 Series/C220 Series Chipset Fami... | 2     | ata_pii... | [78D39E18EF](<All In One/Pegatron/H81/H81-P1/1DBAFEC13877/UBUNTU-18.04/4.15.0-43-GENERIC/X86_64/78D39E18EF>) |
| 1002:438c | 1033:886f | AMD              | SB600 IDE                            | 1     | pata_at... | [86771347FB](<All In One/NEC Computers/PC-GV58/PC-GV58ZYCAA/96538F2FC249/UBUNTU-19.04/5.0.0-13-GENERIC/X86_64/86771347FB>) |
| 1002:439c | 1462:aa53 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 1     | pata_at... | [7BD55BD71D](<All In One/MSI/MS-AA/MS-AA53/738F36889CD9/MANJARO/4.19.34-1-MANJARO/X86_64/7BD55BD71D>) |
| 1022:780c | 103c:2b26 | AMD              | FCH IDE Controller                   | 1     | pata_at... | [DEC1B9E40F](<All In One/Hewlett-Packard/23/23-p132la/CD7770B0F855/GENTOO-2.8/5.15.69-GENTOO/X86_64/DEC1B9E40F>) |
| 1022:780c | 1043:8589 | AMD              | FCH IDE Controller                   | 1     | pata_at... | [C8D8836613](<All In One/ASUSTek Computer/ET2221/ET2221A/27768DCF5E7B/UBUNTU-18.04/4.15.0-54-GENERIC/X86_64/C8D8836613>) |
| 1022:780c | 1458:b001 | AMD              | FCH IDE Controller                   | 1     | pata_at... | [1DC2419A21](<All In One/Gigabyte Technology/GB-A5/GB-A5DNK-RH/2D59EF3CA1FB/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/1DC2419A21>) |
| 10de:0ab5 | 1043:8379 | Nvidia           | MCP79 SATA Controller                | 1     | ahci, p... | [72365E4985](<All In One/ASUSTek Computer/ET/ET2002/9AD492BE589B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/72365E4985>) |
| 197b:2363 | 1462:ae11 | JMicron Techn... | JMB363 SATA/IDE Controller           | 1     | ahci       | [17AD880F72](<All In One/MSI/MS-AE/MS-AE1111/D998FCCDF4CE/ROSA-2016.1/4.9.124-NRJ-DESKTOP-1ROSA-X86_64/X86_64/17AD880F72>) |
| 197b:2363 | 197b:2363 | JMicron Techn... | JMB363 SATA/IDE Controller           | 1     | ahci       | [8ADEBB44D3](<All In One/Acer/Veriton/Veriton Z4860G/87F793395C72/ALT-9.1/5.4.51-STD-DEF-ALT1/X86_64/8ADEBB44D3>) |
| 8086:0f21 |           | Intel            | Atom Processor E3800 Series SATA ... | 1     | ata_piix   | [B3E778A640](<All In One/Acer/Aspire/Aspire Z1-601/502836ED0FF7/POP!_OS-20.04/5.4.0-7634-GENERIC/X86_64/B3E778A640>) |
| 8086:0f21 | 1025:085f | Intel            | Atom Processor E3800 Series SATA ... | 1     | ata_pii... | [7923ACCECA](<All In One/Acer/Aspire/Aspire ZC-606/5D8E49197BD5/ROSA-2014.1/3.14.44-NRJ-DESKTOP-2ROSA-X86_64/X86_64/7923ACCECA>) |
| 8086:1c00 | 1025:0593 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pata_acpi  | [139C780029](<All In One/Acer/Z/Z2621G/98000EE3CE57/UBUNTU-22.04/5.15.0-30-GENERIC/X86_64/139C780029>) |
| 8086:1c00 | 1025:0618 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pata_acpi  | [B8E61A53BD](<All In One/Gateway/ZX/ZX6971/2A2802F2406C/UBUNTU-18.04/5.3.0-45-GENERIC/X86_64/B8E61A53BD>) |
| 8086:1c00 | 1025:0641 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pata_acpi  | [0B0D526E89](<All In One/Acer/Veriton/Veriton Z4630G/310398820220/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/0B0D526E89>) |
| 8086:1c00 | 103c:2aed | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ata_pii... | [E2ADA83EE9](<All In One/Hewlett-Packard/HP3520/HP3520 Aio/85A474C6BFEC/ROSA-2016.1/4.9.20-NRJ-DESKTOP-1ROSA-X86_64/X86_64/E2ADA83EE9>) |
| 8086:1c00 | 1458:b005 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ata_pii... | [A965900724](<All In One/Gigabyte Technology/H61/H61M-DS2/763FAF752932/MANJARO-21.2.1/5.10.81-1-MULTIMEDIA-LTS/X86_64/A965900724>) |
| 8086:1c00 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ata_pii... | [098D8022D0](<All In One/Lenovo/C/C430/C3D6B501559D/ROSA-2014.1/3.14.44-NRJ-DESKTOP-2ROSA-I586/I686/098D8022D0>) |
| 8086:1c00 | 17aa:366c | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pata_acpi  | [37F3D75177](<All In One/Lenovo/C540/C540 10110/34F5C2F40072/XUBUNTU-22.04/5.16.9-051609-GENERIC/X86_64/37F3D75177>) |
| 8086:1c08 | 1025:0593 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pata_acpi  | [139C780029](<All In One/Acer/Z/Z2621G/98000EE3CE57/UBUNTU-22.04/5.15.0-30-GENERIC/X86_64/139C780029>) |
| 8086:1c08 | 1025:0618 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pata_acpi  | [B8E61A53BD](<All In One/Gateway/ZX/ZX6971/2A2802F2406C/UBUNTU-18.04/5.3.0-45-GENERIC/X86_64/B8E61A53BD>) |
| 8086:1c08 | 1025:0641 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pata_acpi  | [0B0D526E89](<All In One/Acer/Veriton/Veriton Z4630G/310398820220/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/0B0D526E89>) |
| 8086:1c08 | 103c:2aed | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ata_pii... | [E2ADA83EE9](<All In One/Hewlett-Packard/HP3520/HP3520 Aio/85A474C6BFEC/ROSA-2016.1/4.9.20-NRJ-DESKTOP-1ROSA-X86_64/X86_64/E2ADA83EE9>) |
| 8086:1c08 | 1458:b002 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ata_pii... | [A965900724](<All In One/Gigabyte Technology/H61/H61M-DS2/763FAF752932/MANJARO-21.2.1/5.10.81-1-MULTIMEDIA-LTS/X86_64/A965900724>) |
| 8086:1c08 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ata_pii... | [098D8022D0](<All In One/Lenovo/C/C430/C3D6B501559D/ROSA-2014.1/3.14.44-NRJ-DESKTOP-2ROSA-I586/I686/098D8022D0>) |
| 8086:1c08 | 8086:2011 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pata_acpi  | [37F3D75177](<All In One/Lenovo/C540/C540 10110/34F5C2F40072/XUBUNTU-22.04/5.16.9-051609-GENERIC/X86_64/37F3D75177>) |
| 8086:1e00 | 1028:0548 | Intel            | 7 Series/C210 Series Chipset Fami... | 1     | ata_piix   | [B94AB82BDC](<All In One/Dell/Inspiron/Inspiron One 2330/E16E7B80BE08/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/B94AB82BDC>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 55    | nvme       | [5FF8444666](<All In One/Acidanthera/iMac18/iMac18,1/BB56FB1A5393/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/5FF8444666>) |
| 144d:a806 | 144d:a801 | Samsung Elect... | Surface NVMe Controller              | 44    | nvme       | [EE288626F4](<All In One/Apple/iMac18/iMac18,3/85F2F89AFF57/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/EE288626F4>) |
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 31    | nvme       | [CA4C9D7E6C](<All In One/Apple/iMac18/iMac18,3/C69792706D66/UBUNTU-22.10/5.19.0-40-GENERIC/X86_64/CA4C9D7E6C>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980              | 23    | nvme       | [8CF49B59A5](<All In One/Lenovo/V130-20IGM/V130-20IGM AIO 10RX004PSP/516826CB41E7/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/8CF49B59A5>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013 E13 NVMe Controller           | 16    | nvme       | [B13E626D1A](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/8BDE9218D7A8/UBUNTU-BUDGIE-22.04/5.15.0-27-GENERIC/X86_64/B13E626D1A>) |
| 1c5c:1327 | 1c5c:0000 | SK hynix         | BC501 NVMe Solid State Drive         | 15    | nvme       | [40BD947612](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-22ICB F0DT0002AX/05823FEB35B5/RED-OS-7.3.2/5.15.87-1.EL7.3.X86_64/X86_64/40BD947612>) |
| 1e0f:0001 | 1e0f:0001 | KIOXIA           | NVMe SSD Controller BG4              | 14    | nvme       | [E86753F364](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-d0xxx/C8F5FD68E798/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/E86753F364>) |
| 15b7:5003 | 15b7:5003 | SanDisk          | WD Blue SN500 / PC SN520 NVMe SSD    | 13    | nvme       | [D801E40F8C](<All In One/Acer/Aspire/Aspire C27-962/0D6785EE4B93/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/D801E40F8C>) |
| 15b7:5009 | 15b7:5009 | SanDisk          | WD Blue SN550 NVMe SSD               | 13    | nvme       | [13A42307A4](<All In One/Acidanthera/iMacPro1/iMacPro1,1/CCEF88A1D848/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/13A42307A4>) |
| 1c5c:174a | 1c5c:174a | SK hynix         | Gold P31/PC711 NVMe Solid State D... | 11    | nvme       | [C87417466C](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 27ITL6 F0FW00Q2RU/E4E2B81CA7F6/DEBIAN-11/5.10.0-21-AMD64/X86_64/C87417466C>) |
| 1c5c:1627 | 1c5c:1627 | SK hynix         | Non-Volatile memory controller       | 9     | nvme       | [FAEB46556E](<All In One/Lenovo/V540-24IWL/V540-24IWL AIO 10YS0031RU/886440AA02F6/KOMETA-P10/5.10.102-STD-DEF-ALT1/X86_64/FAEB46556E>) |
| 106b:2001 | 106b:2001 | Apple            | S1X NVMe Controller                  | 8     | nvme       | [15582A281D](<All In One/Apple/iMac16/iMac16,2/5E6F1890C476/UBUNTU-22.04/5.15.0-57-GENERIC/X86_64/15582A281D>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT SSD Controller     | 8     | nvme       | [4C3B90EDE8](<All In One/Graviton/M52/M52i/E9D47E018B4D/RED-OS-7.3.2/6.1.11-1.EL7.3.X86_64/X86_64/4C3B90EDE8>) |
| 1179:0113 | 1179:0001 | Toshiba Ameri... | BG3 NVMe SSD Controller              | 7     | nvme       | [8E1245836B](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/B6DE3C8A8AED/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/8E1245836B>) |
| 15b7:5008 | 15b7:5008 | SanDisk          | NVMe Controller                      | 7     | nvme       | [2BD3CDBC37](<All In One/Lenovo/AIO/AIO 3-22ADA05 F0EX003JRK/BA9C03EB4E8E/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/2BD3CDBC37>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 7     | nvme       | [D16F5CA08A](<All In One/Acidanthera/iMac20/iMac20,1/1EB5BA2AB9E0/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/D16F5CA08A>) |
| 8086:f1a8 | 8086:390d | Intel            | SSD 660P Series                      | 7     | nvme       | [C9F6D95FB2](<All In One/Hewlett-Packard/ProOne/ProOne 440 G5 23.8-in All-in-One/3714C25A2744/UBUNTU-MATE-22.10/5.19.0-31-GENERIC/X86_64/C9F6D95FB2>) |
| 1344:5410 | 1344:0100 | Micron Techno... | NVMe Storage Controller              | 6     | nvme       | [380754E2F6](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/89B6F2E5BC73/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/380754E2F6>) |
| 2646:5008 | 2646:5008 | Kingston Tech... | U-SNS8154P3 NVMe SSD                 | 6     | nvme       | [7B4EEEBDBC](<All In One/Acer/Aspire/Aspire C24-963/E4A4E93BCF0A/RED-OS-7.3/5.15.87-1.EL7.3.X86_64/X86_64/7B4EEEBDBC>) |
| 126f:2262 | 126f:2262 | Silicon Motion   | SM2262/SM2262EN SSD Controller       | 5     | nvme       | [E8FC7722EF](<All In One/Apple/iMac17/iMac17,1/F3D5F5910EA5/UBUNTU-BUDGIE-22.10/5.19.0-38-GENERIC/X86_64/E8FC7722EF>) |
| 15b7:5006 | 15b7:5006 | SanDisk          | WD Black SN750 / PC SN730 NVMe SSD   | 5     | nvme       | [88D774DF0D](<All In One/Acidanthera/iMac20/iMac20,1/C13BE88FDE86/DEBIAN-12/6.1.0-7-AMD64/X86_64/88D774DF0D>) |
| 2646:500c | 2646:500c | Kingston Tech... | Technology Company Non-Volatile m... | 5     | nvme       | [72DF681F16](<All In One/ASUSTek Computer/ASUS/ASUS Vivo AIO V241DA_M241DA/95E14D288239/UBUNTU-22.10/5.19.0-29-GENERIC/X86_64/72DF681F16>) |
| 15b7:5002 | 15b7:5002 | SanDisk          | WD Black 2018/SN750 / PC SN720 NV... | 4     | nvme       | [3900976672](<All In One/Acidanthera/iMac20/iMac20,1/88166FB0CD9D/FEDORA-36/6.0.5-200.FC36.X86_64/X86_64/3900976672>) |
| 1e95:9100 | 126f:2263 | Solid State S... | Non-Volatile memory controller       | 4     | nvme       | [681D2000F3](<All In One/Dell/Inspiron/Inspiron 5400 AIO/9A7047B5BC8F/ZORIN-16/5.13.0-30-GENERIC/X86_64/681D2000F3>) |
| 10ec:5762 | 10ec:5762 | Realtek Semic... | RTS5763DL NVMe SSD Controller        | 3     | nvme       | [68015B73D0](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-r0xx/27EA4D544A61/ALT-10.1/5.15.72-UN-DEF-ALT1/X86_64/68015B73D0>) |
| 1179:0116 | 1179:0001 | Toshiba Ameri... | XG5 NVMe SSD Controller              | 3     | nvme       | [81AF87F00C](<All In One/Dell/Inspiron/Inspiron 27 7775/D1240D4484D8/ELEMENTARY-5.1.7/5.4.0-89-GENERIC/X86_64/81AF87F00C>) |
| 15b7:501a | 15b7:501a | SanDisk          | WD Blue SN570 NVMe SSD               | 3     | nvme       | [91F5A10BA1](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G3 23.8-in NT GPU AiO/67C5374EC0C9/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/91F5A10BA1>) |
| 1c5c:1339 | 1c5c:0000 | SK hynix         | BC511                                | 3     | nvme       | [2FAB63E976](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-df0xxx/0229793D3988/KUBUNTU-22.04/5.15.0-60-LOWLATENCY/X86_64/2FAB63E976>) |
| 1cc4:2263 | 1cc4:1cc4 | Union Memory ... | Non-Volatile memory controller       | 3     | nvme       | [5DA493DE55](<All In One/Lenovo/IdeaCentre/IdeaCentre A540-24API F0EM0000UK/93E2EABF69EE/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/5DA493DE55>) |
| 1e4b:1202 | 1e4b:1202 | MAXIO Technol... | NVMe SSD Controller MAP1202          | 3     | nvme       | [E734B33010](<All In One/Graviton/D12/D12i/E65E993A1E87/ALT-10.1/5.15.104-UN-DEF-ALT1/X86_64/E734B33010>) |
| 106b:2005 | 106b:1800 | Apple            | ANS2 NVMe Controller                 | 2     | nvme       | [B54C61BEA2](<All In One/Apple/iMac20/iMac20,1/4FE23979BC61/UBUNTU-22.04/5.19.10-T2/X86_64/B54C61BEA2>) |
| 1179:011a | 1179:0001 | Toshiba Ameri... | XG6 NVMe SSD Controller              | 2     | nvme       | [4FE6CA7F88](<All In One/Acer/Aspire/Aspire C27-1655/38F1D8798E6E/RED-OS-7.3.2/5.15.87-1.EL7.3.X86_64/X86_64/4FE6CA7F88>) |
| 1344:5404 | 1344:1100 | Micron Techno... | NVMe Storage Controller              | 2     | nvme       | [EC07BB84CF](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 27ALC6 F0FY0055GE/634764CAF8D6/SIDUCTION-12/6.2.8-1-SIDUCTION-AMD64/X86_64/EC07BB84CF>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 2     | nvme       | [C824A76199](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-27IKL F0D0/6FBC3DB85416/UBUNTU-22.10/5.19.0-26-GENERIC/X86_64/C824A76199>) |
| 1987:5007 | 1987:5007 | Phison Electr... | E7 NVMe Controller                   | 2     | nvme       | [DA913ED8D3](<All In One/Acidanthera/iMac19/iMac19,1/F3CD9559B336/LINUXMINT-20.1/5.8.0-50-GENERIC/X86_64/DA913ED8D3>) |
| 2646:500d | 2646:500d | Kingston Tech... | OM3PDP3 NVMe SSD                     | 2     | nvme       | [9F1A2EDF3B](<All In One/Acer/Aspire/Aspire C24-1650/6C7EDB39C36C/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/9F1A2EDF3B>) |
| 8086:0975 | 8086:8410 | Intel            | NVMe Controller                      | 2     | nvme       | [EFB6906A46](<All In One/Hewlett-Packard/ENVY/ENVY All-in-One 32-a11xxx/AC2CB5057523/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/EFB6906A46>) |
| 8086:0975 | 8086:8510 | Intel            | NVMe Controller                      | 2     | nvme       | [EFB6906A46](<All In One/Hewlett-Packard/ENVY/ENVY All-in-One 32-a11xxx/AC2CB5057523/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/EFB6906A46>) |
| 8086:f1a6 | 8086:390b | Intel            | SSD Pro 7600p/760p/E 6100p Series    | 2     | nvme       | [D16F5CA08A](<All In One/Acidanthera/iMac20/iMac20,1/1EB5BA2AB9E0/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/D16F5CA08A>) |
| 1179:0115 | 1179:0001 | Toshiba Ameri... | XG4 NVMe SSD Controller              | 1     | nvme       | [F41BD5BF5B](<All In One/Dell/Precision/Precision 5720 AIO/88AAB8E50334/LINUXMINT-19.1/4.15.0-20-GENERIC/X86_64/F41BD5BF5B>) |
| 1344:5411 | 1344:1100 | Micron Techno... | NVMe Storage Controller              | 1     | nvme       | [D8AFBB81F9](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One Desktop 27-ca1xxx/14CB272FDF67/LUBUNTU-22.10/5.19.0-35-GENERIC/X86_64/D8AFBB81F9>) |
| 144d:a808 | 144d:a811 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 1     | nvme       | [25999BFD58](<All In One/Apple/iMac19/iMac19,1/6C107CF760F6/UBUNTU-20.04/5.4.0-54-GENERIC/X86_64/25999BFD58>) |
| 144d:a80a | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 1     | nvme       | [0C23DF771F](<All In One/Hewlett-Packard/EliteOne/EliteOne 870 27 inch G9 All-in-One Desktop PC/3F38BA670890/RED-OS-7.3.2/5.15.87-1.EL7.3.X86_64/X86_64/0C23DF771F>) |
| 14a4:2200 | 1b4b:1093 | Lite-On Techn... | Lite-On Non-Volatile memory contr... | 1     | nvme       | [673BECE511](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/AFF5FBFC8C68/OPENMANDRIVA-23.01/6.1.2-DESKTOP-1OMV2301/X86_64/673BECE511>) |
| 15b7:5005 | 15b7:5005 | SanDisk          | PC SN520 NVMe SSD                    | 1     | nvme       | [231DA9915B](<All In One/Lenovo/IdeaCentre/IdeaCentre A340-22ICB F0E90010RK/7B7162E100C2/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/231DA9915B>) |
| 15b7:5007 | 15b7:5007 | SanDisk          | Non-Volatile memory controller       | 1     | nvme       | [3A565370DE](<All In One/Dell/OptiPlex/OptiPlex 7480 AIO/58ED8D7EB631/ALT-8.0/4.19.135-UN-DEF-ALT0.M80C.1/X86_64/3A565370DE>) |
| 15b7:5011 | 15b7:5011 | SanDisk          | WD PC SN810 / Black SN850 NVMe SSD   | 1     | nvme       | [015BB102A2](<All In One/Acidanthera/iMac19/iMac19,1/2768684200E0/KDE-NEON-22.04/5.15.0-52-GENERIC/X86_64/015BB102A2>) |
| 1c5c:1639 | 1c5c:1639 | SK hynix         | Non-Volatile memory controller       | 1     | nvme       | [66914D8BED](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/1B35E42B0931/UBUNTU-22.10/5.19.0-15-GENERIC/X86_64/66914D8BED>) |
| 1cc1:613a | 1dbe:5220 | ADATA Technology | A Non-Volatile memory controller     | 1     | nvme       | [1011557C31](<All In One/Hewlett-Packard/ProOne/ProOne 440 G4 23.8-in NT AiO/EC8129DD680A/RED-OS-7.3/5.15.35-5.EL7.3.X86_64/X86_64/1011557C31>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 1     | nvme       | [CB6D3B830B](<All In One/Others/1/1.0/47C41F330033/ELEMENTARY-5.1.3/5.3.0-47-GENERIC/X86_64/CB6D3B830B>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2822 | 1028:05a7 | Intel            | SATA Controller [RAID mode]          | 11    | ahci       | [F52114AC39](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/CF736E32B43F/KUBUNTU-22.04/5.15.0-47-GENERIC/X86_64/F52114AC39>) |
| 8086:9a0b | 8086:0000 | Intel            | Volume Management Device NVMe RAI... | 9     | vmd        | [C87417466C](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 27ITL6 F0FW00Q2RU/E4E2B81CA7F6/DEBIAN-11/5.10.0-21-AMD64/X86_64/C87417466C>) |
| 8086:282a | 1025:1418 | Intel            | 82801 Mobile SATA Controller [RAI... | 8     | ahci       | [A82A90955E](<All In One/Acer/Aspire/Aspire C27-962/563F493FD77F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/A82A90955E>) |
| 8086:282a | 1043:17b1 | Intel            | 82801 Mobile SATA Controller [RAI... | 7     | ahci       | [24ED481783](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_A6521FA/262E2C088492/RED-OS-7.3.2/5.15.72-1.EL7.3.X86_64/X86_64/24ED481783>) |
| 8086:2822 | 1028:06c5 | Intel            | SATA Controller [RAID mode]          | 5     | ahci       | [446D4B4C59](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/34CACCC6D3D6/FEDORA-35/5.16.18-200.FC35.X86_64/X86_64/446D4B4C59>) |
| 8086:2822 | 1028:0625 | Intel            | SATA Controller [RAID mode]          | 4     | ahci       | [405A60B1E3](<All In One/Dell/OptiPlex/OptiPlex 9030 AIO/CC35AD545B7D/MANJARO/6.1.7-1-MANJARO/X86_64/405A60B1E3>) |
| 8086:282a | 103c:84de | Intel            | 82801 Mobile SATA Controller [RAI... | 4     | ahci       | [6B7FA4FF60](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/B673E7AEA681/UBUNTU-19.04/5.0.0-27-GENERIC/X86_64/6B7FA4FF60>) |
| 8086:282a | 152d:0924 | Intel            | 82801 Mobile SATA Controller [RAI... | 4     | ahci       | [7CCE1C6F6F](<All In One/Vizio/CA/CA27/FCA4878A3D40/ZORIN-16/5.15.0-69-GENERIC/X86_64/7CCE1C6F6F>) |
| 8086:2822 | 1028:079c | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [1940C6417C](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/A9167F8393F4/DEBIAN-11/5.10.0-21-AMD64/X86_64/1940C6417C>) |
| 8086:2822 | 103c:86f7 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [C6437188E6](<All In One/Hewlett-Packard/All-in-One/All-in-One 27-dp0xxx/1B38D1EFE767/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/C6437188E6>) |
| 8086:2822 | 1028:05b0 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [5E0726466B](<All In One/Dell/XPS/XPS 2720/CE5E9E89BC9C/LINUXMINT-20.3/5.4.0-117-GENERIC/X86_64/5E0726466B>) |
| 8086:2822 | 103c:3561 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [7AF1912AB7](<All In One/Hewlett-Packard/Z1/Z1 Workstation/4089A5726DF1/FEDORA-37/6.0.9-300.FC37.X86_64/X86_64/7AF1912AB7>) |
| 8086:2822 | 103c:84ee | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [79C81FCFB5](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-xa0xxx/172DC93717BB/ROSA-12.3/6.0.7.XM1-1.KLP-XANMOD-ROSA2021.1-X86_64/X86_64/79C81FCFB5>) |
| 8086:2822 | 103c:86c7 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [EFB6906A46](<All In One/Hewlett-Packard/ENVY/ENVY All-in-One 32-a11xxx/AC2CB5057523/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/EFB6906A46>) |
| 8086:2822 | 103c:86ed | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [E86753F364](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-d0xxx/C8F5FD68E798/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/E86753F364>) |
| 8086:282a | 1028:05db | Intel            | 82801 Mobile SATA Controller [RAI... | 2     | ahci       | [323E28FDED](<All In One/Dell/Inspiron/Inspiron 2350/07DCD03E083E/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/323E28FDED>) |
| 8086:282a | 1028:0853 | Intel            | 82801 Mobile SATA Controller [RAI... | 2     | ahci       | [515F746557](<All In One/Dell/Inspiron/Inspiron 3277 AIO/31B12D6ABF76/LINUXMINT-20.3/5.4.0-109-GENERIC/X86_64/515F746557>) |
| 8086:282a | 1028:0954 | Intel            | 82801 Mobile SATA Controller [RAI... | 2     | ahci       | [51D212B73F](<All In One/Dell/Inspiron/Inspiron 7790 AIO/5226FB806DAF/MAKULU-2020/5.8.0-44-GENERIC/X86_64/51D212B73F>) |
| 8086:282a | 103c:87a4 | Intel            | 82801 Mobile SATA Controller [RAI... | 2     | ahci       | [6B92AEDE76](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-df0xxx/2DAE71242922/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/6B92AEDE76>) |
| 8086:467f | 8086:0000 | Intel            | Volume Management Device NVMe RAI... | 2     | vmd        | [F5311B2134](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One Desktop 27-ca1xxx/21D85AAC9DF0/UBUNTU-22.10/5.19.17-051917-GENERIC/X86_64/F5311B2134>) |
| 8086:2822 | 1025:1189 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [7DF055CFAC](<All In One/Acer/Aspire/Aspire Z24-880/CBD0ED9CC044/UBUNTU-20.04/5.13.0-37-GENERIC/X86_64/7DF055CFAC>) |
| 8086:2822 | 1025:1291 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [13496AAE5D](<All In One/Acer/Veriton/Veriton Z4660G/A736A6205FE1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/13496AAE5D>) |
| 8086:2822 | 1028:054b | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [FCD0EF9F0E](<All In One/Dell/XPS/XPS One 2710/E83BF6F5E12A/POP!_OS-21.04/5.13.0-7614-GENERIC/X86_64/FCD0EF9F0E>) |
| 8086:2822 | 1028:075c | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [1FA1F8CD8C](<All In One/Dell/XPS/XPS 7760 AIO/BD46D877F953/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/1FA1F8CD8C>) |
| 8086:2822 | 1028:075d | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [F41BD5BF5B](<All In One/Dell/Precision/Precision 5720 AIO/88AAB8E50334/LINUXMINT-19.1/4.15.0-20-GENERIC/X86_64/F41BD5BF5B>) |
| 8086:2822 | 1028:079e | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [2BF103DD36](<All In One/Dell/OptiPlex/OptiPlex 3050 AIO/6E8B4AA4839E/UBUNTU-18.04/4.18.0-15-GENERIC/X86_64/2BF103DD36>) |
| 8086:2822 | 1028:084b | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [77C3745DAB](<All In One/Dell/OptiPlex/OptiPlex 7460 AIO/97FD484B4E36/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/77C3745DAB>) |
| 8086:2822 | 1028:084c | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [A059134B9B](<All In One/Dell/OptiPlex/OptiPlex 5260 AIO/F49D2C138AA3/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/A059134B9B>) |
| 8086:2822 | 103c:82a6 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [DD3E2FA2B5](<All In One/Hewlett-Packard/ProOne/ProOne 400 G3 20.0-in Non-Touch AiO/A09511605F07/MANJARO-18.1.5/5.4.6-2-MANJARO/X86_64/DD3E2FA2B5>) |
| 8086:2822 | 103c:838b | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [AC62725ABE](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-r0xx/7DE2EBF070ED/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/AC62725ABE>) |
| 8086:2822 | 103c:885e | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [6B6DD9140A](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-d1xxx/1DA1FD0FD208/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/6B6DD9140A>) |
| 8086:2822 | 1462:b106 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [6A736E8849](<All In One/MSI/MS-B/MS-B10611/54D0884E1335/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/6A736E8849>) |
| 8086:2822 | 17aa:36dd | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [7EBBF6AAD0](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-27IKL F0D0001BCK/4FB1AC9C7D60/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/7EBBF6AAD0>) |
| 8086:282a | 1025:1230 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [A255155F98](<All In One/Acer/Aspire/Aspire S24-880/00A232C06A58/OPENMANDRIVA-4.50/5.19.12-DESKTOP-2OMV4090/X86_64/A255155F98>) |
| 8086:282a | 1028:05d1 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [45C116DB45](<All In One/Dell/XPS/XPS 18/9C7C62A1A766/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/45C116DB45>) |
| 8086:282a | 1028:08f9 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [727E0D3A2E](<All In One/Dell/Inspiron/Inspiron 3280 AIO/34CA6784808C/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/727E0D3A2E>) |
| 8086:282a | 1028:0953 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [D77787D6EC](<All In One/Dell/Inspiron/Inspiron 5490 AIO/DED288B166FA/POP!_OS-20.10/5.8.0-7642-GENERIC/X86_64/D77787D6EC>) |
| 8086:282a | 17aa:36dc | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [A4AFD5181F](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-24IKU F0D200E2LD/E39A5F0652F6/ARCH-ROLLING/5.6.13.A-1-HARDENED/X86_64/A4AFD5181F>) |
| 8086:282a | 8086:7270 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [C3ACBCAEA0](<All In One/Medion/E/E23403/AE54AAD7F16E/KUBUNTU-11.1/5.13.0-51-GENERIC/X86_64/C3ACBCAEA0>) |
| 8086:467f | 17aa:3767 | Intel            | Volume Management Device NVMe RAI... | 1     | vmd        | [F9F38488A8](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 5 27IAH7 F0GQ0001US/D9930DEAC59F/POP!_OS-22.04/6.0.12-76060006-GENERIC/X86_64/F9F38488A8>) |
| 8086:9a0b | 1025:1475 | Intel            | Volume Management Device NVMe RAI... | 1     | vmd        | [A28B44985D](<All In One/Acer/Aspire/Aspire C24-1650/784D54B26B25/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/A28B44985D>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1513 | 2222:1111 | Intel            | CV82524 Thunderbolt Controller [L... | 169   | thunder... | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 8086:15d2 | 8086:0000 | Intel            | JHL6540 Thunderbolt 3 NHI (C step... | 70    | thunder... | [EE288626F4](<All In One/Apple/iMac18/iMac18,3/85F2F89AFF57/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/EE288626F4>) |
| 8086:156c |           | Intel            | DSL5520 Thunderbolt 2 NHI [Falcon... | 66    | thunder... | [570077AA64](<All In One/Apple/iMac16/iMac16,2/2D4E89D37302/ZORIN-16/5.15.0-69-GENERIC/X86_64/570077AA64>) |
| 8086:15eb | 8086:0000 | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 51    | thunder... | [0F3F45F8E9](<All In One/Apple/iMac19/iMac19,2/5322EAC8B99B/PARROT-5.2/6.0.0-12PARROT1-AMD64/X86_64/0F3F45F8E9>) |
| 8086:d150 |           | Intel            | Core Processor QPI Link              | 48    |            | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 8086:d151 |           | Intel            | Core Processor QPI Routing and Pr... | 48    |            | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 8086:d155 |           | Intel            | Core Processor System Management ... | 48    |            | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 8086:d156 |           | Intel            | Core Processor Semaphore and Scra... | 48    |            | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 8086:d157 |           | Intel            | Core Processor System Control and... | 48    |            | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 8086:d158 |           | Intel            | Core Processor Miscellaneous Regi... | 48    |            | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 8086:1911 | 1019:a5a1 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 22    |            | [63DBB9394E](<All In One/ICL/RAY/RAY S122.Mi/767FFC5AB7B5/ALT-8.4/5.10.83-STD-DEF-ALT0.C9F.2/X86_64/63DBB9394E>) |
| 8086:3190 |           | Intel            | Celeron/Pentium Silver Processor ... | 15    |            | [2F11E3E79D](<All In One/ASUSTek Computer/Vivo/Vivo AIO 16 V161GA_V161GA/733A41D44410/ENDLESS-4.0.14/5.11.0-35-GENERIC/X86_64/2F11E3E79D>) |
| 8086:1911 | 103c:84ee | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 14    |            | [8E1245836B](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/B6DE3C8A8AED/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/8E1245836B>) |
| 8086:1568 | 2222:1111 | Intel            | DSL4510 Thunderbolt NHI [Redwood ... | 13    |            | [6976F884E6](<All In One/Apple/iMac14/iMac14,4/6E7600BFDA83/LUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6976F884E6>) |
| 8086:1911 | 1025:1287 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 13    |            | [EB0191F969](<All In One/Acer/Aspire/Aspire C22-865/2C5B66C0839A/MANJARO/6.1.1-1-MANJARO/X86_64/EB0191F969>) |
| 197b:2382 | 1025:0266 | JMicron Techn... | SD/MMC Host Controller               | 12    | sdhci_pci  | [8A9EDF5A44](<All In One/Acer/Aspire/Aspire Z5600/021BA2DCCB15/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/8A9EDF5A44>) |
| 197b:2383 | 1025:0266 | JMicron Techn... | MS Host Controller                   | 12    | jmb38x_ms  | [8A9EDF5A44](<All In One/Acer/Aspire/Aspire Z5600/021BA2DCCB15/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/8A9EDF5A44>) |
| 8086:3190 | 1025:1304 | Intel            | Celeron/Pentium Silver Processor ... | 12    |            | [07D4BF17AA](<All In One/Acer/Aspire/Aspire C22-820/D247EFB9442C/ROSA-12.3/5.10.155-GENERIC-1ROSA2021.1-X86_64/X86_64/07D4BF17AA>) |
| 1180:e230 | 104d:9060 | Ricoh            | R5U2xx (R5U230 / R5U231 / R5U241)... | 10    |            | [57E0224FFD](<All In One/Sony/VPCL13/VPCL13M1R/82175A598A60/RELD-7.9/5.15.33-1.RES7.X86_64/X86_64/57E0224FFD>) |
| 8086:1911 | 17aa:3145 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 10    |            | [FAEB46556E](<All In One/Lenovo/V540-24IWL/V540-24IWL AIO 10YS0031RU/886440AA02F6/KOMETA-P10/5.10.102-STD-DEF-ALT1/X86_64/FAEB46556E>) |
| 8086:1911 | 8086:1911 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 10    |            | [48ADD8DC01](<All In One/ASUSTek Computer/V241/V241IC-R/D782169DBFD0/RED-OS-7.3.1/5.15.35-1.EL7.3.X86_64/X86_64/48ADD8DC01>) |
| 1180:e232 | 104d:907e | Ricoh            | PCIe Memory Stick Host Controller    | 8     |            | [0451CAEB29](<All In One/Sony/VPCL212/VPCL212FX/01EE677E7F92/UBUNTU-21.10/5.13.0-22-GENERIC/X86_64/0451CAEB29>) |
| 8086:464f |           | Intel            | 12th Gen Core Processor Gaussian ... | 8     |            | [E734B33010](<All In One/Graviton/D12/D12i/E65E993A1E87/ALT-10.1/5.15.104-UN-DEF-ALT1/X86_64/E734B33010>) |
| 8086:1911 | 1028:0754 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 7     |            | [348BC23246](<All In One/Dell/Inspiron/Inspiron 3464 AIO/00109263052E/ENDEAVOUROS-ROLLING/5.15.71-1-LTS/X86_64/348BC23246>) |
| 8086:1911 | 1043:17b1 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 7     |            | [24ED481783](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_A6521FA/262E2C088492/RED-OS-7.3.2/5.15.72-1.EL7.3.X86_64/X86_64/24ED481783>) |
| 1180:e232 | 104d:9083 | Ricoh            | PCIe Memory Stick Host Controller    | 6     |            | [1F521568E1](<All In One/Sony/VPCJ23/VPCJ23S1R/38825FA7D374/ZORIN-16/5.15.0-57-GENERIC/X86_64/1F521568E1>) |
| 1180:e232 | 104d:9097 | Ricoh            | PCIe Memory Stick Host Controller    | 6     |            | [CEFAD415D0](<All In One/Sony/SVL2411/SVL24117FLB/B337A07B7653/POP!_OS-22.04/6.0.2-76060002-GENERIC/X86_64/CEFAD415D0>) |
| 197b:2382 | 103c:1489 | JMicron Techn... | SD/MMC Host Controller               | 6     | sdhci_pci  | [EBD3760355](<All In One/Hewlett-Packard/Compaq/Compaq 6000 Pro AiO Business PC/F6BD16E86080/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/EBD3760355>) |
| 197b:2383 | 103c:1489 | JMicron Techn... | MS Host Controller                   | 6     | jmb38x_ms  | [EBD3760355](<All In One/Hewlett-Packard/Compaq/Compaq 6000 Pro AiO Business PC/F6BD16E86080/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/EBD3760355>) |
| 197b:2384 | 103c:1489 | JMicron Techn... | xD Host Controller                   | 6     |            | [EBD3760355](<All In One/Hewlett-Packard/Compaq/Compaq 6000 Pro AiO Business PC/F6BD16E86080/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/EBD3760355>) |
| 8086:1911 | 103c:8446 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 6     |            | [AD79D02FF6](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/FED3FEB2A294/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/AD79D02FF6>) |
| 8086:3190 | 103c:86f0 | Intel            | Celeron/Pentium Silver Processor ... | 6     |            | [2FAB63E976](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-df0xxx/0229793D3988/KUBUNTU-22.04/5.15.0-60-LOWLATENCY/X86_64/2FAB63E976>) |
| 197b:2382 | 17aa:3602 | JMicron Techn... | SD/MMC Host Controller               | 5     | sdhci_pci  | [195EC7CB8C](<All In One/Lenovo/10051/10051/11244BE45969/LINUXMINT-20.3/5.4.0-126-GENERIC/X86_64/195EC7CB8C>) |
| 197b:2383 | 17aa:3602 | JMicron Techn... | MS Host Controller                   | 5     | jmb38x_ms  | [195EC7CB8C](<All In One/Lenovo/10051/10051/11244BE45969/LINUXMINT-20.3/5.4.0-126-GENERIC/X86_64/195EC7CB8C>) |
| 197b:2384 | 17aa:3602 | JMicron Techn... | xD Host Controller                   | 5     |            | [195EC7CB8C](<All In One/Lenovo/10051/10051/11244BE45969/LINUXMINT-20.3/5.4.0-126-GENERIC/X86_64/195EC7CB8C>) |
| 8086:1911 | 8086:7270 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 5     |            | [1498908025](<All In One/Others/Others/Others/DD5904031925/LINUXMINT-20.1/5.4.0-121-GENERIC/X86_64/1498908025>) |
| 8086:3190 | 103c:8431 | Intel            | Celeron/Pentium Silver Processor ... | 5     |            | [9F9D598111](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/2D41DA9A7073/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/9F9D598111>) |
| 1180:0592 | 104d:9044 | Ricoh            | R5C592 Memory Stick Bus Host Adapter | 4     | r592       | [3ED1AD79E4](<All In One/Sony/VGC-JS54/VGC-JS54FB_W/1013B0577913/LINUX-LITE-6.0/5.16.9/X86_64/3ED1AD79E4>) |
| 1180:e230 | 104d:9074 | Ricoh            | R5U2xx (R5U230 / R5U231 / R5U241)... | 4     |            | [2DEFAA2F88](<All In One/Sony/VPCJ118/VPCJ118FJ/356CC6106273/UBUNTU-20.04/5.15.0-43-GENERIC/X86_64/2DEFAA2F88>) |
| 8086:09ab | 1043:1482 | Intel            | RST VMD Managed Controller           | 4     |            | [FFB4ED2207](<All In One/ASUSTek Computer/ASUS/ASUS Vivo AIO V241EA_V241EA/69C580FE0877/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/FFB4ED2207>) |
| 8086:1911 | 1028:084b | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 4     |            | [5F63C2FD15](<All In One/Dell/OptiPlex/OptiPlex 7460 AIO/81D9C9B1F509/GENTOO-2.9/6.1.1/X86_64/5F63C2FD15>) |
| 8086:1911 | 1028:0852 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 4     |            | [F373C43A01](<All In One/Dell/Inspiron/Inspiron 3477 AIO/6B758C37D517/POP!_OS-22.04/5.17.5-76051705-GENERIC/X86_64/F373C43A01>) |
| 8086:1911 | 103c:86f7 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 4     |            | [C6437188E6](<All In One/Hewlett-Packard/All-in-One/All-in-One 27-dp0xxx/1B38D1EFE767/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/C6437188E6>) |
| 8086:1911 | 17aa:36f4 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 4     |            | [C129F7C9B1](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-27ICB F0DE00EJRI/E74066EE0DE7/UBUNTUSTUDIO-22.04/5.15.0-47-LOWLATENCY/X86_64/C129F7C9B1>) |
| 8086:3190 | 17aa:36ed | Intel            | Celeron/Pentium Silver Processor ... | 4     |            | [6481787B51](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 330-20IGM F0D7001PLD/4248D7BD5C39/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/6481787B51>) |
| 8086:9a11 | 1025:150f | Intel            | GNA Scoring Accelerator module       | 4     |            | [4FE6CA7F88](<All In One/Acer/Aspire/Aspire C27-1655/38F1D8798E6E/RED-OS-7.3.2/5.15.87-1.EL7.3.X86_64/X86_64/4FE6CA7F88>) |
| 8086:9a11 | 1043:1482 | Intel            | GNA Scoring Accelerator module       | 4     |            | [FFB4ED2207](<All In One/ASUSTek Computer/ASUS/ASUS Vivo AIO V241EA_V241EA/69C580FE0877/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/FFB4ED2207>) |
| 197b:2382 | 1025:0275 | JMicron Techn... | SD/MMC Host Controller               | 3     | sdhci_pci  | [49DF2710DC](<All In One/Packard Bell/ONETWO/ONETWO M3700/3096674A954A/UBUNTU-18.04/5.0.0-37-GENERIC/X86_64/49DF2710DC>) |
| 197b:2382 | 1025:0608 | JMicron Techn... | SD/MMC Host Controller               | 3     | sdhci_pci  | [33937E8F75](<All In One/Acer/Aspire/Aspire Z1620/19DE00291955/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/33937E8F75>) |
| 197b:2382 | 1043:842d | JMicron Techn... | SD/MMC Host Controller               | 3     | sdhci_pci  | [86CD4A72D1](<All In One/ASUSTek Computer/ET2010/ET2010AG/03DD34D94A32/XUBUNTU-21.04/5.11.0-37-GENERIC/X86_64/86CD4A72D1>) |

### Tv card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1131:7134 | 16be:5000 | Philips Semic... | SAA7134/SAA7135HL Video Broadcast... | 1     | saa7134    | [098FE372A3](<All In One/Acidanthera/iMac14/iMac14,4/E2C69985CC45/GENTOO-2.6/5.4.97-GENTOO_DQ87PG/X86_64/098FE372A3>) |
| 14f1:8880 | 0070:7801 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 1     | cx23885    | [FCD01E22D7](<All In One/ASUSTek Computer/PRIME/PRIME B450M-A II/E71284EECA39/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/FCD01E22D7>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c26 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 170   | ehci_pci   | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 8086:1c27 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 170   | uhci_hcd   | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 8086:1c2c | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 170   | uhci_hcd   | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 8086:1c2d | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 170   | ehci_pci   | [BD50784A0B](<All In One/Apple/iMac12/iMac12,2/61F4612A7D02/LILIDOG-23/6.1.0-7-AMD64/X86_64/BD50784A0B>) |
| 8086:2830 | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 155   | uhci_hcd   | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 8086:2831 | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 155   | uhci_hcd   | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 8086:2832 | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 155   | uhci_hcd   | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 8086:2834 |           | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 155   | uhci_hcd   | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 8086:2835 | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 155   | uhci_hcd   | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 8086:2836 | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB2 EHCI Co... | 155   | ehci_pci   | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 8086:283a | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB2 EHCI Co... | 155   | ehci_pci   | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 10de:0aa5 | 10de:cb79 | Nvidia           | MCP79 OHCI USB 1.1 Controller        | 128   | ohci_pci   | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 10de:0aa6 | 10de:cb79 | Nvidia           | MCP79 EHCI USB 2.0 Controller        | 128   | ehci_pci   | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 10de:0aa7 | 10de:cb79 | Nvidia           | MCP79 OHCI USB 1.1 Controller        | 128   | ohci_pci   | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 10de:0aa9 | 10de:cb79 | Nvidia           | MCP79 EHCI USB 2.0 Controller        | 128   | ehci_pci   | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 8086:8c31 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 89    | xhci_hcd   | [00D8186404](<All In One/Apple/iMac14/iMac14,2/6ABD34C5E7DF/UBUNTU-22.04/5.15.0-33-GENERIC/X86_64/00D8186404>) |
| 8086:a12f | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 89    | xhci_hcd   | [EE288626F4](<All In One/Apple/iMac18/iMac18,3/85F2F89AFF57/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/EE288626F4>) |
| 8086:3b34 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset USB2... | 86    | ehci_pci   | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 8086:3b36 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset USB ... | 86    | uhci_hcd   | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 8086:3b3b | 8086:7270 | Intel            | 5 Series/3400 Series Chipset USB ... | 86    | uhci_hcd   | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 8086:3b3c | 8086:7270 | Intel            | 5 Series/3400 Series Chipset USB2... | 86    | ehci_pci   | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 8086:15d4 | 8086:0000 | Intel            | JHL6540 Thunderbolt 3 USB Control... | 70    | xhci_hcd   | [EE288626F4](<All In One/Apple/iMac18/iMac18,3/85F2F89AFF57/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/EE288626F4>) |
| 8086:15ec | 8086:0000 | Intel            | JHL7540 Thunderbolt 3 USB Control... | 51    | xhci_pci   | [0F3F45F8E9](<All In One/Apple/iMac19/iMac19,2/5322EAC8B99B/PARROT-5.2/6.0.0-12PARROT1-AMD64/X86_64/0F3F45F8E9>) |
| 8086:a36d | 8086:7270 | Intel            | Cannon Lake PCH USB 3.1 xHCI Host... | 51    | xhci_pci   | [0F3F45F8E9](<All In One/Apple/iMac19/iMac19,2/5322EAC8B99B/PARROT-5.2/6.0.0-12PARROT1-AMD64/X86_64/0F3F45F8E9>) |
| 8086:1e26 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family USB ... | 49    | ehci_pci   | [C8C9C1E591](<All In One/Apple/iMac13/iMac13,1/ED988FB747CF/DEBIAN-11/5.10.0-21-AMD64/X86_64/C8C9C1E591>) |
| 8086:1e2d | 8086:7270 | Intel            | 7 Series/C216 Chipset Family USB ... | 49    | ehci_pci   | [C8C9C1E591](<All In One/Apple/iMac13/iMac13,1/ED988FB747CF/DEBIAN-11/5.10.0-21-AMD64/X86_64/C8C9C1E591>) |
| 8086:1e31 | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 49    | xhci_hcd   | [C8C9C1E591](<All In One/Apple/iMac13/iMac13,1/ED988FB747CF/DEBIAN-11/5.10.0-21-AMD64/X86_64/C8C9C1E591>) |
| 8086:27c8 | 8086:7270 | Intel            | NM10/ICH7 Family USB UHCI Control... | 30    | uhci_hcd   | [C7444AC7F0](<All In One/Apple/iMac5/iMac5,1/104264B0BD86/XUBUNTU-22.04/5.15.0-70-GENERIC/X86_64/C7444AC7F0>) |
| 8086:27c9 | 8086:7270 | Intel            | NM10/ICH7 Family USB UHCI Control... | 30    | uhci_hcd   | [C7444AC7F0](<All In One/Apple/iMac5/iMac5,1/104264B0BD86/XUBUNTU-22.04/5.15.0-70-GENERIC/X86_64/C7444AC7F0>) |
| 8086:27ca | 8086:7270 | Intel            | NM10/ICH7 Family USB UHCI Control... | 30    | uhci_hcd   | [C7444AC7F0](<All In One/Apple/iMac5/iMac5,1/104264B0BD86/XUBUNTU-22.04/5.15.0-70-GENERIC/X86_64/C7444AC7F0>) |
| 8086:27cb | 8086:7270 | Intel            | NM10/ICH7 Family USB UHCI Control... | 30    | uhci_hcd   | [C7444AC7F0](<All In One/Apple/iMac5/iMac5,1/104264B0BD86/XUBUNTU-22.04/5.15.0-70-GENERIC/X86_64/C7444AC7F0>) |
| 8086:27cc | 8086:7270 | Intel            | NM10/ICH7 Family USB2 EHCI Contro... | 30    | ehci_pci   | [C7444AC7F0](<All In One/Apple/iMac5/iMac5,1/104264B0BD86/XUBUNTU-22.04/5.15.0-70-GENERIC/X86_64/C7444AC7F0>) |
| 8086:a2af | 1019:a5a1 | Intel            | 200 Series/Z370 Chipset Family US... | 22    | xhci_pci   | [63DBB9394E](<All In One/ICL/RAY/RAY S122.Mi/767FFC5AB7B5/ALT-8.4/5.10.83-STD-DEF-ALT0.C9F.2/X86_64/63DBB9394E>) |
| 8086:8cb1 | 8086:7270 | Intel            | 9 Series Chipset Family USB xHCI ... | 19    | xhci_pci   | [570077AA64](<All In One/Apple/iMac16/iMac16,2/2D4E89D37302/ZORIN-16/5.15.0-69-GENERIC/X86_64/570077AA64>) |
| 8086:9a13 |           | Intel            | Tiger Lake-LP Thunderbolt 4 USB C... | 18    | xhci_hcd   | [F1FD38B5C2](<All In One/Dell/Inspiron/Inspiron 7700 AIO/F8AA8C9CD183/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/F1FD38B5C2>) |
| 1022:7808 | 103c:8245 | AMD              | FCH USB EHCI Controller              | 17    | ehci_pci   | [81F625006B](<All In One/Hewlett-Packard/24/24-g020/310803ED8E33/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/81F625006B>) |
| 1022:7814 | 103c:8245 | AMD              | FCH USB XHCI Controller              | 17    | xhci_hcd   | [81F625006B](<All In One/Hewlett-Packard/24/24-g020/310803ED8E33/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/81F625006B>) |
| 8086:9d2f | 103c:84de | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 17    | xhci_hcd   | [CDB6233482](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/13576610145B/DEBIAN-11/5.10.0-18-AMD64/X86_64/CDB6233482>) |
| 1b6f:7023 | 1025:8030 | Etron Technology | EJ168 USB 3.0 Host Controller        | 16    | xhci_hcd   | [2E34D8A2CC](<All In One/Acer/Aspire/Aspire Z5770/1DB05CC1D29C/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/2E34D8A2CC>) |
| 8086:1c26 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 16    | ehci_hc... | [D75E472005](<All In One/Lenovo/C440/C440 10104/983B023892A1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/D75E472005>) |
| 8086:1c2d | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 16    | ehci_hc... | [D75E472005](<All In One/Lenovo/C440/C440 10104/983B023892A1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/D75E472005>) |
| 8086:1c26 | 1028:0511 | Intel            | 6 Series/C200 Series Chipset Fami... | 15    | ehci_pci   | [225E42D432](<All In One/Dell/Inspiron/Inspiron One 2320/D8B99273D539/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/225E42D432>) |
| 8086:1c2d | 1028:0511 | Intel            | 6 Series/C200 Series Chipset Fami... | 15    | ehci_pci   | [225E42D432](<All In One/Dell/Inspiron/Inspiron One 2320/D8B99273D539/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/225E42D432>) |
| 8086:31a8 | 1043:201f | Intel            | Celeron/Pentium Silver Processor ... | 15    | xhci_hcd   | [2F11E3E79D](<All In One/ASUSTek Computer/Vivo/Vivo AIO 16 V161GA_V161GA/733A41D44410/ENDLESS-4.0.14/5.11.0-35-GENERIC/X86_64/2F11E3E79D>) |
| 8086:8c26 | 1028:05a7 | Intel            | 8 Series/C220 Series Chipset Fami... | 15    | ehci_pci   | [757AE6AA73](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/099C9C0A02A0/DEBIAN-11/5.10.0-20-AMD64/X86_64/757AE6AA73>) |
| 8086:8c2d | 1028:05a7 | Intel            | 8 Series/C220 Series Chipset Fami... | 15    | ehci_pci   | [757AE6AA73](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/099C9C0A02A0/DEBIAN-11/5.10.0-20-AMD64/X86_64/757AE6AA73>) |
| 8086:8c31 | 1028:05a7 | Intel            | 8 Series/C220 Series Chipset Fami... | 15    | xhci_hcd   | [757AE6AA73](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/099C9C0A02A0/DEBIAN-11/5.10.0-20-AMD64/X86_64/757AE6AA73>) |
| 8086:1e26 | 1028:0543 | Intel            | 7 Series/C216 Chipset Family USB ... | 14    | ehci_pci   | [00CB2D66A8](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/42A1DEC89484/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/00CB2D66A8>) |
| 8086:1e26 | 1028:0548 | Intel            | 7 Series/C216 Chipset Family USB ... | 14    | ehci_pci   | [22CBD67F5D](<All In One/Dell/Inspiron/Inspiron One 2330/C959D85DE508/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/22CBD67F5D>) |
| 8086:1e2d | 1028:0543 | Intel            | 7 Series/C216 Chipset Family USB ... | 14    | ehci_pci   | [00CB2D66A8](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/42A1DEC89484/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/00CB2D66A8>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:8d7c | 8086:7270 | Intel            | C610/X99 series chipset SPSR         | 1     |            | [B2AD449201](<All In One/Acidanthera/iMacPro1/iMacPro1,1/02ABD56D98BC/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/B2AD449201>) |

