Most popular PCI devices in System On Chips
===========================================

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in System On Chips ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Multimedia controller ](#multimedia-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Network and computing encryption device ](#network-and-computing-encryption-device-pci)
   * [ Non-vga unclassified device ](#non-vga-unclassified-device-pci)
   * [ Signal processing controller ](#signal-processing-controller-pci)
   * [ Smbus ](#smbus-pci)
   * [ Sound ](#sound-pci)
   * [ Storage/ata ](#storageata-pci)
   * [ Storage/nvme ](#storagenvme-pci)
   * [ Storage/raid ](#storageraid-pci)
   * [ Storage/sas ](#storagesas-pci)
   * [ System peripheral ](#system-peripheral-pci)
   * [ Usb controller ](#usb-controller-pci)

PCI Devices
-----------

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:2711 |           | Broadcom   | BCM2711 PCIe Bridge          | 411   | pcieport   | 2C283A99A8 |
| 10de:0faf | 10de:0000 | Nvidia     | PCI bridge                   | 33    | pcieport   | 742BE0320C |
| 10de:0fae | 10de:0000 | Nvidia     | PCI bridge                   | 17    | pcieport   | 54592EC1A2 |
| 10de:1ad1 |           | Nvidia     | PCI bridge                   | 6     | pcieport   | E8C67DC172 |
| 10de:1ad0 |           | Nvidia     | PCI bridge                   | 4     | pcieport   | A1E1FC9259 |
| 10de:1ad2 |           | Nvidia     | PCI bridge                   | 2     | pcieport   | A1E1FC9259 |
| 19e5:a120 | 19e5:371e | Huawei ... | HiSilicon PCIe Root Port ... | 2     | pcieport   | BD05C84564 |
| 19e5:a121 |           | Huawei ... | HiSilicon PCI-PCI Bridge     | 2     |            | BD05C84564 |
| 11ab:0110 |           | Marvell... | Marvell PCI bridge           | 1     | pcieport   | 864F7FA430 |
| 17cb:0104 |           | Qualcomm   | PCI bridge                   | 1     | pcieport   | AC382F40E8 |
| 1b21:1080 |           | ASMedia... | ASM1083/1085 PCIe to PCI ... | 1     |            | 7FD82B33F8 |
| 1d87:0100 |           | Fuzhou ... | RK3399 PCI Express Root Port | 1     | pcieport   | EC849F00FC |
| 8086:1901 | 8086:2015 | Intel      | 6th-10th Gen Core Process... | 1     | pcieport   | CFBB1B9F64 |
| 8086:1905 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | pcieport   | CFBB1B9F64 |
| 8086:1909 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | pcieport   | CFBB1B9F64 |
| 8086:5910 | 8086:2015 | Intel      | Xeon E3-1200 v6/7th Gen C... | 1     | skl_uncore | CFBB1B9F64 |
| 8086:a118 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     | pcieport   | CFBB1B9F64 |
| 8086:a153 | 8086:7270 | Intel      | QM175 Chipset LPC/eSPI Co... | 1     |            | CFBB1B9F64 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a13a | 8086:1999 | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | CFBB1B9F64 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:6611 | 1642:1869 | AMD        | Oland [Radeon HD 8570 / R... | 1     | radeon     | BD05C84564 |
| 1002:6611 | 1642:1871 | AMD        | Oland [Radeon HD 8570 / R... | 1     | radeon     | CBD268B858 |
| 8086:591b | 8086:2015 | Intel      | HD Graphics 630              | 1     | i915       | CFBB1B9F64 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a121 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     |            | CFBB1B9F64 |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10cf:2049 | 13fe:8701 | Fujitsu... | Fujitsu Multimedia contro... | 1     |            | CFBB1B9F64 |
| 13fe:0059 | 13fe:0059 | Advantech  | Multimedia controller        | 1     |            | CFBB1B9F64 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8168 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 18    | r8168      | 742BE0320C |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 15    | r8168      | CF8601E4F0 |
| 19e5:a221 | 19e5:0000 | Huawei ... | HNS GE/10GE/25GE Network ... | 1     | hclge, ... | CBD268B858 |
| 19e5:a222 |           | Huawei ... | HNS GE/10GE/25GE RDMA Net... | 1     | hclge, ... | BD05C84564 |
| 19e5:a222 | 19e5:0000 | Huawei ... | HNS GE/10GE/25GE RDMA Net... | 1     | hclge, ... | CBD268B858 |
| 8086:1572 | 8086:0000 | Intel      | Ethernet Controller X710 ... | 1     | i40e       | CFBB1B9F64 |
| 8086:15b7 | 8086:0000 | Intel      | Ethernet Connection (2) I... | 1     | e1000e     | CFBB1B9F64 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 7     | iwlwifi    | CF8601E4F0 |
| 10ec:c822 | 1a3b:3751 | Realtek... | RTL8822CE 802.11ac PCIe W... | 5     | rtl8822ce  | E8C67DC172 |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 2     | iwlwifi    | 54592EC1A2 |
| 8086:24fd | 8086:1130 | Intel      | Wireless 8265 / 8275         | 2     | iwlwifi    | BE96BBE4F4 |
| 10ec:b822 | 103c:831b | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 1     | rtwpci     | 1B215DD48C |
| 10ec:c822 | 1a3b:3750 | Realtek... | RTL8822CE 802.11ac PCIe W... | 1     | rtl8822ce  | DB3EB249A1 |
| 168c:003e |           | Qualcom... | QCA6174 802.11ac Wireless... | 1     | ath10k_pci | AC382F40E8 |
| 168c:0042 | 11ad:1806 | Qualcom... | QCA9377 802.11ac Wireless... | 1     | ath10k_pci | 5E682A0733 |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 1     | iwlwifi    | C72F8C76F7 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:10d3 | 8086:a01f | Intel      | 82574L Gigabit Network Co... | 1     | e1000e     | AC382F40E8 |
| 8086:1531 | 8086:0000 | Intel      | I210 Gigabit Unprogrammed    | 1     | igb        | D48FD712A5 |
| 8086:1533 | ffff:0000 | Intel      | I210 Gigabit Network Conn... | 1     | igb        | CFBB1B9F64 |

### Network and computing encryption device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 19e5:a255 |           | Huawei ... | HiSilicon SEC Engine         | 1     | hisi_sec2  | BD05C84564 |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a124 |           | Intel      | 100 Series/C230 Series Ch... | 1     |            | CFBB1B9F64 |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a131 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | CFBB1B9F64 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a123 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     | i2c_i801   | CFBB1B9F64 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:aab0 | 1642:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 2     | snd_hda... | BD05C84564 |
| 13f6:0111 | 13f6:0111 | C-Media... | CMI8738/CMI8768 PCI Audio    | 1     |            | 7FD82B33F8 |
| 8086:a171 | 8086:7270 | Intel      | CM238 HD Audio Controller    | 1     | snd_hda... | CFBB1B9F64 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 19e5:a235 |           | Huawei ... | HiSilicon AHCI HBA           | 2     | ahci       | BD05C84564 |
| 1b4b:9171 | 1b4b:9171 | Marvell... | 88SE9171 SATA 6G Controller  | 2     | ahci       | A1E1FC9259 |
| 1b4b:9183 | 1b4b:9183 | Marvell... | 88SS9183 PCIe SSD Controller | 1     |            | 5E07806B7E |
| 8086:a103 | 8086:7270 | Intel      | HM170/QM170 Chipset SATA ... | 1     | ahci       | CFBB1B9F64 |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 4     | nvme       | BD05C84564 |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 1     | nvme       | 0965D05FE6 |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 1     | nvme       | A1E1FC9259 |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 1     | nvme       | DF2CCD3ED4 |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 1     | nvme       | EC849F00FC |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 19e5:a25a |           | Huawei ... | HiSilicon RDE Engine         | 2     |            | BD05C84564 |

### Storage/sas (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 19e5:a230 |           | Huawei ... | HiSilicon SAS 3.0 HBA        | 2     | hisi_sa... | BD05C84564 |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 19e5:a122 |           | Huawei ... | HiSilicon Embedded DMA En... | 2     | hisi_dma   | BD05C84564 |
| 8086:1911 | 8086:2015 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | CFBB1B9F64 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1106:3483 | 1106:3483 | VIA Tec... | VL805/806 xHCI USB 3.0 Co... | 409   | xhci_pci   | 2C283A99A8 |
| 19e5:a238 |           | Huawei ... | HiSilicon USB 3.0 Host Co... | 2     | xhci_pci   | BD05C84564 |
| 19e5:a239 |           | Huawei ... | HiSilicon USB 2.0 2-port ... | 2     | ehci_pci   | BD05C84564 |
| 19e5:a23b |           | Huawei ... | HiSilicon USB 1.1 Host Co... | 2     | ohci_pci   | BD05C84564 |
| 1912:0015 | 19e5:3e22 | Renesas... | uPD720202 USB 3.0 Host Co... | 1     | xhci_pci   | BD05C84564 |
| 8086:a12f | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     | xhci_pci   | CFBB1B9F64 |

