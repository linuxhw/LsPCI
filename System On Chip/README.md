Most popular PCI devices in System On Chips
===========================================

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in System On Chips ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Usb controller ](#usb-controller-pci)

PCI Devices
-----------

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:2711 |           | Broadco... | PCI bridge                   | 12    | pcieport   | 401B4E187B |
| 10de:0faf | 10de:0000 | Nvidia     | PCI bridge                   | 6     | pcieport   | B301762DE6 |
| 10de:0fae | 10de:0000 | Nvidia     | PCI bridge                   | 4     | pcieport   | B301762DE6 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 6     | r8168      | B301762DE6 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 168c:0042 | 11ad:1806 | Qualcom... | QCA9377 802.11ac Wireless... | 1     | ath10k_pci | 5E682A0733 |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 1     | iwlwifi    | C72F8C76F7 |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 1     | iwlwifi    | 5458E9A8B8 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 1     | iwlwifi    | B301762DE6 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1106:3483 | 1106:3483 | VIA Tec... | VL805 USB 3.0 Host Contro... | 12    | xhci_hcd   | 401B4E187B |

