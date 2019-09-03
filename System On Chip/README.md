Most popular PCI devices in System On Chips
===========================================

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in System On Chips ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)

PCI Devices
-----------

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0faf | 10de:0000 | Nvidia     | PCI bridge                   | 3     | pcieport   | 97C0D626A3 |
| 10de:0fae | 10de:0000 | Nvidia     | PCI bridge                   | 2     | pcieport   | 5458E9A8B8 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8168      | 97C0D626A3 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 168c:0042 | 11ad:1806 | Qualcom... | QCA9377 802.11ac Wireless... | 1     | ath10k_pci | 5E682A0733 |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 1     | iwlwifi    | 5458E9A8B8 |

