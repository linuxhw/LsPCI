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

Count  - number of computers with this device installed,
Driver - driver in use for this device,
Probe  - latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1a03:1150 | 1a03:1150 | ASPEED Techno... | AST1150 PCI-to-PCI Bridge            | 160   | shpchp     | [9FBB87A829](<Server/VIT/NP3020/NP3020M3/6DA8E8BE5005/DEBIAN-10/4.19.0-18-AMD64/X86_64/9FBB87A829>) |
| 8086:2c70 | 8086:8086 | Intel            | Xeon 5600 Series QuickPath Archit... | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2d81 | 8086:8086 | Intel            | Xeon 5600 Series QuickPath Archit... | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2d90 | 8086:8086 | Intel            | Xeon 5600 Series QPI Link 0          | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2d91 | 8086:8086 | Intel            | Xeon 5600 Series QPI Physical 0      | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2d92 | 8086:8086 | Intel            | Xeon 5600 Series Mirror Port Link 0  | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2d93 | 8086:8086 | Intel            | Xeon 5600 Series Mirror Port Link 1  | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2d94 | 8086:8086 | Intel            | Xeon 5600 Series QPI Link 1          | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2d95 | 8086:8086 | Intel            | Xeon 5600 Series QPI Physical 1      | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2d98 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2d99 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2d9a | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2d9c | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2da0 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2da1 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2da2 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2da3 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2da8 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2da9 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2daa | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2dab | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2db0 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2db1 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2db2 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2db3 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 116   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:2030 | 8086:0000 | Intel            | Sky Lake-E PCI Express Root Port A   | 87    | pcieport   | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2032 | 8086:0000 | Intel            | Sky Lake-E PCI Express Root Port C   | 79    | pcieport   | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2020 | 8086:0000 | Intel            | Sky Lake-E DMI3 Registers            | 71    |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:244e |           | Intel            | 82801 PCI Bridge                     | 55    | shpchp     | [C022B50299](<Server/Dell/PowerEdge/PowerEdge 2900/2D778EC201D6/FEDORA-35/5.16.8-200.FC35.X86_64/X86_64/C022B50299>) |
| 1912:0012 | 1912:0012 | Renesas Techn... | SH7757 PCIe-PCI Bridge [PPB]         | 50    | shpchp     | [7BF19C1CD2](<Server/Dell/PowerEdge/PowerEdge R720/2489ED365DE4/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/7BF19C1CD2>) |
| 1912:0013 | 1912:0013 | Renesas Techn... | SH7757 PCIe Switch [PS]              | 50    | pcieport   | [7BF19C1CD2](<Server/Dell/PowerEdge/PowerEdge R720/2489ED365DE4/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/7BF19C1CD2>) |
| 8086:25e3 |           | Intel            | 5000 Series Chipset PCI Express x... | 46    | pcieport   | [C022B50299](<Server/Dell/PowerEdge/PowerEdge 2900/2D778EC201D6/FEDORA-35/5.16.8-200.FC35.X86_64/X86_64/C022B50299>) |
| 8086:341c |           | Intel            | 7500/5520/5500/X58 Unknown           | 46    |            | [67816634D5](<Server/Supermicro/X8/X8DA3/CC00F7DE0E2E/DEBIAN-11/5.10.0-10-AMD64/X86_64/67816634D5>) |
| 8086:341d |           | Intel            | 7500/5520/5500/X58 Unknown           | 46    |            | [67816634D5](<Server/Supermicro/X8/X8DA3/CC00F7DE0E2E/DEBIAN-11/5.10.0-10-AMD64/X86_64/67816634D5>) |
| 8086:341e |           | Intel            | 7500/5520/5500/X58 Unknown           | 46    |            | [67816634D5](<Server/Supermicro/X8/X8DA3/CC00F7DE0E2E/DEBIAN-11/5.10.0-10-AMD64/X86_64/67816634D5>) |
| 8086:1d10 | 103c:18a9 | Intel            | C600/X79 series chipset PCI Expre... | 45    | pcieport   | [1172390E59](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/2267C96ADE00/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/1172390E59>) |
| 8086:1d1e | 103c:18a9 | Intel            | C600/X79 series chipset PCI Expre... | 45    | pcieport   | [1172390E59](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/2267C96ADE00/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/1172390E59>) |
| 8086:1d3e | 103c:18a9 | Intel            | C600/X79 series chipset PCI Expre... | 45    | pcieport   | [1172390E59](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/2267C96ADE00/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/1172390E59>) |
| 8086:1d41 |           | Intel            | C600/X79 series chipset LPC Contr... | 45    | lpc_ich    | [1172390E59](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/2267C96ADE00/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/1172390E59>) |
| 8086:244e | 103c:18a9 | Intel            | 82801 PCI Bridge                     | 45    |            | [1172390E59](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/2267C96ADE00/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/1172390E59>) |
| 8086:3408 | 103c:330b | Intel            | 5520/5500/X58 I/O Hub PCI Express... | 44    | pcieport   | [537E8D34B7](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 G6/E32F627377A6/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/537E8D34B7>) |
| 8086:340a | 103c:330b | Intel            | 5520/5500/X58 I/O Hub PCI Express... | 44    | pcieport   | [537E8D34B7](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 G6/E32F627377A6/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/537E8D34B7>) |
| 8086:340e | 103c:330b | Intel            | 5520/5500/X58 I/O Hub PCI Express... | 44    | pcieport   | [537E8D34B7](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 G6/E32F627377A6/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/537E8D34B7>) |
| 8086:3410 | 103c:330b | Intel            | 7500/5520/5500/X58 I/O Hub PCI Ex... | 44    | pcieport   | [537E8D34B7](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 G6/E32F627377A6/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/537E8D34B7>) |
| 8086:3418 |           | Intel            | 7500/5520/5500/X58 Physical Layer... | 44    |            | [909B88F852](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/BE425EE16F85/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/909B88F852>) |
| 8086:3419 |           | Intel            | 7500/5520/5500 Physical Layer Port 1 | 44    |            | [909B88F852](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/BE425EE16F85/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/909B88F852>) |
| 8086:341a |           | Intel            | 7500/5520/5500/X58 Unknown           | 44    |            | [909B88F852](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/BE425EE16F85/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/909B88F852>) |
| 8086:3439 |           | Intel            | 7500/5520/5500/X58 Unknown           | 44    |            | [909B88F852](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/BE425EE16F85/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/909B88F852>) |
| 8086:343a |           | Intel            | 7500/5520/5500/X58 Unknown           | 44    |            | [909B88F852](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/BE425EE16F85/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/909B88F852>) |
| 8086:343b |           | Intel            | 7500/5520/5500/X58 Unknown           | 44    |            | [909B88F852](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/BE425EE16F85/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/909B88F852>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:5229 | 10ec:5229 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [9F7F807004](<Server/ECS/LIVA/LIVA Q2/6F0AAEC80AB2/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/9F7F807004>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:19e2 | 8086:0000 | Intel            | Atom Processor C3000 Series Quick... | 3     | qat_c3xxx  | [F96B0CFDA0](<Server/Supermicro/Super/Super Server/9AA985C08DF3/GENTOO-2.7/5.10.76-GENTOO-R1/X86_64/F96B0CFDA0>) |
| 8086:2710 | 8086:0000 | Intel            | Co-processor                         | 2     |            | [AEAD99F55D](<Server/Intel/AST2600/AST2600EVB/BE9050B3ECF3/CENTOS-8/5.12.0-0.RC2.33.EL8.X86_64+SPR/X86_64/AEAD99F55D>) |
| 8086:37c8 | 8086:0000 | Intel            | C62x Chipset QuickAssist Technology  | 2     | qat_c62x   | [9A0AAAD7ED](<Server/Prime Computer/Server/Server Pro/289FB0C396A8/UBUNTU-20.04/5.4.0-99-GENERIC/X86_64/9A0AAAD7ED>) |
| 8086:4940 | 8086:0000 | Intel            | Co-processor                         | 2     |            | [AEAD99F55D](<Server/Intel/AST2600/AST2600EVB/BE9050B3ECF3/CENTOS-8/5.12.0-0.RC2.33.EL8.X86_64+SPR/X86_64/AEAD99F55D>) |
| 8086:0434 | 8086:0000 | Intel            | DH89XXCC Series QAT                  | 1     |            | [14C76E0C83](<Server/F5 Networks/C/C117/C1512B26FE54/ALPINE-3.13.2/5.10.16-0-LTS/X86_64/14C76E0C83>) |
| 8086:0435 | 8086:0000 | Intel            | DH895XCC Series QAT                  | 1     | qat_dh8... | [EB5771B190](<Server/Huawei/Taishan/Taishan 2180/98FD400CE456/DEBIAN-10/4.1.44-06.151.VHULK1711.1.1.AARCH64/AARCH64/EB5771B190>) |
| 8086:1f18 | 15d9:0820 | Intel            | Atom processor C2000 QAT             | 1     |            | [B9AC0D657E](<Server/Supermicro/A1/A1SRM-2558F/DAF42406F667/FEDORA-32/5.8.16-200.FC32.X86_64/X86_64/B9AC0D657E>) |
| 8086:225c | 8086:2500 | Intel            | Xeon Phi coprocessor SE10/7120 se... | 1     | mic_host   | [9D9DA282F6](<Server/Dedicated Computing/OEM-F7342/OEM-F7342-00/A56806D283ED/UBUNTU-20.04/5.4.0-45-GENERIC/X86_64/9D9DA282F6>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a1ba | 8086:35ce | Intel            | C620 Series Chipset Family MEI Co... | 20    | mei_me     | [36C4ACAC2D](<Server/Intel/S2600/S2600WFT/8DC9639F1DBF/ROCKY-8.4/4.18.0-305.10.2.EL8_4.X86_64/X86_64/36C4ACAC2D>) |
| 8086:a1ba | 8086:7270 | Intel            | C620 Series Chipset Family MEI Co... | 20    | mei_me     | [73518731A1](<Server/Supermicro/X11/X11DPi-N/6D6FD3049691/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/73518731A1>) |
| 8086:a1be | 8086:35ce | Intel            | C620 Series Chipset Family MEI Co... | 20    |            | [36C4ACAC2D](<Server/Intel/S2600/S2600WFT/8DC9639F1DBF/ROCKY-8.4/4.18.0-305.10.2.EL8_4.X86_64/X86_64/36C4ACAC2D>) |
| 8086:a1be | 8086:7270 | Intel            | C620 Series Chipset Family MEI Co... | 20    |            | [73518731A1](<Server/Supermicro/X11/X11DPi-N/6D6FD3049691/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/73518731A1>) |
| 8086:a1bb | 8086:35ce | Intel            | C620 Series Chipset Family MEI Co... | 19    |            | [36C4ACAC2D](<Server/Intel/S2600/S2600WFT/8DC9639F1DBF/ROCKY-8.4/4.18.0-305.10.2.EL8_4.X86_64/X86_64/36C4ACAC2D>) |
| 8086:a1bb | 8086:7270 | Intel            | C620 Series Chipset Family MEI Co... | 19    |            | [73518731A1](<Server/Supermicro/X11/X11DPi-N/6D6FD3049691/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/73518731A1>) |
| 8086:8d3a | 15d9:0821 | Intel            | C610/X99 series chipset MEI Contr... | 17    | mei_me     | [AAEEE85BE7](<Server/Supermicro/SYS-6028/SYS-6028R-WTRT/690B86B530B0/DEBIAN-11/4.19.0-17-AMD64/X86_64/AAEEE85BE7>) |
| 8086:8d3b | 15d9:0821 | Intel            | C610/X99 series chipset MEI Contr... | 17    |            | [AAEEE85BE7](<Server/Supermicro/SYS-6028/SYS-6028R-WTRT/690B86B530B0/DEBIAN-11/4.19.0-17-AMD64/X86_64/AAEEE85BE7>) |
| 8086:1d3a | 1043:84ef | Intel            | C600/X79 series chipset MEI Contr... | 16    | mei_me     | [0D39F4F066](<Server/ASUSTek Computer/Z9PE-D16/Z9PE-D16 Series/7948CC9F2801/UBUNTU-18.04/5.4.0-91-GENERIC/X86_64/0D39F4F066>) |
| 8086:1d3b | 1043:84ef | Intel            | C600/X79 series chipset MEI Contr... | 16    |            | [0D39F4F066](<Server/ASUSTek Computer/Z9PE-D16/Z9PE-D16 Series/7948CC9F2801/UBUNTU-18.04/5.4.0-91-GENERIC/X86_64/0D39F4F066>) |
| 8086:1d3a | 1028:048c | Intel            | C600/X79 series chipset MEI Contr... | 13    | mei_me     | [7BF19C1CD2](<Server/Dell/PowerEdge/PowerEdge R720/2489ED365DE4/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/7BF19C1CD2>) |
| 8086:1d3a | 15d9:0636 | Intel            | C600/X79 series chipset MEI Contr... | 13    | mei_me     | [31684AD7E4](<Server/Supermicro/X9/X9DRW/55D2AD4AF0CF/UBUNTU-21.04/5.11.0-44-GENERIC/X86_64/31684AD7E4>) |
| 8086:1d3b | 1028:048c | Intel            | C600/X79 series chipset MEI Contr... | 13    |            | [7BF19C1CD2](<Server/Dell/PowerEdge/PowerEdge R720/2489ED365DE4/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/7BF19C1CD2>) |
| 8086:1d3b | 15d9:0636 | Intel            | C600/X79 series chipset MEI Contr... | 13    |            | [31684AD7E4](<Server/Supermicro/X9/X9DRW/55D2AD4AF0CF/UBUNTU-21.04/5.11.0-44-GENERIC/X86_64/31684AD7E4>) |
| 8086:a13a | 8086:1999 | Intel            | 100 Series/C230 Series Chipset Fa... | 12    | mei_me     | [7C1FA00B21](<Server/Intel/S1200/S1200SP/4B4C83B49974/CENTOS-7/4.4.241-1.EL7.ELREPO.X86_64/X86_64/7C1FA00B21>) |
| 8086:8d3a | 8086:7270 | Intel            | C610/X99 series chipset MEI Contr... | 11    | mei_me     | [50AEBE4B28](<Server/Supermicro/SSG-6048/SSG-6048R-E1CR24H/8A7A52EA4807/CENTOS-8/4.18.0-348.2.1.EL8_5.X86_64/X86_64/50AEBE4B28>) |
| 8086:8d3b | 8086:7270 | Intel            | C610/X99 series chipset MEI Contr... | 11    |            | [50AEBE4B28](<Server/Supermicro/SSG-6048/SSG-6048R-E1CR24H/8A7A52EA4807/CENTOS-8/4.18.0-348.2.1.EL8_5.X86_64/X86_64/50AEBE4B28>) |
| 8086:a1ba | 1028:073a | Intel            | C620 Series Chipset Family MEI Co... | 11    | mei_me     | [2E5507B849](<Server/Dell/Precision/Precision 7920 Tower/6DBFD1DBD45A/UBUNTU-20.04/5.10.0-1055-OEM/X86_64/2E5507B849>) |
| 8086:1d3a | 1028:04ce | Intel            | C600/X79 series chipset MEI Contr... | 9     | mei_me     | [3A287683DC](<Server/Dell/PowerEdge/PowerEdge R620/072234E6D563/DEBIAN-10/5.4.106-1-PVE/X86_64/3A287683DC>) |
| 8086:1d3a | 1028:04fa | Intel            | C600/X79 series chipset MEI Contr... | 9     | mei_me     | [ABE0B5613A](<Server/Dell/PowerEdge/PowerEdge T320/EB32D3263597/UBUNTU-20.04/5.4.0-74-GENERIC/X86_64/ABE0B5613A>) |
| 8086:1d3b | 1028:04ce | Intel            | C600/X79 series chipset MEI Contr... | 9     |            | [3A287683DC](<Server/Dell/PowerEdge/PowerEdge R620/072234E6D563/DEBIAN-10/5.4.106-1-PVE/X86_64/3A287683DC>) |
| 8086:1d3b | 1028:04fa | Intel            | C600/X79 series chipset MEI Contr... | 9     |            | [ABE0B5613A](<Server/Dell/PowerEdge/PowerEdge T320/EB32D3263597/UBUNTU-20.04/5.4.0-74-GENERIC/X86_64/ABE0B5613A>) |
| 8086:a13b | 8086:1999 | Intel            | 100 Series/C230 Series Chipset Fa... | 9     | mei_me     | [7C1FA00B21](<Server/Intel/S1200/S1200SP/4B4C83B49974/CENTOS-7/4.4.241-1.EL7.ELREPO.X86_64/X86_64/7C1FA00B21>) |
| 8086:a1ba | 1043:871e | Intel            | C620 Series Chipset Family MEI Co... | 8     | mei_me     | [55BDC0F976](<Server/ASUSTek Computer/WS-C621E-SAGE/WS-C621E-SAGE Series/6AC5092A72AC/UBUNTU-MATE-20.04/5.8.0-59-GENERIC/X86_64/55BDC0F976>) |
| 8086:a1ba | 15d9:096d | Intel            | C620 Series Chipset Family MEI Co... | 8     | mei_me     | [2CDAC4454D](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.16.8-051608-GENERIC/X86_64/2CDAC4454D>) |
| 8086:a1bb | 15d9:096d | Intel            | C620 Series Chipset Family MEI Co... | 8     |            | [2CDAC4454D](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.16.8-051608-GENERIC/X86_64/2CDAC4454D>) |
| 8086:a1be | 1043:871e | Intel            | C620 Series Chipset Family MEI Co... | 8     |            | [55BDC0F976](<Server/ASUSTek Computer/WS-C621E-SAGE/WS-C621E-SAGE Series/6AC5092A72AC/UBUNTU-MATE-20.04/5.8.0-59-GENERIC/X86_64/55BDC0F976>) |
| 8086:a1be | 15d9:096d | Intel            | C620 Series Chipset Family MEI Co... | 8     |            | [2CDAC4454D](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.16.8-051608-GENERIC/X86_64/2CDAC4454D>) |
| 8086:8d3a | 1043:85f6 | Intel            | C610/X99 series chipset MEI Contr... | 7     | mei_me     | [4158CB76EF](<Server/ASUSTek Computer/RS400/RS400-E8-PS2-F/B939D9497146/GENTOO-2.7/5.10.14-HARDENED1/X86_64/4158CB76EF>) |
| 8086:8d3a | 15d9:0831 | Intel            | C610/X99 series chipset MEI Contr... | 7     | mei_me     | [58E86F0E34](<Server/Supermicro/Super/Super Server/BD4C9B6F043B/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/58E86F0E34>) |
| 8086:8d3b | 1043:85f6 | Intel            | C610/X99 series chipset MEI Contr... | 7     |            | [4158CB76EF](<Server/ASUSTek Computer/RS400/RS400-E8-PS2-F/B939D9497146/GENTOO-2.7/5.10.14-HARDENED1/X86_64/4158CB76EF>) |
| 8086:8d3b | 15d9:0831 | Intel            | C610/X99 series chipset MEI Contr... | 7     |            | [58E86F0E34](<Server/Supermicro/Super/Super Server/BD4C9B6F043B/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/58E86F0E34>) |
| 8086:a1ba | 1590:00eb | Intel            | C620 Series Chipset Family MEI Co... | 7     | mei_me     | [7AB4F05613](<Server/HPE/ProLiant/ProLiant DL360 Gen10/4443D3087423/UBUNTU-18.04/4.15.0-135-GENERIC/X86_64/7AB4F05613>) |
| 8086:a1ba | 17aa:7808 | Intel            | C620 Series Chipset Family MEI Co... | 7     | mei_me     | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 8086:a1bb | 1043:871e | Intel            | C620 Series Chipset Family MEI Co... | 7     |            | [55BDC0F976](<Server/ASUSTek Computer/WS-C621E-SAGE/WS-C621E-SAGE Series/6AC5092A72AC/UBUNTU-MATE-20.04/5.8.0-59-GENERIC/X86_64/55BDC0F976>) |
| 8086:a1bb | 17aa:7808 | Intel            | C620 Series Chipset Family MEI Co... | 7     |            | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 8086:a1be | 1590:00eb | Intel            | C620 Series Chipset Family MEI Co... | 7     |            | [7AB4F05613](<Server/HPE/ProLiant/ProLiant DL360 Gen10/4443D3087423/UBUNTU-18.04/4.15.0-135-GENERIC/X86_64/7AB4F05613>) |
| 8086:a1be | 17aa:7808 | Intel            | C620 Series Chipset Family MEI Co... | 7     |            | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 8086:8d3a | 1028:0601 | Intel            | C610/X99 series chipset MEI Contr... | 6     | mei_me     | [F90168C69D](<Server/Dell/PowerEdge/PowerEdge R630/DBDF919E8981/RHEL-7/3.10.0-1127.19.1.EL7.YAHOO.20200821.63.X86_64/X86_64/F90168C69D>) |
| 8086:8d3b | 1028:0601 | Intel            | C610/X99 series chipset MEI Contr... | 6     |            | [F90168C69D](<Server/Dell/PowerEdge/PowerEdge R630/DBDF919E8981/RHEL-7/3.10.0-1127.19.1.EL7.YAHOO.20200821.63.X86_64/X86_64/F90168C69D>) |
| 8086:a13a | 1028:06a5 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     | mei_me     | [C8D2D41009](<Server/Dell/PowerEdge/PowerEdge R230/5B911C7AB359/UBUNTU-20.04/5.4.0-97-GENERIC/X86_64/C8D2D41009>) |
| 8086:a13b | 1028:06a5 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     | mei_me     | [C8D2D41009](<Server/Dell/PowerEdge/PowerEdge R230/5B911C7AB359/UBUNTU-20.04/5.4.0-97-GENERIC/X86_64/C8D2D41009>) |
| 8086:1d3a | 15d9:0626 | Intel            | C600/X79 series chipset MEI Contr... | 5     | mei_me     | [DE8D4D24B6](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/050383036EDE/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/DE8D4D24B6>) |
| 8086:1d3b | 15d9:0626 | Intel            | C600/X79 series chipset MEI Contr... | 5     |            | [DE8D4D24B6](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/050383036EDE/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/DE8D4D24B6>) |
| 8086:8c3a | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 5     | mei_me     | [12DB3650F6](<Server/Supermicro/Super/Super Server/51A56BB4E7AB/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/12DB3650F6>) |
| 8086:8c3a | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 5     | mei_me     | [E60EC405AF](<Server/Supermicro/Super/Super Server/F5F261808B48/GENTOO-2.6/5.15.19-GENTOO/X86_64/E60EC405AF>) |
| 8086:8c3b | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 5     |            | [12DB3650F6](<Server/Supermicro/Super/Super Server/51A56BB4E7AB/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/12DB3650F6>) |
| 8086:8c3b | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 5     |            | [E60EC405AF](<Server/Supermicro/Super/Super Server/F5F261808B48/GENTOO-2.6/5.15.19-GENTOO/X86_64/E60EC405AF>) |
| 8086:8d3a | 1028:0600 | Intel            | C610/X99 series chipset MEI Contr... | 5     | mei_me     | [11DDC3D97B](<Server/Dell/PowerEdge/PowerEdge R730/B08360FD5D56/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/11DDC3D97B>) |
| 8086:8d3b | 1028:0600 | Intel            | C610/X99 series chipset MEI Contr... | 5     |            | [11DDC3D97B](<Server/Dell/PowerEdge/PowerEdge R730/B08360FD5D56/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/11DDC3D97B>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1498 | 1022:1498 | AMD              | Starship/Matisse PTDMA               | 20    |            | [85004F427A](<Server/Dell/PowerEdge/PowerEdge R6515/591EBA0E828F/SLACKWARE-15.0/5.15.19/X86_64/85004F427A>) |
| 1022:1486 | 1022:1486 | AMD              | Starship/Matisse Cryptographic Co... | 13    | ccp        | [4798AC1234](<Server/Supermicro/Super/Super Server/4CD86DE2F12F/UBUNTU-20.04/5.4.0-84-GENERIC/X86_64/4798AC1234>) |
| 1022:1578 | 1022:1578 | AMD              | Carrizo Platform Security Processor  | 7     |            | [F7739E263E](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/05C34CB58FDD/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/F7739E263E>) |
| 1022:1486 | 1458:1000 | AMD              | Starship/Matisse Cryptographic Co... | 6     | ccp        | [6D2EE30F72](<Server/Gigabyte Technology/MZ71/MZ71-CE0-00/74E7E16574F5/UBUNTU-MATE-20.04/5.11.0-43-GENERIC/X86_64/6D2EE30F72>) |
| 1022:1498 | 1458:1000 | AMD              | Starship/Matisse PTDMA               | 6     |            | [6D2EE30F72](<Server/Gigabyte Technology/MZ71/MZ71-CE0-00/74E7E16574F5/UBUNTU-MATE-20.04/5.11.0-43-GENERIC/X86_64/6D2EE30F72>) |
| 1022:1456 | 1022:1456 | AMD              | Family 17h (Models 00h-0fh) Platf... | 3     | ccp        | [10F1608197](<Server/Supermicro/Super/Super Server/786209B7D1E0/DEBIAN-11/5.11.22-5-PVE/X86_64/10F1608197>) |
| 1022:1468 | 1022:1468 | AMD              | Zeppelin Cryptographic Coprocesso... | 3     | ccp        | [10F1608197](<Server/Supermicro/Super/Super Server/786209B7D1E0/DEBIAN-11/5.11.22-5-PVE/X86_64/10F1608197>) |
| 1022:1486 | 1028:08fc | AMD              | Starship/Matisse Cryptographic Co... | 3     | ccp        | [85004F427A](<Server/Dell/PowerEdge/PowerEdge R6515/591EBA0E828F/SLACKWARE-15.0/5.15.19/X86_64/85004F427A>) |
| 1022:1486 | 1028:08ff | AMD              | Starship/Matisse Cryptographic Co... | 3     | ccp        | [A35E7D3EB0](<Server/Dell/PowerEdge/PowerEdge R7525/6B51CAA01B7C/UBUNTU-20.04/5.4.0-74-GENERIC/X86_64/A35E7D3EB0>) |
| 1022:1498 | 1028:08fc | AMD              | Starship/Matisse PTDMA               | 3     |            | [85004F427A](<Server/Dell/PowerEdge/PowerEdge R6515/591EBA0E828F/SLACKWARE-15.0/5.15.19/X86_64/85004F427A>) |
| 1022:1498 | 1028:08ff | AMD              | Starship/Matisse PTDMA               | 3     |            | [A35E7D3EB0](<Server/Dell/PowerEdge/PowerEdge R7525/6B51CAA01B7C/UBUNTU-20.04/5.4.0-74-GENERIC/X86_64/A35E7D3EB0>) |
| 1022:15df | 1022:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     | ccp        | [0AB1FF409B](<Server/BESSTAR Tech/X/X500/A95AE61E36B4/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/0AB1FF409B>) |
| 1022:1456 | 1458:1000 | AMD              | Family 17h (Models 00h-0fh) Platf... | 2     | ccp        | [6D486A7EE9](<Server/Gigabyte Technology/MZ31/MZ31-AR0-00/20445DA51E24/UBUNTU-20.04/5.6.0-1048-OEM/X86_64/6D486A7EE9>) |
| 1022:1468 | 1458:1000 | AMD              | Zeppelin Cryptographic Coprocesso... | 2     | ccp        | [6D486A7EE9](<Server/Gigabyte Technology/MZ31/MZ31-AR0-00/20445DA51E24/UBUNTU-20.04/5.6.0-1048-OEM/X86_64/6D486A7EE9>) |
| 1022:1456 | 1028:07f9 | AMD              | Family 17h (Models 00h-0fh) Platf... | 1     | ccp        | [8F7FF50C55](<Server/Dell/PowerEdge/PowerEdge R7425/EEF1E1F22650/OPENSUSE-LEAP-15.1/4.12.14-LP151.28.13-DEFAULT/X86_64/8F7FF50C55>) |
| 1022:1468 | 1028:07f9 | AMD              | Zeppelin Cryptographic Coprocesso... | 1     | ccp        | [8F7FF50C55](<Server/Dell/PowerEdge/PowerEdge R7425/EEF1E1F22650/OPENSUSE-LEAP-15.1/4.12.14-LP151.28.13-DEFAULT/X86_64/8F7FF50C55>) |
| 1022:1486 | 1028:08fd | AMD              | Starship/Matisse Cryptographic Co... | 1     | ccp        | [F3CBAC183E](<Server/Dell/PowerEdge/PowerEdge R7515/9A7A286BD3E1/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/F3CBAC183E>) |
| 1022:1498 | 1028:08fd | AMD              | Starship/Matisse PTDMA               | 1     |            | [F3CBAC183E](<Server/Dell/PowerEdge/PowerEdge R7515/9A7A286BD3E1/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/F3CBAC183E>) |

### Firewire controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 104c:8023 | 15d9:0100 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 5     | firewir... | [C83DC07B7C](<Server/Supermicro/X8/X8DAH/B787FD60BF9A/LINUXMINT-20.1/5.4.0-65-GENERIC/X86_64/C83DC07B7C>) |
| 104c:8023 | 15d9:0805 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 5     | firewir... | [019914CC29](<Server/Supermicro/X10/X10SAE/6D8BBA911035/GENTOO-2.7/5.13.12-GENTOO/X86_64/019914CC29>) |
| 1106:3403 | 1043:8384 | VIA Technologies | VT6315 Series Firewire Controller    | 5     | firewir... | [C3665EBF57](<Server/ASUSTek Computer/Z9PE-D8/Z9PE-D8 WS/5BADF976211F/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/C3665EBF57>) |
| 104c:8023 | 8086:34e2 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 4     | firewir... | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 1102:4001 | 1102:0010 | Creative Labs    | SB Audigy FireWire Port              | 4     | firewir... | [F879FD97F7](<Server/TYAN Computer/S/S2895/4B5DFCDB09B6/LINUXMINT-20/5.4.0-58-GENERIC/X86_64/F879FD97F7>) |
| 1106:3403 | 1106:3403 | VIA Technologies | VT6315 Series Firewire Controller    | 3     | firewir... | [D8182AC89A](<Server/ASUSTek Computer/Z9PE-D8/Z9PE-D8 WS/766F4B69F456/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/D8182AC89A>) |
| 104c:823f | 8086:3594 | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 2     | firewir... | [E70645D3E6](<Server/Intel/W2600/W2600CR/5A75A85091D9/UBUNTU-20.04/5.4.0-80-GENERIC/X86_64/E70645D3E6>) |
| 1106:3044 | 1462:6520 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 2     | firewir... | [B8300AFB35](<Server/MSI/MCP/MCP55/8728FA454DA7/UBUNTU-20.04/5.4.0-56-GENERIC/X86_64/B8300AFB35>) |
| 104c:8023 | 10f1:2895 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | firewir... | [768571B831](<Server/TYAN Computer/S/S2895/4B5DFCDB09B6/LINUXMINT-20/5.4.0-58-GENERIC/X86_64/768571B831>) |
| 104c:8023 | 10f1:2915 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | firewir... | [0D3D065311](<Server/TYAN Computer/MCP/MCP55/DB4D10F83692/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/0D3D065311>) |
| 104c:8023 | 15d9:0653 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | firewir... | [171EE8DB12](<Server/Supermicro/C7/C7Z87/4BD99E9BA2B9/XUBUNTU-19.10/5.3.0-18-LOWLATENCY/X86_64/171EE8DB12>) |
| 104c:8023 | 15d9:1411 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | firewir... | [039BF2C96A](<Server/Supermicro/X8/X8DA3/578F928B17F4/LUBUNTU-20.04/5.4.0-42-GENERIC/X86_64/039BF2C96A>) |
| 104c:8024 | 104c:8010 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 1     | firewir... | [18B25AC51A](<Server/TYAN Computer/S/S4882/84BBA0EA52AC/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/18B25AC51A>) |
| 104c:8024 | 1458:132c | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 1     | firewir... | [0AC54E7FB4](<Server/Gigabyte Technology/GA-6/GA-6PXSV1/54F5641A961B/KAISEN-1.6/5.10.0-KAISEN3-AMD64/X86_64/0AC54E7FB4>) |
| 104c:823f | 3412:7856 | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 1     | firewir... | [21E2FBBB75](<Server/Supermicro/Super/Super Server/A70DB16AB074/UBUNTU-18.04/4.15.0-29-GENERIC/X86_64/21E2FBBB75>) |
| 1106:3044 | 108e:534d | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 1     | firewir... | [1F35F79302](<Server/Sun Microsystems/Ultra20/Ultra20 M2/23D902832E84/ROSA-2014.1/4.1.15-NRJ-DESKTOP-1ROSA-I586/I686/1F35F79302>) |
| 1106:3044 | 1106:3044 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 1     | firewir... | [CC8DB94EBA](<Server/Supermicro/X8/X8DT3/37E408F4C551/UBUNTU-19.04/4.19.0-13-LOWLATENCY/X86_64/CC8DB94EBA>) |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1002:5a23 | 1002:5a23 | AMD              | RD890S/RD990 I/O Memory Managemen... | 11    |            | [AA1C79AB75](<Server/Supermicro/H8/H8DG6-H8DGi/49F6AA867D33/ARCH/5.16.5-ARCH1-1/X86_64/AA1C79AB75>) |
| 1022:1577 | 1022:1577 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 2     |            | [5D00EDD035](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/2052FF1A6B1D/UBUNTU-20.10/5.8.0-41-GENERIC/X86_64/5D00EDD035>) |
| 8086:0b23 | 8086:0000 | Intel            | Generic system peripheral            | 2     | pcieport   | [AEAD99F55D](<Server/Intel/AST2600/AST2600EVB/BE9050B3ECF3/CENTOS-8/5.12.0-0.RC2.33.EL8.X86_64+SPR/X86_64/AEAD99F55D>) |
| 8086:0b23 | 8086:7270 | Intel            | Generic system peripheral            | 2     | pcieport   | [AEAD99F55D](<Server/Intel/AST2600/AST2600EVB/BE9050B3ECF3/CENTOS-8/5.12.0-0.RC2.33.EL8.X86_64+SPR/X86_64/AEAD99F55D>) |
| 8086:19a2 | 15d9:0969 | Intel            | Atom Processor C3000 Series Root ... | 2     | pcieport   | [40E07B4DAD](<Server/Supermicro/Super/Super Server/73152EF104BB/MANJARO-21.0.2/5.11.14-1-MANJARO/X86_64/40E07B4DAD>) |
| 1022:1451 | 1022:1451 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 1     |            | [10F1608197](<Server/Supermicro/Super/Super Server/786209B7D1E0/DEBIAN-11/5.11.22-5-PVE/X86_64/10F1608197>) |
| 8086:19a2 | 15d9:1b10 | Intel            | Atom Processor C3000 Series Root ... | 1     |            | [F96B0CFDA0](<Server/Supermicro/Super/Super Server/9AA985C08DF3/GENTOO-2.7/5.10.76-GENTOO-R1/X86_64/F96B0CFDA0>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1a03:2000 | 1a03:2000 | ASPEED Techno... | ASPEED Graphics Family               | 60    | ast        | [73518731A1](<Server/Supermicro/X11/X11DPi-N/6D6FD3049691/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/73518731A1>) |
| 102b:0533 | 103c:3381 | Matrox Electr... | MGA G200EH                           | 55    | mgag200    | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 1002:515e | 103c:31fb | AMD              | ES1000                               | 48    | radeon     | [909B88F852](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/BE425EE16F85/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/909B88F852>) |
| 102b:0522 | 8086:0103 | Matrox Electr... | MGA G200e [Pilot] ServerEngines (... | 32    | mgag200    | [7C1FA00B21](<Server/Intel/S1200/S1200SP/4B4C83B49974/CENTOS-7/4.4.241-1.EL7.ELREPO.X86_64/X86_64/7C1FA00B21>) |
| 102b:0532 | 1028:0235 | Matrox Electr... | MGA G200eW WPCM450                   | 17    | mgag200    | [27639679E2](<Server/Dell/PowerEdge/PowerEdge R710/ACC1A39EDD24/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/27639679E2>) |
| 1a03:2000 | 15d9:0821 | ASPEED Techno... | ASPEED Graphics Family               | 17    | ast        | [AAEEE85BE7](<Server/Supermicro/SYS-6028/SYS-6028R-WTRT/690B86B530B0/DEBIAN-11/4.19.0-17-AMD64/X86_64/AAEEE85BE7>) |
| 102b:0522 | 8086:0101 | Matrox Electr... | MGA G200e [Pilot] ServerEngines (... | 16    | mgag200    | [16885BD699](<Server/Intel/S3420/S3420GP/F23666DD52C7/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/16885BD699>) |
| 102b:0532 | 15d9:0006 | Matrox Electr... | MGA G200eW WPCM450                   | 15    | mgag200    | [89D676AF03](<Server/Supermicro/X8/X8DTL/6E7DE9F9FEDC/DEBIAN-11/5.10.0-11-AMD64/X86_64/89D676AF03>) |
| 10de:1eba | 10de:0000 | Nvidia           | 3D controller                        | 15    | nvidia     | [4391DFF8D2](<Server/Others/Others/Others/29E67FFE5E37/UBUNTU-18.04/4.18.0-20-GENERIC/X86_64/4391DFF8D2>) |
| 102b:0536 |           | Matrox Electr... | Integrated Matrox G200eW3 Graphic... | 14    | mgag200    | [85004F427A](<Server/Dell/PowerEdge/PowerEdge R6515/591EBA0E828F/SLACKWARE-15.0/5.15.19/X86_64/85004F427A>) |
| 102b:0530 | 1014:0369 | Matrox Electr... | MGA G200EV                           | 13    | mgag200    | [76A0EBBFC4](<Server/IBM/System/System x3550 M3 -[7944KAG]-/E6F6F92CA768/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/76A0EBBFC4>) |
| 102b:0534 | 1028:048c | Matrox Electr... | G200eR2                              | 13    | mgag200    | [7BF19C1CD2](<Server/Dell/PowerEdge/PowerEdge R720/2489ED365DE4/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/7BF19C1CD2>) |
| 102b:0534 | 15d9:0636 | Matrox Electr... | G200eR2                              | 13    | mgag200    | [31684AD7E4](<Server/Supermicro/X9/X9DRW/55D2AD4AF0CF/UBUNTU-21.04/5.11.0-44-GENERIC/X86_64/31684AD7E4>) |
| 102b:0522 | 19a2:0101 | Matrox Electr... | MGA G200e [Pilot] ServerEngines (... | 12    | mgag200    | [FF6113B91D](<Server/Lenovo/ThinkSystem/ThinkSystem SR630 V2/ECB5C724E79D/CENTOS-7/3.10.0-1160.49.1.EL7.X86_64/X86_64/FF6113B91D>) |
| 102b:0534 | 1014:0405 | Matrox Electr... | G200eR2                              | 10    | mgag200    | [C717BB4AC6](<Server/IBM/System/System X iDataPlex dx360 M4 Server -[7912AC1]-/E15173785994/UBUNTU-18.04/4.15.0-166-GENERIC/X86_64/C717BB4AC6>) |
| 102b:0532 | 1028:0236 | Matrox Electr... | MGA G200eW WPCM450                   | 9     | mgag200    | [02E5C56A80](<Server/Dell/PowerEdge/PowerEdge R610/D7D0CF9B35C0/ROCKY-8.5/4.18.0-348.12.2.EL8_5.X86_64/X86_64/02E5C56A80>) |
| 102b:0534 | 1028:04ce | Matrox Electr... | G200eR2                              | 9     | mgag200    | [3A287683DC](<Server/Dell/PowerEdge/PowerEdge R620/072234E6D563/DEBIAN-10/5.4.106-1-PVE/X86_64/3A287683DC>) |
| 102b:0532 | 1028:02a4 | Matrox Electr... | MGA G200eW WPCM450                   | 8     | mgag200    | [2CAE1B1D80](<Server/Dell/PowerEdge/PowerEdge T310/1B407A78D4C5/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/2CAE1B1D80>) |
| 19e5:1711 |           | Huawei Techno... | Hi171x Series [iBMC Intelligent M... | 8     | hibmc_drm  | [EB5771B190](<Server/Huawei/Taishan/Taishan 2180/98FD400CE456/DEBIAN-10/4.1.44-06.151.VHULK1711.1.1.AARCH64/AARCH64/EB5771B190>) |
| 1a03:2000 | 1043:85f9 | ASPEED Techno... | ASPEED Graphics Family               | 8     | ast        | [4158CB76EF](<Server/ASUSTek Computer/RS400/RS400-E8-PS2-F/B939D9497146/GENTOO-2.7/5.10.14-HARDENED1/X86_64/4158CB76EF>) |
| 1a03:2000 | 1043:86ed | ASPEED Techno... | ASPEED Graphics Family               | 8     | ast        | [3035FDAD91](<Server/ASUSTek Computer/WS-C621E-SAGE/WS-C621E-SAGE Series/E86AFFE0F80D/KUBUNTU-20.04/5.4.0-97-GENERIC/X86_64/3035FDAD91>) |
| 1a03:2000 | 1458:1000 | ASPEED Techno... | ASPEED Graphics Family               | 8     | ast        | [6D2EE30F72](<Server/Gigabyte Technology/MZ71/MZ71-CE0-00/74E7E16574F5/UBUNTU-MATE-20.04/5.11.0-43-GENERIC/X86_64/6D2EE30F72>) |
| 1a03:2000 | 15d9:0801 | ASPEED Techno... | ASPEED Graphics Family               | 8     | ast        | [84ED224F36](<Server/Supermicro/X10/X10SLL-F/34D1B7FAB08F/ALPINE-3.12.7/5.4.111-0-LTS/X86_64/84ED224F36>) |
| 1a03:2000 | 15d9:096d | ASPEED Techno... | ASPEED Graphics Family               | 8     | ast        | [2CDAC4454D](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.16.8-051608-GENERIC/X86_64/2CDAC4454D>) |
| 1002:9874 | 1002:1871 | AMD              | Wani [Radeon R5/R6/R7 Graphics]      | 7     | amdgpu     | [F7739E263E](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/05C34CB58FDD/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/F7739E263E>) |
| 102b:0532 | 1028:04de | Matrox Electr... | MGA G200eW WPCM450                   | 7     | mgag200    | [D95EA030FF](<Server/Dell/PowerEdge/PowerEdge T110 II/2E5934354FEE/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/D95EA030FF>) |
| 102b:0534 | 1028:04fa | Matrox Electr... | G200eR2                              | 7     | mgag200    | [ABE0B5613A](<Server/Dell/PowerEdge/PowerEdge T320/EB32D3263597/UBUNTU-20.04/5.4.0-74-GENERIC/X86_64/ABE0B5613A>) |
| 102b:0538 | 1590:00e4 | Matrox Electr... | MGA G200eH3                          | 7     | mgag200    | [7AB4F05613](<Server/HPE/ProLiant/ProLiant DL360 Gen10/4443D3087423/UBUNTU-18.04/4.15.0-135-GENERIC/X86_64/7AB4F05613>) |
| 10de:128b | 1462:8c93 | Nvidia           | GK208B [GeForce GT 710]              | 7     | nouveau    | [4DC142D672](<Server/Supermicro/X9/X9DRD-7LN4F-X9DRD-EF/A67A7A3867A4/UBUNTU-20.04/5.4.0-81-GENERIC/X86_64/4DC142D672>) |
| 1a03:2000 | 15d9:0831 | ASPEED Techno... | ASPEED Graphics Family               | 7     | ast        | [58E86F0E34](<Server/Supermicro/Super/Super Server/BD4C9B6F043B/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/58E86F0E34>) |
| 102b:0532 | 1028:028c | Matrox Electr... | MGA G200eW WPCM450                   | 6     | mgag200    | [F46A021C88](<Server/Dell/PowerEdge/PowerEdge R410/9BE3F9CEE048/LUBUNTU-20.04/5.4.0-83-GENERIC/X86_64/F46A021C88>) |
| 102b:0532 | 15d9:0001 | Matrox Electr... | MGA G200eW WPCM450                   | 6     | mgag200    | [AFA93003E2](<Server/Supermicro/X8/X8DT3/B53F2D96B315/DEBIAN-10/5.4.128-1-PVE/X86_64/AFA93003E2>) |
| 102b:0532 | 15d9:ab11 | Matrox Electr... | MGA G200eW WPCM450                   | 6     | mgag200    | [D5563E325C](<Server/Supermicro/H8/H8QG6/58E82626C3C5/KUBUNTU-20.04/5.4.0-73-GENERIC/X86_64/D5563E325C>) |
| 102b:0532 | 15d9:bc11 | Matrox Electr... | MGA G200eW WPCM450                   | 6     | mgag200    | [AA1C79AB75](<Server/Supermicro/H8/H8DG6-H8DGi/49F6AA867D33/ARCH/5.16.5-ARCH1-1/X86_64/AA1C79AB75>) |
| 102b:0534 | 1028:0601 | Matrox Electr... | G200eR2                              | 6     | mgag200    | [F90168C69D](<Server/Dell/PowerEdge/PowerEdge R630/DBDF919E8981/RHEL-7/3.10.0-1127.19.1.EL7.YAHOO.20200821.63.X86_64/X86_64/F90168C69D>) |
| 102b:0534 | 1028:06a5 | Matrox Electr... | G200eR2                              | 6     | mgag200    | [C8D2D41009](<Server/Dell/PowerEdge/PowerEdge R230/5B911C7AB359/UBUNTU-20.04/5.4.0-97-GENERIC/X86_64/C8D2D41009>) |
| 10de:128b | 196e:118b | Nvidia           | GK208B [GeForce GT 710]              | 6     | nouveau    | [3A68279F78](<Server/IBM/System/System x3650 -[7979AC1]-/D68394872CF7/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/3A68279F78>) |
| 1a03:2000 | 1043:84eb | ASPEED Techno... | ASPEED Graphics Family               | 6     | ast        | [26BEB89FBE](<Server/ASUSTek Computer/P9D-I/P9D-I Series/5316A66710E3/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/26BEB89FBE>) |
| 1002:515e | 1028:01b2 | AMD              | ES1000                               | 5     | radeon     | [4CC109A2AB](<Server/Dell/PowerEdge/PowerEdge 2950/819CF07A677E/ZORIN-16/5.11.0-43-GENERIC/X86_64/4CC109A2AB>) |
| 102b:0532 | 1028:02f1 | Matrox Electr... | MGA G200eW WPCM450                   | 5     | mgag200    | [CD7187DD0B](<Server/Dell/PowerEdge/PowerEdge R510/3788D55886C4/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/CD7187DD0B>) |
| 102b:0532 | 1028:0444 | Matrox Electr... | MGA G200eW WPCM450                   | 5     | mgag200    | [FBE32ACA1D](<Server/Dell/PowerEdge/PowerEdge R815/D106BA160A7C/DEBIAN-UNSTABLE/5.16.0-RC8-AMD64/X86_64/FBE32ACA1D>) |
| 102b:0532 | 1028:04dd | Matrox Electr... | MGA G200eW WPCM450                   | 5     | mgag200    | [E0E68EFC2F](<Server/Dell/PowerEdge/PowerEdge R210 II/D6DEF28F8714/UBUNTU-18.04/4.15.0-109-GENERIC/X86_64/E0E68EFC2F>) |
| 102b:0532 | 15d9:0400 | Matrox Electr... | MGA G200eW WPCM450                   | 5     | mgag200    | [AD4ABE60CD](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/03637143A526/XUBUNTU-20.04/5.11.0-37-GENERIC/X86_64/AD4ABE60CD>) |
| 102b:0534 | 1028:0600 | Matrox Electr... | G200eR2                              | 5     | mgag200    | [3E58F60E33](<Server/Dell/PowerEdge/PowerEdge R730/B08360FD5D56/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/3E58F60E33>) |
| 102b:0536 | 1028:0715 | Matrox Electr... | Integrated Matrox G200eW3 Graphic... | 5     | mgag200    | [FCC6D41C03](<Server/Dell/PowerEdge/PowerEdge R740/203EBCE27AC6/CENTOS-7/3.10.0-1160.45.1.EL7.X86_64/X86_64/FCC6D41C03>) |
| 1a03:2000 | 1043:8544 | ASPEED Techno... | ASPEED Graphics Family               | 5     | ast        | [9FBB87A829](<Server/VIT/NP3020/NP3020M3/6DA8E8BE5005/DEBIAN-10/4.19.0-18-AMD64/X86_64/9FBB87A829>) |
| 1a03:2000 | 15d9:086d | ASPEED Techno... | ASPEED Graphics Family               | 5     | ast        | [12DB3650F6](<Server/Supermicro/Super/Super Server/51A56BB4E7AB/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/12DB3650F6>) |
| 1a03:2000 | 15d9:0921 | ASPEED Techno... | ASPEED Graphics Family               | 5     | ast        | [E60EC405AF](<Server/Supermicro/Super/Super Server/F5F261808B48/GENTOO-2.6/5.15.19-GENTOO/X86_64/E60EC405AF>) |
| 1a03:2000 | 15d9:0964 | ASPEED Techno... | ASPEED Graphics Family               | 5     | ast        | [2BB4102B1C](<Server/Supermicro/Super/Super Server/45717F18B5CF/CENTOS-8/4.18.0-240.22.1.EL8_3.X86_64/X86_64/2BB4102B1C>) |
| 1a03:2000 | 15d9:0981 | ASPEED Techno... | ASPEED Graphics Family               | 5     | ast        | [1A73C74FBB](<Server/Supermicro/Super/Super Server/909986EADB14/UBUNTU-21.04/5.11.0-38-GENERIC/X86_64/1A73C74FBB>) |

### Input device controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1102:7003 | 1102:0040 | Creative Labs    | SB Audigy Game Port                  | 2     | Emu10k1... | [F879FD97F7](<Server/TYAN Computer/S/S2895/4B5DFCDB09B6/LINUXMINT-20/5.4.0-58-GENERIC/X86_64/F879FD97F7>) |
| 1102:7002 | 1102:0020 | Creative Labs    | SB Live! Game Port                   | 1     | emu10k1_gp | [80DC2F8936](<Server/Supermicro/Super/Super Server/A9CFB59D8528/OPENSUSE-LEAP-42.1/4.1.39-56-DEFAULT/X86_64/80DC2F8936>) |
| 1102:7003 | 1102:0060 | Creative Labs    | SB Audigy Game Port                  | 1     | emu10k1_gp | [D471D2B279](<Server/Wortmann AG/TERRA/TERRA Server/DAE4E032512D/UBUNTU-20.04/5.4.0-33-GENERIC/X86_64/D471D2B279>) |

### Iommu (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1481 | 1022:1481 | AMD              | Starship/Matisse IOMMU               | 10    |            | [2BB4102B1C](<Server/Supermicro/Super/Super Server/45717F18B5CF/CENTOS-8/4.18.0-240.22.1.EL8_3.X86_64/X86_64/2BB4102B1C>) |
| 1022:1481 | 1458:1000 | AMD              | Starship/Matisse IOMMU               | 5     |            | [6D2EE30F72](<Server/Gigabyte Technology/MZ71/MZ71-CE0-00/74E7E16574F5/UBUNTU-MATE-20.04/5.11.0-43-GENERIC/X86_64/6D2EE30F72>) |
| 1002:5a23 | 1028:0444 | AMD              | RD890S/RD990 I/O Memory Managemen... | 3     |            | [FBE32ACA1D](<Server/Dell/PowerEdge/PowerEdge R815/D106BA160A7C/DEBIAN-UNSTABLE/5.16.0-RC8-AMD64/X86_64/FBE32ACA1D>) |
| 1022:1631 | 1022:1631 | AMD              | Renoir/Cezanne IOMMU                 | 3     |            | [0AB1FF409B](<Server/BESSTAR Tech/X/X500/A95AE61E36B4/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/0AB1FF409B>) |
| 1022:1481 | 1028:08fc | AMD              | Starship/Matisse IOMMU               | 2     |            | [85004F427A](<Server/Dell/PowerEdge/PowerEdge R6515/591EBA0E828F/SLACKWARE-15.0/5.15.19/X86_64/85004F427A>) |
| 1022:1481 | 1028:08ff | AMD              | Starship/Matisse IOMMU               | 2     |            | [A35E7D3EB0](<Server/Dell/PowerEdge/PowerEdge R7525/6B51CAA01B7C/UBUNTU-20.04/5.4.0-74-GENERIC/X86_64/A35E7D3EB0>) |
| 1022:164f | 1022:164f | AMD              | Milan IOMMU                          | 2     |            | [4798AC1234](<Server/Supermicro/Super/Super Server/4CD86DE2F12F/UBUNTU-20.04/5.4.0-84-GENERIC/X86_64/4798AC1234>) |
| 8086:1f16 | 15d9:0820 | Intel            | Atom processor C2000 RCEC            | 2     |            | [A9E1A5906C](<Server/Supermicro/A1/A1SAM-2550F/B9FD41A2E4E7/MANJARO-21.2.3/5.15.21-1-MANJARO/X86_64/A9E1A5906C>) |
| 1002:5a23 | 103c:1762 | AMD              | RD890S/RD990 I/O Memory Managemen... | 1     |            | [E60DA0D6CE](<Server/Hewlett-Packard/ProLiant/ProLiant DL385p Gen8/EAADD5928698/UBUNTU-20.04/5.4.0-37-GENERIC/X86_64/E60DA0D6CE>) |
| 1002:5a23 | 103c:3324 | AMD              | RD890S/RD990 I/O Memory Managemen... | 1     |            | [7CE46A749E](<Server/Hewlett-Packard/ProLiant/ProLiant DL165 G7/1273A822F849/UBUNTU-19.04/5.0.0-20-LOWLATENCY/X86_64/7CE46A749E>) |
| 1022:1451 | 1028:07f9 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 1     |            | [8F7FF50C55](<Server/Dell/PowerEdge/PowerEdge R7425/EEF1E1F22650/OPENSUSE-LEAP-15.1/4.12.14-LP151.28.13-DEFAULT/X86_64/8F7FF50C55>) |
| 1022:1481 | 1028:08fd | AMD              | Starship/Matisse IOMMU               | 1     |            | [F3CBAC183E](<Server/Dell/PowerEdge/PowerEdge R7515/9A7A286BD3E1/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/F3CBAC183E>) |
| 1022:164f | 1028:08fc | AMD              | Milan IOMMU                          | 1     |            | [9320E12A9A](<Server/Dell/PowerEdge/PowerEdge R6515/38E4D8545292/DEBIAN-11/5.10.0-8-AMD64/X86_64/9320E12A9A>) |
| 1022:164f | 1028:08ff | AMD              | Milan IOMMU                          | 1     |            | [B7AC531BF5](<Server/Dell/PowerEdge/PowerEdge R7525/3F409CE3A366/RHEL-8///B7AC531BF5>) |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 103c:3302 | 103c:3305 | Hewlett-Packard  | Integrated Lights-Out Standard KC... | 28    | ipmi_si    | [24D4B5B8DB](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/9A14972DB3E8/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/24D4B5B8DB>) |

### Isdn adapter (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1244:0a00 | 1244:0a00 | AVM              | A1 ISDN [Fritz]                      | 1     | fcpci      | [750A124EF3](<Server/Wortmann AG/TERRA_PC/TERRA_PC/8340D78F7FD7/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/750A124EF3>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a1a1 | 8086:7270 | Intel            | C620 Series Chipset Family Power ... | 20    |            | [73518731A1](<Server/Supermicro/X11/X11DPi-N/6D6FD3049691/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/73518731A1>) |
| 8086:a1a1 | 8086:35ce | Intel            | C620 Series Chipset Family Power ... | 19    |            | [36C4ACAC2D](<Server/Intel/S2600/S2600WFT/8DC9639F1DBF/ROCKY-8.4/4.18.0-305.10.2.EL8_4.X86_64/X86_64/36C4ACAC2D>) |
| 8086:a36f | 8086:7270 | Intel            | Cannon Lake PCH Shared SRAM          | 16    |            | [B850CD60F6](<Server/Acord-92/PCplus/PCplus T600-C246/CC2E95E1BC69/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B850CD60F6>) |
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 13    |            | [7C1FA00B21](<Server/Intel/S1200/S1200SP/4B4C83B49974/CENTOS-7/4.4.241-1.EL7.ELREPO.X86_64/X86_64/7C1FA00B21>) |
| 8086:a1a1 | 1028:073a | Intel            | C620 Series Chipset Family Power ... | 11    |            | [2E5507B849](<Server/Dell/Precision/Precision 7920 Tower/6DBFD1DBD45A/UBUNTU-20.04/5.10.0-1055-OEM/X86_64/2E5507B849>) |
| 8086:a1a1 | 1043:871e | Intel            | C620 Series Chipset Family Power ... | 9     |            | [3035FDAD91](<Server/ASUSTek Computer/WS-C621E-SAGE/WS-C621E-SAGE Series/E86AFFE0F80D/KUBUNTU-20.04/5.4.0-97-GENERIC/X86_64/3035FDAD91>) |
| 8086:a1a1 | 15d9:096d | Intel            | C620 Series Chipset Family Power ... | 8     |            | [2CDAC4454D](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.16.8-051608-GENERIC/X86_64/2CDAC4454D>) |
| 8086:a1a1 | 1590:00eb | Intel            | C620 Series Chipset Family Power ... | 7     |            | [7AB4F05613](<Server/HPE/ProLiant/ProLiant DL360 Gen10/4443D3087423/UBUNTU-18.04/4.15.0-135-GENERIC/X86_64/7AB4F05613>) |
| 8086:a1a1 | 17aa:7808 | Intel            | C620 Series Chipset Family Power ... | 7     |            | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 8086:a36f |           | Intel            | Cannon Lake PCH Shared SRAM          | 7     |            | [5011114071](<Server/Dell/PowerEdge/PowerEdge R240/3378DCFA2CDA/DEBIAN-11/5.13.19-4-PVE/X86_64/5011114071>) |
| 8086:a121 | 1028:06a5 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     |            | [C8D2D41009](<Server/Dell/PowerEdge/PowerEdge R230/5B911C7AB359/UBUNTU-20.04/5.4.0-97-GENERIC/X86_64/C8D2D41009>) |
| 8086:a121 | 15d9:0895 | Intel            | 100 Series/C230 Series Chipset Fa... | 5     |            | [79E6EAFC82](<Server/Supermicro/Super/Super Server/EA582B67D89D/DEBIAN-11/5.13.19-2-PVE/X86_64/79E6EAFC82>) |
| 8086:a1a1 | 1028:0715 | Intel            | C620 Series Chipset Family Power ... | 5     |            | [FCC6D41C03](<Server/Dell/PowerEdge/PowerEdge R740/203EBCE27AC6/CENTOS-7/3.10.0-1160.45.1.EL7.X86_64/X86_64/FCC6D41C03>) |
| 8086:a1a1 | 1028:0739 | Intel            | C620 Series Chipset Family Power ... | 5     |            | [5A2FCB7023](<Server/Dell/Precision/Precision 7820 Tower/8AAB146ACE98/LINUXMINT-20/5.4.0-91-GENERIC/X86_64/5A2FCB7023>) |
| 8086:a1a1 | 15d9:0981 | Intel            | C620 Series Chipset Family Power ... | 5     |            | [1A73C74FBB](<Server/Supermicro/Super/Super Server/909986EADB14/UBUNTU-21.04/5.11.0-38-GENERIC/X86_64/1A73C74FBB>) |
| 8086:a1a1 | 1849:a1a1 | Intel            | C620 Series Chipset Family Power ... | 5     |            | [BAA2C57359](<Server/ASRockRack/EPC621/EPC621D8A/5678CB93815F/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/BAA2C57359>) |
| 8086:a36f | 8086:a36f | Intel            | Cannon Lake PCH Shared SRAM          | 5     |            | [4A717F6348](<Server/Neousys Technology/Nuvo-8208GC/Nuvo-8208GC Series/02E83AA0CBB0/GENTOO-2.8/5.16.5-GENTOO/X86_64/4A717F6348>) |
| 1590:005f | 1590:005f | Hewlett-Packard  | Memory controller                    | 4     |            | [3A14AEA222](<Server/Hewlett-Packard/ProLiant/ProLiant DL320e Gen8/C247AB0902A1/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/3A14AEA222>) |
| 8086:a121 | 15d9:089a | Intel            | 100 Series/C230 Series Chipset Fa... | 4     |            | [E8634FF947](<Server/Supermicro/Super/Super Server/0EC007042E2B/DEBIAN-9/4.15.18-12-PVE/X86_64/E8634FF947>) |
| 8086:a1a1 | 103c:81c7 | Intel            | C620 Series Chipset Family Power ... | 4     |            | [5299B4DA87](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/68BC2092E093/UBUNTU-18.04/5.4.0-74-GENERIC/X86_64/5299B4DA87>) |
| 8086:a1a1 | 15d9:0953 | Intel            | C620 Series Chipset Family Power ... | 4     |            | [A76BB2E30D](<Server/Supermicro/SYS-5029/SYS-5029P-WTR/2D889DFAC2FF/ROCKY-8.5/4.18.0-348.12.2.EL8_5.X86_64/X86_64/A76BB2E30D>) |
| 1912:0011 |           | Renesas Techn... | SH7757 PCIe End-Point [PBI]          | 3     |            | [B689A1C943](<Server/Dell/PowerEdge/PowerEdge R220/2869EAF432EF/DEBIAN-11/5.10.0-9-AMD64/X86_64/B689A1C943>) |
| 8086:a1a1 | 1028:0716 | Intel            | C620 Series Chipset Family Power ... | 3     |            | [E752263E49](<Server/Dell/PowerEdge/PowerEdge R640/1917FF5F0757/CENTOS-7/3.10.0-957.21.3.EL7.X86_64/X86_64/E752263E49>) |
| 8086:a1a1 | 1028:0718 | Intel            | C620 Series Chipset Family Power ... | 3     |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:a1a1 | 103c:81c6 | Intel            | C620 Series Chipset Family Power ... | 3     |            | [679871CFEC](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/E621F1A07D2C/UBUNTU-20.04/5.4.0-84-GENERIC/X86_64/679871CFEC>) |
| 8086:a1a1 | 15d9:095d | Intel            | C620 Series Chipset Family Power ... | 3     |            | [C682299C13](<Server/Supermicro/X11/X11-SPM-TF/17F67170A1AB/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/C682299C13>) |
| 8086:a1a1 | 17aa:1038 | Intel            | C620 Series Chipset Family Power ... | 3     |            | [5658A2FB98](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC003KUS/DD1C32AB7122/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/5658A2FB98>) |
| 10de:0369 | 1462:cb84 | Nvidia           | MCP55 Memory Controller              | 2     |            | [B8300AFB35](<Server/MSI/MCP/MCP55/8728FA454DA7/UBUNTU-20.04/5.4.0-56-GENERIC/X86_64/B8300AFB35>) |
| 8086:19de | 15d9:0969 | Intel            | Atom Processor C3000 Series Power... | 2     |            | [40E07B4DAD](<Server/Supermicro/Super/Super Server/73152EF104BB/MANJARO-21.0.2/5.11.14-1-MANJARO/X86_64/40E07B4DAD>) |
| 8086:1bce | 8086:7270 | Intel            | RAM memory                           | 2     |            | [AEAD99F55D](<Server/Intel/AST2600/AST2600EVB/BE9050B3ECF3/CENTOS-8/5.12.0-0.RC2.33.EL8.X86_64+SPR/X86_64/AEAD99F55D>) |
| 8086:a121 | 15d9:088b | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [C0E1C15247](<Server/Supermicro/C7/C7Z170-M/5D50FA33A353/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/C0E1C15247>) |
| 8086:a121 | 15d9:089f | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [ECB9EC0D34](<Server/Supermicro/Super/Super Server/D5D09C37A0C7/ARCO-ROLLING/5.15.19-XANMOD1-TT-1/X86_64/ECB9EC0D34>) |
| 8086:a121 | 1734:1222 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [CDED98E996](<Server/Fujitsu/PRIMERGY/PRIMERGY TX1310 M3/35A0293EF01F/FEDORA-34/5.11.12-300.FC34.X86_64/X86_64/CDED98E996>) |
| 8086:a121 | 8086:a121 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [C4D59010A1](<Server/ASUSTek Computer/P10S-I/P10S-I Series/18373715D587/MANJARO-20.1.2/5.8.16-2-MANJARO/X86_64/C4D59010A1>) |
| 8086:a1a1 | 1028:0737 | Intel            | C620 Series Chipset Family Power ... | 2     |            | [DF9A63BE43](<Server/Dell/PowerEdge/PowerEdge R740xd/62F4A9812E0F/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/DF9A63BE43>) |
| 8086:a1a1 | 1028:07c9 | Intel            | C620 Series Chipset Family Power ... | 2     |            | [4B1DC70687](<Server/Dell/PowerEdge/PowerEdge R440/F8F03AC45B85/DEBIAN-UNSTABLE/5.16.0-3-AMD64/X86_64/4B1DC70687>) |
| 8086:a1a1 | 1028:07cb | Intel            | C620 Series Chipset Family Power ... | 2     |            | [FE43558C7A](<Server/Dell/PowerEdge/PowerEdge T440/B0AF20400020/UBUNTU-20.04/5.4.0-88-GENERIC/X86_64/FE43558C7A>) |
| 8086:a1a1 | 1028:07e5 | Intel            | C620 Series Chipset Family Power ... | 2     |            | [4C88B2E09B](<Server/Dell/PowerEdge/PowerEdge T640/56D8A440BA81/UBUNTU-18.04/5.4.0-47-GENERIC/X86_64/4C88B2E09B>) |
| 8086:a1a1 | 15d9:091c | Intel            | C620 Series Chipset Family Power ... | 2     |            | [748FB8054B](<Server/Supermicro/SYS-1029/SYS-1029U-TR25M/29100DD815C0/DEBIAN-10/4.19.0-9-AMD64/X86_64/748FB8054B>) |
| 8086:a1a1 | 15d9:0941 | Intel            | C620 Series Chipset Family Power ... | 2     |            | [C619DB847B](<Server/Supermicro/Super/Super Server/FC9F112D0567/XUBUNTU-18.04/4.15.0-112-LOWLATENCY/X86_64/C619DB847B>) |
| 8086:a1a1 | 15d9:0986 | Intel            | C620 Series Chipset Family Power ... | 2     |            | [9A0AAAD7ED](<Server/Prime Computer/Server/Server Pro/289FB0C396A8/UBUNTU-20.04/5.4.0-99-GENERIC/X86_64/9A0AAAD7ED>) |
| 8086:a1a1 | 17aa:7800 | Intel            | C620 Series Chipset Family Power ... | 2     |            | [928EE22E71](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 -[7X06CTO1WW]-/5D8AB08CFEB3/CENTOS-7/3.10.0-1160.21.1.EL7.X86_64/X86_64/928EE22E71>) |
| 10de:005e | 10f1:2891 | Nvidia           | CK804 Memory Controller              | 1     |            | [64251B3F2A](<Server/TYAN Computer/S/S4885/58FA2062A619/KUBUNTU-20.04/5.4.0-47-LOWLATENCY/X86_64/64251B3F2A>) |
| 10de:005e | 10f1:2895 | Nvidia           | CK804 Memory Controller              | 1     |            | [768571B831](<Server/TYAN Computer/S/S2895/4B5DFCDB09B6/LINUXMINT-20/5.4.0-58-GENERIC/X86_64/768571B831>) |
| 10de:00d3 | 10f1:2891 | Nvidia           | CK804 Memory Controller              | 1     |            | [64251B3F2A](<Server/TYAN Computer/S/S4885/58FA2062A619/KUBUNTU-20.04/5.4.0-47-LOWLATENCY/X86_64/64251B3F2A>) |
| 10de:00d3 | 10f1:2895 | Nvidia           | CK804 Memory Controller              | 1     |            | [768571B831](<Server/TYAN Computer/S/S2895/4B5DFCDB09B6/LINUXMINT-20/5.4.0-58-GENERIC/X86_64/768571B831>) |
| 10de:0361 | 10f1:2915 | Nvidia           | MCP55 LPC Bridge                     | 1     |            | [0D3D065311](<Server/TYAN Computer/MCP/MCP55/DB4D10F83692/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/0D3D065311>) |
| 10de:0369 | 108e:534b | Nvidia           | MCP55 Memory Controller              | 1     |            | [E54A36A0C4](<Server/Sun Microsystems/Sun/Sun Fire X2200 M2/CD7CD7D1524A/CENTOS-7/3.10.0-1160.25.1.EL7.X86_64/X86_64/E54A36A0C4>) |
| 10de:0369 | 108e:534d | Nvidia           | MCP55 Memory Controller              | 1     |            | [1F35F79302](<Server/Sun Microsystems/Ultra20/Ultra20 M2/23D902832E84/ROSA-2014.1/4.1.15-NRJ-DESKTOP-1ROSA-I586/I686/1F35F79302>) |
| 10de:0369 | 10f1:2915 | Nvidia           | MCP55 Memory Controller              | 1     |            | [0D3D065311](<Server/TYAN Computer/MCP/MCP55/DB4D10F83692/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/0D3D065311>) |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15e2 | 1022:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 3     | snd_pci... | [0AB1FF409B](<Server/BESSTAR Tech/X/X500/A95AE61E36B4/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/0AB1FF409B>) |
| 109e:0878 |           | Brooktree        | Bt878 Audio Capture                  | 1     | bt878      | [B55D1DAEA5](<Server/Intel/S5500/S5500BC/EB1E1FCFB3A4/UBUNTU-MATE-19.10/5.3.0-51-GENERIC/X86_64/B55D1DAEA5>) |
| 109e:0878 | 0070:ff04 | Brooktree        | Bt878 Audio Capture                  | 1     |            | [2C877CF870](<Server/Hewlett-Packard/ProLiant/ProLiant DL140 G2/7851FB932D49/ARCH/4.18.12-ARCH1-1-ARCH/X86_64/2C877CF870>) |
| 109e:0878 | 800a:763d | Brooktree        | Bt878 Audio Capture                  | 1     |            | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 109e:0878 | 800b:763d | Brooktree        | Bt878 Audio Capture                  | 1     |            | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 109e:0878 | 800c:763d | Brooktree        | Bt878 Audio Capture                  | 1     |            | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 109e:0878 | 800d:763d | Brooktree        | Bt878 Audio Capture                  | 1     |            | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 1131:7164 | 0070:8851 | Philips Semic... | SAA7164                              | 1     | saa7164    | [019914CC29](<Server/Supermicro/X10/X10SAE/6D8BBA911035/GENTOO-2.7/5.13.12-GENTOO/X86_64/019914CC29>) |
| 1797:6869 |           | Intersil Tech... | C968 PCIe SD Capture                 | 1     | avc8000    | [375EC8881D](<Server/Neousys Technology/Nuvo-8208GC/Nuvo-8208GC Series/78293157040C/UBUNTU-18.04/5.4.0-53-GENERIC/X86_64/375EC8881D>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14e4:1639 | 103c:7055 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 35    | bnx2       | [909B88F852](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/BE425EE16F85/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/909B88F852>) |
| 14e4:1657 | 103c:169d | Broadcom         | NetXtreme BCM5719 Gigabit Etherne... | 24    | tg3        | [1172390E59](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/2267C96ADE00/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/1172390E59>) |
| 14e4:165f | 1028:1f5b | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 24    | tg3        | [7BF19C1CD2](<Server/Dell/PowerEdge/PowerEdge R720/2489ED365DE4/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/7BF19C1CD2>) |
| 8086:1572 | 8086:0000 | Intel            | Ethernet Controller X710 for 10Gb... | 22    | i40e       | [928EE22E71](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 -[7X06CTO1WW]-/5D8AB08CFEB3/CENTOS-7/3.10.0-1160.21.1.EL7.X86_64/X86_64/928EE22E71>) |
| 8086:37d2 | 15d9:37d2 | Intel            | Ethernet Connection X722 for 10GB... | 18    | i40e       | [9A0AAAD7ED](<Server/Prime Computer/Server/Server Pro/289FB0C396A8/UBUNTU-20.04/5.4.0-99-GENERIC/X86_64/9A0AAAD7ED>) |
| 14e4:1639 | 1028:0235 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 17    | bnx2       | [27639679E2](<Server/Dell/PowerEdge/PowerEdge R710/ACC1A39EDD24/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/27639679E2>) |
| 8086:15b9 | 8086:0000 | Intel            | Ethernet Connection (3) I219-LM      | 17    | e1000e     | [4391DFF8D2](<Server/Others/Others/Others/29E67FFE5E37/UBUNTU-18.04/4.18.0-20-GENERIC/X86_64/4391DFF8D2>) |
| 14e4:1657 | 103c:22be | Broadcom         | NetXtreme BCM5719 Gigabit Etherne... | 15    | tg3        | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 14e4:164c | 103c:7038 | Broadcom Limited | NetXtreme II BCM5708 Gigabit Ethe... | 14    | bnx2       | [24D4B5B8DB](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/9A14972DB3E8/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/24D4B5B8DB>) |
| 8086:153a | 15d9:153a | Intel            | Ethernet Connection I217-LM          | 14    | e1000e     | [84ED224F36](<Server/Supermicro/X10/X10SLL-F/34D1B7FAB08F/ALPINE-3.12.7/5.4.111-0-LTS/X86_64/84ED224F36>) |
| 14e4:1639 | 1028:0236 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 11    | bnx2       | [02E5C56A80](<Server/Dell/PowerEdge/PowerEdge R610/D7D0CF9B35C0/ROCKY-8.5/4.18.0-348.12.2.EL8_5.X86_64/X86_64/02E5C56A80>) |
| 8086:1563 | 15d9:1563 | Intel            | Ethernet Controller 10G X550T        | 11    | ixgbe      | [7A720A4E41](<Server/Supermicro/Super/Super Server/06E41BB3C6CC/ROCKY-8.5/4.18.0-348.12.2.EL8_5.X86_64/X86_64/7A720A4E41>) |
| 8086:15b9 | 1028:073a | Intel            | Ethernet Connection (3) I219-LM      | 11    | e1000e     | [2E5507B849](<Server/Dell/Precision/Precision 7920 Tower/6DBFD1DBD45A/UBUNTU-20.04/5.10.0-1055-OEM/X86_64/2E5507B849>) |
| 14e4:163b | 1028:02a4 | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 10    | bnx2       | [2CAE1B1D80](<Server/Dell/PowerEdge/PowerEdge T310/1B407A78D4C5/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/2CAE1B1D80>) |
| 8086:10fb | 8086:0003 | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 10    | ixgbe      | [882EA8E25E](<Server/IBM/System/System x3250 M3 -[4252K4G]-/76E08604766E/DEBIAN-10/5.4.106-1-PVE/X86_64/882EA8E25E>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 9     | r8169      | [0AB1FF409B](<Server/BESSTAR Tech/X/X500/A95AE61E36B4/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/0AB1FF409B>) |
| 14e4:165f | 1028:04fa | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 9     | tg3        | [ABE0B5613A](<Server/Dell/PowerEdge/PowerEdge T320/EB32D3263597/UBUNTU-20.04/5.4.0-74-GENERIC/X86_64/ABE0B5613A>) |
| 8086:10fb | 108e:7b11 | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 9     | ixgbe      | [5A96F790B1](<Server/Supermicro/Super/Super Server/022F96D5DAA8/CENTOS-7/3.10.0-862.14.4.EL7.X86_64/X86_64/5A96F790B1>) |
| 8086:1521 | 103c:3380 | Intel            | I350 Gigabit Network Connection      | 9     | igb        | [1E7A730FCC](<Server/Hewlett-Packard/ProLiant/ProLiant DL380e Gen8/1BC24BA0C1ED/ACRONIS-CYBER-INFRASTRUCTURE-3.5.4/3.10.0-1062.4.2.VZ7.116.7/X86_64/1E7A730FCC>) |
| 8086:1528 | 15d9:1528 | Intel            | Ethernet Controller 10-Gigabit X5... | 9     | ixgbe      | [50AEBE4B28](<Server/Supermicro/SSG-6048/SSG-6048R-E1CR24H/8A7A52EA4807/CENTOS-8/4.18.0-348.2.1.EL8_5.X86_64/X86_64/50AEBE4B28>) |
| 14e4:163b | 1028:028c | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 8     | bnx2       | [24358FA4BD](<Server/Dell/PowerEdge/PowerEdge R410/C25F044F8862/FEDORA-34/5.14.11-200.FC34.X86_64/X86_64/24358FA4BD>) |
| 14e4:165a | 1028:04de | Broadcom         | NetXtreme BCM5722 Gigabit Etherne... | 8     | tg3        | [D95EA030FF](<Server/Dell/PowerEdge/PowerEdge T110 II/2E5934354FEE/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/D95EA030FF>) |
| 14e4:165f | 103c:22e8 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 8     | tg3        | [F7739E263E](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/05C34CB58FDD/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/F7739E263E>) |
| 8086:15b7 | 15d9:15b7 | Intel            | Ethernet Connection (2) I219-LM      | 8     | e1000e     | [ECB9EC0D34](<Server/Supermicro/Super/Super Server/D5D09C37A0C7/ARCO-ROLLING/5.15.19-XANMOD1-TT-1/X86_64/ECB9EC0D34>) |
| 8086:37d1 | 15d9:37d1 | Intel            | Ethernet Connection X722 for 1GbE    | 8     | i40e       | [73518731A1](<Server/Supermicro/X11/X11DPi-N/6D6FD3049691/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/73518731A1>) |
| 14e4:1639 | 1014:03a9 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 7     | bnx2       | [76A0EBBFC4](<Server/IBM/System/System x3550 M3 -[7944KAG]-/E6F6F92CA768/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/76A0EBBFC4>) |
| 8086:1076 | 8086:34d0 | Intel            | 82541GI Gigabit Ethernet Controller  | 7     | e1000      | [FC38CA11F5](<Server/Intel/S3210/S3210SH/5BCC9327A8D8/UBUNTU-20.04/5.8.0-53-GENERIC/X86_64/FC38CA11F5>) |
| 8086:1572 | 8086:0001 | Intel            | Ethernet Controller X710 for 10Gb... | 7     | i40e       | [928EE22E71](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 -[7X06CTO1WW]-/5D8AB08CFEB3/CENTOS-7/3.10.0-1160.21.1.EL7.X86_64/X86_64/928EE22E71>) |
| 8086:1572 | 8086:000a | Intel            | Ethernet Controller X710 for 10Gb... | 7     | i40e       | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 8086:37d1 | 17aa:4020 | Intel            | Ethernet Connection X722 for 1GbE    | 7     | i40e       | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 8086:37d2 | 17aa:4020 | Intel            | Ethernet Connection X722 for 10GB... | 7     | i40e       | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 14e4:163b | 1028:02f1 | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 6     | bnx2       | [CD7187DD0B](<Server/Dell/PowerEdge/PowerEdge R510/3788D55886C4/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/CD7187DD0B>) |
| 14e4:164c | 1028:01b2 | Broadcom         | NetXtreme II BCM5708 Gigabit Ethe... | 6     | bnx2       | [4CC109A2AB](<Server/Dell/PowerEdge/PowerEdge 2950/819CF07A677E/ZORIN-16/5.11.0-43-GENERIC/X86_64/4CC109A2AB>) |
| 14e4:165f | 1028:06a5 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 6     | tg3        | [C8D2D41009](<Server/Dell/PowerEdge/PowerEdge R230/5B911C7AB359/UBUNTU-20.04/5.4.0-97-GENERIC/X86_64/C8D2D41009>) |
| 14e4:165f | 14e4:4160 | Broadcom Limited | NetXtreme BCM5720 Gigabit Etherne... | 6     | tg3        | [FCC6D41C03](<Server/Dell/PowerEdge/PowerEdge R740/203EBCE27AC6/CENTOS-7/3.10.0-1160.45.1.EL7.X86_64/X86_64/FCC6D41C03>) |
| 14e4:16d8 | 14e4:4160 | Broadcom Limited | BCM57416 NetXtreme-E Dual-Media 1... | 6     | bnxt_en    | [FCC6D41C03](<Server/Dell/PowerEdge/PowerEdge R740/203EBCE27AC6/CENTOS-7/3.10.0-1160.45.1.EL7.X86_64/X86_64/FCC6D41C03>) |
| 8086:15bb | 15d9:15bb | Intel            | Ethernet Connection (7) I219-LM      | 6     | e1000e     | [B850CD60F6](<Server/Acord-92/PCplus/PCplus T600-C246/CC2E95E1BC69/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B850CD60F6>) |
| 14e4:1639 | 1028:0237 | Broadcom Limited | NetXtreme II BCM5709 Gigabit Ethe... | 5     | bnx2       | [BCDCCDDEC2](<Server/Dell/PowerEdge/PowerEdge T610/EFB372134BAB/ZORIN-16/5.13.0-28-GENERIC/X86_64/BCDCCDDEC2>) |
| 14e4:1639 | 14e4:0906 | Broadcom Limited | NetXtreme II BCM5709 Gigabit Ethe... | 5     | bnx2       | [E36BFCD946](<Server/Dell/PowerEdge/PowerEdge R900/7C692A98BD7B/XCP-NG-8.2.0/4.19.0+1/X86_64/E36BFCD946>) |
| 14e4:1639 | 14e4:1906 | Broadcom Limited | NetXtreme II BCM5709 Gigabit Ethe... | 5     | bnx2       | [E36BFCD946](<Server/Dell/PowerEdge/PowerEdge R900/7C692A98BD7B/XCP-NG-8.2.0/4.19.0+1/X86_64/E36BFCD946>) |
| 14e4:163b | 1028:04dd | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 5     | bnx2       | [E0E68EFC2F](<Server/Dell/PowerEdge/PowerEdge R210 II/D6DEF28F8714/UBUNTU-18.04/4.15.0-109-GENERIC/X86_64/E0E68EFC2F>) |
| 8086:105e | 8086:125e | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 5     | e1000e     | [43C0756BA6](<Server/Fujitsu/PRIMERGY/PRIMERGY RX300 S5/8D101F548ADF/OPENSUSE-LEAP-15.1/4.12.14-LP151.28.91-DEFAULT/X86_64/43C0756BA6>) |
| 8086:1096 | 8086:3476 | Intel            | 80003ES2LAN Gigabit Ethernet Cont... | 5     | e1000e     | [2AEA05D635](<Server/Intel/MP/MP Server/65A44D78DEFA/LINUXMINT-20.2/5.4.0-81-GENERIC/X86_64/2AEA05D635>) |
| 8086:10fb | 8086:000c | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 5     | ixgbe      | [AEAD99F55D](<Server/Intel/AST2600/AST2600EVB/BE9050B3ECF3/CENTOS-8/5.12.0-0.RC2.33.EL8.X86_64+SPR/X86_64/AEAD99F55D>) |
| 8086:1521 | 8086:0001 | Intel            | I350 Gigabit Network Connection      | 5     | igb        | [2CDAC4454D](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.16.8-051608-GENERIC/X86_64/2CDAC4454D>) |
| 8086:15ac | 15d9:15ac | Intel            | Ethernet Connection X552 10 GbE SFP+ | 5     | ixgbe      | [ADC426B903](<Server/Supermicro/SYS-5018/SYS-5018D-FN8T/0EAEDC62B715/ALT-P8/4.9.260-STD-DEF-ALT0.M80P.1/X86_64/ADC426B903>) |
| 8086:15b7 | 8086:0000 | Intel            | Ethernet Connection (2) I219-LM      | 5     | e1000e     | [03F2D30DF2](<Server/HPE/ML10/ML10Gen9/5368299CD3DB/UBUNTU-MATE-21.10/5.13.0-23-GENERIC/X86_64/03F2D30DF2>) |
| 8086:15b9 | 1028:0739 | Intel            | Ethernet Connection (3) I219-LM      | 5     | e1000e     | [5A2FCB7023](<Server/Dell/Precision/Precision 7820 Tower/8AAB146ACE98/LINUXMINT-20/5.4.0-91-GENERIC/X86_64/5A2FCB7023>) |
| 8086:15bb | 8086:0000 | Intel            | Ethernet Connection (7) I219-LM      | 5     | e1000e     | [4A717F6348](<Server/Neousys Technology/Nuvo-8208GC/Nuvo-8208GC Series/02E83AA0CBB0/GENTOO-2.8/5.16.5-GENTOO/X86_64/4A717F6348>) |
| 10ec:8168 | 7470:3468 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 4     | r8169      | [D95EA030FF](<Server/Dell/PowerEdge/PowerEdge T110 II/2E5934354FEE/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/D95EA030FF>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2723 | 8086:0084 | Intel            | Wi-Fi 6 AX200                        | 7     | iwlwifi    | [670589EC65](<Server/BESSTAR Tech/X/X400/EAE359C1D27F/ENDEAVOUROS-ROLLING/5.15.12-ARCH1-1/X86_64/670589EC65>) |
| 168c:003e | 168c:3360 | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 3     | ath10k_pci | [9F7F807004](<Server/ECS/LIVA/LIVA Q2/6F0AAEC80AB2/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/9F7F807004>) |
| 14e4:43a0 | 14e4:0619 | Broadcom         | BCM4360 802.11ac Wireless Network... | 2     | wl         | [CC8DB94EBA](<Server/Supermicro/X8/X8DT3/37E408F4C551/UBUNTU-19.04/4.19.0-13-LOWLATENCY/X86_64/CC8DB94EBA>) |
| 8086:2526 | 8086:0014 | Intel            | Wireless-AC 9260                     | 2     | iwlwifi    | [3F6EBB3247](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/B6AFC473D671/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/3F6EBB3247>) |
| 8086:a370 | 8086:0034 | Intel            | Cannon Lake PCH CNVi WiFi            | 2     | iwlwifi    | [B943041FBF](<Server/Supermicro/C9/C9Z390-PGW/A268B798E65F/KALI-2021.3/5.14.0-KALI2-AMD64/X86_64/B943041FBF>) |
| 10ec:8812 | 10ec:8203 | Realtek Semic... | RTL8812AE 802.11ac PCIe Wireless ... | 1     | rtl8821ae  | [87E94A007B](<Server/ASUSTek Computer/Z10PA-D8/Z10PA-D8 Series/4CEF9D099F22/UBUNTU-20.04/5.8.0-41-GENERIC/X86_64/87E94A007B>) |
| 10ec:8812 | 10ec:8812 | Realtek Semic... | RTL8812AE 802.11ac PCIe Wireless ... | 1     | rtl8821ae  | [5658A2FB98](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC003KUS/DD1C32AB7122/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/5658A2FB98>) |
| 14c3:0608 | 14c3:0608 | MEDIATEK         | Network controller                   | 1     |            | [0AB1FF409B](<Server/BESSTAR Tech/X/X500/A95AE61E36B4/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/0AB1FF409B>) |
| 14e4:43ba | 106b:0133 | Broadcom         | BCM43602 802.11ac Wireless LAN SoC   | 1     | brcmfmac   | [FC1F78ADA0](<Server/Supermicro/Super/Super Server/C97C65EAC5E2/UBUNTU-20.04/5.4.0-40-GENERIC/X86_64/FC1F78ADA0>) |
| 168c:0013 | 1186:3a73 | Qualcomm Atheros | AR5212/5213/2414 Wireless Network... | 1     | ath5k      | [8F945E0A15](<Server/Supermicro/X8/X8DTL/7581500BE1DB/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/8F945E0A15>) |
| 168c:0013 | 168c:2051 | Qualcomm Atheros | AR5212/5213/2414 Wireless Network... | 1     | ath5k      | [FE3D758C20](<Server/Intel/S5500/S5500BC/EB1E1FCFB3A4/KDE-NEON-20.04/5.4.0-66-GENERIC/X86_64/FE3D758C20>) |
| 168c:001d | 1113:b203 | Qualcomm Atheros | AR2417 Wireless Network Adapter [... | 1     | ath5k      | [EF95821AFC](<Server/Supermicro/X10/X10SAE/233AFEE2447E/UBUNTU-MATE-20.04/5.4.0-52-GENERIC/X86_64/EF95821AFC>) |
| 168c:001d | 168c:2055 | Qualcomm Atheros | AR2417 Wireless Network Adapter [... | 1     | ath5k      | [16BEFD9DC3](<Server/Supermicro/X10/X10SAE/233AFEE2447E/OPENSUSE-TUMBLEWEED-20210311/5.11.4-1-DEFAULT/X86_64/16BEFD9DC3>) |
| 168c:002e | 168c:30a4 | Qualcomm Atheros | AR9287 Wireless Network Adapter (... | 1     | ath9k      | [30831977D2](<Server/ASUSTek Computer/Z9PA-D8/Z9PA-D8 Series/86EE66EF8DD5/OPENSUSE-20211031/5.14.14-1-DEFAULT/X86_64/30831977D2>) |
| 168c:0030 | 168c:3112 | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 1     | ath9k      | [B9AC0D657E](<Server/Supermicro/A1/A1SRM-2558F/DAF42406F667/FEDORA-32/5.8.16-200.FC32.X86_64/X86_64/B9AC0D657E>) |
| 168c:0032 | 168c:3118 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 1     | ath9k      | [E70645D3E6](<Server/Intel/W2600/W2600CR/5A75A85091D9/UBUNTU-20.04/5.4.0-80-GENERIC/X86_64/E70645D3E6>) |
| 168c:0034 | 105b:e058 | Qualcomm Atheros | AR9462 Wireless Network Adapter      | 1     | ath9k      | [676C3ECA96](<Server/Intel/S5520/S5520HC/4D880C0CBA79/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/676C3ECA96>) |
| 1814:0301 | 1737:0055 | Ralink           | RT2561/RT61 802.11g PCI              | 1     | rt61pci    | [5600070A23](<Server/ASUSTek Computer/Z9PA-U8/Z9PA-U8 Series/ACAF72B240BB/UBUNTU-18.04/5.4.0-48-GENERIC/X86_64/5600070A23>) |
| 1814:5392 | 1186:3c06 | Ralink           | RT5392 PCIe Wireless Network Adapter | 1     | rt2800pci  | [E24D0E827B](<Server/Dell/PowerEdge/PowerEdge T110 II/C9588E9ACEC9/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/E24D0E827B>) |
| 8086:08b1 | 8086:4470 | Intel            | Wireless 7260                        | 1     | iwlwifi    | [B8FFB92409](<Server/Neousys Technology/Nuvo-8108GC/Nuvo-8108GC Series/0E8814EA22E8/UBUNTU-18.04/5.4.0-56-GENERIC/X86_64/B8FFB92409>) |
| 8086:08b1 | 8086:c070 | Intel            | Wireless 7260                        | 1     | iwlwifi    | [026B32269E](<Server/ASUSTek Computer/Z9PE-D8/Z9PE-D8 WS/F5006016F49C/CENTOS-8/4.18.0-193.28.1.EL8_2.X86_64/X86_64/026B32269E>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 1     | iwlwifi    | [377C88D227](<Server/Intel/S2600/S2600CO/CF676281389E/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/377C88D227>) |
| 8086:24fd | 8086:0010 | Intel            | Wireless 8265 / 8275                 | 1     | iwlwifi    | [41249F2E48](<Server/Lenovo/ThinkStation/ThinkStation P720 30BBS1PF00/41BFB52F3B1A/FEDORA-32/5.11.11-100.FC32.X86_64/X86_64/41249F2E48>) |
| 8086:2725 | 8086:0024 | Intel            | Wi-Fi 6 AX210/AX211/AX411 160MHz     | 1     |            | [8F45F37B98](<Server/Supermicro/Super/Super Server/FFD9D364C13B/ROSA-2016.1/5.4.32-GENERIC-2ROSA-X86_64/X86_64/8F45F37B98>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1533 | 15d9:1533 | Intel            | I210 Gigabit Network Connection      | 78    | igb        | [B850CD60F6](<Server/Acord-92/PCplus/PCplus T600-C246/CC2E95E1BC69/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B850CD60F6>) |
| 8086:1521 | 15d9:1521 | Intel            | I350 Gigabit Network Connection      | 69    | igb        | [9A0AAAD7ED](<Server/Prime Computer/Server/Server Pro/289FB0C396A8/UBUNTU-20.04/5.4.0-99-GENERIC/X86_64/9A0AAAD7ED>) |
| 8086:10d3 | 15d9:10d3 | Intel            | 82574L Gigabit Network Connection    | 24    | e1000e     | [89D676AF03](<Server/Supermicro/X8/X8DTL/6E7DE9F9FEDC/DEBIAN-11/5.10.0-11-AMD64/X86_64/89D676AF03>) |
| 8086:10d3 | 1043:8369 | Intel            | 82574L Gigabit Network Connection    | 21    | e1000e     | [8A2FB874FE](<Server/ASUSTek Computer/P8B-M/P8B-M Series/38C22118911E/UBUNTU-20.04/5.4.157-1-PVE/X86_64/8A2FB874FE>) |
| 8086:1533 | 1043:8557 | Intel            | I210 Gigabit Network Connection      | 21    | igb        | [9FBB87A829](<Server/VIT/NP3020/NP3020M3/6DA8E8BE5005/DEBIAN-10/4.19.0-18-AMD64/X86_64/9FBB87A829>) |
| 8086:10c9 | 15d9:10c9 | Intel            | 82576 Gigabit Network Connection     | 19    | igb        | [AA1C79AB75](<Server/Supermicro/H8/H8DG6-H8DGi/49F6AA867D33/ARCH/5.16.5-ARCH1-1/X86_64/AA1C79AB75>) |
| 8086:1533 | ffff:0000 | Intel            | I210 Gigabit Network Connection      | 14    | igb        | [4A717F6348](<Server/Neousys Technology/Nuvo-8208GC/Nuvo-8208GC Series/02E83AA0CBB0/GENTOO-2.8/5.16.5-GENTOO/X86_64/4A717F6348>) |
| 8086:1521 | 1028:1f60 | Intel            | I350 Gigabit Network Connection      | 12    | igb        | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:1533 | 1028:0619 | Intel            | I210 Gigabit Network Connection      | 11    | igb        | [2E5507B849](<Server/Dell/Precision/Precision 7920 Tower/6DBFD1DBD45A/UBUNTU-20.04/5.10.0-1055-OEM/X86_64/2E5507B849>) |
| 8086:10d3 | 8086:0000 | Intel            | 82574L Gigabit Network Connection    | 10    | e1000e     | [C5F294D367](<Server/TYAN Computer/S/S7025/49F38982A59C/GENTOO-2.8/5.15.12-GENTOO-X86_64/X86_64/C5F294D367>) |
| 8086:10d3 | 15d9:0000 | Intel            | 82574L Gigabit Network Connection    | 9     | e1000e     | [7F43788673](<Server/Supermicro/X9/X9SRA-X9SRA-3/E419ADCAE2D8/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/7F43788673>) |
| 1077:8020 | 103c:3733 | QLogic           | cLOM8214 1/10GbE Controller          | 8     | qlcnic     | [A28B637049](<Server/Hewlett-Packard/ProLiant/ProLiant DL380e Gen8/ECA2BB01C65F/RHEL-7/3.10.0-1160.EL7.X86_64/X86_64/A28B637049>) |
| 8086:10c9 | 103c:323f | Intel            | 82576 Gigabit Network Connection     | 8     | igb        | [537E8D34B7](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 G6/E32F627377A6/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/537E8D34B7>) |
| 8086:10c9 | 15d9:ab11 | Intel            | 82576 Gigabit Network Connection     | 8     | igb        | [3051CEA326](<Server/Supermicro/H8/H8DGU/8ACEE5E956B2/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3051CEA326>) |
| 8086:1533 | 8086:35b4 | Intel            | I210 Gigabit Network Connection      | 8     | igb        | [7023226F81](<Server/Intel/S1200/S1200RP/832EB05B058D/FEDORA-35/5.16.2-200.FC35.X86_64/X86_64/7023226F81>) |
| 8086:10a7 | 8086:34dc | Intel            | 82575EB Gigabit Network Connection   | 7     | igb        | [A30DCB5033](<Server/Intel/S5520/S5520HC/5E89F6CD026C/ZORIN-16/5.11.0-40-GENERIC/X86_64/A30DCB5033>) |
| 8086:10c9 | 15d9:0100 | Intel            | 82576 Gigabit Network Connection     | 7     | igb        | [C83DC07B7C](<Server/Supermicro/X8/X8DAH/B787FD60BF9A/LINUXMINT-20.1/5.4.0-65-GENERIC/X86_64/C83DC07B7C>) |
| 8086:1521 | 8086:1521 | Intel            | I350 Gigabit Network Connection      | 7     | igb        | [C717BB4AC6](<Server/IBM/System/System X iDataPlex dx360 M4 Server -[7912AC1]-/E15173785994/UBUNTU-18.04/4.15.0-166-GENERIC/X86_64/C717BB4AC6>) |
| 8086:10bd | 8086:34d0 | Intel            | 82566DM-2 Gigabit Network Connection | 6     | e1000e     | [F0473D3564](<Server/Intel/S3210/S3210SH/D6FE7FA8CA14/DEBIAN-10/4.19.0-16-AMD64/X86_64/F0473D3564>) |
| 8086:10d3 | 8086:3578 | Intel            | 82574L Gigabit Network Connection    | 6     | e1000e     | [0051160B0D](<Server/Intel/S1200/S1200BTL/A063843D6E74/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/0051160B0D>) |
| 8086:1502 | 15d9:0623 | Intel            | 82579LM Gigabit Network Connectio... | 6     | e1000e     | [7F43788673](<Server/Supermicro/X9/X9SRA-X9SRA-3/E419ADCAE2D8/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/7F43788673>) |
| 8086:1502 | 8086:3578 | Intel            | 82579LM Gigabit Network Connectio... | 6     | e1000e     | [0051160B0D](<Server/Intel/S1200/S1200BTL/A063843D6E74/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/0051160B0D>) |
| 8086:10a7 | 8086:34e2 | Intel            | 82575EB Gigabit Network Connection   | 5     | igb        | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:10cc | 8086:34da | Intel            | 82567LM-2 Gigabit Network Connection | 5     | e1000e     | [F9F8DD79F5](<Server/Intel/S5500/S5500BC/FF348A4732B6/DEBIAN-9/4.15.18-9-PVE/X86_64/F9F8DD79F5>) |
| 8086:10d3 | 8086:34da | Intel            | 82574L Gigabit Network Connection    | 5     | e1000e     | [F9F8DD79F5](<Server/Intel/S5500/S5500BC/FF348A4732B6/DEBIAN-9/4.15.18-9-PVE/X86_64/F9F8DD79F5>) |
| 8086:10fb | 15d9:0611 | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 5     | ixgbe      | [AFAB4598A7](<Server/ASUSTek Computer/ESC4000/ESC4000 G4/E6BBA8966F48/UBUNTU-18.04/4.15.0-140-GENERIC/X86_64/AFAB4598A7>) |
| 8086:1521 | 1458:0000 | Intel            | I350 Gigabit Network Connection      | 5     | igb        | [96079334BD](<Server/Gigabyte Technology/R182/R182-Z90-00/5D7AD81D6479/UBUNTU-20.04/5.4.0-80-GENERIC/X86_64/96079334BD>) |
| 15b3:1003 | 15b3:0090 | Mellanox Tech... | MT27500 Family [ConnectX-3]          | 4     | mlx4_core  | [2BB4102B1C](<Server/Supermicro/Super/Super Server/45717F18B5CF/CENTOS-8/4.18.0-240.22.1.EL8_3.X86_64/X86_64/2BB4102B1C>) |
| 4040:0100 | 103c:705a | NetXen Incorp... | NX3031 Multifunction 1/10-Gigabit... | 4     | netxen_nic | [FE6B8CB2E4](<Server/Hewlett-Packard/ProLiant/ProLiant DL580 G7/68420A1A9387/FEDORA-35/5.15.16-200.FC35.X86_64/X86_64/FE6B8CB2E4>) |
| 8086:10c9 | 15d9:0400 | Intel            | 82576 Gigabit Network Connection     | 4     | igb        | [AD4ABE60CD](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/03637143A526/XUBUNTU-20.04/5.11.0-37-GENERIC/X86_64/AD4ABE60CD>) |
| 8086:10c9 | 15d9:0600 | Intel            | 82576 Gigabit Network Connection     | 4     | igb        | [ACA2A2FFDF](<Server/Supermicro/X8/X8DTU/B1E056AA3422/DEBIAN-10/5.4.73-1-PVE/X86_64/ACA2A2FFDF>) |
| 8086:10c9 | 15d9:060f | Intel            | 82576 Gigabit Network Connection     | 4     | igb        | [CF99AAD395](<Server/Supermicro/X8/X8DTN+-F/6E42C1AD124C/CENTOS-7/3.10.0-327.36.1.EL7.X86_64/X86_64/CF99AAD395>) |
| 8086:10d3 | 1014:03bd | Intel            | 82574L Gigabit Network Connection    | 4     | e1000e     | [882EA8E25E](<Server/IBM/System/System x3250 M3 -[4252K4G]-/76E08604766E/DEBIAN-10/5.4.106-1-PVE/X86_64/882EA8E25E>) |
| 8086:10d3 | 1734:1192 | Intel            | 82574L Gigabit Network Connection    | 4     | e1000e     | [8CF8F98A53](<Server/Fujitsu/PRIMERGY/PRIMERGY/41B1E7A57925/FEDORA-35/5.14.10-300.FC35.X86_64/X86_64/8CF8F98A53>) |
| 8086:1502 | 1734:11b7 | Intel            | 82579LM Gigabit Network Connectio... | 4     | e1000e     | [8CF8F98A53](<Server/Fujitsu/PRIMERGY/PRIMERGY/41B1E7A57925/FEDORA-35/5.14.10-300.FC35.X86_64/X86_64/8CF8F98A53>) |
| 8086:1521 | 15d9:0656 | Intel            | I350 Gigabit Network Connection      | 4     | igb        | [7AD1F5EB4E](<Server/Supermicro/SYS-1019/SYS-1019P-WTR/4A2458268772/ROSA-2016.1/5.4.32-GENERIC-2ROSA-X86_64/X86_64/7AD1F5EB4E>) |
| 8086:1521 | 8086:357e | Intel            | I350 Gigabit Network Connection      | 4     | igb        | [0FADD1EBE3](<Server/Rackable Systems/CYPRESS/CYPRESS11/8BEF03F49BD3/UBUNTU-18.04/4.15.0-72-GENERIC/X86_64/0FADD1EBE3>) |
| 14e4:164f | 14e4:1113 | Broadcom         | NetXtreme II BCM57711 10-Gigabit ... | 3     | bnx2x      | [FDC516788A](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/7607018A1D31/DEBIAN-10/5.4.65-1-PVE/X86_64/FDC516788A>) |
| 8086:10a7 | 1734:1128 | Intel            | 82575EB Gigabit Network Connection   | 3     | igb        | [43C0756BA6](<Server/Fujitsu/PRIMERGY/PRIMERGY RX300 S5/8D101F548ADF/OPENSUSE-LEAP-15.1/4.12.14-LP151.28.91-DEFAULT/X86_64/43C0756BA6>) |
| 8086:10c9 | 10f1:7012 | Intel            | 82576 Gigabit Network Connection     | 3     | igb        | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:10c9 | 8086:a04c | Intel            | 82576 Gigabit Network Connection     | 3     | igb        | [2CAE1B1D80](<Server/Dell/PowerEdge/PowerEdge T310/1B407A78D4C5/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/2CAE1B1D80>) |
| 8086:10d3 | 1734:1158 | Intel            | 82574L Gigabit Network Connection    | 3     | e1000e     | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:10d3 | 8086:34ec | Intel            | 82574L Gigabit Network Connection    | 3     | e1000e     | [16885BD699](<Server/Intel/S3420/S3420GP/F23666DD52C7/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/16885BD699>) |
| 8086:10d3 | 8086:a01f | Intel            | 82574L Gigabit Network Connection    | 3     | e1000e     | [79E6EAFC82](<Server/Supermicro/Super/Super Server/EA582B67D89D/DEBIAN-11/5.13.19-2-PVE/X86_64/79E6EAFC82>) |
| 8086:10e8 | 8086:a02c | Intel            | 82576 Gigabit Network Connection     | 3     | igb        | [A4C832AB44](<Server/ASUSTek Computer/Z9PE-D8/Z9PE-D8 WS/38D0E7604F44/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/A4C832AB44>) |
| 8086:10ef | 8086:34ec | Intel            | 82578DM Gigabit Network Connection   | 3     | e1000e     | [16885BD699](<Server/Intel/S3420/S3420GP/F23666DD52C7/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/16885BD699>) |
| 8086:1521 | 1028:1faa | Intel            | I350 Gigabit Network Connection      | 3     | igb        | [1CCB5D67C2](<Server/Dell/Precision/Precision 7920 Rack/A97F0E3198F7/UBUNTU-20.04/5.4.0-37-GENERIC/X86_64/1CCB5D67C2>) |
| 8086:1521 | 15d9:0652 | Intel            | I350 Gigabit Network Connection      | 3     | igb        | [F1BF9D35EF](<Server/Supermicro/SYS-5039/SYS-5039MC-H12TRF/C2156B6F043C/DEBIAN-10/5.4.98-1-PVE/X86_64/F1BF9D35EF>) |
| 8086:1521 | 15d9:0875 | Intel            | I350 Gigabit Network Connection      | 3     | igb        | [35739B35C9](<Server/Supermicro/SYS-2049/SYS-2049U-TR4/13107E8A13EF/FEDORA-32/5.8.10-200.FC32.X86_64/X86_64/35739B35C9>) |
| 8086:1521 | ffff:0000 | Intel            | I350 Gigabit Network Connection      | 3     | igb        | [201AA7046E](<Server/Supermicro/H8/H8DGU/2827522B851B/UBUNTU-20.04/5.4.0-77-GENERIC/X86_64/201AA7046E>) |

### Network and computing encryption device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19e5:a255 |           | Huawei Techno... | HiSilicon SEC Engine                 | 1     |            | [63BDABB5A4](<Server/Huawei/TaiShan/TaiShan 2280 V2/2603C7B2E57E/CENTOS-7/4.18.0-147.0.3.EL7.AARCH64/AARCH64/63BDABB5A4>) |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1485 | 1022:1485 | AMD              | Starship/Matisse Reserved SPP        | 13    |            | [4798AC1234](<Server/Supermicro/Super/Super Server/4CD86DE2F12F/UBUNTU-20.04/5.4.0-84-GENERIC/X86_64/4798AC1234>) |
| 1022:148a | 1022:148a | AMD              | Starship/Matisse PCIe Dummy Function | 13    |            | [4798AC1234](<Server/Supermicro/Super/Super Server/4CD86DE2F12F/UBUNTU-20.04/5.4.0-84-GENERIC/X86_64/4798AC1234>) |
| 1022:1485 | 1458:1000 | AMD              | Starship/Matisse Reserved SPP        | 6     |            | [6D2EE30F72](<Server/Gigabyte Technology/MZ71/MZ71-CE0-00/74E7E16574F5/UBUNTU-MATE-20.04/5.11.0-43-GENERIC/X86_64/6D2EE30F72>) |
| 1022:148a | 1458:1000 | AMD              | Starship/Matisse PCIe Dummy Function | 6     |            | [6D2EE30F72](<Server/Gigabyte Technology/MZ71/MZ71-CE0-00/74E7E16574F5/UBUNTU-MATE-20.04/5.11.0-43-GENERIC/X86_64/6D2EE30F72>) |
| 8086:a126 |           | Intel            | 100 Series/C230 Series Chipset Fa... | 4     | intel_t... | [03F2D30DF2](<Server/HPE/ML10/ML10Gen9/5368299CD3DB/UBUNTU-MATE-21.10/5.13.0-23-GENERIC/X86_64/03F2D30DF2>) |
| 1022:1455 | 1022:1455 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 3     |            | [10F1608197](<Server/Supermicro/Super/Super Server/786209B7D1E0/DEBIAN-11/5.11.22-5-PVE/X86_64/10F1608197>) |
| 1022:145a | 1022:145a | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 3     |            | [10F1608197](<Server/Supermicro/Super/Super Server/786209B7D1E0/DEBIAN-11/5.11.22-5-PVE/X86_64/10F1608197>) |
| 1022:1485 | 1028:08fc | AMD              | Starship/Matisse Reserved SPP        | 3     |            | [85004F427A](<Server/Dell/PowerEdge/PowerEdge R6515/591EBA0E828F/SLACKWARE-15.0/5.15.19/X86_64/85004F427A>) |
| 1022:1485 | 1028:08ff | AMD              | Starship/Matisse Reserved SPP        | 3     |            | [A35E7D3EB0](<Server/Dell/PowerEdge/PowerEdge R7525/6B51CAA01B7C/UBUNTU-20.04/5.4.0-74-GENERIC/X86_64/A35E7D3EB0>) |
| 1022:148a | 1028:08fc | AMD              | Starship/Matisse PCIe Dummy Function | 3     |            | [85004F427A](<Server/Dell/PowerEdge/PowerEdge R6515/591EBA0E828F/SLACKWARE-15.0/5.15.19/X86_64/85004F427A>) |
| 1022:148a | 1028:08ff | AMD              | Starship/Matisse PCIe Dummy Function | 3     |            | [A35E7D3EB0](<Server/Dell/PowerEdge/PowerEdge R7525/6B51CAA01B7C/UBUNTU-20.04/5.4.0-74-GENERIC/X86_64/A35E7D3EB0>) |
| 1022:1455 | 1458:1000 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 2     |            | [6D486A7EE9](<Server/Gigabyte Technology/MZ31/MZ31-AR0-00/20445DA51E24/UBUNTU-20.04/5.6.0-1048-OEM/X86_64/6D486A7EE9>) |
| 1022:145a | 1458:1000 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 2     |            | [6D486A7EE9](<Server/Gigabyte Technology/MZ31/MZ31-AR0-00/20445DA51E24/UBUNTU-20.04/5.6.0-1048-OEM/X86_64/6D486A7EE9>) |
| 8086:3456 |           | Intel            | Non-Essential Instrumentation        | 2     |            | [AEAD99F55D](<Server/Intel/AST2600/AST2600EVB/BE9050B3ECF3/CENTOS-8/5.12.0-0.RC2.33.EL8.X86_64+SPR/X86_64/AEAD99F55D>) |
| 1022:1455 | 1028:07f9 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 1     |            | [8F7FF50C55](<Server/Dell/PowerEdge/PowerEdge R7425/EEF1E1F22650/OPENSUSE-LEAP-15.1/4.12.14-LP151.28.13-DEFAULT/X86_64/8F7FF50C55>) |
| 1022:145a | 1028:07f9 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 1     |            | [8F7FF50C55](<Server/Dell/PowerEdge/PowerEdge R7425/EEF1E1F22650/OPENSUSE-LEAP-15.1/4.12.14-LP151.28.13-DEFAULT/X86_64/8F7FF50C55>) |
| 1022:1485 | 1028:08fd | AMD              | Starship/Matisse Reserved SPP        | 1     |            | [F3CBAC183E](<Server/Dell/PowerEdge/PowerEdge R7515/9A7A286BD3E1/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/F3CBAC183E>) |
| 1022:148a | 1028:08fd | AMD              | Starship/Matisse PCIe Dummy Function | 1     |            | [F3CBAC183E](<Server/Dell/PowerEdge/PowerEdge R7515/9A7A286BD3E1/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/F3CBAC183E>) |
| 8086:3456 | 17aa:7810 | Intel            | Non-Essential Instrumentation        | 1     |            | [FF6113B91D](<Server/Lenovo/ThinkSystem/ThinkSystem SR630 V2/ECB5C724E79D/CENTOS-7/3.10.0-1160.49.1.EL7.X86_64/X86_64/FF6113B91D>) |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a135 | 15d9:089a | Intel            | 100 Series/C230 Series Chipset Fa... | 3     | intel_i... | [89CC93BB0F](<Server/Supermicro/Super/Super Server/1751A0B4EDAF/DEBIAN-9/4.15.18-15-PVE/X86_64/89CC93BB0F>) |
| 1415:9510 | 131f:0000 | Oxford Semico... | OX16PCI954 (Quad 16950 UART) func... | 1     |            | [80DC2F8936](<Server/Supermicro/Super/Super Server/A9CFB59D8528/OPENSUSE-LEAP-42.1/4.1.39-56-DEFAULT/X86_64/80DC2F8936>) |
| 1b4b:1475 |           | Marvell Techn... |                                      | 1     |            | [7F5766D5DA](<Server/Dell/PowerEdge/PowerEdge T640/C3C1AB1B873D/UBUNTU-16.04/3.10.105/X86_64/7F5766D5DA>) |
| 1b4b:9235 |           | Marvell Techn... | 88SE9235 PCIe 2.0 x2 4-port SATA ... | 1     |            | [7F5766D5DA](<Server/Dell/PowerEdge/PowerEdge T640/C3C1AB1B873D/UBUNTU-16.04/3.10.105/X86_64/7F5766D5DA>) |
| 1b94:c156 | 1b94:c156 | Signatec / Dy... |                                      | 1     |            | [B3C09674CF](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/31A946D98462/UBUNTU-18.04/4.15.0-142-GENERIC/X86_64/B3C09674CF>) |
| 8086:1533 |           | Intel            | I210 Gigabit Network Connection      | 1     |            | [7F5766D5DA](<Server/Dell/PowerEdge/PowerEdge T640/C3C1AB1B873D/UBUNTU-16.04/3.10.105/X86_64/7F5766D5DA>) |
| 8086:6f04 |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 1     |            | [7F5766D5DA](<Server/Dell/PowerEdge/PowerEdge T640/C3C1AB1B873D/UBUNTU-16.04/3.10.105/X86_64/7F5766D5DA>) |
| 8086:6f06 |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 1     |            | [7F5766D5DA](<Server/Dell/PowerEdge/PowerEdge T640/C3C1AB1B873D/UBUNTU-16.04/3.10.105/X86_64/7F5766D5DA>) |
| 8086:6f08 |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 1     |            | [7F5766D5DA](<Server/Dell/PowerEdge/PowerEdge T640/C3C1AB1B873D/UBUNTU-16.04/3.10.105/X86_64/7F5766D5DA>) |
| 8086:6f0a |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 1     |            | [7F5766D5DA](<Server/Dell/PowerEdge/PowerEdge T640/C3C1AB1B873D/UBUNTU-16.04/3.10.105/X86_64/7F5766D5DA>) |
| 8086:8c22 |           | Intel            | 8 Series/C220 Series Chipset Fami... | 1     |            | [7F5766D5DA](<Server/Dell/PowerEdge/PowerEdge T640/C3C1AB1B873D/UBUNTU-16.04/3.10.105/X86_64/7F5766D5DA>) |
| 8086:8c54 |           | Intel            | C224 Series Chipset Family Server... | 1     |            | [7F5766D5DA](<Server/Dell/PowerEdge/PowerEdge T640/C3C1AB1B873D/UBUNTU-16.04/3.10.105/X86_64/7F5766D5DA>) |
| 8086:a135 | 15d9:0884 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [BB8832ACBD](<Server/Supermicro/Super/Super Server/846C921FF296/ARCH/4.20.0-ARCH1-1-ARCH/X86_64/BB8832ACBD>) |
| 8086:a135 | 15d9:0885 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | intel_i... | [50169A0FFB](<Server/Supermicro/Super/Super Server/866C451F74FD/LINUXMINT-20/5.4.0-26-GENERIC/X86_64/50169A0FFB>) |

### Parallel controller (ieee1284) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 9710:9865 | a000:2000 | MosChip Semic... | PCI 9865 Multi-I/O Controller        | 1     | parport_pc | [715B40D8B6](<Server/Intel/S5000/S5000XVN/187007C30239/FEDORA-34/5.14.12-200.FC34.X86_64/X86_64/715B40D8B6>) |

### Performance counters (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:204c | 8086:0000 | Intel            | Sky Lake-E M3KTI Registers           | 120   | skx_uncore | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:204d | 8086:0000 | Intel            | Sky Lake-E M3KTI Registers           | 120   | skx_uncore | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2015 | 8086:0000 | Intel            | Sky Lake-E Ubox Registers            | 119   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2058 | 8086:0000 | Intel            | Sky Lake-E KTI 0                     | 115   | skx_uncore | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2088 | 8086:0000 | Intel            | Sky Lake-E DDRIO Registers           | 60    | skx_uncore | [73518731A1](<Server/Supermicro/X11/X11DPi-N/6D6FD3049691/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/73518731A1>) |
| 8086:2f30 | 8086:2f30 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 41    | hswep_u... | [C0AA1BF2F1](<Server/Dell/PowerEdge/PowerEdge R730xd/3856150DE2AC/FEDORA-32/5.6.6-300.FC32.X86_64/X86_64/C0AA1BF2F1>) |
| 8086:2f34 | 8086:2f34 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 PCI... | 41    | hswep_u... | [C0AA1BF2F1](<Server/Dell/PowerEdge/PowerEdge R730xd/3856150DE2AC/FEDORA-32/5.6.6-300.FC32.X86_64/X86_64/C0AA1BF2F1>) |
| 8086:2f36 | 8086:2f36 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 41    | hswep_u... | [C0AA1BF2F1](<Server/Dell/PowerEdge/PowerEdge R730xd/3856150DE2AC/FEDORA-32/5.6.6-300.FC32.X86_64/X86_64/C0AA1BF2F1>) |
| 8086:2f37 | 8086:2f37 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 41    | hswep_u... | [C0AA1BF2F1](<Server/Dell/PowerEdge/PowerEdge R730xd/3856150DE2AC/FEDORA-32/5.6.6-300.FC32.X86_64/X86_64/C0AA1BF2F1>) |
| 8086:2f7d | 8086:2f7d | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 41    |            | [C0AA1BF2F1](<Server/Dell/PowerEdge/PowerEdge R730xd/3856150DE2AC/FEDORA-32/5.6.6-300.FC32.X86_64/X86_64/C0AA1BF2F1>) |
| 8086:6f30 | 8086:6f30 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 31    | bdx_uncore | [E60EC405AF](<Server/Supermicro/Super/Super Server/F5F261808B48/GENTOO-2.6/5.15.19-GENTOO/X86_64/E60EC405AF>) |
| 8086:6f34 | 8086:6f34 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 31    | bdx_uncore | [E60EC405AF](<Server/Supermicro/Super/Super Server/F5F261808B48/GENTOO-2.6/5.15.19-GENTOO/X86_64/E60EC405AF>) |
| 8086:6f36 | 8086:6f36 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 31    | bdx_uncore | [E60EC405AF](<Server/Supermicro/Super/Super Server/F5F261808B48/GENTOO-2.6/5.15.19-GENTOO/X86_64/E60EC405AF>) |
| 8086:6f37 | 8086:6f37 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 31    | bdx_uncore | [E60EC405AF](<Server/Supermicro/Super/Super Server/F5F261808B48/GENTOO-2.6/5.15.19-GENTOO/X86_64/E60EC405AF>) |
| 8086:6f7d | 8086:6f7d | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 31    |            | [E60EC405AF](<Server/Supermicro/Super/Super Server/F5F261808B48/GENTOO-2.6/5.15.19-GENTOO/X86_64/E60EC405AF>) |
| 8086:3c43 | 103c:18a8 | Intel            | Xeon E5/Core i7 Ring to PCI Expre... | 28    | snbep_u... | [1172390E59](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/2267C96ADE00/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/1172390E59>) |
| 8086:3c44 | 103c:18a8 | Intel            | Xeon E5/Core i7 Ring to QuickPath... | 28    | snbep_u... | [1172390E59](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/2267C96ADE00/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/1172390E59>) |
| 8086:3c46 | 103c:18a8 | Intel            | Xeon E5/Core i7 Processor Home Ag... | 28    | snbep_u... | [1172390E59](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/2267C96ADE00/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/1172390E59>) |
| 8086:3ce6 | 103c:18a8 | Intel            | Xeon E5/Core i7 QuickPath Interco... | 28    |            | [1172390E59](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/2267C96ADE00/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/1172390E59>) |
| 8086:2f32 | 8086:2f32 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 QPI... | 25    | hswep_u... | [C0AA1BF2F1](<Server/Dell/PowerEdge/PowerEdge R730xd/3856150DE2AC/FEDORA-32/5.6.6-300.FC32.X86_64/X86_64/C0AA1BF2F1>) |
| 8086:2f33 | 8086:2f33 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 QPI... | 24    | hswep_u... | [C0AA1BF2F1](<Server/Dell/PowerEdge/PowerEdge R730xd/3856150DE2AC/FEDORA-32/5.6.6-300.FC32.X86_64/X86_64/C0AA1BF2F1>) |
| 8086:2058 |           | Intel            | Sky Lake-E KTI 0                     | 19    | skx_uncore | [4B1DC70687](<Server/Dell/PowerEdge/PowerEdge R440/F8F03AC45B85/DEBIAN-UNSTABLE/5.16.0-3-AMD64/X86_64/4B1DC70687>) |
| 8086:6f30 | 15d9:0821 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 17    | bdx_uncore | [AAEEE85BE7](<Server/Supermicro/SYS-6028/SYS-6028R-WTRT/690B86B530B0/DEBIAN-11/4.19.0-17-AMD64/X86_64/AAEEE85BE7>) |
| 8086:6f34 | 15d9:0821 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 17    | bdx_uncore | [AAEEE85BE7](<Server/Supermicro/SYS-6028/SYS-6028R-WTRT/690B86B530B0/DEBIAN-11/4.19.0-17-AMD64/X86_64/AAEEE85BE7>) |
| 8086:6f36 | 15d9:0821 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 17    | bdx_uncore | [AAEEE85BE7](<Server/Supermicro/SYS-6028/SYS-6028R-WTRT/690B86B530B0/DEBIAN-11/4.19.0-17-AMD64/X86_64/AAEEE85BE7>) |
| 8086:6f37 | 15d9:0821 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 17    | bdx_uncore | [AAEEE85BE7](<Server/Supermicro/SYS-6028/SYS-6028R-WTRT/690B86B530B0/DEBIAN-11/4.19.0-17-AMD64/X86_64/AAEEE85BE7>) |
| 8086:6f7d | 15d9:0821 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 17    |            | [AAEEE85BE7](<Server/Supermicro/SYS-6028/SYS-6028R-WTRT/690B86B530B0/DEBIAN-11/4.19.0-17-AMD64/X86_64/AAEEE85BE7>) |
| 8086:6f32 | 15d9:0821 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 16    | bdx_uncore | [AAEEE85BE7](<Server/Supermicro/SYS-6028/SYS-6028R-WTRT/690B86B530B0/DEBIAN-11/4.19.0-17-AMD64/X86_64/AAEEE85BE7>) |
| 8086:6f33 | 15d9:0821 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 16    | bdx_uncore | [AAEEE85BE7](<Server/Supermicro/SYS-6028/SYS-6028R-WTRT/690B86B530B0/DEBIAN-11/4.19.0-17-AMD64/X86_64/AAEEE85BE7>) |
| 8086:0e30 | 103c:18a8 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 13    | ivbep_u... | [CB5A76DA6B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/E8F6CD962AFA/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/CB5A76DA6B>) |
| 8086:0e34 | 103c:18a8 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 13    | ivbep_u... | [CB5A76DA6B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/E8F6CD962AFA/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/CB5A76DA6B>) |
| 8086:0e36 | 103c:18a8 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 13    | ivbep_u... | [CB5A76DA6B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/E8F6CD962AFA/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/CB5A76DA6B>) |
| 8086:2f38 | 8086:2f38 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 13    | hswep_u... | [F12EF6E12F](<Server/Others/04N3DF/04N3DF A09/F6FDC11D9D45/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/F12EF6E12F>) |
| 8086:0e30 | 15d9:0636 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 12    | ivbep_u... | [DD93F62FFC](<Server/Supermicro/X9/X9DRW/8C2C75F95ADA/UBUNTU-18.04/5.4.0-58-GENERIC/X86_64/DD93F62FFC>) |
| 8086:0e34 | 15d9:0636 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 12    | ivbep_u... | [DD93F62FFC](<Server/Supermicro/X9/X9DRW/8C2C75F95ADA/UBUNTU-18.04/5.4.0-58-GENERIC/X86_64/DD93F62FFC>) |
| 8086:0e36 | 15d9:0636 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 12    | ivbep_u... | [DD93F62FFC](<Server/Supermicro/X9/X9DRW/8C2C75F95ADA/UBUNTU-18.04/5.4.0-58-GENERIC/X86_64/DD93F62FFC>) |
| 8086:3c43 | 8086:0000 | Intel            | Xeon E5/Core i7 Ring to PCI Expre... | 11    | snbep_u... | [C717BB4AC6](<Server/IBM/System/System X iDataPlex dx360 M4 Server -[7912AC1]-/E15173785994/UBUNTU-18.04/4.15.0-166-GENERIC/X86_64/C717BB4AC6>) |
| 8086:3c44 | 8086:0000 | Intel            | Xeon E5/Core i7 Ring to QuickPath... | 11    | snbep_u... | [C717BB4AC6](<Server/IBM/System/System X iDataPlex dx360 M4 Server -[7912AC1]-/E15173785994/UBUNTU-18.04/4.15.0-166-GENERIC/X86_64/C717BB4AC6>) |
| 8086:3ce6 | 8086:0000 | Intel            | Xeon E5/Core i7 QuickPath Interco... | 11    |            | [C717BB4AC6](<Server/IBM/System/System X iDataPlex dx360 M4 Server -[7912AC1]-/E15173785994/UBUNTU-18.04/4.15.0-166-GENERIC/X86_64/C717BB4AC6>) |
| 8086:6f32 | 8086:6f32 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 11    | bdx_uncore | [11DDC3D97B](<Server/Dell/PowerEdge/PowerEdge R730/B08360FD5D56/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/11DDC3D97B>) |
| 8086:6f33 | 8086:6f33 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 11    | bdx_uncore | [11DDC3D97B](<Server/Dell/PowerEdge/PowerEdge R730/B08360FD5D56/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/11DDC3D97B>) |
| 8086:3c41 | 8086:0000 | Intel            | Sandy Bridge QPI Port 0 Performan... | 10    | snbep_u... | [C717BB4AC6](<Server/IBM/System/System X iDataPlex dx360 M4 Server -[7912AC1]-/E15173785994/UBUNTU-18.04/4.15.0-166-GENERIC/X86_64/C717BB4AC6>) |
| 8086:3c42 | 8086:0000 | Intel            | Sandy Bridge QPI Port 1 Performan... | 10    | snbep_u... | [C717BB4AC6](<Server/IBM/System/System X iDataPlex dx360 M4 Server -[7912AC1]-/E15173785994/UBUNTU-18.04/4.15.0-166-GENERIC/X86_64/C717BB4AC6>) |
| 8086:3c46 |           | Intel            | Xeon E5/Core i7 Processor Home Ag... | 10    | snbep_u... | [C717BB4AC6](<Server/IBM/System/System X iDataPlex dx360 M4 Server -[7912AC1]-/E15173785994/UBUNTU-18.04/4.15.0-166-GENERIC/X86_64/C717BB4AC6>) |
| 8086:3c43 | 1028:048c | Intel            | Xeon E5/Core i7 Ring to PCI Expre... | 9     | snbep_u... | [3B0D723E31](<Server/Dell/PowerEdge/PowerEdge R720/6808912223D2/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/3B0D723E31>) |
| 8086:3c43 | 1043:84f0 | Intel            | Xeon E5/Core i7 Ring to PCI Expre... | 9     | snbep_u... | [30831977D2](<Server/ASUSTek Computer/Z9PA-D8/Z9PA-D8 Series/86EE66EF8DD5/OPENSUSE-20211031/5.14.14-1-DEFAULT/X86_64/30831977D2>) |
| 8086:3c44 | 1028:048c | Intel            | Xeon E5/Core i7 Ring to QuickPath... | 9     | snbep_u... | [3B0D723E31](<Server/Dell/PowerEdge/PowerEdge R720/6808912223D2/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/3B0D723E31>) |
| 8086:3c44 | 1043:84f0 | Intel            | Xeon E5/Core i7 Ring to QuickPath... | 9     | snbep_u... | [30831977D2](<Server/ASUSTek Computer/Z9PA-D8/Z9PA-D8 Series/86EE66EF8DD5/OPENSUSE-20211031/5.14.14-1-DEFAULT/X86_64/30831977D2>) |
| 8086:3c46 | 1028:048c | Intel            | Xeon E5/Core i7 Processor Home Ag... | 9     | snbep_u... | [3B0D723E31](<Server/Dell/PowerEdge/PowerEdge R720/6808912223D2/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/3B0D723E31>) |
| 8086:3c46 | 1043:84f0 | Intel            | Xeon E5/Core i7 Processor Home Ag... | 9     | snbep_u... | [30831977D2](<Server/ASUSTek Computer/Z9PA-D8/Z9PA-D8 Series/86EE66EF8DD5/OPENSUSE-20211031/5.14.14-1-DEFAULT/X86_64/30831977D2>) |

### Pic (8259) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:342e |           | Intel            | 7500/5520/5500/X58 I/O Hub System... | 143   | i7core_... | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:3422 |           | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 141   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:3423 |           | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 141   |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:3438 |           | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 78    | i5500_temp | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:3422 | 003c:000b | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 44    |            | [537E8D34B7](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 G6/E32F627377A6/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/537E8D34B7>) |
| 8086:3423 | 003c:000b | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 44    |            | [537E8D34B7](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 G6/E32F627377A6/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/537E8D34B7>) |
| 8086:342e | 003c:000b | Intel            | 7500/5520/5500/X58 I/O Hub System... | 44    | i7core_... | [537E8D34B7](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 G6/E32F627377A6/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/537E8D34B7>) |
| 8086:3425 |           | Intel            | 7500/5520/5500/X58 Physical and L... | 13    |            | [C5F294D367](<Server/TYAN Computer/S/S7025/49F38982A59C/GENTOO-2.8/5.15.12-GENTOO-X86_64/X86_64/C5F294D367>) |
| 8086:3426 |           | Intel            | 7500/5520/5500/X58 Routing and Pr... | 13    |            | [C5F294D367](<Server/TYAN Computer/S/S7025/49F38982A59C/GENTOO-2.8/5.15.12-GENTOO-X86_64/X86_64/C5F294D367>) |
| 8086:3427 |           | Intel            | 7500/5520/5500 Physical and Link ... | 13    |            | [C5F294D367](<Server/TYAN Computer/S/S7025/49F38982A59C/GENTOO-2.8/5.15.12-GENTOO-X86_64/X86_64/C5F294D367>) |
| 8086:3428 |           | Intel            | 7500/5520/5500 Routing & Protocol... | 13    |            | [C5F294D367](<Server/TYAN Computer/S/S7025/49F38982A59C/GENTOO-2.8/5.15.12-GENTOO-X86_64/X86_64/C5F294D367>) |
| 8086:3422 | 0086:00dc | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 7     |            | [A30DCB5033](<Server/Intel/S5520/S5520HC/5E89F6CD026C/ZORIN-16/5.11.0-40-GENERIC/X86_64/A30DCB5033>) |
| 8086:3423 | 0086:00dc | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 7     |            | [A30DCB5033](<Server/Intel/S5520/S5520HC/5E89F6CD026C/ZORIN-16/5.11.0-40-GENERIC/X86_64/A30DCB5033>) |
| 8086:3425 | 0086:00dc | Intel            | 7500/5520/5500/X58 Physical and L... | 7     |            | [A30DCB5033](<Server/Intel/S5520/S5520HC/5E89F6CD026C/ZORIN-16/5.11.0-40-GENERIC/X86_64/A30DCB5033>) |
| 8086:3426 | 0086:00dc | Intel            | 7500/5520/5500/X58 Routing and Pr... | 7     |            | [A30DCB5033](<Server/Intel/S5520/S5520HC/5E89F6CD026C/ZORIN-16/5.11.0-40-GENERIC/X86_64/A30DCB5033>) |
| 8086:3427 | 0086:00dc | Intel            | 7500/5520/5500 Physical and Link ... | 7     |            | [A30DCB5033](<Server/Intel/S5520/S5520HC/5E89F6CD026C/ZORIN-16/5.11.0-40-GENERIC/X86_64/A30DCB5033>) |
| 8086:3428 | 0086:00dc | Intel            | 7500/5520/5500 Routing & Protocol... | 7     |            | [A30DCB5033](<Server/Intel/S5520/S5520HC/5E89F6CD026C/ZORIN-16/5.11.0-40-GENERIC/X86_64/A30DCB5033>) |
| 8086:342e | 0086:00dc | Intel            | 7500/5520/5500/X58 I/O Hub System... | 7     | i7core_... | [A30DCB5033](<Server/Intel/S5520/S5520HC/5E89F6CD026C/ZORIN-16/5.11.0-40-GENERIC/X86_64/A30DCB5033>) |
| 8086:3438 | 0086:00dc | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 7     | i5500_temp | [A30DCB5033](<Server/Intel/S5520/S5520HC/5E89F6CD026C/ZORIN-16/5.11.0-40-GENERIC/X86_64/A30DCB5033>) |
| 8086:3422 | 0034:0027 | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 6     |            | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:3423 | 0034:0027 | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 6     |            | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:3425 | 0034:0027 | Intel            | 7500/5520/5500/X58 Physical and L... | 6     |            | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:3426 | 0034:0027 | Intel            | 7500/5520/5500/X58 Routing and Pr... | 6     |            | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:3427 | 0034:0027 | Intel            | 7500/5520/5500 Physical and Link ... | 6     |            | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:3428 | 0034:0027 | Intel            | 7500/5520/5500 Routing & Protocol... | 6     |            | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:342e | 0034:0027 | Intel            | 7500/5520/5500/X58 I/O Hub System... | 6     | i7core_... | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:3438 | 0034:0027 | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 6     | i5500_temp | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:3422 | 0086:00da | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 5     |            | [F9F8DD79F5](<Server/Intel/S5500/S5500BC/FF348A4732B6/DEBIAN-9/4.15.18-9-PVE/X86_64/F9F8DD79F5>) |
| 8086:3422 | 0086:00e2 | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3423 | 0086:00da | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 5     |            | [F9F8DD79F5](<Server/Intel/S5500/S5500BC/FF348A4732B6/DEBIAN-9/4.15.18-9-PVE/X86_64/F9F8DD79F5>) |
| 8086:3423 | 0086:00e2 | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3425 | 0086:00da | Intel            | 7500/5520/5500/X58 Physical and L... | 5     |            | [F9F8DD79F5](<Server/Intel/S5500/S5500BC/FF348A4732B6/DEBIAN-9/4.15.18-9-PVE/X86_64/F9F8DD79F5>) |
| 8086:3425 | 0086:00e2 | Intel            | 7500/5520/5500/X58 Physical and L... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3426 | 0086:00da | Intel            | 7500/5520/5500/X58 Routing and Pr... | 5     |            | [F9F8DD79F5](<Server/Intel/S5500/S5500BC/FF348A4732B6/DEBIAN-9/4.15.18-9-PVE/X86_64/F9F8DD79F5>) |
| 8086:3426 | 0086:00e2 | Intel            | 7500/5520/5500/X58 Routing and Pr... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3427 | 0086:00da | Intel            | 7500/5520/5500 Physical and Link ... | 5     |            | [F9F8DD79F5](<Server/Intel/S5500/S5500BC/FF348A4732B6/DEBIAN-9/4.15.18-9-PVE/X86_64/F9F8DD79F5>) |
| 8086:3427 | 0086:00e2 | Intel            | 7500/5520/5500 Physical and Link ... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3428 | 0086:00da | Intel            | 7500/5520/5500 Routing & Protocol... | 5     |            | [F9F8DD79F5](<Server/Intel/S5500/S5500BC/FF348A4732B6/DEBIAN-9/4.15.18-9-PVE/X86_64/F9F8DD79F5>) |
| 8086:3428 | 0086:00e2 | Intel            | 7500/5520/5500 Routing & Protocol... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:342e | 0086:00da | Intel            | 7500/5520/5500/X58 I/O Hub System... | 5     | i7core_... | [F9F8DD79F5](<Server/Intel/S5500/S5500BC/FF348A4732B6/DEBIAN-9/4.15.18-9-PVE/X86_64/F9F8DD79F5>) |
| 8086:342e | 0086:00e2 | Intel            | 7500/5520/5500/X58 I/O Hub System... | 5     | i7core_... | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3438 | 0086:00da | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 5     | i5500_temp | [F9F8DD79F5](<Server/Intel/S5500/S5500BC/FF348A4732B6/DEBIAN-9/4.15.18-9-PVE/X86_64/F9F8DD79F5>) |
| 8086:3438 | 0086:00e2 | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 5     | i5500_temp | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3422 | 0086:00de | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 2     |            | [3AB9D48A33](<Server/Intel/S5520/S5520UR/156DA9D7B494/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/3AB9D48A33>) |
| 8086:3423 | 0086:00de | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 2     |            | [3AB9D48A33](<Server/Intel/S5520/S5520UR/156DA9D7B494/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/3AB9D48A33>) |
| 8086:3425 | 0086:00de | Intel            | 7500/5520/5500/X58 Physical and L... | 2     |            | [3AB9D48A33](<Server/Intel/S5520/S5520UR/156DA9D7B494/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/3AB9D48A33>) |
| 8086:3426 | 0086:00de | Intel            | 7500/5520/5500/X58 Routing and Pr... | 2     |            | [3AB9D48A33](<Server/Intel/S5520/S5520UR/156DA9D7B494/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/3AB9D48A33>) |
| 8086:3427 | 0086:00de | Intel            | 7500/5520/5500 Physical and Link ... | 2     |            | [3AB9D48A33](<Server/Intel/S5520/S5520UR/156DA9D7B494/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/3AB9D48A33>) |
| 8086:3428 | 0086:00de | Intel            | 7500/5520/5500 Routing & Protocol... | 2     |            | [3AB9D48A33](<Server/Intel/S5520/S5520UR/156DA9D7B494/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/3AB9D48A33>) |
| 8086:342e | 0086:00de | Intel            | 7500/5520/5500/X58 I/O Hub System... | 2     | i7core_... | [3AB9D48A33](<Server/Intel/S5520/S5520UR/156DA9D7B494/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/3AB9D48A33>) |

### Pic (io(x)-apic) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2026 | 8086:2026 | Intel            | Sky Lake-E IOAPIC                    | 115   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2036 | 8086:2036 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 115   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:342d |           | Intel            | 7500/5520/5500/X58 I/O Hub I/OxAP... | 64    |            | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:3c2c | 103c:18a8 | Intel            | Xeon E5/Core i7 I/O APIC             | 32    |            | [1172390E59](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/2267C96ADE00/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/1172390E59>) |
| 8086:2f2c | 8086:0000 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 29    |            | [C0AA1BF2F1](<Server/Dell/PowerEdge/PowerEdge R730xd/3856150DE2AC/FEDORA-32/5.6.6-300.FC32.X86_64/X86_64/C0AA1BF2F1>) |
| 8086:6f2c | 15d9:0821 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 17    |            | [AAEEE85BE7](<Server/Supermicro/SYS-6028/SYS-6028R-WTRT/690B86B530B0/DEBIAN-11/4.19.0-17-AMD64/X86_64/AAEEE85BE7>) |
| 8086:6f2c | 8086:0000 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 15    |            | [11DDC3D97B](<Server/Dell/PowerEdge/PowerEdge R730/B08360FD5D56/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/11DDC3D97B>) |
| 8086:0e2c | 103c:18a8 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 13    |            | [CB5A76DA6B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/E8F6CD962AFA/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/CB5A76DA6B>) |
| 8086:0e2c | 15d9:0636 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 12    |            | [DD93F62FFC](<Server/Supermicro/X9/X9DRW/8C2C75F95ADA/UBUNTU-18.04/5.4.0-58-GENERIC/X86_64/DD93F62FFC>) |
| 8086:3c2c | 1043:84f0 | Intel            | Xeon E5/Core i7 I/O APIC             | 9     |            | [30831977D2](<Server/ASUSTek Computer/Z9PA-D8/Z9PA-D8 Series/86EE66EF8DD5/OPENSUSE-20211031/5.14.14-1-DEFAULT/X86_64/30831977D2>) |
| 8086:2f2c | 15d9:0857 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 8     |            | [6A333A499D](<Server/Supermicro/X10/X10SRA/0DAF404C22AB/GENTOO-2.7/5.14.14-GENTOO-X86_64/X86_64/6A333A499D>) |
| 8086:342f |           | Intel            | 7500/5520/5500/X58 Trusted Execut... | 8     |            | [76A0EBBFC4](<Server/IBM/System/System x3550 M3 -[7944KAG]-/E6F6F92CA768/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/76A0EBBFC4>) |
| 8086:0e2c | 1043:84f0 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 7     |            | [0D39F4F066](<Server/ASUSTek Computer/Z9PE-D16/Z9PE-D16 Series/7948CC9F2801/UBUNTU-18.04/5.4.0-91-GENERIC/X86_64/0D39F4F066>) |
| 8086:2026 | 1590:18a9 | Intel            | Sky Lake-E IOAPIC                    | 7     |            | [7AB4F05613](<Server/HPE/ProLiant/ProLiant DL360 Gen10/4443D3087423/UBUNTU-18.04/4.15.0-135-GENERIC/X86_64/7AB4F05613>) |
| 8086:2026 | 17aa:7808 | Intel            | Sky Lake-E IOAPIC                    | 7     |            | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 8086:2026 | 8086:0000 | Intel            | Sky Lake-E IOAPIC                    | 7     |            | [679871CFEC](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/E621F1A07D2C/UBUNTU-20.04/5.4.0-84-GENERIC/X86_64/679871CFEC>) |
| 8086:2036 | 1590:18a9 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 7     |            | [7AB4F05613](<Server/HPE/ProLiant/ProLiant DL360 Gen10/4443D3087423/UBUNTU-18.04/4.15.0-135-GENERIC/X86_64/7AB4F05613>) |
| 8086:2036 | 17aa:7808 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 7     |            | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 8086:2036 | 8086:0000 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 7     |            | [679871CFEC](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/E621F1A07D2C/UBUNTU-20.04/5.4.0-84-GENERIC/X86_64/679871CFEC>) |
| 8086:2f2c | 103c:21ea | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 7     |            | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 8086:342d | 0086:00dc | Intel            | 7500/5520/5500/X58 I/O Hub I/OxAP... | 7     |            | [A30DCB5033](<Server/Intel/S5520/S5520HC/5E89F6CD026C/ZORIN-16/5.11.0-40-GENERIC/X86_64/A30DCB5033>) |
| 8086:342f | 0086:00dc | Intel            | 7500/5520/5500/X58 Trusted Execut... | 7     |            | [A30DCB5033](<Server/Intel/S5520/S5520HC/5E89F6CD026C/ZORIN-16/5.11.0-40-GENERIC/X86_64/A30DCB5033>) |
| 8086:2f2c | 15d9:0831 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 6     |            | [58E86F0E34](<Server/Supermicro/Super/Super Server/BD4C9B6F043B/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/58E86F0E34>) |
| 8086:342f | 0034:0027 | Intel            | 7500/5520/5500/X58 Trusted Execut... | 6     |            | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:2026 | 1849:2026 | Intel            | Sky Lake-E IOAPIC                    | 5     |            | [BAA2C57359](<Server/ASRockRack/EPC621/EPC621D8A/5678CB93815F/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/BAA2C57359>) |
| 8086:2036 | 1849:2036 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 5     |            | [BAA2C57359](<Server/ASRockRack/EPC621/EPC621D8A/5678CB93815F/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/BAA2C57359>) |
| 8086:342d | 0086:00da | Intel            | 7500/5520/5500/X58 I/O Hub I/OxAP... | 5     |            | [F9F8DD79F5](<Server/Intel/S5500/S5500BC/FF348A4732B6/DEBIAN-9/4.15.18-9-PVE/X86_64/F9F8DD79F5>) |
| 8086:342d | 0086:00e2 | Intel            | 7500/5520/5500/X58 I/O Hub I/OxAP... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:342f | 0086:00da | Intel            | 7500/5520/5500/X58 Trusted Execut... | 5     |            | [F9F8DD79F5](<Server/Intel/S5500/S5500BC/FF348A4732B6/DEBIAN-9/4.15.18-9-PVE/X86_64/F9F8DD79F5>) |
| 8086:342f | 0086:00e2 | Intel            | 7500/5520/5500/X58 Trusted Execut... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:6f2c | 103c:21ea | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 5     |            | [7D9FDF4B73](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/16075FBC6C06/UBUNTU-21.10/5.15.1-051501-GENERIC/X86_64/7D9FDF4B73>) |
| 8086:0e2c | 15d9:062a | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 4     |            | [7F43788673](<Server/Supermicro/X9/X9SRA-X9SRA-3/E419ADCAE2D8/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/7F43788673>) |
| 8086:0e2c | 8086:35a0 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 4     |            | [FE1E6CFF79](<Server/Intel/S4600/S4600LH/F04F47B2E9E9/UBUNTU-18.04/4.15.0-76-GENERIC/X86_64/FE1E6CFF79>) |
| 8086:2026 | 8086:35ce | Intel            | Sky Lake-E IOAPIC                    | 4     |            | [36C4ACAC2D](<Server/Intel/S2600/S2600WFT/8DC9639F1DBF/ROCKY-8.4/4.18.0-305.10.2.EL8_4.X86_64/X86_64/36C4ACAC2D>) |
| 8086:0e2c | 8086:0e2c | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 3     |            | [E0EF143493](<Server/Quanta/Freedom/Freedom/53CBFD82B356/LINUXMINT-19.3/5.0.0-32-GENERIC/X86_64/E0EF143493>) |
| 8086:2026 | 17aa:1038 | Intel            | Sky Lake-E IOAPIC                    | 3     |            | [5658A2FB98](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC003KUS/DD1C32AB7122/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/5658A2FB98>) |
| 8086:2036 | 17aa:1038 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 3     |            | [5658A2FB98](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC003KUS/DD1C32AB7122/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/5658A2FB98>) |
| 8086:2036 | 8086:35ce | Intel            | Sky Lake-E IOxAPIC Configuration ... | 3     |            | [36C4ACAC2D](<Server/Intel/S2600/S2600WFT/8DC9639F1DBF/ROCKY-8.4/4.18.0-305.10.2.EL8_4.X86_64/X86_64/36C4ACAC2D>) |
| 8086:3c2c | 15d9:0626 | Intel            | Xeon E5/Core i7 I/O APIC             | 3     |            | [DE8D4D24B6](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/050383036EDE/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/DE8D4D24B6>) |
| 8086:3c2c | 8086:357e | Intel            | Xeon E5/Core i7 I/O APIC             | 3     |            | [0FADD1EBE3](<Server/Rackable Systems/CYPRESS/CYPRESS11/8BEF03F49BD3/UBUNTU-18.04/4.15.0-72-GENERIC/X86_64/0FADD1EBE3>) |
| 8086:6f2c | 1d49:0a00 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 3     |            | [78113D1370](<Server/Lenovo/Flex/Flex System x240 M5 Compute Node -[9532AC1]-/CC76B4AA67C4/DEBIAN-10/4.19.0-16-AMD64/X86_64/78113D1370>) |
| 8086:0326 |           | Intel            | 6700/6702PXH I/OxAPIC Interrupt C... | 2     |            | [535E5F1D58](<Server/Supermicro/X8/X8DTN/50F52177DF45/DEBIAN-11/5.10.0-8-AMD64/X86_64/535E5F1D58>) |
| 8086:0e2c | 1170:0054 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 2     |            | [1B5977B024](<Server/ZTSYSTEMS/Z/Z801/2920EC336BF6/RHEL-7/3.10.0-1062.4.3.EL7.YAHOO.20191113.49.X86_64/X86_64/1B5977B024>) |
| 8086:0e2c | 15d9:0626 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 2     |            | [00FDD71981](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/B8B03C82409C/GENTOO-2.6/5.4.48-GENTOO/X86_64/00FDD71981>) |
| 8086:0e2c | 15d9:062b | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 2     |            | [FD24B5D375](<Server/Supermicro/X9/X9SRE-X9SRE-3F-X9SRi-X9SRi-3F/B81C423EDCC3/DEBIAN-10/4.19.0-10-AMD64/X86_64/FD24B5D375>) |
| 8086:2026 | 17aa:7800 | Intel            | Sky Lake-E IOAPIC                    | 2     |            | [928EE22E71](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 -[7X06CTO1WW]-/5D8AB08CFEB3/CENTOS-7/3.10.0-1160.21.1.EL7.X86_64/X86_64/928EE22E71>) |
| 8086:2036 | 17aa:7800 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 2     |            | [928EE22E71](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 -[7X06CTO1WW]-/5D8AB08CFEB3/CENTOS-7/3.10.0-1160.21.1.EL7.X86_64/X86_64/928EE22E71>) |
| 8086:2f2c | 15d9:0860 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 2     |            | [CC00646768](<Server/Supermicro/Super/Super Server/218C388A99BB/CENTOS-7/3.10.0-1062.18.1.EL7.X86_64/X86_64/CC00646768>) |
| 8086:342d | 0086:00de | Intel            | 7500/5520/5500/X58 I/O Hub I/OxAP... | 2     |            | [3AB9D48A33](<Server/Intel/S5520/S5520UR/156DA9D7B494/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/3AB9D48A33>) |
| 8086:342f | 0086:00de | Intel            | 7500/5520/5500/X58 Trusted Execut... | 2     |            | [3AB9D48A33](<Server/Intel/S5520/S5520UR/156DA9D7B494/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/3AB9D48A33>) |

### Pic (io-apic) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:7451 | 1022:7451 | AMD              | AMD-8131 PCI-X IOAPIC                | 1     |            | [18B25AC51A](<Server/TYAN Computer/S/S4882/84BBA0EA52AC/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/18B25AC51A>) |
| 1022:7451 | 10f1:2895 | AMD              | AMD-8131 PCI-X IOAPIC                | 1     |            | [768571B831](<Server/TYAN Computer/S/S2895/4B5DFCDB09B6/LINUXMINT-20/5.4.0-58-GENERIC/X86_64/768571B831>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:31cc | 1019:a94d | Intel            | Celeron/Pentium Silver Processor ... | 3     | sdhci_pci  | [9F7F807004](<Server/ECS/LIVA/LIVA Q2/6F0AAEC80AB2/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/9F7F807004>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a1a4 | 8086:7270 | Intel            | C620 Series Chipset Family SPI Co... | 20    | intel_s... | [73518731A1](<Server/Supermicro/X11/X11DPi-N/6D6FD3049691/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/73518731A1>) |
| 8086:a1a4 | 8086:35ce | Intel            | C620 Series Chipset Family SPI Co... | 19    |            | [36C4ACAC2D](<Server/Intel/S2600/S2600WFT/8DC9639F1DBF/ROCKY-8.4/4.18.0-305.10.2.EL8_4.X86_64/X86_64/36C4ACAC2D>) |
| 8086:a1a4 | 1028:073a | Intel            | C620 Series Chipset Family SPI Co... | 11    |            | [2E5507B849](<Server/Dell/Precision/Precision 7920 Tower/6DBFD1DBD45A/UBUNTU-20.04/5.10.0-1055-OEM/X86_64/2E5507B849>) |
| 8086:a1a4 | 1043:871e | Intel            | C620 Series Chipset Family SPI Co... | 9     | intel_s... | [3035FDAD91](<Server/ASUSTek Computer/WS-C621E-SAGE/WS-C621E-SAGE Series/E86AFFE0F80D/KUBUNTU-20.04/5.4.0-97-GENERIC/X86_64/3035FDAD91>) |
| 8086:a1a4 | 15d9:096d | Intel            | C620 Series Chipset Family SPI Co... | 8     |            | [2CDAC4454D](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.16.8-051608-GENERIC/X86_64/2CDAC4454D>) |
| 8086:a1a4 | 17aa:7808 | Intel            | C620 Series Chipset Family SPI Co... | 7     | intel_s... | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 8086:a1a4 | 1028:0715 | Intel            | C620 Series Chipset Family SPI Co... | 5     |            | [FCC6D41C03](<Server/Dell/PowerEdge/PowerEdge R740/203EBCE27AC6/CENTOS-7/3.10.0-1160.45.1.EL7.X86_64/X86_64/FCC6D41C03>) |
| 8086:a1a4 | 1028:0739 | Intel            | C620 Series Chipset Family SPI Co... | 5     |            | [5A2FCB7023](<Server/Dell/Precision/Precision 7820 Tower/8AAB146ACE98/LINUXMINT-20/5.4.0-91-GENERIC/X86_64/5A2FCB7023>) |
| 8086:a1a4 | 15d9:0981 | Intel            | C620 Series Chipset Family SPI Co... | 5     | intel_s... | [1A73C74FBB](<Server/Supermicro/Super/Super Server/909986EADB14/UBUNTU-21.04/5.11.0-38-GENERIC/X86_64/1A73C74FBB>) |
| 8086:a1a4 | 1849:a1a4 | Intel            | C620 Series Chipset Family SPI Co... | 5     |            | [BAA2C57359](<Server/ASRockRack/EPC621/EPC621D8A/5678CB93815F/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/BAA2C57359>) |
| 8086:a324 | 8086:7270 | Intel            | Cannon Lake PCH SPI Controller       | 5     |            | [4A717F6348](<Server/Neousys Technology/Nuvo-8208GC/Nuvo-8208GC Series/02E83AA0CBB0/GENTOO-2.8/5.16.5-GENTOO/X86_64/4A717F6348>) |
| 8086:a1a4 | 103c:81c7 | Intel            | C620 Series Chipset Family SPI Co... | 4     |            | [5299B4DA87](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/68BC2092E093/UBUNTU-18.04/5.4.0-74-GENERIC/X86_64/5299B4DA87>) |
| 8086:a1a4 | 15d9:0953 | Intel            | C620 Series Chipset Family SPI Co... | 4     |            | [A76BB2E30D](<Server/Supermicro/SYS-5029/SYS-5029P-WTR/2D889DFAC2FF/ROCKY-8.5/4.18.0-348.12.2.EL8_5.X86_64/X86_64/A76BB2E30D>) |
| 8086:a324 | 15d9:1a1d | Intel            | Cannon Lake PCH SPI Controller       | 4     | intel_s... | [B850CD60F6](<Server/Acord-92/PCplus/PCplus T600-C246/CC2E95E1BC69/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B850CD60F6>) |
| 8086:a368 | 15d9:1a1d | Intel            | Cannon Lake PCH Serial IO I2C Con... | 4     | intel_l... | [B850CD60F6](<Server/Acord-92/PCplus/PCplus T600-C246/CC2E95E1BC69/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B850CD60F6>) |
| 8086:a369 | 15d9:1a1d | Intel            | Cannon Lake PCH Serial IO I2C Con... | 4     | intel_l... | [B850CD60F6](<Server/Acord-92/PCplus/PCplus T600-C246/CC2E95E1BC69/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B850CD60F6>) |
| 10de:1ad7 | 1458:37c4 | Nvidia           | TU102 USB Type-C UCSI Controller     | 3     | i2c_nvi... | [F9D0B2BC99](<Server/Supermicro/Super/Super Server/AB17D6414AF9/UBUNTU-18.04/5.3.0-51-GENERIC/X86_64/F9D0B2BC99>) |
| 10de:1ad9 | 1028:12a0 | Nvidia           | TU104 USB Type-C UCSI Controller     | 3     | i2c_nvi... | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:a1a4 | 1028:0716 | Intel            | C620 Series Chipset Family SPI Co... | 3     |            | [E752263E49](<Server/Dell/PowerEdge/PowerEdge R640/1917FF5F0757/CENTOS-7/3.10.0-957.21.3.EL7.X86_64/X86_64/E752263E49>) |
| 8086:a1a4 | 1028:0718 | Intel            | C620 Series Chipset Family SPI Co... | 3     |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:a1a4 | 103c:81c6 | Intel            | C620 Series Chipset Family SPI Co... | 3     |            | [679871CFEC](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/E621F1A07D2C/UBUNTU-20.04/5.4.0-84-GENERIC/X86_64/679871CFEC>) |
| 8086:a1a4 | 15d9:095d | Intel            | C620 Series Chipset Family SPI Co... | 3     |            | [C682299C13](<Server/Supermicro/X11/X11-SPM-TF/17F67170A1AB/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/C682299C13>) |
| 8086:a1a4 | 17aa:1038 | Intel            | C620 Series Chipset Family SPI Co... | 3     |            | [5658A2FB98](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC003KUS/DD1C32AB7122/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/5658A2FB98>) |
| 8086:a324 | 1028:088e | Intel            | Cannon Lake PCH SPI Controller       | 3     |            | [2A87802C58](<Server/Dell/PowerEdge/PowerEdge R340/89867B3F61A1/DEBIAN-9/4.9.0-14-AMD64/X86_64/2A87802C58>) |
| 8086:a324 | 15d9:1a1b | Intel            | Cannon Lake PCH SPI Controller       | 3     |            | [F1BF9D35EF](<Server/Supermicro/SYS-5039/SYS-5039MC-H12TRF/C2156B6F043C/DEBIAN-10/5.4.98-1-PVE/X86_64/F1BF9D35EF>) |
| 8086:a324 | 15d9:1a1f | Intel            | Cannon Lake PCH SPI Controller       | 3     |            | [34B9B698CD](<Server/Supermicro/Super/Super Server/617C605D5B8B/DEBIAN-11/5.10.0-9-AMD64/X86_64/34B9B698CD>) |
| 8086:a368 | 15d9:1a1b | Intel            | Cannon Lake PCH Serial IO I2C Con... | 3     | intel_l... | [F1BF9D35EF](<Server/Supermicro/SYS-5039/SYS-5039MC-H12TRF/C2156B6F043C/DEBIAN-10/5.4.98-1-PVE/X86_64/F1BF9D35EF>) |
| 8086:a368 | 15d9:1a1f | Intel            | Cannon Lake PCH Serial IO I2C Con... | 3     | intel_l... | [34B9B698CD](<Server/Supermicro/Super/Super Server/617C605D5B8B/DEBIAN-11/5.10.0-9-AMD64/X86_64/34B9B698CD>) |
| 8086:a369 | 15d9:1a1b | Intel            | Cannon Lake PCH Serial IO I2C Con... | 3     | intel_l... | [F1BF9D35EF](<Server/Supermicro/SYS-5039/SYS-5039MC-H12TRF/C2156B6F043C/DEBIAN-10/5.4.98-1-PVE/X86_64/F1BF9D35EF>) |
| 8086:a369 | 15d9:1a1f | Intel            | Cannon Lake PCH Serial IO I2C Con... | 3     | intel_l... | [34B9B698CD](<Server/Supermicro/Super/Super Server/617C605D5B8B/DEBIAN-11/5.10.0-9-AMD64/X86_64/34B9B698CD>) |
| 10de:1ad7 | 1028:12ba | Nvidia           | TU102 USB Type-C UCSI Controller     | 2     | i2c_nvi... | [33FDE2B5FB](<Server/Dell/Precision/Precision 7920 Tower/FB96B8D78458/UBUNTU-20.04/5.8.0-43-GENERIC/X86_64/33FDE2B5FB>) |
| 10de:1ad7 | 1043:8675 | Nvidia           | TU102 USB Type-C UCSI Controller     | 2     | i2c_nvi... | [B714FA4C7F](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/E3AB736A8A10/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/B714FA4C7F>) |
| 10de:1ad7 | 10de:12a3 | Nvidia           | TU102 USB Type-C UCSI Controller     | 2     | i2c_nvi... | [8A1397B10C](<Server/Dell/Precision/Precision 7920 Tower/2EF12D6F97D1/UBUNTU-20.04/5.8.0-63-GENERIC/X86_64/8A1397B10C>) |
| 8086:19e0 | 15d9:0969 | Intel            | Atom Processor C3000 Series SPI C... | 2     | intel_s... | [40E07B4DAD](<Server/Supermicro/Super/Super Server/73152EF104BB/MANJARO-21.0.2/5.11.14-1-MANJARO/X86_64/40E07B4DAD>) |
| 8086:1bca | 8086:7270 | Intel            | Serial bus controller                | 2     |            | [AEAD99F55D](<Server/Intel/AST2600/AST2600EVB/BE9050B3ECF3/CENTOS-8/5.12.0-0.RC2.33.EL8.X86_64+SPR/X86_64/AEAD99F55D>) |
| 8086:a1a4 | 1028:0737 | Intel            | C620 Series Chipset Family SPI Co... | 2     |            | [DF9A63BE43](<Server/Dell/PowerEdge/PowerEdge R740xd/62F4A9812E0F/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/DF9A63BE43>) |
| 8086:a1a4 | 1028:07c9 | Intel            | C620 Series Chipset Family SPI Co... | 2     |            | [4B1DC70687](<Server/Dell/PowerEdge/PowerEdge R440/F8F03AC45B85/DEBIAN-UNSTABLE/5.16.0-3-AMD64/X86_64/4B1DC70687>) |
| 8086:a1a4 | 1028:07cb | Intel            | C620 Series Chipset Family SPI Co... | 2     |            | [FE43558C7A](<Server/Dell/PowerEdge/PowerEdge T440/B0AF20400020/UBUNTU-20.04/5.4.0-88-GENERIC/X86_64/FE43558C7A>) |
| 8086:a1a4 | 1028:07e5 | Intel            | C620 Series Chipset Family SPI Co... | 2     |            | [4C88B2E09B](<Server/Dell/PowerEdge/PowerEdge T640/56D8A440BA81/UBUNTU-18.04/5.4.0-47-GENERIC/X86_64/4C88B2E09B>) |
| 8086:a1a4 | 15d9:091c | Intel            | C620 Series Chipset Family SPI Co... | 2     |            | [748FB8054B](<Server/Supermicro/SYS-1029/SYS-1029U-TR25M/29100DD815C0/DEBIAN-10/4.19.0-9-AMD64/X86_64/748FB8054B>) |
| 8086:a1a4 | 15d9:0941 | Intel            | C620 Series Chipset Family SPI Co... | 2     |            | [C619DB847B](<Server/Supermicro/Super/Super Server/FC9F112D0567/XUBUNTU-18.04/4.15.0-112-LOWLATENCY/X86_64/C619DB847B>) |
| 8086:a1a4 | 15d9:0986 | Intel            | C620 Series Chipset Family SPI Co... | 2     |            | [9A0AAAD7ED](<Server/Prime Computer/Server/Server Pro/289FB0C396A8/UBUNTU-20.04/5.4.0-99-GENERIC/X86_64/9A0AAAD7ED>) |
| 8086:a1a4 | 17aa:7800 | Intel            | C620 Series Chipset Family SPI Co... | 2     |            | [928EE22E71](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 -[7X06CTO1WW]-/5D8AB08CFEB3/CENTOS-7/3.10.0-1160.21.1.EL7.X86_64/X86_64/928EE22E71>) |
| 8086:a324 | 1028:0890 | Intel            | Cannon Lake PCH SPI Controller       | 2     |            | [13E5EC2882](<Server/Dell/PowerEdge/PowerEdge T340/F59FB860259E/GENTOO-2.7/5.8.0-RC4-X86_64/X86_64/13E5EC2882>) |
| 8086:a324 | 15d9:099e | Intel            | Cannon Lake PCH SPI Controller       | 2     |            | [B943041FBF](<Server/Supermicro/C9/C9Z390-PGW/A268B798E65F/KALI-2021.3/5.14.0-KALI2-AMD64/X86_64/B943041FBF>) |
| 8086:a324 | 15d9:1b09 | Intel            | Cannon Lake PCH SPI Controller       | 2     | intel_s... | [FFC55DBFA7](<Server/Supermicro/Super/Super Server/A61851B3D7CC/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/FFC55DBFA7>) |
| 8086:a368 | 15d9:099e | Intel            | Cannon Lake PCH Serial IO I2C Con... | 2     | intel_l... | [B943041FBF](<Server/Supermicro/C9/C9Z390-PGW/A268B798E65F/KALI-2021.3/5.14.0-KALI2-AMD64/X86_64/B943041FBF>) |
| 8086:a368 | 15d9:1b09 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 2     | intel_l... | [FFC55DBFA7](<Server/Supermicro/Super/Super Server/A61851B3D7CC/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/FFC55DBFA7>) |
| 8086:a369 | 15d9:099e | Intel            | Cannon Lake PCH Serial IO I2C Con... | 2     | intel_l... | [B943041FBF](<Server/Supermicro/C9/C9Z390-PGW/A268B798E65F/KALI-2021.3/5.14.0-KALI2-AMD64/X86_64/B943041FBF>) |
| 8086:a369 | 15d9:1b09 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 2     | intel_l... | [FFC55DBFA7](<Server/Supermicro/Super/Super Server/A61851B3D7CC/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/FFC55DBFA7>) |

### Serial controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a1bd | 1028:073a | Intel            | C620 Series Chipset Family KT Red... | 7     | serial     | [113B5E448D](<Server/Dell/Precision/Precision 7920 Tower/7523CA2C9CDA/UBUNTU-18.04/5.4.0-80-GENERIC/X86_64/113B5E448D>) |
| 8086:a13d | 15d9:0895 | Intel            | 100 Series/C230 Series Chipset Fa... | 5     | serial     | [79E6EAFC82](<Server/Supermicro/Super/Super Server/EA582B67D89D/DEBIAN-11/5.13.19-2-PVE/X86_64/79E6EAFC82>) |
| 8086:a363 | 8086:7270 | Intel            | Cannon Lake PCH Active Management... | 5     | serial     | [4A717F6348](<Server/Neousys Technology/Nuvo-8208GC/Nuvo-8208GC Series/02E83AA0CBB0/GENTOO-2.8/5.16.5-GENTOO/X86_64/4A717F6348>) |
| 8086:8c3d | 15d9:0805 | Intel            | 8 Series/C220 Series Chipset Fami... | 4     | serial     | [019914CC29](<Server/Supermicro/X10/X10SAE/6D8BBA911035/GENTOO-2.7/5.13.12-GENTOO/X86_64/019914CC29>) |
| 8086:a13d | 8086:1999 | Intel            | 100 Series/C230 Series Chipset Fa... | 3     | serial     | [03F2D30DF2](<Server/HPE/ML10/ML10Gen9/5368299CD3DB/UBUNTU-MATE-21.10/5.13.0-23-GENERIC/X86_64/03F2D30DF2>) |
| 8086:a1bd | 1028:0739 | Intel            | C620 Series Chipset Family KT Red... | 3     | serial     | [5A2FCB7023](<Server/Dell/Precision/Precision 7820 Tower/8AAB146ACE98/LINUXMINT-20/5.4.0-91-GENERIC/X86_64/5A2FCB7023>) |
| 8086:a1bd | 17aa:1038 | Intel            | C620 Series Chipset Family KT Red... | 3     | serial     | [5658A2FB98](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC003KUS/DD1C32AB7122/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/5658A2FB98>) |
| 8086:a13d | 15d9:089f | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | serial     | [ECB9EC0D34](<Server/Supermicro/Super/Super Server/D5D09C37A0C7/ARCO-ROLLING/5.15.19-XANMOD1-TT-1/X86_64/ECB9EC0D34>) |
| 9710:9865 | a000:1000 | MosChip Semic... | PCI 9865 Multi-I/O Controller        | 2     | parport_pc | [715B40D8B6](<Server/Intel/S5000/S5000XVN/187007C30239/FEDORA-34/5.14.12-200.FC34.X86_64/X86_64/715B40D8B6>) |
| 10ee:4b87 | 10ee:4350 | Xilinx           | Serial controller                    | 1     | xclmgmt    | [7026C20C97](<Server/Supermicro/Super/Super Server/007236A7EB64/UBUNTU-16.04/4.13.0-36-GENERIC/X86_64/7026C20C97>) |
| 10ee:4b88 | 10ee:4350 | Xilinx           | Serial controller                    | 1     | xocl       | [7026C20C97](<Server/Supermicro/Super/Super Server/007236A7EB64/UBUNTU-16.04/4.13.0-36-GENERIC/X86_64/7026C20C97>) |
| 1393:1024 | 1393:1024 | Moxa Technolo... | CP-102E (2-port RS-232 Smart PCI ... | 1     | serial     | [9C8826C0D2](<Server/Dell/PowerEdge/PowerEdge T110/31B8C6D71C1F/UBUNTU-20.04/5.4.0-89-GENERIC/X86_64/9C8826C0D2>) |
| 1415:9501 | 131f:2050 | Oxford Semico... | OX16PCI954 (Quad 16950 UART) func... | 1     | serial     | [80DC2F8936](<Server/Supermicro/Super/Super Server/A9CFB59D8528/OPENSUSE-LEAP-42.1/4.1.39-56-DEFAULT/X86_64/80DC2F8936>) |
| 1415:c158 | 1415:c158 | Oxford Semico... | OXPCIe952 Dual Native 950 UART       | 1     | serial     | [352FEE0E7F](<Server/HPE/ProLiant/ProLiant DL360 Gen10/0438CFCFB022/DEBIAN-10/4.19.0-8-AMD64/X86_64/352FEE0E7F>) |
| 1415:c208 | 1415:c208 | Oxford Semico... | OXPCIe954 Quad Native 950 UART       | 1     | serial     | [375EC8881D](<Server/Neousys Technology/Nuvo-8208GC/Nuvo-8208GC Series/78293157040C/UBUNTU-18.04/5.4.0-53-GENERIC/X86_64/375EC8881D>) |
| 8086:1d3d | 152d:8988 | Intel            | C600/X79 series chipset KT Contro... | 1     | serial     | [E0EF143493](<Server/Quanta/Freedom/Freedom/53CBFD82B356/LINUXMINT-19.3/5.0.0-32-GENERIC/X86_64/E0EF143493>) |
| 8086:8c3d | 15d9:0654 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | serial     | [AE67700E54](<Server/Supermicro/X10/X10SLQ/A28F497601BF/FEDORA-33/5.9.13-200.FC33.X86_64/X86_64/AE67700E54>) |
| 8086:8d3d | 1458:1000 | Intel            | C610/X99 series chipset KT Contro... | 1     | serial     | [2F69A2F89C](<Server/Dedicated Computing/OEM-F7342/OEM-F7342-00/A56806D283ED/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/2F69A2F89C>) |
| 8086:a13d | 15d9:0907 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | serial     | [66EE0BC524](<Server/Supermicro/Super/Super Server/40D662EC15C8/UBUNTU-18.04/4.15.0-143-GENERIC/X86_64/66EE0BC524>) |
| 8086:a13d | 8086:a13d | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | serial     | [E86E339278](<Server/Neousys Technology/Nuvo-5100/Nuvo-5100VTC/E9F17F7D3348/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/E86E339278>) |
| 8086:a1bd | 1734:1230 | Intel            | C620 Series Chipset Family KT Red... | 1     | serial     | [86AB491564](<Server/Fujitsu/CELSIUS/CELSIUS R970/7E07629658CC/CENTOS-8/4.18.0-240.10.1.EL8_3.X86_64/X86_64/86AB491564>) |
| 8086:a1bd | 17aa:1037 | Intel            | C620 Series Chipset Family KT Red... | 1     | serial     | [41249F2E48](<Server/Lenovo/ThinkStation/ThinkStation P720 30BBS1PF00/41BFB52F3B1A/FEDORA-32/5.11.11-100.FC32.X86_64/X86_64/41249F2E48>) |
| 9710:9904 | a000:1000 | MosChip Semic... | 4-Port PCIe Serial Adapter           | 1     | serial     | [22A316E31B](<Server/Neousys Technology/Nuvo-8208GC/Nuvo-8208GC Series/78293157040C/UBUNTU-18.04/5.4.0-52-GENERIC/X86_64/22A316E31B>) |
| 9710:9922 | a000:1000 | MosChip Semic... | MCS9922 PCIe Multi-I/O Controller    | 1     | serial     | [7479576DA8](<Server/Supermicro/Super/Super Server/95B1AD8FBD26/ROSA-2014.1/4.1.34-NRJ-DESKTOP-2ROSA-X86_64/X86_64/7479576DA8>) |

### Signal processing (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0e30 | 1028:04f6 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 1     | ivbep_u... | [0FC3F83656](<Server/Dell/PowerEdge/PowerEdge R520/92ADF18337FF/CENTOS-7/3.10.0-957.12.2.EL7.X86_64/X86_64/0FC3F83656>) |
| 8086:0e34 | 1028:04f6 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 1     | ivbep_u... | [0FC3F83656](<Server/Dell/PowerEdge/PowerEdge R520/92ADF18337FF/CENTOS-7/3.10.0-957.12.2.EL7.X86_64/X86_64/0FC3F83656>) |
| 8086:0e36 | 1028:04f6 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 1     | ivbep_u... | [0FC3F83656](<Server/Dell/PowerEdge/PowerEdge R520/92ADF18337FF/CENTOS-7/3.10.0-957.12.2.EL7.X86_64/X86_64/0FC3F83656>) |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a1b1 | 8086:35ce | Intel            | C620 Series Chipset Family Therma... | 20    |            | [36C4ACAC2D](<Server/Intel/S2600/S2600WFT/8DC9639F1DBF/ROCKY-8.4/4.18.0-305.10.2.EL8_4.X86_64/X86_64/36C4ACAC2D>) |
| 8086:a1b1 | 8086:7270 | Intel            | C620 Series Chipset Family Therma... | 20    |            | [73518731A1](<Server/Supermicro/X11/X11DPi-N/6D6FD3049691/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/73518731A1>) |
| 8086:1d24 | 15d9:0636 | Intel            | C600/X79 series chipset Thermal M... | 13    |            | [31684AD7E4](<Server/Supermicro/X9/X9DRW/55D2AD4AF0CF/UBUNTU-21.04/5.11.0-44-GENERIC/X86_64/31684AD7E4>) |
| 8086:a131 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 13    | intel_p... | [7C1FA00B21](<Server/Intel/S1200/S1200SP/4B4C83B49974/CENTOS-7/4.4.241-1.EL7.ELREPO.X86_64/X86_64/7C1FA00B21>) |
| 8086:a1b1 | 1028:073a | Intel            | C620 Series Chipset Family Therma... | 11    |            | [2E5507B849](<Server/Dell/Precision/Precision 7920 Tower/6DBFD1DBD45A/UBUNTU-20.04/5.10.0-1055-OEM/X86_64/2E5507B849>) |
| 8086:a1b1 | 1043:871e | Intel            | C620 Series Chipset Family Therma... | 9     | intel_p... | [3035FDAD91](<Server/ASUSTek Computer/WS-C621E-SAGE/WS-C621E-SAGE Series/E86AFFE0F80D/KUBUNTU-20.04/5.4.0-97-GENERIC/X86_64/3035FDAD91>) |
| 8086:8c24 | 15d9:0801 | Intel            | 8 Series Chipset Family Thermal M... | 8     | intel_p... | [84ED224F36](<Server/Supermicro/X10/X10SLL-F/34D1B7FAB08F/ALPINE-3.12.7/5.4.111-0-LTS/X86_64/84ED224F36>) |
| 8086:8d24 | 15d9:0857 | Intel            | C610/X99 series chipset Thermal S... | 8     |            | [6A333A499D](<Server/Supermicro/X10/X10SRA/0DAF404C22AB/GENTOO-2.7/5.14.14-GENTOO-X86_64/X86_64/6A333A499D>) |
| 8086:a1b1 | 15d9:096d | Intel            | C620 Series Chipset Family Therma... | 8     | intel_p... | [2CDAC4454D](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.16.8-051608-GENERIC/X86_64/2CDAC4454D>) |
| 8086:8c24 | 8086:35b5 | Intel            | 8 Series Chipset Family Thermal M... | 7     | intel_p... | [F257C969DA](<Server/Intel/S1200/S1200RP/F49E27D3A7F1/DEBIAN-11/5.10.0-9-AMD64/X86_64/F257C969DA>) |
| 8086:a1b1 | 1590:00eb | Intel            | C620 Series Chipset Family Therma... | 7     |            | [7AB4F05613](<Server/HPE/ProLiant/ProLiant DL360 Gen10/4443D3087423/UBUNTU-18.04/4.15.0-135-GENERIC/X86_64/7AB4F05613>) |
| 8086:a1b1 | 17aa:7808 | Intel            | C620 Series Chipset Family Therma... | 7     |            | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 8086:1d24 | 15d9:062a | Intel            | C600/X79 series chipset Thermal M... | 6     |            | [7F43788673](<Server/Supermicro/X9/X9SRA-X9SRA-3/E419ADCAE2D8/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/7F43788673>) |
| 8086:a131 | 1028:06a5 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     | intel_p... | [C8D2D41009](<Server/Dell/PowerEdge/PowerEdge R230/5B911C7AB359/UBUNTU-20.04/5.4.0-97-GENERIC/X86_64/C8D2D41009>) |
| 19e5:1710 | 19e5:0000 | Huawei Techno... | iBMA Virtual Network Adapter         | 5     |            | [AD903545CE](<Server/Huawei/2288H/2288H V5/94600F3C6456/ALT-9.1/5.4.51-STD-DEF-ALT1/X86_64/AD903545CE>) |
| 8086:1d24 | 15d9:0626 | Intel            | C600/X79 series chipset Thermal M... | 5     |            | [DE8D4D24B6](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/050383036EDE/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/DE8D4D24B6>) |
| 8086:8c24 | 15d9:0805 | Intel            | 8 Series Chipset Family Thermal M... | 5     | intel_p... | [019914CC29](<Server/Supermicro/X10/X10SAE/6D8BBA911035/GENTOO-2.7/5.13.12-GENTOO/X86_64/019914CC29>) |
| 8086:8c24 | 15d9:086d | Intel            | 8 Series Chipset Family Thermal M... | 5     | intel_p... | [12DB3650F6](<Server/Supermicro/Super/Super Server/51A56BB4E7AB/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/12DB3650F6>) |
| 8086:8c24 | 15d9:0921 | Intel            | 8 Series Chipset Family Thermal M... | 5     | intel_p... | [E60EC405AF](<Server/Supermicro/Super/Super Server/F5F261808B48/GENTOO-2.6/5.15.19-GENTOO/X86_64/E60EC405AF>) |
| 8086:a131 | 15d9:0895 | Intel            | 100 Series/C230 Series Chipset Fa... | 5     | intel_p... | [79E6EAFC82](<Server/Supermicro/Super/Super Server/EA582B67D89D/DEBIAN-11/5.13.19-2-PVE/X86_64/79E6EAFC82>) |
| 8086:a1b1 | 1028:0715 | Intel            | C620 Series Chipset Family Therma... | 5     |            | [FCC6D41C03](<Server/Dell/PowerEdge/PowerEdge R740/203EBCE27AC6/CENTOS-7/3.10.0-1160.45.1.EL7.X86_64/X86_64/FCC6D41C03>) |
| 8086:a1b1 | 1028:0739 | Intel            | C620 Series Chipset Family Therma... | 5     |            | [5A2FCB7023](<Server/Dell/Precision/Precision 7820 Tower/8AAB146ACE98/LINUXMINT-20/5.4.0-91-GENERIC/X86_64/5A2FCB7023>) |
| 8086:a1b1 | 15d9:0981 | Intel            | C620 Series Chipset Family Therma... | 5     | intel_p... | [1A73C74FBB](<Server/Supermicro/Super/Super Server/909986EADB14/UBUNTU-21.04/5.11.0-38-GENERIC/X86_64/1A73C74FBB>) |
| 8086:a1b1 | 1849:a1b1 | Intel            | C620 Series Chipset Family Therma... | 5     | intel_p... | [BAA2C57359](<Server/ASRockRack/EPC621/EPC621D8A/5678CB93815F/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/BAA2C57359>) |
| 8086:a379 | 8086:7270 | Intel            | Cannon Lake PCH Thermal Controller   | 5     | intel_p... | [4A717F6348](<Server/Neousys Technology/Nuvo-8208GC/Nuvo-8208GC Series/02E83AA0CBB0/GENTOO-2.8/5.16.5-GENTOO/X86_64/4A717F6348>) |
| 8086:8c24 | 8086:0000 | Intel            | 8 Series Chipset Family Thermal M... | 4     | intel_p... | [7023226F81](<Server/Intel/S1200/S1200RP/832EB05B058D/FEDORA-35/5.16.2-200.FC35.X86_64/X86_64/7023226F81>) |
| 8086:8d24 | 15d9:0831 | Intel            | C610/X99 series chipset Thermal S... | 4     |            | [58E86F0E34](<Server/Supermicro/Super/Super Server/BD4C9B6F043B/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/58E86F0E34>) |
| 8086:a131 | 15d9:089a | Intel            | 100 Series/C230 Series Chipset Fa... | 4     | intel_p... | [E8634FF947](<Server/Supermicro/Super/Super Server/0EC007042E2B/DEBIAN-9/4.15.18-12-PVE/X86_64/E8634FF947>) |
| 8086:a160 | 15d9:0895 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     | intel_l... | [79E6EAFC82](<Server/Supermicro/Super/Super Server/EA582B67D89D/DEBIAN-11/5.13.19-2-PVE/X86_64/79E6EAFC82>) |
| 8086:a161 | 15d9:0895 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     | intel_l... | [79E6EAFC82](<Server/Supermicro/Super/Super Server/EA582B67D89D/DEBIAN-11/5.13.19-2-PVE/X86_64/79E6EAFC82>) |
| 8086:a1b1 | 103c:81c7 | Intel            | C620 Series Chipset Family Therma... | 4     |            | [5299B4DA87](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/68BC2092E093/UBUNTU-18.04/5.4.0-74-GENERIC/X86_64/5299B4DA87>) |
| 8086:a1b1 | 15d9:0953 | Intel            | C620 Series Chipset Family Therma... | 4     |            | [A76BB2E30D](<Server/Supermicro/SYS-5029/SYS-5029P-WTR/2D889DFAC2FF/ROCKY-8.5/4.18.0-348.12.2.EL8_5.X86_64/X86_64/A76BB2E30D>) |
| 8086:a379 | 15d9:1a1d | Intel            | Cannon Lake PCH Thermal Controller   | 4     | intel_p... | [B850CD60F6](<Server/Acord-92/PCplus/PCplus T600-C246/CC2E95E1BC69/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B850CD60F6>) |
| 8086:8d24 | 1458:0000 | Intel            | C610/X99 series chipset Thermal S... | 3     |            | [2F69A2F89C](<Server/Dedicated Computing/OEM-F7342/OEM-F7342-00/A56806D283ED/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/2F69A2F89C>) |
| 8086:8d24 | 1d49:0000 | Intel            | C610/X99 series chipset Thermal S... | 3     |            | [3510DD7B10](<Server/Lenovo/System/System x3650 M5: -[8871AC1]-/A8B0683FFC4F/CENTOS-7/3.10.0-862.14.4.EL7.X86_64/X86_64/3510DD7B10>) |
| 8086:a1b1 | 1028:0716 | Intel            | C620 Series Chipset Family Therma... | 3     |            | [E752263E49](<Server/Dell/PowerEdge/PowerEdge R640/1917FF5F0757/CENTOS-7/3.10.0-957.21.3.EL7.X86_64/X86_64/E752263E49>) |
| 8086:a1b1 | 1028:0718 | Intel            | C620 Series Chipset Family Therma... | 3     | intel_p... | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:a1b1 | 103c:81c6 | Intel            | C620 Series Chipset Family Therma... | 3     |            | [679871CFEC](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/E621F1A07D2C/UBUNTU-20.04/5.4.0-84-GENERIC/X86_64/679871CFEC>) |
| 8086:a1b1 | 15d9:095d | Intel            | C620 Series Chipset Family Therma... | 3     |            | [C682299C13](<Server/Supermicro/X11/X11-SPM-TF/17F67170A1AB/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/C682299C13>) |
| 8086:a1b1 | 17aa:1038 | Intel            | C620 Series Chipset Family Therma... | 3     |            | [5658A2FB98](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC003KUS/DD1C32AB7122/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/5658A2FB98>) |
| 8086:a379 | 1028:088e | Intel            | Cannon Lake PCH Thermal Controller   | 3     | intel_p... | [2A87802C58](<Server/Dell/PowerEdge/PowerEdge R340/89867B3F61A1/DEBIAN-9/4.9.0-14-AMD64/X86_64/2A87802C58>) |
| 8086:a379 | 15d9:1a1b | Intel            | Cannon Lake PCH Thermal Controller   | 3     | intel_p... | [F1BF9D35EF](<Server/Supermicro/SYS-5039/SYS-5039MC-H12TRF/C2156B6F043C/DEBIAN-10/5.4.98-1-PVE/X86_64/F1BF9D35EF>) |
| 8086:a379 | 15d9:1a1f | Intel            | Cannon Lake PCH Thermal Controller   | 3     | intel_p... | [34B9B698CD](<Server/Supermicro/Super/Super Server/617C605D5B8B/DEBIAN-11/5.10.0-9-AMD64/X86_64/34B9B698CD>) |
| 8086:1d24 | 1014:0000 | Intel            | C600/X79 series chipset Thermal M... | 2     |            | [C717BB4AC6](<Server/IBM/System/System X iDataPlex dx360 M4 Server -[7912AC1]-/E15173785994/UBUNTU-18.04/4.15.0-166-GENERIC/X86_64/C717BB4AC6>) |
| 8086:1d24 | 15d9:062b | Intel            | C600/X79 series chipset Thermal M... | 2     |            | [FD24B5D375](<Server/Supermicro/X9/X9SRE-X9SRE-3F-X9SRi-X9SRi-3F/B81C423EDCC3/DEBIAN-10/4.19.0-10-AMD64/X86_64/FD24B5D375>) |
| 8086:1d24 | 15d9:0660 | Intel            | C600/X79 series chipset Thermal M... | 2     |            | [AFE42B7E58](<Server/SYNNEX/HYVE-ZEUS/HYVE-ZEUS/3AD7D5C11C7F/DEBIAN-10/5.4.34-1-PVE/X86_64/AFE42B7E58>) |
| 8086:1d24 | 15d9:0702 | Intel            | C600/X79 series chipset Thermal M... | 2     |            | [4DC142D672](<Server/Supermicro/X9/X9DRD-7LN4F-X9DRD-EF/A67A7A3867A4/UBUNTU-20.04/5.4.0-81-GENERIC/X86_64/4DC142D672>) |
| 8086:8c24 | 15d9:0803 | Intel            | 8 Series Chipset Family Thermal M... | 2     | intel_p... | [869444ACF6](<Server/Supermicro/X10/X10SLH-F-X10SLM+-F/F237C21493F8/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/869444ACF6>) |
| 8086:8d24 | 8086:8d24 | Intel            | C610/X99 series chipset Thermal S... | 2     |            | [2903921AEB](<Server/AIC/SB302/SB302-LB/98EDCF68ED2D/CENTOS-8/4.18.0-80.EL8.X86_64/X86_64/2903921AEB>) |
| 8086:a131 | 15d9:088b | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | intel_p... | [C0E1C15247](<Server/Supermicro/C7/C7Z170-M/5D50FA33A353/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/C0E1C15247>) |

### Signal processing management (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19a2:0800 | 19a2:0800 | Emulex           | ServerView iRMC HTI                  | 1     |            | [14C76E0C83](<Server/F5 Networks/C/C117/C1512B26FE54/ALPINE-3.13.2/5.10.16-0-LTS/X86_64/14C76E0C83>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a1a3 | 8086:7270 | Intel            | C620 Series Chipset Family SMBus     | 20    | i2c_i801   | [73518731A1](<Server/Supermicro/X11/X11DPi-N/6D6FD3049691/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/73518731A1>) |
| 8086:a1a3 | 8086:35ce | Intel            | C620 Series Chipset Family SMBus     | 19    | i2c_i801   | [36C4ACAC2D](<Server/Intel/S2600/S2600WFT/8DC9639F1DBF/ROCKY-8.4/4.18.0-305.10.2.EL8_4.X86_64/X86_64/36C4ACAC2D>) |
| 8086:8d22 | 15d9:0821 | Intel            | C610/X99 series chipset SMBus Con... | 17    | i2c_i801   | [AAEEE85BE7](<Server/Supermicro/SYS-6028/SYS-6028R-WTRT/690B86B530B0/DEBIAN-11/4.19.0-17-AMD64/X86_64/AAEEE85BE7>) |
| 8086:1d22 | 1043:84ef | Intel            | C600/X79 series chipset SMBus Hos... | 16    | i2c_i801   | [0D39F4F066](<Server/ASUSTek Computer/Z9PE-D16/Z9PE-D16 Series/7948CC9F2801/UBUNTU-18.04/5.4.0-91-GENERIC/X86_64/0D39F4F066>) |
| 8086:3a30 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 16    | i2c_i801   | [89D676AF03](<Server/Supermicro/X8/X8DTL/6E7DE9F9FEDC/DEBIAN-11/5.10.0-11-AMD64/X86_64/89D676AF03>) |
| 1022:790b | 1022:790b | AMD              | FCH SMBus Controller                 | 13    | i2c_piix4  | [F7739E263E](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/05C34CB58FDD/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/F7739E263E>) |
| 1022:790b | 15d9:790b | AMD              | FCH SMBus Controller                 | 13    | i2c_piix4  | [4798AC1234](<Server/Supermicro/Super/Super Server/4CD86DE2F12F/UBUNTU-20.04/5.4.0-84-GENERIC/X86_64/4798AC1234>) |
| 8086:1d22 | 15d9:0636 | Intel            | C600/X79 series chipset SMBus Hos... | 13    | i2c_i801   | [31684AD7E4](<Server/Supermicro/X9/X9DRW/55D2AD4AF0CF/UBUNTU-21.04/5.11.0-44-GENERIC/X86_64/31684AD7E4>) |
| 8086:a123 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 13    | i2c_i801   | [7C1FA00B21](<Server/Intel/S1200/S1200SP/4B4C83B49974/CENTOS-7/4.4.241-1.EL7.ELREPO.X86_64/X86_64/7C1FA00B21>) |
| 8086:8d22 | 103c:8030 | Intel            | C610/X99 series chipset SMBus Con... | 12    | i2c_i801   | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 8086:8d22 | 8086:7270 | Intel            | C610/X99 series chipset SMBus Con... | 11    | i2c_i801   | [50AEBE4B28](<Server/Supermicro/SSG-6048/SSG-6048R-E1CR24H/8A7A52EA4807/CENTOS-8/4.18.0-348.2.1.EL8_5.X86_64/X86_64/50AEBE4B28>) |
| 8086:a1a3 | 1028:073a | Intel            | C620 Series Chipset Family SMBus     | 11    | i2c_i801   | [2E5507B849](<Server/Dell/Precision/Precision 7920 Tower/6DBFD1DBD45A/UBUNTU-20.04/5.10.0-1055-OEM/X86_64/2E5507B849>) |
| 8086:3a30 | 1014:3a30 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 10    | i2c_i801   | [76A0EBBFC4](<Server/IBM/System/System x3550 M3 -[7944KAG]-/E6F6F92CA768/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/76A0EBBFC4>) |
| 8086:1d22 | 1014:1d22 | Intel            | C600/X79 series chipset SMBus Hos... | 9     | i2c_i801   | [C717BB4AC6](<Server/IBM/System/System X iDataPlex dx360 M4 Server -[7912AC1]-/E15173785994/UBUNTU-18.04/4.15.0-166-GENERIC/X86_64/C717BB4AC6>) |
| 8086:a1a3 | 1043:871e | Intel            | C620 Series Chipset Family SMBus     | 9     | i2c_i801   | [3035FDAD91](<Server/ASUSTek Computer/WS-C621E-SAGE/WS-C621E-SAGE Series/E86AFFE0F80D/KUBUNTU-20.04/5.4.0-97-GENERIC/X86_64/3035FDAD91>) |
| 1022:790b | 1458:1000 | AMD              | FCH SMBus Controller                 | 8     | i2c_piix4  | [6D2EE30F72](<Server/Gigabyte Technology/MZ71/MZ71-CE0-00/74E7E16574F5/UBUNTU-MATE-20.04/5.11.0-43-GENERIC/X86_64/6D2EE30F72>) |
| 8086:1c22 | 1028:04de | Intel            | 6 Series/C200 Series Chipset Fami... | 8     | i2c_i801   | [D95EA030FF](<Server/Dell/PowerEdge/PowerEdge T110 II/2E5934354FEE/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/D95EA030FF>) |
| 8086:8c22 | 15d9:0801 | Intel            | 8 Series/C220 Series Chipset Fami... | 8     | i2c_i801   | [84ED224F36](<Server/Supermicro/X10/X10SLL-F/34D1B7FAB08F/ALPINE-3.12.7/5.4.111-0-LTS/X86_64/84ED224F36>) |
| 8086:8c22 | 8086:35b5 | Intel            | 8 Series/C220 Series Chipset Fami... | 8     | i2c_i801   | [7023226F81](<Server/Intel/S1200/S1200RP/832EB05B058D/FEDORA-35/5.16.2-200.FC35.X86_64/X86_64/7023226F81>) |
| 8086:8d22 | 15d9:0857 | Intel            | C610/X99 series chipset SMBus Con... | 8     | i801_smbus | [6A333A499D](<Server/Supermicro/X10/X10SRA/0DAF404C22AB/GENTOO-2.7/5.14.14-GENTOO-X86_64/X86_64/6A333A499D>) |
| 8086:a1a3 | 15d9:096d | Intel            | C620 Series Chipset Family SMBus     | 8     | i2c_i801   | [2CDAC4454D](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.16.8-051608-GENERIC/X86_64/2CDAC4454D>) |
| 1002:4385 | 15d9:bc11 | AMD              | SBx00 SMBus Controller               | 7     | i2c_piix4  | [AA1C79AB75](<Server/Supermicro/H8/H8DG6-H8DGi/49F6AA867D33/ARCH/5.16.5-ARCH1-1/X86_64/AA1C79AB75>) |
| 8086:3a30 | 15d9:0400 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 7     | i2c_i801   | [AD4ABE60CD](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/03637143A526/XUBUNTU-20.04/5.11.0-37-GENERIC/X86_64/AD4ABE60CD>) |
| 8086:3a30 | 8086:34dc | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 7     | i801_smbus | [A30DCB5033](<Server/Intel/S5520/S5520HC/5E89F6CD026C/ZORIN-16/5.11.0-40-GENERIC/X86_64/A30DCB5033>) |
| 8086:3a30 | 8086:3a30 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 7     | i2c_i801   | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:8c22 | 8086:8c22 | Intel            | 8 Series/C220 Series Chipset Fami... | 7     | i2c_i801   | [9FBB87A829](<Server/VIT/NP3020/NP3020M3/6DA8E8BE5005/DEBIAN-10/4.19.0-18-AMD64/X86_64/9FBB87A829>) |
| 8086:8d22 | 1043:85f6 | Intel            | C610/X99 series chipset SMBus Con... | 7     | i2c_i801   | [4158CB76EF](<Server/ASUSTek Computer/RS400/RS400-E8-PS2-F/B939D9497146/GENTOO-2.7/5.10.14-HARDENED1/X86_64/4158CB76EF>) |
| 8086:8d22 | 15d9:0831 | Intel            | C610/X99 series chipset SMBus Con... | 7     | i2c_i801   | [58E86F0E34](<Server/Supermicro/Super/Super Server/BD4C9B6F043B/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/58E86F0E34>) |
| 8086:a1a3 | 17aa:7808 | Intel            | C620 Series Chipset Family SMBus     | 7     | i2c_i801   | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 1002:4385 | 15d9:ab11 | AMD              | SBx00 SMBus Controller               | 6     | i2c_piix4  | [D5563E325C](<Server/Supermicro/H8/H8QG6/58E82626C3C5/KUBUNTU-20.04/5.4.0-73-GENERIC/X86_64/D5563E325C>) |
| 8086:1c22 | 1043:8497 | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | i2c_i801   | [8A2FB874FE](<Server/ASUSTek Computer/P8B-M/P8B-M Series/38C22118911E/UBUNTU-20.04/5.4.157-1-PVE/X86_64/8A2FB874FE>) |
| 8086:1c22 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | i2c_i801   | [0051160B0D](<Server/Intel/S1200/S1200BTL/A063843D6E74/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/0051160B0D>) |
| 8086:1d22 | 15d9:062a | Intel            | C600/X79 series chipset SMBus Hos... | 6     | i2c_i801   | [7F43788673](<Server/Supermicro/X9/X9SRA-X9SRA-3/E419ADCAE2D8/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/7F43788673>) |
| 8086:2930 | 8086:34d0 | Intel            | 82801I (ICH9 Family) SMBus Contro... | 6     | i2c_i801   | [FC38CA11F5](<Server/Intel/S3210/S3210SH/5BCC9327A8D8/UBUNTU-20.04/5.8.0-53-GENERIC/X86_64/FC38CA11F5>) |
| 8086:3a30 | 15d9:0001 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 6     | i2c_i801   | [AFA93003E2](<Server/Supermicro/X8/X8DT3/B53F2D96B315/DEBIAN-10/5.4.128-1-PVE/X86_64/AFA93003E2>) |
| 8086:3a30 | 1734:114d | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 6     | i2c_i801   | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:a123 | 1028:06a5 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     | i2c_i801   | [C8D2D41009](<Server/Dell/PowerEdge/PowerEdge R230/5B911C7AB359/UBUNTU-20.04/5.4.0-97-GENERIC/X86_64/C8D2D41009>) |
| 1002:4385 | 1028:0444 | AMD              | SBx00 SMBus Controller               | 5     | i2c_piix4  | [FBE32ACA1D](<Server/Dell/PowerEdge/PowerEdge R815/D106BA160A7C/DEBIAN-UNSTABLE/5.16.0-RC8-AMD64/X86_64/FBE32ACA1D>) |
| 8086:1c22 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 5     | i2c_i801   | [E0E68EFC2F](<Server/Dell/PowerEdge/PowerEdge R210 II/D6DEF28F8714/UBUNTU-18.04/4.15.0-109-GENERIC/X86_64/E0E68EFC2F>) |
| 8086:1d22 | 15d9:0626 | Intel            | C600/X79 series chipset SMBus Hos... | 5     | i2c_i801   | [DE8D4D24B6](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/050383036EDE/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/DE8D4D24B6>) |
| 8086:3a30 | 15d9:0100 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 5     | i2c_i801   | [C83DC07B7C](<Server/Supermicro/X8/X8DAH/B787FD60BF9A/LINUXMINT-20.1/5.4.0-65-GENERIC/X86_64/C83DC07B7C>) |
| 8086:3a30 | 15d9:0600 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 5     | i2c_i801   | [ACA2A2FFDF](<Server/Supermicro/X8/X8DTU/B1E056AA3422/DEBIAN-10/5.4.73-1-PVE/X86_64/ACA2A2FFDF>) |
| 8086:3a30 | 8086:34da | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 5     | i2c_i801   | [F9F8DD79F5](<Server/Intel/S5500/S5500BC/FF348A4732B6/DEBIAN-9/4.15.18-9-PVE/X86_64/F9F8DD79F5>) |
| 8086:3a30 | 8086:34e2 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 5     | i2c_i801   | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:8c22 | 15d9:0805 | Intel            | 8 Series/C220 Series Chipset Fami... | 5     | i801_smbus | [019914CC29](<Server/Supermicro/X10/X10SAE/6D8BBA911035/GENTOO-2.7/5.13.12-GENTOO/X86_64/019914CC29>) |
| 8086:8c22 | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 5     | i2c_i801   | [12DB3650F6](<Server/Supermicro/Super/Super Server/51A56BB4E7AB/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/12DB3650F6>) |
| 8086:8c22 | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 5     | i2c_i801   | [E60EC405AF](<Server/Supermicro/Super/Super Server/F5F261808B48/GENTOO-2.6/5.15.19-GENTOO/X86_64/E60EC405AF>) |
| 8086:a123 | 15d9:0895 | Intel            | 100 Series/C230 Series Chipset Fa... | 5     | i2c_i801   | [79E6EAFC82](<Server/Supermicro/Super/Super Server/EA582B67D89D/DEBIAN-11/5.13.19-2-PVE/X86_64/79E6EAFC82>) |
| 8086:a1a3 | 1028:0715 | Intel            | C620 Series Chipset Family SMBus     | 5     | i2c_i801   | [FCC6D41C03](<Server/Dell/PowerEdge/PowerEdge R740/203EBCE27AC6/CENTOS-7/3.10.0-1160.45.1.EL7.X86_64/X86_64/FCC6D41C03>) |
| 8086:a1a3 | 1028:0739 | Intel            | C620 Series Chipset Family SMBus     | 5     | i2c_i801   | [5A2FCB7023](<Server/Dell/Precision/Precision 7820 Tower/8AAB146ACE98/LINUXMINT-20/5.4.0-91-GENERIC/X86_64/5A2FCB7023>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:3a3e | 15d9:0006 | Intel            | 82801JI (ICH10 Family) HD Audio C... | 11    | snd_hda... | [A1BB16C84F](<Server/Supermicro/X8/X8DTL/350B845C95FD/DEBIAN-11/5.10.0-10-AMD64/X86_64/A1BB16C84F>) |
| 8086:a1f0 | 1028:073a | Intel            | Lewisburg MROM 0                     | 11    | snd_hda... | [2E5507B849](<Server/Dell/Precision/Precision 7920 Tower/6DBFD1DBD45A/UBUNTU-20.04/5.10.0-1055-OEM/X86_64/2E5507B849>) |
| 13f6:0111 | 13f6:0111 | C-Media Elect... | CMI8738/CMI8768 PCI Audio            | 10    | snd_cmipci | [9FBB87A829](<Server/VIT/NP3020/NP3020M3/6DA8E8BE5005/DEBIAN-10/4.19.0-18-AMD64/X86_64/9FBB87A829>) |
| 1102:0012 | 1102:0010 | Creative Labs    | Sound Core3D [Sound Blaster Recon... | 8     | snd_hda... | [D2AA9ED999](<Server/Dell/PowerEdge/PowerEdge SC1430/B7BF150C0263/UBUNTU-18.04/5.4.0-58-GENERIC/X86_64/D2AA9ED999>) |
| 8086:8d20 | 15d9:0857 | Intel            | C610/X99 series chipset HD Audio ... | 8     | snd_hda... | [6A333A499D](<Server/Supermicro/X10/X10SRA/0DAF404C22AB/GENTOO-2.7/5.14.14-GENTOO-X86_64/X86_64/6A333A499D>) |
| 8086:a1f0 | 15d9:096d | Intel            | Lewisburg MROM 0                     | 8     | snd_hda... | [2CDAC4454D](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.16.8-051608-GENERIC/X86_64/2CDAC4454D>) |
| 10de:0e0f | 1462:8c93 | Nvidia           | GK208 HDMI/DP Audio Controller       | 7     | snd_hda... | [4DC142D672](<Server/Supermicro/X9/X9DRD-7LN4F-X9DRD-EF/A67A7A3867A4/UBUNTU-20.04/5.4.0-81-GENERIC/X86_64/4DC142D672>) |
| 8086:1d20 | 1043:84d8 | Intel            | C600/X79 series chipset High Defi... | 7     | snd_hda... | [C3665EBF57](<Server/ASUSTek Computer/Z9PE-D8/Z9PE-D8 WS/5BADF976211F/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/C3665EBF57>) |
| 1002:aae0 | 1002:aae0 | AMD              | Baffin HDMI/DP Audio [Radeon RX 5... | 6     | snd_hda... | [0E264C593F](<Server/Phytium/FT-2000/FT-2000-4/2114858A8611/DEBIAN-11/5.15.0-0.BPO.2-RT-ARM64/AARCH64/0E264C593F>) |
| 1002:aaf8 | 1002:aaf8 | AMD              | Vega 10 HDMI Audio [Radeon Vega 5... | 6     | snd_hda... | [AA1C79AB75](<Server/Supermicro/H8/H8DG6-H8DGi/49F6AA867D33/ARCH/5.16.5-ARCH1-1/X86_64/AA1C79AB75>) |
| 10de:0e0f | 196e:118b | Nvidia           | GK208 HDMI/DP Audio Controller       | 6     | snd_hda... | [3A68279F78](<Server/IBM/System/System x3650 -[7979AC1]-/D68394872CF7/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/3A68279F78>) |
| 8086:1d20 | 15d9:062a | Intel            | C600/X79 series chipset High Defi... | 6     | snd_hda... | [7F43788673](<Server/Supermicro/X9/X9SRA-X9SRA-3/E419ADCAE2D8/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/7F43788673>) |
| 1002:aab0 | 174b:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 5     | snd_hda... | [7636863C25](<Server/TYAN Computer/S/S7002/2E94F60F60CB/DEBIAN-11/5.10.0-9-AMD64/X86_64/7636863C25>) |
| 8086:1d20 | 1043:851b | Intel            | C600/X79 series chipset High Defi... | 5     | snd_hda... | [0D39F4F066](<Server/ASUSTek Computer/Z9PE-D16/Z9PE-D16 Series/7948CC9F2801/UBUNTU-18.04/5.4.0-91-GENERIC/X86_64/0D39F4F066>) |
| 8086:3a3e | 15d9:0100 | Intel            | 82801JI (ICH10 Family) HD Audio C... | 5     | snd_hda... | [C83DC07B7C](<Server/Supermicro/X8/X8DAH/B787FD60BF9A/LINUXMINT-20.1/5.4.0-65-GENERIC/X86_64/C83DC07B7C>) |
| 8086:3a3e | 8086:34e2 | Intel            | 82801JI (ICH10 Family) HD Audio C... | 5     | snd_hda... | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:8c20 | 15d9:0805 | Intel            | 8 Series/C220 Series Chipset High... | 5     | snd_hda... | [019914CC29](<Server/Supermicro/X10/X10SAE/6D8BBA911035/GENTOO-2.7/5.13.12-GENTOO/X86_64/019914CC29>) |
| 8086:a1f0 | 1028:0739 | Intel            | Lewisburg MROM 0                     | 5     | snd_hda... | [5A2FCB7023](<Server/Dell/Precision/Precision 7820 Tower/8AAB146ACE98/LINUXMINT-20/5.4.0-91-GENERIC/X86_64/5A2FCB7023>) |
| 8086:a348 | 8086:7270 | Intel            | Cannon Lake PCH cAVS                 | 5     | snd_hda... | [4A717F6348](<Server/Neousys Technology/Nuvo-8208GC/Nuvo-8208GC Series/02E83AA0CBB0/GENTOO-2.8/5.16.5-GENTOO/X86_64/4A717F6348>) |
| 1002:aa98 | 1028:aa98 | AMD              | Caicos HDMI Audio [Radeon HD 6450... | 4     | snd_hda... | [5D6883F1BB](<Server/Others/0JP31P/0JP31P A16/77D7AC607011/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/5D6883F1BB>) |
| 1002:aab0 | 1043:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 4     | snd_hda... | [79E6EAFC82](<Server/Supermicro/Super/Super Server/EA582B67D89D/DEBIAN-11/5.13.19-2-PVE/X86_64/79E6EAFC82>) |
| 10de:0e0a | 10de:1096 | Nvidia           | GK104 HDMI Audio Controller          | 4     | snd_hda... | [F508BB4C99](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/40A1E58B45BA/POP!_OS-20.10/5.8.0-7625-GENERIC/X86_64/F508BB4C99>) |
| 8086:0c0c | 15d9:0805 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 4     | snd_hda... | [019914CC29](<Server/Supermicro/X10/X10SAE/6D8BBA911035/GENTOO-2.7/5.13.12-GENTOO/X86_64/019914CC29>) |
| 8086:3a3e | 8086:3a3e | Intel            | 82801JI (ICH10 Family) HD Audio C... | 4     | snd_hda... | [C5F294D367](<Server/TYAN Computer/S/S7025/49F38982A59C/GENTOO-2.8/5.15.12-GENTOO-X86_64/X86_64/C5F294D367>) |
| 8086:a170 | 15d9:0895 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     | snd_hda... | [79E6EAFC82](<Server/Supermicro/Super/Super Server/EA582B67D89D/DEBIAN-11/5.13.19-2-PVE/X86_64/79E6EAFC82>) |
| 8086:a1f0 | 103c:81c7 | Intel            | Lewisburg MROM 0                     | 4     | snd_hda... | [5299B4DA87](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/68BC2092E093/UBUNTU-18.04/5.4.0-74-GENERIC/X86_64/5299B4DA87>) |
| 8086:a1f0 | 1043:8724 | Intel            | Lewisburg MROM 0                     | 4     | snd_hda... | [3035FDAD91](<Server/ASUSTek Computer/WS-C621E-SAGE/WS-C621E-SAGE Series/E86AFFE0F80D/KUBUNTU-20.04/5.4.0-97-GENERIC/X86_64/3035FDAD91>) |
| 8086:a348 | 15d9:1a1d | Intel            | Cannon Lake PCH cAVS                 | 4     | snd_hda... | [B850CD60F6](<Server/Acord-92/PCplus/PCplus T600-C246/CC2E95E1BC69/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B850CD60F6>) |
| 1002:1637 | 1002:1637 | AMD              | Renoir Radeon High Definition Aud... | 3     | snd_hda... | [0AB1FF409B](<Server/BESSTAR Tech/X/X500/A95AE61E36B4/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/0AB1FF409B>) |
| 1002:4383 | 1111:077c | AMD              | SBx00 Azalia (Intel HDA)             | 3     | snd_hda... | [4A83A85932](<Server/AMD/AOPW-PLUS/AOPW-PLUS/B61223D18897/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/4A83A85932>) |
| 1002:9840 | 1002:9840 | AMD              | Kabini HDMI/DP Audio                 | 3     | snd_hda... | [F7739E263E](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/05C34CB58FDD/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/F7739E263E>) |
| 1002:aa68 | 1043:aa68 | AMD              | Cedar HDMI Audio [Radeon HD 5400/... | 3     | snd_hda... | [B8300AFB35](<Server/MSI/MCP/MCP55/8728FA454DA7/UBUNTU-20.04/5.4.0-56-GENERIC/X86_64/B8300AFB35>) |
| 1002:aa68 | 1462:aa68 | AMD              | Cedar HDMI Audio [Radeon HD 5400/... | 3     | snd_hda... | [6D2EE30F72](<Server/Gigabyte Technology/MZ71/MZ71-CE0-00/74E7E16574F5/UBUNTU-MATE-20.04/5.11.0-43-GENERIC/X86_64/6D2EE30F72>) |
| 1002:aa98 | 1462:aa98 | AMD              | Caicos HDMI Audio [Radeon HD 6450... | 3     | snd_hda... | [A30DCB5033](<Server/Intel/S5520/S5520HC/5E89F6CD026C/ZORIN-16/5.11.0-40-GENERIC/X86_64/A30DCB5033>) |
| 1002:aab0 | 1028:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 3     | snd_hda... | [A8902B24DD](<Server/Dell/PowerEdge/PowerEdge R510/7D78A7BA99AA/OPENSUSE-20211107/5.14.14-1-DEFAULT/X86_64/A8902B24DD>) |
| 1002:aae0 | 1682:aae0 | AMD              | Baffin HDMI/DP Audio [Radeon RX 5... | 3     | snd_hda... | [2953317989](<Server/Dell/PowerEdge/PowerEdge T620/525ECA602515/KUBUNTU-21.10/5.13.0-23-LOWLATENCY/X86_64/2953317989>) |
| 1022:15e3 | 14f1:0200 | AMD              | Family 17h/19h HD Audio Controller   | 3     | snd_hda... | [0AB1FF409B](<Server/BESSTAR Tech/X/X500/A95AE61E36B4/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/0AB1FF409B>) |
| 10de:0e0f | 1043:84f5 | Nvidia           | GK208 HDMI/DP Audio Controller       | 3     | snd_hda... | [5D93D067D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G5/1BCCA824D53F/XUBUNTU-19.10/5.4.0-2-GENERIC/X86_64/5D93D067D7>) |
| 10de:0e0f | 1462:8a9f | Nvidia           | GK208 HDMI/DP Audio Controller       | 3     | snd_hda... | [398F8F6326](<Server/Dell/PowerEdge/PowerEdge R810/87DE67442167/LUBUNTU-20.04/5.4.0-96-GENERIC/X86_64/398F8F6326>) |
| 10de:0e0f | 19da:7326 | Nvidia           | GK208 HDMI/DP Audio Controller       | 3     | snd_hda... | [F3CBAC183E](<Server/Dell/PowerEdge/PowerEdge R7515/9A7A286BD3E1/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/F3CBAC183E>) |
| 10de:0e1b | 10de:094b | Nvidia           | GK107 HDMI Audio Controller          | 3     | snd_hda... | [9FBB87A829](<Server/VIT/NP3020/NP3020M3/6DA8E8BE5005/DEBIAN-10/4.19.0-18-AMD64/X86_64/9FBB87A829>) |
| 10de:0fb9 | 1028:11be | Nvidia           | GP107GL High Definition Audio Con... | 3     | snd_hda... | [1567EFE934](<Server/Dell/Precision/Precision 7920 Tower/91A68E33F84B/UBUNTU-20.04/5.8.0-53-GENERIC/X86_64/1567EFE934>) |
| 10de:10f0 | 103c:11a3 | Nvidia           | GP104 High Definition Audio Contr... | 3     | snd_hda... | [9D6E46ECA9](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/2EFC95DF5773/CENTOS-7/3.10.0-957.21.2.EL7.X86_64/X86_64/9D6E46ECA9>) |
| 10de:10f7 | 1458:37c4 | Nvidia           | TU102 High Definition Audio Contr... | 3     | snd_hda... | [F9D0B2BC99](<Server/Supermicro/Super/Super Server/AB17D6414AF9/UBUNTU-18.04/5.3.0-51-GENERIC/X86_64/F9D0B2BC99>) |
| 10de:10f8 | 1028:12a0 | Nvidia           | TU104 HD Audio Controller            | 3     | snd_hda... | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 1102:0007 | 1102:100a | Creative Labs    | CA0106/CA0111 [SB Live!/Audigy/X-... | 3     | snd_ca0106 | [11BB1EE3A2](<Server/Intel/S1200/S1200BTL/C10DA3F7FBBC/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/11BB1EE3A2>) |
| 13f6:8788 | 1043:8521 | C-Media Elect... | CMI8788 [Oxygen HD Audio]            | 3     | snd_oxygen | [9C8826C0D2](<Server/Dell/PowerEdge/PowerEdge T110/31B8C6D71C1F/UBUNTU-20.04/5.4.0-89-GENERIC/X86_64/9C8826C0D2>) |
| 8086:3198 | 1019:a94d | Intel            | Celeron/Pentium Silver Processor ... | 3     | snd_hda... | [9F7F807004](<Server/ECS/LIVA/LIVA Q2/6F0AAEC80AB2/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/9F7F807004>) |
| 8086:a1f0 | 103c:81c6 | Intel            | Lewisburg MROM 0                     | 3     | snd_hda... | [679871CFEC](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/E621F1A07D2C/UBUNTU-20.04/5.4.0-84-GENERIC/X86_64/679871CFEC>) |
| 8086:a1f0 | 17aa:1038 | Intel            | Lewisburg MROM 0                     | 3     | snd_hda... | [5658A2FB98](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC003KUS/DD1C32AB7122/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/5658A2FB98>) |

### Storage (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1077:2532 | 1077:015d | QLogic           | ISP2532-based 8Gb Fibre Channel t... | 4     | qla2xxx    | [F2602534BE](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/405C5FBE4F5F/KUBUNTU-18.04/5.3.0-46-GENERIC/X86_64/F2602534BE>) |
| 1077:2432 | 1077:0137 | QLogic           | ISP2432-based 4Gb Fibre Channel t... | 3     | qla2xxx    | [B85DBD88F5](<Server/IBM/System/System x3650 M2 -[7947AC1]-/B4AFB5C90D39/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/B85DBD88F5>) |
| 11f8:8032 | 117c:003b | PMC-Sierra       | PM8032 Tachyon QE8                   | 3     | celerit... | [FB8C0A4C3A](<Server/Dell/PowerEdge/PowerEdge R730/1F01BE7E44C8/UBUNTU-18.04/4.15.0-88-GENERIC/X86_64/FB8C0A4C3A>) |
| 1077:2532 | 1077:015c | QLogic           | ISP2532-based 8Gb Fibre Channel t... | 2     | qla2xxx    | [1A5CF39F4F](<Server/IBM/System/System x3650 M4 -[7915AC1]/2D2939361294/UBUNTU-20.04/5.11.0-36-GENERIC/X86_64/1A5CF39F4F>) |
| 1077:2532 | 1077:015e | QLogic           | ISP2532-based 8Gb Fibre Channel t... | 2     | qla2xxx    | [C43FD89A0B](<Server/IBM/System/System x3850 X5 -[7143Y61]-/32036814BD3E/OPENSUSE-20201216/5.9.14-1-DEFAULT/X86_64/C43FD89A0B>) |
| 10df:f0e5 | 10df:f0e5 | Emulex           | Zephyr LightPulse Fibre Channel H... | 2     | lpfc       | [E36BFCD946](<Server/Dell/PowerEdge/PowerEdge R900/7C692A98BD7B/XCP-NG-8.2.0/4.19.0+1/X86_64/E36BFCD946>) |
| 1aed:2001 | 1590:006f | SanDisk          | ioDrive2                             | 2     |            | [1A73C74FBB](<Server/Supermicro/Super/Super Server/909986EADB14/UBUNTU-21.04/5.11.0-38-GENERIC/X86_64/1A73C74FBB>) |
| 1aed:2001 | 1aed:2001 | SanDisk          | ioDrive2                             | 2     |            | [26B693742E](<Server/Dell/PowerEdge/PowerEdge R810/A7C91C5C7A32/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/26B693742E>) |
| 1000:0646 | 1000:1020 | Broadcom / LSI   | FC949ES Fibre Channel Adapter        | 1     | mptfc      | [8F6E544820](<Server/Sun Microsystems/Sun/Sun Fire X4270 SERVER/38FCB3A1E58B/FEDORA-34/5.11.11-300.FC34.X86_64/X86_64/8F6E544820>) |
| 105a:1275 | 105a:1275 | Promise Techn... | 20275                                | 1     | pata_pd... | [E0E805180D](<Server/Others/Others/Others/7994F07888CD/DEBIAN-8/4.1.42-RIVOREO-POWERPC64/PPC64/E0E805180D>) |
| 1077:2031 | 103c:1939 | QLogic           | ISP8324-based 16Gb Fibre Channel ... | 1     | qla2xxx    | [9036136416](<Server/Hewlett-Packard/Superdome2/Superdome2 16s x86/777124CB43C9/ROSA-SX-CHROME-1.0/2.6.32-504.EL6.X86_64/X86_64/9036136416>) |
| 1077:2031 | 1077:0249 | QLogic           | ISP8324-based 16Gb Fibre Channel ... | 1     | qla2xxx    | [77A5A8BF12](<Server/Others/0JP31P/0JP31P A14/025EA12C2DA6/UBUNTU-18.08.39/4.10.0-38-GENERIC/X86_64/77A5A8BF12>) |
| 1077:2031 | 1077:0257 | QLogic           | ISP8324-based 16Gb Fibre Channel ... | 1     | qla2xxx    | [CBFB7C31D8](<Server/Dell/PowerEdge/PowerEdge R510/739618260755/UBUNTU-18.04/4.15.0-29-GENERIC/X86_64/CBFB7C31D8>) |
| 1077:2261 | 1077:02af | QLogic           | ISP2722-based 16/32Gb Fibre Chann... | 1     | qla2xxx    | [2AE35CF194](<Server/Lenovo/ThinkSystem/ThinkSystem SR630 -[7X02CTO1WW]-/D0074D37A357/UBUNTU-20.04/5.4.0-62-GENERIC/X86_64/2AE35CF194>) |
| 1077:2312 | 1077:0100 | QLogic           | ISP2312-based 2Gb Fibre Channel t... | 1     | qla2xxx    | [40F9D31598](<Server/Dell/PowerEdge/PowerEdge 2850/8C9CA6088BC7/CENTOS-6/2.6.32-754.30.2.EL6.X86_64/X86_64/40F9D31598>) |
| 1077:2432 | 103c:1705 | QLogic           | ISP2432-based 4Gb Fibre Channel t... | 1     | qla2xxx    | [DC4AC74B49](<Server/Hewlett-Packard/ProLiant/ProLiant BL685c G7/3F69ABE6ED6B/OPENSUSE-LEAP-15.2/5.3.18-LP152.60-DEFAULT/X86_64/DC4AC74B49>) |
| 1077:2432 | 103c:7040 | QLogic           | ISP2432-based 4Gb Fibre Channel t... | 1     | qla2xxx    | [B4EF3B8086](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G5/A36E86AAD166/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/B4EF3B8086>) |
| 1077:2432 | 103c:7041 | QLogic           | ISP2432-based 4Gb Fibre Channel t... | 1     | qla2xxx    | [C9D389B2A3](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/71BEBF7B78CB/UBUNTU-16.04/4.4.0-131-GENERIC/X86_64/C9D389B2A3>) |
| 1077:2532 | 1077:0171 | QLogic           | ISP2532-based 8Gb Fibre Channel t... | 1     | qla2xxx    | [4F5756D065](<Server/Oracle/Sun/Sun Fire X4270 M2 SERVER/FF52124EF1E7/FEDORA-32/5.8.12-200.FC32.X86_64/X86_64/4F5756D065>) |
| 1077:2532 | 1077:0176 | QLogic           | ISP2532-based 8Gb Fibre Channel t... | 1     | qla2xxx    | [D7CBC31CEE](<Server/IBM/BladeCenter/BladeCenter HS23 -[7875MFM]-/D5DD0E377016/RELS-6.9/2.6.32-696.EL6.X86_64/X86_64/D7CBC31CEE>) |
| 10df:f100 | 103c:3282 | Emulex           | LPe12000 Series 8Gb Fibre Channel... | 1     | lpfc       | [23F12250E5](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/C92D3D39B250/RHEL-8/4.18.0-240.22.1.EL8_3.X86_64/X86_64/23F12250E5>) |
| 10df:f400 | 10df:f410 | Emulex           | LPe35000/LPe36000 Series 32Gb/64G... | 1     | lpfc       | [9320E12A9A](<Server/Dell/PowerEdge/PowerEdge R6515/38E4D8545292/DEBIAN-11/5.10.0-8-AMD64/X86_64/9320E12A9A>) |
| 10df:fe00 | 10df:fe00 | Emulex           | Zephyr-X LightPulse Fibre Channel... | 1     | lpfc       | [6806624961](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G6/97C666008E4E/UBUNTU-18.04/4.15.0-50-GENERIC/X86_64/6806624961>) |
| 117c:0064 | 117c:0064 | ATTO Technology  | Celerity FC 16Gb/s Gen 5 Fibre Ch... | 1     |            | [43EE2001E1](<Server/AIC/SB302/SB302-LB/77AF6612F1D7/CENTOS-7/3.10.0-1062.4.1.EL7.X86_64/X86_64/43EE2001E1>) |
| 11f8:8032 | 117c:003a | PMC-Sierra       | PM8032 Tachyon QE8                   | 1     | celerit... | [5315690568](<Server/Supermicro/SYS-5018/SYS-5018D-FN8T/3DFAD0AEC112/UBUNTU-18.04/4.15.0-55-GENERIC/X86_64/5315690568>) |
| 19a2:0702 | 103c:3314 | Emulex           | OneConnect 10Gb iSCSI Initiator      | 1     | be2iscsi   | [DC4AC74B49](<Server/Hewlett-Packard/ProLiant/ProLiant BL685c G7/3F69ABE6ED6B/OPENSUSE-LEAP-15.2/5.3.18-LP152.60-DEFAULT/X86_64/DC4AC74B49>) |
| 19a2:0704 | 103c:174b | Emulex           | OneConnect OCe10100/OCe10102 Seri... | 1     | lpfc       | [E707BBA6A9](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G7/941269F514A4/UBUNTU-18.04/4.15.0-91-GENERIC/X86_64/E707BBA6A9>) |
| 19a2:0712 | 103c:337b | Emulex           | OneConnect 10Gb iSCSI Initiator (... | 1     | be2iscsi   | [9F21E5D9D9](<Server/Hewlett-Packard/ProLiant/ProLiant BL460c Gen8/1DB9D4472AA8/ARCH-ROLLING/5.10.79-1-LTS/X86_64/9F21E5D9D9>) |
| 19e5:0203 | 19e5:d301 | Huawei Techno... | Hi1822 Family (2*16G FC)             | 1     |            | [F548D0A0A9](<Server/Huawei/TaiShan/TaiShan 200/7F69DEB6BBD3/RELS-2019.1/5.10.42-GENERIC-1ROSA2019.1-ARM64/AARCH64/F548D0A0A9>) |
| 1aed:2001 | 1028:1f70 | SanDisk          | ioDrive2                             | 1     |            | [1AFA47E662](<Server/Dell/PowerEdge/PowerEdge R810/8C29BCCFEEB7/UBUNTU-20.04/5.4.0-67-GENERIC/X86_64/1AFA47E662>) |
| 1aed:2001 | 1028:1f71 | SanDisk          | ioDrive2                             | 1     |            | [4707D5CBF3](<Server/Dell/PowerEdge/PowerEdge R810/A7C91C5C7A32/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/4707D5CBF3>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a182 | 8086:7270 | Intel            | C620 Series Chipset Family SATA C... | 18    | ahci       | [FF6113B91D](<Server/Lenovo/ThinkSystem/ThinkSystem SR630 V2/ECB5C724E79D/CENTOS-7/3.10.0-1160.49.1.EL7.X86_64/X86_64/FF6113B91D>) |
| 8086:a1d2 | 8086:7270 | Intel            | C620 Series Chipset Family SSATA ... | 18    | ahci       | [FF6113B91D](<Server/Lenovo/ThinkSystem/ThinkSystem SR630 V2/ECB5C724E79D/CENTOS-7/3.10.0-1160.49.1.EL7.X86_64/X86_64/FF6113B91D>) |
| 8086:1d02 | 1043:84ef | Intel            | C600/X79 series chipset 6-Port SA... | 16    | ahci       | [0D39F4F066](<Server/ASUSTek Computer/Z9PE-D16/Z9PE-D16 Series/7948CC9F2801/UBUNTU-18.04/5.4.0-91-GENERIC/X86_64/0D39F4F066>) |
| 8086:8d02 | 15d9:0821 | Intel            | C610/X99 series chipset 6-Port SA... | 14    | ahci       | [AAEEE85BE7](<Server/Supermicro/SYS-6028/SYS-6028R-WTRT/690B86B530B0/DEBIAN-11/4.19.0-17-AMD64/X86_64/AAEEE85BE7>) |
| 8086:8d62 | 15d9:0821 | Intel            | C610/X99 series chipset sSATA Con... | 14    | ahci       | [AAEEE85BE7](<Server/Supermicro/SYS-6028/SYS-6028R-WTRT/690B86B530B0/DEBIAN-11/4.19.0-17-AMD64/X86_64/AAEEE85BE7>) |
| 8086:1d02 | 103c:18a9 | Intel            | C600/X79 series chipset 6-Port SA... | 13    | ahci       | [043730AD50](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/6413B944B1D2/UBUNTU-21.04/5.11.0-18-GENERIC/X86_64/043730AD50>) |
| 8086:1d02 | 15d9:0636 | Intel            | C600/X79 series chipset 6-Port SA... | 13    | ahci       | [31684AD7E4](<Server/Supermicro/X9/X9DRW/55D2AD4AF0CF/UBUNTU-21.04/5.11.0-44-GENERIC/X86_64/31684AD7E4>) |
| 8086:3a22 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) SATA AHCI ... | 13    | ahci       | [DB4185737E](<Server/Supermicro/X8/X8DTL/4816D25892DF/UBUNTU-20.04/5.4.44-2-PVE/X86_64/DB4185737E>) |
| 8086:a102 | 8086:7270 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 13    | ahci       | [7C1FA00B21](<Server/Intel/S1200/S1200SP/4B4C83B49974/CENTOS-7/4.4.241-1.EL7.ELREPO.X86_64/X86_64/7C1FA00B21>) |
| 1022:7901 | 15d9:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 12    | ahci       | [4798AC1234](<Server/Supermicro/Super/Super Server/4CD86DE2F12F/UBUNTU-20.04/5.4.0-84-GENERIC/X86_64/4798AC1234>) |
| 8086:a1d2 | 1028:073a | Intel            | C620 Series Chipset Family SSATA ... | 11    | ahci       | [2E5507B849](<Server/Dell/Precision/Precision 7920 Tower/6DBFD1DBD45A/UBUNTU-20.04/5.10.0-1055-OEM/X86_64/2E5507B849>) |
| 1022:7901 | 1022:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 10    | ahci       | [F7739E263E](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/05C34CB58FDD/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/F7739E263E>) |
| 8086:1d02 | 1028:048c | Intel            | C600/X79 series chipset 6-Port SA... | 10    | ahci       | [7BF19C1CD2](<Server/Dell/PowerEdge/PowerEdge R720/2489ED365DE4/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/7BF19C1CD2>) |
| 1002:4391 | 1002:4391 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 9     | ahci       | [3051CEA326](<Server/Supermicro/H8/H8DGU/8ACEE5E956B2/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3051CEA326>) |
| 1b4b:9230 | 1b4b:9230 | Marvell Techn... | 88SE9230 PCIe 2.0 x2 4-port SATA ... | 9     | ahci       | [F7739E263E](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/05C34CB58FDD/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/F7739E263E>) |
| 8086:8d02 | 8086:7270 | Intel            | C610/X99 series chipset 6-Port SA... | 9     | ahci       | [50AEBE4B28](<Server/Supermicro/SSG-6048/SSG-6048R-E1CR24H/8A7A52EA4807/CENTOS-8/4.18.0-348.2.1.EL8_5.X86_64/X86_64/50AEBE4B28>) |
| 1022:7901 | 1458:1000 | AMD              | FCH SATA Controller [AHCI mode]      | 8     | ahci       | [6D2EE30F72](<Server/Gigabyte Technology/MZ71/MZ71-CE0-00/74E7E16574F5/UBUNTU-MATE-20.04/5.11.0-43-GENERIC/X86_64/6D2EE30F72>) |
| 1b4b:9230 | 1043:84fa | Marvell Techn... | 88SE9230 PCIe 2.0 x2 4-port SATA ... | 8     | ahci       | [A4C832AB44](<Server/ASUSTek Computer/Z9PE-D8/Z9PE-D8 WS/38D0E7604F44/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/A4C832AB44>) |
| 8086:1d02 | 1028:04fa | Intel            | C600/X79 series chipset 6-Port SA... | 8     | ahci       | [ABE0B5613A](<Server/Dell/PowerEdge/PowerEdge T320/EB32D3263597/UBUNTU-20.04/5.4.0-74-GENERIC/X86_64/ABE0B5613A>) |
| 8086:8c02 | 8086:35b5 | Intel            | 8 Series/C220 Series Chipset Fami... | 8     | ahci       | [7023226F81](<Server/Intel/S1200/S1200RP/832EB05B058D/FEDORA-35/5.16.2-200.FC35.X86_64/X86_64/7023226F81>) |
| 8086:8d02 | 103c:8030 | Intel            | C610/X99 series chipset 6-Port SA... | 8     | ahci       | [CFFFE6AA63](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/74B986D09E54/DEBIAN-11/5.11.22-5-PVE/X86_64/CFFFE6AA63>) |
| 8086:8d62 | 15d9:0857 | Intel            | C610/X99 series chipset sSATA Con... | 8     | ahci       | [6A333A499D](<Server/Supermicro/X10/X10SRA/0DAF404C22AB/GENTOO-2.7/5.14.14-GENTOO-X86_64/X86_64/6A333A499D>) |
| 8086:a182 | 1043:871e | Intel            | C620 Series Chipset Family SATA C... | 8     | ahci       | [3035FDAD91](<Server/ASUSTek Computer/WS-C621E-SAGE/WS-C621E-SAGE Series/E86AFFE0F80D/KUBUNTU-20.04/5.4.0-97-GENERIC/X86_64/3035FDAD91>) |
| 8086:a182 | 15d9:096d | Intel            | C620 Series Chipset Family SATA C... | 8     | ahci       | [2CDAC4454D](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.16.8-051608-GENERIC/X86_64/2CDAC4454D>) |
| 8086:a1d2 | 15d9:096d | Intel            | C620 Series Chipset Family SSATA ... | 8     | ahci       | [2CDAC4454D](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.16.8-051608-GENERIC/X86_64/2CDAC4454D>) |
| 8086:1c02 | 1028:04de | Intel            | 6 Series/C200 Series Chipset Fami... | 7     | ahci       | [D95EA030FF](<Server/Dell/PowerEdge/PowerEdge T110 II/2E5934354FEE/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/D95EA030FF>) |
| 8086:8c02 | 15d9:0801 | Intel            | 8 Series/C220 Series Chipset Fami... | 7     | ahci       | [84ED224F36](<Server/Supermicro/X10/X10SLL-F/34D1B7FAB08F/ALPINE-3.12.7/5.4.111-0-LTS/X86_64/84ED224F36>) |
| 8086:8d02 | 15d9:0831 | Intel            | C610/X99 series chipset 6-Port SA... | 7     | ahci       | [58E86F0E34](<Server/Supermicro/Super/Super Server/BD4C9B6F043B/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/58E86F0E34>) |
| 8086:8d02 | 15d9:0857 | Intel            | C610/X99 series chipset 6-Port SA... | 7     | ahci       | [6A333A499D](<Server/Supermicro/X10/X10SRA/0DAF404C22AB/GENTOO-2.7/5.14.14-GENTOO-X86_64/X86_64/6A333A499D>) |
| 8086:8d62 | 1043:85f7 | Intel            | C610/X99 series chipset sSATA Con... | 7     | ahci       | [4158CB76EF](<Server/ASUSTek Computer/RS400/RS400-E8-PS2-F/B939D9497146/GENTOO-2.7/5.10.14-HARDENED1/X86_64/4158CB76EF>) |
| 8086:8d62 | 8086:7270 | Intel            | C610/X99 series chipset sSATA Con... | 7     | ahci       | [50AEBE4B28](<Server/Supermicro/SSG-6048/SSG-6048R-E1CR24H/8A7A52EA4807/CENTOS-8/4.18.0-348.2.1.EL8_5.X86_64/X86_64/50AEBE4B28>) |
| 8086:a182 | 17aa:7808 | Intel            | C620 Series Chipset Family SATA C... | 7     | ahci       | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 8086:a1d2 | 17aa:7808 | Intel            | C620 Series Chipset Family SSATA ... | 7     | ahci       | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 8086:1d02 | 1014:1d02 | Intel            | C600/X79 series chipset 6-Port SA... | 6     | ahci       | [C717BB4AC6](<Server/IBM/System/System X iDataPlex dx360 M4 Server -[7912AC1]-/E15173785994/UBUNTU-18.04/4.15.0-166-GENERIC/X86_64/C717BB4AC6>) |
| 8086:8c02 | 8086:8c02 | Intel            | 8 Series/C220 Series Chipset Fami... | 6     | ahci       | [9FBB87A829](<Server/VIT/NP3020/NP3020M3/6DA8E8BE5005/DEBIAN-10/4.19.0-18-AMD64/X86_64/9FBB87A829>) |
| 8086:8d02 | 1028:0601 | Intel            | C610/X99 series chipset 6-Port SA... | 6     | ahci       | [F90168C69D](<Server/Dell/PowerEdge/PowerEdge R630/DBDF919E8981/RHEL-7/3.10.0-1127.19.1.EL7.YAHOO.20200821.63.X86_64/X86_64/F90168C69D>) |
| 8086:8d02 | 1043:85f6 | Intel            | C610/X99 series chipset 6-Port SA... | 6     | ahci       | [ED442D7C21](<Server/OEGStone/Z10PE-D8/Z10PE-D8 WS/CC28E46A3610/UBUNTU-20.04/5.4.0-66-GENERIC/X86_64/ED442D7C21>) |
| 8086:8d62 | 1028:0601 | Intel            | C610/X99 series chipset sSATA Con... | 6     | ahci       | [F90168C69D](<Server/Dell/PowerEdge/PowerEdge R630/DBDF919E8981/RHEL-7/3.10.0-1127.19.1.EL7.YAHOO.20200821.63.X86_64/X86_64/F90168C69D>) |
| 1002:4390 | 1028:0444 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 5     | ahci       | [FBE32ACA1D](<Server/Dell/PowerEdge/PowerEdge R815/D106BA160A7C/DEBIAN-UNSTABLE/5.16.0-RC8-AMD64/X86_64/FBE32ACA1D>) |
| 8086:1c02 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 5     | ahci       | [E0E68EFC2F](<Server/Dell/PowerEdge/PowerEdge R210 II/D6DEF28F8714/UBUNTU-18.04/4.15.0-109-GENERIC/X86_64/E0E68EFC2F>) |
| 8086:1c02 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 5     | ahci       | [0051160B0D](<Server/Intel/S1200/S1200BTL/A063843D6E74/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/0051160B0D>) |
| 8086:1d02 | 1028:04ce | Intel            | C600/X79 series chipset 6-Port SA... | 5     | ahci       | [F5F07BFFC2](<Server/Others/0XWDCF/0XWDCF A01/60D0A665A1F8/DEBIAN-11/5.13.19-3-PVE/X86_64/F5F07BFFC2>) |
| 8086:1d02 | 15d9:0626 | Intel            | C600/X79 series chipset 6-Port SA... | 5     | ahci       | [DE8D4D24B6](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/050383036EDE/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/DE8D4D24B6>) |
| 8086:1d02 | 15d9:062a | Intel            | C600/X79 series chipset 6-Port SA... | 5     | ahci       | [7EF7B85267](<Server/Supermicro/X9/X9SRA-X9SRA-3/6DA328B1EF68/UBUNTU-18.04/4.15.0-166-GENERIC/X86_64/7EF7B85267>) |
| 8086:3a22 | 103c:330b | Intel            | 82801JI (ICH10 Family) SATA AHCI ... | 5     | ahci       | [537E8D34B7](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 G6/E32F627377A6/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/537E8D34B7>) |
| 8086:8c02 | 15d9:0805 | Intel            | 8 Series/C220 Series Chipset Fami... | 5     | ahci       | [019914CC29](<Server/Supermicro/X10/X10SAE/6D8BBA911035/GENTOO-2.7/5.13.12-GENTOO/X86_64/019914CC29>) |
| 8086:8c02 | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 5     | ahci       | [12DB3650F6](<Server/Supermicro/Super/Super Server/51A56BB4E7AB/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/12DB3650F6>) |
| 8086:8c02 | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 5     | ahci       | [E60EC405AF](<Server/Supermicro/Super/Super Server/F5F261808B48/GENTOO-2.6/5.15.19-GENTOO/X86_64/E60EC405AF>) |
| 8086:8d62 | 15d9:0831 | Intel            | C610/X99 series chipset sSATA Con... | 5     | ahci       | [58E86F0E34](<Server/Supermicro/Super/Super Server/BD4C9B6F043B/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/58E86F0E34>) |
| 8086:a102 | 1028:06a5 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 5     | ahci       | [E2A3815DD2](<Server/Dell/PowerEdge/PowerEdge R230/9BDDC6CE9A41/RHEL-7/3.10.0-1062.12.1.EL7.X86_64/X86_64/E2A3815DD2>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1d00 | 103c:18a9 | Intel            | C600/X79 series chipset 4-Port SA... | 27    | pata_acpi  | [1172390E59](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/2267C96ADE00/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/1172390E59>) |
| 8086:3a20 | 103c:330d | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 22    | pata_acpi  | [FE6B8CB2E4](<Server/Hewlett-Packard/ProLiant/ProLiant DL580 G7/68420A1A9387/FEDORA-35/5.15.16-200.FC35.X86_64/X86_64/FE6B8CB2E4>) |
| 8086:2921 | 1028:0235 | Intel            | 82801IB (ICH9) 2 port SATA Contro... | 15    | pata_acpi  | [27639679E2](<Server/Dell/PowerEdge/PowerEdge R710/ACC1A39EDD24/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/27639679E2>) |
| 8086:269e | 103c:31fe | Intel            | 631xESB/632xESB IDE Controller       | 14    | pata_acpi  | [24D4B5B8DB](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/9A14972DB3E8/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/24D4B5B8DB>) |
| 8086:a1bc | 1028:073a | Intel            | C620 Series Chipset Family IDE Re... | 11    | pata_acpi  | [2E5507B849](<Server/Dell/Precision/Precision 7920 Tower/6DBFD1DBD45A/UBUNTU-20.04/5.10.0-1055-OEM/X86_64/2E5507B849>) |
| 8086:2921 | 1028:0236 | Intel            | 82801IB (ICH9) 2 port SATA Contro... | 10    | pata_acpi  | [02E5C56A80](<Server/Dell/PowerEdge/PowerEdge R610/D7D0CF9B35C0/ROCKY-8.5/4.18.0-348.12.2.EL8_5.X86_64/X86_64/02E5C56A80>) |
| 8086:3a20 | 1014:3a20 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 10    | pata_acpi  | [76A0EBBFC4](<Server/IBM/System/System x3550 M3 -[7944KAG]-/E6F6F92CA768/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/76A0EBBFC4>) |
| 8086:3b20 | 1028:02a4 | Intel            | 5 Series/3400 Series Chipset 4 po... | 10    | ata_piix   | [2CAE1B1D80](<Server/Dell/PowerEdge/PowerEdge T310/1B407A78D4C5/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/2CAE1B1D80>) |
| 8086:3b26 | 1028:02a4 | Intel            | 5 Series/3400 Series Chipset 2 po... | 10    | ata_piix   | [2CAE1B1D80](<Server/Dell/PowerEdge/PowerEdge T310/1B407A78D4C5/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/2CAE1B1D80>) |
| 8086:3a26 | 1014:3a26 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 8     | pata_acpi  | [76A0EBBFC4](<Server/IBM/System/System x3550 M3 -[7944KAG]-/E6F6F92CA768/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/76A0EBBFC4>) |
| 197b:2368 | 197b:2368 | JMicron Techn... | JMB368 IDE controller                | 6     | pata_jm... | [535E5F1D58](<Server/Supermicro/X8/X8DTN/50F52177DF45/DEBIAN-11/5.10.0-8-AMD64/X86_64/535E5F1D58>) |
| 8086:3a20 | 8086:34dc | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 6     | ata_piix   | [A30DCB5033](<Server/Intel/S5520/S5520HC/5E89F6CD026C/ZORIN-16/5.11.0-40-GENERIC/X86_64/A30DCB5033>) |
| 8086:3a20 | 8086:3a20 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 6     | ata_piix   | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:3a26 | 8086:34dc | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 6     | ata_piix   | [A30DCB5033](<Server/Intel/S5520/S5520HC/5E89F6CD026C/ZORIN-16/5.11.0-40-GENERIC/X86_64/A30DCB5033>) |
| 8086:3a26 | 8086:3a26 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 6     | ata_piix   | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:1d08 | 103c:18a9 | Intel            | C600/X79 series chipset 2-Port SA... | 5     | ata_pii... | [A28B637049](<Server/Hewlett-Packard/ProLiant/ProLiant DL380e Gen8/ECA2BB01C65F/RHEL-7/3.10.0-1160.EL7.X86_64/X86_64/A28B637049>) |
| 8086:269e | 1028:01b2 | Intel            | 631xESB/632xESB IDE Controller       | 5     | ata_piix   | [4CC109A2AB](<Server/Dell/PowerEdge/PowerEdge 2950/819CF07A677E/ZORIN-16/5.11.0-43-GENERIC/X86_64/4CC109A2AB>) |
| 8086:2921 | 1028:0237 | Intel            | 82801IB (ICH9) 2 port SATA Contro... | 5     | pata_acpi  | [BCDCCDDEC2](<Server/Dell/PowerEdge/PowerEdge T610/EFB372134BAB/ZORIN-16/5.13.0-28-GENERIC/X86_64/BCDCCDDEC2>) |
| 8086:3a20 | 8086:34e2 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 5     | pata_acpi  | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3a26 | 8086:34e2 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 5     | pata_acpi  | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:a1bc | 1028:0739 | Intel            | C620 Series Chipset Family IDE Re... | 5     | pata_acpi  | [5A2FCB7023](<Server/Dell/Precision/Precision 7820 Tower/8AAB146ACE98/LINUXMINT-20/5.4.0-91-GENERIC/X86_64/5A2FCB7023>) |
| 1002:439c | 15d9:ab11 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 4     | pata_at... | [D5563E325C](<Server/Supermicro/H8/H8QG6/58E82626C3C5/KUBUNTU-20.04/5.4.0-73-GENERIC/X86_64/D5563E325C>) |
| 1002:439c | 15d9:bc11 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 4     | pata_at... | [1FE97B31A1](<Server/Supermicro/H8/H8DG6-H8DGi/E9DC2B4F6431/FEDORA-32/5.11.22-100.FC32.X86_64/X86_64/1FE97B31A1>) |
| 8086:2680 | 1028:01b3 | Intel            | 631xESB/632xESB/3100 Chipset SATA... | 4     | pata_acpi  | [CA96304CAC](<Server/Dell/PowerEdge/PowerEdge 1950/E6782D539697/POP!_OS-20.04/5.15.15-76051515-GENERIC/X86_64/CA96304CAC>) |
| 8086:269e | 8086:3476 | Intel            | 631xESB/632xESB IDE Controller       | 4     | pata_acpi  | [38109F9919](<Server/Intel/S5000/S5000PSL/26C6E7EE0282/UBUNTU-20.04/5.4.0-33-GENERIC/X86_64/38109F9919>) |
| 8086:27c0 | 1028:01e7 | Intel            | NM10/ICH7 Family SATA Controller ... | 4     | pata_acpi  | [EA66809CE7](<Server/Dell/PowerEdge/PowerEdge 840/E4DBE564B603/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/EA66809CE7>) |
| 8086:27df | 1028:01e7 | Intel            | 82801G (ICH7 Family) IDE Controller  | 4     | pata_acpi  | [EA66809CE7](<Server/Dell/PowerEdge/PowerEdge 840/E4DBE564B603/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/EA66809CE7>) |
| 8086:3a20 | 1028:028c | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 4     | pata_acpi  | [F46A021C88](<Server/Dell/PowerEdge/PowerEdge R410/9BE3F9CEE048/LUBUNTU-20.04/5.4.0-83-GENERIC/X86_64/F46A021C88>) |
| 8086:3a20 | 15d9:0400 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 4     | ata_pii... | [AD4ABE60CD](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/03637143A526/XUBUNTU-20.04/5.11.0-37-GENERIC/X86_64/AD4ABE60CD>) |
| 8086:3a20 | 15d9:0600 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 4     | pata_acpi  | [ACA2A2FFDF](<Server/Supermicro/X8/X8DTU/B1E056AA3422/DEBIAN-10/5.4.73-1-PVE/X86_64/ACA2A2FFDF>) |
| 8086:3a20 | 1734:1150 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 4     | ata_piix   | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:3a20 | 8086:34da | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 4     | pata_acpi  | [FE3D758C20](<Server/Intel/S5500/S5500BC/EB1E1FCFB3A4/KDE-NEON-20.04/5.4.0-66-GENERIC/X86_64/FE3D758C20>) |
| 8086:3a26 | 1028:028c | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 4     | pata_acpi  | [F46A021C88](<Server/Dell/PowerEdge/PowerEdge R410/9BE3F9CEE048/LUBUNTU-20.04/5.4.0-83-GENERIC/X86_64/F46A021C88>) |
| 8086:3a26 | 15d9:0400 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 4     | ata_pii... | [AD4ABE60CD](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/03637143A526/XUBUNTU-20.04/5.11.0-37-GENERIC/X86_64/AD4ABE60CD>) |
| 8086:3a26 | 15d9:0600 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 4     | pata_acpi  | [ACA2A2FFDF](<Server/Supermicro/X8/X8DTU/B1E056AA3422/DEBIAN-10/5.4.73-1-PVE/X86_64/ACA2A2FFDF>) |
| 8086:3a26 | 1734:114d | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 4     | ata_piix   | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:3a26 | 8086:34da | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 4     | pata_acpi  | [FE3D758C20](<Server/Intel/S5500/S5500BC/EB1E1FCFB3A4/KDE-NEON-20.04/5.4.0-66-GENERIC/X86_64/FE3D758C20>) |
| 1002:439c | 103c:1773 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 3     | pata_at... | [DC4AC74B49](<Server/Hewlett-Packard/ProLiant/ProLiant BL685c G7/3F69ABE6ED6B/OPENSUSE-LEAP-15.2/5.3.18-LP152.60-DEFAULT/X86_64/DC4AC74B49>) |
| 1002:439c | 103c:3338 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 3     | pata_at... | [91AD975174](<Server/Hewlett-Packard/ProLiant/ProLiant DL165 G7/418C07CB59F3/CENTOS-7/3.10.0-1127.19.1.EL7.X86_64/X86_64/91AD975174>) |
| 1002:439c | 1111:077c | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 3     | pata_at... | [4A83A85932](<Server/AMD/AOPW-PLUS/AOPW-PLUS/B61223D18897/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/4A83A85932>) |
| 1002:439c | 15d9:a811 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 3     | pata_at... | [3051CEA326](<Server/Supermicro/H8/H8DGU/8ACEE5E956B2/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3051CEA326>) |
| 8086:2680 | 1014:02dd | Intel            | 631xESB/632xESB/3100 Chipset SATA... | 3     | ata_pii... | [701B89AC2E](<Server/IBM/System/System x3650 -[7979B9U]-/BC2D6FA78D8E/OPENMANDRIVA-4.2/5.11.12-DESKTOP-1OMV4002/X86_64/701B89AC2E>) |
| 8086:269e | 1028:01b3 | Intel            | 631xESB/632xESB IDE Controller       | 3     | pata_acpi  | [CA96304CAC](<Server/Dell/PowerEdge/PowerEdge 1950/E6782D539697/POP!_OS-20.04/5.15.15-76051515-GENERIC/X86_64/CA96304CAC>) |
| 8086:269e | 8086:3486 | Intel            | 631xESB/632xESB IDE Controller       | 3     | pata_acpi  | [0A3F6D305B](<Server/Powerleader/PR1710/PR1710N/AF12FD7CB1BD/DEBIAN-10/5.4.78-2-PVE/X86_64/0A3F6D305B>) |
| 8086:3a20 | 1028:028d | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 3     | ata_pii... | [1A05144C7E](<Server/Dell/PowerEdge/PowerEdge T410/5468AD1E8E89/UBUNTU-20.10/5.8.0-50-GENERIC/X86_64/1A05144C7E>) |
| 8086:3a20 | 1028:02d4 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 3     | pata_acpi  | [26B693742E](<Server/Dell/PowerEdge/PowerEdge R810/A7C91C5C7A32/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/26B693742E>) |
| 8086:3a20 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 3     | ata_pii... | [89D676AF03](<Server/Supermicro/X8/X8DTL/6E7DE9F9FEDC/DEBIAN-11/5.10.0-11-AMD64/X86_64/89D676AF03>) |
| 8086:3a26 | 1028:028d | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 3     | ata_pii... | [1A05144C7E](<Server/Dell/PowerEdge/PowerEdge T410/5468AD1E8E89/UBUNTU-20.10/5.8.0-50-GENERIC/X86_64/1A05144C7E>) |
| 8086:3a26 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 3     | ata_pii... | [89D676AF03](<Server/Supermicro/X8/X8DTL/6E7DE9F9FEDC/DEBIAN-11/5.10.0-11-AMD64/X86_64/89D676AF03>) |
| 8086:3b20 | 1028:02a3 | Intel            | 5 Series/3400 Series Chipset 4 po... | 3     | pata_acpi  | [C7E2652542](<Server/Dell/PowerEdge/PowerEdge R310/01A426146917/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/C7E2652542>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 47    | nvme       | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 12    | nvme       | [AA1C79AB75](<Server/Supermicro/H8/H8DG6-H8DGi/49F6AA867D33/ARCH/5.16.5-ARCH1-1/X86_64/AA1C79AB75>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 8     | nvme       | [5F7514110B](<Server/Hewlett-Packard/ProLiant/ProLiant DL560 Gen8/33DD1AF8270B/UBUNTU-21.04/5.11.0-22-GENERIC/X86_64/5F7514110B>) |
| 8086:0a54 | 8086:4802 | Intel            | NVMe Datacenter SSD [3DNAND, Beta... | 7     | nvme       | [2552B5BB72](<Server/Aquarius/Catfish/Catfish AQC624CF/F60E6B0A63F8/CENTOS-8/4.18.0-193.EL8.X86_64/X86_64/2552B5BB72>) |
| 14a4:2300 | 1b4b:1093 | Lite-On Techn... | Non-Volatile memory controller       | 6     | nvme       | [4391DFF8D2](<Server/Others/Others/Others/29E67FFE5E37/UBUNTU-18.04/4.18.0-20-GENERIC/X86_64/4391DFF8D2>) |
| 1344:5405 | 1344:0100 | Micron Techno... | Non-Volatile memory controller       | 5     | nvme       | [5A2FCB7023](<Server/Dell/Precision/Precision 7820 Tower/8AAB146ACE98/LINUXMINT-20/5.4.0-91-GENERIC/X86_64/5A2FCB7023>) |
| 15b7:5009 | 15b7:5009 | Sandisk          | WD Blue SN550 NVMe SSD               | 5     | nvme       | [1DF72E1613](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/2D28DE8C0BFA/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/1DF72E1613>) |
| 8086:f1a6 | 8086:390b | Intel            | SSD Pro 7600p/760p/E 6100p Series    | 5     | nvme       | [113B5E448D](<Server/Dell/Precision/Precision 7920 Tower/7523CA2C9CDA/UBUNTU-18.04/5.4.0-80-GENERIC/X86_64/113B5E448D>) |
| 1344:51b2 | 1344:5000 | Micron Techno... | Non-Volatile memory controller       | 4     | nvme       | [2BB4102B1C](<Server/Supermicro/Super/Super Server/45717F18B5CF/CENTOS-8/4.18.0-240.22.1.EL8_3.X86_64/X86_64/2BB4102B1C>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980              | 4     | nvme       | [2BB4102B1C](<Server/Supermicro/Super/Super Server/45717F18B5CF/CENTOS-8/4.18.0-240.22.1.EL8_3.X86_64/X86_64/2BB4102B1C>) |
| 144d:a80a | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 4     | nvme       | [F5F07BFFC2](<Server/Others/0XWDCF/0XWDCF A01/60D0A665A1F8/DEBIAN-11/5.13.19-3-PVE/X86_64/F5F07BFFC2>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013 E13 NVMe Controller           | 4     | nvme       | [B850CD60F6](<Server/Acord-92/PCplus/PCplus T600-C246/CC2E95E1BC69/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B850CD60F6>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 4     | nvme       | [36434C8979](<Server/Supermicro/Super/Super Server/64BD44B140C6/UBUNTU-20.04/5.11.0-46-GENERIC/X86_64/36434C8979>) |
| 126f:2262 | 126f:2262 | Silicon Motion   | SM2262/SM2262EN SSD Controller       | 2     | nvme       | [4A717F6348](<Server/Neousys Technology/Nuvo-8208GC/Nuvo-8208GC Series/02E83AA0CBB0/GENTOO-2.8/5.16.5-GENTOO/X86_64/4A717F6348>) |
| 15b7:5002 | 15b7:5002 | Sandisk          | WD Black 2018/SN750 / PC SN720 NV... | 2     | nvme       | [F6F6B1BC99](<Server/TYAN Computer/S8026/S8026GM2NRE/850F0AA78715/DEBIAN-9/4.9.0-13-AMD64/X86_64/F6F6B1BC99>) |
| 15b7:5006 | 15b7:5006 | Sandisk          | WD Black SN750 / PC SN730 NVMe SSD   | 2     | nvme       | [6877A6D4E6](<Server/Dell/PowerEdge/PowerEdge R820/D7A373654239/UBUNTU-20.04/5.8.0-55-GENERIC/X86_64/6877A6D4E6>) |
| 1987:5016 | 1987:5016 | Phison Electr... | E16 PCIe4 NVMe Controller            | 2     | nvme       | [29F49B3A79](<Server/Dell/PowerEdge/PowerEdge R520/F12E87D98729/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/29F49B3A79>) |
| 1bc0:1002 | 1bc0:1002 | Innodisk         | PCIe 3TE6 Controller                 | 2     | nvme       | [7E72EDD37F](<Server/Others/Others/Others/D71A313EE626/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/7E72EDD37F>) |
| 2646:500d | 2646:500d | Kingston Tech... | OM3PDP3 NVMe SSD                     | 2     | nvme       | [0AB1FF409B](<Server/BESSTAR Tech/X/X500/A95AE61E36B4/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/0AB1FF409B>) |
| 8086:0953 | 8086:3705 | Intel            | PCIe Data Center SSD                 | 2     | nvme       | [2A41E48C27](<Server/Intel/S1200/S1200SP/D1D1E80179A7/UBUNTU-21.04/5.11.0-38-GENERIC/X86_64/2A41E48C27>) |
| 8086:0a54 | 8086:4714 | Intel            | NVMe Datacenter SSD [3DNAND, Beta... | 2     | nvme       | [D373AF93CD](<Server/DALCO/S2600/S2600WFT/1A8F025340D8/UBUNTU-18.04/4.15.0-91-GENERIC/X86_64/D373AF93CD>) |
| 8086:2700 | 8086:3900 | Intel            | Optane SSD 900P Series               | 2     | nvme       | [376BED560D](<Server/Supermicro/X9/X9DRD-7LN4F-X9DRD-EF/E23334E6B08A/VIRTUOZZO-7.0.11/3.10.0-957.12.2.VZ7.96.21/X86_64/376BED560D>) |
| 8086:f1a5 | 8086:390a | Intel            | SSD 600P Series                      | 2     | nvme       | [AAEEE85BE7](<Server/Supermicro/SYS-6028/SYS-6028R-WTRT/690B86B530B0/DEBIAN-11/4.19.0-17-AMD64/X86_64/AAEEE85BE7>) |
| 1179:0116 | 1179:0001 | Toshiba Ameri... | Toshiba America Info Non-Volatile... | 1     | nvme       | [3514F18D29](<Server/Dell/Precision/Precision 7820 Tower/30A81C70C13D/ELEMENTARY-5.1/4.15.0-65-GENERIC/X86_64/3514F18D29>) |
| 1179:011a | 1179:0001 | Toshiba Ameri... | XG6 NVMe SSD Controller              | 1     | nvme       | [C8F90792EC](<Server/Dell/Precision/Precision 7920 Tower/11F2F8B0AD2A/UBUNTU-18.04/5.4.0-81-GENERIC/X86_64/C8F90792EC>) |
| 126f:2260 | 126f:2260 | Silicon Motion   | Non-Volatile memory controller       | 1     | nvme       | [DB4185737E](<Server/Supermicro/X8/X8DTL/4816D25892DF/UBUNTU-20.04/5.4.44-2-PVE/X86_64/DB4185737E>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT SSD Controller     | 1     | nvme       | [0C9DFEB831](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/A94765827296/UBUNTU-20.04/5.4.0-37-GENERIC/X86_64/0C9DFEB831>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 1     | nvme       | [AC7F5D0860](<Server/Supermicro/X10/X10SRA-F/9B64171C62F0/UBUNTU-18.04/4.15.0-88-GENERIC/X86_64/AC7F5D0860>) |
| 144d:a821 | 108e:a803 | Samsung Elect... | NVMe SSD Controller 172X             | 1     | nvme       | [FDC516788A](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/7607018A1D31/DEBIAN-10/5.4.65-1-PVE/X86_64/FDC516788A>) |
| 144d:a822 | 1028:1ff7 | Samsung Elect... | NVMe SSD Controller 172Xa/172Xb      | 1     | nvme       | [E9A1FC86F9](<Server/Dell/PowerEdge/PowerEdge R740/4DA16FD481F3/UBUNTU-18.04/4.15.0-118-GENERIC/X86_64/E9A1FC86F9>) |
| 144d:a822 | 144d:a80b | Samsung Elect... | NVMe SSD Controller 172Xa/172Xb      | 1     | nvme       | [04144B327A](<Server/AMD/ETHANOL_DEBUG_X/ETHANOL_DEBUG_X/475A2B0CCAB4/UBUNTU-21.04/5.11.0-34-GENERIC/X86_64/04144B327A>) |
| 144d:a822 | 1590:0297 | Samsung Elect... | NVMe SSD Controller 172Xa/172Xb      | 1     | nvme       | [7D9FDF4B73](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/16075FBC6C06/UBUNTU-21.10/5.15.1-051501-GENERIC/X86_64/7D9FDF4B73>) |
| 144d:a824 | 1028:2044 | Samsung Elect... | NVMe SSD Controller PM173X           | 1     | nvme       | [4B1DC70687](<Server/Dell/PowerEdge/PowerEdge R440/F8F03AC45B85/DEBIAN-UNSTABLE/5.16.0-3-AMD64/X86_64/4B1DC70687>) |
| 144d:a824 | 1028:2071 | Samsung Elect... | NVMe SSD Controller PM173X           | 1     | nvme       | [B7AC531BF5](<Server/Dell/PowerEdge/PowerEdge R7525/3F409CE3A366/RHEL-8///B7AC531BF5>) |
| 144d:a824 | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM173X           | 1     | nvme       | [4231BB05CE](<Server/Gigabyte Technology/G482/G482-Z54-00/7CA16E0B16D7/UBUNTU-20.04/5.4.0-64-GENERIC/X86_64/4231BB05CE>) |
| 14a4:22f1 | 1b4b:1093 | Lite-On Techn... | M8Pe Series NVMe SSD                 | 1     | nvme       | [1AFA47E662](<Server/Dell/PowerEdge/PowerEdge R810/8C29BCCFEEB7/UBUNTU-20.04/5.4.0-67-GENERIC/X86_64/1AFA47E662>) |
| 15b7:501a | 15b7:501a | Sandisk          | WD Blue SN570 NVMe SSD               | 1     | nvme       | [3035FDAD91](<Server/ASUSTek Computer/WS-C621E-SAGE/WS-C621E-SAGE Series/E86AFFE0F80D/KUBUNTU-20.04/5.4.0-97-GENERIC/X86_64/3035FDAD91>) |
| 1987:5007 | 1987:5007 | Phison Electr... | E7 NVMe Controller                   | 1     | nvme       | [BB8832ACBD](<Server/Supermicro/Super/Super Server/846C921FF296/ARCH/4.20.0-ARCH1-1-ARCH/X86_64/BB8832ACBD>) |
| 1987:5008 | 1987:5008 | Phison Electr... | NVMe Storage Controller              | 1     | nvme       | [E60EC405AF](<Server/Supermicro/Super/Super Server/F5F261808B48/GENTOO-2.6/5.15.19-GENTOO/X86_64/E60EC405AF>) |
| 1987:5018 | 1987:5018 | Phison Electr... | E18 PCIe4 NVMe Controller            | 1     | nvme       | [7A720A4E41](<Server/Supermicro/Super/Super Server/06E41BB3C6CC/ROCKY-8.5/4.18.0-348.12.2.EL8_5.X86_64/X86_64/7A720A4E41>) |
| 19e5:3714 | 19e5:5123 | Huawei Techno... | ES3000 V5 NVMe PCIe SSD              | 1     | nvme       | [A17BEFC33B](<Server/Huawei/TaiShan/TaiShan 200/50ED10C1AEE2/UBUNTU-20.04/5.4.0-42-GENERIC/AARCH64/A17BEFC33B>) |
| 19e5:3714 | 19e5:5312 | Huawei Techno... | ES3000 V5 NVMe PCIe SSD              | 1     | nvme       | [3CA7825025](<Server/Huawei/TaiShan/TaiShan 200/D4C1A2BB9D96/UBUNTU-21.04/5.8.0-42-GENERIC/AARCH64/3CA7825025>) |
| 1b4b:1160 | 1b4b:1160 | Marvell Techn... | Marvell Non-Volatile memory contr... | 1     | nvme       | [375EC8881D](<Server/Neousys Technology/Nuvo-8208GC/Nuvo-8208GC Series/78293157040C/UBUNTU-18.04/5.4.0-53-GENERIC/X86_64/375EC8881D>) |
| 1b85:6018 | 1b85:6018 | OCZ Technolog... | RD400/400A SSD                       | 1     | nvme       | [FFC55DBFA7](<Server/Supermicro/Super/Super Server/A61851B3D7CC/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/FFC55DBFA7>) |
| 1b96:2200 | 1b96:0000 | Western Digital  | Ultrastar DC SN630 NVMe SSD          | 1     | nvme       | [0627DB12DF](<Server/Lenovo/7X56CTO1WW/7X56CTO1WW HR630X/560D5AFC1336/RHEL-7/3.10.0-1160.15.2.EL7.X86_64/X86_64/0627DB12DF>) |
| 1b96:2400 | 1b96:0000 | Western Digital  | Ultrastar DC SN640 NVMe SSD          | 1     | nvme       | [66EE0BC524](<Server/Supermicro/Super/Super Server/40D662EC15C8/UBUNTU-18.04/4.15.0-143-GENERIC/X86_64/66EE0BC524>) |
| 1bb1:0100 | 1bb1:0121 | Seagate Techn... | Nytro Flash Storage                  | 1     | nvme       | [869C99ACED](<Server/Supermicro/Super/Super Server/AFDA788A3E18/UBUNTU-20.10/5.8.0-23-GENERIC/X86_64/869C99ACED>) |
| 1bb1:5012 | 1bb1:5012 | Seagate Techn... | FireCuda 510 SSD                     | 1     | nvme       | [937DE612E9](<Server/Supermicro/X10/X10DRi/50B36DEF01E7/DEBIAN-10/5.12.0-RC2-RECOMP/X86_64/937DE612E9>) |
| 1bb1:5016 | 1bb1:5016 | Seagate Techn... | FireCuda 520 SSD                     | 1     | nvme       | [86AB491564](<Server/Fujitsu/CELSIUS/CELSIUS R970/7E07629658CC/CENTOS-8/4.18.0-240.10.1.EL8_3.X86_64/X86_64/86AB491564>) |
| 1c5c:1639 | 1c5c:1639 | SK Hynix         | Non-Volatile memory controller       | 1     |            | [7EF7B85267](<Server/Supermicro/X9/X9SRA-X9SRA-3/6DA328B1EF68/UBUNTU-18.04/4.15.0-166-GENERIC/X86_64/7EF7B85267>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 103c:323a | 103c:3245 | Hewlett-Packard  | Smart Array G6 controllers           | 41    | hpsa       | [FE6B8CB2E4](<Server/Hewlett-Packard/ProLiant/ProLiant DL580 G7/68420A1A9387/FEDORA-35/5.15.16-200.FC35.X86_64/X86_64/FE6B8CB2E4>) |
| 103c:323b | 103c:3354 | Hewlett-Packard  | Smart Array Gen8 Controllers         | 29    | hpsa       | [1172390E59](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/2267C96ADE00/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/1172390E59>) |
| 1000:0079 | 1028:1f17 | LSI Logic / S... | MegaRAID SAS 2108 [Liberator]        | 23    | megarai... | [BCDCCDDEC2](<Server/Dell/PowerEdge/PowerEdge T610/EFB372134BAB/ZORIN-16/5.13.0-28-GENERIC/X86_64/BCDCCDDEC2>) |
| 1000:0060 | 1028:1f0c | LSI Logic / S... | MegaRAID SAS 1078                    | 22    | megarai... | [02E5C56A80](<Server/Dell/PowerEdge/PowerEdge R610/D7D0CF9B35C0/ROCKY-8.5/4.18.0-348.12.2.EL8_5.X86_64/X86_64/02E5C56A80>) |
| 1000:005d | 1000:9363 | LSI Logic / S... | MegaRAID SAS-3 3108 [Invader]        | 16    | megarai... | [2F38C3FD0E](<Server/Hyve/C4/C4I/09324DBA0E18/RHEL-7/3.10.0-1160.2.2.EL7.X86_64/X86_64/2F38C3FD0E>) |
| 1000:005f | 1028:1f44 | LSI Logic / S... | MegaRAID SAS-3 3008 [Fury]           | 16    | megarai... | [5011114071](<Server/Dell/PowerEdge/PowerEdge R240/3378DCFA2CDA/DEBIAN-11/5.13.19-4-PVE/X86_64/5011114071>) |
| 1000:005b | 1028:1f38 | LSI Logic / S... | MegaRAID SAS 2208 [Thunderbolt]      | 13    | megarai... | [7BF19C1CD2](<Server/Dell/PowerEdge/PowerEdge R720/2489ED365DE4/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/7BF19C1CD2>) |
| 8086:201d | 8086:0000 | Intel            | Volume Management Device NVMe RAI... | 13    | vmd        | [2E5507B849](<Server/Dell/Precision/Precision 7920 Tower/6DBFD1DBD45A/UBUNTU-20.04/5.10.0-1055-OEM/X86_64/2E5507B849>) |
| 1000:005d | 15d9:0809 | LSI Logic / S... | MegaRAID SAS-3 3108 [Invader]        | 11    | megarai... | [50AEBE4B28](<Server/Supermicro/SSG-6048/SSG-6048R-E1CR24H/8A7A52EA4807/CENTOS-8/4.18.0-348.2.1.EL8_5.X86_64/X86_64/50AEBE4B28>) |
| 1000:0079 | 1000:9263 | LSI Logic / S... | MegaRAID SAS 2108 [Liberator]        | 10    | megarai... | [A243FDE4E1](<Server/Oracle/Sun/Sun Fire X4270 M3/3AEA7677F53C/ZORIN-16/5.11.0-46-GENERIC/X86_64/A243FDE4E1>) |
| 8086:2826 | 1028:073a | Intel            | C600/X79 series chipset SATA RAID... | 9     | ahci       | [2E5507B849](<Server/Dell/Precision/Precision 7920 Tower/6DBFD1DBD45A/UBUNTU-20.04/5.10.0-1055-OEM/X86_64/2E5507B849>) |
| 103c:3239 | 103c:21c0 | Hewlett-Packard  | Smart Array Gen9 Controllers         | 8     | hpsa       | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 103c:323b | 103c:3351 | Hewlett-Packard  | Smart Array Gen8 Controllers         | 8     | hpsa       | [A28B637049](<Server/Hewlett-Packard/ProLiant/ProLiant DL380e Gen8/ECA2BB01C65F/RHEL-7/3.10.0-1160.EL7.X86_64/X86_64/A28B637049>) |
| 1000:005d | 1028:1f47 | LSI Logic / S... | MegaRAID SAS-3 3108 [Invader]        | 7     | megarai... | [C0AA1BF2F1](<Server/Dell/PowerEdge/PowerEdge R730xd/3856150DE2AC/FEDORA-32/5.6.6-300.FC32.X86_64/X86_64/C0AA1BF2F1>) |
| 1000:005d | 1028:1f49 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 7     | megarai... | [E4DEE6FAF7](<Server/Dell/PowerEdge/PowerEdge R530/2178C7DB8E3B/OPENSUSE-20210512/5.12.2-1-DEFAULT/X86_64/E4DEE6FAF7>) |
| 103c:3230 | 103c:3234 | Hewlett-Packard  | Smart Array Controller               | 7     | hpsa       | [24D4B5B8DB](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/9A14972DB3E8/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/24D4B5B8DB>) |
| 17d3:1880 | 17d3:1883 | Areca Technology | ARC-188x series PCIe 2.0/3.0 to S... | 7     | arcmsr     | [96079334BD](<Server/Gigabyte Technology/R182/R182-Z90-00/5D7AD81D6479/UBUNTU-20.04/5.4.0-80-GENERIC/X86_64/96079334BD>) |
| 1000:005b | 1028:1f35 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 6     | megarai... | [87A79FD79B](<Server/Dell/PowerEdge/PowerEdge T320/9CB0E7FD4912/LINUXMINT-20.1/5.4.0-66-GENERIC/X86_64/87A79FD79B>) |
| 1000:005d | 1028:1f42 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 6     | megarai... | [E757687F86](<Server/Dell/PowerEdge/PowerEdge R440/EE4BDD6E98EC/DEBIAN-10/4.19.0-17-AMD64/X86_64/E757687F86>) |
| 1000:0060 | 1028:1f0b | LSI Logic / S... | MegaRAID SAS 1078                    | 6     | megarai... | [2A289951DE](<Server/Dell/PowerEdge/PowerEdge T310/D04C74D757A7/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/2A289951DE>) |
| 1000:0073 | 1028:1f51 | LSI Logic / S... | MegaRAID SAS 2008 [Falcon]           | 6     | megarai... | [F5F07BFFC2](<Server/Others/0XWDCF/0XWDCF A01/60D0A665A1F8/DEBIAN-11/5.13.19-3-PVE/X86_64/F5F07BFFC2>) |
| 1028:0015 | 1028:1f03 | Dell             | PowerEdge Expandable RAID control... | 6     | megarai... | [C022B50299](<Server/Dell/PowerEdge/PowerEdge 2900/2D778EC201D6/FEDORA-35/5.16.8-200.FC35.X86_64/X86_64/C022B50299>) |
| 1000:0014 | 1d49:0602 | Broadcom / LSI   | MegaRAID Tri-Mode SAS3516            | 5     | megarai... | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 1000:005b | 1028:1f34 | LSI Logic / S... | MegaRAID SAS 2208 [Thunderbolt]      | 5     | megarai... | [FB712E669E](<Server/Dell/PowerEdge/PowerEdge R620/9296BE589422/ARCH/5.15.2-ARCH1-1/X86_64/FB712E669E>) |
| 1000:005f | 1028:1f4b | LSI Logic / S... | MegaRAID SAS-3 3008 [Fury]           | 5     | megarai... | [F3CBAC183E](<Server/Dell/PowerEdge/PowerEdge R7515/9A7A286BD3E1/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/F3CBAC183E>) |
| 1000:0079 | 1014:03b2 | LSI Logic / S... | MegaRAID SAS 2108 [Liberator]        | 5     | megarai... | [430B4F4EDF](<Server/Supermicro/H8/H8DGU/8ACEE5E956B2/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/430B4F4EDF>) |
| 103c:3230 | 103c:3235 | Hewlett-Packard  | Smart Array Controller               | 5     | hpsa       | [59421FDCD1](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/D89FE0F9FFD3/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/59421FDCD1>) |
| 1b4b:9485 | 1b4b:9480 | Marvell Techn... | 88SE9485 SAS/SATA 6Gb/s controller   | 5     | mvsas      | [AAEEE85BE7](<Server/Supermicro/SYS-6028/SYS-6028R-WTRT/690B86B530B0/DEBIAN-11/4.19.0-17-AMD64/X86_64/AAEEE85BE7>) |
| 1000:0016 | 1028:1fcb | LSI Logic / S... | MegaRAID Tri-Mode SAS3508            | 4     | megarai... | [FCC6D41C03](<Server/Dell/PowerEdge/PowerEdge R740/203EBCE27AC6/CENTOS-7/3.10.0-1160.45.1.EL7.X86_64/X86_64/FCC6D41C03>) |
| 1000:0016 | 1028:1fcd | LSI Logic / S... | MegaRAID Tri-Mode SAS3508            | 4     | megarai... | [E9A1FC86F9](<Server/Dell/PowerEdge/PowerEdge R740/4DA16FD481F3/UBUNTU-18.04/4.15.0-118-GENERIC/X86_64/E9A1FC86F9>) |
| 1000:0016 | 19e5:d215 | Broadcom / LSI   | MegaRAID Tri-Mode SAS3508            | 4     | megarai... | [AD903545CE](<Server/Huawei/2288H/2288H V5/94600F3C6456/ALT-9.1/5.4.51-STD-DEF-ALT1/X86_64/AD903545CE>) |
| 1000:005b | 1014:040b | LSI Logic / S... | MegaRAID SAS 2208 [Thunderbolt]      | 4     | megarai... | [8D55479353](<Server/IBM/System/System x3550 M4 Server -[7914AC1]/D13FC123FD88/XUBUNTU-21.04/5.11.0-22-GENERIC/X86_64/8D55479353>) |
| 1000:005b | 1028:1f31 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 4     | megarai... | [C685A0033B](<Server/Dell/PowerEdge/PowerEdge T420/33ABAEDD79BF/OPENSUSE-LEAP-15.3/5.3.18-59.34-DEFAULT/X86_64/C685A0033B>) |
| 1000:005b | 8086:3510 | LSI Logic / S... | MegaRAID SAS 2208 [Thunderbolt]      | 4     | megarai... | [FE1E6CFF79](<Server/Intel/S4600/S4600LH/F04F47B2E9E9/UBUNTU-18.04/4.15.0-76-GENERIC/X86_64/FE1E6CFF79>) |
| 1000:005d | 1000:9361 | LSI Logic / S... | MegaRAID SAS-3 3108 [Invader]        | 4     | megarai... | [8D109AC7B4](<Server/Supermicro/Super/Super Server/90C71D2FD9A2/ALT-9.1/5.4.51-STD-DEF-ALT1/X86_64/8D109AC7B4>) |
| 1000:0060 | 1734:10f9 | Broadcom / LSI   | MegaRAID SAS 1078                    | 4     | megarai... | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 1000:0079 | 1028:1f16 | Broadcom / LSI   | MegaRAID SAS 2108 [Liberator]        | 4     | megarai... | [F46A021C88](<Server/Dell/PowerEdge/PowerEdge R410/9BE3F9CEE048/LUBUNTU-20.04/5.4.0-83-GENERIC/X86_64/F46A021C88>) |
| 1000:0016 | 1d49:0601 | Broadcom / LSI   | MegaRAID Tri-Mode SAS3508            | 3     | megarai... | [FF6113B91D](<Server/Lenovo/ThinkSystem/ThinkSystem SR630 V2/ECB5C724E79D/CENTOS-7/3.10.0-1160.49.1.EL7.X86_64/X86_64/FF6113B91D>) |
| 1000:005d | 1014:0454 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 3     | megarai... | [C7B39E92CA](<Server/Dell/PowerEdge/PowerEdge R730xd/A83FA4403312/DEBIAN-10/4.19.147-RIVOREO-AMD64/X86_64/C7B39E92CA>) |
| 1000:0072 | 1000:0072 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 3     | mpt3sas    | [ABE0B5613A](<Server/Dell/PowerEdge/PowerEdge T320/EB32D3263597/UBUNTU-20.04/5.4.0-74-GENERIC/X86_64/ABE0B5613A>) |
| 103c:3239 | 103c:21c7 | Hewlett-Packard  | Smart Array Gen9 Controllers         | 3     | hpsa       | [1A73C74FBB](<Server/Supermicro/Super/Super Server/909986EADB14/UBUNTU-21.04/5.11.0-38-GENERIC/X86_64/1A73C74FBB>) |
| 103c:323a | 103c:3243 | Hewlett-Packard  | Smart Array G6 controllers           | 3     | hpsa       | [28B04C3004](<Server/Hewlett-Packard/ProLiant/ProLiant DL180 G6/D1FDB54452D3/RHEL-7/3.10.0-957.10.1.EL7.YAHOO.20190320.30.X86_64/X86_64/28B04C3004>) |
| 103c:323b | 103c:3355 | Hewlett-Packard  | Smart Array Gen8 Controllers         | 3     | hpsa       | [9F21E5D9D9](<Server/Hewlett-Packard/ProLiant/ProLiant BL460c Gen8/1DB9D4472AA8/ARCH-ROLLING/5.10.79-1-LTS/X86_64/9F21E5D9D9>) |
| 13c1:1003 | 13c1:1003 | 3ware            | 9550SX SATA-II RAID PCI-X            | 3     | 3w_9xxx    | [0A3F6D305B](<Server/Powerleader/PR1710/PR1710N/AF12FD7CB1BD/DEBIAN-10/5.4.78-2-PVE/X86_64/0A3F6D305B>) |
| 17d3:1880 | 17d3:1880 | Areca Technology | ARC-188x series PCIe 2.0/3.0 to S... | 3     | arcmsr     | [B3C09674CF](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/31A946D98462/UBUNTU-18.04/4.15.0-142-GENERIC/X86_64/B3C09674CF>) |
| 8086:201d | 1043:875d | Intel            | Volume Management Device NVMe RAI... | 3     | vmd        | [E4BE3F2344](<Server/ASUSTek Computer/ESC8000/ESC8000 G4-10G/C093968548F7/UBUNTU-20.04/5.4.0-74-GENERIC/X86_64/E4BE3F2344>) |
| 8086:2826 | 1028:0739 | Intel            | C600/X79 series chipset SATA RAID... | 3     | ahci       | [52B7CECCFF](<Server/Dell/Precision/Precision 7820 Tower/4D5B9AB98F40/UBUNTU-18.04/5.4.0-65-GENERIC/X86_64/52B7CECCFF>) |
| 8086:2826 | 103c:81c7 | Intel            | C600/X79 series chipset SATA RAID... | 3     | ahci       | [5299B4DA87](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/68BC2092E093/UBUNTU-18.04/5.4.0-74-GENERIC/X86_64/5299B4DA87>) |
| 8086:2826 | 8086:7270 | Intel            | C600/X79 series chipset SATA RAID... | 3     | ahci       | [73518731A1](<Server/Supermicro/X11/X11DPi-N/6D6FD3049691/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/73518731A1>) |
| 8086:2827 | 103c:81c6 | Intel            | C610/X99 series chipset sSATA Con... | 3     | ahci       | [679871CFEC](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/E621F1A07D2C/UBUNTU-20.04/5.4.0-84-GENERIC/X86_64/679871CFEC>) |

### Storage/sas (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1000:0072 | 1028:1f1c | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 11    | mpt3sas    | [7C1FA00B21](<Server/Intel/S1200/S1200SP/4B4C83B49974/CENTOS-7/4.4.241-1.EL7.ELREPO.X86_64/X86_64/7C1FA00B21>) |
| 8086:1d6b | 1043:84ef | Intel            | C602 chipset 4-Port SATA Storage ... | 11    | isci       | [0D39F4F066](<Server/ASUSTek Computer/Z9PE-D16/Z9PE-D16 Series/7948CC9F2801/UBUNTU-18.04/5.4.0-91-GENERIC/X86_64/0D39F4F066>) |
| 1000:0072 | 15d9:0400 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 10    | mpt3sas    | [7A720A4E41](<Server/Supermicro/Super/Super Server/06E41BB3C6CC/ROCKY-8.5/4.18.0-348.12.2.EL8_5.X86_64/X86_64/7A720A4E41>) |
| 1000:0072 | 1000:3020 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 8     | mpt3sas    | [580838BF3C](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/1D52FD217A6F/DEBIAN-11/5.10.42+TRUENAS/X86_64/580838BF3C>) |
| 1000:0097 | 15d9:0808 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 8     | mpt3sas    | [2BB4102B1C](<Server/Supermicro/Super/Super Server/45717F18B5CF/CENTOS-8/4.18.0-240.22.1.EL8_3.X86_64/X86_64/2BB4102B1C>) |
| 1000:0072 | 1028:1f1d | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 6     | mpt3sas    | [E0E68EFC2F](<Server/Dell/PowerEdge/PowerEdge R210 II/D6DEF28F8714/UBUNTU-18.04/4.15.0-109-GENERIC/X86_64/E0E68EFC2F>) |
| 1000:0072 | 1028:1f1e | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 5     | mpt3sas    | [0335142464](<Server/Dell/PowerEdge/PowerEdge R515/0AC29BF27784/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/0335142464>) |
| 1000:0072 | 1000:3040 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 4     | mpt3sas    | [430B4F4EDF](<Server/Supermicro/H8/H8DGU/8ACEE5E956B2/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/430B4F4EDF>) |
| 19e5:a230 |           | Huawei Techno... | HiSilicon SAS 3.0 HBA                | 4     | hisi_sa... | [F548D0A0A9](<Server/Huawei/TaiShan/TaiShan 200/7F69DEB6BBD3/RELS-2019.1/5.10.42-GENERIC-1ROSA2019.1-ARM64/AARCH64/F548D0A0A9>) |
| 8086:1d6b | 15d9:062a | Intel            | C602 chipset 4-Port SATA Storage ... | 4     | isci       | [7F43788673](<Server/Supermicro/X9/X9SRA-X9SRA-3/E419ADCAE2D8/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/7F43788673>) |
| 8086:1d6b | 8086:35a1 | Intel            | C602 chipset 4-Port SATA Storage ... | 4     | isci       | [FE1E6CFF79](<Server/Intel/S4600/S4600LH/F04F47B2E9E9/UBUNTU-18.04/4.15.0-76-GENERIC/X86_64/FE1E6CFF79>) |
| 9005:028f | 103c:0602 | Adaptec          | Smart Storage PQI SAS                | 4     | smartpqi   | [7AB4F05613](<Server/HPE/ProLiant/ProLiant DL360 Gen10/4443D3087423/UBUNTU-18.04/4.15.0-135-GENERIC/X86_64/7AB4F05613>) |
| 1000:0086 | 15d9:0691 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 3     | mpt3sas    | [CEF9CEED55](<Server/Supermicro/X10/X10SL7-F/F0DE0FC4ED27/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/CEF9CEED55>) |
| 1000:0087 | 1000:3040 | LSI Logic / S... | SAS2308 PCI-Express Fusion-MPT SAS-2 | 3     | mpt3sas    | [909B88F852](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/BE425EE16F85/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/909B88F852>) |
| 1000:0097 | 1000:30e0 | LSI Logic / S... | SAS3008 PCI-Express Fusion-MPT SAS-3 | 3     | mpt3sas    | [F9D5463C17](<Server/Supermicro/X9/X9SRH-7F-7TF/D0C49383632B/POP!_OS-20.04/5.4.0-7634-GENERIC/X86_64/F9D5463C17>) |
| 8086:1d6b | 15d9:0626 | Intel            | C602 chipset 4-Port SATA Storage ... | 3     | isci       | [DE8D4D24B6](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/050383036EDE/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/DE8D4D24B6>) |
| 8086:1d6b | 15d9:0636 | Intel            | C602 chipset 4-Port SATA Storage ... | 3     | isci       | [31684AD7E4](<Server/Supermicro/X9/X9DRW/55D2AD4AF0CF/UBUNTU-21.04/5.11.0-44-GENERIC/X86_64/31684AD7E4>) |
| 1000:0064 | 1000:30d0 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 2     | mpt3sas    | [1DF72E1613](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/2D28DE8C0BFA/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/1DF72E1613>) |
| 1000:0070 | 1000:3010 | LSI Logic / S... | SAS2004 PCI-Express Fusion-MPT SA... | 2     | mpt3sas    | [4CE6A061A6](<Server/Dell/PowerEdge/PowerEdge R720/D87975CF195B/UBUNTU-20.04/5.8.0-49-GENERIC/X86_64/4CE6A061A6>) |
| 1000:0097 | 1000:0090 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 2     | mpt3sas    | [2903921AEB](<Server/AIC/SB302/SB302-LB/98EDCF68ED2D/CENTOS-8/4.18.0-80.EL8.X86_64/X86_64/2903921AEB>) |
| 1000:0097 | 1028:1f53 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 2     | mpt3sas    | [DF9A63BE43](<Server/Dell/PowerEdge/PowerEdge R740xd/62F4A9812E0F/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/DF9A63BE43>) |
| 8086:1d6b | 1170:0054 | Intel            | C602 chipset 4-Port SATA Storage ... | 2     | isci       | [1B5977B024](<Server/ZTSYSTEMS/Z/Z801/2920EC336BF6/RHEL-7/3.10.0-1062.4.3.EL7.YAHOO.20191113.49.X86_64/X86_64/1B5977B024>) |
| 8086:1d6b | 15d9:0660 | Intel            | C602 chipset 4-Port SATA Storage ... | 2     | isci       | [AFE42B7E58](<Server/SYNNEX/HYVE-ZEUS/HYVE-ZEUS/3AD7D5C11C7F/DEBIAN-10/5.4.34-1-PVE/X86_64/AFE42B7E58>) |
| 1000:005d | 8086:3a1e | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 1     | megarai... | [98C12554CB](<Server/Intel/S1200/S1200SP/FDDD794115FC/CLEAR-LINUX-OS-34560/5.10.33-1036.NATIVE/X86_64/98C12554CB>) |
| 1000:0064 | 1000:3030 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 1     | mpt3sas    | [32951A000F](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/E782FD83F7D2/UBUNTU-20.04/5.8.0-53-GENERIC/X86_64/32951A000F>) |
| 1000:0064 | 15d9:083c | LSI Logic / S... | SAS2116 PCI-Express Fusion-MPT SA... | 1     | mpt3sas    | [DB25C87154](<Server/Supermicro/Super/Super Server/71B3E013BFED/ARCH/4.15.5-1-ARCH/X86_64/DB25C87154>) |
| 1000:0070 | 1014:03f7 | LSI Logic / S... | SAS2004 PCI-Express Fusion-MPT SA... | 1     | mpt2sas    | [D7CBC31CEE](<Server/IBM/BladeCenter/BladeCenter HS23 -[7875MFM]-/D5DD0E377016/RELS-6.9/2.6.32-696.EL6.X86_64/X86_64/D7CBC31CEE>) |
| 1000:0070 | 1014:03f8 | Broadcom / LSI   | SAS2004 PCI-Express Fusion-MPT SA... | 1     | mpt2sas    | [7C109612B9](<Server/IBM/Flex/Flex System x240 Compute Node -[8737AC1]-/6F6DEF6E7D5A/CENTOS-7/3.10.0-1127.8.2.EL7.X86_64/X86_64/7C109612B9>) |
| 1000:0072 | 1000:3050 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mpt3sas    | [0B2E10175B](<Server/Supermicro/X8/X8DAH/4A92FB7AB3EE/UBUNTU-18.04/4.15.0-88-GENERIC/X86_64/0B2E10175B>) |
| 1000:0072 | 1000:3060 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mpt3sas    | [D52DB39EEB](<Server/Dell/PowerEdge/PowerEdge R210 II/D25E2376C7EE/FEDORA-33/5.13.4-100.FC33.X86_64/X86_64/D52DB39EEB>) |
| 1000:0072 | 1000:3080 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mpt3sas    | [7D9FDF4B73](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/16075FBC6C06/UBUNTU-21.10/5.15.1-051501-GENERIC/X86_64/7D9FDF4B73>) |
| 1000:0072 | 1014:03cb | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mpt3sas    | [2B9980B42B](<Server/Dell/PowerEdge/PowerEdge T410/B94D2AA4D7E6/UBUNTU-20.04/5.8.0-41-GENERIC/X86_64/2B9980B42B>) |
| 1000:0072 | 1170:6019 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mpt3sas    | [395F17CE3F](<Server/Dell/PowerEdge/PowerEdge C8220/5BC95B2B42C7/UBUNTU-20.04/5.8.0-55-GENERIC/X86_64/395F17CE3F>) |
| 1000:007e | 1000:0507 | Broadcom / LSI   | SSS6200 PCI-Express Flash SSD        | 1     | mpt3sas    | [BA4FFBDA6D](<Server/Dell/PowerEdge/PowerEdge R610/1D256EA1AA3C/XUBUNTU-20.04/5.4.0-48-GENERIC/X86_64/BA4FFBDA6D>) |
| 1000:007e | 108e:0581 | Broadcom / LSI   | SSS6200 PCI-Express Flash SSD        | 1     | mpt3sas    | [A243FDE4E1](<Server/Oracle/Sun/Sun Fire X4270 M3/3AEA7677F53C/ZORIN-16/5.11.0-46-GENERIC/X86_64/A243FDE4E1>) |
| 1000:0087 | 1000:0087 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mpt3sas    | [BA0F3C3B41](<Server/Huawei/RH1288/RH1288 V3/DCCC7932E1B0/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/BA0F3C3B41>) |
| 1000:0087 | 1000:3020 | LSI Logic / S... | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mpt3sas    | [7DC714253B](<Server/Intel/S2600/S2600CP/74C94B7C7A62/DEBIAN-9/4.14.0-0.BPO.2-AMD64/X86_64/7DC714253B>) |
| 1000:0087 | 1028:1f34 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mpt3sas    | [FBDF83F7FF](<Server/Dell/PowerEdge/PowerEdge R720/4D59BA33C94F/DEBIAN-11/5.11.22-2-PVE/X86_64/FBDF83F7FF>) |
| 1000:0087 | 1028:1f35 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mpt3sas    | [C9C876F0E7](<Server/Dell/PowerEdge/PowerEdge T320/8A9310CFABA2/UBUNTU-20.04/5.11.0-34-GENERIC/X86_64/C9C876F0E7>) |
| 1000:0087 | 1028:1f38 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mpt3sas    | [29F49B3A79](<Server/Dell/PowerEdge/PowerEdge R520/F12E87D98729/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/29F49B3A79>) |
| 1000:0087 | 1590:0042 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mpt3sas    | [A14015F487](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/FC3112711290/UBUNTU-18.04/4.15.0-99-GENERIC/X86_64/A14015F487>) |
| 1000:0087 | 8086:3519 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mpt3sas    | [E70645D3E6](<Server/Intel/W2600/W2600CR/5A75A85091D9/UBUNTU-20.04/5.4.0-80-GENERIC/X86_64/E70645D3E6>) |
| 1000:0097 | 1000:30a0 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 1     | mpt3sas    | [21E2FBBB75](<Server/Supermicro/Super/Super Server/A70DB16AB074/UBUNTU-18.04/4.15.0-29-GENERIC/X86_64/21E2FBBB75>) |
| 1000:0097 | 1043:860c | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 1     | mpt3sas    | [C934F8E023](<Server/ASUSTek Computer/RS720/RS720Q-E9-RS24-S/5DCDC5F18084/GENTOO-2.7/5.10.18-HARDENED1/X86_64/C934F8E023>) |
| 1000:00ac | 1d49:0203 | Broadcom / LSI   | SAS3416 Fusion-MPT Tri-Mode I/O C... | 1     | mpt3sas    | [928EE22E71](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 -[7X06CTO1WW]-/5D8AB08CFEB3/CENTOS-7/3.10.0-1160.21.1.EL7.X86_64/X86_64/928EE22E71>) |
| 1000:00af | 1d49:0202 | Broadcom / LSI   | SAS3408 Fusion-MPT Tri-Mode I/O C... | 1     | mpt3sas    | [928EE22E71](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 -[7X06CTO1WW]-/5D8AB08CFEB3/CENTOS-7/3.10.0-1160.21.1.EL7.X86_64/X86_64/928EE22E71>) |
| 1000:00c4 | 1000:3190 | Broadcom / LSI   | SAS3224 PCI-Express Fusion-MPT SAS-3 | 1     | mpt3sas    | [00FDD71981](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/B8B03C82409C/GENTOO-2.6/5.4.48-GENTOO/X86_64/00FDD71981>) |
| 1000:00c4 | 1000:31a0 | Broadcom / LSI   | SAS3224 PCI-Express Fusion-MPT SAS-3 | 1     | mpt3sas    | [E60EC405AF](<Server/Supermicro/Super/Super Server/F5F261808B48/GENTOO-2.6/5.15.19-GENTOO/X86_64/E60EC405AF>) |
| 11f8:8001 |           | PMC-Sierra       | SPC 8x6G SAS/SATA (storport)         | 1     | pm80xx     | [4F5756D065](<Server/Oracle/Sun/Sun Fire X4270 M2 SERVER/FF52124EF1E7/FEDORA-32/5.8.12-200.FC32.X86_64/X86_64/4F5756D065>) |
| 8086:1d68 | 15d9:0626 | Intel            | C606 chipset Dual 4-Port SATA/SAS... | 1     | isci       | [00FDD71981](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/B8B03C82409C/GENTOO-2.6/5.4.48-GENTOO/X86_64/00FDD71981>) |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1000:0058 | 1028:1f0e | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 6     | mptsas     | [2CAE1B1D80](<Server/Dell/PowerEdge/PowerEdge T310/1B407A78D4C5/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/2CAE1B1D80>) |
| 1000:0058 | 1028:1f0f | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 6     | mptsas     | [24358FA4BD](<Server/Dell/PowerEdge/PowerEdge R410/C25F044F8862/FEDORA-34/5.14.11-200.FC34.X86_64/X86_64/24358FA4BD>) |
| 1000:0056 | 1014:03bb | LSI Logic / S... | SAS1064ET PCI-Express Fusion-MPT SAS | 5     | mptsas     | [882EA8E25E](<Server/IBM/System/System x3250 M3 -[4252K4G]-/76E08604766E/DEBIAN-10/5.4.106-1-PVE/X86_64/882EA8E25E>) |
| 1000:0058 | 1028:1f10 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 5     | mptsas     | [5FBC90E0CD](<Server/Dell/PowerEdge/PowerEdge R610/EBF19EC41F61/UBUNTU-20.04/5.8.0-50-GENERIC/X86_64/5FBC90E0CD>) |
| 1000:0058 | 1014:0394 | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 3     | mptsas     | [B85DBD88F5](<Server/IBM/System/System x3650 M2 -[7947AC1]-/B4AFB5C90D39/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/B85DBD88F5>) |
| 1000:0054 | 1028:1f09 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 2     | mptsas     | [701B89AC2E](<Server/IBM/System/System x3650 -[7979B9U]-/BC2D6FA78D8E/OPENMANDRIVA-4.2/5.11.12-DESKTOP-1OMV4002/X86_64/701B89AC2E>) |
| 1000:0056 | 152d:896d | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 2     | mptsas     | [23E536F087](<Server/Quanta/QSSC-98/QSSC-98J_C2/03AF1302C679/CENTOS-6.9/2.6.32-754.6.3.EL6.X86_64/X86_64/23E536F087>) |
| 1000:0056 | 8086:3486 | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 2     | mptsas     | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 1000:0058 | 15d9:0001 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 2     | mptsas     | [F645C4227C](<Server/Supermicro/X8/X8DT3/095547D33119/LMDE-4/4.19.0-16-AMD64/X86_64/F645C4227C>) |
| 9005:8017 | 9005:0045 | Adaptec          | ASC-29320ALP U320                    | 2     | aic79xx    | [096D3E62FE](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/7FC37BA0963D/FEDORA-34/5.12.3-300.FC34.X86_64/X86_64/096D3E62FE>) |
| 1000:000f | 0e11:7004 | Broadcom / LSI   | 53c875                               | 1     | sym53c8xx  | [AFF808A68F](<Server/Supermicro/X8/X8DTL/2CC89667A3DA/UBUNTU-18.04/4.15.0-99-GENERIC/X86_64/AFF808A68F>) |
| 1000:0030 | 1000:1000 | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mptspi     | [18B25AC51A](<Server/TYAN Computer/S/S4882/84BBA0EA52AC/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/18B25AC51A>) |
| 1000:0030 | 1000:50c0 | LSI Logic / S... | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mptspi     | [3F4700F256](<Server/Dell/PowerEdge/PowerEdge T610/A5921AA6471A/CENTOS-7/3.10.0-693.11.1.EL7.X86_64/X86_64/3F4700F256>) |
| 1000:0030 | 1014:026c | LSI Logic / S... | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mptspi     | [46973B5B05](<Server/IBM/eserver/eserver xSeries 235 -[86712AX]-/93A8BF1AD0B5/ROSA-2014.1/3.14.44-NRJ-DESKTOP-2ROSA-I586/I686/46973B5B05>) |
| 1000:0030 | 1028:016e | LSI Logic / S... | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mptspi     | [76EF1C8CA9](<Server/Dell/PowerEdge/PowerEdge 2800/2245B0434B88/UBUNTU-18.04/4.15.0-47-GENERIC/X86_64/76EF1C8CA9>) |
| 1000:0054 | 1000:30e0 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 1     | mptsas     | [E0E805180D](<Server/Others/Others/Others/7994F07888CD/DEBIAN-8/4.1.42-RIVOREO-POWERPC64/PPC64/E0E805180D>) |
| 1000:0054 | 1734:1082 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 1     | mptsas     | [872AE76863](<Server/Fujitsu Siemens/PRIMERGY/PRIMERGY RX300 S3/2366E6CCAF09/OPENSUSE-LEAP-15.1/4.12.14-LP151.28.91-DEFAULT/X86_64/872AE76863>) |
| 1000:0054 | 1734:10b9 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 1     | mptsas     | [A0F9679F57](<Server/Fujitsu Siemens/PRIMERGY/PRIMERGY RX330 S1/BBBDB6433647/UBUNTU-18.04/4.15.0-112-GENERIC/X86_64/A0F9679F57>) |
| 1000:0054 | 8086:3504 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 1     | mptsas     | [A61FFACB08](<Server/Intel/S5000/S5000PAL/A2AA6EE937D8/UBUNTU-18.04/5.0.0-37-GENERIC/X86_64/A61FFACB08>) |
| 1000:0056 | 1734:1131 | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 1     | mptsas     | [28EB3733CA](<Server/Fujitsu/PRIMERGY/PRIMERGY RX200 S6/A598FCA268BC/UBUNTU-20.04/5.4.0-88-GENERIC/X86_64/28EB3733CA>) |
| 1000:0056 | 8086:346c | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 1     | mptsas     | [390F15B7F9](<Server/Intel/S5000/S5000PAL/74FE128B70DE/CENTOS-7/3.10.0-1062.1.1.EL7.X86_64/X86_64/390F15B7F9>) |
| 1000:0058 | 1000:3080 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mptsas     | [8CF8F98A53](<Server/Fujitsu/PRIMERGY/PRIMERGY/41B1E7A57925/FEDORA-35/5.14.10-300.FC35.X86_64/X86_64/8CF8F98A53>) |
| 1000:0058 | 1000:30a0 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mptsas     | [E5AEAF13AE](<Server/Intel/S3210/S3210SH/9BAA0B7E268E/UBUNTU-18.04/4.15.0-64-GENERIC/X86_64/E5AEAF13AE>) |
| 1000:0058 | 1000:3150 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mptsas     | [8F6E544820](<Server/Sun Microsystems/Sun/Sun Fire X4270 SERVER/38FCB3A1E58B/FEDORA-34/5.11.11-300.FC34.X86_64/X86_64/8F6E544820>) |
| 1000:0058 | 1000:7016 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mptsas     | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 1000:0058 | 1734:1130 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mptsas     | [43C0756BA6](<Server/Fujitsu/PRIMERGY/PRIMERGY RX300 S5/8D101F548ADF/OPENSUSE-LEAP-15.1/4.12.14-LP151.28.91-DEFAULT/X86_64/43C0756BA6>) |
| 1000:0059 | 15d9:0006 | Broadcom / LSI   | MegaRAID SAS 8208ELP/8208ELP         | 1     | mptsas     | [8F945E0A15](<Server/Supermicro/X8/X8DTL/7581500BE1DB/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/8F945E0A15>) |
| 1069:b166 | 1014:02d3 | Mylex            | AcceleRAID 600/500/400/Sapphire s... | 1     | ipr        | [E0E805180D](<Server/Others/Others/Others/7994F07888CD/DEBIAN-8/4.1.42-RIVOREO-POWERPC64/PPC64/E0E805180D>) |
| 9004:5078 | 9004:7850 | Adaptec          | AIC-7850T/7856T [AVA-2902/4/6 / A... | 1     | aic7xxx    | [171EE8DB12](<Server/Supermicro/C7/C7Z87/4BD99E9BA2B9/XUBUNTU-19.10/5.3.0-18-LOWLATENCY/X86_64/171EE8DB12>) |
| 9005:00c0 | 9005:f620 | Adaptec          | AHA-3960D / AIC-7899A U160/m         | 1     | aic7xxx    | [CA96304CAC](<Server/Dell/PowerEdge/PowerEdge 1950/E6782D539697/POP!_OS-20.04/5.15.15-76051515-GENERIC/X86_64/CA96304CAC>) |
| 9005:801f | 8086:341a | Adaptec          | AIC-7902 U320                        | 1     | aic79xx    | [37AA8C0E8E](<Server/Intel/SE7501WV2S/SE7501WV2S A99386-110/784B87202334/UBUNTU-18.04/4.15.0-108-GENERIC/I686/37AA8C0E8E>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:204e | 8086:0000 | Intel            | Sky Lake-E M3KTI Registers           | 125   | skx_uncore | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2018 | 8086:0000 | Intel            | Sky Lake-E M2PCI Registers           | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2035 |           | Intel            | Sky Lake-E RAS Configuration Regi... | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2040 | 8086:0000 | Intel            | Sky Lake-E Integrated Memory Cont... | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2041 | 8086:0000 | Intel            | Sky Lake-E Integrated Memory Cont... | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2042 | 8086:0000 | Intel            | Sky Lake-E Integrated Memory Cont... | 120   | skx_uncore | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2043 | 8086:0000 | Intel            | Sky Lake-E Integrated Memory Cont... | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2044 | 8086:0000 | Intel            | Sky Lake-E Integrated Memory Cont... | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2045 | 8086:0000 | Intel            | Sky Lake-E LM Channel 1              | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2046 | 8086:0000 | Intel            | Sky Lake-E LMS Channel 1             | 120   | skx_uncore | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2047 | 8086:0000 | Intel            | Sky Lake-E LMDP Channel 1            | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2048 | 8086:0000 | Intel            | Sky Lake-E DECS Channel 2            | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2049 | 8086:0000 | Intel            | Sky Lake-E LM Channel 2              | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:204a | 8086:0000 | Intel            | Sky Lake-E LMS Channel 2             | 120   | skx_uncore | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:204b | 8086:0000 | Intel            | Sky Lake-E LMDP Channel 2            | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2054 | 8086:0000 | Intel            | Sky Lake-E CHA Registers             | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2055 | 8086:0000 | Intel            | Sky Lake-E CHA Registers             | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2056 | 8086:0000 | Intel            | Sky Lake-E CHA Registers             | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2057 | 8086:0000 | Intel            | Sky Lake-E CHA Registers             | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2066 | 8086:0000 | Intel            | Sky Lake-E Integrated Memory Cont... | 120   | skx_uncore | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2080 | 8086:0000 | Intel            | Sky Lake-E PCU Registers             | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2081 | 8086:0000 | Intel            | Sky Lake-E PCU Registers             | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2082 | 8086:0000 | Intel            | Sky Lake-E PCU Registers             | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2083 | 8086:0000 | Intel            | Sky Lake-E PCU Registers             | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2084 | 8086:0000 | Intel            | Sky Lake-E PCU Registers             | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2085 | 8086:0000 | Intel            | Sky Lake-E PCU Registers             | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2086 | 8086:0000 | Intel            | Sky Lake-E PCU Registers             | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:208d | 8086:0000 | Intel            | Sky Lake-E CHA Registers             | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:208e | 8086:0000 | Intel            | Sky Lake-E CHA Registers             | 120   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2016 | 8086:0000 | Intel            | Sky Lake-E Ubox Registers            | 119   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2025 |           | Intel            | Sky Lake-E RAS                       | 119   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2014 | 8086:0000 | Intel            | Sky Lake-E Ubox Registers            | 117   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2034 | 8086:0000 | Intel            | Sky Lake-E VT-d                      | 115   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2059 | 8086:0000 | Intel            | Sky Lake-E UPI Registers             | 115   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2024 | 8086:0000 | Intel            | Sky Lake-E MM/Vt-d Configuration ... | 113   |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:2021 | 8086:0000 | Intel            | Sky Lake-E CBDMA Registers           | 100   | ioatdma    | [73518731A1](<Server/Supermicro/X11/X11DPi-N/6D6FD3049691/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/73518731A1>) |
| 8086:2f6e |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 64    |            | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 8086:2f6f |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 64    |            | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 8086:2f88 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 VCU    | 64    |            | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 8086:2f8a |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 VCU    | 64    |            | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 8086:2fae |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 64    |            | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 8086:2faf |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 64    |            | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 8086:2fb8 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 64    |            | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 8086:2fb9 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 64    |            | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 8086:2fba |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 64    |            | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 8086:2fbb |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 64    |            | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 8086:2fbe |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 64    |            | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 8086:2fbf |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 64    |            | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 8086:2ff8 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Buf... | 64    |            | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 8086:2ff9 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Buf... | 64    |            | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |

### Tv card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 109e:036e |           | Brooktree        | Bt878 Video Capture                  | 1     | bttv       | [B55D1DAEA5](<Server/Intel/S5500/S5500BC/EB1E1FCFB3A4/UBUNTU-MATE-19.10/5.3.0-51-GENERIC/X86_64/B55D1DAEA5>) |
| 109e:036e | 0070:ff04 | Brooktree        | Bt878 Video Capture                  | 1     | bttv       | [2C877CF870](<Server/Hewlett-Packard/ProLiant/ProLiant DL140 G2/7851FB932D49/ARCH/4.18.12-ARCH1-1-ARCH/X86_64/2C877CF870>) |
| 109e:036e | 800a:763d | Brooktree        | Bt878 Video Capture                  | 1     | bttv       | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 109e:036e | 800b:763d | Brooktree        | Bt878 Video Capture                  | 1     | bttv       | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 109e:036e | 800c:763d | Brooktree        | Bt878 Video Capture                  | 1     | bttv       | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 109e:036e | 800d:763d | Brooktree        | Bt878 Video Capture                  | 1     | bttv       | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 14f1:8880 | 0070:6a18 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 1     | cx23885    | [019914CC29](<Server/Supermicro/X10/X10SAE/6D8BBA911035/GENTOO-2.7/5.13.12-GENTOO/X86_64/019914CC29>) |
| 14f1:8880 | 0070:6b18 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 1     | cx23885    | [019914CC29](<Server/Supermicro/X10/X10SAE/6D8BBA911035/GENTOO-2.7/5.13.12-GENTOO/X86_64/019914CC29>) |
| 14f1:8880 | 1461:d439 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 1     |            | [D8325626F2](<Server/Dell/PowerEdge/PowerEdge T610/E71BEA809C78/SLED-15.1/4.12.14-197.64-DEFAULT/X86_64/D8325626F2>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 103c:3300 | 103c:3381 | Hewlett-Packard  | Integrated Lights-Out Standard Vi... | 61    | uhci_hcd   | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 8086:1d26 | 103c:18a9 | Intel            | C600/X79 series chipset USB2 Enha... | 45    | ehci_pci   | [1172390E59](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/2267C96ADE00/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/1172390E59>) |
| 8086:1d2d | 103c:18a9 | Intel            | C600/X79 series chipset USB2 Enha... | 45    | ehci_pci   | [1172390E59](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/2267C96ADE00/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/1172390E59>) |
| 8086:3a34 | 103c:330d | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 39    | uhci_hcd   | [FE6B8CB2E4](<Server/Hewlett-Packard/ProLiant/ProLiant DL580 G7/68420A1A9387/FEDORA-35/5.15.16-200.FC35.X86_64/X86_64/FE6B8CB2E4>) |
| 8086:3a35 | 103c:330d | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 39    | uhci_hcd   | [FE6B8CB2E4](<Server/Hewlett-Packard/ProLiant/ProLiant DL580 G7/68420A1A9387/FEDORA-35/5.15.16-200.FC35.X86_64/X86_64/FE6B8CB2E4>) |
| 8086:3a36 | 103c:330d | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 39    | uhci_hcd   | [FE6B8CB2E4](<Server/Hewlett-Packard/ProLiant/ProLiant DL580 G7/68420A1A9387/FEDORA-35/5.15.16-200.FC35.X86_64/X86_64/FE6B8CB2E4>) |
| 8086:3a39 | 103c:330d | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 39    | uhci_hcd   | [FE6B8CB2E4](<Server/Hewlett-Packard/ProLiant/ProLiant DL580 G7/68420A1A9387/FEDORA-35/5.15.16-200.FC35.X86_64/X86_64/FE6B8CB2E4>) |
| 8086:3a3a | 103c:330d | Intel            | 82801JI (ICH10 Family) USB2 EHCI ... | 39    | ehci_pci   | [FE6B8CB2E4](<Server/Hewlett-Packard/ProLiant/ProLiant DL580 G7/68420A1A9387/FEDORA-35/5.15.16-200.FC35.X86_64/X86_64/FE6B8CB2E4>) |
| 103c:3300 | 103c:3305 | Hewlett-Packard  | Integrated Lights-Out Standard Vi... | 28    | uhci_hcd   | [24D4B5B8DB](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/9A14972DB3E8/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/24D4B5B8DB>) |
| 103c:3300 | 103c:3309 | Hewlett-Packard  | Integrated Lights-Out Standard Vi... | 28    | uhci_hcd   | [FE6B8CB2E4](<Server/Hewlett-Packard/ProLiant/ProLiant DL580 G7/68420A1A9387/FEDORA-35/5.15.16-200.FC35.X86_64/X86_64/FE6B8CB2E4>) |
| 1912:0014 | ffff:ffff | Renesas Techn... | uPD720201 USB 3.0 Host Controller    | 22    | xhci_hcd   | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 8086:a1af | 8086:35ce | Intel            | C620 Series Chipset Family USB 3.... | 20    | xhci_hcd   | [36C4ACAC2D](<Server/Intel/S2600/S2600WFT/8DC9639F1DBF/ROCKY-8.4/4.18.0-305.10.2.EL8_4.X86_64/X86_64/36C4ACAC2D>) |
| 1002:4396 | 1002:4396 | AMD              | SB7x0/SB8x0/SB9x0 USB EHCI Contro... | 19    | ehci_pci   | [4A83A85932](<Server/AMD/AOPW-PLUS/AOPW-PLUS/B61223D18897/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/4A83A85932>) |
| 8086:a1af | 8086:7270 | Intel            | C620 Series Chipset Family USB 3.... | 19    | xhci_hcd   | [73518731A1](<Server/Supermicro/X11/X11DPi-N/6D6FD3049691/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/73518731A1>) |
| 1002:4399 | 1002:4396 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI2 Contr... | 18    | ohci_pci   | [4A83A85932](<Server/AMD/AOPW-PLUS/AOPW-PLUS/B61223D18897/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/4A83A85932>) |
| 8086:2934 | 1028:0235 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 18    | uhci_hcd   | [27639679E2](<Server/Dell/PowerEdge/PowerEdge R710/ACC1A39EDD24/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/27639679E2>) |
| 8086:2935 | 1028:0235 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 18    | uhci_hcd   | [27639679E2](<Server/Dell/PowerEdge/PowerEdge R710/ACC1A39EDD24/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/27639679E2>) |
| 8086:2937 | 1028:0235 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 18    | uhci_hcd   | [27639679E2](<Server/Dell/PowerEdge/PowerEdge R710/ACC1A39EDD24/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/27639679E2>) |
| 8086:2938 | 1028:0235 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 18    | uhci_hcd   | [27639679E2](<Server/Dell/PowerEdge/PowerEdge R710/ACC1A39EDD24/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/27639679E2>) |
| 8086:293a | 1028:0235 | Intel            | 82801I (ICH9 Family) USB2 EHCI Co... | 18    | ehci_pci   | [27639679E2](<Server/Dell/PowerEdge/PowerEdge R710/ACC1A39EDD24/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/27639679E2>) |
| 8086:293c | 1028:0235 | Intel            | 82801I (ICH9 Family) USB2 EHCI Co... | 18    | ehci_pci   | [27639679E2](<Server/Dell/PowerEdge/PowerEdge R710/ACC1A39EDD24/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/27639679E2>) |
| 8086:8d26 | 15d9:0821 | Intel            | C610/X99 series chipset USB Enhan... | 17    | ehci_pci   | [AAEEE85BE7](<Server/Supermicro/SYS-6028/SYS-6028R-WTRT/690B86B530B0/DEBIAN-11/4.19.0-17-AMD64/X86_64/AAEEE85BE7>) |
| 8086:8d2d | 15d9:0821 | Intel            | C610/X99 series chipset USB Enhan... | 17    | ehci_pci   | [AAEEE85BE7](<Server/Supermicro/SYS-6028/SYS-6028R-WTRT/690B86B530B0/DEBIAN-11/4.19.0-17-AMD64/X86_64/AAEEE85BE7>) |
| 8086:8d31 | 15d9:0821 | Intel            | C610/X99 series chipset USB xHCI ... | 17    | xhci_hcd   | [AAEEE85BE7](<Server/Supermicro/SYS-6028/SYS-6028R-WTRT/690B86B530B0/DEBIAN-11/4.19.0-17-AMD64/X86_64/AAEEE85BE7>) |
| 8086:1d26 | 1043:84ef | Intel            | C600/X79 series chipset USB2 Enha... | 16    | ehci_pci   | [0D39F4F066](<Server/ASUSTek Computer/Z9PE-D16/Z9PE-D16 Series/7948CC9F2801/UBUNTU-18.04/5.4.0-91-GENERIC/X86_64/0D39F4F066>) |
| 8086:1d2d | 1043:84ef | Intel            | C600/X79 series chipset USB2 Enha... | 16    | ehci_pci   | [0D39F4F066](<Server/ASUSTek Computer/Z9PE-D16/Z9PE-D16 Series/7948CC9F2801/UBUNTU-18.04/5.4.0-91-GENERIC/X86_64/0D39F4F066>) |
| 8086:3a34 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 16    | uhci_hcd   | [89D676AF03](<Server/Supermicro/X8/X8DTL/6E7DE9F9FEDC/DEBIAN-11/5.10.0-11-AMD64/X86_64/89D676AF03>) |
| 8086:3a35 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 16    | uhci_hcd   | [89D676AF03](<Server/Supermicro/X8/X8DTL/6E7DE9F9FEDC/DEBIAN-11/5.10.0-11-AMD64/X86_64/89D676AF03>) |
| 8086:3a36 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 16    | uhci_hcd   | [89D676AF03](<Server/Supermicro/X8/X8DTL/6E7DE9F9FEDC/DEBIAN-11/5.10.0-11-AMD64/X86_64/89D676AF03>) |
| 8086:3a37 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 16    | uhci_hcd   | [89D676AF03](<Server/Supermicro/X8/X8DTL/6E7DE9F9FEDC/DEBIAN-11/5.10.0-11-AMD64/X86_64/89D676AF03>) |
| 8086:3a38 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 16    | uhci_hcd   | [89D676AF03](<Server/Supermicro/X8/X8DTL/6E7DE9F9FEDC/DEBIAN-11/5.10.0-11-AMD64/X86_64/89D676AF03>) |
| 8086:3a39 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 16    | uhci_hcd   | [89D676AF03](<Server/Supermicro/X8/X8DTL/6E7DE9F9FEDC/DEBIAN-11/5.10.0-11-AMD64/X86_64/89D676AF03>) |
| 8086:3a3a | 15d9:0006 | Intel            | 82801JI (ICH10 Family) USB2 EHCI ... | 16    | ehci_hcd   | [89D676AF03](<Server/Supermicro/X8/X8DTL/6E7DE9F9FEDC/DEBIAN-11/5.10.0-11-AMD64/X86_64/89D676AF03>) |
| 8086:3a3c | 15d9:0006 | Intel            | 82801JI (ICH10 Family) USB2 EHCI ... | 16    | ehci_hcd   | [89D676AF03](<Server/Supermicro/X8/X8DTL/6E7DE9F9FEDC/DEBIAN-11/5.10.0-11-AMD64/X86_64/89D676AF03>) |
| 8086:2688 | 103c:31fe | Intel            | 631xESB/632xESB/3100 Chipset UHCI... | 14    | uhci_hcd   | [24D4B5B8DB](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/9A14972DB3E8/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/24D4B5B8DB>) |
| 8086:2689 | 103c:31fe | Intel            | 631xESB/632xESB/3100 Chipset UHCI... | 14    | uhci_hcd   | [24D4B5B8DB](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/9A14972DB3E8/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/24D4B5B8DB>) |
| 8086:268a | 103c:31fe | Intel            | 631xESB/632xESB/3100 Chipset UHCI... | 14    | uhci_hcd   | [24D4B5B8DB](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/9A14972DB3E8/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/24D4B5B8DB>) |
| 8086:268c | 103c:31fe | Intel            | 631xESB/632xESB/3100 Chipset EHCI... | 14    | ehci_pci   | [24D4B5B8DB](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/9A14972DB3E8/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/24D4B5B8DB>) |
| 8086:1d26 | 1028:048c | Intel            | C600/X79 series chipset USB2 Enha... | 13    | ehci_pci   | [7BF19C1CD2](<Server/Dell/PowerEdge/PowerEdge R720/2489ED365DE4/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/7BF19C1CD2>) |
| 8086:1d26 | 15d9:0636 | Intel            | C600/X79 series chipset USB2 Enha... | 13    | ehci_hcd   | [31684AD7E4](<Server/Supermicro/X9/X9DRW/55D2AD4AF0CF/UBUNTU-21.04/5.11.0-44-GENERIC/X86_64/31684AD7E4>) |
| 8086:1d2d | 1028:048c | Intel            | C600/X79 series chipset USB2 Enha... | 13    | ehci_pci   | [7BF19C1CD2](<Server/Dell/PowerEdge/PowerEdge R720/2489ED365DE4/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/7BF19C1CD2>) |
| 8086:1d2d | 15d9:0636 | Intel            | C600/X79 series chipset USB2 Enha... | 13    | ehci_hcd   | [31684AD7E4](<Server/Supermicro/X9/X9DRW/55D2AD4AF0CF/UBUNTU-21.04/5.11.0-44-GENERIC/X86_64/31684AD7E4>) |
| 8086:268b | 103c:31fe | Intel            | 631xESB/632xESB/3100 Chipset UHCI... | 13    | uhci_hcd   | [24D4B5B8DB](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/9A14972DB3E8/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/24D4B5B8DB>) |
| 8086:8d31 | 8086:7270 | Intel            | C610/X99 series chipset USB xHCI ... | 13    | xhci_hcd   | [50AEBE4B28](<Server/Supermicro/SSG-6048/SSG-6048R-E1CR24H/8A7A52EA4807/CENTOS-8/4.18.0-348.2.1.EL8_5.X86_64/X86_64/50AEBE4B28>) |
| 1b21:1042 | 1043:8488 | ASMedia Techn... | ASM1042 SuperSpeed USB Host Contr... | 12    | xhci_hcd   | [30831977D2](<Server/ASUSTek Computer/Z9PA-D8/Z9PA-D8 Series/86EE66EF8DD5/OPENSUSE-20211031/5.14.14-1-DEFAULT/X86_64/30831977D2>) |
| 8086:3b34 | 1028:02a4 | Intel            | 5 Series/3400 Series Chipset USB2... | 12    | ehci_pci   | [2CAE1B1D80](<Server/Dell/PowerEdge/PowerEdge T310/1B407A78D4C5/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/2CAE1B1D80>) |
| 8086:3b3c | 1028:02a4 | Intel            | 5 Series/3400 Series Chipset USB2... | 12    | ehci_pci   | [2CAE1B1D80](<Server/Dell/PowerEdge/PowerEdge T310/1B407A78D4C5/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/2CAE1B1D80>) |
| 8086:8d26 | 103c:8030 | Intel            | C610/X99 series chipset USB Enhan... | 12    | ehci_pci   | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 8086:8d26 | 8086:7270 | Intel            | C610/X99 series chipset USB Enhan... | 12    | ehci_pci   | [50AEBE4B28](<Server/Supermicro/SSG-6048/SSG-6048R-E1CR24H/8A7A52EA4807/CENTOS-8/4.18.0-348.2.1.EL8_5.X86_64/X86_64/50AEBE4B28>) |
| 8086:8d2d | 103c:8030 | Intel            | C610/X99 series chipset USB Enhan... | 12    | ehci_pci   | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a1ec | 8086:7270 | Intel            | C620 Series Chipset Family MROM 0    | 19    |            | [73518731A1](<Server/Supermicro/X11/X11DPi-N/6D6FD3049691/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/73518731A1>) |
| 8086:8d7c | 15d9:0821 | Intel            | C610/X99 series chipset SPSR         | 17    |            | [AAEEE85BE7](<Server/Supermicro/SYS-6028/SYS-6028R-WTRT/690B86B530B0/DEBIAN-11/4.19.0-17-AMD64/X86_64/AAEEE85BE7>) |
| 8086:a1ec | 8086:35ce | Intel            | C620 Series Chipset Family MROM 0    | 16    |            | [4391DFF8D2](<Server/Others/Others/Others/29E67FFE5E37/UBUNTU-18.04/4.18.0-20-GENERIC/X86_64/4391DFF8D2>) |
| 8086:a1ed | 8086:7270 | Intel            | C620 Series Chipset Family MROM 1    | 15    |            | [73518731A1](<Server/Supermicro/X11/X11DPi-N/6D6FD3049691/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/73518731A1>) |
| 8086:8d7c | 103c:8030 | Intel            | C610/X99 series chipset SPSR         | 12    |            | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 8086:8d7c | 8086:7270 | Intel            | C610/X99 series chipset SPSR         | 11    |            | [50AEBE4B28](<Server/Supermicro/SSG-6048/SSG-6048R-E1CR24H/8A7A52EA4807/CENTOS-8/4.18.0-348.2.1.EL8_5.X86_64/X86_64/50AEBE4B28>) |
| 8086:a1ec | 1028:073a | Intel            | C620 Series Chipset Family MROM 0    | 11    |            | [2E5507B849](<Server/Dell/Precision/Precision 7920 Tower/6DBFD1DBD45A/UBUNTU-20.04/5.10.0-1055-OEM/X86_64/2E5507B849>) |
| 8086:a1ed | 1028:073a | Intel            | C620 Series Chipset Family MROM 1    | 11    |            | [2E5507B849](<Server/Dell/Precision/Precision 7920 Tower/6DBFD1DBD45A/UBUNTU-20.04/5.10.0-1055-OEM/X86_64/2E5507B849>) |
| 8086:a1ec | 1043:871e | Intel            | C620 Series Chipset Family MROM 0    | 9     |            | [3035FDAD91](<Server/ASUSTek Computer/WS-C621E-SAGE/WS-C621E-SAGE Series/E86AFFE0F80D/KUBUNTU-20.04/5.4.0-97-GENERIC/X86_64/3035FDAD91>) |
| 8086:8d7c | 15d9:0857 | Intel            | C610/X99 series chipset SPSR         | 8     |            | [6A333A499D](<Server/Supermicro/X10/X10SRA/0DAF404C22AB/GENTOO-2.7/5.14.14-GENTOO-X86_64/X86_64/6A333A499D>) |
| 8086:8d7c | 8086:0000 | Intel            | C610/X99 series chipset SPSR         | 8     |            | [BA0F3C3B41](<Server/Huawei/RH1288/RH1288 V3/DCCC7932E1B0/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/BA0F3C3B41>) |
| 8086:a1ec | 15d9:096d | Intel            | C620 Series Chipset Family MROM 0    | 8     |            | [2CDAC4454D](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.16.8-051608-GENERIC/X86_64/2CDAC4454D>) |
| 8086:a1ed | 15d9:096d | Intel            | C620 Series Chipset Family MROM 1    | 8     |            | [2CDAC4454D](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.16.8-051608-GENERIC/X86_64/2CDAC4454D>) |
| 8086:8d7c | 1043:85f6 | Intel            | C610/X99 series chipset SPSR         | 7     |            | [4158CB76EF](<Server/ASUSTek Computer/RS400/RS400-E8-PS2-F/B939D9497146/GENTOO-2.7/5.10.14-HARDENED1/X86_64/4158CB76EF>) |
| 8086:8d7c | 15d9:0831 | Intel            | C610/X99 series chipset SPSR         | 7     |            | [58E86F0E34](<Server/Supermicro/Super/Super Server/BD4C9B6F043B/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/58E86F0E34>) |
| 8086:a1ec | 1590:00eb | Intel            | C620 Series Chipset Family MROM 0    | 7     |            | [7AB4F05613](<Server/HPE/ProLiant/ProLiant DL360 Gen10/4443D3087423/UBUNTU-18.04/4.15.0-135-GENERIC/X86_64/7AB4F05613>) |
| 8086:a1ec | 17aa:7808 | Intel            | C620 Series Chipset Family MROM 0    | 7     |            | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 8086:a1ed | 1590:00eb | Intel            | C620 Series Chipset Family MROM 1    | 7     |            | [7AB4F05613](<Server/HPE/ProLiant/ProLiant DL360 Gen10/4443D3087423/UBUNTU-18.04/4.15.0-135-GENERIC/X86_64/7AB4F05613>) |
| 8086:8d7c | 1028:0601 | Intel            | C610/X99 series chipset SPSR         | 6     |            | [F90168C69D](<Server/Dell/PowerEdge/PowerEdge R630/DBDF919E8981/RHEL-7/3.10.0-1127.19.1.EL7.YAHOO.20200821.63.X86_64/X86_64/F90168C69D>) |
| 8086:8d7c | 1028:0600 | Intel            | C610/X99 series chipset SPSR         | 5     |            | [11DDC3D97B](<Server/Dell/PowerEdge/PowerEdge R730/B08360FD5D56/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/11DDC3D97B>) |
| 8086:a1ec | 1028:0715 | Intel            | C620 Series Chipset Family MROM 0    | 5     |            | [FCC6D41C03](<Server/Dell/PowerEdge/PowerEdge R740/203EBCE27AC6/CENTOS-7/3.10.0-1160.45.1.EL7.X86_64/X86_64/FCC6D41C03>) |
| 8086:a1ec | 1028:0739 | Intel            | C620 Series Chipset Family MROM 0    | 5     |            | [5A2FCB7023](<Server/Dell/Precision/Precision 7820 Tower/8AAB146ACE98/LINUXMINT-20/5.4.0-91-GENERIC/X86_64/5A2FCB7023>) |
| 8086:a1ec | 15d9:0981 | Intel            | C620 Series Chipset Family MROM 0    | 5     |            | [1A73C74FBB](<Server/Supermicro/Super/Super Server/909986EADB14/UBUNTU-21.04/5.11.0-38-GENERIC/X86_64/1A73C74FBB>) |
| 8086:a1ec | 1849:a1ec | Intel            | C620 Series Chipset Family MROM 0    | 5     |            | [BAA2C57359](<Server/ASRockRack/EPC621/EPC621D8A/5678CB93815F/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/BAA2C57359>) |
| 8086:a1ed | 1028:0739 | Intel            | C620 Series Chipset Family MROM 1    | 5     |            | [5A2FCB7023](<Server/Dell/Precision/Precision 7820 Tower/8AAB146ACE98/LINUXMINT-20/5.4.0-91-GENERIC/X86_64/5A2FCB7023>) |
| 8086:a1ed | 15d9:0981 | Intel            | C620 Series Chipset Family MROM 1    | 5     |            | [1A73C74FBB](<Server/Supermicro/Super/Super Server/909986EADB14/UBUNTU-21.04/5.11.0-38-GENERIC/X86_64/1A73C74FBB>) |
| 8086:a1ed | 1849:a1ed | Intel            | C620 Series Chipset Family MROM 1    | 5     |            | [BAA2C57359](<Server/ASRockRack/EPC621/EPC621D8A/5678CB93815F/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/BAA2C57359>) |
| 1912:001b | 1d49:0a02 | Renesas Techn... | SH7758 PCIe End-Point [PBI]          | 4     |            | [78113D1370](<Server/Lenovo/Flex/Flex System x240 M5 Compute Node -[9532AC1]-/CC76B4AA67C4/DEBIAN-10/4.19.0-16-AMD64/X86_64/78113D1370>) |
| 8086:8d7c | 1028:0627 | Intel            | C610/X99 series chipset SPSR         | 4     |            | [C0AA1BF2F1](<Server/Dell/PowerEdge/PowerEdge R730xd/3856150DE2AC/FEDORA-32/5.6.6-300.FC32.X86_64/X86_64/C0AA1BF2F1>) |
| 8086:8d7c | 1d49:0a00 | Intel            | C610/X99 series chipset SPSR         | 4     |            | [78113D1370](<Server/Lenovo/Flex/Flex System x240 M5 Compute Node -[9532AC1]-/CC76B4AA67C4/DEBIAN-10/4.19.0-16-AMD64/X86_64/78113D1370>) |
| 8086:a1ec | 103c:81c7 | Intel            | C620 Series Chipset Family MROM 0    | 4     |            | [5299B4DA87](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/68BC2092E093/UBUNTU-18.04/5.4.0-74-GENERIC/X86_64/5299B4DA87>) |
| 8086:a1ec | 15d9:0953 | Intel            | C620 Series Chipset Family MROM 0    | 4     |            | [A76BB2E30D](<Server/Supermicro/SYS-5029/SYS-5029P-WTR/2D889DFAC2FF/ROCKY-8.5/4.18.0-348.12.2.EL8_5.X86_64/X86_64/A76BB2E30D>) |
| 8086:a1ec | 8086:0000 | Intel            | C620 Series Chipset Family MROM 0    | 4     |            | [36C4ACAC2D](<Server/Intel/S2600/S2600WFT/8DC9639F1DBF/ROCKY-8.4/4.18.0-305.10.2.EL8_4.X86_64/X86_64/36C4ACAC2D>) |
| 8086:a1ed | 103c:81c7 | Intel            | C620 Series Chipset Family MROM 1    | 4     |            | [5299B4DA87](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/68BC2092E093/UBUNTU-18.04/5.4.0-74-GENERIC/X86_64/5299B4DA87>) |
| 8086:a1ed | 15d9:0953 | Intel            | C620 Series Chipset Family MROM 1    | 4     |            | [A76BB2E30D](<Server/Supermicro/SYS-5029/SYS-5029P-WTR/2D889DFAC2FF/ROCKY-8.5/4.18.0-348.12.2.EL8_5.X86_64/X86_64/A76BB2E30D>) |
| 8086:a1ed | 8086:35ce | Intel            | C620 Series Chipset Family MROM 1    | 4     |            | [36C4ACAC2D](<Server/Intel/S2600/S2600WFT/8DC9639F1DBF/ROCKY-8.4/4.18.0-305.10.2.EL8_4.X86_64/X86_64/36C4ACAC2D>) |
| 8086:8d7c | 1028:0639 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [E5766C8331](<Server/Dell/PowerEdge/PowerEdge R430/71142245BA84/LUBUNTU-20.04/5.4.0-42-GENERIC/X86_64/E5766C8331>) |
| 8086:8d7c | 1458:1000 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [2F69A2F89C](<Server/Dedicated Computing/OEM-F7342/OEM-F7342-00/A56806D283ED/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/2F69A2F89C>) |
| 8086:8d7c | 15d9:0834 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [FA4BECDE8B](<Server/Supermicro/Super/Super Server/DCA5291A7516/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/FA4BECDE8B>) |
| 8086:a1ec | 1028:0716 | Intel            | C620 Series Chipset Family MROM 0    | 3     |            | [E752263E49](<Server/Dell/PowerEdge/PowerEdge R640/1917FF5F0757/CENTOS-7/3.10.0-957.21.3.EL7.X86_64/X86_64/E752263E49>) |
| 8086:a1ec | 1028:0718 | Intel            | C620 Series Chipset Family MROM 0    | 3     |            | [3021BDC8E0](<Server/Dell/Precision/Precision 7920 Rack/BEB8B2D33731/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3021BDC8E0>) |
| 8086:a1ec | 103c:81c6 | Intel            | C620 Series Chipset Family MROM 0    | 3     |            | [679871CFEC](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/E621F1A07D2C/UBUNTU-20.04/5.4.0-84-GENERIC/X86_64/679871CFEC>) |
| 8086:a1ec | 15d9:095d | Intel            | C620 Series Chipset Family MROM 0    | 3     |            | [C682299C13](<Server/Supermicro/X11/X11-SPM-TF/17F67170A1AB/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/C682299C13>) |
| 8086:a1ec | 17aa:1038 | Intel            | C620 Series Chipset Family MROM 0    | 3     |            | [5658A2FB98](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC003KUS/DD1C32AB7122/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/5658A2FB98>) |
| 8086:a1ed | 103c:81c6 | Intel            | C620 Series Chipset Family MROM 1    | 3     |            | [679871CFEC](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/E621F1A07D2C/UBUNTU-20.04/5.4.0-84-GENERIC/X86_64/679871CFEC>) |
| 8086:a1ed | 15d9:095d | Intel            | C620 Series Chipset Family MROM 1    | 3     |            | [C682299C13](<Server/Supermicro/X11/X11-SPM-TF/17F67170A1AB/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/C682299C13>) |
| 8086:a1ed | 17aa:1038 | Intel            | C620 Series Chipset Family MROM 1    | 3     |            | [5658A2FB98](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC003KUS/DD1C32AB7122/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/5658A2FB98>) |
| 8086:3a40 | 152d:8969 | Intel            | 82801JI (ICH10 Family) PCI Expres... | 2     |            | [23E536F087](<Server/Quanta/QSSC-98/QSSC-98J_C2/03AF1302C679/CENTOS-6.9/2.6.32-754.6.3.EL6.X86_64/X86_64/23E536F087>) |
| 8086:3a48 | 152d:8969 | Intel            | 82801JI (ICH10 Family) PCI Expres... | 2     |            | [23E536F087](<Server/Quanta/QSSC-98/QSSC-98J_C2/03AF1302C679/CENTOS-6.9/2.6.32-754.6.3.EL6.X86_64/X86_64/23E536F087>) |
| 8086:8d7c | 1028:063a | Intel            | C610/X99 series chipset SPSR         | 2     |            | [E4DEE6FAF7](<Server/Dell/PowerEdge/PowerEdge R530/2178C7DB8E3B/OPENSUSE-20210512/5.12.2-1-DEFAULT/X86_64/E4DEE6FAF7>) |

