Most popular PCI devices in Firewalls
=====================================

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Firewalls ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Iommu ](#iommu-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Network ](#network-pci)
   * [ Smbus ](#smbus-pci)
   * [ Sound ](#sound-pci)
   * [ Storage/ata ](#storageata-pci)
   * [ System peripheral ](#system-peripheral-pci)
   * [ Usb controller ](#usb-controller-pci)

PCI Devices
-----------

Count  - number of computers with this device installed,
Driver - driver in use for this device,
Probe  - latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10b5:8605 | 10b5:8605 | PLX Technology   | PEX 8605 PCI Express 4-port Gen2 ... | 1     | pcieport   | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |
| 1a03:1150 | 1a03:1150 | ASPEED Techno... | AST1150 PCI-to-PCI Bridge            | 1     |            | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |
| 8086:0100 | 8086:0100 | Intel            | 2nd Generation Core Processor Fam... | 1     | snb_uncore | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:0101 | 8086:0101 | Intel            | Xeon E3-1200/2nd Generation Core ... | 1     | pcieport   | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:0105 | 8086:0105 | Intel            | Xeon E3-1200/2nd Generation Core ... | 1     | pcieport   | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:010d | 8086:010d | Intel            | Xeon E3-1200/2nd Generation Core ... | 1     | pcieport   | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:0c00 | 8086:0c00 | Intel            | 4th Gen Core Processor DRAM Contr... | 1     | hsw_uncore | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-20210611/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:0c01 | 8086:0c01 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 1     | pcieport   | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-20210611/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:1c10 | 8086:1c10 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pcieport   | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:1c12 | 8086:1c12 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pcieport   | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:1c14 | 8086:1c14 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pcieport   | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:1c16 | 8086:1c16 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pcieport   | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:1c18 | 8086:1c18 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pcieport   | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:1c1a | 8086:1c1a | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pcieport   | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:1c1c | 8086:1c1c | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pcieport   | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:1c1e | 8086:1c1e | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | pcieport   | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:1c56 | 8086:1c56 | Intel            | C206 Chipset LPC Controller          | 1     | lpc_ich    | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:1f0e |           | Intel            | Atom processor C2000 SoC Transact... | 1     |            | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |
| 8086:1f10 | 8086:7270 | Intel            | Atom processor C2000 PCIe Root Po... | 1     | pcieport   | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |
| 8086:1f11 | 8086:7270 | Intel            | Atom processor C2000 PCIe Root Po... | 1     | pcieport   | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |
| 8086:1f12 | 8086:7270 | Intel            | Atom processor C2000 PCIe Root Po... | 1     | pcieport   | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |
| 8086:1f13 | 8086:8086 | Intel            | Atom processor C2000 PCIe Root Po... | 1     | pcieport   | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |
| 8086:1f14 | 8086:0000 | Intel            | Atom processor C2000 RAS             | 1     |            | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |
| 8086:1f38 | 8086:7270 | Intel            | Atom processor C2000 PCU             | 1     | lpc_ich    | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |
| 8086:244e | 8086:244e | Intel            | 82801 PCI Bridge                     | 1     |            | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:8c10 | 8086:8c10 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | pcieport   | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-20210611/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:8c12 | 8086:8c12 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | pcieport   | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-20210611/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:8c14 | 8086:8c14 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | pcieport   | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-20210611/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:8c16 | 8086:8c16 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | pcieport   | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-20210611/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:8c18 | 8086:8c18 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | pcieport   | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-20210611/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:8c1a | 8086:8c1a | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | pcieport   | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-20210611/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:8c5c | 8086:8c5c | Intel            | H81 Express LPC Controller           | 1     | lpc_ich    | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-20210611/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1f18 | 8086:0000 | Intel            | Atom processor C2000 QAT             | 1     |            | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1a03:2000 | 1a03:2000 | ASPEED Techno... | ASPEED Graphics Family               | 1     | ast        | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |
| 8086:0102 | 8086:2111 | Intel            | 2nd Generation Core Processor Fam... | 1     | i915       | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:0402 | 8086:0402 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 1     | i915       | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-20210611/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |

### Iommu (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1f16 | 8086:0000 | Intel            | Atom processor C2000 RCEC            | 1     |            | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1533 | 15bb:30e0 | Intel            | I210 Gigabit Network Connection      | 1     | igb        | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-20210611/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:1f41 | 8086:1f41 | Intel            | Ethernet Connection I354             | 1     | igb        | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:150c | 8086:0000 | Intel            | 82583V Gigabit Network Connection    | 1     | e1000e     | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:1533 | ffff:0000 | Intel            | I210 Gigabit Network Connection      | 1     | igb        | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-20210611/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:1539 | 8086:0000 | Intel            | I211 Gigabit Network Connection      | 1     | igb        | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c22 | 8086:1c22 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     |            | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:1f3c | 8086:7270 | Intel            | Atom processor C2000 PCU SMBus       | 1     | i2c_i801   | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |
| 8086:8c22 | 8086:8c22 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | i2c_i801   | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-20210611/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0c0c | 8086:0c0c | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 1     | snd_hda... | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-20210611/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c02 | 8086:1c02 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ahci       | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:1f32 | 8086:7270 | Intel            | Atom processor C2000 AHCI SATA3 C... | 1     | ahci       | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |
| 8086:8c02 | 8086:8c02 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | ahci       | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-20210611/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1f15 | 8086:0000 | Intel            | Atom processor C2000 SMBus 2.0       | 1     | i2c_ismt   | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c26 | 8086:1c26 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ehci_pci   | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:1f2c | 8086:7270 | Intel            | Atom processor C2000 USB Enhanced... | 1     | ehci_pci   | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |
| 8086:8c26 | 8086:8c26 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | ehci_hc... | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-20210611/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:8c2d | 8086:8c2d | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | ehci_hc... | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-20210611/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:8c31 | 8086:8c31 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | xhci_pci   | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-20210611/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |

