Most popular PCI devices in Mini Pcs
====================================

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Mini Pcs ](#pci-devices)
   * [ Bluetooth ](#bluetooth-pci)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Dma controller (eisa dma) ](#dma-controller-eisa-dma-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Firewire controller ](#firewire-controller-pci)
   * [ Generic system peripheral ](#generic-system-peripheral-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Iommu ](#iommu-pci)
   * [ Ipmi interface (kcs) ](#ipmi-interface-kcs-pci)
   * [ Ipmi smic interface ](#ipmi-smic-interface-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Multimedia ](#multimedia-pci)
   * [ Multimedia controller ](#multimedia-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Non-essential instrumentation ](#non-essential-instrumentation-pci)
   * [ Non-vga unclassified device ](#non-vga-unclassified-device-pci)
   * [ Performance counters ](#performance-counters-pci)
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
   * [ Tv card ](#tv-card-pci)
   * [ Unclassified device ](#unclassified-device-pci)
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
| 1814:3298 | 1a3b:2987 | Ralink           | RT3290 Bluetooth                     | 3     |            | [121F403E29](<Mini Pc/ZOTAC/ZBOXNANO-AD/ZBOXNANO-AD10/F40922BC09C5/POP!_OS-20.04/5.4.0-7634-GENERIC/X86_64/121F403E29>) |

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d84 | 8086:2074 | Intel            | Cannon Point-LP LPC Controller       | 156   |            | [C79A71B9DB](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/C0AF1D599D12/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C79A71B9DB>) |
| 8086:9db8 | 8086:2074 | Intel            | Cannon Point-LP PCI Express Root ... | 154   | pcieport   | [C79A71B9DB](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/C0AF1D599D12/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C79A71B9DB>) |
| 8086:9dbc | 8086:2074 | Intel            | Cannon Point-LP PCI Express Root ... | 154   | pcieport   | [C79A71B9DB](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/C0AF1D599D12/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C79A71B9DB>) |
| 8086:9db0 | 8086:2074 | Intel            | Cannon Point-LP PCI Express Root ... | 153   | pcieport   | [C79A71B9DB](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/C0AF1D599D12/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C79A71B9DB>) |
| 8086:9db6 | 8086:2074 | Intel            | Cannon Point-LP PCI Express Root ... | 152   | pcieport   | [C79A71B9DB](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/C0AF1D599D12/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C79A71B9DB>) |
| 8086:3ed0 | 8086:2074 | Intel            | 8th Gen Core Processor Host Bridg... | 110   | skl_uncore | [C79A71B9DB](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/C0AF1D599D12/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C79A71B9DB>) |
| 8086:0284 | 8086:2081 | Intel            | Comet Lake PCH-LP LPC Premium Con... | 89    |            | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:02b5 | 8086:2081 | Intel            | Comet Lake PCH-LP PCIe Port #14      | 86    | pcieport   | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:02bc | 8086:2081 | Intel            | Comet Lake PCI Express Root Port #5  | 86    | pcieport   | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:15e7 | 8086:2081 | Intel            | JHL7540 Thunderbolt 3 Bridge [Tit... | 86    | pcieport   | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:0f00 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 80    | iosf_mb... | [BF7C2C6D9B](<Mini Pc/NEXCOM/VTC/VTC1010/6EF054560413/DEBIAN-11/5.10.0-11-AMD64/X86_64/BF7C2C6D9B>) |
| 8086:0f1c | 8086:0f1c | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 79    | lpc_ich    | [BF7C2C6D9B](<Mini Pc/NEXCOM/VTC/VTC1010/6EF054560413/DEBIAN-11/5.10.0-11-AMD64/X86_64/BF7C2C6D9B>) |
| 8086:5904 | 8086:2068 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 79    | skl_uncore | [7F8770AFC4](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/38F8ADEA821D/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/7F8770AFC4>) |
| 8086:9d10 | 8086:2068 | Intel            | Sunrise Point-LP PCI Express Root... | 79    | pcieport   | [7F8770AFC4](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/38F8ADEA821D/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/7F8770AFC4>) |
| 8086:9d4e | 8086:2068 | Intel            | Sunrise Point LPC Controller/eSPI... | 79    |            | [7F8770AFC4](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/38F8ADEA821D/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/7F8770AFC4>) |
| 8086:9d17 | 8086:2068 | Intel            | Sunrise Point-LP PCI Express Root... | 77    | pcieport   | [7F8770AFC4](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/38F8ADEA821D/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/7F8770AFC4>) |
| 8086:9d15 | 8086:2068 | Intel            | Sunrise Point-LP PCI Express Root... | 75    | pcieport   | [7F8770AFC4](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/38F8ADEA821D/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/7F8770AFC4>) |
| 8086:02b0 | 8086:2081 | Intel            | Comet Lake PCI Express Root Port #9  | 70    | pcieport   | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:1604 | 8086:2057 | Intel            | Broadwell-U Host Bridge -OPI         | 54    | bdw_uncore | [CEA504B47D](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-503/F250AC8777D6/CENTOS-STREAM/4.18.0-348.2.1.EL8_5.X86_64/X86_64/CEA504B47D>) |
| 104c:823e |           | Texas Instrum... | XIO2213A/B/XIO2221 PCI Express to... | 53    | shpchp     | [D7F1687670](<Mini Pc/Apple/Macmini4/Macmini4,1/BCBD7A97BE65/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D7F1687670>) |
| 8086:1e10 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family PCI ... | 53    | pcieport   | [C3A014CA22](<Mini Pc/Apple/Macmini6/Macmini6,2/F5E3810853BC/CLEAR-LINUX-OS-35970/5.13.13-1070.NATIVE/X86_64/C3A014CA22>) |
| 8086:9b51 | 8086:2081 | Intel            | Comet Lake-U v1 6c Host Bridge/DR... | 53    | skl_uncore | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:9c90 | 8086:2057 | Intel            | Wildcat Point-LP PCI Express Root... | 53    | pcieport   | [CEA504B47D](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-503/F250AC8777D6/CENTOS-STREAM/4.18.0-348.2.1.EL8_5.X86_64/X86_64/CEA504B47D>) |
| 8086:9cc3 | 8086:2057 | Intel            | Wildcat Point-LP LPC Controller      | 53    | lpc_ich    | [CEA504B47D](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-503/F250AC8777D6/CENTOS-STREAM/4.18.0-348.2.1.EL8_5.X86_64/X86_64/CEA504B47D>) |
| 8086:1e12 | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 52    | pcieport   | [C3A014CA22](<Mini Pc/Apple/Macmini6/Macmini6,2/F5E3810853BC/CLEAR-LINUX-OS-35970/5.13.13-1070.NATIVE/X86_64/C3A014CA22>) |
| 8086:9c96 | 8086:2057 | Intel            | Wildcat Point-LP PCI Express Root... | 52    | pcieport   | [CEA504B47D](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-503/F250AC8777D6/CENTOS-STREAM/4.18.0-348.2.1.EL8_5.X86_64/X86_64/CEA504B47D>) |
| 8086:1e14 | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 51    | pcieport   | [C3A014CA22](<Mini Pc/Apple/Macmini6/Macmini6,2/F5E3810853BC/CLEAR-LINUX-OS-35970/5.13.13-1070.NATIVE/X86_64/C3A014CA22>) |
| 8086:1547 | 2222:1111 | Intel            | DSL3510 Thunderbolt Controller [C... | 50    | pcieport   | [C3A014CA22](<Mini Pc/Apple/Macmini6/Macmini6,2/F5E3810853BC/CLEAR-LINUX-OS-35970/5.13.13-1070.NATIVE/X86_64/C3A014CA22>) |
| 8086:1e57 | 8086:7270 | Intel            | HM77 Express Chipset LPC Controller  | 50    | lpc_ich    | [C3A014CA22](<Mini Pc/Apple/Macmini6/Macmini6,2/F5E3810853BC/CLEAR-LINUX-OS-35970/5.13.13-1070.NATIVE/X86_64/C3A014CA22>) |
| 8086:15da | 8086:2074 | Intel            | JHL6340 Thunderbolt 3 Bridge (C s... | 46    | pcieport   | [F72047DC6D](<Mini Pc/Intel Client Systems/NUC8/NUC8i7BEH/CB26D11F0398/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/F72047DC6D>) |
| 8086:3ecc | 8086:2074 | Intel            | Coffee Lake Host Bridge/DRAM Regi... | 46    | skl_uncore | [849A97D8C3](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/C1EBC5D5D8E2/DEBIAN-11/5.10.0-11-AMD64/X86_64/849A97D8C3>) |
| 8086:0f48 | 8086:0f48 | Intel            | Atom Processor E3800 Series PCI E... | 44    | pcieport   | [BF7C2C6D9B](<Mini Pc/NEXCOM/VTC/VTC1010/6EF054560413/DEBIAN-11/5.10.0-11-AMD64/X86_64/BF7C2C6D9B>) |
| 8086:5af0 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 44    |            | [5BEEF7A5B1](<Mini Pc/Intel/NUC6/NUC6CAYH/0C6F2967B76D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5BEEF7A5B1>) |
| 1022:1632 |           | AMD              | Renoir PCIe Dummy Host Bridge        | 43    |            | [8A85AEAF5A](<Mini Pc/AZW/GTR/GTR/BB648F57E2C2/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/8A85AEAF5A>) |
| 8086:0f4a | 8086:0f4a | Intel            | Atom Processor E3800 Series PCI E... | 43    | pcieport   | [BF7C2C6D9B](<Mini Pc/NEXCOM/VTC/VTC1010/6EF054560413/DEBIAN-11/5.10.0-11-AMD64/X86_64/BF7C2C6D9B>) |
| 8086:0f4c | 8086:0f4c | Intel            | Atom Processor E3800 Series PCI E... | 43    | pcieport   | [BF7C2C6D9B](<Mini Pc/NEXCOM/VTC/VTC1010/6EF054560413/DEBIAN-11/5.10.0-11-AMD64/X86_64/BF7C2C6D9B>) |
| 8086:5ae8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 43    | lpc_ich    | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 8086:5af0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 43    |            | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 1022:1630 | 1022:1630 | AMD              | Renoir/Cezanne Root Complex          | 42    |            | [8A85AEAF5A](<Mini Pc/AZW/GTR/GTR/BB648F57E2C2/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/8A85AEAF5A>) |
| 1022:1635 | 1022:1635 | AMD              | Renoir Internal PCIe GPP Bridge t... | 42    | pcieport   | [8A85AEAF5A](<Mini Pc/AZW/GTR/GTR/BB648F57E2C2/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/8A85AEAF5A>) |
| 8086:0f4e | 8086:0f4e | Intel            | Atom Processor E3800 Series PCI E... | 42    | pcieport   | [BF7C2C6D9B](<Mini Pc/NEXCOM/VTC/VTC1010/6EF054560413/DEBIAN-11/5.10.0-11-AMD64/X86_64/BF7C2C6D9B>) |
| 1022:1448 |           | AMD              | Renoir Device 24: Function 0         | 39    |            | [2F6DF3FFF6](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/86C8213ACE93/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2F6DF3FFF6>) |
| 1022:1449 |           | AMD              | Renoir Device 24: Function 1         | 39    |            | [2F6DF3FFF6](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/86C8213ACE93/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2F6DF3FFF6>) |
| 1022:144a |           | AMD              | Renoir Device 24: Function 2         | 39    |            | [2F6DF3FFF6](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/86C8213ACE93/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2F6DF3FFF6>) |
| 1022:144b |           | AMD              | Renoir Device 24: Function 3         | 39    | k10temp    | [2F6DF3FFF6](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/86C8213ACE93/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2F6DF3FFF6>) |
| 1022:144c |           | AMD              | Renoir Device 24: Function 4         | 39    |            | [2F6DF3FFF6](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/86C8213ACE93/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2F6DF3FFF6>) |
| 1022:144d |           | AMD              | Renoir Device 24: Function 5         | 39    |            | [2F6DF3FFF6](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/86C8213ACE93/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2F6DF3FFF6>) |
| 1022:144e |           | AMD              | Renoir Device 24: Function 6         | 39    |            | [2F6DF3FFF6](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/86C8213ACE93/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2F6DF3FFF6>) |
| 1022:144f |           | AMD              | Renoir Device 24: Function 7         | 39    |            | [2F6DF3FFF6](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/86C8213ACE93/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2F6DF3FFF6>) |
| 8086:1513 |           | Intel            | CV82524 Thunderbolt Controller [L... | 39    | pcieport   | [703034E8C4](<Mini Pc/Apple/Macmini6/Macmini6,2/122FDC1BF87C/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/703034E8C4>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:522a | 8086:2074 | Realtek Semic... | RTS522A PCI Express Card Reader      | 152   | rtsx_pci   | [C79A71B9DB](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/C0AF1D599D12/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C79A71B9DB>) |
| 10ec:5229 | 8086:2068 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 77    | rtsx_pci   | [7F8770AFC4](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/38F8ADEA821D/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/7F8770AFC4>) |
| 10ec:5229 | 8086:2072 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 36    | rtsx_pci   | [E02C6336D6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/3F30AC0E5D22/ARTIX-ROLLING/5.16.3-ARTIX1-1/X86_64/E02C6336D6>) |
| 10ec:5229 | 8086:2067 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 35    | rtsx_pci   | [5BEEF7A5B1](<Mini Pc/Intel/NUC6/NUC6CAYH/0C6F2967B76D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5BEEF7A5B1>) |
| 10ec:525a | 8086:3004 | Realtek Semic... | RTS525A PCI Express Card Reader      | 14    | rtsx_pci   | [9EB75AB42F](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/4076B509F693/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/9EB75AB42F>) |
| 10ec:5229 | 10ec:5229 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [45B14891D4](<Mini Pc/Intel Client Systems/NUC8/NUC8i5INH/CFC9656AFB5C/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/45B14891D4>) |
| 10ec:525a | 10ec:525a | Realtek Semic... | RTS525A PCI Express Card Reader      | 2     | rtsx_pci   | [7F8E6D2DA9](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/A868B36AB404/ARCO-ROLLING/5.13.13-ARCH1-1/X86_64/7F8E6D2DA9>) |
| 10ec:522a | 103c:815a | Realtek Semic... | RTS522A PCI Express Card Reader      | 1     | rtsx_pci   | [7D65A83025](<Mini Pc/Hewlett-Packard/mt42/mt42 Mobile Thin Client/A398497B20DA/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/7D65A83025>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10de:0aa3 | 10de:cb79 | Nvidia           | MCP79 Co-processor                   | 26    | nvidia     | [F114F6EA54](<Mini Pc/Apple/Macmini3/Macmini3,1/C67829525D2F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F114F6EA54>) |
| 10de:0d7a | 10de:cb89 | Nvidia           | MCP89 Co-Processor                   | 16    |            | [D7F1687670](<Mini Pc/Apple/Macmini4/Macmini4,1/BCBD7A97BE65/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D7F1687670>) |
| 8086:1f18 | 8086:0000 | Intel            | Atom processor C2000 QAT             | 2     |            | [C1D37659C1](<Mini Pc/Supermicro/A1/A1SAi/F097711C2215/GENTOO-2.6/5.4.86-GENTOO/X86_64/C1D37659C1>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9de0 | 8086:2074 | Intel            | Cannon Point-LP MEI Controller #1    | 156   | mei_me     | [C79A71B9DB](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/C0AF1D599D12/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C79A71B9DB>) |
| 8086:02e0 | 8086:2081 | Intel            | Comet Lake Management Engine Inte... | 89    | mei_me     | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:9d3a | 8086:2068 | Intel            | Sunrise Point-LP CSME HECI #1        | 78    | mei_me     | [7F8770AFC4](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/38F8ADEA821D/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/7F8770AFC4>) |
| 8086:9cba | 8086:2057 | Intel            | Wildcat Point-LP MEI Controller #1   | 54    | mei_me     | [CEA504B47D](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-503/F250AC8777D6/CENTOS-STREAM/4.18.0-348.2.1.EL8_5.X86_64/X86_64/CEA504B47D>) |
| 8086:1e3a | 8086:7270 | Intel            | 7 Series/C216 Chipset Family MEI ... | 53    | mei_me     | [C3A014CA22](<Mini Pc/Apple/Macmini6/Macmini6,2/F5E3810853BC/CLEAR-LINUX-OS-35970/5.13.13-1070.NATIVE/X86_64/C3A014CA22>) |
| 8086:5a9a |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 45    | mei_me     | [5BEEF7A5B1](<Mini Pc/Intel/NUC6/NUC6CAYH/0C6F2967B76D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5BEEF7A5B1>) |
| 8086:5a9a | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 42    | mei_me     | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 8086:a13a | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 38    | mei_me     | [317E098A9E](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/A75259B85C6D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/317E098A9E>) |
| 8086:1c3a | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 37    | mei_me     | [A2BA361F2C](<Mini Pc/Apple/Macmini5/Macmini5,1/C29061AA8B1E/ZORIN-16/5.11.0-43-GENERIC/X86_64/A2BA361F2C>) |
| 8086:319a | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 37    | mei_me     | [E02C6336D6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/3F30AC0E5D22/ARTIX-ROLLING/5.16.3-ARTIX1-1/X86_64/E02C6336D6>) |
| 8086:9c3a | 8086:7270 | Intel            | 8 Series HECI #0                     | 37    | mei_me     | [5550136FFD](<Mini Pc/Apple/Macmini7/Macmini7,1/65598A0C8936/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/5550136FFD>) |
| 8086:a13a | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 29    | mei_me     | [86D379E9D5](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/54383D955906/UBUNTU-20.10/5.8.0-63-GENERIC/X86_64/86D379E9D5>) |
| 8086:9d3a | 8086:2063 | Intel            | Sunrise Point-LP CSME HECI #1        | 19    | mei_me     | [6879986BF2](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-505/29B4250B3145/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/6879986BF2>) |
| 8086:9d3a | 8086:2070 | Intel            | Sunrise Point-LP CSME HECI #1        | 17    | mei_me     | [0261508BA5](<Mini Pc/Intel Client Systems/NUC7/NUC7i3DNHE/F93E47848AEB/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/0261508BA5>) |
| 8086:a0e0 | 8086:3004 | Intel            | Tiger Lake-LP Management Engine I... | 15    | mei_me     | [CA53435B36](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/26774C86D363/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/CA53435B36>) |
| 8086:a360 | 17aa:312d | Intel            | Cannon Lake PCH HECI Controller      | 15    | mei_me     | [88A943EC80](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T700BHBL/970C8BB93481/DEBIAN-11/5.10.0-11-AMD64/X86_64/88A943EC80>) |
| 8086:319a | 1043:875e | Intel            | Celeron/Pentium Silver Processor ... | 13    | mei_me     | [27BB88805D](<Mini Pc/ASUSTek Computer/PN/PN40/21E857FB29E9/CENTOS-7/3.10.0-1160.53.1.EL7.X86_64/X86_64/27BB88805D>) |
| 8086:319a | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 13    | mei_me     | [76B5667130](<Mini Pc/MeLE Computer/Quieter/Quieter2/73E8BF27E06D/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/76B5667130>) |
| 8086:5a9c |           | Intel            | Communication controller             | 13    |            | [94EB262136](<Mini Pc/Intel/NUC6/NUC6CAYH/64D04D5AA3BE/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/94EB262136>) |
| 8086:5a9e |           | Intel            | Communication controller             | 13    |            | [94EB262136](<Mini Pc/Intel/NUC6/NUC6CAYH/64D04D5AA3BE/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/94EB262136>) |
| 8086:319a | 8086:319a | Intel            | Celeron/Pentium Silver Processor ... | 12    | mei_me     | [B78185D870](<Mini Pc/Chuwi/HeroBox/HeroBox/0564D825BBAD/DEBIAN-11/5.15.0-0.BPO.3-AMD64/X86_64/B78185D870>) |
| 8086:9d3a | 8086:1999 | Intel            | Sunrise Point-LP CSME HECI #1        | 9     | mei_me     | [E4BBE42B5A](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/33AEB9BBD609/DEBIAN-11/5.10.0-11-AMD64/X86_64/E4BBE42B5A>) |
| 8086:9cba | 8086:7270 | Intel            | Wildcat Point-LP MEI Controller #1   | 8     | mei_me     | [0A76AC3FB8](<Mini Pc/AZW/U/U55/BDB0C02F8F71/MANJARO/5.13.19-2-MANJARO/X86_64/0A76AC3FB8>) |
| 8086:a2ba | 103c:829a | Intel            | 200 Series PCH CSME HECI #1          | 8     | mei_me     | [67A56E0954](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/8143DA8FF5D3/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/67A56E0954>) |
| 8086:a328 | 8086:7270 | Intel            | Cannon Lake PCH Serial IO UART Ho... | 8     | intel_l... | [CA26CBBF22](<Mini Pc/Apple/Macmini8/Macmini8,1/F39A3C4B83EB/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/CA26CBBF22>) |
| 8086:a360 | 17aa:3135 | Intel            | Cannon Lake PCH HECI Controller      | 8     | mei_me     | [C43EF85B97](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920x 10S1S07700/59BDC87984FB/ROSA-2016.1/5.4.40-GENERIC-1ROSA-X86_64/X86_64/C43EF85B97>) |
| 8086:a360 | 8086:7270 | Intel            | Cannon Lake PCH HECI Controller      | 8     | mei_me     | [CA26CBBF22](<Mini Pc/Apple/Macmini8/Macmini8,1/F39A3C4B83EB/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/CA26CBBF22>) |
| 8086:a13a | 19da:b333 | Intel            | 100 Series/C230 Series Chipset Fa... | 7     | mei_me     | [7348D34142](<Mini Pc/ZOTAC/ZBOX-EN1070/ZBOX-EN1070-1060/0CBF4FF1BBBE/LINUXMINT-20.2/5.13.0-22-GENERIC/X86_64/7348D34142>) |
| 8086:a360 | 17aa:3136 | Intel            | Cannon Lake PCH HECI Controller      | 7     | mei_me     | [B3BA67D085](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10V8S06904/EAA513742A16/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/B3BA67D085>) |
| 8086:9cba | 8086:2058 | Intel            | Wildcat Point-LP MEI Controller #1   | 6     | mei_me     | [ABF846A2C2](<Mini Pc/Intel/NUC5i3MYBE/NUC5i3MYBE H47781-202/BBE07E7A6081/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/ABF846A2C2>) |
| 8086:9de0 | 17aa:314d | Intel            | Cannon Point-LP MEI Controller #1    | 6     | mei_me     | [BD2F6222E5](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AD002DGE/D203F33318BC/MANJARO-21.1.0/5.10.53-1-MANJARO/X86_64/BD2F6222E5>) |
| 8086:a328 | 8086:2089 | Intel            | Cannon Lake PCH Serial IO UART Ho... | 6     | intel_l... | [EFF399191D](<Mini Pc/Intel Client Systems/NUC9/NUC9i9QNX/519180459546/UBUNTU-20.04/5.13.0-25-GENERIC/X86_64/EFF399191D>) |
| 8086:a360 | 8086:2089 | Intel            | Cannon Lake PCH HECI Controller      | 6     | mei_me     | [EFF399191D](<Mini Pc/Intel Client Systems/NUC9/NUC9i9QNX/519180459546/UBUNTU-20.04/5.13.0-25-GENERIC/X86_64/EFF399191D>) |
| 8086:4da8 | 1043:8813 | Intel            | Jasper Lake LPSS: UART Controller #0 | 5     | intel_l... | [B416BA575D](<Mini Pc/ASUSTek Computer/PN/PN41/20388AD561BB/ZORIN-16/5.13.0-30-GENERIC/X86_64/B416BA575D>) |
| 8086:4de0 | 1043:8813 | Intel            | Management Engine Interface          | 5     | mei_me     | [B416BA575D](<Mini Pc/ASUSTek Computer/PN/PN41/20388AD561BB/ZORIN-16/5.13.0-30-GENERIC/X86_64/B416BA575D>) |
| 8086:a2ba | 103c:82a5 | Intel            | 200 Series PCH CSME HECI #1          | 5     | mei_me     | [C47D9B3AE0](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 400 G3 DM/342D63741B55/ELEMENTARY-6.1/5.13.0-28-GENERIC/X86_64/C47D9B3AE0>) |
| 8086:a2ba | 17aa:3111 | Intel            | 200 Series PCH CSME HECI #1          | 5     | mei_me     | [B9D4EFB68C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MR000XUK/3928CECFA48F/POP!_OS-21.10/5.15.15-76051515-GENERIC/X86_64/B9D4EFB68C>) |
| 8086:02e0 | 1043:87bd | Intel            | Comet Lake Management Engine Inte... | 4     | mei_me     | [7A01C63401](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN62S/469668D35D11/DEBIAN-11/5.10.0-8-AMD64/X86_64/7A01C63401>) |
| 8086:06e0 | 17aa:316e | Intel            | Comet Lake HECI Controller           | 4     | mei_me     | [0224398912](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DUS4SQ00/DA9A8078DC3D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/0224398912>) |
| 8086:1e3a | 19da:b211 | Intel            | 7 Series/C216 Chipset Family MEI ... | 4     | mei_me     | [EFBBD0C3F8](<Mini Pc/ZOTAC/ZBOX-ID/ZBOX-ID18/48784B911DCF/UBUNTU-20.04/5.8.0-43-GENERIC/X86_64/EFBBD0C3F8>) |
| 8086:5a9a | 8086:5a9a | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | mei_me     | [6874BC3566](<Mini Pc/BESSTAR Tech/N/N33/2A74991B0C12/UBUNTU-20.04/5.11.0-44-GENERIC/X86_64/6874BC3566>) |
| 8086:8c3a | 19da:b220 | Intel            | 8 Series/C220 Series Chipset Fami... | 4     | mei_me     | [FCAA602427](<Mini Pc/ZOTAC/ZBOX-ID92/ZBOX-ID92-ZBOX-IQ01/502C1C75B175/KUBUNTU-20.10/5.8.0-41-GENERIC/X86_64/FCAA602427>) |
| 8086:9d3a | 103c:84f5 | Intel            | Sunrise Point-LP CSME HECI #1        | 4     | mei_me     | [CF5DEA43E1](<Mini Pc/Hewlett-Packard/260/260 G3 DM/D334B500C95E/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/CF5DEA43E1>) |
| 8086:a13a | 103c:82c0 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     | mei_me     | [AC904E9BCB](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G3 Workstation/90A7B6AE2869/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/AC904E9BCB>) |
| 8086:02e0 | 8086:7270 | Intel            | Comet Lake Management Engine Inte... | 3     | mei_me     | [934F2F075C](<Mini Pc/AZW/SEi/SEi/2957B295DEBC/LINUXMINT-20/5.4.0-90-GENERIC/X86_64/934F2F075C>) |
| 8086:06e0 | 17aa:3172 | Intel            | Comet Lake HECI Controller           | 3     | mei_me     | [EE32355409](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/EE29838C95B5/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/EE32355409>) |
| 8086:1e3a | 19da:a247 | Intel            | 7 Series/C216 Chipset Family MEI ... | 3     | mei_me     | [306FBC1B87](<Mini Pc/ZOTAC/ZBOXNANO-ID/ZBOXNANO-ID62/900EE78FB205/ZORIN-16/5.11.0-38-GENERIC/X86_64/306FBC1B87>) |
| 8086:a0e0 | 8086:2090 | Intel            | Tiger Lake-LP Management Engine I... | 3     | mei_me     | [1158CBFEAA](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/894923AF1BC3/DEBIAN-11/5.10.0-10-AMD64/X86_64/1158CBFEAA>) |
| 8086:a0e0 | 8086:3002 | Intel            | Tiger Lake-LP Management Engine I... | 3     | mei_me     | [23FCE48DF7](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKi7/5BE9775954D9/FEDORA-35/5.16.5-200.FC35.X86_64/X86_64/23FCE48DF7>) |
| 8086:a13a | 15d9:0898 | Intel            | 100 Series/C230 Series Chipset Fa... | 3     | mei_me     | [8D4CBF243D](<Mini Pc/Supermicro/SYS-5039/SYS-5039MS-H12TRF/C29A8D8B7AFC/ROSA-2021.1/5.10.56-GENERIC-1ROSA2021.1-X86_64/X86_64/8D4CBF243D>) |

### Dma controller (eisa dma) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:22c0 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 22    | dw_dmac... | [207E311CFC](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-102/8054EC01AC51/ASTRALINUXCE-2.12.44/5.10.0-1038.40-GENERIC/X86_64/207E311CFC>) |
| 8086:0f06 |           | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | dw_dmac... | [BF7C2C6D9B](<Mini Pc/NEXCOM/VTC/VTC1010/6EF054560413/DEBIAN-11/5.10.0-11-AMD64/X86_64/BF7C2C6D9B>) |
| 8086:0f06 | 8086:0f06 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | dw_dmac... | [A968EF1DD8](<Mini Pc/HPE/EL/EL10/3097F99AD33E/OPENSUSE-LEAP-15.0/4.12.14-LP150.11-DEFAULT/X86_64/A968EF1DD8>) |
| 8086:0f40 | 8086:0f40 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | dw_dmac... | [BF7C2C6D9B](<Mini Pc/NEXCOM/VTC/VTC1010/6EF054560413/DEBIAN-11/5.10.0-11-AMD64/X86_64/BF7C2C6D9B>) |
| 8086:2286 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | dw_dmac... | [10C1838B9D](<Mini Pc/AMI/Aptio/Aptio CRB/6C7827486731/DEBIAN-11/5.10.0-8-AMD64/X86_64/10C1838B9D>) |
| 8086:22c0 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | dw_dmac... | [10C1838B9D](<Mini Pc/AMI/Aptio/Aptio CRB/6C7827486731/DEBIAN-11/5.10.0-8-AMD64/X86_64/10C1838B9D>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0f18 | 8086:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 80    | mei_txe    | [BF7C2C6D9B](<Mini Pc/NEXCOM/VTC/VTC1010/6EF054560413/DEBIAN-11/5.10.0-11-AMD64/X86_64/BF7C2C6D9B>) |
| 1022:15df | 1022:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 51    | ccp        | [8A85AEAF5A](<Mini Pc/AZW/GTR/GTR/BB648F57E2C2/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/8A85AEAF5A>) |
| 8086:2298 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 38    | mei_txe    | [207E311CFC](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-102/8054EC01AC51/ASTRALINUXCE-2.12.44/5.10.0-1038.40-GENERIC/X86_64/207E311CFC>) |
| 8086:2298 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 33    | mei_txe    | [CDDC590270](<Mini Pc/BESSTAR Tech/Z83/Z83-F/833154D27E3C/ZORIN-16/5.13.0-30-GENERIC/X86_64/CDDC590270>) |
| 1022:1578 | 1022:1578 | AMD              | Carrizo Platform Security Processor  | 18    |            | [3C277DC3C1](<Mini Pc/Hewlett-Packard/t530/t530 Thin Client/982DFBB69A90/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3C277DC3C1>) |
| 8086:0f18 | 17aa:368d | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 11    | mei_txe    | [03220F70D0](<Mini Pc/Lenovo/E50-00/E50-00 90BX003VUL/536000E6D70F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/03220F70D0>) |
| 1022:15df | 103c:872e | AMD              | Family 17h (Models 10h-1fh) Platf... | 9     | ccp        | [8366A84CDB](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/F373E702B28B/XUBUNTU-20.04/5.13.0-28-GENERIC/X86_64/8366A84CDB>) |
| 8086:0f18 |           | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | mei_txe    | [2882CF9963](<Mini Pc/NOBLEX/NB/NB1602/840F6A17AA98/DEBIAN-11/5.10.0-8-AMD64/X86_64/2882CF9963>) |
| 8086:2298 | 17aa:30dd | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | mei_txe    | [BD46C4BAC3](<Mini Pc/Lenovo/S200z/S200z 10HA000FRU/0E3D6DC0E64D/UBUNTU-20.04/5.4.0-99-GENERIC/X86_64/BD46C4BAC3>) |
| 8086:2298 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | mei_txe    | [175DDA01F6](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/92EB5D9C4CEF/LUBUNTU-20.04/5.4.0-91-GENERIC/X86_64/175DDA01F6>) |
| 1022:15df | 103c:8836 | AMD              | Family 17h (Models 10h-1fh) Platf... | 4     | ccp        | [DA34E7C710](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/DD273ADCD4AF/XUBUNTU-20.04/5.8.0-53-GENERIC/X86_64/DA34E7C710>) |
| 8086:0f18 | 19da:b219 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 4     | mei_txe    | [34EFC38E50](<Mini Pc/ZOTAC/ZBOX-CI320NANO/ZBOX-CI320NANO series/5BD80C26892B/XUBUNTU-18.04/4.15.0-139-GENERIC/X86_64/34EFC38E50>) |
| 8086:2298 | 17aa:3637 | Intel            | Atom/Celeron/Pentium Processor x5... | 4     | mei_txe    | [9FC0FE4A5F](<Mini Pc/Lenovo/C20-00/C20-00 F0BB00VCAU/1522F026E3A1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/9FC0FE4A5F>) |
| 8086:2298 | 19da:b273 | Intel            | Atom/Celeron/Pentium Processor x5... | 4     | mei_txe    | [0D05B404DD](<Mini Pc/ZOTAC/ZBOX-BI/ZBOX-BI324/C214E8207F22/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/0D05B404DD>) |
| 8086:0f18 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     | mei_txe    | [EED35A825A](<Mini Pc/AMI/Aptio/Aptio CRB/2ED6AEE7BDE7/GENTOO-2.7/5.10.7/X86_64/EED35A825A>) |
| 8086:2298 | 1462:b120 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | mei_txe    | [FDE91E565C](<Mini Pc/MSI/MS-B/MS-B120/B29C493EAF7D/UBUNTU-18.04/5.3.0-28-GENERIC/X86_64/FDE91E565C>) |
| 1022:15df | 103c:872c | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     | ccp        | [36F1254C43](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 805 G6 Desktop Mini PC/20C32FFA6ABD/CENTOS-7/5.15.1-1.EL7.ELREPO.X86_64/X86_64/36F1254C43>) |
| 1022:15df | 17aa:3181 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     | ccp        | [56F9A83D77](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75n 11GW000BUS/8D95E87EDCE7/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/56F9A83D77>) |
| 8086:0f18 | 1071:0730 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | mei_txe    | [BE63E554C5](<Mini Pc/AMI/Aptio/Aptio CRB/3075E71938D1/UBUNTU-19.04/5.0.0-29-GENERIC/X86_64/BE63E554C5>) |
| 8086:2298 | 1028:07c1 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | mei_txe    | [74450C0224](<Mini Pc/Dell/Wyse/Wyse 3040 Thin Client/159E337F7751/DEBIAN-11/5.10.0-11-AMD64/X86_64/74450C0224>) |
| 8086:2298 | 8086:2298 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | mei_txe    | [3AB4853FDD](<Mini Pc/BESSTAR Tech/GN/GN31/FCAF87D82341/DEBIAN-10/5.4.78-2-PVE/X86_64/3AB4853FDD>) |
| 1022:15df | 103c:8523 | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     |            | [BAB721D52E](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/FB37A4F0BA3A/SLACKWARE-14.2/5.4.62/X86_64/BAB721D52E>) |
| 1022:15df | 17aa:3190 | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     | ccp        | [EF676712A0](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00000/67A5CBCEF039/DEBIAN-11/5.10.0-10-AMD64/X86_64/EF676712A0>) |
| 8086:0f18 | 1028:07b9 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [F444E9914B](<Mini Pc/Dell/Edge/Edge Gateway 3001/9349E7ABA493/UBUNTU-CORE-16/4.4.0-171-GENERIC/X86_64/F444E9914B>) |
| 8086:0f18 | 1071:0740 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [F2F4C5E23E](<Mini Pc/AMI/Aptio/Aptio CRB/4331D427A030/UBUNTU-18.04/5.4.0-48-GENERIC/X86_64/F2F4C5E23E>) |
| 8086:0f18 | 17aa:3688 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [A88328FDB9](<Mini Pc/Lenovo/H500/H500 10156/0127105F4BF9/ROSA-2014.1/4.1.34-NRJ-DESKTOP-2ROSA-X86_64/X86_64/A88328FDB9>) |
| 8086:0f18 | 1d05:100f | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [9569E1B79C](<Mini Pc/Exo/Smart/Smart R8-CE/6DED5F1A28A7/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/9569E1B79C>) |
| 8086:2298 | 1297:4033 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | mei_txe    | [B31E28E55F](<Mini Pc/Shuttle/XS35/XS35V5/00878A051AA2/UBUNTU-19.10/5.3.0-42-GENERIC/X86_64/B31E28E55F>) |

### Firewire controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 11c1:5901 | 11c1:5900 | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 78    | firewir... | [C3A014CA22](<Mini Pc/Apple/Macmini6/Macmini6,2/F5E3810853BC/CLEAR-LINUX-OS-35970/5.13.13-1070.NATIVE/X86_64/C3A014CA22>) |
| 104c:823f |           | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 53    | firewir... | [D7F1687670](<Mini Pc/Apple/Macmini4/Macmini4,1/BCBD7A97BE65/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D7F1687670>) |
| 11c1:5811 | 11c1:5811 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 17    | firewir... | [2075A95BFB](<Mini Pc/Apple/Macmini2/Macmini2,1/8B91B715078D/FEDORA-30/5.3.11-100.FC29.I686/I686/2075A95BFB>) |
| 11c1:5901 | c111:0159 | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 3     | firewir... | [703034E8C4](<Mini Pc/Apple/Macmini6/Macmini6,2/122FDC1BF87C/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/703034E8C4>) |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1577 | 1022:1577 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 18    |            | [3C277DC3C1](<Mini Pc/Hewlett-Packard/t530/t530 Thin Client/982DFBB69A90/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3C277DC3C1>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:3ea5 | 8086:2074 | Intel            | CoffeeLake-U GT3e [Iris Plus Grap... | 156   | i915       | [C79A71B9DB](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/C0AF1D599D12/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C79A71B9DB>) |
| 8086:0f31 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 80    | i915       | [BF7C2C6D9B](<Mini Pc/NEXCOM/VTC/VTC1010/6EF054560413/DEBIAN-11/5.10.0-11-AMD64/X86_64/BF7C2C6D9B>) |
| 8086:9bca | 8086:2081 | Intel            | Comet Lake UHD Graphics              | 53    | i915       | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:22b1 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 38    | i915       | [207E311CFC](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-102/8054EC01AC51/ASTRALINUXCE-2.12.44/5.10.0-1038.40-GENERIC/X86_64/207E311CFC>) |
| 8086:5a85 | 8086:2067 | Intel            | HD Graphics 500                      | 37    | i915       | [5BEEF7A5B1](<Mini Pc/Intel/NUC6/NUC6CAYH/0C6F2967B76D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5BEEF7A5B1>) |
| 8086:9b41 | 8086:2081 | Intel            | CometLake-U GT2 [UHD Graphics]       | 36    | i915       | [C62C19EF52](<Mini Pc/Intel Client Systems/NUC10/NUC10i5FNH/209162C330FD/DEBIAN-11/5.10.0-9-AMD64/X86_64/C62C19EF52>) |
| 8086:5a85 | 8086:2212 | Intel            | HD Graphics 500                      | 32    | i915       | [224597688F](<Mini Pc/AMI/Aptio/Aptio CRB/0421BC2A6F1E/UBUNTU-20.04/5.4.0-90-GENERIC/X86_64/224597688F>) |
| 1002:694c | 8086:2073 | AMD              | Polaris 22 XT [Radeon RX Vega M GH]  | 31    | amdgpu     | [317E098A9E](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/A75259B85C6D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/317E098A9E>) |
| 8086:5916 | 8086:2068 | Intel            | HD Graphics 620                      | 30    | i915       | [8F83AE693D](<Mini Pc/Intel/NUC7/NUC7i3BNK/5938BD8B09C1/KUBUNTU-20.04/5.14.9-XANMOD2/X86_64/8F83AE693D>) |
| 8086:591b | 8086:2073 | Intel            | HD Graphics 630                      | 30    | i915       | [093D240F55](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/22525E8969DB/OPENSUSE-TUMBLEWEED-20220125/5.16.1-1-DEFAULT/X86_64/093D240F55>) |
| 8086:193b | 8086:2064 | Intel            | Iris Pro Graphics 580                | 29    | i915       | [86D379E9D5](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/54383D955906/UBUNTU-20.10/5.8.0-63-GENERIC/X86_64/86D379E9D5>) |
| 8086:5926 | 8086:2068 | Intel            | Iris Plus Graphics 640               | 29    | i915       | [7F8770AFC4](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/38F8ADEA821D/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/7F8770AFC4>) |
| 8086:0166 | 106b:00ff | Intel            | 3rd Gen Core processor Graphics C... | 28    | i915       | [7901968D67](<Mini Pc/Apple/Macmini6/Macmini6,1/357DADC601E4/MANJARO/5.16.11-2-MANJARO/X86_64/7901968D67>) |
| 10de:0861 | 106b:00ae | Nvidia           | C79 [GeForce 9400]                   | 26    | nouveau    | [F114F6EA54](<Mini Pc/Apple/Macmini3/Macmini3,1/C67829525D2F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F114F6EA54>) |
| 1002:1636 | 1043:87e7 | AMD              | Renoir                               | 25    | amdgpu     | [2F6DF3FFF6](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/86C8213ACE93/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2F6DF3FFF6>) |
| 8086:0166 | 106b:0101 | Intel            | 3rd Gen Core processor Graphics C... | 23    | i915       | [C3A014CA22](<Mini Pc/Apple/Macmini6/Macmini6,2/F5E3810853BC/CLEAR-LINUX-OS-35970/5.13.13-1070.NATIVE/X86_64/C3A014CA22>) |
| 8086:1626 | 8086:2057 | Intel            | HD Graphics 6000                     | 22    | i915       | [A07A68BA43](<Mini Pc/Intel/NUC5i5RYB/NUC5i5RYB H40999-504/8FB44501D2B3/DEBIAN-11/5.10.0-9-AMD64/X86_64/A07A68BA43>) |
| 8086:0126 | 106b:00e6 | Intel            | 2nd Generation Core Processor Fam... | 21    | i915       | [A2BA361F2C](<Mini Pc/Apple/Macmini5/Macmini5,1/C29061AA8B1E/ZORIN-16/5.11.0-43-GENERIC/X86_64/A2BA361F2C>) |
| 8086:0a2e | 106b:0141 | Intel            | Haswell-ULT Integrated Graphics C... | 21    | i915       | [8441AB9EB2](<Mini Pc/Apple/Macmini7/Macmini7,1/1777ECA502AA/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/8441AB9EB2>) |
| 8086:1616 | 8086:2057 | Intel            | HD Graphics 5500                     | 20    | i915       | [CEA504B47D](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-503/F250AC8777D6/CENTOS-STREAM/4.18.0-348.2.1.EL8_5.X86_64/X86_64/CEA504B47D>) |
| 8086:5927 | 8086:2068 | Intel            | Iris Plus Graphics 650               | 20    | i915       | [524246985D](<Mini Pc/Intel/NUC7/NUC7i7BNH/BB7338CF729A/KUBUNTU-19.04/5.0.0-38-GENERIC/X86_64/524246985D>) |
| 8086:3185 | 8086:2072 | Intel            | GeminiLake [UHD Graphics 600]        | 19    | i915       | [E02C6336D6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/3F30AC0E5D22/ARTIX-ROLLING/5.16.3-ARTIX1-1/X86_64/E02C6336D6>) |
| 8086:3184 | 8086:2072 | Intel            | GeminiLake [UHD Graphics 605]        | 18    | i915       | [95A1F9D8FD](<Mini Pc/Intel Client Systems/NUC7/NUC7PJYH/BB8E2DFD12E1/KALI-2021.3/5.10.0-KALI9-AMD64/X86_64/95A1F9D8FD>) |
| 8086:22b0 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 17    | i915       | [CDDC590270](<Mini Pc/BESSTAR Tech/Z83/Z83-F/833154D27E3C/ZORIN-16/5.13.0-30-GENERIC/X86_64/CDDC590270>) |
| 8086:27a2 | 8086:7270 | Intel            | Mobile 945GM/GMS, 943/940GML Expr... | 17    | i915       | [2075A95BFB](<Mini Pc/Apple/Macmini2/Macmini2,1/8B91B715078D/FEDORA-30/5.3.11-100.FC29.I686/I686/2075A95BFB>) |
| 10de:08a4 | 106b:00c0 | Nvidia           | MCP89 [GeForce 320M]                 | 16    | nouveau    | [D7F1687670](<Mini Pc/Apple/Macmini4/Macmini4,1/BCBD7A97BE65/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D7F1687670>) |
| 8086:0a26 | 106b:0141 | Intel            | Haswell-ULT Integrated Graphics C... | 16    | i915       | [5550136FFD](<Mini Pc/Apple/Macmini7/Macmini7,1/65598A0C8936/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/5550136FFD>) |
| 8086:22b1 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 16    | i915       | [85A08428DF](<Mini Pc/AMI/Aptio/Aptio CRB/A758F1A02D67/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/85A08428DF>) |
| 8086:3185 | 1e50:8003 | Intel            | GeminiLake [UHD Graphics 600]        | 15    | i915       | [B78185D870](<Mini Pc/Chuwi/HeroBox/HeroBox/0564D825BBAD/DEBIAN-11/5.15.0-0.BPO.3-AMD64/X86_64/B78185D870>) |
| 8086:9a49 | 8086:3004 | Intel            | TigerLake-LP GT2 [Iris Xe Graphics]  | 15    | i915       | [CA53435B36](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/26774C86D363/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/CA53435B36>) |
| 1002:6741 | 106b:00e8 | AMD              | Whistler [Radeon HD 6630M/6650M/6... | 14    | radeon     | [FEE3E2FEF0](<Mini Pc/Apple/Macmini5/Macmini5,2/D5A757D5CEB8/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/FEE3E2FEF0>) |
| 1002:9806 | 103c:17e2 | AMD              | Wrestler [Radeon HD 6320]            | 14    | radeon     | [AE54C309D5](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/A9289FCA615E/DEBIAN-11/5.10.0-11-686-PAE/I686/AE54C309D5>) |
| 8086:3e92 | 17aa:312d | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 13    | i915       | [88A943EC80](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T700BHBL/970C8BB93481/DEBIAN-11/5.10.0-11-AMD64/X86_64/88A943EC80>) |
| 8086:162b | 8086:2057 | Intel            | Iris Graphics 6100                   | 12    | i915       | [87A77E0618](<Mini Pc/Intel/NUC5i7RYB/NUC5i7RYB H73774-101/BE69D0456A98/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/87A77E0618>) |
| 8086:3185 | 1043:875e | Intel            | GeminiLake [UHD Graphics 600]        | 12    | i915       | [27BB88805D](<Mini Pc/ASUSTek Computer/PN/PN40/21E857FB29E9/CENTOS-7/3.10.0-1160.53.1.EL7.X86_64/X86_64/27BB88805D>) |
| 8086:0126 | 106b:00f0 | Intel            | 2nd Generation Core Processor Fam... | 11    |            | [FEE3E2FEF0](<Mini Pc/Apple/Macmini5/Macmini5,2/D5A757D5CEB8/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/FEE3E2FEF0>) |
| 8086:1926 | 8086:2063 | Intel            | Iris Graphics 540                    | 11    | i915       | [6879986BF2](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-505/29B4250B3145/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/6879986BF2>) |
| 8086:5917 | 8086:2070 | Intel            | UHD Graphics 620                     | 11    | i915       | [65AE59D048](<Mini Pc/Intel Client Systems/NUC7/NUC7i7DNKE/491DF6CA7E6C/ARCH/5.16.2-ARCH1-1/X86_64/65AE59D048>) |
| 1002:15dd | 17aa:3130 | AMD              | Raven Ridge [Radeon Vega Series /... | 10    | amdgpu     | [CC222D78B9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VG001QRU/28BB5B3B7530/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/CC222D78B9>) |
| 8086:0f31 | 17aa:368d | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 10    | i915       | [0A2E33DAD2](<Mini Pc/Lenovo/E50-00/E50-00 90BX001HUK/8992AAAB2A15/UBUNTU-20.04/5.4.0-90-GENERIC/X86_64/0A2E33DAD2>) |
| 1002:1636 | 103c:872e | AMD              | Renoir                               | 9     | amdgpu     | [8366A84CDB](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/F373E702B28B/XUBUNTU-20.04/5.13.0-28-GENERIC/X86_64/8366A84CDB>) |
| 1106:7122 | 1106:7122 | VIA Technologies | VX900 Graphics [Chrome9 HD]          | 8     |            | [15268C0CCC](<Mini Pc/Hewlett-Packard/t510/t510 Thin Client/21A13F83F33E/XUBUNTU-20.04/5.8.0-53-GENERIC/X86_64/15268C0CCC>) |
| 8086:1916 | 8086:2063 | Intel            | Skylake GT2 [HD Graphics 520]        | 8     | i915       | [DB86E412B7](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-502/DB7A6FF83407/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/DB86E412B7>) |
| 8086:3e9b | 106b:0207 | Intel            | CoffeeLake-H GT2 [UHD Graphics 630]  | 8     | i915       | [CA26CBBF22](<Mini Pc/Apple/Macmini8/Macmini8,1/F39A3C4B83EB/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/CA26CBBF22>) |
| 8086:5a84 | 8086:2212 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 8     | i915       | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 1002:15d8 | 17aa:3151 | AMD              | Picasso/Raven 2 [Radeon Vega Seri... | 7     | amdgpu     | [5AC6CDC8FB](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A4001WUS/A25EA1475B0F/REBORNOS-ROLLING/5.16.9-ARCH1-1/X86_64/5AC6CDC8FB>) |
| 1002:9874 | 103c:8158 | AMD              | Wani [Radeon R5/R6/R7 Graphics]      | 7     | amdgpu     | [702F310A99](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/642F86533F2F/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/702F310A99>) |
| 8086:0f31 | 1027:2014 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 7     | i915       | [AD5481A5BC](<Mini Pc/RCA/W/W1162/9C676F6C513F/DEBIAN-10/4.19.0-11-AMD64/X86_64/AD5481A5BC>) |
| 1002:694e | 8086:2073 | AMD              | Polaris 22 XL [Radeon RX Vega M GL]  | 6     | amdgpu     | [CA6047EF7C](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HNK/5B8C59357A49/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/CA6047EF7C>) |
| 8086:0f31 | 17aa:30b5 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | i915       | [538597F50A](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M53 10DE001HUS/36D92E1E56E1/ENDLESS-3.7.8/5.3.0-28-GENERIC/X86_64/538597F50A>) |

### Iommu (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1631 | 1022:1631 | AMD              | Renoir/Cezanne IOMMU                 | 42    |            | [8A85AEAF5A](<Mini Pc/AZW/GTR/GTR/BB648F57E2C2/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/8A85AEAF5A>) |
| 1022:15d1 | 1022:15d1 | AMD              | Raven/Raven2 IOMMU                   | 25    |            | [CC222D78B9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VG001QRU/28BB5B3B7530/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/CC222D78B9>) |
| 1022:1423 | 103c:8103 | AMD              | Family 15h (Models 30h-3fh) I/O M... | 2     |            | [60924B9FD9](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client TC/D0CDB04E03EF/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/60924B9FD9>) |
| 8086:1f16 | 8086:0000 | Intel            | Atom processor C2000 RCEC            | 2     |            | [C1D37659C1](<Mini Pc/Supermicro/A1/A1SAi/F097711C2215/GENTOO-2.6/5.4.86-GENTOO/X86_64/C1D37659C1>) |
| 1022:15d1 | 103c:8523 | AMD              | Raven/Raven2 IOMMU                   | 1     |            | [BAB721D52E](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/FB37A4F0BA3A/SLACKWARE-14.2/5.4.62/X86_64/BAB721D52E>) |
| 1022:1631 | 17aa:3190 | AMD              | Renoir/Cezanne IOMMU                 | 1     |            | [EF676712A0](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00000/67A5CBCEF039/DEBIAN-11/5.10.0-10-AMD64/X86_64/EF676712A0>) |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:816c | 1043:85b5 | Realtek Semic... | RTL8111xP IPMI interface             | 19    |            | [2F6DF3FFF6](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/86C8213ACE93/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2F6DF3FFF6>) |
| 10ec:816c | 17aa:3151 | Realtek Semic... | RTL8111xP IPMI interface             | 7     |            | [5AC6CDC8FB](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A4001WUS/A25EA1475B0F/REBORNOS-ROLLING/5.16.9-ARCH1-1/X86_64/5AC6CDC8FB>) |
| 10ec:816c | 17aa:3181 | Realtek Semic... | RTL8111xP IPMI interface             | 2     |            | [56F9A83D77](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75n 11GW000BUS/8D95E87EDCE7/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/56F9A83D77>) |
| 10ec:816c | 103c:83dd | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [9EC6F2E5FE](<Mini Pc/Hewlett-Packard/mt44/mt44 Mobile Thin Client/367A393AEEB1/KDE-NEON-20.04/5.11.0-40-GENERIC/X86_64/9EC6F2E5FE>) |
| 10ec:816c | 103c:8523 | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [BAB721D52E](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/FB37A4F0BA3A/SLACKWARE-14.2/5.4.62/X86_64/BAB721D52E>) |
| 10ec:816c | 17aa:30fd | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [5F6F9A1C6C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10M2S0DL00/BC868DED3F88/UBUNTU-21.04/5.11.0-17-GENERIC/X86_64/5F6F9A1C6C>) |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:816c | 10ec:8168 | Realtek Semic... | RTL8111xP IPMI interface             | 10    | ipmi_si    | [8366A84CDB](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/F373E702B28B/XUBUNTU-20.04/5.13.0-28-GENERIC/X86_64/8366A84CDB>) |
| 10ec:816c | 17aa:3130 | Realtek Semic... | RTL8111xP IPMI interface             | 10    |            | [CC222D78B9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VG001QRU/28BB5B3B7530/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/CC222D78B9>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9def | 8086:2074 | Intel            | Cannon Point-LP Shared SRAM          | 156   |            | [C79A71B9DB](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/C0AF1D599D12/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C79A71B9DB>) |
| 8086:02ef | 8086:2081 | Intel            | Comet Lake PCH-LP Shared SRAM        | 89    |            | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:9d21 | 8086:2068 | Intel            | Sunrise Point-LP PMC                 | 79    |            | [7F8770AFC4](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/38F8ADEA821D/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/7F8770AFC4>) |
| 8086:a121 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 38    |            | [317E098A9E](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/A75259B85C6D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/317E098A9E>) |
| 8086:a121 | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 29    |            | [86D379E9D5](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/54383D955906/UBUNTU-20.10/5.8.0-63-GENERIC/X86_64/86D379E9D5>) |
| 10de:0a88 |           | Nvidia           | MCP79 Memory Controller              | 26    |            | [F114F6EA54](<Mini Pc/Apple/Macmini3/Macmini3,1/C67829525D2F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F114F6EA54>) |
| 10de:0a89 |           | Nvidia           | MCP79 Memory Controller              | 26    |            | [F114F6EA54](<Mini Pc/Apple/Macmini3/Macmini3,1/C67829525D2F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F114F6EA54>) |
| 10de:0a98 | 10de:cb79 | Nvidia           | MCP79 Memory Controller              | 26    |            | [F114F6EA54](<Mini Pc/Apple/Macmini3/Macmini3,1/C67829525D2F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F114F6EA54>) |
| 10de:0aa4 |           | Nvidia           | MCP79 Memory Controller              | 26    |            | [F114F6EA54](<Mini Pc/Apple/Macmini3/Macmini3,1/C67829525D2F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F114F6EA54>) |
| 8086:a0ef |           | Intel            | Tiger Lake-LP Shared SRAM            | 24    |            | [CA53435B36](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/26774C86D363/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/CA53435B36>) |
| 8086:9d21 | 8086:2063 | Intel            | Sunrise Point-LP PMC                 | 19    |            | [6879986BF2](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-505/29B4250B3145/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/6879986BF2>) |
| 8086:9d21 | 8086:2070 | Intel            | Sunrise Point-LP PMC                 | 17    |            | [0261508BA5](<Mini Pc/Intel Client Systems/NUC7/NUC7i3DNHE/F93E47848AEB/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/0261508BA5>) |
| 10de:0d68 |           | Nvidia           | MCP89 Memory Controller              | 16    |            | [D7F1687670](<Mini Pc/Apple/Macmini4/Macmini4,1/BCBD7A97BE65/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D7F1687670>) |
| 10de:0d69 |           | Nvidia           | MCP89 Memory Controller              | 16    |            | [D7F1687670](<Mini Pc/Apple/Macmini4/Macmini4,1/BCBD7A97BE65/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D7F1687670>) |
| 10de:0d6d |           | Nvidia           | MCP89 Memory Controller              | 16    |            | [D7F1687670](<Mini Pc/Apple/Macmini4/Macmini4,1/BCBD7A97BE65/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D7F1687670>) |
| 10de:0d6e |           | Nvidia           | MCP89 Memory Controller              | 16    |            | [D7F1687670](<Mini Pc/Apple/Macmini4/Macmini4,1/BCBD7A97BE65/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D7F1687670>) |
| 10de:0d6f |           | Nvidia           | MCP89 Memory Controller              | 16    |            | [D7F1687670](<Mini Pc/Apple/Macmini4/Macmini4,1/BCBD7A97BE65/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D7F1687670>) |
| 10de:0d70 |           | Nvidia           | MCP89 Memory Controller              | 16    |            | [D7F1687670](<Mini Pc/Apple/Macmini4/Macmini4,1/BCBD7A97BE65/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D7F1687670>) |
| 10de:0d71 |           | Nvidia           | MCP89 Memory Controller              | 16    |            | [D7F1687670](<Mini Pc/Apple/Macmini4/Macmini4,1/BCBD7A97BE65/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D7F1687670>) |
| 10de:0d72 |           | Nvidia           | MCP89 Memory Controller              | 16    |            | [D7F1687670](<Mini Pc/Apple/Macmini4/Macmini4,1/BCBD7A97BE65/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D7F1687670>) |
| 10de:0d75 |           | Nvidia           | MCP89 Memory Controller              | 16    |            | [D7F1687670](<Mini Pc/Apple/Macmini4/Macmini4,1/BCBD7A97BE65/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D7F1687670>) |
| 10de:0d7b |           | Nvidia           | MCP89 Memory Controller              | 16    |            | [D7F1687670](<Mini Pc/Apple/Macmini4/Macmini4,1/BCBD7A97BE65/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D7F1687670>) |
| 8086:a36f | 17aa:312d | Intel            | Cannon Lake PCH Shared SRAM          | 15    |            | [88A943EC80](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T700BHBL/970C8BB93481/DEBIAN-11/5.10.0-11-AMD64/X86_64/88A943EC80>) |
| 8086:a36f | 8086:7270 | Intel            | Cannon Lake PCH Shared SRAM          | 10    |            | [EFF399191D](<Mini Pc/Intel Client Systems/NUC9/NUC9i9QNX/519180459546/UBUNTU-20.04/5.13.0-25-GENERIC/X86_64/EFF399191D>) |
| 8086:9d21 | 8086:7270 | Intel            | Sunrise Point-LP PMC                 | 9     |            | [E4BBE42B5A](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/33AEB9BBD609/DEBIAN-11/5.10.0-11-AMD64/X86_64/E4BBE42B5A>) |
| 8086:a2a1 | 103c:829a | Intel            | 200 Series/Z370 Chipset Family Po... | 9     |            | [DFD0CB667C](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/0C45B1FBE800/DEBIAN-11/5.10.0-11-AMD64/X86_64/DFD0CB667C>) |
| 8086:a36f |           | Intel            | Cannon Lake PCH Shared SRAM          | 8     |            | [CA26CBBF22](<Mini Pc/Apple/Macmini8/Macmini8,1/F39A3C4B83EB/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/CA26CBBF22>) |
| 8086:a36f | 17aa:3135 | Intel            | Cannon Lake PCH Shared SRAM          | 8     |            | [C43EF85B97](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920x 10S1S07700/59BDC87984FB/ROSA-2016.1/5.4.40-GENERIC-1ROSA-X86_64/X86_64/C43EF85B97>) |
| 8086:a121 | 19da:b333 | Intel            | 100 Series/C230 Series Chipset Fa... | 7     |            | [7348D34142](<Mini Pc/ZOTAC/ZBOX-EN1070/ZBOX-EN1070-1060/0CBF4FF1BBBE/LINUXMINT-20.2/5.13.0-22-GENERIC/X86_64/7348D34142>) |
| 8086:a36f | 17aa:3136 | Intel            | Cannon Lake PCH Shared SRAM          | 7     |            | [B3BA67D085](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10V8S06904/EAA513742A16/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/B3BA67D085>) |
| 8086:9def | 17aa:314d | Intel            | Cannon Point-LP Shared SRAM          | 6     |            | [BD2F6222E5](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AD002DGE/D203F33318BC/MANJARO-21.1.0/5.10.53-1-MANJARO/X86_64/BD2F6222E5>) |
| 8086:4def | 1043:8813 | Intel            | Jasper Lake Shared SRAM Controller   | 5     |            | [B416BA575D](<Mini Pc/ASUSTek Computer/PN/PN41/20388AD561BB/ZORIN-16/5.13.0-30-GENERIC/X86_64/B416BA575D>) |
| 8086:a2a1 | 103c:82a5 | Intel            | 200 Series/Z370 Chipset Family Po... | 5     |            | [C47D9B3AE0](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 400 G3 DM/342D63741B55/ELEMENTARY-6.1/5.13.0-28-GENERIC/X86_64/C47D9B3AE0>) |
| 8086:a2a1 | 17aa:3111 | Intel            | 200 Series/Z370 Chipset Family Po... | 5     |            | [B9D4EFB68C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MR000XUK/3928CECFA48F/POP!_OS-21.10/5.15.15-76051515-GENERIC/X86_64/B9D4EFB68C>) |
| 8086:02ef | 1043:87bd | Intel            | Comet Lake PCH-LP Shared SRAM        | 4     |            | [7A01C63401](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN62S/469668D35D11/DEBIAN-11/5.10.0-8-AMD64/X86_64/7A01C63401>) |
| 8086:06ef | 17aa:316e | Intel            | Comet Lake PCH Shared SRAM           | 4     |            | [0224398912](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DUS4SQ00/DA9A8078DC3D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/0224398912>) |
| 8086:9d21 | 103c:84f5 | Intel            | Sunrise Point-LP PMC                 | 4     |            | [CF5DEA43E1](<Mini Pc/Hewlett-Packard/260/260 G3 DM/D334B500C95E/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/CF5DEA43E1>) |
| 8086:9def | 8086:7270 | Intel            | Cannon Point-LP Shared SRAM          | 4     |            | [D9AC661777](<Mini Pc/Intel Client Systems/NUC8/NUC8i3CYS/F84856907C67/KALI-2021.3/5.10.0-KALI9-AMD64/X86_64/D9AC661777>) |
| 8086:a121 | 103c:82c0 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     |            | [AC904E9BCB](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G3 Workstation/90A7B6AE2869/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/AC904E9BCB>) |
| 8086:02ef | 8086:7270 | Intel            | Comet Lake PCH-LP Shared SRAM        | 3     |            | [934F2F075C](<Mini Pc/AZW/SEi/SEi/2957B295DEBC/LINUXMINT-20/5.4.0-90-GENERIC/X86_64/934F2F075C>) |
| 8086:06ef | 17aa:3172 | Intel            | Comet Lake PCH Shared SRAM           | 3     |            | [EE32355409](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/EE29838C95B5/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/EE32355409>) |
| 8086:a121 | 15d9:0898 | Intel            | 100 Series/C230 Series Chipset Fa... | 3     |            | [8D4CBF243D](<Mini Pc/Supermicro/SYS-5039/SYS-5039MS-H12TRF/C29A8D8B7AFC/ROSA-2021.1/5.10.56-GENERIC-1ROSA2021.1-X86_64/X86_64/8D4CBF243D>) |
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 3     |            | [CA900F89D0](<Mini Pc/Soyo/SY-Thin/SY-Thin Mini H110/B4016DB6A371/DEEPIN-20.2.3/5.12.18-AMD64-DESKTOP/X86_64/CA900F89D0>) |
| 8086:a2a1 | 17aa:310b | Intel            | 200 Series/Z370 Chipset Family Po... | 3     |            | [C7930B0D92](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M910q 10MUS3JC00/F360C35AE270/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/C7930B0D92>) |
| 8086:06ef | 103c:8710 | Intel            | Comet Lake PCH Shared SRAM           | 2     |            | [B2A212246B](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G6 Desktop Mini PC/1AD35AB4DD59/CENTOS-7/5.4.118-1.EL7.ELREPO.X86_64/X86_64/B2A212246B>) |
| 8086:06ef | 103c:871a | Intel            | Comet Lake PCH Shared SRAM           | 2     |            | [FDBB17D3B2](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 400 G6 Desktop Mini PC/4C0794A3D051/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/FDBB17D3B2>) |
| 8086:06ef | 8086:7270 | Intel            | Comet Lake PCH Shared SRAM           | 2     |            | [57676DE735](<Mini Pc/ZOTAC/ZBOX-ECM7307/ZBOX-ECM73070C-53060C/C458DE01446F/ARCO-ROLLING/5.13.12-ARCH1-1/X86_64/57676DE735>) |
| 8086:9d21 | 1043:8694 | Intel            | Sunrise Point-LP PMC                 | 2     |            | [847A813A2C](<Mini Pc/ASUSTek Computer/PN60/PN60-R/1051BA1EB3B1/MANJARO/5.10.15-1-MANJARO/X86_64/847A813A2C>) |
| 8086:9def | 1043:8790 | Intel            | Cannon Point-LP Shared SRAM          | 2     |            | [45389EF622](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN61/9FE5C35BEA82/KDE-NEON-20.04/5.4.0-67-GENERIC/X86_64/45389EF622>) |
| 8086:9def | 17aa:314c | Intel            | Cannon Point-LP Shared SRAM          | 2     |            | [0F66B49A44](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AD000YMX/8552A91D7647/ALPINE-3.13.0_ALPHA20200917/5.4.65-0-LTS/X86_64/0F66B49A44>) |

### Multimedia (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0f38 |           | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     |            | [C4198C729C](<Mini Pc/AMI/Aptio/Aptio CRB/D031FAB792D1/ROSA-2016.1/4.13.6-NRJ-DESKTOP-1ROSA-X86_64/X86_64/C4198C729C>) |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15e2 | 1022:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 52    | snd_pci... | [8A85AEAF5A](<Mini Pc/AZW/GTR/GTR/BB648F57E2C2/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/8A85AEAF5A>) |
| 8086:5a88 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 10    |            | [D831E8693D](<Mini Pc/Beelink/AP/AP34/5D90ACC24076/LINUXMINT-20.2/5.4.0-81-GENERIC/X86_64/D831E8693D>) |
| 8086:0f38 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 5     | intel_a... | [87E6D2F056](<Mini Pc/AMI/Aptio/Aptio CRB/BE0598986E2E/UBUNTU-19.10/5.3.0-55-GENERIC/X86_64/87E6D2F056>) |
| 8086:22b8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | intel_a... | [10C1838B9D](<Mini Pc/AMI/Aptio/Aptio CRB/6C7827486731/DEBIAN-11/5.10.0-8-AMD64/X86_64/10C1838B9D>) |
| 1022:15e2 | 103c:8523 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     | snd_pci... | [BAB721D52E](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/FB37A4F0BA3A/SLACKWARE-14.2/5.4.62/X86_64/BAB721D52E>) |
| 1022:15e2 | 17aa:3190 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     | snd_pci... | [EF676712A0](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00000/67A5CBCEF039/DEBIAN-11/5.10.0-10-AMD64/X86_64/EF676712A0>) |
| 109e:0878 |           | Brooktree        | Bt878 Audio Capture                  | 1     |            | [10DB69DD6C](<Mini Pc/Kontron/SMX/SMX945/327FC59121CA/UBUNTU-18.04/4.15.0-88-GENERIC/I686/10DB69DD6C>) |
| 8086:0f38 | 1027:2014 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | intel_a... | [029DA6FFCC](<Mini Pc/AMI/Aptio/Aptio CRB/5E66E4F2E42F/UBUNTU-20.04/5.4.0-28-GENERIC/X86_64/029DA6FFCC>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:15be | 8086:2074 | Intel            | Ethernet Connection (6) I219-V       | 155   | e1000e     | [C79A71B9DB](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/C0AF1D599D12/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C79A71B9DB>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 152   | r8169      | [CDDC590270](<Mini Pc/BESSTAR Tech/Z83/Z83-F/833154D27E3C/ZORIN-16/5.13.0-30-GENERIC/X86_64/CDDC590270>) |
| 8086:0d4f | 8086:2081 | Intel            | Ethernet Connection (10) I219-V      | 89    | e1000e     | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 14e4:1686 | 14e4:1686 | Broadcom         | NetXtreme BCM57766 Gigabit Ethern... | 87    | tg3        | [5550136FFD](<Mini Pc/Apple/Macmini7/Macmini7,1/65598A0C8936/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/5550136FFD>) |
| 8086:15d8 | 8086:2068 | Intel            | Ethernet Connection (4) I219-V       | 78    | e1000e     | [7F8770AFC4](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/38F8ADEA821D/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/7F8770AFC4>) |
| 8086:15a3 | 8086:2057 | Intel            | Ethernet Connection (3) I218-V       | 54    | e1000e     | [CEA504B47D](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-503/F250AC8777D6/CENTOS-STREAM/4.18.0-348.2.1.EL8_5.X86_64/X86_64/CEA504B47D>) |
| 14e4:16b4 | 14e4:16b4 | Broadcom         | NetXtreme BCM57765 Gigabit Ethern... | 53    | tg3        | [D7F1687670](<Mini Pc/Apple/Macmini4/Macmini4,1/BCBD7A97BE65/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D7F1687670>) |
| 10ec:8168 | 19da:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 47    | r8169      | [7EAB522138](<Mini Pc/ZOTAC/ZBOXNANO-ID/ZBOXNANO-ID67/C3933CE474DF/LINUXMINT-20.3/5.4.0-26-GENERIC/X86_64/7EAB522138>) |
| 8086:15b7 | 8086:0000 | Intel            | Ethernet Connection (2) I219-LM      | 38    | e1000e     | [317E098A9E](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/A75259B85C6D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/317E098A9E>) |
| 10ec:8168 | 8086:2072 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 37    | r8169      | [E02C6336D6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/3F30AC0E5D22/ARTIX-ROLLING/5.16.3-ARTIX1-1/X86_64/E02C6336D6>) |
| 10ec:8168 | 8086:2060 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 35    | r8169      | [207E311CFC](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-102/8054EC01AC51/ASTRALINUXCE-2.12.44/5.10.0-1038.40-GENERIC/X86_64/207E311CFC>) |
| 10ec:8168 | 8086:2067 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 35    | r8169      | [5BEEF7A5B1](<Mini Pc/Intel/NUC6/NUC6CAYH/0C6F2967B76D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5BEEF7A5B1>) |
| 8086:15b7 | 8086:2064 | Intel            | Ethernet Connection (2) I219-LM      | 29    | e1000e     | [86D379E9D5](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/54383D955906/UBUNTU-20.10/5.8.0-63-GENERIC/X86_64/86D379E9D5>) |
| 10de:0ab0 | 10de:cb79 | Nvidia           | MCP79 Ethernet                       | 26    | forcedeth  | [F114F6EA54](<Mini Pc/Apple/Macmini3/Macmini3,1/C67829525D2F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F114F6EA54>) |
| 10ec:8168 | 1043:85b5 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 19    | r8169      | [2F6DF3FFF6](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/86C8213ACE93/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2F6DF3FFF6>) |
| 8086:1570 | 8086:2063 | Intel            | Ethernet Connection I219-V           | 19    | e1000e     | [6879986BF2](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-505/29B4250B3145/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/6879986BF2>) |
| 11ab:4362 | 11ab:5321 | Marvell Techn... | 88E8053 PCI-E Gigabit Ethernet Co... | 17    | sky2       | [2075A95BFB](<Mini Pc/Apple/Macmini2/Macmini2,1/8B91B715078D/FEDORA-30/5.3.11-100.FC29.I686/I686/2075A95BFB>) |
| 8086:156f | 8086:2070 | Intel            | Ethernet Connection I219-LM          | 17    | e1000e     | [0261508BA5](<Mini Pc/Intel Client Systems/NUC7/NUC7i3DNHE/F93E47848AEB/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/0261508BA5>) |
| 10ec:8168 | 1043:8677 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 15    | r8169      | [27BB88805D](<Mini Pc/ASUSTek Computer/PN/PN40/21E857FB29E9/CENTOS-7/3.10.0-1160.53.1.EL7.X86_64/X86_64/27BB88805D>) |
| 8086:15bc | 17aa:312d | Intel            | Ethernet Connection (7) I219-V       | 15    | e1000e     | [88A943EC80](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T700BHBL/970C8BB93481/DEBIAN-11/5.10.0-11-AMD64/X86_64/88A943EC80>) |
| 8086:15f3 | 8086:3004 | Intel            | Ethernet Controller I225-V           | 15    | igc        | [CA53435B36](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/26774C86D363/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/CA53435B36>) |
| 14e4:16b1 | 103c:17e2 | Broadcom         | NetLink BCM57781 Gigabit Ethernet... | 14    | tg3        | [AE54C309D5](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/A9289FCA615E/DEBIAN-11/5.10.0-11-686-PAE/I686/AE54C309D5>) |
| 10ec:8168 | 17aa:3130 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 10    | r8169      | [CC222D78B9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VG001QRU/28BB5B3B7530/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/CC222D78B9>) |
| 10ec:8168 | 103c:872e | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 9     | r8169      | [8366A84CDB](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/F373E702B28B/XUBUNTU-20.04/5.13.0-28-GENERIC/X86_64/8366A84CDB>) |
| 8086:15e3 | 103c:829a | Intel            | Ethernet Connection (5) I219-LM      | 9     | e1000e     | [DFD0CB667C](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/0C45B1FBE800/DEBIAN-11/5.10.0-11-AMD64/X86_64/DFD0CB667C>) |
| 14e4:1692 | 14e4:9692 | Broadcom         | NetLink BCM57780 Gigabit Ethernet... | 8     | tg3        | [15268C0CCC](<Mini Pc/Hewlett-Packard/t510/t510 Thin Client/21A13F83F33E/XUBUNTU-20.04/5.8.0-53-GENERIC/X86_64/15268C0CCC>) |
| 8086:15bb | 17aa:3135 | Intel            | Ethernet Connection (7) I219-LM      | 8     | e1000e     | [C43EF85B97](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920x 10S1S07700/59BDC87984FB/ROSA-2016.1/5.4.40-GENERIC-1ROSA-X86_64/X86_64/C43EF85B97>) |
| 8086:15bb | 8086:0000 | Intel            | Ethernet Connection (7) I219-LM      | 8     | e1000e     | [EFF399191D](<Mini Pc/Intel Client Systems/NUC9/NUC9i9QNX/519180459546/UBUNTU-20.04/5.13.0-25-GENERIC/X86_64/EFF399191D>) |
| 10ec:8136 | 17aa:368d | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 7     | r8169      | [462B8C10A5](<Mini Pc/Lenovo/H30-00/H30-00 90C2001MFR/1BF8ED927CEB/CLEAR-LINUX-OS-33760/5.8.11-988.NATIVE/X86_64/462B8C10A5>) |
| 10ec:8168 | 103c:8158 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 7     | r8169      | [702F310A99](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/642F86533F2F/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/702F310A99>) |
| 10ec:8168 | 17aa:3151 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 7     | r8169      | [5AC6CDC8FB](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A4001WUS/A25EA1475B0F/REBORNOS-ROLLING/5.16.9-ARCH1-1/X86_64/5AC6CDC8FB>) |
| 14e4:1686 | 106b:0099 | Broadcom         | NetXtreme BCM57766 Gigabit Ethern... | 7     | tg3        | [D09823163E](<Mini Pc/Apple/Macmini8/Macmini8,1/4D6AA7F4655B/UBUNTU-20.04/5.8.0-44-GENERIC/X86_64/D09823163E>) |
| 8086:15bb | 17aa:3136 | Intel            | Ethernet Connection (7) I219-LM      | 7     | e1000e     | [B3BA67D085](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10V8S06904/EAA513742A16/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/B3BA67D085>) |
| 10ec:8168 | 17aa:30b5 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 6     | r8169      | [538597F50A](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M53 10DE001HUS/36D92E1E56E1/ENDLESS-3.7.8/5.3.0-28-GENERIC/X86_64/538597F50A>) |
| 10ec:8168 | 103c:8267 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 5     | r8169      | [3C277DC3C1](<Mini Pc/Hewlett-Packard/t530/t530 Thin Client/982DFBB69A90/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3C277DC3C1>) |
| 10ec:8168 | 103c:82a5 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 5     | r8169      | [C47D9B3AE0](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 400 G3 DM/342D63741B55/ELEMENTARY-6.1/5.13.0-28-GENERIC/X86_64/C47D9B3AE0>) |
| 10ec:8168 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 5     | r8169      | [04D1FD85D9](<Mini Pc/CompuLab/Intense-PC/Intense-PC/62D6B61BDA7B/FEDORA-34/5.12.13-300.FC34.X86_64/X86_64/04D1FD85D9>) |
| 10ec:8168 | 17aa:30dd | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 5     | r8169      | [BD46C4BAC3](<Mini Pc/Lenovo/S200z/S200z 10HA000FRU/0E3D6DC0E64D/UBUNTU-20.04/5.4.0-99-GENERIC/X86_64/BD46C4BAC3>) |
| 10ec:8168 | 1b50:4606 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 5     | r8169      | [2882CF9963](<Mini Pc/NOBLEX/NB/NB1602/840F6A17AA98/DEBIAN-11/5.10.0-8-AMD64/X86_64/2882CF9963>) |
| 8086:15b8 | 17aa:3111 | Intel            | Ethernet Connection (2) I219-V       | 5     | e1000e     | [B9D4EFB68C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MR000XUK/3928CECFA48F/POP!_OS-21.10/5.15.15-76051515-GENERIC/X86_64/B9D4EFB68C>) |
| 10ec:8168 | 103c:84f5 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 4     | r8169      | [CF5DEA43E1](<Mini Pc/Hewlett-Packard/260/260 G3 DM/D334B500C95E/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/CF5DEA43E1>) |
| 10ec:8168 | 103c:8836 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 4     | r8168      | [DA34E7C710](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/DD273ADCD4AF/XUBUNTU-20.04/5.8.0-53-GENERIC/X86_64/DA34E7C710>) |
| 10ec:8168 | 17aa:312f | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 4     | r8169      | [5205C41BC5](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M625q 10TF002MGE/79CE2ACCD525/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/5205C41BC5>) |
| 10ec:8168 | 17aa:314d | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 4     | r8169      | [032DB5DB0F](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AHS0B200/B9CCA0A76C35/CENTOS-8/4.18.0-269.EL8.X86_64/X86_64/032DB5DB0F>) |
| 10ec:8168 | 17aa:3637 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 4     | r8169      | [9FC0FE4A5F](<Mini Pc/Lenovo/C20-00/C20-00 F0BB00VCAU/1522F026E3A1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/9FC0FE4A5F>) |
| 10ec:8168 | 17aa:368d | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 4     | r8169      | [03220F70D0](<Mini Pc/Lenovo/E50-00/E50-00 90BX003VUL/536000E6D70F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/03220F70D0>) |
| 8086:0d4d | 17aa:316e | Intel            | Ethernet Connection (11) I219-V      | 4     | e1000e     | [0224398912](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DUS4SQ00/DA9A8078DC3D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/0224398912>) |
| 8086:0d4f | 1043:8672 | Intel            | Ethernet Connection (10) I219-V      | 4     | e1000e     | [7A01C63401](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN62S/469668D35D11/DEBIAN-11/5.10.0-8-AMD64/X86_64/7A01C63401>) |
| 8086:15b7 | 103c:82c0 | Intel            | Ethernet Connection (2) I219-LM      | 4     | e1000e     | [AC904E9BCB](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G3 Workstation/90A7B6AE2869/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/AC904E9BCB>) |
| 8086:15be | 8086:0000 | Intel            | Ethernet Connection (6) I219-V       | 4     | e1000e     | [D9AC661777](<Mini Pc/Intel Client Systems/NUC8/NUC8i3CYS/F84856907C67/KALI-2021.3/5.10.0-KALI9-AMD64/X86_64/D9AC661777>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9df0 | 8086:0034 | Intel            | Cannon Point-LP CNVi [Wireless-AC]   | 162   | iwlwifi    | [C79A71B9DB](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/C0AF1D599D12/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C79A71B9DB>) |
| 8086:02f0 | 8086:0074 | Intel            | Comet Lake PCH-LP CNVi WiFi          | 93    | iwlwifi    | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:24fd | 8086:9010 | Intel            | Wireless 8265 / 8275                 | 75    | iwlwifi    | [7F8770AFC4](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/38F8ADEA821D/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/7F8770AFC4>) |
| 8086:3165 | 8086:4010 | Intel            | Wireless 3165                        | 69    | iwlwifi    | [762D0D5C0B](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-402/7B4966383EE1/DEBIAN-11/5.10.0-9-AMD64/X86_64/762D0D5C0B>) |
| 8086:095a | 8086:9010 | Intel            | Wireless 7265                        | 53    | iwlwifi    | [CEA504B47D](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-503/F250AC8777D6/CENTOS-STREAM/4.18.0-348.2.1.EL8_5.X86_64/X86_64/CEA504B47D>) |
| 8086:24fd | 8086:1010 | Intel            | Wireless 8265 / 8275                 | 50    | iwlwifi    | [317E098A9E](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/A75259B85C6D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/317E098A9E>) |
| 8086:24f3 | 8086:9010 | Intel            | Wireless 8260                        | 44    | iwlwifi    | [6879986BF2](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-505/29B4250B3145/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/6879986BF2>) |
| 8086:24fb | 8086:2110 | Intel            | Dual Band Wireless-AC 3168NGW [St... | 41    | iwlwifi    | [5BEEF7A5B1](<Mini Pc/Intel/NUC6/NUC6CAYH/0C6F2967B76D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5BEEF7A5B1>) |
| 8086:31dc | 8086:02a4 | Intel            | Gemini Lake PCH CNVi WiFi            | 39    | iwlwifi    | [E02C6336D6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/3F30AC0E5D22/ARTIX-ROLLING/5.16.3-ARTIX1-1/X86_64/E02C6336D6>) |
| 14e4:4331 | 14e4:4331 | Broadcom         | BCM4331 802.11a/b/g/n                | 37    | wl         | [C3A014CA22](<Mini Pc/Apple/Macmini6/Macmini6,2/F5E3810853BC/CLEAR-LINUX-OS-35970/5.13.13-1070.NATIVE/X86_64/C3A014CA22>) |
| 14e4:43a0 | 106b:013b | Broadcom Limited | BCM4360 802.11ac Wireless Network... | 37    | wl         | [5550136FFD](<Mini Pc/Apple/Macmini7/Macmini7,1/65598A0C8936/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/5550136FFD>) |
| 14e4:4331 | 106b:010e | Broadcom         | BCM4331 802.11a/b/g/n                | 34    | wl         | [7901968D67](<Mini Pc/Apple/Macmini6/Macmini6,1/357DADC601E4/MANJARO/5.16.11-2-MANJARO/X86_64/7901968D67>) |
| 14e4:4331 | 106b:00e4 | Broadcom Limited | BCM4331 802.11a/b/g/n                | 32    | wl         | [A2BA361F2C](<Mini Pc/Apple/Macmini5/Macmini5,1/C29061AA8B1E/ZORIN-16/5.11.0-43-GENERIC/X86_64/A2BA361F2C>) |
| 8086:3165 | 8086:8010 | Intel            | Wireless 3165                        | 31    | iwlwifi    | [78762D9561](<Mini Pc/Shenzhen Wangang Technology/AERO/AERO 2/503AFB8927C2/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/78762D9561>) |
| 8086:2723 | 8086:0084 | Intel            | Wi-Fi 6 AX200                        | 28    | iwlwifi    | [2F6DF3FFF6](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/86C8213ACE93/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2F6DF3FFF6>) |
| 14e4:4328 | 106b:0090 | Broadcom Limited | BCM4321 802.11a/b/g/n                | 24    | ssb        | [C3D19D1297](<Mini Pc/Apple/Macmini3/Macmini3,1/0C3107FBE1E9/UBUNTU-MATE-20.04/5.4.0-94-GENERIC/X86_64/C3D19D1297>) |
| 8086:08b3 | 8086:0070 | Intel            | Wireless 3160                        | 21    | iwlwifi    | [7EAB522138](<Mini Pc/ZOTAC/ZBOXNANO-ID/ZBOXNANO-ID67/C3933CE474DF/LINUXMINT-20.3/5.4.0-26-GENERIC/X86_64/7EAB522138>) |
| 8086:a0f0 | 8086:0074 | Intel            | Wi-Fi 6 AX201                        | 20    | iwlwifi    | [CA53435B36](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/26774C86D363/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/CA53435B36>) |
| 8086:24fd | 8086:0010 | Intel            | Wireless 8265 / 8275                 | 18    | iwlwifi    | [DFD0CB667C](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/0C45B1FBE800/DEBIAN-11/5.10.0-11-AMD64/X86_64/DFD0CB667C>) |
| 168c:001c | 106b:0086 | Qualcomm Atheros | AR242x / AR542x Wireless Network ... | 17    | ath5k      | [2075A95BFB](<Mini Pc/Apple/Macmini2/Macmini2,1/8B91B715078D/FEDORA-30/5.3.11-100.FC29.I686/I686/2075A95BFB>) |
| 14e4:4353 | 106b:0093 | Broadcom         | BCM43224 802.11a/b/g/n               | 16    | wl         | [D7F1687670](<Mini Pc/Apple/Macmini4/Macmini4,1/BCBD7A97BE65/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D7F1687670>) |
| 8086:3166 | 8086:4210 | Intel            | Dual Band Wireless-AC 3165 Plus B... | 13    | iwlwifi    | [1F9DF11A59](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MRCTO1WW/EFC9DED54B32/ARCO-ROLLING/5.16.2-ARCH1-1/X86_64/1F9DF11A59>) |
| 8086:31dc | 8086:0264 | Intel            | Gemini Lake PCH CNVi WiFi            | 11    | iwlwifi    | [2048DCBA92](<Mini Pc/BESSTAR Tech/N/N40/5987D958939E/UBUNTU-20.04/5.8.0-45-GENERIC/X86_64/2048DCBA92>) |
| 8086:3165 | 8086:8110 | Intel            | Wireless 3165                        | 10    | iwlwifi    | [76B5667130](<Mini Pc/MeLE Computer/Quieter/Quieter2/73E8BF27E06D/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/76B5667130>) |
| 8086:08b3 | 8086:8070 | Intel            | Wireless 3160                        | 9     | iwlwifi    | [0AE2257DF3](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/9C4C68096B25/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/0AE2257DF3>) |
| 8086:2526 | 8086:0014 | Intel            | Wireless-AC 9260                     | 9     | iwlwifi    | [5AC6CDC8FB](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A4001WUS/A25EA1475B0F/REBORNOS-ROLLING/5.16.9-ARCH1-1/X86_64/5AC6CDC8FB>) |
| 10ec:b723 | 10ec:b723 | Realtek Semic... | RTL8723BE PCIe Wireless Network A... | 8     | rtl8723be  | [A0C8ECBA6B](<Mini Pc/PCBOX/GAND/GAND/6B01BFCD3069/KDE-NEON-20.04/5.4.0-58-GENERIC/X86_64/A0C8ECBA6B>) |
| 14e4:4464 | 106b:07bf | Broadcom         | BCM4364 802.11ac Wireless Network... | 8     | brcmfmac   | [CA26CBBF22](<Mini Pc/Apple/Macmini8/Macmini8,1/F39A3C4B83EB/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/CA26CBBF22>) |
| 8086:a370 | 8086:0030 | Intel            | Cannon Lake PCH CNVi WiFi            | 6     | iwlwifi    | [B41631FF89](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CFCTO1WW/646F3FD65343/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/B41631FF89>) |
| 8086:24f3 | 8086:10b0 | Intel            | Wireless 8260                        | 5     | iwlwifi    | [CE81650620](<Mini Pc/CompuLab/fitlet/fitlet2/BEA0FF9DF81E/LINUXMINT-20.1/5.4.0-74-GENERIC/X86_64/CE81650620>) |
| 8086:2723 | 8086:008c | Intel            | Wi-Fi 6 AX200                        | 5     | iwlwifi    | [EFF399191D](<Mini Pc/Intel Client Systems/NUC9/NUC9i9QNX/519180459546/UBUNTU-20.04/5.13.0-25-GENERIC/X86_64/EFF399191D>) |
| 8086:31dc | 8086:0034 | Intel            | Gemini Lake PCH CNVi WiFi            | 5     | iwlwifi    | [1264EAC747](<Mini Pc/ASUSTek Computer/PN/PN40/E021532C4664/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/1264EAC747>) |
| 10ec:b723 | 17aa:b728 | Realtek Semic... | RTL8723BE PCIe Wireless Network A... | 4     | rtl8723be  | [538597F50A](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M53 10DE001HUS/36D92E1E56E1/ENDLESS-3.7.8/5.3.0-28-GENERIC/X86_64/538597F50A>) |
| 10ec:c821 | 17aa:c024 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 4     | 8821ce     | [CC222D78B9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VG001QRU/28BB5B3B7530/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/CC222D78B9>) |
| 14c3:0608 | 14c3:0608 | MEDIATEK         | Network controller                   | 4     |            | [8A85AEAF5A](<Mini Pc/AZW/GTR/GTR/BB648F57E2C2/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/8A85AEAF5A>) |
| 14e4:4353 | 14e4:04d8 | Broadcom Limited | BCM43224 802.11a/b/g/n               | 4     | wl         | [AF1F6C2CD7](<Mini Pc/AMI/Aptio/Aptio CRB/7BF12BD8CA76/XUBUNTU-20.04/5.4.0-40-GENERIC/X86_64/AF1F6C2CD7>) |
| 168c:002b | 1a3b:2c37 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 4     | ath9k      | [BE96F10577](<Mini Pc/ZOTAC/ZBOX-AD/ZBOX-AD04/0EEEABB8A5DF/UBUNTU-20.04/5.11.0-44-GENERIC/X86_64/BE96F10577>) |
| 168c:0042 | 1a3b:2b51 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 4     | ath10k_pci | [B78185D870](<Mini Pc/Chuwi/HeroBox/HeroBox/0564D825BBAD/DEBIAN-11/5.15.0-0.BPO.3-AMD64/X86_64/B78185D870>) |
| 8086:06f0 | 8086:0070 | Intel            | Comet Lake PCH CNVi WiFi             | 4     | iwlwifi    | [EE32355409](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/EE29838C95B5/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/EE32355409>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 4     | iwlwifi    | [0028753E4D](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G3 DM/341483C13D08/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/0028753E4D>) |
| 8086:2723 | 1a56:1654 | Intel            | Wi-Fi 6 AX200                        | 4     | iwlwifi    | [57676DE735](<Mini Pc/ZOTAC/ZBOX-ECM7307/ZBOX-ECM73070C-53060C/C458DE01446F/ARCO-ROLLING/5.13.12-ARCH1-1/X86_64/57676DE735>) |
| 8086:4df0 | 8086:0034 | Intel            | Wi-Fi 6 AX201 160MHz                 | 4     | iwlwifi    | [B416BA575D](<Mini Pc/ASUSTek Computer/PN/PN41/20388AD561BB/ZORIN-16/5.13.0-30-GENERIC/X86_64/B416BA575D>) |
| 10ec:c822 | 17aa:c123 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 3     | rtw_8822ce | [F7CA8D84CA](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A4000GGE/BA13EDD10A17/FEDORA-35/5.15.6-200.FC35.X86_64/X86_64/F7CA8D84CA>) |
| 1814:3290 | 1a3b:2b87 | Ralink           | RT3290 Wireless 802.11n 1T/1R PCIe   | 3     | rt2800pci  | [121F403E29](<Mini Pc/ZOTAC/ZBOXNANO-AD/ZBOXNANO-AD10/F40922BC09C5/POP!_OS-20.04/5.4.0-7634-GENERIC/X86_64/121F403E29>) |
| 8086:06f0 | 8086:0074 | Intel            | Comet Lake PCH CNVi WiFi             | 3     | iwlwifi    | [D99CA518F9](<Mini Pc/Lenovo/IdeaCentre/IdeaCentre Mini 5 01IMH05 90Q60000UT/70492AEAC407/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D99CA518F9>) |
| 8086:0892 | 8086:0062 | Intel            | Centrino Wireless-N 135              | 3     | iwlwifi    | [4D23C29B62](<Mini Pc/ZOTAC/ZBOX-ID88/ZBOX-ID88-ID89-ID90/A1935E253AD1/KDE-NEON-20.04/5.4.0-67-GENERIC/X86_64/4D23C29B62>) |
| 8086:0896 | 8086:5005 | Intel            | Centrino Wireless-N 130              | 3     | iwlwifi    | [0909932423](<Mini Pc/ZOTAC/ZBOX-ID/ZBOX-ID81/F7860DA1FE29/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/0909932423>) |
| 8086:24fd | 8086:0110 | Intel            | Wireless 8265 / 8275                 | 3     | iwlwifi    | [4E0BA9D6D3](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50-E1/5671376EA6FB/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/4E0BA9D6D3>) |
| 8086:a0f0 | 8086:0070 | Intel            | Wi-Fi 6 AX201                        | 3     | iwlwifi    | [B23894B3E4](<Mini Pc/Intel Client Systems/NUC11/NUC11TNHv7/CD64B645A9A3/CLEAR-LINUX-OS-35250/5.15.1-1089.NATIVE/X86_64/B23894B3E4>) |
| 8086:a370 | 8086:0034 | Intel            | Cannon Lake PCH CNVi WiFi            | 3     | iwlwifi    | [C15E7F2A47](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G4 Workstation/DA084C88EC03/ZORIN-15/5.4.0-66-GENERIC/X86_64/C15E7F2A47>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:157b | 8086:0000 | Intel            | I210 Gigabit Network Connection      | 35    | igb        | [317E098A9E](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/A75259B85C6D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/317E098A9E>) |
| 8086:1533 | ffff:0000 | Intel            | I210 Gigabit Network Connection      | 22    | igb        | [BF7C2C6D9B](<Mini Pc/NEXCOM/VTC/VTC1010/6EF054560413/DEBIAN-11/5.10.0-11-AMD64/X86_64/BF7C2C6D9B>) |
| 8086:1539 | 8086:0000 | Intel            | I211 Gigabit Network Connection      | 22    | igb        | [C2474EED31](<Mini Pc/AMI/Aptio/Aptio CRB/C5490E733A08/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/C2474EED31>) |
| 10ec:8125 | 1043:87d7 | Realtek Semic... | RTL8125 2.5GbE Controller            | 12    | r8169      | [B416BA575D](<Mini Pc/ASUSTek Computer/PN/PN41/20388AD561BB/ZORIN-16/5.13.0-30-GENERIC/X86_64/B416BA575D>) |
| 10ec:8125 | 10ec:0123 | Realtek Semic... | RTL8125 2.5GbE Controller            | 4     | r8169      | [8A85AEAF5A](<Mini Pc/AZW/GTR/GTR/BB648F57E2C2/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/8A85AEAF5A>) |
| 8086:1521 | 15d9:0652 | Intel            | I350 Gigabit Network Connection      | 3     | igb        | [8D4CBF243D](<Mini Pc/Supermicro/SYS-5039/SYS-5039MS-H12TRF/C29A8D8B7AFC/ROSA-2021.1/5.10.56-GENERIC-1ROSA2021.1-X86_64/X86_64/8D4CBF243D>) |
| 8086:1502 | 8086:0000 | Intel            | 82579LM Gigabit Network Connectio... | 2     | e1000e     | [04D1FD85D9](<Mini Pc/CompuLab/Intense-PC/Intense-PC/62D6B61BDA7B/FEDORA-34/5.12.13-300.FC34.X86_64/X86_64/04D1FD85D9>) |
| 8086:1533 | 1ab6:0214 | Intel            | I210 Gigabit Network Connection      | 2     | igb        | [57130AC0AB](<Mini Pc/Intel Client Systems/NUC8/NUC8i7BEH/93AEAB1C8291/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/57130AC0AB>) |
| 8086:1539 | 8086:2080 | Intel            | I211 Gigabit Network Connection      | 2     | igb        | [745C35E31C](<Mini Pc/Intel Client Systems/NUC8/NUC8CCHK/59E5DD9DCBC3/UBUNTU-20.04/5.4.0-31-GENERIC/X86_64/745C35E31C>) |
| 8086:1093 | 8086:0001 | Intel            | PRO/100 VM Network Connection        | 1     | e100       | [10DB69DD6C](<Mini Pc/Kontron/SMX/SMX945/327FC59121CA/UBUNTU-18.04/4.15.0-88-GENERIC/I686/10DB69DD6C>) |
| 8086:10fe | 17aa:3605 | Intel            | 82552 10/100 Network Connection      | 1     | e100       | [F077B2F98E](<Mini Pc/Lenovo/3000/3000 IdeaCentre Q150 10053/8A86675CFC31/UBUNTU-18.04/5.0.0-27-GENERIC/X86_64/F077B2F98E>) |
| 8086:1503 | 1734:11d9 | Intel            | 82579V Gigabit Network Connection    | 1     | e1000e     | [FC67594808](<Mini Pc/Fujitsu/ESPRIMO/ESPRIMO Q510/7ECBADB17C83/UBUNTU-16.04/4.15.0-51-GENERIC/X86_64/FC67594808>) |
| 8086:150c | 8086:0000 | Intel            | 82583V Gigabit Network Connection    | 1     | e1000e     | [F483DDC44F](<Mini Pc/AMI/Aptio/Aptio CRB/CA0946537674/ALPINE-3.15.0/5.15.12-0-LTS/X86_64/F483DDC44F>) |
| 8086:1533 | 15bd:100a | Intel            | I210 Gigabit Network Connection      | 1     | igb        | [593A489E8D](<Mini Pc/ARBOR/LYNC/LYNC-712/F11739CA6754/ALT-9.1/5.4.51-STD-DEF-ALT1/X86_64/593A489E8D>) |
| 8086:1539 | 1043:85f0 | Intel            | I211 Gigabit Network Connection      | 1     | igb        | [6C00869D7B](<Mini Pc/ASUSTek Computer/PN/PN41/868E1EC59BE7/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/6C00869D7B>) |
| 8086:1539 | 1297:4033 | Intel            | I211 Gigabit Network Connection      | 1     | igb        | [B31E28E55F](<Mini Pc/Shuttle/XS35/XS35V5/00878A051AA2/UBUNTU-19.10/5.3.0-42-GENERIC/X86_64/B31E28E55F>) |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a126 |           | Intel            | 100 Series/C230 Series Chipset Fa... | 3     | intel_t... | [7348D34142](<Mini Pc/ZOTAC/ZBOX-EN1070/ZBOX-EN1070-1060/0CBF4FF1BBBE/LINUXMINT-20.2/5.13.0-22-GENERIC/X86_64/7348D34142>) |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 106b:1801 | 106b:1801 | Apple            | T2 Bridge Controller                 | 8     |            | [CA26CBBF22](<Mini Pc/Apple/Macmini8/Macmini8,1/F39A3C4B83EB/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/CA26CBBF22>) |
| 106b:1802 | 106b:1802 | Apple            | T2 Secure Enclave Processor          | 8     |            | [CA26CBBF22](<Mini Pc/Apple/Macmini8/Macmini8,1/F39A3C4B83EB/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/CA26CBBF22>) |
| 1022:15e6 | 1022:15e4 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 5     | i2c_amd... | [56F9A83D77](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75n 11GW000BUS/8D95E87EDCE7/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/56F9A83D77>) |
| 8086:a135 | 15d9:0898 | Intel            | 100 Series/C230 Series Chipset Fa... | 3     | intel_i... | [8D4CBF243D](<Mini Pc/Supermicro/SYS-5039/SYS-5039MS-H12TRF/C29A8D8B7AFC/ROSA-2021.1/5.10.56-GENERIC-1ROSA2021.1-X86_64/X86_64/8D4CBF243D>) |

### Performance counters (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:27a3 |           | Intel            | 945GM/GU Chipset Hardware Monitor... | 17    |            | [2075A95BFB](<Mini Pc/Apple/Macmini2/Macmini2,1/8B91B715078D/FEDORA-30/5.3.11-100.FC29.I686/I686/2075A95BFB>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14e4:16bc | 14e4:0000 | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 140   | sdhci_pci  | [5550136FFD](<Mini Pc/Apple/Macmini7/Macmini7,1/65598A0C8936/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/5550136FFD>) |
| 17a0:9755 | 8086:2081 | Genesys Logic    | GL9755 SD Host Controller            | 86    | sdhci_pci  | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 39    | sdhci_pci  | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 1217:8621 | 8086:2073 | O2 Micro         | SD/MMC Card Reader Controller        | 38    | sdhci_pci  | [317E098A9E](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/A75259B85C6D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/317E098A9E>) |
| 8086:31cc | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 37    | sdhci_pci  | [E02C6336D6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/3F30AC0E5D22/ARTIX-ROLLING/5.16.3-ARTIX1-1/X86_64/E02C6336D6>) |
| 8086:5aca | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 31    | sdhci_pci  | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 8086:5ad0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 29    | sdhci_pci  | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 1217:8621 | 8086:2064 | O2 Micro         | SD/MMC Card Reader Controller        | 27    | sdhci_pci  | [86D379E9D5](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/54383D955906/UBUNTU-20.10/5.8.0-63-GENERIC/X86_64/86D379E9D5>) |
| 8086:2296 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 22    | sdhci_pci  | [207E311CFC](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-102/8054EC01AC51/ASTRALINUXCE-2.12.44/5.10.0-1038.40-GENERIC/X86_64/207E311CFC>) |
| 8086:9d2d | 8086:2063 | Intel            | Sunrise Point-LP Secure Digital I... | 17    | sdhci_pci  | [DB86E412B7](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-502/DB7A6FF83407/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/DB86E412B7>) |
| 8086:31cc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 11    | sdhci_pci  | [76B5667130](<Mini Pc/MeLE Computer/Quieter/Quieter2/73E8BF27E06D/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/76B5667130>) |
| 8086:31cc | 8086:31cc | Intel            | Celeron/Pentium Silver Processor ... | 10    | sdhci_pci  | [34B97F062B](<Mini Pc/Chuwi/HeroBox/HeroBox/1BAACBF37863/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/34B97F062B>) |
| 8086:5ad0 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 10    | sdhci_pci  | [6874BC3566](<Mini Pc/BESSTAR Tech/N/N33/2A74991B0C12/UBUNTU-20.04/5.11.0-44-GENERIC/X86_64/6874BC3566>) |
| 8086:31d0 | 8086:7270 | Intel            | SD Host Controller                   | 9     | sdhci_pci  | [78762D9561](<Mini Pc/Shenzhen Wangang Technology/AERO/AERO 2/503AFB8927C2/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/78762D9561>) |
| 8086:5acc | 19da:b325 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 6     | sdhci_pci  | [23BDDBF63A](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/0FE806EB02BE/LINUXMINT-20.1/5.4.0-65-GENERIC/X86_64/23BDDBF63A>) |
| 8086:0f16 | 8086:0f16 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 5     | sdhci_pci  | [BF7C2C6D9B](<Mini Pc/NEXCOM/VTC/VTC1010/6EF054560413/DEBIAN-11/5.10.0-11-AMD64/X86_64/BF7C2C6D9B>) |
| 8086:4dc4 | 1043:8813 | Intel            | Jasper Lake SCS1: eMMC Controller    | 5     | sdhci_pci  | [B416BA575D](<Mini Pc/ASUSTek Computer/PN/PN41/20388AD561BB/ZORIN-16/5.13.0-30-GENERIC/X86_64/B416BA575D>) |
| 8086:0f50 |           | Intel            | Atom Processor E3800 Series eMMC ... | 4     | sdhci_pci  | [34EFC38E50](<Mini Pc/ZOTAC/ZBOX-CI320NANO/ZBOX-CI320NANO series/5BD80C26892B/XUBUNTU-18.04/4.15.0-139-GENERIC/X86_64/34EFC38E50>) |
| 8086:5acc | 8086:5acc | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | sdhci_pci  | [6874BC3566](<Mini Pc/BESSTAR Tech/N/N33/2A74991B0C12/UBUNTU-20.04/5.11.0-44-GENERIC/X86_64/6874BC3566>) |
| 8086:02c4 | 8086:7270 | Intel            | Comet Lake PCH-LP SCS1: eMMC         | 3     | sdhci_pci  | [934F2F075C](<Mini Pc/AZW/SEi/SEi/2957B295DEBC/LINUXMINT-20/5.4.0-90-GENERIC/X86_64/934F2F075C>) |
| 8086:0f16 | 19da:b219 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     | sdhci_pci  | [34EFC38E50](<Mini Pc/ZOTAC/ZBOX-CI320NANO/ZBOX-CI320NANO series/5BD80C26892B/XUBUNTU-18.04/4.15.0-139-GENERIC/X86_64/34EFC38E50>) |
| 8086:2294 | 1462:b120 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | sdhci_pci  | [FDE91E565C](<Mini Pc/MSI/MS-B/MS-B120/B29C493EAF7D/UBUNTU-18.04/5.3.0-28-GENERIC/X86_64/FDE91E565C>) |
| 8086:2294 | 19da:b273 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | sdhci_pci  | [0D05B404DD](<Mini Pc/ZOTAC/ZBOX-BI/ZBOX-BI324/C214E8207F22/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/0D05B404DD>) |
| 8086:2294 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | sdhci_pci  | [DCC1CCB590](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-408/59A86BD4C203/LINUXMINT-19.3/5.4.0-80-GENERIC/X86_64/DCC1CCB590>) |
| 8086:2294 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | sdhci_pci  | [10C1838B9D](<Mini Pc/AMI/Aptio/Aptio CRB/6C7827486731/DEBIAN-11/5.10.0-8-AMD64/X86_64/10C1838B9D>) |
| 8086:2296 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | sdhci_pci  | [10C1838B9D](<Mini Pc/AMI/Aptio/Aptio CRB/6C7827486731/DEBIAN-11/5.10.0-8-AMD64/X86_64/10C1838B9D>) |
| 8086:5aca | 8086:5aca | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | sdhci_pci  | [6874BC3566](<Mini Pc/BESSTAR Tech/N/N33/2A74991B0C12/UBUNTU-20.04/5.11.0-44-GENERIC/X86_64/6874BC3566>) |
| 8086:5acc | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | sdhci_pci  | [C65572E240](<Mini Pc/Intel/NUC6/NUC6CAYS/4E13C3ECB9A9/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/C65572E240>) |
| 1022:7806 | 19da:a261 | AMD              | FCH SD Flash Controller              | 2     | sdhci_pci  | [8C3CA64606](<Mini Pc/ZOTAC/ZBOXNXS-AD/ZBOXNXS-AD13/5DDED330808E/LINUXMINT-20.1/5.4.0-67-GENERIC/X86_64/8C3CA64606>) |
| 8086:2295 | 1028:07c1 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | sdhci_pci  | [74450C0224](<Mini Pc/Dell/Wyse/Wyse 3040 Thin Client/159E337F7751/DEBIAN-11/5.10.0-11-AMD64/X86_64/74450C0224>) |
| 8086:31cc | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 2     | sdhci_pci  | [E46F325CBA](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/EEB3D49D8109/ENDLESS-3.8.3/5.4.0-19-GENERIC/X86_64/E46F325CBA>) |
| 8086:5acc | 8086:2080 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | sdhci_pci  | [745C35E31C](<Mini Pc/Intel Client Systems/NUC8/NUC8CCHK/59E5DD9DCBC3/UBUNTU-20.04/5.4.0-31-GENERIC/X86_64/745C35E31C>) |
| 8086:9d2b | 1043:8694 | Intel            | Skylake-U/Y SCC: eMMC                | 2     | sdhci_pci  | [847A813A2C](<Mini Pc/ASUSTek Computer/PN60/PN60-R/1051BA1EB3B1/MANJARO/5.10.15-1-MANJARO/X86_64/847A813A2C>) |
| 8086:9dc4 | 8086:2075 | Intel            | Cannon Point-LP SD Host Controller   | 2     | sdhci_pci  | [D9AC661777](<Mini Pc/Intel Client Systems/NUC8/NUC8i3CYS/F84856907C67/KALI-2021.3/5.10.0-KALI9-AMD64/X86_64/D9AC661777>) |
| 8086:9df5 | 8086:2075 | Intel            | BayHubTech Integrated SD controller  | 2     | sdhci_pci  | [D9AC661777](<Mini Pc/Intel Client Systems/NUC8/NUC8i3CYS/F84856907C67/KALI-2021.3/5.10.0-KALI9-AMD64/X86_64/D9AC661777>) |
| 1022:7806 | 19da:b218 | AMD              | FCH SD Flash Controller              | 1     | sdhci_pci  | [EB76FF1C3F](<Mini Pc/ZOTAC/ZBOXNANO-AQ/ZBOXNANO-AQ02/652E2251D263/ARCO-ROLLING/5.11.21-HARDENED1-2-HARDENED/X86_64/EB76FF1C3F>) |
| 1022:7813 | 1022:7806 | AMD              | FCH SD Flash Controller              | 1     | sdhci_pci  | [6B1C47D1B5](<Mini Pc/CompuLab/fit-PC/fit-PC4/EE1B264492ED/UBUNTU-20.04/5.4.0-29-GENERIC/X86_64/6B1C47D1B5>) |
| 1217:8520 | 1217:0002 | O2 Micro         | SD/MMC Card Reader Controller        | 1     |            | [493278D567](<Mini Pc/ZOTAC/ZBOX/ZBOX/7D34FF7AFACD/GENTOO-2.6/5.4.80-GENTOO-R1-COMPACT-0.1/X86_64/493278D567>) |
| 17a0:9755 | 8086:3004 | Genesys Logic    | GL9755 SD Host Controller            | 1     | sdhci_pci  | [CA53435B36](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/26774C86D363/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/CA53435B36>) |
| 8086:0f15 | 19da:b219 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | sdhci_pci  | [4BC48CCC62](<Mini Pc/ZOTAC/ZBOX-CI320NANO/ZBOX-CI320NANO series/D08D302F039C/UBUNTU-18.04/5.3.0-26-GENERIC/X86_64/4BC48CCC62>) |
| 8086:2294 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | sdhci_pci  | [175DDA01F6](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/92EB5D9C4CEF/LUBUNTU-20.04/5.4.0-91-GENERIC/X86_64/175DDA01F6>) |
| 8086:5aca | 19da:b342 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | sdhci_pci  | [9A0C888104](<Mini Pc/ZOTAC/ZBOX-PI/ZBOX-PI335/F87E9860569F/UBUNTU-18.04/4.15.0-88-GENERIC/X86_64/9A0C888104>) |
| 8086:5acc | 19da:b342 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | sdhci_pci  | [9A0C888104](<Mini Pc/ZOTAC/ZBOX-PI/ZBOX-PI335/F87E9860569F/UBUNTU-18.04/4.15.0-88-GENERIC/X86_64/9A0C888104>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9da4 | 8086:2074 | Intel            | Cannon Point-LP SPI Controller       | 156   |            | [C79A71B9DB](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/C0AF1D599D12/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C79A71B9DB>) |
| 8086:02a4 | 8086:2081 | Intel            | Comet Lake SPI (flash) Controller    | 89    | intel_s... | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:02e8 | 8086:2081 | Intel            | Serial IO I2C Host Controller        | 89    | intel_l... | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:02ea | 8086:2081 | Intel            | Comet Lake PCH-LP LPSS: I2C Contr... | 89    | intel_l... | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:5ac8 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 29    | pwm_lpss   | [5BEEF7A5B1](<Mini Pc/Intel/NUC6/NUC6CAYH/0C6F2967B76D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5BEEF7A5B1>) |
| 8086:22c6 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 22    | i2c_des... | [207E311CFC](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-102/8054EC01AC51/ASTRALINUXCE-2.12.44/5.10.0-1038.40-GENERIC/X86_64/207E311CFC>) |
| 8086:22c7 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 22    | i2c_des... | [207E311CFC](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-102/8054EC01AC51/ASTRALINUXCE-2.12.44/5.10.0-1038.40-GENERIC/X86_64/207E311CFC>) |
| 8086:a0a4 | 8086:3004 | Intel            | Tiger Lake-LP SPI Controller         | 15    | intel_spi  | [CA53435B36](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/26774C86D363/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/CA53435B36>) |
| 8086:a0e8 | 8086:3004 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 15    | intel_l... | [CA53435B36](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/26774C86D363/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/CA53435B36>) |
| 8086:a324 | 17aa:312d | Intel            | Cannon Lake PCH SPI Controller       | 15    |            | [88A943EC80](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T700BHBL/970C8BB93481/DEBIAN-11/5.10.0-11-AMD64/X86_64/88A943EC80>) |
| 8086:5ac8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 12    | pwm_lpss   | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 8086:a324 | 17aa:3135 | Intel            | Cannon Lake PCH SPI Controller       | 8     |            | [C43EF85B97](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920x 10S1S07700/59BDC87984FB/ROSA-2016.1/5.4.40-GENERIC-1ROSA-X86_64/X86_64/C43EF85B97>) |
| 8086:a324 | 8086:7270 | Intel            | Cannon Lake PCH SPI Controller       | 8     | intel_s... | [CA26CBBF22](<Mini Pc/Apple/Macmini8/Macmini8,1/F39A3C4B83EB/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/CA26CBBF22>) |
| 8086:a324 | 17aa:3136 | Intel            | Cannon Lake PCH SPI Controller       | 7     |            | [B3BA67D085](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10V8S06904/EAA513742A16/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/B3BA67D085>) |
| 8086:9da4 | 17aa:314d | Intel            | Cannon Point-LP SPI Controller       | 6     |            | [BD2F6222E5](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AD002DGE/D203F33318BC/MANJARO-21.1.0/5.10.53-1-MANJARO/X86_64/BD2F6222E5>) |
| 8086:a324 | 8086:2089 | Intel            | Cannon Lake PCH SPI Controller       | 6     |            | [EFF399191D](<Mini Pc/Intel Client Systems/NUC9/NUC9i9QNX/519180459546/UBUNTU-20.04/5.13.0-25-GENERIC/X86_64/EFF399191D>) |
| 8086:a368 | 8086:2089 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 6     | intel_l... | [EFF399191D](<Mini Pc/Intel Client Systems/NUC9/NUC9i9QNX/519180459546/UBUNTU-20.04/5.13.0-25-GENERIC/X86_64/EFF399191D>) |
| 8086:a369 | 8086:2089 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 6     | intel_l... | [EFF399191D](<Mini Pc/Intel Client Systems/NUC9/NUC9i9QNX/519180459546/UBUNTU-20.04/5.13.0-25-GENERIC/X86_64/EFF399191D>) |
| 8086:4da4 | 1043:8813 | Intel            | Jasper Lake SPI Controller           | 5     | intel_s... | [B416BA575D](<Mini Pc/ASUSTek Computer/PN/PN41/20388AD561BB/ZORIN-16/5.13.0-30-GENERIC/X86_64/B416BA575D>) |
| 8086:4dab |           | Intel            | Jasper Lake LPSS: SPI Controller #1  | 5     | intel_l... | [B416BA575D](<Mini Pc/ASUSTek Computer/PN/PN41/20388AD561BB/ZORIN-16/5.13.0-30-GENERIC/X86_64/B416BA575D>) |
| 8086:4dc5 | 1043:8813 | Intel            | Jasper Lake LPSS: I2C Controller #4  | 5     | intel_l... | [B416BA575D](<Mini Pc/ASUSTek Computer/PN/PN41/20388AD561BB/ZORIN-16/5.13.0-30-GENERIC/X86_64/B416BA575D>) |
| 8086:4dc6 | 1043:8813 | Intel            | Jasper Lake LPSS: I2C Controller #5  | 5     | intel_l... | [B416BA575D](<Mini Pc/ASUSTek Computer/PN/PN41/20388AD561BB/ZORIN-16/5.13.0-30-GENERIC/X86_64/B416BA575D>) |
| 8086:4de8 | 1043:8813 | Intel            | Serial IO I2C Host Controller        | 5     | intel_l... | [B416BA575D](<Mini Pc/ASUSTek Computer/PN/PN41/20388AD561BB/ZORIN-16/5.13.0-30-GENERIC/X86_64/B416BA575D>) |
| 8086:4dea | 1043:8813 | Intel            | Jasper Lake LPSS: I2C Controller #2  | 5     | intel_l... | [B416BA575D](<Mini Pc/ASUSTek Computer/PN/PN41/20388AD561BB/ZORIN-16/5.13.0-30-GENERIC/X86_64/B416BA575D>) |
| 8086:02a4 | 1043:87bd | Intel            | Comet Lake SPI (flash) Controller    | 4     | intel_s... | [7A01C63401](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN62S/469668D35D11/DEBIAN-11/5.10.0-8-AMD64/X86_64/7A01C63401>) |
| 8086:02e8 | 1043:87bd | Intel            | Serial IO I2C Host Controller        | 4     | intel_l... | [7A01C63401](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN62S/469668D35D11/DEBIAN-11/5.10.0-8-AMD64/X86_64/7A01C63401>) |
| 8086:02e9 | 1043:87bd | Intel            | Comet Lake Serial IO I2C Host Con... | 4     | intel_l... | [7A01C63401](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN62S/469668D35D11/DEBIAN-11/5.10.0-8-AMD64/X86_64/7A01C63401>) |
| 8086:06a4 | 17aa:316e | Intel            | Comet Lake PCH SPI Controller        | 4     | intel_s... | [0224398912](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DUS4SQ00/DA9A8078DC3D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/0224398912>) |
| 10de:1adb | 8086:2090 | Nvidia           | TU106 USB Type-C UCSI Controller     | 3     | i2c_nvi... | [1158CBFEAA](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/894923AF1BC3/DEBIAN-11/5.10.0-10-AMD64/X86_64/1158CBFEAA>) |
| 8086:02a4 | 8086:7270 | Intel            | Comet Lake SPI (flash) Controller    | 3     | intel_s... | [934F2F075C](<Mini Pc/AZW/SEi/SEi/2957B295DEBC/LINUXMINT-20/5.4.0-90-GENERIC/X86_64/934F2F075C>) |
| 8086:02e8 | 8086:7270 | Intel            | Serial IO I2C Host Controller        | 3     | intel_lpss | [934F2F075C](<Mini Pc/AZW/SEi/SEi/2957B295DEBC/LINUXMINT-20/5.4.0-90-GENERIC/X86_64/934F2F075C>) |
| 8086:06a4 | 17aa:3172 | Intel            | Comet Lake PCH SPI Controller        | 3     | intel_s... | [EE32355409](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/EE29838C95B5/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/EE32355409>) |
| 8086:a0a4 | 8086:2090 | Intel            | Tiger Lake-LP SPI Controller         | 3     | intel_s... | [1158CBFEAA](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/894923AF1BC3/DEBIAN-11/5.10.0-10-AMD64/X86_64/1158CBFEAA>) |
| 8086:a0a4 | 8086:3002 | Intel            | Tiger Lake-LP SPI Controller         | 3     |            | [23FCE48DF7](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKi7/5BE9775954D9/FEDORA-35/5.16.5-200.FC35.X86_64/X86_64/23FCE48DF7>) |
| 8086:a0e8 | 8086:2090 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 3     | intel_l... | [1158CBFEAA](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/894923AF1BC3/DEBIAN-11/5.10.0-10-AMD64/X86_64/1158CBFEAA>) |
| 8086:a0e8 | 8086:3002 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 3     | intel_l... | [23FCE48DF7](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKi7/5BE9775954D9/FEDORA-35/5.16.5-200.FC35.X86_64/X86_64/23FCE48DF7>) |
| 8086:a0e9 | 8086:2090 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 3     | intel_l... | [1158CBFEAA](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/894923AF1BC3/DEBIAN-11/5.10.0-10-AMD64/X86_64/1158CBFEAA>) |
| 8086:a0e9 | 8086:3002 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 3     | intel_l... | [23FCE48DF7](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKi7/5BE9775954D9/FEDORA-35/5.16.5-200.FC35.X86_64/X86_64/23FCE48DF7>) |
| 8086:06a4 | 103c:8710 | Intel            | Comet Lake PCH SPI Controller        | 2     |            | [B2A212246B](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G6 Desktop Mini PC/1AD35AB4DD59/CENTOS-7/5.4.118-1.EL7.ELREPO.X86_64/X86_64/B2A212246B>) |
| 8086:06a4 | 103c:871a | Intel            | Comet Lake PCH SPI Controller        | 2     |            | [FDBB17D3B2](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 400 G6 Desktop Mini PC/4C0794A3D051/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/FDBB17D3B2>) |
| 8086:06a4 | 19da:b440 | Intel            | Comet Lake PCH SPI Controller        | 2     | intel_s... | [57676DE735](<Mini Pc/ZOTAC/ZBOX-ECM7307/ZBOX-ECM73070C-53060C/C458DE01446F/ARCO-ROLLING/5.13.12-ARCH1-1/X86_64/57676DE735>) |
| 8086:31c8 | 8086:7270 | Intel            | Serial bus controller                | 2     | pwm_lpss   | [76B5667130](<Mini Pc/MeLE Computer/Quieter/Quieter2/73E8BF27E06D/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/76B5667130>) |
| 8086:9da4 | 1043:8790 | Intel            | Cannon Point-LP SPI Controller       | 2     |            | [45389EF622](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN61/9FE5C35BEA82/KDE-NEON-20.04/5.4.0-67-GENERIC/X86_64/45389EF622>) |
| 8086:9da4 | 17aa:314c | Intel            | Cannon Point-LP SPI Controller       | 2     |            | [0F66B49A44](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AD000YMX/8552A91D7647/ALPINE-3.13.0_ALPHA20200917/5.4.65-0-LTS/X86_64/0F66B49A44>) |
| 8086:9da4 | 8086:2075 | Intel            | Cannon Point-LP SPI Controller       | 2     |            | [D9AC661777](<Mini Pc/Intel Client Systems/NUC8/NUC8i3CYS/F84856907C67/KALI-2021.3/5.10.0-KALI9-AMD64/X86_64/D9AC661777>) |
| 8086:9da4 | 8086:2079 | Intel            | Cannon Point-LP SPI Controller       | 2     |            | [45B14891D4](<Mini Pc/Intel Client Systems/NUC8/NUC8i5INH/CFC9656AFB5C/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/45B14891D4>) |
| 8086:9dc5 | 8086:2075 | Intel            | Cannon Point-LP Serial IO I2C Hos... | 2     | intel_lpss | [D9AC661777](<Mini Pc/Intel Client Systems/NUC8/NUC8i3CYS/F84856907C67/KALI-2021.3/5.10.0-KALI9-AMD64/X86_64/D9AC661777>) |
| 8086:9dc5 | 8086:2079 | Intel            | Cannon Point-LP Serial IO I2C Hos... | 2     | intel_lpss | [45B14891D4](<Mini Pc/Intel Client Systems/NUC8/NUC8i5INH/CFC9656AFB5C/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/45B14891D4>) |
| 8086:9de8 | 8086:2075 | Intel            | Cannon Point-LP Serial IO I2C Con... | 2     | intel_lpss | [D9AC661777](<Mini Pc/Intel Client Systems/NUC8/NUC8i3CYS/F84856907C67/KALI-2021.3/5.10.0-KALI9-AMD64/X86_64/D9AC661777>) |
| 8086:9de8 | 8086:2079 | Intel            | Cannon Point-LP Serial IO I2C Con... | 2     | intel_lpss | [45B14891D4](<Mini Pc/Intel Client Systems/NUC8/NUC8i5INH/CFC9656AFB5C/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/45B14891D4>) |

### Serial controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:816a | 1043:85b5 | Realtek Semic... | RTL8111xP UART #1                    | 19    | serial     | [2F6DF3FFF6](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/86C8213ACE93/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2F6DF3FFF6>) |
| 10ec:816b | 1043:85b5 | Realtek Semic... | RTL8111xP UART #2                    | 19    | serial     | [2F6DF3FFF6](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/86C8213ACE93/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2F6DF3FFF6>) |
| 8086:9d3d | 8086:2070 | Intel            | Sunrise Point-LP Active Managemen... | 14    | serial     | [65AE59D048](<Mini Pc/Intel Client Systems/NUC7/NUC7i7DNKE/491DF6CA7E6C/ARCH/5.16.2-ARCH1-1/X86_64/65AE59D048>) |
| 10ec:816a | 10ec:8168 | Realtek Semic... | RTL8111xP UART #1                    | 10    | serial     | [8366A84CDB](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/F373E702B28B/XUBUNTU-20.04/5.13.0-28-GENERIC/X86_64/8366A84CDB>) |
| 10ec:816a | 17aa:3130 | Realtek Semic... | RTL8111xP UART #1                    | 10    | serial     | [CC222D78B9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VG001QRU/28BB5B3B7530/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/CC222D78B9>) |
| 10ec:816b | 17aa:3130 | Realtek Semic... | RTL8111xP UART #2                    | 10    | serial     | [CC222D78B9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VG001QRU/28BB5B3B7530/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/CC222D78B9>) |
| 8086:a2bd | 103c:829a | Intel            | 200 Series Chipset Family KT Redi... | 8     | serial     | [67A56E0954](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/8143DA8FF5D3/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/67A56E0954>) |
| 10ec:816a | 17aa:3151 | Realtek Semic... | RTL8111xP UART #1                    | 7     | serial     | [5AC6CDC8FB](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A4001WUS/A25EA1475B0F/REBORNOS-ROLLING/5.16.9-ARCH1-1/X86_64/5AC6CDC8FB>) |
| 10ec:816b | 17aa:3151 | Realtek Semic... | RTL8111xP UART #2                    | 7     | serial     | [5AC6CDC8FB](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A4001WUS/A25EA1475B0F/REBORNOS-ROLLING/5.16.9-ARCH1-1/X86_64/5AC6CDC8FB>) |
| 8086:a363 | 17aa:3135 | Intel            | Cannon Lake PCH Active Management... | 7     | serial     | [C43EF85B97](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920x 10S1S07700/59BDC87984FB/ROSA-2016.1/5.4.40-GENERIC-1ROSA-X86_64/X86_64/C43EF85B97>) |
| 8086:a363 | 17aa:3136 | Intel            | Cannon Lake PCH Active Management... | 7     | serial     | [B3BA67D085](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10V8S06904/EAA513742A16/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/B3BA67D085>) |
| 8086:a13d | 103c:82c0 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     | serial     | [AC904E9BCB](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G3 Workstation/90A7B6AE2869/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/AC904E9BCB>) |
| 8086:06e3 | 17aa:3172 | Intel            | Comet Lake Keyboard and Text (KT)... | 3     | serial     | [EE32355409](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/EE29838C95B5/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/EE32355409>) |
| 10ec:816a | 17aa:3181 | Realtek Semic... | RTL8111xP UART #1                    | 2     | serial     | [56F9A83D77](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75n 11GW000BUS/8D95E87EDCE7/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/56F9A83D77>) |
| 8086:06e3 | 103c:8710 | Intel            | Comet Lake Keyboard and Text (KT)... | 2     | serial     | [B2A212246B](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G6 Desktop Mini PC/1AD35AB4DD59/CENTOS-7/5.4.118-1.EL7.ELREPO.X86_64/X86_64/B2A212246B>) |
| 8086:8c3d | 103c:2145 | Intel            | 8 Series/C220 Series Chipset Fami... | 2     | serial     | [9C26D1B3DD](<Mini Pc/Hewlett-Packard/t820/t820 Flexible Thin Client/94B86B15DFFF/UBUNTU-20.04/5.8.0-44-GENERIC/X86_64/9C26D1B3DD>) |
| 8086:9de3 | 17aa:314c | Intel            | Cannon Point-LP Keyboard and Text... | 2     | serial     | [0F66B49A44](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AD000YMX/8552A91D7647/ALPINE-3.13.0_ALPHA20200917/5.4.65-0-LTS/X86_64/0F66B49A44>) |
| 8086:a0e3 | 8086:3003 | Intel            | Tiger Lake-LP Active Management T... | 2     | serial     | [B23894B3E4](<Mini Pc/Intel Client Systems/NUC11/NUC11TNHv7/CD64B645A9A3/CLEAR-LINUX-OS-35250/5.15.1-1089.NATIVE/X86_64/B23894B3E4>) |
| 8086:a2bd | 17aa:310b | Intel            | 200 Series Chipset Family KT Redi... | 2     | serial     | [C7930B0D92](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M910q 10MUS3JC00/F360C35AE270/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/C7930B0D92>) |
| 8086:a2bd | 17aa:310c | Intel            | 200 Series Chipset Family KT Redi... | 2     | serial     | [B4770C2901](<Mini Pc/Lenovo/ThinkStation/ThinkStation P320 Tiny 30C1S1K902/BF32A8DAED23/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/B4770C2901>) |
| 8086:a363 | 8086:2088 | Intel            | Cannon Lake PCH Active Management... | 2     | serial     | [2AE39C4439](<Mini Pc/Intel Client Systems/NUC9/NUC9VXQNX/698519E45C28/UBUNTU-18.04/4.15.0-159-GENERIC/X86_64/2AE39C4439>) |
| 10ec:816a | 103c:83dd | Realtek Semic... | RTL8111xP UART #1                    | 1     | serial     | [9EC6F2E5FE](<Mini Pc/Hewlett-Packard/mt44/mt44 Mobile Thin Client/367A393AEEB1/KDE-NEON-20.04/5.11.0-40-GENERIC/X86_64/9EC6F2E5FE>) |
| 10ec:816a | 103c:8523 | Realtek Semic... | RTL8111xP UART #1                    | 1     |            | [BAB721D52E](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/FB37A4F0BA3A/SLACKWARE-14.2/5.4.62/X86_64/BAB721D52E>) |
| 10ec:816a | 17aa:30fd | Realtek Semic... | RTL8111xP UART #1                    | 1     | serial     | [5F6F9A1C6C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10M2S0DL00/BC868DED3F88/UBUNTU-21.04/5.11.0-17-GENERIC/X86_64/5F6F9A1C6C>) |
| 10ec:816b | 103c:83dd | Realtek Semic... | RTL8111xP UART #2                    | 1     | serial     | [9EC6F2E5FE](<Mini Pc/Hewlett-Packard/mt44/mt44 Mobile Thin Client/367A393AEEB1/KDE-NEON-20.04/5.11.0-40-GENERIC/X86_64/9EC6F2E5FE>) |
| 10ec:816b | 103c:8523 | Realtek Semic... | RTL8111xP UART #2                    | 1     |            | [BAB721D52E](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/FB37A4F0BA3A/SLACKWARE-14.2/5.4.62/X86_64/BAB721D52E>) |
| 10ec:816b | 10ec:8168 | Realtek Semic... | RTL8111xP UART #2                    | 1     |            | [5DD127A865](<Mini Pc/Daten Tecnologia/DC2/DC2C-U/DEAB1E021B3F/LINUXMINT-19/4.15.0-20-GENERIC/X86_64/5DD127A865>) |
| 10ec:816b | 17aa:30fd | Realtek Semic... | RTL8111xP UART #2                    | 1     | serial     | [5F6F9A1C6C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10M2S0DL00/BC868DED3F88/UBUNTU-21.04/5.11.0-17-GENERIC/X86_64/5F6F9A1C6C>) |
| 8086:06e3 | 103c:871a | Intel            | Comet Lake Keyboard and Text (KT)... | 1     | serial     | [F74885CE0C](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 400 G6 Desktop Mini PC/3847FD544AA9/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/F74885CE0C>) |
| 8086:1e3d | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 1     | serial     | [04D1FD85D9](<Mini Pc/CompuLab/Intense-PC/Intense-PC/62D6B61BDA7B/FEDORA-34/5.12.13-300.FC34.X86_64/X86_64/04D1FD85D9>) |
| 8086:9cbd | 8086:2058 | Intel            | Wildcat Point-LP KT Controller       | 1     | serial     | [4AB80B03C5](<Mini Pc/Intel/NUC5i5MYBE/NUC5i5MYBE H47797-203/60E7A3A0F8FF/ROSA-2014.1/4.4.1-NRJ-DESKTOP-1ROSA-X86_64/X86_64/4AB80B03C5>) |
| 8086:a0e3 | 8086:3013 | Intel            | Tiger Lake-LP Active Management T... | 1     | serial     | [66A02F462F](<Mini Pc/Intel/Board/Board/CDA9CB78A5E4/CLEAR-LINUX-OS-33960/5.9.8-1000.NATIVE/X86_64/66A02F462F>) |
| 8086:a13d | 1019:9bc6 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | serial     | [7101BAED7A](<Mini Pc/Daten Tecnologia/DC2/DC2B-U/5CEC86B8AF22/FEDORA-33/5.10.7-200.FC33.X86_64/X86_64/7101BAED7A>) |
| 8086:a2bd | 103c:829e | Intel            | 200 Series Chipset Family KT Redi... | 1     | serial     | [0028753E4D](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G3 DM/341483C13D08/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/0028753E4D>) |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9df9 | 8086:2074 | Intel            | Cannon Point-LP Thermal Controller   | 156   | intel_p... | [C79A71B9DB](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/C0AF1D599D12/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C79A71B9DB>) |
| 8086:02f9 | 8086:2081 | Intel            | Comet Lake Thermal Subsytem          | 89    | intel_p... | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:9d31 | 8086:2068 | Intel            | Sunrise Point-LP Thermal subsystem   | 79    | intel_p... | [7F8770AFC4](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/38F8ADEA821D/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/7F8770AFC4>) |
| 8086:5abc |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 41    | intel_l... | [5BEEF7A5B1](<Mini Pc/Intel/NUC6/NUC6CAYH/0C6F2967B76D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5BEEF7A5B1>) |
| 8086:5ac4 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 41    | intel_l... | [5BEEF7A5B1](<Mini Pc/Intel/NUC6/NUC6CAYH/0C6F2967B76D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5BEEF7A5B1>) |
| 8086:5ac6 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 41    | intel_l... | [5BEEF7A5B1](<Mini Pc/Intel/NUC6/NUC6CAYH/0C6F2967B76D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5BEEF7A5B1>) |
| 8086:a127 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 38    | intel_l... | [317E098A9E](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/A75259B85C6D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/317E098A9E>) |
| 8086:a131 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 38    | intel_p... | [317E098A9E](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/A75259B85C6D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/317E098A9E>) |
| 8086:a160 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 38    | intel_l... | [317E098A9E](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/A75259B85C6D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/317E098A9E>) |
| 8086:a161 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 38    | intel_l... | [317E098A9E](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/A75259B85C6D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/317E098A9E>) |
| 8086:a162 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 38    | intel_l... | [317E098A9E](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/A75259B85C6D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/317E098A9E>) |
| 8086:5aac | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 37    | intel_l... | [5BEEF7A5B1](<Mini Pc/Intel/NUC6/NUC6CAYH/0C6F2967B76D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5BEEF7A5B1>) |
| 8086:5ac2 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 37    | intel_l... | [5BEEF7A5B1](<Mini Pc/Intel/NUC6/NUC6CAYH/0C6F2967B76D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5BEEF7A5B1>) |
| 8086:5abc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 30    | intel_l... | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 8086:5abe | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 30    | intel_l... | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 8086:5ac0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 30    | intel_l... | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 8086:5aee | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 30    | intel_l... | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 8086:5a8c |           | Intel            | Atom/Celeron/Pentium Dynamic Plat... | 29    | process... | [D831E8693D](<Mini Pc/Beelink/AP/AP34/5D90ACC24076/LINUXMINT-20.2/5.4.0-81-GENERIC/X86_64/D831E8693D>) |
| 8086:a131 | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 29    | intel_p... | [86D379E9D5](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/54383D955906/UBUNTU-20.10/5.8.0-63-GENERIC/X86_64/86D379E9D5>) |
| 8086:5aac | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 28    | intel_l... | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 8086:5aae | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 28    | intel_l... | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 8086:5ab0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 28    | intel_l... | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 8086:5ab2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 28    | intel_l... | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 8086:5ab4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 28    | intel_l... | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 8086:5ab6 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 28    | intel_l... | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 8086:5ab8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 28    | intel_l... | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 8086:5aba | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 28    | intel_l... | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 1022:15e4 | 1022:15e4 | AMD              | Sensor Fusion Hub                    | 27    | amd_sfh    | [2F6DF3FFF6](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/86C8213ACE93/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2F6DF3FFF6>) |
| 8086:5ac2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 21    | intel_l... | [D831E8693D](<Mini Pc/Beelink/AP/AP34/5D90ACC24076/LINUXMINT-20.2/5.4.0-81-GENERIC/X86_64/D831E8693D>) |
| 8086:5ac4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 20    | intel_l... | [D831E8693D](<Mini Pc/Beelink/AP/AP34/5D90ACC24076/LINUXMINT-20.2/5.4.0-81-GENERIC/X86_64/D831E8693D>) |
| 8086:5ac6 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 20    | intel_l... | [D831E8693D](<Mini Pc/Beelink/AP/AP34/5D90ACC24076/LINUXMINT-20.2/5.4.0-81-GENERIC/X86_64/D831E8693D>) |
| 8086:9d27 | 8086:2063 | Intel            | Sunrise Point-LP Serial IO UART C... | 19    | intel_l... | [6879986BF2](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-505/29B4250B3145/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/6879986BF2>) |
| 8086:9d31 | 8086:2063 | Intel            | Sunrise Point-LP Thermal subsystem   | 19    | intel_p... | [6879986BF2](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-505/29B4250B3145/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/6879986BF2>) |
| 8086:22dc | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 18    | process... | [CDDC590270](<Mini Pc/BESSTAR Tech/Z83/Z83-F/833154D27E3C/ZORIN-16/5.13.0-30-GENERIC/X86_64/CDDC590270>) |
| 8086:9d31 | 8086:2070 | Intel            | Sunrise Point-LP Thermal subsystem   | 17    | intel_p... | [0261508BA5](<Mini Pc/Intel Client Systems/NUC7/NUC7i3DNHE/F93E47848AEB/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/0261508BA5>) |
| 8086:9d60 | 8086:2070 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 17    | intel_l... | [0261508BA5](<Mini Pc/Intel Client Systems/NUC7/NUC7i3DNHE/F93E47848AEB/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/0261508BA5>) |
| 8086:9d61 | 8086:2070 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 17    | intel_l... | [0261508BA5](<Mini Pc/Intel Client Systems/NUC7/NUC7i3DNHE/F93E47848AEB/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/0261508BA5>) |
| 8086:318c | 8086:318c | Intel            | Celeron/Pentium Silver Processor ... | 16    | process... | [B78185D870](<Mini Pc/Chuwi/HeroBox/HeroBox/0564D825BBAD/DEBIAN-11/5.15.0-0.BPO.3-AMD64/X86_64/B78185D870>) |
| 8086:318c | 1043:875e | Intel            | Celeron/Pentium Silver Processor ... | 13    | process... | [27BB88805D](<Mini Pc/ASUSTek Computer/PN/PN40/21E857FB29E9/CENTOS-7/3.10.0-1160.53.1.EL7.X86_64/X86_64/27BB88805D>) |
| 8086:31ac | 8086:31ac | Intel            | Celeron/Pentium Silver Processor ... | 12    | intel_l... | [B78185D870](<Mini Pc/Chuwi/HeroBox/HeroBox/0564D825BBAD/DEBIAN-11/5.15.0-0.BPO.3-AMD64/X86_64/B78185D870>) |
| 8086:31b2 | 8086:31b2 | Intel            | Celeron/Pentium Silver Processor ... | 12    | intel_l... | [B78185D870](<Mini Pc/Chuwi/HeroBox/HeroBox/0564D825BBAD/DEBIAN-11/5.15.0-0.BPO.3-AMD64/X86_64/B78185D870>) |
| 8086:31ac | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 10    | intel_lpss | [76B5667130](<Mini Pc/MeLE Computer/Quieter/Quieter2/73E8BF27E06D/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/76B5667130>) |
| 8086:31c2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 9     | intel_lpss | [78762D9561](<Mini Pc/Shenzhen Wangang Technology/AERO/AERO 2/503AFB8927C2/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/78762D9561>) |
| 8086:31c4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 9     | intel_lpss | [78762D9561](<Mini Pc/Shenzhen Wangang Technology/AERO/AERO 2/503AFB8927C2/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/78762D9561>) |
| 8086:31c6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 9     | intel_lpss | [78762D9561](<Mini Pc/Shenzhen Wangang Technology/AERO/AERO 2/503AFB8927C2/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/78762D9561>) |
| 8086:9d31 | 8086:7270 | Intel            | Sunrise Point-LP Thermal subsystem   | 9     | intel_p... | [E4BBE42B5A](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/33AEB9BBD609/DEBIAN-11/5.10.0-11-AMD64/X86_64/E4BBE42B5A>) |
| 8086:a2b1 | 103c:829a | Intel            | 200 Series PCH Thermal Subsystem     | 9     |            | [DFD0CB667C](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/0C45B1FBE800/DEBIAN-11/5.10.0-11-AMD64/X86_64/DFD0CB667C>) |
| 8086:31ae | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 8     | intel_lpss | [78762D9561](<Mini Pc/Shenzhen Wangang Technology/AERO/AERO 2/503AFB8927C2/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/78762D9561>) |
| 8086:31b0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 8     | intel_lpss | [78762D9561](<Mini Pc/Shenzhen Wangang Technology/AERO/AERO 2/503AFB8927C2/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/78762D9561>) |
| 8086:31b2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 8     | intel_lpss | [78762D9561](<Mini Pc/Shenzhen Wangang Technology/AERO/AERO 2/503AFB8927C2/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/78762D9561>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9da3 | 8086:2074 | Intel            | Cannon Point-LP SMBus Controller     | 156   | i2c_i801   | [C79A71B9DB](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/C0AF1D599D12/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C79A71B9DB>) |
| 8086:02a3 | 8086:2081 | Intel            | Comet Lake PCH-LP SMBus Host Cont... | 89    | i2c_i801   | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:9d23 | 8086:2068 | Intel            | Sunrise Point-LP SMBus               | 79    | i2c_i801   | [7F8770AFC4](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/38F8ADEA821D/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/7F8770AFC4>) |
| 8086:9ca2 | 8086:2057 | Intel            | Wildcat Point-LP SMBus Controller    | 54    | i2c_i801   | [CEA504B47D](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-503/F250AC8777D6/CENTOS-STREAM/4.18.0-348.2.1.EL8_5.X86_64/X86_64/CEA504B47D>) |
| 8086:1e22 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family SMBu... | 53    | i2c_i801   | [C3A014CA22](<Mini Pc/Apple/Macmini6/Macmini6,2/F5E3810853BC/CLEAR-LINUX-OS-35970/5.13.13-1070.NATIVE/X86_64/C3A014CA22>) |
| 8086:0f12 | 8086:0f12 | Intel            | Atom Processor E3800/CE2700 Serie... | 44    | i2c_i801   | [BF7C2C6D9B](<Mini Pc/NEXCOM/VTC/VTC1010/6EF054560413/DEBIAN-11/5.10.0-11-AMD64/X86_64/BF7C2C6D9B>) |
| 8086:5ad4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 42    | i2c_i801   | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 8086:2292 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 38    | i2c_i801   | [207E311CFC](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-102/8054EC01AC51/ASTRALINUXCE-2.12.44/5.10.0-1038.40-GENERIC/X86_64/207E311CFC>) |
| 8086:a123 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 38    | i2c_i801   | [317E098A9E](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/A75259B85C6D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/317E098A9E>) |
| 8086:1c22 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 37    | i2c_i801   | [A2BA361F2C](<Mini Pc/Apple/Macmini5/Macmini5,1/C29061AA8B1E/ZORIN-16/5.11.0-43-GENERIC/X86_64/A2BA361F2C>) |
| 8086:31d4 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 37    | i2c_i801   | [E02C6336D6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/3F30AC0E5D22/ARTIX-ROLLING/5.16.3-ARTIX1-1/X86_64/E02C6336D6>) |
| 8086:5ad4 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 37    | i2c_i801   | [5BEEF7A5B1](<Mini Pc/Intel/NUC6/NUC6CAYH/0C6F2967B76D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5BEEF7A5B1>) |
| 8086:9c22 | 8086:7270 | Intel            | 8 Series SMBus Controller            | 37    | i2c_i801   | [5550136FFD](<Mini Pc/Apple/Macmini7/Macmini7,1/65598A0C8936/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/5550136FFD>) |
| 8086:a123 | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 29    | i2c_i801   | [86D379E9D5](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/54383D955906/UBUNTU-20.10/5.8.0-63-GENERIC/X86_64/86D379E9D5>) |
| 10de:0aa2 | 10de:cb79 | Nvidia           | MCP79 SMBus                          | 26    | i2c_nfo... | [F114F6EA54](<Mini Pc/Apple/Macmini3/Macmini3,1/C67829525D2F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F114F6EA54>) |
| 1022:790b | 1043:87e7 | AMD              | FCH SMBus Controller                 | 25    | i2c_piix4  | [2F6DF3FFF6](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/86C8213ACE93/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2F6DF3FFF6>) |
| 8086:9d23 | 8086:2063 | Intel            | Sunrise Point-LP SMBus               | 19    | i2c_i801   | [6879986BF2](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-505/29B4250B3145/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/6879986BF2>) |
| 8086:27da | 8086:7270 | Intel            | NM10/ICH7 Family SMBus Controller    | 18    | i2c_i801   | [2075A95BFB](<Mini Pc/Apple/Macmini2/Macmini2,1/8B91B715078D/FEDORA-30/5.3.11-100.FC29.I686/I686/2075A95BFB>) |
| 8086:9d23 | 8086:2070 | Intel            | Sunrise Point-LP SMBus               | 17    | i2c_i801   | [0261508BA5](<Mini Pc/Intel Client Systems/NUC7/NUC7i3DNHE/F93E47848AEB/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/0261508BA5>) |
| 10de:0d79 | 10de:cb89 | Nvidia           | MCP89 SMBus                          | 16    |            | [D7F1687670](<Mini Pc/Apple/Macmini4/Macmini4,1/BCBD7A97BE65/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D7F1687670>) |
| 8086:2292 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 16    | i2c_i801   | [85A08428DF](<Mini Pc/AMI/Aptio/Aptio CRB/A758F1A02D67/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/85A08428DF>) |
| 8086:a0a3 | 8086:3004 | Intel            | Tiger Lake-LP SMBus Controller       | 15    | i2c_i801   | [CA53435B36](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/26774C86D363/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/CA53435B36>) |
| 8086:a323 | 17aa:312d | Intel            | Cannon Lake PCH SMBus Controller     | 15    | i2c_i801   | [88A943EC80](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T700BHBL/970C8BB93481/DEBIAN-11/5.10.0-11-AMD64/X86_64/88A943EC80>) |
| 1002:4385 | 103c:17e2 | AMD              | SBx00 SMBus Controller               | 14    | i2c_piix4  | [AE54C309D5](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/A9289FCA615E/DEBIAN-11/5.10.0-11-686-PAE/I686/AE54C309D5>) |
| 8086:31d4 | 1043:875e | Intel            | Celeron/Pentium Silver Processor ... | 13    | i2c_i801   | [27BB88805D](<Mini Pc/ASUSTek Computer/PN/PN40/21E857FB29E9/CENTOS-7/3.10.0-1160.53.1.EL7.X86_64/X86_64/27BB88805D>) |
| 8086:31d4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 13    | i2c_i801   | [76B5667130](<Mini Pc/MeLE Computer/Quieter/Quieter2/73E8BF27E06D/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/76B5667130>) |
| 8086:31d4 | 8086:31d4 | Intel            | Celeron/Pentium Silver Processor ... | 12    | i2c_i801   | [B78185D870](<Mini Pc/Chuwi/HeroBox/HeroBox/0564D825BBAD/DEBIAN-11/5.15.0-0.BPO.3-AMD64/X86_64/B78185D870>) |
| 8086:0f12 | 17aa:368d | Intel            | Atom Processor E3800/CE2700 Serie... | 11    | i2c_i801   | [03220F70D0](<Mini Pc/Lenovo/E50-00/E50-00 90BX003VUL/536000E6D70F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/03220F70D0>) |
| 1022:790b | 17aa:3130 | AMD              | FCH SMBus Controller                 | 10    | i2c_pii... | [CC222D78B9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VG001QRU/28BB5B3B7530/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/CC222D78B9>) |
| 1022:790b | 103c:872e | AMD              | FCH SMBus Controller                 | 9     | i2c_piix4  | [8366A84CDB](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/F373E702B28B/XUBUNTU-20.04/5.13.0-28-GENERIC/X86_64/8366A84CDB>) |
| 8086:9d23 | 8086:7270 | Intel            | Sunrise Point-LP SMBus               | 9     | i2c_i801   | [E4BBE42B5A](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/33AEB9BBD609/DEBIAN-11/5.10.0-11-AMD64/X86_64/E4BBE42B5A>) |
| 8086:a2a3 | 103c:829a | Intel            | 200 Series/Z370 Chipset Family SM... | 9     | i2c_i801   | [DFD0CB667C](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/0C45B1FBE800/DEBIAN-11/5.10.0-11-AMD64/X86_64/DFD0CB667C>) |
| 8086:9ca2 | 8086:7270 | Intel            | Wildcat Point-LP SMBus Controller    | 8     | i2c_i801   | [0A76AC3FB8](<Mini Pc/AZW/U/U55/BDB0C02F8F71/MANJARO/5.13.19-2-MANJARO/X86_64/0A76AC3FB8>) |
| 8086:a323 | 17aa:3135 | Intel            | Cannon Lake PCH SMBus Controller     | 8     | i2c_i801   | [C43EF85B97](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920x 10S1S07700/59BDC87984FB/ROSA-2016.1/5.4.40-GENERIC-1ROSA-X86_64/X86_64/C43EF85B97>) |
| 8086:a323 | 8086:7270 | Intel            | Cannon Lake PCH SMBus Controller     | 8     | i2c_i801   | [CA26CBBF22](<Mini Pc/Apple/Macmini8/Macmini8,1/F39A3C4B83EB/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/CA26CBBF22>) |
| 1022:790b | 103c:8158 | AMD              | FCH SMBus Controller                 | 7     | i2c_piix4  | [702F310A99](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/642F86533F2F/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/702F310A99>) |
| 1022:790b | 17aa:3151 | AMD              | FCH SMBus Controller                 | 7     | piix4_s... | [5AC6CDC8FB](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A4001WUS/A25EA1475B0F/REBORNOS-ROLLING/5.16.9-ARCH1-1/X86_64/5AC6CDC8FB>) |
| 8086:a123 | 19da:b333 | Intel            | 100 Series/C230 Series Chipset Fa... | 7     | i801_smbus | [7348D34142](<Mini Pc/ZOTAC/ZBOX-EN1070/ZBOX-EN1070-1060/0CBF4FF1BBBE/LINUXMINT-20.2/5.13.0-22-GENERIC/X86_64/7348D34142>) |
| 8086:a323 | 17aa:3136 | Intel            | Cannon Lake PCH SMBus Controller     | 7     | i2c_i801   | [B3BA67D085](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10V8S06904/EAA513742A16/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/B3BA67D085>) |
| 8086:0f12 |           | Intel            | Atom Processor E3800/CE2700 Serie... | 6     | i2c_i801   | [2882CF9963](<Mini Pc/NOBLEX/NB/NB1602/840F6A17AA98/DEBIAN-11/5.10.0-8-AMD64/X86_64/2882CF9963>) |
| 8086:0f12 | 17aa:30b5 | Intel            | Atom Processor E3800/CE2700 Serie... | 6     | i2c_i801   | [538597F50A](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M53 10DE001HUS/36D92E1E56E1/ENDLESS-3.7.8/5.3.0-28-GENERIC/X86_64/538597F50A>) |
| 8086:5ad4 | 19da:b325 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 6     | i2c_i801   | [23BDDBF63A](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/0FE806EB02BE/LINUXMINT-20.1/5.4.0-65-GENERIC/X86_64/23BDDBF63A>) |
| 8086:9ca2 | 8086:2058 | Intel            | Wildcat Point-LP SMBus Controller    | 6     | i2c_i801   | [ABF846A2C2](<Mini Pc/Intel/NUC5i3MYBE/NUC5i3MYBE H47781-202/BBE07E7A6081/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/ABF846A2C2>) |
| 8086:9da3 | 17aa:314d | Intel            | Cannon Point-LP SMBus Controller     | 6     | i2c_i801   | [BD2F6222E5](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AD002DGE/D203F33318BC/MANJARO-21.1.0/5.10.53-1-MANJARO/X86_64/BD2F6222E5>) |
| 8086:a323 | 8086:2089 | Intel            | Cannon Lake PCH SMBus Controller     | 6     | i2c_i801   | [EFF399191D](<Mini Pc/Intel Client Systems/NUC9/NUC9i9QNX/519180459546/UBUNTU-20.04/5.13.0-25-GENERIC/X86_64/EFF399191D>) |
| 1022:790b | 103c:8267 | AMD              | FCH SMBus Controller                 | 5     | i2c_piix4  | [3C277DC3C1](<Mini Pc/Hewlett-Packard/t530/t530 Thin Client/982DFBB69A90/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3C277DC3C1>) |
| 8086:2292 | 17aa:30dd | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | i2c_i801   | [BD46C4BAC3](<Mini Pc/Lenovo/S200z/S200z 10HA000FRU/0E3D6DC0E64D/UBUNTU-20.04/5.4.0-99-GENERIC/X86_64/BD46C4BAC3>) |
| 8086:2292 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | i2c_i801   | [175DDA01F6](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/92EB5D9C4CEF/LUBUNTU-20.04/5.4.0-91-GENERIC/X86_64/175DDA01F6>) |
| 8086:4da3 | 1043:8813 | Intel            | Jasper Lake SMBus                    | 5     | i2c_i801   | [B416BA575D](<Mini Pc/ASUSTek Computer/PN/PN41/20388AD561BB/ZORIN-16/5.13.0-30-GENERIC/X86_64/B416BA575D>) |
| 8086:a2a3 | 103c:82a5 | Intel            | 200 Series/Z370 Chipset Family SM... | 5     | i2c_i801   | [C47D9B3AE0](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 400 G3 DM/342D63741B55/ELEMENTARY-6.1/5.13.0-28-GENERIC/X86_64/C47D9B3AE0>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9dc8 | 8086:2074 | Intel            | Cannon Point-LP High Definition A... | 153   | snd_hda... | [C79A71B9DB](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/C0AF1D599D12/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C79A71B9DB>) |
| 8086:02c8 | 8086:2081 | Intel            | Comet Lake PCH-LP cAVS               | 89    | snd_hda... | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:9d71 | 8086:2068 | Intel            | Sunrise Point-LP HD Audio            | 76    | snd_hda... | [7F8770AFC4](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/38F8ADEA821D/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/7F8770AFC4>) |
| 8086:9ca0 | 8086:2057 | Intel            | Wildcat Point-LP High Definition ... | 54    | snd_hda... | [CEA504B47D](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-503/F250AC8777D6/CENTOS-STREAM/4.18.0-348.2.1.EL8_5.X86_64/X86_64/CEA504B47D>) |
| 8086:160c | 8086:2057 | Intel            | Broadwell-U Audio Controller         | 53    | snd_hda... | [CEA504B47D](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-503/F250AC8777D6/CENTOS-STREAM/4.18.0-348.2.1.EL8_5.X86_64/X86_64/CEA504B47D>) |
| 8086:1e20 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family High... | 53    | snd_hda... | [C3A014CA22](<Mini Pc/Apple/Macmini6/Macmini6,2/F5E3810853BC/CLEAR-LINUX-OS-35970/5.13.13-1070.NATIVE/X86_64/C3A014CA22>) |
| 8086:2284 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 38    | snd_hda... | [207E311CFC](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-102/8054EC01AC51/ASTRALINUXCE-2.12.44/5.10.0-1038.40-GENERIC/X86_64/207E311CFC>) |
| 8086:a171 | 8086:2073 | Intel            | CM238 HD Audio Controller            | 38    | snd_hda... | [317E098A9E](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/A75259B85C6D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/317E098A9E>) |
| 8086:0a0c | 106b:0141 | Intel            | Haswell-ULT HD Audio Controller      | 37    | snd_hda... | [5550136FFD](<Mini Pc/Apple/Macmini7/Macmini7,1/65598A0C8936/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/5550136FFD>) |
| 8086:1c20 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 37    | snd_hda... | [A2BA361F2C](<Mini Pc/Apple/Macmini5/Macmini5,1/C29061AA8B1E/ZORIN-16/5.11.0-43-GENERIC/X86_64/A2BA361F2C>) |
| 8086:3198 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 37    | snd_hda... | [E02C6336D6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/3F30AC0E5D22/ARTIX-ROLLING/5.16.3-ARTIX1-1/X86_64/E02C6336D6>) |
| 8086:9c20 | 8086:7270 | Intel            | 8 Series HD Audio Controller         | 37    | snd_hda... | [5550136FFD](<Mini Pc/Apple/Macmini7/Macmini7,1/65598A0C8936/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/5550136FFD>) |
| 8086:5a98 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 35    | snd_hda... | [5BEEF7A5B1](<Mini Pc/Intel/NUC6/NUC6CAYH/0C6F2967B76D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5BEEF7A5B1>) |
| 1002:ab08 | 8086:2073 | AMD              | Polaris 22 HDMI Audio                | 34    | snd_hda... | [317E098A9E](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/A75259B85C6D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/317E098A9E>) |
| 1002:1637 | 1002:1637 | AMD              | Renoir Radeon High Definition Aud... | 31    | snd_hda... | [8A85AEAF5A](<Mini Pc/AZW/GTR/GTR/BB648F57E2C2/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/8A85AEAF5A>) |
| 8086:0f04 | 8086:0f04 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 29    | snd_hda... | [8B6B6116B4](<Mini Pc/AMI/Aptio/Aptio CRB/B56EB544FA4F/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/8B6B6116B4>) |
| 8086:a170 | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 29    | snd_hda... | [86D379E9D5](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/54383D955906/UBUNTU-20.10/5.8.0-63-GENERIC/X86_64/86D379E9D5>) |
| 10de:0ac0 | 10de:cb79 | Nvidia           | MCP79 High Definition Audio          | 26    | snd_hda... | [F114F6EA54](<Mini Pc/Apple/Macmini3/Macmini3,1/C67829525D2F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F114F6EA54>) |
| 1002:15de | 1002:15de | AMD              | Raven/Raven2/Fenghuang HDMI/DP Au... | 20    | snd_hda... | [CC222D78B9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VG001QRU/28BB5B3B7530/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/CC222D78B9>) |
| 1022:15e3 | 1043:87bc | AMD              | Family 17h/19h HD Audio Controller   | 20    | snd_hda... | [2F6DF3FFF6](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/86C8213ACE93/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2F6DF3FFF6>) |
| 8086:9d70 | 8086:2063 | Intel            | Sunrise Point-LP HD Audio            | 18    | snd_hda... | [6879986BF2](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-505/29B4250B3145/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/6879986BF2>) |
| 8086:9d71 | 8086:2070 | Intel            | Sunrise Point-LP HD Audio            | 17    | snd_hda... | [0261508BA5](<Mini Pc/Intel Client Systems/NUC7/NUC7i3DNHE/F93E47848AEB/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/0261508BA5>) |
| 10de:0d94 | 10de:cb89 | Nvidia           | MCP89 High Definition Audio          | 16    | snd_hda... | [D7F1687670](<Mini Pc/Apple/Macmini4/Macmini4,1/BCBD7A97BE65/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D7F1687670>) |
| 8086:2284 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 16    | snd_hda... | [85A08428DF](<Mini Pc/AMI/Aptio/Aptio CRB/A758F1A02D67/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/85A08428DF>) |
| 8086:27d8 | 8384:7680 | Intel            | NM10/ICH7 Family High Definition ... | 16    | snd_hda... | [2075A95BFB](<Mini Pc/Apple/Macmini2/Macmini2,1/8B91B715078D/FEDORA-30/5.3.11-100.FC29.I686/I686/2075A95BFB>) |
| 8086:5a98 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 16    | snd_hda... | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 8086:a0c8 | 8086:3004 | Intel            | Tiger Lake-LP Smart Sound Technol... | 15    | snd_hda... | [CA53435B36](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/26774C86D363/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/CA53435B36>) |
| 8086:a348 | 17aa:312d | Intel            | Cannon Lake PCH cAVS                 | 15    | snd_hda... | [88A943EC80](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T700BHBL/970C8BB93481/DEBIAN-11/5.10.0-11-AMD64/X86_64/88A943EC80>) |
| 1002:1314 | 103c:17e2 | AMD              | Wrestler HDMI Audio                  | 14    | snd_hda... | [AE54C309D5](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/A9289FCA615E/DEBIAN-11/5.10.0-11-686-PAE/I686/AE54C309D5>) |
| 1002:4383 | 103c:17e2 | AMD              | SBx00 Azalia (Intel HDA)             | 14    | snd_hda... | [AE54C309D5](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/A9289FCA615E/DEBIAN-11/5.10.0-11-686-PAE/I686/AE54C309D5>) |
| 1002:aa90 | 0000:aa90 | AMD              | Turks HDMI Audio [Radeon HD 6500/... | 14    | snd_hda... | [FEE3E2FEF0](<Mini Pc/Apple/Macmini5/Macmini5,2/D5A757D5CEB8/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/FEE3E2FEF0>) |
| 8086:0f04 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 14    | snd_hda... | [C197C7FD6E](<Mini Pc/AMI/Aptio/Aptio CRB/75857A8874A3/LINUXMINT-19.3/5.4.0-100-GENERIC/X86_64/C197C7FD6E>) |
| 8086:5a98 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 14    | snd_hda... | [25CBD96C5F](<Mini Pc/GHIA/Endless/Endless/335E2515D22A/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/25CBD96C5F>) |
| 8086:3198 | 1043:871d | Intel            | Celeron/Pentium Silver Processor ... | 13    | snd_hda... | [27BB88805D](<Mini Pc/ASUSTek Computer/PN/PN40/21E857FB29E9/CENTOS-7/3.10.0-1160.53.1.EL7.X86_64/X86_64/27BB88805D>) |
| 8086:3198 | 10ec:119e | Intel            | Celeron/Pentium Silver Processor ... | 12    | snd_hda... | [B78185D870](<Mini Pc/Chuwi/HeroBox/HeroBox/0564D825BBAD/DEBIAN-11/5.15.0-0.BPO.3-AMD64/X86_64/B78185D870>) |
| 8086:0f04 | 17aa:368d | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 11    | snd_hda... | [03220F70D0](<Mini Pc/Lenovo/E50-00/E50-00 90BX003VUL/536000E6D70F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/03220F70D0>) |
| 1022:15e3 | 17aa:3130 | AMD              | Family 17h/19h HD Audio Controller   | 10    | snd_hda... | [CC222D78B9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VG001QRU/28BB5B3B7530/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/CC222D78B9>) |
| 1002:1637 | 103c:872e | AMD              | Renoir Radeon High Definition Aud... | 9     | snd_hda... | [8366A84CDB](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/F373E702B28B/XUBUNTU-20.04/5.13.0-28-GENERIC/X86_64/8366A84CDB>) |
| 1022:15e3 | 103c:872e | AMD              | Family 17h/19h HD Audio Controller   | 9     | snd_hda... | [8366A84CDB](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/F373E702B28B/XUBUNTU-20.04/5.13.0-28-GENERIC/X86_64/8366A84CDB>) |
| 8086:160c | 111e:10ec | Intel            | Broadwell-U Audio Controller         | 9     | snd_hda... | [0A76AC3FB8](<Mini Pc/AZW/U/U55/BDB0C02F8F71/MANJARO/5.13.19-2-MANJARO/X86_64/0A76AC3FB8>) |
| 8086:a2f0 | 103c:829a | Intel            | 200 Series PCH HD Audio              | 9     | snd_hda... | [DFD0CB667C](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/0C45B1FBE800/DEBIAN-11/5.10.0-11-AMD64/X86_64/DFD0CB667C>) |
| 106b:1803 | 106b:1884 | Apple            | Audio Device                         | 8     |            | [CA26CBBF22](<Mini Pc/Apple/Macmini8/Macmini8,1/F39A3C4B83EB/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/CA26CBBF22>) |
| 8086:3198 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 8     | snd_hda... | [78762D9561](<Mini Pc/Shenzhen Wangang Technology/AERO/AERO 2/503AFB8927C2/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/78762D9561>) |
| 8086:5a98 | 10ec:1128 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 8     | snd_hda... | [D831E8693D](<Mini Pc/Beelink/AP/AP34/5D90ACC24076/LINUXMINT-20.2/5.4.0-81-GENERIC/X86_64/D831E8693D>) |
| 8086:9d71 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 8     | snd_hda... | [E4BBE42B5A](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/33AEB9BBD609/DEBIAN-11/5.10.0-11-AMD64/X86_64/E4BBE42B5A>) |
| 8086:a348 | 17aa:3135 | Intel            | Cannon Lake PCH cAVS                 | 8     | snd_hda... | [C43EF85B97](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920x 10S1S07700/59BDC87984FB/ROSA-2016.1/5.4.40-GENERIC-1ROSA-X86_64/X86_64/C43EF85B97>) |
| 8086:a348 | 8086:7270 | Intel            | Cannon Lake PCH cAVS                 | 8     | snd_hda... | [CA26CBBF22](<Mini Pc/Apple/Macmini8/Macmini8,1/F39A3C4B83EB/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/CA26CBBF22>) |
| 1002:9840 | 103c:8158 | AMD              | Kabini HDMI/DP Audio                 | 7     | snd_hda... | [702F310A99](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/642F86533F2F/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/702F310A99>) |
| 1022:157a | 103c:8158 | AMD              | Family 15h (Models 60h-6fh) Audio... | 7     | snd_hda... | [702F310A99](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/642F86533F2F/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/702F310A99>) |
| 1022:15e3 | 1043:8820 | AMD              | Family 17h/19h HD Audio Controller   | 7     | snd_hda... | [F9A8D0F268](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50-E1/DB79BB22B588/POP!_OS-21.10/5.16.2-051602-GENERIC/X86_64/F9A8D0F268>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9dd3 | 8086:2074 | Intel            | Cannon Point-LP SATA Controller [... | 151   | ahci       | [C79A71B9DB](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/C0AF1D599D12/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C79A71B9DB>) |
| 8086:02d3 | 8086:2081 | Intel            | Comet Lake SATA AHCI Controller      | 84    | ahci       | [AFA3998157](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/190D68FD5AEE/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/AFA3998157>) |
| 8086:9d03 | 8086:2068 | Intel            | Sunrise Point-LP SATA Controller ... | 77    | ahci       | [7F8770AFC4](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/38F8ADEA821D/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/7F8770AFC4>) |
| 8086:1e03 | 8086:7270 | Intel            | 7 Series Chipset Family 6-port SA... | 53    | ahci       | [C3A014CA22](<Mini Pc/Apple/Macmini6/Macmini6,2/F5E3810853BC/CLEAR-LINUX-OS-35970/5.13.13-1070.NATIVE/X86_64/C3A014CA22>) |
| 8086:9c83 | 8086:2057 | Intel            | Wildcat Point-LP SATA Controller ... | 49    | ahci       | [87A77E0618](<Mini Pc/Intel/NUC5i7RYB/NUC5i7RYB H73774-101/BE69D0456A98/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/87A77E0618>) |
| 8086:5ae3 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 43    | ahci       | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 8086:0f23 | 8086:0f23 | Intel            | Atom Processor E3800 Series SATA ... | 39    | ahci       | [C197C7FD6E](<Mini Pc/AMI/Aptio/Aptio CRB/75857A8874A3/LINUXMINT-19.3/5.4.0-100-GENERIC/X86_64/C197C7FD6E>) |
| 8086:22a3 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 38    | ahci       | [207E311CFC](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-102/8054EC01AC51/ASTRALINUXCE-2.12.44/5.10.0-1038.40-GENERIC/X86_64/207E311CFC>) |
| 8086:31e3 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 37    | ahci       | [E02C6336D6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/3F30AC0E5D22/ARTIX-ROLLING/5.16.3-ARTIX1-1/X86_64/E02C6336D6>) |
| 8086:5ae3 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 37    | ahci       | [5BEEF7A5B1](<Mini Pc/Intel/NUC6/NUC6CAYH/0C6F2967B76D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5BEEF7A5B1>) |
| 8086:9c03 | 8086:7270 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 35    | ahci       | [5550136FFD](<Mini Pc/Apple/Macmini7/Macmini7,1/65598A0C8936/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/5550136FFD>) |
| 8086:1c03 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 33    | ahci       | [A2BA361F2C](<Mini Pc/Apple/Macmini5/Macmini5,1/C29061AA8B1E/ZORIN-16/5.11.0-43-GENERIC/X86_64/A2BA361F2C>) |
| 1022:7901 | 1043:87e7 | AMD              | FCH SATA Controller [AHCI mode]      | 25    | ahci       | [2F6DF3FFF6](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/86C8213ACE93/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2F6DF3FFF6>) |
| 10de:0ab9 | 10de:cb79 | Nvidia           | MCP79 AHCI Controller                | 22    | ahci       | [F114F6EA54](<Mini Pc/Apple/Macmini3/Macmini3,1/C67829525D2F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F114F6EA54>) |
| 8086:9d03 | 8086:2063 | Intel            | Sunrise Point-LP SATA Controller ... | 19    | ahci       | [6879986BF2](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-505/29B4250B3145/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/6879986BF2>) |
| 10de:0d88 | 106b:cb89 | Nvidia           | MCP89 SATA Controller (AHCI mode)    | 16    | ahci       | [D7F1687670](<Mini Pc/Apple/Macmini4/Macmini4,1/BCBD7A97BE65/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D7F1687670>) |
| 8086:22a3 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 16    | ahci       | [85A08428DF](<Mini Pc/AMI/Aptio/Aptio CRB/A758F1A02D67/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/85A08428DF>) |
| 8086:9d03 | 8086:2070 | Intel            | Sunrise Point-LP SATA Controller ... | 16    | ahci       | [0261508BA5](<Mini Pc/Intel Client Systems/NUC7/NUC7i3DNHE/F93E47848AEB/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/0261508BA5>) |
| 8086:a352 | 17aa:312d | Intel            | Cannon Lake PCH SATA AHCI Controller | 15    | ahci       | [88A943EC80](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T700BHBL/970C8BB93481/DEBIAN-11/5.10.0-11-AMD64/X86_64/88A943EC80>) |
| 8086:a0d3 | 8086:3004 | Intel            | Tiger Lake-LP SATA Controller [AH... | 14    | ahci       | [CA53435B36](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/26774C86D363/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/CA53435B36>) |
| 8086:31e3 | 1043:875e | Intel            | Celeron/Pentium Silver Processor ... | 13    | ahci       | [27BB88805D](<Mini Pc/ASUSTek Computer/PN/PN40/21E857FB29E9/CENTOS-7/3.10.0-1160.53.1.EL7.X86_64/X86_64/27BB88805D>) |
| 8086:31e3 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 13    | ahci       | [76B5667130](<Mini Pc/MeLE Computer/Quieter/Quieter2/73E8BF27E06D/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/76B5667130>) |
| 1002:4390 | 103c:17e2 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 12    | ahci       | [AE54C309D5](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/A9289FCA615E/DEBIAN-11/5.10.0-11-686-PAE/I686/AE54C309D5>) |
| 8086:31e3 | 8086:31e3 | Intel            | Celeron/Pentium Silver Processor ... | 12    | ahci       | [B78185D870](<Mini Pc/Chuwi/HeroBox/HeroBox/0564D825BBAD/DEBIAN-11/5.15.0-0.BPO.3-AMD64/X86_64/B78185D870>) |
| 8086:a103 | 8086:2064 | Intel            | HM170/QM170 Chipset SATA Controll... | 12    | ahci       | [E7AEECFF98](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/FCA7A82BFDE5/DEBIAN-11/5.10.0-8-AMD64/X86_64/E7AEECFF98>) |
| 8086:0f23 | 17aa:368d | Intel            | Atom Processor E3800 Series SATA ... | 11    | ahci       | [03220F70D0](<Mini Pc/Lenovo/E50-00/E50-00 90BX003VUL/536000E6D70F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/03220F70D0>) |
| 8086:a103 | 8086:2073 | Intel            | HM170/QM170 Chipset SATA Controll... | 10    | ahci       | [093D240F55](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/22525E8969DB/OPENSUSE-TUMBLEWEED-20220125/5.16.1-1-DEFAULT/X86_64/093D240F55>) |
| 1022:43eb | 103c:872e | AMD              | 500 Series Chipset SATA Controller   | 9     | ahci       | [8366A84CDB](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/F373E702B28B/XUBUNTU-20.04/5.13.0-28-GENERIC/X86_64/8366A84CDB>) |
| 1022:7901 | 17aa:3130 | AMD              | FCH SATA Controller [AHCI mode]      | 9     | ahci       | [CC222D78B9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VG001QRU/28BB5B3B7530/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/CC222D78B9>) |
| 8086:9d03 | 8086:7270 | Intel            | Sunrise Point-LP SATA Controller ... | 9     | ahci       | [E4BBE42B5A](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/33AEB9BBD609/DEBIAN-11/5.10.0-11-AMD64/X86_64/E4BBE42B5A>) |
| 8086:a282 | 103c:829a | Intel            | 200 Series PCH SATA controller [A... | 8     | ahci       | [DFD0CB667C](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/0C45B1FBE800/DEBIAN-11/5.10.0-11-AMD64/X86_64/DFD0CB667C>) |
| 8086:a352 | 17aa:3135 | Intel            | Cannon Lake PCH SATA AHCI Controller | 8     | ahci       | [C43EF85B97](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920x 10S1S07700/59BDC87984FB/ROSA-2016.1/5.4.40-GENERIC-1ROSA-X86_64/X86_64/C43EF85B97>) |
| 1022:7901 | 103c:8158 | AMD              | FCH SATA Controller [AHCI mode]      | 7     | ahci       | [702F310A99](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/642F86533F2F/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/702F310A99>) |
| 1022:7901 | 17aa:3151 | AMD              | FCH SATA Controller [AHCI mode]      | 7     | ahci       | [5AC6CDC8FB](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A4001WUS/A25EA1475B0F/REBORNOS-ROLLING/5.16.9-ARCH1-1/X86_64/5AC6CDC8FB>) |
| 8086:9c83 | 8086:7270 | Intel            | Wildcat Point-LP SATA Controller ... | 7     | ahci       | [0A76AC3FB8](<Mini Pc/AZW/U/U55/BDB0C02F8F71/MANJARO/5.13.19-2-MANJARO/X86_64/0A76AC3FB8>) |
| 8086:a102 | 19da:b333 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 7     | ahci       | [7348D34142](<Mini Pc/ZOTAC/ZBOX-EN1070/ZBOX-EN1070-1060/0CBF4FF1BBBE/LINUXMINT-20.2/5.13.0-22-GENERIC/X86_64/7348D34142>) |
| 1b4b:9215 | 1b4b:9215 | Marvell Techn... | 88SE9215 PCIe 2.0 x1 4-port SATA ... | 6     | ahci       | [C2474EED31](<Mini Pc/AMI/Aptio/Aptio CRB/C5490E733A08/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/C2474EED31>) |
| 8086:0f23 |           | Intel            | Atom Processor E3800 Series SATA ... | 6     | ahci       | [2882CF9963](<Mini Pc/NOBLEX/NB/NB1602/840F6A17AA98/DEBIAN-11/5.10.0-8-AMD64/X86_64/2882CF9963>) |
| 8086:0f23 | 17aa:30b5 | Intel            | Atom Processor E3800 Series SATA ... | 6     | ahci       | [538597F50A](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M53 10DE001HUS/36D92E1E56E1/ENDLESS-3.7.8/5.3.0-28-GENERIC/X86_64/538597F50A>) |
| 8086:5ae3 | 19da:b325 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 6     | ahci       | [23BDDBF63A](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/0FE806EB02BE/LINUXMINT-20.1/5.4.0-65-GENERIC/X86_64/23BDDBF63A>) |
| 8086:9c83 | 8086:2058 | Intel            | Wildcat Point-LP SATA Controller ... | 6     | ahci       | [ABF846A2C2](<Mini Pc/Intel/NUC5i3MYBE/NUC5i3MYBE H47781-202/BBE07E7A6081/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/ABF846A2C2>) |
| 8086:a352 | 17aa:3136 | Intel            | Cannon Lake PCH SATA AHCI Controller | 6     | ahci       | [B3BA67D085](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10V8S06904/EAA513742A16/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/B3BA67D085>) |
| 8086:a353 | 8086:2089 | Intel            | Cannon Lake Mobile PCH SATA AHCI ... | 6     | ahci       | [EFF399191D](<Mini Pc/Intel Client Systems/NUC9/NUC9i9QNX/519180459546/UBUNTU-20.04/5.13.0-25-GENERIC/X86_64/EFF399191D>) |
| 1022:7901 | 103c:8267 | AMD              | FCH SATA Controller [AHCI mode]      | 5     | ahci       | [3C277DC3C1](<Mini Pc/Hewlett-Packard/t530/t530 Thin Client/982DFBB69A90/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3C277DC3C1>) |
| 8086:22a3 | 17aa:30dd | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | ahci       | [BD46C4BAC3](<Mini Pc/Lenovo/S200z/S200z 10HA000FRU/0E3D6DC0E64D/UBUNTU-20.04/5.4.0-99-GENERIC/X86_64/BD46C4BAC3>) |
| 8086:22a3 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | ahci       | [175DDA01F6](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/92EB5D9C4CEF/LUBUNTU-20.04/5.4.0-91-GENERIC/X86_64/175DDA01F6>) |
| 8086:27c5 | 8086:7270 | Intel            | 82801GBM/GHM (ICH7-M Family) SATA... | 5     | ahci       | [2A96949FD0](<Mini Pc/Apple/Macmini2/Macmini2,1/BAC9E87D2647/DEBIAN-10/4.19.0-17-686-PAE/I686/2A96949FD0>) |
| 8086:a282 | 103c:82a5 | Intel            | 200 Series PCH SATA controller [A... | 5     | ahci       | [C47D9B3AE0](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 400 G3 DM/342D63741B55/ELEMENTARY-6.1/5.13.0-28-GENERIC/X86_64/C47D9B3AE0>) |
| 8086:a282 | 17aa:3111 | Intel            | 200 Series PCH SATA controller [A... | 5     | ahci       | [B9D4EFB68C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MR000XUK/3928CECFA48F/POP!_OS-21.10/5.15.15-76051515-GENERIC/X86_64/B9D4EFB68C>) |
| 1022:43eb | 103c:8836 | AMD              | 500 Series Chipset SATA Controller   | 4     | ahci       | [DA34E7C710](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/DD273ADCD4AF/XUBUNTU-20.04/5.8.0-53-GENERIC/X86_64/DA34E7C710>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:27df | 8086:7270 | Intel            | 82801G (ICH7 Family) IDE Controller  | 17    | pata_acpi  | [2075A95BFB](<Mini Pc/Apple/Macmini2/Macmini2,1/8B91B715078D/FEDORA-30/5.3.11-100.FC29.I686/I686/2075A95BFB>) |
| 8086:27c4 | 8086:7270 | Intel            | 82801GBM/GHM (ICH7-M Family) SATA... | 12    | pata_acpi  | [2075A95BFB](<Mini Pc/Apple/Macmini2/Macmini2,1/8B91B715078D/FEDORA-30/5.3.11-100.FC29.I686/I686/2075A95BFB>) |
| 1106:9001 | 1106:9001 | VIA Technologies | VX900 Series Serial-ATA Controller   | 8     | pata_vi... | [15268C0CCC](<Mini Pc/Hewlett-Packard/t510/t510 Thin Client/21A13F83F33E/XUBUNTU-20.04/5.8.0-53-GENERIC/X86_64/15268C0CCC>) |
| 10de:0ab5 | 10de:cb79 | Nvidia           | MCP79 SATA Controller                | 5     | ahci, p... | [D65F9A48FD](<Mini Pc/Apple/Macmini3/Macmini3,1/B1D24220B517/DEVUAN-4/5.10.0-8-AMD64/X86_64/D65F9A48FD>) |
| 8086:1c01 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 4     | ata_pii... | [8DC468B83D](<Mini Pc/Apple/Macmini5/Macmini5,1/DF6A36CD4774/OPENMANDRIVA-4.50/5.12.4-DESKTOP-1OMV4050/X86_64/8DC468B83D>) |
| 1002:439c | 19da:a191 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 3     | pata_at... | [C0CE2CCABE](<Mini Pc/ZOTAC/ZBOXNANO-AD/ZBOXNANO-AD10/E4426F81F461/UBUNTU-20.04/5.11.0-44-GENERIC/X86_64/C0CE2CCABE>) |
| 1002:439c | 19da:a233 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 3     | pata_at... | [BE96F10577](<Mini Pc/ZOTAC/ZBOX-AD/ZBOX-AD04/0EEEABB8A5DF/UBUNTU-20.04/5.11.0-44-GENERIC/X86_64/BE96F10577>) |
| 8086:27c0 | 8086:544b | Intel            | NM10/ICH7 Family SATA Controller ... | 3     | ata_pii... | [9DC27FC5BE](<Mini Pc/Intel/D425KT/D425KT AAE93083-401/10EE8CFFD4E7/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/9DC27FC5BE>) |
| 1022:780c | 103c:8103 | AMD              | FCH IDE Controller                   | 2     | pata_at... | [60924B9FD9](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client TC/D0CDB04E03EF/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/60924B9FD9>) |
| 1022:780c | 19da:a261 | AMD              | FCH IDE Controller                   | 2     | pata_at... | [8C3CA64606](<Mini Pc/ZOTAC/ZBOXNXS-AD/ZBOXNXS-AD13/5DDED330808E/LINUXMINT-20.1/5.4.0-67-GENERIC/X86_64/8C3CA64606>) |
| 1002:439c | 19da:a183 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 1     | pata_at... | [037A3E45C7](<Mini Pc/ZOTAC/ZBOX-AD/ZBOX-AD02/9D6F0E41A45F/ROSA-2014.1/4.1.15-NRJ-DESKTOP-1ROSA-I586/I686/037A3E45C7>) |
| 1022:780c | 19da:b218 | AMD              | FCH IDE Controller                   | 1     | pata_at... | [EB76FF1C3F](<Mini Pc/ZOTAC/ZBOXNANO-AQ/ZBOXNANO-AQ02/652E2251D263/ARCO-ROLLING/5.11.21-HARDENED1-2-HARDENED/X86_64/EB76FF1C3F>) |
| 8086:0f21 | 17aa:368d | Intel            | Atom Processor E3800 Series SATA ... | 1     | ata_pii... | [E3D598C5CB](<Mini Pc/Lenovo/H50-00/H50-00 90C1000PRS/BB394062E9F8/ROSA-2014.1/4.1.38-NRJ-DESKTOP-1ROSA-X86_64/X86_64/E3D598C5CB>) |
| 8086:0f21 | 8086:0f21 | Intel            | Atom Processor E3800 Series SATA ... | 1     | ata_pii... | [BF7C2C6D9B](<Mini Pc/NEXCOM/VTC/VTC1010/6EF054560413/DEBIAN-11/5.10.0-11-AMD64/X86_64/BF7C2C6D9B>) |
| 8086:24cb | 8086:1977 | Intel            | 82801DB (ICH4) IDE Controller        | 1     | ata_piix   | [4A3E3CD4EE](<Mini Pc/Radiant Systems/P/P845/6CDD298F6645/ANTIX-17.4.1/4.9.160-ANTIX.2-486-SMP/I686/4A3E3CD4EE>) |
| 8086:27c0 | 19da:a140 | Intel            | NM10/ICH7 Family SATA Controller ... | 1     | pata_acpi  | [90F8E7B807](<Mini Pc/ZOTAC/ZBOXSD-ID12/ZBOXSD-ID12-ID13/035C74FA7C3D/UBUNTU-20.04/5.4.0-37-GENERIC/X86_64/90F8E7B807>) |
| 8086:27c0 | 19da:a218 | Intel            | NM10/ICH7 Family SATA Controller ... | 1     | ata_pii... | [E907BA80AE](<Mini Pc/ZOTAC/ZBOX-ID/ZBOX-ID80/E1C6E46AEEE7/ROSA-2014.1/4.1.38-NRJ-DESKTOP-2ROSA-X86_64/X86_64/E907BA80AE>) |
| 8086:27c0 | 8086:7270 | Intel            | NM10/ICH7 Family SATA Controller ... | 1     | pata_acpi  | [6B9414B09F](<Mini Pc/Intel/CedarTrail/CedarTrail Platform/009433D25421/UBUNTU-20.04/5.4.0-47-GENERIC/X86_64/6B9414B09F>) |
| 8086:27c4 | 8086:27c4 | Intel            | 82801GBM/GHM (ICH7-M Family) SATA... | 1     | pata_acpi  | [10DB69DD6C](<Mini Pc/Kontron/SMX/SMX945/327FC59121CA/UBUNTU-18.04/4.15.0-88-GENERIC/I686/10DB69DD6C>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 158   | nvme       | [2068EFCD75](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/0E0D4411E185/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/2068EFCD75>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 40    | nvme       | [BC052DAF77](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/8638844D4716/GENTOO-2.8/5.16.2-GENTOO/X86_64/BC052DAF77>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT SSD Controller     | 19    | nvme       | [F72047DC6D](<Mini Pc/Intel Client Systems/NUC8/NUC8i7BEH/CB26D11F0398/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/F72047DC6D>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 16    | nvme       | [8A85AEAF5A](<Mini Pc/AZW/GTR/GTR/BB648F57E2C2/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/8A85AEAF5A>) |
| 15b7:5006 | 15b7:5006 | Sandisk          | WD Black SN750 / PC SN730 NVMe SSD   | 15    | nvme       | [EE32355409](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/EE29838C95B5/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/EE32355409>) |
| 2646:2263 | 2646:2263 | Kingston Tech... | A2000 NVMe SSD                       | 14    | nvme       | [CC222D78B9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VG001QRU/28BB5B3B7530/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/CC222D78B9>) |
| 8086:f1a5 | 8086:390a | Intel            | SSD 600P Series                      | 14    | nvme       | [FA29A65816](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/EE29838C95B5/FEDORA-35/5.15.16-200.FC35.X86_64/X86_64/FA29A65816>) |
| 144d:a80a | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 12    | nvme       | [1158CBFEAA](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/894923AF1BC3/DEBIAN-11/5.10.0-10-AMD64/X86_64/1158CBFEAA>) |
| c0a9:2263 | c0a9:2263 | Micron/Crucia... | P1 NVMe PCIe SSD                     | 12    | nvme       | [4B198A6B46](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/B2C179CD3985/KUBUNTU-21.10/5.13.0-27-GENERIC/X86_64/4B198A6B46>) |
| 8086:f1a8 | 8086:390d | Intel            | SSD 660P Series                      | 11    | nvme       | [C79A71B9DB](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/C0AF1D599D12/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C79A71B9DB>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 10    | nvme       | [86D379E9D5](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/54383D955906/UBUNTU-20.10/5.8.0-63-GENERIC/X86_64/86D379E9D5>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980              | 9     | nvme       | [D99CA518F9](<Mini Pc/Lenovo/IdeaCentre/IdeaCentre Mini 5 01IMH05 90Q60000UT/70492AEAC407/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D99CA518F9>) |
| 15b7:5002 | 15b7:5002 | Sandisk          | WD Black 2018/SN750 / PC SN720 NV... | 9     | nvme       | [3371572AA9](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNH/746A210D754A/ELEMENTARY-6.1/5.11.0-41-GENERIC/X86_64/3371572AA9>) |
| 15b7:5009 | 15b7:5009 | Sandisk          | WD Blue SN550 NVMe SSD               | 9     | nvme       | [B416BA575D](<Mini Pc/ASUSTek Computer/PN/PN41/20388AD561BB/ZORIN-16/5.13.0-30-GENERIC/X86_64/B416BA575D>) |
| 106b:2005 | 106b:1800 | Apple            | ANS2 NVMe Controller                 | 8     | nvme       | [CA26CBBF22](<Mini Pc/Apple/Macmini8/Macmini8,1/F39A3C4B83EB/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/CA26CBBF22>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 8     | nvme       | [5AC6CDC8FB](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A4001WUS/A25EA1475B0F/REBORNOS-ROLLING/5.16.9-ARCH1-1/X86_64/5AC6CDC8FB>) |
| 1179:0116 | 1179:0001 | Toshiba Ameri... | Toshiba America Info Non-Volatile... | 7     | nvme       | [DFD0CB667C](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/0C45B1FBE800/DEBIAN-11/5.10.0-11-AMD64/X86_64/DFD0CB667C>) |
| 8086:f1a6 | 8086:390b | Intel            | SSD Pro 7600p/760p/E 6100p Series    | 6     | nvme       | [29FA794275](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/48B13EA7ABE2/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/29FA794275>) |
| 126f:2262 | 126f:2262 | Silicon Motion   | SM2262/SM2262EN SSD Controller       | 5     | nvme       | [849A97D8C3](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/C1EBC5D5D8E2/DEBIAN-11/5.10.0-11-AMD64/X86_64/849A97D8C3>) |
| 15b7:5011 | 15b7:5011 | Sandisk          | WD PC SN810 / Black SN850 NVMe SSD   | 5     | nvme       | [9EB75AB42F](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/4076B509F693/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/9EB75AB42F>) |
| 1987:5008 | 1987:5008 | Phison Electr... | NVMe Storage Controller              | 5     | nvme       | [161445E905](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/DC511A2DF716/DEBIAN-TESTING/5.10.0-5-AMD64/X86_64/161445E905>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013 E13 NVMe Controller           | 5     | nvme       | [6536E752DD](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/D6FDC6C0C087/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/6536E752DD>) |
| 1c5c:1627 | 1c5c:1627 | SK Hynix         | Non-Volatile memory controller       | 5     | nvme       | [F7CA8D84CA](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A4000GGE/BA13EDD10A17/FEDORA-35/5.15.6-200.FC35.X86_64/X86_64/F7CA8D84CA>) |
| c0a9:540a | c0a9:540a | Micron/Crucia... | P2 NVMe PCIe SSD                     | 5     | nvme       | [83A99CBA20](<Mini Pc/Intel Client Systems/NUC10/NUC10i5FNH/369CEF883DD9/LINUXMINT-20.2/5.4.0-92-GENERIC/X86_64/83A99CBA20>) |
| 1179:011a | 1179:0001 | Toshiba Ameri... | XG6 NVMe SSD Controller              | 4     | nvme       | [5205C41BC5](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M625q 10TF002MGE/79CE2ACCD525/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/5205C41BC5>) |
| 1987:5016 | 1987:5016 | Phison Electr... | E16 PCIe4 NVMe Controller            | 4     | nvme       | [507FBFC464](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/DA58DDCDF0D1/UBUNTU-21.04/5.11.0-22-GENERIC/X86_64/507FBFC464>) |
| 1c5c:1327 | 1c5c:0000 | SK Hynix         | BC501 NVMe Solid State Drive         | 4     | nvme       | [CF5DEA43E1](<Mini Pc/Hewlett-Packard/260/260 G3 DM/D334B500C95E/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/CF5DEA43E1>) |
| 1e0f:0001 | 1e0f:0001 | KIOXIA           | Non-Volatile memory controller       | 4     | nvme       | [B3BA67D085](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10V8S06904/EAA513742A16/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/B3BA67D085>) |
| 2646:500e | 2646:500e | Kingston Tech... | SNVS2000G [NV1 NVMe PCIe SSD 2TB]    | 4     | nvme       | [2B0F2F8139](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/73C1EB1E8CDA/FEDORA-35/5.16.5-200.FC35.X86_64/X86_64/2B0F2F8139>) |
| 15b7:5005 | 15b7:5005 | Sandisk          | PC SN520 NVMe SSD                    | 3     | nvme       | [3376399C24](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AH000UUS/FA83C5554701/UBUNTU-18.04/5.3.0-40-GENERIC/X86_64/3376399C24>) |
| 15b7:5019 | 15b7:5019 | Sandisk          | Non-Volatile memory controller       | 3     | nvme       | [2B7802EDC0](<Mini Pc/Intel/NUC7i7BNB/NUC7i7BNB J31145-304/CD867DDD9D35/POP!_OS-20.04/5.13.0-7614-GENERIC/X86_64/2B7802EDC0>) |
| 1c5c:1639 | 1c5c:1639 | SK Hynix         | Non-Volatile memory controller       | 3     | nvme       | [B41631FF89](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CFCTO1WW/646F3FD65343/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/B41631FF89>) |
| 1c5c:174a | 1c5c:174a | SK Hynix         | Gold P31 SSD                         | 3     | nvme       | [1FFFD953F4](<Mini Pc/Fanless Mini PC/PCG35/PCG35 GLK/5E7BD773CC7D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/1FFFD953F4>) |
| 2646:5008 | 2646:5008 | Kingston Tech... | U-SNS8154P3 NVMe SSD                 | 3     | nvme       | [053EA52CD6](<Mini Pc/Intel/NUC7/NUC7i3BNH/06E49E0DB8AE/UBUNTU-21.04/5.14.8-051408-GENERIC/X86_64/053EA52CD6>) |
| 2646:500f | 2646:500f | Kingston Tech... | Technology Company Non-Volatile m... | 3     | nvme       | [39D215E49D](<Mini Pc/AZW/GTR/GTR/0370FAAF0441/FEDORA-35/5.16.10-200.FC35.X86_64/X86_64/39D215E49D>) |
| 8086:2522 | 8086:3806 | Intel            | NVMe Optane Memory Series            | 3     | nvme       | [13353E2037](<Mini Pc/Intel/NUC7i7BNB/NUC7i7BNB J31145-303/BA0AE0126DA2/CLEAR-LINUX-OS-33780/5.8.12-989.NATIVE/X86_64/13353E2037>) |
| c0a9:5412 | c0a9:0100 | Micron/Crucia... | Non-Volatile memory controller       | 3     | nvme       | [6D7C53D047](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/D1621C065C38/UBUNTU-21.10/5.13.0-22-GENERIC/X86_64/6D7C53D047>) |
| 1022:b000 | 144d:a801 | AMD              | RAID Bottom Device                   | 2     | nvme       | [F2418E15EC](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/EAFA3EC7B472/FEDORA-33/5.9.8-200.FC33.X86_64/X86_64/F2418E15EC>) |
| 10ec:5760 | 5760:10ec | Realtek Semic... | Realtek Non-Volatile memory contr... | 2     | nvme       | [596EEA9169](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/455817D08D63/UBUNTU-18.04/4.15.0-151-GENERIC/X86_64/596EEA9169>) |
| 10ec:5762 | 10ec:5762 | Realtek Semic... | RTS5763DL NVMe SSD Controller        | 2     | nvme       | [847A813A2C](<Mini Pc/ASUSTek Computer/PN60/PN60-R/1051BA1EB3B1/MANJARO/5.10.15-1-MANJARO/X86_64/847A813A2C>) |
| 10ec:5763 | 10ec:5763 | Realtek Semic... | Realtek Non-Volatile memory contr... | 2     | nvme       | [A03DE89D54](<Mini Pc/Intel Client Systems/NUC7/NUC7i3DNHE/1E04700AAC6F/UBUNTU-20.04/5.8.0-44-GENERIC/X86_64/A03DE89D54>) |
| 15b7:5003 | 15b7:5003 | Sandisk          | WD Blue SN500 / PC SN520 NVMe SSD    | 2     | nvme       | [4055D7B3FC](<Mini Pc/Hewlett-Packard/260/260 G3 DM/C1AE1F7EFF79/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/4055D7B3FC>) |
| 1987:5007 | 1987:5007 | Phison Electr... | E7 NVMe Controller                   | 2     | nvme       | [F9C39F6628](<Mini Pc/Intel/NUC7/NUC7i7BNH/24B90FE9CEBE/ARCH/5.3.7-ARCH1-1-ARCH/X86_64/F9C39F6628>) |
| 1b85:6018 | 1b85:6018 | OCZ Technolog... | RD400/400A SSD                       | 2     | nvme       | [CC099348C2](<Mini Pc/ZOTAC/ZBOX-EN1070/ZBOX-EN1070-1060,EN1070K-1060K/F834407E83E3/DEBIAN-11/5.11.22-3-PVE/X86_64/CC099348C2>) |
| 1c5c:1339 | 1c5c:0000 | SK Hynix         | BC511                                | 2     | nvme       | [DFCA28CC5F](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/22E8EE3E19B2/MANJARO-21.1.0/5.12.16-1-MANJARO/X86_64/DFCA28CC5F>) |
| 1d79:2263 | 1d79:2263 |                  | Non-Volatile memory controller       | 2     | nvme       | [2BEFA53304](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNK/01AA0F125F1B/FEDORA-35/5.9.16-200.FC33.X86_64/X86_64/2BEFA53304>) |
| 2646:2262 | 2646:2262 | Kingston Tech... | KC2000 NVMe SSD                      | 2     | nvme       | [744AB63B06](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-406/A5968EFD623F/FEDORA-34/5.12.14-300.FC34.X86_64/X86_64/744AB63B06>) |
| 8086:faf0 | 8086:390e | Intel            | Non-Volatile memory controller       | 2     | nvme       | [391F80AE12](<Mini Pc/Intel Client Systems/NUC10/NUC10i5FNH/A820E1C60A88/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/391F80AE12>) |
| c0a9:5403 | c0a9:2100 | Micron/Crucia... | NVMe Controller                      | 2     | nvme       | [0E1DD5F9DA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/81AD067954DA/CLEAR-LINUX-OS-35550/5.15.12-1113.NATIVE/X86_64/0E1DD5F9DA>) |
| 1022:b000 | 15b7:5006 | AMD              | RAID Bottom Device                   | 1     | nvme       | [0E48C94F83](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 805 G6 Desktop Mini PC/FB1F518D1327/CENTOS-8/4.18.0-240.22.1.EL8_3.X86_64/X86_64/0E48C94F83>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2822 | 103c:82c0 | Intel            | SATA Controller [RAID mode]          | 4     | ahci       | [AC904E9BCB](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G3 Workstation/90A7B6AE2869/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/AC904E9BCB>) |
| 8086:282a | 8086:2074 | Intel            | 82801 Mobile SATA Controller [RAI... | 4     | ahci       | [0837C1616A](<Mini Pc/System76/Meerkat/Meerkat/7558D65AB1B2/UBUNTU-20.04/5.15.8-76051508-GENERIC/X86_64/0837C1616A>) |
| 8086:282a | 8086:2081 | Intel            | 82801 Mobile SATA Controller [RAI... | 3     | ahci       | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:2822 | 103c:8458 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [87E6E38B4A](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G4 Workstation/79AC29E69A55/PEPPERMINT-9/4.15.0-135-GENERIC/X86_64/87E6E38B4A>) |
| 1022:43bd | 103c:872c | AMD              | FCH RAID Controller                  | 1     |            | [0E48C94F83](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 805 G6 Desktop Mini PC/FB1F518D1327/CENTOS-8/4.18.0-240.22.1.EL8_3.X86_64/X86_64/0E48C94F83>) |
| 8086:2822 | 103c:829a | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [E0FB7EA560](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/FF31240EBC03/UBUNTU-18.04/5.0.0-29-GENERIC/X86_64/E0FB7EA560>) |
| 8086:2822 | 103c:829e | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [0028753E4D](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G3 DM/341483C13D08/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/0028753E4D>) |
| 8086:282a | 19da:b248 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [D521E3AD79](<Mini Pc/ZOTAC/ZBOX-EN/ZBOX-EN760/C87907D81660/LINUXMINT-19.3/5.4.0-42-GENERIC/X86_64/D521E3AD79>) |
| 8086:282a | 8086:2068 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [1C3A187EC6](<Mini Pc/Intel/NUC7/NUC7i3BNK/41760ECEF797/KUBUNTU-21.04/5.11.0-41-LOWLATENCY/X86_64/1C3A187EC6>) |
| 8086:282a | 8086:2079 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [985AA77681](<Mini Pc/Intel Client Systems/NUC8/NUC8i5INH/B39881C57542/CLEAR-LINUX-OS-34440/5.10.19-1032.NATIVE/X86_64/985AA77681>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1911 | 8086:2074 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 156   |            | [C79A71B9DB](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/C0AF1D599D12/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C79A71B9DB>) |
| 8086:1911 | 8086:2081 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 88    |            | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:15e8 | 8086:2081 | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 86    | thunder... | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:1911 | 8086:2068 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 79    |            | [7F8770AFC4](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/38F8ADEA821D/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/7F8770AFC4>) |
| 8086:1911 | 8086:2073 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 38    |            | [317E098A9E](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/A75259B85C6D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/317E098A9E>) |
| 8086:1513 | 2222:1111 | Intel            | CV82524 Thunderbolt Controller [L... | 37    | thunder... | [A2BA361F2C](<Mini Pc/Apple/Macmini5/Macmini5,1/C29061AA8B1E/ZORIN-16/5.11.0-43-GENERIC/X86_64/A2BA361F2C>) |
| 8086:156c |           | Intel            | DSL5520 Thunderbolt 2 NHI [Falcon... | 33    | thunder... | [5550136FFD](<Mini Pc/Apple/Macmini7/Macmini7,1/65598A0C8936/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/5550136FFD>) |
| 8086:1911 | 8086:2064 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 29    |            | [86D379E9D5](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/54383D955906/UBUNTU-20.10/5.8.0-63-GENERIC/X86_64/86D379E9D5>) |
| 8086:1911 | 8086:2070 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 17    |            | [0261508BA5](<Mini Pc/Intel Client Systems/NUC7/NUC7i3DNHE/F93E47848AEB/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/0261508BA5>) |
| 8086:1911 | 17aa:312d | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 15    |            | [88A943EC80](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T700BHBL/970C8BB93481/DEBIAN-11/5.10.0-11-AMD64/X86_64/88A943EC80>) |
| 8086:9a11 | 8086:3004 | Intel            | GNA Scoring Accelerator module       | 15    |            | [CA53435B36](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/26774C86D363/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/CA53435B36>) |
| 8086:3190 | 1043:875e | Intel            | Celeron/Pentium Silver Processor ... | 13    |            | [27BB88805D](<Mini Pc/ASUSTek Computer/PN/PN40/21E857FB29E9/CENTOS-7/3.10.0-1160.53.1.EL7.X86_64/X86_64/27BB88805D>) |
| 8086:1911 | 8086:2015 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 11    |            | [E4BBE42B5A](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/33AEB9BBD609/DEBIAN-11/5.10.0-11-AMD64/X86_64/E4BBE42B5A>) |
| 8086:15d9 | 8086:2074 | Intel            | JHL6340 Thunderbolt 3 NHI (C step... | 8     | thunder... | [F72047DC6D](<Mini Pc/Intel Client Systems/NUC8/NUC8i7BEH/CB26D11F0398/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/F72047DC6D>) |
| 8086:15eb | 8086:0000 | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 8     | thunder... | [CA26CBBF22](<Mini Pc/Apple/Macmini8/Macmini8,1/F39A3C4B83EB/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/CA26CBBF22>) |
| 8086:15eb | 8086:2088 | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 8     | thunder... | [EFF399191D](<Mini Pc/Intel Client Systems/NUC9/NUC9i9QNX/519180459546/UBUNTU-20.04/5.13.0-25-GENERIC/X86_64/EFF399191D>) |
| 8086:1911 | 17aa:3135 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 8     |            | [C43EF85B97](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920x 10S1S07700/59BDC87984FB/ROSA-2016.1/5.4.40-GENERIC-1ROSA-X86_64/X86_64/C43EF85B97>) |
| 8086:1911 | 17aa:3136 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 7     |            | [B3BA67D085](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10V8S06904/EAA513742A16/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/B3BA67D085>) |
| 8086:1911 | 17aa:314d | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 6     |            | [BD2F6222E5](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AD002DGE/D203F33318BC/MANJARO-21.1.0/5.10.53-1-MANJARO/X86_64/BD2F6222E5>) |
| 8086:1911 | 8086:2089 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 6     |            | [EFF399191D](<Mini Pc/Intel Client Systems/NUC9/NUC9i9QNX/519180459546/UBUNTU-20.04/5.13.0-25-GENERIC/X86_64/EFF399191D>) |
| 8086:1911 | 19da:b333 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 5     |            | [CC099348C2](<Mini Pc/ZOTAC/ZBOX-EN1070/ZBOX-EN1070-1060,EN1070K-1060K/F834407E83E3/DEBIAN-11/5.11.22-3-PVE/X86_64/CC099348C2>) |
| 8086:4e11 | 1043:8813 | Intel            | System peripheral                    | 5     |            | [B416BA575D](<Mini Pc/ASUSTek Computer/PN/PN41/20388AD561BB/ZORIN-16/5.13.0-30-GENERIC/X86_64/B416BA575D>) |
| 8086:1575 | 2222:1111 | Intel            | DSL6340 Thunderbolt 3 NHI [Alpine... | 4     | thunder... | [E7AEECFF98](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/FCA7A82BFDE5/DEBIAN-11/5.10.0-8-AMD64/X86_64/E7AEECFF98>) |
| 8086:15de | 2222:1111 | Intel            | JHL6340 Thunderbolt 3 Controller ... | 4     | thunder... | [78B5820785](<Mini Pc/Intel/NUC7i3BNB/NUC7i3BNB J22859-303/3A9D186752F0/UBUNTU-18.04/4.15.0-72-GENERIC/X86_64/78B5820785>) |
| 8086:1911 | 17aa:316e | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 4     |            | [0224398912](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DUS4SQ00/DA9A8078DC3D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/0224398912>) |
| 8086:3190 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 4     |            | [94025849E2](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/96716D11F503/MANJARO/5.13.12-1-MANJARO/X86_64/94025849E2>) |
| 8086:1911 | 17aa:3172 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 3     |            | [EE32355409](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/EE29838C95B5/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/EE32355409>) |
| 8086:1911 | 8086:7270 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 3     |            | [934F2F075C](<Mini Pc/AZW/SEi/SEi/2957B295DEBC/LINUXMINT-20/5.4.0-90-GENERIC/X86_64/934F2F075C>) |
| 8086:9a11 | 8086:2090 | Intel            | GNA Scoring Accelerator module       | 3     |            | [1158CBFEAA](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/894923AF1BC3/DEBIAN-11/5.10.0-10-AMD64/X86_64/1158CBFEAA>) |
| 8086:9a11 | 8086:3002 | Intel            | GNA Scoring Accelerator module       | 3     |            | [23FCE48DF7](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKi7/5BE9775954D9/FEDORA-35/5.16.5-200.FC35.X86_64/X86_64/23FCE48DF7>) |
| 8086:15d2 | 8086:2073 | Intel            | JHL6540 Thunderbolt 3 NHI (C step... | 2     | thunder... | [36AD5EF96A](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/03515C2F23EB/GENTOO-2.8/5.15.4-GENTOO.8I7HVK/X86_64/36AD5EF96A>) |
| 8086:1911 | 1019:9bc6 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [7101BAED7A](<Mini Pc/Daten Tecnologia/DC2/DC2B-U/5CEC86B8AF22/FEDORA-33/5.10.7-200.FC33.X86_64/X86_64/7101BAED7A>) |
| 8086:1911 | 17aa:314c | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [0F66B49A44](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AD000YMX/8552A91D7647/ALPINE-3.13.0_ALPHA20200917/5.4.65-0-LTS/X86_64/0F66B49A44>) |
| 8086:1911 | 19da:b411 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [CF60BF6309](<Mini Pc/ZOTAC/ZBOX-EN7208/ZBOX-EN72080V-EN72070V-EN52060V-EN51660T/21ECD795A8CC/UBUNTU-20.04/5.8.0-45-GENERIC/X86_64/CF60BF6309>) |
| 8086:1911 | 19da:b440 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [57676DE735](<Mini Pc/ZOTAC/ZBOX-ECM7307/ZBOX-ECM73070C-53060C/C458DE01446F/ARCO-ROLLING/5.13.12-ARCH1-1/X86_64/57676DE735>) |
| 8086:1911 | 8086:2079 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [45B14891D4](<Mini Pc/Intel Client Systems/NUC8/NUC8i5INH/CFC9656AFB5C/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/45B14891D4>) |
| 8086:1911 | 8086:2088 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [2AE39C4439](<Mini Pc/Intel Client Systems/NUC9/NUC9VXQNX/698519E45C28/UBUNTU-18.04/4.15.0-159-GENERIC/X86_64/2AE39C4439>) |
| 8086:1f15 | 8086:0000 | Intel            | Atom processor C2000 SMBus 2.0       | 2     | i2c_ismt   | [C1D37659C1](<Mini Pc/Supermicro/A1/A1SAi/F097711C2215/GENTOO-2.6/5.4.86-GENTOO/X86_64/C1D37659C1>) |
| 8086:3190 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 2     |            | [E46F325CBA](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/EEB3D49D8109/ENDLESS-3.8.3/5.4.0-19-GENERIC/X86_64/E46F325CBA>) |
| 8086:3190 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 2     |            | [4C465E5A03](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/6236CFFD80EB/GENTOO-2.6/5.3.0-GENTOO/X86_64/4C465E5A03>) |
| 8086:5a11 | 8086:2075 | Intel            | System peripheral                    | 2     |            | [D9AC661777](<Mini Pc/Intel Client Systems/NUC8/NUC8i3CYS/F84856907C67/KALI-2021.3/5.10.0-KALI9-AMD64/X86_64/D9AC661777>) |
| 8086:9a11 | 8086:3003 | Intel            | GNA Scoring Accelerator module       | 2     |            | [B23894B3E4](<Mini Pc/Intel Client Systems/NUC11/NUC11TNHv7/CD64B645A9A3/CLEAR-LINUX-OS-35250/5.15.1-1089.NATIVE/X86_64/B23894B3E4>) |
| 1ac1:089a | 1ac1:089a | Global Unichip   | Coral Edge TPU                       | 1     |            | [DC32208597](<Mini Pc/Intel Client Systems/NUC6/NUC6i7KYK/DE8B7D607E9B/FEDORA-35/5.15.11-200.FC35.X86_64/X86_64/DC32208597>) |
| 8086:1577 | 2222:1111 | Intel            | DSL6540 Thunderbolt 3 NHI [Alpine... | 1     | thunder... | [40AEEA62F1](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/F577DFADD508/UBUNTU-20.04/5.4.0-47-GENERIC/X86_64/40AEEA62F1>) |
| 8086:15d9 | 8086:0000 | Intel            | JHL6340 Thunderbolt 3 NHI (C step... | 1     | thunder... | [42A1AEA9C7](<Mini Pc/Intel Client Systems/NUC7/NUC7i3BNH/3A8E888F8DF9/UBUNTU-18.04/4.15.0-72-GENERIC/X86_64/42A1AEA9C7>) |
| 8086:1911 | 17aa:3144 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [8D0F1F5E39](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M630e 10YM001SRU/7F8C8151CE1E/UBUNTU-19.10/5.3.0-51-GENERIC/X86_64/8D0F1F5E39>) |
| 8086:1911 | 17aa:3307 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [D99CA518F9](<Mini Pc/Lenovo/IdeaCentre/IdeaCentre Mini 5 01IMH05 90Q60000UT/70492AEAC407/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D99CA518F9>) |
| 8086:3584 | 8086:1977 | Intel            | 82852/82855 GM/GME/PM/GMV Process... | 1     |            | [4A3E3CD4EE](<Mini Pc/Radiant Systems/P/P845/6CDD298F6645/ANTIX-17.4.1/4.9.160-ANTIX.2-486-SMP/I686/4A3E3CD4EE>) |
| 8086:3585 | 8086:1977 | Intel            | 82852/82855 GM/GME/PM/GMV Process... | 1     |            | [4A3E3CD4EE](<Mini Pc/Radiant Systems/P/P845/6CDD298F6645/ANTIX-17.4.1/4.9.160-ANTIX.2-486-SMP/I686/4A3E3CD4EE>) |
| 8086:9a11 | 19da:b448 | Intel            | GNA Scoring Accelerator module       | 1     |            | [28EAF0B05C](<Mini Pc/ZOTAC/ZBOX-MI-CI625/ZBOX-MI-CI625-645-665NANO/0EBA1A9CB7E4/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/28EAF0B05C>) |

### Tv card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 109e:036e |           | Brooktree        | Bt878 Video Capture                  | 1     | bttv       | [10DB69DD6C](<Mini Pc/Kontron/SMX/SMX945/327FC59121CA/UBUNTU-18.04/4.15.0-88-GENERIC/I686/10DB69DD6C>) |

### Unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:5aa2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | intel_i... | [224597688F](<Mini Pc/AMI/Aptio/Aptio CRB/0421BC2A6F1E/UBUNTU-20.04/5.4.0-90-GENERIC/X86_64/224597688F>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9ded | 8086:2074 | Intel            | Cannon Point-LP USB 3.1 xHCI Cont... | 156   | xhci_hcd   | [C79A71B9DB](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/C0AF1D599D12/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C79A71B9DB>) |
| 8086:02ed | 8086:2081 | Intel            | Comet Lake PCH-LP USB 3.1 xHCI Ho... | 89    | xhci_hcd   | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:15e9 | 8086:2081 | Intel            | JHL7540 Thunderbolt 3 USB Control... | 86    | xhci_hcd   | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 8086:9d2f | 8086:2068 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 79    | xhci_hcd   | [7F8770AFC4](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/38F8ADEA821D/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/7F8770AFC4>) |
| 8086:0f35 | 8086:0f35 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 74    | xhci_hcd   | [BF7C2C6D9B](<Mini Pc/NEXCOM/VTC/VTC1010/6EF054560413/DEBIAN-11/5.10.0-11-AMD64/X86_64/BF7C2C6D9B>) |
| 8086:1e26 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family USB ... | 53    | ehci_pci   | [C3A014CA22](<Mini Pc/Apple/Macmini6/Macmini6,2/F5E3810853BC/CLEAR-LINUX-OS-35970/5.13.13-1070.NATIVE/X86_64/C3A014CA22>) |
| 8086:1e2d | 8086:7270 | Intel            | 7 Series/C216 Chipset Family USB ... | 53    | ehci_pci   | [C3A014CA22](<Mini Pc/Apple/Macmini6/Macmini6,2/F5E3810853BC/CLEAR-LINUX-OS-35970/5.13.13-1070.NATIVE/X86_64/C3A014CA22>) |
| 8086:1e31 | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 53    | xhci_hcd   | [C3A014CA22](<Mini Pc/Apple/Macmini6/Macmini6,2/F5E3810853BC/CLEAR-LINUX-OS-35970/5.13.13-1070.NATIVE/X86_64/C3A014CA22>) |
| 8086:9cb1 | 8086:2057 | Intel            | Wildcat Point-LP USB xHCI Controller | 53    | xhci_hcd   | [CEA504B47D](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-503/F250AC8777D6/CENTOS-STREAM/4.18.0-348.2.1.EL8_5.X86_64/X86_64/CEA504B47D>) |
| 8086:9ca6 | 8086:2057 | Intel            | Wildcat Point-LP USB EHCI Controller | 51    | ehci_pci   | [CEA504B47D](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-503/F250AC8777D6/CENTOS-STREAM/4.18.0-348.2.1.EL8_5.X86_64/X86_64/CEA504B47D>) |
| 8086:15db | 8086:2074 | Intel            | JHL6340 Thunderbolt 3 USB 3.1 Con... | 46    | xhci_hcd   | [F72047DC6D](<Mini Pc/Intel Client Systems/NUC8/NUC8i7BEH/CB26D11F0398/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/F72047DC6D>) |
| 8086:5aa8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 43    | xhci_hcd   | [1C6C1F4C45](<Mini Pc/EXTRA Computer/Pokini/Pokini F2/22D503355AD1/DEBIAN-11/5.14.0-0.BPO.2-AMD64/X86_64/1C6C1F4C45>) |
| 1b21:2142 | 8086:2073 | ASMedia Techn... | ASM2142 USB 3.1 Host Controller      | 38    | xhci_hcd   | [317E098A9E](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/A75259B85C6D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/317E098A9E>) |
| 8086:a12f | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 38    | xhci_hcd   | [317E098A9E](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/A75259B85C6D/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/317E098A9E>) |
| 8086:1c26 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 37    | ehci_pci   | [A2BA361F2C](<Mini Pc/Apple/Macmini5/Macmini5,1/C29061AA8B1E/ZORIN-16/5.11.0-43-GENERIC/X86_64/A2BA361F2C>) |
| 8086:1c27 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 37    | uhci_hcd   | [A2BA361F2C](<Mini Pc/Apple/Macmini5/Macmini5,1/C29061AA8B1E/ZORIN-16/5.11.0-43-GENERIC/X86_64/A2BA361F2C>) |
| 8086:1c2c | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 37    | uhci_hcd   | [A2BA361F2C](<Mini Pc/Apple/Macmini5/Macmini5,1/C29061AA8B1E/ZORIN-16/5.11.0-43-GENERIC/X86_64/A2BA361F2C>) |
| 8086:1c2d | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 37    | ehci_pci   | [A2BA361F2C](<Mini Pc/Apple/Macmini5/Macmini5,1/C29061AA8B1E/ZORIN-16/5.11.0-43-GENERIC/X86_64/A2BA361F2C>) |
| 8086:31a8 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 37    | xhci_hcd   | [E02C6336D6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/3F30AC0E5D22/ARTIX-ROLLING/5.16.3-ARTIX1-1/X86_64/E02C6336D6>) |
| 8086:5aa8 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 37    | xhci_hcd   | [5BEEF7A5B1](<Mini Pc/Intel/NUC6/NUC6CAYH/0C6F2967B76D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5BEEF7A5B1>) |
| 8086:9c31 | 8086:7270 | Intel            | 8 Series USB xHCI HC                 | 37    | xhci_hcd   | [5550136FFD](<Mini Pc/Apple/Macmini7/Macmini7,1/65598A0C8936/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/5550136FFD>) |
| 8086:22b5 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 33    | xhci_hcd   | [CDDC590270](<Mini Pc/BESSTAR Tech/Z83/Z83-F/833154D27E3C/ZORIN-16/5.13.0-30-GENERIC/X86_64/CDDC590270>) |
| 8086:a12f | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 29    | xhci_hcd   | [86D379E9D5](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/54383D955906/UBUNTU-20.10/5.8.0-63-GENERIC/X86_64/86D379E9D5>) |
| 1b21:1142 | 1043:85bf | ASMedia Techn... | ASM1042A USB 3.0 Host Controller     | 27    | xhci_pci   | [2F6DF3FFF6](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/86C8213ACE93/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2F6DF3FFF6>) |
| 8086:22b5 |           | Intel            | Atom/Celeron/Pentium Processor x5... | 27    | xhci_hcd   | [207E311CFC](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-102/8054EC01AC51/ASTRALINUXCE-2.12.44/5.10.0-1038.40-GENERIC/X86_64/207E311CFC>) |
| 10de:0aa5 | 10de:cb79 | Nvidia           | MCP79 OHCI USB 1.1 Controller        | 26    | ohci_pci   | [F114F6EA54](<Mini Pc/Apple/Macmini3/Macmini3,1/C67829525D2F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F114F6EA54>) |
| 10de:0aa6 | 10de:cb79 | Nvidia           | MCP79 EHCI USB 2.0 Controller        | 26    | ehci_pci   | [F114F6EA54](<Mini Pc/Apple/Macmini3/Macmini3,1/C67829525D2F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F114F6EA54>) |
| 10de:0aa7 | 10de:cb79 | Nvidia           | MCP79 OHCI USB 1.1 Controller        | 26    | ohci_pci   | [F114F6EA54](<Mini Pc/Apple/Macmini3/Macmini3,1/C67829525D2F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F114F6EA54>) |
| 10de:0aa9 | 10de:cb79 | Nvidia           | MCP79 EHCI USB 2.0 Controller        | 26    | ehci_pci   | [F114F6EA54](<Mini Pc/Apple/Macmini3/Macmini3,1/C67829525D2F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F114F6EA54>) |
| 1022:1639 | 1043:87e7 | AMD              | Renoir/Cezanne USB 3.1               | 25    | xhci_pci   | [2F6DF3FFF6](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/86C8213ACE93/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2F6DF3FFF6>) |
| 8086:9a13 |           | Intel            | Tiger Lake-LP Thunderbolt 4 USB C... | 24    | xhci_pci   | [CA53435B36](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/26774C86D363/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/CA53435B36>) |
| 8086:9a1b | 2222:1111 | Intel            | Tiger Lake-LP Thunderbolt 4 NHI #0   | 23    | thunder... | [CA53435B36](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/26774C86D363/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/CA53435B36>) |
| 8086:9a1d | 2222:1111 | Intel            | Tiger Lake-LP Thunderbolt 4 NHI #1   | 23    | thunder... | [CA53435B36](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/26774C86D363/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/CA53435B36>) |
| 10ec:816d | 1043:85b5 | Realtek Semic... | RTL811x EHCI host controller         | 19    | ehci_pci   | [2F6DF3FFF6](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/86C8213ACE93/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2F6DF3FFF6>) |
| 8086:9d2f | 8086:2063 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 19    | xhci_hcd   | [6879986BF2](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-505/29B4250B3145/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/6879986BF2>) |
| 8086:27c8 | 8086:7270 | Intel            | NM10/ICH7 Family USB UHCI Control... | 18    | uhci_hcd   | [2075A95BFB](<Mini Pc/Apple/Macmini2/Macmini2,1/8B91B715078D/FEDORA-30/5.3.11-100.FC29.I686/I686/2075A95BFB>) |
| 8086:27c9 | 8086:7270 | Intel            | NM10/ICH7 Family USB UHCI Control... | 18    | uhci_hcd   | [2075A95BFB](<Mini Pc/Apple/Macmini2/Macmini2,1/8B91B715078D/FEDORA-30/5.3.11-100.FC29.I686/I686/2075A95BFB>) |
| 8086:27ca | 8086:7270 | Intel            | NM10/ICH7 Family USB UHCI Control... | 18    | uhci_hcd   | [2075A95BFB](<Mini Pc/Apple/Macmini2/Macmini2,1/8B91B715078D/FEDORA-30/5.3.11-100.FC29.I686/I686/2075A95BFB>) |
| 8086:27cb | 8086:7270 | Intel            | NM10/ICH7 Family USB UHCI Control... | 18    | uhci_hcd   | [2075A95BFB](<Mini Pc/Apple/Macmini2/Macmini2,1/8B91B715078D/FEDORA-30/5.3.11-100.FC29.I686/I686/2075A95BFB>) |
| 8086:27cc | 8086:7270 | Intel            | NM10/ICH7 Family USB2 EHCI Contro... | 18    | ehci_pci   | [2075A95BFB](<Mini Pc/Apple/Macmini2/Macmini2,1/8B91B715078D/FEDORA-30/5.3.11-100.FC29.I686/I686/2075A95BFB>) |
| 8086:9d2f | 8086:2070 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 17    | xhci_hcd   | [0261508BA5](<Mini Pc/Intel Client Systems/NUC7/NUC7i3DNHE/F93E47848AEB/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/0261508BA5>) |
| 10de:0d9c | 10de:cb89 | Nvidia           | MCP89 OHCI USB 1.1 Controller        | 16    | ohci_pci   | [D7F1687670](<Mini Pc/Apple/Macmini4/Macmini4,1/BCBD7A97BE65/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D7F1687670>) |
| 10de:0d9d | 10de:cb89 | Nvidia           | MCP89 EHCI USB 2.0 Controller        | 16    | ehci_pci   | [D7F1687670](<Mini Pc/Apple/Macmini4/Macmini4,1/BCBD7A97BE65/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D7F1687670>) |
| 8086:a0ed | 8086:3004 | Intel            | Tiger Lake-LP USB 3.2 Gen 2x1 xHC... | 15    | xhci_pci   | [CA53435B36](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/26774C86D363/GENTOO-2.6/5.15.23-GENTOO-X86_64/X86_64/CA53435B36>) |
| 8086:a36d | 17aa:312d | Intel            | Cannon Lake PCH USB 3.1 xHCI Host... | 15    | xhci_hcd   | [88A943EC80](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T700BHBL/970C8BB93481/DEBIAN-11/5.10.0-11-AMD64/X86_64/88A943EC80>) |
| 1002:4396 | 103c:17e2 | AMD              | SB7x0/SB8x0/SB9x0 USB EHCI Contro... | 14    | ehci_pci   | [AE54C309D5](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/A9289FCA615E/DEBIAN-11/5.10.0-11-686-PAE/I686/AE54C309D5>) |
| 1002:4397 | 103c:17e2 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI0 Contr... | 14    | ohci_pci   | [AE54C309D5](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/A9289FCA615E/DEBIAN-11/5.10.0-11-686-PAE/I686/AE54C309D5>) |
| 104c:8241 | 103c:17e2 | Texas Instrum... | TUSB73x0 SuperSpeed USB 3.0 xHCI ... | 14    | xhci_pci   | [AE54C309D5](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/A9289FCA615E/DEBIAN-11/5.10.0-11-686-PAE/I686/AE54C309D5>) |
| 8086:15db | 2222:1111 | Intel            | JHL6340 Thunderbolt 3 USB 3.1 Con... | 13    | xhci_hcd   | [6434338413](<Mini Pc/Intel/NUC7i5BNB/NUC7i5BNB J31144-304/7594AA844CE4/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/6434338413>) |
| 8086:31a8 | 1043:875e | Intel            | Celeron/Pentium Silver Processor ... | 13    | xhci_hcd   | [27BB88805D](<Mini Pc/ASUSTek Computer/PN/PN40/21E857FB29E9/CENTOS-7/3.10.0-1160.53.1.EL7.X86_64/X86_64/27BB88805D>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:816e | 10ec:8168 | Realtek Semic... | RealManage BMC                       | 16    |            | [8366A84CDB](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/F373E702B28B/XUBUNTU-20.04/5.13.0-28-GENERIC/X86_64/8366A84CDB>) |
| 10ec:816e | 17aa:3181 | Realtek Semic... | RealManage BMC                       | 2     |            | [56F9A83D77](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75n 11GW000BUS/8D95E87EDCE7/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/56F9A83D77>) |

