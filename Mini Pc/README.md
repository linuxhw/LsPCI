Most popular PCI devices in Mini Pcs
------------------------------------

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Mini Pcs ](#pci-devices)
   * [ Bluetooth ](#bluetooth-pci)
   * [ Bridge ](#bridge-pci)
   * [ Canbus ](#canbus-pci)
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
| 1814:3298 | 1a3b:2987 | Ralink           | RT3290 Bluetooth                     | 4     |            | [3A6297D90B](<Mini Pc/ZOTAC/ZBOXNANO-AD/ZBOXNANO-AD12/1942AB43E912/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/3A6297D90B>) |

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d84 | 8086:2074 | Intel            | Cannon Point-LP LPC Controller       | 207   |            | [A92B4A305F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/21A3465BD54D/DEBIAN-11/5.10.0-21-AMD64/X86_64/A92B4A305F>) |
| 8086:9db8 | 8086:2074 | Intel            | Cannon Point-LP PCI Express Root ... | 206   | pcieport   | [A92B4A305F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/21A3465BD54D/DEBIAN-11/5.10.0-21-AMD64/X86_64/A92B4A305F>) |
| 8086:9dbc | 8086:2074 | Intel            | Cannon Point-LP PCI Express Root ... | 206   | pcieport   | [A92B4A305F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/21A3465BD54D/DEBIAN-11/5.10.0-21-AMD64/X86_64/A92B4A305F>) |
| 8086:9db0 | 8086:2074 | Intel            | Cannon Point-LP PCI Express Root ... | 204   | pcieport   | [A92B4A305F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/21A3465BD54D/DEBIAN-11/5.10.0-21-AMD64/X86_64/A92B4A305F>) |
| 8086:9db6 | 8086:2074 | Intel            | Cannon Point-LP PCI Express Root ... | 201   | pcieport   | [A92B4A305F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/21A3465BD54D/DEBIAN-11/5.10.0-21-AMD64/X86_64/A92B4A305F>) |
| 1022:1632 |           | AMD              | Renoir PCIe Dummy Host Bridge        | 157   |            | [6097531BFC](<Mini Pc/AZW/SER/SER/0FDA0A46CA08/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/6097531BFC>) |
| 1022:1635 | 1022:1635 | AMD              | Renoir Internal PCIe GPP Bridge t... | 146   | pcieport   | [6097531BFC](<Mini Pc/AZW/SER/SER/0FDA0A46CA08/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/6097531BFC>) |
| 8086:3ed0 | 8086:2074 | Intel            | 8th Gen Core Processor Host Bridg... | 145   | skl_uncore | [A92B4A305F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/21A3465BD54D/DEBIAN-11/5.10.0-21-AMD64/X86_64/A92B4A305F>) |
| 1022:1630 | 1022:1630 | AMD              | Renoir/Cezanne Root Complex          | 141   |            | [6097531BFC](<Mini Pc/AZW/SER/SER/0FDA0A46CA08/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/6097531BFC>) |
| 8086:0284 | 8086:2081 | Intel            | Comet Lake PCH-LP LPC Premium Con... | 123   |            | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 8086:02b5 | 8086:2081 | Intel            | Comet Lake PCH-LP PCIe Port #14      | 119   | pcieport   | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 8086:02bc | 8086:2081 | Intel            | Comet Lake PCI Express Root Port #5  | 119   | pcieport   | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 8086:15e7 | 8086:2081 | Intel            | JHL7540 Thunderbolt 3 Bridge [Tit... | 119   | pcieport   | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 8086:5904 | 8086:2068 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 105   | skl_uncore | [05B1BDF24D](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/5A48D52A7EDA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/05B1BDF24D>) |
| 8086:9d10 | 8086:2068 | Intel            | Sunrise Point-LP PCI Express Root... | 105   | pcieport   | [05B1BDF24D](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/5A48D52A7EDA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/05B1BDF24D>) |
| 8086:9d4e | 8086:2068 | Intel            | Sunrise Point LPC Controller/eSPI... | 105   |            | [05B1BDF24D](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/5A48D52A7EDA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/05B1BDF24D>) |
| 8086:31f0 |           | Intel            | Gemini Lake Host Bridge              | 104   |            | [BB29A94285](<Mini Pc/Hewlett-Packard/t430/t430 Thin Client/96DF0C529E2C/DEBIAN-11/5.10.0-22-AMD64/X86_64/BB29A94285>) |
| 8086:9d17 | 8086:2068 | Intel            | Sunrise Point-LP PCI Express Root... | 102   | pcieport   | [05B1BDF24D](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/5A48D52A7EDA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/05B1BDF24D>) |
| 8086:0f00 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 99    | iosf_mb... | [1F19B2C0DC](<Mini Pc/AMI/Aptio/Aptio CRB/E8C182707BA0/DEBIAN-11/5.10.0-21-AMD64/X86_64/1F19B2C0DC>) |
| 8086:0f1c | 8086:0f1c | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 99    | lpc_ich    | [1F19B2C0DC](<Mini Pc/AMI/Aptio/Aptio CRB/E8C182707BA0/DEBIAN-11/5.10.0-21-AMD64/X86_64/1F19B2C0DC>) |
| 8086:9d15 | 8086:2068 | Intel            | Sunrise Point-LP PCI Express Root... | 99    | pcieport   | [05B1BDF24D](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/5A48D52A7EDA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/05B1BDF24D>) |
| 1022:790e | 1022:790e | AMD              | FCH LPC Bridge                       | 97    |            | [6097531BFC](<Mini Pc/AZW/SER/SER/0FDA0A46CA08/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/6097531BFC>) |
| 8086:02b0 | 8086:2081 | Intel            | Comet Lake PCI Express Root Port #9  | 93    | pcieport   | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 1022:1448 |           | AMD              | Renoir Device 24: Function 0         | 90    |            | [C1BF3A9C44](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/24AA08459D0E/DEBIAN-11/5.10.0-20-AMD64/X86_64/C1BF3A9C44>) |
| 1022:1449 |           | AMD              | Renoir Device 24: Function 1         | 90    |            | [C1BF3A9C44](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/24AA08459D0E/DEBIAN-11/5.10.0-20-AMD64/X86_64/C1BF3A9C44>) |
| 1022:144a |           | AMD              | Renoir Device 24: Function 2         | 90    |            | [C1BF3A9C44](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/24AA08459D0E/DEBIAN-11/5.10.0-20-AMD64/X86_64/C1BF3A9C44>) |
| 1022:144b |           | AMD              | Renoir Device 24: Function 3         | 90    | k10temp    | [C1BF3A9C44](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/24AA08459D0E/DEBIAN-11/5.10.0-20-AMD64/X86_64/C1BF3A9C44>) |
| 1022:144c |           | AMD              | Renoir Device 24: Function 4         | 90    |            | [C1BF3A9C44](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/24AA08459D0E/DEBIAN-11/5.10.0-20-AMD64/X86_64/C1BF3A9C44>) |
| 1022:144d |           | AMD              | Renoir Device 24: Function 5         | 90    |            | [C1BF3A9C44](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/24AA08459D0E/DEBIAN-11/5.10.0-20-AMD64/X86_64/C1BF3A9C44>) |
| 1022:144e |           | AMD              | Renoir Device 24: Function 6         | 90    |            | [C1BF3A9C44](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/24AA08459D0E/DEBIAN-11/5.10.0-20-AMD64/X86_64/C1BF3A9C44>) |
| 1022:144f |           | AMD              | Renoir Device 24: Function 7         | 90    |            | [C1BF3A9C44](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/24AA08459D0E/DEBIAN-11/5.10.0-20-AMD64/X86_64/C1BF3A9C44>) |
| 8086:1e10 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family PCI ... | 90    | pcieport   | [3DA35D8BC2](<Mini Pc/Apple/Macmini6/Macmini6,1/BE32E3873E80/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/3DA35D8BC2>) |
| 104c:823e |           | Texas Instrum... | XIO2213A/B/XIO2221 PCI Express to... | 89    | shpchp     | [0CCFB5109B](<Mini Pc/Apple/Macmini5/Macmini5,1/C751DFCA80AB/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/0CCFB5109B>) |
| 8086:1e12 | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 89    | pcieport   | [3DA35D8BC2](<Mini Pc/Apple/Macmini6/Macmini6,1/BE32E3873E80/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/3DA35D8BC2>) |
| 8086:1e14 | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 86    | pcieport   | [3DA35D8BC2](<Mini Pc/Apple/Macmini6/Macmini6,1/BE32E3873E80/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/3DA35D8BC2>) |
| 8086:1547 | 2222:1111 | Intel            | DSL3510 Thunderbolt Controller [C... | 85    | pcieport   | [3DA35D8BC2](<Mini Pc/Apple/Macmini6/Macmini6,1/BE32E3873E80/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/3DA35D8BC2>) |
| 8086:1e57 | 8086:7270 | Intel            | HM77 Express Chipset LPC Controller  | 85    | lpc_ich    | [3DA35D8BC2](<Mini Pc/Apple/Macmini6/Macmini6,1/BE32E3873E80/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/3DA35D8BC2>) |
| 1022:1634 | 1022:1453 | AMD              | Renoir/Cezanne PCIe GPP Bridge       | 83    | pcieport   | [6097531BFC](<Mini Pc/AZW/SER/SER/0FDA0A46CA08/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/6097531BFC>) |
| 8086:0a04 | 106b:0141 | Intel            | Haswell-ULT DRAM Controller          | 76    | hsw_uncore | [FA074ED7C9](<Mini Pc/Apple/Macmini7/Macmini7,1/9A4B9DC9209B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FA074ED7C9>) |
| 8086:9c10 | 8086:7270 | Intel            | 8 Series PCI Express Root Port 1     | 76    | pcieport   | [FA074ED7C9](<Mini Pc/Apple/Macmini7/Macmini7,1/9A4B9DC9209B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FA074ED7C9>) |
| 8086:9c14 | 8086:7270 | Intel            | 8 Series PCI Express Root Port 3     | 76    | pcieport   | [FA074ED7C9](<Mini Pc/Apple/Macmini7/Macmini7,1/9A4B9DC9209B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FA074ED7C9>) |
| 8086:9c16 | 8086:7270 | Intel            | 8 Series PCI Express Root Port 4     | 76    | pcieport   | [FA074ED7C9](<Mini Pc/Apple/Macmini7/Macmini7,1/9A4B9DC9209B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FA074ED7C9>) |
| 8086:9c18 | 8086:7270 | Intel            | 8 Series PCI Express Root Port 5     | 76    | pcieport   | [FA074ED7C9](<Mini Pc/Apple/Macmini7/Macmini7,1/9A4B9DC9209B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FA074ED7C9>) |
| 8086:9c43 | 8086:7270 | Intel            | 8 Series LPC Controller              | 76    | lpc_ich    | [FA074ED7C9](<Mini Pc/Apple/Macmini7/Macmini7,1/9A4B9DC9209B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FA074ED7C9>) |
| 8086:1604 | 8086:2057 | Intel            | Broadwell-U Host Bridge -OPI         | 72    | bdw_uncore | [D89F9A2346](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-507/128101606584/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/D89F9A2346>) |
| 8086:9b51 | 8086:2081 | Intel            | Core i9/i7/i5/Xeon 6c Host Bridge... | 72    | skl_uncore | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 8086:9a09 |           | Intel            | 11th Gen Core Processor PCIe Cont... | 71    | pcieport   | [B85A510A03](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKi5/2E2F0EA6AA4A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/B85A510A03>) |
| 8086:9cc3 | 8086:2057 | Intel            | Wildcat Point-LP LPC Controller      | 71    | lpc_ich    | [D89F9A2346](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-507/128101606584/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/D89F9A2346>) |
| 8086:156d |           | Intel            | DSL5520 Thunderbolt 2 Bridge [Fal... | 70    | pcieport   | [FA074ED7C9](<Mini Pc/Apple/Macmini7/Macmini7,1/9A4B9DC9209B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FA074ED7C9>) |
| 8086:9c90 | 8086:2057 | Intel            | Wildcat Point-LP PCI Express Root... | 70    | pcieport   | [584E5E014A](<Mini Pc/Intel/NUC5i7RYB/NUC5i7RYB H73774-105/20165E913553/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/584E5E014A>) |

### Canbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:4bc1 | 8086:7270 | Intel            | CANBUS                               | 1     | m_can_pci  | [15D4B0E11D](<Mini Pc/Dell EMC/Edge/Edge Gateway 3200/609E0359DDEC/UBUNTU-CORE-20/5.13.0-1008-INTEL/X86_64/15D4B0E11D>) |
| 8086:4bc2 | 8086:7270 | Intel            | CANBUS                               | 1     | m_can_pci  | [15D4B0E11D](<Mini Pc/Dell EMC/Edge/Edge Gateway 3200/609E0359DDEC/UBUNTU-CORE-20/5.13.0-1008-INTEL/X86_64/15D4B0E11D>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:522a | 8086:2074 | Realtek Semic... | RTS522A PCI Express Card Reader      | 201   | rtsx_pci   | [A92B4A305F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/21A3465BD54D/DEBIAN-11/5.10.0-21-AMD64/X86_64/A92B4A305F>) |
| 10ec:5229 | 8086:2068 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 102   | rtsx_pci   | [05B1BDF24D](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/5A48D52A7EDA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/05B1BDF24D>) |
| 10ec:5229 | 8086:2067 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 48    | rtsx_pci   | [AC904A4DF9](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-402/B3229CB33E06/FEDORA-39/6.3.0-0.RC6.20230411GIT0D3EB744AED4.50.FC39.X86_64/X86_64/AC904A4DF9>) |
| 10ec:5229 | 8086:2072 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 43    | rtsx_pci   | [E93C6204C1](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/3F30AC0E5D22/DEBIAN-11/5.10.0-21-AMD64/X86_64/E93C6204C1>) |
| 10ec:525a | 8086:3004 | Realtek Semic... | RTS525A PCI Express Card Reader      | 31    | rtsx_pci   | [7C7FDC5950](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi3/63C01DFB5A1A/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/7C7FDC5950>) |
| 10ec:525a | 10ec:525a | Realtek Semic... | RTS525A PCI Express Card Reader      | 9     | rtsx_pci   | [F28F7150BA](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/C55F851F02E4/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/F28F7150BA>) |
| 10ec:5229 | 10ec:5229 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx_pci   | [27D189D77F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5INH/B6171178AD06/UBUNTU-22.04/5.15.0-40-GENERIC/X86_64/27D189D77F>) |
| 10ec:522a | 8086:2072 | Realtek Semic... | RTS522A PCI Express Card Reader      | 2     | rtsx_pci   | [B9649AAA48](<Mini Pc/Intel Client Systems/NUC7/NUC7PJYHN/4C38130D2991/ALT-10.1/5.15.102-UN-DEF-ALT1/X86_64/B9649AAA48>) |
| 10ec:522a | 103c:815a | Realtek Semic... | RTS522A PCI Express Card Reader      | 1     | rtsx_pci   | [7D65A83025](<Mini Pc/Hewlett-Packard/mt42/mt42 Mobile Thin Client/A398497B20DA/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/7D65A83025>) |
| 1aea:6625 | 8086:2072 | Alcor Micro      | AU6625 PCI-E Flash card reader co... | 1     | alcor_pci  | [68322A0698](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYHN/3A95FF73D4BD/UBUNTU-MATE-23.04/6.2.9-060209-GENERIC/X86_64/68322A0698>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10de:0aa3 | 10de:cb79 | Nvidia           | MCP79 Co-processor                   | 38    | nvidia     | [A206715EC6](<Mini Pc/Apple/Macmini3/Macmini3,1/807755291B05/UBUNTU-23.04/6.1.12-060112-GENERIC/X86_64/A206715EC6>) |
| 10de:0d7a | 10de:cb89 | Nvidia           | MCP89 Co-Processor                   | 26    |            | [6BAD65AD2D](<Mini Pc/Apple/Macmini4/Macmini4,1/43290460D960/ZORIN-16/5.15.0-69-GENERIC/X86_64/6BAD65AD2D>) |
| 8086:1f18 | 8086:0000 | Intel            | Atom processor C2000 QAT             | 2     |            | [C1D37659C1](<Mini Pc/Supermicro/A1/A1SAi/F097711C2215/GENTOO-2.6/5.4.86-GENTOO/X86_64/C1D37659C1>) |
| 8086:0434 | 8086:0000 | Intel            | DH89XXCC Series QAT                  | 1     |            | [372A1D69D7](<Mini Pc/AMI/Aptio/Aptio CRB/223D303B469A/RHEL-8/4.18.0-348.12.2.EL8_5.X86_64/X86_64/372A1D69D7>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9de0 | 8086:2074 | Intel            | Cannon Point-LP MEI Controller #1    | 207   | mei_me     | [A92B4A305F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/21A3465BD54D/DEBIAN-11/5.10.0-21-AMD64/X86_64/A92B4A305F>) |
| 8086:02e0 | 8086:2081 | Intel            | Comet Lake Management Engine Inte... | 123   | mei_me     | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 8086:9d3a | 8086:2068 | Intel            | Sunrise Point-LP CSME HECI #1        | 104   | mei_me     | [05B1BDF24D](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/5A48D52A7EDA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/05B1BDF24D>) |
| 8086:1e3a | 8086:7270 | Intel            | 7 Series/C216 Chipset Family MEI ... | 90    | mei_me     | [3DA35D8BC2](<Mini Pc/Apple/Macmini6/Macmini6,1/BE32E3873E80/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/3DA35D8BC2>) |
| 8086:9c3a | 8086:7270 | Intel            | 8 Series HECI #0                     | 76    | mei_me     | [FA074ED7C9](<Mini Pc/Apple/Macmini7/Macmini7,1/9A4B9DC9209B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FA074ED7C9>) |
| 8086:9cba | 8086:2057 | Intel            | Wildcat Point-LP MEI Controller #1   | 72    | mei_me     | [D89F9A2346](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-507/128101606584/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/D89F9A2346>) |
| 8086:1c3a | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 63    | mei_me     | [0CCFB5109B](<Mini Pc/Apple/Macmini5/Macmini5,1/C751DFCA80AB/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/0CCFB5109B>) |
| 8086:5a9a |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 59    | mei_me     | [AC904A4DF9](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-402/B3229CB33E06/FEDORA-39/6.3.0-0.RC6.20230411GIT0D3EB744AED4.50.FC39.X86_64/X86_64/AC904A4DF9>) |
| 8086:5a9a | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 59    | mei_me     | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 8086:319a | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 57    | mei_me     | [1F1CB63EDC](<Mini Pc/Fanless Mini PC/PCG35/PCG35 GLK/E937013DF7EB/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/1F1CB63EDC>) |
| 8086:a13a | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 54    | mei_me     | [68B65FDA4C](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/0FA94421095F/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/68B65FDA4C>) |
| 8086:319a | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 48    | mei_me     | [D955CBB060](<Mini Pc/Intel/NUC7/NUC7PJYH/E5C0E8061815/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D955CBB060>) |
| 8086:319a | 8086:319a | Intel            | Celeron/Pentium Silver Processor ... | 48    | mei_me     | [91696FE0F2](<Mini Pc/BESSTAR Tech/GK/GK50/0786D176E577/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/91696FE0F2>) |
| 8086:a13a | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 45    | mei_me     | [19BB30E27A](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-405/6215398CADD3/ARCH-ROLLING/6.2.11-ARCH1-1/X86_64/19BB30E27A>) |
| 8086:a0e0 | 8086:3004 | Intel            | Tiger Lake-LP Management Engine I... | 41    | mei_me     | [7232D92C69](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi5/E0ECB94FBAC3/DEBIAN-11/5.10.0-21-AMD64/X86_64/7232D92C69>) |
| 8086:9d3a | 8086:2063 | Intel            | Sunrise Point-LP CSME HECI #1        | 29    | mei_me     | [C370821F44](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/C6B76D6C0340/ALMA-9.1/5.14.0-162.23.1.EL9_1.X86_64/X86_64/C370821F44>) |
| 8086:9d3a | 8086:2070 | Intel            | Sunrise Point-LP CSME HECI #1        | 28    | mei_me     | [861B0673A0](<Mini Pc/Intel/NUC7/NUC7i5DNKE/960B20F7C35D/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/861B0673A0>) |
| 8086:a360 | 17aa:312d | Intel            | Cannon Lake PCH HECI Controller      | 26    | mei_me     | [3A87280F55](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8SEYP00/41DB2AC53FB7/ARCH-ROLLING/6.2.9-ARCH1-1/X86_64/3A87280F55>) |
| 8086:a328 | 8086:7270 | Intel            | Cannon Lake PCH Serial IO UART Ho... | 24    | intel_l... | [7CCE222CE2](<Mini Pc/Apple/Macmini8/Macmini8,1/C2BFA09A14AD/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/7CCE222CE2>) |
| 8086:a360 | 8086:7270 | Intel            | Cannon Lake PCH HECI Controller      | 24    | mei_me     | [7CCE222CE2](<Mini Pc/Apple/Macmini8/Macmini8,1/C2BFA09A14AD/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/7CCE222CE2>) |
| 8086:a2ba | 17aa:3111 | Intel            | 200 Series PCH CSME HECI #1          | 22    | mei_me     | [C95999B5AD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MR001YMZ/CF634F337F26/DEBIAN-11/5.10.0-22-AMD64/X86_64/C95999B5AD>) |
| 8086:4de0 |           | Intel            | Management Engine Interface          | 21    | mei_me     | [E812A255A4](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3/09653BE1DD03/MX-21/5.10.0-22-AMD64/X86_64/E812A255A4>) |
| 8086:4da8 | 1043:8813 | Intel            | Jasper Lake LPSS: UART Controller #0 | 20    | intel_l... | [99D3ECA719](<Mini Pc/CSL-Computer/Mini/Mini PN41/19DD952D9531/ZORIN-16/5.15.0-71-GENERIC/X86_64/99D3ECA719>) |
| 8086:4de0 | 1043:8813 | Intel            | Management Engine Interface          | 20    | mei_me     | [99D3ECA719](<Mini Pc/CSL-Computer/Mini/Mini PN41/19DD952D9531/ZORIN-16/5.15.0-71-GENERIC/X86_64/99D3ECA719>) |
| 8086:a2ba | 103c:829a | Intel            | 200 Series PCH CSME HECI #1          | 20    | mei_me     | [8791CD83C7](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/6D08DAE0C65E/DEVUAN-4/5.10.0-21-AMD64/X86_64/8791CD83C7>) |
| 8086:51e0 | 8086:3024 | Intel            | Alder Lake PCH HECI Controller       | 19    | mei_me     | [68B1E1E6CB](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/5A227E0116FB/KUBUNTU-23.04/6.3.1-CUSTOM/X86_64/68B1E1E6CB>) |
| 8086:319a | 1043:875e | Intel            | Celeron/Pentium Silver Processor ... | 15    | mei_me     | [8C5E382D0A](<Mini Pc/ASUSTek Computer/PN/PN40/65635FC05246/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/8C5E382D0A>) |
| 8086:5a9c |           | Intel            | Communication controller             | 14    |            | [86964DCCFD](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-402/3B68B6C0551B/KUBUNTU-11/5.13.0-40-GENERIC/X86_64/86964DCCFD>) |
| 8086:5a9e |           | Intel            | Communication controller             | 14    |            | [86964DCCFD](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-402/3B68B6C0551B/KUBUNTU-11/5.13.0-40-GENERIC/X86_64/86964DCCFD>) |
| 8086:a0e0 | 8086:3002 | Intel            | Tiger Lake-LP Management Engine I... | 14    | mei_me     | [B85A510A03](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKi5/2E2F0EA6AA4A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/B85A510A03>) |
| 8086:a360 | 17aa:3135 | Intel            | Cannon Lake PCH HECI Controller      | 14    | mei_me     | [A1E7A34896](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CES0BH00/C62828790843/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.4-1-DEFAULT/X86_64/A1E7A34896>) |
| 8086:4da8 | 8086:3027 | Intel            | Jasper Lake LPSS: UART Controller #0 | 12    | intel_l... | [1B7F3C90CA](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/4F56B3D0D076/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/1B7F3C90CA>) |
| 8086:4de0 | 8086:3027 | Intel            | Management Engine Interface          | 12    | mei_me     | [1B7F3C90CA](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/4F56B3D0D076/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/1B7F3C90CA>) |
| 8086:9d3a | 8086:1999 | Intel            | Sunrise Point-LP CSME HECI #1        | 12    | mei_me     | [97F86DA425](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547NANO/DDD3E8ECA091/ARCO-ROLLING/6.2.12-ARCH1-1/X86_64/97F86DA425>) |
| 8086:4da8 |           | Intel            | Jasper Lake LPSS: UART Controller #0 | 11    | intel_l... | [7398AD2411](<Mini Pc/GMKtec/NucBox/NucBox7/7678135C0E37/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/7398AD2411>) |
| 8086:9cba | 8086:2058 | Intel            | Wildcat Point-LP MEI Controller #1   | 11    | mei_me     | [20A5E76A25](<Mini Pc/Intel/NUC5i5MYBE/NUC5i5MYBE H47797-205/0C6EDF67EE8B/MANJARO-22.0.0/5.15.81-1-MANJARO/X86_64/20A5E76A25>) |
| 8086:9cba | 8086:7270 | Intel            | Wildcat Point-LP MEI Controller #1   | 11    | mei_me     | [3E9E7C877C](<Mini Pc/AWOW/NYI/NYI3/1F0DE9559559/LINUXMINT-21.1/5.15.0-60-GENERIC/X86_64/3E9E7C877C>) |
| 8086:a360 | 17aa:3136 | Intel            | Cannon Lake PCH HECI Controller      | 11    | mei_me     | [BDC231EAE9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RUS00300/1B1E837DD190/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/BDC231EAE9>) |
| 8086:319a | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 10    | mei_me     | [71EE0575D4](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/06099CAD1A2D/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/71EE0575D4>) |
| 8086:a0e0 | 8086:2090 | Intel            | Tiger Lake-LP Management Engine I... | 10    | mei_me     | [F28F7150BA](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/C55F851F02E4/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/F28F7150BA>) |
| 8086:06e0 | 17aa:316e | Intel            | Comet Lake HECI Controller           | 9     | mei_me     | [0C5D92EBF9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DT003GRU/DFE02E0590AD/RED-OS-7.3/5.15.87-1.EL7.3.X86_64/X86_64/0C5D92EBF9>) |
| 8086:06e0 | 19da:b440 | Intel            | Comet Lake HECI Controller           | 8     | mei_me     | [6184308BD3](<Mini Pc/ZOTAC/ZBOX-ECM7307/ZBOX-ECM73070C-7307LH-53060C/97C1F8B840C8/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/6184308BD3>) |
| 8086:a13a | 19da:b333 | Intel            | 100 Series/C230 Series Chipset Fa... | 8     | mei_me     | [5F703BFC7D](<Mini Pc/ZOTAC/ZBOX-EN1070/ZBOX-EN1070-1060,EN1070K-1060K/C708E1327B22/OPENMANDRIVA-4.3/5.16.13-DESKTOP-1OMV4003/X86_64/5F703BFC7D>) |
| 8086:a2ba | 103c:829e | Intel            | 200 Series PCH CSME HECI #1          | 8     | mei_me     | [8111885092](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G3 DM/31906DBA1358/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/8111885092>) |
| 8086:a2ba | 103c:82a5 | Intel            | 200 Series PCH CSME HECI #1          | 8     | mei_me     | [C0BE7985C0](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 400 G3 DM/256EB048B176/FEDORA-36/5.19.16-200.FC36.X86_64/X86_64/C0BE7985C0>) |
| 8086:9de0 | 17aa:314d | Intel            | Cannon Point-LP MEI Controller #1    | 7     | mei_me     | [4673EC60EA](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AD000UGE/E42960BAAF23/POP!_OS-22.04/6.0.12-76060006-GENERIC/X86_64/4673EC60EA>) |
| 8086:a0e0 | 8086:3003 | Intel            | Tiger Lake-LP Management Engine I... | 7     | mei_me     | [94D4FE9A93](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKv7/10393889EC9C/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/94D4FE9A93>) |
| 8086:a328 | 8086:2089 | Intel            | Cannon Lake PCH Serial IO UART Ho... | 7     | intel_l... | [8749B43DB1](<Mini Pc/Intel Client Systems/NUC9/NUC9i9QNX/519180459546/UBUNTU-20.04/5.15.0-46-GENERIC/X86_64/8749B43DB1>) |
| 8086:a360 | 8086:2089 | Intel            | Cannon Lake PCH HECI Controller      | 7     | mei_me     | [8749B43DB1](<Mini Pc/Intel Client Systems/NUC9/NUC9i9QNX/519180459546/UBUNTU-20.04/5.15.0-46-GENERIC/X86_64/8749B43DB1>) |
| 8086:02e0 | 1043:87bd | Intel            | Comet Lake Management Engine Inte... | 6     | mei_me     | [8B7D9CA6FD](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN62S/C5A82ADBCB5E/OPENMANDRIVA-4.2/5.11.12-DESKTOP-1OMV4002/X86_64/8B7D9CA6FD>) |

### Dma controller (eisa dma) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:22c0 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 31    | dw_dmac... | [410350C836](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/99AD9DE0D682/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/410350C836>) |
| 8086:0f06 |           | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | dw_dmac... | [8FE291470D](<Mini Pc/NEXCOM/VTC/VTC1010/03C726F79B18/LUBUNTU-22.04/5.15.0-33-GENERIC/X86_64/8FE291470D>) |
| 8086:0f40 | 8086:0f40 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | dw_dmac... | [8FE291470D](<Mini Pc/NEXCOM/VTC/VTC1010/03C726F79B18/LUBUNTU-22.04/5.15.0-33-GENERIC/X86_64/8FE291470D>) |
| 8086:0f06 | 8086:0f06 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | dw_dmac... | [A968EF1DD8](<Mini Pc/HPE/EL/EL10/3097F99AD33E/OPENSUSE-LEAP-15.0/4.12.14-LP150.11-DEFAULT/X86_64/A968EF1DD8>) |
| 8086:2286 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | dw_dmac... | [10C1838B9D](<Mini Pc/AMI/Aptio/Aptio CRB/6C7827486731/DEBIAN-11/5.10.0-8-AMD64/X86_64/10C1838B9D>) |
| 8086:22c0 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | dw_dmac... | [10C1838B9D](<Mini Pc/AMI/Aptio/Aptio CRB/6C7827486731/DEBIAN-11/5.10.0-8-AMD64/X86_64/10C1838B9D>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15df | 1022:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 171   | ccp        | [6097531BFC](<Mini Pc/AZW/SER/SER/0FDA0A46CA08/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/6097531BFC>) |
| 8086:0f18 | 8086:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 102   | mei_txe    | [1F19B2C0DC](<Mini Pc/AMI/Aptio/Aptio CRB/E8C182707BA0/DEBIAN-11/5.10.0-21-AMD64/X86_64/1F19B2C0DC>) |
| 8086:2298 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 51    | mei_txe    | [410350C836](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/99AD9DE0D682/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/410350C836>) |
| 1022:1578 | 1022:1578 | AMD              | Carrizo Platform Security Processor  | 44    |            | [BFFA46EF83](<Mini Pc/ATOPNUC/MA/MA90/A53ED68DF138/UBUNTUSTUDIO-23.04/6.2.0-1003-LOWLATENCY/X86_64/BFFA46EF83>) |
| 8086:2298 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 40    | mei_txe    | [9408F6348B](<Mini Pc/AMI/Aptio/Aptio CRB/19DF7B640AD0/DEBIAN-11/6.2.10-1-LIQUORIX-AMD64/X86_64/9408F6348B>) |
| 1022:15df | 103c:872e | AMD              | Family 17h (Models 10h-1fh) Platf... | 13    | ccp        | [4BE8DDC98E](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/5D3851BCDC5D/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/4BE8DDC98E>) |
| 8086:0f18 | 17aa:368d | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 12    | mei_txe    | [BA6F405592](<Mini Pc/Lenovo/H30-00/H30-00 90C2003FMT/38341BB3FC42/UBUNTU-22.04/5.15.0-41-GENERIC/X86_64/BA6F405592>) |
| 8086:0f18 |           | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 10    | mei_txe    | [AE8045E8DD](<Mini Pc/NOBLEX/NB/NB1601/6611033DEAB1/LINUXMINT-21/5.15.0-41-GENERIC/X86_64/AE8045E8DD>) |
| 1022:15df | 17aa:3190 | AMD              | Family 17h (Models 10h-1fh) Platf... | 9     | ccp        | [56B4F8A1A9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJ000BMZ/C185070F41DC/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/56B4F8A1A9>) |
| 8086:0f18 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 9     | mei_txe    | [9BA3333988](<Mini Pc/AMI/Aptio/Aptio CRB/24010023E208/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/9BA3333988>) |
| 1022:1537 | 1022:1537 | AMD              | Kabini/Mullins PSP-Platform Secur... | 6     | ccp        | [3007D5DD93](<Mini Pc/WYSE/Dell/Dell Thin Client Desktop 5060/BFFD9DC32BEF/DEBIAN-11/5.10.0-17-AMD64/X86_64/3007D5DD93>) |
| 8086:0f18 | 19da:b219 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | mei_txe    | [AB1C46C857](<Mini Pc/ZOTAC/ZBOX-CI320NANO/ZBOX-CI320NANO series/777238CAAA55/NOBARA-36/6.0.7-202.FSYNC.FC36.X86_64/X86_64/AB1C46C857>) |
| 8086:2298 | 17aa:30dd | Intel            | Atom/Celeron/Pentium Processor x5... | 6     | mei_txe    | [EEDDC09936](<Mini Pc/Lenovo/S200z/S200z 10K5001YRU/15AD9828B67F/RED-OS-7.3.2/5.15.72-1.EL7.3.X86_64/X86_64/EEDDC09936>) |
| 8086:2298 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 6     | mei_txe    | [A8BF4AD2A0](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/E4715B308A66/ZORIN-16/5.15.0-46-GENERIC/X86_64/A8BF4AD2A0>) |
| 1022:15df | 17aa:3181 | AMD              | Family 17h (Models 10h-1fh) Platf... | 5     | ccp        | [D4C01D094B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75n 11GWCTO1WW/5439510A54DE/UBUNTU-18.04/5.4.0-137-GENERIC/X86_64/D4C01D094B>) |
| 1022:1649 | 1022:1649 | AMD              | VanGogh PSP/CCP                      | 5     | ccp        | [74F148FB60](<Mini Pc/AZW/SER/SER/6ACE98838322/GARUDA-SOARING/6.3.0-AMD-ZNVER2/X86_64/74F148FB60>) |
| 8086:2298 | 1028:07c1 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | mei_txe    | [F1FB89D0F7](<Mini Pc/Dell/Wyse/Wyse 3040 Thin Client/AC1F30A762B7/DEBIAN-11/5.10.0-21-AMD64/X86_64/F1FB89D0F7>) |
| 8086:2298 | 1462:b120 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | mei_txe    | [4C3E0A0AC6](<Mini Pc/MSI/MS-B/MS-B120/3412F4B83350/UBUNTU-MATE-23.04/6.3.1-060301-GENERIC/X86_64/4C3E0A0AC6>) |
| 1022:15df | 103c:8836 | AMD              | Family 17h (Models 10h-1fh) Platf... | 4     | ccp        | [DA34E7C710](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/DD273ADCD4AF/XUBUNTU-20.04/5.8.0-53-GENERIC/X86_64/DA34E7C710>) |
| 8086:2298 | 17aa:3637 | Intel            | Atom/Celeron/Pentium Processor x5... | 4     | mei_txe    | [9FC0FE4A5F](<Mini Pc/Lenovo/C20-00/C20-00 F0BB00VCAU/1522F026E3A1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/9FC0FE4A5F>) |
| 8086:2298 | 19da:b273 | Intel            | Atom/Celeron/Pentium Processor x5... | 4     | mei_txe    | [0D05B404DD](<Mini Pc/ZOTAC/ZBOX-BI/ZBOX-BI324/C214E8207F22/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/0D05B404DD>) |
| 1022:15df | 103c:8523 | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     | ccp        | [57C13D1B6A](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/DD76DE9A334C/KDE-NEON-20.04/5.15.0-46-GENERIC/X86_64/57C13D1B6A>) |
| 8086:0f18 | 1071:0730 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     | mei_txe    | [F341B62F96](<Mini Pc/Aquarius/Tcc/Tcc Uvl U30 S25/A0CCC50D7DCA/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/F341B62F96>) |
| 1022:15df | 103c:872c | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     | ccp        | [36F1254C43](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 805 G6 Desktop Mini PC/20C32FFA6ABD/CENTOS-7/5.15.1-1.EL7.ELREPO.X86_64/X86_64/36F1254C43>) |
| 1022:15df | 17aa:32e4 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     | ccp        | [F49F7BA847](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JNS02N00/EFCDDA73E969/RED-OS-7.3.1/5.15.35-5.EL7.3.X86_64/X86_64/F49F7BA847>) |
| 8086:0f18 | 17aa:3688 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | mei_txe    | [5C12ED53B7](<Mini Pc/Lenovo/H500s/H500s 10157/D1B811E9CDB3/ELEMENTARY-7/5.19.0-38-GENERIC/X86_64/5C12ED53B7>) |
| 8086:0f18 | 1d05:100f | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | mei_txe    | [3749438EF1](<Mini Pc/Exo/Smart/Smart R8-CE/13753A7E26E0/POP!_OS-22.04/5.19.16-76051916-GENERIC/X86_64/3749438EF1>) |
| 8086:2298 | 8086:2298 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | mei_txe    | [3AB4853FDD](<Mini Pc/BESSTAR Tech/GN/GN31/FCAF87D82341/DEBIAN-10/5.4.78-2-PVE/X86_64/3AB4853FDD>) |
| 1022:15df | 103c:8522 | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     | ccp        | [28B79EA28B](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/84561BBF7057/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/28B79EA28B>) |
| 1022:15df | 103c:873a | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     | ccp        | [5C3BE4E9AA](<Mini Pc/Hewlett-Packard/t540/t540 Thin Client/D3480EA77BCC/XUBUNTU-22.04/5.15.0-56-GENERIC/X86_64/5C3BE4E9AA>) |
| 1022:15df | 103c:8881 | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     | ccp        | [D9864F2860](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 805 G8 Desktop Mini PC/C85E0CDAD14F/ROCKY-8.7/4.18.0-425.10.1.EL8_7.X86_64/X86_64/D9864F2860>) |
| 1022:1649 | 1043:8870 | AMD              | VanGogh PSP/CCP                      | 1     | ccp        | [73F7FB3F85](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN53/031C11533068/FEDORA-37/6.1.11-200.FC37.X86_64/X86_64/73F7FB3F85>) |
| 8086:0f18 | 1028:07b9 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [F444E9914B](<Mini Pc/Dell/Edge/Edge Gateway 3001/9349E7ABA493/UBUNTU-CORE-16/4.4.0-171-GENERIC/X86_64/F444E9914B>) |
| 8086:0f18 | 1071:0740 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [F2F4C5E23E](<Mini Pc/AMI/Aptio/Aptio CRB/4331D427A030/UBUNTU-18.04/5.4.0-48-GENERIC/X86_64/F2F4C5E23E>) |
| 8086:2298 | 1297:4033 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | mei_txe    | [B31E28E55F](<Mini Pc/Shuttle/XS35/XS35V5/00878A051AA2/UBUNTU-19.10/5.3.0-42-GENERIC/X86_64/B31E28E55F>) |

### Firewire controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 11c1:5901 | 11c1:5900 | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 125   | firewir... | [3DA35D8BC2](<Mini Pc/Apple/Macmini6/Macmini6,1/BE32E3873E80/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/3DA35D8BC2>) |
| 104c:823f |           | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 89    | firewir... | [0CCFB5109B](<Mini Pc/Apple/Macmini5/Macmini5,1/C751DFCA80AB/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/0CCFB5109B>) |
| 11c1:5811 | 11c1:5811 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 20    | firewir... | [564A8CF5C2](<Mini Pc/Apple/Macmini2/Macmini2,1/F0A4DC4C2837/UBUNTU-18.04/5.4.0-131-GENERIC/X86_64/564A8CF5C2>) |
| 11c1:5901 | c111:0159 | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 4     | firewir... | [A9D3A75926](<Mini Pc/Apple/Macmini6/Macmini6,2/499D40DB5C22/LINUXMINT-21/5.15.0-48-GENERIC/X86_64/A9D3A75926>) |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1577 | 1022:1577 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 44    |            | [BFFA46EF83](<Mini Pc/ATOPNUC/MA/MA90/A53ED68DF138/UBUNTUSTUDIO-23.04/6.2.0-1003-LOWLATENCY/X86_64/BFFA46EF83>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:3ea5 | 8086:2074 | Intel            | CoffeeLake-U GT3e [Iris Plus Grap... | 205   | i915       | [A92B4A305F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/21A3465BD54D/DEBIAN-11/5.10.0-21-AMD64/X86_64/A92B4A305F>) |
| 8086:0f31 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 99    | i915       | [1F19B2C0DC](<Mini Pc/AMI/Aptio/Aptio CRB/E8C182707BA0/DEBIAN-11/5.10.0-21-AMD64/X86_64/1F19B2C0DC>) |
| 8086:9bca | 8086:2081 | Intel            | Comet Lake UHD Graphics              | 72    | i915       | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 1002:1638 | 1002:0123 | AMD              | Cezanne [Radeon Vega Series / Rad... | 64    | amdgpu     | [6097531BFC](<Mini Pc/AZW/SER/SER/0FDA0A46CA08/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/6097531BFC>) |
| 8086:3185 | 1e50:8003 | Intel            | GeminiLake [UHD Graphics 600]        | 53    | i915       | [DC66113388](<Mini Pc/BESSTAR Tech/N/N40/4F2893E9BF26/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/DC66113388>) |
| 8086:22b1 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 51    | i915       | [410350C836](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/99AD9DE0D682/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/410350C836>) |
| 8086:9b41 | 8086:2081 | Intel            | CometLake-U GT2 [UHD Graphics]       | 51    | i915       | [BCA816C594](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNH/AB601F3A2215/UBUNTU-22.04/5.15.0-70-GENERIC/X86_64/BCA816C594>) |
| 8086:5a85 | 8086:2067 | Intel            | HD Graphics 500                      | 50    | i915       | [AC904A4DF9](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-402/B3229CB33E06/FEDORA-39/6.3.0-0.RC6.20230411GIT0D3EB744AED4.50.FC39.X86_64/X86_64/AC904A4DF9>) |
| 8086:0a2e | 106b:0141 | Intel            | Haswell-ULT Integrated Graphics C... | 47    | i915       | [FA074ED7C9](<Mini Pc/Apple/Macmini7/Macmini7,1/9A4B9DC9209B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FA074ED7C9>) |
| 8086:0166 | 106b:00ff | Intel            | 3rd Gen Core processor Graphics C... | 46    | i915       | [3DA35D8BC2](<Mini Pc/Apple/Macmini6/Macmini6,1/BE32E3873E80/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/3DA35D8BC2>) |
| 8086:193b | 8086:2064 | Intel            | Iris Pro Graphics 580                | 45    | i915       | [19BB30E27A](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-405/6215398CADD3/ARCH-ROLLING/6.2.11-ARCH1-1/X86_64/19BB30E27A>) |
| 8086:5a85 | 8086:2212 | Intel            | HD Graphics 500                      | 44    | i915       | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 1002:1636 | 1043:87e7 | AMD              | Renoir                               | 43    | amdgpu     | [C1BF3A9C44](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/24AA08459D0E/DEBIAN-11/5.10.0-20-AMD64/X86_64/C1BF3A9C44>) |
| 8086:591b | 8086:2073 | Intel            | HD Graphics 630                      | 43    | i915       | [68B65FDA4C](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/0FA94421095F/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/68B65FDA4C>) |
| 8086:5926 | 8086:2068 | Intel            | Iris Plus Graphics 640               | 43    | i915       | [05B1BDF24D](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/5A48D52A7EDA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/05B1BDF24D>) |
| 1002:694c | 8086:2073 | AMD              | Polaris 22 XT [Radeon RX Vega M GH]  | 40    | amdgpu     | [68B65FDA4C](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/0FA94421095F/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/68B65FDA4C>) |
| 8086:0166 | 106b:0101 | Intel            | 3rd Gen Core processor Graphics C... | 40    | i915       | [3D0CCACE69](<Mini Pc/Apple/Macmini6/Macmini6,2/6489A616068C/LINUXMINT-21.1/5.15.0-57-GENERIC/X86_64/3D0CCACE69>) |
| 8086:5916 | 8086:2068 | Intel            | HD Graphics 620                      | 39    | i915       | [D268EE328B](<Mini Pc/Intel/NUC7/NUC7i3BNH/9FF202ED96DA/UBUNTU-16.04/4.15.0-142-GENERIC/X86_64/D268EE328B>) |
| 10de:0861 | 106b:00ae | Nvidia           | C79 [GeForce 9400]                   | 38    | nouveau    | [A206715EC6](<Mini Pc/Apple/Macmini3/Macmini3,1/807755291B05/UBUNTU-23.04/6.1.12-060112-GENERIC/X86_64/A206715EC6>) |
| 8086:9a49 | 8086:3004 | Intel            | TigerLake-LP GT2 [Iris Xe Graphics]  | 38    | i915       | [7232D92C69](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi5/E0ECB94FBAC3/DEBIAN-11/5.10.0-21-AMD64/X86_64/7232D92C69>) |
| 8086:0126 | 106b:00e6 | Intel            | 2nd Generation Core Processor Fam... | 37    | i915       | [0CCFB5109B](<Mini Pc/Apple/Macmini5/Macmini5,1/C751DFCA80AB/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/0CCFB5109B>) |
| 8086:0a26 | 106b:0141 | Intel            | Haswell-ULT Integrated Graphics C... | 28    | i915       | [6182CCA953](<Mini Pc/Apple/Macmini7/Macmini7,1/2C4B1063EAE6/FEDORA-37/6.2.9-200.FC37.X86_64/X86_64/6182CCA953>) |
| 8086:1616 | 8086:2057 | Intel            | HD Graphics 5500                     | 27    | i915       | [D89F9A2346](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-507/128101606584/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/D89F9A2346>) |
| 8086:1626 | 8086:2057 | Intel            | HD Graphics 6000                     | 27    | i915       | [8F1AF30BBA](<Mini Pc/Intel/NUC5i5RYB/NUC5i5RYB H40999-502/2F7BB1D9A85D/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/8F1AF30BBA>) |
| 8086:3185 | 8086:2072 | Intel            | GeminiLake [UHD Graphics 600]        | 27    | i915       | [68322A0698](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYHN/3A95FF73D4BD/UBUNTU-MATE-23.04/6.2.9-060209-GENERIC/X86_64/68322A0698>) |
| 10de:08a4 | 106b:00c0 | Nvidia           | MCP89 [GeForce 320M]                 | 26    | nouveau    | [6BAD65AD2D](<Mini Pc/Apple/Macmini4/Macmini4,1/43290460D960/ZORIN-16/5.15.0-69-GENERIC/X86_64/6BAD65AD2D>) |
| 8086:3185 |           | Intel            | GeminiLake [UHD Graphics 600]        | 25    | i915       | [1F1CB63EDC](<Mini Pc/Fanless Mini PC/PCG35/PCG35 GLK/E937013DF7EB/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/1F1CB63EDC>) |
| 8086:3e9b | 106b:0207 | Intel            | CoffeeLake-H GT2 [UHD Graphics 630]  | 23    | i915       | [7CCE222CE2](<Mini Pc/Apple/Macmini8/Macmini8,1/C2BFA09A14AD/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/7CCE222CE2>) |
| 8086:5927 | 8086:2068 | Intel            | Iris Plus Graphics 650               | 23    | i915       | [9FD1F28183](<Mini Pc/Intel Client Systems/NUC7/NUC7i7BNHX/7537AD613D75/UBUNTU-22.04/5.15.0-52-GENERIC/X86_64/9FD1F28183>) |
| 1002:6741 | 106b:00e8 | AMD              | Whistler [Radeon HD 6630M/6650M/6... | 22    | radeon     | [401F407DAE](<Mini Pc/Apple/Macmini5/Macmini5,2/BF21898B2E13/ZORIN-16/5.15.0-69-GENERIC/X86_64/401F407DAE>) |
| 1002:9806 | 103c:17e2 | AMD              | Wrestler [Radeon HD 6320]            | 21    | radeon     | [02EE837763](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/3EA0F94B1F39/DEBIAN-11/5.10.0-21-AMD64/X86_64/02EE837763>) |
| 8086:22b0 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 21    | i915       | [9AC0BAC56E](<Mini Pc/BESSTAR Tech/Z83/Z83-F/E4F29253430F/DEBIAN-11/5.10.0-21-AMD64/X86_64/9AC0BAC56E>) |
| 8086:3184 | 8086:2072 | Intel            | GeminiLake [UHD Graphics 605]        | 21    | i915       | [D955CBB060](<Mini Pc/Intel/NUC7/NUC7PJYH/E5C0E8061815/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D955CBB060>) |
| 8086:3e92 | 17aa:312d | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 21    | i915       | [3A87280F55](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8SEYP00/41DB2AC53FB7/ARCH-ROLLING/6.2.9-ARCH1-1/X86_64/3A87280F55>) |
| 8086:27a2 | 8086:7270 | Intel            | Mobile 945GM/GMS, 943/940GML Expr... | 20    | i915       | [564A8CF5C2](<Mini Pc/Apple/Macmini2/Macmini2,1/F0A4DC4C2837/UBUNTU-18.04/5.4.0-131-GENERIC/X86_64/564A8CF5C2>) |
| 8086:1926 | 8086:2063 | Intel            | Iris Graphics 540                    | 19    | i915       | [C370821F44](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/C6B76D6C0340/ALMA-9.1/5.14.0-162.23.1.EL9_1.X86_64/X86_64/C370821F44>) |
| 8086:22b1 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 19    | i915       | [9408F6348B](<Mini Pc/AMI/Aptio/Aptio CRB/19DF7B640AD0/DEBIAN-11/6.2.10-1-LIQUORIX-AMD64/X86_64/9408F6348B>) |
| 8086:0126 | 106b:00f0 | Intel            | 2nd Generation Core Processor Fam... | 18    |            | [401F407DAE](<Mini Pc/Apple/Macmini5/Macmini5,2/BF21898B2E13/ZORIN-16/5.15.0-69-GENERIC/X86_64/401F407DAE>) |
| 8086:162b | 8086:2057 | Intel            | Iris Graphics 6100                   | 18    | i915       | [584E5E014A](<Mini Pc/Intel/NUC5i7RYB/NUC5i7RYB H73774-105/20165E913553/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/584E5E014A>) |
| 8086:5912 | 17aa:3111 | Intel            | HD Graphics 630                      | 18    | i915       | [C95999B5AD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MR001YMZ/CF634F337F26/DEBIAN-11/5.10.0-22-AMD64/X86_64/C95999B5AD>) |
| 1002:9874 | 103c:8158 | AMD              | Wani [Radeon R5/R6/R7 Graphics]      | 17    | amdgpu     | [A7D7E5C675](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/D14A501869D8/DEBIAN-11/5.10.0-19-AMD64/X86_64/A7D7E5C675>) |
| 8086:4e61 | 1e50:800f | Intel            | JasperLake [UHD Graphics]            | 17    | i915       | [E812A255A4](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3/09653BE1DD03/MX-21/5.10.0-22-AMD64/X86_64/E812A255A4>) |
| 1002:15dd | 17aa:3130 | AMD              | Raven Ridge [Radeon Vega Series /... | 16    | amdgpu     | [52B38CEE5C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VG000EUS/FEE9E9034339/KUBUNTU-22.10/5.19.0-26-GENERIC/X86_64/52B38CEE5C>) |
| 1002:15d8 | 1002:0123 | AMD              | Picasso/Raven 2 [Radeon Vega Seri... | 15    | amdgpu     | [86A3944105](<Mini Pc/AZW/SER/SER/4F9AF19348C5/DEBIAN-11/5.10.6-1-PVE/X86_64/86A3944105>) |
| 1002:164c | 1043:880a | AMD              | Lucienne                             | 15    | amdgpu     | [E92E5DE977](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN51-E1/8C48251D82E0/UBUNTU-20.04/5.15.0-69-GENERIC/X86_64/E92E5DE977>) |
| 8086:3185 | 0301:02f3 | Intel            | GeminiLake [UHD Graphics 600]        | 15    | i915       | [9FEB6E0D59](<Mini Pc/Chuwi/LarkBox/LarkBox Pro/F364AAE2AE09/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/9FEB6E0D59>) |
| 8086:3185 | 1043:875e | Intel            | GeminiLake [UHD Graphics 600]        | 14    | i915       | [D3CC2A53B6](<Mini Pc/ASUSTek Computer/PN/PN40/C0D04E936FD2/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/D3CC2A53B6>) |
| 8086:5916 | 8086:2070 | Intel            | HD Graphics 620                      | 14    | i915       | [861B0673A0](<Mini Pc/Intel/NUC7/NUC7i5DNKE/960B20F7C35D/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/861B0673A0>) |
| 8086:5917 | 8086:2070 | Intel            | UHD Graphics 620                     | 14    | i915       | [B00FA62F7C](<Mini Pc/Intel Client Systems/NUC7/NUC7i7DNKE/E1250A723D48/KDE-NEON-22.04/5.19.0-40-GENERIC/X86_64/B00FA62F7C>) |
| 1002:1636 | 103c:872e | AMD              | Renoir                               | 13    | amdgpu     | [4BE8DDC98E](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/5D3851BCDC5D/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/4BE8DDC98E>) |

### Iommu (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1631 | 1022:1631 | AMD              | Renoir/Cezanne IOMMU                 | 146   |            | [6097531BFC](<Mini Pc/AZW/SER/SER/0FDA0A46CA08/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/6097531BFC>) |
| 1022:15d1 | 1022:15d1 | AMD              | Raven/Raven2 IOMMU                   | 49    |            | [86A3944105](<Mini Pc/AZW/SER/SER/4F9AF19348C5/DEBIAN-11/5.10.6-1-PVE/X86_64/86A3944105>) |
| 1022:1631 | 17aa:3190 | AMD              | Renoir/Cezanne IOMMU                 | 9     |            | [56B4F8A1A9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJ000BMZ/C185070F41DC/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/56B4F8A1A9>) |
| 1022:14b6 | 1022:14b6 | AMD              | Family 17h-19h IOMMU                 | 5     |            | [74F148FB60](<Mini Pc/AZW/SER/SER/6ACE98838322/GARUDA-SOARING/6.3.0-AMD-ZNVER2/X86_64/74F148FB60>) |
| 1022:1423 | 103c:8103 | AMD              | Family 15h (Models 30h-3fh) I/O M... | 4     |            | [19C575A4D8](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/E94D038C9E51/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/19C575A4D8>) |
| 1022:15d1 | 103c:8523 | AMD              | Raven/Raven2 IOMMU                   | 3     |            | [57C13D1B6A](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/DD76DE9A334C/KDE-NEON-20.04/5.15.0-46-GENERIC/X86_64/57C13D1B6A>) |
| 8086:1f16 | 8086:0000 | Intel            | Atom processor C2000 RCEC            | 2     |            | [C1D37659C1](<Mini Pc/Supermicro/A1/A1SAi/F097711C2215/GENTOO-2.6/5.4.86-GENTOO/X86_64/C1D37659C1>) |
| 1022:14b6 | 1043:8870 | AMD              | Family 17h-19h IOMMU                 | 1     |            | [73F7FB3F85](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN53/031C11533068/FEDORA-37/6.1.11-200.FC37.X86_64/X86_64/73F7FB3F85>) |
| 1022:15d1 | 103c:8522 | AMD              | Raven/Raven2 IOMMU                   | 1     |            | [28B79EA28B](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/84561BBF7057/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/28B79EA28B>) |
| 1022:1631 | 17aa:32e4 | AMD              | Renoir/Cezanne IOMMU                 | 1     |            | [3825D0CE9C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JN000NGE/1AEE52FF07DC/KUBUNTU-22.04/5.15.0-46-GENERIC/X86_64/3825D0CE9C>) |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:816c | 1043:85b5 | Realtek Semic... | RTL8111xP IPMI interface             | 37    |            | [9CE749E52E](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/4EDEB05C441C/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.1-1-DEFAULT/X86_64/9CE749E52E>) |
| 10ec:816c | 17aa:3151 | Realtek Semic... | RTL8111xP IPMI interface             | 7     |            | [6D4ECB5A00](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A5S1HM00/EDB5CB0BC766/FEDORA-36/6.1.5-100.FC36.X86_64/X86_64/6D4ECB5A00>) |
| 10ec:816c | 17aa:30fd | Realtek Semic... | RTL8111xP IPMI interface             | 3     |            | [F355BAB53F](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10M2S0JL00/0168DA559F7B/FEDORA-37/6.2.8-200.FC37.X86_64/X86_64/F355BAB53F>) |
| 10ec:816c | 103c:8523 | Realtek Semic... | RTL8111xP IPMI interface             | 2     |            | [D3AFFBBDF4](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/E6875D808502/ROSA-12/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/D3AFFBBDF4>) |
| 10ec:816c | 17aa:3181 | Realtek Semic... | RTL8111xP IPMI interface             | 2     |            | [56F9A83D77](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75n 11GW000BUS/8D95E87EDCE7/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/56F9A83D77>) |
| 10ec:816c | 103c:83dd | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [9EC6F2E5FE](<Mini Pc/Hewlett-Packard/mt44/mt44 Mobile Thin Client/367A393AEEB1/KDE-NEON-20.04/5.11.0-40-GENERIC/X86_64/9EC6F2E5FE>) |
| 10ec:816c | 103c:8522 | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [28B79EA28B](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/84561BBF7057/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/28B79EA28B>) |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:816c | 10ec:8168 | Realtek Semic... | RTL8111xP IPMI interface             | 18    | ipmi_si    | [4BE8DDC98E](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/5D3851BCDC5D/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/4BE8DDC98E>) |
| 10ec:816c | 17aa:3130 | Realtek Semic... | RTL8111xP IPMI interface             | 16    |            | [52B38CEE5C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VG000EUS/FEE9E9034339/KUBUNTU-22.10/5.19.0-26-GENERIC/X86_64/52B38CEE5C>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9def | 8086:2074 | Intel            | Cannon Point-LP Shared SRAM          | 207   |            | [A92B4A305F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/21A3465BD54D/DEBIAN-11/5.10.0-21-AMD64/X86_64/A92B4A305F>) |
| 8086:02ef | 8086:2081 | Intel            | Comet Lake PCH-LP Shared SRAM        | 123   |            | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 8086:9d21 | 8086:2068 | Intel            | Sunrise Point-LP PMC                 | 105   |            | [05B1BDF24D](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/5A48D52A7EDA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/05B1BDF24D>) |
| 8086:a0ef |           | Intel            | Tiger Lake-LP Shared SRAM            | 74    |            | [B85A510A03](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKi5/2E2F0EA6AA4A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/B85A510A03>) |
| 8086:a121 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 54    |            | [68B65FDA4C](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/0FA94421095F/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/68B65FDA4C>) |
| 8086:a121 | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 45    |            | [19BB30E27A](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-405/6215398CADD3/ARCH-ROLLING/6.2.11-ARCH1-1/X86_64/19BB30E27A>) |
| 10de:0a88 |           | Nvidia           | MCP79 Memory Controller              | 38    |            | [A206715EC6](<Mini Pc/Apple/Macmini3/Macmini3,1/807755291B05/UBUNTU-23.04/6.1.12-060112-GENERIC/X86_64/A206715EC6>) |
| 10de:0a89 |           | Nvidia           | MCP79 Memory Controller              | 38    |            | [A206715EC6](<Mini Pc/Apple/Macmini3/Macmini3,1/807755291B05/UBUNTU-23.04/6.1.12-060112-GENERIC/X86_64/A206715EC6>) |
| 10de:0a98 | 10de:cb79 | Nvidia           | MCP79 Memory Controller              | 38    |            | [A206715EC6](<Mini Pc/Apple/Macmini3/Macmini3,1/807755291B05/UBUNTU-23.04/6.1.12-060112-GENERIC/X86_64/A206715EC6>) |
| 10de:0aa4 |           | Nvidia           | MCP79 Memory Controller              | 38    |            | [A206715EC6](<Mini Pc/Apple/Macmini3/Macmini3,1/807755291B05/UBUNTU-23.04/6.1.12-060112-GENERIC/X86_64/A206715EC6>) |
| 8086:4def |           | Intel            | Jasper Lake Shared SRAM Controller   | 35    |            | [E812A255A4](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3/09653BE1DD03/MX-21/5.10.0-22-AMD64/X86_64/E812A255A4>) |
| 8086:9d21 | 8086:2063 | Intel            | Sunrise Point-LP PMC                 | 29    |            | [C370821F44](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/C6B76D6C0340/ALMA-9.1/5.14.0-162.23.1.EL9_1.X86_64/X86_64/C370821F44>) |
| 8086:9d21 | 8086:2070 | Intel            | Sunrise Point-LP PMC                 | 28    |            | [861B0673A0](<Mini Pc/Intel/NUC7/NUC7i5DNKE/960B20F7C35D/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/861B0673A0>) |
| 10de:0d68 |           | Nvidia           | MCP89 Memory Controller              | 26    |            | [6BAD65AD2D](<Mini Pc/Apple/Macmini4/Macmini4,1/43290460D960/ZORIN-16/5.15.0-69-GENERIC/X86_64/6BAD65AD2D>) |
| 10de:0d69 |           | Nvidia           | MCP89 Memory Controller              | 26    |            | [6BAD65AD2D](<Mini Pc/Apple/Macmini4/Macmini4,1/43290460D960/ZORIN-16/5.15.0-69-GENERIC/X86_64/6BAD65AD2D>) |
| 10de:0d6d |           | Nvidia           | MCP89 Memory Controller              | 26    |            | [6BAD65AD2D](<Mini Pc/Apple/Macmini4/Macmini4,1/43290460D960/ZORIN-16/5.15.0-69-GENERIC/X86_64/6BAD65AD2D>) |
| 10de:0d6e |           | Nvidia           | MCP89 Memory Controller              | 26    |            | [6BAD65AD2D](<Mini Pc/Apple/Macmini4/Macmini4,1/43290460D960/ZORIN-16/5.15.0-69-GENERIC/X86_64/6BAD65AD2D>) |
| 10de:0d6f |           | Nvidia           | MCP89 Memory Controller              | 26    |            | [6BAD65AD2D](<Mini Pc/Apple/Macmini4/Macmini4,1/43290460D960/ZORIN-16/5.15.0-69-GENERIC/X86_64/6BAD65AD2D>) |
| 10de:0d70 |           | Nvidia           | MCP89 Memory Controller              | 26    |            | [6BAD65AD2D](<Mini Pc/Apple/Macmini4/Macmini4,1/43290460D960/ZORIN-16/5.15.0-69-GENERIC/X86_64/6BAD65AD2D>) |
| 10de:0d71 |           | Nvidia           | MCP89 Memory Controller              | 26    |            | [6BAD65AD2D](<Mini Pc/Apple/Macmini4/Macmini4,1/43290460D960/ZORIN-16/5.15.0-69-GENERIC/X86_64/6BAD65AD2D>) |
| 10de:0d72 |           | Nvidia           | MCP89 Memory Controller              | 26    |            | [6BAD65AD2D](<Mini Pc/Apple/Macmini4/Macmini4,1/43290460D960/ZORIN-16/5.15.0-69-GENERIC/X86_64/6BAD65AD2D>) |
| 10de:0d75 |           | Nvidia           | MCP89 Memory Controller              | 26    |            | [6BAD65AD2D](<Mini Pc/Apple/Macmini4/Macmini4,1/43290460D960/ZORIN-16/5.15.0-69-GENERIC/X86_64/6BAD65AD2D>) |
| 10de:0d7b |           | Nvidia           | MCP89 Memory Controller              | 26    |            | [6BAD65AD2D](<Mini Pc/Apple/Macmini4/Macmini4,1/43290460D960/ZORIN-16/5.15.0-69-GENERIC/X86_64/6BAD65AD2D>) |
| 8086:a36f | 17aa:312d | Intel            | Cannon Lake PCH Shared SRAM          | 26    |            | [3A87280F55](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8SEYP00/41DB2AC53FB7/ARCH-ROLLING/6.2.9-ARCH1-1/X86_64/3A87280F55>) |
| 8086:a2a1 | 103c:829a | Intel            | 200 Series/Z370 Chipset Family Po... | 23    |            | [EBA2B6CE4E](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/623C6DFA14C1/DEBIAN-12/6.1.0-7-AMD64/X86_64/EBA2B6CE4E>) |
| 8086:a36f |           | Intel            | Cannon Lake PCH Shared SRAM          | 23    |            | [7CCE222CE2](<Mini Pc/Apple/Macmini8/Macmini8,1/C2BFA09A14AD/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/7CCE222CE2>) |
| 8086:51ef |           | Intel            | Alder Lake PCH Shared SRAM           | 22    |            | [68B1E1E6CB](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/5A227E0116FB/KUBUNTU-23.04/6.3.1-CUSTOM/X86_64/68B1E1E6CB>) |
| 8086:a2a1 | 17aa:3111 | Intel            | 200 Series/Z370 Chipset Family Po... | 22    |            | [C95999B5AD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MR001YMZ/CF634F337F26/DEBIAN-11/5.10.0-22-AMD64/X86_64/C95999B5AD>) |
| 8086:4def | 1043:8813 | Intel            | Jasper Lake Shared SRAM Controller   | 20    |            | [99D3ECA719](<Mini Pc/CSL-Computer/Mini/Mini PN41/19DD952D9531/ZORIN-16/5.15.0-71-GENERIC/X86_64/99D3ECA719>) |
| 8086:a36f | 8086:7270 | Intel            | Cannon Lake PCH Shared SRAM          | 17    |            | [FEF5F08978](<Mini Pc/ZOTAC/ZBOX-EN7208/ZBOX-EN72080V-EN72070V-EN52060V-EN51660T/FEC8FB1A3ACB/XUBUNTU-20.04/5.4.0-65-GENERIC/X86_64/FEF5F08978>) |
| 8086:9d21 | 8086:7270 | Intel            | Sunrise Point-LP PMC                 | 14    |            | [86E1A89B72](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/E1E22FE45F6D/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/86E1A89B72>) |
| 8086:a36f | 17aa:3135 | Intel            | Cannon Lake PCH Shared SRAM          | 14    |            | [A1E7A34896](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CES0BH00/C62828790843/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.4-1-DEFAULT/X86_64/A1E7A34896>) |
| 8086:9def | 8086:7270 | Intel            | Cannon Point-LP Shared SRAM          | 11    |            | [2D07BFB282](<Mini Pc/Intel Client Systems/NUC8/NUC8v7PNH/AECCF9C01BD8/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/2D07BFB282>) |
| 8086:a2a1 | 103c:829e | Intel            | 200 Series/Z370 Chipset Family Po... | 11    |            | [8111885092](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G3 DM/31906DBA1358/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/8111885092>) |
| 8086:a36f | 17aa:3136 | Intel            | Cannon Lake PCH Shared SRAM          | 11    |            | [BDC231EAE9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RUS00300/1B1E837DD190/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/BDC231EAE9>) |
| 8086:02ef | 8086:7270 | Intel            | Comet Lake PCH-LP Shared SRAM        | 9     |            | [8042BCA2E6](<Mini Pc/AZW/SEi/SEi/96A7CA1D6C7E/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/8042BCA2E6>) |
| 8086:06ef | 17aa:316e | Intel            | Comet Lake PCH Shared SRAM           | 9     |            | [0C5D92EBF9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DT003GRU/DFE02E0590AD/RED-OS-7.3/5.15.87-1.EL7.3.X86_64/X86_64/0C5D92EBF9>) |
| 8086:06ef | 8086:7270 | Intel            | Comet Lake PCH Shared SRAM           | 9     |            | [6184308BD3](<Mini Pc/ZOTAC/ZBOX-ECM7307/ZBOX-ECM73070C-7307LH-53060C/97C1F8B840C8/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/6184308BD3>) |
| 8086:a121 | 19da:b333 | Intel            | 100 Series/C230 Series Chipset Fa... | 8     |            | [5F703BFC7D](<Mini Pc/ZOTAC/ZBOX-EN1070/ZBOX-EN1070-1060,EN1070K-1060K/C708E1327B22/OPENMANDRIVA-4.3/5.16.13-DESKTOP-1OMV4003/X86_64/5F703BFC7D>) |
| 8086:a2a1 | 103c:82a5 | Intel            | 200 Series/Z370 Chipset Family Po... | 8     |            | [C0BE7985C0](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 400 G3 DM/256EB048B176/FEDORA-36/5.19.16-200.FC36.X86_64/X86_64/C0BE7985C0>) |
| 8086:7aa7 |           | Intel            | Alder Lake-S PCH Shared SRAM         | 7     |            | [77577A0447](<Mini Pc/Intel Client Systems/NUC13/NUC13RNGi5/5FB909E0A69B/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/77577A0447>) |
| 8086:9def | 17aa:314d | Intel            | Cannon Point-LP Shared SRAM          | 7     |            | [4673EC60EA](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AD000UGE/E42960BAAF23/POP!_OS-22.04/6.0.12-76060006-GENERIC/X86_64/4673EC60EA>) |
| 8086:02ef | 1043:87bd | Intel            | Comet Lake PCH-LP Shared SRAM        | 6     |            | [8B7D9CA6FD](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN62S/C5A82ADBCB5E/OPENMANDRIVA-4.2/5.11.12-DESKTOP-1OMV4002/X86_64/8B7D9CA6FD>) |
| 8086:06ef | 103c:871a | Intel            | Comet Lake PCH Shared SRAM           | 6     |            | [B4B1C552AD](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 400 G6 Desktop Mini PC/44C939723A39/DEBIAN-11/5.15.85-1-PVE/X86_64/B4B1C552AD>) |
| 8086:4def | 8086:7270 | Intel            | Jasper Lake Shared SRAM Controller   | 6     |            | [0BAA359181](<Mini Pc/Chuwi/HeroBox/HeroBox Pro/7CB92A102103/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/0BAA359181>) |
| 8086:06ef | 103c:8715 | Intel            | Comet Lake PCH Shared SRAM           | 5     |            | [8D210CCE39](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G6 Desktop Mini PC/74BE63B62162/ENDEAVOUROS-ROLLING/6.2.12-ARCH1-1/X86_64/8D210CCE39>) |
| 8086:06ef | 17aa:3172 | Intel            | Comet Lake PCH Shared SRAM           | 5     |            | [1DDBBF71EB](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFCTO1WW/AEAA18AE3FAE/FEDORA-36/5.19.16-200.FC36.X86_64/X86_64/1DDBBF71EB>) |
| 8086:a121 | 103c:82c0 | Intel            | 100 Series/C230 Series Chipset Fa... | 5     |            | [C35B1DB9A1](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G3 Workstation/C879EA567BC9/UBUNTU-22.04/5.18.12-051812-GENERIC/X86_64/C35B1DB9A1>) |
| 8086:a2a1 | 17aa:310b | Intel            | 200 Series/Z370 Chipset Family Po... | 5     |            | [3F57FB1495](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M910q 10MVS02T00/FA0B01CC86C2/DEBIAN-11/5.15.85-1-PVE/X86_64/3F57FB1495>) |
| 8086:06ef | 103c:8710 | Intel            | Comet Lake PCH Shared SRAM           | 4     |            | [FDD0FEE41E](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G6 Desktop Mini PC/B77C187A6748/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/FDD0FEE41E>) |

### Multimedia (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0f38 |           | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     |            | [C4198C729C](<Mini Pc/AMI/Aptio/Aptio CRB/D031FAB792D1/ROSA-2016.1/4.13.6-NRJ-DESKTOP-1ROSA-X86_64/X86_64/C4198C729C>) |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15e2 | 1022:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 180   | snd_pci... | [6097531BFC](<Mini Pc/AZW/SER/SER/0FDA0A46CA08/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/6097531BFC>) |
| 8086:5a88 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 14    |            | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 1022:15e2 | 17aa:3190 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 9     | snd_pci... | [56B4F8A1A9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJ000BMZ/C185070F41DC/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/56B4F8A1A9>) |
| 8086:0f38 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 5     | intel_a... | [87E6D2F056](<Mini Pc/AMI/Aptio/Aptio CRB/BE0598986E2E/UBUNTU-19.10/5.3.0-55-GENERIC/X86_64/87E6D2F056>) |
| 1022:15e2 | 103c:8523 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 3     | snd_pci... | [57C13D1B6A](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/DD76DE9A334C/KDE-NEON-20.04/5.15.0-46-GENERIC/X86_64/57C13D1B6A>) |
| 1022:15e2 | 17aa:32e4 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     | snd_pci... | [F49F7BA847](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JNS02N00/EFCDDA73E969/RED-OS-7.3.1/5.15.35-5.EL7.3.X86_64/X86_64/F49F7BA847>) |
| 8086:0f38 | 1027:2014 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | intel_a... | [8932D07801](<Mini Pc/TMAX/TM800/TM800W560L/9FF0FC2CDFA2/ZORIN-16/5.13.0-48-GENERIC/X86_64/8932D07801>) |
| 8086:22b8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | intel_a... | [10C1838B9D](<Mini Pc/AMI/Aptio/Aptio CRB/6C7827486731/DEBIAN-11/5.10.0-8-AMD64/X86_64/10C1838B9D>) |
| 1022:15e2 | 103c:8522 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     | snd_pci... | [28B79EA28B](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/84561BBF7057/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/28B79EA28B>) |
| 1022:15e2 | 103c:873a | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     | snd_pci... | [5C3BE4E9AA](<Mini Pc/Hewlett-Packard/t540/t540 Thin Client/D3480EA77BCC/XUBUNTU-22.04/5.15.0-56-GENERIC/X86_64/5C3BE4E9AA>) |
| 1022:15e2 | 1043:8870 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     | snd_pci... | [73F7FB3F85](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN53/031C11533068/FEDORA-37/6.1.11-200.FC37.X86_64/X86_64/73F7FB3F85>) |
| 109e:0878 |           | Brooktree        | Bt878 Audio Capture                  | 1     |            | [10DB69DD6C](<Mini Pc/Kontron/SMX/SMX945/327FC59121CA/UBUNTU-18.04/4.15.0-88-GENERIC/I686/10DB69DD6C>) |
| 8086:0f38 | 8086:2212 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | atomisp    | [0734F58B03](<Mini Pc/NOBLEX/N15/N15W1/561537D5DFFE/KUBUNTU-22.04/6.0.0-060000-GENERIC/X86_64/0734F58B03>) |
| 8086:4e19 |           | Intel            | JasperLake IPU                       | 1     | intel_i... | [4D57E57019](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3/F8E05E061E2B/UBUNTU-22.04/5.15.0-41-GENERIC/X86_64/4D57E57019>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 317   | r8169      | [6097531BFC](<Mini Pc/AZW/SER/SER/0FDA0A46CA08/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/6097531BFC>) |
| 8086:15be | 8086:2074 | Intel            | Ethernet Connection (6) I219-V       | 206   | e1000e     | [A92B4A305F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/21A3465BD54D/DEBIAN-11/5.10.0-21-AMD64/X86_64/A92B4A305F>) |
| 14e4:1686 | 14e4:1686 | Broadcom         | NetXtreme BCM57766 Gigabit Ethern... | 161   | tg3        | [FA074ED7C9](<Mini Pc/Apple/Macmini7/Macmini7,1/9A4B9DC9209B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FA074ED7C9>) |
| 8086:0d4f | 8086:2081 | Intel            | Ethernet Connection (10) I219-V      | 123   | e1000e     | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 8086:15d8 | 8086:2068 | Intel            | Ethernet Connection (4) I219-V       | 104   | e1000e     | [05B1BDF24D](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/5A48D52A7EDA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/05B1BDF24D>) |
| 14e4:16b4 | 14e4:16b4 | Broadcom         | NetXtreme BCM57765 Gigabit Ethern... | 89    | tg3        | [0CCFB5109B](<Mini Pc/Apple/Macmini5/Macmini5,1/C751DFCA80AB/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/0CCFB5109B>) |
| 8086:15a3 | 8086:2057 | Intel            | Ethernet Connection (3) I218-V       | 72    | e1000e     | [D89F9A2346](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-507/128101606584/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/D89F9A2346>) |
| 10ec:8168 | 19da:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 60    | r8169      | [5F703BFC7D](<Mini Pc/ZOTAC/ZBOX-EN1070/ZBOX-EN1070-1060,EN1070K-1060K/C708E1327B22/OPENMANDRIVA-4.3/5.16.13-DESKTOP-1OMV4003/X86_64/5F703BFC7D>) |
| 8086:15b7 | 8086:0000 | Intel            | Ethernet Connection (2) I219-LM      | 54    | e1000e     | [68B65FDA4C](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/0FA94421095F/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/68B65FDA4C>) |
| 10ec:8168 | 8086:2060 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 48    | r8169      | [410350C836](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/99AD9DE0D682/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/410350C836>) |
| 10ec:8168 | 8086:2067 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 48    | r8169      | [AC904A4DF9](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-402/B3229CB33E06/FEDORA-39/6.3.0-0.RC6.20230411GIT0D3EB744AED4.50.FC39.X86_64/X86_64/AC904A4DF9>) |
| 10ec:8168 | 8086:2072 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 48    | r8169      | [D955CBB060](<Mini Pc/Intel/NUC7/NUC7PJYH/E5C0E8061815/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D955CBB060>) |
| 8086:15b7 | 8086:2064 | Intel            | Ethernet Connection (2) I219-LM      | 44    | e1000e     | [19BB30E27A](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-405/6215398CADD3/ARCH-ROLLING/6.2.11-ARCH1-1/X86_64/19BB30E27A>) |
| 8086:15f3 | 8086:0000 | Intel            | Ethernet Controller I225-V           | 41    | igc        | [BFFA46EF83](<Mini Pc/ATOPNUC/MA/MA90/A53ED68DF138/UBUNTUSTUDIO-23.04/6.2.0-1003-LOWLATENCY/X86_64/BFFA46EF83>) |
| 8086:15f3 | 8086:3004 | Intel            | Ethernet Controller I225-V           | 40    | igc        | [7232D92C69](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi5/E0ECB94FBAC3/DEBIAN-11/5.10.0-21-AMD64/X86_64/7232D92C69>) |
| 10de:0ab0 | 10de:cb79 | Nvidia           | MCP79 Ethernet                       | 38    | forcedeth  | [A206715EC6](<Mini Pc/Apple/Macmini3/Macmini3,1/807755291B05/UBUNTU-23.04/6.1.12-060112-GENERIC/X86_64/A206715EC6>) |
| 10ec:8168 | 1043:85b5 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 38    | r8169      | [C1BF3A9C44](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/24AA08459D0E/DEBIAN-11/5.10.0-20-AMD64/X86_64/C1BF3A9C44>) |
| 8086:1570 | 8086:2063 | Intel            | Ethernet Connection I219-V           | 29    | e1000e     | [C370821F44](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/C6B76D6C0340/ALMA-9.1/5.14.0-162.23.1.EL9_1.X86_64/X86_64/C370821F44>) |
| 8086:156f | 8086:2070 | Intel            | Ethernet Connection I219-LM          | 28    | e1000e     | [861B0673A0](<Mini Pc/Intel/NUC7/NUC7i5DNKE/960B20F7C35D/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/861B0673A0>) |
| 8086:15bc | 17aa:312d | Intel            | Ethernet Connection (7) I219-V       | 26    | e1000e     | [3A87280F55](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8SEYP00/41DB2AC53FB7/ARCH-ROLLING/6.2.9-ARCH1-1/X86_64/3A87280F55>) |
| 8086:15e3 | 103c:829a | Intel            | Ethernet Connection (5) I219-LM      | 23    | e1000e     | [EBA2B6CE4E](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/623C6DFA14C1/DEBIAN-12/6.1.0-7-AMD64/X86_64/EBA2B6CE4E>) |
| 14e4:16b1 | 103c:17e2 | Broadcom         | NetLink BCM57781 Gigabit Ethernet... | 22    | tg3        | [02EE837763](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/3EA0F94B1F39/DEBIAN-11/5.10.0-21-AMD64/X86_64/02EE837763>) |
| 8086:15b8 | 17aa:3111 | Intel            | Ethernet Connection (2) I219-V       | 22    | e1000e     | [C95999B5AD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MR001YMZ/CF634F337F26/DEBIAN-11/5.10.0-22-AMD64/X86_64/C95999B5AD>) |
| 11ab:4362 | 11ab:5321 | Marvell Techn... | 88E8053 PCI-E Gigabit Ethernet Co... | 20    | sky2       | [564A8CF5C2](<Mini Pc/Apple/Macmini2/Macmini2,1/F0A4DC4C2837/UBUNTU-18.04/5.4.0-131-GENERIC/X86_64/564A8CF5C2>) |
| 8086:15f3 | 8086:3024 | Intel            | Ethernet Controller I225-V           | 19    | igc        | [68B1E1E6CB](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/5A227E0116FB/KUBUNTU-23.04/6.3.1-CUSTOM/X86_64/68B1E1E6CB>) |
| 10ec:8168 | 1043:8677 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 18    | r8169      | [8C5E382D0A](<Mini Pc/ASUSTek Computer/PN/PN40/65635FC05246/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/8C5E382D0A>) |
| 14e4:1686 | 106b:0099 | Broadcom         | NetXtreme BCM57766 Gigabit Ethern... | 18    | tg3        | [7CCE222CE2](<Mini Pc/Apple/Macmini8/Macmini8,1/C2BFA09A14AD/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/7CCE222CE2>) |
| 10ec:8168 | 103c:8158 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 17    | r8169      | [A7D7E5C675](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/D14A501869D8/DEBIAN-11/5.10.0-19-AMD64/X86_64/A7D7E5C675>) |
| 10ec:8168 | 17aa:3130 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 17    | r8169      | [52B38CEE5C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VG000EUS/FEE9E9034339/KUBUNTU-22.10/5.19.0-26-GENERIC/X86_64/52B38CEE5C>) |
| 8086:15bb | 17aa:3135 | Intel            | Ethernet Connection (7) I219-LM      | 14    | e1000e     | [A1E7A34896](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CES0BH00/C62828790843/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.4-1-DEFAULT/X86_64/A1E7A34896>) |
| 8086:15f2 | 8086:3002 | Intel            | Ethernet Controller I225-LM          | 14    | igc        | [B85A510A03](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKi5/2E2F0EA6AA4A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/B85A510A03>) |
| 10ec:8168 | 103c:872e | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 13    | r8169      | [4BE8DDC98E](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/5D3851BCDC5D/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/4BE8DDC98E>) |
| 10ec:8168 | 8086:3027 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 12    | r8169      | [1B7F3C90CA](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/4F56B3D0D076/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/1B7F3C90CA>) |
| 8086:15bb | 8086:0000 | Intel            | Ethernet Connection (7) I219-LM      | 12    | e1000e     | [8749B43DB1](<Mini Pc/Intel Client Systems/NUC9/NUC9i9QNX/519180459546/UBUNTU-20.04/5.15.0-46-GENERIC/X86_64/8749B43DB1>) |
| 8086:15bb | 17aa:3136 | Intel            | Ethernet Connection (7) I219-LM      | 11    | e1000e     | [BDC231EAE9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RUS00300/1B1E837DD190/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/BDC231EAE9>) |
| 8086:15e3 | 103c:829e | Intel            | Ethernet Connection (5) I219-LM      | 11    | e1000e     | [8111885092](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G3 DM/31906DBA1358/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/8111885092>) |
| 10ec:8168 | 1028:080c | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 10    | r8169      | [71EE0575D4](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/06099CAD1A2D/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/71EE0575D4>) |
| 10ec:8168 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 10    | r8169      | [F4AFC80A6C](<Mini Pc/Umbrel/Home/Home/17E60BD189AC/DEBIAN-11/5.10.0-21-AMD64/X86_64/F4AFC80A6C>) |
| 10ec:8168 | 17aa:3190 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 9     | r8169      | [56B4F8A1A9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJ000BMZ/C185070F41DC/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/56B4F8A1A9>) |
| 14e4:1692 | 14e4:9692 | Broadcom         | NetLink BCM57780 Gigabit Ethernet... | 9     | tg3        | [241022B1D0](<Mini Pc/Hewlett-Packard/t510/t510 Thin Client/68BE52C35943/UBUNTU-18.04/4.15.0-176-GENERIC/X86_64/241022B1D0>) |
| 8086:0d4d | 17aa:316e | Intel            | Ethernet Connection (11) I219-V      | 9     | e1000e     | [0C5D92EBF9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DT003GRU/DFE02E0590AD/RED-OS-7.3/5.15.87-1.EL7.3.X86_64/X86_64/0C5D92EBF9>) |
| 8086:15f2 | 8086:2090 | Intel            | Ethernet Controller I225-LM          | 9     | igc        | [F28F7150BA](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/C55F851F02E4/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/F28F7150BA>) |
| 10ec:3000 | 09a3:1028 | Realtek Semic... | Killer E3000 2.5GbE Controller       | 8     | r8169      | [6184308BD3](<Mini Pc/ZOTAC/ZBOX-ECM7307/ZBOX-ECM73070C-7307LH-53060C/97C1F8B840C8/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/6184308BD3>) |
| 10ec:8136 | 17aa:368d | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 8     | r8169      | [BA6F405592](<Mini Pc/Lenovo/H30-00/H30-00 90C2003FMT/38341BB3FC42/UBUNTU-22.04/5.15.0-41-GENERIC/X86_64/BA6F405592>) |
| 10ec:8168 | 103c:82a5 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 8     | r8169      | [C0BE7985C0](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 400 G3 DM/256EB048B176/FEDORA-36/5.19.16-200.FC36.X86_64/X86_64/C0BE7985C0>) |
| 10ec:8168 | 17aa:30b5 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 8     | r8169      | [E4D5290D7B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M53 10DD001BFR/EB2BCA05FD7C/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/E4D5290D7B>) |
| 10ec:8168 | 1b50:4606 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 8     | r8169      | [AE8045E8DD](<Mini Pc/NOBLEX/NB/NB1601/6611033DEAB1/LINUXMINT-21/5.15.0-41-GENERIC/X86_64/AE8045E8DD>) |
| 8086:15be | 8086:0000 | Intel            | Ethernet Connection (6) I219-V       | 8     | e1000e     | [19000343FD](<Mini Pc/Chuwi/CoreBox/CoreBox/5D8F87EBC9F9/UBUNTU-UNITY-16.04/4.15.0-142-GENERIC/X86_64/19000343FD>) |
| 10ec:8168 | 17aa:3151 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 7     | r8169      | [6D4ECB5A00](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A5S1HM00/EDB5CB0BC766/FEDORA-36/6.1.5-100.FC36.X86_64/X86_64/6D4ECB5A00>) |
| 14e4:1686 | 14e4:9686 | Broadcom         | NetXtreme BCM57766 Gigabit Ethern... | 7     | tg3        | [12E9972D5A](<Mini Pc/Apple/Macmini8/Macmini8,1/0577EEAC7900/MX-21/6.1.0-T2/X86_64/12E9972D5A>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9df0 | 8086:0034 | Intel            | Cannon Point-LP CNVi [Wireless-AC]   | 216   | iwlwifi    | [A92B4A305F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/21A3465BD54D/DEBIAN-11/5.10.0-21-AMD64/X86_64/A92B4A305F>) |
| 8086:02f0 | 8086:0074 | Intel            | Comet Lake PCH-LP CNVi WiFi          | 130   | iwlwifi    | [8B7D9CA6FD](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN62S/C5A82ADBCB5E/OPENMANDRIVA-4.2/5.11.12-DESKTOP-1OMV4002/X86_64/8B7D9CA6FD>) |
| 8086:24fd | 8086:9010 | Intel            | Wireless 8265 / 8275                 | 99    | iwlwifi    | [05B1BDF24D](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/5A48D52A7EDA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/05B1BDF24D>) |
| 8086:3165 | 8086:4010 | Intel            | Wireless 3165                        | 95    | iwlwifi    | [410350C836](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/99AD9DE0D682/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/410350C836>) |
| 8086:24fd | 8086:1010 | Intel            | Wireless 8265 / 8275                 | 82    | iwlwifi    | [EBA2B6CE4E](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/623C6DFA14C1/DEBIAN-12/6.1.0-7-AMD64/X86_64/EBA2B6CE4E>) |
| 8086:095a | 8086:9010 | Intel            | Wireless 7265                        | 81    | iwlwifi    | [119A217E25](<Mini Pc/Fanless Mini PC/Quieter/Quieter2/074F07430469/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/119A217E25>) |
| 14e4:43a0 | 106b:013b | Broadcom Limited | BCM4360 802.11ac Wireless Network... | 76    | wl         | [FA074ED7C9](<Mini Pc/Apple/Macmini7/Macmini7,1/9A4B9DC9209B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FA074ED7C9>) |
| 8086:24f3 | 8086:9010 | Intel            | Wireless 8260                        | 69    | iwlwifi    | [19BB30E27A](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-405/6215398CADD3/ARCH-ROLLING/6.2.11-ARCH1-1/X86_64/19BB30E27A>) |
| 8086:2723 | 8086:0084 | Intel            | Wi-Fi 6 AX200                        | 66    | iwlwifi    | [ECF58906E7](<Mini Pc/AZW/SER/SER/89DAE8FF2DDA/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/ECF58906E7>) |
| 8086:a0f0 | 8086:0074 | Intel            | Wi-Fi 6 AX201                        | 64    | iwlwifi    | [B85A510A03](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKi5/2E2F0EA6AA4A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/B85A510A03>) |
| 14e4:4331 | 14e4:4331 | Broadcom         | BCM4331 802.11a/b/g/n                | 62    | wl         | [BF82BEBB69](<Mini Pc/Apple/Macmini5/Macmini5,1/F4FF1BC89D1F/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/BF82BEBB69>) |
| 14e4:4331 | 106b:010e | Broadcom         | BCM4331 802.11a/b/g/n                | 57    | wl         | [3DA35D8BC2](<Mini Pc/Apple/Macmini6/Macmini6,1/BE32E3873E80/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/3DA35D8BC2>) |
| 8086:24fb | 8086:2110 | Intel            | Dual Band Wireless-AC 3168NGW [St... | 56    | iwlwifi    | [AC904A4DF9](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-402/B3229CB33E06/FEDORA-39/6.3.0-0.RC6.20230411GIT0D3EB744AED4.50.FC39.X86_64/X86_64/AC904A4DF9>) |
| 8086:31dc | 8086:02a4 | Intel            | Gemini Lake PCH CNVi WiFi            | 54    | iwlwifi    | [68322A0698](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYHN/3A95FF73D4BD/UBUNTU-MATE-23.04/6.2.9-060209-GENERIC/X86_64/68322A0698>) |
| 14c3:0608 | 14c3:0608 | MediaTek         | MT7921K (RZ608) Wi-Fi 6E 80MHz       | 52    | mt7921e    | [6097531BFC](<Mini Pc/AZW/SER/SER/0FDA0A46CA08/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/6097531BFC>) |
| 14e4:4331 | 106b:00e4 | Broadcom Limited | BCM4331 802.11a/b/g/n                | 49    | wl         | [0CCFB5109B](<Mini Pc/Apple/Macmini5/Macmini5,1/C751DFCA80AB/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/0CCFB5109B>) |
| 8086:3165 | 8086:8010 | Intel            | Wireless 3165                        | 48    | iwlwifi    | [04A458482B](<Mini Pc/Fanless Mini PC/PCG35/PCG35 GLK/E97F04B2B1C1/TUXEDO-22.04/6.2.0-10005-TUXEDO/X86_64/04A458482B>) |
| 14e4:4328 | 106b:0090 | Broadcom Limited | BCM4321 802.11a/b/g/n                | 35    | ssb        | [CDC1678CAE](<Mini Pc/Apple/Macmini3/Macmini3,1/5B41FC221BF8/UBUNTU-20.04/5.15.0-46-GENERIC/X86_64/CDC1678CAE>) |
| 8086:24fd | 8086:0010 | Intel            | Wireless 8265 / 8275                 | 29    | iwlwifi    | [C0F2B10022](<Mini Pc/Lenovo/ThinkStation/ThinkStation P320 Tiny 30C2001XRU/9F9358369869/MANJARO-22.0.1/5.10.164-1-MANJARO/X86_64/C0F2B10022>) |
| 8086:08b3 | 8086:0070 | Intel            | Wireless 3160                        | 28    | iwlwifi    | [AD4D45D3FA](<Mini Pc/ZOTAC/ZBOXNANO-AQ/ZBOXNANO-AQ01/CB6345F9DAF9/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/AD4D45D3FA>) |
| 14e4:4353 | 106b:0093 | Broadcom         | BCM43224 802.11a/b/g/n               | 27    | bcma       | [6BAD65AD2D](<Mini Pc/Apple/Macmini4/Macmini4,1/43290460D960/ZORIN-16/5.15.0-69-GENERIC/X86_64/6BAD65AD2D>) |
| 8086:31dc | 8086:0264 | Intel            | Gemini Lake PCH CNVi WiFi            | 27    | iwlwifi    | [9FEB6E0D59](<Mini Pc/Chuwi/LarkBox/LarkBox Pro/F364AAE2AE09/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/9FEB6E0D59>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 26    | iwlwifi    | [8111885092](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G3 DM/31906DBA1358/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/8111885092>) |
| 14e4:4464 | 106b:07bf | Broadcom         | BCM4364 802.11ac Wireless Network... | 23    | brcmfmac   | [7CCE222CE2](<Mini Pc/Apple/Macmini8/Macmini8,1/C2BFA09A14AD/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/7CCE222CE2>) |
| 8086:3165 | 8086:8110 | Intel            | Wireless 3165                        | 22    | iwlwifi    | [BC18513752](<Mini Pc/iBall/CompBook/CompBook Premio V3/FF77B9DA22AC/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/BC18513752>) |
| 168c:0042 | 1a3b:2b51 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 21    | ath10k_pci | [1F1CB63EDC](<Mini Pc/Fanless Mini PC/PCG35/PCG35 GLK/E937013DF7EB/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/1F1CB63EDC>) |
| 168c:001c | 106b:0086 | Qualcomm Atheros | AR242x / AR542x Wireless Network ... | 20    | ath5k      | [564A8CF5C2](<Mini Pc/Apple/Macmini2/Macmini2,1/F0A4DC4C2837/UBUNTU-18.04/5.4.0-131-GENERIC/X86_64/564A8CF5C2>) |
| 8086:3166 | 8086:4210 | Intel            | Dual Band Wireless-AC 3165 Plus B... | 20    | iwlwifi    | [B88840BFDF](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MQA09ANZ/46EC40254521/POP!_OS-22.04/6.0.6-76060006-GENERIC/X86_64/B88840BFDF>) |
| 8086:51f0 | 8086:0094 | Intel            | Alder Lake-P PCH CNVi WiFi           | 19    | iwlwifi    | [68B1E1E6CB](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/5A227E0116FB/KUBUNTU-23.04/6.3.1-CUSTOM/X86_64/68B1E1E6CB>) |
| 10ec:c821 | 10ec:c821 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 16    | rtw88_8... | [4AC1BCCADA](<Mini Pc/Fanless Mini PC/Quieter/Quieter2/B4282FCEF933/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/4AC1BCCADA>) |
| 8086:2526 | 8086:0014 | Intel            | Wireless-AC 9260                     | 16    | iwlwifi    | [76433E9257](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JKS1MX00/558CB252A4B2/UBUNTU-22.10/5.19.0-26-GENERIC/X86_64/76433E9257>) |
| 8086:2723 | 1a56:1654 | Intel            | Wi-Fi 6 AX200                        | 14    | iwlwifi    | [6184308BD3](<Mini Pc/ZOTAC/ZBOX-ECM7307/ZBOX-ECM73070C-7307LH-53060C/97C1F8B840C8/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/6184308BD3>) |
| 8086:4df0 | 8086:0074 | Intel            | Wi-Fi 6 AX201 160MHz                 | 13    | iwlwifi    | [E812A255A4](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3/09653BE1DD03/MX-21/5.10.0-22-AMD64/X86_64/E812A255A4>) |
| 8086:4df0 | 8086:0034 | Intel            | Wi-Fi 6 AX201 160MHz                 | 12    | iwlwifi    | [99D3ECA719](<Mini Pc/CSL-Computer/Mini/Mini PN41/19DD952D9531/ZORIN-16/5.15.0-71-GENERIC/X86_64/99D3ECA719>) |
| 10ec:c822 | 1a3b:3751 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 11    | rtw88_8... | [BFFA46EF83](<Mini Pc/ATOPNUC/MA/MA90/A53ED68DF138/UBUNTUSTUDIO-23.04/6.2.0-1003-LOWLATENCY/X86_64/BFFA46EF83>) |
| 8086:06f0 | 8086:0070 | Intel            | Comet Lake PCH CNVi WiFi             | 11    | iwlwifi    | [0C5D92EBF9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DT003GRU/DFE02E0590AD/RED-OS-7.3/5.15.87-1.EL7.3.X86_64/X86_64/0C5D92EBF9>) |
| 8086:08b3 | 8086:8070 | Intel            | Wireless 3160                        | 11    | iwlwifi    | [762CB319C6](<Mini Pc/ZOTAC/ZBOX/ZBOX/25512EE3A2CB/KDE-NEON-22.04/5.15.0-60-GENERIC/X86_64/762CB319C6>) |
| 8086:4df0 | 8086:02a4 | Intel            | Wi-Fi 6 AX201 160MHz                 | 11    | iwlwifi    | [1B7F3C90CA](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/4F56B3D0D076/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/1B7F3C90CA>) |
| 10ec:b723 | 10ec:b723 | Realtek Semic... | RTL8723BE PCIe Wireless Network A... | 10    | rtl8723be  | [AE8045E8DD](<Mini Pc/NOBLEX/NB/NB1601/6611033DEAB1/LINUXMINT-21/5.15.0-41-GENERIC/X86_64/AE8045E8DD>) |
| 10ec:c822 | 17aa:c123 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 10    | rtw88_8... | [17F1E0F135](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q Gen 2 11MY003MRU/9EE717DD71FC/RED-OS-7.3/5.15.87-1.EL7.3.X86_64/X86_64/17F1E0F135>) |
| 8086:06f0 | 8086:0074 | Intel            | Comet Lake PCH CNVi WiFi             | 10    | iwlwifi    | [8D210CCE39](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G6 Desktop Mini PC/74BE63B62162/ENDEAVOUROS-ROLLING/6.2.12-ARCH1-1/X86_64/8D210CCE39>) |
| 8086:24fd | 8086:0110 | Intel            | Wireless 8265 / 8275                 | 9     | iwlwifi    | [14761D1566](<Mini Pc/CSL-Computer/Celeron/Celeron/AA990300D125/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/14761D1566>) |
| 8086:a370 | 8086:0030 | Intel            | Cannon Lake PCH CNVi WiFi            | 9     | iwlwifi    | [01D39BC0CA](<Mini Pc/Lenovo/M920q/M920q 10RS/5E8E3BCCFC40/POP!_OS-22.04/6.0.12-76060006-GENERIC/X86_64/01D39BC0CA>) |
| 10ec:c822 | 1a3b:4210 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 8     | rtw88_8... | [91696FE0F2](<Mini Pc/BESSTAR Tech/GK/GK50/0786D176E577/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/91696FE0F2>) |
| 8086:2725 | 8086:0024 | Intel            | Wi-Fi 6 AX210/AX211/AX411 160MHz     | 8     | iwlwifi    | [3A2E981385](<Mini Pc/Others/V/V00/E328A5C71B69/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/3A2E981385>) |
| 8086:24f3 | 8086:10b0 | Intel            | Wireless 8260                        | 7     | iwlwifi    | [F7FC2A9686](<Mini Pc/CompuLab/fitlet/fitlet2/C10956CC758D/DEBIAN-11/5.10.0-17-AMD64/X86_64/F7FC2A9686>) |
| 8086:31dc | 8086:0034 | Intel            | Gemini Lake PCH CNVi WiFi            | 7     | iwlwifi    | [8C5E382D0A](<Mini Pc/ASUSTek Computer/PN/PN40/65635FC05246/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/8C5E382D0A>) |
| 8086:a0f0 | 8086:0070 | Intel            | Wi-Fi 6 AX201                        | 7     | iwlwifi    | [94D4FE9A93](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKv7/10393889EC9C/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/94D4FE9A93>) |
| 10ec:b723 | 17aa:b728 | Realtek Semic... | RTL8723BE PCIe Wireless Network A... | 6     | rtl8723be  | [CE2A33CAFF](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M53 10DE001HUS/32B998916CDE/DEBIAN-11/5.10.0-18-AMD64/X86_64/CE2A33CAFF>) |
| 14c3:0616 | 105b:e0cd | MediaTek         | MT7922 802.11ax PCI Express Wirel... | 6     | mt7921e    | [5F0D451EE3](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN52/15A1BF409ED4/ROSA-12.3/6.0.12.XM1-1.KLP-XANMOD-ROSA2021.1-X86_64/X86_64/5F0D451EE3>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:157b | 8086:0000 | Intel            | I210 Gigabit Network Connection      | 51    | igb        | [68B65FDA4C](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/0FA94421095F/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/68B65FDA4C>) |
| 10ec:8125 | 1043:87d7 | Realtek Semic... | RTL8125 2.5GbE Controller            | 45    | r8169      | [99D3ECA719](<Mini Pc/CSL-Computer/Mini/Mini PN41/19DD952D9531/ZORIN-16/5.15.0-71-GENERIC/X86_64/99D3ECA719>) |
| 8086:1539 | 8086:0000 | Intel            | I211 Gigabit Network Connection      | 30    | igb        | [7241638915](<Mini Pc/AMI/Aptio/Aptio CRB/F6266ED51964/UBUNTU-20.04/5.15.0-48-GENERIC/X86_64/7241638915>) |
| 10ec:8125 | 10ec:0123 | Realtek Semic... | RTL8125 2.5GbE Controller            | 29    | r8169      | [74F148FB60](<Mini Pc/AZW/SER/SER/6ACE98838322/GARUDA-SOARING/6.3.0-AMD-ZNVER2/X86_64/74F148FB60>) |
| 8086:1533 | ffff:0000 | Intel            | I210 Gigabit Network Connection      | 26    | igb        | [DD887AFD02](<Mini Pc/NEXCOM/VTC/VTC1010/6EF054560413/DEBIAN-TESTING/5.19.0-2-AMD64/X86_64/DD887AFD02>) |
| 8086:1502 | 8086:0000 | Intel            | 82579LM Gigabit Network Connectio... | 4     | e1000e     | [AD65FE187A](<Mini Pc/CompuLab/Intense-PC/Intense-PC/F82D466DC54E/KDE-NEON-22.04/5.15.0-56-GENERIC/X86_64/AD65FE187A>) |
| 8086:1521 | 15d9:0652 | Intel            | I350 Gigabit Network Connection      | 4     | igb        | [8DC6B94CBD](<Mini Pc/Supermicro/SYS-5039/SYS-5039MS-H12TRF-OS012/E04529F8DAEB/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/8DC6B94CBD>) |
| 8086:1503 | 1734:11d9 | Intel            | 82579V Gigabit Network Connection    | 3     | e1000e     | [273CE0954A](<Mini Pc/Fujitsu/ESPRIMO/ESPRIMO Q510/694AE29C9C7C/DEBIAN-11/5.10.0-17-AMD64/X86_64/273CE0954A>) |
| 8086:1533 | 1ab6:0214 | Intel            | I210 Gigabit Network Connection      | 3     | igb        | [8EF2E84F50](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/285ACAA734D3/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/8EF2E84F50>) |
| 8086:1539 | 8086:2080 | Intel            | I211 Gigabit Network Connection      | 3     | igb        | [D686B50BA5](<Mini Pc/Intel Client Systems/NUC8/NUC8CCHK/6D7DBA663446/DEBIAN-11/5.10.0-13-AMD64/X86_64/D686B50BA5>) |
| 8086:4ba0 | 8086:7270 | Intel            | Ethernet controller                  | 2     | dwmac_i... | [E0C6234F77](<Mini Pc/congatec/conga-PA7/conga-PA7 A.0/FC51E41C422F/UBUNTU-22.04/5.15.0-25-GENERIC/X86_64/E0C6234F77>) |
| 8086:4bb0 | 8086:7270 | Intel            | Ethernet controller                  | 2     | dwmac_i... | [E0C6234F77](<Mini Pc/congatec/conga-PA7/conga-PA7 A.0/FC51E41C422F/UBUNTU-22.04/5.15.0-25-GENERIC/X86_64/E0C6234F77>) |
| 14e4:5f69 | 106b:4378 | Broadcom         | BRCM4378 Bluetooth Controller        | 1     | hci_bcm... | [F6634D3A58](<Mini Pc/Others/Apple/Apple Mac mini/8D3727CCFCBE/ARCHARM/5.19.0-ASAHI-5-1-ARCH/AARCH64/F6634D3A58>) |
| 8086:1093 | 8086:0001 | Intel            | PRO/100 VM Network Connection        | 1     | e100       | [10DB69DD6C](<Mini Pc/Kontron/SMX/SMX945/327FC59121CA/UBUNTU-18.04/4.15.0-88-GENERIC/I686/10DB69DD6C>) |
| 8086:10fe | 17aa:3605 | Intel            | 82552 10/100 Network Connection      | 1     | e100       | [F077B2F98E](<Mini Pc/Lenovo/3000/3000 IdeaCentre Q150 10053/8A86675CFC31/UBUNTU-18.04/5.0.0-27-GENERIC/X86_64/F077B2F98E>) |
| 8086:150c | 8086:0000 | Intel            | 82583V Gigabit Network Connection    | 1     | e1000e     | [F483DDC44F](<Mini Pc/AMI/Aptio/Aptio CRB/CA0946537674/ALPINE-3.15.0/5.15.12-0-LTS/X86_64/F483DDC44F>) |
| 8086:1533 | 15bd:100a | Intel            | I210 Gigabit Network Connection      | 1     | igb        | [593A489E8D](<Mini Pc/ARBOR/LYNC/LYNC-712/F11739CA6754/ALT-9.1/5.4.51-STD-DEF-ALT1/X86_64/593A489E8D>) |
| 8086:1539 | 1043:85f0 | Intel            | I211 Gigabit Network Connection      | 1     | igb        | [6C00869D7B](<Mini Pc/ASUSTek Computer/PN/PN41/868E1EC59BE7/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/6C00869D7B>) |
| 8086:1539 | 1297:4033 | Intel            | I211 Gigabit Network Connection      | 1     | igb        | [B31E28E55F](<Mini Pc/Shuttle/XS35/XS35V5/00878A051AA2/UBUNTU-19.10/5.3.0-42-GENERIC/X86_64/B31E28E55F>) |
| 8086:422b | 8086:0000 | Intel            | Centrino Ultimate-N 6300             | 1     |            | [86523F9A5F](<Mini Pc/WYSE/Dell/Dell Thin Client Desktop 3290/3455973AC1A4/LINUX-LITE-6.0/5.15.0-46-GENERIC/X86_64/86523F9A5F>) |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a126 |           | Intel            | 100 Series/C230 Series Chipset Fa... | 4     | intel_t... | [5F703BFC7D](<Mini Pc/ZOTAC/ZBOX-EN1070/ZBOX-EN1070-1060,EN1070K-1060K/C708E1327B22/OPENMANDRIVA-4.3/5.16.13-DESKTOP-1OMV4003/X86_64/5F703BFC7D>) |
| 1022:145a | 1022:7901 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 3     |            | [037E8C7254](<Mini Pc/AZW/SER/SER/FA045DCBCCD5/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/037E8C7254>) |
| 8086:9d26 |           | Intel            | Skylake-U/Y Northpeak                | 1     | intel_t... | [D88CB8B5AE](<Mini Pc/Fanless Mini PC/PCG35/PCG35 GLK/E97F04B2B1C1/KUBUNTU-22.04/5.13.0-19-GENERIC/X86_64/D88CB8B5AE>) |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 106b:1801 | 106b:1801 | Apple            | T2 Bridge Controller                 | 23    | apple_bce  | [7CCE222CE2](<Mini Pc/Apple/Macmini8/Macmini8,1/C2BFA09A14AD/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/7CCE222CE2>) |
| 106b:1802 | 106b:1802 | Apple            | T2 Secure Enclave Processor          | 23    |            | [7CCE222CE2](<Mini Pc/Apple/Macmini8/Macmini8,1/C2BFA09A14AD/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/7CCE222CE2>) |
| 1022:15e6 | 1022:15e4 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 20    | i2c_amd... | [86A3944105](<Mini Pc/AZW/SER/SER/4F9AF19348C5/DEBIAN-11/5.10.6-1-PVE/X86_64/86A3944105>) |
| 8086:a135 | 15d9:0898 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     | intel_i... | [8DC6B94CBD](<Mini Pc/Supermicro/SYS-5039/SYS-5039MS-H12TRF-OS012/E04529F8DAEB/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/8DC6B94CBD>) |

### Performance counters (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:27a3 |           | Intel            | 945GM/GU Chipset Hardware Monitor... | 20    |            | [564A8CF5C2](<Mini Pc/Apple/Macmini2/Macmini2,1/F0A4DC4C2837/UBUNTU-18.04/5.4.0-131-GENERIC/X86_64/564A8CF5C2>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14e4:16bc | 14e4:0000 | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 250   | sdhci_pci  | [0CCFB5109B](<Mini Pc/Apple/Macmini5/Macmini5,1/C751DFCA80AB/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/0CCFB5109B>) |
| 17a0:9755 | 8086:2081 | Genesys Logic    | GL9755 SD Host Controller            | 119   | sdhci_pci  | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 8086:31cc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 55    | sdhci_pci  | [1F1CB63EDC](<Mini Pc/Fanless Mini PC/PCG35/PCG35 GLK/E937013DF7EB/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/1F1CB63EDC>) |
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 55    | sdhci_pci  | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 1217:8621 | 8086:2073 | O2 Micro         | SD/MMC Card Reader Controller        | 53    | sdhci_pci  | [68B65FDA4C](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/0FA94421095F/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/68B65FDA4C>) |
| 8086:31cc | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 48    | sdhci_pci  | [D955CBB060](<Mini Pc/Intel/NUC7/NUC7PJYH/E5C0E8061815/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D955CBB060>) |
| 1217:8621 | 8086:2064 | O2 Micro         | SD/MMC Card Reader Controller        | 43    | sdhci_pci  | [19BB30E27A](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-405/6215398CADD3/ARCH-ROLLING/6.2.11-ARCH1-1/X86_64/19BB30E27A>) |
| 8086:31cc | 8086:31cc | Intel            | Celeron/Pentium Silver Processor ... | 43    | sdhci_pci  | [91696FE0F2](<Mini Pc/BESSTAR Tech/GK/GK50/0786D176E577/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/91696FE0F2>) |
| 8086:5aca | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 43    | sdhci_pci  | [6EA31CC2ED](<Mini Pc/AMI/Aptio/Aptio CRB/5AEFCC18D04F/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/6EA31CC2ED>) |
| 8086:31d0 | 8086:7270 | Intel            | Celeron/Pentium Silver SD Host Co... | 37    | sdhci_pci  | [9FEB6E0D59](<Mini Pc/Chuwi/LarkBox/LarkBox Pro/F364AAE2AE09/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/9FEB6E0D59>) |
| 8086:5ad0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 37    | sdhci_pci  | [7C4F6801F0](<Mini Pc/CSL-Computer/Narrow/Narrow Box Ultra HD Compact/B849F9AC9470/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/7C4F6801F0>) |
| 8086:2296 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 31    | sdhci_pci  | [410350C836](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/99AD9DE0D682/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/410350C836>) |
| 8086:9d2d | 8086:2063 | Intel            | Sunrise Point-LP Secure Digital I... | 27    | sdhci_pci  | [C370821F44](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/C6B76D6C0340/ALMA-9.1/5.14.0-162.23.1.EL9_1.X86_64/X86_64/C370821F44>) |
| 8086:4dc4 |           | Intel            | Jasper Lake SCS1: eMMC Controller    | 21    | sdhci_pci  | [E812A255A4](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3/09653BE1DD03/MX-21/5.10.0-22-AMD64/X86_64/E812A255A4>) |
| 8086:4dc4 | 1043:8813 | Intel            | Jasper Lake SCS1: eMMC Controller    | 20    | sdhci_pci  | [99D3ECA719](<Mini Pc/CSL-Computer/Mini/Mini PN41/19DD952D9531/ZORIN-16/5.15.0-71-GENERIC/X86_64/99D3ECA719>) |
| 8086:4df8 |           | Intel            | SD Host Controller                   | 19    | sdhci_pci  | [E812A255A4](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3/09653BE1DD03/MX-21/5.10.0-22-AMD64/X86_64/E812A255A4>) |
| 1022:7906 | 1022:7806 | AMD              | FCH SD Flash Controller              | 11    | sdhci_pci  | [BFFA46EF83](<Mini Pc/ATOPNUC/MA/MA90/A53ED68DF138/UBUNTUSTUDIO-23.04/6.2.0-1003-LOWLATENCY/X86_64/BFFA46EF83>) |
| 8086:4dc4 | 8086:3027 | Intel            | Jasper Lake SCS1: eMMC Controller    | 11    | sdhci_pci  | [1B7F3C90CA](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/4F56B3D0D076/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/1B7F3C90CA>) |
| 8086:5ad0 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 11    | sdhci_pci  | [B23AC4ACF0](<Mini Pc/ZOTAC/ZBOX-PI/ZBOX-PI335/B3E1B5172912/UBUNTU-22.04/5.15.0-41-GENERIC/X86_64/B23AC4ACF0>) |
| 8086:31cc | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 10    | sdhci_pci  | [71EE0575D4](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/06099CAD1A2D/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/71EE0575D4>) |
| 17a0:9755 | 8086:3004 | Genesys Logic    | GL9755 SD Host Controller            | 9     | sdhci_pci  | [7232D92C69](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi5/E0ECB94FBAC3/DEBIAN-11/5.10.0-21-AMD64/X86_64/7232D92C69>) |
| 8086:0f50 |           | Intel            | Atom Processor E3800 Series eMMC ... | 7     | sdhci_pci  | [3749438EF1](<Mini Pc/Exo/Smart/Smart R8-CE/13753A7E26E0/POP!_OS-22.04/5.19.16-76051916-GENERIC/X86_64/3749438EF1>) |
| 8086:0f16 | 8086:0f16 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | sdhci_pci  | [DD887AFD02](<Mini Pc/NEXCOM/VTC/VTC1010/6EF054560413/DEBIAN-TESTING/5.19.0-2-AMD64/X86_64/DD887AFD02>) |
| 8086:4dc4 | 8086:7270 | Intel            | Jasper Lake SCS1: eMMC Controller    | 6     | sdhci_pci  | [0BAA359181](<Mini Pc/Chuwi/HeroBox/HeroBox Pro/7CB92A102103/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/0BAA359181>) |
| 8086:4df8 | 8086:7270 | Intel            | SD Host Controller                   | 6     | sdhci_pci  | [0BAA359181](<Mini Pc/Chuwi/HeroBox/HeroBox Pro/7CB92A102103/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/0BAA359181>) |
| 8086:5acc | 19da:b325 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 6     | sdhci_pci  | [23BDDBF63A](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/0FE806EB02BE/LINUXMINT-20.1/5.4.0-65-GENERIC/X86_64/23BDDBF63A>) |
| 8086:02c4 | 8086:7270 | Intel            | Comet Lake PCH-LP SCS1: eMMC         | 5     | sdhci_pci  | [8042BCA2E6](<Mini Pc/AZW/SEi/SEi/96A7CA1D6C7E/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/8042BCA2E6>) |
| 8086:2294 | 1462:b120 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | sdhci_pci  | [4C3E0A0AC6](<Mini Pc/MSI/MS-B/MS-B120/3412F4B83350/UBUNTU-MATE-23.04/6.3.1-060301-GENERIC/X86_64/4C3E0A0AC6>) |
| 8086:2295 | 1028:07c1 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | sdhci_pci  | [F1FB89D0F7](<Mini Pc/Dell/Wyse/Wyse 3040 Thin Client/AC1F30A762B7/DEBIAN-11/5.10.0-21-AMD64/X86_64/F1FB89D0F7>) |
| 8086:0f16 | 19da:b219 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 4     | sdhci_pci  | [E2A827D41B](<Mini Pc/ZOTAC/ZBOX-CI320NANO/ZBOX-CI320NANO series/EF9DDA5FE7DD/LINUXMINT-21/5.15.0-48-GENERIC/X86_64/E2A827D41B>) |
| 8086:5acc | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | sdhci_pci  | [E86F93CF49](<Mini Pc/Intel Client Systems/NUC6/NUC6CAYS/964F9DF89D52/UBUNTU-22.04/5.15.0-46-GENERIC/X86_64/E86F93CF49>) |
| 8086:5acc | 8086:5acc | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | sdhci_pci  | [6874BC3566](<Mini Pc/BESSTAR Tech/N/N33/2A74991B0C12/UBUNTU-20.04/5.11.0-44-GENERIC/X86_64/6874BC3566>) |
| 1022:7806 | 19da:a261 | AMD              | FCH SD Flash Controller              | 3     | sdhci_pci  | [3A6297D90B](<Mini Pc/ZOTAC/ZBOXNANO-AD/ZBOXNANO-AD12/1942AB43E912/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/3A6297D90B>) |
| 1217:8520 | 1217:0002 | O2 Micro         | SD/MMC Card Reader Controller        | 3     | sdhci_pci  | [6F53D65339](<Mini Pc/ZOTAC/ZBOX-EN1730/ZBOX-EN173080C-EN173070C-EN153060C-QTG7A4500/FB5898E3AED0/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/6F53D65339>) |
| 8086:2294 | 19da:b273 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | sdhci_pci  | [0D05B404DD](<Mini Pc/ZOTAC/ZBOX-BI/ZBOX-BI324/C214E8207F22/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/0D05B404DD>) |
| 8086:2294 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | sdhci_pci  | [DCC1CCB590](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-408/59A86BD4C203/LINUXMINT-19.3/5.4.0-80-GENERIC/X86_64/DCC1CCB590>) |
| 8086:2294 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | sdhci_pci  | [10C1838B9D](<Mini Pc/AMI/Aptio/Aptio CRB/6C7827486731/DEBIAN-11/5.10.0-8-AMD64/X86_64/10C1838B9D>) |
| 8086:2296 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | sdhci_pci  | [10C1838B9D](<Mini Pc/AMI/Aptio/Aptio CRB/6C7827486731/DEBIAN-11/5.10.0-8-AMD64/X86_64/10C1838B9D>) |
| 8086:5aca | 8086:1e8b | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | sdhci_pci  | [568740A6B1](<Mini Pc/Intel/AB2/AB2L/5A3D6A149496/DEBIAN-11/5.10.0-21-AMD64/X86_64/568740A6B1>) |
| 8086:5aca | 8086:5aca | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | sdhci_pci  | [6874BC3566](<Mini Pc/BESSTAR Tech/N/N33/2A74991B0C12/UBUNTU-20.04/5.11.0-44-GENERIC/X86_64/6874BC3566>) |
| 8086:5acc | 8086:1e8b | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | sdhci_pci  | [568740A6B1](<Mini Pc/Intel/AB2/AB2L/5A3D6A149496/DEBIAN-11/5.10.0-21-AMD64/X86_64/568740A6B1>) |
| 8086:5acc | 8086:2080 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | sdhci_pci  | [D686B50BA5](<Mini Pc/Intel Client Systems/NUC8/NUC8CCHK/6D7DBA663446/DEBIAN-11/5.10.0-13-AMD64/X86_64/D686B50BA5>) |
| 8086:5ad0 | 8086:1e8b | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | sdhci_pci  | [568740A6B1](<Mini Pc/Intel/AB2/AB2L/5A3D6A149496/DEBIAN-11/5.10.0-21-AMD64/X86_64/568740A6B1>) |
| 1022:7806 | 19da:b218 | AMD              | FCH SD Flash Controller              | 2     | sdhci_pci  | [619BD547D1](<Mini Pc/ZOTAC/ZBOXNANO-AQ/ZBOXNANO-AQ02/B80DC01E2387/LINUXMINT-20.3/5.4.0-121-GENERIC/X86_64/619BD547D1>) |
| 14e4:16bc | 14e4:96bc | Broadcom Limited | BCM57765/57785 SDXC/MMC Card Reader  | 2     | sdhci_pci  | [BEF5CE8984](<Mini Pc/Apple/Macmini8/Macmini8,1/453BE981DB64/UBUNTU-22.10/6.1.2-T2-KINETIC/X86_64/BEF5CE8984>) |
| 8086:5aca | 19da:b342 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | sdhci_pci  | [B23AC4ACF0](<Mini Pc/ZOTAC/ZBOX-PI/ZBOX-PI335/B3E1B5172912/UBUNTU-22.04/5.15.0-41-GENERIC/X86_64/B23AC4ACF0>) |
| 8086:5acc | 19da:b342 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | sdhci_pci  | [B23AC4ACF0](<Mini Pc/ZOTAC/ZBOX-PI/ZBOX-PI335/B3E1B5172912/UBUNTU-22.04/5.15.0-41-GENERIC/X86_64/B23AC4ACF0>) |
| 8086:9d2b | 1043:8694 | Intel            | Skylake-U/Y SCC: eMMC                | 2     | sdhci_pci  | [847A813A2C](<Mini Pc/ASUSTek Computer/PN60/PN60-R/1051BA1EB3B1/MANJARO/5.10.15-1-MANJARO/X86_64/847A813A2C>) |
| 8086:9dc4 | 8086:2075 | Intel            | Cannon Point-LP SD Host Controller   | 2     | sdhci_pci  | [D9AC661777](<Mini Pc/Intel Client Systems/NUC8/NUC8i3CYS/F84856907C67/KALI-2021.3/5.10.0-KALI9-AMD64/X86_64/D9AC661777>) |
| 8086:9df5 | 8086:2075 | Intel            | BayHubTech Integrated SD controller  | 2     | sdhci_pci  | [D9AC661777](<Mini Pc/Intel Client Systems/NUC8/NUC8i3CYS/F84856907C67/KALI-2021.3/5.10.0-KALI9-AMD64/X86_64/D9AC661777>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9da4 | 8086:2074 | Intel            | Cannon Point-LP SPI Controller       | 207   |            | [A92B4A305F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/21A3465BD54D/DEBIAN-11/5.10.0-21-AMD64/X86_64/A92B4A305F>) |
| 8086:02a4 | 8086:2081 | Intel            | Comet Lake SPI (flash) Controller    | 123   | intel_s... | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 8086:02e8 | 8086:2081 | Intel            | Serial IO I2C Host Controller        | 123   | intel_l... | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 8086:02ea | 8086:2081 | Intel            | Comet Lake PCH-LP LPSS: I2C Contr... | 123   | intel_l... | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 8086:4dab |           | Intel            | Jasper Lake LPSS: SPI Controller #1  | 43    | intel_l... | [99D3ECA719](<Mini Pc/CSL-Computer/Mini/Mini PN41/19DD952D9531/ZORIN-16/5.15.0-71-GENERIC/X86_64/99D3ECA719>) |
| 8086:a0a4 | 8086:3004 | Intel            | Tiger Lake-LP SPI Controller         | 41    | intel_spi  | [7232D92C69](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi5/E0ECB94FBAC3/DEBIAN-11/5.10.0-21-AMD64/X86_64/7232D92C69>) |
| 8086:a0e8 | 8086:3004 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 41    | intel_l... | [7232D92C69](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi5/E0ECB94FBAC3/DEBIAN-11/5.10.0-21-AMD64/X86_64/7232D92C69>) |
| 8086:5ac8 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 39    | pwm_lpss   | [AC904A4DF9](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-402/B3229CB33E06/FEDORA-39/6.3.0-0.RC6.20230411GIT0D3EB744AED4.50.FC39.X86_64/X86_64/AC904A4DF9>) |
| 8086:22c6 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 31    | i2c_des... | [410350C836](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/99AD9DE0D682/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/410350C836>) |
| 8086:22c7 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 31    | i2c_des... | [410350C836](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/99AD9DE0D682/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/410350C836>) |
| 8086:a324 | 17aa:312d | Intel            | Cannon Lake PCH SPI Controller       | 26    | intel_spi  | [3A87280F55](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8SEYP00/41DB2AC53FB7/ARCH-ROLLING/6.2.9-ARCH1-1/X86_64/3A87280F55>) |
| 8086:a324 | 8086:7270 | Intel            | Cannon Lake PCH SPI Controller       | 24    | spi_int... | [7CCE222CE2](<Mini Pc/Apple/Macmini8/Macmini8,1/C2BFA09A14AD/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/7CCE222CE2>) |
| 8086:4da4 |           | Intel            | Jasper Lake SPI Controller           | 21    | spi_int... | [E812A255A4](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3/09653BE1DD03/MX-21/5.10.0-22-AMD64/X86_64/E812A255A4>) |
| 8086:4da4 | 1043:8813 | Intel            | Jasper Lake SPI Controller           | 20    | intel_s... | [99D3ECA719](<Mini Pc/CSL-Computer/Mini/Mini PN41/19DD952D9531/ZORIN-16/5.15.0-71-GENERIC/X86_64/99D3ECA719>) |
| 8086:4dc5 | 1043:8813 | Intel            | Jasper Lake LPSS: I2C Controller #4  | 20    | intel_l... | [99D3ECA719](<Mini Pc/CSL-Computer/Mini/Mini PN41/19DD952D9531/ZORIN-16/5.15.0-71-GENERIC/X86_64/99D3ECA719>) |
| 8086:4dc6 | 1043:8813 | Intel            | Jasper Lake LPSS: I2C Controller #5  | 20    | intel_l... | [99D3ECA719](<Mini Pc/CSL-Computer/Mini/Mini PN41/19DD952D9531/ZORIN-16/5.15.0-71-GENERIC/X86_64/99D3ECA719>) |
| 8086:4de8 | 1043:8813 | Intel            | Serial IO I2C Host Controller        | 20    | intel_l... | [99D3ECA719](<Mini Pc/CSL-Computer/Mini/Mini PN41/19DD952D9531/ZORIN-16/5.15.0-71-GENERIC/X86_64/99D3ECA719>) |
| 8086:4dea | 1043:8813 | Intel            | Jasper Lake LPSS: I2C Controller #2  | 20    | intel_l... | [99D3ECA719](<Mini Pc/CSL-Computer/Mini/Mini PN41/19DD952D9531/ZORIN-16/5.15.0-71-GENERIC/X86_64/99D3ECA719>) |
| 8086:51a4 | 8086:3024 | Intel            | Alder Lake-P PCH SPI Controller      | 19    | spi_int... | [68B1E1E6CB](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/5A227E0116FB/KUBUNTU-23.04/6.3.1-CUSTOM/X86_64/68B1E1E6CB>) |
| 8086:51e8 | 8086:3024 | Intel            | Alder Lake PCH Serial IO I2C Cont... | 19    | intel_l... | [68B1E1E6CB](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/5A227E0116FB/KUBUNTU-23.04/6.3.1-CUSTOM/X86_64/68B1E1E6CB>) |
| 8086:51e9 | 8086:3024 | Intel            | Alder Lake PCH Serial IO I2C Cont... | 19    | intel_l... | [68B1E1E6CB](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/5A227E0116FB/KUBUNTU-23.04/6.3.1-CUSTOM/X86_64/68B1E1E6CB>) |
| 8086:5ac8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 14    | pwm_lpss   | [F7FC2A9686](<Mini Pc/CompuLab/fitlet/fitlet2/C10956CC758D/DEBIAN-11/5.10.0-17-AMD64/X86_64/F7FC2A9686>) |
| 8086:a0a4 | 8086:3002 | Intel            | Tiger Lake-LP SPI Controller         | 14    | spi_int... | [B85A510A03](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKi5/2E2F0EA6AA4A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/B85A510A03>) |
| 8086:a0e8 | 8086:3002 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 14    | intel_l... | [B85A510A03](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKi5/2E2F0EA6AA4A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/B85A510A03>) |
| 8086:a324 | 17aa:3135 | Intel            | Cannon Lake PCH SPI Controller       | 14    | intel_spi  | [A1E7A34896](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CES0BH00/C62828790843/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.4-1-DEFAULT/X86_64/A1E7A34896>) |
| 8086:a0e9 | 8086:3002 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 13    | intel_l... | [868456CA5D](<Mini Pc/Intel Client Systems/NUC11/NUC11TNHi3/2CAA9C44DD55/DEBIAN-11/5.10.0-21-AMD64/X86_64/868456CA5D>) |
| 8086:31c8 | 8086:7270 | Intel            | Serial bus controller                | 12    | pwm_lpss   | [1F1CB63EDC](<Mini Pc/Fanless Mini PC/PCG35/PCG35 GLK/E937013DF7EB/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/1F1CB63EDC>) |
| 8086:4da4 | 8086:3027 | Intel            | Jasper Lake SPI Controller           | 12    | intel_s... | [1B7F3C90CA](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/4F56B3D0D076/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/1B7F3C90CA>) |
| 8086:4dc5 | 8086:3027 | Intel            | Jasper Lake LPSS: I2C Controller #4  | 12    | intel_l... | [1B7F3C90CA](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/4F56B3D0D076/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/1B7F3C90CA>) |
| 8086:4dc6 | 8086:3027 | Intel            | Jasper Lake LPSS: I2C Controller #5  | 12    | intel_l... | [1B7F3C90CA](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/4F56B3D0D076/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/1B7F3C90CA>) |
| 8086:4de8 | 8086:3027 | Intel            | Serial IO I2C Host Controller        | 12    | intel_l... | [1B7F3C90CA](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/4F56B3D0D076/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/1B7F3C90CA>) |
| 8086:4dea | 8086:3027 | Intel            | Jasper Lake LPSS: I2C Controller #2  | 12    | intel_l... | [1B7F3C90CA](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/4F56B3D0D076/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/1B7F3C90CA>) |
| 8086:4de8 |           | Intel            | Serial IO I2C Host Controller        | 11    | intel_l... | [7398AD2411](<Mini Pc/GMKtec/NucBox/NucBox7/7678135C0E37/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/7398AD2411>) |
| 8086:4de9 |           | Intel            | Serial IO I2C Host Controller        | 11    | intel_l... | [7398AD2411](<Mini Pc/GMKtec/NucBox/NucBox7/7678135C0E37/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/7398AD2411>) |
| 8086:4dea |           | Intel            | Jasper Lake LPSS: I2C Controller #2  | 11    | intel_l... | [7398AD2411](<Mini Pc/GMKtec/NucBox/NucBox7/7678135C0E37/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/7398AD2411>) |
| 8086:a324 | 17aa:3136 | Intel            | Cannon Lake PCH SPI Controller       | 11    | intel_spi  | [BDC231EAE9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RUS00300/1B1E837DD190/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/BDC231EAE9>) |
| 8086:4dc5 |           | Intel            | Jasper Lake LPSS: I2C Controller #4  | 10    | intel_l... | [7398AD2411](<Mini Pc/GMKtec/NucBox/NucBox7/7678135C0E37/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/7398AD2411>) |
| 8086:4dc6 |           | Intel            | Jasper Lake LPSS: I2C Controller #5  | 10    | intel_l... | [7398AD2411](<Mini Pc/GMKtec/NucBox/NucBox7/7678135C0E37/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/7398AD2411>) |
| 8086:a0a4 | 8086:2090 | Intel            | Tiger Lake-LP SPI Controller         | 10    | intel_spi  | [F28F7150BA](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/C55F851F02E4/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/F28F7150BA>) |
| 8086:a0e8 | 8086:2090 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 10    | intel_lpss | [F28F7150BA](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/C55F851F02E4/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/F28F7150BA>) |
| 8086:a0e9 | 8086:2090 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 10    | intel_lpss | [F28F7150BA](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/C55F851F02E4/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/F28F7150BA>) |
| 8086:06a4 | 17aa:316e | Intel            | Comet Lake PCH SPI Controller        | 9     | intel_s... | [0C5D92EBF9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DT003GRU/DFE02E0590AD/RED-OS-7.3/5.15.87-1.EL7.3.X86_64/X86_64/0C5D92EBF9>) |
| 10de:1adb | 8086:2090 | Nvidia           | TU106 USB Type-C UCSI Controller     | 8     | i2c_nvi... | [F28F7150BA](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/C55F851F02E4/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/F28F7150BA>) |
| 8086:06a4 | 19da:b440 | Intel            | Comet Lake PCH SPI Controller        | 8     | spi_int... | [6184308BD3](<Mini Pc/ZOTAC/ZBOX-ECM7307/ZBOX-ECM73070C-7307LH-53060C/97C1F8B840C8/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/6184308BD3>) |
| 8086:9da4 | 17aa:314d | Intel            | Cannon Point-LP SPI Controller       | 7     |            | [4673EC60EA](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AD000UGE/E42960BAAF23/POP!_OS-22.04/6.0.12-76060006-GENERIC/X86_64/4673EC60EA>) |
| 8086:a0a4 | 8086:3003 | Intel            | Tiger Lake-LP SPI Controller         | 7     |            | [94D4FE9A93](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKv7/10393889EC9C/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/94D4FE9A93>) |
| 8086:a0e8 | 8086:3003 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 7     | intel_l... | [94D4FE9A93](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKv7/10393889EC9C/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/94D4FE9A93>) |
| 8086:a0e9 | 8086:3003 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 7     | intel_l... | [94D4FE9A93](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKv7/10393889EC9C/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/94D4FE9A93>) |
| 8086:a324 | 8086:2089 | Intel            | Cannon Lake PCH SPI Controller       | 7     |            | [8749B43DB1](<Mini Pc/Intel Client Systems/NUC9/NUC9i9QNX/519180459546/UBUNTU-20.04/5.15.0-46-GENERIC/X86_64/8749B43DB1>) |
| 8086:a368 | 8086:2089 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 7     | intel_l... | [8749B43DB1](<Mini Pc/Intel Client Systems/NUC9/NUC9i9QNX/519180459546/UBUNTU-20.04/5.15.0-46-GENERIC/X86_64/8749B43DB1>) |

### Serial controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:816a | 1043:85b5 | Realtek Semic... | RTL8111xP UART #1                    | 37    | serial     | [9CE749E52E](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/4EDEB05C441C/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.1-1-DEFAULT/X86_64/9CE749E52E>) |
| 10ec:816b | 1043:85b5 | Realtek Semic... | RTL8111xP UART #2                    | 37    | serial     | [9CE749E52E](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/4EDEB05C441C/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.1-1-DEFAULT/X86_64/9CE749E52E>) |
| 8086:9d3d | 8086:2070 | Intel            | Sunrise Point-LP Active Managemen... | 20    | serial     | [861B0673A0](<Mini Pc/Intel/NUC7/NUC7i5DNKE/960B20F7C35D/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/861B0673A0>) |
| 8086:a2bd | 103c:829a | Intel            | 200 Series Chipset Family KT Redi... | 20    | serial     | [8791CD83C7](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/6D08DAE0C65E/DEVUAN-4/5.10.0-21-AMD64/X86_64/8791CD83C7>) |
| 10ec:816a | 10ec:8168 | Realtek Semic... | RTL8111xP UART #1                    | 18    | serial     | [4BE8DDC98E](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/5D3851BCDC5D/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/4BE8DDC98E>) |
| 10ec:816a | 17aa:3130 | Realtek Semic... | RTL8111xP UART #1                    | 16    | serial     | [52B38CEE5C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VG000EUS/FEE9E9034339/KUBUNTU-22.10/5.19.0-26-GENERIC/X86_64/52B38CEE5C>) |
| 10ec:816b | 17aa:3130 | Realtek Semic... | RTL8111xP UART #2                    | 16    | serial     | [52B38CEE5C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VG000EUS/FEE9E9034339/KUBUNTU-22.10/5.19.0-26-GENERIC/X86_64/52B38CEE5C>) |
| 8086:a363 | 17aa:3135 | Intel            | Cannon Lake PCH Active Management... | 12    | serial     | [A1E7A34896](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CES0BH00/C62828790843/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.4-1-DEFAULT/X86_64/A1E7A34896>) |
| 8086:a363 | 17aa:3136 | Intel            | Cannon Lake PCH Active Management... | 11    | serial     | [BDC231EAE9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RUS00300/1B1E837DD190/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/BDC231EAE9>) |
| 8086:a2bd | 103c:829e | Intel            | 200 Series Chipset Family KT Redi... | 8     | serial     | [8111885092](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G3 DM/31906DBA1358/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/8111885092>) |
| 10ec:816a | 17aa:3151 | Realtek Semic... | RTL8111xP UART #1                    | 7     | serial     | [6D4ECB5A00](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A5S1HM00/EDB5CB0BC766/FEDORA-36/6.1.5-100.FC36.X86_64/X86_64/6D4ECB5A00>) |
| 10ec:816b | 17aa:3151 | Realtek Semic... | RTL8111xP UART #2                    | 7     | serial     | [6D4ECB5A00](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A5S1HM00/EDB5CB0BC766/FEDORA-36/6.1.5-100.FC36.X86_64/X86_64/6D4ECB5A00>) |
| 8086:a0e3 | 8086:3003 | Intel            | Tiger Lake-LP Active Management T... | 7     | serial     | [94D4FE9A93](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKv7/10393889EC9C/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/94D4FE9A93>) |
| 8086:06e3 | 103c:8715 | Intel            | Comet Lake Keyboard and Text (KT)... | 5     | serial     | [8D210CCE39](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G6 Desktop Mini PC/74BE63B62162/ENDEAVOUROS-ROLLING/6.2.12-ARCH1-1/X86_64/8D210CCE39>) |
| 8086:06e3 | 103c:871a | Intel            | Comet Lake Keyboard and Text (KT)... | 5     | serial     | [B4B1C552AD](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 400 G6 Desktop Mini PC/44C939723A39/DEBIAN-11/5.15.85-1-PVE/X86_64/B4B1C552AD>) |
| 8086:06e3 | 17aa:3172 | Intel            | Comet Lake Keyboard and Text (KT)... | 5     | serial     | [1DDBBF71EB](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFCTO1WW/AEAA18AE3FAE/FEDORA-36/5.19.16-200.FC36.X86_64/X86_64/1DDBBF71EB>) |
| 8086:a13d | 103c:82c0 | Intel            | 100 Series/C230 Series Chipset Fa... | 5     | serial     | [C35B1DB9A1](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G3 Workstation/C879EA567BC9/UBUNTU-22.04/5.18.12-051812-GENERIC/X86_64/C35B1DB9A1>) |
| 8086:a2bd | 17aa:310b | Intel            | 200 Series Chipset Family KT Redi... | 4     | serial     | [3F57FB1495](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M910q 10MVS02T00/FA0B01CC86C2/DEBIAN-11/5.15.85-1-PVE/X86_64/3F57FB1495>) |
| 8086:a363 | 8086:2088 | Intel            | Cannon Lake PCH Active Management... | 4     | serial     | [C99C3CDAC6](<Mini Pc/Intel Client Systems/NUC9/NUC9VXQNX/41AB2C49D511/FEDORA-35/5.17.4-200.FC35.X86_64/X86_64/C99C3CDAC6>) |
| 10ec:816a | 17aa:30fd | Realtek Semic... | RTL8111xP UART #1                    | 3     | serial     | [F355BAB53F](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10M2S0JL00/0168DA559F7B/FEDORA-37/6.2.8-200.FC37.X86_64/X86_64/F355BAB53F>) |
| 10ec:816b | 17aa:30fd | Realtek Semic... | RTL8111xP UART #2                    | 3     | serial     | [F355BAB53F](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10M2S0JL00/0168DA559F7B/FEDORA-37/6.2.8-200.FC37.X86_64/X86_64/F355BAB53F>) |
| 8086:06e3 | 103c:8710 | Intel            | Comet Lake Keyboard and Text (KT)... | 3     | serial     | [FDD0FEE41E](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G6 Desktop Mini PC/B77C187A6748/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/FDD0FEE41E>) |
| 8086:1e3d | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 3     | serial     | [AD65FE187A](<Mini Pc/CompuLab/Intense-PC/Intense-PC/F82D466DC54E/KDE-NEON-22.04/5.15.0-56-GENERIC/X86_64/AD65FE187A>) |
| 8086:a2bd | 17aa:310c | Intel            | 200 Series Chipset Family KT Redi... | 3     | serial     | [C0F2B10022](<Mini Pc/Lenovo/ThinkStation/ThinkStation P320 Tiny 30C2001XRU/9F9358369869/MANJARO-22.0.1/5.10.164-1-MANJARO/X86_64/C0F2B10022>) |
| 10ec:816a | 103c:8523 | Realtek Semic... | RTL8111xP UART #1                    | 2     | serial     | [D3AFFBBDF4](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/E6875D808502/ROSA-12/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/D3AFFBBDF4>) |
| 10ec:816a | 17aa:3181 | Realtek Semic... | RTL8111xP UART #1                    | 2     | serial     | [56F9A83D77](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75n 11GW000BUS/8D95E87EDCE7/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/56F9A83D77>) |
| 10ec:816b | 103c:8523 | Realtek Semic... | RTL8111xP UART #2                    | 2     | serial     | [D3AFFBBDF4](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/E6875D808502/ROSA-12/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/D3AFFBBDF4>) |
| 8086:8c3d | 103c:2145 | Intel            | 8 Series/C220 Series Chipset Fami... | 2     | serial     | [9C26D1B3DD](<Mini Pc/Hewlett-Packard/t820/t820 Flexible Thin Client/94B86B15DFFF/UBUNTU-20.04/5.8.0-44-GENERIC/X86_64/9C26D1B3DD>) |
| 8086:9cbd | 8086:2058 | Intel            | Wildcat Point-LP KT Controller       | 2     | serial     | [E904EF7A24](<Mini Pc/Intel/NUC5i5MYBE/NUC5i5MYBE H47797-202/7B4D2C094AB2/FEDORA-37/6.0.8-300.FC37.X86_64/X86_64/E904EF7A24>) |
| 8086:9de3 | 17aa:314c | Intel            | Cannon Point-LP Keyboard and Text... | 2     | serial     | [0F66B49A44](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AD000YMX/8552A91D7647/ALPINE-3.13.0_ALPHA20200917/5.4.65-0-LTS/X86_64/0F66B49A44>) |
| 10ec:816a | 103c:83dd | Realtek Semic... | RTL8111xP UART #1                    | 1     | serial     | [9EC6F2E5FE](<Mini Pc/Hewlett-Packard/mt44/mt44 Mobile Thin Client/367A393AEEB1/KDE-NEON-20.04/5.11.0-40-GENERIC/X86_64/9EC6F2E5FE>) |
| 10ec:816a | 103c:8522 | Realtek Semic... | RTL8111xP UART #1                    | 1     | serial     | [28B79EA28B](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/84561BBF7057/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/28B79EA28B>) |
| 10ec:816b | 103c:83dd | Realtek Semic... | RTL8111xP UART #2                    | 1     | serial     | [9EC6F2E5FE](<Mini Pc/Hewlett-Packard/mt44/mt44 Mobile Thin Client/367A393AEEB1/KDE-NEON-20.04/5.11.0-40-GENERIC/X86_64/9EC6F2E5FE>) |
| 10ec:816b | 103c:8522 | Realtek Semic... | RTL8111xP UART #2                    | 1     | serial     | [28B79EA28B](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/84561BBF7057/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/28B79EA28B>) |
| 10ec:816b | 10ec:8168 | Realtek Semic... | RTL8111xP UART #2                    | 1     |            | [5DD127A865](<Mini Pc/Daten Tecnologia/DC2/DC2C-U/DEAB1E021B3F/LINUXMINT-19/4.15.0-20-GENERIC/X86_64/5DD127A865>) |
| 8086:06e3 | 103c:8711 | Intel            | Comet Lake Keyboard and Text (KT)... | 1     | serial     | [6CEAFDDB10](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G6 Desktop Mini PC/2587630952E1/CENTOS-7/3.10.0-1160.66.1.EL7.X86_64/X86_64/6CEAFDDB10>) |
| 8086:51e3 | 8086:3025 | Intel            | Alder Lake AMT SOL Redirection       | 1     | serial     | [F7ECD6FF17](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHv7/8070E0F9F732/MANJARO-22.0.5/6.1.19-1-MANJARO/X86_64/F7ECD6FF17>) |
| 8086:7aeb | 103c:894f | Intel            | 600 Series Chipset Family Managem... | 1     | serial     | [A671F44480](<Mini Pc/Hewlett-Packard/Elite/Elite Mini 800 G9 Desktop PC/236AD7372929/DEBIAN-11/5.15.12/X86_64/A671F44480>) |
| 8086:7aeb | 103c:8952 | Intel            | 600 Series Chipset Family Managem... | 1     | serial     | [E49754F551](<Mini Pc/Hewlett-Packard/Elite/Elite Mini 600 G9 Desktop PC/9FD935DA3E5B/ROCKY-9.1/5.14.0-162.6.1.EL9_1.0.1.X86_64/X86_64/E49754F551>) |
| 8086:7aeb | 17aa:3309 | Intel            | 600 Series Chipset Family Managem... | 1     | serial     | [DC858E1B6D](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M80q Gen 3 11U2S05400/FD82C7A7E5C0/UBUNTU-23.04/5.19.0-30-GENERIC/X86_64/DC858E1B6D>) |
| 8086:9d3d | 1458:1000 | Intel            | Sunrise Point-LP Active Managemen... | 1     | serial     | [DD56498FBF](<Mini Pc/Gigabyte Technology/GB-BSi3/GB-BSi3-6100/D5628C0A20B9/CLEAR-LINUX-OS-31290/5.3.5-847.NATIVE/X86_64/DD56498FBF>) |
| 8086:9de3 | 8086:2096 | Intel            | Cannon Point-LP Keyboard and Text... | 1     | serial     | [2D07BFB282](<Mini Pc/Intel Client Systems/NUC8/NUC8v7PNH/AECCF9C01BD8/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/2D07BFB282>) |
| 8086:a0e3 | 8086:3013 | Intel            | Tiger Lake-LP Active Management T... | 1     | serial     | [66A02F462F](<Mini Pc/Others/CMGB/CMGB/CDA9CB78A5E4/CLEAR-LINUX-OS-33960/5.9.8-1000.NATIVE/X86_64/66A02F462F>) |
| 8086:a13d | 1019:9bc6 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | serial     | [7101BAED7A](<Mini Pc/Daten Tecnologia/DC2/DC2B-U/5CEC86B8AF22/FEDORA-33/5.10.7-200.FC33.X86_64/X86_64/7101BAED7A>) |
| 8086:a13d | 103c:82bf | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | serial     | [305883BE65](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G3 Workstation/A9881D706083/MANJARO/6.1.19-1-MANJARO/X86_64/305883BE65>) |
| 8086:a363 | 8086:7270 | Intel            | Cannon Lake PCH Active Management... | 1     | serial     | [BB0C0E7B99](<Mini Pc/CompuLab/Airtop/Airtop3/1F2E8F787ED7/UBUNTU-22.04/5.15.0-27-GENERIC/X86_64/BB0C0E7B99>) |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9df9 | 8086:2074 | Intel            | Cannon Point-LP Thermal Controller   | 207   | intel_p... | [A92B4A305F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/21A3465BD54D/DEBIAN-11/5.10.0-21-AMD64/X86_64/A92B4A305F>) |
| 8086:02f9 | 8086:2081 | Intel            | Comet Lake Thermal Subsytem          | 123   | intel_p... | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 8086:9d31 | 8086:2068 | Intel            | Sunrise Point-LP Thermal subsystem   | 105   | intel_p... | [05B1BDF24D](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/5A48D52A7EDA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/05B1BDF24D>) |
| 1022:15e4 | 1022:15e4 | AMD              | Sensor Fusion Hub                    | 59    | amd_sfh    | [C1BF3A9C44](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/24AA08459D0E/DEBIAN-11/5.10.0-20-AMD64/X86_64/C1BF3A9C44>) |
| 8086:318c | 8086:318c | Intel            | Celeron/Pentium Silver Processor ... | 54    | process... | [91696FE0F2](<Mini Pc/BESSTAR Tech/GK/GK50/0786D176E577/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/91696FE0F2>) |
| 8086:5abc |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 54    | intel_l... | [AC904A4DF9](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-402/B3229CB33E06/FEDORA-39/6.3.0-0.RC6.20230411GIT0D3EB744AED4.50.FC39.X86_64/X86_64/AC904A4DF9>) |
| 8086:5ac4 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 54    | intel_l... | [AC904A4DF9](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-402/B3229CB33E06/FEDORA-39/6.3.0-0.RC6.20230411GIT0D3EB744AED4.50.FC39.X86_64/X86_64/AC904A4DF9>) |
| 8086:5ac6 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 54    | intel_l... | [AC904A4DF9](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-402/B3229CB33E06/FEDORA-39/6.3.0-0.RC6.20230411GIT0D3EB744AED4.50.FC39.X86_64/X86_64/AC904A4DF9>) |
| 8086:a127 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 54    | intel_l... | [68B65FDA4C](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/0FA94421095F/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/68B65FDA4C>) |
| 8086:a131 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 54    | intel_p... | [68B65FDA4C](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/0FA94421095F/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/68B65FDA4C>) |
| 8086:a160 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 54    | intel_l... | [68B65FDA4C](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/0FA94421095F/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/68B65FDA4C>) |
| 8086:a161 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 54    | intel_l... | [68B65FDA4C](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/0FA94421095F/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/68B65FDA4C>) |
| 8086:a162 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 54    | intel_l... | [68B65FDA4C](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/0FA94421095F/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/68B65FDA4C>) |
| 8086:5aac | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 50    | intel_l... | [AC904A4DF9](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-402/B3229CB33E06/FEDORA-39/6.3.0-0.RC6.20230411GIT0D3EB744AED4.50.FC39.X86_64/X86_64/AC904A4DF9>) |
| 8086:5ac2 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 50    | intel_l... | [AC904A4DF9](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-402/B3229CB33E06/FEDORA-39/6.3.0-0.RC6.20230411GIT0D3EB744AED4.50.FC39.X86_64/X86_64/AC904A4DF9>) |
| 8086:318c | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 46    | process... | [1F1CB63EDC](<Mini Pc/Fanless Mini PC/PCG35/PCG35 GLK/E937013DF7EB/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/1F1CB63EDC>) |
| 8086:31ac | 8086:31ac | Intel            | Celeron/Pentium Silver Processor ... | 45    | intel_l... | [91696FE0F2](<Mini Pc/BESSTAR Tech/GK/GK50/0786D176E577/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/91696FE0F2>) |
| 8086:31b2 | 8086:31b2 | Intel            | Celeron/Pentium Silver Processor ... | 45    | intel_l... | [91696FE0F2](<Mini Pc/BESSTAR Tech/GK/GK50/0786D176E577/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/91696FE0F2>) |
| 8086:5a8c |           | Intel            | Atom/Celeron/Pentium Dynamic Plat... | 45    | process... | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 8086:a131 | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 45    | intel_p... | [19BB30E27A](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-405/6215398CADD3/ARCH-ROLLING/6.2.11-ARCH1-1/X86_64/19BB30E27A>) |
| 8086:5abc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 44    | intel_l... | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 8086:5abe | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 44    | intel_l... | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 8086:5ac0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 44    | intel_l... | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 8086:31ac | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 43    | intel_l... | [1F1CB63EDC](<Mini Pc/Fanless Mini PC/PCG35/PCG35 GLK/E937013DF7EB/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/1F1CB63EDC>) |
| 8086:5aee | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 42    | intel_l... | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 8086:5aac | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 41    | intel_l... | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 8086:5ab0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 41    | intel_l... | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 8086:5aae | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 40    | intel_l... | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 8086:5ab2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 40    | intel_l... | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 8086:5ab4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 40    | intel_l... | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 8086:5ab6 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 40    | intel_l... | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 8086:5ab8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 40    | intel_l... | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 8086:5aba | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 40    | intel_l... | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 8086:31ae | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 33    | intel_l... | [9FEB6E0D59](<Mini Pc/Chuwi/LarkBox/LarkBox Pro/F364AAE2AE09/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/9FEB6E0D59>) |
| 8086:31b0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 33    | intel_l... | [9FEB6E0D59](<Mini Pc/Chuwi/LarkBox/LarkBox Pro/F364AAE2AE09/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/9FEB6E0D59>) |
| 8086:31b2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 33    | intel_l... | [9FEB6E0D59](<Mini Pc/Chuwi/LarkBox/LarkBox Pro/F364AAE2AE09/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/9FEB6E0D59>) |
| 8086:31b4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 33    | intel_l... | [9FEB6E0D59](<Mini Pc/Chuwi/LarkBox/LarkBox Pro/F364AAE2AE09/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/9FEB6E0D59>) |
| 8086:31b6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 33    | intel_l... | [9FEB6E0D59](<Mini Pc/Chuwi/LarkBox/LarkBox Pro/F364AAE2AE09/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/9FEB6E0D59>) |
| 8086:31b8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 33    | intel_l... | [9FEB6E0D59](<Mini Pc/Chuwi/LarkBox/LarkBox Pro/F364AAE2AE09/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/9FEB6E0D59>) |
| 8086:31ba | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 33    | intel_l... | [9FEB6E0D59](<Mini Pc/Chuwi/LarkBox/LarkBox Pro/F364AAE2AE09/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/9FEB6E0D59>) |
| 8086:5ac2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 32    | intel_l... | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 8086:5ac4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 31    | intel_l... | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 8086:5ac6 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 31    | intel_l... | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 8086:9d27 | 8086:2063 | Intel            | Sunrise Point-LP Serial IO UART C... | 29    | intel_l... | [C370821F44](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/C6B76D6C0340/ALMA-9.1/5.14.0-162.23.1.EL9_1.X86_64/X86_64/C370821F44>) |
| 8086:9d31 | 8086:2063 | Intel            | Sunrise Point-LP Thermal subsystem   | 29    | intel_p... | [C370821F44](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/C6B76D6C0340/ALMA-9.1/5.14.0-162.23.1.EL9_1.X86_64/X86_64/C370821F44>) |
| 8086:9d31 | 8086:2070 | Intel            | Sunrise Point-LP Thermal subsystem   | 28    | intel_p... | [861B0673A0](<Mini Pc/Intel/NUC7/NUC7i5DNKE/960B20F7C35D/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/861B0673A0>) |
| 8086:9d60 | 8086:2070 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 28    | intel_l... | [861B0673A0](<Mini Pc/Intel/NUC7/NUC7i5DNKE/960B20F7C35D/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/861B0673A0>) |
| 8086:9d61 | 8086:2070 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 28    | intel_l... | [861B0673A0](<Mini Pc/Intel/NUC7/NUC7i5DNKE/960B20F7C35D/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/861B0673A0>) |
| 8086:467d |           | Intel            | Platform Monitoring Technology       | 24    | intel_vsec | [68B1E1E6CB](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/5A227E0116FB/KUBUNTU-23.04/6.3.1-CUSTOM/X86_64/68B1E1E6CB>) |
| 8086:a379 | 8086:7270 | Intel            | Cannon Lake PCH Thermal Controller   | 24    | intel_p... | [7CCE222CE2](<Mini Pc/Apple/Macmini8/Macmini8,1/C2BFA09A14AD/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/7CCE222CE2>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9da3 | 8086:2074 | Intel            | Cannon Point-LP SMBus Controller     | 207   | i2c_i801   | [A92B4A305F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/21A3465BD54D/DEBIAN-11/5.10.0-21-AMD64/X86_64/A92B4A305F>) |
| 8086:02a3 | 8086:2081 | Intel            | Comet Lake PCH-LP SMBus Host Cont... | 123   | i2c_i801   | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 8086:9d23 | 8086:2068 | Intel            | Sunrise Point-LP SMBus               | 105   | i2c_i801   | [05B1BDF24D](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/5A48D52A7EDA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/05B1BDF24D>) |
| 1022:790b | 1022:790b | AMD              | FCH SMBus Controller                 | 97    | i2c_piix4  | [6097531BFC](<Mini Pc/AZW/SER/SER/0FDA0A46CA08/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/6097531BFC>) |
| 8086:1e22 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family SMBu... | 90    | i2c_i801   | [3DA35D8BC2](<Mini Pc/Apple/Macmini6/Macmini6,1/BE32E3873E80/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/3DA35D8BC2>) |
| 8086:9c22 | 8086:7270 | Intel            | 8 Series SMBus Controller            | 76    | i2c_i801   | [FA074ED7C9](<Mini Pc/Apple/Macmini7/Macmini7,1/9A4B9DC9209B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FA074ED7C9>) |
| 8086:9ca2 | 8086:2057 | Intel            | Wildcat Point-LP SMBus Controller    | 72    | i2c_i801   | [D89F9A2346](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-507/128101606584/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/D89F9A2346>) |
| 8086:1c22 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 63    | i2c_i801   | [0CCFB5109B](<Mini Pc/Apple/Macmini5/Macmini5,1/C751DFCA80AB/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/0CCFB5109B>) |
| 8086:5ad4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 59    | i2c_i801   | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 8086:31d4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 57    | i2c_i801   | [1F1CB63EDC](<Mini Pc/Fanless Mini PC/PCG35/PCG35 GLK/E937013DF7EB/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/1F1CB63EDC>) |
| 8086:a123 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 54    | i2c_i801   | [68B65FDA4C](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/0FA94421095F/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/68B65FDA4C>) |
| 8086:0f12 | 8086:0f12 | Intel            | Atom Processor E3800/CE2700 Serie... | 53    | i2c_i801   | [1F19B2C0DC](<Mini Pc/AMI/Aptio/Aptio CRB/E8C182707BA0/DEBIAN-11/5.10.0-21-AMD64/X86_64/1F19B2C0DC>) |
| 8086:2292 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 51    | i2c_i801   | [410350C836](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/99AD9DE0D682/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/410350C836>) |
| 8086:5ad4 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 50    | i2c_i801   | [AC904A4DF9](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-402/B3229CB33E06/FEDORA-39/6.3.0-0.RC6.20230411GIT0D3EB744AED4.50.FC39.X86_64/X86_64/AC904A4DF9>) |
| 8086:31d4 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 48    | i2c_i801   | [D955CBB060](<Mini Pc/Intel/NUC7/NUC7PJYH/E5C0E8061815/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D955CBB060>) |
| 8086:31d4 | 8086:31d4 | Intel            | Celeron/Pentium Silver Processor ... | 48    | i2c_i801   | [91696FE0F2](<Mini Pc/BESSTAR Tech/GK/GK50/0786D176E577/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/91696FE0F2>) |
| 8086:a123 | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 45    | i801_smbus | [19BB30E27A](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-405/6215398CADD3/ARCH-ROLLING/6.2.11-ARCH1-1/X86_64/19BB30E27A>) |
| 1022:790b | 1043:87e7 | AMD              | FCH SMBus Controller                 | 43    | i2c_piix4  | [C1BF3A9C44](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/24AA08459D0E/DEBIAN-11/5.10.0-20-AMD64/X86_64/C1BF3A9C44>) |
| 8086:a0a3 | 8086:3004 | Intel            | Tiger Lake-LP SMBus Controller       | 41    | i2c_i801   | [7232D92C69](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi5/E0ECB94FBAC3/DEBIAN-11/5.10.0-21-AMD64/X86_64/7232D92C69>) |
| 10de:0aa2 | 10de:cb79 | Nvidia           | MCP79 SMBus                          | 38    | i2c_nfo... | [A206715EC6](<Mini Pc/Apple/Macmini3/Macmini3,1/807755291B05/UBUNTU-23.04/6.1.12-060112-GENERIC/X86_64/A206715EC6>) |
| 8086:9d23 | 8086:2063 | Intel            | Sunrise Point-LP SMBus               | 29    | i2c_i801   | [C370821F44](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/C6B76D6C0340/ALMA-9.1/5.14.0-162.23.1.EL9_1.X86_64/X86_64/C370821F44>) |
| 8086:9d23 | 8086:2070 | Intel            | Sunrise Point-LP SMBus               | 28    | i2c_i801   | [861B0673A0](<Mini Pc/Intel/NUC7/NUC7i5DNKE/960B20F7C35D/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/861B0673A0>) |
| 10de:0d79 | 10de:cb89 | Nvidia           | MCP89 SMBus                          | 26    |            | [6BAD65AD2D](<Mini Pc/Apple/Macmini4/Macmini4,1/43290460D960/ZORIN-16/5.15.0-69-GENERIC/X86_64/6BAD65AD2D>) |
| 8086:a323 | 17aa:312d | Intel            | Cannon Lake PCH SMBus Controller     | 26    | i2c_i801   | [3A87280F55](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8SEYP00/41DB2AC53FB7/ARCH-ROLLING/6.2.9-ARCH1-1/X86_64/3A87280F55>) |
| 8086:a323 | 8086:7270 | Intel            | Cannon Lake PCH SMBus Controller     | 24    | i2c_i801   | [7CCE222CE2](<Mini Pc/Apple/Macmini8/Macmini8,1/C2BFA09A14AD/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/7CCE222CE2>) |
| 8086:a2a3 | 103c:829a | Intel            | 200 Series/Z370 Chipset Family SM... | 23    | i2c_i801   | [EBA2B6CE4E](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/623C6DFA14C1/DEBIAN-12/6.1.0-7-AMD64/X86_64/EBA2B6CE4E>) |
| 1002:4385 | 103c:17e2 | AMD              | SBx00 SMBus Controller               | 22    | i2c_piix4  | [02EE837763](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/3EA0F94B1F39/DEBIAN-11/5.10.0-21-AMD64/X86_64/02EE837763>) |
| 8086:a2a3 | 17aa:3111 | Intel            | 200 Series/Z370 Chipset Family SM... | 22    | i2c_i801   | [C95999B5AD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MR001YMZ/CF634F337F26/DEBIAN-11/5.10.0-22-AMD64/X86_64/C95999B5AD>) |
| 8086:27da | 8086:7270 | Intel            | NM10/ICH7 Family SMBus Controller    | 21    | i2c_i801   | [564A8CF5C2](<Mini Pc/Apple/Macmini2/Macmini2,1/F0A4DC4C2837/UBUNTU-18.04/5.4.0-131-GENERIC/X86_64/564A8CF5C2>) |
| 8086:4da3 |           | Intel            | Jasper Lake SMBus                    | 21    | i2c_i801   | [E812A255A4](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3/09653BE1DD03/MX-21/5.10.0-22-AMD64/X86_64/E812A255A4>) |
| 1022:790b | 1043:880a | AMD              | FCH SMBus Controller                 | 20    | i2c_piix4  | [E92E5DE977](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN51-E1/8C48251D82E0/UBUNTU-20.04/5.15.0-69-GENERIC/X86_64/E92E5DE977>) |
| 8086:4da3 | 1043:8813 | Intel            | Jasper Lake SMBus                    | 20    | i2c_i801   | [99D3ECA719](<Mini Pc/CSL-Computer/Mini/Mini PN41/19DD952D9531/ZORIN-16/5.15.0-71-GENERIC/X86_64/99D3ECA719>) |
| 8086:2292 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 19    | i2c_i801   | [9408F6348B](<Mini Pc/AMI/Aptio/Aptio CRB/19DF7B640AD0/DEBIAN-11/6.2.10-1-LIQUORIX-AMD64/X86_64/9408F6348B>) |
| 8086:51a3 | 8086:3024 | Intel            | Alder Lake PCH-P SMBus Host Contr... | 19    | i2c_i801   | [68B1E1E6CB](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/5A227E0116FB/KUBUNTU-23.04/6.3.1-CUSTOM/X86_64/68B1E1E6CB>) |
| 1022:790b | 103c:8158 | AMD              | FCH SMBus Controller                 | 17    | i2c_piix4  | [A7D7E5C675](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/D14A501869D8/DEBIAN-11/5.10.0-19-AMD64/X86_64/A7D7E5C675>) |
| 1022:790b | 17aa:3130 | AMD              | FCH SMBus Controller                 | 17    | i2c_pii... | [52B38CEE5C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VG000EUS/FEE9E9034339/KUBUNTU-22.10/5.19.0-26-GENERIC/X86_64/52B38CEE5C>) |
| 8086:31d4 | 1043:875e | Intel            | Celeron/Pentium Silver Processor ... | 15    | i2c_i801   | [8C5E382D0A](<Mini Pc/ASUSTek Computer/PN/PN40/65635FC05246/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/8C5E382D0A>) |
| 8086:9d23 | 8086:7270 | Intel            | Sunrise Point-LP SMBus               | 14    | i2c_i801   | [86E1A89B72](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/E1E22FE45F6D/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/86E1A89B72>) |
| 8086:a0a3 | 8086:3002 | Intel            | Tiger Lake-LP SMBus Controller       | 14    | i2c_i801   | [B85A510A03](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKi5/2E2F0EA6AA4A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/B85A510A03>) |
| 8086:a323 | 17aa:3135 | Intel            | Cannon Lake PCH SMBus Controller     | 14    | i2c_i801   | [A1E7A34896](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CES0BH00/C62828790843/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.4-1-DEFAULT/X86_64/A1E7A34896>) |
| 1022:790b | 103c:872e | AMD              | FCH SMBus Controller                 | 13    | i2c_piix4  | [4BE8DDC98E](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/5D3851BCDC5D/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/4BE8DDC98E>) |
| 8086:0f12 | 17aa:368d | Intel            | Atom Processor E3800/CE2700 Serie... | 12    | i2c_i801   | [BA6F405592](<Mini Pc/Lenovo/H30-00/H30-00 90C2003FMT/38341BB3FC42/UBUNTU-22.04/5.15.0-41-GENERIC/X86_64/BA6F405592>) |
| 8086:4da3 | 8086:3027 | Intel            | Jasper Lake SMBus                    | 12    | i2c_i801   | [1B7F3C90CA](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/4F56B3D0D076/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/1B7F3C90CA>) |
| 8086:9ca2 | 8086:2058 | Intel            | Wildcat Point-LP SMBus Controller    | 11    | i2c_i801   | [20A5E76A25](<Mini Pc/Intel/NUC5i5MYBE/NUC5i5MYBE H47797-205/0C6EDF67EE8B/MANJARO-22.0.0/5.15.81-1-MANJARO/X86_64/20A5E76A25>) |
| 8086:9ca2 | 8086:7270 | Intel            | Wildcat Point-LP SMBus Controller    | 11    | i2c_i801   | [3E9E7C877C](<Mini Pc/AWOW/NYI/NYI3/1F0DE9559559/LINUXMINT-21.1/5.15.0-60-GENERIC/X86_64/3E9E7C877C>) |
| 8086:a2a3 | 103c:829e | Intel            | 200 Series/Z370 Chipset Family SM... | 11    | i2c_i801   | [8111885092](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G3 DM/31906DBA1358/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/8111885092>) |
| 8086:a323 | 17aa:3136 | Intel            | Cannon Lake PCH SMBus Controller     | 11    | i2c_i801   | [BDC231EAE9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RUS00300/1B1E837DD190/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/BDC231EAE9>) |
| 8086:0f12 |           | Intel            | Atom Processor E3800/CE2700 Serie... | 10    | i2c_i801   | [AE8045E8DD](<Mini Pc/NOBLEX/NB/NB1601/6611033DEAB1/LINUXMINT-21/5.15.0-41-GENERIC/X86_64/AE8045E8DD>) |
| 8086:31d4 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 10    | i2c_i801   | [71EE0575D4](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/06099CAD1A2D/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/71EE0575D4>) |
| 8086:a0a3 | 8086:2090 | Intel            | Tiger Lake-LP SMBus Controller       | 10    | i2c_i801   | [F28F7150BA](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/C55F851F02E4/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/F28F7150BA>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9dc8 | 8086:2074 | Intel            | Cannon Point-LP High Definition A... | 203   | snd_hda... | [A92B4A305F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/21A3465BD54D/DEBIAN-11/5.10.0-21-AMD64/X86_64/A92B4A305F>) |
| 1002:1637 | 1002:1637 | AMD              | Renoir Radeon High Definition Aud... | 130   | snd_hda... | [6097531BFC](<Mini Pc/AZW/SER/SER/0FDA0A46CA08/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/6097531BFC>) |
| 8086:02c8 | 8086:2081 | Intel            | Comet Lake PCH-LP cAVS               | 122   | snd_hda... | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 8086:9d71 | 8086:2068 | Intel            | Sunrise Point-LP HD Audio            | 102   | snd_hda... | [05B1BDF24D](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/5A48D52A7EDA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/05B1BDF24D>) |
| 8086:1e20 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family High... | 90    | snd_hda... | [3DA35D8BC2](<Mini Pc/Apple/Macmini6/Macmini6,1/BE32E3873E80/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/3DA35D8BC2>) |
| 8086:9c20 | 8086:7270 | Intel            | 8 Series HD Audio Controller         | 76    | snd_hda... | [FA074ED7C9](<Mini Pc/Apple/Macmini7/Macmini7,1/9A4B9DC9209B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FA074ED7C9>) |
| 8086:0a0c | 106b:0141 | Intel            | Haswell-ULT HD Audio Controller      | 75    | snd_hda... | [FA074ED7C9](<Mini Pc/Apple/Macmini7/Macmini7,1/9A4B9DC9209B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FA074ED7C9>) |
| 8086:9ca0 | 8086:2057 | Intel            | Wildcat Point-LP High Definition ... | 72    | snd_hda... | [D89F9A2346](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-507/128101606584/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/D89F9A2346>) |
| 8086:160c | 8086:2057 | Intel            | Broadwell-U Audio Controller         | 71    | snd_hda... | [D89F9A2346](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-507/128101606584/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/D89F9A2346>) |
| 8086:1c20 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 63    | snd_hda... | [0CCFB5109B](<Mini Pc/Apple/Macmini5/Macmini5,1/C751DFCA80AB/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/0CCFB5109B>) |
| 8086:a171 | 8086:2073 | Intel            | CM238 HD Audio Controller            | 53    | snd_hda... | [68B65FDA4C](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/0FA94421095F/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/68B65FDA4C>) |
| 1002:ab08 | 8086:2073 | AMD              | Polaris 22 HDMI Audio                | 49    | snd_hda... | [68B65FDA4C](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/0FA94421095F/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/68B65FDA4C>) |
| 1022:15e3 | 10ec:0000 | AMD              | Family 17h/19h HD Audio Controller   | 49    | snd_hda... | [6097531BFC](<Mini Pc/AZW/SER/SER/0FDA0A46CA08/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/6097531BFC>) |
| 8086:2284 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 49    | snd_hda... | [410350C836](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/99AD9DE0D682/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/410350C836>) |
| 8086:3198 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 48    | snd_hda... | [D955CBB060](<Mini Pc/Intel/NUC7/NUC7PJYH/E5C0E8061815/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D955CBB060>) |
| 8086:5a98 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 46    | snd_hda... | [AC904A4DF9](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-402/B3229CB33E06/FEDORA-39/6.3.0-0.RC6.20230411GIT0D3EB744AED4.50.FC39.X86_64/X86_64/AC904A4DF9>) |
| 1002:15de | 1002:15de | AMD              | Raven/Raven2/Fenghuang HDMI/DP Au... | 45    | snd_hda... | [28B79EA28B](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/84561BBF7057/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/28B79EA28B>) |
| 8086:3198 | 10ec:119e | Intel            | Celeron/Pentium Silver Processor ... | 45    | snd_hda... | [91696FE0F2](<Mini Pc/BESSTAR Tech/GK/GK50/0786D176E577/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/91696FE0F2>) |
| 8086:a170 | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 45    | snd_hda... | [19BB30E27A](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-405/6215398CADD3/ARCH-ROLLING/6.2.11-ARCH1-1/X86_64/19BB30E27A>) |
| 10de:0ac0 | 10de:cb79 | Nvidia           | MCP79 High Definition Audio          | 38    | snd_hda... | [A206715EC6](<Mini Pc/Apple/Macmini3/Macmini3,1/807755291B05/UBUNTU-23.04/6.1.12-060112-GENERIC/X86_64/A206715EC6>) |
| 8086:a0c8 | 8086:3004 | Intel            | Tiger Lake-LP Smart Sound Technol... | 38    | snd_hda... | [7232D92C69](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi5/E0ECB94FBAC3/DEBIAN-11/5.10.0-21-AMD64/X86_64/7232D92C69>) |
| 1022:15e3 | 1043:87bc | AMD              | Family 17h/19h HD Audio Controller   | 37    | snd_hda... | [C1BF3A9C44](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/24AA08459D0E/DEBIAN-11/5.10.0-20-AMD64/X86_64/C1BF3A9C44>) |
| 8086:0f04 | 8086:0f04 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 36    | snd_hda... | [1F19B2C0DC](<Mini Pc/AMI/Aptio/Aptio CRB/E8C182707BA0/DEBIAN-11/5.10.0-21-AMD64/X86_64/1F19B2C0DC>) |
| 8086:9d71 | 8086:2070 | Intel            | Sunrise Point-LP HD Audio            | 28    | snd_hda... | [861B0673A0](<Mini Pc/Intel/NUC7/NUC7i5DNKE/960B20F7C35D/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/861B0673A0>) |
| 8086:9d70 | 8086:2063 | Intel            | Sunrise Point-LP HD Audio            | 27    | snd_hda... | [C370821F44](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/C6B76D6C0340/ALMA-9.1/5.14.0-162.23.1.EL9_1.X86_64/X86_64/C370821F44>) |
| 10de:0d94 | 10de:cb89 | Nvidia           | MCP89 High Definition Audio          | 26    | snd_hda... | [6BAD65AD2D](<Mini Pc/Apple/Macmini4/Macmini4,1/43290460D960/ZORIN-16/5.15.0-69-GENERIC/X86_64/6BAD65AD2D>) |
| 8086:a348 | 17aa:312d | Intel            | Cannon Lake PCH cAVS                 | 26    | snd_hda... | [3A87280F55](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8SEYP00/41DB2AC53FB7/ARCH-ROLLING/6.2.9-ARCH1-1/X86_64/3A87280F55>) |
| 8086:a348 | 8086:7270 | Intel            | Cannon Lake PCH cAVS                 | 24    | snd_hda... | [7CCE222CE2](<Mini Pc/Apple/Macmini8/Macmini8,1/C2BFA09A14AD/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/7CCE222CE2>) |
| 106b:1803 | 106b:1884 | Apple            | Audio Device                         | 23    | aaudio     | [7CCE222CE2](<Mini Pc/Apple/Macmini8/Macmini8,1/C2BFA09A14AD/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/7CCE222CE2>) |
| 8086:a2f0 | 103c:829a | Intel            | 200 Series PCH HD Audio              | 23    | snd_hda... | [EBA2B6CE4E](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/623C6DFA14C1/DEBIAN-12/6.1.0-7-AMD64/X86_64/EBA2B6CE4E>) |
| 1002:4383 | 103c:17e2 | AMD              | SBx00 Azalia (Intel HDA)             | 22    | snd_hda... | [02EE837763](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/3EA0F94B1F39/DEBIAN-11/5.10.0-21-AMD64/X86_64/02EE837763>) |
| 1002:aa90 | 0000:aa90 | AMD              | Turks HDMI Audio [Radeon HD 6500/... | 22    | snd_hda... | [401F407DAE](<Mini Pc/Apple/Macmini5/Macmini5,2/BF21898B2E13/ZORIN-16/5.15.0-69-GENERIC/X86_64/401F407DAE>) |
| 8086:a2f0 | 17aa:3111 | Intel            | 200 Series PCH HD Audio              | 22    | snd_hda... | [C95999B5AD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MR001YMZ/CF634F337F26/DEBIAN-11/5.10.0-22-AMD64/X86_64/C95999B5AD>) |
| 1002:1314 | 103c:17e2 | AMD              | Wrestler HDMI Audio                  | 21    | snd_hda... | [02EE837763](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/3EA0F94B1F39/DEBIAN-11/5.10.0-21-AMD64/X86_64/02EE837763>) |
| 8086:0f04 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 20    | snd_hda... | [9BA3333988](<Mini Pc/AMI/Aptio/Aptio CRB/24010023E208/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/9BA3333988>) |
| 8086:2284 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 19    | snd_hda... | [9408F6348B](<Mini Pc/AMI/Aptio/Aptio CRB/19DF7B640AD0/DEBIAN-11/6.2.10-1-LIQUORIX-AMD64/X86_64/9408F6348B>) |
| 8086:3198 | 10ec:111c | Intel            | Celeron/Pentium Silver Processor ... | 19    | snd_hda... | [1F1CB63EDC](<Mini Pc/Fanless Mini PC/PCG35/PCG35 GLK/E937013DF7EB/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/1F1CB63EDC>) |
| 8086:5a98 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 19    | snd_hda... | [6EA31CC2ED](<Mini Pc/AMI/Aptio/Aptio CRB/5AEFCC18D04F/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/6EA31CC2ED>) |
| 8086:27d8 | 8384:7680 | Intel            | NM10/ICH7 Family High Definition ... | 18    | snd_hda... | [564A8CF5C2](<Mini Pc/Apple/Macmini2/Macmini2,1/F0A4DC4C2837/UBUNTU-18.04/5.4.0-131-GENERIC/X86_64/564A8CF5C2>) |
| 1022:15e3 | 1043:8820 | AMD              | Family 17h/19h HD Audio Controller   | 17    | snd_hda... | [E92E5DE977](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN51-E1/8C48251D82E0/UBUNTU-20.04/5.15.0-69-GENERIC/X86_64/E92E5DE977>) |
| 8086:3198 | 02f3:0301 | Intel            | Celeron/Pentium Silver Processor ... | 17    | snd_hda... | [9FEB6E0D59](<Mini Pc/Chuwi/LarkBox/LarkBox Pro/F364AAE2AE09/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/9FEB6E0D59>) |
| 8086:5a98 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 17    | snd_hda... | [183E716FF5](<Mini Pc/Prestigio/PSB133/PSB133S01ZFP/5B023D8A425A/ROSA-12.3/5.15.79-GENERIC-1ROSA2021.1-X86_64/X86_64/183E716FF5>) |
| 1002:9840 | 103c:8158 | AMD              | Kabini HDMI/DP Audio                 | 16    | snd_hda... | [8D1C60FE86](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/F58D7253760E/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/8D1C60FE86>) |
| 1022:157a | 103c:8158 | AMD              | Family 15h (Models 60h-6fh) Audio... | 16    | snd_hda... | [8D1C60FE86](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/F58D7253760E/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/8D1C60FE86>) |
| 1022:15e3 | 17aa:3130 | AMD              | Family 17h/19h HD Audio Controller   | 16    | snd_hda... | [52B38CEE5C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VG000EUS/FEE9E9034339/KUBUNTU-22.10/5.19.0-26-GENERIC/X86_64/52B38CEE5C>) |
| 8086:51c8 | 8086:3024 | Intel            | Alder Lake PCH-P High Definition ... | 16    | snd_hda... | [68B1E1E6CB](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/5A227E0116FB/KUBUNTU-23.04/6.3.1-CUSTOM/X86_64/68B1E1E6CB>) |
| 1022:15e3 | 1022:d270 | AMD              | Family 17h/19h HD Audio Controller   | 15    | snd_hda... | [ECF58906E7](<Mini Pc/AZW/SER/SER/89DAE8FF2DDA/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/ECF58906E7>) |
| 8086:3198 | 1043:871d | Intel            | Celeron/Pentium Silver Processor ... | 15    | snd_hda... | [8C5E382D0A](<Mini Pc/ASUSTek Computer/PN/PN40/65635FC05246/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/8C5E382D0A>) |
| 8086:a348 | 17aa:3135 | Intel            | Cannon Lake PCH cAVS                 | 14    | snd_hda... | [A1E7A34896](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CES0BH00/C62828790843/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.4-1-DEFAULT/X86_64/A1E7A34896>) |
| 1002:1637 | 103c:872e | AMD              | Renoir Radeon High Definition Aud... | 13    | snd_hda... | [4BE8DDC98E](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/5D3851BCDC5D/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/4BE8DDC98E>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9dd3 | 8086:2074 | Intel            | Cannon Point-LP SATA Controller [... | 200   | ahci       | [A92B4A305F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/21A3465BD54D/DEBIAN-11/5.10.0-21-AMD64/X86_64/A92B4A305F>) |
| 8086:02d3 | 8086:2081 | Intel            | Comet Lake SATA AHCI Controller      | 117   | ahci       | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 8086:9d03 | 8086:2068 | Intel            | Sunrise Point-LP SATA Controller ... | 103   | ahci       | [05B1BDF24D](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/5A48D52A7EDA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/05B1BDF24D>) |
| 8086:1e03 | 8086:7270 | Intel            | 7 Series Chipset Family 6-port SA... | 90    | ahci       | [3DA35D8BC2](<Mini Pc/Apple/Macmini6/Macmini6,1/BE32E3873E80/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/3DA35D8BC2>) |
| 1022:7901 | 1022:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 82    | ahci       | [6097531BFC](<Mini Pc/AZW/SER/SER/0FDA0A46CA08/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/6097531BFC>) |
| 8086:9c03 | 8086:7270 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 69    | ahci       | [FA074ED7C9](<Mini Pc/Apple/Macmini7/Macmini7,1/9A4B9DC9209B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FA074ED7C9>) |
| 8086:9c83 | 8086:2057 | Intel            | Wildcat Point-LP SATA Controller ... | 66    | ahci       | [D89F9A2346](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-507/128101606584/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/D89F9A2346>) |
| 8086:5ae3 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 60    | ahci       | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 8086:1c03 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 57    | ahci       | [0CCFB5109B](<Mini Pc/Apple/Macmini5/Macmini5,1/C751DFCA80AB/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/0CCFB5109B>) |
| 8086:31e3 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 57    | ahci       | [1F1CB63EDC](<Mini Pc/Fanless Mini PC/PCG35/PCG35 GLK/E937013DF7EB/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/1F1CB63EDC>) |
| 8086:22a3 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 50    | ahci       | [410350C836](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/99AD9DE0D682/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/410350C836>) |
| 8086:5ae3 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 50    | ahci       | [AC904A4DF9](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-402/B3229CB33E06/FEDORA-39/6.3.0-0.RC6.20230411GIT0D3EB744AED4.50.FC39.X86_64/X86_64/AC904A4DF9>) |
| 8086:31e3 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 48    | ahci       | [D955CBB060](<Mini Pc/Intel/NUC7/NUC7PJYH/E5C0E8061815/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D955CBB060>) |
| 8086:31e3 | 8086:31e3 | Intel            | Celeron/Pentium Silver Processor ... | 48    | ahci       | [91696FE0F2](<Mini Pc/BESSTAR Tech/GK/GK50/0786D176E577/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/91696FE0F2>) |
| 8086:0f23 | 8086:0f23 | Intel            | Atom Processor E3800 Series SATA ... | 47    | ahci       | [1F19B2C0DC](<Mini Pc/AMI/Aptio/Aptio CRB/E8C182707BA0/DEBIAN-11/5.10.0-21-AMD64/X86_64/1F19B2C0DC>) |
| 1022:7901 | 1043:87e7 | AMD              | FCH SATA Controller [AHCI mode]      | 43    | ahci       | [C1BF3A9C44](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/24AA08459D0E/DEBIAN-11/5.10.0-20-AMD64/X86_64/C1BF3A9C44>) |
| 8086:a0d3 | 8086:3004 | Intel            | Tiger Lake-LP SATA Controller        | 39    | ahci       | [7232D92C69](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi5/E0ECB94FBAC3/DEBIAN-11/5.10.0-21-AMD64/X86_64/7232D92C69>) |
| 10de:0ab9 | 10de:cb79 | Nvidia           | MCP79 AHCI Controller                | 32    | ahci       | [A206715EC6](<Mini Pc/Apple/Macmini3/Macmini3,1/807755291B05/UBUNTU-23.04/6.1.12-060112-GENERIC/X86_64/A206715EC6>) |
| 8086:9d03 | 8086:2063 | Intel            | Sunrise Point-LP SATA Controller ... | 29    | ahci       | [C370821F44](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/C6B76D6C0340/ALMA-9.1/5.14.0-162.23.1.EL9_1.X86_64/X86_64/C370821F44>) |
| 8086:9d03 | 8086:2070 | Intel            | Sunrise Point-LP SATA Controller ... | 27    | ahci       | [861B0673A0](<Mini Pc/Intel/NUC7/NUC7i5DNKE/960B20F7C35D/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/861B0673A0>) |
| 10de:0d88 | 106b:cb89 | Nvidia           | MCP89 SATA Controller (AHCI mode)    | 26    | ahci       | [6BAD65AD2D](<Mini Pc/Apple/Macmini4/Macmini4,1/43290460D960/ZORIN-16/5.15.0-69-GENERIC/X86_64/6BAD65AD2D>) |
| 8086:a352 | 17aa:312d | Intel            | Cannon Lake PCH SATA AHCI Controller | 26    | ahci       | [3A87280F55](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8SEYP00/41DB2AC53FB7/ARCH-ROLLING/6.2.9-ARCH1-1/X86_64/3A87280F55>) |
| 8086:4dd3 |           | Intel            | Jasper Lake SATA AHCI Controller     | 21    | ahci       | [E812A255A4](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3/09653BE1DD03/MX-21/5.10.0-22-AMD64/X86_64/E812A255A4>) |
| 8086:a282 | 103c:829a | Intel            | 200 Series PCH SATA controller [A... | 21    | ahci       | [EBA2B6CE4E](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/623C6DFA14C1/DEBIAN-12/6.1.0-7-AMD64/X86_64/EBA2B6CE4E>) |
| 8086:a282 | 17aa:3111 | Intel            | 200 Series PCH SATA controller [A... | 21    | ahci       | [C95999B5AD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MR001YMZ/CF634F337F26/DEBIAN-11/5.10.0-22-AMD64/X86_64/C95999B5AD>) |
| 1022:7901 | 1043:880a | AMD              | FCH SATA Controller [AHCI mode]      | 20    | ahci       | [E92E5DE977](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN51-E1/8C48251D82E0/UBUNTU-20.04/5.15.0-69-GENERIC/X86_64/E92E5DE977>) |
| 8086:22a3 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 19    | ahci       | [9408F6348B](<Mini Pc/AMI/Aptio/Aptio CRB/19DF7B640AD0/DEBIAN-11/6.2.10-1-LIQUORIX-AMD64/X86_64/9408F6348B>) |
| 8086:4dd3 | 1043:8813 | Intel            | Jasper Lake SATA AHCI Controller     | 19    | ahci       | [99D3ECA719](<Mini Pc/CSL-Computer/Mini/Mini PN41/19DD952D9531/ZORIN-16/5.15.0-71-GENERIC/X86_64/99D3ECA719>) |
| 8086:51d3 | 8086:3024 | Intel            | Alder Lake-P SATA AHCI Controller    | 19    | ahci       | [68B1E1E6CB](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/5A227E0116FB/KUBUNTU-23.04/6.3.1-CUSTOM/X86_64/68B1E1E6CB>) |
| 1022:7901 | 103c:8158 | AMD              | FCH SATA Controller [AHCI mode]      | 17    | ahci       | [A7D7E5C675](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/D14A501869D8/DEBIAN-11/5.10.0-19-AMD64/X86_64/A7D7E5C675>) |
| 1022:7901 | 17aa:3130 | AMD              | FCH SATA Controller [AHCI mode]      | 16    | ahci       | [52B38CEE5C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VG000EUS/FEE9E9034339/KUBUNTU-22.10/5.19.0-26-GENERIC/X86_64/52B38CEE5C>) |
| 8086:a103 | 8086:2064 | Intel            | HM170/QM170 Chipset SATA Controll... | 16    | ahci       | [D7E9027E6A](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-408/FFD543369635/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/D7E9027E6A>) |
| 1002:4390 | 103c:17e2 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 15    | ahci       | [41FDB27963](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/AD923ADA8EB1/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/41FDB27963>) |
| 8086:31e3 | 1043:875e | Intel            | Celeron/Pentium Silver Processor ... | 15    | ahci       | [8C5E382D0A](<Mini Pc/ASUSTek Computer/PN/PN40/65635FC05246/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/8C5E382D0A>) |
| 8086:9d03 | 8086:7270 | Intel            | Sunrise Point-LP SATA Controller ... | 14    | ahci       | [86E1A89B72](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/E1E22FE45F6D/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/86E1A89B72>) |
| 8086:a352 | 17aa:3135 | Intel            | Cannon Lake PCH SATA AHCI Controller | 14    | ahci       | [A1E7A34896](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CES0BH00/C62828790843/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.4-1-DEFAULT/X86_64/A1E7A34896>) |
| 1022:43eb | 103c:872e | AMD              | 500 Series Chipset SATA Controller   | 13    | ahci       | [4BE8DDC98E](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/5D3851BCDC5D/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/4BE8DDC98E>) |
| 8086:a0d3 | 8086:3002 | Intel            | Tiger Lake-LP SATA Controller        | 13    | ahci       | [B85A510A03](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKi5/2E2F0EA6AA4A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/B85A510A03>) |
| 8086:0f23 | 17aa:368d | Intel            | Atom Processor E3800 Series SATA ... | 12    | ahci       | [BA6F405592](<Mini Pc/Lenovo/H30-00/H30-00 90C2003FMT/38341BB3FC42/UBUNTU-22.04/5.15.0-41-GENERIC/X86_64/BA6F405592>) |
| 8086:a103 | 8086:2073 | Intel            | HM170/QM170 Chipset SATA Controll... | 12    | ahci       | [4639213F3E](<Mini Pc/Intel/NUC8/NUC8i7HNK/2483CDED328C/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/4639213F3E>) |
| 8086:4dd3 | 8086:3027 | Intel            | Jasper Lake SATA AHCI Controller     | 11    | ahci       | [1B7F3C90CA](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/4F56B3D0D076/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/1B7F3C90CA>) |
| 8086:9c83 | 8086:2058 | Intel            | Wildcat Point-LP SATA Controller ... | 11    | ahci       | [20A5E76A25](<Mini Pc/Intel/NUC5i5MYBE/NUC5i5MYBE H47797-205/0C6EDF67EE8B/MANJARO-22.0.0/5.15.81-1-MANJARO/X86_64/20A5E76A25>) |
| 8086:0f23 |           | Intel            | Atom Processor E3800 Series SATA ... | 10    | ahci       | [AE8045E8DD](<Mini Pc/NOBLEX/NB/NB1601/6611033DEAB1/LINUXMINT-21/5.15.0-41-GENERIC/X86_64/AE8045E8DD>) |
| 8086:31e3 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 10    | ahci       | [71EE0575D4](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/06099CAD1A2D/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/71EE0575D4>) |
| 8086:9c83 | 8086:7270 | Intel            | Wildcat Point-LP SATA Controller ... | 10    | ahci       | [3E9E7C877C](<Mini Pc/AWOW/NYI/NYI3/1F0DE9559559/LINUXMINT-21.1/5.15.0-60-GENERIC/X86_64/3E9E7C877C>) |
| 8086:a282 | 103c:829e | Intel            | 200 Series PCH SATA controller [A... | 10    | ahci       | [8111885092](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G3 DM/31906DBA1358/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/8111885092>) |
| 8086:a352 | 17aa:3136 | Intel            | Cannon Lake PCH SATA AHCI Controller | 10    | ahci       | [BDC231EAE9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RUS00300/1B1E837DD190/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/BDC231EAE9>) |
| 144d:a801 | 144d:a801 | Samsung Elect... | Electronics SATA controller          | 9     | ahci       | [C89AEAF207](<Mini Pc/Apple/Macmini7/Macmini7,1/D3A31E4E14CF/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/C89AEAF207>) |
| 8086:06d2 | 17aa:316e | Intel            | Comet Lake SATA AHCI Controller      | 9     | ahci       | [0C5D92EBF9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DT003GRU/DFE02E0590AD/RED-OS-7.3/5.15.87-1.EL7.3.X86_64/X86_64/0C5D92EBF9>) |
| 8086:0f23 | 8086:7270 | Intel            | Atom Processor E3800 Series SATA ... | 9     | ahci       | [0CA0B99AA3](<Mini Pc/AMI/Aptio/Aptio CRB/24010023E208/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/0CA0B99AA3>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:27df | 8086:7270 | Intel            | 82801G (ICH7 Family) IDE Controller  | 20    | pata_acpi  | [564A8CF5C2](<Mini Pc/Apple/Macmini2/Macmini2,1/F0A4DC4C2837/UBUNTU-18.04/5.4.0-131-GENERIC/X86_64/564A8CF5C2>) |
| 8086:27c4 | 8086:7270 | Intel            | 82801GBM/GHM (ICH7-M Family) SATA... | 13    | pata_acpi  | [62D808A3E5](<Mini Pc/Apple/Macmini1/Macmini1,1/1810C1967C95/ZORIN-15/5.4.0-126-GENERIC/I686/62D808A3E5>) |
| 1106:9001 | 1106:9001 | VIA Technologies | VX900 Series Serial-ATA Controller   | 9     | pata_vi... | [241022B1D0](<Mini Pc/Hewlett-Packard/t510/t510 Thin Client/68BE52C35943/UBUNTU-18.04/4.15.0-176-GENERIC/X86_64/241022B1D0>) |
| 10de:0ab5 | 10de:cb79 | Nvidia           | MCP79 SATA Controller                | 7     | ahci, p... | [CDC1678CAE](<Mini Pc/Apple/Macmini3/Macmini3,1/5B41FC221BF8/UBUNTU-20.04/5.15.0-46-GENERIC/X86_64/CDC1678CAE>) |
| 8086:1c01 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | pata_acpi  | [3D01B5328F](<Mini Pc/Apple/Macmini5/Macmini5,2/6291C9908DA3/LINUXMINT-20/5.4.0-144-GENERIC/X86_64/3D01B5328F>) |
| 1022:780c | 103c:8103 | AMD              | FCH IDE Controller                   | 4     | ata_gen... | [19C575A4D8](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/E94D038C9E51/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/19C575A4D8>) |
| 1002:439c | 19da:a191 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 3     | pata_at... | [C0CE2CCABE](<Mini Pc/ZOTAC/ZBOXNANO-AD/ZBOXNANO-AD10/E4426F81F461/UBUNTU-20.04/5.11.0-44-GENERIC/X86_64/C0CE2CCABE>) |
| 1002:439c | 19da:a233 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 3     | pata_at... | [BE96F10577](<Mini Pc/ZOTAC/ZBOX-AD/ZBOX-AD04/0EEEABB8A5DF/UBUNTU-20.04/5.11.0-44-GENERIC/X86_64/BE96F10577>) |
| 1022:780c | 19da:a261 | AMD              | FCH IDE Controller                   | 3     | pata_at... | [3A6297D90B](<Mini Pc/ZOTAC/ZBOXNANO-AD/ZBOXNANO-AD12/1942AB43E912/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/3A6297D90B>) |
| 8086:27c0 | 8086:544b | Intel            | NM10/ICH7 Family SATA Controller ... | 3     | ata_pii... | [9DC27FC5BE](<Mini Pc/Intel/D425KT/D425KT AAE93083-401/10EE8CFFD4E7/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/9DC27FC5BE>) |
| 1002:439c | 19da:a183 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 2     | pata_at... | [B4447459DF](<Mini Pc/ZOTAC/ZBOX-AD/ZBOX-AD02/BB1B94107982/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/B4447459DF>) |
| 1022:780c | 19da:b218 | AMD              | FCH IDE Controller                   | 2     | pata_at... | [619BD547D1](<Mini Pc/ZOTAC/ZBOXNANO-AQ/ZBOXNANO-AQ02/B80DC01E2387/LINUXMINT-20.3/5.4.0-121-GENERIC/X86_64/619BD547D1>) |
| 8086:1e3c | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 2     | pata_acpi  | [AD65FE187A](<Mini Pc/CompuLab/Intense-PC/Intense-PC/F82D466DC54E/KDE-NEON-22.04/5.15.0-56-GENERIC/X86_64/AD65FE187A>) |
| 8086:27c0 | 19da:a140 | Intel            | NM10/ICH7 Family SATA Controller ... | 2     | pata_acpi  | [620812FE84](<Mini Pc/ZOTAC/ZBOX-ID/ZBOX-ID41/E272C7549D5E/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/620812FE84>) |
| 8086:0f21 | 17aa:368d | Intel            | Atom Processor E3800 Series SATA ... | 1     | ata_pii... | [E3D598C5CB](<Mini Pc/Lenovo/H50-00/H50-00 90C1000PRS/BB394062E9F8/ROSA-2014.1/4.1.38-NRJ-DESKTOP-1ROSA-X86_64/X86_64/E3D598C5CB>) |
| 8086:0f21 | 8086:0f21 | Intel            | Atom Processor E3800 Series SATA ... | 1     | ata_pii... | [BF7C2C6D9B](<Mini Pc/NEXCOM/VTC/VTC1010/6EF054560413/DEBIAN-11/5.10.0-11-AMD64/X86_64/BF7C2C6D9B>) |
| 8086:24cb | 8086:1977 | Intel            | 82801DB (ICH4) IDE Controller        | 1     | ata_piix   | [4A3E3CD4EE](<Mini Pc/Radiant Systems/P/P845/6CDD298F6645/ANTIX-17.4.1/4.9.160-ANTIX.2-486-SMP/I686/4A3E3CD4EE>) |
| 8086:27c0 | 19da:a218 | Intel            | NM10/ICH7 Family SATA Controller ... | 1     | ata_pii... | [E907BA80AE](<Mini Pc/ZOTAC/ZBOX-ID/ZBOX-ID80/E1C6E46AEEE7/ROSA-2014.1/4.1.38-NRJ-DESKTOP-2ROSA-X86_64/X86_64/E907BA80AE>) |
| 8086:27c0 | 19da:b209 | Intel            | NM10/ICH7 Family SATA Controller ... | 1     | pata_acpi  | [6162BE584A](<Mini Pc/ZOTAC/ZBOX-ID/ZBOX-ID84/2624D8EDD4B1/UBUNTU-21.10/5.13.0-22-GENERIC/X86_64/6162BE584A>) |
| 8086:27c0 | 8086:7270 | Intel            | NM10/ICH7 Family SATA Controller ... | 1     | pata_acpi  | [6B9414B09F](<Mini Pc/Intel/CedarTrail/CedarTrail Platform/009433D25421/UBUNTU-20.04/5.4.0-47-GENERIC/X86_64/6B9414B09F>) |
| 8086:27c4 | 8086:27c4 | Intel            | 82801GBM/GHM (ICH7-M Family) SATA... | 1     | pata_acpi  | [10DB69DD6C](<Mini Pc/Kontron/SMX/SMX945/327FC59121CA/UBUNTU-18.04/4.15.0-88-GENERIC/I686/10DB69DD6C>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 243   | nvme       | [6184308BD3](<Mini Pc/ZOTAC/ZBOX-ECM7307/ZBOX-ECM73070C-7307LH-53060C/97C1F8B840C8/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/6184308BD3>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 66    | nvme       | [C0F2B10022](<Mini Pc/Lenovo/ThinkStation/ThinkStation P320 Tiny 30C2001XRU/9F9358369869/MANJARO-22.0.1/5.10.164-1-MANJARO/X86_64/C0F2B10022>) |
| 144d:a80a | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 47    | nvme       | [68B1E1E6CB](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/5A227E0116FB/KUBUNTU-23.04/6.3.1-CUSTOM/X86_64/68B1E1E6CB>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT SSD Controller     | 39    | nvme       | [C3D1C96452](<Mini Pc/ZOTAC/ZBOX-ECM7307/ZBOX-ECM73070C-7307LH-53060C/C5CA6B4DF0FA/UBUNTU-BUDGIE-22.10/5.19.0-21-GENERIC/X86_64/C3D1C96452>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980              | 38    | nvme       | [868456CA5D](<Mini Pc/Intel Client Systems/NUC11/NUC11TNHi3/2CAA9C44DD55/DEBIAN-11/5.10.0-21-AMD64/X86_64/868456CA5D>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 31    | nvme       | [C1BF3A9C44](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/24AA08459D0E/DEBIAN-11/5.10.0-20-AMD64/X86_64/C1BF3A9C44>) |
| 2646:500f | 2646:500f | Kingston Tech... | NVMe Controller                      | 30    | nvme       | [99D3ECA719](<Mini Pc/CSL-Computer/Mini/Mini PN41/19DD952D9531/ZORIN-16/5.15.0-71-GENERIC/X86_64/99D3ECA719>) |
| 8086:f1a8 | 8086:390d | Intel            | SSD 660P Series                      | 26    | nvme       | [CCAF63588A](<Mini Pc/AZW/GTR/GTR/150CD34EF594/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/CCAF63588A>) |
| 15b7:5006 | 15b7:5006 | SanDisk          | WD Black SN750 / PC SN730 NVMe SSD   | 24    | nvme       | [0C5D92EBF9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DT003GRU/DFE02E0590AD/RED-OS-7.3/5.15.87-1.EL7.3.X86_64/X86_64/0C5D92EBF9>) |
| 106b:2005 | 106b:1800 | Apple            | ANS2 NVMe Controller                 | 23    | nvme       | [7CCE222CE2](<Mini Pc/Apple/Macmini8/Macmini8,1/C2BFA09A14AD/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/7CCE222CE2>) |
| 15b7:5009 | 15b7:5009 | SanDisk          | WD Blue SN550 NVMe SSD               | 22    | nvme       | [62990532FE](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKi7/6657C921A76B/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/62990532FE>) |
| 8086:f1a5 | 8086:390a | Intel            | SSD 600P Series                      | 18    | nvme       | [D27EC7C05B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MQS2SV0F/FB6EB060C710/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D27EC7C05B>) |
| c0a9:540a | c0a9:540a | Micron/Crucia... | P2 NVMe PCIe SSD                     | 18    | nvme       | [DFD625BC68](<Mini Pc/Intel Client Systems/NUC10/NUC10i5FNH/F9FC40BCC314/UBUNTU-20.04/5.4.0-146-GENERIC/X86_64/DFD625BC68>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013 E13 NVMe Controller           | 17    | nvme       | [213CD129CD](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/DA788620325B/DEBIAN-11/5.10.0-21-AMD64/X86_64/213CD129CD>) |
| 2646:2263 | 2646:2263 | Kingston Tech... | A2000 NVMe SSD                       | 17    | nvme       | [FCCB05FBEF](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-406/E821B07C41C5/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/FCCB05FBEF>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 15    | nvme       | [1B49E21822](<Mini Pc/Intel Client Systems/NUC7/NUC7i5DNKE/9520DB1C59AE/KUBUNTU-22.10/5.19.0-35-GENERIC/X86_64/1B49E21822>) |
| 1c5c:174a | 1c5c:174a | SK hynix         | Gold P31/PC711 NVMe Solid State D... | 15    | nvme       | [9CE704A4B9](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G6 Desktop Mini PC/3BD98BA3E33B/DEBIAN-11/5.10.0-21-AMD64/X86_64/9CE704A4B9>) |
| c0a9:2263 | c0a9:2263 | Micron/Crucia... | P1 NVMe PCIe SSD                     | 14    | nvme       | [A92B4A305F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/21A3465BD54D/DEBIAN-11/5.10.0-21-AMD64/X86_64/A92B4A305F>) |
| 1179:0116 | 1179:0001 | Toshiba Ameri... | XG5 NVMe SSD Controller              | 13    | nvme       | [8111885092](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G3 DM/31906DBA1358/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/8111885092>) |
| 15b7:5002 | 15b7:5002 | SanDisk          | WD Black 2018/SN750 / PC SN720 NV... | 13    | nvme       | [B00FA62F7C](<Mini Pc/Intel Client Systems/NUC7/NUC7i7DNKE/E1250A723D48/KDE-NEON-22.04/5.19.0-40-GENERIC/X86_64/B00FA62F7C>) |
| 15b7:501a | 15b7:501a | SanDisk          | WD Blue SN570 NVMe SSD               | 13    | nvme       | [1B7F3C90CA](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/4F56B3D0D076/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/1B7F3C90CA>) |
| 15b7:5011 | 15b7:5011 | SanDisk          | WD PC SN810 / Black SN850 NVMe SSD   | 12    | nvme       | [14761D1566](<Mini Pc/CSL-Computer/Celeron/Celeron/AA990300D125/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/14761D1566>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 12    | nvme       | [507F441BFC](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/271976958C44/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/507F441BFC>) |
| c0a9:540a | c0a9:5021 | Micron/Crucia... | P2 NVMe PCIe SSD                     | 11    | nvme       | [6097531BFC](<Mini Pc/AZW/SER/SER/0FDA0A46CA08/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/6097531BFC>) |
| 126f:2262 | 126f:2262 | Silicon Motion   | SM2262/SM2262EN SSD Controller       | 10    | nvme       | [03C7DC63DA](<Mini Pc/Intel Client Systems/NUC10/NUC10i5FNK/088644A0DB09/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/03C7DC63DA>) |
| 8086:f1a6 | 8086:390b | Intel            | SSD Pro 7600p/760p/E 6100p Series    | 9     | nvme       | [8078D7CA28](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNKP/F6FE7725A838/FEDORA-39/6.3.0-0.RC0.20230303GIT2EB29D59DDF0.13.FC39.X86_64/X86_64/8078D7CA28>) |
| 1e0f:0001 | 1e0f:0001 | KIOXIA           | NVMe SSD Controller BG4              | 8     | nvme       | [A671F44480](<Mini Pc/Hewlett-Packard/Elite/Elite Mini 800 G9 Desktop PC/236AD7372929/DEBIAN-11/5.15.12/X86_64/A671F44480>) |
| 2646:5008 | 2646:5008 | Kingston Tech... | U-SNS8154P3 NVMe SSD                 | 8     | nvme       | [CBFDFC82B4](<Mini Pc/Chuwi/LarkBox/LarkBox X/1EDC925D0177/DEBIAN-11/5.10.0-19-AMD64/X86_64/CBFDFC82B4>) |
| 1987:5016 | 1987:5016 | Phison Electr... | E16 PCIe4 NVMe Controller            | 6     | nvme       | [9BC1ED9531](<Mini Pc/Intel Client Systems/NUC11/NUC11TNBv7/CF66240F29BB/UBUNTU-22.04/5.17.0-1014-OEM/X86_64/9BC1ED9531>) |
| 1c5c:1327 | 1c5c:0000 | SK hynix         | BC501 NVMe Solid State Drive         | 6     | nvme       | [8D210CCE39](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G6 Desktop Mini PC/74BE63B62162/ENDEAVOUROS-ROLLING/6.2.12-ARCH1-1/X86_64/8D210CCE39>) |
| 1c5c:1639 | 1c5c:1639 | SK hynix         | Non-Volatile memory controller       | 6     | nvme       | [9721D24C04](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DT003RRU/8094613BB2EA/RED-OS-7.3/5.15.78-2.EL7.3.X86_64/X86_64/9721D24C04>) |
| 2646:5021 | 2646:5021 | Kingston Tech... | Technology Company Non-Volatile m... | 6     | nvme       | [037E8C7254](<Mini Pc/AZW/SER/SER/FA045DCBCCD5/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/037E8C7254>) |
| 8086:f1aa | 8086:390f | Intel            | Non-Volatile memory controller       | 6     | nvme       | [6799113F3E](<Mini Pc/AZW/SER/SER/D1AED4CBE717/XEROG/6.1.12-ZEN1-1-ZEN/X86_64/6799113F3E>) |
| 15b7:5017 | 15b7:5017 | SanDisk          | NVMe Controller                      | 5     | nvme       | [F7CDC4223D](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/797C2DA701A6/XUBUNTU-22.04/6.2.9-060209-GENERIC/X86_64/F7CDC4223D>) |
| 1987:5008 | 1987:5008 | Phison Electr... | NVMe Storage Controller              | 5     | nvme       | [FC74DC1357](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/DC511A2DF716/DEBIAN/6.0.0-2-AMD64/X86_64/FC74DC1357>) |
| 1c5c:1339 | 1c5c:0000 | SK hynix         | BC511                                | 5     | nvme       | [FDCB637C97](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/BB89D4F8427B/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/FDCB637C97>) |
| 1c5c:1627 | 1c5c:1627 | SK hynix         | Non-Volatile memory controller       | 5     | nvme       | [F7CA8D84CA](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A4000GGE/BA13EDD10A17/FEDORA-35/5.15.6-200.FC35.X86_64/X86_64/F7CA8D84CA>) |
| 1e95:9100 | 126f:2263 | Solid State S... | Non-Volatile memory controller       | 5     | nvme       | [EBA2B6CE4E](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/623C6DFA14C1/DEBIAN-12/6.1.0-7-AMD64/X86_64/EBA2B6CE4E>) |
| 2646:500d | 2646:500d | Kingston Tech... | OM3PDP3 NVMe SSD                     | 5     | nvme       | [86A3944105](<Mini Pc/AZW/SER/SER/4F9AF19348C5/DEBIAN-11/5.10.6-1-PVE/X86_64/86A3944105>) |
| 2646:500e | 2646:500e | Kingston Tech... | SNVS2000G [NV1 NVMe PCIe SSD 2TB]    | 5     | nvme       | [063A4BB843](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50-E1/6D982203448C/DEBIAN-SID/6.1.7/X86_64/063A4BB843>) |
| 2646:5017 | 2646:5017 | Kingston Tech... | Technology Company Non-Volatile m... | 5     | nvme       | [6184308BD3](<Mini Pc/ZOTAC/ZBOX-ECM7307/ZBOX-ECM73070C-7307LH-53060C/97C1F8B840C8/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/6184308BD3>) |
| c0a9:5412 | c0a9:0100 | Micron/Crucia... | NVMe Storage Controller              | 5     | nvme       | [F75685D3BE](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-403/A858DBEADDB9/MANJARO/6.1.23-1-MANJARO/X86_64/F75685D3BE>) |
| 1179:011a | 1179:0001 | Toshiba Ameri... | XG6 NVMe SSD Controller              | 4     | nvme       | [5205C41BC5](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M625q 10TF002MGE/79CE2ACCD525/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/5205C41BC5>) |
| 1344:5413 | 1344:1100 | Micron Techno... | NVMe Controller                      | 4     | nvme       | [41FA60329F](<Mini Pc/AZW/SER/SER/6A8219B028E8/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/41FA60329F>) |
| 15b7:5003 | 15b7:5003 | SanDisk          | WD Blue SN500 / PC SN520 NVMe SSD    | 4     | nvme       | [16B8333671](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/DFFAF76553E6/DEEPIN-20.8/5.18.17-AMD64-DESKTOP-COMMUNITY-HWE/X86_64/16B8333671>) |
| 15b7:5005 | 15b7:5005 | SanDisk          | PC SN520 NVMe SSD                    | 4     | nvme       | [52B38CEE5C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VG000EUS/FEE9E9034339/KUBUNTU-22.10/5.19.0-26-GENERIC/X86_64/52B38CEE5C>) |
| 15b7:5019 | 15b7:5019 | SanDisk          | Non-Volatile memory controller       | 4     | nvme       | [35510EAF63](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/A6FB31A882F4/FEDORA-37/6.2.7-200.FC37.X86_64/X86_64/35510EAF63>) |
| 1bb1:5012 | 1bb1:5012 | Seagate Techn... | FireCuda 510 SSD                     | 4     | nvme       | [564C992A69](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/2E531BF3A99D/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/564C992A69>) |
| 2646:5013 | 2646:5013 | Kingston Tech... | Technology Company Non-Volatile m... | 4     | nvme       | [785A41F4E9](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi5/72C6F46CB420/CENTOS-9/5.14.0-289.EL9.X86_64/X86_64/785A41F4E9>) |
| 8086:2522 | 8086:3806 | Intel            | NVMe Optane Memory Series            | 4     | nvme       | [9FD1F28183](<Mini Pc/Intel Client Systems/NUC7/NUC7i7BNHX/7537AD613D75/UBUNTU-22.04/5.15.0-52-GENERIC/X86_64/9FD1F28183>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:282a | 8086:2074 | Intel            | 82801 Mobile SATA Controller [RAI... | 6     | ahci       | [09966CDD9A](<Mini Pc/Intel Client Systems/NUC8/NUC8i7BEH/156E47AE720D/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/09966CDD9A>) |
| 8086:2822 | 103c:82c0 | Intel            | SATA Controller [RAID mode]          | 5     | ahci       | [C35B1DB9A1](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G3 Workstation/C879EA567BC9/UBUNTU-22.04/5.18.12-051812-GENERIC/X86_64/C35B1DB9A1>) |
| 8086:282a | 8086:2081 | Intel            | 82801 Mobile SATA Controller [RAI... | 4     | ahci       | [042FB842D2](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/FF9B4FBF244B/DEBIAN-11/5.10.0-20-AMD64/X86_64/042FB842D2>) |
| 8086:2822 | 103c:8458 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [4DA864256D](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G4 Workstation/2A25D01147BA/DEBIAN-11/5.18.16-1RODETE4-AMD64/X86_64/4DA864256D>) |
| 8086:06d6 | 103c:8754 | Intel            | Comet Lake PCH-H RAID                | 2     | ahci       | [4913915D6F](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G5 Workstation/27025763B8C7/ARCH-ROLLING/6.1.15-1-LTS/X86_64/4913915D6F>) |
| 8086:2822 | 103c:829a | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [534D46FCAB](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/D4E71A99CACC/LINUXMINT-20.3/5.4.0-113-GENERIC/X86_64/534D46FCAB>) |
| 8086:467f | 8086:0000 | Intel            | Volume Management Device NVMe RAI... | 2     | vmd        | [C9A2A7F73C](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN64/C413A7E78C2D/UBUNTU-22.04/6.2.0-21-GENERIC/X86_64/C9A2A7F73C>) |
| 1022:43bd | 103c:872c | AMD              | FCH RAID Controller                  | 1     |            | [0E48C94F83](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 805 G6 Desktop Mini PC/FB1F518D1327/CENTOS-8/4.18.0-240.22.1.EL8_3.X86_64/X86_64/0E48C94F83>) |
| 8086:2822 | 103c:829e | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [0028753E4D](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G3 DM/341483C13D08/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/0028753E4D>) |
| 8086:2822 | 103c:82bf | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [305883BE65](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G3 Workstation/A9881D706083/MANJARO/6.1.19-1-MANJARO/X86_64/305883BE65>) |
| 8086:2822 | 103c:8457 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [9B6E5BB6EA](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G4 Workstation/E2A11D014692/LINUXMINT-20.3/5.4.0-120-GENERIC/X86_64/9B6E5BB6EA>) |
| 8086:282a | 1043:8744 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [F0BAB8D97C](<Mini Pc/ASUSTek Computer/UN65/UN65U/859CC84F4A33/AXYL-ROLLING/5.19.13-ARCH1-1/X86_64/F0BAB8D97C>) |
| 8086:282a | 19da:b248 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [D521E3AD79](<Mini Pc/ZOTAC/ZBOX-EN/ZBOX-EN760/C87907D81660/LINUXMINT-19.3/5.4.0-42-GENERIC/X86_64/D521E3AD79>) |
| 8086:282a | 8086:2068 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [1C3A187EC6](<Mini Pc/Intel/NUC7/NUC7i3BNK/41760ECEF797/KUBUNTU-21.04/5.11.0-41-LOWLATENCY/X86_64/1C3A187EC6>) |
| 8086:282a | 8086:2073 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [6D946007B8](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HNK/6F86351FEFD1/KALI-2022.3/5.19.0-KALI2-AMD64/X86_64/6D946007B8>) |
| 8086:282a | 8086:2079 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [985AA77681](<Mini Pc/Intel Client Systems/NUC8/NUC8i5INH/B39881C57542/CLEAR-LINUX-OS-34440/5.10.19-1032.NATIVE/X86_64/985AA77681>) |
| 8086:9a0b | 8086:0000 | Intel            | Volume Management Device NVMe RAI... | 1     |            | [E1E4CBBE30](<Mini Pc/Intel Client Systems/NUC11/NUC11BTMi7/B1E0EE37A099/RHEL-7/3.10.0-1160.59.1.EL7.X86_64/X86_64/E1E4CBBE30>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1911 | 8086:2074 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 207   |            | [A92B4A305F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/21A3465BD54D/DEBIAN-11/5.10.0-21-AMD64/X86_64/A92B4A305F>) |
| 8086:1911 | 8086:2081 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 122   |            | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 8086:15e8 | 8086:2081 | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 119   | thunder... | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 8086:1911 | 8086:2068 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 105   |            | [05B1BDF24D](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/5A48D52A7EDA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/05B1BDF24D>) |
| 8086:156c |           | Intel            | DSL5520 Thunderbolt 2 NHI [Falcon... | 70    | thunder... | [FA074ED7C9](<Mini Pc/Apple/Macmini7/Macmini7,1/9A4B9DC9209B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FA074ED7C9>) |
| 8086:1513 | 2222:1111 | Intel            | CV82524 Thunderbolt Controller [L... | 63    | thunder... | [0CCFB5109B](<Mini Pc/Apple/Macmini5/Macmini5,1/C751DFCA80AB/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/0CCFB5109B>) |
| 8086:1911 | 8086:2073 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 54    |            | [68B65FDA4C](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/0FA94421095F/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/68B65FDA4C>) |
| 8086:1911 | 8086:2064 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 45    |            | [19BB30E27A](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-405/6215398CADD3/ARCH-ROLLING/6.2.11-ARCH1-1/X86_64/19BB30E27A>) |
| 8086:9a11 | 8086:3004 | Intel            | GNA Scoring Accelerator module       | 39    |            | [7232D92C69](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi5/E0ECB94FBAC3/DEBIAN-11/5.10.0-21-AMD64/X86_64/7232D92C69>) |
| 8086:1911 | 8086:2070 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 28    |            | [861B0673A0](<Mini Pc/Intel/NUC7/NUC7i5DNKE/960B20F7C35D/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/861B0673A0>) |
| 8086:1911 | 17aa:312d | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 26    |            | [3A87280F55](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8SEYP00/41DB2AC53FB7/ARCH-ROLLING/6.2.9-ARCH1-1/X86_64/3A87280F55>) |
| 8086:15eb | 8086:0000 | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 23    | thunder... | [7CCE222CE2](<Mini Pc/Apple/Macmini8/Macmini8,1/C2BFA09A14AD/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/7CCE222CE2>) |
| 8086:4e11 | 1043:8813 | Intel            | Jasper Lake System Peripheral        | 20    |            | [99D3ECA719](<Mini Pc/CSL-Computer/Mini/Mini PN41/19DD952D9531/ZORIN-16/5.15.0-71-GENERIC/X86_64/99D3ECA719>) |
| 8086:464f | 8086:3024 | Intel            | 12th Gen Core Processor Gaussian ... | 18    |            | [68B1E1E6CB](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/5A227E0116FB/KUBUNTU-23.04/6.3.1-CUSTOM/X86_64/68B1E1E6CB>) |
| 8086:1911 | 8086:2015 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 16    |            | [86E1A89B72](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/E1E22FE45F6D/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/86E1A89B72>) |
| 8086:3190 | 1043:875e | Intel            | Celeron/Pentium Silver Processor ... | 15    |            | [8C5E382D0A](<Mini Pc/ASUSTek Computer/PN/PN40/65635FC05246/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/8C5E382D0A>) |
| 8086:1911 | 17aa:3135 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 14    |            | [A1E7A34896](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CES0BH00/C62828790843/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.4-1-DEFAULT/X86_64/A1E7A34896>) |
| 8086:9a11 | 8086:3002 | Intel            | GNA Scoring Accelerator module       | 14    |            | [B85A510A03](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKi5/2E2F0EA6AA4A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/B85A510A03>) |
| 8086:15eb | 8086:2088 | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 11    | thunder... | [8749B43DB1](<Mini Pc/Intel Client Systems/NUC9/NUC9i9QNX/519180459546/UBUNTU-20.04/5.15.0-46-GENERIC/X86_64/8749B43DB1>) |
| 8086:1911 | 17aa:3136 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 11    |            | [BDC231EAE9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RUS00300/1B1E837DD190/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/BDC231EAE9>) |
| 8086:1911 | 8086:7270 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 11    |            | [8042BCA2E6](<Mini Pc/AZW/SEi/SEi/96A7CA1D6C7E/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/8042BCA2E6>) |
| 8086:4e11 | 8086:3027 | Intel            | Jasper Lake System Peripheral        | 11    |            | [1B7F3C90CA](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/4F56B3D0D076/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/1B7F3C90CA>) |
| 8086:3190 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 10    |            | [71EE0575D4](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/06099CAD1A2D/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/71EE0575D4>) |
| 8086:9a11 | 8086:2090 | Intel            | GNA Scoring Accelerator module       | 10    |            | [F28F7150BA](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/C55F851F02E4/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/F28F7150BA>) |
| 8086:15d9 | 8086:2074 | Intel            | JHL6340 Thunderbolt 3 NHI (C step... | 9     | thunder... | [FA975AC535](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/3A352B8322BD/OPENMANDRIVA-4.90/5.18.12-DESKTOP-3OMV4090/X86_64/FA975AC535>) |
| 8086:1911 | 17aa:316e | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 9     |            | [0C5D92EBF9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DT003GRU/DFE02E0590AD/RED-OS-7.3/5.15.87-1.EL7.3.X86_64/X86_64/0C5D92EBF9>) |
| 8086:1911 | 19da:b440 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 8     |            | [6184308BD3](<Mini Pc/ZOTAC/ZBOX-ECM7307/ZBOX-ECM73070C-7307LH-53060C/97C1F8B840C8/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/6184308BD3>) |
| 8086:1911 | 17aa:314d | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 7     |            | [4673EC60EA](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AD000UGE/E42960BAAF23/POP!_OS-22.04/6.0.12-76060006-GENERIC/X86_64/4673EC60EA>) |
| 8086:1911 | 8086:2089 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 7     |            | [8749B43DB1](<Mini Pc/Intel Client Systems/NUC9/NUC9i9QNX/519180459546/UBUNTU-20.04/5.15.0-46-GENERIC/X86_64/8749B43DB1>) |
| 8086:9a11 | 8086:3003 | Intel            | GNA Scoring Accelerator module       | 7     |            | [94D4FE9A93](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKv7/10393889EC9C/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/94D4FE9A93>) |
| 8086:1911 | 19da:b333 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 6     |            | [5F703BFC7D](<Mini Pc/ZOTAC/ZBOX-EN1070/ZBOX-EN1070-1060,EN1070K-1060K/C708E1327B22/OPENMANDRIVA-4.3/5.16.13-DESKTOP-1OMV4003/X86_64/5F703BFC7D>) |
| 8086:a74f | 8086:3033 | Intel            | Core i9/i7/i5/i3 GNA Scoring Acce... | 6     |            | [77577A0447](<Mini Pc/Intel Client Systems/NUC13/NUC13RNGi5/5FB909E0A69B/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/77577A0447>) |
| 8086:1575 | 2222:1111 | Intel            | DSL6340 Thunderbolt 3 NHI [Alpine... | 5     | thunder... | [8E03A02104](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/DDE9BAC39F50/UBUNTU-22.04/5.15.0-40-GENERIC/X86_64/8E03A02104>) |
| 8086:1911 | 17aa:3172 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 5     |            | [1DDBBF71EB](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFCTO1WW/AEAA18AE3FAE/FEDORA-36/5.19.16-200.FC36.X86_64/X86_64/1DDBBF71EB>) |
| 8086:1911 | 19da:b411 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 5     |            | [FEF5F08978](<Mini Pc/ZOTAC/ZBOX-EN7208/ZBOX-EN72080V-EN72070V-EN52060V-EN51660T/FEC8FB1A3ACB/XUBUNTU-20.04/5.4.0-65-GENERIC/X86_64/FEF5F08978>) |
| 8086:3190 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 5     |            | [B8546E4162](<Mini Pc/Fanless Mini PC/PCG35/PCG35 GLK/00E97DC632F1/ARCO/6.0.1-ARCH2-1/X86_64/B8546E4162>) |
| 8086:15d2 | 8086:2073 | Intel            | JHL6540 Thunderbolt 3 NHI (C step... | 4     | thunder... | [68B65FDA4C](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/0FA94421095F/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/68B65FDA4C>) |
| 8086:15de | 2222:1111 | Intel            | JHL6340 Thunderbolt 3 Controller ... | 4     | thunder... | [78B5820785](<Mini Pc/Intel/NUC7i3BNB/NUC7i3BNB J22859-303/3A9D186752F0/UBUNTU-18.04/4.15.0-72-GENERIC/X86_64/78B5820785>) |
| 8086:1911 | 8086:2088 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 4     |            | [C99C3CDAC6](<Mini Pc/Intel Client Systems/NUC9/NUC9VXQNX/41AB2C49D511/FEDORA-35/5.17.4-200.FC35.X86_64/X86_64/C99C3CDAC6>) |
| 8086:464f | 8086:3020 | Intel            | 12th Gen Core Processor Gaussian ... | 4     |            | [BB51E864A7](<Mini Pc/Intel Client Systems/NUC12/NUC12DCMi7/9DF75800A431/UBUNTU-MATE-22.04/5.15.0-60-GENERIC/X86_64/BB51E864A7>) |
| 8086:1911 | 1458:1000 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 3     |            | [686B1350C9](<Mini Pc/Gigabyte Technology/GB-BSi3/GB-BSi3-6100/D5628C0A20B9/OPENSUSE-TUMBLEWEED-XXXXXXXX/5.16.8-1-DEFAULT/X86_64/686B1350C9>) |
| 8086:1911 | 17aa:3307 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 3     |            | [DF054EEC71](<Mini Pc/Lenovo/IdeaCentre/IdeaCentre Mini 5 01IMH05 90Q7002AGF/4106B38F9A0C/LINUXMINT-21/5.15.0-50-GENERIC/X86_64/DF054EEC71>) |
| 8086:1911 | 8086:2079 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 3     |            | [27D189D77F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5INH/B6171178AD06/UBUNTU-22.04/5.15.0-40-GENERIC/X86_64/27D189D77F>) |
| 8086:4e11 |           | Intel            | Jasper Lake System Peripheral        | 3     |            | [D75FBA5311](<Mini Pc/BYTENUC/AZ/AZ51/1A77C2AC53A8/FEDORA-37/6.2.8-200.FC37.X86_64/X86_64/D75FBA5311>) |
| 8086:9a11 | 8086:3019 | Intel            | GNA Scoring Accelerator module       | 3     |            | [D407C538C4](<Mini Pc/Intel Client Systems/NUC11/NUC11BTMi7/74EFD96AADA4/LILIDOG-22/5.10.0-20-AMD64/X86_64/D407C538C4>) |
| 14e4:16be | 14e4:96be | Broadcom         | BCM57765/57785 MS Card Reader        | 2     |            | [BEF5CE8984](<Mini Pc/Apple/Macmini8/Macmini8,1/453BE981DB64/UBUNTU-22.10/6.1.2-T2-KINETIC/X86_64/BEF5CE8984>) |
| 8086:1911 | 1019:9bc6 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [7101BAED7A](<Mini Pc/Daten Tecnologia/DC2/DC2B-U/5CEC86B8AF22/FEDORA-33/5.10.7-200.FC33.X86_64/X86_64/7101BAED7A>) |
| 8086:1911 | 17aa:3144 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [6AE0A203A7](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M630e 10YM0001SP/F8398AF98B3D/FEDORA-37/6.0.18-300.FC37.X86_64/X86_64/6AE0A203A7>) |
| 8086:1911 | 17aa:314c | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [0F66B49A44](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AD000YMX/8552A91D7647/ALPINE-3.13.0_ALPHA20200917/5.4.65-0-LTS/X86_64/0F66B49A44>) |
| 8086:1911 | 19da:b418 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [D1765EBD98](<Mini Pc/ZOTAC/ZBOX-CI622/ZBOX-CI622-CI642-CI662NANO/2AC1C02AA42F/LINUXMINT-21.1/5.15.0-67-GENERIC/X86_64/D1765EBD98>) |

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
| 8086:9ded | 8086:2074 | Intel            | Cannon Point-LP USB 3.1 xHCI Cont... | 207   | xhci_hcd   | [A92B4A305F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/21A3465BD54D/DEBIAN-11/5.10.0-21-AMD64/X86_64/A92B4A305F>) |
| 8086:02ed | 8086:2081 | Intel            | Comet Lake PCH-LP USB 3.1 xHCI Ho... | 123   | xhci_pci   | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 8086:15e9 | 8086:2081 | Intel            | JHL7540 Thunderbolt 3 USB Control... | 119   | xhci_hcd   | [4C775782EA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/A217958C2DD2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4C775782EA>) |
| 8086:9d2f | 8086:2068 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 105   | xhci_hcd   | [05B1BDF24D](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/5A48D52A7EDA/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/05B1BDF24D>) |
| 8086:0f35 | 8086:0f35 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 91    | xhci_hcd   | [1F19B2C0DC](<Mini Pc/AMI/Aptio/Aptio CRB/E8C182707BA0/DEBIAN-11/5.10.0-21-AMD64/X86_64/1F19B2C0DC>) |
| 8086:1e26 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family USB ... | 90    | ehci_pci   | [3DA35D8BC2](<Mini Pc/Apple/Macmini6/Macmini6,1/BE32E3873E80/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/3DA35D8BC2>) |
| 8086:1e2d | 8086:7270 | Intel            | 7 Series/C216 Chipset Family USB ... | 90    | ehci_pci   | [3DA35D8BC2](<Mini Pc/Apple/Macmini6/Macmini6,1/BE32E3873E80/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/3DA35D8BC2>) |
| 8086:1e31 | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 90    | xhci_hcd   | [3DA35D8BC2](<Mini Pc/Apple/Macmini6/Macmini6,1/BE32E3873E80/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/3DA35D8BC2>) |
| 8086:9c31 | 8086:7270 | Intel            | 8 Series USB xHCI HC                 | 76    | xhci_hcd   | [FA074ED7C9](<Mini Pc/Apple/Macmini7/Macmini7,1/9A4B9DC9209B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FA074ED7C9>) |
| 8086:9a13 |           | Intel            | Tiger Lake-LP Thunderbolt 4 USB C... | 74    | xhci_pci   | [F28F7150BA](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/C55F851F02E4/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/F28F7150BA>) |
| 8086:9a1b | 2222:1111 | Intel            | Tiger Lake-LP Thunderbolt 4 NHI #0   | 72    | thunder... | [F28F7150BA](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/C55F851F02E4/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/F28F7150BA>) |
| 8086:9a1d | 2222:1111 | Intel            | Tiger Lake-LP Thunderbolt 4 NHI #1   | 72    | thunder... | [F28F7150BA](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/C55F851F02E4/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/F28F7150BA>) |
| 8086:9cb1 | 8086:2057 | Intel            | Wildcat Point-LP USB xHCI Controller | 71    | xhci_hcd   | [D89F9A2346](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-507/128101606584/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/D89F9A2346>) |
| 8086:9ca6 | 8086:2057 | Intel            | Wildcat Point-LP USB EHCI Controller | 68    | ehci_pci   | [D89F9A2346](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-507/128101606584/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/D89F9A2346>) |
| 1022:1639 | 1022:1639 | AMD              | Renoir/Cezanne USB 3.1               | 67    | xhci_pci   | [6097531BFC](<Mini Pc/AZW/SER/SER/0FDA0A46CA08/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/6097531BFC>) |
| 8086:15db | 8086:2074 | Intel            | JHL6340 Thunderbolt 3 USB 3.1 Con... | 63    | xhci_hcd   | [19C864F074](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/7C5081232828/FEDORA-37/6.2.9-200.FC37.X86_64/X86_64/19C864F074>) |
| 8086:1c26 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 63    | ehci_pci   | [0CCFB5109B](<Mini Pc/Apple/Macmini5/Macmini5,1/C751DFCA80AB/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/0CCFB5109B>) |
| 8086:1c27 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 63    | uhci_hcd   | [0CCFB5109B](<Mini Pc/Apple/Macmini5/Macmini5,1/C751DFCA80AB/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/0CCFB5109B>) |
| 8086:1c2c | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 63    | uhci_hcd   | [0CCFB5109B](<Mini Pc/Apple/Macmini5/Macmini5,1/C751DFCA80AB/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/0CCFB5109B>) |
| 8086:1c2d | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 63    | ehci_pci   | [0CCFB5109B](<Mini Pc/Apple/Macmini5/Macmini5,1/C751DFCA80AB/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/0CCFB5109B>) |
| 8086:5aa8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 60    | xhci_hcd   | [9F2A1A2C93](<Mini Pc/Nuvision/NEBP/NEBP12/FFE86D67A763/XUBUNTU-22.04/5.15.0-69-GENERIC/X86_64/9F2A1A2C93>) |
| 8086:31a8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 57    | xhci_pci   | [1F1CB63EDC](<Mini Pc/Fanless Mini PC/PCG35/PCG35 GLK/E937013DF7EB/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/1F1CB63EDC>) |
| 1b21:1142 | 1043:85bf | ASMedia Techn... | ASM1042A USB 3.0 Host Controller     | 55    | xhci_pci   | [C1BF3A9C44](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/24AA08459D0E/DEBIAN-11/5.10.0-20-AMD64/X86_64/C1BF3A9C44>) |
| 1b21:2142 | 8086:2073 | ASMedia Techn... | ASM2142/ASM3142 USB 3.1 Host Cont... | 54    | xhci_hcd   | [68B65FDA4C](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/0FA94421095F/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/68B65FDA4C>) |
| 8086:a12f | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 54    | xhci_hcd   | [68B65FDA4C](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/0FA94421095F/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/68B65FDA4C>) |
| 8086:5aa8 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 50    | xhci_hcd   | [AC904A4DF9](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-402/B3229CB33E06/FEDORA-39/6.3.0-0.RC6.20230411GIT0D3EB744AED4.50.FC39.X86_64/X86_64/AC904A4DF9>) |
| 8086:31a8 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 48    | xhci_pci   | [D955CBB060](<Mini Pc/Intel/NUC7/NUC7PJYH/E5C0E8061815/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D955CBB060>) |
| 8086:31a8 | 8086:31a8 | Intel            | Celeron/Pentium Silver Processor ... | 48    | xhci_pci   | [91696FE0F2](<Mini Pc/BESSTAR Tech/GK/GK50/0786D176E577/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/91696FE0F2>) |
| 8086:a12f | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 45    | xhci_hcd   | [19BB30E27A](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-405/6215398CADD3/ARCH-ROLLING/6.2.11-ARCH1-1/X86_64/19BB30E27A>) |
| 1022:1639 | 1043:87e7 | AMD              | Renoir/Cezanne USB 3.1               | 43    | xhci_pci   | [C1BF3A9C44](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/24AA08459D0E/DEBIAN-11/5.10.0-20-AMD64/X86_64/C1BF3A9C44>) |
| 8086:a0ed | 8086:3004 | Intel            | Tiger Lake-LP USB 3.2 Gen 2x1 xHC... | 41    | xhci_pci   | [7232D92C69](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi5/E0ECB94FBAC3/DEBIAN-11/5.10.0-21-AMD64/X86_64/7232D92C69>) |
| 8086:22b5 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 40    | xhci_hcd   | [9408F6348B](<Mini Pc/AMI/Aptio/Aptio CRB/19DF7B640AD0/DEBIAN-11/6.2.10-1-LIQUORIX-AMD64/X86_64/9408F6348B>) |
| 10de:0aa5 | 10de:cb79 | Nvidia           | MCP79 OHCI USB 1.1 Controller        | 38    | ohci_pci   | [A206715EC6](<Mini Pc/Apple/Macmini3/Macmini3,1/807755291B05/UBUNTU-23.04/6.1.12-060112-GENERIC/X86_64/A206715EC6>) |
| 10de:0aa6 | 10de:cb79 | Nvidia           | MCP79 EHCI USB 2.0 Controller        | 38    | ehci_pci   | [A206715EC6](<Mini Pc/Apple/Macmini3/Macmini3,1/807755291B05/UBUNTU-23.04/6.1.12-060112-GENERIC/X86_64/A206715EC6>) |
| 10de:0aa7 | 10de:cb79 | Nvidia           | MCP79 OHCI USB 1.1 Controller        | 38    | ohci_pci   | [A206715EC6](<Mini Pc/Apple/Macmini3/Macmini3,1/807755291B05/UBUNTU-23.04/6.1.12-060112-GENERIC/X86_64/A206715EC6>) |
| 10de:0aa9 | 10de:cb79 | Nvidia           | MCP79 EHCI USB 2.0 Controller        | 38    | ehci_pci   | [A206715EC6](<Mini Pc/Apple/Macmini3/Macmini3,1/807755291B05/UBUNTU-23.04/6.1.12-060112-GENERIC/X86_64/A206715EC6>) |
| 10ec:816d | 1043:85b5 | Realtek Semic... | RTL811x EHCI host controller         | 37    | ehci_pci   | [9CE749E52E](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/4EDEB05C441C/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.1-1-DEFAULT/X86_64/9CE749E52E>) |
| 8086:22b5 |           | Intel            | Atom/Celeron/Pentium Processor x5... | 33    | xhci_hcd   | [A87D0FE300](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-412/4827237811A9/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/A87D0FE300>) |
| 8086:9d2f | 8086:2063 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 29    | xhci_hcd   | [C370821F44](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/C6B76D6C0340/ALMA-9.1/5.14.0-162.23.1.EL9_1.X86_64/X86_64/C370821F44>) |
| 8086:9d2f | 8086:2070 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 28    | xhci_hcd   | [861B0673A0](<Mini Pc/Intel/NUC7/NUC7i5DNKE/960B20F7C35D/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/861B0673A0>) |
| 10de:0d9c | 10de:cb89 | Nvidia           | MCP89 OHCI USB 1.1 Controller        | 26    | ohci_pci   | [6BAD65AD2D](<Mini Pc/Apple/Macmini4/Macmini4,1/43290460D960/ZORIN-16/5.15.0-69-GENERIC/X86_64/6BAD65AD2D>) |
| 10de:0d9d | 10de:cb89 | Nvidia           | MCP89 EHCI USB 2.0 Controller        | 26    | ehci_pci   | [6BAD65AD2D](<Mini Pc/Apple/Macmini4/Macmini4,1/43290460D960/ZORIN-16/5.15.0-69-GENERIC/X86_64/6BAD65AD2D>) |
| 8086:a36d | 17aa:312d | Intel            | Cannon Lake PCH USB 3.1 xHCI Host... | 26    | xhci_hcd   | [3A87280F55](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8SEYP00/41DB2AC53FB7/ARCH-ROLLING/6.2.9-ARCH1-1/X86_64/3A87280F55>) |
| 8086:a36d | 8086:7270 | Intel            | Cannon Lake PCH USB 3.1 xHCI Host... | 24    | xhci_pci   | [7CCE222CE2](<Mini Pc/Apple/Macmini8/Macmini8,1/C2BFA09A14AD/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/7CCE222CE2>) |
| 8086:15ec | 8086:0000 | Intel            | JHL7540 Thunderbolt 3 USB Control... | 23    | xhci_pci   | [7CCE222CE2](<Mini Pc/Apple/Macmini8/Macmini8,1/C2BFA09A14AD/KUBUNTU-22.04/5.19.0-38-GENERIC/X86_64/7CCE222CE2>) |
| 8086:461e |           | Intel            | Alder Lake-P Thunderbolt 4 USB Co... | 23    | xhci_pci   | [68B1E1E6CB](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/5A227E0116FB/KUBUNTU-23.04/6.3.1-CUSTOM/X86_64/68B1E1E6CB>) |
| 8086:a2af | 103c:829a | Intel            | 200 Series/Z370 Chipset Family US... | 23    | xhci_pci   | [EBA2B6CE4E](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/623C6DFA14C1/DEBIAN-12/6.1.0-7-AMD64/X86_64/EBA2B6CE4E>) |
| 1002:4396 | 103c:17e2 | AMD              | SB7x0/SB8x0/SB9x0 USB EHCI Contro... | 22    | ehci_pci   | [02EE837763](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/3EA0F94B1F39/DEBIAN-11/5.10.0-21-AMD64/X86_64/02EE837763>) |
| 1002:4397 | 103c:17e2 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI0 Contr... | 22    | ohci_pci   | [02EE837763](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/3EA0F94B1F39/DEBIAN-11/5.10.0-21-AMD64/X86_64/02EE837763>) |
| 104c:8241 | 103c:17e2 | Texas Instrum... | TUSB73x0 SuperSpeed USB 3.0 xHCI ... | 22    | xhci_pci   | [02EE837763](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/3EA0F94B1F39/DEBIAN-11/5.10.0-21-AMD64/X86_64/02EE837763>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:816e | 10ec:8168 | Realtek Semic... | RealManage BMC                       | 27    |            | [4BE8DDC98E](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/5D3851BCDC5D/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/4BE8DDC98E>) |
| 10ec:816e | 17aa:3181 | Realtek Semic... | RealManage BMC                       | 5     |            | [D4C01D094B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75n 11GWCTO1WW/5439510A54DE/UBUNTU-18.04/5.4.0-137-GENERIC/X86_64/D4C01D094B>) |
| 10ec:5261 | 8086:3026 | Realtek Semic... | RTS5261 PCI Express Card Reader      | 1     | rtsx_pci   | [67985889B2](<Mini Pc/Intel Client Systems/NUC12/NUC12SNKi72/3ED4B618CE1A/DEBIAN-11/5.10.0-21-AMD64/X86_64/67985889B2>) |

