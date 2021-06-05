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
| 1a03:1150 | 1a03:1150 | ASPEED ... | AST1150 PCI-to-PCI Bridge    | 113   | shpchp     | CF083F4B62 |
| 8086:2c70 | 8086:8086 | Intel      | Xeon 5600 Series QuickPat... | 89    |            | 4DEBADA4BF |
| 8086:2d81 | 8086:8086 | Intel      | Xeon 5600 Series QuickPat... | 89    |            | 4DEBADA4BF |
| 8086:2d90 | 8086:8086 | Intel      | Xeon 5600 Series QPI Link 0  | 89    |            | 4DEBADA4BF |
| 8086:2d91 | 8086:8086 | Intel      | Xeon 5600 Series QPI Phys... | 89    |            | 4DEBADA4BF |
| 8086:2d92 | 8086:8086 | Intel      | Xeon 5600 Series Mirror P... | 89    |            | 4DEBADA4BF |
| 8086:2d93 | 8086:8086 | Intel      | Xeon 5600 Series Mirror P... | 89    |            | 4DEBADA4BF |
| 8086:2d94 | 8086:8086 | Intel      | Xeon 5600 Series QPI Link 1  | 89    |            | 4DEBADA4BF |
| 8086:2d95 | 8086:8086 | Intel      | Xeon 5600 Series QPI Phys... | 89    |            | 4DEBADA4BF |
| 8086:2d98 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 89    |            | 4DEBADA4BF |
| 8086:2d99 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 89    |            | 4DEBADA4BF |
| 8086:2d9a | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 89    |            | 4DEBADA4BF |
| 8086:2d9c | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 89    |            | 4DEBADA4BF |
| 8086:2da0 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 89    |            | 4DEBADA4BF |
| 8086:2da1 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 89    |            | 4DEBADA4BF |
| 8086:2da2 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 89    |            | 4DEBADA4BF |
| 8086:2da3 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 89    |            | 4DEBADA4BF |
| 8086:2da8 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 89    |            | 4DEBADA4BF |
| 8086:2da9 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 89    |            | 4DEBADA4BF |
| 8086:2daa | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 89    |            | 4DEBADA4BF |
| 8086:2dab | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 89    |            | 4DEBADA4BF |
| 8086:2db0 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 89    |            | 4DEBADA4BF |
| 8086:2db1 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 89    |            | 4DEBADA4BF |
| 8086:2db2 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 89    |            | 4DEBADA4BF |
| 8086:2db3 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 89    |            | 4DEBADA4BF |
| 8086:2030 | 8086:0000 | Intel      | Sky Lake-E PCI Express Ro... | 64    | pcieport   | 2D1D9030E8 |
| 8086:2032 | 8086:0000 | Intel      | Sky Lake-E PCI Express Ro... | 56    | pcieport   | 2D1D9030E8 |
| 8086:2020 | 8086:0000 | Intel      | Sky Lake-E DMI3 Registers    | 50    |            | 2D1D9030E8 |
| 8086:244e |           | Intel      | 82801 PCI Bridge             | 48    | shpchp     | 8571D09FE7 |
| 8086:25e3 |           | Intel      | 5000 Series Chipset PCI E... | 35    | pcieport   | 3A68279F78 |
| 8086:3408 | 103c:330b | Intel      | 5520/5500/X58 I/O Hub PCI... | 34    | pcieport   | 28B04C3004 |
| 8086:340a | 103c:330b | Intel      | 5520/5500/X58 I/O Hub PCI... | 34    | pcieport   | 28B04C3004 |
| 8086:340e | 103c:330b | Intel      | 5520/5500/X58 I/O Hub PCI... | 34    | pcieport   | 28B04C3004 |
| 8086:3410 | 103c:330b | Intel      | 7500/5520/5500/X58 I/O Hu... | 34    | pcieport   | 28B04C3004 |
| 8086:341c |           | Intel      | 7500/5520/5500/X58 Unknown   | 34    |            | C56840DF98 |
| 8086:341d |           | Intel      | 7500/5520/5500/X58 Unknown   | 34    |            | C56840DF98 |
| 8086:341e |           | Intel      | 7500/5520/5500/X58 Unknown   | 34    |            | C56840DF98 |
| 8086:1d10 | 103c:18a9 | Intel      | C600/X79 series chipset P... | 33    | pcieport   | 799CC190DB |
| 8086:1d1e | 103c:18a9 | Intel      | C600/X79 series chipset P... | 33    | pcieport   | 799CC190DB |
| 8086:1d3e | 103c:18a9 | Intel      | C600/X79 series chipset P... | 33    | pcieport   | 799CC190DB |
| 8086:1d41 |           | Intel      | C600/X79 series chipset L... | 33    | lpc_ich    | 799CC190DB |
| 8086:244e | 103c:18a9 | Intel      | 82801 PCI Bridge             | 33    |            | 799CC190DB |
| 8086:3411 | 103c:330b | Intel      | 7500/5520/5500/X58 I/O Hu... | 33    | pcieport   | C56840DF98 |
| 8086:3418 |           | Intel      | 7500/5520/5500/X58 Physic... | 33    |            | C56840DF98 |
| 8086:3419 |           | Intel      | 7500/5520/5500 Physical L... | 33    |            | C56840DF98 |
| 8086:341a |           | Intel      | 7500/5520/5500/X58 Unknown   | 33    |            | C56840DF98 |
| 8086:3439 |           | Intel      | 7500/5520/5500/X58 Unknown   | 33    |            | C56840DF98 |
| 8086:343a |           | Intel      | 7500/5520/5500/X58 Unknown   | 33    |            | C56840DF98 |
| 8086:343b |           | Intel      | 7500/5520/5500/X58 Unknown   | 33    |            | C56840DF98 |
| 8086:343c |           | Intel      | 7500/5520/5500/X58 Unknown   | 33    |            | C56840DF98 |
| 8086:343d |           | Intel      | 7500/5520/5500/X58 Unknown   | 33    |            | C56840DF98 |
| 8086:37c0 | 8086:0000 | Intel      | PCI bridge                   | 33    | pcieport   | 7AD1F5EB4E |
| 1002:4384 |           | AMD        | SBx00 PCI to PCI Bridge      | 32    |            | 0335142464 |
| 8086:244e | 103c:330d | Intel      | 82801 PCI Bridge             | 31    |            | C56840DF98 |
| 8086:3406 | 103c:330b | Intel      | 5520 I/O Hub to ESI Port     | 31    |            | 28B04C3004 |
| 8086:3409 | 103c:330b | Intel      | 5520/5500/X58 I/O Hub PCI... | 30    | pcieport   | C56840DF98 |
| 8086:340b | 103c:330b | Intel      | 5520/X58 I/O Hub PCI Expr... | 30    | pcieport   | C56840DF98 |
| 8086:340c | 103c:330b | Intel      | 5520/X58 I/O Hub PCI Expr... | 30    | pcieport   | C56840DF98 |
| 8086:340d | 103c:330b | Intel      | 5520/X58 I/O Hub PCI Expr... | 30    | pcieport   | C56840DF98 |
| 8086:340f | 103c:330b | Intel      | 5520/5500/X58 I/O Hub PCI... | 30    | pcieport   | C56840DF98 |
| 8086:3a18 |           | Intel      | 82801JIB (ICH10) LPC Inte... | 30    | lpc_ich    | C56840DF98 |
| 8086:25e5 |           | Intel      | 5000 Series Chipset PCI E... | 29    | pcieport   | 3A68279F78 |
| 8086:25e7 |           | Intel      | 5000 Series Chipset PCI E... | 29    | pcieport   | 3A68279F78 |
| 1912:0012 | 1912:0012 | Renesas... | SH7757 PCIe-PCI Bridge [PPB] | 28    | shpchp     | 7A9C742839 |
| 1912:0013 | 1912:0013 | Renesas... | SH7757 PCIe Switch [PS]      | 28    | pcieport   | 7A9C742839 |
| 8086:341f |           | Intel      | 7500/5520/5500/X58 Unknown   | 27    |            | C56840DF98 |
| 8086:3c00 | 103c:18a8 | Intel      | Xeon E5/Core i7 DMI2         | 27    |            | 799CC190DB |
| 8086:3c02 | 103c:18a8 | Intel      | Xeon E5/Core i7 IIO PCI E... | 27    | pcieport   | 799CC190DB |
| 8086:3c03 | 103c:18a8 | Intel      | Xeon E5/Core i7 IIO PCI E... | 27    | pcieport   | 799CC190DB |
| 8086:3c08 | 103c:18a8 | Intel      | Xeon E5/Core i7 IIO PCI E... | 27    | pcieport   | 799CC190DB |
| 8086:3c09 | 103c:18a8 | Intel      | Xeon E5/Core i7 IIO PCI E... | 27    | pcieport   | 799CC190DB |
| 8086:3c0a | 103c:18a8 | Intel      | Xeon E5/Core i7 IIO PCI E... | 27    | pcieport   | 799CC190DB |
| 8086:3c0b | 103c:18a8 | Intel      | Xeon E5/Core i7 IIO PCI E... | 27    | pcieport   | 799CC190DB |
| 1166:0103 |           | Broadcom   | EPB PCI-Express to PCI-X ... | 26    | shpchp     | 3A68279F78 |
| 8086:25f8 |           | Intel      | 5000 Series Chipset PCI E... | 26    | pcieport   | 3A68279F78 |
| 1912:0012 |           | Renesas... | SH7757 PCIe-PCI Bridge [PPB] | 25    | shpchp     | 58A63B2A93 |
| 1912:0013 |           | Renesas... | SH7757 PCIe Switch [PS]      | 25    | shpchp     | 58A63B2A93 |
| 1912:001a | 1912:001a | Renesas... | SH7758 PCIe-PCI Bridge [PPB] | 25    | shpchp     | F90168C69D |
| 1912:001d | 1912:001d | Renesas... | SH7758 PCIe Switch [PS]      | 25    | pcieport   | F90168C69D |
| 8086:2033 | 8086:0000 | Intel      | Sky Lake-E PCI Express Ro... | 25    | pcieport   | 2D1D9030E8 |
| 8086:3a40 | 103c:330d | Intel      | 82801JI (ICH10 Family) PC... | 25    | pcieport   | C56840DF98 |
| 8086:25f9 |           | Intel      | 5000 Series Chipset PCI E... | 24    | pcieport   | 3A68279F78 |
| 8086:2f08 | 8086:0000 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 24    | pcieport   | F90168C69D |
| 8086:37c0 | beef:dead | Intel      | PCI bridge                   | 24    | pcieport   | 331227D869 |
| 8086:2f02 | 8086:0000 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 23    | pcieport   | F90168C69D |
| 1556:be00 |           | PLDA       | PCI Express Bridge           | 22    | shpchp     | 2A87802C58 |
| 8086:2c01 | 8086:8086 | Intel      | Xeon 5500/Core i7 QuickPa... | 22    |            | 6D447A2756 |
| 8086:2c10 | 8086:8086 | Intel      | Xeon 5500/Core i7 QPI Link 0 | 22    |            | 6D447A2756 |
| 8086:2c11 | 8086:8086 | Intel      | Xeon 5500/Core i7 QPI Phy... | 22    |            | 6D447A2756 |
| 8086:2c14 | 8086:8086 | Intel      | Xeon 5500/Core i7 QPI Link 1 | 22    |            | 6D447A2756 |
| 8086:2c15 | 8086:8086 | Intel      | Xeon 5500/Core i7 QPI Phy... | 22    |            | 6D447A2756 |
| 8086:2c18 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 22    |            | 6D447A2756 |
| 8086:2c19 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 22    |            | 6D447A2756 |
| 8086:2c1a | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 22    |            | 6D447A2756 |
| 8086:2c1c | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 22    |            | 6D447A2756 |
| 8086:2c20 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 22    |            | 6D447A2756 |
| 8086:2c21 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 22    |            | 6D447A2756 |
| 8086:2c22 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 22    |            | 6D447A2756 |
| 8086:2c23 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 22    |            | 6D447A2756 |
| 8086:2c28 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 22    |            | 6D447A2756 |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:5229 | 10ec:5229 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 598D43B1F2 |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:19e2 | 8086:0000 | Intel      | Atom Processor C3000 Seri... | 2     | qat_c3xxx  | 40E07B4DAD |
| 8086:37c8 | 8086:0000 | Intel      | C62x Chipset QuickAssist ... | 2     | qat_c62x   | 331227D869 |
| 8086:0434 | 8086:0000 | Intel      | DH89XXCC Series QAT          | 1     |            | 14C76E0C83 |
| 8086:1f18 | 15d9:0820 | Intel      | Atom processor C2000 QAT     | 1     |            | B9AC0D657E |
| 8086:225c | 8086:2500 | Intel      | Xeon Phi coprocessor SE10... | 1     | mic_host   | 9D9DA282F6 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a1ba | 8086:35ce | Intel      | C620 Series Chipset Famil... | 19    | mei_me     | D373AF93CD |
| 8086:a1be | 8086:35ce | Intel      | C620 Series Chipset Famil... | 19    |            | D373AF93CD |
| 8086:a1bb | 8086:35ce | Intel      | C620 Series Chipset Famil... | 18    |            | D373AF93CD |
| 8086:8d3a | 15d9:0821 | Intel      | C610/X99 series chipset M... | 16    | mei_me     | 17BF7A3CBC |
| 8086:8d3b | 15d9:0821 | Intel      | C610/X99 series chipset M... | 16    |            | 17BF7A3CBC |
| 8086:a1ba | 8086:7270 | Intel      | C620 Series Chipset Famil... | 14    | mei_me     | FD087082C0 |
| 8086:a1be | 8086:7270 | Intel      | C620 Series Chipset Famil... | 14    |            | FD087082C0 |
| 8086:1d3a | 1043:84ef | Intel      | C600/X79 series chipset M... | 13    | mei_me     | A4C832AB44 |
| 8086:1d3b | 1043:84ef | Intel      | C600/X79 series chipset M... | 13    |            | A4C832AB44 |
| 8086:a1bb | 8086:7270 | Intel      | C620 Series Chipset Famil... | 13    |            | FD087082C0 |
| 8086:1d3a | 15d9:0636 | Intel      | C600/X79 series chipset M... | 12    | mei_me     | DD93F62FFC |
| 8086:1d3b | 15d9:0636 | Intel      | C600/X79 series chipset M... | 12    |            | DD93F62FFC |
| 8086:8d3a | 8086:7270 | Intel      | C610/X99 series chipset M... | 9     | mei_me     | 2F38C3FD0E |
| 8086:8d3b | 8086:7270 | Intel      | C610/X99 series chipset M... | 9     |            | 2F38C3FD0E |
| 8086:1d3a | 1028:04fa | Intel      | C600/X79 series chipset M... | 7     | mei_me     | 1A32B081A7 |
| 8086:1d3b | 1028:04fa | Intel      | C600/X79 series chipset M... | 7     |            | 1A32B081A7 |
| 8086:8d3a | 1043:85f6 | Intel      | C610/X99 series chipset M... | 7     | mei_me     | 4158CB76EF |
| 8086:8d3b | 1043:85f6 | Intel      | C610/X99 series chipset M... | 7     |            | 4158CB76EF |
| 8086:a1ba | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     | mei_me     | CEE7ED2CE9 |
| 8086:a1bb | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     |            | CEE7ED2CE9 |
| 8086:a1be | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     |            | CEE7ED2CE9 |
| 8086:1d3a | 1028:048c | Intel      | C600/X79 series chipset M... | 6     | mei_me     | 4CE6A061A6 |
| 8086:1d3a | 1028:04ce | Intel      | C600/X79 series chipset M... | 6     | mei_me     | 7A9C742839 |
| 8086:1d3b | 1028:048c | Intel      | C600/X79 series chipset M... | 6     |            | 4CE6A061A6 |
| 8086:1d3b | 1028:04ce | Intel      | C600/X79 series chipset M... | 6     |            | 7A9C742839 |
| 8086:8d3a | 1028:0601 | Intel      | C610/X99 series chipset M... | 6     | mei_me     | F90168C69D |
| 8086:8d3b | 1028:0601 | Intel      | C610/X99 series chipset M... | 6     |            | F90168C69D |
| 8086:a1ba | 1043:871e | Intel      | C620 Series Chipset Famil... | 6     | mei_me     | AFAB4598A7 |
| 8086:a1be | 1043:871e | Intel      | C620 Series Chipset Famil... | 6     |            | AFAB4598A7 |
| 8086:8d3a | 15d9:0831 | Intel      | C610/X99 series chipset M... | 5     | mei_me     | 64918C950D |
| 8086:8d3b | 15d9:0831 | Intel      | C610/X99 series chipset M... | 5     |            | 64918C950D |
| 8086:a13a | 1028:06a5 | Intel      | 100 Series/C230 Series Ch... | 5     | mei_me     | E2A3815DD2 |
| 8086:a13a | 8086:1999 | Intel      | 100 Series/C230 Series Ch... | 5     | mei_me     | 98C12554CB |
| 8086:a13b | 1028:06a5 | Intel      | 100 Series/C230 Series Ch... | 5     | mei_me     | E2A3815DD2 |
| 8086:a1ba | 1590:00eb | Intel      | C620 Series Chipset Famil... | 5     | mei_me     | 3120E02C21 |
| 8086:a1bb | 1043:871e | Intel      | C620 Series Chipset Famil... | 5     |            | AFAB4598A7 |
| 8086:a1be | 1590:00eb | Intel      | C620 Series Chipset Famil... | 5     |            | 3120E02C21 |
| 8086:1d3a | 8086:357e | Intel      | C600/X79 series chipset M... | 4     | mei_me     | 0FADD1EBE3 |
| 8086:1d3a | 8086:35a0 | Intel      | C600/X79 series chipset M... | 4     | mei_me     | FE1E6CFF79 |
| 8086:1d3b | 8086:357e | Intel      | C600/X79 series chipset M... | 4     |            | 0FADD1EBE3 |
| 8086:1d3b | 8086:35a0 | Intel      | C600/X79 series chipset M... | 4     |            | FE1E6CFF79 |
| 8086:a13b | 8086:1999 | Intel      | 100 Series/C230 Series Ch... | 4     | mei_me     | 98C12554CB |
| 8086:a1ba | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     | mei_me     | E9A1FC86F9 |
| 8086:a1ba | 1028:0739 | Intel      | C620 Series Chipset Famil... | 4     | mei_me     | 2D1D9030E8 |
| 8086:a1ba | 15d9:096d | Intel      | C620 Series Chipset Famil... | 4     | mei_me     | F9D0B2BC99 |
| 8086:a1ba | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 4     | mei_me     | CD543E37E2 |
| 8086:a1bb | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     |            | E9A1FC86F9 |
| 8086:a1bb | 15d9:096d | Intel      | C620 Series Chipset Famil... | 4     |            | F9D0B2BC99 |
| 8086:a1bb | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 4     |            | CD543E37E2 |
| 8086:a1be | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     |            | E9A1FC86F9 |
| 8086:a1be | 15d9:096d | Intel      | C620 Series Chipset Famil... | 4     |            | F9D0B2BC99 |
| 8086:a1be | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 4     |            | CD543E37E2 |
| 8086:a360 | 8086:7270 | Intel      | Cannon Lake PCH HECI Cont... | 4     | mei_me     | B8FFB92409 |
| 8086:1d3a | 1028:04f8 | Intel      | C600/X79 series chipset M... | 3     | mei_me     | EA68439F2E |
| 8086:1d3a | 1028:0528 | Intel      | C600/X79 series chipset M... | 3     | mei_me     | 31EA0B6D96 |
| 8086:1d3b | 1028:04f8 | Intel      | C600/X79 series chipset M... | 3     |            | EA68439F2E |
| 8086:1d3b | 1028:0528 | Intel      | C600/X79 series chipset M... | 3     |            | 31EA0B6D96 |
| 8086:8c3a | 15d9:0805 | Intel      | 8 Series/C220 Series Chip... | 3     | mei_me     | 16BEFD9DC3 |
| 8086:8c3a | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 3     | mei_me     | 34DBD86F7B |
| 8086:8c3b | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 3     |            | 34DBD86F7B |
| 8086:8d3a | 1028:0600 | Intel      | C610/X99 series chipset M... | 3     | mei_me     | A98D12AD3E |
| 8086:8d3a | 1458:1000 | Intel      | C610/X99 series chipset M... | 3     | mei_me     | 2F69A2F89C |
| 8086:8d3a | 15d9:0834 | Intel      | C610/X99 series chipset M... | 3     | mei_me     | FA4BECDE8B |
| 8086:8d3a | 1d49:0a00 | Intel      | C610/X99 series chipset M... | 3     | mei_me     | 3510DD7B10 |
| 8086:8d3b | 1028:0600 | Intel      | C610/X99 series chipset M... | 3     |            | A98D12AD3E |
| 8086:8d3b | 15d9:0834 | Intel      | C610/X99 series chipset M... | 3     |            | FA4BECDE8B |
| 8086:8d3b | 1d49:0a00 | Intel      | C610/X99 series chipset M... | 3     |            | 3510DD7B10 |
| 8086:a1ba | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     | mei_me     | E752263E49 |
| 8086:a1ba | 1028:073a | Intel      | C620 Series Chipset Famil... | 3     | mei_me     | 33FDE2B5FB |
| 8086:a1ba | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 3     | mei_me     | ED3C250112 |
| 8086:a1ba | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     | mei_me     | 7AD1F5EB4E |
| 8086:a1ba | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     | mei_me     | C682299C13 |
| 8086:a1ba | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     | mei_me     | 5658A2FB98 |
| 8086:a1ba | 1849:a1ba | Intel      | C620 Series Chipset Famil... | 3     | mei_me     | 35C171899E |
| 8086:a1bb | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | E752263E49 |
| 8086:a1bb | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     |            | 7AD1F5EB4E |
| 8086:a1bb | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     |            | C682299C13 |
| 8086:a1be | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | E752263E49 |
| 8086:a1be | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     |            | 7AD1F5EB4E |
| 8086:a1be | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     |            | C682299C13 |
| 8086:a328 | 1028:088e | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | 2A87802C58 |
| 8086:a328 | 15d9:1a1b | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | 16D1B33F25 |
| 8086:a328 | 15d9:1a1d | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | E57FDAECA4 |
| 8086:a360 | 1028:088e | Intel      | Cannon Lake PCH HECI Cont... | 3     | mei_me     | 2A87802C58 |
| 8086:a360 | 15d9:1a1b | Intel      | Cannon Lake PCH HECI Cont... | 3     | mei_me     | 16D1B33F25 |
| 8086:a360 | 15d9:1a1d | Intel      | Cannon Lake PCH HECI Cont... | 3     | mei_me     | E57FDAECA4 |
| 8086:a361 | 15d9:1a1b | Intel      | 300 Series Chipset HECI #2   | 3     |            | 16D1B33F25 |
| 8086:a364 | 1028:088e | Intel      | Cannon Lake PCH HECI Cont... | 3     | mei_me     | 2A87802C58 |
| 8086:a364 | 15d9:1a1b | Intel      | Cannon Lake PCH HECI Cont... | 3     | mei_me     | 16D1B33F25 |
| 8086:19d3 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 2     |            | 40E07B4DAD |
| 8086:1d3a | 15d9:0626 | Intel      | C600/X79 series chipset M... | 2     | mei_me     | 00FDD71981 |
| 8086:1d3a | 15d9:0660 | Intel      | C600/X79 series chipset M... | 2     | mei_me     | AFE42B7E58 |
| 8086:1d3a | 8086:3594 | Intel      | C600/X79 series chipset M... | 2     | mei_me     | FBDCC4D1F5 |
| 8086:1d3b | 15d9:0626 | Intel      | C600/X79 series chipset M... | 2     |            | 00FDD71981 |
| 8086:1d3b | 15d9:0660 | Intel      | C600/X79 series chipset M... | 2     |            | AFE42B7E58 |
| 8086:1d3b | 8086:3594 | Intel      | C600/X79 series chipset M... | 2     |            | FBDCC4D1F5 |
| 8086:319a | 1019:a94d | Intel      | Celeron/Pentium Silver Pr... | 2     | mei_me     | 598D43B1F2 |
| 8086:8c3a | 15d9:0803 | Intel      | 8 Series/C220 Series Chip... | 2     | mei_me     | 869444ACF6 |
| 8086:8c3a | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 2     | mei_me     | 9AF20F3BA9 |
| 8086:8c3a | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 2     | mei_me     | 14C76E0C83 |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1498 | 1022:1498 | AMD        | Starship/Matisse PTDMA       | 7     |            | 2175466EA1 |
| 1022:1486 | 1022:1486 | AMD        | Starship/Matisse Cryptogr... | 6     | ccp        | 2175466EA1 |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 5     |            | 5D00EDD035 |
| 1022:1486 | 1458:1000 | AMD        | Starship/Matisse Cryptogr... | 3     | ccp        | D140FF934B |
| 1022:1498 | 1458:1000 | AMD        | Starship/Matisse PTDMA       | 3     |            | D140FF934B |
| 1022:1456 | 1022:1456 | AMD        | Family 17h (Models 00h-0f... | 2     | ccp        | F6F6B1BC99 |
| 1022:1456 | 1458:1000 | AMD        | Family 17h (Models 00h-0f... | 2     | ccp        | 6D486A7EE9 |
| 1022:1468 | 1022:1468 | AMD        | Zeppelin Cryptographic Co... | 2     | ccp        | F6F6B1BC99 |
| 1022:1468 | 1458:1000 | AMD        | Zeppelin Cryptographic Co... | 2     | ccp        | 6D486A7EE9 |
| 1022:1456 | 1028:07f9 | AMD        | Family 17h (Models 00h-0f... | 1     | ccp        | 8F7FF50C55 |
| 1022:1468 | 1028:07f9 | AMD        | Zeppelin Cryptographic Co... | 1     | ccp        | 8F7FF50C55 |
| 1022:1486 | 1028:08ff | AMD        | Starship/Matisse Cryptogr... | 1     |            | B7F3606E31 |
| 1022:1498 | 1028:08ff | AMD        | Starship/Matisse PTDMA       | 1     |            | B7F3606E31 |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 104c:8023 | 15d9:0100 | Texas I... | TSB43AB22A IEEE-1394a-200... | 5     | firewir... | C83DC07B7C |
| 1106:3403 | 1043:8384 | VIA Tec... | VT6315 Series Firewire Co... | 5     | firewir... | C3665EBF57 |
| 104c:8023 | 15d9:0805 | Texas I... | TSB43AB22A IEEE-1394a-200... | 4     | firewir... | 16BEFD9DC3 |
| 1102:4001 | 1102:0010 | Creativ... | SB Audigy FireWire Port      | 4     | firewir... | F879FD97F7 |
| 104c:8023 | 8086:34e2 | Texas I... | TSB43AB22A IEEE-1394a-200... | 3     | firewir... | 1D4FEABAAA |
| 1106:3403 | 1106:3403 | VIA Tec... | VT6315 Series Firewire Co... | 3     | firewir... | D8182AC89A |
| 104c:823f | 8086:3594 | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 2     | firewir... | FBDCC4D1F5 |
| 1106:3044 | 1462:6520 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 2     | firewir... | B8300AFB35 |
| 104c:8023 | 10f1:2895 | Texas I... | TSB43AB22A IEEE-1394a-200... | 1     | firewir... | 768571B831 |
| 104c:8023 | 15d9:0653 | Texas I... | TSB43AB22A IEEE-1394a-200... | 1     | firewir... | 171EE8DB12 |
| 104c:8023 | 15d9:1411 | Texas I... | TSB43AB22A IEEE-1394a-200... | 1     | firewir... | 039BF2C96A |
| 104c:823f | 3412:7856 | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 1     | firewir... | 21E2FBBB75 |
| 1106:3044 | 108e:534d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 1     | firewir... | 1F35F79302 |
| 1106:3044 | 1106:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 1     | firewir... | CC8DB94EBA |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:5a23 | 1002:5a23 | AMD        | RD890S/RD990 I/O Memory M... | 9     |            | AD61EFB931 |
| 1022:1577 | 1022:1577 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 5D00EDD035 |
| 8086:19a2 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 2     | pcieport   | 40E07B4DAD |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1a03:2000 | 1a03:2000 | ASPEED ... | ASPEED Graphics Family       | 48    | ast        | 2F38C3FD0E |
| 102b:0533 | 103c:3381 | Matrox ... | MGA G200EH                   | 41    | mgag200    | 799CC190DB |
| 1002:515e | 103c:31fb | AMD        | ES1000                       | 37    | radeon     | C56840DF98 |
| 102b:0522 | 8086:0103 | Matrox ... | MGA G200e [Pilot] ServerE... | 22    | mgag200    | 98C12554CB |
| 1a03:2000 | 15d9:0821 | ASPEED ... | ASPEED Graphics Family       | 16    | ast        | 17BF7A3CBC |
| 10de:1eba | 10de:0000 | Nvidia     | 3D controller                | 15    | nvidia     | 4391DFF8D2 |
| 102b:0532 | 1028:0235 | Matrox ... | MGA G200eW WPCM450           | 14    | mgag200    | 4DEBADA4BF |
| 102b:0532 | 15d9:0006 | Matrox ... | MGA G200eW WPCM450           | 13    | mgag200    | AFF808A68F |
| 102b:0534 | 15d9:0636 | Matrox ... | G200eR2                      | 12    | mgag200    | DD93F62FFC |
| 102b:0522 | 8086:0101 | Matrox ... | MGA G200e [Pilot] ServerE... | 11    | mgag200    | F0473D3564 |
| 102b:0522 | 19a2:0101 | Matrox ... | MGA G200e [Pilot] ServerE... | 9     | mgag200    | 2175466EA1 |
| 102b:0530 | 1014:0369 | Matrox ... | MGA G200EV                   | 9     | mgag200    | 882EA8E25E |
| 102b:0536 |           | Matrox ... | Integrated Matrox G200eW3... | 8     | mgag200    | 2A87802C58 |
| 1a03:2000 | 1043:85f9 | ASPEED ... | ASPEED Graphics Family       | 8     | ast        | 4158CB76EF |
| 102b:0534 | 1014:0405 | Matrox ... | G200eR2                      | 7     | mgag200    | 58A63B2A93 |
| 102b:0532 | 1028:0236 | Matrox ... | MGA G200eW WPCM450           | 6     | mgag200    | 5FBC90E0CD |
| 102b:0532 | 1028:02a4 | Matrox ... | MGA G200eW WPCM450           | 6     | mgag200    | 741DB5D841 |
| 102b:0532 | 15d9:ab11 | Matrox ... | MGA G200eW WPCM450           | 6     | mgag200    | D5563E325C |
| 102b:0534 | 1028:048c | Matrox ... | G200eR2                      | 6     | mgag200    | 4CE6A061A6 |
| 102b:0534 | 1028:04ce | Matrox ... | G200eR2                      | 6     | mgag200    | 7A9C742839 |
| 102b:0534 | 1028:0601 | Matrox ... | G200eR2                      | 6     | mgag200    | F90168C69D |
| 10de:128b | 1462:8c93 | Nvidia     | GK208B [GeForce GT 710]      | 6     | nouveau    | 16BEFD9DC3 |
| 10de:128b | 196e:118b | Nvidia     | GK208B [GeForce GT 710]      | 6     | nouveau    | 3A68279F78 |
| 1002:9874 | 1002:1871 | AMD        | Wani [Radeon R5/R6/R7 Gra... | 5     | amdgpu     | 5D00EDD035 |
| 102b:0532 | 1028:028c | Matrox ... | MGA G200eW WPCM450           | 5     | mgag200    | 0094B64AB2 |
| 102b:0532 | 15d9:0001 | Matrox ... | MGA G200eW WPCM450           | 5     | mgag200    | 6BA00F03DE |
| 102b:0534 | 1028:04fa | Matrox ... | G200eR2                      | 5     | mgag200    | 87A79FD79B |
| 102b:0534 | 1028:06a5 | Matrox ... | G200eR2                      | 5     | mgag200    | E2A3815DD2 |
| 102b:0538 | 1590:00e4 | Matrox ... | MGA G200eH3                  | 5     | mgag200    | 3120E02C21 |
| 19e5:1711 |           | Huawei ... | Hi171x Series [iBMC Intel... | 5     | hibmc_drm  | 63BDABB5A4 |
| 1a03:2000 | 1043:86ed | ASPEED ... | ASPEED Graphics Family       | 5     | ast        | AFAB4598A7 |
| 1a03:2000 | 1458:1000 | ASPEED ... | ASPEED Graphics Family       | 5     | ast        | D140FF934B |
| 1a03:2000 | 15d9:0801 | ASPEED ... | ASPEED Graphics Family       | 5     | ast        | 7F5062CA8F |
| 1a03:2000 | 15d9:0831 | ASPEED ... | ASPEED Graphics Family       | 5     | ast        | 64918C950D |
| 1002:515e | 1028:01b2 | AMD        | ES1000                       | 4     | radeon     | 252659BF58 |
| 1002:515e | 1028:01e7 | AMD        | ES1000                       | 4     | radeon     | EA66809CE7 |
| 102b:0522 | 103c:0100 | Matrox ... | MGA G200e [Pilot] ServerE... | 4     | mgag200    | 28B04C3004 |
| 102b:0532 | 1028:02f1 | Matrox ... | MGA G200eW WPCM450           | 4     | mgag200    | DEE1F70644 |
| 102b:0532 | 1028:04de | Matrox ... | MGA G200eW WPCM450           | 4     | mgag200    | E24D0E827B |
| 102b:0532 | 15d9:0100 | Matrox ... | MGA G200eW WPCM450           | 4     | mgag200    | C83DC07B7C |
| 102b:0532 | 15d9:0400 | Matrox ... | MGA G200eW WPCM450           | 4     | mgag200    | B3C09674CF |
| 102b:0532 | 15d9:060f | Matrox ... | MGA G200eW WPCM450           | 4     | mgag200    | CF99AAD395 |
| 102b:0532 | 15d9:bc11 | Matrox ... | MGA G200eW WPCM450           | 4     | mgag200    | AD61EFB931 |
| 102b:0536 | 1028:0715 | Matrox ... | Integrated Matrox G200eW3... | 4     | mgag200    | E9A1FC86F9 |
| 10de:0638 | 10de:062c | Nvidia     | G94GL [Quadro FX 1800]       | 4     | nvidia     | 1D4FEABAAA |
| 10de:11b4 | 10de:1096 | Nvidia     | GK104GL [Quadro K4200]       | 4     | nvidia     | F508BB4C99 |
| 1a03:2000 | 15d9:096d | ASPEED ... | ASPEED Graphics Family       | 4     | ast        | F9D0B2BC99 |
| 1a03:2000 | 15d9:0981 | ASPEED ... | ASPEED Graphics Family       | 4     | ast        | CD543E37E2 |
| 1002:515e | 1028:01b3 | AMD        | ES1000                       | 3     | radeon     | 8571D09FE7 |
| 1002:515e | 8086:3476 | AMD        | ES1000                       | 3     | radeon     | D471D2B279 |
| 102b:0522 | 1734:11cc | Matrox ... | MGA G200e [Pilot] ServerE... | 3     | mgag200    | 9C16958A72 |
| 102b:0522 | 19a2:0100 | Matrox ... | MGA G200e [Pilot] ServerE... | 3     | mgag200    | 91AD975174 |
| 102b:0532 | 1028:0237 | Matrox ... | MGA G200eW WPCM450           | 3     | mgag200    | B506487E48 |
| 102b:0532 | 1028:02a6 | Matrox ... | MGA G200eW WPCM450           | 3     | mgag200    | 650772B11D |
| 102b:0532 | 1028:0444 | Matrox ... | MGA G200eW WPCM450           | 3     | mgag200    | B913A90C28 |
| 102b:0532 | 1028:04dd | Matrox ... | MGA G200eW WPCM450           | 3     | mgag200    | D4CCC85620 |
| 102b:0532 | 15d9:0600 | Matrox ... | MGA G200eW WPCM450           | 3     | mgag200    | C17B3F71EC |
| 102b:0534 | 1028:04f8 | Matrox ... | G200eR2                      | 3     | mgag200    | EA68439F2E |
| 102b:0534 | 1028:0528 | Matrox ... | G200eR2                      | 3     | mgag200    | 31EA0B6D96 |
| 102b:0534 | 1028:0600 | Matrox ... | G200eR2                      | 3     | mgag200    | A98D12AD3E |
| 102b:0534 | 1d49:0a01 | Matrox ... | G200eR2                      | 3     | mgag200    | 3510DD7B10 |
| 102b:0536 | 1028:0716 | Matrox ... | Integrated Matrox G200eW3... | 3     | mgag200    | E752263E49 |
| 10de:1287 | 1043:84f5 | Nvidia     | GK208B [GeForce GT 730]      | 3     | nvidia     | 5D93D067D7 |
| 10de:1bb1 | 103c:11a3 | Nvidia     | GP104GL [Quadro P4000]       | 3     | nouveau    | 9D6E46ECA9 |
| 10de:1e04 | 1458:37c4 | Nvidia     | TU102 [GeForce RTX 2080 Ti]  | 3     | nvidia     | F9D0B2BC99 |
| 1a03:2000 | 1043:84eb | ASPEED ... | ASPEED Graphics Family       | 3     | ast        | 6ACBF140D4 |
| 1a03:2000 | 1043:8544 | ASPEED ... | ASPEED Graphics Family       | 3     | ast        | AE3BFE95C9 |
| 1a03:2000 | 15d9:0728 | ASPEED ... | ASPEED Graphics Family       | 3     | ast        | 937DE612E9 |
| 1a03:2000 | 15d9:0834 | ASPEED ... | ASPEED Graphics Family       | 3     | ast        | FA4BECDE8B |
| 1a03:2000 | 15d9:0892 | ASPEED ... | ASPEED Graphics Family       | 3     | ast        | 822418675E |
| 1a03:2000 | 15d9:0921 | ASPEED ... | ASPEED Graphics Family       | 3     | ast        | 34DBD86F7B |
| 1a03:2000 | 15d9:0953 | ASPEED ... | ASPEED Graphics Family       | 3     | ast        | 7AD1F5EB4E |
| 1a03:2000 | 15d9:095d | ASPEED ... | ASPEED Graphics Family       | 3     | ast        | C682299C13 |
| 1a03:2000 | 15d9:1a1b | ASPEED ... | ASPEED Graphics Family       | 3     | ast        | 16D1B33F25 |
| 1002:5159 | 1028:016d | AMD        | RV100 [Radeon 7000 / Rade... | 2     | radeon     | 08919C80E8 |
| 1002:515e | 8086:346c | AMD        | ES1000                       | 2     | radeon     | 390F15B7F9 |
| 1002:515e | 8086:3486 | AMD        | ES1000                       | 2     | radeon     | 0A3F6D305B |
| 1002:66af | 1002:081e | AMD        | Vega 20 [Radeon VII]         | 2     | amdgpu     | 0343B901D9 |
| 1002:6771 | 1028:2120 | AMD        | Caicos XTX [Radeon HD 849... | 2     | radeon     | 61DFD26E01 |
| 1002:6798 | 174b:3001 | AMD        | Tahiti XT [Radeon HD 7970... | 2     | radeon     | BEA324B5DA |
| 1002:67df | 1da2:e366 | AMD        | Ellesmere [Radeon RX 470/... | 2     | amdgpu     | D09F385D74 |
| 1002:68f9 | 1462:2127 | AMD        | Cedar [Radeon HD 5000/600... | 2     | radeon     | E014B80891 |
| 102b:0522 | 1033:8372 | Matrox ... | MGA G200e [Pilot] ServerE... | 2     | mgag200    | 460A274240 |
| 102b:0522 | 103c:31fa | Matrox ... | MGA G200e [Pilot] ServerE... | 2     | mgag200    | 20AE4260BB |
| 102b:0522 | 1734:108e | Matrox ... | MGA G200e [Pilot] ServerE... | 2     | mgag200    | A0F9679F57 |
| 102b:0522 | 8086:0102 | Matrox ... | MGA G200e [Pilot] ServerE... | 2     | mgag200    | DAA63A315C |
| 102b:0532 | 1028:028d | Matrox ... | MGA G200eW WPCM450           | 2     | mgag200    | 2B9980B42B |
| 102b:0532 | 1028:029b | Matrox ... | MGA G200eW WPCM450           | 2     | mgag200    | 1F6AFDC077 |
| 102b:0532 | 1028:02a3 | Matrox ... | MGA G200eW WPCM450           | 2     | mgag200    | 07FABCF50F |
| 102b:0532 | 1028:02a5 | Matrox ... | MGA G200eW WPCM450           | 2     | mgag200    | F21A3DB016 |
| 102b:0532 | 1028:02d3 | Matrox ... | MGA G200eW WPCM450           | 2     | mgag200    | C3EC3FCF73 |
| 102b:0532 | 1028:02d4 | Matrox ... | MGA G200eW WPCM450           | 2     | mgag200    | 1AFA47E662 |
| 102b:0532 | 15d9:0007 | Matrox ... | MGA G200eW WPCM450           | 2     | mgag200    | A652ED3DB4 |
| 102b:0532 | 15d9:0660 | Matrox ... | MGA G200eW WPCM450           | 2     | mgag200    | AFE42B7E58 |
| 102b:0532 | 15d9:a811 | Matrox ... | MGA G200eW WPCM450           | 2     | mgag200    | 340A3648A2 |
| 102b:0532 | 15d9:ba11 | Matrox ... | MGA G200eW WPCM450           | 2     | mgag200    | 6381FD461D |
| 102b:0532 | 15d9:cd11 | Matrox ... | MGA G200eW WPCM450           | 2     | mgag200    | CF37C43C55 |
| 102b:0534 | 1028:05e5 | Matrox ... | G200eR2                      | 2     | mgag200    | EB7B7FD10B |
| 102b:0534 | 1028:0639 | Matrox ... | G200eR2                      | 2     | mgag200    | B39BBB71E2 |
| 102b:0534 | 1028:063a | Matrox ... | G200eR2                      | 2     | mgag200    | E4DEE6FAF7 |

### Input device controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1102:7003 | 1102:0040 | Creativ... | SB Audigy Game Port          | 2     | Emu10k1... | F879FD97F7 |
| 1102:7002 | 1102:0020 | Creativ... | SB Live! Game Port           | 1     | emu10k1_gp | 80DC2F8936 |
| 1102:7003 | 1102:0060 | Creativ... | SB Audigy Game Port          | 1     | emu10k1_gp | D471D2B279 |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1481 | 1022:1481 | AMD        | Starship/Matisse IOMMU       | 5     |            | 2175466EA1 |
| 1002:5a23 | 1028:0444 | AMD        | RD890S/RD990 I/O Memory M... | 2     |            | B913A90C28 |
| 1022:1481 | 1458:1000 | AMD        | Starship/Matisse IOMMU       | 2     |            | D140FF934B |
| 1002:5a23 | 103c:1762 | AMD        | RD890S/RD990 I/O Memory M... | 1     |            | E60DA0D6CE |
| 1002:5a23 | 103c:3324 | AMD        | RD890S/RD990 I/O Memory M... | 1     |            | 7CE46A749E |
| 1022:1451 | 1028:07f9 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 8F7FF50C55 |
| 1022:1481 | 1028:08ff | AMD        | Starship/Matisse IOMMU       | 1     |            | B7F3606E31 |
| 8086:1f16 | 15d9:0820 | Intel      | Atom processor C2000 RCEC    | 1     |            | B9AC0D657E |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 103c:3302 | 103c:3305 | Hewlett... | Integrated Lights-Out Sta... | 21    | ipmi_si    | FA5961B4C8 |

### Isdn adapter (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1244:0a00 | 1244:0a00 | AVM        | A1 ISDN [Fritz]              | 1     | fcpci      | 750A124EF3 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a1a1 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 18    |            | D373AF93CD |
| 8086:a1a1 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 14    |            | FD087082C0 |
| 8086:a36f | 8086:7270 | Intel      | Cannon Lake PCH Shared SRAM  | 12    |            | CF083F4B62 |
| 8086:a1a1 | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     |            | CEE7ED2CE9 |
| 8086:a121 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 6     |            | 98C12554CB |
| 8086:a1a1 | 1043:871e | Intel      | C620 Series Chipset Famil... | 6     |            | AFAB4598A7 |
| 8086:a36f |           | Intel      | Cannon Lake PCH Shared SRAM  | 6     |            | 2A87802C58 |
| 8086:a121 | 1028:06a5 | Intel      | 100 Series/C230 Series Ch... | 5     |            | E2A3815DD2 |
| 8086:a1a1 | 1590:00eb | Intel      | C620 Series Chipset Famil... | 5     |            | 3120E02C21 |
| 1590:005f | 1590:005f | Hewlett... | Memory controller            | 4     |            | 3A14AEA222 |
| 8086:a1a1 | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     |            | E9A1FC86F9 |
| 8086:a1a1 | 1028:0739 | Intel      | C620 Series Chipset Famil... | 4     |            | 2D1D9030E8 |
| 8086:a1a1 | 15d9:096d | Intel      | C620 Series Chipset Famil... | 4     |            | F9D0B2BC99 |
| 8086:a1a1 | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 4     |            | CD543E37E2 |
| 8086:a36f | 8086:a36f | Intel      | Cannon Lake PCH Shared SRAM  | 4     |            | B8FFB92409 |
| 8086:a1a1 | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | E752263E49 |
| 8086:a1a1 | 1028:073a | Intel      | C620 Series Chipset Famil... | 3     |            | 33FDE2B5FB |
| 8086:a1a1 | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 3     |            | ED3C250112 |
| 8086:a1a1 | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     |            | 7AD1F5EB4E |
| 8086:a1a1 | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     |            | C682299C13 |
| 8086:a1a1 | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     |            | 5658A2FB98 |
| 8086:a1a1 | 1849:a1a1 | Intel      | C620 Series Chipset Famil... | 3     |            | 35C171899E |
| 10de:0369 | 1462:cb84 | Nvidia     | MCP55 Memory Controller      | 2     |            | B8300AFB35 |
| 1912:0011 |           | Renesas... | SH7757 PCIe End-Point [PBI]  | 2     |            | EB7B7FD10B |
| 8086:19de | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 2     |            | 40E07B4DAD |
| 8086:a121 | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 8F45F37B98 |
| 8086:a121 | 15d9:089a | Intel      | 100 Series/C230 Series Ch... | 2     |            | 6B930AF6EC |
| 8086:a121 | 8086:a121 | Intel      | 100 Series/C230 Series Ch... | 2     |            | C4D59010A1 |
| 8086:a1a1 | 1028:0718 | Intel      | C620 Series Chipset Famil... | 2     |            | 1CCB5D67C2 |
| 8086:a1a1 | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     |            | DF9A63BE43 |
| 8086:a1a1 | 1028:07e5 | Intel      | C620 Series Chipset Famil... | 2     |            | 4C88B2E09B |
| 8086:a1a1 | 103c:81c6 | Intel      | C620 Series Chipset Famil... | 2     |            | 9D6E46ECA9 |
| 8086:a1a1 | 15d9:091c | Intel      | C620 Series Chipset Famil... | 2     |            | 748FB8054B |
| 8086:a1a1 | 15d9:0941 | Intel      | C620 Series Chipset Famil... | 2     |            | C619DB847B |
| 10de:005e | 10f1:2891 | Nvidia     | CK804 Memory Controller      | 1     |            | 64251B3F2A |
| 10de:005e | 10f1:2895 | Nvidia     | CK804 Memory Controller      | 1     |            | 768571B831 |
| 10de:00d3 | 10f1:2891 | Nvidia     | CK804 Memory Controller      | 1     |            | 64251B3F2A |
| 10de:00d3 | 10f1:2895 | Nvidia     | CK804 Memory Controller      | 1     |            | 768571B831 |
| 10de:0369 | 108e:534d | Nvidia     | MCP55 Memory Controller      | 1     |            | 1F35F79302 |
| 10de:0369 | 1462:2800 | Nvidia     | MCP55 Memory Controller      | 1     |            | 933EED177A |
| 1b94:1500 | 1b94:1500 | Signate... | Memory controller            | 1     |            | B3C09674CF |
| 8086:0374 |           | Intel      | 80333 Address Translation... | 1     |            | 8571D09FE7 |
| 8086:a121 | 1028:06a6 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 55471D97F1 |
| 8086:a121 | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     |            | C74A66C7E6 |
| 8086:a121 | 103c:8165 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 3C08E6393F |
| 8086:a121 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 1     |            | BB8832ACBD |
| 8086:a121 | 15d9:0886 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 80DC2F8936 |
| 8086:a121 | 15d9:088b | Intel      | 100 Series/C230 Series Ch... | 1     |            | 7202CCFD44 |
| 8086:a121 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     |            | C392838A14 |
| 8086:a121 | 1734:1222 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 0BD7D9FCEA |
| 8086:a1a1 | 1028:07cb | Intel      | C620 Series Chipset Famil... | 1     |            | 5B9EC879FC |
| 8086:a1a1 | 1458:5001 | Intel      | C620 Series Chipset Famil... | 1     |            | 7E93E1B694 |
| 8086:a1a1 | 15d9:0962 | Intel      | C620 Series Chipset Famil... | 1     |            | 57460AA45B |
| 8086:a1a1 | 15d9:096e | Intel      | C620 Series Chipset Famil... | 1     |            | 4D0ED95E02 |
| 8086:a1a1 | 15d9:0986 | Intel      | C620 Series Chipset Famil... | 1     |            | 331227D869 |
| 8086:a1a1 | 15d9:0987 | Intel      | C620 Series Chipset Famil... | 1     |            | 893E9D69F2 |
| 8086:a1a1 | 1734:1230 | Intel      | C620 Series Chipset Famil... | 1     |            | 86AB491564 |
| 8086:a1a1 | 17aa:1037 | Intel      | C620 Series Chipset Famil... | 1     |            | 41249F2E48 |
| 8086:a1a1 | 17aa:7800 | Intel      | C620 Series Chipset Famil... | 1     |            | 2AE35CF194 |
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
| 1797:6869 |           | Intersi... | C968 PCIe SD Capture         | 1     | avc8000    | 375EC8881D |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:1639 | 103c:7055 | Broadcom   | NetXtreme II BCM5709 Giga... | 28    | bnx2       | C56840DF98 |
| 14e4:1657 | 103c:169d | Broadcom   | NetXtreme BCM5719 Gigabit... | 19    | tg3        | 799CC190DB |
| 8086:1572 | 8086:0000 | Intel      | Ethernet Controller X710 ... | 19    | i40e       | 3510DD7B10 |
| 8086:15b9 | 8086:0000 | Intel      | Ethernet Connection (3) I... | 17    | e1000e     | 4391DFF8D2 |
| 14e4:165f | 1028:1f5b | Broadcom   | NetXtreme BCM5720 Gigabit... | 16    | tg3        | F90168C69D |
| 14e4:1639 | 1028:0235 | Broadcom   | NetXtreme II BCM5709 Giga... | 14    | bnx2       | BED13D11AD |
| 8086:37d2 | 15d9:37d2 | Intel      | Ethernet Connection X722 ... | 14    | i40e       | 331227D869 |
| 14e4:164c | 103c:7038 | Broadco... | NetXtreme II BCM5708 Giga... | 10    | bnx2       | FA5961B4C8 |
| 14e4:1657 | 103c:22be | Broadcom   | NetXtreme BCM5719 Gigabit... | 10    | tg3        | 23F12250E5 |
| 8086:10fb | 8086:0003 | Intel      | 82599ES 10-Gigabit SFI/SF... | 10    | ixgbe      | 882EA8E25E |
| 8086:153a | 15d9:153a | Intel      | Ethernet Connection I217-LM  | 10    | e1000e     | 7F5062CA8F |
| 8086:10fb | 108e:7b11 | Intel      | 82599ES 10-Gigabit SFI/SF... | 9     | ixgbe      | 5A96F790B1 |
| 8086:1521 | 103c:3380 | Intel      | I350 Gigabit Network Conn... | 9     | igb        | 1E7A730FCC |
| 14e4:1639 | 1028:0236 | Broadcom   | NetXtreme II BCM5709 Giga... | 8     | bnx2       | 5FBC90E0CD |
| 14e4:163b | 1028:02a4 | Broadcom   | NetXtreme II BCM5716 Giga... | 7     | bnx2       | 741DB5D841 |
| 14e4:165f | 1028:04fa | Broadcom   | NetXtreme BCM5720 Gigabit... | 7     | tg3        | 1A32B081A7 |
| 8086:1076 | 8086:34d0 | Intel      | 82541GI Gigabit Ethernet ... | 7     | e1000      | FC38CA11F5 |
| 8086:1563 | 15d9:1563 | Intel      | Ethernet Controller 10G X... | 7     | ixgbe      | 3FC4F3458F |
| 8086:1572 | 8086:000a | Intel      | Ethernet Controller X710 ... | 7     | i40e       | CEE7ED2CE9 |
| 8086:37d1 | 17aa:4020 | Intel      | Ethernet Connection X722 ... | 7     | i40e       | CEE7ED2CE9 |
| 8086:37d2 | 17aa:4020 | Intel      | Ethernet Connection X722 ... | 7     | i40e       | CEE7ED2CE9 |
| 14e4:163b | 1028:028c | Broadcom   | NetXtreme II BCM5716 Giga... | 6     | bnx2       | 0094B64AB2 |
| 14e4:165f | 103c:22e8 | Broadcom   | NetXtreme BCM5720 Gigabit... | 6     | tg3        | 3C08E6393F |
| 8086:1572 | 8086:0001 | Intel      | Ethernet Controller X710 ... | 6     | i40e       | 3510DD7B10 |
| 14e4:164c | 1028:01b2 | Broadcom   | NetXtreme II BCM5708 Giga... | 5     | bnx2       | 252659BF58 |
| 14e4:165a | 1028:04de | Broadcom   | NetXtreme BCM5722 Gigabit... | 5     | tg3        | E24D0E827B |
| 14e4:165f | 1028:06a5 | Broadcom   | NetXtreme BCM5720 Gigabit... | 5     | tg3        | E2A3815DD2 |
| 14e4:165f | 14e4:4160 | Broadco... | NetXtreme BCM5720 Gigabit... | 5     | tg3        | E9A1FC86F9 |
| 14e4:16d8 | 14e4:4160 | Broadco... | BCM57416 NetXtreme-E Dual... | 5     | bnxt_en    | E9A1FC86F9 |
| 8086:37d1 | 15d9:37d1 | Intel      | Ethernet Connection X722 ... | 5     | i40e       | BB5C62E290 |
| 14e4:1639 | 1014:03a9 | Broadcom   | NetXtreme II BCM5709 Giga... | 4     | bnx2       | 2856AAF09F |
| 14e4:1639 | 1028:0237 | Broadco... | NetXtreme II BCM5709 Giga... | 4     | bnx2       | B506487E48 |
| 14e4:163b | 1028:028d | Broadcom   | NetXtreme II BCM5716 Giga... | 4     | bnx2       | 1A05144C7E |
| 14e4:163b | 1028:02f1 | Broadcom   | NetXtreme II BCM5716 Giga... | 4     | bnx2       | DEE1F70644 |
| 8086:105e | 8086:125e | Intel      | 82571EB/82571GB Gigabit E... | 4     | e1000e     | 460A274240 |
| 8086:1096 | 8086:3476 | Intel      | 80003ES2LAN Gigabit Ether... | 4     | e1000e     | 38109F9919 |
| 8086:1096 | 8086:3484 | Intel      | 80003ES2LAN Gigabit Ether... | 4     | e1000e     | 0A3F6D305B |
| 8086:10bc | 103c:704b | Intel      | 82571EB/82571GB Gigabit E... | 4     | e1000e     | 2B9980B42B |
| 8086:1521 | 103c:337f | Intel      | I350 Gigabit Network Conn... | 4     | igb        | 0B1954F5E9 |
| 8086:1521 | 8086:0002 | Intel      | I350 Gigabit Network Conn... | 4     | igb        | 6D486A7EE9 |
| 8086:1528 | 15d9:1528 | Intel      | Ethernet Controller 10-Gi... | 4     | ixgbe      | 937DE612E9 |
| 8086:1528 | 8086:35a0 | Intel      | Ethernet Controller 10-Gi... | 4     | ixgbe      | FE1E6CFF79 |
| 8086:15ac | 15d9:15ac | Intel      | Ethernet Connection X552 ... | 4     | ixgbe      | 9AF20F3BA9 |
| 8086:15b9 | 1028:0739 | Intel      | Ethernet Connection (3) I... | 4     | e1000e     | 2D1D9030E8 |
| 8086:15bb | 15d9:15bb | Intel      | Ethernet Connection (7) I... | 4     | e1000e     | 59C50944A0 |
| 8086:15bb | 8086:0000 | Intel      | Ethernet Connection (7) I... | 4     | e1000e     | B8FFB92409 |
| 10ec:8168 | 7470:3468 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | AD61EFB931 |
| 14e4:163b | 1028:04dd | Broadcom   | NetXtreme II BCM5716 Giga... | 3     | bnx2       | D4CCC85620 |
| 14e4:164c | 1028:01b3 | Broadcom   | NetXtreme II BCM5708 Giga... | 3     | bnx2       | 8571D09FE7 |
| 14e4:1657 | 17aa:400e | Broadcom   | NetXtreme BCM5719 Gigabit... | 3     | tg3        | 3510DD7B10 |
| 14e4:1659 | 1028:01e7 | Broadcom   | NetXtreme BCM5721 Gigabit... | 3     | tg3        | EA66809CE7 |
| 14e4:165f | 1028:04f8 | Broadcom   | NetXtreme BCM5720 Gigabit... | 3     | tg3        | EA68439F2E |
| 14e4:165f | 1028:0639 | Broadco... | NetXtreme BCM5720 Gigabit... | 3     | tg3        | E4DEE6FAF7 |
| 14e4:165f | 1028:088e | Broadcom   | NetXtreme BCM5720 Gigabit... | 3     | tg3        | 2A87802C58 |
| 14e4:16d8 | 14e4:4161 | Broadco... | BCM57416 NetXtreme-E Dual... | 3     | bnxt_en    | 6CD5E5C480 |
| 8086:105e | 8086:115e | Intel      | 82571EB/82571GB Gigabit E... | 3     | e1000e     | B3C09674CF |
| 8086:1076 | 1028:016d | Intel      | 82541GI Gigabit Ethernet ... | 3     | e1000      | 08919C80E8 |
| 8086:107d | 8086:1084 | Intel      | 82572EI Gigabit Ethernet ... | 3     | e1000e     | 837E4A9092 |
| 8086:150e | 103c:1780 | Intel      | 82580 Gigabit Network Con... | 3     | igb        | 14A3E68490 |
| 8086:1563 | 1028:1fa8 | Intel      | Ethernet Controller 10G X... | 3     | ixgbe      | 1CCB5D67C2 |
| 8086:1563 | 8086:0001 | Intel      | Ethernet Controller 10G X... | 3     | ixgbe      | 4231BB05CE |
| 8086:15b7 | 15d9:15b7 | Intel      | Ethernet Connection (2) I... | 3     | e1000e     | 8F45F37B98 |
| 8086:15b7 | 8086:0000 | Intel      | Ethernet Connection (2) I... | 3     | e1000e     | E86E339278 |
| 8086:15b9 | 1028:073a | Intel      | Ethernet Connection (3) I... | 3     | e1000e     | 33FDE2B5FB |
| 8086:15b9 | 103c:81c7 | Intel      | Ethernet Connection (3) I... | 3     | e1000e     | ED3C250112 |
| 8086:15b9 | 17aa:1038 | Intel      | Ethernet Connection (3) I... | 3     | e1000e     | 5658A2FB98 |
| 8086:37cc | 103c:81c7 | Intel      | Ethernet Connection X722     | 3     |            | ED3C250112 |
| 8086:37d1 | 103c:81c7 | Intel      | Ethernet Connection X722 ... | 3     | i40e       | ED3C250112 |
| 8086:37d2 | 8086:35ce | Intel      | Ethernet Connection X722 ... | 3     | i40e       | D373AF93CD |
| 10ec:8168 | 1019:a94d | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 598D43B1F2 |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 8F45F37B98 |
| 10ec:8168 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8168      | B8D0722935 |
| 14e4:1639 | 1028:029b | Broadcom   | NetXtreme II BCM5709 Giga... | 2     | bnx2       | 1F6AFDC077 |
| 14e4:1639 | 1028:02d3 | Broadcom   | NetXtreme II BCM5709 Giga... | 2     | bnx2       | C3EC3FCF73 |
| 14e4:1639 | 1028:02d4 | Broadcom   | NetXtreme II BCM5709 Giga... | 2     | bnx2       | 1AFA47E662 |
| 14e4:1639 | 1028:1f26 | Broadcom   | NetXtreme II BCM5709 Giga... | 2     | bnx2       | B913A90C28 |
| 14e4:1639 | 14e4:0906 | Broadco... | NetXtreme II BCM5709 Giga... | 2     | bnx2       | AFE42B7E58 |
| 14e4:1639 | 14e4:0907 | Broadcom   | NetXtreme II BCM5709 Giga... | 2     | bnx2       | D4CCC85620 |
| 14e4:1639 | 14e4:1906 | Broadco... | NetXtreme II BCM5709 Giga... | 2     | bnx2       | AFE42B7E58 |
| 14e4:163b | 1028:02a3 | Broadcom   | NetXtreme II BCM5716 Giga... | 2     | bnx2       | 07FABCF50F |
| 14e4:163b | 1028:02a5 | Broadcom   | NetXtreme II BCM5716 Giga... | 2     | bnx2       | F21A3DB016 |
| 14e4:164c | 1014:0342 | Broadcom   | NetXtreme II BCM5708 Giga... | 2     | bnx2       | 3A68279F78 |
| 14e4:165a | 1028:02a6 | Broadcom   | NetXtreme BCM5722 Gigabit... | 2     | tg3        | 650772B11D |
| 14e4:165f | 1028:05e5 | Broadco... | NetXtreme BCM5720 Gigabit... | 2     | tg3        | EB7B7FD10B |
| 14e4:165f | 1028:0890 | Broadcom   | NetXtreme BCM5720 Gigabit... | 2     | tg3        | 13E5EC2882 |
| 14e4:165f | 14e4:165f | Broadcom   | NetXtreme BCM5720 Gigabit... | 2     | tg3        | F6F6B1BC99 |
| 14e4:165f | 14e4:2003 | Broadcom   | NetXtreme BCM5720 Gigabit... | 2     | tg3        | 56CB3FC570 |
| 14e4:168a | 1028:1f5d | Broadco... | NetXtreme II BCM57800 1/1... | 2     | bnx2x      | 6CD5E5C480 |
| 14e4:168a | 1028:1f68 | Broadco... | NetXtreme II BCM57800 1/1... | 2     | bnx2x      | 6CD5E5C480 |
| 14e4:168e | 103c:193a | Broadcom   | NetXtreme II BCM57810 10 ... | 2     | bnx2x      | B7B182E812 |
| 14e4:168e | 103c:3382 | Broadcom   | NetXtreme II BCM57810 10 ... | 2     | bnx2x      | A49E101BFB |
| 14e4:168e | 1458:e000 | Broadcom   | NetXtreme II BCM57810 10 ... | 2     | bnx2x      | 6D486A7EE9 |
| 14e4:168e | 14e4:1006 | Broadcom   | NetXtreme II BCM57810 10 ... | 2     | bnx2x      | 4CE6A061A6 |
| 14e4:16d8 | 1028:07e5 | Broadcom   | BCM57416 NetXtreme-E Dual... | 2     | bnxt_en    | 4C88B2E09B |
| 14e4:16d8 | 15d9:16d8 | Broadcom   | BCM57416 NetXtreme-E Dual... | 2     | bnxt_en    | 43E601437F |
| 19e5:1822 | 19e5:d136 | Huawei ... | Hi1822 Family (4*25GE)       | 2     | hinic      | 63BDABB5A4 |
| 19e5:a221 |           | Huawei ... | HNS GE/10GE/25GE Network ... | 2     | hclge, ... | 63BDABB5A4 |
| 19e5:a222 |           | Huawei ... | HNS GE/10GE/25GE RDMA Net... | 2     | hclge, ... | 63BDABB5A4 |
| 1d6a:07b1 | 15d9:07b1 | Aquantia   | AQC107 NBase-T/IEEE 802.3... | 2     | atlantic   | 43A2D3F891 |
| 8086:105e | 8086:135e | Intel      | 82571EB/82571GB Gigabit E... | 2     | e1000e     | EFEB179060 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2723 | 8086:0084 | Intel      | Wi-Fi 6 AX200                | 3     | iwlwifi    | 279B8964E5 |
| 14e4:43a0 | 14e4:0619 | Broadcom   | BCM4360 802.11ac Wireless... | 2     | wl         | CC8DB94EBA |
| 168c:003e | 168c:3360 | Qualcom... | QCA6174 802.11ac Wireless... | 2     | ath10k_pci | 598D43B1F2 |
| 8086:2526 | 8086:0014 | Intel      | Wireless-AC 9260             | 2     | iwlwifi    | 3F6EBB3247 |
| 10ec:8812 | 10ec:8203 | Realtek... | RTL8812AE 802.11ac PCIe W... | 1     | rtl8821ae  | 87E94A007B |
| 10ec:8812 | 10ec:8812 | Realtek... | RTL8812AE 802.11ac PCIe W... | 1     | rtl8821ae  | 5658A2FB98 |
| 14e4:43ba | 106b:0133 | Broadcom   | BCM43602 802.11ac Wireles... | 1     | brcmfmac   | FC1F78ADA0 |
| 168c:0013 | 1186:3a73 | Qualcom... | AR5212/5213/2414 Wireless... | 1     | ath5k      | 8F945E0A15 |
| 168c:0013 | 168c:2051 | Qualcom... | AR5212/5213/2414 Wireless... | 1     | ath5k      | FE3D758C20 |
| 168c:001d | 1113:b203 | Qualcom... | AR2417 Wireless Network A... | 1     | ath5k      | EF95821AFC |
| 168c:001d | 168c:2055 | Qualcom... | AR2417 Wireless Network A... | 1     | ath5k      | 16BEFD9DC3 |
| 168c:0030 | 168c:3112 | Qualcom... | AR93xx Wireless Network A... | 1     | ath9k      | B9AC0D657E |
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
| 8086:1521 | 15d9:1521 | Intel      | I350 Gigabit Network Conn... | 57    | igb        | 331227D869 |
| 8086:1533 | 15d9:1533 | Intel      | I210 Gigabit Network Conn... | 48    | igb        | CF083F4B62 |
| 8086:10d3 | 15d9:10d3 | Intel      | 82574L Gigabit Network Co... | 19    | e1000e     | CF37C43C55 |
| 8086:10d3 | 1043:8369 | Intel      | 82574L Gigabit Network Co... | 17    | e1000e     | A4C832AB44 |
| 8086:1533 | 1043:8557 | Intel      | I210 Gigabit Network Conn... | 16    | igb        | AE3BFE95C9 |
| 8086:10c9 | 15d9:10c9 | Intel      | 82576 Gigabit Network Con... | 15    | igb        | D9ED4F04A3 |
| 8086:1533 | ffff:0000 | Intel      | I210 Gigabit Network Conn... | 10    | igb        | 14C76E0C83 |
| 8086:1521 | 1028:1f60 | Intel      | I350 Gigabit Network Conn... | 8     | igb        | C436F9E67A |
| 1077:8020 | 103c:3733 | QLogic     | cLOM8214 1/10GbE Controller  | 7     | qlcnic     | C56840DF98 |
| 8086:10c9 | 103c:323f | Intel      | 82576 Gigabit Network Con... | 7     | igb        | 28B04C3004 |
| 8086:10c9 | 15d9:0100 | Intel      | 82576 Gigabit Network Con... | 7     | igb        | C83DC07B7C |
| 8086:10c9 | 15d9:ab11 | Intel      | 82576 Gigabit Network Con... | 7     | igb        | D5563E325C |
| 8086:10a7 | 8086:34dc | Intel      | 82575EB Gigabit Network C... | 6     | igb        | 61DFD26E01 |
| 8086:10bd | 8086:34d0 | Intel      | 82566DM-2 Gigabit Network... | 6     | e1000e     | F0473D3564 |
| 8086:10d3 | 15d9:0000 | Intel      | 82574L Gigabit Network Co... | 5     | e1000e     | 2E139151DE |
| 8086:10d3 | 8086:0000 | Intel      | 82574L Gigabit Network Co... | 5     | e1000e     | 32DF3AB75F |
| 8086:10fb | 15d9:0611 | Intel      | 82599ES 10-Gigabit SFI/SF... | 5     | ixgbe      | AFAB4598A7 |
| 8086:10a7 | 8086:34e2 | Intel      | 82575EB Gigabit Network C... | 4     | igb        | D577FE5BA4 |
| 8086:10c9 | 15d9:0600 | Intel      | 82576 Gigabit Network Con... | 4     | igb        | C17B3F71EC |
| 8086:10c9 | 15d9:060f | Intel      | 82576 Gigabit Network Con... | 4     | igb        | CF99AAD395 |
| 8086:10cc | 8086:34da | Intel      | 82567LM-2 Gigabit Network... | 4     | e1000e     | FE3D758C20 |
| 8086:10d3 | 1014:03bd | Intel      | 82574L Gigabit Network Co... | 4     | e1000e     | 882EA8E25E |
| 8086:10d3 | 8086:34da | Intel      | 82574L Gigabit Network Co... | 4     | e1000e     | FE3D758C20 |
| 8086:10d3 | 8086:3578 | Intel      | 82574L Gigabit Network Co... | 4     | e1000e     | 57162CA72C |
| 8086:1502 | 8086:3578 | Intel      | 82579LM Gigabit Network C... | 4     | e1000e     | 57162CA72C |
| 8086:1521 | 1458:0000 | Intel      | I350 Gigabit Network Conn... | 4     | igb        | D140FF934B |
| 8086:1521 | 15d9:0656 | Intel      | I350 Gigabit Network Conn... | 4     | igb        | 7AD1F5EB4E |
| 8086:1521 | 8086:357e | Intel      | I350 Gigabit Network Conn... | 4     | igb        | 0FADD1EBE3 |
| 14e4:164f | 14e4:1113 | Broadcom   | NetXtreme II BCM57711 10-... | 3     | bnx2x      | FDC516788A |
| 4040:0100 | 103c:705a | NetXen ... | NX3031 Multifunction 1/10... | 3     | netxen_nic | A2261C146D |
| 8086:10c9 | 15d9:0400 | Intel      | 82576 Gigabit Network Con... | 3     | igb        | B3C09674CF |
| 8086:10d3 | 1734:1158 | Intel      | 82574L Gigabit Network Co... | 3     | e1000e     | 4874F3ABB6 |
| 8086:10d3 | 1734:1192 | Intel      | 82574L Gigabit Network Co... | 3     | e1000e     | E6D89DC95B |
| 8086:10e8 | 8086:a02c | Intel      | 82576 Gigabit Network Con... | 3     | igb        | A4C832AB44 |
| 8086:1502 | 1734:11b7 | Intel      | 82579LM Gigabit Network C... | 3     | e1000e     | E6D89DC95B |
| 8086:1521 | 1028:1faa | Intel      | I350 Gigabit Network Conn... | 3     | igb        | 1CCB5D67C2 |
| 8086:1521 | 15d9:0652 | Intel      | I350 Gigabit Network Conn... | 3     | igb        | 16D1B33F25 |
| 8086:1521 | 15d9:0875 | Intel      | I350 Gigabit Network Conn... | 3     | igb        | 35739B35C9 |
| 8086:1521 | 8086:1521 | Intel      | I350 Gigabit Network Conn... | 3     | igb        | B6548538D4 |
| 8086:1533 | 1028:0619 | Intel      | I210 Gigabit Network Conn... | 3     | igb        | 33FDE2B5FB |
| 8086:1533 | 17aa:1038 | Intel      | I210 Gigabit Network Conn... | 3     | igb        | 5658A2FB98 |
| 10de:0373 | 1462:cb84 | Nvidia     | MCP55 Ethernet               | 2     | forcedeth  | B8300AFB35 |
| 15b3:1007 | 15b3:000c | Mellano... | MT27520 Family [ConnectX-... | 2     | mlx4_core  | 3CA7825025 |
| 15b3:1013 | 15b3:0014 | Mellano... | MT27700 Family [ConnectX-4]  | 2     | mlx5_core  | 2903921AEB |
| 15b3:673c | 15b3:0022 | Mellano... | MT25408A0-FCC-QI ConnectX... | 2     | mlx4_core  | 75223203BD |
| 15b3:6750 | 15b3:0015 | Mellano... | MT26448 [ConnectX EN 10Gi... | 2     | mlx4_core  | AFDF449993 |
| 8086:10a7 | 8086:34de | Intel      | 82575EB Gigabit Network C... | 2     | igb        | 3AB9D48A33 |
| 8086:10c9 | 10f1:7012 | Intel      | 82576 Gigabit Network Con... | 2     | igb        | 368A801F1A |
| 8086:10c9 | 1170:004a | Intel      | 82576 Gigabit Network Con... | 2     | igb        | 9D511D1A0B |
| 8086:10c9 | 8086:a04c | Intel      | 82576 Gigabit Network Con... | 2     | igb        | 614C766EEC |
| 8086:10d6 | 8086:145a | Intel      | 82575GB Gigabit Network C... | 2     | igb        | C83DC07B7C |
| 8086:1502 | 15d9:0623 | Intel      | 82579LM Gigabit Network C... | 2     | e1000e     | 2E139151DE |
| 8086:1521 | 0050:0019 | Intel      | I350 Gigabit Network Conn... | 2     | igb        | 58A63B2A93 |
| 8086:1521 | 8086:3594 | Intel      | I350 Gigabit Network Conn... | 2     | igb        | FBDCC4D1F5 |
| 8086:1521 | ffff:0000 | Intel      | I350 Gigabit Network Conn... | 2     | igb        | 5EB4DFC951 |
| 8086:1533 | 1458:0000 | Intel      | I210 Gigabit Network Conn... | 2     | igb        | 2F69A2F89C |
| 8086:1533 | 8086:35b4 | Intel      | I210 Gigabit Network Conn... | 2     | igb        | F3C8AC67B6 |
| 8086:1533 | 8086:35bd | Intel      | I210 Gigabit Network Conn... | 2     | igb        | 98C12554CB |
| 1077:7322 | 1077:7322 | QLogic     | IBA7322 QDR InfiniBand HCA   | 1     | ib_qib     | BA0F3C3B41 |
| 10b7:9200 | 10b7:1000 | 3Com       | 3c905C-TX/TX-M [Tornado]     | 1     | 3c59x      | 0B5D843F10 |
| 10de:0057 | 10f1:2891 | Nvidia     | CK804 Ethernet Controller    | 1     | forcedeth  | 64251B3F2A |
| 10de:0057 | 10f1:2895 | Nvidia     | CK804 Ethernet Controller    | 1     | forcedeth  | 768571B831 |
| 10de:0373 | 108e:534d | Nvidia     | MCP55 Ethernet               | 1     | forcedeth  | 1F35F79302 |
| 10de:0373 | 1462:2800 | Nvidia     | MCP55 Ethernet               | 1     | forcedeth  | 933EED177A |
| 10df:0720 | 10df:e863 | Emulex     | OneConnect NIC (Skyhawk)     | 1     | be2net     | 64918C950D |
| 1425:0031 | 1425:0001 | Chelsio... | T320 10GbE Dual Port Adapter | 1     | cxgb3      | C43FD89A0B |
| 14e4:164f | 1028:02d3 | Broadcom   | NetXtreme II BCM57711 10-... | 1     | bnx2x      | F33CE0F316 |
| 15b3:1003 | 15b3:0050 | Mellano... | MT27500 Family [ConnectX-3]  | 1     | mlx4_core  | 77A5A8BF12 |
| 15b3:1003 | 15b3:0123 | Mellano... | MT27500 Family [ConnectX-3]  | 1     | mlx4_core  | D15B8F8758 |
| 15b3:1015 | 15b3:0003 | Mellano... | MT27710 Family [ConnectX-... | 1     | mlx5_core  | 64918C950D |
| 15b3:1015 | 15d9:094c | Mellano... | MT27710 Family [ConnectX-... | 1     | mlx5_core  | 57460AA45B |
| 15b3:1017 | 15b3:0007 | Mellano... | MT27800 Family [ConnectX-5]  | 1     | mlx5_core  | F823B40D84 |
| 15b3:1017 | 15b3:0020 | Mellano... | MT27800 Family [ConnectX-5]  | 1     | mlx5_core  | 9CF9DCEEE9 |
| 15b3:673c | 15b3:0033 | Mellano... | MT25408A0-FCC-QI ConnectX... | 1     | mlx4_core  | 179B0500B3 |
| 15b3:673c | 15b3:673c | Mellano... | MT25408A0-FCC-QI ConnectX... | 1     | mlx4_core  | 0138C33179 |
| 15b3:6750 | 15b3:0021 | Mellano... | MT26448 [ConnectX EN 10Gi... | 1     | mlx4_core  | 98ED2C77C7 |
| 19a2:0710 | 103c:337b | Emulex     | OneConnect 10Gb NIC (be3)    | 1     | be2net     | C2075DC2CE |
| 19a2:0710 | 10df:e70a | Emulex     | OneConnect 10Gb NIC (be3)    | 1     | be2net     | D7CBC31CEE |
| 19a2:0710 | 10df:e731 | Emulex     | OneConnect 10Gb NIC (be3)    | 1     | be2net     | 7C109612B9 |
| 8086:0436 | 8086:0000 | Intel      | DH8900CC Null Device         | 1     |            | 14C76E0C83 |
| 8086:10a7 | 1734:1128 | Intel      | 82575EB Gigabit Network C... | 1     | igb        | 28D7F4FA53 |
| 8086:10bd | 8086:0000 | Intel      | 82566DM-2 Gigabit Network... | 1     | e1000e     | ECA989A5BF |
| 8086:10d3 | 10f1:7012 | Intel      | 82574L Gigabit Network Co... | 1     | e1000e     | 3D4DABE8D3 |
| 8086:10d3 | 8086:34ec | Intel      | 82574L Gigabit Network Co... | 1     | e1000e     | 6DE12619B5 |
| 8086:10d3 | 8086:a01f | Intel      | 82574L Gigabit Network Co... | 1     | e1000e     | 574D59E89A |
| 8086:10e8 | 8086:a02b | Intel      | 82576 Gigabit Network Con... | 1     | igb        | 3A05F2F446 |
| 8086:10ef | 8086:34ec | Intel      | 82578DM Gigabit Network C... | 1     | e1000e     | 6DE12619B5 |
| 8086:1521 |           | Intel      | I350 Gigabit Network Conn... | 1     | igb        | EDE05678EF |
| 8086:1521 | 1028:1f73 | Intel      | I350 Gigabit Network Conn... | 1     | igb        | 77A5A8BF12 |
| 8086:1521 | 1043:84ec | Intel      | I350 Gigabit Network Conn... | 1     | igb        | 996F55BB36 |
| 8086:1521 | 15d9:0912 | Intel      | I350 Gigabit Network Conn... | 1     | igb        | 1687263A9E |
| 8086:1521 | 1734:11ce | Intel      | I350 Gigabit Network Conn... | 1     | igb        | B0EE52BCF3 |
| 8086:1521 | 8086:3582 | Intel      | I350 Gigabit Network Conn... | 1     | igb        | 9F6D925B73 |
| 8086:1521 | 8086:358c | Intel      | I350 Gigabit Network Conn... | 1     | igb        | D15B8F8758 |
| 8086:1521 | 8086:35b0 | Intel      | I350 Gigabit Network Conn... | 1     | igb        | 30CFD7BC18 |
| 8086:1533 | 1458:e000 | Intel      | I210 Gigabit Network Conn... | 1     | igb        | 7E93E1B694 |
| 8086:1533 | 1734:11fc | Intel      | I210 Gigabit Network Conn... | 1     | igb        | 86AB491564 |
| 8086:1533 | 1849:1533 | Intel      | I210 Gigabit Network Conn... | 1     | igb        | 35C171899E |
| 8086:1533 | 8086:35be | Intel      | I210 Gigabit Network Conn... | 1     | igb        | C1AF65BF26 |
| d161:8002 | d161:8002 | Digium     | Wildcard AEX800 8-port an... | 1     |            | FE3D758C20 |

### Network and computing encryption device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 19e5:a255 |           | Huawei ... | HiSilicon SEC Engine         | 1     |            | 63BDABB5A4 |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1485 | 1022:1485 | AMD        | Starship/Matisse Reserved... | 6     |            | 2175466EA1 |
| 1022:148a | 1022:148a | AMD        | Starship/Matisse PCIe Dum... | 6     |            | 2175466EA1 |
| 1022:1485 | 1458:1000 | AMD        | Starship/Matisse Reserved... | 3     |            | D140FF934B |
| 1022:148a | 1458:1000 | AMD        | Starship/Matisse PCIe Dum... | 3     |            | D140FF934B |
| 1022:1455 | 1022:1455 | AMD        | Zeppelin/Renoir PCIe Dumm... | 2     |            | F6F6B1BC99 |
| 1022:1455 | 1458:1000 | AMD        | Zeppelin/Renoir PCIe Dumm... | 2     |            | 6D486A7EE9 |
| 1022:145a | 1022:145a | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | F6F6B1BC99 |
| 1022:145a | 1458:1000 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 6D486A7EE9 |
| 8086:a126 |           | Intel      | 100 Series/C230 Series Ch... | 2     | intel_t... | 7ACAB2007D |
| 1022:1455 | 1028:07f9 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 8F7FF50C55 |
| 1022:145a | 1028:07f9 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 8F7FF50C55 |
| 1022:1485 | 1028:08ff | AMD        | Starship/Matisse Reserved... | 1     |            | B7F3606E31 |
| 1022:148a | 1028:08ff | AMD        | Starship/Matisse PCIe Dum... | 1     |            | B7F3606E31 |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a135 | 15d9:089a | Intel      | 100 Series/C230 Series Ch... | 2     | intel_i... | 6B930AF6EC |
| 1415:9510 | 131f:0000 | Oxford ... | OX16PCI954 (Quad 16950 UA... | 1     |            | 80DC2F8936 |
| 1b94:c156 | 1b94:c156 | Signate... |                              | 1     |            | B3C09674CF |
| 8086:a135 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 1     |            | BB8832ACBD |

### Performance counters (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:204c | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 87    | skx_uncore | 2D1D9030E8 |
| 8086:204d | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 87    | skx_uncore | 2D1D9030E8 |
| 8086:2015 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 86    |            | 2D1D9030E8 |
| 8086:2058 | 8086:0000 | Intel      | Sky Lake-E KTI 0             | 83    | skx_uncore | 2D1D9030E8 |
| 8086:2088 | 8086:0000 | Intel      | Sky Lake-E DDRIO Registers   | 41    | skx_uncore | AFAB4598A7 |
| 8086:2f30 | 8086:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    | hswep_u... | F90168C69D |
| 8086:2f34 | 8086:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    | hswep_u... | F90168C69D |
| 8086:2f36 | 8086:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    | hswep_u... | F90168C69D |
| 8086:2f37 | 8086:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    | hswep_u... | F90168C69D |
| 8086:2f7d | 8086:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:3c43 | 103c:18a8 | Intel      | Xeon E5/Core i7 Ring to P... | 23    | snbep_u... | 799CC190DB |
| 8086:3c44 | 103c:18a8 | Intel      | Xeon E5/Core i7 Ring to Q... | 23    | snbep_u... | 799CC190DB |
| 8086:3c46 | 103c:18a8 | Intel      | Xeon E5/Core i7 Processor... | 23    | snbep_u... | 799CC190DB |
| 8086:3ce6 | 103c:18a8 | Intel      | Xeon E5/Core i7 QuickPath... | 23    |            | 799CC190DB |
| 8086:2f32 | 8086:2f32 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 20    | hswep_u... | F90168C69D |
| 8086:2f33 | 8086:2f33 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 19    | hswep_u... | F90168C69D |
| 8086:6f30 | 8086:6f30 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 19    | bdx_uncore | 2F38C3FD0E |
| 8086:6f34 | 8086:6f34 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 19    | bdx_uncore | 2F38C3FD0E |
| 8086:6f36 | 8086:6f36 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 19    | bdx_uncore | 2F38C3FD0E |
| 8086:6f37 | 8086:6f37 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 19    | bdx_uncore | 2F38C3FD0E |
| 8086:6f7d | 8086:6f7d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 19    |            | 2F38C3FD0E |
| 8086:6f30 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6f34 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6f36 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6f37 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6f7d | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6f32 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 15    | bdx_uncore | 17BF7A3CBC |
| 8086:6f33 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 15    | bdx_uncore | 17BF7A3CBC |
| 8086:0e30 | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 12    | ivbep_u... | DD93F62FFC |
| 8086:0e34 | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 12    | ivbep_u... | DD93F62FFC |
| 8086:0e36 | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 12    | ivbep_u... | DD93F62FFC |
| 8086:2f38 | 8086:2f38 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 12    | hswep_u... | F90168C69D |
| 8086:2058 |           | Intel      | Sky Lake-E KTI 0             | 11    | skx_uncore | 8D109AC7B4 |
| 8086:2015 | 17aa:7808 | Intel      | Sky Lake-E Ubox Registers    | 7     |            | CEE7ED2CE9 |
| 8086:204c | 17aa:7808 | Intel      | Sky Lake-E M3KTI Registers   | 7     | skx_uncore | CEE7ED2CE9 |
| 8086:204d | 17aa:7808 | Intel      | Sky Lake-E M3KTI Registers   | 7     | skx_uncore | CEE7ED2CE9 |
| 8086:2058 | 17aa:7808 | Intel      | Sky Lake-E KTI 0             | 7     | skx_uncore | CEE7ED2CE9 |
| 8086:2088 | 17aa:7808 | Intel      | Sky Lake-E DDRIO Registers   | 7     | skx_uncore | CEE7ED2CE9 |
| 8086:3c43 | 1043:84f0 | Intel      | Xeon E5/Core i7 Ring to P... | 7     | snbep_u... | 6ACBF140D4 |
| 8086:3c44 | 1043:84f0 | Intel      | Xeon E5/Core i7 Ring to Q... | 7     | snbep_u... | 6ACBF140D4 |
| 8086:3c46 | 1043:84f0 | Intel      | Xeon E5/Core i7 Processor... | 7     | snbep_u... | 6ACBF140D4 |
| 8086:3ce6 | 1043:84f0 | Intel      | Xeon E5/Core i7 QuickPath... | 7     |            | 6ACBF140D4 |
| 8086:6f32 | 8086:6f32 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 7     | bdx_uncore | 2F38C3FD0E |
| 8086:6f33 | 8086:6f33 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 7     | bdx_uncore | 2F38C3FD0E |
| 8086:0e30 | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 6     | ivbep_u... | 2FC41158D5 |
| 8086:0e30 | 1043:84f0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 6     | ivbep_u... | A4C832AB44 |
| 8086:0e34 | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 6     | ivbep_u... | 2FC41158D5 |
| 8086:0e34 | 1043:84f0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 6     | ivbep_u... | A4C832AB44 |
| 8086:0e36 | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 6     | ivbep_u... | 2FC41158D5 |
| 8086:0e36 | 1043:84f0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 6     | ivbep_u... | A4C832AB44 |
| 8086:3c43 | 1028:04fa | Intel      | Xeon E5/Core i7 Ring to P... | 6     | snbep_u... | 1A32B081A7 |
| 8086:3c44 | 1028:04fa | Intel      | Xeon E5/Core i7 Ring to Q... | 6     | snbep_u... | 1A32B081A7 |
| 8086:3c46 | 1028:04fa | Intel      | Xeon E5/Core i7 Processor... | 6     | snbep_u... | 1A32B081A7 |
| 8086:3ce6 | 1028:04fa | Intel      | Xeon E5/Core i7 QuickPath... | 6     |            | 1A32B081A7 |
| 8086:2015 | 1590:00ea | Intel      | Sky Lake-E Ubox Registers    | 5     |            | 3120E02C21 |
| 8086:204c | 1590:00ea | Intel      | Sky Lake-E M3KTI Registers   | 5     | skx_uncore | 3120E02C21 |
| 8086:204d | 1590:00ea | Intel      | Sky Lake-E M3KTI Registers   | 5     | skx_uncore | 3120E02C21 |
| 8086:2058 | 1590:00ea | Intel      | Sky Lake-E KTI 0             | 5     | skx_uncore | 3120E02C21 |
| 8086:2f30 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 5     | hswep_u... | 0B1954F5E9 |
| 8086:2f34 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 5     | hswep_u... | 0B1954F5E9 |
| 8086:2f36 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 5     | hswep_u... | 0B1954F5E9 |
| 8086:2f37 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 5     | hswep_u... | 0B1954F5E9 |
| 8086:2f7d | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 5     |            | 0B1954F5E9 |
| 8086:3c41 | 8086:0000 | Intel      | Sandy Bridge QPI Port 0 P... | 5     | snbep_u... | 58A63B2A93 |
| 8086:3c42 | 8086:0000 | Intel      | Sandy Bridge QPI Port 1 P... | 5     | snbep_u... | 58A63B2A93 |
| 8086:3c43 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to P... | 5     | snbep_u... | 58A63B2A93 |
| 8086:3c44 | 8086:0000 | Intel      | Xeon E5/Core i7 Ring to Q... | 5     | snbep_u... | 58A63B2A93 |
| 8086:3c46 |           | Intel      | Xeon E5/Core i7 Processor... | 5     | snbep_u... | 58A63B2A93 |
| 8086:3ce6 | 8086:0000 | Intel      | Xeon E5/Core i7 QuickPath... | 5     |            | 58A63B2A93 |
| 8086:0e30 | 8086:35a0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     | ivbep_u... | FE1E6CFF79 |
| 8086:0e34 | 8086:35a0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     | ivbep_u... | FE1E6CFF79 |
| 8086:0e36 | 8086:35a0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     | ivbep_u... | FE1E6CFF79 |
| 8086:0e37 | 8086:35a0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     | ivbep_u... | FE1E6CFF79 |
| 8086:2f30 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | FD108DE325 |
| 8086:2f34 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | FD108DE325 |
| 8086:2f36 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | FD108DE325 |
| 8086:2f37 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     | hswep_u... | FD108DE325 |
| 8086:2f7d | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | FD108DE325 |
| 8086:3c41 | 103c:18a8 | Intel      | Sandy Bridge QPI Port 0 P... | 4     | snbep_u... | 32951A000F |
| 8086:3c42 | 103c:18a8 | Intel      | Sandy Bridge QPI Port 1 P... | 4     | snbep_u... | 32951A000F |
| 8086:3c43 | 1028:048c | Intel      | Xeon E5/Core i7 Ring to P... | 4     | snbep_u... | 4CE6A061A6 |
| 8086:3c43 | 1028:04ce | Intel      | Xeon E5/Core i7 Ring to P... | 4     | snbep_u... | 9977E2B5C3 |
| 8086:3c44 | 1028:048c | Intel      | Xeon E5/Core i7 Ring to Q... | 4     | snbep_u... | 4CE6A061A6 |
| 8086:3c44 | 1028:04ce | Intel      | Xeon E5/Core i7 Ring to Q... | 4     | snbep_u... | 9977E2B5C3 |
| 8086:3c46 | 1028:048c | Intel      | Xeon E5/Core i7 Processor... | 4     | snbep_u... | 4CE6A061A6 |
| 8086:3c46 | 1028:04ce | Intel      | Xeon E5/Core i7 Processor... | 4     | snbep_u... | 9977E2B5C3 |
| 8086:3ce6 | 1028:048c | Intel      | Xeon E5/Core i7 QuickPath... | 4     |            | 4CE6A061A6 |
| 8086:3ce6 | 1028:04ce | Intel      | Xeon E5/Core i7 QuickPath... | 4     |            | 9977E2B5C3 |
| 8086:6f30 | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     | bdx_uncore | 23F12250E5 |
| 8086:6f34 | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     | bdx_uncore | 23F12250E5 |
| 8086:6f36 | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     | bdx_uncore | 23F12250E5 |
| 8086:6f37 | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     | bdx_uncore | 23F12250E5 |
| 8086:6f38 | 8086:6f38 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     | bdx_uncore | 2F38C3FD0E |
| 8086:6f7d | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     |            | 23F12250E5 |
| 8086:0e30 | 1028:04f8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     | ivbep_u... | EA68439F2E |
| 8086:0e34 | 1028:04f8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     | ivbep_u... | EA68439F2E |
| 8086:0e36 | 1028:04f8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     | ivbep_u... | EA68439F2E |
| 8086:2015 | 17aa:1038 | Intel      | Sky Lake-E Ubox Registers    | 3     |            | 5658A2FB98 |
| 8086:2015 | 1849:2015 | Intel      | Sky Lake-E Ubox Registers    | 3     |            | 35C171899E |
| 8086:2015 | 8086:35ce | Intel      | Sky Lake-E Ubox Registers    | 3     |            | D373AF93CD |

### Pic (8259) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:342e |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 107   | i7core_... | 4DEBADA4BF |
| 8086:3422 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 105   |            | 4DEBADA4BF |
| 8086:3423 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 105   |            | 4DEBADA4BF |
| 8086:3438 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 56    | i5500_temp | D9ED4F04A3 |
| 8086:3422 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 34    |            | 28B04C3004 |
| 8086:3423 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 34    |            | 28B04C3004 |
| 8086:342e | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 34    | i7core_... | 28B04C3004 |
| 8086:3425 |           | Intel      | 7500/5520/5500/X58 Physic... | 7     |            | 2856AAF09F |
| 8086:3426 |           | Intel      | 7500/5520/5500/X58 Routin... | 7     |            | 2856AAF09F |
| 8086:3427 |           | Intel      | 7500/5520/5500 Physical a... | 7     |            | 2856AAF09F |
| 8086:3428 |           | Intel      | 7500/5520/5500 Routing & ... | 7     |            | 2856AAF09F |
| 8086:3422 | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 6     |            | 61DFD26E01 |
| 8086:3423 | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 6     |            | 61DFD26E01 |
| 8086:3425 | 0086:00dc | Intel      | 7500/5520/5500/X58 Physic... | 6     |            | 61DFD26E01 |
| 8086:3426 | 0086:00dc | Intel      | 7500/5520/5500/X58 Routin... | 6     |            | 61DFD26E01 |
| 8086:3427 | 0086:00dc | Intel      | 7500/5520/5500 Physical a... | 6     |            | 61DFD26E01 |
| 8086:3428 | 0086:00dc | Intel      | 7500/5520/5500 Routing & ... | 6     |            | 61DFD26E01 |
| 8086:342e | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 6     | i7core_... | 61DFD26E01 |
| 8086:3438 | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 6     | i5500_temp | 61DFD26E01 |
| 8086:3422 | 0034:0027 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | 4874F3ABB6 |
| 8086:3422 | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | FE3D758C20 |
| 8086:3422 | 0086:00e2 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | D577FE5BA4 |
| 8086:3423 | 0034:0027 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | 4874F3ABB6 |
| 8086:3423 | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | FE3D758C20 |
| 8086:3423 | 0086:00e2 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | D577FE5BA4 |
| 8086:3425 | 0034:0027 | Intel      | 7500/5520/5500/X58 Physic... | 4     |            | 4874F3ABB6 |
| 8086:3425 | 0086:00da | Intel      | 7500/5520/5500/X58 Physic... | 4     |            | FE3D758C20 |
| 8086:3425 | 0086:00e2 | Intel      | 7500/5520/5500/X58 Physic... | 4     |            | D577FE5BA4 |
| 8086:3426 | 0034:0027 | Intel      | 7500/5520/5500/X58 Routin... | 4     |            | 4874F3ABB6 |
| 8086:3426 | 0086:00da | Intel      | 7500/5520/5500/X58 Routin... | 4     |            | FE3D758C20 |
| 8086:3426 | 0086:00e2 | Intel      | 7500/5520/5500/X58 Routin... | 4     |            | D577FE5BA4 |
| 8086:3427 | 0034:0027 | Intel      | 7500/5520/5500 Physical a... | 4     |            | 4874F3ABB6 |
| 8086:3427 | 0086:00da | Intel      | 7500/5520/5500 Physical a... | 4     |            | FE3D758C20 |
| 8086:3427 | 0086:00e2 | Intel      | 7500/5520/5500 Physical a... | 4     |            | D577FE5BA4 |
| 8086:3428 | 0034:0027 | Intel      | 7500/5520/5500 Routing & ... | 4     |            | 4874F3ABB6 |
| 8086:3428 | 0086:00da | Intel      | 7500/5520/5500 Routing & ... | 4     |            | FE3D758C20 |
| 8086:3428 | 0086:00e2 | Intel      | 7500/5520/5500 Routing & ... | 4     |            | D577FE5BA4 |
| 8086:342e | 0034:0027 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     | i7core_... | 4874F3ABB6 |
| 8086:342e | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     | i7core_... | FE3D758C20 |
| 8086:342e | 0086:00e2 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     | i7core_... | D577FE5BA4 |
| 8086:3438 | 0034:0027 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     | i5500_temp | 4874F3ABB6 |
| 8086:3438 | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     | i5500_temp | FE3D758C20 |
| 8086:3438 | 0086:00e2 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     | i5500_temp | D577FE5BA4 |
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
| 8086:2026 | 8086:2026 | Intel      | Sky Lake-E IOAPIC            | 83    |            | 2D1D9030E8 |
| 8086:2036 | 8086:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 83    |            | 2D1D9030E8 |
| 8086:342d |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 47    |            | D9ED4F04A3 |
| 8086:3c2c | 103c:18a8 | Intel      | Xeon E5/Core i7 I/O APIC     | 27    |            | 799CC190DB |
| 8086:2f2c | 8086:0000 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 24    |            | F90168C69D |
| 8086:6f2c | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:0e2c | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 12    |            | DD93F62FFC |
| 8086:6f2c | 8086:0000 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 9     |            | 2F38C3FD0E |
| 8086:2026 | 17aa:7808 | Intel      | Sky Lake-E IOAPIC            | 7     |            | CEE7ED2CE9 |
| 8086:2036 | 17aa:7808 | Intel      | Sky Lake-E IOxAPIC Config... | 7     |            | CEE7ED2CE9 |
| 8086:2f2c | 15d9:0857 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 7     |            | 7CF4F8ED17 |
| 8086:3c2c | 1043:84f0 | Intel      | Xeon E5/Core i7 I/O APIC     | 7     |            | 6ACBF140D4 |
| 8086:0e2c | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 6     |            | 2FC41158D5 |
| 8086:0e2c | 1043:84f0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 6     |            | A4C832AB44 |
| 8086:342d | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 6     |            | 61DFD26E01 |
| 8086:342f | 0086:00dc | Intel      | 7500/5520/5500/X58 Truste... | 6     |            | 61DFD26E01 |
| 8086:2026 | 1590:18a9 | Intel      | Sky Lake-E IOAPIC            | 5     |            | 3120E02C21 |
| 8086:2026 | 8086:0000 | Intel      | Sky Lake-E IOAPIC            | 5     |            | 9D6E46ECA9 |
| 8086:2036 | 1590:18a9 | Intel      | Sky Lake-E IOxAPIC Config... | 5     |            | 3120E02C21 |
| 8086:2036 | 8086:0000 | Intel      | Sky Lake-E IOxAPIC Config... | 5     |            | 9D6E46ECA9 |
| 8086:2f2c | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 5     |            | 0B1954F5E9 |
| 8086:342f |           | Intel      | 7500/5520/5500/X58 Truste... | 5     |            | 2856AAF09F |
| 8086:0e2c | 8086:35a0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 4     |            | FE1E6CFF79 |
| 8086:2f2c | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |            | FD108DE325 |
| 8086:342d | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | FE3D758C20 |
| 8086:342d | 0086:00e2 | Intel      | 7500/5520/5500/X58 I/O Hu... | 4     |            | D577FE5BA4 |
| 8086:342f | 0034:0027 | Intel      | 7500/5520/5500/X58 Truste... | 4     |            | 4874F3ABB6 |
| 8086:342f | 0086:00da | Intel      | 7500/5520/5500/X58 Truste... | 4     |            | FE3D758C20 |
| 8086:342f | 0086:00e2 | Intel      | 7500/5520/5500/X58 Truste... | 4     |            | D577FE5BA4 |
| 8086:6f2c | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 4     |            | 23F12250E5 |
| 8086:2026 | 17aa:1038 | Intel      | Sky Lake-E IOAPIC            | 3     |            | 5658A2FB98 |
| 8086:2026 | 1849:2026 | Intel      | Sky Lake-E IOAPIC            | 3     |            | 35C171899E |
| 8086:2026 | 8086:35ce | Intel      | Sky Lake-E IOAPIC            | 3     |            | D373AF93CD |
| 8086:2036 | 17aa:1038 | Intel      | Sky Lake-E IOxAPIC Config... | 3     |            | 5658A2FB98 |
| 8086:2036 | 1849:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 3     |            | 35C171899E |
| 8086:3c2c | 8086:357e | Intel      | Xeon E5/Core i7 I/O APIC     | 3     |            | 0FADD1EBE3 |
| 8086:0e2c | 15d9:0626 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | 00FDD71981 |
| 8086:0e2c | 15d9:062a | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | 2E139151DE |
| 8086:0e2c | 8086:0e2c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | F99E449D8B |
| 8086:2036 | 8086:35ce | Intel      | Sky Lake-E IOxAPIC Config... | 2     |            | D373AF93CD |
| 8086:342d | 0086:00de | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     |            | 3AB9D48A33 |
| 8086:342f | 0086:00de | Intel      | 7500/5520/5500/X58 Truste... | 2     |            | 3AB9D48A33 |
| 8086:3c2c | 8086:3594 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | FBDCC4D1F5 |
| 8086:6f2c | 1458:1000 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 0EA40336C5 |
| 8086:6f2c | 15d9:0824 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 6C96E4A591 |
| 8086:6f2c | 15d9:0834 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | FA4BECDE8B |
| 8086:6f2c | 1d49:0a00 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 3510DD7B10 |
| 8086:6f2c | 8086:6f2c | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 2903921AEB |
| 8086:0326 |           | Intel      | 6700/6702PXH I/OxAPIC Int... | 1     |            | 4FDE34B201 |
| 8086:0326 | 103c:3208 | Intel      | 6700/6702PXH I/OxAPIC Int... | 1     |            | 2C877CF870 |
| 8086:0326 | 8086:3439 | Intel      | 6700/6702PXH I/OxAPIC Int... | 1     |            | 0F21E859FA |
| 8086:0327 | 103c:3208 | Intel      | 6700PXH I/OxAPIC Interrup... | 1     |            | 2C877CF870 |
| 8086:0327 | 8086:3439 | Intel      | 6700PXH I/OxAPIC Interrup... | 1     |            | 0F21E859FA |
| 8086:0e2c | 15d9:062b | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 5C5668995E |
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
| 8086:2026 | 17aa:7800 | Intel      | Sky Lake-E IOAPIC            | 1     |            | 2AE35CF194 |
| 8086:2026 | 8086:35cd | Intel      | Sky Lake-E IOAPIC            | 1     |            | 9CF9DCEEE9 |
| 8086:2036 | 17aa:1037 | Intel      | Sky Lake-E IOxAPIC Config... | 1     |            | 41249F2E48 |
| 8086:2036 | 17aa:7800 | Intel      | Sky Lake-E IOxAPIC Config... | 1     |            | 2AE35CF194 |
| 8086:2036 | 8086:35cd | Intel      | Sky Lake-E IOxAPIC Config... | 1     |            | 9CF9DCEEE9 |
| 8086:25ac | 0e11:3201 | Intel      | 6300ESB I/O Advanced Prog... | 1     |            | BF8AB3D150 |
| 8086:2f2c | 1458:1000 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 2F69A2F89C |
| 8086:2f2c | 15d9:0834 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 3DA0A0E196 |
| 8086:2f2c | 15d9:0856 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 50EC24A7DE |
| 8086:2f2c | 15d9:0879 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 21124E85CC |
| 8086:2f2c | 15d9:0924 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 3FC4F3458F |
| 8086:2f2c | 19e5:2061 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 5EB4DFC951 |
| 8086:2f2c | 19e5:2062 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | BA0F3C3B41 |
| 8086:2f2c | 1d49:0a00 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 817865DED6 |
| 8086:2f2c | 8086:35c5 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 08100751B7 |
| 8086:2f2c | 8086:35c9 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 5F9F099F36 |
| 8086:342d | 0086:0000 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | CBBE408AAC |
| 8086:342f | 0086:0000 | Intel      | 7500/5520/5500/X58 Truste... | 1     |            | CBBE408AAC |
| 8086:3c2c | 15d9:0630 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | 575A60EDC8 |
| 8086:3c2c | 15d9:0660 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | AFE42B7E58 |
| 8086:3c2c | 15d9:066b | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | 1FF0EE8759 |
| 8086:3c2c | 15d9:0702 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | 376BED560D |
| 8086:3c2c | 1734:11b5 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | B0EE52BCF3 |
| 8086:3c2c | 1734:11b6 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | 9C16958A72 |
| 8086:3c2c | 8086:35b0 | Intel      | Xeon E5/Core i7 I/O APIC     | 1     |            | 30CFD7BC18 |
| 8086:6f2c | 15d9:0831 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | 64918C950D |
| 8086:6f2c | 15d9:0835 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | 7479576DA8 |
| 8086:6f2c | 8086:35c8 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | 574D59E89A |
| 8086:7813 | 8086:0000 | Intel      | Xeon Phi x200 product fam... | 1     |            | 5F6D0233A8 |
| 8086:7813 | 8086:35cb | Intel      | Xeon Phi x200 product fam... | 1     |            | CC33C2E194 |

### Pic (io-apic) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:7451 | 10f1:2895 | AMD        | AMD-8131 PCI-X IOAPIC        | 1     |            | 768571B831 |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:31cc | 1019:a94d | Intel      | Celeron/Pentium Silver Pr... | 2     | sdhci_pci  | 598D43B1F2 |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a1a4 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 18    |            | D373AF93CD |
| 8086:a1a4 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 14    |            | FD087082C0 |
| 8086:a1a4 | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     | intel_s... | CEE7ED2CE9 |
| 8086:a1a4 | 1043:871e | Intel      | C620 Series Chipset Famil... | 6     | intel_s... | AFAB4598A7 |
| 8086:a1a4 | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     |            | E9A1FC86F9 |
| 8086:a1a4 | 1028:0739 | Intel      | C620 Series Chipset Famil... | 4     |            | 2D1D9030E8 |
| 8086:a1a4 | 15d9:096d | Intel      | C620 Series Chipset Famil... | 4     |            | F9D0B2BC99 |
| 8086:a1a4 | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 4     | intel_s... | CD543E37E2 |
| 8086:a324 | 8086:7270 | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | B8FFB92409 |
| 10de:1ad7 | 1458:37c4 | Nvidia     | TU102 USB Type-C UCSI Con... | 3     | i2c_nvi... | F9D0B2BC99 |
| 8086:a1a4 | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | E752263E49 |
| 8086:a1a4 | 1028:073a | Intel      | C620 Series Chipset Famil... | 3     |            | 33FDE2B5FB |
| 8086:a1a4 | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 3     |            | ED3C250112 |
| 8086:a1a4 | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     |            | 7AD1F5EB4E |
| 8086:a1a4 | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     |            | C682299C13 |
| 8086:a1a4 | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     |            | 5658A2FB98 |
| 8086:a1a4 | 1849:a1a4 | Intel      | C620 Series Chipset Famil... | 3     |            | 35C171899E |
| 8086:a324 | 1028:088e | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | 2A87802C58 |
| 8086:a324 | 15d9:1a1b | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | 16D1B33F25 |
| 8086:a324 | 15d9:1a1d | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | E57FDAECA4 |
| 8086:a368 | 15d9:1a1b | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | 16D1B33F25 |
| 8086:a368 | 15d9:1a1d | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | E57FDAECA4 |
| 8086:a369 | 15d9:1a1b | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | 16D1B33F25 |
| 8086:a369 | 15d9:1a1d | Intel      | Cannon Lake PCH Serial IO... | 3     | intel_l... | E57FDAECA4 |
| 10de:1ad7 | 1028:12ba | Nvidia     | TU102 USB Type-C UCSI Con... | 2     | i2c_nvi... | 33FDE2B5FB |
| 8086:19e0 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 2     | intel_s... | 40E07B4DAD |
| 8086:a1a4 | 1028:0718 | Intel      | C620 Series Chipset Famil... | 2     |            | 1CCB5D67C2 |
| 8086:a1a4 | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     |            | DF9A63BE43 |
| 8086:a1a4 | 1028:07e5 | Intel      | C620 Series Chipset Famil... | 2     |            | 4C88B2E09B |
| 8086:a1a4 | 103c:81c6 | Intel      | C620 Series Chipset Famil... | 2     |            | 9D6E46ECA9 |
| 8086:a1a4 | 15d9:091c | Intel      | C620 Series Chipset Famil... | 2     |            | 748FB8054B |
| 8086:a1a4 | 15d9:0941 | Intel      | C620 Series Chipset Famil... | 2     |            | C619DB847B |
| 8086:a324 | 1028:0890 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 13E5EC2882 |
| 8086:a324 | 15d9:1a1f | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | A74597710B |
| 8086:a368 | 15d9:1a1f | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | A74597710B |
| 8086:a369 | 15d9:1a1f | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | A74597710B |
| 10de:1ad7 | 1043:8675 | Nvidia     | TU102 USB Type-C UCSI Con... | 1     |            | 8D9AEAB599 |
| 10de:1ad7 | 10de:12a3 | Nvidia     | TU102 USB Type-C UCSI Con... | 1     |            | AFAB4598A7 |
| 10de:1ad7 | 10de:12ba | Nvidia     | TU102 USB Type-C UCSI Con... | 1     | i2c_nvi... | 188BBE12AF |
| 10de:1ad7 | 1458:37ab | Nvidia     | TU102 USB Type-C UCSI Con... | 1     | i2c_nvi... | 72C72698D3 |
| 10de:1ad7 | 196e:134e | Nvidia     | TU102 USB Type-C UCSI Con... | 1     |            | BE9847546A |
| 10de:1ad7 | 19da:2503 | Nvidia     | TU102 USB Type-C UCSI Con... | 1     |            | 8E73F804F5 |
| 10de:1ad7 | 3842:2281 | Nvidia     | TU102 USB Type-C UCSI Con... | 1     | i2c_nvi... | 7E93E1B694 |
| 10de:1ad7 | 3842:2382 | Nvidia     | TU102 USB Type-C UCSI Con... | 1     | i2c_nvi... | B8FFB92409 |
| 10de:1ad9 | 1028:12a0 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     |            | 845D92DA91 |
| 10de:1ad9 | 1462:3720 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     |            | 3AC4E6EB75 |
| 10de:1ad9 | 196e:133f | Nvidia     | TU104 USB Type-C UCSI Con... | 1     | i2c_nvi... | 375EC8881D |
| 10de:1ad9 | 3842:2066 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     |            | EF434D4B56 |
| 10de:1adb | 19da:1516 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     |            | 78CDBBD363 |
| 10de:1adb | 19da:2516 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     |            | 9E25A27714 |
| 10de:1adb | 3842:3067 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     | i2c_nvi... | 2F69A2F89C |
| 10de:1aed | 3842:1357 | Nvidia     | TU116 USB Type-C UCSI Con... | 1     | i2c_nvi... | 3A14AEA222 |
| 8086:a1a4 | 1028:07cb | Intel      | C620 Series Chipset Famil... | 1     |            | 5B9EC879FC |
| 8086:a1a4 | 1458:5001 | Intel      | C620 Series Chipset Famil... | 1     |            | 7E93E1B694 |
| 8086:a1a4 | 15d9:0962 | Intel      | C620 Series Chipset Famil... | 1     |            | 57460AA45B |
| 8086:a1a4 | 15d9:096e | Intel      | C620 Series Chipset Famil... | 1     |            | 4D0ED95E02 |
| 8086:a1a4 | 15d9:0986 | Intel      | C620 Series Chipset Famil... | 1     |            | 331227D869 |
| 8086:a1a4 | 15d9:0987 | Intel      | C620 Series Chipset Famil... | 1     |            | 893E9D69F2 |
| 8086:a1a4 | 1734:1230 | Intel      | C620 Series Chipset Famil... | 1     |            | 86AB491564 |
| 8086:a1a4 | 17aa:1037 | Intel      | C620 Series Chipset Famil... | 1     |            | 41249F2E48 |
| 8086:a1a4 | 17aa:7800 | Intel      | C620 Series Chipset Famil... | 1     |            | 2AE35CF194 |
| 8086:a1a4 | 8086:35cd | Intel      | C620 Series Chipset Famil... | 1     |            | 9CF9DCEEE9 |
| 8086:a324 | 1028:0891 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 56CB3FC570 |
| 8086:a324 | 15d9:099e | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | F34EB9D9C6 |
| 8086:a324 | 15d9:1b09 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 59C50944A0 |
| 8086:a324 | 15d9:1b0e | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | CF083F4B62 |
| 8086:a324 | 15d9:1b0f | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | D9DA751F0F |
| 8086:a368 | 15d9:099e | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | F34EB9D9C6 |
| 8086:a368 | 15d9:1b09 | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | 59C50944A0 |
| 8086:a368 | 15d9:1b0e | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_lpss | CF083F4B62 |
| 8086:a368 | 15d9:1b0f | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | D9DA751F0F |
| 8086:a368 | 8086:7270 | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | 6FAAF237CE |
| 8086:a369 | 15d9:099e | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | F34EB9D9C6 |
| 8086:a369 | 15d9:1b09 | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | 59C50944A0 |
| 8086:a369 | 15d9:1b0e | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_lpss | CF083F4B62 |
| 8086:a369 | 15d9:1b0f | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | D9DA751F0F |
| 8086:a369 | 8086:7270 | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | 6FAAF237CE |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a363 | 8086:7270 | Intel      | Cannon Lake PCH Active Ma... | 4     | serial     | B8FFB92409 |
| 8086:8c3d | 15d9:0805 | Intel      | 8 Series/C220 Series Chip... | 3     | serial     | EF95821AFC |
| 8086:a1bd | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     | serial     | 5658A2FB98 |
| 8086:a13d | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 2     | serial     | 8F45F37B98 |
| 8086:a1bd | 1028:0739 | Intel      | C620 Series Chipset Famil... | 2     | serial     | 3514F18D29 |
| 8086:a1bd | 1028:073a | Intel      | C620 Series Chipset Famil... | 2     | serial     | 33FDE2B5FB |
| 1415:9501 | 131f:2050 | Oxford ... | OX16PCI954 (Quad 16950 UA... | 1     | serial     | 80DC2F8936 |
| 1415:c158 | 1415:c158 | Oxford ... | OXPCIe952 Dual Native 950... | 1     | serial     | 352FEE0E7F |
| 1415:c208 | 1415:c208 | Oxford ... | PCI Express Multiport Ser... | 1     | serial     | 375EC8881D |
| 8086:8c3d | 15d9:0654 | Intel      | 8 Series/C220 Series Chip... | 1     | serial     | AE67700E54 |
| 8086:8d3d | 1458:1000 | Intel      | C610/X99 series chipset K... | 1     | serial     | 2F69A2F89C |
| 8086:a13d | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | serial     | C392838A14 |
| 8086:a13d | 8086:1999 | Intel      | 100 Series/C230 Series Ch... | 1     | serial     | 95260B46FF |
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
| 8086:a1b1 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 19    |            | D373AF93CD |
| 8086:a1b1 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 14    |            | FD087082C0 |
| 8086:1d24 | 15d9:0636 | Intel      | C600/X79 series chipset T... | 12    |            | DD93F62FFC |
| 8086:8d24 | 15d9:0857 | Intel      | C610/X99 series chipset T... | 7     |            | 7CF4F8ED17 |
| 8086:a1b1 | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     |            | CEE7ED2CE9 |
| 8086:a131 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 6     | intel_p... | 98C12554CB |
| 8086:a1b1 | 1043:871e | Intel      | C620 Series Chipset Famil... | 6     | intel_p... | AFAB4598A7 |
| 8086:8c24 | 15d9:0801 | Intel      | 8 Series Chipset Family T... | 5     | intel_p... | 7F5062CA8F |
| 8086:a131 | 1028:06a5 | Intel      | 100 Series/C230 Series Ch... | 5     |            | E2A3815DD2 |
| 8086:a1b1 | 1590:00eb | Intel      | C620 Series Chipset Famil... | 5     |            | 3120E02C21 |
| 8086:8c24 | 15d9:0805 | Intel      | 8 Series Chipset Family T... | 4     | intel_p... | 16BEFD9DC3 |
| 8086:a1b1 | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     |            | E9A1FC86F9 |
| 8086:a1b1 | 1028:0739 | Intel      | C620 Series Chipset Famil... | 4     |            | 2D1D9030E8 |
| 8086:a1b1 | 15d9:096d | Intel      | C620 Series Chipset Famil... | 4     |            | F9D0B2BC99 |
| 8086:a1b1 | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 4     |            | CD543E37E2 |
| 8086:a379 | 8086:7270 | Intel      | Cannon Lake PCH Thermal C... | 4     | intel_p... | B8FFB92409 |
| 19e5:1710 | 19e5:0000 | Huawei ... | iBMA Virtual Network Adapter | 3     |            | 63BDABB5A4 |
| 8086:8c24 | 15d9:0921 | Intel      | 8 Series Chipset Family T... | 3     | intel_p... | 34DBD86F7B |
| 8086:8c24 | 8086:0000 | Intel      | 8 Series Chipset Family T... | 3     | intel_p... | 14C76E0C83 |
| 8086:8d24 | 1458:0000 | Intel      | C610/X99 series chipset T... | 3     |            | 2F69A2F89C |
| 8086:8d24 | 15d9:0831 | Intel      | C610/X99 series chipset T... | 3     |            | 2CE36E96F0 |
| 8086:8d24 | 1d49:0000 | Intel      | C610/X99 series chipset T... | 3     |            | 3510DD7B10 |
| 8086:a1b1 | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | E752263E49 |
| 8086:a1b1 | 1028:073a | Intel      | C620 Series Chipset Famil... | 3     |            | 33FDE2B5FB |
| 8086:a1b1 | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 3     |            | ED3C250112 |
| 8086:a1b1 | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     |            | 7AD1F5EB4E |
| 8086:a1b1 | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     |            | C682299C13 |
| 8086:a1b1 | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     |            | 5658A2FB98 |
| 8086:a1b1 | 1849:a1b1 | Intel      | C620 Series Chipset Famil... | 3     |            | 35C171899E |
| 8086:a379 | 1028:088e | Intel      | Cannon Lake PCH Thermal C... | 3     | intel_p... | 2A87802C58 |
| 8086:a379 | 15d9:1a1b | Intel      | Cannon Lake PCH Thermal C... | 3     | intel_p... | 16D1B33F25 |
| 8086:a379 | 15d9:1a1d | Intel      | Cannon Lake PCH Thermal C... | 3     | intel_p... | E57FDAECA4 |
| 8086:1d24 | 15d9:0626 | Intel      | C600/X79 series chipset T... | 2     |            | 00FDD71981 |
| 8086:1d24 | 15d9:062a | Intel      | C600/X79 series chipset T... | 2     |            | 2E139151DE |
| 8086:1d24 | 15d9:0660 | Intel      | C600/X79 series chipset T... | 2     |            | AFE42B7E58 |
| 8086:8c24 | 15d9:0803 | Intel      | 8 Series Chipset Family T... | 2     | intel_p... | 869444ACF6 |
| 8086:8c24 | 15d9:086d | Intel      | 8 Series Chipset Family T... | 2     | intel_p... | 9AF20F3BA9 |
| 8086:8c24 | 8086:35b5 | Intel      | 8 Series Chipset Family T... | 2     | intel_p... | F3C8AC67B6 |
| 8086:8d24 | 8086:8d24 | Intel      | C610/X99 series chipset T... | 2     |            | 2903921AEB |
| 8086:a131 | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_p... | 8F45F37B98 |
| 8086:a131 | 15d9:089a | Intel      | 100 Series/C230 Series Ch... | 2     | intel_p... | 6B930AF6EC |
| 8086:a160 | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_l... | 8F45F37B98 |
| 8086:a161 | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_l... | 8F45F37B98 |
| 8086:a1b1 | 1028:0718 | Intel      | C620 Series Chipset Famil... | 2     |            | 1CCB5D67C2 |
| 8086:a1b1 | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     |            | DF9A63BE43 |
| 8086:a1b1 | 1028:07e5 | Intel      | C620 Series Chipset Famil... | 2     |            | 4C88B2E09B |
| 8086:a1b1 | 103c:81c6 | Intel      | C620 Series Chipset Famil... | 2     |            | 9D6E46ECA9 |
| 8086:a1b1 | 15d9:091c | Intel      | C620 Series Chipset Famil... | 2     |            | 748FB8054B |
| 8086:a1b1 | 15d9:0941 | Intel      | C620 Series Chipset Famil... | 2     |            | C619DB847B |
| 8086:a379 | 1028:0890 | Intel      | Cannon Lake PCH Thermal C... | 2     | intel_p... | 13E5EC2882 |
| 8086:a379 | 15d9:1a1f | Intel      | Cannon Lake PCH Thermal C... | 2     | intel_p... | A74597710B |
| 1805:0812 | 1805:0004 | Euresys    | S.A Signal processing con... | 1     | coaxlink   | C619DB847B |
| 8086:1d24 | 15d9:062b | Intel      | C600/X79 series chipset T... | 1     |            | 5C5668995E |
| 8086:1d24 | 15d9:062f | Intel      | C600/X79 series chipset T... | 1     |            | F5F0A90676 |
| 8086:1d24 | 15d9:0630 | Intel      | C600/X79 series chipset T... | 1     |            | 575A60EDC8 |
| 8086:1d24 | 15d9:0665 | Intel      | C600/X79 series chipset T... | 1     |            | CEC82EF5D0 |
| 8086:1d24 | 15d9:066b | Intel      | C600/X79 series chipset T... | 1     |            | 1FF0EE8759 |
| 8086:1d24 | 15d9:0702 | Intel      | C600/X79 series chipset T... | 1     |            | 376BED560D |
| 8086:1d24 | 15d9:0703 | Intel      | C600/X79 series chipset T... | 1     |            | 8C793BB137 |
| 8086:1d24 | 15d9:0705 | Intel      | C600/X79 series chipset T... | 1     |            | B3D08DD227 |
| 8086:1d24 | 15d9:070a | Intel      | C600/X79 series chipset T... | 1     |            | B4C8ABC585 |
| 8086:1d24 | 15d9:0714 | Intel      | C600/X79 series chipset T... | 1     |            | F9D5463C17 |
| 8086:1d77 | 8086:0000 | Intel      | C600/X79 series chipset P... | 1     |            | FC0558920D |
| 8086:8c24 | 15d9:0653 | Intel      | 8 Series Chipset Family T... | 1     | intel_p... | 171EE8DB12 |
| 8086:8c24 | 15d9:0654 | Intel      | 8 Series Chipset Family T... | 1     | intel_p... | AE67700E54 |
| 8086:8c24 | 15d9:0802 | Intel      | 8 Series Chipset Family T... | 1     | intel_p... | 7115F8FDB7 |
| 8086:8c24 | 15d9:0842 | Intel      | 8 Series Chipset Family T... | 1     | intel_p... | 290C6ED969 |
| 8086:8d24 | 15d9:0000 | Intel      | C610/X99 series chipset T... | 1     |            | 5F6D0233A8 |
| 8086:8d24 | 15d9:0856 | Intel      | C610/X99 series chipset T... | 1     |            | 50EC24A7DE |
| 8086:8d24 | 19e5:2061 | Intel      | C610/X99 series chipset T... | 1     |            | 5EB4DFC951 |
| 8086:8d24 | 19e5:2062 | Intel      | C610/X99 series chipset T... | 1     |            | BA0F3C3B41 |
| 8086:8d24 | 8086:35cb | Intel      | C610/X99 series chipset T... | 1     |            | CC33C2E194 |
| 8086:a131 | 1028:06a6 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | 55471D97F1 |
| 8086:a131 | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | C74A66C7E6 |
| 8086:a131 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | BB8832ACBD |
| 8086:a131 | 15d9:0886 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 80DC2F8936 |
| 8086:a131 | 15d9:088b | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | 7202CCFD44 |
| 8086:a131 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | C392838A14 |
| 8086:a131 | 1734:1222 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | 0BD7D9FCEA |
| 8086:a131 | 8086:a131 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | C4D59010A1 |
| 8086:a160 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | intel_l... | C392838A14 |
| 8086:a161 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | intel_l... | C392838A14 |
| 8086:a1b1 | 1028:07cb | Intel      | C620 Series Chipset Famil... | 1     |            | 5B9EC879FC |
| 8086:a1b1 | 1458:5001 | Intel      | C620 Series Chipset Famil... | 1     |            | 7E93E1B694 |
| 8086:a1b1 | 15d9:0962 | Intel      | C620 Series Chipset Famil... | 1     |            | 57460AA45B |
| 8086:a1b1 | 15d9:096e | Intel      | C620 Series Chipset Famil... | 1     |            | 4D0ED95E02 |
| 8086:a1b1 | 15d9:0986 | Intel      | C620 Series Chipset Famil... | 1     |            | 331227D869 |
| 8086:a1b1 | 15d9:0987 | Intel      | C620 Series Chipset Famil... | 1     |            | 893E9D69F2 |
| 8086:a1b1 | 1734:1230 | Intel      | C620 Series Chipset Famil... | 1     |            | 86AB491564 |
| 8086:a1b1 | 17aa:1037 | Intel      | C620 Series Chipset Famil... | 1     | intel_p... | 41249F2E48 |
| 8086:a1b1 | 17aa:7800 | Intel      | C620 Series Chipset Famil... | 1     |            | 2AE35CF194 |
| 8086:a2b1 | 15d9:098e | Intel      | 200 Series PCH Thermal Su... | 1     |            | 98ED2C77C7 |
| 8086:a2b1 | 15d9:1b14 | Intel      | 200 Series PCH Thermal Su... | 1     |            | 43A2D3F891 |
| 8086:a2e0 | 15d9:098e | Intel      | 200 Series PCH Serial IO ... | 1     | intel_lpss | 98ED2C77C7 |
| 8086:a2e1 | 15d9:098e | Intel      | 200 Series PCH Serial IO ... | 1     | intel_lpss | 98ED2C77C7 |
| 8086:a379 | 1028:0891 | Intel      | Cannon Lake PCH Thermal C... | 1     |            | 56CB3FC570 |
| 8086:a379 | 15d9:099e | Intel      | Cannon Lake PCH Thermal C... | 1     | intel_p... | F34EB9D9C6 |
| 8086:a379 | 15d9:1b09 | Intel      | Cannon Lake PCH Thermal C... | 1     | intel_p... | 59C50944A0 |
| 8086:a379 | 15d9:1b0e | Intel      | Cannon Lake PCH Thermal C... | 1     | intel_p... | CF083F4B62 |
| 8086:a379 | 15d9:1b0f | Intel      | Cannon Lake PCH Thermal C... | 1     | intel_p... | D9DA751F0F |

### Signal processing management (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 19a2:0800 | 19a2:0800 | Emulex     | ServerView iRMC HTI          | 1     |            | 14C76E0C83 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a1a3 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 18    |            | D373AF93CD |
| 8086:8d22 | 15d9:0821 | Intel      | C610/X99 series chipset S... | 16    | i2c_i801   | 17BF7A3CBC |
| 8086:a1a3 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 14    | i2c_i801   | FD087082C0 |
| 8086:1d22 | 1043:84ef | Intel      | C600/X79 series chipset S... | 13    | i2c_i801   | A4C832AB44 |
| 8086:3a30 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) SM... | 13    | i2c_i801   | AFF808A68F |
| 8086:1d22 | 15d9:0636 | Intel      | C600/X79 series chipset S... | 12    | i2c_i801   | DD93F62FFC |
| 8086:8d22 | 103c:8030 | Intel      | C610/X99 series chipset S... | 9     | i2c_i801   | 23F12250E5 |
| 8086:8d22 | 8086:7270 | Intel      | C610/X99 series chipset S... | 9     | i2c_i801   | 2F38C3FD0E |
| 1022:790b | 1022:790b | AMD        | FCH SMBus Controller         | 7     | i2c_piix4  | 2175466EA1 |
| 8086:1d22 | 1014:1d22 | Intel      | C600/X79 series chipset S... | 7     | i2c_i801   | 58A63B2A93 |
| 8086:8d22 | 1043:85f6 | Intel      | C610/X99 series chipset S... | 7     | i2c_i801   | 4158CB76EF |
| 8086:8d22 | 15d9:0857 | Intel      | C610/X99 series chipset S... | 7     | i801_smbus | 7CF4F8ED17 |
| 8086:a1a3 | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     | i2c_i801   | CEE7ED2CE9 |
| 1002:4385 | 15d9:ab11 | AMD        | SBx00 SMBus Controller       | 6     | i2c_piix4  | D5563E325C |
| 1022:790b | 15d9:790b | AMD        | FCH SMBus Controller         | 6     | i2c_piix4  | 43E601437F |
| 8086:2930 | 8086:34d0 | Intel      | 82801I (ICH9 Family) SMBu... | 6     | i2c_i801   | FC38CA11F5 |
| 8086:3a30 | 1014:3a30 | Intel      | 82801JI (ICH10 Family) SM... | 6     | i2c_i801   | 2856AAF09F |
| 8086:3a30 | 15d9:0400 | Intel      | 82801JI (ICH10 Family) SM... | 6     | i2c_i801   | D9ED4F04A3 |
| 8086:3a30 | 8086:34dc | Intel      | 82801JI (ICH10 Family) SM... | 6     | i801_smbus | 61DFD26E01 |
| 8086:a123 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 6     | i2c_i801   | 98C12554CB |
| 8086:a1a3 | 1043:871e | Intel      | C620 Series Chipset Famil... | 6     | i2c_i801   | AFAB4598A7 |
| 1002:4385 | 15d9:bc11 | AMD        | SBx00 SMBus Controller       | 5     | i2c_piix4  | AD61EFB931 |
| 1022:790b | 1458:1000 | AMD        | FCH SMBus Controller         | 5     | i2c_piix4  | D140FF934B |
| 8086:1c22 | 1028:04de | Intel      | 6 Series/C200 Series Chip... | 5     | i2c_i801   | E24D0E827B |
| 8086:3a30 | 15d9:0001 | Intel      | 82801JI (ICH10 Family) SM... | 5     | i2c_i801   | 6BA00F03DE |
| 8086:3a30 | 15d9:0100 | Intel      | 82801JI (ICH10 Family) SM... | 5     | i2c_i801   | C83DC07B7C |
| 8086:3a30 | 15d9:0600 | Intel      | 82801JI (ICH10 Family) SM... | 5     | i2c_i801   | C17B3F71EC |
| 8086:8c22 | 15d9:0801 | Intel      | 8 Series/C220 Series Chip... | 5     | i2c_i801   | 7F5062CA8F |
| 8086:8d22 | 15d9:0831 | Intel      | C610/X99 series chipset S... | 5     | i2c_i801   | 64918C950D |
| 8086:a123 | 1028:06a5 | Intel      | 100 Series/C230 Series Ch... | 5     | i2c_i801   | E2A3815DD2 |
| 8086:1c22 | 1043:8497 | Intel      | 6 Series/C200 Series Chip... | 4     | i2c_i801   | 750A124EF3 |
| 8086:1c22 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 4     | i2c_i801   | 57162CA72C |
| 8086:1d22 | 8086:357e | Intel      | C600/X79 series chipset S... | 4     | i2c_i801   | 0FADD1EBE3 |
| 8086:1d22 | 8086:35a0 | Intel      | C600/X79 series chipset S... | 4     |            | FE1E6CFF79 |
| 8086:1d70 | 8086:35a0 | Intel      | C600/X79 series chipset S... | 4     |            | FE1E6CFF79 |
| 8086:269b | 8086:3476 | Intel      | 631xESB/632xESB/3100 Chip... | 4     | i2c_i801   | 38109F9919 |
| 8086:27da | 1028:01e7 | Intel      | NM10/ICH7 Family SMBus Co... | 4     | i2c_i801   | EA66809CE7 |
| 8086:3a30 | 15d9:060f | Intel      | 82801JI (ICH10 Family) SM... | 4     | i2c_i801   | CF99AAD395 |
| 8086:3a30 | 1734:114d | Intel      | 82801JI (ICH10 Family) SM... | 4     | i2c_i801   | 4874F3ABB6 |
| 8086:3a30 | 8086:34da | Intel      | 82801JI (ICH10 Family) SM... | 4     | i2c_i801   | FE3D758C20 |
| 8086:3a30 | 8086:34e2 | Intel      | 82801JI (ICH10 Family) SM... | 4     | i2c_i801   | D577FE5BA4 |
| 8086:3b30 | 1014:0377 | Intel      | 5 Series/3400 Series Chip... | 4     | i2c_i801   | 882EA8E25E |
| 8086:8c22 | 15d9:0805 | Intel      | 8 Series/C220 Series Chip... | 4     | i801_smbus | 16BEFD9DC3 |
| 8086:8c22 | 8086:8c22 | Intel      | 8 Series/C220 Series Chip... | 4     | i2c_i801   | AE3BFE95C9 |
| 8086:a1a3 | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     | i2c_i801   | E9A1FC86F9 |
| 8086:a1a3 | 1028:0739 | Intel      | C620 Series Chipset Famil... | 4     | i2c_i801   | 2D1D9030E8 |
| 8086:a1a3 | 15d9:096d | Intel      | C620 Series Chipset Famil... | 4     | i2c_i801   | F9D0B2BC99 |
| 8086:a1a3 | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 4     | i2c_i801   | CD543E37E2 |
| 8086:a323 | 8086:7270 | Intel      | Cannon Lake PCH SMBus Con... | 4     |            | B8FFB92409 |
| 1002:4385 | 1028:0444 | AMD        | SBx00 SMBus Controller       | 3     | i2c_piix4  | B913A90C28 |
| 1002:4385 | 103c:1772 | AMD        | SBx00 SMBus Controller       | 3     | piix4_s... | DC4AC74B49 |
| 1002:4385 | 103c:3337 | AMD        | SBx00 SMBus Controller       | 3     | i2c_piix4  | 91AD975174 |
| 8086:1c22 | 1028:04dd | Intel      | 6 Series/C200 Series Chip... | 3     | i2c_i801   | D4CCC85620 |
| 8086:1c22 | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 3     | i2c_i801   | E6D89DC95B |
| 8086:269b | 8086:3486 | Intel      | 631xESB/632xESB/3100 Chip... | 3     | i2c_i801   | 0A3F6D305B |
| 8086:3a30 | 8086:3a30 | Intel      | 82801JI (ICH10 Family) SM... | 3     | i2c_i801   | 32DF3AB75F |
| 8086:8c22 | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 3     | i801_smbus | 34DBD86F7B |
| 8086:8d22 | 1458:1000 | Intel      | C610/X99 series chipset S... | 3     | i2c_i801   | 2F69A2F89C |
| 8086:8d22 | 15d9:0834 | Intel      | C610/X99 series chipset S... | 3     | i2c_i801   | FA4BECDE8B |
| 8086:8d22 | 1d49:0a00 | Intel      | C610/X99 series chipset S... | 3     | i2c_i801   | 3510DD7B10 |
| 8086:a1a3 | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     | i2c_i801   | E752263E49 |
| 8086:a1a3 | 1028:073a | Intel      | C620 Series Chipset Famil... | 3     | i2c_i801   | 33FDE2B5FB |
| 8086:a1a3 | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 3     | i801_smbus | ED3C250112 |
| 8086:a1a3 | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     | i2c_i801   | 7AD1F5EB4E |
| 8086:a1a3 | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     |            | C682299C13 |
| 8086:a1a3 | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     | i2c_i801   | 5658A2FB98 |
| 8086:a1a3 | 1849:a1a3 | Intel      | C620 Series Chipset Famil... | 3     | i2c_i801   | 35C171899E |
| 8086:a323 | 1028:088e | Intel      | Cannon Lake PCH SMBus Con... | 3     | i2c_i801   | 2A87802C58 |
| 8086:a323 | 15d9:1a1b | Intel      | Cannon Lake PCH SMBus Con... | 3     | i2c_i801   | 16D1B33F25 |
| 8086:a323 | 15d9:1a1d | Intel      | Cannon Lake PCH SMBus Con... | 3     | i2c_i801   | E57FDAECA4 |
| 1002:4385 | 15d9:a811 | AMD        | SBx00 SMBus Controller       | 2     | i2c_piix4  | 340A3648A2 |
| 1002:4385 | 15d9:ba11 | AMD        | SBx00 SMBus Controller       | 2     | i2c_pii... | 6381FD461D |
| 1002:4385 | 15d9:ca11 | AMD        | SBx00 SMBus Controller       | 2     | i2c_piix4  | 9712585D1C |
| 1002:4385 | 15d9:cd11 | AMD        | SBx00 SMBus Controller       | 2     | i2c_piix4  | CF37C43C55 |
| 10de:0368 | 1462:cb84 | Nvidia     | MCP55 SMBus Controller       | 2     | i2c_nfo... | B8300AFB35 |
| 8086:19df | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 2     | i2c_i801   | 40E07B4DAD |
| 8086:1d22 | 15d9:0626 | Intel      | C600/X79 series chipset S... | 2     | i2c_i801   | 00FDD71981 |
| 8086:1d22 | 15d9:062a | Intel      | C600/X79 series chipset S... | 2     | i2c_i801   | 2E139151DE |
| 8086:1d22 | 15d9:0660 | Intel      | C600/X79 series chipset S... | 2     | i2c_i801   | AFE42B7E58 |
| 8086:1d22 | 8086:3594 | Intel      | C600/X79 series chipset S... | 2     | i2c_i801   | FBDCC4D1F5 |
| 8086:1d70 | 8086:3594 | Intel      | C600/X79 series chipset S... | 2     | i2c_i801   | FBDCC4D1F5 |
| 8086:269b | 1014:02dd | Intel      | 631xESB/632xESB/3100 Chip... | 2     | i2c_i801   | 3A68279F78 |
| 8086:269b | 8086:346c | Intel      | 631xESB/632xESB/3100 Chip... | 2     | i2c_i801   | 390F15B7F9 |
| 8086:31d4 | 1019:a94d | Intel      | Celeron/Pentium Silver Pr... | 2     | i2c_i801   | 598D43B1F2 |
| 8086:3a30 | 1033:8372 | Intel      | 82801JI (ICH10 Family) SM... | 2     | i2c_i801   | 460A274240 |
| 8086:3a30 | 1170:0047 | Intel      | 82801JI (ICH10 Family) SM... | 2     | i2c_i801   | 9D511D1A0B |
| 8086:3a30 | 15d9:0007 | Intel      | 82801JI (ICH10 Family) SM... | 2     | i2c_i801   | A652ED3DB4 |
| 8086:3a30 | 8086:34de | Intel      | 82801JI (ICH10 Family) SM... | 2     | i2c_i801   | 3AB9D48A33 |
| 8086:8c22 | 1028:05e5 | Intel      | 8 Series/C220 Series Chip... | 2     | i2c_i801   | EB7B7FD10B |
| 8086:8c22 | 15d9:0803 | Intel      | 8 Series/C220 Series Chip... | 2     | i2c_i801   | 869444ACF6 |
| 8086:8c22 | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 2     | i2c_i801   | 9AF20F3BA9 |
| 8086:8c22 | 8086:35b5 | Intel      | 8 Series/C220 Series Chip... | 2     | i2c_i801   | F3C8AC67B6 |
| 8086:8c22 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 2     | i2c_i801   | 14C76E0C83 |
| 8086:8d22 | 15d9:0824 | Intel      | C610/X99 series chipset S... | 2     | i2c_i801   | 6C96E4A591 |
| 8086:8d22 | 8086:8d22 | Intel      | C610/X99 series chipset S... | 2     | i2c_i801   | 2903921AEB |
| 8086:a123 | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 2     | i2c_i801   | 8F45F37B98 |
| 8086:a123 | 15d9:089a | Intel      | 100 Series/C230 Series Ch... | 2     | i2c_i801   | 6B930AF6EC |
| 8086:a123 | 8086:a123 | Intel      | 100 Series/C230 Series Ch... | 2     | i2c_i801   | C4D59010A1 |
| 8086:a1a3 | 1028:0718 | Intel      | C620 Series Chipset Famil... | 2     | i2c_i801   | 1CCB5D67C2 |
| 8086:a1a3 | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     | i2c_i801   | DF9A63BE43 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3a3e | 15d9:0006 | Intel      | 82801JI (ICH10 Family) HD... | 10    | snd_hda... | 8F945E0A15 |
| 1102:0012 | 1102:0010 | Creativ... | Sound Core3D [Sound Blast... | 8     | snd_hda... | D2AA9ED999 |
| 8086:1d20 | 1043:84d8 | Intel      | C600/X79 series chipset H... | 7     | snd_hda... | C3665EBF57 |
| 8086:8d20 | 15d9:0857 | Intel      | C610/X99 series chipset H... | 7     | snd_hda... | 7CF4F8ED17 |
| 10de:0e0f | 1462:8c93 | Nvidia     | GK208 HDMI/DP Audio Contr... | 6     | snd_hda... | 16BEFD9DC3 |
| 10de:0e0f | 196e:118b | Nvidia     | GK208 HDMI/DP Audio Contr... | 6     | snd_hda... | 3A68279F78 |
| 8086:3a3e | 15d9:0100 | Intel      | 82801JI (ICH10 Family) HD... | 5     | snd_hda... | C83DC07B7C |
| 1002:aab0 | 174b:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 4     | snd_hda... | CD543E37E2 |
| 1002:aaf8 | 1002:aaf8 | AMD        | Vega 10 HDMI Audio [Radeo... | 4     | snd_hda... | 755B723BB0 |
| 10de:0e0a | 10de:1096 | Nvidia     | GK104 HDMI Audio Controller  | 4     | snd_hda... | F508BB4C99 |
| 8086:3a3e | 8086:34e2 | Intel      | 82801JI (ICH10 Family) HD... | 4     | snd_hda... | D577FE5BA4 |
| 8086:8c20 | 15d9:0805 | Intel      | 8 Series/C220 Series Chip... | 4     | snd_hda... | 16BEFD9DC3 |
| 8086:a1f0 | 1028:0739 | Intel      | Lewisburg MROM 0             | 4     | snd_hda... | 2D1D9030E8 |
| 8086:a1f0 | 15d9:096d | Intel      | Lewisburg MROM 0             | 4     | snd_hda... | F9D0B2BC99 |
| 8086:a348 | 8086:7270 | Intel      | Cannon Lake PCH cAVS         | 4     | snd_hda... | B8FFB92409 |
| 1002:9840 | 1002:9840 | AMD        | Kabini HDMI/DP Audio         | 3     | snd_hda... | 5D00EDD035 |
| 1002:aa68 | 1043:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 3     | snd_hda... | B8300AFB35 |
| 1002:aa98 | 1028:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 3     | snd_hda... | 61DFD26E01 |
| 10de:0e0f | 1043:84f5 | Nvidia     | GK208 HDMI/DP Audio Contr... | 3     | snd_hda... | 5D93D067D7 |
| 10de:10f0 | 103c:11a3 | Nvidia     | GP104 High Definition Aud... | 3     | snd_hda... | 9D6E46ECA9 |
| 10de:10f7 | 1458:37c4 | Nvidia     | TU102 High Definition Aud... | 3     | snd_hda... | F9D0B2BC99 |
| 1102:0007 | 1102:100a | Creativ... | CA0106/CA0111 [SB Live!/A... | 3     | snd_ca0106 | 11BB1EE3A2 |
| 13f6:0111 | 13f6:0111 | C-Media... | CMI8738/CMI8768 PCI Audio    | 3     | snd_cmipci | 72DFF1BD7F |
| 8086:0c0c | 15d9:0805 | Intel      | Xeon E3-1200 v3/4th Gen C... | 3     | snd_hda... | EF95821AFC |
| 8086:1d20 | 1043:851b | Intel      | C600/X79 series chipset H... | 3     | snd_hda... | 5600070A23 |
| 8086:a1f0 | 1028:073a | Intel      | Lewisburg MROM 0             | 3     | snd_hda... | 33FDE2B5FB |
| 8086:a1f0 | 103c:81c7 | Intel      | Lewisburg MROM 0             | 3     | snd_hda... | ED3C250112 |
| 8086:a1f0 | 17aa:1038 | Intel      | Lewisburg MROM 0             | 3     | snd_hda... | 5658A2FB98 |
| 8086:a348 | 15d9:1a1d | Intel      | Cannon Lake PCH cAVS         | 3     | snd_hda... | E57FDAECA4 |
| 1002:aa68 | 1462:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 2     | snd_hda... | E014B80891 |
| 1002:aa98 | 1462:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 2     | snd_hda... | 1BF8F58CAF |
| 1002:aaa0 | 174b:aaa0 | AMD        | Tahiti HDMI Audio [Radeon... | 2     | snd_hda... | BEA324B5DA |
| 1002:aac0 | 1682:aac0 | AMD        | Tobago HDMI Audio [Radeon... | 2     | snd_hda... | 8BD3D92585 |
| 1002:aaf0 | 1043:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 2     | snd_hda... | C79A74A94E |
| 1002:aaf0 | 1682:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 2     | snd_hda... | 98C12554CB |
| 1002:aaf0 | 1da2:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 2     | snd_hda... | D09F385D74 |
| 1002:ab20 | 1002:ab20 | AMD        | Vega 20 HDMI Audio [Radeo... | 2     | snd_hda... | 0343B901D9 |
| 10de:0371 | 10de:cb84 | Nvidia     | MCP55 High Definition Audio  | 2     | snd_hda... | B8300AFB35 |
| 10de:0be3 | 10de:0862 | Nvidia     | High Definition Audio Con... | 2     | snd_hda... | 87E94A007B |
| 10de:0be5 | 10de:0771 | Nvidia     | GF100 High Definition Aud... | 2     | snd_hda... | 8E9E87A717 |
| 10de:0be9 | 10de:0914 | Nvidia     | GF106 High Definition Aud... | 2     | snd_hda... | 30DE024858 |
| 10de:0e0f | 1043:86cb | Nvidia     | GK208 HDMI/DP Audio Contr... | 2     | snd_hda... | 57162CA72C |
| 10de:0e0f | 1462:8a9f | Nvidia     | GK208 HDMI/DP Audio Contr... | 2     | snd_hda... | AE3BFE95C9 |
| 10de:0e0f | 19da:5360 | Nvidia     | GK208 HDMI/DP Audio Contr... | 2     | snd_hda... | AFF808A68F |
| 10de:0fb8 | 1458:3767 | Nvidia     | GP108 High Definition Aud... | 2     | snd_hda... | C889E2066F |
| 10de:0fbb | 1043:8508 | Nvidia     | GM204 High Definition Aud... | 2     | snd_hda... | AC7F5D0860 |
| 10de:0fbb | 10de:1153 | Nvidia     | GM204 High Definition Aud... | 2     | snd_hda... | ED3C250112 |
| 10de:0fbc | 3842:3753 | Nvidia     | GM107 High Definition Aud... | 2     | snd_hda... | AD61EFB931 |
| 10de:10ef | 1458:374c | Nvidia     | GP102 HDMI Audio Controller  | 2     | snd_hda... | 279B8964E5 |
| 10de:10f0 | 1028:11a3 | Nvidia     | GP104 High Definition Aud... | 2     | snd_hda... | 52B7CECCFF |
| 10de:10f0 | 10de:11a3 | Nvidia     | GP104 High Definition Aud... | 2     | snd_hda... | 5658A2FB98 |
| 10de:10f0 | 10de:11b2 | Nvidia     | GP104 High Definition Aud... | 2     | snd_hda... | 4D0ED95E02 |
| 10de:10f7 | 1028:12ba | Nvidia     | TU102 High Definition Aud... | 2     | snd_hda... | 33FDE2B5FB |
| 13f6:8788 | 1043:8521 | C-Media... | CMI8788 [Oxygen HD Audio]    | 2     | snd_oxygen | 0FADD1EBE3 |
| 8086:1d20 | 15d9:062a | Intel      | C600/X79 series chipset H... | 2     | snd_hda... | 2E139151DE |
| 8086:1d20 | 8086:3594 | Intel      | C600/X79 series chipset H... | 2     | snd_hda... | FBDCC4D1F5 |
| 8086:3198 | 1019:a94d | Intel      | Celeron/Pentium Silver Pr... | 2     | snd_hda... | 598D43B1F2 |
| 8086:8d20 | 1043:855f | Intel      | C610/X99 series chipset H... | 2     | snd_hda... | ED442D7C21 |
| 8086:a170 | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 2     | snd_hda... | 8F45F37B98 |
| 8086:a1f0 | 103c:81c6 | Intel      | Lewisburg MROM 0             | 2     | snd_hda... | 9D6E46ECA9 |
| 8086:a1f0 | 1043:8724 | Intel      | Lewisburg MROM 0             | 2     | snd_hda... | 755B723BB0 |
| 1002:4383 | 1734:119c | AMD        | SBx00 Azalia (Intel HDA)     | 1     | snd_hda... | 4D5DEAC32F |
| 1002:aa08 | 0000:aa08 | AMD        | RV630 HDMI Audio [Radeon ... | 1     | snd_hda... | 2E139151DE |
| 1002:aa08 | 174b:aa08 | AMD        | RV630 HDMI Audio [Radeon ... | 1     | snd_hda... | 869444ACF6 |
| 1002:aa28 | 1787:aa28 | AMD        | RV620 HDMI Audio [Radeon ... | 1     | snd_hda... | 92A1C2425F |
| 1002:aa30 | 1787:aa30 | AMD        | RV770 HDMI Audio [Radeon ... | 1     | snd_hda... | C02E4721B7 |
| 1002:aa38 | 0000:aa38 | AMD        | RV710/730 HDMI Audio [Rad... | 1     | snd_hda... | 4D5DEAC32F |
| 1002:aa38 | 1043:aa38 | AMD        | RV710/730 HDMI Audio [Rad... | 1     | snd_hda... | 8F45F37B98 |
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
| 1002:aa98 | 1b0a:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 1     | snd_hda... | 7DC7C9B0AF |
| 1002:aaa0 | 1002:aaa0 | AMD        | Tahiti HDMI Audio [Radeon... | 1     | snd_hda... | CEC82EF5D0 |
| 1002:aab0 | 1028:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 1     | snd_hda... | 1A32B081A7 |
| 1002:aab0 | 103c:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 1     | snd_hda... | 269E17071C |
| 1002:aab0 | 1043:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 1     | snd_hda... | 3F6EE4141E |
| 1002:aab0 | 1458:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 1     | snd_hda... | 0778329460 |
| 1002:aab0 | 148c:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 1     | snd_hda... | 726EA75DCA |
| 1002:aab0 | 1545:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 1     | snd_hda... | 5722EADDD3 |
| 1002:aab0 | 1787:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 1     | snd_hda... | 0C9DFEB831 |
| 1002:aac8 | 174b:aac8 | AMD        | Hawaii HDMI Audio [Radeon... | 1     | snd_hda... | C83DC07B7C |
| 1002:aae0 | 1002:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 1     | snd_hda... | 76299BB9FF |
| 1002:aae0 | 1019:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 1     | snd_hda... | 4874F3ABB6 |
| 1002:aae0 | 1028:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 1     | snd_hda... | 7540D08F3B |
| 1002:aae0 | 148c:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 1     | snd_hda... | 03F09902C6 |
| 1002:aae0 | 1682:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 1     | snd_hda... | 3223E40095 |
| 1002:aae0 | 1b0a:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 1     | snd_hda... | 1A05144C7E |
| 1002:aae0 | 1da2:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 1     | snd_hda... | FA25CA8BF5 |
| 1002:aae8 | 1002:aae8 | AMD        | Fiji HDMI/DP Audio [Radeo... | 1     | snd_hda... | 98ED2C77C7 |
| 1002:aaf0 | 1002:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 1     | snd_hda... | 676C3ECA96 |
| 1002:aaf0 | 1028:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 1     | snd_hda... | 3514F18D29 |
| 1002:aaf0 | 148c:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 1     | snd_hda... | 2FF14127D7 |

### Storage (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1077:2532 | 1077:015d | QLogic     | ISP2532-based 8Gb Fibre C... | 4     | qla2xxx    | F2602534BE |
| 11f8:8032 | 117c:003b | PMC-Sierra | PM8032 Tachyon QE8           | 3     | celerit... | FB8C0A4C3A |
| 1077:2532 | 1077:015e | QLogic     | ISP2532-based 8Gb Fibre C... | 2     | qla2xxx    | C43FD89A0B |
| 1000:0646 | 1000:1020 | Broadco... | FC949ES Fibre Channel Ada... | 1     | mptfc      | 8F6E544820 |
| 1077:2031 | 103c:1939 | QLogic     | ISP8324-based 16Gb Fibre ... | 1     | qla2xxx    | 9036136416 |
| 1077:2031 | 1077:0249 | QLogic     | ISP8324-based 16Gb Fibre ... | 1     | qla2xxx    | 77A5A8BF12 |
| 1077:2031 | 1077:0257 | QLogic     | ISP8324-based 16Gb Fibre ... | 1     | qla2xxx    | CBFB7C31D8 |
| 1077:2261 | 1077:02af | QLogic     | ISP2722-based 16/32Gb Fib... | 1     | qla2xxx    | 2AE35CF194 |
| 1077:2312 | 1077:0100 | QLogic     | ISP2312-based 2Gb Fibre C... | 1     | qla2xxx    | 40F9D31598 |
| 1077:2432 | 103c:1705 | QLogic     | ISP2432-based 4Gb Fibre C... | 1     | qla2xxx    | DC4AC74B49 |
| 1077:2432 | 103c:7040 | QLogic     | ISP2432-based 4Gb Fibre C... | 1     | qla2xxx    | B4EF3B8086 |
| 1077:2432 | 103c:7041 | QLogic     | ISP2432-based 4Gb Fibre C... | 1     | qla2xxx    | C9D389B2A3 |
| 1077:2432 | 1077:0137 | QLogic     | ISP2432-based 4Gb Fibre C... | 1     | qla2xxx    | 5C4A86988B |
| 1077:2532 | 1077:015c | QLogic     | ISP2532-based 8Gb Fibre C... | 1     | qla2xxx    | 1F6AFDC077 |
| 1077:2532 | 1077:0171 | QLogic     | ISP2532-based 8Gb Fibre C... | 1     | qla2xxx    | 4F5756D065 |
| 1077:2532 | 1077:0176 | QLogic     | ISP2532-based 8Gb Fibre C... | 1     | qla2xxx    | D7CBC31CEE |
| 10df:f0e5 | 10df:f0e5 | Emulex     | Zephyr LightPulse Fibre C... | 1     | lpfc       | C4DF6F1F79 |
| 10df:f100 | 103c:3282 | Emulex     | LPe12000 Series 8Gb Fibre... | 1     | lpfc       | 23F12250E5 |
| 10df:fe00 | 10df:fe00 | Emulex     | Zephyr-X LightPulse Fibre... | 1     | lpfc       | 6806624961 |
| 117c:0064 | 117c:0064 | ATTO Te... | Celerity FC 16Gb/s Gen 5 ... | 1     |            | 43EE2001E1 |
| 11f8:8032 | 117c:003a | PMC-Sierra | PM8032 Tachyon QE8           | 1     | celerit... | 5315690568 |
| 19a2:0702 | 103c:3314 | Emulex     | OneConnect 10Gb iSCSI Ini... | 1     | be2iscsi   | DC4AC74B49 |
| 19a2:0704 | 103c:174b | Emulex     | OneConnect OCe10100/OCe10... | 1     | lpfc       | E707BBA6A9 |
| 1aed:2001 | 1028:1f70 | SanDisk    | ioDrive2                     | 1     |            | 1AFA47E662 |
| 1aed:2001 | 1590:006f | SanDisk    | ioDrive2                     | 1     |            | CD543E37E2 |
| 1aed:2001 | 1aed:2001 | SanDisk    | ioDrive2                     | 1     |            | CD543E37E2 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1d02 | 1043:84ef | Intel      | C600/X79 series chipset 6... | 13    | ahci       | A4C832AB44 |
| 8086:8d02 | 15d9:0821 | Intel      | C610/X99 series chipset 6... | 13    | ahci       | 57FC9BDF47 |
| 8086:8d62 | 15d9:0821 | Intel      | C610/X99 series chipset s... | 13    | ahci       | 57FC9BDF47 |
| 8086:a182 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 13    | ahci       | FD087082C0 |
| 8086:a1d2 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 13    | ahci       | FD087082C0 |
| 8086:1d02 | 103c:18a9 | Intel      | C600/X79 series chipset 6... | 12    | ahci       | 2FC41158D5 |
| 8086:1d02 | 15d9:0636 | Intel      | C600/X79 series chipset 6... | 12    | ahci       | DD93F62FFC |
| 8086:3a22 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) SA... | 12    | ahci       | 8F945E0A15 |
| 1b4b:9230 | 1043:84fa | Marvell... | 88SE9230 PCIe 2.0 x2 4-po... | 8     | ahci       | A4C832AB44 |
| 1002:4391 | 1002:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 7     | ahci       | AD61EFB931 |
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 7     | ahci       | 2175466EA1 |
| 1b4b:9230 | 1b4b:9230 | Marvell... | 88SE9230 PCIe 2.0 x2 4-po... | 7     | ahci       | CFFE15A3E5 |
| 8086:8d02 | 103c:8030 | Intel      | C610/X99 series chipset 6... | 7     | ahci       | 23F12250E5 |
| 8086:8d02 | 8086:7270 | Intel      | C610/X99 series chipset 6... | 7     | ahci       | 937DE612E9 |
| 8086:8d62 | 1043:85f7 | Intel      | C610/X99 series chipset s... | 7     | ahci       | 4158CB76EF |
| 8086:8d62 | 15d9:0857 | Intel      | C610/X99 series chipset s... | 7     | ahci       | 7CF4F8ED17 |
| 8086:a182 | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     | ahci       | CEE7ED2CE9 |
| 8086:a1d2 | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     | ahci       | CEE7ED2CE9 |
| 8086:1d02 | 1028:04fa | Intel      | C600/X79 series chipset 6... | 6     | ahci       | 87A79FD79B |
| 8086:8d02 | 1028:0601 | Intel      | C610/X99 series chipset 6... | 6     | ahci       | F90168C69D |
| 8086:8d02 | 1043:85f6 | Intel      | C610/X99 series chipset 6... | 6     | ahci       | ED442D7C21 |
| 8086:8d02 | 15d9:0857 | Intel      | C610/X99 series chipset 6... | 6     | ahci       | 7CF4F8ED17 |
| 8086:8d62 | 1028:0601 | Intel      | C610/X99 series chipset s... | 6     | ahci       | F90168C69D |
| 8086:a102 | 8086:7270 | Intel      | Q170/Q150/B150/H170/H110/... | 6     | ahci       | 98C12554CB |
| 1022:7901 | 1458:1000 | AMD        | FCH SATA Controller [AHCI... | 5     | ahci       | D140FF934B |
| 1022:7901 | 15d9:7901 | AMD        | FCH SATA Controller [AHCI... | 5     | ahci       | 43E601437F |
| 8086:1d02 | 1028:048c | Intel      | C600/X79 series chipset 6... | 5     | ahci       | 4CE6A061A6 |
| 8086:8d02 | 15d9:0831 | Intel      | C610/X99 series chipset 6... | 5     | ahci       | 64918C950D |
| 8086:8d62 | 8086:7270 | Intel      | C610/X99 series chipset s... | 5     | ahci       | 822418675E |
| 8086:a102 | 1028:06a5 | Intel      | Q170/Q150/B150/H170/H110/... | 5     | ahci       | E2A3815DD2 |
| 8086:a182 | 1043:871e | Intel      | C620 Series Chipset Famil... | 5     | ahci       | AFAB4598A7 |
| 8086:1c02 | 1028:04de | Intel      | 6 Series/C200 Series Chip... | 4     | ahci       | E24D0E827B |
| 8086:1d02 | 8086:357e | Intel      | C600/X79 series chipset 6... | 4     | ahci       | 0FADD1EBE3 |
| 8086:1d02 | 8086:35a0 | Intel      | C600/X79 series chipset 6... | 4     | ahci       | FE1E6CFF79 |
| 8086:2922 | 8086:34d0 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 4     | ahci       | FC38CA11F5 |
| 8086:3a22 | 103c:330b | Intel      | 82801JI (ICH10 Family) SA... | 4     | ahci       | 28B04C3004 |
| 8086:3a22 | 15d9:060f | Intel      | 82801JI (ICH10 Family) SA... | 4     | ahci       | CF99AAD395 |
| 8086:8c02 | 15d9:0801 | Intel      | 8 Series/C220 Series Chip... | 4     | ahci       | 7F5062CA8F |
| 8086:8c02 | 15d9:0805 | Intel      | 8 Series/C220 Series Chip... | 4     | ahci       | 16BEFD9DC3 |
| 8086:a182 | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     | ahci       | E9A1FC86F9 |
| 8086:a182 | 15d9:096d | Intel      | C620 Series Chipset Famil... | 4     | ahci       | F9D0B2BC99 |
| 8086:a1d2 | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     | ahci       | E9A1FC86F9 |
| 8086:a1d2 | 15d9:096d | Intel      | C620 Series Chipset Famil... | 4     | ahci       | F9D0B2BC99 |
| 8086:a1d2 | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 4     | ahci       | CD543E37E2 |
| 8086:a352 | 8086:7270 | Intel      | Cannon Lake PCH SATA AHCI... | 4     | ahci       | B8FFB92409 |
| 1002:4390 | 1028:0444 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 3     | ahci       | B913A90C28 |
| 1002:4390 | 103c:176e | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 3     | ahci       | DC4AC74B49 |
| 1002:4390 | 15d9:ab11 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 3     | ahci       | D5563E325C |
| 1002:4394 | 1002:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 3     | ahci       | 578FEA3A6C |
| 19e5:a235 |           | Huawei ... | HiSilicon AHCI HBA           | 3     | ahci       | 63BDABB5A4 |
| 1b21:0612 | 15d9:0805 | ASMedia... | ASM1062 Serial ATA Contro... | 3     | ahci       | 16BEFD9DC3 |
| 8086:1c02 | 1028:04dd | Intel      | 6 Series/C200 Series Chip... | 3     | ahci       | D4CCC85620 |
| 8086:1c02 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 3     | ahci       | 57162CA72C |
| 8086:1d02 | 1014:1d02 | Intel      | C600/X79 series chipset 6... | 3     | ahci       | 58A63B2A93 |
| 8086:1d02 | 1028:04ce | Intel      | C600/X79 series chipset 6... | 3     | ahci       | 7A9C742839 |
| 8086:3a22 | 15d9:0001 | Intel      | 82801JI (ICH10 Family) SA... | 3     | ahci       | 6BA00F03DE |
| 8086:3a22 | 15d9:0400 | Intel      | 82801JI (ICH10 Family) SA... | 3     | ahci       | D9ED4F04A3 |
| 8086:8c02 | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 3     | ahci       | 34DBD86F7B |
| 8086:8c02 | 8086:8c02 | Intel      | 8 Series/C220 Series Chip... | 3     | ahci       | AE3BFE95C9 |
| 8086:8d62 | 15d9:0831 | Intel      | C610/X99 series chipset s... | 3     | ahci       | 64918C950D |
| 8086:8d62 | 15d9:0834 | Intel      | C610/X99 series chipset s... | 3     | ahci       | FA4BECDE8B |
| 8086:a182 | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     | ahci       | E752263E49 |
| 8086:a182 | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     | ahci       | 7AD1F5EB4E |
| 8086:a182 | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     | ahci       | C682299C13 |
| 8086:a182 | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 3     | ahci       | 8D109AC7B4 |
| 8086:a1d2 | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     | ahci       | E752263E49 |
| 8086:a1d2 | 1028:073a | Intel      | C620 Series Chipset Famil... | 3     | ahci       | 33FDE2B5FB |
| 8086:a1d2 | 1043:871f | Intel      | C620 Series Chipset Famil... | 3     | ahci       | AFAB4598A7 |
| 8086:a1d2 | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     | ahci       | 7AD1F5EB4E |
| 8086:a1d2 | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     | ahci       | C682299C13 |
| 8086:a1d2 | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     | ahci       | 5658A2FB98 |
| 8086:a1d2 | 1849:a1d2 | Intel      | C620 Series Chipset Famil... | 3     | ahci       | 35C171899E |
| 8086:a1d2 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 3     | ahci       | D373AF93CD |
| 8086:a352 | 15d9:1a1b | Intel      | Cannon Lake PCH SATA AHCI... | 3     | ahci       | 16D1B33F25 |
| 8086:a352 | 15d9:1a1d | Intel      | Cannon Lake PCH SATA AHCI... | 3     | ahci       | E57FDAECA4 |
| 1002:4390 | 15d9:ba11 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 2     | ahci       | 6381FD461D |
| 1002:4390 | 15d9:cd11 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 2     | ahci       | CF37C43C55 |
| 1b21:0612 | 15d9:1b2b | ASMedia... | ASM1062 Serial ATA Contro... | 2     | ahci       | 43E601437F |
| 1b21:0612 | 1b21:1060 | ASMedia... | ASM1062 Serial ATA Contro... | 2     | ahci       | AD61EFB931 |
| 1b21:0625 | 1043:8634 | ASMedia... | 106x SATA/RAID Controller    | 2     | ahci       | 755B723BB0 |
| 1b4b:9230 | 1028:1fe2 | Marvell... | 88SE9230 PCIe 2.0 x2 4-po... | 2     | ahci       | 03CC317284 |
| 8086:19b2 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 2     | ahci       | 40E07B4DAD |
| 8086:19c2 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 2     | ahci       | 40E07B4DAD |
| 8086:1c02 | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 2     | ahci       | E6D89DC95B |
| 8086:1d02 | 1028:04f8 | Intel      | C600/X79 series chipset 6... | 2     | ahci       | E8BE4F8032 |
| 8086:1d02 | 15d9:0626 | Intel      | C600/X79 series chipset 6... | 2     | ahci       | 00FDD71981 |
| 8086:1d02 | 15d9:062a | Intel      | C600/X79 series chipset 6... | 2     | ahci       | 2E139151DE |
| 8086:1d02 | 15d9:0660 | Intel      | C600/X79 series chipset 6... | 2     | ahci       | AFE42B7E58 |
| 8086:1d02 | 8086:3594 | Intel      | C600/X79 series chipset 6... | 2     | ahci       | FBDCC4D1F5 |
| 8086:2681 | 8086:3476 | Intel      | 631xESB/632xESB SATA AHCI... | 2     | ahci       | 38109F9919 |
| 8086:2681 | 8086:3486 | Intel      | 631xESB/632xESB SATA AHCI... | 2     | ahci       | 0A3F6D305B |
| 8086:3a22 | 1170:0047 | Intel      | 82801JI (ICH10 Family) SA... | 2     | ahci       | 9D511D1A0B |
| 8086:3a22 | 15d9:0007 | Intel      | 82801JI (ICH10 Family) SA... | 2     | ahci       | A652ED3DB4 |
| 8086:3a22 | 15d9:0100 | Intel      | 82801JI (ICH10 Family) SA... | 2     | ahci       | C83DC07B7C |
| 8086:3a22 | 1734:1150 | Intel      | 82801JI (ICH10 Family) SA... | 2     | ahci       | 4874F3ABB6 |
| 8086:3a22 | 8086:34de | Intel      | 82801JI (ICH10 Family) SA... | 2     | ahci       | 3AB9D48A33 |
| 8086:3b22 | 1014:0377 | Intel      | 5 Series/3400 Series Chip... | 2     | ahci       | 882EA8E25E |
| 8086:3b22 | 1028:02a6 | Intel      | 5 Series/3400 Series Chip... | 2     | ahci       | 650772B11D |
| 8086:8c02 | 15d9:0803 | Intel      | 8 Series/C220 Series Chip... | 2     | ahci       | 869444ACF6 |
| 8086:8c02 | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 2     | ahci       | 9AF20F3BA9 |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1d00 | 103c:18a9 | Intel      | C600/X79 series chipset 4... | 18    | pata_acpi  | 799CC190DB |
| 8086:3a20 | 103c:330d | Intel      | 82801JI (ICH10 Family) 4 ... | 17    | pata_acpi  | A2261C146D |
| 8086:2921 | 1028:0235 | Intel      | 82801IB (ICH9) 2 port SAT... | 12    | ata_piix   | 4DEBADA4BF |
| 8086:269e | 103c:31fe | Intel      | 631xESB/632xESB IDE Contr... | 10    | pata_acpi  | FA5961B4C8 |
| 8086:2921 | 1028:0236 | Intel      | 82801IB (ICH9) 2 port SAT... | 7     | pata_acpi  | 5FBC90E0CD |
| 8086:3b20 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 7     | ata_piix   | 741DB5D841 |
| 8086:3b26 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 7     | ata_piix   | 741DB5D841 |
| 8086:3a20 | 1014:3a20 | Intel      | 82801JI (ICH10 Family) 4 ... | 6     | pata_acpi  | 2856AAF09F |
| 197b:2368 | 197b:2368 | JMicron... | JMB368 IDE controller        | 5     | pata_jm... | C83DC07B7C |
| 8086:1d08 | 103c:18a9 | Intel      | C600/X79 series chipset 2... | 5     | ata_pii... | 1E7A730FCC |
| 8086:3a20 | 8086:34dc | Intel      | 82801JI (ICH10 Family) 4 ... | 5     | pata_acpi  | 61DFD26E01 |
| 8086:3a26 | 1014:3a26 | Intel      | 82801JI (ICH10 Family) 2 ... | 5     | pata_acpi  | 2856AAF09F |
| 8086:3a26 | 8086:34dc | Intel      | 82801JI (ICH10 Family) 2 ... | 5     | pata_acpi  | 61DFD26E01 |
| 1002:439c | 15d9:ab11 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 4     | pata_at... | D5563E325C |
| 8086:269e | 1028:01b2 | Intel      | 631xESB/632xESB IDE Contr... | 4     | pata_acpi  | 252659BF58 |
| 8086:269e | 8086:3476 | Intel      | 631xESB/632xESB IDE Contr... | 4     | pata_acpi  | 38109F9919 |
| 8086:27c0 | 1028:01e7 | Intel      | NM10/ICH7 Family SATA Con... | 4     | pata_acpi  | EA66809CE7 |
| 8086:27df | 1028:01e7 | Intel      | 82801G (ICH7 Family) IDE ... | 4     | pata_acpi  | EA66809CE7 |
| 8086:2921 | 1028:0237 | Intel      | 82801IB (ICH9) 2 port SAT... | 4     | pata_acpi  | B506487E48 |
| 8086:3a20 | 15d9:0600 | Intel      | 82801JI (ICH10 Family) 4 ... | 4     | pata_acpi  | C17B3F71EC |
| 8086:3a20 | 8086:34da | Intel      | 82801JI (ICH10 Family) 4 ... | 4     | pata_acpi  | FE3D758C20 |
| 8086:3a20 | 8086:34e2 | Intel      | 82801JI (ICH10 Family) 4 ... | 4     | pata_acpi  | D577FE5BA4 |
| 8086:3a26 | 15d9:0600 | Intel      | 82801JI (ICH10 Family) 2 ... | 4     | pata_acpi  | C17B3F71EC |
| 8086:3a26 | 8086:34da | Intel      | 82801JI (ICH10 Family) 2 ... | 4     | pata_acpi  | FE3D758C20 |
| 8086:3a26 | 8086:34e2 | Intel      | 82801JI (ICH10 Family) 2 ... | 4     | pata_acpi  | D577FE5BA4 |
| 8086:a1bc | 1028:0739 | Intel      | C620 Series Chipset Famil... | 4     | pata_acpi  | 2D1D9030E8 |
| 1002:439c | 103c:1773 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 3     | pata_at... | DC4AC74B49 |
| 1002:439c | 103c:3338 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 3     | pata_at... | 91AD975174 |
| 1002:439c | 15d9:bc11 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 3     | pata_at... | AD61EFB931 |
| 8086:2680 | 1028:01b3 | Intel      | 631xESB/632xESB/3100 Chip... | 3     | pata_acpi  | 8571D09FE7 |
| 8086:269e | 8086:3486 | Intel      | 631xESB/632xESB IDE Contr... | 3     | pata_acpi  | 0A3F6D305B |
| 8086:3a20 | 1028:028c | Intel      | 82801JI (ICH10 Family) 4 ... | 3     | pata_acpi  | 0094B64AB2 |
| 8086:3a20 | 1028:028d | Intel      | 82801JI (ICH10 Family) 4 ... | 3     | ata_pii... | 1A05144C7E |
| 8086:3a20 | 15d9:0400 | Intel      | 82801JI (ICH10 Family) 4 ... | 3     | ata_pii... | B3C09674CF |
| 8086:3a20 | 8086:3a20 | Intel      | 82801JI (ICH10 Family) 4 ... | 3     | pata_acpi  | 32DF3AB75F |
| 8086:3a26 | 1028:028c | Intel      | 82801JI (ICH10 Family) 2 ... | 3     | pata_acpi  | 0094B64AB2 |
| 8086:3a26 | 1028:028d | Intel      | 82801JI (ICH10 Family) 2 ... | 3     | ata_pii... | 1A05144C7E |
| 8086:3a26 | 15d9:0400 | Intel      | 82801JI (ICH10 Family) 2 ... | 3     | ata_pii... | B3C09674CF |
| 8086:3a26 | 8086:3a26 | Intel      | 82801JI (ICH10 Family) 2 ... | 3     | pata_acpi  | 32DF3AB75F |
| 8086:a1bc | 1028:073a | Intel      | C620 Series Chipset Famil... | 3     | pata_acpi  | 33FDE2B5FB |
| 8086:a1bc | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     | pata_acpi  | 5658A2FB98 |
| 1002:439c | 15d9:ba11 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 2     | pata_at... | 6381FD461D |
| 1002:439c | 15d9:cd11 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 2     | pata_at... | CF37C43C55 |
| 10de:036e | 1462:cb84 | Nvidia     | MCP55 IDE                    | 2     | pata_am... | B8300AFB35 |
| 10de:037f | 1462:cb84 | Nvidia     | MCP55 SATA Controller        | 2     | sata_nv... | B8300AFB35 |
| 8086:1c00 | 1043:8498 | Intel      | 6 Series/C200 Series Chip... | 2     | pata_acpi  | 750A124EF3 |
| 8086:1c08 | 1043:8497 | Intel      | 6 Series/C200 Series Chip... | 2     | pata_acpi  | 750A124EF3 |
| 8086:24db | 1028:016d | Intel      | 82801EB/ER (ICH5/ICH5R) I... | 2     | ata_pii... | 08919C80E8 |
| 8086:2680 | 1014:02dd | Intel      | 631xESB/632xESB/3100 Chip... | 2     | ata_pii... | 3A68279F78 |
| 8086:2680 | 1028:01b2 | Intel      | 631xESB/632xESB/3100 Chip... | 2     | pata_acpi  | 1C2A92612A |
| 8086:2680 | 8086:3476 | Intel      | 631xESB/632xESB/3100 Chip... | 2     | ata_pii... | 0E19261B88 |
| 8086:269e | 1028:01b3 | Intel      | 631xESB/632xESB IDE Contr... | 2     | pata_acpi  | CA9524A167 |
| 8086:2920 | 8086:34d0 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 2     | pata_acpi  | 81A05F54F2 |
| 8086:2921 | 1028:029b | Intel      | 82801IB (ICH9) 2 port SAT... | 2     | ata_piix   | 1F6AFDC077 |
| 8086:2926 | 8086:34d0 | Intel      | 82801I (ICH9 Family) 2 po... | 2     | pata_acpi  | 81A05F54F2 |
| 8086:3a20 | 1028:02d3 | Intel      | 82801JI (ICH10 Family) 4 ... | 2     | pata_acpi  | C3EC3FCF73 |
| 8086:3a20 | 1028:02d4 | Intel      | 82801JI (ICH10 Family) 4 ... | 2     | pata_acpi  | 1AFA47E662 |
| 8086:3a20 | 1033:8372 | Intel      | 82801JI (ICH10 Family) 4 ... | 2     | pata_acpi  | 460A274240 |
| 8086:3a20 | 15d9:0100 | Intel      | 82801JI (ICH10 Family) 4 ... | 2     | pata_acpi  | 0B2E10175B |
| 8086:3a20 | 1734:1150 | Intel      | 82801JI (ICH10 Family) 4 ... | 2     | pata_acpi  | 28D7F4FA53 |
| 8086:3a26 | 1033:8372 | Intel      | 82801JI (ICH10 Family) 2 ... | 2     | pata_acpi  | 460A274240 |
| 8086:3a26 | 15d9:0100 | Intel      | 82801JI (ICH10 Family) 2 ... | 2     | pata_acpi  | 0B2E10175B |
| 8086:3a26 | 1734:114d | Intel      | 82801JI (ICH10 Family) 2 ... | 2     | pata_acpi  | 28D7F4FA53 |
| 8086:3b20 | 1014:0377 | Intel      | 5 Series/3400 Series Chip... | 2     | ata_pii... | EE06305E30 |
| 8086:3b20 | 1028:02a3 | Intel      | 5 Series/3400 Series Chip... | 2     | pata_acpi  | 07FABCF50F |
| 8086:3b26 | 1014:0377 | Intel      | 5 Series/3400 Series Chip... | 2     | ata_pii... | EE06305E30 |
| 8086:3b26 | 1028:02a3 | Intel      | 5 Series/3400 Series Chip... | 2     | pata_acpi  | 07FABCF50F |
| 1002:439c | 1002:439c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | pata_at... | 368A801F1A |
| 1002:439c | 1028:0489 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | pata_at... | 0335142464 |
| 1002:439c | 15d9:a711 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | pata_at... | CFFE15A3E5 |
| 1002:439c | 15d9:a811 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | pata_at... | 340A3648A2 |
| 1002:439c | 15d9:ca11 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | pata_at... | 9712585D1C |
| 10de:0053 | 10f1:2891 | Nvidia     | CK804 IDE                    | 1     | pata_am... | 64251B3F2A |
| 10de:0053 | 10f1:2895 | Nvidia     | CK804 IDE                    | 1     | pata_amd   | 768571B831 |
| 10de:0054 | 10de:cb84 | Nvidia     | CK804 Serial ATA Controller  | 1     | sata_nv    | 64251B3F2A |
| 10de:0054 | 10f1:2895 | Nvidia     | CK804 Serial ATA Controller  | 1     | sata_nv    | 768571B831 |
| 10de:0055 | 10de:cb84 | Nvidia     | CK804 Serial ATA Controller  | 1     | sata_nv    | 64251B3F2A |
| 10de:0055 | 10f1:2895 | Nvidia     | CK804 Serial ATA Controller  | 1     | sata_nv    | 768571B831 |
| 10de:036e | 108e:534d | Nvidia     | MCP55 IDE                    | 1     | pata_am... | 1F35F79302 |
| 10de:036e | 1462:2800 | Nvidia     | MCP55 IDE                    | 1     | pata_am... | 933EED177A |
| 10de:037f | 108e:534d | Nvidia     | MCP55 SATA Controller        | 1     | sata_nv... | 1F35F79302 |
| 10de:037f | 1462:2800 | Nvidia     | MCP55 SATA Controller        | 1     | sata_nv... | 933EED177A |
| 1166:0211 |           | Broadcom   | OSB4 IDE Controller          | 1     | pata_se... | 0B5D843F10 |
| 1166:0212 | 1166:0212 | Broadcom   | CSB5 IDE Controller          | 1     | pata_se... | 46973B5B05 |
| 1166:0214 | 1028:0205 | Broadcom   | BCM5785 [HT1000] IDE         | 1     | pata_se... | B7596E9C0E |
| 1166:0214 | 103c:320b | Broadcom   | BCM5785 [HT1000] IDE         | 1     | pata_se... | 5AB62504F8 |
| 1166:0214 | 1734:10b9 | Broadcom   | BCM5785 [HT1000] IDE         | 1     | pata_se... | A0F9679F57 |
| 1166:024b | 1028:0205 | Broadcom   | BCM5785 [HT1000] SATA (PA... | 1     | sata_sv... | B7596E9C0E |
| 1166:024b | 1166:024b | Broadcom   | BCM5785 [HT1000] SATA (PA... | 1     | sata_sv... | A0F9679F57 |
| 8086:1c00 | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 1     | ata_pii... | D092DEFE79 |
| 8086:1c00 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     | pata_acpi  | D9F1CB21BC |
| 8086:1c08 | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 1     | ata_pii... | D092DEFE79 |
| 8086:1c08 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     | pata_acpi  | D9F1CB21BC |
| 8086:1d00 | 1014:1d00 | Intel      | C600/X79 series chipset 4... | 1     | ata_pii... | FC0558920D |
| 8086:1d00 | 1028:04ce | Intel      | C600/X79 series chipset 4... | 1     | pata_acpi  | FC4B28C875 |
| 8086:1d00 | 1028:04f8 | Intel      | C600/X79 series chipset 4... | 1     | pata_acpi  | EA68439F2E |
| 8086:1d00 | 1028:04fa | Intel      | C600/X79 series chipset 4... | 1     | ata_pii... | 1A32B081A7 |
| 8086:1d08 | 1014:1d08 | Intel      | C600/X79 series chipset 2... | 1     | ata_pii... | FC0558920D |
| 8086:1d08 | 1028:04ce | Intel      | C600/X79 series chipset 2... | 1     | pata_acpi  | FC4B28C875 |
| 8086:1d08 | 1028:04f8 | Intel      | C600/X79 series chipset 2... | 1     | pata_acpi  | EA68439F2E |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 32    | nvme       | 331227D869 |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 9     | nvme       | E014B80891 |
| 14a4:2300 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 6     | nvme       | 4391DFF8D2 |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 5     | nvme       | 937DE612E9 |
| 8086:0a54 | 8086:4802 | Intel      | NVMe Datacenter SSD [3DNA... | 5     | nvme       | 4FC6787907 |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 3     | nvme       | 21124E85CC |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 3     | nvme       | 35C171899E |
| 1344:5405 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 2     | nvme       | C3665EBF57 |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/SN750 / PC ... | 2     | nvme       | F6F6B1BC99 |
| 15b7:5009 | 15b7:5009 | Sandisk    | WD Blue SN550 NVMe SSD       | 2     | nvme       | AD61EFB931 |
| 8086:0a54 | 8086:4714 | Intel      | NVMe Datacenter SSD [3DNA... | 2     | nvme       | D373AF93CD |
| 8086:2700 | 8086:3900 | Intel      | Optane SSD 900P Series       | 2     | nvme       | 376BED560D |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 1     | nvme       | 3514F18D29 |
| 126f:2263 | 126f:2263 | Silicon... | SM2263EN/SM2263XT SSD Con... | 1     | nvme       | 0C9DFEB831 |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 1     | nvme       | AC7F5D0860 |
| 144d:a821 | 108e:a803 | Samsung... | NVMe SSD Controller 172X     | 1     | nvme       | FDC516788A |
| 144d:a822 | 1028:1ff7 | Samsung... | NVMe SSD Controller 172Xa... | 1     | nvme       | E9A1FC86F9 |
| 144d:a824 | 144d:a801 | Samsung... | NVMe SSD Controller PM173X   | 1     | nvme       | 4231BB05CE |
| 14a4:22f1 | 1b4b:1093 | Lite-On... | M8Pe Series NVMe SSD         | 1     | nvme       | 1AFA47E662 |
| 15b7:5006 | 15b7:5006 | Sandisk    | WD Black SN750 / PC SN730... | 1     | nvme       | 33FDE2B5FB |
| 1987:5007 | 1987:5007 | Phison ... | E7 NVMe Controller           | 1     | nvme       | BB8832ACBD |
| 19e5:3714 | 19e5:5123 | Huawei ... | ES3000 V5 NVMe PCIe SSD      | 1     | nvme       | A17BEFC33B |
| 19e5:3714 | 19e5:5312 | Huawei ... | ES3000 V5 NVMe PCIe SSD      | 1     | nvme       | 3CA7825025 |
| 1b4b:1160 | 1b4b:1160 | Marvell... | Marvell Non-Volatile memo... | 1     | nvme       | 375EC8881D |
| 1bb1:0100 | 1bb1:0121 | Seagate... | Nytro Flash Storage          | 1     | nvme       | 869C99ACED |
| 1bb1:5012 | 1bb1:5012 | Seagate... | FireCuda 510 SSD             | 1     | nvme       | 937DE612E9 |
| 1bb1:5016 | 1bb1:5016 | Seagate... | FireCuda 520 SSD             | 1     | nvme       | 86AB491564 |
| 8086:0953 | 8086:3702 | Intel      | PCIe Data Center SSD         | 1     | nvme       | 64918C950D |
| 8086:0953 | 8086:3704 | Intel      | PCIe Data Center SSD         | 1     | nvme       | 5F6D0233A8 |
| 8086:0953 | 8086:3708 | Intel      | PCIe Data Center SSD         | 1     | nvme       | 971A75C8ED |
| 8086:0953 | 8086:3709 | Intel      | PCIe Data Center SSD         | 1     | nvme       | 2F38C3FD0E |
| 8086:0a53 | 8086:3705 | Intel      | DC P3520 SSD                 | 1     | nvme       | C682299C13 |
| 8086:0a54 | 8086:4702 | Intel      | NVMe Datacenter SSD [3DNA... | 1     | nvme       | 755B723BB0 |
| 8086:0a54 | 8086:4805 | Intel      | NVMe Datacenter SSD [3DNA... | 1     | nvme       | EB0C95C2B3 |
| 8086:2701 | 8086:3904 | Intel      | NVMe Datacenter SSD [Optane] | 1     | nvme       | 64918C950D |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 1     | nvme       | 4D0ED95E02 |
| 8086:faf0 | 8086:390e | Intel      | Non-Volatile memory contr... | 1     | nvme       | A74597710B |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 103c:323a | 103c:3245 | Hewlett... | Smart Array G6 controllers   | 32    | hpsa       | C56840DF98 |
| 1000:0079 | 1028:1f17 | LSI Log... | MegaRAID SAS 2108 [Libera... | 18    | megarai... | B913A90C28 |
| 103c:323b | 103c:3354 | Hewlett... | Smart Array Gen8 Controllers | 18    | hpsa       | 799CC190DB |
| 1000:005d | 1000:9363 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 16    | megarai... | 2F38C3FD0E |
| 1000:0060 | 1028:1f0c | LSI Log... | MegaRAID SAS 1078            | 12    | megarai... | 546C1677CB |
| 1000:005f | 1028:1f44 | LSI Log... | MegaRAID SAS-3 3008 [Fury]   | 11    | megarai... | 2A87802C58 |
| 1000:005d | 15d9:0809 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 8     | megarai... | 822418675E |
| 103c:323b | 103c:3351 | Hewlett... | Smart Array Gen8 Controllers | 8     | hpsa       | CD543E37E2 |
| 1000:005d | 1028:1f49 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 7     | megarai... | E4DEE6FAF7 |
| 1000:0079 | 1000:9263 | LSI Log... | MegaRAID SAS 2108 [Libera... | 7     | megarai... | C60718AEF4 |
| 1000:005b | 1028:1f35 | Broadco... | MegaRAID SAS 2208 [Thunde... | 6     | megarai... | 87A79FD79B |
| 1000:005b | 1028:1f38 | LSI Log... | MegaRAID SAS 2208 [Thunde... | 6     | megarai... | 9977E2B5C3 |
| 1000:0060 | 1028:1f0b | LSI Log... | MegaRAID SAS 1078            | 6     | megarai... | 1A05144C7E |
| 103c:3230 | 103c:3234 | Hewlett... | Smart Array Controller       | 6     | hpsa       | 5AB62504F8 |
| 103c:3239 | 103c:21c0 | Hewlett... | Smart Array Gen9 Controllers | 6     | hpsa       | 23F12250E5 |
| 17d3:1880 | 17d3:1883 | Areca T... | ARC-188x series PCIe 2.0/... | 6     | arcmsr     | D140FF934B |
| 1000:0014 | 1d49:0602 | Broadco... | MegaRAID Tri-Mode SAS3516    | 5     | megarai... | CEE7ED2CE9 |
| 1000:005d | 1028:1f42 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 5     | megarai... | 4C88B2E09B |
| 8086:201d | 8086:0000 | Intel      | Volume Management Device ... | 5     | vmd        | 2D1D9030E8 |
| 1000:0016 | 1028:1fcd | LSI Log... | MegaRAID Tri-Mode SAS3508    | 4     | megarai... | E9A1FC86F9 |
| 1000:005b | 1028:1f34 | LSI Log... | MegaRAID SAS 2208 [Thunde... | 4     | megarai... | D1FAA99D53 |
| 1000:005b | 8086:3510 | LSI Log... | MegaRAID SAS 2208 [Thunde... | 4     | megarai... | FE1E6CFF79 |
| 1000:005d | 1000:9361 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 4     | megarai... | 8D109AC7B4 |
| 1000:005d | 1028:1f47 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 4     | megarai... | 018184F964 |
| 1000:0060 | 1734:10f9 | Broadco... | MegaRAID SAS 1078            | 4     | megarai... | 4874F3ABB6 |
| 1000:0073 | 1028:1f51 | LSI Log... | MegaRAID SAS 2008 [Falcon]   | 4     | megarai... | 7462357A1A |
| 1000:0016 | 19e5:d215 | Broadco... | MegaRAID Tri-Mode SAS3508    | 3     | megarai... | 63BDABB5A4 |
| 1000:005b | 1014:040b | LSI Log... | MegaRAID SAS 2208 [Thunde... | 3     | megarai... | 58A63B2A93 |
| 1000:0079 | 1028:1f16 | Broadco... | MegaRAID SAS 2108 [Libera... | 3     | megarai... | 0094B64AB2 |
| 1028:0015 | 1028:1f03 | Dell       | PowerEdge Expandable RAID... | 3     | megarai... | AE126E5F79 |
| 103c:323a | 103c:3243 | Hewlett... | Smart Array G6 controllers   | 3     | hpsa       | 28B04C3004 |
| 13c1:1003 | 13c1:1003 | 3ware      | 9550SX SATA-II RAID PCI-X    | 3     | 3w_9xxx    | 0A3F6D305B |
| 17d3:1880 | 17d3:1880 | Areca T... | ARC-188x series PCIe 2.0/... | 3     | arcmsr     | B3C09674CF |
| 1b4b:9485 | 1b4b:9480 | Marvell... | 88SE9485 SAS/SATA 6Gb/s c... | 3     | mvsas      | 8E9E87A717 |
| 8086:2826 | 1028:0739 | Intel      | C600/X79 series chipset S... | 3     | ahci       | 52B7CECCFF |
| 8086:2826 | 1028:073a | Intel      | C600/X79 series chipset S... | 3     | ahci       | 33FDE2B5FB |
| 1000:0016 | 1028:1fcb | LSI Log... | MegaRAID Tri-Mode SAS3508    | 2     | megarai... | DF7C395A6C |
| 1000:0016 | 1d49:0601 | Broadco... | MegaRAID Tri-Mode SAS3508    | 2     | megarai... | 2AE35CF194 |
| 1000:005b | 1028:1f31 | Broadco... | MegaRAID SAS 2208 [Thunde... | 2     | megarai... | A4512466F1 |
| 1000:005d | 1014:0454 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 2     | megarai... | 3510DD7B10 |
| 1000:005d | 8086:351e | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 2     | megarai... | D373AF93CD |
| 1000:005f | 1028:1f4b | LSI Log... | MegaRAID SAS-3 3008 [Fury]   | 2     | megarai... | A98D12AD3E |
| 1000:0072 | 1000:0072 | LSI Log... | SAS2008 PCI-Express Fusio... | 2     | mpt3sas    | 368A801F1A |
| 1000:0072 | 1028:1f51 | LSI Log... | SAS2008 PCI-Express Fusio... | 2     | mpt3sas    | 31EA0B6D96 |
| 1000:0073 | 1014:040d | Broadco... | MegaRAID SAS 2008 [Falcon]   | 2     | megarai... | A4B7DEFC78 |
| 1000:0073 | 1028:1f4e | Broadco... | MegaRAID SAS 2008 [Falcon]   | 2     | megarai... | EB7B7FD10B |
| 1000:0079 | 1000:9260 | LSI Log... | MegaRAID SAS 2108 [Libera... | 2     | megarai... | 376BED560D |
| 1000:0079 | 1014:03b2 | LSI Log... | MegaRAID SAS 2108 [Libera... | 2     | megarai... | C43FD89A0B |
| 1028:0013 | 1028:016d | Dell       | PowerEdge Expandable RAID... | 2     | megarai... | 08919C80E8 |
| 1028:0016 | 1028:1f24 | Dell       | PowerEdge Expandable RAID... | 2     |            | 650772B11D |
| 103c:3230 | 103c:3235 | Hewlett... | Smart Array Controller       | 2     | hpsa       | FA5961B4C8 |
| 103c:3238 | 103c:3211 | Hewlett... | Smart Array E200i (SAS Co... | 2     | cciss      | B3175C4255 |
| 103c:323b | 103c:3350 | Hewlett... | Smart Array Gen8 Controllers | 2     | hpsa       | 9E2CA41ABB |
| 103c:323b | 103c:3355 | Hewlett... | Smart Array Gen8 Controllers | 2     | hpsa       | C2075DC2CE |
| 1590:0045 | 1590:0045 | Hewlett... | RAID bus controller          | 2     |            | 3FAC52AF81 |
| 17d3:1880 | 17d3:1882 | Areca T... | ARC-188x series PCIe 2.0/... | 2     | arcmsr     | FE1E6CFF79 |
| 8086:201d | 1043:875d | Intel      | Volume Management Device ... | 2     | vmd        | C934F8E023 |
| 8086:2826 | 103c:81c7 | Intel      | C600/X79 series chipset S... | 2     | ahci       | ED3C250112 |
| 8086:2827 | 103c:81c6 | Intel      | C610/X99 series chipset s... | 2     | ahci       | 9D6E46ECA9 |
| 8086:2827 | 103c:81c7 | Intel      | C610/X99 series chipset s... | 2     | ahci       | ED3C250112 |
| 8086:3b25 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 2     | ahci       | 0A8BFA9B71 |
| 8086:a356 | 1028:088e | Intel      | 300 Series Chipset Family... | 2     | ahci       | 2A87802C58 |
| 9005:0285 | 9005:02d1 | Adaptec    | AAC-RAID                     | 2     | aacraid    | 591107EC98 |
| 9005:0286 | 1014:9580 | Adaptec    | AAC-RAID (Rocket)            | 2     | aacraid    | 3A68279F78 |
| 1000:0010 | 0e11:4040 | Broadco... | 53C1510                      | 1     |            | 0B5D843F10 |
| 1000:0014 | 1000:9460 | Broadco... | MegaRAID Tri-Mode SAS3516    | 1     | megarai... | 33FDE2B5FB |
| 1000:0014 | 1000:9467 | Broadco... | MegaRAID Tri-Mode SAS3516    | 1     | megarai... | 2175466EA1 |
| 1000:0014 | 1028:1f3b | Broadco... | MegaRAID Tri-Mode SAS3516    | 1     | megarai... | B7F3606E31 |
| 1000:0017 | 1000:9440 | Broadco... | MegaRAID Tri-Mode SAS3408    | 1     | megarai... | 43E601437F |
| 1000:005b | 1000:9271 | Broadco... | MegaRAID SAS 2208 [Thunde... | 1     | megarai... | CEC82EF5D0 |
| 1000:005b | 1000:9276 | LSI Log... | MegaRAID SAS 2208 [Thunde... | 1     | megarai... | 5F9F099F36 |
| 1000:005b | 1000:9285 | Broadco... | MegaRAID SAS 2208 [Thunde... | 1     | megarai... | 7A9C742839 |
| 1000:005b | 1000:9288 | Broadco... | MegaRAID SAS 2208 [Thunde... | 1     | megarai... | C682299C13 |
| 1000:005b | 1014:0448 | Broadco... | MegaRAID SAS 2208 [Thunde... | 1     | megarai... | 7C109612B9 |
| 1000:005b | 1028:1f77 | Broadco... | MegaRAID SAS 2208 [Thunde... | 1     | megarai... | A98D12AD3E |
| 1000:005d | 1028:1f43 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | megarai... | 031D1E0BEC |
| 1000:005d | 1043:8666 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | megarai... | AFAB4598A7 |
| 1000:005d | 19e5:d207 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | megarai... | 5EB4DFC951 |
| 1000:005d | 8086:9362 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | megarai... | 2794B14FEE |
| 1000:005f | 1000:9341 | LSI Log... | MegaRAID SAS-3 3008 [Fury]   | 1     | megarai... | 64918C950D |
| 1000:005f | 1000:9343 | Broadco... | MegaRAID SAS-3 3008 [Fury]   | 1     | megarai... | 4E379512D0 |
| 1000:005f | 1014:0456 | LSI Log... | MegaRAID SAS-3 3008 [Fury]   | 1     | megarai... | 817865DED6 |
| 1000:0060 | 1000:100a | Broadco... | MegaRAID SAS 1078            | 1     | megarai... | 5C3DF14DAD |
| 1000:0073 | 1000:9240 | Broadco... | MegaRAID SAS 2008 [Falcon]   | 1     | megarai... | B273789224 |
| 1000:0073 | 1000:9241 | LSI Log... | MegaRAID SAS 2008 [Falcon]   | 1     | megarai... | B5E13C32D7 |
| 1000:0073 | 8086:9240 | Broadco... | MegaRAID SAS 2008 [Falcon]   | 1     | megarai... | E06B230F3D |
| 1000:0079 | 1000:9261 | LSI Log... | MegaRAID SAS 2108 [Libera... | 1     | megarai... | 9762DCCBE9 |
| 1000:0079 | 15d9:0700 | Broadco... | MegaRAID SAS 2108 [Libera... | 1     | megarai... | E7D96A67AB |
| 1000:0079 | 1734:1176 | Broadco... | MegaRAID SAS 2108 [Libera... | 1     | megarai... | E6D89DC95B |
| 1000:0079 | 8086:9260 | Broadco... | MegaRAID SAS 2108 [Libera... | 1     | megarai... | 1BEF5D0065 |
| 1000:0411 | 1734:1081 | Broadco... | MegaRAID SAS 1068            | 1     | megarai... | 1A0DFE074E |
| 1000:0411 | 8086:1003 | Broadco... | MegaRAID SAS 1068            | 1     |            | 0E19261B88 |
| 1002:4391 | 103c:1778 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | F03EBEFE94 |
| 1002:4392 | 15d9:ab11 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | A2C07ECC65 |
| 103c:193f | 103c:3381 | Hewlett... | Dynamic Smart Array B140i    | 1     |            | 3C08E6393F |
| 103c:3220 | 103c:3225 | Hewlett... | Smart Array P600             | 1     | hpsa       | BF8AB3D150 |
| 103c:3239 | 103c:21c7 | Hewlett... | Smart Array Gen9 Controllers | 1     | hpsa       | 3C08E6393F |
| 103c:323a | 103c:3241 | Hewlett... | Smart Array G6 controllers   | 1     | hpsa       | F03EBEFE94 |
| 103c:323c | 103c:1924 | Hewlett... | Smart Array Gen8+ Control... | 1     | hpsa       | 80E0B0265B |
| 1095:3132 | 1095:7132 | Silicon... | SiI 3132 Serial ATA Raid ... | 1     | sata_sil24 | CBBE408AAC |

### Storage/sas (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1d6b | 1043:84ef | Intel      | C602 chipset 4-Port SATA ... | 10    | isci       | A4C832AB44 |
| 1000:0072 | 1028:1f1c | LSI Log... | SAS2008 PCI-Express Fusio... | 8     | mpt3sas    | DEE1F70644 |
| 1000:0072 | 15d9:0400 | Broadco... | SAS2008 PCI-Express Fusio... | 8     | mpt3sas    | D5563E325C |
| 1000:0072 | 1000:3020 | LSI Log... | SAS2008 PCI-Express Fusio... | 7     | mpt3sas    | F3C8AC67B6 |
| 1000:0072 | 1028:1f1e | Broadco... | SAS2008 PCI-Express Fusio... | 5     | mpt3sas    | 0335142464 |
| 1000:0072 | 1028:1f1d | LSI Log... | SAS2008 PCI-Express Fusio... | 4     | mpt3sas    | 741DB5D841 |
| 8086:1d6b | 8086:35a1 | Intel      | C602 chipset 4-Port SATA ... | 4     | isci       | FE1E6CFF79 |
| 1000:0072 | 1000:3040 | LSI Log... | SAS2008 PCI-Express Fusio... | 3     | mpt3sas    | 61DFD26E01 |
| 1000:0097 | 1000:30e0 | LSI Log... | SAS3008 PCI-Express Fusio... | 3     | mpt3sas    | F9D5463C17 |
| 19e5:a230 |           | Huawei ... | HiSilicon SAS 3.0 HBA        | 3     | hisi_sa... | 63BDABB5A4 |
| 9005:028f | 103c:0602 | Adaptec    | Smart Storage PQI SAS        | 3     | smartpqi   | A0E4A8C71D |
| 1000:0070 | 1000:3010 | LSI Log... | SAS2004 PCI-Express Fusio... | 2     | mpt3sas    | 4CE6A061A6 |
| 1000:0086 | 15d9:0691 | Broadco... | SAS2308 PCI-Express Fusio... | 2     | mpt3sas    | F9D5463C17 |
| 1000:0087 | 1000:3040 | LSI Log... | SAS2308 PCI-Express Fusio... | 2     | mpt3sas    | 9FC500CA2E |
| 1000:0097 | 1000:0090 | Broadco... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | 2903921AEB |
| 1000:0097 | 1028:1f53 | Broadco... | SAS3008 PCI-Express Fusio... | 2     | mpt3sas    | DF9A63BE43 |
| 8086:1d6b | 15d9:0636 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | DD93F62FFC |
| 8086:1d6b | 15d9:0660 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | AFE42B7E58 |
| 1000:005d | 8086:3a1e | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | megarai... | 98C12554CB |
| 1000:0064 | 1000:3030 | Broadco... | SAS2116 PCI-Express Fusio... | 1     | mpt3sas    | 32951A000F |
| 1000:0064 | 1000:30d0 | Broadco... | SAS2116 PCI-Express Fusio... | 1     | mpt3sas    | 31EA0B6D96 |
| 1000:0064 | 15d9:083c | LSI Log... | SAS2116 PCI-Express Fusio... | 1     | mpt3sas    | DB25C87154 |
| 1000:0070 | 1014:03f7 | LSI Log... | SAS2004 PCI-Express Fusio... | 1     | mpt2sas    | D7CBC31CEE |
| 1000:0070 | 1014:03f8 | Broadco... | SAS2004 PCI-Express Fusio... | 1     | mpt2sas    | 7C109612B9 |
| 1000:0072 | 1000:3050 | LSI Log... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | 0B2E10175B |
| 1000:0072 | 1014:03cb | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | 2B9980B42B |
| 1000:007e | 1000:0507 | Broadco... | SSS6200 PCI-Express Flash... | 1     | mpt3sas    | BA4FFBDA6D |
| 1000:0087 | 1000:0087 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | BA0F3C3B41 |
| 1000:0087 | 1000:3020 | LSI Log... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | 7DC714253B |
| 1000:0087 | 1590:0042 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | A14015F487 |
| 1000:0087 | 8086:3519 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | FBDCC4D1F5 |
| 1000:0097 | 1000:30a0 | Broadco... | SAS3008 PCI-Express Fusio... | 1     | mpt3sas    | 21E2FBBB75 |
| 1000:0097 | 1043:860c | Broadco... | SAS3008 PCI-Express Fusio... | 1     | mpt3sas    | C934F8E023 |
| 1000:00c4 | 1000:3190 | Broadco... | SAS3224 PCI-Express Fusio... | 1     | mpt3sas    | 00FDD71981 |
| 11f8:8001 |           | PMC-Sierra | SPC 8x6G SAS/SATA (storport) | 1     | pm80xx     | 4F5756D065 |
| 8086:1d68 | 15d9:0626 | Intel      | C606 chipset Dual 4-Port ... | 1     | isci       | 00FDD71981 |
| 8086:1d68 | 15d9:0630 | Intel      | C606 chipset Dual 4-Port ... | 1     | isci       | 575A60EDC8 |
| 8086:1d6a | 8086:3583 | Intel      | C600/X79 series chipset D... | 1     | isci       | 9F6D925B73 |
| 8086:1d6b | 1014:0432 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | FC0558920D |
| 8086:1d6b | 15d9:062a | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 2E139151DE |
| 8086:1d6b | 15d9:062f | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | F5F0A90676 |
| 8086:1d6b | 15d9:0665 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | CEC82EF5D0 |
| 8086:1d6b | 15d9:066b | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 1FF0EE8759 |
| 8086:1d6b | 15d9:0703 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 8C793BB137 |
| 8086:1d6b | 15d9:0705 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | B3D08DD227 |
| 8086:1d6b | 15d9:070a | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | B4C8ABC585 |
| 8086:1d6b | 8086:357f | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 7DC714253B |
| 8086:1d6b | 8086:358d | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | D15B8F8758 |
| 8086:1d6b | 8086:3595 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 91F3C901D3 |
| 8086:1d6b | 8086:35b1 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 30CFD7BC18 |
| 8086:1d6d | 1734:11b6 | Intel      | C600/X79 series chipset 4... | 1     |            | 9C16958A72 |
| 8086:1d6f | 8086:3595 | Intel      | C600/X79 series chipset 4... | 1     |            | FBDCC4D1F5 |
| 9005:028d | 9005:0652 | Adaptec    | Series 8 12G SAS/PCIe 3      | 1     | aacraid    | 7479576DA8 |
| 9005:028f | 103c:0701 | Adaptec    | Smart Storage PQI SAS        | 1     | smartpqi   | 9E91D0ED19 |
| 9005:028f | 103c:1100 | Adaptec    | Smart Storage PQI SAS        | 1     | smartpqi   | 3120E02C21 |
| 9005:028f | 9005:0802 | Adaptec    | Smart Storage PQI SAS        | 1     | smartpqi   | A8FBAC3A35 |
| 9005:0450 | 11ab:6440 | Adaptec    | ASC-1405 Unified Serial HBA  | 1     | mvsas      | A61FFACB08 |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1000:0056 | 1014:03bb | LSI Log... | SAS1064ET PCI-Express Fus... | 5     | mptsas     | 882EA8E25E |
| 1000:0058 | 1028:1f0f | LSI Log... | SAS1068E PCI-Express Fusi... | 5     | mptsas     | 5136C6B827 |
| 1000:0058 | 1028:1f10 | Broadco... | SAS1068E PCI-Express Fusi... | 5     | mptsas     | 5FBC90E0CD |
| 1000:0058 | 1028:1f0e | LSI Log... | SAS1068E PCI-Express Fusi... | 4     | mptsas     | 4DEBADA4BF |
| 1000:0056 | 8086:3486 | Broadco... | SAS1064ET PCI-Express Fus... | 2     | mptsas     | 7E72574FF4 |
| 1000:0058 | 1014:0394 | LSI Log... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | 5C4A86988B |
| 1000:0058 | 15d9:0001 | Broadco... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | F645C4227C |
| 1000:000f | 0e11:7004 | Broadco... | 53c875                       | 1     | sym53c8xx  | AFF808A68F |
| 1000:0030 | 1000:50c0 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 3F4700F256 |
| 1000:0030 | 1014:026c | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 46973B5B05 |
| 1000:0030 | 1028:016e | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 76EF1C8CA9 |
| 1000:0054 | 1028:1f09 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | 4FDE34B201 |
| 1000:0054 | 1734:10b9 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | A0F9679F57 |
| 1000:0054 | 8086:3504 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 1     | mptsas     | A61FFACB08 |
| 1000:0056 | 8086:346c | Broadco... | SAS1064ET PCI-Express Fus... | 1     | mptsas     | 390F15B7F9 |
| 1000:0058 | 1000:30a0 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | E5AEAF13AE |
| 1000:0058 | 1000:3150 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | 8F6E544820 |
| 1000:0059 | 15d9:0006 | Broadco... | MegaRAID SAS 8208ELP/8208ELP | 1     | mptsas     | 8F945E0A15 |
| 9004:5078 | 9004:7850 | Adaptec    | AIC-7850T/7856T [AVA-2902... | 1     | aic7xxx    | 171EE8DB12 |
| 9005:8017 | 9005:0045 | Adaptec    | ASC-29320ALP U320            | 1     | aic79xx    | 5C3DF14DAD |
| 9005:801f | 8086:341a | Adaptec    | AIC-7902 U320                | 1     | aic79xx    | 37AA8C0E8E |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:204e | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 90    | skx_uncore | 2D1D9030E8 |
| 8086:2018 | 8086:0000 | Intel      | Sky Lake-E M2PCI Registers   | 87    |            | 2D1D9030E8 |
| 8086:2035 |           | Intel      | Sky Lake-E RAS Configurat... | 87    |            | 2D1D9030E8 |
| 8086:2040 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 87    |            | 2D1D9030E8 |
| 8086:2041 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 87    |            | 2D1D9030E8 |
| 8086:2042 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 87    | skx_uncore | 2D1D9030E8 |
| 8086:2043 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 87    |            | 2D1D9030E8 |
| 8086:2044 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 87    |            | 2D1D9030E8 |
| 8086:2045 | 8086:0000 | Intel      | Sky Lake-E LM Channel 1      | 87    |            | 2D1D9030E8 |
| 8086:2046 | 8086:0000 | Intel      | Sky Lake-E LMS Channel 1     | 87    | skx_uncore | 2D1D9030E8 |
| 8086:2047 | 8086:0000 | Intel      | Sky Lake-E LMDP Channel 1    | 87    |            | 2D1D9030E8 |
| 8086:2048 | 8086:0000 | Intel      | Sky Lake-E DECS Channel 2    | 87    |            | 2D1D9030E8 |
| 8086:2049 | 8086:0000 | Intel      | Sky Lake-E LM Channel 2      | 87    |            | 2D1D9030E8 |
| 8086:204a | 8086:0000 | Intel      | Sky Lake-E LMS Channel 2     | 87    | skx_uncore | 2D1D9030E8 |
| 8086:204b | 8086:0000 | Intel      | Sky Lake-E LMDP Channel 2    | 87    |            | 2D1D9030E8 |
| 8086:2054 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 87    |            | 2D1D9030E8 |
| 8086:2055 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 87    |            | 2D1D9030E8 |
| 8086:2056 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 87    |            | 2D1D9030E8 |
| 8086:2057 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 87    |            | 2D1D9030E8 |
| 8086:2066 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 87    | skx_uncore | 2D1D9030E8 |
| 8086:2080 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 87    |            | 2D1D9030E8 |
| 8086:2081 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 87    |            | 2D1D9030E8 |
| 8086:2082 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 87    |            | 2D1D9030E8 |
| 8086:2083 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 87    |            | 2D1D9030E8 |
| 8086:2084 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 87    |            | 2D1D9030E8 |
| 8086:2085 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 87    |            | 2D1D9030E8 |
| 8086:2086 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 87    |            | 2D1D9030E8 |
| 8086:208d | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 87    |            | 2D1D9030E8 |
| 8086:208e | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 87    |            | 2D1D9030E8 |
| 8086:2016 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 86    |            | 2D1D9030E8 |
| 8086:2025 |           | Intel      | Sky Lake-E RAS               | 86    |            | 2D1D9030E8 |
| 8086:2014 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 84    |            | 2D1D9030E8 |
| 8086:2034 | 8086:0000 | Intel      | Sky Lake-E VT-d              | 83    |            | 2D1D9030E8 |
| 8086:2059 | 8086:0000 | Intel      | Sky Lake-E UPI Registers     | 83    |            | 2D1D9030E8 |
| 8086:2024 | 8086:0000 | Intel      | Sky Lake-E MM/Vt-d Config... | 81    |            | 2D1D9030E8 |
| 8086:2021 | 8086:0000 | Intel      | Sky Lake-E CBDMA Registers   | 72    | ioatdma    | 2D1D9030E8 |
| 8086:2f6e |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | F90168C69D |
| 8086:2f6f |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | F90168C69D |
| 8086:2f88 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | F90168C69D |
| 8086:2f8a |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | F90168C69D |
| 8086:2fae |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | F90168C69D |
| 8086:2faf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | F90168C69D |
| 8086:2fb8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | F90168C69D |
| 8086:2fb9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | F90168C69D |
| 8086:2fba |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | F90168C69D |
| 8086:2fbb |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | F90168C69D |
| 8086:2fbe |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | F90168C69D |
| 8086:2fbf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | F90168C69D |
| 8086:2ff8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | F90168C69D |
| 8086:2ff9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 50    |            | F90168C69D |
| 8086:6f76 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 47    |            | 2F38C3FD0E |
| 8086:6f88 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 47    |            | 2F38C3FD0E |
| 8086:6f8a |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 47    |            | 2F38C3FD0E |
| 8086:6fae |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 47    |            | 2F38C3FD0E |
| 8086:6faf |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 47    |            | 2F38C3FD0E |
| 8086:6fbc |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 47    |            | 2F38C3FD0E |
| 8086:6fbd |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 47    |            | 2F38C3FD0E |
| 8086:6fbe |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 47    |            | 2F38C3FD0E |
| 8086:6fbf |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 47    |            | 2F38C3FD0E |
| 103c:3306 | 103c:3381 | Hewlett... | Integrated Lights-Out Sta... | 46    | hpwdt      | 799CC190DB |
| 103c:3307 | 103c:3381 | Hewlett... | Integrated Lights-Out Sta... | 46    | hpilo      | 799CC190DB |
| 8086:2fbc |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 44    |            | F90168C69D |
| 8086:2fbd |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 44    |            | F90168C69D |
| 8086:6f6e |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 40    |            | 2F38C3FD0E |
| 8086:6f6f |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 40    |            | 2F38C3FD0E |
| 8086:6fb8 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 40    |            | 2F38C3FD0E |
| 8086:6fb9 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 40    |            | 2F38C3FD0E |
| 8086:6fba |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 40    |            | 2F38C3FD0E |
| 8086:6fbb |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 40    |            | 2F38C3FD0E |
| 8086:2f1d | 8086:2f1d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:2f1e | 8086:2f1e | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:2f1f | 8086:2f1f | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:2f71 | 8086:2f71 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:2f81 | 8086:2f81 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:2f98 | 8086:2f98 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:2f99 | 8086:2f99 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:2f9a | 8086:2f9a | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:2f9c | 8086:2f9c | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:2fa0 | 8086:2fa0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    | sb_edac    | F90168C69D |
| 8086:2fa8 | 8086:2fa8 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:2faa | 8086:2faa | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:2fab | 8086:2fab | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:2fb0 | 8086:2fb0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    | hswep_u... | F90168C69D |
| 8086:2fb1 | 8086:2fb1 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    | hswep_u... | F90168C69D |
| 8086:2fb2 | 8086:2fb2 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:2fb3 | 8086:2fb3 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:2fc0 | 8086:2fc0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    | hswep_u... | F90168C69D |
| 8086:2fe0 | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:2fe1 | 8086:2fe1 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:2fe2 | 8086:2fe2 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:2fe3 | 8086:2fe3 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:2ffc | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:2ffd | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:2ffe | 8086:2fe0 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 35    |            | F90168C69D |
| 8086:6f68 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 34    |            | 23F12250E5 |
| 8086:6fd0 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 34    | bdx_uncore | 23F12250E5 |
| 8086:2f68 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 32    |            | 937DE612E9 |
| 8086:2fd0 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 32    | hswep_u... | 937DE612E9 |
| 8086:2fe4 | 8086:2fe4 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 32    |            | F90168C69D |
| 8086:2fe5 | 8086:2fe5 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 32    |            | F90168C69D |

### Tv card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 109e:036e |           | Brooktree  | Bt878 Video Capture          | 1     | bttv       | B55D1DAEA5 |
| 109e:036e | 0070:ff04 | Brooktree  | Bt878 Video Capture          | 1     | bttv       | 2C877CF870 |
| 109e:036e | 800a:763d | Brooktree  | Bt878 Video Capture          | 1     | bttv       | 7E72574FF4 |
| 109e:036e | 800b:763d | Brooktree  | Bt878 Video Capture          | 1     | bttv       | 7E72574FF4 |
| 109e:036e | 800c:763d | Brooktree  | Bt878 Video Capture          | 1     | bttv       | 7E72574FF4 |
| 109e:036e | 800d:763d | Brooktree  | Bt878 Video Capture          | 1     | bttv       | 7E72574FF4 |
| 14f1:8880 | 1461:d439 | Conexan... | CX23887/8 PCIe Broadcast ... | 1     |            | D8325626F2 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 103c:3300 | 103c:3381 | Hewlett... | Integrated Lights-Out Sta... | 46    | uhci_hcd   | 799CC190DB |
| 8086:1d26 | 103c:18a9 | Intel      | C600/X79 series chipset U... | 33    | ehci_pci   | 799CC190DB |
| 8086:1d2d | 103c:18a9 | Intel      | C600/X79 series chipset U... | 33    | ehci_pci   | 799CC190DB |
| 8086:3a34 | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 30    | uhci_hcd   | C56840DF98 |
| 8086:3a35 | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 30    | uhci_hcd   | C56840DF98 |
| 8086:3a36 | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 30    | uhci_hcd   | C56840DF98 |
| 8086:3a39 | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 30    | uhci_hcd   | C56840DF98 |
| 8086:3a3a | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 30    | ehci_pci   | C56840DF98 |
| 103c:3300 | 103c:3309 | Hewlett... | Integrated Lights-Out Sta... | 22    | uhci_hcd   | C56840DF98 |
| 103c:3300 | 103c:3305 | Hewlett... | Integrated Lights-Out Sta... | 21    | uhci_hcd   | FA5961B4C8 |
| 8086:a1af | 8086:35ce | Intel      | C620 Series Chipset Famil... | 19    | xhci_hcd   | D373AF93CD |
| 1912:0014 | ffff:ffff | Renesas... | uPD720201 USB 3.0 Host Co... | 16    | xhci_hcd   | 5FBC90E0CD |
| 8086:8d26 | 15d9:0821 | Intel      | C610/X99 series chipset U... | 16    | ehci_pci   | 17BF7A3CBC |
| 8086:8d2d | 15d9:0821 | Intel      | C610/X99 series chipset U... | 16    | ehci_pci   | 17BF7A3CBC |
| 8086:8d31 | 15d9:0821 | Intel      | C610/X99 series chipset U... | 16    | xhci_hcd   | 17BF7A3CBC |
| 1002:4396 | 1002:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 15    | ehci_pci   | D5563E325C |
| 1002:4399 | 1002:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 15    | ohci_pci   | D5563E325C |
| 8086:2934 | 1028:0235 | Intel      | 82801I (ICH9 Family) USB ... | 15    | uhci_hcd   | 4DEBADA4BF |
| 8086:2935 | 1028:0235 | Intel      | 82801I (ICH9 Family) USB ... | 15    | uhci_hcd   | 4DEBADA4BF |
| 8086:2937 | 1028:0235 | Intel      | 82801I (ICH9 Family) USB ... | 15    | uhci_hcd   | 4DEBADA4BF |
| 8086:2938 | 1028:0235 | Intel      | 82801I (ICH9 Family) USB ... | 15    | uhci_hcd   | 4DEBADA4BF |
| 8086:293a | 1028:0235 | Intel      | 82801I (ICH9 Family) USB2... | 15    | ehci_pci   | 4DEBADA4BF |
| 8086:293c | 1028:0235 | Intel      | 82801I (ICH9 Family) USB2... | 15    | ehci_pci   | 4DEBADA4BF |
| 8086:a1af | 8086:7270 | Intel      | C620 Series Chipset Famil... | 14    | xhci_hcd   | FD087082C0 |
| 8086:1d26 | 1043:84ef | Intel      | C600/X79 series chipset U... | 13    | ehci_pci   | A4C832AB44 |
| 8086:1d2d | 1043:84ef | Intel      | C600/X79 series chipset U... | 13    | ehci_pci   | A4C832AB44 |
| 8086:3a34 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 13    | uhci_hcd   | AFF808A68F |
| 8086:3a35 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 13    | uhci_hcd   | AFF808A68F |
| 8086:3a36 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 13    | uhci_hcd   | AFF808A68F |
| 8086:3a37 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 13    | uhci_hcd   | AFF808A68F |
| 8086:3a38 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 13    | uhci_hcd   | AFF808A68F |
| 8086:3a39 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 13    | uhci_hcd   | AFF808A68F |
| 8086:3a3a | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 13    | ehci_hcd   | AFF808A68F |
| 8086:3a3c | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 13    | ehci_hcd   | AFF808A68F |
| 8086:1d26 | 15d9:0636 | Intel      | C600/X79 series chipset U... | 12    | ehci_hcd   | DD93F62FFC |
| 8086:1d2d | 15d9:0636 | Intel      | C600/X79 series chipset U... | 12    | ehci_hcd   | DD93F62FFC |
| 1b21:1042 | 1043:8488 | ASMedia... | ASM1042 SuperSpeed USB Ho... | 11    | xhci_hcd   | A4C832AB44 |
| 8086:8d26 | 8086:7270 | Intel      | C610/X99 series chipset U... | 11    | ehci_pci   | 2F38C3FD0E |
| 8086:8d2d | 8086:7270 | Intel      | C610/X99 series chipset U... | 11    | ehci_pci   | 2F38C3FD0E |
| 8086:8d31 | 8086:7270 | Intel      | C610/X99 series chipset U... | 11    | xhci_hcd   | 2F38C3FD0E |
| 8086:2688 | 103c:31fe | Intel      | 631xESB/632xESB/3100 Chip... | 10    | uhci_hcd   | FA5961B4C8 |
| 8086:2689 | 103c:31fe | Intel      | 631xESB/632xESB/3100 Chip... | 10    | uhci_hcd   | FA5961B4C8 |
| 8086:268a | 103c:31fe | Intel      | 631xESB/632xESB/3100 Chip... | 10    | uhci_hcd   | FA5961B4C8 |
| 8086:268c | 103c:31fe | Intel      | 631xESB/632xESB/3100 Chip... | 10    | ehci_pci   | FA5961B4C8 |
| 8086:268b | 103c:31fe | Intel      | 631xESB/632xESB/3100 Chip... | 9     | uhci_hcd   | FA5961B4C8 |
| 8086:3b34 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 9     | ehci_pci   | 741DB5D841 |
| 8086:3b3c | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 9     | ehci_pci   | 741DB5D841 |
| 8086:8d26 | 103c:8030 | Intel      | C610/X99 series chipset U... | 9     | ehci_pci   | 23F12250E5 |
| 8086:8d2d | 103c:8030 | Intel      | C610/X99 series chipset U... | 9     | ehci_pci   | 23F12250E5 |
| 8086:8d31 | 103c:8030 | Intel      | C610/X99 series chipset U... | 9     | xhci_hcd   | 23F12250E5 |
| 1b21:1142 | 1b21:1142 | ASMedia... | ASM1042A USB 3.0 Host Con... | 8     | xhci_hcd   | 7CF4F8ED17 |
| 1b73:1100 | 1b73:1100 | Fresco ... | FL1100 USB 3.0 Host Contr... | 8     | xhci_hcd   | 1F6AFDC077 |
| 8086:2934 | 1028:0236 | Intel      | 82801I (ICH9 Family) USB ... | 8     | uhci_hcd   | 5FBC90E0CD |
| 8086:2935 | 1028:0236 | Intel      | 82801I (ICH9 Family) USB ... | 8     | uhci_hcd   | 5FBC90E0CD |
| 8086:2937 | 1028:0236 | Intel      | 82801I (ICH9 Family) USB ... | 8     | uhci_hcd   | 5FBC90E0CD |
| 8086:2938 | 1028:0236 | Intel      | 82801I (ICH9 Family) USB ... | 8     | uhci_hcd   | 5FBC90E0CD |
| 8086:293a | 1028:0236 | Intel      | 82801I (ICH9 Family) USB2... | 8     | ehci_pci   | 5FBC90E0CD |
| 8086:293c | 1028:0236 | Intel      | 82801I (ICH9 Family) USB2... | 8     | ehci_pci   | 5FBC90E0CD |
| 8086:1d26 | 1014:1d26 | Intel      | C600/X79 series chipset U... | 7     | ehci_pci   | 58A63B2A93 |
| 8086:1d26 | 1028:04fa | Intel      | C600/X79 series chipset U... | 7     | ehci_pci   | 1A32B081A7 |
| 8086:1d2d | 1014:1d2d | Intel      | C600/X79 series chipset U... | 7     | ehci_pci   | 58A63B2A93 |
| 8086:1d2d | 1028:04fa | Intel      | C600/X79 series chipset U... | 7     | ehci_pci   | 1A32B081A7 |
| 8086:8d26 | 1043:85f6 | Intel      | C610/X99 series chipset U... | 7     | ehci_pci   | 4158CB76EF |
| 8086:8d26 | 15d9:0857 | Intel      | C610/X99 series chipset U... | 7     | ehci_pci   | 7CF4F8ED17 |
| 8086:8d2d | 1043:85f6 | Intel      | C610/X99 series chipset U... | 7     | ehci_pci   | 4158CB76EF |
| 8086:8d2d | 15d9:0857 | Intel      | C610/X99 series chipset U... | 7     | ehci_pci   | 7CF4F8ED17 |
| 8086:8d31 | 1043:85f6 | Intel      | C610/X99 series chipset U... | 7     | xhci_hcd   | 4158CB76EF |
| 8086:8d31 | 15d9:0857 | Intel      | C610/X99 series chipset U... | 7     | xhci_hcd   | 7CF4F8ED17 |
| 8086:a1af | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     | xhci_pci   | CEE7ED2CE9 |
| 1002:4396 | 15d9:ab11 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 6     | ehci_pci   | D5563E325C |
| 1002:4397 | 15d9:ab11 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 6     | ohci_pci   | D5563E325C |
| 1002:4398 | 15d9:ab11 | AMD        | SB7x0 USB OHCI1 Controller   | 6     | ohci_pci   | D5563E325C |
| 8086:1d26 | 1028:048c | Intel      | C600/X79 series chipset U... | 6     | ehci_pci   | 4CE6A061A6 |
| 8086:1d26 | 1028:04ce | Intel      | C600/X79 series chipset U... | 6     | ehci_pci   | 7A9C742839 |
| 8086:1d2d | 1028:048c | Intel      | C600/X79 series chipset U... | 6     | ehci_pci   | 4CE6A061A6 |
| 8086:1d2d | 1028:04ce | Intel      | C600/X79 series chipset U... | 6     | ehci_pci   | 7A9C742839 |
| 8086:2934 | 8086:34d0 | Intel      | 82801I (ICH9 Family) USB ... | 6     | uhci_hcd   | FC38CA11F5 |
| 8086:2935 | 8086:34d0 | Intel      | 82801I (ICH9 Family) USB ... | 6     | uhci_hcd   | FC38CA11F5 |
| 8086:2936 | 8086:34d0 | Intel      | 82801I (ICH9 Family) USB ... | 6     | uhci_hcd   | FC38CA11F5 |
| 8086:2937 | 8086:34d0 | Intel      | 82801I (ICH9 Family) USB ... | 6     | uhci_hcd   | FC38CA11F5 |
| 8086:2938 | 8086:34d0 | Intel      | 82801I (ICH9 Family) USB ... | 6     | uhci_hcd   | FC38CA11F5 |
| 8086:293a | 8086:34d0 | Intel      | 82801I (ICH9 Family) USB2... | 6     | ehci_pci   | FC38CA11F5 |
| 8086:293c | 8086:34d0 | Intel      | 82801I (ICH9 Family) USB2... | 6     | ehci_pci   | FC38CA11F5 |
| 8086:3a34 | 1014:3a34 | Intel      | 82801JI (ICH10 Family) US... | 6     | uhci_hcd   | 2856AAF09F |
| 8086:3a34 | 1028:028c | Intel      | 82801JI (ICH10 Family) US... | 6     | uhci_hcd   | 0094B64AB2 |
| 8086:3a34 | 15d9:0400 | Intel      | 82801JI (ICH10 Family) US... | 6     | uhci_hcd   | D9ED4F04A3 |
| 8086:3a34 | 8086:34dc | Intel      | 82801JI (ICH10 Family) US... | 6     | uhci_hcd   | 61DFD26E01 |
| 8086:3a35 | 1014:3a35 | Intel      | 82801JI (ICH10 Family) US... | 6     | uhci_hcd   | 2856AAF09F |
| 8086:3a35 | 1028:028c | Intel      | 82801JI (ICH10 Family) US... | 6     | uhci_hcd   | 0094B64AB2 |
| 8086:3a35 | 15d9:0400 | Intel      | 82801JI (ICH10 Family) US... | 6     | uhci_hcd   | D9ED4F04A3 |
| 8086:3a35 | 8086:34dc | Intel      | 82801JI (ICH10 Family) US... | 6     | uhci_hcd   | 61DFD26E01 |
| 8086:3a36 | 1014:3a36 | Intel      | 82801JI (ICH10 Family) US... | 6     | uhci_hcd   | 2856AAF09F |
| 8086:3a36 | 1028:028c | Intel      | 82801JI (ICH10 Family) US... | 6     | uhci_hcd   | 0094B64AB2 |
| 8086:3a36 | 15d9:0400 | Intel      | 82801JI (ICH10 Family) US... | 6     | uhci_hcd   | D9ED4F04A3 |
| 8086:3a36 | 8086:34dc | Intel      | 82801JI (ICH10 Family) US... | 6     | uhci_hcd   | 61DFD26E01 |
| 8086:3a37 | 1014:3a37 | Intel      | 82801JI (ICH10 Family) US... | 6     | uhci_hcd   | 2856AAF09F |
| 8086:3a37 | 1028:028c | Intel      | 82801JI (ICH10 Family) US... | 6     | uhci_hcd   | 0094B64AB2 |
| 8086:3a37 | 15d9:0400 | Intel      | 82801JI (ICH10 Family) US... | 6     | uhci_hcd   | D9ED4F04A3 |
| 8086:3a37 | 8086:34dc | Intel      | 82801JI (ICH10 Family) US... | 6     | uhci_hcd   | 61DFD26E01 |
| 8086:3a38 | 1014:3a38 | Intel      | 82801JI (ICH10 Family) US... | 6     | uhci_hcd   | 2856AAF09F |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8d7c | 15d9:0821 | Intel      | C610/X99 series chipset SPSR | 16    |            | 17BF7A3CBC |
| 8086:a1ec | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    |            | 4391DFF8D2 |
| 8086:a1ec | 8086:7270 | Intel      | C620 Series Chipset Famil... | 14    |            | FD087082C0 |
| 8086:a1ed | 8086:7270 | Intel      | C620 Series Chipset Famil... | 12    |            | FD087082C0 |
| 8086:8d7c | 103c:8030 | Intel      | C610/X99 series chipset SPSR | 9     |            | 23F12250E5 |
| 8086:8d7c | 8086:7270 | Intel      | C610/X99 series chipset SPSR | 9     |            | 2F38C3FD0E |
| 8086:8d7c | 8086:0000 | Intel      | C610/X99 series chipset SPSR | 8     |            | BA0F3C3B41 |
| 8086:8d7c | 1043:85f6 | Intel      | C610/X99 series chipset SPSR | 7     |            | 4158CB76EF |
| 8086:8d7c | 15d9:0857 | Intel      | C610/X99 series chipset SPSR | 7     |            | 7CF4F8ED17 |
| 8086:a1ec | 17aa:7808 | Intel      | C620 Series Chipset Famil... | 7     |            | CEE7ED2CE9 |
| 8086:8d7c | 1028:0601 | Intel      | C610/X99 series chipset SPSR | 6     |            | F90168C69D |
| 8086:a1ec | 1043:871e | Intel      | C620 Series Chipset Famil... | 6     |            | AFAB4598A7 |
| 8086:8d7c | 15d9:0831 | Intel      | C610/X99 series chipset SPSR | 5     |            | 64918C950D |
| 8086:a1ec | 1590:00eb | Intel      | C620 Series Chipset Famil... | 5     |            | 3120E02C21 |
| 8086:a1ed | 1590:00eb | Intel      | C620 Series Chipset Famil... | 5     |            | 3120E02C21 |
| 8086:a1ec | 1028:0715 | Intel      | C620 Series Chipset Famil... | 4     |            | E9A1FC86F9 |
| 8086:a1ec | 1028:0739 | Intel      | C620 Series Chipset Famil... | 4     |            | 2D1D9030E8 |
| 8086:a1ec | 15d9:096d | Intel      | C620 Series Chipset Famil... | 4     |            | F9D0B2BC99 |
| 8086:a1ec | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 4     |            | CD543E37E2 |
| 8086:a1ed | 1028:0739 | Intel      | C620 Series Chipset Famil... | 4     |            | 2D1D9030E8 |
| 8086:a1ed | 15d9:096d | Intel      | C620 Series Chipset Famil... | 4     |            | F9D0B2BC99 |
| 8086:a1ed | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 4     |            | CD543E37E2 |
| 1912:001b | 1d49:0a02 | Renesas... | SH7758 PCIe End-Point [PBI]  | 3     |            | 3510DD7B10 |
| 8086:8d7c | 1028:0600 | Intel      | C610/X99 series chipset SPSR | 3     |            | A98D12AD3E |
| 8086:8d7c | 1458:1000 | Intel      | C610/X99 series chipset SPSR | 3     |            | 2F69A2F89C |
| 8086:8d7c | 15d9:0834 | Intel      | C610/X99 series chipset SPSR | 3     |            | FA4BECDE8B |
| 8086:8d7c | 1d49:0a00 | Intel      | C610/X99 series chipset SPSR | 3     |            | 3510DD7B10 |
| 8086:a1ec | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | E752263E49 |
| 8086:a1ec | 1028:073a | Intel      | C620 Series Chipset Famil... | 3     |            | 33FDE2B5FB |
| 8086:a1ec | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 3     |            | ED3C250112 |
| 8086:a1ec | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     |            | 7AD1F5EB4E |
| 8086:a1ec | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     |            | C682299C13 |
| 8086:a1ec | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     |            | 5658A2FB98 |
| 8086:a1ec | 1849:a1ec | Intel      | C620 Series Chipset Famil... | 3     |            | 35C171899E |
| 8086:a1ec | 8086:0000 | Intel      | C620 Series Chipset Famil... | 3     |            | D373AF93CD |
| 8086:a1ed | 1028:073a | Intel      | C620 Series Chipset Famil... | 3     |            | 33FDE2B5FB |
| 8086:a1ed | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 3     |            | ED3C250112 |
| 8086:a1ed | 15d9:0953 | Intel      | C620 Series Chipset Famil... | 3     |            | 7AD1F5EB4E |
| 8086:a1ed | 15d9:095d | Intel      | C620 Series Chipset Famil... | 3     |            | C682299C13 |
| 8086:a1ed | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 3     |            | 5658A2FB98 |
| 8086:a1ed | 1849:a1ed | Intel      | C620 Series Chipset Famil... | 3     |            | 35C171899E |
| 8086:a1ed | 8086:35ce | Intel      | C620 Series Chipset Famil... | 3     |            | D373AF93CD |
| 8086:8d7c | 1028:0639 | Intel      | C610/X99 series chipset SPSR | 2     |            | B39BBB71E2 |
| 8086:8d7c | 1028:063a | Intel      | C610/X99 series chipset SPSR | 2     |            | E4DEE6FAF7 |
| 8086:8d7c | 15d9:0824 | Intel      | C610/X99 series chipset SPSR | 2     |            | 6C96E4A591 |
| 8086:a1ec | 1028:0718 | Intel      | C620 Series Chipset Famil... | 2     |            | 1CCB5D67C2 |
| 8086:a1ec | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     |            | DF9A63BE43 |
| 8086:a1ec | 1028:07e5 | Intel      | C620 Series Chipset Famil... | 2     |            | 4C88B2E09B |
| 8086:a1ec | 103c:81c6 | Intel      | C620 Series Chipset Famil... | 2     |            | 9D6E46ECA9 |
| 8086:a1ec | 15d9:091c | Intel      | C620 Series Chipset Famil... | 2     |            | 748FB8054B |
| 8086:a1ec | 15d9:0941 | Intel      | C620 Series Chipset Famil... | 2     |            | C619DB847B |
| 8086:a1ed | 103c:81c6 | Intel      | C620 Series Chipset Famil... | 2     |            | 9D6E46ECA9 |
| 8086:a1ed | 15d9:091c | Intel      | C620 Series Chipset Famil... | 2     |            | 748FB8054B |
| 8086:a1ed | 15d9:0941 | Intel      | C620 Series Chipset Famil... | 2     |            | C619DB847B |
| 1000:fury | 1000:9341 | Broadco... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 64918C950D |
| 1000:fury | 1014:0456 | LSI Log... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 817865DED6 |
| 1000:fury | 1028:1f44 | LSI Log... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 5B9EC879FC |
| 1000:fury | 1028:1f4b | LSI Log... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | FF3ACF2BDC |
| 1a41:0200 |           | Tilera     | TILE-Gx processor            | 1     | tilegxpci  | 08100751B7 |
| 1a41:0201 |           | Tilera     | TILE-Gx Processor Virtual... | 1     |            | 08100751B7 |
| 8086:10a6 | 8086:0000 | Intel      | 82599EB 10-Gigabit Dummy ... | 1     |            | 14C76E0C83 |
| 8086:2541 | 8086:341a | Intel      | E7500/E7501 Host RASUM Co... | 1     |            | 37AA8C0E8E |
| 8086:2546 | 8086:341a | Intel      | E7500/E7501 Hub Interface... | 1     |            | 37AA8C0E8E |
| 8086:3591 | 103c:3208 | Intel      | E7525/E7520 Error Reporti... | 1     |            | 2C877CF870 |
| 8086:3591 | 8086:3439 | Intel      | E7525/E7520 Error Reporti... | 1     |            | 0F21E859FA |
| 8086:6ff2 | 8086:6ff2 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 822418675E |
| 8086:6ff3 | 8086:6ff3 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 822418675E |
| 8086:6ff4 | 8086:6ff4 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 822418675E |
| 8086:6ff5 | 8086:6ff5 | Intel      | Broadwell-E CBo Unicast R... | 1     |            | 822418675E |
| 8086:8d7c | 1028:0627 | Intel      | C610/X99 series chipset SPSR | 1     |            | 51FB8FEE00 |
| 8086:8d7c | 1028:063b | Intel      | C610/X99 series chipset SPSR | 1     |            | 031D1E0BEC |
| 8086:8d7c | 15d9:0835 | Intel      | C610/X99 series chipset SPSR | 1     |            | 7479576DA8 |
| 8086:8d7c | 15d9:0856 | Intel      | C610/X99 series chipset SPSR | 1     |            | 50EC24A7DE |
| 8086:8d7c | 15d9:0879 | Intel      | C610/X99 series chipset SPSR | 1     |            | 21124E85CC |
| 8086:8d7c | 15d9:0924 | Intel      | C610/X99 series chipset SPSR | 1     |            | 3FC4F3458F |
| 8086:8d7c | 15d9:7270 | Intel      | C610/X99 series chipset SPSR | 1     |            | 5F6D0233A8 |
| 8086:a1ec | 1028:07cb | Intel      | C620 Series Chipset Famil... | 1     |            | 5B9EC879FC |
| 8086:a1ec | 1458:5001 | Intel      | C620 Series Chipset Famil... | 1     |            | 7E93E1B694 |
| 8086:a1ec | 15d9:0962 | Intel      | C620 Series Chipset Famil... | 1     |            | 57460AA45B |
| 8086:a1ec | 15d9:096e | Intel      | C620 Series Chipset Famil... | 1     |            | 4D0ED95E02 |
| 8086:a1ec | 15d9:0986 | Intel      | C620 Series Chipset Famil... | 1     |            | 331227D869 |
| 8086:a1ec | 15d9:0987 | Intel      | C620 Series Chipset Famil... | 1     |            | 893E9D69F2 |
| 8086:a1ec | 1734:1230 | Intel      | C620 Series Chipset Famil... | 1     |            | 86AB491564 |
| 8086:a1ec | 17aa:1037 | Intel      | C620 Series Chipset Famil... | 1     |            | 41249F2E48 |
| 8086:a1ec | 17aa:7800 | Intel      | C620 Series Chipset Famil... | 1     |            | 2AE35CF194 |
| 8086:a1ed | 1458:5001 | Intel      | C620 Series Chipset Famil... | 1     |            | 7E93E1B694 |
| 8086:a1ed | 15d9:0962 | Intel      | C620 Series Chipset Famil... | 1     |            | 57460AA45B |
| 8086:a1ed | 15d9:096e | Intel      | C620 Series Chipset Famil... | 1     |            | 4D0ED95E02 |
| 8086:a1ed | 15d9:0986 | Intel      | C620 Series Chipset Famil... | 1     |            | 331227D869 |
| 8086:a1ed | 15d9:0987 | Intel      | C620 Series Chipset Famil... | 1     |            | 893E9D69F2 |
| 8086:a1ed | 1734:1230 | Intel      | C620 Series Chipset Famil... | 1     |            | 86AB491564 |
| 8086:a1ed | 17aa:1037 | Intel      | C620 Series Chipset Famil... | 1     |            | 41249F2E48 |
| 8086:a1ed | 8086:a1ed | Intel      | C620 Series Chipset Famil... | 1     |            | F823B40D84 |

