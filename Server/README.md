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
   * [ Flash memory ](#flash-memory-pci)
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
   * [ Rf controller ](#rf-controller-pci)
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
| 1a03:1150 | 1a03:1150 | ASPEED Techno... | AST1150 PCI-to-PCI Bridge            | 495   | shpchp     | [726B65D6E8](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.10/4.18.0-553.27.1.EL8_10.X86_64/X86_64/726B65D6E8>) |
| 8086:2c70 | 8086:8086 | Intel            | Xeon 5600 Series QuickPath Archit... | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2d81 | 8086:8086 | Intel            | Xeon 5600 Series QuickPath Archit... | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2d90 | 8086:8086 | Intel            | Xeon 5600 Series QPI Link 0          | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2d91 | 8086:8086 | Intel            | Xeon 5600 Series QPI Physical 0      | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2d92 | 8086:8086 | Intel            | Xeon 5600 Series Mirror Port Link 0  | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2d93 | 8086:8086 | Intel            | Xeon 5600 Series Mirror Port Link 1  | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2d94 | 8086:8086 | Intel            | Xeon 5600 Series QPI Link 1          | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2d95 | 8086:8086 | Intel            | Xeon 5600 Series QPI Physical 1      | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2d98 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2d99 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2d9a | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2d9c | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2da0 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2da1 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2da2 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2da3 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2da8 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2da9 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2daa | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2dab | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2db0 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2db1 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2db2 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2db3 | 8086:8086 | Intel            | Xeon 5600 Series Integrated Memor... | 271   |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:2030 | 8086:0000 | Intel            | Sky Lake-E PCI Express Root Port A   | 206   | pcieport   | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2032 | 8086:0000 | Intel            | Sky Lake-E PCI Express Root Port C   | 199   | pcieport   | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2020 | 8086:0000 | Intel            | Sky Lake-E DMI3 Registers            | 177   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 1912:0012 | 1912:0012 | Renesas Techn... | SH7757 PCIe-PCI Bridge [PPB]         | 131   | shpchp     | [D63ADBC5DD](<Server/Dell/PowerEdge/PowerEdge R720/13A7060552FC/NIXOS-25.05/6.6.63/X86_64/D63ADBC5DD>) |
| 1912:0013 | 1912:0013 | Renesas Techn... | SH7757 PCIe Switch [PS]              | 131   | pcieport   | [D63ADBC5DD](<Server/Dell/PowerEdge/PowerEdge R720/13A7060552FC/NIXOS-25.05/6.6.63/X86_64/D63ADBC5DD>) |
| 8086:2033 | 8086:0000 | Intel            | Sky Lake-E PCI Express Root Port D   | 124   | pcieport   | [2EA3B6BA11](<Server/Dell/PowerEdge/PowerEdge R740/102E11A0DB9A/DEBIAN-12/6.8.4-2-PVE/X86_64/2EA3B6BA11>) |
| 1556:be00 |           | PLDA             | PCI Express Bridge                   | 117   | shpchp     | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 1022:1482 |           | AMD              | Starship/Matisse PCIe Dummy Host ... | 110   |            | [726B65D6E8](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.10/4.18.0-553.27.1.EL8_10.X86_64/X86_64/726B65D6E8>) |
| 8086:37c0 | 8086:0000 | Intel            | PCI bridge                           | 110   | pcieport   | [122B21A8E4](<Server/Others/Others/Others/DB0155950DC6/DEBIAN-12/6.8.12-5-PVE/X86_64/122B21A8E4>) |
| 1022:1484 | 1022:1484 | AMD              | Starship/Matisse Internal PCIe GP... | 109   | pcieport   | [726B65D6E8](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.10/4.18.0-553.27.1.EL8_10.X86_64/X86_64/726B65D6E8>) |
| 1912:001a | 1912:001a | Renesas Techn... | SH7758 PCIe-PCI Bridge [PPB]         | 108   | shpchp     | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 1912:001d | 1912:001d | Renesas Techn... | SH7758 PCIe Switch [PS]              | 108   | pcieport   | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:1d10 | 103c:18a9 | Intel            | C600/X79 series chipset PCI Expre... | 103   | pcieport   | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |
| 8086:1d1e | 103c:18a9 | Intel            | C600/X79 series chipset PCI Expre... | 103   | pcieport   | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |
| 8086:1d3e | 103c:18a9 | Intel            | C600/X79 series chipset PCI Expre... | 103   | pcieport   | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |
| 8086:1d41 |           | Intel            | C600/X79 series chipset LPC Contr... | 103   | lpc_ich    | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |
| 8086:244e | 103c:18a9 | Intel            | 82801 PCI Bridge                     | 103   |            | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |
| 8086:8d10 | 103c:8030 | Intel            | C610/X99 series chipset PCI Expre... | 103   | pcieport   | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:8d14 | 103c:8030 | Intel            | C610/X99 series chipset PCI Expre... | 103   | pcieport   | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:8d18 | 103c:8030 | Intel            | C610/X99 series chipset PCI Expre... | 103   | pcieport   | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:8d44 | 103c:8030 | Intel            | C610/X99 series chipset LPC Contr... | 103   | lpc_ich    | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:8d1c | 103c:8030 | Intel            | C610/X99 series chipset PCI Expre... | 101   | pcieport   | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:8d1e | 103c:8030 | Intel            | C610/X99 series chipset PCI Expre... | 101   | pcieport   | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:341c |           | Intel            | 7500/5520/5500/X58 Unknown           | 97    |            | [B076CBF109](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/416C8912B3CC/DEBIAN/6.11.10-AMD64/X86_64/B076CBF109>) |
| 8086:341d |           | Intel            | 7500/5520/5500/X58 Unknown           | 97    |            | [B076CBF109](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/416C8912B3CC/DEBIAN/6.11.10-AMD64/X86_64/B076CBF109>) |

### Canbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1a07:0011 | 1a07:0011 | Kvaser AB        | Mini PCIe 2xHS v2                    | 1     | kvaser_... | [196C8EB317](<Server/Neousys Technology/Nuvo-7100VTC/Nuvo-7100VTC Series/E44E3E216941/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/196C8EB317>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:5229 | 10ec:5229 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx_pci   | [AE43167B8A](<Server/ECS/LIVA/LIVA Q2/6F0AAEC80AB2/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/AE43167B8A>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19a2:0800 | 1734:11cc | Emulex           | ServerView iRMC HTI                  | 9     |            | [ED6A47B6F9](<Server/Fujitsu/PRIMERGY/PRIMERGY TX2540 M1/6D63F93EE5A2/DEBIAN-12/6.11.10+BPO-AMD64/X86_64/ED6A47B6F9>) |
| 8086:2710 | 8086:0000 | Intel            | HQM/DLB                              | 8     |            | [96962C9FAC](<Server/Supermicro/SYS-511/SYS-511E-WR/4D3CCDFB3187/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/96962C9FAC>) |
| 8086:19e2 | 8086:0000 | Intel            | Atom Processor C3000 Series Quick... | 6     | qat_c3xxx  | [D809C4B99D](<Server/Supermicro/Super/Super Server/5282A3BE97F8/UBUNTU-22.04/6.5.0-18-GENERIC/X86_64/D809C4B99D>) |
| 8086:4940 | 8086:0000 | Intel            | 4xxx Series QAT                      | 6     | qat_4xxx   | [80A2F3D367](<Server/Lenovo/ThinkSystem/ThinkSystem SR950 V3/80C0A7FFD0E3/RHEL-9/5.14.0-70.22.1.EL9_0.X86_64/X86_64/80A2F3D367>) |
| 8086:0435 | 8086:0000 | Intel            | DH895XCC Series QAT                  | 3     | qat_dh8... | [F44D953566](<Server/IBM/System/System x3650 M4: -[2145DH8]-/D19C902B5426/ARCH-ROLLING/6.9.3-ARCH1-1/X86_64/F44D953566>) |
| 8086:37c8 | 8086:0000 | Intel            | C62x Chipset QuickAssist Technology  | 3     | qat_c62x   | [FFA58F1702](<Server/Supermicro/SYS-E300/SYS-E300-9D-8CN8TP/202BFE094BD2/DEBIAN-11/5.10.0-21-AMD64/X86_64/FFA58F1702>) |
| 8086:4942 | 8086:0000 | Intel            | 401xx Series QAT                     | 2     | qat_4xxx   | [96962C9FAC](<Server/Supermicro/SYS-511/SYS-511E-WR/4D3CCDFB3187/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/96962C9FAC>) |
| 1000:0a01 | 1000:0a01 | Broadcom / LSI   | Co-processor                         | 1     |            | [DDFEFE06A3](<Server/Sun Microsystems/Sun/Sun Fire X4170 M2 SERVER/82C4B5F145E4/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/DDFEFE06A3>) |
| 1734:1228 | 1734:1229 | Fujitsu Techn... | Fujitsu Co-processor                 | 1     |            | [2F6EE7ADA1](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2540 M4/4D63FF3C8C3D/DEBIAN/6.6.15-AMD64/X86_64/2F6EE7ADA1>) |
| 1a03:2402 | 1a03:2402 | ASPEED Techno... | Co-processor                         | 1     |            | [5FB0C3A747](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2450 M2/6F7BBA6E51B5/GENTOO-2.15/6.6.30-1-LTS/X86_64/5FB0C3A747>) |
| 8086:0434 | 8086:0000 | Intel            | DH89XXCC Series QAT                  | 1     |            | [14C76E0C83](<Server/F5 Networks/C/C117/C1512B26FE54/ALPINE-3.13.2/5.10.16-0-LTS/X86_64/14C76E0C83>) |
| 8086:18a0 | 8086:0000 | Intel            | Atom Processor P5xxx Series QAT      | 1     |            | [C618310D44](<Server/Dell/PowerEdge/PowerEdge XR4510c/35E133588594/DEBIAN-12/6.1.0-10-AMD64/X86_64/C618310D44>) |
| 8086:18ee | 8086:0000 | Intel            | 200xx Series QAT                     | 1     |            | [3751D50DDE](<Server/Supermicro/Super/Super Server/ACFD57B232A4/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/3751D50DDE>) |
| 8086:1f18 | 15d9:0820 | Intel            | Atom processor C2000 QAT             | 1     |            | [B9AC0D657E](<Server/Supermicro/A1/A1SRM-2558F/DAF42406F667/FEDORA-32/5.8.16-200.FC32.X86_64/X86_64/B9AC0D657E>) |
| 8086:225c | 8086:2500 | Intel            | Xeon Phi coprocessor SE10/7120 se... | 1     | mic_host   | [9D9DA282F6](<Server/Dedicated Computing/OEM-F7342/OEM-F7342-00/A56806D283ED/UBUNTU-20.04/5.4.0-45-GENERIC/X86_64/9D9DA282F6>) |
| 8086:2714 | 8086:0000 | Intel            | Co-processor                         | 1     |            | [F71EAE46A6](<Server/Intel/BIRCHSTREAM/BIRCHSTREAM/1F03C9158405/XUBUNTU-24.04/6.8.0-48-GENERIC/X86_64/F71EAE46A6>) |
| 8086:37c8 | 8086:0001 | Intel            | C62x Chipset QuickAssist Technology  | 1     | qat_c62x   | [F9ECA543F7](<Server/Gigabyte Technology/MZ32/MZ32-AR0-00/EF6E29D7D44C/UBUNTU-23.10/6.5.0-44-GENERIC/X86_64/F9ECA543F7>) |
| 8086:37c8 | 8086:0002 | Intel            | C62x Chipset QuickAssist Technology  | 1     | qat_c62x   | [2384B2E12C](<Server/Dell/PowerEdge/PowerEdge R740/92D8B2360623/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/2384B2E12C>) |
| 8086:4941 | 8086:0000 | Intel            | 4xxx Series QAT Virtual Function     | 1     | vfio_pci   | [3DDB00DA94](<Server/Intel/ArcherCity/ArcherCity/35F42C801DE0/FEDORA-37/6.1.7-200.FC37.X86_64/X86_64/3DDB00DA94>) |
| 8086:4944 | 8086:09a2 | Intel            | 402xx Series QAT                     | 1     | qat_4xxx   | [F71EAE46A6](<Server/Intel/BIRCHSTREAM/BIRCHSTREAM/1F03C9158405/XUBUNTU-24.04/6.8.0-48-GENERIC/X86_64/F71EAE46A6>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a1ba | 8086:7270 | Intel            | C620 Series Chipset Family MEI Co... | 92    | mei_me     | [122B21A8E4](<Server/Others/Others/Others/DB0155950DC6/DEBIAN-12/6.8.12-5-PVE/X86_64/122B21A8E4>) |
| 8086:a1be | 8086:7270 | Intel            | C620 Series Chipset Family MEI Co... | 92    |            | [122B21A8E4](<Server/Others/Others/Others/DB0155950DC6/DEBIAN-12/6.8.12-5-PVE/X86_64/122B21A8E4>) |
| 8086:a1bb | 8086:7270 | Intel            | C620 Series Chipset Family MEI Co... | 86    |            | [122B21A8E4](<Server/Others/Others/Others/DB0155950DC6/DEBIAN-12/6.8.12-5-PVE/X86_64/122B21A8E4>) |
| 8086:8d3a | 8086:7270 | Intel            | C610/X99 series chipset MEI Contr... | 41    | mei_me     | [142EA5AAAB](<Server/Lenovo/70FRR156CN/70FRR156CN RD450X/8535AF5D51BA/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/142EA5AAAB>) |
| 8086:8d3b | 8086:7270 | Intel            | C610/X99 series chipset MEI Contr... | 41    |            | [142EA5AAAB](<Server/Lenovo/70FRR156CN/70FRR156CN RD450X/8535AF5D51BA/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/142EA5AAAB>) |
| 8086:1d3a | 15d9:0636 | Intel            | C600/X79 series chipset MEI Contr... | 39    | mei_me     | [86B4E152AD](<Server/Supermicro/X9/X9DRW/D2C6B0237967/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/86B4E152AD>) |
| 8086:1d3b | 15d9:0636 | Intel            | C600/X79 series chipset MEI Contr... | 39    |            | [86B4E152AD](<Server/Supermicro/X9/X9DRW/D2C6B0237967/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/86B4E152AD>) |
| 8086:1d3a | 1028:048c | Intel            | C600/X79 series chipset MEI Contr... | 36    | mei_me     | [D63ADBC5DD](<Server/Dell/PowerEdge/PowerEdge R720/13A7060552FC/NIXOS-25.05/6.6.63/X86_64/D63ADBC5DD>) |
| 8086:1d3b | 1028:048c | Intel            | C600/X79 series chipset MEI Contr... | 36    |            | [D63ADBC5DD](<Server/Dell/PowerEdge/PowerEdge R720/13A7060552FC/NIXOS-25.05/6.6.63/X86_64/D63ADBC5DD>) |
| 8086:a1ba | 1028:073a | Intel            | C620 Series Chipset Family MEI Co... | 29    | mei_me     | [B75294443B](<Server/Dell/Precision/Precision 7920 Tower/5E36FA18A2AE/KUBUNTU-20.04/5.15.0-84-GENERIC/X86_64/B75294443B>) |
| 8086:a1ba | 15d9:0967 | Intel            | C620 Series Chipset Family MEI Co... | 27    | mei_me     | [01602FD84E](<Server/Supermicro/SYS-6019/SYS-6019P-WTR/0C2A376E8BE8/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/01602FD84E>) |
| 8086:a1bb | 15d9:0967 | Intel            | C620 Series Chipset Family MEI Co... | 27    |            | [01602FD84E](<Server/Supermicro/SYS-6019/SYS-6019P-WTR/0C2A376E8BE8/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/01602FD84E>) |
| 8086:a1be | 15d9:0967 | Intel            | C620 Series Chipset Family MEI Co... | 27    |            | [01602FD84E](<Server/Supermicro/SYS-6019/SYS-6019P-WTR/0C2A376E8BE8/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/01602FD84E>) |
| 8086:1d3a | 1043:84ef | Intel            | C600/X79 series chipset MEI Contr... | 26    | mei_me     | [E805BE0AAC](<Server/Kraftway/GEG/GEG/C4E325834440/DEBIAN-12/6.1.0-27-AMD64/X86_64/E805BE0AAC>) |
| 8086:1d3b | 1043:84ef | Intel            | C600/X79 series chipset MEI Contr... | 26    |            | [E805BE0AAC](<Server/Kraftway/GEG/GEG/C4E325834440/DEBIAN-12/6.1.0-27-AMD64/X86_64/E805BE0AAC>) |
| 8086:1d3a | 152d:899b | Intel            | C600/X79 series chipset MEI Contr... | 25    | mei_me     | [7E09CCDA22](<Server/ETegro Technologies/Hyperion/Hyperion RS125 G4/5259A72AB62F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/7E09CCDA22>) |
| 8086:1d3b | 152d:899b | Intel            | C600/X79 series chipset MEI Contr... | 25    |            | [7E09CCDA22](<Server/ETegro Technologies/Hyperion/Hyperion RS125 G4/5259A72AB62F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/7E09CCDA22>) |
| 8086:8d3a | 1028:0601 | Intel            | C610/X99 series chipset MEI Contr... | 24    | mei_me     | [44126F8D86](<Server/Dell/PowerEdge/PowerEdge R630/23D674735CB9/GENTOO-2.15/6.6.38-GENTOO-MANS/X86_64/44126F8D86>) |
| 8086:8d3b | 1028:0601 | Intel            | C610/X99 series chipset MEI Contr... | 24    |            | [44126F8D86](<Server/Dell/PowerEdge/PowerEdge R630/23D674735CB9/GENTOO-2.15/6.6.38-GENTOO-MANS/X86_64/44126F8D86>) |
| 8086:a13a | 8086:1999 | Intel            | 100 Series/C230 Series Chipset Fa... | 24    | mei_me     | [172A6309DF](<Server/Tarox/ParX/ParX T100c G6 Server/24E1CEA11A00/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/172A6309DF>) |
| 8086:a1ba | 8086:35ce | Intel            | C620 Series Chipset Family MEI Co... | 23    | mei_me     | [781F43495A](<Server/Intel/S2600/S2600WFT/B54D5A70237A/RED-OS-7.3.2/5.15.87-1.EL7.3.X86_64/X86_64/781F43495A>) |
| 8086:a1be | 8086:35ce | Intel            | C620 Series Chipset Family MEI Co... | 23    |            | [781F43495A](<Server/Intel/S2600/S2600WFT/B54D5A70237A/RED-OS-7.3.2/5.15.87-1.EL7.3.X86_64/X86_64/781F43495A>) |
| 8086:a1ba | 1590:00eb | Intel            | C620 Series Chipset Family MEI Co... | 21    | mei_me     | [D9F97B2071](<Server/HPE/ProLiant/ProLiant DL380 Gen10/6D60567E7E8D/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/D9F97B2071>) |
| 8086:a1be | 1590:00eb | Intel            | C620 Series Chipset Family MEI Co... | 21    |            | [D9F97B2071](<Server/HPE/ProLiant/ProLiant DL380 Gen10/6D60567E7E8D/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/D9F97B2071>) |
| 8086:8d3a | 1028:0627 | Intel            | C610/X99 series chipset MEI Contr... | 20    | mei_me     | [72A4F63713](<Server/Dell/PowerEdge/PowerEdge R730XD/1A3F6F422946/DEBIAN-12/6.8.12-4-PVE/X86_64/72A4F63713>) |
| 8086:8d3a | 15d9:0821 | Intel            | C610/X99 series chipset MEI Contr... | 20    | mei_me     | [98EF58F80D](<Server/Supermicro/SYS-6018/SYS-6018R-WTR/4A5A129EA8CA/CENTOS-7/3.10.0-1160.83.1.EL7.X86_64/X86_64/98EF58F80D>) |
| 8086:8d3b | 1028:0627 | Intel            | C610/X99 series chipset MEI Contr... | 20    |            | [72A4F63713](<Server/Dell/PowerEdge/PowerEdge R730XD/1A3F6F422946/DEBIAN-12/6.8.12-4-PVE/X86_64/72A4F63713>) |
| 8086:8d3b | 15d9:0821 | Intel            | C610/X99 series chipset MEI Contr... | 20    |            | [98EF58F80D](<Server/Supermicro/SYS-6018/SYS-6018R-WTR/4A5A129EA8CA/CENTOS-7/3.10.0-1160.83.1.EL7.X86_64/X86_64/98EF58F80D>) |
| 8086:a1bb | 8086:35ce | Intel            | C620 Series Chipset Family MEI Co... | 20    |            | [781F43495A](<Server/Intel/S2600/S2600WFT/B54D5A70237A/RED-OS-7.3.2/5.15.87-1.EL7.3.X86_64/X86_64/781F43495A>) |
| 8086:1d3a | 1028:04ce | Intel            | C600/X79 series chipset MEI Contr... | 19    | mei_me     | [33A45E355F](<Server/Dell/PowerEdge/PowerEdge R620/C7F9C68EF445/CENTOS-6/2.6.32-754.33.1.EL6.X86_64/X86_64/33A45E355F>) |
| 8086:1d3b | 1028:04ce | Intel            | C600/X79 series chipset MEI Contr... | 19    |            | [33A45E355F](<Server/Dell/PowerEdge/PowerEdge R620/C7F9C68EF445/CENTOS-6/2.6.32-754.33.1.EL6.X86_64/X86_64/33A45E355F>) |
| 8086:a1ba | 1028:0715 | Intel            | C620 Series Chipset Family MEI Co... | 19    | mei_me     | [2EA3B6BA11](<Server/Dell/PowerEdge/PowerEdge R740/102E11A0DB9A/DEBIAN-12/6.8.4-2-PVE/X86_64/2EA3B6BA11>) |
| 8086:a1bb | 1028:0715 | Intel            | C620 Series Chipset Family MEI Co... | 19    |            | [2EA3B6BA11](<Server/Dell/PowerEdge/PowerEdge R740/102E11A0DB9A/DEBIAN-12/6.8.4-2-PVE/X86_64/2EA3B6BA11>) |
| 8086:a1be | 1028:0715 | Intel            | C620 Series Chipset Family MEI Co... | 19    |            | [2EA3B6BA11](<Server/Dell/PowerEdge/PowerEdge R740/102E11A0DB9A/DEBIAN-12/6.8.4-2-PVE/X86_64/2EA3B6BA11>) |
| 8086:1d3a | 1028:04fa | Intel            | C600/X79 series chipset MEI Contr... | 18    | mei_me     | [B416E87C4A](<Server/Dell/PowerEdge/PowerEdge T320/7C98CB79C6C7/OPENMANDRIVA-24.09/6.11.0-DESKTOP-2OMV2490/X86_64/B416E87C4A>) |
| 8086:1d3b | 1028:04fa | Intel            | C600/X79 series chipset MEI Contr... | 18    |            | [B416E87C4A](<Server/Dell/PowerEdge/PowerEdge T320/7C98CB79C6C7/OPENMANDRIVA-24.09/6.11.0-DESKTOP-2OMV2490/X86_64/B416E87C4A>) |
| 8086:a13b | 8086:1999 | Intel            | 100 Series/C230 Series Chipset Fa... | 18    | mei_me     | [172A6309DF](<Server/Tarox/ParX/ParX T100c G6 Server/24E1CEA11A00/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/172A6309DF>) |
| 8086:a1ba | 1458:1000 | Intel            | C620 Series Chipset Family MEI Co... | 17    | mei_me     | [F76FC4031D](<Server/PSSC Labs/SS4000/SS4000HD/13084E646FAA/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/F76FC4031D>) |
| 8086:a1bb | 1458:1000 | Intel            | C620 Series Chipset Family MEI Co... | 17    |            | [F76FC4031D](<Server/PSSC Labs/SS4000/SS4000HD/13084E646FAA/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/F76FC4031D>) |
| 8086:a1be | 1458:1000 | Intel            | C620 Series Chipset Family MEI Co... | 17    |            | [F76FC4031D](<Server/PSSC Labs/SS4000/SS4000HD/13084E646FAA/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/F76FC4031D>) |
| 8086:8d3a | 1028:0600 | Intel            | C610/X99 series chipset MEI Contr... | 16    | mei_me     | [888A235104](<Server/Dell/PowerEdge/PowerEdge R730/B44B0E51BDB3/DEBIAN-12/6.8.12-4-PVE/X86_64/888A235104>) |
| 8086:8d3b | 1028:0600 | Intel            | C610/X99 series chipset MEI Contr... | 16    |            | [888A235104](<Server/Dell/PowerEdge/PowerEdge R730/B44B0E51BDB3/DEBIAN-12/6.8.12-4-PVE/X86_64/888A235104>) |
| 8086:a1ba | 1028:0739 | Intel            | C620 Series Chipset Family MEI Co... | 16    | mei_me     | [BA0626CE0A](<Server/Dell/Precision/Precision 7820 Tower/3792A2743A38/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/BA0626CE0A>) |
| 8086:1d3a | 15d9:0626 | Intel            | C600/X79 series chipset MEI Contr... | 15    | mei_me     | [39232DFDE3](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/B0C1ED30C610/DEBIAN-12/6.1.0-25-AMD64/X86_64/39232DFDE3>) |
| 8086:1d3b | 15d9:0626 | Intel            | C600/X79 series chipset MEI Contr... | 14    |            | [39232DFDE3](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/B0C1ED30C610/DEBIAN-12/6.1.0-25-AMD64/X86_64/39232DFDE3>) |
| 8086:8d3a | 15d9:0831 | Intel            | C610/X99 series chipset MEI Contr... | 14    | mei_me     | [2BAD48B8D4](<Server/Silicon Mechanics/Rackform/Rackform R309.v5/8442C8D36737/DEBIAN-12/6.1.0-21-AMD64/X86_64/2BAD48B8D4>) |
| 8086:8d3a | 19e5:2062 | Intel            | C610/X99 series chipset MEI Contr... | 14    | mei_me     | [EDA2D8550F](<Server/HUAWEI/RH1288/RH1288 V3/899B0DE1B12F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/EDA2D8550F>) |
| 8086:8d3b | 15d9:0831 | Intel            | C610/X99 series chipset MEI Contr... | 14    |            | [2BAD48B8D4](<Server/Silicon Mechanics/Rackform/Rackform R309.v5/8442C8D36737/DEBIAN-12/6.1.0-21-AMD64/X86_64/2BAD48B8D4>) |
| 8086:8d3b | 19e5:2062 | Intel            | C610/X99 series chipset MEI Contr... | 14    |            | [EDA2D8550F](<Server/HUAWEI/RH1288/RH1288 V3/899B0DE1B12F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/EDA2D8550F>) |
| 8086:51e0 |           | Intel            | Alder Lake PCH HECI Controller       | 13    | mei_me     | [DF42F11E59](<Server/GEEKOM/GT13/GT13 Pro/EF7C9F2D8B32/LINUXMINT-22/6.8.0-48-GENERIC/X86_64/DF42F11E59>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1498 | 1022:1498 | AMD              | Starship/Matisse PTDMA               | 90    | ptdma      | [726B65D6E8](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.10/4.18.0-553.27.1.EL8_10.X86_64/X86_64/726B65D6E8>) |
| 1022:1486 | 1022:1486 | AMD              | Starship/Matisse Cryptographic Co... | 74    | ccp        | [726B65D6E8](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.10/4.18.0-553.27.1.EL8_10.X86_64/X86_64/726B65D6E8>) |
| 1022:1649 | 1022:1649 | AMD              | Family 19h PSP/CCP                   | 20    | ccp        | [EE0C91380E](<Server/ASRockRack/B650/B650D4U-2L2T-BCM/4E50B00275AF/ALMA-8.10/4.18.0-553.33.1.EL8_10.X86_64/X86_64/EE0C91380E>) |
| 1022:14ca | 1022:14ca | AMD              | Genoa CCP/PSP 4.0 Device             | 17    | ccp        | [E3AF2BABD8](<Server/Dell/PowerEdge/PowerEdge R6625/674A81CD0424/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/E3AF2BABD8>) |
| 1022:1486 | 1458:1000 | AMD              | Starship/Matisse Cryptographic Co... | 14    | ccp        | [5F638CAF1F](<Server/Gigabyte Technology/G292/G292-Z20-00/38987F4940DE/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/5F638CAF1F>) |
| 1022:1578 | 1022:1578 | AMD              | Carrizo Platform Security Processor  | 14    |            | [F83E3EE442](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/00F75AC4089A/FEDORA-40/6.10.10-200.FC40.X86_64/X86_64/F83E3EE442>) |
| 1022:1456 | 1022:1456 | AMD              | Family 17h (Models 00h-0fh) Platf... | 13    | ccp        | [65D9CE4263](<Server/Supermicro/Super/Super Server/1BBC024DD007/DEBIAN-12/6.8.12-4-PVE/X86_64/65D9CE4263>) |
| 1022:1468 | 1022:1468 | AMD              | Zeppelin Cryptographic Coprocesso... | 13    | ccp        | [65D9CE4263](<Server/Supermicro/Super/Super Server/1BBC024DD007/DEBIAN-12/6.8.12-4-PVE/X86_64/65D9CE4263>) |
| 1022:1498 | 1458:1000 | AMD              | Starship/Matisse PTDMA               | 13    | ptdma      | [5F638CAF1F](<Server/Gigabyte Technology/G292/G292-Z20-00/38987F4940DE/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/5F638CAF1F>) |
| 1022:1486 | 1028:08fc | AMD              | Starship/Matisse Cryptographic Co... | 11    | ccp        | [CE34F45F28](<Server/AWS Elemental/Appliance/Appliance/78AD1C73F775/UBUNTU-22.04/6.5.0-27-GENERIC/X86_64/CE34F45F28>) |
| 1022:1498 | 1028:08fc | AMD              | Starship/Matisse PTDMA               | 11    | ptdma      | [CE34F45F28](<Server/AWS Elemental/Appliance/Appliance/78AD1C73F775/UBUNTU-22.04/6.5.0-27-GENERIC/X86_64/CE34F45F28>) |
| 1022:15df | 1022:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 9     | ccp        | [650A06CBD5](<Server/ASRockRack/X570/X570D4U/BD8DD3707384/NIXOS-24.11/6.6.63/X86_64/650A06CBD5>) |
| 1022:1486 | 1028:08ff | AMD              | Starship/Matisse Cryptographic Co... | 6     | ccp        | [77F946C99B](<Server/Dell/PowerEdge/PowerEdge R7525/ED52A1D54F9D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/77F946C99B>) |
| 1022:1498 | 1028:08ff | AMD              | Starship/Matisse PTDMA               | 6     | ptdma      | [77F946C99B](<Server/Dell/PowerEdge/PowerEdge R7525/ED52A1D54F9D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/77F946C99B>) |
| 1022:1456 | 1458:1000 | AMD              | Family 17h (Models 00h-0fh) Platf... | 5     | ccp        | [182255B026](<Server/Gigabyte Technology/G431/G431-MM0-OT/04B3B45439D3/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/182255B026>) |
| 1022:1468 | 1458:1000 | AMD              | Zeppelin Cryptographic Coprocesso... | 5     | ccp        | [182255B026](<Server/Gigabyte Technology/G431/G431-MM0-OT/04B3B45439D3/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/182255B026>) |
| 1022:1486 | 1028:08fd | AMD              | Starship/Matisse Cryptographic Co... | 4     | ccp        | [28E8ABBBDF](<Server/Dell/PowerEdge/PowerEdge R7515/8E207635BBF5/NIXOS-23.11/6.5.12/X86_64/28E8ABBBDF>) |
| 1022:1498 | 1028:08fd | AMD              | Starship/Matisse PTDMA               | 4     | ptdma      | [28E8ABBBDF](<Server/Dell/PowerEdge/PowerEdge R7515/8E207635BBF5/NIXOS-23.11/6.5.12/X86_64/28E8ABBBDF>) |
| 1022:1456 | 1028:07f9 | AMD              | Family 17h (Models 00h-0fh) Platf... | 2     | ccp        | [FD88331144](<Server/Dell/PowerEdge/PowerEdge R7425/1C2794FDE243/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/FD88331144>) |
| 1022:1468 | 1028:07f9 | AMD              | Zeppelin Cryptographic Coprocesso... | 2     | ccp        | [FD88331144](<Server/Dell/PowerEdge/PowerEdge R7425/1C2794FDE243/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/FD88331144>) |
| 1022:15df | 1458:1000 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     | ccp        | [722F640CCD](<Server/Gigabyte Technology/MC12/MC12-LE0-00/37078BD0F3C1/UBUNTU-22.04/6.5.0-18-GENERIC/X86_64/722F640CCD>) |
| 1022:1649 | 1458:1000 | AMD              | Family 19h PSP/CCP                   | 2     | ccp        | [1F2C7821A0](<Server/Giga Computing/MC13/MC13-LE1-000/338E31DACCCB/UBUNTU-22.04/5.15.0-91-GENERIC/X86_64/1F2C7821A0>) |
| 1022:1486 | 1028:0900 | AMD              | Starship/Matisse Cryptographic Co... | 1     | ccp        | [382F999542](<Server/Dell/PowerEdge/PowerEdge C6525/B11FEC7694D8/ARCH/5.15.59-1-LTS/X86_64/382F999542>) |
| 1022:1498 | 1028:0900 | AMD              | Starship/Matisse PTDMA               | 1     | ptdma      | [382F999542](<Server/Dell/PowerEdge/PowerEdge C6525/B11FEC7694D8/ARCH/5.15.59-1-LTS/X86_64/382F999542>) |
| 1022:1498 | 1849:1498 | AMD              | Starship/Matisse PTDMA               | 1     |            | [3C11A0856C](<Server/ASRockRack/ROMED8/ROMED8-2T/9F9114A5632E/DEBIAN-10/5.8.0-0.BPO.2-AMD64/X86_64/3C11A0856C>) |
| 1022:1649 | 15d9:1c97 | AMD              | Family 19h PSP/CCP                   | 1     | ccp        | [CAB997495E](<Server/Supermicro/Super/Super Server/9ABB78B85737/DEBIAN-12/6.8.12-2-PVE/X86_64/CAB997495E>) |

### Firewire controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 104c:8023 | 15d9:0100 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 9     | firewir... | [CE40C8C96F](<Server/DEPO Computers/X8/X8DAH/6FED46D0B032/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/CE40C8C96F>) |
| 1102:4001 | 1102:0010 | Creative Labs    | SB Audigy FireWire Port              | 8     | firewir... | [2D3C35E364](<Server/Fujitsu/PRIMERGY/PRIMERGY TX2540 M1/25DC1F84A0CF/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/2D3C35E364>) |
| 104c:8023 | 15d9:0805 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 6     | firewir... | [4B0CFEC9A7](<Server/Supermicro/X10/X10SAE/FF0B31A8C494/NOBARA-37/6.2.10-200.FSYNC.FC37.X86_64/X86_64/4B0CFEC9A7>) |
| 1106:3403 | 1106:3403 | VIA Technologies | VT6315 Series Firewire Controller    | 6     | firewir... | [1B2CDEC714](<Server/ASUSTek Computer/Z9PE-D8/Z9PE-D8 WS/07125A08677D/FEDORA-39/6.7.4-200.FC39.X86_64/X86_64/1B2CDEC714>) |
| 1106:3403 | 1043:8384 | VIA Technologies | VT6315 Series Firewire Controller    | 5     | firewir... | [C3665EBF57](<Server/ASUSTek Computer/Z9PE-D8/Z9PE-D8 WS/5BADF976211F/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/C3665EBF57>) |
| 104c:8023 | 8086:34e2 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 4     | firewir... | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 1106:3044 | 1106:3044 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 4     | firewir... | [E74EF17929](<Server/Dell/PowerEdge/PowerEdge R210/A10F18121DF9/UBUNTU-22.04/6.2.0-36-GENERIC/X86_64/E74EF17929>) |
| 1106:3044 | 1462:6520 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 4     | firewir... | [1888FA6DF7](<Server/MSI/MCP/MCP55/E26C4EDDD3C1/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/1888FA6DF7>) |
| 104c:823f | 8086:3594 | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 3     | firewir... | [96CDA648C2](<Server/Intel/W2600/W2600CR/577694DF59DA/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/96CDA648C2>) |
| 1033:00f2 | 1033:00f2 | NEC Computers    | uPD72874 [Firewarden] IEEE1394a O... | 1     | firewir... | [5018997F48](<Server/Supermicro/Super/Super Server/0D2971EB9E61/GENTOO-2.14/6.1.41-GENTOO.AI/X86_64/5018997F48>) |
| 104c:8023 | 108e:6676 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | firewir... | [7CC89D3CBA](<Server/Sun Microsystems/Sun/Sun Ultra 40 M2 Workstation/3EE30E1E3EAB/MX-21/5.16.0-18.1-LIQUORIX-AMD64/X86_64/7CC89D3CBA>) |
| 104c:8023 | 10f1:2895 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | firewir... | [768571B831](<Server/TYAN Computer/S/S2895/4B5DFCDB09B6/LINUXMINT-20/5.4.0-58-GENERIC/X86_64/768571B831>) |
| 104c:8023 | 10f1:2915 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | firewir... | [0D3D065311](<Server/TYAN Computer/MCP/MCP55/DB4D10F83692/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/0D3D065311>) |
| 104c:8023 | 15d9:0653 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | firewir... | [171EE8DB12](<Server/Supermicro/C7/C7Z87/4BD99E9BA2B9/XUBUNTU-19.10/5.3.0-18-LOWLATENCY/X86_64/171EE8DB12>) |
| 104c:8023 | 15d9:1411 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | firewir... | [039BF2C96A](<Server/Supermicro/X8/X8DA3/578F928B17F4/LUBUNTU-20.04/5.4.0-42-GENERIC/X86_64/039BF2C96A>) |
| 104c:8024 |           | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 1     | firewir... | [AE2D4DE7A3](<Server/Supermicro/X8/X8DT3/E0190A2AFA14/UBUNTU-24.04/6.8.0-47-GENERIC/X86_64/AE2D4DE7A3>) |
| 104c:8024 | 104c:8010 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 1     | firewir... | [18B25AC51A](<Server/TYAN Computer/S/S4882/84BBA0EA52AC/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/18B25AC51A>) |
| 104c:8024 | 1458:132c | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 1     | firewir... | [0AC54E7FB4](<Server/Gigabyte Technology/GA-6/GA-6PXSV1/54F5641A961B/KAISEN-1.6/5.10.0-KAISEN3-AMD64/X86_64/0AC54E7FB4>) |
| 104c:823f | 3412:7856 | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 1     | firewir... | [21E2FBBB75](<Server/Supermicro/Super/Super Server/A70DB16AB074/UBUNTU-18.04/4.15.0-29-GENERIC/X86_64/21E2FBBB75>) |
| 1102:4001 |           | Creative Labs    | SB Audigy FireWire Port              | 1     | firewir... | [319647C509](<Server/Dell/PowerEdge/PowerEdge 1800/DEFCB85959FA/UBUNTU-23.10/6.5.0-25-LOWLATENCY/X86_64/319647C509>) |
| 1106:3044 | 108e:534d | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 1     | firewir... | [1F35F79302](<Server/Sun Microsystems/Ultra20/Ultra20 M2/23D902832E84/ROSA-2014.1/4.1.15-NRJ-DESKTOP-1ROSA-I586/I686/1F35F79302>) |

### Flash memory (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1a78:0040 | 1a78:0040 | Virident Systems | FlashMAX II                          | 1     |            | [AEB295F54A](<Server/Intel/S5520/S5520HC/8C327755D17C/UBUNTU-20.04/5.4.0-167-GENERIC/X86_64/AEB295F54A>) |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:14a6 | 1022:14a6 | AMD              | Genoa/Bergamo RCEC                   | 17    | pcieport   | [E3AF2BABD8](<Server/Dell/PowerEdge/PowerEdge R6625/674A81CD0424/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/E3AF2BABD8>) |
| 8086:0b23 | 8086:0000 | Intel            | Xeon Root Event Collector            | 16    | pcieport   | [1524F37BBF](<Server/Dell/PowerEdge/PowerEdge R660xs/46E84777EA42/CENTOS-7/3.10.0-1160.119.1.EL7.X86_64/X86_64/1524F37BBF>) |
| 1002:5a23 | 1002:5a23 | AMD              | RD890S/RD990 I/O Memory Managemen... | 11    |            | [C425CE191D](<Server/Rackable Systems/KAURI/KAURI/35311A1382DF/LINUXMINT-20/5.4.0-113-GENERIC/X86_64/C425CE191D>) |
| 8086:0b23 | 8086:7270 | Intel            | Xeon Root Event Collector            | 8     | pcieport   | [F71EAE46A6](<Server/Intel/BIRCHSTREAM/BIRCHSTREAM/1F03C9158405/XUBUNTU-24.04/6.8.0-48-GENERIC/X86_64/F71EAE46A6>) |
| 1022:1577 | 1022:1577 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 6     |            | [F83E3EE442](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/00F75AC4089A/FEDORA-40/6.10.10-200.FC40.X86_64/X86_64/F83E3EE442>) |
| 1022:1451 | 1022:1451 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 5     |            | [D314F4B7CF](<Server/Supermicro/Super/Super Server/ECB64B8152DF/DEBIAN-12/6.8.12-1-PVE/X86_64/D314F4B7CF>) |
| 8086:19a2 | 15d9:0969 | Intel            | Atom Processor C3000 Series Root ... | 4     | pcieport   | [CDCA826585](<Server/Supermicro/Super/Super Server/67F50154C8D4/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/CDCA826585>) |
| 8086:0b23 | 15d9:1c51 | Intel            | Xeon Root Event Collector            | 3     | pcieport   | [96962C9FAC](<Server/Supermicro/SYS-511/SYS-511E-WR/4D3CCDFB3187/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/96962C9FAC>) |
| 8086:0b23 | 15d9:1c82 | Intel            | Xeon Root Event Collector            | 2     | pcieport   | [ADC9050B3F](<Server/Supermicro/Super/Super Server/A5DA019EA0BE/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/ADC9050B3F>) |
| 8086:0b23 | 1028:0a6b | Intel            | Xeon Root Event Collector            | 1     | pcieport   | [8826988040](<Server/Others/0024FG/0024FG A01/FF97E492C16F/DEBIAN-12/6.8.8-2-PVE/X86_64/8826988040>) |
| 8086:0b23 | 1028:0aaa | Intel            | Xeon Root Event Collector            | 1     | pcieport   | [45477E743D](<Server/Dell/Precision/Precision 7960 Rack/A4F90226C97E/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/45477E743D>) |
| 8086:0b23 | 1028:0b9d | Intel            | Xeon Root Event Collector            | 1     |            | [1524F37BBF](<Server/Dell/PowerEdge/PowerEdge R660xs/46E84777EA42/CENTOS-7/3.10.0-1160.119.1.EL7.X86_64/X86_64/1524F37BBF>) |
| 8086:0b23 | 15d9:1c87 | Intel            | Xeon Root Event Collector            | 1     | pcieport   | [7A000004A8](<Server/Supermicro/SYS-751/SYS-751A-I/A896A4C21B30/UBUNTU-22.04/6.5.0-35-GENERIC/X86_64/7A000004A8>) |
| 8086:0b23 | 17aa:104e | Intel            | Xeon Root Event Collector            | 1     | pcieport   | [791DC0869D](<Server/Lenovo/ThinkStation/ThinkStation PX 30EUA0EG00/8A299C9A2065/DEBIAN-12/6.10.11+BPO-AMD64/X86_64/791DC0869D>) |
| 8086:0b23 | 17aa:7830 | Intel            | Xeon Root Event Collector            | 1     | pcieport   | [80A2F3D367](<Server/Lenovo/ThinkSystem/ThinkSystem SR950 V3/80C0A7FFD0E3/RHEL-9/5.14.0-70.22.1.EL9_0.X86_64/X86_64/80A2F3D367>) |
| 8086:0b23 | 8086:09a2 | Intel            | Xeon Root Event Collector            | 1     | pcieport   | [F71EAE46A6](<Server/Intel/BIRCHSTREAM/BIRCHSTREAM/1F03C9158405/XUBUNTU-24.04/6.8.0-48-GENERIC/X86_64/F71EAE46A6>) |
| 8086:19a2 | 15d9:0982 | Intel            | Atom Processor C3000 Series Root ... | 1     | pcieport   | [D809C4B99D](<Server/Supermicro/Super/Super Server/5282A3BE97F8/UBUNTU-22.04/6.5.0-18-GENERIC/X86_64/D809C4B99D>) |
| 8086:19a2 | 15d9:1b10 | Intel            | Atom Processor C3000 Series Root ... | 1     |            | [F96B0CFDA0](<Server/Supermicro/Super/Super Server/9AA985C08DF3/GENTOO-2.7/5.10.76-GENTOO-R1/X86_64/F96B0CFDA0>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 102b:0533 | 103c:3381 | Matrox Electr... | MGA G200EH                           | 204   | mgag200    | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 1a03:2000 | 1a03:2000 | ASPEED Techno... | ASPEED Graphics Family               | 188   | ast        | [122B21A8E4](<Server/Others/Others/Others/DB0155950DC6/DEBIAN-12/6.8.12-5-PVE/X86_64/122B21A8E4>) |
| 1002:515e | 103c:31fb | AMD              | ES1000                               | 81    | radeon     | [B076CBF109](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/416C8912B3CC/DEBIAN/6.11.10-AMD64/X86_64/B076CBF109>) |
| 102b:0522 | 8086:0103 | Matrox Electr... | MGA G200e [Pilot] ServerEngines (... | 54    | mgag200    | [172A6309DF](<Server/Tarox/ParX/ParX T100c G6 Server/24E1CEA11A00/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/172A6309DF>) |
| 102b:0532 | 15d9:0600 | Matrox Electr... | MGA G200eW WPCM450                   | 46    | mgag200    | [6918605D42](<Server/Supermicro/X8/X8DTU/2EC017791B11/DEBIAN-12/6.8.12-5-PVE/X86_64/6918605D42>) |
| 102b:0536 |           | Matrox Electr... | Integrated Matrox G200eW3 Graphic... | 46    | mgag200    | [E80578896E](<Server/Dell/PowerEdge/PowerEdge R240/83EA7CA85F81/RED-OS-8.0/6.6.26-1.RED80.X86_64/X86_64/E80578896E>) |
| 1a03:2000 | 1458:1000 | ASPEED Techno... | ASPEED Graphics Family               | 45    | ast        | [DF0B00ACCC](<Server/Gigabyte Technology/MX33/MX33-BS1-V1/1BBDCF35885F/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/DF0B00ACCC>) |
| 102b:0534 | 15d9:0636 | Matrox Electr... | G200eR2                              | 39    | mgag200    | [86B4E152AD](<Server/Supermicro/X9/X9DRW/D2C6B0237967/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/86B4E152AD>) |
| 102b:0534 | 1028:048c | Matrox Electr... | G200eR2                              | 35    | mgag200    | [D63ADBC5DD](<Server/Dell/PowerEdge/PowerEdge R720/13A7060552FC/NIXOS-25.05/6.6.63/X86_64/D63ADBC5DD>) |
| 1a03:2000 | 1849:2000 | ASPEED Techno... | ASPEED Graphics Family               | 33    | ast        | [EE0C91380E](<Server/ASRockRack/B650/B650D4U-2L2T-BCM/4E50B00275AF/ALMA-8.10/4.18.0-553.33.1.EL8_10.X86_64/X86_64/EE0C91380E>) |
| 102b:0522 | 19a2:0101 | Matrox Electr... | MGA G200e [Pilot] ServerEngines (... | 32    | mgag200    | [ECD5A5BE36](<Server/Lenovo/ThinkSystem/ThinkSystem ST650 V2/038AE9A4AA3B/XUBUNTU-22.04/5.15.0-94-GENERIC/X86_64/ECD5A5BE36>) |
| 102b:0532 | 1028:0235 | Matrox Electr... | MGA G200eW WPCM450                   | 31    | mgag200    | [E9F4F40104](<Server/Dell/PowerEdge/PowerEdge R710/4BAAF0C6A4BB/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/E9F4F40104>) |
| 19e5:1711 |           | Huawei Techno... | Hi171x Series [iBMC Intelligent M... | 29    | hibmc_drm  | [29BDE967FC](<Server/HUAWEI/TaiShan/TaiShan 2280 V2/2603C7B2E57E/UBUNTU-22.04/5.15.0-88-GENERIC/AARCH64/29BDE967FC>) |
| 1a03:2000 | 15d9:0967 | ASPEED Techno... | ASPEED Graphics Family               | 27    | ast        | [01602FD84E](<Server/Supermicro/SYS-6019/SYS-6019P-WTR/0C2A376E8BE8/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/01602FD84E>) |
| 102b:0538 | 1590:00e4 | Matrox Electr... | MGA G200eH3                          | 26    | mgag200    | [D9F97B2071](<Server/HPE/ProLiant/ProLiant DL380 Gen10/6D60567E7E8D/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/D9F97B2071>) |
| 102b:0522 | 8086:0101 | Matrox Electr... | MGA G200e [Pilot] ServerEngines (... | 25    | mgag200    | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 1a03:2000 | 152d:899b | ASPEED Techno... | ASPEED Graphics Family               | 25    | ast        | [7E09CCDA22](<Server/ETegro Technologies/Hyperion/Hyperion RS125 G4/5259A72AB62F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/7E09CCDA22>) |
| 102b:0532 | 1028:02f1 | Matrox Electr... | MGA G200eW WPCM450                   | 24    | mgag200    | [0D6D6A6743](<Server/Dell/PowerEdge/PowerEdge R510/7E56EFD8FB93/DEBIAN-12/6.8.8-2-PVE/X86_64/0D6D6A6743>) |
| 102b:0534 | 1028:0601 | Matrox Electr... | G200eR2                              | 24    | mgag200    | [44126F8D86](<Server/Dell/PowerEdge/PowerEdge R630/23D674735CB9/GENTOO-2.15/6.6.38-GENTOO-MANS/X86_64/44126F8D86>) |
| 102b:0530 | 1014:0369 | Matrox Electr... | MGA G200EV                           | 23    | mgag200    | [133F7BC9A5](<Server/IBM/System/System x3250 M3 -[4252K4G]-/76E08604766E/DEBIAN-11/6.2.16-20-BPO11-PVE/X86_64/133F7BC9A5>) |
| 102b:0532 | 1028:0236 | Matrox Electr... | MGA G200eW WPCM450                   | 23    | mgag200    | [A2B12B6DA3](<Server/Dell/PowerEdge/PowerEdge R610/14D2A48FEC25/CENTOS-7/3.10.0-1160.11.1.EL7.X86_64/X86_64/A2B12B6DA3>) |
| 102b:0534 | 1014:0405 | Matrox Electr... | G200eR2                              | 20    | mgag200    | [C15B3DE94E](<Server/IBM/System/System X3250 M4 -[2583AC1]-/B87E2E266E18/LINUXMINT-21.2/5.15.0-106-GENERIC/X86_64/C15B3DE94E>) |
| 102b:0534 | 1028:0627 | Matrox Electr... | G200eR2                              | 20    | mgag200    | [72A4F63713](<Server/Dell/PowerEdge/PowerEdge R730XD/1A3F6F422946/DEBIAN-12/6.8.12-4-PVE/X86_64/72A4F63713>) |
| 1a03:2000 | 15d9:0821 | ASPEED Techno... | ASPEED Graphics Family               | 20    | ast        | [98EF58F80D](<Server/Supermicro/SYS-6018/SYS-6018R-WTR/4A5A129EA8CA/CENTOS-7/3.10.0-1160.83.1.EL7.X86_64/X86_64/98EF58F80D>) |
| 102b:0534 | 1028:04ce | Matrox Electr... | G200eR2                              | 19    | mgag200    | [33A45E355F](<Server/Dell/PowerEdge/PowerEdge R620/C7F9C68EF445/CENTOS-6/2.6.32-754.33.1.EL6.X86_64/X86_64/33A45E355F>) |
| 102b:0536 | 1028:0715 | Matrox Electr... | Integrated Matrox G200eW3 Graphic... | 19    | mgag200    | [2EA3B6BA11](<Server/Dell/PowerEdge/PowerEdge R740/102E11A0DB9A/DEBIAN-12/6.8.4-2-PVE/X86_64/2EA3B6BA11>) |
| 102b:0532 | 15d9:0006 | Matrox Electr... | MGA G200eW WPCM450                   | 18    | mgag200    | [337DC9A775](<Server/Supermicro/X8/X8DTL/0C862FB30BE8/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/337DC9A775>) |
| 1a03:2000 | 1043:84eb | ASPEED Techno... | ASPEED Graphics Family               | 18    | ast        | [E805BE0AAC](<Server/Kraftway/GEG/GEG/C4E325834440/DEBIAN-12/6.1.0-27-AMD64/X86_64/E805BE0AAC>) |
| 1a03:2000 | 15d9:0728 | ASPEED Techno... | ASPEED Graphics Family               | 17    | ast        | [76C41C5097](<Server/Supermicro/X10/X10DRi/B47EB5B551E7/DEBIAN-12/6.1.0-26-AMD64/X86_64/76C41C5097>) |
| 102b:0522 | 1734:11cc | Matrox Electr... | MGA G200e [Pilot] ServerEngines (... | 16    | mgag200    | [ED6A47B6F9](<Server/Fujitsu/PRIMERGY/PRIMERGY TX2540 M1/6D63F93EE5A2/DEBIAN-12/6.11.10+BPO-AMD64/X86_64/ED6A47B6F9>) |
| 102b:0532 | 1028:028c | Matrox Electr... | MGA G200eW WPCM450                   | 16    | mgag200    | [B6E4EA8841](<Server/Dell/PowerEdge/PowerEdge R410/904CC8DF7D0A/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/B6E4EA8841>) |
| 102b:0532 | 1028:04de | Matrox Electr... | MGA G200eW WPCM450                   | 16    | mgag200    | [1E51138D9B](<Server/Dell/PowerEdge/PowerEdge T110 II/A23024949A59/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/1E51138D9B>) |
| 102b:0534 | 1028:04fa | Matrox Electr... | G200eR2                              | 16    | mgag200    | [B416E87C4A](<Server/Dell/PowerEdge/PowerEdge T320/7C98CB79C6C7/OPENMANDRIVA-24.09/6.11.0-DESKTOP-2OMV2490/X86_64/B416E87C4A>) |
| 102b:0534 | 1028:0600 | Matrox Electr... | G200eR2                              | 16    | mgag200    | [888A235104](<Server/Dell/PowerEdge/PowerEdge R730/B44B0E51BDB3/DEBIAN-12/6.8.12-4-PVE/X86_64/888A235104>) |
| 1a03:2000 | 1043:86ed | ASPEED Techno... | ASPEED Graphics Family               | 16    | ast        | [664827DD6C](<Server/ASUSTek Computer/Pro/Pro WS C621-64L SAGE-10G Series/A1C444FAB774/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/664827DD6C>) |
| 1002:164e | 1002:164e | AMD              | Raphael                              | 15    | amdgpu     | [EE0C91380E](<Server/ASRockRack/B650/B650D4U-2L2T-BCM/4E50B00275AF/ALMA-8.10/4.18.0-553.33.1.EL8_10.X86_64/X86_64/EE0C91380E>) |
| 10de:1eba | 10de:0000 | Nvidia           | TU104GL [PG189 SKU600]               | 15    | nvidia     | [4391DFF8D2](<Server/Others/Others/Others/29E67FFE5E37/UBUNTU-18.04/4.18.0-20-GENERIC/X86_64/4391DFF8D2>) |
| 1002:9874 | 1002:1871 | AMD              | Wani [Radeon R5/R6/R7 Graphics]      | 14    | amdgpu     | [F83E3EE442](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/00F75AC4089A/FEDORA-40/6.10.10-200.FC40.X86_64/X86_64/F83E3EE442>) |
| 102b:0532 | 15d9:0007 | Matrox Electr... | MGA G200eW WPCM450                   | 14    | mgag200    | [8C5797ED25](<Server/Supermicro/X8/X8DTT/714C700A2F5C/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/8C5797ED25>) |
| 1a03:2000 | 15d9:0831 | ASPEED Techno... | ASPEED Graphics Family               | 14    | ast        | [2BAD48B8D4](<Server/Silicon Mechanics/Rackform/Rackform R309.v5/8442C8D36737/DEBIAN-12/6.1.0-21-AMD64/X86_64/2BAD48B8D4>) |
| 102b:0532 | 1028:04dd | Matrox Electr... | MGA G200eW WPCM450                   | 13    | mgag200    | [969B046986](<Server/Dell/PowerEdge/PowerEdge R210 II/93E843E2F825/UBUNTU-22.04/5.15.0-124-GENERIC/X86_64/969B046986>) |
| 1a03:2000 | 15d9:089a | ASPEED Techno... | ASPEED Graphics Family               | 13    | ast        | [85E2DD189C](<Server/Supermicro/Super/Super Server/2FA87A9B8E2E/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/85E2DD189C>) |
| 1a03:2000 | 15d9:1a03 | ASPEED Techno... | ASPEED Graphics Family               | 13    | ast        | [3B1B28CFC7](<Server/Supermicro/Super/Super Server/CD7B912FA9C9/ROSA-12.5.1/6.6.27-GENERIC-3ROSA2021.1-X86_64/X86_64/3B1B28CFC7>) |
| 1a03:2000 | 15d9:1b2b | ASPEED Techno... | ASPEED Graphics Family               | 13    | ast        | [4235F71014](<Server/Supermicro/AS/AS -1014S-WTRT/4126E18782A7/CYBER-INFRASTRUCTURE-6.5.0/3.10.0-1160.114.2.AIP7.222.1/X86_64/4235F71014>) |
| 102b:0522 | 1734:108e | Matrox Electr... | MGA G200e [Pilot] ServerEngines (... | 12    | mgag200    | [486301061F](<Server/Fujitsu/PRIMERGY/PRIMERGY TX150 S7/3406DF3EF425/ARCH-ROLLING/6.12.7-ARCH1-1/X86_64/486301061F>) |
| 102b:0532 | 1028:02a4 | Matrox Electr... | MGA G200eW WPCM450                   | 12    | mgag200    | [48E00D403A](<Server/Dell/PowerEdge/PowerEdge T310/0EAF01173A25/DEBIAN-12/6.6.32-PRODUCTION+TRUENAS/X86_64/48E00D403A>) |
| 102b:0532 | 15d9:0626 | Matrox Electr... | MGA G200eW WPCM450                   | 12    | mgag200    | [39232DFDE3](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/B0C1ED30C610/DEBIAN-12/6.1.0-25-AMD64/X86_64/39232DFDE3>) |
| 1a03:2000 | 15d9:086d | ASPEED Techno... | ASPEED Graphics Family               | 12    | ast        | [3E9BE7A949](<Server/Supermicro/Super/Super Server/CE1321EEE3B9/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/3E9BE7A949>) |
| 1002:515e | 1028:01b2 | AMD              | ES1000                               | 11    | radeon     | [5DE4C4A538](<Server/Dell/PowerEdge/PowerEdge 2950/A7ED8CBDCF7D/LMDE-6/6.1.0-28-AMD64/X86_64/5DE4C4A538>) |
| 1a03:2000 | 15d9:0844 | ASPEED Techno... | ASPEED Graphics Family               | 11    |            | [D24D2612FE](<Server/Supermicro/Super/Super Server/F4A31F1B8877/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/D24D2612FE>) |

### Input device controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1102:7003 | 1102:0040 | Creative Labs    | SB Audigy Game Port                  | 4     | emu10k1_gp | [A41CABB3D6](<Server/Dell/PowerEdge/PowerEdge SC1430/2088C31572DB/DEBIAN-11/5.10.0-19-AMD64/X86_64/A41CABB3D6>) |
| 1102:7002 | 1102:0020 | Creative Labs    | SB Live! Game Port                   | 2     | emu10k1_gp | [A8B96E89F2](<Server/TYAN Computer/S/S7010/0C071F7B6B6A/XUBUNTU-20.04/5.15.0-73-GENERIC/X86_64/A8B96E89F2>) |
| 1102:7003 | 1102:0060 | Creative Labs    | SB Audigy Game Port                  | 2     | emu10k1_gp | [2D3C35E364](<Server/Fujitsu/PRIMERGY/PRIMERGY TX2540 M1/25DC1F84A0CF/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/2D3C35E364>) |

### Iommu (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1481 | 1022:1481 | AMD              | Starship/Matisse IOMMU               | 53    |            | [726B65D6E8](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.10/4.18.0-553.27.1.EL8_10.X86_64/X86_64/726B65D6E8>) |
| 1022:164f | 1022:164f | AMD              | Milan IOMMU                          | 19    |            | [08FE32BEB9](<Server/ASRockRack/ROMED8/ROMED8-2T-OVHA/6C847AA5821C/UBUNTU-22.04/5.15.0-73-GENERIC/X86_64/08FE32BEB9>) |
| 1022:14d9 | 1022:14d9 | AMD              | Raphael/Granite Ridge IOMMU          | 11    |            | [F4A02ED514](<Server/MSI/MSIS/MSIS366/66AA7EB4825A/UBUNTU-20.04/5.15.0-124-GENERIC/X86_64/F4A02ED514>) |
| 1022:14d9 | 1849:14d9 | AMD              | Raphael/Granite Ridge IOMMU          | 11    |            | [EE0C91380E](<Server/ASRockRack/B650/B650D4U-2L2T-BCM/4E50B00275AF/ALMA-8.10/4.18.0-553.33.1.EL8_10.X86_64/X86_64/EE0C91380E>) |
| 1022:1481 | 1028:08fc | AMD              | Starship/Matisse IOMMU               | 8     |            | [CE34F45F28](<Server/AWS Elemental/Appliance/Appliance/78AD1C73F775/UBUNTU-22.04/6.5.0-27-GENERIC/X86_64/CE34F45F28>) |
| 1022:1631 | 1022:1631 | AMD              | Renoir/Cezanne IOMMU                 | 8     |            | [650A06CBD5](<Server/ASRockRack/X570/X570D4U/BD8DD3707384/NIXOS-24.11/6.6.63/X86_64/650A06CBD5>) |
| 1002:5a23 | 1028:0444 | AMD              | RD890S/RD990 I/O Memory Managemen... | 7     |            | [2D3D5673E7](<Server/Dell/PowerEdge/PowerEdge R815/6B72BADC37CC/UBUNTU-22.04/5.15.0-119-GENERIC/X86_64/2D3D5673E7>) |
| 1022:1481 | 1458:1000 | AMD              | Starship/Matisse IOMMU               | 6     |            | [DEF4067C8E](<Server/Gigabyte Technology/G242/G242-Z11-00/B5251D581093/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/DEF4067C8E>) |
| 1022:149e | 1022:149e | AMD              | Genoa/Bergamo IOMMU                  | 6     |            | [5FB0C3A747](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2450 M2/6F7BBA6E51B5/GENTOO-2.15/6.6.30-1-LTS/X86_64/5FB0C3A747>) |
| 1022:1481 | 1028:08ff | AMD              | Starship/Matisse IOMMU               | 5     |            | [77F946C99B](<Server/Dell/PowerEdge/PowerEdge R7525/ED52A1D54F9D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/77F946C99B>) |
| 1022:149e | 1028:0af9 | AMD              | Genoa/Bergamo IOMMU                  | 5     |            | [F73AE91625](<Server/Dell/PowerEdge/PowerEdge R7625/85D8E20875A1/UBUNTU-20.04/5.4.0-156-GENERIC/X86_64/F73AE91625>) |
| 1022:164f | 1458:1000 | AMD              | Milan IOMMU                          | 5     |            | [57A7F1D729](<Server/Gigabyte Technology/R262/R262-ZA2-00/CDDBD3B5CB39/DEBIAN-12/6.2.16-3-PVE/X86_64/57A7F1D729>) |
| 1002:5a23 | 103c:1762 | AMD              | RD890S/RD990 I/O Memory Managemen... | 3     |            | [5BB6B014BF](<Server/Hewlett-Packard/ProLiant/ProLiant DL385p Gen8/2A0018D2AAFA/DEBIAN-12/6.5.13-1-PVE/X86_64/5BB6B014BF>) |
| 1022:1481 | 1028:08fd | AMD              | Starship/Matisse IOMMU               | 3     |            | [F0B9CD86EF](<Server/Dell/PowerEdge/PowerEdge R7515/723F15A8AB49/UBUNTU-22.04/5.15.0-47-GENERIC/X86_64/F0B9CD86EF>) |
| 1022:149e | 1849:149e | AMD              | Genoa/Bergamo IOMMU                  | 3     |            | [70D3A74444](<Server/ASRockRack/GENOAD12/GENOAD12M3-2Q-H/AF39B86BBAAF/UBUNTU-24.04/6.8.0-38-GENERIC/X86_64/70D3A74444>) |
| 1022:164f | 1028:08fc | AMD              | Milan IOMMU                          | 3     |            | [D56CA4A374](<Server/Dell/PowerEdge/PowerEdge R6515/C4B03BD3B174/UBUNTU-22.04/5.15.0-41-GENERIC/X86_64/D56CA4A374>) |
| 1022:1451 | 1028:07f9 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 2     |            | [FD88331144](<Server/Dell/PowerEdge/PowerEdge R7425/1C2794FDE243/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/FD88331144>) |
| 1022:149e | 1028:0af6 | AMD              | Genoa/Bergamo IOMMU                  | 2     |            | [2DF42D8015](<Server/Dell/PowerEdge/PowerEdge R6615/A3D1D83B109B/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/2DF42D8015>) |
| 1022:1631 | 1458:1000 | AMD              | Renoir/Cezanne IOMMU                 | 2     |            | [722F640CCD](<Server/Gigabyte Technology/MC12/MC12-LE0-00/37078BD0F3C1/UBUNTU-22.04/6.5.0-18-GENERIC/X86_64/722F640CCD>) |
| 8086:1f16 | 15d9:0820 | Intel            | Atom processor C2000 RCEC            | 2     |            | [A9E1A5906C](<Server/Supermicro/A1/A1SAM-2550F/B9FD41A2E4E7/MANJARO-21.2.3/5.15.21-1-MANJARO/X86_64/A9E1A5906C>) |
| 1002:5a23 | 1028:0445 | AMD              | RD890S/RD990 I/O Memory Managemen... | 1     |            | [0E5CEE5637](<Server/Dell/PowerEdge/PowerEdge R715/E2B668AC841B/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/0E5CEE5637>) |
| 1002:5a23 | 103c:3324 | AMD              | RD890S/RD990 I/O Memory Managemen... | 1     |            | [7CE46A749E](<Server/Hewlett-Packard/ProLiant/ProLiant DL165 G7/1273A822F849/UBUNTU-19.04/5.0.0-20-LOWLATENCY/X86_64/7CE46A749E>) |
| 1022:149e | 1028:0af8 | AMD              | Genoa/Bergamo IOMMU                  | 1     |            | [E3AF2BABD8](<Server/Dell/PowerEdge/PowerEdge R6625/674A81CD0424/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/E3AF2BABD8>) |
| 1022:14d9 | 15d9:1c97 | AMD              | Raphael/Granite Ridge IOMMU          | 1     |            | [CAB997495E](<Server/Supermicro/Super/Super Server/9ABB78B85737/DEBIAN-12/6.8.12-2-PVE/X86_64/CAB997495E>) |
| 1022:15d1 | 1022:15d1 | AMD              | Raven/Raven2 IOMMU                   | 1     |            | [A3BF3001FB](<Server/BESSTAR Tech/X/X300/E9F8161B7597/OPENMANDRIVA-23.11/6.6.2-DESKTOP-1OMV2390/X86_64/A3BF3001FB>) |
| 1022:164f | 1028:08fd | AMD              | Milan IOMMU                          | 1     |            | [28E8ABBBDF](<Server/Dell/PowerEdge/PowerEdge R7515/8E207635BBF5/NIXOS-23.11/6.5.12/X86_64/28E8ABBBDF>) |
| 1022:164f | 1028:08ff | AMD              | Milan IOMMU                          | 1     |            | [B7AC531BF5](<Server/Dell/PowerEdge/PowerEdge R7525/3F409CE3A366/RHEL-8///B7AC531BF5>) |
| 1022:164f | 1028:0900 | AMD              | Milan IOMMU                          | 1     |            | [382F999542](<Server/Dell/PowerEdge/PowerEdge C6525/B11FEC7694D8/ARCH/5.15.59-1-LTS/X86_64/382F999542>) |
| 8086:1f16 | 15d9:0828 | Intel            | Atom processor C2000 RCEC            | 1     |            | [E134D7A317](<Server/Supermicro/A1/A1SA2-2750F/64B5066C8E62/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E134D7A317>) |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 103c:3302 | 103c:3305 | Hewlett-Packard  | Integrated Lights-Out Standard KC... | 43    | ipmi_si    | [7EE3CAE73F](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/FB9F2505E84E/DEBIAN-12/6.1.0-22-AMD64/X86_64/7EE3CAE73F>) |

### Isdn adapter (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1244:0a00 | 1244:0a00 | AVM              | A1 ISDN [Fritz]                      | 1     | fcpci      | [750A124EF3](<Server/Wortmann AG/TERRA_PC/TERRA_PC/8340D78F7FD7/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/750A124EF3>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a1a1 | 8086:7270 | Intel            | C620 Series Chipset Family Power ... | 92    |            | [122B21A8E4](<Server/Others/Others/Others/DB0155950DC6/DEBIAN-12/6.8.12-5-PVE/X86_64/122B21A8E4>) |
| 8086:a1a1 | 1028:073a | Intel            | C620 Series Chipset Family Power ... | 29    |            | [B75294443B](<Server/Dell/Precision/Precision 7920 Tower/5E36FA18A2AE/KUBUNTU-20.04/5.15.0-84-GENERIC/X86_64/B75294443B>) |
| 8086:a36f | 8086:7270 | Intel            | Cannon Lake PCH Shared SRAM          | 29    |            | [AEF6DB08C4](<Server/Supermicro/Super/Super Server/BAD6EC448C66/UBUNTU-22.04/5.15.0-116-GENERIC/X86_64/AEF6DB08C4>) |
| 8086:a1a1 | 15d9:0967 | Intel            | C620 Series Chipset Family Power ... | 27    |            | [01602FD84E](<Server/Supermicro/SYS-6019/SYS-6019P-WTR/0C2A376E8BE8/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/01602FD84E>) |
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 25    |            | [172A6309DF](<Server/Tarox/ParX/ParX T100c G6 Server/24E1CEA11A00/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/172A6309DF>) |
| 8086:a1a1 | 1590:00eb | Intel            | C620 Series Chipset Family Power ... | 22    |            | [D9F97B2071](<Server/HPE/ProLiant/ProLiant DL380 Gen10/6D60567E7E8D/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/D9F97B2071>) |
| 8086:a1a1 | 8086:35ce | Intel            | C620 Series Chipset Family Power ... | 22    |            | [781F43495A](<Server/Intel/S2600/S2600WFT/B54D5A70237A/RED-OS-7.3.2/5.15.87-1.EL7.3.X86_64/X86_64/781F43495A>) |
| 8086:a1a1 | 1028:0715 | Intel            | C620 Series Chipset Family Power ... | 19    |            | [2EA3B6BA11](<Server/Dell/PowerEdge/PowerEdge R740/102E11A0DB9A/DEBIAN-12/6.8.4-2-PVE/X86_64/2EA3B6BA11>) |
| 8086:a1a1 | 1458:1000 | Intel            | C620 Series Chipset Family Power ... | 17    |            | [F76FC4031D](<Server/PSSC Labs/SS4000/SS4000HD/13084E646FAA/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/F76FC4031D>) |
| 8086:a1a1 | 1028:0739 | Intel            | C620 Series Chipset Family Power ... | 16    |            | [BA0626CE0A](<Server/Dell/Precision/Precision 7820 Tower/3792A2743A38/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/BA0626CE0A>) |
| 8086:a1a1 | 1043:871e | Intel            | C620 Series Chipset Family Power ... | 15    |            | [664827DD6C](<Server/ASUSTek Computer/Pro/Pro WS C621-64L SAGE-10G Series/A1C444FAB774/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/664827DD6C>) |
| 8086:51ef |           | Intel            | Alder Lake PCH Shared SRAM           | 14    |            | [DF42F11E59](<Server/GEEKOM/GT13/GT13 Pro/EF7C9F2D8B32/LINUXMINT-22/6.8.0-48-GENERIC/X86_64/DF42F11E59>) |
| 8086:a121 | 15d9:089a | Intel            | 100 Series/C230 Series Chipset Fa... | 13    |            | [85E2DD189C](<Server/Supermicro/Super/Super Server/2FA87A9B8E2E/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/85E2DD189C>) |
| 8086:a1a1 | 17aa:1038 | Intel            | C620 Series Chipset Family Power ... | 13    | vfio_pci   | [CAFAEE2FC7](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC000QGE/C9B0658BA91C/DEBIAN-12/6.1.0-28-AMD64/X86_64/CAFAEE2FC7>) |
| 8086:a1a1 | 1849:a1a1 | Intel            | C620 Series Chipset Family Power ... | 12    |            | [E9C9A4C51A](<Server/INFERIT/RS224/RS224 R1G3D32RU/68DD4BB73C8C/ROSA-12F.1/6.1.58-GENERIC-5ROSA2021.15-X86_64/X86_64/E9C9A4C51A>) |
| 1912:0011 |           | Renesas Techn... | SH7757 PCIe End-Point [PBI]          | 10    |            | [FAC7B88BA4](<Server/Dell/PowerEdge/PowerEdge R220/6C41BB312960/UBUNTU-22.04/5.15.0-92-GENERIC/X86_64/FAC7B88BA4>) |
| 8086:a1a1 | 15d9:096d | Intel            | C620 Series Chipset Family Power ... | 10    |            | [80DB5BCB0E](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/F054CE6D6C8F/UBUNTU-22.04/6.2.0-33-GENERIC/X86_64/80DB5BCB0E>) |
| 8086:a36f |           | Intel            | Cannon Lake PCH Shared SRAM          | 10    |            | [E80578896E](<Server/Dell/PowerEdge/PowerEdge R240/83EA7CA85F81/RED-OS-8.0/6.6.26-1.RED80.X86_64/X86_64/E80578896E>) |
| 1590:005f | 1590:005f | Hewlett-Packard  | Memory controller                    | 9     |            | [735D113F73](<Server/Hewlett-Packard/ProLiant/ProLiant DL380e Gen8/4865ACA2339D/CLEAR-LINUX-OS-42390/6.10.10-1463.NATIVE/X86_64/735D113F73>) |
| 8086:a1a1 | 15d9:095d | Intel            | C620 Series Chipset Family Power ... | 9     |            | [A121B2A2E1](<Server/Supermicro/Super/Super Server/751AC2BC6C6F/CYBER-INFRASTRUCTURE-6.0.2/3.10.0-1160.105.1.AIP7.214.3/X86_64/A121B2A2E1>) |
| 8086:a1a1 | 17aa:7808 | Intel            | C620 Series Chipset Family Power ... | 9     |            | [424E70419E](<Server/Lenovo/ThinkSystem/ThinkSystem SR570 -[7Y03CTO1WW]-/D3469A41F07A/XUBUNTU-18.04/4.15.0-213-GENERIC/X86_64/424E70419E>) |
| 8086:a1a1 | 1028:0716 | Intel            | C620 Series Chipset Family Power ... | 8     |            | [B89424543D](<Server/Dell/PowerEdge/PowerEdge R640/88100BFA40CD/DEBIAN-12/6.1.0-13-AMD64/X86_64/B89424543D>) |
| 8086:a1a1 | 103c:81c6 | Intel            | C620 Series Chipset Family Power ... | 8     |            | [21781753FB](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/4E03B443521E/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/21781753FB>) |
| 8086:a1a1 | 15d9:0981 | Intel            | C620 Series Chipset Family Power ... | 8     |            | [6CA957B8C9](<Server/Supermicro/SSG-6049/SSG-6049P-E1CR36L/A0CFEEE452D8/DEBIAN/6.6.15-AMD64/X86_64/6CA957B8C9>) |
| 8086:a1a1 | 17aa:1037 | Intel            | C620 Series Chipset Family Power ... | 8     |            | [301BFF683B](<Server/Lenovo/ThinkStation/ThinkStation P720 30BBS3H50D/215583F782C1/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.10.4-1-DEFAULT/X86_64/301BFF683B>) |
| 8086:a36f | 8086:a36f | Intel            | Cannon Lake PCH Shared SRAM          | 8     |            | [196C8EB317](<Server/Neousys Technology/Nuvo-7100VTC/Nuvo-7100VTC Series/E44E3E216941/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/196C8EB317>) |
| 8086:1bce | 8086:7270 | Intel            | C741 Series PMC Shared               | 7     |            | [A2CE10373E](<Server/Graviton/S2122/S2122IU/ED2248ACB950/ROSA-12/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/A2CE10373E>) |
| 8086:a121 | 1028:06a5 | Intel            | 100 Series/C230 Series Chipset Fa... | 7     |            | [097C771B65](<Server/Dell/PowerEdge/PowerEdge R230/1EDFED183BEA/DEBIAN-11/5.10.0-19-AMD64/X86_64/097C771B65>) |
| 8086:a121 | 15d9:0895 | Intel            | 100 Series/C230 Series Chipset Fa... | 7     |            | [23F3141732](<Server/Supermicro/Super/Super Server/C06149C5792E/UBUNTU-24.04/6.8.0-36-GENERIC/X86_64/23F3141732>) |
| 8086:a1a1 | 1028:07c9 | Intel            | C620 Series Chipset Family Power ... | 7     |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:a1a1 | 103c:81c7 | Intel            | C620 Series Chipset Family Power ... | 7     |            | [03E2A5BAC1](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/5E9B675190B8/UBUNTU-22.04/6.2.0-37-GENERIC/X86_64/03E2A5BAC1>) |
| 8086:a1a1 | 15d9:091c | Intel            | C620 Series Chipset Family Power ... | 7     |            | [0B1FEB460C](<Server/Supermicro/SYS-6019/SYS-6019U-TN4R4T/51D2EF357A4F/ROCKY-9.2/5.14.0-284.18.1.EL9_2.X86_64/X86_64/0B1FEB460C>) |
| 8086:4def |           | Intel            | Jasper Lake Shared SRAM              | 6     |            | [6B8F982987](<Server/GEEKOM/MiniAir/MiniAir 11/5E7475318C5E/UBUNTU-24.04/6.8.0-35-GENERIC/X86_64/6B8F982987>) |
| 8086:7aa7 |           | Intel            | Alder Lake-S PCH Shared SRAM         | 6     |            | [9CAFDCB628](<Server/ASRockRack/W680/W680D4U-1L/78FE6457B62F/UBUNTU-24.04/6.8.0-50-GENERIC/X86_64/9CAFDCB628>) |
| 8086:a121 | 1028:06aa | Intel            | 100 Series/C230 Series Chipset Fa... | 6     |            | [AA643EDF66](<Server/Dell/PowerEdge/PowerEdge T130/32614BB1FD9D/LINUXMINT-21.2/6.2.0-26-GENERIC/X86_64/AA643EDF66>) |
| 8086:a121 | 15d9:0884 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     |            | [0840C7521E](<Server/OEM/PR2285/PR2285S1/E9EE5DAF6D75/DEBIAN-12/6.6.38-TRIM/X86_64/0840C7521E>) |
| 8086:a121 | 15d9:088b | Intel            | 100 Series/C230 Series Chipset Fa... | 6     |            | [1CECE2A441](<Server/Supermicro/C7/C7H170-M/40203ADD6246/FEDORA-40/6.10.12-200.FC40.X86_64/X86_64/1CECE2A441>) |
| 8086:a1a1 | 1028:0718 | Intel            | C620 Series Chipset Family Power ... | 6     |            | [A4F3535E84](<Server/Dell/Precision/Precision 7920 Rack/1D56B1A533A9/UBUNTU-20.04/5.14.0-1057-OEM/X86_64/A4F3535E84>) |
| 8086:a1a1 | 17aa:7800 | Intel            | C620 Series Chipset Family Power ... | 6     |            | [47FE0DACDD](<Server/Lenovo/ThinkSystem/ThinkSystem SR630 -[7X02CTO1WW]/74C1AF03C5E9/LINUXMINT-20.3/5.4.0-144-GENERIC/X86_64/47FE0DACDD>) |
| 8086:a1a1 | 17aa:7801 | Intel            | C620 Series Chipset Family Power ... | 6     |            | [BAFB634A37](<Server/Lenovo/ThinkSystem/ThinkSystem SR530 -[7X08CTO1WW]-/16717DADAA79/CENTOS-7/3.10.0-1160.36.2.EL7.X86_64/X86_64/BAFB634A37>) |
| 8086:a121 | 1028:06a7 | Intel            | 100 Series/C230 Series Chipset Fa... | 5     |            | [F9C38114CE](<Server/Dell/PowerEdge/PowerEdge T330/FE5D632CB860/DEBIAN-12/6.8.4-2-PVE/X86_64/F9C38114CE>) |
| 8086:a1a1 | 1028:0737 | Intel            | C620 Series Chipset Family Power ... | 5     |            | [D288D87AB5](<Server/Dell/PowerEdge/PowerEdge R740xd/BB55A2E30656/ALMA-8.7/4.18.0-425.19.2.EL8_7.X86_64/X86_64/D288D87AB5>) |
| 8086:a1a1 | 1028:07cb | Intel            | C620 Series Chipset Family Power ... | 5     |            | [C59E7B7F26](<Server/Dell/PowerEdge/PowerEdge T440/D6901D17FD14/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.3.7-1-DEFAULT/X86_64/C59E7B7F26>) |
| 8086:a1a1 | 1028:07e5 | Intel            | C620 Series Chipset Family Power ... | 5     |            | [26C6662D67](<Server/Dell/PowerEdge/PowerEdge T640/2781755B8077/FEDORA-39/6.7.7-200.FC39.X86_64/X86_64/26C6662D67>) |
| 8086:a2a1 | 15d9:098e | Intel            | 200 Series/Z370 Chipset Family Po... | 5     |            | [2887A82948](<Server/Supermicro/Super/Super Server/4CD262ADBF12/DEBIAN-11/5.19.11/X86_64/2887A82948>) |
| 10de:0369 | 1462:cb84 | Nvidia           | MCP55 Memory Controller              | 4     |            | [1888FA6DF7](<Server/MSI/MCP/MCP55/E26C4EDDD3C1/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/1888FA6DF7>) |
| 8086:19de | 15d9:0969 | Intel            | Atom Processor C3000 Series Power... | 4     |            | [CDCA826585](<Server/Supermicro/Super/Super Server/67F50154C8D4/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/CDCA826585>) |
| 8086:43ef | 1458:1000 | Intel            | Tiger Lake-H Shared SRAM             | 4     |            | [DF0B00ACCC](<Server/Gigabyte Technology/MX33/MX33-BS1-V1/1BBDCF35885F/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/DF0B00ACCC>) |
| 8086:43ef | 1849:43ef | Intel            | Tiger Lake-H Shared SRAM             | 4     |            | [125542F615](<Server/ASRockRack/E3/E3C252D4U-2T-OVH/FD8B71F461B7/UBUNTU-22.04/5.15.0-83-GENERIC/X86_64/125542F615>) |
| 8086:a1a1 | 15d9:0953 | Intel            | C620 Series Chipset Family Power ... | 4     |            | [A76BB2E30D](<Server/Supermicro/SYS-5029/SYS-5029P-WTR/2D889DFAC2FF/ROCKY-8.5/4.18.0-348.12.2.EL8_5.X86_64/X86_64/A76BB2E30D>) |

### Mips (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 177d:0092 | 177d:0001 | Cavium           | Octeon II CN65XX Network Processor   | 2     | vfio_pci   | [FB9B03532C](<Server/Supermicro/X9/X9DRW/6A1A83EBE660/DEBIAN-11/5.15.39-1-PVE/X86_64/FB9B03532C>) |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15e2 | 1022:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 27    | snd_rn_... | [EE0C91380E](<Server/ASRockRack/B650/B650D4U-2L2T-BCM/4E50B00275AF/ALMA-8.10/4.18.0-553.33.1.EL8_10.X86_64/X86_64/EE0C91380E>) |
| 1131:7164 | 0070:8851 | Philips Semic... | SAA7164                              | 2     | saa7164    | [DFB6580F2A](<Server/Dell/PowerEdge/PowerEdge T710/DA543BCEB9D6/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/DFB6580F2A>) |
| 1022:15e2 | 15d9:1c97 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     | snd_pci... | [CAB997495E](<Server/Supermicro/Super/Super Server/9ABB78B85737/DEBIAN-12/6.8.12-2-PVE/X86_64/CAB997495E>) |
| 109e:0878 |           | Brooktree        | Bt878 Audio Capture                  | 1     | bt878      | [B55D1DAEA5](<Server/Intel/S5500/S5500BC/EB1E1FCFB3A4/UBUNTU-MATE-19.10/5.3.0-51-GENERIC/X86_64/B55D1DAEA5>) |
| 109e:0878 | 0070:ff04 | Brooktree        | Bt878 Audio Capture                  | 1     |            | [2C877CF870](<Server/Hewlett-Packard/ProLiant/ProLiant DL140 G2/7851FB932D49/ARCH/4.18.12-ARCH1-1-ARCH/X86_64/2C877CF870>) |
| 109e:0878 | 800a:763d | Brooktree        | Bt878 Audio Capture                  | 1     |            | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 109e:0878 | 800b:763d | Brooktree        | Bt878 Audio Capture                  | 1     |            | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 109e:0878 | 800c:763d | Brooktree        | Bt878 Audio Capture                  | 1     |            | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 109e:0878 | 800d:763d | Brooktree        | Bt878 Audio Capture                  | 1     |            | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 1131:7160 | 6985:0002 | Philips Semic... | SAA7160                              | 1     | saa716x... | [4919ECC453](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/7F9639321C91/UBUNTU-20.04/5.15.0-73-GENERIC/X86_64/4919ECC453>) |
| 1131:7231 | 0070:0810 | Philips Semic... | SAA7231                              | 1     |            | [14CD986ACA](<Server/Dell/PowerEdge/PowerEdge R710/13132B93A918/UBUNTU-22.04/6.5.0-14-GENERIC/X86_64/14CD986ACA>) |
| 1172:e003 | 1172:0000 | Altera           | Multimedia controller                | 1     | dyvi       | [1126AE11AE](<Server/ASUSTek Computer/Z11PG-D16/Z11PG-D16 Series/9878F56186D3/DEBIAN-9/4.9.35-DYVI/X86_64/1126AE11AE>) |
| 11af:0012 | 11af:0444 | Avid Technology  | Multimedia controller                | 1     |            | [841DF68A54](<Server/Intel/Thurley/Thurley/FE991D0B4D72/UBUNTU-22.04/5.15.0-25-GENERIC/X86_64/841DF68A54>) |
| 11af:0013 | 11af:0448 | Avid Technology  | Multimedia controller                | 1     |            | [841DF68A54](<Server/Intel/Thurley/Thurley/FE991D0B4D72/UBUNTU-22.04/5.15.0-25-GENERIC/X86_64/841DF68A54>) |
| 1797:6814 | 000a:6814 | Intersil Tech... | TW6816 multimedia video controller   | 1     |            | [B7AE64EA56](<Server/Supermicro/SYS-6028/SYS-6028R-WTR/FAC06E774FCC/ROCKY-8.10/4.18.0-553.8.1.EL8_10.X86_64/X86_64/B7AE64EA56>) |
| 1797:6815 | 000a:6815 | Intersil Tech... | TW6816 multimedia video controller   | 1     |            | [B7AE64EA56](<Server/Supermicro/SYS-6028/SYS-6028R-WTR/FAC06E774FCC/ROCKY-8.10/4.18.0-553.8.1.EL8_10.X86_64/X86_64/B7AE64EA56>) |
| 1797:6816 | 000a:6816 | Intersil Tech... | TW6816 multimedia video controller   | 1     |            | [B7AE64EA56](<Server/Supermicro/SYS-6028/SYS-6028R-WTR/FAC06E774FCC/ROCKY-8.10/4.18.0-553.8.1.EL8_10.X86_64/X86_64/B7AE64EA56>) |
| 1797:6817 | 000a:6817 | Intersil Tech... | TW6816 multimedia video controller   | 1     |            | [B7AE64EA56](<Server/Supermicro/SYS-6028/SYS-6028R-WTR/FAC06E774FCC/ROCKY-8.10/4.18.0-553.8.1.EL8_10.X86_64/X86_64/B7AE64EA56>) |
| 1797:6869 |           | Intersil Tech... | C968 PCIe SD Capture                 | 1     | avc8000    | [375EC8881D](<Server/Neousys Technology/Nuvo-8208GC/Nuvo-8208GC Series/78293157040C/UBUNTU-18.04/5.4.0-53-GENERIC/X86_64/375EC8881D>) |
| 544d:6178 | 6205:0001 | TBS Technologies | DVB Tuner PCIe Card                  | 1     |            | [757C40F561](<Server/Dell/PowerEdge/PowerEdge T110/742C86EF63C5/UBUNTU-22.04/5.15.0-86-GENERIC/X86_64/757C40F561>) |
| 544d:6178 | 6908:0001 | TBS Technologies | DVB Tuner PCIe Card                  | 1     | tbsecp3    | [032E32E32D](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/58114B8A6690/UBUNTU-22.04/6.5.0-18-GENERIC/X86_64/032E32E32D>) |
| 544d:6178 | 6909:0001 | TBS Technologies | DVB Tuner PCIe Card                  | 1     | tbsecp3    | [4919ECC453](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/7F9639321C91/UBUNTU-20.04/5.15.0-73-GENERIC/X86_64/4919ECC453>) |
| 544d:6178 | 6909:0019 | TBS Technologies | DVB Tuner PCIe Card                  | 1     | tbsecp3    | [72B9753B42](<Server/Hewlett-Packard/ProLiant/ProLiant DL380e Gen8/F46144405C53/UBUNTU-18.04/4.15.0-202-GENERIC/X86_64/72B9753B42>) |
| 8086:7d19 | 8086:7270 | Intel            | Meteor Lake IPU                      | 1     |            | [43E67C9439](<Server/Intel/Meteor/Meteor Lake Client Platform/83A3F13660D9/UBUNTU-20.04/5.15.0-100-GENERIC/X86_64/43E67C9439>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14e4:1657 | 103c:22be | Broadcom         | NetXtreme BCM5719 Gigabit Etherne... | 104   | tg3        | [D9F97B2071](<Server/HPE/ProLiant/ProLiant DL380 Gen10/6D60567E7E8D/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/D9F97B2071>) |
| 14e4:165f | 1028:1f5b | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 72    | tg3        | [44126F8D86](<Server/Dell/PowerEdge/PowerEdge R630/23D674735CB9/GENTOO-2.15/6.6.38-GENTOO-MANS/X86_64/44126F8D86>) |
| 14e4:1639 | 103c:7055 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 62    | bnx2       | [B076CBF109](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/416C8912B3CC/DEBIAN/6.11.10-AMD64/X86_64/B076CBF109>) |
| 14e4:1657 | 103c:169d | Broadcom         | NetXtreme BCM5719 Gigabit Etherne... | 60    | tg3        | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |
| 8086:37d2 | 15d9:37d2 | Intel            | Ethernet Connection X722 for 10GB... | 43    | i40e       | [0C4013CAF3](<Server/Supermicro/Super/Super Server/131078870A66/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/0C4013CAF3>) |
| 8086:1572 | 8086:0000 | Intel            | Ethernet Controller X710 for 10Gb... | 41    | i40e       | [943C34D6FE](<Server/Insyde/Purley/Purley/31EA1140F134/DEBIAN-11/5.15.158-2-PVE/X86_64/943C34D6FE>) |
| 8086:37d1 | 15d9:37d1 | Intel            | Ethernet Connection X722 for 1GbE    | 35    | i40e       | [01602FD84E](<Server/Supermicro/SYS-6019/SYS-6019P-WTR/0C2A376E8BE8/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/01602FD84E>) |
| 14e4:1639 | 1028:0235 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 32    | bnx2       | [E9F4F40104](<Server/Dell/PowerEdge/PowerEdge R710/4BAAF0C6A4BB/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/E9F4F40104>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 30    | r8169      | [3B5585BEC8](<Server/Supermicro/X9/X9SRA-X9SRA-3/E73ED86A7227/DEBIAN-11/5.10.0-33-AMD64/X86_64/3B5585BEC8>) |
| 8086:15b9 | 1028:073a | Intel            | Ethernet Connection (3) I219-LM      | 29    | e1000e     | [B75294443B](<Server/Dell/Precision/Precision 7920 Tower/5E36FA18A2AE/KUBUNTU-20.04/5.15.0-84-GENERIC/X86_64/B75294443B>) |
| 8086:159b | 8086:0003 | Intel            | Ethernet Controller E810-XXV for SFP | 28    | ice        | [4235F71014](<Server/Supermicro/AS/AS -1014S-WTRT/4126E18782A7/CYBER-INFRASTRUCTURE-6.5.0/3.10.0-1160.114.2.AIP7.222.1/X86_64/4235F71014>) |
| 14e4:1639 | 1028:0236 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 26    | bnx2       | [A2B12B6DA3](<Server/Dell/PowerEdge/PowerEdge R610/14D2A48FEC25/CENTOS-7/3.10.0-1160.11.1.EL7.X86_64/X86_64/A2B12B6DA3>) |
| 14e4:163b | 1028:02f1 | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 25    | bnx2       | [0D6D6A6743](<Server/Dell/PowerEdge/PowerEdge R510/7E56EFD8FB93/DEBIAN-12/6.8.8-2-PVE/X86_64/0D6D6A6743>) |
| 8086:1521 | 152d:899b | Intel            | I350 Gigabit Network Connection      | 25    | igb        | [7E09CCDA22](<Server/ETegro Technologies/Hyperion/Hyperion RS125 G4/5259A72AB62F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/7E09CCDA22>) |
| 8086:15b9 | 8086:0000 | Intel            | Ethernet Connection (3) I219-LM      | 24    | e1000e     | [943C34D6FE](<Server/Insyde/Purley/Purley/31EA1140F134/DEBIAN-11/5.15.158-2-PVE/X86_64/943C34D6FE>) |
| 14e4:16d8 | 15d9:16d8 | Broadcom         | BCM57416 NetXtreme-E Dual-Media 1... | 22    | bnxt_en    | [4235F71014](<Server/Supermicro/AS/AS -1014S-WTRT/4126E18782A7/CYBER-INFRASTRUCTURE-6.5.0/3.10.0-1160.114.2.AIP7.222.1/X86_64/4235F71014>) |
| 8086:15ff | 8086:0000 | Intel            | Ethernet Controller X710 for 10GB... | 21    | i40e       | [23780701F7](<Server/EPS/MSIS336/MSIS336 MS-S336/7E012565E9F2/UBUNTU-22.04/5.15.0-126-GENERIC/X86_64/23780701F7>) |
| 14e4:164c | 103c:7038 | Broadcom Limited | NetXtreme II BCM5708 Gigabit Ethe... | 20    | bnx2       | [A72E4DEEF3](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G5/5395FD01B3EA/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/A72E4DEEF3>) |
| 8086:10fb | 8086:0003 | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 20    | ixgbe      | [133F7BC9A5](<Server/IBM/System/System x3250 M3 -[4252K4G]-/76E08604766E/DEBIAN-11/6.2.16-20-BPO11-PVE/X86_64/133F7BC9A5>) |
| 8086:1521 | 103c:3380 | Intel            | I350 Gigabit Network Connection      | 20    | igb        | [735D113F73](<Server/Hewlett-Packard/ProLiant/ProLiant DL380e Gen8/4865ACA2339D/CLEAR-LINUX-OS-42390/6.10.10-1463.NATIVE/X86_64/735D113F73>) |
| 14e4:168e | 103c:3382 | Broadcom         | NetXtreme II BCM57810 10 Gigabit ... | 19    | bnx2x      | [6E4FB0D4B2](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/3DAA87FAC48E/DEBIAN-12/6.1.0-26-AMD64/X86_64/6E4FB0D4B2>) |
| 8086:1528 | 15d9:1528 | Intel            | Ethernet Controller 10-Gigabit X5... | 19    | ixgbe      | [CA71A1B4D6](<Server/Supermicro/X9/X9DRH-7TF-7F-iTF-iF/EC8C275F9BA3/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/CA71A1B4D6>) |
| 8086:153a | 15d9:153a | Intel            | Ethernet Connection I217-LM          | 19    | e1000e     | [578C1F5048](<Server/Supermicro/X10/X10SLL-F/02E1EBC8108D/DEBIAN-10/5.4.203-1-PVE/X86_64/578C1F5048>) |
| 14e4:163b | 1028:028c | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 18    | bnx2       | [B6E4EA8841](<Server/Dell/PowerEdge/PowerEdge R410/904CC8DF7D0A/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/B6E4EA8841>) |
| 14e4:165f | 1028:04fa | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 18    | tg3        | [B416E87C4A](<Server/Dell/PowerEdge/PowerEdge T320/7C98CB79C6C7/OPENMANDRIVA-24.09/6.11.0-DESKTOP-2OMV2490/X86_64/B416E87C4A>) |
| 14e4:16d6 | 14e4:4124 | Broadcom         | BCM57412 NetXtreme-E 10Gb RDMA Et... | 18    | bnxt_en    | [5FB0C3A747](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2450 M2/6F7BBA6E51B5/GENTOO-2.15/6.6.30-1-LTS/X86_64/5FB0C3A747>) |
| 14e4:1639 | 1014:03a9 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 17    | bnx2       | [3286B36B51](<Server/IBM/System/System x3650 M3 -[7945YBU]-/64198599779C/DEBIAN-12/6.8.12-1-PVE/X86_64/3286B36B51>) |
| 14e4:165a | 1028:04de | Broadcom         | NetXtreme BCM5722 Gigabit Etherne... | 17    | tg3        | [1E51138D9B](<Server/Dell/PowerEdge/PowerEdge T110 II/A23024949A59/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/1E51138D9B>) |
| 14e4:165f | 103c:22e8 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 17    | tg3        | [F83E3EE442](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/00F75AC4089A/FEDORA-40/6.10.10-200.FC40.X86_64/X86_64/F83E3EE442>) |
| 8086:10fb | 8086:000c | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 17    | ixgbe      | [19F56B169E](<Server/Insyde/Purley/Purley/59D48E04A69B/RED-OS-7.3/6.1.52-1.EL7.3.X86_64/X86_64/19F56B169E>) |
| 8086:1563 | 15d9:1563 | Intel            | Ethernet Controller X550             | 16    | ixgbe      | [0BD63D201C](<Server/Supermicro/Super/Super Server/745BF698699B/MANJARO/6.10.11-2-MANJARO/X86_64/0BD63D201C>) |
| 8086:15b9 | 1028:0739 | Intel            | Ethernet Connection (3) I219-LM      | 16    | e1000e     | [BA0626CE0A](<Server/Dell/Precision/Precision 7820 Tower/3792A2743A38/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/BA0626CE0A>) |
| 14e4:163b | 1028:02a4 | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 15    | bnx2       | [48E00D403A](<Server/Dell/PowerEdge/PowerEdge T310/0EAF01173A25/DEBIAN-12/6.6.32-PRODUCTION+TRUENAS/X86_64/48E00D403A>) |
| 8086:37d1 | 17aa:4020 | Intel            | Ethernet Connection X722 for 1GbE    | 15    | i40e       | [424E70419E](<Server/Lenovo/ThinkSystem/ThinkSystem SR570 -[7Y03CTO1WW]-/D3469A41F07A/XUBUNTU-18.04/4.15.0-213-GENERIC/X86_64/424E70419E>) |
| 14e4:165f | 1028:08fd | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 14    | tg3        | [CE34F45F28](<Server/AWS Elemental/Appliance/Appliance/78AD1C73F775/UBUNTU-22.04/6.5.0-27-GENERIC/X86_64/CE34F45F28>) |
| 8086:15b7 | 15d9:15b7 | Intel            | Ethernet Connection (2) I219-LM      | 14    | e1000e     | [23F3141732](<Server/Supermicro/Super/Super Server/C06149C5792E/UBUNTU-24.04/6.8.0-36-GENERIC/X86_64/23F3141732>) |
| 14e4:1639 | 1028:1f26 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 13    | bnx2       | [2D3D5673E7](<Server/Dell/PowerEdge/PowerEdge R815/6B72BADC37CC/UBUNTU-22.04/5.15.0-119-GENERIC/X86_64/2D3D5673E7>) |
| 14e4:163b | 1028:04dd | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 13    | bnx2       | [969B046986](<Server/Dell/PowerEdge/PowerEdge R210 II/93E843E2F825/UBUNTU-22.04/5.15.0-124-GENERIC/X86_64/969B046986>) |
| 15b3:1015 | 15b3:0004 | Mellanox Tech... | MT27710 Family [ConnectX-4 Lx]       | 13    | mlx5_core  | [FF8C7320CC](<Server/Supermicro/Super/Super Server/FD3A63BBABAD/CYBER-INFRASTRUCTURE-6.0.0/3.10.0-1160.105.1.AIP7.214.3/X86_64/FF8C7320CC>) |
| 8086:1563 | 8086:0001 | Intel            | Ethernet Controller X550             | 13    | ixgbe      | [755C2C2B13](<Server/Dell/PowerEdge/PowerEdge T630/0073F51087B6/DEBIAN-12/6.5.13-5-PVE/X86_64/755C2C2B13>) |
| 8086:15b9 | 17aa:1038 | Intel            | Ethernet Connection (3) I219-LM      | 13    | e1000e     | [CAFAEE2FC7](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC000QGE/C9B0658BA91C/DEBIAN-12/6.1.0-28-AMD64/X86_64/CAFAEE2FC7>) |
| 14e4:164c | 1028:01b2 | Broadcom         | NetXtreme II BCM5708 Gigabit Ethe... | 12    | bnx2       | [5DE4C4A538](<Server/Dell/PowerEdge/PowerEdge 2950/A7ED8CBDCF7D/LMDE-6/6.1.0-28-AMD64/X86_64/5DE4C4A538>) |
| 14e4:165f | 1028:0639 | Broadcom Limited | NetXtreme BCM5720 Gigabit Etherne... | 12    | tg3        | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 14e4:168a | 1028:1f67 | Broadcom         | NetXtreme II BCM57800 1/10 Gigabi... | 12    | bnx2x      | [D59552DE3E](<Server/Dell/PowerEdge/PowerEdge R730/C3E2640E6C9F/DEBIAN-12/6.8.8-4-PVE/X86_64/D59552DE3E>) |
| 8086:1528 | 15d9:0847 | Intel            | Ethernet Controller 10-Gigabit X5... | 12    | ixgbe      | [D24D2612FE](<Server/Supermicro/Super/Super Server/F4A31F1B8877/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/D24D2612FE>) |
| 8086:1528 | 19e5:d110 | Intel            | Ethernet Controller 10-Gigabit X5... | 12    | ixgbe      | [EDA2D8550F](<Server/HUAWEI/RH1288/RH1288 V3/899B0DE1B12F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/EDA2D8550F>) |
| 8086:1528 | 8086:0001 | Intel            | Ethernet Controller 10-Gigabit X5... | 12    | ixgbe      | [726B65D6E8](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.10/4.18.0-553.27.1.EL8_10.X86_64/X86_64/726B65D6E8>) |
| 8086:15f3 | 8086:0000 | Intel            | Ethernet Controller I225-V           | 12    | igc        | [DF42F11E59](<Server/GEEKOM/GT13/GT13 Pro/EF7C9F2D8B32/LINUXMINT-22/6.8.0-48-GENERIC/X86_64/DF42F11E59>) |
| 8086:15ff | 8086:0003 | Intel            | Ethernet Controller X710 for 10GB... | 12    | i40e       | [A466D61B44](<Server/Supermicro/SYS-1029/SYS-1029P-WTR/6B7A3609D8D6/CYBER-INFRASTRUCTURE-5.5.0/3.10.0-1160.105.1.AIP7.214.3/X86_64/A466D61B44>) |
| 14e4:163b | 1028:028d | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 11    | bnx2       | [A35A094F7E](<Server/Dell/PowerEdge/PowerEdge T410/981EBE64D562/UBUNTU-22.04/5.15.0-126-GENERIC/X86_64/A35A094F7E>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2723 | 8086:0084 | Intel            | Wi-Fi 6 AX200                        | 14    | iwlwifi    | [F30D39393C](<Server/BESSTAR Tech/X/X400/B2CBACACFA8F/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/F30D39393C>) |
| 14c3:7922 | 1a3b:5911 | MediaTek         | MT7922 802.11ax PCI Express Wirel... | 13    | mt7921e    | [DF42F11E59](<Server/GEEKOM/GT13/GT13 Pro/EF7C9F2D8B32/LINUXMINT-22/6.8.0-48-GENERIC/X86_64/DF42F11E59>) |
| 8086:2725 | 8086:0024 | Intel            | Wi-Fi 6E(802.11ax) AX210/AX1675* ... | 6     | iwlwifi    | [5CA3522B87](<Server/Dell/PowerEdge/PowerEdge R910/1DA1E79D8B43/XUBUNTU-24.04/6.8.0-47-GENERIC/X86_64/5CA3522B87>) |
| 10ec:8125 | 10ec:0123 | Realtek Semic... | RTL8125 2.5GbE Controller            | 5     | r8169      | [3321BC6ABD](<Server/ASUSTek Computer/Z9PA-D8/Z9PA-D8 Series/3F5F9C7C17F0/DEBIAN-12/6.8.12-5-PVE/X86_64/3321BC6ABD>) |
| 10ec:c821 | 10ec:c821 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 4     | rtw88_8... | [6B8F982987](<Server/GEEKOM/MiniAir/MiniAir 11/5E7475318C5E/UBUNTU-24.04/6.8.0-35-GENERIC/X86_64/6B8F982987>) |
| 14c3:0608 | 14c3:0608 | MediaTek         | MT7921K (RZ608) Wi-Fi 6E 80MHz       | 4     | mt7921e    | [6A0AF69B4A](<Server/Dell/PowerEdge/PowerEdge R720/F424DE07066D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6A0AF69B4A>) |
| 8086:2526 | 8086:0014 | Intel            | Wi-Fi 5(802.11ac) Wireless-AC 9x6... | 4     | iwlwifi    | [076E19B0AA](<Server/ASUSTek Computer/WS-C621E-SAGE/WS-C621E-SAGE Series/D9B6F0153F86/POP!_OS-22.04/6.5.6-76060506-GENERIC/X86_64/076E19B0AA>) |
| 10ec:b852 | 10ec:b852 | Realtek Semic... | RTL8852BE PCIe 802.11ax Wireless ... | 3     | rtw89_8... | [94CCA0DB39](<Server/GEEKOM/Mini/Mini Air12/F53E738CBAB9/LINUXMINT-22/6.8.0-47-GENERIC/X86_64/94CCA0DB39>) |
| 14e4:43a0 | 14e4:0619 | Broadcom         | BCM4360 802.11ac Dual Band Wirele... | 3     | wl         | [A0623DC5A7](<Server/Dell/Precision/Precision 7820 Tower/70D486E7A18E/UBUNTU-22.10/5.19.0-40-GENERIC/X86_64/A0623DC5A7>) |
| 168c:002e | 168c:30a4 | Qualcomm Atheros | AR9287 Wireless Network Adapter (... | 3     | ath9k      | [93DE2051E2](<Server/Supermicro/X8/X8DT3/3D7941CC8117/GENTOO-2.13/5.19.3-GENTOO/X86_64/93DE2051E2>) |
| 168c:003e | 168c:3360 | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 3     | ath10k_pci | [AE43167B8A](<Server/ECS/LIVA/LIVA Q2/6F0AAEC80AB2/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/AE43167B8A>) |
| 8086:24fd | 8086:0010 | Intel            | Wireless 8265 / 8275                 | 3     | iwlwifi    | [1D6082EFE8](<Server/Lenovo/ThinkStation/ThinkStation P720 30BBS21C01/FE8DF4F9C290/FEDORA-37/6.2.11-200.FC37.X86_64/X86_64/1D6082EFE8>) |
| 8086:24fd | 8086:0050 | Intel            | Wireless 8265 / 8275                 | 3     | iwlwifi    | [806213DAC1](<Server/Intel/S3420/S3420GP/CF6DB3BD70D6/UBUNTU-24.04/6.8.0-38-GENERIC/X86_64/806213DAC1>) |
| 8086:2725 | 8086:0020 | Intel            | Wi-Fi 6E(802.11ax) AX210/AX1675* ... | 3     | iwlwifi    | [791DC0869D](<Server/Lenovo/ThinkStation/ThinkStation PX 30EUA0EG00/8A299C9A2065/DEBIAN-12/6.10.11+BPO-AMD64/X86_64/791DC0869D>) |
| 8086:a370 | 8086:0034 | Intel            | Cannon Lake PCH CNVi WiFi            | 3     | iwlwifi    | [8648FC0825](<Server/Supermicro/C9/C9Z390-CG-IW/64D15818D339/UBUNTU-22.04/5.15.0-30-GENERIC/X86_64/8648FC0825>) |
| 10ec:8179 | 10ec:8197 | Realtek Semic... | RTL8188EE Wireless Network Adapter   | 2     | rtl8188ee  | [5731D8F8DC](<Server/Supermicro/C7/C7Z370-CG-L/D66B6C0B7FDD/LINUXMINT-21.1/5.15.0-75-GENERIC/X86_64/5731D8F8DC>) |
| 10ec:8812 | 10ec:8203 | Realtek Semic... | RTL8812AE 802.11ac PCIe Wireless ... | 2     | rtl8821ae  | [4B0CFEC9A7](<Server/Supermicro/X10/X10SAE/FF0B31A8C494/NOBARA-37/6.2.10-200.FSYNC.FC37.X86_64/X86_64/4B0CFEC9A7>) |
| 10ec:8812 | 10ec:8812 | Realtek Semic... | RTL8812AE 802.11ac PCIe Wireless ... | 2     | rtl8821ae  | [FE6DC0D9C7](<Server/Dell/Precision/Precision 7820 Tower/FB09ECB98D56/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FE6DC0D9C7>) |
| 8086:095a | 8086:9010 | Intel            | Wireless 7265                        | 2     | iwlwifi    | [0D27879BB6](<Server/GEEKOM/MiniAir/MiniAir 11/696C922FC5EB/OPENMANDRIVA-4.3/5.16.13-DESKTOP-1OMV4003/X86_64/0D27879BB6>) |
| 8086:24fb | 8086:2110 | Intel            | Dual Band Wireless-AC 3168NGW [St... | 2     | iwlwifi    | [A96D1129F7](<Server/Intel/S5500/S5500HCV/D87EBB706FDF/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/A96D1129F7>) |
| 10ec:818b | 10ec:8196 | Realtek Semic... | RTL8192EE PCIe Wireless Network A... | 1     | rtl8192ee  | [62C087CE77](<Server/Supermicro/Super/Super Server/1EA3150B8AF0/FEDORA-40/6.10.6-200.FC40.X86_64/X86_64/62C087CE77>) |
| 10ec:b822 | 1a3b:2951 | Realtek Semic... | RTL8822BE 802.11a/b/g/n/ac WiFi a... | 1     | rtw88_8... | [5145E7D26E](<Server/Supermicro/C7/C7Z370-CG-IW/66BE2E39DAA0/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/5145E7D26E>) |
| 10ec:c821 | 1a3b:3041 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 1     | rtw88_8... | [B076CBF109](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/416C8912B3CC/DEBIAN/6.11.10-AMD64/X86_64/B076CBF109>) |
| 14e4:43a0 | 1043:85df | Broadcom         | BCM4360 802.11ac Dual Band Wirele... | 1     | wl         | [E14FDDFA11](<Server/Gigabyte Technology/GA-7/GA-7PESLX/0F0117B3BD76/ZORIN-17/6.5.0-15-GENERIC/X86_64/E14FDDFA11>) |
| 14e4:43ba | 106b:0133 | Broadcom         | BCM43602 802.11ac Wireless LAN SoC   | 1     | brcmfmac   | [FC1F78ADA0](<Server/Supermicro/Super/Super Server/C97C65EAC5E2/UBUNTU-20.04/5.4.0-40-GENERIC/X86_64/FC1F78ADA0>) |
| 168c:0013 | 1186:3a73 | Qualcomm Atheros | AR5212/5213/2414 Wireless Network... | 1     | ath5k      | [8F945E0A15](<Server/Supermicro/X8/X8DTL/7581500BE1DB/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/8F945E0A15>) |
| 168c:0013 | 168c:2051 | Qualcomm Atheros | AR5212/5213/2414 Wireless Network... | 1     | ath5k      | [FE3D758C20](<Server/Intel/S5500/S5500BC/EB1E1FCFB3A4/KDE-NEON-20.04/5.4.0-66-GENERIC/X86_64/FE3D758C20>) |
| 168c:001d | 1113:b203 | Qualcomm Atheros | AR2417 Wireless Network Adapter [... | 1     | ath5k      | [EF95821AFC](<Server/Supermicro/X10/X10SAE/233AFEE2447E/UBUNTU-MATE-20.04/5.4.0-52-GENERIC/X86_64/EF95821AFC>) |
| 168c:001d | 168c:2055 | Qualcomm Atheros | AR2417 Wireless Network Adapter [... | 1     | ath5k      | [16BEFD9DC3](<Server/Supermicro/X10/X10SAE/233AFEE2447E/OPENSUSE-TUMBLEWEED-XXXXXXXX/5.11.4-1-DEFAULT/X86_64/16BEFD9DC3>) |
| 168c:0030 | 144f:7188 | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 1     | ath9k      | [C6FE3BE3CD](<Server/Dell/PowerEdge/PowerEdge T420/84B5AE1C1912/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/C6FE3BE3CD>) |
| 168c:0030 | 168c:3112 | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 1     | ath9k      | [B9AC0D657E](<Server/Supermicro/A1/A1SRM-2558F/DAF42406F667/FEDORA-32/5.8.16-200.FC32.X86_64/X86_64/B9AC0D657E>) |
| 168c:0030 | 168c:3116 | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 1     | ath9k      | [D52E0ED118](<Server/Neousys Technology/Nuvo-7000/Nuvo-7000 Series/55C9FBF8C557/UBUNTU-20.04/5.13.0-37-GENERIC/X86_64/D52E0ED118>) |
| 168c:0032 | 168c:3118 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 1     | ath9k      | [E70645D3E6](<Server/Intel/W2600/W2600CR/5A75A85091D9/UBUNTU-20.04/5.4.0-80-GENERIC/X86_64/E70645D3E6>) |
| 168c:0034 | 105b:e058 | Qualcomm Atheros | AR9462 Wireless Network Adapter      | 1     | ath9k      | [676C3ECA96](<Server/Intel/S5520/S5520HC/4D880C0CBA79/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/676C3ECA96>) |
| 168c:0036 | 103c:18e3 | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 1     | ath9k      | [6D994999C9](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G7/A848C0BF3086/ROCKY-9.0/5.14.0-70.17.1.EL9_0.X86_64/X86_64/6D994999C9>) |
| 168c:0037 | 1a3b:2100 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 1     | ath9k      | [0C8C032D4A](<Server/Gigabyte Technology/GA-6/GA-6PXSVT/77D6155C8845/ELEMENTARY-7.1/6.5.0-35-GENERIC/X86_64/0C8C032D4A>) |
| 1814:0301 | 1737:0055 | Ralink           | RT2561/RT61 802.11g PCI              | 1     | rt61pci    | [5600070A23](<Server/ASUSTek Computer/Z9PA-U8/Z9PA-U8 Series/ACAF72B240BB/UBUNTU-18.04/5.4.0-48-GENERIC/X86_64/5600070A23>) |
| 1814:3062 | 1814:3062 | Ralink           | RT3062 Wireless 802.11n 2T/2R        | 1     | rt2800pci  | [DA3626FE6C](<Server/Hewlett-Packard/HP/HP NetServer/EC05DE7F9D5E/UBUNTU-16.04/4.4.0-210-GENERIC/I686/DA3626FE6C>) |
| 1814:5392 | 1186:3c06 | Ralink           | RT5392 PCIe Wireless Network Adapter | 1     | rt2800pci  | [E24D0E827B](<Server/Dell/PowerEdge/PowerEdge T110 II/C9588E9ACEC9/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/E24D0E827B>) |
| 8086:08b1 | 8086:4070 | Intel            | Wireless 7260                        | 1     | iwlwifi    | [3CB0E7E907](<Server/System76/Silverback/Silverback WS/10B1D15652E1/DEBIAN-12/6.1.0-17-AMD64/X86_64/3CB0E7E907>) |
| 8086:08b1 | 8086:4470 | Intel            | Wireless 7260                        | 1     | iwlwifi    | [B8FFB92409](<Server/Neousys Technology/Nuvo-8108GC/Nuvo-8108GC Series/0E8814EA22E8/UBUNTU-18.04/5.4.0-56-GENERIC/X86_64/B8FFB92409>) |
| 8086:08b1 | 8086:c070 | Intel            | Wireless 7260                        | 1     | iwlwifi    | [026B32269E](<Server/ASUSTek Computer/Z9PE-D8/Z9PE-D8 WS/F5006016F49C/CENTOS-8/4.18.0-193.28.1.EL8_2.X86_64/X86_64/026B32269E>) |
| 8086:093c | 8086:7001 | Intel            | Wireless Gigabit 17265               | 1     |            | [F600E260E9](<Server/Lenovo/ThinkStation/ThinkStation P920 30BDS0RB00/48C5B5FA7A49/FEDORA-39/6.9.8-100.FC39.X86_64/X86_64/F600E260E9>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 1     | iwlwifi    | [377C88D227](<Server/Intel/S2600/S2600CO/CF676281389E/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/377C88D227>) |
| 8086:24f3 | 8086:0010 | Intel            | Wireless 8260                        | 1     | iwlwifi    | [A54A6DED9C](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/94A1A58A00C5/UBUNTU-22.04/6.5.0-27-GENERIC/X86_64/A54A6DED9C>) |
| 8086:3165 | 8086:8010 | Intel            | Wireless 3165                        | 1     | iwlwifi    | [F5A2B2DE44](<Server/GEEKOM/MiniAir/MiniAir 11/A07BDBCD0072/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/F5A2B2DE44>) |
| 8086:a370 | 8086:0030 | Intel            | Cannon Lake PCH CNVi WiFi            | 1     | iwlwifi    | [065427C37F](<Server/Supermicro/Super/Super Server/2CF7574245C0/DEBIAN-11/5.10.162-1.LAT5.10.0-21/X86_64/065427C37F>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1533 | 15d9:1533 | Intel            | I210 Gigabit Network Connection      | 178   | igb        | [CAB997495E](<Server/Supermicro/Super/Super Server/9ABB78B85737/DEBIAN-12/6.8.12-2-PVE/X86_64/CAB997495E>) |
| 8086:1521 | 15d9:1521 | Intel            | I350 Gigabit Network Connection      | 174   | igb        | [F3D2F362E8](<Server/Supermicro/X9/X9SRE-X9SRE-3F-X9SRi-X9SRi-3F/55A635F4E92C/DEBIAN-12/6.8.8-2-PVE/X86_64/F3D2F362E8>) |
| 8086:10c9 | 15d9:10c9 | Intel            | 82576 Gigabit Network Connection     | 41    | igb        | [8C5797ED25](<Server/Supermicro/X8/X8DTT/714C700A2F5C/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/8C5797ED25>) |
| 8086:10d3 | 15d9:10d3 | Intel            | 82574L Gigabit Network Connection    | 41    | e1000e     | [05F8EBDF95](<Server/Supermicro/X8/X8DTT-H/319D85D1D7C9/LUBUNTU-22.04/5.15.0-125-GENERIC/X86_64/05F8EBDF95>) |
| 8086:1521 | 1028:1f60 | Intel            | I350 Gigabit Network Connection      | 38    | igb        | [888A235104](<Server/Dell/PowerEdge/PowerEdge R730/B44B0E51BDB3/DEBIAN-12/6.8.12-4-PVE/X86_64/888A235104>) |
| 8086:10d3 | 1043:8369 | Intel            | 82574L Gigabit Network Connection    | 36    | e1000e     | [3321BC6ABD](<Server/ASUSTek Computer/Z9PA-D8/Z9PA-D8 Series/3F5F9C7C17F0/DEBIAN-12/6.8.12-5-PVE/X86_64/3321BC6ABD>) |
| 8086:1533 | 1043:8557 | Intel            | I210 Gigabit Network Connection      | 35    | igb        | [E805BE0AAC](<Server/Kraftway/GEG/GEG/C4E325834440/DEBIAN-12/6.1.0-27-AMD64/X86_64/E805BE0AAC>) |
| 8086:10c9 | 15d9:0100 | Intel            | 82576 Gigabit Network Connection     | 33    | igb        | [6918605D42](<Server/Supermicro/X8/X8DTU/2EC017791B11/DEBIAN-12/6.8.12-5-PVE/X86_64/6918605D42>) |
| 8086:1533 | ffff:0000 | Intel            | I210 Gigabit Network Connection      | 31    | igb        | [F71EAE46A6](<Server/Intel/BIRCHSTREAM/BIRCHSTREAM/1F03C9158405/XUBUNTU-24.04/6.8.0-48-GENERIC/X86_64/F71EAE46A6>) |
| 8086:1533 | 1028:0619 | Intel            | I210 Gigabit Network Connection      | 28    | igb        | [B75294443B](<Server/Dell/Precision/Precision 7920 Tower/5E36FA18A2AE/KUBUNTU-20.04/5.15.0-84-GENERIC/X86_64/B75294443B>) |
| 8086:10c9 | 15d9:0600 | Intel            | 82576 Gigabit Network Connection     | 27    | igb        | [B66E4C113A](<Server/DEPO Computers/X8/X8DTU/732C5C269461/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/B66E4C113A>) |
| 8086:1533 | 1849:1533 | Intel            | I210 Gigabit Network Connection      | 27    | igb        | [EE0C91380E](<Server/ASRockRack/B650/B650D4U-2L2T-BCM/4E50B00275AF/ALMA-8.10/4.18.0-553.33.1.EL8_10.X86_64/X86_64/EE0C91380E>) |
| 8086:1521 | ffff:0000 | Intel            | I350 Gigabit Network Connection      | 20    | igb        | [A2CE10373E](<Server/Graviton/S2122/S2122IU/ED2248ACB950/ROSA-12/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/A2CE10373E>) |
| 8086:1521 | 1458:0000 | Intel            | I350 Gigabit Network Connection      | 19    | igb        | [F9ECA543F7](<Server/Gigabyte Technology/MZ32/MZ32-AR0-00/EF6E29D7D44C/UBUNTU-23.10/6.5.0-44-GENERIC/X86_64/F9ECA543F7>) |
| 8086:10d3 | 8086:0000 | Intel            | 82574L Gigabit Network Connection    | 16    | e1000e     | [F82AA66A16](<Server/Schweitzer Engineering Laboratories/SEL/SEL-3355/766281720A90/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/F82AA66A16>) |
| 8086:10a7 | 8086:34dc | Intel            | 82575EB Gigabit Network Connection   | 14    | igb        | [BD871B1C6F](<Server/Intel/S5520/S5520HC/256D70541E78/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/BD871B1C6F>) |
| 8086:10c9 | 103c:323f | Intel            | 82576 Gigabit Network Connection     | 14    | igb        | [683A6AEB9D](<Server/Hewlett-Packard/ProLiant/ProLiant DL165 G7/7792B2C8D06D/UBUNTU-24.04/6.8.0-35-GENERIC/X86_64/683A6AEB9D>) |
| 8086:1521 | 8086:1521 | Intel            | I350 Gigabit Network Connection      | 14    | igb        | [128986423A](<Server/IBM/System/System x3650 M4 -[7915E1G]-/605DCB19505B/CENTOS-6/2.6.32-696.20.1.EL6.X86_64/X86_64/128986423A>) |
| 8086:10d3 | 1734:1192 | Intel            | 82574L Gigabit Network Connection    | 13    | e1000e     | [486301061F](<Server/Fujitsu/PRIMERGY/PRIMERGY TX150 S7/3406DF3EF425/ARCH-ROLLING/6.12.7-ARCH1-1/X86_64/486301061F>) |
| 15b3:1017 | 15b3:0007 | Mellanox Tech... | MT27800 Family [ConnectX-5]          | 12    | mlx5_core  | [01602FD84E](<Server/Supermicro/SYS-6019/SYS-6019P-WTR/0C2A376E8BE8/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/01602FD84E>) |
| 8086:10d3 | 8086:3578 | Intel            | 82574L Gigabit Network Connection    | 12    | e1000e     | [69CCB9B978](<Server/Intel/S1200/S1200BTL/8EF10894528C/UBUNTU-22.04/6.5.0-35-GENERIC/X86_64/69CCB9B978>) |
| 8086:1502 | 8086:3578 | Intel            | 82579LM Gigabit Network Connectio... | 12    | e1000e     | [69CCB9B978](<Server/Intel/S1200/S1200BTL/8EF10894528C/UBUNTU-22.04/6.5.0-35-GENERIC/X86_64/69CCB9B978>) |
| 8086:1533 | 17aa:1038 | Intel            | I210 Gigabit Network Connection      | 12    | igb        | [CAFAEE2FC7](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC000QGE/C9B0658BA91C/DEBIAN-12/6.1.0-28-AMD64/X86_64/CAFAEE2FC7>) |
| 15b3:1017 | 15b3:0020 | Mellanox Tech... | MT27800 Family [ConnectX-5]          | 11    | mlx5_core  | [1423C51CDB](<Server/w 9k/Others/Others/23BA3B5E78E1/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/1423C51CDB>) |
| 8086:10d3 | 15d9:0000 | Intel            | 82574L Gigabit Network Connection    | 11    | e1000e     | [3B5585BEC8](<Server/Supermicro/X9/X9SRA-X9SRA-3/E73ED86A7227/DEBIAN-11/5.10.0-33-AMD64/X86_64/3B5585BEC8>) |
| 8086:1521 | 1028:1f73 | Intel            | I350 Gigabit Network Connection      | 11    | igb        | [72A4F63713](<Server/Dell/PowerEdge/PowerEdge R730XD/1A3F6F422946/DEBIAN-12/6.8.12-4-PVE/X86_64/72A4F63713>) |
| 8086:1533 | 8086:35b4 | Intel            | I210 Gigabit Network Connection      | 11    | igb        | [6A61981EA4](<Server/Wortmann AG/TERRA_SERVER/TERRA_SERVER/A40FD0B78666/UBUNTU-22.04/6.5.0-17-GENERIC/X86_64/6A61981EA4>) |
| 1077:8020 | 103c:3733 | QLogic           | cLOM8214 1/10GbE Controller          | 10    | qlcnic     | [A9289CA04C](<Server/IBM/System/System x3650 M3 -[794562M]-/70C4A6EC4717/ARCH-ROLLING/5.18.6-ARCH1-1/X86_64/A9289CA04C>) |
| 15b3:1015 | 15b3:0003 | Mellanox Tech... | MT27710 Family [ConnectX-4 Lx]       | 10    | mlx5_core  | [8B21D2F04C](<Server/INFERIT/R1/R1G3D32/EC54AC1F686F/ROSA-12F.1/6.1.58-GENERIC-5ROSA2021.15-X86_64/X86_64/8B21D2F04C>) |
| 15b3:673c | 15b3:673c | Mellanox Tech... | MT25408A0-FCC-QI ConnectX, Dual P... | 10    | mlx4_core  | [8C5797ED25](<Server/Supermicro/X8/X8DTT/714C700A2F5C/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/8C5797ED25>) |
| 8086:10c9 | 15d9:ab11 | Intel            | 82576 Gigabit Network Connection     | 10    | igb        | [E673BAB21F](<Server/Supermicro/H8/H8QG6/539918058863/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/E673BAB21F>) |
| 8086:10d3 | 8086:34ec | Intel            | 82574L Gigabit Network Connection    | 10    | e1000e     | [D735382568](<Server/HCL/S3420/S3420GPV/403EC13AAE26/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/D735382568>) |
| 8086:10ef | 8086:34ec | Intel            | 82578DM Gigabit Network Connection   | 10    | e1000e     | [D735382568](<Server/HCL/S3420/S3420GPV/403EC13AAE26/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/D735382568>) |
| 15b3:1013 | 15b3:0010 | Mellanox Tech... | MT27700 Family [ConnectX-4]          | 9     | mlx5_core  | [4235F71014](<Server/Supermicro/AS/AS -1014S-WTRT/4126E18782A7/CYBER-INFRASTRUCTURE-6.5.0/3.10.0-1160.114.2.AIP7.222.1/X86_64/4235F71014>) |
| 8086:1533 | 1458:0000 | Intel            | I210 Gigabit Network Connection      | 9     | igb        | [532EDFCFAC](<Server/Gigabyte Technology/MU70/MU70-SU0-NV-XX/34029535BAED/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/532EDFCFAC>) |
| 8086:1539 | 8086:0000 | Intel            | I211 Gigabit Network Connection      | 9     | igb        | [943C34D6FE](<Server/Insyde/Purley/Purley/31EA1140F134/DEBIAN-11/5.15.158-2-PVE/X86_64/943C34D6FE>) |
| 15b3:1003 | 15b3:0050 | Mellanox Tech... | MT27500 Family [ConnectX-3]          | 8     | mlx4_core  | [A60CF74303](<Server/Others/04N3DF/04N3DF A11/5E891354636F/DEBIAN-12/6.8.12-1-PVE/X86_64/A60CF74303>) |
| 15b3:1007 | 15b3:000c | Mellanox Tech... | MT27520 Family [ConnectX-3 Pro]      | 8     | mlx4_core  | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 4040:0100 | 103c:705a | NetXen Incorp... | NX3031 Multifunction 1/10-Gigabit... | 8     | netxen_nic | [05B7C13538](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/38DF42BD22E8/DEBIAN-12/6.5.11-7-PVE/X86_64/05B7C13538>) |
| 8086:10fb | 15d9:0611 | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 8     | ixgbe      | [39232DFDE3](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/B0C1ED30C610/DEBIAN-12/6.1.0-25-AMD64/X86_64/39232DFDE3>) |
| 15b3:6750 | 15b3:0015 | Mellanox Tech... | MT26448 [ConnectX EN 10GigE, PCIe... | 7     | mlx4_core  | [0D6D6A6743](<Server/Dell/PowerEdge/PowerEdge R510/7E56EFD8FB93/DEBIAN-12/6.8.8-2-PVE/X86_64/0D6D6A6743>) |
| 8086:10bd | 8086:34d0 | Intel            | 82566DM-2 Gigabit Network Connection | 7     | e1000e     | [40FC7CD8AA](<Server/Intel/S3210/S3210SH/D6FE7FA8CA14/DEBIAN-11/5.15.30-2-PVE/X86_64/40FC7CD8AA>) |
| 8086:10c9 | 15d9:060f | Intel            | 82576 Gigabit Network Connection     | 7     | igb        | [673665AF55](<Server/DEPO Computers/X8/X8DTN+-F/C21E3E059615/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/673665AF55>) |
| 8086:10cc | 8086:34da | Intel            | 82567LM-2 Gigabit Network Connection | 7     | e1000e     | [D7D5249BC9](<Server/Intel/S5500/S5500BC/49891E2271E6/UBUNTU-22.04/6.2.0-31-GENERIC/X86_64/D7D5249BC9>) |
| 8086:10d3 | 8086:34da | Intel            | 82574L Gigabit Network Connection    | 7     | e1000e     | [D7D5249BC9](<Server/Intel/S5500/S5500BC/49891E2271E6/UBUNTU-22.04/6.2.0-31-GENERIC/X86_64/D7D5249BC9>) |
| 8086:10d3 | 8086:a01f | Intel            | 82574L Gigabit Network Connection    | 7     | e1000e     | [9C52136F33](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/94BA1F306E38/UBUNTU-18.04/4.15.0-76-GENERIC/X86_64/9C52136F33>) |
| 8086:1502 | 15d9:0623 | Intel            | 82579LM Gigabit Network Connectio... | 7     | e1000e     | [3B5585BEC8](<Server/Supermicro/X9/X9SRA-X9SRA-3/E73ED86A7227/DEBIAN-11/5.10.0-33-AMD64/X86_64/3B5585BEC8>) |
| 8086:1521 | 15d9:0656 | Intel            | I350 Gigabit Network Connection      | 7     | igb        | [8619E38037](<Server/Gigabyte Technology/E252/E252-P30-00/513B50B63035/UBUNTU-20.04/5.4.0-145-GENERIC/AARCH64/8619E38037>) |
| 8086:1521 | 8086:357e | Intel            | I350 Gigabit Network Connection      | 7     | igb        | [48F56B1871](<Server/Intel/S2600/S2600CP/931EED482113/UBUNTU-22.04/6.2.0-39-GENERIC/X86_64/48F56B1871>) |
| 15b3:1003 | 15b3:0090 | Mellanox Tech... | MT27500 Family [ConnectX-3]          | 6     | mlx4_core  | [565F6E8DCC](<Server/Dell/PowerEdge/PowerEdge R720/E58BDCDE7390/UBUNTU-18.04/5.4.0-150-GENERIC/X86_64/565F6E8DCC>) |

### Network and computing encryption device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19e5:a255 |           | Huawei Techno... | HiSilicon SEC Engine                 | 1     | hisi_sec2  | [29BDE967FC](<Server/HUAWEI/TaiShan/TaiShan 2280 V2/2603C7B2E57E/UBUNTU-22.04/5.15.0-88-GENERIC/AARCH64/29BDE967FC>) |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1485 | 1022:1485 | AMD              | Starship/Matisse Reserved SPP        | 75    |            | [726B65D6E8](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.10/4.18.0-553.27.1.EL8_10.X86_64/X86_64/726B65D6E8>) |
| 1022:148a | 1022:148a | AMD              | Starship/Matisse PCIe Dummy Function | 74    |            | [726B65D6E8](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.10/4.18.0-553.27.1.EL8_10.X86_64/X86_64/726B65D6E8>) |
| 8086:3456 |           | Intel            | Ice Lake NorthPeak                   | 38    | intel_t... | [481D7F644B](<Server/Graviton/Server/Server/42D49089972B/ROSA-12.6/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/481D7F644B>) |
| 1022:14ac | 1022:14ac | AMD              | Genoa/Bergamo Dummy Function         | 17    |            | [E3AF2BABD8](<Server/Dell/PowerEdge/PowerEdge R6625/674A81CD0424/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/E3AF2BABD8>) |
| 1022:1485 | 1458:1000 | AMD              | Starship/Matisse Reserved SPP        | 14    |            | [5F638CAF1F](<Server/Gigabyte Technology/G292/G292-Z20-00/38987F4940DE/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/5F638CAF1F>) |
| 1022:148a | 1458:1000 | AMD              | Starship/Matisse PCIe Dummy Function | 14    |            | [5F638CAF1F](<Server/Gigabyte Technology/G292/G292-Z20-00/38987F4940DE/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/5F638CAF1F>) |
| 1022:1455 | 1022:1455 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 13    |            | [65D9CE4263](<Server/Supermicro/Super/Super Server/1BBC024DD007/DEBIAN-12/6.8.12-4-PVE/X86_64/65D9CE4263>) |
| 1022:145a | 1022:145a | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 13    |            | [65D9CE4263](<Server/Supermicro/Super/Super Server/1BBC024DD007/DEBIAN-12/6.8.12-4-PVE/X86_64/65D9CE4263>) |
| 8086:3456 | 1458:1000 | Intel            | Ice Lake NorthPeak                   | 12    |            | [F76FC4031D](<Server/PSSC Labs/SS4000/SS4000HD/13084E646FAA/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/F76FC4031D>) |
| 1022:1485 | 1028:08fc | AMD              | Starship/Matisse Reserved SPP        | 11    |            | [CE34F45F28](<Server/AWS Elemental/Appliance/Appliance/78AD1C73F775/UBUNTU-22.04/6.5.0-27-GENERIC/X86_64/CE34F45F28>) |
| 1022:148a | 1028:08fc | AMD              | Starship/Matisse PCIe Dummy Function | 11    |            | [CE34F45F28](<Server/AWS Elemental/Appliance/Appliance/78AD1C73F775/UBUNTU-22.04/6.5.0-27-GENERIC/X86_64/CE34F45F28>) |
| 1022:145a | 1458:1000 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 6     |            | [722F640CCD](<Server/Gigabyte Technology/MC12/MC12-LE0-00/37078BD0F3C1/UBUNTU-22.04/6.5.0-18-GENERIC/X86_64/722F640CCD>) |
| 1022:1485 | 1028:08ff | AMD              | Starship/Matisse Reserved SPP        | 6     |            | [77F946C99B](<Server/Dell/PowerEdge/PowerEdge R7525/ED52A1D54F9D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/77F946C99B>) |
| 1022:148a | 1028:08ff | AMD              | Starship/Matisse PCIe Dummy Function | 6     |            | [77F946C99B](<Server/Dell/PowerEdge/PowerEdge R7525/ED52A1D54F9D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/77F946C99B>) |
| 1022:1455 | 1458:1000 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 5     |            | [182255B026](<Server/Gigabyte Technology/G431/G431-MM0-OT/04B3B45439D3/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/182255B026>) |
| 1022:14ac | 1028:0af9 | AMD              | Genoa/Bergamo Dummy Function         | 5     |            | [F73AE91625](<Server/Dell/PowerEdge/PowerEdge R7625/85D8E20875A1/UBUNTU-20.04/5.4.0-156-GENERIC/X86_64/F73AE91625>) |
| 8086:a126 |           | Intel            | 100 Series/C230 Series Chipset Fa... | 5     | intel_t... | [F5115C8A74](<Server/HPE/ML10/ML10Gen9/5368299CD3DB/KUBUNTU-23.04/6.2.0-1007-LOWLATENCY/X86_64/F5115C8A74>) |
| 1022:1485 | 1028:08fd | AMD              | Starship/Matisse Reserved SPP        | 4     |            | [28E8ABBBDF](<Server/Dell/PowerEdge/PowerEdge R7515/8E207635BBF5/NIXOS-23.11/6.5.12/X86_64/28E8ABBBDF>) |
| 1022:148a | 1028:08fd | AMD              | Starship/Matisse PCIe Dummy Function | 4     |            | [28E8ABBBDF](<Server/Dell/PowerEdge/PowerEdge R7515/8E207635BBF5/NIXOS-23.11/6.5.12/X86_64/28E8ABBBDF>) |
| 1022:14ac | 1849:14ac | AMD              | Genoa/Bergamo Dummy Function         | 3     |            | [70D3A74444](<Server/ASRockRack/GENOAD12/GENOAD12M3-2Q-H/AF39B86BBAAF/UBUNTU-24.04/6.8.0-38-GENERIC/X86_64/70D3A74444>) |
| 1022:14de | 1002:164e | AMD              | Raphael/Granite Ridge PCIe Dummy ... | 3     |            | [F4A02ED514](<Server/MSI/MSIS/MSIS366/66AA7EB4825A/UBUNTU-20.04/5.15.0-124-GENERIC/X86_64/F4A02ED514>) |
| 1022:1455 | 1028:07f9 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 2     |            | [FD88331144](<Server/Dell/PowerEdge/PowerEdge R7425/1C2794FDE243/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/FD88331144>) |
| 1022:145a | 1028:07f9 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 2     |            | [FD88331144](<Server/Dell/PowerEdge/PowerEdge R7425/1C2794FDE243/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/FD88331144>) |
| 1022:14ac | 1028:0af6 | AMD              | Genoa/Bergamo Dummy Function         | 2     |            | [2DF42D8015](<Server/Dell/PowerEdge/PowerEdge R6615/A3D1D83B109B/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/2DF42D8015>) |
| 1022:14de | 1458:1000 | AMD              | Raphael/Granite Ridge PCIe Dummy ... | 2     |            | [1F2C7821A0](<Server/Giga Computing/MC13/MC13-LE1-000/338E31DACCCB/UBUNTU-22.04/5.15.0-91-GENERIC/X86_64/1F2C7821A0>) |
| 8086:3456 | 17aa:7811 | Intel            | Ice Lake NorthPeak                   | 2     |            | [29F89998EE](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 V2/D65FD98664FE/DEBIAN-11/5.10.0-20-AMD64/X86_64/29F89998EE>) |
| 8086:3456 | 1849:3456 | Intel            | Ice Lake NorthPeak                   | 2     |            | [E9C9A4C51A](<Server/INFERIT/RS224/RS224 R1G3D32RU/68DD4BB73C8C/ROSA-12F.1/6.1.58-GENERIC-5ROSA2021.15-X86_64/X86_64/E9C9A4C51A>) |
| 8086:3456 | 8086:7270 | Intel            | Ice Lake NorthPeak                   | 2     |            | [DEE94DD20E](<Server/Intel/WHITLEY/WHITLEY/4290A93BC0B0/UBUNTU-22.04/5.15.0-91-GENERIC/X86_64/DEE94DD20E>) |
| 1022:1485 | 1028:0900 | AMD              | Starship/Matisse Reserved SPP        | 1     |            | [382F999542](<Server/Dell/PowerEdge/PowerEdge C6525/B11FEC7694D8/ARCH/5.15.59-1-LTS/X86_64/382F999542>) |
| 1022:1485 | 1849:1485 | AMD              | Starship/Matisse Reserved SPP        | 1     |            | [3C11A0856C](<Server/ASRockRack/ROMED8/ROMED8-2T/9F9114A5632E/DEBIAN-10/5.8.0-0.BPO.2-AMD64/X86_64/3C11A0856C>) |
| 1022:148a | 1028:0900 | AMD              | Starship/Matisse PCIe Dummy Function | 1     |            | [382F999542](<Server/Dell/PowerEdge/PowerEdge C6525/B11FEC7694D8/ARCH/5.15.59-1-LTS/X86_64/382F999542>) |
| 1022:14ac | 1028:0af8 | AMD              | Genoa/Bergamo Dummy Function         | 1     |            | [E3AF2BABD8](<Server/Dell/PowerEdge/PowerEdge R6625/674A81CD0424/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/E3AF2BABD8>) |
| 8086:18e1 | 15d9:1c18 | Intel            | Atom Processor P5xxx Series Trace... | 1     | intel_t... | [3751D50DDE](<Server/Supermicro/Super/Super Server/ACFD57B232A4/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/3751D50DDE>) |
| 8086:18e1 | 15d9:1c4f | Intel            | Atom Processor P5xxx Series Trace... | 1     | intel_t... | [54A4E7C93E](<Server/Supermicro/Super/Super Server/E299F91C21A0/UBUNTU-20.04/5.15.0-73-GENERIC/X86_64/54A4E7C93E>) |
| 8086:18e1 | 8086:7270 | Intel            | Atom Processor P5xxx Series Trace... | 1     | intel_t... | [C618310D44](<Server/Dell/PowerEdge/PowerEdge XR4510c/35E133588594/DEBIAN-12/6.1.0-10-AMD64/X86_64/C618310D44>) |
| 8086:1bcc | 17aa:7830 | Intel            | C741 Series TH                       | 1     | intel_t... | [80A2F3D367](<Server/Lenovo/ThinkSystem/ThinkSystem SR950 V3/80C0A7FFD0E3/RHEL-9/5.14.0-70.22.1.EL9_0.X86_64/X86_64/80A2F3D367>) |
| 8086:1bcc | 8086:7270 | Intel            | C741 Series TH                       | 1     | intel_t... | [C2F51116FA](<Server/Quanta/QuantaGrid/QuantaGrid D54Q-2U/C47EF5FEC5BF/UBUNTU-22.04/5.15.0-70-GENERIC/X86_64/C2F51116FA>) |
| 8086:3456 | 17aa:7810 | Intel            | Ice Lake NorthPeak                   | 1     |            | [FF6113B91D](<Server/Lenovo/ThinkSystem/ThinkSystem SR630 V2/ECB5C724E79D/CENTOS-7/3.10.0-1160.49.1.EL7.X86_64/X86_64/FF6113B91D>) |
| 8086:3456 | 17aa:7812 | Intel            | Ice Lake NorthPeak                   | 1     |            | [ECD5A5BE36](<Server/Lenovo/ThinkSystem/ThinkSystem ST650 V2/038AE9A4AA3B/XUBUNTU-22.04/5.15.0-94-GENERIC/X86_64/ECD5A5BE36>) |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a135 | 15d9:089a | Intel            | 100 Series/C230 Series Chipset Fa... | 11    | intel_i... | [85E2DD189C](<Server/Supermicro/Super/Super Server/2FA87A9B8E2E/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/85E2DD189C>) |
| 8086:a135 | 15d9:0884 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     | intel_i... | [0840C7521E](<Server/OEM/PR2285/PR2285S1/E9EE5DAF6D75/DEBIAN-12/6.6.38-TRIM/X86_64/0840C7521E>) |
| 8086:a135 | 15d9:0896 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | intel_i... | [B0100C59BB](<Server/Supermicro/Super/Super Server/E58401D9CAE3/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/B0100C59BB>) |
| 1b94:c156 | 1b94:c156 | Signatec / Dy... |                                      | 1     |            | [B3C09674CF](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/31A946D98462/UBUNTU-18.04/4.15.0-142-GENERIC/X86_64/B3C09674CF>) |
| 8086:a135 | 15d9:0885 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | intel_i... | [50169A0FFB](<Server/Supermicro/Super/Super Server/866C451F74FD/LINUXMINT-20/5.4.0-26-GENERIC/X86_64/50169A0FFB>) |
| 8086:a2a4 |           | Intel            | 200 Series/Z370 Chipset Family SP... | 1     | spi_int... | [B77ECB9D84](<Server/Hewlett-Packard/ZCentral/ZCentral 4R Workstation/7FA6C6FE3813/UBUNTU-22.04/6.5.0-35-GENERIC/X86_64/B77ECB9D84>) |
| f002:0050 |           |                  |                                      | 1     |            | [6B39AA397F](<Server/TYAN Computer/S/S7020/6436C2C09FA9/FEDORA-38/6.3.5-200.FC38.X86_64/X86_64/6B39AA397F>) |

### Parallel controller (ecp) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1415:9513 | 1415:9513 | Oxford Semico... | OX16PCI954 (Quad 16950 UART) func... | 1     | parport_pc | [3B5585BEC8](<Server/Supermicro/X9/X9SRA-X9SRA-3/E73ED86A7227/DEBIAN-11/5.10.0-33-AMD64/X86_64/3B5585BEC8>) |
| 1415:c110 | 1415:c110 | Oxford Semico... | OXPCIe952 Parallel Port              | 1     | parport_pc | [1CECE2A441](<Server/Supermicro/C7/C7H170-M/40203ADD6246/FEDORA-40/6.10.12-200.FC40.X86_64/X86_64/1CECE2A441>) |

### Parallel controller (ieee1284) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 9710:9865 | a000:2000 | MosChip Semic... | PCI 9865 Multi-I/O Controller        | 1     | parport_pc | [715B40D8B6](<Server/Intel/S5000/S5000XVN/187007C30239/FEDORA-34/5.14.12-200.FC34.X86_64/X86_64/715B40D8B6>) |

### Performance counters (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:204c | 8086:0000 | Intel            | Sky Lake-E M3KTI Registers           | 299   | skx_uncore | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:204d | 8086:0000 | Intel            | Sky Lake-E M3KTI Registers           | 299   | skx_uncore | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2015 | 8086:0000 | Intel            | Sky Lake-E Ubox Registers            | 298   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2058 | 8086:0000 | Intel            | Sky Lake-E KTI 0                     | 286   | skx_uncore | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2088 | 8086:0000 | Intel            | Sky Lake-E DDRIO Registers           | 175   | skx_uncore | [01602FD84E](<Server/Supermicro/SYS-6019/SYS-6019P-WTR/0C2A376E8BE8/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/01602FD84E>) |
| 8086:6f30 | 8086:6f30 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 101   | bdx_uncore | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6f34 | 8086:6f34 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 101   | bdx_uncore | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6f36 | 8086:6f36 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 101   | bdx_uncore | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6f37 | 8086:6f37 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 101   | bdx_uncore | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6f7d | 8086:6f7d | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 101   |            | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:2f30 | 8086:2f30 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 94    | hswep_u... | [22CE816D89](<Server/Dell/PowerEdge/PowerEdge R630/D53C4C379040/ALMA-9.4/5.14.0-427.31.1.EL9_4.X86_64/X86_64/22CE816D89>) |
| 8086:2f34 | 8086:2f34 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 PCI... | 94    | hswep_u... | [22CE816D89](<Server/Dell/PowerEdge/PowerEdge R630/D53C4C379040/ALMA-9.4/5.14.0-427.31.1.EL9_4.X86_64/X86_64/22CE816D89>) |
| 8086:2f36 | 8086:2f36 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 94    | hswep_u... | [22CE816D89](<Server/Dell/PowerEdge/PowerEdge R630/D53C4C379040/ALMA-9.4/5.14.0-427.31.1.EL9_4.X86_64/X86_64/22CE816D89>) |
| 8086:2f37 | 8086:2f37 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 94    | hswep_u... | [22CE816D89](<Server/Dell/PowerEdge/PowerEdge R630/D53C4C379040/ALMA-9.4/5.14.0-427.31.1.EL9_4.X86_64/X86_64/22CE816D89>) |
| 8086:2f7d | 8086:2f7d | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 94    |            | [22CE816D89](<Server/Dell/PowerEdge/PowerEdge R630/D53C4C379040/ALMA-9.4/5.14.0-427.31.1.EL9_4.X86_64/X86_64/22CE816D89>) |
| 8086:2058 |           | Intel            | Sky Lake-E KTI 0                     | 78    | skx_uncore | [BE48E1A4CD](<Server/HPE/ProLiant/ProLiant DL380 Gen10/4A81CFAB7E9A/UBUNTU-20.04/5.15.0-127-GENERIC/X86_64/BE48E1A4CD>) |
| 8086:6f30 | 103c:21ea | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 70    | bdx_uncore | [34E5B43715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/07607C1620F7/DEBIAN-12/6.8.8-4-PVE/X86_64/34E5B43715>) |
| 8086:6f34 | 103c:21ea | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 70    | bdx_uncore | [34E5B43715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/07607C1620F7/DEBIAN-12/6.8.8-4-PVE/X86_64/34E5B43715>) |
| 8086:6f36 | 103c:21ea | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 70    | bdx_uncore | [34E5B43715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/07607C1620F7/DEBIAN-12/6.8.8-4-PVE/X86_64/34E5B43715>) |
| 8086:6f37 | 103c:21ea | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 70    | bdx_uncore | [34E5B43715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/07607C1620F7/DEBIAN-12/6.8.8-4-PVE/X86_64/34E5B43715>) |
| 8086:6f7d | 103c:21ea | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 70    |            | [34E5B43715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/07607C1620F7/DEBIAN-12/6.8.8-4-PVE/X86_64/34E5B43715>) |
| 8086:2f32 | 8086:2f32 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 QPI... | 65    | hswep_u... | [22CE816D89](<Server/Dell/PowerEdge/PowerEdge R630/D53C4C379040/ALMA-9.4/5.14.0-427.31.1.EL9_4.X86_64/X86_64/22CE816D89>) |
| 8086:6f32 | 8086:6f32 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 62    | bdx_uncore | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6f33 | 8086:6f33 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 62    | bdx_uncore | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:2f33 | 8086:2f33 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 QPI... | 61    | hswep_u... | [22CE816D89](<Server/Dell/PowerEdge/PowerEdge R630/D53C4C379040/ALMA-9.4/5.14.0-427.31.1.EL9_4.X86_64/X86_64/22CE816D89>) |
| 8086:3c43 | 103c:18a8 | Intel            | Xeon E5/Core i7 Ring to PCI Expre... | 61    | snbep_u... | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |
| 8086:3c44 | 103c:18a8 | Intel            | Xeon E5/Core i7 Ring to QuickPath... | 61    | snbep_u... | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |
| 8086:3c46 | 103c:18a8 | Intel            | Xeon E5/Core i7 Processor Home Ag... | 61    | snbep_u... | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |
| 8086:3ce6 | 103c:18a8 | Intel            | Xeon E5/Core i7 QuickPath Interco... | 61    |            | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |
| 8086:2880 | 8086:0000 | Intel            | Core i9/Xeon DDRIO Host Config Re... | 57    |            | [481D7F644B](<Server/Graviton/Server/Server/42D49089972B/ROSA-12.6/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/481D7F644B>) |
| 8086:6f38 | 8086:6f38 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 41    | bdx_uncore | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:0e30 | 103c:18a8 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 38    | ivbep_u... | [62172231BE](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/A6B377D0F4D1/DEBIAN-12/6.8.8-2-PVE/X86_64/62172231BE>) |
| 8086:0e34 | 103c:18a8 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 38    | ivbep_u... | [62172231BE](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/A6B377D0F4D1/DEBIAN-12/6.8.8-2-PVE/X86_64/62172231BE>) |
| 8086:0e36 | 103c:18a8 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 38    | ivbep_u... | [62172231BE](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/A6B377D0F4D1/DEBIAN-12/6.8.8-2-PVE/X86_64/62172231BE>) |
| 8086:344a | 8086:0000 | Intel            | Core i9/Xeon IMC0 Mesh to Mem Reg... | 38    | icx_uncore | [481D7F644B](<Server/Graviton/Server/Server/42D49089972B/ROSA-12.6/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/481D7F644B>) |
| 8086:0e30 | 15d9:0636 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 36    | ivbep_u... | [86B4E152AD](<Server/Supermicro/X9/X9DRW/D2C6B0237967/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/86B4E152AD>) |
| 8086:0e34 | 15d9:0636 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 36    | ivbep_u... | [86B4E152AD](<Server/Supermicro/X9/X9DRW/D2C6B0237967/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/86B4E152AD>) |
| 8086:0e36 | 15d9:0636 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 36    | ivbep_u... | [86B4E152AD](<Server/Supermicro/X9/X9DRW/D2C6B0237967/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/86B4E152AD>) |
| 8086:6f38 | 103c:21ea | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 36    | bdx_uncore | [6E4FB0D4B2](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/3DAA87FAC48E/DEBIAN-12/6.1.0-26-AMD64/X86_64/6E4FB0D4B2>) |
| 8086:2f38 | 8086:2f38 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 35    | hswep_u... | [22CE816D89](<Server/Dell/PowerEdge/PowerEdge R630/D53C4C379040/ALMA-9.4/5.14.0-427.31.1.EL9_4.X86_64/X86_64/22CE816D89>) |
| 8086:2f30 | 103c:21ea | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 33    | hswep_u... | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:2f34 | 103c:21ea | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 PCI... | 33    | hswep_u... | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:2f36 | 103c:21ea | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 33    | hswep_u... | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:2f37 | 103c:21ea | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 33    | hswep_u... | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:2f7d | 103c:21ea | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 33    |            | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:0e30 | 152d:899b | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 25    | ivbep_u... | [7E09CCDA22](<Server/ETegro Technologies/Hyperion/Hyperion RS125 G4/5259A72AB62F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/7E09CCDA22>) |
| 8086:0e34 | 152d:899b | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 25    | ivbep_u... | [7E09CCDA22](<Server/ETegro Technologies/Hyperion/Hyperion RS125 G4/5259A72AB62F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/7E09CCDA22>) |
| 8086:0e36 | 152d:899b | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 25    | ivbep_u... | [7E09CCDA22](<Server/ETegro Technologies/Hyperion/Hyperion RS125 G4/5259A72AB62F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/7E09CCDA22>) |
| 8086:2015 | 1590:00ea | Intel            | Sky Lake-E Ubox Registers            | 21    |            | [D9F97B2071](<Server/HPE/ProLiant/ProLiant DL380 Gen10/6D60567E7E8D/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/D9F97B2071>) |
| 8086:204c | 1590:00ea | Intel            | Sky Lake-E M3KTI Registers           | 21    | skx_uncore | [D9F97B2071](<Server/HPE/ProLiant/ProLiant DL380 Gen10/6D60567E7E8D/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/D9F97B2071>) |

### Pic (8259) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:342e |           | Intel            | 7500/5520/5500/X58 I/O Hub System... | 333   | i7core_... | [6918605D42](<Server/Supermicro/X8/X8DTU/2EC017791B11/DEBIAN-12/6.8.12-5-PVE/X86_64/6918605D42>) |
| 8086:3422 |           | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 330   |            | [6918605D42](<Server/Supermicro/X8/X8DTU/2EC017791B11/DEBIAN-12/6.8.12-5-PVE/X86_64/6918605D42>) |
| 8086:3423 |           | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 330   |            | [6918605D42](<Server/Supermicro/X8/X8DTU/2EC017791B11/DEBIAN-12/6.8.12-5-PVE/X86_64/6918605D42>) |
| 8086:3438 |           | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 190   | i5500_temp | [6918605D42](<Server/Supermicro/X8/X8DTU/2EC017791B11/DEBIAN-12/6.8.12-5-PVE/X86_64/6918605D42>) |
| 8086:3422 | 003c:000b | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 78    |            | [B076CBF109](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/416C8912B3CC/DEBIAN/6.11.10-AMD64/X86_64/B076CBF109>) |
| 8086:3423 | 003c:000b | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 78    |            | [B076CBF109](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/416C8912B3CC/DEBIAN/6.11.10-AMD64/X86_64/B076CBF109>) |
| 8086:342e | 003c:000b | Intel            | 7500/5520/5500/X58 I/O Hub System... | 78    | i7core_... | [B076CBF109](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/416C8912B3CC/DEBIAN/6.11.10-AMD64/X86_64/B076CBF109>) |
| 8086:3425 |           | Intel            | 7500/5520/5500/X58 Physical and L... | 24    |            | [3286B36B51](<Server/IBM/System/System x3650 M3 -[7945YBU]-/64198599779C/DEBIAN-12/6.8.12-1-PVE/X86_64/3286B36B51>) |
| 8086:3426 |           | Intel            | 7500/5520/5500/X58 Routing and Pr... | 24    |            | [3286B36B51](<Server/IBM/System/System x3650 M3 -[7945YBU]-/64198599779C/DEBIAN-12/6.8.12-1-PVE/X86_64/3286B36B51>) |
| 8086:3427 |           | Intel            | 7500/5520/5500 Physical and Link ... | 24    |            | [3286B36B51](<Server/IBM/System/System x3650 M3 -[7945YBU]-/64198599779C/DEBIAN-12/6.8.12-1-PVE/X86_64/3286B36B51>) |
| 8086:3428 |           | Intel            | 7500/5520/5500 Routing & Protocol... | 24    |            | [3286B36B51](<Server/IBM/System/System x3650 M3 -[7945YBU]-/64198599779C/DEBIAN-12/6.8.12-1-PVE/X86_64/3286B36B51>) |
| 8086:3422 | 0086:00dc | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 14    |            | [BD871B1C6F](<Server/Intel/S5520/S5520HC/256D70541E78/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/BD871B1C6F>) |
| 8086:3423 | 0086:00dc | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 14    |            | [BD871B1C6F](<Server/Intel/S5520/S5520HC/256D70541E78/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/BD871B1C6F>) |
| 8086:3425 | 0086:00dc | Intel            | 7500/5520/5500/X58 Physical and L... | 14    |            | [BD871B1C6F](<Server/Intel/S5520/S5520HC/256D70541E78/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/BD871B1C6F>) |
| 8086:3426 | 0086:00dc | Intel            | 7500/5520/5500/X58 Routing and Pr... | 14    |            | [BD871B1C6F](<Server/Intel/S5520/S5520HC/256D70541E78/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/BD871B1C6F>) |
| 8086:3427 | 0086:00dc | Intel            | 7500/5520/5500 Physical and Link ... | 14    |            | [BD871B1C6F](<Server/Intel/S5520/S5520HC/256D70541E78/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/BD871B1C6F>) |
| 8086:3428 | 0086:00dc | Intel            | 7500/5520/5500 Routing & Protocol... | 14    |            | [BD871B1C6F](<Server/Intel/S5520/S5520HC/256D70541E78/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/BD871B1C6F>) |
| 8086:342e | 0086:00dc | Intel            | 7500/5520/5500/X58 I/O Hub System... | 14    | i7core_... | [BD871B1C6F](<Server/Intel/S5520/S5520HC/256D70541E78/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/BD871B1C6F>) |
| 8086:3438 | 0086:00dc | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 14    | i5500_temp | [BD871B1C6F](<Server/Intel/S5520/S5520HC/256D70541E78/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/BD871B1C6F>) |
| 8086:3422 | 0034:0027 | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 9     |            | [DF81B53B94](<Server/Fujitsu/PRIMERGY/PRIMERGY TX300 S5/C75C8D396A0B/DEBIAN-11/5.15.158-2-PVE/X86_64/DF81B53B94>) |
| 8086:3423 | 0034:0027 | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 9     |            | [DF81B53B94](<Server/Fujitsu/PRIMERGY/PRIMERGY TX300 S5/C75C8D396A0B/DEBIAN-11/5.15.158-2-PVE/X86_64/DF81B53B94>) |
| 8086:3425 | 0034:0027 | Intel            | 7500/5520/5500/X58 Physical and L... | 9     |            | [DF81B53B94](<Server/Fujitsu/PRIMERGY/PRIMERGY TX300 S5/C75C8D396A0B/DEBIAN-11/5.15.158-2-PVE/X86_64/DF81B53B94>) |
| 8086:3426 | 0034:0027 | Intel            | 7500/5520/5500/X58 Routing and Pr... | 9     |            | [DF81B53B94](<Server/Fujitsu/PRIMERGY/PRIMERGY TX300 S5/C75C8D396A0B/DEBIAN-11/5.15.158-2-PVE/X86_64/DF81B53B94>) |
| 8086:3427 | 0034:0027 | Intel            | 7500/5520/5500 Physical and Link ... | 9     |            | [DF81B53B94](<Server/Fujitsu/PRIMERGY/PRIMERGY TX300 S5/C75C8D396A0B/DEBIAN-11/5.15.158-2-PVE/X86_64/DF81B53B94>) |
| 8086:3428 | 0034:0027 | Intel            | 7500/5520/5500 Routing & Protocol... | 9     |            | [DF81B53B94](<Server/Fujitsu/PRIMERGY/PRIMERGY TX300 S5/C75C8D396A0B/DEBIAN-11/5.15.158-2-PVE/X86_64/DF81B53B94>) |
| 8086:342e | 0034:0027 | Intel            | 7500/5520/5500/X58 I/O Hub System... | 9     | i7core_... | [DF81B53B94](<Server/Fujitsu/PRIMERGY/PRIMERGY TX300 S5/C75C8D396A0B/DEBIAN-11/5.15.158-2-PVE/X86_64/DF81B53B94>) |
| 8086:3438 | 0034:0027 | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 9     | i5500_temp | [DF81B53B94](<Server/Fujitsu/PRIMERGY/PRIMERGY TX300 S5/C75C8D396A0B/DEBIAN-11/5.15.158-2-PVE/X86_64/DF81B53B94>) |
| 8086:3422 | 0086:00da | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 7     |            | [D7D5249BC9](<Server/Intel/S5500/S5500BC/49891E2271E6/UBUNTU-22.04/6.2.0-31-GENERIC/X86_64/D7D5249BC9>) |
| 8086:3423 | 0086:00da | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 7     |            | [D7D5249BC9](<Server/Intel/S5500/S5500BC/49891E2271E6/UBUNTU-22.04/6.2.0-31-GENERIC/X86_64/D7D5249BC9>) |
| 8086:3425 | 0086:00da | Intel            | 7500/5520/5500/X58 Physical and L... | 7     |            | [D7D5249BC9](<Server/Intel/S5500/S5500BC/49891E2271E6/UBUNTU-22.04/6.2.0-31-GENERIC/X86_64/D7D5249BC9>) |
| 8086:3426 | 0086:00da | Intel            | 7500/5520/5500/X58 Routing and Pr... | 7     |            | [D7D5249BC9](<Server/Intel/S5500/S5500BC/49891E2271E6/UBUNTU-22.04/6.2.0-31-GENERIC/X86_64/D7D5249BC9>) |
| 8086:3427 | 0086:00da | Intel            | 7500/5520/5500 Physical and Link ... | 7     |            | [D7D5249BC9](<Server/Intel/S5500/S5500BC/49891E2271E6/UBUNTU-22.04/6.2.0-31-GENERIC/X86_64/D7D5249BC9>) |
| 8086:3428 | 0086:00da | Intel            | 7500/5520/5500 Routing & Protocol... | 7     |            | [D7D5249BC9](<Server/Intel/S5500/S5500BC/49891E2271E6/UBUNTU-22.04/6.2.0-31-GENERIC/X86_64/D7D5249BC9>) |
| 8086:342e | 0086:00da | Intel            | 7500/5520/5500/X58 I/O Hub System... | 7     | i7core_... | [D7D5249BC9](<Server/Intel/S5500/S5500BC/49891E2271E6/UBUNTU-22.04/6.2.0-31-GENERIC/X86_64/D7D5249BC9>) |
| 8086:3438 | 0086:00da | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 7     | i5500_temp | [D7D5249BC9](<Server/Intel/S5500/S5500BC/49891E2271E6/UBUNTU-22.04/6.2.0-31-GENERIC/X86_64/D7D5249BC9>) |
| 8086:3422 | 0086:00e2 | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3423 | 0086:00e2 | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3425 | 0086:00e2 | Intel            | 7500/5520/5500/X58 Physical and L... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3426 | 0086:00e2 | Intel            | 7500/5520/5500/X58 Routing and Pr... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3427 | 0086:00e2 | Intel            | 7500/5520/5500 Physical and Link ... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3428 | 0086:00e2 | Intel            | 7500/5520/5500 Routing & Protocol... | 5     |            | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:342e | 0086:00e2 | Intel            | 7500/5520/5500/X58 I/O Hub System... | 5     | i7core_... | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3438 | 0086:00e2 | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 5     | i5500_temp | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3422 | 0086:00de | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 4     |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:3423 | 0086:00de | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 4     |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:3425 | 0086:00de | Intel            | 7500/5520/5500/X58 Physical and L... | 4     |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:3426 | 0086:00de | Intel            | 7500/5520/5500/X58 Routing and Pr... | 4     |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:3427 | 0086:00de | Intel            | 7500/5520/5500 Physical and Link ... | 4     |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:3428 | 0086:00de | Intel            | 7500/5520/5500 Routing & Protocol... | 4     |            | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |
| 8086:342e | 0086:00de | Intel            | 7500/5520/5500/X58 I/O Hub System... | 4     | i7core_... | [E32D8048DD](<Server/Intel/S5520/S5520UR/8A034FDC2020/DEBIAN-11/5.15.158-2-PVE/X86_64/E32D8048DD>) |

### Pic (io(x)-apic) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2026 | 8086:2026 | Intel            | Sky Lake-E IOAPIC                    | 297   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2036 | 8086:2036 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 297   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:342d |           | Intel            | 7500/5520/5500/X58 I/O Hub I/OxAP... | 151   |            | [B66E4C113A](<Server/DEPO Computers/X8/X8DTU/732C5C269461/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/B66E4C113A>) |
| 8086:2f2c | 8086:0000 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 76    |            | [22CE816D89](<Server/Dell/PowerEdge/PowerEdge R630/D53C4C379040/ALMA-9.4/5.14.0-427.31.1.EL9_4.X86_64/X86_64/22CE816D89>) |
| 8086:6f2c | 8086:0000 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 72    |            | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6f2c | 103c:21ea | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 70    |            | [34E5B43715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/07607C1620F7/DEBIAN-12/6.8.8-4-PVE/X86_64/34E5B43715>) |
| 8086:3c2c | 103c:18a8 | Intel            | Xeon E5/Core i7 I/O APIC             | 65    |            | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |
| 8086:0e2c | 103c:18a8 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 38    |            | [62172231BE](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/A6B377D0F4D1/DEBIAN-12/6.8.8-2-PVE/X86_64/62172231BE>) |
| 8086:0e2c | 15d9:0636 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 36    |            | [86B4E152AD](<Server/Supermicro/X9/X9DRW/D2C6B0237967/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/86B4E152AD>) |
| 8086:2f2c | 103c:21ea | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 33    |            | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:0e2c | 152d:899b | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 25    |            | [7E09CCDA22](<Server/ETegro Technologies/Hyperion/Hyperion RS125 G4/5259A72AB62F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/7E09CCDA22>) |
| 8086:2026 | 1590:18a9 | Intel            | Sky Lake-E IOAPIC                    | 21    |            | [D9F97B2071](<Server/HPE/ProLiant/ProLiant DL380 Gen10/6D60567E7E8D/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/D9F97B2071>) |
| 8086:2036 | 1590:18a9 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 21    |            | [D9F97B2071](<Server/HPE/ProLiant/ProLiant DL380 Gen10/6D60567E7E8D/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/D9F97B2071>) |
| 8086:342f |           | Intel            | 7500/5520/5500/X58 Trusted Execut... | 18    |            | [3286B36B51](<Server/IBM/System/System x3650 M3 -[7945YBU]-/64198599779C/DEBIAN-12/6.8.12-1-PVE/X86_64/3286B36B51>) |
| 8086:6f2c | 15d9:0821 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 18    |            | [34DDE21779](<Server/transtec/CALLEO/CALLEO/ABD07D26A4AA/RHCOS-4.16/5.14.0-427.24.1.EL9_4.X86_64/X86_64/34DDE21779>) |
| 8086:0e2c | 1043:84f0 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 17    |            | [E805BE0AAC](<Server/Kraftway/GEG/GEG/C4E325834440/DEBIAN-12/6.1.0-27-AMD64/X86_64/E805BE0AAC>) |
| 8086:2026 | 8086:0000 | Intel            | Sky Lake-E IOAPIC                    | 16    |            | [21781753FB](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/4E03B443521E/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/21781753FB>) |
| 8086:2036 | 8086:0000 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 16    |            | [21781753FB](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/4E03B443521E/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/21781753FB>) |
| 8086:342d | 0086:00dc | Intel            | 7500/5520/5500/X58 I/O Hub I/OxAP... | 14    |            | [BD871B1C6F](<Server/Intel/S5520/S5520HC/256D70541E78/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/BD871B1C6F>) |
| 8086:342f | 0086:00dc | Intel            | 7500/5520/5500/X58 Trusted Execut... | 14    |            | [BD871B1C6F](<Server/Intel/S5520/S5520HC/256D70541E78/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/BD871B1C6F>) |
| 8086:2026 | 17aa:1038 | Intel            | Sky Lake-E IOAPIC                    | 13    |            | [CAFAEE2FC7](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC000QGE/C9B0658BA91C/DEBIAN-12/6.1.0-28-AMD64/X86_64/CAFAEE2FC7>) |
| 8086:2036 | 17aa:1038 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 13    |            | [CAFAEE2FC7](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC000QGE/C9B0658BA91C/DEBIAN-12/6.1.0-28-AMD64/X86_64/CAFAEE2FC7>) |
| 8086:3c2c | 15d9:0626 | Intel            | Xeon E5/Core i7 I/O APIC             | 12    |            | [39232DFDE3](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/B0C1ED30C610/DEBIAN-12/6.1.0-25-AMD64/X86_64/39232DFDE3>) |
| 8086:3c2c | 15d9:0636 | Intel            | Xeon E5/Core i7 I/O APIC             | 12    |            | [BEE961D2C4](<Server/Supermicro/X9/X9DRW/FCB6DBF7633A/UBUNTU-22.04/5.15.0-107-GENERIC/X86_64/BEE961D2C4>) |
| 8086:6f2c | 19e5:2062 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 12    |            | [EDA2D8550F](<Server/HUAWEI/RH1288/RH1288 V3/899B0DE1B12F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/EDA2D8550F>) |
| 8086:3c2c | 1043:84f0 | Intel            | Xeon E5/Core i7 I/O APIC             | 11    |            | [7955C56C67](<Server/ASUSTek Computer/ESC4000/ESC4000 G2 Series/75FA7A6A974C/OPENSUSE-LEAP-15.5/5.14.21-150500.55.44-DEFAULT/X86_64/7955C56C67>) |
| 8086:6f2c | 15d9:0844 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 11    |            | [D24D2612FE](<Server/Supermicro/Super/Super Server/F4A31F1B8877/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/D24D2612FE>) |
| 8086:2026 | 1849:2026 | Intel            | Sky Lake-E IOAPIC                    | 10    |            | [7C5F635356](<Server/3Logic Group/Server/Server Graviton/339E3377D714/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/7C5F635356>) |
| 8086:2036 | 1849:2036 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 10    |            | [7C5F635356](<Server/3Logic Group/Server/Server Graviton/339E3377D714/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/7C5F635356>) |
| 8086:2f2c | 15d9:0857 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 10    |            | [87045C1939](<Server/Supermicro/X10/X10SRA/D3E806C3F6B3/DEBIAN-12/6.1.0-13-AMD64/X86_64/87045C1939>) |
| 8086:2026 | 17aa:7808 | Intel            | Sky Lake-E IOAPIC                    | 9     |            | [424E70419E](<Server/Lenovo/ThinkSystem/ThinkSystem SR570 -[7Y03CTO1WW]-/D3469A41F07A/XUBUNTU-18.04/4.15.0-213-GENERIC/X86_64/424E70419E>) |
| 8086:2036 | 17aa:7808 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 9     |            | [424E70419E](<Server/Lenovo/ThinkSystem/ThinkSystem SR570 -[7Y03CTO1WW]-/D3469A41F07A/XUBUNTU-18.04/4.15.0-213-GENERIC/X86_64/424E70419E>) |
| 8086:342f | 0034:0027 | Intel            | 7500/5520/5500/X58 Trusted Execut... | 9     |            | [DF81B53B94](<Server/Fujitsu/PRIMERGY/PRIMERGY TX300 S5/C75C8D396A0B/DEBIAN-11/5.15.158-2-PVE/X86_64/DF81B53B94>) |
| 8086:0e2c | 15d9:062b | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 8     |            | [F3D2F362E8](<Server/Supermicro/X9/X9SRE-X9SRE-3F-X9SRi-X9SRi-3F/55A635F4E92C/DEBIAN-12/6.8.8-2-PVE/X86_64/F3D2F362E8>) |
| 8086:2026 | 17aa:1037 | Intel            | Sky Lake-E IOAPIC                    | 8     |            | [301BFF683B](<Server/Lenovo/ThinkStation/ThinkStation P720 30BBS3H50D/215583F782C1/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.10.4-1-DEFAULT/X86_64/301BFF683B>) |
| 8086:2036 | 17aa:1037 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 8     |            | [301BFF683B](<Server/Lenovo/ThinkStation/ThinkStation P720 30BBS3H50D/215583F782C1/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.10.4-1-DEFAULT/X86_64/301BFF683B>) |
| 8086:2f2c | 15d9:0831 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 I/O... | 8     |            | [33E788CB66](<Server/Supermicro/Super/Super Server/3066F1E958A7/ROCKY-8.8/4.18.0-477.13.1.EL8_8.X86_64/X86_64/33E788CB66>) |
| 8086:342d | 0086:00da | Intel            | 7500/5520/5500/X58 I/O Hub I/OxAP... | 7     |            | [D7D5249BC9](<Server/Intel/S5500/S5500BC/49891E2271E6/UBUNTU-22.04/6.2.0-31-GENERIC/X86_64/D7D5249BC9>) |
| 8086:342f | 0086:00da | Intel            | 7500/5520/5500/X58 Trusted Execut... | 7     |            | [D7D5249BC9](<Server/Intel/S5500/S5500BC/49891E2271E6/UBUNTU-22.04/6.2.0-31-GENERIC/X86_64/D7D5249BC9>) |
| 8086:6f2c | 15d9:0834 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 7     |            | [E343AB03F0](<Server/DEPO Computers/Super/Super Server/B1C00A465F68/DEBIAN-12/6.8.8-2-PVE/X86_64/E343AB03F0>) |
| 8086:2026 | 17aa:7800 | Intel            | Sky Lake-E IOAPIC                    | 6     |            | [47FE0DACDD](<Server/Lenovo/ThinkSystem/ThinkSystem SR630 -[7X02CTO1WW]/74C1AF03C5E9/LINUXMINT-20.3/5.4.0-144-GENERIC/X86_64/47FE0DACDD>) |
| 8086:2026 | 17aa:7801 | Intel            | Sky Lake-E IOAPIC                    | 6     |            | [BAFB634A37](<Server/Lenovo/ThinkSystem/ThinkSystem SR530 -[7X08CTO1WW]-/16717DADAA79/CENTOS-7/3.10.0-1160.36.2.EL7.X86_64/X86_64/BAFB634A37>) |
| 8086:2026 | 8086:35ce | Intel            | Sky Lake-E IOAPIC                    | 6     |            | [781F43495A](<Server/Intel/S2600/S2600WFT/B54D5A70237A/RED-OS-7.3.2/5.15.87-1.EL7.3.X86_64/X86_64/781F43495A>) |
| 8086:2036 | 17aa:7800 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 6     |            | [47FE0DACDD](<Server/Lenovo/ThinkSystem/ThinkSystem SR630 -[7X02CTO1WW]/74C1AF03C5E9/LINUXMINT-20.3/5.4.0-144-GENERIC/X86_64/47FE0DACDD>) |
| 8086:2036 | 17aa:7801 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 6     |            | [BAFB634A37](<Server/Lenovo/ThinkSystem/ThinkSystem SR530 -[7X08CTO1WW]-/16717DADAA79/CENTOS-7/3.10.0-1160.36.2.EL7.X86_64/X86_64/BAFB634A37>) |
| 8086:6f2c | 15d9:0831 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 6     |            | [2BAD48B8D4](<Server/Silicon Mechanics/Rackform/Rackform R309.v5/8442C8D36737/DEBIAN-12/6.1.0-21-AMD64/X86_64/2BAD48B8D4>) |
| 8086:0e2c | 15d9:062a | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 5     |            | [3B5585BEC8](<Server/Supermicro/X9/X9SRA-X9SRA-3/E73ED86A7227/DEBIAN-11/5.10.0-33-AMD64/X86_64/3B5585BEC8>) |
| 8086:0e2c | 1734:11f8 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 5     |            | [ED6A47B6F9](<Server/Fujitsu/PRIMERGY/PRIMERGY TX2540 M1/6D63F93EE5A2/DEBIAN-12/6.11.10+BPO-AMD64/X86_64/ED6A47B6F9>) |
| 8086:0e2c | 8086:35a0 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 IOAPIC | 5     |            | [5FBA63C085](<Server/Intel/S4600/S4600LH/902A1E31749C/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/5FBA63C085>) |
| 8086:2026 | 1458:1000 | Intel            | Sky Lake-E IOAPIC                    | 5     |            | [11E2B42F72](<Server/Gigabyte Technology/MD61/MD61-SC2-00/9CA6F80BADD9/UBUNTU-23.10/6.5.0-26-GENERIC/X86_64/11E2B42F72>) |

### Pic (io-apic) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:7451 | 1022:7451 | AMD              | AMD-8131 PCI-X IOAPIC                | 1     |            | [18B25AC51A](<Server/TYAN Computer/S/S4882/84BBA0EA52AC/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/18B25AC51A>) |
| 1022:7451 | 10f1:2895 | AMD              | AMD-8131 PCI-X IOAPIC                | 1     |            | [768571B831](<Server/TYAN Computer/S/S2895/4B5DFCDB09B6/LINUXMINT-20/5.4.0-58-GENERIC/X86_64/768571B831>) |

### Processing accelerators (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1db7:dc24 |           | Phytium Techn... | NPU Controller [X100 Series]         | 3     |            | [497220C5DD](<Server/Phytium/D/D2000/E78D0AE566AE/ATZ-11.6/5.10.0-20-ARM64/AARCH64/497220C5DD>) |
| 10ee:5000 | 10ee:000e | Xilinx           | Alveo U200 XDMA Platform             | 2     |            | [AE0B8A9E36](<Server/ASUSTek Computer/WS-C621E-SAGE/WS-C621E-SAGE Series/E269F7C9BB0F/UBUNTU-22.04/5.19.0-50-GENERIC/X86_64/AE0B8A9E36>) |
| 10ee:5001 | 10ee:000e | Xilinx           | Processing accelerators              | 2     |            | [AE0B8A9E36](<Server/ASUSTek Computer/WS-C621E-SAGE/WS-C621E-SAGE Series/E269F7C9BB0F/UBUNTU-22.04/5.19.0-50-GENERIC/X86_64/AE0B8A9E36>) |
| 8086:09c4 | 8086:0000 | Intel            | PAC with Intel Arria 10 GX FPGA      | 1     | dfl_pci    | [3A917876BA](<Server/Dell/PowerEdge/PowerEdge R740/388DE5F0FB73/UBUNTU-20.04/5.4.0-132-GENERIC/X86_64/3A917876BA>) |
| 8086:0d5c | 8086:0000 | Intel            | Processing accelerators              | 1     |            | [D617CC1B4B](<Server/HOU/Whitestone-A/Whitestone-A PVT 5262C5330051/5CE342FC93F6/UBUNTU-22.04/5.15.0-122-GENERIC/X86_64/D617CC1B4B>) |
| 8086:7d1d | 8086:7270 | Intel            | Meteor Lake NPU                      | 1     |            | [43E67C9439](<Server/Intel/Meteor/Meteor Lake Client Platform/83A3F13660D9/UBUNTU-20.04/5.15.0-100-GENERIC/X86_64/43E67C9439>) |

### Processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1db7:dc20 | 0000:1701 | Phytium Techn... | [X100 Series]                        | 2     | pvrsrvkm   | [497220C5DD](<Server/Phytium/D/D2000/E78D0AE566AE/ATZ-11.6/5.10.0-20-ARM64/AARCH64/497220C5DD>) |
| 1db7:dc20 | 0000:1509 | Phytium Techn... | [X100 Series]                        | 1     | pvrsrvkm   | [7E0BE651B1](<Server/Phytium/D/D2000/17EC7603AC2B/UOS-20/4.19.0-ARM64-DESKTOP/AARCH64/7E0BE651B1>) |

### Rf controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ee:9038 | 10ee:0007 | Xilinx           | RF controller                        | 1     | sdr        | [D617CC1B4B](<Server/HOU/Whitestone-A/Whitestone-A PVT 5262C5330051/5CE342FC93F6/UBUNTU-22.04/5.15.0-122-GENERIC/X86_64/D617CC1B4B>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1217:8520 | 1f55:0000 | O2 Micro         | SD/MMC Card Reader Controller        | 13    | sdhci_pci  | [DF42F11E59](<Server/GEEKOM/GT13/GT13 Pro/EF7C9F2D8B32/LINUXMINT-22/6.8.0-48-GENERIC/X86_64/DF42F11E59>) |
| 8086:31cc | 1019:a94d | Intel            | Celeron/Pentium Silver Processor ... | 3     | sdhci_pci  | [AE43167B8A](<Server/ECS/LIVA/LIVA Q2/6F0AAEC80AB2/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/AE43167B8A>) |
| 8086:54c4 |           | Intel            | Alder Lake-N SD Host Controller      | 3     | sdhci_pci  | [94CCA0DB39](<Server/GEEKOM/Mini/Mini Air12/F53E738CBAB9/LINUXMINT-22/6.8.0-47-GENERIC/X86_64/94CCA0DB39>) |
| 8086:18db | 15d9:1c18 | Intel            | SD Host controller                   | 1     | sdhci_pci  | [3751D50DDE](<Server/Supermicro/Super/Super Server/ACFD57B232A4/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/3751D50DDE>) |
| 8086:18db | 15d9:1c4f | Intel            | SD Host controller                   | 1     | sdhci_pci  | [54A4E7C93E](<Server/Supermicro/Super/Super Server/E299F91C21A0/UBUNTU-20.04/5.15.0-73-GENERIC/X86_64/54A4E7C93E>) |
| 8086:31cc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1     | sdhci_pci  | [ABC999A1A4](<Server/GMKtec/NucBox/NucBox8/D2066B2FCB01/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/ABC999A1A4>) |
| 8086:31d0 | 8086:7270 | Intel            | Celeron/Pentium Silver SD Host Co... | 1     | sdhci_pci  | [ABC999A1A4](<Server/GMKtec/NucBox/NucBox8/D2066B2FCB01/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/ABC999A1A4>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a1a4 | 8086:7270 | Intel            | C620 Series Chipset Family SPI Co... | 92    | spi_int... | [122B21A8E4](<Server/Others/Others/Others/DB0155950DC6/DEBIAN-12/6.8.12-5-PVE/X86_64/122B21A8E4>) |
| 8086:a1a4 | 1028:073a | Intel            | C620 Series Chipset Family SPI Co... | 29    | spi_int... | [B75294443B](<Server/Dell/Precision/Precision 7920 Tower/5E36FA18A2AE/KUBUNTU-20.04/5.15.0-84-GENERIC/X86_64/B75294443B>) |
| 8086:a1a4 | 15d9:0967 | Intel            | C620 Series Chipset Family SPI Co... | 27    | spi_int... | [01602FD84E](<Server/Supermicro/SYS-6019/SYS-6019P-WTR/0C2A376E8BE8/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/01602FD84E>) |
| 8086:a1a4 | 8086:35ce | Intel            | C620 Series Chipset Family SPI Co... | 22    |            | [781F43495A](<Server/Intel/S2600/S2600WFT/B54D5A70237A/RED-OS-7.3.2/5.15.87-1.EL7.3.X86_64/X86_64/781F43495A>) |
| 8086:a1a4 | 1028:0715 | Intel            | C620 Series Chipset Family SPI Co... | 19    | spi_int... | [2EA3B6BA11](<Server/Dell/PowerEdge/PowerEdge R740/102E11A0DB9A/DEBIAN-12/6.8.4-2-PVE/X86_64/2EA3B6BA11>) |
| 8086:a1a4 | 1458:1000 | Intel            | C620 Series Chipset Family SPI Co... | 17    | spi_int... | [F76FC4031D](<Server/PSSC Labs/SS4000/SS4000HD/13084E646FAA/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/F76FC4031D>) |
| 8086:a1a4 | 1028:0739 | Intel            | C620 Series Chipset Family SPI Co... | 16    | intel_spi  | [BA0626CE0A](<Server/Dell/Precision/Precision 7820 Tower/3792A2743A38/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/BA0626CE0A>) |
| 8086:a1a4 | 1043:871e | Intel            | C620 Series Chipset Family SPI Co... | 15    | intel_s... | [664827DD6C](<Server/ASUSTek Computer/Pro/Pro WS C621-64L SAGE-10G Series/A1C444FAB774/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/664827DD6C>) |
| 8086:51a4 |           | Intel            | Alder Lake-P PCH SPI Controller      | 13    | spi_int... | [DF42F11E59](<Server/GEEKOM/GT13/GT13 Pro/EF7C9F2D8B32/LINUXMINT-22/6.8.0-48-GENERIC/X86_64/DF42F11E59>) |
| 8086:a1a4 | 17aa:1038 | Intel            | C620 Series Chipset Family SPI Co... | 13    | spi_int... | [CAFAEE2FC7](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC000QGE/C9B0658BA91C/DEBIAN-12/6.1.0-28-AMD64/X86_64/CAFAEE2FC7>) |
| 8086:a1a4 | 1849:a1a4 | Intel            | C620 Series Chipset Family SPI Co... | 12    |            | [E9C9A4C51A](<Server/INFERIT/RS224/RS224 R1G3D32RU/68DD4BB73C8C/ROSA-12F.1/6.1.58-GENERIC-5ROSA2021.15-X86_64/X86_64/E9C9A4C51A>) |
| 8086:a324 | 8086:7270 | Intel            | Cannon Lake PCH SPI Controller       | 11    | spi_int... | [A2FD0BC88C](<Server/Lenovo/ThinkSystem/ThinkSystem SR250 -[7Y51CTO1WW]-/56D35BA12534/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/A2FD0BC88C>) |
| 10de:1ad9 | 1028:12a0 | Nvidia           | TU104 USB Type-C UCSI Controller     | 10    | i2c_nvi... | [3BAB33D8D5](<Server/Dell/Precision/Precision 7920 Tower/2D5729D9652C/XUBUNTU-20.04/5.14.0-1052-OEM/X86_64/3BAB33D8D5>) |
| 8086:a1a4 | 15d9:096d | Intel            | C620 Series Chipset Family SPI Co... | 10    | spi_int... | [80DB5BCB0E](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/F054CE6D6C8F/UBUNTU-22.04/6.2.0-33-GENERIC/X86_64/80DB5BCB0E>) |
| 8086:a1a4 | 15d9:095d | Intel            | C620 Series Chipset Family SPI Co... | 9     | spi_int... | [A121B2A2E1](<Server/Supermicro/Super/Super Server/751AC2BC6C6F/CYBER-INFRASTRUCTURE-6.0.2/3.10.0-1160.105.1.AIP7.214.3/X86_64/A121B2A2E1>) |
| 8086:a1a4 | 17aa:7808 | Intel            | C620 Series Chipset Family SPI Co... | 9     | intel_s... | [424E70419E](<Server/Lenovo/ThinkSystem/ThinkSystem SR570 -[7Y03CTO1WW]-/D3469A41F07A/XUBUNTU-18.04/4.15.0-213-GENERIC/X86_64/424E70419E>) |
| 8086:a1a4 | 1028:0716 | Intel            | C620 Series Chipset Family SPI Co... | 8     |            | [B89424543D](<Server/Dell/PowerEdge/PowerEdge R640/88100BFA40CD/DEBIAN-12/6.1.0-13-AMD64/X86_64/B89424543D>) |
| 8086:a1a4 | 103c:81c6 | Intel            | C620 Series Chipset Family SPI Co... | 8     | spi_int... | [21781753FB](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/4E03B443521E/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/21781753FB>) |
| 8086:a1a4 | 15d9:0981 | Intel            | C620 Series Chipset Family SPI Co... | 8     | intel_s... | [6CA957B8C9](<Server/Supermicro/SSG-6049/SSG-6049P-E1CR36L/A0CFEEE452D8/DEBIAN/6.6.15-AMD64/X86_64/6CA957B8C9>) |
| 8086:a1a4 | 17aa:1037 | Intel            | C620 Series Chipset Family SPI Co... | 8     | intel_spi  | [301BFF683B](<Server/Lenovo/ThinkStation/ThinkStation P720 30BBS3H50D/215583F782C1/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.10.4-1-DEFAULT/X86_64/301BFF683B>) |
| 8086:1bca | 8086:7270 | Intel            | C741 Series SPI Controller           | 7     | spi_int... | [A2CE10373E](<Server/Graviton/S2122/S2122IU/ED2248ACB950/ROSA-12/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/A2CE10373E>) |
| 8086:a1a4 | 1028:07c9 | Intel            | C620 Series Chipset Family SPI Co... | 7     | spi_int... | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:a1a4 | 103c:81c7 | Intel            | C620 Series Chipset Family SPI Co... | 7     | spi_int... | [03E2A5BAC1](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/5E9B675190B8/UBUNTU-22.04/6.2.0-37-GENERIC/X86_64/03E2A5BAC1>) |
| 8086:a1a4 | 15d9:091c | Intel            | C620 Series Chipset Family SPI Co... | 7     |            | [0B1FEB460C](<Server/Supermicro/SYS-6019/SYS-6019U-TN4R4T/51D2EF357A4F/ROCKY-9.2/5.14.0-284.18.1.EL9_2.X86_64/X86_64/0B1FEB460C>) |
| 8086:a324 | 15d9:1a1d | Intel            | Cannon Lake PCH SPI Controller       | 7     | intel_s... | [E63931ED4F](<Server/Supermicro/Super/Super Server/A6F8ADA06288/VOID-ROLLING/6.3.13_1/X86_64/E63931ED4F>) |
| 8086:a324 | 15d9:1a1f | Intel            | Cannon Lake PCH SPI Controller       | 7     | intel_s... | [AEF6DB08C4](<Server/Supermicro/Super/Super Server/BAD6EC448C66/UBUNTU-22.04/5.15.0-116-GENERIC/X86_64/AEF6DB08C4>) |
| 8086:a368 | 15d9:1a1d | Intel            | Cannon Lake PCH Serial IO I2C Con... | 7     | intel_l... | [E63931ED4F](<Server/Supermicro/Super/Super Server/A6F8ADA06288/VOID-ROLLING/6.3.13_1/X86_64/E63931ED4F>) |
| 8086:a368 | 15d9:1a1f | Intel            | Cannon Lake PCH Serial IO I2C Con... | 7     | intel_l... | [AEF6DB08C4](<Server/Supermicro/Super/Super Server/BAD6EC448C66/UBUNTU-22.04/5.15.0-116-GENERIC/X86_64/AEF6DB08C4>) |
| 8086:a369 | 15d9:1a1d | Intel            | Cannon Lake PCH Serial IO I2C Con... | 7     | intel_l... | [E63931ED4F](<Server/Supermicro/Super/Super Server/A6F8ADA06288/VOID-ROLLING/6.3.13_1/X86_64/E63931ED4F>) |
| 8086:a369 | 15d9:1a1f | Intel            | Cannon Lake PCH Serial IO I2C Con... | 7     | intel_l... | [AEF6DB08C4](<Server/Supermicro/Super/Super Server/BAD6EC448C66/UBUNTU-22.04/5.15.0-116-GENERIC/X86_64/AEF6DB08C4>) |
| 8086:4da4 |           | Intel            | Jasper Lake SPI Controller           | 6     | spi_int... | [6B8F982987](<Server/GEEKOM/MiniAir/MiniAir 11/5E7475318C5E/UBUNTU-24.04/6.8.0-35-GENERIC/X86_64/6B8F982987>) |
| 8086:4de8 |           | Intel            | Jasper Lake Serial IO I2C Host Co... | 6     | intel_l... | [6B8F982987](<Server/GEEKOM/MiniAir/MiniAir 11/5E7475318C5E/UBUNTU-24.04/6.8.0-35-GENERIC/X86_64/6B8F982987>) |
| 8086:4de9 |           | Intel            | Jasper Lake Serial IO I2C Host Co... | 6     | intel_l... | [6B8F982987](<Server/GEEKOM/MiniAir/MiniAir 11/5E7475318C5E/UBUNTU-24.04/6.8.0-35-GENERIC/X86_64/6B8F982987>) |
| 8086:4deb |           | Intel            | Jasper Lake Serial IO I2C Host Co... | 6     | intel_l... | [6B8F982987](<Server/GEEKOM/MiniAir/MiniAir 11/5E7475318C5E/UBUNTU-24.04/6.8.0-35-GENERIC/X86_64/6B8F982987>) |
| 8086:a1a4 | 1028:0718 | Intel            | C620 Series Chipset Family SPI Co... | 6     |            | [A4F3535E84](<Server/Dell/Precision/Precision 7920 Rack/1D56B1A533A9/UBUNTU-20.04/5.14.0-1057-OEM/X86_64/A4F3535E84>) |
| 8086:a1a4 | 17aa:7800 | Intel            | C620 Series Chipset Family SPI Co... | 6     |            | [47FE0DACDD](<Server/Lenovo/ThinkSystem/ThinkSystem SR630 -[7X02CTO1WW]/74C1AF03C5E9/LINUXMINT-20.3/5.4.0-144-GENERIC/X86_64/47FE0DACDD>) |
| 8086:a1a4 | 17aa:7801 | Intel            | C620 Series Chipset Family SPI Co... | 6     |            | [BAFB634A37](<Server/Lenovo/ThinkSystem/ThinkSystem SR530 -[7X08CTO1WW]-/16717DADAA79/CENTOS-7/3.10.0-1160.36.2.EL7.X86_64/X86_64/BAFB634A37>) |
| 10de:1ad7 | 1458:37c4 | Nvidia           | TU102 USB Type-C UCSI Controller     | 5     | i2c_nvi... | [29DC4440FF](<Server/Gigabyte Technology/G291/G291-281-00/D997C51354A6/ROCKY-8.9/4.18.0-513.11.1.EL8_9.X86_64/X86_64/29DC4440FF>) |
| 8086:a1a4 | 1028:0737 | Intel            | C620 Series Chipset Family SPI Co... | 5     |            | [D288D87AB5](<Server/Dell/PowerEdge/PowerEdge R740xd/BB55A2E30656/ALMA-8.7/4.18.0-425.19.2.EL8_7.X86_64/X86_64/D288D87AB5>) |
| 8086:a1a4 | 1028:07cb | Intel            | C620 Series Chipset Family SPI Co... | 5     | intel_spi  | [C59E7B7F26](<Server/Dell/PowerEdge/PowerEdge T440/D6901D17FD14/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.3.7-1-DEFAULT/X86_64/C59E7B7F26>) |
| 8086:a1a4 | 1028:07e5 | Intel            | C620 Series Chipset Family SPI Co... | 5     | intel_spi  | [26C6662D67](<Server/Dell/PowerEdge/PowerEdge T640/2781755B8077/FEDORA-39/6.7.7-200.FC39.X86_64/X86_64/26C6662D67>) |
| 10de:1ad7 | 10de:12a3 | Nvidia           | TU102 USB Type-C UCSI Controller     | 4     | i2c_nvi... | [409CDE8B44](<Server/AIC/SB203/SB203-LX/9D990B8AEFFB/UBUNTU-20.04/5.15.0-122-GENERIC/X86_64/409CDE8B44>) |
| 8086:19e0 | 15d9:0969 | Intel            | Atom Processor C3000 Series SPI C... | 4     | intel_s... | [CDCA826585](<Server/Supermicro/Super/Super Server/67F50154C8D4/UBUNTU-22.04/5.15.0-67-GENERIC/X86_64/CDCA826585>) |
| 8086:43a4 | 1458:1000 | Intel            | Tiger Lake-H SPI Controller          | 4     | spi_int... | [DF0B00ACCC](<Server/Gigabyte Technology/MX33/MX33-BS1-V1/1BBDCF35885F/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/DF0B00ACCC>) |
| 8086:43a4 | 1849:43a4 | Intel            | Tiger Lake-H SPI Controller          | 4     | spi_int... | [125542F615](<Server/ASRockRack/E3/E3C252D4U-2T-OVH/FD8B71F461B7/UBUNTU-22.04/5.15.0-83-GENERIC/X86_64/125542F615>) |
| 8086:43ad | 1849:43ad | Intel            | 500 Series Chipset Family PCIe Po... | 4     | intel_l... | [125542F615](<Server/ASRockRack/E3/E3C252D4U-2T-OVH/FD8B71F461B7/UBUNTU-22.04/5.15.0-83-GENERIC/X86_64/125542F615>) |
| 8086:43ae | 1849:43ae | Intel            | 500 Series Chipset Family PCIe Po... | 4     | intel_l... | [125542F615](<Server/ASRockRack/E3/E3C252D4U-2T-OVH/FD8B71F461B7/UBUNTU-22.04/5.15.0-83-GENERIC/X86_64/125542F615>) |
| 8086:43e8 | 1458:1000 | Intel            | Tiger Lake-H Serial IO I2C Contro... | 4     | intel_l... | [DF0B00ACCC](<Server/Gigabyte Technology/MX33/MX33-BS1-V1/1BBDCF35885F/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/DF0B00ACCC>) |
| 8086:43e8 | 1849:43e8 | Intel            | Tiger Lake-H Serial IO I2C Contro... | 4     | intel_l... | [125542F615](<Server/ASRockRack/E3/E3C252D4U-2T-OVH/FD8B71F461B7/UBUNTU-22.04/5.15.0-83-GENERIC/X86_64/125542F615>) |
| 8086:43e9 | 1849:43e9 | Intel            | Tiger Lake-H Serial IO I2C Contro... | 4     | intel_l... | [125542F615](<Server/ASRockRack/E3/E3C252D4U-2T-OVH/FD8B71F461B7/UBUNTU-22.04/5.15.0-83-GENERIC/X86_64/125542F615>) |

### Serial controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a1bd | 17aa:1038 | Intel            | C620 Series Chipset Family KT Red... | 13    | serial     | [CAFAEE2FC7](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC000QGE/C9B0658BA91C/DEBIAN-12/6.1.0-28-AMD64/X86_64/CAFAEE2FC7>) |
| 8086:a1bd | 1028:073a | Intel            | C620 Series Chipset Family KT Red... | 12    | serial     | [45516ED3A7](<Server/Dell/Precision/Precision 7920 Tower/4910BAFAEC76/UBUNTU-22.04/5.15.0-106-GENERIC/X86_64/45516ED3A7>) |
| 8086:a1bd | 1028:0739 | Intel            | C620 Series Chipset Family KT Red... | 11    | serial     | [BA0626CE0A](<Server/Dell/Precision/Precision 7820 Tower/3792A2743A38/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/BA0626CE0A>) |
| 8086:a1bd | 17aa:1037 | Intel            | C620 Series Chipset Family KT Red... | 8     | serial     | [301BFF683B](<Server/Lenovo/ThinkStation/ThinkStation P720 30BBS3H50D/215583F782C1/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.10.4-1-DEFAULT/X86_64/301BFF683B>) |
| 8086:a363 | 8086:7270 | Intel            | Cannon Lake PCH Active Management... | 8     | serial     | [196C8EB317](<Server/Neousys Technology/Nuvo-7100VTC/Nuvo-7100VTC Series/E44E3E216941/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/196C8EB317>) |
| 8086:a13d | 15d9:0895 | Intel            | 100 Series/C230 Series Chipset Fa... | 7     | serial     | [23F3141732](<Server/Supermicro/Super/Super Server/C06149C5792E/UBUNTU-24.04/6.8.0-36-GENERIC/X86_64/23F3141732>) |
| 8086:8c3d | 15d9:0805 | Intel            | 8 Series/C220 Series Chipset Fami... | 6     | serial     | [A3DDA288D1](<Server/Supermicro/X10/X10SAE/FB4CD398216A/LINUXMINT-21.2/5.15.0-91-GENERIC/X86_64/A3DDA288D1>) |
| 8086:a13d | 8086:1999 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     | serial     | [740BB1191A](<Server/Schweitzer Engineering Laboratories/SEL/SEL-3355/C89D1BB6CD6D/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/740BB1191A>) |
| 8086:a2bd | 15d9:098e | Intel            | 200 Series Chipset Family KT Redi... | 4     | serial     | [2887A82948](<Server/Supermicro/Super/Super Server/4CD262ADBF12/DEBIAN-11/5.19.11/X86_64/2887A82948>) |
| 8086:43fc | 1458:1000 | Intel            | Tiger Lake-H Integrated Sensor Hub   | 3     | intel_i... | [DF0B00ACCC](<Server/Gigabyte Technology/MX33/MX33-BS1-V1/1BBDCF35885F/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/DF0B00ACCC>) |
| 8086:43fc | 1849:43fc | Intel            | Tiger Lake-H Integrated Sensor Hub   | 3     | intel_i... | [125542F615](<Server/ASRockRack/E3/E3C252D4U-2T-OVH/FD8B71F461B7/UBUNTU-22.04/5.15.0-83-GENERIC/X86_64/125542F615>) |
| 8086:7aeb | 15d9:1c48 | Intel            | Alder Lake-S Keyboard and Text (K... | 3     | serial     | [82704D894B](<Server/Supermicro/Super/Super Server/C1D7CD066F95/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/82704D894B>) |
| 8086:a13d | 15d9:089f | Intel            | 100 Series/C230 Series Chipset Fa... | 3     | serial     | [BA41A40F36](<Server/Supermicro/Super/Super Server/D838587F42DD/DEBIAN/6.6.15-AMD64/X86_64/BA41A40F36>) |
| 1415:c208 | 1415:c208 | Oxford Semico... | OXPCIe954 Quad Native 950 UART       | 2     | serial     | [C088868F62](<Server/Supermicro/X9/X9DRD-iF-LF/F42BB6D21594/DEBIAN-11/5.15.74-1-PVE/X86_64/C088868F62>) |
| 8086:43e3 | 15d9:1c28 | Intel            | Tiger Lake AMT SOL Redirection       | 2     | serial     | [9A4BA4F180](<Server/Supermicro/Super/Super Server/0E8D90837AAF/DEBIAN-12/6.5.13-3-PVE/X86_64/9A4BA4F180>) |
| 8086:7aeb | 8086:7270 | Intel            | Alder Lake-S Keyboard and Text (K... | 2     | serial     | [CDE616CDE3](<Server/Neousys Technology/Nuvo-10000/Nuvo-10000 Series/4193457B5D58/UBUNTU-22.04/6.2.0-39-GENERIC/X86_64/CDE616CDE3>) |
| 8086:a13d | 15d9:0894 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | 8250_pci   | [470EF56159](<Server/Supermicro/X11/X11SSV-Q/10133D1BC396/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/470EF56159>) |
| 8086:a13d | 8086:a13d | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | serial     | [7414E2296D](<Server/Neousys Technology/Nuvo-6108/Nuvo-6108GC/A7F473C7C9E6/UBUNTU-18.04/5.4.0-152-GENERIC/X86_64/7414E2296D>) |
| 9710:9865 | a000:1000 | MosChip Semic... | PCI 9865 Multi-I/O Controller        | 2     | parport_pc | [715B40D8B6](<Server/Intel/S5000/S5000XVN/187007C30239/FEDORA-34/5.14.12-200.FC34.X86_64/X86_64/715B40D8B6>) |
| 10ee:4b87 | 10ee:4350 | Xilinx           | Serial controller                    | 1     | xclmgmt    | [7026C20C97](<Server/Supermicro/Super/Super Server/007236A7EB64/UBUNTU-UNITY-16.04/4.13.0-36-GENERIC/X86_64/7026C20C97>) |
| 10ee:4b88 | 10ee:4350 | Xilinx           | Serial controller                    | 1     | xocl       | [7026C20C97](<Server/Supermicro/Super/Super Server/007236A7EB64/UBUNTU-UNITY-16.04/4.13.0-36-GENERIC/X86_64/7026C20C97>) |
| 1393:1024 | 1393:1024 | Moxa Technolo... | CP-102E (2-port RS-232 Smart PCI ... | 1     | serial     | [9C8826C0D2](<Server/Dell/PowerEdge/PowerEdge T110/31B8C6D71C1F/UBUNTU-20.04/5.4.0-89-GENERIC/X86_64/9C8826C0D2>) |
| 1415:9501 | 131f:2050 | Oxford Semico... | OX16PCI954 (Quad 16950 UART) func... | 1     | serial     | [80DC2F8936](<Server/Supermicro/Super/Super Server/A9CFB59D8528/OPENSUSE-LEAP-42.1/4.1.39-56-DEFAULT/X86_64/80DC2F8936>) |
| 1415:c158 | 1415:c158 | Oxford Semico... | OXPCIe952 Dual Native 950 UART       | 1     | serial     | [352FEE0E7F](<Server/HPE/ProLiant/ProLiant DL360 Gen10/0438CFCFB022/DEBIAN-10/4.19.0-8-AMD64/X86_64/352FEE0E7F>) |
| 8086:18d8 | 15d9:1c18 | Intel            | Cedar Fork HSUART                    | 1     | 8250_mi... | [3751D50DDE](<Server/Supermicro/Super/Super Server/ACFD57B232A4/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/3751D50DDE>) |
| 8086:18d8 | 15d9:1c4f | Intel            | Cedar Fork HSUART                    | 1     | 8250_mid   | [54A4E7C93E](<Server/Supermicro/Super/Super Server/E299F91C21A0/UBUNTU-20.04/5.15.0-73-GENERIC/X86_64/54A4E7C93E>) |
| 8086:18d8 | 8086:7270 | Intel            | Cedar Fork HSUART                    | 1     | 8250_mid   | [C618310D44](<Server/Dell/PowerEdge/PowerEdge XR4510c/35E133588594/DEBIAN-12/6.1.0-10-AMD64/X86_64/C618310D44>) |
| 8086:1be3 | 17aa:104e | Intel            | C741 Series Active Management Tec... | 1     | serial     | [791DC0869D](<Server/Lenovo/ThinkStation/ThinkStation PX 30EUA0EG00/8A299C9A2065/DEBIAN-12/6.10.11+BPO-AMD64/X86_64/791DC0869D>) |
| 8086:1d3d | 152d:8988 | Intel            | C600/X79 series chipset KT Contro... | 1     | serial     | [E0EF143493](<Server/Quanta/Freedom/Freedom/53CBFD82B356/LINUXMINT-19.3/5.0.0-32-GENERIC/X86_64/E0EF143493>) |
| 8086:1e3d | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 1     | serial     | [F82AA66A16](<Server/Schweitzer Engineering Laboratories/SEL/SEL-3355/766281720A90/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/F82AA66A16>) |
| 8086:43e3 | e4bf:53c9 | Intel            | Tiger Lake AMT SOL Redirection       | 1     | serial     | [A5CA58A104](<Server/EKF Elektronik/CompactPCI/CompactPCI Serial/89AAC1C97050/UBUNTU-24.04/6.8.0-47-GENERIC/X86_64/A5CA58A104>) |
| 8086:43fc | 1043:882f | Intel            | Tiger Lake-H Integrated Sensor Hub   | 1     | intel_i... | [0C1465AD47](<Server/ASUSTek Computer/RS300/RS300-E11-PS4/85644FBAE9C3/UBUNTU-22.10/5.19.0-15-GENERIC/X86_64/0C1465AD47>) |
| 8086:43fc | 8086:7270 | Intel            | Tiger Lake-H Integrated Sensor Hub   | 1     | intel_i... | [B6B52E11FE](<Server/Lenovo/ThinkSystem/ThinkSystem SR250 V2/DCE46F160939/DEBIAN-12/6.1.0-12-AMD64/X86_64/B6B52E11FE>) |
| 8086:51e3 | 15d9:1c86 | Intel            | Alder Lake AMT SOL Redirection       | 1     | serial     | [E0B7939357](<Server/Supermicro/Super/Super Server/6403FDE36610/UBUNTU-22.04/5.15.0-72-GENERIC/X86_64/E0B7939357>) |
| 8086:8c3d | 15d9:0654 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | serial     | [AE67700E54](<Server/Supermicro/X10/X10SLQ/A28F497601BF/FEDORA-33/5.9.13-200.FC33.X86_64/X86_64/AE67700E54>) |
| 8086:8d3d | 1458:1000 | Intel            | C610/X99 series chipset KT Contro... | 1     | serial     | [2F69A2F89C](<Server/Dedicated Computing/OEM-F7342/OEM-F7342-00/A56806D283ED/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/2F69A2F89C>) |
| 8086:8d3d | 15d9:0834 | Intel            | C610/X99 series chipset KT Contro... | 1     | serial     | [746DAACC72](<Server/Supermicro/Super/Super Server/4582319ADDEA/DEBIAN-10/5.4.203-1-PVE/X86_64/746DAACC72>) |
| 8086:a13d | 15d9:0888 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | serial     | [C37F8CD97A](<Server/Supermicro/Super/Super Server/3D7809C86280/DEBIAN-11/5.15.74-1-PVE/X86_64/C37F8CD97A>) |
| 8086:a13d | 15d9:0907 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | serial     | [66EE0BC524](<Server/Supermicro/Super/Super Server/40D662EC15C8/UBUNTU-18.04/4.15.0-143-GENERIC/X86_64/66EE0BC524>) |
| 8086:a1bd | 103c:81c6 | Intel            | C620 Series Chipset Family KT Red... | 1     | serial     | [21781753FB](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/4E03B443521E/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/21781753FB>) |
| 8086:a1bd | 103c:81c7 | Intel            | C620 Series Chipset Family KT Red... | 1     | serial     | [E717A99F1F](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/5E9B675190B8/ZORIN-16/5.15.0-67-GENERIC/X86_64/E717A99F1F>) |
| 8086:a1bd | 1043:871e | Intel            | C620 Series Chipset Family KT Red... | 1     | serial     | [664827DD6C](<Server/ASUSTek Computer/Pro/Pro WS C621-64L SAGE-10G Series/A1C444FAB774/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/664827DD6C>) |
| 8086:a1bd | 1734:1230 | Intel            | C620 Series Chipset Family KT Red... | 1     | serial     | [86AB491564](<Server/Fujitsu/CELSIUS/CELSIUS R970/7E07629658CC/CENTOS-8/4.18.0-240.10.1.EL8_3.X86_64/X86_64/86AB491564>) |
| 9710:9904 | a000:1000 | MosChip Semic... | 4-Port PCIe Serial Adapter           | 1     | serial     | [22A316E31B](<Server/Neousys Technology/Nuvo-8208GC/Nuvo-8208GC Series/78293157040C/UBUNTU-18.04/5.4.0-52-GENERIC/X86_64/22A316E31B>) |
| 9710:9922 | a000:1000 | MosChip Semic... | MCS9922 PCIe Multi-I/O Controller    | 1     | serial     | [7479576DA8](<Server/Supermicro/Super/Super Server/95B1AD8FBD26/ROSA-2014.1/4.1.34-NRJ-DESKTOP-2ROSA-X86_64/X86_64/7479576DA8>) |

### Signal processing (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0e30 | 1028:04f6 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 3     | ivbep_u... | [B06AB09EE7](<Server/Dell/PowerEdge/PowerEdge R520/CE26586B1628/ROCKY-9.3/5.14.0-362.24.1.EL9_3.X86_64/X86_64/B06AB09EE7>) |
| 8086:0e34 | 1028:04f6 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 3     | ivbep_u... | [B06AB09EE7](<Server/Dell/PowerEdge/PowerEdge R520/CE26586B1628/ROCKY-9.3/5.14.0-362.24.1.EL9_3.X86_64/X86_64/B06AB09EE7>) |
| 8086:0e36 | 1028:04f6 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 3     | ivbep_u... | [B06AB09EE7](<Server/Dell/PowerEdge/PowerEdge R520/CE26586B1628/ROCKY-9.3/5.14.0-362.24.1.EL9_3.X86_64/X86_64/B06AB09EE7>) |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a1b1 | 8086:7270 | Intel            | C620 Series Chipset Family Therma... | 92    | intel_p... | [122B21A8E4](<Server/Others/Others/Others/DB0155950DC6/DEBIAN-12/6.8.12-5-PVE/X86_64/122B21A8E4>) |
| 8086:1d24 | 15d9:0636 | Intel            | C600/X79 series chipset Thermal M... | 39    |            | [86B4E152AD](<Server/Supermicro/X9/X9DRW/D2C6B0237967/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/86B4E152AD>) |
| 8086:a1b1 | 1028:073a | Intel            | C620 Series Chipset Family Therma... | 29    | intel_p... | [B75294443B](<Server/Dell/Precision/Precision 7920 Tower/5E36FA18A2AE/KUBUNTU-20.04/5.15.0-84-GENERIC/X86_64/B75294443B>) |
| 8086:a1b1 | 15d9:0967 | Intel            | C620 Series Chipset Family Therma... | 27    | intel_p... | [01602FD84E](<Server/Supermicro/SYS-6019/SYS-6019P-WTR/0C2A376E8BE8/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/01602FD84E>) |
| 8086:1d24 | 152d:899b | Intel            | C600/X79 series chipset Thermal M... | 25    |            | [7E09CCDA22](<Server/ETegro Technologies/Hyperion/Hyperion RS125 G4/5259A72AB62F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/7E09CCDA22>) |
| 8086:a131 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 25    | intel_p... | [172A6309DF](<Server/Tarox/ParX/ParX T100c G6 Server/24E1CEA11A00/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/172A6309DF>) |
| 8086:a1b1 | 8086:35ce | Intel            | C620 Series Chipset Family Therma... | 23    | intel_p... | [781F43495A](<Server/Intel/S2600/S2600WFT/B54D5A70237A/RED-OS-7.3.2/5.15.87-1.EL7.3.X86_64/X86_64/781F43495A>) |
| 8086:a1b1 | 1590:00eb | Intel            | C620 Series Chipset Family Therma... | 22    | intel_p... | [D9F97B2071](<Server/HPE/ProLiant/ProLiant DL380 Gen10/6D60567E7E8D/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/D9F97B2071>) |
| 8086:a1b1 | 1028:0715 | Intel            | C620 Series Chipset Family Therma... | 19    | intel_p... | [2EA3B6BA11](<Server/Dell/PowerEdge/PowerEdge R740/102E11A0DB9A/DEBIAN-12/6.8.4-2-PVE/X86_64/2EA3B6BA11>) |
| 8086:a1b1 | 1458:1000 | Intel            | C620 Series Chipset Family Therma... | 17    | intel_p... | [F76FC4031D](<Server/PSSC Labs/SS4000/SS4000HD/13084E646FAA/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/F76FC4031D>) |
| 8086:a1b1 | 1028:0739 | Intel            | C620 Series Chipset Family Therma... | 16    | intel_p... | [BA0626CE0A](<Server/Dell/Precision/Precision 7820 Tower/3792A2743A38/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/BA0626CE0A>) |
| 8086:1d24 | 15d9:0626 | Intel            | C600/X79 series chipset Thermal M... | 15    |            | [39232DFDE3](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/B0C1ED30C610/DEBIAN-12/6.1.0-25-AMD64/X86_64/39232DFDE3>) |
| 8086:a1b1 | 1043:871e | Intel            | C620 Series Chipset Family Therma... | 15    | intel_p... | [664827DD6C](<Server/ASUSTek Computer/Pro/Pro WS C621-64L SAGE-10G Series/A1C444FAB774/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/664827DD6C>) |
| 8086:8d24 | 19e5:2062 | Intel            | C610/X99 series chipset Thermal S... | 14    | intel_p... | [EDA2D8550F](<Server/HUAWEI/RH1288/RH1288 V3/899B0DE1B12F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/EDA2D8550F>) |
| 8086:a131 | 15d9:089a | Intel            | 100 Series/C230 Series Chipset Fa... | 13    | intel_p... | [85E2DD189C](<Server/Supermicro/Super/Super Server/2FA87A9B8E2E/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/85E2DD189C>) |
| 8086:a1b1 | 17aa:1038 | Intel            | C620 Series Chipset Family Therma... | 13    | intel_p... | [CAFAEE2FC7](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC000QGE/C9B0658BA91C/DEBIAN-12/6.1.0-28-AMD64/X86_64/CAFAEE2FC7>) |
| 8086:8c24 | 15d9:086d | Intel            | 8 Series Chipset Family Thermal M... | 12    | intel_p... | [3E9BE7A949](<Server/Supermicro/Super/Super Server/CE1321EEE3B9/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/3E9BE7A949>) |
| 8086:8d24 | 15d9:0857 | Intel            | C610/X99 series chipset Thermal S... | 12    | intel_p... | [7B12EA87ED](<Server/Supermicro/X10/X10SRA/62E49A78B3EF/RHEL-8/4.18.0-553.16.1.EL8_10.X86_64/X86_64/7B12EA87ED>) |
| 8086:a1b1 | 1849:a1b1 | Intel            | C620 Series Chipset Family Therma... | 12    | intel_p... | [E9C9A4C51A](<Server/INFERIT/RS224/RS224 R1G3D32RU/68DD4BB73C8C/ROSA-12F.1/6.1.58-GENERIC-5ROSA2021.15-X86_64/X86_64/E9C9A4C51A>) |
| 8086:1d24 | 15d9:062b | Intel            | C600/X79 series chipset Thermal M... | 11    |            | [F3D2F362E8](<Server/Supermicro/X9/X9SRE-X9SRE-3F-X9SRi-X9SRi-3F/55A635F4E92C/DEBIAN-12/6.8.8-2-PVE/X86_64/F3D2F362E8>) |
| 8086:a379 | 8086:7270 | Intel            | Cannon Lake PCH Thermal Controller   | 11    | intel_p... | [A2FD0BC88C](<Server/Lenovo/ThinkSystem/ThinkSystem SR250 -[7Y51CTO1WW]-/56D35BA12534/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/A2FD0BC88C>) |
| 8086:467d |           | Intel            | Platform Monitoring Technology       | 10    | intel_vsec | [94CCA0DB39](<Server/GEEKOM/Mini/Mini Air12/F53E738CBAB9/LINUXMINT-22/6.8.0-47-GENERIC/X86_64/94CCA0DB39>) |
| 8086:8c24 | 8086:35b5 | Intel            | 8 Series Chipset Family Thermal M... | 10    | intel_p... | [6A61981EA4](<Server/Wortmann AG/TERRA_SERVER/TERRA_SERVER/A40FD0B78666/UBUNTU-22.04/6.5.0-17-GENERIC/X86_64/6A61981EA4>) |
| 8086:a1b1 | 15d9:096d | Intel            | C620 Series Chipset Family Therma... | 10    | intel_p... | [80DB5BCB0E](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/F054CE6D6C8F/UBUNTU-22.04/6.2.0-33-GENERIC/X86_64/80DB5BCB0E>) |
| 19e5:1710 | 19e5:0000 | Huawei Techno... | iBMA Virtual Network Adapter         | 9     |            | [29BDE967FC](<Server/HUAWEI/TaiShan/TaiShan 2280 V2/2603C7B2E57E/UBUNTU-22.04/5.15.0-88-GENERIC/AARCH64/29BDE967FC>) |
| 8086:8c24 | 15d9:0801 | Intel            | 8 Series Chipset Family Thermal M... | 9     | intel_p... | [578C1F5048](<Server/Supermicro/X10/X10SLL-F/02E1EBC8108D/DEBIAN-10/5.4.203-1-PVE/X86_64/578C1F5048>) |
| 8086:a1b1 | 15d9:095d | Intel            | C620 Series Chipset Family Therma... | 9     | intel_p... | [A121B2A2E1](<Server/Supermicro/Super/Super Server/751AC2BC6C6F/CYBER-INFRASTRUCTURE-6.0.2/3.10.0-1160.105.1.AIP7.214.3/X86_64/A121B2A2E1>) |
| 8086:a1b1 | 17aa:7808 | Intel            | C620 Series Chipset Family Therma... | 9     |            | [424E70419E](<Server/Lenovo/ThinkSystem/ThinkSystem SR570 -[7Y03CTO1WW]-/D3469A41F07A/XUBUNTU-18.04/4.15.0-213-GENERIC/X86_64/424E70419E>) |
| 8086:a1b1 | 1028:0716 | Intel            | C620 Series Chipset Family Therma... | 8     | intel_p... | [B89424543D](<Server/Dell/PowerEdge/PowerEdge R640/88100BFA40CD/DEBIAN-12/6.1.0-13-AMD64/X86_64/B89424543D>) |
| 8086:a1b1 | 103c:81c6 | Intel            | C620 Series Chipset Family Therma... | 8     | intel_p... | [21781753FB](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/4E03B443521E/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/21781753FB>) |
| 8086:a1b1 | 15d9:0981 | Intel            | C620 Series Chipset Family Therma... | 8     | intel_p... | [6CA957B8C9](<Server/Supermicro/SSG-6049/SSG-6049P-E1CR36L/A0CFEEE452D8/DEBIAN/6.6.15-AMD64/X86_64/6CA957B8C9>) |
| 8086:a1b1 | 17aa:1037 | Intel            | C620 Series Chipset Family Therma... | 8     | intel_p... | [301BFF683B](<Server/Lenovo/ThinkStation/ThinkStation P720 30BBS3H50D/215583F782C1/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.10.4-1-DEFAULT/X86_64/301BFF683B>) |
| 8086:1d24 | 15d9:062a | Intel            | C600/X79 series chipset Thermal M... | 7     |            | [3B5585BEC8](<Server/Supermicro/X9/X9SRA-X9SRA-3/E73ED86A7227/DEBIAN-11/5.10.0-33-AMD64/X86_64/3B5585BEC8>) |
| 8086:8c24 | 15d9:0804 | Intel            | 8 Series Chipset Family Thermal M... | 7     | intel_p... | [EA13C0439B](<Server/Supermicro/X10/X10SL7-F/1E0E59CD49A9/FEDORA-40/6.10.11-200.FC40.X86_64/X86_64/EA13C0439B>) |
| 8086:8c24 | 15d9:0805 | Intel            | 8 Series Chipset Family Thermal M... | 7     | intel_p... | [A3DDA288D1](<Server/Supermicro/X10/X10SAE/FB4CD398216A/LINUXMINT-21.2/5.15.0-91-GENERIC/X86_64/A3DDA288D1>) |
| 8086:a131 | 1028:06a5 | Intel            | 100 Series/C230 Series Chipset Fa... | 7     | intel_p... | [097C771B65](<Server/Dell/PowerEdge/PowerEdge R230/1EDFED183BEA/DEBIAN-11/5.10.0-19-AMD64/X86_64/097C771B65>) |
| 8086:a131 | 15d9:0895 | Intel            | 100 Series/C230 Series Chipset Fa... | 7     | intel_p... | [23F3141732](<Server/Supermicro/Super/Super Server/C06149C5792E/UBUNTU-24.04/6.8.0-36-GENERIC/X86_64/23F3141732>) |
| 8086:a1b1 | 1028:07c9 | Intel            | C620 Series Chipset Family Therma... | 7     | intel_p... | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:a1b1 | 103c:81c7 | Intel            | C620 Series Chipset Family Therma... | 7     | intel_p... | [03E2A5BAC1](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/5E9B675190B8/UBUNTU-22.04/6.2.0-37-GENERIC/X86_64/03E2A5BAC1>) |
| 8086:a1b1 | 15d9:091c | Intel            | C620 Series Chipset Family Therma... | 7     | intel_p... | [0B1FEB460C](<Server/Supermicro/SYS-6019/SYS-6019U-TN4R4T/51D2EF357A4F/ROCKY-9.2/5.14.0-284.18.1.EL9_2.X86_64/X86_64/0B1FEB460C>) |
| 8086:a379 | 15d9:1a1d | Intel            | Cannon Lake PCH Thermal Controller   | 7     | intel_p... | [E63931ED4F](<Server/Supermicro/Super/Super Server/A6F8ADA06288/VOID-ROLLING/6.3.13_1/X86_64/E63931ED4F>) |
| 8086:a379 | 15d9:1a1f | Intel            | Cannon Lake PCH Thermal Controller   | 7     | intel_p... | [AEF6DB08C4](<Server/Supermicro/Super/Super Server/BAD6EC448C66/UBUNTU-22.04/5.15.0-116-GENERIC/X86_64/AEF6DB08C4>) |
| 8086:a71d |           | Intel            | Raptor Lake Dynamic Platform and ... | 7     | process... | [DF42F11E59](<Server/GEEKOM/GT13/GT13 Pro/EF7C9F2D8B32/LINUXMINT-22/6.8.0-48-GENERIC/X86_64/DF42F11E59>) |
| 8086:1d24 | 15d9:0702 | Intel            | C600/X79 series chipset Thermal M... | 6     |            | [18E84EAC28](<Server/Supermicro/X9/X9DRD-7LN4F-X9DRD-EF/B9F8C820757C/SLACKWARE-15.0/6.1.106-UNRAID/X86_64/18E84EAC28>) |
| 8086:4e03 |           | Intel            | Dynamic Tuning service               | 6     | process... | [6B8F982987](<Server/GEEKOM/MiniAir/MiniAir 11/5E7475318C5E/UBUNTU-24.04/6.8.0-35-GENERIC/X86_64/6B8F982987>) |
| 8086:8c24 | 15d9:0921 | Intel            | 8 Series Chipset Family Thermal M... | 6     | intel_p... | [7B51710FD1](<Server/Supermicro/Super/Super Server/717CACBD4C9C/UBUNTU-22.04/5.15.0-84-GENERIC/X86_64/7B51710FD1>) |
| 8086:8d24 | 1458:0000 | Intel            | C610/X99 series chipset Thermal S... | 6     | intel_p... | [532EDFCFAC](<Server/Gigabyte Technology/MU70/MU70-SU0-NV-XX/34029535BAED/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/532EDFCFAC>) |
| 8086:8d24 | 1d49:0000 | Intel            | C610/X99 series chipset Thermal S... | 6     | intel_p... | [9F36A4143D](<Server/Lenovo/System/System x3650 M5: -[8871AC1]/C84E3B816866/KUBUNTU-22.04/6.2.0-26-GENERIC/X86_64/9F36A4143D>) |
| 8086:a131 | 1028:06aa | Intel            | 100 Series/C230 Series Chipset Fa... | 6     | intel_p... | [AA643EDF66](<Server/Dell/PowerEdge/PowerEdge T130/32614BB1FD9D/LINUXMINT-21.2/6.2.0-26-GENERIC/X86_64/AA643EDF66>) |
| 8086:a131 | 15d9:0884 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     | intel_p... | [0840C7521E](<Server/OEM/PR2285/PR2285S1/E9EE5DAF6D75/DEBIAN-12/6.6.38-TRIM/X86_64/0840C7521E>) |

### Signal processing management (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 19a2:0800 | 19a2:0800 | Emulex           | ServerView iRMC HTI                  | 1     |            | [14C76E0C83](<Server/F5 Networks/C/C117/C1512B26FE54/ALPINE-3.13.2/5.10.16-0-LTS/X86_64/14C76E0C83>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:8d22 | 103c:8030 | Intel            | C610/X99 series chipset SMBus Con... | 103   | i2c_i801   | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:a1a3 | 8086:7270 | Intel            | C620 Series Chipset Family SMBus     | 92    | i2c_i801   | [122B21A8E4](<Server/Others/Others/Others/DB0155950DC6/DEBIAN-12/6.8.12-5-PVE/X86_64/122B21A8E4>) |
| 1022:790b | 1022:790b | AMD              | FCH SMBus Controller                 | 66    | i2c_pii... | [EE0C91380E](<Server/ASRockRack/B650/B650D4U-2L2T-BCM/4E50B00275AF/ALMA-8.10/4.18.0-553.33.1.EL8_10.X86_64/X86_64/EE0C91380E>) |
| 1022:790b | 15d9:790b | AMD              | FCH SMBus Controller                 | 57    | i2c_pii... | [726B65D6E8](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.10/4.18.0-553.27.1.EL8_10.X86_64/X86_64/726B65D6E8>) |
| 8086:3a30 | 15d9:0600 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 49    | i2c_i801   | [6918605D42](<Server/Supermicro/X8/X8DTU/2EC017791B11/DEBIAN-12/6.8.12-5-PVE/X86_64/6918605D42>) |
| 8086:1d22 | 15d9:0636 | Intel            | C600/X79 series chipset SMBus Hos... | 39    | i2c_i801   | [86B4E152AD](<Server/Supermicro/X9/X9DRW/D2C6B0237967/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/86B4E152AD>) |
| 8086:8d22 | 8086:7270 | Intel            | C610/X99 series chipset SMBus Con... | 38    | i2c_i801   | [142EA5AAAB](<Server/Lenovo/70FRR156CN/70FRR156CN RD450X/8535AF5D51BA/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/142EA5AAAB>) |
| 8086:a1a3 | 1028:073a | Intel            | C620 Series Chipset Family SMBus     | 29    | i2c_i801   | [B75294443B](<Server/Dell/Precision/Precision 7920 Tower/5E36FA18A2AE/KUBUNTU-20.04/5.15.0-84-GENERIC/X86_64/B75294443B>) |
| 8086:1d22 | 1043:84ef | Intel            | C600/X79 series chipset SMBus Hos... | 28    | i2c_i801   | [E805BE0AAC](<Server/Kraftway/GEG/GEG/C4E325834440/DEBIAN-12/6.1.0-27-AMD64/X86_64/E805BE0AAC>) |
| 8086:a1a3 | 15d9:0967 | Intel            | C620 Series Chipset Family SMBus     | 27    | i2c_i801   | [01602FD84E](<Server/Supermicro/SYS-6019/SYS-6019P-WTR/0C2A376E8BE8/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/01602FD84E>) |
| 8086:1d22 | 152d:899b | Intel            | C600/X79 series chipset SMBus Hos... | 25    | i2c_i801   | [7E09CCDA22](<Server/ETegro Technologies/Hyperion/Hyperion RS125 G4/5259A72AB62F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/7E09CCDA22>) |
| 8086:a123 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 25    | i2c_i801   | [172A6309DF](<Server/Tarox/ParX/ParX T100c G6 Server/24E1CEA11A00/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/172A6309DF>) |
| 1022:790b | 1458:1000 | AMD              | FCH SMBus Controller                 | 23    | i2c_piix4  | [5F638CAF1F](<Server/Gigabyte Technology/G292/G292-Z20-00/38987F4940DE/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/5F638CAF1F>) |
| 8086:a1a3 | 8086:35ce | Intel            | C620 Series Chipset Family SMBus     | 22    | i2c_i801   | [781F43495A](<Server/Intel/S2600/S2600WFT/B54D5A70237A/RED-OS-7.3.2/5.15.87-1.EL7.3.X86_64/X86_64/781F43495A>) |
| 8086:3a30 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 21    | i2c_i801   | [337DC9A775](<Server/Supermicro/X8/X8DTL/0C862FB30BE8/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/337DC9A775>) |
| 8086:3a30 | 1014:3a30 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 20    | i2c_i801   | [3286B36B51](<Server/IBM/System/System x3650 M3 -[7945YBU]-/64198599779C/DEBIAN-12/6.8.12-1-PVE/X86_64/3286B36B51>) |
| 8086:8d22 | 15d9:0821 | Intel            | C610/X99 series chipset SMBus Con... | 20    | i2c_i801   | [98EF58F80D](<Server/Supermicro/SYS-6018/SYS-6018R-WTR/4A5A129EA8CA/CENTOS-7/3.10.0-1160.83.1.EL7.X86_64/X86_64/98EF58F80D>) |
| 8086:a1a3 | 1028:0715 | Intel            | C620 Series Chipset Family SMBus     | 19    | i2c_i801   | [2EA3B6BA11](<Server/Dell/PowerEdge/PowerEdge R740/102E11A0DB9A/DEBIAN-12/6.8.4-2-PVE/X86_64/2EA3B6BA11>) |
| 8086:1c22 | 1028:04de | Intel            | 6 Series/C200 Series Chipset Fami... | 17    | i2c_i801   | [1E51138D9B](<Server/Dell/PowerEdge/PowerEdge T110 II/A23024949A59/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/1E51138D9B>) |
| 8086:a1a3 | 1458:1000 | Intel            | C620 Series Chipset Family SMBus     | 17    | i2c_i801   | [F76FC4031D](<Server/PSSC Labs/SS4000/SS4000HD/13084E646FAA/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/F76FC4031D>) |
| 8086:a1a3 | 1028:0739 | Intel            | C620 Series Chipset Family SMBus     | 16    | i2c_i801   | [BA0626CE0A](<Server/Dell/Precision/Precision 7820 Tower/3792A2743A38/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/BA0626CE0A>) |
| 8086:1d22 | 1014:1d22 | Intel            | C600/X79 series chipset SMBus Hos... | 15    | i2c_i801   | [128986423A](<Server/IBM/System/System x3650 M4 -[7915E1G]-/605DCB19505B/CENTOS-6/2.6.32-696.20.1.EL6.X86_64/X86_64/128986423A>) |
| 8086:1d22 | 15d9:0626 | Intel            | C600/X79 series chipset SMBus Hos... | 15    | i2c_i801   | [39232DFDE3](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/B0C1ED30C610/DEBIAN-12/6.1.0-25-AMD64/X86_64/39232DFDE3>) |
| 8086:3a30 | 8086:3a30 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 15    | i2c_i801   | [A200E3116A](<Server/TYAN Computer/S/S7012/854B76EC6EB1/DEBIAN-12/6.8.12-1-PVE/X86_64/A200E3116A>) |
| 8086:a1a3 | 1043:871e | Intel            | C620 Series Chipset Family SMBus     | 15    | i2c_i801   | [664827DD6C](<Server/ASUSTek Computer/Pro/Pro WS C621-64L SAGE-10G Series/A1C444FAB774/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/664827DD6C>) |
| 8086:3a30 | 15d9:0007 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 14    | i2c_i801   | [8C5797ED25](<Server/Supermicro/X8/X8DTT/714C700A2F5C/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/8C5797ED25>) |
| 8086:3a30 | 8086:34dc | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 14    | i2c_i801   | [BD871B1C6F](<Server/Intel/S5520/S5520HC/256D70541E78/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/BD871B1C6F>) |
| 8086:8d22 | 15d9:0831 | Intel            | C610/X99 series chipset SMBus Con... | 14    | i2c_i801   | [2BAD48B8D4](<Server/Silicon Mechanics/Rackform/Rackform R309.v5/8442C8D36737/DEBIAN-12/6.1.0-21-AMD64/X86_64/2BAD48B8D4>) |
| 8086:8d22 | 19e5:2062 | Intel            | C610/X99 series chipset SMBus Con... | 14    | i2c_i801   | [EDA2D8550F](<Server/HUAWEI/RH1288/RH1288 V3/899B0DE1B12F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/EDA2D8550F>) |
| 8086:1c22 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 13    | i2c_i801   | [969B046986](<Server/Dell/PowerEdge/PowerEdge R210 II/93E843E2F825/UBUNTU-22.04/5.15.0-124-GENERIC/X86_64/969B046986>) |
| 8086:51a3 |           | Intel            | Alder Lake PCH-P SMBus Host Contr... | 13    | i2c_i801   | [DF42F11E59](<Server/GEEKOM/GT13/GT13 Pro/EF7C9F2D8B32/LINUXMINT-22/6.8.0-48-GENERIC/X86_64/DF42F11E59>) |
| 8086:a123 | 15d9:089a | Intel            | 100 Series/C230 Series Chipset Fa... | 13    | i2c_i801   | [85E2DD189C](<Server/Supermicro/Super/Super Server/2FA87A9B8E2E/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/85E2DD189C>) |
| 8086:a1a3 | 17aa:1038 | Intel            | C620 Series Chipset Family SMBus     | 13    | i2c_i801   | [CAFAEE2FC7](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC000QGE/C9B0658BA91C/DEBIAN-12/6.1.0-28-AMD64/X86_64/CAFAEE2FC7>) |
| 8086:1c22 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 12    | i2c_i801   | [69CCB9B978](<Server/Intel/S1200/S1200BTL/8EF10894528C/UBUNTU-22.04/6.5.0-35-GENERIC/X86_64/69CCB9B978>) |
| 8086:8c22 | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 12    | i2c_i801   | [3E9BE7A949](<Server/Supermicro/Super/Super Server/CE1321EEE3B9/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/3E9BE7A949>) |
| 8086:8c22 | 8086:8c22 | Intel            | 8 Series/C220 Series Chipset Fami... | 12    | i2c_i801   | [236C9198C6](<Server/ASUSTek Computer/P9D-I/P9D-I Series/AB61093A716E/ZORIN-17/6.8.0-49-GENERIC/X86_64/236C9198C6>) |
| 8086:8d22 | 15d9:0857 | Intel            | C610/X99 series chipset SMBus Con... | 12    | i2c_i801   | [7B12EA87ED](<Server/Supermicro/X10/X10SRA/62E49A78B3EF/RHEL-8/4.18.0-553.16.1.EL8_10.X86_64/X86_64/7B12EA87ED>) |
| 8086:a1a3 | 1849:a1a3 | Intel            | C620 Series Chipset Family SMBus     | 12    | i2c_i801   | [E9C9A4C51A](<Server/INFERIT/RS224/RS224 R1G3D32RU/68DD4BB73C8C/ROSA-12F.1/6.1.58-GENERIC-5ROSA2021.15-X86_64/X86_64/E9C9A4C51A>) |
| 1002:4385 | 1028:0444 | AMD              | SBx00 SMBus Controller               | 11    | i2c_piix4  | [2D3D5673E7](<Server/Dell/PowerEdge/PowerEdge R815/6B72BADC37CC/UBUNTU-22.04/5.15.0-119-GENERIC/X86_64/2D3D5673E7>) |
| 1022:790b | 1028:08fc | AMD              | FCH SMBus Controller                 | 11    | i2c_pii... | [CE34F45F28](<Server/AWS Elemental/Appliance/Appliance/78AD1C73F775/UBUNTU-22.04/6.5.0-27-GENERIC/X86_64/CE34F45F28>) |
| 8086:1d22 | 15d9:062b | Intel            | C600/X79 series chipset SMBus Hos... | 11    | i2c_i801   | [F3D2F362E8](<Server/Supermicro/X9/X9SRE-X9SRE-3F-X9SRi-X9SRi-3F/55A635F4E92C/DEBIAN-12/6.8.8-2-PVE/X86_64/F3D2F362E8>) |
| 8086:3a30 | 15d9:0400 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 11    | i2c_i801   | [60421FD6B5](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/CBD0C7907B35/DEBIAN-12/6.8.8-3-PVE/X86_64/60421FD6B5>) |
| 8086:8c22 | 8086:35b5 | Intel            | 8 Series/C220 Series Chipset Fami... | 11    | i2c_i801   | [6A61981EA4](<Server/Wortmann AG/TERRA_SERVER/TERRA_SERVER/A40FD0B78666/UBUNTU-22.04/6.5.0-17-GENERIC/X86_64/6A61981EA4>) |
| 8086:8d22 | 15d9:0844 | Intel            | C610/X99 series chipset SMBus Con... | 11    | i2c_i801   | [D24D2612FE](<Server/Supermicro/Super/Super Server/F4A31F1B8877/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/D24D2612FE>) |
| 8086:a323 | 8086:7270 | Intel            | Cannon Lake PCH SMBus Controller     | 11    | i2c_i801   | [A2FD0BC88C](<Server/Lenovo/ThinkSystem/ThinkSystem SR250 -[7Y51CTO1WW]-/56D35BA12534/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/A2FD0BC88C>) |
| 1022:790b | 1849:790b | AMD              | FCH SMBus Controller                 | 10    | i2c_piix4  | [9F3633CAA8](<Server/ASRockRack/X570/X570D4U-2L2T-BCM/1ABB0156B2C9/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/9F3633CAA8>) |
| 8086:1c22 | 1043:8497 | Intel            | 6 Series/C200 Series Chipset Fami... | 10    | i2c_i801   | [B559AD98CF](<Server/ASUSTek Computer/P8B-M/P8B-M Series/E1996EEBAA7B/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/B559AD98CF>) |
| 8086:3a30 | 15d9:0001 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 10    | i2c_i801   | [AE2D4DE7A3](<Server/Supermicro/X8/X8DT3/E0190A2AFA14/UBUNTU-24.04/6.8.0-47-GENERIC/X86_64/AE2D4DE7A3>) |
| 8086:3a30 | 15d9:0404 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 10    | i2c_i801   | [7D6B6074CA](<Server/DEPO Computers/X8/X8DT6/51562B8D18BD/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/7D6B6074CA>) |
| 8086:3b30 | 8086:34ec | Intel            | 5 Series/3400 Series Chipset SMBu... | 10    | i2c_i801   | [D735382568](<Server/HCL/S3420/S3420GPV/403EC13AAE26/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/D735382568>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a1f0 | 1028:073a | Intel            | Lewisburg MROM 0                     | 28    | snd_hda... | [B75294443B](<Server/Dell/Precision/Precision 7920 Tower/5E36FA18A2AE/KUBUNTU-20.04/5.15.0-84-GENERIC/X86_64/B75294443B>) |
| 13f6:0111 | 13f6:0111 | C-Media Elect... | CMI8738/CMI8768 PCI Audio            | 17    | snd_cmipci | [C6FE3BE3CD](<Server/Dell/PowerEdge/PowerEdge T420/84B5AE1C1912/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/C6FE3BE3CD>) |
| 1002:1640 | 1002:1640 | AMD              | Rembrandt Radeon High Definition ... | 16    | snd_hda... | [EE0C91380E](<Server/ASRockRack/B650/B650D4U-2L2T-BCM/4E50B00275AF/ALMA-8.10/4.18.0-553.33.1.EL8_10.X86_64/X86_64/EE0C91380E>) |
| 1022:15e3 | 1022:d601 | AMD              | Family 17h/19h/1ah HD Audio Contr... | 16    | snd_hda... | [EE0C91380E](<Server/ASRockRack/B650/B650D4U-2L2T-BCM/4E50B00275AF/ALMA-8.10/4.18.0-553.33.1.EL8_10.X86_64/X86_64/EE0C91380E>) |
| 1102:0012 | 1102:0010 | Creative Labs    | CA0132 Sound Core3D [Sound Blaste... | 16    | snd_hda... | [172A6309DF](<Server/Tarox/ParX/ParX T100c G6 Server/24E1CEA11A00/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/172A6309DF>) |
| 8086:a1f0 | 1028:0739 | Intel            | Lewisburg MROM 0                     | 16    | snd_hda... | [BA0626CE0A](<Server/Dell/Precision/Precision 7820 Tower/3792A2743A38/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/BA0626CE0A>) |
| 8086:3a3e | 15d9:0006 | Intel            | 82801JI (ICH10 Family) HD Audio C... | 13    | snd_hda... | [4D6836803F](<Server/Supermicro/X8/X8DTL/6BBB477A611B/UBUNTU-21.10/5.13.0-25-GENERIC/X86_64/4D6836803F>) |
| 8086:a1f0 | 17aa:1038 | Intel            | Lewisburg MROM 0                     | 13    | snd_hda... | [CAFAEE2FC7](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC000QGE/C9B0658BA91C/DEBIAN-12/6.1.0-28-AMD64/X86_64/CAFAEE2FC7>) |
| 1002:aae0 | 1002:aae0 | AMD              | Baffin HDMI/DP Audio [Radeon RX 5... | 12    | snd_hda... | [F9ECA543F7](<Server/Gigabyte Technology/MZ32/MZ32-AR0-00/EF6E29D7D44C/UBUNTU-23.10/6.5.0-44-GENERIC/X86_64/F9ECA543F7>) |
| 8086:8d20 | 15d9:0857 | Intel            | C610/X99 series chipset HD Audio ... | 12    | snd_hda... | [7B12EA87ED](<Server/Supermicro/X10/X10SRA/62E49A78B3EF/RHEL-8/4.18.0-553.16.1.EL8_10.X86_64/X86_64/7B12EA87ED>) |
| 1002:ab28 | 1002:ab28 | AMD              | Navi 21/23 HDMI/DP Audio Controller  | 11    | snd_hda... | [3B1B28CFC7](<Server/Supermicro/Super/Super Server/CD7B912FA9C9/ROSA-12.5.1/6.6.27-GENERIC-3ROSA2021.1-X86_64/X86_64/3B1B28CFC7>) |
| 10de:10f8 | 1028:12a0 | Nvidia           | TU104 HD Audio Controller            | 10    | snd_hda... | [3BAB33D8D5](<Server/Dell/Precision/Precision 7920 Tower/2D5729D9652C/XUBUNTU-20.04/5.14.0-1052-OEM/X86_64/3BAB33D8D5>) |
| 8086:a1f0 | 15d9:096d | Intel            | Lewisburg MROM 0                     | 10    | snd_hda... | [80DB5BCB0E](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/F054CE6D6C8F/UBUNTU-22.04/6.2.0-33-GENERIC/X86_64/80DB5BCB0E>) |
| 10de:0e0f | 1462:8c93 | Nvidia           | GK208 HDMI/DP Audio Controller       | 9     | snd_hda... | [664827DD6C](<Server/ASUSTek Computer/Pro/Pro WS C621-64L SAGE-10G Series/A1C444FAB774/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/664827DD6C>) |
| 8086:1d20 | 1043:84d8 | Intel            | C600/X79 series chipset High Defi... | 9     | snd_hda... | [1B2CDEC714](<Server/ASUSTek Computer/Z9PE-D8/Z9PE-D8 WS/07125A08677D/FEDORA-39/6.7.4-200.FC39.X86_64/X86_64/1B2CDEC714>) |
| 8086:3a3e | 15d9:0100 | Intel            | 82801JI (ICH10 Family) HD Audio C... | 9     | snd_hda... | [CE40C8C96F](<Server/DEPO Computers/X8/X8DAH/6FED46D0B032/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/CE40C8C96F>) |
| 1002:1637 | 1002:1637 | AMD              | Renoir Radeon High Definition Aud... | 8     | snd_hda... | [650A06CBD5](<Server/ASRockRack/X570/X570D4U/BD8DD3707384/NIXOS-24.11/6.6.63/X86_64/650A06CBD5>) |
| 1002:aab0 | 1028:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 8     | snd_hda... | [BD0FE2F7FD](<Server/WIWYNN/Qualcomm/Qualcomm Centriq 2400 Reference Evaluation Platform CV90-LA115-P23/4DF620D6973A/FEDORA-41/6.11.11-300.FALKOR.FC41.AARCH64/AARCH64/BD0FE2F7FD>) |
| 1002:aab0 | 174b:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 8     | snd_hda... | [DAA3DF0F31](<Server/IBM/FAB2/FAB2 Controller/4957F7FD2B12/RHEL-8/4.18.0-477.10.1.EL8_8.X86_64/X86_64/DAA3DF0F31>) |
| 1022:15e3 | 14f1:0200 | AMD              | Family 17h/19h/1ah HD Audio Contr... | 8     | snd_hda... | [F30D39393C](<Server/BESSTAR Tech/X/X400/B2CBACACFA8F/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/F30D39393C>) |
| 10de:10f0 | 1028:11a3 | Nvidia           | GP104 High Definition Audio Contr... | 8     | snd_hda... | [888A235104](<Server/Dell/PowerEdge/PowerEdge R730/B44B0E51BDB3/DEBIAN-12/6.8.12-4-PVE/X86_64/888A235104>) |
| 10de:228b | 10de:14ad | Nvidia           | GA104 High Definition Audio Contr... | 8     | snd_hda... | [D9F97B2071](<Server/HPE/ProLiant/ProLiant DL380 Gen10/6D60567E7E8D/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/D9F97B2071>) |
| 8086:1d20 | 1043:851b | Intel            | C600/X79 series chipset High Defi... | 8     | snd_hda... | [E4686E182A](<Server/ASUSTek Computer/Z9PA-D8/Z9PA-D8 Series/0A5900AC477F/DEBIAN-12/6.5.3-ZABBLY+/X86_64/E4686E182A>) |
| 8086:3a3e | 8086:3a3e | Intel            | 82801JI (ICH10 Family) HD Audio C... | 8     | snd_hda... | [A8B96E89F2](<Server/TYAN Computer/S/S7010/0C071F7B6B6A/XUBUNTU-20.04/5.15.0-73-GENERIC/X86_64/A8B96E89F2>) |
| 8086:a1f0 | 103c:81c6 | Intel            | Lewisburg MROM 0                     | 8     | snd_hda... | [21781753FB](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/4E03B443521E/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/21781753FB>) |
| 8086:a1f0 | 17aa:1037 | Intel            | Lewisburg MROM 0                     | 8     | snd_hda... | [301BFF683B](<Server/Lenovo/ThinkStation/ThinkStation P720 30BBS3H50D/215583F782C1/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.10.4-1-DEFAULT/X86_64/301BFF683B>) |
| 8086:a348 | 8086:7270 | Intel            | Cannon Lake PCH cAVS                 | 8     | snd_hda... | [196C8EB317](<Server/Neousys Technology/Nuvo-7100VTC/Nuvo-7100VTC Series/E44E3E216941/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/196C8EB317>) |
| 1002:aaf8 | 1002:aaf8 | AMD              | Vega 10 HDMI Audio [Radeon Vega 5... | 7     | snd_hda... | [A42E535407](<Server/Dell/Precision/Precision Rack 7910/B0CC6989B61E/UBUNTU-20.04/5.13.0-39-GENERIC/X86_64/A42E535407>) |
| 1002:ab38 | 1002:ab38 | AMD              | Navi 10 HDMI Audio                   | 7     | snd_hda... | [89C105960A](<Server/ASRockRack/ROMED8/ROMED8-2T/3BC6540442E7/DEBIAN-12/6.1.0-26-AMD64/X86_64/89C105960A>) |
| 10de:0e0f | 196e:118b | Nvidia           | GK208 HDMI/DP Audio Controller       | 7     | snd_hda... | [1FD820B09B](<Server/Dell/PowerEdge/PowerEdge R710/20339C7414DA/DEBIAN-12/6.8.4-3-PVE/X86_64/1FD820B09B>) |
| 10de:10f0 | 10de:11a3 | Nvidia           | GP104 High Definition Audio Contr... | 7     | snd_hda... | [D24D2612FE](<Server/Supermicro/Super/Super Server/F4A31F1B8877/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/D24D2612FE>) |
| 10de:10f1 | 10de:11b3 | Nvidia           | GP106 High Definition Audio Contr... | 7     | snd_hda... | [CAFAEE2FC7](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC000QGE/C9B0658BA91C/DEBIAN-12/6.1.0-28-AMD64/X86_64/CAFAEE2FC7>) |
| 8086:1d20 | 15d9:062a | Intel            | C600/X79 series chipset High Defi... | 7     | snd_hda... | [3B5585BEC8](<Server/Supermicro/X9/X9SRA-X9SRA-3/E73ED86A7227/DEBIAN-11/5.10.0-33-AMD64/X86_64/3B5585BEC8>) |
| 8086:51ca | 1f55:0000 | Intel            | Raptor Lake-P/U/H cAVS               | 7     | snd_hda... | [DF42F11E59](<Server/GEEKOM/GT13/GT13 Pro/EF7C9F2D8B32/LINUXMINT-22/6.8.0-48-GENERIC/X86_64/DF42F11E59>) |
| 8086:8c20 | 15d9:0805 | Intel            | 8 Series/C220 Series Chipset High... | 7     | snd_hda... | [A3DDA288D1](<Server/Supermicro/X10/X10SAE/FB4CD398216A/LINUXMINT-21.2/5.15.0-91-GENERIC/X86_64/A3DDA288D1>) |
| 8086:a1f0 | 103c:81c7 | Intel            | Lewisburg MROM 0                     | 7     | snd_hda... | [03E2A5BAC1](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/5E9B675190B8/UBUNTU-22.04/6.2.0-37-GENERIC/X86_64/03E2A5BAC1>) |
| 8086:a1f0 | 1043:8724 | Intel            | Lewisburg MROM 0                     | 7     | snd_hda... | [664827DD6C](<Server/ASUSTek Computer/Pro/Pro WS C621-64L SAGE-10G Series/A1C444FAB774/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/664827DD6C>) |
| 8086:a348 | 15d9:1a1d | Intel            | Cannon Lake PCH cAVS                 | 7     | snd_hda... | [E63931ED4F](<Server/Supermicro/Super/Super Server/A6F8ADA06288/VOID-ROLLING/6.3.13_1/X86_64/E63931ED4F>) |
| 1002:9840 | 1002:9840 | AMD              | Kabini HDMI/DP Audio                 | 6     | snd_hda... | [826ECBEAD0](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/31AE83A243F5/UBUNTU-20.04/5.15.0-46-GENERIC/X86_64/826ECBEAD0>) |
| 1002:aae0 | 1028:aae0 | AMD              | Baffin HDMI/DP Audio [Radeon RX 5... | 6     | snd_hda... | [B86B3EAD94](<Server/Dell/PowerEdge/PowerEdge R810/DC9A8138124A/ROCKY-8.9/4.18.0-513.5.1.EL8_9.X86_64/X86_64/B86B3EAD94>) |
| 10de:0fbb | 10de:1153 | Nvidia           | GM204 High Definition Audio Contr... | 6     | snd_hda... | [172A6309DF](<Server/Tarox/ParX/ParX T100c G6 Server/24E1CEA11A00/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/172A6309DF>) |
| 10de:1aef | 10de:147d | Nvidia           | GA102 High Definition Audio Contr... | 6     | snd_hda... | [656B2E45C3](<Server/Supermicro/Super/Super Server/B5CC5EAAF621/OPENSUSE-LEAP-15.6/6.4.0-150600.23.17-DEFAULT/X86_64/656B2E45C3>) |
| 8086:4dc8 | 10ec:0000 | Intel            | Jasper Lake HD Audio                 | 6     | snd_hda... | [6B8F982987](<Server/GEEKOM/MiniAir/MiniAir 11/5E7475318C5E/UBUNTU-24.04/6.8.0-35-GENERIC/X86_64/6B8F982987>) |
| 8086:51c8 | 1f55:0000 | Intel            | Alder Lake PCH-P High Definition ... | 6     | snd_hda... | [7CBAAA2380](<Server/GEEKOM/IT/IT12/1E2D35C7A82A/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/7CBAAA2380>) |
| 8086:a170 | 15d9:088b | Intel            | 100 Series/C230 Series Chipset Fa... | 6     | snd_hda... | [1CECE2A441](<Server/Supermicro/C7/C7H170-M/40203ADD6246/FEDORA-40/6.10.12-200.FC40.X86_64/X86_64/1CECE2A441>) |
| 8086:a170 | 15d9:0895 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     | snd_hda... | [23F3141732](<Server/Supermicro/Super/Super Server/C06149C5792E/UBUNTU-24.04/6.8.0-36-GENERIC/X86_64/23F3141732>) |
| 1002:aa98 | 1028:aa98 | AMD              | Caicos HDMI Audio [Radeon HD 6450... | 5     | snd_hda... | [976D5E0A08](<Server/Dell/PowerEdge/PowerEdge R720/B91188EAD5B9/UBUNTU-20.04/5.15.0-73-GENERIC/X86_64/976D5E0A08>) |
| 1002:aaf0 | 1002:aaf0 | AMD              | Ellesmere HDMI Audio [Radeon RX 4... | 5     | snd_hda... | [2554F52D5C](<Server/Supermicro/C7/C7Z170-M/6706484E9311/ROSA-12.5.1/6.6.27-GENERIC-3ROSA2021.1-X86_64/X86_64/2554F52D5C>) |
| 1022:1487 | 1849:d264 | AMD              | Starship/Matisse HD Audio Controller | 5     | snd_hda... | [9F3633CAA8](<Server/ASRockRack/X570/X570D4U-2L2T-BCM/1ABB0156B2C9/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/9F3633CAA8>) |
| 10de:0e0f | 1462:8a9f | Nvidia           | GK208 HDMI/DP Audio Controller       | 5     | snd_hda... | [D7AED73C92](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/34F529CFFE51/UBUNTU-20.04/5.6.0-1018-OEM/X86_64/D7AED73C92>) |

### Storage (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1077:2532 | 1077:015d | QLogic           | ISP2532-based 8Gb Fibre Channel t... | 21    | qla2xxx    | [40BB0B1415](<Server/Fujitsu/PRIMERGY/PRIMERGY RX200 S8/1DC23A737F38/DEBIAN-12/6.8.12-4-PVE/X86_64/40BB0B1415>) |
| 11f8:8032 |           | PMC-Sierra       | PM8032 Tachyon QE8                   | 7     |            | [F44D953566](<Server/IBM/System/System x3650 M4: -[2145DH8]-/D19C902B5426/ARCH-ROLLING/6.9.3-ARCH1-1/X86_64/F44D953566>) |
| 10df:f100 | 10df:f100 | Emulex           | LPe12000 Series 8Gb Fibre Channel... | 6     | lpfc       | [7C45C3FDC9](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2530 M1/3CE2488F0609/UBUNTU-24.04/6.8.0-40-GENERIC/X86_64/7C45C3FDC9>) |
| 10df:f400 | 10df:f410 | Emulex           | LPe35000/LPe36000 Series 32Gb/64G... | 6     | lpfc       | [F73AE91625](<Server/Dell/PowerEdge/PowerEdge R7625/85D8E20875A1/UBUNTU-20.04/5.4.0-156-GENERIC/X86_64/F73AE91625>) |
| 10df:f0e5 | 10df:f0e5 | Emulex           | Zephyr LightPulse Fibre Channel H... | 4     | lpfc       | [73B5A8C763](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/1567E7B66486/UBUNTU-20.04/5.4.0-137-GENERIC/X86_64/73B5A8C763>) |
| 10df:f100 | 103c:338f | Emulex           | LPe12000 Series 8Gb Fibre Channel... | 4     | lpfc       | [03CE72541E](<Server/Hewlett-Packard/ProLiant/ProLiant BL460c Gen8/C2E6DBC32789/CYBER-INFRASTRUCTURE-6.0.1/3.10.0-1160.105.1.AIP7.214.3/X86_64/03CE72541E>) |
| 11f8:8032 | 117c:003b | PMC-Sierra       | PM8032 Tachyon QE8                   | 4     | celerit... | [8E1DEB831F](<Server/Dell/PowerEdge/PowerEdge T640/0B98FFB4DAB4/CENTOS-9/5.14.0-333.EL9.X86_64/X86_64/8E1DEB831F>) |
| 1077:2031 | 1077:0249 | QLogic           | ISP8324-based 16Gb Fibre Channel ... | 3     | qla2xxx    | [41DF429035](<Server/3Logic Group/Server/Server Graviton/1E34987A2608/RED-OS-7.3/6.1.52-1.EL7.3.X86_64/X86_64/41DF429035>) |
| 1077:2432 | 1077:0137 | QLogic           | ISP2432-based 4Gb Fibre Channel t... | 3     | qla2xxx    | [B85DBD88F5](<Server/IBM/System/System x3650 M2 -[7947AC1]-/B4AFB5C90D39/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/B85DBD88F5>) |
| 1077:2532 | 1077:015c | QLogic           | ISP2532-based 8Gb Fibre Channel t... | 3     | qla2xxx    | [05B7C13538](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/38DF42BD22E8/DEBIAN-12/6.5.11-7-PVE/X86_64/05B7C13538>) |
| 1077:2532 | 1077:015e | QLogic           | ISP2532-based 8Gb Fibre Channel t... | 3     | qla2xxx    | [A60CF74303](<Server/Others/04N3DF/04N3DF A11/5E891354636F/DEBIAN-12/6.8.12-1-PVE/X86_64/A60CF74303>) |
| 1077:2031 | 1077:0257 | QLogic           | ISP8324-based 16Gb Fibre Channel ... | 2     | qla2xxx    | [E0BD072160](<Server/Dell/PowerEdge/PowerEdge R740/59332F4730C8/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/E0BD072160>) |
| 1077:2261 | 1077:02af | QLogic           | ISP2722-based 16/32Gb Fibre Chann... | 2     | qla2xxx    | [DC3EA6DBB8](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 -[7X06CTO1WW]-/447F1CAA9701/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/DC3EA6DBB8>) |
| 1077:2261 | 1590:00fa | QLogic           | ISP2722-based 16/32Gb Fibre Chann... | 2     | qla2xxx    | [CD4212E565](<Server/HPE/ProLiant/ProLiant DL360 Gen10/846234757CD7/UBUNTU-22.04/6.5.0-15-GENERIC/X86_64/CD4212E565>) |
| 1077:2432 | 103c:7040 | QLogic           | ISP2432-based 4Gb Fibre Channel t... | 2     | qla2xxx    | [6CCFA104A6](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/1118CE7EE8C7/ROSA-8.3/4.18.0-477.15.1.EL8_8.X86_64/X86_64/6CCFA104A6>) |
| 1077:2432 | 103c:7041 | QLogic           | ISP2432-based 4Gb Fibre Channel t... | 2     | qla2xxx    | [3BF8EDF992](<Server/Others/A/A06/03B41DA567E8/RHEL-8/4.18.0-348.12.2.EL8_5.X86_64/X86_64/3BF8EDF992>) |
| 1077:2432 | 1077:0138 | QLogic           | ISP2432-based 4Gb Fibre Channel t... | 2     | qla2xxx    | [1D2875A6FC](<Server/Intel/WHITLEY/WHITLEY/C00E3024712A/CYBER-INFRASTRUCTURE-5.5.0/3.10.0-1160.90.1.AIP7.200.7.1/X86_64/1D2875A6FC>) |
| 10df:e300 | 10df:e310 | Emulex           | LPe31000/LPe32000 Series 16Gb/32G... | 2     | lpfc       | [00FB2051A8](<Server/OpenYard/RS201/RS201I/143EE93F1249/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/00FB2051A8>) |
| 1aed:2001 | 1590:006f | SanDisk          | ioDrive2                             | 2     |            | [D9B96BCE95](<Server/Supermicro/Super/Super Server/909986EADB14/UBUNTU-22.10/5.19.0-23-GENERIC/X86_64/D9B96BCE95>) |
| 1aed:2001 | 1aed:2001 | SanDisk          | ioDrive2                             | 2     |            | [26B693742E](<Server/Dell/PowerEdge/PowerEdge R810/A7C91C5C7A32/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/26B693742E>) |
| 1000:0646 | 1000:1020 | Broadcom / LSI   | FC949ES Fibre Channel Adapter        | 1     | mptfc      | [8F6E544820](<Server/Sun Microsystems/Sun/Sun Fire X4270 SERVER/38FCB3A1E58B/FEDORA-34/5.11.11-300.FC34.X86_64/X86_64/8F6E544820>) |
| 1000:0646 | 1000:1240 | Broadcom / LSI   | FC949ES Fibre Channel Adapter        | 1     |            | [107B5509E6](<Server/Dell/PowerEdge/PowerEdge R210/42576B36F606/FEDORA-35/5.4.198-300.FC35.X86_64/X86_64/107B5509E6>) |
| 1000:c010 | 1000:00b2 | Broadcom / LSI   | PEX880xx PCIe Gen 4 Switch           | 1     |            | [0EFF104F09](<Server/Supermicro/AS/AS -4124GS-TNR/7104941B4991/UBUNTU-20.04/5.10.73-RT54/X86_64/0EFF104F09>) |
| 1077:2031 | 103c:17e8 | QLogic           | ISP8324-based 16Gb Fibre Channel ... | 1     | qla2xxx    | [EE529E06FF](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/C3B22E1F3C53/UBUNTU-24.04/6.8.0-47-GENERIC/X86_64/EE529E06FF>) |
| 1077:2031 | 103c:1939 | QLogic           | ISP8324-based 16Gb Fibre Channel ... | 1     | qla2xxx    | [9036136416](<Server/Hewlett-Packard/Superdome2/Superdome2 16s x86/777124CB43C9/ROSA-SX-CHROME-1.0/2.6.32-504.EL6.X86_64/X86_64/9036136416>) |
| 1077:2031 | 1077:0241 | QLogic           | ISP8324-based 16Gb Fibre Channel ... | 1     | qla2xxx    | [D791606410](<Server/Supermicro/X9/X9DRD-7LN4F-X9DRD-EF/1932E0848226/ROCKY-9.4/5.14.0-427.16.1.EL9_4.X86_64/X86_64/D791606410>) |
| 1077:2281 | 1077:02f3 | QLogic           | ISP2812-based 64/32G Fibre Channe... | 1     | qla2xxx    | [77F946C99B](<Server/Dell/PowerEdge/PowerEdge R7525/ED52A1D54F9D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/77F946C99B>) |
| 1077:2312 | 1077:0100 | QLogic           | ISP2312-based 2Gb Fibre Channel t... | 1     | qla2xxx    | [40F9D31598](<Server/Dell/PowerEdge/PowerEdge 2850/8C9CA6088BC7/CENTOS-6/2.6.32-754.30.2.EL6.X86_64/X86_64/40F9D31598>) |
| 1077:2432 | 103c:1705 | QLogic           | ISP2432-based 4Gb Fibre Channel t... | 1     | qla2xxx    | [DC4AC74B49](<Server/Hewlett-Packard/ProLiant/ProLiant BL685c G7/3F69ABE6ED6B/OPENSUSE-LEAP-15.2/5.3.18-LP152.60-DEFAULT/X86_64/DC4AC74B49>) |
| 1077:2532 | 103c:3261 | QLogic           | ISP2532-based 8Gb Fibre Channel t... | 1     | qla2xxx    | [04CE60AD90](<Server/Hewlett-Packard/ProLiant/ProLiant BL460c G7/125A512DC57A/UBUNTU-22.04/6.8.0-49-GENERIC/X86_64/04CE60AD90>) |
| 1077:2532 | 103c:3262 | QLogic           | ISP2532-based 8Gb Fibre Channel t... | 1     | qla2xxx    | [90CE2B0711](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/A8DA802364DF/MX-21/6.6.0-CUSTOM/X86_64/90CE2B0711>) |
| 1077:2532 | 1077:0171 | QLogic           | ISP2532-based 8Gb Fibre Channel t... | 1     | qla2xxx    | [4F5756D065](<Server/Oracle/Sun/Sun Fire X4270 M2 SERVER/FF52124EF1E7/FEDORA-32/5.8.12-200.FC32.X86_64/X86_64/4F5756D065>) |
| 1077:2532 | 1077:0176 | QLogic           | ISP2532-based 8Gb Fibre Channel t... | 1     | qla2xxx    | [D7CBC31CEE](<Server/IBM/BladeCenter/BladeCenter HS23 -[7875MFM]-/D5DD0E377016/RELS-6.9/2.6.32-696.EL6.X86_64/X86_64/D7CBC31CEE>) |
| 1077:8021 | 1077:0229 | QLogic           | 8200 Series 10GbE Converged Netwo... | 1     | qla2xxx    | [FAC0FDC118](<Server/Dell/PowerEdge/PowerEdge R720/D51711BBFDE5/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/FAC0FDC118>) |
| 10df:e200 | 10df:e280 | Emulex           | LPe15000/LPe16000 Series 8Gb/16Gb... | 1     | lpfc       | [22855916DE](<Server/HUAWEI/1288H/1288H V5/C98B42F4F0E0/DEBIAN-12/6.8.4-3-PVE/X86_64/22855916DE>) |
| 10df:e300 | 10df:e300 | Emulex           | LPe31000/LPe32000 Series 16Gb/32G... | 1     | lpfc       | [A2CE10373E](<Server/Graviton/S2122/S2122IU/ED2248ACB950/ROSA-12/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/A2CE10373E>) |
| 10df:e300 | 10df:e380 | Emulex           | LPe31000/LPe32000 Series 16Gb/32G... | 1     | lpfc       | [DAA3DF0F31](<Server/IBM/FAB2/FAB2 Controller/4957F7FD2B12/RHEL-8/4.18.0-477.10.1.EL8_8.X86_64/X86_64/DAA3DF0F31>) |
| 10df:f100 | 103c:3282 | Emulex           | LPe12000 Series 8Gb Fibre Channel... | 1     | lpfc       | [23F12250E5](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/C92D3D39B250/RHEL-8/4.18.0-240.22.1.EL8_3.X86_64/X86_64/23F12250E5>) |
| 10df:fc40 | 10df:fc42 | Emulex           | Saturn-X: LightPulse Fibre Channe... | 1     |            | [C83BA710F9](<Server/Quanta/D51/D51B-2U/ED213C10A885/FEDORA-39/6.6.12-200.FC39.X86_64/X86_64/C83BA710F9>) |
| 10df:fe00 | 10df:fe00 | Emulex           | Zephyr-X LightPulse Fibre Channel... | 1     | lpfc       | [6806624961](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G6/97C666008E4E/UBUNTU-18.04/4.15.0-50-GENERIC/X86_64/6806624961>) |
| 1137:0045 | 1137:012e | Cisco Systems    | VIC FCoE HBA                         | 1     | fnic       | [BAF3069CD7](<Server/Cisco Systems/UCSC-C220/UCSC-C220-M4S/9D3781D2096F/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/BAF3069CD7>) |
| 117c:0064 | 117c:0064 | ATTO Technology  | Celerity FC 16Gb/s Gen 5 Fibre Ch... | 1     |            | [43EE2001E1](<Server/AIC/SB302/SB302-LB/77AF6612F1D7/CENTOS-7/3.10.0-1062.4.1.EL7.X86_64/X86_64/43EE2001E1>) |
| 11f8:8032 | 117c:003a | PMC-Sierra       | PM8032 Tachyon QE8                   | 1     | celerit... | [5315690568](<Server/Supermicro/SYS-5018/SYS-5018D-FN8T/3DFAD0AEC112/UBUNTU-18.04/4.15.0-55-GENERIC/X86_64/5315690568>) |
| 11f8:8032 | 117c:003c | PMC-Sierra       | PM8032 Tachyon QE8                   | 1     | celerit... | [A3E30CA34E](<Server/Silicon Mechanics/iPC-12/iPC-12-210/4DEF485089A2/UBUNTU-24.04/6.8.0-38-GENERIC/X86_64/A3E30CA34E>) |
| 1425:6607 | 1425:0000 | Chelsio Commu... | T62100-LP-CR Unified Wire Storage... | 1     |            | [1126AE11AE](<Server/ASUSTek Computer/Z11PG-D16/Z11PG-D16 Series/9878F56186D3/DEBIAN-9/4.9.35-DYVI/X86_64/1126AE11AE>) |
| 1657:0013 | 103c:1742 | Cavium QLogic    | 425/825/42B/82B 4Gbps/8Gbps PCIe ... | 1     |            | [7911C68EB5](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/1118CE7EE8C7/ROSA-8.3/4.18.0-477.15.1.EL8_8.X86_64/X86_64/7911C68EB5>) |
| 19a2:0702 | 103c:3314 | Emulex           | OneConnect 10Gb iSCSI Initiator      | 1     | be2iscsi   | [DC4AC74B49](<Server/Hewlett-Packard/ProLiant/ProLiant BL685c G7/3F69ABE6ED6B/OPENSUSE-LEAP-15.2/5.3.18-LP152.60-DEFAULT/X86_64/DC4AC74B49>) |
| 19a2:0704 | 103c:174b | Emulex           | OneConnect OCe10100/OCe10102 Seri... | 1     | lpfc       | [E707BBA6A9](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G7/941269F514A4/UBUNTU-18.04/4.15.0-91-GENERIC/X86_64/E707BBA6A9>) |
| 19a2:0712 | 103c:3344 | Emulex           | OneConnect 10Gb iSCSI Initiator (... | 1     |            | [BCD4E93239](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/35A8854EC380/CENTOS-8/4.18.0-500.EL8.X86_64/X86_64/BCD4E93239>) |
| 19a2:0712 | 103c:337b | Emulex           | OneConnect 10Gb iSCSI Initiator (... | 1     | be2iscsi   | [9F21E5D9D9](<Server/Hewlett-Packard/ProLiant/ProLiant BL460c Gen8/1DB9D4472AA8/ARCH-ROLLING/5.10.79-1-LTS/X86_64/9F21E5D9D9>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a182 | 8086:7270 | Intel            | C620 Series Chipset Family SATA C... | 92    | ahci       | [122B21A8E4](<Server/Others/Others/Others/DB0155950DC6/DEBIAN-12/6.8.12-5-PVE/X86_64/122B21A8E4>) |
| 8086:a1d2 | 8086:7270 | Intel            | C620 Series Chipset Family SSATA ... | 81    | ahci       | [122B21A8E4](<Server/Others/Others/Others/DB0155950DC6/DEBIAN-12/6.8.12-5-PVE/X86_64/122B21A8E4>) |
| 1022:7901 | 15d9:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 53    | ahci       | [726B65D6E8](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.10/4.18.0-553.27.1.EL8_10.X86_64/X86_64/726B65D6E8>) |
| 1022:7901 | 1022:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 44    | ahci       | [9F3633CAA8](<Server/ASRockRack/X570/X570D4U-2L2T-BCM/1ABB0156B2C9/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/9F3633CAA8>) |
| 8086:1d02 | 15d9:0636 | Intel            | C600/X79 series chipset 6-Port SA... | 37    | ahci       | [86B4E152AD](<Server/Supermicro/X9/X9DRW/D2C6B0237967/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/86B4E152AD>) |
| 8086:8d02 | 8086:7270 | Intel            | C610/X99 series chipset 6-Port SA... | 32    | ahci       | [142EA5AAAB](<Server/Lenovo/70FRR156CN/70FRR156CN RD450X/8535AF5D51BA/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/142EA5AAAB>) |
| 8086:3a22 | 15d9:0600 | Intel            | 82801JI (ICH10 Family) SATA AHCI ... | 31    | ahci       | [6918605D42](<Server/Supermicro/X8/X8DTU/2EC017791B11/DEBIAN-12/6.8.12-5-PVE/X86_64/6918605D42>) |
| 8086:1d02 | 1028:048c | Intel            | C600/X79 series chipset 6-Port SA... | 30    | ahci       | [D63ADBC5DD](<Server/Dell/PowerEdge/PowerEdge R720/13A7060552FC/NIXOS-25.05/6.6.63/X86_64/D63ADBC5DD>) |
| 8086:8d02 | 103c:8030 | Intel            | C610/X99 series chipset 6-Port SA... | 30    | ahci       | [DC8278F9CE](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/A1AD06C117B0/DEBIAN-12/6.8.12-1-PVE/X86_64/DC8278F9CE>) |
| 8086:8d62 | 8086:7270 | Intel            | C610/X99 series chipset sSATA Con... | 30    | ahci       | [142EA5AAAB](<Server/Lenovo/70FRR156CN/70FRR156CN RD450X/8535AF5D51BA/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/142EA5AAAB>) |
| 8086:a1d2 | 1028:073a | Intel            | C620 Series Chipset Family SSATA ... | 29    | ahci       | [B75294443B](<Server/Dell/Precision/Precision 7920 Tower/5E36FA18A2AE/KUBUNTU-20.04/5.15.0-84-GENERIC/X86_64/B75294443B>) |
| 8086:1d02 | 103c:18a9 | Intel            | C600/X79 series chipset 6-Port SA... | 28    | ahci       | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |
| 8086:1d02 | 1043:84ef | Intel            | C600/X79 series chipset 6-Port SA... | 27    | ahci       | [E805BE0AAC](<Server/Kraftway/GEG/GEG/C4E325834440/DEBIAN-12/6.1.0-27-AMD64/X86_64/E805BE0AAC>) |
| 8086:a1d2 | 15d9:0967 | Intel            | C620 Series Chipset Family SSATA ... | 27    | ahci       | [01602FD84E](<Server/Supermicro/SYS-6019/SYS-6019P-WTR/0C2A376E8BE8/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/01602FD84E>) |
| 8086:a102 | 8086:7270 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 24    | ahci       | [172A6309DF](<Server/Tarox/ParX/ParX T100c G6 Server/24E1CEA11A00/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/172A6309DF>) |
| 1022:43f6 | 1b21:1062 | AMD              | 600 Series Chipset SATA Controller   | 21    | ahci       | [EE0C91380E](<Server/ASRockRack/B650/B650D4U-2L2T-BCM/4E50B00275AF/ALMA-8.10/4.18.0-553.33.1.EL8_10.X86_64/X86_64/EE0C91380E>) |
| 1022:7901 | 1458:1000 | AMD              | FCH SATA Controller [AHCI mode]      | 19    | ahci       | [5F638CAF1F](<Server/Gigabyte Technology/G292/G292-Z20-00/38987F4940DE/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/5F638CAF1F>) |
| 8086:8d02 | 1028:0601 | Intel            | C610/X99 series chipset 6-Port SA... | 19    | ahci       | [44126F8D86](<Server/Dell/PowerEdge/PowerEdge R630/23D674735CB9/GENTOO-2.15/6.6.38-GENTOO-MANS/X86_64/44126F8D86>) |
| 8086:8d62 | 1028:0601 | Intel            | C610/X99 series chipset sSATA Con... | 19    | ahci       | [44126F8D86](<Server/Dell/PowerEdge/PowerEdge R630/23D674735CB9/GENTOO-2.15/6.6.38-GENTOO-MANS/X86_64/44126F8D86>) |
| 1b4b:9230 | 1b4b:9230 | Marvell Techn... | 88SE9230 PCIe 2.0 x2 4-port SATA ... | 18    | ahci       | [6918605D42](<Server/Supermicro/X8/X8DTU/2EC017791B11/DEBIAN-12/6.8.12-5-PVE/X86_64/6918605D42>) |
| 8086:a182 | 1028:0715 | Intel            | C620 Series Chipset Family SATA C... | 18    | ahci       | [FD86EE3128](<Server/Dell/PowerEdge/PowerEdge R740/437663FE9CF6/UBUNTU-24.04/6.8.0-47-GENERIC/X86_64/FD86EE3128>) |
| 8086:a1d2 | 1028:0715 | Intel            | C620 Series Chipset Family SSATA ... | 18    | ahci       | [FD86EE3128](<Server/Dell/PowerEdge/PowerEdge R740/437663FE9CF6/UBUNTU-24.04/6.8.0-47-GENERIC/X86_64/FD86EE3128>) |
| 8086:1d02 | 1028:04fa | Intel            | C600/X79 series chipset 6-Port SA... | 16    | ahci       | [B416E87C4A](<Server/Dell/PowerEdge/PowerEdge T320/7C98CB79C6C7/OPENMANDRIVA-24.09/6.11.0-DESKTOP-2OMV2490/X86_64/B416E87C4A>) |
| 8086:8d02 | 15d9:0821 | Intel            | C610/X99 series chipset 6-Port SA... | 16    | ahci       | [34DDE21779](<Server/transtec/CALLEO/CALLEO/ABD07D26A4AA/RHCOS-4.16/5.14.0-427.24.1.EL9_4.X86_64/X86_64/34DDE21779>) |
| 8086:a1d2 | 1458:1000 | Intel            | C620 Series Chipset Family SSATA ... | 16    | ahci       | [F76FC4031D](<Server/PSSC Labs/SS4000/SS4000HD/13084E646FAA/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/F76FC4031D>) |
| 1b4b:9230 | 1028:1fe2 | Marvell Techn... | 88SE9230 PCIe 2.0 x2 4-port SATA ... | 15    | ahci       | [E87C223500](<Server/Dell/PowerEdge/PowerEdge R740xd2/B6A360938137/CENTOS-9/5.14.0-333.EL9.X86_64/X86_64/E87C223500>) |
| 8086:3a22 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) SATA AHCI ... | 15    | ahci       | [337DC9A775](<Server/Supermicro/X8/X8DTL/0C862FB30BE8/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/337DC9A775>) |
| 8086:8d62 | 15d9:0821 | Intel            | C610/X99 series chipset sSATA Con... | 15    | ahci       | [34DDE21779](<Server/transtec/CALLEO/CALLEO/ABD07D26A4AA/RHCOS-4.16/5.14.0-427.24.1.EL9_4.X86_64/X86_64/34DDE21779>) |
| 1b21:0612 | 1b21:1060 | ASMedia Techn... | ASM1061/ASM1062 Serial ATA Contro... | 14    | ahci       | [F4A02ED514](<Server/MSI/MSIS/MSIS366/66AA7EB4825A/UBUNTU-20.04/5.15.0-124-GENERIC/X86_64/F4A02ED514>) |
| 8086:1c02 | 1028:04de | Intel            | 6 Series/C200 Series Chipset Fami... | 14    | ahci       | [11BECE0A30](<Server/Dell/PowerEdge/PowerEdge T110 II/0DB321514907/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/11BECE0A30>) |
| 8086:1d02 | 15d9:0626 | Intel            | C600/X79 series chipset 6-Port SA... | 14    | ahci       | [39232DFDE3](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/B0C1ED30C610/DEBIAN-12/6.1.0-25-AMD64/X86_64/39232DFDE3>) |
| 8086:8d62 | 19e5:2062 | Intel            | C610/X99 series chipset sSATA Con... | 14    | ahci       | [EDA2D8550F](<Server/HUAWEI/RH1288/RH1288 V3/899B0DE1B12F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/EDA2D8550F>) |
| 8086:a182 | 1043:871e | Intel            | C620 Series Chipset Family SATA C... | 14    | ahci       | [664827DD6C](<Server/ASUSTek Computer/Pro/Pro WS C621-64L SAGE-10G Series/A1C444FAB774/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/664827DD6C>) |
| 8086:a182 | 15d9:0967 | Intel            | C620 Series Chipset Family SATA C... | 14    | ahci       | [01602FD84E](<Server/Supermicro/SYS-6019/SYS-6019P-WTR/0C2A376E8BE8/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/01602FD84E>) |
| 1002:4391 | 1002:4391 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 13    | ahci       | [683A6AEB9D](<Server/Hewlett-Packard/ProLiant/ProLiant DL165 G7/7792B2C8D06D/UBUNTU-24.04/6.8.0-35-GENERIC/X86_64/683A6AEB9D>) |
| 1b21:0612 | 15d9:1b2b | ASMedia Techn... | ASM1061/ASM1062 Serial ATA Contro... | 13    | ahci       | [4235F71014](<Server/Supermicro/AS/AS -1014S-WTRT/4126E18782A7/CYBER-INFRASTRUCTURE-6.5.0/3.10.0-1160.114.2.AIP7.222.1/X86_64/4235F71014>) |
| 8086:1c02 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 13    | ahci       | [969B046986](<Server/Dell/PowerEdge/PowerEdge R210 II/93E843E2F825/UBUNTU-22.04/5.15.0-124-GENERIC/X86_64/969B046986>) |
| 8086:1d02 | 1028:04ce | Intel            | C600/X79 series chipset 6-Port SA... | 13    | ahci       | [33A45E355F](<Server/Dell/PowerEdge/PowerEdge R620/C7F9C68EF445/CENTOS-6/2.6.32-754.33.1.EL6.X86_64/X86_64/33A45E355F>) |
| 8086:1d02 | 152d:899b | Intel            | C600/X79 series chipset 6-Port SA... | 13    | ahci       | [7E09CCDA22](<Server/ETegro Technologies/Hyperion/Hyperion RS125 G4/5259A72AB62F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/7E09CCDA22>) |
| 8086:51d3 |           | Intel            | Alder Lake-P SATA AHCI Controller    | 13    | ahci       | [DF42F11E59](<Server/GEEKOM/GT13/GT13 Pro/EF7C9F2D8B32/LINUXMINT-22/6.8.0-48-GENERIC/X86_64/DF42F11E59>) |
| 8086:8d02 | 15d9:0831 | Intel            | C610/X99 series chipset 6-Port SA... | 13    | ahci       | [2BAD48B8D4](<Server/Silicon Mechanics/Rackform/Rackform R309.v5/8442C8D36737/DEBIAN-12/6.1.0-21-AMD64/X86_64/2BAD48B8D4>) |
| 8086:8d02 | 19e5:2062 | Intel            | C610/X99 series chipset 6-Port SA... | 13    | ahci       | [EDA2D8550F](<Server/HUAWEI/RH1288/RH1288 V3/899B0DE1B12F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/EDA2D8550F>) |
| 8086:a102 | 15d9:089a | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 13    | ahci       | [85E2DD189C](<Server/Supermicro/Super/Super Server/2FA87A9B8E2E/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/85E2DD189C>) |
| 8086:1d02 | 1014:1d02 | Intel            | C600/X79 series chipset 6-Port SA... | 12    | ahci       | [128986423A](<Server/IBM/System/System x3650 M4 -[7915E1G]-/605DCB19505B/CENTOS-6/2.6.32-696.20.1.EL6.X86_64/X86_64/128986423A>) |
| 8086:a182 | 17aa:1038 | Intel            | C620 Series Chipset Family SATA C... | 12    | ahci       | [CAFAEE2FC7](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC000QGE/C9B0658BA91C/DEBIAN-12/6.1.0-28-AMD64/X86_64/CAFAEE2FC7>) |
| 8086:a1d2 | 17aa:1038 | Intel            | C620 Series Chipset Family SSATA ... | 12    | ahci       | [CAFAEE2FC7](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC000QGE/C9B0658BA91C/DEBIAN-12/6.1.0-28-AMD64/X86_64/CAFAEE2FC7>) |
| 1002:4390 | 1028:0444 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 11    | ahci       | [2D3D5673E7](<Server/Dell/PowerEdge/PowerEdge R815/6B72BADC37CC/UBUNTU-22.04/5.15.0-119-GENERIC/X86_64/2D3D5673E7>) |
| 8086:1c02 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 11    | ahci       | [69CCB9B978](<Server/Intel/S1200/S1200BTL/8EF10894528C/UBUNTU-22.04/6.5.0-35-GENERIC/X86_64/69CCB9B978>) |
| 8086:1d02 | 15d9:062b | Intel            | C600/X79 series chipset 6-Port SA... | 11    | ahci       | [F3D2F362E8](<Server/Supermicro/X9/X9SRE-X9SRE-3F-X9SRi-X9SRi-3F/55A635F4E92C/DEBIAN-12/6.8.8-2-PVE/X86_64/F3D2F362E8>) |
| 8086:8c02 | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 11    | ahci       | [3E9BE7A949](<Server/Supermicro/Super/Super Server/CE1321EEE3B9/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/3E9BE7A949>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1d00 | 103c:18a9 | Intel            | C600/X79 series chipset 4-Port SA... | 62    | pata_acpi  | [EDAE721CCD](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/2EAEE8C0C88F/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/EDAE721CCD>) |
| 8086:3a20 | 103c:330d | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 41    | pata_acpi  | [B076CBF109](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/416C8912B3CC/DEBIAN/6.11.10-AMD64/X86_64/B076CBF109>) |
| 8086:a1bc | 1028:073a | Intel            | C620 Series Chipset Family IDE Re... | 29    | pata_acpi  | [B75294443B](<Server/Dell/Precision/Precision 7920 Tower/5E36FA18A2AE/KUBUNTU-20.04/5.15.0-84-GENERIC/X86_64/B75294443B>) |
| 8086:2921 | 1028:0235 | Intel            | 82801IB (ICH9) 2 port SATA Contro... | 28    | pata_acpi  | [1FD820B09B](<Server/Dell/PowerEdge/PowerEdge R710/20339C7414DA/DEBIAN-12/6.8.4-3-PVE/X86_64/1FD820B09B>) |
| 8086:2921 | 1028:0236 | Intel            | 82801IB (ICH9) 2 port SATA Contro... | 25    | pata_acpi  | [A2B12B6DA3](<Server/Dell/PowerEdge/PowerEdge R610/14D2A48FEC25/CENTOS-7/3.10.0-1160.11.1.EL7.X86_64/X86_64/A2B12B6DA3>) |
| 8086:269e | 103c:31fe | Intel            | 631xESB/632xESB IDE Controller       | 20    | pata_acpi  | [A72E4DEEF3](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G5/5395FD01B3EA/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/A72E4DEEF3>) |
| 8086:3a20 | 1014:3a20 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 20    | pata_acpi  | [3286B36B51](<Server/IBM/System/System x3650 M3 -[7945YBU]-/64198599779C/DEBIAN-12/6.8.12-1-PVE/X86_64/3286B36B51>) |
| 8086:3a26 | 1014:3a26 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 18    | pata_acpi  | [3286B36B51](<Server/IBM/System/System x3650 M3 -[7945YBU]-/64198599779C/DEBIAN-12/6.8.12-1-PVE/X86_64/3286B36B51>) |
| 8086:a1bc | 1028:0739 | Intel            | C620 Series Chipset Family IDE Re... | 16    | pata_acpi  | [BA0626CE0A](<Server/Dell/Precision/Precision 7820 Tower/3792A2743A38/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/BA0626CE0A>) |
| 8086:3a20 | 15d9:0600 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 15    | pata_acpi  | [1128E2A9FA](<Server/Supermicro/X8/X8DTU/D85AACC2195B/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/1128E2A9FA>) |
| 8086:3a26 | 15d9:0600 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 15    | pata_acpi  | [1128E2A9FA](<Server/Supermicro/X8/X8DTU/D85AACC2195B/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/1128E2A9FA>) |
| 8086:3b20 | 1028:02a4 | Intel            | 5 Series/3400 Series Chipset 4 po... | 14    | ata_pii... | [48E00D403A](<Server/Dell/PowerEdge/PowerEdge T310/0EAF01173A25/DEBIAN-12/6.6.32-PRODUCTION+TRUENAS/X86_64/48E00D403A>) |
| 8086:3b26 | 1028:02a4 | Intel            | 5 Series/3400 Series Chipset 2 po... | 14    | ata_pii... | [48E00D403A](<Server/Dell/PowerEdge/PowerEdge T310/0EAF01173A25/DEBIAN-12/6.6.32-PRODUCTION+TRUENAS/X86_64/48E00D403A>) |
| 8086:a1bc | 17aa:1038 | Intel            | C620 Series Chipset Family IDE Re... | 13    | pata_acpi  | [CAFAEE2FC7](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC000QGE/C9B0658BA91C/DEBIAN-12/6.1.0-28-AMD64/X86_64/CAFAEE2FC7>) |
| 197b:2368 | 197b:2368 | JMicron Techn... | JMB368 IDE controller                | 12    | pata_jm... | [CE40C8C96F](<Server/DEPO Computers/X8/X8DAH/6FED46D0B032/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/CE40C8C96F>) |
| 8086:269e | 1028:01b2 | Intel            | 631xESB/632xESB IDE Controller       | 11    | ata_piix   | [5DE4C4A538](<Server/Dell/PowerEdge/PowerEdge 2950/A7ED8CBDCF7D/LMDE-6/6.1.0-28-AMD64/X86_64/5DE4C4A538>) |
| 8086:3a20 | 8086:3a20 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 10    | ata_piix   | [A8B96E89F2](<Server/TYAN Computer/S/S7010/0C071F7B6B6A/XUBUNTU-20.04/5.15.0-73-GENERIC/X86_64/A8B96E89F2>) |
| 8086:3a20 | 1028:028c | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 9     | pata_acpi  | [A6838F51AF](<Server/Dell/PowerEdge/PowerEdge R410/8F2BA8E7E914/UBUNTU-22.04/5.15.0-107-GENERIC/X86_64/A6838F51AF>) |
| 8086:3a20 | 8086:34dc | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 9     | pata_acpi  | [D074A45CA2](<Server/Intel/S5500/S5500HCV/95ED43502548/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/D074A45CA2>) |
| 8086:3a26 | 1028:028c | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 9     | pata_acpi  | [A6838F51AF](<Server/Dell/PowerEdge/PowerEdge R410/8F2BA8E7E914/UBUNTU-22.04/5.15.0-107-GENERIC/X86_64/A6838F51AF>) |
| 8086:3a26 | 8086:34dc | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 9     | pata_acpi  | [D074A45CA2](<Server/Intel/S5500/S5500HCV/95ED43502548/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/D074A45CA2>) |
| 8086:3a26 | 8086:3a26 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 9     | ata_piix   | [A8B96E89F2](<Server/TYAN Computer/S/S7010/0C071F7B6B6A/XUBUNTU-20.04/5.15.0-73-GENERIC/X86_64/A8B96E89F2>) |
| 8086:2921 | 1028:0237 | Intel            | 82801IB (ICH9) 2 port SATA Contro... | 8     | pata_acpi  | [017C48FD55](<Server/Dell/PowerEdge/PowerEdge T610/3365AFC18135/DEBIAN-12/6.5.11-4-PVE/X86_64/017C48FD55>) |
| 8086:3a20 | 15d9:0007 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 8     | pata_acpi  | [3A09F1AB51](<Server/Supermicro/X8/X8DTT/C514A5A1A1C3/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/3A09F1AB51>) |
| 8086:3a26 | 15d9:0007 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 8     | pata_acpi  | [3A09F1AB51](<Server/Supermicro/X8/X8DTT/C514A5A1A1C3/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/3A09F1AB51>) |
| 8086:a1bc | 17aa:1037 | Intel            | C620 Series Chipset Family IDE Re... | 8     | ata_gen... | [301BFF683B](<Server/Lenovo/ThinkStation/ThinkStation P720 30BBS3H50D/215583F782C1/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.10.4-1-DEFAULT/X86_64/301BFF683B>) |
| 1002:439c | 103c:1773 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 7     | pata_at... | [5BB6B014BF](<Server/Hewlett-Packard/ProLiant/ProLiant DL385p Gen8/2A0018D2AAFA/DEBIAN-12/6.5.13-1-PVE/X86_64/5BB6B014BF>) |
| 8086:1d08 | 103c:18a9 | Intel            | C600/X79 series chipset 2-Port SA... | 7     | ata_pii... | [689A7F3CA3](<Server/Hewlett-Packard/ProLiant/ProLiant DL360e Gen8/A34AD0901046/UBUNTU-22.04/5.15.0-72-GENERIC/X86_64/689A7F3CA3>) |
| 8086:3a20 | 1028:028d | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 7     | pata_acpi  | [A35A094F7E](<Server/Dell/PowerEdge/PowerEdge T410/981EBE64D562/UBUNTU-22.04/5.15.0-126-GENERIC/X86_64/A35A094F7E>) |
| 8086:3a20 | 1028:02f1 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 7     | pata_acpi  | [0D6D6A6743](<Server/Dell/PowerEdge/PowerEdge R510/7E56EFD8FB93/DEBIAN-12/6.8.8-2-PVE/X86_64/0D6D6A6743>) |
| 8086:3a26 | 1028:028d | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 7     | pata_acpi  | [A35A094F7E](<Server/Dell/PowerEdge/PowerEdge T410/981EBE64D562/UBUNTU-22.04/5.15.0-126-GENERIC/X86_64/A35A094F7E>) |
| 8086:3a26 | 1028:02f1 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 7     | pata_acpi  | [0D6D6A6743](<Server/Dell/PowerEdge/PowerEdge R510/7E56EFD8FB93/DEBIAN-12/6.8.8-2-PVE/X86_64/0D6D6A6743>) |
| 1002:439c | 103c:3338 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 6     | pata_at... | [683A6AEB9D](<Server/Hewlett-Packard/ProLiant/ProLiant DL165 G7/7792B2C8D06D/UBUNTU-24.04/6.8.0-35-GENERIC/X86_64/683A6AEB9D>) |
| 1002:439c | 15d9:ab11 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 6     | pata_at... | [E673BAB21F](<Server/Supermicro/H8/H8QG6/539918058863/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/E673BAB21F>) |
| 8086:269e | 1028:01b3 | Intel            | 631xESB/632xESB IDE Controller       | 6     | pata_acpi  | [2E77448A7D](<Server/Dell/PowerEdge/PowerEdge 1950/9FAD7399F359/DEBIAN-11/5.15.74-1-PVE/X86_64/2E77448A7D>) |
| 8086:3a20 | 1734:1150 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 6     | ata_piix   | [DF81B53B94](<Server/Fujitsu/PRIMERGY/PRIMERGY TX300 S5/C75C8D396A0B/DEBIAN-11/5.15.158-2-PVE/X86_64/DF81B53B94>) |
| 8086:3a26 | 1734:114d | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 6     | ata_piix   | [DF81B53B94](<Server/Fujitsu/PRIMERGY/PRIMERGY TX300 S5/C75C8D396A0B/DEBIAN-11/5.15.158-2-PVE/X86_64/DF81B53B94>) |
| 8086:3b20 | 8086:34ec | Intel            | 5 Series/3400 Series Chipset 4 po... | 6     | pata_acpi  | [D735382568](<Server/HCL/S3420/S3420GPV/403EC13AAE26/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/D735382568>) |
| 8086:3b26 | 8086:34ec | Intel            | 5 Series/3400 Series Chipset 2 po... | 6     | pata_acpi  | [D735382568](<Server/HCL/S3420/S3420GPV/403EC13AAE26/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/D735382568>) |
| 1002:439c | 15d9:bc11 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 5     | pata_at... | [EF32C0C2CA](<Server/Supermicro/H8/H8DG6-H8DGi/8E20B1D3526C/UBUNTU-18.04/4.15.0-200-GENERIC/X86_64/EF32C0C2CA>) |
| 8086:2680 | 1028:01b3 | Intel            | 631xESB/632xESB/3100 Chipset SATA... | 5     | pata_acpi  | [2FF8924B15](<Server/Dell/PowerEdge/PowerEdge 1950/12946989497B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2FF8924B15>) |
| 8086:2921 | 1028:029b | Intel            | 82801IB (ICH9) 2 port SATA Contro... | 5     | ata_pii... | [D3DFB8B571](<Server/Dell/PowerEdge/PowerEdge T710/706DF62A3B8D/UBUNTU-23.04/6.2.0-33-GENERIC/X86_64/D3DFB8B571>) |
| 8086:3a20 | 1028:02d4 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 5     | pata_acpi  | [B86B3EAD94](<Server/Dell/PowerEdge/PowerEdge R810/DC9A8138124A/ROCKY-8.9/4.18.0-513.5.1.EL8_9.X86_64/X86_64/B86B3EAD94>) |
| 8086:3a20 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 5     | ata_pii... | [A3BE5CDF41](<Server/Supermicro/X8/X8DTL/26E707D77C6B/CENTOS-7/3.10.0-1160.83.1.EL7.X86_64/X86_64/A3BE5CDF41>) |
| 8086:3a20 | 15d9:0404 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 5     | pata_acpi  | [A8D1FC822F](<Server/DEPO Computers/X8/X8DT6/A59B91023B6B/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/A8D1FC822F>) |
| 8086:3a20 | 8086:34e2 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 5     | pata_acpi  | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 8086:3a26 | 15d9:0006 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 5     | ata_pii... | [A3BE5CDF41](<Server/Supermicro/X8/X8DTL/26E707D77C6B/CENTOS-7/3.10.0-1160.83.1.EL7.X86_64/X86_64/A3BE5CDF41>) |
| 8086:3a26 | 15d9:0404 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 5     | pata_acpi  | [A8D1FC822F](<Server/DEPO Computers/X8/X8DT6/A59B91023B6B/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/A8D1FC822F>) |
| 8086:3a26 | 8086:34e2 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 5     | pata_acpi  | [FDCE629C37](<Server/Intel/S5520/S5520SC/7A80895EEC2E/LINUXMINT-19.1/4.15.0-151-GENERIC/X86_64/FDCE629C37>) |
| 1002:439c | 1111:077c | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 4     | pata_at... | [9E0F4D41E2](<Server/AMD/AOPW-PLUS/AOPW-PLUS/25EF7D306164/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/9E0F4D41E2>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 101   | nvme       | [CAFAEE2FC7](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC000QGE/C9B0658BA91C/DEBIAN-12/6.1.0-28-AMD64/X86_64/CAFAEE2FC7>) |
| 144d:a80a | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 37    | nvme       | [CAFAEE2FC7](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC000QGE/C9B0658BA91C/DEBIAN-12/6.1.0-28-AMD64/X86_64/CAFAEE2FC7>) |
| 144d:a80a | 144d:a812 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 28    | nvme       | [4235F71014](<Server/Supermicro/AS/AS -1014S-WTRT/4126E18782A7/CYBER-INFRASTRUCTURE-6.5.0/3.10.0-1160.114.2.AIP7.222.1/X86_64/4235F71014>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 21    | nvme       | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980 (DRAM-less)  | 17    | nvme       | [CAFAEE2FC7](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC000QGE/C9B0658BA91C/DEBIAN-12/6.1.0-28-AMD64/X86_64/CAFAEE2FC7>) |
| 144d:a80a | 144d:a813 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 17    | nvme       | [08FE32BEB9](<Server/ASRockRack/ROMED8/ROMED8-2T-OVHA/6C847AA5821C/UBUNTU-22.04/5.15.0-73-GENERIC/X86_64/08FE32BEB9>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 13    | nvme       | [76C41C5097](<Server/Supermicro/X10/X10DRi/B47EB5B551E7/DEBIAN-12/6.1.0-26-AMD64/X86_64/76C41C5097>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT (DRAM-less) NVM... | 12    | nvme       | [122B21A8E4](<Server/Others/Others/Others/DB0155950DC6/DEBIAN-12/6.8.12-5-PVE/X86_64/122B21A8E4>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013-E13 PCIe3 NVMe Controller ... | 12    | nvme       | [A5CA58A104](<Server/EKF Elektronik/CompactPCI/CompactPCI Serial/89AAC1C97050/UBUNTU-24.04/6.8.0-47-GENERIC/X86_64/A5CA58A104>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 12    | nvme       | [CD58D1AEB6](<Server/Dell/PowerEdge/PowerEdge R630/BCFA5D7F8962/FEDORA-40/6.9.11-200.FC40.X86_64/X86_64/CD58D1AEB6>) |
| 8086:0a54 | 8086:4802 | Intel            | NVMe Datacenter SSD [3DNAND, Beta... | 12    | nvme       | [2561CC96C3](<Server/HuaXun Group Limited/SHARQ/SHARQ U628V2/65E5F738D053/DEBIAN-12/6.8.8-2-PVE/X86_64/2561CC96C3>) |
| 8086:f1a6 | 8086:390b | Intel            | SSD DC P4101/Pro 7600p/760p/E 610... | 12    | nvme       | [E43C302BA4](<Server/ThinkStation P920/30BDS0/30BDS0N700/E37D2DC96A1D/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/E43C302BA4>) |
| 8086:0a54 | 8086:4812 | Intel            | NVMe Datacenter SSD [3DNAND, Beta... | 11    | nvme       | [A2CE10373E](<Server/Graviton/S2122/S2122IU/ED2248ACB950/ROSA-12/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/A2CE10373E>) |
| 1987:5016 | 1987:5016 | Phison Electr... | E16 PCIe4 NVMe Controller            | 9     | nvme       | [89C105960A](<Server/ASRockRack/ROMED8/ROMED8-2T/3BC6540442E7/DEBIAN-12/6.1.0-26-AMD64/X86_64/89C105960A>) |
| 1e4b:1202 | 1e4b:1202 | MAXIO Technol... | NVMe SSD Controller MAP1202 (DRAM... | 9     | nvme       | [075693E3A5](<Server/Dell/Precision/Precision 7920 Tower/789891DFDA00/RHEL-9/5.14.0-427.26.1.EL9_4.X86_64/X86_64/075693E3A5>) |
| 126f:2262 | 126f:2262 | Silicon Motion   | SM2262/SM2262EN SSD Controller       | 8     | nvme       | [76C45A7A8A](<Server/ASRockRack/X570/X570D4U/6ADE942D8CE3/UBUNTU-20.04/5.4.0-150-GENERIC/X86_64/76C45A7A8A>) |
| 1344:5405 | 1344:0100 | Micron Techno... | 2300 NVMe SSD [Santana]              | 8     | nvme       | [A71DF974B6](<Server/ASRockRack/X570/X570D4U-2L2T/E7FFF5522462/DEBIAN-12/6.8.12-1-PVE/X86_64/A71DF974B6>) |
| 144d:a80c | 144d:a801 | Samsung Elect... | NVMe SSD Controller S4LV008[Pascal]  | 8     | nvme       | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |
| 15b7:5006 | 15b7:5006 | SanDisk          | Extreme Pro / WD Black SN750 / PC... | 8     | nvme       | [722F640CCD](<Server/Gigabyte Technology/MC12/MC12-LE0-00/37078BD0F3C1/UBUNTU-22.04/6.5.0-18-GENERIC/X86_64/722F640CCD>) |
| 15b7:501a | 15b7:501a | SanDisk          | Ultra 3D / WD Blue SN570 NVMe SSD... | 8     | nvme       | [6BE191DAD3](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/213E402D3EC3/ZORIN-17/6.8.0-48-GENERIC/X86_64/6BE191DAD3>) |
| 14a4:2300 | 1b4b:1093 | Lite-On Techn... | CA3-8D256, CA3-8D512 NVMe SSD        | 7     | nvme       | [735D113F73](<Server/Hewlett-Packard/ProLiant/ProLiant DL380e Gen8/4865ACA2339D/CLEAR-LINUX-OS-42390/6.10.10-1463.NATIVE/X86_64/735D113F73>) |
| 15b7:5002 | 15b7:5002 | SanDisk          | Extreme Pro / WD Black 2018/SN750... | 7     | nvme       | [E8D7ABA4FE](<Server/Lenovo/ThinkStation/ThinkStation P720 30BBS4RV00/DD019A7B6721/KUBUNTU-22.04/5.15.0-91-GENERIC/X86_64/E8D7ABA4FE>) |
| 1dee:1602 | 1dee:1602 | Biwin Storage... | Non-Volatile memory controller       | 7     | nvme       | [DF42F11E59](<Server/GEEKOM/GT13/GT13 Pro/EF7C9F2D8B32/LINUXMINT-22/6.8.0-48-GENERIC/X86_64/DF42F11E59>) |
| c0a9:540a | c0a9:5021 | Micron/Crucia... | P2 [Nick P2] / P3 / P3 Plus NVMe ... | 7     | nvme       | [2BC6C0E61B](<Server/Supermicro/Super/Super Server/AF36827D1D5F/DEBIAN-12/6.2.16-18-PVE/X86_64/2BC6C0E61B>) |
| 1179:011a | 1179:0001 | Toshiba Ameri... | XG6 NVMe SSD Controller              | 6     | nvme       | [45516ED3A7](<Server/Dell/Precision/Precision 7920 Tower/4910BAFAEC76/UBUNTU-22.04/5.15.0-106-GENERIC/X86_64/45516ED3A7>) |
| 15b7:5009 | 15b7:5009 | SanDisk          | Ultra 3D / WD PC SN530, IX SN530,... | 6     | nvme       | [CC642B859B](<Server/ASRockRack/Z690/Z690D4U-2L2T-G5/2A61D8CF253D/UBUNTU-22.04/6.1.55-X64V3-XANMOD1/X86_64/CC642B859B>) |
| 15b7:5017 | 15b7:5017 | SanDisk          | WD Black SN770 / PC SN740 256GB /... | 6     | nvme       | [CAFAEE2FC7](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC000QGE/C9B0658BA91C/DEBIAN-12/6.1.0-28-AMD64/X86_64/CAFAEE2FC7>) |
| 1987:5021 | 1987:5021 | Phison Electr... | PS5021-E21 PCIe4 NVMe Controller ... | 6     | nvme       | [7CBAAA2380](<Server/GEEKOM/IT/IT12/1E2D35C7A82A/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/7CBAAA2380>) |
| 2646:5013 | 2646:5013 | Kingston Tech... | KC3000/FURY Renegade NVMe SSD [E18]  | 6     | nvme       | [830FDBC722](<Server/Supermicro/Super/Super Server/FCCD9A3F161B/UBUNTU-22.04/5.15.0-91-GENERIC/X86_64/830FDBC722>) |
| 8086:2700 | 8086:3900 | Intel            | Optane SSD 900P Series               | 6     | nvme       | [D7AED73C92](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/34F529CFFE51/UBUNTU-20.04/5.6.0-1018-OEM/X86_64/D7AED73C92>) |
| 1344:51a2 | 1344:5000 | Micron Techno... | 7300 PRO NVMe SSD                    | 5     | nvme       | [DE3332B83C](<Server/Supermicro/SYS-6029/SYS-6029P-WTRT/35C50F3639E9/ACRONIS-CYBER-INFRASTRUCTURE-5.1.0/3.10.0-1160.53.1.VZ7.185.3/X86_64/DE3332B83C>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 5     | nvme       | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 15b7:5030 | 15b7:5030 | Sandisk          | WD Black SN850X NVMe SSD             | 5     | nvme       | [BC61F95204](<Server/ASRockRack/ALTRAD8/ALTRAD8UD-1L2T/33DCD26EDA10/UBUNTU-24.04/6.8.0-51-GENERIC/AARCH64/BC61F95204>) |
| 1f31:4512 | 1f31:4512 | Nextorage        | NE1N NVMe SSD                        | 5     | nvme       | [EE0C91380E](<Server/ASRockRack/B650/B650D4U-2L2T-BCM/4E50B00275AF/ALMA-8.10/4.18.0-553.33.1.EL8_10.X86_64/X86_64/EE0C91380E>) |
| 2646:500d | 2646:500d | Kingston Tech... | OM3PDP3 NVMe SSD                     | 5     | nvme       | [F30D39393C](<Server/BESSTAR Tech/X/X400/B2CBACACFA8F/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/F30D39393C>) |
| 8086:0953 | 8086:3702 | Intel            | PCIe Data Center SSD                 | 5     | nvme       | [B0100C59BB](<Server/Supermicro/Super/Super Server/E58401D9CAE3/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/B0100C59BB>) |
| 8086:0a54 | 1028:1fef | Intel            | NVMe Datacenter SSD [3DNAND, Beta... | 5     | nvme       | [EDA2D8550F](<Server/HUAWEI/RH1288/RH1288 V3/899B0DE1B12F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/EDA2D8550F>) |
| 8086:0b60 | 8086:9008 | Intel            | NVMe DC SSD [3DNAND, Sentinel Roc... | 5     | nvme       | [A7C07F57E4](<Server/ASRockRack/GENOAD12/GENOAD12M3-2Q-H/E6AC8C7FCE11/UBUNTU-20.04/5.4.0-173-GENERIC/X86_64/A7C07F57E4>) |
| c0a9:5412 | c0a9:0100 | Micron/Crucia... | P5 NVMe PCIe SSD[SlashP5]            | 5     | nvme       | [DE3332B83C](<Server/Supermicro/SYS-6029/SYS-6029P-WTRT/35C50F3639E9/ACRONIS-CYBER-INFRASTRUCTURE-5.1.0/3.10.0-1160.53.1.VZ7.185.3/X86_64/DE3332B83C>) |
| 1179:0116 | 1179:0001 | Toshiba Ameri... | XG5 NVMe SSD Controller              | 4     | nvme       | [5F638CAF1F](<Server/Gigabyte Technology/G292/G292-Z20-00/38987F4940DE/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/5F638CAF1F>) |
| 1344:51a2 | 1344:4000 | Micron Techno... | 7300 PRO NVMe SSD                    | 4     | nvme       | [18B2BF9FF4](<Server/Delta Computers/DSS-C621/DSS-C621LTG/EA1701537BF7/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/18B2BF9FF4>) |
| 1344:51b2 | 1344:5000 | Micron Techno... | 9300 MAX NVMe SSD                    | 4     | nvme       | [2BB4102B1C](<Server/Supermicro/Super/Super Server/45717F18B5CF/CENTOS-8/4.18.0-240.22.1.EL8_3.X86_64/X86_64/2BB4102B1C>) |
| 1b96:2400 | 1b96:0000 | Western Digital  | Ultrastar DC SN640 NVMe SSD          | 4     | nvme       | [E550577A60](<Server/Dell/PowerEdge/PowerEdge R750/D1750E589C22/UBUNTU-22.04/6.2.0-36-GENERIC/X86_64/E550577A60>) |
| 1c5c:174a | 1c5c:174a | SK hynix         | Gold P31/BC711/PC711 NVMe Solid S... | 4     | nvme       | [1CECE2A441](<Server/Supermicro/C7/C7H170-M/40203ADD6246/FEDORA-40/6.10.12-200.FC40.X86_64/X86_64/1CECE2A441>) |
| 2646:500a | 2646:500a | Kingston Tech... | DC1000B NVMe SSD [E12DC]             | 4     | nvme       | [F6563C2624](<Server/Gigabyte Technology/MP32/MP32-AR0/3E7CD5E49F69/ROSA-13.0/6.1.42-GENERIC-1ROSA2023.1-ARM64/AARCH64/F6563C2624>) |
| 2646:500f | 2646:500f | Kingston Tech... | NV1 NVMe SSD [SM2263XT] (DRAM-less)  | 4     | nvme       | [0B1FEB460C](<Server/Supermicro/SYS-6019/SYS-6019U-TN4R4T/51D2EF357A4F/ROCKY-9.2/5.14.0-284.18.1.EL9_2.X86_64/X86_64/0B1FEB460C>) |
| 2646:5017 | 2646:5017 | Kingston Tech... | NV2 NVMe SSD [SM2267XT] (DRAM-less)  | 4     | nvme       | [CA329A6038](<Server/Supermicro/Super/Super Server/1F76DDE31F47/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CA329A6038>) |
| 8086:0953 | 8086:3705 | Intel            | PCIe Data Center SSD                 | 4     | nvme       | [15B2418CE7](<Server/Supermicro/Super/Super Server/CB5581199B99/UBUNTU-20.04/5.4.0-198-GENERIC/X86_64/15B2418CE7>) |
| c0a9:540a | c0a9:540a | Micron/Crucia... | P2 [Nick P2] / P3 / P3 Plus NVMe ... | 4     | nvme       | [36DA660B8B](<Server/Supermicro/Super/Super Server/D88157B0FA32/GENTOO-2.15/6.6.51-GENTOO-DIST/X86_64/36DA660B8B>) |
| c0a9:5421 | c0a9:5021 | Micron/Crucia... | P3 Plus NVMe PCIe SSD (DRAM-less)    | 4     | nvme       | [891E87B485](<Server/ASRockRack/B650/B650D4U/004D224B2B56/UBUNTU-22.04/5.15.0-125-GENERIC/X86_64/891E87B485>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 103c:3239 | 103c:21c0 | Hewlett-Packard  | Smart Array Gen9 Controllers         | 77    | hpsa       | [0B10A476DB](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/334260409128/DEBIAN/6.1.0-17-AMD64/X86_64/0B10A476DB>) |
| 103c:323b | 103c:3354 | Hewlett-Packard  | Smart Array Gen8 Controllers         | 73    | hpsa       | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |
| 103c:323a | 103c:3245 | Hewlett-Packard  | Smart Array G6 controllers           | 72    | hpsa       | [B076CBF109](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/416C8912B3CC/DEBIAN/6.11.10-AMD64/X86_64/B076CBF109>) |
| 1000:0079 | 1028:1f17 | LSI Logic / S... | MegaRAID SAS 2108 [Liberator]        | 57    | megarai... | [A2B12B6DA3](<Server/Dell/PowerEdge/PowerEdge R610/14D2A48FEC25/CENTOS-7/3.10.0-1160.11.1.EL7.X86_64/X86_64/A2B12B6DA3>) |
| 8086:201d | 8086:0000 | Intel            | Volume Management Device NVMe RAI... | 47    | vmd        | [AC6F8597CB](<Server/Lenovo/7X57S02N00/7X57S02N00 HR650X/44ADAB3CC0D8/CENTOS-8/4.18.0-348.7.1.EL8_5.X86_64/X86_64/AC6F8597CB>) |
| 1000:0060 | 1028:1f0c | LSI Logic / S... | MegaRAID SAS 1078                    | 41    | megarai... | [66405A9436](<Server/Dell/PowerEdge/PowerEdge R610/52C6387726CD/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/66405A9436>) |
| 1000:005d | 1028:1f47 | LSI Logic / S... | MegaRAID SAS-3 3108 [Invader]        | 36    | megarai... | [44126F8D86](<Server/Dell/PowerEdge/PowerEdge R630/23D674735CB9/GENTOO-2.15/6.6.38-GENTOO-MANS/X86_64/44126F8D86>) |
| 1000:005b | 1028:1f38 | LSI Logic / S... | MegaRAID SAS 2208 [Thunderbolt]      | 34    | megarai... | [D63ADBC5DD](<Server/Dell/PowerEdge/PowerEdge R720/13A7060552FC/NIXOS-25.05/6.6.63/X86_64/D63ADBC5DD>) |
| 8086:2826 | 8086:7270 | Intel            | SATA Controller [RAID Mode]          | 32    | ahci       | [3491BAD189](<Server/Supermicro/SBI-6119/SBI-6119P-T3N/0BAF8B926179/CYBER-INFRASTRUCTURE-6.0.2/3.10.0-1160.105.1.AIP7.214.3/X86_64/3491BAD189>) |
| 1000:005f | 1028:1f44 | LSI Logic / S... | MegaRAID SAS-3 3008 [Fury]           | 31    | megarai... | [E80578896E](<Server/Dell/PowerEdge/PowerEdge R240/83EA7CA85F81/RED-OS-8.0/6.6.26-1.RED80.X86_64/X86_64/E80578896E>) |
| 1000:005d | 1028:1f49 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 29    | megarai... | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 1000:005d | 1000:9361 | LSI Logic / S... | MegaRAID SAS-3 3108 [Invader]        | 26    | megarai... | [481D7F644B](<Server/Graviton/Server/Server/42D49089972B/ROSA-12.6/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/481D7F644B>) |
| 1000:005d | 1000:9363 | LSI Logic / S... | MegaRAID SAS-3 3108 [Invader]        | 23    | megarai... | [98EF58F80D](<Server/Supermicro/SYS-6018/SYS-6018R-WTR/4A5A129EA8CA/CENTOS-7/3.10.0-1160.83.1.EL7.X86_64/X86_64/98EF58F80D>) |
| 8086:2826 | 1028:073a | Intel            | SATA Controller [RAID Mode]          | 21    | ahci       | [B75294443B](<Server/Dell/Precision/Precision 7920 Tower/5E36FA18A2AE/KUBUNTU-20.04/5.15.0-84-GENERIC/X86_64/B75294443B>) |
| 1000:005b | 1028:1f34 | LSI Logic / S... | MegaRAID SAS 2208 [Thunderbolt]      | 19    | megarai... | [33A45E355F](<Server/Dell/PowerEdge/PowerEdge R620/C7F9C68EF445/CENTOS-6/2.6.32-754.33.1.EL6.X86_64/X86_64/33A45E355F>) |
| 1000:005d | 1028:1f42 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 19    | megarai... | [50DAB2C292](<Server/Dell/PowerEdge/PowerEdge R740/C7C19D76CEBF/UBUNTU-22.04/5.15.0-122-GENERIC/X86_64/50DAB2C292>) |
| 1000:005d | 15d9:0809 | LSI Logic / S... | MegaRAID SAS-3 3108 [Invader]        | 19    | megarai... | [1D6655D78B](<Server/transtec/CALLEO/CALLEO/204D0A7F12E7/DEBIAN-12/6.8.8-2-PVE/X86_64/1D6655D78B>) |
| 1000:005f | 1028:1f4b | LSI Logic / S... | MegaRAID SAS-3 3008 [Fury]           | 19    | megarai... | [CE34F45F28](<Server/AWS Elemental/Appliance/Appliance/78AD1C73F775/UBUNTU-22.04/6.5.0-27-GENERIC/X86_64/CE34F45F28>) |
| 1000:0079 | 1000:9260 | LSI Logic / S... | MegaRAID SAS 2108 [Liberator]        | 19    | megarai... | [6BB4760E91](<Server/Supermicro/X9/X9DRW/399D455C2665/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/6BB4760E91>) |
| 1000:005b | 1028:1f35 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 16    | megarai... | [B416E87C4A](<Server/Dell/PowerEdge/PowerEdge T320/7C98CB79C6C7/OPENMANDRIVA-24.09/6.11.0-DESKTOP-2OMV2490/X86_64/B416E87C4A>) |
| 103c:323b | 103c:3351 | Hewlett-Packard  | Smart Array Gen8 Controllers         | 16    | hpsa       | [5F9BC5DADC](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/F90BC48C287B/OPENSUSE-LEAP-15.6/6.4.0-150600.23.22-DEFAULT/X86_64/5F9BC5DADC>) |
| 1000:0073 | 1028:1f51 | LSI Logic / S... | MegaRAID SAS 2008 [Falcon]           | 11    | megarai... | [05BA811091](<Server/Dell/PowerEdge/PowerEdge R320/A501893D5B0E/DEBIAN-12/6.8.12-4-PVE/X86_64/05BA811091>) |
| 1000:0079 | 1000:9263 | LSI Logic / S... | MegaRAID SAS 2108 [Liberator]        | 11    | megarai... | [E673BAB21F](<Server/Supermicro/H8/H8QG6/539918058863/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/E673BAB21F>) |
| 1028:0015 | 1028:1f03 | Dell             | PowerEdge Expandable RAID control... | 11    | megarai... | [5DE4C4A538](<Server/Dell/PowerEdge/PowerEdge 2950/A7ED8CBDCF7D/LMDE-6/6.1.0-28-AMD64/X86_64/5DE4C4A538>) |
| 1000:0072 | 1000:0072 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 9     | mpt3sas    | [7D6B6074CA](<Server/DEPO Computers/X8/X8DT6/51562B8D18BD/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/7D6B6074CA>) |
| 103c:3230 | 103c:3234 | Hewlett-Packard  | Smart Array Controller               | 9     | hpsa       | [55414DE640](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G5/97BE895CF6E6/MX-23/6.6.0-CUSTOM/X86_64/55414DE640>) |
| 8086:2826 | 1028:0739 | Intel            | SATA Controller [RAID Mode]          | 9     | ahci       | [BA0626CE0A](<Server/Dell/Precision/Precision 7820 Tower/3792A2743A38/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/BA0626CE0A>) |
| 1000:0016 | 1028:1fcb | LSI Logic / S... | MegaRAID Tri-Mode SAS3508            | 8     | megarai... | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 1000:0017 | 1d49:0500 | Broadcom / LSI   | MegaRAID Tri-Mode SAS3408            | 8     | megarai... | [424E70419E](<Server/Lenovo/ThinkSystem/ThinkSystem SR570 -[7Y03CTO1WW]-/D3469A41F07A/XUBUNTU-18.04/4.15.0-213-GENERIC/X86_64/424E70419E>) |
| 1000:005b | 1014:040b | LSI Logic / S... | MegaRAID SAS 2208 [Thunderbolt]      | 8     | megarai... | [2112C605E2](<Server/Supermicro/X8/X8DAH/A2C78BCBF3F4/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/2112C605E2>) |
| 1000:005b | 1028:1f31 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 8     | megarai... | [C6FE3BE3CD](<Server/Dell/PowerEdge/PowerEdge T420/84B5AE1C1912/UBUNTU-22.04/6.5.0-28-GENERIC/X86_64/C6FE3BE3CD>) |
| 1000:0060 | 1028:1f0b | LSI Logic / S... | MegaRAID SAS 1078                    | 8     | megarai... | [A6838F51AF](<Server/Dell/PowerEdge/PowerEdge R410/8F2BA8E7E914/UBUNTU-22.04/5.15.0-107-GENERIC/X86_64/A6838F51AF>) |
| 1000:0079 | 1028:1f16 | Broadcom / LSI   | MegaRAID SAS 2108 [Liberator]        | 8     | megarai... | [3E627DE1A2](<Server/Dell/PowerEdge/PowerEdge R310/4E5975FDE146/DEBIAN-12/6.2.16-4-PVE/X86_64/3E627DE1A2>) |
| 103c:3230 | 103c:3235 | Hewlett-Packard  | Smart Array Controller               | 8     | hpsa       | [225FB05B12](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/38FD2BD94129/LINUXMINT-21.1/5.15.0-100-GENERIC/X86_64/225FB05B12>) |
| 8086:2827 | 8086:7270 | Intel            | sSATA Controller [RAID Mode]         | 8     | ahci       | [E37AC0AC00](<Server/Supermicro/X10/X10DRH/B93634E098F2/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/E37AC0AC00>) |
| 1000:0014 | 1d49:0602 | Broadcom / LSI   | MegaRAID Tri-Mode SAS3516            | 7     | megarai... | [C97EB83B9C](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 -[7X06CTO1WW]-/7AFAAAD68C64/CENTOS-7/3.10.0-1160.36.2.EL7.X86_64/X86_64/C97EB83B9C>) |
| 1000:0073 | 1028:1f4e | Broadcom / LSI   | MegaRAID SAS 2008 [Falcon]           | 7     | megarai... | [BF4CAFD003](<Server/HUAWEI/RH1288/RH1288 V3/D491636E1A1B/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/BF4CAFD003>) |
| 1000:0079 | 1014:03b2 | LSI Logic / S... | MegaRAID SAS 2108 [Liberator]        | 7     | megarai... | [3286B36B51](<Server/IBM/System/System x3650 M3 -[7945YBU]-/64198599779C/DEBIAN-12/6.8.12-1-PVE/X86_64/3286B36B51>) |
| 1000:0079 | 1734:1176 | Broadcom / LSI   | MegaRAID SAS 2108 [Liberator]        | 7     | megarai... | [F7382028BB](<Server/Fujitsu/PRIMERGY/PRIMERGY TX300 S6/F3E69C4EE4BB/OPENMANDRIVA-23.08/6.4.11-DESKTOP-1OMV2390/X86_64/F7382028BB>) |
| 1000:10e2 | 1028:1ae1 | Broadcom / LSI   | MegaRAID 12GSAS/PCIe Secure SAS39xx  | 7     | megarai... | [96EF3C9FDD](<Server/Dell/PowerEdge/PowerEdge R750/2DFFE1B75A53/CYBER-INFRASTRUCTURE-5.0.1/3.10.0-1160.41.1.VZ7.183.5/X86_64/96EF3C9FDD>) |
| 103c:323a | 103c:3243 | Hewlett-Packard  | Smart Array G6 controllers           | 7     | hpsa       | [EB01B42E57](<Server/Supermicro/X8/X8DTL/F728885E2B38/UBUNTU-22.04/5.15.0-107-GENERIC/X86_64/EB01B42E57>) |
| 17d3:1880 | 17d3:1883 | Areca Technology | ARC-188x series PCIe 2.0/3.0 to S... | 7     | arcmsr     | [3E6B182473](<Server/Gigabyte Technology/R182/R182-Z91-00/C0D8E0800C76/UBUNTU-22.04/5.15.0-70-GENERIC/X86_64/3E6B182473>) |
| 8086:2827 | 103c:81c6 | Intel            | sSATA Controller [RAID Mode]         | 7     | ahci       | [21781753FB](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/4E03B443521E/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/21781753FB>) |
| 9005:0285 | 9005:02d1 | Adaptec          | AAC-RAID                             | 7     | aacraid    | [B7F70CDB24](<Server/Supermicro/X8/X8DTU/5B1BC8DFEEB2/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/B7F70CDB24>) |
| 9005:028c | 9005:0501 | Adaptec          | Series 7 6G SAS/PCIe 3               | 7     | aacraid    | [943C34D6FE](<Server/Insyde/Purley/Purley/31EA1140F134/DEBIAN-11/5.15.158-2-PVE/X86_64/943C34D6FE>) |
| 1000:0014 | 1028:1f3b | Broadcom / LSI   | MegaRAID Tri-Mode SAS3516            | 6     | megarai... | [228949EF5A](<Server/Dell/PowerEdge/PowerEdge R450/3684EA8CEBA1/DEBIAN-11/5.10.0-23-AMD64/X86_64/228949EF5A>) |
| 1000:0016 | 1028:1fcd | LSI Logic / S... | MegaRAID Tri-Mode SAS3508            | 6     | megarai... | [D56CA4A374](<Server/Dell/PowerEdge/PowerEdge R6515/C4B03BD3B174/UBUNTU-22.04/5.15.0-41-GENERIC/X86_64/D56CA4A374>) |
| 1000:005d | 19e5:d207 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 6     | megarai... | [EA4033794A](<Server/HUAWEI/RH2288H/RH2288H V3/9A84058B41F9/ELEMENTARY-8/6.8.0-49-GENERIC/X86_64/EA4033794A>) |
| 1000:0073 | 1014:03b1 | LSI Logic / S... | MegaRAID SAS 2008 [Falcon]           | 6     | megarai... | [E9F6BF0852](<Server/IBM/System/System x3550 M3 -[2145CG8]-/F1DD25180469/DEBIAN-11/5.13.19-2-PVE/X86_64/E9F6BF0852>) |
| 1000:0079 | 15d9:0700 | Broadcom / LSI   | MegaRAID SAS 2108 [Liberator]        | 6     | megarai... | [05F8EBDF95](<Server/Supermicro/X8/X8DTT-H/319D85D1D7C9/LUBUNTU-22.04/5.15.0-125-GENERIC/X86_64/05F8EBDF95>) |

### Storage/sas (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1000:0072 | 1028:1f1c | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 28    | mpt3sas    | [22CE816D89](<Server/Dell/PowerEdge/PowerEdge R630/D53C4C379040/ALMA-9.4/5.14.0-427.31.1.EL9_4.X86_64/X86_64/22CE816D89>) |
| 8086:1d6b | 15d9:0636 | Intel            | C602 chipset 4-Port SATA Storage ... | 26    | isci       | [86B4E152AD](<Server/Supermicro/X9/X9DRW/D2C6B0237967/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/86B4E152AD>) |
| 1000:0097 | 15d9:0808 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 24    | mpt3sas    | [3B1B28CFC7](<Server/Supermicro/Super/Super Server/CD7B912FA9C9/ROSA-12.5.1/6.6.27-GENERIC-3ROSA2021.1-X86_64/X86_64/3B1B28CFC7>) |
| 8086:1d6b | 152d:899b | Intel            | C602 chipset 4-Port SATA Storage ... | 24    | isci       | [7E09CCDA22](<Server/ETegro Technologies/Hyperion/Hyperion RS125 G4/5259A72AB62F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/7E09CCDA22>) |
| 1000:0070 | 1000:3010 | LSI Logic / S... | SAS2004 PCI-Express Fusion-MPT SA... | 23    | mpt3sas    | [B66E4C113A](<Server/DEPO Computers/X8/X8DTU/732C5C269461/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/B66E4C113A>) |
| 8086:1d6b | 1043:84ef | Intel            | C602 chipset 4-Port SATA Storage ... | 17    | isci       | [F922090BB9](<Server/ASUSTek Computer/RS700/RS700-X7-PS4/FFF77E8C316C/DEBIAN-12/6.8.4-2-PVE/X86_64/F922090BB9>) |
| 1000:0072 | 1000:3020 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 16    | mpt3sas    | [CA71A1B4D6](<Server/Supermicro/X9/X9DRH-7TF-7F-iTF-iF/EC8C275F9BA3/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/CA71A1B4D6>) |
| 1000:0072 | 1028:1f1d | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 14    | mpt3sas    | [1E51138D9B](<Server/Dell/PowerEdge/PowerEdge T110 II/A23024949A59/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/1E51138D9B>) |
| 9005:028f | 103c:0602 | Adaptec          | Smart Storage PQI SAS                | 13    | smartpqi   | [D9F97B2071](<Server/HPE/ProLiant/ProLiant DL380 Gen10/6D60567E7E8D/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/D9F97B2071>) |
| 1000:0072 | 15d9:0400 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 12    | mpt3sas    | [D341C929E0](<Server/Supermicro/H8/H8QG6/8BCA4F0C7663/CLEAR-LINUX-OS-36250/5.16.13-1132.NATIVE/X86_64/D341C929E0>) |
| 1000:0086 | 15d9:0691 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 12    | mpt3sas    | [18E84EAC28](<Server/Supermicro/X9/X9DRD-7LN4F-X9DRD-EF/B9F8C820757C/SLACKWARE-15.0/6.1.106-UNRAID/X86_64/18E84EAC28>) |
| 8086:1d6b | 15d9:0626 | Intel            | C602 chipset 4-Port SATA Storage ... | 12    | isci       | [39232DFDE3](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/B0C1ED30C610/DEBIAN-12/6.1.0-25-AMD64/X86_64/39232DFDE3>) |
| 1000:0072 | 1028:1f1e | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 11    | mpt3sas    | [ECB7C501FD](<Server/Dell/PowerEdge/PowerEdge R815/E4A2FB4AF96A/OPENSUSE-LEAP-15.5/5.14.21-150500.55.52-DEFAULT/X86_64/ECB7C501FD>) |
| 1000:0097 | 1000:30e0 | LSI Logic / S... | SAS3008 PCI-Express Fusion-MPT SAS-3 | 11    | mpt3sas    | [1128E2A9FA](<Server/Supermicro/X8/X8DTU/D85AACC2195B/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/1128E2A9FA>) |
| 1000:0097 | 1028:1f53 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 10    | mpt3sas    | [152599CE84](<Server/Dell/PowerEdge/PowerEdge R730xd/6779A47FD98B/DEBIAN-10/4.19.147-RIVOREO-AMD64/X86_64/152599CE84>) |
| 1000:0064 | 1000:30d0 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 5     | mpt3sas    | [358C84CEAE](<Server/Dell/PowerEdge/PowerEdge R810/376A04F0DBD5/DEBIAN-12/6.5.3-1-PVE/X86_64/358C84CEAE>) |
| 1000:0072 | 1000:3040 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 5     | mpt3sas    | [6BE191DAD3](<Server/Supermicro/X9/X9DRi-LN4+-X9DR3-LN4+/213E402D3EC3/ZORIN-17/6.8.0-48-GENERIC/X86_64/6BE191DAD3>) |
| 1000:0087 | 1000:3020 | LSI Logic / S... | SAS2308 PCI-Express Fusion-MPT SAS-2 | 5     | mpt3sas    | [BE50A442AB](<Server/Dell/PowerEdge/PowerEdge R720xd/7383C7FB42D0/DEBIAN-12/6.1.74-PRODUCTION+TRUENAS/X86_64/BE50A442AB>) |
| 1000:0087 | 1000:3040 | LSI Logic / S... | SAS2308 PCI-Express Fusion-MPT SAS-2 | 5     | mpt3sas    | [7B51710FD1](<Server/Supermicro/Super/Super Server/717CACBD4C9C/UBUNTU-22.04/5.15.0-84-GENERIC/X86_64/7B51710FD1>) |
| 1000:0087 | 1028:1f34 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 5     | mpt3sas    | [B138AD81E5](<Server/Dell/PowerEdge/PowerEdge R720/BFA5B67AB0B1/DEBIAN-12/6.8.12-2-PVE/X86_64/B138AD81E5>) |
| 1000:0097 | 1000:3090 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 5     | mpt3sas    | [122B21A8E4](<Server/Others/Others/Others/DB0155950DC6/DEBIAN-12/6.8.12-5-PVE/X86_64/122B21A8E4>) |
| 103c:3239 | 103c:21bf | Hewlett-Packard  | Smart Array Gen9 Controllers         | 5     | hpsa       | [6E4FB0D4B2](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/3DAA87FAC48E/DEBIAN-12/6.1.0-26-AMD64/X86_64/6E4FB0D4B2>) |
| 19e5:a230 |           | Huawei Techno... | HiSilicon SAS 3.0 HBA                | 5     | hisi_sa... | [29BDE967FC](<Server/HUAWEI/TaiShan/TaiShan 2280 V2/2603C7B2E57E/UBUNTU-22.04/5.15.0-88-GENERIC/AARCH64/29BDE967FC>) |
| 8086:1d6b | 15d9:062a | Intel            | C602 chipset 4-Port SATA Storage ... | 5     | isci       | [3B5585BEC8](<Server/Supermicro/X9/X9SRA-X9SRA-3/E73ED86A7227/DEBIAN-11/5.10.0-33-AMD64/X86_64/3B5585BEC8>) |
| 8086:1d6b | 15d9:062b | Intel            | C602 chipset 4-Port SATA Storage ... | 5     | isci       | [F3D2F362E8](<Server/Supermicro/X9/X9SRE-X9SRE-3F-X9SRi-X9SRi-3F/55A635F4E92C/DEBIAN-12/6.8.8-2-PVE/X86_64/F3D2F362E8>) |
| 8086:1d6b | 1734:11b6 | Intel            | C602 chipset 4-Port SATA Storage ... | 5     | isci       | [ED6A47B6F9](<Server/Fujitsu/PRIMERGY/PRIMERGY TX2540 M1/6D63F93EE5A2/DEBIAN-12/6.11.10+BPO-AMD64/X86_64/ED6A47B6F9>) |
| 8086:1d6b | 8086:35a1 | Intel            | C602 chipset 4-Port SATA Storage ... | 5     | isci       | [5FBA63C085](<Server/Intel/S4600/S4600LH/902A1E31749C/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/5FBA63C085>) |
| 1000:0072 | 1014:03ca | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 4     | mpt3sas    | [BABEC64E24](<Server/IBM/System/System x3650 M4: -[7915G3G]/7F8745C284B0/UBUNTU-22.04/6.2.0-26-GENERIC/X86_64/BABEC64E24>) |
| 1000:0072 | 1014:03cb | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 4     | mpt3sas    | [E4686E182A](<Server/ASUSTek Computer/Z9PA-D8/Z9PA-D8 Series/0A5900AC477F/DEBIAN-12/6.5.3-ZABBLY+/X86_64/E4686E182A>) |
| 1000:0087 | 1028:1f38 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 4     | mpt3sas    | [4FCFB3FB2A](<Server/Dell/PowerEdge/PowerEdge R520/4F1CD316F76B/DEBIAN-11/5.15.85-1-PVE/X86_64/4FCFB3FB2A>) |
| 1000:00c4 | 1000:3190 | Broadcom / LSI   | SAS3224 PCI-Express Fusion-MPT SAS-3 | 4     | mpt3sas    | [BE6BB6833C](<Server/Supermicro/X11/X11DPi-N/FC0F4F308AC0/DEBIAN-11/5.15.60-1-PVE/X86_64/BE6BB6833C>) |
| 8086:1d6b | 15d9:0660 | Intel            | C602 chipset 4-Port SATA Storage ... | 4     | isci       | [F608C52359](<Server/SYNNEX/HYVE-ZEUS/HYVE-ZEUS/3156A60398CA/UBUNTU-23.10/6.5.0-9-GENERIC/X86_64/F608C52359>) |
| 8086:1d6b | 8086:357f | Intel            | C602 chipset 4-Port SATA Storage ... | 4     | isci       | [48F56B1871](<Server/Intel/S2600/S2600CP/931EED482113/UBUNTU-22.04/6.2.0-39-GENERIC/X86_64/48F56B1871>) |
| 1000:0072 | 1000:3050 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 3     | mpt3sas    | [CA71A1B4D6](<Server/Supermicro/X9/X9DRH-7TF-7F-iTF-iF/EC8C275F9BA3/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/CA71A1B4D6>) |
| 1000:0087 | 1590:0042 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 3     | mpt3sas    | [9E2F7A350A](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/845FF9826FEF/DEBIAN-11/5.15.126-1-PVE/X86_64/9E2F7A350A>) |
| 1000:0087 | 1590:0044 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 3     | mpt3sas    | [221DCDA3AE](<Server/Hewlett-Packard/ProLiant/ProLiant DL380e Gen8/D16FDAE3C88D/GENTOO-2.14/6.1.41-GENTOO-DIST/X86_64/221DCDA3AE>) |
| 103c:3239 | 103c:21c1 | Hewlett-Packard  | Smart Array Gen9 Controllers         | 3     | hpsa       | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:1d6a | 8086:3583 | Intel            | C600/X79 series chipset Dual 4-Po... | 3     | isci       | [ED7ACE37FB](<Server/Intel/S2600/S2600GZ/4B0292812B94/DEBIAN-12/6.8.12-2-PVE/X86_64/ED7ACE37FB>) |
| 9005:028f | 103c:0654 | Adaptec          | Smart Storage PQI SAS                | 3     | smartpqi   | [B6AF75AFF4](<Server/HPE/ProLiant/ProLiant DL380 Gen10/0895878555EA/ALPINE-3.21.0_ALPHA20240923/6.11.9-0-EDGE/X86_64/B6AF75AFF4>) |
| 1000:005d | 1000:9a61 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 2     | megarai... | [65D9CE4263](<Server/Supermicro/Super/Super Server/1BBC024DD007/DEBIAN-12/6.8.12-4-PVE/X86_64/65D9CE4263>) |
| 1000:005d | 8086:3a1e | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 2     | megarai... | [9D35C63CB8](<Server/Intel/S2600/S2600WTTR/590D589C3D64/DEBIAN-12/6.8.12-1-PVE/X86_64/9D35C63CB8>) |
| 1000:0064 | 1000:30c0 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 2     | mpt3sas    | [633B5B7A5F](<Server/Supermicro/X8/X8DTU/ECD77E6F1C15/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/633B5B7A5F>) |
| 1000:0072 | 1000:3080 | LSI Logic / S... | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mpt3sas    | [2D71FECB6D](<Server/Sun Microsystems/Sun/Sun Fire X2200 M2 with Quad Core Processor/D0B8300B5254/DEBIAN-12/6.1.0-18-AMD64/X86_64/2D71FECB6D>) |
| 1000:0072 | 103c:3371 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mpt3sas    | [7CC6270F3F](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G7/92B0219DC6F1/OL-9.4/5.15.0-206.153.7.EL9UEK.X86_64/X86_64/7CC6270F3F>) |
| 1000:0072 | 1170:6019 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mpt3sas    | [D1A141052C](<Server/Dell/PowerEdge/PowerEdge C6220 II/F5E056823CF5/DEBIAN-11/5.15.85-1-PVE/X86_64/D1A141052C>) |
| 1000:0087 | 1028:1f31 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 2     | mpt3sas    | [3796C964B5](<Server/Dell/PowerEdge/PowerEdge T420/2DEFEF8AD2D6/DEBIAN-12/6.5.13-5-PVE/X86_64/3796C964B5>) |
| 1000:0087 | 1590:0041 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 2     | mpt3sas    | [CA329A6038](<Server/Supermicro/Super/Super Server/1F76DDE31F47/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/CA329A6038>) |
| 1000:0097 | 1000:0090 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 2     | mpt3sas    | [2903921AEB](<Server/AIC/SB302/SB302-LB/98EDCF68ED2D/CENTOS-8/4.18.0-80.EL8.X86_64/X86_64/2903921AEB>) |
| 1000:0097 | 1000:30a0 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 2     | mpt3sas    | [FD86EE3128](<Server/Dell/PowerEdge/PowerEdge R740/437663FE9CF6/UBUNTU-24.04/6.8.0-47-GENERIC/X86_64/FD86EE3128>) |
| 1000:0097 | 1028:1f46 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 2     | mpt3sas    | [1DD21B89E9](<Server/Dell/PowerEdge/PowerEdge R640/34DAF9822B89/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/1DD21B89E9>) |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1000:0056 | 1000:3090 | LSI Logic / S... | SAS1064ET PCI-Express Fusion-MPT SAS | 21    | mptsas     | [B79574C0C8](<Server/DEPO Computers/X8/X8DTU/3FF996EC5B0F/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/B79574C0C8>) |
| 1000:0058 | 1028:1f0f | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 12    | mptsas     | [B6E4EA8841](<Server/Dell/PowerEdge/PowerEdge R410/904CC8DF7D0A/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/B6E4EA8841>) |
| 1000:0058 | 1028:1f0e | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 11    | mptsas     | [5E68E8F07F](<Server/Dell/PowerEdge/PowerEdge T410/2DA5F1F42ADD/UBUNTU-23.10/6.5.0-25-LOWLATENCY/X86_64/5E68E8F07F>) |
| 1000:0058 | 1028:1f10 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 9     | mptsas     | [BAC383D8EC](<Server/Dell/PowerEdge/PowerEdge R710/9120169A2D61/UBUNTU-22.04/5.15.0-88-GENERIC/X86_64/BAC383D8EC>) |
| 1000:0056 | 1014:03bb | LSI Logic / S... | SAS1064ET PCI-Express Fusion-MPT SAS | 7     | mptsas     | [133F7BC9A5](<Server/IBM/System/System x3250 M3 -[4252K4G]-/76E08604766E/DEBIAN-11/6.2.16-20-BPO11-PVE/X86_64/133F7BC9A5>) |
| 1000:0056 | 8086:3486 | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 3     | mptsas     | [EC199DC348](<Server/Intel/S5000/S5000VSA/20C09D0041D0/DEBIAN-11/5.15.158-2-PVE/X86_64/EC199DC348>) |
| 1000:0058 | 1000:3150 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 3     | mptsas     | [EA845EC5EA](<Server/Sun Microsystems/Sun/Sun Fire X4170 M2 SERVER/DD45CBFD7301/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/EA845EC5EA>) |
| 1000:0058 | 1014:0394 | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 3     | mptsas     | [B85DBD88F5](<Server/IBM/System/System x3650 M2 -[7947AC1]-/B4AFB5C90D39/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/B85DBD88F5>) |
| 1000:0030 | 1000:50c0 | LSI Logic / S... | 53c1030 PCI-X Fusion-MPT Dual Ult... | 2     | mptspi     | [F59DFC5D01](<Server/Dell/PowerEdge/PowerEdge T300/B5E455AD0EE1/DEBIAN-12/6.1.0-13-AMD64/X86_64/F59DFC5D01>) |
| 1000:0054 | 1028:1f09 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 2     | mptsas     | [701B89AC2E](<Server/IBM/System/System x3650 -[7979B9U]-/BC2D6FA78D8E/OPENMANDRIVA-4.2/5.11.12-DESKTOP-1OMV4002/X86_64/701B89AC2E>) |
| 1000:0056 | 152d:896d | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 2     | mptsas     | [23E536F087](<Server/Quanta/QSSC-98/QSSC-98J_C2/03AF1302C679/CENTOS-6.9/2.6.32-754.6.3.EL6.X86_64/X86_64/23E536F087>) |
| 1000:0058 | 103c:3229 | LSI Logic / S... | SAS1068E PCI-Express Fusion-MPT SAS  | 2     | mptsas     | [7CC6270F3F](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G7/92B0219DC6F1/OL-9.4/5.15.0-206.153.7.EL9UEK.X86_64/X86_64/7CC6270F3F>) |
| 1000:0058 | 15d9:0001 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 2     | mptsas     | [F645C4227C](<Server/Supermicro/X8/X8DT3/095547D33119/LMDE-4/4.19.0-16-AMD64/X86_64/F645C4227C>) |
| 1000:0058 | 1734:1130 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 2     | mptsas     | [C4C0B53877](<Server/Fujitsu/PRIMERGY/PRIMERGY TX150 S7/4BE064DA92A3/OL-9.0/5.15.0-0.30.19.EL9UEK.X86_64/X86_64/C4C0B53877>) |
| 9005:8017 | 9005:0045 | Adaptec          | ASC-29320ALP U320                    | 2     | aic79xx    | [096D3E62FE](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/7FC37BA0963D/FEDORA-34/5.12.3-300.FC34.X86_64/X86_64/096D3E62FE>) |
| 1000:000f | 0e11:7004 | Broadcom / LSI   | 53c875                               | 1     | sym53c8xx  | [AFF808A68F](<Server/Supermicro/X8/X8DTL/2CC89667A3DA/UBUNTU-18.04/4.15.0-99-GENERIC/X86_64/AFF808A68F>) |
| 1000:0030 | 1000:1000 | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mptspi     | [18B25AC51A](<Server/TYAN Computer/S/S4882/84BBA0EA52AC/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/18B25AC51A>) |
| 1000:0030 | 1014:026c | LSI Logic / S... | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mptspi     | [46973B5B05](<Server/IBM/eserver/eserver xSeries 235 -[86712AX]-/93A8BF1AD0B5/ROSA-2014.1/3.14.44-NRJ-DESKTOP-2ROSA-I586/I686/46973B5B05>) |
| 1000:0030 | 1028:016c | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mptspi     | [9A384DEF54](<Server/Dell/PowerEdge/PowerEdge 1850/858D0EB6BB9A/LINUXMINT-20.3/5.4.0-117-GENERIC/X86_64/9A384DEF54>) |
| 1000:0030 | 1028:016e | LSI Logic / S... | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mptspi     | [76EF1C8CA9](<Server/Dell/PowerEdge/PowerEdge 2800/2245B0434B88/UBUNTU-18.04/4.15.0-47-GENERIC/X86_64/76EF1C8CA9>) |
| 1000:0030 | 1028:0183 | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mptspi     | [319647C509](<Server/Dell/PowerEdge/PowerEdge 1800/DEFCB85959FA/UBUNTU-23.10/6.5.0-25-LOWLATENCY/X86_64/319647C509>) |
| 1000:0054 | 1028:1f04 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 1     | mptsas     | [358C84CEAE](<Server/Dell/PowerEdge/PowerEdge R810/376A04F0DBD5/DEBIAN-12/6.5.3-1-PVE/X86_64/358C84CEAE>) |
| 1000:0054 | 1028:1f06 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 1     | mptsas     | [2FF8924B15](<Server/Dell/PowerEdge/PowerEdge 1950/12946989497B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2FF8924B15>) |
| 1000:0054 | 1734:1082 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 1     | mptsas     | [872AE76863](<Server/Fujitsu Siemens/PRIMERGY/PRIMERGY RX300 S3/2366E6CCAF09/OPENSUSE-LEAP-15.1/4.12.14-LP151.28.91-DEFAULT/X86_64/872AE76863>) |
| 1000:0054 | 1734:10b9 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 1     | mptsas     | [A0F9679F57](<Server/Fujitsu Siemens/PRIMERGY/PRIMERGY RX330 S1/BBBDB6433647/UBUNTU-18.04/4.15.0-112-GENERIC/X86_64/A0F9679F57>) |
| 1000:0054 | 8086:3504 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 1     | mptsas     | [A61FFACB08](<Server/Intel/S5000/S5000PAL/A2AA6EE937D8/UBUNTU-18.04/5.0.0-37-GENERIC/X86_64/A61FFACB08>) |
| 1000:0056 | 1734:1131 | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 1     | mptsas     | [28EB3733CA](<Server/Fujitsu/PRIMERGY/PRIMERGY RX200 S6/A598FCA268BC/UBUNTU-20.04/5.4.0-88-GENERIC/X86_64/28EB3733CA>) |
| 1000:0056 | 8086:346c | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 1     | mptsas     | [390F15B7F9](<Server/Intel/S5000/S5000PAL/74FE128B70DE/CENTOS-7/3.10.0-1062.1.1.EL7.X86_64/X86_64/390F15B7F9>) |
| 1000:0056 | 8086:3478 | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 1     | mptsas     | [4ABB5E39FC](<Server/Intel/S5000/S5000PSL/8E7B5827ED01/DEBIAN-12/6.5.11-7-PVE/X86_64/4ABB5E39FC>) |
| 1000:0058 | 1000:3080 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mptsas     | [8CF8F98A53](<Server/Fujitsu/PRIMERGY/PRIMERGY/41B1E7A57925/FEDORA-35/5.14.10-300.FC35.X86_64/X86_64/8CF8F98A53>) |
| 1000:0058 | 1000:30a0 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mptsas     | [E5AEAF13AE](<Server/Intel/S3210/S3210SH/9BAA0B7E268E/UBUNTU-18.04/4.15.0-64-GENERIC/X86_64/E5AEAF13AE>) |
| 1000:0058 | 1000:3140 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mptsas     | [09C71F9FAA](<Server/Supermicro/X8/X8DTU/1ABD2AAE69B0/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/09C71F9FAA>) |
| 1000:0058 | 1000:7016 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mptsas     | [FEC98B51DA](<Server/TYAN Computer/S/S7012/E4E1099CB0ED/SLACKWARE-15.0/5.15.21-HARDENED1/X86_64/FEC98B51DA>) |
| 1000:0058 | 103c:322d | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mptsas     | [AC48708BDD](<Server/Hewlett-Packard/ProLiant/ProLiant DL60 Gen9/A4D4D00D8A92/DEBIAN-11/5.15.107+TRUENAS/X86_64/AC48708BDD>) |
| 1000:0059 | 15d9:0001 | Broadcom / LSI   | MegaRAID SAS 8208ELP/8208ELP         | 1     | mptsas     | [93DE2051E2](<Server/Supermicro/X8/X8DT3/3D7941CC8117/GENTOO-2.13/5.19.3-GENTOO/X86_64/93DE2051E2>) |
| 1000:0059 | 15d9:0006 | Broadcom / LSI   | MegaRAID SAS 8208ELP/8208ELP         | 1     | mptsas     | [8F945E0A15](<Server/Supermicro/X8/X8DTL/7581500BE1DB/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/8F945E0A15>) |
| 1000:0062 | 1014:0366 | Broadcom / LSI   | SAS1078 PCI-Express Fusion-MPT SAS   | 1     | mptsas     | [1947C0F43A](<Server/IBM/3850/3850 M2-x3950 M2 -[7233AC2]/96C33EE0F405/UBUNTU-22.04/5.15.0-89-GENERIC/X86_64/1947C0F43A>) |
| 1000:0062 | 8086:3505 | Broadcom / LSI   | SAS1078 PCI-Express Fusion-MPT SAS   | 1     | mptsas     | [476430304C](<Server/Intel/S5520/S5520UR/ED7F5C075DAE/UBUNTU-20.04/5.4.0-104-GENERIC/X86_64/476430304C>) |
| 11ab:7042 | 11ab:11ab | Marvell Techn... | 88SX7042 PCIe 4-port SATA-II cont... | 1     | sata_mv    | [7A931B2F8D](<Server/Nvidia/MCP/MCP55/C2985C928080/UBUNTU-18.04/5.4.0-150-GENERIC/X86_64/7A931B2F8D>) |
| 1425:6507 | 1425:0000 | Chelsio Commu... | T62100-LP-CR Unified Wire Storage... | 1     |            | [1126AE11AE](<Server/ASUSTek Computer/Z11PG-D16/Z11PG-D16 Series/9878F56186D3/DEBIAN-9/4.9.35-DYVI/X86_64/1126AE11AE>) |
| 1b4b:1475 | 1baa:1852 | Marvell Techn... | Marvell SCSI storage controller      | 1     |            | [5FA39DA50A](<Server/Dell/PowerEdge/PowerEdge R350/95232CC6FD85/UBUNTU-22.04/5.15.0-97-GENERIC/X86_64/5FA39DA50A>) |
| 9004:5078 | 9004:7850 | Adaptec          | AIC-7850T/7856T [AVA-2902/4/6 / A... | 1     | aic7xxx    | [171EE8DB12](<Server/Supermicro/C7/C7Z87/4BD99E9BA2B9/XUBUNTU-19.10/5.3.0-18-LOWLATENCY/X86_64/171EE8DB12>) |
| 9005:00c0 | 9005:f620 | Adaptec          | AHA-3960D / AIC-7899A U160/m         | 1     | aic7xxx    | [CA96304CAC](<Server/Dell/PowerEdge/PowerEdge 1950/E6782D539697/POP!_OS-20.04/5.15.15-76051515-GENERIC/X86_64/CA96304CAC>) |
| 9005:801f | 8086:341a | Adaptec          | AIC-7902 U320                        | 1     | aic79xx    | [37AA8C0E8E](<Server/Intel/SE7501WV2S/SE7501WV2S A99386-110/784B87202334/UBUNTU-18.04/4.15.0-108-GENERIC/I686/37AA8C0E8E>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:204e | 8086:0000 | Intel            | Sky Lake-E M3KTI Registers           | 309   | skx_uncore | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2018 | 8086:0000 | Intel            | Sky Lake-E M2PCI Registers           | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2035 |           | Intel            | Sky Lake-E RAS Configuration Regi... | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2040 | 8086:0000 | Intel            | Sky Lake-E Integrated Memory Cont... | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2041 | 8086:0000 | Intel            | Sky Lake-E Integrated Memory Cont... | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2042 | 8086:0000 | Intel            | Sky Lake-E Integrated Memory Cont... | 299   | skx_uncore | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2043 | 8086:0000 | Intel            | Sky Lake-E Integrated Memory Cont... | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2044 | 8086:0000 | Intel            | Sky Lake-E Integrated Memory Cont... | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2045 | 8086:0000 | Intel            | Sky Lake-E LM Channel 1              | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2046 | 8086:0000 | Intel            | Sky Lake-E LMS Channel 1             | 299   | skx_uncore | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2047 | 8086:0000 | Intel            | Sky Lake-E LMDP Channel 1            | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2048 | 8086:0000 | Intel            | Sky Lake-E DECS Channel 2            | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2049 | 8086:0000 | Intel            | Sky Lake-E LM Channel 2              | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:204a | 8086:0000 | Intel            | Sky Lake-E LMS Channel 2             | 299   | skx_uncore | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:204b | 8086:0000 | Intel            | Sky Lake-E LMDP Channel 2            | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2054 | 8086:0000 | Intel            | Sky Lake-E CHA Registers             | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2055 | 8086:0000 | Intel            | Sky Lake-E CHA Registers             | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2056 | 8086:0000 | Intel            | Sky Lake-E CHA Registers             | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2057 | 8086:0000 | Intel            | Sky Lake-E CHA Registers             | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2066 | 8086:0000 | Intel            | Sky Lake-E Integrated Memory Cont... | 299   | skx_uncore | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2080 | 8086:0000 | Intel            | Sky Lake-E PCU Registers             | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2081 | 8086:0000 | Intel            | Sky Lake-E PCU Registers             | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2082 | 8086:0000 | Intel            | Sky Lake-E PCU Registers             | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2083 | 8086:0000 | Intel            | Sky Lake-E PCU Registers             | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2084 | 8086:0000 | Intel            | Sky Lake-E PCU Registers             | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2085 | 8086:0000 | Intel            | Sky Lake-E PCU Registers             | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2086 | 8086:0000 | Intel            | Sky Lake-E PCU Registers             | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:208d | 8086:0000 | Intel            | Sky Lake-E CHA Registers             | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:208e | 8086:0000 | Intel            | Sky Lake-E CHA Registers             | 299   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2016 | 8086:0000 | Intel            | Sky Lake-E Ubox Registers            | 298   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2025 |           | Intel            | Sky Lake-E RAS                       | 297   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2034 | 8086:0000 | Intel            | Sky Lake-E VT-d                      | 296   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2014 | 8086:0000 | Intel            | Sky Lake-E Ubox Registers            | 292   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2024 | 8086:0000 | Intel            | Sky Lake-E MM/Vt-d Configuration ... | 290   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:2059 | 8086:0000 | Intel            | Sky Lake-E UPI Registers             | 286   |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:6f76 |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 253   |            | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6f88 |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 252   |            | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6f8a |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 252   |            | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6fae |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 252   |            | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6faf |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 252   |            | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6fbc |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 252   |            | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6fbd |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 252   |            | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6fbe |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 252   |            | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6fbf |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 252   |            | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:2021 | 8086:0000 | Intel            | Sky Lake-E CBDMA Registers           | 244   | ioatdma    | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:6f6e |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 227   |            | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6f6f |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 227   |            | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6fb8 |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 227   |            | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6fb9 |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 227   |            | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |
| 8086:6fba |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 227   |            | [9484E3F188](<Server/Dell/PowerEdge/PowerEdge R530/92C4F89B0588/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/9484E3F188>) |

### Tv card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 109e:036e |           | Brooktree        | Bt878 Video Capture                  | 1     | bttv       | [B55D1DAEA5](<Server/Intel/S5500/S5500BC/EB1E1FCFB3A4/UBUNTU-MATE-19.10/5.3.0-51-GENERIC/X86_64/B55D1DAEA5>) |
| 109e:036e | 0070:ff04 | Brooktree        | Bt878 Video Capture                  | 1     | bttv       | [2C877CF870](<Server/Hewlett-Packard/ProLiant/ProLiant DL140 G2/7851FB932D49/ARCH/4.18.12-ARCH1-1-ARCH/X86_64/2C877CF870>) |
| 109e:036e | 800a:763d | Brooktree        | Bt878 Video Capture                  | 1     | bttv       | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 109e:036e | 800b:763d | Brooktree        | Bt878 Video Capture                  | 1     | bttv       | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 109e:036e | 800c:763d | Brooktree        | Bt878 Video Capture                  | 1     | bttv       | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 109e:036e | 800d:763d | Brooktree        | Bt878 Video Capture                  | 1     | bttv       | [7E72574FF4](<Server/Intel/S5000/S5000VSA/F1E60FC0C0E1/UBUNTU-20.04/5.4.0-72-GENERIC/X86_64/7E72574FF4>) |
| 14f1:5b7a | 0070:7446 | Conexant Systems | CX23418 Single-Chip MPEG-2 Encode... | 1     | cx18       | [D9A8E46B60](<Server/Intel/S5520/S5520HC/42DF18E9A677/KUBUNTU-23.10/6.5.0-10-GENERIC/X86_64/D9A8E46B60>) |
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
| 103c:3300 | 103c:3381 | Hewlett-Packard  | Integrated Lights-Out Standard Vi... | 214   | uhci_hcd   | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:1d26 | 103c:18a9 | Intel            | C600/X79 series chipset USB2 Enha... | 103   | ehci_pci   | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |
| 8086:1d2d | 103c:18a9 | Intel            | C600/X79 series chipset USB2 Enha... | 103   | ehci_pci   | [1F5E96532B](<Server/Hewlett-Packard/ProLiant/ProLiant DL380p Gen8/1DE2DBCF3FF6/UBUNTU-24.04/6.8.0-39-GENERIC/X86_64/1F5E96532B>) |
| 8086:8d31 | 103c:8030 | Intel            | C610/X99 series chipset USB xHCI ... | 103   | xhci_pci   | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:8d26 | 103c:8030 | Intel            | C610/X99 series chipset USB Enhan... | 102   | ehci_pci   | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:8d2d | 103c:8030 | Intel            | C610/X99 series chipset USB Enhan... | 102   | ehci_pci   | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:a1af | 8086:7270 | Intel            | C620 Series Chipset Family USB 3.... | 87    | xhci_hcd   | [122B21A8E4](<Server/Others/Others/Others/DB0155950DC6/DEBIAN-12/6.8.12-5-PVE/X86_64/122B21A8E4>) |
| 8086:3a34 | 103c:330d | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 71    | uhci_hcd   | [B076CBF109](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/416C8912B3CC/DEBIAN/6.11.10-AMD64/X86_64/B076CBF109>) |
| 8086:3a35 | 103c:330d | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 71    | uhci_hcd   | [B076CBF109](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/416C8912B3CC/DEBIAN/6.11.10-AMD64/X86_64/B076CBF109>) |
| 8086:3a36 | 103c:330d | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 71    | uhci_hcd   | [B076CBF109](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/416C8912B3CC/DEBIAN/6.11.10-AMD64/X86_64/B076CBF109>) |
| 8086:3a3a | 103c:330d | Intel            | 82801JI (ICH10 Family) USB2 EHCI ... | 71    | ehci_pci   | [B076CBF109](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/416C8912B3CC/DEBIAN/6.11.10-AMD64/X86_64/B076CBF109>) |
| 8086:3a39 | 103c:330d | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 70    | uhci_hcd   | [B076CBF109](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/416C8912B3CC/DEBIAN/6.11.10-AMD64/X86_64/B076CBF109>) |
| 103c:3300 | 103c:3309 | Hewlett-Packard  | Integrated Lights-Out Standard Vi... | 52    | uhci_hcd   | [B076CBF109](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/416C8912B3CC/DEBIAN/6.11.10-AMD64/X86_64/B076CBF109>) |
| 8086:3a34 | 15d9:0600 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 49    | uhci_hcd   | [6918605D42](<Server/Supermicro/X8/X8DTU/2EC017791B11/DEBIAN-12/6.8.12-5-PVE/X86_64/6918605D42>) |
| 8086:3a35 | 15d9:0600 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 49    | uhci_hcd   | [6918605D42](<Server/Supermicro/X8/X8DTU/2EC017791B11/DEBIAN-12/6.8.12-5-PVE/X86_64/6918605D42>) |
| 8086:3a36 | 15d9:0600 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 49    | uhci_hcd   | [6918605D42](<Server/Supermicro/X8/X8DTU/2EC017791B11/DEBIAN-12/6.8.12-5-PVE/X86_64/6918605D42>) |
| 8086:3a37 | 15d9:0600 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 49    | uhci_hcd   | [6918605D42](<Server/Supermicro/X8/X8DTU/2EC017791B11/DEBIAN-12/6.8.12-5-PVE/X86_64/6918605D42>) |
| 8086:3a38 | 15d9:0600 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 49    | uhci_hcd   | [6918605D42](<Server/Supermicro/X8/X8DTU/2EC017791B11/DEBIAN-12/6.8.12-5-PVE/X86_64/6918605D42>) |
| 8086:3a39 | 15d9:0600 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 49    | uhci_hcd   | [6918605D42](<Server/Supermicro/X8/X8DTU/2EC017791B11/DEBIAN-12/6.8.12-5-PVE/X86_64/6918605D42>) |
| 8086:3a3a | 15d9:0600 | Intel            | 82801JI (ICH10 Family) USB2 EHCI ... | 49    | ehci_pci   | [6918605D42](<Server/Supermicro/X8/X8DTU/2EC017791B11/DEBIAN-12/6.8.12-5-PVE/X86_64/6918605D42>) |
| 8086:3a3c | 15d9:0600 | Intel            | 82801JI (ICH10 Family) USB2 EHCI ... | 49    | ehci_pci   | [6918605D42](<Server/Supermicro/X8/X8DTU/2EC017791B11/DEBIAN-12/6.8.12-5-PVE/X86_64/6918605D42>) |
| 1022:148c | 15d9:145c | AMD              | Starship USB 3.0 Host Controller     | 47    | xhci_hcd   | [726B65D6E8](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.10/4.18.0-553.27.1.EL8_10.X86_64/X86_64/726B65D6E8>) |
| 1912:0014 | ffff:ffff | Renesas Techn... | uPD720201 USB 3.0 Host Controller    | 44    | xhci_pci   | [0D6D6A6743](<Server/Dell/PowerEdge/PowerEdge R510/7E56EFD8FB93/DEBIAN-12/6.8.8-2-PVE/X86_64/0D6D6A6743>) |
| 103c:3300 | 103c:3305 | Hewlett-Packard  | Integrated Lights-Out Standard Vi... | 43    | uhci_hcd   | [7EE3CAE73F](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/FB9F2505E84E/DEBIAN-12/6.1.0-22-AMD64/X86_64/7EE3CAE73F>) |
| 8086:8d26 | 8086:7270 | Intel            | C610/X99 series chipset USB Enhan... | 43    | ehci_pci   | [142EA5AAAB](<Server/Lenovo/70FRR156CN/70FRR156CN RD450X/8535AF5D51BA/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/142EA5AAAB>) |
| 8086:8d2d | 8086:7270 | Intel            | C610/X99 series chipset USB Enhan... | 43    | ehci_pci   | [142EA5AAAB](<Server/Lenovo/70FRR156CN/70FRR156CN RD450X/8535AF5D51BA/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/142EA5AAAB>) |
| 8086:8d31 | 8086:7270 | Intel            | C610/X99 series chipset USB xHCI ... | 43    | xhci_pci   | [142EA5AAAB](<Server/Lenovo/70FRR156CN/70FRR156CN RD450X/8535AF5D51BA/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/142EA5AAAB>) |
| 8086:1d26 | 15d9:0636 | Intel            | C600/X79 series chipset USB2 Enha... | 39    | ehci_pci   | [86B4E152AD](<Server/Supermicro/X9/X9DRW/D2C6B0237967/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/86B4E152AD>) |
| 8086:1d2d | 15d9:0636 | Intel            | C600/X79 series chipset USB2 Enha... | 39    | ehci_pci   | [86B4E152AD](<Server/Supermicro/X9/X9DRW/D2C6B0237967/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/86B4E152AD>) |
| 8086:1d26 | 1028:048c | Intel            | C600/X79 series chipset USB2 Enha... | 36    | ehci_pci   | [D63ADBC5DD](<Server/Dell/PowerEdge/PowerEdge R720/13A7060552FC/NIXOS-25.05/6.6.63/X86_64/D63ADBC5DD>) |
| 8086:1d2d | 1028:048c | Intel            | C600/X79 series chipset USB2 Enha... | 36    | ehci_pci   | [D63ADBC5DD](<Server/Dell/PowerEdge/PowerEdge R720/13A7060552FC/NIXOS-25.05/6.6.63/X86_64/D63ADBC5DD>) |
| 8086:2934 | 1028:0235 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 33    | uhci_hcd   | [E9F4F40104](<Server/Dell/PowerEdge/PowerEdge R710/4BAAF0C6A4BB/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/E9F4F40104>) |
| 8086:2935 | 1028:0235 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 33    | uhci_hcd   | [E9F4F40104](<Server/Dell/PowerEdge/PowerEdge R710/4BAAF0C6A4BB/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/E9F4F40104>) |
| 8086:2937 | 1028:0235 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 33    | uhci_hcd   | [E9F4F40104](<Server/Dell/PowerEdge/PowerEdge R710/4BAAF0C6A4BB/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/E9F4F40104>) |
| 8086:2938 | 1028:0235 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 33    | uhci_hcd   | [E9F4F40104](<Server/Dell/PowerEdge/PowerEdge R710/4BAAF0C6A4BB/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/E9F4F40104>) |
| 8086:293a | 1028:0235 | Intel            | 82801I (ICH9 Family) USB2 EHCI Co... | 33    | ehci_pci   | [E9F4F40104](<Server/Dell/PowerEdge/PowerEdge R710/4BAAF0C6A4BB/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/E9F4F40104>) |
| 8086:293c | 1028:0235 | Intel            | 82801I (ICH9 Family) USB2 EHCI Co... | 33    | ehci_pci   | [E9F4F40104](<Server/Dell/PowerEdge/PowerEdge R710/4BAAF0C6A4BB/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/E9F4F40104>) |
| 1106:3483 | 1106:3483 | VIA Technologies | VL805/806 xHCI USB 3.0 Controller    | 31    | xhci_pci   | [3B5585BEC8](<Server/Supermicro/X9/X9SRA-X9SRA-3/E73ED86A7227/DEBIAN-11/5.10.0-33-AMD64/X86_64/3B5585BEC8>) |
| 8086:a1af | 1028:073a | Intel            | C620 Series Chipset Family USB 3.... | 29    | xhci_pci   | [B75294443B](<Server/Dell/Precision/Precision 7920 Tower/5E36FA18A2AE/KUBUNTU-20.04/5.15.0-84-GENERIC/X86_64/B75294443B>) |
| 8086:1d26 | 1043:84ef | Intel            | C600/X79 series chipset USB2 Enha... | 28    | ehci_pci   | [E805BE0AAC](<Server/Kraftway/GEG/GEG/C4E325834440/DEBIAN-12/6.1.0-27-AMD64/X86_64/E805BE0AAC>) |
| 8086:1d2d | 1043:84ef | Intel            | C600/X79 series chipset USB2 Enha... | 28    | ehci_pci   | [E805BE0AAC](<Server/Kraftway/GEG/GEG/C4E325834440/DEBIAN-12/6.1.0-27-AMD64/X86_64/E805BE0AAC>) |
| 1b21:1142 | 1b21:1142 | ASMedia Techn... | ASM1042A USB 3.0 Host Controller     | 27    | xhci_hcd   | [726B65D6E8](<Server/Supermicro/motherboard-H12/motherboard-H12 Series/D02A5951EE17/ALMA-8.10/4.18.0-553.27.1.EL8_10.X86_64/X86_64/726B65D6E8>) |
| 8086:a1af | 15d9:0967 | Intel            | C620 Series Chipset Family USB 3.... | 27    | xhci_hcd   | [01602FD84E](<Server/Supermicro/SYS-6019/SYS-6019P-WTR/0C2A376E8BE8/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/01602FD84E>) |
| 103c:22f6 | 1590:00e4 | Hewlett-Packard  | iLO5 Virtual USB Controller          | 26    | ehci_pci   | [D9F97B2071](<Server/HPE/ProLiant/ProLiant DL380 Gen10/6D60567E7E8D/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/D9F97B2071>) |
| 8086:2934 | 1028:0236 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 26    | uhci_hcd   | [A2B12B6DA3](<Server/Dell/PowerEdge/PowerEdge R610/14D2A48FEC25/CENTOS-7/3.10.0-1160.11.1.EL7.X86_64/X86_64/A2B12B6DA3>) |
| 8086:2935 | 1028:0236 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 26    | uhci_hcd   | [A2B12B6DA3](<Server/Dell/PowerEdge/PowerEdge R610/14D2A48FEC25/CENTOS-7/3.10.0-1160.11.1.EL7.X86_64/X86_64/A2B12B6DA3>) |
| 8086:2937 | 1028:0236 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 26    | uhci_hcd   | [A2B12B6DA3](<Server/Dell/PowerEdge/PowerEdge R610/14D2A48FEC25/CENTOS-7/3.10.0-1160.11.1.EL7.X86_64/X86_64/A2B12B6DA3>) |
| 8086:2938 | 1028:0236 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 26    | uhci_hcd   | [A2B12B6DA3](<Server/Dell/PowerEdge/PowerEdge R610/14D2A48FEC25/CENTOS-7/3.10.0-1160.11.1.EL7.X86_64/X86_64/A2B12B6DA3>) |
| 8086:293a | 1028:0236 | Intel            | 82801I (ICH9 Family) USB2 EHCI Co... | 26    | ehci_pci   | [A2B12B6DA3](<Server/Dell/PowerEdge/PowerEdge R610/14D2A48FEC25/CENTOS-7/3.10.0-1160.11.1.EL7.X86_64/X86_64/A2B12B6DA3>) |
| 8086:293c | 1028:0236 | Intel            | 82801I (ICH9 Family) USB2 EHCI Co... | 26    | ehci_pci   | [A2B12B6DA3](<Server/Dell/PowerEdge/PowerEdge R610/14D2A48FEC25/CENTOS-7/3.10.0-1160.11.1.EL7.X86_64/X86_64/A2B12B6DA3>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:8d7c | 103c:8030 | Intel            | C610/X99 series chipset SPSR         | 103   |            | [7AFC8353D7](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/47B40C834EA5/DEBIAN-12/6.5.11-8-PVE/X86_64/7AFC8353D7>) |
| 8086:a1ec | 8086:7270 | Intel            | C620 Series Chipset Family MROM 0    | 86    |            | [122B21A8E4](<Server/Others/Others/Others/DB0155950DC6/DEBIAN-12/6.8.12-5-PVE/X86_64/122B21A8E4>) |
| 8086:a1ed | 8086:7270 | Intel            | C620 Series Chipset Family MROM 1    | 50    |            | [122B21A8E4](<Server/Others/Others/Others/DB0155950DC6/DEBIAN-12/6.8.12-5-PVE/X86_64/122B21A8E4>) |
| 8086:8d7c | 8086:7270 | Intel            | C610/X99 series chipset SPSR         | 41    |            | [142EA5AAAB](<Server/Lenovo/70FRR156CN/70FRR156CN RD450X/8535AF5D51BA/OPENMANDRIVA-23.08/6.4.8-DESKTOP-2OMV2390/X86_64/142EA5AAAB>) |
| 8086:8d7c | 8086:0000 | Intel            | C610/X99 series chipset SPSR         | 29    |            | [30659AA37A](<Server/HUAWEI/RH2288/RH2288 V3/C95D9CCBAF34/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/30659AA37A>) |
| 8086:a1ec | 1028:073a | Intel            | C620 Series Chipset Family MROM 0    | 29    |            | [B75294443B](<Server/Dell/Precision/Precision 7920 Tower/5E36FA18A2AE/KUBUNTU-20.04/5.15.0-84-GENERIC/X86_64/B75294443B>) |
| 8086:a1ec | 15d9:0967 | Intel            | C620 Series Chipset Family MROM 0    | 27    |            | [01602FD84E](<Server/Supermicro/SYS-6019/SYS-6019P-WTR/0C2A376E8BE8/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/01602FD84E>) |
| 8086:8d7c | 1028:0601 | Intel            | C610/X99 series chipset SPSR         | 24    |            | [44126F8D86](<Server/Dell/PowerEdge/PowerEdge R630/23D674735CB9/GENTOO-2.15/6.6.38-GENTOO-MANS/X86_64/44126F8D86>) |
| 8086:a1ec | 1590:00eb | Intel            | C620 Series Chipset Family MROM 0    | 22    |            | [D9F97B2071](<Server/HPE/ProLiant/ProLiant DL380 Gen10/6D60567E7E8D/UBUNTU-22.04/6.8.0-50-GENERIC/X86_64/D9F97B2071>) |
| 8086:8d7c | 1028:0627 | Intel            | C610/X99 series chipset SPSR         | 20    |            | [72A4F63713](<Server/Dell/PowerEdge/PowerEdge R730XD/1A3F6F422946/DEBIAN-12/6.8.12-4-PVE/X86_64/72A4F63713>) |
| 8086:8d7c | 15d9:0821 | Intel            | C610/X99 series chipset SPSR         | 20    |            | [98EF58F80D](<Server/Supermicro/SYS-6018/SYS-6018R-WTR/4A5A129EA8CA/CENTOS-7/3.10.0-1160.83.1.EL7.X86_64/X86_64/98EF58F80D>) |
| 8086:a1ec | 1028:0715 | Intel            | C620 Series Chipset Family MROM 0    | 19    |            | [2EA3B6BA11](<Server/Dell/PowerEdge/PowerEdge R740/102E11A0DB9A/DEBIAN-12/6.8.4-2-PVE/X86_64/2EA3B6BA11>) |
| 8086:a1ec | 1458:1000 | Intel            | C620 Series Chipset Family MROM 0    | 17    |            | [F76FC4031D](<Server/PSSC Labs/SS4000/SS4000HD/13084E646FAA/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/F76FC4031D>) |
| 8086:a1ec | 8086:35ce | Intel            | C620 Series Chipset Family MROM 0    | 17    |            | [97B57F8628](<Server/YADRO/VEGMAN/VEGMAN S220 Server/91703340854B/RED-OS-7.3.1/5.15.10-1.EL7.X86_64/X86_64/97B57F8628>) |
| 8086:a1ed | 1028:073a | Intel            | C620 Series Chipset Family MROM 1    | 17    |            | [45516ED3A7](<Server/Dell/Precision/Precision 7920 Tower/4910BAFAEC76/UBUNTU-22.04/5.15.0-106-GENERIC/X86_64/45516ED3A7>) |
| 8086:8d7c | 1028:0600 | Intel            | C610/X99 series chipset SPSR         | 16    |            | [888A235104](<Server/Dell/PowerEdge/PowerEdge R730/B44B0E51BDB3/DEBIAN-12/6.8.12-4-PVE/X86_64/888A235104>) |
| 8086:a1ec | 1028:0739 | Intel            | C620 Series Chipset Family MROM 0    | 16    |            | [BA0626CE0A](<Server/Dell/Precision/Precision 7820 Tower/3792A2743A38/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/BA0626CE0A>) |
| 8086:a1ec | 1043:871e | Intel            | C620 Series Chipset Family MROM 0    | 15    |            | [664827DD6C](<Server/ASUSTek Computer/Pro/Pro WS C621-64L SAGE-10G Series/A1C444FAB774/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/664827DD6C>) |
| 8086:8d7c | 15d9:0831 | Intel            | C610/X99 series chipset SPSR         | 14    |            | [2BAD48B8D4](<Server/Silicon Mechanics/Rackform/Rackform R309.v5/8442C8D36737/DEBIAN-12/6.1.0-21-AMD64/X86_64/2BAD48B8D4>) |
| 8086:a1ec | 17aa:1038 | Intel            | C620 Series Chipset Family MROM 0    | 13    |            | [CAFAEE2FC7](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC000QGE/C9B0658BA91C/DEBIAN-12/6.1.0-28-AMD64/X86_64/CAFAEE2FC7>) |
| 8086:a1ed | 15d9:0967 | Intel            | C620 Series Chipset Family MROM 1    | 13    |            | [01602FD84E](<Server/Supermicro/SYS-6019/SYS-6019P-WTR/0C2A376E8BE8/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/01602FD84E>) |
| 8086:a1ed | 17aa:1038 | Intel            | C620 Series Chipset Family MROM 1    | 13    |            | [CAFAEE2FC7](<Server/Lenovo/ThinkStation/ThinkStation P920 30BC000QGE/C9B0658BA91C/DEBIAN-12/6.1.0-28-AMD64/X86_64/CAFAEE2FC7>) |
| 8086:8d7c | 15d9:0857 | Intel            | C610/X99 series chipset SPSR         | 12    |            | [7B12EA87ED](<Server/Supermicro/X10/X10SRA/62E49A78B3EF/RHEL-8/4.18.0-553.16.1.EL8_10.X86_64/X86_64/7B12EA87ED>) |
| 8086:a1ec | 1849:a1ec | Intel            | C620 Series Chipset Family MROM 0    | 12    |            | [E9C9A4C51A](<Server/INFERIT/RS224/RS224 R1G3D32RU/68DD4BB73C8C/ROSA-12F.1/6.1.58-GENERIC-5ROSA2021.15-X86_64/X86_64/E9C9A4C51A>) |
| 8086:8d7c | 15d9:0844 | Intel            | C610/X99 series chipset SPSR         | 11    |            | [D24D2612FE](<Server/Supermicro/Super/Super Server/F4A31F1B8877/UBUNTU-22.04/5.15.0-117-GENERIC/X86_64/D24D2612FE>) |
| 8086:a1ec | 15d9:096d | Intel            | C620 Series Chipset Family MROM 0    | 10    |            | [80DB5BCB0E](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/F054CE6D6C8F/UBUNTU-22.04/6.2.0-33-GENERIC/X86_64/80DB5BCB0E>) |
| 8086:a1ec | 8086:0000 | Intel            | C620 Series Chipset Family MROM 0    | 10    |            | [0CE0F968A8](<Server/Intel/S2600/S2600STB/46A6757EC740/DEBIAN-12/6.8.12-4-PVE/X86_64/0CE0F968A8>) |
| 8086:8d7c | 1043:85f6 | Intel            | C610/X99 series chipset SPSR         | 9     |            | [3CB0E7E907](<Server/System76/Silverback/Silverback WS/10B1D15652E1/DEBIAN-12/6.1.0-17-AMD64/X86_64/3CB0E7E907>) |
| 8086:a1ec | 15d9:095d | Intel            | C620 Series Chipset Family MROM 0    | 9     |            | [A121B2A2E1](<Server/Supermicro/Super/Super Server/751AC2BC6C6F/CYBER-INFRASTRUCTURE-6.0.2/3.10.0-1160.105.1.AIP7.214.3/X86_64/A121B2A2E1>) |
| 8086:a1ec | 17aa:7808 | Intel            | C620 Series Chipset Family MROM 0    | 9     |            | [424E70419E](<Server/Lenovo/ThinkSystem/ThinkSystem SR570 -[7Y03CTO1WW]-/D3469A41F07A/XUBUNTU-18.04/4.15.0-213-GENERIC/X86_64/424E70419E>) |
| 8086:a1ed | 1028:0739 | Intel            | C620 Series Chipset Family MROM 1    | 9     |            | [BA0626CE0A](<Server/Dell/Precision/Precision 7820 Tower/3792A2743A38/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/BA0626CE0A>) |
| 8086:a1ed | 1590:00eb | Intel            | C620 Series Chipset Family MROM 1    | 9     |            | [4CDCAD1148](<Server/HPE/ProLiant/ProLiant DL380 Gen10/AD4000C49F0A/UBUNTU-22.10/5.19.0-21-GENERIC/X86_64/4CDCAD1148>) |
| 8086:a1ed | 15d9:096d | Intel            | C620 Series Chipset Family MROM 1    | 9     |            | [80DB5BCB0E](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/F054CE6D6C8F/UBUNTU-22.04/6.2.0-33-GENERIC/X86_64/80DB5BCB0E>) |
| 8086:a1ed | 1849:a1ed | Intel            | C620 Series Chipset Family MROM 1    | 9     |            | [7C5F635356](<Server/3Logic Group/Server/Server Graviton/339E3377D714/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/7C5F635356>) |
| 8086:a1ed | 8086:a1ed | Intel            | C620 Series Chipset Family MROM 1    | 9     |            | [943C34D6FE](<Server/Insyde/Purley/Purley/31EA1140F134/DEBIAN-11/5.15.158-2-PVE/X86_64/943C34D6FE>) |
| 8086:8d7c | 15d9:0834 | Intel            | C610/X99 series chipset SPSR         | 8     |            | [E343AB03F0](<Server/DEPO Computers/Super/Super Server/B1C00A465F68/DEBIAN-12/6.8.8-2-PVE/X86_64/E343AB03F0>) |
| 8086:a1ec | 1028:0716 | Intel            | C620 Series Chipset Family MROM 0    | 8     |            | [B89424543D](<Server/Dell/PowerEdge/PowerEdge R640/88100BFA40CD/DEBIAN-12/6.1.0-13-AMD64/X86_64/B89424543D>) |
| 8086:a1ec | 103c:81c6 | Intel            | C620 Series Chipset Family MROM 0    | 8     |            | [21781753FB](<Server/Hewlett-Packard/Z6/Z6 G4 Workstation/4E03B443521E/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/21781753FB>) |
| 8086:a1ec | 15d9:0981 | Intel            | C620 Series Chipset Family MROM 0    | 8     |            | [6CA957B8C9](<Server/Supermicro/SSG-6049/SSG-6049P-E1CR36L/A0CFEEE452D8/DEBIAN/6.6.15-AMD64/X86_64/6CA957B8C9>) |
| 8086:a1ec | 17aa:1037 | Intel            | C620 Series Chipset Family MROM 0    | 8     |            | [301BFF683B](<Server/Lenovo/ThinkStation/ThinkStation P720 30BBS3H50D/215583F782C1/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.10.4-1-DEFAULT/X86_64/301BFF683B>) |
| 8086:a1ed | 17aa:1037 | Intel            | C620 Series Chipset Family MROM 1    | 8     |            | [301BFF683B](<Server/Lenovo/ThinkStation/ThinkStation P720 30BBS3H50D/215583F782C1/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.10.4-1-DEFAULT/X86_64/301BFF683B>) |
| 1912:001b | 1d49:0a02 | Renesas Techn... | SH7758 PCIe End-Point [PBI]          | 7     |            | [9F36A4143D](<Server/Lenovo/System/System x3650 M5: -[8871AC1]/C84E3B816866/KUBUNTU-22.04/6.2.0-26-GENERIC/X86_64/9F36A4143D>) |
| 8086:6ff2 | 8086:6ff2 | Intel            | Broadwell-E CBo Unicast Registers 0  | 7     |            | [888A235104](<Server/Dell/PowerEdge/PowerEdge R730/B44B0E51BDB3/DEBIAN-12/6.8.12-4-PVE/X86_64/888A235104>) |
| 8086:6ff3 | 8086:6ff3 | Intel            | Broadwell-E CBo Unicast Registers 1  | 7     |            | [888A235104](<Server/Dell/PowerEdge/PowerEdge R730/B44B0E51BDB3/DEBIAN-12/6.8.12-4-PVE/X86_64/888A235104>) |
| 8086:8d7c | 1028:0639 | Intel            | C610/X99 series chipset SPSR         | 7     |            | [AFE0C7DFBE](<Server/Dell/PowerEdge/PowerEdge R430/F1FDD41026F0/DEBIAN-12/6.2.16-15-PVE/X86_64/AFE0C7DFBE>) |
| 8086:8d7c | 15d9:0832 | Intel            | C610/X99 series chipset SPSR         | 7     |            | [CFF09C5796](<Server/Supermicro/Super/Super Server/C341EAB89194/GENTOO-2.15/6.9.3-GENTOO-X86_64/X86_64/CFF09C5796>) |
| 8086:8d7c | 1d49:0a00 | Intel            | C610/X99 series chipset SPSR         | 7     |            | [9F36A4143D](<Server/Lenovo/System/System x3650 M5: -[8871AC1]/C84E3B816866/KUBUNTU-22.04/6.2.0-26-GENERIC/X86_64/9F36A4143D>) |
| 8086:a1ec | 1028:07c9 | Intel            | C620 Series Chipset Family MROM 0    | 7     |            | [069319FA9F](<Server/Dell/PowerEdge/PowerEdge R440/4A122AB18262/FEDORA-41/6.12.7-200.FC41.X86_64/X86_64/069319FA9F>) |
| 8086:a1ec | 103c:81c7 | Intel            | C620 Series Chipset Family MROM 0    | 7     |            | [03E2A5BAC1](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/5E9B675190B8/UBUNTU-22.04/6.2.0-37-GENERIC/X86_64/03E2A5BAC1>) |
| 8086:a1ec | 15d9:091c | Intel            | C620 Series Chipset Family MROM 0    | 7     |            | [0B1FEB460C](<Server/Supermicro/SYS-6019/SYS-6019U-TN4R4T/51D2EF357A4F/ROCKY-9.2/5.14.0-284.18.1.EL9_2.X86_64/X86_64/0B1FEB460C>) |

