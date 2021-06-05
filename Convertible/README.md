Most popular PCI devices in Convertibles
========================================

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Convertibles ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Iommu ](#iommu-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Multimedia controller ](#multimedia-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Non-essential instrumentation ](#non-essential-instrumentation-pci)
   * [ Non-vga unclassified device ](#non-vga-unclassified-device-pci)
   * [ Sd host controller ](#sd-host-controller-pci)
   * [ Serial bus controller ](#serial-bus-controller-pci)
   * [ Serial controller ](#serial-controller-pci)
   * [ Signal processing controller ](#signal-processing-controller-pci)
   * [ Smbus ](#smbus-pci)
   * [ Sound ](#sound-pci)
   * [ Storage/ata ](#storageata-pci)
   * [ Storage/nvme ](#storagenvme-pci)
   * [ Storage/raid ](#storageraid-pci)
   * [ System peripheral ](#system-peripheral-pci)
   * [ Unclassified device ](#unclassified-device-pci)
   * [ Usb controller ](#usb-controller-pci)
   * [ Others ](#others-pci)

PCI Devices
-----------

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1448 |           | AMD        | Renoir Device 24: Function 0 | 126   |            | F77E2EBB10 |
| 1022:1449 |           | AMD        | Renoir Device 24: Function 1 | 126   |            | F77E2EBB10 |
| 1022:144a |           | AMD        | Renoir Device 24: Function 2 | 126   |            | F77E2EBB10 |
| 1022:144b |           | AMD        | Renoir Device 24: Function 3 | 126   | k10temp    | F77E2EBB10 |
| 1022:144c |           | AMD        | Renoir Device 24: Function 4 | 126   |            | F77E2EBB10 |
| 1022:144d |           | AMD        | Renoir Device 24: Function 5 | 126   |            | F77E2EBB10 |
| 1022:144e |           | AMD        | Renoir Device 24: Function 6 | 126   |            | F77E2EBB10 |
| 1022:144f |           | AMD        | Renoir Device 24: Function 7 | 126   |            | F77E2EBB10 |
| 1022:1632 |           | AMD        | Renoir PCIe Dummy Host Br... | 126   |            | F77E2EBB10 |
| 1022:1635 | 1022:1635 | AMD        | Renoir Internal PCIe GPP ... | 126   | pcieport   | F77E2EBB10 |
| 1022:1634 | 1022:1453 | AMD        | Renoir PCIe GPP Bridge       | 123   | pcieport   | F77E2EBB10 |
| 1022:1452 |           | AMD        | Family 17h (Models 00h-1f... | 111   |            | 168717D052 |
| 1022:15e8 |           | AMD        | Raven/Raven2 Device 24: F... | 111   |            | 168717D052 |
| 1022:15e9 |           | AMD        | Raven/Raven2 Device 24: F... | 111   |            | 168717D052 |
| 1022:15ea |           | AMD        | Raven/Raven2 Device 24: F... | 111   |            | 168717D052 |
| 1022:15eb |           | AMD        | Raven/Raven2 Device 24: F... | 111   | k10temp    | 168717D052 |
| 1022:15ec |           | AMD        | Raven/Raven2 Device 24: F... | 111   |            | 168717D052 |
| 1022:15ed |           | AMD        | Raven/Raven2 Device 24: F... | 111   |            | 168717D052 |
| 1022:15ee |           | AMD        | Raven/Raven2 Device 24: F... | 111   |            | 168717D052 |
| 1022:15ef |           | AMD        | Raven/Raven2 Device 24: F... | 111   |            | 168717D052 |
| 1022:15db | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 109   | pcieport   | 168717D052 |
| 1022:1630 | 1022:1630 | AMD        | Renoir Root Complex          | 63    |            | 64A9E43743 |
| 1022:15dc | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 55    | pcieport   | 168717D052 |
| 1022:790e | 1022:790e | AMD        | FCH LPC Bridge               | 49    |            | 64A9E43743 |
| 8086:9d14 | 17aa:3835 | Intel      | Sunrise Point-LP PCI Expr... | 36    | pcieport   | 44E586277C |
| 8086:9d15 | 17aa:382f | Intel      | Sunrise Point-LP PCI Expr... | 36    | pcieport   | 44E586277C |
| 8086:9d4e | 17aa:3803 | Intel      | Sunrise Point LPC Control... | 31    |            | 44E586277C |
| 8086:0284 | 17aa:3802 | Intel      | Comet Lake PCH-LP LPC Pre... | 28    |            | F72E765EF0 |
| 8086:02b4 | 17aa:3803 | Intel      | Comet Lake PCI Express Ro... | 28    | pcieport   | F72E765EF0 |
| 1022:15d3 | 1022:1453 | AMD        | Raven/Raven2 PCIe GPP Bri... | 27    | pcieport   | 57651669E3 |
| 1022:1630 | 103c:876f | AMD        | Renoir Root Complex          | 27    |            | 08B513769D |
| 1022:790e | 103c:876f | AMD        | FCH LPC Bridge               | 27    |            | 08B513769D |
| 8086:2280 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 27    | iosf_mb... | 1866D29174 |
| 8086:229c | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 27    | lpc_ich    | 1866D29174 |
| 8086:5ae8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | lpc_ich    | 378291C3E0 |
| 1022:1630 | 103c:876e | AMD        | Renoir Root Complex          | 26    |            | F77E2EBB10 |
| 1022:790e | 103c:876e | AMD        | FCH LPC Bridge               | 26    |            | F77E2EBB10 |
| 8086:5af0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 26    |            | 378291C3E0 |
| 8086:5ad7 |           | Intel      | Celeron N3350/Pentium N42... | 25    | pcieport   | 378291C3E0 |
| 8086:9b61 | 17aa:380a | Intel      | Comet Lake-U v1 4c Host B... | 25    | skl_uncore | F72E765EF0 |
| 8086:15d3 | 2222:1111 | Intel      | JHL6540 Thunderbolt 3 Bri... | 24    | pcieport   | 570666D7D6 |
| 8086:5914 | 103c:83b9 | Intel      | Xeon E3-1200 v6/7th Gen C... | 24    | skl_uncore | 2C533BE257 |
| 8086:9d10 | 103c:83b9 | Intel      | Sunrise Point-LP PCI Expr... | 24    | pcieport   | 2C533BE257 |
| 8086:9d11 | 103c:83b9 | Intel      | Sunrise Point-LP PCI Expr... | 24    | pcieport   | 2C533BE257 |
| 8086:9d14 | 103c:83b9 | Intel      | Sunrise Point-LP PCI Expr... | 24    | pcieport   | 2C533BE257 |
| 8086:9d18 | 103c:83b9 | Intel      | Sunrise Point-LP PCI Expr... | 24    | pcieport   | 2C533BE257 |
| 8086:9d4e | 103c:83b9 | Intel      | Sunrise Point LPC Control... | 24    |            | 2C533BE257 |
| 8086:15d3 | 103c:8514 | Intel      | JHL6540 Thunderbolt 3 Bri... | 23    | pcieport   | 2352CAA9CF |
| 8086:3e34 | 103c:8514 | Intel      | Coffee Lake HOST and DRAM... | 23    | skl_uncore | 2352CAA9CF |
| 8086:9d84 | 103c:8514 | Intel      | Cannon Point-LP LPC Contr... | 23    |            | 2352CAA9CF |
| 8086:9db4 | 103c:8514 | Intel      | Cannon Point-LP PCI Expre... | 23    | pcieport   | 2352CAA9CF |
| 8086:9dba | 103c:8514 | Intel      | 300 Series Chipset PCIe P... | 23    | pcieport   | 2352CAA9CF |
| 8086:9dbc | 103c:8514 | Intel      | Cannon Point-LP PCI Expre... | 23    | pcieport   | 2352CAA9CF |
| 1022:15d0 | 103c:85dd | AMD        | Raven/Raven2 Root Complex    | 22    |            | A93B2565DF |
| 1022:15d3 | 103c:85dd | AMD        | Raven/Raven2 PCIe GPP Bri... | 22    | pcieport   | A93B2565DF |
| 1022:790e | 103c:85dd | AMD        | FCH LPC Bridge               | 22    |            | A93B2565DF |
| 8086:9db7 | 8086:9db7 | Intel      | 300 Series Chipset PCIe P... | 22    | pcieport   | CD156B08D8 |
| 8086:3482 | 17aa:3812 | Intel      | Ice Lake-LP LPC Controller   | 21    |            | 7C965E245C |
| 8086:34b8 | 17aa:3810 | Intel      | Ice Lake-LP PCIe Port #1     | 21    | pcieport   | 7C965E245C |
| 8086:34be | 17aa:3801 | Intel      | Ice Lake-LP PCIe Port #7     | 21    | pcieport   | 7C965E245C |
| 8086:5904 | 17aa:382b | Intel      | Xeon E3-1200 v6/7th Gen C... | 21    | skl_uncore | 44E586277C |
| 8086:31d8 | 8086:7270 | Intel      | Gemini Lake PCI Express R... | 20    | pcieport   | 38E5F73567 |
| 8086:31e8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    |            | 38E5F73567 |
| 8086:34b0 | 17aa:380f | Intel      | Ice Lake-LP PCI Express R... | 20    | pcieport   | 7C965E245C |
| 8086:8a12 | 17aa:3807 | Intel      | Ice Lake-LP Processor Hos... | 20    | icl_uncore | 7C965E245C |
| 8086:9d84 | 17aa:380c | Intel      | Cannon Point-LP LPC Contr... | 20    |            | CD156B08D8 |
| 8086:15d3 | 17aa:2292 | Intel      | JHL6540 Thunderbolt 3 Bri... | 19    | pcieport   | 32CA60DCEA |
| 8086:1904 | 17aa:2238 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 19    | skl_uncore | D878C63FE4 |
| 8086:9d10 | 17aa:2238 | Intel      | Sunrise Point-LP PCI Expr... | 19    | pcieport   | D878C63FE4 |
| 8086:9d12 | 17aa:2238 | Intel      | Sunrise Point-LP PCI Expr... | 19    | pcieport   | D878C63FE4 |
| 8086:9d14 | 17aa:3856 | Intel      | Sunrise Point-LP PCI Expr... | 19    | pcieport   | 1A0B1FFDBD |
| 8086:9d18 | 17aa:3844 | Intel      | Sunrise Point-LP PCI Expr... | 19    | pcieport   | 1A0B1FFDBD |
| 8086:9d48 | 17aa:2238 | Intel      | Sunrise Point-LP LPC Cont... | 19    |            | D878C63FE4 |
| 8086:9d4e | 17aa:3814 | Intel      | Sunrise Point LPC Control... | 19    |            | 1A0B1FFDBD |
| 8086:3e34 | 17aa:3808 | Intel      | Coffee Lake HOST and DRAM... | 18    | skl_uncore | CD156B08D8 |
| 8086:9db0 | 17aa:380f | Intel      | Cannon Point-LP PCI Expre... | 18    | pcieport   | AC5C64FED1 |
| 1022:15d0 | 103c:85de | AMD        | Raven/Raven2 Root Complex    | 17    |            | 9E86C8EDE5 |
| 1022:15d3 | 103c:85de | AMD        | Raven/Raven2 PCIe GPP Bri... | 17    | pcieport   | 9E86C8EDE5 |
| 1022:790e | 103c:85de | AMD        | FCH LPC Bridge               | 17    |            | 9E86C8EDE5 |
| 8086:3482 | 1028:08b0 | Intel      | Ice Lake-LP LPC Controller   | 17    |            | 6B27A727BE |
| 8086:34b7 | 1028:08b0 | Intel      | Ice Lake-LP PCI Express R... | 17    | pcieport   | 6B27A727BE |
| 8086:5914 | 17aa:3820 | Intel      | Xeon E3-1200 v6/7th Gen C... | 17    | skl_uncore | 86A25931BD |
| 8086:5914 | 17aa:3821 | Intel      | Xeon E3-1200 v6/7th Gen C... | 17    | skl_uncore | 6E045B787A |
| 8086:8a12 | 1028:08b0 | Intel      | Ice Lake-LP Processor Hos... | 17    | icl_uncore | 6B27A727BE |
| 8086:8a1d |           | Intel      | Ice Lake Thunderbolt 3 PC... | 17    | pcieport   | 6B27A727BE |
| 8086:9d10 | 17aa:384f | Intel      | Sunrise Point-LP PCI Expr... | 17    | pcieport   | 6E045B787A |
| 8086:9d18 | 17aa:382a | Intel      | Sunrise Point-LP PCI Expr... | 17    | pcieport   | 480F534F9F |
| 8086:9d18 | 17aa:384b | Intel      | Sunrise Point-LP PCI Expr... | 17    | pcieport   | 6E045B787A |
| 8086:9d4e | 17aa:3816 | Intel      | Sunrise Point LPC Control... | 17    |            | 6E045B787A |
| 1022:15d0 | 17aa:380a | AMD        | Raven/Raven2 Root Complex    | 16    |            | 57651669E3 |
| 1022:790e | 17aa:3819 | AMD        | FCH LPC Bridge               | 16    |            | 57651669E3 |
| 8086:34b0 | 1028:08b0 | Intel      | Ice Lake-LP PCI Express R... | 16    | pcieport   | 6B27A727BE |
| 8086:3e34 | 17aa:2292 | Intel      | Coffee Lake HOST and DRAM... | 16    | skl_uncore | 3795F3DF87 |
| 8086:9d14 | 17aa:385b | Intel      | Sunrise Point-LP PCI Expr... | 16    | pcieport   | 6E045B787A |
| 8086:9d84 | 17aa:2292 | Intel      | Cannon Point-LP LPC Contr... | 16    |            | 3795F3DF87 |
| 8086:9db0 | 17aa:2292 | Intel      | Cannon Point-LP PCI Expre... | 16    | pcieport   | 3795F3DF87 |
| 1022:15d0 | 103c:83c6 | AMD        | Raven/Raven2 Root Complex    | 15    |            | 168717D052 |
| 1022:15d3 | 103c:83c6 | AMD        | Raven/Raven2 PCIe GPP Bri... | 15    | pcieport   | 168717D052 |
| 1022:790e | 103c:83c6 | AMD        | FCH LPC Bridge               | 15    |            | 168717D052 |
| 8086:3482 | 17aa:380e | Intel      | Ice Lake-LP LPC Controller   | 15    |            | 2E19A058F9 |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:522a | 17aa:380e | Realtek... | RTS522A PCI Express Card ... | 39    | rtsx_pci   | CC7CB4A34E |
| 10ec:5229 | 17aa:3832 | Realtek... | RTS5229 PCI Express Card ... | 36    | rtsx_pci   | 44E586277C |
| 10ec:522a | 103c:876f | Realtek... | RTS522A PCI Express Card ... | 27    | rtsx_pci   | 08B513769D |
| 10ec:522a | 103c:876e | Realtek... | RTS522A PCI Express Card ... | 26    | rtsx_pci   | F77E2EBB10 |
| 10ec:525a | 103c:83b9 | Realtek... | RTS525A PCI Express Card ... | 24    | rtsx_pci   | 2C533BE257 |
| 10ec:525a | 103c:8514 | Realtek... | RTS525A PCI Express Card ... | 23    | rtsx_pci   | 2352CAA9CF |
| 10ec:522a | 103c:85dd | Realtek... | RTS522A PCI Express Card ... | 22    | rtsx_pci   | A93B2565DF |
| 10ec:522a | 103c:85de | Realtek... | RTS522A PCI Express Card ... | 17    | rtsx_pci   | 9E86C8EDE5 |
| 10ec:525a | 1028:08b0 | Realtek... | RTS525A PCI Express Card ... | 17    | rtsx_pci   | 6B27A727BE |
| 10ec:525a | 17aa:2238 | Realtek... | RTS525A PCI Express Card ... | 17    | rtsx_pci   | D878C63FE4 |
| 10ec:522a | 103c:83c6 | Realtek... | RTS522A PCI Express Card ... | 15    | rtsx_pci   | 168717D052 |
| 10ec:522a | 103c:830f | Realtek... | RTS522A PCI Express Card ... | 14    | rtsx_pci   | B6BC75336E |
| 10ec:522a | 103c:8496 | Realtek... | RTS522A PCI Express Card ... | 14    | rtsx_pci   | 8A63E2E055 |
| 10ec:5229 | 17aa:380d | Realtek... | RTS5229 PCI Express Card ... | 13    | rtsx_pci   | 1E4A851AD2 |
| 10ec:5229 | 17aa:381d | Realtek... | RTS5229 PCI Express Card ... | 13    | rtsx_pci   | 15C0F31B91 |
| 10ec:522a | 103c:827d | Realtek... | RTS522A PCI Express Card ... | 13    | rtsx_pci   | 51178C1953 |
| 10ec:522a | 103c:8497 | Realtek... | RTS522A PCI Express Card ... | 13    | rtsx_pci   | 2910A4173E |
| 10ec:525a | 103c:83bb | Realtek... | RTS525A PCI Express Card ... | 13    | rtsx_pci   | BA09E3B76F |
| 10ec:525a | 1028:077a | Realtek... | RTS525A PCI Express Card ... | 11    | rtsx_pci   | C0A9C9443B |
| 10ec:525a | 17aa:224e | Realtek... | RTS525A PCI Express Card ... | 11    | rtsx_pci   | B866426527 |
| 10ec:5229 | 17aa:381b | Realtek... | RTS5229 PCI Express Card ... | 10    | rtsx_pci   | A4D6F3CCE4 |
| 10ec:522a | 103c:8735 | Realtek... | RTS522A PCI Express Card ... | 10    | rtsx_pci   | F36EA99568 |
| 10ec:522a | 17aa:3809 | Realtek... | RTS522A PCI Express Card ... | 10    | rtsx_pci   | 7C965E245C |
| 10ec:5227 | 103c:81a1 | Realtek... | RTS5227 PCI Express Card ... | 9     | rtsx_pci   | B37CBA5DF4 |
| 10ec:5229 | 103c:82e1 | Realtek... | RTS5229 PCI Express Card ... | 9     | rtsx_pci   | 8638532EEB |
| 10ec:522a | 103c:80d1 | Realtek... | RTS522A PCI Express Card ... | 9     | rtsx_pci   | 629D516666 |
| 10ec:522a | 17aa:5078 | Realtek... | RTS522A PCI Express Card ... | 9     | rtsx_pci   | 7C78B71A99 |
| 10ec:525a | 1028:080d | Realtek... | RTS525A PCI Express Card ... | 9     | rtsx_pci   | C28F77B8F1 |
| 10ec:5260 | 1028:09ff | Realtek... | RTS5260 PCI Express Card ... | 9     | rtsx_pci   | AD3C1FB56A |
| 10ec:522a | 103c:86b1 | Realtek... | RTS522A PCI Express Card ... | 7     | rtsx_pci   | 093BEED213 |
| 10ec:522a | 103c:86b2 | Realtek... | RTS522A PCI Express Card ... | 7     | rtsx_pci   | 42A03DCD82 |
| 10ec:522a | 17aa:506d | Realtek... | RTS522A PCI Express Card ... | 7     | rtsx_pci   | 847655CB40 |
| 10ec:525a | 1028:09cd | Realtek... | RTS525A PCI Express Card ... | 7     | rtsx_pci   | BC7C58F248 |
| 10ec:525a | 103c:863f | Realtek... | RTS525A PCI Express Card ... | 7     | rtsx_pci   | 638C4207CE |
| 10ec:525a | 103c:86f9 | Realtek... | RTS525A PCI Express Card ... | 7     | rtsx_pci   | A18B247E3D |
| 10ec:5227 | 103c:802b | Realtek... | RTS5227 PCI Express Card ... | 6     | rtsx_pci   | 4EDDB18ED9 |
| 10ec:5229 | 1025:1176 | Realtek... | RTS5229 PCI Express Card ... | 6     | rtsx_pci   | 566FA6B1D5 |
| 10ec:522a | 103c:8484 | Realtek... | RTS522A PCI Express Card ... | 6     | rtsx_pci   | D46010346C |
| 10ec:522a | 17aa:2237 | Realtek... | RTS522A PCI Express Card ... | 6     | rtsx_pci   | 2A0ECA4670 |
| 10ec:5229 | 103c:81aa | Realtek... | RTS5229 PCI Express Card ... | 5     | rtsx_pci   | 633D386331 |
| 10ec:522a | 103c:81a9 | Realtek... | RTS522A PCI Express Card ... | 5     | rtsx_pci   | 0BB3F77C75 |
| 10ec:522a | 103c:81ad | Realtek... | RTS522A PCI Express Card ... | 5     | rtsx_pci   | CE728E8715 |
| 10ec:522a | 103c:8313 | Realtek... | RTS522A PCI Express Card ... | 5     | rtsx_pci   | DCD840E8A2 |
| 10ec:522a | 103c:8483 | Realtek... | RTS522A PCI Express Card ... | 5     | rtsx_pci   | C41A1DE997 |
| 10ec:522a | 103c:85e7 | Realtek... | RTS522A PCI Express Card ... | 5     | rtsx_pci   | 169477DE3F |
| 10ec:522a | 17aa:506c | Realtek... | RTS522A PCI Express Card ... | 5     | rtsx_pci   | 6C4ABD0606 |
| 10ec:522a | 17aa:5077 | Realtek... | RTS522A PCI Express Card ... | 5     | rtsx_pci   | 87DA71BBB9 |
| 10ec:525a | 1028:08b6 | Realtek... | RTS525A PCI Express Card ... | 5     | rtsx_pci   | B0722E1B57 |
| 10ec:525a | 103c:827f | Realtek... | RTS525A PCI Express Card ... | 5     | rtsx_pci   | BD5BDFD31F |
| 10ec:525a | 103c:87f7 | Realtek... | RTS525A PCI Express Card ... | 5     | rtsx_pci   | 48A0452D0B |
| 10ec:5227 | 103c:802d | Realtek... | RTS5227 PCI Express Card ... | 4     | rtsx_pci   | 24D17544A9 |
| 10ec:5229 | 17aa:3810 | Realtek... | RTS5229 PCI Express Card ... | 4     | rtsx_pci   | DC41704AEC |
| 10ec:522a | 103c:806e | Realtek... | RTS522A PCI Express Card ... | 4     | rtsx_pci   | A8AA7A1D17 |
| 10ec:522a | 103c:81a7 | Realtek... | RTS522A PCI Express Card ... | 4     | rtsx_pci   | BC77E670A5 |
| 10ec:522a | 103c:83c4 | Realtek... | RTS522A PCI Express Card ... | 4     | rtsx_pci   | 3F62C672FB |
| 10ec:522a | 103c:850c | Realtek... | RTS522A PCI Express Card ... | 4     | rtsx_pci   | EEC05D1BF9 |
| 10ec:522a | 103c:87f4 | Realtek... | RTS522A PCI Express Card ... | 4     | rtsx_pci   | A0A4DFE970 |
| 10ec:522a | 17aa:3817 | Realtek... | RTS522A PCI Express Card ... | 4     | rtsx_pci   | D9D123FF85 |
| 10ec:522a | 17aa:5061 | Realtek... | RTS522A PCI Express Card ... | 4     | rtsx_pci   | 9FCFE8BF6A |
| 10ec:525a | 1028:08e2 | Realtek... | RTS525A PCI Express Card ... | 4     | rtsx_pci   | 31C59F8FC7 |
| 10ec:525a | 103c:82c1 | Realtek... | RTS525A PCI Express Card ... | 4     | rtsx_pci   | CF06BA276E |
| 10ec:525a | 103c:8518 | Realtek... | RTS525A PCI Express Card ... | 4     | rtsx_pci   | 64C5568456 |
| 10ec:525a | 103c:863e | Realtek... | RTS525A PCI Express Card ... | 4     | rtsx_pci   | B47C4EF32E |
| 10ec:525a | 103c:86fa | Realtek... | RTS525A PCI Express Card ... | 4     | rtsx_pci   | 520E728AF7 |
| 10ec:525a | 103c:8709 | Realtek... | RTS525A PCI Express Card ... | 4     | rtsx_pci   | 6B850F8E6F |
| 10ec:5227 | 103c:804e | Realtek... | RTS5227 PCI Express Card ... | 3     | rtsx_pci   | B4E75E63FB |
| 10ec:522a | 103c:82b7 | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | 3B8F11D2DB |
| 10ec:522a | 103c:8310 | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | D7D0DE8CF4 |
| 10ec:522a | 103c:850d | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | 987181B525 |
| 10ec:522a | 103c:875b | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | 7490F0847D |
| 10ec:522a | 103c:87a9 | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | F8C5A69D8E |
| 10ec:522a | 103c:8825 | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | 7FC1E5873C |
| 10ec:522a | 17aa:2294 | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | 09DC5430DA |
| 10ec:522a | 17aa:3813 | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | 998884BE70 |
| 10ec:522a | 17aa:381e | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | 63C11CE610 |
| 10ec:525a | 103c:83ba | Realtek... | RTS525A PCI Express Card ... | 3     | rtsx_pci   | FB88A217E9 |
| 10ec:525a | 103c:844f | Realtek... | RTS525A PCI Express Card ... | 3     | rtsx_pci   | 2668A6580A |
| 10ec:5227 | 103c:804f | Realtek... | RTS5227 PCI Express Card ... | 2     | rtsx_pci   | E5C02D2922 |
| 10ec:5229 | 103c:81a2 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 35DC79725B |
| 10ec:522a | 103c:8143 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 03065735FF |
| 10ec:522a | 103c:81ac | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 235D55372B |
| 10ec:522a | 103c:8251 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | A758FDF9AF |
| 10ec:522a | 103c:8311 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 514D46C27F |
| 10ec:522a | 103c:8314 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 5CF089CFA1 |
| 10ec:522a | 103c:83c9 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 8BF489A0CB |
| 10ec:522a | 103c:85e6 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 0A7C046DCE |
| 10ec:522a | 17aa:22ad | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 8E3E2A94C3 |
| 10ec:522a | 17aa:3811 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 85121B8AEC |
| 10ec:522a | 17aa:3818 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | B27B2EACEE |
| 10ec:525a | 1028:09c6 | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx_pci   | B776BEB710 |
| 10ec:525a | 1028:0a37 | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx_pci   | C5856B1EA0 |
| 10ec:525a | 103c:8519 | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx_pci   | AED071D8CE |
| 10ec:525a | 103c:86e5 | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx_pci   | FD2D87232F |
| 10ec:5229 | 103c:8074 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 51A2F6EB71 |
| 10ec:5229 | 103c:81ab | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | D98A9E0C48 |
| 10ec:5229 | 103c:84fa | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 345648FE18 |
| 10ec:5229 | 17aa:3801 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | F6650D66F7 |
| 10ec:522a | 103c:80cf | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 15B7980DAF |
| 10ec:522a | 103c:80d0 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 97ED13A8C0 |
| 10ec:522a | 103c:8252 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | E610D18176 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d3a | 17aa:383e | Intel      | Sunrise Point-LP CSME HEC... | 36    | mei_me     | 44E586277C |
| 8086:02c7 | 17aa:3801 | Intel      | Comet Lake PCH-LP LPSS: U... | 28    | intel_lpss | F72E765EF0 |
| 8086:02e0 | 17aa:3803 | Intel      | Comet Lake Management Eng... | 28    | mei_me     | F72E765EF0 |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 26    | mei_me     | 378291C3E0 |
| 8086:9d3a | 103c:83b9 | Intel      | Sunrise Point-LP CSME HEC... | 24    | mei_me     | 2C533BE257 |
| 8086:9de0 | 103c:8514 | Intel      | Cannon Point-LP MEI Contr... | 23    | mei_me     | 2352CAA9CF |
| 8086:9de0 | 17aa:3805 | Intel      | Cannon Point-LP MEI Contr... | 22    | mei_me     | CD156B08D8 |
| 8086:34e0 | 17aa:3801 | Intel      | Ice Lake-LP Management En... | 21    | mei_me     | 7C965E245C |
| 8086:319a | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | mei_me     | 38E5F73567 |
| 8086:9d3a | 17aa:2238 | Intel      | Sunrise Point-LP CSME HEC... | 19    | mei_me     | D878C63FE4 |
| 8086:9d3a | 17aa:3801 | Intel      | Sunrise Point-LP CSME HEC... | 19    | mei_me     | 1A0B1FFDBD |
| 8086:34e0 | 1028:08b0 | Intel      | Ice Lake-LP Management En... | 17    | mei_me     | 6B27A727BE |
| 8086:9d3a | 17aa:3868 | Intel      | Sunrise Point-LP CSME HEC... | 17    | mei_me     | 6E045B787A |
| 8086:9de0 | 17aa:2292 | Intel      | Cannon Point-LP MEI Contr... | 16    | mei_me     | 3795F3DF87 |
| 8086:02e0 | 17aa:3806 | Intel      | Comet Lake Management Eng... | 15    | mei_me     | 5BDCB41FEE |
| 8086:34e0 | 17aa:383a | Intel      | Ice Lake-LP Management En... | 15    | mei_me     | 2E19A058F9 |
| 8086:9d3a | 103c:830f | Intel      | Sunrise Point-LP CSME HEC... | 14    | mei_me     | B6BC75336E |
| 8086:9d3a | 17aa:3824 | Intel      | Sunrise Point-LP CSME HEC... | 14    | mei_me     | 15C0F31B91 |
| 8086:9d3a | 103c:8486 | Intel      | Sunrise Point-LP CSME HEC... | 13    | mei_me     | B149A04EE8 |
| 8086:9d3a | 17aa:3811 | Intel      | Sunrise Point-LP CSME HEC... | 13    | mei_me     | 1E4A851AD2 |
| 8086:9d3a | 17aa:383d | Intel      | Sunrise Point-LP CSME HEC... | 13    | mei_me     | 2F1BC93921 |
| 8086:a0e0 | 1028:0a05 | Intel      | Tiger Lake-LP Management ... | 13    | mei_me     | 71B5E3C825 |
| 8086:a13a | 103c:83bb | Intel      | 100 Series/C230 Series Ch... | 13    | mei_me     | BA09E3B76F |
| 8086:9d3a | 103c:827d | Intel      | Sunrise Point-LP CSME HEC... | 12    | mei_me     | 51178C1953 |
| 8086:9d3a | 103c:827e | Intel      | Sunrise Point-LP CSME HEC... | 12    | mei_me     | B3CFF29C2E |
| 8086:9d3a | 17aa:2259 | Intel      | Sunrise Point-LP CSME HEC... | 12    | mei_me     | C96223F666 |
| 8086:a13a | 17aa:3809 | Intel      | 100 Series/C230 Series Ch... | 12    | mei_me     | A9626F1580 |
| 8086:9d3a | 1028:077a | Intel      | Sunrise Point-LP CSME HEC... | 11    | mei_me     | C0A9C9443B |
| 8086:9d3a | 17aa:224e | Intel      | Sunrise Point-LP CSME HEC... | 11    | mei_me     | B866426527 |
| 8086:9d3a | 103c:8488 | Intel      | Sunrise Point-LP CSME HEC... | 10    | mei_me     | 7B7C2317D8 |
| 8086:9d3a | 1043:1ab0 | Intel      | Sunrise Point-LP CSME HEC... | 10    | mei_me     | CE8E9AF30D |
| 8086:9d3a | 17aa:3805 | Intel      | Sunrise Point-LP CSME HEC... | 10    | mei_me     | B58AABDE5F |
| 8086:9d3a | 17aa:380d | Intel      | Sunrise Point-LP CSME HEC... | 10    | mei_me     | A4D6F3CCE4 |
| 8086:9d3a | 17aa:3860 | Intel      | Sunrise Point-LP CSME HEC... | 10    | mei_me     | 384114E0B4 |
| 8086:02e0 | 17aa:5078 | Intel      | Comet Lake Management Eng... | 9     | mei_me     | 7C78B71A99 |
| 8086:9d3a | 103c:80d1 | Intel      | Sunrise Point-LP CSME HEC... | 9     | mei_me     | 629D516666 |
| 8086:9d3a | 103c:81a1 | Intel      | Sunrise Point-LP CSME HEC... | 9     | mei_me     | B37CBA5DF4 |
| 8086:9de0 | 1028:0894 | Intel      | Cannon Point-LP MEI Contr... | 9     | mei_me     | B07A0CF706 |
| 8086:a0a8 | 17aa:381f | Intel      | Tiger Lake-LP Serial IO U... | 9     | intel_l... | 13AC1F05DD |
| 8086:a0e0 | 1028:09ff | Intel      | Tiger Lake-LP Management ... | 9     | mei_me     | AD3C1FB56A |
| 8086:a0e0 | 17aa:383b | Intel      | Tiger Lake-LP Management ... | 9     | mei_me     | 13AC1F05DD |
| 8086:a13a | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 9     | mei_me     | C28F77B8F1 |
| 8086:02e0 | 1028:095d | Intel      | Comet Lake Management Eng... | 8     | mei_me     | B5682ADC9E |
| 8086:9d3a | 103c:8438 | Intel      | Sunrise Point-LP CSME HEC... | 8     | mei_me     | 633CDE303A |
| 8086:02e0 | 1028:09cd | Intel      | Comet Lake Management Eng... | 7     | mei_me     | BC7C58F248 |
| 8086:02e0 | 103c:863f | Intel      | Comet Lake Management Eng... | 7     | mei_me     | 638C4207CE |
| 8086:02e0 | 103c:86b1 | Intel      | Comet Lake Management Eng... | 7     | mei_me     | 093BEED213 |
| 8086:02e0 | 103c:86b2 | Intel      | Comet Lake Management Eng... | 7     | mei_me     | 42A03DCD82 |
| 8086:34e0 | 103c:86f9 | Intel      | Ice Lake-LP Management En... | 7     | mei_me     | A18B247E3D |
| 8086:9d3a | 17aa:506d | Intel      | Sunrise Point-LP CSME HEC... | 7     | mei_me     | 847655CB40 |
| 8086:9de0 | 103c:85c4 | Intel      | Cannon Point-LP MEI Contr... | 7     | mei_me     | 9BCBAF17E9 |
| 8086:9de0 | 103c:861f | Intel      | Cannon Point-LP MEI Contr... | 7     | mei_me     | D284325FCF |
| 8086:02e0 | 103c:866e | Intel      | Comet Lake Management Eng... | 6     | mei_me     | 22FAA280E3 |
| 8086:34e0 | 1025:141f | Intel      | Ice Lake-LP Management En... | 6     | mei_me     | AA8934716B |
| 8086:9d3a | 1025:1176 | Intel      | Sunrise Point-LP CSME HEC... | 6     | mei_me     | 566FA6B1D5 |
| 8086:9d3a | 103c:8484 | Intel      | Sunrise Point-LP CSME HEC... | 6     | mei_me     | D46010346C |
| 8086:9d3a | 1043:1b00 | Intel      | Sunrise Point-LP CSME HEC... | 6     | mei_me     | BC2368FBE6 |
| 8086:9d3a | 1043:1c90 | Intel      | Sunrise Point-LP CSME HEC... | 6     | mei_me     | AED32F7A4D |
| 8086:9d3a | 17aa:2237 | Intel      | Sunrise Point-LP CSME HEC... | 6     | mei_me     | 2A0ECA4670 |
| 8086:9d3a | 17aa:3846 | Intel      | Sunrise Point-LP CSME HEC... | 6     | mei_me     | CF93488B90 |
| 8086:9d3a | 17aa:3861 | Intel      | Sunrise Point-LP CSME HEC... | 6     | mei_me     | 570666D7D6 |
| 8086:9de0 | 1028:089e | Intel      | Cannon Point-LP MEI Contr... | 6     | mei_me     | C6692154A1 |
| 8086:a0e0 | 1028:09dd | Intel      | Tiger Lake-LP Management ... | 6     | mei_me     | 6BFDD9FDA4 |
| 8086:02e0 | 1028:0950 | Intel      | Comet Lake Management Eng... | 5     | mei_me     | 9DD76AE820 |
| 8086:02e0 | 17aa:2292 | Intel      | Comet Lake Management Eng... | 5     | mei_me     | 32CA60DCEA |
| 8086:02e0 | 17aa:22be | Intel      | Comet Lake Management Eng... | 5     | mei_me     | E40B11DCA2 |
| 8086:02e0 | 17aa:3809 | Intel      | Comet Lake Management Eng... | 5     | mei_me     | D9D123FF85 |
| 8086:5a9a | 17aa:3803 | Intel      | Celeron N3350/Pentium N42... | 5     | mei_me     | 98851C034C |
| 8086:5a9c | 17aa:3803 | Intel      | Communication controller     | 5     |            | 98851C034C |
| 8086:5a9e | 17aa:3803 | Intel      | Communication controller     | 5     |            | 98851C034C |
| 8086:9d3a | 1028:07eb | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | E4FFC93C6A |
| 8086:9d3a | 103c:81a9 | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | 0BB3F77C75 |
| 8086:9d3a | 103c:81ad | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | CE728E8715 |
| 8086:9d3a | 103c:827f | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | BD5BDFD31F |
| 8086:9d3a | 103c:8313 | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | DCD840E8A2 |
| 8086:9d3a | 103c:8483 | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | C41A1DE997 |
| 8086:9d3a | 103c:8487 | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | CA8936A74C |
| 8086:9d3a | 1043:14f0 | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | 93B1606116 |
| 8086:9d3a | 1043:1dc0 | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | DF55EA30E7 |
| 8086:9d3a | 17aa:504c | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | 4983586FE5 |
| 8086:9d3a | 17aa:506c | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | 6C4ABD0606 |
| 8086:9da8 | 1043:1541 | Intel      | Cannon Point-LP Serial IO... | 5     | intel_l... | 8EFC8CAADA |
| 8086:9da8 | 1043:19d1 | Intel      | Cannon Point-LP Serial IO... | 5     | intel_lpss | 9054D4EBEB |
| 8086:9de0 | 1028:08b6 | Intel      | Cannon Point-LP MEI Contr... | 5     | mei_me     | B0722E1B57 |
| 8086:9de0 | 103c:85e7 | Intel      | Cannon Point-LP MEI Contr... | 5     | mei_me     | 169477DE3F |
| 8086:9de0 | 1043:1541 | Intel      | Cannon Point-LP MEI Contr... | 5     | mei_me     | 8EFC8CAADA |
| 8086:9de0 | 1043:19d1 | Intel      | Cannon Point-LP MEI Contr... | 5     | mei_me     | 9054D4EBEB |
| 8086:9de0 | 17aa:2294 | Intel      | Cannon Point-LP MEI Contr... | 5     | mei_me     | 09DC5430DA |
| 8086:9de0 | 17aa:5077 | Intel      | Cannon Point-LP MEI Contr... | 5     | mei_me     | 87DA71BBB9 |
| 8086:a0e0 | 103c:87f7 | Intel      | Tiger Lake-LP Management ... | 5     | mei_me     | 48A0452D0B |
| 8086:a0e0 | 17aa:382c | Intel      | Tiger Lake-LP Management ... | 5     | mei_me     | 0B7B90BB5D |
| 8086:a360 | 17aa:382c | Intel      | Cannon Lake PCH HECI Cont... | 5     | mei_me     | 78960B975F |
| 8086:02e0 | 1028:0951 | Intel      | Comet Lake Management Eng... | 4     | mei_me     | 247867F57E |
| 8086:319a |           | Intel      | Celeron/Pentium Silver Pr... | 4     | mei_me     | 65846CBF2B |
| 8086:34e0 | 103c:86fa | Intel      | Ice Lake-LP Management En... | 4     | mei_me     | 520E728AF7 |
| 8086:9cba | 103c:802d | Intel      | Wildcat Point-LP MEI Cont... | 4     | mei_me     | 24D17544A9 |
| 8086:9cba | 103c:806e | Intel      | Wildcat Point-LP MEI Cont... | 4     | mei_me     | A8AA7A1D17 |
| 8086:9d3a | 103c:81a7 | Intel      | Sunrise Point-LP CSME HEC... | 4     | mei_me     | BC77E670A5 |
| 8086:9d3a | 103c:82c1 | Intel      | Sunrise Point-LP CSME HEC... | 4     | mei_me     | CF06BA276E |
| 8086:9d3a | 103c:83c4 | Intel      | Sunrise Point-LP CSME HEC... | 4     | mei_me     | 3F62C672FB |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15df | 1022:15df | AMD        | Family 17h (Models 10h-1f... | 71    | ccp        | 64A9E43743 |
| 1022:15df | 103c:876f | AMD        | Family 17h (Models 10h-1f... | 27    | ccp        | 08B513769D |
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 27    | mei_txe    | 1866D29174 |
| 1022:15df | 103c:876e | AMD        | Family 17h (Models 10h-1f... | 26    | ccp        | F77E2EBB10 |
| 1022:15df | 103c:85dd | AMD        | Family 17h (Models 10h-1f... | 22    | ccp        | A93B2565DF |
| 1022:15df | 103c:85de | AMD        | Family 17h (Models 10h-1f... | 17    | ccp        | 9E86C8EDE5 |
| 1022:15df | 17aa:3804 | AMD        | Family 17h (Models 10h-1f... | 16    | ccp        | 57651669E3 |
| 1022:15df | 103c:83c6 | AMD        | Family 17h (Models 10h-1f... | 15    | ccp        | 168717D052 |
| 1022:15df | 103c:8496 | AMD        | Family 17h (Models 10h-1f... | 14    | ccp        | 8A63E2E055 |
| 1022:15df | 103c:8497 | AMD        | Family 17h (Models 10h-1f... | 13    | ccp        | 2910A4173E |
| 8086:2298 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 9     | mei_txe    | 8638532EEB |
| 8086:0f18 | 103c:802b | Intel      | Atom Processor Z36xxx/Z37... | 6     | mei_txe    | 4EDDB18ED9 |
| 1022:1578 | 103c:81aa | AMD        | Carrizo Platform Security... | 5     |            | 633D386331 |
| 1022:1578 | 17aa:3802 | AMD        | Carrizo Platform Security... | 4     |            | DC41704AEC |
| 1022:15df | 1028:09e3 | AMD        | Family 17h (Models 10h-1f... | 4     | ccp        | 9ED34E6D16 |
| 1022:15df | 1028:090c | AMD        | Family 17h (Models 10h-1f... | 3     | ccp        | B6C573F5AA |
| 1022:15df | 103c:87a9 | AMD        | Family 17h (Models 10h-1f... | 3     | ccp        | F8C5A69D8E |
| 1022:15df | 17aa:3824 | AMD        | Family 17h (Models 10h-1f... | 3     | ccp        | 84728690A1 |
| 1022:1578 | 103c:8311 | AMD        | Carrizo Platform Security... | 2     |            | 514D46C27F |
| 1022:15df | 1025:1506 | AMD        | Family 17h (Models 10h-1f... | 2     | ccp        | D000862005 |
| 8086:2298 | 103c:81a2 | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | 35DC79725B |
| 1022:1578 | 103c:81ab | AMD        | Carrizo Platform Security... | 1     |            | D98A9E0C48 |
| 1022:15df | 103c:8535 | AMD        | Family 17h (Models 10h-1f... | 1     | ccp        | 31CBD77D73 |
| 8086:2298 | 103c:8074 | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | 51A2F6EB71 |
| 8086:2298 | 17aa:3801 | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | F6650D66F7 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:1636 | 17aa:3f1a | AMD        | Renoir                       | 46    | amdgpu     | 64A9E43743 |
| 1002:1636 | 103c:876f | AMD        | Renoir                       | 27    | amdgpu     | 08B513769D |
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 27    | i915       | 1866D29174 |
| 1002:1636 | 103c:876e | AMD        | Renoir                       | 26    | amdgpu     | F77E2EBB10 |
| 8086:9b41 | 17aa:3f12 | Intel      | CometLake-U GT2 [UHD Grap... | 25    | i915       | F72E765EF0 |
| 8086:5917 | 103c:83b9 | Intel      | UHD Graphics 620             | 24    | i915       | 2C533BE257 |
| 8086:3ea0 | 103c:8514 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 23    | i915       | 2352CAA9CF |
| 1002:15d8 | 103c:85dd | AMD        | Picasso                      | 22    | amdgpu     | A93B2565DF |
| 8086:1916 | 17aa:2238 | Intel      | Skylake GT2 [HD Graphics ... | 19    | i915       | D878C63FE4 |
| 1002:15d8 | 103c:85de | AMD        | Picasso                      | 17    | amdgpu     | 9E86C8EDE5 |
| 8086:5917 | 17aa:3803 | Intel      | UHD Graphics 620             | 17    | i915       | 6E045B787A |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics 500              | 17    | i915       | 7332052765 |
| 1002:15dd | 17aa:39ff | AMD        | Raven Ridge [Radeon Vega ... | 16    | amdgpu     | 57651669E3 |
| 8086:3ea0 | 17aa:2292 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 16    | i915       | 3795F3DF87 |
| 8086:3ea0 | 17aa:39f4 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 16    | i915       | CD156B08D8 |
| 8086:8a52 | 1028:08b0 | Intel      | Iris Plus Graphics G7        | 16    | i915       | 6B27A727BE |
| 1002:15dd | 103c:83c6 | AMD        | Raven Ridge [Radeon Vega ... | 15    | amdgpu     | 168717D052 |
| 8086:8a52 | 17aa:3801 | Intel      | Iris Plus Graphics G7        | 15    | i915       | 2E19A058F9 |
| 1002:15dd | 103c:8496 | AMD        | Raven Ridge [Radeon Vega ... | 14    | amdgpu     | 8A63E2E055 |
| 8086:5916 | 103c:830f | Intel      | HD Graphics 620              | 14    | i915       | B6BC75336E |
| 8086:8a56 | 17aa:380d | Intel      | Iris Plus Graphics G1 (Ic... | 14    | i915       | 35876A09AD |
| 1002:15dd | 103c:8497 | AMD        | Raven Ridge [Radeon Vega ... | 13    | amdgpu     | 2910A4173E |
| 1002:694e | 103c:83bb | AMD        | Polaris 22 XL [Radeon RX ... | 13    | amdgpu     | BA09E3B76F |
| 8086:3185 | 8086:2212 | Intel      | GeminiLake [UHD Graphics ... | 13    | i915       | 38E5F73567 |
| 8086:5916 | 103c:827d | Intel      | HD Graphics 620              | 13    | i915       | 51178C1953 |
| 8086:5916 | 17aa:3987 | Intel      | HD Graphics 620              | 13    | i915       | 44E586277C |
| 8086:5917 | 103c:8486 | Intel      | UHD Graphics 620             | 13    | i915       | B149A04EE8 |
| 8086:591b | 103c:83bb | Intel      | HD Graphics 630              | 13    | i915       | BA09E3B76F |
| 8086:9b41 | 17aa:3806 | Intel      | CometLake-U GT2 [UHD Grap... | 13    | i915       | 5BDCB41FEE |
| 8086:5916 | 103c:827e | Intel      | HD Graphics 620              | 12    | i915       | B3CFF29C2E |
| 8086:5917 | 17aa:2259 | Intel      | UHD Graphics 620             | 12    | i915       | C96223F666 |
| 8086:5917 | 17aa:398e | Intel      | UHD Graphics 620             | 12    | i915       | 86A25931BD |
| 8086:9a49 | 1028:0a05 | Intel      | TigerLake-LP GT2 [Iris Xe... | 12    | i915       | 71B5E3C825 |
| 1002:1636 | 103c:8735 | AMD        | Renoir                       | 11    | amdgpu     | F36EA99568 |
| 10de:1c8d | 17aa:39cb | Nvidia     | GP107M [GeForce GTX 1050 ... | 11    | nvidia     | A9626F1580 |
| 8086:5916 | 17aa:224e | Intel      | HD Graphics 620              | 11    | i915       | B866426527 |
| 8086:591b | 17aa:39cb | Intel      | HD Graphics 630              | 11    | i915       | A9626F1580 |
| 8086:5916 | 17aa:3801 | Intel      | HD Graphics 620              | 10    | i915       | B58AABDE5F |
| 8086:5917 | 103c:8488 | Intel      | UHD Graphics 620             | 10    | i915       | 7B7C2317D8 |
| 8086:5917 | 17aa:39ce | Intel      | UHD Graphics 620             | 10    | i915       | 480F534F9F |
| 1002:694e | 1028:080d | ATI Tec... | Polaris 22 XL [Radeon RX ... | 9     | amdgpu     | C28F77B8F1 |
| 8086:1916 | 103c:80d1 | Intel      | Skylake GT2 [HD Graphics ... | 9     | i915       | 629D516666 |
| 8086:22b1 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 9     | i915       | 8638532EEB |
| 8086:3ea0 | 1028:0894 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 9     | i915       | B07A0CF706 |
| 8086:5916 | 17aa:39f3 | Intel      | HD Graphics 620              | 9     | i915       | 15C0F31B91 |
| 8086:5917 | 1043:1ab0 | Intel      | UHD Graphics 620             | 9     | i915       | CE8E9AF30D |
| 8086:591b | 1028:080d | Intel      | HD Graphics 630              | 9     | i915       | C28F77B8F1 |
| 8086:9a49 | 1028:09ff | Intel      | TigerLake-LP GT2 [Iris Xe... | 9     | i915       | AD3C1FB56A |
| 8086:9a49 | 17aa:3f1a | Intel      | TigerLake-LP GT2 [Iris Xe... | 9     | i915       | 13AC1F05DD |
| 8086:9b41 | 17aa:5078 | Intel      | CometLake-U GT2 [UHD Grap... | 9     | i915       | 7C78B71A99 |
| 10de:174d | 17aa:39ce | Nvidia     | GM108M [GeForce MX130]       | 8     | nvidia     | 480F534F9F |
| 8086:5917 | 103c:8438 | Intel      | UHD Graphics 620             | 8     | i915       | 633CDE303A |
| 8086:591e | 1028:077a | Intel      | HD Graphics 615              | 8     | i915       | C0A9C9443B |
| 8086:9b41 | 1028:095d | Intel      | CometLake-U GT2 [UHD Grap... | 8     | i915       | B5682ADC9E |
| 1002:15d8 | 1043:1921 | AMD        | Picasso                      | 7     | amdgpu     | 87C26A2591 |
| 10de:1d13 | 103c:863f | Nvidia     | GP108M [GeForce MX250]       | 7     | nvidia     | 638C4207CE |
| 10de:1d13 | 103c:86b2 | Nvidia     | GP108M [GeForce MX250]       | 7     | nvidia     | 42A03DCD82 |
| 8086:1916 | 103c:81a1 | Intel      | Skylake GT2 [HD Graphics ... | 7     | i915       | B37CBA5DF4 |
| 8086:3ea0 | 103c:85c4 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 7     | i915       | 9BCBAF17E9 |
| 8086:3ea0 | 103c:861f | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 7     | i915       | D284325FCF |
| 8086:5917 | 17aa:39fd | Intel      | UHD Graphics 620             | 7     | i915       | 2F1BC93921 |
| 8086:5917 | 17aa:506d | Intel      | UHD Graphics 620             | 7     | i915       | 847655CB40 |
| 8086:8a52 | 103c:86f9 | Intel      | Iris Plus Graphics G7        | 7     | i915       | A18B247E3D |
| 8086:8a52 | 17aa:380d | Intel      | Iris Plus Graphics G7        | 7     | i915       | 7C965E245C |
| 8086:9b41 | 1028:09cd | Intel      | CometLake-U GT2 [UHD Grap... | 7     | i915       | BC7C58F248 |
| 8086:9b41 | 103c:863f | Intel      | CometLake-U GT2 [UHD Grap... | 7     | i915       | 638C4207CE |
| 8086:9b41 | 103c:86b1 | Intel      | CometLake-U GT2 [UHD Grap... | 7     | i915       | 093BEED213 |
| 8086:9b41 | 103c:86b2 | Intel      | CometLake-U GT2 [UHD Grap... | 7     | i915       | 42A03DCD82 |
| 10de:174d | 17aa:398c | Nvidia     | GM108M [GeForce MX130]       | 6     | nouveau    | EAA1882521 |
| 10de:1d10 | 103c:8484 | Nvidia     | GP108M [GeForce MX150]       | 6     | nvidia     | D46010346C |
| 10de:1d16 | 17aa:3801 | Nvidia     | GP108M [GeForce MX330]       | 6     | nvidia     | 7C965E245C |
| 8086:0f31 | 103c:802b | Intel      | Atom Processor Z36xxx/Z37... | 6     | i915       | 4EDDB18ED9 |
| 8086:1916 | 17aa:2237 | Intel      | Skylake GT2 [HD Graphics ... | 6     | i915       | 2A0ECA4670 |
| 8086:3ea0 | 1028:089e | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 6     | i915       | C6692154A1 |
| 8086:5916 | 1025:1176 | Intel      | HD Graphics 620              | 6     | i915       | 566FA6B1D5 |
| 8086:5916 | 17aa:3988 | Intel      | HD Graphics 620              | 6     | i915       | EA182AB251 |
| 8086:5917 | 103c:8484 | Intel      | UHD Graphics 620             | 6     | i915       | D46010346C |
| 8086:5917 | 1043:1c90 | Intel      | UHD Graphics 620             | 6     | i915       | AED32F7A4D |
| 8086:5917 | 17aa:3802 | Intel      | UHD Graphics 620             | 6     | i915       | CF93488B90 |
| 8086:5917 | 17aa:398c | Intel      | UHD Graphics 620             | 6     | i915       | EAA1882521 |
| 8086:5917 | 17aa:39ef | Intel      | UHD Graphics 620             | 6     | i915       | 570666D7D6 |
| 8086:591e | 1ae0:2212 | Intel      | HD Graphics 615              | 6     | i915       | CBC1BB3811 |
| 8086:9a49 | 1028:09dd | Intel      | TigerLake-LP GT2 [Iris Xe... | 6     | i915       | 6BFDD9FDA4 |
| 8086:9b41 | 103c:866e | Intel      | CometLake-U GT2 [UHD Grap... | 6     | i915       | 22FAA280E3 |
| 1002:9874 | 103c:81aa | AMD        | Wani [Radeon R5/R6/R7 Gra... | 5     | amdgpu     | 633D386331 |
| 10de:134d | 17aa:39ce | Nvidia     | GM108M [GeForce 940MX]       | 5     | nvidia     | C93EE714CF |
| 10de:134d | 17aa:39f4 | Nvidia     | GM108M [GeForce 940MX]       | 5     | nvidia     | DAF737A5BA |
| 10de:174d | 103c:8487 | Nvidia     | GM108M [GeForce MX130]       | 5     | nouveau    | CA8936A74C |
| 10de:1d10 | 103c:827f | Nvidia     | GP108M [GeForce MX150]       | 5     | nouveau    | BD5BDFD31F |
| 10de:1d13 | 103c:85e7 | Nvidia     | GP108M [GeForce MX250]       | 5     | nouveau    | 169477DE3F |
| 10de:1f91 | 17aa:3f1a | Nvidia     | TU117M [GeForce GTX 1650 ... | 5     | nvidia     | 78960B975F |
| 8086:1906 | 17aa:381d | Intel      | HD Graphics 510              | 5     | i915       | F49067FAAB |
| 8086:1916 | 17aa:381e | Intel      | Skylake GT2 [HD Graphics ... | 5     | i915       | 1E4A851AD2 |
| 8086:3e9b | 17aa:3f1a | Intel      | CoffeeLake-H GT2 [UHD Gra... | 5     | i915       | 78960B975F |
| 8086:3ea0 | 1028:08b6 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 5     | i915       | B0722E1B57 |
| 8086:3ea0 | 103c:85e7 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 5     | i915       | 169477DE3F |
| 8086:3ea0 | 17aa:2294 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 5     | i915       | 09DC5430DA |
| 8086:3ea0 | 17aa:5077 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 5     | i915       | 87DA71BBB9 |
| 8086:5906 | 17aa:39da | Intel      | Kaby Lake-U GT1 Integrate... | 5     | i915       | CD9AB2FD5E |
| 8086:5916 | 103c:81a9 | Intel      | HD Graphics 620              | 5     | i915       | 0BB3F77C75 |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1631 | 1022:1631 | AMD        | Renoir IOMMU                 | 63    |            | 64A9E43743 |
| 1022:1631 | 103c:876f | AMD        | Renoir IOMMU                 | 27    |            | 08B513769D |
| 1022:1631 | 103c:876e | AMD        | Renoir IOMMU                 | 26    |            | F77E2EBB10 |
| 1022:15d1 | 103c:85dd | AMD        | Raven/Raven2 IOMMU           | 22    |            | A93B2565DF |
| 1022:15d1 | 103c:85de | AMD        | Raven/Raven2 IOMMU           | 17    |            | 9E86C8EDE5 |
| 1022:15d1 | 17aa:3809 | AMD        | Raven/Raven2 IOMMU           | 16    |            | 57651669E3 |
| 1022:15d1 | 103c:83c6 | AMD        | Raven/Raven2 IOMMU           | 15    |            | 168717D052 |
| 1022:15d1 | 103c:8496 | AMD        | Raven/Raven2 IOMMU           | 14    |            | 8A63E2E055 |
| 1022:15d1 | 103c:8497 | AMD        | Raven/Raven2 IOMMU           | 13    |            | 2910A4173E |
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 11    |            | 824BB881D7 |
| 1022:1577 | 103c:81aa | AMD        | Family 15h (Models 60h-6f... | 5     |            | 633D386331 |
| 1022:1577 | 17aa:3806 | AMD        | Family 15h (Models 60h-6f... | 4     |            | DC41704AEC |
| 1022:1631 | 1028:09e3 | AMD        | Renoir IOMMU                 | 4     |            | 9ED34E6D16 |
| 1022:1631 | 103c:87a9 | AMD        | Renoir IOMMU                 | 3     |            | F8C5A69D8E |
| 1022:1631 | 17aa:3807 | AMD        | Renoir IOMMU                 | 3     |            | 84728690A1 |
| 1022:1577 | 103c:8311 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 514D46C27F |
| 1022:15d1 | 1025:1506 | AMD        | Raven/Raven2 IOMMU           | 2     |            | D000862005 |
| 1022:1577 | 103c:81ab | AMD        | Family 15h (Models 60h-6f... | 1     |            | D98A9E0C48 |
| 1022:15d1 | 103c:8535 | AMD        | Raven/Raven2 IOMMU           | 1     |            | 31CBD77D73 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d21 | 17aa:383d | Intel      | Sunrise Point-LP PMC         | 36    |            | 44E586277C |
| 8086:02ef | 17aa:3805 | Intel      | Comet Lake PCH-LP Shared ... | 28    |            | F72E765EF0 |
| 8086:9def |           | Intel      | Cannon Point-LP Shared SRAM  | 27    |            | 09DC5430DA |
| 8086:9def | 8086:9def | Intel      | Cannon Point-LP Shared SRAM  | 27    |            | CD156B08D8 |
| 8086:9d21 | 103c:83b9 | Intel      | Sunrise Point-LP PMC         | 24    |            | 2C533BE257 |
| 8086:9def | 103c:8514 | Intel      | Cannon Point-LP Shared SRAM  | 23    |            | 2352CAA9CF |
| 8086:34ef | 17aa:3803 | Intel      | Ice Lake-LP DRAM Controller  | 21    |            | 7C965E245C |
| 8086:34ef |           | Intel      | Ice Lake-LP DRAM Controller  | 19    |            | 6B27A727BE |
| 8086:9d21 | 17aa:2238 | Intel      | Sunrise Point-LP PMC         | 19    |            | D878C63FE4 |
| 8086:9d21 | 17aa:3866 | Intel      | Sunrise Point-LP PMC         | 19    |            | 1A0B1FFDBD |
| 8086:9d21 | 17aa:386c | Intel      | Sunrise Point-LP PMC         | 17    |            | 6E045B787A |
| 8086:34ef | 17aa:3846 | Intel      | Ice Lake-LP DRAM Controller  | 15    |            | 2E19A058F9 |
| 8086:9d21 | 103c:830f | Intel      | Sunrise Point-LP PMC         | 14    |            | B6BC75336E |
| 8086:9d21 | 17aa:3823 | Intel      | Sunrise Point-LP PMC         | 14    |            | 15C0F31B91 |
| 8086:02ef | 17aa:3806 | Intel      | Comet Lake PCH-LP Shared ... | 13    |            | 5BDCB41FEE |
| 8086:9d21 | 103c:827d | Intel      | Sunrise Point-LP PMC         | 13    |            | 51178C1953 |
| 8086:9d21 | 103c:8486 | Intel      | Sunrise Point-LP PMC         | 13    |            | B149A04EE8 |
| 8086:9d21 | 17aa:3811 | Intel      | Sunrise Point-LP PMC         | 13    |            | 1E4A851AD2 |
| 8086:9d21 | 17aa:383f | Intel      | Sunrise Point-LP PMC         | 13    |            | 2F1BC93921 |
| 8086:9def | 8086:7270 | Intel      | Cannon Point-LP Shared SRAM  | 13    |            | 30B72B97CB |
| 8086:a0ef | 1028:0a05 | Intel      | Tiger Lake-LP Shared SRAM    | 13    |            | 71B5E3C825 |
| 8086:a121 | 103c:83bb | Intel      | 100 Series/C230 Series Ch... | 13    |            | BA09E3B76F |
| 8086:9d21 | 103c:827e | Intel      | Sunrise Point-LP PMC         | 12    |            | B3CFF29C2E |
| 8086:9d21 | 17aa:2259 | Intel      | Sunrise Point-LP PMC         | 12    |            | C96223F666 |
| 8086:a121 | 17aa:380f | Intel      | 100 Series/C230 Series Ch... | 12    |            | A9626F1580 |
| 8086:9d21 | 1028:077a | Intel      | Sunrise Point-LP PMC         | 11    |            | C0A9C9443B |
| 8086:9d21 | 17aa:224e | Intel      | Sunrise Point-LP PMC         | 11    | intel_p... | B866426527 |
| 8086:9d21 | 103c:8488 | Intel      | Sunrise Point-LP PMC         | 10    |            | 7B7C2317D8 |
| 8086:9d21 | 1043:1ab0 | Intel      | Sunrise Point-LP PMC         | 10    |            | CE8E9AF30D |
| 8086:9d21 | 17aa:3805 | Intel      | Sunrise Point-LP PMC         | 10    |            | B58AABDE5F |
| 8086:9d21 | 17aa:380b | Intel      | Sunrise Point-LP PMC         | 10    |            | A4D6F3CCE4 |
| 8086:9d21 | 17aa:3863 | Intel      | Sunrise Point-LP PMC         | 10    |            | 384114E0B4 |
| 8086:02ef | 17aa:5078 | Intel      | Comet Lake PCH-LP Shared ... | 9     |            | 7C78B71A99 |
| 8086:9d21 | 103c:80d1 | Intel      | Sunrise Point-LP PMC         | 9     |            | 629D516666 |
| 8086:9d21 | 103c:81a1 | Intel      | Sunrise Point-LP PMC         | 9     |            | B37CBA5DF4 |
| 8086:9def | 1028:0894 | Intel      | Cannon Point-LP Shared SRAM  | 9     |            | B07A0CF706 |
| 8086:a0ef | 1028:09ff | Intel      | Tiger Lake-LP Shared SRAM    | 9     |            | AD3C1FB56A |
| 8086:a0ef | 17aa:3847 | Intel      | Tiger Lake-LP Shared SRAM    | 9     |            | 13AC1F05DD |
| 8086:a121 | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 9     |            | C28F77B8F1 |
| 8086:02ef | 1028:095d | Intel      | Comet Lake PCH-LP Shared ... | 8     |            | B5682ADC9E |
| 8086:9d21 | 103c:8438 | Intel      | Sunrise Point-LP PMC         | 8     |            | 633CDE303A |
| 8086:02ef | 1028:09cd | Intel      | Comet Lake PCH-LP Shared ... | 7     |            | BC7C58F248 |
| 8086:02ef | 103c:863f | Intel      | Comet Lake PCH-LP Shared ... | 7     |            | 638C4207CE |
| 8086:02ef | 103c:86b1 | Intel      | Comet Lake PCH-LP Shared ... | 7     |            | 093BEED213 |
| 8086:02ef | 103c:86b2 | Intel      | Comet Lake PCH-LP Shared ... | 7     |            | 42A03DCD82 |
| 8086:34ef | 103c:86f9 | Intel      | Ice Lake-LP DRAM Controller  | 7     |            | A18B247E3D |
| 8086:9d21 | 17aa:506d | Intel      | Sunrise Point-LP PMC         | 7     |            | 847655CB40 |
| 8086:9def | 103c:85c4 | Intel      | Cannon Point-LP Shared SRAM  | 7     |            | 9BCBAF17E9 |
| 8086:9def | 103c:861f | Intel      | Cannon Point-LP Shared SRAM  | 7     |            | D284325FCF |
| 8086:02ef | 103c:866e | Intel      | Comet Lake PCH-LP Shared ... | 6     |            | 22FAA280E3 |
| 8086:34ef | 1025:141f | Intel      | Ice Lake-LP DRAM Controller  | 6     |            | AA8934716B |
| 8086:9d21 | 1025:1176 | Intel      | Sunrise Point-LP PMC         | 6     |            | 566FA6B1D5 |
| 8086:9d21 | 103c:8484 | Intel      | Sunrise Point-LP PMC         | 6     |            | D46010346C |
| 8086:9d21 | 1043:1b00 | Intel      | Sunrise Point-LP PMC         | 6     |            | BC2368FBE6 |
| 8086:9d21 | 1043:1c90 | Intel      | Sunrise Point-LP PMC         | 6     |            | AED32F7A4D |
| 8086:9d21 | 17aa:2237 | Intel      | Sunrise Point-LP PMC         | 6     |            | 2A0ECA4670 |
| 8086:9d21 | 17aa:3849 | Intel      | Sunrise Point-LP PMC         | 6     |            | CF93488B90 |
| 8086:9d21 | 17aa:3864 | Intel      | Sunrise Point-LP PMC         | 6     |            | 570666D7D6 |
| 8086:9d21 | 1ae0:006b | Intel      | Sunrise Point-LP PMC         | 6     |            | CBC1BB3811 |
| 8086:9def | 1028:089e | Intel      | Cannon Point-LP Shared SRAM  | 6     |            | C6692154A1 |
| 8086:a0ef | 1028:09dd | Intel      | Tiger Lake-LP Shared SRAM    | 6     |            | 6BFDD9FDA4 |
| 8086:02ef | 1028:0950 | Intel      | Comet Lake PCH-LP Shared ... | 5     |            | 9DD76AE820 |
| 8086:02ef | 17aa:2292 | Intel      | Comet Lake PCH-LP Shared ... | 5     |            | 32CA60DCEA |
| 8086:02ef | 17aa:22be | Intel      | Comet Lake PCH-LP Shared ... | 5     |            | E40B11DCA2 |
| 8086:02ef | 17aa:3803 | Intel      | Comet Lake PCH-LP Shared ... | 5     |            | D9D123FF85 |
| 8086:9d21 | 1028:07eb | Intel      | Sunrise Point-LP PMC         | 5     |            | E4FFC93C6A |
| 8086:9d21 | 103c:81a9 | Intel      | Sunrise Point-LP PMC         | 5     |            | 0BB3F77C75 |
| 8086:9d21 | 103c:81ad | Intel      | Sunrise Point-LP PMC         | 5     |            | CE728E8715 |
| 8086:9d21 | 103c:827f | Intel      | Sunrise Point-LP PMC         | 5     | intel_p... | BD5BDFD31F |
| 8086:9d21 | 103c:8313 | Intel      | Sunrise Point-LP PMC         | 5     |            | DCD840E8A2 |
| 8086:9d21 | 103c:8483 | Intel      | Sunrise Point-LP PMC         | 5     |            | C41A1DE997 |
| 8086:9d21 | 103c:8487 | Intel      | Sunrise Point-LP PMC         | 5     |            | CA8936A74C |
| 8086:9d21 | 1043:14f0 | Intel      | Sunrise Point-LP PMC         | 5     |            | 93B1606116 |
| 8086:9d21 | 1043:1dc0 | Intel      | Sunrise Point-LP PMC         | 5     |            | DF55EA30E7 |
| 8086:9d21 | 17aa:504c | Intel      | Sunrise Point-LP PMC         | 5     |            | 4983586FE5 |
| 8086:9d21 | 17aa:506c | Intel      | Sunrise Point-LP PMC         | 5     |            | 6C4ABD0606 |
| 8086:9def | 1028:08b6 | Intel      | Cannon Point-LP Shared SRAM  | 5     |            | B0722E1B57 |
| 8086:9def | 103c:85e7 | Intel      | Cannon Point-LP Shared SRAM  | 5     |            | 169477DE3F |
| 8086:9def | 1043:19d1 | Intel      | Cannon Point-LP Shared SRAM  | 5     |            | 9054D4EBEB |
| 8086:9def | 17aa:5077 | Intel      | Cannon Point-LP Shared SRAM  | 5     |            | 87DA71BBB9 |
| 8086:a0ef | 103c:87f7 | Intel      | Tiger Lake-LP Shared SRAM    | 5     |            | 48A0452D0B |
| 8086:a0ef | 17aa:3838 | Intel      | Tiger Lake-LP Shared SRAM    | 5     |            | 0B7B90BB5D |
| 8086:a36f | 17aa:3835 | Intel      | Cannon Lake PCH Shared SRAM  | 5     |            | 78960B975F |
| 8086:02ef | 1028:0951 | Intel      | Comet Lake PCH-LP Shared ... | 4     |            | 247867F57E |
| 8086:34ef | 103c:86fa | Intel      | Ice Lake-LP DRAM Controller  | 4     |            | 520E728AF7 |
| 8086:9d21 | 103c:81a7 | Intel      | Sunrise Point-LP PMC         | 4     |            | BC77E670A5 |
| 8086:9d21 | 103c:82c1 | Intel      | Sunrise Point-LP PMC         | 4     |            | CF06BA276E |
| 8086:9d21 | 103c:83c4 | Intel      | Sunrise Point-LP PMC         | 4     |            | 3F62C672FB |
| 8086:9d21 | 103c:84d8 | Intel      | Sunrise Point-LP PMC         | 4     |            | 03FE12C3CC |
| 8086:9d21 | 17aa:5061 | Intel      | Sunrise Point-LP PMC         | 4     |            | 9FCFE8BF6A |
| 8086:9def | 1028:08e2 | Intel      | Cannon Point-LP Shared SRAM  | 4     |            | 31C59F8FC7 |
| 8086:9def | 103c:850c | Intel      | Cannon Point-LP Shared SRAM  | 4     |            | EEC05D1BF9 |
| 8086:9def | 103c:850e | Intel      | Cannon Point-LP Shared SRAM  | 4     |            | 0C2D648815 |
| 8086:9def | 103c:8518 | Intel      | Cannon Point-LP Shared SRAM  | 4     |            | 64C5568456 |
| 8086:9def | 103c:8548 | Intel      | Cannon Point-LP Shared SRAM  | 4     |            | D862548439 |
| 8086:9def | 103c:857f | Intel      | Cannon Point-LP Shared SRAM  | 4     |            | DD643D4C19 |
| 8086:9def | 103c:85c8 | Intel      | Cannon Point-LP Shared SRAM  | 4     |            | 1649B0B654 |
| 8086:9def | 103c:85cd | Intel      | Cannon Point-LP Shared SRAM  | 4     |            | E7DCDD4B39 |
| 8086:a0ef |           | Intel      | Tiger Lake-LP Shared SRAM    | 4     |            | A0A4DFE970 |
| 8086:a0ef | 1028:09de | Intel      | Tiger Lake-LP Shared SRAM    | 4     |            | 5BF274A8E3 |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15e2 | 17aa:381b | AMD        | Raven/Raven2/FireFlight/R... | 46    | snd_pci... | 64A9E43743 |
| 1022:15e2 | 103c:876f | AMD        | Raven/Raven2/FireFlight/R... | 27    | snd_pci... | 08B513769D |
| 8086:22b8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 27    | intel_a... | 1866D29174 |
| 1022:15e2 | 103c:876e | AMD        | Raven/Raven2/FireFlight/R... | 26    | snd_pci... | F77E2EBB10 |
| 1022:15e2 | 103c:85dd | AMD        | Raven/Raven2/FireFlight/R... | 22    | snd_pci... | A93B2565DF |
| 1022:15e2 | 103c:85de | AMD        | Raven/Raven2/FireFlight/R... | 17    | snd_pci... | 9E86C8EDE5 |
| 8086:8a19 | 1028:08b0 | Intel      | Image Signal Processor       | 17    |            | 6B27A727BE |
| 1022:15e2 | 103c:8735 | AMD        | Raven/Raven2/FireFlight/R... | 11    | snd_pci... | F36EA99568 |
| 1022:15e2 | 17aa:380b | AMD        | Raven/Raven2/FireFlight/R... | 7     | snd_pci... | 8B75181A08 |
| 1022:15e2 | 103c:8496 | AMD        | Raven/Raven2/FireFlight/R... | 6     | snd_pci... | 8A63E2E055 |
| 8086:5a88 |           | Intel      | Celeron N3350/Pentium N42... | 5     |            | 378291C3E0 |
| 1022:15e2 | 1028:09e3 | AMD        | Raven/Raven2/FireFlight/R... | 4     | snd_pci... | 9ED34E6D16 |
| 8086:9d32 |           | Intel      | CSI-2 Host Controller        | 4     | ipu3_cio2  | 6F018F175E |
| 1022:15e2 | 103c:87a9 | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_rn_... | F8C5A69D8E |
| 1022:15e2 | 1043:11f2 | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | 974B8F73D1 |
| 1022:15e2 | 17aa:380e | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | 84728690A1 |
| 1022:15e2 | 17aa:3828 | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | 63C11CE610 |
| 1022:15e2 | 1025:1506 | AMD        | Raven/Raven2/FireFlight/R... | 2     | snd_pci... | D000862005 |
| 8086:1919 | 103c:8486 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | ipu3_imgu  | 4796134BF9 |
| 8086:1919 | 8086:1919 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | ipu3_imgu  | 6F018F175E |
| 1022:15e2 | 103c:8497 | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | C5914E5F87 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8168 | 17aa:3850 | Realtek... | RTL8111/8168/8411 PCI Exp... | 13    | r8169      | 1E4A851AD2 |
| 8086:156f | 17aa:2233 | Intel      | Ethernet Connection I219-LM  | 11    | e1000e     | D878C63FE4 |
| 8086:1570 | 17aa:2233 | Intel      | Ethernet Connection I219-V   | 11    | e1000e     | 2A0ECA4670 |
| 10ec:8168 | 17aa:3848 | Realtek... | RTL8111/8168/8411 PCI Exp... | 10    | r8169      | A4D6F3CCE4 |
| 8086:15be | 17aa:2292 | Intel      | Ethernet Connection (6) I... | 10    | e1000e     | 1D4E30D33E |
| 10ec:8136 | 103c:80d1 | Realtek... | RTL810xE PCI Express Fast... | 9     | r8169      | 629D516666 |
| 8086:0d4f | 17aa:5078 | Intel      | Ethernet Connection (10) ... | 9     | e1000e     | 7C78B71A99 |
| 8086:15d7 | 17aa:2259 | Intel      | Ethernet Connection (4) I... | 8     | e1000e     | C96223F666 |
| 8086:15d7 | 17aa:224e | Intel      | Ethernet Connection (4) I... | 7     | e1000e     | B866426527 |
| 10ec:8136 | 103c:802b | Realtek... | RTL810xE PCI Express Fast... | 6     | r8169      | 4EDDB18ED9 |
| 8086:15bd | 17aa:2292 | Intel      | Ethernet Connection (6) I... | 6     | e1000e     | 3795F3DF87 |
| 10ec:8168 | 17aa:383f | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8169      | 98851C034C |
| 8086:0d4f | 17aa:2292 | Intel      | Ethernet Connection (10) ... | 5     | e1000e     | 32CA60DCEA |
| 8086:0d4f | 17aa:22be | Intel      | Ethernet Connection (10) ... | 5     | e1000e     | E40B11DCA2 |
| 8086:15be | 17aa:5077 | Intel      | Ethernet Connection (6) I... | 5     | e1000e     | 87DA71BBB9 |
| 8086:15d7 | 17aa:506d | Intel      | Ethernet Connection (4) I... | 5     | e1000e     | 6B1A65C794 |
| 8086:15d8 | 17aa:506c | Intel      | Ethernet Connection (4) I... | 5     | e1000e     | 6C4ABD0606 |
| 10ec:8136 | 103c:806e | Realtek... | RTL810xE PCI Express Fast... | 4     | r8169      | A8AA7A1D17 |
| 10ec:8168 | 103c:84d8 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 03FE12C3CC |
| 10ec:8168 | 17aa:3868 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | DC41704AEC |
| 8086:15be | 17aa:2294 | Intel      | Ethernet Connection (6) I... | 4     | e1000e     | 09DC5430DA |
| 8086:15d7 | 17aa:224f | Intel      | Ethernet Connection (4) I... | 4     | e1000e     | 9FCFE8BF6A |
| 8086:15d8 | 17aa:224e | Intel      | Ethernet Connection (4) I... | 4     | e1000e     | A5DFF2C638 |
| 8086:156f | 17aa:504c | Intel      | Ethernet Connection I219-LM  | 3     | e1000e     | 4983586FE5 |
| 8086:15d8 | 17aa:2259 | Intel      | Ethernet Connection (4) I... | 3     | e1000e     | 84651F4EA3 |
| 10ec:8168 | 1025:1198 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | ACA273FE62 |
| 10ec:8168 | 103c:8143 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 03065735FF |
| 10ec:8168 | 103c:8251 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | A758FDF9AF |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 6B3E692B8E |
| 8086:1570 | 17aa:504c | Intel      | Ethernet Connection I219-V   | 2     | e1000e     | 8451A446B5 |
| 8086:15d8 | 17aa:506d | Intel      | Ethernet Connection (4) I... | 2     | e1000e     | 847655CB40 |
| 10ec:8136 | 103c:8074 | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | 51A2F6EB71 |
| 10ec:8168 | 1025:129f | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 0F6F9B0A03 |
| 10ec:8168 | 103c:806c | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 462F2D5347 |
| 10ec:8168 | 103c:80cf | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 15B7980DAF |
| 10ec:8168 | 103c:80d0 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 97ED13A8C0 |
| 10ec:8168 | 103c:8252 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | E610D18176 |
| 10ec:8168 | 103c:86cf | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 33D5688BFC |
| 10ec:8168 | 144d:c14c | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 6E023867E9 |
| 10ec:8168 | 17aa:5058 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | C65BB14578 |
| 10ec:8168 | 17aa:506e | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 65846CBF2B |
| 14e4:1682 | 14e4:1682 | Broadcom   | NetXtreme BCM57762 Gigabi... | 1     | tg3        | 1C675DD7D7 |
| 8086:0d4e | 17aa:22ad | Intel      | Ethernet Connection (10) ... | 1     | e1000e     | BFE30DECD3 |
| 8086:0d4f | 17aa:22ad | Intel      | Ethernet Connection (10) ... | 1     | e1000e     | 8E3E2A94C3 |
| 8086:1533 | 1799:0098 | Intel      | I210 Gigabit Network Conn... | 1     | igb        | AC3DC845F8 |
| 8086:1533 | 1c7a:0019 | Intel      | I210 Gigabit Network Conn... | 1     | igb        | C28F77B8F1 |
| 8086:15bd | 17aa:2294 | Intel      | Ethernet Connection (6) I... | 1     | e1000e     | 38035357A1 |
| 8086:15bd | 1e26:001a | Intel      | Ethernet Connection (6) I... | 1     | e1000e     | 437C9D66AA |
| 8086:15fc | 17aa:5089 | Intel      | Ethernet Connection (13) ... | 1     | e1000e     | 19835B06AE |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:b822 | 103c:831b | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 101   | rtwpci     | 168717D052 |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 81    | iwlwifi    | 8BF489A0CB |
| 8086:9df0 | 8086:0034 | Intel      | Cannon Point-LP CNVi [Wir... | 63    | iwlwifi    | 9054D4EBEB |
| 8086:24fd | 8086:9010 | Intel      | Wireless 8265 / 8275         | 62    | iwlwifi    | 824BB881D7 |
| 8086:2723 | 8086:0084 | Intel      | Wi-Fi 6 AX200                | 55    | iwlwifi    | 84728690A1 |
| 168c:003e | 17aa:0827 | Qualcom... | QCA6174 802.11ac Wireless... | 53    | ath10k_pci | 15C0F31B91 |
| 8086:34f0 | 8086:0074 | Intel      | Ice Lake-LP PCH CNVi WiFi    | 53    | iwlwifi    | 520E728AF7 |
| 8086:02f0 | 8086:0074 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 47    | iwlwifi    | FD2D87232F |
| 10ec:c822 | 103c:85f7 | Realtek... | RTL8822CE 802.11ac PCIe W... | 42    | rtw88_8... | F77E2EBB10 |
| 10ec:c822 | 17aa:c123 | Realtek... | RTL8822CE 802.11ac PCIe W... | 42    | rtw88_8... | 64A9E43743 |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 41    | iwlwifi    | CE8E9AF30D |
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 41    | iwlwifi    | B3CFF29C2E |
| 168c:0042 | 17aa:0901 | Qualcom... | QCA9377 802.11ac Wireless... | 37    | ath10k_pci | 1A0B1FFDBD |
| 8086:a0f0 | 8086:0074 | Intel      | Wi-Fi 6 AX201                | 36    | iwlwifi    | 0B7B90BB5D |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 31    | 8821ce     | 7B7C2317D8 |
| 8086:02f0 | 8086:0034 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 29    | iwlwifi    | EAD7DA3246 |
| 8086:a0f0 | 8086:4070 | Intel      | Wi-Fi 6 AX201                | 29    | iwlwifi    | 5B40E331B3 |
| 8086:2526 | 8086:0014 | Intel      | Wireless-AC 9260             | 27    | iwlwifi    | 6E045B787A |
| 8086:9df0 | 8086:0030 | Intel      | Cannon Point-LP CNVi [Wir... | 27    | iwlwifi    | 87DA71BBB9 |
| 8086:24fd | 8086:8010 | Intel      | Wireless 8265 / 8275         | 24    | iwlwifi    | EF7445EB15 |
| 10ec:b822 | 17aa:b023 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 23    | rtw88_8... | 86A25931BD |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 23    | iwlwifi    | CD156B08D8 |
| 8086:24f3 | 8086:1130 | Intel      | Wireless 8260                | 21    | iwlwifi    | 2A0ECA4670 |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 20    | iwlwifi    | B6BC75336E |
| 8086:02f0 | 8086:4070 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 18    | iwlwifi    | BC7C58F248 |
| 8086:24f3 | 8086:0130 | Intel      | Wireless 8260                | 17    | iwlwifi    | D878C63FE4 |
| 8086:3165 | 8086:8010 | Intel      | Wireless 3165                | 17    | iwlwifi    | 378291C3E0 |
| 8086:34f0 | 1a56:1651 | Intel      | Ice Lake-LP PCH CNVi WiFi    | 17    | iwlwifi    | 6B27A727BE |
| 8086:9df0 | 8086:4234 | Intel      | Cannon Point-LP CNVi [Wir... | 17    | iwlwifi    | B07A0CF706 |
| 8086:2723 | 8086:008c | Intel      | Wi-Fi 6 AX200                | 16    | iwlwifi    | F30D3F55AD |
| 8086:9df0 | 8086:4030 | Intel      | Cannon Point-LP CNVi [Wir... | 15    | iwlwifi    | B0722E1B57 |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 14    | iwlwifi    | 03065735FF |
| 8086:24fd | 8086:8050 | Intel      | Wireless 8265 / 8275         | 13    | iwlwifi    | C0A9C9443B |
| 8086:7360 | 8086:0020 | Intel      | XMM7360 LTE Advanced Modem   | 13    |            | E40B11DCA2 |
| 8086:02f0 | 8086:0030 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 12    | iwlwifi    | 32CA60DCEA |
| 8086:24f3 | 8086:0110 | Intel      | Wireless 8260                | 12    | iwlwifi    | 7AD86811C5 |
| 168c:0042 | 11ad:08a6 | Qualcom... | QCA9377 802.11ac Wireless... | 10    | ath10k_pci | 97DFF84E2B |
| 168c:0042 | 17aa:4035 | Qualcom... | QCA9377 802.11ac Wireless... | 10    | ath10k_pci | DC41704AEC |
| 8086:02f0 | 8086:0070 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 10    | iwlwifi    | E40B11DCA2 |
| 8086:24f3 | 8086:8010 | Intel      | Wireless 8260                | 10    | iwlwifi    | DF55EA30E7 |
| 8086:24fd | 8086:0130 | Intel      | Wireless 8265 / 8275         | 10    | iwlwifi    | 9FCFE8BF6A |
| 8086:3165 | 8086:8110 | Intel      | Wireless 3165                | 10    | iwlwifi    | 7332052765 |
| 10ec:c821 | 17aa:c024 | Realtek... | RTL8821CE 802.11ac PCIe W... | 9     | 8821ce     | 010C424C33 |
| 168c:003e | 11ad:0807 | Qualcom... | QCA6174 802.11ac Wireless... | 9     | ath10k_pci | D000862005 |
| 168c:003e | 1a56:143a | Qualcom... | QCA6174 802.11ac Wireless... | 9     | ath10k_pci | C28F77B8F1 |
| 8086:a0f0 | 1a56:1651 | Intel      | Wi-Fi 6 AX201                | 9     | iwlwifi    | AD3C1FB56A |
| 10ec:d723 | 103c:8319 | Realtek... | RTL8723DE Wireless Networ... | 8     | rtl8723de  | BDF169950D |
| 8086:02f0 | 8086:4234 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 8     | iwlwifi    | B5682ADC9E |
| 8086:7360 | 103c:8337 | Intel      | XMM7360 LTE Advanced Modem   | 8     |            | D284325FCF |
| 8086:31dc | 8086:02a4 | Intel      | Gemini Lake PCH CNVi WiFi    | 7     | iwlwifi    | 070E212C9B |
| 8086:095a | 8086:5410 | Intel      | Wireless 7265                | 6     | iwlwifi    | E4FFC93C6A |
| 8086:095a | 8086:9e10 | Intel      | Wireless 7265                | 6     | iwlwifi    | CBC1BB3811 |
| 8086:3166 | 8086:4310 | Intel      | Dual Band Wireless-AC 316... | 6     | iwlwifi    | 1E4A851AD2 |
| 8086:9df0 | 8086:0000 | Intel      | Cannon Point-LP CNVi [Wir... | 6     | iwlwifi    | 79D9E16164 |
| 10ec:b723 | 103c:804c | Realtek... | RTL8723BE PCIe Wireless N... | 5     | rtl8723be  | A8AA7A1D17 |
| 14e4:4365 | 103c:2230 | Broadcom   | BCM43142 802.11b/g/n         | 5     | wl         | 4EDDB18ED9 |
| 8086:24f3 | 8086:9010 | Intel      | Wireless 8260                | 5     | iwlwifi    | FCDC02AB43 |
| 8086:24fd | 8086:1130 | Intel      | Wireless 8265 / 8275         | 5     | iwlwifi    | 3EA410030C |
| 8086:31dc | 8086:0034 | Intel      | Gemini Lake PCH CNVi WiFi    | 5     | iwlwifi    | 19F4CA16E7 |
| 8086:34f0 | 8086:0234 | Intel      | Ice Lake-LP PCH CNVi WiFi    | 5     | iwlwifi    | 7D020ED41B |
| 8086:a370 | 8086:0034 | Intel      | Cannon Lake PCH CNVi WiFi    | 5     | iwlwifi    | 78960B975F |
| 8086:24fd | 8086:0150 | Intel      | Wireless 8265 / 8275         | 4     | iwlwifi    | 1BB17DC648 |
| 8086:2723 | 8086:4080 | Intel      | Wi-Fi 6 AX200                | 4     | iwlwifi    | 9ED34E6D16 |
| 8086:9df0 | 8086:42a4 | Intel      | Cannon Point-LP CNVi [Wir... | 4     | iwlwifi    | DDC277B9F6 |
| 14e4:43ec | 17aa:7006 | Broadco... | BCM4356 802.11ac Wireless... | 3     | brcmfmac   | 78CA0E0334 |
| 168c:003e | 1028:0310 | Qualcom... | QCA6174 802.11ac Wireless... | 3     | ath10k_pci | 91F3D918A0 |
| 168c:0042 | 1028:1810 | Qualcom... | QCA9377 802.11ac Wireless... | 3     | ath10k_pci | 8C30BDF3B8 |
| 168c:0042 | 1a3b:2231 | Qualcom... | QCA9377 802.11ac Wireless... | 3     | ath10k_pci | C8D3F204E5 |
| 8086:02f0 | 8086:4030 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 3     | iwlwifi    | A4270EEE0B |
| 8086:095a | 8086:9010 | Intel      | Wireless 7265                | 3     | iwlwifi    | B58CB2CFAB |
| 8086:2526 | 8086:0010 | Intel      | Wireless-AC 9260             | 3     | iwlwifi    | 6E5C30C5C5 |
| 8086:2723 | 8086:0080 | Intel      | Wi-Fi 6 AX200                | 3     | iwlwifi    | 4F8F955FAF |
| 8086:2723 | 8086:0088 | Intel      | Wi-Fi 6 AX200                | 3     | iwlwifi    | CE851E2475 |
| 8086:31dc | 8086:0264 | Intel      | Gemini Lake PCH CNVi WiFi    | 3     | iwlwifi    | 38E5F73567 |
| 10ec:b723 | 103c:81c1 | Realtek... | RTL8723BE PCIe Wireless N... | 2     | rtl8723be  | 198A1829BB |
| 10ec:b822 | 1a3b:2950 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 2     | rtw_pci    | 18B4F9B58E |
| 168c:0042 | 1a3b:2251 | Qualcom... | QCA9377 802.11ac Wireless... | 2     | ath10k_pci | 45B1907784 |
| 8086:02f0 | 8086:02a4 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 2     | iwlwifi    | D9D123FF85 |
| 8086:06f0 | 8086:0074 | Intel      | Comet Lake PCH CNVi WiFi     | 2     | iwlwifi    | 46AFFA13CE |
| 8086:08b3 | 8086:8070 | Intel      | Wireless 3160                | 2     | iwlwifi    | 31942977C3 |
| 8086:24fd | 8086:0110 | Intel      | Wireless 8265 / 8275         | 2     | iwlwifi    | 430A666F91 |
| 8086:7560 | 103c:8507 | Intel      | Wireless controller          | 2     |            | 2ECA85F866 |
| 8086:9df0 | 8086:02a4 | Intel      | Cannon Point-LP CNVi [Wir... | 2     | iwlwifi    | E47B0DD26C |
| 8086:a0f0 | 8086:0070 | Intel      | Wi-Fi 6 AX201                | 2     | iwlwifi    | 0B8822B65D |
| 8086:a370 | 8086:0030 | Intel      | Cannon Lake PCH CNVi WiFi    | 2     | iwlwifi    | 2668A6580A |
| 10ec:8821 | 1a3b:2161 | Realtek... | RTL8821AE 802.11ac PCIe W... | 1     | rtl8821ae  | 8269E87811 |
| 10ec:b723 | 103c:8167 | Realtek... | RTL8723BE PCIe Wireless N... | 1     | rtl8723be  | 629D516666 |
| 10ec:b822 | 17aa:b024 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 1     | r8822be    | BC69AFD822 |
| 10ec:c821 | 10ec:c821 | Realtek... | RTL8821CE 802.11ac PCIe W... | 1     |            | 88F50AB643 |
| 10ec:c822 | 11ad:0810 | Realtek... | RTL8822CE 802.11ac PCIe W... | 1     | rtw_8822ce | F8A425D2CC |
| 14e4:43a3 | 1028:0021 | Broadcom   | BCM4350 802.11ac Wireless... | 1     | brcmfmac   | 670DDC1E5C |
| 14e4:43b1 | 17aa:0623 | Broadco... | BCM4352 802.11ac Wireless... | 1     | wl         | B2BE953A1D |
| 14e4:43ba | 1028:0020 | Broadcom   | BCM43602 802.11ac Wireles... | 1     | brcmfmac   | C77AFE79C3 |
| 8086:02f0 | 8086:4034 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 1     | iwlwifi    | 3C0A6F0C03 |
| 8086:08b2 | 8086:c270 | Intel      | Wireless 7260                | 1     | iwlwifi    | F6650D66F7 |
| 8086:093c | 8086:2191 | Intel      | Wireless Gigabit 17265       | 1     |            | 805B5CFC62 |
| 8086:095a | 8086:5110 | Intel      | Wireless 7265                | 1     | iwlwifi    | 932B22C52A |
| 8086:095b | 8086:5210 | Intel      | Wireless 7265                | 1     | iwlwifi    | C65BB14578 |
| 8086:24f3 | 8086:0930 | Intel      | Wireless 8260                | 1     | iwlwifi    | 805B5CFC62 |
| 8086:34f0 | 8086:0034 | Intel      | Ice Lake-LP PCH CNVi WiFi    | 1     | iwlwifi    | D22BAD4798 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1533 | 1ab6:0214 | Intel      | I210 Gigabit Network Conn... | 1     | igb        | B918F25E12 |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d26 |           | Intel      | Skylake-U/Y Northpeak        | 19    | intel_t... | 03065735FF |
| 8086:318e |           | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_t... | 582965792D |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d35 | 8086:9d35 | Intel      | Sunrise Point-LP Integrat... | 30    | intel_i... | 7AD86811C5 |
| 8086:9d35 | 103c:83b9 | Intel      | Sunrise Point-LP Integrat... | 24    | intel_i... | 2C533BE257 |
| 1022:15e4 | 103c:85dd | AMD        | Raven/Raven2/Renoir Senso... | 22    | amd_sfh    | A93B2565DF |
| 8086:9d35 | 17aa:2238 | Intel      | Sunrise Point-LP Integrat... | 19    | intel_i... | D878C63FE4 |
| 8086:9d35 | 17aa:380d | Intel      | Sunrise Point-LP Integrat... | 19    | intel_i... | 1A0B1FFDBD |
| 1022:15e4 | 103c:85de | AMD        | Raven/Raven2/Renoir Senso... | 17    | amd_sfh    | 9E86C8EDE5 |
| 1022:15e6 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Non-S... | 16    | i2c_amd... | 57651669E3 |
| 1022:15e4 | 103c:8496 | AMD        | Raven/Raven2/Renoir Senso... | 14    | amd_sfh    | 8A63E2E055 |
| 8086:9d35 | 103c:830f | Intel      | Sunrise Point-LP Integrat... | 14    | intel_i... | B6BC75336E |
| 1022:15e4 | 103c:8497 | AMD        | Raven/Raven2/Renoir Senso... | 13    | pcie_mp... | 2910A4173E |
| 8086:9d35 | 103c:827d | Intel      | Sunrise Point-LP Integrat... | 13    | intel_i... | 51178C1953 |
| 8086:9d35 | 103c:8486 | Intel      | Sunrise Point-LP Integrat... | 13    | intel_i... | B149A04EE8 |
| 8086:a135 | 103c:83bb | Intel      | 100 Series/C230 Series Ch... | 13    | intel_i... | BA09E3B76F |
| 8086:9d35 | 103c:827e | Intel      | Sunrise Point-LP Integrat... | 12    | intel_i... | B3CFF29C2E |
| 8086:9d35 | 17aa:2259 | Intel      | Sunrise Point-LP Integrat... | 12    | intel_i... | C96223F666 |
| 8086:9d35 | 1028:077a | Intel      | Sunrise Point-LP Integrat... | 11    | intel_i... | C0A9C9443B |
| 8086:9d35 | 17aa:224e | Intel      | Sunrise Point-LP Integrat... | 11    | intel_i... | B866426527 |
| 8086:9d35 | 103c:8488 | Intel      | Sunrise Point-LP Integrat... | 10    | intel_i... | 7B7C2317D8 |
| 8086:9d35 | 1043:1ab0 | Intel      | Sunrise Point-LP Integrat... | 10    | intel_i... | CE8E9AF30D |
| 8086:9d35 | 103c:81a1 | Intel      | Sunrise Point-LP Integrat... | 9     | intel_i... | B37CBA5DF4 |
| 8086:a135 | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 9     | intel_i... | C28F77B8F1 |
| 8086:9d35 | 103c:8438 | Intel      | Sunrise Point-LP Integrat... | 8     | intel_i... | 633CDE303A |
| 8086:9d24 |           | Intel      | Skylake-U/Y SPI Controller   | 7     |            | CBC1BB3811 |
| 8086:9d35 | 17aa:506d | Intel      | Sunrise Point-LP Integrat... | 7     | intel_i... | 847655CB40 |
| 8086:9d35 | 103c:8484 | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | D46010346C |
| 8086:9d35 | 1043:1c90 | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | AED32F7A4D |
| 8086:9d35 | 17aa:2237 | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | 2A0ECA4670 |
| 8086:9d35 | 1028:07eb | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | E4FFC93C6A |
| 8086:9d35 | 103c:81a9 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 0BB3F77C75 |
| 8086:9d35 | 103c:81ad | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | CE728E8715 |
| 8086:9d35 | 103c:827f | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | BD5BDFD31F |
| 8086:9d35 | 103c:8313 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | DCD840E8A2 |
| 8086:9d35 | 103c:8483 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | C41A1DE997 |
| 8086:9d35 | 103c:8487 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | CA8936A74C |
| 8086:9d35 | 17aa:504c | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 4983586FE5 |
| 8086:9d35 | 17aa:506c | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 6C4ABD0606 |
| 8086:9d35 | 103c:81a7 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | BC77E670A5 |
| 8086:9d35 | 103c:82c1 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | CF06BA276E |
| 8086:9d35 | 103c:83c4 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 3F62C672FB |
| 8086:9d35 | 103c:84d8 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 03FE12C3CC |
| 8086:9d35 | 17aa:5061 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 9FCFE8BF6A |
| 1022:15e4 | 1028:090c | AMD        | Raven/Raven2/Renoir Senso... | 3     |            | B6C573F5AA |
| 8086:22d8 | 8086:7270 | Intel      | Integrated Sensor Solution   | 3     | intel_i... | 78CA0E0334 |
| 8086:9d35 | 1028:07aa | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 5492FDD780 |
| 8086:9d35 | 1028:0878 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 91F3D918A0 |
| 8086:9d35 | 103c:82b7 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 3B8F11D2DB |
| 8086:9d35 | 103c:8310 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | D7D0DE8CF4 |
| 8086:9d35 | 103c:83ba | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | FB88A217E9 |
| 8086:9d35 | 103c:8470 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | EF7445EB15 |
| 8086:9d35 | 1043:1c40 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | BD57C16BE8 |
| 8086:9d35 | 144d:c162 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 5DA835E33E |
| 8086:9d35 | 17aa:380c | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 32B0895AB5 |
| 1022:15e4 | 1025:1506 | AMD        | Raven/Raven2/Renoir Senso... | 2     | amd_sfh    | D000862005 |
| 8086:9d35 | 103c:804f | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | E5C02D2922 |
| 8086:9d35 | 103c:8143 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 03065735FF |
| 8086:9d35 | 103c:81ac | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 235D55372B |
| 8086:9d35 | 103c:8251 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | A758FDF9AF |
| 8086:9d35 | 103c:8314 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 5CF089CFA1 |
| 8086:9d35 | 103c:83c9 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 8BF489A0CB |
| 8086:9d35 | 103c:8503 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | F6ABCD9B4F |
| 8086:9d35 | 144d:c141 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | ADF6EF8A4C |
| 8086:9d35 |           | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 2293E21257 |
| 8086:9d35 | 1028:07ec | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 4CCEC31055 |
| 8086:9d35 | 1028:0823 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 1BB17DC648 |
| 8086:9d35 | 103c:80cf | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 15B7980DAF |
| 8086:9d35 | 103c:80d1 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | EC722FBBFE |
| 8086:9d35 | 103c:8174 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 48C1B1144A |
| 8086:9d35 | 103c:8252 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | E610D18176 |
| 8086:9d35 | 103c:8316 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 122A201FB4 |
| 8086:9d35 | 103c:83c5 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | AA7134D622 |
| 8086:9d35 | 103c:8491 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 8CE6E9CB36 |
| 8086:9d35 | 103c:8770 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 87199D7E85 |
| 8086:9d35 | 1043:1b40 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 0324B06288 |
| 8086:9d35 | 1179:0001 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 430A666F91 |
| 8086:9d35 | 144d:c14b | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | FCDC02AB43 |
| 8086:9d35 | 144d:c14c | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 6E023867E9 |
| 8086:9d35 | 144d:c157 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 70CA86BF4D |
| 8086:9d35 | 144d:c15f | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | ED50EF80EA |
| 8086:9d35 | 144d:c164 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | F84F88E2C8 |
| 8086:9d35 | 152d:1147 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 7DA5C4A4FA |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | sdhci_pci  | 378291C3E0 |
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | sdhci_pci  | 38E5F73567 |
| 8086:31d0 | 8086:7270 | Intel      | SD Host Controller           | 20    | sdhci_pci  | 38E5F73567 |
| 1217:8621 | 17aa:39f6 | O2 Micro   | SD/MMC Card Reader Contro... | 19    | sdhci_pci  | CD156B08D8 |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 13    | sdhci_pci  | 378291C3E0 |
| 8086:9d2d | 103c:8486 | Intel      | Sunrise Point-LP Secure D... | 13    | sdhci_pci  | B149A04EE8 |
| 1217:8621 | 17aa:3817 | O2 Micro   | SD/MMC Card Reader Contro... | 11    | sdhci_pci  | A60117C096 |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 10    | sdhci_pci  | 378291C3E0 |
| 8086:9d2b | 103c:8488 | Intel      | Skylake-U/Y SCC: eMMC        | 10    | sdhci_pci  | 7B7C2317D8 |
| 8086:9d2d | 103c:8488 | Intel      | Sunrise Point-LP Secure D... | 10    | sdhci_pci  | 7B7C2317D8 |
| 1217:8621 | 17aa:381b | O2 Micro   | SD/MMC Card Reader Contro... | 7     | sdhci_pci  | 64A9E43743 |
| 8086:9df5 | 103c:85c4 | Intel      | BayHubTech Integrated SD ... | 7     | sdhci_pci  | 9BCBAF17E9 |
| 8086:02f5 | 103c:866e | Intel      | Comet Lake PCH-LP SCS3       | 6     | sdhci_pci  | 22FAA280E3 |
| 8086:9d2b | 1ae0:006b | Intel      | Skylake-U/Y SCC: eMMC        | 6     | sdhci_pci  | CBC1BB3811 |
| 1217:8520 | 17aa:504c | O2 Micro   | SD/MMC Card Reader Contro... | 5     | sdhci_pci  | 4983586FE5 |
| 8086:02f5 | 1028:0950 | Intel      | Comet Lake PCH-LP SCS3       | 5     | sdhci_pci  | 9DD76AE820 |
| 8086:5aca | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 5     | sdhci_pci  | 98851C034C |
| 8086:5acc | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 5     | sdhci_pci  | 98851C034C |
| 8086:9d2d | 103c:8487 | Intel      | Sunrise Point-LP Secure D... | 5     | sdhci_pci  | CA8936A74C |
| 1217:8621 | 17aa:383e | O2 Micro   | SD/MMC Card Reader Contro... | 4     | sdhci_pci  | 78960B975F |
| 8086:02f5 | 1028:0951 | Intel      | Comet Lake PCH-LP SCS3       | 4     | sdhci_pci  | 247867F57E |
| 8086:9d2d | 103c:84d8 | Intel      | Sunrise Point-LP Secure D... | 4     | sdhci_pci  | 03FE12C3CC |
| 8086:9df5 | 103c:850e | Intel      | BayHubTech Integrated SD ... | 4     | sdhci_pci  | 0C2D648815 |
| 8086:9df5 | 103c:85c8 | Intel      | BayHubTech Integrated SD ... | 4     | sdhci_pci  | 1649B0B654 |
| 8086:9df5 | 103c:85cd | Intel      | BayHubTech Integrated SD ... | 4     | sdhci_pci  | E7DCDD4B39 |
| 8086:2294 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 3     | sdhci_pci  | D423BBA02B |
| 8086:31cc | 1025:1316 | Intel      | Celeron/Pentium Silver Pr... | 3     | sdhci_pci  | 19F4CA16E7 |
| 8086:9df5 | 1028:0908 | Intel      | BayHubTech Integrated SD ... | 3     | sdhci_pci  | C086BA0897 |
| 8086:9df5 | 103c:85c5 | Intel      | BayHubTech Integrated SD ... | 3     | sdhci_pci  | D2D2EB910A |
| 1217:8621 | 17aa:3814 | O2 Micro   | SD/MMC Card Reader Contro... | 2     | sdhci_pci  | 3C0A5BE140 |
| 1217:8621 | 17aa:3846 | O2 Micro   | SD/MMC Card Reader Contro... | 2     | sdhci_pci  | 3E9117AA42 |
| 17a0:9750 | 17a0:9750 | Genesys... | GL9750 SD Host Controller    | 2     | sdhci_pci  | E2A9000D5B |
| 8086:02f5 | 103c:8671 | Intel      | Comet Lake PCH-LP SCS3       | 2     | sdhci_pci  | 74D939AB7B |
| 8086:31cc | 1025:1293 | Intel      | Celeron/Pentium Silver Pr... | 2     | sdhci_pci  | 0A09D00B74 |
| 8086:31cc | 1028:081f | Intel      | Celeron/Pentium Silver Pr... | 2     | sdhci_pci  | 582965792D |
| 8086:31cc | 17aa:3801 | Intel      | Celeron/Pentium Silver Pr... | 2     | sdhci_pci  | 3E9117AA42 |
| 8086:5aca | 103c:830d | Intel      | Celeron N3350/Pentium N42... | 2     | sdhci_pci  | 27DC03B58E |
| 8086:5acc | 1043:1d90 | Intel      | Celeron N3350/Pentium N42... | 2     | sdhci_pci  | C8D3F204E5 |
| 8086:5ad0 | 103c:830d | Intel      | Celeron N3350/Pentium N42... | 2     | sdhci_pci  | 27DC03B58E |
| 8086:9d2d | 8086:9d2d | Intel      | Sunrise Point-LP Secure D... | 2     | sdhci_pci  | 6F018F175E |
| 1217:8520 | 1e26:001c | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 437C9D66AA |
| 1217:8621 | 17aa:3818 | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | EC411DE2BB |
| 1217:8621 | 17aa:3828 | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 6834D8137C |
| 1217:8621 | 17aa:3837 | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | DE8ECBD462 |
| 1217:8621 | 17aa:383b | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 29E4FF83DB |
| 8086:02f5 | 103c:8670 | Intel      | Comet Lake PCH-LP SCS3       | 1     | sdhci_pci  | 9212F9DB05 |
| 8086:02f5 | 103c:8672 | Intel      | Comet Lake PCH-LP SCS3       | 1     | sdhci_pci  | 8E5E4CCD9B |
| 8086:02f5 | 103c:86ec | Intel      | Comet Lake PCH-LP SCS3       | 1     | sdhci_pci  | 483D4785B1 |
| 8086:02f5 | 8086:7270 | Intel      | Comet Lake PCH-LP SCS3       | 1     | sdhci_pci  | EE715DE644 |
| 8086:31cc | 1025:129f | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | 0F6F9B0A03 |
| 8086:31cc | 103c:86cf | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | 33D5688BFC |
| 8086:31cc | 17aa:506e | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | 65846CBF2B |
| 8086:31d0 | 103c:86cf | Intel      | SD Host Controller           | 1     | sdhci_pci  | 33D5688BFC |
| 8086:34c4 | 17aa:3801 | Intel      | Ice Lake-LP SD Host Contr... | 1     | sdhci_pci  | DE8ECBD462 |
| 8086:34f8 | 17aa:3801 | Intel      | Ice Lake-LP SD Controller    | 1     | sdhci_pci  | DE8ECBD462 |
| 8086:5acc | 1025:1148 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | C55FC9990D |
| 8086:5acc | 1025:1150 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 97DFF84E2B |
| 8086:5acc | 1043:1930 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | B6FC10EFA8 |
| 8086:5acc | 1043:1d60 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 45B1907784 |
| 8086:9d2b |           | Intel      | Skylake-U/Y SCC: eMMC        | 1     | sdhci_pci  | 2293E21257 |
| 8086:9d2b | 8086:7270 | Intel      | Skylake-U/Y SCC: eMMC        | 1     | sdhci_pci  | C78BE59C16 |
| 8086:9d2b | 8086:9d2b | Intel      | Skylake-U/Y SCC: eMMC        | 1     | sdhci_pci  | 2C6BCC75CC |
| 8086:9d2d |           | Intel      | Sunrise Point-LP Secure D... | 1     | sdhci_pci  | 2293E21257 |
| 8086:9d2d | 103c:8491 | Intel      | Sunrise Point-LP Secure D... | 1     | sdhci_pci  | 8CE6E9CB36 |
| 8086:9dc4 | 8086:7270 | Intel      | 300 Series Chipset SD Hos... | 1     | sdhci_pci  | DC14D7EC63 |
| 8086:9df5 | 103c:85c6 | Intel      | BayHubTech Integrated SD ... | 1     | sdhci_pci  | 447AC858DA |
| 8086:9df5 | 8086:7270 | Intel      | BayHubTech Integrated SD ... | 1     | sdhci_pci  | DC14D7EC63 |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:02a4 | 17aa:3804 | Intel      | Comet Lake SPI (flash) Co... | 28    | intel_s... | F72E765EF0 |
| 8086:02c5 | 17aa:3802 | Intel      | Comet Lake Serial IO I2C ... | 28    | intel_lpss | F72E765EF0 |
| 8086:02e8 | 17aa:3807 | Intel      | Serial IO I2C Host Contro... | 28    | intel_lpss | F72E765EF0 |
| 8086:02e9 | 17aa:3802 | Intel      | Comet Lake Serial IO I2C ... | 28    | intel_lpss | F72E765EF0 |
| 8086:9da4 | 8086:9da4 | Intel      | Cannon Point-LP SPI Contr... | 24    |            | CD156B08D8 |
| 8086:9da4 | 103c:8514 | Intel      | Cannon Point-LP SPI Contr... | 23    |            | 2352CAA9CF |
| 8086:9de8 | 103c:8514 | Intel      | Cannon Point-LP Serial IO... | 23    | intel_l... | 2352CAA9CF |
| 8086:9de9 | 103c:8514 | Intel      | Cannon Point-LP Serial IO... | 23    | intel_l... | 2352CAA9CF |
| 8086:9de8 | 17aa:380b | Intel      | Cannon Point-LP Serial IO... | 22    | intel_l... | CD156B08D8 |
| 8086:9de9 | 17aa:3804 | Intel      | Cannon Point-LP Serial IO... | 22    | intel_l... | CD156B08D8 |
| 8086:9dea | 17aa:3802 | Intel      | 8th Gen Intel Core Proces... | 22    | intel_l... | CD156B08D8 |
| 8086:34a4 | 17aa:3804 | Intel      | Ice Lake-LP SPI Controller   | 21    | intel_s... | 7C965E245C |
| 8086:34e8 | 17aa:3806 | Intel      | Ice Lake-LP Serial IO I2C... | 21    | intel_l... | 7C965E245C |
| 8086:34e9 | 17aa:3801 | Intel      | Ice Lake-LP Serial IO I2C... | 21    | intel_l... | 7C965E245C |
| 8086:34a4 | 1028:08b0 | Intel      | Ice Lake-LP SPI Controller   | 17    | intel_spi  | 6B27A727BE |
| 8086:34e8 | 1028:08b0 | Intel      | Ice Lake-LP Serial IO I2C... | 17    | intel_l... | 6B27A727BE |
| 8086:34e9 | 1028:08b0 | Intel      | Ice Lake-LP Serial IO I2C... | 17    | intel_l... | 6B27A727BE |
| 8086:34eb | 1028:08b0 | Intel      | Ice Lake-LP Serial IO I2C... | 17    | intel_l... | 6B27A727BE |
| 8086:9da4 | 17aa:2292 | Intel      | Cannon Point-LP SPI Contr... | 16    |            | 3795F3DF87 |
| 8086:9de8 | 17aa:2292 | Intel      | Cannon Point-LP Serial IO... | 16    | intel_l... | 3795F3DF87 |
| 8086:9de9 | 17aa:2292 | Intel      | Cannon Point-LP Serial IO... | 16    | intel_l... | 3795F3DF87 |
| 8086:34a4 | 17aa:3812 | Intel      | Ice Lake-LP SPI Controller   | 15    | intel_s... | 2E19A058F9 |
| 8086:34e8 | 17aa:3840 | Intel      | Ice Lake-LP Serial IO I2C... | 15    | intel_l... | 2E19A058F9 |
| 8086:34e9 | 17aa:3841 | Intel      | Ice Lake-LP Serial IO I2C... | 15    | intel_l... | 2E19A058F9 |
| 8086:34ea | 17aa:3842 | Intel      | Ice Lake-LP Serial IO I2C... | 15    | intel_l... | 2E19A058F9 |
| 8086:9da4 | 8086:7270 | Intel      | Cannon Point-LP SPI Contr... | 14    |            | 30B72B97CB |
| 8086:02a4 | 17aa:3806 | Intel      | Comet Lake SPI (flash) Co... | 13    | intel_s... | 5BDCB41FEE |
| 8086:02e8 | 17aa:3806 | Intel      | Serial IO I2C Host Contro... | 13    | intel_l... | 5BDCB41FEE |
| 8086:02e9 | 17aa:3806 | Intel      | Comet Lake Serial IO I2C ... | 13    | intel_l... | 5BDCB41FEE |
| 8086:a0a4 | 1028:0a05 | Intel      | Tiger Lake-LP SPI Controller | 13    |            | 71B5E3C825 |
| 8086:a0e8 | 1028:0a05 | Intel      | Tiger Lake-LP Serial IO I... | 13    | intel_l... | 71B5E3C825 |
| 8086:a0e9 | 1028:0a05 | Intel      | Tiger Lake-LP Serial IO I... | 13    | intel_l... | 71B5E3C825 |
| 8086:02a4 | 17aa:5078 | Intel      | Comet Lake SPI (flash) Co... | 9     | intel_s... | 7C78B71A99 |
| 8086:02e8 | 17aa:5078 | Intel      | Serial IO I2C Host Contro... | 9     | intel_l... | 7C78B71A99 |
| 8086:9da4 | 1028:0894 | Intel      | Cannon Point-LP SPI Contr... | 9     |            | B07A0CF706 |
| 8086:9de8 | 1028:0894 | Intel      | Cannon Point-LP Serial IO... | 9     | intel_l... | B07A0CF706 |
| 8086:9de9 | 1028:0894 | Intel      | Cannon Point-LP Serial IO... | 9     | intel_l... | B07A0CF706 |
| 8086:a0a4 | 1028:09ff | Intel      | Tiger Lake-LP SPI Controller | 9     |            | AD3C1FB56A |
| 8086:a0a4 | 17aa:381b | Intel      | Tiger Lake-LP SPI Controller | 9     |            | 13AC1F05DD |
| 8086:a0ab | 17aa:3822 | Intel      | Tiger Lake-LP Serial IO S... | 9     | intel_l... | 13AC1F05DD |
| 8086:a0e8 | 1028:09ff | Intel      | Tiger Lake-LP Serial IO I... | 9     | intel_lpss | AD3C1FB56A |
| 8086:a0e8 | 17aa:3841 | Intel      | Tiger Lake-LP Serial IO I... | 9     | intel_l... | 13AC1F05DD |
| 8086:a0e9 | 1028:09ff | Intel      | Tiger Lake-LP Serial IO I... | 9     | intel_lpss | AD3C1FB56A |
| 8086:a0e9 | 17aa:3842 | Intel      | Tiger Lake-LP Serial IO I... | 9     | intel_l... | 13AC1F05DD |
| 8086:02a4 | 1028:095d | Intel      | Comet Lake SPI (flash) Co... | 8     |            | B5682ADC9E |
| 8086:02e8 | 1028:095d | Intel      | Serial IO I2C Host Contro... | 8     | intel_l... | B5682ADC9E |
| 8086:02e9 | 1028:095d | Intel      | Comet Lake Serial IO I2C ... | 8     | intel_l... | B5682ADC9E |
| 8086:02a4 | 1028:09cd | Intel      | Comet Lake SPI (flash) Co... | 7     |            | BC7C58F248 |
| 8086:02a4 | 103c:863f | Intel      | Comet Lake SPI (flash) Co... | 7     |            | 638C4207CE |
| 8086:02a4 | 103c:86b1 | Intel      | Comet Lake SPI (flash) Co... | 7     | intel_spi  | 093BEED213 |
| 8086:02a4 | 103c:86b2 | Intel      | Comet Lake SPI (flash) Co... | 7     |            | 42A03DCD82 |
| 8086:02c5 | 1028:09cd | Intel      | Comet Lake Serial IO I2C ... | 7     | intel_l... | BC7C58F248 |
| 8086:02e8 | 1028:09cd | Intel      | Serial IO I2C Host Contro... | 7     | intel_l... | BC7C58F248 |
| 8086:02e8 | 103c:863f | Intel      | Serial IO I2C Host Contro... | 7     | intel_l... | 638C4207CE |
| 8086:02e8 | 103c:86b1 | Intel      | Serial IO I2C Host Contro... | 7     | intel_l... | 093BEED213 |
| 8086:02e8 | 103c:86b2 | Intel      | Serial IO I2C Host Contro... | 7     | intel_l... | 42A03DCD82 |
| 8086:02e9 | 1028:09cd | Intel      | Comet Lake Serial IO I2C ... | 7     | intel_l... | BC7C58F248 |
| 8086:02e9 | 103c:863f | Intel      | Comet Lake Serial IO I2C ... | 7     | intel_l... | 638C4207CE |
| 8086:02e9 | 103c:86b1 | Intel      | Comet Lake Serial IO I2C ... | 7     | intel_l... | 093BEED213 |
| 8086:02e9 | 103c:86b2 | Intel      | Comet Lake Serial IO I2C ... | 7     | intel_l... | 42A03DCD82 |
| 8086:34a4 | 103c:86f9 | Intel      | Ice Lake-LP SPI Controller   | 7     | intel_s... | A18B247E3D |
| 8086:34e8 | 103c:86f9 | Intel      | Ice Lake-LP Serial IO I2C... | 7     | intel_l... | A18B247E3D |
| 8086:34e9 | 103c:86f9 | Intel      | Ice Lake-LP Serial IO I2C... | 7     | intel_l... | A18B247E3D |
| 8086:9da4 | 103c:85c4 | Intel      | Cannon Point-LP SPI Contr... | 7     |            | 9BCBAF17E9 |
| 8086:9da4 | 103c:861f | Intel      | Cannon Point-LP SPI Contr... | 7     |            | D284325FCF |
| 8086:9de8 | 103c:85c4 | Intel      | Cannon Point-LP Serial IO... | 7     | intel_lpss | 9BCBAF17E9 |
| 8086:9de8 | 103c:861f | Intel      | Cannon Point-LP Serial IO... | 7     | intel_l... | D284325FCF |
| 8086:9de9 | 103c:85c4 | Intel      | Cannon Point-LP Serial IO... | 7     | intel_lpss | 9BCBAF17E9 |
| 8086:9de9 | 103c:861f | Intel      | Cannon Point-LP Serial IO... | 7     | intel_l... | D284325FCF |
| 8086:02a4 | 103c:866e | Intel      | Comet Lake SPI (flash) Co... | 6     | intel_s... | 22FAA280E3 |
| 8086:02e8 | 103c:866e | Intel      | Serial IO I2C Host Contro... | 6     | intel_l... | 22FAA280E3 |
| 8086:02e9 | 103c:866e | Intel      | Comet Lake Serial IO I2C ... | 6     | intel_l... | 22FAA280E3 |
| 8086:34a4 | 1025:141f | Intel      | Ice Lake-LP SPI Controller   | 6     | intel_s... | AA8934716B |
| 8086:34e8 | 1025:141f | Intel      | Ice Lake-LP Serial IO I2C... | 6     | intel_l... | AA8934716B |
| 8086:34e9 | 1025:141f | Intel      | Ice Lake-LP Serial IO I2C... | 6     | intel_l... | AA8934716B |
| 8086:34ea | 1025:141f | Intel      | Ice Lake-LP Serial IO I2C... | 6     | intel_l... | AA8934716B |
| 8086:9da4 | 1028:089e | Intel      | Cannon Point-LP SPI Contr... | 6     |            | C6692154A1 |
| 8086:9de8 | 1028:089e | Intel      | Cannon Point-LP Serial IO... | 6     | intel_l... | C6692154A1 |
| 8086:9de9 | 1028:089e | Intel      | Cannon Point-LP Serial IO... | 6     | intel_l... | C6692154A1 |
| 8086:a0a4 | 1028:09dd | Intel      | Tiger Lake-LP SPI Controller | 6     |            | 6BFDD9FDA4 |
| 8086:a0e8 | 1028:09dd | Intel      | Tiger Lake-LP Serial IO I... | 6     | intel_l... | 6BFDD9FDA4 |
| 8086:a0e9 | 1028:09dd | Intel      | Tiger Lake-LP Serial IO I... | 6     | intel_l... | 6BFDD9FDA4 |
| 8086:02a4 | 1028:0950 | Intel      | Comet Lake SPI (flash) Co... | 5     | intel_s... | 9DD76AE820 |
| 8086:02a4 | 17aa:2292 | Intel      | Comet Lake SPI (flash) Co... | 5     | intel_s... | 32CA60DCEA |
| 8086:02a4 | 17aa:22be | Intel      | Comet Lake SPI (flash) Co... | 5     | intel_s... | E40B11DCA2 |
| 8086:02a4 | 17aa:3803 | Intel      | Comet Lake SPI (flash) Co... | 5     | intel_spi  | D9D123FF85 |
| 8086:02e8 | 1028:0950 | Intel      | Serial IO I2C Host Contro... | 5     | intel_l... | 9DD76AE820 |
| 8086:02e8 | 17aa:2292 | Intel      | Serial IO I2C Host Contro... | 5     | intel_l... | 32CA60DCEA |
| 8086:02e8 | 17aa:22be | Intel      | Serial IO I2C Host Contro... | 5     | intel_l... | E40B11DCA2 |
| 8086:02e8 | 17aa:3804 | Intel      | Serial IO I2C Host Contro... | 5     | intel_l... | D9D123FF85 |
| 8086:02e9 | 1028:0950 | Intel      | Comet Lake Serial IO I2C ... | 5     | intel_l... | 9DD76AE820 |
| 8086:02e9 | 17aa:2292 | Intel      | Comet Lake Serial IO I2C ... | 5     | intel_l... | 32CA60DCEA |
| 8086:02e9 | 17aa:22be | Intel      | Comet Lake Serial IO I2C ... | 5     | intel_l... | E40B11DCA2 |
| 8086:02e9 | 17aa:3803 | Intel      | Comet Lake Serial IO I2C ... | 5     | intel_l... | D9D123FF85 |
| 8086:02ea | 17aa:3806 | Intel      | Comet Lake PCH-LP LPSS: I... | 5     | intel_l... | D9D123FF85 |
| 8086:9da4 | 1028:08b6 | Intel      | Cannon Point-LP SPI Contr... | 5     |            | B0722E1B57 |
| 8086:9da4 | 103c:85e7 | Intel      | Cannon Point-LP SPI Contr... | 5     |            | 169477DE3F |
| 8086:9da4 | 1043:19d1 | Intel      | Cannon Point-LP SPI Contr... | 5     |            | 9054D4EBEB |
| 8086:9da4 | 17aa:2294 | Intel      | Cannon Point-LP SPI Contr... | 5     |            | 09DC5430DA |
| 8086:9da4 | 17aa:5077 | Intel      | Cannon Point-LP SPI Contr... | 5     |            | 87DA71BBB9 |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:02fc | 17aa:3804 | Intel      | Comet Lake Integrated Sen... | 28    | intel_i... | F72E765EF0 |
| 8086:9dfc | 103c:8514 | Intel      | Cannon Point-LP Integrate... | 23    | intel_i... | 2352CAA9CF |
| 8086:34fc | 17aa:380e | Intel      | Ice Lake-LP Integrated Se... | 21    | intel_i... | 7C965E245C |
| 8086:34fc | 1028:08b0 | Intel      | Ice Lake-LP Integrated Se... | 17    | intel_i... | 6B27A727BE |
| 8086:9dfc | 17aa:2292 | Intel      | Cannon Point-LP Integrate... | 16    | intel_i... | 3795F3DF87 |
| 8086:34fc | 17aa:384d | Intel      | Ice Lake-LP Integrated Se... | 15    | intel_i... | 2E19A058F9 |
| 8086:02fc | 17aa:3806 | Intel      | Comet Lake Integrated Sen... | 13    | intel_i... | 5BDCB41FEE |
| 8086:a0fc | 1028:0a05 | Intel      | Tiger Lake-LP Integrated ... | 13    | intel_i... | 71B5E3C825 |
| 8086:9d3d | 103c:827d | Intel      | Sunrise Point-LP Active M... | 11    | serial     | 51178C1953 |
| 8086:9dfc | 8086:7270 | Intel      | Cannon Point-LP Integrate... | 10    | intel_i... | 30B72B97CB |
| 8086:02fc | 17aa:5078 | Intel      | Comet Lake Integrated Sen... | 9     | intel_i... | 7C78B71A99 |
| 8086:9dfc | 1028:0894 | Intel      | Cannon Point-LP Integrate... | 9     | intel_i... | B07A0CF706 |
| 8086:a0fc | 1028:09ff | Intel      | Tiger Lake-LP Integrated ... | 9     | intel_i... | AD3C1FB56A |
| 8086:a0fc | 17aa:3850 | Intel      | Tiger Lake-LP Integrated ... | 9     | intel_i... | 13AC1F05DD |
| 8086:02fc | 1028:095d | Intel      | Comet Lake Integrated Sen... | 8     | intel_i... | B5682ADC9E |
| 8086:02fc | 1028:09cd | Intel      | Comet Lake Integrated Sen... | 7     | intel_i... | BC7C58F248 |
| 8086:02fc | 103c:863f | Intel      | Comet Lake Integrated Sen... | 7     | intel_i... | 638C4207CE |
| 8086:02fc | 103c:86b1 | Intel      | Comet Lake Integrated Sen... | 7     | intel_i... | 093BEED213 |
| 8086:02fc | 103c:86b2 | Intel      | Comet Lake Integrated Sen... | 7     | intel_i... | 42A03DCD82 |
| 8086:34fc | 103c:86f9 | Intel      | Ice Lake-LP Integrated Se... | 7     | intel_i... | A18B247E3D |
| 8086:9d3d | 17aa:2259 | Intel      | Sunrise Point-LP Active M... | 7     | serial     | C96223F666 |
| 8086:9dfc | 103c:85c4 | Intel      | Cannon Point-LP Integrate... | 7     | intel_i... | 9BCBAF17E9 |
| 8086:9dfc | 103c:861f | Intel      | Cannon Point-LP Integrate... | 7     | intel_i... | D284325FCF |
| 8086:02fc | 103c:866e | Intel      | Comet Lake Integrated Sen... | 6     | intel_i... | 22FAA280E3 |
| 8086:9d3d | 17aa:224e | Intel      | Sunrise Point-LP Active M... | 6     | serial     | B866426527 |
| 8086:9dfc | 1028:089e | Intel      | Cannon Point-LP Integrate... | 6     | intel_i... | C6692154A1 |
| 8086:a0fc | 1028:09dd | Intel      | Tiger Lake-LP Integrated ... | 6     | intel_i... | 6BFDD9FDA4 |
| 8086:02fc | 1028:0950 | Intel      | Comet Lake Integrated Sen... | 5     | intel_i... | 9DD76AE820 |
| 8086:02fc | 17aa:2292 | Intel      | Comet Lake Integrated Sen... | 5     | intel_i... | 32CA60DCEA |
| 8086:02fc | 17aa:22be | Intel      | Comet Lake Integrated Sen... | 5     | intel_i... | E40B11DCA2 |
| 8086:9de3 | 17aa:2292 | Intel      | Cannon Point-LP Keyboard ... | 5     | serial     | 3795F3DF87 |
| 8086:9dfc | 1028:08b6 | Intel      | Cannon Point-LP Integrate... | 5     | intel_i... | B0722E1B57 |
| 8086:9dfc | 103c:85e7 | Intel      | Cannon Point-LP Integrate... | 5     | intel_i... | 169477DE3F |
| 8086:9dfc | 1043:19d1 | Intel      | Cannon Point-LP Integrate... | 5     | intel_i... | 9054D4EBEB |
| 8086:9dfc | 17aa:2294 | Intel      | Cannon Point-LP Integrate... | 5     | intel_i... | 09DC5430DA |
| 8086:9dfc | 17aa:5077 | Intel      | Cannon Point-LP Integrate... | 5     | intel_i... | 87DA71BBB9 |
| 8086:a0fc | 103c:87f7 | Intel      | Tiger Lake-LP Integrated ... | 5     | intel_i... | 48A0452D0B |
| 8086:a0fc | 17aa:3841 | Intel      | Tiger Lake-LP Integrated ... | 5     | intel_i... | 0B7B90BB5D |
| 8086:02e3 | 1028:09cd | Intel      | Comet Lake PCH-LP Keyboar... | 4     | serial     | E4ABE2A187 |
| 8086:02fc | 1028:0951 | Intel      | Comet Lake Integrated Sen... | 4     | intel_i... | 247867F57E |
| 8086:34fc | 103c:86fa | Intel      | Ice Lake-LP Integrated Se... | 4     | intel_i... | 520E728AF7 |
| 8086:9d3d | 17aa:2238 | Intel      | Sunrise Point-LP Active M... | 4     | serial     | D878C63FE4 |
| 8086:9d3d | 17aa:5061 | Intel      | Sunrise Point-LP Active M... | 4     | serial     | 9FCFE8BF6A |
| 8086:9d3d | 17aa:506d | Intel      | Sunrise Point-LP Active M... | 4     | serial     | 6B1A65C794 |
| 8086:9dfc | 1028:08e2 | Intel      | Cannon Point-LP Integrate... | 4     | intel_i... | 31C59F8FC7 |
| 8086:9dfc | 103c:850c | Intel      | Cannon Point-LP Integrate... | 4     | intel_i... | EEC05D1BF9 |
| 8086:9dfc | 103c:850e | Intel      | Cannon Point-LP Integrate... | 4     | intel_i... | 0C2D648815 |
| 8086:9dfc | 103c:8518 | Intel      | Cannon Point-LP Integrate... | 4     | intel_i... | 64C5568456 |
| 8086:9dfc | 103c:8548 | Intel      | Cannon Point-LP Integrate... | 4     | intel_i... | D862548439 |
| 8086:9dfc | 103c:857f | Intel      | Cannon Point-LP Integrate... | 4     | intel_i... | DD643D4C19 |
| 8086:9dfc | 103c:85c8 | Intel      | Cannon Point-LP Integrate... | 4     | intel_i... | 1649B0B654 |
| 8086:9dfc | 103c:85cd | Intel      | Cannon Point-LP Integrate... | 4     | intel_i... | E7DCDD4B39 |
| 8086:a0fc | 1028:09de | Intel      | Tiger Lake-LP Integrated ... | 4     | intel_i... | 5BF274A8E3 |
| 8086:a0fc | 1028:09df | Intel      | Tiger Lake-LP Integrated ... | 4     | intel_i... | 5B40E331B3 |
| 8086:a0fc | 103c:8709 | Intel      | Tiger Lake-LP Integrated ... | 4     | intel_i... | 6B850F8E6F |
| 8086:a0fc | 103c:87f4 | Intel      | Tiger Lake-LP Integrated ... | 4     | intel_i... | A0A4DFE970 |
| 8086:a37c | 103c:863e | Intel      | VROC Virtual Controller      | 4     | intel_i... | B47C4EF32E |
| 8086:02fc | 1028:0960 | Intel      | Comet Lake Integrated Sen... | 3     | intel_i... | F7AB576C61 |
| 8086:02fc | 103c:876d | Intel      | Comet Lake Integrated Sen... | 3     | intel_i... | 502CD63C0F |
| 8086:02fc | 8086:7270 | Intel      | Comet Lake Integrated Sen... | 3     | intel_i... | EE715DE644 |
| 8086:34fc | 103c:875b | Intel      | Ice Lake-LP Integrated Se... | 3     | intel_i... | 7490F0847D |
| 8086:9d3d | 1028:07aa | Intel      | Sunrise Point-LP Active M... | 3     | serial     | 5492FDD780 |
| 8086:9d3d | 103c:8438 | Intel      | Sunrise Point-LP Active M... | 3     | serial     | 633CDE303A |
| 8086:9de3 | 1028:08e2 | Intel      | Cannon Point-LP Keyboard ... | 3     | serial     | B015C22CFB |
| 8086:9dfc | 1028:0895 | Intel      | Cannon Point-LP Integrate... | 3     | intel_i... | 8E4E4194ED |
| 8086:9dfc | 1028:0896 | Intel      | Cannon Point-LP Integrate... | 3     | intel_i... | 4F9EBC7CD4 |
| 8086:9dfc | 1028:089f | Intel      | Cannon Point-LP Integrate... | 3     | intel_i... | DDC277B9F6 |
| 8086:9dfc | 1028:0907 | Intel      | Cannon Point-LP Integrate... | 3     | intel_i... | B6EB2D9514 |
| 8086:9dfc | 1028:0908 | Intel      | Cannon Point-LP Integrate... | 3     | intel_i... | C086BA0897 |
| 8086:9dfc | 103c:850d | Intel      | Cannon Point-LP Integrate... | 3     | intel_i... | 987181B525 |
| 8086:9dfc | 103c:85c5 | Intel      | Cannon Point-LP Integrate... | 3     | intel_i... | D2D2EB910A |
| 8086:9dfc | 103c:8637 | Intel      | Cannon Point-LP Integrate... | 3     | intel_i... | F30D3F55AD |
| 8086:a0fc | 103c:8825 | Intel      | Tiger Lake-LP Integrated ... | 3     | intel_i... | 7FC1E5873C |
| 8086:a0fc | 17aa:3801 | Intel      | Tiger Lake-LP Integrated ... | 3     | intel_i... | B27B2EACEE |
| 8086:a37c | 103c:844f | Intel      | VROC Virtual Controller      | 3     | intel_i... | 2668A6580A |
| 8086:a37c | 17aa:3803 | Intel      | VROC Virtual Controller      | 3     | intel_i... | F1C4AE114C |
| 8086:02fc | 1028:09c6 | Intel      | Comet Lake Integrated Sen... | 2     | intel_i... | B776BEB710 |
| 8086:02fc | 103c:8671 | Intel      | Comet Lake Integrated Sen... | 2     | intel_i... | 74D939AB7B |
| 8086:02fc | 103c:86e5 | Intel      | Comet Lake Integrated Sen... | 2     | intel_i... | FD2D87232F |
| 8086:02fc | 103c:8725 | Intel      | Comet Lake Integrated Sen... | 2     | intel_i... | C617B180A8 |
| 8086:02fc | 17aa:22ad | Intel      | Comet Lake Integrated Sen... | 2     | intel_i... | 8E3E2A94C3 |
| 8086:9d3d | 103c:8470 | Intel      | Sunrise Point-LP Active M... | 2     | serial     | EF7445EB15 |
| 8086:9de3 | 1028:08b6 | Intel      | Cannon Point-LP Keyboard ... | 2     | serial     | ADBA0A4782 |
| 8086:9de3 | 103c:861f | Intel      | Cannon Point-LP Keyboard ... | 2     | serial     | CE851E2475 |
| 8086:9dfc | 103c:85e6 | Intel      | Cannon Point-LP Integrate... | 2     | intel_i... | 0A7C046DCE |
| 8086:a0fc | 1028:0a37 | Intel      | Tiger Lake-LP Integrated ... | 2     | intel_i... | C5856B1EA0 |
| 8086:a37c | 103c:8519 | Intel      | VROC Virtual Controller      | 2     | intel_i... | AED071D8CE |
| 8086:02e3 | 1028:099e | Intel      | Comet Lake PCH-LP Keyboar... | 1     | serial     | 7F030D7425 |
| 8086:02e3 | 1028:09c6 | Intel      | Comet Lake PCH-LP Keyboar... | 1     | serial     | B776BEB710 |
| 8086:02e3 | 103c:8725 | Intel      | Comet Lake PCH-LP Keyboar... | 1     | serial     | 1DAC3FA543 |
| 8086:02e3 | 17aa:22ad | Intel      | Comet Lake PCH-LP Keyboar... | 1     | serial     | BFE30DECD3 |
| 8086:02fc | 1028:099e | Intel      | Comet Lake Integrated Sen... | 1     | intel_i... | 7F030D7425 |
| 8086:02fc | 1028:09da | Intel      | Comet Lake Integrated Sen... | 1     | intel_i... | 2BE9BAE979 |
| 8086:02fc | 103c:8670 | Intel      | Comet Lake Integrated Sen... | 1     | intel_i... | 9212F9DB05 |
| 8086:02fc | 103c:8672 | Intel      | Comet Lake Integrated Sen... | 1     | intel_i... | 8E5E4CCD9B |
| 8086:02fc | 103c:86ec | Intel      | Comet Lake Integrated Sen... | 1     | intel_i... | 483D4785B1 |
| 8086:02fc | 1043:1f61 | Intel      | Comet Lake Integrated Sen... | 1     | intel_i... | 3D10849F6E |
| 8086:06fc | 103c:86e7 | Intel      | 400 Series Chipset Family... | 1     | intel_i... | 46AFFA13CE |
| 8086:06fc | 17aa:3801 | Intel      | 400 Series Chipset Family... | 1     | intel_i... | 25166EAADD |
| 8086:34fc | 1028:09dc | Intel      | Ice Lake-LP Integrated Se... | 1     | intel_i... | 2758011D5E |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15e4 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Senso... | 71    | amd_sfh    | 64A9E43743 |
| 8086:9d31 | 17aa:3830 | Intel      | Sunrise Point-LP Thermal ... | 36    | intel_p... | 44E586277C |
| 8086:9d60 | 17aa:3837 | Intel      | Sunrise Point-LP Serial I... | 36    | intel_l... | 44E586277C |
| 8086:9d61 | 17aa:3836 | Intel      | Sunrise Point-LP Serial I... | 36    | intel_l... | 44E586277C |
| 8086:9d62 | 17aa:3809 | Intel      | Sunrise Point-LP Serial I... | 36    | intel_l... | 44E586277C |
| 8086:02f9 | 17aa:3804 | Intel      | Comet Lake Thermal Subsytem  | 28    | intel_p... | F72E765EF0 |
| 8086:1903 | 17aa:3832 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 28    | process... | F72E765EF0 |
| 1022:15e4 | 103c:876f | AMD        | Raven/Raven2/Renoir Senso... | 27    | amd_sfh    | 08B513769D |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | intel_l... | 378291C3E0 |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | intel_l... | 378291C3E0 |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | intel_l... | 378291C3E0 |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | intel_l... | 378291C3E0 |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | intel_l... | 378291C3E0 |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | intel_l... | 378291C3E0 |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | intel_l... | 378291C3E0 |
| 1022:15e4 | 103c:876e | AMD        | Raven/Raven2/Renoir Senso... | 26    | amd_sfh    | F77E2EBB10 |
| 8086:1903 | 103c:83b9 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 24    | process... | 2C533BE257 |
| 8086:5a8c |           | Intel      | Atom/Celeron/Pentium Dyna... | 24    | process... | 378291C3E0 |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 24    | intel_l... | 378291C3E0 |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 24    | intel_l... | 378291C3E0 |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 24    | intel_l... | 378291C3E0 |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 24    | intel_l... | 378291C3E0 |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 24    | intel_l... | 378291C3E0 |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 24    | intel_l... | 378291C3E0 |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 24    | intel_l... | 378291C3E0 |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 24    | intel_l... | 378291C3E0 |
| 8086:9d27 | 103c:83b9 | Intel      | Sunrise Point-LP Serial I... | 24    | intel_l... | 2C533BE257 |
| 8086:9d29 | 103c:83b9 | Intel      | Sunrise Point-LP Serial I... | 24    | intel_l... | 2C533BE257 |
| 8086:9d31 | 103c:83b9 | Intel      | Sunrise Point-LP Thermal ... | 24    | intel_p... | 2C533BE257 |
| 8086:9d60 | 103c:83b9 | Intel      | Sunrise Point-LP Serial I... | 24    | intel_l... | 2C533BE257 |
| 8086:1903 | 103c:8514 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 23    | process... | 2352CAA9CF |
| 8086:9d66 | 17aa:3810 | Intel      | Sunrise Point-LP Serial I... | 23    | intel_l... | CF93488B90 |
| 8086:9df9 | 103c:8514 | Intel      | Cannon Point-LP Thermal C... | 23    | intel_p... | 2352CAA9CF |
| 8086:1903 | 17aa:3829 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 22    | process... | CD156B08D8 |
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 22    | process... | 1866D29174 |
| 8086:9df9 | 17aa:380a | Intel      | Cannon Point-LP Thermal C... | 22    | intel_p... | CD156B08D8 |
| 8086:1903 | 17aa:2292 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 21    | process... | 32CA60DCEA |
| 8086:8a03 | 17aa:3809 | Intel      | Ice Lake Dynamic Platform... | 21    | process... | 7C965E245C |
| 8086:9d27 |           | Intel      | Sunrise Point-LP Serial I... | 21    | intel_lpss | CE8E9AF30D |
| 8086:318c | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | process... | 38E5F73567 |
| 8086:31ac | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | intel_l... | 38E5F73567 |
| 8086:31ae | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | intel_l... | 38E5F73567 |
| 8086:31b0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | intel_l... | 38E5F73567 |
| 8086:31b2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | intel_l... | 38E5F73567 |
| 8086:31b4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | intel_l... | 38E5F73567 |
| 8086:31b6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | intel_l... | 38E5F73567 |
| 8086:31b8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | intel_l... | 38E5F73567 |
| 8086:31ba | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | intel_l... | 38E5F73567 |
| 8086:31bc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | intel_l... | 38E5F73567 |
| 8086:31be | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | intel_l... | 38E5F73567 |
| 8086:31c0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | intel_l... | 38E5F73567 |
| 8086:31c2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | intel_l... | 38E5F73567 |
| 8086:31c4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | intel_l... | 38E5F73567 |
| 8086:31c6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | intel_l... | 38E5F73567 |
| 8086:31ee | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | intel_l... | 38E5F73567 |
| 8086:9d29 |           | Intel      | Sunrise Point-LP Serial I... | 20    | intel_lpss | CE8E9AF30D |
| 8086:1903 | 17aa:3819 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 19    | process... | 1A0B1FFDBD |
| 8086:9d31 | 17aa:2238 | Intel      | Sunrise Point-LP Thermal ... | 19    | intel_p... | D878C63FE4 |
| 8086:9d31 | 17aa:3854 | Intel      | Sunrise Point-LP Thermal ... | 19    | intel_p... | 1A0B1FFDBD |
| 8086:9d60 | 17aa:3859 | Intel      | Sunrise Point-LP Serial I... | 19    | intel_l... | 1A0B1FFDBD |
| 8086:9d61 | 17aa:3855 | Intel      | Sunrise Point-LP Serial I... | 19    | intel_l... | 1A0B1FFDBD |
| 8086:1903 | 17aa:381c | Intel      | Xeon E3-1200 v5/E3-1500 v... | 17    | process... | 6E045B787A |
| 8086:8a03 | 1028:08b0 | Intel      | Ice Lake Dynamic Platform... | 17    | process... | 6B27A727BE |
| 8086:9d31 | 17aa:385a | Intel      | Sunrise Point-LP Thermal ... | 17    | intel_p... | 6E045B787A |
| 8086:9d60 | 17aa:385f | Intel      | Sunrise Point-LP Serial I... | 17    | intel_l... | 6E045B787A |
| 8086:9d61 | 17aa:3857 | Intel      | Sunrise Point-LP Serial I... | 17    | intel_l... | 6E045B787A |
| 8086:9d63 | 17aa:3809 | Intel      | Sunrise Point-LP Serial I... | 17    | intel_l... | 6E045B787A |
| 8086:9df9 | 17aa:2292 | Intel      | Cannon Point-LP Thermal C... | 16    | intel_p... | 3795F3DF87 |
| 8086:8a03 | 17aa:3802 | Intel      | Ice Lake Dynamic Platform... | 15    | process... | 2E19A058F9 |
| 8086:1903 | 103c:830f | Intel      | Xeon E3-1200 v5/E3-1500 v... | 14    | process... | B6BC75336E |
| 8086:9d27 | 17aa:381d | Intel      | Sunrise Point-LP Serial I... | 14    | intel_l... | 15C0F31B91 |
| 8086:9d31 | 103c:830f | Intel      | Sunrise Point-LP Thermal ... | 14    | intel_p... | B6BC75336E |
| 8086:9d31 | 17aa:3819 | Intel      | Sunrise Point-LP Thermal ... | 14    | intel_p... | 15C0F31B91 |
| 8086:9d60 | 103c:830f | Intel      | Sunrise Point-LP Serial I... | 14    | intel_l... | B6BC75336E |
| 8086:9d60 | 17aa:381d | Intel      | Sunrise Point-LP Serial I... | 14    | intel_l... | 15C0F31B91 |
| 8086:9d61 | 103c:830f | Intel      | Sunrise Point-LP Serial I... | 14    | intel_l... | B6BC75336E |
| 8086:9d61 | 17aa:381d | Intel      | Sunrise Point-LP Serial I... | 14    | intel_l... | 15C0F31B91 |
| 8086:02f9 | 17aa:3806 | Intel      | Comet Lake Thermal Subsytem  | 13    | intel_p... | 5BDCB41FEE |
| 8086:1903 | 103c:83bb | Intel      | Xeon E3-1200 v5/E3-1500 v... | 13    | proc_th... | BA09E3B76F |
| 8086:1903 | 103c:8486 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 13    | process... | B149A04EE8 |
| 8086:1903 | 17aa:3806 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 13    | process... | 5BDCB41FEE |
| 8086:1903 | 17aa:3807 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 13    | process... | 2F1BC93921 |
| 8086:9a03 | 1028:0a05 | Intel      | TigerLake-LP Dynamic Tuni... | 13    | process... | 71B5E3C825 |
| 8086:9a0d | 1028:0a05 | Intel      | Tigerlake Telemetry Aggre... | 13    | intel_pmt  | 71B5E3C825 |
| 8086:9d27 | 103c:8486 | Intel      | Sunrise Point-LP Serial I... | 13    | intel_l... | B149A04EE8 |
| 8086:9d27 | 17aa:3833 | Intel      | Sunrise Point-LP Serial I... | 13    | intel_l... | 2F1BC93921 |
| 8086:9d31 | 103c:827d | Intel      | Sunrise Point-LP Thermal ... | 13    | intel_p... | 51178C1953 |
| 8086:9d31 | 103c:8486 | Intel      | Sunrise Point-LP Thermal ... | 13    | intel_p... | B149A04EE8 |
| 8086:9d31 | 17aa:380b | Intel      | Sunrise Point-LP Thermal ... | 13    | intel_p... | 1E4A851AD2 |
| 8086:9d31 | 17aa:3831 | Intel      | Sunrise Point-LP Thermal ... | 13    | intel_p... | 2F1BC93921 |
| 8086:9d60 | 103c:827d | Intel      | Sunrise Point-LP Serial I... | 13    | intel_l... | 51178C1953 |
| 8086:9d60 | 103c:8486 | Intel      | Sunrise Point-LP Serial I... | 13    | intel_l... | B149A04EE8 |
| 8086:9d60 | 17aa:3811 | Intel      | Sunrise Point-LP Serial I... | 13    | intel_l... | 1E4A851AD2 |
| 8086:9d60 | 17aa:3836 | Intel      | Sunrise Point-LP Serial I... | 13    | intel_l... | 2F1BC93921 |
| 8086:9d61 | 103c:827d | Intel      | Sunrise Point-LP Serial I... | 13    | intel_l... | 51178C1953 |
| 8086:9d61 | 103c:8486 | Intel      | Sunrise Point-LP Serial I... | 13    | intel_l... | B149A04EE8 |
| 8086:9d61 | 17aa:3811 | Intel      | Sunrise Point-LP Serial I... | 13    | intel_l... | 1E4A851AD2 |
| 8086:9d61 | 17aa:3837 | Intel      | Sunrise Point-LP Serial I... | 13    | intel_l... | 2F1BC93921 |
| 8086:9d62 | 103c:827d | Intel      | Sunrise Point-LP Serial I... | 13    | intel_l... | 51178C1953 |
| 8086:9d62 | 103c:8486 | Intel      | Sunrise Point-LP Serial I... | 13    | intel_l... | B149A04EE8 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:790b | 17aa:382e | AMD        | FCH SMBus Controller         | 46    | i2c_pii... | 64A9E43743 |
| 8086:9d23 | 17aa:3840 | Intel      | Sunrise Point-LP SMBus       | 36    | i2c_i801   | 44E586277C |
| 8086:02a3 | 17aa:3803 | Intel      | Comet Lake PCH-LP SMBus H... | 28    | i2c_i801   | F72E765EF0 |
| 1022:790b | 103c:876f | AMD        | FCH SMBus Controller         | 27    | i2c_piix4  | 08B513769D |
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | i2c_i801   | 378291C3E0 |
| 1022:790b | 103c:876e | AMD        | FCH SMBus Controller         | 26    | i2c_piix4  | F77E2EBB10 |
| 8086:9d23 | 103c:83b9 | Intel      | Sunrise Point-LP SMBus       | 24    | i2c_i801   | 2C533BE257 |
| 8086:9da3 | 103c:8514 | Intel      | Cannon Point-LP SMBus Con... | 23    | i2c_i801   | 2352CAA9CF |
| 1022:790b | 103c:85dd | AMD        | FCH SMBus Controller         | 22    | i2c_pii... | A93B2565DF |
| 8086:9da3 | 17aa:3812 | Intel      | Cannon Point-LP SMBus Con... | 22    | i2c_i801   | CD156B08D8 |
| 8086:34a3 | 17aa:3813 | Intel      | Ice Lake-LP SMBus Controller | 21    | i2c_i801   | 7C965E245C |
| 8086:31d4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | i2c_i801   | 38E5F73567 |
| 8086:9d23 | 17aa:2238 | Intel      | Sunrise Point-LP SMBus       | 19    | i2c_i801   | D878C63FE4 |
| 8086:9d23 | 17aa:3862 | Intel      | Sunrise Point-LP SMBus       | 19    | i2c_i801   | 1A0B1FFDBD |
| 1022:790b | 103c:85de | AMD        | FCH SMBus Controller         | 17    | i2c_piix4  | 9E86C8EDE5 |
| 8086:34a3 | 1028:08b0 | Intel      | Ice Lake-LP SMBus Controller | 17    | i2c_i801   | 6B27A727BE |
| 8086:9d23 | 17aa:3867 | Intel      | Sunrise Point-LP SMBus       | 17    | i2c_i801   | 6E045B787A |
| 1022:790b | 17aa:3818 | AMD        | FCH SMBus Controller         | 16    | i2c_pii... | 57651669E3 |
| 8086:9da3 | 17aa:2292 | Intel      | Cannon Point-LP SMBus Con... | 16    | i2c_i801   | 3795F3DF87 |
| 1022:790b | 103c:83c6 | AMD        | FCH SMBus Controller         | 15    | i2c_piix4  | 168717D052 |
| 8086:34a3 | 17aa:3811 | Intel      | Ice Lake-LP SMBus Controller | 15    | i2c_i801   | 2E19A058F9 |
| 1022:790b | 103c:8496 | AMD        | FCH SMBus Controller         | 14    | i2c_piix4  | 8A63E2E055 |
| 8086:9d23 | 103c:830f | Intel      | Sunrise Point-LP SMBus       | 14    | i2c_i801   | B6BC75336E |
| 8086:9d23 | 17aa:3823 | Intel      | Sunrise Point-LP SMBus       | 14    | i2c_i801   | 15C0F31B91 |
| 1022:790b | 103c:8497 | AMD        | FCH SMBus Controller         | 13    | piix4_s... | 2910A4173E |
| 8086:02a3 | 17aa:3806 | Intel      | Comet Lake PCH-LP SMBus H... | 13    | i2c_i801   | 5BDCB41FEE |
| 8086:9d23 | 103c:827d | Intel      | Sunrise Point-LP SMBus       | 13    | i2c_i801   | 51178C1953 |
| 8086:9d23 | 103c:8486 | Intel      | Sunrise Point-LP SMBus       | 13    | i2c_i801   | B149A04EE8 |
| 8086:9d23 | 17aa:3811 | Intel      | Sunrise Point-LP SMBus       | 13    | i2c_i801   | 1E4A851AD2 |
| 8086:9d23 | 17aa:383c | Intel      | Sunrise Point-LP SMBus       | 13    | i2c_i801   | 2F1BC93921 |
| 8086:a0a3 | 1028:0a05 | Intel      | Tiger Lake-LP SMBus Contr... | 13    | i2c_i801   | 71B5E3C825 |
| 8086:a123 | 103c:83bb | Intel      | 100 Series/C230 Series Ch... | 13    | i801_smbus | BA09E3B76F |
| 8086:9d23 | 103c:827e | Intel      | Sunrise Point-LP SMBus       | 12    | i2c_i801   | B3CFF29C2E |
| 8086:9d23 | 17aa:2259 | Intel      | Sunrise Point-LP SMBus       | 12    | i2c_i801   | C96223F666 |
| 8086:a123 | 17aa:3810 | Intel      | 100 Series/C230 Series Ch... | 12    | i2c_i801   | A9626F1580 |
| 1022:790b | 103c:8735 | AMD        | FCH SMBus Controller         | 11    | i2c_piix4  | F36EA99568 |
| 8086:9d23 | 1028:077a | Intel      | Sunrise Point-LP SMBus       | 11    | i2c_i801   | C0A9C9443B |
| 8086:9d23 | 17aa:224e | Intel      | Sunrise Point-LP SMBus       | 11    | i2c_i801   | B866426527 |
| 8086:9d23 | 103c:8488 | Intel      | Sunrise Point-LP SMBus       | 10    | i2c_i801   | 7B7C2317D8 |
| 8086:9d23 | 1043:1ab0 | Intel      | Sunrise Point-LP SMBus       | 10    | i801_smbus | CE8E9AF30D |
| 8086:9d23 | 17aa:3805 | Intel      | Sunrise Point-LP SMBus       | 10    | i2c_i801   | B58AABDE5F |
| 8086:9d23 | 17aa:380b | Intel      | Sunrise Point-LP SMBus       | 10    | i2c_i801   | A4D6F3CCE4 |
| 8086:9d23 | 17aa:385f | Intel      | Sunrise Point-LP SMBus       | 10    | i2c_i801   | 384114E0B4 |
| 8086:02a3 | 17aa:5078 | Intel      | Comet Lake PCH-LP SMBus H... | 9     | i2c_i801   | 7C78B71A99 |
| 8086:2292 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 9     | i2c_i801   | 8638532EEB |
| 8086:9d23 | 103c:80d1 | Intel      | Sunrise Point-LP SMBus       | 9     | i2c_i801   | 629D516666 |
| 8086:9d23 | 103c:81a1 | Intel      | Sunrise Point-LP SMBus       | 9     | i2c_i801   | B37CBA5DF4 |
| 8086:9da3 | 1028:0894 | Intel      | Cannon Point-LP SMBus Con... | 9     | i2c_i801   | B07A0CF706 |
| 8086:a0a3 | 1028:09ff | Intel      | Tiger Lake-LP SMBus Contr... | 9     | i2c_i801   | AD3C1FB56A |
| 8086:a0a3 | 17aa:381a | Intel      | Tiger Lake-LP SMBus Contr... | 9     | i2c_i801   | 13AC1F05DD |
| 8086:a123 | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 9     | i2c_i801   | C28F77B8F1 |
| 1022:790b | 1043:1921 | AMD        | FCH SMBus Controller         | 8     | piix4_s... | 824BB881D7 |
| 8086:02a3 | 1028:095d | Intel      | Comet Lake PCH-LP SMBus H... | 8     | i2c_i801   | B5682ADC9E |
| 8086:9d23 | 103c:8438 | Intel      | Sunrise Point-LP SMBus       | 8     | i2c_i801   | 633CDE303A |
| 8086:02a3 | 1028:09cd | Intel      | Comet Lake PCH-LP SMBus H... | 7     | i2c_i801   | BC7C58F248 |
| 8086:02a3 | 103c:863f | Intel      | Comet Lake PCH-LP SMBus H... | 7     | i2c_i801   | 638C4207CE |
| 8086:02a3 | 103c:86b1 | Intel      | Comet Lake PCH-LP SMBus H... | 7     | i2c_i801   | 093BEED213 |
| 8086:02a3 | 103c:86b2 | Intel      | Comet Lake PCH-LP SMBus H... | 7     | i2c_i801   | 42A03DCD82 |
| 8086:34a3 | 103c:86f9 | Intel      | Ice Lake-LP SMBus Controller | 7     | i2c_i801   | A18B247E3D |
| 8086:9d23 | 17aa:506d | Intel      | Sunrise Point-LP SMBus       | 7     | i2c_i801   | 847655CB40 |
| 8086:9da3 | 103c:85c4 | Intel      | Cannon Point-LP SMBus Con... | 7     | i2c_i801   | 9BCBAF17E9 |
| 8086:9da3 | 103c:861f | Intel      | Cannon Point-LP SMBus Con... | 7     | i2c_i801   | D284325FCF |
| 8086:02a3 | 103c:866e | Intel      | Comet Lake PCH-LP SMBus H... | 6     | i2c_i801   | 22FAA280E3 |
| 8086:0f12 | 103c:802b | Intel      | Atom Processor E3800 Seri... | 6     | i2c_i801   | 4EDDB18ED9 |
| 8086:9d23 | 1025:1176 | Intel      | Sunrise Point-LP SMBus       | 6     | i2c_i801   | 566FA6B1D5 |
| 8086:9d23 | 103c:8484 | Intel      | Sunrise Point-LP SMBus       | 6     | i801_smbus | D46010346C |
| 8086:9d23 | 1043:1b00 | Intel      | Sunrise Point-LP SMBus       | 6     | i801_smbus | BC2368FBE6 |
| 8086:9d23 | 1043:1c90 | Intel      | Sunrise Point-LP SMBus       | 6     | i2c_i801   | AED32F7A4D |
| 8086:9d23 | 17aa:2237 | Intel      | Sunrise Point-LP SMBus       | 6     | i801_smbus | 2A0ECA4670 |
| 8086:9d23 | 17aa:3848 | Intel      | Sunrise Point-LP SMBus       | 6     | i2c_i801   | CF93488B90 |
| 8086:9d23 | 17aa:3860 | Intel      | Sunrise Point-LP SMBus       | 6     | i2c_i801   | 570666D7D6 |
| 8086:9d23 | 1ae0:006b | Intel      | Sunrise Point-LP SMBus       | 6     | i801_smbus | CBC1BB3811 |
| 8086:9da3 | 1028:089e | Intel      | Cannon Point-LP SMBus Con... | 6     | i2c_i801   | C6692154A1 |
| 8086:a0a3 | 1028:09dd | Intel      | Tiger Lake-LP SMBus Contr... | 6     | i2c_i801   | 6BFDD9FDA4 |
| 1022:790b | 103c:81aa | AMD        | FCH SMBus Controller         | 5     | i2c_piix4  | 633D386331 |
| 8086:02a3 | 1028:0950 | Intel      | Comet Lake PCH-LP SMBus H... | 5     | i2c_i801   | 9DD76AE820 |
| 8086:02a3 | 17aa:2292 | Intel      | Comet Lake PCH-LP SMBus H... | 5     | i2c_i801   | 32CA60DCEA |
| 8086:02a3 | 17aa:22be | Intel      | Comet Lake PCH-LP SMBus H... | 5     | i2c_i801   | E40B11DCA2 |
| 8086:02a3 | 17aa:3816 | Intel      | Comet Lake PCH-LP SMBus H... | 5     | i2c_i801   | D9D123FF85 |
| 8086:5ad4 | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 5     | i2c_i801   | 98851C034C |
| 8086:9d23 | 1028:07eb | Intel      | Sunrise Point-LP SMBus       | 5     | i2c_i801   | E4FFC93C6A |
| 8086:9d23 | 103c:81a9 | Intel      | Sunrise Point-LP SMBus       | 5     | i2c_i801   | 0BB3F77C75 |
| 8086:9d23 | 103c:81ad | Intel      | Sunrise Point-LP SMBus       | 5     | i2c_i801   | CE728E8715 |
| 8086:9d23 | 103c:827f | Intel      | Sunrise Point-LP SMBus       | 5     | i801_smbus | BD5BDFD31F |
| 8086:9d23 | 103c:8313 | Intel      | Sunrise Point-LP SMBus       | 5     | i801_smbus | DCD840E8A2 |
| 8086:9d23 | 103c:8483 | Intel      | Sunrise Point-LP SMBus       | 5     | i2c_i801   | C41A1DE997 |
| 8086:9d23 | 103c:8487 | Intel      | Sunrise Point-LP SMBus       | 5     | i2c_i801   | CA8936A74C |
| 8086:9d23 | 1043:14f0 | Intel      | Sunrise Point-LP SMBus       | 5     | i2c_i801   | 93B1606116 |
| 8086:9d23 | 1043:1dc0 | Intel      | Sunrise Point-LP SMBus       | 5     | i2c_i801   | DF55EA30E7 |
| 8086:9d23 | 17aa:504c | Intel      | Sunrise Point-LP SMBus       | 5     | i2c_i801   | 4983586FE5 |
| 8086:9d23 | 17aa:506c | Intel      | Sunrise Point-LP SMBus       | 5     | i2c_i801   | 6C4ABD0606 |
| 8086:9da3 | 1028:08b6 | Intel      | Cannon Point-LP SMBus Con... | 5     | i801_smbus | B0722E1B57 |
| 8086:9da3 | 103c:85e7 | Intel      | Cannon Point-LP SMBus Con... | 5     | i2c_i801   | 169477DE3F |
| 8086:9da3 | 1043:1541 | Intel      | Cannon Point-LP SMBus Con... | 5     | i2c_i801   | 8EFC8CAADA |
| 8086:9da3 | 1043:19d1 | Intel      | Cannon Point-LP SMBus Con... | 5     | i801_smbus | 9054D4EBEB |
| 8086:9da3 | 17aa:2294 | Intel      | Cannon Point-LP SMBus Con... | 5     | i2c_i801   | 09DC5430DA |
| 8086:9da3 | 17aa:5077 | Intel      | Cannon Point-LP SMBus Con... | 5     | i2c_i801   | 87DA71BBB9 |
| 8086:a0a3 | 103c:87f7 | Intel      | Tiger Lake-LP SMBus Contr... | 5     | i2c_i801   | 48A0452D0B |
| 8086:a0a3 | 17aa:3806 | Intel      | Tiger Lake-LP SMBus Contr... | 5     | i2c_i801   | 0B7B90BB5D |
| 8086:a323 | 17aa:3805 | Intel      | Cannon Lake PCH SMBus Con... | 5     | i2c_i801   | 78960B975F |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:1637 | 1002:1637 | AMD        | Renoir Radeon High Defini... | 49    | snd_hda... | 64A9E43743 |
| 1022:15e3 | 17aa:381c | AMD        | Family 17h (Models 10h-1f... | 46    | snd_hda... | 64A9E43743 |
| 8086:9d71 | 17aa:3808 | Intel      | Sunrise Point-LP HD Audio    | 36    | snd_hda... | 44E586277C |
| 8086:02c8 | 17aa:3803 | Intel      | Comet Lake PCH-LP cAVS       | 28    | sof_aud... | F72E765EF0 |
| 1002:1637 | 103c:876f | AMD        | Renoir Radeon High Defini... | 27    | snd_hda... | 08B513769D |
| 1022:15e3 | 103c:876f | AMD        | Family 17h (Models 10h-1f... | 27    | snd_hda... | 08B513769D |
| 1002:1637 | 103c:876e | AMD        | Renoir Radeon High Defini... | 26    | snd_hda... | F77E2EBB10 |
| 1022:15e3 | 103c:876e | AMD        | Family 17h (Models 10h-1f... | 26    | snd_hda... | F77E2EBB10 |
| 8086:9d71 | 103c:83b9 | Intel      | Sunrise Point-LP HD Audio    | 24    | snd_hda... | 2C533BE257 |
| 8086:9dc8 | 103c:8514 | Intel      | Cannon Point-LP High Defi... | 23    | snd_hda... | 2352CAA9CF |
| 1002:15de | 103c:85dd | AMD        | Raven/Raven2/Fenghuang HD... | 22    | snd_hda... | A93B2565DF |
| 1022:15e3 | 103c:85dd | AMD        | Family 17h (Models 10h-1f... | 22    | snd_hda... | A93B2565DF |
| 8086:9dc8 | 17aa:3814 | Intel      | Cannon Point-LP High Defi... | 22    | snd_hda... | CD156B08D8 |
| 8086:34c8 | 17aa:3811 | Intel      | Ice Lake-LP Smart Sound T... | 21    | snd_hda... | 7C965E245C |
| 8086:9d70 | 17aa:2238 | Intel      | Sunrise Point-LP HD Audio    | 19    | snd_hda... | D878C63FE4 |
| 8086:9d71 | 17aa:3829 | Intel      | Sunrise Point-LP HD Audio    | 19    | snd_hda... | 1A0B1FFDBD |
| 1002:15de | 103c:85de | AMD        | Raven/Raven2/Fenghuang HD... | 17    | snd_hda... | 9E86C8EDE5 |
| 1022:15e3 | 103c:85de | AMD        | Family 17h (Models 10h-1f... | 17    | snd_hda... | 9E86C8EDE5 |
| 8086:34c8 | 1028:08b0 | Intel      | Ice Lake-LP Smart Sound T... | 17    | snd_hda... | 6B27A727BE |
| 8086:9d71 | 17aa:3831 | Intel      | Sunrise Point-LP HD Audio    | 17    | snd_hda... | 6E045B787A |
| 1002:15de | 17aa:3803 | AMD        | Raven/Raven2/Fenghuang HD... | 16    | snd_hda... | 57651669E3 |
| 1022:15e3 | 17aa:380c | AMD        | Family 17h (Models 10h-1f... | 16    | snd_hda... | 57651669E3 |
| 8086:9dc8 | 17aa:2292 | Intel      | Cannon Point-LP High Defi... | 16    | snd_hda... | 3795F3DF87 |
| 1002:15de | 103c:83c6 | AMD        | Raven/Raven2/Fenghuang HD... | 15    | snd_hda... | 168717D052 |
| 1022:15e3 | 103c:83c6 | AMD        | Family 17h (Models 10h-1f... | 15    | snd_hda... | 168717D052 |
| 8086:34c8 | 17aa:382e | Intel      | Ice Lake-LP Smart Sound T... | 15    | snd_hda... | 2E19A058F9 |
| 1002:15de | 103c:8496 | AMD        | Raven/Raven2/Fenghuang HD... | 14    | snd_hda... | 8A63E2E055 |
| 1022:15e3 | 103c:8496 | AMD        | Family 17h (Models 10h-1f... | 14    | snd_hda... | 8A63E2E055 |
| 8086:5a98 | 1c6c:122a | Intel      | Celeron N3350/Pentium N42... | 14    | snd_hda... | 7332052765 |
| 8086:9d71 | 103c:830f | Intel      | Sunrise Point-LP HD Audio    | 14    | snd_hda... | B6BC75336E |
| 8086:9d71 | 17aa:3801 | Intel      | Sunrise Point-LP HD Audio    | 14    | snd_hda... | 15C0F31B91 |
| 1002:15de | 103c:8497 | AMD        | Raven/Raven2/Fenghuang HD... | 13    | snd_hda... | 2910A4173E |
| 1022:15e3 | 103c:8497 | AMD        | Family 17h (Models 10h-1f... | 13    | snd_hda... | 2910A4173E |
| 8086:02c8 | 17aa:3806 | Intel      | Comet Lake PCH-LP cAVS       | 13    | snd_hda... | 5BDCB41FEE |
| 8086:9d70 | 17aa:3801 | Intel      | Sunrise Point-LP HD Audio    | 13    | snd_hda... | 1E4A851AD2 |
| 8086:9d71 | 103c:827d | Intel      | Sunrise Point-LP HD Audio    | 13    | snd_hda... | 51178C1953 |
| 8086:9d71 | 103c:8486 | Intel      | Sunrise Point-LP HD Audio    | 13    | snd_hda... | B149A04EE8 |
| 8086:9d71 | 17aa:3809 | Intel      | Sunrise Point-LP HD Audio    | 13    | snd_hda... | 2F1BC93921 |
| 8086:a0c8 | 1028:0a05 | Intel      | Tiger Lake-LP Smart Sound... | 13    | snd_hda... | 71B5E3C825 |
| 8086:a171 | 103c:83bb | Intel      | CM238 HD Audio Controller    | 13    | snd_hda... | BA09E3B76F |
| 8086:9d71 | 103c:827e | Intel      | Sunrise Point-LP HD Audio    | 12    | snd_hda... | B3CFF29C2E |
| 8086:9d71 | 17aa:2259 | Intel      | Sunrise Point-LP HD Audio    | 12    | snd_hda... | C96223F666 |
| 8086:a171 | 17aa:380e | Intel      | CM238 HD Audio Controller    | 12    | snd_hda... | A9626F1580 |
| 1002:1637 | 103c:8735 | AMD        | Renoir Radeon High Defini... | 11    | snd_hda... | F36EA99568 |
| 1022:15e3 | 103c:8735 | AMD        | Family 17h (Models 10h-1f... | 11    | snd_hda... | F36EA99568 |
| 8086:9d71 | 1028:077a | Intel      | Sunrise Point-LP HD Audio    | 11    | snd_hda... | C0A9C9443B |
| 8086:9d71 | 17aa:224e | Intel      | Sunrise Point-LP HD Audio    | 11    | snd_hda... | B866426527 |
| 8086:9d71 | 1043:1ab0 | Intel      | Sunrise Point-LP HD Audio    | 10    | snd_hda... | CE8E9AF30D |
| 8086:9d71 | 17aa:3804 | Intel      | Sunrise Point-LP HD Audio    | 10    | snd_hda... | A4D6F3CCE4 |
| 8086:9d71 | 17aa:3806 | Intel      | Sunrise Point-LP HD Audio    | 10    | snd_hda... | B58AABDE5F |
| 8086:9d71 | 17aa:3827 | Intel      | Sunrise Point-LP HD Audio    | 10    | snd_hda... | 384114E0B4 |
| 8086:02c8 | 17aa:5078 | Intel      | Comet Lake PCH-LP cAVS       | 9     | snd_hda... | 7C78B71A99 |
| 8086:2284 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 9     | snd_hda... | 8638532EEB |
| 8086:3198 | 10ec:1194 | Intel      | Celeron/Pentium Silver Pr... | 9     | snd_hda... | 468B5A689D |
| 8086:9d70 | 103c:80d1 | Intel      | Sunrise Point-LP HD Audio    | 9     | snd_hda... | 629D516666 |
| 8086:9d70 | 103c:81a1 | Intel      | Sunrise Point-LP HD Audio    | 9     | snd_hda... | B37CBA5DF4 |
| 8086:9d71 | 103c:8488 | Intel      | Sunrise Point-LP HD Audio    | 9     | snd_hda... | 7B7C2317D8 |
| 8086:9dc8 | 1028:0894 | Intel      | Cannon Point-LP High Defi... | 9     | snd_hda... | B07A0CF706 |
| 8086:a0c8 | 1028:09ff | Intel      | Tiger Lake-LP Smart Sound... | 9     | snd_hda... | AD3C1FB56A |
| 8086:a0c8 | 17aa:3832 | Intel      | Tiger Lake-LP Smart Sound... | 9     | snd_hda... | 13AC1F05DD |
| 8086:a171 | 1028:080d | Intel      | CM238 HD Audio Controller    | 9     | snd_hda... | C28F77B8F1 |
| 1002:15de | 1002:15de | AMD        | Raven/Raven2/Fenghuang HD... | 8     | snd_hda... | 824BB881D7 |
| 1022:15e3 | 1043:1921 | AMD        | Family 17h (Models 10h-1f... | 8     | snd_hda... | 824BB881D7 |
| 8086:02c8 | 1028:095d | Intel      | Comet Lake PCH-LP cAVS       | 8     | snd_hda... | B5682ADC9E |
| 8086:9d71 | 103c:8438 | Intel      | Sunrise Point-LP HD Audio    | 8     | snd_hda... | 633CDE303A |
| 8086:9d71 | 1043:1b60 | Intel      | Sunrise Point-LP HD Audio    | 8     | snd_hda... | DF55EA30E7 |
| 8086:02c8 | 1028:09cd | Intel      | Comet Lake PCH-LP cAVS       | 7     | snd_hda... | BC7C58F248 |
| 8086:02c8 | 103c:863f | Intel      | Comet Lake PCH-LP cAVS       | 7     | snd_hda... | 638C4207CE |
| 8086:02c8 | 103c:86b1 | Intel      | Comet Lake PCH-LP cAVS       | 7     | snd_hda... | 093BEED213 |
| 8086:02c8 | 103c:86b2 | Intel      | Comet Lake PCH-LP cAVS       | 7     | snd_hda... | 42A03DCD82 |
| 8086:34c8 | 103c:86f9 | Intel      | Ice Lake-LP Smart Sound T... | 7     | snd_hda... | A18B247E3D |
| 8086:9d71 | 17aa:506d | Intel      | Sunrise Point-LP HD Audio    | 7     | snd_hda... | 847655CB40 |
| 8086:9dc8 | 103c:85c4 | Intel      | Cannon Point-LP High Defi... | 7     | snd_hda... | 9BCBAF17E9 |
| 8086:9dc8 | 103c:861f | Intel      | Cannon Point-LP High Defi... | 7     | snd_hda... | D284325FCF |
| 8086:02c8 | 103c:866e | Intel      | Comet Lake PCH-LP cAVS       | 6     | snd_hda... | 22FAA280E3 |
| 8086:0f04 | 103c:802b | Intel      | Atom Processor Z36xxx/Z37... | 6     | snd_hda... | 4EDDB18ED9 |
| 8086:34c8 | 1025:141f | Intel      | Ice Lake-LP Smart Sound T... | 6     | snd_hda... | AA8934716B |
| 8086:5a98 | 10ec:11ca | Intel      | Celeron N3350/Pentium N42... | 6     | snd_hda... | 58A89EDC96 |
| 8086:9d70 | 17aa:2237 | Intel      | Sunrise Point-LP HD Audio    | 6     | snd_hda... | 2A0ECA4670 |
| 8086:9d71 | 1025:1176 | Intel      | Sunrise Point-LP HD Audio    | 6     | snd_hda... | 566FA6B1D5 |
| 8086:9d71 | 103c:8484 | Intel      | Sunrise Point-LP HD Audio    | 6     | snd_hda... | D46010346C |
| 8086:9d71 | 1043:1c90 | Intel      | Sunrise Point-LP HD Audio    | 6     | snd_hda... | AED32F7A4D |
| 8086:9d71 | 17aa:381c | Intel      | Sunrise Point-LP HD Audio    | 6     | snd_hda... | CF93488B90 |
| 8086:9d71 | 17aa:3828 | Intel      | Sunrise Point-LP HD Audio    | 6     | snd_hda... | 570666D7D6 |
| 8086:9d71 | 1ae0:006b | Intel      | Sunrise Point-LP HD Audio    | 6     | snd_soc... | CBC1BB3811 |
| 8086:9dc8 | 1028:089e | Intel      | Cannon Point-LP High Defi... | 6     | snd_hda... | C6692154A1 |
| 8086:a0c8 | 1028:09dd | Intel      | Tiger Lake-LP Smart Sound... | 6     | snd_hda... | 6BFDD9FDA4 |
| 1002:9840 | 103c:81aa | AMD        | Kabini HDMI/DP Audio         | 5     | snd_hda... | 633D386331 |
| 1022:157a | 103c:81aa | AMD        | Family 15h (Models 60h-6f... | 5     | snd_hda... | 633D386331 |
| 8086:02c8 | 1028:0950 | Intel      | Comet Lake PCH-LP cAVS       | 5     | snd_hda... | 9DD76AE820 |
| 8086:02c8 | 17aa:2292 | Intel      | Comet Lake PCH-LP cAVS       | 5     | snd_hda... | 32CA60DCEA |
| 8086:02c8 | 17aa:22be | Intel      | Comet Lake PCH-LP cAVS       | 5     | snd_hda... | E40B11DCA2 |
| 8086:02c8 | 17aa:3815 | Intel      | Comet Lake PCH-LP cAVS       | 5     | snd_hda... | D9D123FF85 |
| 8086:5a98 | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 5     | snd_hda... | 98851C034C |
| 8086:9d70 | 17aa:504c | Intel      | Sunrise Point-LP HD Audio    | 5     | snd_hda... | 4983586FE5 |
| 8086:9d71 | 1028:07eb | Intel      | Sunrise Point-LP HD Audio    | 5     | snd_hda... | E4FFC93C6A |
| 8086:9d71 | 103c:81a9 | Intel      | Sunrise Point-LP HD Audio    | 5     | snd_hda... | 0BB3F77C75 |
| 8086:9d71 | 103c:81ad | Intel      | Sunrise Point-LP HD Audio    | 5     | snd_hda... | CE728E8715 |
| 8086:9d71 | 103c:827f | Intel      | Sunrise Point-LP HD Audio    | 5     | snd_hda... | BD5BDFD31F |
| 8086:9d71 | 103c:8313 | Intel      | Sunrise Point-LP HD Audio    | 5     | snd_hda... | DCD840E8A2 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 46    | ahci       | 64A9E43743 |
| 8086:02d3 | 17aa:3802 | Intel      | Comet Lake SATA AHCI Cont... | 28    | ahci       | F72E765EF0 |
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | ahci       | 378291C3E0 |
| 8086:9d03 | 17aa:383b | Intel      | Sunrise Point-LP SATA Con... | 24    | ahci       | 480F534F9F |
| 8086:31e3 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | ahci       | 38E5F73567 |
| 1022:7901 | 103c:876e | AMD        | FCH SATA Controller [AHCI... | 19    | ahci       | D071E37713 |
| 1022:7901 | 103c:876f | AMD        | FCH SATA Controller [AHCI... | 17    | ahci       | FBB923829D |
| 8086:9dd3 | 17aa:3806 | Intel      | Cannon Point-LP SATA Cont... | 16    | ahci       | AC5C64FED1 |
| 1022:7901 | 103c:83c6 | AMD        | FCH SATA Controller [AHCI... | 15    | ahci       | 168717D052 |
| 1022:7901 | 103c:8496 | AMD        | FCH SATA Controller [AHCI... | 14    | ahci       | 8A63E2E055 |
| 8086:9d03 | 103c:830f | Intel      | Sunrise Point-LP SATA Con... | 14    | ahci       | B6BC75336E |
| 8086:9d03 | 17aa:3822 | Intel      | Sunrise Point-LP SATA Con... | 14    | ahci       | 15C0F31B91 |
| 1022:7901 | 103c:8497 | AMD        | FCH SATA Controller [AHCI... | 13    | ahci       | 2910A4173E |
| 8086:9d03 | 17aa:380d | Intel      | Sunrise Point-LP SATA Con... | 13    | ahci       | 1E4A851AD2 |
| 8086:a103 | 103c:83bb | Intel      | HM170/QM170 Chipset SATA ... | 13    | ahci       | BA09E3B76F |
| 8086:9d03 | 103c:8486 | Intel      | Sunrise Point-LP SATA Con... | 12    | ahci       | B149A04EE8 |
| 8086:9d03 | 17aa:2238 | Intel      | Sunrise Point-LP SATA Con... | 12    | ahci       | D878C63FE4 |
| 8086:9d03 | 1043:1ab0 | Intel      | Sunrise Point-LP SATA Con... | 10    | ahci       | CE8E9AF30D |
| 8086:9d03 | 17aa:3810 | Intel      | Sunrise Point-LP SATA Con... | 10    | ahci       | A4D6F3CCE4 |
| 8086:9d03 | 103c:80d1 | Intel      | Sunrise Point-LP SATA Con... | 9     | ahci       | 629D516666 |
| 1022:7901 | 1043:1921 | AMD        | FCH SATA Controller [AHCI... | 8     | ahci       | 824BB881D7 |
| 8086:9d03 | 103c:8488 | Intel      | Sunrise Point-LP SATA Con... | 8     | ahci       | 7B7C2317D8 |
| 8086:02d3 | 1028:095d | Intel      | Comet Lake SATA AHCI Cont... | 7     | ahci       | B5682ADC9E |
| 8086:9d03 | 1025:1176 | Intel      | Sunrise Point-LP SATA Con... | 6     | ahci       | 566FA6B1D5 |
| 8086:9d03 | 103c:8484 | Intel      | Sunrise Point-LP SATA Con... | 6     | ahci       | D46010346C |
| 8086:9d03 | 1043:1b00 | Intel      | Sunrise Point-LP SATA Con... | 6     | ahci       | BC2368FBE6 |
| 1022:7901 | 103c:8735 | AMD        | FCH SATA Controller [AHCI... | 5     | ahci       | 055E0C7AAB |
| 1022:7904 | 103c:81aa | AMD        | FCH SATA Controller [AHCI... | 5     | ahci       | 633D386331 |
| 8086:5ae3 | 17aa:3803 | Intel      | Celeron N3350/Pentium N42... | 5     | ahci       | 98851C034C |
| 8086:9d03 | 1028:07eb | Intel      | Sunrise Point-LP SATA Con... | 5     | ahci       | E4FFC93C6A |
| 8086:9d03 | 103c:81a9 | Intel      | Sunrise Point-LP SATA Con... | 5     | ahci       | 0BB3F77C75 |
| 8086:9d03 | 103c:81ad | Intel      | Sunrise Point-LP SATA Con... | 5     | ahci       | CE728E8715 |
| 8086:9d03 | 103c:8313 | Intel      | Sunrise Point-LP SATA Con... | 5     | ahci       | DCD840E8A2 |
| 8086:9d03 | 103c:8483 | Intel      | Sunrise Point-LP SATA Con... | 5     | ahci       | C41A1DE997 |
| 8086:9d03 | 1043:14f0 | Intel      | Sunrise Point-LP SATA Con... | 5     | ahci       | 93B1606116 |
| 8086:9d03 | 17aa:2237 | Intel      | Sunrise Point-LP SATA Con... | 5     | ahci       | 2A0ECA4670 |
| 8086:9d03 | 17aa:504c | Intel      | Sunrise Point-LP SATA Con... | 5     | ahci       | 4983586FE5 |
| 1022:7901 | 1028:09e3 | AMD        | FCH SATA Controller [AHCI... | 4     | ahci       | 9ED34E6D16 |
| 1022:7904 | 17aa:3804 | AMD        | FCH SATA Controller [AHCI... | 4     | ahci       | DC41704AEC |
| 8086:02d3 | 17aa:380a | Intel      | Comet Lake SATA AHCI Cont... | 4     | ahci       | BA4EB365BC |
| 8086:9c83 | 103c:806e | Intel      | Wildcat Point-LP SATA Con... | 4     | ahci       | A8AA7A1D17 |
| 8086:9d03 | 103c:81a7 | Intel      | Sunrise Point-LP SATA Con... | 4     | ahci       | BC77E670A5 |
| 8086:9d03 | 103c:83c4 | Intel      | Sunrise Point-LP SATA Con... | 4     | ahci       | 3F62C672FB |
| 8086:9d03 | 103c:8487 | Intel      | Sunrise Point-LP SATA Con... | 4     | ahci       | CA8936A74C |
| 8086:9d03 | 103c:84d8 | Intel      | Sunrise Point-LP SATA Con... | 4     | ahci       | 03FE12C3CC |
| 8086:9d03 | 1043:1c90 | Intel      | Sunrise Point-LP SATA Con... | 4     | ahci       | A294ADAC80 |
| 8086:9dd3 | 1028:089e | Intel      | Cannon Point-LP SATA Cont... | 4     | ahci       | C6692154A1 |
| 1022:7901 | 103c:87a9 | AMD        | FCH SATA Controller [AHCI... | 3     | ahci       | F8C5A69D8E |
| 1022:7901 | 1043:11f2 | AMD        | FCH SATA Controller [AHCI... | 3     | ahci       | 974B8F73D1 |
| 8086:02d3 | 1028:0950 | Intel      | Comet Lake SATA AHCI Cont... | 3     | ahci       | BCEA6766BF |
| 8086:02d3 | 1028:0951 | Intel      | Comet Lake SATA AHCI Cont... | 3     | ahci       | 247867F57E |
| 8086:31e3 | 1025:1316 | Intel      | Celeron/Pentium Silver Pr... | 3     | ahci       | 19F4CA16E7 |
| 8086:9c83 | 103c:802d | Intel      | Wildcat Point-LP SATA Con... | 3     | ahci       | C1A4649FC7 |
| 8086:9d03 | 1025:120d | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 50D4915C8A |
| 8086:9d03 | 1028:0878 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 91F3D918A0 |
| 8086:9d03 | 103c:804e | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | B4E75E63FB |
| 8086:9d03 | 103c:81a1 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | CDA71D4B90 |
| 8086:9d03 | 103c:8310 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | D7D0DE8CF4 |
| 8086:9d03 | 1043:14c0 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 6B35C72C5A |
| 8086:9d03 | 1043:1c40 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | BD57C16BE8 |
| 8086:9d03 | 144d:c162 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 5DA835E33E |
| 8086:9dd3 | 1028:0895 | Intel      | Cannon Point-LP SATA Cont... | 3     | ahci       | 8E4E4194ED |
| 8086:9dd3 | 1028:0896 | Intel      | Cannon Point-LP SATA Cont... | 3     | ahci       | 4F9EBC7CD4 |
| 8086:9dd3 | 103c:85cd | Intel      | Cannon Point-LP SATA Cont... | 3     | ahci       | 802426D52D |
| 8086:9dd3 | 1043:1481 | Intel      | Cannon Point-LP SATA Cont... | 3     | ahci       | 30B72B97CB |
| 8086:9dd3 | 1043:19d1 | Intel      | Cannon Point-LP SATA Cont... | 3     | ahci       | 9054D4EBEB |
| 8086:a353 | 103c:844f | Intel      | Cannon Lake Mobile PCH SA... | 3     | ahci       | 2668A6580A |
| 1022:7904 | 103c:8311 | AMD        | FCH SATA Controller [AHCI... | 2     | ahci       | 514D46C27F |
| 8086:02d3 | 17aa:3804 | Intel      | Comet Lake SATA AHCI Cont... | 2     | ahci       | 3C0A5BE140 |
| 8086:22a3 | 103c:81a2 | Intel      | Atom/Celeron/Pentium Proc... | 2     | ahci       | 35DC79725B |
| 8086:31e3 | 1025:1293 | Intel      | Celeron/Pentium Silver Pr... | 2     | ahci       | 0A09D00B74 |
| 8086:31e3 | 1028:081f | Intel      | Celeron/Pentium Silver Pr... | 2     | ahci       | 582965792D |
| 8086:31e3 | 17aa:3801 | Intel      | Celeron/Pentium Silver Pr... | 2     | ahci       | 3E9117AA42 |
| 8086:5ae3 | 1025:1198 | Intel      | Celeron N3350/Pentium N42... | 2     | ahci       | ACA273FE62 |
| 8086:5ae3 | 103c:830d | Intel      | Celeron N3350/Pentium N42... | 2     | ahci       | 27DC03B58E |
| 8086:5ae3 | 1043:1d90 | Intel      | Celeron N3350/Pentium N42... | 2     | ahci       | C8D3F204E5 |
| 8086:9d03 | 1025:1139 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 95AF4B8DC9 |
| 8086:9d03 | 103c:804f | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | E5C02D2922 |
| 8086:9d03 | 103c:8143 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 03065735FF |
| 8086:9d03 | 103c:81ac | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 235D55372B |
| 8086:9d03 | 103c:8251 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | A758FDF9AF |
| 8086:9d03 | 103c:8314 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 5CF089CFA1 |
| 8086:9d03 | 103c:83c9 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 8BF489A0CB |
| 8086:9d03 | 1043:1330 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 905BC0C0BC |
| 8086:9d03 | 1043:1480 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 7AD86811C5 |
| 8086:9d03 | 1043:18e0 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 442B55026A |
| 8086:9d03 | 1043:1b60 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 6570252E3E |
| 8086:9d03 | 144d:c141 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | ADF6EF8A4C |
| 8086:9d03 | 17aa:385b | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 32B0895AB5 |
| 8086:9dd3 | 1028:089f | Intel      | Cannon Point-LP SATA Cont... | 2     | ahci       | DDC277B9F6 |
| 8086:9dd3 | 1028:0908 | Intel      | Cannon Point-LP SATA Cont... | 2     | ahci       | 273368EC98 |
| 8086:9dd3 | 1043:1541 | Intel      | Cannon Point-LP SATA Cont... | 2     | ahci       | 16BD2F3C70 |
| 8086:9dd3 | 17aa:3803 | Intel      | Cannon Point-LP SATA Cont... | 2     | ahci       | 85121B8AEC |
| 1022:7901 | 103c:8535 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 31CBD77D73 |
| 1022:7901 | 103c:85dd | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 28E0BC08FA |
| 1022:7904 | 103c:81ab | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | D98A9E0C48 |
| 8086:02d3 | 1028:0960 | Intel      | Comet Lake SATA AHCI Cont... | 1     | ahci       | 6194139036 |
| 8086:22a3 | 103c:8074 | Intel      | Atom/Celeron/Pentium Proc... | 1     | ahci       | 51A2F6EB71 |
| 8086:22a3 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 1     | ahci       | 6B543E87F8 |
| 8086:22a3 | 17aa:3801 | Intel      | Atom/Celeron/Pentium Proc... | 1     | ahci       | F6650D66F7 |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 233   | nvme       | 87DA71BBB9 |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 79    | nvme       | 9FCFE8BF6A |
| 8086:0975 | 8086:8410 | Intel      | Non-Volatile memory contr... | 54    | nvme       | 520E728AF7 |
| 8086:0975 | 8086:8510 | Intel      | Non-Volatile memory contr... | 53    | nvme       | 520E728AF7 |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 53    | nvme       | 4A08AFE55E |
| 1e0f:0001 | 1e0f:0001 | KIOXIA     | Non-Volatile memory contr... | 51    | nvme       | AD3C1FB56A |
| 144d:a809 | 144d:a801 | Samsung... | NVMe Controller              | 45    | nvme       | D000862005 |
| 1179:0113 | 1179:0001 | Toshiba... | BG3 NVMe SSD Controller      | 40    | nvme       | D2D2EB910A |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 40    | nvme       | B47C4EF32E |
| 15b7:5003 | 15b7:5003 | Sandisk    | WD Blue SN500 / PC SN520 ... | 36    | nvme       | 7B7C2317D8 |
| 1c5c:1527 | 1c5c:1527 | SK Hynix   | PC401 NVMe Solid State Dr... | 34    | nvme       | 1A0B1FFDBD |
| 1c5c:1339 | 1c5c:0000 | SK Hynix   | BC511                        | 33    | nvme       | 9ED34E6D16 |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | BC501 NVMe Solid State Dr... | 32    | nvme       | 633CDE303A |
| 15b7:5006 | 15b7:5006 | Sandisk    | WD Black SN750 / PC SN730... | 31    | nvme       | 32CA60DCEA |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/SN750 / PC ... | 29    | nvme       | 168717D052 |
| 1179:011a | 1179:0001 | Toshiba... | XG6 NVMe SSD Controller      | 28    | nvme       | FD2D87232F |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 19    | nvme       | 19DF1FFB17 |
| 1179:0115 | 1179:0001 | Toshiba... | XG4 NVMe SSD Controller      | 16    | nvme       | 0CF31876B8 |
| 1c5c:1627 | 1c5c:1627 | SK Hynix   | Non-Volatile memory contr... | 12    | nvme       | A18B247E3D |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 11    | nvme       | EF922FA721 |
| 1cc4:6202 | 1cc4:1cc4 | Union M... | Non-Volatile memory contr... | 10    | nvme       | CC7CB4A34E |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 10    | nvme       | CA8936A74C |
| 15b7:5004 | 15b7:5004 | Sandisk    | PC SN520 NVMe SSD            | 9     | nvme       | DDC277B9F6 |
| 15b7:5005 | 15b7:5005 | Sandisk    | PC SN520 NVMe SSD            | 9     | nvme       | 86A25931BD |
| 15b7:5008 | 15b7:5008 | Sandisk    | Non-Volatile memory contr... | 9     | nvme       | BD60E8098F |
| 1344:5405 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 7     | nvme       | 104C0A6058 |
| 126f:2263 | 126f:2263 | Silicon... | SM2263EN/SM2263XT SSD Con... | 6     | nvme       | 85121B8AEC |
| 1344:5410 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 6     | nvme       | B0722E1B57 |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 6     | nvme       | 1AF669260C |
| 1c5c:1639 | 1c5c:1639 | SK Hynix   | Non-Volatile memory contr... | 6     | nvme       | D5829ED162 |
| 1cc4:6203 | 1cc4:1cc4 | Union M... | Non-Volatile memory contr... | 6     | nvme       | 64A9E43743 |
| 15b7:5009 | 15b7:5009 | Sandisk    | WD Blue SN550 NVMe SSD       | 5     | nvme       | 96E19F007A |
| c0a9:2263 | c0a9:2263 | Micron/... | P1 NVMe PCIe SSD             | 5     | nvme       | 6E5C30C5C5 |
| 1987:5013 | 1987:5013 | Phison ... | PS5013 E13 NVMe Controller   | 4     | nvme       | 57651669E3 |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 4     | nvme       | CB2B38D97F |
| 2646:2263 | 2646:2263 | Kingsto... | A2000 NVMe SSD               | 4     | nvme       | EF7445EB15 |
| 126f:2262 | 126f:2262 | Silicon... | SM2262/SM2262EN SSD Contr... | 3     | nvme       | A9626F1580 |
| 15b7:5007 | 15b7:5007 | Sandisk    | Non-Volatile memory contr... | 3     | nvme       | F131057329 |
| 1cc4:5008 | 1cc4:5008 | Union M... | Non-Volatile memory contr... | 3     | nvme       | 010C424C33 |
| 2646:500c | 2646:500c | Kingsto... | Technology Company Non-Vo... | 3     | nvme       | 3CCC205BB6 |
| 1344:5404 | 1344:1100 | Micron ... | Non-Volatile memory contr... | 2     | nvme       | 1EADD9C9AC |
| 144d:a80a | 144d:a801 | Samsung... | NVMe SSD Controller PM9A1... | 2     | nvme       | C5856B1EA0 |
| 1c5c:1284 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 2     | nvme       | BC2A228855 |
| 1c5c:174a | 1c5c:174a | SK Hynix   | NVMe SSD Controller          | 2     | nvme       | BC7C58F248 |
| 1cc1:33f3 | 1cc1:33f3 | ADATA T... | Non-Volatile memory contr... | 2     | nvme       | 82EB222C26 |
| 2646:5008 | 2646:5008 | Kingsto... | U-SNS8154P3 NVMe SSD         | 2     | nvme       | 898F69117C |
| 8086:0000 |           | Intel      | PROSet/Wireless WiFi Soft... | 2     | nvme       | 086EC09EE4 |
| c0a9:5403 | c0a9:2100 | Micron/... | NVMe Controller              | 2     | nvme       | 1DC136B651 |
| c0a9:5412 | c0a9:0100 | Micron/... | Non-Volatile memory contr... | 2     | nvme       | 3CCC205BB6 |
| 10ec:5762 | 10ec:5762 | Realtek... | RTS5763DL NVMe SSD Contro... | 1     | nvme       | BC69AFD822 |
| 10ec:5763 | 10ec:5763 | Realtek... | Realtek Non-Volatile memo... | 1     | nvme       | A7D8B6A0DD |
| 144d:a806 | 144d:a801 | Samsung... | Electronics Non-Volatile ... | 1     | nvme       | 5F781E103C |
| 14a4:2100 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 1     | nvme       | C28AED72AA |
| 14a4:9100 | 126f:2263 | Lite-On... | NVMe Controller              | 1     | nvme       | 30F9D92510 |
| 15b7:5001 | 1b4b:1093 | Sandisk    | WD Black NVMe SSD            | 1     | nvme       | D666EADD11 |
| 17aa:0005 | 17aa:1005 | Lenovo     | Non-Volatile memory contr... | 1     | nvme       | 30BE25CAF6 |
| 1987:5008 | 1987:5008 | Phison ... | NVMe Storage Controller      | 1     | nvme       | CDEC5FA860 |
| 1bb1:5012 | 1bb1:5012 | Seagate... | FireCuda 510 SSD             | 1     | nvme       | D4082453C1 |
| 1cc4:2260 | 1cc4:2260 | Union M... | Non-Volatile memory contr... | 1     | nvme       | CE03C99485 |
| 1dee:2262 | 1dee:1dee | Biwin S... | Non-Volatile memory contr... | 1     | nvme       | F8C5A69D8E |
| 2646:500d | 2646:500d | Kingsto... | OM3PDP3 NVMe SSD             | 1     | nvme       | EB4CC7F2C2 |
| 8086:f1a7 | 8086:390c | Intel      | Non-Volatile memory contr... | 1     | nvme       | 6C6FB6B24A |
| c0a9:540a | c0a9:540a | Micron/... | P2 NVMe PCIe SSD             | 1     | nvme       | 511562A9DF |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9a0b | 8086:0000 | Intel      | Volume Management Device ... | 13    | vmd        | 6B850F8E6F |
| 8086:282a | 17aa:380e | Intel      | 82801 Mobile SATA Control... | 12    | ahci       | 44E586277C |
| 8086:9a0b | 1028:0a05 | Intel      | Volume Management Device ... | 12    | vmd        | 71B5E3C825 |
| 8086:9a0b | 8086:7270 | Intel      | Volume Management Device ... | 8     | vmd        | 13AC1F05DD |
| 8086:282a | 103c:85c4 | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | 9BCBAF17E9 |
| 8086:282a | 103c:863f | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | 638C4207CE |
| 8086:282a | 103c:86b1 | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | 093BEED213 |
| 8086:282a | 103c:86b2 | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | 42A03DCD82 |
| 8086:282a | 103c:86f9 | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | A18B247E3D |
| 8086:282a | 103c:866e | Intel      | 82801 Mobile SATA Control... | 6     | ahci       | 22FAA280E3 |
| 8086:9a0b | 1028:09dd | Intel      | Volume Management Device ... | 6     | vmd        | 6BFDD9FDA4 |
| 8086:282a | 103c:85e7 | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 169477DE3F |
| 8086:282a | 17aa:3806 | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | CD156B08D8 |
| 8086:9a0b | 1028:09ff | Intel      | Volume Management Device ... | 5     | vmd        | ACD54357F7 |
| 8086:282a | 103c:850c | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | EEC05D1BF9 |
| 8086:282a | 103c:850e | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 0C2D648815 |
| 8086:282a | 103c:85c8 | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 1649B0B654 |
| 8086:282a | 103c:86fa | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 520E728AF7 |
| 8086:9a0b | 1028:09df | Intel      | Volume Management Device ... | 4     | vmd        | 5B40E331B3 |
| 8086:282a | 103c:8488 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 913C46A400 |
| 8086:282a | 103c:850d | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 987181B525 |
| 8086:282a | 103c:85c5 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | D2D2EB910A |
| 8086:282a | 103c:861f | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | D284325FCF |
| 8086:282a | 103c:875b | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 7490F0847D |
| 8086:9a0b | 103c:8825 | Intel      | Volume Management Device ... | 3     | vmd        | 7FC1E5873C |
| 8086:02d7 | 1028:0950 | Intel      | Comet Lake PCH-LP SATA RA... | 2     | ahci       | 9DD76AE820 |
| 8086:02d7 | 1028:0960 | Intel      | Comet Lake PCH-LP SATA RA... | 2     | ahci       | F7AB576C61 |
| 8086:02d7 | 1043:1c51 | Intel      | Comet Lake PCH-LP SATA RA... | 2     |            | C5079022A9 |
| 8086:282a | 1028:089e | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 7BF07FCCB5 |
| 8086:282a | 1028:0907 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | CE0C672AEB |
| 8086:282a | 103c:8514 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 3204FA323C |
| 8086:282a | 103c:85e6 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 0A7C046DCE |
| 8086:282a | 103c:8637 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | F30D3F55AD |
| 8086:282a | 103c:8671 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 74D939AB7B |
| 8086:282a | 1043:19d1 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 597F1536E2 |
| 8086:282a | 17aa:3836 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | E473000ADA |
| 8086:9a0b | 1028:09de | Intel      | Volume Management Device ... | 2     | vmd        | 65286CB6D4 |
| 8086:9a0b | 14c0:012d | Intel      | Volume Management Device ... | 2     | vmd        | DB80BC62DA |
| 8086:02d7 | 1028:0951 | Intel      | Comet Lake PCH-LP SATA RA... | 1     |            | 1C83B9C63C |
| 8086:02d7 | 1028:09da | Intel      | Comet Lake PCH-LP SATA RA... | 1     | ahci       | 2BE9BAE979 |
| 8086:02d7 | 103c:86e5 | Intel      | Comet Lake PCH-LP SATA RA... | 1     | ahci       | BC0C18859B |
| 8086:282a | 1025:120e | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | CF6164516E |
| 8086:282a | 1025:1419 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | C617717583 |
| 8086:282a | 1028:077a | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 57D57D82FE |
| 8086:282a | 1028:07aa | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | DFDC8C484F |
| 8086:282a | 1028:07ec | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 4CCEC31055 |
| 8086:282a | 1028:0894 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | B07A0CF706 |
| 8086:282a | 1028:089f | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 70A45F8830 |
| 8086:282a | 1028:08b0 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 84E42F271F |
| 8086:282a | 1028:0908 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | C086BA0897 |
| 8086:282a | 1028:095d | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 708D566327 |
| 8086:282a | 103c:8486 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 026067E41D |
| 8086:282a | 103c:8487 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | C9B7CA8930 |
| 8086:282a | 103c:85c6 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 447AC858DA |
| 8086:282a | 103c:85cd | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | E7DCDD4B39 |
| 8086:282a | 103c:863e | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | DF64AA5AA5 |
| 8086:282a | 103c:8670 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 9212F9DB05 |
| 8086:282a | 103c:8672 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 8E5E4CCD9B |
| 8086:282a | 103c:86ec | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 483D4785B1 |
| 8086:282a | 103c:8774 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | B2E6CAF193 |
| 8086:282a | 1043:1b31 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | EE715DE644 |
| 8086:282a | 1043:1f61 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 3D10849F6E |
| 8086:282a | 17aa:3805 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | B2648D2B7C |
| 8086:282a | 17aa:380a | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | D9D123FF85 |
| 8086:282a | 17aa:380b | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 1681EDB0F6 |
| 8086:282a | 8086:7270 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | DC14D7EC63 |
| 8086:9a0b | 1025:1509 | Intel      | Volume Management Device ... | 1     | vmd        | 3CCC205BB6 |
| 8086:9a0b | 1028:0a37 | Intel      | Volume Management Device ... | 1     | vmd        | 6B922F27D1 |
| 8086:9a0b | 103c:8811 | Intel      | Volume Management Device ... | 1     | vmd        | 23CF6E2D7A |
| 8086:9a0b | 103c:8824 | Intel      | Volume Management Device ... | 1     | vmd        | 1D88D038F7 |
| 8086:9a0b | 103c:8826 | Intel      | Volume Management Device ... | 1     | vmd        | 96E19F007A |
| 8086:9a0b | 103c:8847 | Intel      | Volume Management Device ... | 1     | vmd        | 0B8822B65D |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8a17 |           | Intel      | Ice Lake Thunderbolt 3 NH... | 50    | thunder... | 520E728AF7 |
| 8086:09ab |           | Intel      | System peripheral            | 30    |            | 5B40E331B3 |
| 8086:1911 | 17aa:3869 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 28    |            | F72E765EF0 |
| 8086:15d2 | 103c:8514 | Intel      | JHL6540 Thunderbolt 3 NHI... | 23    | thunder... | 2352CAA9CF |
| 8086:1911 | 17aa:385b | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 22    |            | CD156B08D8 |
| 8086:1911 | 17aa:2292 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 21    |            | 32CA60DCEA |
| 8086:8a0d |           | Intel      | Ice Lake Thunderbolt 3 NH... | 21    | thunder... | 6B27A727BE |
| 8086:15d2 | 17aa:2292 | Intel      | JHL6540 Thunderbolt 3 NHI... | 19    | thunder... | 32CA60DCEA |
| 8086:1911 | 17aa:2238 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 19    |            | D878C63FE4 |
| 8086:1911 | 17aa:3806 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 13    |            | 5BDCB41FEE |
| 8086:1911 | 17aa:2259 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 12    |            | C96223F666 |
| 8086:15d2 | 2222:1111 | Intel      | JHL6540 Thunderbolt 3 NHI... | 11    | thunder... | 84651F4EA3 |
| 8086:1911 | 17aa:224e | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 11    |            | B866426527 |
| 8086:1911 | 17aa:3804 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 10    |            | B58AABDE5F |
| 8086:1911 | 1028:0894 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 9     |            | B07A0CF706 |
| 8086:1911 | 17aa:5078 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 9     |            | 7C78B71A99 |
| 8086:09ab | ffff:ffff | Intel      | System peripheral            | 8     |            | 13AC1F05DD |
| 8086:15d2 | 103c:8438 | Intel      | JHL6540 Thunderbolt 3 NHI... | 8     | thunder... | 633CDE303A |
| 8086:1911 | 1028:095d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 8     |            | B5682ADC9E |
| 8086:15e8 | 1028:0950 | Intel      | JHL7540 Thunderbolt 3 NHI... | 7     | thunder... | 1C83B9C63C |
| 8086:15e8 | 103c:863f | Intel      | JHL7540 Thunderbolt 3 NHI... | 7     | thunder... | 638C4207CE |
| 8086:15eb | 1028:09cd | Intel      | JHL7540 Thunderbolt 3 NHI... | 7     | thunder... | BC7C58F248 |
| 8086:15eb | 103c:861f | Intel      | JHL7540 Thunderbolt 3 NHI... | 7     | thunder... | D284325FCF |
| 8086:1911 | 1028:09cd | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 7     |            | BC7C58F248 |
| 8086:1911 | 103c:85c4 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 7     |            | 9BCBAF17E9 |
| 8086:1911 | 103c:86b1 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 7     |            | 093BEED213 |
| 8086:1911 | 103c:86b2 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 7     |            | 42A03DCD82 |
| 8086:1911 | 17aa:506d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 7     |            | 847655CB40 |
| 8086:1911 | 1028:089e | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 6     |            | C6692154A1 |
| 8086:1911 | 103c:866e | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 6     |            | 22FAA280E3 |
| 8086:1911 | 17aa:2237 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 6     |            | 2A0ECA4670 |
| 8086:1911 | 17aa:3831 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 6     |            | CF93488B90 |
| 8086:8a11 | 1025:141f | Intel      | System peripheral            | 6     |            | AA8934716B |
| 8086:09ab | 1028:09ff | Intel      | System peripheral            | 5     |            | ACD54357F7 |
| 8086:09ab | 103c:87f6 | Intel      | System peripheral            | 5     |            | 48A0452D0B |
| 8086:15bf | 17aa:2294 | Intel      | JHL6240 Thunderbolt 3 NHI... | 5     | thunder... | 09DC5430DA |
| 8086:15d2 | 17aa:22be | Intel      | JHL6540 Thunderbolt 3 NHI... | 5     | thunder... | E40B11DCA2 |
| 8086:15d2 | 17aa:3801 | Intel      | JHL6540 Thunderbolt 3 NHI... | 5     | thunder... | 78960B975F |
| 8086:1911 | 1028:08b6 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | B0722E1B57 |
| 8086:1911 | 1028:0950 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 9DD76AE820 |
| 8086:1911 | 103c:85e7 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 169477DE3F |
| 8086:1911 | 1043:1541 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 8EFC8CAADA |
| 8086:1911 | 1043:19d1 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 9054D4EBEB |
| 8086:1911 | 17aa:2294 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 09DC5430DA |
| 8086:1911 | 17aa:22be | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | E40B11DCA2 |
| 8086:1911 | 17aa:3855 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | D9D123FF85 |
| 8086:1911 | 17aa:3867 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 78960B975F |
| 8086:1911 | 17aa:504c | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 4983586FE5 |
| 8086:1911 | 17aa:5077 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 87DA71BBB9 |
| 8086:9a11 | 103c:87f7 | Intel      | GNA Scoring Accelerator m... | 5     |            | 48A0452D0B |
| 8086:09ab | 103c:8709 | Intel      | System peripheral            | 4     |            | 6B850F8E6F |
| 8086:15d2 | 1028:08e2 | Intel      | JHL6540 Thunderbolt 3 NHI... | 4     | thunder... | 31C59F8FC7 |
| 8086:15d9 | 1028:08b6 | Intel      | JHL6340 Thunderbolt 3 NHI... | 4     | thunder... | B0722E1B57 |
| 8086:15d9 | 103c:8518 | Intel      | JHL6340 Thunderbolt 3 NHI... | 4     | thunder... | 64C5568456 |
| 8086:15eb | 103c:8548 | Intel      | JHL7540 Thunderbolt 3 NHI... | 4     | thunder... | D862548439 |
| 8086:15eb | 103c:863e | Intel      | JHL7540 Thunderbolt 3 NHI... | 4     | thunder... | B47C4EF32E |
| 8086:1911 | 1028:08e2 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | 31C59F8FC7 |
| 8086:1911 | 1028:0951 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | 247867F57E |
| 8086:1911 | 103c:850c | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | EEC05D1BF9 |
| 8086:1911 | 103c:850e | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | 0C2D648815 |
| 8086:1911 | 103c:85c8 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | 1649B0B654 |
| 8086:1911 | 103c:85cd | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | E7DCDD4B39 |
| 8086:1911 | 17aa:5061 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | 9FCFE8BF6A |
| 8086:9a11 | 103c:8709 | Intel      | GNA Scoring Accelerator m... | 4     |            | 6B850F8E6F |
| 8086:9a11 | 103c:87f4 | Intel      | GNA Scoring Accelerator m... | 4     |            | A0A4DFE970 |
| 8086:09ab | 103c:8825 | Intel      | System peripheral            | 3     |            | 7FC1E5873C |
| 8086:15bf | 2222:1111 | Intel      | JHL6240 Thunderbolt 3 NHI... | 3     | thunder... | A9626F1580 |
| 8086:15d2 | 103c:8470 | Intel      | JHL6540 Thunderbolt 3 NHI... | 3     | thunder... | EF7445EB15 |
| 8086:15e8 | 1028:0960 | Intel      | JHL7540 Thunderbolt 3 NHI... | 3     | thunder... | F7AB576C61 |
| 8086:15eb | 103c:857f | Intel      | JHL7540 Thunderbolt 3 NHI... | 3     | thunder... | 5FDEDC599E |
| 8086:15eb | 103c:8637 | Intel      | JHL7540 Thunderbolt 3 NHI... | 3     | thunder... | F30D3F55AD |
| 8086:15eb | 103c:876d | Intel      | JHL7540 Thunderbolt 3 NHI... | 3     | thunder... | 502CD63C0F |
| 8086:15eb | 17aa:383d | Intel      | JHL7540 Thunderbolt 3 NHI... | 3     | thunder... | F1C4AE114C |
| 8086:1911 | 1028:0895 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | 8E4E4194ED |
| 8086:1911 | 1028:0896 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | 4F9EBC7CD4 |
| 8086:1911 | 1028:089f | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | DDC277B9F6 |
| 8086:1911 | 1028:0907 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | B6EB2D9514 |
| 8086:1911 | 1028:0908 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | C086BA0897 |
| 8086:1911 | 1028:0960 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | F7AB576C61 |
| 8086:1911 | 103c:850d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | 987181B525 |
| 8086:1911 | 103c:85c5 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | D2D2EB910A |
| 8086:1911 | 1043:1481 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | 30B72B97CB |
| 8086:1911 | 17aa:3845 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | 32B0895AB5 |
| 8086:1911 | 17aa:3851 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | E970E25954 |
| 8086:1911 | 17aa:3853 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | F204C1A1F4 |
| 8086:1911 | 17aa:386b | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | F1C4AE114C |
| 8086:1911 | 8086:1911 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | 6F018F175E |
| 8086:3190 | 1025:1316 | Intel      | Celeron/Pentium Silver Pr... | 3     |            | 19F4CA16E7 |
| 8086:9a11 | 103c:8825 | Intel      | GNA Scoring Accelerator m... | 3     |            | 7FC1E5873C |
| 8086:09ab | 14c0:012d | Intel      | System peripheral            | 2     |            | DB80BC62DA |
| 8086:15bf | 17aa:22ad | Intel      | JHL6240 Thunderbolt 3 NHI... | 2     | thunder... | 8E3E2A94C3 |
| 8086:15d2 | 103c:8503 | Intel      | JHL6540 Thunderbolt 3 NHI... | 2     | thunder... | F6ABCD9B4F |
| 8086:15d9 | 2222:1111 | Intel      | JHL6340 Thunderbolt 3 NHI... | 2     | thunder... | C0A9C9443B |
| 8086:15e8 | 103c:86e5 | Intel      | JHL7540 Thunderbolt 3 NHI... | 2     | thunder... | FD2D87232F |
| 8086:15eb | 1028:09c6 | Intel      | JHL7540 Thunderbolt 3 NHI... | 2     | thunder... | B776BEB710 |
| 8086:15eb | 103c:8725 | Intel      | JHL7540 Thunderbolt 3 NHI... | 2     | thunder... | C617B180A8 |
| 8086:15eb | 10c3:8519 | Intel      | JHL7540 Thunderbolt 3 NHI... | 2     | thunder... | AED071D8CE |
| 8086:1911 | 1028:09c6 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | B776BEB710 |
| 8086:1911 | 103c:8503 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | F6ABCD9B4F |
| 8086:1911 | 103c:85e6 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 0A7C046DCE |

### Unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:5aa2 | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 5     | intel_i... | 98851C034C |
| 8086:31a2 | 1028:081f | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_i... | 582965792D |
| 8086:31a2 | 17aa:3801 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_i... | 3E9117AA42 |
| 8086:5aa2 | 103c:830d | Intel      | Celeron N3350/Pentium N42... | 2     | intel_i... | 27DC03B58E |
| 8086:5aa2 | 1043:1d90 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_i... | C8D3F204E5 |
| 8086:31a2 | 103c:84fa | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_i... | 345648FE18 |
| 8086:31a2 | 103c:85ca | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_i... | 363C54D31F |
| 8086:31a2 | 103c:86cf | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_i... | 33D5688BFC |
| 8086:5aa2 | 1043:1930 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | B6FC10EFA8 |
| 8086:5aa2 | 1043:1d60 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | 45B1907784 |
| 8086:5aa2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | 6663E08482 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d2f | 1043:201f | Intel      | Sunrise Point-LP USB 3.0 ... | 50    | xhci_hcd   | CE8E9AF30D |
| 8086:9a13 |           | Intel      | Tiger Lake-LP Thunderbolt... | 49    | xhci_pci   | 5B40E331B3 |
| 8086:9a1b | 2222:1111 | Intel      | Tiger Lake-LP Thunderbolt... | 47    | thunder... | AD3C1FB56A |
| 1022:1639 | 17aa:3812 | AMD        | Renoir USB 3.1               | 46    | xhci_pci   | 64A9E43743 |
| 8086:8a13 |           | Intel      | Ice Lake Thunderbolt 3 US... | 45    | xhci_hcd   | 6B27A727BE |
| 8086:a0ed |           | Intel      | Tiger Lake-LP USB 3.2 Gen... | 42    | xhci_hcd   | 5B40E331B3 |
| 8086:9d2f | 17aa:383f | Intel      | Sunrise Point-LP USB 3.0 ... | 36    | xhci_hcd   | 44E586277C |
| 8086:02ed | 17aa:380a | Intel      | Comet Lake PCH-LP USB 3.1... | 28    | xhci_hcd   | F72E765EF0 |
| 1022:1639 | 103c:876f | AMD        | Renoir USB 3.1               | 27    | xhci_hcd   | 08B513769D |
| 8086:5aa8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | xhci_hcd   | 378291C3E0 |
| 1022:1639 | 103c:876e | AMD        | Renoir USB 3.1               | 26    | xhci_hcd   | F77E2EBB10 |
| 8086:22b5 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 25    | xhci_hcd   | 1866D29174 |
| 8086:9d2f | 103c:83b9 | Intel      | Sunrise Point-LP USB 3.0 ... | 24    | xhci_hcd   | 2C533BE257 |
| 8086:15d4 | 103c:8514 | Intel      | JHL6540 Thunderbolt 3 USB... | 23    | xhci_hcd   | 2352CAA9CF |
| 8086:9ded | 103c:8514 | Intel      | Cannon Point-LP USB 3.1 x... | 23    | xhci_hcd   | 2352CAA9CF |
| 1022:15e0 | 103c:85dd | AMD        | Raven USB 3.1                | 22    | xhci_pci   | A93B2565DF |
| 1022:15e1 | 103c:85dd | AMD        | Raven USB 3.1                | 22    | xhci_pci   | A93B2565DF |
| 8086:15d4 | 2222:1111 | Intel      | JHL6540 Thunderbolt 3 USB... | 22    | xhci_hcd   | 570666D7D6 |
| 8086:9ded | 17aa:3807 | Intel      | Cannon Point-LP USB 3.1 x... | 22    | xhci_hcd   | CD156B08D8 |
| 8086:34ed | 17aa:3805 | Intel      | Ice Lake-LP USB 3.1 xHCI ... | 21    | xhci_pci   | 7C965E245C |
| 8086:9a1b |           | Intel      | Tiger Lake-LP Thunderbolt... | 21    | thunder... | 9907063783 |
| 8086:31a8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    | xhci_hcd   | 38E5F73567 |
| 8086:15d4 | 17aa:2292 | Intel      | JHL6540 Thunderbolt 3 USB... | 19    | xhci_hcd   | 32CA60DCEA |
| 8086:9d2f | 17aa:2238 | Intel      | Sunrise Point-LP USB 3.0 ... | 19    | xhci_hcd   | D878C63FE4 |
| 8086:9d2f | 17aa:3864 | Intel      | Sunrise Point-LP USB 3.0 ... | 19    | xhci_hcd   | 1A0B1FFDBD |
| 1022:15e0 | 103c:85de | AMD        | Raven USB 3.1                | 17    | xhci_hcd   | 9E86C8EDE5 |
| 1022:15e1 | 103c:85de | AMD        | Raven USB 3.1                | 17    | xhci_hcd   | 9E86C8EDE5 |
| 8086:34ed | 1028:08b0 | Intel      | Ice Lake-LP USB 3.1 xHCI ... | 17    | xhci_hcd   | 6B27A727BE |
| 8086:9d2f | 17aa:386a | Intel      | Sunrise Point-LP USB 3.0 ... | 17    | xhci_hcd   | 6E045B787A |
| 1022:15e0 | 17aa:3805 | AMD        | Raven USB 3.1                | 16    | xhci_hcd   | 57651669E3 |
| 1022:15e1 | 17aa:3806 | AMD        | Raven USB 3.1                | 16    | xhci_hcd   | 57651669E3 |
| 8086:9ded | 17aa:2292 | Intel      | Cannon Point-LP USB 3.1 x... | 16    | xhci_hcd   | 3795F3DF87 |
| 1022:15e0 | 103c:83c6 | AMD        | Raven USB 3.1                | 15    | xhci_hcd   | 168717D052 |
| 1022:15e1 | 103c:83c6 | AMD        | Raven USB 3.1                | 15    | xhci_hcd   | 168717D052 |
| 8086:34ed | 17aa:3844 | Intel      | Ice Lake-LP USB 3.1 xHCI ... | 15    | xhci_hcd   | 2E19A058F9 |
| 8086:8a13 | 17aa:380a | Intel      | Ice Lake Thunderbolt 3 US... | 15    | xhci_hcd   | 2E19A058F9 |
| 8086:9ded | 1043:201f | Intel      | Cannon Point-LP USB 3.1 x... | 15    | xhci_hcd   | 9054D4EBEB |
| 1022:15e0 | 103c:8496 | AMD        | Raven USB 3.1                | 14    | xhci_hcd   | 8A63E2E055 |
| 1022:15e1 | 103c:8496 | AMD        | Raven USB 3.1                | 14    | xhci_hcd   | 8A63E2E055 |
| 8086:9a1d |           | Intel      | Tiger Lake-LP Thunderbolt... | 14    | thunder... | 9907063783 |
| 8086:9d2f | 103c:830f | Intel      | Sunrise Point-LP USB 3.0 ... | 14    | xhci_hcd   | B6BC75336E |
| 8086:9d2f | 17aa:3825 | Intel      | Sunrise Point-LP USB 3.0 ... | 14    | xhci_hcd   | 15C0F31B91 |
| 1022:15e0 | 103c:8497 | AMD        | Raven USB 3.1                | 13    | xhci_hcd   | 2910A4173E |
| 1022:15e1 | 103c:8497 | AMD        | Raven USB 3.1                | 13    | xhci_hcd   | 2910A4173E |
| 8086:02ed | 17aa:3806 | Intel      | Comet Lake PCH-LP USB 3.1... | 13    | xhci_hcd   | 5BDCB41FEE |
| 8086:9d2f | 103c:827d | Intel      | Sunrise Point-LP USB 3.0 ... | 13    | xhci_hcd   | 51178C1953 |
| 8086:9d2f | 103c:8486 | Intel      | Sunrise Point-LP USB 3.0 ... | 13    | xhci_hcd   | B149A04EE8 |
| 8086:9d2f | 17aa:3811 | Intel      | Sunrise Point-LP USB 3.0 ... | 13    | xhci_hcd   | 1E4A851AD2 |
| 8086:9d2f | 17aa:383e | Intel      | Sunrise Point-LP USB 3.0 ... | 13    | xhci_hcd   | 2F1BC93921 |
| 8086:a12f | 103c:83bb | Intel      | 100 Series/C230 Series Ch... | 13    | xhci_hcd   | BA09E3B76F |
| 8086:9a1d | 2222:1111 | Intel      | Tiger Lake-LP Thunderbolt... | 12    | thunder... | AD3C1FB56A |
| 8086:9d2f | 103c:827e | Intel      | Sunrise Point-LP USB 3.0 ... | 12    | xhci_hcd   | B3CFF29C2E |
| 8086:9d2f | 17aa:2259 | Intel      | Sunrise Point-LP USB 3.0 ... | 12    | xhci_hcd   | C96223F666 |
| 8086:a12f | 17aa:3807 | Intel      | 100 Series/C230 Series Ch... | 12    | xhci_hcd   | A9626F1580 |
| 1022:1639 | 103c:8735 | AMD        | Renoir USB 3.1               | 11    | xhci_pci   | F36EA99568 |
| 8086:9d2f | 1028:077a | Intel      | Sunrise Point-LP USB 3.0 ... | 11    | xhci_hcd   | C0A9C9443B |
| 8086:9d2f | 17aa:224e | Intel      | Sunrise Point-LP USB 3.0 ... | 11    | xhci_hcd   | B866426527 |
| 8086:9d2f | 103c:8488 | Intel      | Sunrise Point-LP USB 3.0 ... | 10    | xhci_hcd   | 7B7C2317D8 |
| 8086:9d2f | 17aa:3805 | Intel      | Sunrise Point-LP USB 3.0 ... | 10    | xhci_hcd   | B58AABDE5F |
| 8086:9d2f | 17aa:380b | Intel      | Sunrise Point-LP USB 3.0 ... | 10    | xhci_hcd   | A4D6F3CCE4 |
| 8086:9d2f | 17aa:3861 | Intel      | Sunrise Point-LP USB 3.0 ... | 10    | xhci_hcd   | 384114E0B4 |
| 8086:02ed | 17aa:5078 | Intel      | Comet Lake PCH-LP USB 3.1... | 9     | xhci_hcd   | 7C78B71A99 |
| 8086:22b5 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 9     | xhci_hcd   | 8638532EEB |
| 8086:9a13 | 1028:09ff | Intel      | Tiger Lake-LP Thunderbolt... | 9     | xhci_hcd   | AD3C1FB56A |
| 8086:9d2f | 103c:80d1 | Intel      | Sunrise Point-LP USB 3.0 ... | 9     | xhci_hcd   | 629D516666 |
| 8086:9d2f | 103c:81a1 | Intel      | Sunrise Point-LP USB 3.0 ... | 9     | xhci_hcd   | B37CBA5DF4 |
| 8086:9ded | 1028:0894 | Intel      | Cannon Point-LP USB 3.1 x... | 9     | xhci_hcd   | B07A0CF706 |
| 8086:a0ed | 1028:09ff | Intel      | Tiger Lake-LP USB 3.2 Gen... | 9     | xhci_hcd   | AD3C1FB56A |
| 8086:a12f | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 9     | xhci_hcd   | C28F77B8F1 |
| 1022:15e0 | 1043:201f | AMD        | Raven USB 3.1                | 8     | xhci_hcd   | 824BB881D7 |
| 1022:15e1 | 1043:201f | AMD        | Raven USB 3.1                | 8     | xhci_hcd   | 824BB881D7 |
| 8086:02ed | 1028:095d | Intel      | Comet Lake PCH-LP USB 3.1... | 8     | xhci_hcd   | B5682ADC9E |
| 8086:15d4 | 103c:8438 | Intel      | JHL6540 Thunderbolt 3 USB... | 8     | xhci_hcd   | 633CDE303A |
| 8086:9d2f | 103c:8438 | Intel      | Sunrise Point-LP USB 3.0 ... | 8     | xhci_hcd   | 633CDE303A |
| 8086:02ed | 1028:09cd | Intel      | Comet Lake PCH-LP USB 3.1... | 7     | xhci_hcd   | BC7C58F248 |
| 8086:02ed | 103c:863f | Intel      | Comet Lake PCH-LP USB 3.1... | 7     | xhci_hcd   | 638C4207CE |
| 8086:02ed | 103c:86b1 | Intel      | Comet Lake PCH-LP USB 3.1... | 7     | xhci_hcd   | 093BEED213 |
| 8086:02ed | 103c:86b2 | Intel      | Comet Lake PCH-LP USB 3.1... | 7     | xhci_hcd   | 42A03DCD82 |
| 8086:15c1 | 2222:1111 | Intel      | JHL6240 Thunderbolt 3 USB... | 7     | xhci_hcd   | B87E295470 |
| 8086:15d4 |           | Intel      | JHL6540 Thunderbolt 3 USB... | 7     | xhci_hcd   | 6E045B787A |
| 8086:15e9 | 1028:0950 | Intel      | JHL7540 Thunderbolt 3 USB... | 7     | xhci_pci   | 1C83B9C63C |
| 8086:15e9 | 103c:863f | Intel      | JHL7540 Thunderbolt 3 USB... | 7     | xhci_hcd   | 638C4207CE |
| 8086:15ec | 1028:09cd | Intel      | JHL7540 Thunderbolt 3 USB... | 7     | xhci_hcd   | BC7C58F248 |
| 8086:15ec | 103c:861f | Intel      | JHL7540 Thunderbolt 3 USB... | 7     | xhci_pci   | D284325FCF |
| 8086:34ed | 103c:86f9 | Intel      | Ice Lake-LP USB 3.1 xHCI ... | 7     | xhci_hcd   | A18B247E3D |
| 8086:8a13 | 103c:86f9 | Intel      | Ice Lake Thunderbolt 3 US... | 7     | xhci_hcd   | A18B247E3D |
| 8086:9d2f | 17aa:506d | Intel      | Sunrise Point-LP USB 3.0 ... | 7     | xhci_hcd   | 847655CB40 |
| 8086:9ded | 103c:85c4 | Intel      | Cannon Point-LP USB 3.1 x... | 7     | xhci_hcd   | 9BCBAF17E9 |
| 8086:9ded | 103c:861f | Intel      | Cannon Point-LP USB 3.1 x... | 7     | xhci_pci   | D284325FCF |
| 8086:02ed | 103c:866e | Intel      | Comet Lake PCH-LP USB 3.1... | 6     | xhci_pci   | 22FAA280E3 |
| 8086:0f35 | 103c:802b | Intel      | Atom Processor Z36xxx/Z37... | 6     | xhci_pci   | 4EDDB18ED9 |
| 8086:34ed | 1025:141f | Intel      | Ice Lake-LP USB 3.1 xHCI ... | 6     | xhci_hcd   | AA8934716B |
| 8086:8a13 | 1025:141f | Intel      | Ice Lake Thunderbolt 3 US... | 6     | xhci_hcd   | AA8934716B |
| 8086:9d2f | 1025:1176 | Intel      | Sunrise Point-LP USB 3.0 ... | 6     | xhci_hcd   | 566FA6B1D5 |
| 8086:9d2f | 103c:8484 | Intel      | Sunrise Point-LP USB 3.0 ... | 6     | xhci_hcd   | D46010346C |
| 8086:9d2f | 17aa:2237 | Intel      | Sunrise Point-LP USB 3.0 ... | 6     | xhci_hcd   | 2A0ECA4670 |
| 8086:9d2f | 17aa:3847 | Intel      | Sunrise Point-LP USB 3.0 ... | 6     | xhci_hcd   | CF93488B90 |
| 8086:9d2f | 17aa:3862 | Intel      | Sunrise Point-LP USB 3.0 ... | 6     | xhci_hcd   | 570666D7D6 |
| 8086:9d2f | 1ae0:006b | Intel      | Sunrise Point-LP USB 3.0 ... | 6     | xhci_hcd   | CBC1BB3811 |
| 8086:9ded | 1028:089e | Intel      | Cannon Point-LP USB 3.1 x... | 6     | xhci_hcd   | C6692154A1 |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:694e | 1002:694e | AMD        | Polaris 22 XL [Radeon RX ... | 1     | amdgpu     | 07A9851CD6 |
| 10ec-b... |           | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 1     | rtwpci     | D6005821D4 |

