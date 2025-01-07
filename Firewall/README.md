Most popular PCI devices in Firewalls
-------------------------------------

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Firewalls ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Iommu ](#iommu-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Network ](#network-pci)
   * [ Signal processing controller ](#signal-processing-controller-pci)
   * [ Smbus ](#smbus-pci)
   * [ Sound ](#sound-pci)
   * [ Storage/ata ](#storageata-pci)
   * [ Storage/ide ](#storageide-pci)
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
| 8086:244e | 8086:244e | Intel            | 82801 PCI Bridge                     | 2     |            | [A1C39D146E](<Firewall/Sophos/UTM/UTM/6DCD53966354/DEBIAN-12/6.1.0-10-AMD64/X86_64/A1C39D146E>) |
| 10b5:8604 | 10b5:8604 | PLX Technology   | PEX 8604 4-lane, 4-Port PCI Expre... | 1     | pcieport   | [A1C39D146E](<Firewall/Sophos/UTM/UTM/6DCD53966354/DEBIAN-12/6.1.0-10-AMD64/X86_64/A1C39D146E>) |
| 10b5:8605 | 10b5:8605 | PLX Technology   | PEX 8605 PCI Express 4-port Gen2 ... | 1     | pcieport   | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |
| 1106:0410 | 1106:0410 | VIA Technologies | VX900 Series Host Bridge: Host Co... | 1     |            | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 1106:1410 | 1106:1410 | VIA Technologies | VX900 Series Error Reporting         | 1     |            | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 1106:2410 | 1106:2410 | VIA Technologies | VX900 Series CPU Bus Controller      | 1     |            | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 1106:3410 | 1106:3410 | VIA Technologies | VX900 Series DRAM Bus Control        | 1     |            | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 1106:4410 | 1106:4410 | VIA Technologies | VX900 Series Power Management and... | 1     |            | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 1106:5410 | 1106:5410 | VIA Technologies | VX900 Series APIC and Central Tra... | 1     |            | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 1106:6410 | 1106:6410 | VIA Technologies | VX900 Series Scratch Registers       | 1     |            | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 1106:7410 | 1106:7410 | VIA Technologies | VX900 Series North-South Module I... | 1     |            | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 1106:8410 | 1106:8410 | VIA Technologies | VX900 Series Bus Control and Powe... | 1     |            | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 1106:a353 | 1106:a353 | VIA Technologies | VX8xx/900 Series South-North Modu... | 1     |            | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 1106:a410 |           | VIA Technologies | VX900 Series PCI Express Root Port 0 | 1     | pcieport   | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 1106:b353 |           | VIA Technologies | VX855/VX875/VX900 PCI to PCI Bridge  | 1     |            | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 1106:b410 |           | VIA Technologies | VX900 Series PCI Express Root Port 1 | 1     | pcieport   | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 1106:c410 |           | VIA Technologies | VX900 Series PCI Express Root Port 2 | 1     | pcieport   | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 1106:d410 |           | VIA Technologies | VX900 Series PCI Express Root Port 3 | 1     | pcieport   | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 1106:d410 | 1106:d410 | VIA Technologies | VX900 Series PCI Express Root Port 3 | 1     |            | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 1106:e410 |           | VIA Technologies | VX900 Series PCI Express Physical... | 1     |            | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 12d8:2404 |           | Pericom Semic... | PI7C9X2G404 EL/SL PCIe2 4-Port/4-... | 1     | pcieport   | [649258CEEE](<Firewall/Sophos/XG/XG/71FACD422839/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/649258CEEE>) |
| 1a03:1150 | 1a03:1150 | ASPEED Techno... | AST1150 PCI-to-PCI Bridge            | 1     |            | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |
| 8086:0100 | 8086:0100 | Intel            | 2nd Generation Core Processor Fam... | 1     | snb_uncore | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:0101 | 8086:0101 | Intel            | Xeon E3-1200/2nd Generation Core ... | 1     | pcieport   | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:0105 | 8086:0105 | Intel            | Xeon E3-1200/2nd Generation Core ... | 1     | pcieport   | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:010d | 8086:010d | Intel            | Xeon E3-1200/2nd Generation Core ... | 1     | pcieport   | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:0c00 | 8086:0c00 | Intel            | 4th Gen Core Processor DRAM Contr... | 1     | hsw_uncore | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-TUMBLEWEED-XXXXXXXX/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:0c01 | 8086:0c01 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 1     | pcieport   | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-TUMBLEWEED-XXXXXXXX/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:1901 | 8086:2015 | Intel            | 6th-10th Gen Core Processor PCIe ... | 1     | pcieport   | [649258CEEE](<Firewall/Sophos/XG/XG/71FACD422839/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/649258CEEE>) |
| 8086:190f | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 1     | skl_uncore | [649258CEEE](<Firewall/Sophos/XG/XG/71FACD422839/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/649258CEEE>) |
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
| 8086:27b8 | 8086:27b8 | Intel            | 82801GB/GR (ICH7 Family) LPC Inte... | 1     | lpc_ich    | [A1C39D146E](<Firewall/Sophos/UTM/UTM/6DCD53966354/DEBIAN-12/6.1.0-10-AMD64/X86_64/A1C39D146E>) |
| 8086:27d0 | 8086:27d0 | Intel            | NM10/ICH7 Family PCI Express Port 1  | 1     | pcieport   | [A1C39D146E](<Firewall/Sophos/UTM/UTM/6DCD53966354/DEBIAN-12/6.1.0-10-AMD64/X86_64/A1C39D146E>) |
| 8086:27d2 | 8086:27d2 | Intel            | NM10/ICH7 Family PCI Express Port 2  | 1     | pcieport   | [A1C39D146E](<Firewall/Sophos/UTM/UTM/6DCD53966354/DEBIAN-12/6.1.0-10-AMD64/X86_64/A1C39D146E>) |
| 8086:27d4 | 8086:27d4 | Intel            | NM10/ICH7 Family PCI Express Port 3  | 1     | pcieport   | [A1C39D146E](<Firewall/Sophos/UTM/UTM/6DCD53966354/DEBIAN-12/6.1.0-10-AMD64/X86_64/A1C39D146E>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1f18 | 8086:0000 | Intel            | Atom processor C2000 QAT             | 1     |            | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a13a | 8086:1999 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | mei_me     | [649258CEEE](<Firewall/Sophos/XG/XG/71FACD422839/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/649258CEEE>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1106:7122 | 1106:7122 | VIA Technologies | VX900 Graphics [Chrome9 HD]          | 1     |            | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 1a03:2000 | 1a03:2000 | ASPEED Techno... | ASPEED Graphics Family               | 1     | ast        | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |
| 8086:0102 | 8086:2111 | Intel            | 2nd Generation Core Processor Fam... | 1     | i915       | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:0402 | 8086:0402 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 1     | i915       | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-TUMBLEWEED-XXXXXXXX/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:1902 | 8086:0000 | Intel            | HD Graphics 510                      | 1     | i915       | [649258CEEE](<Firewall/Sophos/XG/XG/71FACD422839/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/649258CEEE>) |
| 8086:2e32 | 8086:2e32 | Intel            | 4 Series Chipset Integrated Graph... | 1     |            | [A1C39D146E](<Firewall/Sophos/UTM/UTM/6DCD53966354/DEBIAN-12/6.1.0-10-AMD64/X86_64/A1C39D146E>) |
| 8086:2e33 | 8086:2e32 | Intel            | 4 Series Chipset Integrated Graph... | 1     |            | [A1C39D146E](<Firewall/Sophos/UTM/UTM/6DCD53966354/DEBIAN-12/6.1.0-10-AMD64/X86_64/A1C39D146E>) |

### Iommu (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1f16 | 8086:0000 | Intel            | Atom processor C2000 RCEC            | 1     |            | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [649258CEEE](<Firewall/Sophos/XG/XG/71FACD422839/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/649258CEEE>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 1     | r8169      | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 8086:1533 | 15bb:30e0 | Intel            | I210 Gigabit Network Connection      | 1     | igb        | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-TUMBLEWEED-XXXXXXXX/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:1536 | 15bb:0000 | Intel            | I210 Gigabit Fiber Network Connec... | 1     | igb        | [649258CEEE](<Firewall/Sophos/XG/XG/71FACD422839/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/649258CEEE>) |
| 8086:1539 | 15bb:0000 | Intel            | I211 Gigabit Network Connection      | 1     | igb        | [649258CEEE](<Firewall/Sophos/XG/XG/71FACD422839/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/649258CEEE>) |
| 8086:1539 | 15bb:34e6 | Intel            | I211 Gigabit Network Connection      | 1     | igb        | [649258CEEE](<Firewall/Sophos/XG/XG/71FACD422839/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/649258CEEE>) |
| 8086:1f41 | 8086:1f41 | Intel            | Ethernet Connection I354             | 1     | igb        | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:10d3 | 8086:0000 | Intel            | 82574L Gigabit Network Connection    | 1     | e1000e     | [A1C39D146E](<Firewall/Sophos/UTM/UTM/6DCD53966354/DEBIAN-12/6.1.0-10-AMD64/X86_64/A1C39D146E>) |
| 8086:150c | 8086:0000 | Intel            | 82583V Gigabit Network Connection    | 1     | e1000e     | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:1533 | ffff:0000 | Intel            | I210 Gigabit Network Connection      | 1     | igb        | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-TUMBLEWEED-XXXXXXXX/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:1539 | 8086:0000 | Intel            | I211 Gigabit Network Connection      | 1     | igb        | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a131 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | intel_p... | [649258CEEE](<Firewall/Sophos/XG/XG/71FACD422839/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/649258CEEE>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c22 | 8086:1c22 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     |            | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:1f3c | 8086:7270 | Intel            | Atom processor C2000 PCU SMBus       | 1     | i2c_i801   | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |
| 8086:27da | 8086:27da | Intel            | NM10/ICH7 Family SMBus Controller    | 1     | i2c_i801   | [A1C39D146E](<Firewall/Sophos/UTM/UTM/6DCD53966354/DEBIAN-12/6.1.0-10-AMD64/X86_64/A1C39D146E>) |
| 8086:8c22 | 8086:8c22 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | i2c_i801   | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-TUMBLEWEED-XXXXXXXX/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:a123 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | i2c_i801   | [649258CEEE](<Firewall/Sophos/XG/XG/71FACD422839/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/649258CEEE>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1106:9170 | 1106:9170 | VIA Technologies | High Definition Audio Controller     | 1     |            | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 8086:0c0c | 8086:0c0c | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 1     | snd_hda... | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-TUMBLEWEED-XXXXXXXX/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:a170 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | snd_hda... | [649258CEEE](<Firewall/Sophos/XG/XG/71FACD422839/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/649258CEEE>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c02 | 8086:1c02 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ahci       | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:1f32 | 8086:7270 | Intel            | Atom processor C2000 AHCI SATA3 C... | 1     | ahci       | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |
| 8086:27c1 | 8086:27c0 | Intel            | NM10/ICH7 Family SATA Controller ... | 1     | ahci       | [A1C39D146E](<Firewall/Sophos/UTM/UTM/6DCD53966354/DEBIAN-12/6.1.0-10-AMD64/X86_64/A1C39D146E>) |
| 8086:8c02 | 8086:8c02 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | ahci       | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-TUMBLEWEED-XXXXXXXX/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:a102 | 8086:7270 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 1     | ahci       | [649258CEEE](<Firewall/Sophos/XG/XG/71FACD422839/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/649258CEEE>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1106:9001 | 1106:9001 | VIA Technologies | VX900 Series Serial-ATA Controller   | 1     | pata_vi... | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 8086:27df | 8086:27df | Intel            | 82801G (ICH7 Family) IDE Controller  | 1     | ata_pii... | [A1C39D146E](<Firewall/Sophos/UTM/UTM/6DCD53966354/DEBIAN-12/6.1.0-10-AMD64/X86_64/A1C39D146E>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1f15 | 8086:0000 | Intel            | Atom processor C2000 SMBus 2.0       | 1     | i2c_ismt   | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1106:3038 | 1106:3038 | VIA Technologies | VT82xx/62xx/VX700/8x0/900 UHCI US... | 1     | uhci_hcd   | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 1106:3104 | 1106:3104 | VIA Technologies | USB 2.0 EHCI-Compliant Host-Contr... | 1     | ehci_hcd   | [4ECB047DE3](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F100b/CB64B39F7F20/BARRACUDANGFIREWALL/2.6.32.9-70PH5.2.8.04.I686/I686/4ECB047DE3>) |
| 8086:1c26 | 8086:1c26 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ehci_pci   | [F6A9986FD7](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F380/C33B52A5617D/XUBUNTU-18.04/5.4.0-59-GENERIC/X86_64/F6A9986FD7>) |
| 8086:1f2c | 8086:7270 | Intel            | Atom processor C2000 USB Enhanced... | 1     | ehci_pci   | [4A3E898F12](<Firewall/Sophos/SG/SG/0A1460C28B04/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/4A3E898F12>) |
| 8086:27c8 | 8086:27c8 | Intel            | NM10/ICH7 Family USB UHCI Control... | 1     | uhci_hcd   | [A1C39D146E](<Firewall/Sophos/UTM/UTM/6DCD53966354/DEBIAN-12/6.1.0-10-AMD64/X86_64/A1C39D146E>) |
| 8086:27c9 | 8086:27c9 | Intel            | NM10/ICH7 Family USB UHCI Control... | 1     | uhci_hcd   | [A1C39D146E](<Firewall/Sophos/UTM/UTM/6DCD53966354/DEBIAN-12/6.1.0-10-AMD64/X86_64/A1C39D146E>) |
| 8086:27ca | 8086:27ca | Intel            | NM10/ICH7 Family USB UHCI Control... | 1     | uhci_hcd   | [A1C39D146E](<Firewall/Sophos/UTM/UTM/6DCD53966354/DEBIAN-12/6.1.0-10-AMD64/X86_64/A1C39D146E>) |
| 8086:27cb | 8086:27cb | Intel            | NM10/ICH7 Family USB UHCI Control... | 1     | uhci_hcd   | [A1C39D146E](<Firewall/Sophos/UTM/UTM/6DCD53966354/DEBIAN-12/6.1.0-10-AMD64/X86_64/A1C39D146E>) |
| 8086:27cc | 8086:27cc | Intel            | NM10/ICH7 Family USB2 EHCI Contro... | 1     | ehci_hc... | [A1C39D146E](<Firewall/Sophos/UTM/UTM/6DCD53966354/DEBIAN-12/6.1.0-10-AMD64/X86_64/A1C39D146E>) |
| 8086:8c26 | 8086:8c26 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | ehci_hc... | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-TUMBLEWEED-XXXXXXXX/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:8c2d | 8086:8c2d | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | ehci_hc... | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-TUMBLEWEED-XXXXXXXX/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:8c31 | 8086:8c31 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | xhci_pci   | [0012DC289A](<Firewall/Sophos/SG/SG/3C2B8CB52BB3/OPENSUSE-TUMBLEWEED-XXXXXXXX/5.12.9-1-DEFAULT/X86_64/0012DC289A>) |
| 8086:a12f | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | xhci_pci   | [649258CEEE](<Firewall/Sophos/XG/XG/71FACD422839/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/649258CEEE>) |

