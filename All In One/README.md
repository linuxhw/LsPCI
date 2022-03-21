Most popular PCI devices in All In Ones
=======================================

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
| 1814:3298 | 1a3b:2f87 | Ralink           | RT3290 Bluetooth                     | 2     |            | [0D7E8C7568](<All In One/AIO/H61/H61H-G11/80341B910781/ROSA-12.2/5.10.71-GENERIC-1ROSA2021.1-X86_64/X86_64/0D7E8C7568>) |
| 1814:3298 | 103c:18ec | Ralink           | RT3290 Bluetooth                     | 1     |            | [B6CF0A1651](<All In One/Hewlett-Packard/205/205 G1 AiO Business PC/5EDA8801C3DD/ELEMENTARY-6/5.11.0-40-GENERIC/X86_64/B6CF0A1651>) |
| 1814:3298 | 1a3b:2987 | Ralink           | RT3290 Bluetooth                     | 1     |            | [1F5B5C1D86](<All In One/AIO/H61/H61H-G11/1F971B06A938/ROSA-2016.1/4.15.0-DESKTOP-60.7ROSA-X86_64/X86_64/1F5B5C1D86>) |

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2448 |           | Intel            | 82801 Mobile PCI Bridge              | 131   |            | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 8086:2815 | 106b:00a0 | Intel            | 82801HM (ICH8M) LPC Interface Con... | 108   | lpc_ich    | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 8086:283f |           | Intel            | 82801H (ICH8 Family) PCI Express ... | 108   | pcieport   | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 8086:2845 |           | Intel            | 82801H (ICH8 Family) PCI Express ... | 108   | pcieport   | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 8086:2847 |           | Intel            | 82801H (ICH8 Family) PCI Express ... | 108   | pcieport   | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 8086:2849 |           | Intel            | 82801H (ICH8 Family) PCI Express ... | 108   | pcieport   | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 8086:2a00 | 106b:00a0 | Intel            | Mobile PM965/GM965/GL960 Memory C... | 108   | intel_agp  | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 8086:2a01 | 8086:0000 | Intel            | Mobile PM965/GM965/GL960 PCI Expr... | 108   | pcieport   | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 8086:1513 |           | Intel            | CV82524 Thunderbolt Controller [L... | 103   | pcieport   | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 8086:1c10 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 103   | pcieport   | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 8086:1c14 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 103   | pcieport   | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 8086:1c18 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 103   | pcieport   | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 8086:1c44 | 8086:7270 | Intel            | Z68 Express Chipset LPC Controller   | 103   | lpc_ich    | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 8086:1c12 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 102   | pcieport   | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 104c:823e |           | Texas Instrum... | XIO2213A/B/XIO2221 PCI Express to... | 99    | shpchp     | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 10de:0aab | 10de:cb79 | Nvidia           | MCP79 PCI Bridge                     | 88    |            | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 10de:0ac4 | 10de:0000 | Nvidia           | MCP79 PCI Express Bridge             | 88    | pcieport   | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 10de:0ac6 | 10de:0000 | Nvidia           | MCP79 PCI Express Bridge             | 88    | pcieport   | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 10de:0ac7 | 10de:0000 | Nvidia           | MCP79 PCI Express Bridge             | 88    | pcieport   | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 8086:244e | 8086:7270 | Intel            | 82801 PCI Bridge                     | 88    |            | [435548337A](<All In One/Apple/iMac13/iMac13,1/BB29D11F01EF/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/435548337A>) |
| 8086:1578 | 8086:0000 | Intel            | DSL6540 Thunderbolt 3 Bridge [Alp... | 76    | pcieport   | [841AB4FFE2](<All In One/Apple/iMac18/iMac18,2/6AAE34125DB5/FEDORA-36/5.17.0-0.RC5.102.FC36.X86_64/X86_64/841AB4FFE2>) |
| 8086:1547 | 2222:1111 | Intel            | DSL3510 Thunderbolt Controller [C... | 68    | pcieport   | [435548337A](<All In One/Apple/iMac13/iMac13,1/BB29D11F01EF/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/435548337A>) |
| 10de:0aa0 | 10de:0000 | Nvidia           | MCP79 PCI Express Bridge             | 58    | shpchp     | [4F76CF1BC8](<All In One/Apple/iMac10/iMac10,1/F2F44B6FDD9E/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/4F76CF1BC8>) |
| 8086:0100 | 8086:2010 | Intel            | 2nd Generation Core Processor Fam... | 57    | snb_uncore | [FE2249C404](<All In One/Apple/iMac12/iMac12,1/825F0CF6DCAC/ZORIN-16/5.13.0-30-GENERIC/X86_64/FE2249C404>) |
| 8086:0101 | 8086:2010 | Intel            | Xeon E3-1200/2nd Generation Core ... | 57    | pcieport   | [FE2249C404](<All In One/Apple/iMac12/iMac12,1/825F0CF6DCAC/ZORIN-16/5.13.0-30-GENERIC/X86_64/FE2249C404>) |
| 8086:a110 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 57    | pcieport   | [436904EAE3](<All In One/Apple/iMac17/iMac17,1/7E034427C03F/DEBIAN-11/5.10.0-12-AMD64/X86_64/436904EAE3>) |
| 8086:a111 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 57    | pcieport   | [436904EAE3](<All In One/Apple/iMac17/iMac17,1/7E034427C03F/DEBIAN-11/5.10.0-12-AMD64/X86_64/436904EAE3>) |
| 8086:a145 | 8086:7270 | Intel            | Z170 Chipset LPC/eSPI Controller     | 57    |            | [436904EAE3](<All In One/Apple/iMac17/iMac17,1/7E034427C03F/DEBIAN-11/5.10.0-12-AMD64/X86_64/436904EAE3>) |
| 8086:3b02 | 8086:7270 | Intel            | P55 Chipset LPC Interface Controller | 56    | lpc_ich    | [99D7E82DF9](<All In One/Apple/iMac11/iMac11,2/9D11563CF50D/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/99D7E82DF9>) |
| 8086:3b42 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset PCI ... | 56    | pcieport   | [99D7E82DF9](<All In One/Apple/iMac11/iMac11,2/9D11563CF50D/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/99D7E82DF9>) |
| 8086:3b44 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset PCI ... | 56    | pcieport   | [99D7E82DF9](<All In One/Apple/iMac11/iMac11,2/9D11563CF50D/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/99D7E82DF9>) |
| 8086:3b46 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset PCI ... | 56    | pcieport   | [99D7E82DF9](<All In One/Apple/iMac11/iMac11,2/9D11563CF50D/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/99D7E82DF9>) |
| 1022:156b |           | AMD              | Family 16h (Models 30h-3fh) Host ... | 46    |            | [F9526F3928](<All In One/Hewlett-Packard/21/21-2025la/6D56BDCCA9B3/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F9526F3928>) |
| 1022:1580 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 46    |            | [F9526F3928](<All In One/Hewlett-Packard/21/21-2025la/6D56BDCCA9B3/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F9526F3928>) |
| 1022:1581 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 46    |            | [F9526F3928](<All In One/Hewlett-Packard/21/21-2025la/6D56BDCCA9B3/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F9526F3928>) |
| 1022:1582 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 46    |            | [F9526F3928](<All In One/Hewlett-Packard/21/21-2025la/6D56BDCCA9B3/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F9526F3928>) |
| 1022:1583 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 46    | k10temp    | [F9526F3928](<All In One/Hewlett-Packard/21/21-2025la/6D56BDCCA9B3/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F9526F3928>) |
| 1022:1584 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 46    | fam15h_... | [F9526F3928](<All In One/Hewlett-Packard/21/21-2025la/6D56BDCCA9B3/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F9526F3928>) |
| 1022:1585 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 46    |            | [F9526F3928](<All In One/Hewlett-Packard/21/21-2025la/6D56BDCCA9B3/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F9526F3928>) |
| 8086:0101 | 106b:0000 | Intel            | Xeon E3-1200/2nd Generation Core ... | 46    | pcieport   | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 8086:8c10 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 46    | pcieport   | [7757BE603C](<All In One/Apple/iMac14/iMac14,2/3F4033EA2574/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/7757BE603C>) |
| 8086:8c14 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 46    | pcieport   | [7757BE603C](<All In One/Apple/iMac14/iMac14,2/3F4033EA2574/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/7757BE603C>) |
| 8086:8c16 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 46    | pcieport   | [7757BE603C](<All In One/Apple/iMac14/iMac14,2/3F4033EA2574/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/7757BE603C>) |
| 8086:8c18 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 46    | pcieport   | [7757BE603C](<All In One/Apple/iMac14/iMac14,2/3F4033EA2574/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/7757BE603C>) |
| 10de:0a82 |           | Nvidia           | MCP79 Host Bridge                    | 45    |            | [BF684BCED7](<All In One/Apple/iMac9/iMac9,1/B20C0E9191A5/MANJARO/5.15.19-1-MANJARO/X86_64/BF684BCED7>) |
| 10de:0aae | 10de:cb79 | Nvidia           | MCP79 LPC Bridge                     | 45    |            | [BF684BCED7](<All In One/Apple/iMac9/iMac9,1/B20C0E9191A5/MANJARO/5.15.19-1-MANJARO/X86_64/BF684BCED7>) |
| 8086:0100 | 106b:0000 | Intel            | 2nd Generation Core Processor Fam... | 45    | snb_uncore | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 8086:15d3 | 8086:0000 | Intel            | JHL6540 Thunderbolt 3 Bridge (C s... | 45    | pcieport   | [841AB4FFE2](<All In One/Apple/iMac18/iMac18,2/6AAE34125DB5/FEDORA-36/5.17.0-0.RC5.102.FC36.X86_64/X86_64/841AB4FFE2>) |
| 8086:2d01 | 8086:8086 | Intel            | Core Processor QuickPath Architec... | 44    |            | [99D7E82DF9](<All In One/Apple/iMac11/iMac11,2/9D11563CF50D/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/99D7E82DF9>) |
| 8086:2d10 | 8086:8086 | Intel            | Core Processor QPI Link 0            | 44    |            | [99D7E82DF9](<All In One/Apple/iMac11/iMac11,2/9D11563CF50D/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/99D7E82DF9>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:5229 | 17aa:365e | Realtek Semic... | RTS5229 PCI Express Card Reader      | 14    | rtsx_pci   | [485E063883](<All In One/Lenovo/C340/C340 10102/B4F39330CA94/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/485E063883>) |
| 10ec:5209 | 1025:8020 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 13    | rtsx_pci   | [520A9BC6A0](<All In One/Acer/Aspire/Aspire ZS600/307894E2C20C/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/520A9BC6A0>) |
| 10ec:5209 | 1028:0543 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 12    | rtsx_pci   | [F92FA1F111](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/04BEB2B29F37/CLEAR-LINUX-OS-35190/5.13.13-1070.NATIVE/X86_64/F92FA1F111>) |
| 10ec:5209 | 1028:0548 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 12    | rtsx_pci   | [6D6980BC69](<All In One/Dell/Inspiron/Inspiron One 2330/CC15798AE672/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/6D6980BC69>) |
| 10ec:5209 | 1028:05a7 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 11    | rtsx_pci   | [ED0DFEF2DF](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/FA6C8EA82464/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/ED0DFEF2DF>) |
| 10ec:5209 | 103c:2ac5 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 11    | rtsx_pci   | [DF20701C5E](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/2B14E403FA28/DEBIAN-10/5.10.0-0.BPO.3-AMD64/X86_64/DF20701C5E>) |
| 10ec:5209 | 1028:05db | Realtek Semic... | RTS5209 PCI Express Card Reader      | 9     | rtsx_pci   | [6B8B0EC7F9](<All In One/Dell/Inspiron/Inspiron 2350/62A6886810DD/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/6B8B0EC7F9>) |
| 10ec:5229 | 17aa:366c | Realtek Semic... | RTS5229 PCI Express Card Reader      | 7     | rtsx_pci   | [3903A96DE3](<All In One/Lenovo/C540/C540 10110/2B8EE2F234A3/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/3903A96DE3>) |
| 10ec:522a | 1028:0754 | Realtek Semic... | RTS522A PCI Express Card Reader      | 7     | rtsx_pci   | [00C297540D](<All In One/Dell/Inspiron/Inspiron 3464 AIO/31AD17DDDC01/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/00C297540D>) |
| 10ec:522a | 1854:0308 | Realtek Semic... | RTS522A PCI Express Card Reader      | 7     | rtsx_pci   | [F57C7BBE97](<All In One/LG Electronics/22V280/22V280-L.BY31P1/BF6C05A5FCC3/ENDEAVOUROS-ROLLING/5.13.12-ARCH1-1/X86_64/F57C7BBE97>) |
| 10ec:525a | 1028:06c5 | Realtek Semic... | RTS525A PCI Express Card Reader      | 7     | rtsx_pci   | [0DCB1B8C3C](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/34CACCC6D3D6/UBUNTU-20.04/5.13.0-32-GENERIC/X86_64/0DCB1B8C3C>) |
| 10ec:5229 | 103c:81b7 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 6     | rtsx_pci   | [35AB480926](<All In One/Hewlett-Packard/27/27-a154ng/BDD291411CF6/ARCH/5.16.10-ARCH1-1/X86_64/35AB480926>) |
| 10ec:5229 | 103c:82dc | Realtek Semic... | RTS5229 PCI Express Card Reader      | 6     | rtsx_pci   | [E3A85B9AAF](<All In One/Hewlett-Packard/27/27-a271ny/689111B5E631/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E3A85B9AAF>) |
| 10ec:5229 | 103c:2179 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 5     | rtsx_pci   | [79BAC7CE1B](<All In One/Hewlett-Packard/ProOne/ProOne 400 G1 AiO/F93097D5EFA1/XERO-ROLLING/5.15.12-ARCH1-1/X86_64/79BAC7CE1B>) |
| 10ec:5229 | 10ec:5229 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 5     | rtsx_pci   | [4CBAD8A144](<All In One/CSL-Computer/Unity/Unity F24W/DCF637E8FC6A/LINUXMINT-19.1/4.15.0-167-GENERIC/X86_64/4CBAD8A144>) |
| 10ec:5229 | 17aa:367b | Realtek Semic... | RTS5229 PCI Express Card Reader      | 5     | rtsx_pci   | [A459000D17](<All In One/Lenovo/IdeaCentre/IdeaCentre B550 F0A60004BR/96B34C085E78/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/A459000D17>) |
| 10ec:5229 | 17aa:3686 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 5     | rtsx_pci   | [7B95568874](<All In One/Lenovo/C560/C560 10150/393D3B2346F6/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/7B95568874>) |
| 10ec:5229 | 17aa:36ab | Realtek Semic... | RTS5229 PCI Express Card Reader      | 5     | rtsx_pci   | [AA6E9BA312](<All In One/Lenovo/C40-05/C40-05 F0B5002NCF/770FDA610B82/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/AA6E9BA312>) |
| 10ec:5249 | 103c:18e6 | Realtek Semic... | RTS5249 PCI Express Card Reader      | 5     | rtsx_pci   | [F8D1E58D06](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G1 AiO/44D1B0C864ED/LINUXMINT-18.3/4.15.0-142-GENERIC/X86_64/F8D1E58D06>) |
| 10ec:5289 | 17aa:3671 | Realtek Semic... | RTL8411 PCI Express Card Reader      | 5     | rtsx_pci   | [2A92010AD3](<All In One/Lenovo/C240/C240 10113/2C9D687CEE76/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/2A92010AD3>) |
| 10ec:5209 | 1028:05b0 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 4     | rtsx_pci   | [A06DFE0632](<All In One/Dell/XPS/XPS 2720/22BAEC305099/LINUXMINT-20.1/5.13.0-28-GENERIC/X86_64/A06DFE0632>) |
| 10ec:5209 | 17aa:3629 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 4     | rtsx_pci   | [7D3A0A3AD9](<All In One/Lenovo/C/C325/DC976463CB3E/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/7D3A0A3AD9>) |
| 10ec:5229 | 1025:085f | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx_pci   | [75EF8688A2](<All In One/Acer/Aspire/Aspire ZC-606/7E3C8CE0B8C9/LINUXMINT-19.3/5.4.0-96-GENERIC/X86_64/75EF8688A2>) |
| 10ec:5229 | 103c:2b0d | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx_pci   | [EF93DCE05C](<All In One/Hewlett-Packard/23/23-p010/51C1D74D49DB/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/EF93DCE05C>) |
| 10ec:5229 | 103c:2b3e | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx_pci   | [D11126F73D](<All In One/Hewlett-Packard/24/24-n014/8FD013C5503B/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/D11126F73D>) |
| 10ec:5229 | 17aa:3685 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx_pci   | [9333B9C923](<All In One/Lenovo/C460/C460 10149/45F639AE2A3D/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/9333B9C923>) |
| 10ec:5287 | 1297:2053 | Realtek Semic... | RTL8411B PCI Express Card Reader     | 4     | rtsx_pci   | [35E67A81CD](<All In One/Positivo/DH8/DH8BW01/0A5F7CE3222B/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/35E67A81CD>) |
| 10ec:5209 | 103c:2aed | Realtek Semic... | RTS5209 PCI Express Card Reader      | 3     | rtsx_pci   | [00FCD6CB57](<All In One/Hewlett-Packard/HP3520/HP3520 Aio/18652B622E3A/ROSA-2016.1/4.9.155-NRJ-DESKTOP-1ROSA-X86_64/X86_64/00FCD6CB57>) |
| 10ec:5209 | 1854:0167 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 3     | rtsx_pci   | [D0CF0BEEA8](<All In One/LG Electronics/V320/V320-M.BG31P1/B2985A63DB99/UBUNTU-18.04/4.15.0-142-GENERIC/X86_64/D0CF0BEEA8>) |
| 10ec:5229 | 103c:2b2f | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [06BE58F9B6](<All In One/Hewlett-Packard/18/18-5200br/3652E5CBCCE1/DEBIAN-11/5.10.0-9-AMD64/X86_64/06BE58F9B6>) |
| 10ec:5229 | 103c:838b | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [A8811301BC](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-r0xx/67514D08A17D/UBUNTU-20.10/5.8.0-45-GENERIC/X86_64/A8811301BC>) |
| 10ec:5229 | 17aa:3696 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [E18CF3C9D1](<All In One/Lenovo/S40-40/S40-40 F0AX0053PB/A9A8B8D300C2/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E18CF3C9D1>) |
| 10ec:5229 | 17aa:369c | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [D0194FC092](<All In One/Lenovo/B50-30/B50-30 F0AU001YUS/6D591A8B8CEF/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/D0194FC092>) |
| 10ec:5229 | 17aa:36ed | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [B5D4B3357A](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 330-20IGM F0D70043CK/77A4D86B366E/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B5D4B3357A>) |
| 10ec:522a | 103c:85a2 | Realtek Semic... | RTS522A PCI Express Card Reader      | 3     | rtsx_pci   | [F0691E6EDA](<All In One/Hewlett-Packard/ProOne/ProOne 600 G5 21.5-in All-in-One/FC490F22A5D6/MANJARO/5.10.23-1-MANJARO/X86_64/F0691E6EDA>) |
| 10ec:522a | 10ec:522a | Realtek Semic... | RTS522A PCI Express Card Reader      | 3     | rtsx_pci   | [41FA541CA4](<All In One/LG Electronics/22V270/22V270-L.BJ31P1/F6B5728652E7/UBUNTU-20.04/5.4.0-47-GENERIC/X86_64/41FA541CA4>) |
| 10ec:525a | 1028:079c | Realtek Semic... | RTS525A PCI Express Card Reader      | 3     | rtsx_pci   | [0B0F9A42CD](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/F87DB1F1F5AC/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/0B0F9A42CD>) |
| 10ec:525a | 1028:0984 | Realtek Semic... | RTS525A PCI Express Card Reader      | 3     | rtsx_pci   | [EA489D447C](<All In One/Dell/OptiPlex/OptiPlex 7480 AIO/AA453186B2B9/LINUXMINT-20.1/5.4.0-104-GENERIC/X86_64/EA489D447C>) |
| 10ec:5289 | 1297:2032 | Realtek Semic... | RTL8411 PCI Express Card Reader      | 3     | rtsx_pci   | [26A6CD4678](<All In One/Positivo/DC8/DC8BT11/67631B5005CA/POP!_OS-20.04/5.4.0-7642-GENERIC/X86_64/26A6CD4678>) |
| 10ec:5289 | 17aa:3670 | Realtek Semic... | RTL8411 PCI Express Card Reader      | 3     | rtsx_pci   | [225E0C36DC](<All In One/Lenovo/C245/C245 10114/D4553E683441/XUBUNTU-18.04/5.3.0-28-GENERIC/I686/225E0C36DC>) |
| 10ec:5209 | 1028:054b | Realtek Semic... | RTS5209 PCI Express Card Reader      | 2     | rtsx_pci   | [FCD0EF9F0E](<All In One/Dell/XPS/XPS One 2710/E83BF6F5E12A/POP!_OS-21.04/5.13.0-7614-GENERIC/X86_64/FCD0EF9F0E>) |
| 10ec:5209 | 1179:ff1e | Realtek Semic... | RTS5209 PCI Express Card Reader      | 2     | rtsx_pci   | [E1BB0618FD](<All In One/Toshiba/DX/DX730/EB2297CCFE3E/UBUNTU-18.04/4.18.0-15-GENERIC/X86_64/E1BB0618FD>) |
| 10ec:5209 | 1b0a:0183 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 2     | rtsx_pci   | [78D39E18EF](<All In One/Pegatron/H81/H81-P1/1DBAFEC13877/UBUNTU-18.04/4.15.0-43-GENERIC/X86_64/78D39E18EF>) |
| 10ec:5227 | 103c:2b1c | Realtek Semic... | RTS5227 PCI Express Card Reader      | 2     | rtsx_pci   | [EA47F5ADBE](<All In One/Hewlett-Packard/23/23-n010ne/DD737DCCDFC9/KALI-2021.1/5.10.0-KALI5-AMD64/X86_64/EA47F5ADBE>) |
| 10ec:5229 | 103c:18ea | Realtek Semic... | RTS5229 PCI Express Card Reader      | 2     | rtsx_pci   | [FFBC26C0F1](<All In One/Hewlett-Packard/ProOne/ProOne 400 G1 AiO/950E0229189F/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/FFBC26C0F1>) |
| 10ec:5229 | 103c:2afc | Realtek Semic... | RTS5229 PCI Express Card Reader      | 2     | rtsx_pci   | [7A71F7247E](<All In One/Hewlett-Packard/23/23-b237c/071341049EF0/UBUNTU-20.04/5.7.8-WINDOWSFX-GENERIC/X86_64/7A71F7247E>) |
| 10ec:5229 | 103c:2b0a | Realtek Semic... | RTS5229 PCI Express Card Reader      | 2     | rtsx_pci   | [BA22741458](<All In One/Hewlett-Packard/20/20-2010el/9602F13BC818/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/BA22741458>) |
| 10ec:5229 | 103c:2b13 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 2     | rtsx_pci   | [991915273E](<All In One/Hewlett-Packard/22/22-h020ef/A7730E2637A2/UBUNTU-20.04/5.8.0-43-GENERIC/X86_64/991915273E>) |
| 10ec:5229 | 103c:2b3b | Realtek Semic... | RTS5229 PCI Express Card Reader      | 2     | rtsx_pci   | [BA4DA15B98](<All In One/Hewlett-Packard/23/23-r191la/FC3FF24DBFA4/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/BA4DA15B98>) |
| 10ec:5229 | 103c:82f3 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 2     | rtsx_pci   | [DAF0CCBC42](<All In One/Hewlett-Packard/ENVY/ENVY 27-b114/BB85DDA47130/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/DAF0CCBC42>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10de:0aa3 | 10de:cb79 | Nvidia           | MCP79 Co-processor                   | 88    | nvidia     | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 10de:0753 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 7     |            | [04B8123AA5](<All In One/Acer/Aspire/Aspire Z3101/EDA041C04858/UBUNTU-18.04/4.15.0-96-GENERIC/X86_64/04B8123AA5>) |
| 10de:0aa3 | 1462:4570 | Nvidia           | MCP79 Co-processor                   | 4     | nvidia     | [BF5395A5D3](<All In One/MSI/MS-AA/MS-AA1511/EC062EE8E1B7/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/BF5395A5D3>) |
| 10de:0aa3 | 1043:8379 | Nvidia           | MCP79 Co-processor                   | 2     |            | [72365E4985](<All In One/ASUSTek Computer/ET/ET2002/9AD492BE589B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/72365E4985>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c3a | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 103   | mei_me     | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 8086:a13a | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 57    | mei_me     | [436904EAE3](<All In One/Apple/iMac17/iMac17,1/7E034427C03F/DEBIAN-11/5.10.0-12-AMD64/X86_64/436904EAE3>) |
| 8086:8c3a | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 46    | mei_me     | [7757BE603C](<All In One/Apple/iMac14/iMac14,2/3F4033EA2574/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/7757BE603C>) |
| 8086:1e3a | 8086:7270 | Intel            | 7 Series/C216 Chipset Family MEI ... | 32    | mei_me     | [435548337A](<All In One/Apple/iMac13/iMac13,1/BB29D11F01EF/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/435548337A>) |
| 8086:a360 | 8086:7270 | Intel            | Cannon Lake PCH HECI Controller      | 32    | mei_me     | [5E0CEEF0D1](<All In One/Apple/iMac19/iMac19,2/B4B5423C68DB/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/5E0CEEF0D1>) |
| 8086:a328 | 8086:7270 | Intel            | Cannon Lake PCH Serial IO UART Ho... | 31    | intel_l... | [5E0CEEF0D1](<All In One/Apple/iMac19/iMac19,2/B4B5423C68DB/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/5E0CEEF0D1>) |
| 8086:a329 | 8086:7270 | Intel            | 300 Series Chipset Family            | 31    | intel_l... | [5E0CEEF0D1](<All In One/Apple/iMac19/iMac19,2/B4B5423C68DB/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/5E0CEEF0D1>) |
| 8086:1c3a | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 14    | mei_me     | [485E063883](<All In One/Lenovo/C340/C340 10102/B4F39330CA94/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/485E063883>) |
| 8086:9d3a | 103c:84de | Intel            | Sunrise Point-LP CSME HECI #1        | 14    | mei_me     | [43184FD6BF](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/3E27DCFED7C5/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/43184FD6BF>) |
| 8086:1e3a | 1028:0543 | Intel            | 7 Series/C216 Chipset Family MEI ... | 12    | mei_me     | [F92FA1F111](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/04BEB2B29F37/CLEAR-LINUX-OS-35190/5.13.13-1070.NATIVE/X86_64/F92FA1F111>) |
| 8086:1e3a | 1028:0548 | Intel            | 7 Series/C216 Chipset Family MEI ... | 12    | mei_me     | [6D6980BC69](<All In One/Dell/Inspiron/Inspiron One 2330/CC15798AE672/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/6D6980BC69>) |
| 8086:1c3a | 1028:0511 | Intel            | 6 Series/C200 Series Chipset Fami... | 11    | mei_me     | [6008FDA2AD](<All In One/Dell/Inspiron/Inspiron One 2320/61122D664D9D/UBUNTU-21.10/5.13.0-23-GENERIC/X86_64/6008FDA2AD>) |
| 8086:1c3a | 103c:2ac5 | Intel            | 6 Series/C200 Series Chipset Fami... | 11    | mei_me     | [DF20701C5E](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/2B14E403FA28/DEBIAN-10/5.10.0-0.BPO.3-AMD64/X86_64/DF20701C5E>) |
| 8086:8c3a | 1028:05a7 | Intel            | 8 Series/C220 Series Chipset Fami... | 11    | mei_me     | [ED0DFEF2DF](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/FA6C8EA82464/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/ED0DFEF2DF>) |
| 8086:9d3a | 8086:9d3a | Intel            | Sunrise Point-LP CSME HECI #1        | 10    | mei_me     | [8826665773](<All In One/ASUSTek Computer/ZN240/ZN240IC/B519220D6F37/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/8826665773>) |
| 8086:319a | 1025:1304 | Intel            | Celeron/Pentium Silver Processor ... | 9     | mei_me     | [B7F823BFDA](<All In One/Others/Others/Others/EFF35801EAC2/UBUNTU/5.8.0-14-GENERIC/X86_64/B7F823BFDA>) |
| 8086:8c3a | 1028:05db | Intel            | 8 Series/C220 Series Chipset Fami... | 9     | mei_me     | [6B8B0EC7F9](<All In One/Dell/Inspiron/Inspiron 2350/62A6886810DD/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/6B8B0EC7F9>) |
| 8086:9d3a | 1025:1287 | Intel            | Sunrise Point-LP CSME HECI #1        | 9     | mei_me     | [70014EA10E](<All In One/Acer/Aspire/Aspire C22-865/CAE70310F314/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/70014EA10E>) |
| 8086:a360 | 103c:84ee | Intel            | Cannon Lake PCH HECI Controller      | 9     | mei_me     | [2311649D51](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-xa0xxx/3187A1587DA6/LINUXMINT-20.2/5.4.0-90-GENERIC/X86_64/2311649D51>) |
| 8086:1c3a | 104d:907e | Intel            | 6 Series/C200 Series Chipset Fami... | 8     | mei_me     | [0451CAEB29](<All In One/Sony/VPCL212/VPCL212FX/01EE677E7F92/UBUNTU-21.10/5.13.0-22-GENERIC/X86_64/0451CAEB29>) |
| 8086:1c3a | 17aa:366c | Intel            | 6 Series/C200 Series Chipset Fami... | 7     | mei_me     | [3903A96DE3](<All In One/Lenovo/C540/C540 10110/2B8EE2F234A3/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/3903A96DE3>) |
| 8086:1e3a | 144d:b091 | Intel            | 7 Series/C216 Chipset Family MEI ... | 7     | mei_me     | [DD513D338C](<All In One/Samsung Electronics/DP700/DP700A3D-DM700A3D-DB701A3D-DP700A7D/F34D6AA53F0D/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/DD513D338C>) |
| 8086:319a | 1854:0308 | Intel            | Celeron/Pentium Silver Processor ... | 7     | mei_me     | [F57C7BBE97](<All In One/LG Electronics/22V280/22V280-L.BY31P1/BF6C05A5FCC3/ENDEAVOUROS-ROLLING/5.13.12-ARCH1-1/X86_64/F57C7BBE97>) |
| 8086:3b64 | 17aa:306a | Intel            | 5 Series/3400 Series Chipset HECI... | 7     | mei_me     | [0EF323D23D](<All In One/Lenovo/ThinkCentre/ThinkCentre M90z 5205RQ1/DDABC203DAB8/UBUNTU-20.04/5.8.0-53-GENERIC/X86_64/0EF323D23D>) |
| 8086:8cba | 8086:7270 | Intel            | 9 Series Chipset Family ME Interf... | 7     | mei_me     | [BC313CE031](<All In One/Apple/iMac16/iMac16,2/224B9F366AD7/ENDEAVOUROS-ROLLING/5.15.7-ARCH1-1/X86_64/BC313CE031>) |
| 8086:9d3a | 1028:0754 | Intel            | Sunrise Point-LP CSME HECI #1        | 7     | mei_me     | [00C297540D](<All In One/Dell/Inspiron/Inspiron 3464 AIO/31AD17DDDC01/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/00C297540D>) |
| 8086:1e3a | 104d:9097 | Intel            | 7 Series/C216 Chipset Family MEI ... | 6     | mei_me     | [4D477A343A](<All In One/Sony/SVL2411/SVL24117FLB/B337A07B7653/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/4D477A343A>) |
| 8086:319a | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 6     | mei_me     | [10E8B5B5BD](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/10E8B5B5BD>) |
| 8086:8c3a | 1028:0623 | Intel            | 8 Series/C220 Series Chipset Fami... | 6     | mei_me     | [FE22676441](<All In One/Dell/OptiPlex/OptiPlex 3030 AIO/F73EB67F5BAB/FEDORA-35/5.14.14-300.FC35.X86_64/X86_64/FE22676441>) |
| 8086:8c3a | 103c:18e6 | Intel            | 8 Series/C220 Series Chipset Fami... | 6     | mei_me     | [F8D1E58D06](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G1 AiO/44D1B0C864ED/LINUXMINT-18.3/4.15.0-142-GENERIC/X86_64/F8D1E58D06>) |
| 8086:9de0 | 1043:17b1 | Intel            | Cannon Point-LP MEI Controller #1    | 6     | mei_me     | [60C6C7EA7C](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/3602C27EA430/ENDLESS-3.9.6/5.8.0-14-GENERIC/X86_64/60C6C7EA7C>) |
| 8086:a13a | 1028:06c5 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     | mei_me     | [0DCB1B8C3C](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/34CACCC6D3D6/UBUNTU-20.04/5.13.0-32-GENERIC/X86_64/0DCB1B8C3C>) |
| 8086:1c3a | 1019:7c94 | Intel            | 6 Series/C200 Series Chipset Fami... | 5     | mei_me     | [DD57D8772A](<All In One/Seneca/pro/pro399288/812FEDFC17B0/UBUNTU-21.04/5.11.0-18-GENERIC/X86_64/DD57D8772A>) |
| 8086:1c3a | 104d:9083 | Intel            | 6 Series/C200 Series Chipset Fami... | 5     | mei_me     | [EEB433BF77](<All In One/Sony/VPCJ21/VPCJ21S1E/704C84A1D492/LINUXMINT-20.1/5.8.0-53-GENERIC/X86_64/EEB433BF77>) |
| 8086:1e3a | 17aa:3671 | Intel            | 7 Series/C216 Chipset Family MEI ... | 5     | mei_me     | [2A92010AD3](<All In One/Lenovo/C240/C240 10113/2C9D687CEE76/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/2A92010AD3>) |
| 8086:319a | 103c:86f0 | Intel            | Celeron/Pentium Silver Processor ... | 5     | mei_me     | [75738404AE](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-df0xxx/20A2CA3001FD/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/75738404AE>) |
| 8086:319a | 1043:1e80 | Intel            | Celeron/Pentium Silver Processor ... | 5     | mei_me     | [23082AB8CA](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222GA_V222GA/30DB3562CA34/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/23082AB8CA>) |
| 8086:34e0 | 1025:1418 | Intel            | Ice Lake-LP Management Engine        | 5     | mei_me     | [F15CA34264](<All In One/Acer/Aspire/Aspire C27-962/A23104408196/LINUXMINT-20.3/5.4.0-92-GENERIC/X86_64/F15CA34264>) |
| 8086:5a9a | 17aa:36c4 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 5     | mei_me     | [C2A07B6931](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 310-20IAP F0CL005CRK/234016A28DFB/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/C2A07B6931>) |
| 8086:8c3a | 1028:0626 | Intel            | 8 Series/C220 Series Chipset Fami... | 5     | mei_me     | [8F04A0DF98](<All In One/Dell/Inspiron/Inspiron 23 Model 5348/39CAC93F617B/UBUNTU-21.04/5.11.0-34-GENERIC/X86_64/8F04A0DF98>) |
| 8086:8c3a | 103c:2179 | Intel            | 8 Series/C220 Series Chipset Fami... | 5     | mei_me     | [79BAC7CE1B](<All In One/Hewlett-Packard/ProOne/ProOne 400 G1 AiO/F93097D5EFA1/XERO-ROLLING/5.15.12-ARCH1-1/X86_64/79BAC7CE1B>) |
| 8086:8c3a | 17aa:367b | Intel            | 8 Series/C220 Series Chipset Fami... | 5     | mei_me     | [A459000D17](<All In One/Lenovo/IdeaCentre/IdeaCentre B550 F0A60004BR/96B34C085E78/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/A459000D17>) |
| 8086:8c3a | 17aa:3686 | Intel            | 8 Series/C220 Series Chipset Fami... | 5     | mei_me     | [7B95568874](<All In One/Lenovo/C560/C560 10150/393D3B2346F6/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/7B95568874>) |
| 8086:9cba | 8086:7270 | Intel            | Wildcat Point-LP MEI Controller #1   | 5     | mei_me     | [6514199D0C](<All In One/Apple/iMac16/iMac16,1/4BCFE045F418/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/6514199D0C>) |
| 8086:9cba | 8086:9cba | Intel            | Wildcat Point-LP MEI Controller #1   | 5     | mei_me     | [84E7C5B8B5](<All In One/BESSTAR Tech/U/U700/6A863B3F6857/LINUXMINT-20.1/5.11.0-22-GENERIC/X86_64/84E7C5B8B5>) |
| 8086:9d3a | 8086:7270 | Intel            | Sunrise Point-LP CSME HECI #1        | 5     | mei_me     | [E0D2C2356F](<All In One/Apple/iMac18/iMac18,1/447C402E8489/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/E0D2C2356F>) |
| 8086:a0e0 | 1028:0a06 | Intel            | Tiger Lake-LP Management Engine I... | 5     | mei_me     | [503D10D676](<All In One/Dell/Inspiron/Inspiron 5400 AIO/1B0441A55B57/ZORIN-16/5.11.0-38-GENERIC/X86_64/503D10D676>) |
| 8086:a13a | 103c:82dc | Intel            | 100 Series/C230 Series Chipset Fa... | 5     | mei_me     | [E3A85B9AAF](<All In One/Hewlett-Packard/27/27-a271ny/689111B5E631/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E3A85B9AAF>) |
| 8086:a13a | 8086:a13a | Intel            | 100 Series/C230 Series Chipset Fa... | 5     | mei_me     | [31E48D8DA1](<All In One/ASUSTek Computer/Z240/Z240IC-H170/FB2F1250F58B/POP!_OS-20.10/5.8.0-7642-GENERIC/X86_64/31E48D8DA1>) |
| 8086:a360 | 103c:8446 | Intel            | Cannon Lake PCH HECI Controller      | 5     | mei_me     | [46A47AB08E](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/D3EA8545A30E/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/46A47AB08E>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1537 | 1022:1537 | AMD              | Kabini/Mullins PSP-Platform Secur... | 18    | ccp        | [6F6101B39B](<All In One/Hewlett-Packard/23/23-p112/E4C61E0250B4/FEDORA-35/5.15.5-200.FC35.X86_64/X86_64/6F6101B39B>) |
| 1022:1537 | 103c:8245 | AMD              | Kabini/Mullins PSP-Platform Secur... | 15    | ccp        | [BFDC2533BB](<All In One/Hewlett-Packard/20/20-c211la/6F4CC01CA4A6/LINUXMINT-20.3/5.4.0-96-GENERIC/X86_64/BFDC2533BB>) |
| 1022:1578 | 103c:8381 | AMD              | Carrizo Platform Security Processor  | 11    |            | [0DC8027649](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/B4EEA135048F/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/0DC8027649>) |
| 1022:1578 | 103c:8430 | AMD              | Carrizo Platform Security Processor  | 10    |            | [56C6D48F6E](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/A2E8399A62AF/ENDEAVOUROS-ROLLING/5.14.2-ARCH1-2/X86_64/56C6D48F6E>) |
| 8086:2298 | 103c:81bb | Intel            | Atom/Celeron/Pentium Processor x5... | 8     | mei_txe    | [516F843813](<All In One/Hewlett-Packard/22/22-b009na/2C2C0369DE9C/KALI-2021.4/5.15.0-KALI2-AMD64/X86_64/516F843813>) |
| 1022:1537 | 103c:2b3b | AMD              | Kabini/Mullins PSP-Platform Secur... | 7     | ccp        | [B3DCCF594C](<All In One/Hewlett-Packard/23/23-r035la/8A9A83560619/ZORIN-16/5.13.0-27-GENERIC/X86_64/B3DCCF594C>) |
| 1022:15df | 103c:86f3 | AMD              | Family 17h (Models 10h-1fh) Platf... | 6     | ccp        | [7DE0381DB8](<All In One/Hewlett-Packard/205/205 G4 22 All-in-One PC/F158F87A803B/SLACKWARE-15.0/5.15.27/X86_64/7DE0381DB8>) |
| 8086:0f18 | 17aa:3695 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | mei_txe    | [3E79CADCEA](<All In One/Lenovo/C260/C260 10160/A6FBDDCB0193/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/3E79CADCEA>) |
| 8086:2298 | 1028:06cc | Intel            | Atom/Celeron/Pentium Processor x5... | 6     | mei_txe    | [3AC5DA5F93](<All In One/Dell/Inspiron/Inspiron 20-3052/E44132686405/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/3AC5DA5F93>) |
| 1022:1578 | 1022:1578 | AMD              | Carrizo Platform Security Processor  | 5     |            | [0DD6576588](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-22AST F0D6002EFR/7FE429038D53/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/0DD6576588>) |
| 8086:0f18 |           | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 5     | mei_txe    | [29A6B45091](<All In One/Acer/Aspire/Aspire Z1-601/0EFA289080ED/LUBUNTU-18.04/4.15.0-151-GENERIC/I686/29A6B45091>) |
| 8086:0f18 | 1028:0690 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 5     | mei_txe    | [F96E26BB9A](<All In One/Dell/Inspiron/Inspiron 20 Model 3043/16F41C0EA91A/ZORIN-16/5.13.0-30-GENERIC/X86_64/F96E26BB9A>) |
| 8086:0f18 | 1854:0200 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 5     | mei_txe    | [23B20C26F2](<All In One/LG Electronics/22V240/22V240-L.BK55P1/673803797B34/XUBUNTU-20.04/5.13.0-30-GENERIC/X86_64/23B20C26F2>) |
| 1022:1456 | 1022:1456 | AMD              | Family 17h (Models 00h-0fh) Platf... | 4     | ccp        | [81AF87F00C](<All In One/Dell/Inspiron/Inspiron 27 7775/D1240D4484D8/ELEMENTARY-5.1.7/5.4.0-89-GENERIC/X86_64/81AF87F00C>) |
| 8086:0f18 | 1025:085f | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 4     | mei_txe    | [75EF8688A2](<All In One/Acer/Aspire/Aspire ZC-606/7E3C8CE0B8C9/LINUXMINT-19.3/5.4.0-96-GENERIC/X86_64/75EF8688A2>) |
| 8086:2298 | 1297:2053 | Intel            | Atom/Celeron/Pentium Processor x5... | 4     | mei_txe    | [35E67A81CD](<All In One/Positivo/DH8/DH8BW01/0A5F7CE3222B/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/35E67A81CD>) |
| 1022:1537 | 103c:2b2f | AMD              | Kabini/Mullins PSP-Platform Secur... | 3     | ccp        | [06BE58F9B6](<All In One/Hewlett-Packard/18/18-5200br/3652E5CBCCE1/DEBIAN-11/5.10.0-9-AMD64/X86_64/06BE58F9B6>) |
| 1022:1578 | 1028:07e3 | AMD              | Carrizo Platform Security Processor  | 3     |            | [87A4F1E989](<All In One/Dell/Inspiron/Inspiron 24 5475/44B04AE381C1/UBUNTU-18.04/5.4.0-89-GENERIC/X86_64/87A4F1E989>) |
| 1022:15df | 1022:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     | ccp        | [8259FB58CE](<All In One/iRU/J/J2335/CF1EEDC28C45/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/8259FB58CE>) |
| 1022:15df | 103c:86ee | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     | ccp        | [B200DC3D0F](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-k0xxx/3A4D1D72C41E/UBUNTU-20.04/5.11.0-46-GENERIC/X86_64/B200DC3D0F>) |
| 1022:15df | 17aa:36f5 | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     | ccp        | [EB38810FB8](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-24ARR F0DN006KGE/1D5E59C5CB5F/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/EB38810FB8>) |
| 1022:15df | 17aa:371c | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     | ccp        | [6C4714D241](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 24ARE05 F0EW00FLSC/74D0340E2EB1/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/6C4714D241>) |
| 8086:0f18 | 1025:0994 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     | mei_txe    | [6247D83BAB](<All In One/Acer/Aspire/Aspire Z1-611/A6EFF7123453/LINUXMINT-19.1/4.15.0-128-GENERIC/X86_64/6247D83BAB>) |
| 8086:0f18 | 1297:2041 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     | mei_txe    | [26A6CD4678](<All In One/Positivo/DC8/DC8BT11/67631B5005CA/POP!_OS-20.04/5.4.0-7642-GENERIC/X86_64/26A6CD4678>) |
| 8086:2298 | 1025:0992 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | mei_txe    | [A8ED405BDB](<All In One/Acer/Aspire/Aspire ZC-700G/612A7DF81DC0/LINUXMINT-20.1/5.4.0-58-GENERIC/X86_64/A8ED405BDB>) |
| 8086:2298 | 8086:2298 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | mei_txe    | [8FD1F10C40](<All In One/ASUSTek Computer/A/A4110/816792239BA1/ZORIN-16/5.13.0-30-GENERIC/X86_64/8FD1F10C40>) |
| 1022:1578 | 17aa:36bd | AMD              | Carrizo Platform Security Processor  | 2     |            | [CE295294E2](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 510-23ASR F0CE0015UK/7C4A00A8EBE8/KUBUNTU-19.10/5.3.0-51-GENERIC/X86_64/CE295294E2>) |
| 1022:1578 | 17aa:36be | AMD              | Carrizo Platform Security Processor  | 2     |            | [4863245A0E](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 510-22ASR F0CC000RLD/54235580CC91/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/4863245A0E>) |
| 1022:1578 | 17aa:36ec | AMD              | Carrizo Platform Security Processor  | 2     |            | [2CFA2D338E](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 330-20AST F0D8001LUS/36DA6D8B2B0D/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/2CFA2D338E>) |
| 1022:15df | 103c:8449 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     | ccp        | [A1CB66A671](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-r0xx/117890FC2D25/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/A1CB66A671>) |
| 1022:15df | 103c:84ef | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     | ccp        | [94918CE530](<All In One/Hewlett-Packard/84EF/84EF 01100/71672B489844/UBUNTU-21.04/5.11.0-31-GENERIC/X86_64/94918CE530>) |
| 1022:15df | 103c:8582 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     | ccp        | [BACA8B82E5](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c1xx/B53C48E864B9/UBUNTU-20.10/5.8.0-36-GENERIC/X86_64/BACA8B82E5>) |
| 1022:15df | 103c:85ba | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     | ccp        | [082D2AE17D](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa1xxx/99B46DAA2CED/ARCH-ROLLING/5.15.5-ARCH1-1/X86_64/082D2AE17D>) |
| 1022:15df | 103c:86f1 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     | ccp        | [4DB843D0C6](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-dp0xxx/F7426AF86A80/OPENMANDRIVA-4.50/5.16.3-DESKTOP-2OMV4050/X86_64/4DB843D0C6>) |
| 1022:15df | 17aa:3703 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     | ccp        | [5DA493DE55](<All In One/Lenovo/IdeaCentre/IdeaCentre A540-24API F0EM0000UK/93E2EABF69EE/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/5DA493DE55>) |
| 8086:0f18 | 17aa:368a | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | mei_txe    | [08057029E5](<All In One/Lenovo/N300/N300 10161/C819A7104F2E/KDE-NEON-18.04/5.4.0-42-GENERIC/X86_64/08057029E5>) |
| 8086:0f18 | 17aa:36a8 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | mei_txe    | [5F6FF0EBDA](<All In One/Lenovo/S20-00/S20-00 F0AY000CRK/EE8C5812AAF0/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/5F6FF0EBDA>) |
| 8086:2298 | 1025:098f | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | mei_txe    | [350CC83AC7](<All In One/Acer/Aspire/Aspire Z1-622/12DC70B153E8/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/350CC83AC7>) |
| 8086:2298 | 1025:1065 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | mei_txe    | [21CA50C386](<All In One/Acer/Aspire/Aspire C20-720/0880373379ED/ROSA-2016.1/4.15.0-DESKTOP-51.4ROSA-X86_64/X86_64/21CA50C386>) |
| 1022:1486 | 1022:1486 | AMD              | Starship/Matisse Cryptographic Co... | 1     | ccp        | [991A74F3E5](<All In One/Acidanthera/iMacPro1/iMacPro1,1/068603353593/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/991A74F3E5>) |
| 1022:1486 | 1043:87c0 | AMD              | Starship/Matisse Cryptographic Co... | 1     | ccp        | [577AD83B8F](<All In One/Acidanthera/iMacPro1/iMacPro1,1/6286842FEC0E/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/577AD83B8F>) |
| 1022:1537 | 103c:2b31 | AMD              | Kabini/Mullins PSP-Platform Secur... | 1     | ccp        | [F9526F3928](<All In One/Hewlett-Packard/21/21-2025la/6D56BDCCA9B3/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F9526F3928>) |
| 1022:1537 | 103c:2b42 | AMD              | Kabini/Mullins PSP-Platform Secur... | 1     | ccp        | [42D66AED80](<All In One/Hewlett-Packard/23/23-q014a/412A4AE1BE51/ELEMENTARY-6/5.11.0-37-GENERIC/X86_64/42D66AED80>) |
| 1022:1537 | 103c:2b54 | AMD              | Kabini/Mullins PSP-Platform Secur... | 1     | ccp        | [161455EFD7](<All In One/Hewlett-Packard/20/20-e003la/7A681895544B/UBUNTU-20.04/5.4.0-51-GENERIC/X86_64/161455EFD7>) |
| 1022:1578 | 1028:0854 | AMD              | Carrizo Platform Security Processor  | 1     |            | [BEF244106F](<All In One/Dell/Inspiron/Inspiron 3475 AIO/EA044F848CBC/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/BEF244106F>) |
| 1022:1578 | 1028:0855 | AMD              | Carrizo Platform Security Processor  | 1     |            | [DACA9432F8](<All In One/Dell/Inspiron/Inspiron 3275 AIO/6D40C1FA2274/LINUXMINT-19.2/4.15.0-65-GENERIC/X86_64/DACA9432F8>) |
| 1022:1578 | 103c:81b9 | AMD              | Carrizo Platform Security Processor  | 1     |            | [15C46542B5](<All In One/Hewlett-Packard/24/24-b224la/5211CD5F3090/UBUNTU-18.04/5.0.0-23-GENERIC/X86_64/15C46542B5>) |
| 1022:1578 | 103c:8374 | AMD              | Carrizo Platform Security Processor  | 1     |            | [DEEDD3ED67](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-r0xx/E65B37A798F3/LINUXMINT-19.3/5.3.0-28-GENERIC/X86_64/DEEDD3ED67>) |
| 1022:1578 | 103c:84f0 | AMD              | Carrizo Platform Security Processor  | 1     |            | [0ACFC1AB65](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/4C0E5938F484/ZORIN-16/5.11.0-27-GENERIC/X86_64/0ACFC1AB65>) |
| 1022:15df | 1043:1832 | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     | ccp        | [C1F6B30A92](<All In One/ASUSTek Computer/ASUS/ASUS ZEN AIO M5401WUA_M5401WUA/446C2FD0324E/ARCO-ROLLING/5.15.2-ARCH1-1/X86_64/C1F6B30A92>) |

### Firewire controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 11c1:5901 | 11c1:5900 | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 256   | firewir... | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 104c:823f |           | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 99    | firewir... | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 11c1:5811 | 11c1:5811 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 21    | firewir... | [261E6C0463](<All In One/Apple/iMac5/iMac5,1/F72BF7BFE069/LMDE-5/5.10.0-11-686/I686/261E6C0463>) |
| 1180:e832 | 104d:907e | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 8     | firewir... | [0451CAEB29](<All In One/Sony/VPCL212/VPCL212FX/01EE677E7F92/UBUNTU-21.10/5.13.0-22-GENERIC/X86_64/0451CAEB29>) |
| 1180:e832 | 104d:9097 | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 6     | firewir... | [4D477A343A](<All In One/Sony/SVL2411/SVL24117FLB/B337A07B7653/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/4D477A343A>) |
| 197b:2380 | 17aa:3602 | JMicron Techn... | IEEE 1394 Host Controller            | 4     | firewir... | [C25FDFE643](<All In One/Lenovo/IdeaCentre/IdeaCentre B300 10051/20208F91C976/ENDLESS-3.8.6/5.4.0-42-GENERIC/X86_64/C25FDFE643>) |
| 1180:e832 | 104d:9060 | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 3     | firewir... | [05CFF66AC2](<All In One/Sony/VPCL11/VPCL11M1E/93DA71AEEC1E/UBUNTU-19.04/5.0.0-27-GENERIC/X86_64/05CFF66AC2>) |
| 1180:e832 | 104d:9074 | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 3     | firewir... | [D1D4080F45](<All In One/Sony/VPCJ118/VPCJ118FW/7247E7BFDC34/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D1D4080F45>) |
| 197b:2380 | 103c:1489 | JMicron Techn... | IEEE 1394 Host Controller            | 3     | firewir... | [F321ECCADC](<All In One/Hewlett-Packard/Compaq/Compaq 6000 Pro AiO Brazil PC/8D326FF3188E/POP!_OS-21.10/5.15.11-76051511-GENERIC/X86_64/F321ECCADC>) |
| 104c:8025 |           | Texas Instrum... | TSB82AA2 IEEE-1394b Link Layer Co... | 2     | firewir... | [2BAA39FB91](<All In One/Apple/iMac6/iMac6,1/06954601F29C/UBUNTU-16.04/4.15.0-88-GENERIC/X86_64/2BAA39FB91>) |
| 1180:0832 | 104d:9043 | Ricoh            | R5C832 IEEE 1394 Controller          | 2     | firewir... | [AFA509714D](<All In One/Sony/VGC-LN52/VGC-LN52JGB/54F15FF48E03/UBUNTU-20.04/5.8.0-54-GENERIC/X86_64/AFA509714D>) |
| 1180:0832 | 104d:9044 | Ricoh            | R5C832 IEEE 1394 Controller          | 2     | firewir... | [EB74857893](<All In One/Sony/VGC-JS210/VGC-JS210J/8B88CB56EBD6/ENDLESS-3.8.6/5.4.0-42-GENERIC/X86_64/EB74857893>) |
| 1180:e832 | 104d:908e | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 2     | firewir... | [E43A2C01EB](<All In One/Sony/VPCL22/VPCL22Z1R/BC94F4FEC1E7/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/E43A2C01EB>) |
| 1217:13f7 | 1bcf:a013 | O2 Micro         | 1394 OHCI Compliant Host Controller  | 2     | firewir... | [1494683BB9](<All In One/NEC Computers/PC-VN770/PC-VN770DS3ER/18CEF0AA43DB/UBUNTU-20.04/5.8.0-48-GENERIC/X86_64/1494683BB9>) |
| 197b:2380 | 103c:3561 | JMicron Techn... | IEEE 1394 Host Controller            | 2     | firewir... | [5FF1D7A72E](<All In One/Hewlett-Packard/Z1/Z1 Workstation/4089A5726DF1/FEDORA-35/5.14.18-300.FC35.X86_64/X86_64/5FF1D7A72E>) |
| 104c:8024 | 9005:0030 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 1     | firewir... | [098FE372A3](<All In One/Acidanthera/iMac14/iMac14,4/E2C69985CC45/GENTOO-2.6/5.4.97-GENTOO_DQ87PG/X86_64/098FE372A3>) |
| 104c:8029 | 107b:4009 | Texas Instrum... | PCI4510 IEEE-1394 Controller         | 1     | firewir... | [0213C3A21C](<All In One/Gateway/PROFILE5/PROFILE5.5/89C7C3620F05/UBUNTU-18.04/4.15.0-122-GENERIC/I686/0213C3A21C>) |
| 1106:3401 | 17aa:3603 | VIA Technologies | FireWire (IEEE 1394)                 | 1     | firewir... | [8399296D51](<All In One/Lenovo/IdeaCentre/IdeaCentre B305 10052/A8184A7A8382/UBUNTU-20.04/5.8.0-55-GENERIC/X86_64/8399296D51>) |
| 1106:3401 | 17aa:3608 | VIA Technologies | FireWire (IEEE 1394)                 | 1     | firewir... | [69574214D7](<All In One/Lenovo/IdeaCentre/IdeaCentre A700 10050/51968677EC4C/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/69574214D7>) |
| 1180:0552 | 1033:886f | Ricoh            | R5C552 IEEE 1394 Controller          | 1     | firewir... | [86771347FB](<All In One/NEC Computers/PC-GV58/PC-GV58ZYCAA/96538F2FC249/UBUNTU-19.04/5.0.0-13-GENERIC/X86_64/86771347FB>) |
| 1217:10f7 | 17aa:3068 | O2 Micro         | 1394 OHCI Compliant Host Controller  | 1     | firewir... | [27E7D42D53](<All In One/Lenovo/xxxx/xxxx/18DB28A21724/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/27E7D42D53>) |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1577 | 1022:1577 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 15    |            | [0DD6576588](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-22AST F0D6002EFR/7FE429038D53/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/0DD6576588>) |
| 1022:1419 | 1022:1419 | AMD              | Family 15h (Models 10h-1fh) I/O M... | 1     |            | [DD512D1882](<All In One/Gigabyte Technology/GB-A5/GB-A5DNK-RH/2D59EF3CA1FB/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/DD512D1882>) |
| 1022:1423 | 17aa:368f | AMD              | Family 15h (Models 30h-3fh) I/O M... | 1     |            | [58DDD6F565](<All In One/Lenovo/B50-35/B50-35 F0AV0025GE/7D201658F55F/ROSA-2014.1/4.9.76-NRJ-DESKTOP-1ROSA-X86_64/X86_64/58DDD6F565>) |
| 1022:1451 | 1022:1451 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 1     |            | [42B182D5F0](<All In One/Acidanthera/iMacPro1/iMacPro1,1/9A30E1010885/ARCH/5.9.10-ARCH1-1/X86_64/42B182D5F0>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1002:9583 | 106b:0083 | AMD              | RV630/M76 [Mobility Radeon HD 260... | 68    | radeon     | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 8086:0102 | 8086:2010 | Intel            | 2nd Generation Core Processor Fam... | 55    | i915       | [FE2249C404](<All In One/Apple/iMac12/iMac12,1/825F0CF6DCAC/ZORIN-16/5.13.0-30-GENERIC/X86_64/FE2249C404>) |
| 8086:0102 | 106b:0000 | Intel            | 2nd Generation Core Processor Fam... | 45    | i915       | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 1002:6741 | 106b:6741 | AMD              | Whistler [Radeon HD 6630M/6650M/6... | 42    | radeon     | [FE2249C404](<All In One/Apple/iMac12/iMac12,1/825F0CF6DCAC/ZORIN-16/5.13.0-30-GENERIC/X86_64/FE2249C404>) |
| 1002:94c8 | 106b:0084 | AMD              | RV610/M74 [Mobility Radeon HD 240... | 37    | radeon     | [3345FF19CD](<All In One/Apple/iMac8/iMac8,1/479BD0727CA4/DEBIAN-11/5.10.0-11-AMD64/X86_64/3345FF19CD>) |
| 1002:9488 | 106b:00b6 | AMD              | RV730/M96-XT [Mobility Radeon HD ... | 34    | radeon     | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 1002:6740 | 106b:6740 | AMD              | Whistler [Radeon HD 6730M/6770M/7... | 33    | radeon     | [EBE80F974B](<All In One/Apple/iMac12/iMac12,1/30B8B7C54347/UBUNTU-20.04/5.13.0-32-GENERIC/X86_64/EBE80F974B>) |
| 10de:0867 | 106b:00ad | Nvidia           | C79 [GeForce 9400]                   | 33    | nouveau    | [BF684BCED7](<All In One/Apple/iMac9/iMac9,1/B20C0E9191A5/MANJARO/5.15.19-1-MANJARO/X86_64/BF684BCED7>) |
| 1002:6720 | 106b:0b00 | AMD              | Blackcomb [Radeon HD 6970M/6990M]    | 26    | radeon     | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 10de:0869 | 106b:00b4 | Nvidia           | MCP7A [GeForce 9400]                 | 25    | nouveau    | [4F76CF1BC8](<All In One/Apple/iMac10/iMac10,1/F2F44B6FDD9E/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/4F76CF1BC8>) |
| 1002:71c5 | 106b:0080 | AMD              | RV530/M56-P [Mobility Radeon X1600]  | 19    | radeon     | [261E6C0463](<All In One/Apple/iMac5/iMac5,1/F72BF7BFE069/LMDE-5/5.10.0-11-686/I686/261E6C0463>) |
| 10de:0fd8 | 106b:0109 | Nvidia           | GK107M [GeForce GT 640M Mac Edition] | 17    | nvidia     | [435548337A](<All In One/Apple/iMac13/iMac13,1/BB29D11F01EF/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/435548337A>) |
| 1002:68a1 | 106b:00cc | AMD              | Broadway PRO [Mobility Radeon HD ... | 16    | radeon     | [48688703FE](<All In One/Apple/iMac11/iMac11,3/720CB377D1CB/UBUNTU-20.04/5.8.0-43-GENERIC/X86_64/48688703FE>) |
| 1002:67ef | 106b:016b | AMD              | Baffin [Radeon RX 460/560D / Pro ... | 15    | amdgpu     | [841AB4FFE2](<All In One/Apple/iMac18/iMac18,2/6AAE34125DB5/FEDORA-36/5.17.0-0.RC5.102.FC36.X86_64/X86_64/841AB4FFE2>) |
| 1002:944a | 106b:00b5 | AMD              | RV770/M98L [Mobility Radeon HD 4850] | 14    | radeon     | [F9560B6FE3](<All In One/Apple/iMac11/iMac11,1/9FF8106A1F94/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/F9560B6FE3>) |
| 8086:5917 | 103c:84de | Intel            | UHD Graphics 620                     | 14    | i915       | [43184FD6BF](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/3E27DCFED7C5/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/43184FD6BF>) |
| 8086:0d22 | 106b:0122 | Intel            | Crystal Well Integrated Iris Pro ... | 13    | i915       | [9AEE4C877D](<All In One/Apple/iMac14/iMac14,1/50E077CF962C/MANJARO-21.2.0/5.13.19-2-MANJARO/X86_64/9AEE4C877D>) |
| 8086:0102 | 1028:0511 | Intel            | 2nd Generation Core Processor Fam... | 12    | i915       | [6008FDA2AD](<All In One/Dell/Inspiron/Inspiron One 2320/61122D664D9D/UBUNTU-21.10/5.13.0-23-GENERIC/X86_64/6008FDA2AD>) |
| 1002:67ef | 106b:0197 | AMD              | Baffin [Radeon RX 460/560D / Pro ... | 11    | amdgpu     | [5E0CEEF0D1](<All In One/Apple/iMac19/iMac19,2/B4B5423C68DB/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/5E0CEEF0D1>) |
| 1002:98e4 | 103c:8381 | AMD              | Stoney [Radeon R2/R3/R4/R5 Graphics] | 11    | amdgpu     | [0DC8027649](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/B4EEA135048F/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/0DC8027649>) |
| 8086:0102 | 103c:2ac5 | Intel            | 2nd Generation Core Processor Fam... | 11    | i915       | [DF20701C5E](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/2B14E403FA28/DEBIAN-10/5.10.0-0.BPO.3-AMD64/X86_64/DF20701C5E>) |
| 8086:0412 | 1028:05a7 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 11    | i915       | [ED0DFEF2DF](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/FA6C8EA82464/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/ED0DFEF2DF>) |
| 1002:67ef | 106b:016a | AMD              | Baffin [Radeon RX 460/560D / Pro ... | 10    | amdgpu     | [84E2EE1E04](<All In One/Apple/iMac18/iMac18,2/71D14BCF57F1/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/84E2EE1E04>) |
| 1002:98e4 | 103c:8430 | AMD              | Stoney [Radeon R2/R3/R4/R5 Graphics] | 10    | amdgpu     | [56C6D48F6E](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/A2E8399A62AF/ENDEAVOUROS-ROLLING/5.14.2-ARCH1-2/X86_64/56C6D48F6E>) |
| 1002:6751 | 1028:0548 | AMD              | Turks [Radeon HD 7650A/7670A]        | 9     | radeon     | [6D6980BC69](<All In One/Dell/Inspiron/Inspiron One 2330/CC15798AE672/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/6D6980BC69>) |
| 1002:68c0 | 106b:00d2 | AMD              | Madison [Mobility Radeon HD 5730 ... | 9     | radeon     | [99D7E82DF9](<All In One/Apple/iMac11/iMac11,2/9D11563CF50D/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/99D7E82DF9>) |
| 10de:0fea | 106b:011f | Nvidia           | GK107M [GeForce GT 755M Mac Edition] | 9     | nvidia     | [275D33A826](<All In One/Apple/iMac14/iMac14,2/431D98DD9113/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/275D33A826>) |
| 8086:0416 | 1028:05db | Intel            | 4th Gen Core Processor Integrated... | 9     | i915       | [6B8B0EC7F9](<All In One/Dell/Inspiron/Inspiron 2350/62A6886810DD/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/6B8B0EC7F9>) |
| 8086:5917 | 1025:1287 | Intel            | UHD Graphics 620                     | 9     | i915       | [70014EA10E](<All In One/Acer/Aspire/Aspire C22-865/CAE70310F314/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/70014EA10E>) |
| 1002:6640 | 106b:014b | AMD              | Saturn XT [FirePro M6100]            | 8     | radeon     | [11BF29BDD1](<All In One/Apple/iMac17/iMac17,1/712E1D65BC52/ZORIN-16/5.11.0-46-GENERIC/X86_64/11BF29BDD1>) |
| 1002:6819 | 106b:014e | AMD              | Pitcairn PRO [Radeon HD 7850 / R7... | 8     | radeon     | [436904EAE3](<All In One/Apple/iMac17/iMac17,1/7E034427C03F/DEBIAN-11/5.10.0-12-AMD64/X86_64/436904EAE3>) |
| 1002:9851 | 103c:8245 | AMD              | Mullins [Radeon R4/R5 Graphics]      | 8     | radeon     | [317A5752C4](<All In One/Hewlett-Packard/24/24-g013ns/323FC2F05365/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/317A5752C4>) |
| 10de:0655 | 106b:0633 | Nvidia           | G96 [GeForce GT 120 Mac Edition]     | 8     | nouveau    | [3BA2AA8C2D](<All In One/Apple/iMac9/iMac9,1/4F9940E6FFA2/KDE-NEON-20.04/5.11.0-37-GENERIC/X86_64/3BA2AA8C2D>) |
| 10de:0dea | 17aa:365e | Nvidia           | GF108M [GeForce 610M]                | 8     | nouveau    | [968B139684](<All In One/Lenovo/C440/C440 10104/DBCDF802DB54/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/968B139684>) |
| 8086:0042 | 17aa:306a | Intel            | Core Processor Integrated Graphic... | 8     | i915       | [0EF323D23D](<All In One/Lenovo/ThinkCentre/ThinkCentre M90z 5205RQ1/DDABC203DAB8/UBUNTU-20.04/5.8.0-53-GENERIC/X86_64/0EF323D23D>) |
| 8086:22b1 | 103c:81bb | Intel            | Atom/Celeron/Pentium Processor x5... | 8     | i915       | [516F843813](<All In One/Hewlett-Packard/22/22-b009na/2C2C0369DE9C/KALI-2021.4/5.15.0-KALI2-AMD64/X86_64/516F843813>) |
| 1002:6660 | 1028:05db | AMD              | Sun XT [Radeon HD 8670A/8670M/869... | 7     | radeon     | [6B8B0EC7F9](<All In One/Dell/Inspiron/Inspiron 2350/62A6886810DD/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/6B8B0EC7F9>) |
| 1002:9850 | 103c:8245 | AMD              | Mullins [Radeon R3 Graphics]         | 7     | radeon     | [BFDC2533BB](<All In One/Hewlett-Packard/20/20-c211la/6F4CC01CA4A6/LINUXMINT-20.3/5.4.0-96-GENERIC/X86_64/BFDC2533BB>) |
| 8086:1622 | 106b:014f | Intel            | Iris Pro Graphics 6200               | 7     | i915       | [BC313CE031](<All In One/Apple/iMac16/iMac16,2/224B9F366AD7/ENDEAVOUROS-ROLLING/5.15.7-ARCH1-1/X86_64/BC313CE031>) |
| 8086:1912 | 1028:06c5 | Intel            | HD Graphics 530                      | 7     | i915       | [0DCB1B8C3C](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/34CACCC6D3D6/UBUNTU-20.04/5.13.0-32-GENERIC/X86_64/0DCB1B8C3C>) |
| 8086:3185 | 1854:0308 | Intel            | GeminiLake [UHD Graphics 600]        | 7     | i915       | [F57C7BBE97](<All In One/LG Electronics/22V280/22V280-L.BY31P1/BF6C05A5FCC3/ENDEAVOUROS-ROLLING/5.13.12-ARCH1-1/X86_64/F57C7BBE97>) |
| 8086:5916 | 1028:0754 | Intel            | HD Graphics 620                      | 7     | i915       | [00C297540D](<All In One/Dell/Inspiron/Inspiron 3464 AIO/31AD17DDDC01/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/00C297540D>) |
| 1002:15d8 | 103c:86f3 | AMD              | Picasso/Raven 2 [Radeon Vega Seri... | 6     | amdgpu     | [7DE0381DB8](<All In One/Hewlett-Packard/205/205 G4 22 All-in-One PC/F158F87A803B/SLACKWARE-15.0/5.15.27/X86_64/7DE0381DB8>) |
| 1002:67df | 106b:0161 | AMD              | Ellesmere [Radeon RX 470/480/570/... | 6     | amdgpu     | [F1B9BEBE99](<All In One/Apple/iMac18/iMac18,3/497041B41EEB/KALI-2021.3/5.10.0-KALI9-AMD64/X86_64/F1B9BEBE99>) |
| 1002:67df | 106b:019e | AMD              | Ellesmere [Radeon RX 470/480/570/... | 6     | amdgpu     | [90E49546C2](<All In One/Apple/iMac19/iMac19,1/330392FCD8B9/UBUNTU-BUDGIE-20.04/5.11.0-38-GENERIC/X86_64/90E49546C2>) |
| 1002:67ef | 106b:019f | AMD              | Baffin [Radeon RX 460/560D / Pro ... | 6     | amdgpu     | [79D2578788](<All In One/Apple/iMac19/iMac19,2/703D201F7BA5/UBUNTU-20.04/5.16.7-051607-GENERIC/X86_64/79D2578788>) |
| 1002:6840 | 144d:b091 | AMD              | Thames [Radeon HD 7500M/7600M Ser... | 6     | radeon     | [DD513D338C](<All In One/Samsung Electronics/DP700/DP700A3D-DM700A3D-DB701A3D-DP700A7D/F34D6AA53F0D/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/DD513D338C>) |
| 1002:9553 | 1025:0266 | AMD              | RV710/M92 [Mobility Radeon HD 453... | 6     | radeon     | [141F5642FC](<All In One/Acer/Aspire/Aspire Z5610/93F4A5EF8D69/LINUXMINT-20.2/5.4.0-96-GENERIC/X86_64/141F5642FC>) |
| 10de:0df5 | 1028:0511 | Nvidia           | GF108M [GeForce GT 525M]             | 6     | nvidia     | [6008FDA2AD](<All In One/Dell/Inspiron/Inspiron One 2320/61122D664D9D/UBUNTU-21.10/5.13.0-23-GENERIC/X86_64/6008FDA2AD>) |
| 10de:119d | 106b:0120 | Nvidia           | GK104M [GeForce GTX 775M Mac Edit... | 6     | nvidia     | [7757BE603C](<All In One/Apple/iMac14/iMac14,2/3F4033EA2574/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/7757BE603C>) |

### Iommu (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15d1 | 1022:15d1 | AMD              | Raven/Raven2 IOMMU                   | 21    |            | [7DE0381DB8](<All In One/Hewlett-Packard/205/205 G4 22 All-in-One PC/F158F87A803B/SLACKWARE-15.0/5.15.27/X86_64/7DE0381DB8>) |
| 1022:1451 | 1028:07e4 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 3     |            | [81AF87F00C](<All In One/Dell/Inspiron/Inspiron 27 7775/D1240D4484D8/ELEMENTARY-5.1.7/5.4.0-89-GENERIC/X86_64/81AF87F00C>) |
| 1022:1577 | 1028:07e3 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 3     |            | [87A4F1E989](<All In One/Dell/Inspiron/Inspiron 24 5475/44B04AE381C1/UBUNTU-18.04/5.4.0-89-GENERIC/X86_64/87A4F1E989>) |
| 1022:1631 | 103c:86ee | AMD              | Renoir/Cezanne IOMMU                 | 3     |            | [B200DC3D0F](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-k0xxx/3A4D1D72C41E/UBUNTU-20.04/5.11.0-46-GENERIC/X86_64/B200DC3D0F>) |
| 1022:1631 | 17aa:371c | AMD              | Renoir/Cezanne IOMMU                 | 3     |            | [6C4714D241](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 24ARE05 F0EW00FLSC/74D0340E2EB1/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/6C4714D241>) |
| 1022:1481 | 1022:1481 | AMD              | Starship/Matisse IOMMU               | 2     |            | [991A74F3E5](<All In One/Acidanthera/iMacPro1/iMacPro1,1/068603353593/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/991A74F3E5>) |
| 1022:1577 | 17aa:36ec | AMD              | Family 15h (Models 60h-6fh) I/O M... | 2     |            | [2CFA2D338E](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 330-20AST F0D8001LUS/36DA6D8B2B0D/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/2CFA2D338E>) |
| 1022:1631 | 1022:1631 | AMD              | Renoir/Cezanne IOMMU                 | 2     |            | [4DB843D0C6](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-dp0xxx/F7426AF86A80/OPENMANDRIVA-4.50/5.16.3-DESKTOP-2OMV4050/X86_64/4DB843D0C6>) |
| 1022:1481 | 1043:87c0 | AMD              | Starship/Matisse IOMMU               | 1     |            | [577AD83B8F](<All In One/Acidanthera/iMacPro1/iMacPro1,1/6286842FEC0E/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/577AD83B8F>) |
| 1022:1577 | 1028:0854 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 1     |            | [BEF244106F](<All In One/Dell/Inspiron/Inspiron 3475 AIO/EA044F848CBC/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/BEF244106F>) |
| 1022:1577 | 1028:0855 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 1     |            | [DACA9432F8](<All In One/Dell/Inspiron/Inspiron 3275 AIO/6D40C1FA2274/LINUXMINT-19.2/4.15.0-65-GENERIC/X86_64/DACA9432F8>) |
| 1022:1577 | 17aa:36c6 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 1     |            | [5DA9F63B49](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 310-20ASR F0CK001ERK/FC84FC5E58C9/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/5DA9F63B49>) |
| 1022:1631 | 1043:1832 | AMD              | Renoir/Cezanne IOMMU                 | 1     |            | [C1F6B30A92](<All In One/ASUSTek Computer/ASUS/ASUS ZEN AIO M5401WUA_M5401WUA/446C2FD0324E/ARCO-ROLLING/5.15.2-ARCH1-1/X86_64/C1F6B30A92>) |
| 1022:1631 | 1043:1a72 | AMD              | Renoir/Cezanne IOMMU                 | 1     |            | [F788930C1E](<All In One/ASUSTek Computer/ASUS/ASUS AIO M3400WUA_M3400WUA/C57F5A924964/ROSA-12/5.10.71-GENERIC-1ROSA2021.1-X86_64/X86_64/F788930C1E>) |
| 1022:1631 | 17aa:3734 | AMD              | Renoir/Cezanne IOMMU                 | 1     |            | [53462F848A](<All In One/Lenovo/Yoga/Yoga 27-ARH F0FN0002CP/61F8ED84D9C7/XUBUNTU-20.04/5.11.0-40-GENERIC/X86_64/53462F848A>) |
| 1022:1631 | 17aa:3744 | AMD              | Renoir/Cezanne IOMMU                 | 1     |            | [B3EDFBFEE7](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 24ALC6 F0G1002YUK/C0099F4B4E0C/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/B3EDFBFEE7>) |
| 1022:1631 | 17aa:3746 | AMD              | Renoir/Cezanne IOMMU                 | 1     |            | [44D15EF318](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 27ALC6 F0FY0011RK/F7C486141AE7/FEDORA-35/5.14.18-300.FC35.X86_64/X86_64/44D15EF318>) |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:816c | 1025:1290 | Realtek Semic... | RTL8111xP IPMI interface             | 2     |            | [A27363041A](<All In One/Acer/Veriton/Veriton Z4860G/8955EDC1BE49/ENDLESS-3.9.1/5.8.0-14-GENERIC/X86_64/A27363041A>) |
| 10ec:816c | 1025:1291 | Realtek Semic... | RTL8111xP IPMI interface             | 2     |            | [13496AAE5D](<All In One/Acer/Veriton/Veriton Z4660G/A736A6205FE1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/13496AAE5D>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10de:0a88 |           | Nvidia           | MCP79 Memory Controller              | 88    |            | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 10de:0a89 |           | Nvidia           | MCP79 Memory Controller              | 88    |            | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 10de:0a98 | 10de:cb79 | Nvidia           | MCP79 Memory Controller              | 88    |            | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 10de:0aa4 |           | Nvidia           | MCP79 Memory Controller              | 88    |            | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 57    |            | [436904EAE3](<All In One/Apple/iMac17/iMac17,1/7E034427C03F/DEBIAN-11/5.10.0-12-AMD64/X86_64/436904EAE3>) |
| 8086:a36f |           | Intel            | Cannon Lake PCH Shared SRAM          | 31    |            | [5E0CEEF0D1](<All In One/Apple/iMac19/iMac19,2/B4B5423C68DB/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/5E0CEEF0D1>) |
| 8086:a36f | 8086:7270 | Intel            | Cannon Lake PCH Shared SRAM          | 23    |            | [46A47AB08E](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/D3EA8545A30E/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/46A47AB08E>) |
| 8086:9d21 | 103c:84de | Intel            | Sunrise Point-LP PMC                 | 14    |            | [43184FD6BF](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/3E27DCFED7C5/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/43184FD6BF>) |
| 8086:9d21 | 8086:9d21 | Intel            | Sunrise Point-LP PMC                 | 10    | intel_p... | [8826665773](<All In One/ASUSTek Computer/ZN240/ZN240IC/B519220D6F37/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/8826665773>) |
| 8086:9d21 | 1025:1287 | Intel            | Sunrise Point-LP PMC                 | 9     | intel_p... | [70014EA10E](<All In One/Acer/Aspire/Aspire C22-865/CAE70310F314/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/70014EA10E>) |
| 8086:a0ef |           | Intel            | Tiger Lake-LP Shared SRAM            | 8     |            | [503D10D676](<All In One/Dell/Inspiron/Inspiron 5400 AIO/1B0441A55B57/ZORIN-16/5.11.0-38-GENERIC/X86_64/503D10D676>) |
| 10de:0568 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] Memory Cont... | 7     |            | [04B8123AA5](<All In One/Acer/Aspire/Aspire Z3101/EDA041C04858/UBUNTU-18.04/4.15.0-96-GENERIC/X86_64/04B8123AA5>) |
| 10de:0751 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] Memory Cont... | 7     |            | [04B8123AA5](<All In One/Acer/Aspire/Aspire Z3101/EDA041C04858/UBUNTU-18.04/4.15.0-96-GENERIC/X86_64/04B8123AA5>) |
| 10de:0754 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] Memory Cont... | 7     |            | [04B8123AA5](<All In One/Acer/Aspire/Aspire Z3101/EDA041C04858/UBUNTU-18.04/4.15.0-96-GENERIC/X86_64/04B8123AA5>) |
| 8086:34ef | 8086:7270 | Intel            | Ice Lake-LP DRAM Controller          | 7     |            | [F15CA34264](<All In One/Acer/Aspire/Aspire C27-962/A23104408196/LINUXMINT-20.3/5.4.0-92-GENERIC/X86_64/F15CA34264>) |
| 8086:9d21 | 1028:0754 | Intel            | Sunrise Point-LP PMC                 | 7     |            | [00C297540D](<All In One/Dell/Inspiron/Inspiron 3464 AIO/31AD17DDDC01/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/00C297540D>) |
| 8086:a121 | 1028:06c5 | Intel            | 100 Series/C230 Series Chipset Fa... | 7     |            | [0DCB1B8C3C](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/34CACCC6D3D6/UBUNTU-20.04/5.13.0-32-GENERIC/X86_64/0DCB1B8C3C>) |
| 8086:06ef | 8086:7270 | Intel            | Comet Lake PCH Shared SRAM           | 6     |            | [EA489D447C](<All In One/Dell/OptiPlex/OptiPlex 7480 AIO/AA453186B2B9/LINUXMINT-20.1/5.4.0-104-GENERIC/X86_64/EA489D447C>) |
| 8086:9def | 8086:7270 | Intel            | Cannon Point-LP Shared SRAM          | 6     |            | [60C6C7EA7C](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/3602C27EA430/ENDLESS-3.9.6/5.8.0-14-GENERIC/X86_64/60C6C7EA7C>) |
| 8086:a121 | 103c:81b7 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     |            | [35AB480926](<All In One/Hewlett-Packard/27/27-a154ng/BDD291411CF6/ARCH/5.16.10-ARCH1-1/X86_64/35AB480926>) |
| 8086:a121 | 103c:82dc | Intel            | 100 Series/C230 Series Chipset Fa... | 6     |            | [E3A85B9AAF](<All In One/Hewlett-Packard/27/27-a271ny/689111B5E631/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E3A85B9AAF>) |
| 8086:9d21 | 8086:7270 | Intel            | Sunrise Point-LP PMC                 | 5     |            | [E0D2C2356F](<All In One/Apple/iMac18/iMac18,1/447C402E8489/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/E0D2C2356F>) |
| 8086:a121 | 8086:a121 | Intel            | 100 Series/C230 Series Chipset Fa... | 5     |            | [31E48D8DA1](<All In One/ASUSTek Computer/Z240/Z240IC-H170/FB2F1250F58B/POP!_OS-20.10/5.8.0-7642-GENERIC/X86_64/31E48D8DA1>) |
| 10de:0a88 | 1462:4570 | Nvidia           | MCP79 Memory Controller              | 4     |            | [BF5395A5D3](<All In One/MSI/MS-AA/MS-AA1511/EC062EE8E1B7/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/BF5395A5D3>) |
| 10de:0a89 | 1462:4570 | Nvidia           | MCP79 Memory Controller              | 4     |            | [BF5395A5D3](<All In One/MSI/MS-AA/MS-AA1511/EC062EE8E1B7/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/BF5395A5D3>) |
| 10de:0aa4 | 1462:4570 | Nvidia           | MCP79 Memory Controller              | 4     |            | [BF5395A5D3](<All In One/MSI/MS-AA/MS-AA1511/EC062EE8E1B7/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/BF5395A5D3>) |
| 8086:9d21 | 103c:82dd | Intel            | Sunrise Point-LP PMC                 | 4     |            | [0A0BE4F02F](<All In One/Hewlett-Packard/All-in-One/All-in-One/B6AE7C054ACC/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/0A0BE4F02F>) |
| 8086:a0ef | 1043:1482 | Intel            | Tiger Lake-LP Shared SRAM            | 4     |            | [FFB4ED2207](<All In One/ASUSTek Computer/ASUS/ASUS Vivo AIO V241EA_V241EA/69C580FE0877/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/FFB4ED2207>) |
| 8086:a121 | 1025:1063 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     |            | [654A051A24](<All In One/Acer/Aspire/Aspire Z3-715/65616ABBF7DA/UBUNTU-20.10/5.8.0-63-GENERIC/X86_64/654A051A24>) |
| 8086:a121 | 103c:2b3e | Intel            | 100 Series/C230 Series Chipset Fa... | 4     |            | [D11126F73D](<All In One/Hewlett-Packard/24/24-n014/8FD013C5503B/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/D11126F73D>) |
| 8086:34ef | 1025:1434 | Intel            | Ice Lake-LP DRAM Controller          | 3     |            | [9B4659E4DD](<All In One/Acer/Aspire/Aspire C24-963/CC4A926A8703/ROSA-12/5.10.71-GENERIC-1ROSA2021.1-X86_64/X86_64/9B4659E4DD>) |
| 8086:9d21 | 1028:0852 | Intel            | Sunrise Point-LP PMC                 | 3     |            | [5A27DEAF8A](<All In One/Dell/Inspiron/Inspiron 3477 AIO/707700FC1C87/ROSA-2014.1/4.9.155-NRJ-DESKTOP-1ROSA-I586/I686/5A27DEAF8A>) |
| 8086:9d21 | 1043:12a1 | Intel            | Sunrise Point-LP PMC                 | 3     |            | [E0EF808E3F](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222UA/9F8A84B648C2/ENDLESS-3.4.1/4.15.0-22-GENERIC/X86_64/E0EF808E3F>) |
| 8086:9d21 | 17aa:3630 | Intel            | Sunrise Point-LP PMC                 | 3     |            | [D7C6B6357C](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 300-23ISU F0BY008PSP/B70B487274F2/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/D7C6B6357C>) |
| 8086:a121 | 17aa:30ba | Intel            | 100 Series/C230 Series Chipset Fa... | 3     |            | [F3E9E0B2F5](<All In One/Lenovo/ThinkCentre/ThinkCentre M900z 10F3000DGE/DDF891FE5172/ROSA-2016.1/4.15.0-DESKTOP-68.5ROSA-X86_64/X86_64/F3E9E0B2F5>) |
| 8086:a2a1 | 1028:079c | Intel            | 200 Series/Z370 Chipset Family Po... | 3     |            | [0B0F9A42CD](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/F87DB1F1F5AC/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/0B0F9A42CD>) |
| 8086:a2a1 | 103c:838b | Intel            | 200 Series/Z370 Chipset Family Po... | 3     |            | [A8811301BC](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-r0xx/67514D08A17D/UBUNTU-20.10/5.8.0-45-GENERIC/X86_64/A8811301BC>) |
| 8086:a2a1 | 1043:8694 | Intel            | 200 Series/Z370 Chipset Family Po... | 3     |            | [181BD83BDD](<All In One/Acidanthera/iMac19/iMac19,1/55906309CABF/ARTIX-ROLLING/5.12.8-ARTIX1-1/X86_64/181BD83BDD>) |
| 8086:a2a1 | 8086:7270 | Intel            | 200 Series/Z370 Chipset Family Po... | 3     |            | [4ED51200E5](<All In One/iRU/A/A2313/9007113D5706/ROSA-12/5.10.71-GENERIC-1ROSA2021.1-X86_64/X86_64/4ED51200E5>) |
| 8086:a36f | 103c:85a2 | Intel            | Cannon Lake PCH Shared SRAM          | 3     |            | [F0691E6EDA](<All In One/Hewlett-Packard/ProOne/ProOne 600 G5 21.5-in All-in-One/FC490F22A5D6/MANJARO/5.10.23-1-MANJARO/X86_64/F0691E6EDA>) |
| 8086:a36f | 17aa:36f4 | Intel            | Cannon Lake PCH Shared SRAM          | 3     |            | [68B6455D7A](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-27ICB F0DE00A7MB/9B6878A5EA27/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/68B6455D7A>) |
| 10de:0a88 | 1043:8379 | Nvidia           | MCP79 Memory Controller              | 2     |            | [72365E4985](<All In One/ASUSTek Computer/ET/ET2002/9AD492BE589B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/72365E4985>) |
| 10de:0a89 | 1043:8379 | Nvidia           | MCP79 Memory Controller              | 2     |            | [72365E4985](<All In One/ASUSTek Computer/ET/ET2002/9AD492BE589B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/72365E4985>) |
| 10de:0aa4 | 1043:8379 | Nvidia           | MCP79 Memory Controller              | 2     |            | [72365E4985](<All In One/ASUSTek Computer/ET/ET2002/9AD492BE589B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/72365E4985>) |
| 8086:02ef | 1028:0953 | Intel            | Comet Lake PCH-LP Shared SRAM        | 2     |            | [AEFAC2FB50](<All In One/Dell/Inspiron/Inspiron 5490 AIO/B7D11D1CE42A/ZORIN-16/5.11.0-36-GENERIC/X86_64/AEFAC2FB50>) |
| 8086:02ef | 1028:0954 | Intel            | Comet Lake PCH-LP Shared SRAM        | 2     |            | [51D212B73F](<All In One/Dell/Inspiron/Inspiron 7790 AIO/5226FB806DAF/UBUNTU-2020/5.8.0-44-GENERIC/X86_64/51D212B73F>) |
| 8086:02ef | 17aa:370c | Intel            | Comet Lake PCH-LP Shared SRAM        | 2     |            | [B9A115E6A4](<All In One/Lenovo/IdeaCentre/IdeaCentre A340-24IWL F0E800Q1IN/7A95353B97C7/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/B9A115E6A4>) |
| 8086:02ef | 8086:7270 | Intel            | Comet Lake PCH-LP Shared SRAM        | 2     |            | [9E72716F96](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222FA_A6432FA/9F429A9552E8/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/9E72716F96>) |
| 8086:9d21 | 17aa:36dc | Intel            | Sunrise Point-LP PMC                 | 2     |            | [CD5915910D](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-24IKU F0D2000DRK/056309C58314/KDE-NEON-20.04/5.10.26-XANMOD1/X86_64/CD5915910D>) |
| 8086:9def | 17aa:36fe | Intel            | Cannon Point-LP Shared SRAM          | 2     |            | [CA86244C1D](<All In One/Lenovo/IdeaCentre/IdeaCentre A340-22IWL F0EB006RRI/F8358448E319/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/CA86244C1D>) |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1131:7231 | 1461:2a0f | Philips Semic... | SAA7231                              | 8     |            | [93684F3ECF](<All In One/Acer/Aspire/Aspire Z3751/B1AF8B7D0810/ROSA-2016.1/5.4.107-GENERIC-0.1ROSA-X86_64/X86_64/93684F3ECF>) |
| 1002:ac12 | 12ab:0003 | AMD              | Theater HD T507 (DVB-T) TV tuner/... | 5     |            | [8F25ED4108](<All In One/Lenovo/IdeaCentre/IdeaCentre A310 10056/1F51DDDCDF1C/LINUXMINT-19.3/5.4.0-77-GENERIC/X86_64/8F25ED4108>) |
| 1131:7231 | 1461:2b0f | Philips Semic... | SAA7231                              | 5     |            | [3936FD702B](<All In One/Dell/Inspiron/Inspiron One 2320/5F50F67A6BCF/XUBUNTU-20.04/5.8.0-63-LOWLATENCY/X86_64/3936FD702B>) |
| 1022:15e2 | 17aa:36f5 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 3     | snd_pci... | [EB38810FB8](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-24ARR F0DN006KGE/1D5E59C5CB5F/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/EB38810FB8>) |
| 1022:15e2 | 17aa:371c | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 3     | snd_pci... | [6C4714D241](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 24ARE05 F0EW00FLSC/74D0340E2EB1/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/6C4714D241>) |
| 1022:15e2 | 1022:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     | snd_pci... | [5DA493DE55](<All In One/Lenovo/IdeaCentre/IdeaCentre A540-24API F0EM0000UK/93E2EABF69EE/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/5DA493DE55>) |
| 10cf:2030 | 104d:9053 | Fujitsu Limited. | Fujitsu Multimedia controller        | 2     |            | [AFA509714D](<All In One/Sony/VGC-LN52/VGC-LN52JGB/54F15FF48E03/UBUNTU-20.04/5.8.0-54-GENERIC/X86_64/AFA509714D>) |
| 1131:7231 | 1461:2b07 | Philips Semic... | SAA7231                              | 2     |            | [911C78A85D](<All In One/Dell/Inspiron/Inspiron One 2320/D8B99273D539/UBUNTU-21.04/5.11.0-31-GENERIC/X86_64/911C78A85D>) |
| 1002:ac12 | 1002:b539 | AMD              | Theater HD T507 (DVB-T) TV tuner/... | 1     |            | [DD5E0979B0](<All In One/Lenovo/IdeaCentre/IdeaCentre B300 10051/CECF63D85737/ROSA-2014.1/3.14.44-NRJ-DESKTOP-2ROSA-X86_64/X86_64/DD5E0979B0>) |
| 1022:15e2 | 1043:1832 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     | snd_pci... | [C1F6B30A92](<All In One/ASUSTek Computer/ASUS/ASUS ZEN AIO M5401WUA_M5401WUA/446C2FD0324E/ARCO-ROLLING/5.15.2-ARCH1-1/X86_64/C1F6B30A92>) |
| 1022:15e2 | 1043:1a72 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     | snd_pci... | [F788930C1E](<All In One/ASUSTek Computer/ASUS/ASUS AIO M3400WUA_M3400WUA/C57F5A924964/ROSA-12/5.10.71-GENERIC-1ROSA2021.1-X86_64/X86_64/F788930C1E>) |
| 1022:15e2 | 17aa:371d | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     | snd_pci... | [98A498AE78](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 22ADA05 F0EX003AIX/6C5F8148C1EA/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/98A498AE78>) |
| 1022:15e2 | 17aa:3734 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     | snd_pci... | [53462F848A](<All In One/Lenovo/Yoga/Yoga 27-ARH F0FN0002CP/61F8ED84D9C7/XUBUNTU-20.04/5.11.0-40-GENERIC/X86_64/53462F848A>) |
| 1022:15e2 | 17aa:3744 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     | snd_pci... | [B3EDFBFEE7](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 24ALC6 F0G1002YUK/C0099F4B4E0C/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/B3EDFBFEE7>) |
| 1022:15e2 | 17aa:3746 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [44D15EF318](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 27ALC6 F0FY0011RK/F7C486141AE7/FEDORA-35/5.14.18-300.FC35.X86_64/X86_64/44D15EF318>) |
| 10cf:2030 | 104d:9062 | Fujitsu Limited. | Fujitsu Multimedia controller        | 1     |            | [2628EBE1BB](<All In One/Sony/VPCL118/VPCL118FJ/15BB34EF7F80/UBUNTU-18.04/4.15.0-39-GENERIC/X86_64/2628EBE1BB>) |
| 10cf:2036 | 104d:906e | Fujitsu Limited. | DT-XXX                               | 1     |            | [68937CF6BB](<All In One/Sony/VPCJ128/VPCJ128FJ/CD1A2B850F5B/UBUNTU-20.04/5.4.0-56-GENERIC/X86_64/68937CF6BB>) |
| 1131:7160 | 1461:2155 | Philips Semic... | SAA7160                              | 1     |            | [27E7D42D53](<All In One/Lenovo/xxxx/xxxx/18DB28A21724/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/27E7D42D53>) |
| 1745:3000 | 104d:9049 | ViXS Systems     | Colossus Encoder                     | 1     |            | [2628EBE1BB](<All In One/Sony/VPCL118/VPCL118FJ/15BB34EF7F80/UBUNTU-18.04/4.15.0-39-GENERIC/X86_64/2628EBE1BB>) |
| 1745:3000 | 1bcf:a023 | ViXS Systems     | Colossus Encoder                     | 1     |            | [1494683BB9](<All In One/NEC Computers/PC-VN770/PC-VN770DS3ER/18CEF0AA43DB/UBUNTU-20.04/5.8.0-48-GENERIC/X86_64/1494683BB9>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14e4:1686 | 14e4:1686 | Broadcom         | NetXtreme BCM57766 Gigabit Ethern... | 177   | tg3        | [436904EAE3](<All In One/Apple/iMac17/iMac17,1/7E034427C03F/DEBIAN-11/5.10.0-12-AMD64/X86_64/436904EAE3>) |
| 11ab:436a | 11ab:00ba | Marvell Techn... | 88E8058 PCI-E Gigabit Ethernet Co... | 108   | sky2       | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 14e4:16b4 | 14e4:16b4 | Broadcom         | NetXtreme BCM57765 Gigabit Ethern... | 103   | tg3        | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 10de:0ab0 | 10de:cb79 | Nvidia           | MCP79 Ethernet                       | 88    | forcedeth  | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 14e4:1684 | 14e4:1684 | Broadcom         | NetXtreme BCM5764M Gigabit Ethern... | 56    | tg3        | [99D7E82DF9](<All In One/Apple/iMac11/iMac11,2/9D11563CF50D/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/99D7E82DF9>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 31    | r8169      | [286F257AF2](<All In One/Intel/AB2/AB2L/922CC7F780A0/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/286F257AF2>) |
| 10ec:8168 | 1043:205f | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 23    | r8169      | [EF42B78DC5](<All In One/ASUSTek Computer/V221/V221ID/E5E39EC35D8F/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/EF42B78DC5>) |
| 10ec:8168 | 1025:8000 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 21    | r8169      | [33937E8F75](<All In One/Acer/Aspire/Aspire Z1620/19DE00291955/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/33937E8F75>) |
| 11ab:4362 | 11ab:5321 | Marvell Techn... | 88E8053 PCI-E Gigabit Ethernet Co... | 21    | sky2       | [261E6C0463](<All In One/Apple/iMac5/iMac5,1/F72BF7BFE069/LMDE-5/5.10.0-11-686/I686/261E6C0463>) |
| 10ec:8168 | 1b50:4606 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 16    | r8169      | [8952D0F7D8](<All In One/Acer/Aspire/Aspire C22-760/1F1998194D47/FEDORA-35/5.16.12-200.FC35.X86_64/X86_64/8952D0F7D8>) |
| 10ec:8168 | 103c:8245 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 15    | r8169      | [BFDC2533BB](<All In One/Hewlett-Packard/20/20-c211la/6F4CC01CA4A6/LINUXMINT-20.3/5.4.0-96-GENERIC/X86_64/BFDC2533BB>) |
| 10ec:8168 | 103c:84de | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 14    | r8169      | [43184FD6BF](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/3E27DCFED7C5/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/43184FD6BF>) |
| 10ec:8168 | 17aa:365e | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 14    | r8169      | [485E063883](<All In One/Lenovo/C340/C340 10102/B4F39330CA94/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/485E063883>) |
| 10ec:8168 | 1028:0511 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 11    | r8169      | [C5E733F00F](<All In One/Dell/Inspiron/Inspiron One 2320/48201EE60452/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/C5E733F00F>) |
| 10ec:8168 | 103c:2ac5 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 11    | r8169      | [DF20701C5E](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/2B14E403FA28/DEBIAN-10/5.10.0-0.BPO.3-AMD64/X86_64/DF20701C5E>) |
| 10ec:8168 | 103c:8381 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 11    | r8169      | [0DC8027649](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/B4EEA135048F/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/0DC8027649>) |
| 1969:1091 | 1028:0548 | Qualcomm Atheros | AR8161 Gigabit Ethernet              | 11    | alx        | [B94AB82BDC](<All In One/Dell/Inspiron/Inspiron One 2330/8A9D53F13600/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/B94AB82BDC>) |
| 8086:153a | 1028:05a7 | Intel            | Ethernet Connection I217-LM          | 11    | e1000e     | [ED0DFEF2DF](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/FA6C8EA82464/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/ED0DFEF2DF>) |
| 10ec:8168 | 1025:0266 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 10    | r8169      | [141F5642FC](<All In One/Acer/Aspire/Aspire Z5610/93F4A5EF8D69/LINUXMINT-20.2/5.4.0-96-GENERIC/X86_64/141F5642FC>) |
| 10ec:8168 | 103c:8430 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 10    | r8169      | [56C6D48F6E](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/A2E8399A62AF/ENDEAVOUROS-ROLLING/5.14.2-ARCH1-2/X86_64/56C6D48F6E>) |
| 14e4:1686 | 106b:0110 | Broadcom         | NetXtreme BCM57766 Gigabit Ethern... | 10    | tg3        | [5154B1932F](<All In One/Apple/iMac13/iMac13,2/767BA25290CE/GARUDA-SOARING/5.14.14-ZEN1-1-ZEN/X86_64/5154B1932F>) |
| 10ec:8168 | 1025:1287 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 9     | r8169      | [70014EA10E](<All In One/Acer/Aspire/Aspire C22-865/CAE70310F314/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/70014EA10E>) |
| 10ec:8168 | 1028:05db | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 9     | r8169      | [6B8B0EC7F9](<All In One/Dell/Inspiron/Inspiron 2350/62A6886810DD/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/6B8B0EC7F9>) |
| 10ec:8168 | 103c:84ee | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 9     | r8169      | [2311649D51](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-xa0xxx/3187A1587DA6/LINUXMINT-20.2/5.4.0-90-GENERIC/X86_64/2311649D51>) |
| 10ec:8168 | 1043:858f | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 9     | r8169      | [8826665773](<All In One/ASUSTek Computer/ZN240/ZN240IC/B519220D6F37/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/8826665773>) |
| 10ec:8168 | 144d:b091 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 9     | r8169      | [DD513D338C](<All In One/Samsung Electronics/DP700/DP700A3D-DM700A3D-DB701A3D-DP700A7D/F34D6AA53F0D/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/DD513D338C>) |
| 10ec:8168 | 103c:81bb | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 8     | r8169      | [516F843813](<All In One/Hewlett-Packard/22/22-b009na/2C2C0369DE9C/KALI-2021.4/5.15.0-KALI2-AMD64/X86_64/516F843813>) |
| 10de:0760 | 1025:8000 | Nvidia           | MCP77 Ethernet                       | 7     | forcedeth  | [04B8123AA5](<All In One/Acer/Aspire/Aspire Z3101/EDA041C04858/UBUNTU-18.04/4.15.0-96-GENERIC/X86_64/04B8123AA5>) |
| 10ec:8136 | 1028:0754 | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 7     | r8169      | [00C297540D](<All In One/Dell/Inspiron/Inspiron 3464 AIO/31AD17DDDC01/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/00C297540D>) |
| 10ec:8136 | 10ec:8136 | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 7     | r8169      | [F96E26BB9A](<All In One/Dell/Inspiron/Inspiron 20 Model 3043/16F41C0EA91A/ZORIN-16/5.13.0-30-GENERIC/X86_64/F96E26BB9A>) |
| 10ec:8168 | 1019:811e | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 7     | r8169      | [0D7E8C7568](<All In One/AIO/H61/H61H-G11/80341B910781/ROSA-12.2/5.10.71-GENERIC-1ROSA2021.1-X86_64/X86_64/0D7E8C7568>) |
| 10ec:8168 | 103c:2b3b | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 7     | r8169      | [B3DCCF594C](<All In One/Hewlett-Packard/23/23-r035la/8A9A83560619/ZORIN-16/5.13.0-27-GENERIC/X86_64/B3DCCF594C>) |
| 10ec:8168 | 1043:200f | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 7     | r8169      | [2F804D87B1](<All In One/ASUSTek Computer/Zen/Zen AIO 24 ZN242GD_ZN242GD/9589773F7783/UBUNTU-18.04/5.4.0-80-GENERIC/X86_64/2F804D87B1>) |
| 10ec:8168 | 104d:907e | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 7     | r8169      | [0451CAEB29](<All In One/Sony/VPCL212/VPCL212FX/01EE677E7F92/UBUNTU-21.10/5.13.0-22-GENERIC/X86_64/0451CAEB29>) |
| 10ec:8168 | 17aa:366c | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 7     | r8169      | [3903A96DE3](<All In One/Lenovo/C540/C540 10110/2B8EE2F234A3/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/3903A96DE3>) |
| 10ec:8168 | 17aa:36ab | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 7     | r8169      | [AA6E9BA312](<All In One/Lenovo/C40-05/C40-05 F0B5002NCF/770FDA610B82/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/AA6E9BA312>) |
| 10ec:8168 | 1854:0308 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 7     | r8169      | [F57C7BBE97](<All In One/LG Electronics/22V280/22V280-L.BY31P1/BF6C05A5FCC3/ENDEAVOUROS-ROLLING/5.13.12-ARCH1-1/X86_64/F57C7BBE97>) |
| 8086:153a | 103c:18e6 | Intel            | Ethernet Connection I217-LM          | 7     | e1000e     | [F8D1E58D06](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G1 AiO/44D1B0C864ED/LINUXMINT-18.3/4.15.0-142-GENERIC/X86_64/F8D1E58D06>) |
| 8086:15b7 | 1028:06c5 | Intel            | Ethernet Connection (2) I219-LM      | 7     | e1000e     | [0DCB1B8C3C](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/34CACCC6D3D6/UBUNTU-20.04/5.13.0-32-GENERIC/X86_64/0DCB1B8C3C>) |
| 10ec:8168 | 1028:0623 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 6     | r8169      | [FE22676441](<All In One/Dell/OptiPlex/OptiPlex 3030 AIO/F73EB67F5BAB/FEDORA-35/5.14.14-300.FC35.X86_64/X86_64/FE22676441>) |
| 10ec:8168 | 1028:06cc | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 6     | r8169      | [3AC5DA5F93](<All In One/Dell/Inspiron/Inspiron 20-3052/E44132686405/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/3AC5DA5F93>) |
| 10ec:8168 | 1028:07e4 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 6     | r8169      | [81AF87F00C](<All In One/Dell/Inspiron/Inspiron 27 7775/D1240D4484D8/ELEMENTARY-5.1.7/5.4.0-89-GENERIC/X86_64/81AF87F00C>) |
| 10ec:8168 | 103c:81b7 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 6     | r8169      | [35AB480926](<All In One/Hewlett-Packard/27/27-a154ng/BDD291411CF6/ARCH/5.16.10-ARCH1-1/X86_64/35AB480926>) |
| 10ec:8168 | 103c:82dc | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 6     | r8169      | [E3A85B9AAF](<All In One/Hewlett-Packard/27/27-a271ny/689111B5E631/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E3A85B9AAF>) |
| 10ec:8168 | 103c:86f3 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 6     | r8169      | [7DE0381DB8](<All In One/Hewlett-Packard/205/205 G4 22 All-in-One PC/F158F87A803B/SLACKWARE-15.0/5.15.27/X86_64/7DE0381DB8>) |
| 10ec:8168 | 1043:84cd | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 6     | r8169      | [B20D7593CE](<All In One/ASUSTek Computer/ET2013/ET2013I/837E538FD9B7/ZORIN-16/5.13.0-30-GENERIC/X86_64/B20D7593CE>) |
| 10ec:8168 | 104d:9097 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 6     | r8169      | [4D477A343A](<All In One/Sony/SVL2411/SVL24117FLB/B337A07B7653/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/4D477A343A>) |
| 10ec:8168 | 17aa:3695 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 6     | r8168      | [3E79CADCEA](<All In One/Lenovo/C260/C260 10160/A6FBDDCB0193/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/3E79CADCEA>) |
| 10ec:8168 | 1b50:4607 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 6     | r8169      | [BC20F9A9CA](<All In One/Acer/Aspire/Aspire C27-1655/163A30053117/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/BC20F9A9CA>) |
| 10ec:8168 | 1028:0479 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 5     | r8169      | [CDCA9F74F5](<All In One/Dell/Inspiron/Inspiron One 2305/178B94E5C2F7/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/CDCA9F74F5>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 168c:0030 | 106b:009a | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 102   | ath9k      | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 168c:002a | 106b:008f | Qualcomm Atheros | AR928X Wireless Network Adapter (... | 97    | ath9k      | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 10ec:c821 | 103c:831a | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 65    | rtl8821ce  | [7DE0381DB8](<All In One/Hewlett-Packard/205/205 G4 22 All-in-One PC/F158F87A803B/SLACKWARE-15.0/5.15.27/X86_64/7DE0381DB8>) |
| 14e4:4328 | 106b:008c | Broadcom         | BCM4321 802.11a/b/g/n                | 59    | wl         | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 14e4:4328 | 106b:0088 | Broadcom         | BCM4321 802.11a/b/g/n                | 49    | wl         | [C26F81E381](<All In One/Apple/iMac7/iMac7,1/AA142ADA7D9D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C26F81E381>) |
| 14e4:432b | 106b:008e | Broadcom         | BCM4322 802.11a/b/g/n Wireless LA... | 45    | wl         | [BF684BCED7](<All In One/Apple/iMac9/iMac9,1/B20C0E9191A5/MANJARO/5.15.19-1-MANJARO/X86_64/BF684BCED7>) |
| 14e4:43a0 | 106b:0111 | Broadcom         | BCM4360 802.11ac Wireless Network... | 45    | wl         | [7757BE603C](<All In One/Apple/iMac14/iMac14,2/3F4033EA2574/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/7757BE603C>) |
| 8086:24fb | 8086:2110 | Intel            | Dual Band Wireless-AC 3168NGW [St... | 38    | iwlwifi    | [8952D0F7D8](<All In One/Acer/Aspire/Aspire C22-760/1F1998194D47/FEDORA-35/5.16.12-200.FC35.X86_64/X86_64/8952D0F7D8>) |
| 14e4:4464 | 106b:07bf | Broadcom         | BCM4364 802.11ac Wireless Network... | 33    | brcmfmac   | [5E0CEEF0D1](<All In One/Apple/iMac19/iMac19,2/B4B5423C68DB/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/5E0CEEF0D1>) |
| 14e4:4331 | 106b:00f4 | Broadcom Limited | BCM4331 802.11a/b/g/n                | 32    | wl         | [435548337A](<All In One/Apple/iMac13/iMac13,1/BB29D11F01EF/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/435548337A>) |
| 10ec:b723 | 103c:81c1 | Realtek Semic... | RTL8723BE PCIe Wireless Network A... | 28    | rtl8723be  | [BFDC2533BB](<All In One/Hewlett-Packard/20/20-c211la/6F4CC01CA4A6/LINUXMINT-20.3/5.4.0-96-GENERIC/X86_64/BFDC2533BB>) |
| 14e4:43ba | 106b:016e | Broadcom         | BCM43602 802.11ac Wireless LAN SoC   | 25    | brcmfmac   | [841AB4FFE2](<All In One/Apple/iMac18/iMac18,2/6AAE34125DB5/FEDORA-36/5.17.0-0.RC5.102.FC36.X86_64/X86_64/841AB4FFE2>) |
| 10ec:c821 | 17aa:c024 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 22    | 8821ce     | [0DD6576588](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-22AST F0D6002EFR/7FE429038D53/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/0DD6576588>) |
| 168c:0042 | 1a3b:2231 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 22    | ath10k_pci | [EF42B78DC5](<All In One/ASUSTek Computer/V221/V221ID/E5E39EC35D8F/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/EF42B78DC5>) |
| 10ec:b822 | 103c:831b | Realtek Semic... | RTL8822BE 802.11a/b/g/n/ac WiFi a... | 20    | rtw_pci    | [A1CB66A671](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-r0xx/117890FC2D25/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/A1CB66A671>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 20    | iwlwifi    | [10E8B5B5BD](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/10E8B5B5BD>) |
| 10ec:8179 | 17aa:0179 | Realtek Semic... | RTL8188EE Wireless Network Adapter   | 19    | rtl8188ee  | [3E79CADCEA](<All In One/Lenovo/C260/C260 10160/A6FBDDCB0193/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/3E79CADCEA>) |
| 10ec:8176 | 10ec:8176 | Realtek Semic... | RTL8188CE 802.11b/g/n WiFi Adapter   | 18    | rtl8192ce  | [485E063883](<All In One/Lenovo/C340/C340 10102/B4F39330CA94/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/485E063883>) |
| 14e4:43ba | 106b:014a | Broadcom         | BCM43602 802.11ac Wireless LAN SoC   | 18    | brcmfmac   | [436904EAE3](<All In One/Apple/iMac17/iMac17,1/7E034427C03F/DEBIAN-11/5.10.0-12-AMD64/X86_64/436904EAE3>) |
| 1814:3090 | 11ad:6622 | Ralink           | RT3090 Wireless 802.11n 1T/1R PCIe   | 18    | rt2800pci  | [33937E8F75](<All In One/Acer/Aspire/Aspire Z1620/19DE00291955/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/33937E8F75>) |
| 8086:3166 | 8086:4210 | Intel            | Dual Band Wireless-AC 3165 Plus B... | 17    | iwlwifi    | [B7EF217600](<All In One/Lenovo/V530-24ICB/V530-24ICB AIO 10UW000ARU/C7E357CDE299/LINUXMINT-20.2/5.4.0-92-GENERIC/X86_64/B7EF217600>) |
| 168c:0034 | 11ad:6621 | Qualcomm Atheros | AR9462 Wireless Network Adapter      | 16    | ath9k      | [520A9BC6A0](<All In One/Acer/Aspire/Aspire ZS600/307894E2C20C/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/520A9BC6A0>) |
| 168c:0042 | 17aa:0901 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 16    | ath10k_pci | [68B6455D7A](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-27ICB F0DE00A7MB/9B6878A5EA27/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/68B6455D7A>) |
| 8086:08b3 | 8086:8070 | Intel            | Wireless 3160                        | 16    | iwlwifi    | [23B20C26F2](<All In One/LG Electronics/22V240/22V240-L.BK55P1/673803797B34/XUBUNTU-20.04/5.13.0-30-GENERIC/X86_64/23B20C26F2>) |
| 168c:0036 | 1028:020c | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 15    | ath9k      | [F96E26BB9A](<All In One/Dell/Inspiron/Inspiron 20 Model 3043/16F41C0EA91A/ZORIN-16/5.13.0-30-GENERIC/X86_64/F96E26BB9A>) |
| 168c:0036 | 1028:020e | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 15    | ath9k      | [75CE72A959](<All In One/Dell/Inspiron/Inspiron 20 Model 3048/4A397B580265/UBUNTU-20.04/5.11.0-37-GENERIC/X86_64/75CE72A959>) |
| 8086:3165 | 8086:4010 | Intel            | Wireless 3165                        | 15    | iwlwifi    | [70A6D2738E](<All In One/MSI/MS-B/MS-B09011/8365E982E7EF/KDE-NEON-20.04/5.11.0-43-GENERIC/X86_64/70A6D2738E>) |
| 14e4:43ba | 106b:016f | Broadcom         | BCM43602 802.11ac Wireless LAN SoC   | 14    | brcmfmac   | [BE5C338F64](<All In One/Apple/iMac18/iMac18,3/77873736C177/ARCO-ROLLING/5.14.12-ARCH1-1/X86_64/BE5C338F64>) |
| 168c:0032 | 17aa:3118 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 14    | ath9k      | [9164B5B105](<All In One/Lenovo/C440/C440 10104/45130055FFB8/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/9164B5B105>) |
| 14e4:4328 | 106b:0087 | Broadcom Limited | BCM4321 802.11a/b/g/n                | 13    | ssb        | [261E6C0463](<All In One/Apple/iMac5/iMac5,1/F72BF7BFE069/LMDE-5/5.10.0-11-686/I686/261E6C0463>) |
| 168c:002b | 1a3b:1089 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 13    | ath9k      | [72365E4985](<All In One/ASUSTek Computer/ET/ET2002/9AD492BE589B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/72365E4985>) |
| 168c:0032 | 1028:0209 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 11    | ath9k      | [6D6980BC69](<All In One/Dell/Inspiron/Inspiron One 2330/CC15798AE672/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/6D6980BC69>) |
| 168c:0032 | 103c:1838 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 11    | ath9k      | [06BE58F9B6](<All In One/Hewlett-Packard/18/18-5200br/3652E5CBCCE1/DEBIAN-11/5.10.0-9-AMD64/X86_64/06BE58F9B6>) |
| 1814:5390 | 1814:f051 | Ralink           | RT5390 Wireless 802.11n 1T/1R PCIe   | 11    | rt2800pci  | [DF20701C5E](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/2B14E403FA28/DEBIAN-10/5.10.0-0.BPO.3-AMD64/X86_64/DF20701C5E>) |
| 10ec:8179 | 1a3b:1f38 | Realtek Semic... | RTL8188EE Wireless Network Adapter   | 10    | rtl8188ee  | [76B99F17C7](<All In One/MSI/MS-AC/MS-AC1511/3E37316EBEBD/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/76B99F17C7>) |
| 14e4:4359 | 14e4:05e2 | Broadcom         | BCM43228 802.11a/b/g/n               | 10    | wl         | [79BAC7CE1B](<All In One/Hewlett-Packard/ProOne/ProOne 400 G1 AiO/F93097D5EFA1/XERO-ROLLING/5.15.12-ARCH1-1/X86_64/79BAC7CE1B>) |
| 168c:002b | 105b:e017 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 10    | ath9k      | [D1D4080F45](<All In One/Sony/VPCJ118/VPCJ118FW/7247E7BFDC34/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D1D4080F45>) |
| 168c:0036 | 11ad:0642 | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 10    | ath9k      | [4E971F0CAA](<All In One/Acer/Aspire/Aspire Z3-615/55D57464CF62/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/4E971F0CAA>) |
| 10ec:8172 | 10ec:e021 | Realtek Semic... | RTL8191SEvB Wireless LAN Controller  | 9     | rtl8192se  | [141F5642FC](<All In One/Acer/Aspire/Aspire Z5610/93F4A5EF8D69/LINUXMINT-20.2/5.4.0-96-GENERIC/X86_64/141F5642FC>) |
| 14e4:4312 | 106b:0089 | Broadcom         | BCM4311 802.11a/b/g                  | 9     | ssb        | [071E31EA5E](<All In One/Apple/iMac4/iMac4,1/B4F87958ABE1/LINUXMINT-19.3/5.4.0-91-GENERIC/I686/071E31EA5E>) |
| 14e4:43a0 | 106b:0142 | Broadcom         | BCM4360 802.11ac Wireless Network... | 9     | wl         | [BC94DA6089](<All In One/Apple/iMac15/iMac15,1/35F88A3CD118/ZORIN-16/5.11.0-46-GENERIC/X86_64/BC94DA6089>) |
| 14e4:4727 | 1028:0010 | Broadcom         | BCM4313 802.11bgn Wireless Networ... | 9     | bcma       | [CDCA9F74F5](<All In One/Dell/Inspiron/Inspiron One 2305/178B94E5C2F7/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/CDCA9F74F5>) |
| 168c:002b | 17aa:30a1 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 9     | ath9k      | [0C9232361D](<All In One/Lenovo/C200/C200 10040/933BB294784A/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/0C9232361D>) |
| 168c:0034 | 144d:4112 | Qualcomm Atheros | AR9462 Wireless Network Adapter      | 9     | ath9k      | [DD513D338C](<All In One/Samsung Electronics/DP700/DP700A3D-DM700A3D-DB701A3D-DP700A7D/F34D6AA53F0D/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/DD513D338C>) |
| 168c:003e | 1028:0310 | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 9     | ath10k_pci | [81AF87F00C](<All In One/Dell/Inspiron/Inspiron 27 7775/D1240D4484D8/ELEMENTARY-5.1.7/5.4.0-89-GENERIC/X86_64/81AF87F00C>) |
| 8086:088e | 8086:4460 | Intel            | Centrino Advanced-N 6235             | 9     | iwlwifi    | [1645DD96FD](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/DC0257EEB120/REBORNOS/5.10.89-1-LTS/X86_64/1645DD96FD>) |
| 8086:3165 | 8086:4410 | Intel            | Wireless 3165                        | 9     | iwlwifi    | [00C297540D](<All In One/Dell/Inspiron/Inspiron 3464 AIO/31AD17DDDC01/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/00C297540D>) |
| 8086:a370 | 8086:0034 | Intel            | Cannon Lake PCH CNVi WiFi            | 9     | iwlwifi    | [CC989948AF](<All In One/Hewlett-Packard/ProOne/ProOne 440 G4 23.8-in NT AiO/9E1FC507AB5B/DEBIAN-11/5.10.0-8-AMD64/X86_64/CC989948AF>) |
| 168c:002b | 105b:e037 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 8     | ath9k      | [E43A2C01EB](<All In One/Sony/VPCL22/VPCL22Z1R/BC94F4FEC1E7/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/E43A2C01EB>) |
| 168c:0036 | 17aa:3026 | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 8     | ath9k      | [7B95568874](<All In One/Lenovo/C560/C560 10150/393D3B2346F6/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/7B95568874>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1502 | 1028:0543 | Intel            | 82579LM Gigabit Network Connectio... | 11    | e1000e     | [F92FA1F111](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/04BEB2B29F37/CLEAR-LINUX-OS-35190/5.13.13-1070.NATIVE/X86_64/F92FA1F111>) |
| 8086:10ef | 17aa:306a | Intel            | 82578DM Gigabit Network Connection   | 7     | e1000e     | [0EF323D23D](<All In One/Lenovo/ThinkCentre/ThinkCentre M90z 5205RQ1/DDABC203DAB8/UBUNTU-20.04/5.8.0-53-GENERIC/X86_64/0EF323D23D>) |
| 8086:10fe | 17aa:3610 | Intel            | 82552 10/100 Network Connection      | 4     | e100       | [11B9953715](<All In One/Lenovo/C/C200/E2BB4B1443B8/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/11B9953715>) |
| 8086:10ce | 104d:9060 | Intel            | 82567V-2 Gigabit Network Connection  | 3     | e1000e     | [05CFF66AC2](<All In One/Sony/VPCL11/VPCL11M1E/93DA71AEEC1E/UBUNTU-19.04/5.0.0-27-GENERIC/X86_64/05CFF66AC2>) |
| 8086:10de | 103c:1489 | Intel            | 82567LM-3 Gigabit Network Connection | 3     | e1000e     | [F321ECCADC](<All In One/Hewlett-Packard/Compaq/Compaq 6000 Pro AiO Brazil PC/8D326FF3188E/POP!_OS-21.10/5.15.11-76051511-GENERIC/X86_64/F321ECCADC>) |
| 8086:10f0 | 1025:8000 | Intel            | 82578DC Gigabit Network Connection   | 3     | e1000e     | [96C29C6C68](<All In One/Acer/Aspire/Aspire Z5710/4B694C479D35/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/96C29C6C68>) |
| 8086:1502 | 103c:3395 | Intel            | 82579LM Gigabit Network Connectio... | 3     | e1000e     | [7814E00461](<All In One/Hewlett-Packard/Compaq/Compaq 8200 Elite AiO Business PC/AF5919835808/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/7814E00461>) |
| 8086:1502 | 8086:0000 | Intel            | 82579LM Gigabit Network Connectio... | 3     | e1000e     | [4E2FFC0DB7](<All In One/InFocus/INF/INF5520/89A8A2E44A06/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/4E2FFC0DB7>) |
| 8086:1503 | 1025:8000 | Intel            | 82579V Gigabit Network Connection    | 3     | e1000e     | [D8225AFA7A](<All In One/Acer/Aspire/Aspire Z5761/79828CC2DB92/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/D8225AFA7A>) |
| 8086:10ce | 1025:048f | Intel            | 82567V-2 Gigabit Network Connection  | 2     | e1000e     | [24D42A520E](<All In One/Acer/Aspire/Aspire Z3730/D0C4BAA72BF8/UBUNTU-MATE-19.10/5.3.0-40-GENERIC/X86_64/24D42A520E>) |
| 8086:10ce | 104d:9043 | Intel            | 82567V-2 Gigabit Network Connection  | 2     | e1000e     | [AFA509714D](<All In One/Sony/VGC-LN52/VGC-LN52JGB/54F15FF48E03/UBUNTU-20.04/5.8.0-54-GENERIC/X86_64/AFA509714D>) |
| 8086:10ce | 104d:9044 | Intel            | 82567V-2 Gigabit Network Connection  | 2     | e1000e     | [EB74857893](<All In One/Sony/VGC-JS210/VGC-JS210J/8B88CB56EBD6/ENDLESS-3.8.6/5.4.0-42-GENERIC/X86_64/EB74857893>) |
| 8086:1539 | 1043:85f0 | Intel            | I211 Gigabit Network Connection      | 2     | igb        | [577AD83B8F](<All In One/Acidanthera/iMacPro1/iMacPro1,1/6286842FEC0E/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/577AD83B8F>) |
| 8086:10d3 | 8086:0000 | Intel            | 82574L Gigabit Network Connection    | 1     | e1000e     | [4E2FFC0DB7](<All In One/InFocus/INF/INF5520/89A8A2E44A06/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/4E2FFC0DB7>) |
| 8086:10eb | 17aa:3608 | Intel            | 82577LC Gigabit Network Connection   | 1     | e1000e     | [69574214D7](<All In One/Lenovo/IdeaCentre/IdeaCentre A700 10050/51968677EC4C/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/69574214D7>) |
| 8086:1502 | 1028:052c | Intel            | 82579LM Gigabit Network Connectio... | 1     | e1000e     | [E7CE3F2F38](<All In One/Acidanthera/iMacPro1/iMacPro1,1/C2AEF029DC5F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E7CE3F2F38>) |
| 8086:1503 | 1043:849c | Intel            | 82579V Gigabit Network Connection    | 1     | e1000e     | [259158AB96](<All In One/Acidanthera/iMacPro1/iMacPro1,1/F1829F0BF600/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/259158AB96>) |
| 8086:1503 | 17aa:3620 | Intel            | 82579V Gigabit Network Connection    | 1     | e1000e     | [520F0EF994](<All In One/Lenovo/IdeaCentre/IdeaCentre B520 7745/71BD816847A0/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/520F0EF994>) |
| 8086:1539 | 1458:e000 | Intel            | I211 Gigabit Network Connection      | 1     | igb        | [42B182D5F0](<All In One/Acidanthera/iMacPro1/iMacPro1,1/9A30E1010885/ARCH/5.9.10-ARCH1-1/X86_64/42B182D5F0>) |
| 8086:1539 | 1849:1539 | Intel            | I211 Gigabit Network Connection      | 1     | igb        | [991A74F3E5](<All In One/Acidanthera/iMacPro1/iMacPro1,1/068603353593/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/991A74F3E5>) |
| 8086:1539 | 8086:0000 | Intel            | I211 Gigabit Network Connection      | 1     | igb        | [4ED51200E5](<All In One/iRU/A/A2313/9007113D5706/ROSA-12/5.10.71-GENERIC-1ROSA2021.1-X86_64/X86_64/4ED51200E5>) |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1455 | 1022:1455 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 4     |            | [81AF87F00C](<All In One/Dell/Inspiron/Inspiron 27 7775/D1240D4484D8/ELEMENTARY-5.1.7/5.4.0-89-GENERIC/X86_64/81AF87F00C>) |
| 1022:145a | 1022:145a | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 4     |            | [81AF87F00C](<All In One/Dell/Inspiron/Inspiron 27 7775/D1240D4484D8/ELEMENTARY-5.1.7/5.4.0-89-GENERIC/X86_64/81AF87F00C>) |
| 1022:1485 | 1022:1485 | AMD              | Starship/Matisse Reserved SPP        | 3     |            | [991A74F3E5](<All In One/Acidanthera/iMacPro1/iMacPro1,1/068603353593/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/991A74F3E5>) |
| 1022:148a | 1022:148a | AMD              | Starship/Matisse PCIe Dummy Function | 2     |            | [991A74F3E5](<All In One/Acidanthera/iMacPro1/iMacPro1,1/068603353593/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/991A74F3E5>) |
| 1022:1485 | 1043:87c0 | AMD              | Starship/Matisse Reserved SPP        | 1     |            | [577AD83B8F](<All In One/Acidanthera/iMacPro1/iMacPro1,1/6286842FEC0E/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/577AD83B8F>) |
| 1022:148a | 1043:87c0 | AMD              | Starship/Matisse PCIe Dummy Function | 1     |            | [577AD83B8F](<All In One/Acidanthera/iMacPro1/iMacPro1,1/6286842FEC0E/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/577AD83B8F>) |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 106b:1801 | 106b:1801 | Apple            | T2 Bridge Controller                 | 2     |            | [43CB3AF3A5](<All In One/Apple/iMacPro1/iMacPro1,1/5A74E0CD85EE/KUBUNTU-20.10/5.8.0-25-LOWLATENCY/X86_64/43CB3AF3A5>) |
| 106b:1802 | 106b:1802 | Apple            | T2 Secure Enclave Processor          | 2     |            | [43CB3AF3A5](<All In One/Apple/iMacPro1/iMacPro1,1/5A74E0CD85EE/KUBUNTU-20.10/5.8.0-25-LOWLATENCY/X86_64/43CB3AF3A5>) |

### Performance counters (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:27a3 |           | Intel            | 945GM/GU Chipset Hardware Monitor... | 23    |            | [261E6C0463](<All In One/Apple/iMac5/iMac5,1/F72BF7BFE069/LMDE-5/5.10.0-11-686/I686/261E6C0463>) |
| 8086:2015 | 8086:0000 | Intel            | Sky Lake-E Ubox Registers            | 2     |            | [43CB3AF3A5](<All In One/Apple/iMacPro1/iMacPro1,1/5A74E0CD85EE/KUBUNTU-20.10/5.8.0-25-LOWLATENCY/X86_64/43CB3AF3A5>) |
| 8086:204c | 8086:0000 | Intel            | Sky Lake-E M3KTI Registers           | 2     |            | [43CB3AF3A5](<All In One/Apple/iMacPro1/iMacPro1,1/5A74E0CD85EE/KUBUNTU-20.10/5.8.0-25-LOWLATENCY/X86_64/43CB3AF3A5>) |
| 8086:204d | 8086:0000 | Intel            | Sky Lake-E M3KTI Registers           | 2     | skx_uncore | [43CB3AF3A5](<All In One/Apple/iMacPro1/iMacPro1,1/5A74E0CD85EE/KUBUNTU-20.10/5.8.0-25-LOWLATENCY/X86_64/43CB3AF3A5>) |
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
| 8086:2026 | 8086:2026 | Intel            | Sky Lake-E IOAPIC                    | 2     |            | [43CB3AF3A5](<All In One/Apple/iMacPro1/iMacPro1,1/5A74E0CD85EE/KUBUNTU-20.10/5.8.0-25-LOWLATENCY/X86_64/43CB3AF3A5>) |
| 8086:2036 | 8086:2036 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 2     |            | [43CB3AF3A5](<All In One/Apple/iMacPro1/iMacPro1,1/5A74E0CD85EE/KUBUNTU-20.10/5.8.0-25-LOWLATENCY/X86_64/43CB3AF3A5>) |
| 8086:0e2c | 1043:84ef | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 1     |            | [259158AB96](<All In One/Acidanthera/iMacPro1/iMacPro1,1/F1829F0BF600/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/259158AB96>) |
| 8086:0e2c | 1458:5000 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 1     |            | [A8D4959FDE](<All In One/Acidanthera/iMacPro1/iMacPro1,1/44B50065E23C/ELEMENTARY-6/5.11.0-25-GENERIC/X86_64/A8D4959FDE>) |
| 8086:2f2c | 8086:0000 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 1     |            | [B2AD449201](<All In One/Acidanthera/iMacPro1/iMacPro1,1/02ABD56D98BC/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/B2AD449201>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14e4:16bc | 14e4:0000 | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 152   | sdhci_pci  | [436904EAE3](<All In One/Apple/iMac17/iMac17,1/7E034427C03F/DEBIAN-11/5.10.0-12-AMD64/X86_64/436904EAE3>) |
| 14e4:16bc | 14e4:96bc | Broadcom Limited | BCM57765/57785 SDXC/MMC Card Reader  | 25    | sdhci_pci  | [7757BE603C](<All In One/Apple/iMac14/iMac14,2/3F4033EA2574/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/7757BE603C>) |
| 1217:8621 | 1217:0002 | O2 Micro         | SD/MMC Card Reader Controller        | 14    | sdhci_pci  | [654A051A24](<All In One/Acer/Aspire/Aspire Z3-715/65616ABBF7DA/UBUNTU-20.10/5.8.0-63-GENERIC/X86_64/654A051A24>) |
| 14e4:16bc | 106b:0000 | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 10    | sdhci_pci  | [5154B1932F](<All In One/Apple/iMac13/iMac13,2/767BA25290CE/GARUDA-SOARING/5.14.14-ZEN1-1-ZEN/X86_64/5154B1932F>) |
| 197b:2381 | 1025:0266 | JMicron Techn... | Standard SD Host Controller          | 10    | sdhci_pci  | [141F5642FC](<All In One/Acer/Aspire/Aspire Z5610/93F4A5EF8D69/LINUXMINT-20.2/5.4.0-96-GENERIC/X86_64/141F5642FC>) |
| 10ec:5209 | 10ec:5209 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 9     | rtsx_pci   | [23B20C26F2](<All In One/LG Electronics/22V240/22V240-L.BK55P1/673803797B34/XUBUNTU-20.04/5.13.0-30-GENERIC/X86_64/23B20C26F2>) |
| 8086:a375 | 103c:84ee | Intel            | 300 Series Chipset Family SD Host... | 9     | sdhci_pci  | [2311649D51](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-xa0xxx/3187A1587DA6/LINUXMINT-20.2/5.4.0-90-GENERIC/X86_64/2311649D51>) |
| 1180:e823 | 104d:907e | Ricoh            | PCIe SDXC/MMC Host Controller        | 6     | sdhci_pci  | [0451CAEB29](<All In One/Sony/VPCL212/VPCL212FX/01EE677E7F92/UBUNTU-21.10/5.13.0-22-GENERIC/X86_64/0451CAEB29>) |
| 8086:31cc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 6     | sdhci_pci  | [10E8B5B5BD](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/10E8B5B5BD>) |
| 8086:31d0 | 8086:7270 | Intel            | SD Host Controller                   | 6     | sdhci_pci  | [10E8B5B5BD](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/10E8B5B5BD>) |
| 1022:7813 | 103c:2b3b | AMD              | FCH SD Flash Controller              | 5     | sdhci_pci  | [B3DCCF594C](<All In One/Hewlett-Packard/23/23-r035la/8A9A83560619/ZORIN-16/5.13.0-27-GENERIC/X86_64/B3DCCF594C>) |
| 1180:e822 | 104d:9097 | Ricoh            | MMC/SD Host Controller               | 5     | sdhci_pci  | [4D477A343A](<All In One/Sony/SVL2411/SVL24117FLB/B337A07B7653/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/4D477A343A>) |
| 1217:8520 | 1028:0626 | O2 Micro         | SD/MMC Card Reader Controller        | 5     | sdhci_pci  | [8F04A0DF98](<All In One/Dell/Inspiron/Inspiron 23 Model 5348/39CAC93F617B/UBUNTU-21.04/5.11.0-34-GENERIC/X86_64/8F04A0DF98>) |
| 8086:5aca | 17aa:36c4 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 5     | sdhci_pci  | [C2A07B6931](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 310-20IAP F0CL005CRK/234016A28DFB/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/C2A07B6931>) |
| 1180:e822 | 104d:907e | Ricoh            | MMC/SD Host Controller               | 4     | sdhci_pci  | [2F2E7E4A62](<All In One/Sony/VPCL22/VPCL22S1E/A460018969DD/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/2F2E7E4A62>) |
| 1180:e822 | 104d:9083 | Ricoh            | MMC/SD Host Controller               | 4     | sdhci_pci  | [B6A48C3652](<All In One/Sony/VPCJ21/VPCJ21S1E/704C84A1D492/LINUXMINT-20.1/5.8.0-40-GENERIC/X86_64/B6A48C3652>) |
| 197b:2381 | 17aa:3602 | JMicron Techn... | Standard SD Host Controller          | 4     | sdhci_pci  | [C25FDFE643](<All In One/Lenovo/IdeaCentre/IdeaCentre B300 10051/20208F91C976/ENDLESS-3.8.6/5.4.0-42-GENERIC/X86_64/C25FDFE643>) |
| 8086:31cc | 1043:1ea0 | Intel            | Celeron/Pentium Silver Processor ... | 4     | sdhci_pci  | [3B910E6A74](<All In One/ASUSTek Computer/Vivo/Vivo AIO 16 V161GA_V161GA/254722CA34A1/ENDLESS-3.9.1/5.8.0-14-GENERIC/X86_64/3B910E6A74>) |
| 1022:7806 | 17aa:3670 | AMD              | FCH SD Flash Controller              | 3     | sdhci_pci  | [225E0C36DC](<All In One/Lenovo/C245/C245 10114/D4553E683441/XUBUNTU-18.04/5.3.0-28-GENERIC/I686/225E0C36DC>) |
| 1022:7813 | 1028:06d1 | AMD              | FCH SD Flash Controller              | 3     | sdhci_pci  | [05A046D623](<All In One/Dell/Inspiron/Inspiron 24-3455/256073270BDD/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/05A046D623>) |
| 10ec:5209 | 1b0a:0188 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 3     | sdhci_pci  | [0C24A93146](<All In One/Pegatron/H81/H81-P2/12407774A62B/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/0C24A93146>) |
| 1180:e822 | 104d:9060 | Ricoh            | MMC/SD Host Controller               | 3     | sdhci_pci  | [05CFF66AC2](<All In One/Sony/VPCL11/VPCL11M1E/93DA71AEEC1E/UBUNTU-19.04/5.0.0-27-GENERIC/X86_64/05CFF66AC2>) |
| 1180:e822 | 104d:9074 | Ricoh            | MMC/SD Host Controller               | 3     | sdhci_pci  | [D1D4080F45](<All In One/Sony/VPCJ118/VPCJ118FW/7247E7BFDC34/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D1D4080F45>) |
| 1180:e823 | 104d:9083 | Ricoh            | PCIe SDXC/MMC Host Controller        | 3     | sdhci_pci  | [EEB433BF77](<All In One/Sony/VPCJ21/VPCJ21S1E/704C84A1D492/LINUXMINT-20.1/5.8.0-53-GENERIC/X86_64/EEB433BF77>) |
| 1217:8520 | 1028:0625 | O2 Micro         | SD/MMC Card Reader Controller        | 3     | sdhci_pci  | [399D367F06](<All In One/Dell/OptiPlex/OptiPlex 9030 AIO/4D03114CF02D/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/399D367F06>) |
| 197b:2381 | 1025:0275 | JMicron Techn... | Standard SD Host Controller          | 3     | sdhci_pci  | [49DF2710DC](<All In One/Packard Bell/ONETWO/ONETWO M3700/3096674A954A/UBUNTU-18.04/5.0.0-37-GENERIC/X86_64/49DF2710DC>) |
| 197b:2381 | 1025:0608 | JMicron Techn... | Standard SD Host Controller          | 3     | sdhci_pci  | [33937E8F75](<All In One/Acer/Aspire/Aspire Z1620/19DE00291955/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/33937E8F75>) |
| 197b:2381 | 103c:1489 | JMicron Techn... | Standard SD Host Controller          | 3     | sdhci_pci  | [F321ECCADC](<All In One/Hewlett-Packard/Compaq/Compaq 6000 Pro AiO Brazil PC/8D326FF3188E/POP!_OS-21.10/5.15.11-76051511-GENERIC/X86_64/F321ECCADC>) |
| 197b:2381 | 1043:842d | JMicron Techn... | Standard SD Host Controller          | 3     | sdhci_pci  | [86CD4A72D1](<All In One/ASUSTek Computer/ET2010/ET2010AG/03DD34D94A32/XUBUNTU-21.04/5.11.0-37-GENERIC/X86_64/86CD4A72D1>) |
| 8086:5acc | 1854:0267 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | sdhci_pci  | [41FA541CA4](<All In One/LG Electronics/22V270/22V270-L.BJ31P1/F6B5728652E7/UBUNTU-20.04/5.4.0-47-GENERIC/X86_64/41FA541CA4>) |
| 1022:7806 | 1462:aa5e | AMD              | FCH SD Flash Controller              | 2     | sdhci_pci  | [A70A78E0D0](<All In One/Itautec/Infoway/Infoway AL2010/799AB71061E2/LINUXMINT-19.3/5.3.0-45-GENERIC/X86_64/A70A78E0D0>) |
| 1022:7813 | 1028:0628 | AMD              | FCH SD Flash Controller              | 2     | sdhci_pci  | [BB462BF2F6](<All In One/Dell/Inspiron/Inspiron 20 Model 3045/ABA0519402D4/KUBUNTU-20.04/5.4.0-40-GENERIC/X86_64/BB462BF2F6>) |
| 1022:7906 | 17aa:36bd | AMD              | FCH SD Flash Controller              | 2     | sdhci_pci  | [CE295294E2](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 510-23ASR F0CE0015UK/7C4A00A8EBE8/KUBUNTU-19.10/5.3.0-51-GENERIC/X86_64/CE295294E2>) |
| 1022:7906 | 17aa:36be | AMD              | FCH SD Flash Controller              | 2     | sdhci_pci  | [4863245A0E](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 510-22ASR F0CC000RLD/54235580CC91/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/4863245A0E>) |
| 1022:7906 | 17aa:36ec | AMD              | FCH SD Flash Controller              | 2     | sdhci_pci  | [2CFA2D338E](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 330-20AST F0D8001LUS/36DA6D8B2B0D/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/2CFA2D338E>) |
| 1180:0822 | 104d:9043 | Ricoh            | R5C822 SD/SDIO/MMC/MS/MSPro Host ... | 2     | sdhci_pci  | [AFA509714D](<All In One/Sony/VGC-LN52/VGC-LN52JGB/54F15FF48E03/UBUNTU-20.04/5.8.0-54-GENERIC/X86_64/AFA509714D>) |
| 1180:0822 | 104d:9044 | Ricoh            | R5C822 SD/SDIO/MMC/MS/MSPro Host ... | 2     | sdhci_pci  | [EB74857893](<All In One/Sony/VGC-JS210/VGC-JS210J/8B88CB56EBD6/ENDLESS-3.8.6/5.4.0-42-GENERIC/X86_64/EB74857893>) |
| 1180:e822 | 104d:908e | Ricoh            | MMC/SD Host Controller               | 2     | sdhci_pci  | [FE0F4C11DF](<All In One/Sony/VPCL22/VPCL22Z1R/FBA23D249ABB/ROSA-2016.1/4.9.76-NRJ-DESKTOP-1ROSA-X86_64/X86_64/FE0F4C11DF>) |
| 1180:e823 | 104d:908e | Ricoh            | PCIe SDXC/MMC Host Controller        | 2     | sdhci_pci  | [E43A2C01EB](<All In One/Sony/VPCL22/VPCL22Z1R/BC94F4FEC1E7/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/E43A2C01EB>) |
| 1180:e823 | 104d:9097 | Ricoh            | PCIe SDXC/MMC Host Controller        | 2     | sdhci_pci  | [B2B912EF1E](<All In One/Sony/SVL2411/SVL24117FLB/B337A07B7653/POP!_OS-20.10/5.11.0-7614-GENERIC/X86_64/B2B912EF1E>) |
| 1217:8321 | 1bcf:a013 | O2 Micro         | OZ600RJ0/OZ900RJ0/OZ600RJS SD/MMC... | 2     | sdhci_pci  | [1494683BB9](<All In One/NEC Computers/PC-VN770/PC-VN770DS3ER/18CEF0AA43DB/UBUNTU-20.04/5.8.0-48-GENERIC/X86_64/1494683BB9>) |
| 197b:2391 | 103c:3561 | JMicron Techn... | Standard SD Host Controller          | 2     | sdhci_pci  | [5FF1D7A72E](<All In One/Hewlett-Packard/Z1/Z1 Workstation/4089A5726DF1/FEDORA-35/5.14.18-300.FC35.X86_64/X86_64/5FF1D7A72E>) |
| 197b:2391 | 1043:84c1 | JMicron Techn... | Standard SD Host Controller          | 2     | sdhci_pci  | [DB3BBECDD0](<All In One/ASUSTek Computer/ET/ET2411/8ACCCF9E85DA/UBUNTU-18.04/4.18.0-16-GENERIC/X86_64/DB3BBECDD0>) |
| 8086:5aca | 8086:1e8b | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | sdhci_pci  | [286F257AF2](<All In One/Intel/AB2/AB2L/922CC7F780A0/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/286F257AF2>) |
| 8086:5aca | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | sdhci_pci  | [9032726EA4](<All In One/CSL-Computer/UNITY/UNITY F24B/D60F8F6679D1/OPENSUSE-20211025/5.14.14-1-DEFAULT/X86_64/9032726EA4>) |
| 8086:5acc | 8086:1e8b | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | sdhci_pci  | [286F257AF2](<All In One/Intel/AB2/AB2L/922CC7F780A0/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/286F257AF2>) |
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | sdhci_pci  | [9032726EA4](<All In One/CSL-Computer/UNITY/UNITY F24B/D60F8F6679D1/OPENSUSE-20211025/5.14.14-1-DEFAULT/X86_64/9032726EA4>) |
| 8086:5ad0 | 8086:1e8b | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | sdhci_pci  | [286F257AF2](<All In One/Intel/AB2/AB2L/922CC7F780A0/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/286F257AF2>) |
| 8086:5ad0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | sdhci_pci  | [9032726EA4](<All In One/CSL-Computer/UNITY/UNITY F24B/D60F8F6679D1/OPENSUSE-20211025/5.14.14-1-DEFAULT/X86_64/9032726EA4>) |
| 1022:7813 | 1028:074a | AMD              | FCH SD Flash Controller              | 1     | sdhci_pci  | [D07D321CCE](<All In One/Dell/Inspiron/Inspiron 22-3265/764B00D389EF/UBUNTU-18.04/4.15.0-38-GENERIC/X86_64/D07D321CCE>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a324 | 8086:7270 | Intel            | Cannon Lake PCH SPI Controller       | 34    | intel_s... | [5E0CEEF0D1](<All In One/Apple/iMac19/iMac19,2/B4B5423C68DB/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/5E0CEEF0D1>) |
| 8086:a324 | 103c:84ee | Intel            | Cannon Lake PCH SPI Controller       | 9     | intel_spi  | [2311649D51](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-xa0xxx/3187A1587DA6/LINUXMINT-20.2/5.4.0-90-GENERIC/X86_64/2311649D51>) |
| 8086:9da4 | 8086:7270 | Intel            | Cannon Point-LP SPI Controller       | 6     |            | [60C6C7EA7C](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/3602C27EA430/ENDLESS-3.9.6/5.8.0-14-GENERIC/X86_64/60C6C7EA7C>) |
| 8086:9dc5 | 1043:17b1 | Intel            | Cannon Point-LP Serial IO I2C Hos... | 6     | intel_lpss | [60C6C7EA7C](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/3602C27EA430/ENDLESS-3.9.6/5.8.0-14-GENERIC/X86_64/60C6C7EA7C>) |
| 8086:9de8 | 1043:17b1 | Intel            | Cannon Point-LP Serial IO I2C Con... | 6     | intel_lpss | [60C6C7EA7C](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/3602C27EA430/ENDLESS-3.9.6/5.8.0-14-GENERIC/X86_64/60C6C7EA7C>) |
| 8086:9de9 | 1043:17b1 | Intel            | Cannon Point-LP Serial IO I2C Con... | 6     | intel_lpss | [60C6C7EA7C](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/3602C27EA430/ENDLESS-3.9.6/5.8.0-14-GENERIC/X86_64/60C6C7EA7C>) |
| 8086:34a4 | 1025:1418 | Intel            | Ice Lake-LP SPI Controller           | 5     | intel_s... | [F15CA34264](<All In One/Acer/Aspire/Aspire C27-962/A23104408196/LINUXMINT-20.3/5.4.0-92-GENERIC/X86_64/F15CA34264>) |
| 8086:a0a4 | 1028:0a06 | Intel            | Tiger Lake-LP SPI Controller         | 5     |            | [503D10D676](<All In One/Dell/Inspiron/Inspiron 5400 AIO/1B0441A55B57/ZORIN-16/5.11.0-38-GENERIC/X86_64/503D10D676>) |
| 8086:a324 | 103c:8446 | Intel            | Cannon Lake PCH SPI Controller       | 5     | intel_spi  | [46A47AB08E](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/D3EA8545A30E/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/46A47AB08E>) |
| 8086:a0a4 | 1043:1482 | Intel            | Tiger Lake-LP SPI Controller         | 4     |            | [FFB4ED2207](<All In One/ASUSTek Computer/ASUS/ASUS Vivo AIO V241EA_V241EA/69C580FE0877/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/FFB4ED2207>) |
| 8086:06a4 | 1028:0984 | Intel            | Comet Lake PCH SPI Controller        | 3     |            | [EA489D447C](<All In One/Dell/OptiPlex/OptiPlex 7480 AIO/AA453186B2B9/LINUXMINT-20.1/5.4.0-104-GENERIC/X86_64/EA489D447C>) |
| 8086:34a4 | 1025:1434 | Intel            | Ice Lake-LP SPI Controller           | 3     |            | [9B4659E4DD](<All In One/Acer/Aspire/Aspire C24-963/CC4A926A8703/ROSA-12/5.10.71-GENERIC-1ROSA2021.1-X86_64/X86_64/9B4659E4DD>) |
| 8086:a324 | 103c:85a2 | Intel            | Cannon Lake PCH SPI Controller       | 3     | intel_s... | [F0691E6EDA](<All In One/Hewlett-Packard/ProOne/ProOne 600 G5 21.5-in All-in-One/FC490F22A5D6/MANJARO/5.10.23-1-MANJARO/X86_64/F0691E6EDA>) |
| 8086:a324 | 17aa:36f4 | Intel            | Cannon Lake PCH SPI Controller       | 3     | intel_s... | [68B6455D7A](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-27ICB F0DE00A7MB/9B6878A5EA27/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/68B6455D7A>) |
| 8086:02a4 | 1028:0953 | Intel            | Comet Lake SPI (flash) Controller    | 2     |            | [AEFAC2FB50](<All In One/Dell/Inspiron/Inspiron 5490 AIO/B7D11D1CE42A/ZORIN-16/5.11.0-36-GENERIC/X86_64/AEFAC2FB50>) |
| 8086:02a4 | 1028:0954 | Intel            | Comet Lake SPI (flash) Controller    | 2     |            | [51D212B73F](<All In One/Dell/Inspiron/Inspiron 7790 AIO/5226FB806DAF/UBUNTU-2020/5.8.0-44-GENERIC/X86_64/51D212B73F>) |
| 8086:02a4 | 17aa:370c | Intel            | Comet Lake SPI (flash) Controller    | 2     |            | [B9A115E6A4](<All In One/Lenovo/IdeaCentre/IdeaCentre A340-24IWL F0E800Q1IN/7A95353B97C7/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/B9A115E6A4>) |
| 8086:02a4 | 8086:7270 | Intel            | Comet Lake SPI (flash) Controller    | 2     |            | [9E72716F96](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222FA_A6432FA/9F429A9552E8/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/9E72716F96>) |
| 8086:02c5 | 1043:1f51 | Intel            | Comet Lake Serial IO I2C Host Con... | 2     | intel_lpss | [9E72716F96](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222FA_A6432FA/9F429A9552E8/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/9E72716F96>) |
| 8086:02e8 | 1043:1f51 | Intel            | Serial IO I2C Host Controller        | 2     | intel_lpss | [9E72716F96](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222FA_A6432FA/9F429A9552E8/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/9E72716F96>) |
| 8086:02e9 | 1043:1f51 | Intel            | Comet Lake Serial IO I2C Host Con... | 2     | intel_lpss | [9E72716F96](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222FA_A6432FA/9F429A9552E8/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/9E72716F96>) |
| 8086:06a4 | 103c:86c7 | Intel            | Comet Lake PCH SPI Controller        | 2     | intel_spi  | [EFB6906A46](<All In One/Hewlett-Packard/ENVY/ENVY All-in-One 32-a11xxx/AC2CB5057523/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/EFB6906A46>) |
| 8086:34a4 | 103c:87a4 | Intel            | Ice Lake-LP SPI Controller           | 2     | intel_s... | [FCC6F8EC82](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-df0xxx/1ACFF9ABA384/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/FCC6F8EC82>) |
| 8086:9da4 | 17aa:36fe | Intel            | Cannon Point-LP SPI Controller       | 2     |            | [CA86244C1D](<All In One/Lenovo/IdeaCentre/IdeaCentre A340-22IWL F0EB006RRI/F8358448E319/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/CA86244C1D>) |
| 8086:a324 | 1025:1290 | Intel            | Cannon Lake PCH SPI Controller       | 2     |            | [A27363041A](<All In One/Acer/Veriton/Veriton Z4860G/8955EDC1BE49/ENDLESS-3.9.1/5.8.0-14-GENERIC/X86_64/A27363041A>) |
| 8086:a324 | 1025:1291 | Intel            | Cannon Lake PCH SPI Controller       | 2     | intel_s... | [13496AAE5D](<All In One/Acer/Veriton/Veriton Z4660G/A736A6205FE1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/13496AAE5D>) |
| 8086:a324 | 1028:084b | Intel            | Cannon Lake PCH SPI Controller       | 2     |            | [301B4DE8EA](<All In One/Dell/OptiPlex/OptiPlex 7460 AIO/221C8E22E535/KUBUNTU-20.04/5.4.0-59-GENERIC/X86_64/301B4DE8EA>) |
| 8086:a324 | 103c:83eb | Intel            | Cannon Lake PCH SPI Controller       | 2     |            | [CC989948AF](<All In One/Hewlett-Packard/ProOne/ProOne 440 G4 23.8-in NT AiO/9E1FC507AB5B/DEBIAN-11/5.10.0-8-AMD64/X86_64/CC989948AF>) |
| 8086:a324 | 17aa:313d | Intel            | Cannon Lake PCH SPI Controller       | 2     |            | [50AAA5CF43](<All In One/Lenovo/V530-22ICB/V530-22ICB AIO 10US003EUM/BF722D010110/UBUNTU-20.04/5.8.0-50-GENERIC/X86_64/50AAA5CF43>) |
| 8086:a324 | 17aa:3701 | Intel            | Cannon Lake PCH SPI Controller       | 2     |            | [3AAB28E1E4](<All In One/Lenovo/IdeaCentre/IdeaCentre A540-27ICB F0EK0056MZ/E1FEFC182AD1/UBUNTU-21.04/5.11.0-17-GENERIC/X86_64/3AAB28E1E4>) |
| 8086:a368 | 1025:1290 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 2     | intel_lpss | [A27363041A](<All In One/Acer/Veriton/Veriton Z4860G/8955EDC1BE49/ENDLESS-3.9.1/5.8.0-14-GENERIC/X86_64/A27363041A>) |
| 8086:a368 | 1025:1291 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 2     | intel_lpss | [13496AAE5D](<All In One/Acer/Veriton/Veriton Z4660G/A736A6205FE1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/13496AAE5D>) |
| 8086:a368 | 1043:1241 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 2     | intel_l... | [2F804D87B1](<All In One/ASUSTek Computer/Zen/Zen AIO 24 ZN242GD_ZN242GD/9589773F7783/UBUNTU-18.04/5.4.0-80-GENERIC/X86_64/2F804D87B1>) |
| 8086:a369 | 1043:1241 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 2     | intel_l... | [2F804D87B1](<All In One/ASUSTek Computer/Zen/Zen AIO 24 ZN242GD_ZN242GD/9589773F7783/UBUNTU-18.04/5.4.0-80-GENERIC/X86_64/2F804D87B1>) |
| 10de:1adb | 10de:13ad | Nvidia           | TU106 USB Type-C UCSI Controller     | 1     | i2c_nvi... | [E0192EBFC1](<All In One/Apple/iMac17/iMac17,1/6B3AAAC52B64/UBUNTU-18.04/5.2.13-050213-GENERIC/X86_64/E0192EBFC1>) |
| 8086:02a4 | 17aa:3185 | Intel            | Comet Lake SPI (flash) Controller    | 1     |            | [324F862858](<All In One/Lenovo/V30a-24IML/V30a-24IML 11FT003QIH/6732593F3092/UBUNTU-18.04/4.15.0-20-GENERIC/X86_64/324F862858>) |
| 8086:02a4 | 17aa:370b | Intel            | Comet Lake SPI (flash) Controller    | 1     |            | [F179844FE4](<All In One/Lenovo/IdeaCentre/IdeaCentre A340-22IWL F0EB00EKRK/3C652B5856C0/UBUNTU-20.04/5.8.0-53-GENERIC/X86_64/F179844FE4>) |
| 8086:06a4 | 103c:86ed | Intel            | Comet Lake PCH SPI Controller        | 1     |            | [78778F22A2](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-k0xxx/97B1ED37BE45/ELEMENTARY-6/5.11.0-27-GENERIC/X86_64/78778F22A2>) |
| 8086:06a4 | 103c:871c | Intel            | Comet Lake PCH SPI Controller        | 1     |            | [2F7FD6200F](<All In One/Hewlett-Packard/ProOne/ProOne 440 G6 24 All-in-One PC/E75014542A4C/CENTOS-7/3.10.0-1160.11.1.EL7.X86_64/X86_64/2F7FD6200F>) |
| 8086:43a4 | 1043:8694 | Intel            | Tiger Lake-H SPI Controller          | 1     |            | [38DDF02B60](<All In One/AIO/PC/PC/72C48E584F76/RED-OS-7.3.1/5.15.10-1.EL7.X86_64/X86_64/38DDF02B60>) |
| 8086:43a4 | 1849:43a4 | Intel            | Tiger Lake-H SPI Controller          | 1     |            | [4D3DF118F0](<All In One/Aquarius/Pro/Pro T514 R53/3714C95A3FFD/RED-OS-7.3/5.15.10-2.EL7.X86_64/X86_64/4D3DF118F0>) |
| 8086:43e8 | 1043:8694 | Intel            | Tiger Lake-H Serial IO I2C Contro... | 1     | intel_lpss | [38DDF02B60](<All In One/AIO/PC/PC/72C48E584F76/RED-OS-7.3.1/5.15.10-1.EL7.X86_64/X86_64/38DDF02B60>) |
| 8086:5ac8 | 8086:1e8b | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | pwm_lpss   | [286F257AF2](<All In One/Intel/AB2/AB2L/922CC7F780A0/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/286F257AF2>) |
| 8086:9da4 | 1028:08f9 | Intel            | Cannon Point-LP SPI Controller       | 1     |            | [727E0D3A2E](<All In One/Dell/Inspiron/Inspiron 3280 AIO/34CA6784808C/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/727E0D3A2E>) |
| 8086:9da4 | 17aa:36ff | Intel            | Cannon Point-LP SPI Controller       | 1     |            | [9AA68C7A65](<All In One/Lenovo/IdeaCentre/IdeaCentre A340-24IWL F0E8000JRK/0806E00F37CD/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/9AA68C7A65>) |
| 8086:9dc5 | 1028:08f9 | Intel            | Cannon Point-LP Serial IO I2C Hos... | 1     | intel_l... | [727E0D3A2E](<All In One/Dell/Inspiron/Inspiron 3280 AIO/34CA6784808C/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/727E0D3A2E>) |
| 8086:a0a4 | 1025:1475 | Intel            | Tiger Lake-LP SPI Controller         | 1     |            | [32ECAAC328](<All In One/Acer/Aspire/Aspire C24-1650/DA8A3F508342/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/32ECAAC328>) |
| 8086:a0a4 | 1025:150f | Intel            | Tiger Lake-LP SPI Controller         | 1     |            | [BC20F9A9CA](<All In One/Acer/Aspire/Aspire C27-1655/163A30053117/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/BC20F9A9CA>) |
| 8086:a0a4 | 1028:0a07 | Intel            | Tiger Lake-LP SPI Controller         | 1     |            | [354668E360](<All In One/Dell/Inspiron/Inspiron 7700 AIO/BE97ED33795E/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/354668E360>) |
| 8086:a0a4 | 103c:87f3 | Intel            | Tiger Lake-LP SPI Controller         | 1     |            | [4F0974E255](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-dd1xxx/2777F47C0C1D/LINUXMINT-20.2/5.4.0-89-GENERIC/X86_64/4F0974E255>) |

### Serial controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1e3d | 1028:0543 | Intel            | 7 Series/C210 Series Chipset Fami... | 12    | serial     | [F92FA1F111](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/04BEB2B29F37/CLEAR-LINUX-OS-35190/5.13.13-1070.NATIVE/X86_64/F92FA1F111>) |
| 8086:8c3d | 1028:05a7 | Intel            | 8 Series/C220 Series Chipset Fami... | 8     | serial     | [1645DD96FD](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/DC0257EEB120/REBORNOS/5.10.89-1-LTS/X86_64/1645DD96FD>) |
| 8086:8c3d | 103c:18e6 | Intel            | 8 Series/C220 Series Chipset Fami... | 6     | serial     | [F8D1E58D06](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G1 AiO/44D1B0C864ED/LINUXMINT-18.3/4.15.0-142-GENERIC/X86_64/F8D1E58D06>) |
| 8086:1c3d | 103c:3395 | Intel            | 6 Series/C200 Series Chipset Fami... | 3     | serial     | [7814E00461](<All In One/Hewlett-Packard/Compaq/Compaq 8200 Elite AiO Business PC/AF5919835808/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/7814E00461>) |
| 8086:2e17 | 103c:1489 | Intel            | 4 Series Chipset Serial KT Contro... | 3     | serial     | [F321ECCADC](<All In One/Hewlett-Packard/Compaq/Compaq 6000 Pro AiO Brazil PC/8D326FF3188E/POP!_OS-21.10/5.15.11-76051511-GENERIC/X86_64/F321ECCADC>) |
| 8086:a13d | 17aa:30ba | Intel            | 100 Series/C230 Series Chipset Fa... | 3     | serial     | [F3E9E0B2F5](<All In One/Lenovo/ThinkCentre/ThinkCentre M900z 10F3000DGE/DDF891FE5172/ROSA-2016.1/4.15.0-DESKTOP-68.5ROSA-X86_64/X86_64/F3E9E0B2F5>) |
| 8086:a363 | 103c:85a2 | Intel            | Cannon Lake PCH Active Management... | 3     | serial     | [F0691E6EDA](<All In One/Hewlett-Packard/ProOne/ProOne 600 G5 21.5-in All-in-One/FC490F22A5D6/MANJARO/5.10.23-1-MANJARO/X86_64/F0691E6EDA>) |
| 10ec:816a | 1025:1290 | Realtek Semic... | RTL8111xP UART #1                    | 2     |            | [A27363041A](<All In One/Acer/Veriton/Veriton Z4860G/8955EDC1BE49/ENDLESS-3.9.1/5.8.0-14-GENERIC/X86_64/A27363041A>) |
| 10ec:816a | 1025:1291 | Realtek Semic... | RTL8111xP UART #1                    | 2     | serial     | [13496AAE5D](<All In One/Acer/Veriton/Veriton Z4660G/A736A6205FE1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/13496AAE5D>) |
| 10ec:816b | 1025:1290 | Realtek Semic... | RTL8111xP UART #2                    | 2     |            | [A27363041A](<All In One/Acer/Veriton/Veriton Z4860G/8955EDC1BE49/ENDLESS-3.9.1/5.8.0-14-GENERIC/X86_64/A27363041A>) |
| 10ec:816b | 1025:1291 | Realtek Semic... | RTL8111xP UART #2                    | 2     | serial     | [13496AAE5D](<All In One/Acer/Veriton/Veriton Z4660G/A736A6205FE1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/13496AAE5D>) |
| 8086:1c3d | 103c:3561 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | serial     | [5FF1D7A72E](<All In One/Hewlett-Packard/Z1/Z1 Workstation/4089A5726DF1/FEDORA-35/5.14.18-300.FC35.X86_64/X86_64/5FF1D7A72E>) |
| 8086:8c3d | 103c:18e8 | Intel            | 8 Series/C220 Series Chipset Fami... | 2     | serial     | [BD9D548890](<All In One/Hewlett-Packard/ProOne/ProOne 600 G1 AiO/3C8246737092/UBUNTU-21.10/5.13.0-20-GENERIC/X86_64/BD9D548890>) |
| 8086:a13d | 1028:075d | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | serial     | [404A8B3A68](<All In One/Dell/Precision/Precision 5720 AIO/20C5601ED4D8/FEDORA-30/5.2.16-200.FC30.X86_64/X86_64/404A8B3A68>) |
| 8086:a13d | 103c:8058 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | serial     | [09B55E64F6](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G2 23-in Non-Touch AiO/0E4D816E1F73/UBUNTU-20.04/5.4.0-31-GENERIC/X86_64/09B55E64F6>) |
| 8086:a2bd | 1028:079c | Intel            | 200 Series Chipset Family KT Redi... | 2     | serial     | [0B0F9A42CD](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/F87DB1F1F5AC/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/0B0F9A42CD>) |
| 8086:a2bd | 103c:829b | Intel            | 200 Series Chipset Family KT Redi... | 2     | serial     | [44675B1F55](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G3 23.8-in Non-Touch AiO/37F128288AEC/UBUNTU-18.04/4.18.0-24-GENERIC/X86_64/44675B1F55>) |
| 8086:a363 | 103c:83eb | Intel            | Cannon Lake PCH Active Management... | 2     | serial     | [CC989948AF](<All In One/Hewlett-Packard/ProOne/ProOne 440 G4 23.8-in NT AiO/9E1FC507AB5B/DEBIAN-11/5.10.0-8-AMD64/X86_64/CC989948AF>) |
| 13a8:0354 |           | Exar             | Exar's 4-Port UART PCIe Card         | 1     | 8250_exar  | [B5FBC6A19B](<All In One/Lenovo/IdeaCentre/IdeaCentre B540p 3363/9976329CE6AE/UBUNTU-20.04/5.4.0-31-GENERIC/X86_64/B5FBC6A19B>) |
| 8086:06e3 | 103c:871c | Intel            | Comet Lake Keyboard and Text (KT)... | 1     | serial     | [2F7FD6200F](<All In One/Hewlett-Packard/ProOne/ProOne 440 G6 24 All-in-One PC/E75014542A4C/CENTOS-7/3.10.0-1160.11.1.EL7.X86_64/X86_64/2F7FD6200F>) |
| 8086:1c3d | 1c1d:0001 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | serial     | [4E2FFC0DB7](<All In One/InFocus/INF/INF5520/89A8A2E44A06/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/4E2FFC0DB7>) |
| 8086:1e3d | 1028:0577 | Intel            | 7 Series/C210 Series Chipset Fami... | 1     | serial     | [E7CE3F2F38](<All In One/Acidanthera/iMacPro1/iMacPro1,1/C2AEF029DC5F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E7CE3F2F38>) |
| 8086:1e3d | 1854:f004 | Intel            | 7 Series/C210 Series Chipset Fami... | 1     | serial     | [81CF385125](<All In One/LG Electronics/LG/LG SUPERSIGN/3DF362B44399/ROSA-2012.0/3.0.28-NRJ-DESKTOP-2ROSA.LTS/X86_64/81CF385125>) |
| 8086:8c3d | 1028:0625 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | serial     | [399D367F06](<All In One/Dell/OptiPlex/OptiPlex 9030 AIO/4D03114CF02D/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/399D367F06>) |
| 8086:8c3d | 8086:204c | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | serial     | [098FE372A3](<All In One/Acidanthera/iMac14/iMac14,4/E2C69985CC45/GENTOO-2.6/5.4.97-GENTOO_DQ87PG/X86_64/098FE372A3>) |
| 8086:8d3d | 8086:7270 | Intel            | C610/X99 series chipset KT Contro... | 1     | serial     | [B2AD449201](<All In One/Acidanthera/iMacPro1/iMacPro1,1/02ABD56D98BC/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/B2AD449201>) |
| 8086:a13d | 1028:06c5 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | serial     | [0DCB1B8C3C](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/34CACCC6D3D6/UBUNTU-20.04/5.13.0-32-GENERIC/X86_64/0DCB1B8C3C>) |
| 8086:a13d | 103c:805e | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | serial     | [FDD0A4E977](<All In One/Hewlett-Packard/ProOne/ProOne 600 G2 21.5-in Non-Touch AiO/9C57BC957F05/CLEAR-LINUX-OS-31530/5.3.9-863.NATIVE/X86_64/FDD0A4E977>) |
| 8086:a13d | 103c:8139 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | serial     | [453674ECA2](<All In One/Hewlett-Packard/RP9/RP9 G1 AiO Retail System, Model 9015/2AA49223DF93/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/453674ECA2>) |
| 8086:a2bd | 17aa:3110 | Intel            | 200 Series Chipset Family KT Redi... | 1     | serial     | [84B6274AFE](<All In One/Lenovo/ThinkCentre/ThinkCentre M910z 10NR0012SP/02C4FE3BB5A8/DEBIAN-11/5.10.0-8-AMD64/X86_64/84B6274AFE>) |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:3b32 | 8086:0000 | Intel            | 5 Series/3400 Series Chipset Ther... | 56    | intel_ips  | [99D7E82DF9](<All In One/Apple/iMac11/iMac11,2/9D11563CF50D/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/99D7E82DF9>) |
| 8086:a379 | 8086:7270 | Intel            | Cannon Lake PCH Thermal Controller   | 32    | intel_p... | [5E0CEEF0D1](<All In One/Apple/iMac19/iMac19,2/B4B5423C68DB/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/5E0CEEF0D1>) |
| 8086:9d61 | 8086:9d61 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 22    | intel_l... | [43184FD6BF](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/3E27DCFED7C5/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/43184FD6BF>) |
| 8086:9d60 | 103c:84de | Intel            | Sunrise Point-LP Serial IO I2C Co... | 14    | intel_l... | [43184FD6BF](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/3E27DCFED7C5/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/43184FD6BF>) |
| 8086:9a0d |           | Intel            | Tigerlake Telemetry Aggregator       | 11    | intel_pmt  | [503D10D676](<All In One/Dell/Inspiron/Inspiron 5400 AIO/1B0441A55B57/ZORIN-16/5.11.0-38-GENERIC/X86_64/503D10D676>) |
| 8086:3a32 | 1025:0266 | Intel            | 82801JI (ICH10 Family) Thermal Su... | 10    |            | [141F5642FC](<All In One/Acer/Aspire/Aspire Z5610/93F4A5EF8D69/LINUXMINT-20.2/5.4.0-96-GENERIC/X86_64/141F5642FC>) |
| 8086:9d31 | 8086:9d31 | Intel            | Sunrise Point-LP Thermal subsystem   | 10    | intel_p... | [8826665773](<All In One/ASUSTek Computer/ZN240/ZN240IC/B519220D6F37/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/8826665773>) |
| 8086:22dc |           | Intel            | Atom/Celeron/Pentium Processor x5... | 9     | process... | [8FD1F10C40](<All In One/ASUSTek Computer/A/A4110/816792239BA1/ZORIN-16/5.13.0-30-GENERIC/X86_64/8FD1F10C40>) |
| 8086:318c | 1025:1304 | Intel            | Celeron/Pentium Silver Processor ... | 9     | proc_th... | [B7F823BFDA](<All In One/Others/Others/Others/EFF35801EAC2/UBUNTU/5.8.0-14-GENERIC/X86_64/B7F823BFDA>) |
| 8086:9d31 | 1025:1287 | Intel            | Sunrise Point-LP Thermal subsystem   | 9     | intel_p... | [70014EA10E](<All In One/Acer/Aspire/Aspire C22-865/CAE70310F314/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/70014EA10E>) |
| 8086:a379 | 103c:84ee | Intel            | Cannon Lake PCH Thermal Controller   | 9     | intel_p... | [2311649D51](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-xa0xxx/3187A1587DA6/LINUXMINT-20.2/5.4.0-90-GENERIC/X86_64/2311649D51>) |
| 8086:9d60 | 8086:9d60 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 8     | intel_l... | [2FDFFAE0E5](<All In One/ASUSTek Computer/V241/V241IC-R/F65D7B31A7ED/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/2FDFFAE0E5>) |
| 8086:1903 | 8086:1903 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 7     | proc_th... | [2FDFFAE0E5](<All In One/ASUSTek Computer/V241/V241IC-R/F65D7B31A7ED/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/2FDFFAE0E5>) |
| 8086:318c | 1854:0308 | Intel            | Celeron/Pentium Silver Processor ... | 7     | process... | [F57C7BBE97](<All In One/LG Electronics/22V280/22V280-L.BY31P1/BF6C05A5FCC3/ENDEAVOUROS-ROLLING/5.13.12-ARCH1-1/X86_64/F57C7BBE97>) |
| 8086:8ca4 | 8086:7270 | Intel            | 9 Series Chipset Family Thermal C... | 7     |            | [BC313CE031](<All In One/Apple/iMac16/iMac16,2/224B9F366AD7/ENDEAVOUROS-ROLLING/5.15.7-ARCH1-1/X86_64/BC313CE031>) |
| 8086:9d31 | 1028:0754 | Intel            | Sunrise Point-LP Thermal subsystem   | 7     | intel_p... | [00C297540D](<All In One/Dell/Inspiron/Inspiron 3464 AIO/31AD17DDDC01/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/00C297540D>) |
| 8086:9d60 | 1028:0754 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 7     | intel_l... | [00C297540D](<All In One/Dell/Inspiron/Inspiron 3464 AIO/31AD17DDDC01/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/00C297540D>) |
| 8086:9d61 | 1028:0754 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 7     | intel_l... | [00C297540D](<All In One/Dell/Inspiron/Inspiron 3464 AIO/31AD17DDDC01/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/00C297540D>) |
| 8086:a131 | 1028:06c5 | Intel            | 100 Series/C230 Series Chipset Fa... | 7     | intel_p... | [0DCB1B8C3C](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/34CACCC6D3D6/UBUNTU-20.04/5.13.0-32-GENERIC/X86_64/0DCB1B8C3C>) |
| 8086:1903 | 1043:17b1 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 6     | proc_th... | [60C6C7EA7C](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/3602C27EA430/ENDLESS-3.9.6/5.8.0-14-GENERIC/X86_64/60C6C7EA7C>) |
| 8086:9df9 | 1043:17b1 | Intel            | Cannon Point-LP Thermal Controller   | 6     | intel_p... | [60C6C7EA7C](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/3602C27EA430/ENDLESS-3.9.6/5.8.0-14-GENERIC/X86_64/60C6C7EA7C>) |
| 8086:318c | 103c:86f0 | Intel            | Celeron/Pentium Silver Processor ... | 5     | process... | [75738404AE](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-df0xxx/20A2CA3001FD/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/75738404AE>) |
| 8086:318c | 1043:1e80 | Intel            | Celeron/Pentium Silver Processor ... | 5     | process... | [23082AB8CA](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222GA_V222GA/30DB3562CA34/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/23082AB8CA>) |
| 8086:31b4 | 1043:1e80 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_l... | [23082AB8CA](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222GA_V222GA/30DB3562CA34/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/23082AB8CA>) |
| 8086:31b6 | 1043:1e80 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_l... | [23082AB8CA](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222GA_V222GA/30DB3562CA34/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/23082AB8CA>) |
| 8086:31c2 | 1043:1e80 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_l... | [23082AB8CA](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222GA_V222GA/30DB3562CA34/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/23082AB8CA>) |
| 8086:5a8c |           | Intel            | Atom/Celeron/Pentium Dynamic Plat... | 5     | process... | [286F257AF2](<All In One/Intel/AB2/AB2L/922CC7F780A0/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/286F257AF2>) |
| 8086:5a8c | 17aa:36c4 | Intel            | Atom/Celeron/Pentium Dynamic Plat... | 5     | process... | [C2A07B6931](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 310-20IAP F0CL005CRK/234016A28DFB/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/C2A07B6931>) |
| 8086:9ca4 | 8086:7270 | Intel            | Wildcat Point-LP Thermal Manageme... | 5     | intel_p... | [6514199D0C](<All In One/Apple/iMac16/iMac16,1/4BCFE045F418/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/6514199D0C>) |
| 8086:a131 | 8086:a131 | Intel            | 100 Series/C230 Series Chipset Fa... | 5     | intel_p... | [31E48D8DA1](<All In One/ASUSTek Computer/Z240/Z240IC-H170/FB2F1250F58B/POP!_OS-20.10/5.8.0-7642-GENERIC/X86_64/31E48D8DA1>) |
| 8086:a379 | 103c:8446 | Intel            | Cannon Lake PCH Thermal Controller   | 5     | intel_p... | [46A47AB08E](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/D3EA8545A30E/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/46A47AB08E>) |
| 8086:1e24 | 1462:b062 | Intel            | 7 Series/C210 Series Chipset Fami... | 4     |            | [E00F23043A](<All In One/MSI/MS-B/MS-B06211/337FE0F473E0/LINUXMINT-20.2/5.4.0-90-GENERIC/X86_64/E00F23043A>) |
| 8086:318c | 1043:1ea0 | Intel            | Celeron/Pentium Silver Processor ... | 4     | proc_th... | [3B910E6A74](<All In One/ASUSTek Computer/Vivo/Vivo AIO 16 V161GA_V161GA/254722CA34A1/ENDLESS-3.9.1/5.8.0-14-GENERIC/X86_64/3B910E6A74>) |
| 8086:31b4 | 1043:1ea0 | Intel            | Celeron/Pentium Silver Processor ... | 4     | intel_lpss | [3B910E6A74](<All In One/ASUSTek Computer/Vivo/Vivo AIO 16 V161GA_V161GA/254722CA34A1/ENDLESS-3.9.1/5.8.0-14-GENERIC/X86_64/3B910E6A74>) |
| 8086:31b6 | 1043:1ea0 | Intel            | Celeron/Pentium Silver Processor ... | 4     | intel_lpss | [3B910E6A74](<All In One/ASUSTek Computer/Vivo/Vivo AIO 16 V161GA_V161GA/254722CA34A1/ENDLESS-3.9.1/5.8.0-14-GENERIC/X86_64/3B910E6A74>) |
| 8086:31c2 | 1043:1ea0 | Intel            | Celeron/Pentium Silver Processor ... | 4     | intel_lpss | [3B910E6A74](<All In One/ASUSTek Computer/Vivo/Vivo AIO 16 V161GA_V161GA/254722CA34A1/ENDLESS-3.9.1/5.8.0-14-GENERIC/X86_64/3B910E6A74>) |
| 8086:9a03 | 1043:1482 | Intel            | TigerLake-LP Dynamic Tuning Proce... | 4     | proc_th... | [FFB4ED2207](<All In One/ASUSTek Computer/ASUS/ASUS Vivo AIO V241EA_V241EA/69C580FE0877/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/FFB4ED2207>) |
| 8086:a131 | 1025:1063 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     | intel_p... | [654A051A24](<All In One/Acer/Aspire/Aspire Z3-715/65616ABBF7DA/UBUNTU-20.10/5.8.0-63-GENERIC/X86_64/654A051A24>) |
| 8086:a3b1 | 8086:7270 | Intel            | Comet Lake PCH-V Thermal Subsystem   | 4     |            | [273716C6CB](<All In One/Others/Others/Others/2C5F9D7A9E9D/UBUNTU-20.04/5.11.0-25-GENERIC/X86_64/273716C6CB>) |
| 8086:06f9 | 1028:0984 | Intel            | Comet Lake PCH Thermal Controller    | 3     | intel_p... | [EA489D447C](<All In One/Dell/OptiPlex/OptiPlex 7480 AIO/AA453186B2B9/LINUXMINT-20.1/5.4.0-104-GENERIC/X86_64/EA489D447C>) |
| 8086:1603 | 8086:2010 | Intel            | Broadwell-U Processor Thermal Sub... | 3     | process... | [CF0ED40752](<All In One/LG Electronics/24V550/24V550-G.BJ31P1/F728BA821E63/POP!_OS-20.04/5.11.0-7620-GENERIC/X86_64/CF0ED40752>) |
| 8086:1903 | 1043:12a1 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 3     | proc_th... | [E0EF808E3F](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222UA/9F8A84B648C2/ENDLESS-3.4.1/4.15.0-22-GENERIC/X86_64/E0EF808E3F>) |
| 8086:318c | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 3     | proc_th... | [10E8B5B5BD](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/10E8B5B5BD>) |
| 8086:31ac | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 3     | intel_l... | [10E8B5B5BD](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/10E8B5B5BD>) |
| 8086:31ae | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 3     | intel_l... | [10E8B5B5BD](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/10E8B5B5BD>) |
| 8086:31b0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 3     | intel_l... | [10E8B5B5BD](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/10E8B5B5BD>) |
| 8086:31b2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 3     | intel_l... | [10E8B5B5BD](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/10E8B5B5BD>) |
| 8086:31b4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 3     | intel_l... | [10E8B5B5BD](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/10E8B5B5BD>) |
| 8086:31b6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 3     | intel_l... | [10E8B5B5BD](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/10E8B5B5BD>) |
| 8086:31bc | 17aa:36ed | Intel            | Celeron/Pentium Silver Processor ... | 3     | intel_l... | [B5D4B3357A](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 330-20IGM F0D70043CK/77A4D86B366E/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B5D4B3357A>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:283e | 106b:00a0 | Intel            | 82801H (ICH8 Family) SMBus Contro... | 108   | i2c_i801   | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 8086:1c22 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 103   | i2c_i801   | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 10de:0aa2 | 10de:cb79 | Nvidia           | MCP79 SMBus                          | 88    | i2c_nfo... | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 8086:a123 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 57    | i2c_i801   | [436904EAE3](<All In One/Apple/iMac17/iMac17,1/7E034427C03F/DEBIAN-11/5.10.0-12-AMD64/X86_64/436904EAE3>) |
| 8086:3b30 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset SMBu... | 56    | i2c_i801   | [99D7E82DF9](<All In One/Apple/iMac11/iMac11,2/9D11563CF50D/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/99D7E82DF9>) |
| 8086:8c22 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 46    | i2c_i801   | [7757BE603C](<All In One/Apple/iMac14/iMac14,2/3F4033EA2574/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/7757BE603C>) |
| 8086:1e22 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family SMBu... | 32    | i2c_i801   | [435548337A](<All In One/Apple/iMac13/iMac13,1/BB29D11F01EF/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/435548337A>) |
| 8086:a323 | 8086:7270 | Intel            | Cannon Lake PCH SMBus Controller     | 32    | i2c_i801   | [5E0CEEF0D1](<All In One/Apple/iMac19/iMac19,2/B4B5423C68DB/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/5E0CEEF0D1>) |
| 8086:27da | 8086:7270 | Intel            | NM10/ICH7 Family SMBus Controller    | 23    | i2c_i801   | [261E6C0463](<All In One/Apple/iMac5/iMac5,1/F72BF7BFE069/LMDE-5/5.10.0-11-686/I686/261E6C0463>) |
| 1022:780b | 103c:8245 | AMD              | FCH SMBus Controller                 | 15    | i2c_piix4  | [BFDC2533BB](<All In One/Hewlett-Packard/20/20-c211la/6F4CC01CA4A6/LINUXMINT-20.3/5.4.0-96-GENERIC/X86_64/BFDC2533BB>) |
| 8086:1c22 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 14    | i2c_i801   | [485E063883](<All In One/Lenovo/C340/C340 10102/B4F39330CA94/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/485E063883>) |
| 8086:9d23 | 103c:84de | Intel            | Sunrise Point-LP SMBus               | 14    | i2c_i801   | [43184FD6BF](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/3E27DCFED7C5/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/43184FD6BF>) |
| 8086:1c22 | 1028:0511 | Intel            | 6 Series/C200 Series Chipset Fami... | 12    | i2c_i801   | [6008FDA2AD](<All In One/Dell/Inspiron/Inspiron One 2320/61122D664D9D/UBUNTU-21.10/5.13.0-23-GENERIC/X86_64/6008FDA2AD>) |
| 8086:1e22 | 1028:0543 | Intel            | 7 Series/C216 Chipset Family SMBu... | 12    | i2c_i801   | [F92FA1F111](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/04BEB2B29F37/CLEAR-LINUX-OS-35190/5.13.13-1070.NATIVE/X86_64/F92FA1F111>) |
| 8086:1e22 | 1028:0548 | Intel            | 7 Series/C216 Chipset Family SMBu... | 12    | i2c_i801   | [6D6980BC69](<All In One/Dell/Inspiron/Inspiron One 2330/CC15798AE672/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/6D6980BC69>) |
| 1022:790b | 103c:8381 | AMD              | FCH SMBus Controller                 | 11    | i2c_pii... | [0DC8027649](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/B4EEA135048F/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/0DC8027649>) |
| 8086:1c22 | 103c:2ac5 | Intel            | 6 Series/C200 Series Chipset Fami... | 11    | i2c_i801   | [DF20701C5E](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/2B14E403FA28/DEBIAN-10/5.10.0-0.BPO.3-AMD64/X86_64/DF20701C5E>) |
| 8086:8c22 | 1028:05a7 | Intel            | 8 Series/C220 Series Chipset Fami... | 11    | i2c_i801   | [ED0DFEF2DF](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/FA6C8EA82464/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/ED0DFEF2DF>) |
| 1022:790b | 103c:8430 | AMD              | FCH SMBus Controller                 | 10    | i2c_piix4  | [56C6D48F6E](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/A2E8399A62AF/ENDEAVOUROS-ROLLING/5.14.2-ARCH1-2/X86_64/56C6D48F6E>) |
| 8086:3a30 | 1025:0266 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 10    | i2c_i801   | [141F5642FC](<All In One/Acer/Aspire/Aspire Z5610/93F4A5EF8D69/LINUXMINT-20.2/5.4.0-96-GENERIC/X86_64/141F5642FC>) |
| 8086:9d23 | 8086:9d23 | Intel            | Sunrise Point-LP SMBus               | 10    | i2c_i801   | [8826665773](<All In One/ASUSTek Computer/ZN240/ZN240IC/B519220D6F37/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/8826665773>) |
| 1002:4385 |           | AMD              | SBx00 SMBus Controller               | 9     | i2c_piix4  | [CDCA9F74F5](<All In One/Dell/Inspiron/Inspiron One 2305/178B94E5C2F7/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/CDCA9F74F5>) |
| 8086:31d4 | 1025:1304 | Intel            | Celeron/Pentium Silver Processor ... | 9     |            | [B7F823BFDA](<All In One/Others/Others/Others/EFF35801EAC2/UBUNTU/5.8.0-14-GENERIC/X86_64/B7F823BFDA>) |
| 8086:8c22 | 1028:05db | Intel            | 8 Series/C220 Series Chipset Fami... | 9     | i2c_i801   | [6B8B0EC7F9](<All In One/Dell/Inspiron/Inspiron 2350/62A6886810DD/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/6B8B0EC7F9>) |
| 8086:9d23 | 1025:1287 | Intel            | Sunrise Point-LP SMBus               | 9     | i2c_i801   | [70014EA10E](<All In One/Acer/Aspire/Aspire C22-865/CAE70310F314/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/70014EA10E>) |
| 8086:a323 | 103c:84ee | Intel            | Cannon Lake PCH SMBus Controller     | 9     | i801_smbus | [2311649D51](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-xa0xxx/3187A1587DA6/LINUXMINT-20.2/5.4.0-90-GENERIC/X86_64/2311649D51>) |
| 8086:1c22 | 104d:907e | Intel            | 6 Series/C200 Series Chipset Fami... | 8     | i2c_i801   | [0451CAEB29](<All In One/Sony/VPCL212/VPCL212FX/01EE677E7F92/UBUNTU-21.10/5.13.0-22-GENERIC/X86_64/0451CAEB29>) |
| 8086:2292 | 103c:81bb | Intel            | Atom/Celeron/Pentium Processor x5... | 8     | i801_smbus | [516F843813](<All In One/Hewlett-Packard/22/22-b009na/2C2C0369DE9C/KALI-2021.4/5.15.0-KALI2-AMD64/X86_64/516F843813>) |
| 8086:3b30 | 17aa:306a | Intel            | 5 Series/3400 Series Chipset SMBu... | 8     | i2c_i801   | [0EF323D23D](<All In One/Lenovo/ThinkCentre/ThinkCentre M90z 5205RQ1/DDABC203DAB8/UBUNTU-20.04/5.8.0-53-GENERIC/X86_64/0EF323D23D>) |
| 1022:780b | 103c:2b3b | AMD              | FCH SMBus Controller                 | 7     | i2c_piix4  | [B3DCCF594C](<All In One/Hewlett-Packard/23/23-r035la/8A9A83560619/ZORIN-16/5.13.0-27-GENERIC/X86_64/B3DCCF594C>) |
| 10de:0752 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] SMBus          | 7     | i2c_nfo... | [04B8123AA5](<All In One/Acer/Aspire/Aspire Z3101/EDA041C04858/UBUNTU-18.04/4.15.0-96-GENERIC/X86_64/04B8123AA5>) |
| 8086:1c22 | 17aa:366c | Intel            | 6 Series/C200 Series Chipset Fami... | 7     | i2c_i801   | [3903A96DE3](<All In One/Lenovo/C540/C540 10110/2B8EE2F234A3/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/3903A96DE3>) |
| 8086:1e22 | 144d:b091 | Intel            | 7 Series/C216 Chipset Family SMBu... | 7     | i2c_i801   | [DD513D338C](<All In One/Samsung Electronics/DP700/DP700A3D-DM700A3D-DB701A3D-DP700A7D/F34D6AA53F0D/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/DD513D338C>) |
| 8086:31d4 | 1854:0308 | Intel            | Celeron/Pentium Silver Processor ... | 7     | i2c_i801   | [F57C7BBE97](<All In One/LG Electronics/22V280/22V280-L.BY31P1/BF6C05A5FCC3/ENDEAVOUROS-ROLLING/5.13.12-ARCH1-1/X86_64/F57C7BBE97>) |
| 8086:8c22 | 103c:18e6 | Intel            | 8 Series/C220 Series Chipset Fami... | 7     | i2c_i801   | [F8D1E58D06](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G1 AiO/44D1B0C864ED/LINUXMINT-18.3/4.15.0-142-GENERIC/X86_64/F8D1E58D06>) |
| 8086:8ca2 | 8086:7270 | Intel            | 9 Series Chipset Family SMBus Con... | 7     | i2c_i801   | [BC313CE031](<All In One/Apple/iMac16/iMac16,2/224B9F366AD7/ENDEAVOUROS-ROLLING/5.15.7-ARCH1-1/X86_64/BC313CE031>) |
| 8086:9d23 | 1028:0754 | Intel            | Sunrise Point-LP SMBus               | 7     | i2c_i801   | [00C297540D](<All In One/Dell/Inspiron/Inspiron 3464 AIO/31AD17DDDC01/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/00C297540D>) |
| 8086:a123 | 1028:06c5 | Intel            | 100 Series/C230 Series Chipset Fa... | 7     | i2c_i801   | [0DCB1B8C3C](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/34CACCC6D3D6/UBUNTU-20.04/5.13.0-32-GENERIC/X86_64/0DCB1B8C3C>) |
| 1022:790b | 103c:86f3 | AMD              | FCH SMBus Controller                 | 6     | i2c_piix4  | [7DE0381DB8](<All In One/Hewlett-Packard/205/205 G4 22 All-in-One PC/F158F87A803B/SLACKWARE-15.0/5.15.27/X86_64/7DE0381DB8>) |
| 8086:0f12 | 17aa:3695 | Intel            | Atom Processor E3800/CE2700 Serie... | 6     | i2c_i801   | [3E79CADCEA](<All In One/Lenovo/C260/C260 10160/A6FBDDCB0193/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/3E79CADCEA>) |
| 8086:1e22 | 104d:9097 | Intel            | 7 Series/C216 Chipset Family SMBu... | 6     | i2c_i801   | [4D477A343A](<All In One/Sony/SVL2411/SVL24117FLB/B337A07B7653/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/4D477A343A>) |
| 8086:2292 | 1028:06cc | Intel            | Atom/Celeron/Pentium Processor x5... | 6     | i2c_i801   | [3AC5DA5F93](<All In One/Dell/Inspiron/Inspiron 20-3052/E44132686405/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/3AC5DA5F93>) |
| 8086:31d4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 6     | i801_smbus | [10E8B5B5BD](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/10E8B5B5BD>) |
| 8086:8c22 | 1028:0623 | Intel            | 8 Series/C220 Series Chipset Fami... | 6     | i2c_i801   | [FE22676441](<All In One/Dell/OptiPlex/OptiPlex 3030 AIO/F73EB67F5BAB/FEDORA-35/5.14.14-300.FC35.X86_64/X86_64/FE22676441>) |
| 8086:9da3 | 1043:17b1 | Intel            | Cannon Point-LP SMBus Controller     | 6     |            | [60C6C7EA7C](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/3602C27EA430/ENDLESS-3.9.6/5.8.0-14-GENERIC/X86_64/60C6C7EA7C>) |
| 8086:a123 | 103c:81b7 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     | i2c_i801   | [35AB480926](<All In One/Hewlett-Packard/27/27-a154ng/BDD291411CF6/ARCH/5.16.10-ARCH1-1/X86_64/35AB480926>) |
| 8086:a123 | 103c:82dc | Intel            | 100 Series/C230 Series Chipset Fa... | 6     | i2c_i801   | [E3A85B9AAF](<All In One/Hewlett-Packard/27/27-a271ny/689111B5E631/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E3A85B9AAF>) |
| 1022:780b | 17aa:36ab | AMD              | FCH SMBus Controller                 | 5     | i2c_piix4  | [AA6E9BA312](<All In One/Lenovo/C40-05/C40-05 F0B5002NCF/770FDA610B82/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/AA6E9BA312>) |
| 8086:0f12 |           | Intel            | Atom Processor E3800/CE2700 Serie... | 5     | i2c_i801   | [29A6B45091](<All In One/Acer/Aspire/Aspire Z1-601/0EFA289080ED/LUBUNTU-18.04/4.15.0-151-GENERIC/I686/29A6B45091>) |
| 8086:0f12 | 1028:0690 | Intel            | Atom Processor E3800/CE2700 Serie... | 5     | i2c_i801   | [F96E26BB9A](<All In One/Dell/Inspiron/Inspiron 20 Model 3043/16F41C0EA91A/ZORIN-16/5.13.0-30-GENERIC/X86_64/F96E26BB9A>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:284b | 106b:00a0 | Intel            | 82801H (ICH8 Family) HD Audio Con... | 108   | snd_hda... | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 8086:1c20 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 103   | snd_hda... | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 10de:0ac0 | 10de:cb79 | Nvidia           | MCP79 High Definition Audio          | 88    | snd_hda... | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 1002:aa90 | 106b:aa90 | AMD              | Turks HDMI Audio [Radeon HD 6500/... | 75    | snd_hda... | [FE2249C404](<All In One/Apple/iMac12/iMac12,1/825F0CF6DCAC/ZORIN-16/5.13.0-30-GENERIC/X86_64/FE2249C404>) |
| 8086:a170 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 57    | snd_hda... | [436904EAE3](<All In One/Apple/iMac17/iMac17,1/7E034427C03F/DEBIAN-11/5.10.0-12-AMD64/X86_64/436904EAE3>) |
| 8086:3b56 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset High... | 56    | snd_hda... | [99D7E82DF9](<All In One/Apple/iMac11/iMac11,2/9D11563CF50D/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/99D7E82DF9>) |
| 8086:8c20 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset High... | 46    | snd_hda... | [7757BE603C](<All In One/Apple/iMac14/iMac14,2/3F4033EA2574/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/7757BE603C>) |
| 1002:aae0 | 1002:aae0 | AMD              | Baffin HDMI/DP Audio [Radeon RX 5... | 42    | snd_hda... | [841AB4FFE2](<All In One/Apple/iMac18/iMac18,2/6AAE34125DB5/FEDORA-36/5.17.0-0.RC5.102.FC36.X86_64/X86_64/841AB4FFE2>) |
| 1002:aa38 | 106b:aa38 | AMD              | RV710/730 HDMI Audio [Radeon HD 4... | 34    | snd_hda... | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 8086:1e20 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family High... | 32    | snd_hda... | [435548337A](<All In One/Apple/iMac13/iMac13,1/BB29D11F01EF/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/435548337A>) |
| 8086:a348 | 8086:7270 | Intel            | Cannon Lake PCH cAVS                 | 32    | snd_hda... | [5E0CEEF0D1](<All In One/Apple/iMac19/iMac19,2/B4B5423C68DB/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/5E0CEEF0D1>) |
| 1002:aaf0 | 1002:aaf0 | AMD              | Ellesmere HDMI Audio [Radeon RX 4... | 27    | snd_hda... | [6248556DD7](<All In One/Apple/iMac19/iMac19,1/926D486F8F2F/POP!_OS-20.04/5.13.0-7620-GENERIC/X86_64/6248556DD7>) |
| 1002:aa88 | 106b:aa88 | AMD              | Barts HDMI Audio [Radeon HD 6790/... | 26    | snd_hda... | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 8086:27d8 | 8384:7680 | Intel            | NM10/ICH7 Family High Definition ... | 21    | snd_hda... | [261E6C0463](<All In One/Apple/iMac5/iMac5,1/F72BF7BFE069/LMDE-5/5.10.0-11-686/I686/261E6C0463>) |
| 10de:0e1b | 106b:0109 | Nvidia           | GK107 HDMI Audio Controller          | 17    | snd_hda... | [435548337A](<All In One/Apple/iMac13/iMac13,1/BB29D11F01EF/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/435548337A>) |
| 1002:aa58 | 106b:aa58 | AMD              | Juniper HDMI Audio [Radeon HD 570... | 16    | snd_hda... | [48688703FE](<All In One/Apple/iMac11/iMac11,3/720CB377D1CB/UBUNTU-20.04/5.8.0-43-GENERIC/X86_64/48688703FE>) |
| 1002:9840 | 103c:8245 | AMD              | Kabini HDMI/DP Audio                 | 15    | snd_hda... | [BFDC2533BB](<All In One/Hewlett-Packard/20/20-c211la/6F4CC01CA4A6/LINUXMINT-20.3/5.4.0-96-GENERIC/X86_64/BFDC2533BB>) |
| 1002:aa30 | 106b:aa30 | AMD              | RV770 HDMI Audio [Radeon HD 4850/... | 15    | snd_hda... | [F9560B6FE3](<All In One/Apple/iMac11/iMac11,1/9FF8106A1F94/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/F9560B6FE3>) |
| 1022:780d | 103c:8245 | AMD              | FCH Azalia Controller                | 15    | snd_hda... | [BFDC2533BB](<All In One/Hewlett-Packard/20/20-c211la/6F4CC01CA4A6/LINUXMINT-20.3/5.4.0-96-GENERIC/X86_64/BFDC2533BB>) |
| 1002:aab0 | 0000:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 14    | snd_hda... | [436904EAE3](<All In One/Apple/iMac17/iMac17,1/7E034427C03F/DEBIAN-11/5.10.0-12-AMD64/X86_64/436904EAE3>) |
| 8086:1c20 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 14    | snd_hda... | [485E063883](<All In One/Lenovo/C340/C340 10102/B4F39330CA94/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/485E063883>) |
| 8086:9d71 | 103c:84de | Intel            | Sunrise Point-LP HD Audio            | 14    | snd_hda... | [43184FD6BF](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/3E27DCFED7C5/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/43184FD6BF>) |
| 8086:0d0c | 106b:0122 | Intel            | Crystal Well HD Audio Controller     | 13    | snd_hda... | [9AEE4C877D](<All In One/Apple/iMac14/iMac14,1/50E077CF962C/MANJARO-21.2.0/5.13.19-2-MANJARO/X86_64/9AEE4C877D>) |
| 10de:0e0a |           | Nvidia           | GK104 HDMI Audio Controller          | 12    | snd_hda... | [7757BE603C](<All In One/Apple/iMac14/iMac14,2/3F4033EA2574/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/7757BE603C>) |
| 10de:0e1b |           | Nvidia           | GK107 HDMI Audio Controller          | 12    | snd_hda... | [275D33A826](<All In One/Apple/iMac14/iMac14,2/431D98DD9113/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/275D33A826>) |
| 8086:1c20 | 1028:0511 | Intel            | 6 Series/C200 Series Chipset Fami... | 12    | snd_hda... | [6008FDA2AD](<All In One/Dell/Inspiron/Inspiron One 2320/61122D664D9D/UBUNTU-21.10/5.13.0-23-GENERIC/X86_64/6008FDA2AD>) |
| 8086:1e20 | 1028:0543 | Intel            | 7 Series/C216 Chipset Family High... | 12    | snd_hda... | [F92FA1F111](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/04BEB2B29F37/CLEAR-LINUX-OS-35190/5.13.13-1070.NATIVE/X86_64/F92FA1F111>) |
| 8086:1e20 | 1028:0548 | Intel            | 7 Series/C216 Chipset Family High... | 12    | snd_hda... | [6D6980BC69](<All In One/Dell/Inspiron/Inspiron One 2330/CC15798AE672/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/6D6980BC69>) |
| 1002:15b3 | 103c:8381 | AMD              | High Definition Audio Controller     | 11    | snd_hda... | [0DC8027649](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/B4EEA135048F/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/0DC8027649>) |
| 1022:157a | 103c:8381 | AMD              | Family 15h (Models 60h-6fh) Audio... | 11    | snd_hda... | [0DC8027649](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/B4EEA135048F/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/0DC8027649>) |
| 8086:0c0c | 1028:05a7 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 11    | snd_hda... | [ED0DFEF2DF](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/FA6C8EA82464/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/ED0DFEF2DF>) |
| 8086:1c20 | 103c:2ac5 | Intel            | 6 Series/C200 Series Chipset Fami... | 11    | snd_hda... | [DF20701C5E](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/2B14E403FA28/DEBIAN-10/5.10.0-0.BPO.3-AMD64/X86_64/DF20701C5E>) |
| 8086:8c20 | 1028:05a7 | Intel            | 8 Series/C220 Series Chipset High... | 11    | snd_hda... | [ED0DFEF2DF](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/FA6C8EA82464/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/ED0DFEF2DF>) |
| 1002:15b3 | 103c:8430 | AMD              | High Definition Audio Controller     | 10    | snd_hda... | [56C6D48F6E](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/A2E8399A62AF/ENDEAVOUROS-ROLLING/5.14.2-ARCH1-2/X86_64/56C6D48F6E>) |
| 1022:157a | 103c:8430 | AMD              | Family 15h (Models 60h-6fh) Audio... | 10    | snd_hda... | [56C6D48F6E](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/A2E8399A62AF/ENDEAVOUROS-ROLLING/5.14.2-ARCH1-2/X86_64/56C6D48F6E>) |
| 8086:3a3e | 1025:0266 | Intel            | 82801JI (ICH10 Family) HD Audio C... | 10    | snd_hda... | [141F5642FC](<All In One/Acer/Aspire/Aspire Z5610/93F4A5EF8D69/LINUXMINT-20.2/5.4.0-96-GENERIC/X86_64/141F5642FC>) |
| 1002:aa60 | 106b:aa60 | AMD              | Redwood HDMI Audio [Radeon HD 500... | 9     | snd_hda... | [99D7E82DF9](<All In One/Apple/iMac11/iMac11,2/9D11563CF50D/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/99D7E82DF9>) |
| 8086:0c0c | 1028:05db | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 9     | snd_hda... | [6B8B0EC7F9](<All In One/Dell/Inspiron/Inspiron 2350/62A6886810DD/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/6B8B0EC7F9>) |
| 8086:0c0c | 8086:2010 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 9     | snd_hda... | [D0194FC092](<All In One/Lenovo/B50-30/B50-30 F0AU001YUS/6D591A8B8CEF/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/D0194FC092>) |
| 8086:3198 | 1025:1130 | Intel            | Celeron/Pentium Silver Processor ... | 9     | snd_hda... | [B7F823BFDA](<All In One/Others/Others/Others/EFF35801EAC2/UBUNTU/5.8.0-14-GENERIC/X86_64/B7F823BFDA>) |
| 8086:8c20 | 1028:05db | Intel            | 8 Series/C220 Series Chipset High... | 9     | snd_hda... | [6B8B0EC7F9](<All In One/Dell/Inspiron/Inspiron 2350/62A6886810DD/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/6B8B0EC7F9>) |
| 8086:9d71 | 1025:1287 | Intel            | Sunrise Point-LP HD Audio            | 9     | snd_hda... | [70014EA10E](<All In One/Acer/Aspire/Aspire C22-865/CAE70310F314/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/70014EA10E>) |
| 8086:a348 | 103c:84ee | Intel            | Cannon Lake PCH cAVS                 | 9     | snd_hda... | [2311649D51](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-xa0xxx/3187A1587DA6/LINUXMINT-20.2/5.4.0-90-GENERIC/X86_64/2311649D51>) |
| 1002:aac0 | 0000:aac0 | AMD              | Tobago HDMI Audio [Radeon R7 360 ... | 8     | snd_hda... | [11BF29BDD1](<All In One/Apple/iMac17/iMac17,1/712E1D65BC52/ZORIN-16/5.11.0-46-GENERIC/X86_64/11BF29BDD1>) |
| 10de:0bea | 17aa:365e | Nvidia           | GF108 High Definition Audio Contr... | 8     | snd_hda... | [968B139684](<All In One/Lenovo/C440/C440 10104/DBCDF802DB54/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/968B139684>) |
| 8086:1c20 | 104d:907e | Intel            | 6 Series/C200 Series Chipset Fami... | 8     | snd_hda... | [0451CAEB29](<All In One/Sony/VPCL212/VPCL212FX/01EE677E7F92/UBUNTU-21.10/5.13.0-22-GENERIC/X86_64/0451CAEB29>) |
| 8086:2284 | 103c:81bb | Intel            | Atom/Celeron/Pentium Processor x5... | 8     | snd_hda... | [516F843813](<All In One/Hewlett-Packard/22/22-b009na/2C2C0369DE9C/KALI-2021.4/5.15.0-KALI2-AMD64/X86_64/516F843813>) |
| 8086:3b56 | 17aa:306a | Intel            | 5 Series/3400 Series Chipset High... | 8     | snd_hda... | [0EF323D23D](<All In One/Lenovo/ThinkCentre/ThinkCentre M90z 5205RQ1/DDABC203DAB8/UBUNTU-20.04/5.8.0-53-GENERIC/X86_64/0EF323D23D>) |
| 1002:9840 | 103c:2b3b | AMD              | Kabini HDMI/DP Audio                 | 7     | snd_hda... | [B3DCCF594C](<All In One/Hewlett-Packard/23/23-r035la/8A9A83560619/ZORIN-16/5.13.0-27-GENERIC/X86_64/B3DCCF594C>) |
| 1022:780d | 103c:2b3b | AMD              | FCH Azalia Controller                | 7     | snd_hda... | [B3DCCF594C](<All In One/Hewlett-Packard/23/23-r035la/8A9A83560619/ZORIN-16/5.13.0-27-GENERIC/X86_64/B3DCCF594C>) |

### Storage (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1217:8331 | 1bcf:a013 | O2 Micro         | O2 Flash Memory Card                 | 2     |            | [1494683BB9](<All In One/NEC Computers/PC-VN770/PC-VN770DS3ER/18CEF0AA43DB/UBUNTU-20.04/5.8.0-48-GENERIC/X86_64/1494683BB9>) |
| 1106:401a | 17aa:3603 | VIA Technologies | VIA Card Reader Host Controller      | 1     |            | [8399296D51](<All In One/Lenovo/IdeaCentre/IdeaCentre B305 10052/A8184A7A8382/UBUNTU-20.04/5.8.0-55-GENERIC/X86_64/8399296D51>) |
| 1106:401a | 17aa:3608 | VIA Technologies | VIA Card Reader Host Controller      | 1     |            | [69574214D7](<All In One/Lenovo/IdeaCentre/IdeaCentre A700 10050/51968677EC4C/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/69574214D7>) |
| 1217:8130 | 17aa:3068 | O2 Micro         | Integrated MS/MSPRO/xD Controller    | 1     |            | [27E7D42D53](<All In One/Lenovo/xxxx/xxxx/18DB28A21724/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/27E7D42D53>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c02 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 100   | ahci       | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 8086:2829 | 106b:00a0 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) SATA ... | 94    | ahci       | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 10de:0ab9 | 10de:cb79 | Nvidia           | MCP79 AHCI Controller                | 82    | ahci       | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 8086:a102 | 8086:7270 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 57    | ahci       | [436904EAE3](<All In One/Apple/iMac17/iMac17,1/7E034427C03F/DEBIAN-11/5.10.0-12-AMD64/X86_64/436904EAE3>) |
| 8086:3b22 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset 6 po... | 53    | ahci       | [99D7E82DF9](<All In One/Apple/iMac11/iMac11,2/9D11563CF50D/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/99D7E82DF9>) |
| 8086:1e02 | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 32    | ahci       | [435548337A](<All In One/Apple/iMac13/iMac13,1/BB29D11F01EF/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/435548337A>) |
| 8086:a352 | 8086:7270 | Intel            | Cannon Lake PCH SATA AHCI Controller | 32    | ahci       | [5E0CEEF0D1](<All In One/Apple/iMac19/iMac19,2/B4B5423C68DB/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/5E0CEEF0D1>) |
| 8086:8c02 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 29    | ahci       | [7757BE603C](<All In One/Apple/iMac14/iMac14,2/3F4033EA2574/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/7757BE603C>) |
| 1022:7801 | 103c:8245 | AMD              | FCH SATA Controller [AHCI mode]      | 15    | ahci       | [BFDC2533BB](<All In One/Hewlett-Packard/20/20-c211la/6F4CC01CA4A6/LINUXMINT-20.3/5.4.0-96-GENERIC/X86_64/BFDC2533BB>) |
| 144d:a801 | 144d:a801 | Samsung Elect... | Electronics SATA controller          | 14    | ahci       | [C0830F8E91](<All In One/Apple/iMac17/iMac17,1/1D658E93D47D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C0830F8E91>) |
| 8086:1c02 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 13    | ahci       | [485E063883](<All In One/Lenovo/C340/C340 10102/B4F39330CA94/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/485E063883>) |
| 8086:8c03 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 13    | ahci       | [9AEE4C877D](<All In One/Apple/iMac14/iMac14,1/50E077CF962C/MANJARO-21.2.0/5.13.19-2-MANJARO/X86_64/9AEE4C877D>) |
| 8086:1c02 | 1028:0511 | Intel            | 6 Series/C200 Series Chipset Fami... | 12    | ahci       | [6008FDA2AD](<All In One/Dell/Inspiron/Inspiron One 2320/61122D664D9D/UBUNTU-21.10/5.13.0-23-GENERIC/X86_64/6008FDA2AD>) |
| 8086:1e02 | 1028:0543 | Intel            | 7 Series/C210 Series Chipset Fami... | 12    | ahci       | [F92FA1F111](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/04BEB2B29F37/CLEAR-LINUX-OS-35190/5.13.13-1070.NATIVE/X86_64/F92FA1F111>) |
| 8086:1c02 | 103c:2ac5 | Intel            | 6 Series/C200 Series Chipset Fami... | 11    | ahci       | [DF20701C5E](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/2B14E403FA28/DEBIAN-10/5.10.0-0.BPO.3-AMD64/X86_64/DF20701C5E>) |
| 8086:1e02 | 1028:0548 | Intel            | 7 Series/C210 Series Chipset Fami... | 11    | ahci       | [6D6980BC69](<All In One/Dell/Inspiron/Inspiron One 2330/CC15798AE672/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/6D6980BC69>) |
| 1022:7901 | 103c:8381 | AMD              | FCH SATA Controller [AHCI mode]      | 10    | ahci       | [0DC8027649](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/B4EEA135048F/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/0DC8027649>) |
| 1022:7901 | 103c:8430 | AMD              | FCH SATA Controller [AHCI mode]      | 10    | ahci       | [56C6D48F6E](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/A2E8399A62AF/ENDEAVOUROS-ROLLING/5.14.2-ARCH1-2/X86_64/56C6D48F6E>) |
| 8086:3a22 | 1025:0266 | Intel            | 82801JI (ICH10 Family) SATA AHCI ... | 10    | ahci       | [141F5642FC](<All In One/Acer/Aspire/Aspire Z5610/93F4A5EF8D69/LINUXMINT-20.2/5.4.0-96-GENERIC/X86_64/141F5642FC>) |
| 8086:9d03 | 103c:84de | Intel            | Sunrise Point-LP SATA Controller ... | 10    | ahci       | [43184FD6BF](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/3E27DCFED7C5/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/43184FD6BF>) |
| 8086:9d03 | 8086:9d03 | Intel            | Sunrise Point-LP SATA Controller ... | 10    | ahci       | [8826665773](<All In One/ASUSTek Computer/ZN240/ZN240IC/B519220D6F37/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/8826665773>) |
| 1b4b:9183 | 1b4b:9183 | Marvell Techn... | 88SS9183 PCIe SSD Controller         | 9     | ahci       | [F4ADB105A4](<All In One/Apple/iMac15/iMac15,1/5F6A7F51EB9F/UBUNTU-21.10/5.13.0-20-GENERIC/X86_64/F4ADB105A4>) |
| 8086:31e3 | 1025:1304 | Intel            | Celeron/Pentium Silver Processor ... | 9     | ahci       | [B7F823BFDA](<All In One/Others/Others/Others/EFF35801EAC2/UBUNTU/5.8.0-14-GENERIC/X86_64/B7F823BFDA>) |
| 8086:9d03 | 1025:1287 | Intel            | Sunrise Point-LP SATA Controller ... | 9     | ahci       | [70014EA10E](<All In One/Acer/Aspire/Aspire C22-865/CAE70310F314/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/70014EA10E>) |
| 8086:a352 | 103c:84ee | Intel            | Cannon Lake PCH SATA AHCI Controller | 9     | ahci       | [2311649D51](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-xa0xxx/3187A1587DA6/LINUXMINT-20.2/5.4.0-90-GENERIC/X86_64/2311649D51>) |
| 8086:1c03 | 104d:907e | Intel            | 6 Series/C200 Series Chipset Fami... | 8     | ahci       | [0451CAEB29](<All In One/Sony/VPCL212/VPCL212FX/01EE677E7F92/UBUNTU-21.10/5.13.0-22-GENERIC/X86_64/0451CAEB29>) |
| 8086:22a3 | 103c:81bb | Intel            | Atom/Celeron/Pentium Processor x5... | 8     | ahci       | [516F843813](<All In One/Hewlett-Packard/22/22-b009na/2C2C0369DE9C/KALI-2021.4/5.15.0-KALI2-AMD64/X86_64/516F843813>) |
| 8086:8c03 | 1028:05db | Intel            | 8 Series/C220 Series Chipset Fami... | 8     | ahci       | [6B8B0EC7F9](<All In One/Dell/Inspiron/Inspiron 2350/62A6886810DD/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/6B8B0EC7F9>) |
| 1022:7801 | 103c:2b3b | AMD              | FCH SATA Controller [AHCI mode]      | 7     | ahci       | [B3DCCF594C](<All In One/Hewlett-Packard/23/23-r035la/8A9A83560619/ZORIN-16/5.13.0-27-GENERIC/X86_64/B3DCCF594C>) |
| 10de:0ad4 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] AHCI Contro... | 7     | ahci       | [04B8123AA5](<All In One/Acer/Aspire/Aspire Z3101/EDA041C04858/UBUNTU-18.04/4.15.0-96-GENERIC/X86_64/04B8123AA5>) |
| 8086:1c02 | 17aa:366c | Intel            | 6 Series/C200 Series Chipset Fami... | 7     | ahci       | [3903A96DE3](<All In One/Lenovo/C540/C540 10110/2B8EE2F234A3/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/3903A96DE3>) |
| 8086:1e02 | 144d:b091 | Intel            | 7 Series/C210 Series Chipset Fami... | 7     | ahci       | [DD513D338C](<All In One/Samsung Electronics/DP700/DP700A3D-DM700A3D-DB701A3D-DP700A7D/F34D6AA53F0D/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/DD513D338C>) |
| 8086:31e3 | 1854:0308 | Intel            | Celeron/Pentium Silver Processor ... | 7     | ahci       | [F57C7BBE97](<All In One/LG Electronics/22V280/22V280-L.BY31P1/BF6C05A5FCC3/ENDEAVOUROS-ROLLING/5.13.12-ARCH1-1/X86_64/F57C7BBE97>) |
| 8086:3b22 | 17aa:306a | Intel            | 5 Series/3400 Series Chipset 6 po... | 7     | ahci       | [0EF323D23D](<All In One/Lenovo/ThinkCentre/ThinkCentre M90z 5205RQ1/DDABC203DAB8/UBUNTU-20.04/5.8.0-53-GENERIC/X86_64/0EF323D23D>) |
| 8086:8c02 | 103c:18e6 | Intel            | 8 Series/C220 Series Chipset Fami... | 7     | ahci       | [F8D1E58D06](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G1 AiO/44D1B0C864ED/LINUXMINT-18.3/4.15.0-142-GENERIC/X86_64/F8D1E58D06>) |
| 8086:9d03 | 1028:0754 | Intel            | Sunrise Point-LP SATA Controller ... | 7     | ahci       | [00C297540D](<All In One/Dell/Inspiron/Inspiron 3464 AIO/31AD17DDDC01/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/00C297540D>) |
| 1022:43b7 | 1b21:1062 | AMD              | 300 Series Chipset SATA Controller   | 6     | ahci       | [81AF87F00C](<All In One/Dell/Inspiron/Inspiron 27 7775/D1240D4484D8/ELEMENTARY-5.1.7/5.4.0-89-GENERIC/X86_64/81AF87F00C>) |
| 1022:7901 | 103c:86f3 | AMD              | FCH SATA Controller [AHCI mode]      | 6     | ahci       | [7DE0381DB8](<All In One/Hewlett-Packard/205/205 G4 22 All-in-One PC/F158F87A803B/SLACKWARE-15.0/5.15.27/X86_64/7DE0381DB8>) |
| 8086:0f23 | 17aa:3695 | Intel            | Atom Processor E3800 Series SATA ... | 6     | ahci       | [3E79CADCEA](<All In One/Lenovo/C260/C260 10160/A6FBDDCB0193/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/3E79CADCEA>) |
| 8086:1e03 | 104d:9097 | Intel            | 7 Series Chipset Family 6-port SA... | 6     | ahci       | [4D477A343A](<All In One/Sony/SVL2411/SVL24117FLB/B337A07B7653/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/4D477A343A>) |
| 8086:22a3 | 1028:06cc | Intel            | Atom/Celeron/Pentium Processor x5... | 6     | ahci       | [3AC5DA5F93](<All In One/Dell/Inspiron/Inspiron 20-3052/E44132686405/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/3AC5DA5F93>) |
| 8086:31e3 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 6     | ahci       | [10E8B5B5BD](<All In One/CSL-Computer/UNITY/UNITY F27B/9F839E737A91/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/10E8B5B5BD>) |
| 8086:8c02 | 1028:0623 | Intel            | 8 Series/C220 Series Chipset Fami... | 6     | ahci       | [FE22676441](<All In One/Dell/OptiPlex/OptiPlex 3030 AIO/F73EB67F5BAB/FEDORA-35/5.14.14-300.FC35.X86_64/X86_64/FE22676441>) |
| 8086:8c83 | 8086:7270 | Intel            | 9 Series Chipset Family SATA Cont... | 6     | ahci       | [7B3EFC8CD8](<All In One/Apple/iMac16/iMac16,2/10693C2A6D97/ELEMENTARY-6/5.11.0-41-GENERIC/X86_64/7B3EFC8CD8>) |
| 8086:a102 | 103c:81b7 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 6     | ahci       | [35AB480926](<All In One/Hewlett-Packard/27/27-a154ng/BDD291411CF6/ARCH/5.16.10-ARCH1-1/X86_64/35AB480926>) |
| 8086:a102 | 103c:82dc | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 6     | ahci       | [E3A85B9AAF](<All In One/Hewlett-Packard/27/27-a271ny/689111B5E631/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E3A85B9AAF>) |
| 1002:4391 | 1028:0479 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 5     | ahci       | [CDCA9F74F5](<All In One/Dell/Inspiron/Inspiron One 2305/178B94E5C2F7/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/CDCA9F74F5>) |
| 1022:7801 | 17aa:36ab | AMD              | FCH SATA Controller [AHCI mode]      | 5     | ahci       | [AA6E9BA312](<All In One/Lenovo/C40-05/C40-05 F0B5002NCF/770FDA610B82/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/AA6E9BA312>) |
| 1022:7901 | 1022:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 5     | ahci       | [8259FB58CE](<All In One/iRU/J/J2335/CF1EEDC28C45/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/8259FB58CE>) |
| 8086:0f23 | 1028:0690 | Intel            | Atom Processor E3800 Series SATA ... | 5     | ahci       | [F96E26BB9A](<All In One/Dell/Inspiron/Inspiron 20 Model 3043/16F41C0EA91A/ZORIN-16/5.13.0-30-GENERIC/X86_64/F96E26BB9A>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2850 | 106b:00a0 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) IDE C... | 108   | pata_acpi  | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 8086:27df | 8086:7270 | Intel            | 82801G (ICH7 Family) IDE Controller  | 23    | pata_acpi  | [261E6C0463](<All In One/Apple/iMac5/iMac5,1/F72BF7BFE069/LMDE-5/5.10.0-11-686/I686/261E6C0463>) |
| 8086:27c4 | 8086:7270 | Intel            | 82801GBM/GHM (ICH7-M Family) SATA... | 22    | pata_acpi  | [261E6C0463](<All In One/Apple/iMac5/iMac5,1/F72BF7BFE069/LMDE-5/5.10.0-11-686/I686/261E6C0463>) |
| 8086:2828 | 106b:00a0 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) SATA ... | 15    | pata_acpi  | [285B0FC2FD](<All In One/Apple/iMac8/iMac8,1/7177C4468C98/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/285B0FC2FD>) |
| 1002:439c | 1002:439c | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 7     | pata_at... | [86CD4A72D1](<All In One/ASUSTek Computer/ET2010/ET2010AG/03DD34D94A32/XUBUNTU-21.04/5.11.0-37-GENERIC/X86_64/86CD4A72D1>) |
| 10de:0ab5 | 10de:cb79 | Nvidia           | MCP79 SATA Controller                | 6     | ahci, p... | [9B86C3FB93](<All In One/Apple/iMac10/iMac10,1/8FA5435E7AA6/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/9B86C3FB93>) |
| 1002:439c | 17aa:3629 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 4     | pata_at... | [7D3A0A3AD9](<All In One/Lenovo/C/C325/DC976463CB3E/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/7D3A0A3AD9>) |
| 8086:27c0 | 17aa:3602 | Intel            | NM10/ICH7 Family SATA Controller ... | 4     | ata_pii... | [C25FDFE643](<All In One/Lenovo/IdeaCentre/IdeaCentre B300 10051/20208F91C976/ENDLESS-3.8.6/5.4.0-42-GENERIC/X86_64/C25FDFE643>) |
| 8086:27c0 | 17aa:3610 | Intel            | NM10/ICH7 Family SATA Controller ... | 4     | ata_pii... | [5D8EF57728](<All In One/Lenovo/C/C200/3278BC0AB6A5/ROSA-2016.1/4.15.0-DESKTOP-94.1ROSA-I586/I686/5D8EF57728>) |
| 8086:3b20 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset 4 po... | 4     | ata_piix   | [4384DEED19](<All In One/Apple/iMac11/iMac11,2/64489F9C6F44/ZORIN-16/5.11.0-43-GENERIC/X86_64/4384DEED19>) |
| 8086:1c00 | 1019:0777 | Intel            | 6 Series/C200 Series Chipset Fami... | 3     | ata_piix   | [0D7E8C7568](<All In One/AIO/H61/H61H-G11/80341B910781/ROSA-12.2/5.10.71-GENERIC-1ROSA2021.1-X86_64/X86_64/0D7E8C7568>) |
| 8086:1c00 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 3     | pata_acpi  | [E139B75008](<All In One/Apple/iMac12/iMac12,1/0A552597D867/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/E139B75008>) |
| 8086:1c08 | 1019:0777 | Intel            | 6 Series/C200 Series Chipset Fami... | 3     | ata_piix   | [0D7E8C7568](<All In One/AIO/H61/H61H-G11/80341B910781/ROSA-12.2/5.10.71-GENERIC-1ROSA2021.1-X86_64/X86_64/0D7E8C7568>) |
| 8086:3a20 | 104d:9060 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 3     | ata_pii... | [05CFF66AC2](<All In One/Sony/VPCL11/VPCL11M1E/93DA71AEEC1E/UBUNTU-19.04/5.0.0-27-GENERIC/X86_64/05CFF66AC2>) |
| 8086:1c01 | 1bcf:a013 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | pata_acpi  | [1494683BB9](<All In One/NEC Computers/PC-VN770/PC-VN770DS3ER/18CEF0AA43DB/UBUNTU-20.04/5.8.0-48-GENERIC/X86_64/1494683BB9>) |
| 8086:1c3c | 103c:3561 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | ata_gen... | [5FF1D7A72E](<All In One/Hewlett-Packard/Z1/Z1 Workstation/4089A5726DF1/FEDORA-35/5.14.18-300.FC35.X86_64/X86_64/5FF1D7A72E>) |
| 8086:1e01 | 17aa:3671 | Intel            | 7 Series Chipset Family 4-port SA... | 2     | ata_pii... | [906A62D75E](<All In One/Lenovo/C240/C240 10113/52E2D6BDB71D/UBUNTU-16.04/4.15.0-55-GENERIC/I686/906A62D75E>) |
| 8086:1e09 | 17aa:3671 | Intel            | 7 Series Chipset Family 2-port SA... | 2     | ata_pii... | [906A62D75E](<All In One/Lenovo/C240/C240 10113/52E2D6BDB71D/UBUNTU-16.04/4.15.0-55-GENERIC/I686/906A62D75E>) |
| 8086:27c0 | 1462:a912 | Intel            | NM10/ICH7 Family SATA Controller ... | 2     | pata_acpi  | [B8B4472592](<All In One/MSI/MS-A/MS-A912/F92BE636D295/DEBIAN-10/4.8.0-2-AMD64/X86_64/B8B4472592>) |
| 8086:27c4 | 1025:025a | Intel            | 82801GBM/GHM (ICH7-M Family) SATA... | 2     | pata_acpi  | [CA89C2F311](<All In One/eMachines/EZ/EZ1600/E4B9D799E916/UBUNTU-MATE-18.04/5.4.0-65-GENERIC/I686/CA89C2F311>) |
| 8086:3a20 | 104d:9043 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 2     | pata_acpi  | [AFA509714D](<All In One/Sony/VGC-LN52/VGC-LN52JGB/54F15FF48E03/UBUNTU-20.04/5.8.0-54-GENERIC/X86_64/AFA509714D>) |
| 8086:3a20 | 104d:9044 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 2     | ata_piix   | [EB74857893](<All In One/Sony/VGC-JS210/VGC-JS210J/8B88CB56EBD6/ENDLESS-3.8.6/5.4.0-42-GENERIC/X86_64/EB74857893>) |
| 8086:3b28 | 17aa:360e | Intel            | 5 Series/3400 Series Chipset 4 po... | 2     | ata_piix   | [8F25ED4108](<All In One/Lenovo/IdeaCentre/IdeaCentre A310 10056/1F51DDDCDF1C/LINUXMINT-19.3/5.4.0-77-GENERIC/X86_64/8F25ED4108>) |
| 8086:8c00 | 1b0a:0183 | Intel            | 8 Series/C220 Series Chipset Fami... | 2     | ata_pii... | [78D39E18EF](<All In One/Pegatron/H81/H81-P1/1DBAFEC13877/UBUNTU-18.04/4.15.0-43-GENERIC/X86_64/78D39E18EF>) |
| 8086:8c08 | 1b0a:0183 | Intel            | 8 Series/C220 Series Chipset Fami... | 2     | ata_pii... | [78D39E18EF](<All In One/Pegatron/H81/H81-P1/1DBAFEC13877/UBUNTU-18.04/4.15.0-43-GENERIC/X86_64/78D39E18EF>) |
| 1002:438c | 1033:886f | AMD              | SB600 IDE                            | 1     | pata_at... | [86771347FB](<All In One/NEC Computers/PC-GV58/PC-GV58ZYCAA/96538F2FC249/UBUNTU-19.04/5.0.0-13-GENERIC/X86_64/86771347FB>) |
| 1002:439c | 1462:aa53 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 1     | pata_at... | [7BD55BD71D](<All In One/MSI/MS-AA/MS-AA53/738F36889CD9/MANJARO/4.19.34-1-MANJARO/X86_64/7BD55BD71D>) |
| 1022:780c | 1043:8589 | AMD              | FCH IDE Controller                   | 1     | pata_at... | [C8D8836613](<All In One/ASUSTek Computer/ET2221/ET2221A/27768DCF5E7B/UBUNTU-18.04/4.15.0-54-GENERIC/X86_64/C8D8836613>) |
| 1022:780c | 1458:b001 | AMD              | FCH IDE Controller                   | 1     | pata_at... | [DD512D1882](<All In One/Gigabyte Technology/GB-A5/GB-A5DNK-RH/2D59EF3CA1FB/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/DD512D1882>) |
| 10de:0759 | 1025:0461 | Nvidia           | MCP78S [GeForce 8200] IDE            | 1     | pata_am... | [04B8123AA5](<All In One/Acer/Aspire/Aspire Z3101/EDA041C04858/UBUNTU-18.04/4.15.0-96-GENERIC/X86_64/04B8123AA5>) |
| 10de:0ab5 | 1043:8379 | Nvidia           | MCP79 SATA Controller                | 1     | ahci, p... | [72365E4985](<All In One/ASUSTek Computer/ET/ET2002/9AD492BE589B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/72365E4985>) |
| 197b:2363 | 1462:ae11 | JMicron Techn... | JMB363 SATA/IDE Controller           | 1     | ahci       | [17AD880F72](<All In One/MSI/MS-AE/MS-AE1111/D998FCCDF4CE/ROSA-2016.1/4.9.124-NRJ-DESKTOP-1ROSA-X86_64/X86_64/17AD880F72>) |
| 197b:2363 | 197b:2363 | JMicron Techn... | JMB363 SATA/IDE Controller           | 1     | ahci       | [8ADEBB44D3](<All In One/Acer/Veriton/Veriton Z4860G/87F793395C72/ALT-9.1/5.4.51-STD-DEF-ALT1/X86_64/8ADEBB44D3>) |
| 8086:0f21 |           | Intel            | Atom Processor E3800 Series SATA ... | 1     | ata_piix   | [B3E778A640](<All In One/Acer/Aspire/Aspire Z1-601/502836ED0FF7/POP!_OS-20.04/5.4.0-7634-GENERIC/X86_64/B3E778A640>) |
| 8086:0f21 | 1025:085f | Intel            | Atom Processor E3800 Series SATA ... | 1     | ata_pii... | [7923ACCECA](<All In One/Acer/Aspire/Aspire ZC-606/5D8E49197BD5/ROSA-2014.1/3.14.44-NRJ-DESKTOP-2ROSA-X86_64/X86_64/7923ACCECA>) |
| 8086:1c00 | 1025:0618 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pata_acpi  | [B8E61A53BD](<All In One/Gateway/ZX/ZX6971/2A2802F2406C/UBUNTU-18.04/5.3.0-45-GENERIC/X86_64/B8E61A53BD>) |
| 8086:1c00 | 103c:2aed | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ata_pii... | [E2ADA83EE9](<All In One/Hewlett-Packard/HP3520/HP3520 Aio/85A474C6BFEC/ROSA-2016.1/4.9.20-NRJ-DESKTOP-1ROSA-X86_64/X86_64/E2ADA83EE9>) |
| 8086:1c00 | 1458:b005 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ata_pii... | [A965900724](<All In One/Gigabyte Technology/H61/H61M-DS2/763FAF752932/MANJARO-21.2.1/5.10.81-1-MULTIMEDIA-LTS/X86_64/A965900724>) |
| 8086:1c00 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ata_pii... | [098D8022D0](<All In One/Lenovo/C/C430/C3D6B501559D/ROSA-2014.1/3.14.44-NRJ-DESKTOP-2ROSA-I586/I686/098D8022D0>) |
| 8086:1c08 | 1025:0618 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pata_acpi  | [B8E61A53BD](<All In One/Gateway/ZX/ZX6971/2A2802F2406C/UBUNTU-18.04/5.3.0-45-GENERIC/X86_64/B8E61A53BD>) |
| 8086:1c08 | 103c:2aed | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ata_pii... | [E2ADA83EE9](<All In One/Hewlett-Packard/HP3520/HP3520 Aio/85A474C6BFEC/ROSA-2016.1/4.9.20-NRJ-DESKTOP-1ROSA-X86_64/X86_64/E2ADA83EE9>) |
| 8086:1c08 | 1458:b002 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ata_pii... | [A965900724](<All In One/Gigabyte Technology/H61/H61M-DS2/763FAF752932/MANJARO-21.2.1/5.10.81-1-MULTIMEDIA-LTS/X86_64/A965900724>) |
| 8086:1c08 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ata_pii... | [098D8022D0](<All In One/Lenovo/C/C430/C3D6B501559D/ROSA-2014.1/3.14.44-NRJ-DESKTOP-2ROSA-I586/I686/098D8022D0>) |
| 8086:1e00 | 1028:0548 | Intel            | 7 Series/C210 Series Chipset Fami... | 1     | ata_piix   | [B94AB82BDC](<All In One/Dell/Inspiron/Inspiron One 2330/8A9D53F13600/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/B94AB82BDC>) |
| 8086:1e01 | 1462:a953 | Intel            | 7 Series Chipset Family 4-port SA... | 1     | ata_pii... | [1EAD53F6C2](<All In One/MSI/MS-A/MS-A95311/57D5FC913695/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/1EAD53F6C2>) |
| 8086:1e08 | 1028:0548 | Intel            | 7 Series/C210 Series Chipset Fami... | 1     | ata_piix   | [B94AB82BDC](<All In One/Dell/Inspiron/Inspiron One 2330/8A9D53F13600/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/B94AB82BDC>) |
| 8086:2651 | 107b:4009 | Intel            | 82801FB/FW (ICH6/ICH6W) SATA Cont... | 1     | pata_acpi  | [0213C3A21C](<All In One/Gateway/PROFILE5/PROFILE5.5/89C7C3620F05/UBUNTU-18.04/4.15.0-122-GENERIC/I686/0213C3A21C>) |
| 8086:27c0 | 1043:8179 | Intel            | NM10/ICH7 Family SATA Controller ... | 1     | ata_pii... | [A4A1D08110](<All In One/ASUSTek Computer/ET2400/ET2400E/E5D937FA11F7/OPENMANDRIVA-4.50/5.12.4-DESKTOP-1OMV4050/X86_64/A4A1D08110>) |
| 8086:27c0 | 1462:ae11 | Intel            | NM10/ICH7 Family SATA Controller ... | 1     | ata_pii... | [17AD880F72](<All In One/MSI/MS-AE/MS-AE1111/D998FCCDF4CE/ROSA-2016.1/4.9.124-NRJ-DESKTOP-1ROSA-X86_64/X86_64/17AD880F72>) |
| 8086:27c0 | 17aa:3607 | Intel            | NM10/ICH7 Family SATA Controller ... | 1     | pata_acpi  | [0C9232361D](<All In One/Lenovo/C200/C200 10040/933BB294784A/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/0C9232361D>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a806 | 144d:a801 | Samsung Elect... | Electronics Non-Volatile memory c... | 31    | nvme       | [5E0CEEF0D1](<All In One/Apple/iMac19/iMac19,2/B4B5423C68DB/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/5E0CEEF0D1>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 29    | nvme       | [79D2578788](<All In One/Apple/iMac19/iMac19,2/703D201F7BA5/UBUNTU-20.04/5.16.7-051607-GENERIC/X86_64/79D2578788>) |
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 19    | nvme       | [68B6455D7A](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-27ICB F0DE00A7MB/9B6878A5EA27/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/68B6455D7A>) |
| 1c5c:1327 | 1c5c:0000 | SK Hynix         | BC501 NVMe Solid State Drive         | 11    | nvme       | [9E72716F96](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222FA_A6432FA/9F429A9552E8/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/9E72716F96>) |
| 15b7:5003 | 15b7:5003 | Sandisk          | WD Blue SN500 / PC SN520 NVMe SSD    | 9     | nvme       | [CC989948AF](<All In One/Hewlett-Packard/ProOne/ProOne 440 G4 23.8-in NT AiO/9E1FC507AB5B/DEBIAN-11/5.10.0-8-AMD64/X86_64/CC989948AF>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980              | 8     | nvme       | [4DB843D0C6](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-dp0xxx/F7426AF86A80/OPENMANDRIVA-4.50/5.16.3-DESKTOP-2OMV4050/X86_64/4DB843D0C6>) |
| 106b:2001 | 106b:2001 | Apple            | S1X NVMe Controller                  | 7     | nvme       | [436904EAE3](<All In One/Apple/iMac17/iMac17,1/7E034427C03F/DEBIAN-11/5.10.0-12-AMD64/X86_64/436904EAE3>) |
| 1e0f:0001 | 1e0f:0001 | KIOXIA           | Non-Volatile memory controller       | 7     | nvme       | [EA489D447C](<All In One/Dell/OptiPlex/OptiPlex 7480 AIO/AA453186B2B9/LINUXMINT-20.1/5.4.0-104-GENERIC/X86_64/EA489D447C>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT SSD Controller     | 5     | nvme       | [727E0D3A2E](<All In One/Dell/Inspiron/Inspiron 3280 AIO/34CA6784808C/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/727E0D3A2E>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 5     | nvme       | [26D008C895](<All In One/Acidanthera/iMac19/iMac19,1/2E9792DAB2C5/POP!_OS-21.04/5.13.0-7614-GENERIC/X86_64/26D008C895>) |
| 2646:500c | 2646:500c | Kingston Tech... | Technology Company Non-Volatile m... | 5     | nvme       | [38DDF02B60](<All In One/AIO/PC/PC/72C48E584F76/RED-OS-7.3.1/5.15.10-1.EL7.X86_64/X86_64/38DDF02B60>) |
| 1179:0113 | 1179:0001 | Toshiba Ameri... | BG3 NVMe SSD Controller              | 4     | nvme       | [225F3EE57B](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/3E30057D83C8/ELEMENTARY-6/5.11.0-38-GENERIC/X86_64/225F3EE57B>) |
| 15b7:5009 | 15b7:5009 | Sandisk          | WD Blue SN550 NVMe SSD               | 4     | nvme       | [BC20F9A9CA](<All In One/Acer/Aspire/Aspire C27-1655/163A30053117/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/BC20F9A9CA>) |
| 1e95:9100 | 126f:2263 | Solid State S... | Non-Volatile memory controller       | 4     | nvme       | [681D2000F3](<All In One/Dell/Inspiron/Inspiron 5400 AIO/9A7047B5BC8F/ZORIN-16/5.13.0-30-GENERIC/X86_64/681D2000F3>) |
| 8086:f1a8 | 8086:390d | Intel            | SSD 660P Series                      | 4     | nvme       | [8579540A18](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-d0xxx/03AC6BD9F069/LINUXMINT-20.1/5.4.0-62-GENERIC/X86_64/8579540A18>) |
| 1179:0116 | 1179:0001 | Toshiba Ameri... | Toshiba America Info Non-Volatile... | 3     | nvme       | [81AF87F00C](<All In One/Dell/Inspiron/Inspiron 27 7775/D1240D4484D8/ELEMENTARY-5.1.7/5.4.0-89-GENERIC/X86_64/81AF87F00C>) |
| 1344:5410 | 1344:0100 | Micron Techno... | Non-Volatile memory controller       | 3     | nvme       | [46A47AB08E](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/D3EA8545A30E/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/46A47AB08E>) |
| 15b7:5008 | 15b7:5008 | Sandisk          | Non-Volatile memory controller       | 3     | nvme       | [B3EDFBFEE7](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 24ALC6 F0G1002YUK/C0099F4B4E0C/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/B3EDFBFEE7>) |
| 1cc4:2263 | 1cc4:1cc4 | Union Memory ... | Non-Volatile memory controller       | 3     | nvme       | [5DA493DE55](<All In One/Lenovo/IdeaCentre/IdeaCentre A540-24API F0EM0000UK/93E2EABF69EE/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/5DA493DE55>) |
| 2646:5008 | 2646:5008 | Kingston Tech... | U-SNS8154P3 NVMe SSD                 | 3     | nvme       | [5820A2D4C3](<All In One/Acer/Aspire/Aspire C27-962/93EEE25E2034/ENDLESS-3.9.3/5.8.0-14-GENERIC/X86_64/5820A2D4C3>) |
| 106b:2005 | 106b:1800 | Apple            | ANS2 NVMe Controller                 | 2     | nvme       | [43CB3AF3A5](<All In One/Apple/iMacPro1/iMacPro1,1/5A74E0CD85EE/KUBUNTU-20.10/5.8.0-25-LOWLATENCY/X86_64/43CB3AF3A5>) |
| 15b7:5006 | 15b7:5006 | Sandisk          | WD Black SN750 / PC SN730 NVMe SSD   | 2     | nvme       | [F15CA34264](<All In One/Acer/Aspire/Aspire C27-962/A23104408196/LINUXMINT-20.3/5.4.0-92-GENERIC/X86_64/F15CA34264>) |
| 1987:5007 | 1987:5007 | Phison Electr... | E7 NVMe Controller                   | 2     | nvme       | [DA913ED8D3](<All In One/Acidanthera/iMac19/iMac19,1/F3CD9559B336/LINUXMINT-20.1/5.8.0-50-GENERIC/X86_64/DA913ED8D3>) |
| 1c5c:174a | 1c5c:174a | SK Hynix         | Gold P31 SSD                         | 2     | nvme       | [32ECAAC328](<All In One/Acer/Aspire/Aspire C24-1650/DA8A3F508342/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/32ECAAC328>) |
| 8086:0975 | 8086:8410 | Intel            | Non-Volatile memory controller       | 2     | nvme       | [EFB6906A46](<All In One/Hewlett-Packard/ENVY/ENVY All-in-One 32-a11xxx/AC2CB5057523/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/EFB6906A46>) |
| 8086:0975 | 8086:8510 | Intel            | Non-Volatile memory controller       | 2     | nvme       | [EFB6906A46](<All In One/Hewlett-Packard/ENVY/ENVY All-in-One 32-a11xxx/AC2CB5057523/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/EFB6906A46>) |
| 10ec:5762 | 10ec:5762 | Realtek Semic... | RTS5763DL NVMe SSD Controller        | 1     | nvme       | [94918CE530](<All In One/Hewlett-Packard/84EF/84EF 01100/71672B489844/UBUNTU-21.04/5.11.0-31-GENERIC/X86_64/94918CE530>) |
| 1179:0115 | 1179:0001 | Toshiba Ameri... | XG4 NVMe SSD Controller              | 1     | nvme       | [F41BD5BF5B](<All In One/Dell/Precision/Precision 5720 AIO/88AAB8E50334/LINUXMINT-19.1/4.15.0-20-GENERIC/X86_64/F41BD5BF5B>) |
| 1179:011a | 1179:0001 | Toshiba Ameri... | XG6 NVMe SSD Controller              | 1     | nvme       | [930847F29A](<All In One/Hewlett-Packard/ProOne/ProOne 440 G5 23.8-in All-in-One/C540F809EF08/RELS-7.8/3.10.0-1160.RES7.X86_64/X86_64/930847F29A>) |
| 126f:2262 | 126f:2262 | Silicon Motion   | SM2262/SM2262EN SSD Controller       | 1     | nvme       | [42B182D5F0](<All In One/Acidanthera/iMacPro1/iMacPro1,1/9A30E1010885/ARCH/5.9.10-ARCH1-1/X86_64/42B182D5F0>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 1     | nvme       | [1BC488324F](<All In One/MSI/MS-B/MS-B10611/E4546301703F/ZORIN-16/5.11.0-36-GENERIC/X86_64/1BC488324F>) |
| 144d:a808 | 144d:a811 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 1     | nvme       | [25999BFD58](<All In One/Apple/iMac19/iMac19,1/6C107CF760F6/UBUNTU-20.04/5.4.0-54-GENERIC/X86_64/25999BFD58>) |
| 15b7:5002 | 15b7:5002 | Sandisk          | WD Black 2018/SN750 / PC SN720 NV... | 1     | nvme       | [2BF103DD36](<All In One/Dell/OptiPlex/OptiPlex 3050 AIO/6E8B4AA4839E/UBUNTU-18.04/4.18.0-15-GENERIC/X86_64/2BF103DD36>) |
| 15b7:5005 | 15b7:5005 | Sandisk          | PC SN520 NVMe SSD                    | 1     | nvme       | [231DA9915B](<All In One/Lenovo/IdeaCentre/IdeaCentre A340-22ICB F0E90010RK/7B7162E100C2/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/231DA9915B>) |
| 15b7:5007 | 15b7:5007 | Sandisk          | Non-Volatile memory controller       | 1     | nvme       | [3A565370DE](<All In One/Dell/OptiPlex/OptiPlex 7480 AIO/58ED8D7EB631/ALT-8.0/4.19.135-UN-DEF-ALT0.M80C.1/X86_64/3A565370DE>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013 E13 NVMe Controller           | 1     | nvme       | [2E8E2BD9B3](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/8BDE9218D7A8/ZORIN-16/5.11.0-40-GENERIC/X86_64/2E8E2BD9B3>) |
| 1c5c:1339 | 1c5c:0000 | SK Hynix         | BC511                                | 1     | nvme       | [4F0974E255](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-dd1xxx/2777F47C0C1D/LINUXMINT-20.2/5.4.0-89-GENERIC/X86_64/4F0974E255>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 1     | nvme       | [CB6D3B830B](<All In One/Others/1/1.0/47C41F330033/ELEMENTARY-5.1.3/5.3.0-47-GENERIC/X86_64/CB6D3B830B>) |
| 1cc4:6203 | 1cc4:1cc4 | Union Memory ... | Non-Volatile memory controller       | 1     | nvme       | [53462F848A](<All In One/Lenovo/Yoga/Yoga 27-ARH F0FN0002CP/61F8ED84D9C7/XUBUNTU-20.04/5.11.0-40-GENERIC/X86_64/53462F848A>) |
| 8086:2522 | 8086:3810 | Intel            | NVMe Optane Memory Series            | 1     | nvme       | [F172B5B1EA](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-22ICB F0DT001TUS/168A49A3A14F/UBUNTU-BUDGIE-20.10/5.8.0-44-GENERIC/X86_64/F172B5B1EA>) |
| 8086:f1a5 | 8086:390a | Intel            | SSD 600P Series                      | 1     | nvme       | [D77183679A](<All In One/MSI/H110/H110 Pro PRO20EX/B8F27402FC20/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/D77183679A>) |
| 8086:f1a6 | 8086:390b | Intel            | SSD Pro 7600p/760p/E 6100p Series    | 1     | nvme       | [577AD83B8F](<All In One/Acidanthera/iMacPro1/iMacPro1,1/6286842FEC0E/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/577AD83B8F>) |
| 8086:f1aa | 8086:390f | Intel            | Non-Volatile memory controller       | 1     | nvme       | [F788930C1E](<All In One/ASUSTek Computer/ASUS/ASUS AIO M3400WUA_M3400WUA/C57F5A924964/ROSA-12/5.10.71-GENERIC-1ROSA2021.1-X86_64/X86_64/F788930C1E>) |
| c0a9:2263 | c0a9:2263 | Micron/Crucia... | P1 NVMe PCIe SSD                     | 1     | nvme       | [0B1F7CCED7](<All In One/Dell/Inspiron/Inspiron 27 7775/ACE5205CCA5D/FEDORA-32/5.8.7-200.FC32.X86_64/X86_64/0B1F7CCED7>) |
| c0a9:540a | c0a9:540a | Micron/Crucia... | P2 NVMe PCIe SSD                     | 1     | nvme       | [273716C6CB](<All In One/Others/Others/Others/2C5F9D7A9E9D/UBUNTU-20.04/5.11.0-25-GENERIC/X86_64/273716C6CB>) |
| c0a9:5412 | c0a9:0100 | Micron/Crucia... | Non-Volatile memory controller       | 1     | nvme       | [D26755F36D](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-xa0xxx/AFF07EB65B70/MANJARO/5.13.19-2-MANJARO/X86_64/D26755F36D>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2822 | 1028:05a7 | Intel            | SATA Controller [RAID mode]          | 9     | ahci       | [ED0DFEF2DF](<All In One/Dell/OptiPlex/OptiPlex 9020 AIO/FA6C8EA82464/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/ED0DFEF2DF>) |
| 8086:282a | 1043:17b1 | Intel            | 82801 Mobile SATA Controller [RAI... | 6     | ahci       | [60C6C7EA7C](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/3602C27EA430/ENDLESS-3.9.6/5.8.0-14-GENERIC/X86_64/60C6C7EA7C>) |
| 8086:9a0b | 8086:0000 | Intel            | Volume Management Device NVMe RAI... | 6     | vmd        | [BC20F9A9CA](<All In One/Acer/Aspire/Aspire C27-1655/163A30053117/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/BC20F9A9CA>) |
| 8086:2822 | 1028:06c5 | Intel            | SATA Controller [RAID mode]          | 5     | ahci       | [0DCB1B8C3C](<All In One/Dell/OptiPlex/OptiPlex 7440 AIO/34CACCC6D3D6/UBUNTU-20.04/5.13.0-32-GENERIC/X86_64/0DCB1B8C3C>) |
| 8086:282a | 1025:1418 | Intel            | 82801 Mobile SATA Controller [RAI... | 5     | ahci       | [F15CA34264](<All In One/Acer/Aspire/Aspire C27-962/A23104408196/LINUXMINT-20.3/5.4.0-92-GENERIC/X86_64/F15CA34264>) |
| 8086:282a | 103c:84de | Intel            | 82801 Mobile SATA Controller [RAI... | 4     | ahci       | [6B7FA4FF60](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/B673E7AEA681/UBUNTU-19.04/5.0.0-27-GENERIC/X86_64/6B7FA4FF60>) |
| 8086:2822 | 1028:0625 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [399D367F06](<All In One/Dell/OptiPlex/OptiPlex 9030 AIO/4D03114CF02D/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/399D367F06>) |
| 8086:2822 | 1028:079c | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [0B0F9A42CD](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/F87DB1F1F5AC/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/0B0F9A42CD>) |
| 8086:2822 | 103c:3561 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [5FF1D7A72E](<All In One/Hewlett-Packard/Z1/Z1 Workstation/4089A5726DF1/FEDORA-35/5.14.18-300.FC35.X86_64/X86_64/5FF1D7A72E>) |
| 8086:2822 | 103c:86c7 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [EFB6906A46](<All In One/Hewlett-Packard/ENVY/ENVY All-in-One 32-a11xxx/AC2CB5057523/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/EFB6906A46>) |
| 8086:282a | 1028:0954 | Intel            | 82801 Mobile SATA Controller [RAI... | 2     | ahci       | [51D212B73F](<All In One/Dell/Inspiron/Inspiron 7790 AIO/5226FB806DAF/UBUNTU-2020/5.8.0-44-GENERIC/X86_64/51D212B73F>) |
| 8086:282a | 152d:0924 | Intel            | 82801 Mobile SATA Controller [RAI... | 2     | ahci       | [9D84CFFDE0](<All In One/VIZIO/CA/CA27/FCA4878A3D40/ZORIN-16/5.13.0-28-GENERIC/X86_64/9D84CFFDE0>) |
| 8086:2822 | 1025:1291 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [13496AAE5D](<All In One/Acer/Veriton/Veriton Z4660G/A736A6205FE1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/13496AAE5D>) |
| 8086:2822 | 1028:054b | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [FCD0EF9F0E](<All In One/Dell/XPS/XPS One 2710/E83BF6F5E12A/POP!_OS-21.04/5.13.0-7614-GENERIC/X86_64/FCD0EF9F0E>) |
| 8086:2822 | 1028:05b0 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [BDF125B54E](<All In One/Dell/XPS/XPS 2720/FAC2C5816BAA/UBUNTU-20.04/5.8.0-45-GENERIC/X86_64/BDF125B54E>) |
| 8086:2822 | 1028:075c | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [1FA1F8CD8C](<All In One/Dell/XPS/XPS 7760 AIO/BD46D877F953/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/1FA1F8CD8C>) |
| 8086:2822 | 1028:075d | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [F41BD5BF5B](<All In One/Dell/Precision/Precision 5720 AIO/88AAB8E50334/LINUXMINT-19.1/4.15.0-20-GENERIC/X86_64/F41BD5BF5B>) |
| 8086:2822 | 1028:079e | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [2BF103DD36](<All In One/Dell/OptiPlex/OptiPlex 3050 AIO/6E8B4AA4839E/UBUNTU-18.04/4.18.0-15-GENERIC/X86_64/2BF103DD36>) |
| 8086:2822 | 103c:82a6 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [DD3E2FA2B5](<All In One/Hewlett-Packard/ProOne/ProOne 400 G3 20.0-in Non-Touch AiO/A09511605F07/MANJARO-18.1.5/5.4.6-2-MANJARO/X86_64/DD3E2FA2B5>) |
| 8086:2822 | 103c:838b | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [AC62725ABE](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-r0xx/7DE2EBF070ED/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/AC62725ABE>) |
| 8086:2822 | 103c:86ed | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [78778F22A2](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 24-k0xxx/97B1ED37BE45/ELEMENTARY-6/5.11.0-27-GENERIC/X86_64/78778F22A2>) |
| 8086:2822 | 103c:86f7 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [27FB773ED3](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-df0xxx/6B44738EE3C7/UBUNTU-20.04/5.8.0-55-GENERIC/X86_64/27FB773ED3>) |
| 8086:2822 | 17aa:36dd | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [7EBBF6AAD0](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-27IKL F0D0001BCK/4FB1AC9C7D60/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/7EBBF6AAD0>) |
| 8086:282a | 1028:05d1 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [45C116DB45](<All In One/Dell/XPS/XPS 18/9C7C62A1A766/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/45C116DB45>) |
| 8086:282a | 1028:05db | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [1DBF9CCED7](<All In One/Dell/Inspiron/Inspiron 2350/F3030D1F2BE8/UBUNTU-20.04/5.10.9-051009-GENERIC/X86_64/1DBF9CCED7>) |
| 8086:282a | 1028:0853 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [107F431AD7](<All In One/Dell/Inspiron/Inspiron 3277 AIO/0A27E3227B8E/ROSA-2016.1/4.15.0-DESKTOP-94.1ROSA-X86_64/X86_64/107F431AD7>) |
| 8086:282a | 1028:08f9 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [727E0D3A2E](<All In One/Dell/Inspiron/Inspiron 3280 AIO/34CA6784808C/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/727E0D3A2E>) |
| 8086:282a | 1028:0953 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [D77787D6EC](<All In One/Dell/Inspiron/Inspiron 5490 AIO/DED288B166FA/POP!_OS-20.10/5.8.0-7642-GENERIC/X86_64/D77787D6EC>) |
| 8086:282a | 103c:87a4 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [FCC6F8EC82](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-df0xxx/1ACFF9ABA384/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/FCC6F8EC82>) |
| 8086:282a | 17aa:36dc | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [A4AFD5181F](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-24IKU F0D200E2LD/E39A5F0652F6/ARCH-ROLLING/5.6.13.A-1-HARDENED/X86_64/A4AFD5181F>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1513 | 2222:1111 | Intel            | CV82524 Thunderbolt Controller [L... | 103   | thunder... | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 8086:15d2 | 8086:0000 | Intel            | JHL6540 Thunderbolt 3 NHI (C step... | 45    | thunder... | [841AB4FFE2](<All In One/Apple/iMac18/iMac18,2/6AAE34125DB5/FEDORA-36/5.17.0-0.RC5.102.FC36.X86_64/X86_64/841AB4FFE2>) |
| 8086:156c |           | Intel            | DSL5520 Thunderbolt 2 NHI [Falcon... | 39    | thunder... | [436904EAE3](<All In One/Apple/iMac17/iMac17,1/7E034427C03F/DEBIAN-11/5.10.0-12-AMD64/X86_64/436904EAE3>) |
| 8086:15eb | 8086:0000 | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 31    | thunder... | [5E0CEEF0D1](<All In One/Apple/iMac19/iMac19,2/B4B5423C68DB/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/5E0CEEF0D1>) |
| 8086:d150 |           | Intel            | Core Processor QPI Link              | 31    |            | [48688703FE](<All In One/Apple/iMac11/iMac11,3/720CB377D1CB/UBUNTU-20.04/5.8.0-43-GENERIC/X86_64/48688703FE>) |
| 8086:d151 |           | Intel            | Core Processor QPI Routing and Pr... | 31    |            | [48688703FE](<All In One/Apple/iMac11/iMac11,3/720CB377D1CB/UBUNTU-20.04/5.8.0-43-GENERIC/X86_64/48688703FE>) |
| 8086:d155 |           | Intel            | Core Processor System Management ... | 31    |            | [48688703FE](<All In One/Apple/iMac11/iMac11,3/720CB377D1CB/UBUNTU-20.04/5.8.0-43-GENERIC/X86_64/48688703FE>) |
| 8086:d156 |           | Intel            | Core Processor Semaphore and Scra... | 31    |            | [48688703FE](<All In One/Apple/iMac11/iMac11,3/720CB377D1CB/UBUNTU-20.04/5.8.0-43-GENERIC/X86_64/48688703FE>) |
| 8086:d157 |           | Intel            | Core Processor System Control and... | 31    |            | [48688703FE](<All In One/Apple/iMac11/iMac11,3/720CB377D1CB/UBUNTU-20.04/5.8.0-43-GENERIC/X86_64/48688703FE>) |
| 8086:d158 |           | Intel            | Core Processor Miscellaneous Regi... | 31    |            | [48688703FE](<All In One/Apple/iMac11/iMac11,3/720CB377D1CB/UBUNTU-20.04/5.8.0-43-GENERIC/X86_64/48688703FE>) |
| 197b:2382 | 1025:0266 | JMicron Techn... | SD/MMC Host Controller               | 10    | sdhci_pci  | [141F5642FC](<All In One/Acer/Aspire/Aspire Z5610/93F4A5EF8D69/LINUXMINT-20.2/5.4.0-96-GENERIC/X86_64/141F5642FC>) |
| 197b:2383 | 1025:0266 | JMicron Techn... | MS Host Controller                   | 10    | jmb38x_ms  | [141F5642FC](<All In One/Acer/Aspire/Aspire Z5610/93F4A5EF8D69/LINUXMINT-20.2/5.4.0-96-GENERIC/X86_64/141F5642FC>) |
| 8086:3190 |           | Intel            | Celeron/Pentium Silver Processor ... | 10    |            | [23082AB8CA](<All In One/ASUSTek Computer/Vivo/Vivo AIO 22 V222GA_V222GA/30DB3562CA34/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/23082AB8CA>) |
| 8086:1911 | 1025:1287 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 9     |            | [70014EA10E](<All In One/Acer/Aspire/Aspire C22-865/CAE70310F314/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/70014EA10E>) |
| 8086:1911 | 103c:84ee | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 9     |            | [2311649D51](<All In One/Hewlett-Packard/Pavilion/Pavilion All-in-One 27-xa0xxx/3187A1587DA6/LINUXMINT-20.2/5.4.0-90-GENERIC/X86_64/2311649D51>) |
| 8086:1911 | 8086:1911 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 9     |            | [2FDFFAE0E5](<All In One/ASUSTek Computer/V241/V241IC-R/F65D7B31A7ED/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/2FDFFAE0E5>) |
| 8086:3190 | 1025:1304 | Intel            | Celeron/Pentium Silver Processor ... | 9     |            | [B7F823BFDA](<All In One/Others/Others/Others/EFF35801EAC2/UBUNTU/5.8.0-14-GENERIC/X86_64/B7F823BFDA>) |
| 1180:e232 | 104d:907e | Ricoh            | PCIe Memory Stick Host Controller    | 8     |            | [0451CAEB29](<All In One/Sony/VPCL212/VPCL212FX/01EE677E7F92/UBUNTU-21.10/5.13.0-22-GENERIC/X86_64/0451CAEB29>) |
| 8086:1911 | 1028:0754 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 7     |            | [00C297540D](<All In One/Dell/Inspiron/Inspiron 3464 AIO/31AD17DDDC01/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/00C297540D>) |
| 1180:e232 | 104d:9097 | Ricoh            | PCIe Memory Stick Host Controller    | 6     |            | [4D477A343A](<All In One/Sony/SVL2411/SVL24117FLB/B337A07B7653/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/4D477A343A>) |
| 8086:1911 | 1043:17b1 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 6     |            | [60C6C7EA7C](<All In One/ASUSTek Computer/Vivo/Vivo AIO 24 V241FA_V241FA/3602C27EA430/ENDLESS-3.9.6/5.8.0-14-GENERIC/X86_64/60C6C7EA7C>) |
| 1180:e232 | 104d:9083 | Ricoh            | PCIe Memory Stick Host Controller    | 5     |            | [EEB433BF77](<All In One/Sony/VPCJ21/VPCJ21S1E/704C84A1D492/LINUXMINT-20.1/5.8.0-53-GENERIC/X86_64/EEB433BF77>) |
| 8086:1911 | 103c:8446 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 5     |            | [46A47AB08E](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/D3EA8545A30E/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/46A47AB08E>) |
| 8086:3190 | 103c:86f0 | Intel            | Celeron/Pentium Silver Processor ... | 5     |            | [75738404AE](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-df0xxx/20A2CA3001FD/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/75738404AE>) |
| 197b:2382 | 17aa:3602 | JMicron Techn... | SD/MMC Host Controller               | 4     | sdhci_pci  | [C25FDFE643](<All In One/Lenovo/IdeaCentre/IdeaCentre B300 10051/20208F91C976/ENDLESS-3.8.6/5.4.0-42-GENERIC/X86_64/C25FDFE643>) |
| 197b:2383 | 17aa:3602 | JMicron Techn... | MS Host Controller                   | 4     | jmb38x_ms  | [C25FDFE643](<All In One/Lenovo/IdeaCentre/IdeaCentre B300 10051/20208F91C976/ENDLESS-3.8.6/5.4.0-42-GENERIC/X86_64/C25FDFE643>) |
| 197b:2384 | 17aa:3602 | JMicron Techn... | xD Host Controller                   | 4     |            | [C25FDFE643](<All In One/Lenovo/IdeaCentre/IdeaCentre B300 10051/20208F91C976/ENDLESS-3.8.6/5.4.0-42-GENERIC/X86_64/C25FDFE643>) |
| 8086:09ab | 1043:1482 | Intel            | System peripheral                    | 4     |            | [FFB4ED2207](<All In One/ASUSTek Computer/ASUS/ASUS Vivo AIO V241EA_V241EA/69C580FE0877/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/FFB4ED2207>) |
| 8086:1568 | 2222:1111 | Intel            | DSL4510 Thunderbolt NHI [Redwood ... | 4     |            | [CD144ACBF6](<All In One/Apple/iMac14/iMac14,4/193D926C44E8/UBUNTU-20.04/5.8.0-63-GENERIC/X86_64/CD144ACBF6>) |
| 8086:9a11 | 1043:1482 | Intel            | GNA Scoring Accelerator module       | 4     |            | [FFB4ED2207](<All In One/ASUSTek Computer/ASUS/ASUS Vivo AIO V241EA_V241EA/69C580FE0877/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/FFB4ED2207>) |
| 1180:e230 | 104d:9060 | Ricoh            | R5U2xx (R5U230 / R5U231 / R5U241)... | 3     |            | [05CFF66AC2](<All In One/Sony/VPCL11/VPCL11M1E/93DA71AEEC1E/UBUNTU-19.04/5.0.0-27-GENERIC/X86_64/05CFF66AC2>) |
| 1180:e230 | 104d:9074 | Ricoh            | R5U2xx (R5U230 / R5U231 / R5U241)... | 3     |            | [D1D4080F45](<All In One/Sony/VPCJ118/VPCJ118FW/7247E7BFDC34/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D1D4080F45>) |
| 197b:2382 | 1025:0275 | JMicron Techn... | SD/MMC Host Controller               | 3     | sdhci_pci  | [49DF2710DC](<All In One/Packard Bell/ONETWO/ONETWO M3700/3096674A954A/UBUNTU-18.04/5.0.0-37-GENERIC/X86_64/49DF2710DC>) |
| 197b:2382 | 1025:0608 | JMicron Techn... | SD/MMC Host Controller               | 3     | sdhci_pci  | [33937E8F75](<All In One/Acer/Aspire/Aspire Z1620/19DE00291955/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/33937E8F75>) |
| 197b:2382 | 103c:1489 | JMicron Techn... | SD/MMC Host Controller               | 3     | sdhci_pci  | [F321ECCADC](<All In One/Hewlett-Packard/Compaq/Compaq 6000 Pro AiO Brazil PC/8D326FF3188E/POP!_OS-21.10/5.15.11-76051511-GENERIC/X86_64/F321ECCADC>) |
| 197b:2382 | 1043:842d | JMicron Techn... | SD/MMC Host Controller               | 3     | sdhci_pci  | [86CD4A72D1](<All In One/ASUSTek Computer/ET2010/ET2010AG/03DD34D94A32/XUBUNTU-21.04/5.11.0-37-GENERIC/X86_64/86CD4A72D1>) |
| 197b:2383 | 1025:0275 | JMicron Techn... | MS Host Controller                   | 3     | jmb38x_ms  | [49DF2710DC](<All In One/Packard Bell/ONETWO/ONETWO M3700/3096674A954A/UBUNTU-18.04/5.0.0-37-GENERIC/X86_64/49DF2710DC>) |
| 197b:2383 | 1025:0608 | JMicron Techn... | MS Host Controller                   | 3     | jmb38x_ms  | [33937E8F75](<All In One/Acer/Aspire/Aspire Z1620/19DE00291955/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/33937E8F75>) |
| 197b:2383 | 103c:1489 | JMicron Techn... | MS Host Controller                   | 3     | jmb38x_ms  | [F321ECCADC](<All In One/Hewlett-Packard/Compaq/Compaq 6000 Pro AiO Brazil PC/8D326FF3188E/POP!_OS-21.10/5.15.11-76051511-GENERIC/X86_64/F321ECCADC>) |
| 197b:2384 | 103c:1489 | JMicron Techn... | xD Host Controller                   | 3     |            | [F321ECCADC](<All In One/Hewlett-Packard/Compaq/Compaq 6000 Pro AiO Brazil PC/8D326FF3188E/POP!_OS-21.10/5.15.11-76051511-GENERIC/X86_64/F321ECCADC>) |
| 8086:1911 | 1028:0852 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 3     |            | [5A27DEAF8A](<All In One/Dell/Inspiron/Inspiron 3477 AIO/707700FC1C87/ROSA-2014.1/4.9.155-NRJ-DESKTOP-1ROSA-I586/I686/5A27DEAF8A>) |
| 8086:1911 | 1028:0984 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 3     |            | [EA489D447C](<All In One/Dell/OptiPlex/OptiPlex 7480 AIO/AA453186B2B9/LINUXMINT-20.1/5.4.0-104-GENERIC/X86_64/EA489D447C>) |
| 8086:1911 | 17aa:36f4 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 3     |            | [68B6455D7A](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-27ICB F0DE00A7MB/9B6878A5EA27/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/68B6455D7A>) |
| 8086:1911 | 8086:7270 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 3     |            | [273716C6CB](<All In One/Others/Others/Others/2C5F9D7A9E9D/UBUNTU-20.04/5.11.0-25-GENERIC/X86_64/273716C6CB>) |
| 8086:3190 | 17aa:36ed | Intel            | Celeron/Pentium Silver Processor ... | 3     |            | [B5D4B3357A](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 330-20IGM F0D70043CK/77A4D86B366E/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B5D4B3357A>) |
| 8086:3190 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 3     |            | [32E5618CFE](<All In One/BESSTAR Tech/GN/GN41/56D9EBD7BE9A/UBUNTU-20.04/5.7.1-050701-GENERIC/X86_64/32E5618CFE>) |
| 1180:0592 | 104d:9043 | Ricoh            | R5C592 Memory Stick Bus Host Adapter | 2     | r592       | [AFA509714D](<All In One/Sony/VGC-LN52/VGC-LN52JGB/54F15FF48E03/UBUNTU-20.04/5.8.0-54-GENERIC/X86_64/AFA509714D>) |
| 1180:0592 | 104d:9044 | Ricoh            | R5C592 Memory Stick Bus Host Adapter | 2     | r592       | [EB74857893](<All In One/Sony/VGC-JS210/VGC-JS210J/8B88CB56EBD6/ENDLESS-3.8.6/5.4.0-42-GENERIC/X86_64/EB74857893>) |
| 1180:e232 | 104d:908e | Ricoh            | PCIe Memory Stick Host Controller    | 2     |            | [E43A2C01EB](<All In One/Sony/VPCL22/VPCL22Z1R/BC94F4FEC1E7/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/E43A2C01EB>) |
| 197b:2392 | 103c:3561 | JMicron Techn... | SD/MMC Host Controller               | 2     | sdhci_pci  | [5FF1D7A72E](<All In One/Hewlett-Packard/Z1/Z1 Workstation/4089A5726DF1/FEDORA-35/5.14.18-300.FC35.X86_64/X86_64/5FF1D7A72E>) |

### Tv card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1131:7134 | 16be:5000 | Philips Semic... | SAA7134/SAA7135HL Video Broadcast... | 1     | saa7134    | [098FE372A3](<All In One/Acidanthera/iMac14/iMac14,4/E2C69985CC45/GENTOO-2.6/5.4.97-GENTOO_DQ87PG/X86_64/098FE372A3>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2830 | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 108   | uhci_hcd   | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 8086:2831 | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 108   | uhci_hcd   | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 8086:2832 | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 108   | uhci_hcd   | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 8086:2834 |           | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 108   | uhci_hcd   | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 8086:2835 | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 108   | uhci_hcd   | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 8086:2836 | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB2 EHCI Co... | 108   | ehci_pci   | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 8086:283a | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB2 EHCI Co... | 108   | ehci_pci   | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 8086:1c26 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 103   | ehci_pci   | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 8086:1c27 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 103   | uhci_hcd   | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 8086:1c2c | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 103   | uhci_hcd   | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 8086:1c2d | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 103   | ehci_pci   | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 10de:0aa5 | 10de:cb79 | Nvidia           | MCP79 OHCI USB 1.1 Controller        | 88    | ohci_pci   | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 10de:0aa6 | 10de:cb79 | Nvidia           | MCP79 EHCI USB 2.0 Controller        | 88    | ehci_pci   | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 10de:0aa7 | 10de:cb79 | Nvidia           | MCP79 OHCI USB 1.1 Controller        | 88    | ohci_pci   | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 10de:0aa9 | 10de:cb79 | Nvidia           | MCP79 EHCI USB 2.0 Controller        | 88    | ehci_pci   | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 8086:a12f | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 57    | xhci_hcd   | [436904EAE3](<All In One/Apple/iMac17/iMac17,1/7E034427C03F/DEBIAN-11/5.10.0-12-AMD64/X86_64/436904EAE3>) |
| 8086:3b34 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset USB2... | 56    | ehci_pci   | [99D7E82DF9](<All In One/Apple/iMac11/iMac11,2/9D11563CF50D/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/99D7E82DF9>) |
| 8086:3b36 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset USB ... | 56    | uhci_hcd   | [99D7E82DF9](<All In One/Apple/iMac11/iMac11,2/9D11563CF50D/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/99D7E82DF9>) |
| 8086:3b3b | 8086:7270 | Intel            | 5 Series/3400 Series Chipset USB ... | 56    | uhci_hcd   | [99D7E82DF9](<All In One/Apple/iMac11/iMac11,2/9D11563CF50D/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/99D7E82DF9>) |
| 8086:3b3c | 8086:7270 | Intel            | 5 Series/3400 Series Chipset USB2... | 56    | ehci_pci   | [99D7E82DF9](<All In One/Apple/iMac11/iMac11,2/9D11563CF50D/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/99D7E82DF9>) |
| 8086:8c31 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 46    | xhci_hcd   | [7757BE603C](<All In One/Apple/iMac14/iMac14,2/3F4033EA2574/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/7757BE603C>) |
| 8086:15d4 | 8086:0000 | Intel            | JHL6540 Thunderbolt 3 USB Control... | 45    | xhci_hcd   | [841AB4FFE2](<All In One/Apple/iMac18/iMac18,2/6AAE34125DB5/FEDORA-36/5.17.0-0.RC5.102.FC36.X86_64/X86_64/841AB4FFE2>) |
| 8086:1e26 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family USB ... | 32    | ehci_pci   | [435548337A](<All In One/Apple/iMac13/iMac13,1/BB29D11F01EF/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/435548337A>) |
| 8086:1e2d | 8086:7270 | Intel            | 7 Series/C216 Chipset Family USB ... | 32    | ehci_pci   | [435548337A](<All In One/Apple/iMac13/iMac13,1/BB29D11F01EF/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/435548337A>) |
| 8086:1e31 | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 32    | xhci_hcd   | [435548337A](<All In One/Apple/iMac13/iMac13,1/BB29D11F01EF/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/435548337A>) |
| 8086:a36d | 8086:7270 | Intel            | Cannon Lake PCH USB 3.1 xHCI Host... | 32    | xhci_pci   | [5E0CEEF0D1](<All In One/Apple/iMac19/iMac19,2/B4B5423C68DB/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/5E0CEEF0D1>) |
| 8086:15ec | 8086:0000 | Intel            | JHL7540 Thunderbolt 3 USB Control... | 31    | xhci_pci   | [5E0CEEF0D1](<All In One/Apple/iMac19/iMac19,2/B4B5423C68DB/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/5E0CEEF0D1>) |
| 8086:27c8 | 8086:7270 | Intel            | NM10/ICH7 Family USB UHCI Control... | 23    | uhci_hcd   | [261E6C0463](<All In One/Apple/iMac5/iMac5,1/F72BF7BFE069/LMDE-5/5.10.0-11-686/I686/261E6C0463>) |
| 8086:27c9 | 8086:7270 | Intel            | NM10/ICH7 Family USB UHCI Control... | 23    | uhci_hcd   | [261E6C0463](<All In One/Apple/iMac5/iMac5,1/F72BF7BFE069/LMDE-5/5.10.0-11-686/I686/261E6C0463>) |
| 8086:27ca | 8086:7270 | Intel            | NM10/ICH7 Family USB UHCI Control... | 23    | uhci_hcd   | [261E6C0463](<All In One/Apple/iMac5/iMac5,1/F72BF7BFE069/LMDE-5/5.10.0-11-686/I686/261E6C0463>) |
| 8086:27cb | 8086:7270 | Intel            | NM10/ICH7 Family USB UHCI Control... | 23    | uhci_hcd   | [261E6C0463](<All In One/Apple/iMac5/iMac5,1/F72BF7BFE069/LMDE-5/5.10.0-11-686/I686/261E6C0463>) |
| 8086:27cc | 8086:7270 | Intel            | NM10/ICH7 Family USB2 EHCI Contro... | 23    | ehci_pci   | [261E6C0463](<All In One/Apple/iMac5/iMac5,1/F72BF7BFE069/LMDE-5/5.10.0-11-686/I686/261E6C0463>) |
| 1022:7808 | 103c:8245 | AMD              | FCH USB EHCI Controller              | 15    | ehci_pci   | [BFDC2533BB](<All In One/Hewlett-Packard/20/20-c211la/6F4CC01CA4A6/LINUXMINT-20.3/5.4.0-96-GENERIC/X86_64/BFDC2533BB>) |
| 1022:7814 | 103c:8245 | AMD              | FCH USB XHCI Controller              | 15    | xhci_hcd   | [BFDC2533BB](<All In One/Hewlett-Packard/20/20-c211la/6F4CC01CA4A6/LINUXMINT-20.3/5.4.0-96-GENERIC/X86_64/BFDC2533BB>) |
| 8086:1c26 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 14    | ehci_hc... | [485E063883](<All In One/Lenovo/C340/C340 10102/B4F39330CA94/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/485E063883>) |
| 8086:1c2d | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 14    | ehci_hc... | [485E063883](<All In One/Lenovo/C340/C340 10102/B4F39330CA94/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/485E063883>) |
| 8086:9d2f | 103c:84de | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 14    | xhci_hcd   | [43184FD6BF](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/3E27DCFED7C5/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/43184FD6BF>) |
| 1b6f:7023 | 1025:8030 | Etron Technology | EJ168 USB 3.0 Host Controller        | 13    | xhci_hcd   | [520A9BC6A0](<All In One/Acer/Aspire/Aspire ZS600/307894E2C20C/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/520A9BC6A0>) |
| 8086:1c26 | 1028:0511 | Intel            | 6 Series/C200 Series Chipset Fami... | 12    | ehci_pci   | [6008FDA2AD](<All In One/Dell/Inspiron/Inspiron One 2320/61122D664D9D/UBUNTU-21.10/5.13.0-23-GENERIC/X86_64/6008FDA2AD>) |
| 8086:1c2d | 1028:0511 | Intel            | 6 Series/C200 Series Chipset Fami... | 12    | ehci_pci   | [6008FDA2AD](<All In One/Dell/Inspiron/Inspiron One 2320/61122D664D9D/UBUNTU-21.10/5.13.0-23-GENERIC/X86_64/6008FDA2AD>) |
| 8086:1e26 | 1028:0543 | Intel            | 7 Series/C216 Chipset Family USB ... | 12    | ehci_pci   | [F92FA1F111](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/04BEB2B29F37/CLEAR-LINUX-OS-35190/5.13.13-1070.NATIVE/X86_64/F92FA1F111>) |
| 8086:1e26 | 1028:0548 | Intel            | 7 Series/C216 Chipset Family USB ... | 12    | ehci_pci   | [6D6980BC69](<All In One/Dell/Inspiron/Inspiron One 2330/CC15798AE672/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/6D6980BC69>) |
| 8086:1e2d | 1028:0543 | Intel            | 7 Series/C216 Chipset Family USB ... | 12    | ehci_pci   | [F92FA1F111](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/04BEB2B29F37/CLEAR-LINUX-OS-35190/5.13.13-1070.NATIVE/X86_64/F92FA1F111>) |
| 8086:1e2d | 1028:0548 | Intel            | 7 Series/C216 Chipset Family USB ... | 12    | ehci_pci   | [6D6980BC69](<All In One/Dell/Inspiron/Inspiron One 2330/CC15798AE672/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/6D6980BC69>) |
| 8086:1e31 | 1028:0543 | Intel            | 7 Series/C210 Series Chipset Fami... | 12    | xhci_hcd   | [F92FA1F111](<All In One/Dell/OptiPlex/OptiPlex 9010 AIO/04BEB2B29F37/CLEAR-LINUX-OS-35190/5.13.13-1070.NATIVE/X86_64/F92FA1F111>) |
| 8086:1e31 | 1028:0548 | Intel            | 7 Series/C210 Series Chipset Fami... | 12    | xhci_hcd   | [6D6980BC69](<All In One/Dell/Inspiron/Inspiron One 2330/CC15798AE672/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/6D6980BC69>) |
| 1022:7908 | 103c:8381 | AMD              | FCH USB EHCI Controller              | 11    | ehci_pci   | [0DC8027649](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/B4EEA135048F/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/0DC8027649>) |
| 1022:7914 | 103c:8381 | AMD              | FCH USB XHCI Controller              | 11    | xhci_hcd   | [0DC8027649](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-e0XX/B4EEA135048F/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/0DC8027649>) |
| 8086:1c26 | 103c:2ac5 | Intel            | 6 Series/C200 Series Chipset Fami... | 11    | ehci_pci   | [DF20701C5E](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/2B14E403FA28/DEBIAN-10/5.10.0-0.BPO.3-AMD64/X86_64/DF20701C5E>) |
| 8086:1c2d | 103c:2ac5 | Intel            | 6 Series/C200 Series Chipset Fami... | 11    | ehci_pci   | [DF20701C5E](<All In One/Hewlett-Packard/Pro/Pro 3420 AiO PC/2B14E403FA28/DEBIAN-10/5.10.0-0.BPO.3-AMD64/X86_64/DF20701C5E>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:8d7c | 8086:7270 | Intel            | C610/X99 series chipset SPSR         | 1     |            | [B2AD449201](<All In One/Acidanthera/iMacPro1/iMacPro1,1/02ABD56D98BC/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/B2AD449201>) |

