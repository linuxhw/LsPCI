Most popular PCI devices in Servers
===================================

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Servers ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Firewire controller ](#firewire-controller-pci)
   * [ Generic system peripheral ](#generic-system-peripheral-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Input device controller ](#input-device-controller-pci)
   * [ Iommu ](#iommu-pci)
   * [ Ipmi smic interface ](#ipmi-smic-interface-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Multimedia controller ](#multimedia-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Non-vga unclassified device ](#non-vga-unclassified-device-pci)
   * [ Performance counters ](#performance-counters-pci)
   * [ Pic (8259) ](#pic-8259-pci)
   * [ Pic (io(x)-apic) ](#pic-iox-apic-pci)
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

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1a03:1150 | 1a03:1150 | ASPEED ... | AST1150 PCI-to-PCI Bridge    | 33    | shpchp     | 8E73F804F5 |
| 8086:2030 | 8086:0000 | Intel      | Sky Lake-E PCI Express Ro... | 27    | pcieport   | 8E73F804F5 |
| 8086:244e |           | Intel      | 82801 PCI Bridge             | 24    | shpchp     | 25731D395E |
| 8086:2020 | 8086:0000 | Intel      | Sky Lake-E DMI3 Registers    | 23    |            | 4391DFF8D2 |
| 8086:2032 | 8086:0000 | Intel      | Sky Lake-E PCI Express Ro... | 21    | pcieport   | 8E73F804F5 |
| 8086:2c70 | 8086:8086 | Intel      | Xeon 5600 Series QuickPat... | 21    |            | 726EA75DCA |
| 8086:2d81 | 8086:8086 | Intel      | Xeon 5600 Series QuickPat... | 21    |            | 726EA75DCA |
| 8086:2d90 | 8086:8086 | Intel      | Xeon 5600 Series QPI Link 0  | 21    |            | 726EA75DCA |
| 8086:2d91 | 8086:8086 | Intel      | Xeon 5600 Series QPI Phys... | 21    |            | 726EA75DCA |
| 8086:2d92 | 8086:8086 | Intel      | Xeon 5600 Series Mirror P... | 21    |            | 726EA75DCA |
| 8086:2d93 | 8086:8086 | Intel      | Xeon 5600 Series Mirror P... | 21    |            | 726EA75DCA |
| 8086:2d94 | 8086:8086 | Intel      | Xeon 5600 Series QPI Link 1  | 21    |            | 726EA75DCA |
| 8086:2d95 | 8086:8086 | Intel      | Xeon 5600 Series QPI Phys... | 21    |            | 726EA75DCA |
| 8086:2d98 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 21    |            | 726EA75DCA |
| 8086:2d99 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 21    |            | 726EA75DCA |
| 8086:2d9a | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 21    |            | 726EA75DCA |
| 8086:2d9c | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 21    |            | 726EA75DCA |
| 8086:2da0 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 21    |            | 726EA75DCA |
| 8086:2da1 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 21    |            | 726EA75DCA |
| 8086:2da2 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 21    |            | 726EA75DCA |
| 8086:2da3 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 21    |            | 726EA75DCA |
| 8086:2da8 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 21    |            | 726EA75DCA |
| 8086:2da9 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 21    |            | 726EA75DCA |
| 8086:2daa | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 21    |            | 726EA75DCA |
| 8086:2dab | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 21    |            | 726EA75DCA |
| 8086:2db0 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 21    |            | 726EA75DCA |
| 8086:2db1 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 21    |            | 726EA75DCA |
| 8086:2db2 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 21    |            | 726EA75DCA |
| 8086:2db3 | 8086:8086 | Intel      | Xeon 5600 Series Integrat... | 21    |            | 726EA75DCA |
| 8086:37c0 | 8086:0000 | Intel      | PCI bridge                   | 18    | pcieport   | 8E73F804F5 |
| 1a03:1150 | 15d9:0821 | ASPEED ... | AST1150 PCI-to-PCI Bridge    | 16    | shpchp     | 17BF7A3CBC |
| 8086:6f00 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6f02 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | shpchp     | 17BF7A3CBC |
| 8086:6f04 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | shpchp     | 17BF7A3CBC |
| 8086:6f08 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | shpchp     | 17BF7A3CBC |
| 8086:8d10 | 15d9:0821 | Intel      | C610/X99 series chipset P... | 16    | shpchp     | 17BF7A3CBC |
| 8086:8d18 | 15d9:0821 | Intel      | C610/X99 series chipset P... | 16    | shpchp     | 17BF7A3CBC |
| 8086:8d44 | 15d9:0821 | Intel      | C610/X99 series chipset L... | 16    | lpc_ich    | 17BF7A3CBC |
| 8086:a190 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    | pcieport   | 4391DFF8D2 |
| 8086:a194 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    | pcieport   | 4391DFF8D2 |
| 8086:a196 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    | pcieport   | 4391DFF8D2 |
| 8086:a198 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    | pcieport   | 4391DFF8D2 |
| 8086:a19c | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    | pcieport   | 4391DFF8D2 |
| 8086:a1c1 | 8086:35ce | Intel      | C621 Series Chipset LPC/e... | 16    | lpc_ich    | 4391DFF8D2 |
| 8086:244e | 15d9:0006 | Intel      | 82801 PCI Bridge             | 11    |            | 726EA75DCA |
| 8086:3403 | 15d9:0006 | Intel      | 5500 I/O Hub to ESI Port     | 11    |            | 726EA75DCA |
| 8086:3408 | 15d9:0006 | Intel      | 5520/5500/X58 I/O Hub PCI... | 11    | shpchp     | 726EA75DCA |
| 8086:340a | 15d9:0006 | Intel      | 5520/5500/X58 I/O Hub PCI... | 11    | shpchp     | 726EA75DCA |
| 8086:340e | 15d9:0006 | Intel      | 5520/5500/X58 I/O Hub PCI... | 11    | shpchp     | 726EA75DCA |
| 8086:3410 | 15d9:0006 | Intel      | 7500/5520/5500/X58 I/O Hu... | 11    | shpchp     | 726EA75DCA |
| 8086:3a16 | 15d9:0006 | Intel      | 82801JIR (ICH10R) LPC Int... | 11    | lpc_ich    | 726EA75DCA |
| 8086:3a40 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) PC... | 11    | shpchp     | 726EA75DCA |
| 8086:3a48 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) PC... | 11    | shpchp     | 726EA75DCA |
| 8086:3a4a | 15d9:0006 | Intel      | 82801JI (ICH10 Family) PC... | 11    | shpchp     | 726EA75DCA |
| 8086:1d10 |           | Intel      | C600/X79 series chipset P... | 10    | shpchp     | F65EC09250 |
| 8086:1d1e |           | Intel      | C600/X79 series chipset P... | 10    | shpchp     | F65EC09250 |
| 8086:3408 |           | Intel      | 5520/5500/X58 I/O Hub PCI... | 10    | shpchp     | 4AD2087A83 |
| 8086:340a |           | Intel      | 5520/5500/X58 I/O Hub PCI... | 10    | shpchp     | 4AD2087A83 |
| 8086:340e |           | Intel      | 5520/5500/X58 I/O Hub PCI... | 10    | shpchp     | 4AD2087A83 |
| 8086:3410 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 10    | shpchp     | 4AD2087A83 |
| 8086:1d3e |           | Intel      | C600/X79 series chipset P... | 9     | shpchp     | 100EFA1F4A |
| 8086:1d10 | 103c:18a9 | Intel      | C600/X79 series chipset P... | 8     | shpchp     | 07278BAD4B |
| 8086:1d1e | 103c:18a9 | Intel      | C600/X79 series chipset P... | 8     | shpchp     | 07278BAD4B |
| 8086:1d3e | 103c:18a9 | Intel      | C600/X79 series chipset P... | 8     | shpchp     | 07278BAD4B |
| 8086:1d41 |           | Intel      | C600/X79 series chipset L... | 8     | lpc_ich    | 07278BAD4B |
| 8086:244e | 103c:18a9 | Intel      | 82801 PCI Bridge             | 8     |            | 07278BAD4B |
| 8086:2c01 | 8086:8086 | Intel      | Xeon 5500/Core i7 QuickPa... | 8     |            | 09FB58BF8D |
| 8086:2c10 | 8086:8086 | Intel      | Xeon 5500/Core i7 QPI Link 0 | 8     |            | 09FB58BF8D |
| 8086:2c11 | 8086:8086 | Intel      | Xeon 5500/Core i7 QPI Phy... | 8     |            | 09FB58BF8D |
| 8086:2c14 | 8086:8086 | Intel      | Xeon 5500/Core i7 QPI Link 1 | 8     |            | 09FB58BF8D |
| 8086:2c15 | 8086:8086 | Intel      | Xeon 5500/Core i7 QPI Phy... | 8     |            | 09FB58BF8D |
| 8086:2c18 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 8     |            | 09FB58BF8D |
| 8086:2c19 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 8     |            | 09FB58BF8D |
| 8086:2c1a | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 8     |            | 09FB58BF8D |
| 8086:2c1c | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 8     |            | 09FB58BF8D |
| 8086:2c20 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 8     |            | 09FB58BF8D |
| 8086:2c21 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 8     |            | 09FB58BF8D |
| 8086:2c22 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 8     |            | 09FB58BF8D |
| 8086:2c23 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 8     |            | 09FB58BF8D |
| 8086:2c28 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 8     |            | 09FB58BF8D |
| 8086:2c29 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 8     |            | 09FB58BF8D |
| 8086:2c2a | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 8     |            | 09FB58BF8D |
| 8086:2c2b | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 8     |            | 09FB58BF8D |
| 8086:2c30 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 8     |            | 09FB58BF8D |
| 8086:2c31 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 8     |            | 09FB58BF8D |
| 8086:2c32 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 8     |            | 09FB58BF8D |
| 8086:2c33 | 8086:8086 | Intel      | Xeon 5500/Core i7 Integra... | 8     |            | 09FB58BF8D |
| 8086:2c40 | 8086:8086 | Intel      | Xeon 5500/Core i7 QuickPa... | 8     |            | 09FB58BF8D |
| 8086:3418 |           | Intel      | 7500/5520/5500/X58 Physic... | 8     |            | 6806624961 |
| 8086:3419 |           | Intel      | 7500/5520/5500 Physical L... | 8     |            | 6806624961 |
| 8086:341a |           | Intel      | 7500/5520/5500/X58 Unknown   | 8     |            | 6806624961 |
| 8086:341c |           | Intel      | 7500/5520/5500/X58 Unknown   | 8     |            | 6806624961 |
| 8086:341d |           | Intel      | 7500/5520/5500/X58 Unknown   | 8     |            | 6806624961 |
| 8086:341e |           | Intel      | 7500/5520/5500/X58 Unknown   | 8     |            | 6806624961 |
| 8086:3439 |           | Intel      | 7500/5520/5500/X58 Unknown   | 8     |            | 6806624961 |
| 8086:343a |           | Intel      | 7500/5520/5500/X58 Unknown   | 8     |            | 6806624961 |
| 8086:343b |           | Intel      | 7500/5520/5500/X58 Unknown   | 8     |            | 6806624961 |
| 8086:343c |           | Intel      | 7500/5520/5500/X58 Unknown   | 8     |            | 6806624961 |
| 8086:343d |           | Intel      | 7500/5520/5500/X58 Unknown   | 8     |            | 6806624961 |
| 8086:3a40 |           | Intel      | 82801JI (ICH10 Family) PC... | 8     | shpchp     | 4AD2087A83 |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:37c8 | 8086:0000 | Intel      | C62x Chipset QuickAssist ... | 1     |            | F8D0599716 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8d3a | 15d9:0821 | Intel      | C610/X99 series chipset M... | 16    | mei_me     | 17BF7A3CBC |
| 8086:8d3b | 15d9:0821 | Intel      | C610/X99 series chipset M... | 16    |            | 17BF7A3CBC |
| 8086:a1ba | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    | mei_me     | 4391DFF8D2 |
| 8086:a1be | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    |            | 4391DFF8D2 |
| 8086:a1bb | 8086:35ce | Intel      | C620 Series Chipset Famil... | 15    |            | 5B11F4C63C |
| 8086:a1ba | 8086:7270 | Intel      | C620 Series Chipset Famil... | 5     | mei_me     | 8E73F804F5 |
| 8086:a1be | 8086:7270 | Intel      | C620 Series Chipset Famil... | 5     |            | 8E73F804F5 |
| 8086:a1bb | 8086:7270 | Intel      | C620 Series Chipset Famil... | 4     |            | 8E73F804F5 |
| 8086:1d3a | 1043:84ef | Intel      | C600/X79 series chipset M... | 3     | mei_me     | 996F55BB36 |
| 8086:1d3a | 15d9:0636 | Intel      | C600/X79 series chipset M... | 3     |            | 100EFA1F4A |
| 8086:1d3a | 8086:357e | Intel      | C600/X79 series chipset M... | 3     | mei_me     | F65EC09250 |
| 8086:1d3b | 1043:84ef | Intel      | C600/X79 series chipset M... | 3     |            | 996F55BB36 |
| 8086:1d3b | 15d9:0636 | Intel      | C600/X79 series chipset M... | 3     |            | 100EFA1F4A |
| 8086:1d3b | 8086:357e | Intel      | C600/X79 series chipset M... | 3     |            | F65EC09250 |
| 8086:8d3a | 1028:0601 | Intel      | C610/X99 series chipset M... | 3     | mei_me     | AF9F6ACE3F |
| 8086:8d3a | 8086:7270 | Intel      | C610/X99 series chipset M... | 3     | mei_me     | 7658F21E98 |
| 8086:8d3b | 1028:0601 | Intel      | C610/X99 series chipset M... | 3     |            | AF9F6ACE3F |
| 8086:8d3b | 8086:7270 | Intel      | C610/X99 series chipset M... | 3     |            | 7658F21E98 |
| 8086:8d3a | 15d9:0824 | Intel      | C610/X99 series chipset M... | 2     | mei_me     | 6C96E4A591 |
| 8086:8d3a | 15d9:0831 | Intel      | C610/X99 series chipset M... | 2     | mei_me     | 52D5275C7F |
| 8086:8d3b | 15d9:0824 | Intel      | C610/X99 series chipset M... | 2     |            | 6C96E4A591 |
| 8086:8d3b | 15d9:0831 | Intel      | C610/X99 series chipset M... | 2     |            | 52D5275C7F |
| 8086:1d3a | 1028:048c | Intel      | C600/X79 series chipset M... | 1     | mei_me     | B6374DF09A |
| 8086:1d3a | 1028:04f8 | Intel      | C600/X79 series chipset M... | 1     | mei_me     | A1EFBB1BE1 |
| 8086:1d3a | 15d9:0665 | Intel      | C600/X79 series chipset M... | 1     | mei_me     | CEC82EF5D0 |
| 8086:1d3a | 15d9:070a | Intel      | C600/X79 series chipset M... | 1     | mei_me     | B4C8ABC585 |
| 8086:1d3b | 1028:048c | Intel      | C600/X79 series chipset M... | 1     |            | B6374DF09A |
| 8086:1d3b | 1028:04f8 | Intel      | C600/X79 series chipset M... | 1     |            | A1EFBB1BE1 |
| 8086:1d3b | 15d9:0665 | Intel      | C600/X79 series chipset M... | 1     |            | CEC82EF5D0 |
| 8086:1d3b | 15d9:070a | Intel      | C600/X79 series chipset M... | 1     |            | B4C8ABC585 |
| 8086:8c3a | 15d9:0805 | Intel      | 8 Series/C220 Series Chip... | 1     | mei_me     | 3F6EE4141E |
| 8086:8c3a | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 1     |            | DB25C87154 |
| 8086:8c3b | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 1     |            | DB25C87154 |
| 8086:8d3a | 1028:0639 | Intel      | C610/X99 series chipset M... | 1     | mei_me     | 3BA1B5FC84 |
| 8086:8d3a | 1028:063a | Intel      | C610/X99 series chipset M... | 1     | mei_me     | FF3ACF2BDC |
| 8086:8d3a | 1043:85f6 | Intel      | C610/X99 series chipset M... | 1     | mei_me     | FD500E59D6 |
| 8086:8d3a | 15d9:0834 | Intel      | C610/X99 series chipset M... | 1     | mei_me     | EEE6327556 |
| 8086:8d3a | 15d9:0835 | Intel      | C610/X99 series chipset M... | 1     | mei_me     | 7479576DA8 |
| 8086:8d3a | 1d49:0a00 | Intel      | C610/X99 series chipset M... | 1     | mei_me     | 817865DED6 |
| 8086:8d3a | 8086:35c5 | Intel      | C610/X99 series chipset M... | 1     |            | 08100751B7 |
| 8086:8d3a | 8086:35c9 | Intel      | C610/X99 series chipset M... | 1     |            | 5F9F099F36 |
| 8086:8d3b | 1028:0639 | Intel      | C610/X99 series chipset M... | 1     |            | 3BA1B5FC84 |
| 8086:8d3b | 1028:063a | Intel      | C610/X99 series chipset M... | 1     |            | FF3ACF2BDC |
| 8086:8d3b | 1043:85f6 | Intel      | C610/X99 series chipset M... | 1     |            | FD500E59D6 |
| 8086:8d3b | 15d9:0834 | Intel      | C610/X99 series chipset M... | 1     |            | EEE6327556 |
| 8086:8d3b | 15d9:0835 | Intel      | C610/X99 series chipset M... | 1     |            | 7479576DA8 |
| 8086:8d3b | 1d49:0a00 | Intel      | C610/X99 series chipset M... | 1     |            | 817865DED6 |
| 8086:8d3b | 8086:35c5 | Intel      | C610/X99 series chipset M... | 1     |            | 08100751B7 |
| 8086:8d3b | 8086:35c9 | Intel      | C610/X99 series chipset M... | 1     |            | 5F9F099F36 |
| 8086:a13a | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | C74A66C7E6 |
| 8086:a13a | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | BB8832ACBD |
| 8086:a13a | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | 5372999434 |
| 8086:a13a | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | C392838A14 |
| 8086:a13a | 1734:1222 | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | 0BD7D9FCEA |
| 8086:a13a | 8086:1999 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 13B41B547A |
| 8086:a13b | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | C74A66C7E6 |
| 8086:a13b | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | BB8832ACBD |
| 8086:a13b | 8086:1999 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 13B41B547A |
| 8086:a1ba | 1028:0718 | Intel      | C620 Series Chipset Famil... | 1     | mei_me     | 97313ACF09 |
| 8086:a1ba | 1028:0739 | Intel      | C620 Series Chipset Famil... | 1     | mei_me     | AD29AF92C2 |
| 8086:a1ba | 1028:07cb | Intel      | C620 Series Chipset Famil... | 1     | mei_me     | 5B9EC879FC |
| 8086:a1ba | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 1     | mei_me     | 0617E49F12 |
| 8086:a1ba | 1043:871e | Intel      | C620 Series Chipset Famil... | 1     | mei_me     | A1916FC246 |
| 8086:a1ba | 1590:00eb | Intel      | C620 Series Chipset Famil... | 1     | mei_me     | 9E91D0ED19 |
| 8086:a1ba | 15d9:095d | Intel      | C620 Series Chipset Famil... | 1     | mei_me     | 2794B14FEE |
| 8086:a1ba | 15d9:096d | Intel      | C620 Series Chipset Famil... | 1     | mei_me     | DCFB9EE48A |
| 8086:a1ba | 15d9:0987 | Intel      | C620 Series Chipset Famil... | 1     | mei_me     | 893E9D69F2 |
| 8086:a1ba | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 1     | mei_me     | ED799888EB |
| 8086:a1bb | 1028:0718 | Intel      | C620 Series Chipset Famil... | 1     |            | 97313ACF09 |
| 8086:a1bb | 1028:07cb | Intel      | C620 Series Chipset Famil... | 1     |            | 5B9EC879FC |
| 8086:a1bb | 1043:871e | Intel      | C620 Series Chipset Famil... | 1     |            | A1916FC246 |
| 8086:a1bb | 15d9:095d | Intel      | C620 Series Chipset Famil... | 1     |            | 2794B14FEE |
| 8086:a1bb | 15d9:096d | Intel      | C620 Series Chipset Famil... | 1     |            | DCFB9EE48A |
| 8086:a1bb | 15d9:0987 | Intel      | C620 Series Chipset Famil... | 1     |            | 893E9D69F2 |
| 8086:a1be | 1028:0718 | Intel      | C620 Series Chipset Famil... | 1     |            | 97313ACF09 |
| 8086:a1be | 1028:07cb | Intel      | C620 Series Chipset Famil... | 1     |            | 5B9EC879FC |
| 8086:a1be | 1043:871e | Intel      | C620 Series Chipset Famil... | 1     |            | A1916FC246 |
| 8086:a1be | 1590:00eb | Intel      | C620 Series Chipset Famil... | 1     |            | 9E91D0ED19 |
| 8086:a1be | 15d9:095d | Intel      | C620 Series Chipset Famil... | 1     |            | 2794B14FEE |
| 8086:a1be | 15d9:096d | Intel      | C620 Series Chipset Famil... | 1     |            | DCFB9EE48A |
| 8086:a1be | 15d9:0987 | Intel      | C620 Series Chipset Famil... | 1     |            | 893E9D69F2 |
| 8086:a2ba | 15d9:098e | Intel      | 200 Series PCH CSME HECI #1  | 1     | mei_me     | 98ED2C77C7 |
| 8086:a328 | 15d9:1a1d | Intel      | 300 Series Chipset Device    | 1     | intel_l... | 21E2FBBB75 |
| 8086:a360 | 15d9:1a1d | Intel      | Cannon Lake PCH HECI Cont... | 1     | mei_me     | 21E2FBBB75 |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 2     |            | 4B4029781F |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 104c:8023 | 15d9:0100 | Texas I... | TSB43AB22A IEEE-1394a-200... | 1     | firewir... | 68E0C84652 |
| 104c:8023 | 15d9:0805 | Texas I... | TSB43AB22A IEEE-1394a-200... | 1     | firewir... | 3F6EE4141E |
| 104c:823f | 3412:7856 | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 1     | firewir... | 21E2FBBB75 |
| 1102:4001 | 1102:0010 | Creativ... | SB Audigy FireWire Port      | 1     | firewir... | 138B84322E |
| 1106:3044 | 108e:534d | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 1     | firewir... | 1F35F79302 |
| 1106:3044 | 1106:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 1     | firewir... | CC8DB94EBA |
| 1106:3403 | 1043:8384 | VIA Tec... | VT6315 Series Firewire Co... | 1     | firewir... | 90D8E62525 |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:5a23 | 1002:5a23 | AMD        | RD890S/RD990 I/O Memory M... | 1     |            | 7E28DD35AD |
| 1022:1577 | 1022:1577 | AMD        | Family 15h (Models 60h-6f... | 1     |            | 1E87C9E765 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1a03:2000 | 1a03:2000 | ASPEED ... | ASPEED Graphics Family       | 25    | ast        | 8E73F804F5 |
| 1a03:2000 | 15d9:0821 | ASPEED ... | ASPEED Graphics Family       | 16    | ast        | 17BF7A3CBC |
| 10de:1eba | 10de:0000 | Nvidia     | 3D controller                | 15    | nvidia     | 4391DFF8D2 |
| 102b:0533 | 103c:3381 | Matrox ... | MGA G200EH                   | 13    | mgag200    | 140DAF886E |
| 102b:0532 | 15d9:0006 | Matrox ... | MGA G200eW WPCM450           | 11    | mgag200    | 726EA75DCA |
| 1002:515e | 103c:31fb | AMD        | ES1000                       | 6     | radeon     | 6806624961 |
| 102b:0522 | 8086:0103 | Matrox ... | MGA G200e [Pilot] ServerE... | 6     | mgag200    | 5F9F099F36 |
| 102b:0522 | 8086:0101 | Matrox ... | MGA G200e [Pilot] ServerE... | 5     | mgag200    | CBBE408AAC |
| 102b:0532 | 15d9:060f | Matrox ... | MGA G200eW WPCM450           | 4     | mgag200    | 1D3C1DC3BF |
| 102b:0530 | 1014:0369 | Matrox ... | MGA G200EV                   | 3     | mgag200    | D804E1DA52 |
| 102b:0532 | 1028:0235 | Matrox ... | MGA G200eW WPCM450           | 3     | mgag200    | ABCF5C7050 |
| 102b:0534 | 1028:0601 | Matrox ... | G200eR2                      | 3     | mgag200    | AF9F6ACE3F |
| 102b:0534 | 15d9:0636 | Matrox ... | G200eR2                      | 3     |            | 100EFA1F4A |
| 1002:515e | 1028:01b2 | AMD        | ES1000                       | 2     | radeon     | 1C2A92612A |
| 1002:9874 | 1002:1871 | AMD        | Wani [Radeon R5/R6/R7 Gra... | 2     | amdgpu     | 4B4029781F |
| 102b:0522 | 8086:0102 | Matrox ... | MGA G200e [Pilot] ServerE... | 2     | mgag200    | DAA63A315C |
| 102b:0532 | 1028:04de | Matrox ... | MGA G200eW WPCM450           | 2     | mgag200    | 389DD308F7 |
| 102b:0534 | 1014:0405 | Matrox ... | G200eR2                      | 2     | mgag200    | B55F7AE6F3 |
| 10de:1287 | 1043:84f5 | Nvidia     | GK208B [GeForce GT 730]      | 2     | nvidia     | D05461EFDA |
| 10de:13c2 | 1043:8508 | Nvidia     | GM204 [GeForce GTX 970]      | 2     | nvidia     | 22AA6FF795 |
| 1a03:2000 | 15d9:0824 | ASPEED ... | ASPEED Graphics Family       | 2     | ast        | 6C96E4A591 |
| 1a03:2000 | 15d9:0831 | ASPEED ... | ASPEED Graphics Family       | 2     | ast        | 52D5275C7F |
| 1002:4752 | 1014:0240 | AMD        | Rage 3 [Rage XL PCI]         | 1     |            | 46973B5B05 |
| 1002:4752 | 103c:3208 | AMD        | Rage 3 [Rage XL PCI]         | 1     |            | 2C877CF870 |
| 1002:4752 | 8086:3439 | AMD        | Rage 3 [Rage XL PCI]         | 1     |            | 0F21E859FA |
| 1002:5159 | 1028:016e | AMD        | RV100 [Radeon 7000 / Rade... | 1     | radeon     | 76EF1C8CA9 |
| 1002:515e | 1028:01b3 | AMD        | ES1000                       | 1     | radeon     | 25731D395E |
| 1002:515e | 1028:0205 | AMD        | ES1000                       | 1     |            | B7596E9C0E |
| 1002:515e | 8086:3476 | AMD        | ES1000                       | 1     | radeon     | 5229FAFC3E |
| 1002:515e | 8086:3484 | AMD        | ES1000                       | 1     | radeon     | 5C3DF14DAD |
| 1002:6704 | 1002:0b00 | AMD        | Cayman PRO GL [FirePro V7... | 1     | radeon     | 7F6C6E8DE0 |
| 1002:6704 | 1028:2b0c | AMD        | Cayman PRO GL [FirePro V7... | 1     | radeon     | C7E9D74C3D |
| 1002:674a | 1002:0106 | AMD        | Turks GL [FirePro V3900]     | 1     | radeon     | 5372999434 |
| 1002:6779 | 1462:8090 | AMD        | Caicos [Radeon HD 6450/74... | 1     | radeon     | 138B84322E |
| 1002:6780 | 1002:031e | AMD        | Tahiti XT GL [FirePro W9000] | 1     | radeon     | CEC82EF5D0 |
| 1002:67df | 1043:0517 | AMD        | Ellesmere [Radeon RX 470/... | 1     |            | A8A3023830 |
| 1002:67df | 1da2:e366 | AMD        | Ellesmere [Radeon RX 470/... | 1     | amdgpu     | F65EC09250 |
| 1002:6811 | 148c:2337 | AMD        | Curacao PRO [Radeon R7 37... | 1     | radeon     | 726EA75DCA |
| 1002:683d | 1043:043b | AMD        | Cape Verde XT [Radeon HD ... | 1     | radeon     | 3F6EE4141E |
| 1002:68ba | 1043:03fe | AMD        | Juniper XT [Radeon HD 6770]  | 1     | radeon     | 7E28DD35AD |
| 1002:68d9 | 1462:2150 | AMD        | Redwood PRO [Radeon HD 55... | 1     | radeon     | 53D66D8AB3 |
| 1002:7300 | 1002:0b36 | AMD        | Fiji [Radeon R9 FURY / NA... | 1     | amdgpu     | 98ED2C77C7 |
| 1002:9440 | 1787:2267 | AMD        | RV770 [Radeon HD 4870]       | 1     | radeon     | 7092025B53 |
| 102b:0522 | 103c:0100 | Matrox ... | MGA G200e [Pilot] ServerE... | 1     | mgag200    | 7CE46A749E |
| 102b:0522 | 1734:11cc | Matrox ... | MGA G200e [Pilot] ServerE... | 1     |            | D092DEFE79 |
| 102b:0532 | 1028:0236 | Matrox ... | MGA G200eW WPCM450           | 1     | mgag200    | 21EEA2083D |
| 102b:0532 | 1028:0237 | Matrox ... | MGA G200eW WPCM450           | 1     | mgag200    | 3F4700F256 |
| 102b:0532 | 1028:028c | Matrox ... | MGA G200eW WPCM450           | 1     | mgag200    | 8E139BB972 |
| 102b:0532 | 1028:02a3 | Matrox ... | MGA G200eW WPCM450           | 1     |            | 0F9D97BC71 |
| 102b:0532 | 1028:02a4 | Matrox ... | MGA G200eW WPCM450           | 1     | mgag200    | 4D09E718D8 |
| 102b:0532 | 1028:02d3 | Matrox ... | MGA G200eW WPCM450           | 1     | mgag200    | F33CE0F316 |
| 102b:0532 | 1028:02f1 | Matrox ... | MGA G200eW WPCM450           | 1     | mgag200    | CBFB7C31D8 |
| 102b:0532 | 1028:04dd | Matrox ... | MGA G200eW WPCM450           | 1     | mgag200    | 3A05F2F446 |
| 102b:0532 | 15d9:0001 | Matrox ... | MGA G200eW WPCM450           | 1     | mgag200    | CC8DB94EBA |
| 102b:0532 | 15d9:0100 | Matrox ... | MGA G200eW WPCM450           | 1     | mgag200    | 68E0C84652 |
| 102b:0532 | 15d9:0600 | Matrox ... | MGA G200eW WPCM450           | 1     | mgag200    | 8C854FDF21 |
| 102b:0532 | 15d9:070a | Matrox ... | MGA G200eW WPCM450           | 1     |            | B4C8ABC585 |
| 102b:0532 | 15d9:ab11 | Matrox ... | MGA G200eW WPCM450           | 1     | mgag200    | 463CF097DA |
| 102b:0532 | 15d9:bc11 | Matrox ... | MGA G200eW WPCM450           | 1     | mgag200    | 7E28DD35AD |
| 102b:0534 | 1028:048c | Matrox ... | G200eR2                      | 1     | mgag200    | B6374DF09A |
| 102b:0534 | 1028:04f8 | Matrox ... | G200eR2                      | 1     | mgag200    | A1EFBB1BE1 |
| 102b:0534 | 1028:0639 | Matrox ... | G200eR2                      | 1     | mgag200    | 3BA1B5FC84 |
| 102b:0534 | 1028:063a | Matrox ... | G200eR2                      | 1     | mgag200    | FF3ACF2BDC |
| 102b:0534 | 1028:06aa | Matrox ... | G200eR2                      | 1     | mgag200    | C74A66C7E6 |
| 102b:0534 | 15d9:0665 | Matrox ... | G200eR2                      | 1     | mgag200    | CEC82EF5D0 |
| 102b:0534 | 1d49:0a01 | Matrox ... | G200eR2                      | 1     |            | 817865DED6 |
| 102b:0536 | 1028:0718 | Matrox ... | Integrated Matrox G200eW3... | 1     | mgag200    | 97313ACF09 |
| 102b:0536 | 1028:07cb | Matrox ... | Integrated Matrox G200eW3... | 1     | mgag200    | 5B9EC879FC |
| 102b:0538 | 1590:00e4 | Matrox ... | MGA G200eH3                  | 1     | mgag200    | 9E91D0ED19 |
| 10de:0422 | 1682:2308 | Nvidia     | G86 [GeForce 8400 GS]        | 1     | nouveau    | 9A27511AEB |
| 10de:042f | 10de:0493 | Nvidia     | G86 [Quadro NVS 290]         | 1     | nouveau    | ABCF5C7050 |
| 10de:0a65 | 1462:8094 | Nvidia     | GT218 [GeForce 210]          | 1     | nouveau    | 1F35F79302 |
| 10de:0fc6 | 19da:1294 | Nvidia     | GK107 [GeForce GTX 650]      | 1     | nvidia     | 50527E087E |
| 10de:0ffa | 10de:094b | Nvidia     | GK107GL [Quadro K600]        | 1     |            | 90D8E62525 |
| 10de:10c3 | 3842:1301 | Nvidia     | GT218 [GeForce 8400 GS Re... | 1     | nouveau    | 21E2FBBB75 |
| 10de:1187 | 3842:3769 | Nvidia     | GK104 [GeForce GTX 760]      | 1     | nvidia     | CC8DB94EBA |
| 10de:11b4 | 10de:1096 | Nvidia     | GK104GL [Quadro K4200]       | 1     | nvidia     | FD500E59D6 |
| 10de:11c0 | 1043:8423 | Nvidia     | GK106 [GeForce GTX 660]      | 1     | nouveau    | 7115F8FDB7 |
| 10de:11c6 | 1043:842a | Nvidia     | GK106 [GeForce GTX 650 Ti]   | 1     | nouveau    | 6DE12619B5 |
| 10de:128b | 19da:5360 | Nvidia     | GK208B [GeForce GT 710]      | 1     | nouveau    | D9F1CB21BC |
| 10de:15f7 | 10de:11da | Nvidia     | GP100GL [Tesla P100 PCIe ... | 1     | nvidia     | 7658F21E98 |
| 10de:1b00 | 10de:119a | Nvidia     | GP102 [TITAN X]              | 1     | nvidia     | 7658F21E98 |
| 10de:1b80 | 1043:85aa | Nvidia     | GP104 [GeForce GTX 1080]     | 1     | nvidia     | F8D0599716 |
| 10de:1b80 | 1458:3702 | Nvidia     | GP104 [GeForce GTX 1080]     | 1     | nvidia     | 996F55BB36 |
| 10de:1b81 | 1043:8597 | Nvidia     | GP104 [GeForce GTX 1070]     | 1     |            | 90D8E62525 |
| 10de:1bb0 | 10de:11b2 | Nvidia     | GP104GL [Quadro P5000]       | 1     | nouveau    | ED799888EB |
| 10de:1bb1 | 103c:11a3 | Nvidia     | GP104GL [Quadro P4000]       | 1     | nouveau    | 0617E49F12 |
| 10de:1c81 | 1458:3765 | Nvidia     | GP107 [GeForce GTX 1050]     | 1     | nouveau    | A1916FC246 |
| 10de:1c82 | 1043:8613 | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 1     | nvidia     | 09FB58BF8D |
| 10de:1c82 | 10de:0000 | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 1     | nvidia     | DEC98C8F86 |
| 10de:1cb2 | 10de:11bd | Nvidia     | GP107GL [Quadro P600]        | 1     | nvidia     | 8681056F1F |
| 10de:1cb6 | 1028:1264 | Nvidia     | GP107GL [Quadro P620]        | 1     |            | AD29AF92C2 |
| 10de:1db4 | 10de:1214 | Nvidia     | GV100GL [Tesla V100 PCIe ... | 1     | nouveau    | 97313ACF09 |
| 10de:1e04 | 19da:2503 | Nvidia     | TU102 [GeForce RTX 2080 Ti]  | 1     | nvidia     | 8E73F804F5 |
| 1a03:2000 | 1043:8373 | ASPEED ... | ASPEED Graphics Family       | 1     | ast        | 833ACDFC5E |
| 1a03:2000 | 1043:84eb | ASPEED ... | ASPEED Graphics Family       | 1     | ast        | 67F26A64DE |
| 1a03:2000 | 1043:8544 | ASPEED ... | ASPEED Graphics Family       | 1     | ast        | B3CC6B4BAD |
| 1a03:2000 | 1043:85f9 | ASPEED ... | ASPEED Graphics Family       | 1     | ast        | FD500E59D6 |
| 1a03:2000 | 1043:86ed | ASPEED ... | ASPEED Graphics Family       | 1     | ast        | A1916FC246 |
| 1a03:2000 | 1170:0047 | ASPEED ... | ASPEED Graphics Family       | 1     | ast        | 9762DCCBE9 |

### Input device controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1102:7003 | 1102:0040 | Creativ... | SB Audigy Game Port          | 1     | Emu10k1... | 138B84322E |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:5a23 | 103c:3324 | AMD        | RD890S/RD990 I/O Memory M... | 1     |            | 7CE46A749E |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 103c:3302 | 103c:3305 | Hewlett... | Integrated Lights-Out Sta... | 3     | ipmi_si    | 6806624961 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a1a1 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    |            | 4391DFF8D2 |
| 8086:a1a1 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 5     |            | 8E73F804F5 |
| 1590:005f | 1590:005f | Hewlett... | Memory controller            | 2     |            | 3FAC52AF81 |
| 10de:0369 | 108e:534d | Nvidia     | MCP55 Memory Controller      | 1     |            | 1F35F79302 |
| 8086:a121 | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     |            | C74A66C7E6 |
| 8086:a121 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 1     |            | BB8832ACBD |
| 8086:a121 | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 5372999434 |
| 8086:a121 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     |            | C392838A14 |
| 8086:a121 | 1734:1222 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 0BD7D9FCEA |
| 8086:a121 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 13B41B547A |
| 8086:a1a1 | 1028:0718 | Intel      | C620 Series Chipset Famil... | 1     |            | 97313ACF09 |
| 8086:a1a1 | 1028:0739 | Intel      | C620 Series Chipset Famil... | 1     |            | AD29AF92C2 |
| 8086:a1a1 | 1028:07cb | Intel      | C620 Series Chipset Famil... | 1     |            | 5B9EC879FC |
| 8086:a1a1 | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 1     |            | 0617E49F12 |
| 8086:a1a1 | 1043:871e | Intel      | C620 Series Chipset Famil... | 1     |            | A1916FC246 |
| 8086:a1a1 | 1590:00eb | Intel      | C620 Series Chipset Famil... | 1     |            | 9E91D0ED19 |
| 8086:a1a1 | 15d9:095d | Intel      | C620 Series Chipset Famil... | 1     |            | 2794B14FEE |
| 8086:a1a1 | 15d9:096d | Intel      | C620 Series Chipset Famil... | 1     |            | DCFB9EE48A |
| 8086:a1a1 | 15d9:0987 | Intel      | C620 Series Chipset Famil... | 1     |            | 893E9D69F2 |
| 8086:a1a1 | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 1     |            | ED799888EB |
| 8086:a2a1 | 15d9:098e | Intel      | 200 Series/Z370 Chipset F... | 1     |            | 98ED2C77C7 |
| 8086:a36f | 8086:7270 | Intel      | Cannon Lake PCH Shared SRAM  | 1     |            | 21E2FBBB75 |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 109e:0878 | 0070:ff04 | Brooktree  | Bt878 Audio Capture          | 1     |            | 2C877CF870 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:15b9 | 8086:0000 | Intel      | Ethernet Connection (3) I... | 17    | e1000e     | 4391DFF8D2 |
| 8086:10fb | 108e:7b11 | Intel      | 82599ES 10-Gigabit SFI/SF... | 9     | ixgbe      | 5A96F790B1 |
| 14e4:1639 | 103c:7055 | Broadco... | NetXtreme II BCM5709 Giga... | 7     | bnx2       | 6806624961 |
| 8086:1572 | 8086:0000 | Intel      | Ethernet Controller X710 ... | 5     | i40e       | 57FC9BDF47 |
| 14e4:1639 | 1028:0235 | Broadcom   | NetXtreme II BCM5709 Giga... | 3     | bnx2       | ABCF5C7050 |
| 14e4:1657 | 103c:22be | Broadco... | NetXtreme BCM5719 Gigabit... | 3     | tg3        | C9D389B2A3 |
| 8086:1076 | 8086:34d0 | Intel      | 82541GI Gigabit Ethernet ... | 3     | e1000      | 9A27511AEB |
| 8086:10fb | 8086:0003 | Intel      | 82599ES 10-Gigabit SFI/SF... | 3     | ixgbe      | 17BF7A3CBC |
| 8086:1521 | 103c:337f | Intel      | I350 Gigabit Network Conn... | 3     | igb        | 140DAF886E |
| 8086:1521 | 103c:3380 | Intel      | I350 Gigabit Network Conn... | 3     | igb        | BA2F9FC714 |
| 8086:1572 | 8086:0001 | Intel      | Ethernet Controller X710 ... | 3     | i40e       | 57FC9BDF47 |
| 8086:37d2 | 15d9:37d2 | Intel      | Ethernet Connection X722 ... | 3     | i40e       | 8E73F804F5 |
| 14e4:1639 | 1014:03a9 | Broadco... | NetXtreme II BCM5709 Giga... | 2     | bnx2       | D804E1DA52 |
| 14e4:164c | 1028:01b2 | Broadco... | NetXtreme II BCM5708 Giga... | 2     | bnx2       | 1C2A92612A |
| 14e4:1657 | 103c:169d | Broadcom   | NetXtreme BCM5719 Gigabit... | 2     | tg3        | 4805EBBD1F |
| 14e4:165a | 1028:04de | Broadco... | NetXtreme BCM5722 Gigabit... | 2     | tg3        | 389DD308F7 |
| 14e4:165f | 103c:22e8 | Broadco... | NetXtreme BCM5720 2-port ... | 2     | tg3        | 4B4029781F |
| 14e4:168e | 103c:193a | Broadcom   | NetXtreme II BCM57810 10 ... | 2     | bnx2x      | B7B182E812 |
| 8086:150e | 103c:1780 | Intel      | 82580 Gigabit Network Con... | 2     | igb        | 6806624961 |
| 8086:1521 | 8086:0002 | Intel      | I350 Gigabit Network Conn... | 2     | igb        | 5372999434 |
| 8086:1572 | 8086:0005 | Intel      | Ethernet Controller X710 ... | 2     | i40e       | 351F393121 |
| 8086:15b7 | 15d9:15b7 | Intel      | Ethernet Connection (2) I... | 2     | e1000e     | C392838A14 |
| 8086:37d1 | 15d9:37d1 | Intel      | Ethernet Connection X722 ... | 2     | i40e       | 2794B14FEE |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | B3CC6B4BAD |
| 10ec:8168 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 3F4700F256 |
| 10ec:8168 | 7470:3468 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | CBBE408AAC |
| 11ab:4361 | 8086:3439 | Marvell... | 88E8050 PCI-E ASF Gigabit... | 1     | sky2       | 0F21E859FA |
| 14e4:1639 | 1028:0236 | Broadco... | NetXtreme II BCM5709 Giga... | 1     | bnx2       | 21EEA2083D |
| 14e4:1639 | 1028:0237 | Broadco... | NetXtreme II BCM5709 Giga... | 1     | bnx2       | 3F4700F256 |
| 14e4:1639 | 1028:02d3 | Broadco... | NetXtreme II BCM5709 Giga... | 1     | bnx2       | F33CE0F316 |
| 14e4:163b | 1028:028c | Broadco... | NetXtreme II BCM5716 Giga... | 1     | bnx2       | 8E139BB972 |
| 14e4:163b | 1028:02a3 | Broadco... | NetXtreme II BCM5716 Giga... | 1     | bnx2       | 0F9D97BC71 |
| 14e4:163b | 1028:02a4 | Broadco... | NetXtreme II BCM5716 Giga... | 1     | bnx2       | 4D09E718D8 |
| 14e4:163b | 1028:02f1 | Broadco... | NetXtreme II BCM5716 Giga... | 1     | bnx2       | CBFB7C31D8 |
| 14e4:163b | 1028:04dd | Broadco... | NetXtreme II BCM5716 Giga... | 1     | bnx2       | 3A05F2F446 |
| 14e4:164c | 1028:01b3 | Broadco... | NetXtreme II BCM5708 Giga... | 1     | bnx2       | 25731D395E |
| 14e4:164c | 1028:0205 | Broadco... | NetXtreme II BCM5708 Giga... | 1     | bnx2       | B7596E9C0E |
| 14e4:1657 | 17aa:400e | Broadco... | NetXtreme BCM5719 Gigabit... | 1     | tg3        | 817865DED6 |
| 14e4:1659 | 103c:1659 | Broadco... | NetXtreme BCM5721 Gigabit... | 1     | tg3        | 2C877CF870 |
| 14e4:165f | 1028:000a | Broadco... | NetXtreme BCM5720 2-port ... | 1     | tg3        | 5B9EC879FC |
| 14e4:165f | 1028:04f8 | Broadco... | NetXtreme BCM5720 2-port ... | 1     | tg3        | A1EFBB1BE1 |
| 14e4:165f | 1028:0639 | Broadco... | NetXtreme BCM5720 2-port ... | 1     | tg3        | 3BA1B5FC84 |
| 14e4:165f | 1028:06a7 | Broadco... | NetXtreme BCM5720 2-port ... | 1     | tg3        | C74A66C7E6 |
| 14e4:165f | 1028:1f5b | Broadco... | NetXtreme BCM5720 2-port ... | 1     | tg3        | B6374DF09A |
| 14e4:165f | 14e4:2003 | Broadco... | NetXtreme BCM5720 2-port ... | 1     | tg3        | 5B9EC879FC |
| 14e4:16a2 | 103c:22fa | Broadco... | BCM57840 NetXtreme II 10/... | 1     | bnx2x      | 9E91D0ED19 |
| 14e4:16a7 | 1014:026f | Broadco... | NetXtreme BCM5703X Gigabi... | 1     | tg3        | 46973B5B05 |
| 1d6a:d108 | 15d9:d108 | Aquantia   | AQC108 NBase-T/IEEE 802.3... | 1     | atlantic   | 98ED2C77C7 |
| 8086:105e | 8086:135e | Intel      | 82571EB/82571GB Gigabit E... | 1     | e1000e     | F170BEEE88 |
| 8086:1076 | 1028:016d | Intel      | 82541GI Gigabit Ethernet ... | 1     | e1000      | 76EF1C8CA9 |
| 8086:1076 | 8086:3439 | Intel      | 82541GI Gigabit Ethernet ... | 1     | e1000      | 0F21E859FA |
| 8086:107d | 8086:1084 | Intel      | 82572EI Gigabit Ethernet ... | 1     | e1000e     | 4D09E718D8 |
| 8086:1096 | 8086:3476 | Intel      | 80003ES2LAN Gigabit Ether... | 1     | e1000e     | 5229FAFC3E |
| 8086:1096 | 8086:3484 | Intel      | 80003ES2LAN Gigabit Ether... | 1     | e1000e     | 5C3DF14DAD |
| 8086:10aa | 8086:0000 | Intel      | Ethernet controller          | 1     |            | CBBE408AAC |
| 8086:10bc | 8086:11bc | Intel      | 82571EB/82571GB Gigabit E... | 1     | e1000e     | C7E9D74C3D |
| 8086:10f8 | 103c:17d2 | Intel      | 82599 10 Gigabit Dual Por... | 1     | ixgbe      | 9E91D0ED19 |
| 8086:10f8 | 103c:18d0 | Intel      | 82599 10 Gigabit Dual Por... | 1     | ixgbe      | 9036136416 |
| 8086:10fb | 8086:7a11 | Intel      | 82599ES 10-Gigabit SFI/SF... | 1     | ixgbe      | B55F7AE6F3 |
| 8086:1521 | 103c:17d1 | Intel      | I350 Gigabit Network Conn... | 1     | igb        | 07278BAD4B |
| 8086:1521 | 8086:0001 | Intel      | I350 Gigabit Network Conn... | 1     | igb        | 21E2FBBB75 |
| 8086:1521 | 8086:5002 | Intel      | I350 Gigabit Network Conn... | 1     | igb        | FF3ACF2BDC |
| 8086:1528 | 8086:0002 | Intel      | Ethernet Controller 10-Gi... | 1     | ixgbe      | 5372999434 |
| 8086:1528 | 8086:35c5 | Intel      | Ethernet Controller 10-Gi... | 1     | ixgbe      | 08100751B7 |
| 8086:1528 | 8086:35c9 | Intel      | Ethernet Controller 10-Gi... | 1     | ixgbe      | 5F9F099F36 |
| 8086:1533 | 103c:0003 | Intel      | I210 Gigabit Network Conn... | 1     | igb        | 0617E49F12 |
| 8086:153a | 15d9:153a | Intel      | Ethernet Connection I217-LM  | 1     | e1000e     | 3F6EE4141E |
| 8086:1563 | 15d9:1563 | Intel      | Ethernet Controller 10G X... | 1     | ixgbe      | DCFB9EE48A |
| 8086:15ac | 15d9:15ac | Intel      | Ethernet Connection X552 ... | 1     | ixgbe      | DB25C87154 |
| 8086:15b7 | 1734:121f | Intel      | Ethernet Connection (2) I... | 1     | e1000e     | 0BD7D9FCEA |
| 8086:15b9 | 1028:0739 | Intel      | Ethernet Connection (3) I... | 1     | e1000e     | AD29AF92C2 |
| 8086:15b9 | 103c:81c7 | Intel      | Ethernet Connection (3) I... | 1     | e1000e     | 0617E49F12 |
| 8086:15b9 | 17aa:1038 | Intel      | Ethernet Connection (3) I... | 1     | e1000e     | ED799888EB |
| 8086:15bb | 15d9:15bb | Intel      | Ethernet Connection (7) I... | 1     | e1000e     | 21E2FBBB75 |
| 8086:37cc | 103c:81c7 | Intel      | Ethernet Connection X722     | 1     |            | 0617E49F12 |
| 8086:37cc | 15d9:0000 | Intel      | Ethernet Connection X722     | 1     |            | 2794B14FEE |
| 8086:37d0 | 8086:0000 | Intel      | Ethernet Connection X722 ... | 1     | i40e       | F8D0599716 |
| 8086:37d1 | 103c:81c7 | Intel      | Ethernet Connection X722 ... | 1     | i40e       | 0617E49F12 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:43a0 | 14e4:0619 | Broadco... | BCM4360 802.11ac Wireless... | 2     | wl         | CC8DB94EBA |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1521 | 15d9:1521 | Intel      | I350 Gigabit Network Conn... | 27    | igb        | B4C8ABC585 |
| 8086:1533 | 15d9:1533 | Intel      | I210 Gigabit Network Conn... | 12    | igb        | D05461EFDA |
| 8086:10d3 | 15d9:10d3 | Intel      | 82574L Gigabit Network Co... | 11    | e1000e     | 726EA75DCA |
| 8086:10d3 | 1043:8369 | Intel      | 82574L Gigabit Network Co... | 6     | e1000e     | AB7179BE16 |
| 8086:10c9 | 15d9:060f | Intel      | 82576 Gigabit Network Con... | 4     | igb        | 1D3C1DC3BF |
| 8086:1521 | 1028:1f60 | Intel      | I350 Gigabit Network Conn... | 4     | igb        | AF9F6ACE3F |
| 8086:1533 | 1043:8557 | Intel      | I210 Gigabit Network Conn... | 4     | igb        | FD500E59D6 |
| 8086:10a7 | 8086:34dc | Intel      | 82575EB Gigabit Network C... | 3     | igb        | 138B84322E |
| 8086:10bd | 8086:34d0 | Intel      | 82566DM-2 Gigabit Network... | 3     | e1000e     | 9A27511AEB |
| 8086:10c9 | 15d9:0100 | Intel      | 82576 Gigabit Network Con... | 3     | igb        | 8C854FDF21 |
| 8086:1521 | 8086:357e | Intel      | I350 Gigabit Network Conn... | 3     | igb        | F65EC09250 |
| 8086:10c9 | 15d9:10c9 | Intel      | 82576 Gigabit Network Con... | 2     | igb        | CC8DB94EBA |
| 8086:10cc | 8086:34da | Intel      | 82567LM-2 Gigabit Network... | 2     | e1000e     | DEC98C8F86 |
| 8086:10d3 | 8086:34da | Intel      | 82574L Gigabit Network Co... | 2     | e1000e     | DEC98C8F86 |
| 8086:10d3 | 8086:3578 | Intel      | 82574L Gigabit Network Co... | 2     | e1000e     | DAA63A315C |
| 8086:1502 | 8086:3578 | Intel      | 82579LM Gigabit Network C... | 2     | e1000e     | DAA63A315C |
| 10de:0373 | 108e:534d | Nvidia     | MCP55 Ethernet               | 1     | forcedeth  | 1F35F79302 |
| 14e4:164f | 1028:02d3 | Broadco... | NetXtreme II BCM57711 10-... | 1     | bnx2x      | F33CE0F316 |
| 15b3:1017 | 15b3:0007 | Mellano... | MT27800 Family [ConnectX-5]  | 1     | mlx5_core  | F823B40D84 |
| 15b3:673c | 15b3:0022 | Mellano... | MT25408A0-FCC-QI ConnectX... | 1     | mlx4_core  | 179B0500B3 |
| 15b3:673c | 15b3:0033 | Mellano... | MT25408A0-FCC-QI ConnectX... | 1     | mlx4_core  | 179B0500B3 |
| 15b3:6750 | 15b3:0021 | Mellano... | MT26448 [ConnectX EN 10Gi... | 1     | mlx4_core  | 98ED2C77C7 |
| 19a2:0710 | 10df:e70a | Emulex     | OneConnect 10Gb NIC (be3)    | 1     | be2net     | D7CBC31CEE |
| 8086:10c9 | 103c:323f | Intel      | 82576 Gigabit Network Con... | 1     | igb        | 7CE46A749E |
| 8086:10c9 | 10f1:7012 | Intel      | 82576 Gigabit Network Con... | 1     | igb        | 3D4DABE8D3 |
| 8086:10c9 | 1170:004a | Intel      | 82576 Gigabit Network Con... | 1     | igb        | 9762DCCBE9 |
| 8086:10c9 | 15d9:ab11 | Intel      | 82576 Gigabit Network Con... | 1     | igb        | 463CF097DA |
| 8086:10c9 | 8086:a04c | Intel      | 82576 Gigabit Network Con... | 1     | igb        | 0F9D97BC71 |
| 8086:10d3 | 1014:03bd | Intel      | 82574L Gigabit Network Co... | 1     | e1000e     | E53A957D3F |
| 8086:10d3 | 10f1:7012 | Intel      | 82574L Gigabit Network Co... | 1     | e1000e     | 3D4DABE8D3 |
| 8086:10d3 | 1734:1158 | Intel      | 82574L Gigabit Network Co... | 1     | e1000e     | C7E9D74C3D |
| 8086:10d3 | 1734:1192 | Intel      | 82574L Gigabit Network Co... | 1     | e1000e     | D092DEFE79 |
| 8086:10d3 | 8086:0000 | Intel      | 82574L Gigabit Network Co... | 1     | e1000e     | A8A3023830 |
| 8086:10d3 | 8086:34ec | Intel      | 82574L Gigabit Network Co... | 1     | e1000e     | 6DE12619B5 |
| 8086:10e8 | 8086:a02b | Intel      | 82576 Gigabit Network Con... | 1     | igb        | 3A05F2F446 |
| 8086:10ef | 8086:34ec | Intel      | 82578DM Gigabit Network C... | 1     | e1000e     | 6DE12619B5 |
| 8086:10fb | 15d9:0611 | Intel      | 82599ES 10-Gigabit SFI/SF... | 1     | ixgbe      | B4C8ABC585 |
| 8086:1502 | 1734:11b7 | Intel      | 82579LM Gigabit Network C... | 1     | e1000e     | D092DEFE79 |
| 8086:1521 |           | Intel      | I350 Gigabit Network Conn... | 1     | igb        | EDE05678EF |
| 8086:1521 | 1043:84ec | Intel      | I350 Gigabit Network Conn... | 1     | igb        | 996F55BB36 |
| 8086:1521 | 8086:1521 | Intel      | I350 Gigabit Network Conn... | 1     | igb        | B55F7AE6F3 |
| 8086:1521 | ffff:0000 | Intel      | I350 Gigabit Network Conn... | 1     | igb        | EDE05678EF |
| 8086:1533 | 17aa:1038 | Intel      | I210 Gigabit Network Conn... | 1     | igb        | ED799888EB |
| 8086:1533 | 8086:35bd | Intel      | I210 Gigabit Network Conn... | 1     | igb        | 13B41B547A |
| 8086:1533 | ffff:0000 | Intel      | I210 Gigabit Network Conn... | 1     | igb        | F823B40D84 |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a135 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 1     |            | BB8832ACBD |

### Performance counters (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2015 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 29    |            | 8E73F804F5 |
| 8086:204c | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 29    | skx_uncore | 8E73F804F5 |
| 8086:204d | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 29    | skx_uncore | 8E73F804F5 |
| 8086:2058 | 8086:0000 | Intel      | Sky Lake-E KTI 0             | 27    | skx_uncore | 8E73F804F5 |
| 8086:2088 | 8086:0000 | Intel      | Sky Lake-E DDRIO Registers   | 17    | skx_uncore | 0234D26806 |
| 8086:6f30 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6f34 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6f36 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6f37 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6f7d | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6f32 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 15    | bdx_uncore | 17BF7A3CBC |
| 8086:6f33 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 15    | bdx_uncore | 17BF7A3CBC |
| 8086:2f30 | 8086:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 13    | hswep_u... | D05461EFDA |
| 8086:2f34 | 8086:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 13    | hswep_u... | D05461EFDA |
| 8086:2f36 | 8086:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 13    | hswep_u... | D05461EFDA |
| 8086:2f37 | 8086:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 13    | hswep_u... | D05461EFDA |
| 8086:2f7d | 8086:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 13    |            | D05461EFDA |
| 8086:2f32 | 8086:2f32 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 7     | hswep_u... | AF9F6ACE3F |
| 8086:2f33 | 8086:2f33 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 6     | hswep_u... | AF9F6ACE3F |
| 8086:0e30 | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     | ivbep_u... | 100EFA1F4A |
| 8086:0e34 | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     | ivbep_u... | 100EFA1F4A |
| 8086:0e36 | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     | ivbep_u... | 100EFA1F4A |
| 8086:2f30 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     | hswep_u... | C9D389B2A3 |
| 8086:2f34 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     | hswep_u... | C9D389B2A3 |
| 8086:2f36 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     | hswep_u... | C9D389B2A3 |
| 8086:2f37 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     | hswep_u... | C9D389B2A3 |
| 8086:2f7d | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     |            | C9D389B2A3 |
| 8086:6f30 | 8086:6f30 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     | bdx_uncore | 3BA1B5FC84 |
| 8086:6f34 | 8086:6f34 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     | bdx_uncore | 3BA1B5FC84 |
| 8086:6f36 | 8086:6f36 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     | bdx_uncore | 3BA1B5FC84 |
| 8086:6f37 | 8086:6f37 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     | bdx_uncore | 3BA1B5FC84 |
| 8086:6f7d | 8086:6f7d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     |            | 3BA1B5FC84 |
| 8086:0e30 | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     | ivbep_u... | 07278BAD4B |
| 8086:0e34 | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     | ivbep_u... | 07278BAD4B |
| 8086:0e36 | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     | ivbep_u... | 07278BAD4B |
| 8086:2f30 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     | hswep_u... | 52D5275C7F |
| 8086:2f34 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     | hswep_u... | 52D5275C7F |
| 8086:2f36 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     | hswep_u... | 52D5275C7F |
| 8086:2f37 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     | hswep_u... | 52D5275C7F |
| 8086:2f38 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     |            | B7B182E812 |
| 8086:2f38 | 8086:2f38 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     | hswep_u... | AF9F6ACE3F |
| 8086:2f7d | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     |            | 52D5275C7F |
| 8086:3c43 | 103c:18a8 | Intel      | Xeon E5/Core i7 Ring to P... | 2     | snbep_u... | 4805EBBD1F |
| 8086:3c43 | 1043:84f0 | Intel      | Xeon E5/Core i7 Ring to P... | 2     | snbep_u... | 996F55BB36 |
| 8086:3c43 | 8086:357e | Intel      | Xeon E5/Core i7 Ring to P... | 2     | snbep_u... | F65EC09250 |
| 8086:3c44 | 103c:18a8 | Intel      | Xeon E5/Core i7 Ring to Q... | 2     | snbep_u... | 4805EBBD1F |
| 8086:3c44 | 1043:84f0 | Intel      | Xeon E5/Core i7 Ring to Q... | 2     | snbep_u... | 996F55BB36 |
| 8086:3c44 | 8086:357e | Intel      | Xeon E5/Core i7 Ring to Q... | 2     | snbep_u... | F65EC09250 |
| 8086:3c46 | 103c:18a8 | Intel      | Xeon E5/Core i7 Processor... | 2     | snbep_u... | 4805EBBD1F |
| 8086:3c46 | 1043:84f0 | Intel      | Xeon E5/Core i7 Processor... | 2     | snbep_u... | 996F55BB36 |
| 8086:3c46 | 8086:357e | Intel      | Xeon E5/Core i7 Processor... | 2     | snbep_u... | F65EC09250 |
| 8086:3ce6 | 103c:18a8 | Intel      | Xeon E5/Core i7 QuickPath... | 2     |            | 4805EBBD1F |
| 8086:3ce6 | 1043:84f0 | Intel      | Xeon E5/Core i7 QuickPath... | 2     |            | 996F55BB36 |
| 8086:3ce6 | 8086:357e | Intel      | Xeon E5/Core i7 QuickPath... | 2     |            | F65EC09250 |
| 8086:6f30 | 15d9:0824 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     | bdx_uncore | 6C96E4A591 |
| 8086:6f32 | 15d9:0824 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     | bdx_uncore | 6C96E4A591 |
| 8086:6f33 | 15d9:0824 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     | bdx_uncore | 6C96E4A591 |
| 8086:6f34 | 15d9:0824 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     | bdx_uncore | 6C96E4A591 |
| 8086:6f36 | 15d9:0824 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     | bdx_uncore | 6C96E4A591 |
| 8086:6f37 | 15d9:0824 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     | bdx_uncore | 6C96E4A591 |
| 8086:6f7d | 15d9:0824 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 6C96E4A591 |
| 8086:0e30 |           | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | B55F7AE6F3 |
| 8086:0e30 | 1028:048c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | B6374DF09A |
| 8086:0e30 | 1028:04f8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | A1EFBB1BE1 |
| 8086:0e30 | 1043:84f0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 90D8E62525 |
| 8086:0e30 | 15d9:0665 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | CEC82EF5D0 |
| 8086:0e30 | 15d9:070a | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | B4C8ABC585 |
| 8086:0e30 | 8086:357e | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 018029FB72 |
| 8086:0e32 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | B55F7AE6F3 |
| 8086:0e33 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | B55F7AE6F3 |
| 8086:0e34 | 1028:048c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | B6374DF09A |
| 8086:0e34 | 1028:04f8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | A1EFBB1BE1 |
| 8086:0e34 | 1043:84f0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 90D8E62525 |
| 8086:0e34 | 15d9:0665 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | CEC82EF5D0 |
| 8086:0e34 | 15d9:070a | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | B4C8ABC585 |
| 8086:0e34 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | B55F7AE6F3 |
| 8086:0e34 | 8086:357e | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 018029FB72 |
| 8086:0e36 | 1028:048c | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | B6374DF09A |
| 8086:0e36 | 1028:04f8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | A1EFBB1BE1 |
| 8086:0e36 | 1043:84f0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 90D8E62525 |
| 8086:0e36 | 15d9:0665 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | CEC82EF5D0 |
| 8086:0e36 | 15d9:070a | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | B4C8ABC585 |
| 8086:0e36 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | B55F7AE6F3 |
| 8086:0e36 | 8086:357e | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 018029FB72 |
| 8086:0e37 | 8086:0000 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | B55F7AE6F3 |
| 8086:0e37 | 8086:357e | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | 018029FB72 |
| 8086:0e38 |           | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ivbep_u... | B55F7AE6F3 |
| 8086:2015 | 1590:00ea | Intel      | Sky Lake-E Ubox Registers    | 1     |            | 9E91D0ED19 |
| 8086:2015 | 17aa:1038 | Intel      | Sky Lake-E Ubox Registers    | 1     |            | ED799888EB |
| 8086:2015 | 8086:2015 | Intel      | Sky Lake-E Ubox Registers    | 1     |            | F823B40D84 |
| 8086:204c | 1590:00ea | Intel      | Sky Lake-E M3KTI Registers   | 1     | skx_uncore | 9E91D0ED19 |
| 8086:204c | 17aa:1038 | Intel      | Sky Lake-E M3KTI Registers   | 1     | skx_uncore | ED799888EB |
| 8086:204c | 8086:204c | Intel      | Sky Lake-E M3KTI Registers   | 1     | skx_uncore | F823B40D84 |
| 8086:204d | 1590:00ea | Intel      | Sky Lake-E M3KTI Registers   | 1     | skx_uncore | 9E91D0ED19 |
| 8086:204d | 17aa:1038 | Intel      | Sky Lake-E M3KTI Registers   | 1     | skx_uncore | ED799888EB |
| 8086:204d | 8086:204d | Intel      | Sky Lake-E M3KTI Registers   | 1     | skx_uncore | F823B40D84 |
| 8086:2058 | 1590:00ea | Intel      | Sky Lake-E KTI 0             | 1     | skx_uncore | 9E91D0ED19 |
| 8086:2058 | 17aa:1038 | Intel      | Sky Lake-E KTI 0             | 1     | skx_uncore | ED799888EB |
| 8086:2058 | 8086:2058 | Intel      | Sky Lake-E KTI 0             | 1     | skx_uncore | F823B40D84 |
| 8086:2f32 | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     | hswep_u... | F0EB4348F0 |

### Pic (8259) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:342e |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 32    | i7core_... | 726EA75DCA |
| 8086:3422 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 30    |            | 726EA75DCA |
| 8086:3423 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 30    |            | 726EA75DCA |
| 8086:3438 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 22    | i5500_temp | 726EA75DCA |
| 8086:3422 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     |            | 6806624961 |
| 8086:3423 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     |            | 6806624961 |
| 8086:342e | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     | i7core_... | 6806624961 |
| 8086:3422 | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     |            | 138B84322E |
| 8086:3423 | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     |            | 138B84322E |
| 8086:3425 | 0086:00dc | Intel      | 7500/5520/5500/X58 Physic... | 3     |            | 138B84322E |
| 8086:3426 | 0086:00dc | Intel      | 7500/5520/5500/X58 Routin... | 3     |            | 138B84322E |
| 8086:3427 | 0086:00dc | Intel      | 7500/5520/5500 Physical a... | 3     |            | 138B84322E |
| 8086:3428 | 0086:00dc | Intel      | 7500/5520/5500 Routing & ... | 3     |            | 138B84322E |
| 8086:342e | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     | i7core_... | 138B84322E |
| 8086:3438 | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     | i5500_temp | 138B84322E |
| 8086:3422 | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     |            | DEC98C8F86 |
| 8086:3423 | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     |            | DEC98C8F86 |
| 8086:3425 |           | Intel      | 7500/5520/5500/X58 Physic... | 2     |            | D804E1DA52 |
| 8086:3425 | 0086:00da | Intel      | 7500/5520/5500/X58 Physic... | 2     |            | DEC98C8F86 |
| 8086:3426 |           | Intel      | 7500/5520/5500/X58 Routin... | 2     |            | D804E1DA52 |
| 8086:3426 | 0086:00da | Intel      | 7500/5520/5500/X58 Routin... | 2     |            | DEC98C8F86 |
| 8086:3427 |           | Intel      | 7500/5520/5500 Physical a... | 2     |            | D804E1DA52 |
| 8086:3427 | 0086:00da | Intel      | 7500/5520/5500 Physical a... | 2     |            | DEC98C8F86 |
| 8086:3428 |           | Intel      | 7500/5520/5500 Routing & ... | 2     |            | D804E1DA52 |
| 8086:3428 | 0086:00da | Intel      | 7500/5520/5500 Routing & ... | 2     |            | DEC98C8F86 |
| 8086:342e | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     | i7core_... | DEC98C8F86 |
| 8086:3438 | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     | i5500_temp | DEC98C8F86 |
| 8086:3422 | 0034:0027 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | C7E9D74C3D |
| 8086:3422 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | 8681056F1F |
| 8086:3422 | 0086:0000 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | CBBE408AAC |
| 8086:3423 | 0034:0027 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | C7E9D74C3D |
| 8086:3423 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | 8681056F1F |
| 8086:3423 | 0086:0000 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | CBBE408AAC |
| 8086:3425 | 0034:0027 | Intel      | 7500/5520/5500/X58 Physic... | 1     |            | C7E9D74C3D |
| 8086:3425 | 0043:0063 | Intel      | 7500/5520/5500/X58 Physic... | 1     |            | 8681056F1F |
| 8086:3425 | 0086:0000 | Intel      | 7500/5520/5500/X58 Physic... | 1     |            | CBBE408AAC |
| 8086:3426 | 0034:0027 | Intel      | 7500/5520/5500/X58 Routin... | 1     |            | C7E9D74C3D |
| 8086:3426 | 0043:0063 | Intel      | 7500/5520/5500/X58 Routin... | 1     |            | 8681056F1F |
| 8086:3426 | 0086:0000 | Intel      | 7500/5520/5500/X58 Routin... | 1     |            | CBBE408AAC |
| 8086:3427 | 0034:0027 | Intel      | 7500/5520/5500 Physical a... | 1     |            | C7E9D74C3D |
| 8086:3427 | 0043:0063 | Intel      | 7500/5520/5500 Physical a... | 1     |            | 8681056F1F |
| 8086:3427 | 0086:0000 | Intel      | 7500/5520/5500 Physical a... | 1     |            | CBBE408AAC |
| 8086:3428 | 0034:0027 | Intel      | 7500/5520/5500 Routing & ... | 1     |            | C7E9D74C3D |
| 8086:3428 | 0043:0063 | Intel      | 7500/5520/5500 Routing & ... | 1     |            | 8681056F1F |
| 8086:3428 | 0086:0000 | Intel      | 7500/5520/5500 Routing & ... | 1     |            | CBBE408AAC |
| 8086:342e | 0034:0027 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     | i7core_... | C7E9D74C3D |
| 8086:342e | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     | i7core_... | 8681056F1F |
| 8086:342e | 0086:0000 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     | i7core_... | CBBE408AAC |
| 8086:3438 | 0034:0027 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     | i5500_temp | C7E9D74C3D |
| 8086:3438 | 0043:0063 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     | i5500_temp | 8681056F1F |
| 8086:3438 | 0086:0000 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     | i5500_temp | CBBE408AAC |

### Pic (io(x)-apic) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2026 | 8086:2026 | Intel      | Sky Lake-E IOAPIC            | 29    |            | 8E73F804F5 |
| 8086:2036 | 8086:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 29    |            | 8E73F804F5 |
| 8086:342d |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 21    |            | 726EA75DCA |
| 8086:6f2c | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:2f2c | 8086:0000 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 7     |            | AF9F6ACE3F |
| 8086:3c2c | 103c:18a8 | Intel      | Xeon E5/Core i7 I/O APIC     | 6     |            | 4805EBBD1F |
| 8086:0e2c | 15d9:0636 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     |            | 100EFA1F4A |
| 8086:2f2c | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     |            | C9D389B2A3 |
| 8086:2f2c | 15d9:0857 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     |            | D05461EFDA |
| 8086:342d | 0086:00dc | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     |            | 138B84322E |
| 8086:342f | 0086:00dc | Intel      | 7500/5520/5500/X58 Truste... | 3     |            | 138B84322E |
| 8086:0e2c | 103c:18a8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 2     |            | 07278BAD4B |
| 8086:2f2c | 15d9:0831 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     |            | 52D5275C7F |
| 8086:342d | 0086:00da | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     |            | DEC98C8F86 |
| 8086:342f |           | Intel      | 7500/5520/5500/X58 Truste... | 2     |            | D804E1DA52 |
| 8086:342f | 0086:00da | Intel      | 7500/5520/5500/X58 Truste... | 2     |            | DEC98C8F86 |
| 8086:3c2c | 1043:84f0 | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | 996F55BB36 |
| 8086:3c2c | 8086:357e | Intel      | Xeon E5/Core i7 I/O APIC     | 2     |            | F65EC09250 |
| 8086:6f2c | 15d9:0824 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 6C96E4A591 |
| 8086:6f2c | 8086:0000 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | 3BA1B5FC84 |
| 8086:0326 | 103c:3208 | Intel      | 6700/6702PXH I/OxAPIC Int... | 1     |            | 2C877CF870 |
| 8086:0326 | 8086:3439 | Intel      | 6700/6702PXH I/OxAPIC Int... | 1     |            | 0F21E859FA |
| 8086:0327 | 103c:3208 | Intel      | 6700PXH I/OxAPIC Interrup... | 1     |            | 2C877CF870 |
| 8086:0327 | 8086:3439 | Intel      | 6700PXH I/OxAPIC Interrup... | 1     |            | 0F21E859FA |
| 8086:0e2c | 1043:84f0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 90D8E62525 |
| 8086:0e2c | 15d9:0665 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | CEC82EF5D0 |
| 8086:0e2c | 15d9:070a | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | B4C8ABC585 |
| 8086:0e2c | 8086:357e | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 018029FB72 |
| 8086:2026 | 1590:18a9 | Intel      | Sky Lake-E IOAPIC            | 1     |            | 9E91D0ED19 |
| 8086:2026 | 17aa:1038 | Intel      | Sky Lake-E IOAPIC            | 1     |            | ED799888EB |
| 8086:2026 | 8086:0000 | Intel      | Sky Lake-E IOAPIC            | 1     |            | 0617E49F12 |
| 8086:2036 | 1590:18a9 | Intel      | Sky Lake-E IOxAPIC Config... | 1     |            | 9E91D0ED19 |
| 8086:2036 | 17aa:1038 | Intel      | Sky Lake-E IOxAPIC Config... | 1     |            | ED799888EB |
| 8086:2036 | 8086:0000 | Intel      | Sky Lake-E IOxAPIC Config... | 1     |            | 0617E49F12 |
| 8086:2f2c | 1d49:0a00 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 817865DED6 |
| 8086:2f2c | 8086:35c5 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 08100751B7 |
| 8086:2f2c | 8086:35c9 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 5F9F099F36 |
| 8086:342d | 0086:0000 | Intel      | 7500/5520/5500/X58 I/O Hu... | 1     |            | CBBE408AAC |
| 8086:342f | 0034:0027 | Intel      | 7500/5520/5500/X58 Truste... | 1     |            | C7E9D74C3D |
| 8086:342f | 0086:0000 | Intel      | 7500/5520/5500/X58 Truste... | 1     |            | CBBE408AAC |
| 8086:6f2c | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | 140DAF886E |
| 8086:6f2c | 15d9:0834 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | EEE6327556 |
| 8086:6f2c | 15d9:0835 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | 7479576DA8 |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a1a4 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    |            | 4391DFF8D2 |
| 8086:a1a4 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 5     |            | 8E73F804F5 |
| 10de:1ad7 | 19da:2503 | Nvidia     | TU102 UCSI Controller        | 1     |            | 8E73F804F5 |
| 8086:a1a4 | 1028:0718 | Intel      | C620 Series Chipset Famil... | 1     |            | 97313ACF09 |
| 8086:a1a4 | 1028:0739 | Intel      | C620 Series Chipset Famil... | 1     |            | AD29AF92C2 |
| 8086:a1a4 | 1028:07cb | Intel      | C620 Series Chipset Famil... | 1     |            | 5B9EC879FC |
| 8086:a1a4 | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 1     |            | 0617E49F12 |
| 8086:a1a4 | 1043:871e | Intel      | C620 Series Chipset Famil... | 1     |            | A1916FC246 |
| 8086:a1a4 | 15d9:095d | Intel      | C620 Series Chipset Famil... | 1     |            | 2794B14FEE |
| 8086:a1a4 | 15d9:096d | Intel      | C620 Series Chipset Famil... | 1     |            | DCFB9EE48A |
| 8086:a1a4 | 15d9:0987 | Intel      | C620 Series Chipset Famil... | 1     |            | 893E9D69F2 |
| 8086:a1a4 | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 1     |            | ED799888EB |
| 8086:a324 | 15d9:1a1d | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 21E2FBBB75 |
| 8086:a368 | 15d9:1a1d | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | 21E2FBBB75 |
| 8086:a369 | 15d9:1a1d | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | 21E2FBBB75 |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8c3d | 15d9:0805 | Intel      | 8 Series/C220 Series Chip... | 1     | serial     | 3F6EE4141E |
| 8086:a13d | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 1     | serial     | 5372999434 |
| 8086:a13d | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | serial     | C392838A14 |
| 8086:a1bd | 1028:0739 | Intel      | C620 Series Chipset Famil... | 1     | serial     | AD29AF92C2 |
| 8086:a1bd | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 1     | serial     | ED799888EB |
| 9710:9922 | a000:1000 | MosChip... | MCS9922 PCIe Multi-I/O Co... | 1     | serial     | 7479576DA8 |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a1b1 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    |            | 4391DFF8D2 |
| 8086:a1b1 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 5     |            | 8E73F804F5 |
| 8086:1d24 | 15d9:0636 | Intel      | C600/X79 series chipset T... | 3     |            | 100EFA1F4A |
| 8086:8d24 | 15d9:0857 | Intel      | C610/X99 series chipset T... | 3     |            | D05461EFDA |
| 8086:8d24 | 15d9:0831 | Intel      | C610/X99 series chipset T... | 2     |            | 52D5275C7F |
| 8086:1d24 | 15d9:0665 | Intel      | C600/X79 series chipset T... | 1     |            | CEC82EF5D0 |
| 8086:1d24 | 15d9:070a | Intel      | C600/X79 series chipset T... | 1     |            | B4C8ABC585 |
| 8086:8c24 | 15d9:0802 | Intel      | 8 Series Chipset Family T... | 1     | intel_p... | 7115F8FDB7 |
| 8086:8c24 | 15d9:0805 | Intel      | 8 Series Chipset Family T... | 1     | intel_p... | 3F6EE4141E |
| 8086:8c24 | 15d9:0921 | Intel      | 8 Series Chipset Family T... | 1     | intel_p... | DB25C87154 |
| 8086:8d24 | 1d49:0000 | Intel      | C610/X99 series chipset T... | 1     |            | 817865DED6 |
| 8086:a131 | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | C74A66C7E6 |
| 8086:a131 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | BB8832ACBD |
| 8086:a131 | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | 5372999434 |
| 8086:a131 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | C392838A14 |
| 8086:a131 | 1734:1222 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | 0BD7D9FCEA |
| 8086:a131 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 13B41B547A |
| 8086:a160 | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_l... | 5372999434 |
| 8086:a160 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | intel_l... | C392838A14 |
| 8086:a161 | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_l... | 5372999434 |
| 8086:a161 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | intel_l... | C392838A14 |
| 8086:a1b1 | 1028:0718 | Intel      | C620 Series Chipset Famil... | 1     |            | 97313ACF09 |
| 8086:a1b1 | 1028:0739 | Intel      | C620 Series Chipset Famil... | 1     |            | AD29AF92C2 |
| 8086:a1b1 | 1028:07cb | Intel      | C620 Series Chipset Famil... | 1     |            | 5B9EC879FC |
| 8086:a1b1 | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 1     |            | 0617E49F12 |
| 8086:a1b1 | 1043:871e | Intel      | C620 Series Chipset Famil... | 1     |            | A1916FC246 |
| 8086:a1b1 | 1590:00eb | Intel      | C620 Series Chipset Famil... | 1     |            | 9E91D0ED19 |
| 8086:a1b1 | 15d9:095d | Intel      | C620 Series Chipset Famil... | 1     |            | 2794B14FEE |
| 8086:a1b1 | 15d9:096d | Intel      | C620 Series Chipset Famil... | 1     |            | DCFB9EE48A |
| 8086:a1b1 | 15d9:0987 | Intel      | C620 Series Chipset Famil... | 1     |            | 893E9D69F2 |
| 8086:a1b1 | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 1     |            | ED799888EB |
| 8086:a2b1 | 15d9:098e | Intel      | 200 Series PCH Thermal Su... | 1     |            | 98ED2C77C7 |
| 8086:a2e0 | 15d9:098e | Intel      | 200 Series PCH Serial IO ... | 1     | intel_lpss | 98ED2C77C7 |
| 8086:a2e1 | 15d9:098e | Intel      | 200 Series PCH Serial IO ... | 1     | intel_lpss | 98ED2C77C7 |
| 8086:a379 | 15d9:1a1d | Intel      | Cannon Lake PCH Thermal C... | 1     | intel_p... | 21E2FBBB75 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8d22 | 15d9:0821 | Intel      | C610/X99 series chipset S... | 16    | i2c_i801   | 17BF7A3CBC |
| 8086:a1a3 | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    |            | 4391DFF8D2 |
| 8086:3a30 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) SM... | 11    | i2c_i801   | 726EA75DCA |
| 8086:a1a3 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 5     | i2c_i801   | 8E73F804F5 |
| 8086:3a30 | 15d9:060f | Intel      | 82801JI (ICH10 Family) SM... | 4     | i2c_i801   | 1D3C1DC3BF |
| 8086:8d22 | 103c:8030 | Intel      | C610/X99 series chipset S... | 4     | i2c_i801   | 140DAF886E |
| 8086:1c22 | 1043:8497 | Intel      | 6 Series/C200 Series Chip... | 3     | i2c_i801   | AB7179BE16 |
| 8086:1d22 | 1043:84ef | Intel      | C600/X79 series chipset S... | 3     | i2c_i801   | 996F55BB36 |
| 8086:1d22 | 15d9:0636 | Intel      | C600/X79 series chipset S... | 3     | i2c_i801   | 100EFA1F4A |
| 8086:1d22 | 8086:357e | Intel      | C600/X79 series chipset S... | 3     | i2c_i801   | F65EC09250 |
| 8086:3a30 | 8086:34dc | Intel      | 82801JI (ICH10 Family) SM... | 3     |            | 138B84322E |
| 8086:8d22 | 15d9:0857 | Intel      | C610/X99 series chipset S... | 3     |            | D05461EFDA |
| 8086:8d22 | 8086:7270 | Intel      | C610/X99 series chipset S... | 3     | i2c_i801   | 7658F21E98 |
| 1022:790b | 1022:790b | AMD        | FCH SMBus Controller         | 2     | i2c_piix4  | 4B4029781F |
| 8086:1c22 | 1028:04de | Intel      | 6 Series/C200 Series Chip... | 2     |            | 389DD308F7 |
| 8086:1c22 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 2     |            | DAA63A315C |
| 8086:1d22 | 1014:1d22 | Intel      | C600/X79 series chipset S... | 2     | i2c_i801   | B55F7AE6F3 |
| 8086:2930 | 8086:34d0 | Intel      | 82801I (ICH9 Family) SMBu... | 2     | i2c_i801   | 81A05F54F2 |
| 8086:3a30 | 1014:3a30 | Intel      | 82801JI (ICH10 Family) SM... | 2     | i2c_i801   | D804E1DA52 |
| 8086:3a30 | 15d9:0600 | Intel      | 82801JI (ICH10 Family) SM... | 2     | i2c_i801   | 8C854FDF21 |
| 8086:3a30 | 8086:34da | Intel      | 82801JI (ICH10 Family) SM... | 2     | i2c_i801   | DEC98C8F86 |
| 8086:3a30 | 8086:3a30 | Intel      | 82801JI (ICH10 Family) SM... | 2     | i2c_i801   | 3D4DABE8D3 |
| 8086:8c22 | 8086:8c22 | Intel      | 8 Series/C220 Series Chip... | 2     | i2c_i801   | B3CC6B4BAD |
| 8086:8d22 | 15d9:0824 | Intel      | C610/X99 series chipset S... | 2     | i2c_i801   | 6C96E4A591 |
| 8086:8d22 | 15d9:0831 | Intel      | C610/X99 series chipset S... | 2     | i801_smbus | 52D5275C7F |
| 1002:4385 | 103c:3337 | AMD        | SBx00 SMBus Controller       | 1     | i2c_piix4  | 7CE46A749E |
| 1002:4385 | 15d9:ab11 | AMD        | SBx00 SMBus Controller       | 1     | i2c_piix4  | 463CF097DA |
| 1002:4385 | 15d9:bc11 | AMD        | SBx00 SMBus Controller       | 1     | i2c_piix4  | 7E28DD35AD |
| 10de:0368 | 108e:534d | Nvidia     | MCP55 SMBus Controller       | 1     | i2c_nfo... | 1F35F79302 |
| 8086:1c22 | 1028:04dd | Intel      | 6 Series/C200 Series Chip... | 1     | i2c_i801   | 3A05F2F446 |
| 8086:1c22 | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 1     | i2c_i801   | D092DEFE79 |
| 8086:1d22 | 15d9:0665 | Intel      | C600/X79 series chipset S... | 1     |            | CEC82EF5D0 |
| 8086:1d22 | 15d9:070a | Intel      | C600/X79 series chipset S... | 1     |            | B4C8ABC585 |
| 8086:1d70 | 8086:357e | Intel      | C600/X79 series chipset S... | 1     | i2c_i801   | 7DC714253B |
| 8086:24d3 | 103c:3208 | Intel      | 82801EB/ER (ICH5/ICH5R) S... | 1     | i2c_i801   | 2C877CF870 |
| 8086:24d3 | 8086:3439 | Intel      | 82801EB/ER (ICH5/ICH5R) S... | 1     | i2c_i801   | 0F21E859FA |
| 8086:269b | 8086:3476 | Intel      | 631xESB/632xESB/3100 Chip... | 1     | i2c_i801   | 5229FAFC3E |
| 8086:269b | 8086:3484 | Intel      | 631xESB/632xESB/3100 Chip... | 1     | i2c_i801   | 5C3DF14DAD |
| 8086:2930 | 8086:34d1 | Intel      | 82801I (ICH9 Family) SMBu... | 1     | i2c_i801   | 9A27511AEB |
| 8086:3a30 | 1043:8362 | Intel      | 82801JI (ICH10 Family) SM... | 1     | i2c_i801   | 8681056F1F |
| 8086:3a30 | 1170:0047 | Intel      | 82801JI (ICH10 Family) SM... | 1     |            | 9762DCCBE9 |
| 8086:3a30 | 15d9:0001 | Intel      | 82801JI (ICH10 Family) SM... | 1     |            | CC8DB94EBA |
| 8086:3a30 | 15d9:0100 | Intel      | 82801JI (ICH10 Family) SM... | 1     | i2c_i801   | 68E0C84652 |
| 8086:3a30 | 1734:114d | Intel      | 82801JI (ICH10 Family) SM... | 1     |            | C7E9D74C3D |
| 8086:3a30 | 8086:0000 | Intel      | 82801JI (ICH10 Family) SM... | 1     |            | CBBE408AAC |
| 8086:3b30 | 1014:0377 | Intel      | 5 Series/3400 Series Chip... | 1     | i2c_i801   | E53A957D3F |
| 8086:3b30 | 8086:34ec | Intel      | 5 Series/3400 Series Chip... | 1     | i2c_i801   | 6DE12619B5 |
| 8086:8c22 | 15d9:0802 | Intel      | 8 Series/C220 Series Chip... | 1     | i2c_i801   | 7115F8FDB7 |
| 8086:8c22 | 15d9:0805 | Intel      | 8 Series/C220 Series Chip... | 1     | i801_smbus | 3F6EE4141E |
| 8086:8c22 | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 1     | i801_smbus | DB25C87154 |
| 8086:8d22 | 1043:85f6 | Intel      | C610/X99 series chipset S... | 1     |            | FD500E59D6 |
| 8086:8d22 | 15d9:0834 | Intel      | C610/X99 series chipset S... | 1     | i2c_i801   | EEE6327556 |
| 8086:8d22 | 15d9:0835 | Intel      | C610/X99 series chipset S... | 1     | i2c_i801   | 7479576DA8 |
| 8086:8d22 | 1d49:0a00 | Intel      | C610/X99 series chipset S... | 1     | i2c_i801   | 817865DED6 |
| 8086:8d22 | 8086:35c5 | Intel      | C610/X99 series chipset S... | 1     | i2c_i801   | 08100751B7 |
| 8086:8d22 | 8086:35c9 | Intel      | C610/X99 series chipset S... | 1     |            | 5F9F099F36 |
| 8086:8d7d | 8086:35c5 | Intel      | C610/X99 series chipset M... | 1     | i2c_i801   | 08100751B7 |
| 8086:a123 | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     |            | C74A66C7E6 |
| 8086:a123 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 1     | i2c_i801   | BB8832ACBD |
| 8086:a123 | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 5372999434 |
| 8086:a123 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     |            | C392838A14 |
| 8086:a123 | 1734:1222 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 0BD7D9FCEA |
| 8086:a123 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     | i2c_i801   | 13B41B547A |
| 8086:a1a3 | 1028:0718 | Intel      | C620 Series Chipset Famil... | 1     |            | 97313ACF09 |
| 8086:a1a3 | 1028:0739 | Intel      | C620 Series Chipset Famil... | 1     | i2c_i801   | AD29AF92C2 |
| 8086:a1a3 | 1028:07cb | Intel      | C620 Series Chipset Famil... | 1     |            | 5B9EC879FC |
| 8086:a1a3 | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 1     |            | 0617E49F12 |
| 8086:a1a3 | 1043:871e | Intel      | C620 Series Chipset Famil... | 1     |            | A1916FC246 |
| 8086:a1a3 | 15d9:095d | Intel      | C620 Series Chipset Famil... | 1     |            | 2794B14FEE |
| 8086:a1a3 | 15d9:096d | Intel      | C620 Series Chipset Famil... | 1     |            | DCFB9EE48A |
| 8086:a1a3 | 15d9:0987 | Intel      | C620 Series Chipset Famil... | 1     |            | 893E9D69F2 |
| 8086:a1a3 | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 1     |            | ED799888EB |
| 8086:a2a3 | 15d9:098e | Intel      | 200 Series/Z370 Chipset F... | 1     | i801_smbus | 98ED2C77C7 |
| 8086:a323 | 15d9:1a1d | Intel      | Cannon Lake PCH SMBus Con... | 1     |            | 21E2FBBB75 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3a3e | 15d9:0006 | Intel      | 82801JI (ICH10 Family) HD... | 9     | snd_hda... | 320D2811E2 |
| 8086:8d20 | 15d9:0857 | Intel      | C610/X99 series chipset H... | 3     | snd_hda... | D05461EFDA |
| 10de:0e0f | 1043:84f5 | Nvidia     | GK208 HDMI/DP Audio Contr... | 2     | snd_hda... | D05461EFDA |
| 10de:0fbb | 1043:8508 | Nvidia     | GM204 High Definition Aud... | 2     | snd_hda... | 22AA6FF795 |
| 1102:0007 | 1102:100a | Creativ... | CA0106/CA0111 [SB Live!/A... | 2     | snd_ca0106 | 50527E087E |
| 8086:1d20 | 1043:851b | Intel      | C600/X79 series chipset H... | 2     | snd_hda... | 996F55BB36 |
| 1002:aa30 | 1787:aa30 | AMD        | RV770 HDMI Audio [Radeon ... | 1     | snd_hda... | 7092025B53 |
| 1002:aa58 | 1043:aa58 | AMD        | Juniper HDMI Audio [Radeo... | 1     | snd_hda... | 7E28DD35AD |
| 1002:aa60 | 1462:aa60 | AMD        | Redwood HDMI Audio [Radeo... | 1     | snd_hda... | 53D66D8AB3 |
| 1002:aa80 | 1002:aa80 | AMD        | Cayman/Antilles HDMI Audi... | 1     | snd_hda... | 7F6C6E8DE0 |
| 1002:aa80 | 1028:aa80 | AMD        | Cayman/Antilles HDMI Audi... | 1     | snd_hda... | C7E9D74C3D |
| 1002:aa90 | 1002:aa90 | AMD        | Turks HDMI Audio [Radeon ... | 1     | snd_hda... | 5372999434 |
| 1002:aa98 | 1462:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 1     | snd_hda... | 138B84322E |
| 1002:aaa0 | 1002:aaa0 | AMD        | Tahiti HDMI Audio [Radeon... | 1     | snd_hda... | CEC82EF5D0 |
| 1002:aab0 | 1043:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 1     | snd_hda... | 3F6EE4141E |
| 1002:aab0 | 148c:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 1     | snd_hda... | 726EA75DCA |
| 1002:aae8 | 1002:aae8 | AMD        | Fiji HDMI/DP Audio [Radeo... | 1     | snd_hda... | 98ED2C77C7 |
| 1002:aaf0 | 1043:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 1     | snd_hda... | A8A3023830 |
| 1002:aaf0 | 1da2:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 1     | snd_hda... | F65EC09250 |
| 10de:0371 | 108e:534d | Nvidia     | MCP55 High Definition Audio  | 1     | snd_hda... | 1F35F79302 |
| 10de:0be3 | 1462:8094 | Nvidia     | High Definition Audio Con... | 1     | snd_hda... | 1F35F79302 |
| 10de:0be3 | 3842:1301 | Nvidia     | High Definition Audio Con... | 1     | snd_hda... | 21E2FBBB75 |
| 10de:0bee | 10de:0000 | Nvidia     | GF116 High Definition Aud... | 1     | snd_hda... | DEC98C8F86 |
| 10de:0e0a | 10de:1096 | Nvidia     | GK104 HDMI Audio Controller  | 1     | snd_hda... | FD500E59D6 |
| 10de:0e0a | 3842:3769 | Nvidia     | GK104 HDMI Audio Controller  | 1     | snd_hda... | CC8DB94EBA |
| 10de:0e0b | 1043:8423 | Nvidia     | GK106 HDMI Audio Controller  | 1     | snd_hda... | 7115F8FDB7 |
| 10de:0e0b | 1043:842a | Nvidia     | GK106 HDMI Audio Controller  | 1     | snd_hda... | 6DE12619B5 |
| 10de:0e0f | 19da:5360 | Nvidia     | GK208 HDMI/DP Audio Contr... | 1     | snd_hda... | D9F1CB21BC |
| 10de:0e1b | 10de:094b | Nvidia     | GK107 HDMI Audio Controller  | 1     | snd_hda... | 90D8E62525 |
| 10de:0e1b | 19da:1294 | Nvidia     | GK107 HDMI Audio Controller  | 1     | snd_hda... | 50527E087E |
| 10de:0fb9 | 1028:1264 | Nvidia     | GP107GL High Definition A... | 1     | snd_hda... | AD29AF92C2 |
| 10de:0fb9 | 1043:8613 | Nvidia     | GP107GL High Definition A... | 1     | snd_hda... | 09FB58BF8D |
| 10de:0fb9 | 10de:11bd | Nvidia     | GP107GL High Definition A... | 1     | snd_hda... | 8681056F1F |
| 10de:0fb9 | 1458:3765 | Nvidia     | GP107GL High Definition A... | 1     | snd_hda... | A1916FC246 |
| 10de:10ef | 10de:119a | Nvidia     | GP102 HDMI Audio Controller  | 1     | snd_hda... | 7658F21E98 |
| 10de:10f0 | 103c:11a3 | Nvidia     | GP104 High Definition Aud... | 1     | snd_hda... | 0617E49F12 |
| 10de:10f0 | 1043:8597 | Nvidia     | GP104 High Definition Aud... | 1     | snd_hda... | 90D8E62525 |
| 10de:10f0 | 1043:85aa | Nvidia     | GP104 High Definition Aud... | 1     | snd_hda... | F8D0599716 |
| 10de:10f0 | 10de:11b2 | Nvidia     | GP104 High Definition Aud... | 1     | snd_hda... | ED799888EB |
| 10de:10f0 | 1458:3702 | Nvidia     | GP104 High Definition Aud... | 1     | snd_hda... | 996F55BB36 |
| 10de:10f7 | 19da:2503 | Nvidia     | TU102 High Definition Aud... | 1     | snd_hda... | 8E73F804F5 |
| 1102:0004 | 1102:0053 | Creativ... | EMU10k2/CA0100/CA0102/CA1... | 1     | snd_emu... | 138B84322E |
| 1102:0007 | 1102:1004 | Creativ... | CA0106/CA0111 [SB Live!/A... | 1     | snd_ca0106 | AB7179BE16 |
| 1102:0012 | 1102:0010 | Creativ... | Sound Core3D [Sound Blast... | 1     | snd_hda... | DEC98C8F86 |
| 13f6:0111 | 13f6:0111 | C-Media... | CMI8738/CMI8768 PCI Audio    | 1     | snd_cmipci | ABCF5C7050 |
| 13f6:8788 | 1043:8275 | C-Media... | CMI8788 [Oxygen HD Audio]    | 1     | snd_vir... | CEC82EF5D0 |
| 13f6:8788 | 1043:8521 | C-Media... | CMI8788 [Oxygen HD Audio]    | 1     | snd_oxygen | 6DE12619B5 |
| 1412:1724 | 1412:1724 | VIA Tec... | VT1720/24 [Envy24PT/HT] P... | 1     | snd_ice... | 81A05F54F2 |
| 8086:1c20 | 1043:8469 | Intel      | 6 Series/C200 Series Chip... | 1     | snd_hda... | 833ACDFC5E |
| 8086:1d20 | 1043:84d8 | Intel      | C600/X79 series chipset H... | 1     | snd_hda... | 90D8E62525 |
| 8086:1d20 | 15d9:0665 | Intel      | C600/X79 series chipset H... | 1     | snd_hda... | CEC82EF5D0 |
| 8086:3a3e | 15d9:0100 | Intel      | 82801JI (ICH10 Family) HD... | 1     | snd_hda... | 68E0C84652 |
| 8086:8c20 | 15d9:0805 | Intel      | 8 Series/C220 Series Chip... | 1     | snd_hda... | 3F6EE4141E |
| 8086:8d20 | 1043:855f | Intel      | C610/X99 series chipset H... | 1     | snd_hda... | FD500E59D6 |
| 8086:a170 | 15d9:0895 | Intel      | 100 Series/C230 Series Ch... | 1     | snd_hda... | 5372999434 |
| 8086:a170 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | snd_hda... | C392838A14 |
| 8086:a1f0 | 1028:0739 | Intel      | Lewisburg MROM 0             | 1     | snd_hda... | AD29AF92C2 |
| 8086:a1f0 | 103c:81c7 | Intel      | Lewisburg MROM 0             | 1     | snd_hda... | 0617E49F12 |
| 8086:a1f0 | 15d9:096d | Intel      | Lewisburg MROM 0             | 1     | snd_hda... | DCFB9EE48A |
| 8086:a1f0 | 17aa:1038 | Intel      | Lewisburg MROM 0             | 1     | snd_hda... | ED799888EB |
| 8086:a1f0 | 8086:7270 | Intel      | Lewisburg MROM 0             | 1     | snd_hda... | F8D0599716 |
| 8086:a2f0 | 15d9:098e | Intel      | 200 Series PCH HD Audio      | 1     | snd_hda... | 98ED2C77C7 |
| 8086:a348 | 15d9:1a1d | Intel      | Cannon Lake PCH cAVS         | 1     | snd_hda... | 21E2FBBB75 |

### Storage (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1000:0058 | 1028:1f0f | LSI Log... | SAS1068E PCI-Express Fusi... | 2     | mptsas     | 0F9D97BC71 |
| 1000:0072 | 1000:3020 | LSI Log... | SAS2008 PCI-Express Fusio... | 2     | mpt3sas    | 7E28DD35AD |
| 1000:0072 | 1028:1f1c | LSI Log... | SAS2008 PCI-Express Fusio... | 2     | mpt3sas    | 68E0C84652 |
| 8086:1d6b | 1043:84ef | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 996F55BB36 |
| 1000:0030 | 1000:50c0 | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 3F4700F256 |
| 1000:0030 | 1014:026c | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 46973B5B05 |
| 1000:0030 | 1028:016e | LSI Log... | 53c1030 PCI-X Fusion-MPT ... | 1     | mptspi     | 76EF1C8CA9 |
| 1000:0056 | 1014:03bb | LSI Log... | SAS1064ET PCI-Express Fus... | 1     | mptsas     | E53A957D3F |
| 1000:0058 | 1014:0394 | LSI Log... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | A82CA8F32E |
| 1000:0058 | 1028:1f10 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mptsas     | 25731D395E |
| 1000:0064 | 15d9:083c | LSI Log... | SAS2116 PCI-Express Fusio... | 1     | mpt3sas    | DB25C87154 |
| 1000:0070 | 1014:03f7 | LSI Log... | SAS2004 PCI-Express Fusio... | 1     | mpt2sas    | D7CBC31CEE |
| 1000:0072 | 1000:3040 | LSI Log... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | DF1B417E9A |
| 1000:0072 | 15d9:0400 | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mpt3sas    | 463CF097DA |
| 1000:0087 | 1000:3020 | LSI Log... | SAS2308 PCI-Express Fusio... | 1     | mpt3sas    | 7DC714253B |
| 1000:0097 | 1000:30a0 | Broadco... | SAS3008 PCI-Express Fusio... | 1     | mpt3sas    | 21E2FBBB75 |
| 1000:0097 | 1000:30e0 | LSI Log... | SAS3008 PCI-Express Fusio... | 1     | mpt3sas    | EDE05678EF |
| 1077:2031 | 103c:1939 | QLogic     | ISP8324-based 16Gb Fibre ... | 1     | qla2xxx    | 9036136416 |
| 1077:2031 | 1077:0257 | QLogic     | ISP8324-based 16Gb Fibre ... | 1     | qla2xxx    | CBFB7C31D8 |
| 1077:2432 | 103c:7041 | QLogic     | ISP2432-based 4Gb Fibre C... | 1     | qla2xxx    | C9D389B2A3 |
| 1077:2532 | 1077:015d | QLogic     | ISP2532-based 8Gb Fibre C... | 1     | qla2xxx    | 97313ACF09 |
| 1077:2532 | 1077:0176 | QLogic     | ISP2532-based 8Gb Fibre C... | 1     | qla2xxx    | D7CBC31CEE |
| 10df:fe00 | 10df:fe00 | Emulex     | Zephyr-X LightPulse Fibre... | 1     | lpfc       | 6806624961 |
| 8086:1d6b | 15d9:0636 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 98CA4D1013 |
| 8086:1d6b | 15d9:0665 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | CEC82EF5D0 |
| 8086:1d6b | 15d9:070a | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | B4C8ABC585 |
| 8086:1d6b | 8086:357f | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 7DC714253B |
| 9005:028d | 9005:0652 | Adaptec    | Series 8 12G SAS/PCIe 3      | 1     | aacraid    | 7479576DA8 |
| 9005:028f | 103c:0701 | Adaptec    | Smart Storage PQI 12G SAS... | 1     | smartpqi   | 9E91D0ED19 |
| 9005:8017 | 9005:0045 | Adaptec    | ASC-29320ALP U320            | 1     | aic79xx    | 5C3DF14DAD |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8d02 | 15d9:0821 | Intel      | C610/X99 series chipset 6... | 13    | ahci       | 57FC9BDF47 |
| 8086:8d62 | 15d9:0821 | Intel      | C610/X99 series chipset s... | 13    | ahci       | 57FC9BDF47 |
| 8086:3a22 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) SA... | 11    | ahci       | 726EA75DCA |
| 8086:1d02 | 103c:18a9 | Intel      | C600/X79 series chipset 6... | 5     | ahci       | BA2F9FC714 |
| 8086:a1d2 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 5     | ahci       | 8E73F804F5 |
| 8086:3a22 | 15d9:060f | Intel      | 82801JI (ICH10 Family) SA... | 4     | ahci       | 1D3C1DC3BF |
| 8086:8d02 | 103c:8030 | Intel      | C610/X99 series chipset 6... | 4     | ahci       | 140DAF886E |
| 8086:a182 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 4     | ahci       | 8E73F804F5 |
| 8086:1d02 | 1043:84ef | Intel      | C600/X79 series chipset 6... | 3     | ahci       | 996F55BB36 |
| 8086:1d02 | 15d9:0636 | Intel      | C600/X79 series chipset 6... | 3     | ahci       | 100EFA1F4A |
| 8086:1d02 | 8086:357e | Intel      | C600/X79 series chipset 6... | 3     | ahci       | F65EC09250 |
| 8086:8d02 | 1028:0601 | Intel      | C610/X99 series chipset 6... | 3     | ahci       | AF9F6ACE3F |
| 8086:8d02 | 8086:7270 | Intel      | C610/X99 series chipset 6... | 3     | ahci       | 7658F21E98 |
| 8086:8d62 | 1028:0601 | Intel      | C610/X99 series chipset s... | 3     | ahci       | AF9F6ACE3F |
| 8086:8d62 | 15d9:0857 | Intel      | C610/X99 series chipset s... | 3     | ahci       | D05461EFDA |
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 2     | ahci       | 4B4029781F |
| 1b4b:9230 | 1b4b:9230 | Marvell... | 88SE9230 PCIe SATA 6Gb/s ... | 2     | ahci       | 4B4029781F |
| 8086:8d02 | 15d9:0824 | Intel      | C610/X99 series chipset 6... | 2     | ahci       | 6C96E4A591 |
| 8086:8d02 | 15d9:0831 | Intel      | C610/X99 series chipset 6... | 2     | ahci       | 52D5275C7F |
| 8086:8d02 | 15d9:0857 | Intel      | C610/X99 series chipset 6... | 2     | ahci       | D05461EFDA |
| 8086:8d62 | 15d9:0824 | Intel      | C610/X99 series chipset s... | 2     | ahci       | 6C96E4A591 |
| 8086:8d62 | 8086:7270 | Intel      | C610/X99 series chipset s... | 2     | ahci       | 7658F21E98 |
| 1002:4391 | 1002:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 7E28DD35AD |
| 1b21:0612 | 15d9:0805 | ASMedia... | ASM1062 Serial ATA Contro... | 1     | ahci       | 3F6EE4141E |
| 1b21:0612 | 1b21:1060 | ASMedia... | ASM1062 Serial ATA Contro... | 1     | ahci       | ABCF5C7050 |
| 1b4b:9230 | 1043:84fa | Marvell... | 88SE9230 PCIe SATA 6Gb/s ... | 1     | ahci       | 90D8E62525 |
| 1b4b:9230 | 1043:857a | Marvell... | 88SE9230 PCIe SATA 6Gb/s ... | 1     | ahci       | A1916FC246 |
| 8086:1c02 | 1028:04dd | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | 3A05F2F446 |
| 8086:1c02 | 1028:04de | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | 389DD308F7 |
| 8086:1c02 | 1043:8497 | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | 833ACDFC5E |
| 8086:1c02 | 1043:8498 | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | 50527E087E |
| 8086:1c02 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | DAA63A315C |
| 8086:1d02 | 1028:048c | Intel      | C600/X79 series chipset 6... | 1     | ahci       | B6374DF09A |
| 8086:1d02 | 1028:04f8 | Intel      | C600/X79 series chipset 6... | 1     | ahci       | A1EFBB1BE1 |
| 8086:1d02 | 15d9:0665 | Intel      | C600/X79 series chipset 6... | 1     | ahci       | CEC82EF5D0 |
| 8086:1d02 | 15d9:070a | Intel      | C600/X79 series chipset 6... | 1     | ahci       | B4C8ABC585 |
| 8086:3a22 | 1170:0047 | Intel      | 82801JI (ICH10 Family) SA... | 1     | ahci       | 9762DCCBE9 |
| 8086:3a22 | 15d9:0001 | Intel      | 82801JI (ICH10 Family) SA... | 1     | ahci       | CC8DB94EBA |
| 8086:3a22 | 15d9:0600 | Intel      | 82801JI (ICH10 Family) SA... | 1     | ahci       | 8C854FDF21 |
| 8086:3a22 | 8086:34dc | Intel      | 82801JI (ICH10 Family) SA... | 1     | ahci       | 661671ECB0 |
| 8086:3b22 | 8086:34ec | Intel      | 5 Series/3400 Series Chip... | 1     | ahci       | 6DE12619B5 |
| 8086:8c02 | 15d9:0805 | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | 3F6EE4141E |
| 8086:8c02 | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | DB25C87154 |
| 8086:8c02 | 8086:8c02 | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | B3CC6B4BAD |
| 8086:8d02 | 1028:0639 | Intel      | C610/X99 series chipset 6... | 1     | ahci       | 3BA1B5FC84 |
| 8086:8d02 | 1028:063a | Intel      | C610/X99 series chipset 6... | 1     | ahci       | FF3ACF2BDC |
| 8086:8d02 | 1043:85f6 | Intel      | C610/X99 series chipset 6... | 1     | ahci       | FD500E59D6 |
| 8086:8d02 | 15d9:0835 | Intel      | C610/X99 series chipset 6... | 1     | ahci       | 7479576DA8 |
| 8086:8d02 | 8086:35c9 | Intel      | C610/X99 series chipset 6... | 1     | ahci       | 5F9F099F36 |
| 8086:8d62 | 1028:0639 | Intel      | C610/X99 series chipset s... | 1     | ahci       | 3BA1B5FC84 |
| 8086:8d62 | 1028:063a | Intel      | C610/X99 series chipset s... | 1     | ahci       | FF3ACF2BDC |
| 8086:8d62 | 1043:85f7 | Intel      | C610/X99 series chipset s... | 1     | ahci       | FD500E59D6 |
| 8086:8d62 | 15d9:0831 | Intel      | C610/X99 series chipset s... | 1     | ahci       | 52D5275C7F |
| 8086:8d62 | 15d9:0834 | Intel      | C610/X99 series chipset s... | 1     | ahci       | EEE6327556 |
| 8086:8d62 | 15d9:0835 | Intel      | C610/X99 series chipset s... | 1     | ahci       | 7479576DA8 |
| 8086:8d62 | 8086:35c5 | Intel      | C610/X99 series chipset s... | 1     | ahci       | 08100751B7 |
| 8086:8d62 | 8086:35c9 | Intel      | C610/X99 series chipset s... | 1     | ahci       | 5F9F099F36 |
| 8086:a102 | 1028:06aa | Intel      | Q170/Q150/B150/H170/H110/... | 1     | ahci       | C74A66C7E6 |
| 8086:a102 | 15d9:0884 | Intel      | Q170/Q150/B150/H170/H110/... | 1     | ahci       | BB8832ACBD |
| 8086:a102 | 15d9:0895 | Intel      | Q170/Q150/B150/H170/H110/... | 1     | ahci       | 5372999434 |
| 8086:a102 | 1734:1222 | Intel      | Q170/Q150/B150/H170/H110/... | 1     | ahci       | 0BD7D9FCEA |
| 8086:a102 | 8086:7270 | Intel      | Q170/Q150/B150/H170/H110/... | 1     | ahci       | 13B41B547A |
| 8086:a182 | 1028:0718 | Intel      | C620 Series Chipset Famil... | 1     | ahci       | 97313ACF09 |
| 8086:a182 | 1028:07cb | Intel      | C620 Series Chipset Famil... | 1     | ahci       | 5B9EC879FC |
| 8086:a182 | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 1     | ahci       | 0617E49F12 |
| 8086:a182 | 1043:871e | Intel      | C620 Series Chipset Famil... | 1     | ahci       | A1916FC246 |
| 8086:a182 | 15d9:095d | Intel      | C620 Series Chipset Famil... | 1     | ahci       | 2794B14FEE |
| 8086:a182 | 15d9:096d | Intel      | C620 Series Chipset Famil... | 1     | ahci       | DCFB9EE48A |
| 8086:a182 | 15d9:0987 | Intel      | C620 Series Chipset Famil... | 1     | ahci       | 893E9D69F2 |
| 8086:a1d2 | 1028:0718 | Intel      | C620 Series Chipset Famil... | 1     | ahci       | 97313ACF09 |
| 8086:a1d2 | 1028:07cb | Intel      | C620 Series Chipset Famil... | 1     | ahci       | 5B9EC879FC |
| 8086:a1d2 | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 1     | ahci       | 0617E49F12 |
| 8086:a1d2 | 1043:871f | Intel      | C620 Series Chipset Famil... | 1     | ahci       | A1916FC246 |
| 8086:a1d2 | 15d9:095d | Intel      | C620 Series Chipset Famil... | 1     | ahci       | 2794B14FEE |
| 8086:a1d2 | 15d9:096d | Intel      | C620 Series Chipset Famil... | 1     | ahci       | DCFB9EE48A |
| 8086:a1d2 | 15d9:0987 | Intel      | C620 Series Chipset Famil... | 1     | ahci       | 893E9D69F2 |
| 8086:a1d2 | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 1     | ahci       | ED799888EB |
| 8086:a282 | 15d9:098e | Intel      | 200 Series PCH SATA contr... | 1     | ahci       | 98ED2C77C7 |
| 8086:a352 | 15d9:1a1d | Intel      | Cannon Lake PCH SATA AHCI... | 1     | ahci       | 21E2FBBB75 |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3a20 | 103c:330d | Intel      | 82801JI (ICH10 Family) 4 ... | 5     | pata_acpi  | 6806624961 |
| 8086:1d00 | 103c:18a9 | Intel      | C600/X79 series chipset 4... | 3     | pata_acpi  | 07278BAD4B |
| 8086:2921 | 1028:0235 | Intel      | 82801IB (ICH9) 2 port SAT... | 3     | ata_piix   | ABCF5C7050 |
| 8086:2680 | 1028:01b2 | Intel      | 631xESB/632xESB/3100 Chip... | 2     | pata_acpi  | 1C2A92612A |
| 8086:2920 | 8086:34d0 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 2     | pata_acpi  | 81A05F54F2 |
| 8086:2926 | 8086:34d0 | Intel      | 82801I (ICH9 Family) 2 po... | 2     | pata_acpi  | 81A05F54F2 |
| 8086:3a20 | 1014:3a20 | Intel      | 82801JI (ICH10 Family) 4 ... | 2     | pata_acpi  | D804E1DA52 |
| 8086:3a20 | 8086:34da | Intel      | 82801JI (ICH10 Family) 4 ... | 2     | ata_pii... | DEC98C8F86 |
| 8086:3a20 | 8086:34dc | Intel      | 82801JI (ICH10 Family) 4 ... | 2     | ata_piix   | 138B84322E |
| 8086:3a20 | 8086:3a20 | Intel      | 82801JI (ICH10 Family) 4 ... | 2     | ata_pii... | 3D4DABE8D3 |
| 8086:3a26 | 1014:3a26 | Intel      | 82801JI (ICH10 Family) 2 ... | 2     | pata_acpi  | D804E1DA52 |
| 8086:3a26 | 8086:34da | Intel      | 82801JI (ICH10 Family) 2 ... | 2     | ata_pii... | DEC98C8F86 |
| 8086:3a26 | 8086:34dc | Intel      | 82801JI (ICH10 Family) 2 ... | 2     | ata_piix   | 138B84322E |
| 8086:3a26 | 8086:3a26 | Intel      | 82801JI (ICH10 Family) 2 ... | 2     | ata_pii... | 3D4DABE8D3 |
| 1002:439c | 103c:3338 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | pata_at... | 7CE46A749E |
| 1002:439c | 15d9:ab11 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | pata_at... | 463CF097DA |
| 1002:439c | 15d9:bc11 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | pata_at... | 7E28DD35AD |
| 10de:036e | 108e:534d | Nvidia     | MCP55 IDE                    | 1     | pata_am... | 1F35F79302 |
| 10de:037f | 108e:534d | Nvidia     | MCP55 SATA Controller        | 1     | sata_nv... | 1F35F79302 |
| 1166:0212 | 1166:0212 | Broadcom   | CSB5 IDE Controller          | 1     | pata_se... | 46973B5B05 |
| 1166:0214 | 1028:0205 | Broadcom   | BCM5785 [HT1000] IDE         | 1     | pata_se... | B7596E9C0E |
| 1166:024b | 1028:0205 | Broadcom   | BCM5785 [HT1000] SATA (PA... | 1     | sata_sv... | B7596E9C0E |
| 197b:2368 | 197b:2368 | JMicron... | JMB368 IDE controller        | 1     | pata_jm... | 68E0C84652 |
| 8086:1c00 | 1043:8498 | Intel      | 6 Series/C200 Series Chip... | 1     | pata_acpi  | AB7179BE16 |
| 8086:1c00 | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 1     | ata_pii... | D092DEFE79 |
| 8086:1c00 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     | pata_acpi  | D9F1CB21BC |
| 8086:1c08 | 1043:8497 | Intel      | 6 Series/C200 Series Chip... | 1     | pata_acpi  | AB7179BE16 |
| 8086:1c08 | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 1     | ata_pii... | D092DEFE79 |
| 8086:1c08 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     | pata_acpi  | D9F1CB21BC |
| 8086:24d1 | 103c:3208 | Intel      | 82801EB (ICH5) SATA Contr... | 1     | ata_pii... | 2C877CF870 |
| 8086:24d1 | 8086:3439 | Intel      | 82801EB (ICH5) SATA Contr... | 1     | pata_acpi  | 0F21E859FA |
| 8086:24db | 1028:016e | Intel      | 82801EB/ER (ICH5/ICH5R) I... | 1     | pata_acpi  | 76EF1C8CA9 |
| 8086:24db | 8086:3439 | Intel      | 82801EB/ER (ICH5/ICH5R) I... | 1     | pata_acpi  | 0F21E859FA |
| 8086:2680 | 1028:01b3 | Intel      | 631xESB/632xESB/3100 Chip... | 1     | pata_acpi  | 25731D395E |
| 8086:2680 | 8086:3476 | Intel      | 631xESB/632xESB/3100 Chip... | 1     | ata_pii... | 5229FAFC3E |
| 8086:2680 | 8086:3484 | Intel      | 631xESB/632xESB/3100 Chip... | 1     | pata_acpi  | 5C3DF14DAD |
| 8086:269e | 1028:01b2 | Intel      | 631xESB/632xESB IDE Contr... | 1     | pata_acpi  | 1C2A92612A |
| 8086:269e | 1028:01b3 | Intel      | 631xESB/632xESB IDE Contr... | 1     | pata_acpi  | 25731D395E |
| 8086:269e | 8086:3476 | Intel      | 631xESB/632xESB IDE Contr... | 1     | ata_pii... | 5229FAFC3E |
| 8086:269e | 8086:3484 | Intel      | 631xESB/632xESB IDE Contr... | 1     | pata_acpi  | 5C3DF14DAD |
| 8086:2921 | 1028:0236 | Intel      | 82801IB (ICH9) 2 port SAT... | 1     | pata_acpi  | 21EEA2083D |
| 8086:2921 | 1028:0237 | Intel      | 82801IB (ICH9) 2 port SAT... | 1     | ata_pii... | 3F4700F256 |
| 8086:3a20 | 1028:02d3 | Intel      | 82801JI (ICH10 Family) 4 ... | 1     | pata_acpi  | F33CE0F316 |
| 8086:3a20 | 1028:02f1 | Intel      | 82801JI (ICH10 Family) 4 ... | 1     | pata_acpi  | CBFB7C31D8 |
| 8086:3a20 | 1043:8362 | Intel      | 82801JI (ICH10 Family) 4 ... | 1     | pata_acpi  | 8681056F1F |
| 8086:3a20 | 15d9:0100 | Intel      | 82801JI (ICH10 Family) 4 ... | 1     | pata_acpi  | 68E0C84652 |
| 8086:3a20 | 15d9:0600 | Intel      | 82801JI (ICH10 Family) 4 ... | 1     | pata_acpi  | 7092025B53 |
| 8086:3a20 | 1734:1150 | Intel      | 82801JI (ICH10 Family) 4 ... | 1     | pata_acpi  | C7E9D74C3D |
| 8086:3a26 | 1028:02f1 | Intel      | 82801JI (ICH10 Family) 2 ... | 1     | pata_acpi  | CBFB7C31D8 |
| 8086:3a26 | 1043:8362 | Intel      | 82801JI (ICH10 Family) 2 ... | 1     | pata_acpi  | 8681056F1F |
| 8086:3a26 | 15d9:0100 | Intel      | 82801JI (ICH10 Family) 2 ... | 1     | pata_acpi  | 68E0C84652 |
| 8086:3a26 | 15d9:0600 | Intel      | 82801JI (ICH10 Family) 2 ... | 1     | pata_acpi  | 7092025B53 |
| 8086:3a26 | 1734:114d | Intel      | 82801JI (ICH10 Family) 2 ... | 1     | pata_acpi  | C7E9D74C3D |
| 8086:3b20 | 1014:0377 | Intel      | 5 Series/3400 Series Chip... | 1     | ata_pii... | E53A957D3F |
| 8086:3b20 | 1028:02a3 | Intel      | 5 Series/3400 Series Chip... | 1     | pata_acpi  | 0F9D97BC71 |
| 8086:3b26 | 1014:0377 | Intel      | 5 Series/3400 Series Chip... | 1     | ata_pii... | E53A957D3F |
| 8086:3b26 | 1028:02a3 | Intel      | 5 Series/3400 Series Chip... | 1     | pata_acpi  | 0F9D97BC71 |
| 8086:a1bc | 1028:0739 | Intel      | C620 Series Chipset Famil... | 1     | pata_acpi  | AD29AF92C2 |
| 8086:a1bc | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 1     | pata_acpi  | ED799888EB |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 11    | nvme       | 5B11F4C63C |
| 14a4:2300 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 6     | nvme       | 4391DFF8D2 |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 4     | nvme       | C392838A14 |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 1     | nvme       | 22AA6FF795 |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/PC SN720 NV... | 1     | nvme       | ED799888EB |
| 1987:5007 | 1987:5007 | Phison ... | E7 NVMe Controller           | 1     | nvme       | BB8832ACBD |
| 8086:2700 | 8086:3900 | Intel      | Optane SSD 900P Series       | 1     | nvme       | 481A638E26 |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 1     | nvme       | 73D514E056 |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1000:005d | 1000:9363 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 14    | megarai... | 57FC9BDF47 |
| 1000:0079 | 1000:9263 | LSI Log... | MegaRAID SAS 2108 [Libera... | 7     | megarai... | C60718AEF4 |
| 103c:323a | 103c:3245 | Hewlett... | Smart Array G6 controllers   | 7     | hpsa       | 6806624961 |
| 1000:005d | 15d9:0809 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 4     | megarai... | 6C96E4A591 |
| 1000:0060 | 1028:1f0c | LSI Log... | MegaRAID SAS 1078            | 4     | megarai... | ABCF5C7050 |
| 1000:0079 | 1028:1f17 | LSI Log... | MegaRAID SAS 2108 [Libera... | 4     | megarai... | F33CE0F316 |
| 1000:005d | 1028:1f47 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 3     | megarai... | D5DD49E570 |
| 103c:3239 | 103c:21c0 | Hewlett... | Smart Array Gen9 Controllers | 3     | hpsa       | C9D389B2A3 |
| 103c:323b | 103c:3354 | Hewlett... | Smart Array Gen8 Controllers | 3     | hpsa       | 07278BAD4B |
| 1000:005d | 1000:9361 | LSI Log... | MegaRAID SAS-3 3108 [Inva... | 2     | megarai... | AA728FD340 |
| 103c:323b | 103c:3350 | Hewlett... | Smart Array Gen8 Controllers | 2     | hpsa       | 9E2CA41ABB |
| 1590:0045 | 1590:0045 | Hewlett... | RAID bus controller          | 2     |            | 3FAC52AF81 |
| 1000:005b | 1000:9271 | Broadco... | MegaRAID SAS 2208 [Thunde... | 1     | megarai... | CEC82EF5D0 |
| 1000:005b | 1000:9276 | LSI Log... | MegaRAID SAS 2208 [Thunde... | 1     | megarai... | 5F9F099F36 |
| 1000:005b | 1014:040b | LSI Log... | MegaRAID SAS 2208 [Thunde... | 1     | megarai... | B55F7AE6F3 |
| 1000:005b | 1028:1f34 | LSI Log... | MegaRAID SAS 2208 [Thunde... | 1     | megarai... | A1EFBB1BE1 |
| 1000:005d | 1028:1f49 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | megarai... | AF9F6ACE3F |
| 1000:005d | 8086:9362 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | megarai... | 2794B14FEE |
| 1000:005f | 1014:0456 | LSI Log... | MegaRAID SAS-3 3008 [Fury]   | 1     | megarai... | 817865DED6 |
| 1000:005f | 1028:1f44 | LSI Log... | MegaRAID SAS-3 3008 [Fury]   | 1     | megarai... | 5B9EC879FC |
| 1000:005f | 1028:1f4b | LSI Log... | MegaRAID SAS-3 3008 [Fury]   | 1     | megarai... | FF3ACF2BDC |
| 1000:0060 | 1000:100a | Broadco... | MegaRAID SAS 1078            | 1     | megarai... | 5C3DF14DAD |
| 1000:0060 | 1028:1f0b | LSI Log... | MegaRAID SAS 1078            | 1     | megarai... | 4D09E718D8 |
| 1000:0060 | 1734:10f9 | Broadco... | MegaRAID SAS 1078            | 1     | megarai... | C7E9D74C3D |
| 1000:0073 | 1014:040d | Broadco... | MegaRAID SAS 2008 [Falcon]   | 1     | megarai... | DAA63A315C |
| 1000:0073 | 1028:1f51 | LSI Log... | MegaRAID SAS 2008 [Falcon]   | 1     | megarai... | B6374DF09A |
| 1000:0079 | 1000:9260 | LSI Log... | MegaRAID SAS 2108 [Libera... | 1     | megarai... | 17BF7A3CBC |
| 1000:0079 | 1000:9261 | LSI Log... | MegaRAID SAS 2108 [Libera... | 1     | megarai... | 9762DCCBE9 |
| 1000:0079 | 1014:03b2 | LSI Log... | MegaRAID SAS 2108 [Libera... | 1     | megarai... | D804E1DA52 |
| 1002:4392 | 15d9:ab11 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 463CF097DA |
| 1028:0016 | 1028:1f24 | Dell       | PowerEdge Expandable RAID... | 1     |            | 389DD308F7 |
| 103c:323a | 103c:3243 | Hewlett... | Smart Array G6 controllers   | 1     | hpsa       | 7CE46A749E |
| 103c:323b | 103c:3351 | Hewlett... | Smart Array Gen8 Controllers | 1     | hpsa       | 2B50D6A636 |
| 1095:3132 | 1095:7132 | Silicon... | SiI 3132 Serial ATA Raid ... | 1     | sata_sil24 | CBBE408AAC |
| 17d3:1880 | 17d3:1882 | Areca T... | ARC-188x series PCIe 2.0/... | 1     | arcmsr     | 018029FB72 |
| 8086:1c04 | 1028:04de | Intel      | 6 Series/C200 Series Desk... | 1     | ahci       | 342271719A |
| 8086:201d | 8086:0000 | Intel      | Skylake-E RSTe Volume Man... | 1     | vmd        | AD29AF92C2 |
| 8086:2822 | 8086:34d1 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | 9A27511AEB |
| 8086:2826 | 1028:0739 | Intel      | C600/X79 series chipset S... | 1     | ahci       | AD29AF92C2 |
| 8086:2826 | 15d9:0802 | Intel      | C600/X79 series chipset S... | 1     | ahci       | 7115F8FDB7 |
| 8086:2826 | 15d9:0834 | Intel      | C600/X79 series chipset S... | 1     | ahci       | EEE6327556 |
| 8086:2826 | 15d9:0857 | Intel      | C600/X79 series chipset S... | 1     | ahci       | 22AA6FF795 |
| 8086:2826 | 15d9:089f | Intel      | C600/X79 series chipset S... | 1     | ahci       | C392838A14 |
| 8086:2826 | 17aa:1038 | Intel      | C600/X79 series chipset S... | 1     | ahci       | ED799888EB |
| 8086:2826 | 8086:2826 | Intel      | C600/X79 series chipset S... | 1     | ahci       | 53D66D8AB3 |
| 8086:2827 | 8086:7270 | Intel      | C610/X99 series chipset s... | 1     | ahci       | EDE05678EF |
| 8086:3a25 | 8086:34dd | Intel      | 82801JIR (ICH10R) SATA RA... | 1     | ahci       | CBBE408AAC |
| 8086:3b25 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 1     | ahci       | 4D09E718D8 |
| 8086:8d06 | 8086:35c0 | Intel      | C610/X99 series chipset S... | 1     | ahci       | 08100751B7 |
| 9005:0285 | 9005:02d8 | Adaptec    | AAC-RAID                     | 1     | aacraid    | 138B84322E |
| 9005:028d | 9005:0557 | Adaptec    | Series 8 12G SAS/PCIe 3      | 1     | aacraid    | 5372999434 |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2016 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 29    |            | 8E73F804F5 |
| 8086:2018 | 8086:0000 | Intel      | Sky Lake-E M2PCI Registers   | 29    |            | 8E73F804F5 |
| 8086:2025 |           | Intel      | Sky Lake-E RAS               | 29    |            | 8E73F804F5 |
| 8086:2034 | 8086:0000 | Intel      | Sky Lake-E VT-d              | 29    |            | 8E73F804F5 |
| 8086:2035 |           | Intel      | Sky Lake-E RAS Configurat... | 29    |            | 8E73F804F5 |
| 8086:2040 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 29    |            | 8E73F804F5 |
| 8086:2041 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 29    |            | 8E73F804F5 |
| 8086:2042 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 29    | skx_uncore | 8E73F804F5 |
| 8086:2043 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 29    |            | 8E73F804F5 |
| 8086:2044 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 29    |            | 8E73F804F5 |
| 8086:2045 | 8086:0000 | Intel      | Sky Lake-E LM Channel 1      | 29    |            | 8E73F804F5 |
| 8086:2046 | 8086:0000 | Intel      | Sky Lake-E LMS Channel 1     | 29    | skx_uncore | 8E73F804F5 |
| 8086:2047 | 8086:0000 | Intel      | Sky Lake-E LMDP Channel 1    | 29    |            | 8E73F804F5 |
| 8086:2048 | 8086:0000 | Intel      | Sky Lake-E DECS Channel 2    | 29    |            | 8E73F804F5 |
| 8086:2049 | 8086:0000 | Intel      | Sky Lake-E LM Channel 2      | 29    |            | 8E73F804F5 |
| 8086:204a | 8086:0000 | Intel      | Sky Lake-E LMS Channel 2     | 29    | skx_uncore | 8E73F804F5 |
| 8086:204b | 8086:0000 | Intel      | Sky Lake-E LMDP Channel 2    | 29    |            | 8E73F804F5 |
| 8086:204e | 8086:0000 | Intel      | Sky Lake-E M3KTI Registers   | 29    | skx_uncore | 8E73F804F5 |
| 8086:2054 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 29    |            | 8E73F804F5 |
| 8086:2055 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 29    |            | 8E73F804F5 |
| 8086:2056 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 29    |            | 8E73F804F5 |
| 8086:2057 | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 29    |            | 8E73F804F5 |
| 8086:2066 | 8086:0000 | Intel      | Sky Lake-E Integrated Mem... | 29    | skx_uncore | 8E73F804F5 |
| 8086:2080 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 29    |            | 8E73F804F5 |
| 8086:2081 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 29    |            | 8E73F804F5 |
| 8086:2082 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 29    |            | 8E73F804F5 |
| 8086:2083 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 29    |            | 8E73F804F5 |
| 8086:2084 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 29    |            | 8E73F804F5 |
| 8086:2085 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 29    |            | 8E73F804F5 |
| 8086:2086 | 8086:0000 | Intel      | Sky Lake-E PCU Registers     | 29    |            | 8E73F804F5 |
| 8086:208d | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 29    |            | 8E73F804F5 |
| 8086:208e | 8086:0000 | Intel      | Sky Lake-E CHA Registers     | 29    |            | 8E73F804F5 |
| 8086:2014 | 8086:0000 | Intel      | Sky Lake-E Ubox Registers    | 28    |            | 8E73F804F5 |
| 8086:2024 | 8086:0000 | Intel      | Sky Lake-E MM/Vt-d Config... | 28    |            | 8E73F804F5 |
| 8086:2021 | 8086:0000 | Intel      | Sky Lake-E CBDMA Registers   | 27    | ioatdma    | 8E73F804F5 |
| 8086:2059 | 8086:0000 | Intel      | Sky Lake-E UPI Registers     | 27    |            | 8E73F804F5 |
| 8086:6f76 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 24    |            | 140DAF886E |
| 8086:6f88 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 24    |            | 140DAF886E |
| 8086:6f8a |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 24    |            | 140DAF886E |
| 8086:6fae |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 24    |            | 140DAF886E |
| 8086:6faf |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 24    |            | 140DAF886E |
| 8086:6fbc |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 24    |            | 140DAF886E |
| 8086:6fbd |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 24    |            | 140DAF886E |
| 8086:6fbe |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 24    |            | 140DAF886E |
| 8086:6fbf |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 24    |            | 140DAF886E |
| 8086:6f68 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 140DAF886E |
| 8086:6f6e |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 140DAF886E |
| 8086:6f6f |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 140DAF886E |
| 8086:6fb8 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 140DAF886E |
| 8086:6fb9 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 140DAF886E |
| 8086:6fba |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 140DAF886E |
| 8086:6fbb |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 140DAF886E |
| 8086:6fd0 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    | bdx_uncore | 140DAF886E |
| 8086:2f6e |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 18    |            | D05461EFDA |
| 8086:2f6f |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 18    |            | D05461EFDA |
| 8086:2f88 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 18    |            | D05461EFDA |
| 8086:2f8a |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 18    |            | D05461EFDA |
| 8086:2fae |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 18    |            | D05461EFDA |
| 8086:2faf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 18    |            | D05461EFDA |
| 8086:2fb8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 18    |            | D05461EFDA |
| 8086:2fb9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 18    |            | D05461EFDA |
| 8086:2fba |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 18    |            | D05461EFDA |
| 8086:2fbb |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 18    |            | D05461EFDA |
| 8086:2fbe |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 18    |            | D05461EFDA |
| 8086:2fbf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 18    |            | D05461EFDA |
| 8086:2ff8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 18    |            | D05461EFDA |
| 8086:2ff9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 18    |            | D05461EFDA |
| 8086:6f1d | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6f1e | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6f1f | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6f20 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | ioatdma    | 17BF7A3CBC |
| 8086:6f21 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | ioatdma    | 17BF7A3CBC |
| 8086:6f22 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | ioatdma    | 17BF7A3CBC |
| 8086:6f23 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | ioatdma    | 17BF7A3CBC |
| 8086:6f24 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | ioatdma    | 17BF7A3CBC |
| 8086:6f25 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | ioatdma    | 17BF7A3CBC |
| 8086:6f26 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | ioatdma    | 17BF7A3CBC |
| 8086:6f27 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | ioatdma    | 17BF7A3CBC |
| 8086:6f28 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6f29 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6f2a | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6f71 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6f81 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6f98 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6f99 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6f9a | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6f9c | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6fa0 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6fa8 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6faa | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6fab | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6fac | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6fad | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6fb0 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6fb1 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6fb2 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6fb3 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |
| 8086:6fb4 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6fb5 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    | bdx_uncore | 17BF7A3CBC |
| 8086:6fb6 | 15d9:0821 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 16    |            | 17BF7A3CBC |

### Tv card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 109e:036e | 0070:ff04 | Brooktree  | Bt878 Video Capture          | 1     | bttv       | 2C877CF870 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8d26 | 15d9:0821 | Intel      | C610/X99 series chipset U... | 16    | ehci_pci   | 17BF7A3CBC |
| 8086:8d2d | 15d9:0821 | Intel      | C610/X99 series chipset U... | 16    | ehci_pci   | 17BF7A3CBC |
| 8086:8d31 | 15d9:0821 | Intel      | C610/X99 series chipset U... | 16    | xhci_hcd   | 17BF7A3CBC |
| 8086:a1af | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    | xhci_hcd   | 4391DFF8D2 |
| 103c:3300 | 103c:3381 | Hewlett... | Integrated Lights-Out Sta... | 13    | uhci_hcd   | 140DAF886E |
| 8086:3a34 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 11    | uhci_hcd   | 726EA75DCA |
| 8086:3a35 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 11    | uhci_hcd   | 726EA75DCA |
| 8086:3a36 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 11    | uhci_hcd   | 726EA75DCA |
| 8086:3a37 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 11    | uhci_hcd   | 726EA75DCA |
| 8086:3a38 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 11    | uhci_hcd   | 726EA75DCA |
| 8086:3a39 | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 11    | uhci_hcd   | 726EA75DCA |
| 8086:3a3a | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 11    | ehci_hcd   | 726EA75DCA |
| 8086:3a3c | 15d9:0006 | Intel      | 82801JI (ICH10 Family) US... | 11    | ehci_hcd   | 726EA75DCA |
| 8086:1d26 | 103c:18a9 | Intel      | C600/X79 series chipset U... | 8     | ehci_hcd   | 07278BAD4B |
| 8086:1d2d | 103c:18a9 | Intel      | C600/X79 series chipset U... | 8     | ehci_hcd   | 07278BAD4B |
| 8086:3a34 | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 7     | uhci_hcd   | 6806624961 |
| 8086:3a35 | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 7     | uhci_hcd   | 6806624961 |
| 8086:3a36 | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 7     | uhci_hcd   | 6806624961 |
| 8086:3a39 | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 7     | uhci_hcd   | 6806624961 |
| 8086:3a3a | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 7     | ehci_pci   | 6806624961 |
| 8086:a1af | 8086:7270 | Intel      | C620 Series Chipset Famil... | 5     | xhci_hcd   | 8E73F804F5 |
| 103c:3300 | 103c:3309 | Hewlett... | Integrated Lights-Out Sta... | 4     | uhci_hcd   | 179B0500B3 |
| 8086:3a34 | 15d9:060f | Intel      | 82801JI (ICH10 Family) US... | 4     | uhci_hcd   | 1D3C1DC3BF |
| 8086:3a35 | 15d9:060f | Intel      | 82801JI (ICH10 Family) US... | 4     | uhci_hcd   | 1D3C1DC3BF |
| 8086:3a36 | 15d9:060f | Intel      | 82801JI (ICH10 Family) US... | 4     | uhci_hcd   | 1D3C1DC3BF |
| 8086:3a37 | 15d9:060f | Intel      | 82801JI (ICH10 Family) US... | 4     | uhci_hcd   | 1D3C1DC3BF |
| 8086:3a38 | 15d9:060f | Intel      | 82801JI (ICH10 Family) US... | 4     | uhci_hcd   | 1D3C1DC3BF |
| 8086:3a39 | 15d9:060f | Intel      | 82801JI (ICH10 Family) US... | 4     | uhci_hcd   | 1D3C1DC3BF |
| 8086:3a3a | 15d9:060f | Intel      | 82801JI (ICH10 Family) US... | 4     | ehci_pci   | 1D3C1DC3BF |
| 8086:3a3c | 15d9:060f | Intel      | 82801JI (ICH10 Family) US... | 4     | ehci_pci   | 1D3C1DC3BF |
| 8086:8d26 | 103c:8030 | Intel      | C610/X99 series chipset U... | 4     | ehci_pci   | 140DAF886E |
| 8086:8d2d | 103c:8030 | Intel      | C610/X99 series chipset U... | 4     | ehci_pci   | 140DAF886E |
| 8086:8d31 | 103c:8030 | Intel      | C610/X99 series chipset U... | 4     | xhci_hcd   | 140DAF886E |
| 103c:3300 | 103c:3305 | Hewlett... | Integrated Lights-Out Sta... | 3     | uhci_hcd   | 6806624961 |
| 1b21:1142 | 1b21:1142 | ASMedia... | ASM1042A USB 3.0 Host Con... | 3     | xhci_hcd   | D05461EFDA |
| 8086:1c26 | 1043:8497 | Intel      | 6 Series/C200 Series Chip... | 3     | ehci_hc... | AB7179BE16 |
| 8086:1c2d | 1043:8497 | Intel      | 6 Series/C200 Series Chip... | 3     | ehci_hc... | AB7179BE16 |
| 8086:1d26 | 1043:84ef | Intel      | C600/X79 series chipset U... | 3     | ehci_pci   | 996F55BB36 |
| 8086:1d26 | 15d9:0636 | Intel      | C600/X79 series chipset U... | 3     | ehci_hcd   | 100EFA1F4A |
| 8086:1d26 | 8086:357e | Intel      | C600/X79 series chipset U... | 3     | ehci_pci   | F65EC09250 |
| 8086:1d2d | 1043:84ef | Intel      | C600/X79 series chipset U... | 3     | ehci_pci   | 996F55BB36 |
| 8086:1d2d | 15d9:0636 | Intel      | C600/X79 series chipset U... | 3     | ehci_hcd   | 100EFA1F4A |
| 8086:1d2d | 8086:357e | Intel      | C600/X79 series chipset U... | 3     | ehci_pci   | F65EC09250 |
| 8086:2934 | 1028:0235 | Intel      | 82801I (ICH9 Family) USB ... | 3     | uhci_hcd   | ABCF5C7050 |
| 8086:2935 | 1028:0235 | Intel      | 82801I (ICH9 Family) USB ... | 3     | uhci_hcd   | ABCF5C7050 |
| 8086:2937 | 1028:0235 | Intel      | 82801I (ICH9 Family) USB ... | 3     | uhci_hcd   | ABCF5C7050 |
| 8086:2938 | 1028:0235 | Intel      | 82801I (ICH9 Family) USB ... | 3     | uhci_hcd   | ABCF5C7050 |
| 8086:293a | 1028:0235 | Intel      | 82801I (ICH9 Family) USB2... | 3     | ehci_pci   | ABCF5C7050 |
| 8086:293c | 1028:0235 | Intel      | 82801I (ICH9 Family) USB2... | 3     | ehci_pci   | ABCF5C7050 |
| 8086:3a34 | 8086:34dc | Intel      | 82801JI (ICH10 Family) US... | 3     | uhci_hcd   | 138B84322E |
| 8086:3a35 | 8086:34dc | Intel      | 82801JI (ICH10 Family) US... | 3     | uhci_hcd   | 138B84322E |
| 8086:3a36 | 8086:34dc | Intel      | 82801JI (ICH10 Family) US... | 3     | uhci_hcd   | 138B84322E |
| 8086:3a37 | 8086:34dc | Intel      | 82801JI (ICH10 Family) US... | 3     | uhci_hcd   | 138B84322E |
| 8086:3a38 | 8086:34dc | Intel      | 82801JI (ICH10 Family) US... | 3     | uhci_hcd   | 138B84322E |
| 8086:3a39 | 8086:34dc | Intel      | 82801JI (ICH10 Family) US... | 3     | uhci_hcd   | 138B84322E |
| 8086:3a3a | 8086:34dc | Intel      | 82801JI (ICH10 Family) US... | 3     | ehci_pci   | 138B84322E |
| 8086:3a3c | 8086:34dc | Intel      | 82801JI (ICH10 Family) US... | 3     | ehci_pci   | 138B84322E |
| 8086:8d26 | 1028:0601 | Intel      | C610/X99 series chipset U... | 3     | ehci_pci   | AF9F6ACE3F |
| 8086:8d26 | 15d9:0857 | Intel      | C610/X99 series chipset U... | 3     | ehci_pci   | D05461EFDA |
| 8086:8d26 | 8086:7270 | Intel      | C610/X99 series chipset U... | 3     | ehci_pci   | 7658F21E98 |
| 8086:8d2d | 1028:0601 | Intel      | C610/X99 series chipset U... | 3     | ehci_pci   | AF9F6ACE3F |
| 8086:8d2d | 15d9:0857 | Intel      | C610/X99 series chipset U... | 3     | ehci_pci   | D05461EFDA |
| 8086:8d2d | 8086:7270 | Intel      | C610/X99 series chipset U... | 3     | ehci_pci   | 7658F21E98 |
| 8086:8d31 | 15d9:0857 | Intel      | C610/X99 series chipset U... | 3     | xhci_hcd   | D05461EFDA |
| 1022:7908 | 1022:7908 | AMD        | FCH USB EHCI Controller      | 2     | ehci_pci   | 4B4029781F |
| 1022:7914 | 1022:7914 | AMD        | FCH USB XHCI Controller      | 2     | xhci_hcd   | 4B4029781F |
| 1033:0194 | ffff:ffff | NEC Com... | uPD720200 USB 3.0 Host Co... | 2     | xhci_hcd   | 3F6EE4141E |
| 1b21:1042 | 1043:8488 | ASMedia... | ASM1042 SuperSpeed USB Ho... | 2     | xhci_hcd   | 90D8E62525 |
| 8086:1c26 | 1028:04de | Intel      | 6 Series/C200 Series Chip... | 2     | ehci_pci   | 389DD308F7 |
| 8086:1c26 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 2     | ehci_pci   | DAA63A315C |
| 8086:1c2d | 1028:04de | Intel      | 6 Series/C200 Series Chip... | 2     | ehci_pci   | 389DD308F7 |
| 8086:1c2d | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 2     | ehci_pci   | DAA63A315C |
| 8086:1d26 | 1014:1d26 | Intel      | C600/X79 series chipset U... | 2     | ehci_pci   | B55F7AE6F3 |
| 8086:1d2d | 1014:1d2d | Intel      | C600/X79 series chipset U... | 2     | ehci_pci   | B55F7AE6F3 |
| 8086:2688 | 1028:01b2 | Intel      | 631xESB/632xESB/3100 Chip... | 2     | uhci_hcd   | 1C2A92612A |
| 8086:2689 | 1028:01b2 | Intel      | 631xESB/632xESB/3100 Chip... | 2     | uhci_hcd   | 1C2A92612A |
| 8086:268a | 1028:01b2 | Intel      | 631xESB/632xESB/3100 Chip... | 2     | uhci_hcd   | 1C2A92612A |
| 8086:268b | 1028:01b2 | Intel      | 631xESB/632xESB/3100 Chip... | 2     | uhci_hcd   | 1C2A92612A |
| 8086:268c | 1028:01b2 | Intel      | 631xESB/632xESB/3100 Chip... | 2     | ehci_pci   | 1C2A92612A |
| 8086:2934 | 8086:34d0 | Intel      | 82801I (ICH9 Family) USB ... | 2     | uhci_hcd   | 81A05F54F2 |
| 8086:2935 | 8086:34d0 | Intel      | 82801I (ICH9 Family) USB ... | 2     | uhci_hcd   | 81A05F54F2 |
| 8086:2936 | 8086:34d0 | Intel      | 82801I (ICH9 Family) USB ... | 2     | uhci_hcd   | 81A05F54F2 |
| 8086:2937 | 8086:34d0 | Intel      | 82801I (ICH9 Family) USB ... | 2     | uhci_hcd   | 81A05F54F2 |
| 8086:2938 | 8086:34d0 | Intel      | 82801I (ICH9 Family) USB ... | 2     | uhci_hcd   | 81A05F54F2 |
| 8086:293a | 8086:34d0 | Intel      | 82801I (ICH9 Family) USB2... | 2     | ehci_pci   | 81A05F54F2 |
| 8086:293c | 8086:34d0 | Intel      | 82801I (ICH9 Family) USB2... | 2     | ehci_pci   | 81A05F54F2 |
| 8086:3a34 | 1014:3a34 | Intel      | 82801JI (ICH10 Family) US... | 2     | uhci_hcd   | D804E1DA52 |
| 8086:3a34 | 15d9:0600 | Intel      | 82801JI (ICH10 Family) US... | 2     | uhci_hcd   | 8C854FDF21 |
| 8086:3a34 | 8086:34da | Intel      | 82801JI (ICH10 Family) US... | 2     | uhci_hcd   | DEC98C8F86 |
| 8086:3a34 | 8086:3a34 | Intel      | 82801JI (ICH10 Family) US... | 2     | uhci_hcd   | 3D4DABE8D3 |
| 8086:3a35 | 1014:3a35 | Intel      | 82801JI (ICH10 Family) US... | 2     | uhci_hcd   | D804E1DA52 |
| 8086:3a35 | 15d9:0600 | Intel      | 82801JI (ICH10 Family) US... | 2     | uhci_hcd   | 8C854FDF21 |
| 8086:3a35 | 8086:34da | Intel      | 82801JI (ICH10 Family) US... | 2     | uhci_hcd   | DEC98C8F86 |
| 8086:3a35 | 8086:3a35 | Intel      | 82801JI (ICH10 Family) US... | 2     | uhci_hcd   | 3D4DABE8D3 |
| 8086:3a36 | 1014:3a36 | Intel      | 82801JI (ICH10 Family) US... | 2     | uhci_hcd   | D804E1DA52 |
| 8086:3a36 | 15d9:0600 | Intel      | 82801JI (ICH10 Family) US... | 2     | uhci_hcd   | 8C854FDF21 |
| 8086:3a36 | 8086:34da | Intel      | 82801JI (ICH10 Family) US... | 2     | uhci_hcd   | DEC98C8F86 |
| 8086:3a36 | 8086:3a36 | Intel      | 82801JI (ICH10 Family) US... | 2     | uhci_hcd   | 3D4DABE8D3 |
| 8086:3a37 | 1014:3a37 | Intel      | 82801JI (ICH10 Family) US... | 2     | uhci_hcd   | D804E1DA52 |
| 8086:3a37 | 15d9:0600 | Intel      | 82801JI (ICH10 Family) US... | 2     | uhci_hcd   | 8C854FDF21 |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8d7c | 15d9:0821 | Intel      | C610/X99 series chipset SPSR | 16    |            | 17BF7A3CBC |
| 8086:a1ec | 8086:35ce | Intel      | C620 Series Chipset Famil... | 16    |            | 4391DFF8D2 |
| 8086:a1ec | 8086:7270 | Intel      | C620 Series Chipset Famil... | 5     |            | 8E73F804F5 |
| 8086:8d7c | 103c:8030 | Intel      | C610/X99 series chipset SPSR | 4     |            | 140DAF886E |
| 8086:a1ed | 8086:7270 | Intel      | C620 Series Chipset Famil... | 4     |            | 8E73F804F5 |
| 8086:8d7c | 1028:0601 | Intel      | C610/X99 series chipset SPSR | 3     |            | AF9F6ACE3F |
| 8086:8d7c | 15d9:0857 | Intel      | C610/X99 series chipset SPSR | 3     |            | D05461EFDA |
| 8086:8d7c | 8086:7270 | Intel      | C610/X99 series chipset SPSR | 3     |            | 7658F21E98 |
| 8086:8d7c | 15d9:0824 | Intel      | C610/X99 series chipset SPSR | 2     |            | 6C96E4A591 |
| 8086:8d7c | 15d9:0831 | Intel      | C610/X99 series chipset SPSR | 2     |            | 52D5275C7F |
| 8086:8d7c | 8086:0000 | Intel      | C610/X99 series chipset SPSR | 2     |            | 5F9F099F36 |
| 1000:fury | 1014:0456 | LSI Log... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 817865DED6 |
| 1000:fury | 1028:1f44 | LSI Log... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | 5B9EC879FC |
| 1000:fury | 1028:1f4b | LSI Log... | MegaRAID SAS-3 3008 [005f]   | 1     | megarai... | FF3ACF2BDC |
| 1166:0140 | 0000:0000 | Broadcom   | HT2100 PCI-Express Bridge    | 1     | shpchp     | B7596E9C0E |
| 1912:001b | 1d49:0a02 | Renesas... | SH7758 PCIe End-Point [PBI]  | 1     |            | 817865DED6 |
| 1a41:0200 |           | Tilera     | TILE-Gx processor            | 1     | tilegxpci  | 08100751B7 |
| 1a41:0201 |           | Tilera     | TILE-Gx Processor Virtual... | 1     |            | 08100751B7 |
| 8086:3591 | 103c:3208 | Intel      | E7525/E7520 Error Reporti... | 1     |            | 2C877CF870 |
| 8086:3591 | 8086:3439 | Intel      | E7525/E7520 Error Reporti... | 1     |            | 0F21E859FA |
| 8086:8d7c | 1028:0639 | Intel      | C610/X99 series chipset SPSR | 1     |            | 3BA1B5FC84 |
| 8086:8d7c | 1028:063a | Intel      | C610/X99 series chipset SPSR | 1     |            | FF3ACF2BDC |
| 8086:8d7c | 1043:85f6 | Intel      | C610/X99 series chipset SPSR | 1     |            | FD500E59D6 |
| 8086:8d7c | 15d9:0834 | Intel      | C610/X99 series chipset SPSR | 1     |            | EEE6327556 |
| 8086:8d7c | 15d9:0835 | Intel      | C610/X99 series chipset SPSR | 1     |            | 7479576DA8 |
| 8086:8d7c | 1d49:0a00 | Intel      | C610/X99 series chipset SPSR | 1     |            | 817865DED6 |
| 8086:a1ec | 1028:0718 | Intel      | C620 Series Chipset Famil... | 1     |            | 97313ACF09 |
| 8086:a1ec | 1028:0739 | Intel      | C620 Series Chipset Famil... | 1     |            | AD29AF92C2 |
| 8086:a1ec | 1028:07cb | Intel      | C620 Series Chipset Famil... | 1     |            | 5B9EC879FC |
| 8086:a1ec | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 1     |            | 0617E49F12 |
| 8086:a1ec | 1043:871e | Intel      | C620 Series Chipset Famil... | 1     |            | A1916FC246 |
| 8086:a1ec | 1590:00eb | Intel      | C620 Series Chipset Famil... | 1     |            | 9E91D0ED19 |
| 8086:a1ec | 15d9:095d | Intel      | C620 Series Chipset Famil... | 1     |            | 2794B14FEE |
| 8086:a1ec | 15d9:096d | Intel      | C620 Series Chipset Famil... | 1     |            | DCFB9EE48A |
| 8086:a1ec | 15d9:0987 | Intel      | C620 Series Chipset Famil... | 1     |            | 893E9D69F2 |
| 8086:a1ec | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 1     |            | ED799888EB |
| 8086:a1ed | 1028:0739 | Intel      | C620 Series Chipset Famil... | 1     |            | AD29AF92C2 |
| 8086:a1ed | 103c:81c7 | Intel      | C620 Series Chipset Famil... | 1     |            | 0617E49F12 |
| 8086:a1ed | 1590:00eb | Intel      | C620 Series Chipset Famil... | 1     |            | 9E91D0ED19 |
| 8086:a1ed | 15d9:095d | Intel      | C620 Series Chipset Famil... | 1     |            | 2794B14FEE |
| 8086:a1ed | 15d9:096d | Intel      | C620 Series Chipset Famil... | 1     |            | DCFB9EE48A |
| 8086:a1ed | 15d9:0987 | Intel      | C620 Series Chipset Famil... | 1     |            | 893E9D69F2 |
| 8086:a1ed | 17aa:1038 | Intel      | C620 Series Chipset Famil... | 1     |            | ED799888EB |
| 8086:a1ed | 8086:a1ed | Intel      | C620 Series Chipset Famil... | 1     |            | F823B40D84 |

