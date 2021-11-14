Most popular PCI devices in Firewalls
=====================================

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Firewalls ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Network ](#network-pci)
   * [ Smbus ](#smbus-pci)
   * [ Sound ](#sound-pci)
   * [ Storage/ata ](#storageata-pci)
   * [ Usb controller ](#usb-controller-pci)

PCI Devices
-----------

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0100 | 8086:0100 | Intel      | 2nd Generation Core Proce... | 1     | snb_uncore | F6A9986FD7 |
| 8086:0101 | 8086:0101 | Intel      | Xeon E3-1200/2nd Generati... | 1     | pcieport   | F6A9986FD7 |
| 8086:0105 | 8086:0105 | Intel      | Xeon E3-1200/2nd Generati... | 1     | pcieport   | F6A9986FD7 |
| 8086:010d | 8086:010d | Intel      | Xeon E3-1200/2nd Generati... | 1     | pcieport   | F6A9986FD7 |
| 8086:0c00 | 8086:0c00 | Intel      | 4th Gen Core Processor DR... | 1     | hsw_uncore | 0012DC289A |
| 8086:0c01 | 8086:0c01 | Intel      | Xeon E3-1200 v3/4th Gen C... | 1     | pcieport   | 0012DC289A |
| 8086:1c10 | 8086:1c10 | Intel      | 6 Series/C200 Series Chip... | 1     | pcieport   | F6A9986FD7 |
| 8086:1c12 | 8086:1c12 | Intel      | 6 Series/C200 Series Chip... | 1     | pcieport   | F6A9986FD7 |
| 8086:1c14 | 8086:1c14 | Intel      | 6 Series/C200 Series Chip... | 1     | pcieport   | F6A9986FD7 |
| 8086:1c16 | 8086:1c16 | Intel      | 6 Series/C200 Series Chip... | 1     | pcieport   | F6A9986FD7 |
| 8086:1c18 | 8086:1c18 | Intel      | 6 Series/C200 Series Chip... | 1     | pcieport   | F6A9986FD7 |
| 8086:1c1a | 8086:1c1a | Intel      | 6 Series/C200 Series Chip... | 1     | pcieport   | F6A9986FD7 |
| 8086:1c1c | 8086:1c1c | Intel      | 6 Series/C200 Series Chip... | 1     | pcieport   | F6A9986FD7 |
| 8086:1c1e | 8086:1c1e | Intel      | 6 Series/C200 Series Chip... | 1     | pcieport   | F6A9986FD7 |
| 8086:1c56 | 8086:1c56 | Intel      | C206 Chipset LPC Controller  | 1     | lpc_ich    | F6A9986FD7 |
| 8086:244e | 8086:244e | Intel      | 82801 PCI Bridge             | 1     |            | F6A9986FD7 |
| 8086:8c10 | 8086:8c10 | Intel      | 8 Series/C220 Series Chip... | 1     | pcieport   | 0012DC289A |
| 8086:8c12 | 8086:8c12 | Intel      | 8 Series/C220 Series Chip... | 1     | pcieport   | 0012DC289A |
| 8086:8c14 | 8086:8c14 | Intel      | 8 Series/C220 Series Chip... | 1     | pcieport   | 0012DC289A |
| 8086:8c16 | 8086:8c16 | Intel      | 8 Series/C220 Series Chip... | 1     | pcieport   | 0012DC289A |
| 8086:8c18 | 8086:8c18 | Intel      | 8 Series/C220 Series Chip... | 1     | pcieport   | 0012DC289A |
| 8086:8c1a | 8086:8c1a | Intel      | 8 Series/C220 Series Chip... | 1     | pcieport   | 0012DC289A |
| 8086:8c5c | 8086:8c5c | Intel      | H81 Express LPC Controller   | 1     | lpc_ich    | 0012DC289A |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0102 | 8086:2111 | Intel      | 2nd Generation Core Proce... | 1     | i915       | F6A9986FD7 |
| 8086:0402 | 8086:0402 | Intel      | Xeon E3-1200 v3/4th Gen C... | 1     | i915       | 0012DC289A |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1533 | 15bb:30e0 | Intel      | I210 Gigabit Network Conn... | 1     | igb        | 0012DC289A |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:150c | 8086:0000 | Intel      | 82583V Gigabit Network Co... | 1     | e1000e     | F6A9986FD7 |
| 8086:1533 | ffff:0000 | Intel      | I210 Gigabit Network Conn... | 1     | igb        | 0012DC289A |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1c22 | 8086:1c22 | Intel      | 6 Series/C200 Series Chip... | 1     |            | F6A9986FD7 |
| 8086:8c22 | 8086:8c22 | Intel      | 8 Series/C220 Series Chip... | 1     | i2c_i801   | 0012DC289A |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0c0c | 8086:0c0c | Intel      | Xeon E3-1200 v3/4th Gen C... | 1     | snd_hda... | 0012DC289A |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1c02 | 8086:1c02 | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | F6A9986FD7 |
| 8086:8c02 | 8086:8c02 | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | 0012DC289A |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1c26 | 8086:1c26 | Intel      | 6 Series/C200 Series Chip... | 1     | ehci_pci   | F6A9986FD7 |
| 8086:8c26 | 8086:8c26 | Intel      | 8 Series/C220 Series Chip... | 1     | ehci_hc... | 0012DC289A |
| 8086:8c2d | 8086:8c2d | Intel      | 8 Series/C220 Series Chip... | 1     | ehci_hc... | 0012DC289A |
| 8086:8c31 | 8086:8c31 | Intel      | 8 Series/C220 Series Chip... | 1     | xhci_pci   | 0012DC289A |

