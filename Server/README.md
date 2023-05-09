Most popular PCI devices in Servers
-----------------------------------

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Servers ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Canbus ](#canbus-pci)
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
   * [ Mips ](#mips-pci)
   * [ Multimedia controller ](#multimedia-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Network and computing encryption device ](#network-and-computing-encryption-device-pci)
   * [ Non-essential instrumentation ](#non-essential-instrumentation-pci)
   * [ Non-vga unclassified device ](#non-vga-unclassified-device-pci)
   * [ Parallel controller (ecp) ](#parallel-controller-ecp-pci)
   * [ Parallel controller (ieee1284) ](#parallel-controller-ieee1284-pci)
   * [ Performance counters ](#performance-counters-pci)
   * [ Pic (8259) ](#pic-8259-pci)
   * [ Pic (io(x)-apic) ](#pic-iox-apic-pci)
   * [ Pic (io-apic) ](#pic-io-apic-pci)
   * [ Processing accelerators ](#processing-accelerators-pci)
   * [ Processor ](#processor-pci)
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
   * [ Unclassified device ](#unclassified-device-pci)
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
| 1a03:1150 | 1a03:1150 | ASPEED Techno... | AST1150 PCI-to-PCI Bridge            | 269   | shpchp     | [55AF41B298](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.7/4.18.0-425.19.2.EL8_7.X86_64/X86_64/55AF41B298>) |
| 8086:2c70 | 8086:8086 | Intel            | Xeon 5600 Series QuickPath Archit... | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2d81 | 8086:8086 | Intel            | Xeon 5600 Series QuickPath Archit... | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2d90 | 8086:8086 | Intel            | Xeon 5600 Series QPI Link 0          | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2d91 | 8086:8086 | Intel            | Xeon 5600 Series QPI Physical 0      | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2d92 | 8086:8086 | Intel            | Xeon 5600 Series Mirror Port Link 0  | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2d93 | 8086:8086 | Intel            | Xeon 5600 Series Mirror Port Link 1  | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2d94 | 8086:8086 | Intel            | Xeon 5600 Series QPI Link 1          | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2d95 | 8086:8086 | Intel            | Xeon 5600 Series QPI Physical 1      | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2d98 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2d99 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2d9a | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2d9c | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2da0 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2da1 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2da2 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2da3 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2da8 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2da9 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2daa | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2dab | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2db0 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2db1 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2db2 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2db3 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 164   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:2030 | 8086:0000 | Intel            | Sky Lake-E PCI Express Root Port A   | 136   | pcieport   | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2032 | 8086:0000 | Intel            | Sky Lake-E PCI Express Root Port C   | 136   | pcieport   | [FE6DC0D9C7](<Server/Dell/Precision/Precision 7820 Tower/FB09ECB98D56/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FE6DC0D9C7>) |
| 8086:2020 | 8086:0000 | Intel            | Sky Lake-E DMI3 Registers            | 116   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2033 | 8086:0000 | Intel            | Sky Lake-E PCI Express Root Port D   | 85    | pcieport   | [A0623DC5A7](<Server/Dell/Precision/Precision 7820 Tower/70D486E7A18E/UBUNTU-22.10/5.19.0-40-GENERIC/X86_64/A0623DC5A7>) |
| 1912:0012 | 1912:0012 | Renesas Techn... | SH7757 PCIe-PCI Bridge [PPB]         | 73    | shpchp     | [6A0AF69B4A](<Server/Dell/PowerEdge/PowerEdge R720/F424DE07066D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6A0AF69B4A>) |
| 1912:0013 | 1912:0013 | Renesas Techn... | SH7757 PCIe Switch [PS]              | 73    | pcieport   | [6A0AF69B4A](<Server/Dell/PowerEdge/PowerEdge R720/F424DE07066D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6A0AF69B4A>) |
| 8086:1d10 | 103c:18a9 | Intel            | C600/X79 series chipset PCI Expre... | 69    | pcieport   | [961A066E6B](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/F726BB41B090/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/961A066E6B>) |
| 8086:1d1e | 103c:18a9 | Intel            | C600/X79 series chipset PCI Expre... | 69    | pcieport   | [961A066E6B](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/F726BB41B090/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/961A066E6B>) |
| 8086:1d3e | 103c:18a9 | Intel            | C600/X79 series chipset PCI Expre... | 69    | pcieport   | [961A066E6B](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/F726BB41B090/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/961A066E6B>) |
| 8086:1d41 |           | Intel            | C600/X79 series chipset LPC Contr... | 69    | lpc_ich    | [961A066E6B](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/F726BB41B090/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/961A066E6B>) |
| 8086:244e | 103c:18a9 | Intel            | 82801 PCI Bridge                     | 69    |            | [961A066E6B](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/F726BB41B090/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/961A066E6B>) |
| 1022:1482 |           | AMD              | Starship/Matisse PCIe Dummy Host ... | 67    |            | [55AF41B298](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.7/4.18.0-425.19.2.EL8_7.X86_64/X86_64/55AF41B298>) |
| 1556:be00 |           | PLDA             | PCI Express Bridge                   | 67    | shpchp     | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 1022:1484 | 1022:1484 | AMD              | Starship/Matisse Internal PCIe GP... | 66    | pcieport   | [55AF41B298](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.7/4.18.0-425.19.2.EL8_7.X86_64/X86_64/55AF41B298>) |
| 8086:341c |           | Intel            | 7500/5520/5500/X58 Unknown           | 66    |            | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |
| 8086:341d |           | Intel            | 7500/5520/5500/X58 Unknown           | 66    |            | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |
| 8086:341e |           | Intel            | 7500/5520/5500/X58 Unknown           | 66    |            | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |
| 8086:37c0 | 8086:0000 | Intel            | PCI bridge                           | 65    | pcieport   | [51DC310024](<Server/Kraftway/Trusted/Trusted TS2000/583173D8B5F2/RED-OS-7.3.2/6.1.11-1.EL7.3.X86_64/X86_64/51DC310024>) |
| 8086:244e |           | Intel            | 82801 PCI Bridge                     | 64    | shpchp     | [403A18BFFF](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G4/5D6174213849/ARCH-ROLLING/6.1.18-1-LTS/X86_64/403A18BFFF>) |
| 8086:3418 |           | Intel            | 7500/5520/5500/X58 Physical Layer... | 63    |            | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |
| 8086:3419 |           | Intel            | 7500/5520/5500 Physical Layer Port 1 | 63    |            | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |
| 8086:341a |           | Intel            | 7500/5520/5500/X58 Unknown           | 63    |            | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |
| 8086:3439 |           | Intel            | 7500/5520/5500/X58 Unknown           | 63    |            | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |
| 8086:343a |           | Intel            | 7500/5520/5500/X58 Unknown           | 63    |            | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |
| 8086:343b |           | Intel            | 7500/5520/5500/X58 Unknown           | 63    |            | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |

### Canbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1a07:0011 | 1a07:0011 | Kvaser AB        | Mini PCIe 2xHS v2                    | 1     | kvaser_... | [196C8EB317](<Server/Neousys Technology/Nuvo-7100VTC/Nuvo-7100VTC Series/E44E3E216941/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/196C8EB317>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:5229 | 10ec:5229 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [0600880DBA](<Server/ECS/LIVA/LIVA Q2/51AFACC4D80B/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/0600880DBA>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:19e2 | 8086:0000 | Intel            | Atom Processor C3000 Series Quick... | 5     | qat_c3xxx  | [CDCA826585](<Server/Supermicro/Super/Super Server/67F50154C8D4/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/CDCA826585>) |
| 8086:2710 | 8086:0000 | Intel            | HQM/DLB                              | 4     |            | [3DDB00DA94](<Server/Intel/ArcherCity/ArcherCity/35F42C801DE0/FEDORA-37/6.1.7-200.FC37.X86_64/X86_64/3DDB00DA94>) |
| 8086:4940 | 8086:0000 | Intel            | Xeon Co-processor                    | 4     | qat_4xxx   | [3DDB00DA94](<Server/Intel/ArcherCity/ArcherCity/35F42C801DE0/FEDORA-37/6.1.7-200.FC37.X86_64/X86_64/3DDB00DA94>) |
| 8086:37c8 | 8086:0000 | Intel            | C62x Chipset QuickAssist Technology  | 3     | qat_c62x   | [FFA58F1702](<Server/Supermicro/SYS-E300/SYS-E300-9D-8CN8TP/202BFE094BD2/DEBIAN-11/5.10.0-21-AMD64/X86_64/FFA58F1702>) |
| 1000:0a01 | 1000:0a01 | Broadcom / LSI   | Co-processor                         | 1     |            | [DDFEFE06A3](<Server/Sun Microsystems/Sun/Sun Fire X4170 M2 SERVER/82C4B5F145E4/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/DDFEFE06A3>) |
| 19a2:0800 | 1734:11cc | Emulex           | ServerView iRMC HTI                  | 1     |            | [EFE128BA47](<Server/Fujitsu/PRIMERGY/PRIMERGY RX300 S8/6E07B32FDA2C/UBUNTU-20.04/5.15.0-48-GENERIC/X86_64/EFE128BA47>) |
| 8086:0434 | 8086:0000 | Intel            | DH89XXCC Series QAT                  | 1     |            | [14C76E0C83](<Server/F5 Networks/C/C117/C1512B26FE54/ALPINE-3.13.2/5.10.16-0-LTS/X86_64/14C76E0C83>) |
| 8086:0435 | 8086:0000 | Intel            | DH895XCC Series QAT                  | 1     | qat_dh8... | [EB5771B190](<Server/HUAWEI/Taishan/Taishan 2180/98FD400CE456/DEBIAN-10/4.1.44-06.151.VHULK1711.1.1.AARCH64/AARCH64/EB5771B190>) |
| 8086:18ee | 8086:0000 | Intel            | 200xx Series QAT                     | 1     |            | [3751D50DDE](<Server/Supermicro/Super/Super Server/ACFD57B232A4/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/3751D50DDE>) |
| 8086:1f18 | 15d9:0820 | Intel            | Atom processor C2000 QAT             | 1     |            | [B9AC0D657E](<Server/Supermicro/A1/A1SRM-2558F/DAF42406F667/FEDORA-32/5.8.16-200.FC32.X86_64/X86_64/B9AC0D657E>) |
| 8086:225c | 8086:2500 | Intel            | Xeon Phi coprocessor SE10/7120 se... | 1     | mic_host   | [9D9DA282F6](<Server/Dedicated Computing/OEM-F7342/OEM-F7342-00/A56806D283ED/UBUNTU-20.04/5.4.0-45-GENERIC/X86_64/9D9DA282F6>) |
| 8086:4941 | 8086:0000 | Intel            | Co-processor                         | 1     | vfio_pci   | [3DDB00DA94](<Server/Intel/ArcherCity/ArcherCity/35F42C801DE0/FEDORA-37/6.1.7-200.FC37.X86_64/X86_64/3DDB00DA94>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a1ba | 8086:7270 | Intel            | C620 Series Chipset Family MEI Co... | 48    | mei_me     | [18B2BF9FF4](<Server/Delta Computers/DSS-C621/DSS-C621LTG/EA1701537BF7/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/18B2BF9FF4>) |
| 8086:a1be | 8086:7270 | Intel            | C620 Series Chipset Family MEI Co... | 48    |            | [18B2BF9FF4](<Server/Delta Computers/DSS-C621/DSS-C621LTG/EA1701537BF7/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/18B2BF9FF4>) |
| 8086:a1bb | 8086:7270 | Intel            | C620 Series Chipset Family MEI Co... | 47    |            | [18B2BF9FF4](<Server/Delta Computers/DSS-C621/DSS-C621LTG/EA1701537BF7/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/18B2BF9FF4>) |
| 8086:a1ba | 8086:35ce | Intel            | C620 Series Chipset Family MEI Co... | 22    | mei_me     | [F5848D1BA2](<Server/DALCO/S2600/S2600WFT/37B0D5359698/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/F5848D1BA2>) |
| 8086:a1be | 8086:35ce | Intel            | C620 Series Chipset Family MEI Co... | 22    |            | [F5848D1BA2](<Server/DALCO/S2600/S2600WFT/37B0D5359698/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/F5848D1BA2>) |
| 8086:1d3a | 1043:84ef | Intel            | C600/X79 series chipset MEI Contr... | 20    | mei_me     | [4AC44C74A3](<Server/ASUSTek Computer/Z9PA-D8/Z9PA-D8 Series/0BE952D59456/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/4AC44C74A3>) |
| 8086:1d3b | 1043:84ef | Intel            | C600/X79 series chipset MEI Contr... | 20    |            | [4AC44C74A3](<Server/ASUSTek Computer/Z9PA-D8/Z9PA-D8 Series/0BE952D59456/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/4AC44C74A3>) |
| 8086:a1ba | 1028:073a | Intel            | C620 Series Chipset Family MEI Co... | 20    | mei_me     | [962B265260](<Server/Dell/Precision/Precision 7920 Tower/8C7F63FF0FE0/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/962B265260>) |
| 8086:a1bb | 8086:35ce | Intel            | C620 Series Chipset Family MEI Co... | 20    |            | [F5848D1BA2](<Server/DALCO/S2600/S2600WFT/37B0D5359698/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/F5848D1BA2>) |
| 8086:1d3a | 1028:048c | Intel            | C600/X79 series chipset MEI Contr... | 17    | mei_me     | [6A0AF69B4A](<Server/Dell/PowerEdge/PowerEdge R720/F424DE07066D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6A0AF69B4A>) |
| 8086:1d3b | 1028:048c | Intel            | C600/X79 series chipset MEI Contr... | 17    |            | [6A0AF69B4A](<Server/Dell/PowerEdge/PowerEdge R720/F424DE07066D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6A0AF69B4A>) |
| 8086:8d3a | 15d9:0821 | Intel            | C610/X99 series chipset MEI Contr... | 16    | mei_me     | [17BF7A3CBC](<Server/Supermicro/SYS-6018/SYS-6018R-WTR/5EE2BAE645DD/CENTOS-7/3.10.0-862.14.4.EL7.X86_64/X86_64/17BF7A3CBC>) |
| 8086:8d3a | 8086:7270 | Intel            | C610/X99 series chipset MEI Contr... | 16    | mei_me     | [BAF3069CD7](<Server/Cisco Systems/UCSC-C220/UCSC-C220-M4S/9D3781D2096F/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/BAF3069CD7>) |
| 8086:8d3b | 15d9:0821 | Intel            | C610/X99 series chipset MEI Contr... | 16    |            | [17BF7A3CBC](<Server/Supermicro/SYS-6018/SYS-6018R-WTR/5EE2BAE645DD/CENTOS-7/3.10.0-862.14.4.EL7.X86_64/X86_64/17BF7A3CBC>) |
| 8086:8d3b | 8086:7270 | Intel            | C610/X99 series chipset MEI Contr... | 16    |            | [BAF3069CD7](<Server/Cisco Systems/UCSC-C220/UCSC-C220-M4S/9D3781D2096F/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/BAF3069CD7>) |
| 8086:a13a | 8086:1999 | Intel            | 100 Series/C230 Series Chipset Fa... | 16    | mei_me     | [97D3C70FB5](<Server/Quanta/QuantaMicro/QuantaMicro X10E-9N/01ACEA39AAB2/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/97D3C70FB5>) |
| 8086:1d3a | 15d9:0636 | Intel            | C600/X79 series chipset MEI Contr... | 15    | mei_me     | [6994C89077](<Server/Supermicro/X9/X9DRW/6A1A83EBE660/DEBIAN-11/5.15.104-1-PVE/X86_64/6994C89077>) |
| 8086:1d3b | 15d9:0636 | Intel            | C600/X79 series chipset MEI Contr... | 15    |            | [6994C89077](<Server/Supermicro/X9/X9DRW/6A1A83EBE660/DEBIAN-11/5.15.104-1-PVE/X86_64/6994C89077>) |
| 8086:1d3a | 1028:04fa | Intel            | C600/X79 series chipset MEI Contr... | 14    | mei_me     | [8EE7146669](<Server/Dell/PowerEdge/PowerEdge T320/6878B1DE0919/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/8EE7146669>) |
| 8086:1d3b | 1028:04fa | Intel            | C600/X79 series chipset MEI Contr... | 14    |            | [8EE7146669](<Server/Dell/PowerEdge/PowerEdge T320/6878B1DE0919/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/8EE7146669>) |
| 8086:a13b | 8086:1999 | Intel            | 100 Series/C230 Series Chipset Fa... | 12    | mei_me     | [97D3C70FB5](<Server/Quanta/QuantaMicro/QuantaMicro X10E-9N/01ACEA39AAB2/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/97D3C70FB5>) |
| 8086:a1ba | 1028:0715 | Intel            | C620 Series Chipset Family MEI Co... | 12    | mei_me     | [7AD0D2D67B](<Server/Dell/PowerEdge/PowerEdge R740/FF8CDFB5CB55/UBUNTU-18.04/4.15.0-193-GENERIC/X86_64/7AD0D2D67B>) |
| 8086:a1ba | 1028:0739 | Intel            | C620 Series Chipset Family MEI Co... | 12    | mei_me     | [FE6DC0D9C7](<Server/Dell/Precision/Precision 7820 Tower/FB09ECB98D56/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FE6DC0D9C7>) |
| 8086:a1bb | 1028:0715 | Intel            | C620 Series Chipset Family MEI Co... | 12    |            | [7AD0D2D67B](<Server/Dell/PowerEdge/PowerEdge R740/FF8CDFB5CB55/UBUNTU-18.04/4.15.0-193-GENERIC/X86_64/7AD0D2D67B>) |
| 8086:a1be | 1028:0715 | Intel            | C620 Series Chipset Family MEI Co... | 12    |            | [7AD0D2D67B](<Server/Dell/PowerEdge/PowerEdge R740/FF8CDFB5CB55/UBUNTU-18.04/4.15.0-193-GENERIC/X86_64/7AD0D2D67B>) |
| 8086:8d3a | 15d9:0831 | Intel            | C610/X99 series chipset MEI Contr... | 11    | mei_me     | [5E92E7FE1E](<Server/Supermicro/Super/Super Server/FD3A63BBABAD/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/5E92E7FE1E>) |
| 8086:8d3b | 15d9:0831 | Intel            | C610/X99 series chipset MEI Contr... | 11    |            | [5E92E7FE1E](<Server/Supermicro/Super/Super Server/FD3A63BBABAD/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/5E92E7FE1E>) |
| 8086:a1ba | 1590:00eb | Intel            | C620 Series Chipset Family MEI Co... | 11    | mei_me     | [C03DEE89F6](<Server/HPE/ProLiant/ProLiant DL380 Gen10/EE85DEEC4F6D/UBUNTU-20.04/5.15.0-60-GENERIC/X86_64/C03DEE89F6>) |
| 8086:a1be | 1590:00eb | Intel            | C620 Series Chipset Family MEI Co... | 11    |            | [C03DEE89F6](<Server/HPE/ProLiant/ProLiant DL380 Gen10/EE85DEEC4F6D/UBUNTU-20.04/5.15.0-60-GENERIC/X86_64/C03DEE89F6>) |
| 8086:a360 | 8086:7270 | Intel            | Cannon Lake PCH HECI Controller      | 11    | mei_me     | [A2FD0BC88C](<Server/Lenovo/ThinkSystem/ThinkSystem SR250 -[7Y51CTO1WW]-/56D35BA12534/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/A2FD0BC88C>) |
| 8086:1d3a | 15d9:0626 | Intel            | C600/X79 series chipset MEI Contr... | 10    | mei_me     | [C4B4851A88](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/5E5B10F103C2/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/C4B4851A88>) |
| 8086:8d3a | 1028:0601 | Intel            | C610/X99 series chipset MEI Contr... | 10    | mei_me     | [1ABE023ED7](<Server/Dell/PowerEdge/PowerEdge R630/0354475C3BDD/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/1ABE023ED7>) |
| 8086:8d3b | 1028:0601 | Intel            | C610/X99 series chipset MEI Contr... | 10    |            | [1ABE023ED7](<Server/Dell/PowerEdge/PowerEdge R630/0354475C3BDD/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/1ABE023ED7>) |
| 8086:a13a | 15d9:089a | Intel            | 100 Series/C230 Series Chipset Fa... | 10    | mei_me     | [7AA0EB0936](<Server/Supermicro/Super/Super Server/7660AB944FAA/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/7AA0EB0936>) |
| 8086:a1ba | 1043:871e | Intel            | C620 Series Chipset Family MEI Co... | 10    | mei_me     | [C874A6D28C](<Server/ASUSTek Computer/ESC8000/ESC8000 G4/05733798C837/UBUNTU-18.04/5.4.0-121-GENERIC/X86_64/C874A6D28C>) |
| 8086:a1be | 1043:871e | Intel            | C620 Series Chipset Family MEI Co... | 10    |            | [C874A6D28C](<Server/ASUSTek Computer/ESC8000/ESC8000 G4/05733798C837/UBUNTU-18.04/5.4.0-121-GENERIC/X86_64/C874A6D28C>) |
| 8086:1d3a | 1028:04ce | Intel            | C600/X79 series chipset MEI Contr... | 9     | mei_me     | [3A287683DC](<Server/Dell/PowerEdge/PowerEdge R620/072234E6D563/DEBIAN-10/5.4.106-1-PVE/X86_64/3A287683DC>) |
| 8086:1d3b | 1028:04ce | Intel            | C600/X79 series chipset MEI Contr... | 9     |            | [3A287683DC](<Server/Dell/PowerEdge/PowerEdge R620/072234E6D563/DEBIAN-10/5.4.106-1-PVE/X86_64/3A287683DC>) |
| 8086:1d3b | 15d9:0626 | Intel            | C600/X79 series chipset MEI Contr... | 9     |            | [C4B4851A88](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/5E5B10F103C2/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/C4B4851A88>) |
| 8086:8c3a | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 9     | mei_me     | [210B2E16E3](<Server/Supermicro/Super/Super Server/9DEEB33699DA/GENTOO-2.13/5.15.75-GENTOO-DIST/X86_64/210B2E16E3>) |
| 8086:8c3b | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 9     |            | [210B2E16E3](<Server/Supermicro/Super/Super Server/9DEEB33699DA/GENTOO-2.13/5.15.75-GENTOO-DIST/X86_64/210B2E16E3>) |
| 8086:8d3a | 1028:0600 | Intel            | C610/X99 series chipset MEI Contr... | 9     | mei_me     | [BE75097D0F](<Server/Dell/PowerEdge/PowerEdge R730/E686E52F7B47/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/BE75097D0F>) |
| 8086:8d3b | 1028:0600 | Intel            | C610/X99 series chipset MEI Contr... | 9     |            | [BE75097D0F](<Server/Dell/PowerEdge/PowerEdge R730/E686E52F7B47/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/BE75097D0F>) |
| 8086:a1bb | 1043:871e | Intel            | C620 Series Chipset Family MEI Co... | 9     |            | [C874A6D28C](<Server/ASUSTek Computer/ESC8000/ESC8000 G4/05733798C837/UBUNTU-18.04/5.4.0-121-GENERIC/X86_64/C874A6D28C>) |
| 8086:1d3a | 1028:04f8 | Intel            | C600/X79 series chipset MEI Contr... | 8     | mei_me     | [87EE1B58E4](<Server/Dell/PowerEdge/PowerEdge R420/BACBDE063781/DEBIAN-11/5.10.0-19-AMD64/X86_64/87EE1B58E4>) |
| 8086:1d3b | 1028:04f8 | Intel            | C600/X79 series chipset MEI Contr... | 8     |            | [87EE1B58E4](<Server/Dell/PowerEdge/PowerEdge R420/BACBDE063781/DEBIAN-11/5.10.0-19-AMD64/X86_64/87EE1B58E4>) |
| 8086:8d3a | 1043:85f6 | Intel            | C610/X99 series chipset MEI Contr... | 8     | mei_me     | [74269B72B0](<Server/ASUSTek Computer/Z10PE-D16/Z10PE-D16 WS/9FCE74D7C651/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/74269B72B0>) |
| 8086:8d3b | 1043:85f6 | Intel            | C610/X99 series chipset MEI Contr... | 8     |            | [74269B72B0](<Server/ASUSTek Computer/Z10PE-D16/Z10PE-D16 WS/9FCE74D7C651/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/74269B72B0>) |
| 8086:a1ba | 15d9:096d | Intel            | C620 Series Chipset Family MEI Co... | 8     | mei_me     | [DCBB3D117A](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.4.0-105-GENERIC/X86_64/DCBB3D117A>) |
| 8086:a1bb | 15d9:096d | Intel            | C620 Series Chipset Family MEI Co... | 8     |            | [DCBB3D117A](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.4.0-105-GENERIC/X86_64/DCBB3D117A>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1498 | 1022:1498 | AMD              | Starship/Matisse PTDMA               | 56    | ptdma      | [55AF41B298](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.7/4.18.0-425.19.2.EL8_7.X86_64/X86_64/55AF41B298>) |
| 1022:1486 | 1022:1486 | AMD              | Starship/Matisse Cryptographic Co... | 41    | ccp        | [55AF41B298](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.7/4.18.0-425.19.2.EL8_7.X86_64/X86_64/55AF41B298>) |
| 1022:1578 | 1022:1578 | AMD              | Carrizo Platform Security Processor  | 10    |            | [01D2615C22](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/00C05E8C85AC/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/01D2615C22>) |
| 1022:1486 | 1028:08fc | AMD              | Starship/Matisse Cryptographic Co... | 8     | ccp        | [237A3CD682](<Server/Dell/PowerEdge/PowerEdge R6515/647C815644AA/DEBIAN-12/6.1.0-5-AMD64/X86_64/237A3CD682>) |
| 1022:1486 | 1458:1000 | AMD              | Starship/Matisse Cryptographic Co... | 8     | ccp        | [DEF4067C8E](<Server/Gigabyte Technology/G242/G242-Z11-00/B5251D581093/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/DEF4067C8E>) |
| 1022:1498 | 1028:08fc | AMD              | Starship/Matisse PTDMA               | 8     | ptdma      | [237A3CD682](<Server/Dell/PowerEdge/PowerEdge R6515/647C815644AA/DEBIAN-12/6.1.0-5-AMD64/X86_64/237A3CD682>) |
| 1022:1456 | 1022:1456 | AMD              | Family 17h (Models 00h-0fh) Platf... | 7     | ccp        | [89E91928BB](<Server/Supermicro/Super/Super Server/ECB64B8152DF/DEBIAN-11/6.2.6-1-PVE/X86_64/89E91928BB>) |
| 1022:1468 | 1022:1468 | AMD              | Zeppelin Cryptographic Coprocesso... | 7     | ccp        | [89E91928BB](<Server/Supermicro/Super/Super Server/ECB64B8152DF/DEBIAN-11/6.2.6-1-PVE/X86_64/89E91928BB>) |
| 1022:1498 | 1458:1000 | AMD              | Starship/Matisse PTDMA               | 7     | ptdma      | [DEF4067C8E](<Server/Gigabyte Technology/G242/G242-Z11-00/B5251D581093/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/DEF4067C8E>) |
| 1022:1486 | 1028:08ff | AMD              | Starship/Matisse Cryptographic Co... | 6     | ccp        | [77F946C99B](<Server/Dell/PowerEdge/PowerEdge R7525/ED52A1D54F9D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/77F946C99B>) |
| 1022:1498 | 1028:08ff | AMD              | Starship/Matisse PTDMA               | 6     | ptdma      | [77F946C99B](<Server/Dell/PowerEdge/PowerEdge R7525/ED52A1D54F9D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/77F946C99B>) |
| 1022:15df | 1022:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 6     | ccp        | [D6E47A7C18](<Server/BESSTAR Tech/X/X500/81B31475FFFF/XEROLINUX-KDE-ROLLING/5.17.9-ARCH1-1/X86_64/D6E47A7C18>) |
| 1022:1486 | 1028:08fd | AMD              | Starship/Matisse Cryptographic Co... | 3     | ccp        | [F0B9CD86EF](<Server/Dell/PowerEdge/PowerEdge R7515/723F15A8AB49/UBUNTU-22.04/5.15.0-47-GENERIC/X86_64/F0B9CD86EF>) |
| 1022:1498 | 1028:08fd | AMD              | Starship/Matisse PTDMA               | 3     | ptdma      | [F0B9CD86EF](<Server/Dell/PowerEdge/PowerEdge R7515/723F15A8AB49/UBUNTU-22.04/5.15.0-47-GENERIC/X86_64/F0B9CD86EF>) |
| 1022:1456 | 1458:1000 | AMD              | Family 17h (Models 00h-0fh) Platf... | 2     | ccp        | [6D486A7EE9](<Server/Gigabyte Technology/MZ31/MZ31-AR0-00/20445DA51E24/UBUNTU-20.04/5.6.0-1048-OEM/X86_64/6D486A7EE9>) |
| 1022:1468 | 1458:1000 | AMD              | Zeppelin Cryptographic Coprocesso... | 2     | ccp        | [6D486A7EE9](<Server/Gigabyte Technology/MZ31/MZ31-AR0-00/20445DA51E24/UBUNTU-20.04/5.6.0-1048-OEM/X86_64/6D486A7EE9>) |
| 1022:1456 | 1028:07f9 | AMD              | Family 17h (Models 00h-0fh) Platf... | 1     | ccp        | [8F7FF50C55](<Server/Dell/PowerEdge/PowerEdge R7425/EEF1E1F22650/OPENSUSE-LEAP-15.1/4.12.14-LP151.28.13-DEFAULT/X86_64/8F7FF50C55>) |
| 1022:1468 | 1028:07f9 | AMD              | Zeppelin Cryptographic Coprocesso... | 1     | ccp        | [8F7FF50C55](<Server/Dell/PowerEdge/PowerEdge R7425/EEF1E1F22650/OPENSUSE-LEAP-15.1/4.12.14-LP151.28.13-DEFAULT/X86_64/8F7FF50C55>) |
| 1022:1486 | 1028:0900 | AMD              | Starship/Matisse Cryptographic Co... | 1     | ccp        | [382F999542](<Server/Dell/PowerEdge/PowerEdge C6525/B11FEC7694D8/ARCH/5.15.59-1-LTS/X86_64/382F999542>) |
| 1022:1498 | 1028:0900 | AMD              | Starship/Matisse PTDMA               | 1     | ptdma      | [382F999542](<Server/Dell/PowerEdge/PowerEdge C6525/B11FEC7694D8/ARCH/5.15.59-1-LTS/X86_64/382F999542>) |
| 1022:1498 | 1849:1498 | AMD              | Starship/Matisse PTDMA               | 1     |            | [3C11A0856C](<Server/ASRockRack/ROMED8/ROMED8-2T/9F9114A5632E/DEBIAN-10/5.8.0-0.BPO.2-AMD64/X86_64/3C11A0856C>) |
| 1022:14ca | 1022:14ca | AMD              | Family 19h PSP Device                | 1     |            | [B7E67F8130](<Server/AMD/Volcano/Volcano/59C634EF9C63/DEBIAN-11/5.10.0-21-AMD64/X86_64/B7E67F8130>) |
| 1022:1649 | 1458:1000 | AMD              | VanGogh PSP/CCP                      | 1     | ccp        | [7BA797B6A5](<Server/Giga Computing/MC13/MC13-LE0-000/1D7046547004/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/7BA797B6A5>) |

### Firewire controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 104c:8023 | 15d9:0100 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 6     | firewir... | [71610CE997](<Server/Supermicro/X8/X8DAH/6A1E9F33BACC/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/71610CE997>) |
| 104c:8023 | 15d9:0805 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 6     | firewir... | [4B0CFEC9A7](<Server/Supermicro/X10/X10SAE/FF0B31A8C494/NOBARA-37/6.2.10-200.FSYNC.FC37.X86_64/X86_64/4B0CFEC9A7>) |
| 1102:4001 | 1102:0010 | Creative Labs    | SB Audigy FireWire Port              | 6     | firewir... | [A41CABB3D6](<Server/Dell/PowerEdge/PowerEdge SC1430/2088C31572DB/DEBIAN-11/5.10.0-19-AMD64/X86_64/A41CABB3D6>) |
| 1106:3403 | 1043:8384 | VIA Technologies | VT6315 Series Firewire Controller    | 5     | firewir... | [C3665EBF57](<Server/ASUSTek Computer/Z9PE-D8/Z9PE-D8 WS/5BADF976211F/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/C3665EBF57>) |
| 1106:3403 | 1106:3403 | VIA Technologies | VT6315 Series Firewire Controller    | 5     | firewir... | [EEF379BEE2](<Server/Supermicro/X9/X9SRL-F/CC3074F1C867/ROSA-12.3/5.15.79-GENERIC-1ROSA2021.1-X86_64/X86_64/EEF379BEE2>) |
| 104c:8023 | 8086:34e2 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 4     | firewir... | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 1106:3044 | 1462:6520 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 4     | firewir... | [1888FA6DF7](<Server/MSI/MCP/MCP55/E26C4EDDD3C1/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/1888FA6DF7>) |
| 104c:823f | 8086:3594 | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 3     | firewir... | [96CDA648C2](<Server/Intel/W2600/W2600CR/577694DF59DA/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/96CDA648C2>) |
| 1106:3044 | 1106:3044 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 2     | firewir... | [AF4D333445](<Server/TYAN Computer/S/S7010/10698B3E1433/LINUXMINT-20.3/5.4.0-121-GENERIC/X86_64/AF4D333445>) |
| 1033:00f2 | 1033:00f2 | NEC Computers    | uPD72874 [Firewarden] IEEE1394a O... | 1     | firewir... | [9384FEF88D](<Server/Supermicro/Super/Super Server/0D2971EB9E61/GENTOO-2.13/6.1.12-GENTOO.AF/X86_64/9384FEF88D>) |
| 104c:8023 | 108e:6676 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | firewir... | [7CC89D3CBA](<Server/Sun Microsystems/Sun/Sun Ultra 40 M2 Workstation/3EE30E1E3EAB/MX-21/5.16.0-18.1-LIQUORIX-AMD64/X86_64/7CC89D3CBA>) |
| 104c:8023 | 10f1:2895 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | firewir... | [768571B831](<Server/TYAN Computer/S/S2895/4B5DFCDB09B6/LINUXMINT-20/5.4.0-58-GENERIC/X86_64/768571B831>) |
| 104c:8023 | 10f1:2915 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | firewir... | [0D3D065311](<Server/TYAN Computer/MCP/MCP55/DB4D10F83692/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/0D3D065311>) |
| 104c:8023 | 15d9:0653 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | firewir... | [171EE8DB12](<Server/Supermicro/C7/C7Z87/4BD99E9BA2B9/XUBUNTU-19.10/5.3.0-18-LOWLATENCY/X86_64/171EE8DB12>) |
| 104c:8023 | 15d9:1411 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | firewir... | [039BF2C96A](<Server/Supermicro/X8/X8DA3/578F928B17F4/LUBUNTU-20.04/5.4.0-42-GENERIC/X86_64/039BF2C96A>) |
| 104c:8024 | 104c:8010 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 1     | firewir... | [18B25AC51A](<Server/TYAN Computer/S/S4882/84BBA0EA52AC/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/18B25AC51A>) |
| 104c:8024 | 1458:132c | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 1     | firewir... | [0AC54E7FB4](<Server/Gigabyte Technology/GA-6/GA-6PXSV1/54F5641A961B/KAISEN-1.6/5.10.0-KAISEN3-AMD64/X86_64/0AC54E7FB4>) |
| 104c:823f | 3412:7856 | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 1     | firewir... | [21E2FBBB75](<Server/Supermicro/Super/Super Server/A70DB16AB074/UBUNTU-18.04/4.15.0-29-GENERIC/X86_64/21E2FBBB75>) |
| 1106:3044 | 108e:534d | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 1     | firewir... | [1F35F79302](<Server/Sun Microsystems/Ultra20/Ultra20 M2/23D902832E84/ROSA-2014.1/4.1.15-NRJ-DESKTOP-1ROSA-I586/I686/1F35F79302>) |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1002:5a23 | 1002:5a23 | AMD              | RD890S/RD990 I/O Memory Managemen... | 11    |            | [C425CE191D](<Server/Rackable Systems/KAURI/KAURI/35311A1382DF/LINUXMINT-20/5.4.0-113-GENERIC/X86_64/C425CE191D>) |
| 1022:1451 | 1022:1451 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 4     |            | [89E91928BB](<Server/Supermicro/Super/Super Server/ECB64B8152DF/DEBIAN-11/6.2.6-1-PVE/X86_64/89E91928BB>) |
| 8086:0b23 | 8086:0000 | Intel            | Xeon Root Event Collector            | 4     | pcieport   | [3DDB00DA94](<Server/Intel/ArcherCity/ArcherCity/35F42C801DE0/FEDORA-37/6.1.7-200.FC37.X86_64/X86_64/3DDB00DA94>) |
| 8086:0b23 | 8086:7270 | Intel            | Xeon Root Event Collector            | 4     | pcieport   | [3DDB00DA94](<Server/Intel/ArcherCity/ArcherCity/35F42C801DE0/FEDORA-37/6.1.7-200.FC37.X86_64/X86_64/3DDB00DA94>) |
| 8086:19a2 | 15d9:0969 | Intel            | Atom Processor C3000 Series Root ... | 4     | pcieport   | [CDCA826585](<Server/Supermicro/Super/Super Server/67F50154C8D4/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/CDCA826585>) |
| 1022:1577 | 1022:1577 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 3     |            | [01D2615C22](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/00C05E8C85AC/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/01D2615C22>) |
| 1022:14a6 | 1022:14a6 | AMD              | Generic system peripheral            | 1     | pcieport   | [B7E67F8130](<Server/AMD/Volcano/Volcano/59C634EF9C63/DEBIAN-11/5.10.0-21-AMD64/X86_64/B7E67F8130>) |
| 8086:19a2 | 15d9:1b10 | Intel            | Atom Processor C3000 Series Root ... | 1     |            | [F96B0CFDA0](<Server/Supermicro/Super/Super Server/9AA985C08DF3/GENTOO-2.7/5.10.76-GENTOO-R1/X86_64/F96B0CFDA0>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1a03:2000 | 1a03:2000 | ASPEED Techno... | ASPEED Graphics Family               | 107   | ast        | [A3F043A03C](<Server/Supermicro/M12/M12SWA-TF/4F883AA311F8/UBUNTU-22.04/5.15.0-33-GENERIC/X86_64/A3F043A03C>) |
| 102b:0533 | 103c:3381 | Matrox Electr... | MGA G200EH                           | 91    | mgag200    | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 1002:515e | 103c:31fb | AMD              | ES1000                               | 65    | radeon     | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |
| 102b:0522 | 8086:0103 | Matrox Electr... | MGA G200e [Pilot] ServerEngines (... | 38    | mgag200    | [9BB50174EF](<Server/DALCO/S2600/S2600WTTR/F200B7AE62EB/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/9BB50174EF>) |
| 102b:0536 |           | Matrox Electr... | Integrated Matrox G200eW3 Graphic... | 27    | mgag200    | [237A3CD682](<Server/Dell/PowerEdge/PowerEdge R6515/647C815644AA/DEBIAN-12/6.1.0-5-AMD64/X86_64/237A3CD682>) |
| 102b:0522 | 19a2:0101 | Matrox Electr... | MGA G200e [Pilot] ServerEngines (... | 25    | mgag200    | [A2FD0BC88C](<Server/Lenovo/ThinkSystem/ThinkSystem SR250 -[7Y51CTO1WW]-/56D35BA12534/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/A2FD0BC88C>) |
| 102b:0532 | 1028:0235 | Matrox Electr... | MGA G200eW WPCM450                   | 23    | mgag200    | [BC1B2F4337](<Server/Dell/PowerEdge/PowerEdge R710/4BD52918C3EA/UBUNTU-22.10/5.19.0-30-GENERIC/X86_64/BC1B2F4337>) |
| 102b:0522 | 8086:0101 | Matrox Electr... | MGA G200e [Pilot] ServerEngines (... | 20    | mgag200    | [94527A8584](<Server/Intel/S5500/S5500BC/A12E8B03104E/LINUXMINT-19.3/5.4.0-148-GENERIC/X86_64/94527A8584>) |
| 102b:0530 | 1014:0369 | Matrox Electr... | MGA G200EV                           | 19    | mgag200    | [16C68A28D8](<Server/IBM/System/System x3550 M3 -[7944SCP]-/B3404BB51BF1/DEBIAN-10/4.19.0-20-686-PAE/I686/16C68A28D8>) |
| 102b:0534 | 1028:048c | Matrox Electr... | G200eR2                              | 17    | mgag200    | [6A0AF69B4A](<Server/Dell/PowerEdge/PowerEdge R720/F424DE07066D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6A0AF69B4A>) |
| 102b:0532 | 15d9:0006 | Matrox Electr... | MGA G200eW WPCM450                   | 16    | mgag200    | [A3BE5CDF41](<Server/Supermicro/X8/X8DTL/26E707D77C6B/CENTOS-7/3.10.0-1160.83.1.EL7.X86_64/X86_64/A3BE5CDF41>) |
| 1a03:2000 | 15d9:0821 | ASPEED Techno... | ASPEED Graphics Family               | 16    | ast        | [17BF7A3CBC](<Server/Supermicro/SYS-6018/SYS-6018R-WTR/5EE2BAE645DD/CENTOS-7/3.10.0-862.14.4.EL7.X86_64/X86_64/17BF7A3CBC>) |
| 102b:0534 | 15d9:0636 | Matrox Electr... | G200eR2                              | 15    | mgag200    | [6994C89077](<Server/Supermicro/X9/X9DRW/6A1A83EBE660/DEBIAN-11/5.15.104-1-PVE/X86_64/6994C89077>) |
| 10de:1eba | 10de:0000 | Nvidia           | TU104GL [PG189 SKU600]               | 15    | nvidia     | [4391DFF8D2](<Server/Others/Others/Others/29E67FFE5E37/UBUNTU-18.04/4.18.0-20-GENERIC/X86_64/4391DFF8D2>) |
| 1a03:2000 | 1458:1000 | ASPEED Techno... | ASPEED Graphics Family               | 14    | ast        | [7BA797B6A5](<Server/Giga Computing/MC13/MC13-LE0-000/1D7046547004/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/7BA797B6A5>) |
| 102b:0534 | 1014:0405 | Matrox Electr... | G200eR2                              | 13    | mgag200    | [F2D1382390](<Server/IBM/System/System x3650 M4: -[2145DH8]-/453EF656FB54/ARCH-ROLLING/5.19.12-ARCH1-1/X86_64/F2D1382390>) |
| 102b:0538 | 1590:00e4 | Matrox Electr... | MGA G200eH3                          | 13    | mgag200    | [74466AD718](<Server/HPE/ProLiant/ProLiant DL360 Gen10 Plus/6004A3CDB655/DEBIAN-11/5.15.107-1-PVE/X86_64/74466AD718>) |
| 1a03:2000 | 15d9:1b2b | ASPEED Techno... | ASPEED Graphics Family               | 13    | ast        | [3E3CB25241](<Server/Supermicro/AS/AS -1014S-WTRT/4D11B8584472/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/3E3CB25241>) |
| 102b:0532 | 1028:0236 | Matrox Electr... | MGA G200eW WPCM450                   | 12    | mgag200    | [1A2EE8A8D5](<Server/Dell/PowerEdge/PowerEdge R610/37A92833E6A5/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/1A2EE8A8D5>) |
| 102b:0532 | 1028:028c | Matrox Electr... | MGA G200eW WPCM450                   | 12    | mgag200    | [C0B7421A8B](<Server/Dell/PowerEdge/PowerEdge R410/5EF56DA48933/DEBIAN-11/5.10.0-21-AMD64/X86_64/C0B7421A8B>) |
| 102b:0532 | 1028:04de | Matrox Electr... | MGA G200eW WPCM450                   | 12    | mgag200    | [745C5316F5](<Server/Dell/PowerEdge/PowerEdge T110 II/B75E91D5BD9F/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/745C5316F5>) |
| 102b:0534 | 1028:04fa | Matrox Electr... | G200eR2                              | 12    | mgag200    | [8EE7146669](<Server/Dell/PowerEdge/PowerEdge T320/6878B1DE0919/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/8EE7146669>) |
| 102b:0536 | 1028:0715 | Matrox Electr... | Integrated Matrox G200eW3 Graphic... | 12    | mgag200    | [7AD0D2D67B](<Server/Dell/PowerEdge/PowerEdge R740/FF8CDFB5CB55/UBUNTU-18.04/4.15.0-193-GENERIC/X86_64/7AD0D2D67B>) |
| 102b:0532 | 1028:02a4 | Matrox Electr... | MGA G200eW WPCM450                   | 11    | mgag200    | [83C0F8E7E5](<Server/Dell/PowerEdge/PowerEdge T310/0EAF01173A25/DEBIAN-11/5.15.79+TRUENAS/X86_64/83C0F8E7E5>) |
| 1a03:2000 | 1043:84eb | ASPEED Techno... | ASPEED Graphics Family               | 11    | ast        | [44B55B4721](<Server/ASUSTek Computer/P9D-M/P9D-M Series/61497326D129/MANJARO/5.15.108-1-MANJARO/X86_64/44B55B4721>) |
| 1a03:2000 | 1043:86ed | ASPEED Techno... | ASPEED Graphics Family               | 11    | ast        | [C874A6D28C](<Server/ASUSTek Computer/ESC8000/ESC8000 G4/05733798C837/UBUNTU-18.04/5.4.0-121-GENERIC/X86_64/C874A6D28C>) |
| 1a03:2000 | 15d9:0831 | ASPEED Techno... | ASPEED Graphics Family               | 11    | ast        | [5E92E7FE1E](<Server/Supermicro/Super/Super Server/FD3A63BBABAD/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/5E92E7FE1E>) |
| 1002:9874 | 1002:1871 | AMD              | Wani [Radeon R5/R6/R7 Graphics]      | 10    | amdgpu     | [01D2615C22](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/00C05E8C85AC/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/01D2615C22>) |
| 102b:0532 | 1028:02f1 | Matrox Electr... | MGA G200eW WPCM450                   | 10    | mgag200    | [51412400BA](<Server/Dell/PowerEdge/PowerEdge R510/9C3341952849/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/51412400BA>) |
| 102b:0534 | 1028:0601 | Matrox Electr... | G200eR2                              | 10    | mgag200    | [1ABE023ED7](<Server/Dell/PowerEdge/PowerEdge R630/0354475C3BDD/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/1ABE023ED7>) |
| 1a03:2000 | 15d9:089a | ASPEED Techno... | ASPEED Graphics Family               | 10    | ast        | [7AA0EB0936](<Server/Supermicro/Super/Super Server/7660AB944FAA/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/7AA0EB0936>) |
| 102b:0534 | 1028:04ce | Matrox Electr... | G200eR2                              | 9     | mgag200    | [3A287683DC](<Server/Dell/PowerEdge/PowerEdge R620/072234E6D563/DEBIAN-10/5.4.106-1-PVE/X86_64/3A287683DC>) |
| 102b:0534 | 1028:0600 | Matrox Electr... | G200eR2                              | 9     | mgag200    | [BE75097D0F](<Server/Dell/PowerEdge/PowerEdge R730/E686E52F7B47/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/BE75097D0F>) |
| 10de:1eb1 | 1028:12a0 | Nvidia           | TU104GL [Quadro RTX 4000]            | 9     | nvidia     | [962B265260](<Server/Dell/Precision/Precision 7920 Tower/8C7F63FF0FE0/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/962B265260>) |
| 1a03:2000 | 15d9:0801 | ASPEED Techno... | ASPEED Graphics Family               | 9     | ast        | [6CE8B7FB26](<Server/Supermicro/X10/X10SLL-F/34D1B7FAB08F/NIXOS-22.11/5.15.96/X86_64/6CE8B7FB26>) |
| 1a03:2000 | 15d9:086d | ASPEED Techno... | ASPEED Graphics Family               | 9     | ast        | [210B2E16E3](<Server/Supermicro/Super/Super Server/9DEEB33699DA/GENTOO-2.13/5.15.75-GENTOO-DIST/X86_64/210B2E16E3>) |
| 1002:515e | 1028:01b3 | AMD              | ES1000                               | 8     | radeon     | [2E77448A7D](<Server/Dell/PowerEdge/PowerEdge 1950/9FAD7399F359/DEBIAN-11/5.15.74-1-PVE/X86_64/2E77448A7D>) |
| 102b:0522 | 1734:108e | Matrox Electr... | MGA G200e [Pilot] ServerEngines (... | 8     | mgag200    | [C4C0B53877](<Server/Fujitsu/PRIMERGY/PRIMERGY TX150 S7/4BE064DA92A3/OL-9.0/5.15.0-0.30.19.EL9UEK.X86_64/X86_64/C4C0B53877>) |
| 102b:0532 | 15d9:ab11 | Matrox Electr... | MGA G200eW WPCM450                   | 8     | mgag200    | [E673BAB21F](<Server/Supermicro/H8/H8QG6/539918058863/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/E673BAB21F>) |
| 102b:0534 | 1028:04f8 | Matrox Electr... | G200eR2                              | 8     | mgag200    | [87EE1B58E4](<Server/Dell/PowerEdge/PowerEdge R420/BACBDE063781/DEBIAN-11/5.10.0-19-AMD64/X86_64/87EE1B58E4>) |
| 10de:128b | 1462:8c93 | Nvidia           | GK208B [GeForce GT 710]              | 8     | nouveau    | [6012DE6351](<Server/Supermicro/X8/X8DTU/17EEEE82432B/LINUXMINT-20.2/5.4.0-131-GENERIC/X86_64/6012DE6351>) |
| 19e5:1711 |           | Huawei Techno... | Hi171x Series [iBMC Intelligent M... | 8     | hibmc_drm  | [EB5771B190](<Server/HUAWEI/Taishan/Taishan 2180/98FD400CE456/DEBIAN-10/4.1.44-06.151.VHULK1711.1.1.AARCH64/AARCH64/EB5771B190>) |
| 1a03:2000 | 1043:85f9 | ASPEED Techno... | ASPEED Graphics Family               | 8     | ast        | [4158CB76EF](<Server/ASUSTek Computer/RS400/RS400-E8-PS2-F/B939D9497146/GENTOO-2.7/5.10.14-HARDENED1/X86_64/4158CB76EF>) |
| 1a03:2000 | 15d9:096d | ASPEED Techno... | ASPEED Graphics Family               | 8     | ast        | [DCBB3D117A](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.4.0-105-GENERIC/X86_64/DCBB3D117A>) |
| 102b:0522 | 8086:0102 | Matrox Electr... | MGA G200e [Pilot] ServerEngines (... | 7     | mgag200    | [891709C211](<Server/Intel/S1200/S1200BTL/F40AFD7A2D8F/FEDORA-36/6.2.8-100.FC36.X86_64/X86_64/891709C211>) |
| 102b:0532 | 1028:02a5 | Matrox Electr... | MGA G200eW WPCM450                   | 7     | mgag200    | [9F365307F3](<Server/Dell/PowerEdge/PowerEdge R210/5787887A4087/LUBUNTU-20.04/5.4.0-73-GENERIC/X86_64/9F365307F3>) |
| 102b:0532 | 15d9:0626 | Matrox Electr... | MGA G200eW WPCM450                   | 7     | mgag200    | [C4B4851A88](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/5E5B10F103C2/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/C4B4851A88>) |
| 102b:0532 | 15d9:bc11 | Matrox Electr... | MGA G200eW WPCM450                   | 7     | mgag200    | [EF32C0C2CA](<Server/Supermicro/H8/H8DG6-H8DGi/8E20B1D3526C/UBUNTU-18.04/4.15.0-200-GENERIC/X86_64/EF32C0C2CA>) |
| 1a03:2000 | 15d9:0967 | ASPEED Techno... | ASPEED Graphics Family               | 7     | ast        | [DE3332B83C](<Server/Supermicro/SYS-6029/SYS-6029P-WTRT/35C50F3639E9/ACRONIS-CYBER-INFRASTRUCTURE-5.1.0/3.10.0-1160.53.1.VZ7.185.3/X86_64/DE3332B83C>) |
| 1a03:2000 | 15d9:1b95 | ASPEED Techno... | ASPEED Graphics Family               | 7     | ast        | [55AF41B298](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.7/4.18.0-425.19.2.EL8_7.X86_64/X86_64/55AF41B298>) |

### Input device controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1102:7003 | 1102:0040 | Creative Labs    | SB Audigy Game Port                  | 4     | emu10k1_gp | [A41CABB3D6](<Server/Dell/PowerEdge/PowerEdge SC1430/2088C31572DB/DEBIAN-11/5.10.0-19-AMD64/X86_64/A41CABB3D6>) |
| 1102:7002 | 1102:0020 | Creative Labs    | SB Live! Game Port                   | 1     | emu10k1_gp | [80DC2F8936](<Server/Supermicro/Super/Super Server/A9CFB59D8528/OPENSUSE-LEAP-42.1/4.1.39-56-DEFAULT/X86_64/80DC2F8936>) |
| 1102:7003 | 1102:0060 | Creative Labs    | SB Audigy Game Port                  | 1     | emu10k1_gp | [D471D2B279](<Server/Wortmann AG/TERRA/TERRA Server/DAE4E032512D/UBUNTU-20.04/5.4.0-33-GENERIC/X86_64/D471D2B279>) |

### Iommu (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1481 | 1022:1481 | AMD              | Starship/Matisse IOMMU               | 31    |            | [55AF41B298](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.7/4.18.0-425.19.2.EL8_7.X86_64/X86_64/55AF41B298>) |
| 1022:164f | 1022:164f | AMD              | Milan IOMMU                          | 8     |            | [A3F043A03C](<Server/Supermicro/M12/M12SWA-TF/4F883AA311F8/UBUNTU-22.04/5.15.0-33-GENERIC/X86_64/A3F043A03C>) |
| 1022:1481 | 1458:1000 | AMD              | Starship/Matisse IOMMU               | 6     |            | [DEF4067C8E](<Server/Gigabyte Technology/G242/G242-Z11-00/B5251D581093/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/DEF4067C8E>) |
| 1022:1631 | 1022:1631 | AMD              | Renoir/Cezanne IOMMU                 | 6     |            | [D6E47A7C18](<Server/BESSTAR Tech/X/X500/81B31475FFFF/XEROLINUX-KDE-ROLLING/5.17.9-ARCH1-1/X86_64/D6E47A7C18>) |
| 1022:1481 | 1028:08fc | AMD              | Starship/Matisse IOMMU               | 5     |            | [237A3CD682](<Server/Dell/PowerEdge/PowerEdge R6515/647C815644AA/DEBIAN-12/6.1.0-5-AMD64/X86_64/237A3CD682>) |
| 1022:1481 | 1028:08ff | AMD              | Starship/Matisse IOMMU               | 5     |            | [77F946C99B](<Server/Dell/PowerEdge/PowerEdge R7525/ED52A1D54F9D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/77F946C99B>) |
| 1002:5a23 | 1028:0444 | AMD              | RD890S/RD990 I/O Memory Managemen... | 4     |            | [13BD99E4BC](<Server/Dell/PowerEdge/PowerEdge R815/0D8B6921A323/KUBUNTU-22.10/5.19.0-1021-LOWLATENCY/X86_64/13BD99E4BC>) |
| 1022:1481 | 1028:08fd | AMD              | Starship/Matisse IOMMU               | 3     |            | [F0B9CD86EF](<Server/Dell/PowerEdge/PowerEdge R7515/723F15A8AB49/UBUNTU-22.04/5.15.0-47-GENERIC/X86_64/F0B9CD86EF>) |
| 1022:164f | 1028:08fc | AMD              | Milan IOMMU                          | 3     |            | [D56CA4A374](<Server/Dell/PowerEdge/PowerEdge R6515/C4B03BD3B174/UBUNTU-22.04/5.15.0-41-GENERIC/X86_64/D56CA4A374>) |
| 8086:1f16 | 15d9:0820 | Intel            | Atom processor C2000 RCEC            | 2     |            | [A9E1A5906C](<Server/Supermicro/A1/A1SAM-2550F/B9FD41A2E4E7/MANJARO-21.2.3/5.15.21-1-MANJARO/X86_64/A9E1A5906C>) |
| 1002:5a23 | 1028:0445 | AMD              | RD890S/RD990 I/O Memory Managemen... | 1     |            | [0E5CEE5637](<Server/Dell/PowerEdge/PowerEdge R715/E2B668AC841B/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/0E5CEE5637>) |
| 1002:5a23 | 103c:1762 | AMD              | RD890S/RD990 I/O Memory Managemen... | 1     |            | [E60DA0D6CE](<Server/Hewlett-Packard/ProLiant/ProLiant DL385p Gen8/EAADD5928698/UBUNTU-20.04/5.4.0-37-GENERIC/X86_64/E60DA0D6CE>) |
| 1002:5a23 | 103c:3324 | AMD              | RD890S/RD990 I/O Memory Managemen... | 1     |            | [7CE46A749E](<Server/Hewlett-Packard/ProLiant/ProLiant DL165 G7/1273A822F849/UBUNTU-19.04/5.0.0-20-LOWLATENCY/X86_64/7CE46A749E>) |
| 1022:1451 | 1028:07f9 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 1     |            | [8F7FF50C55](<Server/Dell/PowerEdge/PowerEdge R7425/EEF1E1F22650/OPENSUSE-LEAP-15.1/4.12.14-LP151.28.13-DEFAULT/X86_64/8F7FF50C55>) |
| 1022:149e | 1022:149e | AMD              | Genoa IOMMU                          | 1     |            | [B7E67F8130](<Server/AMD/Volcano/Volcano/59C634EF9C63/DEBIAN-11/5.10.0-21-AMD64/X86_64/B7E67F8130>) |
| 1022:14d9 | 1022:14d9 | AMD              | Family 19h IOMMU Controller          | 1     |            | [7BA797B6A5](<Server/Giga Computing/MC13/MC13-LE0-000/1D7046547004/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/7BA797B6A5>) |
| 1022:164f | 1028:08ff | AMD              | Milan IOMMU                          | 1     |            | [B7AC531BF5](<Server/Dell/PowerEdge/PowerEdge R7525/3F409CE3A366/RHEL-8///B7AC531BF5>) |
| 1022:164f | 1028:0900 | AMD              | Milan IOMMU                          | 1     |            | [382F999542](<Server/Dell/PowerEdge/PowerEdge C6525/B11FEC7694D8/ARCH/5.15.59-1-LTS/X86_64/382F999542>) |
| 1022:164f | 1458:1000 | AMD              | Milan IOMMU                          | 1     |            | [A4D3AB40A5](<Server/Gigabyte Technology/MC62/MC62-G40-00/FF6922E2D8CA/MANJARO-22.0.0/5.19.7-1-MANJARO/X86_64/A4D3AB40A5>) |
| 8086:1f16 | 15d9:0828 | Intel            | Atom processor C2000 RCEC            | 1     |            | [E134D7A317](<Server/Supermicro/A1/A1SA2-2750F/64B5066C8E62/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E134D7A317>) |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 103c:3302 | 103c:3305 | Hewlett-Packard  | Integrated Lights-Out Standard KC... | 34    | ipmi_si    | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |

### Isdn adapter (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1244:0a00 | 1244:0a00 | AVM              | A1 ISDN [Fritz]                      | 1     | fcpci      | [750A124EF3](<Server/Wortmann AG/TERRA_PC/TERRA_PC/8340D78F7FD7/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/750A124EF3>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a1a1 | 8086:7270 | Intel            | C620 Series Chipset Family Power ... | 48    |            | [18B2BF9FF4](<Server/Delta Computers/DSS-C621/DSS-C621LTG/EA1701537BF7/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/18B2BF9FF4>) |
| 8086:a36f | 8086:7270 | Intel            | Cannon Lake PCH Shared SRAM          | 25    |            | [A2FD0BC88C](<Server/Lenovo/ThinkSystem/ThinkSystem SR250 -[7Y51CTO1WW]-/56D35BA12534/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/A2FD0BC88C>) |
| 8086:a1a1 | 8086:35ce | Intel            | C620 Series Chipset Family Power ... | 21    |            | [F5848D1BA2](<Server/DALCO/S2600/S2600WFT/37B0D5359698/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/F5848D1BA2>) |
| 8086:a1a1 | 1028:073a | Intel            | C620 Series Chipset Family Power ... | 20    |            | [962B265260](<Server/Dell/Precision/Precision 7920 Tower/8C7F63FF0FE0/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/962B265260>) |
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 17    |            | [97D3C70FB5](<Server/Quanta/QuantaMicro/QuantaMicro X10E-9N/01ACEA39AAB2/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/97D3C70FB5>) |
| 8086:a1a1 | 1028:0715 | Intel            | C620 Series Chipset Family Power ... | 12    |            | [7AD0D2D67B](<Server/Dell/PowerEdge/PowerEdge R740/FF8CDFB5CB55/UBUNTU-18.04/4.15.0-193-GENERIC/X86_64/7AD0D2D67B>) |
| 8086:a1a1 | 1028:0739 | Intel            | C620 Series Chipset Family Power ... | 12    |            | [FE6DC0D9C7](<Server/Dell/Precision/Precision 7820 Tower/FB09ECB98D56/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FE6DC0D9C7>) |
| 8086:a1a1 | 1590:00eb | Intel            | C620 Series Chipset Family Power ... | 12    |            | [74466AD718](<Server/HPE/ProLiant/ProLiant DL360 Gen10 Plus/6004A3CDB655/DEBIAN-11/5.15.107-1-PVE/X86_64/74466AD718>) |
| 8086:a1a1 | 1043:871e | Intel            | C620 Series Chipset Family Power ... | 11    |            | [C874A6D28C](<Server/ASUSTek Computer/ESC8000/ESC8000 G4/05733798C837/UBUNTU-18.04/5.4.0-121-GENERIC/X86_64/C874A6D28C>) |
| 8086:a121 | 15d9:089a | Intel            | 100 Series/C230 Series Chipset Fa... | 10    |            | [7AA0EB0936](<Server/Supermicro/Super/Super Server/7660AB944FAA/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/7AA0EB0936>) |
| 8086:a1a1 | 15d9:096d | Intel            | C620 Series Chipset Family Power ... | 8     |            | [DCBB3D117A](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.4.0-105-GENERIC/X86_64/DCBB3D117A>) |
| 8086:a36f |           | Intel            | Cannon Lake PCH Shared SRAM          | 8     |            | [029040A622](<Server/Dell/PowerEdge/PowerEdge R240/7ED18DB7AC28/UBUNTU-20.04/5.15.0-48-GENERIC/X86_64/029040A622>) |
| 8086:a36f | 8086:a36f | Intel            | Cannon Lake PCH Shared SRAM          | 8     |            | [196C8EB317](<Server/Neousys Technology/Nuvo-7100VTC/Nuvo-7100VTC Series/E44E3E216941/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/196C8EB317>) |
| 8086:a1a1 | 15d9:0967 | Intel            | C620 Series Chipset Family Power ... | 7     |            | [DE3332B83C](<Server/Supermicro/SYS-6029/SYS-6029P-WTRT/35C50F3639E9/ACRONIS-CYBER-INFRASTRUCTURE-5.1.0/3.10.0-1160.53.1.VZ7.185.3/X86_64/DE3332B83C>) |
| 8086:a1a1 | 17aa:7808 | Intel            | C620 Series Chipset Family Power ... | 7     |            | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 1590:005f | 1590:005f | Hewlett-Packard  | Memory controller                    | 6     |            | [5477E8F714](<Server/Hewlett-Packard/ProLiant/ProLiant DL360e Gen8/0F9365A4AA99/DEBIAN-11/5.10.0-18-AMD64/X86_64/5477E8F714>) |
| 8086:a121 | 1028:06a5 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     |            | [C8D2D41009](<Server/Dell/PowerEdge/PowerEdge R230/5B911C7AB359/UBUNTU-20.04/5.4.0-97-GENERIC/X86_64/C8D2D41009>) |
| 8086:a121 | 15d9:0895 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     |            | [CE6BAA4FDA](<Server/Supermicro/Super/Super Server/A842905AAA3B/UBUNTU-18.04/5.4.0-132-GENERIC/X86_64/CE6BAA4FDA>) |
| 8086:a1a1 | 1028:0718 | Intel            | C620 Series Chipset Family Power ... | 6     |            | [A4F3535E84](<Server/Dell/Precision/Precision 7920 Rack/1D56B1A533A9/UBUNTU-20.04/5.14.0-1057-OEM/X86_64/A4F3535E84>) |
| 8086:a1a1 | 103c:81c7 | Intel            | C620 Series Chipset Family Power ... | 6     |            | [50CCA471C5](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/010A19E087DC/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/50CCA471C5>) |
| 8086:a1a1 | 17aa:7801 | Intel            | C620 Series Chipset Family Power ... | 6     |            | [BAFB634A37](<Server/Lenovo/ThinkSystem/ThinkSystem SR530 -[7X08CTO1WW]-/16717DADAA79/CENTOS-7/3.10.0-1160.36.2.EL7.X86_64/X86_64/BAFB634A37>) |
| 8086:a1a1 | 1849:a1a1 | Intel            | C620 Series Chipset Family Power ... | 6     |            | [51DC310024](<Server/Kraftway/Trusted/Trusted TS2000/583173D8B5F2/RED-OS-7.3.2/6.1.11-1.EL7.3.X86_64/X86_64/51DC310024>) |
| 8086:a1a1 | 103c:81c6 | Intel            | C620 Series Chipset Family Power ... | 5     |            | [C60CE01C1E](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/5FDF871A62B0/UBUNTU-20.04/5.15.0-48-GENERIC/X86_64/C60CE01C1E>) |
| 8086:a1a1 | 15d9:095d | Intel            | C620 Series Chipset Family Power ... | 5     |            | [6D1F207293](<Server/primeLine Solutions/egino/egino BTO Konfig Server/B668BEC7EEFE/DEBIAN-11/5.15.85-1-PVE/X86_64/6D1F207293>) |
| 8086:a1a1 | 15d9:0981 | Intel            | C620 Series Chipset Family Power ... | 5     |            | [D9B96BCE95](<Server/Supermicro/Super/Super Server/909986EADB14/UBUNTU-22.10/5.19.0-23-GENERIC/X86_64/D9B96BCE95>) |
| 8086:a2a1 | 15d9:098e | Intel            | 200 Series/Z370 Chipset Family Po... | 5     |            | [2887A82948](<Server/Supermicro/Super/Super Server/4CD262ADBF12/DEBIAN-11/5.19.11/X86_64/2887A82948>) |
| 10de:0369 | 1462:cb84 | Nvidia           | MCP55 Memory Controller              | 4     |            | [1888FA6DF7](<Server/MSI/MCP/MCP55/E26C4EDDD3C1/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/1888FA6DF7>) |
| 1912:0011 |           | Renesas Techn... | SH7757 PCIe End-Point [PBI]          | 4     |            | [ACA491BB91](<Server/Others/A/A06/03B41DA567E8/RHEL-8/4.18.0-348.12.2.EL8_5.X86_64/X86_64/ACA491BB91>) |
| 8086:19de | 15d9:0969 | Intel            | Atom Processor C3000 Series Power... | 4     |            | [CDCA826585](<Server/Supermicro/Super/Super Server/67F50154C8D4/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/CDCA826585>) |
| 8086:1bce | 8086:7270 | Intel            | C741 Series PMC Shared               | 4     |            | [3DDB00DA94](<Server/Intel/ArcherCity/ArcherCity/35F42C801DE0/FEDORA-37/6.1.7-200.FC37.X86_64/X86_64/3DDB00DA94>) |
| 8086:a1a1 | 1028:0716 | Intel            | C620 Series Chipset Family Power ... | 4     |            | [02F8E21FA8](<Server/Dell/PowerEdge/PowerEdge R640/D35AD5A42EE7/UBUNTU-20.04/5.4.0-105-GENERIC/X86_64/02F8E21FA8>) |
| 8086:a1a1 | 1028:0737 | Intel            | C620 Series Chipset Family Power ... | 4     |            | [D2AE46F823](<Server/Dell/XC740xd-12/XC740xd-12 CORE/DD8724B460B5/UBUNTU-18.04/4.15.0-175-GENERIC/X86_64/D2AE46F823>) |
| 8086:a1a1 | 1028:07cb | Intel            | C620 Series Chipset Family Power ... | 4     |            | [465C40DD0F](<Server/Dell/PowerEdge/PowerEdge T440/1E0687BF68BA/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/465C40DD0F>) |
| 8086:a1a1 | 15d9:091c | Intel            | C620 Series Chipset Family Power ... | 4     |            | [90F9906D76](<Server/Supermicro/SYS-1029/SYS-1029U-TR25M-BK-LC019/25926C72BE6F/ACRONIS-CYBER-INFRASTRUCTURE-5.1.1/3.10.0-1160.53.1.VZ7.185.3/X86_64/90F9906D76>) |
| 8086:a1a1 | 15d9:0953 | Intel            | C620 Series Chipset Family Power ... | 4     |            | [A76BB2E30D](<Server/Supermicro/SYS-5029/SYS-5029P-WTR/2D889DFAC2FF/ROCKY-8.5/4.18.0-348.12.2.EL8_5.X86_64/X86_64/A76BB2E30D>) |
| 8086:a1a1 | 15d9:0986 | Intel            | C620 Series Chipset Family Power ... | 4     |            | [FFA58F1702](<Server/Supermicro/SYS-E300/SYS-E300-9D-8CN8TP/202BFE094BD2/DEBIAN-11/5.10.0-21-AMD64/X86_64/FFA58F1702>) |
| 8086:a1a1 | 17aa:1038 | Intel            | C620 Series Chipset Family Power ... | 4     |            | [7630762F0E](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC001DGE/B0EFE7081048/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/7630762F0E>) |
| 8086:a1a1 | 17aa:7800 | Intel            | C620 Series Chipset Family Power ... | 4     |            | [C97EB83B9C](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 -[7X06CTO1WW]-/7AFAAAD68C64/CENTOS-7/3.10.0-1160.36.2.EL7.X86_64/X86_64/C97EB83B9C>) |
| 8086:a121 | 1028:06aa | Intel            | 100 Series/C230 Series Chipset Fa... | 3     |            | [5959883085](<Server/Dell/PowerEdge/PowerEdge T130/DAC592B2E02F/UBUNTU-22.04/5.15.0-40-GENERIC/X86_64/5959883085>) |
| 8086:a121 | 15d9:0884 | Intel            | 100 Series/C230 Series Chipset Fa... | 3     |            | [A65A6E89D1](<Server/Thomas-Krenn.AG/Super/Super Server/05511CFA9691/FEDORA-37/6.0.9-300.FC37.X86_64/X86_64/A65A6E89D1>) |
| 8086:a1a1 | 1028:07c9 | Intel            | C620 Series Chipset Family Power ... | 3     |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:a1a1 | 1458:5001 | Intel            | C620 Series Chipset Family Power ... | 3     |            | [030B77C94D](<Server/Gigabyte Technology/C621/C621-WD12-IPMI/5E4783EDD64C/ROCKY-8.7/4.18.0-425.13.1.EL8_7.X86_64/X86_64/030B77C94D>) |
| 8086:a1a1 | 17aa:1037 | Intel            | C620 Series Chipset Family Power ... | 3     |            | [1D6082EFE8](<Server/Lenovo/ThinkStation/ThinkStation P720 30BBS21C01/FE8DF4F9C290/FEDORA-37/6.2.11-200.FC37.X86_64/X86_64/1D6082EFE8>) |
| 10de:0369 | 108e:534b | Nvidia           | MCP55 Memory Controller              | 2     |            | [ED02F6A855](<Server/Sun Microsystems/Sun/Sun Fire X2200 M2/BEDAEAEA8D92/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/ED02F6A855>) |
| 8086:43ef | 1043:882f | Intel            | Tiger Lake-H Shared SRAM             | 2     |            | [F4BF235EA8](<Server/ASUSTek Computer/P12R-E/P12R-E Series 60SB0A90-SB0A08/4BCF5AD8367F/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/F4BF235EA8>) |
| 8086:43ef | 1458:1000 | Intel            | Tiger Lake-H Shared SRAM             | 2     |            | [ABFEE9C5F7](<Server/Gigabyte Technology/MX33/MX33-BS0-00/2E0D4C1B34E3/KUBUNTU-22.04/5.17.0-1017-OEM/X86_64/ABFEE9C5F7>) |
| 8086:4def |           | Intel            | Jasper Lake Shared SRAM Controller   | 2     |            | [F5A2B2DE44](<Server/GEEKOM/MiniAir/MiniAir 11/A07BDBCD0072/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/F5A2B2DE44>) |
| 8086:a121 | 1028:06a7 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [4D9F06CA7B](<Server/Dell/PowerEdge/PowerEdge T330/99156426010E/DEBIAN-11/5.10.0-20-AMD64/X86_64/4D9F06CA7B>) |
| 8086:a121 | 15d9:088b | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [C0E1C15247](<Server/Supermicro/C7/C7Z170-M/5D50FA33A353/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/C0E1C15247>) |
| 8086:a121 | 15d9:0896 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [B0100C59BB](<Server/Supermicro/Super/Super Server/E58401D9CAE3/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/B0100C59BB>) |

### Mips (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 177d:0092 | 177d:0001 | Cavium           | Octeon II CN65XX Network Processor   | 2     | vfio_pci   | [FB9B03532C](<Server/Supermicro/X9/X9DRW/6A1A83EBE660/DEBIAN-11/5.15.39-1-PVE/X86_64/FB9B03532C>) |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15e2 | 1022:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 6     | snd_pci... | [D6E47A7C18](<Server/BESSTAR Tech/X/X500/81B31475FFFF/XEROLINUX-KDE-ROLLING/5.17.9-ARCH1-1/X86_64/D6E47A7C18>) |
| 1131:7164 | 0070:8851 | Philips Semic... | SAA7164                              | 2     | saa7164    | [DFB6580F2A](<Server/Dell/PowerEdge/PowerEdge T710/DA543BCEB9D6/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/DFB6580F2A>) |
| 109e:0878 |           | Brooktree        | Bt878 Audio Capture                  | 1     | bt878      | [B55D1DAEA5](<Server/Intel/S5500/S5500BC/EB1E1FCFB3A4/UBUNTU-MATE-19.10/5.3.0-51-GENERIC/X86_64/B55D1DAEA5>) |
| 109e:0878 | 0070:ff04 | Brooktree        | Bt878 Audio Capture                  | 1     |            | [2C877CF870](<Server/Hewlett-Packard/ProLiant/ProLiant DL140 G2/7851FB932D49/ARCH/4.18.12-ARCH1-1-ARCH/X86_64/2C877CF870>) |
| 109e:0878 | 800a:763d | Brooktree        | Bt878 Audio Capture                  | 1     |            | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 109e:0878 | 800b:763d | Brooktree        | Bt878 Audio Capture                  | 1     |            | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 109e:0878 | 800c:763d | Brooktree        | Bt878 Audio Capture                  | 1     |            | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 109e:0878 | 800d:763d | Brooktree        | Bt878 Audio Capture                  | 1     |            | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 1172:e003 | 1172:0000 | Altera           | Multimedia controller                | 1     | dyvi       | [1126AE11AE](<Server/ASUSTek Computer/Z11PG-D16/Z11PG-D16 Series/9878F56186D3/DEBIAN-9/4.9.35-DYVI/X86_64/1126AE11AE>) |
| 11af:0012 | 11af:0444 | Avid Technology  | Multimedia controller                | 1     |            | [841DF68A54](<Server/Intel/Thurley/Thurley/FE991D0B4D72/UBUNTU-22.04/5.15.0-25-GENERIC/X86_64/841DF68A54>) |
| 11af:0013 | 11af:0448 | Avid Technology  | Multimedia controller                | 1     |            | [841DF68A54](<Server/Intel/Thurley/Thurley/FE991D0B4D72/UBUNTU-22.04/5.15.0-25-GENERIC/X86_64/841DF68A54>) |
| 1797:6869 |           | Intersil Tech... | C968 PCIe SD Capture                 | 1     | avc8000    | [375EC8881D](<Server/Neousys Technology/Nuvo-8208GC/Nuvo-8208GC Series/78293157040C/UBUNTU-18.04/5.4.0-53-GENERIC/X86_64/375EC8881D>) |
| 544d:6178 | 6909:0019 | TBS Technologies | DVB Tuner PCIe Card                  | 1     | tbsecp3    | [72B9753B42](<Server/Hewlett-Packard/ProLiant/ProLiant DL380e Gen8/F46144405C53/UBUNTU-18.04/4.15.0-202-GENERIC/X86_64/72B9753B42>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14e4:1639 | 103c:7055 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 50    | bnx2       | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |
| 14e4:1657 | 103c:169d | Broadcom         | NetXtreme BCM5719 Gigabit Etherne... | 39    | tg3        | [961A066E6B](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/F726BB41B090/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/961A066E6B>) |
| 14e4:165f | 1028:1f5b | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 36    | tg3        | [BA5FEBE33B](<Server/Dell/PowerEdge/PowerEdge R730/B08360FD5D56/UBUNTU-20.04/5.15.0-67-GENERIC/X86_64/BA5FEBE33B>) |
| 8086:37d2 | 15d9:37d2 | Intel            | Ethernet Connection X722 for 10GB... | 31    | i40e       | [6D1F207293](<Server/primeLine Solutions/egino/egino BTO Konfig Server/B668BEC7EEFE/DEBIAN-11/5.15.85-1-PVE/X86_64/6D1F207293>) |
| 14e4:1657 | 103c:22be | Broadcom         | NetXtreme BCM5719 Gigabit Etherne... | 30    | tg3        | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:1572 | 8086:0000 | Intel            | Ethernet Controller X710 for 10Gb... | 28    | i40e       | [8382988CA9](<Server/Supermicro/Super/Super Server/BC9F8E43AF76/DEBIAN-11/5.15.107-1-PVE/X86_64/8382988CA9>) |
| 14e4:1639 | 1028:0235 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 24    | bnx2       | [BC1B2F4337](<Server/Dell/PowerEdge/PowerEdge R710/4BD52918C3EA/UBUNTU-22.10/5.19.0-30-GENERIC/X86_64/BC1B2F4337>) |
| 8086:15b9 | 1028:073a | Intel            | Ethernet Connection (3) I219-LM      | 20    | e1000e     | [962B265260](<Server/Dell/Precision/Precision 7920 Tower/8C7F63FF0FE0/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/962B265260>) |
| 14e4:164c | 103c:7038 | Broadcom Limited | NetXtreme II BCM5708 Gigabit Ethe... | 17    | bnx2       | [8CF84909E3](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G5/CB5A662BC228/CENTOS-7/3.10.0-1160.88.1.EL7.X86_64/X86_64/8CF84909E3>) |
| 8086:15b9 | 8086:0000 | Intel            | Ethernet Connection (3) I219-LM      | 17    | e1000e     | [4391DFF8D2](<Server/Others/Others/Others/29E67FFE5E37/UBUNTU-18.04/4.18.0-20-GENERIC/X86_64/4391DFF8D2>) |
| 14e4:16d8 | 15d9:16d8 | Broadcom         | BCM57416 NetXtreme-E Dual-Media 1... | 16    | bnxt_en    | [6161A05CF1](<Server/Supermicro/Super/Super Server/46FD6D462182/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/6161A05CF1>) |
| 8086:153a | 15d9:153a | Intel            | Ethernet Connection I217-LM          | 16    | e1000e     | [4B0CFEC9A7](<Server/Supermicro/X10/X10SAE/FF0B31A8C494/NOBARA-37/6.2.10-200.FSYNC.FC37.X86_64/X86_64/4B0CFEC9A7>) |
| 8086:1521 | 103c:3380 | Intel            | I350 Gigabit Network Connection      | 15    | igb        | [72B9753B42](<Server/Hewlett-Packard/ProLiant/ProLiant DL380e Gen8/F46144405C53/UBUNTU-18.04/4.15.0-202-GENERIC/X86_64/72B9753B42>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 14    | r8169      | [F5A2B2DE44](<Server/GEEKOM/MiniAir/MiniAir 11/A07BDBCD0072/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/F5A2B2DE44>) |
| 14e4:1639 | 1028:0236 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 14    | bnx2       | [1A2EE8A8D5](<Server/Dell/PowerEdge/PowerEdge R610/37A92833E6A5/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/1A2EE8A8D5>) |
| 14e4:163b | 1028:028c | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 14    | bnx2       | [C0B7421A8B](<Server/Dell/PowerEdge/PowerEdge R410/5EF56DA48933/DEBIAN-11/5.10.0-21-AMD64/X86_64/C0B7421A8B>) |
| 14e4:165f | 1028:04fa | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 14    | tg3        | [8EE7146669](<Server/Dell/PowerEdge/PowerEdge T320/6878B1DE0919/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/8EE7146669>) |
| 14e4:1639 | 1014:03a9 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 13    | bnx2       | [16C68A28D8](<Server/IBM/System/System x3550 M3 -[7944SCP]-/B3404BB51BF1/DEBIAN-10/4.19.0-20-686-PAE/I686/16C68A28D8>) |
| 14e4:163b | 1028:02a4 | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 13    | bnx2       | [83C0F8E7E5](<Server/Dell/PowerEdge/PowerEdge T310/0EAF01173A25/DEBIAN-11/5.15.79+TRUENAS/X86_64/83C0F8E7E5>) |
| 14e4:165a | 1028:04de | Broadcom         | NetXtreme BCM5722 Gigabit Etherne... | 13    | tg3        | [745C5316F5](<Server/Dell/PowerEdge/PowerEdge T110 II/B75E91D5BD9F/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/745C5316F5>) |
| 8086:10fb | 8086:0003 | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 13    | ixgbe      | [5FBA63C085](<Server/Intel/S4600/S4600LH/902A1E31749C/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/5FBA63C085>) |
| 8086:37d1 | 17aa:4020 | Intel            | Ethernet Connection X722 for 1GbE    | 13    | i40e       | [BAFB634A37](<Server/Lenovo/ThinkSystem/ThinkSystem SR530 -[7X08CTO1WW]-/16717DADAA79/CENTOS-7/3.10.0-1160.36.2.EL7.X86_64/X86_64/BAFB634A37>) |
| 15b3:1015 | 15b3:0004 | Mellanox Tech... | MT27710 Family [ConnectX-4 Lx]       | 12    | mlx5_core  | [5E92E7FE1E](<Server/Supermicro/Super/Super Server/FD3A63BBABAD/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/5E92E7FE1E>) |
| 8086:1563 | 15d9:1563 | Intel            | Ethernet Controller X550             | 12    | ixgbe      | [C37F8CD97A](<Server/Supermicro/Super/Super Server/3D7809C86280/DEBIAN-11/5.15.74-1-PVE/X86_64/C37F8CD97A>) |
| 8086:15b9 | 1028:0739 | Intel            | Ethernet Connection (3) I219-LM      | 12    | e1000e     | [FE6DC0D9C7](<Server/Dell/Precision/Precision 7820 Tower/FB09ECB98D56/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FE6DC0D9C7>) |
| 14e4:163b | 1028:02f1 | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 11    | bnx2       | [51412400BA](<Server/Dell/PowerEdge/PowerEdge R510/9C3341952849/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/51412400BA>) |
| 14e4:165f | 103c:22e8 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 11    | tg3        | [01D2615C22](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/00C05E8C85AC/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/01D2615C22>) |
| 8086:1528 | 15d9:1528 | Intel            | Ethernet Controller 10-Gigabit X5... | 11    | ixgbe      | [3DCF1286AB](<Server/Supermicro/Super/Super Server/34AD0A1E9B39/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/3DCF1286AB>) |
| 8086:15b7 | 15d9:15b7 | Intel            | Ethernet Connection (2) I219-LM      | 11    | e1000e     | [7FD98E489A](<Server/Supermicro/X11/X11SSV-Q/FE7DA47D9138/OPENMANDRIVA-22.12/6.0.10-DESKTOP-GCC-2OMV22090/X86_64/7FD98E489A>) |
| 14e4:165f | 1028:08fd | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 10    | tg3        | [237A3CD682](<Server/Dell/PowerEdge/PowerEdge R6515/647C815644AA/DEBIAN-12/6.1.0-5-AMD64/X86_64/237A3CD682>) |
| 8086:159b | 8086:0003 | Intel            | Ethernet Controller E810-XXV for SFP | 10    | ice        | [3E3CB25241](<Server/Supermicro/AS/AS -1014S-WTRT/4D11B8584472/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/3E3CB25241>) |
| 8086:37ce | 8086:0000 | Intel            | Ethernet Connection X722 for 10Gb... | 10    | i40e       | [BDFA203C78](<Server/Supermicro/SBI-6119/SBI-6119P-T3N/985FBFBECAB2/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/BDFA203C78>) |
| 8086:10fb | 108e:7b11 | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 9     | ixgbe      | [5A96F790B1](<Server/Supermicro/Super/Super Server/022F96D5DAA8/CENTOS-7/3.10.0-862.14.4.EL7.X86_64/X86_64/5A96F790B1>) |
| 8086:37d1 | 15d9:37d1 | Intel            | Ethernet Connection X722 for 1GbE    | 9     | i40e       | [38AE00936B](<Server/Supermicro/X11/X11DPi-N/C01F92B951F6/FEDORA-35/5.17.8-200.FC35.X86_64/X86_64/38AE00936B>) |
| 14e4:1639 | 1028:1f26 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 8     | bnx2       | [0E5CEE5637](<Server/Dell/PowerEdge/PowerEdge R715/E2B668AC841B/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/0E5CEE5637>) |
| 14e4:164c | 1028:01b3 | Broadcom         | NetXtreme II BCM5708 Gigabit Ethe... | 8     | bnx2       | [2E77448A7D](<Server/Dell/PowerEdge/PowerEdge 1950/9FAD7399F359/DEBIAN-11/5.15.74-1-PVE/X86_64/2E77448A7D>) |
| 14e4:165f | 1028:04f8 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 8     | tg3        | [87EE1B58E4](<Server/Dell/PowerEdge/PowerEdge R420/BACBDE063781/DEBIAN-11/5.10.0-19-AMD64/X86_64/87EE1B58E4>) |
| 14e4:168e | 103c:3382 | Broadcom         | NetXtreme II BCM57810 10 Gigabit ... | 8     | bnx2x      | [A31A2A807F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/706E3A372AB2/R-VIRTUALIZATION-7/3.10.0-1062.12.1.RV7.131.10.1/X86_64/A31A2A807F>) |
| 8086:1076 | 8086:34d0 | Intel            | 82541GI Gigabit Ethernet Controller  | 8     | e1000      | [40FC7CD8AA](<Server/Intel/S3210/S3210SH/D6FE7FA8CA14/DEBIAN-11/5.15.30-2-PVE/X86_64/40FC7CD8AA>) |
| 8086:15bb | 15d9:15bb | Intel            | Ethernet Connection (7) I219-LM      | 8     | e1000e     | [065427C37F](<Server/Supermicro/Super/Super Server/2CF7574245C0/DEBIAN-11/5.10.162-1.LAT5.10.0-21/X86_64/065427C37F>) |
| 8086:15bb | 8086:0000 | Intel            | Ethernet Connection (7) I219-LM      | 8     | e1000e     | [196C8EB317](<Server/Neousys Technology/Nuvo-7100VTC/Nuvo-7100VTC Series/E44E3E216941/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/196C8EB317>) |
| 14e4:163b | 1028:02a5 | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 7     | bnx2       | [9F365307F3](<Server/Dell/PowerEdge/PowerEdge R210/5787887A4087/LUBUNTU-20.04/5.4.0-73-GENERIC/X86_64/9F365307F3>) |
| 14e4:164c | 1028:01b2 | Broadcom         | NetXtreme II BCM5708 Gigabit Ethe... | 7     | bnx2       | [75A840C1D8](<Server/Dell/PowerEdge/PowerEdge 2950/C63204CC3467/UBUNTU-16.04/4.4.0-194-GENERIC/X86_64/75A840C1D8>) |
| 14e4:165a | 1028:02a6 | Broadcom         | NetXtreme BCM5722 Gigabit Etherne... | 7     | tg3        | [0D3437E666](<Server/Dell/PowerEdge/PowerEdge T110/E57797C8A6CF/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/0D3437E666>) |
| 14e4:165f | 1028:08ff | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 7     | tg3        | [E02734E72E](<Server/Dell/PowerEdge/PowerEdge R750/369267D116AD/UBUNTU-20.04/5.4.0-137-GENERIC/X86_64/E02734E72E>) |
| 14e4:168a | 1028:1f5c | Broadcom         | NetXtreme II BCM57800 1/10 Gigabi... | 7     | bnx2x      | [6A0AF69B4A](<Server/Dell/PowerEdge/PowerEdge R720/F424DE07066D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6A0AF69B4A>) |
| 14e4:168a | 1028:1f67 | Broadcom         | NetXtreme II BCM57800 1/10 Gigabi... | 7     | bnx2x      | [6A0AF69B4A](<Server/Dell/PowerEdge/PowerEdge R720/F424DE07066D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6A0AF69B4A>) |
| 8086:10fb | 8086:000c | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 7     | ixgbe      | [457ABEF5D3](<Server/ASRockRack/ROMED8/ROMED8-2T/E9A31A87AD3F/ALMA-9.1/6.3.0-2.EL9.ELREPO.X86_64/X86_64/457ABEF5D3>) |
| 8086:1533 | 8086:0001 | Intel            | I210 Gigabit Network Connection      | 7     | igb        | [962B265260](<Server/Dell/Precision/Precision 7920 Tower/8C7F63FF0FE0/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/962B265260>) |
| 8086:1572 | 8086:0001 | Intel            | Ethernet Controller X710 for 10Gb... | 7     | i40e       | [928EE22E71](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 -[7X06CTO1WW]-/5D8AB08CFEB3/CENTOS-7/3.10.0-1160.21.1.EL7.X86_64/X86_64/928EE22E71>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2723 | 8086:0084 | Intel            | Wi-Fi 6 AX200                        | 9     | iwlwifi    | [AA477C51A8](<Server/Supermicro/X10/X10SL7-F/41DE1FB76B4E/UBUNTU-20.04/5.16.0-051600-GENERIC/X86_64/AA477C51A8>) |
| 14c3:0608 | 14c3:0608 | MediaTek         | MT7921K (RZ608) Wi-Fi 6E 80MHz       | 4     | mt7921e    | [6A0AF69B4A](<Server/Dell/PowerEdge/PowerEdge R720/F424DE07066D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6A0AF69B4A>) |
| 14e4:43a0 | 14e4:0619 | Broadcom         | BCM4360 802.11ac Wireless Network... | 3     | wl         | [A0623DC5A7](<Server/Dell/Precision/Precision 7820 Tower/70D486E7A18E/UBUNTU-22.10/5.19.0-40-GENERIC/X86_64/A0623DC5A7>) |
| 168c:003e | 168c:3360 | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 3     | ath10k_pci | [0600880DBA](<Server/ECS/LIVA/LIVA Q2/51AFACC4D80B/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/0600880DBA>) |
| 8086:24fd | 8086:0010 | Intel            | Wireless 8265 / 8275                 | 3     | iwlwifi    | [1D6082EFE8](<Server/Lenovo/ThinkStation/ThinkStation P720 30BBS21C01/FE8DF4F9C290/FEDORA-37/6.2.11-200.FC37.X86_64/X86_64/1D6082EFE8>) |
| 8086:2526 | 8086:0014 | Intel            | Wireless-AC 9260                     | 3     | iwlwifi    | [BD3C9AA4FD](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/533FA109A252/ARCH-ROLLING/6.1.4-ARCH1-1/X86_64/BD3C9AA4FD>) |
| 8086:2725 | 8086:0024 | Intel            | Wi-Fi 6 AX210/AX211/AX411 160MHz     | 3     | iwlwifi    | [5C00E2D415](<Server/Intel/S5520/S5520HC/42DF18E9A677/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/5C00E2D415>) |
| 8086:a370 | 8086:0034 | Intel            | Cannon Lake PCH CNVi WiFi            | 3     | iwlwifi    | [8648FC0825](<Server/Supermicro/C9/C9Z390-CG-IW/64D15818D339/UBUNTU-22.04/5.15.0-30-GENERIC/X86_64/8648FC0825>) |
| 10ec:8812 | 10ec:8203 | Realtek Semic... | RTL8812AE 802.11ac PCIe Wireless ... | 2     | rtl8821ae  | [4B0CFEC9A7](<Server/Supermicro/X10/X10SAE/FF0B31A8C494/NOBARA-37/6.2.10-200.FSYNC.FC37.X86_64/X86_64/4B0CFEC9A7>) |
| 10ec:8812 | 10ec:8812 | Realtek Semic... | RTL8812AE 802.11ac PCIe Wireless ... | 2     | rtl8821ae  | [FE6DC0D9C7](<Server/Dell/Precision/Precision 7820 Tower/FB09ECB98D56/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FE6DC0D9C7>) |
| 168c:002e | 168c:30a4 | Qualcomm Atheros | AR9287 Wireless Network Adapter (... | 2     | ath9k      | [4689CAC5C7](<Server/Dell/PowerEdge/PowerEdge T130/7304C0B78510/POP!_OS-22.04/5.19.0-76051900-GENERIC/X86_64/4689CAC5C7>) |
| 8086:095a | 8086:9010 | Intel            | Wireless 7265                        | 2     | iwlwifi    | [0D27879BB6](<Server/GEEKOM/MiniAir/MiniAir 11/696C922FC5EB/OPENMANDRIVA-4.3/5.16.13-DESKTOP-1OMV4003/X86_64/0D27879BB6>) |
| 8086:24fd | 8086:0050 | Intel            | Wireless 8265 / 8275                 | 2     | iwlwifi    | [DB5C0DD7B2](<Server/Dell/Precision/Precision 7820 Tower/97883BD78AD3/POP!_OS-22.04/6.1.0-1006-OEM/X86_64/DB5C0DD7B2>) |
| 10ec:8179 | 10ec:8197 | Realtek Semic... | RTL8188EE Wireless Network Adapter   | 1     | rtl8188ee  | [CDFBA65630](<Server/Intel/S2600/S2600CP/5F463C4DAE95/UBUNTU-22.04/5.15.0-23-GENERIC/X86_64/CDFBA65630>) |
| 10ec:b822 | 1a3b:2951 | Realtek Semic... | RTL8822BE 802.11a/b/g/n/ac WiFi a... | 1     | rtw88_8... | [5145E7D26E](<Server/Supermicro/C7/C7Z370-CG-IW/66BE2E39DAA0/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/5145E7D26E>) |
| 14e4:43ba | 106b:0133 | Broadcom         | BCM43602 802.11ac Wireless LAN SoC   | 1     | brcmfmac   | [FC1F78ADA0](<Server/Supermicro/Super/Super Server/C97C65EAC5E2/UBUNTU-20.04/5.4.0-40-GENERIC/X86_64/FC1F78ADA0>) |
| 168c:0013 | 1186:3a73 | Qualcomm Atheros | AR5212/5213/2414 Wireless Network... | 1     | ath5k      | [8F945E0A15](<Server/Supermicro/X8/X8DTL/7581500BE1DB/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/8F945E0A15>) |
| 168c:0013 | 168c:2051 | Qualcomm Atheros | AR5212/5213/2414 Wireless Network... | 1     | ath5k      | [FE3D758C20](<Server/Intel/S5500/S5500BC/EB1E1FCFB3A4/KDE-NEON-20.04/5.4.0-66-GENERIC/X86_64/FE3D758C20>) |
| 168c:001d | 1113:b203 | Qualcomm Atheros | AR2417 Wireless Network Adapter [... | 1     | ath5k      | [EF95821AFC](<Server/Supermicro/X10/X10SAE/233AFEE2447E/UBUNTU-MATE-20.04/5.4.0-52-GENERIC/X86_64/EF95821AFC>) |
| 168c:001d | 168c:2055 | Qualcomm Atheros | AR2417 Wireless Network Adapter [... | 1     | ath5k      | [16BEFD9DC3](<Server/Supermicro/X10/X10SAE/233AFEE2447E/OPENSUSE-TUMBLEWEED-XXXXXXXX/5.11.4-1-DEFAULT/X86_64/16BEFD9DC3>) |
| 168c:0030 | 168c:3112 | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 1     | ath9k      | [B9AC0D657E](<Server/Supermicro/A1/A1SRM-2558F/DAF42406F667/FEDORA-32/5.8.16-200.FC32.X86_64/X86_64/B9AC0D657E>) |
| 168c:0030 | 168c:3116 | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 1     | ath9k      | [D52E0ED118](<Server/Neousys Technology/Nuvo-7000/Nuvo-7000 Series/55C9FBF8C557/UBUNTU-20.04/5.13.0-37-GENERIC/X86_64/D52E0ED118>) |
| 168c:0032 | 168c:3118 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 1     | ath9k      | [E70645D3E6](<Server/Intel/W2600/W2600CR/5A75A85091D9/UBUNTU-20.04/5.4.0-80-GENERIC/X86_64/E70645D3E6>) |
| 168c:0034 | 105b:e058 | Qualcomm Atheros | AR9462 Wireless Network Adapter      | 1     | ath9k      | [676C3ECA96](<Server/Intel/S5520/S5520HC/4D880C0CBA79/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/676C3ECA96>) |
| 168c:0036 | 103c:18e3 | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 1     | ath9k      | [6D994999C9](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G7/A848C0BF3086/ROCKY-9.0/5.14.0-70.17.1.EL9_0.X86_64/X86_64/6D994999C9>) |
| 1814:0301 | 1737:0055 | Ralink           | RT2561/RT61 802.11g PCI              | 1     | rt61pci    | [5600070A23](<Server/ASUSTek Computer/Z9PA-U8/Z9PA-U8 Series/ACAF72B240BB/UBUNTU-18.04/5.4.0-48-GENERIC/X86_64/5600070A23>) |
| 1814:5392 | 1186:3c06 | Ralink           | RT5392 PCIe Wireless Network Adapter | 1     | rt2800pci  | [E24D0E827B](<Server/Dell/PowerEdge/PowerEdge T110 II/C9588E9ACEC9/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/E24D0E827B>) |
| 8086:08b1 | 8086:4470 | Intel            | Wireless 7260                        | 1     | iwlwifi    | [B8FFB92409](<Server/Neousys Technology/Nuvo-8108GC/Nuvo-8108GC Series/0E8814EA22E8/UBUNTU-18.04/5.4.0-56-GENERIC/X86_64/B8FFB92409>) |
| 8086:08b1 | 8086:c070 | Intel            | Wireless 7260                        | 1     | iwlwifi    | [026B32269E](<Server/ASUSTek Computer/Z9PE-D8/Z9PE-D8 WS/F5006016F49C/CENTOS-8/4.18.0-193.28.1.EL8_2.X86_64/X86_64/026B32269E>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 1     | iwlwifi    | [377C88D227](<Server/Intel/S2600/S2600CO/CF676281389E/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/377C88D227>) |
| 8086:24fb | 8086:2110 | Intel            | Dual Band Wireless-AC 3168NGW [St... | 1     | iwlwifi    | [A99D672930](<Server/ZMY/D/D1500/8AAB60D58948/UBUNTU-22.04/5.15.0-47-GENERIC/X86_64/A99D672930>) |
| 8086:2725 | 8086:0020 | Intel            | Wi-Fi 6 AX210/AX211/AX411 160MHz     | 1     | iwlwifi    | [517DA38F28](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/283652467D28/DEBIAN-11/5.19.17-2-PVE/X86_64/517DA38F28>) |
| 8086:3165 | 8086:8010 | Intel            | Wireless 3165                        | 1     | iwlwifi    | [F5A2B2DE44](<Server/GEEKOM/MiniAir/MiniAir 11/A07BDBCD0072/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/F5A2B2DE44>) |
| 8086:a370 | 8086:0030 | Intel            | Cannon Lake PCH CNVi WiFi            | 1     | iwlwifi    | [065427C37F](<Server/Supermicro/Super/Super Server/2CF7574245C0/DEBIAN-11/5.10.162-1.LAT5.10.0-21/X86_64/065427C37F>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1533 | 15d9:1533 | Intel            | I210 Gigabit Network Connection      | 126   | igb        | [A3F043A03C](<Server/Supermicro/M12/M12SWA-TF/4F883AA311F8/UBUNTU-22.04/5.15.0-33-GENERIC/X86_64/A3F043A03C>) |
| 8086:1521 | 15d9:1521 | Intel            | I350 Gigabit Network Connection      | 99    | igb        | [6994C89077](<Server/Supermicro/X9/X9DRW/6A1A83EBE660/DEBIAN-11/5.15.104-1-PVE/X86_64/6994C89077>) |
| 8086:10d3 | 15d9:10d3 | Intel            | 82574L Gigabit Network Connection    | 31    | e1000e     | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:10d3 | 1043:8369 | Intel            | 82574L Gigabit Network Connection    | 29    | e1000e     | [4AC44C74A3](<Server/ASUSTek Computer/Z9PA-D8/Z9PA-D8 Series/0BE952D59456/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/4AC44C74A3>) |
| 8086:1533 | 1043:8557 | Intel            | I210 Gigabit Network Connection      | 26    | igb        | [44B55B4721](<Server/ASUSTek Computer/P9D-M/P9D-M Series/61497326D129/MANJARO/5.15.108-1-MANJARO/X86_64/44B55B4721>) |
| 8086:10c9 | 15d9:10c9 | Intel            | 82576 Gigabit Network Connection     | 24    | igb        | [EF32C0C2CA](<Server/Supermicro/H8/H8DG6-H8DGi/8E20B1D3526C/UBUNTU-18.04/4.15.0-200-GENERIC/X86_64/EF32C0C2CA>) |
| 8086:1533 | ffff:0000 | Intel            | I210 Gigabit Network Connection      | 24    | igb        | [18B2BF9FF4](<Server/Delta Computers/DSS-C621/DSS-C621LTG/EA1701537BF7/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/18B2BF9FF4>) |
| 8086:1521 | 1028:1f60 | Intel            | I350 Gigabit Network Connection      | 23    | igb        | [BE75097D0F](<Server/Dell/PowerEdge/PowerEdge R730/E686E52F7B47/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/BE75097D0F>) |
| 8086:1533 | 1028:0619 | Intel            | I210 Gigabit Network Connection      | 20    | igb        | [962B265260](<Server/Dell/Precision/Precision 7920 Tower/8C7F63FF0FE0/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/962B265260>) |
| 8086:10d3 | 8086:0000 | Intel            | 82574L Gigabit Network Connection    | 13    | e1000e     | [844D96FCD7](<Server/TYAN Computer/S/S7025/65136A7FAD48/GENTOO-2.8/5.18.12-GENTOO-X86_64/X86_64/844D96FCD7>) |
| 8086:10d3 | 15d9:0000 | Intel            | 82574L Gigabit Network Connection    | 11    | e1000e     | [EEF379BEE2](<Server/Supermicro/X9/X9SRL-F/CC3074F1C867/ROSA-12.3/5.15.79-GENERIC-1ROSA2021.1-X86_64/X86_64/EEF379BEE2>) |
| 1077:8020 | 103c:3733 | QLogic           | cLOM8214 1/10GbE Controller          | 10    | qlcnic     | [A9289CA04C](<Server/IBM/System/System x3650 M3 -[794562M]-/70C4A6EC4717/ARCH-ROLLING/5.18.6-ARCH1-1/X86_64/A9289CA04C>) |
| 8086:10c9 | 15d9:ab11 | Intel            | 82576 Gigabit Network Connection     | 10    | igb        | [E673BAB21F](<Server/Supermicro/H8/H8QG6/539918058863/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/E673BAB21F>) |
| 8086:10d3 | 8086:3578 | Intel            | 82574L Gigabit Network Connection    | 10    | e1000e     | [891709C211](<Server/Intel/S1200/S1200BTL/F40AFD7A2D8F/FEDORA-36/6.2.8-100.FC36.X86_64/X86_64/891709C211>) |
| 8086:1502 | 8086:3578 | Intel            | 82579LM Gigabit Network Connectio... | 10    | e1000e     | [891709C211](<Server/Intel/S1200/S1200BTL/F40AFD7A2D8F/FEDORA-36/6.2.8-100.FC36.X86_64/X86_64/891709C211>) |
| 8086:10a7 | 8086:34dc | Intel            | 82575EB Gigabit Network Connection   | 9     | igb        | [5C00E2D415](<Server/Intel/S5520/S5520HC/42DF18E9A677/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/5C00E2D415>) |
| 8086:10c9 | 103c:323f | Intel            | 82576 Gigabit Network Connection     | 9     | igb        | [3955B91269](<Server/Hewlett-Packard/ProLiant/ProLiant DL165 G7/1979FBF2D488/DEBIAN-11/5.15.39-4-PVE/X86_64/3955B91269>) |
| 8086:10c9 | 15d9:0100 | Intel            | 82576 Gigabit Network Connection     | 9     | igb        | [71610CE997](<Server/Supermicro/X8/X8DAH/6A1E9F33BACC/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/71610CE997>) |
| 8086:1533 | 8086:35b4 | Intel            | I210 Gigabit Network Connection      | 9     | igb        | [28F4CEB8EE](<Server/Intel/S1200/S1200RP/FB9A925E61E5/ARCH-ROLLING/5.19.13-ARCH1-1/X86_64/28F4CEB8EE>) |
| 8086:10d3 | 1734:1192 | Intel            | 82574L Gigabit Network Connection    | 8     | e1000e     | [C4C0B53877](<Server/Fujitsu/PRIMERGY/PRIMERGY TX150 S7/4BE064DA92A3/OL-9.0/5.15.0-0.30.19.EL9UEK.X86_64/X86_64/C4C0B53877>) |
| 8086:1521 | 8086:1521 | Intel            | I350 Gigabit Network Connection      | 8     | igb        | [F2D1382390](<Server/IBM/System/System x3650 M4: -[2145DH8]-/453EF656FB54/ARCH-ROLLING/5.19.12-ARCH1-1/X86_64/F2D1382390>) |
| 8086:1521 | ffff:0000 | Intel            | I350 Gigabit Network Connection      | 8     | igb        | [8619E38037](<Server/Gigabyte Technology/E252/E252-P30-00/513B50B63035/UBUNTU-20.04/5.4.0-145-GENERIC/AARCH64/8619E38037>) |
| 15b3:1013 | 15b3:0010 | Mellanox Tech... | MT27700 Family [ConnectX-4]          | 7     | mlx5_core  | [83FF998A9A](<Server/Supermicro/AS/AS -1014S-WTRT/153A09726ED2/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/83FF998A9A>) |
| 8086:10bd | 8086:34d0 | Intel            | 82566DM-2 Gigabit Network Connection | 7     | e1000e     | [40FC7CD8AA](<Server/Intel/S3210/S3210SH/D6FE7FA8CA14/DEBIAN-11/5.15.30-2-PVE/X86_64/40FC7CD8AA>) |
| 8086:1502 | 15d9:0623 | Intel            | 82579LM Gigabit Network Connectio... | 7     | e1000e     | [2E9D55D3A7](<Server/Supermicro/X9/X9SRA-X9SRA-3/E73ED86A7227/DEBIAN-11/5.10.0-14-AMD64/X86_64/2E9D55D3A7>) |
| 8086:1521 | 15d9:0656 | Intel            | I350 Gigabit Network Connection      | 7     | igb        | [8619E38037](<Server/Gigabyte Technology/E252/E252-P30-00/513B50B63035/UBUNTU-20.04/5.4.0-145-GENERIC/AARCH64/8619E38037>) |
| 8086:10cc | 8086:34da | Intel            | 82567LM-2 Gigabit Network Connection | 6     | e1000e     | [94527A8584](<Server/Intel/S5500/S5500BC/A12E8B03104E/LINUXMINT-19.3/5.4.0-148-GENERIC/X86_64/94527A8584>) |
| 8086:10d3 | 8086:34da | Intel            | 82574L Gigabit Network Connection    | 6     | e1000e     | [94527A8584](<Server/Intel/S5500/S5500BC/A12E8B03104E/LINUXMINT-19.3/5.4.0-148-GENERIC/X86_64/94527A8584>) |
| 8086:10d3 | 8086:a01f | Intel            | 82574L Gigabit Network Connection    | 6     | e1000e     | [CE6BAA4FDA](<Server/Supermicro/Super/Super Server/A842905AAA3B/UBUNTU-18.04/5.4.0-132-GENERIC/X86_64/CE6BAA4FDA>) |
| 10df:0720 | 10df:e863 | Emulex           | OneConnect NIC (Skyhawk)             | 5     | be2net     | [B0100C59BB](<Server/Supermicro/Super/Super Server/E58401D9CAE3/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/B0100C59BB>) |
| 4040:0100 | 103c:705a | NetXen Incorp... | NX3031 Multifunction 1/10-Gigabit... | 5     | netxen_nic | [1DBD0517E3](<Server/Hewlett-Packard/ProLiant/ProLiant DL585 G7/0239B15EF9C8/DEBIAN-11/5.10.0-16-AMD64/X86_64/1DBD0517E3>) |
| 8086:10a7 | 8086:34e2 | Intel            | 82575EB Gigabit Network Connection   | 5     | igb        | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:10c9 | 10f1:7012 | Intel            | 82576 Gigabit Network Connection     | 5     | igb        | [5B5D81B1A8](<Server/TYAN Computer/S/S7012/4A43E21507D4/FEDORA-37/6.0.8-300.FC37.X86_64/X86_64/5B5D81B1A8>) |
| 8086:10c9 | 15d9:0600 | Intel            | 82576 Gigabit Network Connection     | 5     | igb        | [6012DE6351](<Server/Supermicro/X8/X8DTU/17EEEE82432B/LINUXMINT-20.2/5.4.0-131-GENERIC/X86_64/6012DE6351>) |
| 8086:10c9 | 15d9:060f | Intel            | 82576 Gigabit Network Connection     | 5     | igb        | [57D3FB0A5D](<Server/Supermicro/X8/X8DTN+-F/963C16CF4315/DEBIAN-9/5.19.0-2-AMD64/X86_64/57D3FB0A5D>) |
| 8086:10d3 | 8086:34ec | Intel            | 82574L Gigabit Network Connection    | 5     | e1000e     | [E61EBB59C3](<Server/Intel/S3420/S3420GP/8F1F72982A9D/LINUXMINT-20.3/5.4.0-105-GENERIC/X86_64/E61EBB59C3>) |
| 8086:10ef | 8086:34ec | Intel            | 82578DM Gigabit Network Connection   | 5     | e1000e     | [E61EBB59C3](<Server/Intel/S3420/S3420GP/8F1F72982A9D/LINUXMINT-20.3/5.4.0-105-GENERIC/X86_64/E61EBB59C3>) |
| 8086:10fb | 15d9:0611 | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 5     | ixgbe      | [AFAB4598A7](<Server/ASUSTek Computer/ESC4000/ESC4000 G4/E6BBA8966F48/UBUNTU-18.04/4.15.0-140-GENERIC/X86_64/AFAB4598A7>) |
| 8086:1521 | 1458:0000 | Intel            | I350 Gigabit Network Connection      | 5     | igb        | [3E6B182473](<Server/Gigabyte Technology/R182/R182-Z91-00/C0D8E0800C76/UBUNTU-22.04/5.15.0-70-GENERIC/X86_64/3E6B182473>) |
| 8086:1521 | 8086:357e | Intel            | I350 Gigabit Network Connection      | 5     | igb        | [CDFBA65630](<Server/Intel/S2600/S2600CP/5F463C4DAE95/UBUNTU-22.04/5.15.0-23-GENERIC/X86_64/CDFBA65630>) |
| 8086:1533 | 1458:0000 | Intel            | I210 Gigabit Network Connection      | 5     | igb        | [92BFF0D0AC](<Server/Gigabyte Technology/GA-6/GA-6LXSG/539D984915EE/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/92BFF0D0AC>) |
| 10de:0373 | 1462:cb84 | Nvidia           | MCP55 Ethernet                       | 4     | forcedeth  | [1888FA6DF7](<Server/MSI/MCP/MCP55/E26C4EDDD3C1/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/1888FA6DF7>) |
| 15b3:1003 | 15b3:0050 | Mellanox Tech... | MT27500 Family [ConnectX-3]          | 4     | mlx4_core  | [19FDDB0A01](<Server/Supermicro/AS/AS -1014S-WTRT/D80A1900B9F1/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/19FDDB0A01>) |
| 15b3:1003 | 15b3:0090 | Mellanox Tech... | MT27500 Family [ConnectX-3]          | 4     | mlx4_core  | [2BB4102B1C](<Server/Supermicro/Super/Super Server/45717F18B5CF/CENTOS-8/4.18.0-240.22.1.EL8_3.X86_64/X86_64/2BB4102B1C>) |
| 15b3:6750 | 15b3:0015 | Mellanox Tech... | MT26448 [ConnectX EN 10GigE, PCIe... | 4     | mlx4_core  | [6E08BAAB68](<Server/Supermicro/X8/X8DT6/6ED912FEA9B2/DEBIAN-11/5.15.83-1-PVE/X86_64/6E08BAAB68>) |
| 8086:10c9 | 15d9:0400 | Intel            | 82576 Gigabit Network Connection     | 4     | igb        | [AD4ABE60CD](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/03637143A526/XUBUNTU-20.04/5.11.0-37-GENERIC/X86_64/AD4ABE60CD>) |
| 8086:10d3 | 1014:03bd | Intel            | 82574L Gigabit Network Connection    | 4     | e1000e     | [B1AB802CB1](<Server/IBM/System/System x3250 M3 -[4252PAW]-/DE8F12F20151/DEBIAN-11/5.15.30-2-PVE/X86_64/B1AB802CB1>) |
| 8086:10d3 | 10f1:7012 | Intel            | 82574L Gigabit Network Connection    | 4     | e1000e     | [5B5D81B1A8](<Server/TYAN Computer/S/S7012/4A43E21507D4/FEDORA-37/6.0.8-300.FC37.X86_64/X86_64/5B5D81B1A8>) |
| 8086:1502 | 1734:11b7 | Intel            | 82579LM Gigabit Network Connectio... | 4     | e1000e     | [8CF8F98A53](<Server/Fujitsu/PRIMERGY/PRIMERGY/41B1E7A57925/FEDORA-35/5.14.10-300.FC35.X86_64/X86_64/8CF8F98A53>) |
| 8086:1521 | 1028:1f73 | Intel            | I350 Gigabit Network Connection      | 4     | igb        | [698093BBC6](<Server/Dell/PowerEdge/PowerEdge R630/26C95AC2FC26/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/698093BBC6>) |

### Network and computing encryption device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19e5:a255 |           | Huawei Techno... | HiSilicon SEC Engine                 | 1     |            | [63BDABB5A4](<Server/HUAWEI/TaiShan/TaiShan 2280 V2/2603C7B2E57E/CENTOS-7/4.18.0-147.0.3.EL7.AARCH64/AARCH64/63BDABB5A4>) |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1485 | 1022:1485 | AMD              | Starship/Matisse Reserved SPP        | 41    |            | [55AF41B298](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.7/4.18.0-425.19.2.EL8_7.X86_64/X86_64/55AF41B298>) |
| 1022:148a | 1022:148a | AMD              | Starship/Matisse PCIe Dummy Function | 41    |            | [55AF41B298](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.7/4.18.0-425.19.2.EL8_7.X86_64/X86_64/55AF41B298>) |
| 8086:3456 |           | Intel            | Ice Lake NorthPeak                   | 18    |            | [74466AD718](<Server/HPE/ProLiant/ProLiant DL360 Gen10 Plus/6004A3CDB655/DEBIAN-11/5.15.107-1-PVE/X86_64/74466AD718>) |
| 1022:1485 | 1028:08fc | AMD              | Starship/Matisse Reserved SPP        | 8     |            | [237A3CD682](<Server/Dell/PowerEdge/PowerEdge R6515/647C815644AA/DEBIAN-12/6.1.0-5-AMD64/X86_64/237A3CD682>) |
| 1022:1485 | 1458:1000 | AMD              | Starship/Matisse Reserved SPP        | 8     |            | [DEF4067C8E](<Server/Gigabyte Technology/G242/G242-Z11-00/B5251D581093/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/DEF4067C8E>) |
| 1022:148a | 1028:08fc | AMD              | Starship/Matisse PCIe Dummy Function | 8     |            | [237A3CD682](<Server/Dell/PowerEdge/PowerEdge R6515/647C815644AA/DEBIAN-12/6.1.0-5-AMD64/X86_64/237A3CD682>) |
| 1022:148a | 1458:1000 | AMD              | Starship/Matisse PCIe Dummy Function | 8     |            | [DEF4067C8E](<Server/Gigabyte Technology/G242/G242-Z11-00/B5251D581093/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/DEF4067C8E>) |
| 1022:1455 | 1022:1455 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 7     |            | [89E91928BB](<Server/Supermicro/Super/Super Server/ECB64B8152DF/DEBIAN-11/6.2.6-1-PVE/X86_64/89E91928BB>) |
| 1022:145a | 1022:145a | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 7     |            | [89E91928BB](<Server/Supermicro/Super/Super Server/ECB64B8152DF/DEBIAN-11/6.2.6-1-PVE/X86_64/89E91928BB>) |
| 1022:1485 | 1028:08ff | AMD              | Starship/Matisse Reserved SPP        | 6     |            | [77F946C99B](<Server/Dell/PowerEdge/PowerEdge R7525/ED52A1D54F9D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/77F946C99B>) |
| 1022:148a | 1028:08ff | AMD              | Starship/Matisse PCIe Dummy Function | 6     |            | [77F946C99B](<Server/Dell/PowerEdge/PowerEdge R7525/ED52A1D54F9D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/77F946C99B>) |
| 8086:a126 |           | Intel            | 100 Series/C230 Series Chipset Fa... | 5     | intel_t... | [BBD0BE963A](<Server/HPE/ML10/ML10Gen9/06A38AE11D38/UBUNTU-20.04/5.15.0-48-GENERIC/X86_64/BBD0BE963A>) |
| 1022:1485 | 1028:08fd | AMD              | Starship/Matisse Reserved SPP        | 3     |            | [F0B9CD86EF](<Server/Dell/PowerEdge/PowerEdge R7515/723F15A8AB49/UBUNTU-22.04/5.15.0-47-GENERIC/X86_64/F0B9CD86EF>) |
| 1022:148a | 1028:08fd | AMD              | Starship/Matisse PCIe Dummy Function | 3     |            | [F0B9CD86EF](<Server/Dell/PowerEdge/PowerEdge R7515/723F15A8AB49/UBUNTU-22.04/5.15.0-47-GENERIC/X86_64/F0B9CD86EF>) |
| 1022:1455 | 1458:1000 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 2     |            | [6D486A7EE9](<Server/Gigabyte Technology/MZ31/MZ31-AR0-00/20445DA51E24/UBUNTU-20.04/5.6.0-1048-OEM/X86_64/6D486A7EE9>) |
| 1022:145a | 1458:1000 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 2     |            | [6D486A7EE9](<Server/Gigabyte Technology/MZ31/MZ31-AR0-00/20445DA51E24/UBUNTU-20.04/5.6.0-1048-OEM/X86_64/6D486A7EE9>) |
| 8086:3456 | 17aa:7811 | Intel            | Ice Lake NorthPeak                   | 2     |            | [29F89998EE](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 V2/D65FD98664FE/DEBIAN-11/5.10.0-20-AMD64/X86_64/29F89998EE>) |
| 1022:1455 | 1028:07f9 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 1     |            | [8F7FF50C55](<Server/Dell/PowerEdge/PowerEdge R7425/EEF1E1F22650/OPENSUSE-LEAP-15.1/4.12.14-LP151.28.13-DEFAULT/X86_64/8F7FF50C55>) |
| 1022:145a | 1028:07f9 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 1     |            | [8F7FF50C55](<Server/Dell/PowerEdge/PowerEdge R7425/EEF1E1F22650/OPENSUSE-LEAP-15.1/4.12.14-LP151.28.13-DEFAULT/X86_64/8F7FF50C55>) |
| 1022:1485 | 1028:0900 | AMD              | Starship/Matisse Reserved SPP        | 1     |            | [382F999542](<Server/Dell/PowerEdge/PowerEdge C6525/B11FEC7694D8/ARCH/5.15.59-1-LTS/X86_64/382F999542>) |
| 1022:1485 | 1849:1485 | AMD              | Starship/Matisse Reserved SPP        | 1     |            | [3C11A0856C](<Server/ASRockRack/ROMED8/ROMED8-2T/9F9114A5632E/DEBIAN-10/5.8.0-0.BPO.2-AMD64/X86_64/3C11A0856C>) |
| 1022:148a | 1028:0900 | AMD              | Starship/Matisse PCIe Dummy Function | 1     |            | [382F999542](<Server/Dell/PowerEdge/PowerEdge C6525/B11FEC7694D8/ARCH/5.15.59-1-LTS/X86_64/382F999542>) |
| 1022:14ac | 1022:14ac | AMD              | Genoa PCIe Dummy Function            | 1     |            | [B7E67F8130](<Server/AMD/Volcano/Volcano/59C634EF9C63/DEBIAN-11/5.10.0-21-AMD64/X86_64/B7E67F8130>) |
| 1022:14de | 1458:1000 | AMD              | Family 19h PCIe Dummy Function Co... | 1     |            | [7BA797B6A5](<Server/Giga Computing/MC13/MC13-LE0-000/1D7046547004/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/7BA797B6A5>) |
| 8086:18e1 | 15d9:1c18 | Intel            | Cedar Fork Northpeak                 | 1     | intel_t... | [3751D50DDE](<Server/Supermicro/Super/Super Server/ACFD57B232A4/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/3751D50DDE>) |
| 8086:3456 | 1458:1000 | Intel            | Ice Lake NorthPeak                   | 1     |            | [AB729DC8A5](<Server/Gigabyte Technology/MU72/MU72-SU0-00/972D51B2901F/RHEL-9/5.14.0-70.17.1.EL9_0.X86_64/X86_64/AB729DC8A5>) |
| 8086:3456 | 17aa:7810 | Intel            | Ice Lake NorthPeak                   | 1     |            | [FF6113B91D](<Server/Lenovo/ThinkSystem/ThinkSystem SR630 V2/ECB5C724E79D/CENTOS-7/3.10.0-1160.49.1.EL7.X86_64/X86_64/FF6113B91D>) |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a135 | 15d9:089a | Intel            | 100 Series/C230 Series Chipset Fa... | 8     | intel_i... | [7AA0EB0936](<Server/Supermicro/Super/Super Server/7660AB944FAA/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/7AA0EB0936>) |
| 8086:a135 | 15d9:0884 | Intel            | 100 Series/C230 Series Chipset Fa... | 3     | intel_i... | [A65A6E89D1](<Server/Thomas-Krenn.AG/Super/Super Server/05511CFA9691/FEDORA-37/6.0.9-300.FC37.X86_64/X86_64/A65A6E89D1>) |
| 8086:a135 | 15d9:0896 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | intel_i... | [B0100C59BB](<Server/Supermicro/Super/Super Server/E58401D9CAE3/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/B0100C59BB>) |
| 1b94:c156 | 1b94:c156 | Signatec / Dy... |                                      | 1     |            | [B3C09674CF](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/31A946D98462/UBUNTU-18.04/4.15.0-142-GENERIC/X86_64/B3C09674CF>) |
| 8086:a135 | 15d9:0885 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | intel_i... | [50169A0FFB](<Server/Supermicro/Super/Super Server/866C451F74FD/LINUXMINT-20/5.4.0-26-GENERIC/X86_64/50169A0FFB>) |

### Parallel controller (ecp) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1415:9513 | 1415:9513 | Oxford Semico... | OX16PCI954 (Quad 16950 UART) func... | 1     | parport_pc | [2E9D55D3A7](<Server/Supermicro/X9/X9SRA-X9SRA-3/E73ED86A7227/DEBIAN-11/5.10.0-14-AMD64/X86_64/2E9D55D3A7>) |

### Parallel controller (ieee1284) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 9710:9865 | a000:2000 | MosChip Semic... | PCI 9865 Multi-I/O Controller        | 1     | parport_pc | [715B40D8B6](<Server/Intel/S5000/S5000XVN/187007C30239/FEDORA-34/5.14.12-200.FC34.X86_64/X86_64/715B40D8B6>) |

### Performance counters (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:204c | 8086:0000 | Intel            | Sky Lake-E M3KTI Registers           | 199   | skx_uncore | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:204d | 8086:0000 | Intel            | Sky Lake-E M3KTI Registers           | 199   | skx_uncore | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2015 | 8086:0000 | Intel            | Sky Lake-E Ubox Registers            | 198   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2058 | 8086:0000 | Intel            | Sky Lake-E KTI 0                     | 188   | skx_uncore | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2088 | 8086:0000 | Intel            | Sky Lake-E DDRIO Registers           | 113   | skx_uncore | [962B265260](<Server/Dell/Precision/Precision 7920 Tower/8C7F63FF0FE0/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/962B265260>) |
| 8086:2f30 | 8086:2f30 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 60    | hswep_u... | [AD555BFDE2](<Server/Dell/PowerEdge/PowerEdge T430/F2945010DA0E/ARCH-ROLLING/6.3.0-273-TKG-PDS-LLVM/X86_64/AD555BFDE2>) |
| 8086:2f34 | 8086:2f34 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 PCI... | 60    | hswep_u... | [AD555BFDE2](<Server/Dell/PowerEdge/PowerEdge T430/F2945010DA0E/ARCH-ROLLING/6.3.0-273-TKG-PDS-LLVM/X86_64/AD555BFDE2>) |
| 8086:2f36 | 8086:2f36 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 60    | hswep_u... | [AD555BFDE2](<Server/Dell/PowerEdge/PowerEdge T430/F2945010DA0E/ARCH-ROLLING/6.3.0-273-TKG-PDS-LLVM/X86_64/AD555BFDE2>) |
| 8086:2f37 | 8086:2f37 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 60    | hswep_u... | [AD555BFDE2](<Server/Dell/PowerEdge/PowerEdge T430/F2945010DA0E/ARCH-ROLLING/6.3.0-273-TKG-PDS-LLVM/X86_64/AD555BFDE2>) |
| 8086:2f7d | 8086:2f7d | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 60    |            | [AD555BFDE2](<Server/Dell/PowerEdge/PowerEdge T430/F2945010DA0E/ARCH-ROLLING/6.3.0-273-TKG-PDS-LLVM/X86_64/AD555BFDE2>) |
| 8086:3c43 | 103c:18a8 | Intel            | Xeon E5/Core i7 Ring to PCI Expre... | 45    | snbep_u... | [961A066E6B](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/F726BB41B090/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/961A066E6B>) |
| 8086:3c44 | 103c:18a8 | Intel            | Xeon E5/Core i7 Ring to QuickPath... | 45    | snbep_u... | [961A066E6B](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/F726BB41B090/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/961A066E6B>) |
| 8086:3c46 | 103c:18a8 | Intel            | Xeon E5/Core i7 Processor Home Ag... | 45    | snbep_u... | [961A066E6B](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/F726BB41B090/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/961A066E6B>) |
| 8086:3ce6 | 103c:18a8 | Intel            | Xeon E5/Core i7 QuickPath Interco... | 45    |            | [961A066E6B](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/F726BB41B090/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/961A066E6B>) |
| 8086:6f30 | 8086:6f30 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 45    | bdx_uncore | [BAF3069CD7](<Server/Cisco Systems/UCSC-C220/UCSC-C220-M4S/9D3781D2096F/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/BAF3069CD7>) |
| 8086:6f34 | 8086:6f34 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 45    | bdx_uncore | [BAF3069CD7](<Server/Cisco Systems/UCSC-C220/UCSC-C220-M4S/9D3781D2096F/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/BAF3069CD7>) |
| 8086:6f36 | 8086:6f36 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 45    | bdx_uncore | [BAF3069CD7](<Server/Cisco Systems/UCSC-C220/UCSC-C220-M4S/9D3781D2096F/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/BAF3069CD7>) |
| 8086:6f37 | 8086:6f37 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 45    | bdx_uncore | [BAF3069CD7](<Server/Cisco Systems/UCSC-C220/UCSC-C220-M4S/9D3781D2096F/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/BAF3069CD7>) |
| 8086:6f7d | 8086:6f7d | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 45    |            | [BAF3069CD7](<Server/Cisco Systems/UCSC-C220/UCSC-C220-M4S/9D3781D2096F/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/BAF3069CD7>) |
| 8086:2058 |           | Intel            | Sky Lake-E KTI 0                     | 43    | skx_uncore | [0CE29BA75C](<Server/Delta Computers/DSS-C621/DSS-C621LTG/E7DB42D68091/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/0CE29BA75C>) |
| 8086:2f32 | 8086:2f32 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 QPI... | 41    | hswep_u... | [AD555BFDE2](<Server/Dell/PowerEdge/PowerEdge T430/F2945010DA0E/ARCH-ROLLING/6.3.0-273-TKG-PDS-LLVM/X86_64/AD555BFDE2>) |
| 8086:2f33 | 8086:2f33 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 QPI... | 39    | hswep_u... | [AD555BFDE2](<Server/Dell/PowerEdge/PowerEdge T430/F2945010DA0E/ARCH-ROLLING/6.3.0-273-TKG-PDS-LLVM/X86_64/AD555BFDE2>) |
| 8086:2f38 | 8086:2f38 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 23    | hswep_u... | [9BB50174EF](<Server/DALCO/S2600/S2600WTTR/F200B7AE62EB/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/9BB50174EF>) |
| 8086:2880 | 8086:0000 | Intel            | Core i9/Xeon DDRIO Host Config Re... | 22    |            | [74466AD718](<Server/HPE/ProLiant/ProLiant DL360 Gen10 Plus/6004A3CDB655/DEBIAN-11/5.15.107-1-PVE/X86_64/74466AD718>) |
| 8086:0e30 | 103c:18a8 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 20    | ivbep_u... | [C36BF90EFB](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/4BDFA2F6AD42/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/C36BF90EFB>) |
| 8086:0e34 | 103c:18a8 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 20    | ivbep_u... | [C36BF90EFB](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/4BDFA2F6AD42/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/C36BF90EFB>) |
| 8086:0e36 | 103c:18a8 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 20    | ivbep_u... | [C36BF90EFB](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/4BDFA2F6AD42/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/C36BF90EFB>) |
| 8086:344a | 8086:0000 | Intel            | Core i9/Xeon IMC0 Mesh to Mem Reg... | 18    | icx_uncore | [74466AD718](<Server/HPE/ProLiant/ProLiant DL360 Gen10 Plus/6004A3CDB655/DEBIAN-11/5.15.107-1-PVE/X86_64/74466AD718>) |
| 8086:6f32 | 8086:6f32 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 18    | bdx_uncore | [BAF3069CD7](<Server/Cisco Systems/UCSC-C220/UCSC-C220-M4S/9D3781D2096F/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/BAF3069CD7>) |
| 8086:6f33 | 8086:6f33 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 18    | bdx_uncore | [BAF3069CD7](<Server/Cisco Systems/UCSC-C220/UCSC-C220-M4S/9D3781D2096F/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/BAF3069CD7>) |
| 8086:6f30 | 103c:21ea | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 16    | bdx_uncore | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:6f30 | 15d9:0821 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 16    | bdx_uncore | [17BF7A3CBC](<Server/Supermicro/SYS-6018/SYS-6018R-WTR/5EE2BAE645DD/CENTOS-7/3.10.0-862.14.4.EL7.X86_64/X86_64/17BF7A3CBC>) |
| 8086:6f34 | 103c:21ea | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 16    | bdx_uncore | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:6f34 | 15d9:0821 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 16    | bdx_uncore | [17BF7A3CBC](<Server/Supermicro/SYS-6018/SYS-6018R-WTR/5EE2BAE645DD/CENTOS-7/3.10.0-862.14.4.EL7.X86_64/X86_64/17BF7A3CBC>) |
| 8086:6f36 | 103c:21ea | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 16    | bdx_uncore | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:6f36 | 15d9:0821 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 16    | bdx_uncore | [17BF7A3CBC](<Server/Supermicro/SYS-6018/SYS-6018R-WTR/5EE2BAE645DD/CENTOS-7/3.10.0-862.14.4.EL7.X86_64/X86_64/17BF7A3CBC>) |
| 8086:6f37 | 103c:21ea | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 16    | bdx_uncore | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:6f37 | 15d9:0821 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 16    | bdx_uncore | [17BF7A3CBC](<Server/Supermicro/SYS-6018/SYS-6018R-WTR/5EE2BAE645DD/CENTOS-7/3.10.0-862.14.4.EL7.X86_64/X86_64/17BF7A3CBC>) |
| 8086:6f7d | 103c:21ea | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 16    |            | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:6f7d | 15d9:0821 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 16    |            | [17BF7A3CBC](<Server/Supermicro/SYS-6018/SYS-6018R-WTR/5EE2BAE645DD/CENTOS-7/3.10.0-862.14.4.EL7.X86_64/X86_64/17BF7A3CBC>) |
| 8086:6f32 | 15d9:0821 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 15    | bdx_uncore | [17BF7A3CBC](<Server/Supermicro/SYS-6018/SYS-6018R-WTR/5EE2BAE645DD/CENTOS-7/3.10.0-862.14.4.EL7.X86_64/X86_64/17BF7A3CBC>) |
| 8086:6f33 | 15d9:0821 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 15    | bdx_uncore | [17BF7A3CBC](<Server/Supermicro/SYS-6018/SYS-6018R-WTR/5EE2BAE645DD/CENTOS-7/3.10.0-862.14.4.EL7.X86_64/X86_64/17BF7A3CBC>) |
| 8086:0e30 | 15d9:0636 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 14    | ivbep_u... | [6994C89077](<Server/Supermicro/X9/X9DRW/6A1A83EBE660/DEBIAN-11/5.15.104-1-PVE/X86_64/6994C89077>) |
| 8086:0e34 | 15d9:0636 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 14    | ivbep_u... | [6994C89077](<Server/Supermicro/X9/X9DRW/6A1A83EBE660/DEBIAN-11/5.15.104-1-PVE/X86_64/6994C89077>) |
| 8086:0e36 | 15d9:0636 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 14    | ivbep_u... | [6994C89077](<Server/Supermicro/X9/X9DRW/6A1A83EBE660/DEBIAN-11/5.15.104-1-PVE/X86_64/6994C89077>) |
| 8086:3c43 | 1028:048c | Intel            | Xeon E5/Core i7 Ring to PCI Expre... | 12    | snbep_u... | [6A0AF69B4A](<Server/Dell/PowerEdge/PowerEdge R720/F424DE07066D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6A0AF69B4A>) |
| 8086:3c43 | 8086:0000 | Intel            | Xeon E5/Core i7 Ring to PCI Expre... | 12    | snbep_u... | [27BD1EBECD](<Server/IBM/System/System x3300 M4 -[7382E3G]-/9B380C91EDA6/DEBIAN-11/5.10.0-18-AMD64/X86_64/27BD1EBECD>) |
| 8086:3c44 | 1028:048c | Intel            | Xeon E5/Core i7 Ring to QuickPath... | 12    | snbep_u... | [6A0AF69B4A](<Server/Dell/PowerEdge/PowerEdge R720/F424DE07066D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6A0AF69B4A>) |
| 8086:3c44 | 8086:0000 | Intel            | Xeon E5/Core i7 Ring to QuickPath... | 12    | snbep_u... | [27BD1EBECD](<Server/IBM/System/System x3300 M4 -[7382E3G]-/9B380C91EDA6/DEBIAN-11/5.10.0-18-AMD64/X86_64/27BD1EBECD>) |
| 8086:3c46 | 1028:048c | Intel            | Xeon E5/Core i7 Processor Home Ag... | 12    | snbep_u... | [6A0AF69B4A](<Server/Dell/PowerEdge/PowerEdge R720/F424DE07066D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6A0AF69B4A>) |

### Pic (8259) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:342e |           | Intel            | 7500/5520/5500/X58 I/O Hub System... | 199   | i7core_... | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:3422 |           | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 197   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:3423 |           | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 197   |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:3438 |           | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 107   | i5500_temp | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:3422 | 003c:000b | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 59    |            | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |
| 8086:3423 | 003c:000b | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 59    |            | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |
| 8086:342e | 003c:000b | Intel            | 7500/5520/5500/X58 I/O Hub System... | 59    | i7core_... | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |
| 8086:3425 |           | Intel            | 7500/5520/5500/X58 Physical and L... | 20    |            | [16C68A28D8](<Server/IBM/System/System x3550 M3 -[7944SCP]-/B3404BB51BF1/DEBIAN-10/4.19.0-20-686-PAE/I686/16C68A28D8>) |
| 8086:3426 |           | Intel            | 7500/5520/5500/X58 Routing and Pr... | 20    |            | [16C68A28D8](<Server/IBM/System/System x3550 M3 -[7944SCP]-/B3404BB51BF1/DEBIAN-10/4.19.0-20-686-PAE/I686/16C68A28D8>) |
| 8086:3427 |           | Intel            | 7500/5520/5500 Physical and Link ... | 20    |            | [16C68A28D8](<Server/IBM/System/System x3550 M3 -[7944SCP]-/B3404BB51BF1/DEBIAN-10/4.19.0-20-686-PAE/I686/16C68A28D8>) |
| 8086:3428 |           | Intel            | 7500/5520/5500 Routing & Protocol... | 20    |            | [16C68A28D8](<Server/IBM/System/System x3550 M3 -[7944SCP]-/B3404BB51BF1/DEBIAN-10/4.19.0-20-686-PAE/I686/16C68A28D8>) |
| 8086:3422 | 0086:00dc | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 9     |            | [5C00E2D415](<Server/Intel/S5520/S5520HC/42DF18E9A677/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/5C00E2D415>) |
| 8086:3423 | 0086:00dc | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 9     |            | [5C00E2D415](<Server/Intel/S5520/S5520HC/42DF18E9A677/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/5C00E2D415>) |
| 8086:3425 | 0086:00dc | Intel            | 7500/5520/5500/X58 Physical and L... | 9     |            | [5C00E2D415](<Server/Intel/S5520/S5520HC/42DF18E9A677/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/5C00E2D415>) |
| 8086:3426 | 0086:00dc | Intel            | 7500/5520/5500/X58 Routing and Pr... | 9     |            | [5C00E2D415](<Server/Intel/S5520/S5520HC/42DF18E9A677/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/5C00E2D415>) |
| 8086:3427 | 0086:00dc | Intel            | 7500/5520/5500 Physical and Link ... | 9     |            | [5C00E2D415](<Server/Intel/S5520/S5520HC/42DF18E9A677/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/5C00E2D415>) |
| 8086:3428 | 0086:00dc | Intel            | 7500/5520/5500 Routing & Protocol... | 9     |            | [5C00E2D415](<Server/Intel/S5520/S5520HC/42DF18E9A677/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/5C00E2D415>) |
| 8086:342e | 0086:00dc | Intel            | 7500/5520/5500/X58 I/O Hub System... | 9     | i7core_... | [5C00E2D415](<Server/Intel/S5520/S5520HC/42DF18E9A677/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/5C00E2D415>) |
| 8086:3438 | 0086:00dc | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 9     | i5500_temp | [5C00E2D415](<Server/Intel/S5520/S5520HC/42DF18E9A677/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/5C00E2D415>) |
| 8086:3422 | 0034:0027 | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 6     |            | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:3422 | 0086:00da | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 6     |            | [94527A8584](<Server/Intel/S5500/S5500BC/A12E8B03104E/LINUXMINT-19.3/5.4.0-148-GENERIC/X86_64/94527A8584>) |
| 8086:3423 | 0034:0027 | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 6     |            | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:3423 | 0086:00da | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 6     |            | [94527A8584](<Server/Intel/S5500/S5500BC/A12E8B03104E/LINUXMINT-19.3/5.4.0-148-GENERIC/X86_64/94527A8584>) |
| 8086:3425 | 0034:0027 | Intel            | 7500/5520/5500/X58 Physical and L... | 6     |            | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:3425 | 0086:00da | Intel            | 7500/5520/5500/X58 Physical and L... | 6     |            | [94527A8584](<Server/Intel/S5500/S5500BC/A12E8B03104E/LINUXMINT-19.3/5.4.0-148-GENERIC/X86_64/94527A8584>) |
| 8086:3426 | 0034:0027 | Intel            | 7500/5520/5500/X58 Routing and Pr... | 6     |            | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:3426 | 0086:00da | Intel            | 7500/5520/5500/X58 Routing and Pr... | 6     |            | [94527A8584](<Server/Intel/S5500/S5500BC/A12E8B03104E/LINUXMINT-19.3/5.4.0-148-GENERIC/X86_64/94527A8584>) |
| 8086:3427 | 0034:0027 | Intel            | 7500/5520/5500 Physical and Link ... | 6     |            | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:3427 | 0086:00da | Intel            | 7500/5520/5500 Physical and Link ... | 6     |            | [94527A8584](<Server/Intel/S5500/S5500BC/A12E8B03104E/LINUXMINT-19.3/5.4.0-148-GENERIC/X86_64/94527A8584>) |
| 8086:3428 | 0034:0027 | Intel            | 7500/5520/5500 Routing & Protocol... | 6     |            | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:3428 | 0086:00da | Intel            | 7500/5520/5500 Routing & Protocol... | 6     |            | [94527A8584](<Server/Intel/S5500/S5500BC/A12E8B03104E/LINUXMINT-19.3/5.4.0-148-GENERIC/X86_64/94527A8584>) |
| 8086:342e | 0034:0027 | Intel            | 7500/5520/5500/X58 I/O Hub System... | 6     | i7core_... | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:342e | 0086:00da | Intel            | 7500/5520/5500/X58 I/O Hub System... | 6     | i7core_... | [94527A8584](<Server/Intel/S5500/S5500BC/A12E8B03104E/LINUXMINT-19.3/5.4.0-148-GENERIC/X86_64/94527A8584>) |
| 8086:3438 | 0034:0027 | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 6     | i5500_temp | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:3438 | 0086:00da | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 6     | i5500_temp | [94527A8584](<Server/Intel/S5500/S5500BC/A12E8B03104E/LINUXMINT-19.3/5.4.0-148-GENERIC/X86_64/94527A8584>) |
| 8086:3422 | 0086:00e2 | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3423 | 0086:00e2 | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3425 | 0086:00e2 | Intel            | 7500/5520/5500/X58 Physical and L... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3426 | 0086:00e2 | Intel            | 7500/5520/5500/X58 Routing and Pr... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3427 | 0086:00e2 | Intel            | 7500/5520/5500 Physical and Link ... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3428 | 0086:00e2 | Intel            | 7500/5520/5500 Routing & Protocol... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:342e | 0086:00e2 | Intel            | 7500/5520/5500/X58 I/O Hub System... | 5     | i7core_... | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3438 | 0086:00e2 | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 5     | i5500_temp | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3422 | 0086:00de | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 3     |            | [476430304C](<Server/Intel/S5520/S5520UR/ED7F5C075DAE/UBUNTU-20.04/5.4.0-104-GENERIC/X86_64/476430304C>) |
| 8086:3423 | 0086:00de | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 3     |            | [476430304C](<Server/Intel/S5520/S5520UR/ED7F5C075DAE/UBUNTU-20.04/5.4.0-104-GENERIC/X86_64/476430304C>) |
| 8086:3425 | 0086:00de | Intel            | 7500/5520/5500/X58 Physical and L... | 3     |            | [476430304C](<Server/Intel/S5520/S5520UR/ED7F5C075DAE/UBUNTU-20.04/5.4.0-104-GENERIC/X86_64/476430304C>) |
| 8086:3426 | 0086:00de | Intel            | 7500/5520/5500/X58 Routing and Pr... | 3     |            | [476430304C](<Server/Intel/S5520/S5520UR/ED7F5C075DAE/UBUNTU-20.04/5.4.0-104-GENERIC/X86_64/476430304C>) |
| 8086:3427 | 0086:00de | Intel            | 7500/5520/5500 Physical and Link ... | 3     |            | [476430304C](<Server/Intel/S5520/S5520UR/ED7F5C075DAE/UBUNTU-20.04/5.4.0-104-GENERIC/X86_64/476430304C>) |
| 8086:3428 | 0086:00de | Intel            | 7500/5520/5500 Routing & Protocol... | 3     |            | [476430304C](<Server/Intel/S5520/S5520UR/ED7F5C075DAE/UBUNTU-20.04/5.4.0-104-GENERIC/X86_64/476430304C>) |
| 8086:342e | 0086:00de | Intel            | 7500/5520/5500/X58 I/O Hub System... | 3     | i7core_... | [476430304C](<Server/Intel/S5520/S5520UR/ED7F5C075DAE/UBUNTU-20.04/5.4.0-104-GENERIC/X86_64/476430304C>) |

### Pic (io(x)-apic) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2026 | 8086:2026 | Intel            | Sky Lake-E IOAPIC                    | 191   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2036 | 8086:2036 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 191   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:342d |           | Intel            | 7500/5520/5500/X58 I/O Hub I/OxAP... | 83    |            | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:3c2c | 103c:18a8 | Intel            | Xeon E5/Core i7 I/O APIC             | 49    |            | [961A066E6B](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/F726BB41B090/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/961A066E6B>) |
| 8086:2f2c | 8086:0000 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 45    |            | [AD555BFDE2](<Server/Dell/PowerEdge/PowerEdge T430/F2945010DA0E/ARCH-ROLLING/6.3.0-273-TKG-PDS-LLVM/X86_64/AD555BFDE2>) |
| 8086:6f2c | 8086:0000 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 24    |            | [BAF3069CD7](<Server/Cisco Systems/UCSC-C220/UCSC-C220-M4S/9D3781D2096F/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/BAF3069CD7>) |
| 8086:0e2c | 103c:18a8 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 20    |            | [C36BF90EFB](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/4BDFA2F6AD42/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/C36BF90EFB>) |
| 8086:6f2c | 103c:21ea | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 16    |            | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:6f2c | 15d9:0821 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 16    |            | [17BF7A3CBC](<Server/Supermicro/SYS-6018/SYS-6018R-WTR/5EE2BAE645DD/CENTOS-7/3.10.0-862.14.4.EL7.X86_64/X86_64/17BF7A3CBC>) |
| 8086:0e2c | 15d9:0636 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 14    |            | [6994C89077](<Server/Supermicro/X9/X9DRW/6A1A83EBE660/DEBIAN-11/5.15.104-1-PVE/X86_64/6994C89077>) |
| 8086:342f |           | Intel            | 7500/5520/5500/X58 Trusted Execut... | 14    |            | [16C68A28D8](<Server/IBM/System/System x3550 M3 -[7944SCP]-/B3404BB51BF1/DEBIAN-10/4.19.0-20-686-PAE/I686/16C68A28D8>) |
| 8086:2026 | 1590:18a9 | Intel            | Sky Lake-E IOAPIC                    | 11    |            | [C03DEE89F6](<Server/HPE/ProLiant/ProLiant DL380 Gen10/EE85DEEC4F6D/UBUNTU-20.04/5.15.0-60-GENERIC/X86_64/C03DEE89F6>) |
| 8086:2026 | 8086:0000 | Intel            | Sky Lake-E IOAPIC                    | 11    |            | [50CCA471C5](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/010A19E087DC/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/50CCA471C5>) |
| 8086:2036 | 1590:18a9 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 11    |            | [C03DEE89F6](<Server/HPE/ProLiant/ProLiant DL380 Gen10/EE85DEEC4F6D/UBUNTU-20.04/5.15.0-60-GENERIC/X86_64/C03DEE89F6>) |
| 8086:2036 | 8086:0000 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 11    |            | [50CCA471C5](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/010A19E087DC/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/50CCA471C5>) |
| 8086:2f2c | 103c:21ea | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 11    |            | [5F85FDADF1](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/C986ADB0FAC7/DEBIAN-11/5.15.74-1-PVE/X86_64/5F85FDADF1>) |
| 8086:0e2c | 1043:84f0 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 10    |            | [4AC44C74A3](<Server/ASUSTek Computer/Z9PA-D8/Z9PA-D8 Series/0BE952D59456/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/4AC44C74A3>) |
| 8086:3c2c | 1043:84f0 | Intel            | Xeon E5/Core i7 I/O APIC             | 10    |            | [91E39972F5](<Server/ASUSTek Computer/ESC4000/ESC4000 G2 Series/75FA7A6A974C/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/91E39972F5>) |
| 8086:2f2c | 15d9:0857 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 9     |            | [4646CB2FAE](<Server/Supermicro/X10/X10SRA/605408244187/XUBUNTU-22.04/5.15.0-40-GENERIC/X86_64/4646CB2FAE>) |
| 8086:342d | 0086:00dc | Intel            | 7500/5520/5500/X58 I/O Hub I/OxAP... | 9     |            | [5C00E2D415](<Server/Intel/S5520/S5520HC/42DF18E9A677/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/5C00E2D415>) |
| 8086:342f | 0086:00dc | Intel            | 7500/5520/5500/X58 Trusted Execut... | 9     |            | [5C00E2D415](<Server/Intel/S5520/S5520HC/42DF18E9A677/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/5C00E2D415>) |
| 8086:2026 | 17aa:7808 | Intel            | Sky Lake-E IOAPIC                    | 7     |            | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 8086:2036 | 17aa:7808 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 7     |            | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 8086:3c2c | 15d9:0626 | Intel            | Xeon E5/Core i7 I/O APIC             | 7     |            | [C4B4851A88](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/5E5B10F103C2/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/C4B4851A88>) |
| 8086:2026 | 17aa:7801 | Intel            | Sky Lake-E IOAPIC                    | 6     |            | [BAFB634A37](<Server/Lenovo/ThinkSystem/ThinkSystem SR530 -[7X08CTO1WW]-/16717DADAA79/CENTOS-7/3.10.0-1160.36.2.EL7.X86_64/X86_64/BAFB634A37>) |
| 8086:2026 | 1849:2026 | Intel            | Sky Lake-E IOAPIC                    | 6     |            | [51DC310024](<Server/Kraftway/Trusted/Trusted TS2000/583173D8B5F2/RED-OS-7.3.2/6.1.11-1.EL7.3.X86_64/X86_64/51DC310024>) |
| 8086:2036 | 17aa:7801 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 6     |            | [BAFB634A37](<Server/Lenovo/ThinkSystem/ThinkSystem SR530 -[7X08CTO1WW]-/16717DADAA79/CENTOS-7/3.10.0-1160.36.2.EL7.X86_64/X86_64/BAFB634A37>) |
| 8086:2036 | 1849:2036 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 6     |            | [51DC310024](<Server/Kraftway/Trusted/Trusted TS2000/583173D8B5F2/RED-OS-7.3.2/6.1.11-1.EL7.3.X86_64/X86_64/51DC310024>) |
| 8086:2f2c | 15d9:0831 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 6     |            | [58E86F0E34](<Server/Supermicro/Super/Super Server/BD4C9B6F043B/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/58E86F0E34>) |
| 8086:342d | 0086:00da | Intel            | 7500/5520/5500/X58 I/O Hub I/OxAP... | 6     |            | [94527A8584](<Server/Intel/S5500/S5500BC/A12E8B03104E/LINUXMINT-19.3/5.4.0-148-GENERIC/X86_64/94527A8584>) |
| 8086:342f | 0034:0027 | Intel            | 7500/5520/5500/X58 Trusted Execut... | 6     |            | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:342f | 0086:00da | Intel            | 7500/5520/5500/X58 Trusted Execut... | 6     |            | [94527A8584](<Server/Intel/S5500/S5500BC/A12E8B03104E/LINUXMINT-19.3/5.4.0-148-GENERIC/X86_64/94527A8584>) |
| 8086:0e2c | 15d9:062a | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 5     |            | [2E9D55D3A7](<Server/Supermicro/X9/X9SRA-X9SRA-3/E73ED86A7227/DEBIAN-11/5.10.0-14-AMD64/X86_64/2E9D55D3A7>) |
| 8086:0e2c | 8086:35a0 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 5     |            | [5FBA63C085](<Server/Intel/S4600/S4600LH/902A1E31749C/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/5FBA63C085>) |
| 8086:2026 | 8086:35ce | Intel            | Sky Lake-E IOAPIC                    | 5     |            | [F5848D1BA2](<Server/DALCO/S2600/S2600WFT/37B0D5359698/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/F5848D1BA2>) |
| 8086:342d | 0086:00e2 | Intel            | 7500/5520/5500/X58 I/O Hub I/OxAP... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:342f | 0086:00e2 | Intel            | 7500/5520/5500/X58 Trusted Execut... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:6f2c | 15d9:0831 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 5     |            | [5E92E7FE1E](<Server/Supermicro/Super/Super Server/FD3A63BBABAD/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/5E92E7FE1E>) |
| 8086:2026 | 17aa:1038 | Intel            | Sky Lake-E IOAPIC                    | 4     |            | [7630762F0E](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC001DGE/B0EFE7081048/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/7630762F0E>) |
| 8086:2026 | 17aa:7800 | Intel            | Sky Lake-E IOAPIC                    | 4     |            | [C97EB83B9C](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 -[7X06CTO1WW]-/7AFAAAD68C64/CENTOS-7/3.10.0-1160.36.2.EL7.X86_64/X86_64/C97EB83B9C>) |
| 8086:2036 | 17aa:1038 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 4     |            | [7630762F0E](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC001DGE/B0EFE7081048/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/7630762F0E>) |
| 8086:2036 | 17aa:7800 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 4     |            | [C97EB83B9C](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 -[7X06CTO1WW]-/7AFAAAD68C64/CENTOS-7/3.10.0-1160.36.2.EL7.X86_64/X86_64/C97EB83B9C>) |
| 8086:2036 | 8086:35ce | Intel            | Sky Lake-E IOxAPIC Configuration ... | 4     |            | [F5848D1BA2](<Server/DALCO/S2600/S2600WFT/37B0D5359698/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/F5848D1BA2>) |
| 8086:3c2c | 15d9:0702 | Intel            | Xeon E5/Core i7 I/O APIC             | 4     |            | [6A4FA8EBE7](<Server/Supermicro/X9/X9DRD-7LN4F-X9DRD-EF/1932E0848226/DEBIAN-11/5.15.53-1-PVE/X86_64/6A4FA8EBE7>) |
| 8086:6f2c | 15d9:0834 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 4     |            | [16A0245A41](<Server/Supermicro/Super/Super Server/19433F8FA9C4/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/16A0245A41>) |
| 8086:0326 |           | Intel            | 6700/6702PXH I/OxAPIC Interrupt C... | 3     |            | [6668785C6E](<Server/Supermicro/X8/X8DTN/20A324537052/UBUNTU-20.04/5.13.0-39-GENERIC/X86_64/6668785C6E>) |
| 8086:0e2c | 15d9:0626 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 3     |            | [6FC004B792](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/A8FA5EF00732/ARCH/6.0.0-RC6-269-TKG-CFS-LLVM/X86_64/6FC004B792>) |
| 8086:0e2c | 15d9:062b | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 3     |            | [21E11AD4FE](<Server/Supermicro/X9/X9SRE-X9SRE-3F-X9SRi-X9SRi-3F/AC4AC10ED873/DEBIAN-11/5.10.0-11-AMD64/X86_64/21E11AD4FE>) |
| 8086:0e2c | 8086:0e2c | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 3     |            | [E0EF143493](<Server/Quanta/Freedom/Freedom/53CBFD82B356/LINUXMINT-19.3/5.0.0-32-GENERIC/X86_64/E0EF143493>) |
| 8086:2026 | 17aa:1037 | Intel            | Sky Lake-E IOAPIC                    | 3     |            | [1D6082EFE8](<Server/Lenovo/ThinkStation/ThinkStation P720 30BBS21C01/FE8DF4F9C290/FEDORA-37/6.2.11-200.FC37.X86_64/X86_64/1D6082EFE8>) |

### Pic (io-apic) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:7451 | 1022:7451 | AMD              | AMD-8131 PCI-X IOAPIC                | 1     |            | [18B25AC51A](<Server/TYAN Computer/S/S4882/84BBA0EA52AC/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/18B25AC51A>) |
| 1022:7451 | 10f1:2895 | AMD              | AMD-8131 PCI-X IOAPIC                | 1     |            | [768571B831](<Server/TYAN Computer/S/S2895/4B5DFCDB09B6/LINUXMINT-20/5.4.0-58-GENERIC/X86_64/768571B831>) |

### Processing accelerators (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1db7:dc24 |           | Phytium Techn... | NPU Controller [X100 Series]         | 3     |            | [497220C5DD](<Server/Phytium/D/D2000/E78D0AE566AE/ATZ-11.6/5.10.0-20-ARM64/AARCH64/497220C5DD>) |
| 10ee:5000 | 10ee:000e | Xilinx           | Alveo U200 XDMA Platform             | 1     |            | [470CCEF528](<Server/Dell/PowerEdge/PowerEdge R7525/23F136DC785E/DEBIAN-11/5.10.0-15-AMD64/X86_64/470CCEF528>) |
| 10ee:5001 | 10ee:000e | Xilinx           | Processing accelerators              | 1     |            | [470CCEF528](<Server/Dell/PowerEdge/PowerEdge R7525/23F136DC785E/DEBIAN-11/5.10.0-15-AMD64/X86_64/470CCEF528>) |
| 8086:09c4 | 8086:0000 | Intel            | PAC with Intel Arria 10 GX FPGA      | 1     | dfl_pci    | [3A917876BA](<Server/Dell/PowerEdge/PowerEdge R740/388DE5F0FB73/UBUNTU-20.04/5.4.0-132-GENERIC/X86_64/3A917876BA>) |

### Processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1db7:dc20 | 0000:1701 | Phytium Techn... | [X100 Series]                        | 2     | pvrsrvkm   | [497220C5DD](<Server/Phytium/D/D2000/E78D0AE566AE/ATZ-11.6/5.10.0-20-ARM64/AARCH64/497220C5DD>) |
| 1db7:dc20 | 0000:1509 | Phytium Techn... | [X100 Series]                        | 1     | pvrsrvkm   | [7E0BE651B1](<Server/Phytium/D/D2000/17EC7603AC2B/UOS-20/4.19.0-ARM64-DESKTOP/AARCH64/7E0BE651B1>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:31cc | 1019:a94d | Intel            | Celeron/Pentium Silver Processor ... | 3     | sdhci_pci  | [0600880DBA](<Server/ECS/LIVA/LIVA Q2/51AFACC4D80B/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/0600880DBA>) |
| 8086:18db | 15d9:1c18 | Intel            | SD Host controller                   | 1     | sdhci_pci  | [3751D50DDE](<Server/Supermicro/Super/Super Server/ACFD57B232A4/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/3751D50DDE>) |
| 8086:31cc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1     | sdhci_pci  | [ABC999A1A4](<Server/GMKtec/NucBox/NucBox8/D2066B2FCB01/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/ABC999A1A4>) |
| 8086:31d0 | 8086:7270 | Intel            | Celeron/Pentium Silver SD Host Co... | 1     | sdhci_pci  | [ABC999A1A4](<Server/GMKtec/NucBox/NucBox8/D2066B2FCB01/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/ABC999A1A4>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a1a4 | 8086:7270 | Intel            | C620 Series Chipset Family SPI Co... | 48    | intel_s... | [18B2BF9FF4](<Server/Delta Computers/DSS-C621/DSS-C621LTG/EA1701537BF7/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/18B2BF9FF4>) |
| 8086:a1a4 | 8086:35ce | Intel            | C620 Series Chipset Family SPI Co... | 21    |            | [F5848D1BA2](<Server/DALCO/S2600/S2600WFT/37B0D5359698/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/F5848D1BA2>) |
| 8086:a1a4 | 1028:073a | Intel            | C620 Series Chipset Family SPI Co... | 20    | spi_int... | [962B265260](<Server/Dell/Precision/Precision 7920 Tower/8C7F63FF0FE0/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/962B265260>) |
| 8086:a1a4 | 1028:0715 | Intel            | C620 Series Chipset Family SPI Co... | 12    |            | [7AD0D2D67B](<Server/Dell/PowerEdge/PowerEdge R740/FF8CDFB5CB55/UBUNTU-18.04/4.15.0-193-GENERIC/X86_64/7AD0D2D67B>) |
| 8086:a1a4 | 1028:0739 | Intel            | C620 Series Chipset Family SPI Co... | 12    | spi_int... | [FE6DC0D9C7](<Server/Dell/Precision/Precision 7820 Tower/FB09ECB98D56/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FE6DC0D9C7>) |
| 8086:a1a4 | 1043:871e | Intel            | C620 Series Chipset Family SPI Co... | 11    | intel_s... | [C874A6D28C](<Server/ASUSTek Computer/ESC8000/ESC8000 G4/05733798C837/UBUNTU-18.04/5.4.0-121-GENERIC/X86_64/C874A6D28C>) |
| 8086:a324 | 8086:7270 | Intel            | Cannon Lake PCH SPI Controller       | 11    | spi_int... | [A2FD0BC88C](<Server/Lenovo/ThinkSystem/ThinkSystem SR250 -[7Y51CTO1WW]-/56D35BA12534/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/A2FD0BC88C>) |
| 10de:1ad9 | 1028:12a0 | Nvidia           | TU104 USB Type-C UCSI Controller     | 9     | i2c_nvi... | [962B265260](<Server/Dell/Precision/Precision 7920 Tower/8C7F63FF0FE0/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/962B265260>) |
| 8086:a1a4 | 15d9:096d | Intel            | C620 Series Chipset Family SPI Co... | 8     |            | [DCBB3D117A](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.4.0-105-GENERIC/X86_64/DCBB3D117A>) |
| 8086:a1a4 | 15d9:0967 | Intel            | C620 Series Chipset Family SPI Co... | 7     |            | [DE3332B83C](<Server/Supermicro/SYS-6029/SYS-6029P-WTRT/35C50F3639E9/ACRONIS-CYBER-INFRASTRUCTURE-5.1.0/3.10.0-1160.53.1.VZ7.185.3/X86_64/DE3332B83C>) |
| 8086:a1a4 | 17aa:7808 | Intel            | C620 Series Chipset Family SPI Co... | 7     | intel_s... | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 8086:a1a4 | 1028:0718 | Intel            | C620 Series Chipset Family SPI Co... | 6     |            | [A4F3535E84](<Server/Dell/Precision/Precision 7920 Rack/1D56B1A533A9/UBUNTU-20.04/5.14.0-1057-OEM/X86_64/A4F3535E84>) |
| 8086:a1a4 | 103c:81c7 | Intel            | C620 Series Chipset Family SPI Co... | 6     | spi_int... | [50CCA471C5](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/010A19E087DC/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/50CCA471C5>) |
| 8086:a1a4 | 17aa:7801 | Intel            | C620 Series Chipset Family SPI Co... | 6     |            | [BAFB634A37](<Server/Lenovo/ThinkSystem/ThinkSystem SR530 -[7X08CTO1WW]-/16717DADAA79/CENTOS-7/3.10.0-1160.36.2.EL7.X86_64/X86_64/BAFB634A37>) |
| 8086:a1a4 | 1849:a1a4 | Intel            | C620 Series Chipset Family SPI Co... | 6     |            | [51DC310024](<Server/Kraftway/Trusted/Trusted TS2000/583173D8B5F2/RED-OS-7.3.2/6.1.11-1.EL7.3.X86_64/X86_64/51DC310024>) |
| 8086:a324 | 15d9:1a1d | Intel            | Cannon Lake PCH SPI Controller       | 6     | intel_s... | [065427C37F](<Server/Supermicro/Super/Super Server/2CF7574245C0/DEBIAN-11/5.10.162-1.LAT5.10.0-21/X86_64/065427C37F>) |
| 8086:a368 | 15d9:1a1d | Intel            | Cannon Lake PCH Serial IO I2C Con... | 6     | intel_l... | [065427C37F](<Server/Supermicro/Super/Super Server/2CF7574245C0/DEBIAN-11/5.10.162-1.LAT5.10.0-21/X86_64/065427C37F>) |
| 8086:a369 | 15d9:1a1d | Intel            | Cannon Lake PCH Serial IO I2C Con... | 6     | intel_l... | [065427C37F](<Server/Supermicro/Super/Super Server/2CF7574245C0/DEBIAN-11/5.10.162-1.LAT5.10.0-21/X86_64/065427C37F>) |
| 8086:a1a4 | 103c:81c6 | Intel            | C620 Series Chipset Family SPI Co... | 5     |            | [C60CE01C1E](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/5FDF871A62B0/UBUNTU-20.04/5.15.0-48-GENERIC/X86_64/C60CE01C1E>) |
| 8086:a1a4 | 15d9:095d | Intel            | C620 Series Chipset Family SPI Co... | 5     |            | [6D1F207293](<Server/primeLine Solutions/egino/egino BTO Konfig Server/B668BEC7EEFE/DEBIAN-11/5.15.85-1-PVE/X86_64/6D1F207293>) |
| 8086:a1a4 | 15d9:0981 | Intel            | C620 Series Chipset Family SPI Co... | 5     | intel_s... | [D9B96BCE95](<Server/Supermicro/Super/Super Server/909986EADB14/UBUNTU-22.10/5.19.0-23-GENERIC/X86_64/D9B96BCE95>) |
| 8086:a324 | 15d9:1a1f | Intel            | Cannon Lake PCH SPI Controller       | 5     | intel_s... | [EF92C1FC32](<Server/Supermicro/Super/Super Server/A1AAA9CEAEE9/CENTOS-8/4.18.0-448.EL8.X86_64/X86_64/EF92C1FC32>) |
| 8086:a368 | 15d9:1a1f | Intel            | Cannon Lake PCH Serial IO I2C Con... | 5     | intel_l... | [EF92C1FC32](<Server/Supermicro/Super/Super Server/A1AAA9CEAEE9/CENTOS-8/4.18.0-448.EL8.X86_64/X86_64/EF92C1FC32>) |
| 8086:a369 | 15d9:1a1f | Intel            | Cannon Lake PCH Serial IO I2C Con... | 5     | intel_l... | [EF92C1FC32](<Server/Supermicro/Super/Super Server/A1AAA9CEAEE9/CENTOS-8/4.18.0-448.EL8.X86_64/X86_64/EF92C1FC32>) |
| 10de:1ad7 | 1458:37c4 | Nvidia           | TU102 USB Type-C UCSI Controller     | 4     | i2c_nvi... | [C874A6D28C](<Server/ASUSTek Computer/ESC8000/ESC8000 G4/05733798C837/UBUNTU-18.04/5.4.0-121-GENERIC/X86_64/C874A6D28C>) |
| 8086:19e0 | 15d9:0969 | Intel            | Atom Processor C3000 Series SPI C... | 4     | intel_s... | [CDCA826585](<Server/Supermicro/Super/Super Server/67F50154C8D4/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/CDCA826585>) |
| 8086:1bca | 8086:7270 | Intel            | C741 Series SPI Controller           | 4     |            | [3DDB00DA94](<Server/Intel/ArcherCity/ArcherCity/35F42C801DE0/FEDORA-37/6.1.7-200.FC37.X86_64/X86_64/3DDB00DA94>) |
| 8086:a1a4 | 1028:0716 | Intel            | C620 Series Chipset Family SPI Co... | 4     |            | [02F8E21FA8](<Server/Dell/PowerEdge/PowerEdge R640/D35AD5A42EE7/UBUNTU-20.04/5.4.0-105-GENERIC/X86_64/02F8E21FA8>) |
| 8086:a1a4 | 1028:0737 | Intel            | C620 Series Chipset Family SPI Co... | 4     |            | [D2AE46F823](<Server/Dell/XC740xd-12/XC740xd-12 CORE/DD8724B460B5/UBUNTU-18.04/4.15.0-175-GENERIC/X86_64/D2AE46F823>) |
| 8086:a1a4 | 1028:07cb | Intel            | C620 Series Chipset Family SPI Co... | 4     |            | [465C40DD0F](<Server/Dell/PowerEdge/PowerEdge T440/1E0687BF68BA/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/465C40DD0F>) |
| 8086:a1a4 | 15d9:091c | Intel            | C620 Series Chipset Family SPI Co... | 4     |            | [90F9906D76](<Server/Supermicro/SYS-1029/SYS-1029U-TR25M-BK-LC019/25926C72BE6F/ACRONIS-CYBER-INFRASTRUCTURE-5.1.1/3.10.0-1160.53.1.VZ7.185.3/X86_64/90F9906D76>) |
| 8086:a1a4 | 15d9:0953 | Intel            | C620 Series Chipset Family SPI Co... | 4     |            | [A76BB2E30D](<Server/Supermicro/SYS-5029/SYS-5029P-WTR/2D889DFAC2FF/ROCKY-8.5/4.18.0-348.12.2.EL8_5.X86_64/X86_64/A76BB2E30D>) |
| 8086:a1a4 | 15d9:0986 | Intel            | C620 Series Chipset Family SPI Co... | 4     |            | [FFA58F1702](<Server/Supermicro/SYS-E300/SYS-E300-9D-8CN8TP/202BFE094BD2/DEBIAN-11/5.10.0-21-AMD64/X86_64/FFA58F1702>) |
| 8086:a1a4 | 17aa:1038 | Intel            | C620 Series Chipset Family SPI Co... | 4     |            | [7630762F0E](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC001DGE/B0EFE7081048/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/7630762F0E>) |
| 8086:a1a4 | 17aa:7800 | Intel            | C620 Series Chipset Family SPI Co... | 4     |            | [C97EB83B9C](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 -[7X06CTO1WW]-/7AFAAAD68C64/CENTOS-7/3.10.0-1160.36.2.EL7.X86_64/X86_64/C97EB83B9C>) |
| 8086:a368 | 8086:7270 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 4     | intel_l... | [A2FD0BC88C](<Server/Lenovo/ThinkSystem/ThinkSystem SR250 -[7Y51CTO1WW]-/56D35BA12534/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/A2FD0BC88C>) |
| 8086:a369 | 8086:7270 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 4     | intel_l... | [A2FD0BC88C](<Server/Lenovo/ThinkSystem/ThinkSystem SR250 -[7Y51CTO1WW]-/56D35BA12534/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/A2FD0BC88C>) |
| 10de:1ad7 | 1028:12ba | Nvidia           | TU102 USB Type-C UCSI Controller     | 3     | i2c_nvi... | [24B220FDDB](<Server/Dell/Precision/Precision 7820 Tower/804C86655D28/UBUNTU-20.04/5.10.0-1023-OEM/X86_64/24B220FDDB>) |
| 8086:a1a4 | 1028:07c9 | Intel            | C620 Series Chipset Family SPI Co... | 3     |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:a1a4 | 1458:5001 | Intel            | C620 Series Chipset Family SPI Co... | 3     |            | [030B77C94D](<Server/Gigabyte Technology/C621/C621-WD12-IPMI/5E4783EDD64C/ROCKY-8.7/4.18.0-425.13.1.EL8_7.X86_64/X86_64/030B77C94D>) |
| 8086:a1a4 | 17aa:1037 | Intel            | C620 Series Chipset Family SPI Co... | 3     |            | [1D6082EFE8](<Server/Lenovo/ThinkStation/ThinkStation P720 30BBS21C01/FE8DF4F9C290/FEDORA-37/6.2.11-200.FC37.X86_64/X86_64/1D6082EFE8>) |
| 8086:a324 | 1028:088e | Intel            | Cannon Lake PCH SPI Controller       | 3     |            | [2A87802C58](<Server/Dell/PowerEdge/PowerEdge R340/89867B3F61A1/DEBIAN-9/4.9.0-14-AMD64/X86_64/2A87802C58>) |
| 8086:a324 | 15d9:1a1b | Intel            | Cannon Lake PCH SPI Controller       | 3     |            | [F1BF9D35EF](<Server/Supermicro/SYS-5039/SYS-5039MC-H12TRF/C2156B6F043C/DEBIAN-10/5.4.98-1-PVE/X86_64/F1BF9D35EF>) |
| 8086:a368 | 15d9:1a1b | Intel            | Cannon Lake PCH Serial IO I2C Con... | 3     | intel_l... | [F1BF9D35EF](<Server/Supermicro/SYS-5039/SYS-5039MC-H12TRF/C2156B6F043C/DEBIAN-10/5.4.98-1-PVE/X86_64/F1BF9D35EF>) |
| 8086:a369 | 15d9:1a1b | Intel            | Cannon Lake PCH Serial IO I2C Con... | 3     | intel_l... | [F1BF9D35EF](<Server/Supermicro/SYS-5039/SYS-5039MC-H12TRF/C2156B6F043C/DEBIAN-10/5.4.98-1-PVE/X86_64/F1BF9D35EF>) |
| 10de:1ad7 | 1043:8675 | Nvidia           | TU102 USB Type-C UCSI Controller     | 2     | i2c_nvi... | [B714FA4C7F](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/E3AB736A8A10/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/B714FA4C7F>) |
| 10de:1ad7 | 10de:12a3 | Nvidia           | TU102 USB Type-C UCSI Controller     | 2     | i2c_nvi... | [8A1397B10C](<Server/Dell/Precision/Precision 7920 Tower/2EF12D6F97D1/UBUNTU-20.04/5.8.0-63-GENERIC/X86_64/8A1397B10C>) |
| 8086:43a4 | 1043:882f | Intel            | Tiger Lake-H SPI Controller          | 2     | spi_int... | [F4BF235EA8](<Server/ASUSTek Computer/P12R-E/P12R-E Series 60SB0A90-SB0A08/4BCF5AD8367F/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/F4BF235EA8>) |
| 8086:43a4 | 1458:1000 | Intel            | Tiger Lake-H SPI Controller          | 2     |            | [ABFEE9C5F7](<Server/Gigabyte Technology/MX33/MX33-BS0-00/2E0D4C1B34E3/KUBUNTU-22.04/5.17.0-1017-OEM/X86_64/ABFEE9C5F7>) |
| 8086:43ad | 1043:882f | Intel            | 500 Series Chipset Family PCIe Po... | 2     | intel_l... | [F4BF235EA8](<Server/ASUSTek Computer/P12R-E/P12R-E Series 60SB0A90-SB0A08/4BCF5AD8367F/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/F4BF235EA8>) |

### Serial controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a1bd | 1028:073a | Intel            | C620 Series Chipset Family KT Red... | 10    | serial     | [A7C222100E](<Server/Dell/Precision/Precision 7920 Tower/4FFAA8A7598E/LINUXMINT-21.1/5.15.0-67-GENERIC/X86_64/A7C222100E>) |
| 8086:a1bd | 1028:0739 | Intel            | C620 Series Chipset Family KT Red... | 9     | serial     | [FE6DC0D9C7](<Server/Dell/Precision/Precision 7820 Tower/FB09ECB98D56/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FE6DC0D9C7>) |
| 8086:a363 | 8086:7270 | Intel            | Cannon Lake PCH Active Management... | 8     | serial     | [196C8EB317](<Server/Neousys Technology/Nuvo-7100VTC/Nuvo-7100VTC Series/E44E3E216941/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/196C8EB317>) |
| 8086:a13d | 15d9:0895 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     | serial     | [CE6BAA4FDA](<Server/Supermicro/Super/Super Server/A842905AAA3B/UBUNTU-18.04/5.4.0-132-GENERIC/X86_64/CE6BAA4FDA>) |
| 8086:8c3d | 15d9:0805 | Intel            | 8 Series/C220 Series Chipset Fami... | 5     | serial     | [4B0CFEC9A7](<Server/Supermicro/X10/X10SAE/FF0B31A8C494/NOBARA-37/6.2.10-200.FSYNC.FC37.X86_64/X86_64/4B0CFEC9A7>) |
| 8086:a13d | 8086:1999 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     | serial     | [BBD0BE963A](<Server/HPE/ML10/ML10Gen9/06A38AE11D38/UBUNTU-20.04/5.15.0-48-GENERIC/X86_64/BBD0BE963A>) |
| 8086:a1bd | 17aa:1038 | Intel            | C620 Series Chipset Family KT Red... | 4     | serial     | [7630762F0E](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC001DGE/B0EFE7081048/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/7630762F0E>) |
| 8086:a2bd | 15d9:098e | Intel            | 200 Series Chipset Family KT Redi... | 4     | serial     | [2887A82948](<Server/Supermicro/Super/Super Server/4CD262ADBF12/DEBIAN-11/5.19.11/X86_64/2887A82948>) |
| 8086:a1bd | 17aa:1037 | Intel            | C620 Series Chipset Family KT Red... | 3     | serial     | [1D6082EFE8](<Server/Lenovo/ThinkStation/ThinkStation P720 30BBS21C01/FE8DF4F9C290/FEDORA-37/6.2.11-200.FC37.X86_64/X86_64/1D6082EFE8>) |
| 1415:c208 | 1415:c208 | Oxford Semico... | OXPCIe954 Quad Native 950 UART       | 2     | serial     | [C088868F62](<Server/Supermicro/X9/X9DRD-iF-LF/F42BB6D21594/DEBIAN-11/5.15.74-1-PVE/X86_64/C088868F62>) |
| 8086:a13d | 15d9:089f | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | serial     | [ECB9EC0D34](<Server/Supermicro/Super/Super Server/D5D09C37A0C7/ARCO-ROLLING/5.15.19-XANMOD1-TT-1/X86_64/ECB9EC0D34>) |
| 9710:9865 | a000:1000 | MosChip Semic... | PCI 9865 Multi-I/O Controller        | 2     | parport_pc | [715B40D8B6](<Server/Intel/S5000/S5000XVN/187007C30239/FEDORA-34/5.14.12-200.FC34.X86_64/X86_64/715B40D8B6>) |
| 10ee:4b87 | 10ee:4350 | Xilinx           | Serial controller                    | 1     | xclmgmt    | [7026C20C97](<Server/Supermicro/Super/Super Server/007236A7EB64/UBUNTU-UNITY-16.04/4.13.0-36-GENERIC/X86_64/7026C20C97>) |
| 10ee:4b88 | 10ee:4350 | Xilinx           | Serial controller                    | 1     | xocl       | [7026C20C97](<Server/Supermicro/Super/Super Server/007236A7EB64/UBUNTU-UNITY-16.04/4.13.0-36-GENERIC/X86_64/7026C20C97>) |
| 1393:1024 | 1393:1024 | Moxa Technolo... | CP-102E (2-port RS-232 Smart PCI ... | 1     | serial     | [9C8826C0D2](<Server/Dell/PowerEdge/PowerEdge T110/31B8C6D71C1F/UBUNTU-20.04/5.4.0-89-GENERIC/X86_64/9C8826C0D2>) |
| 1415:9501 | 131f:2050 | Oxford Semico... | OX16PCI954 (Quad 16950 UART) func... | 1     | serial     | [80DC2F8936](<Server/Supermicro/Super/Super Server/A9CFB59D8528/OPENSUSE-LEAP-42.1/4.1.39-56-DEFAULT/X86_64/80DC2F8936>) |
| 1415:c158 | 1415:c158 | Oxford Semico... | OXPCIe952 Dual Native 950 UART       | 1     | serial     | [352FEE0E7F](<Server/HPE/ProLiant/ProLiant DL360 Gen10/0438CFCFB022/DEBIAN-10/4.19.0-8-AMD64/X86_64/352FEE0E7F>) |
| 8086:18d8 | 15d9:1c18 | Intel            | Cedar Fork HSUART                    | 1     | 8250_mi... | [3751D50DDE](<Server/Supermicro/Super/Super Server/ACFD57B232A4/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/3751D50DDE>) |
| 8086:1d3d | 152d:8988 | Intel            | C600/X79 series chipset KT Contro... | 1     | serial     | [E0EF143493](<Server/Quanta/Freedom/Freedom/53CBFD82B356/LINUXMINT-19.3/5.0.0-32-GENERIC/X86_64/E0EF143493>) |
| 8086:43fc | 1043:882f | Intel            | Tiger Lake-H Integrated Sensor Hub   | 1     | intel_i... | [0C1465AD47](<Server/ASUSTek Computer/RS300/RS300-E11-PS4/85644FBAE9C3/UBUNTU-22.10/5.19.0-15-GENERIC/X86_64/0C1465AD47>) |
| 8086:43fc | 1458:1000 | Intel            | Tiger Lake-H Integrated Sensor Hub   | 1     | intel_i... | [B5F65C4F56](<Server/Gigabyte Technology/MX33/MX33-BS1-V1/136991526296/UBUNTU-20.04/5.4.0-113-GENERIC/X86_64/B5F65C4F56>) |
| 8086:8c3d | 15d9:0654 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | serial     | [AE67700E54](<Server/Supermicro/X10/X10SLQ/A28F497601BF/FEDORA-33/5.9.13-200.FC33.X86_64/X86_64/AE67700E54>) |
| 8086:8d3d | 1458:1000 | Intel            | C610/X99 series chipset KT Contro... | 1     | serial     | [2F69A2F89C](<Server/Dedicated Computing/OEM-F7342/OEM-F7342-00/A56806D283ED/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/2F69A2F89C>) |
| 8086:8d3d | 15d9:0834 | Intel            | C610/X99 series chipset KT Contro... | 1     | serial     | [746DAACC72](<Server/Supermicro/Super/Super Server/4582319ADDEA/DEBIAN-10/5.4.203-1-PVE/X86_64/746DAACC72>) |
| 8086:a13d | 15d9:0888 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | serial     | [C37F8CD97A](<Server/Supermicro/Super/Super Server/3D7809C86280/DEBIAN-11/5.15.74-1-PVE/X86_64/C37F8CD97A>) |
| 8086:a13d | 15d9:0894 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | serial     | [7FD98E489A](<Server/Supermicro/X11/X11SSV-Q/FE7DA47D9138/OPENMANDRIVA-22.12/6.0.10-DESKTOP-GCC-2OMV22090/X86_64/7FD98E489A>) |
| 8086:a13d | 15d9:0907 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | serial     | [66EE0BC524](<Server/Supermicro/Super/Super Server/40D662EC15C8/UBUNTU-18.04/4.15.0-143-GENERIC/X86_64/66EE0BC524>) |
| 8086:a13d | 8086:a13d | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | serial     | [E86E339278](<Server/Neousys Technology/Nuvo-5100/Nuvo-5100VTC/E9F17F7D3348/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/E86E339278>) |
| 8086:a1bd | 103c:81c7 | Intel            | C620 Series Chipset Family KT Red... | 1     | serial     | [E717A99F1F](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/5E9B675190B8/ZORIN-16/5.15.0-67-GENERIC/X86_64/E717A99F1F>) |
| 8086:a1bd | 1734:1230 | Intel            | C620 Series Chipset Family KT Red... | 1     | serial     | [86AB491564](<Server/Fujitsu/CELSIUS/CELSIUS R970/7E07629658CC/CENTOS-8/4.18.0-240.10.1.EL8_3.X86_64/X86_64/86AB491564>) |
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
| 8086:a1b1 | 8086:7270 | Intel            | C620 Series Chipset Family Therma... | 48    | intel_p... | [18B2BF9FF4](<Server/Delta Computers/DSS-C621/DSS-C621LTG/EA1701537BF7/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/18B2BF9FF4>) |
| 8086:a1b1 | 8086:35ce | Intel            | C620 Series Chipset Family Therma... | 22    | intel_p... | [F5848D1BA2](<Server/DALCO/S2600/S2600WFT/37B0D5359698/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/F5848D1BA2>) |
| 8086:a1b1 | 1028:073a | Intel            | C620 Series Chipset Family Therma... | 20    | intel_p... | [962B265260](<Server/Dell/Precision/Precision 7920 Tower/8C7F63FF0FE0/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/962B265260>) |
| 8086:a131 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 17    | intel_p... | [97D3C70FB5](<Server/Quanta/QuantaMicro/QuantaMicro X10E-9N/01ACEA39AAB2/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/97D3C70FB5>) |
| 8086:1d24 | 15d9:0636 | Intel            | C600/X79 series chipset Thermal M... | 15    |            | [6994C89077](<Server/Supermicro/X9/X9DRW/6A1A83EBE660/DEBIAN-11/5.15.104-1-PVE/X86_64/6994C89077>) |
| 8086:a1b1 | 1028:0715 | Intel            | C620 Series Chipset Family Therma... | 12    |            | [7AD0D2D67B](<Server/Dell/PowerEdge/PowerEdge R740/FF8CDFB5CB55/UBUNTU-18.04/4.15.0-193-GENERIC/X86_64/7AD0D2D67B>) |
| 8086:a1b1 | 1028:0739 | Intel            | C620 Series Chipset Family Therma... | 12    | intel_p... | [FE6DC0D9C7](<Server/Dell/Precision/Precision 7820 Tower/FB09ECB98D56/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FE6DC0D9C7>) |
| 8086:a1b1 | 1590:00eb | Intel            | C620 Series Chipset Family Therma... | 12    | intel_p... | [74466AD718](<Server/HPE/ProLiant/ProLiant DL360 Gen10 Plus/6004A3CDB655/DEBIAN-11/5.15.107-1-PVE/X86_64/74466AD718>) |
| 8086:a1b1 | 1043:871e | Intel            | C620 Series Chipset Family Therma... | 11    | intel_p... | [C874A6D28C](<Server/ASUSTek Computer/ESC8000/ESC8000 G4/05733798C837/UBUNTU-18.04/5.4.0-121-GENERIC/X86_64/C874A6D28C>) |
| 8086:a379 | 8086:7270 | Intel            | Cannon Lake PCH Thermal Controller   | 11    | intel_p... | [A2FD0BC88C](<Server/Lenovo/ThinkSystem/ThinkSystem SR250 -[7Y51CTO1WW]-/56D35BA12534/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/A2FD0BC88C>) |
| 8086:1d24 | 15d9:0626 | Intel            | C600/X79 series chipset Thermal M... | 10    |            | [C4B4851A88](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/5E5B10F103C2/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/C4B4851A88>) |
| 8086:8d24 | 15d9:0857 | Intel            | C610/X99 series chipset Thermal S... | 10    |            | [A9AA07EF24](<Server/Supermicro/X10/X10SRA-F/446FAE82E232/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/A9AA07EF24>) |
| 8086:a131 | 15d9:089a | Intel            | 100 Series/C230 Series Chipset Fa... | 10    | intel_p... | [7AA0EB0936](<Server/Supermicro/Super/Super Server/7660AB944FAA/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/7AA0EB0936>) |
| 8086:8c24 | 15d9:0801 | Intel            | 8 Series Chipset Family Thermal M... | 9     | intel_p... | [6CE8B7FB26](<Server/Supermicro/X10/X10SLL-F/34D1B7FAB08F/NIXOS-22.11/5.15.96/X86_64/6CE8B7FB26>) |
| 8086:8c24 | 15d9:086d | Intel            | 8 Series Chipset Family Thermal M... | 9     | intel_p... | [210B2E16E3](<Server/Supermicro/Super/Super Server/9DEEB33699DA/GENTOO-2.13/5.15.75-GENTOO-DIST/X86_64/210B2E16E3>) |
| 8086:8c24 | 8086:35b5 | Intel            | 8 Series Chipset Family Thermal M... | 8     | intel_p... | [28F4CEB8EE](<Server/Intel/S1200/S1200RP/FB9A925E61E5/ARCH-ROLLING/5.19.13-ARCH1-1/X86_64/28F4CEB8EE>) |
| 8086:a1b1 | 15d9:096d | Intel            | C620 Series Chipset Family Therma... | 8     | intel_p... | [DCBB3D117A](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.4.0-105-GENERIC/X86_64/DCBB3D117A>) |
| 8086:1d24 | 15d9:062a | Intel            | C600/X79 series chipset Thermal M... | 7     |            | [2E9D55D3A7](<Server/Supermicro/X9/X9SRA-X9SRA-3/E73ED86A7227/DEBIAN-11/5.10.0-14-AMD64/X86_64/2E9D55D3A7>) |
| 8086:a1b1 | 15d9:0967 | Intel            | C620 Series Chipset Family Therma... | 7     |            | [DE3332B83C](<Server/Supermicro/SYS-6029/SYS-6029P-WTRT/35C50F3639E9/ACRONIS-CYBER-INFRASTRUCTURE-5.1.0/3.10.0-1160.53.1.VZ7.185.3/X86_64/DE3332B83C>) |
| 8086:a1b1 | 17aa:7808 | Intel            | C620 Series Chipset Family Therma... | 7     |            | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 8086:8c24 | 15d9:0805 | Intel            | 8 Series Chipset Family Thermal M... | 6     | intel_p... | [4B0CFEC9A7](<Server/Supermicro/X10/X10SAE/FF0B31A8C494/NOBARA-37/6.2.10-200.FSYNC.FC37.X86_64/X86_64/4B0CFEC9A7>) |
| 8086:a131 | 1028:06a5 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     | intel_p... | [C8D2D41009](<Server/Dell/PowerEdge/PowerEdge R230/5B911C7AB359/UBUNTU-20.04/5.4.0-97-GENERIC/X86_64/C8D2D41009>) |
| 8086:a131 | 15d9:0895 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     | intel_p... | [CE6BAA4FDA](<Server/Supermicro/Super/Super Server/A842905AAA3B/UBUNTU-18.04/5.4.0-132-GENERIC/X86_64/CE6BAA4FDA>) |
| 8086:a1b1 | 1028:0718 | Intel            | C620 Series Chipset Family Therma... | 6     | intel_p... | [A4F3535E84](<Server/Dell/Precision/Precision 7920 Rack/1D56B1A533A9/UBUNTU-20.04/5.14.0-1057-OEM/X86_64/A4F3535E84>) |
| 8086:a1b1 | 103c:81c7 | Intel            | C620 Series Chipset Family Therma... | 6     | intel_p... | [50CCA471C5](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/010A19E087DC/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/50CCA471C5>) |
| 8086:a1b1 | 17aa:7801 | Intel            | C620 Series Chipset Family Therma... | 6     |            | [BAFB634A37](<Server/Lenovo/ThinkSystem/ThinkSystem SR530 -[7X08CTO1WW]-/16717DADAA79/CENTOS-7/3.10.0-1160.36.2.EL7.X86_64/X86_64/BAFB634A37>) |
| 8086:a1b1 | 1849:a1b1 | Intel            | C620 Series Chipset Family Therma... | 6     | intel_p... | [51DC310024](<Server/Kraftway/Trusted/Trusted TS2000/583173D8B5F2/RED-OS-7.3.2/6.1.11-1.EL7.3.X86_64/X86_64/51DC310024>) |
| 8086:a379 | 15d9:1a1d | Intel            | Cannon Lake PCH Thermal Controller   | 6     | intel_p... | [065427C37F](<Server/Supermicro/Super/Super Server/2CF7574245C0/DEBIAN-11/5.10.162-1.LAT5.10.0-21/X86_64/065427C37F>) |
| 19e5:1710 | 19e5:0000 | Huawei Techno... | iBMA Virtual Network Adapter         | 5     |            | [AD903545CE](<Server/HUAWEI/2288H/2288H V5/94600F3C6456/ALT-9.1/5.4.51-STD-DEF-ALT1/X86_64/AD903545CE>) |
| 8086:1d24 | 15d9:0702 | Intel            | C600/X79 series chipset Thermal M... | 5     |            | [6A4FA8EBE7](<Server/Supermicro/X9/X9DRD-7LN4F-X9DRD-EF/1932E0848226/DEBIAN-11/5.15.53-1-PVE/X86_64/6A4FA8EBE7>) |
| 8086:8c24 | 15d9:0921 | Intel            | 8 Series Chipset Family Thermal M... | 5     | intel_p... | [E60EC405AF](<Server/Supermicro/Super/Super Server/F5F261808B48/GENTOO-2.6/5.15.19-GENTOO/X86_64/E60EC405AF>) |
| 8086:a160 | 15d9:0895 | Intel            | 100 Series/C230 Series Chipset Fa... | 5     | intel_l... | [CE6BAA4FDA](<Server/Supermicro/Super/Super Server/A842905AAA3B/UBUNTU-18.04/5.4.0-132-GENERIC/X86_64/CE6BAA4FDA>) |
| 8086:a161 | 15d9:0895 | Intel            | 100 Series/C230 Series Chipset Fa... | 5     | intel_l... | [CE6BAA4FDA](<Server/Supermicro/Super/Super Server/A842905AAA3B/UBUNTU-18.04/5.4.0-132-GENERIC/X86_64/CE6BAA4FDA>) |
| 8086:a1b1 | 103c:81c6 | Intel            | C620 Series Chipset Family Therma... | 5     | intel_p... | [C60CE01C1E](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/5FDF871A62B0/UBUNTU-20.04/5.15.0-48-GENERIC/X86_64/C60CE01C1E>) |
| 8086:a1b1 | 15d9:095d | Intel            | C620 Series Chipset Family Therma... | 5     | intel_p... | [6D1F207293](<Server/primeLine Solutions/egino/egino BTO Konfig Server/B668BEC7EEFE/DEBIAN-11/5.15.85-1-PVE/X86_64/6D1F207293>) |
| 8086:a1b1 | 15d9:0981 | Intel            | C620 Series Chipset Family Therma... | 5     | intel_p... | [D9B96BCE95](<Server/Supermicro/Super/Super Server/909986EADB14/UBUNTU-22.10/5.19.0-23-GENERIC/X86_64/D9B96BCE95>) |
| 8086:a2b1 | 15d9:098e | Intel            | 200 Series PCH Thermal Subsystem     | 5     |            | [2887A82948](<Server/Supermicro/Super/Super Server/4CD262ADBF12/DEBIAN-11/5.19.11/X86_64/2887A82948>) |
| 8086:a379 | 15d9:1a1f | Intel            | Cannon Lake PCH Thermal Controller   | 5     | intel_p... | [EF92C1FC32](<Server/Supermicro/Super/Super Server/A1AAA9CEAEE9/CENTOS-8/4.18.0-448.EL8.X86_64/X86_64/EF92C1FC32>) |
| 8086:8c24 | 8086:0000 | Intel            | 8 Series Chipset Family Thermal M... | 4     | intel_p... | [7023226F81](<Server/Intel/S1200/S1200RP/832EB05B058D/FEDORA-35/5.16.2-200.FC35.X86_64/X86_64/7023226F81>) |
| 8086:8d24 | 15d9:0831 | Intel            | C610/X99 series chipset Thermal S... | 4     |            | [58E86F0E34](<Server/Supermicro/Super/Super Server/BD4C9B6F043B/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/58E86F0E34>) |
| 8086:a1b1 | 1028:0716 | Intel            | C620 Series Chipset Family Therma... | 4     |            | [02F8E21FA8](<Server/Dell/PowerEdge/PowerEdge R640/D35AD5A42EE7/UBUNTU-20.04/5.4.0-105-GENERIC/X86_64/02F8E21FA8>) |
| 8086:a1b1 | 1028:0737 | Intel            | C620 Series Chipset Family Therma... | 4     | intel_p... | [D2AE46F823](<Server/Dell/XC740xd-12/XC740xd-12 CORE/DD8724B460B5/UBUNTU-18.04/4.15.0-175-GENERIC/X86_64/D2AE46F823>) |
| 8086:a1b1 | 1028:07cb | Intel            | C620 Series Chipset Family Therma... | 4     | intel_p... | [465C40DD0F](<Server/Dell/PowerEdge/PowerEdge T440/1E0687BF68BA/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/465C40DD0F>) |
| 8086:a1b1 | 15d9:091c | Intel            | C620 Series Chipset Family Therma... | 4     | intel_p... | [90F9906D76](<Server/Supermicro/SYS-1029/SYS-1029U-TR25M-BK-LC019/25926C72BE6F/ACRONIS-CYBER-INFRASTRUCTURE-5.1.1/3.10.0-1160.53.1.VZ7.185.3/X86_64/90F9906D76>) |
| 8086:a1b1 | 15d9:0953 | Intel            | C620 Series Chipset Family Therma... | 4     |            | [A76BB2E30D](<Server/Supermicro/SYS-5029/SYS-5029P-WTR/2D889DFAC2FF/ROCKY-8.5/4.18.0-348.12.2.EL8_5.X86_64/X86_64/A76BB2E30D>) |
| 8086:a1b1 | 15d9:0986 | Intel            | C620 Series Chipset Family Therma... | 4     | intel_p... | [FFA58F1702](<Server/Supermicro/SYS-E300/SYS-E300-9D-8CN8TP/202BFE094BD2/DEBIAN-11/5.10.0-21-AMD64/X86_64/FFA58F1702>) |
| 8086:a1b1 | 17aa:1038 | Intel            | C620 Series Chipset Family Therma... | 4     | intel_p... | [7630762F0E](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC001DGE/B0EFE7081048/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/7630762F0E>) |
| 8086:a1b1 | 17aa:7800 | Intel            | C620 Series Chipset Family Therma... | 4     |            | [C97EB83B9C](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 -[7X06CTO1WW]-/7AFAAAD68C64/CENTOS-7/3.10.0-1160.36.2.EL7.X86_64/X86_64/C97EB83B9C>) |
| 8086:1d24 | 15d9:062b | Intel            | C600/X79 series chipset Thermal M... | 3     |            | [21E11AD4FE](<Server/Supermicro/X9/X9SRE-X9SRE-3F-X9SRi-X9SRi-3F/AC4AC10ED873/DEBIAN-11/5.10.0-11-AMD64/X86_64/21E11AD4FE>) |
| 8086:1d24 | 15d9:0660 | Intel            | C600/X79 series chipset Thermal M... | 3     |            | [C088868F62](<Server/Supermicro/X9/X9DRD-iF-LF/F42BB6D21594/DEBIAN-11/5.15.74-1-PVE/X86_64/C088868F62>) |

### Signal processing management (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19a2:0800 | 19a2:0800 | Emulex           | ServerView iRMC HTI                  | 1     |            | [14C76E0C83](<Server/F5 Networks/C/C117/C1512B26FE54/ALPINE-3.13.2/5.10.16-0-LTS/X86_64/14C76E0C83>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a1a3 | 8086:7270 | Intel            | C620 Series Chipset Family SMBus     | 48    | i2c_i801   | [18B2BF9FF4](<Server/Delta Computers/DSS-C621/DSS-C621LTG/EA1701537BF7/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/18B2BF9FF4>) |
| 1022:790b | 15d9:790b | AMD              | FCH SMBus Controller                 | 34    | i2c_pii... | [55AF41B298](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.7/4.18.0-425.19.2.EL8_7.X86_64/X86_64/55AF41B298>) |
| 1022:790b | 1022:790b | AMD              | FCH SMBus Controller                 | 27    | i2c_piix4  | [457ABEF5D3](<Server/ASRockRack/ROMED8/ROMED8-2T/E9A31A87AD3F/ALMA-9.1/6.3.0-2.EL9.ELREPO.X86_64/X86_64/457ABEF5D3>) |
| 8086:8d22 | 103c:8030 | Intel            | C610/X99 series chipset SMBus Con... | 27    | i2c_i801   | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:a1a3 | 8086:35ce | Intel            | C620 Series Chipset Family SMBus     | 21    | i2c_i801   | [F5848D1BA2](<Server/DALCO/S2600/S2600WFT/37B0D5359698/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/F5848D1BA2>) |
| 8086:1d22 | 1043:84ef | Intel            | C600/X79 series chipset SMBus Hos... | 20    | i2c_i801   | [4AC44C74A3](<Server/ASUSTek Computer/Z9PA-D8/Z9PA-D8 Series/0BE952D59456/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/4AC44C74A3>) |
| 8086:a1a3 | 1028:073a | Intel            | C620 Series Chipset Family SMBus     | 20    | i2c_i801   | [962B265260](<Server/Dell/Precision/Precision 7920 Tower/8C7F63FF0FE0/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/962B265260>) |
| 8086:3a30 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 19    | i2c_i801   | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:a123 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 17    | i2c_i801   | [97D3C70FB5](<Server/Quanta/QuantaMicro/QuantaMicro X10E-9N/01ACEA39AAB2/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/97D3C70FB5>) |
| 8086:3a30 | 1014:3a30 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 16    | i2c_i801   | [16C68A28D8](<Server/IBM/System/System x3550 M3 -[7944SCP]-/B3404BB51BF1/DEBIAN-10/4.19.0-20-686-PAE/I686/16C68A28D8>) |
| 8086:8d22 | 15d9:0821 | Intel            | C610/X99 series chipset SMBus Con... | 16    | i2c_i801   | [17BF7A3CBC](<Server/Supermicro/SYS-6018/SYS-6018R-WTR/5EE2BAE645DD/CENTOS-7/3.10.0-862.14.4.EL7.X86_64/X86_64/17BF7A3CBC>) |
| 8086:1d22 | 15d9:0636 | Intel            | C600/X79 series chipset SMBus Hos... | 15    | i2c_i801   | [6994C89077](<Server/Supermicro/X9/X9DRW/6A1A83EBE660/DEBIAN-11/5.15.104-1-PVE/X86_64/6994C89077>) |
| 8086:8d22 | 8086:7270 | Intel            | C610/X99 series chipset SMBus Con... | 15    | i2c_i801   | [37C2630B8F](<Server/INSPUR/SA5212/SA5212M4/4250B01550A6/DEBIAN-11/5.10.0-18-AMD64/X86_64/37C2630B8F>) |
| 8086:1c22 | 1028:04de | Intel            | 6 Series/C200 Series Chipset Fami... | 13    | i2c_i801   | [745C5316F5](<Server/Dell/PowerEdge/PowerEdge T110 II/B75E91D5BD9F/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/745C5316F5>) |
| 8086:3a30 | 8086:3a30 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 12    | i2c_i801   | [5B5D81B1A8](<Server/TYAN Computer/S/S7012/4A43E21507D4/FEDORA-37/6.0.8-300.FC37.X86_64/X86_64/5B5D81B1A8>) |
| 8086:a1a3 | 1028:0715 | Intel            | C620 Series Chipset Family SMBus     | 12    | i2c_i801   | [7AD0D2D67B](<Server/Dell/PowerEdge/PowerEdge R740/FF8CDFB5CB55/UBUNTU-18.04/4.15.0-193-GENERIC/X86_64/7AD0D2D67B>) |
| 8086:a1a3 | 1028:0739 | Intel            | C620 Series Chipset Family SMBus     | 12    | i2c_i801   | [FE6DC0D9C7](<Server/Dell/Precision/Precision 7820 Tower/FB09ECB98D56/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FE6DC0D9C7>) |
| 1022:790b | 1458:1000 | AMD              | FCH SMBus Controller                 | 11    | i2c_piix4  | [7BA797B6A5](<Server/Giga Computing/MC13/MC13-LE0-000/1D7046547004/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/7BA797B6A5>) |
| 8086:1d22 | 1014:1d22 | Intel            | C600/X79 series chipset SMBus Hos... | 11    | i2c_i801   | [BB8E2C7A6D](<Server/IBM/CPU/CPU PLANAR -[8752AC1]/45EC2B958EBD/UBUNTU-22.04/5.15.0-52-GENERIC/X86_64/BB8E2C7A6D>) |
| 8086:8d22 | 15d9:0831 | Intel            | C610/X99 series chipset SMBus Con... | 11    | i2c_i801   | [5E92E7FE1E](<Server/Supermicro/Super/Super Server/FD3A63BBABAD/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/5E92E7FE1E>) |
| 8086:a1a3 | 1043:871e | Intel            | C620 Series Chipset Family SMBus     | 11    | i2c_i801   | [C874A6D28C](<Server/ASUSTek Computer/ESC8000/ESC8000 G4/05733798C837/UBUNTU-18.04/5.4.0-121-GENERIC/X86_64/C874A6D28C>) |
| 8086:a323 | 8086:7270 | Intel            | Cannon Lake PCH SMBus Controller     | 11    | i2c_i801   | [A2FD0BC88C](<Server/Lenovo/ThinkSystem/ThinkSystem SR250 -[7Y51CTO1WW]-/56D35BA12534/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/A2FD0BC88C>) |
| 8086:1c22 | 1043:8497 | Intel            | 6 Series/C200 Series Chipset Fami... | 10    | i2c_i801   | [B559AD98CF](<Server/ASUSTek Computer/P8B-M/P8B-M Series/E1996EEBAA7B/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/B559AD98CF>) |
| 8086:1c22 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 10    | i2c_i801   | [891709C211](<Server/Intel/S1200/S1200BTL/F40AFD7A2D8F/FEDORA-36/6.2.8-100.FC36.X86_64/X86_64/891709C211>) |
| 8086:1d22 | 15d9:0626 | Intel            | C600/X79 series chipset SMBus Hos... | 10    | i2c_i801   | [C4B4851A88](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/5E5B10F103C2/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/C4B4851A88>) |
| 8086:8d22 | 15d9:0857 | Intel            | C610/X99 series chipset SMBus Con... | 10    | i2c_i801   | [A9AA07EF24](<Server/Supermicro/X10/X10SRA-F/446FAE82E232/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/A9AA07EF24>) |
| 8086:a123 | 15d9:089a | Intel            | 100 Series/C230 Series Chipset Fa... | 10    | i2c_i801   | [7AA0EB0936](<Server/Supermicro/Super/Super Server/7660AB944FAA/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/7AA0EB0936>) |
| 8086:3a30 | 8086:34dc | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 9     | i801_smbus | [5C00E2D415](<Server/Intel/S5520/S5520HC/42DF18E9A677/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/5C00E2D415>) |
| 8086:8c22 | 15d9:0801 | Intel            | 8 Series/C220 Series Chipset Fami... | 9     | i2c_i801   | [6CE8B7FB26](<Server/Supermicro/X10/X10SLL-F/34D1B7FAB08F/NIXOS-22.11/5.15.96/X86_64/6CE8B7FB26>) |
| 8086:8c22 | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 9     | i2c_i801   | [210B2E16E3](<Server/Supermicro/Super/Super Server/9DEEB33699DA/GENTOO-2.13/5.15.75-GENTOO-DIST/X86_64/210B2E16E3>) |
| 8086:8c22 | 8086:35b5 | Intel            | 8 Series/C220 Series Chipset Fami... | 9     | i2c_i801   | [28F4CEB8EE](<Server/Intel/S1200/S1200RP/FB9A925E61E5/ARCH-ROLLING/5.19.13-ARCH1-1/X86_64/28F4CEB8EE>) |
| 8086:8c22 | 8086:8c22 | Intel            | 8 Series/C220 Series Chipset Fami... | 9     | i2c_i801   | [44B55B4721](<Server/ASUSTek Computer/P9D-M/P9D-M Series/61497326D129/MANJARO/5.15.108-1-MANJARO/X86_64/44B55B4721>) |
| 1002:4385 | 15d9:ab11 | AMD              | SBx00 SMBus Controller               | 8     | i2c_piix4  | [E673BAB21F](<Server/Supermicro/H8/H8QG6/539918058863/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/E673BAB21F>) |
| 1002:4385 | 15d9:bc11 | AMD              | SBx00 SMBus Controller               | 8     | i2c_piix4  | [EF32C0C2CA](<Server/Supermicro/H8/H8DG6-H8DGi/8E20B1D3526C/UBUNTU-18.04/4.15.0-200-GENERIC/X86_64/EF32C0C2CA>) |
| 1022:790b | 1028:08fc | AMD              | FCH SMBus Controller                 | 8     | i2c_pii... | [237A3CD682](<Server/Dell/PowerEdge/PowerEdge R6515/647C815644AA/DEBIAN-12/6.1.0-5-AMD64/X86_64/237A3CD682>) |
| 8086:8d22 | 1043:85f6 | Intel            | C610/X99 series chipset SMBus Con... | 8     | i2c_i801   | [74269B72B0](<Server/ASUSTek Computer/Z10PE-D16/Z10PE-D16 WS/9FCE74D7C651/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/74269B72B0>) |
| 8086:a1a3 | 15d9:096d | Intel            | C620 Series Chipset Family SMBus     | 8     | i2c_i801   | [DCBB3D117A](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.4.0-105-GENERIC/X86_64/DCBB3D117A>) |
| 8086:1d22 | 15d9:062a | Intel            | C600/X79 series chipset SMBus Hos... | 7     | i2c_i801   | [2E9D55D3A7](<Server/Supermicro/X9/X9SRA-X9SRA-3/E73ED86A7227/DEBIAN-11/5.10.0-14-AMD64/X86_64/2E9D55D3A7>) |
| 8086:2930 | 8086:34d0 | Intel            | 82801I (ICH9 Family) SMBus Contro... | 7     | i2c_i801   | [40FC7CD8AA](<Server/Intel/S3210/S3210SH/D6FE7FA8CA14/DEBIAN-11/5.15.30-2-PVE/X86_64/40FC7CD8AA>) |
| 8086:3a30 | 15d9:0001 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 7     | i2c_i801   | [C2BD925732](<Server/DEPO Computers/X8/X8DT3/81F58A958C06/POP!_OS-22.04/6.0.6-76060006-GENERIC/X86_64/C2BD925732>) |
| 8086:3a30 | 15d9:0400 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 7     | i2c_i801   | [AD4ABE60CD](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/03637143A526/XUBUNTU-20.04/5.11.0-37-GENERIC/X86_64/AD4ABE60CD>) |
| 8086:3a30 | 15d9:0600 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 7     | i2c_i801   | [6012DE6351](<Server/Supermicro/X8/X8DTU/17EEEE82432B/LINUXMINT-20.2/5.4.0-131-GENERIC/X86_64/6012DE6351>) |
| 8086:8c22 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 7     | i2c_i801   | [3FACB2E9A7](<Server/Others/Others/Others/C6A8EA21A292/UBUNTU-18.04/4.15.0-196-GENERIC/X86_64/3FACB2E9A7>) |
| 8086:a1a3 | 15d9:0967 | Intel            | C620 Series Chipset Family SMBus     | 7     | i2c_i801   | [DE3332B83C](<Server/Supermicro/SYS-6029/SYS-6029P-WTRT/35C50F3639E9/ACRONIS-CYBER-INFRASTRUCTURE-5.1.0/3.10.0-1160.53.1.VZ7.185.3/X86_64/DE3332B83C>) |
| 8086:a1a3 | 17aa:7808 | Intel            | C620 Series Chipset Family SMBus     | 7     | i2c_i801   | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 1002:4385 | 1028:0444 | AMD              | SBx00 SMBus Controller               | 6     | i2c_piix4  | [13BD99E4BC](<Server/Dell/PowerEdge/PowerEdge R815/0D8B6921A323/KUBUNTU-22.10/5.19.0-1021-LOWLATENCY/X86_64/13BD99E4BC>) |
| 1022:790b | 1028:08ff | AMD              | FCH SMBus Controller                 | 6     | i2c_piix4  | [77F946C99B](<Server/Dell/PowerEdge/PowerEdge R7525/ED52A1D54F9D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/77F946C99B>) |
| 8086:1c22 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | i2c_i801   | [7C80F5ACE7](<Server/Dell/PowerEdge/PowerEdge R210 II/6D45D032BCEA/UBUNTU-22.04/5.15.0-47-GENERIC/X86_64/7C80F5ACE7>) |
| 8086:3a30 | 15d9:0100 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 6     | i2c_i801   | [71610CE997](<Server/Supermicro/X8/X8DAH/6A1E9F33BACC/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/71610CE997>) |
| 8086:3a30 | 1734:114d | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 6     | i2c_i801   | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a1f0 | 1028:073a | Intel            | Lewisburg MROM 0                     | 19    | snd_hda... | [962B265260](<Server/Dell/Precision/Precision 7920 Tower/8C7F63FF0FE0/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/962B265260>) |
| 1102:0012 | 1102:0010 | Creative Labs    | CA0132 Sound Core3D [Sound Blaste... | 13    | snd_hda... | [53F4F127F2](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/E89F11C69464/MAKULU-2022.12.29/5.15.0-56-GENERIC/X86_64/53F4F127F2>) |
| 8086:3a3e | 15d9:0006 | Intel            | 82801JI (ICH10 Family) HD Audio C... | 13    | snd_hda... | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 13f6:0111 | 13f6:0111 | C-Media Elect... | CMI8738/CMI8768 PCI Audio            | 12    | snd_cmipci | [AD555BFDE2](<Server/Dell/PowerEdge/PowerEdge T430/F2945010DA0E/ARCH-ROLLING/6.3.0-273-TKG-PDS-LLVM/X86_64/AD555BFDE2>) |
| 8086:a1f0 | 1028:0739 | Intel            | Lewisburg MROM 0                     | 12    | snd_hda... | [FE6DC0D9C7](<Server/Dell/Precision/Precision 7820 Tower/FB09ECB98D56/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FE6DC0D9C7>) |
| 1002:aae0 | 1002:aae0 | AMD              | Baffin HDMI/DP Audio [Radeon RX 5... | 10    | snd_hda... | [D59B9FF270](<Server/Phytium/FT-2000/FT-2000-4/813EFFC1A7D1/ATZ-11.6/5.10.0-22-ARM64/AARCH64/D59B9FF270>) |
| 8086:8d20 | 15d9:0857 | Intel            | C610/X99 series chipset HD Audio ... | 10    | snd_hda... | [A9AA07EF24](<Server/Supermicro/X10/X10SRA-F/446FAE82E232/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/A9AA07EF24>) |
| 10de:10f8 | 1028:12a0 | Nvidia           | TU104 HD Audio Controller            | 9     | snd_hda... | [962B265260](<Server/Dell/Precision/Precision 7920 Tower/8C7F63FF0FE0/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/962B265260>) |
| 10de:0e0f | 1462:8c93 | Nvidia           | GK208 HDMI/DP Audio Controller       | 8     | snd_hda... | [6012DE6351](<Server/Supermicro/X8/X8DTU/17EEEE82432B/LINUXMINT-20.2/5.4.0-131-GENERIC/X86_64/6012DE6351>) |
| 8086:1d20 | 1043:84d8 | Intel            | C600/X79 series chipset High Defi... | 8     | snd_hda... | [12DBE88BAB](<Server/ASUSTek Computer/Z9PE-D8/Z9PE-D8 WS/0342B2EECEF7/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/12DBE88BAB>) |
| 8086:a1f0 | 15d9:096d | Intel            | Lewisburg MROM 0                     | 8     | snd_hda... | [DCBB3D117A](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.4.0-105-GENERIC/X86_64/DCBB3D117A>) |
| 8086:a348 | 8086:7270 | Intel            | Cannon Lake PCH cAVS                 | 8     | snd_hda... | [196C8EB317](<Server/Neousys Technology/Nuvo-7100VTC/Nuvo-7100VTC Series/E44E3E216941/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/196C8EB317>) |
| 1002:aab0 | 174b:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 7     | snd_hda... | [C425CE191D](<Server/Rackable Systems/KAURI/KAURI/35311A1382DF/LINUXMINT-20/5.4.0-113-GENERIC/X86_64/C425CE191D>) |
| 1002:aaf8 | 1002:aaf8 | AMD              | Vega 10 HDMI Audio [Radeon Vega 5... | 7     | snd_hda... | [A42E535407](<Server/Dell/Precision/Precision Rack 7910/B0CC6989B61E/UBUNTU-20.04/5.13.0-39-GENERIC/X86_64/A42E535407>) |
| 8086:1d20 | 15d9:062a | Intel            | C600/X79 series chipset High Defi... | 7     | snd_hda... | [2E9D55D3A7](<Server/Supermicro/X9/X9SRA-X9SRA-3/E73ED86A7227/DEBIAN-11/5.10.0-14-AMD64/X86_64/2E9D55D3A7>) |
| 1002:1637 | 1002:1637 | AMD              | Renoir Radeon High Definition Aud... | 6     | snd_hda... | [D6E47A7C18](<Server/BESSTAR Tech/X/X500/81B31475FFFF/XEROLINUX-KDE-ROLLING/5.17.9-ARCH1-1/X86_64/D6E47A7C18>) |
| 1002:ab28 | 1002:ab28 | AMD              | Navi 21/23 HDMI/DP Audio Controller  | 6     | snd_hda... | [5145E7D26E](<Server/Supermicro/C7/C7Z370-CG-IW/66BE2E39DAA0/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/5145E7D26E>) |
| 1022:15e3 | 14f1:0200 | AMD              | Family 17h/19h HD Audio Controller   | 6     | snd_hda... | [D6E47A7C18](<Server/BESSTAR Tech/X/X500/81B31475FFFF/XEROLINUX-KDE-ROLLING/5.17.9-ARCH1-1/X86_64/D6E47A7C18>) |
| 10de:0e0f | 196e:118b | Nvidia           | GK208 HDMI/DP Audio Controller       | 6     | snd_hda... | [3A68279F78](<Server/IBM/System/System x3650 -[7979AC1]-/D68394872CF7/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/3A68279F78>) |
| 8086:1d20 | 1043:851b | Intel            | C600/X79 series chipset High Defi... | 6     | snd_hda... | [FCD4A2D840](<Server/ASUSTek Computer/Z9PA-D8/Z9PA-D8 Series/36C037E8E5B4/UBUNTU-22.10/5.19.0-26-GENERIC/X86_64/FCD4A2D840>) |
| 8086:3a3e | 15d9:0100 | Intel            | 82801JI (ICH10 Family) HD Audio C... | 6     | snd_hda... | [71610CE997](<Server/Supermicro/X8/X8DAH/6A1E9F33BACC/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/71610CE997>) |
| 8086:3a3e | 8086:3a3e | Intel            | 82801JI (ICH10 Family) HD Audio C... | 6     | snd_hda... | [844D96FCD7](<Server/TYAN Computer/S/S7025/65136A7FAD48/GENTOO-2.8/5.18.12-GENTOO-X86_64/X86_64/844D96FCD7>) |
| 8086:8c20 | 15d9:0805 | Intel            | 8 Series/C220 Series Chipset High... | 6     | snd_hda... | [4B0CFEC9A7](<Server/Supermicro/X10/X10SAE/FF0B31A8C494/NOBARA-37/6.2.10-200.FSYNC.FC37.X86_64/X86_64/4B0CFEC9A7>) |
| 8086:a1f0 | 103c:81c7 | Intel            | Lewisburg MROM 0                     | 6     | snd_hda... | [50CCA471C5](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/010A19E087DC/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/50CCA471C5>) |
| 8086:a348 | 15d9:1a1d | Intel            | Cannon Lake PCH cAVS                 | 6     | snd_hda... | [065427C37F](<Server/Supermicro/Super/Super Server/2CF7574245C0/DEBIAN-11/5.10.162-1.LAT5.10.0-21/X86_64/065427C37F>) |
| 1002:aae0 | 1028:aae0 | AMD              | Baffin HDMI/DP Audio [Radeon RX 5... | 5     | snd_hda... | [065427C37F](<Server/Supermicro/Super/Super Server/2CF7574245C0/DEBIAN-11/5.10.162-1.LAT5.10.0-21/X86_64/065427C37F>) |
| 1102:0007 | 1102:100a | Creative Labs    | CA0106/CA0111 [SB Live!/Audigy/X-... | 5     | snd_ca0106 | [E7C499BC85](<Server/Intel/S1200/S1200BTL/C10DA3F7FBBC/UBUNTU-22.04/5.15.0-52-GENERIC/X86_64/E7C499BC85>) |
| 8086:3a3e | 8086:34e2 | Intel            | 82801JI (ICH10 Family) HD Audio C... | 5     | snd_hda... | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:a170 | 15d9:0895 | Intel            | 100 Series/C230 Series Chipset Fa... | 5     | snd_hda... | [CE6BAA4FDA](<Server/Supermicro/Super/Super Server/A842905AAA3B/UBUNTU-18.04/5.4.0-132-GENERIC/X86_64/CE6BAA4FDA>) |
| 8086:a1f0 | 103c:81c6 | Intel            | Lewisburg MROM 0                     | 5     | snd_hda... | [C60CE01C1E](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/5FDF871A62B0/UBUNTU-20.04/5.15.0-48-GENERIC/X86_64/C60CE01C1E>) |
| 1002:9840 | 1002:9840 | AMD              | Kabini HDMI/DP Audio                 | 4     | snd_hda... | [01D2615C22](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/00C05E8C85AC/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/01D2615C22>) |
| 1002:aa68 | 1462:aa68 | AMD              | Cedar HDMI Audio [Radeon HD 5400/... | 4     | snd_hda... | [8EF63CB2DE](<Server/Dell/PowerEdge/PowerEdge T420/B103D6C87C65/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/8EF63CB2DE>) |
| 1002:aa98 | 1028:aa98 | AMD              | Caicos HDMI Audio [Radeon HD 6450... | 4     | snd_hda... | [5D6883F1BB](<Server/Others/0JP31P/0JP31P A16/77D7AC607011/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/5D6883F1BB>) |
| 1002:aab0 | 1028:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 4     | snd_hda... | [6CE8B7FB26](<Server/Supermicro/X10/X10SLL-F/34D1B7FAB08F/NIXOS-22.11/5.15.96/X86_64/6CE8B7FB26>) |
| 1002:aab0 | 1043:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 4     | snd_hda... | [79E6EAFC82](<Server/Supermicro/Super/Super Server/EA582B67D89D/DEBIAN-11/5.13.19-2-PVE/X86_64/79E6EAFC82>) |
| 1002:aaf0 | 1458:aaf0 | AMD              | Ellesmere HDMI Audio [Radeon RX 4... | 4     | snd_hda... | [AD555BFDE2](<Server/Dell/PowerEdge/PowerEdge T430/F2945010DA0E/ARCH-ROLLING/6.3.0-273-TKG-PDS-LLVM/X86_64/AD555BFDE2>) |
| 1002:aaf0 | 1682:aaf0 | AMD              | Ellesmere HDMI Audio [Radeon RX 4... | 4     | snd_hda... | [5C00E2D415](<Server/Intel/S5520/S5520HC/42DF18E9A677/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/5C00E2D415>) |
| 10de:0371 | 10de:cb84 | Nvidia           | MCP55 High Definition Audio          | 4     | snd_hda... | [1888FA6DF7](<Server/MSI/MCP/MCP55/E26C4EDDD3C1/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/1888FA6DF7>) |
| 10de:0e0a | 10de:1096 | Nvidia           | GK104 HDMI Audio Controller          | 4     | snd_hda... | [F508BB4C99](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/40A1E58B45BA/POP!_OS-20.10/5.8.0-7625-GENERIC/X86_64/F508BB4C99>) |
| 10de:0fbb | 10de:1153 | Nvidia           | GM204 High Definition Audio Contr... | 4     | snd_hda... | [BA5FEBE33B](<Server/Dell/PowerEdge/PowerEdge R730/B08360FD5D56/UBUNTU-20.04/5.15.0-67-GENERIC/X86_64/BA5FEBE33B>) |
| 10de:0fbc | 3842:3753 | Nvidia           | GM107 High Definition Audio Contr... | 4     | snd_hda... | [B61612A8A8](<Server/Supermicro/X10/X10SLV/70EC260C4E93/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/B61612A8A8>) |
| 10de:10f0 | 1028:11a3 | Nvidia           | GP104 High Definition Audio Contr... | 4     | snd_hda... | [84012F61FF](<Server/Dell/Precision/Precision 7920 Tower/1749395571DC/RHEL-9/5.14.0-70.26.1.EL9_0.X86_64/X86_64/84012F61FF>) |
| 10de:10f0 | 103c:11a3 | Nvidia           | GP104 High Definition Audio Contr... | 4     | snd_hda... | [2AD477EA6C](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/5E9B675190B8/ZORIN-16/5.15.0-67-GENERIC/X86_64/2AD477EA6C>) |
| 10de:10f0 | 10de:11a3 | Nvidia           | GP104 High Definition Audio Contr... | 4     | snd_hda... | [1D6082EFE8](<Server/Lenovo/ThinkStation/ThinkStation P720 30BBS21C01/FE8DF4F9C290/FEDORA-37/6.2.11-200.FC37.X86_64/X86_64/1D6082EFE8>) |
| 10de:10f7 | 1458:37c4 | Nvidia           | TU102 High Definition Audio Contr... | 4     | snd_hda... | [C874A6D28C](<Server/ASUSTek Computer/ESC8000/ESC8000 G4/05733798C837/UBUNTU-18.04/5.4.0-121-GENERIC/X86_64/C874A6D28C>) |
| 10de:1aef | 10de:147d | Nvidia           | GA102 High Definition Audio Contr... | 4     | snd_hda... | [A7C222100E](<Server/Dell/Precision/Precision 7920 Tower/4FFAA8A7598E/LINUXMINT-21.1/5.15.0-67-GENERIC/X86_64/A7C222100E>) |
| 13f6:8788 | 1043:8521 | C-Media Elect... | CMI8788 [Oxygen HD Audio]            | 4     | snd_oxygen | [4AC44C74A3](<Server/ASUSTek Computer/Z9PA-D8/Z9PA-D8 Series/0BE952D59456/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/4AC44C74A3>) |
| 8086:0c0c | 15d9:0805 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 4     | snd_hda... | [019914CC29](<Server/Supermicro/X10/X10SAE/6D8BBA911035/GENTOO-2.7/5.13.12-GENTOO/X86_64/019914CC29>) |
| 8086:1bc8 | 8086:7270 | Intel            | Audio device                         | 4     | snd_hda... | [3DDB00DA94](<Server/Intel/ArcherCity/ArcherCity/35F42C801DE0/FEDORA-37/6.1.7-200.FC37.X86_64/X86_64/3DDB00DA94>) |
| 8086:a1f0 | 1043:8724 | Intel            | Lewisburg MROM 0                     | 4     | snd_hda... | [3035FDAD91](<Server/ASUSTek Computer/WS-C621E-SAGE/WS-C621E-SAGE Series/E86AFFE0F80D/KUBUNTU-20.04/5.4.0-97-GENERIC/X86_64/3035FDAD91>) |

### Storage (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1077:2532 | 1077:015d | QLogic           | ISP2532-based 8Gb Fibre Channel t... | 14    | qla2xxx    | [C4B4851A88](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/5E5B10F103C2/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/C4B4851A88>) |
| 10df:f0e5 | 10df:f0e5 | Emulex           | Zephyr LightPulse Fibre Channel H... | 4     | lpfc       | [73B5A8C763](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/1567E7B66486/UBUNTU-20.04/5.4.0-137-GENERIC/X86_64/73B5A8C763>) |
| 11f8:8032 |           | PMC-Sierra       | PM8032 Tachyon QE8                   | 4     |            | [029040A622](<Server/Dell/PowerEdge/PowerEdge R240/7ED18DB7AC28/UBUNTU-20.04/5.15.0-48-GENERIC/X86_64/029040A622>) |
| 1077:2432 | 1077:0137 | QLogic           | ISP2432-based 4Gb Fibre Channel t... | 3     | qla2xxx    | [B85DBD88F5](<Server/IBM/System/System x3650 M2 -[7947AC1]-/B4AFB5C90D39/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/B85DBD88F5>) |
| 10df:f100 | 10df:f100 | Emulex           | LPe12000 Series 8Gb Fibre Channel... | 3     | lpfc       | [00E39935AA](<Server/Fujitsu/PRIMERGY/PRIMERGY RX300 S7/B732C00110CF/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/00E39935AA>) |
| 11f8:8032 | 117c:003b | PMC-Sierra       | PM8032 Tachyon QE8                   | 3     | celerit... | [FB8C0A4C3A](<Server/Dell/PowerEdge/PowerEdge R730/1F01BE7E44C8/UBUNTU-18.04/4.15.0-88-GENERIC/X86_64/FB8C0A4C3A>) |
| 1077:2432 | 103c:7041 | QLogic           | ISP2432-based 4Gb Fibre Channel t... | 2     | qla2xxx    | [3BF8EDF992](<Server/Others/A/A06/03B41DA567E8/RHEL-8/4.18.0-348.12.2.EL8_5.X86_64/X86_64/3BF8EDF992>) |
| 1077:2532 | 1077:015c | QLogic           | ISP2532-based 8Gb Fibre Channel t... | 2     | qla2xxx    | [1A5CF39F4F](<Server/IBM/System/System x3650 M4 -[7915AC1]/2D2939361294/UBUNTU-20.04/5.11.0-36-GENERIC/X86_64/1A5CF39F4F>) |
| 1077:2532 | 1077:015e | QLogic           | ISP2532-based 8Gb Fibre Channel t... | 2     | qla2xxx    | [C43FD89A0B](<Server/IBM/System/System x3850 X5 -[7143Y61]-/32036814BD3E/OPENSUSE-TUMBLEWEED-XXXXXXXX/5.9.14-1-DEFAULT/X86_64/C43FD89A0B>) |
| 1aed:2001 | 1590:006f | SanDisk          | ioDrive2                             | 2     |            | [D9B96BCE95](<Server/Supermicro/Super/Super Server/909986EADB14/UBUNTU-22.10/5.19.0-23-GENERIC/X86_64/D9B96BCE95>) |
| 1aed:2001 | 1aed:2001 | SanDisk          | ioDrive2                             | 2     |            | [26B693742E](<Server/Dell/PowerEdge/PowerEdge R810/A7C91C5C7A32/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/26B693742E>) |
| 1000:0646 | 1000:1020 | Broadcom / LSI   | FC949ES Fibre Channel Adapter        | 1     | mptfc      | [8F6E544820](<Server/Sun Microsystems/Sun/Sun Fire X4270 SERVER/38FCB3A1E58B/FEDORA-34/5.11.11-300.FC34.X86_64/X86_64/8F6E544820>) |
| 1000:0646 | 1000:1240 | Broadcom / LSI   | FC949ES Fibre Channel Adapter        | 1     |            | [107B5509E6](<Server/Dell/PowerEdge/PowerEdge R210/42576B36F606/FEDORA-35/5.4.198-300.FC35.X86_64/X86_64/107B5509E6>) |
| 1077:2031 | 103c:1939 | QLogic           | ISP8324-based 16Gb Fibre Channel ... | 1     | qla2xxx    | [9036136416](<Server/Hewlett-Packard/Superdome2/Superdome2 16s x86/777124CB43C9/ROSA-SX-CHROME-1.0/2.6.32-504.EL6.X86_64/X86_64/9036136416>) |
| 1077:2031 | 1077:0249 | QLogic           | ISP8324-based 16Gb Fibre Channel ... | 1     | qla2xxx    | [77A5A8BF12](<Server/Others/0JP31P/0JP31P A14/025EA12C2DA6/UBUNTU-18.08.39/4.10.0-38-GENERIC/X86_64/77A5A8BF12>) |
| 1077:2031 | 1077:0257 | QLogic           | ISP8324-based 16Gb Fibre Channel ... | 1     | qla2xxx    | [CBFB7C31D8](<Server/Dell/PowerEdge/PowerEdge R510/739618260755/UBUNTU-18.04/4.15.0-29-GENERIC/X86_64/CBFB7C31D8>) |
| 1077:2261 | 1077:02af | QLogic           | ISP2722-based 16/32Gb Fibre Chann... | 1     | qla2xxx    | [2AE35CF194](<Server/Lenovo/ThinkSystem/ThinkSystem SR630 -[7X02CTO1WW]-/D0074D37A357/UBUNTU-20.04/5.4.0-62-GENERIC/X86_64/2AE35CF194>) |
| 1077:2281 | 1077:02f3 | QLogic           | ISP2812-based 64/32G Fibre Channe... | 1     | qla2xxx    | [77F946C99B](<Server/Dell/PowerEdge/PowerEdge R7525/ED52A1D54F9D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/77F946C99B>) |
| 1077:2312 | 1077:0100 | QLogic           | ISP2312-based 2Gb Fibre Channel t... | 1     | qla2xxx    | [40F9D31598](<Server/Dell/PowerEdge/PowerEdge 2850/8C9CA6088BC7/CENTOS-6/2.6.32-754.30.2.EL6.X86_64/X86_64/40F9D31598>) |
| 1077:2432 | 103c:1705 | QLogic           | ISP2432-based 4Gb Fibre Channel t... | 1     | qla2xxx    | [DC4AC74B49](<Server/Hewlett-Packard/ProLiant/ProLiant BL685c G7/3F69ABE6ED6B/OPENSUSE-LEAP-15.2/5.3.18-LP152.60-DEFAULT/X86_64/DC4AC74B49>) |
| 1077:2432 | 103c:7040 | QLogic           | ISP2432-based 4Gb Fibre Channel t... | 1     | qla2xxx    | [B4EF3B8086](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G5/A36E86AAD166/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/B4EF3B8086>) |
| 1077:2432 | 1077:0138 | QLogic           | ISP2432-based 4Gb Fibre Channel t... | 1     | qla2xxx... | [A43842B263](<Server/Supermicro/Super/Super Server/C70B4058D7CB/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/A43842B263>) |
| 1077:2532 | 1077:0171 | QLogic           | ISP2532-based 8Gb Fibre Channel t... | 1     | qla2xxx    | [4F5756D065](<Server/Oracle/Sun/Sun Fire X4270 M2 SERVER/FF52124EF1E7/FEDORA-32/5.8.12-200.FC32.X86_64/X86_64/4F5756D065>) |
| 1077:2532 | 1077:0176 | QLogic           | ISP2532-based 8Gb Fibre Channel t... | 1     | qla2xxx    | [D7CBC31CEE](<Server/IBM/BladeCenter/BladeCenter HS23 -[7875MFM]-/D5DD0E377016/RELS-6.9/2.6.32-696.EL6.X86_64/X86_64/D7CBC31CEE>) |
| 10df:e300 | 10df:e310 | Emulex           | LPe31000/LPe32000 Series 16Gb/32G... | 1     | lpfc       | [0ACE3642F0](<Server/Zvezda/Iridium/Iridium/5567EC687189/CENTOS-9/5.14.0-148.EL9.X86_64/X86_64/0ACE3642F0>) |
| 10df:f100 | 103c:3282 | Emulex           | LPe12000 Series 8Gb Fibre Channel... | 1     | lpfc       | [23F12250E5](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/C92D3D39B250/RHEL-8/4.18.0-240.22.1.EL8_3.X86_64/X86_64/23F12250E5>) |
| 10df:f400 | 10df:f410 | Emulex           | LPe35000/LPe36000 Series 32Gb/64G... | 1     | lpfc       | [9320E12A9A](<Server/Dell/PowerEdge/PowerEdge R6515/38E4D8545292/DEBIAN-11/5.10.0-8-AMD64/X86_64/9320E12A9A>) |
| 10df:fe00 | 10df:fe00 | Emulex           | Zephyr-X LightPulse Fibre Channel... | 1     | lpfc       | [6806624961](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G6/97C666008E4E/UBUNTU-18.04/4.15.0-50-GENERIC/X86_64/6806624961>) |
| 1137:0045 | 1137:012e | Cisco Systems    | VIC FCoE HBA                         | 1     | fnic       | [BAF3069CD7](<Server/Cisco Systems/UCSC-C220/UCSC-C220-M4S/9D3781D2096F/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/BAF3069CD7>) |
| 117c:0064 | 117c:0064 | ATTO Technology  | Celerity FC 16Gb/s Gen 5 Fibre Ch... | 1     |            | [43EE2001E1](<Server/AIC/SB302/SB302-LB/77AF6612F1D7/CENTOS-7/3.10.0-1062.4.1.EL7.X86_64/X86_64/43EE2001E1>) |
| 11f8:8032 | 117c:003a | PMC-Sierra       | PM8032 Tachyon QE8                   | 1     | celerit... | [5315690568](<Server/Supermicro/SYS-5018/SYS-5018D-FN8T/3DFAD0AEC112/UBUNTU-18.04/4.15.0-55-GENERIC/X86_64/5315690568>) |
| 1425:6607 | 1425:0000 | Chelsio Commu... | T62100-LP-CR Unified Wire Storage... | 1     |            | [1126AE11AE](<Server/ASUSTek Computer/Z11PG-D16/Z11PG-D16 Series/9878F56186D3/DEBIAN-9/4.9.35-DYVI/X86_64/1126AE11AE>) |
| 19a2:0702 | 103c:3314 | Emulex           | OneConnect 10Gb iSCSI Initiator      | 1     | be2iscsi   | [DC4AC74B49](<Server/Hewlett-Packard/ProLiant/ProLiant BL685c G7/3F69ABE6ED6B/OPENSUSE-LEAP-15.2/5.3.18-LP152.60-DEFAULT/X86_64/DC4AC74B49>) |
| 19a2:0704 | 103c:174b | Emulex           | OneConnect OCe10100/OCe10102 Seri... | 1     | lpfc       | [E707BBA6A9](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G7/941269F514A4/UBUNTU-18.04/4.15.0-91-GENERIC/X86_64/E707BBA6A9>) |
| 19a2:0712 | 103c:337b | Emulex           | OneConnect 10Gb iSCSI Initiator (... | 1     | be2iscsi   | [9F21E5D9D9](<Server/Hewlett-Packard/ProLiant/ProLiant BL460c Gen8/1DB9D4472AA8/ARCH-ROLLING/5.10.79-1-LTS/X86_64/9F21E5D9D9>) |
| 19e5:0203 | 19e5:d301 | Huawei Techno... | Hi1822 Family (2*16G FC)             | 1     |            | [F548D0A0A9](<Server/HUAWEI/TaiShan/TaiShan 200/7F69DEB6BBD3/RELS-2019.1/5.10.42-GENERIC-1ROSA2019.1-ARM64/AARCH64/F548D0A0A9>) |
| 1aed:2001 | 1014:0432 | SanDisk          | ioDrive2                             | 1     |            | [BB8E2C7A6D](<Server/IBM/CPU/CPU PLANAR -[8752AC1]/45EC2B958EBD/UBUNTU-22.04/5.15.0-52-GENERIC/X86_64/BB8E2C7A6D>) |
| 1aed:2001 | 1028:1f70 | SanDisk          | ioDrive2                             | 1     |            | [1AFA47E662](<Server/Dell/PowerEdge/PowerEdge R810/8C29BCCFEEB7/UBUNTU-20.04/5.4.0-67-GENERIC/X86_64/1AFA47E662>) |
| 1aed:2001 | 1028:1f71 | SanDisk          | ioDrive2                             | 1     |            | [4707D5CBF3](<Server/Dell/PowerEdge/PowerEdge R810/A7C91C5C7A32/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/4707D5CBF3>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a1d2 | 8086:7270 | Intel            | C620 Series Chipset Family SSATA ... | 44    | ahci       | [18B2BF9FF4](<Server/Delta Computers/DSS-C621/DSS-C621LTG/EA1701537BF7/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/18B2BF9FF4>) |
| 8086:a182 | 8086:7270 | Intel            | C620 Series Chipset Family SATA C... | 38    | ahci       | [18B2BF9FF4](<Server/Delta Computers/DSS-C621/DSS-C621LTG/EA1701537BF7/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/18B2BF9FF4>) |
| 1022:7901 | 15d9:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 32    | ahci       | [55AF41B298](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.7/4.18.0-425.19.2.EL8_7.X86_64/X86_64/55AF41B298>) |
| 1022:7901 | 1022:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 23    | ahci       | [A3F043A03C](<Server/Supermicro/M12/M12SWA-TF/4F883AA311F8/UBUNTU-22.04/5.15.0-33-GENERIC/X86_64/A3F043A03C>) |
| 8086:1d02 | 103c:18a9 | Intel            | C600/X79 series chipset 6-Port SA... | 20    | ahci       | [1D9FE6158B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/13E3015456A0/DEBIAN-11/5.11.22-5-PVE/X86_64/1D9FE6158B>) |
| 8086:1d02 | 1043:84ef | Intel            | C600/X79 series chipset 6-Port SA... | 20    | ahci       | [4AC44C74A3](<Server/ASUSTek Computer/Z9PA-D8/Z9PA-D8 Series/0BE952D59456/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/4AC44C74A3>) |
| 8086:a1d2 | 1028:073a | Intel            | C620 Series Chipset Family SSATA ... | 20    | ahci       | [962B265260](<Server/Dell/Precision/Precision 7920 Tower/8C7F63FF0FE0/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/962B265260>) |
| 8086:a102 | 8086:7270 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 17    | ahci       | [97D3C70FB5](<Server/Quanta/QuantaMicro/QuantaMicro X10E-9N/01ACEA39AAB2/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/97D3C70FB5>) |
| 8086:1d02 | 15d9:0636 | Intel            | C600/X79 series chipset 6-Port SA... | 15    | ahci       | [6994C89077](<Server/Supermicro/X9/X9DRW/6A1A83EBE660/DEBIAN-11/5.15.104-1-PVE/X86_64/6994C89077>) |
| 8086:3a22 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) SATA AHCI ... | 14    | ahci       | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 1b21:0612 | 15d9:1b2b | ASMedia Techn... | ASM1062 Serial ATA Controller        | 13    | ahci       | [3E3CB25241](<Server/Supermicro/AS/AS -1014S-WTRT/4D11B8584472/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/3E3CB25241>) |
| 1b4b:9230 | 1b4b:9230 | Marvell Techn... | 88SE9230 PCIe 2.0 x2 4-port SATA ... | 13    | ahci       | [01D2615C22](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/00C05E8C85AC/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/01D2615C22>) |
| 8086:1d02 | 1028:048c | Intel            | C600/X79 series chipset 6-Port SA... | 13    | ahci       | [6A0AF69B4A](<Server/Dell/PowerEdge/PowerEdge R720/F424DE07066D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6A0AF69B4A>) |
| 8086:1d02 | 1028:04fa | Intel            | C600/X79 series chipset 6-Port SA... | 13    | ahci       | [8EE7146669](<Server/Dell/PowerEdge/PowerEdge T320/6878B1DE0919/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/8EE7146669>) |
| 8086:8d02 | 15d9:0821 | Intel            | C610/X99 series chipset 6-Port SA... | 13    | ahci       | [57FC9BDF47](<Server/Supermicro/Super/Super Server/872E890D3A71/CENTOS-7/3.10.0-862.14.4.EL7.X86_64/X86_64/57FC9BDF47>) |
| 8086:8d62 | 15d9:0821 | Intel            | C610/X99 series chipset sSATA Con... | 13    | ahci       | [57FC9BDF47](<Server/Supermicro/Super/Super Server/872E890D3A71/CENTOS-7/3.10.0-862.14.4.EL7.X86_64/X86_64/57FC9BDF47>) |
| 8086:8d02 | 8086:7270 | Intel            | C610/X99 series chipset 6-Port SA... | 12    | ahci       | [D07F57B566](<Server/Supermicro/X10/X10DRi/E17F7CC264F8/UBUNTU-22.10/5.19.0-29-GENERIC/X86_64/D07F57B566>) |
| 8086:a182 | 1028:0715 | Intel            | C620 Series Chipset Family SATA C... | 12    | ahci       | [7AD0D2D67B](<Server/Dell/PowerEdge/PowerEdge R740/FF8CDFB5CB55/UBUNTU-18.04/4.15.0-193-GENERIC/X86_64/7AD0D2D67B>) |
| 8086:a1d2 | 1028:0715 | Intel            | C620 Series Chipset Family SSATA ... | 12    | ahci       | [7AD0D2D67B](<Server/Dell/PowerEdge/PowerEdge R740/FF8CDFB5CB55/UBUNTU-18.04/4.15.0-193-GENERIC/X86_64/7AD0D2D67B>) |
| 1002:4391 | 1002:4391 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 11    | ahci       | [3955B91269](<Server/Hewlett-Packard/ProLiant/ProLiant DL165 G7/1979FBF2D488/DEBIAN-11/5.15.39-4-PVE/X86_64/3955B91269>) |
| 8086:1c02 | 1028:04de | Intel            | 6 Series/C200 Series Chipset Fami... | 11    | ahci       | [154F8780DE](<Server/Dell/PowerEdge/PowerEdge T110 II/C81C1D060430/ROCKY-9.1/5.14.0-162.12.1.EL9_1.0.2.X86_64/X86_64/154F8780DE>) |
| 1022:7901 | 1458:1000 | AMD              | FCH SATA Controller [AHCI mode]      | 10    | ahci       | [DEF4067C8E](<Server/Gigabyte Technology/G242/G242-Z11-00/B5251D581093/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/DEF4067C8E>) |
| 8086:8d02 | 1028:0601 | Intel            | C610/X99 series chipset 6-Port SA... | 10    | ahci       | [1ABE023ED7](<Server/Dell/PowerEdge/PowerEdge R630/0354475C3BDD/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/1ABE023ED7>) |
| 8086:8d02 | 103c:8030 | Intel            | C610/X99 series chipset 6-Port SA... | 10    | ahci       | [5F85FDADF1](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/C986ADB0FAC7/DEBIAN-11/5.15.74-1-PVE/X86_64/5F85FDADF1>) |
| 8086:8d02 | 15d9:0831 | Intel            | C610/X99 series chipset 6-Port SA... | 10    | ahci       | [5E92E7FE1E](<Server/Supermicro/Super/Super Server/FD3A63BBABAD/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/5E92E7FE1E>) |
| 8086:8d62 | 1028:0601 | Intel            | C610/X99 series chipset sSATA Con... | 10    | ahci       | [1ABE023ED7](<Server/Dell/PowerEdge/PowerEdge R630/0354475C3BDD/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/1ABE023ED7>) |
| 8086:8d62 | 8086:7270 | Intel            | C610/X99 series chipset sSATA Con... | 10    | ahci       | [D07F57B566](<Server/Supermicro/X10/X10DRi/E17F7CC264F8/UBUNTU-22.10/5.19.0-29-GENERIC/X86_64/D07F57B566>) |
| 8086:a102 | 15d9:089a | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 10    | ahci       | [7AA0EB0936](<Server/Supermicro/Super/Super Server/7660AB944FAA/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/7AA0EB0936>) |
| 8086:a182 | 1043:871e | Intel            | C620 Series Chipset Family SATA C... | 10    | ahci       | [C874A6D28C](<Server/ASUSTek Computer/ESC8000/ESC8000 G4/05733798C837/UBUNTU-18.04/5.4.0-121-GENERIC/X86_64/C874A6D28C>) |
| 1b4b:9230 | 1043:84fa | Marvell Techn... | 88SE9230 PCIe 2.0 x2 4-port SATA ... | 9     | ahci       | [12DBE88BAB](<Server/ASUSTek Computer/Z9PE-D8/Z9PE-D8 WS/0342B2EECEF7/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/12DBE88BAB>) |
| 8086:1c02 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 9     | ahci       | [6D9FF27DE2](<Server/Intel/S1200/S1200BTL/F40AFD7A2D8F/DEBIAN-11/5.10.0-9-AMD64/X86_64/6D9FF27DE2>) |
| 8086:1d02 | 15d9:0626 | Intel            | C600/X79 series chipset 6-Port SA... | 9     | ahci       | [C4B4851A88](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/5E5B10F103C2/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/C4B4851A88>) |
| 8086:8c02 | 8086:35b5 | Intel            | 8 Series/C220 Series Chipset Fami... | 9     | ahci       | [28F4CEB8EE](<Server/Intel/S1200/S1200RP/FB9A925E61E5/ARCH-ROLLING/5.19.13-ARCH1-1/X86_64/28F4CEB8EE>) |
| 1022:7901 | 1028:08fc | AMD              | FCH SATA Controller [AHCI mode]      | 8     | ahci       | [237A3CD682](<Server/Dell/PowerEdge/PowerEdge R6515/647C815644AA/DEBIAN-12/6.1.0-5-AMD64/X86_64/237A3CD682>) |
| 1b4b:9230 | 1028:1fe2 | Marvell Techn... | 88SE9230 PCIe 2.0 x2 4-port SATA ... | 8     | ahci       | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:1d02 | 1014:1d02 | Intel            | C600/X79 series chipset 6-Port SA... | 8     | ahci       | [BB8E2C7A6D](<Server/IBM/CPU/CPU PLANAR -[8752AC1]/45EC2B958EBD/UBUNTU-22.04/5.15.0-52-GENERIC/X86_64/BB8E2C7A6D>) |
| 8086:8c02 | 15d9:0801 | Intel            | 8 Series/C220 Series Chipset Fami... | 8     | ahci       | [6CE8B7FB26](<Server/Supermicro/X10/X10SLL-F/34D1B7FAB08F/NIXOS-22.11/5.15.96/X86_64/6CE8B7FB26>) |
| 8086:8c02 | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 8     | ahci       | [210B2E16E3](<Server/Supermicro/Super/Super Server/9DEEB33699DA/GENTOO-2.13/5.15.75-GENTOO-DIST/X86_64/210B2E16E3>) |
| 8086:8c02 | 8086:8c02 | Intel            | 8 Series/C220 Series Chipset Fami... | 8     | ahci       | [44B55B4721](<Server/ASUSTek Computer/P9D-M/P9D-M Series/61497326D129/MANJARO/5.15.108-1-MANJARO/X86_64/44B55B4721>) |
| 8086:8d02 | 15d9:0857 | Intel            | C610/X99 series chipset 6-Port SA... | 8     | ahci       | [A9AA07EF24](<Server/Supermicro/X10/X10SRA-F/446FAE82E232/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/A9AA07EF24>) |
| 8086:8d62 | 1043:85f7 | Intel            | C610/X99 series chipset sSATA Con... | 8     | ahci       | [74269B72B0](<Server/ASUSTek Computer/Z10PE-D16/Z10PE-D16 WS/9FCE74D7C651/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/74269B72B0>) |
| 8086:8d62 | 15d9:0831 | Intel            | C610/X99 series chipset sSATA Con... | 8     | ahci       | [5E92E7FE1E](<Server/Supermicro/Super/Super Server/FD3A63BBABAD/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/5E92E7FE1E>) |
| 8086:8d62 | 15d9:0857 | Intel            | C610/X99 series chipset sSATA Con... | 8     | ahci       | [6A333A499D](<Server/Supermicro/X10/X10SRA/0DAF404C22AB/GENTOO-2.7/5.14.14-GENTOO-X86_64/X86_64/6A333A499D>) |
| 8086:a182 | 15d9:096d | Intel            | C620 Series Chipset Family SATA C... | 8     | ahci       | [DCBB3D117A](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.4.0-105-GENERIC/X86_64/DCBB3D117A>) |
| 8086:a1d2 | 15d9:096d | Intel            | C620 Series Chipset Family SSATA ... | 8     | ahci       | [DCBB3D117A](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.4.0-105-GENERIC/X86_64/DCBB3D117A>) |
| 8086:a352 | 8086:7270 | Intel            | Cannon Lake PCH SATA AHCI Controller | 8     | ahci       | [196C8EB317](<Server/Neousys Technology/Nuvo-7100VTC/Nuvo-7100VTC Series/E44E3E216941/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/196C8EB317>) |
| 8086:1d02 | 1028:04f8 | Intel            | C600/X79 series chipset 6-Port SA... | 7     | ahci       | [87EE1B58E4](<Server/Dell/PowerEdge/PowerEdge R420/BACBDE063781/DEBIAN-11/5.10.0-19-AMD64/X86_64/87EE1B58E4>) |
| 8086:3b22 | 1028:02a6 | Intel            | 5 Series/3400 Series Chipset 6 po... | 7     | ahci       | [0D3437E666](<Server/Dell/PowerEdge/PowerEdge T110/E57797C8A6CF/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/0D3437E666>) |
| 8086:8c02 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 7     | ahci       | [3FACB2E9A7](<Server/Others/Others/Others/C6A8EA21A292/UBUNTU-18.04/4.15.0-196-GENERIC/X86_64/3FACB2E9A7>) |
| 8086:8d02 | 1028:0600 | Intel            | C610/X99 series chipset 6-Port SA... | 7     | ahci       | [BE75097D0F](<Server/Dell/PowerEdge/PowerEdge R730/E686E52F7B47/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/BE75097D0F>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1d00 | 103c:18a9 | Intel            | C600/X79 series chipset 4-Port SA... | 41    | pata_acpi  | [517DA38F28](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/283652467D28/DEBIAN-11/5.19.17-2-PVE/X86_64/517DA38F28>) |
| 8086:3a20 | 103c:330d | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 30    | pata_acpi  | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |
| 8086:2921 | 1028:0235 | Intel            | 82801IB (ICH9) 2 port SATA Contro... | 21    | pata_acpi  | [BC1B2F4337](<Server/Dell/PowerEdge/PowerEdge R710/4BD52918C3EA/UBUNTU-22.10/5.19.0-30-GENERIC/X86_64/BC1B2F4337>) |
| 8086:a1bc | 1028:073a | Intel            | C620 Series Chipset Family IDE Re... | 20    | pata_acpi  | [962B265260](<Server/Dell/Precision/Precision 7920 Tower/8C7F63FF0FE0/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/962B265260>) |
| 8086:269e | 103c:31fe | Intel            | 631xESB/632xESB IDE Controller       | 17    | pata_acpi  | [8CF84909E3](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G5/CB5A662BC228/CENTOS-7/3.10.0-1160.88.1.EL7.X86_64/X86_64/8CF84909E3>) |
| 8086:3a20 | 1014:3a20 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 16    | pata_acpi  | [16C68A28D8](<Server/IBM/System/System x3550 M3 -[7944SCP]-/B3404BB51BF1/DEBIAN-10/4.19.0-20-686-PAE/I686/16C68A28D8>) |
| 8086:3a26 | 1014:3a26 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 14    | pata_acpi  | [16C68A28D8](<Server/IBM/System/System x3550 M3 -[7944SCP]-/B3404BB51BF1/DEBIAN-10/4.19.0-20-686-PAE/I686/16C68A28D8>) |
| 8086:2921 | 1028:0236 | Intel            | 82801IB (ICH9) 2 port SATA Contro... | 13    | pata_acpi  | [1A2EE8A8D5](<Server/Dell/PowerEdge/PowerEdge R610/37A92833E6A5/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/1A2EE8A8D5>) |
| 8086:3b20 | 1028:02a4 | Intel            | 5 Series/3400 Series Chipset 4 po... | 12    | ata_pii... | [83C0F8E7E5](<Server/Dell/PowerEdge/PowerEdge T310/0EAF01173A25/DEBIAN-11/5.15.79+TRUENAS/X86_64/83C0F8E7E5>) |
| 8086:3b26 | 1028:02a4 | Intel            | 5 Series/3400 Series Chipset 2 po... | 12    | ata_pii... | [83C0F8E7E5](<Server/Dell/PowerEdge/PowerEdge T310/0EAF01173A25/DEBIAN-11/5.15.79+TRUENAS/X86_64/83C0F8E7E5>) |
| 8086:a1bc | 1028:0739 | Intel            | C620 Series Chipset Family IDE Re... | 12    | pata_acpi  | [FE6DC0D9C7](<Server/Dell/Precision/Precision 7820 Tower/FB09ECB98D56/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FE6DC0D9C7>) |
| 8086:3a20 | 8086:3a20 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 9     | ata_piix   | [5B5D81B1A8](<Server/TYAN Computer/S/S7012/4A43E21507D4/FEDORA-37/6.0.8-300.FC37.X86_64/X86_64/5B5D81B1A8>) |
| 197b:2368 | 197b:2368 | JMicron Techn... | JMB368 IDE controller                | 8     | pata_jm... | [71610CE997](<Server/Supermicro/X8/X8DAH/6A1E9F33BACC/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/71610CE997>) |
| 8086:3a26 | 8086:3a26 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 8     | ata_piix   | [5B5D81B1A8](<Server/TYAN Computer/S/S7012/4A43E21507D4/FEDORA-37/6.0.8-300.FC37.X86_64/X86_64/5B5D81B1A8>) |
| 8086:3a20 | 1028:028c | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 7     | pata_acpi  | [C0B7421A8B](<Server/Dell/PowerEdge/PowerEdge R410/5EF56DA48933/DEBIAN-11/5.10.0-21-AMD64/X86_64/C0B7421A8B>) |
| 8086:3a20 | 8086:34dc | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 7     | ata_piix   | [5C00E2D415](<Server/Intel/S5520/S5520HC/42DF18E9A677/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/5C00E2D415>) |
| 8086:3a26 | 1028:028c | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 7     | pata_acpi  | [C0B7421A8B](<Server/Dell/PowerEdge/PowerEdge R410/5EF56DA48933/DEBIAN-11/5.10.0-21-AMD64/X86_64/C0B7421A8B>) |
| 8086:3a26 | 8086:34dc | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 7     | ata_piix   | [5C00E2D415](<Server/Intel/S5520/S5520HC/42DF18E9A677/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/5C00E2D415>) |
| 1002:439c | 15d9:ab11 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 6     | pata_at... | [E673BAB21F](<Server/Supermicro/H8/H8QG6/539918058863/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/E673BAB21F>) |
| 8086:1d08 | 103c:18a9 | Intel            | C600/X79 series chipset 2-Port SA... | 6     | ata_pii... | [709C3A84EA](<Server/Hewlett-Packard/ProLiant/ProLiant DL360e Gen8/2D56A8DFCCB8/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/709C3A84EA>) |
| 8086:269e | 1028:01b2 | Intel            | 631xESB/632xESB IDE Controller       | 6     | pata_acpi  | [75A840C1D8](<Server/Dell/PowerEdge/PowerEdge 2950/C63204CC3467/UBUNTU-16.04/4.4.0-194-GENERIC/X86_64/75A840C1D8>) |
| 8086:269e | 1028:01b3 | Intel            | 631xESB/632xESB IDE Controller       | 6     | pata_acpi  | [2E77448A7D](<Server/Dell/PowerEdge/PowerEdge 1950/9FAD7399F359/DEBIAN-11/5.15.74-1-PVE/X86_64/2E77448A7D>) |
| 8086:2921 | 1028:0237 | Intel            | 82801IB (ICH9) 2 port SATA Contro... | 6     | pata_acpi  | [27B873F279](<Server/Dell/PowerEdge/PowerEdge T610/6017AFDBEA6B/UBUNTU-20.04/5.13.0-44-GENERIC/X86_64/27B873F279>) |
| 1002:439c | 103c:1773 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 5     | pata_at... | [1DBD0517E3](<Server/Hewlett-Packard/ProLiant/ProLiant DL585 G7/0239B15EF9C8/DEBIAN-11/5.10.0-16-AMD64/X86_64/1DBD0517E3>) |
| 1002:439c | 15d9:bc11 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 5     | pata_at... | [EF32C0C2CA](<Server/Supermicro/H8/H8DG6-H8DGi/8E20B1D3526C/UBUNTU-18.04/4.15.0-200-GENERIC/X86_64/EF32C0C2CA>) |
| 8086:2680 | 1028:01b3 | Intel            | 631xESB/632xESB/3100 Chipset SATA... | 5     | pata_acpi  | [2FF8924B15](<Server/Dell/PowerEdge/PowerEdge 1950/12946989497B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2FF8924B15>) |
| 8086:3a20 | 1028:028d | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 5     | pata_acpi  | [BE1989F55D](<Server/Dell/PowerEdge/PowerEdge T410/A09633725563/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/BE1989F55D>) |
| 8086:3a20 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 5     | ata_pii... | [A3BE5CDF41](<Server/Supermicro/X8/X8DTL/26E707D77C6B/CENTOS-7/3.10.0-1160.83.1.EL7.X86_64/X86_64/A3BE5CDF41>) |
| 8086:3a20 | 15d9:0600 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 5     | pata_acpi  | [A421259AA2](<Server/Supermicro/X8/X8DTU/1F0E06E0B056/UBUNTU-20.04/5.4.0-110-GENERIC/X86_64/A421259AA2>) |
| 8086:3a20 | 8086:34e2 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 5     | pata_acpi  | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3a26 | 1028:028d | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 5     | pata_acpi  | [BE1989F55D](<Server/Dell/PowerEdge/PowerEdge T410/A09633725563/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/BE1989F55D>) |
| 8086:3a26 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 5     | ata_pii... | [A3BE5CDF41](<Server/Supermicro/X8/X8DTL/26E707D77C6B/CENTOS-7/3.10.0-1160.83.1.EL7.X86_64/X86_64/A3BE5CDF41>) |
| 8086:3a26 | 15d9:0600 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 5     | pata_acpi  | [A421259AA2](<Server/Supermicro/X8/X8DTU/1F0E06E0B056/UBUNTU-20.04/5.4.0-110-GENERIC/X86_64/A421259AA2>) |
| 8086:3a26 | 8086:34e2 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 5     | pata_acpi  | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 1002:439c | 103c:3338 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 4     | pata_at... | [3955B91269](<Server/Hewlett-Packard/ProLiant/ProLiant DL165 G7/1979FBF2D488/DEBIAN-11/5.15.39-4-PVE/X86_64/3955B91269>) |
| 1002:439c | 15d9:ba11 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 4     | pata_at... | [9EE42DCF6F](<Server/Supermicro/H8/H8SCM/4FE36F650E5D/DEBIAN-10/4.19.0-23-AMD64/X86_64/9EE42DCF6F>) |
| 10de:036e | 1462:cb84 | Nvidia           | MCP55 IDE                            | 4     | pata_am... | [1888FA6DF7](<Server/MSI/MCP/MCP55/E26C4EDDD3C1/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/1888FA6DF7>) |
| 10de:037f | 1462:cb84 | Nvidia           | MCP55 SATA Controller                | 4     | sata_nv... | [1888FA6DF7](<Server/MSI/MCP/MCP55/E26C4EDDD3C1/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/1888FA6DF7>) |
| 8086:269e | 8086:3476 | Intel            | 631xESB/632xESB IDE Controller       | 4     | pata_acpi  | [38109F9919](<Server/Intel/S5000/S5000PSL/26C6E7EE0282/UBUNTU-20.04/5.4.0-33-GENERIC/X86_64/38109F9919>) |
| 8086:27c0 | 1028:01e7 | Intel            | NM10/ICH7 Family SATA Controller ... | 4     | pata_acpi  | [EA66809CE7](<Server/Dell/PowerEdge/PowerEdge 840/E4DBE564B603/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/EA66809CE7>) |
| 8086:27df | 1028:01e7 | Intel            | 82801G (ICH7 Family) IDE Controller  | 4     | pata_acpi  | [EA66809CE7](<Server/Dell/PowerEdge/PowerEdge 840/E4DBE564B603/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/EA66809CE7>) |
| 8086:2921 | 1028:029b | Intel            | 82801IB (ICH9) 2 port SATA Contro... | 4     | ata_pii... | [CB579EF51B](<Server/Dell/PowerEdge/PowerEdge T710/F46F2AE8BCC3/MX-21/5.14.0-4MX-AMD64/X86_64/CB579EF51B>) |
| 8086:3a20 | 1028:02f1 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 4     | pata_acpi  | [51412400BA](<Server/Dell/PowerEdge/PowerEdge R510/9C3341952849/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/51412400BA>) |
| 8086:3a20 | 15d9:0400 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 4     | ata_pii... | [AD4ABE60CD](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/03637143A526/XUBUNTU-20.04/5.11.0-37-GENERIC/X86_64/AD4ABE60CD>) |
| 8086:3a20 | 1734:1150 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 4     | pata_acpi  | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:3a20 | 8086:34da | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 4     | pata_acpi  | [FE3D758C20](<Server/Intel/S5500/S5500BC/EB1E1FCFB3A4/KDE-NEON-20.04/5.4.0-66-GENERIC/X86_64/FE3D758C20>) |
| 8086:3a26 | 1028:02f1 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 4     | pata_acpi  | [51412400BA](<Server/Dell/PowerEdge/PowerEdge R510/9C3341952849/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/51412400BA>) |
| 8086:3a26 | 15d9:0400 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 4     | ata_pii... | [AD4ABE60CD](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/03637143A526/XUBUNTU-20.04/5.11.0-37-GENERIC/X86_64/AD4ABE60CD>) |
| 8086:3a26 | 1734:114d | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 4     | pata_acpi  | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |
| 8086:3a26 | 8086:34da | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 4     | pata_acpi  | [FE3D758C20](<Server/Intel/S5500/S5500BC/EB1E1FCFB3A4/KDE-NEON-20.04/5.4.0-66-GENERIC/X86_64/FE3D758C20>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 71    | nvme       | [89E91928BB](<Server/Supermicro/Super/Super Server/ECB64B8152DF/DEBIAN-11/6.2.6-1-PVE/X86_64/89E91928BB>) |
| 144d:a80a | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 16    | nvme       | [9384FEF88D](<Server/Supermicro/Super/Super Server/0D2971EB9E61/GENTOO-2.13/6.1.12-GENTOO.AF/X86_64/9384FEF88D>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 15    | nvme       | [1D6082EFE8](<Server/Lenovo/ThinkStation/ThinkStation P720 30BBS21C01/FE8DF4F9C290/FEDORA-37/6.2.11-200.FC37.X86_64/X86_64/1D6082EFE8>) |
| 144d:a80a | 144d:a812 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 12    | nvme       | [7BA797B6A5](<Server/Giga Computing/MC13/MC13-LE0-000/1D7046547004/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/7BA797B6A5>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 10    | nvme       | [457ABEF5D3](<Server/ASRockRack/ROMED8/ROMED8-2T/E9A31A87AD3F/ALMA-9.1/6.3.0-2.EL9.ELREPO.X86_64/X86_64/457ABEF5D3>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 9     | nvme       | [9384FEF88D](<Server/Supermicro/Super/Super Server/0D2971EB9E61/GENTOO-2.13/6.1.12-GENTOO.AF/X86_64/9384FEF88D>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013 E13 NVMe Controller           | 8     | nvme       | [D59B9FF270](<Server/Phytium/FT-2000/FT-2000-4/813EFFC1A7D1/ATZ-11.6/5.10.0-22-ARM64/AARCH64/D59B9FF270>) |
| 8086:0a54 | 8086:4802 | Intel            | NVMe Datacenter SSD [3DNAND, Beta... | 8     | nvme       | [22275687F9](<Server/Inspur/NF5280/NF5280M6/C83E955B75CA/CENTOS-8/5.15.15/X86_64/22275687F9>) |
| 8086:f1a6 | 8086:390b | Intel            | SSD Pro 7600p/760p/E 6100p Series    | 8     | nvme       | [A7C222100E](<Server/Dell/Precision/Precision 7920 Tower/4FFAA8A7598E/LINUXMINT-21.1/5.15.0-67-GENERIC/X86_64/A7C222100E>) |
| 126f:2262 | 126f:2262 | Silicon Motion   | SM2262/SM2262EN SSD Controller       | 7     | nvme       | [93DBB217B4](<Server/Dell/Precision/Precision 7920 Tower/F038BB2DE013/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/93DBB217B4>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT SSD Controller     | 7     | nvme       | [030B77C94D](<Server/Gigabyte Technology/C621/C621-WD12-IPMI/5E4783EDD64C/ROCKY-8.7/4.18.0-425.13.1.EL8_7.X86_64/X86_64/030B77C94D>) |
| 1344:5405 | 1344:0100 | Micron Techno... | NVMe Storage Controller              | 7     | nvme       | [962B265260](<Server/Dell/Precision/Precision 7920 Tower/8C7F63FF0FE0/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/962B265260>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980              | 7     | nvme       | [457ABEF5D3](<Server/ASRockRack/ROMED8/ROMED8-2T/E9A31A87AD3F/ALMA-9.1/6.3.0-2.EL9.ELREPO.X86_64/X86_64/457ABEF5D3>) |
| 144d:a80a | 144d:a813 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 7     | nvme       | [C88CBA109A](<Server/ASRockRack/ROMED8/ROMED8-2T/9F9114A5632E/DEBIAN-11/5.10.0-21-AMD64/X86_64/C88CBA109A>) |
| 14a4:2300 | 1b4b:1093 | Lite-On Techn... | Non-Volatile memory controller       | 6     | nvme       | [4391DFF8D2](<Server/Others/Others/Others/29E67FFE5E37/UBUNTU-18.04/4.18.0-20-GENERIC/X86_64/4391DFF8D2>) |
| 1344:51a2 | 1344:5000 | Micron Techno... | 7300 PRO NVMe SSD                    | 5     | nvme       | [DE3332B83C](<Server/Supermicro/SYS-6029/SYS-6029P-WTRT/35C50F3639E9/ACRONIS-CYBER-INFRASTRUCTURE-5.1.0/3.10.0-1160.53.1.VZ7.185.3/X86_64/DE3332B83C>) |
| 15b7:5002 | 15b7:5002 | SanDisk          | WD Black 2018/SN750 / PC SN720 NV... | 5     | nvme       | [12DBE88BAB](<Server/ASUSTek Computer/Z9PE-D8/Z9PE-D8 WS/0342B2EECEF7/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/12DBE88BAB>) |
| 15b7:5009 | 15b7:5009 | SanDisk          | WD Blue SN550 NVMe SSD               | 5     | nvme       | [1DF72E1613](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/2D28DE8C0BFA/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/1DF72E1613>) |
| 8086:0953 | 8086:3702 | Intel            | PCIe Data Center SSD                 | 5     | nvme       | [B0100C59BB](<Server/Supermicro/Super/Super Server/E58401D9CAE3/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/B0100C59BB>) |
| c0a9:5412 | c0a9:0100 | Micron/Crucia... | NVMe Storage Controller              | 5     | nvme       | [DE3332B83C](<Server/Supermicro/SYS-6029/SYS-6029P-WTRT/35C50F3639E9/ACRONIS-CYBER-INFRASTRUCTURE-5.1.0/3.10.0-1160.53.1.VZ7.185.3/X86_64/DE3332B83C>) |
| 1179:011a | 1179:0001 | Toshiba Ameri... | XG6 NVMe SSD Controller              | 4     | nvme       | [FE6DC0D9C7](<Server/Dell/Precision/Precision 7820 Tower/FB09ECB98D56/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FE6DC0D9C7>) |
| 1344:51a2 | 1344:4000 | Micron Techno... | 7300 PRO NVMe SSD                    | 4     | nvme       | [18B2BF9FF4](<Server/Delta Computers/DSS-C621/DSS-C621LTG/EA1701537BF7/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/18B2BF9FF4>) |
| 1344:51b2 | 1344:5000 | Micron Techno... | 9300 MAX NVMe SSD                    | 4     | nvme       | [2BB4102B1C](<Server/Supermicro/Super/Super Server/45717F18B5CF/CENTOS-8/4.18.0-240.22.1.EL8_3.X86_64/X86_64/2BB4102B1C>) |
| 15b7:5006 | 15b7:5006 | SanDisk          | WD Black SN750 / PC SN730 NVMe SSD   | 4     | nvme       | [9384FEF88D](<Server/Supermicro/Super/Super Server/0D2971EB9E61/GENTOO-2.13/6.1.12-GENTOO.AF/X86_64/9384FEF88D>) |
| 15b7:501a | 15b7:501a | SanDisk          | WD Blue SN570 NVMe SSD               | 4     | nvme       | [13BD99E4BC](<Server/Dell/PowerEdge/PowerEdge R815/0D8B6921A323/KUBUNTU-22.10/5.19.0-1021-LOWLATENCY/X86_64/13BD99E4BC>) |
| 1987:5016 | 1987:5016 | Phison Electr... | E16 PCIe4 NVMe Controller            | 4     | nvme       | [A3F043A03C](<Server/Supermicro/M12/M12SWA-TF/4F883AA311F8/UBUNTU-22.04/5.15.0-33-GENERIC/X86_64/A3F043A03C>) |
| 2646:500d | 2646:500d | Kingston Tech... | OM3PDP3 NVMe SSD                     | 4     | nvme       | [D6E47A7C18](<Server/BESSTAR Tech/X/X500/81B31475FFFF/XEROLINUX-KDE-ROLLING/5.17.9-ARCH1-1/X86_64/D6E47A7C18>) |
| 1179:0116 | 1179:0001 | Toshiba Ameri... | XG5 NVMe SSD Controller              | 3     | nvme       | [72D2AA925F](<Server/Dell/Precision/Precision 7920 Tower/54C8E21B1E1D/FEDORA-34/5.17.4-100.FC34.X86_64/X86_64/72D2AA925F>) |
| 1bc0:1002 | 1bc0:1002 | Innodisk         | PCIe 3TE6 Controller                 | 3     | nvme       | [8382988CA9](<Server/Supermicro/Super/Super Server/BC9F8E43AF76/DEBIAN-11/5.15.107-1-PVE/X86_64/8382988CA9>) |
| 1e4b:1202 | 1e4b:1202 | MAXIO Technol... | NVMe SSD Controller MAP1202          | 3     | nvme       | [4AC44C74A3](<Server/ASUSTek Computer/Z9PA-D8/Z9PA-D8 Series/0BE952D59456/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/4AC44C74A3>) |
| 2646:2263 | 2646:2263 | Kingston Tech... | A2000 NVMe SSD                       | 3     | nvme       | [FFA58F1702](<Server/Supermicro/SYS-E300/SYS-E300-9D-8CN8TP/202BFE094BD2/DEBIAN-11/5.10.0-21-AMD64/X86_64/FFA58F1702>) |
| 2646:500f | 2646:500f | Kingston Tech... | NVMe Controller                      | 3     | nvme       | [ABFEE9C5F7](<Server/Gigabyte Technology/MX33/MX33-BS0-00/2E0D4C1B34E3/KUBUNTU-22.04/5.17.0-1017-OEM/X86_64/ABFEE9C5F7>) |
| 8086:0b60 | 8086:9008 | Intel            | NVMe DC SSD [3DNAND, Sentinel Roc... | 3     | nvme       | [30A24A8B24](<Server/Inspur/NF5280/NF5280M6/B52F93BB957F/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/30A24A8B24>) |
| 1344:5407 | 1344:0100 | Micron Techno... | NVMe Storage Controller              | 2     | nvme       | [6161A05CF1](<Server/Supermicro/Super/Super Server/46FD6D462182/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/6161A05CF1>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 2     | nvme       | [3702B80721](<Server/Lenovo/ThinkSystem/ThinkSystem SR358FV2 Reserved for BaseBoard Vendor/4BD29175E918/KUBUNTU-22.10/5.19.0-26-GENERIC/AARCH64/3702B80721>) |
| 144d:a821 | 108e:a803 | Samsung Elect... | NVMe SSD Controller 172X             | 2     | nvme       | [BE75097D0F](<Server/Dell/PowerEdge/PowerEdge R730/E686E52F7B47/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/BE75097D0F>) |
| 144d:a824 | 1028:2044 | Samsung Elect... | NVMe SSD Controller PM173X           | 2     | nvme       | [F5274874B0](<Server/Dell/PowerEdge/PowerEdge R450/3684EA8CEBA1/DEBIAN-11/5.10.0-18-AMD64/X86_64/F5274874B0>) |
| 144d:a824 | 1028:2127 | Samsung Elect... | NVMe SSD Controller PM173X           | 2     | nvme       | [E02734E72E](<Server/Dell/PowerEdge/PowerEdge R750/369267D116AD/UBUNTU-20.04/5.4.0-137-GENERIC/X86_64/E02734E72E>) |
| 1b96:2400 | 1b96:0000 | Western Digital  | Ultrastar DC SN640 NVMe SSD          | 2     | nvme       | [90F9906D76](<Server/Supermicro/SYS-1029/SYS-1029U-TR25M-BK-LC019/25926C72BE6F/ACRONIS-CYBER-INFRASTRUCTURE-5.1.1/3.10.0-1160.53.1.VZ7.185.3/X86_64/90F9906D76>) |
| 1c5c:1959 | 1c5c:1959 | SK hynix         | Platinum P41 NVMe Solid State Dri... | 2     | nvme       | [8200458C21](<Server/ASRockRack/ROMED8/ROMED8-2T/6773052154E7/UBUNTU-20.04/5.4.0-135-GENERIC/X86_64/8200458C21>) |
| 1dee:2262 | 1dee:1dee | Biwin Storage... | Non-Volatile memory controller       | 2     | nvme       | [0CF218F7BF](<Server/Supermicro/X10/X10DRi/4A89D595337C/RHEL-8/5.13.13-1.EL8.ELREPO.X86_64/X86_64/0CF218F7BF>) |
| 2646:2262 | 2646:2262 | Kingston Tech... | KC2000 NVMe SSD                      | 2     | nvme       | [55AF41B298](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.7/4.18.0-425.19.2.EL8_7.X86_64/X86_64/55AF41B298>) |
| 2646:5008 | 2646:5008 | Kingston Tech... | U-SNS8154P3 NVMe SSD                 | 2     | nvme       | [5FD1A2D6E1](<Server/Supermicro/Super/Super Server/C341EAB89194/GENTOO-2.9/5.15.83-GENTOO-DIST/X86_64/5FD1A2D6E1>) |
| 8086:0953 | 8086:3705 | Intel            | PCIe Data Center SSD                 | 2     | nvme       | [2A41E48C27](<Server/Intel/S1200/S1200SP/D1D1E80179A7/UBUNTU-21.04/5.11.0-38-GENERIC/X86_64/2A41E48C27>) |
| 8086:0953 | 8086:370d | Intel            | PCIe Data Center SSD                 | 2     | nvme       | [28F4CEB8EE](<Server/Intel/S1200/S1200RP/FB9A925E61E5/ARCH-ROLLING/5.19.13-ARCH1-1/X86_64/28F4CEB8EE>) |
| 8086:0a54 | 8086:4703 | Intel            | NVMe Datacenter SSD [3DNAND, Beta... | 2     | nvme       | [22275687F9](<Server/Inspur/NF5280/NF5280M6/C83E955B75CA/CENTOS-8/5.15.15/X86_64/22275687F9>) |
| 8086:0a54 | 8086:4714 | Intel            | NVMe Datacenter SSD [3DNAND, Beta... | 2     | nvme       | [F5848D1BA2](<Server/DALCO/S2600/S2600WFT/37B0D5359698/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/F5848D1BA2>) |
| 8086:0a54 | 8086:4812 | Intel            | NVMe Datacenter SSD [3DNAND, Beta... | 2     | nvme       | [1CDD61E1CC](<Server/Supermicro/SYS-510/SYS-510P-MR/7AA16CCEF58D/ARCO-ROLLING/5.16.11-ARCH1-1/X86_64/1CDD61E1CC>) |
| 8086:2522 | 8086:3802 | Intel            | NVMe Optane Memory Series            | 2     | nvme       | [CDCA826585](<Server/Supermicro/Super/Super Server/67F50154C8D4/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/CDCA826585>) |
| 8086:2700 | 8086:3900 | Intel            | Optane SSD 900P Series               | 2     | nvme       | [376BED560D](<Server/Supermicro/X9/X9DRD-7LN4F-X9DRD-EF/E23334E6B08A/VIRTUOZZO-7.0.11/3.10.0-957.12.2.VZ7.96.21/X86_64/376BED560D>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 103c:323a | 103c:3245 | Hewlett-Packard  | Smart Array G6 controllers           | 57    | hpsa       | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |
| 103c:323b | 103c:3354 | Hewlett-Packard  | Smart Array Gen8 Controllers         | 45    | hpsa       | [961A066E6B](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/F726BB41B090/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/961A066E6B>) |
| 1000:0060 | 1028:1f0c | LSI Logic / S... | MegaRAID SAS 1078                    | 32    | megarai... | [FDC74A5707](<Server/Dell/PowerEdge/PowerEdge R510/6F87FD15852A/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/FDC74A5707>) |
| 8086:201d | 8086:0000 | Intel            | Volume Management Device NVMe RAI... | 31    | vmd        | [FE6DC0D9C7](<Server/Dell/Precision/Precision 7820 Tower/FB09ECB98D56/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FE6DC0D9C7>) |
| 1000:0079 | 1028:1f17 | LSI Logic / S... | MegaRAID SAS 2108 [Liberator]        | 29    | megarai... | [0E5CEE5637](<Server/Dell/PowerEdge/PowerEdge R715/E2B668AC841B/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/0E5CEE5637>) |
| 103c:3239 | 103c:21c0 | Hewlett-Packard  | Smart Array Gen9 Controllers         | 21    | hpsa       | [9AB6FD4AE0](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/E449FEB445B7/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/9AB6FD4AE0>) |
| 1000:005f | 1028:1f44 | LSI Logic / S... | MegaRAID SAS-3 3008 [Fury]           | 19    | megarai... | [4D9F06CA7B](<Server/Dell/PowerEdge/PowerEdge T330/99156426010E/DEBIAN-11/5.10.0-20-AMD64/X86_64/4D9F06CA7B>) |
| 1000:005d | 1028:1f47 | LSI Logic / S... | MegaRAID SAS-3 3108 [Invader]        | 18    | megarai... | [BE75097D0F](<Server/Dell/PowerEdge/PowerEdge R730/E686E52F7B47/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/BE75097D0F>) |
| 1000:005b | 1028:1f38 | LSI Logic / S... | MegaRAID SAS 2208 [Thunderbolt]      | 17    | megarai... | [87EE1B58E4](<Server/Dell/PowerEdge/PowerEdge R420/BACBDE063781/DEBIAN-11/5.10.0-19-AMD64/X86_64/87EE1B58E4>) |
| 1000:005d | 1000:9363 | LSI Logic / S... | MegaRAID SAS-3 3108 [Invader]        | 17    | megarai... | [83A6DFFF47](<Server/Supermicro/Safeguard/Safeguard 3000/DF3381466B73/LINUXMINT-20.3/5.4.0-109-GENERIC/X86_64/83A6DFFF47>) |
| 8086:2826 | 1028:073a | Intel            | C600/X79 series chipset SATA RAID... | 15    | ahci       | [A7C222100E](<Server/Dell/Precision/Precision 7920 Tower/4FFAA8A7598E/LINUXMINT-21.1/5.15.0-67-GENERIC/X86_64/A7C222100E>) |
| 1000:005d | 15d9:0809 | LSI Logic / S... | MegaRAID SAS-3 3108 [Invader]        | 14    | megarai... | [6B0669D84C](<Server/transtec/CALLEO/CALLEO/F0064CBB2B63/DEBIAN-11/5.15.74-1-PVE/X86_64/6B0669D84C>) |
| 8086:2826 | 8086:7270 | Intel            | C600/X79 series chipset SATA RAID... | 14    | ahci       | [BDFA203C78](<Server/Supermicro/SBI-6119/SBI-6119P-T3N/985FBFBECAB2/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/BDFA203C78>) |
| 1000:005f | 1028:1f4b | LSI Logic / S... | MegaRAID SAS-3 3008 [Fury]           | 13    | megarai... | [237A3CD682](<Server/Dell/PowerEdge/PowerEdge R6515/647C815644AA/DEBIAN-12/6.1.0-5-AMD64/X86_64/237A3CD682>) |
| 103c:323b | 103c:3351 | Hewlett-Packard  | Smart Array Gen8 Controllers         | 13    | hpsa       | [72B9753B42](<Server/Hewlett-Packard/ProLiant/ProLiant DL380e Gen8/F46144405C53/UBUNTU-18.04/4.15.0-202-GENERIC/X86_64/72B9753B42>) |
| 1000:005d | 1028:1f49 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 12    | megarai... | [A05562BC52](<Server/Dell/PowerEdge/PowerEdge R430/AFD9B671916C/XUBUNTU-22.04/5.15.0-58-GENERIC/X86_64/A05562BC52>) |
| 1000:0079 | 1000:9263 | LSI Logic / S... | MegaRAID SAS 2108 [Liberator]        | 11    | megarai... | [E673BAB21F](<Server/Supermicro/H8/H8QG6/539918058863/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/E673BAB21F>) |
| 1000:005d | 1000:9361 | LSI Logic / S... | MegaRAID SAS-3 3108 [Invader]        | 10    | megarai... | [51DC310024](<Server/Kraftway/Trusted/Trusted TS2000/583173D8B5F2/RED-OS-7.3.2/6.1.11-1.EL7.3.X86_64/X86_64/51DC310024>) |
| 1000:005b | 1028:1f34 | LSI Logic / S... | MegaRAID SAS 2208 [Thunderbolt]      | 9     | megarai... | [6A0AF69B4A](<Server/Dell/PowerEdge/PowerEdge R720/F424DE07066D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6A0AF69B4A>) |
| 1000:005b | 1028:1f35 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 9     | megarai... | [8EE7146669](<Server/Dell/PowerEdge/PowerEdge T320/6878B1DE0919/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/8EE7146669>) |
| 1000:005d | 1028:1f42 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 9     | megarai... | [D2AE46F823](<Server/Dell/XC740xd-12/XC740xd-12 CORE/DD8724B460B5/UBUNTU-18.04/4.15.0-175-GENERIC/X86_64/D2AE46F823>) |
| 103c:3230 | 103c:3234 | Hewlett-Packard  | Smart Array Controller               | 8     | hpsa       | [8CF84909E3](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G5/CB5A662BC228/CENTOS-7/3.10.0-1160.88.1.EL7.X86_64/X86_64/8CF84909E3>) |
| 1000:0014 | 1d49:0602 | Broadcom / LSI   | MegaRAID Tri-Mode SAS3516            | 7     | megarai... | [C97EB83B9C](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 -[7X06CTO1WW]-/7AFAAAD68C64/CENTOS-7/3.10.0-1160.36.2.EL7.X86_64/X86_64/C97EB83B9C>) |
| 1000:0016 | 1028:1fcb | LSI Logic / S... | MegaRAID Tri-Mode SAS3508            | 7     | megarai... | [23031AA11A](<Server/Dell/PowerEdge/PowerEdge T440/EECBFF82A151/OPENSUSE-LEAP-15.4/5.14.21-150400.22-DEFAULT/X86_64/23031AA11A>) |
| 1000:0073 | 1028:1f51 | LSI Logic / S... | MegaRAID SAS 2008 [Falcon]           | 7     | megarai... | [D083AD669A](<Server/Dell/PowerEdge/PowerEdge R420/82C9269B6C2A/SLACKWARE-14.2+/5.15.2-PMAGIC/X86_64/D083AD669A>) |
| 1000:0079 | 1028:1f16 | Broadcom / LSI   | MegaRAID SAS 2108 [Liberator]        | 7     | megarai... | [C0B7421A8B](<Server/Dell/PowerEdge/PowerEdge R410/5EF56DA48933/DEBIAN-11/5.10.0-21-AMD64/X86_64/C0B7421A8B>) |
| 1028:0015 | 1028:1f03 | Dell             | PowerEdge Expandable RAID control... | 7     | megarai... | [75A840C1D8](<Server/Dell/PowerEdge/PowerEdge 2950/C63204CC3467/UBUNTU-16.04/4.4.0-194-GENERIC/X86_64/75A840C1D8>) |
| 103c:3230 | 103c:3235 | Hewlett-Packard  | Smart Array Controller               | 7     | hpsa       | [9861151D08](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/38FD2BD94129/LINUXMINT-21.1/5.15.0-67-GENERIC/X86_64/9861151D08>) |
| 17d3:1880 | 17d3:1883 | Areca Technology | ARC-188x series PCIe 2.0/3.0 to S... | 7     | arcmsr     | [3E6B182473](<Server/Gigabyte Technology/R182/R182-Z91-00/C0D8E0800C76/UBUNTU-22.04/5.15.0-70-GENERIC/X86_64/3E6B182473>) |
| 1000:0014 | 1028:1f3b | Broadcom / LSI   | MegaRAID Tri-Mode SAS3516            | 6     | megarai... | [7CE42AFB90](<Server/Dell/PowerEdge/PowerEdge R650/AF241F438036/DEBIAN-11/5.10.0-19-AMD64/X86_64/7CE42AFB90>) |
| 1000:0016 | 1028:1fcd | LSI Logic / S... | MegaRAID Tri-Mode SAS3508            | 6     | megarai... | [D56CA4A374](<Server/Dell/PowerEdge/PowerEdge R6515/C4B03BD3B174/UBUNTU-22.04/5.15.0-41-GENERIC/X86_64/D56CA4A374>) |
| 1000:0060 | 1028:1f0b | LSI Logic / S... | MegaRAID SAS 1078                    | 6     | megarai... | [2A289951DE](<Server/Dell/PowerEdge/PowerEdge T310/D04C74D757A7/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/2A289951DE>) |
| 1000:0079 | 1014:03b2 | LSI Logic / S... | MegaRAID SAS 2108 [Liberator]        | 6     | megarai... | [3DC8DC7AC1](<Server/IBM/System/System x3650 M3 -[7945AC1]/FFFD96EF2CBD/UBUNTU-22.04/5.15.0-53-GENERIC/X86_64/3DC8DC7AC1>) |
| 8086:2826 | 1028:0739 | Intel            | C600/X79 series chipset SATA RAID... | 6     | ahci       | [FE6DC0D9C7](<Server/Dell/Precision/Precision 7820 Tower/FB09ECB98D56/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FE6DC0D9C7>) |
| 1000:0017 | 1d49:0500 | Broadcom / LSI   | MegaRAID Tri-Mode SAS3408            | 5     | megarai... | [A2FD0BC88C](<Server/Lenovo/ThinkSystem/ThinkSystem SR250 -[7Y51CTO1WW]-/56D35BA12534/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/A2FD0BC88C>) |
| 1000:005b | 1028:1f31 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 5     | megarai... | [396BC50B1C](<Server/Dell/PowerEdge/PowerEdge T620/818E82CB1857/FEDORA-36/6.0.8-200.FC36.X86_64/X86_64/396BC50B1C>) |
| 1000:005b | 8086:3510 | LSI Logic / S... | MegaRAID SAS 2208 [Thunderbolt]      | 5     | megarai... | [5FBA63C085](<Server/Intel/S4600/S4600LH/902A1E31749C/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/5FBA63C085>) |
| 1000:0072 | 1000:0072 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 5     | mpt3sas    | [209C9B938C](<Server/Dell/PowerEdge/PowerEdge R410/62E76CCFE6D3/UBUNTU-20.04/5.4.0-126-GENERIC/X86_64/209C9B938C>) |
| 1000:0073 | 1014:03b1 | LSI Logic / S... | MegaRAID SAS 2008 [Falcon]           | 5     | megarai... | [16C68A28D8](<Server/IBM/System/System x3550 M3 -[7944SCP]-/B3404BB51BF1/DEBIAN-10/4.19.0-20-686-PAE/I686/16C68A28D8>) |
| 1000:0079 | 1734:1176 | Broadcom / LSI   | MegaRAID SAS 2108 [Liberator]        | 5     | megarai... | [00E39935AA](<Server/Fujitsu/PRIMERGY/PRIMERGY RX300 S7/B732C00110CF/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/00E39935AA>) |
| 8086:2826 | 1028:0718 | Intel            | C600/X79 series chipset SATA RAID... | 5     | ahci       | [A4F3535E84](<Server/Dell/Precision/Precision 7920 Rack/1D56B1A533A9/UBUNTU-20.04/5.14.0-1057-OEM/X86_64/A4F3535E84>) |
| 8086:2826 | 103c:81c7 | Intel            | C600/X79 series chipset SATA RAID... | 5     | ahci       | [50CCA471C5](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/010A19E087DC/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/50CCA471C5>) |
| 8086:2827 | 1028:0718 | Intel            | C610/X99 series chipset sSATA Con... | 5     | ahci       | [A4F3535E84](<Server/Dell/Precision/Precision 7920 Rack/1D56B1A533A9/UBUNTU-20.04/5.14.0-1057-OEM/X86_64/A4F3535E84>) |
| 8086:2827 | 103c:81c7 | Intel            | C610/X99 series chipset sSATA Con... | 5     | ahci       | [50CCA471C5](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/010A19E087DC/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/50CCA471C5>) |
| 1000:0016 | 19e5:d215 | Broadcom / LSI   | MegaRAID Tri-Mode SAS3508            | 4     | megarai... | [AD903545CE](<Server/HUAWEI/2288H/2288H V5/94600F3C6456/ALT-9.1/5.4.51-STD-DEF-ALT1/X86_64/AD903545CE>) |
| 1000:0016 | 1d49:0601 | Broadcom / LSI   | MegaRAID Tri-Mode SAS3508            | 4     | megarai... | [29F89998EE](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 V2/D65FD98664FE/DEBIAN-11/5.10.0-20-AMD64/X86_64/29F89998EE>) |
| 1000:005b | 1000:9271 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 4     | megarai... | [C4B4851A88](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/5E5B10F103C2/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/C4B4851A88>) |
| 1000:005b | 1014:040b | LSI Logic / S... | MegaRAID SAS 2208 [Thunderbolt]      | 4     | megarai... | [8D55479353](<Server/IBM/System/System x3550 M4 Server -[7914AC1]/D13FC123FD88/XUBUNTU-21.04/5.11.0-22-GENERIC/X86_64/8D55479353>) |
| 1000:005f | 1000:9341 | LSI Logic / S... | MegaRAID SAS-3 3008 [Fury]           | 4     | megarai... | [A43842B263](<Server/Supermicro/Super/Super Server/C70B4058D7CB/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/A43842B263>) |
| 1000:0060 | 1734:10f9 | Broadcom / LSI   | MegaRAID SAS 1078                    | 4     | megarai... | [9EC6CFFC99](<Server/Fujitsu/PRIMERGY/PRIMERGY TX200 S5/E1D1080FF200/LINUXMINT-19/4.15.0-166-GENERIC/X86_64/9EC6CFFC99>) |

### Storage/sas (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1000:0072 | 1028:1f1c | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 16    | mpt3sas    | [621A5675E8](<Server/Dell/PowerEdge/PowerEdge R715/23A622FDF232/OPENMANDRIVA-22.12/6.0.10-DESKTOP-2OMV22090/X86_64/621A5675E8>) |
| 8086:1d6b | 1043:84ef | Intel            | C602 chipset 4-Port SATA Storage ... | 13    | isci       | [12DBE88BAB](<Server/ASUSTek Computer/Z9PE-D8/Z9PE-D8 WS/0342B2EECEF7/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/12DBE88BAB>) |
| 1000:0072 | 1000:3020 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 12    | mpt3sas    | [DDFEFE06A3](<Server/Sun Microsystems/Sun/Sun Fire X4170 M2 SERVER/82C4B5F145E4/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/DDFEFE06A3>) |
| 1000:0072 | 15d9:0400 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 12    | mpt3sas    | [D341C929E0](<Server/Supermicro/H8/H8QG6/8BCA4F0C7663/CLEAR-LINUX-OS-36250/5.16.13-1132.NATIVE/X86_64/D341C929E0>) |
| 1000:0072 | 1028:1f1d | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 11    | mpt3sas    | [6CE8B7FB26](<Server/Supermicro/X10/X10SLL-F/34D1B7FAB08F/NIXOS-22.11/5.15.96/X86_64/6CE8B7FB26>) |
| 1000:0097 | 15d9:0808 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 10    | mpt3sas    | [302A7EEE03](<Server/Supermicro/Super/Super Server/AA1DCE2D823F/ACRONIS-CYBER-INFRASTRUCTURE-5.1.0/3.10.0-1160.53.1.VZ7.185.3/X86_64/302A7EEE03>) |
| 1000:0072 | 1028:1f1e | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 8     | mpt3sas    | [83C3B04914](<Server/Dell/PowerEdge/PowerEdge R710/C504DDF831F7/ARCH-ROLLING/5.18.19-XANMOD1-1/X86_64/83C3B04914>) |
| 8086:1d6b | 15d9:0626 | Intel            | C602 chipset 4-Port SATA Storage ... | 7     | isci       | [C4B4851A88](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/5E5B10F103C2/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/C4B4851A88>) |
| 1000:0086 | 15d9:0691 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 6     | mpt3sas    | [9C75DE7AF7](<Server/Supermicro/X10/X10SL7-F/C5A9BFB9B9BE/GENTOO-2.9/5.15.80-GENTOO-NVIDIA_SIN_SIMPLEFB/X86_64/9C75DE7AF7>) |
| 9005:028f | 103c:0602 | Adaptec          | Smart Storage PQI SAS                | 6     | smartpqi   | [C03DEE89F6](<Server/HPE/ProLiant/ProLiant DL380 Gen10/EE85DEEC4F6D/UBUNTU-20.04/5.15.0-60-GENERIC/X86_64/C03DEE89F6>) |
| 1000:0097 | 1000:30e0 | LSI Logic / S... | SAS3008 PCI-Express Fusion-MPT SAS-3 | 5     | mpt3sas    | [457ABEF5D3](<Server/ASRockRack/ROMED8/ROMED8-2T/E9A31A87AD3F/ALMA-9.1/6.3.0-2.EL9.ELREPO.X86_64/X86_64/457ABEF5D3>) |
| 8086:1d6b | 15d9:062a | Intel            | C602 chipset 4-Port SATA Storage ... | 5     | isci       | [2E9D55D3A7](<Server/Supermicro/X9/X9SRA-X9SRA-3/E73ED86A7227/DEBIAN-11/5.10.0-14-AMD64/X86_64/2E9D55D3A7>) |
| 8086:1d6b | 15d9:0636 | Intel            | C602 chipset 4-Port SATA Storage ... | 5     | isci       | [6994C89077](<Server/Supermicro/X9/X9DRW/6A1A83EBE660/DEBIAN-11/5.15.104-1-PVE/X86_64/6994C89077>) |
| 8086:1d6b | 8086:35a1 | Intel            | C602 chipset 4-Port SATA Storage ... | 5     | isci       | [5FBA63C085](<Server/Intel/S4600/S4600LH/902A1E31749C/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/5FBA63C085>) |
| 1000:0072 | 1000:3040 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 4     | mpt3sas    | [430B4F4EDF](<Server/Supermicro/H8/H8DGU/8ACEE5E956B2/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/430B4F4EDF>) |
| 1000:0087 | 1000:3040 | LSI Logic / S... | SAS2308 PCI-Express Fusion-MPT SAS-2 | 4     | mpt3sas    | [D368F224C8](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/A55741AC6343/DEBIAN-11/5.15.74-1-PVE/X86_64/D368F224C8>) |
| 1000:0087 | 1028:1f38 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 4     | mpt3sas    | [4FCFB3FB2A](<Server/Dell/PowerEdge/PowerEdge R520/4F1CD316F76B/DEBIAN-11/5.15.85-1-PVE/X86_64/4FCFB3FB2A>) |
| 1000:00c4 | 1000:3190 | Broadcom / LSI   | SAS3224 PCI-Express Fusion-MPT SAS-3 | 4     | mpt3sas    | [BE6BB6833C](<Server/Supermicro/X11/X11DPi-N/FC0F4F308AC0/DEBIAN-11/5.15.60-1-PVE/X86_64/BE6BB6833C>) |
| 19e5:a230 |           | Huawei Techno... | HiSilicon SAS 3.0 HBA                | 4     | hisi_sa... | [F548D0A0A9](<Server/HUAWEI/TaiShan/TaiShan 200/7F69DEB6BBD3/RELS-2019.1/5.10.42-GENERIC-1ROSA2019.1-ARM64/AARCH64/F548D0A0A9>) |
| 1000:0064 | 1000:30d0 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 3     | mpt3sas    | [8B34A52B83](<Server/Dell/PowerEdge/PowerEdge R710/837DD65D6009/DEBIAN-11/5.15.53-1-PVE/X86_64/8B34A52B83>) |
| 1000:0072 | 1014:03cb | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 3     | mpt3sas    | [A9289CA04C](<Server/IBM/System/System x3650 M3 -[794562M]-/70C4A6EC4717/ARCH-ROLLING/5.18.6-ARCH1-1/X86_64/A9289CA04C>) |
| 1000:0087 | 1000:3020 | LSI Logic / S... | SAS2308 PCI-Express Fusion-MPT SAS-2 | 3     | mpt3sas    | [8B34A52B83](<Server/Dell/PowerEdge/PowerEdge R710/837DD65D6009/DEBIAN-11/5.15.53-1-PVE/X86_64/8B34A52B83>) |
| 1000:0097 | 1028:1f53 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 3     | mpt3sas    | [82830908AB](<Server/Dell/PowerEdge/PowerEdge R6515/0474663F511F/ARCH/5.15.59-1-LTS/X86_64/82830908AB>) |
| 8086:1d6b | 15d9:0660 | Intel            | C602 chipset 4-Port SATA Storage ... | 3     | isci       | [C088868F62](<Server/Supermicro/X9/X9DRD-iF-LF/F42BB6D21594/DEBIAN-11/5.15.74-1-PVE/X86_64/C088868F62>) |
| 1000:0070 | 1000:3010 | LSI Logic / S... | SAS2004 PCI-Express Fusion-MPT SA... | 2     | mpt3sas    | [4CE6A061A6](<Server/Dell/PowerEdge/PowerEdge R720/D87975CF195B/UBUNTU-20.04/5.8.0-49-GENERIC/X86_64/4CE6A061A6>) |
| 1000:0072 | 1170:6019 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mpt3sas    | [D1A141052C](<Server/Dell/PowerEdge/PowerEdge C6220 II/F5E056823CF5/DEBIAN-11/5.15.85-1-PVE/X86_64/D1A141052C>) |
| 1000:0097 | 1000:0090 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 2     | mpt3sas    | [2903921AEB](<Server/AIC/SB302/SB302-LB/98EDCF68ED2D/CENTOS-8/4.18.0-80.EL8.X86_64/X86_64/2903921AEB>) |
| 8086:1d68 | 15d9:0626 | Intel            | C606 chipset Dual 4-Port SATA/SAS... | 2     | isci       | [6FC004B792](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/A8FA5EF00732/ARCH/6.0.0-RC6-269-TKG-CFS-LLVM/X86_64/6FC004B792>) |
| 8086:1d6b | 1170:0054 | Intel            | C602 chipset 4-Port SATA Storage ... | 2     | isci       | [1B5977B024](<Server/ZTSYSTEMS/Z/Z801/2920EC336BF6/RHEL-7/3.10.0-1062.4.3.EL7.YAHOO.20191113.49.X86_64/X86_64/1B5977B024>) |
| 8086:1d6b | 1734:11b6 | Intel            | C602 chipset 4-Port SATA Storage ... | 2     | isci       | [00E39935AA](<Server/Fujitsu/PRIMERGY/PRIMERGY RX300 S7/B732C00110CF/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/00E39935AA>) |
| 8086:1d6b | 8086:357f | Intel            | C602 chipset 4-Port SATA Storage ... | 2     | isci       | [CDFBA65630](<Server/Intel/S2600/S2600CP/5F463C4DAE95/UBUNTU-22.04/5.15.0-23-GENERIC/X86_64/CDFBA65630>) |
| 8086:1d6b | 8086:3595 | Intel            | C602 chipset 4-Port SATA Storage ... | 2     | isci       | [96CDA648C2](<Server/Intel/W2600/W2600CR/577694DF59DA/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/96CDA648C2>) |
| 9005:028f | 103c:0654 | Adaptec          | Smart Storage PQI SAS                | 2     | smartpqi   | [4CDCAD1148](<Server/HPE/ProLiant/ProLiant DL380 Gen10/AD4000C49F0A/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/4CDCAD1148>) |
| 1000:005d | 8086:3a1e | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 1     | megarai... | [98C12554CB](<Server/Intel/S1200/S1200SP/FDDD794115FC/CLEAR-LINUX-OS-34560/5.10.33-1036.NATIVE/X86_64/98C12554CB>) |
| 1000:0064 | 1000:3030 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 1     | mpt3sas    | [32951A000F](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/E782FD83F7D2/UBUNTU-20.04/5.8.0-53-GENERIC/X86_64/32951A000F>) |
| 1000:0064 | 1000:30c0 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 1     | mpt3sas    | [28F4CEB8EE](<Server/Intel/S1200/S1200RP/FB9A925E61E5/ARCH-ROLLING/5.19.13-ARCH1-1/X86_64/28F4CEB8EE>) |
| 1000:0064 | 15d9:083c | LSI Logic / S... | SAS2116 PCI-Express Fusion-MPT SA... | 1     | mpt3sas    | [DB25C87154](<Server/Supermicro/Super/Super Server/71B3E013BFED/ARCH/4.15.5-1-ARCH/X86_64/DB25C87154>) |
| 1000:0070 | 1014:03f7 | LSI Logic / S... | SAS2004 PCI-Express Fusion-MPT SA... | 1     | mpt2sas    | [D7CBC31CEE](<Server/IBM/BladeCenter/BladeCenter HS23 -[7875MFM]-/D5DD0E377016/RELS-6.9/2.6.32-696.EL6.X86_64/X86_64/D7CBC31CEE>) |
| 1000:0070 | 1014:03f8 | Broadcom / LSI   | SAS2004 PCI-Express Fusion-MPT SA... | 1     | mpt2sas    | [7C109612B9](<Server/IBM/Flex/Flex System x240 Compute Node -[8737AC1]-/6F6DEF6E7D5A/CENTOS-7/3.10.0-1127.8.2.EL7.X86_64/X86_64/7C109612B9>) |
| 1000:0072 | 1000:3050 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mpt3sas    | [0B2E10175B](<Server/Supermicro/X8/X8DAH/4A92FB7AB3EE/UBUNTU-18.04/4.15.0-88-GENERIC/X86_64/0B2E10175B>) |
| 1000:0072 | 1000:3060 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mpt3sas    | [D52DB39EEB](<Server/Dell/PowerEdge/PowerEdge R210 II/D25E2376C7EE/FEDORA-33/5.13.4-100.FC33.X86_64/X86_64/D52DB39EEB>) |
| 1000:0072 | 1000:3080 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mpt3sas    | [7D9FDF4B73](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/16075FBC6C06/UBUNTU-21.10/5.15.1-051501-GENERIC/X86_64/7D9FDF4B73>) |
| 1000:0072 | 103c:3371 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mpt3sas    | [6A0AF69B4A](<Server/Dell/PowerEdge/PowerEdge R720/F424DE07066D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6A0AF69B4A>) |
| 1000:007e | 1000:0507 | Broadcom / LSI   | SSS6200 PCI-Express Flash SSD        | 1     | mpt3sas    | [BA4FFBDA6D](<Server/Dell/PowerEdge/PowerEdge R610/1D256EA1AA3C/XUBUNTU-20.04/5.4.0-48-GENERIC/X86_64/BA4FFBDA6D>) |
| 1000:007e | 108e:0581 | Broadcom / LSI   | SSS6200 PCI-Express Flash SSD        | 1     | mpt3sas    | [A243FDE4E1](<Server/Oracle/Sun/Sun Fire X4270 M3/3AEA7677F53C/ZORIN-16/5.11.0-46-GENERIC/X86_64/A243FDE4E1>) |
| 1000:0087 | 1000:0087 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mpt3sas    | [BA0F3C3B41](<Server/HUAWEI/RH1288/RH1288 V3/DCCC7932E1B0/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/BA0F3C3B41>) |
| 1000:0087 | 1028:1f34 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mpt3sas    | [FBDF83F7FF](<Server/Dell/PowerEdge/PowerEdge R720/4D59BA33C94F/DEBIAN-11/5.11.22-2-PVE/X86_64/FBDF83F7FF>) |
| 1000:0087 | 1028:1f35 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mpt3sas    | [C9C876F0E7](<Server/Dell/PowerEdge/PowerEdge T320/8A9310CFABA2/UBUNTU-20.04/5.11.0-34-GENERIC/X86_64/C9C876F0E7>) |
| 1000:0087 | 1590:0041 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mpt3sas    | [63553D673B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/8B45D4DD73D1/DEBIAN-11/5.15.39-2-PVE/X86_64/63553D673B>) |
| 1000:0087 | 1590:0042 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mpt3sas    | [A14015F487](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/FC3112711290/UBUNTU-18.04/4.15.0-99-GENERIC/X86_64/A14015F487>) |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1000:0058 | 1028:1f0f | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 9     | mptsas     | [0170EDEB2C](<Server/Dell/PowerEdge/PowerEdge R410/8E553220E003/UBUNTU-20.04/5.15.0-57-GENERIC/X86_64/0170EDEB2C>) |
| 1000:0058 | 1028:1f0e | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 7     | mptsas     | [9C7291AE7E](<Server/Dell/PowerEdge/PowerEdge T110 II/92499E1FE1A3/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/9C7291AE7E>) |
| 1000:0058 | 1028:1f10 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 7     | mptsas     | [14DEFA3569](<Server/Dell/PowerEdge/PowerEdge 1950/7D3E387CFF5B/UBUNTU-22.04/5.15.0-40-GENERIC/X86_64/14DEFA3569>) |
| 1000:0056 | 1014:03bb | LSI Logic / S... | SAS1064ET PCI-Express Fusion-MPT SAS | 5     | mptsas     | [074E80349E](<Server/IBM/System/System x3250 M3 -[4252K4G]-/76E08604766E/DEBIAN-10/5.4.124-1-PVE/X86_64/074E80349E>) |
| 1000:0058 | 1000:3150 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 3     | mptsas     | [EA845EC5EA](<Server/Sun Microsystems/Sun/Sun Fire X4170 M2 SERVER/DD45CBFD7301/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/EA845EC5EA>) |
| 1000:0058 | 1014:0394 | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 3     | mptsas     | [B85DBD88F5](<Server/IBM/System/System x3650 M2 -[7947AC1]-/B4AFB5C90D39/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/B85DBD88F5>) |
| 1000:0054 | 1028:1f09 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 2     | mptsas     | [701B89AC2E](<Server/IBM/System/System x3650 -[7979B9U]-/BC2D6FA78D8E/OPENMANDRIVA-4.2/5.11.12-DESKTOP-1OMV4002/X86_64/701B89AC2E>) |
| 1000:0056 | 152d:896d | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 2     | mptsas     | [23E536F087](<Server/Quanta/QSSC-98/QSSC-98J_C2/03AF1302C679/CENTOS-6.9/2.6.32-754.6.3.EL6.X86_64/X86_64/23E536F087>) |
| 1000:0056 | 8086:3486 | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 2     | mptsas     | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 1000:0058 | 15d9:0001 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 2     | mptsas     | [F645C4227C](<Server/Supermicro/X8/X8DT3/095547D33119/LMDE-4/4.19.0-16-AMD64/X86_64/F645C4227C>) |
| 1000:0058 | 1734:1130 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 2     | mptsas     | [C4C0B53877](<Server/Fujitsu/PRIMERGY/PRIMERGY TX150 S7/4BE064DA92A3/OL-9.0/5.15.0-0.30.19.EL9UEK.X86_64/X86_64/C4C0B53877>) |
| 9005:8017 | 9005:0045 | Adaptec          | ASC-29320ALP U320                    | 2     | aic79xx    | [096D3E62FE](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/7FC37BA0963D/FEDORA-34/5.12.3-300.FC34.X86_64/X86_64/096D3E62FE>) |
| 1000:000f | 0e11:7004 | Broadcom / LSI   | 53c875                               | 1     | sym53c8xx  | [AFF808A68F](<Server/Supermicro/X8/X8DTL/2CC89667A3DA/UBUNTU-18.04/4.15.0-99-GENERIC/X86_64/AFF808A68F>) |
| 1000:0030 | 1000:1000 | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mptspi     | [18B25AC51A](<Server/TYAN Computer/S/S4882/84BBA0EA52AC/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/18B25AC51A>) |
| 1000:0030 | 1000:50c0 | LSI Logic / S... | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mptspi     | [3F4700F256](<Server/Dell/PowerEdge/PowerEdge T610/A5921AA6471A/CENTOS-7/3.10.0-693.11.1.EL7.X86_64/X86_64/3F4700F256>) |
| 1000:0030 | 1014:026c | LSI Logic / S... | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mptspi     | [46973B5B05](<Server/IBM/eserver/eserver xSeries 235 -[86712AX]-/93A8BF1AD0B5/ROSA-2014.1/3.14.44-NRJ-DESKTOP-2ROSA-I586/I686/46973B5B05>) |
| 1000:0030 | 1028:016c | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mptspi     | [9A384DEF54](<Server/Dell/PowerEdge/PowerEdge 1850/858D0EB6BB9A/LINUXMINT-20.3/5.4.0-117-GENERIC/X86_64/9A384DEF54>) |
| 1000:0030 | 1028:016e | LSI Logic / S... | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mptspi     | [76EF1C8CA9](<Server/Dell/PowerEdge/PowerEdge 2800/2245B0434B88/UBUNTU-18.04/4.15.0-47-GENERIC/X86_64/76EF1C8CA9>) |
| 1000:0054 | 1028:1f06 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 1     | mptsas     | [2FF8924B15](<Server/Dell/PowerEdge/PowerEdge 1950/12946989497B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2FF8924B15>) |
| 1000:0054 | 1734:1082 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 1     | mptsas     | [872AE76863](<Server/Fujitsu Siemens/PRIMERGY/PRIMERGY RX300 S3/2366E6CCAF09/OPENSUSE-LEAP-15.1/4.12.14-LP151.28.91-DEFAULT/X86_64/872AE76863>) |
| 1000:0054 | 1734:10b9 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 1     | mptsas     | [A0F9679F57](<Server/Fujitsu Siemens/PRIMERGY/PRIMERGY RX330 S1/BBBDB6433647/UBUNTU-18.04/4.15.0-112-GENERIC/X86_64/A0F9679F57>) |
| 1000:0054 | 8086:3504 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 1     | mptsas     | [A61FFACB08](<Server/Intel/S5000/S5000PAL/A2AA6EE937D8/UBUNTU-18.04/5.0.0-37-GENERIC/X86_64/A61FFACB08>) |
| 1000:0056 | 1000:3090 | LSI Logic / S... | SAS1064ET PCI-Express Fusion-MPT SAS | 1     | mptsas     | [94527A8584](<Server/Intel/S5500/S5500BC/A12E8B03104E/LINUXMINT-19.3/5.4.0-148-GENERIC/X86_64/94527A8584>) |
| 1000:0056 | 1734:1131 | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 1     | mptsas     | [28EB3733CA](<Server/Fujitsu/PRIMERGY/PRIMERGY RX200 S6/A598FCA268BC/UBUNTU-20.04/5.4.0-88-GENERIC/X86_64/28EB3733CA>) |
| 1000:0056 | 8086:346c | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 1     | mptsas     | [390F15B7F9](<Server/Intel/S5000/S5000PAL/74FE128B70DE/CENTOS-7/3.10.0-1062.1.1.EL7.X86_64/X86_64/390F15B7F9>) |
| 1000:0058 | 1000:3080 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mptsas     | [8CF8F98A53](<Server/Fujitsu/PRIMERGY/PRIMERGY/41B1E7A57925/FEDORA-35/5.14.10-300.FC35.X86_64/X86_64/8CF8F98A53>) |
| 1000:0058 | 1000:30a0 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mptsas     | [E5AEAF13AE](<Server/Intel/S3210/S3210SH/9BAA0B7E268E/UBUNTU-18.04/4.15.0-64-GENERIC/X86_64/E5AEAF13AE>) |
| 1000:0058 | 1000:7016 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mptsas     | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 1000:0059 | 15d9:0006 | Broadcom / LSI   | MegaRAID SAS 8208ELP/8208ELP         | 1     | mptsas     | [8F945E0A15](<Server/Supermicro/X8/X8DTL/7581500BE1DB/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/8F945E0A15>) |
| 1000:0062 | 8086:3505 | Broadcom / LSI   | SAS1078 PCI-Express Fusion-MPT SAS   | 1     | mptsas     | [476430304C](<Server/Intel/S5520/S5520UR/ED7F5C075DAE/UBUNTU-20.04/5.4.0-104-GENERIC/X86_64/476430304C>) |
| 1425:6507 | 1425:0000 | Chelsio Commu... | T62100-LP-CR Unified Wire Storage... | 1     |            | [1126AE11AE](<Server/ASUSTek Computer/Z11PG-D16/Z11PG-D16 Series/9878F56186D3/DEBIAN-9/4.9.35-DYVI/X86_64/1126AE11AE>) |
| 9004:5078 | 9004:7850 | Adaptec          | AIC-7850T/7856T [AVA-2902/4/6 / A... | 1     | aic7xxx    | [171EE8DB12](<Server/Supermicro/C7/C7Z87/4BD99E9BA2B9/XUBUNTU-19.10/5.3.0-18-LOWLATENCY/X86_64/171EE8DB12>) |
| 9005:00c0 | 9005:f620 | Adaptec          | AHA-3960D / AIC-7899A U160/m         | 1     | aic7xxx    | [CA96304CAC](<Server/Dell/PowerEdge/PowerEdge 1950/E6782D539697/POP!_OS-20.04/5.15.15-76051515-GENERIC/X86_64/CA96304CAC>) |
| 9005:801f | 8086:341a | Adaptec          | AIC-7902 U320                        | 1     | aic79xx    | [37AA8C0E8E](<Server/Intel/SE7501WV2S/SE7501WV2S A99386-110/784B87202334/UBUNTU-18.04/4.15.0-108-GENERIC/I686/37AA8C0E8E>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:204e | 8086:0000 | Intel            | Sky Lake-E M3KTI Registers           | 205   | skx_uncore | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2018 | 8086:0000 | Intel            | Sky Lake-E M2PCI Registers           | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2035 |           | Intel            | Sky Lake-E RAS Configuration Regi... | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2040 | 8086:0000 | Intel            | Sky Lake-E Integrated Memory Cont... | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2041 | 8086:0000 | Intel            | Sky Lake-E Integrated Memory Cont... | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2042 | 8086:0000 | Intel            | Sky Lake-E Integrated Memory Cont... | 199   | skx_uncore | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2043 | 8086:0000 | Intel            | Sky Lake-E Integrated Memory Cont... | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2044 | 8086:0000 | Intel            | Sky Lake-E Integrated Memory Cont... | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2045 | 8086:0000 | Intel            | Sky Lake-E LM Channel 1              | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2046 | 8086:0000 | Intel            | Sky Lake-E LMS Channel 1             | 199   | skx_uncore | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2047 | 8086:0000 | Intel            | Sky Lake-E LMDP Channel 1            | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2048 | 8086:0000 | Intel            | Sky Lake-E DECS Channel 2            | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2049 | 8086:0000 | Intel            | Sky Lake-E LM Channel 2              | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:204a | 8086:0000 | Intel            | Sky Lake-E LMS Channel 2             | 199   | skx_uncore | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:204b | 8086:0000 | Intel            | Sky Lake-E LMDP Channel 2            | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2054 | 8086:0000 | Intel            | Sky Lake-E CHA Registers             | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2055 | 8086:0000 | Intel            | Sky Lake-E CHA Registers             | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2056 | 8086:0000 | Intel            | Sky Lake-E CHA Registers             | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2057 | 8086:0000 | Intel            | Sky Lake-E CHA Registers             | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2066 | 8086:0000 | Intel            | Sky Lake-E Integrated Memory Cont... | 199   | skx_uncore | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2080 | 8086:0000 | Intel            | Sky Lake-E PCU Registers             | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2081 | 8086:0000 | Intel            | Sky Lake-E PCU Registers             | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2082 | 8086:0000 | Intel            | Sky Lake-E PCU Registers             | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2083 | 8086:0000 | Intel            | Sky Lake-E PCU Registers             | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2084 | 8086:0000 | Intel            | Sky Lake-E PCU Registers             | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2085 | 8086:0000 | Intel            | Sky Lake-E PCU Registers             | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2086 | 8086:0000 | Intel            | Sky Lake-E PCU Registers             | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:208d | 8086:0000 | Intel            | Sky Lake-E CHA Registers             | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:208e | 8086:0000 | Intel            | Sky Lake-E CHA Registers             | 199   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2016 | 8086:0000 | Intel            | Sky Lake-E Ubox Registers            | 198   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2025 |           | Intel            | Sky Lake-E RAS                       | 198   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2014 | 8086:0000 | Intel            | Sky Lake-E Ubox Registers            | 192   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2034 | 8086:0000 | Intel            | Sky Lake-E VT-d                      | 191   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2059 | 8086:0000 | Intel            | Sky Lake-E UPI Registers             | 188   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2024 | 8086:0000 | Intel            | Sky Lake-E MM/Vt-d Configuration ... | 185   |            | [D0CEF22171](<Server/Dell/PowerEdge/PowerEdge R440/7EA52D2EEB48/DEBIAN-11/5.10.0-22-AMD64/X86_64/D0CEF22171>) |
| 8086:2021 | 8086:0000 | Intel            | Sky Lake-E CBDMA Registers           | 165   | ioatdma    | [FE6DC0D9C7](<Server/Dell/Precision/Precision 7820 Tower/FB09ECB98D56/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FE6DC0D9C7>) |
| 103c:3306 | 103c:3381 | Hewlett-Packard  | Integrated Lights-Out Standard Sl... | 100   | hpwdt      | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 103c:3307 | 103c:3381 | Hewlett-Packard  | Integrated Lights-Out Standard Ma... | 100   | hpilo      | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:6f76 |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 100   |            | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:6f88 |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 100   |            | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:6f8a |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 100   |            | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:6fae |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 100   |            | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:6faf |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 100   |            | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:6fbc |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 100   |            | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:6fbd |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 100   |            | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:6fbe |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 100   |            | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:6fbf |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 100   |            | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:2f6e |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 90    |            | [AD555BFDE2](<Server/Dell/PowerEdge/PowerEdge T430/F2945010DA0E/ARCH-ROLLING/6.3.0-273-TKG-PDS-LLVM/X86_64/AD555BFDE2>) |
| 8086:2f6f |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 90    |            | [AD555BFDE2](<Server/Dell/PowerEdge/PowerEdge T430/F2945010DA0E/ARCH-ROLLING/6.3.0-273-TKG-PDS-LLVM/X86_64/AD555BFDE2>) |
| 8086:2f88 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 VCU    | 90    |            | [AD555BFDE2](<Server/Dell/PowerEdge/PowerEdge T430/F2945010DA0E/ARCH-ROLLING/6.3.0-273-TKG-PDS-LLVM/X86_64/AD555BFDE2>) |

### Tv card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 109e:036e |           | Brooktree        | Bt878 Video Capture                  | 1     | bttv       | [B55D1DAEA5](<Server/Intel/S5500/S5500BC/EB1E1FCFB3A4/UBUNTU-MATE-19.10/5.3.0-51-GENERIC/X86_64/B55D1DAEA5>) |
| 109e:036e | 0070:ff04 | Brooktree        | Bt878 Video Capture                  | 1     | bttv       | [2C877CF870](<Server/Hewlett-Packard/ProLiant/ProLiant DL140 G2/7851FB932D49/ARCH/4.18.12-ARCH1-1-ARCH/X86_64/2C877CF870>) |
| 109e:036e | 800a:763d | Brooktree        | Bt878 Video Capture                  | 1     | bttv       | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 109e:036e | 800b:763d | Brooktree        | Bt878 Video Capture                  | 1     | bttv       | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 109e:036e | 800c:763d | Brooktree        | Bt878 Video Capture                  | 1     | bttv       | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 109e:036e | 800d:763d | Brooktree        | Bt878 Video Capture                  | 1     | bttv       | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 14f1:5b7a | 0070:7446 | Conexant Systems | CX23418 Single-Chip MPEG-2 Encode... | 1     | cx18       | [5C00E2D415](<Server/Intel/S5520/S5520HC/42DF18E9A677/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/5C00E2D415>) |
| 14f1:8880 | 0070:6a18 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 1     | cx23885    | [019914CC29](<Server/Supermicro/X10/X10SAE/6D8BBA911035/GENTOO-2.7/5.13.12-GENTOO/X86_64/019914CC29>) |
| 14f1:8880 | 0070:6b18 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 1     | cx23885    | [019914CC29](<Server/Supermicro/X10/X10SAE/6D8BBA911035/GENTOO-2.7/5.13.12-GENTOO/X86_64/019914CC29>) |
| 14f1:8880 | 1461:d439 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 1     |            | [D8325626F2](<Server/Dell/PowerEdge/PowerEdge T610/E71BEA809C78/SLED-15.1/4.12.14-197.64-DEFAULT/X86_64/D8325626F2>) |

### Unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1137:0042 | 1137:012e | Cisco Systems    | VIC Management Controller            | 1     |            | [BAF3069CD7](<Server/Cisco Systems/UCSC-C220/UCSC-C220-M4S/9D3781D2096F/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/BAF3069CD7>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 103c:3300 | 103c:3381 | Hewlett-Packard  | Integrated Lights-Out Standard Vi... | 100   | uhci_hcd   | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:1d26 | 103c:18a9 | Intel            | C600/X79 series chipset USB2 Enha... | 69    | ehci_pci   | [961A066E6B](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/F726BB41B090/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/961A066E6B>) |
| 8086:1d2d | 103c:18a9 | Intel            | C600/X79 series chipset USB2 Enha... | 69    | ehci_pci   | [961A066E6B](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/F726BB41B090/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/961A066E6B>) |
| 8086:3a34 | 103c:330d | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 54    | uhci_hcd   | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |
| 8086:3a35 | 103c:330d | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 54    | uhci_hcd   | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |
| 8086:3a36 | 103c:330d | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 54    | uhci_hcd   | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |
| 8086:3a39 | 103c:330d | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 54    | uhci_hcd   | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |
| 8086:3a3a | 103c:330d | Intel            | 82801JI (ICH10 Family) USB2 EHCI ... | 54    | ehci_pci   | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |
| 8086:a1af | 8086:7270 | Intel            | C620 Series Chipset Family USB 3.... | 45    | xhci_hcd   | [18B2BF9FF4](<Server/Delta Computers/DSS-C621/DSS-C621LTG/EA1701537BF7/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/18B2BF9FF4>) |
| 103c:3300 | 103c:3309 | Hewlett-Packard  | Integrated Lights-Out Standard Vi... | 42    | uhci_hcd   | [4E4F63C868](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/DE8AAA43E1D3/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/4E4F63C868>) |
| 1912:0014 | ffff:ffff | Renesas Techn... | uPD720201 USB 3.0 Host Controller    | 35    | xhci_pci   | [8619E38037](<Server/Gigabyte Technology/E252/E252-P30-00/513B50B63035/UBUNTU-20.04/5.4.0-145-GENERIC/AARCH64/8619E38037>) |
| 103c:3300 | 103c:3305 | Hewlett-Packard  | Integrated Lights-Out Standard Vi... | 34    | uhci_hcd   | [0CAD2B6262](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/378650F39689/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/0CAD2B6262>) |
| 1022:148c | 15d9:145c | AMD              | Starship USB 3.0 Host Controller     | 29    | xhci_hcd   | [55AF41B298](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.7/4.18.0-425.19.2.EL8_7.X86_64/X86_64/55AF41B298>) |
| 8086:8d26 | 103c:8030 | Intel            | C610/X99 series chipset USB Enhan... | 27    | ehci_pci   | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:8d2d | 103c:8030 | Intel            | C610/X99 series chipset USB Enhan... | 27    | ehci_pci   | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:8d31 | 103c:8030 | Intel            | C610/X99 series chipset USB xHCI ... | 27    | xhci_hcd   | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:2934 | 1028:0235 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 25    | uhci_hcd   | [BC1B2F4337](<Server/Dell/PowerEdge/PowerEdge R710/4BD52918C3EA/UBUNTU-22.10/5.19.0-30-GENERIC/X86_64/BC1B2F4337>) |
| 8086:2935 | 1028:0235 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 25    | uhci_hcd   | [BC1B2F4337](<Server/Dell/PowerEdge/PowerEdge R710/4BD52918C3EA/UBUNTU-22.10/5.19.0-30-GENERIC/X86_64/BC1B2F4337>) |
| 8086:2937 | 1028:0235 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 25    | uhci_hcd   | [BC1B2F4337](<Server/Dell/PowerEdge/PowerEdge R710/4BD52918C3EA/UBUNTU-22.10/5.19.0-30-GENERIC/X86_64/BC1B2F4337>) |
| 8086:2938 | 1028:0235 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 25    | uhci_hcd   | [BC1B2F4337](<Server/Dell/PowerEdge/PowerEdge R710/4BD52918C3EA/UBUNTU-22.10/5.19.0-30-GENERIC/X86_64/BC1B2F4337>) |
| 8086:293a | 1028:0235 | Intel            | 82801I (ICH9 Family) USB2 EHCI Co... | 25    | ehci_pci   | [BC1B2F4337](<Server/Dell/PowerEdge/PowerEdge R710/4BD52918C3EA/UBUNTU-22.10/5.19.0-30-GENERIC/X86_64/BC1B2F4337>) |
| 8086:293c | 1028:0235 | Intel            | 82801I (ICH9 Family) USB2 EHCI Co... | 25    | ehci_pci   | [BC1B2F4337](<Server/Dell/PowerEdge/PowerEdge R710/4BD52918C3EA/UBUNTU-22.10/5.19.0-30-GENERIC/X86_64/BC1B2F4337>) |
| 1002:4396 | 1002:4396 | AMD              | SB7x0/SB8x0/SB9x0 USB EHCI Contro... | 22    | ehci_pci   | [EA89B6E705](<Server/Supermicro/H8/H8SGL/4B37E516C354/UBUNTU-20.04/5.13.0-41-GENERIC/X86_64/EA89B6E705>) |
| 1002:4399 | 1002:4396 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI2 Contr... | 22    | ohci_pci   | [EA89B6E705](<Server/Supermicro/H8/H8SGL/4B37E516C354/UBUNTU-20.04/5.13.0-41-GENERIC/X86_64/EA89B6E705>) |
| 8086:a1af | 8086:35ce | Intel            | C620 Series Chipset Family USB 3.... | 22    | xhci_hcd   | [F5848D1BA2](<Server/DALCO/S2600/S2600WFT/37B0D5359698/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/F5848D1BA2>) |
| 1b21:1142 | 1b21:1142 | ASMedia Techn... | ASM1042A USB 3.0 Host Controller     | 20    | xhci_hcd   | [55AF41B298](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.7/4.18.0-425.19.2.EL8_7.X86_64/X86_64/55AF41B298>) |
| 8086:1d26 | 1043:84ef | Intel            | C600/X79 series chipset USB2 Enha... | 20    | ehci_pci   | [4AC44C74A3](<Server/ASUSTek Computer/Z9PA-D8/Z9PA-D8 Series/0BE952D59456/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/4AC44C74A3>) |
| 8086:1d2d | 1043:84ef | Intel            | C600/X79 series chipset USB2 Enha... | 20    | ehci_pci   | [4AC44C74A3](<Server/ASUSTek Computer/Z9PA-D8/Z9PA-D8 Series/0BE952D59456/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/4AC44C74A3>) |
| 8086:a1af | 1028:073a | Intel            | C620 Series Chipset Family USB 3.... | 20    | xhci_pci   | [962B265260](<Server/Dell/Precision/Precision 7920 Tower/8C7F63FF0FE0/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/962B265260>) |
| 8086:3a34 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 19    | uhci_hcd   | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:3a35 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 19    | uhci_hcd   | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:3a36 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 19    | uhci_hcd   | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:3a37 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 19    | uhci_hcd   | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:3a38 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 19    | uhci_hcd   | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:3a39 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 19    | uhci_hcd   | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:3a3a | 15d9:0006 | Intel            | 82801JI (ICH10 Family) USB2 EHCI ... | 19    | ehci_pci   | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:3a3c | 15d9:0006 | Intel            | 82801JI (ICH10 Family) USB2 EHCI ... | 19    | ehci_pci   | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 1106:3483 | 1106:3483 | VIA Technologies | VL805/806 xHCI USB 3.0 Controller    | 18    | xhci_pci   | [5C00E2D415](<Server/Intel/S5520/S5520HC/42DF18E9A677/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/5C00E2D415>) |
| 8086:1d26 | 1028:048c | Intel            | C600/X79 series chipset USB2 Enha... | 17    | ehci_pci   | [6A0AF69B4A](<Server/Dell/PowerEdge/PowerEdge R720/F424DE07066D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6A0AF69B4A>) |
| 8086:1d2d | 1028:048c | Intel            | C600/X79 series chipset USB2 Enha... | 17    | ehci_pci   | [6A0AF69B4A](<Server/Dell/PowerEdge/PowerEdge R720/F424DE07066D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6A0AF69B4A>) |
| 8086:2688 | 103c:31fe | Intel            | 631xESB/632xESB/3100 Chipset UHCI... | 17    | uhci_hcd   | [8CF84909E3](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G5/CB5A662BC228/CENTOS-7/3.10.0-1160.88.1.EL7.X86_64/X86_64/8CF84909E3>) |
| 8086:2689 | 103c:31fe | Intel            | 631xESB/632xESB/3100 Chipset UHCI... | 17    | uhci_hcd   | [8CF84909E3](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G5/CB5A662BC228/CENTOS-7/3.10.0-1160.88.1.EL7.X86_64/X86_64/8CF84909E3>) |
| 8086:268a | 103c:31fe | Intel            | 631xESB/632xESB/3100 Chipset UHCI... | 17    | uhci_hcd   | [8CF84909E3](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G5/CB5A662BC228/CENTOS-7/3.10.0-1160.88.1.EL7.X86_64/X86_64/8CF84909E3>) |
| 8086:268c | 103c:31fe | Intel            | 631xESB/632xESB/3100 Chipset EHCI... | 17    | ehci_pci   | [8CF84909E3](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G5/CB5A662BC228/CENTOS-7/3.10.0-1160.88.1.EL7.X86_64/X86_64/8CF84909E3>) |
| 8086:268b | 103c:31fe | Intel            | 631xESB/632xESB/3100 Chipset UHCI... | 16    | uhci_hcd   | [8CF84909E3](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G5/CB5A662BC228/CENTOS-7/3.10.0-1160.88.1.EL7.X86_64/X86_64/8CF84909E3>) |
| 8086:3a34 | 1014:3a34 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 16    | uhci_hcd   | [16C68A28D8](<Server/IBM/System/System x3550 M3 -[7944SCP]-/B3404BB51BF1/DEBIAN-10/4.19.0-20-686-PAE/I686/16C68A28D8>) |
| 8086:3a35 | 1014:3a35 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 16    | uhci_hcd   | [16C68A28D8](<Server/IBM/System/System x3550 M3 -[7944SCP]-/B3404BB51BF1/DEBIAN-10/4.19.0-20-686-PAE/I686/16C68A28D8>) |
| 8086:3a36 | 1014:3a36 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 16    | uhci_hcd   | [16C68A28D8](<Server/IBM/System/System x3550 M3 -[7944SCP]-/B3404BB51BF1/DEBIAN-10/4.19.0-20-686-PAE/I686/16C68A28D8>) |
| 8086:3a37 | 1014:3a37 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 16    | uhci_hcd   | [16C68A28D8](<Server/IBM/System/System x3550 M3 -[7944SCP]-/B3404BB51BF1/DEBIAN-10/4.19.0-20-686-PAE/I686/16C68A28D8>) |
| 8086:3a38 | 1014:3a38 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 16    | uhci_hcd   | [16C68A28D8](<Server/IBM/System/System x3550 M3 -[7944SCP]-/B3404BB51BF1/DEBIAN-10/4.19.0-20-686-PAE/I686/16C68A28D8>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a1ec | 8086:7270 | Intel            | C620 Series Chipset Family MROM 0    | 46    |            | [18B2BF9FF4](<Server/Delta Computers/DSS-C621/DSS-C621LTG/EA1701537BF7/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/18B2BF9FF4>) |
| 8086:a1ed | 8086:7270 | Intel            | C620 Series Chipset Family MROM 1    | 37    |            | [18B2BF9FF4](<Server/Delta Computers/DSS-C621/DSS-C621LTG/EA1701537BF7/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/18B2BF9FF4>) |
| 8086:8d7c | 103c:8030 | Intel            | C610/X99 series chipset SPSR         | 27    |            | [28BD32B178](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/3E0FB1FA32D4/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/28BD32B178>) |
| 8086:a1ec | 1028:073a | Intel            | C620 Series Chipset Family MROM 0    | 20    |            | [962B265260](<Server/Dell/Precision/Precision 7920 Tower/8C7F63FF0FE0/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/962B265260>) |
| 8086:a1ec | 8086:35ce | Intel            | C620 Series Chipset Family MROM 0    | 17    |            | [97B57F8628](<Server/YADRO/VEGMAN/VEGMAN S220 Server/91703340854B/RED-OS-7.3.1/5.15.10-1.EL7.X86_64/X86_64/97B57F8628>) |
| 8086:8d7c | 15d9:0821 | Intel            | C610/X99 series chipset SPSR         | 16    |            | [17BF7A3CBC](<Server/Supermicro/SYS-6018/SYS-6018R-WTR/5EE2BAE645DD/CENTOS-7/3.10.0-862.14.4.EL7.X86_64/X86_64/17BF7A3CBC>) |
| 8086:8d7c | 8086:7270 | Intel            | C610/X99 series chipset SPSR         | 16    |            | [BAF3069CD7](<Server/Cisco Systems/UCSC-C220/UCSC-C220-M4S/9D3781D2096F/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/BAF3069CD7>) |
| 8086:a1ed | 1028:073a | Intel            | C620 Series Chipset Family MROM 1    | 13    |            | [962B265260](<Server/Dell/Precision/Precision 7920 Tower/8C7F63FF0FE0/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/962B265260>) |
| 8086:a1ec | 1028:0715 | Intel            | C620 Series Chipset Family MROM 0    | 12    |            | [7AD0D2D67B](<Server/Dell/PowerEdge/PowerEdge R740/FF8CDFB5CB55/UBUNTU-18.04/4.15.0-193-GENERIC/X86_64/7AD0D2D67B>) |
| 8086:a1ec | 1028:0739 | Intel            | C620 Series Chipset Family MROM 0    | 12    |            | [FE6DC0D9C7](<Server/Dell/Precision/Precision 7820 Tower/FB09ECB98D56/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FE6DC0D9C7>) |
| 8086:a1ec | 1590:00eb | Intel            | C620 Series Chipset Family MROM 0    | 12    |            | [74466AD718](<Server/HPE/ProLiant/ProLiant DL360 Gen10 Plus/6004A3CDB655/DEBIAN-11/5.15.107-1-PVE/X86_64/74466AD718>) |
| 8086:8d7c | 15d9:0831 | Intel            | C610/X99 series chipset SPSR         | 11    |            | [5E92E7FE1E](<Server/Supermicro/Super/Super Server/FD3A63BBABAD/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/5E92E7FE1E>) |
| 8086:a1ec | 1043:871e | Intel            | C620 Series Chipset Family MROM 0    | 11    |            | [C874A6D28C](<Server/ASUSTek Computer/ESC8000/ESC8000 G4/05733798C837/UBUNTU-18.04/5.4.0-121-GENERIC/X86_64/C874A6D28C>) |
| 8086:8d7c | 1028:0601 | Intel            | C610/X99 series chipset SPSR         | 10    |            | [1ABE023ED7](<Server/Dell/PowerEdge/PowerEdge R630/0354475C3BDD/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/1ABE023ED7>) |
| 8086:8d7c | 15d9:0857 | Intel            | C610/X99 series chipset SPSR         | 10    |            | [A9AA07EF24](<Server/Supermicro/X10/X10SRA-F/446FAE82E232/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/A9AA07EF24>) |
| 8086:8d7c | 8086:0000 | Intel            | C610/X99 series chipset SPSR         | 10    |            | [9BB50174EF](<Server/DALCO/S2600/S2600WTTR/F200B7AE62EB/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/9BB50174EF>) |
| 8086:8d7c | 1028:0600 | Intel            | C610/X99 series chipset SPSR         | 9     |            | [BE75097D0F](<Server/Dell/PowerEdge/PowerEdge R730/E686E52F7B47/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/BE75097D0F>) |
| 8086:a1ed | 1590:00eb | Intel            | C620 Series Chipset Family MROM 1    | 9     |            | [4CDCAD1148](<Server/HPE/ProLiant/ProLiant DL380 Gen10/AD4000C49F0A/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/4CDCAD1148>) |
| 8086:8d7c | 1043:85f6 | Intel            | C610/X99 series chipset SPSR         | 8     |            | [74269B72B0](<Server/ASUSTek Computer/Z10PE-D16/Z10PE-D16 WS/9FCE74D7C651/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/74269B72B0>) |
| 8086:a1ec | 15d9:096d | Intel            | C620 Series Chipset Family MROM 0    | 8     |            | [DCBB3D117A](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.4.0-105-GENERIC/X86_64/DCBB3D117A>) |
| 8086:a1ed | 15d9:096d | Intel            | C620 Series Chipset Family MROM 1    | 8     |            | [DCBB3D117A](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.4.0-105-GENERIC/X86_64/DCBB3D117A>) |
| 8086:a1ec | 15d9:0967 | Intel            | C620 Series Chipset Family MROM 0    | 7     |            | [DE3332B83C](<Server/Supermicro/SYS-6029/SYS-6029P-WTRT/35C50F3639E9/ACRONIS-CYBER-INFRASTRUCTURE-5.1.0/3.10.0-1160.53.1.VZ7.185.3/X86_64/DE3332B83C>) |
| 8086:a1ec | 17aa:7808 | Intel            | C620 Series Chipset Family MROM 0    | 7     |            | [CEE7ED2CE9](<Server/Lenovo/ThinkSystem/ThinkSystem SR590 -[7X99CTO1WW]-/B1F2BD34820F/ALT-9.0/4.19.79-STD-DEF-ALT1/X86_64/CEE7ED2CE9>) |
| 8086:a1ed | 1028:0739 | Intel            | C620 Series Chipset Family MROM 1    | 7     |            | [FE6DC0D9C7](<Server/Dell/Precision/Precision 7820 Tower/FB09ECB98D56/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FE6DC0D9C7>) |
| 8086:8d7c | 1028:0627 | Intel            | C610/X99 series chipset SPSR         | 6     |            | [14F7ADD408](<Server/Dell/PowerEdge/PowerEdge R730xd/15ED2888E4F5/ARCH/5.19.1-ARCH2-1/X86_64/14F7ADD408>) |
| 8086:a1ec | 1028:0718 | Intel            | C620 Series Chipset Family MROM 0    | 6     |            | [A4F3535E84](<Server/Dell/Precision/Precision 7920 Rack/1D56B1A533A9/UBUNTU-20.04/5.14.0-1057-OEM/X86_64/A4F3535E84>) |
| 8086:a1ec | 103c:81c7 | Intel            | C620 Series Chipset Family MROM 0    | 6     |            | [50CCA471C5](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/010A19E087DC/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/50CCA471C5>) |
| 8086:a1ec | 17aa:7801 | Intel            | C620 Series Chipset Family MROM 0    | 6     |            | [BAFB634A37](<Server/Lenovo/ThinkSystem/ThinkSystem SR530 -[7X08CTO1WW]-/16717DADAA79/CENTOS-7/3.10.0-1160.36.2.EL7.X86_64/X86_64/BAFB634A37>) |
| 8086:a1ec | 1849:a1ec | Intel            | C620 Series Chipset Family MROM 0    | 6     |            | [51DC310024](<Server/Kraftway/Trusted/Trusted TS2000/583173D8B5F2/RED-OS-7.3.2/6.1.11-1.EL7.3.X86_64/X86_64/51DC310024>) |
| 8086:a1ed | 15d9:0967 | Intel            | C620 Series Chipset Family MROM 1    | 6     |            | [DE3332B83C](<Server/Supermicro/SYS-6029/SYS-6029P-WTRT/35C50F3639E9/ACRONIS-CYBER-INFRASTRUCTURE-5.1.0/3.10.0-1160.53.1.VZ7.185.3/X86_64/DE3332B83C>) |
| 8086:a1ed | 1849:a1ed | Intel            | C620 Series Chipset Family MROM 1    | 6     |            | [51DC310024](<Server/Kraftway/Trusted/Trusted TS2000/583173D8B5F2/RED-OS-7.3.2/6.1.11-1.EL7.3.X86_64/X86_64/51DC310024>) |
| 8086:a1ed | 8086:35ce | Intel            | C620 Series Chipset Family MROM 1    | 6     |            | [F5848D1BA2](<Server/DALCO/S2600/S2600WFT/37B0D5359698/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/F5848D1BA2>) |
| 8086:8d7c | 15d9:0832 | Intel            | C610/X99 series chipset SPSR         | 5     |            | [96E896465A](<Server/Supermicro/Super/Super Server/264448779CFE/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/96E896465A>) |
| 8086:8d7c | 15d9:0834 | Intel            | C610/X99 series chipset SPSR         | 5     |            | [16A0245A41](<Server/Supermicro/Super/Super Server/19433F8FA9C4/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/16A0245A41>) |
| 8086:a1ec | 103c:81c6 | Intel            | C620 Series Chipset Family MROM 0    | 5     |            | [C60CE01C1E](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/5FDF871A62B0/UBUNTU-20.04/5.15.0-48-GENERIC/X86_64/C60CE01C1E>) |
| 8086:a1ec | 15d9:095d | Intel            | C620 Series Chipset Family MROM 0    | 5     |            | [6D1F207293](<Server/primeLine Solutions/egino/egino BTO Konfig Server/B668BEC7EEFE/DEBIAN-11/5.15.85-1-PVE/X86_64/6D1F207293>) |
| 8086:a1ec | 15d9:0981 | Intel            | C620 Series Chipset Family MROM 0    | 5     |            | [D9B96BCE95](<Server/Supermicro/Super/Super Server/909986EADB14/UBUNTU-22.10/5.19.0-23-GENERIC/X86_64/D9B96BCE95>) |
| 8086:a1ec | 8086:0000 | Intel            | C620 Series Chipset Family MROM 0    | 5     |            | [F5848D1BA2](<Server/DALCO/S2600/S2600WFT/37B0D5359698/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/F5848D1BA2>) |
| 8086:a1ed | 103c:81c6 | Intel            | C620 Series Chipset Family MROM 1    | 5     |            | [C60CE01C1E](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/5FDF871A62B0/UBUNTU-20.04/5.15.0-48-GENERIC/X86_64/C60CE01C1E>) |
| 8086:a1ed | 15d9:095d | Intel            | C620 Series Chipset Family MROM 1    | 5     |            | [6D1F207293](<Server/primeLine Solutions/egino/egino BTO Konfig Server/B668BEC7EEFE/DEBIAN-11/5.15.85-1-PVE/X86_64/6D1F207293>) |
| 8086:a1ed | 15d9:0981 | Intel            | C620 Series Chipset Family MROM 1    | 5     |            | [D9B96BCE95](<Server/Supermicro/Super/Super Server/909986EADB14/UBUNTU-22.10/5.19.0-23-GENERIC/X86_64/D9B96BCE95>) |
| 1912:001b | 1d49:0a02 | Renesas Techn... | SH7758 PCIe End-Point [PBI]          | 4     |            | [78113D1370](<Server/Lenovo/Flex/Flex System x240 M5 Compute Node -[9532AC1]-/CC76B4AA67C4/DEBIAN-10/4.19.0-16-AMD64/X86_64/78113D1370>) |
| 8086:8d7c | 1028:0639 | Intel            | C610/X99 series chipset SPSR         | 4     |            | [A05562BC52](<Server/Dell/PowerEdge/PowerEdge R430/AFD9B671916C/XUBUNTU-22.04/5.15.0-58-GENERIC/X86_64/A05562BC52>) |
| 8086:8d7c | 1d49:0a00 | Intel            | C610/X99 series chipset SPSR         | 4     |            | [78113D1370](<Server/Lenovo/Flex/Flex System x240 M5 Compute Node -[9532AC1]-/CC76B4AA67C4/DEBIAN-10/4.19.0-16-AMD64/X86_64/78113D1370>) |
| 8086:a1ec | 1028:0716 | Intel            | C620 Series Chipset Family MROM 0    | 4     |            | [02F8E21FA8](<Server/Dell/PowerEdge/PowerEdge R640/D35AD5A42EE7/UBUNTU-20.04/5.4.0-105-GENERIC/X86_64/02F8E21FA8>) |
| 8086:a1ec | 1028:0737 | Intel            | C620 Series Chipset Family MROM 0    | 4     |            | [D2AE46F823](<Server/Dell/XC740xd-12/XC740xd-12 CORE/DD8724B460B5/UBUNTU-18.04/4.15.0-175-GENERIC/X86_64/D2AE46F823>) |
| 8086:a1ec | 1028:07cb | Intel            | C620 Series Chipset Family MROM 0    | 4     |            | [465C40DD0F](<Server/Dell/PowerEdge/PowerEdge T440/1E0687BF68BA/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/465C40DD0F>) |
| 8086:a1ec | 15d9:091c | Intel            | C620 Series Chipset Family MROM 0    | 4     |            | [90F9906D76](<Server/Supermicro/SYS-1029/SYS-1029U-TR25M-BK-LC019/25926C72BE6F/ACRONIS-CYBER-INFRASTRUCTURE-5.1.1/3.10.0-1160.53.1.VZ7.185.3/X86_64/90F9906D76>) |
| 8086:a1ec | 15d9:0953 | Intel            | C620 Series Chipset Family MROM 0    | 4     |            | [A76BB2E30D](<Server/Supermicro/SYS-5029/SYS-5029P-WTR/2D889DFAC2FF/ROCKY-8.5/4.18.0-348.12.2.EL8_5.X86_64/X86_64/A76BB2E30D>) |
| 8086:a1ec | 15d9:0986 | Intel            | C620 Series Chipset Family MROM 0    | 4     |            | [FFA58F1702](<Server/Supermicro/SYS-E300/SYS-E300-9D-8CN8TP/202BFE094BD2/DEBIAN-11/5.10.0-21-AMD64/X86_64/FFA58F1702>) |

