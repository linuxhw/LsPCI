Most popular PCI devices in Servers
===================================

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Servers ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Firewire controller ](#firewire-controller-pci)
   * [ Generic system peripheral ](#generic-system-peripheral-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Input device controller ](#input-device-controller-pci)
   * [ Iommu ](#iommu-pci)
   * [ Ipmi smic interface ](#ipmi-smic-interface-pci)
   * [ Isdn adapter ](#isdn-adapter-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Multimedia controller ](#multimedia-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Network and computing encryption device ](#network-and-computing-encryption-device-pci)
   * [ Non-essential instrumentation ](#non-essential-instrumentation-pci)
   * [ Non-vga unclassified device ](#non-vga-unclassified-device-pci)
   * [ Parallel controller (ieee1284) ](#parallel-controller-ieee1284-pci)
   * [ Performance counters ](#performance-counters-pci)
   * [ Pic (8259) ](#pic-8259-pci)
   * [ Pic (io(x)-apic) ](#pic-iox-apic-pci)
   * [ Pic (io-apic) ](#pic-io-apic-pci)
   * [ Sd host controller ](#sd-host-controller-pci)
   * [ Serial bus controller ](#serial-bus-controller-pci)
   * [ Serial controller ](#serial-controller-pci)
   * [ Signal processing ](#signal-processing-pci)
   * [ Signal processing controller ](#signal-processing-controller-pci)
   * [ Signal processing management ](#signal-processing-management-pci)
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
   * [ Usb controller ](#usb-controller-pci)
   * [ Others ](#others-pci)

PCI Devices
-----------

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1a03:1150 | 1a03:1150 | ASPEED ... | AST1150 PCI-to-PCI Bridge    | 139   | shpchp     | 10F1608197 |
| 8086:2c70 | 8086:8086 | Intel      | Xeon 5600 Series QuickPat... | 106   |            | 451F363726 |
| 8086:2d81 | 8086:8086 | Intel      | Xeon 5600 Series QuickPat... | 106   |            | 451F363726 |
| 8086:2d90 | 8086:8086 | Intel      | Xeon 5600 Series QPI Link 0  | 106   |            | 451F363726 |
| 8086:2d91 | 8086:8086 | Intel      | Xeon 5600 Series QPI Phys... | 106   |            | 451F363726 |
| 8086:2d92 | 8086:8086 | Intel      | Xeon 5600 Series Mirror P... | 106   |            | 451F363726 |
| 8086:2d93 | 8086:8086 | Intel      | Xeon 5600 Series Mirror P... | 106   |            | 451F363726 |
| 8086:2d94 | 8086:8086 | Intel      | Xeon 5600 Series QPI Link 1  | 106   |            | 451F363726 |
| 8086:2d95 | 8086:8086 | Intel      | Xeon 5600 Series QPI Phys... | 106   |            | 451F363726 |
| 8086:2d98 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 106   |            | 451F363726 |
| 8086:2d99 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 106   |            | 451F363726 |
| 8086:2d9a | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 106   |            | 451F363726 |
| 8086:2d9c | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 106   |            | 451F363726 |
| 8086:2da0 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 106   |            | 451F363726 |
| 8086:2da1 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 106   |            | 451F363726 |
| 8086:2da2 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 106   |            | 451F363726 |
| 8086:2da3 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 106   |            | 451F363726 |
| 8086:2da8 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 106   |            | 451F363726 |
| 8086:2da9 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 106   |            | 451F363726 |
| 8086:2daa | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 106   |            | 451F363726 |
| 8086:2dab | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 106   |            | 451F363726 |
| 8086:2db0 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 106   |            | 451F363726 |
| 8086:2db1 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 106   |            | 451F363726 |
| 8086:2db2 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 106   |            | 451F363726 |
| 8086:2db3 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 106   |            | 451F363726 |
| 8086:2030 | 8086:0000 | Intel      | Sky Lake-E PCI Express Ro... | 77    | pcieport   | FE43558C7A |
| 8086:2032 | 8086:0000 | Intel      | Sky Lake-E PCI Express Ro... | 69    | pcieport   | E757687F86 |
| 8086:2020 | 8086:0000 | Intel      | Sky Lake-E DMI3 Registers    | 62    |            | E757687F86 |
| 8086:244e |           | Intel      | 82801 PCI Bridge             | 50    | shpchp     | E36BFCD946 |
| 8086:341c |           | Intel      | 7500/5520/5500/X58 Unknown   | 43    |            | A9C87C6C9C |
| 8086:341d |           | Intel      | 7500/5520/5500/X58 Unknown   | 43    |            | A9C87C6C9C |
| 8086:341e |           | Intel      | 7500/5520/5500/X58 Unknown   | 43    |            | A9C87C6C9C |
| 8086:3418 |           | Intel      | 7500/5520/5500/X58 Physic... | 42    |            | A9C87C6C9C |
| 8086:3419 |           | Intel      | 7500/5520/5500 Physical L... | 42    |            | A9C87C6C9C |
| 8086:341a |           | Intel      | 7500/5520/5500/X58 Unknown   | 42    |            | A9C87C6C9C |
| 8086:3439 |           | Intel      | 7500/5520/5500/X58 Unknown   | 42    |            | A9C87C6C9C |
| 8086:343a |           | Intel      | 7500/5520/5500/X58 Unknown   | 42    |            | A9C87C6C9C |
| 8086:343b |           | Intel      | 7500/5520/5500/X58 Unknown   | 42    |            | A9C87C6C9C |
| 8086:343c |           | Intel      | 7500/5520/5500/X58 Unknown   | 42    |            | A9C87C6C9C |
| 8086:343d |           | Intel      | 7500/5520/5500/X58 Unknown   | 42    |            | A9C87C6C9C |
| 8086:1d10 | 103c:18a9 | Intel      | C600/X79 series chipset P... | 41    | pcieport   | 7B579629BB |
| 8086:1d1e | 103c:18a9 | Intel      | C600/X79 series chipset P... | 41    | pcieport   | 7B579629BB |
| 8086:1d3e | 103c:18a9 | Intel      | C600/X79 series chipset P... | 41    | pcieport   | 7B579629BB |
| 8086:1d41 |           | Intel      | C600/X79 series chipset L... | 41    | lpc_ich    | 7B579629BB |
| 8086:244e | 103c:18a9 | Intel      | 82801 PCI Bridge             | 41    |            | 7B579629BB |
| 8086:25e3 |           | Intel      | 5000 Series Chipset PCI E... | 41    | pcieport   | 715B40D8B6 |
| 8086:3408 | 103c:330b | Intel      | 5520/5500/X58 I/O Hub PCI... | 40    | pcieport   | A9C87C6C9C |
| 8086:340a | 103c:330b | Intel      | 5520/5500/X58 I/O Hub PCI... | 40    | pcieport   | A9C87C6C9C |
| 8086:340e | 103c:330b | Intel      | 5520/5500/X58 I/O Hub PCI... | 40    | pcieport   | A9C87C6C9C |
| 8086:3410 | 103c:330b | Intel      | 7500/5520/5500/X58 I/O Hu... | 40    | pcieport   | A9C87C6C9C |
| 1912:0012 | 1912:0012 | Renesas... | SH7757 PCIe-PCI Bridge [PPB] | 39    | shpchp     | 1A5CF39F4F |
| 1912:0013 | 1912:0013 | Renesas... | SH7757 PCIe Switch [PS]      | 39    | pcieport   | 1A5CF39F4F |
| 8086:3411 | 103c:330b | Intel      | 7500/5520/5500/X58 I/O Hu... | 39    | pcieport   | A9C87C6C9C |
| 1002:4384 |           | AMD        | SBx00 PCI to PCI Bridge      | 38    |            | 1FE97B31A1 |
| 8086:244e | 103c:330d | Intel      | 82801 PCI Bridge             | 37    |            | A9C87C6C9C |
| 8086:2033 | 8086:0000 | Intel      | Sky Lake-E PCI Express Ro... | 36    | pcieport   | AD903545CE |
| 8086:3406 | 103c:330b | Intel      | 5520 I/O Hub to ESI Port     | 36    |            | A9C87C6C9C |
| 8086:3409 | 103c:330b | Intel      | 5520/5500/X58 I/O Hub PCI... | 36    | pcieport   | A9C87C6C9C |
| 8086:340f | 103c:330b | Intel      | 5520/5500/X58 I/O Hub PCI... | 36    | pcieport   | A9C87C6C9C |
| 8086:37c0 | 8086:0000 | Intel      | PCI bridge                   | 36    | pcieport   | 5E1947B31A |
| 8086:3a18 |           | Intel      | 82801JIB (ICH10) LPC Inte... | 36    | lpc_ich    | A9C87C6C9C |
| 8086:25e5 |           | Intel      | 5000 Series Chipset PCI E... | 35    | pcieport   | 715B40D8B6 |
| 8086:25e7 |           | Intel      | 5000 Series Chipset PCI E... | 35    | pcieport   | 715B40D8B6 |
| 8086:340b | 103c:330b | Intel      | 5520/X58 I/O Hub PCI Expr... | 35    | pcieport   | A9C87C6C9C |
| 8086:340c | 103c:330b | Intel      | 5520/X58 I/O Hub PCI Expr... | 35    | pcieport   | A9C87C6C9C |
| 8086:340d | 103c:330b | Intel      | 5520/X58 I/O Hub PCI Expr... | 35    | pcieport   | A9C87C6C9C |
| 1166:0103 |           | Broadcom   | EPB PCI-Express to PCI-X ... | 33    | shpchp     | 872AE76863 |
| 8086:341f |           | Intel      | 7500/5520/5500/X58 Unknown   | 33    |            | A9C87C6C9C |
| 8086:25f8 |           | Intel      | 5000 Series Chipset PCI E... | 31    | pcieport   | 872AE76863 |
| 8086:37c0 | beef:dead | Intel      | PCI bridge                   | 31    | pcieport   | AD903545CE |
| 8086:3a40 | 103c:330d | Intel      | 82801JI (ICH10 Family) PC... | 30    | pcieport   | A9C87C6C9C |
| 8086:3c00 | 103c:18a8 | Intel      | Xeon E5/Core i7 DMI2         | 30    |            | 5BFD235851 |
| 8086:3c02 | 103c:18a8 | Intel      | Xeon E5/Core i7 IIO PCI E... | 30    | pcieport   | 5BFD235851 |
| 8086:3c03 | 103c:18a8 | Intel      | Xeon E5/Core i7 IIO PCI E... | 30    | pcieport   | 5BFD235851 |
| 8086:3c08 | 103c:18a8 | Intel      | Xeon E5/Core i7 IIO PCI E... | 30    | pcieport   | 5BFD235851 |
| 8086:3c09 | 103c:18a8 | Intel      | Xeon E5/Core i7 IIO PCI E... | 30    | pcieport   | 5BFD235851 |
| 8086:3c0a | 103c:18a8 | Intel      | Xeon E5/Core i7 IIO PCI E... | 30    | pcieport   | 5BFD235851 |
| 8086:3c0b | 103c:18a8 | Intel      | Xeon E5/Core i7 IIO PCI E... | 30    | pcieport   | 5BFD235851 |
| 1912:001a | 1912:001a | Renesas... | SH7758 PCIe-PCI Bridge [PPB] | 29    | shpchp     | C7B39E92CA |
| 1912:001d | 1912:001d | Renesas... | SH7758 PCIe Switch [PS]      | 29    | pcieport   | C7B39E92CA |
| 1556:be00 |           | PLDA       | PCI Express Bridge           | 28    | shpchp     | E757687F86 |
| 1912:0012 |           | Renesas... | SH7757 PCIe-PCI Bridge [PPB] | 27    | shpchp     | D350652289 |
| 1912:0013 |           | Renesas... | SH7757 PCIe Switch [PS]      | 27    | shpchp     | D350652289 |
| 8086:2031 | 8086:0000 | Intel      | Sky Lake-E PCI Express Ro... | 27    | pcieport   | C7D795E2A5 |
| 8086:2f08 | 8086:0000 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 27    | pcieport   | C7B39E92CA |
| 8086:25f9 |           | Intel      | 5000 Series Chipset PCI E... | 26    | pcieport   | 872AE76863 |
| 8086:2670 |           | Intel      | 631xESB/632xESB/3100 Chip... | 26    | lpc_ich    | E36BFCD946 |
| 8086:2f02 | 8086:0000 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 26    | pcieport   | C7B39E92CA |
| 8086:2c01 | 8086:8086 | Intel      | Xeon 5500/Core i7 QuickPa... | 25    |            | 9CC6367D9F |
| 8086:2c10 | 8086:8086 | Intel      | Xeon 5500/Core i7 QPI Link 0 | 25    |            | 9CC6367D9F |
| 8086:2c11 | 8086:8086 | Intel      | Xeon 5500/Core i7 QPI Phy... | 25    |            | 9CC6367D9F |
| 8086:2c14 | 8086:8086 | Intel      | Xeon 5500/Core i7 QPI Link 1 | 25    |            | 9CC6367D9F |
| 8086:2c15 | 8086:8086 | Intel      | Xeon 5500/Core i7 QPI Phy... | 25    |            | 9CC6367D9F |
| 8086:2c18 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 25    |            | 9CC6367D9F |
| 8086:2c19 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 25    |            | 9CC6367D9F |
| 8086:2c1a | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 25    |            | 9CC6367D9F |
| 8086:2c1c | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 25    |            | 9CC6367D9F |
| 8086:2c20 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 25    |            | 9CC6367D9F |
| 8086:2c21 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 25    |            | 9CC6367D9F |
| 8086:2c22 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 25    |            | 9CC6367D9F |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:5229 | 10ec:5229 | Realtek... | RTS5229 PCI Express Card ... | 3     | rtsx_pci   | 6AEB74B9F1 |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:19e2 | 8086:0000 | Intel      | Atom Processor C3000 Seri... | 2     | qat_c3xxx  | 40E07B4DAD |
| 8086:2710 | 8086:0000 | Intel      | Co-processor                 | 2     |            | AEAD99F55D |
| 8086:37c8 | 8086:0000 | Intel      | C62x Chipset QuickAssist ... | 2     | qat_c62x   | 331227D869 |
| 8086:4940 | 8086:0000 | Intel      | Co-processor                 | 2     |            | AEAD99F55D |
| 8086:0434 | 8086:0000 | Intel      | DH89XXCC Series QAT          | 1     |            | 14C76E0C83 |
| 8086:1f18 | 15d9:0820 | Intel      | Atom processor C2000 QAT     | 1     |            | B9AC0D657E |
| 8086:225c | 8086:2500 | Intel      | Xeon Phi coprocessor SE10... | 1     | mic_host   | 9D9DA282F6 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a1ba | 8086:35ce | Intel      | C620 Series Chipset Famil... | 20    | mei_me     | 36C4ACAC2D |
| 8086:a1be | 8086:35ce | Intel      | C620 Series Chipset Famil... | 20    |            | 36C4ACAC2D |
| 8086:a1bb | 8086:35ce | Intel      | C620 Series Chipset Famil... | 19    |            | 36C4ACAC2D |
| 8086:8d3a | 15d9:0821 | Intel      | C610/X99 series chipset M... | 17    | mei_me     | AAEEE85BE7 |
| 8086:8d3b | 15d9:0821 | Intel      | C610/X99 series chipset M... | 17    |            | AAEEE85BE7 |
| 8086:a1ba | 8086:7270 | Intel      | C620 Series Chipset Famil... | 17    | mei_me     | AD903545CE |
| 8086:a1be | 8086:7270 | Intel      | C620 Series Chipset Famil... | 17    |            | AD903545CE |
| 8086:a1bb | 8086:7270 | Intel      | C620 Series Chipset Famil... | 16    |            | AD903545CE |
| 8086:1d3a | 1043:84ef | Intel      | C600/X79 series chipset M... | 14    | mei_me     | 874EAAB0BB |
| 8086:1d3b | 1043:84ef | Intel      | C600/X79 series chipset M... | 14    |            | 874EAAB0BB |
| 8086:1d3a | 15d9:0636 | Intel      | C600/X79 series chipset M... | 12    | mei_me     | DD93F62FFC |
| 8086:1d3b | 15d9:0636 | Intel      | C600/X79 series chipset M... | 12    |            | DD93F62FFC |
| 8086:1d3a | 1028:048c | Intel      | C600/X79 series chipset M... | 10    | mei_me     | 3BCB61F70C |
| 8086:1d3b | 1028:048c | Intel      | C600/X79 series chipset M... | 10    |            | 3BCB61F70C |
| 8086:8d3a | 8086:7270 | Intel      | C610/X99 series chipset M... | 10    | mei_me     | C04F902B93 |
| 8086:8d3b | 8086:7270 | Intel      | C610/X99 series chipset M... | 10    |            | C04F902B93 |
| 8086:1d3a | 1028:04fa | Intel      | C600/X79 series chipset M... | 8     | mei_me     | C9C876F0E7 |
| 8086:1d3b | 1028:04fa | Intel      | C600/X79 series chipset M... | 8     |            | C9C876F0E7 |
| 8086:a13a | 8086:1999 | Intel      | 100 Series/C230 Series Ch... | 8     | mei_me     | F3A274A366 |
| 8086:a1ba | 1028:073a | Intel      | C620 Series Chipset Famil... | 8     | mei_me     | C7D795E2A5 |
| 8086:a1ba | 1043:871e | Intel      | C620 Series Chipset Famil... | 8     | mei_me     | 55BDC0F976 |
| 8086:a1be | 1043:871e | Intel      | C620 Series Chipset Famil... | 8     |            | 55BDC0F976 |
| 8086:8d3a | 1043:85f6 | Intel      | C610/X99 series chipset M... | 7     | mei_me     | 4158CB76EF |
| 8086:8d3b | 1043:85f6 | Intel      | C610/X99 series chipset M... | 7     |            | 4158CB76EF |
| 8086:a1ba | 1590:00eb | Intel      | C620 Series Chipset Famil... | 7     | mei_me     | 7AB4F05613 |
| 8086:a1ba | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     | mei_me     | CEE7ED2CE9 |
| 8086:a1bb | 1043:871e | Intel      | C620 Series Chipset Famil... | 7     |            | 55BDC0F976 |
| 8086:a1bb | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     |            | CEE7ED2CE9 |
| 8086:a1be | 1590:00eb | Intel      | C620 Series Chipset Famil... | 7     |            | 7AB4F05613 |
| 8086:a1be | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     |            | CEE7ED2CE9 |
| 8086:1d3a | 1028:04ce | Intel      | C600/X79 series chipset M... | 6     | mei_me     | 7A9C742839 |
| 8086:1d3b | 1028:04ce | Intel      | C600/X79 series chipset M... | 6     |            | 7A9C742839 |
| 8086:8d3a | 1028:0601 | Intel      | C610/X99 series chipset M... | 6     | mei_me     | F90168C69D |
| 8086:8d3b | 1028:0601 | Intel      | C610/X99 series chipset M... | 6     |            | F90168C69D |
| 8086:a13b | 8086:1999 | Intel      | 100 Series/C230 Series Ch... | 6     | mei_me     | F3A274A366 |
| 8086:8d3a | 15d9:0831 | Intel      | C610/X99 series chipset M... | 5     | mei_me     | 64918C950D |
| 8086:8d3b | 15d9:0831 | Intel      | C610/X99 series chipset M... | 5     |            | 64918C950D |
| 8086:a13a | 1028:06a5 | Intel      | 100 Series/C230 Series Ch... | 5     | mei_me     | E2A3815DD2 |
| 8086:a13b | 1028:06a5 | Intel      | 100 Series/C230 Series Ch... | 5     | mei_me     | E2A3815DD2 |
| 8086:a1ba | 15d9:096d | Intel      | C620 Series Chipset Famil... | 5     | mei_me     | C8195297A4 |
| 8086:a1ba | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 5     | mei_me     | 5E1947B31A |
| 8086:a1bb | 15d9:096d | Intel      | C620 Series Chipset Famil... | 5     |            | C8195297A4 |
| 8086:a1bb | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 5     |            | 5E1947B31A |
| 8086:a1be | 15d9:096d | Intel      | C620 Series Chipset Famil... | 5     |            | C8195297A4 |
| 8086:a1be | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 5     |            | 5E1947B31A |
| 8086:1d3a | 1028:04f8 | Intel      | C600/X79 series chipset M... | 4     | mei_me     | 494CD954E9 |
| 8086:1d3a | 8086:357e | Intel      | C600/X79 series chipset M... | 4     | mei_me     | 0FADD1EBE3 |
| 8086:1d3a | 8086:35a0 | Intel      | C600/X79 series chipset M... | 4     | mei_me     | FE1E6CFF79 |
| 8086:1d3b | 1028:04f8 | Intel      | C600/X79 series chipset M... | 4     |            | 494CD954E9 |
| 8086:1d3b | 8086:357e | Intel      | C600/X79 series chipset M... | 4     |            | 0FADD1EBE3 |
| 8086:1d3b | 8086:35a0 | Intel      | C600/X79 series chipset M... | 4     |            | FE1E6CFF79 |
| 8086:8c3a | 15d9:0805 | Intel      | 8 Series/C220 Series Chip... | 4     | mei_me     | 019914CC29 |
| 8086:a13a | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 4     | mei_me     | BE8471A6F1 |
| 8086:a13a | 15d9:089a | Intel      | 100 Series/C230 Series Ch... | 4     | mei_me     | E8634FF947 |
| 8086:a1ba | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     | mei_me     | E9A1FC86F9 |
| 8086:a1ba | 1028:0739 | Intel      | C620 Series Chipset Famil... | 4     | mei_me     | 9E01FD5E8C |
| 8086:a1ba | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 4     | mei_me     | 5299B4DA87 |
| 8086:a1ba | 1849:a1ba | Intel      | C620 Series Chipset Famil... | 4     | mei_me     | 2244EB7809 |
| 8086:a1bb | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     |            | E9A1FC86F9 |
| 8086:a1be | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     |            | E9A1FC86F9 |
| 8086:a360 | 8086:7270 | Intel      | Cannon Lake PCH HECI Cont... | 4     | mei_me     | B8FFB92409 |
| 8086:1d3a | 1028:04cf | Intel      | C600/X79 series chipset M... | 3     | mei_me     | D350652289 |
| 8086:1d3a | 1028:0528 | Intel      | C600/X79 series chipset M... | 3     | mei_me     | 31EA0B6D96 |
| 8086:1d3b | 1028:04cf | Intel      | C600/X79 series chipset M... | 3     |            | D350652289 |
| 8086:1d3b | 1028:0528 | Intel      | C600/X79 series chipset M... | 3     |            | 31EA0B6D96 |
| 8086:319a | 1019:a94d | Intel      | Celeron/Pentium Silver Pr... | 3     | mei_me     | 6AEB74B9F1 |
| 8086:8c3a | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 3     | mei_me     | 938F3AEFA9 |
| 8086:8c3a | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 3     | mei_me     | 34DBD86F7B |
| 8086:8c3b | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 3     |            | 938F3AEFA9 |
| 8086:8c3b | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 3     |            | 34DBD86F7B |
| 8086:8d3a | 1028:0600 | Intel      | C610/X99 series chipset M... | 3     | mei_me     | A98D12AD3E |
| 8086:8d3a | 1028:0627 | Intel      | C610/X99 series chipset M... | 3     | mei_me     | C7B39E92CA |
| 8086:8d3a | 1028:0639 | Intel      | C610/X99 series chipset M... | 3     | mei_me     | E5766C8331 |
| 8086:8d3a | 1458:1000 | Intel      | C610/X99 series chipset M... | 3     | mei_me     | 2F69A2F89C |
| 8086:8d3a | 15d9:0834 | Intel      | C610/X99 series chipset M... | 3     | mei_me     | FA4BECDE8B |
| 8086:8d3a | 1d49:0a00 | Intel      | C610/X99 series chipset M... | 3     | mei_me     | 3510DD7B10 |
| 8086:8d3b | 1028:0600 | Intel      | C610/X99 series chipset M... | 3     |            | A98D12AD3E |
| 8086:8d3b | 1028:0627 | Intel      | C610/X99 series chipset M... | 3     |            | C7B39E92CA |
| 8086:8d3b | 1028:0639 | Intel      | C610/X99 series chipset M... | 3     |            | E5766C8331 |
| 8086:8d3b | 15d9:0834 | Intel      | C610/X99 series chipset M... | 3     |            | FA4BECDE8B |
| 8086:8d3b | 1d49:0a00 | Intel      | C610/X99 series chipset M... | 3     |            | 3510DD7B10 |
| 8086:a1ba | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     | mei_me     | E752263E49 |
| 8086:a1ba | 103c:81c6 | Intel      | C620 Series Chipset Famil... | 3     | mei_me     | 679871CFEC |
| 8086:a1ba | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     | mei_me     | 7AD1F5EB4E |
| 8086:a1ba | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     | mei_me     | C682299C13 |
| 8086:a1ba | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     | mei_me     | 5658A2FB98 |
| 8086:a1bb | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | E752263E49 |
| 8086:a1bb | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     |            | 7AD1F5EB4E |
| 8086:a1bb | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     |            | C682299C13 |
| 8086:a1be | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | E752263E49 |
| 8086:a1be | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     |            | 7AD1F5EB4E |
| 8086:a1be | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     |            | C682299C13 |
| 8086:a328 | 1028:088e | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | 2A87802C58 |
| 8086:a328 | 15d9:1a1b | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | F1BF9D35EF |
| 8086:a328 | 15d9:1a1d | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | E57FDAECA4 |
| 8086:a360 | 1028:088e | Intel      | Cannon Lake PCH HECI Cont... | 3     | mei_me     | 2A87802C58 |
| 8086:a360 | 15d9:1a1b | Intel      | Cannon Lake PCH HECI Cont... | 3     | mei_me     | F1BF9D35EF |
| 8086:a360 | 15d9:1a1d | Intel      | Cannon Lake PCH HECI Cont... | 3     | mei_me     | E57FDAECA4 |
| 8086:a361 | 15d9:1a1b | Intel      | 300 Series Chipset HECI #2   | 3     |            | F1BF9D35EF |
| 8086:a364 | 1028:088e | Intel      | Cannon Lake PCH HECI Cont... | 3     | mei_me     | 2A87802C58 |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1498 | 1022:1498 | AMD        | Starship/Matisse PTDMA       | 13    |            | F3CBAC183E |
| 1022:1486 | 1022:1486 | AMD        | Starship/Matisse Cryptogr... | 8     | ccp        | FEE94D715D |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 7     |            | 7735F49C62 |
| 1022:1486 | 1458:1000 | AMD        | Starship/Matisse Cryptogr... | 5     | ccp        | 96079334BD |
| 1022:1498 | 1458:1000 | AMD        | Starship/Matisse PTDMA       | 5     |            | 96079334BD |
| 1022:1456 | 1022:1456 | AMD        | Family 17h (Models 00h-0f... | 3     | ccp        | 10F1608197 |
| 1022:1468 | 1022:1468 | AMD        | Zeppelin Cryptographic Co... | 3     | ccp        | 10F1608197 |
| 1022:1486 | 1028:08ff | AMD        | Starship/Matisse Cryptogr... | 3     | ccp        | A35E7D3EB0 |
| 1022:1498 | 1028:08ff | AMD        | Starship/Matisse PTDMA       | 3     |            | A35E7D3EB0 |
| 1022:1456 | 1458:1000 | AMD        | Family 17h (Models 00h-0f... | 2     | ccp        | 6D486A7EE9 |
| 1022:1468 | 1458:1000 | AMD        | Zeppelin Cryptographic Co... | 2     | ccp        | 6D486A7EE9 |
| 1022:1456 | 1028:07f9 | AMD        | Family 17h (Models 00h-0f... | 1     | ccp        | 8F7FF50C55 |
| 1022:1468 | 1028:07f9 | AMD        | Zeppelin Cryptographic Co... | 1     | ccp        | 8F7FF50C55 |
| 1022:1486 | 1028:08fc | AMD        | Starship/Matisse Cryptogr... | 1     | ccp        | 9320E12A9A |
| 1022:1486 | 1028:08fd | AMD        | Starship/Matisse Cryptogr... | 1     | ccp        | F3CBAC183E |
| 1022:1498 | 1028:08fc | AMD        | Starship/Matisse PTDMA       | 1     |            | 9320E12A9A |
| 1022:1498 | 1028:08fd | AMD        | Starship/Matisse PTDMA       | 1     |            | F3CBAC183E |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 104c:8023 | 15d9:0100 | Texas I... | TSB43AB22A IEEE-1394a-200... | 5     | firewir... | C83DC07B7C |
| 104c:8023 | 15d9:0805 | Texas I... | TSB43AB22A IEEE-1394a-200... | 5     | firewir... | 019914CC29 |
| 1106:3403 | 1043:8384 | VIA Tec... | VT6315 Series Firewire Co... | 5     | firewir... | C3665EBF57 |
| 104c:8023 | 8086:34e2 | Texas I... | TSB43AB22A IEEE-1394a-200... | 4     | firewir... | FDCE629C37 |
| 1102:4001 | 1102:0010 | Creativ... | SB Audigy FireWire Port      | 4     | firewir... | F879FD97F7 |
| 1106:3403 | 1106:3403 | VIA Tec... | VT6315 Series Firewire Co... | 3     | firewir... | D8182AC89A |
| 104c:823f | 8086:3594 | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 2     | firewir... | E70645D3E6 |
| 1106:3044 | 1462:6520 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 2     | firewir... | B8300AFB35 |
| 104c:8023 | 10f1:2895 | Texas I... | TSB43AB22A IEEE-1394a-200... | 1     | firewir... | 768571B831 |
| 104c:8023 | 15d9:0653 | Texas I... | TSB43AB22A IEEE-1394a-200... | 1     | firewir... | 171EE8DB12 |
| 104c:8023 | 15d9:1411 | Texas I... | TSB43AB22A IEEE-1394a-200... | 1     | firewir... | 039BF2C96A |
| 104c:8024 | 1458:132c | Texas I... | TSB43AB23 IEEE-1394a-2000... | 1     | firewir... | 0AC54E7FB4 |
| 104c:823f | 3412:7856 | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 1     | firewir... | 21E2FBBB75 |
| 1106:3044 | 108e:534d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 1     | firewir... | 1F35F79302 |
| 1106:3044 | 1106:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 1     | firewir... | CC8DB94EBA |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:5a23 | 1002:5a23 | AMD        | RD890S/RD990 I/O Memory M... | 10    |            | AD61EFB931 |
| 1022:1577 | 1022:1577 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 5D00EDD035 |
| 8086:0b23 | 8086:0000 | Intel      | Generic system peripheral    | 2     | pcieport   | AEAD99F55D |
| 8086:0b23 | 8086:7270 | Intel      | Generic system peripheral    | 2     | pcieport   | AEAD99F55D |
| 8086:19a2 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 2     | pcieport   | 40E07B4DAD |
| 1022:1451 | 1022:1451 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 10F1608197 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1a03:2000 | 1a03:2000 | ASPEED ... | ASPEED Graphics Family       | 58    | ast        | BDE0BE6A50 |
| 102b:0533 | 103c:3381 | Matrox ... | MGA G200EH                   | 49    | mgag200    | CFFFE6AA63 |
| 1002:515e | 103c:31fb | AMD        | ES1000                       | 45    | radeon     | A9C87C6C9C |
| 102b:0522 | 8086:0103 | Matrox ... | MGA G200e [Pilot] ServerE... | 25    | mgag200    | F3A274A366 |
| 1a03:2000 | 15d9:0821 | ASPEED ... | ASPEED Graphics Family       | 17    | ast        | AAEEE85BE7 |
| 102b:0532 | 1028:0235 | Matrox ... | MGA G200eW WPCM450           | 16    | mgag200    | 246F93C093 |
| 10de:1eba | 10de:0000 | Nvidia     | 3D controller                | 15    | nvidia     | 4391DFF8D2 |
| 102b:0522 | 8086:0101 | Matrox ... | MGA G200e [Pilot] ServerE... | 14    | mgag200    | 451F363726 |
| 102b:0532 | 15d9:0006 | Matrox ... | MGA G200eW WPCM450           | 13    | mgag200    | 0B3B288186 |
| 102b:0534 | 15d9:0636 | Matrox ... | G200eR2                      | 12    | mgag200    | DD93F62FFC |
| 102b:0530 | 1014:0369 | Matrox ... | MGA G200EV                   | 11    | mgag200    | B4A013EED4 |
| 102b:0536 |           | Matrox ... | Integrated Matrox G200eW3... | 11    | mgag200    | 9320E12A9A |
| 102b:0522 | 19a2:0101 | Matrox ... | MGA G200e [Pilot] ServerE... | 10    | mgag200    | 928EE22E71 |
| 102b:0534 | 1028:048c | Matrox ... | G200eR2                      | 10    | mgag200    | 3BCB61F70C |
| 102b:0534 | 1014:0405 | Matrox ... | G200eR2                      | 9     | mgag200    | 8538814CD6 |
| 1a03:2000 | 1043:85f9 | ASPEED ... | ASPEED Graphics Family       | 8     | ast        | 4158CB76EF |
| 1002:9874 | 1002:1871 | AMD        | Wani [Radeon R5/R6/R7 Gra... | 7     | amdgpu     | 7735F49C62 |
| 102b:0532 | 1028:0236 | Matrox ... | MGA G200eW WPCM450           | 7     | mgag200    | 26944912D7 |
| 102b:0532 | 1028:02a4 | Matrox ... | MGA G200eW WPCM450           | 7     | mgag200    | 2A289951DE |
| 102b:0538 | 1590:00e4 | Matrox ... | MGA G200eH3                  | 7     | mgag200    | 7AB4F05613 |
| 10de:128b | 1462:8c93 | Nvidia     | GK208B [GeForce GT 710]      | 7     | nouveau    | 4DC142D672 |
| 19e5:1711 |           | Huawei ... | Hi171x Series [iBMC Intel... | 7     | hibmc_drm  | AD903545CE |
| 1a03:2000 | 1043:86ed | ASPEED ... | ASPEED Graphics Family       | 7     | ast        | 55BDC0F976 |
| 1a03:2000 | 1458:1000 | ASPEED ... | ASPEED Graphics Family       | 7     | ast        | 96079334BD |
| 1a03:2000 | 15d9:0801 | ASPEED ... | ASPEED Graphics Family       | 7     | ast        | EA6FC4377F |
| 102b:0532 | 1028:028c | Matrox ... | MGA G200eW WPCM450           | 6     | mgag200    | F46A021C88 |
| 102b:0532 | 15d9:0001 | Matrox ... | MGA G200eW WPCM450           | 6     | mgag200    | AFA93003E2 |
| 102b:0532 | 15d9:ab11 | Matrox ... | MGA G200eW WPCM450           | 6     | mgag200    | D5563E325C |
| 102b:0534 | 1028:04ce | Matrox ... | G200eR2                      | 6     | mgag200    | 7A9C742839 |
| 102b:0534 | 1028:04fa | Matrox ... | G200eR2                      | 6     | mgag200    | C9C876F0E7 |
| 102b:0534 | 1028:0601 | Matrox ... | G200eR2                      | 6     | mgag200    | F90168C69D |
| 10de:128b | 196e:118b | Nvidia     | GK208B [GeForce GT 710]      | 6     | nouveau    | 3A68279F78 |
| 102b:0532 | 1028:04de | Matrox ... | MGA G200eW WPCM450           | 5     | mgag200    | 0893528A1F |
| 102b:0532 | 15d9:0400 | Matrox ... | MGA G200eW WPCM450           | 5     | mgag200    | AD4ABE60CD |
| 102b:0532 | 15d9:bc11 | Matrox ... | MGA G200eW WPCM450           | 5     | mgag200    | 1FE97B31A1 |
| 102b:0534 | 1028:06a5 | Matrox ... | G200eR2                      | 5     | mgag200    | E2A3815DD2 |
| 1a03:2000 | 15d9:0831 | ASPEED ... | ASPEED Graphics Family       | 5     | ast        | 64918C950D |
| 1a03:2000 | 15d9:096d | ASPEED ... | ASPEED Graphics Family       | 5     | ast        | C8195297A4 |
| 1a03:2000 | 15d9:0981 | ASPEED ... | ASPEED Graphics Family       | 5     | ast        | 5E1947B31A |
| 1002:515e | 1028:01b2 | AMD        | ES1000                       | 4     | radeon     | 252659BF58 |
| 1002:515e | 1028:01e7 | AMD        | ES1000                       | 4     | radeon     | EA66809CE7 |
| 102b:0522 | 103c:0100 | Matrox ... | MGA G200e [Pilot] ServerE... | 4     | mgag200    | 28B04C3004 |
| 102b:0522 | 1734:108e | Matrox ... | MGA G200e [Pilot] ServerE... | 4     | mgag200    | 43C0756BA6 |
| 102b:0532 | 1028:0237 | Matrox ... | MGA G200eW WPCM450           | 4     | mgag200    | 46D07193B2 |
| 102b:0532 | 1028:02a6 | Matrox ... | MGA G200eW WPCM450           | 4     | mgag200    | 9C8826C0D2 |
| 102b:0532 | 1028:02f1 | Matrox ... | MGA G200eW WPCM450           | 4     | mgag200    | DEE1F70644 |
| 102b:0532 | 1028:0444 | Matrox ... | MGA G200eW WPCM450           | 4     | mgag200    | AD7D2477F8 |
| 102b:0532 | 1028:04dd | Matrox ... | MGA G200eW WPCM450           | 4     | mgag200    | D52DB39EEB |
| 102b:0532 | 15d9:0100 | Matrox ... | MGA G200eW WPCM450           | 4     | mgag200    | C83DC07B7C |
| 102b:0532 | 15d9:060f | Matrox ... | MGA G200eW WPCM450           | 4     | mgag200    | CF99AAD395 |
| 102b:0534 | 1028:04f8 | Matrox ... | G200eR2                      | 4     | mgag200    | 494CD954E9 |
| 102b:0536 | 1028:0715 | Matrox ... | Integrated Matrox G200eW3... | 4     | mgag200    | E9A1FC86F9 |
| 10de:0638 | 10de:062c | Nvidia     | G94GL [Quadro FX 1800]       | 4     | nvidia     | 1D4FEABAAA |
| 10de:11b4 | 10de:1096 | Nvidia     | GK104GL [Quadro K4200]       | 4     | nvidia     | F508BB4C99 |
| 1a03:2000 | 1043:84eb | ASPEED ... | ASPEED Graphics Family       | 4     | ast        | 874EAAB0BB |
| 1a03:2000 | 1043:8544 | ASPEED ... | ASPEED Graphics Family       | 4     | ast        | FEC09C0BAC |
| 1a03:2000 | 15d9:0728 | ASPEED ... | ASPEED Graphics Family       | 4     | ast        | C04F902B93 |
| 1a03:2000 | 15d9:089a | ASPEED ... | ASPEED Graphics Family       | 4     | ast        | E8634FF947 |
| 1002:515e | 1028:01b3 | AMD        | ES1000                       | 3     | radeon     | 8571D09FE7 |
| 1002:515e | 8086:3476 | AMD        | ES1000                       | 3     | radeon     | D471D2B279 |
| 102b:0522 | 1734:11cc | Matrox ... | MGA G200e [Pilot] ServerE... | 3     | mgag200    | 9C16958A72 |
| 102b:0522 | 19a2:0100 | Matrox ... | MGA G200e [Pilot] ServerE... | 3     | mgag200    | 91AD975174 |
| 102b:0532 | 1028:02d4 | Matrox ... | MGA G200eW WPCM450           | 3     | mgag200    | 26B693742E |
| 102b:0532 | 15d9:0404 | Matrox ... | MGA G200eW WPCM450           | 3     | mgag200    | 9CC6367D9F |
| 102b:0532 | 15d9:0600 | Matrox ... | MGA G200eW WPCM450           | 3     | mgag200    | ACA2A2FFDF |
| 102b:0532 | 15d9:a811 | Matrox ... | MGA G200eW WPCM450           | 3     | mgag200    | 201AA7046E |
| 102b:0534 | 1028:0528 | Matrox ... | G200eR2                      | 3     | mgag200    | 31EA0B6D96 |
| 102b:0534 | 1028:0600 | Matrox ... | G200eR2                      | 3     | mgag200    | A98D12AD3E |
| 102b:0534 | 1028:0627 | Matrox ... | G200eR2                      | 3     | mgag200    | C7B39E92CA |
| 102b:0534 | 1028:0639 | Matrox ... | G200eR2                      | 3     | mgag200    | E5766C8331 |
| 102b:0534 | 1d49:0a01 | Matrox ... | G200eR2                      | 3     | mgag200    | 3510DD7B10 |
| 102b:0536 | 1028:0716 | Matrox ... | Integrated Matrox G200eW3... | 3     | mgag200    | E752263E49 |
| 10de:1287 | 1043:84f5 | Nvidia     | GK208B [GeForce GT 730]      | 3     | nvidia     | 5D93D067D7 |
| 10de:1bb1 | 103c:11a3 | Nvidia     | GP104GL [Quadro P4000]       | 3     | nouveau    | 9D6E46ECA9 |
| 10de:1cb3 | 1028:11be | Nvidia     | GP107GL [Quadro P400]        | 3     | nvidia     | 1567EFE934 |
| 10de:1e04 | 1458:37c4 | Nvidia     | TU102 [GeForce RTX 2080 Ti]  | 3     | nvidia     | F9D0B2BC99 |
| 1a03:2000 | 15d9:0834 | ASPEED ... | ASPEED Graphics Family       | 3     | ast        | FA4BECDE8B |
| 1a03:2000 | 15d9:086d | ASPEED ... | ASPEED Graphics Family       | 3     | ast        | 938F3AEFA9 |
| 1a03:2000 | 15d9:0892 | ASPEED ... | ASPEED Graphics Family       | 3     | ast        | 822418675E |
| 1a03:2000 | 15d9:0895 | ASPEED ... | ASPEED Graphics Family       | 3     | ast        | 5C898D272B |
| 1a03:2000 | 15d9:0921 | ASPEED ... | ASPEED Graphics Family       | 3     | ast        | 34DBD86F7B |
| 1a03:2000 | 15d9:0953 | ASPEED ... | ASPEED Graphics Family       | 3     | ast        | 7AD1F5EB4E |
| 1a03:2000 | 15d9:095d | ASPEED ... | ASPEED Graphics Family       | 3     | ast        | C682299C13 |
| 1a03:2000 | 15d9:1a1b | ASPEED ... | ASPEED Graphics Family       | 3     | ast        | F1BF9D35EF |
| 8086:3185 | 1019:a94d | Intel      | GeminiLake [UHD Graphics ... | 3     | i915       | 6AEB74B9F1 |
| 1002:5159 | 1028:016d | AMD        | RV100 [Radeon 7000 / Rade... | 2     | radeon     | 08919C80E8 |
| 1002:515e | 1028:01f0 | AMD        | ES1000                       | 2     |            | E36BFCD946 |
| 1002:515e | 8086:346c | AMD        | ES1000                       | 2     | radeon     | 390F15B7F9 |
| 1002:515e | 8086:3486 | AMD        | ES1000                       | 2     | radeon     | 0A3F6D305B |
| 1002:6611 | 1028:210b | AMD        | Oland [Radeon HD 8570 / R... | 2     | radeon     | 5D6883F1BB |
| 1002:66af | 1002:081e | AMD        | Vega 20 [Radeon VII]         | 2     | amdgpu     | 0343B901D9 |
| 1002:6771 | 1028:2120 | AMD        | Caicos XTX [Radeon HD 849... | 2     | radeon     | 61DFD26E01 |
| 1002:6778 | 1028:2120 | AMD        | Caicos XT [Radeon HD 7470... | 2     | radeon     | 5D6883F1BB |
| 1002:6798 | 174b:3001 | AMD        | Tahiti XT [Radeon HD 7970... | 2     | radeon     | BEA324B5DA |
| 1002:67df | 1da2:e366 | AMD        | Ellesmere [Radeon RX 470/... | 2     | amdgpu     | D09F385D74 |
| 1002:67ef | 1682:956d | AMD        | Baffin [Radeon RX 460/560... | 2     | amdgpu     | D350652289 |
| 1002:68f9 | 1462:2127 | AMD        | Cedar [Radeon HD 5000/600... | 2     | radeon     | E014B80891 |
| 102b:0522 | 1033:8372 | Matrox ... | MGA G200e [Pilot] ServerE... | 2     | mgag200    | 460A274240 |
| 102b:0522 | 103c:31fa | Matrox ... | MGA G200e [Pilot] ServerE... | 2     | mgag200    | 20AE4260BB |
| 102b:0522 | 8086:0102 | Matrox ... | MGA G200e [Pilot] ServerE... | 2     | mgag200    | DAA63A315C |

### Input device controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1102:7003 | 1102:0040 | Creativ... | SB Audigy Game Port          | 2     | Emu10k1... | F879FD97F7 |
| 1102:7002 | 1102:0020 | Creativ... | SB Live! Game Port           | 1     | emu10k1_gp | 80DC2F8936 |
| 1102:7003 | 1102:0060 | Creativ... | SB Audigy Game Port          | 1     | emu10k1_gp | D471D2B279 |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1481 | 1022:1481 | AMD        | Starship/Matisse IOMMU       | 6     |            | FEE94D715D |
| 1022:1481 | 1458:1000 | AMD        | Starship/Matisse IOMMU       | 4     |            | 96079334BD |
| 1002:5a23 | 1028:0444 | AMD        | RD890S/RD990 I/O Memory M... | 2     |            | B913A90C28 |
| 1022:1481 | 1028:08ff | AMD        | Starship/Matisse IOMMU       | 2     |            | A35E7D3EB0 |
| 1002:5a23 | 103c:1762 | AMD        | RD890S/RD990 I/O Memory M... | 1     |            | E60DA0D6CE |
| 1002:5a23 | 103c:3324 | AMD        | RD890S/RD990 I/O Memory M... | 1     |            | 7CE46A749E |
| 1022:1451 | 1028:07f9 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 8F7FF50C55 |
| 1022:1481 | 1028:08fd | AMD        | Starship/Matisse IOMMU       | 1     |            | F3CBAC183E |
| 1022:164f | 1022:164f | AMD        | IOMMU                        | 1     |            | 04144B327A |
| 1022:164f | 1028:08fc | AMD        | IOMMU                        | 1     |            | 9320E12A9A |
| 1022:164f | 1028:08ff | AMD        | IOMMU                        | 1     |            | B7AC531BF5 |
| 8086:1f16 | 15d9:0820 | Intel      | Atom processor C2000 RCEC    | 1     |            | B9AC0D657E |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 103c:3302 | 103c:3305 | Hewlett... | Integrated Lights-Out Sta... | 27    | ipmi_si    | DCBC2D451E |

### Isdn adapter (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1244:0a00 | 1244:0a00 | AVM        | A1 ISDN [Fritz]              | 1     | fcpci      | 750A124EF3 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a1a1 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 19    |            | 36C4ACAC2D |
| 8086:a1a1 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 17    |            | AD903545CE |
| 8086:a36f | 8086:7270 | Intel      | Cannon Lake PCH Shared SRAM  | 12    |            | 99AE6D7DBE |
| 8086:a121 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 9     |            | F3A274A366 |
| 8086:a1a1 | 1028:073a | Intel      | C620 Series Chipset Famil... | 8     |            | C7D795E2A5 |
| 8086:a1a1 | 1043:871e | Intel      | C620 Series Chipset Famil... | 8     |            | 55BDC0F976 |
| 8086:a1a1 | 1590:00eb | Intel      | C620 Series Chipset Famil... | 7     |            | 7AB4F05613 |
| 8086:a1a1 | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     |            | CEE7ED2CE9 |
| 8086:a36f |           | Intel      | Cannon Lake PCH Shared SRAM  | 6     |            | 2A87802C58 |
| 8086:a121 | 1028:06a5 | Intel      | 100 Series/C230 Series Ch... | 5     |            | E2A3815DD2 |
| 8086:a1a1 | 15d9:096d | Intel      | C620 Series Chipset Famil... | 5     |            | C8195297A4 |
| 8086:a1a1 | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 5     |            | 5E1947B31A |
| 1590:005f | 1590:005f | Hewlett... | Memory controller            | 4     |            | 3A14AEA222 |
| 8086:a121 | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 4     |            | BE8471A6F1 |
| 8086:a121 | 15d9:089a | Intel      | 100 Series/C230 Series Ch... | 4     |            | E8634FF947 |
| 8086:a1a1 | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     |            | E9A1FC86F9 |
| 8086:a1a1 | 1028:0739 | Intel      | C620 Series Chipset Famil... | 4     |            | 9E01FD5E8C |
| 8086:a1a1 | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 4     |            | 5299B4DA87 |
| 8086:a1a1 | 1849:a1a1 | Intel      | C620 Series Chipset Famil... | 4     |            | 2244EB7809 |
| 8086:a36f | 8086:a36f | Intel      | Cannon Lake PCH Shared SRAM  | 4     |            | B8FFB92409 |
| 8086:a1a1 | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | E752263E49 |
| 8086:a1a1 | 103c:81c6 | Intel      | C620 Series Chipset Famil... | 3     |            | 679871CFEC |
| 8086:a1a1 | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     |            | 7AD1F5EB4E |
| 8086:a1a1 | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     |            | C682299C13 |
| 8086:a1a1 | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     |            | 5658A2FB98 |
| 10de:0369 | 1462:cb84 | Nvidia     | MCP55 Memory Controller      | 2     |            | B8300AFB35 |
| 1912:0011 |           | Renesas... | SH7757 PCIe End-Point [PBI]  | 2     |            | EB7B7FD10B |
| 8086:19de | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 2     |            | 40E07B4DAD |
| 8086:1bce | 8086:7270 | Intel      | RAM memory                   | 2     |            | AEAD99F55D |
| 8086:a121 | 15d9:088b | Intel      | 100 Series/C230 Series Ch... | 2     |            | C0E1C15247 |
| 8086:a121 | 8086:a121 | Intel      | 100 Series/C230 Series Ch... | 2     |            | C4D59010A1 |
| 8086:a1a1 | 1028:0718 | Intel      | C620 Series Chipset Famil... | 2     |            | 1CCB5D67C2 |
| 8086:a1a1 | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     |            | DF9A63BE43 |
| 8086:a1a1 | 1028:07cb | Intel      | C620 Series Chipset Famil... | 2     |            | FE43558C7A |
| 8086:a1a1 | 1028:07e5 | Intel      | C620 Series Chipset Famil... | 2     |            | 4C88B2E09B |
| 8086:a1a1 | 15d9:091c | Intel      | C620 Series Chipset Famil... | 2     |            | 748FB8054B |
| 8086:a1a1 | 15d9:0941 | Intel      | C620 Series Chipset Famil... | 2     |            | C619DB847B |
| 8086:a1a1 | 17aa:7800 | Intel      | C620 Series Chipset Famil... | 2     |            | 928EE22E71 |
| 10de:005e | 10f1:2891 | Nvidia     | CK804 Memory Controller      | 1     |            | 64251B3F2A |
| 10de:005e | 10f1:2895 | Nvidia     | CK804 Memory Controller      | 1     |            | 768571B831 |
| 10de:00d3 | 10f1:2891 | Nvidia     | CK804 Memory Controller      | 1     |            | 64251B3F2A |
| 10de:00d3 | 10f1:2895 | Nvidia     | CK804 Memory Controller      | 1     |            | 768571B831 |
| 10de:0369 | 108e:534b | Nvidia     | MCP55 Memory Controller      | 1     |            | E54A36A0C4 |
| 10de:0369 | 108e:534d | Nvidia     | MCP55 Memory Controller      | 1     |            | 1F35F79302 |
| 10de:0369 | 1462:2800 | Nvidia     | MCP55 Memory Controller      | 1     |            | 933EED177A |
| 1b94:1500 | 1b94:1500 | Signate... | Memory controller            | 1     |            | B3C09674CF |
| 8086:0374 |           | Intel      | 80333 Address Translation... | 1     |            | 8571D09FE7 |
| 8086:a121 | 1028:06a6 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 55471D97F1 |
| 8086:a121 | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     |            | C74A66C7E6 |
| 8086:a121 | 103c:8165 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 3C08E6393F |
| 8086:a121 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 1     |            | BB8832ACBD |
| 8086:a121 | 15d9:0885 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 50169A0FFB |
| 8086:a121 | 15d9:0886 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 80DC2F8936 |
| 8086:a121 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     |            | C392838A14 |
| 8086:a121 | 15d9:0907 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 66EE0BC524 |
| 8086:a121 | 1734:1222 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 0BD7D9FCEA |
| 8086:a1a1 | 1028:07c9 | Intel      | C620 Series Chipset Famil... | 1     |            | E757687F86 |
| 8086:a1a1 | 1458:5001 | Intel      | C620 Series Chipset Famil... | 1     |            | 7E93E1B694 |
| 8086:a1a1 | 15d9:095e | Intel      | C620 Series Chipset Famil... | 1     |            | E0F65B7228 |
| 8086:a1a1 | 15d9:0962 | Intel      | C620 Series Chipset Famil... | 1     |            | 57460AA45B |
| 8086:a1a1 | 15d9:0967 | Intel      | C620 Series Chipset Famil... | 1     |            | 6FAB4E3135 |
| 8086:a1a1 | 15d9:0968 | Intel      | C620 Series Chipset Famil... | 1     |            | 7026C20C97 |
| 8086:a1a1 | 15d9:096e | Intel      | C620 Series Chipset Famil... | 1     |            | 4D0ED95E02 |
| 8086:a1a1 | 15d9:0986 | Intel      | C620 Series Chipset Famil... | 1     |            | 331227D869 |
| 8086:a1a1 | 15d9:0987 | Intel      | C620 Series Chipset Famil... | 1     |            | 893E9D69F2 |
| 8086:a1a1 | 1734:1230 | Intel      | C620 Series Chipset Famil... | 1     |            | 86AB491564 |
| 8086:a1a1 | 17aa:1037 | Intel      | C620 Series Chipset Famil... | 1     |            | 41249F2E48 |
| 8086:a1a1 | 8086:35cd | Intel      | C620 Series Chipset Famil... | 1     |            | 9CF9DCEEE9 |
| 8086:a2a1 | 15d9:098e | Intel      | 200 Series/Z370 Chipset F... | 1     |            | 98ED2C77C7 |
| 8086:a2a1 | 15d9:1b14 | Intel      | 200 Series/Z370 Chipset F... | 1     |            | 43A2D3F891 |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 109e:0878 |           | Brooktree  | Bt878 Audio Capture          | 1     | bt878      | B55D1DAEA5 |
| 109e:0878 | 0070:ff04 | Brooktree  | Bt878 Audio Capture          | 1     |            | 2C877CF870 |
| 109e:0878 | 800a:763d | Brooktree  | Bt878 Audio Capture          | 1     |            | 7E72574FF4 |
| 109e:0878 | 800b:763d | Brooktree  | Bt878 Audio Capture          | 1     |            | 7E72574FF4 |
| 109e:0878 | 800c:763d | Brooktree  | Bt878 Audio Capture          | 1     |            | 7E72574FF4 |
| 109e:0878 | 800d:763d | Brooktree  | Bt878 Audio Capture          | 1     |            | 7E72574FF4 |
| 1131:7164 | 0070:8851 | Philips... | SAA7164                      | 1     | saa7164    | 019914CC29 |
| 1797:6869 |           | Intersi... | C968 PCIe SD Capture         | 1     | avc8000    | 375EC8881D |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:1639 | 103c:7055 | Broadcom   | NetXtreme II BCM5709 Giga... | 33    | bnx2       | A9C87C6C9C |
| 14e4:1657 | 103c:169d | Broadcom   | NetXtreme BCM5719 Gigabit... | 22    | tg3        | 5BFD235851 |
| 8086:1572 | 8086:0000 | Intel      | Ethernet Controller X710 ... | 22    | i40e       | 928EE22E71 |
| 14e4:165f | 1028:1f5b | Broadcom   | NetXtreme BCM5720 Gigabit... | 19    | tg3        | 3BCB61F70C |
| 8086:15b9 | 8086:0000 | Intel      | Ethernet Connection (3) I... | 17    | e1000e     | 4391DFF8D2 |
| 14e4:1639 | 1028:0235 | Broadcom   | NetXtreme II BCM5709 Giga... | 16    | bnx2       | 246F93C093 |
| 8086:37d2 | 15d9:37d2 | Intel      | Ethernet Connection X722 ... | 16    | i40e       | 5E1947B31A |
| 8086:153a | 15d9:153a | Intel      | Ethernet Connection I217-LM  | 14    | e1000e     | 019914CC29 |
| 14e4:164c | 103c:7038 | Broadco... | NetXtreme II BCM5708 Giga... | 13    | bnx2       | B6088E88BA |
| 14e4:1657 | 103c:22be | Broadcom   | NetXtreme BCM5719 Gigabit... | 13    | tg3        | 7AB4F05613 |
| 8086:10fb | 8086:0003 | Intel      | 82599 10 Gigabit Dual Por... | 10    | ixgbe      | 882EA8E25E |
| 14e4:1639 | 1028:0236 | Broadcom   | NetXtreme II BCM5709 Giga... | 9     | bnx2       | 26944912D7 |
| 14e4:163b | 1028:02a4 | Broadcom   | NetXtreme II BCM5716 Giga... | 9     | bnx2       | 56B5E62268 |
| 8086:10fb | 108e:7b11 | Intel      | 82599 10 Gigabit Dual Por... | 9     | ixgbe      | 5A96F790B1 |
| 8086:1521 | 103c:3380 | Intel      | I350 Gigabit Network Conn... | 9     | igb        | 1E7A730FCC |
| 14e4:163b | 1028:028c | Broadcom   | NetXtreme II BCM5716 Giga... | 8     | bnx2       | 24358FA4BD |
| 14e4:165f | 1028:04fa | Broadcom   | NetXtreme BCM5720 Gigabit... | 8     | tg3        | C9C876F0E7 |
| 14e4:165f | 103c:22e8 | Broadcom   | NetXtreme BCM5720 Gigabit... | 8     | tg3        | 7735F49C62 |
| 8086:1528 | 15d9:1528 | Intel      | Ethernet Controller 10-Gi... | 8     | ixgbe      | 3CFD00A1CD |
| 8086:1563 | 15d9:1563 | Intel      | Ethernet Controller 10G X... | 8     | ixgbe      | C8195297A4 |
| 8086:15b9 | 1028:073a | Intel      | Ethernet Connection (3) I... | 8     | e1000e     | C7D795E2A5 |
| 8086:1076 | 8086:34d0 | Intel      | 82541GI Gigabit Ethernet ... | 7     | e1000      | FC38CA11F5 |
| 8086:1572 | 8086:0001 | Intel      | Ethernet Controller X710 ... | 7     | i40e       | 928EE22E71 |
| 8086:1572 | 8086:000a | Intel      | Ethernet Controller X710 ... | 7     | i40e       | CEE7ED2CE9 |
| 8086:37d1 | 15d9:37d1 | Intel      | Ethernet Connection X722 ... | 7     | i40e       | 6FAB4E3135 |
| 8086:37d1 | 17aa:4020 | Intel      | Ethernet Connection X722 ... | 7     | i40e       | CEE7ED2CE9 |
| 8086:37d2 | 17aa:4020 | Intel      | Ethernet Connection X722 ... | 7     | i40e       | CEE7ED2CE9 |
| 14e4:165a | 1028:04de | Broadcom   | NetXtreme BCM5722 Gigabit... | 6     | tg3        | 0893528A1F |
| 8086:15b7 | 15d9:15b7 | Intel      | Ethernet Connection (2) I... | 6     | e1000e     | BE8471A6F1 |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8169      | AAEEE85BE7 |
| 14e4:1639 | 1014:03a9 | Broadcom   | NetXtreme II BCM5709 Giga... | 5     | bnx2       | B4A013EED4 |
| 14e4:1639 | 1028:0237 | Broadco... | NetXtreme II BCM5709 Giga... | 5     | bnx2       | 46D07193B2 |
| 14e4:1639 | 14e4:0906 | Broadco... | NetXtreme II BCM5709 Giga... | 5     | bnx2       | E36BFCD946 |
| 14e4:1639 | 14e4:1906 | Broadco... | NetXtreme II BCM5709 Giga... | 5     | bnx2       | E36BFCD946 |
| 14e4:164c | 1028:01b2 | Broadcom   | NetXtreme II BCM5708 Giga... | 5     | bnx2       | 252659BF58 |
| 14e4:165f | 1028:06a5 | Broadcom   | NetXtreme BCM5720 Gigabit... | 5     | tg3        | E2A3815DD2 |
| 14e4:165f | 14e4:4160 | Broadco... | NetXtreme BCM5720 Gigabit... | 5     | tg3        | E9A1FC86F9 |
| 14e4:16d8 | 14e4:4160 | Broadco... | BCM57416 NetXtreme-E Dual... | 5     | bnxt_en    | E9A1FC86F9 |
| 8086:105e | 8086:125e | Intel      | 82571EB/82571GB Gigabit E... | 5     | e1000e     | 43C0756BA6 |
| 8086:1096 | 8086:3476 | Intel      | 80003ES2LAN Gigabit Ether... | 5     | e1000e     | 2AEA05D635 |
| 8086:10fb | 8086:000c | Intel      | 82599 10 Gigabit Dual Por... | 5     | ixgbe      | AEAD99F55D |
| 14e4:163b | 1028:028d | Broadcom   | NetXtreme II BCM5716 Giga... | 4     | bnx2       | 1A05144C7E |
| 14e4:163b | 1028:02f1 | Broadcom   | NetXtreme II BCM5716 Giga... | 4     | bnx2       | DEE1F70644 |
| 14e4:163b | 1028:04dd | Broadcom   | NetXtreme II BCM5716 Giga... | 4     | bnx2       | D52DB39EEB |
| 14e4:165f | 1028:04f8 | Broadcom   | NetXtreme BCM5720 Gigabit... | 4     | tg3        | 494CD954E9 |
| 14e4:165f | 1028:0639 | Broadco... | NetXtreme BCM5720 Gigabit... | 4     | tg3        | E5766C8331 |
| 14e4:168e | 103c:3382 | Broadcom   | NetXtreme II BCM57810 10 ... | 4     | bnx2x      | 0575B02EDE |
| 8086:1096 | 8086:3484 | Intel      | 80003ES2LAN Gigabit Ether... | 4     | e1000e     | 0A3F6D305B |
| 8086:10bc | 103c:704b | Intel      | 82571EB/82571GB Gigabit E... | 4     | e1000e     | 2B9980B42B |
| 8086:1521 | 103c:337f | Intel      | I350 Gigabit Network Conn... | 4     | igb        | 0B1954F5E9 |
| 8086:1521 | 8086:0002 | Intel      | I350 Gigabit Network Conn... | 4     | igb        | 6D486A7EE9 |
| 8086:1528 | 8086:35a0 | Intel      | Ethernet Controller 10-Gi... | 4     | ixgbe      | FE1E6CFF79 |
| 8086:15ac | 15d9:15ac | Intel      | Ethernet Connection X552 ... | 4     | ixgbe      | 9AF20F3BA9 |
| 8086:15b7 | 8086:0000 | Intel      | Ethernet Connection (2) I... | 4     | e1000e     | 0F1EA2D9DA |
| 8086:15b9 | 1028:0739 | Intel      | Ethernet Connection (3) I... | 4     | e1000e     | 9E01FD5E8C |
| 8086:15b9 | 103c:81c7 | Intel      | Ethernet Connection (3) I... | 4     | e1000e     | 5299B4DA87 |
| 8086:15bb | 15d9:15bb | Intel      | Ethernet Connection (7) I... | 4     | e1000e     | 59C50944A0 |
| 8086:15bb | 8086:0000 | Intel      | Ethernet Connection (7) I... | 4     | e1000e     | B8FFB92409 |
| 8086:37d1 | 103c:81c7 | Intel      | Ethernet Connection X722 ... | 4     | i40e       | 5299B4DA87 |
| 8086:37d2 | 8086:35ce | Intel      | Ethernet Connection X722 ... | 4     | i40e       | 36C4ACAC2D |
| 10ec:8168 | 1019:a94d | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 6AEB74B9F1 |
| 10ec:8168 | 7470:3468 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | AD61EFB931 |
| 14e4:1639 | 1028:02d4 | Broadcom   | NetXtreme II BCM5709 Giga... | 3     | bnx2       | 26B693742E |
| 14e4:1639 | 1028:1f26 | Broadcom   | NetXtreme II BCM5709 Giga... | 3     | bnx2       | AD7D2477F8 |
| 14e4:1639 | 14e4:0907 | Broadcom   | NetXtreme II BCM5709 Giga... | 3     | bnx2       | 0893528A1F |
| 14e4:164c | 1028:01b3 | Broadcom   | NetXtreme II BCM5708 Giga... | 3     | bnx2       | 8571D09FE7 |
| 14e4:1657 | 17aa:400e | Broadcom   | NetXtreme BCM5719 Gigabit... | 3     | tg3        | 3510DD7B10 |
| 14e4:1659 | 1028:01e7 | Broadcom   | NetXtreme BCM5721 Gigabit... | 3     | tg3        | EA66809CE7 |
| 14e4:165a | 1028:02a6 | Broadcom   | NetXtreme BCM5722 Gigabit... | 3     | tg3        | 9C8826C0D2 |
| 14e4:165f | 1028:088e | Broadcom   | NetXtreme BCM5720 Gigabit... | 3     | tg3        | 2A87802C58 |
| 14e4:165f | 1028:08ff | Broadcom   | NetXtreme BCM5720 Gigabit... | 3     | tg3        | A35E7D3EB0 |
| 14e4:165f | 14e4:2003 | Broadcom   | NetXtreme BCM5720 Gigabit... | 3     | tg3        | DF26C4E8C4 |
| 14e4:168a | 1028:1f5d | Broadco... | NetXtreme II BCM57800 1/1... | 3     | bnx2x      | 164BF71243 |
| 14e4:168a | 1028:1f68 | Broadco... | NetXtreme II BCM57800 1/1... | 3     | bnx2x      | 164BF71243 |
| 14e4:168e | 103c:193a | Broadcom   | NetXtreme II BCM57810 10 ... | 3     | bnx2x      | 5F7514110B |
| 14e4:16d8 | 14e4:4161 | Broadco... | BCM57416 NetXtreme-E Dual... | 3     | bnxt_en    | 6CD5E5C480 |
| 8086:105e | 8086:115e | Intel      | 82571EB/82571GB Gigabit E... | 3     | e1000e     | B3C09674CF |
| 8086:1076 | 1028:016d | Intel      | 82541GI Gigabit Ethernet ... | 3     | e1000      | 08919C80E8 |
| 8086:107d | 8086:1084 | Intel      | 82572EI Gigabit Ethernet ... | 3     | e1000e     | 837E4A9092 |
| 8086:150e | 103c:1780 | Intel      | 82580 Gigabit Network Con... | 3     | igb        | 14A3E68490 |
| 8086:150e | 8086:12a2 | Intel      | 82580 Gigabit Network Con... | 3     | igb        | 801EE74858 |
| 8086:1521 | 1028:04cf | Intel      | I350 Gigabit Network Conn... | 3     | igb        | D350652289 |
| 8086:1528 | 8086:5003 | Intel      | Ethernet Controller 10-Gi... | 3     | ixgbe      | 9CC6367D9F |
| 8086:1533 | 8086:0002 | Intel      | I210 Gigabit Network Conn... | 3     | igb        | BE8471A6F1 |
| 8086:1563 | 1028:1fa8 | Intel      | Ethernet Controller 10G X... | 3     | ixgbe      | 1CCB5D67C2 |
| 8086:1563 | 8086:0001 | Intel      | Ethernet Controller 10G X... | 3     | ixgbe      | 4231BB05CE |
| 8086:15b9 | 103c:81c6 | Intel      | Ethernet Connection (3) I... | 3     | e1000e     | 679871CFEC |
| 8086:15b9 | 17aa:1038 | Intel      | Ethernet Connection (3) I... | 3     | e1000e     | 5658A2FB98 |
| 8086:37cc | 103c:81c6 | Intel      | Ethernet Connection X722     | 3     |            | 679871CFEC |
| 8086:37cc | 103c:81c7 | Intel      | Ethernet Connection X722     | 3     |            | ED3C250112 |
| 8086:37d1 | 103c:81c6 | Intel      | Ethernet Connection X722 ... | 3     | i40e       | 679871CFEC |
| 10ec:8168 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8168      | B8D0722935 |
| 14e4:1639 | 1014:03b5 | Broadcom   | NetXtreme II BCM5709 Giga... | 2     | bnx2       | BE2298910B |
| 14e4:1639 | 1028:029b | Broadcom   | NetXtreme II BCM5709 Giga... | 2     | bnx2       | 1F6AFDC077 |
| 14e4:1639 | 1028:02d3 | Broadcom   | NetXtreme II BCM5709 Giga... | 2     | bnx2       | C3EC3FCF73 |
| 14e4:163b | 1028:02a3 | Broadcom   | NetXtreme II BCM5716 Giga... | 2     | bnx2       | 07FABCF50F |
| 14e4:163b | 1028:02a5 | Broadcom   | NetXtreme II BCM5716 Giga... | 2     | bnx2       | F21A3DB016 |
| 14e4:164c | 1014:0342 | Broadcom   | NetXtreme II BCM5708 Giga... | 2     | bnx2       | 3A68279F78 |
| 14e4:164c | 1028:01f0 | Broadcom   | NetXtreme II BCM5708 Giga... | 2     | bnx2       | E36BFCD946 |
| 14e4:165f | 1028:000a | Broadcom   | NetXtreme BCM5720 Gigabit... | 2     | tg3        | FE43558C7A |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2723 | 8086:0084 | Intel      | Wi-Fi 6 AX200                | 5     | iwlwifi    | D3DC168A2A |
| 168c:003e | 168c:3360 | Qualcom... | QCA6174 802.11ac Wireless... | 3     | ath10k_pci | 6AEB74B9F1 |
| 14e4:43a0 | 14e4:0619 | Broadcom   | BCM4360 802.11ac Wireless... | 2     | wl         | CC8DB94EBA |
| 8086:2526 | 8086:0014 | Intel      | Wireless-AC 9260             | 2     | iwlwifi    | 3F6EBB3247 |
| 10ec:8812 | 10ec:8203 | Realtek... | RTL8812AE 802.11ac PCIe W... | 1     | rtl8821ae  | 87E94A007B |
| 10ec:8812 | 10ec:8812 | Realtek... | RTL8812AE 802.11ac PCIe W... | 1     | rtl8821ae  | 5658A2FB98 |
| 14e4:43ba | 106b:0133 | Broadcom   | BCM43602 802.11ac Wireles... | 1     | brcmfmac   | FC1F78ADA0 |
| 168c:0013 | 1186:3a73 | Qualcom... | AR5212/5213/2414 Wireless... | 1     | ath5k      | 8F945E0A15 |
| 168c:0013 | 168c:2051 | Qualcom... | AR5212/5213/2414 Wireless... | 1     | ath5k      | FE3D758C20 |
| 168c:001d | 1113:b203 | Qualcom... | AR2417 Wireless Network A... | 1     | ath5k      | EF95821AFC |
| 168c:001d | 168c:2055 | Qualcom... | AR2417 Wireless Network A... | 1     | ath5k      | 16BEFD9DC3 |
| 168c:0030 | 168c:3112 | Qualcom... | AR93xx Wireless Network A... | 1     | ath9k      | B9AC0D657E |
| 168c:0032 | 168c:3118 | Qualcom... | AR9485 Wireless Network A... | 1     | ath9k      | E70645D3E6 |
| 168c:0034 | 105b:e058 | Qualcom... | AR9462 Wireless Network A... | 1     | ath9k      | 676C3ECA96 |
| 1814:0301 | 1737:0055 | Ralink     | RT2561/RT61 802.11g PCI      | 1     | rt61pci    | 5600070A23 |
| 1814:5392 | 1186:3c06 | Ralink     | RT5392 PCIe Wireless Netw... | 1     | rt2800pci  | E24D0E827B |
| 8086:08b1 | 8086:4470 | Intel      | Wireless 7260                | 1     | iwlwifi    | B8FFB92409 |
| 8086:08b1 | 8086:c070 | Intel      | Wireless 7260                | 1     | iwlwifi    | 026B32269E |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 1     | iwlwifi    | 41249F2E48 |
| 8086:2725 | 8086:0024 | Intel      | Wi-Fi 6 AX210/AX211/AX411... | 1     |            | 8F45F37B98 |
| 8086:a370 | 8086:0034 | Intel      | Cannon Lake PCH CNVi WiFi    | 1     | iwlwifi    | F34EB9D9C6 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1533 | 15d9:1533 | Intel      | I210 Gigabit Network Conn... | 64    | igb        | 6A333A499D |
| 8086:1521 | 15d9:1521 | Intel      | I350 Gigabit Network Conn... | 62    | igb        | 10F1608197 |
| 8086:10d3 | 15d9:10d3 | Intel      | 82574L Gigabit Network Co... | 22    | e1000e     | 9CC6367D9F |
| 8086:10c9 | 15d9:10c9 | Intel      | 82576 Gigabit Network Con... | 18    | igb        | D3DC168A2A |
| 8086:10d3 | 1043:8369 | Intel      | 82574L Gigabit Network Co... | 18    | e1000e     | 874EAAB0BB |
| 8086:1533 | 1043:8557 | Intel      | I210 Gigabit Network Conn... | 18    | igb        | FEC09C0BAC |
| 8086:1533 | ffff:0000 | Intel      | I210 Gigabit Network Conn... | 10    | igb        | 14C76E0C83 |
| 8086:1521 | 1028:1f60 | Intel      | I350 Gigabit Network Conn... | 9     | igb        | DECC1F46BA |
| 8086:1533 | 1028:0619 | Intel      | I210 Gigabit Network Conn... | 8     | igb        | C7D795E2A5 |
| 1077:8020 | 103c:3733 | QLogic     | cLOM8214 1/10GbE Controller  | 7     | qlcnic     | C56840DF98 |
| 8086:10a7 | 8086:34dc | Intel      | 82575EB Gigabit Network C... | 7     | igb        | 451F363726 |
| 8086:10c9 | 103c:323f | Intel      | 82576 Gigabit Network Con... | 7     | igb        | 28B04C3004 |
| 8086:10c9 | 15d9:0100 | Intel      | 82576 Gigabit Network Con... | 7     | igb        | C83DC07B7C |
| 8086:10c9 | 15d9:ab11 | Intel      | 82576 Gigabit Network Con... | 7     | igb        | D5563E325C |
| 8086:10bd | 8086:34d0 | Intel      | 82566DM-2 Gigabit Network... | 6     | e1000e     | F0473D3564 |
| 8086:10d3 | 15d9:0000 | Intel      | 82574L Gigabit Network Co... | 6     | e1000e     | 47401D66CE |
| 8086:10d3 | 8086:0000 | Intel      | 82574L Gigabit Network Co... | 6     | e1000e     | 6B7A9D9BDB |
| 8086:10a7 | 8086:34e2 | Intel      | 82575EB Gigabit Network C... | 5     | igb        | FDCE629C37 |
| 8086:10cc | 8086:34da | Intel      | 82567LM-2 Gigabit Network... | 5     | e1000e     | F9F8DD79F5 |
| 8086:10d3 | 8086:34da | Intel      | 82574L Gigabit Network Co... | 5     | e1000e     | F9F8DD79F5 |
| 8086:10fb | 15d9:0611 | Intel      | 82599 10 Gigabit Dual Por... | 5     | ixgbe      | AFAB4598A7 |
| 8086:1521 | 1458:0000 | Intel      | I350 Gigabit Network Conn... | 5     | igb        | 96079334BD |
| 8086:1521 | 8086:1521 | Intel      | I350 Gigabit Network Conn... | 5     | igb        | 1A5CF39F4F |
| 8086:10c9 | 15d9:0400 | Intel      | 82576 Gigabit Network Con... | 4     | igb        | AD4ABE60CD |
| 8086:10c9 | 15d9:0600 | Intel      | 82576 Gigabit Network Con... | 4     | igb        | ACA2A2FFDF |
| 8086:10c9 | 15d9:060f | Intel      | 82576 Gigabit Network Con... | 4     | igb        | CF99AAD395 |
| 8086:10d3 | 1014:03bd | Intel      | 82574L Gigabit Network Co... | 4     | e1000e     | 882EA8E25E |
| 8086:10d3 | 8086:3578 | Intel      | 82574L Gigabit Network Co... | 4     | e1000e     | 57162CA72C |
| 8086:1502 | 8086:3578 | Intel      | 82579LM Gigabit Network C... | 4     | e1000e     | 57162CA72C |
| 8086:1521 | 15d9:0656 | Intel      | I350 Gigabit Network Conn... | 4     | igb        | 7AD1F5EB4E |
| 8086:1521 | 8086:357e | Intel      | I350 Gigabit Network Conn... | 4     | igb        | 0FADD1EBE3 |
| 14e4:164f | 14e4:1113 | Broadcom   | NetXtreme II BCM57711 10-... | 3     | bnx2x      | FDC516788A |
| 4040:0100 | 103c:705a | NetXen ... | NX3031 Multifunction 1/10... | 3     | netxen_nic | A2261C146D |
| 8086:10a7 | 1734:1128 | Intel      | 82575EB Gigabit Network C... | 3     | igb        | 43C0756BA6 |
| 8086:10d3 | 1734:1158 | Intel      | 82574L Gigabit Network Co... | 3     | e1000e     | 4874F3ABB6 |
| 8086:10d3 | 1734:1192 | Intel      | 82574L Gigabit Network Co... | 3     | e1000e     | E6D89DC95B |
| 8086:10e8 | 8086:a02c | Intel      | 82576 Gigabit Network Con... | 3     | igb        | A4C832AB44 |
| 8086:1502 | 15d9:0623 | Intel      | 82579LM Gigabit Network C... | 3     | e1000e     | 47401D66CE |
| 8086:1502 | 1734:11b7 | Intel      | 82579LM Gigabit Network C... | 3     | e1000e     | E6D89DC95B |
| 8086:1521 | 1028:1faa | Intel      | I350 Gigabit Network Conn... | 3     | igb        | 1CCB5D67C2 |
| 8086:1521 | 15d9:0652 | Intel      | I350 Gigabit Network Conn... | 3     | igb        | F1BF9D35EF |
| 8086:1521 | 15d9:0875 | Intel      | I350 Gigabit Network Conn... | 3     | igb        | 35739B35C9 |
| 8086:1521 | ffff:0000 | Intel      | I350 Gigabit Network Conn... | 3     | igb        | 201AA7046E |
| 8086:1533 | 17aa:1038 | Intel      | I210 Gigabit Network Conn... | 3     | igb        | 5658A2FB98 |
| 8086:1533 | 8086:35b4 | Intel      | I210 Gigabit Network Conn... | 3     | igb        | 20BB0A8951 |
| 10de:0373 | 1462:cb84 | Nvidia     | MCP55 Ethernet               | 2     | forcedeth  | B8300AFB35 |
| 15b3:1007 | 15b3:000c | Mellano... | MT27520 Family [ConnectX-... | 2     | mlx4_core  | 3CA7825025 |
| 15b3:1013 | 15b3:0014 | Mellano... | MT27700 Family [ConnectX-4]  | 2     | mlx5_core  | 2903921AEB |
| 15b3:1013 | 15b3:0039 | Mellano... | MT27700 Family [ConnectX-4]  | 2     | mlx5_core  | FDFCFF5120 |
| 15b3:673c | 15b3:0022 | Mellano... | MT25408A0-FCC-QI ConnectX... | 2     | mlx4_core  | 75223203BD |
| 15b3:6750 | 15b3:0015 | Mellano... | MT26448 [ConnectX EN 10Gi... | 2     | mlx4_core  | AFDF449993 |
| 15b3:6750 | 15b3:0021 | Mellano... | MT26448 [ConnectX EN 10Gi... | 2     | mlx4_core  | 47401D66CE |
| 8086:10a7 | 8086:34de | Intel      | 82575EB Gigabit Network C... | 2     | igb        | 3AB9D48A33 |
| 8086:10c9 | 10f1:7012 | Intel      | 82576 Gigabit Network Con... | 2     | igb        | 368A801F1A |
| 8086:10c9 | 1170:004a | Intel      | 82576 Gigabit Network Con... | 2     | igb        | 9D511D1A0B |
| 8086:10c9 | 8086:a04c | Intel      | 82576 Gigabit Network Con... | 2     | igb        | 614C766EEC |
| 8086:10d3 | 8086:34ec | Intel      | 82574L Gigabit Network Co... | 2     | e1000e     | 78786D13E2 |
| 8086:10d3 | 8086:a01f | Intel      | 82574L Gigabit Network Co... | 2     | e1000e     | 04144B327A |
| 8086:10d6 | 8086:145a | Intel      | 82575GB Gigabit Network C... | 2     | igb        | C83DC07B7C |
| 8086:10ef | 8086:34ec | Intel      | 82578DM Gigabit Network C... | 2     | e1000e     | 78786D13E2 |
| 8086:1521 | 0050:0019 | Intel      | I350 Gigabit Network Conn... | 2     | igb        | 58A63B2A93 |
| 8086:1521 | 1028:1f73 | Intel      | I350 Gigabit Network Conn... | 2     | igb        | C7B39E92CA |
| 8086:1521 | 8086:3594 | Intel      | I350 Gigabit Network Conn... | 2     | igb        | E70645D3E6 |
| 8086:1533 | 1458:0000 | Intel      | I210 Gigabit Network Conn... | 2     | igb        | 2F69A2F89C |
| 8086:1533 | 8086:35bd | Intel      | I210 Gigabit Network Conn... | 2     | igb        | 98C12554CB |
| 1077:7322 | 1077:7322 | QLogic     | IBA7322 QDR InfiniBand HCA   | 1     | ib_qib     | BA0F3C3B41 |
| 10b7:9200 | 10b7:1000 | 3Com       | 3c905C-TX/TX-M [Tornado]     | 1     | 3c59x      | 0B5D843F10 |
| 10de:0057 | 10f1:2891 | Nvidia     | CK804 Ethernet Controller    | 1     | forcedeth  | 64251B3F2A |
| 10de:0057 | 10f1:2895 | Nvidia     | CK804 Ethernet Controller    | 1     | forcedeth  | 768571B831 |
| 10de:0373 | 108e:534b | Nvidia     | MCP55 Ethernet               | 1     |            | E54A36A0C4 |
| 10de:0373 | 108e:534d | Nvidia     | MCP55 Ethernet               | 1     | forcedeth  | 1F35F79302 |
| 10de:0373 | 1462:2800 | Nvidia     | MCP55 Ethernet               | 1     | forcedeth  | 933EED177A |
| 10df:0720 | 10df:e863 | Emulex     | OneConnect NIC (Skyhawk)     | 1     | be2net     | 64918C950D |
| 1425:0031 | 1425:0001 | Chelsio... | T320 10GbE Dual Port Adapter | 1     | cxgb3      | C43FD89A0B |
| 14e4:164f | 1028:02d3 | Broadcom   | NetXtreme II BCM57711 10-... | 1     | bnx2x      | F33CE0F316 |
| 15b3:1003 | 1043:8538 | Mellano... | MT27500 Family [ConnectX-3]  | 1     | mlx4_core  | 874EAAB0BB |
| 15b3:1003 | 15b3:0050 | Mellano... | MT27500 Family [ConnectX-3]  | 1     | mlx4_core  | 77A5A8BF12 |
| 15b3:1003 | 15b3:0123 | Mellano... | MT27500 Family [ConnectX-3]  | 1     | mlx4_core  | D15B8F8758 |
| 15b3:1013 | 15b3:0013 | Mellano... | MT27700 Family [ConnectX-4]  | 1     | mlx5_core  | 36C4ACAC2D |
| 15b3:1015 | 15b3:0003 | Mellano... | MT27710 Family [ConnectX-... | 1     | mlx5_core  | 64918C950D |
| 15b3:1015 | 15d9:094c | Mellano... | MT27710 Family [ConnectX-... | 1     | mlx5_core  | 57460AA45B |
| 15b3:1017 | 15b3:0007 | Mellano... | MT27800 Family [ConnectX-5]  | 1     | mlx5_core  | F823B40D84 |
| 15b3:1017 | 15b3:0020 | Mellano... | MT27800 Family [ConnectX-5]  | 1     | mlx5_core  | 9CF9DCEEE9 |
| 15b3:673c | 15b3:0033 | Mellano... | MT25408A0-FCC-QI ConnectX... | 1     | mlx4_core  | 179B0500B3 |
| 15b3:673c | 15b3:673c | Mellano... | MT25408A0-FCC-QI ConnectX... | 1     | mlx4_core  | 0138C33179 |
| 19a2:0710 | 103c:337b | Emulex     | OneConnect 10Gb NIC (be3)    | 1     | be2net     | C2075DC2CE |
| 19a2:0710 | 10df:e70a | Emulex     | OneConnect 10Gb NIC (be3)    | 1     | be2net     | D7CBC31CEE |
| 19a2:0710 | 10df:e731 | Emulex     | OneConnect 10Gb NIC (be3)    | 1     | be2net     | 7C109612B9 |
| 19e5:0206 | 19e5:d138 | Huawei ... | Hi1822 Family (2*25GE)       | 1     |            | F548D0A0A9 |
| 8086:0436 | 8086:0000 | Intel      | DH8900CC Null Device         | 1     |            | 14C76E0C83 |
| 8086:10bd | 8086:0000 | Intel      | 82566DM-2 Gigabit Network... | 1     | e1000e     | ECA989A5BF |
| 8086:10d3 | 10f1:7012 | Intel      | 82574L Gigabit Network Co... | 1     | e1000e     | 3D4DABE8D3 |
| 8086:10e8 | 8086:a02b | Intel      | 82576 Gigabit Network Con... | 1     | igb        | 3A05F2F446 |
| 8086:1502 | 8086:0000 | Intel      | 82579LM Gigabit Network C... | 1     | e1000e     | 0AC54E7FB4 |
| 8086:1521 |           | Intel      | I350 Gigabit Network Conn... | 1     | igb        | EDE05678EF |
| 8086:1521 | 1043:84ec | Intel      | I350 Gigabit Network Conn... | 1     | igb        | 996F55BB36 |
| 8086:1521 | 15d9:0912 | Intel      | I350 Gigabit Network Conn... | 1     | igb        | 1687263A9E |
| 8086:1521 | 1734:11ce | Intel      | I350 Gigabit Network Conn... | 1     | igb        | B0EE52BCF3 |
| 8086:1521 | 8086:3582 | Intel      | I350 Gigabit Network Conn... | 1     | igb        | 9F6D925B73 |
| 8086:1521 | 8086:358c | Intel      | I350 Gigabit Network Conn... | 1     | igb        | D15B8F8758 |

### Network and computing encryption device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 19e5:a255 |           | Huawei ... | HiSilicon SEC Engine         | 1     |            | 63BDABB5A4 |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1485 | 1022:1485 | AMD        | Starship/Matisse Reserved... | 8     |            | FEE94D715D |
| 1022:148a | 1022:148a | AMD        | Starship/Matisse PCIe Dum... | 8     |            | FEE94D715D |
| 1022:1485 | 1458:1000 | AMD        | Starship/Matisse Reserved... | 5     |            | 96079334BD |
| 1022:148a | 1458:1000 | AMD        | Starship/Matisse PCIe Dum... | 5     |            | 96079334BD |
| 1022:1455 | 1022:1455 | AMD        | Zeppelin/Renoir PCIe Dumm... | 3     |            | 10F1608197 |
| 1022:145a | 1022:145a | AMD        | Zeppelin/Raven/Raven2 PCI... | 3     |            | 10F1608197 |
| 1022:1485 | 1028:08ff | AMD        | Starship/Matisse Reserved... | 3     |            | A35E7D3EB0 |
| 1022:148a | 1028:08ff | AMD        | Starship/Matisse PCIe Dum... | 3     |            | A35E7D3EB0 |
| 8086:a126 |           | Intel      | 100 Series/C230 Series Ch... | 3     | intel_t... | 0F1EA2D9DA |
| 1022:1455 | 1458:1000 | AMD        | Zeppelin/Renoir PCIe Dumm... | 2     |            | 6D486A7EE9 |
| 1022:145a | 1458:1000 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 6D486A7EE9 |
| 8086:3456 |           | Intel      | Non-Essential Instrumenta... | 2     |            | AEAD99F55D |
| 1022:1455 | 1028:07f9 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 8F7FF50C55 |
| 1022:145a | 1028:07f9 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 8F7FF50C55 |
| 1022:1485 | 1028:08fc | AMD        | Starship/Matisse Reserved... | 1     |            | 9320E12A9A |
| 1022:1485 | 1028:08fd | AMD        | Starship/Matisse Reserved... | 1     |            | F3CBAC183E |
| 1022:148a | 1028:08fc | AMD        | Starship/Matisse PCIe Dum... | 1     |            | 9320E12A9A |
| 1022:148a | 1028:08fd | AMD        | Starship/Matisse PCIe Dum... | 1     |            | F3CBAC183E |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a135 | 15d9:089a | Intel      | 100 Series/C230 Series Ch... | 3     | intel_i... | 89CC93BB0F |
| 1415:9510 | 131f:0000 | Oxford ... | OX16PCI954 (Quad 16950 UA... | 1     |            | 80DC2F8936 |
| 1b4b:1475 |           | Marvell... |                              | 1     |            | 7F5766D5DA |
| 1b4b:9235 |           | Marvell... | 88SE9235 PCIe 2.0 x2 4-po... | 1     |            | 7F5766D5DA |
| 1b94:c156 | 1b94:c156 | Signate... |                              | 1     |            | B3C09674CF |
| 8086:1533 |           | Intel      | I210 Gigabit Network Conn... | 1     |            | 7F5766D5DA |
| 8086:6f04 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | 7F5766D5DA |
| 8086:6f06 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | 7F5766D5DA |
| 8086:6f08 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | 7F5766D5DA |
| 8086:6f0a |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | 7F5766D5DA |
| 8086:8c22 |           | Intel      | 8 Series/C220 Series Chip... | 1     |            | 7F5766D5DA |
| 8086:8c54 |           | Intel      | C224 Series Chipset Famil... | 1     |            | 7F5766D5DA |
| 8086:a135 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 1     |            | BB8832ACBD |
| 8086:a135 | 15d9:0885 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_i... | 50169A0FFB |

### Parallel controller (ieee1284) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 9710:9865 | a000:2000 | MosChip... | PCI 9865 Multi-I/O Contro... | 1     | parport_pc | 715B40D8B6 |

### Performance counters (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:204c | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 105   | skx_uncore | E757687F86 |
| 8086:204d | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 105   | skx_uncore | E757687F86 |
| 8086:2015 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 104   |            | E757687F86 |
| 8086:2058 | 8086:0000 | Intel      | Sky Lake-E KTI 0             | 101   | skx_uncore | E757687F86 |
| 8086:2088 | 8086:0000 | Intel      | Sky Lake-E DDRIO Registers   | 49    | skx_uncore | C8F90792EC |
| 8086:2f30 | 8086:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    | hswep_u... | 6A333A499D |
| 8086:2f34 | 8086:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    | hswep_u... | 6A333A499D |
| 8086:2f36 | 8086:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    | hswep_u... | 6A333A499D |
| 8086:2f37 | 8086:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    | hswep_u... | 6A333A499D |
| 8086:2f7d | 8086:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:3c43 | 103c:18a8 | Intel      | Xeon E5/Core i7 Ring to P... | 26    | snbep_u... | 5BFD235851 |
| 8086:3c44 | 103c:18a8 | Intel      | Xeon E5/Core i7 Ring to Q... | 26    | snbep_u... | 5BFD235851 |
| 8086:3c46 | 103c:18a8 | Intel      | Xeon E5/Core i7 Processor... | 26    | snbep_u... | 5BFD235851 |
| 8086:3ce6 | 103c:18a8 | Intel      | Xeon E5/Core i7 QuickPath... | 26    |            | 5BFD235851 |
| 8086:2f32 | 8086:2f32 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 23    | hswep_u... | C7B39E92CA |
| 8086:2f33 | 8086:2f33 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 22    | hswep_u... | C7B39E92CA |
| 8086:6f30 | 8086:6f30 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 22    | bdx_uncore | DF26C4E8C4 |
| 8086:6f34 | 8086:6f34 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 22    | bdx_uncore | DF26C4E8C4 |
| 8086:6f36 | 8086:6f36 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 22    | bdx_uncore | DF26C4E8C4 |
| 8086:6f37 | 8086:6f37 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 22    | bdx_uncore | DF26C4E8C4 |
| 8086:6f7d | 8086:6f7d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 22    |            | DF26C4E8C4 |
| 8086:2058 |           | Intel      | Sky Lake-E KTI 0             | 17    | skx_uncore | AD903545CE |
| 8086:6f30 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 17    | bdx_uncore | AAEEE85BE7 |
| 8086:6f34 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 17    | bdx_uncore | AAEEE85BE7 |
| 8086:6f36 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 17    | bdx_uncore | AAEEE85BE7 |
| 8086:6f37 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 17    | bdx_uncore | AAEEE85BE7 |
| 8086:6f7d | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 17    |            | AAEEE85BE7 |
| 8086:6f32 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | AAEEE85BE7 |
| 8086:6f33 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | AAEEE85BE7 |
| 8086:0e30 | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 12    | ivbep_u... | DD93F62FFC |
| 8086:0e34 | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 12    | ivbep_u... | DD93F62FFC |
| 8086:0e36 | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 12    | ivbep_u... | DD93F62FFC |
| 8086:2f38 | 8086:2f38 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 12    | hswep_u... | F90168C69D |
| 8086:0e30 | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    | ivbep_u... | 7B579629BB |
| 8086:0e34 | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    | ivbep_u... | 7B579629BB |
| 8086:0e36 | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    | ivbep_u... | 7B579629BB |
| 8086:3c43 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to P... | 9     | snbep_u... | 1A5CF39F4F |
| 8086:3c44 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to Q... | 9     | snbep_u... | 1A5CF39F4F |
| 8086:3ce6 | 8086:0000 | Intel      | Xeon E5/Core i7 QuickPath... | 9     |            | 1A5CF39F4F |
| 8086:3c41 | 8086:0000 | Intel      | Sandy Bridge QPI Port 0 P... | 8     | snbep_u... | 1A5CF39F4F |
| 8086:3c42 | 8086:0000 | Intel      | Sandy Bridge QPI Port 1 P... | 8     | snbep_u... | 1A5CF39F4F |
| 8086:3c43 | 1043:84f0 | Intel      | Xeon E5/Core i7 Ring to P... | 8     | snbep_u... | 874EAAB0BB |
| 8086:3c44 | 1043:84f0 | Intel      | Xeon E5/Core i7 Ring to Q... | 8     | snbep_u... | 874EAAB0BB |
| 8086:3c46 |           | Intel      | Xeon E5/Core i7 Processor... | 8     | snbep_u... | 1A5CF39F4F |
| 8086:3c46 | 1043:84f0 | Intel      | Xeon E5/Core i7 Processor... | 8     | snbep_u... | 874EAAB0BB |
| 8086:3ce6 | 1043:84f0 | Intel      | Xeon E5/Core i7 QuickPath... | 8     |            | 874EAAB0BB |
| 8086:6f32 | 8086:6f32 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 8     | bdx_uncore | E5766C8331 |
| 8086:6f33 | 8086:6f33 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 8     | bdx_uncore | E5766C8331 |
| 8086:2015 | 1590:00ea | Intel      | Sky Lake-E Ubox Registers    | 7     |            | 7AB4F05613 |
| 8086:2015 | 17aa:7808 | Intel      | Sky Lake-E Ubox Registers    | 7     |            | CEE7ED2CE9 |
| 8086:204c | 1590:00ea | Intel      | Sky Lake-E M3KTI Registers   | 7     | skx_uncore | 7AB4F05613 |
| 8086:204c | 17aa:7808 | Intel      | Sky Lake-E M3KTI Registers   | 7     | skx_uncore | CEE7ED2CE9 |
| 8086:204d | 1590:00ea | Intel      | Sky Lake-E M3KTI Registers   | 7     | skx_uncore | 7AB4F05613 |
| 8086:204d | 17aa:7808 | Intel      | Sky Lake-E M3KTI Registers   | 7     | skx_uncore | CEE7ED2CE9 |
| 8086:2058 | 1590:00ea | Intel      | Sky Lake-E KTI 0             | 7     | skx_uncore | 7AB4F05613 |
| 8086:2058 | 17aa:7808 | Intel      | Sky Lake-E KTI 0             | 7     | skx_uncore | CEE7ED2CE9 |
| 8086:2088 | 17aa:7808 | Intel      | Sky Lake-E DDRIO Registers   | 7     | skx_uncore | CEE7ED2CE9 |
| 8086:3c43 | 1028:048c | Intel      | Xeon E5/Core i7 Ring to P... | 7     | snbep_u... | FBDF83F7FF |
| 8086:3c43 | 1028:04fa | Intel      | Xeon E5/Core i7 Ring to P... | 7     | snbep_u... | C9C876F0E7 |
| 8086:3c44 | 1028:048c | Intel      | Xeon E5/Core i7 Ring to Q... | 7     | snbep_u... | FBDF83F7FF |
| 8086:3c44 | 1028:04fa | Intel      | Xeon E5/Core i7 Ring to Q... | 7     | snbep_u... | C9C876F0E7 |
| 8086:3c46 | 1028:048c | Intel      | Xeon E5/Core i7 Processor... | 7     | snbep_u... | FBDF83F7FF |
| 8086:3c46 | 1028:04fa | Intel      | Xeon E5/Core i7 Processor... | 7     | snbep_u... | C9C876F0E7 |
| 8086:3ce6 | 1028:048c | Intel      | Xeon E5/Core i7 QuickPath... | 7     |            | FBDF83F7FF |
| 8086:3ce6 | 1028:04fa | Intel      | Xeon E5/Core i7 QuickPath... | 7     |            | C9C876F0E7 |
| 8086:0e30 | 1043:84f0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 6     | ivbep_u... | A4C832AB44 |
| 8086:0e34 | 1043:84f0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 6     | ivbep_u... | A4C832AB44 |
| 8086:0e36 | 1043:84f0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 6     | ivbep_u... | A4C832AB44 |
| 8086:2f30 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 6     | hswep_u... | CFFFE6AA63 |
| 8086:2f34 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 6     | hswep_u... | CFFFE6AA63 |
| 8086:2f36 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 6     | hswep_u... | CFFFE6AA63 |
| 8086:2f37 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 6     | hswep_u... | CFFFE6AA63 |
| 8086:2f7d | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 6     |            | CFFFE6AA63 |
| 8086:0e30 | 1028:04f8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     | ivbep_u... | 494CD954E9 |
| 8086:0e30 | 8086:35a0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     | ivbep_u... | FE1E6CFF79 |
| 8086:0e34 | 1028:04f8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     | ivbep_u... | 494CD954E9 |
| 8086:0e34 | 8086:35a0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     | ivbep_u... | FE1E6CFF79 |
| 8086:0e36 | 1028:04f8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     | ivbep_u... | 494CD954E9 |
| 8086:0e36 | 8086:35a0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     | ivbep_u... | FE1E6CFF79 |
| 8086:0e37 | 8086:35a0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     | ivbep_u... | FE1E6CFF79 |
| 8086:2015 | 1849:2015 | Intel      | Sky Lake-E Ubox Registers    | 4     |            | 2244EB7809 |
| 8086:2015 | 8086:35ce | Intel      | Sky Lake-E Ubox Registers    | 4     |            | 36C4ACAC2D |
| 8086:204c | 1849:204c | Intel      | Sky Lake-E M3KTI Registers   | 4     |            | 2244EB7809 |
| 8086:204d | 1849:204d | Intel      | Sky Lake-E M3KTI Registers   | 4     | skx_uncore | 2244EB7809 |
| 8086:2058 | 1849:2058 | Intel      | Sky Lake-E KTI 0             | 4     | skx_uncore | 2244EB7809 |
| 8086:2f30 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | FD108DE325 |
| 8086:2f34 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | FD108DE325 |
| 8086:2f36 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | FD108DE325 |
| 8086:2f37 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | FD108DE325 |
| 8086:2f7d | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | FD108DE325 |
| 8086:3c41 | 103c:18a8 | Intel      | Sandy Bridge QPI Port 0 P... | 4     | snbep_u... | 32951A000F |
| 8086:3c42 | 103c:18a8 | Intel      | Sandy Bridge QPI Port 1 P... | 4     | snbep_u... | 32951A000F |
| 8086:3c43 | 1028:04ce | Intel      | Xeon E5/Core i7 Ring to P... | 4     | snbep_u... | 9977E2B5C3 |
| 8086:3c44 | 1028:04ce | Intel      | Xeon E5/Core i7 Ring to Q... | 4     | snbep_u... | 9977E2B5C3 |
| 8086:3c46 | 1028:04ce | Intel      | Xeon E5/Core i7 Processor... | 4     | snbep_u... | 9977E2B5C3 |
| 8086:3ce6 | 1028:04ce | Intel      | Xeon E5/Core i7 QuickPath... | 4     |            | 9977E2B5C3 |
| 8086:6f30 | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     | bdx_uncore | 23F12250E5 |
| 8086:6f34 | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     | bdx_uncore | 23F12250E5 |
| 8086:6f36 | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     | bdx_uncore | 23F12250E5 |
| 8086:6f37 | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     | bdx_uncore | 23F12250E5 |

### Pic (8259) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:342e |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 126   | i7core_... | BDE0BE6A50 |
| 8086:3422 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 124   |            | BDE0BE6A50 |
| 8086:3423 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 124   |            | BDE0BE6A50 |
| 8086:3438 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 67    | i5500_temp | BDE0BE6A50 |
| 8086:3422 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 40    |            | A9C87C6C9C |
| 8086:3423 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 40    |            | A9C87C6C9C |
| 8086:342e | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 40    | i7core_... | A9C87C6C9C |
| 8086:3425 |           | Intel      | 7500/5520/5500/X58 Physic... | 10    |            | B4A013EED4 |
| 8086:3426 |           | Intel      | 7500/5520/5500/X58 Routin... | 10    |            | B4A013EED4 |
| 8086:3427 |           | Intel      | 7500/5520/5500 Physical a... | 10    |            | B4A013EED4 |
| 8086:3428 |           | Intel      | 7500/5520/5500 Routing & ... | 10    |            | B4A013EED4 |
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
| 8086:3422 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | 8681056F1F |
| 8086:3422 | 0086:0000 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | CBBE408AAC |
| 8086:3423 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | 8681056F1F |
| 8086:3423 | 0086:0000 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | CBBE408AAC |
| 8086:3425 | 0043:0063 | Intel      | 7500/5520/5500/X58 Physic... | 1     |            | 8681056F1F |
| 8086:3425 | 0086:0000 | Intel      | 7500/5520/5500/X58 Physic... | 1     |            | CBBE408AAC |
| 8086:3426 | 0043:0063 | Intel      | 7500/5520/5500/X58 Routin... | 1     |            | 8681056F1F |
| 8086:3426 | 0086:0000 | Intel      | 7500/5520/5500/X58 Routin... | 1     |            | CBBE408AAC |
| 8086:3427 | 0043:0063 | Intel      | 7500/5520/5500 Physical a... | 1     |            | 8681056F1F |
| 8086:3427 | 0086:0000 | Intel      | 7500/5520/5500 Physical a... | 1     |            | CBBE408AAC |
| 8086:3428 | 0043:0063 | Intel      | 7500/5520/5500 Routing & ... | 1     |            | 8681056F1F |
| 8086:3428 | 0086:0000 | Intel      | 7500/5520/5500 Routing & ... | 1     |            | CBBE408AAC |
| 8086:342e | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     | i7core_... | 8681056F1F |
| 8086:342e | 0086:0000 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     | i7core_... | CBBE408AAC |
| 8086:3438 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     | i5500_temp | 8681056F1F |
| 8086:3438 | 0086:0000 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     | i5500_temp | CBBE408AAC |

### Pic (io(x)-apic) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2026 | 8086:2026 | Intel      | Sky Lake-E IOAPIC            | 100   |            | E757687F86 |
| 8086:2036 | 8086:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 100   |            | E757687F86 |
| 8086:342d |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 56    |            | BDE0BE6A50 |
| 8086:3c2c | 103c:18a8 | Intel      | Xeon E5/Core i7 I/O APIC     | 30    |            | 5BFD235851 |
| 8086:2f2c | 8086:0000 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 27    |            | C7B39E92CA |
| 8086:6f2c | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 17    |            | AAEEE85BE7 |
| 8086:0e2c | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 12    |            | DD93F62FFC |
| 8086:0e2c | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    |            | 7B579629BB |
| 8086:6f2c | 8086:0000 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 11    |            | DF26C4E8C4 |
| 8086:2f2c | 15d9:0857 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 8     |            | 6A333A499D |
| 8086:3c2c | 1043:84f0 | Intel      | Xeon E5/Core i7 I/O APIC     | 8     |            | 874EAAB0BB |
| 8086:2026 | 1590:18a9 | Intel      | Sky Lake-E IOAPIC            | 7     |            | 7AB4F05613 |
| 8086:2026 | 17aa:7808 | Intel      | Sky Lake-E IOAPIC            | 7     |            | CEE7ED2CE9 |
| 8086:2026 | 8086:0000 | Intel      | Sky Lake-E IOAPIC            | 7     |            | 679871CFEC |
| 8086:2036 | 1590:18a9 | Intel      | Sky Lake-E IOxAPIC Config... | 7     |            | 7AB4F05613 |
| 8086:2036 | 17aa:7808 | Intel      | Sky Lake-E IOxAPIC Config... | 7     |            | CEE7ED2CE9 |
| 8086:2036 | 8086:0000 | Intel      | Sky Lake-E IOxAPIC Config... | 7     |            | 679871CFEC |
| 8086:342d | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     |            | 451F363726 |
| 8086:342f | 0086:00dc | Intel      | 7500/5520/5500/X58 Truste... | 7     |            | 451F363726 |
| 8086:0e2c | 1043:84f0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 6     |            | A4C832AB44 |
| 8086:2f2c | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 6     |            | CFFFE6AA63 |
| 8086:342f |           | Intel      | 7500/5520/5500/X58 Truste... | 6     |            | B4A013EED4 |
| 8086:342f | 0034:0027 | Intel      | 7500/5520/5500/X58 Truste... | 6     |            | 43C0756BA6 |
| 8086:342d | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 5     |            | F9F8DD79F5 |
| 8086:342d | 0086:00e2 | Intel      | 7500/5520/5500/X58 I/O Hu... | 5     |            | FDCE629C37 |
| 8086:342f | 0086:00da | Intel      | 7500/5520/5500/X58 Truste... | 5     |            | F9F8DD79F5 |
| 8086:342f | 0086:00e2 | Intel      | 7500/5520/5500/X58 Truste... | 5     |            | FDCE629C37 |
| 8086:0e2c | 8086:35a0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     |            | FE1E6CFF79 |
| 8086:2026 | 1849:2026 | Intel      | Sky Lake-E IOAPIC            | 4     |            | 2244EB7809 |
| 8086:2026 | 8086:35ce | Intel      | Sky Lake-E IOAPIC            | 4     |            | 36C4ACAC2D |
| 8086:2036 | 1849:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 4     |            | 2244EB7809 |
| 8086:2f2c | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | FD108DE325 |
| 8086:6f2c | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     |            | 23F12250E5 |
| 8086:0e2c | 15d9:062a | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     |            | 47401D66CE |
| 8086:0e2c | 8086:0e2c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     |            | E0EF143493 |
| 8086:2026 | 17aa:1038 | Intel      | Sky Lake-E IOAPIC            | 3     |            | 5658A2FB98 |
| 8086:2036 | 17aa:1038 | Intel      | Sky Lake-E IOxAPIC Config... | 3     |            | 5658A2FB98 |
| 8086:2036 | 8086:35ce | Intel      | Sky Lake-E IOxAPIC Config... | 3     |            | 36C4ACAC2D |
| 8086:3c2c | 8086:357e | Intel      | Xeon E5/Core i7 I/O APIC     | 3     |            | 0FADD1EBE3 |
| 8086:0326 |           | Intel      | 6700/6702PXH I/OxAPIC Int... | 2     |            | 535E5F1D58 |
| 8086:0e2c | 1170:0054 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | 1B5977B024 |
| 8086:0e2c | 15d9:0626 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | 00FDD71981 |
| 8086:0e2c | 15d9:062b | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | FD24B5D375 |
| 8086:2026 | 17aa:7800 | Intel      | Sky Lake-E IOAPIC            | 2     |            | 928EE22E71 |
| 8086:2036 | 17aa:7800 | Intel      | Sky Lake-E IOxAPIC Config... | 2     |            | 928EE22E71 |
| 8086:2f2c | 15d9:0860 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     |            | CC00646768 |
| 8086:342d | 0086:00de | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     |            | 3AB9D48A33 |
| 8086:342f | 0086:00de | Intel      | 7500/5520/5500/X58 Truste... | 2     |            | 3AB9D48A33 |
| 8086:3c2c | 15d9:0702 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | 4DC142D672 |
| 8086:3c2c | 8086:3594 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | E70645D3E6 |
| 8086:6f2c | 1458:1000 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 0EA40336C5 |
| 8086:6f2c | 15d9:0824 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 6C96E4A591 |
| 8086:6f2c | 15d9:0834 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | FA4BECDE8B |
| 8086:6f2c | 1d49:0a00 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 3510DD7B10 |
| 8086:6f2c | 8086:6f2c | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 2903921AEB |
| 8086:0326 | 103c:3208 | Intel      | 6700/6702PXH I/OxAPIC Int... | 1     |            | 2C877CF870 |
| 8086:0326 | 8086:3439 | Intel      | 6700/6702PXH I/OxAPIC Int... | 1     |            | 0F21E859FA |
| 8086:0327 |           | Intel      | 6700PXH I/OxAPIC Interrup... | 1     |            | 535E5F1D58 |
| 8086:0327 | 103c:3208 | Intel      | 6700PXH I/OxAPIC Interrup... | 1     |            | 2C877CF870 |
| 8086:0327 | 8086:3439 | Intel      | 6700PXH I/OxAPIC Interrup... | 1     |            | 0F21E859FA |
| 8086:0e2c | 1458:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 0AC54E7FB4 |
| 8086:0e2c | 15d9:062f | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | F5F0A90676 |
| 8086:0e2c | 15d9:0660 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 521882E396 |
| 8086:0e2c | 15d9:0665 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | CEC82EF5D0 |
| 8086:0e2c | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 8C793BB137 |
| 8086:0e2c | 15d9:070a | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | B4C8ABC585 |
| 8086:0e2c | 15d9:0714 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | F9D5463C17 |
| 8086:0e2c | 8086:357e | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 018029FB72 |
| 8086:0e2c | 8086:3582 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 9F6D925B73 |
| 8086:0e2c | 8086:358c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | D15B8F8758 |
| 8086:1461 | 8086:341a | Intel      | 82870P2 P64H2 I/OxAPIC       | 1     |            | 37AA8C0E8E |
| 8086:2026 | 17aa:1037 | Intel      | Sky Lake-E IOAPIC            | 1     |            | 41249F2E48 |
| 8086:2026 | 8086:35cd | Intel      | Sky Lake-E IOAPIC            | 1     |            | 9CF9DCEEE9 |
| 8086:2036 | 17aa:1037 | Intel      | Sky Lake-E IOxAPIC Config... | 1     |            | 41249F2E48 |
| 8086:2036 | 8086:35cd | Intel      | Sky Lake-E IOxAPIC Config... | 1     |            | 9CF9DCEEE9 |
| 8086:25ac | 0e11:3201 | Intel      | 6300ESB I/O Advanced Prog... | 1     |            | BF8AB3D150 |
| 8086:2f2c | 1458:1000 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 2F69A2F89C |
| 8086:2f2c | 15d9:0834 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 3DA0A0E196 |
| 8086:2f2c | 15d9:0856 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 50EC24A7DE |
| 8086:2f2c | 15d9:086b | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 3CFD00A1CD |
| 8086:2f2c | 15d9:0879 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 21124E85CC |
| 8086:2f2c | 15d9:0924 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 3FC4F3458F |
| 8086:2f2c | 19e5:2061 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 5EB4DFC951 |
| 8086:2f2c | 19e5:2062 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | BA0F3C3B41 |
| 8086:2f2c | 1d49:0a00 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 817865DED6 |
| 8086:2f2c | 8086:35c5 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 08100751B7 |
| 8086:2f2c | 8086:35c9 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 5F9F099F36 |
| 8086:342d | 0086:0000 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | CBBE408AAC |
| 8086:342f | 0086:0000 | Intel      | 7500/5520/5500/X58 Truste... | 1     |            | CBBE408AAC |
| 8086:3c2c | 1028:0518 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | 395F17CE3F |
| 8086:3c2c | 15d9:0630 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | 575A60EDC8 |
| 8086:3c2c | 15d9:0660 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | AFE42B7E58 |
| 8086:3c2c | 15d9:066b | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | 1FF0EE8759 |
| 8086:3c2c | 1734:11b5 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | B0EE52BCF3 |
| 8086:3c2c | 1734:11b6 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | 9C16958A72 |
| 8086:3c2c | 8086:35b0 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | 30CFD7BC18 |
| 8086:3c2c | 8086:3c2c | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | 91A367AB6D |
| 8086:6f2c | 15d9:0831 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | 64918C950D |
| 8086:6f2c | 15d9:0832 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | 4D83783043 |
| 8086:6f2c | 15d9:0835 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | 7479576DA8 |

### Pic (io-apic) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:7451 | 10f1:2895 | AMD        | AMD-8131 PCI-X IOAPIC        | 1     |            | 768571B831 |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:31cc | 1019:a94d | Intel      | Celeron/Pentium Silver Pr... | 3     | sdhci_pci  | 6AEB74B9F1 |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a1a4 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 19    |            | 36C4ACAC2D |
| 8086:a1a4 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 17    | intel_s... | AD903545CE |
| 8086:a1a4 | 1028:073a | Intel      | C620 Series Chipset Famil... | 8     |            | C7D795E2A5 |
| 8086:a1a4 | 1043:871e | Intel      | C620 Series Chipset Famil... | 8     | intel_s... | 55BDC0F976 |
| 8086:a1a4 | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     | intel_s... | CEE7ED2CE9 |
| 8086:a1a4 | 15d9:096d | Intel      | C620 Series Chipset Famil... | 5     |            | C8195297A4 |
| 8086:a1a4 | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 5     | intel_s... | 5E1947B31A |
| 8086:a1a4 | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     |            | E9A1FC86F9 |
| 8086:a1a4 | 1028:0739 | Intel      | C620 Series Chipset Famil... | 4     |            | 9E01FD5E8C |
| 8086:a1a4 | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 4     |            | 5299B4DA87 |
| 8086:a1a4 | 1849:a1a4 | Intel      | C620 Series Chipset Famil... | 4     |            | 2244EB7809 |
| 8086:a324 | 8086:7270 | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | B8FFB92409 |
| 10de:1ad7 | 1458:37c4 | Nvidia     | TU102 USB Type-C UCSI Con... | 3     | i2c_nvi... | F9D0B2BC99 |
| 8086:a1a4 | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | E752263E49 |
| 8086:a1a4 | 103c:81c6 | Intel      | C620 Series Chipset Famil... | 3     |            | 679871CFEC |
| 8086:a1a4 | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     |            | 7AD1F5EB4E |
| 8086:a1a4 | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     |            | C682299C13 |
| 8086:a1a4 | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     |            | 5658A2FB98 |
| 8086:a324 | 1028:088e | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | 2A87802C58 |
| 8086:a324 | 15d9:1a1b | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | F1BF9D35EF |
| 8086:a324 | 15d9:1a1d | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | E57FDAECA4 |
| 8086:a368 | 15d9:1a1b | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | F1BF9D35EF |
| 8086:a368 | 15d9:1a1d | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | E57FDAECA4 |
| 8086:a369 | 15d9:1a1b | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | F1BF9D35EF |
| 8086:a369 | 15d9:1a1d | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | E57FDAECA4 |
| 10de:1ad7 | 1028:12ba | Nvidia     | TU102 USB Type-C UCSI Con... | 2     | i2c_nvi... | 33FDE2B5FB |
| 10de:1ad7 | 10de:12a3 | Nvidia     | TU102 USB Type-C UCSI Con... | 2     | i2c_nvi... | 8A1397B10C |
| 8086:19e0 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 2     | intel_s... | 40E07B4DAD |
| 8086:1bca | 8086:7270 | Intel      | Serial bus controller        | 2     |            | AEAD99F55D |
| 8086:a1a4 | 1028:0718 | Intel      | C620 Series Chipset Famil... | 2     |            | 1CCB5D67C2 |
| 8086:a1a4 | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     |            | DF9A63BE43 |
| 8086:a1a4 | 1028:07cb | Intel      | C620 Series Chipset Famil... | 2     |            | FE43558C7A |
| 8086:a1a4 | 1028:07e5 | Intel      | C620 Series Chipset Famil... | 2     |            | 4C88B2E09B |
| 8086:a1a4 | 15d9:091c | Intel      | C620 Series Chipset Famil... | 2     |            | 748FB8054B |
| 8086:a1a4 | 15d9:0941 | Intel      | C620 Series Chipset Famil... | 2     |            | C619DB847B |
| 8086:a1a4 | 17aa:7800 | Intel      | C620 Series Chipset Famil... | 2     |            | 928EE22E71 |
| 8086:a324 | 1028:0890 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 13E5EC2882 |
| 8086:a324 | 15d9:1a1f | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | CAC1B04E1E |
| 8086:a368 | 15d9:1a1f | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | CAC1B04E1E |
| 8086:a369 | 15d9:1a1f | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | CAC1B04E1E |
| 10de:1ad7 | 1043:8675 | Nvidia     | TU102 USB Type-C UCSI Con... | 1     |            | 8D9AEAB599 |
| 10de:1ad7 | 10de:12ba | Nvidia     | TU102 USB Type-C UCSI Con... | 1     | i2c_nvi... | 188BBE12AF |
| 10de:1ad7 | 1458:37ab | Nvidia     | TU102 USB Type-C UCSI Con... | 1     | i2c_nvi... | 72C72698D3 |
| 10de:1ad7 | 196e:134e | Nvidia     | TU102 USB Type-C UCSI Con... | 1     |            | BE9847546A |
| 10de:1ad7 | 19da:2503 | Nvidia     | TU102 USB Type-C UCSI Con... | 1     |            | 8E73F804F5 |
| 10de:1ad7 | 3842:2281 | Nvidia     | TU102 USB Type-C UCSI Con... | 1     | i2c_nvi... | 7E93E1B694 |
| 10de:1ad7 | 3842:2382 | Nvidia     | TU102 USB Type-C UCSI Con... | 1     | i2c_nvi... | B8FFB92409 |
| 10de:1ad9 | 1028:129f | Nvidia     | TU104 USB Type-C UCSI Con... | 1     | i2c_nvi... | C8F90792EC |
| 10de:1ad9 | 1028:12a0 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     |            | 845D92DA91 |
| 10de:1ad9 | 1462:3720 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     |            | 3AC4E6EB75 |
| 10de:1ad9 | 196e:133f | Nvidia     | TU104 USB Type-C UCSI Con... | 1     | i2c_nvi... | 375EC8881D |
| 10de:1ad9 | 3842:2066 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     |            | EF434D4B56 |
| 10de:1adb | 19da:1516 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     |            | 78CDBBD363 |
| 10de:1adb | 19da:2516 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     |            | 9E25A27714 |
| 10de:1adb | 3842:3067 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     | i2c_nvi... | 2F69A2F89C |
| 10de:1aed | 3842:1357 | Nvidia     | TU116 USB Type-C UCSI Con... | 1     | i2c_nvi... | 3A14AEA222 |
| 8086:a1a4 | 1028:07c9 | Intel      | C620 Series Chipset Famil... | 1     |            | E757687F86 |
| 8086:a1a4 | 1458:5001 | Intel      | C620 Series Chipset Famil... | 1     |            | 7E93E1B694 |
| 8086:a1a4 | 15d9:095e | Intel      | C620 Series Chipset Famil... | 1     |            | E0F65B7228 |
| 8086:a1a4 | 15d9:0962 | Intel      | C620 Series Chipset Famil... | 1     |            | 57460AA45B |
| 8086:a1a4 | 15d9:0967 | Intel      | C620 Series Chipset Famil... | 1     |            | 6FAB4E3135 |
| 8086:a1a4 | 15d9:0968 | Intel      | C620 Series Chipset Famil... | 1     |            | 7026C20C97 |
| 8086:a1a4 | 15d9:096e | Intel      | C620 Series Chipset Famil... | 1     |            | 4D0ED95E02 |
| 8086:a1a4 | 15d9:0986 | Intel      | C620 Series Chipset Famil... | 1     |            | 331227D869 |
| 8086:a1a4 | 15d9:0987 | Intel      | C620 Series Chipset Famil... | 1     |            | 893E9D69F2 |
| 8086:a1a4 | 1734:1230 | Intel      | C620 Series Chipset Famil... | 1     |            | 86AB491564 |
| 8086:a1a4 | 17aa:1037 | Intel      | C620 Series Chipset Famil... | 1     |            | 41249F2E48 |
| 8086:a1a4 | 8086:35cd | Intel      | C620 Series Chipset Famil... | 1     |            | 9CF9DCEEE9 |
| 8086:a324 | 1028:0891 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 56CB3FC570 |
| 8086:a324 | 15d9:099e | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | F34EB9D9C6 |
| 8086:a324 | 15d9:1b09 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 59C50944A0 |
| 8086:a324 | 15d9:1b0e | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 99AE6D7DBE |
| 8086:a324 | 15d9:1b0f | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | D9DA751F0F |
| 8086:a368 | 15d9:099e | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | F34EB9D9C6 |
| 8086:a368 | 15d9:1b09 | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | 59C50944A0 |
| 8086:a368 | 15d9:1b0e | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_lpss | 99AE6D7DBE |
| 8086:a368 | 15d9:1b0f | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | D9DA751F0F |
| 8086:a368 | 8086:7270 | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | 6FAAF237CE |
| 8086:a369 | 15d9:099e | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | F34EB9D9C6 |
| 8086:a369 | 15d9:1b09 | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | 59C50944A0 |
| 8086:a369 | 15d9:1b0e | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_lpss | 99AE6D7DBE |
| 8086:a369 | 15d9:1b0f | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | D9DA751F0F |
| 8086:a369 | 8086:7270 | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | 6FAAF237CE |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a1bd | 1028:073a | Intel      | C620 Series Chipset Famil... | 6     | serial     | C7D795E2A5 |
| 8086:8c3d | 15d9:0805 | Intel      | 8 Series/C220 Series Chip... | 4     | serial     | 019914CC29 |
| 8086:a13d | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 4     | serial     | BE8471A6F1 |
| 8086:a363 | 8086:7270 | Intel      | Cannon Lake PCH Active Ma... | 4     | serial     | B8FFB92409 |
| 8086:a1bd | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     | serial     | 5658A2FB98 |
| 8086:a13d | 8086:1999 | Intel      | 100 Series/C230 Series Ch... | 2     | serial     | 0F1EA2D9DA |
| 8086:a1bd | 1028:0739 | Intel      | C620 Series Chipset Famil... | 2     | serial     | 3514F18D29 |
| 9710:9865 | a000:1000 | MosChip... | PCI 9865 Multi-I/O Contro... | 2     | parport_pc | 715B40D8B6 |
| 10ee:4b87 | 10ee:4350 | Xilinx     | Serial controller            | 1     | xclmgmt    | 7026C20C97 |
| 10ee:4b88 | 10ee:4350 | Xilinx     | Serial controller            | 1     | xocl       | 7026C20C97 |
| 1393:1024 | 1393:1024 | Moxa Te... | CP-102E (2-port RS-232 Sm... | 1     | serial     | 9C8826C0D2 |
| 1415:9501 | 131f:2050 | Oxford ... | OX16PCI954 (Quad 16950 UA... | 1     | serial     | 80DC2F8936 |
| 1415:c158 | 1415:c158 | Oxford ... | OXPCIe952 Dual Native 950... | 1     | serial     | 352FEE0E7F |
| 1415:c208 | 1415:c208 | Oxford ... | OXPCIe954 Quad Native 950... | 1     | serial     | 375EC8881D |
| 8086:1d3d | 152d:8988 | Intel      | C600/X79 series chipset K... | 1     | serial     | E0EF143493 |
| 8086:8c3d | 15d9:0654 | Intel      | 8 Series/C220 Series Chip... | 1     | serial     | AE67700E54 |
| 8086:8d3d | 1458:1000 | Intel      | C610/X99 series chipset K... | 1     | serial     | 2F69A2F89C |
| 8086:a13d | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | serial     | C392838A14 |
| 8086:a13d | 15d9:0907 | Intel      | 100 Series/C230 Series Ch... | 1     | serial     | 66EE0BC524 |
| 8086:a13d | 8086:a13d | Intel      | 100 Series/C230 Series Ch... | 1     | serial     | E86E339278 |
| 8086:a1bd | 1734:1230 | Intel      | C620 Series Chipset Famil... | 1     | serial     | 86AB491564 |
| 8086:a1bd | 17aa:1037 | Intel      | C620 Series Chipset Famil... | 1     | serial     | 41249F2E48 |
| 9710:9904 | a000:1000 | MosChip... | 4-Port PCIe Serial Adapter   | 1     | serial     | 22A316E31B |
| 9710:9922 | a000:1000 | MosChip... | MCS9922 PCIe Multi-I/O Co... | 1     | serial     | 7479576DA8 |

### Signal processing (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0e30 | 1028:04f6 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 0FC3F83656 |
| 8086:0e34 | 1028:04f6 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 0FC3F83656 |
| 8086:0e36 | 1028:04f6 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 0FC3F83656 |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a1b1 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 20    |            | 36C4ACAC2D |
| 8086:a1b1 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 17    |            | AD903545CE |
| 8086:1d24 | 15d9:0636 | Intel      | C600/X79 series chipset T... | 12    |            | DD93F62FFC |
| 8086:a131 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 9     | intel_p... | F3A274A366 |
| 8086:8d24 | 15d9:0857 | Intel      | C610/X99 series chipset T... | 8     |            | 6A333A499D |
| 8086:a1b1 | 1028:073a | Intel      | C620 Series Chipset Famil... | 8     |            | C7D795E2A5 |
| 8086:a1b1 | 1043:871e | Intel      | C620 Series Chipset Famil... | 8     | intel_p... | 55BDC0F976 |
| 8086:8c24 | 15d9:0801 | Intel      | 8 Series Chipset Family T... | 7     | intel_p... | EA6FC4377F |
| 8086:a1b1 | 1590:00eb | Intel      | C620 Series Chipset Famil... | 7     |            | 7AB4F05613 |
| 8086:a1b1 | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     |            | CEE7ED2CE9 |
| 19e5:1710 | 19e5:0000 | Huawei ... | iBMA Virtual Network Adapter | 5     |            | AD903545CE |
| 8086:8c24 | 15d9:0805 | Intel      | 8 Series Chipset Family T... | 5     | intel_p... | 019914CC29 |
| 8086:a131 | 1028:06a5 | Intel      | 100 Series/C230 Series Ch... | 5     |            | E2A3815DD2 |
| 8086:a1b1 | 15d9:096d | Intel      | C620 Series Chipset Famil... | 5     |            | C8195297A4 |
| 8086:a1b1 | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 5     | intel_p... | 5E1947B31A |
| 8086:a131 | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_p... | BE8471A6F1 |
| 8086:a131 | 15d9:089a | Intel      | 100 Series/C230 Series Ch... | 4     | intel_p... | E8634FF947 |
| 8086:a1b1 | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     |            | E9A1FC86F9 |
| 8086:a1b1 | 1028:0739 | Intel      | C620 Series Chipset Famil... | 4     |            | 9E01FD5E8C |
| 8086:a1b1 | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 4     |            | 5299B4DA87 |
| 8086:a1b1 | 1849:a1b1 | Intel      | C620 Series Chipset Famil... | 4     | intel_p... | 2244EB7809 |
| 8086:a379 | 8086:7270 | Intel      | Cannon Lake PCH Thermal C... | 4     | intel_p... | B8FFB92409 |
| 8086:1d24 | 15d9:062a | Intel      | C600/X79 series chipset T... | 3     |            | 47401D66CE |
| 8086:8c24 | 15d9:086d | Intel      | 8 Series Chipset Family T... | 3     | intel_p... | 938F3AEFA9 |
| 8086:8c24 | 15d9:0921 | Intel      | 8 Series Chipset Family T... | 3     | intel_p... | 34DBD86F7B |
| 8086:8c24 | 8086:0000 | Intel      | 8 Series Chipset Family T... | 3     | intel_p... | 14C76E0C83 |
| 8086:8c24 | 8086:35b5 | Intel      | 8 Series Chipset Family T... | 3     | intel_p... | 20BB0A8951 |
| 8086:8d24 | 1458:0000 | Intel      | C610/X99 series chipset T... | 3     |            | 2F69A2F89C |
| 8086:8d24 | 15d9:0831 | Intel      | C610/X99 series chipset T... | 3     |            | 2CE36E96F0 |
| 8086:8d24 | 1d49:0000 | Intel      | C610/X99 series chipset T... | 3     |            | 3510DD7B10 |
| 8086:a160 | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 3     | intel_l... | 5C898D272B |
| 8086:a161 | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 3     | intel_l... | 5C898D272B |
| 8086:a1b1 | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | E752263E49 |
| 8086:a1b1 | 103c:81c6 | Intel      | C620 Series Chipset Famil... | 3     |            | 679871CFEC |
| 8086:a1b1 | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     |            | 7AD1F5EB4E |
| 8086:a1b1 | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     |            | C682299C13 |
| 8086:a1b1 | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     |            | 5658A2FB98 |
| 8086:a379 | 1028:088e | Intel      | Cannon Lake PCH Thermal C... | 3     | intel_p... | 2A87802C58 |
| 8086:a379 | 15d9:1a1b | Intel      | Cannon Lake PCH Thermal C... | 3     | intel_p... | F1BF9D35EF |
| 8086:a379 | 15d9:1a1d | Intel      | Cannon Lake PCH Thermal C... | 3     | intel_p... | E57FDAECA4 |
| 8086:1d24 | 15d9:0626 | Intel      | C600/X79 series chipset T... | 2     |            | 00FDD71981 |
| 8086:1d24 | 15d9:062b | Intel      | C600/X79 series chipset T... | 2     |            | FD24B5D375 |
| 8086:1d24 | 15d9:0660 | Intel      | C600/X79 series chipset T... | 2     |            | AFE42B7E58 |
| 8086:1d24 | 15d9:0702 | Intel      | C600/X79 series chipset T... | 2     |            | 4DC142D672 |
| 8086:8c24 | 15d9:0803 | Intel      | 8 Series Chipset Family T... | 2     | intel_p... | 869444ACF6 |
| 8086:8d24 | 8086:8d24 | Intel      | C610/X99 series chipset T... | 2     |            | 2903921AEB |
| 8086:a131 | 15d9:088b | Intel      | 100 Series/C230 Series Ch... | 2     | intel_p... | C0E1C15247 |
| 8086:a1b1 | 1028:0718 | Intel      | C620 Series Chipset Famil... | 2     |            | 1CCB5D67C2 |
| 8086:a1b1 | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     |            | DF9A63BE43 |
| 8086:a1b1 | 1028:07cb | Intel      | C620 Series Chipset Famil... | 2     |            | FE43558C7A |
| 8086:a1b1 | 1028:07e5 | Intel      | C620 Series Chipset Famil... | 2     |            | 4C88B2E09B |
| 8086:a1b1 | 15d9:091c | Intel      | C620 Series Chipset Famil... | 2     |            | 748FB8054B |
| 8086:a1b1 | 15d9:0941 | Intel      | C620 Series Chipset Famil... | 2     |            | C619DB847B |
| 8086:a1b1 | 17aa:7800 | Intel      | C620 Series Chipset Famil... | 2     |            | 928EE22E71 |
| 8086:a379 | 1028:0890 | Intel      | Cannon Lake PCH Thermal C... | 2     | intel_p... | 13E5EC2882 |
| 8086:a379 | 15d9:1a1f | Intel      | Cannon Lake PCH Thermal C... | 2     | intel_p... | CAC1B04E1E |
| 1805:0812 | 1805:0004 | Euresys    | S.A Signal processing con... | 1     | coaxlink   | C619DB847B |
| 8086:1d24 | 1014:0000 | Intel      | C600/X79 series chipset T... | 1     |            | 8538814CD6 |
| 8086:1d24 | 1458:0000 | Intel      | C600/X79 series chipset T... | 1     |            | 0AC54E7FB4 |
| 8086:1d24 | 152d:8988 | Intel      | C600/X79 series chipset T... | 1     |            | E0EF143493 |
| 8086:1d24 | 15d9:062f | Intel      | C600/X79 series chipset T... | 1     |            | F5F0A90676 |
| 8086:1d24 | 15d9:0630 | Intel      | C600/X79 series chipset T... | 1     |            | 575A60EDC8 |
| 8086:1d24 | 15d9:0665 | Intel      | C600/X79 series chipset T... | 1     |            | CEC82EF5D0 |
| 8086:1d24 | 15d9:066b | Intel      | C600/X79 series chipset T... | 1     |            | 1FF0EE8759 |
| 8086:1d24 | 15d9:0703 | Intel      | C600/X79 series chipset T... | 1     |            | 8C793BB137 |
| 8086:1d24 | 15d9:0705 | Intel      | C600/X79 series chipset T... | 1     |            | B3D08DD227 |
| 8086:1d24 | 15d9:070a | Intel      | C600/X79 series chipset T... | 1     |            | B4C8ABC585 |
| 8086:1d24 | 15d9:0714 | Intel      | C600/X79 series chipset T... | 1     |            | F9D5463C17 |
| 8086:1d24 | 17aa:102c | Intel      | C600/X79 series chipset T... | 1     |            | 91A367AB6D |
| 8086:1d77 | 8086:0000 | Intel      | C600/X79 series chipset P... | 1     |            | FC0558920D |
| 8086:8c24 | 15d9:0653 | Intel      | 8 Series Chipset Family T... | 1     | intel_p... | 171EE8DB12 |
| 8086:8c24 | 15d9:0654 | Intel      | 8 Series Chipset Family T... | 1     | intel_p... | AE67700E54 |
| 8086:8c24 | 15d9:0802 | Intel      | 8 Series Chipset Family T... | 1     | intel_p... | 7115F8FDB7 |
| 8086:8c24 | 15d9:0811 | Intel      | 8 Series Chipset Family T... | 1     | intel_p... | 801EE74858 |
| 8086:8c24 | 15d9:0842 | Intel      | 8 Series Chipset Family T... | 1     | intel_p... | 290C6ED969 |
| 8086:8c24 | 8086:35b7 | Intel      | 8 Series Chipset Family T... | 1     | intel_p... | 0C59EA1474 |
| 8086:8d24 | 15d9:0000 | Intel      | C610/X99 series chipset T... | 1     |            | 5F6D0233A8 |
| 8086:8d24 | 15d9:0856 | Intel      | C610/X99 series chipset T... | 1     |            | 50EC24A7DE |
| 8086:8d24 | 15d9:086b | Intel      | C610/X99 series chipset T... | 1     |            | 3CFD00A1CD |
| 8086:8d24 | 19e5:2061 | Intel      | C610/X99 series chipset T... | 1     |            | 5EB4DFC951 |
| 8086:8d24 | 19e5:2062 | Intel      | C610/X99 series chipset T... | 1     |            | BA0F3C3B41 |
| 8086:8d24 | 8086:35cb | Intel      | C610/X99 series chipset T... | 1     |            | CC33C2E194 |
| 8086:a131 | 1028:06a6 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | 55471D97F1 |
| 8086:a131 | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | C74A66C7E6 |
| 8086:a131 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | BB8832ACBD |
| 8086:a131 | 15d9:0885 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | 50169A0FFB |
| 8086:a131 | 15d9:0886 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 80DC2F8936 |
| 8086:a131 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | C392838A14 |
| 8086:a131 | 15d9:0907 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | 66EE0BC524 |
| 8086:a131 | 1734:1222 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | 0BD7D9FCEA |
| 8086:a131 | 8086:a131 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | C4D59010A1 |
| 8086:a160 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | intel_l... | C392838A14 |
| 8086:a160 | 15d9:0907 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_l... | 66EE0BC524 |
| 8086:a161 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | intel_l... | C392838A14 |
| 8086:a161 | 15d9:0907 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_l... | 66EE0BC524 |
| 8086:a1b1 | 1028:07c9 | Intel      | C620 Series Chipset Famil... | 1     |            | E757687F86 |
| 8086:a1b1 | 1458:5001 | Intel      | C620 Series Chipset Famil... | 1     |            | 7E93E1B694 |
| 8086:a1b1 | 15d9:095e | Intel      | C620 Series Chipset Famil... | 1     |            | E0F65B7228 |
| 8086:a1b1 | 15d9:0962 | Intel      | C620 Series Chipset Famil... | 1     |            | 57460AA45B |
| 8086:a1b1 | 15d9:0967 | Intel      | C620 Series Chipset Famil... | 1     |            | 6FAB4E3135 |

### Signal processing management (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 19a2:0800 | 19a2:0800 | Emulex     | ServerView iRMC HTI          | 1     |            | 14C76E0C83 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a1a3 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 19    | i2c_i801   | 36C4ACAC2D |
| 8086:8d22 | 15d9:0821 | Intel      | C610/X99 series chipset S... | 17    | i2c_i801   | AAEEE85BE7 |
| 8086:a1a3 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 17    | i2c_i801   | AD903545CE |
| 8086:1d22 | 1043:84ef | Intel      | C600/X79 series chipset S... | 14    | i2c_i801   | 874EAAB0BB |
| 8086:3a30 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) SM... | 14    | i2c_i801   | DB4185737E |
| 8086:1d22 | 15d9:0636 | Intel      | C600/X79 series chipset S... | 12    | i2c_i801   | DD93F62FFC |
| 1022:790b | 1022:790b | AMD        | FCH SMBus Controller         | 10    | i2c_piix4  | 7735F49C62 |
| 8086:8d22 | 103c:8030 | Intel      | C610/X99 series chipset S... | 10    | i2c_i801   | CFFFE6AA63 |
| 8086:8d22 | 8086:7270 | Intel      | C610/X99 series chipset S... | 10    | i2c_i801   | C04F902B93 |
| 8086:a123 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 9     | i801_smbus | F3A274A366 |
| 1022:790b | 15d9:790b | AMD        | FCH SMBus Controller         | 8     | i2c_piix4  | 10F1608197 |
| 8086:1d22 | 1014:1d22 | Intel      | C600/X79 series chipset S... | 8     | i2c_i801   | 8D55479353 |
| 8086:3a30 | 1014:3a30 | Intel      | 82801JI (ICH10 Family) SM... | 8     | i2c_i801   | B4A013EED4 |
| 8086:8d22 | 15d9:0857 | Intel      | C610/X99 series chipset S... | 8     | i801_smbus | 6A333A499D |
| 8086:a1a3 | 1028:073a | Intel      | C620 Series Chipset Famil... | 8     | i2c_i801   | C7D795E2A5 |
| 8086:a1a3 | 1043:871e | Intel      | C620 Series Chipset Famil... | 8     | i2c_i801   | 55BDC0F976 |
| 1022:790b | 1458:1000 | AMD        | FCH SMBus Controller         | 7     | i2c_piix4  | 96079334BD |
| 8086:3a30 | 15d9:0400 | Intel      | 82801JI (ICH10 Family) SM... | 7     | i2c_i801   | AD4ABE60CD |
| 8086:3a30 | 8086:34dc | Intel      | 82801JI (ICH10 Family) SM... | 7     | i801_smbus | 451F363726 |
| 8086:8c22 | 15d9:0801 | Intel      | 8 Series/C220 Series Chip... | 7     | i2c_i801   | EA6FC4377F |
| 8086:8d22 | 1043:85f6 | Intel      | C610/X99 series chipset S... | 7     | i2c_i801   | 4158CB76EF |
| 8086:a1a3 | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     | i2c_i801   | CEE7ED2CE9 |
| 1002:4385 | 15d9:ab11 | AMD        | SBx00 SMBus Controller       | 6     | i2c_piix4  | D5563E325C |
| 1002:4385 | 15d9:bc11 | AMD        | SBx00 SMBus Controller       | 6     | i2c_piix4  | 1FE97B31A1 |
| 8086:1c22 | 1028:04de | Intel      | 6 Series/C200 Series Chip... | 6     | i2c_i801   | 0893528A1F |
| 8086:2930 | 8086:34d0 | Intel      | 82801I (ICH9 Family) SMBu... | 6     | i2c_i801   | FC38CA11F5 |
| 8086:3a30 | 15d9:0001 | Intel      | 82801JI (ICH10 Family) SM... | 6     | i2c_i801   | AFA93003E2 |
| 8086:3a30 | 1734:114d | Intel      | 82801JI (ICH10 Family) SM... | 6     | i2c_i801   | 43C0756BA6 |
| 8086:3a30 | 15d9:0100 | Intel      | 82801JI (ICH10 Family) SM... | 5     | i2c_i801   | C83DC07B7C |
| 8086:3a30 | 15d9:0600 | Intel      | 82801JI (ICH10 Family) SM... | 5     | i2c_i801   | ACA2A2FFDF |
| 8086:3a30 | 8086:34da | Intel      | 82801JI (ICH10 Family) SM... | 5     | i2c_i801   | F9F8DD79F5 |
| 8086:3a30 | 8086:34e2 | Intel      | 82801JI (ICH10 Family) SM... | 5     | i2c_i801   | FDCE629C37 |
| 8086:8c22 | 15d9:0805 | Intel      | 8 Series/C220 Series Chip... | 5     | i801_smbus | 019914CC29 |
| 8086:8c22 | 8086:8c22 | Intel      | 8 Series/C220 Series Chip... | 5     | i2c_i801   | FEC09C0BAC |
| 8086:8d22 | 15d9:0831 | Intel      | C610/X99 series chipset S... | 5     | i2c_i801   | 64918C950D |
| 8086:a123 | 1028:06a5 | Intel      | 100 Series/C230 Series Ch... | 5     | i2c_i801   | E2A3815DD2 |
| 8086:a1a3 | 15d9:096d | Intel      | C620 Series Chipset Famil... | 5     | i2c_i801   | C8195297A4 |
| 8086:a1a3 | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 5     | i2c_i801   | 5E1947B31A |
| 1002:4385 | 1028:0444 | AMD        | SBx00 SMBus Controller       | 4     | i2c_piix4  | AD7D2477F8 |
| 8086:1c22 | 1028:04dd | Intel      | 6 Series/C200 Series Chip... | 4     | i2c_i801   | D52DB39EEB |
| 8086:1c22 | 1043:8497 | Intel      | 6 Series/C200 Series Chip... | 4     | i2c_i801   | 750A124EF3 |
| 8086:1c22 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 4     | i2c_i801   | 57162CA72C |
| 8086:1d22 | 8086:357e | Intel      | C600/X79 series chipset S... | 4     | i2c_i801   | 0FADD1EBE3 |
| 8086:1d22 | 8086:35a0 | Intel      | C600/X79 series chipset S... | 4     |            | FE1E6CFF79 |
| 8086:1d70 | 8086:35a0 | Intel      | C600/X79 series chipset S... | 4     |            | FE1E6CFF79 |
| 8086:269b | 8086:3476 | Intel      | 631xESB/632xESB/3100 Chip... | 4     | i2c_i801   | 38109F9919 |
| 8086:27da | 1028:01e7 | Intel      | NM10/ICH7 Family SMBus Co... | 4     | i2c_i801   | EA66809CE7 |
| 8086:3a30 | 15d9:060f | Intel      | 82801JI (ICH10 Family) SM... | 4     | i2c_i801   | CF99AAD395 |
| 8086:3a30 | 8086:3a30 | Intel      | 82801JI (ICH10 Family) SM... | 4     | i2c_i801   | 6B7A9D9BDB |
| 8086:3b30 | 1014:0377 | Intel      | 5 Series/3400 Series Chip... | 4     | i2c_i801   | 882EA8E25E |
| 8086:a123 | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 4     | i2c_i801   | BE8471A6F1 |
| 8086:a123 | 15d9:089a | Intel      | 100 Series/C230 Series Ch... | 4     | i2c_i801   | E8634FF947 |
| 8086:a1a3 | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     | i2c_i801   | E9A1FC86F9 |
| 8086:a1a3 | 1028:0739 | Intel      | C620 Series Chipset Famil... | 4     | i2c_i801   | 9E01FD5E8C |
| 8086:a1a3 | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 4     | i801_smbus | 5299B4DA87 |
| 8086:a1a3 | 1849:a1a3 | Intel      | C620 Series Chipset Famil... | 4     | i2c_i801   | 2244EB7809 |
| 8086:a323 | 8086:7270 | Intel      | Cannon Lake PCH SMBus Con... | 4     |            | B8FFB92409 |
| 1002:4385 | 103c:1772 | AMD        | SBx00 SMBus Controller       | 3     | piix4_s... | DC4AC74B49 |
| 1002:4385 | 103c:3337 | AMD        | SBx00 SMBus Controller       | 3     | i2c_piix4  | 91AD975174 |
| 1002:4385 | 15d9:a811 | AMD        | SBx00 SMBus Controller       | 3     | i2c_piix4  | 201AA7046E |
| 1022:790b | 1028:08ff | AMD        | FCH SMBus Controller         | 3     | i2c_piix4  | A35E7D3EB0 |
| 8086:1c22 | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 3     | i2c_i801   | E6D89DC95B |
| 8086:1d22 | 15d9:062a | Intel      | C600/X79 series chipset S... | 3     | i2c_i801   | 47401D66CE |
| 8086:269b | 8086:3486 | Intel      | 631xESB/632xESB/3100 Chip... | 3     | i2c_i801   | 0A3F6D305B |
| 8086:31d4 | 1019:a94d | Intel      | Celeron/Pentium Silver Pr... | 3     | i2c_i801   | 6AEB74B9F1 |
| 8086:3a30 | 15d9:0404 | Intel      | 82801JI (ICH10 Family) SM... | 3     | i2c_i801   | 9CC6367D9F |
| 8086:8c22 | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 3     | i2c_i801   | 938F3AEFA9 |
| 8086:8c22 | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 3     | i801_smbus | 34DBD86F7B |
| 8086:8c22 | 8086:35b5 | Intel      | 8 Series/C220 Series Chip... | 3     | i2c_i801   | 20BB0A8951 |
| 8086:8d22 | 1458:1000 | Intel      | C610/X99 series chipset S... | 3     | i2c_i801   | 2F69A2F89C |
| 8086:8d22 | 15d9:0834 | Intel      | C610/X99 series chipset S... | 3     | i2c_i801   | FA4BECDE8B |
| 8086:8d22 | 1d49:0a00 | Intel      | C610/X99 series chipset S... | 3     | i2c_i801   | 3510DD7B10 |
| 8086:a1a3 | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     | i2c_i801   | E752263E49 |
| 8086:a1a3 | 103c:81c6 | Intel      | C620 Series Chipset Famil... | 3     | i2c_i801   | 679871CFEC |
| 8086:a1a3 | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     | i2c_i801   | 7AD1F5EB4E |
| 8086:a1a3 | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     |            | C682299C13 |
| 8086:a1a3 | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     | i2c_i801   | 5658A2FB98 |
| 8086:a323 | 1028:088e | Intel      | Cannon Lake PCH SMBus Con... | 3     | i2c_i801   | 2A87802C58 |
| 8086:a323 | 15d9:1a1b | Intel      | Cannon Lake PCH SMBus Con... | 3     | i2c_i801   | F1BF9D35EF |
| 8086:a323 | 15d9:1a1d | Intel      | Cannon Lake PCH SMBus Con... | 3     | i2c_i801   | E57FDAECA4 |
| 1002:4385 | 1002:4385 | AMD        | SBx00 SMBus Controller       | 2     | i2c_pii... | D05C262E67 |
| 1002:4385 | 1111:077c | AMD        | SBx00 SMBus Controller       | 2     | piix4_s... | 58771D090D |
| 1002:4385 | 15d9:ba11 | AMD        | SBx00 SMBus Controller       | 2     | i2c_pii... | 6381FD461D |
| 1002:4385 | 15d9:ca11 | AMD        | SBx00 SMBus Controller       | 2     | i2c_piix4  | 9712585D1C |
| 1002:4385 | 15d9:cd11 | AMD        | SBx00 SMBus Controller       | 2     | i2c_piix4  | CF37C43C55 |
| 10de:0368 | 1462:cb84 | Nvidia     | MCP55 SMBus Controller       | 2     | i2c_nfo... | B8300AFB35 |
| 8086:19df | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 2     | i2c_i801   | 40E07B4DAD |
| 8086:1bc9 | 8086:7270 | Intel      | SMBus                        | 2     |            | AEAD99F55D |
| 8086:1d22 | 1170:0054 | Intel      | C600/X79 series chipset S... | 2     | i2c_i801   | 1B5977B024 |
| 8086:1d22 | 15d9:0626 | Intel      | C600/X79 series chipset S... | 2     | i2c_i801   | 00FDD71981 |
| 8086:1d22 | 15d9:062b | Intel      | C600/X79 series chipset S... | 2     | i2c_i801   | FD24B5D375 |
| 8086:1d22 | 15d9:0660 | Intel      | C600/X79 series chipset S... | 2     | i2c_i801   | AFE42B7E58 |
| 8086:1d22 | 15d9:0702 | Intel      | C600/X79 series chipset S... | 2     | i2c_i801   | 4DC142D672 |
| 8086:1d22 | 8086:3594 | Intel      | C600/X79 series chipset S... | 2     | i2c_i801   | E70645D3E6 |
| 8086:1d70 | 8086:3594 | Intel      | C600/X79 series chipset S... | 2     | i2c_i801   | E70645D3E6 |
| 8086:269b | 1014:02dd | Intel      | 631xESB/632xESB/3100 Chip... | 2     | i2c_i801   | 3A68279F78 |
| 8086:269b | 1734:1090 | Intel      | 631xESB/632xESB/3100 Chip... | 2     | i2c_i801   | 872AE76863 |
| 8086:269b | 8086:346c | Intel      | 631xESB/632xESB/3100 Chip... | 2     | i2c_i801   | 390F15B7F9 |
| 8086:269b | 8086:3472 | Intel      | 631xESB/632xESB/3100 Chip... | 2     | i2c_i801   | 715B40D8B6 |
| 8086:3a30 | 1033:8372 | Intel      | 82801JI (ICH10 Family) SM... | 2     | i2c_i801   | 460A274240 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3a3e | 15d9:0006 | Intel      | 82801JI (ICH10 Family) HD... | 10    | snd_hda... | 0B3B288186 |
| 1102:0012 | 1102:0010 | Creativ... | Sound Core3D [Sound Blast... | 8     | snd_hda... | D2AA9ED999 |
| 8086:8d20 | 15d9:0857 | Intel      | C610/X99 series chipset H... | 8     | snd_hda... | 6A333A499D |
| 8086:a1f0 | 1028:073a | Intel      | Lewisburg MROM 0             | 8     | snd_hda... | C7D795E2A5 |
| 10de:0e0f | 1462:8c93 | Nvidia     | GK208 HDMI/DP Audio Contr... | 7     | snd_hda... | 4DC142D672 |
| 8086:1d20 | 1043:84d8 | Intel      | C600/X79 series chipset H... | 7     | snd_hda... | C3665EBF57 |
| 10de:0e0f | 196e:118b | Nvidia     | GK208 HDMI/DP Audio Contr... | 6     | snd_hda... | 3A68279F78 |
| 1002:aaf8 | 1002:aaf8 | AMD        | Vega 10 HDMI Audio [Radeo... | 5     | snd_hda... | 5299B4DA87 |
| 8086:3a3e | 15d9:0100 | Intel      | 82801JI (ICH10 Family) HD... | 5     | snd_hda... | C83DC07B7C |
| 8086:3a3e | 8086:34e2 | Intel      | 82801JI (ICH10 Family) HD... | 5     | snd_hda... | FDCE629C37 |
| 8086:8c20 | 15d9:0805 | Intel      | 8 Series/C220 Series Chip... | 5     | snd_hda... | 019914CC29 |
| 8086:a1f0 | 15d9:096d | Intel      | Lewisburg MROM 0             | 5     | snd_hda... | C8195297A4 |
| 1002:aa98 | 1028:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 4     | snd_hda... | 5D6883F1BB |
| 1002:aab0 | 174b:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 4     | snd_hda... | CD543E37E2 |
| 10de:0e0a | 10de:1096 | Nvidia     | GK104 HDMI Audio Controller  | 4     | snd_hda... | F508BB4C99 |
| 13f6:0111 | 13f6:0111 | C-Media... | CMI8738/CMI8768 PCI Audio    | 4     | snd_cmipci | 0C59EA1474 |
| 8086:0c0c | 15d9:0805 | Intel      | Xeon E3-1200 v3/4th Gen C... | 4     | snd_hda... | 019914CC29 |
| 8086:a1f0 | 1028:0739 | Intel      | Lewisburg MROM 0             | 4     | snd_hda... | 9E01FD5E8C |
| 8086:a1f0 | 103c:81c7 | Intel      | Lewisburg MROM 0             | 4     | snd_hda... | 5299B4DA87 |
| 8086:a348 | 8086:7270 | Intel      | Cannon Lake PCH cAVS         | 4     | snd_hda... | B8FFB92409 |
| 1002:9840 | 1002:9840 | AMD        | Kabini HDMI/DP Audio         | 3     | snd_hda... | 5D00EDD035 |
| 1002:aa68 | 1043:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 3     | snd_hda... | B8300AFB35 |
| 1002:aae0 | 1682:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 3     | snd_hda... | D350652289 |
| 10de:0e0f | 1043:84f5 | Nvidia     | GK208 HDMI/DP Audio Contr... | 3     | snd_hda... | 5D93D067D7 |
| 10de:0e0f | 19da:7326 | Nvidia     | GK208 HDMI/DP Audio Contr... | 3     | snd_hda... | F3CBAC183E |
| 10de:0fb9 | 1028:11be | Nvidia     | GP107GL High Definition A... | 3     | snd_hda... | 1567EFE934 |
| 10de:10f0 | 103c:11a3 | Nvidia     | GP104 High Definition Aud... | 3     | snd_hda... | 9D6E46ECA9 |
| 10de:10f7 | 1458:37c4 | Nvidia     | TU102 High Definition Aud... | 3     | snd_hda... | F9D0B2BC99 |
| 1102:0007 | 1102:100a | Creativ... | CA0106/CA0111 [SB Live!/A... | 3     | snd_ca0106 | 11BB1EE3A2 |
| 13f6:8788 | 1043:8521 | C-Media... | CMI8788 [Oxygen HD Audio]    | 3     | snd_oxygen | 9C8826C0D2 |
| 8086:1d20 | 1043:851b | Intel      | C600/X79 series chipset H... | 3     | snd_hda... | 5600070A23 |
| 8086:1d20 | 15d9:062a | Intel      | C600/X79 series chipset H... | 3     | snd_hda... | 47401D66CE |
| 8086:3198 | 1019:a94d | Intel      | Celeron/Pentium Silver Pr... | 3     | snd_hda... | 6AEB74B9F1 |
| 8086:a170 | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 3     | snd_hda... | 5C898D272B |
| 8086:a1f0 | 103c:81c6 | Intel      | Lewisburg MROM 0             | 3     | snd_hda... | 679871CFEC |
| 8086:a1f0 | 1043:8724 | Intel      | Lewisburg MROM 0             | 3     | snd_hda... | 55BDC0F976 |
| 8086:a1f0 | 17aa:1038 | Intel      | Lewisburg MROM 0             | 3     | snd_hda... | 5658A2FB98 |
| 8086:a348 | 15d9:1a1d | Intel      | Cannon Lake PCH cAVS         | 3     | snd_hda... | E57FDAECA4 |
| 1002:4383 | 1111:077c | AMD        | SBx00 Azalia (Intel HDA)     | 2     | snd_hda... | 58771D090D |
| 1002:aa68 | 1462:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 2     | snd_hda... | E014B80891 |
| 1002:aa98 | 1462:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 2     | snd_hda... | 1BF8F58CAF |
| 1002:aaa0 | 174b:aaa0 | AMD        | Tahiti HDMI Audio [Radeon... | 2     | snd_hda... | BEA324B5DA |
| 1002:aab0 | 1028:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 2     | snd_hda... | 5D6883F1BB |
| 1002:aac0 | 1682:aac0 | AMD        | Tobago HDMI Audio [Radeon... | 2     | snd_hda... | 8BD3D92585 |
| 1002:aae0 | 1002:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 2     | snd_hda... | 2244EB7809 |
| 1002:aae0 | 1028:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 2     | snd_hda... | 947E0AEF4A |
| 1002:aaf0 | 1043:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 2     | snd_hda... | D3DC168A2A |
| 1002:aaf0 | 1682:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 2     | snd_hda... | 98C12554CB |
| 1002:aaf0 | 1da2:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 2     | snd_hda... | D09F385D74 |
| 1002:ab20 | 1002:ab20 | AMD        | Vega 20 HDMI Audio [Radeo... | 2     | snd_hda... | 0343B901D9 |
| 1002:ab38 | 1002:ab38 | AMD        | Navi 10 HDMI Audio           | 2     | snd_hda... | 47401D66CE |
| 10de:0371 | 10de:cb84 | Nvidia     | MCP55 High Definition Audio  | 2     | snd_hda... | B8300AFB35 |
| 10de:0be3 | 10de:0862 | Nvidia     | High Definition Audio Con... | 2     | snd_hda... | 87E94A007B |
| 10de:0be5 | 10de:0771 | Nvidia     | GF100 High Definition Aud... | 2     | snd_hda... | 8E9E87A717 |
| 10de:0be9 | 10de:0914 | Nvidia     | GF106 High Definition Aud... | 2     | snd_hda... | 30DE024858 |
| 10de:0e0a | 3842:3769 | Nvidia     | GK104 HDMI Audio Controller  | 2     | snd_hda... | 1A5CF39F4F |
| 10de:0e0f | 1043:86cb | Nvidia     | GK208 HDMI/DP Audio Contr... | 2     | snd_hda... | 57162CA72C |
| 10de:0e0f | 1462:8a9f | Nvidia     | GK208 HDMI/DP Audio Contr... | 2     | snd_hda... | AE3BFE95C9 |
| 10de:0e0f | 19da:5360 | Nvidia     | GK208 HDMI/DP Audio Contr... | 2     | snd_hda... | AFF808A68F |
| 10de:0fb8 | 1458:3767 | Nvidia     | GP108 High Definition Aud... | 2     | snd_hda... | C889E2066F |
| 10de:0fb9 | 10de:11bc | Nvidia     | GP107GL High Definition A... | 2     | snd_hda... | 7B579629BB |
| 10de:0fbb | 1043:8508 | Nvidia     | GM204 High Definition Aud... | 2     | snd_hda... | AC7F5D0860 |
| 10de:0fbb | 10de:1153 | Nvidia     | GM204 High Definition Aud... | 2     | snd_hda... | ED3C250112 |
| 10de:0fbc | 3842:3753 | Nvidia     | GM107 High Definition Aud... | 2     | snd_hda... | AD61EFB931 |
| 10de:10ef | 1458:374c | Nvidia     | GP102 HDMI Audio Controller  | 2     | snd_hda... | 279B8964E5 |
| 10de:10f0 | 1028:11a3 | Nvidia     | GP104 High Definition Aud... | 2     | snd_hda... | 52B7CECCFF |
| 10de:10f0 | 1043:8597 | Nvidia     | GP104 High Definition Aud... | 2     | snd_hda... | 8BE78FB082 |
| 10de:10f0 | 10de:11a3 | Nvidia     | GP104 High Definition Aud... | 2     | snd_hda... | 5658A2FB98 |
| 10de:10f0 | 10de:11b2 | Nvidia     | GP104 High Definition Aud... | 2     | snd_hda... | 4D0ED95E02 |
| 10de:10f7 | 1028:12ba | Nvidia     | TU102 High Definition Aud... | 2     | snd_hda... | 33FDE2B5FB |
| 10de:10f7 | 10de:12a3 | Nvidia     | TU102 High Definition Aud... | 2     | snd_hda... | 8A1397B10C |
| 13f6:8788 | 1043:8275 | C-Media... | CMI8788 [Oxygen HD Audio]    | 2     | snd_vir... | 0F1EA2D9DA |
| 13f6:8788 | 1043:835c | C-Media... | CMI8788 [Oxygen HD Audio]    | 2     | snd_vir... | 47401D66CE |
| 8086:1bc8 | 8086:7270 | Intel      | Audio device                 | 2     |            | AEAD99F55D |
| 8086:1d20 | 8086:3594 | Intel      | C600/X79 series chipset H... | 2     | snd_hda... | E70645D3E6 |
| 8086:269a | 8086:3472 | Intel      | 631xESB/632xESB High Defi... | 2     | snd_hda... | 715B40D8B6 |
| 8086:3a3e | 8086:3a3e | Intel      | 82801JI (ICH10 Family) HD... | 2     | snd_hda... | 6B7A9D9BDB |
| 8086:8d20 | 1043:855f | Intel      | C610/X99 series chipset H... | 2     | snd_hda... | ED442D7C21 |
| 8086:a170 | 15d9:088b | Intel      | 100 Series/C230 Series Ch... | 2     | snd_hda... | C0E1C15247 |
| 8086:a1f0 | 1849:1158 | Intel      | Lewisburg MROM 0             | 2     | snd_hda... | 2244EB7809 |
| 1002:4383 | 1043:8444 | AMD        | SBx00 Azalia (Intel HDA)     | 1     | snd_hda... | D05C262E67 |
| 1002:4383 | 1734:119c | AMD        | SBx00 Azalia (Intel HDA)     | 1     | snd_hda... | B2EEA425F7 |
| 1002:aa08 | 0000:aa08 | AMD        | RV630 HDMI Audio [Radeon ... | 1     | snd_hda... | 2E139151DE |
| 1002:aa08 | 174b:aa08 | AMD        | RV630 HDMI Audio [Radeon ... | 1     | snd_hda... | 869444ACF6 |
| 1002:aa28 | 1787:aa28 | AMD        | RV620 HDMI Audio [Radeon ... | 1     | snd_hda... | 92A1C2425F |
| 1002:aa30 | 1787:aa30 | AMD        | RV770 HDMI Audio [Radeon ... | 1     | snd_hda... | C02E4721B7 |
| 1002:aa38 | 0000:aa38 | AMD        | RV710/730 HDMI Audio [Rad... | 1     | snd_hda... | B2EEA425F7 |
| 1002:aa38 | 1043:aa38 | AMD        | RV710/730 HDMI Audio [Rad... | 1     | snd_hda... | 8F45F37B98 |
| 1002:aa58 | 1002:aa58 | AMD        | Juniper HDMI Audio [Radeo... | 1     | snd_hda... | 58771D090D |
| 1002:aa58 | 1043:aa58 | AMD        | Juniper HDMI Audio [Radeo... | 1     | snd_hda... | 7E28DD35AD |
| 1002:aa60 | 1043:aa60 | AMD        | Redwood HDMI Audio [Radeo... | 1     | snd_hda... | 80AE06CD0D |
| 1002:aa60 | 1462:aa60 | AMD        | Redwood HDMI Audio [Radeo... | 1     | snd_hda... | 53D66D8AB3 |
| 1002:aa68 | 1092:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 1     | snd_hda... | 0A8BFA9B71 |
| 1002:aa68 | 1545:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 1     | snd_hda... | A4C832AB44 |
| 1002:aa68 | 1682:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 1     | snd_hda... | 5AB62504F8 |
| 1002:aa68 | 1787:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 1     | snd_hda... | B8D0722935 |
| 1002:aa80 | 1002:aa80 | AMD        | Cayman/Antilles HDMI Audi... | 1     | snd_hda... | 7F6C6E8DE0 |
| 1002:aa80 | 1028:aa80 | AMD        | Cayman/Antilles HDMI Audi... | 1     | snd_hda... | C7E9D74C3D |
| 1002:aa90 | 1002:aa90 | AMD        | Turks HDMI Audio [Radeon ... | 1     | snd_hda... | 5372999434 |
| 1002:aa98 | 1002:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 1     | snd_hda... | 429BDB3B21 |

### Storage (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1077:2532 | 1077:015d | QLogic     | ISP2532-based 8Gb Fibre C... | 4     | qla2xxx    | F2602534BE |
| 11f8:8032 | 117c:003b | PMC-Sierra | PM8032 Tachyon QE8           | 3     | celerit... | FB8C0A4C3A |
| 1077:2432 | 1077:0137 | QLogic     | ISP2432-based 4Gb Fibre C... | 2     | qla2xxx    | 43C0756BA6 |
| 1077:2532 | 1077:015c | QLogic     | ISP2532-based 8Gb Fibre C... | 2     | qla2xxx    | 1A5CF39F4F |
| 1077:2532 | 1077:015e | QLogic     | ISP2532-based 8Gb Fibre C... | 2     | qla2xxx    | C43FD89A0B |
| 10df:f0e5 | 10df:f0e5 | Emulex     | Zephyr LightPulse Fibre C... | 2     | lpfc       | E36BFCD946 |
| 1aed:2001 | 1590:006f | SanDisk    | ioDrive2                     | 2     |            | 5E1947B31A |
| 1aed:2001 | 1aed:2001 | SanDisk    | ioDrive2                     | 2     |            | 26B693742E |
| 1000:0646 | 1000:1020 | Broadco... | FC949ES Fibre Channel Ada... | 1     | mptfc      | 8F6E544820 |
| 1077:2031 | 103c:1939 | QLogic     | ISP8324-based 16Gb Fibre ... | 1     | qla2xxx    | 9036136416 |
| 1077:2031 | 1077:0249 | QLogic     | ISP8324-based 16Gb Fibre ... | 1     | qla2xxx    | 77A5A8BF12 |
| 1077:2031 | 1077:0257 | QLogic     | ISP8324-based 16Gb Fibre ... | 1     | qla2xxx    | CBFB7C31D8 |
| 1077:2261 | 1077:02af | QLogic     | ISP2722-based 16/32Gb Fib... | 1     | qla2xxx    | 2AE35CF194 |
| 1077:2312 | 1077:0100 | QLogic     | ISP2312-based 2Gb Fibre C... | 1     | qla2xxx    | 40F9D31598 |
| 1077:2432 | 103c:1705 | QLogic     | ISP2432-based 4Gb Fibre C... | 1     | qla2xxx    | DC4AC74B49 |
| 1077:2432 | 103c:7040 | QLogic     | ISP2432-based 4Gb Fibre C... | 1     | qla2xxx    | B4EF3B8086 |
| 1077:2432 | 103c:7041 | QLogic     | ISP2432-based 4Gb Fibre C... | 1     | qla2xxx    | C9D389B2A3 |
| 1077:2532 | 1077:0171 | QLogic     | ISP2532-based 8Gb Fibre C... | 1     | qla2xxx    | 4F5756D065 |
| 1077:2532 | 1077:0176 | QLogic     | ISP2532-based 8Gb Fibre C... | 1     | qla2xxx    | D7CBC31CEE |
| 10df:f100 | 103c:3282 | Emulex     | LPe12000 Series 8Gb Fibre... | 1     | lpfc       | 23F12250E5 |
| 10df:f400 | 10df:f410 | Emulex     | LPe35000/LPe36000 Series ... | 1     | lpfc       | 9320E12A9A |
| 10df:fe00 | 10df:fe00 | Emulex     | Zephyr-X LightPulse Fibre... | 1     | lpfc       | 6806624961 |
| 117c:0064 | 117c:0064 | ATTO Te... | Celerity FC 16Gb/s Gen 5 ... | 1     |            | 43EE2001E1 |
| 11f8:8032 | 117c:003a | PMC-Sierra | PM8032 Tachyon QE8           | 1     | celerit... | 5315690568 |
| 19a2:0702 | 103c:3314 | Emulex     | OneConnect 10Gb iSCSI Ini... | 1     | be2iscsi   | DC4AC74B49 |
| 19a2:0704 | 103c:174b | Emulex     | OneConnect OCe10100/OCe10... | 1     | lpfc       | E707BBA6A9 |
| 19e5:0203 | 19e5:d301 | Huawei ... | Hi1822 Family (2*16G FC)     | 1     |            | F548D0A0A9 |
| 1aed:2001 | 1028:1f70 | SanDisk    | ioDrive2                     | 1     |            | 1AFA47E662 |
| 1aed:2001 | 1028:1f71 | SanDisk    | ioDrive2                     | 1     |            | 4707D5CBF3 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a182 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 16    | ahci       | AD903545CE |
| 8086:a1d2 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 16    | ahci       | AD903545CE |
| 8086:1d02 | 1043:84ef | Intel      | C600/X79 series chipset 6... | 14    | ahci       | 874EAAB0BB |
| 8086:8d02 | 15d9:0821 | Intel      | C610/X99 series chipset 6... | 14    | ahci       | AAEEE85BE7 |
| 8086:8d62 | 15d9:0821 | Intel      | C610/X99 series chipset s... | 14    | ahci       | AAEEE85BE7 |
| 8086:1d02 | 103c:18a9 | Intel      | C600/X79 series chipset 6... | 13    | ahci       | 043730AD50 |
| 8086:3a22 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) SA... | 13    | ahci       | DB4185737E |
| 8086:1d02 | 15d9:0636 | Intel      | C600/X79 series chipset 6... | 12    | ahci       | DD93F62FFC |
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 9     | ahci       | 7735F49C62 |
| 1b4b:9230 | 1b4b:9230 | Marvell... | 88SE9230 PCIe 2.0 x2 4-po... | 9     | ahci       | 7735F49C62 |
| 8086:a102 | 8086:7270 | Intel      | Q170/Q150/B150/H170/H110/... | 9     | ahci       | F3A274A366 |
| 1b4b:9230 | 1043:84fa | Marvell... | 88SE9230 PCIe 2.0 x2 4-po... | 8     | ahci       | A4C832AB44 |
| 8086:8d02 | 103c:8030 | Intel      | C610/X99 series chipset 6... | 8     | ahci       | CFFFE6AA63 |
| 8086:8d02 | 8086:7270 | Intel      | C610/X99 series chipset 6... | 8     | ahci       | C04F902B93 |
| 8086:8d62 | 15d9:0857 | Intel      | C610/X99 series chipset s... | 8     | ahci       | 6A333A499D |
| 8086:a1d2 | 1028:073a | Intel      | C620 Series Chipset Famil... | 8     | ahci       | C7D795E2A5 |
| 1002:4391 | 1002:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 7     | ahci       | AD61EFB931 |
| 1022:7901 | 1458:1000 | AMD        | FCH SATA Controller [AHCI... | 7     | ahci       | 96079334BD |
| 1022:7901 | 15d9:7901 | AMD        | FCH SATA Controller [AHCI... | 7     | ahci       | 10F1608197 |
| 8086:1d02 | 1028:048c | Intel      | C600/X79 series chipset 6... | 7     | ahci       | 3BCB61F70C |
| 8086:1d02 | 1028:04fa | Intel      | C600/X79 series chipset 6... | 7     | ahci       | C9C876F0E7 |
| 8086:8d02 | 15d9:0857 | Intel      | C610/X99 series chipset 6... | 7     | ahci       | 6A333A499D |
| 8086:8d62 | 1043:85f7 | Intel      | C610/X99 series chipset s... | 7     | ahci       | 4158CB76EF |
| 8086:a182 | 1043:871e | Intel      | C620 Series Chipset Famil... | 7     | ahci       | 55BDC0F976 |
| 8086:a182 | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     | ahci       | CEE7ED2CE9 |
| 8086:a1d2 | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     | ahci       | CEE7ED2CE9 |
| 8086:8c02 | 15d9:0801 | Intel      | 8 Series/C220 Series Chip... | 6     | ahci       | EA6FC4377F |
| 8086:8d02 | 1028:0601 | Intel      | C610/X99 series chipset 6... | 6     | ahci       | F90168C69D |
| 8086:8d02 | 1043:85f6 | Intel      | C610/X99 series chipset 6... | 6     | ahci       | ED442D7C21 |
| 8086:8d62 | 1028:0601 | Intel      | C610/X99 series chipset s... | 6     | ahci       | F90168C69D |
| 8086:8d62 | 8086:7270 | Intel      | C610/X99 series chipset s... | 6     | ahci       | C04F902B93 |
| 8086:1c02 | 1028:04de | Intel      | 6 Series/C200 Series Chip... | 5     | ahci       | 0893528A1F |
| 8086:1d02 | 1014:1d02 | Intel      | C600/X79 series chipset 6... | 5     | ahci       | 1A5CF39F4F |
| 8086:8c02 | 15d9:0805 | Intel      | 8 Series/C220 Series Chip... | 5     | ahci       | 019914CC29 |
| 8086:8d02 | 15d9:0831 | Intel      | C610/X99 series chipset 6... | 5     | ahci       | 64918C950D |
| 8086:a102 | 1028:06a5 | Intel      | Q170/Q150/B150/H170/H110/... | 5     | ahci       | E2A3815DD2 |
| 8086:a182 | 15d9:096d | Intel      | C620 Series Chipset Famil... | 5     | ahci       | C8195297A4 |
| 8086:a1d2 | 15d9:096d | Intel      | C620 Series Chipset Famil... | 5     | ahci       | C8195297A4 |
| 8086:a1d2 | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 5     | ahci       | 5E1947B31A |
| 1002:4390 | 1028:0444 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 4     | ahci       | AD7D2477F8 |
| 19e5:a235 |           | Huawei ... | HiSilicon AHCI HBA           | 4     | ahci       | F548D0A0A9 |
| 1b21:0612 | 15d9:0805 | ASMedia... | ASM1062 Serial ATA Contro... | 4     | ahci       | 019914CC29 |
| 8086:1c02 | 1028:04dd | Intel      | 6 Series/C200 Series Chip... | 4     | ahci       | D52DB39EEB |
| 8086:1d02 | 8086:357e | Intel      | C600/X79 series chipset 6... | 4     | ahci       | 0FADD1EBE3 |
| 8086:1d02 | 8086:35a0 | Intel      | C600/X79 series chipset 6... | 4     | ahci       | FE1E6CFF79 |
| 8086:2922 | 8086:34d0 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 4     | ahci       | FC38CA11F5 |
| 8086:3a22 | 103c:330b | Intel      | 82801JI (ICH10 Family) SA... | 4     | ahci       | 28B04C3004 |
| 8086:3a22 | 15d9:0001 | Intel      | 82801JI (ICH10 Family) SA... | 4     | ahci       | AFA93003E2 |
| 8086:3a22 | 15d9:060f | Intel      | 82801JI (ICH10 Family) SA... | 4     | ahci       | CF99AAD395 |
| 8086:8c02 | 8086:8c02 | Intel      | 8 Series/C220 Series Chip... | 4     | ahci       | FEC09C0BAC |
| 8086:a102 | 15d9:089a | Intel      | Q170/Q150/B150/H170/H110/... | 4     | ahci       | E8634FF947 |
| 8086:a182 | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     | ahci       | E9A1FC86F9 |
| 8086:a182 | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 4     | ahci       | 5E1947B31A |
| 8086:a1d2 | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     | ahci       | E9A1FC86F9 |
| 8086:a1d2 | 1849:a1d2 | Intel      | C620 Series Chipset Famil... | 4     | ahci       | 2244EB7809 |
| 8086:a1d2 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 4     | ahci       | 36C4ACAC2D |
| 8086:a352 | 8086:7270 | Intel      | Cannon Lake PCH SATA AHCI... | 4     | ahci       | B8FFB92409 |
| 1002:4390 | 103c:176e | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 3     | ahci       | DC4AC74B49 |
| 1002:4390 | 15d9:ab11 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 3     | ahci       | D5563E325C |
| 1002:4394 | 1002:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 3     | ahci       | 578FEA3A6C |
| 1022:7901 | 1028:08ff | AMD        | FCH SATA Controller [AHCI... | 3     | ahci       | A35E7D3EB0 |
| 1b21:0625 | 1043:8634 | ASMedia... | 106x SATA/RAID Controller    | 3     | ahci       | 55BDC0F976 |
| 8086:1c02 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 3     | ahci       | 57162CA72C |
| 8086:1d02 | 1028:04ce | Intel      | C600/X79 series chipset 6... | 3     | ahci       | 7A9C742839 |
| 8086:1d02 | 1028:04f8 | Intel      | C600/X79 series chipset 6... | 3     | ahci       | 494CD954E9 |
| 8086:1d02 | 15d9:062a | Intel      | C600/X79 series chipset 6... | 3     | ahci       | 47401D66CE |
| 8086:3a22 | 15d9:0400 | Intel      | 82801JI (ICH10 Family) SA... | 3     | ahci       | D9ED4F04A3 |
| 8086:3b22 | 1028:02a6 | Intel      | 5 Series/3400 Series Chip... | 3     | ahci       | 9C8826C0D2 |
| 8086:8c02 | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 3     | ahci       | 938F3AEFA9 |
| 8086:8c02 | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 3     | ahci       | 34DBD86F7B |
| 8086:8c02 | 8086:35b5 | Intel      | 8 Series/C220 Series Chip... | 3     | ahci       | 20BB0A8951 |
| 8086:8d02 | 1028:0639 | Intel      | C610/X99 series chipset 6... | 3     | ahci       | E5766C8331 |
| 8086:8d62 | 1028:0639 | Intel      | C610/X99 series chipset s... | 3     | ahci       | E5766C8331 |
| 8086:8d62 | 15d9:0831 | Intel      | C610/X99 series chipset s... | 3     | ahci       | 64918C950D |
| 8086:8d62 | 15d9:0834 | Intel      | C610/X99 series chipset s... | 3     | ahci       | FA4BECDE8B |
| 8086:a102 | 15d9:0895 | Intel      | Q170/Q150/B150/H170/H110/... | 3     | ahci       | BE8471A6F1 |
| 8086:a182 | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     | ahci       | E752263E49 |
| 8086:a182 | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     | ahci       | 7AD1F5EB4E |
| 8086:a182 | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     | ahci       | C682299C13 |
| 8086:a182 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 3     | ahci       | 36C4ACAC2D |
| 8086:a1d2 | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     | ahci       | E752263E49 |
| 8086:a1d2 | 1043:871f | Intel      | C620 Series Chipset Famil... | 3     | ahci       | AFAB4598A7 |
| 8086:a1d2 | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     | ahci       | 7AD1F5EB4E |
| 8086:a1d2 | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     | ahci       | C682299C13 |
| 8086:a1d2 | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     | ahci       | 5658A2FB98 |
| 8086:a352 | 15d9:1a1b | Intel      | Cannon Lake PCH SATA AHCI... | 3     | ahci       | F1BF9D35EF |
| 8086:a352 | 15d9:1a1d | Intel      | Cannon Lake PCH SATA AHCI... | 3     | ahci       | E57FDAECA4 |
| 1002:4390 | 1111:077c | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 2     | ahci       | 58771D090D |
| 1002:4390 | 15d9:ba11 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 2     | ahci       | 6381FD461D |
| 1002:4390 | 15d9:cd11 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 2     | ahci       | CF37C43C55 |
| 1b21:0612 | 15d9:1b2b | ASMedia... | ASM1062 Serial ATA Contro... | 2     | ahci       | 43E601437F |
| 1b21:0612 | 1b21:1060 | ASMedia... | ASM1062 Serial ATA Contro... | 2     | ahci       | AD61EFB931 |
| 1b4b:9215 | 1b4b:9215 | Marvell... | 88SE9215 PCIe 2.0 x1 4-po... | 2     | ahci       | AFA93003E2 |
| 1b4b:9230 | 1028:1fe2 | Marvell... | 88SE9230 PCIe 2.0 x2 4-po... | 2     | ahci       | 03CC317284 |
| 8086:19b2 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 2     | ahci       | 40E07B4DAD |
| 8086:19c2 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 2     | ahci       | 40E07B4DAD |
| 8086:1ba2 | 8086:7270 | Intel      | SATA controller              | 2     | ahci       | AEAD99F55D |
| 8086:1c02 | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 2     | ahci       | E6D89DC95B |
| 8086:1d02 | 1028:04f6 | Intel      | C600/X79 series chipset 6... | 2     | ahci       | 29F49B3A79 |
| 8086:1d02 | 1028:04fe | Intel      | C600/X79 series chipset 6... | 2     | ahci       | 6877A6D4E6 |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1d00 | 103c:18a9 | Intel      | C600/X79 series chipset 4... | 24    | pata_acpi  | 7B579629BB |
| 8086:3a20 | 103c:330d | Intel      | 82801JI (ICH10 Family) 4 ... | 20    | pata_acpi  | AA46402C2B |
| 8086:2921 | 1028:0235 | Intel      | 82801IB (ICH9) 2 port SAT... | 14    | pata_acpi  | 246F93C093 |
| 8086:269e | 103c:31fe | Intel      | 631xESB/632xESB IDE Contr... | 13    | pata_acpi  | B6088E88BA |
| 8086:3b20 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 9     | ata_piix   | 56B5E62268 |
| 8086:3b26 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 9     | ata_piix   | 56B5E62268 |
| 8086:2921 | 1028:0236 | Intel      | 82801IB (ICH9) 2 port SAT... | 8     | pata_acpi  | 26944912D7 |
| 8086:3a20 | 1014:3a20 | Intel      | 82801JI (ICH10 Family) 4 ... | 8     | pata_acpi  | B4A013EED4 |
| 8086:a1bc | 1028:073a | Intel      | C620 Series Chipset Famil... | 8     | pata_acpi  | C7D795E2A5 |
| 197b:2368 | 197b:2368 | JMicron... | JMB368 IDE controller        | 6     | pata_jm... | 535E5F1D58 |
| 8086:3a26 | 1014:3a26 | Intel      | 82801JI (ICH10 Family) 2 ... | 6     | pata_acpi  | B4A013EED4 |
| 8086:1d08 | 103c:18a9 | Intel      | C600/X79 series chipset 2... | 5     | ata_pii... | 1E7A730FCC |
| 8086:2921 | 1028:0237 | Intel      | 82801IB (ICH9) 2 port SAT... | 5     | ata_piix   | 46D07193B2 |
| 8086:3a20 | 8086:34dc | Intel      | 82801JI (ICH10 Family) 4 ... | 5     | pata_acpi  | 61DFD26E01 |
| 8086:3a20 | 8086:34e2 | Intel      | 82801JI (ICH10 Family) 4 ... | 5     | pata_acpi  | FDCE629C37 |
| 8086:3a26 | 8086:34dc | Intel      | 82801JI (ICH10 Family) 2 ... | 5     | pata_acpi  | 61DFD26E01 |
| 8086:3a26 | 8086:34e2 | Intel      | 82801JI (ICH10 Family) 2 ... | 5     | pata_acpi  | FDCE629C37 |
| 1002:439c | 15d9:ab11 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 4     | pata_at... | D5563E325C |
| 1002:439c | 15d9:bc11 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 4     | pata_at... | 1FE97B31A1 |
| 8086:269e | 1028:01b2 | Intel      | 631xESB/632xESB IDE Contr... | 4     | pata_acpi  | 252659BF58 |
| 8086:269e | 8086:3476 | Intel      | 631xESB/632xESB IDE Contr... | 4     | pata_acpi  | 38109F9919 |
| 8086:27c0 | 1028:01e7 | Intel      | NM10/ICH7 Family SATA Con... | 4     | pata_acpi  | EA66809CE7 |
| 8086:27df | 1028:01e7 | Intel      | 82801G (ICH7 Family) IDE ... | 4     | pata_acpi  | EA66809CE7 |
| 8086:3a20 | 1028:028c | Intel      | 82801JI (ICH10 Family) 4 ... | 4     | pata_acpi  | F46A021C88 |
| 8086:3a20 | 15d9:0400 | Intel      | 82801JI (ICH10 Family) 4 ... | 4     | ata_pii... | AD4ABE60CD |
| 8086:3a20 | 15d9:0600 | Intel      | 82801JI (ICH10 Family) 4 ... | 4     | pata_acpi  | ACA2A2FFDF |
| 8086:3a20 | 8086:34da | Intel      | 82801JI (ICH10 Family) 4 ... | 4     | pata_acpi  | FE3D758C20 |
| 8086:3a20 | 8086:3a20 | Intel      | 82801JI (ICH10 Family) 4 ... | 4     | pata_acpi  | 6B7A9D9BDB |
| 8086:3a26 | 1028:028c | Intel      | 82801JI (ICH10 Family) 2 ... | 4     | pata_acpi  | F46A021C88 |
| 8086:3a26 | 15d9:0400 | Intel      | 82801JI (ICH10 Family) 2 ... | 4     | ata_pii... | AD4ABE60CD |
| 8086:3a26 | 15d9:0600 | Intel      | 82801JI (ICH10 Family) 2 ... | 4     | pata_acpi  | ACA2A2FFDF |
| 8086:3a26 | 8086:34da | Intel      | 82801JI (ICH10 Family) 2 ... | 4     | pata_acpi  | FE3D758C20 |
| 8086:3a26 | 8086:3a26 | Intel      | 82801JI (ICH10 Family) 2 ... | 4     | pata_acpi  | 6B7A9D9BDB |
| 8086:a1bc | 1028:0739 | Intel      | C620 Series Chipset Famil... | 4     | pata_acpi  | 9E01FD5E8C |
| 1002:439c | 103c:1773 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 3     | pata_at... | DC4AC74B49 |
| 1002:439c | 103c:3338 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 3     | pata_at... | 91AD975174 |
| 8086:2680 | 1028:01b3 | Intel      | 631xESB/632xESB/3100 Chip... | 3     | pata_acpi  | 8571D09FE7 |
| 8086:269e | 8086:3486 | Intel      | 631xESB/632xESB IDE Contr... | 3     | pata_acpi  | 0A3F6D305B |
| 8086:3a20 | 1028:028d | Intel      | 82801JI (ICH10 Family) 4 ... | 3     | ata_pii... | 1A05144C7E |
| 8086:3a20 | 1028:02d4 | Intel      | 82801JI (ICH10 Family) 4 ... | 3     | pata_acpi  | 26B693742E |
| 8086:3a20 | 1734:1150 | Intel      | 82801JI (ICH10 Family) 4 ... | 3     | pata_acpi  | 43C0756BA6 |
| 8086:3a26 | 1028:028d | Intel      | 82801JI (ICH10 Family) 2 ... | 3     | ata_pii... | 1A05144C7E |
| 8086:3a26 | 1734:114d | Intel      | 82801JI (ICH10 Family) 2 ... | 3     | pata_acpi  | 43C0756BA6 |
| 8086:a1bc | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     | pata_acpi  | 5658A2FB98 |
| 1002:439c | 1111:077c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 2     | pata_at... | 58771D090D |
| 1002:439c | 15d9:a811 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 2     | pata_at... | 201AA7046E |
| 1002:439c | 15d9:ba11 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 2     | pata_at... | 6381FD461D |
| 1002:439c | 15d9:cd11 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 2     | pata_at... | CF37C43C55 |
| 10de:036e | 1462:cb84 | Nvidia     | MCP55 IDE                    | 2     | pata_am... | B8300AFB35 |
| 10de:037f | 1462:cb84 | Nvidia     | MCP55 SATA Controller        | 2     | sata_nv... | B8300AFB35 |
| 8086:1c00 | 1043:8498 | Intel      | 6 Series/C200 Series Chip... | 2     | pata_acpi  | 750A124EF3 |
| 8086:1c08 | 1043:8497 | Intel      | 6 Series/C200 Series Chip... | 2     | pata_acpi  | 750A124EF3 |
| 8086:1d00 | 1028:04cf | Intel      | C600/X79 series chipset 4... | 2     | pata_acpi  | D350652289 |
| 8086:1d08 | 1028:04cf | Intel      | C600/X79 series chipset 2... | 2     | pata_acpi  | D350652289 |
| 8086:24db | 1028:016d | Intel      | 82801EB/ER (ICH5/ICH5R) I... | 2     | ata_pii... | 08919C80E8 |
| 8086:2680 | 1014:02dd | Intel      | 631xESB/632xESB/3100 Chip... | 2     | ata_pii... | 3A68279F78 |
| 8086:2680 | 1028:01b2 | Intel      | 631xESB/632xESB/3100 Chip... | 2     | pata_acpi  | 1C2A92612A |
| 8086:2680 | 1028:01f0 | Intel      | 631xESB/632xESB/3100 Chip... | 2     | ata_pii... | E36BFCD946 |
| 8086:2680 | 1734:1090 | Intel      | 631xESB/632xESB/3100 Chip... | 2     | pata_acpi  | 872AE76863 |
| 8086:2680 | 8086:3476 | Intel      | 631xESB/632xESB/3100 Chip... | 2     | ata_pii... | 0E19261B88 |
| 8086:269e | 1028:01b3 | Intel      | 631xESB/632xESB IDE Contr... | 2     | pata_acpi  | CA9524A167 |
| 8086:269e | 1734:1090 | Intel      | 631xESB/632xESB IDE Contr... | 2     | pata_acpi  | 872AE76863 |
| 8086:269e | 8086:3472 | Intel      | 631xESB/632xESB IDE Contr... | 2     | ata_piix   | 715B40D8B6 |
| 8086:2920 | 8086:34d0 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 2     | pata_acpi  | 81A05F54F2 |
| 8086:2921 | 1028:029b | Intel      | 82801IB (ICH9) 2 port SAT... | 2     | ata_piix   | 1F6AFDC077 |
| 8086:2926 | 8086:34d0 | Intel      | 82801I (ICH9 Family) 2 po... | 2     | pata_acpi  | 81A05F54F2 |
| 8086:3a20 | 1028:02d3 | Intel      | 82801JI (ICH10 Family) 4 ... | 2     | pata_acpi  | C3EC3FCF73 |
| 8086:3a20 | 1033:8372 | Intel      | 82801JI (ICH10 Family) 4 ... | 2     | pata_acpi  | 460A274240 |
| 8086:3a20 | 15d9:0100 | Intel      | 82801JI (ICH10 Family) 4 ... | 2     | pata_acpi  | 0B2E10175B |
| 8086:3a26 | 1033:8372 | Intel      | 82801JI (ICH10 Family) 2 ... | 2     | pata_acpi  | 460A274240 |
| 8086:3a26 | 15d9:0100 | Intel      | 82801JI (ICH10 Family) 2 ... | 2     | pata_acpi  | 0B2E10175B |
| 8086:3b20 | 1014:0377 | Intel      | 5 Series/3400 Series Chip... | 2     | ata_pii... | EE06305E30 |
| 8086:3b20 | 1028:02a3 | Intel      | 5 Series/3400 Series Chip... | 2     | pata_acpi  | 07FABCF50F |
| 8086:3b26 | 1014:0377 | Intel      | 5 Series/3400 Series Chip... | 2     | ata_pii... | EE06305E30 |
| 8086:3b26 | 1028:02a3 | Intel      | 5 Series/3400 Series Chip... | 2     | pata_acpi  | 07FABCF50F |
| 1002:439c | 1002:439c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | pata_at... | 368A801F1A |
| 1002:439c | 1028:0489 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | pata_at... | 0335142464 |
| 1002:439c | 15d9:a711 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | pata_at... | CFFE15A3E5 |
| 1002:439c | 15d9:ca11 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | pata_at... | 9712585D1C |
| 10de:0053 | 10f1:2891 | Nvidia     | CK804 IDE                    | 1     | pata_am... | 64251B3F2A |
| 10de:0053 | 10f1:2895 | Nvidia     | CK804 IDE                    | 1     | pata_amd   | 768571B831 |
| 10de:0054 | 10de:cb84 | Nvidia     | CK804 Serial ATA Controller  | 1     | sata_nv    | 64251B3F2A |
| 10de:0054 | 10f1:2895 | Nvidia     | CK804 Serial ATA Controller  | 1     | sata_nv    | 768571B831 |
| 10de:0055 | 10de:cb84 | Nvidia     | CK804 Serial ATA Controller  | 1     | sata_nv    | 64251B3F2A |
| 10de:0055 | 10f1:2895 | Nvidia     | CK804 Serial ATA Controller  | 1     | sata_nv    | 768571B831 |
| 10de:036e | 108e:534b | Nvidia     | MCP55 IDE                    | 1     | pata_am... | E54A36A0C4 |
| 10de:036e | 108e:534d | Nvidia     | MCP55 IDE                    | 1     | pata_am... | 1F35F79302 |
| 10de:036e | 1462:2800 | Nvidia     | MCP55 IDE                    | 1     | pata_am... | 933EED177A |
| 10de:037f | 108e:534b | Nvidia     | MCP55 SATA Controller        | 1     | sata_nv... | E54A36A0C4 |
| 10de:037f | 108e:534d | Nvidia     | MCP55 SATA Controller        | 1     | sata_nv... | 1F35F79302 |
| 10de:037f | 1462:2800 | Nvidia     | MCP55 SATA Controller        | 1     | sata_nv... | 933EED177A |
| 1166:0211 |           | Broadcom   | OSB4 IDE Controller          | 1     | pata_se... | 0B5D843F10 |
| 1166:0212 | 1166:0212 | Broadcom   | CSB5 IDE Controller          | 1     | pata_se... | 46973B5B05 |
| 1166:0214 | 1028:0205 | Broadcom   | BCM5785 [HT1000] IDE         | 1     | pata_se... | B7596E9C0E |
| 1166:0214 | 103c:320b | Broadcom   | BCM5785 [HT1000] IDE         | 1     | pata_se... | 5AB62504F8 |
| 1166:0214 | 1734:10b9 | Broadcom   | BCM5785 [HT1000] IDE         | 1     | pata_se... | A0F9679F57 |
| 1166:024b | 1028:0205 | Broadcom   | BCM5785 [HT1000] SATA (PA... | 1     | sata_sv... | B7596E9C0E |
| 1166:024b | 1166:024b | Broadcom   | BCM5785 [HT1000] SATA (PA... | 1     | sata_sv... | A0F9679F57 |
| 197b:2363 | 197b:2363 | JMicron... | JMB363 SATA/IDE Controller   | 1     | pata_jm... | 4DC142D672 |
| 1b21:0624 | 1b21:1060 | ASMedia... | 106x SATA/RAID Controller    | 1     |            | 10F1608197 |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 41    | nvme       | A9C87C6C9C |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 11    | nvme       | 5E9110EE62 |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 8     | nvme       | 5F7514110B |
| 14a4:2300 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 6     | nvme       | 4391DFF8D2 |
| 8086:0a54 | 8086:4802 | Intel      | NVMe Datacenter SSD [3DNA... | 6     | nvme       | C6E1E678F5 |
| 15b7:5009 | 15b7:5009 | Sandisk    | WD Blue SN550 NVMe SSD       | 4     | nvme       | 8D55479353 |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 4     | nvme       | 55BDC0F976 |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 3     | nvme       | 21124E85CC |
| 1344:5405 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 2     | nvme       | C3665EBF57 |
| 144d:a80a | 144d:a801 | Samsung... | NVMe SSD Controller PM9A1... | 2     | nvme       | AEAD99F55D |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/SN750 / PC ... | 2     | nvme       | F6F6B1BC99 |
| 15b7:5006 | 15b7:5006 | Sandisk    | WD Black SN750 / PC SN730... | 2     | nvme       | 6877A6D4E6 |
| 1987:5016 | 1987:5016 | Phison ... | E16 PCIe4 NVMe Controller    | 2     | nvme       | 29F49B3A79 |
| 8086:0a54 | 8086:4714 | Intel      | NVMe Datacenter SSD [3DNA... | 2     | nvme       | D373AF93CD |
| 8086:2700 | 8086:3900 | Intel      | Optane SSD 900P Series       | 2     | nvme       | 376BED560D |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 2     | nvme       | AAEEE85BE7 |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 1     | nvme       | 3514F18D29 |
| 1179:011a | 1179:0001 | Toshiba... | XG6 NVMe SSD Controller      | 1     | nvme       | C8F90792EC |
| 126f:2260 | 126f:2260 | Silicon... | Non-Volatile memory contr... | 1     | nvme       | DB4185737E |
| 126f:2262 | 126f:2262 | Silicon... | SM2262/SM2262EN SSD Contr... | 1     | nvme       | 6BE87AB445 |
| 126f:2263 | 126f:2263 | Silicon... | SM2263EN/SM2263XT SSD Con... | 1     | nvme       | 0C9DFEB831 |
| 1344:51b2 | 1344:5000 | Micron ... | Non-Volatile memory contr... | 1     | nvme       | FEE94D715D |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 1     | nvme       | AC7F5D0860 |
| 144d:a809 | 144d:a801 | Samsung... | NVMe SSD Controller 980      | 1     | nvme       | FEE94D715D |
| 144d:a821 | 108e:a803 | Samsung... | NVMe SSD Controller 172X     | 1     | nvme       | FDC516788A |
| 144d:a822 | 1028:1ff7 | Samsung... | NVMe SSD Controller 172Xa... | 1     | nvme       | E9A1FC86F9 |
| 144d:a822 | 144d:a80b | Samsung... | NVMe SSD Controller 172Xa... | 1     | nvme       | 04144B327A |
| 144d:a824 | 1028:2071 | Samsung... | NVMe SSD Controller PM173X   | 1     | nvme       | B7AC531BF5 |
| 144d:a824 | 144d:a801 | Samsung... | NVMe SSD Controller PM173X   | 1     | nvme       | 4231BB05CE |
| 14a4:22f1 | 1b4b:1093 | Lite-On... | M8Pe Series NVMe SSD         | 1     | nvme       | 1AFA47E662 |
| 1987:5007 | 1987:5007 | Phison ... | E7 NVMe Controller           | 1     | nvme       | BB8832ACBD |
| 19e5:3714 | 19e5:5123 | Huawei ... | ES3000 V5 NVMe PCIe SSD      | 1     | nvme       | A17BEFC33B |
| 19e5:3714 | 19e5:5312 | Huawei ... | ES3000 V5 NVMe PCIe SSD      | 1     | nvme       | 3CA7825025 |
| 1b4b:1160 | 1b4b:1160 | Marvell... | Marvell Non-Volatile memo... | 1     | nvme       | 375EC8881D |
| 1b96:2200 | 1b96:0000 | Western... | Ultrastar DC SN630 NVMe SSD  | 1     | nvme       | 0627DB12DF |
| 1b96:2400 | 1b96:0000 | Western... | Ultrastar DC SN640 NVMe SSD  | 1     | nvme       | 66EE0BC524 |
| 1bb1:0100 | 1bb1:0121 | Seagate... | Nytro Flash Storage          | 1     | nvme       | 869C99ACED |
| 1bb1:5012 | 1bb1:5012 | Seagate... | FireCuda 510 SSD             | 1     | nvme       | 937DE612E9 |
| 1bb1:5016 | 1bb1:5016 | Seagate... | FireCuda 520 SSD             | 1     | nvme       | 86AB491564 |
| 1d97:2263 | 1d97:2263 | Shenzhe... | SM2263EN/SM2263XT-based O... | 1     | nvme       | BE2298910B |
| 1dee:2262 | 1dee:1dee | Biwin S... | Non-Volatile memory contr... | 1     | nvme       | 6BE87AB445 |
| 1dee:2263 | 1dee:1dee | Biwin S... | Non-Volatile memory contr... | 1     | nvme       | 0C59EA1474 |
| 2646:5008 | 2646:5008 | Kingsto... | U-SNS8154P3 NVMe SSD         | 1     | nvme       | 947E0AEF4A |
| 2646:500f | 2646:500f | Kingsto... | Technology Company Non-Vo... | 1     | nvme       | A9C87C6C9C |
| 8086:0953 | 8086:3702 | Intel      | PCIe Data Center SSD         | 1     | nvme       | 64918C950D |
| 8086:0953 | 8086:3704 | Intel      | PCIe Data Center SSD         | 1     | nvme       | 5F6D0233A8 |
| 8086:0953 | 8086:3705 | Intel      | PCIe Data Center SSD         | 1     | nvme       | F3A274A366 |
| 8086:0953 | 8086:3708 | Intel      | PCIe Data Center SSD         | 1     | nvme       | 971A75C8ED |
| 8086:0953 | 8086:3709 | Intel      | PCIe Data Center SSD         | 1     | nvme       | 2F38C3FD0E |
| 8086:0a53 | 8086:3705 | Intel      | DC P3520 SSD                 | 1     | nvme       | C682299C13 |
| 8086:0a54 | 8086:4702 | Intel      | NVMe Datacenter SSD [3DNA... | 1     | nvme       | 755B723BB0 |
| 8086:0a54 | 8086:4703 | Intel      | NVMe Datacenter SSD [3DNA... | 1     | nvme       | 36C4ACAC2D |
| 8086:0a54 | 8086:4805 | Intel      | NVMe Datacenter SSD [3DNA... | 1     | nvme       | EB0C95C2B3 |
| 8086:2701 | 8086:3904 | Intel      | NVMe Datacenter SSD [Optane] | 1     | nvme       | 64918C950D |
| 8086:2701 | 8086:3907 | Intel      | NVMe Datacenter SSD [Optane] | 1     | nvme       | 6BE87AB445 |
| 8086:faf0 | 8086:390e | Intel      | Non-Volatile memory contr... | 1     | nvme       | CAC1B04E1E |
| c0a9:540a | c0a9:540a | Micron/... | P2 NVMe PCIe SSD             | 1     | nvme       | D3DC168A2A |
| cc53:0001 | cc53:0100 | ScaleFlux  | Non-Volatile memory contr... | 1     |            | 9CC6367D9F |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 103c:323a | 103c:3245 | Hewlett... | Smart Array G6 controllers   | 38    | hpsa       | A9C87C6C9C |
| 103c:323b | 103c:3354 | Hewlett... | Smart Array Gen8 Controllers | 26    | hpsa       | 7B579629BB |
| 1000:0079 | 1028:1f17 | LSI Log... | MegaRAID SAS 2108 [Libera... | 20    | megarai... | 246F93C093 |
| 1000:0060 | 1028:1f0c | LSI Log... | MegaRAID SAS 1078            | 17    | megarai... | 26944912D7 |
| 1000:005d | 1000:9363 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 16    | megarai... | 2F38C3FD0E |
| 1000:005f | 1028:1f44 | LSI Log... | MegaRAID SAS-3 3008 [Fury]   | 14    | megarai... | FE43558C7A |
| 1000:005d | 15d9:0809 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 10    | megarai... | CC00646768 |
| 8086:201d | 8086:0000 | Intel      | Volume Management Device ... | 10    | vmd        | C7D795E2A5 |
| 1000:005b | 1028:1f38 | LSI Log... | MegaRAID SAS 2208 [Thunde... | 8     | megarai... | 3BCB61F70C |
| 1000:0079 | 1000:9263 | LSI Log... | MegaRAID SAS 2108 [Libera... | 8     | megarai... | 579D962F08 |
| 103c:323b | 103c:3351 | Hewlett... | Smart Array Gen8 Controllers | 8     | hpsa       | CD543E37E2 |
| 1000:005d | 1028:1f49 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 7     | megarai... | E4DEE6FAF7 |
| 103c:3230 | 103c:3234 | Hewlett... | Smart Array Controller       | 7     | hpsa       | B6088E88BA |
| 17d3:1880 | 17d3:1883 | Areca T... | ARC-188x series PCIe 2.0/... | 7     | arcmsr     | 96079334BD |
| 8086:2826 | 1028:073a | Intel      | C600/X79 series chipset S... | 7     | ahci       | C7D795E2A5 |
| 1000:005b | 1028:1f35 | Broadco... | MegaRAID SAS 2208 [Thunde... | 6     | megarai... | 87A79FD79B |
| 1000:005d | 1028:1f42 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 6     | megarai... | E757687F86 |
| 1000:005d | 1028:1f47 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 6     | megarai... | 9320E12A9A |
| 1000:0060 | 1028:1f0b | LSI Log... | MegaRAID SAS 1078            | 6     | megarai... | 2A289951DE |
| 103c:3239 | 103c:21c0 | Hewlett... | Smart Array Gen9 Controllers | 6     | hpsa       | 23F12250E5 |
| 1000:0014 | 1d49:0602 | Broadco... | MegaRAID Tri-Mode SAS3516    | 5     | megarai... | CEE7ED2CE9 |
| 1000:005f | 1028:1f4b | LSI Log... | MegaRAID SAS-3 3008 [Fury]   | 5     | megarai... | F3CBAC183E |
| 1000:0073 | 1028:1f51 | LSI Log... | MegaRAID SAS 2008 [Falcon]   | 5     | megarai... | 494CD954E9 |
| 1b4b:9485 | 1b4b:9480 | Marvell... | 88SE9485 SAS/SATA 6Gb/s c... | 5     | mvsas      | AAEEE85BE7 |
| 1000:0016 | 1028:1fcd | LSI Log... | MegaRAID Tri-Mode SAS3508    | 4     | megarai... | E9A1FC86F9 |
| 1000:0016 | 19e5:d215 | Broadco... | MegaRAID Tri-Mode SAS3508    | 4     | megarai... | AD903545CE |
| 1000:005b | 1014:040b | LSI Log... | MegaRAID SAS 2208 [Thunde... | 4     | megarai... | 8D55479353 |
| 1000:005b | 1028:1f34 | LSI Log... | MegaRAID SAS 2208 [Thunde... | 4     | megarai... | D1FAA99D53 |
| 1000:005b | 8086:3510 | LSI Log... | MegaRAID SAS 2208 [Thunde... | 4     | megarai... | FE1E6CFF79 |
| 1000:005d | 1000:9361 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 4     | megarai... | 8D109AC7B4 |
| 1000:0060 | 1734:10f9 | Broadco... | MegaRAID SAS 1078            | 4     | megarai... | 4874F3ABB6 |
| 1000:0079 | 1028:1f16 | Broadco... | MegaRAID SAS 2108 [Libera... | 4     | megarai... | F46A021C88 |
| 103c:3230 | 103c:3235 | Hewlett... | Smart Array Controller       | 4     | hpsa       | 58C9A1D28B |
| 1000:0016 | 1028:1fcb | LSI Log... | MegaRAID Tri-Mode SAS3508    | 3     | megarai... | AD7D2477F8 |
| 1000:005b | 1028:1f31 | Broadco... | MegaRAID SAS 2208 [Thunde... | 3     | megarai... | 6877A6D4E6 |
| 1000:005d | 1014:0454 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 3     | megarai... | C7B39E92CA |
| 1000:0079 | 1014:03b2 | LSI Log... | MegaRAID SAS 2108 [Libera... | 3     | megarai... | B4A013EED4 |
| 1028:0015 | 1028:1f03 | Dell       | PowerEdge Expandable RAID... | 3     | megarai... | AE126E5F79 |
| 103c:323a | 103c:3243 | Hewlett... | Smart Array G6 controllers   | 3     | hpsa       | 28B04C3004 |
| 13c1:1003 | 13c1:1003 | 3ware      | 9550SX SATA-II RAID PCI-X    | 3     | 3w_9xxx    | 0A3F6D305B |
| 17d3:1880 | 17d3:1880 | Areca T... | ARC-188x series PCIe 2.0/... | 3     | arcmsr     | B3C09674CF |
| 8086:201d | 1043:875d | Intel      | Volume Management Device ... | 3     | vmd        | E4BE3F2344 |
| 8086:2826 | 1028:0739 | Intel      | C600/X79 series chipset S... | 3     | ahci       | 52B7CECCFF |
| 8086:2826 | 103c:81c7 | Intel      | C600/X79 series chipset S... | 3     | ahci       | 5299B4DA87 |
| 8086:2827 | 103c:81c6 | Intel      | C610/X99 series chipset s... | 3     | ahci       | 679871CFEC |
| 8086:2827 | 103c:81c7 | Intel      | C610/X99 series chipset s... | 3     | ahci       | 5299B4DA87 |
| 1000:0014 | 1028:1f3b | Broadco... | MegaRAID Tri-Mode SAS3516    | 2     | megarai... | A35E7D3EB0 |
| 1000:0016 | 1d49:0601 | Broadco... | MegaRAID Tri-Mode SAS3508    | 2     | megarai... | 2AE35CF194 |
| 1000:005b | 1000:9271 | Broadco... | MegaRAID SAS 2208 [Thunde... | 2     | megarai... | 57E5191283 |
| 1000:005d | 8086:351e | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 2     | megarai... | D373AF93CD |
| 1000:005f | 1014:0456 | LSI Log... | MegaRAID SAS-3 3008 [Fury]   | 2     | megarai... | C7B39E92CA |
| 1000:0072 | 1000:0072 | LSI Log... | SAS2008 PCI-Express Fusio... | 2     | mpt3sas    | 368A801F1A |
| 1000:0072 | 1028:1f51 | LSI Log... | SAS2008 PCI-Express Fusio... | 2     | mpt3sas    | 31EA0B6D96 |
| 1000:0073 | 1014:040d | Broadco... | MegaRAID SAS 2008 [Falcon]   | 2     | megarai... | A4B7DEFC78 |
| 1000:0073 | 1028:1f4e | Broadco... | MegaRAID SAS 2008 [Falcon]   | 2     | megarai... | EB7B7FD10B |
| 1000:0079 | 1000:9260 | LSI Log... | MegaRAID SAS 2108 [Libera... | 2     | megarai... | 376BED560D |
| 1000:0079 | 15d9:0700 | Broadco... | MegaRAID SAS 2108 [Libera... | 2     | megarai... | 096D3E62FE |
| 1028:0013 | 1028:016d | Dell       | PowerEdge Expandable RAID... | 2     | megarai... | 08919C80E8 |
| 1028:0016 | 1028:1f24 | Dell       | PowerEdge Expandable RAID... | 2     |            | 650772B11D |
| 103c:3238 | 103c:3211 | Hewlett... | Smart Array E200i (SAS Co... | 2     | cciss      | B3175C4255 |
| 103c:3239 | 103c:21c7 | Hewlett... | Smart Array Gen9 Controllers | 2     | hpsa       | 5E1947B31A |
| 103c:323b | 103c:3350 | Hewlett... | Smart Array Gen8 Controllers | 2     | hpsa       | 9E2CA41ABB |
| 103c:323b | 103c:3355 | Hewlett... | Smart Array Gen8 Controllers | 2     | hpsa       | C2075DC2CE |
| 1590:0045 | 1590:0045 | Hewlett... | RAID bus controller          | 2     |            | 3FAC52AF81 |
| 17d3:1880 | 17d3:1882 | Areca T... | ARC-188x series PCIe 2.0/... | 2     | arcmsr     | FE1E6CFF79 |
| 8086:3b25 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 2     | ahci       | 0A8BFA9B71 |
| 8086:a356 | 1028:088e | Intel      | 300 Series Chipset Family... | 2     | ahci       | 2A87802C58 |
| 9005:0285 | 9005:02d1 | Adaptec    | AAC-RAID                     | 2     | aacraid    | 591107EC98 |
| 9005:0285 | 9005:02d8 | Adaptec    | AAC-RAID                     | 2     | aacraid    | 451F363726 |
| 9005:0286 | 1014:9580 | Adaptec    | AAC-RAID (Rocket)            | 2     | aacraid    | 3A68279F78 |
| 1000:0010 | 0e11:4040 | Broadco... | 53C1510                      | 1     |            | 0B5D843F10 |
| 1000:0014 | 1000:9460 | Broadco... | MegaRAID Tri-Mode SAS3516    | 1     | megarai... | 33FDE2B5FB |
| 1000:0014 | 1000:9467 | Broadco... | MegaRAID Tri-Mode SAS3516    | 1     | megarai... | 2175466EA1 |
| 1000:0017 | 1000:9440 | Broadco... | MegaRAID Tri-Mode SAS3408    | 1     | megarai... | 43E601437F |
| 1000:0017 | 1000:9441 | Broadco... | MegaRAID Tri-Mode SAS3408    | 1     | megarai... | 1567EFE934 |
| 1000:005b | 1000:9276 | LSI Log... | MegaRAID SAS 2208 [Thunde... | 1     | megarai... | 5F9F099F36 |
| 1000:005b | 1000:9285 | Broadco... | MegaRAID SAS 2208 [Thunde... | 1     | megarai... | 7A9C742839 |
| 1000:005b | 1000:9288 | Broadco... | MegaRAID SAS 2208 [Thunde... | 1     | megarai... | C682299C13 |
| 1000:005b | 1014:0412 | Broadco... | MegaRAID SAS 2208 [Thunde... | 1     | megarai... | 1A5CF39F4F |
| 1000:005b | 1014:041d | Broadco... | MegaRAID SAS 2208 [Thunde... | 1     | megarai... | 8538814CD6 |
| 1000:005b | 1014:0448 | Broadco... | MegaRAID SAS 2208 [Thunde... | 1     | megarai... | 7C109612B9 |
| 1000:005b | 1028:1f77 | Broadco... | MegaRAID SAS 2208 [Thunde... | 1     | megarai... | A98D12AD3E |
| 1000:005d | 1028:1f43 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | megarai... | 031D1E0BEC |
| 1000:005d | 1043:8666 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | megarai... | AFAB4598A7 |
| 1000:005d | 19e5:d207 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | megarai... | 5EB4DFC951 |
| 1000:005d | 1d49:0600 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | megarai... | 928EE22E71 |
| 1000:005d | 8086:9362 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | megarai... | 2794B14FEE |
| 1000:005f | 1000:9341 | LSI Log... | MegaRAID SAS-3 3008 [Fury]   | 1     | megarai... | 64918C950D |
| 1000:005f | 1000:9343 | Broadco... | MegaRAID SAS-3 3008 [Fury]   | 1     | megarai... | 4E379512D0 |
| 1000:0060 | 1000:100a | Broadco... | MegaRAID SAS 1078            | 1     | megarai... | 5C3DF14DAD |
| 1000:0060 | 1000:1013 | Broadco... | MegaRAID SAS 1078            | 1     | megarai... | 535E5F1D58 |
| 1000:0073 | 1000:9240 | Broadco... | MegaRAID SAS 2008 [Falcon]   | 1     | megarai... | B273789224 |
| 1000:0073 | 1000:9241 | LSI Log... | MegaRAID SAS 2008 [Falcon]   | 1     | megarai... | B5E13C32D7 |
| 1000:0073 | 1014:03b1 | LSI Log... | MegaRAID SAS 2008 [Falcon]   | 1     | megarai... | BE2298910B |
| 1000:0073 | 8086:9240 | Broadco... | MegaRAID SAS 2008 [Falcon]   | 1     | megarai... | E06B230F3D |
| 1000:0079 | 1000:9254 | Broadco... | MegaRAID SAS 2108 [Libera... | 1     | megarai... | FEC09C0BAC |
| 1000:0079 | 1000:9261 | LSI Log... | MegaRAID SAS 2108 [Libera... | 1     | megarai... | 9762DCCBE9 |
| 1000:0079 | 1734:1176 | Broadco... | MegaRAID SAS 2108 [Libera... | 1     | megarai... | E6D89DC95B |
| 1000:0079 | 8086:9260 | Broadco... | MegaRAID SAS 2108 [Libera... | 1     | megarai... | 1BEF5D0065 |
| 1000:0411 | 1734:1081 | Broadco... | MegaRAID SAS 1068            | 1     | megarai... | 1A0DFE074E |

### Storage/sas (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1000:0072 | 1028:1f1c | LSI Log... | SAS2008 PCI-Express Fusio... | 10    | mpt3sas    | C7B39E92CA |
| 8086:1d6b | 1043:84ef | Intel      | C602 chipset 4-Port SATA ... | 10    | isci       | A4C832AB44 |
| 1000:0072 | 15d9:0400 | Broadco... | SAS2008 PCI-Express Fusio... | 9     | mpt3sas    | DABCC72257 |
| 1000:0072 | 1000:3020 | LSI Log... | SAS2008 PCI-Express Fusio... | 8     | mpt3sas    | 580838BF3C |
| 1000:0072 | 1028:1f1d | LSI Log... | SAS2008 PCI-Express Fusio... | 5     | mpt3sas    | B23B38CFA6 |
| 1000:0072 | 1028:1f1e | Broadco... | SAS2008 PCI-Express Fusio... | 5     | mpt3sas    | 0335142464 |
| 19e5:a230 |           | Huawei ... | HiSilicon SAS 3.0 HBA        | 4     | hisi_sa... | F548D0A0A9 |
| 8086:1d6b | 8086:35a1 | Intel      | C602 chipset 4-Port SATA ... | 4     | isci       | FE1E6CFF79 |
| 9005:028f | 103c:0602 | Adaptec    | Smart Storage PQI SAS        | 4     | smartpqi   | 7AB4F05613 |
| 1000:0072 | 1000:3040 | LSI Log... | SAS2008 PCI-Express Fusio... | 3     | mpt3sas    | 61DFD26E01 |
| 1000:0097 | 1000:30e0 | LSI Log... | SAS3008 PCI-Express Fusio... | 3     | mpt3sas    | F9D5463C17 |
| 1000:0097 | 15d9:0808 | Broadco... | SAS3008 PCI-Express Fusio... | 3     | mpt3sas    | 3CFD00A1CD |
| 1000:0070 | 1000:3010 | LSI Log... | SAS2004 PCI-Express Fusio... | 2     | mpt3sas    | 4CE6A061A6 |
| 1000:0086 | 15d9:0691 | Broadco... | SAS2308 PCI-Express Fusio... | 2     | mpt3sas    | F9D5463C17 |
| 1000:0087 | 1000:3040 | LSI Log... | SAS2308 PCI-Express Fusio... | 2     | mpt3sas    | 9FC500CA2E |
| 1000:0097 | 1000:0090 | Broadco... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | 2903921AEB |
| 1000:0097 | 1028:1f53 | Broadco... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | DF9A63BE43 |
| 8086:1d6b | 1170:0054 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 1B5977B024 |
| 8086:1d6b | 15d9:0636 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | DD93F62FFC |
| 8086:1d6b | 15d9:0660 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | AFE42B7E58 |
| 1000:005d | 8086:3a1e | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | megarai... | 98C12554CB |
| 1000:0064 | 1000:3030 | Broadco... | SAS2116 PCI-Express Fusio... | 1     | mpt3sas    | 32951A000F |
| 1000:0064 | 1000:30d0 | Broadco... | SAS2116 PCI-Express Fusio... | 1     | mpt3sas    | 31EA0B6D96 |
| 1000:0064 | 15d9:083c | LSI Log... | SAS2116 PCI-Express Fusio... | 1     | mpt3sas    | DB25C87154 |
| 1000:0070 | 1014:03f7 | LSI Log... | SAS2004 PCI-Express Fusio... | 1     | mpt2sas    | D7CBC31CEE |
| 1000:0070 | 1014:03f8 | Broadco... | SAS2004 PCI-Express Fusio... | 1     | mpt2sas    | 7C109612B9 |
| 1000:0072 | 1000:3050 | LSI Log... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | 0B2E10175B |
| 1000:0072 | 1000:3060 | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | D52DB39EEB |
| 1000:0072 | 1014:03cb | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | 2B9980B42B |
| 1000:0072 | 1170:6019 | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | 395F17CE3F |
| 1000:007e | 1000:0507 | Broadco... | SSS6200 PCI-Express Flash... | 1     | mpt3sas    | BA4FFBDA6D |
| 1000:0087 | 1000:0087 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | BA0F3C3B41 |
| 1000:0087 | 1000:3020 | LSI Log... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | 7DC714253B |
| 1000:0087 | 1028:1f34 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | FBDF83F7FF |
| 1000:0087 | 1028:1f35 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | C9C876F0E7 |
| 1000:0087 | 1028:1f38 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | 29F49B3A79 |
| 1000:0087 | 1590:0042 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | A14015F487 |
| 1000:0087 | 8086:3519 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | E70645D3E6 |
| 1000:0097 | 1000:30a0 | Broadco... | SAS3008 PCI-Express Fusio... | 1     | mpt3sas    | 21E2FBBB75 |
| 1000:0097 | 1043:860c | Broadco... | SAS3008 PCI-Express Fusio... | 1     | mpt3sas    | C934F8E023 |
| 1000:00ac | 1d49:0203 | Broadco... | SAS3416 Fusion-MPT Tri-Mo... | 1     | mpt3sas    | 928EE22E71 |
| 1000:00af | 1d49:0202 | Broadco... | SAS3408 Fusion-MPT Tri-Mo... | 1     | mpt3sas    | 928EE22E71 |
| 1000:00c4 | 1000:3190 | Broadco... | SAS3224 PCI-Express Fusio... | 1     | mpt3sas    | 00FDD71981 |
| 11f8:8001 |           | PMC-Sierra | SPC 8x6G SAS/SATA (storport) | 1     | pm80xx     | 4F5756D065 |
| 8086:1d68 | 15d9:0626 | Intel      | C606 chipset Dual 4-Port ... | 1     | isci       | 00FDD71981 |
| 8086:1d68 | 15d9:0630 | Intel      | C606 chipset Dual 4-Port ... | 1     | isci       | 575A60EDC8 |
| 8086:1d69 | 1458:1d69 | Intel      | C604/X79 series chipset 4... | 1     | isci       | 0AC54E7FB4 |
| 8086:1d69 | 8086:1d69 | Intel      | C604/X79 series chipset 4... | 1     | isci       | E0EF143493 |
| 8086:1d6a | 8086:3583 | Intel      | C600/X79 series chipset D... | 1     | isci       | 9F6D925B73 |
| 8086:1d6b | 1014:0432 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | FC0558920D |
| 8086:1d6b | 15d9:062a | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 2E139151DE |
| 8086:1d6b | 15d9:062b | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | FD24B5D375 |
| 8086:1d6b | 15d9:062f | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | F5F0A90676 |
| 8086:1d6b | 15d9:0665 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | CEC82EF5D0 |
| 8086:1d6b | 15d9:066b | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 1FF0EE8759 |
| 8086:1d6b | 15d9:0703 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 8C793BB137 |
| 8086:1d6b | 15d9:0705 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | B3D08DD227 |
| 8086:1d6b | 15d9:070a | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | B4C8ABC585 |
| 8086:1d6b | 8086:1d6b | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 874EAAB0BB |
| 8086:1d6b | 8086:357f | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 7DC714253B |
| 8086:1d6b | 8086:358d | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | D15B8F8758 |
| 8086:1d6b | 8086:3595 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 91F3C901D3 |
| 8086:1d6b | 8086:35b1 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 30CFD7BC18 |
| 8086:1d6d | 1734:11b6 | Intel      | C600/X79 series chipset 4... | 1     |            | 9C16958A72 |
| 8086:1d6f | 8086:3595 | Intel      | C600/X79 series chipset 4... | 1     |            | E70645D3E6 |
| 9005:028d | 9005:0652 | Adaptec    | Series 8 12G SAS/PCIe 3      | 1     | aacraid    | 7479576DA8 |
| 9005:028f | 103c:0701 | Adaptec    | Smart Storage PQI SAS        | 1     | smartpqi   | 9E91D0ED19 |
| 9005:028f | 103c:1100 | Adaptec    | Smart Storage PQI SAS        | 1     | smartpqi   | 3120E02C21 |
| 9005:028f | 9005:0801 | Adaptec    | Smart Storage PQI SAS        | 1     | smartpqi   | F548D0A0A9 |
| 9005:028f | 9005:0802 | Adaptec    | Smart Storage PQI SAS        | 1     | smartpqi   | A8FBAC3A35 |
| 9005:0450 | 11ab:6440 | Adaptec    | ASC-1405 Unified Serial HBA  | 1     | mvsas      | A61FFACB08 |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1000:0058 | 1028:1f0f | LSI Log... | SAS1068E PCI-Express Fusi... | 6     | mptsas     | 24358FA4BD |
| 1000:0056 | 1014:03bb | LSI Log... | SAS1064ET PCI-Express Fus... | 5     | mptsas     | 882EA8E25E |
| 1000:0058 | 1028:1f0e | LSI Log... | SAS1068E PCI-Express Fusi... | 5     | mptsas     | 56B5E62268 |
| 1000:0058 | 1028:1f10 | Broadco... | SAS1068E PCI-Express Fusi... | 5     | mptsas     | 5FBC90E0CD |
| 1000:0056 | 8086:3486 | Broadco... | SAS1064ET PCI-Express Fus... | 2     | mptsas     | 7E72574FF4 |
| 1000:0058 | 1014:0394 | LSI Log... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | 5C4A86988B |
| 1000:0058 | 15d9:0001 | Broadco... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | F645C4227C |
| 9005:8017 | 9005:0045 | Adaptec    | ASC-29320ALP U320            | 2     | aic79xx    | 096D3E62FE |
| 1000:000f | 0e11:7004 | Broadco... | 53c875                       | 1     | sym53c8xx  | AFF808A68F |
| 1000:0030 | 1000:50c0 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 3F4700F256 |
| 1000:0030 | 1014:026c | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 46973B5B05 |
| 1000:0030 | 1028:016e | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 76EF1C8CA9 |
| 1000:0054 | 1028:1f09 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | 4FDE34B201 |
| 1000:0054 | 1734:1082 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | 872AE76863 |
| 1000:0054 | 1734:10b9 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | A0F9679F57 |
| 1000:0054 | 8086:3504 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | A61FFACB08 |
| 1000:0056 | 1734:1131 | Broadco... | SAS1064ET PCI-Express Fus... | 1     | mptsas     | 28EB3733CA |
| 1000:0056 | 8086:346c | Broadco... | SAS1064ET PCI-Express Fus... | 1     | mptsas     | 390F15B7F9 |
| 1000:0058 | 1000:30a0 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | E5AEAF13AE |
| 1000:0058 | 1000:3150 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | 8F6E544820 |
| 1000:0058 | 1734:1130 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | 43C0756BA6 |
| 1000:0059 | 15d9:0006 | Broadco... | MegaRAID SAS 8208ELP/8208ELP | 1     | mptsas     | 8F945E0A15 |
| 9004:5078 | 9004:7850 | Adaptec    | AIC-7850T/7856T [AVA-2902... | 1     | aic7xxx    | 171EE8DB12 |
| 9005:801f | 8086:341a | Adaptec    | AIC-7902 U320                | 1     | aic79xx    | 37AA8C0E8E |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:204e | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 109   | skx_uncore | E757687F86 |
| 8086:2018 | 8086:0000 | Intel      | Sky Lake-E M2PCI Registers   | 105   |            | E757687F86 |
| 8086:2035 |           | Intel      | Sky Lake-E RAS Configurat... | 105   |            | E757687F86 |
| 8086:2040 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 105   |            | E757687F86 |
| 8086:2041 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 105   |            | E757687F86 |
| 8086:2042 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 105   | skx_uncore | E757687F86 |
| 8086:2043 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 105   |            | E757687F86 |
| 8086:2044 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 105   |            | E757687F86 |
| 8086:2045 | 8086:0000 | Intel      | Sky Lake-E LM Channel 1      | 105   |            | E757687F86 |
| 8086:2046 | 8086:0000 | Intel      | Sky Lake-E LMS Channel 1     | 105   | skx_uncore | E757687F86 |
| 8086:2047 | 8086:0000 | Intel      | Sky Lake-E LMDP Channel 1    | 105   |            | E757687F86 |
| 8086:2048 | 8086:0000 | Intel      | Sky Lake-E DECS Channel 2    | 105   |            | E757687F86 |
| 8086:2049 | 8086:0000 | Intel      | Sky Lake-E LM Channel 2      | 105   |            | E757687F86 |
| 8086:204a | 8086:0000 | Intel      | Sky Lake-E LMS Channel 2     | 105   | skx_uncore | E757687F86 |
| 8086:204b | 8086:0000 | Intel      | Sky Lake-E LMDP Channel 2    | 105   |            | E757687F86 |
| 8086:2054 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 105   |            | E757687F86 |
| 8086:2055 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 105   |            | E757687F86 |
| 8086:2056 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 105   |            | E757687F86 |
| 8086:2057 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 105   |            | E757687F86 |
| 8086:2066 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 105   | skx_uncore | E757687F86 |
| 8086:2080 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 105   |            | E757687F86 |
| 8086:2081 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 105   |            | E757687F86 |
| 8086:2082 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 105   |            | E757687F86 |
| 8086:2083 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 105   |            | E757687F86 |
| 8086:2084 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 105   |            | E757687F86 |
| 8086:2085 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 105   |            | E757687F86 |
| 8086:2086 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 105   |            | E757687F86 |
| 8086:208d | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 105   |            | E757687F86 |
| 8086:208e | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 105   |            | E757687F86 |
| 8086:2016 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 104   |            | E757687F86 |
| 8086:2025 |           | Intel      | Sky Lake-E RAS               | 104   |            | E757687F86 |
| 8086:2014 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 102   |            | E757687F86 |
| 8086:2059 | 8086:0000 | Intel      | Sky Lake-E UPI Registers     | 101   |            | E757687F86 |
| 8086:2034 | 8086:0000 | Intel      | Sky Lake-E VT-d              | 100   |            | E757687F86 |
| 8086:2024 | 8086:0000 | Intel      | Sky Lake-E MM/Vt-d Config... | 98    |            | E757687F86 |
| 8086:2021 | 8086:0000 | Intel      | Sky Lake-E CBDMA Registers   | 88    | ioatdma    | C7D795E2A5 |
| 8086:2f6e |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 58    |            | 6A333A499D |
| 8086:2f6f |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 58    |            | 6A333A499D |
| 8086:2f88 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 58    |            | 6A333A499D |
| 8086:2f8a |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 58    |            | 6A333A499D |
| 8086:2fae |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 58    |            | 6A333A499D |
| 8086:2faf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 58    |            | 6A333A499D |
| 8086:2fb8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 58    |            | 6A333A499D |
| 8086:2fb9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 58    |            | 6A333A499D |
| 8086:2fba |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 58    |            | 6A333A499D |
| 8086:2fbb |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 58    |            | 6A333A499D |
| 8086:2fbe |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 58    |            | 6A333A499D |
| 8086:2fbf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 58    |            | 6A333A499D |
| 8086:2ff8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 58    |            | 6A333A499D |
| 8086:2ff9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 58    |            | 6A333A499D |
| 103c:3306 | 103c:3381 | Hewlett... | Integrated Lights-Out Sta... | 55    | hpwdt      | CFFFE6AA63 |
| 103c:3307 | 103c:3381 | Hewlett... | Integrated Lights-Out Sta... | 55    | hpilo      | CFFFE6AA63 |
| 8086:6f76 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 53    |            | DF26C4E8C4 |
| 8086:6f88 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 53    |            | DF26C4E8C4 |
| 8086:6f8a |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 53    |            | DF26C4E8C4 |
| 8086:6fae |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 53    |            | DF26C4E8C4 |
| 8086:6faf |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 53    |            | DF26C4E8C4 |
| 8086:6fbc |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 53    |            | DF26C4E8C4 |
| 8086:6fbd |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 53    |            | DF26C4E8C4 |
| 8086:6fbe |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 53    |            | DF26C4E8C4 |
| 8086:6fbf |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 53    |            | DF26C4E8C4 |
| 8086:2fbc |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 51    |            | C7B39E92CA |
| 8086:2fbd |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 51    |            | C7B39E92CA |
| 8086:6f6e |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 45    |            | DF26C4E8C4 |
| 8086:6f6f |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 45    |            | DF26C4E8C4 |
| 8086:6fb8 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 45    |            | DF26C4E8C4 |
| 8086:6fb9 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 45    |            | DF26C4E8C4 |
| 8086:6fba |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 45    |            | DF26C4E8C4 |
| 8086:6fbb |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 45    |            | DF26C4E8C4 |
| 8086:3cae | 8086:0000 | Intel      | Xeon E5/Core i7 Integrate... | 43    |            | D350652289 |
| 8086:3cb8 | 8086:0000 | Intel      | Xeon E5/Core i7 DDRIO        | 43    |            | D350652289 |
| 8086:3cc1 | 8086:0000 | Intel      | Xeon E5/Core i7 Power Con... | 43    |            | D350652289 |
| 8086:2f1d | 8086:2f1d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:2f1e | 8086:2f1e | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:2f1f | 8086:2f1f | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:2f71 | 8086:2f71 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:2f81 | 8086:2f81 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:2f98 | 8086:2f98 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:2f99 | 8086:2f99 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:2f9a | 8086:2f9a | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:2f9c | 8086:2f9c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:2fa0 | 8086:2fa0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    | sb_edac    | 6A333A499D |
| 8086:2fa8 | 8086:2fa8 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:2faa | 8086:2faa | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:2fab | 8086:2fab | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:2fb0 | 8086:2fb0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    | hswep_u... | 6A333A499D |
| 8086:2fb1 | 8086:2fb1 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    | hswep_u... | 6A333A499D |
| 8086:2fb2 | 8086:2fb2 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:2fb3 | 8086:2fb3 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:2fc0 | 8086:2fc0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    | hswep_u... | 6A333A499D |
| 8086:2fe0 | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:2fe1 | 8086:2fe1 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:2fe2 | 8086:2fe2 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:2fe3 | 8086:2fe3 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:2ffc | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:2ffd | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:2ffe | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 39    |            | 6A333A499D |
| 8086:6f68 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 38    |            | DF26C4E8C4 |
| 8086:6fd0 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 38    | bdx_uncore | DF26C4E8C4 |
| 8086:2f68 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 37    |            | 6A333A499D |

### Tv card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 109e:036e |           | Brooktree  | Bt878 Video Capture          | 1     | bttv       | B55D1DAEA5 |
| 109e:036e | 0070:ff04 | Brooktree  | Bt878 Video Capture          | 1     | bttv       | 2C877CF870 |
| 109e:036e | 800a:763d | Brooktree  | Bt878 Video Capture          | 1     | bttv       | 7E72574FF4 |
| 109e:036e | 800b:763d | Brooktree  | Bt878 Video Capture          | 1     | bttv       | 7E72574FF4 |
| 109e:036e | 800c:763d | Brooktree  | Bt878 Video Capture          | 1     | bttv       | 7E72574FF4 |
| 109e:036e | 800d:763d | Brooktree  | Bt878 Video Capture          | 1     | bttv       | 7E72574FF4 |
| 14f1:8880 | 0070:6a18 | Conexan... | CX23887/8 PCIe Broadcast ... | 1     | cx23885    | 019914CC29 |
| 14f1:8880 | 0070:6b18 | Conexan... | CX23887/8 PCIe Broadcast ... | 1     | cx23885    | 019914CC29 |
| 14f1:8880 | 1461:d439 | Conexan... | CX23887/8 PCIe Broadcast ... | 1     |            | D8325626F2 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 103c:3300 | 103c:3381 | Hewlett... | Integrated Lights-Out Sta... | 55    | uhci_hcd   | CFFFE6AA63 |
| 8086:1d26 | 103c:18a9 | Intel      | C600/X79 series chipset U... | 41    | ehci_pci   | 7B579629BB |
| 8086:1d2d | 103c:18a9 | Intel      | C600/X79 series chipset U... | 41    | ehci_pci   | 7B579629BB |
| 8086:3a34 | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 36    | uhci_hcd   | A9C87C6C9C |
| 8086:3a35 | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 36    | uhci_hcd   | A9C87C6C9C |
| 8086:3a36 | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 36    | uhci_hcd   | A9C87C6C9C |
| 8086:3a39 | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 36    | uhci_hcd   | A9C87C6C9C |
| 8086:3a3a | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 36    | ehci_pci   | A9C87C6C9C |
| 103c:3300 | 103c:3305 | Hewlett... | Integrated Lights-Out Sta... | 27    | uhci_hcd   | DCBC2D451E |
| 103c:3300 | 103c:3309 | Hewlett... | Integrated Lights-Out Sta... | 25    | uhci_hcd   | A9C87C6C9C |
| 1912:0014 | ffff:ffff | Renesas... | uPD720201 USB 3.0 Host Co... | 20    | xhci_hcd   | D3DC168A2A |
| 8086:a1af | 8086:35ce | Intel      | C620 Series Chipset Famil... | 20    | xhci_hcd   | 36C4ACAC2D |
| 1002:4396 | 1002:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 18    | ehci_pci   | 58771D090D |
| 1002:4399 | 1002:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 17    | ohci_pci   | 58771D090D |
| 8086:2934 | 1028:0235 | Intel      | 82801I (ICH9 Family) USB ... | 17    | uhci_hcd   | 246F93C093 |
| 8086:2935 | 1028:0235 | Intel      | 82801I (ICH9 Family) USB ... | 17    | uhci_hcd   | 246F93C093 |
| 8086:2937 | 1028:0235 | Intel      | 82801I (ICH9 Family) USB ... | 17    | uhci_hcd   | 246F93C093 |
| 8086:2938 | 1028:0235 | Intel      | 82801I (ICH9 Family) USB ... | 17    | uhci_hcd   | 246F93C093 |
| 8086:293a | 1028:0235 | Intel      | 82801I (ICH9 Family) USB2... | 17    | ehci_pci   | 246F93C093 |
| 8086:293c | 1028:0235 | Intel      | 82801I (ICH9 Family) USB2... | 17    | ehci_pci   | 246F93C093 |
| 8086:8d26 | 15d9:0821 | Intel      | C610/X99 series chipset U... | 17    | ehci_pci   | AAEEE85BE7 |
| 8086:8d2d | 15d9:0821 | Intel      | C610/X99 series chipset U... | 17    | ehci_pci   | AAEEE85BE7 |
| 8086:8d31 | 15d9:0821 | Intel      | C610/X99 series chipset U... | 17    | xhci_hcd   | AAEEE85BE7 |
| 8086:a1af | 8086:7270 | Intel      | C620 Series Chipset Famil... | 17    | xhci_hcd   | AD903545CE |
| 8086:1d26 | 1043:84ef | Intel      | C600/X79 series chipset U... | 14    | ehci_pci   | 874EAAB0BB |
| 8086:1d2d | 1043:84ef | Intel      | C600/X79 series chipset U... | 14    | ehci_pci   | 874EAAB0BB |
| 8086:3a34 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 14    | uhci_hcd   | DB4185737E |
| 8086:3a35 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 14    | uhci_hcd   | DB4185737E |
| 8086:3a36 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 14    | uhci_hcd   | DB4185737E |
| 8086:3a37 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 14    | uhci_hcd   | DB4185737E |
| 8086:3a38 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 14    | uhci_hcd   | DB4185737E |
| 8086:3a39 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 14    | uhci_hcd   | DB4185737E |
| 8086:3a3a | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 14    | ehci_hcd   | DB4185737E |
| 8086:3a3c | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 14    | ehci_hcd   | DB4185737E |
| 8086:2688 | 103c:31fe | Intel      | 631xESB/632xESB/3100 Chip... | 13    | uhci_hcd   | B6088E88BA |
| 8086:2689 | 103c:31fe | Intel      | 631xESB/632xESB/3100 Chip... | 13    | uhci_hcd   | B6088E88BA |
| 8086:268a | 103c:31fe | Intel      | 631xESB/632xESB/3100 Chip... | 13    | uhci_hcd   | B6088E88BA |
| 8086:268c | 103c:31fe | Intel      | 631xESB/632xESB/3100 Chip... | 13    | ehci_pci   | B6088E88BA |
| 8086:1d26 | 15d9:0636 | Intel      | C600/X79 series chipset U... | 12    | ehci_hcd   | DD93F62FFC |
| 8086:1d2d | 15d9:0636 | Intel      | C600/X79 series chipset U... | 12    | ehci_hcd   | DD93F62FFC |
| 8086:268b | 103c:31fe | Intel      | 631xESB/632xESB/3100 Chip... | 12    | uhci_hcd   | B6088E88BA |
| 8086:8d31 | 8086:7270 | Intel      | C610/X99 series chipset U... | 12    | xhci_hcd   | C04F902B93 |
| 1b21:1042 | 1043:8488 | ASMedia... | ASM1042 SuperSpeed USB Ho... | 11    | xhci_hcd   | A4C832AB44 |
| 8086:3b34 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 11    | ehci_pci   | 56B5E62268 |
| 8086:3b3c | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 11    | ehci_pci   | 56B5E62268 |
| 8086:8d26 | 8086:7270 | Intel      | C610/X99 series chipset U... | 11    | ehci_pci   | C04F902B93 |
| 8086:8d2d | 8086:7270 | Intel      | C610/X99 series chipset U... | 11    | ehci_pci   | C04F902B93 |
| 1b73:1100 | 1b73:1100 | Fresco ... | FL1100 USB 3.0 Host Contr... | 10    | xhci_hcd   | 6B7A9D9BDB |
| 8086:1d26 | 1028:048c | Intel      | C600/X79 series chipset U... | 10    | ehci_pci   | 3BCB61F70C |
| 8086:1d2d | 1028:048c | Intel      | C600/X79 series chipset U... | 10    | ehci_pci   | 3BCB61F70C |
| 8086:8d26 | 103c:8030 | Intel      | C610/X99 series chipset U... | 10    | ehci_pci   | CFFFE6AA63 |
| 8086:8d2d | 103c:8030 | Intel      | C610/X99 series chipset U... | 10    | ehci_pci   | CFFFE6AA63 |
| 8086:8d31 | 103c:8030 | Intel      | C610/X99 series chipset U... | 10    | xhci_hcd   | CFFFE6AA63 |
| 1b21:1142 | 1b21:1142 | ASMedia... | ASM1042A USB 3.0 Host Con... | 9     | xhci_hcd   | 6A333A499D |
| 8086:1d26 | 1014:1d26 | Intel      | C600/X79 series chipset U... | 9     | ehci_pci   | 1A5CF39F4F |
| 8086:1d2d | 1014:1d2d | Intel      | C600/X79 series chipset U... | 9     | ehci_pci   | 1A5CF39F4F |
| 8086:2934 | 1028:0236 | Intel      | 82801I (ICH9 Family) USB ... | 9     | uhci_hcd   | 26944912D7 |
| 8086:2935 | 1028:0236 | Intel      | 82801I (ICH9 Family) USB ... | 9     | uhci_hcd   | 26944912D7 |
| 8086:2937 | 1028:0236 | Intel      | 82801I (ICH9 Family) USB ... | 9     | uhci_hcd   | 26944912D7 |
| 8086:2938 | 1028:0236 | Intel      | 82801I (ICH9 Family) USB ... | 9     | uhci_hcd   | 26944912D7 |
| 8086:293a | 1028:0236 | Intel      | 82801I (ICH9 Family) USB2... | 9     | ehci_pci   | 26944912D7 |
| 8086:293c | 1028:0236 | Intel      | 82801I (ICH9 Family) USB2... | 9     | ehci_pci   | 26944912D7 |
| 1106:3483 | 1106:3483 | VIA Tec... | VL805/806 xHCI USB 3.0 Co... | 8     | xhci_hcd   | 29F49B3A79 |
| 8086:1d26 | 1028:04fa | Intel      | C600/X79 series chipset U... | 8     | ehci_pci   | C9C876F0E7 |
| 8086:1d2d | 1028:04fa | Intel      | C600/X79 series chipset U... | 8     | ehci_pci   | C9C876F0E7 |
| 8086:3a34 | 1014:3a34 | Intel      | 82801JI (ICH10 Family) US... | 8     | uhci_hcd   | B4A013EED4 |
| 8086:3a34 | 1028:028c | Intel      | 82801JI (ICH10 Family) US... | 8     | uhci_hcd   | 24358FA4BD |
| 8086:3a35 | 1014:3a35 | Intel      | 82801JI (ICH10 Family) US... | 8     | uhci_hcd   | B4A013EED4 |
| 8086:3a35 | 1028:028c | Intel      | 82801JI (ICH10 Family) US... | 8     | uhci_hcd   | 24358FA4BD |
| 8086:3a36 | 1014:3a36 | Intel      | 82801JI (ICH10 Family) US... | 8     | uhci_hcd   | B4A013EED4 |
| 8086:3a36 | 1028:028c | Intel      | 82801JI (ICH10 Family) US... | 8     | uhci_hcd   | 24358FA4BD |
| 8086:3a37 | 1014:3a37 | Intel      | 82801JI (ICH10 Family) US... | 8     | uhci_hcd   | B4A013EED4 |
| 8086:3a37 | 1028:028c | Intel      | 82801JI (ICH10 Family) US... | 8     | uhci_hcd   | 24358FA4BD |
| 8086:3a38 | 1014:3a38 | Intel      | 82801JI (ICH10 Family) US... | 8     | uhci_hcd   | B4A013EED4 |
| 8086:3a38 | 1028:028c | Intel      | 82801JI (ICH10 Family) US... | 8     | uhci_hcd   | 24358FA4BD |
| 8086:3a39 | 1028:028c | Intel      | 82801JI (ICH10 Family) US... | 8     | uhci_hcd   | 24358FA4BD |
| 8086:3a3a | 1014:3a3a | Intel      | 82801JI (ICH10 Family) US... | 8     | ehci_hc... | B4A013EED4 |
| 8086:3a3a | 1028:028c | Intel      | 82801JI (ICH10 Family) US... | 8     | ehci_pci   | 24358FA4BD |
| 8086:3a3c | 1014:3a3c | Intel      | 82801JI (ICH10 Family) US... | 8     | ehci_hc... | B4A013EED4 |
| 8086:3a3c | 1028:028c | Intel      | 82801JI (ICH10 Family) US... | 8     | ehci_pci   | 24358FA4BD |
| 8086:8d26 | 15d9:0857 | Intel      | C610/X99 series chipset U... | 8     | ehci_pci   | 6A333A499D |
| 8086:8d2d | 15d9:0857 | Intel      | C610/X99 series chipset U... | 8     | ehci_pci   | 6A333A499D |
| 8086:8d31 | 15d9:0857 | Intel      | C610/X99 series chipset U... | 8     | xhci_hcd   | 6A333A499D |
| 8086:a1af | 1028:073a | Intel      | C620 Series Chipset Famil... | 8     | xhci_hcd   | C7D795E2A5 |
| 8086:a1af | 1043:8722 | Intel      | C620 Series Chipset Famil... | 8     | xhci_hcd   | 55BDC0F976 |
| 1022:7908 | 1022:7908 | AMD        | FCH USB EHCI Controller      | 7     | ehci_pci   | 7735F49C62 |
| 1022:7914 | 1022:7914 | AMD        | FCH USB XHCI Controller      | 7     | xhci_hcd   | 7735F49C62 |
| 103c:22f6 | 1590:00e4 | Hewlett... | iLO5 Virtual USB Controller  | 7     | ehci_pci   | 7AB4F05613 |
| 8086:3a34 | 15d9:0400 | Intel      | 82801JI (ICH10 Family) US... | 7     | uhci_hcd   | AD4ABE60CD |
| 8086:3a34 | 8086:34dc | Intel      | 82801JI (ICH10 Family) US... | 7     | uhci_hcd   | 451F363726 |
| 8086:3a35 | 15d9:0400 | Intel      | 82801JI (ICH10 Family) US... | 7     | uhci_hcd   | AD4ABE60CD |
| 8086:3a35 | 8086:34dc | Intel      | 82801JI (ICH10 Family) US... | 7     | uhci_hcd   | 451F363726 |
| 8086:3a36 | 15d9:0400 | Intel      | 82801JI (ICH10 Family) US... | 7     | uhci_hcd   | AD4ABE60CD |
| 8086:3a36 | 8086:34dc | Intel      | 82801JI (ICH10 Family) US... | 7     | uhci_hcd   | 451F363726 |
| 8086:3a37 | 15d9:0400 | Intel      | 82801JI (ICH10 Family) US... | 7     | uhci_hcd   | AD4ABE60CD |
| 8086:3a37 | 8086:34dc | Intel      | 82801JI (ICH10 Family) US... | 7     | uhci_hcd   | 451F363726 |
| 8086:3a38 | 15d9:0400 | Intel      | 82801JI (ICH10 Family) US... | 7     | uhci_hcd   | AD4ABE60CD |
| 8086:3a38 | 8086:34dc | Intel      | 82801JI (ICH10 Family) US... | 7     | uhci_hcd   | 451F363726 |
| 8086:3a39 | 8086:34dc | Intel      | 82801JI (ICH10 Family) US... | 7     | uhci_hcd   | 451F363726 |
| 8086:3a3a | 15d9:0400 | Intel      | 82801JI (ICH10 Family) US... | 7     | ehci_pci   | AD4ABE60CD |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8d7c | 15d9:0821 | Intel      | C610/X99 series chipset SPSR | 17    |            | AAEEE85BE7 |
| 8086:a1ec | 8086:7270 | Intel      | C620 Series Chipset Famil... | 17    |            | AD903545CE |
| 8086:a1ec | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    |            | 4391DFF8D2 |
| 8086:a1ed | 8086:7270 | Intel      | C620 Series Chipset Famil... | 13    |            | 0627DB12DF |
| 8086:8d7c | 103c:8030 | Intel      | C610/X99 series chipset SPSR | 10    |            | CFFFE6AA63 |
| 8086:8d7c | 8086:7270 | Intel      | C610/X99 series chipset SPSR | 10    |            | C04F902B93 |
| 8086:8d7c | 15d9:0857 | Intel      | C610/X99 series chipset SPSR | 8     |            | 6A333A499D |
| 8086:8d7c | 8086:0000 | Intel      | C610/X99 series chipset SPSR | 8     |            | BA0F3C3B41 |
| 8086:a1ec | 1028:073a | Intel      | C620 Series Chipset Famil... | 8     |            | C7D795E2A5 |
| 8086:a1ec | 1043:871e | Intel      | C620 Series Chipset Famil... | 8     |            | 55BDC0F976 |
| 8086:a1ed | 1028:073a | Intel      | C620 Series Chipset Famil... | 8     |            | C7D795E2A5 |
| 8086:8d7c | 1043:85f6 | Intel      | C610/X99 series chipset SPSR | 7     |            | 4158CB76EF |
| 8086:a1ec | 1590:00eb | Intel      | C620 Series Chipset Famil... | 7     |            | 7AB4F05613 |
| 8086:a1ec | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     |            | CEE7ED2CE9 |
| 8086:a1ed | 1590:00eb | Intel      | C620 Series Chipset Famil... | 7     |            | 7AB4F05613 |
| 8086:8d7c | 1028:0601 | Intel      | C610/X99 series chipset SPSR | 6     |            | F90168C69D |
| 8086:8d7c | 15d9:0831 | Intel      | C610/X99 series chipset SPSR | 5     |            | 64918C950D |
| 8086:a1ec | 15d9:096d | Intel      | C620 Series Chipset Famil... | 5     |            | C8195297A4 |
| 8086:a1ec | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 5     |            | 5E1947B31A |
| 8086:a1ed | 15d9:096d | Intel      | C620 Series Chipset Famil... | 5     |            | C8195297A4 |
| 8086:a1ed | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 5     |            | 5E1947B31A |
| 8086:a1ec | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     |            | E9A1FC86F9 |
| 8086:a1ec | 1028:0739 | Intel      | C620 Series Chipset Famil... | 4     |            | 9E01FD5E8C |
| 8086:a1ec | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 4     |            | 5299B4DA87 |
| 8086:a1ec | 1849:a1ec | Intel      | C620 Series Chipset Famil... | 4     |            | 2244EB7809 |
| 8086:a1ec | 8086:0000 | Intel      | C620 Series Chipset Famil... | 4     |            | 36C4ACAC2D |
| 8086:a1ed | 1028:0739 | Intel      | C620 Series Chipset Famil... | 4     |            | 9E01FD5E8C |
| 8086:a1ed | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 4     |            | 5299B4DA87 |
| 8086:a1ed | 1849:a1ed | Intel      | C620 Series Chipset Famil... | 4     |            | 2244EB7809 |
| 8086:a1ed | 8086:35ce | Intel      | C620 Series Chipset Famil... | 4     |            | 36C4ACAC2D |
| 1912:001b | 1d49:0a02 | Renesas... | SH7758 PCIe End-Point [PBI]  | 3     |            | 3510DD7B10 |
| 8086:8d7c | 1028:0600 | Intel      | C610/X99 series chipset SPSR | 3     |            | A98D12AD3E |
| 8086:8d7c | 1028:0627 | Intel      | C610/X99 series chipset SPSR | 3     |            | C7B39E92CA |
| 8086:8d7c | 1028:0639 | Intel      | C610/X99 series chipset SPSR | 3     |            | E5766C8331 |
| 8086:8d7c | 1458:1000 | Intel      | C610/X99 series chipset SPSR | 3     |            | 2F69A2F89C |
| 8086:8d7c | 15d9:0834 | Intel      | C610/X99 series chipset SPSR | 3     |            | FA4BECDE8B |
| 8086:8d7c | 1d49:0a00 | Intel      | C610/X99 series chipset SPSR | 3     |            | 3510DD7B10 |
| 8086:a1ec | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | E752263E49 |
| 8086:a1ec | 103c:81c6 | Intel      | C620 Series Chipset Famil... | 3     |            | 679871CFEC |
| 8086:a1ec | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     |            | 7AD1F5EB4E |
| 8086:a1ec | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     |            | C682299C13 |
| 8086:a1ec | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     |            | 5658A2FB98 |
| 8086:a1ed | 103c:81c6 | Intel      | C620 Series Chipset Famil... | 3     |            | 679871CFEC |
| 8086:a1ed | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     |            | 7AD1F5EB4E |
| 8086:a1ed | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     |            | C682299C13 |
| 8086:a1ed | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     |            | 5658A2FB98 |
| 8086:8d7c | 1028:063a | Intel      | C610/X99 series chipset SPSR | 2     |            | E4DEE6FAF7 |
| 8086:8d7c | 1028:063b | Intel      | C610/X99 series chipset SPSR | 2     |            | DF26C4E8C4 |
| 8086:8d7c | 15d9:0824 | Intel      | C610/X99 series chipset SPSR | 2     |            | 6C96E4A591 |
| 8086:8d7c | 15d9:0860 | Intel      | C610/X99 series chipset SPSR | 2     |            | CC00646768 |
| 8086:a1ec | 1028:0718 | Intel      | C620 Series Chipset Famil... | 2     |            | 1CCB5D67C2 |
| 8086:a1ec | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     |            | DF9A63BE43 |
| 8086:a1ec | 1028:07cb | Intel      | C620 Series Chipset Famil... | 2     |            | FE43558C7A |
| 8086:a1ec | 1028:07e5 | Intel      | C620 Series Chipset Famil... | 2     |            | 4C88B2E09B |
| 8086:a1ec | 15d9:091c | Intel      | C620 Series Chipset Famil... | 2     |            | 748FB8054B |
| 8086:a1ec | 15d9:0941 | Intel      | C620 Series Chipset Famil... | 2     |            | C619DB847B |
| 8086:a1ec | 17aa:7800 | Intel      | C620 Series Chipset Famil... | 2     |            | 928EE22E71 |
| 8086:a1ed | 15d9:091c | Intel      | C620 Series Chipset Famil... | 2     |            | 748FB8054B |
| 8086:a1ed | 15d9:0941 | Intel      | C620 Series Chipset Famil... | 2     |            | C619DB847B |
| 1000:fury | 1000:9341 | Broadco... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 64918C950D |
| 1000:fury | 1014:0456 | LSI Log... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 817865DED6 |
| 1000:fury | 1028:1f44 | LSI Log... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 5B9EC879FC |
| 1000:fury | 1028:1f4b | LSI Log... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | FF3ACF2BDC |
| 1a41:0200 |           | Tilera     | TILE-Gx processor            | 1     | tilegxpci  | 08100751B7 |
| 1a41:0201 |           | Tilera     | TILE-Gx Processor Virtual... | 1     |            | 08100751B7 |
| 1bb0:0010 | 1bb0:0010 | SimpliVity | OmniCube Accelerator OA-3... | 1     |            | C5705E6436 |
| 8086:10a6 | 8086:0000 | Intel      | 82599EB 10-Gigabit Dummy ... | 1     |            | 14C76E0C83 |
| 8086:2541 | 8086:341a | Intel      | E7500/E7501 Host RASUM Co... | 1     |            | 37AA8C0E8E |
| 8086:2546 | 8086:341a | Intel      | E7500/E7501 Hub Interface... | 1     |            | 37AA8C0E8E |
| 8086:3591 | 103c:3208 | Intel      | E7525/E7520 Error Reporti... | 1     |            | 2C877CF870 |
| 8086:3591 | 8086:3439 | Intel      | E7525/E7520 Error Reporti... | 1     |            | 0F21E859FA |
| 8086:6ff2 | 8086:6ff2 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 822418675E |
| 8086:6ff3 | 8086:6ff3 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 822418675E |
| 8086:6ff4 | 8086:6ff4 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 822418675E |
| 8086:6ff5 | 8086:6ff5 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 822418675E |
| 8086:8d7c | 15d9:0832 | Intel      | C610/X99 series chipset SPSR | 1     |            | 4D83783043 |
| 8086:8d7c | 15d9:0835 | Intel      | C610/X99 series chipset SPSR | 1     |            | 7479576DA8 |
| 8086:8d7c | 15d9:0856 | Intel      | C610/X99 series chipset SPSR | 1     |            | 50EC24A7DE |
| 8086:8d7c | 15d9:086b | Intel      | C610/X99 series chipset SPSR | 1     |            | 3CFD00A1CD |
| 8086:8d7c | 15d9:086c | Intel      | C610/X99 series chipset SPSR | 1     |            | 947E0AEF4A |
| 8086:8d7c | 15d9:0879 | Intel      | C610/X99 series chipset SPSR | 1     |            | 21124E85CC |
| 8086:8d7c | 15d9:0924 | Intel      | C610/X99 series chipset SPSR | 1     |            | 3FC4F3458F |
| 8086:8d7c | 15d9:7270 | Intel      | C610/X99 series chipset SPSR | 1     |            | 5F6D0233A8 |
| 8086:a1ec | 1028:07c9 | Intel      | C620 Series Chipset Famil... | 1     |            | E757687F86 |
| 8086:a1ec | 1458:5001 | Intel      | C620 Series Chipset Famil... | 1     |            | 7E93E1B694 |
| 8086:a1ec | 15d9:095e | Intel      | C620 Series Chipset Famil... | 1     |            | E0F65B7228 |
| 8086:a1ec | 15d9:0962 | Intel      | C620 Series Chipset Famil... | 1     |            | 57460AA45B |
| 8086:a1ec | 15d9:0967 | Intel      | C620 Series Chipset Famil... | 1     |            | 6FAB4E3135 |
| 8086:a1ec | 15d9:0968 | Intel      | C620 Series Chipset Famil... | 1     |            | 7026C20C97 |
| 8086:a1ec | 15d9:096e | Intel      | C620 Series Chipset Famil... | 1     |            | 4D0ED95E02 |
| 8086:a1ec | 15d9:0986 | Intel      | C620 Series Chipset Famil... | 1     |            | 331227D869 |
| 8086:a1ec | 15d9:0987 | Intel      | C620 Series Chipset Famil... | 1     |            | 893E9D69F2 |
| 8086:a1ec | 1734:1230 | Intel      | C620 Series Chipset Famil... | 1     |            | 86AB491564 |
| 8086:a1ec | 17aa:1037 | Intel      | C620 Series Chipset Famil... | 1     |            | 41249F2E48 |
| 8086:a1ed | 1458:5001 | Intel      | C620 Series Chipset Famil... | 1     |            | 7E93E1B694 |
| 8086:a1ed | 15d9:095e | Intel      | C620 Series Chipset Famil... | 1     |            | E0F65B7228 |
| 8086:a1ed | 15d9:0962 | Intel      | C620 Series Chipset Famil... | 1     |            | 57460AA45B |
| 8086:a1ed | 15d9:0967 | Intel      | C620 Series Chipset Famil... | 1     |            | 6FAB4E3135 |
| 8086:a1ed | 15d9:0968 | Intel      | C620 Series Chipset Famil... | 1     |            | 7026C20C97 |
| 8086:a1ed | 15d9:096e | Intel      | C620 Series Chipset Famil... | 1     |            | 4D0ED95E02 |

