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
| 14e4:2711 |           | Broadcom   | BCM2711 PCIe Bridge          | 519   | pcieport   | D4EE4BA59F |
| 10de:0faf | 10de:0000 | Nvidia     | PCI bridge                   | 38    | pcieport   | 9EDD5667E5 |
| 10de:0fae | 10de:0000 | Nvidia     | PCI bridge                   | 19    | pcieport   | ECDDEDCFB7 |
| 10de:1ad1 |           | Nvidia     | Tegra PCIe x4/x8 Endpoint... | 7     | pcieport   | 7616B8F6B7 |
| 10de:1ad0 |           | Nvidia     | Tegra PCIe x8 Endpoint       | 4     | pcieport   | A1E1FC9259 |
| 1d87:0100 |           | Fuzhou ... | RK3399 PCI Express Root Port | 4     | pcieport   | 51C7D1655A |
| 19e5:a120 | 19e5:371e | Huawei ... | HiSilicon PCIe Root Port ... | 3     | pcieport   | 2A8B1A08BC |
| 19e5:a121 |           | Huawei ... | HiSilicon PCI-PCI Bridge     | 3     | pcieport   | 2A8B1A08BC |
| 10de:1ad2 |           | Nvidia     | Tegra PCIe x1 Root Complex   | 2     | pcieport   | A1E1FC9259 |
| 1d39:8060 |           |            | PCI bridge                   | 2     | pcieport   | 92829C951D |
| 11ab:0110 |           | Marvell... | 88F8040 PCI Express contr... | 1     | pcieport   | 864F7FA430 |
| 144d:a544 |           | Samsung... | Exynos 8890 PCIe Root Com... | 1     | pcieport   | 8AD4DEE3B1 |
| 16c3:abcd |           | Synopsys   | DWC_usb3 / PCIe bridge       | 1     | pcieport   | 14BC5C234D |
| 17cb:0104 |           | Qualcomm   | PCI bridge                   | 1     | pcieport   | AC382F40E8 |
| 1b21:1080 |           | ASMedia... | ASM1083/1085 PCIe to PCI ... | 1     |            | 7FD82B33F8 |
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
| 1002:67ff | 1002:0b04 | AMD        | Baffin [Radeon RX 550 640... | 1     | amdgpu     | 2A8B1A08BC |
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
| 10ec:8168 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 23    | r8168      | 9EDD5667E5 |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 15    | r8168      | CF8601E4F0 |
| 19e5:a222 |           | Huawei ... | HNS GE/10GE/25GE RDMA Net... | 2     | hns3       | 2A8B1A08BC |
| 19e5:a221 | 19e5:0000 | Huawei ... | HNS GE/10GE/25GE Network ... | 1     | hclge, ... | CBD268B858 |
| 19e5:a222 | 19e5:0000 | Huawei ... | HNS GE/10GE/25GE RDMA Net... | 1     | hclge, ... | CBD268B858 |
| 8086:1572 | 8086:0000 | Intel      | Ethernet Controller X710 ... | 1     | i40e       | CFBB1B9F64 |
| 8086:15b7 | 8086:0000 | Intel      | Ethernet Connection (2) I... | 1     | e1000e     | CFBB1B9F64 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 7     | iwlwifi    | CF8601E4F0 |
| 10ec:c822 | 1a3b:3751 | Realtek... | RTL8822CE 802.11ac PCIe W... | 6     | rtl8822ce  | 7616B8F6B7 |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 2     | iwlwifi    | 54592EC1A2 |
| 8086:24fd | 8086:1130 | Intel      | Wireless 8265 / 8275         | 2     | iwlwifi    | BE96BBE4F4 |
| 10ec:b822 | 103c:831b | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 1     | rtwpci     | 1B215DD48C |
| 10ec:c822 | 1a3b:3750 | Realtek... | RTL8822CE 802.11ac PCIe W... | 1     | rtl8822ce  | DB3EB249A1 |
| 168c:002a | 10cf:147c | Qualcom... | AR928X Wireless Network A... | 1     | ath9k      | ECDDEDCFB7 |
| 168c:003e |           | Qualcom... | QCA6174 802.11ac Wireless... | 1     | ath10k_pci | AC382F40E8 |
| 168c:0042 | 11ad:1806 | Qualcom... | QCA9377 802.11ac Wireless... | 1     | ath10k_pci | 5E682A0733 |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 1     | iwlwifi    | C72F8C76F7 |
| 8086:2725 | 8086:0024 | Intel      | Wi-Fi 6 AX210/AX211/AX411... | 1     |            | 1CCD6EEE0E |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:4415 | 14e4:0751 | Broadcom   | BCM4359 802.11ac Dual-Ban... | 1     | pcieh      | 8AD4DEE3B1 |
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
| 1002:aae0 | 1002:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 1     | snd_hda... | 2A8B1A08BC |
| 13f6:0111 | 13f6:0111 | C-Media... | CMI8738/CMI8768 PCI Audio    | 1     |            | 7FD82B33F8 |
| 8086:a171 | 8086:7270 | Intel      | CM238 HD Audio Controller    | 1     | snd_hda... | CFBB1B9F64 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 19e5:a235 |           | Huawei ... | HiSilicon AHCI HBA           | 3     | ahci       | 2A8B1A08BC |
| 1b4b:9171 | 1b4b:9171 | Marvell... | 88SE9171 SATA 6G Controller  | 2     | ahci       | A1E1FC9259 |
| 197b:0585 | 197b:0000 | JMicron... | JMB58x AHCI SATA controller  | 1     | ahci       | 33C6248333 |
| 1b4b:9183 | 1b4b:9183 | Marvell... | 88SS9183 PCIe SSD Controller | 1     |            | 5E07806B7E |
| 1b4b:9215 | 1b4b:9215 | Marvell... | 88SE9215 PCIe 2.0 x1 4-po... | 1     |            | 42C50AC49D |
| 1b4b:9230 | 1b4b:9230 | Marvell... | 88SE9230 PCIe 2.0 x2 4-po... | 1     | ahci       | 4B04BE2436 |
| 8086:a103 | 8086:7270 | Intel      | HM170/QM170 Chipset SATA ... | 1     | ahci       | CFBB1B9F64 |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 4     | nvme       | BD05C84564 |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 1     | nvme       | 51C7D1655A |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 1     | nvme       | 0965D05FE6 |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 1     | nvme       | A1E1FC9259 |
| 1987:5013 | 1987:5013 | Phison ... | PS5013 E13 NVMe Controller   | 1     | nvme       | 14BC5C234D |
| 1c5c:174a | 1c5c:174a | SK Hynix   | Gold P31 SSD                 | 1     | nvme       | BF8ABDFB09 |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 1     | nvme       | DF2CCD3ED4 |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 19e5:a25a |           | Huawei ... | HiSilicon RDE Engine         | 3     |            | 2A8B1A08BC |

### Storage/sas (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 19e5:a230 |           | Huawei ... | HiSilicon SAS 3.0 HBA        | 3     | hisi_sa... | 2A8B1A08BC |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 19e5:a122 |           | Huawei ... | HiSilicon Embedded DMA En... | 3     | hisi_dma   | 2A8B1A08BC |
| 8086:1911 | 8086:2015 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | CFBB1B9F64 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1106:3483 | 1106:3483 | VIA Tec... | VL805/806 xHCI USB 3.0 Co... | 516   | xhci_pci   | D4EE4BA59F |
| 19e5:a238 |           | Huawei ... | HiSilicon USB 3.0 Host Co... | 3     | xhci_pci   | 2A8B1A08BC |
| 19e5:a239 |           | Huawei ... | HiSilicon USB 2.0 2-port ... | 3     | ehci_pci   | 2A8B1A08BC |
| 19e5:a23b |           | Huawei ... | HiSilicon USB 1.1 Host Co... | 3     | ohci_pci   | 2A8B1A08BC |
| 1912:0015 | 19e5:3e22 | Renesas... | uPD720202 USB 3.0 Host Co... | 1     | xhci_pci   | BD05C84564 |
| 8086:a12f | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     | xhci_pci   | CFBB1B9F64 |

