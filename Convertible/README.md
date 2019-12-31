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
   * [ Wireless controller ](#wireless-controller-pci)
   * [ Others ](#others-pci)

PCI Devices
-----------

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1452 |           | AMD        | Family 17h (Models 00h-1f... | 14    |            | B0FCF85E0D |
| 1022:15db | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 14    | pcieport   | B0FCF85E0D |
| 1022:15e8 |           | AMD        | Raven/Raven2 Device 24: F... | 14    |            | B0FCF85E0D |
| 1022:15e9 |           | AMD        | Raven/Raven2 Device 24: F... | 14    |            | B0FCF85E0D |
| 1022:15ea |           | AMD        | Raven/Raven2 Device 24: F... | 14    |            | B0FCF85E0D |
| 1022:15eb |           | AMD        | Raven/Raven2 Device 24: F... | 14    | k10temp    | B0FCF85E0D |
| 1022:15ec |           | AMD        | Raven/Raven2 Device 24: F... | 14    |            | B0FCF85E0D |
| 1022:15ed |           | AMD        | Raven/Raven2 Device 24: F... | 14    |            | B0FCF85E0D |
| 1022:15ee |           | AMD        | Raven/Raven2 Device 24: F... | 14    |            | B0FCF85E0D |
| 1022:15ef |           | AMD        | Raven/Raven2 Device 24: F... | 14    |            | B0FCF85E0D |
| 1022:15dc | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 8     | pcieport   | 447751C623 |
| 8086:2280 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 8     | iosf_mb... | C3F66A8352 |
| 8086:229c | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 8     | lpc_ich    | C3F66A8352 |
| 8086:5ae8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | lpc_ich    | CBA368D785 |
| 8086:5af0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     |            | CBA368D785 |
| 8086:15d3 | 2222:1111 | Intel      | JHL6540 Thunderbolt 3 Bri... | 5     | pcieport   | AC8A41B387 |
| 8086:5904 | 103c:830f | Intel      | Xeon E3-1200 v6/7th Gen C... | 5     | skl_uncore | 0ECB13EDBF |
| 8086:5904 | 103c:8486 | Intel      | Xeon E3-1200 v6/7th Gen C... | 5     | skl_uncore | 7DEF867A41 |
| 8086:5914 | 103c:83b9 | Intel      | Xeon E3-1200 v6/7th Gen C... | 5     | skl_uncore | C28AED72AA |
| 8086:5ad7 |           | Intel      | Celeron N3350/Pentium N42... | 5     | pcieport   | CBA368D785 |
| 8086:9d10 | 103c:83b9 | Intel      | Sunrise Point-LP PCI Expr... | 5     | pcieport   | C28AED72AA |
| 8086:9d11 | 103c:83b9 | Intel      | Sunrise Point-LP PCI Expr... | 5     | pcieport   | C28AED72AA |
| 8086:9d14 | 103c:83b9 | Intel      | Sunrise Point-LP PCI Expr... | 5     | pcieport   | C28AED72AA |
| 8086:9d14 | 17aa:3835 | Intel      | Sunrise Point-LP PCI Expr... | 5     | pcieport   | 33D7D63C6D |
| 8086:9d15 | 103c:8486 | Intel      | Sunrise Point-LP PCI Expr... | 5     | pcieport   | 7DEF867A41 |
| 8086:9d15 | 103c:8488 | Intel      | Sunrise Point-LP PCI Expr... | 5     | pcieport   | 59D61DD321 |
| 8086:9d15 | 17aa:382f | Intel      | Sunrise Point-LP PCI Expr... | 5     | pcieport   | 33D7D63C6D |
| 8086:9d18 | 103c:830f | Intel      | Sunrise Point-LP PCI Expr... | 5     | pcieport   | 0ECB13EDBF |
| 8086:9d18 | 103c:83b9 | Intel      | Sunrise Point-LP PCI Expr... | 5     | pcieport   | C28AED72AA |
| 8086:9d19 | 103c:830f | Intel      | Sunrise Point-LP PCI Expr... | 5     | pcieport   | 0ECB13EDBF |
| 8086:9d4e | 103c:830f | Intel      | Sunrise Point LPC Control... | 5     |            | 0ECB13EDBF |
| 8086:9d4e | 103c:83b9 | Intel      | Sunrise Point LPC Control... | 5     |            | C28AED72AA |
| 8086:9d4e | 103c:8486 | Intel      | Sunrise Point LPC Control... | 5     |            | 7DEF867A41 |
| 8086:9d4e | 103c:8488 | Intel      | Sunrise Point LPC Control... | 5     |            | 59D61DD321 |
| 1022:15d0 | 103c:8496 | AMD        | Raven/Raven2 Root Complex    | 4     |            | 31DDC7FDCB |
| 1022:15d0 | 103c:85dd | AMD        | Raven/Raven2 Root Complex    | 4     |            | D6005821D4 |
| 1022:15d0 | 17aa:380a | AMD        | Raven/Raven2 Root Complex    | 4     |            | B0FCF85E0D |
| 1022:15d3 | 1022:1453 | AMD        | Raven/Raven2 PCIe GPP Bri... | 4     | pcieport   | B0FCF85E0D |
| 1022:15d3 | 103c:8496 | AMD        | Raven/Raven2 PCIe GPP Bri... | 4     | pcieport   | 31DDC7FDCB |
| 1022:15d3 | 103c:85dd | AMD        | Raven/Raven2 PCIe GPP Bri... | 4     | pcieport   | D6005821D4 |
| 1022:790e | 103c:8496 | AMD        | FCH LPC Bridge               | 4     |            | 31DDC7FDCB |
| 1022:790e | 103c:85dd | AMD        | FCH LPC Bridge               | 4     |            | D6005821D4 |
| 1022:790e | 17aa:3819 | AMD        | FCH LPC Bridge               | 4     |            | B0FCF85E0D |
| 8086:15d3 | 17aa:2292 | Intel      | JHL6540 Thunderbolt 3 Bri... | 4     | pcieport   | 7C5B2D05AE |
| 8086:3e34 | 17aa:3808 | Intel      | Coffee Lake HOST and DRAM... | 4     | skl_uncore | C7DFFC3F2A |
| 8086:5904 | 17aa:224e | Intel      | Xeon E3-1200 v6/7th Gen C... | 4     | skl_uncore | 66ACB89125 |
| 8086:5914 | 103c:8488 | Intel      | Xeon E3-1200 v6/7th Gen C... | 4     | skl_uncore | 59D61DD321 |
| 8086:9d10 | 17aa:224e | Intel      | Sunrise Point-LP PCI Expr... | 4     | pcieport   | 66ACB89125 |
| 8086:9d12 | 17aa:224e | Intel      | Sunrise Point-LP PCI Expr... | 4     | pcieport   | 66ACB89125 |
| 8086:9d14 | 17aa:224e | Intel      | Sunrise Point-LP PCI Expr... | 4     | pcieport   | 66ACB89125 |
| 8086:9d18 | 103c:8488 | Intel      | Sunrise Point-LP PCI Expr... | 4     | pcieport   | 59D61DD321 |
| 8086:9d18 | 17aa:224e | Intel      | Sunrise Point-LP PCI Expr... | 4     | pcieport   | 66ACB89125 |
| 8086:9d4e | 17aa:3803 | Intel      | Sunrise Point LPC Control... | 4     |            | 419565138F |
| 8086:9d84 | 17aa:380c | Intel      | Cannon Point-LP LPC Contr... | 4     |            | C7DFFC3F2A |
| 8086:9db0 | 17aa:380f | Intel      | Cannon Point-LP PCI Expre... | 4     | pcieport   | C7DFFC3F2A |
| 8086:9db6 | 8086:9db6 | Intel      | Cannon Point-LP PCI Expre... | 4     | pcieport   | C7DFFC3F2A |
| 8086:9db7 | 8086:9db7 | Intel      | 300 Series Chipset PCIe P... | 4     | pcieport   | C7DFFC3F2A |
| 1022:157b |           | AMD        | Family 15h (Models 60h-6f... | 3     |            | EEE03F79BD |
| 1022:157d |           | AMD        | Carrizo Audio Dummy Host ... | 3     |            | EEE03F79BD |
| 8086:15d3 |           | Intel      | JHL6540 Thunderbolt 3 Bri... | 3     | pcieport   | A2C7E96A52 |
| 8086:15d3 | 103c:8514 | Intel      | JHL6540 Thunderbolt 3 Bri... | 3     | pcieport   | 0CF9D0AFB9 |
| 8086:1904 | 103c:80d1 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | skl_uncore | FD3B38A3F5 |
| 8086:1904 | 17aa:2238 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | skl_uncore | 3504F119EA |
| 8086:1904 | 17aa:380b | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | skl_uncore | 5B8D494C04 |
| 8086:2280 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 3     | iosf_mb... | 9FAC88C07A |
| 8086:229c | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 3     | lpc_ich    | 9FAC88C07A |
| 8086:22c8 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 3     | pcieport   | 9FAC88C07A |
| 8086:22ca | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 3     | pcieport   | 9FAC88C07A |
| 8086:31d8 | 8086:7270 | Intel      | Gemini Lake PCI Express R... | 3     | pcieport   | 991764DD3F |
| 8086:31e8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     |            | 991764DD3F |
| 8086:3e34 | 103c:8514 | Intel      | Coffee Lake HOST and DRAM... | 3     | skl_uncore | 0CF9D0AFB9 |
| 8086:3e34 | 17aa:2292 | Intel      | Coffee Lake HOST and DRAM... | 3     | skl_uncore | 7C5B2D05AE |
| 8086:5904 | 17aa:381d | Intel      | Xeon E3-1200 v6/7th Gen C... | 3     | skl_uncore | 6D14F41FBD |
| 8086:5904 | 17aa:382b | Intel      | Xeon E3-1200 v6/7th Gen C... | 3     | skl_uncore | 33D7D63C6D |
| 8086:5914 | 103c:827f | Intel      | Xeon E3-1200 v6/7th Gen C... | 3     | skl_uncore | 1DB4A76555 |
| 8086:5914 | 103c:84d8 | Intel      | Xeon E3-1200 v6/7th Gen C... | 3     | skl_uncore | 9B4E7338B0 |
| 8086:5914 | 17aa:3821 | Intel      | Xeon E3-1200 v6/7th Gen C... | 3     | skl_uncore | 5A7A4AFFFB |
| 8086:9d10 | 103c:80d1 | Intel      | Sunrise Point-LP PCI Expr... | 3     | shpchp     | FD3B38A3F5 |
| 8086:9d10 | 103c:827f | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 1DB4A76555 |
| 8086:9d10 | 17aa:2238 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 3504F119EA |
| 8086:9d10 | 17aa:384f | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 5A7A4AFFFB |
| 8086:9d12 | 17aa:2238 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 3504F119EA |
| 8086:9d14 | 103c:80d1 | Intel      | Sunrise Point-LP PCI Expr... | 3     | shpchp     | FD3B38A3F5 |
| 8086:9d14 | 103c:827f | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 1DB4A76555 |
| 8086:9d14 | 103c:84d8 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 9B4E7338B0 |
| 8086:9d14 | 17aa:3801 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 5B8D494C04 |
| 8086:9d14 | 17aa:385b | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 5A7A4AFFFB |
| 8086:9d15 | 103c:80d1 | Intel      | Sunrise Point-LP PCI Expr... | 3     | shpchp     | FD3B38A3F5 |
| 8086:9d15 | 103c:84d8 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 9B4E7338B0 |
| 8086:9d15 | 17aa:3801 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 5B8D494C04 |
| 8086:9d15 | 17aa:3813 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 6D14F41FBD |
| 8086:9d16 | 103c:827f | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 1DB4A76555 |
| 8086:9d17 | 103c:827f | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 1DB4A76555 |
| 8086:9d18 | 103c:80d1 | Intel      | Sunrise Point-LP PCI Expr... | 3     | shpchp     | FD3B38A3F5 |
| 8086:9d18 | 103c:827f | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 1DB4A76555 |
| 8086:9d18 | 103c:84d8 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 9B4E7338B0 |
| 8086:9d18 | 17aa:3809 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 5B8D494C04 |
| 8086:9d18 | 17aa:3811 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 6D14F41FBD |
| 8086:9d18 | 17aa:384b | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 5A7A4AFFFB |
| 8086:9d48 | 103c:80d1 | Intel      | Sunrise Point-LP LPC Cont... | 3     |            | FD3B38A3F5 |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:5229 | 17aa:3832 | Realtek... | RTS5229 PCI Express Card ... | 5     | rtsx_pci   | 33D7D63C6D |
| 10ec:522a | 103c:830f | Realtek... | RTS522A PCI Express Card ... | 5     | rtsx_pci   | 0ECB13EDBF |
| 10ec:525a | 103c:83b9 | Realtek... | RTS525A PCI Express Card ... | 5     | rtsx_pci   | C28AED72AA |
| 10ec:522a | 103c:8496 | Realtek... | RTS522A PCI Express Card ... | 4     | rtsx_pci   | 31DDC7FDCB |
| 10ec:522a | 103c:85dd | Realtek... | RTS522A PCI Express Card ... | 4     | rtsx_pci   | D6005821D4 |
| 10ec:525a | 17aa:224e | Realtek... | RTS525A PCI Express Card ... | 4     | rtsx_pci   | 66ACB89125 |
| 10ec:5229 | 103c:82e1 | Realtek... | RTS5229 PCI Express Card ... | 3     | rtsx_pci   | 9FAC88C07A |
| 10ec:5229 | 17aa:380d | Realtek... | RTS5229 PCI Express Card ... | 3     | rtsx_pci   | 5B8D494C04 |
| 10ec:5229 | 17aa:381d | Realtek... | RTS5229 PCI Express Card ... | 3     | rtsx_pci   | 6D14F41FBD |
| 10ec:522a | 103c:80d1 | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | FD3B38A3F5 |
| 10ec:525a | 103c:827f | Realtek... | RTS525A PCI Express Card ... | 3     | rtsx_pci   | 1DB4A76555 |
| 10ec:525a | 103c:8514 | Realtek... | RTS525A PCI Express Card ... | 3     | rtsx_pci   | 0CF9D0AFB9 |
| 10ec:525a | 17aa:2238 | Realtek... | RTS525A PCI Express Card ... | 3     | rtsx_pci   | 3504F119EA |
| 10ec:5229 | 17aa:381b | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | C194639A17 |
| 10ec:522a | 103c:827d | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | E9DECBC4FD |
| 10ec:522a | 103c:8313 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 22FE75A663 |
| 10ec:522a | 103c:83c4 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 65B956E887 |
| 10ec:522a | 17aa:2237 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 6AA622B728 |
| 10ec:522a | 17aa:506c | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 225075209E |
| 10ec:525a | 1028:080d | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx_pci   | 8CA313CDAD |
| 10ec:525a | 103c:82c1 | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx_pci   | A9E42C34F6 |
| 10ec:525a | 103c:8518 | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx_pci   | 969C4C3BCB |
| 10ec:5227 | 103c:802b | Realtek... | RTS5227 PCI Express Card ... | 1     | rtsx_pci   | 07B5ECDCCD |
| 10ec:5227 | 103c:802d | Realtek... | RTS5227 PCI Express Card ... | 1     | rtsx_pci   | D9CA1DBE13 |
| 10ec:5227 | 103c:804e | Realtek... | RTS5227 PCI Express Card ... | 1     | rtsx_pci   | 6F8FD31C2C |
| 10ec:5227 | 103c:81a1 | Realtek... | RTS5227 PCI Express Card ... | 1     | rtsx_pci   | C894E5633B |
| 10ec:5229 | 103c:81aa | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | D103A0F533 |
| 10ec:5229 | 17aa:3810 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | B9FC5DC357 |
| 10ec:522a | 103c:806e | Realtek... | RTS522A PCI Express Card ... | 1     |            | 62A9EF950E |
| 10ec:522a | 103c:80d0 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 97ED13A8C0 |
| 10ec:522a | 103c:8143 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 49796C6747 |
| 10ec:522a | 103c:81ad | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 84C8A9779B |
| 10ec:522a | 103c:8251 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | C77AFE79C3 |
| 10ec:522a | 103c:8311 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | EEE03F79BD |
| 10ec:522a | 103c:8483 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 8B7A2D2A08 |
| 10ec:522a | 103c:8484 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 1B466FC315 |
| 10ec:522a | 103c:8497 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | D9AF75156B |
| 10ec:522a | 103c:85de | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 70F1D3BF36 |
| 10ec:522a | 17aa:506d | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 0818236221 |
| 10ec:522a | 17aa:5077 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | E6D8B9F842 |
| 10ec:522a | 1854:0333 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 6D2724E820 |
| 10ec:525a | 1028:077a | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | 57D57D82FE |
| 10ec:525a | 103c:83ba | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | 3743010FB5 |
| 10ec:525a | 103c:83bb | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | CBA3EC356E |
| 10ec:525a | 103c:8519 | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | D764EA82D5 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | mei_me     | CBA368D785 |
| 8086:9d3a | 103c:830f | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | 0ECB13EDBF |
| 8086:9d3a | 103c:83b9 | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | C28AED72AA |
| 8086:9d3a | 103c:8486 | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | 7DEF867A41 |
| 8086:9d3a | 103c:8488 | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | 59D61DD321 |
| 8086:9d3a | 17aa:383e | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | 33D7D63C6D |
| 8086:9d3a | 17aa:224e | Intel      | Sunrise Point-LP CSME HEC... | 4     | mei_me     | 66ACB89125 |
| 8086:9de0 | 17aa:3805 | Intel      | Cannon Point-LP MEI Contr... | 4     | mei_me     | C7DFFC3F2A |
| 8086:319a | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | mei_me     | 991764DD3F |
| 8086:9d3a | 103c:80d1 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | FD3B38A3F5 |
| 8086:9d3a | 103c:827f | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | 1DB4A76555 |
| 8086:9d3a | 103c:84d8 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | 9B4E7338B0 |
| 8086:9d3a | 17aa:2238 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | 3504F119EA |
| 8086:9d3a | 17aa:3811 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | 5B8D494C04 |
| 8086:9d3a | 17aa:3824 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | 6D14F41FBD |
| 8086:9d3a | 17aa:3868 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | 5A7A4AFFFB |
| 8086:9de0 | 103c:8514 | Intel      | Cannon Point-LP MEI Contr... | 3     | mei_me     | 0CF9D0AFB9 |
| 8086:9de0 | 17aa:2292 | Intel      | Cannon Point-LP MEI Contr... | 3     | mei_me     | 7C5B2D05AE |
| 8086:9d3a | 1028:07aa | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | DFDC8C484F |
| 8086:9d3a | 1028:07eb | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 7EB57A3809 |
| 8086:9d3a | 103c:827d | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | E9DECBC4FD |
| 8086:9d3a | 103c:827e | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 28AF751D12 |
| 8086:9d3a | 103c:82c1 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | A9E42C34F6 |
| 8086:9d3a | 103c:8313 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 22FE75A663 |
| 8086:9d3a | 103c:83c4 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 65B956E887 |
| 8086:9d3a | 103c:8503 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | F6ABCD9B4F |
| 8086:9d3a | 1043:14f0 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | AD2B007CB9 |
| 8086:9d3a | 1043:1c40 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 18B4F9B58E |
| 8086:9d3a | 1043:1c90 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 7BBD1AB6FE |
| 8086:9d3a | 1043:1dc0 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | C0BC126501 |
| 8086:9d3a | 17aa:2237 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 6AA622B728 |
| 8086:9d3a | 17aa:3801 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | FC1E9BDE71 |
| 8086:9d3a | 17aa:3805 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 941DF897AA |
| 8086:9d3a | 17aa:380d | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | C194639A17 |
| 8086:9d3a | 17aa:383d | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 1681EDB0F6 |
| 8086:9d3a | 17aa:3860 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | D16FC3AC03 |
| 8086:9d3a | 17aa:506c | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 225075209E |
| 8086:9de0 | 103c:8518 | Intel      | Cannon Point-LP MEI Contr... | 2     | mei_me     | 969C4C3BCB |
| 8086:a13a | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 2     | mei_me     | 8CA313CDAD |
| 8086:02c7 | 17aa:3801 | Intel      | Comet Lake PCH-LP LPSS: U... | 1     | intel_l... | 702DE7D41F |
| 8086:02e0 | 1028:0950 | Intel      | Comet Lake Management Eng... | 1     |            | 20ABB6DE72 |
| 8086:02e0 | 103c:866e | Intel      | Comet Lake Management Eng... | 1     |            | 8FF42ABD82 |
| 8086:02e0 | 17aa:2292 | Intel      | Comet Lake Management Eng... | 1     | mei_me     | D6B3970321 |
| 8086:02e0 | 17aa:3803 | Intel      | Comet Lake Management Eng... | 1     | mei_me     | 702DE7D41F |
| 8086:02e0 | 17aa:3806 | Intel      | Comet Lake Management Eng... | 1     | mei_me     | A25721AA13 |
| 8086:5a9a | 17aa:3803 | Intel      | Celeron N3350/Pentium N42... | 1     | mei_me     | F8913A087C |
| 8086:5a9c | 17aa:3803 | Intel      | Communication controller     | 1     |            | F8913A087C |
| 8086:5a9e | 17aa:3803 | Intel      | Communication controller     | 1     |            | F8913A087C |
| 8086:9cba | 103c:802d | Intel      | Wildcat Point-LP MEI Cont... | 1     | mei_me     | D9CA1DBE13 |
| 8086:9cba | 103c:806c | Intel      | Wildcat Point-LP MEI Cont... | 1     | mei_me     | 462F2D5347 |
| 8086:9cba | 103c:806e | Intel      | Wildcat Point-LP MEI Cont... | 1     | mei_me     | 62A9EF950E |
| 8086:9d3a | 1025:120d | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | BAE5A5C3DD |
| 8086:9d3a | 1028:077a | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 57D57D82FE |
| 8086:9d3a | 103c:804e | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 6F8FD31C2C |
| 8086:9d3a | 103c:80d0 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 97ED13A8C0 |
| 8086:9d3a | 103c:8143 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 49796C6747 |
| 8086:9d3a | 103c:81a1 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | C894E5633B |
| 8086:9d3a | 103c:81ad | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 84C8A9779B |
| 8086:9d3a | 103c:8251 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | C77AFE79C3 |
| 8086:9d3a | 103c:83ba | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 3743010FB5 |
| 8086:9d3a | 103c:8438 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 7F01433E42 |
| 8086:9d3a | 103c:8483 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 8B7A2D2A08 |
| 8086:9d3a | 103c:8484 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 1B466FC315 |
| 8086:9d3a | 103c:8487 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | C8C863DB3A |
| 8086:9d3a | 1043:12e1 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 93A44B1518 |
| 8086:9d3a | 1043:14c0 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | FA7C5C4F64 |
| 8086:9d3a | 1043:1ab0 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | B2D75821A4 |
| 8086:9d3a | 1043:1b00 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | A9301396F9 |
| 8086:9d3a | 1043:1b40 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | FF2D426E76 |
| 8086:9d3a | 1043:1cf0 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 2C6BCC75CC |
| 8086:9d3a | 144d:c141 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 5B28F6FC87 |
| 8086:9d3a | 144d:c14c | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 6E023867E9 |
| 8086:9d3a | 152d:1147 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 7DA5C4A4FA |
| 8086:9d3a | 17aa:3861 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 3C97527813 |
| 8086:9d3a | 17aa:504c | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 3C1A4327F5 |
| 8086:9d3a | 17aa:5058 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | C65BB14578 |
| 8086:9d3a | 17aa:506d | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 0818236221 |
| 8086:9d3a | 8086:9d3a | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | C3AA237F35 |
| 8086:9de0 | 1028:089e | Intel      | Cannon Point-LP MEI Contr... | 1     | mei_me     | D256E89F2D |
| 8086:9de0 | 1028:089f | Intel      | Cannon Point-LP MEI Contr... | 1     | mei_me     | 70A45F8830 |
| 8086:9de0 | 144d:c812 | Intel      | Cannon Point-LP MEI Contr... | 1     | mei_me     | 3701BEE474 |
| 8086:9de0 | 17aa:2294 | Intel      | Cannon Point-LP MEI Contr... | 1     | mei_me     | 167048774C |
| 8086:9de0 | 17aa:5077 | Intel      | Cannon Point-LP MEI Contr... | 1     | mei_me     | E6D8B9F842 |
| 8086:9de0 | 1854:0333 | Intel      | Cannon Point-LP MEI Contr... | 1     | mei_me     | 6D2724E820 |
| 8086:a13a | 103c:83bb | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | CBA3EC356E |
| 8086:a13a | 17aa:3809 | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | F445F1B326 |
| 8086:a360 | 103c:8519 | Intel      | Cannon Lake PCH HECI Cont... | 1     | mei_me     | D764EA82D5 |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 8     | mei_txe    | C3F66A8352 |
| 1022:15df | 103c:8496 | AMD        | Family 17h (Models 10h-1f... | 4     |            | 31DDC7FDCB |
| 1022:15df | 103c:85dd | AMD        | Family 17h (Models 10h-1f... | 4     |            | D6005821D4 |
| 1022:15df | 17aa:3804 | AMD        | Family 17h (Models 10h-1f... | 4     |            | B0FCF85E0D |
| 8086:2298 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | 9FAC88C07A |
| 1022:1578 | 103c:81aa | AMD        | Carrizo Platform Security... | 1     |            | D103A0F533 |
| 1022:1578 | 103c:8311 | AMD        | Carrizo Platform Security... | 1     |            | EEE03F79BD |
| 1022:1578 | 17aa:3802 | AMD        | Carrizo Platform Security... | 1     |            | B9FC5DC357 |
| 1022:15df | 103c:8497 | AMD        | Family 17h (Models 10h-1f... | 1     |            | D9AF75156B |
| 1022:15df | 103c:85de | AMD        | Family 17h (Models 10h-1f... | 1     |            | 70F1D3BF36 |
| 8086:0f18 | 103c:802b | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | 07B5ECDCCD |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 8     | i915       | C3F66A8352 |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics 500              | 6     | i915       | CBA368D785 |
| 8086:5916 | 103c:830f | Intel      | HD Graphics 620              | 5     | i915       | 0ECB13EDBF |
| 8086:5917 | 103c:83b9 | Intel      | UHD Graphics 620             | 5     | i915       | C28AED72AA |
| 8086:5917 | 103c:8486 | Intel      | UHD Graphics 620             | 5     | i915       | 7DEF867A41 |
| 8086:5917 | 103c:8488 | Intel      | UHD Graphics 620             | 5     | i915       | 59D61DD321 |
| 1002:15d8 | 103c:85dd | AMD        | Picasso                      | 4     | amdgpu     | D6005821D4 |
| 1002:15dd | 103c:8496 | AMD        | Raven Ridge [Radeon Vega ... | 4     | amdgpu     | 31DDC7FDCB |
| 1002:15dd | 17aa:39ff | AMD        | Raven Ridge [Radeon Vega ... | 4     | amdgpu     | B0FCF85E0D |
| 8086:5916 | 17aa:224e | Intel      | HD Graphics 620              | 4     | i915       | 66ACB89125 |
| 10de:1d10 | 103c:827f | Nvidia     | GP108M [GeForce MX150]       | 3     | nouveau    | 1DB4A76555 |
| 8086:1916 | 103c:80d1 | Intel      | Skylake GT2 [HD Graphics ... | 3     | i915       | FD3B38A3F5 |
| 8086:1916 | 17aa:2238 | Intel      | Skylake GT2 [HD Graphics ... | 3     | i915       | 3504F119EA |
| 8086:22b1 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 3     | i915       | 9FAC88C07A |
| 8086:3ea0 | 103c:8514 | Intel      | UHD Graphics 620 (Whiskey... | 3     | i915       | 0CF9D0AFB9 |
| 8086:3ea0 | 17aa:2292 | Intel      | UHD Graphics 620 (Whiskey... | 3     | i915       | 7C5B2D05AE |
| 8086:3ea0 | 17aa:39f4 | Intel      | UHD Graphics 620 (Whiskey... | 3     | i915       | CDF9A3949B |
| 8086:5917 | 103c:827f | Intel      | UHD Graphics 620             | 3     | i915       | 1DB4A76555 |
| 8086:5917 | 103c:84d8 | Intel      | UHD Graphics 620             | 3     | i915       | 9B4E7338B0 |
| 8086:5917 | 17aa:3803 | Intel      | UHD Graphics 620             | 3     | i915       | 5A7A4AFFFB |
| 1002:694e | 1028:080d | ATI Tec... | Polaris 22 XL [Radeon RX ... | 2     | amdgpu     | 8CA313CDAD |
| 10de:134d | 103c:82c1 | Nvidia     | GM108M [GeForce 940MX]       | 2     |            | A9E42C34F6 |
| 10de:134d | 17aa:39ce | Nvidia     | GM108M [GeForce 940MX]       | 2     | nouveau    | 6674277B6A |
| 10de:174d | 103c:84d8 | Nvidia     | GM108M [GeForce MX130]       | 2     | nouveau    | 9B4E7338B0 |
| 10de:1d10 | 103c:8518 | Nvidia     | GP108M [GeForce MX150]       | 2     | nouveau    | 969C4C3BCB |
| 8086:1906 | 17aa:381d | Intel      | HD Graphics 510              | 2     | i915       | 4ACED2B19A |
| 8086:1916 | 17aa:2237 | Intel      | Skylake GT2 [HD Graphics ... | 2     | i915       | 6AA622B728 |
| 8086:3185 | 8086:2212 | Intel      | UHD Graphics 605             | 2     | i915       | 991764DD3F |
| 8086:3ea0 | 103c:8518 | Intel      | UHD Graphics 620 (Whiskey... | 2     | i915       | 969C4C3BCB |
| 8086:5916 | 1028:07aa | Intel      | HD Graphics 620              | 2     | i915       | DFDC8C484F |
| 8086:5916 | 103c:827d | Intel      | HD Graphics 620              | 2     | i915       | E9DECBC4FD |
| 8086:5916 | 103c:827e | Intel      | HD Graphics 620              | 2     | i915       | 28AF751D12 |
| 8086:5916 | 103c:82c1 | Intel      | HD Graphics 620              | 2     | i915       | A9E42C34F6 |
| 8086:5916 | 103c:8313 | Intel      | HD Graphics 620              | 2     | i915       | 22FE75A663 |
| 8086:5916 | 1043:14f0 | Intel      | HD Graphics 620              | 2     | i915       | AD2B007CB9 |
| 8086:5916 | 17aa:3801 | Intel      | HD Graphics 620              | 2     | i915       | 941DF897AA |
| 8086:5916 | 17aa:3987 | Intel      | HD Graphics 620              | 2     | i915       | 419565138F |
| 8086:5916 | 17aa:3988 | Intel      | HD Graphics 620              | 2     | i915       | 1681EDB0F6 |
| 8086:5916 | 17aa:39f3 | Intel      | HD Graphics 620              | 2     | i915       | 6D14F41FBD |
| 8086:5917 | 1028:07eb | Intel      | UHD Graphics 620             | 2     | i915       | 7EB57A3809 |
| 8086:5917 | 103c:83c4 | Intel      | UHD Graphics 620             | 2     | i915       | 65B956E887 |
| 8086:5917 | 1043:1c40 | Intel      | UHD Graphics 620             | 2     | i915       | 18B4F9B58E |
| 8086:5917 | 1043:1c90 | Intel      | UHD Graphics 620             | 2     | i915       | 7BBD1AB6FE |
| 8086:5917 | 1043:1dc0 | Intel      | UHD Graphics 620             | 2     | i915       | C0BC126501 |
| 8086:5917 | 17aa:39ce | Intel      | UHD Graphics 620             | 2     | i915       | 6674277B6A |
| 8086:5917 | 17aa:506c | Intel      | UHD Graphics 620             | 2     | i915       | 225075209E |
| 8086:591b | 1028:080d | Intel      | HD Graphics 630              | 2     | i915       | 8CA313CDAD |
| 8086:591c | 103c:8503 | Intel      | UHD Graphics 615             | 2     | i915       | F6ABCD9B4F |
| 8086:591e | 1ae0:2212 | Intel      | HD Graphics 615              | 2     | i915       | 7CCE37A416 |
| 1002:15d8 | 103c:85de | AMD        | Picasso                      | 1     | amdgpu     | 70F1D3BF36 |
| 1002:15dd | 103c:8497 | AMD        | Raven Ridge [Radeon Vega ... | 1     | amdgpu     | D9AF75156B |
| 1002:6900 | 17aa:39bc | AMD        | Topaz XT [Radeon R7 M260/... | 1     | amdgpu     | A388F4B414 |
| 1002:694e | 103c:83bb | AMD        | Polaris 22 XL [Radeon RX ... | 1     | amdgpu     | CBA3EC356E |
| 1002:9874 | 103c:81aa | AMD        | Wani [Radeon R5/R6/R7 Gra... | 1     | amdgpu     | D103A0F533 |
| 1002:9874 | 103c:8311 | AMD        | Wani [Radeon R5/R6/R7 Gra... | 1     | amdgpu     | EEE03F79BD |
| 1002:98e4 | 17aa:3804 | AMD        | Stoney [Radeon R2/R3/R4/R... | 1     | amdgpu     | B9FC5DC357 |
| 10de:1346 | 103c:80d0 | Nvidia     | GM108M [GeForce 930M]        | 1     | nvidia     | 97ED13A8C0 |
| 10de:134d | 144d:c14c | Nvidia     | GM108M [GeForce 940MX]       | 1     |            | 6E023867E9 |
| 10de:134d | 17aa:39f4 | Nvidia     | GM108M [GeForce 940MX]       | 1     | nvidia     | 5E49D8DD4C |
| 10de:137a | 17aa:505a | Nvidia     | GM108GLM [Quadro K620M / ... | 1     | nvidia     | 3C1A4327F5 |
| 10de:174d | 1028:089e | Nvidia     | GM108M [GeForce MX130]       | 1     | nouveau    | D256E89F2D |
| 10de:174d | 103c:8487 | Nvidia     | GM108M [GeForce MX130]       | 1     | nouveau    | C8C863DB3A |
| 10de:174d | 17aa:398c | Nvidia     | GM108M [GeForce MX130]       | 1     | nouveau    | FC1E9BDE71 |
| 10de:1c8c | 103c:8519 | Nvidia     | GP107M [GeForce GTX 1050 ... | 1     | vfio_pci   | D764EA82D5 |
| 10de:1c8d | 17aa:39ab | Nvidia     | GP107M [GeForce GTX 1050 ... | 1     |            | 27307BC4CF |
| 10de:1c8d | 17aa:39cb | Nvidia     | GP107M [GeForce GTX 1050 ... | 1     | nvidia     | F445F1B326 |
| 10de:1c8d | 17aa:5067 | Nvidia     | GP107M [GeForce GTX 1050 ... | 1     | nouveau    | A2C7E96A52 |
| 10de:1d10 | 103c:83ba | Nvidia     | GP108M [GeForce MX150]       | 1     |            | 3743010FB5 |
| 10de:1d10 | 103c:8484 | Nvidia     | GP108M [GeForce MX150]       | 1     | nvidia     | 1B466FC315 |
| 10de:1d10 | 144d:c812 | Nvidia     | GP108M [GeForce MX150]       | 1     | nvidia     | 3701BEE474 |
| 10de:1d12 | 1043:15ce | Nvidia     | GP108M [GeForce MX150]       | 1     | nvidia     | 864F436F16 |
| 8086:0f31 | 103c:802b | Intel      | Atom Processor Z36xxx/Z37... | 1     | i915       | 07B5ECDCCD |
| 8086:1616 | 103c:802d | Intel      | HD Graphics 5500             | 1     | i915       | D9CA1DBE13 |
| 8086:1616 | 103c:806c | Intel      | HD Graphics 5500             | 1     | i915       | 462F2D5347 |
| 8086:1616 | 103c:806e | Intel      | HD Graphics 5500             | 1     | i915       | 62A9EF950E |
| 8086:1916 | 103c:804e | Intel      | Skylake GT2 [HD Graphics ... | 1     | i915       | 6F8FD31C2C |
| 8086:1916 | 103c:80d0 | Intel      | Skylake GT2 [HD Graphics ... | 1     | i915       | 97ED13A8C0 |
| 8086:1916 | 103c:8143 | Intel      | Skylake GT2 [HD Graphics ... | 1     | i915       | 49796C6747 |
| 8086:1916 | 103c:81a1 | Intel      | Skylake GT2 [HD Graphics ... | 1     | i915       | C894E5633B |
| 8086:1916 | 144d:c141 | Intel      | Skylake GT2 [HD Graphics ... | 1     | i915       | 5B28F6FC87 |
| 8086:1916 | 17aa:5058 | Intel      | Skylake GT2 [HD Graphics ... | 1     | i915       | C65BB14578 |
| 8086:1916 | 17aa:505a | Intel      | Skylake GT2 [HD Graphics ... | 1     | i915       | 3C1A4327F5 |
| 8086:1921 | 17aa:39f2 | Intel      | HD Graphics 520              | 1     | i915       | 5B8D494C04 |
| 8086:3184 | 1e39:a001 | Intel      | UHD Graphics 605             | 1     | i915       | 56A7BF3D18 |
| 8086:3e9b | 103c:8519 | Intel      | UHD Graphics 630 (Mobile)    | 1     | i915       | D764EA82D5 |
| 8086:3ea0 | 1028:089e | Intel      | UHD Graphics 620 (Whiskey... | 1     | i915       | D256E89F2D |
| 8086:3ea0 | 1028:089f | Intel      | UHD Graphics 620 (Whiskey... | 1     | i915       | 70A45F8830 |
| 8086:3ea0 | 144d:c812 | Intel      | UHD Graphics 620 (Whiskey... | 1     | i915       | 3701BEE474 |
| 8086:3ea0 | 17aa:2294 | Intel      | UHD Graphics 620 (Whiskey... | 1     | i915       | 167048774C |
| 8086:3ea0 | 17aa:39f3 | Intel      | UHD Graphics 620 (Whiskey... | 1     | i915       | C7DFFC3F2A |
| 8086:3ea0 | 17aa:5077 | Intel      | UHD Graphics 620 (Whiskey... | 1     | i915       | E6D8B9F842 |
| 8086:3ea0 | 1854:0333 | Intel      | UHD Graphics 620 (Whiskey... | 1     | i915       | 6D2724E820 |
| 8086:5906 | 17aa:39da | Intel      | Kaby Lake-U GT1 Integrate... | 1     | i915       | 33D7D63C6D |
| 8086:5916 | 103c:81ad | Intel      | HD Graphics 620              | 1     | i915       | 84C8A9779B |
| 8086:5916 | 103c:8251 | Intel      | HD Graphics 620              | 1     | i915       | C77AFE79C3 |
| 8086:5916 | 1043:14c0 | Intel      | HD Graphics 620              | 1     | i915       | FA7C5C4F64 |
| 8086:5916 | 1043:1ab0 | Intel      | HD Graphics 620              | 1     | i915       | B2D75821A4 |
| 8086:5916 | 144d:c14c | Intel      | HD Graphics 620              | 1     | i915       | 6E023867E9 |
| 8086:5916 | 152d:1147 | Intel      | HD Graphics 620              | 1     | i915       | 7DA5C4A4FA |
| 8086:5916 | 17aa:39bc | Intel      | HD Graphics 620              | 1     | i915       | A388F4B414 |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15d1 | 103c:8496 | AMD        | Raven/Raven2 IOMMU           | 4     |            | 31DDC7FDCB |
| 1022:15d1 | 103c:85dd | AMD        | Raven/Raven2 IOMMU           | 4     |            | D6005821D4 |
| 1022:15d1 | 17aa:3809 | AMD        | Raven/Raven2 IOMMU           | 4     |            | B0FCF85E0D |
| 1022:1577 | 103c:81aa | AMD        | Family 15h (Models 60h-6f... | 1     |            | D103A0F533 |
| 1022:1577 | 103c:8311 | AMD        | Family 15h (Models 60h-6f... | 1     |            | EEE03F79BD |
| 1022:1577 | 17aa:3806 | AMD        | Family 15h (Models 60h-6f... | 1     |            | B9FC5DC357 |
| 1022:15d1 | 103c:8497 | AMD        | Raven/Raven2 IOMMU           | 1     |            | D9AF75156B |
| 1022:15d1 | 103c:85de | AMD        | Raven/Raven2 IOMMU           | 1     |            | 70F1D3BF36 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d21 | 103c:830f | Intel      | Sunrise Point-LP PMC         | 5     |            | 0ECB13EDBF |
| 8086:9d21 | 103c:83b9 | Intel      | Sunrise Point-LP PMC         | 5     |            | C28AED72AA |
| 8086:9d21 | 103c:8486 | Intel      | Sunrise Point-LP PMC         | 5     |            | 7DEF867A41 |
| 8086:9d21 | 103c:8488 | Intel      | Sunrise Point-LP PMC         | 5     |            | 59D61DD321 |
| 8086:9d21 | 17aa:383d | Intel      | Sunrise Point-LP PMC         | 5     |            | 33D7D63C6D |
| 8086:9d21 | 17aa:224e | Intel      | Sunrise Point-LP PMC         | 4     | intel_p... | 66ACB89125 |
| 8086:9def |           | Intel      | Cannon Point-LP Shared SRAM  | 4     |            | 7C5B2D05AE |
| 8086:9def | 8086:9def | Intel      | Cannon Point-LP Shared SRAM  | 4     |            | C7DFFC3F2A |
| 8086:9d21 | 103c:80d1 | Intel      | Sunrise Point-LP PMC         | 3     |            | FD3B38A3F5 |
| 8086:9d21 | 103c:827f | Intel      | Sunrise Point-LP PMC         | 3     |            | 1DB4A76555 |
| 8086:9d21 | 103c:84d8 | Intel      | Sunrise Point-LP PMC         | 3     |            | 9B4E7338B0 |
| 8086:9d21 | 17aa:2238 | Intel      | Sunrise Point-LP PMC         | 3     |            | 3504F119EA |
| 8086:9d21 | 17aa:3811 | Intel      | Sunrise Point-LP PMC         | 3     |            | 5B8D494C04 |
| 8086:9d21 | 17aa:3823 | Intel      | Sunrise Point-LP PMC         | 3     |            | 6D14F41FBD |
| 8086:9d21 | 17aa:386c | Intel      | Sunrise Point-LP PMC         | 3     |            | 5A7A4AFFFB |
| 8086:9def | 103c:8514 | Intel      | Cannon Point-LP Shared SRAM  | 3     |            | 0CF9D0AFB9 |
| 8086:9d21 | 1028:07aa | Intel      | Sunrise Point-LP PMC         | 2     |            | DFDC8C484F |
| 8086:9d21 | 1028:07eb | Intel      | Sunrise Point-LP PMC         | 2     |            | 7EB57A3809 |
| 8086:9d21 | 103c:827d | Intel      | Sunrise Point-LP PMC         | 2     |            | E9DECBC4FD |
| 8086:9d21 | 103c:827e | Intel      | Sunrise Point-LP PMC         | 2     |            | 28AF751D12 |
| 8086:9d21 | 103c:82c1 | Intel      | Sunrise Point-LP PMC         | 2     |            | A9E42C34F6 |
| 8086:9d21 | 103c:8313 | Intel      | Sunrise Point-LP PMC         | 2     |            | 22FE75A663 |
| 8086:9d21 | 103c:83c4 | Intel      | Sunrise Point-LP PMC         | 2     |            | 65B956E887 |
| 8086:9d21 | 103c:8503 | Intel      | Sunrise Point-LP PMC         | 2     |            | F6ABCD9B4F |
| 8086:9d21 | 1043:14f0 | Intel      | Sunrise Point-LP PMC         | 2     |            | AD2B007CB9 |
| 8086:9d21 | 1043:1c40 | Intel      | Sunrise Point-LP PMC         | 2     |            | 18B4F9B58E |
| 8086:9d21 | 1043:1c90 | Intel      | Sunrise Point-LP PMC         | 2     |            | 7BBD1AB6FE |
| 8086:9d21 | 1043:1dc0 | Intel      | Sunrise Point-LP PMC         | 2     |            | C0BC126501 |
| 8086:9d21 | 17aa:2237 | Intel      | Sunrise Point-LP PMC         | 2     |            | 6AA622B728 |
| 8086:9d21 | 17aa:3805 | Intel      | Sunrise Point-LP PMC         | 2     |            | 941DF897AA |
| 8086:9d21 | 17aa:380b | Intel      | Sunrise Point-LP PMC         | 2     |            | C194639A17 |
| 8086:9d21 | 17aa:383f | Intel      | Sunrise Point-LP PMC         | 2     |            | 1681EDB0F6 |
| 8086:9d21 | 17aa:3863 | Intel      | Sunrise Point-LP PMC         | 2     |            | D16FC3AC03 |
| 8086:9d21 | 17aa:3866 | Intel      | Sunrise Point-LP PMC         | 2     |            | FC1E9BDE71 |
| 8086:9d21 | 17aa:506c | Intel      | Sunrise Point-LP PMC         | 2     |            | 225075209E |
| 8086:9d21 | 1ae0:006b | Intel      | Sunrise Point-LP PMC         | 2     |            | 7CCE37A416 |
| 8086:9def | 103c:8518 | Intel      | Cannon Point-LP Shared SRAM  | 2     |            | 969C4C3BCB |
| 8086:a121 | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 2     |            | 8CA313CDAD |
| 8086:02ef | 1028:0950 | Intel      | Comet Lake PCH-LP Shared ... | 1     |            | 20ABB6DE72 |
| 8086:02ef | 103c:866e | Intel      | Comet Lake PCH-LP Shared ... | 1     |            | 8FF42ABD82 |
| 8086:02ef | 17aa:2292 | Intel      | Comet Lake PCH-LP Shared ... | 1     |            | D6B3970321 |
| 8086:02ef | 17aa:3805 | Intel      | Comet Lake PCH-LP Shared ... | 1     |            | 702DE7D41F |
| 8086:02ef | 17aa:3806 | Intel      | Comet Lake PCH-LP Shared ... | 1     |            | A25721AA13 |
| 8086:9d21 | 1025:120d | Intel      | Sunrise Point-LP PMC         | 1     |            | BAE5A5C3DD |
| 8086:9d21 | 1028:077a | Intel      | Sunrise Point-LP PMC         | 1     |            | 57D57D82FE |
| 8086:9d21 | 103c:804e | Intel      | Sunrise Point-LP PMC         | 1     |            | 6F8FD31C2C |
| 8086:9d21 | 103c:80d0 | Intel      | Sunrise Point-LP PMC         | 1     |            | 97ED13A8C0 |
| 8086:9d21 | 103c:8143 | Intel      | Sunrise Point-LP PMC         | 1     |            | 49796C6747 |
| 8086:9d21 | 103c:81a1 | Intel      | Sunrise Point-LP PMC         | 1     |            | C894E5633B |
| 8086:9d21 | 103c:81ad | Intel      | Sunrise Point-LP PMC         | 1     |            | 84C8A9779B |
| 8086:9d21 | 103c:8251 | Intel      | Sunrise Point-LP PMC         | 1     |            | C77AFE79C3 |
| 8086:9d21 | 103c:83ba | Intel      | Sunrise Point-LP PMC         | 1     |            | 3743010FB5 |
| 8086:9d21 | 103c:8438 | Intel      | Sunrise Point-LP PMC         | 1     |            | 7F01433E42 |
| 8086:9d21 | 103c:8483 | Intel      | Sunrise Point-LP PMC         | 1     |            | 8B7A2D2A08 |
| 8086:9d21 | 103c:8484 | Intel      | Sunrise Point-LP PMC         | 1     |            | 1B466FC315 |
| 8086:9d21 | 103c:8487 | Intel      | Sunrise Point-LP PMC         | 1     |            | C8C863DB3A |
| 8086:9d21 | 1043:12e1 | Intel      | Sunrise Point-LP PMC         | 1     |            | 93A44B1518 |
| 8086:9d21 | 1043:14c0 | Intel      | Sunrise Point-LP PMC         | 1     |            | FA7C5C4F64 |
| 8086:9d21 | 1043:1ab0 | Intel      | Sunrise Point-LP PMC         | 1     |            | B2D75821A4 |
| 8086:9d21 | 1043:1b00 | Intel      | Sunrise Point-LP PMC         | 1     |            | A9301396F9 |
| 8086:9d21 | 1043:1b40 | Intel      | Sunrise Point-LP PMC         | 1     |            | FF2D426E76 |
| 8086:9d21 | 1043:1cf0 | Intel      | Sunrise Point-LP PMC         | 1     |            | 2C6BCC75CC |
| 8086:9d21 | 144d:c141 | Intel      | Sunrise Point-LP PMC         | 1     |            | 5B28F6FC87 |
| 8086:9d21 | 144d:c14c | Intel      | Sunrise Point-LP PMC         | 1     |            | 6E023867E9 |
| 8086:9d21 | 152d:1147 | Intel      | Sunrise Point-LP PMC         | 1     |            | 7DA5C4A4FA |
| 8086:9d21 | 17aa:3864 | Intel      | Sunrise Point-LP PMC         | 1     |            | 3C97527813 |
| 8086:9d21 | 17aa:504c | Intel      | Sunrise Point-LP PMC         | 1     |            | 3C1A4327F5 |
| 8086:9d21 | 17aa:5058 | Intel      | Sunrise Point-LP PMC         | 1     |            | C65BB14578 |
| 8086:9d21 | 17aa:506d | Intel      | Sunrise Point-LP PMC         | 1     |            | 0818236221 |
| 8086:9d21 | 8086:9d21 | Intel      | Sunrise Point-LP PMC         | 1     |            | C3AA237F35 |
| 8086:9def | 1028:089e | Intel      | Cannon Point-LP Shared SRAM  | 1     |            | D256E89F2D |
| 8086:9def | 1028:089f | Intel      | Cannon Point-LP Shared SRAM  | 1     |            | 70A45F8830 |
| 8086:9def | 17aa:5077 | Intel      | Cannon Point-LP Shared SRAM  | 1     |            | E6D8B9F842 |
| 8086:9def | 1854:0333 | Intel      | Cannon Point-LP Shared SRAM  | 1     |            | 6D2724E820 |
| 8086:9def | 8086:7270 | Intel      | Cannon Point-LP Shared SRAM  | 1     |            | 3701BEE474 |
| 8086:a121 | 103c:83bb | Intel      | 100 Series/C230 Series Ch... | 1     |            | CBA3EC356E |
| 8086:a121 | 17aa:380f | Intel      | 100 Series/C230 Series Ch... | 1     |            | F445F1B326 |
| 8086:a36f | 103c:8519 | Intel      | Cannon Lake PCH Shared SRAM  | 1     |            | D764EA82D5 |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 8     | intel_a... | C3F66A8352 |
| 1022:15e2 | 103c:85dd | AMD        | Raven/Raven2/FireFlight/R... | 4     | snd_pci... | D6005821D4 |
| 1022:15e2 | 103c:8496 | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | 53B6114671 |
| 1022:15e2 | 17aa:380b | AMD        | Raven/Raven2/FireFlight/R... | 3     | snd_pci... | B0FCF85E0D |
| 1022:15e2 | 103c:85de | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | 70F1D3BF36 |
| 8086:5a88 |           | Intel      | Celeron N3350/Pentium N42... | 1     |            | 6663E08482 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8136 | 103c:80d1 | Realtek... | RTL810xE PCI Express Fast... | 3     | r8169      | FD3B38A3F5 |
| 10ec:8168 | 103c:84d8 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 9B4E7338B0 |
| 10ec:8168 | 17aa:3850 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 5B8D494C04 |
| 8086:1570 | 17aa:2233 | Intel      | Ethernet Connection I219-V   | 3     | e1000e     | C480CEB1FC |
| 10ec:8168 | 17aa:3848 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | C194639A17 |
| 8086:156f | 17aa:2233 | Intel      | Ethernet Connection I219-LM  | 2     | e1000e     | 3504F119EA |
| 8086:15be | 17aa:2292 | Intel      | Ethernet Connection (6) I... | 2     | e1000e     | FD5A5FBD54 |
| 8086:15d7 | 17aa:224e | Intel      | Ethernet Connection (4) I... | 2     | e1000e     | 66ACB89125 |
| 8086:15d8 | 17aa:224e | Intel      | Ethernet Connection (4) I... | 2     | e1000e     | 3AC5B5C4AD |
| 8086:15d8 | 17aa:506c | Intel      | Ethernet Connection (4) I... | 2     | e1000e     | 225075209E |
| 10ec:8136 | 103c:802b | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | 07B5ECDCCD |
| 10ec:8136 | 103c:806e | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | 62A9EF950E |
| 10ec:8168 | 103c:806c | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 462F2D5347 |
| 10ec:8168 | 103c:80d0 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 97ED13A8C0 |
| 10ec:8168 | 103c:8143 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 49796C6747 |
| 10ec:8168 | 103c:8251 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | C77AFE79C3 |
| 10ec:8168 | 144d:c14c | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 6E023867E9 |
| 10ec:8168 | 17aa:383f | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | F8913A087C |
| 10ec:8168 | 17aa:3868 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | B9FC5DC357 |
| 10ec:8168 | 17aa:5058 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | C65BB14578 |
| 14e4:1682 | 14e4:1682 | Broadco... | NetXtreme BCM57762 Gigabi... | 1     | tg3        | E9DECBC4FD |
| 8086:0d4f | 17aa:2292 | Intel      | Ethernet Connection (10) ... | 1     | e1000e     | D6B3970321 |
| 8086:156f | 17aa:504c | Intel      | Ethernet Connection I219-LM  | 1     | e1000e     | 3C1A4327F5 |
| 8086:15bd | 17aa:2292 | Intel      | Ethernet Connection (6) I... | 1     | e1000e     | 7C5B2D05AE |
| 8086:15be | 17aa:2294 | Intel      | Ethernet Connection (6) I... | 1     | e1000e     | 167048774C |
| 8086:15be | 17aa:5077 | Intel      | Ethernet Connection (6) I... | 1     | e1000e     | E6D8B9F842 |
| 8086:15d7 | 17aa:506d | Intel      | Ethernet Connection (4) I... | 1     | e1000e     | 0818236221 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 16    | iwlwifi    | 6F8FD31C2C |
| 10ec:b822 | 103c:831b | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 13    | r8822be    | D6005821D4 |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 9     | 8821ce     | 59D61DD321 |
| 168c:0042 | 17aa:0901 | Qualcom... | QCA9377 802.11ac Wireless... | 9     | ath10k_pci | C7DFFC3F2A |
| 8086:24fd | 8086:9010 | Intel      | Wireless 8265 / 8275         | 9     | iwlwifi    | C28AED72AA |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 7     | iwlwifi    | A9301396F9 |
| 8086:9df0 | 8086:0034 | Intel      | Cannon Point-LP CNVi [Wir... | 7     | iwlwifi    | 3701BEE474 |
| 168c:003e | 17aa:0827 | Qualcom... | QCA6174 802.11ac Wireless... | 6     | ath10k_pci | 5E49D8DD4C |
| 8086:2526 | 8086:0014 | Intel      | Wireless-AC 9260             | 5     | iwlwifi    | CEDC6D5AA8 |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 5     | iwlwifi    | 49796C6747 |
| 8086:9df0 | 8086:0030 | Intel      | Cannon Point-LP CNVi [Wir... | 5     | iwlwifi    | 7C5B2D05AE |
| 10ec:b822 | 17aa:b023 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 4     | r8822be    | 3C97527813 |
| 168c:0042 | 17aa:4035 | Qualcom... | QCA9377 802.11ac Wireless... | 4     | ath10k_pci | 5B8D494C04 |
| 8086:24f3 | 8086:1130 | Intel      | Wireless 8260                | 4     | iwlwifi    | 6D14F41FBD |
| 8086:24fd | 8086:8010 | Intel      | Wireless 8265 / 8275         | 4     | iwlwifi    | E9DECBC4FD |
| 8086:3165 | 8086:8110 | Intel      | Wireless 3165                | 4     | iwlwifi    | CBA368D785 |
| 8086:24f3 | 8086:0110 | Intel      | Wireless 8260                | 3     | iwlwifi    | AD2B007CB9 |
| 8086:24f3 | 8086:0130 | Intel      | Wireless 8260                | 3     | iwlwifi    | 3504F119EA |
| 8086:24f3 | 8086:9010 | Intel      | Wireless 8260                | 3     | iwlwifi    | 6E023867E9 |
| 8086:3165 | 8086:8010 | Intel      | Wireless 3165                | 3     | iwlwifi    | 991764DD3F |
| 10ec:b723 | 103c:804c | Realtek... | RTL8723BE PCIe Wireless N... | 2     | rtl8723be  | 2DE25CD685 |
| 10ec:b822 | 1a3b:2950 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 2     | rtw_pci    | 18B4F9B58E |
| 168c:003e | 1a56:143a | Qualcom... | QCA6174 802.11ac Wireless... | 2     | ath10k_pci | 8CA313CDAD |
| 8086:095a | 8086:5410 | Intel      | Wireless 7265                | 2     | iwlwifi    | 7EB57A3809 |
| 8086:095a | 8086:9e10 | Intel      | Wireless 7265                | 2     | iwlwifi    | 7CCE37A416 |
| 8086:24f3 | 8086:8010 | Intel      | Wireless 8260                | 2     | iwlwifi    | C0BC126501 |
| 8086:24fd | 8086:0130 | Intel      | Wireless 8265 / 8275         | 2     | iwlwifi    | 66ACB89125 |
| 8086:24fd | 8086:1130 | Intel      | Wireless 8265 / 8275         | 2     | iwlwifi    | 3AC5B5C4AD |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 2     | iwlwifi    | FC1E9BDE71 |
| 8086:31dc | 8086:02a4 | Intel      | Wireless-AC 1550i Wireles... | 2     | iwlwifi    | 56A7BF3D18 |
| 8086:9df0 | 8086:42a4 | Intel      | Cannon Point-LP CNVi [Wir... | 2     | iwlwifi    | D256E89F2D |
| 10ec:b822 | 17aa:b024 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 1     | r8822be    | BC69AFD822 |
| 10ec:c821 | 17aa:c024 | Realtek... | RTL8821CE 802.11ac PCIe W... | 1     | rtl8821ce  | B0FCF85E0D |
| 10ec:c822 | 103c:85f7 | Realtek... | 8822CE Wireless LAN 802.1... | 1     | rtwpci     | 8FF42ABD82 |
| 14e4:4365 | 103c:2230 | Broadco... | BCM43142 802.11b/g/n         | 1     | wl         | 07B5ECDCCD |
| 14e4:43ba | 1028:0020 | Broadco... | BCM43602 802.11ac Wireles... | 1     | brcmfmac   | C77AFE79C3 |
| 168c:003e | 11ad:0807 | Qualcom... | QCA6174 802.11ac Wireless... | 1     | ath10k_pci | BAE5A5C3DD |
| 168c:0042 | 1a3b:2231 | Qualcom... | QCA9377 802.11ac Wireless... | 1     | ath10k_pci | 2C6BCC75CC |
| 8086:02f0 | 8086:0030 | Intel      | Wireless-AC 9462             | 1     | iwlwifi    | D6B3970321 |
| 8086:02f0 | 8086:0034 | Intel      | Wireless-AC 9462             | 1     | iwlwifi    | A25721AA13 |
| 8086:02f0 | 8086:0074 | Intel      | Wireless-AC 9462             | 1     | iwlwifi    | 702DE7D41F |
| 8086:095b | 8086:5210 | Intel      | Wireless 7265                | 1     | iwlwifi    | C65BB14578 |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 1     | iwlwifi    | 1B19B5466D |
| 8086:24fd | 8086:0110 | Intel      | Wireless 8265 / 8275         | 1     | iwlwifi    | 93A44B1518 |
| 8086:24fd | 8086:0150 | Intel      | Wireless 8265 / 8275         | 1     | iwlwifi    | DFDC8C484F |
| 8086:24fd | 8086:8050 | Intel      | Wireless 8265 / 8275         | 1     | iwlwifi    | 57D57D82FE |
| 8086:3166 | 8086:4310 | Intel      | Dual Band Wireless-AC 316... | 1     | iwlwifi    | C194639A17 |
| 8086:a370 | 8086:0034 | Intel      | Wireless-AC 9560 [Jeffers... | 1     | iwlwifi    | D764EA82D5 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 12    | iwlwifi    | 9B4E7338B0 |
| 10ec:d723 | 103c:8319 | Realtek... | RTL8723DE Wireless Networ... | 4     | rtl8723de  | 0ECB13EDBF |
| 8086:02f0 | 8086:4070 | Intel      | Wireless-AC 9462             | 1     | iwlwifi    | 20ABB6DE72 |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d26 |           | Intel      | Skylake-U/Y Northpeak        | 5     | intel_t... | 49796C6747 |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d35 | 8086:9d35 | Intel      | Sunrise Point-LP Integrat... | 8     | intel_i... | A9301396F9 |
| 8086:9d35 | 103c:830f | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 0ECB13EDBF |
| 8086:9d35 | 103c:83b9 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | C28AED72AA |
| 8086:9d35 | 103c:8486 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 7DEF867A41 |
| 8086:9d35 | 103c:8488 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 59D61DD321 |
| 1022:15e4 | 103c:8496 | AMD        | Raven/Raven2/Renoir Senso... | 4     |            | 31DDC7FDCB |
| 1022:15e4 | 103c:85dd | AMD        | Raven/Raven2/Renoir Senso... | 4     |            | D6005821D4 |
| 1022:15e6 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Non-S... | 4     | i2c_amd... | B0FCF85E0D |
| 8086:9d35 | 17aa:224e | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 66ACB89125 |
| 8086:9d35 | 103c:827f | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 1DB4A76555 |
| 8086:9d35 | 103c:84d8 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 9B4E7338B0 |
| 8086:9d35 | 17aa:2238 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 3504F119EA |
| 8086:9d24 |           | Intel      | Skylake-U/Y SPI Controller   | 2     |            | 7CCE37A416 |
| 8086:9d35 | 1028:07aa | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | DFDC8C484F |
| 8086:9d35 | 1028:07eb | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 7EB57A3809 |
| 8086:9d35 | 103c:827d | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | E9DECBC4FD |
| 8086:9d35 | 103c:827e | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 28AF751D12 |
| 8086:9d35 | 103c:82c1 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | A9E42C34F6 |
| 8086:9d35 | 103c:8313 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 22FE75A663 |
| 8086:9d35 | 103c:83c4 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 65B956E887 |
| 8086:9d35 | 103c:8503 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | F6ABCD9B4F |
| 8086:9d35 | 1043:1c40 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 18B4F9B58E |
| 8086:9d35 | 1043:1c90 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 7BBD1AB6FE |
| 8086:9d35 | 17aa:2237 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 6AA622B728 |
| 8086:9d35 | 17aa:380d | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | FC1E9BDE71 |
| 8086:9d35 | 17aa:506c | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 225075209E |
| 8086:a135 | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 2     | intel_i... | 8CA313CDAD |
| 1022:15e4 | 103c:8497 | AMD        | Raven/Raven2/Renoir Senso... | 1     |            | D9AF75156B |
| 1022:15e4 | 103c:85de | AMD        | Raven/Raven2/Renoir Senso... | 1     |            | 70F1D3BF36 |
| 8086:9d35 | 1028:077a | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 57D57D82FE |
| 8086:9d35 | 103c:8143 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 49796C6747 |
| 8086:9d35 | 103c:81a1 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | C894E5633B |
| 8086:9d35 | 103c:81ad | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 84C8A9779B |
| 8086:9d35 | 103c:8251 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | C77AFE79C3 |
| 8086:9d35 | 103c:83ba | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 3743010FB5 |
| 8086:9d35 | 103c:8438 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 7F01433E42 |
| 8086:9d35 | 103c:8483 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 8B7A2D2A08 |
| 8086:9d35 | 103c:8484 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 1B466FC315 |
| 8086:9d35 | 103c:8487 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | C8C863DB3A |
| 8086:9d35 | 1043:1ab0 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | B2D75821A4 |
| 8086:9d35 | 1043:1b40 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | FF2D426E76 |
| 8086:9d35 | 144d:c141 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 5B28F6FC87 |
| 8086:9d35 | 144d:c14c | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 6E023867E9 |
| 8086:9d35 | 152d:1147 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 7DA5C4A4FA |
| 8086:9d35 | 17aa:504c | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 3C1A4327F5 |
| 8086:9d35 | 17aa:506d | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 0818236221 |
| 8086:a135 | 103c:83bb | Intel      | 100 Series/C230 Series Ch... | 1     | intel_i... | CBA3EC356E |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | sdhci_pci  | CBA368D785 |
| 8086:9d2b | 103c:8488 | Intel      | Skylake-U/Y SCC: eMMC        | 5     | sdhci_pci  | 59D61DD321 |
| 8086:9d2d | 103c:8486 | Intel      | Sunrise Point-LP Secure D... | 5     | sdhci_pci  | 7DEF867A41 |
| 8086:9d2d | 103c:8488 | Intel      | Sunrise Point-LP Secure D... | 5     | sdhci_pci  | 59D61DD321 |
| 1217:8621 | 17aa:39f6 | O2 Micro   | SD/MMC Card Reader Contro... | 4     | sdhci_pci  | C7DFFC3F2A |
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | sdhci_pci  | 991764DD3F |
| 8086:31d0 | 8086:7270 | Intel      | SD Host Controller           | 3     | sdhci_pci  | 991764DD3F |
| 8086:9d2d | 103c:84d8 | Intel      | Sunrise Point-LP Secure D... | 3     | sdhci_pci  | 9B4E7338B0 |
| 8086:9d2b | 1ae0:006b | Intel      | Skylake-U/Y SCC: eMMC        | 2     | sdhci_pci  | 7CCE37A416 |
| 1217:8520 | 17aa:504c | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 3C1A4327F5 |
| 17a0:9750 | 17a0:9750 | Genesys... | GL9750 SD Host Controller    | 1     | sdhci_pci  | 167048774C |
| 8086:02f5 | 1028:0950 | Intel      | Comet Lake PCH-LP SCS3: SDXC | 1     | sdhci_pci  | 20ABB6DE72 |
| 8086:02f5 | 103c:866e | Intel      | Comet Lake PCH-LP SCS3: SDXC | 1     | sdhci_pci  | 8FF42ABD82 |
| 8086:5aca | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | F8913A087C |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 6663E08482 |
| 8086:5acc | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | F8913A087C |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 6663E08482 |
| 8086:9d2b | 8086:9d2b | Intel      | Skylake-U/Y SCC: eMMC        | 1     | sdhci_pci  | 2C6BCC75CC |
| 8086:9d2d | 103c:8487 | Intel      | Sunrise Point-LP Secure D... | 1     | sdhci_pci  | C8C863DB3A |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9da4 | 8086:9da4 | Intel      | Cannon Point-LP SPI Contr... | 4     |            | C7DFFC3F2A |
| 8086:9de8 | 17aa:380b | Intel      | Cannon Point-LP Serial IO... | 4     | intel_l... | C7DFFC3F2A |
| 8086:9de9 | 17aa:3804 | Intel      | Cannon Point-LP Serial IO... | 4     | intel_l... | C7DFFC3F2A |
| 8086:9dea | 17aa:3802 | Intel      | 8th Gen Intel Core Proces... | 4     | intel_l... | C7DFFC3F2A |
| 8086:9da4 | 103c:8514 | Intel      | Cannon Point-LP SPI Contr... | 3     |            | 0CF9D0AFB9 |
| 8086:9da4 | 17aa:2292 | Intel      | Cannon Point-LP SPI Contr... | 3     |            | 7C5B2D05AE |
| 8086:9de8 | 103c:8514 | Intel      | Cannon Point-LP Serial IO... | 3     | intel_lpss | 0CF9D0AFB9 |
| 8086:9de8 | 17aa:2292 | Intel      | Cannon Point-LP Serial IO... | 3     | intel_l... | 7C5B2D05AE |
| 8086:9de9 | 103c:8514 | Intel      | Cannon Point-LP Serial IO... | 3     | intel_lpss | 0CF9D0AFB9 |
| 8086:9de9 | 17aa:2292 | Intel      | Cannon Point-LP Serial IO... | 3     | intel_l... | 7C5B2D05AE |
| 8086:5ac8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | pwm_lpss   | 6663E08482 |
| 8086:9da4 | 103c:8518 | Intel      | Cannon Point-LP SPI Contr... | 2     |            | 969C4C3BCB |
| 8086:9de8 | 103c:8518 | Intel      | Cannon Point-LP Serial IO... | 2     | intel_l... | 969C4C3BCB |
| 8086:9de9 | 103c:8518 | Intel      | Cannon Point-LP Serial IO... | 2     | intel_l... | 969C4C3BCB |
| 8086:02a4 | 1028:0950 | Intel      | Comet Lake SPI (flash) Co... | 1     |            | 20ABB6DE72 |
| 8086:02a4 | 103c:866e | Intel      | Comet Lake SPI (flash) Co... | 1     |            | 8FF42ABD82 |
| 8086:02a4 | 17aa:2292 | Intel      | Comet Lake SPI (flash) Co... | 1     |            | D6B3970321 |
| 8086:02a4 | 17aa:3804 | Intel      | Comet Lake SPI (flash) Co... | 1     |            | 702DE7D41F |
| 8086:02a4 | 17aa:3806 | Intel      | Comet Lake SPI (flash) Co... | 1     |            | A25721AA13 |
| 8086:02c5 | 17aa:3802 | Intel      | Comet Lake PCH-LP LPSS: I... | 1     | intel_l... | 702DE7D41F |
| 8086:02e8 | 1028:0950 | Intel      | Serial IO I2C Host Contro... | 1     | intel_l... | 20ABB6DE72 |
| 8086:02e8 | 103c:866e | Intel      | Serial IO I2C Host Contro... | 1     | intel_l... | 8FF42ABD82 |
| 8086:02e8 | 17aa:2292 | Intel      | Serial IO I2C Host Contro... | 1     | intel_l... | D6B3970321 |
| 8086:02e8 | 17aa:3806 | Intel      | Serial IO I2C Host Contro... | 1     | intel_l... | A25721AA13 |
| 8086:02e8 | 17aa:3807 | Intel      | Serial IO I2C Host Contro... | 1     | intel_l... | 702DE7D41F |
| 8086:02e9 | 1028:0950 | Intel      | Comet Lake PCH-LP LPSS: I... | 1     | intel_l... | 20ABB6DE72 |
| 8086:02e9 | 103c:866e | Intel      | Comet Lake PCH-LP LPSS: I... | 1     | intel_l... | 8FF42ABD82 |
| 8086:02e9 | 17aa:2292 | Intel      | Comet Lake PCH-LP LPSS: I... | 1     | intel_l... | D6B3970321 |
| 8086:02e9 | 17aa:3802 | Intel      | Comet Lake PCH-LP LPSS: I... | 1     | intel_l... | 702DE7D41F |
| 8086:02e9 | 17aa:3806 | Intel      | Comet Lake PCH-LP LPSS: I... | 1     | intel_l... | A25721AA13 |
| 8086:9da4 | 1028:089e | Intel      | Cannon Point-LP SPI Contr... | 1     |            | D256E89F2D |
| 8086:9da4 | 1028:089f | Intel      | Cannon Point-LP SPI Contr... | 1     |            | 70A45F8830 |
| 8086:9da4 | 144d:c812 | Intel      | Cannon Point-LP SPI Contr... | 1     |            | 3701BEE474 |
| 8086:9da4 | 17aa:2294 | Intel      | Cannon Point-LP SPI Contr... | 1     |            | 167048774C |
| 8086:9da4 | 17aa:5077 | Intel      | Cannon Point-LP SPI Contr... | 1     |            | E6D8B9F842 |
| 8086:9da4 | 1854:0333 | Intel      | Cannon Point-LP SPI Contr... | 1     |            | 6D2724E820 |
| 8086:9de8 | 1028:089e | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | D256E89F2D |
| 8086:9de8 | 1028:089f | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | 70A45F8830 |
| 8086:9de8 | 144d:c812 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_lpss | 3701BEE474 |
| 8086:9de8 | 17aa:5077 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | E6D8B9F842 |
| 8086:9de8 | 1854:0333 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_lpss | 6D2724E820 |
| 8086:9de9 | 1028:089e | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | D256E89F2D |
| 8086:9de9 | 1028:089f | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | 70A45F8830 |
| 8086:9de9 | 17aa:5077 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | E6D8B9F842 |
| 8086:9de9 | 1854:0333 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_lpss | 6D2724E820 |
| 8086:9dea | 144d:c812 | Intel      | 8th Gen Intel Core Proces... | 1     | intel_lpss | 3701BEE474 |
| 8086:9dea | 17aa:5077 | Intel      | 8th Gen Intel Core Proces... | 1     | intel_l... | E6D8B9F842 |
| 8086:9dea | 1854:0333 | Intel      | 8th Gen Intel Core Proces... | 1     | intel_lpss | 6D2724E820 |
| 8086:9deb | 1854:0333 | Intel      | 8th Gen Intel Core Proces... | 1     | intel_lpss | 6D2724E820 |
| 8086:9dfb | 8086:7270 | Intel      | 300 Series Chipset LPSS: ... | 1     | intel_lpss | 6D2724E820 |
| 8086:a324 | 103c:8519 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | D764EA82D5 |
| 8086:a368 | 103c:8519 | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | D764EA82D5 |
| 8086:a369 | 103c:8519 | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | D764EA82D5 |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9dfc | 103c:8514 | Intel      | Cannon Point-LP Integrate... | 3     | intel_i... | 0CF9D0AFB9 |
| 8086:9dfc | 17aa:2292 | Intel      | Cannon Point-LP Integrate... | 3     | intel_i... | 7C5B2D05AE |
| 8086:9d3d | 1028:07aa | Intel      | Sunrise Point-LP Active M... | 2     | serial     | DFDC8C484F |
| 8086:9d3d | 103c:827d | Intel      | Sunrise Point-LP Active M... | 2     | serial     | E9DECBC4FD |
| 8086:9d3d | 17aa:2238 | Intel      | Sunrise Point-LP Active M... | 2     | serial     | 3504F119EA |
| 8086:9d3d | 17aa:224e | Intel      | Sunrise Point-LP Active M... | 2     | serial     | 66ACB89125 |
| 8086:9dfc | 103c:8518 | Intel      | Cannon Point-LP Integrate... | 2     | intel_i... | 969C4C3BCB |
| 8086:02fc | 1028:0950 | Intel      | Comet Lake Integrated Sen... | 1     | intel_i... | 20ABB6DE72 |
| 8086:02fc | 103c:866e | Intel      | Comet Lake Integrated Sen... | 1     | intel_i... | 8FF42ABD82 |
| 8086:02fc | 17aa:2292 | Intel      | Comet Lake Integrated Sen... | 1     | intel_i... | D6B3970321 |
| 8086:02fc | 17aa:3804 | Intel      | Comet Lake Integrated Sen... | 1     | intel_i... | 702DE7D41F |
| 8086:02fc | 17aa:3806 | Intel      | Comet Lake Integrated Sen... | 1     | intel_i... | A25721AA13 |
| 8086:9de3 | 17aa:2292 | Intel      | Cannon Point-LP Keyboard ... | 1     | serial     | 7C5B2D05AE |
| 8086:9dfc | 1028:089e | Intel      | Cannon Point-LP Integrate... | 1     | intel_i... | D256E89F2D |
| 8086:9dfc | 1028:089f | Intel      | Cannon Point-LP Integrate... | 1     | intel_i... | 70A45F8830 |
| 8086:9dfc | 144d:c812 | Intel      | Cannon Point-LP Integrate... | 1     | intel_i... | 3701BEE474 |
| 8086:9dfc | 17aa:2294 | Intel      | Cannon Point-LP Integrate... | 1     | intel_i... | 167048774C |
| 8086:9dfc | 17aa:5077 | Intel      | Cannon Point-LP Integrate... | 1     | intel_i... | E6D8B9F842 |
| 8086:a37c | 103c:8519 | Intel      | VROC Virtual Controller      | 1     | intel_i... | D764EA82D5 |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 8     | process... | C3F66A8352 |
| 8086:5a8c |           | Intel      | Dynamic Platform and Ther... | 6     | process... | CBA368D785 |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | CBA368D785 |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | CBA368D785 |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | CBA368D785 |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | CBA368D785 |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | CBA368D785 |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | CBA368D785 |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | CBA368D785 |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | CBA368D785 |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | CBA368D785 |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | CBA368D785 |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | CBA368D785 |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | CBA368D785 |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | CBA368D785 |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | CBA368D785 |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | CBA368D785 |
| 8086:9d27 |           | Intel      | Sunrise Point-LP Serial I... | 6     | intel_l... | 18B4F9B58E |
| 8086:9d29 |           | Intel      | Sunrise Point-LP Serial I... | 6     | intel_l... | 18B4F9B58E |
| 8086:1903 | 103c:830f | Intel      | Xeon E3-1200 v5/E3-1500 v... | 5     | process... | 0ECB13EDBF |
| 8086:1903 | 103c:83b9 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 5     | process... | C28AED72AA |
| 8086:1903 | 103c:8486 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 5     | process... | 7DEF867A41 |
| 8086:1903 | 103c:8488 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 5     | process... | 59D61DD321 |
| 8086:9d27 | 103c:83b9 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | C28AED72AA |
| 8086:9d27 | 103c:8486 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 7DEF867A41 |
| 8086:9d27 | 103c:8488 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 59D61DD321 |
| 8086:9d29 | 103c:83b9 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | C28AED72AA |
| 8086:9d31 | 103c:830f | Intel      | Sunrise Point-LP Thermal ... | 5     | intel_p... | 0ECB13EDBF |
| 8086:9d31 | 103c:83b9 | Intel      | Sunrise Point-LP Thermal ... | 5     | intel_p... | C28AED72AA |
| 8086:9d31 | 103c:8486 | Intel      | Sunrise Point-LP Thermal ... | 5     | intel_p... | 7DEF867A41 |
| 8086:9d31 | 103c:8488 | Intel      | Sunrise Point-LP Thermal ... | 5     | intel_p... | 59D61DD321 |
| 8086:9d31 | 17aa:3830 | Intel      | Sunrise Point-LP Thermal ... | 5     | intel_p... | 33D7D63C6D |
| 8086:9d60 | 103c:830f | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 0ECB13EDBF |
| 8086:9d60 | 103c:83b9 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | C28AED72AA |
| 8086:9d60 | 103c:8486 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 7DEF867A41 |
| 8086:9d60 | 103c:8488 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 59D61DD321 |
| 8086:9d60 | 17aa:3837 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 33D7D63C6D |
| 8086:9d61 | 103c:830f | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 0ECB13EDBF |
| 8086:9d61 | 103c:8486 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 7DEF867A41 |
| 8086:9d61 | 103c:8488 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 59D61DD321 |
| 8086:9d61 | 17aa:3836 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 33D7D63C6D |
| 8086:9d62 | 103c:8486 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 7DEF867A41 |
| 8086:9d62 | 17aa:3809 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 33D7D63C6D |
| 8086:1903 | 17aa:2292 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 4     | process... | 7C5B2D05AE |
| 8086:1903 | 17aa:3829 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 4     | process... | C7DFFC3F2A |
| 8086:9d31 | 17aa:224e | Intel      | Sunrise Point-LP Thermal ... | 4     | intel_p... | 66ACB89125 |
| 8086:9df9 | 17aa:380a | Intel      | Cannon Point-LP Thermal C... | 4     | intel_p... | C7DFFC3F2A |
| 8086:1903 | 103c:80d1 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | process... | FD3B38A3F5 |
| 8086:1903 | 103c:827f | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | proc_th... | 1DB4A76555 |
| 8086:1903 | 103c:84d8 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | proc_th... | 9B4E7338B0 |
| 8086:1903 | 103c:8514 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | proc_th... | 0CF9D0AFB9 |
| 8086:1903 | 17aa:381c | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | process... | 5A7A4AFFFB |
| 8086:22dc | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 3     | process... | 9FAC88C07A |
| 8086:318c | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | process... | 991764DD3F |
| 8086:31ac | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_l... | 991764DD3F |
| 8086:31ae | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_l... | 991764DD3F |
| 8086:31b0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_l... | 991764DD3F |
| 8086:31b2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_l... | 991764DD3F |
| 8086:31b4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_l... | 991764DD3F |
| 8086:31b6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_l... | 991764DD3F |
| 8086:31b8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_l... | 991764DD3F |
| 8086:31ba | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_l... | 991764DD3F |
| 8086:31bc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_l... | 991764DD3F |
| 8086:31be | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_l... | 991764DD3F |
| 8086:31c0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_l... | 991764DD3F |
| 8086:31c2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_l... | 991764DD3F |
| 8086:31c4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_l... | 991764DD3F |
| 8086:31c6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_l... | 991764DD3F |
| 8086:31ee | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_l... | 991764DD3F |
| 8086:9d27 | 103c:84d8 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_lpss | 9B4E7338B0 |
| 8086:9d27 | 17aa:381d | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 6D14F41FBD |
| 8086:9d31 | 103c:80d1 | Intel      | Sunrise Point-LP Thermal ... | 3     | intel_p... | FD3B38A3F5 |
| 8086:9d31 | 103c:827f | Intel      | Sunrise Point-LP Thermal ... | 3     | intel_p... | 1DB4A76555 |
| 8086:9d31 | 103c:84d8 | Intel      | Sunrise Point-LP Thermal ... | 3     | intel_p... | 9B4E7338B0 |
| 8086:9d31 | 17aa:2238 | Intel      | Sunrise Point-LP Thermal ... | 3     | intel_p... | 3504F119EA |
| 8086:9d31 | 17aa:380b | Intel      | Sunrise Point-LP Thermal ... | 3     | intel_p... | 5B8D494C04 |
| 8086:9d31 | 17aa:3819 | Intel      | Sunrise Point-LP Thermal ... | 3     | intel_p... | 6D14F41FBD |
| 8086:9d31 | 17aa:385a | Intel      | Sunrise Point-LP Thermal ... | 3     | intel_p... | 5A7A4AFFFB |
| 8086:9d60 | 103c:80d1 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | FD3B38A3F5 |
| 8086:9d60 | 103c:827f | Intel      | Sunrise Point-LP Serial I... | 3     | intel_lpss | 1DB4A76555 |
| 8086:9d60 | 103c:84d8 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_lpss | 9B4E7338B0 |
| 8086:9d60 | 17aa:3811 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 5B8D494C04 |
| 8086:9d60 | 17aa:381d | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 6D14F41FBD |
| 8086:9d60 | 17aa:385f | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 5A7A4AFFFB |
| 8086:9d61 | 103c:80d1 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | FD3B38A3F5 |
| 8086:9d61 | 103c:84d8 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_lpss | 9B4E7338B0 |
| 8086:9d61 | 17aa:3811 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 5B8D494C04 |
| 8086:9d61 | 17aa:381d | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 6D14F41FBD |
| 8086:9d61 | 17aa:3857 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 5A7A4AFFFB |
| 8086:9d63 | 17aa:3809 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 5A7A4AFFFB |
| 8086:9d66 | 17aa:3810 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 5A7A4AFFFB |
| 8086:9df9 | 103c:8514 | Intel      | Cannon Point-LP Thermal C... | 3     | intel_p... | 0CF9D0AFB9 |
| 8086:9df9 | 17aa:2292 | Intel      | Cannon Point-LP Thermal C... | 3     | intel_p... | 7C5B2D05AE |
| 8086:1903 | 1028:07aa | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | proc_th... | DFDC8C484F |
| 8086:1903 | 1028:07eb | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | process... | 7EB57A3809 |
| 8086:1903 | 1028:080d | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | process... | 8CA313CDAD |
| 8086:1903 | 103c:827d | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | proc_th... | E9DECBC4FD |
| 8086:1903 | 103c:827e | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | process... | 28AF751D12 |
| 8086:1903 | 103c:82c1 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | process... | A9E42C34F6 |
| 8086:1903 | 103c:8313 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | proc_th... | 22FE75A663 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | i2c_i801   | CBA368D785 |
| 8086:9d23 | 103c:830f | Intel      | Sunrise Point-LP SMBus       | 5     |            | 0ECB13EDBF |
| 8086:9d23 | 103c:83b9 | Intel      | Sunrise Point-LP SMBus       | 5     | i2c_i801   | C28AED72AA |
| 8086:9d23 | 103c:8486 | Intel      | Sunrise Point-LP SMBus       | 5     | i2c_i801   | 7DEF867A41 |
| 8086:9d23 | 103c:8488 | Intel      | Sunrise Point-LP SMBus       | 5     | i2c_i801   | 59D61DD321 |
| 8086:9d23 | 17aa:3840 | Intel      | Sunrise Point-LP SMBus       | 5     | i2c_i801   | 33D7D63C6D |
| 1022:790b | 103c:8496 | AMD        | FCH SMBus Controller         | 4     | i2c_piix4  | 31DDC7FDCB |
| 1022:790b | 103c:85dd | AMD        | FCH SMBus Controller         | 4     | i2c_pii... | D6005821D4 |
| 1022:790b | 17aa:3818 | AMD        | FCH SMBus Controller         | 4     | i2c_piix4  | B0FCF85E0D |
| 8086:9d23 | 17aa:224e | Intel      | Sunrise Point-LP SMBus       | 4     | i801_smbus | 66ACB89125 |
| 8086:9da3 | 17aa:3812 | Intel      | Cannon Point-LP SMBus Con... | 4     | i2c_i801   | C7DFFC3F2A |
| 8086:2292 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 3     | i2c_i801   | 9FAC88C07A |
| 8086:31d4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | i2c_i801   | 991764DD3F |
| 8086:9d23 | 103c:80d1 | Intel      | Sunrise Point-LP SMBus       | 3     | i2c_i801   | FD3B38A3F5 |
| 8086:9d23 | 103c:827f | Intel      | Sunrise Point-LP SMBus       | 3     | i801_smbus | 1DB4A76555 |
| 8086:9d23 | 103c:84d8 | Intel      | Sunrise Point-LP SMBus       | 3     | i801_smbus | 9B4E7338B0 |
| 8086:9d23 | 17aa:2238 | Intel      | Sunrise Point-LP SMBus       | 3     | i801_smbus | 3504F119EA |
| 8086:9d23 | 17aa:3811 | Intel      | Sunrise Point-LP SMBus       | 3     | i2c_i801   | 5B8D494C04 |
| 8086:9d23 | 17aa:3823 | Intel      | Sunrise Point-LP SMBus       | 3     | i2c_i801   | 6D14F41FBD |
| 8086:9d23 | 17aa:3867 | Intel      | Sunrise Point-LP SMBus       | 3     | i2c_i801   | 5A7A4AFFFB |
| 8086:9da3 | 103c:8514 | Intel      | Cannon Point-LP SMBus Con... | 3     | i801_smbus | 0CF9D0AFB9 |
| 8086:9da3 | 17aa:2292 | Intel      | Cannon Point-LP SMBus Con... | 3     | i2c_i801   | 7C5B2D05AE |
| 8086:9d23 | 1028:07aa | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | DFDC8C484F |
| 8086:9d23 | 1028:07eb | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | 7EB57A3809 |
| 8086:9d23 | 103c:827d | Intel      | Sunrise Point-LP SMBus       | 2     | i801_smbus | E9DECBC4FD |
| 8086:9d23 | 103c:827e | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | 28AF751D12 |
| 8086:9d23 | 103c:82c1 | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | A9E42C34F6 |
| 8086:9d23 | 103c:8313 | Intel      | Sunrise Point-LP SMBus       | 2     | i801_smbus | 22FE75A663 |
| 8086:9d23 | 103c:83c4 | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | 65B956E887 |
| 8086:9d23 | 103c:8503 | Intel      | Sunrise Point-LP SMBus       | 2     |            | F6ABCD9B4F |
| 8086:9d23 | 1043:14f0 | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | AD2B007CB9 |
| 8086:9d23 | 1043:1c40 | Intel      | Sunrise Point-LP SMBus       | 2     | i801_smbus | 18B4F9B58E |
| 8086:9d23 | 1043:1c90 | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | 7BBD1AB6FE |
| 8086:9d23 | 1043:1dc0 | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | C0BC126501 |
| 8086:9d23 | 17aa:2237 | Intel      | Sunrise Point-LP SMBus       | 2     | i801_smbus | 6AA622B728 |
| 8086:9d23 | 17aa:3805 | Intel      | Sunrise Point-LP SMBus       | 2     | i801_smbus | 941DF897AA |
| 8086:9d23 | 17aa:380b | Intel      | Sunrise Point-LP SMBus       | 2     |            | C194639A17 |
| 8086:9d23 | 17aa:383c | Intel      | Sunrise Point-LP SMBus       | 2     |            | 1681EDB0F6 |
| 8086:9d23 | 17aa:385f | Intel      | Sunrise Point-LP SMBus       | 2     | i801_smbus | D16FC3AC03 |
| 8086:9d23 | 17aa:3862 | Intel      | Sunrise Point-LP SMBus       | 2     |            | FC1E9BDE71 |
| 8086:9d23 | 17aa:506c | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | 225075209E |
| 8086:9d23 | 1ae0:006b | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | 7CCE37A416 |
| 8086:9da3 | 103c:8518 | Intel      | Cannon Point-LP SMBus Con... | 2     | i2c_i801   | 969C4C3BCB |
| 8086:a123 | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 2     |            | 8CA313CDAD |
| 1022:790b | 103c:81aa | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | D103A0F533 |
| 1022:790b | 103c:8311 | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | EEE03F79BD |
| 1022:790b | 103c:8497 | AMD        | FCH SMBus Controller         | 1     | piix4_s... | D9AF75156B |
| 1022:790b | 103c:85de | AMD        | FCH SMBus Controller         | 1     | i2c_pii... | 70F1D3BF36 |
| 1022:790b | 17aa:3802 | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | B9FC5DC357 |
| 8086:02a3 | 1028:0950 | Intel      | Comet Lake PCH-LP SMBus H... | 1     | i2c_i801   | 20ABB6DE72 |
| 8086:02a3 | 103c:866e | Intel      | Comet Lake PCH-LP SMBus H... | 1     | i2c_i801   | 8FF42ABD82 |
| 8086:02a3 | 17aa:2292 | Intel      | Comet Lake PCH-LP SMBus H... | 1     | i2c_i801   | D6B3970321 |
| 8086:02a3 | 17aa:3803 | Intel      | Comet Lake PCH-LP SMBus H... | 1     | i2c_i801   | 702DE7D41F |
| 8086:02a3 | 17aa:3806 | Intel      | Comet Lake PCH-LP SMBus H... | 1     | i2c_i801   | A25721AA13 |
| 8086:0f12 | 103c:802b | Intel      | Atom Processor E3800 Seri... | 1     | i2c_i801   | 07B5ECDCCD |
| 8086:5ad4 | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 1     |            | F8913A087C |
| 8086:9ca2 | 103c:802d | Intel      | Wildcat Point-LP SMBus Co... | 1     | i2c_i801   | D9CA1DBE13 |
| 8086:9ca2 | 103c:806c | Intel      | Wildcat Point-LP SMBus Co... | 1     |            | 462F2D5347 |
| 8086:9ca2 | 103c:806e | Intel      | Wildcat Point-LP SMBus Co... | 1     | i2c_i801   | 62A9EF950E |
| 8086:9d23 | 1025:120d | Intel      | Sunrise Point-LP SMBus       | 1     |            | BAE5A5C3DD |
| 8086:9d23 | 1028:077a | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | 57D57D82FE |
| 8086:9d23 | 103c:804e | Intel      | Sunrise Point-LP SMBus       | 1     |            | 6F8FD31C2C |
| 8086:9d23 | 103c:80d0 | Intel      | Sunrise Point-LP SMBus       | 1     | i801_smbus | 97ED13A8C0 |
| 8086:9d23 | 103c:8143 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 49796C6747 |
| 8086:9d23 | 103c:81a1 | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | C894E5633B |
| 8086:9d23 | 103c:81ad | Intel      | Sunrise Point-LP SMBus       | 1     |            | 84C8A9779B |
| 8086:9d23 | 103c:8251 | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | C77AFE79C3 |
| 8086:9d23 | 103c:83ba | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | 3743010FB5 |
| 8086:9d23 | 103c:8438 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 7F01433E42 |
| 8086:9d23 | 103c:8483 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 8B7A2D2A08 |
| 8086:9d23 | 103c:8484 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 1B466FC315 |
| 8086:9d23 | 103c:8487 | Intel      | Sunrise Point-LP SMBus       | 1     |            | C8C863DB3A |
| 8086:9d23 | 1043:12e1 | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | 93A44B1518 |
| 8086:9d23 | 1043:14c0 | Intel      | Sunrise Point-LP SMBus       | 1     |            | FA7C5C4F64 |
| 8086:9d23 | 1043:1ab0 | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | B2D75821A4 |
| 8086:9d23 | 1043:1b00 | Intel      | Sunrise Point-LP SMBus       | 1     | i801_smbus | A9301396F9 |
| 8086:9d23 | 1043:1b40 | Intel      | Sunrise Point-LP SMBus       | 1     |            | FF2D426E76 |
| 8086:9d23 | 1043:1cf0 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 2C6BCC75CC |
| 8086:9d23 | 144d:c141 | Intel      | Sunrise Point-LP SMBus       | 1     | i801_smbus | 5B28F6FC87 |
| 8086:9d23 | 144d:c14c | Intel      | Sunrise Point-LP SMBus       | 1     | i801_smbus | 6E023867E9 |
| 8086:9d23 | 152d:1147 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 7DA5C4A4FA |
| 8086:9d23 | 17aa:3860 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 3C97527813 |
| 8086:9d23 | 17aa:504c | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | 3C1A4327F5 |
| 8086:9d23 | 17aa:5058 | Intel      | Sunrise Point-LP SMBus       | 1     |            | C65BB14578 |
| 8086:9d23 | 17aa:506d | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | 0818236221 |
| 8086:9d23 | 8086:9d23 | Intel      | Sunrise Point-LP SMBus       | 1     |            | C3AA237F35 |
| 8086:9da3 | 1028:089e | Intel      | Cannon Point-LP SMBus Con... | 1     | i2c_i801   | D256E89F2D |
| 8086:9da3 | 1028:089f | Intel      | Cannon Point-LP SMBus Con... | 1     |            | 70A45F8830 |
| 8086:9da3 | 144d:c812 | Intel      | Cannon Point-LP SMBus Con... | 1     | i801_smbus | 3701BEE474 |
| 8086:9da3 | 17aa:2294 | Intel      | Cannon Point-LP SMBus Con... | 1     |            | 167048774C |
| 8086:9da3 | 17aa:5077 | Intel      | Cannon Point-LP SMBus Con... | 1     |            | E6D8B9F842 |
| 8086:9da3 | 1854:0333 | Intel      | Cannon Point-LP SMBus Con... | 1     | i801_smbus | 6D2724E820 |
| 8086:a123 | 103c:83bb | Intel      | 100 Series/C230 Series Ch... | 1     | i2c_i801   | CBA3EC356E |
| 8086:a123 | 17aa:3810 | Intel      | 100 Series/C230 Series Ch... | 1     |            | F445F1B326 |
| 8086:a323 | 103c:8519 | Intel      | Cannon Lake PCH SMBus Con... | 1     | i2c_i801   | D764EA82D5 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:5a98 | 1c6c:122a | Intel      | Celeron N3350/Pentium N42... | 5     | snd_hda... | CBA368D785 |
| 8086:9d71 | 103c:830f | Intel      | Sunrise Point-LP HD Audio    | 5     | snd_hda... | 0ECB13EDBF |
| 8086:9d71 | 103c:83b9 | Intel      | Sunrise Point-LP HD Audio    | 5     | snd_hda... | C28AED72AA |
| 8086:9d71 | 103c:8486 | Intel      | Sunrise Point-LP HD Audio    | 5     | snd_hda... | 7DEF867A41 |
| 8086:9d71 | 103c:8488 | Intel      | Sunrise Point-LP HD Audio    | 5     | snd_hda... | 59D61DD321 |
| 8086:9d71 | 17aa:3808 | Intel      | Sunrise Point-LP HD Audio    | 5     | snd_hda... | 33D7D63C6D |
| 1002:15de | 103c:8496 | AMD        | Raven/Raven2/Fenghuang HD... | 4     | snd_hda... | 31DDC7FDCB |
| 1002:15de | 103c:85dd | AMD        | Raven/Raven2/Fenghuang HD... | 4     | snd_hda... | D6005821D4 |
| 1002:15de | 17aa:3803 | AMD        | Raven/Raven2/Fenghuang HD... | 4     | snd_hda... | B0FCF85E0D |
| 1022:15e3 | 103c:8496 | AMD        | Family 17h (Models 10h-1f... | 4     | snd_hda... | 31DDC7FDCB |
| 1022:15e3 | 103c:85dd | AMD        | Family 17h (Models 10h-1f... | 4     | snd_hda... | D6005821D4 |
| 1022:15e3 | 17aa:380c | AMD        | Family 17h (Models 10h-1f... | 4     | snd_hda... | B0FCF85E0D |
| 8086:9d71 | 17aa:224e | Intel      | Sunrise Point-LP HD Audio    | 4     | snd_hda... | 66ACB89125 |
| 8086:9dc8 | 17aa:3814 | Intel      | Cannon Point-LP High Defi... | 4     | snd_hda... | C7DFFC3F2A |
| 8086:2284 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 3     | snd_hda... | 9FAC88C07A |
| 8086:9d70 | 103c:80d1 | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | FD3B38A3F5 |
| 8086:9d70 | 17aa:2238 | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | 3504F119EA |
| 8086:9d70 | 17aa:3801 | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | 5B8D494C04 |
| 8086:9d71 | 103c:827f | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | 1DB4A76555 |
| 8086:9d71 | 103c:84d8 | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | 9B4E7338B0 |
| 8086:9d71 | 17aa:3801 | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | 6D14F41FBD |
| 8086:9d71 | 17aa:3831 | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | 5A7A4AFFFB |
| 8086:9dc8 | 103c:8514 | Intel      | Cannon Point-LP High Defi... | 3     | snd_hda... | 0CF9D0AFB9 |
| 8086:9dc8 | 17aa:2292 | Intel      | Cannon Point-LP High Defi... | 3     | snd_hda... | 7C5B2D05AE |
| 8086:9d70 | 17aa:2237 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 6AA622B728 |
| 8086:9d71 | 1028:07aa | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | DFDC8C484F |
| 8086:9d71 | 1028:07eb | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 7EB57A3809 |
| 8086:9d71 | 103c:827d | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | E9DECBC4FD |
| 8086:9d71 | 103c:827e | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 28AF751D12 |
| 8086:9d71 | 103c:82c1 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | A9E42C34F6 |
| 8086:9d71 | 103c:8313 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 22FE75A663 |
| 8086:9d71 | 103c:83c4 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 65B956E887 |
| 8086:9d71 | 103c:8503 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | F6ABCD9B4F |
| 8086:9d71 | 1043:14f0 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | AD2B007CB9 |
| 8086:9d71 | 1043:1b60 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | C0BC126501 |
| 8086:9d71 | 1043:1c40 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 18B4F9B58E |
| 8086:9d71 | 1043:1c90 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 7BBD1AB6FE |
| 8086:9d71 | 17aa:3804 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | C194639A17 |
| 8086:9d71 | 17aa:3806 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 941DF897AA |
| 8086:9d71 | 17aa:3809 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 1681EDB0F6 |
| 8086:9d71 | 17aa:3827 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | D16FC3AC03 |
| 8086:9d71 | 17aa:3829 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | FC1E9BDE71 |
| 8086:9d71 | 17aa:506c | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 225075209E |
| 8086:9d71 | 1ae0:006b | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 7CCE37A416 |
| 8086:9dc8 | 103c:8518 | Intel      | Cannon Point-LP High Defi... | 2     | snd_hda... | 969C4C3BCB |
| 8086:a171 | 1028:080d | Intel      | CM238 HD Audio Controller    | 2     | snd_hda... | 8CA313CDAD |
| 1002:15b3 | 17aa:3802 | ATI Tec... | High Definition Audio Con... | 1     | snd_hda... | B9FC5DC357 |
| 1002:15b3 | 17aa:3804 | AMD        | High Definition Audio Con... | 1     | snd_hda... | B9FC5DC357 |
| 1002:15de | 103c:8497 | AMD        | Raven/Raven2/Fenghuang HD... | 1     | snd_hda... | D9AF75156B |
| 1002:15de | 103c:85de | AMD        | Raven/Raven2/Fenghuang HD... | 1     | snd_hda... | 70F1D3BF36 |
| 1002:9840 | 103c:81aa | AMD        | Kabini HDMI/DP Audio         | 1     | snd_hda... | D103A0F533 |
| 1002:9840 | 103c:8311 | AMD        | Kabini HDMI/DP Audio         | 1     | snd_hda... | EEE03F79BD |
| 1022:157a | 103c:81aa | AMD        | Family 15h (Models 60h-6f... | 1     | snd_hda... | D103A0F533 |
| 1022:157a | 103c:8311 | AMD        | Family 15h (Models 60h-6f... | 1     | snd_hda... | EEE03F79BD |
| 1022:157a | 17aa:3802 | AMD        | Family 15h (Models 60h-6f... | 1     | snd_hda... | B9FC5DC357 |
| 1022:15e3 | 103c:8497 | AMD        | Family 17h (Models 10h-1f... | 1     | snd_hda... | D9AF75156B |
| 1022:15e3 | 103c:85de | AMD        | Family 17h (Models 10h-1f... | 1     | snd_hda... | 70F1D3BF36 |
| 10de:0fb9 | 17aa:5067 | Nvidia     | GP107GL High Definition A... | 1     | snd_hda... | A2C7E96A52 |
| 8086:02c8 | 1028:0950 | Intel      | Comet Lake PCH-LP cAVS (A... | 1     | snd_hda... | 20ABB6DE72 |
| 8086:02c8 | 103c:866e | Intel      | Comet Lake PCH-LP cAVS (A... | 1     | snd_hda... | 8FF42ABD82 |
| 8086:02c8 | 17aa:2292 | Intel      | Comet Lake PCH-LP cAVS (A... | 1     | snd_hda... | D6B3970321 |
| 8086:02c8 | 17aa:3803 | Intel      | Comet Lake PCH-LP cAVS (A... | 1     | snd_hda... | 702DE7D41F |
| 8086:02c8 | 17aa:3806 | Intel      | Comet Lake PCH-LP cAVS (A... | 1     | snd_hda... | A25721AA13 |
| 8086:0f04 | 103c:802b | Intel      | Atom Processor Z36xxx/Z37... | 1     | snd_hda... | 07B5ECDCCD |
| 8086:160c | 103c:802d | Intel      | Broadwell-U Audio Controller | 1     | snd_hda... | D9CA1DBE13 |
| 8086:160c | 103c:806c | Intel      | Broadwell-U Audio Controller | 1     | snd_hda... | 462F2D5347 |
| 8086:160c | 103c:806e | Intel      | Broadwell-U Audio Controller | 1     | snd_hda... | 62A9EF950E |
| 8086:22a8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | FAB48926D9 |
| 8086:3198 | 10ec:118e | Intel      | Smart Sound Technology (I... | 1     | snd_hda... | 56A7BF3D18 |
| 8086:3198 | 10ec:1190 | Intel      | Smart Sound Technology (I... | 1     | snd_hda... | 11EC0315D7 |
| 8086:3198 | 10ec:1194 | Intel      | Smart Sound Technology (I... | 1     | snd_hda... | 991764DD3F |
| 8086:5a98 | 10ec:11ca | Intel      | Celeron N3350/Pentium N42... | 1     | snd_hda... | 6663E08482 |
| 8086:5a98 | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 1     | snd_hda... | F8913A087C |
| 8086:9ca0 | 103c:806c | Intel      | Wildcat Point-LP High Def... | 1     | snd_hda... | 462F2D5347 |
| 8086:9ca0 | 103c:806e | Intel      | Wildcat Point-LP High Def... | 1     | snd_hda... | 62A9EF950E |
| 8086:9d70 | 103c:804e | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 6F8FD31C2C |
| 8086:9d70 | 103c:80d0 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 97ED13A8C0 |
| 8086:9d70 | 103c:8143 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 49796C6747 |
| 8086:9d70 | 103c:81a1 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | C894E5633B |
| 8086:9d70 | 144d:c141 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 5B28F6FC87 |
| 8086:9d70 | 17aa:504c | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 3C1A4327F5 |
| 8086:9d70 | 17aa:5058 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | C65BB14578 |
| 8086:9d71 | 1025:120d | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | BAE5A5C3DD |
| 8086:9d71 | 1028:077a | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 57D57D82FE |
| 8086:9d71 | 103c:81ad | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 84C8A9779B |
| 8086:9d71 | 103c:8251 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | C77AFE79C3 |
| 8086:9d71 | 103c:83ba | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 3743010FB5 |
| 8086:9d71 | 103c:8438 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 7F01433E42 |
| 8086:9d71 | 103c:8483 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 8B7A2D2A08 |
| 8086:9d71 | 103c:8484 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 1B466FC315 |
| 8086:9d71 | 103c:8487 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | C8C863DB3A |
| 8086:9d71 | 1043:12e1 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 93A44B1518 |
| 8086:9d71 | 1043:14c0 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | FA7C5C4F64 |
| 8086:9d71 | 1043:1ab0 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | B2D75821A4 |
| 8086:9d71 | 1043:1b00 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | A9301396F9 |
| 8086:9d71 | 1043:1b40 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | FF2D426E76 |
| 8086:9d71 | 1043:1cf0 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 2C6BCC75CC |
| 8086:9d71 | 144d:c14c | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 6E023867E9 |
| 8086:9d71 | 152d:1147 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 7DA5C4A4FA |
| 8086:9d71 | 17aa:3828 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 3C97527813 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | ahci       | CBA368D785 |
| 8086:9d03 | 103c:830f | Intel      | Sunrise Point-LP SATA Con... | 5     | ahci       | 0ECB13EDBF |
| 8086:9d03 | 103c:8486 | Intel      | Sunrise Point-LP SATA Con... | 5     | ahci       | 7DEF867A41 |
| 1022:7901 | 103c:8496 | AMD        | FCH SATA Controller [AHCI... | 4     | ahci       | 31DDC7FDCB |
| 8086:9d03 | 103c:8488 | Intel      | Sunrise Point-LP SATA Con... | 4     | ahci       | 59D61DD321 |
| 8086:9dd3 | 17aa:3806 | Intel      | Cannon Point-LP SATA Cont... | 4     | ahci       | C7DFFC3F2A |
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 3     | ahci       | 447751C623 |
| 8086:31e3 | 8086:7270 | Intel      | SATA controller              | 3     | ahci       | 991764DD3F |
| 8086:9d03 | 103c:80d1 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | FD3B38A3F5 |
| 8086:9d03 | 103c:84d8 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 9B4E7338B0 |
| 8086:9d03 | 17aa:380d | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 5B8D494C04 |
| 8086:9d03 | 17aa:3822 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 6D14F41FBD |
| 8086:9d03 | 17aa:383b | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 33D7D63C6D |
| 8086:9d03 | 1028:07eb | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 7EB57A3809 |
| 8086:9d03 | 103c:8313 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 22FE75A663 |
| 8086:9d03 | 103c:83c4 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 65B956E887 |
| 8086:9d03 | 1043:14f0 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | AD2B007CB9 |
| 8086:9d03 | 1043:1c40 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 18B4F9B58E |
| 8086:9d03 | 17aa:3810 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | C194639A17 |
| 1022:7901 | 103c:8497 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | D9AF75156B |
| 1022:7904 | 103c:81aa | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | D103A0F533 |
| 1022:7904 | 103c:8311 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | EEE03F79BD |
| 1022:7904 | 17aa:3804 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | B9FC5DC357 |
| 8086:02d3 | 1028:0950 | Intel      | Comet Lake SATA AHCI Cont... | 1     | ahci       | 20ABB6DE72 |
| 8086:02d3 | 17aa:3802 | Intel      | Comet Lake SATA AHCI Cont... | 1     | ahci       | 702DE7D41F |
| 8086:5ae3 | 17aa:3803 | Intel      | Celeron N3350/Pentium N42... | 1     | ahci       | F8913A087C |
| 8086:9c83 | 103c:802d | Intel      | Wildcat Point-LP SATA Con... | 1     | ahci       | D9CA1DBE13 |
| 8086:9c83 | 103c:806c | Intel      | Wildcat Point-LP SATA Con... | 1     | ahci       | 462F2D5347 |
| 8086:9c83 | 103c:806e | Intel      | Wildcat Point-LP SATA Con... | 1     | ahci       | 62A9EF950E |
| 8086:9d03 | 1025:120d | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | BAE5A5C3DD |
| 8086:9d03 | 103c:804e | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 6F8FD31C2C |
| 8086:9d03 | 103c:80d0 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 97ED13A8C0 |
| 8086:9d03 | 103c:8143 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 49796C6747 |
| 8086:9d03 | 103c:81a1 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | C894E5633B |
| 8086:9d03 | 103c:81ad | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 84C8A9779B |
| 8086:9d03 | 103c:8251 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | C77AFE79C3 |
| 8086:9d03 | 103c:8483 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 8B7A2D2A08 |
| 8086:9d03 | 103c:8484 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 1B466FC315 |
| 8086:9d03 | 103c:8487 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | C8C863DB3A |
| 8086:9d03 | 1043:12e1 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 93A44B1518 |
| 8086:9d03 | 1043:14c0 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | FA7C5C4F64 |
| 8086:9d03 | 1043:1ab0 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | B2D75821A4 |
| 8086:9d03 | 1043:1b00 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | A9301396F9 |
| 8086:9d03 | 1043:1b40 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | FF2D426E76 |
| 8086:9d03 | 1043:1c90 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 7BBD1AB6FE |
| 8086:9d03 | 144d:c141 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 5B28F6FC87 |
| 8086:9d03 | 144d:c14c | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 6E023867E9 |
| 8086:9d03 | 17aa:2237 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 20176595EA |
| 8086:9d03 | 17aa:2238 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | C480CEB1FC |
| 8086:9d03 | 17aa:504c | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 3C1A4327F5 |
| 8086:9d03 | 17aa:5058 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | C65BB14578 |
| 8086:9d03 | 8086:9d03 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | C3AA237F35 |
| 8086:9dd3 | 1854:0333 | Intel      | Cannon Point-LP SATA Cont... | 1     | ahci       | 6D2724E820 |
| 8086:a103 | 103c:83bb | Intel      | HM170/QM170 Chipset SATA ... | 1     | ahci       | CBA3EC356E |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 26    | nvme       | C7DFFC3F2A |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 15    | nvme       | 66ACB89125 |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 10    | nvme       | 0CF9D0AFB9 |
| 1179:0113 | 1179:0001 | Toshiba... | BG3 NVMe SSD Controller      | 6     | nvme       | 59D61DD321 |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/PC SN720 NV... | 5     | nvme       | CDF9A3949B |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | Non-Volatile memory contr... | 5     | nvme       | D6005821D4 |
| 1179:0115 | 1179:0001 | Toshiba... | XG4 NVMe SSD Controller      | 4     | nvme       | 28AF751D12 |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 3     | nvme       | 3504F119EA |
| 1179:011a | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 2     | nvme       | 8CA313CDAD |
| 1c5c:1527 | 1c5c:1527 | SK Hynix   | Non-Volatile memory contr... | 2     | nvme       | 5A7A4AFFFB |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 2     | nvme       | 7DA5C4A4FA |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 2     | nvme       | 167048774C |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 2     | nvme       | 70F1D3BF36 |
| 10ec:5762 | 10ec:5762 | Realtek... | Realtek Non-Volatile memo... | 1     | nvme       | BC69AFD822 |
| 14a4:2100 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 1     | nvme       | C28AED72AA |
| 14a4:9100 | 126f:2263 | Lite-On... | NVMe Controller              | 1     | nvme       | 902D25ABA3 |
| 15b7:5005 | 15b7:5005 | Sandisk    | Non-Volatile memory contr... | 1     | nvme       | FC1E9BDE71 |
| 1c5c:1284 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 1     | nvme       | 1DB4A76555 |
| 1cc4:2260 | 1cc4:2260 | Union M... | Non-Volatile memory contr... | 1     | nvme       | CE03C99485 |
| 1cc4:5008 | 1cc4:5008 | Union M... | Non-Volatile memory contr... | 1     | nvme       | B0FCF85E0D |
| 1e0f:0001 | 1e0f:0001 |            | Non-Volatile memory contr... | 1     | nvme       | A25721AA13 |
| 8086:0975 | 8086:8410 | Intel      | Non-Volatile memory contr... | 1     | nvme       | 20ABB6DE72 |
| 8086:0975 | 8086:8510 | Intel      | Non-Volatile memory contr... | 1     | nvme       | 20ABB6DE72 |
| c0a9:2263 | c0a9:2263 | Micron/... | P1 NVMe PCIe SSD             | 1     | nvme       | D16FC3AC03 |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:282a | 17aa:380e | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 419565138F |
| 8086:282a | 1028:077a | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 57D57D82FE |
| 8086:282a | 1028:07aa | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | DFDC8C484F |
| 8086:282a | 1028:089e | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | D256E89F2D |
| 8086:282a | 1028:089f | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 70A45F8830 |
| 8086:282a | 103c:8488 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | AC5527757D |
| 8086:282a | 103c:866e | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 8FF42ABD82 |
| 8086:282a | 17aa:3806 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 0C84774BED |
| 8086:282a | 17aa:380b | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 1681EDB0F6 |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:15d2 | 17aa:2292 | Intel      | JHL6540 Thunderbolt 3 NHI... | 4     | thunder... | 7C5B2D05AE |
| 8086:1911 | 17aa:224e | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | 66ACB89125 |
| 8086:1911 | 17aa:2292 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | 7C5B2D05AE |
| 8086:1911 | 17aa:385b | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | C7DFFC3F2A |
| 8086:15d2 | 103c:8514 | Intel      | JHL6540 Thunderbolt 3 NHI... | 3     | thunder... | 0CF9D0AFB9 |
| 8086:1911 | 17aa:2238 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | 3504F119EA |
| 8086:15d2 | 103c:8503 | Intel      | JHL6540 Thunderbolt 3 NHI... | 2     | thunder... | F6ABCD9B4F |
| 8086:15d2 | 2222:1111 | Intel      | JHL6540 Thunderbolt 3 NHI... | 2     | thunder... | A2C7E96A52 |
| 8086:15d9 | 103c:8518 | Intel      | JHL6340 Thunderbolt 3 NHI... | 2     | thunder... | 969C4C3BCB |
| 8086:1911 | 103c:8503 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | F6ABCD9B4F |
| 8086:1911 | 17aa:2237 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 6AA622B728 |
| 8086:1911 | 17aa:3804 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 941DF897AA |
| 8086:1911 | 1ae0:006b | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 7CCE37A416 |
| 8086:15bf | 17aa:2294 | Intel      | JHL6240 Thunderbolt 3 NHI... | 1     | thunder... | 167048774C |
| 8086:15d2 | 103c:8438 | Intel      | JHL6540 Thunderbolt 3 NHI... | 1     | thunder... | 7F01433E42 |
| 8086:15d2 | 144d:c812 | Intel      | JHL6540 Thunderbolt 3 NHI... | 1     | thunder... | 3701BEE474 |
| 8086:15d2 | 8086:0000 | Intel      | JHL6540 Thunderbolt 3 NHI... | 1     | thunder... | 62AF0556D3 |
| 8086:15d9 | 2222:1111 | Intel      | JHL6340 Thunderbolt 3 NHI... | 1     | thunder... | E9DECBC4FD |
| 8086:15e8 | 1028:0950 | Intel      | JHL7540 Thunderbolt 3 NHI... | 1     | thunder... | 20ABB6DE72 |
| 8086:15eb | 10c3:8519 | Intel      | JHL7540 Thunderbolt 3 NHI... | 1     | thunder... | D764EA82D5 |
| 8086:1911 | 1028:089e | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | D256E89F2D |
| 8086:1911 | 1028:089f | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 70A45F8830 |
| 8086:1911 | 1028:0950 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 20ABB6DE72 |
| 8086:1911 | 103c:866e | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 8FF42ABD82 |
| 8086:1911 | 1043:12e1 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 93A44B1518 |
| 8086:1911 | 17aa:2294 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 167048774C |
| 8086:1911 | 17aa:3806 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | A25721AA13 |
| 8086:1911 | 17aa:3869 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 702DE7D41F |
| 8086:1911 | 17aa:504c | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 3C1A4327F5 |
| 8086:1911 | 17aa:506d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 0818236221 |
| 8086:1911 | 17aa:5077 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | E6D8B9F842 |
| 8086:1911 | 1854:0333 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 6D2724E820 |
| 8086:1911 | 8086:1911 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | C3AA237F35 |

### Unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:5aa2 | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | F8913A087C |
| 8086:5aa2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | 6663E08482 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d2f | 1043:201f | Intel      | Sunrise Point-LP USB 3.0 ... | 14    | xhci_hcd   | 18B4F9B58E |
| 8086:22b5 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 8     | xhci_hcd   | C3F66A8352 |
| 8086:5aa8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | xhci_hcd   | CBA368D785 |
| 8086:9d2f | 103c:830f | Intel      | Sunrise Point-LP USB 3.0 ... | 5     | xhci_hcd   | 0ECB13EDBF |
| 8086:9d2f | 103c:83b9 | Intel      | Sunrise Point-LP USB 3.0 ... | 5     | xhci_hcd   | C28AED72AA |
| 8086:9d2f | 103c:8486 | Intel      | Sunrise Point-LP USB 3.0 ... | 5     | xhci_hcd   | 7DEF867A41 |
| 8086:9d2f | 103c:8488 | Intel      | Sunrise Point-LP USB 3.0 ... | 5     | xhci_hcd   | 59D61DD321 |
| 8086:9d2f | 17aa:383f | Intel      | Sunrise Point-LP USB 3.0 ... | 5     | xhci_hcd   | 33D7D63C6D |
| 1022:15e0 | 103c:8496 | AMD        | Raven USB 3.1                | 4     | xhci_hcd   | 31DDC7FDCB |
| 1022:15e0 | 103c:85dd | AMD        | Raven USB 3.1                | 4     | xhci_pci   | D6005821D4 |
| 1022:15e0 | 17aa:3805 | AMD        | Raven USB 3.1                | 4     | xhci_hcd   | B0FCF85E0D |
| 1022:15e1 | 103c:8496 | AMD        | Raven USB 3.1                | 4     | xhci_hcd   | 31DDC7FDCB |
| 1022:15e1 | 103c:85dd | AMD        | Raven USB 3.1                | 4     | xhci_pci   | D6005821D4 |
| 1022:15e1 | 17aa:3806 | AMD        | Raven USB 3.1                | 4     | xhci_hcd   | B0FCF85E0D |
| 8086:15d4 | 17aa:2292 | Intel      | JHL6540 Thunderbolt 3 USB... | 4     | xhci_hcd   | 7C5B2D05AE |
| 8086:15d4 | 2222:1111 | Intel      | JHL6540 Thunderbolt 3 USB... | 4     | xhci_hcd   | AC8A41B387 |
| 8086:9d2f | 17aa:224e | Intel      | Sunrise Point-LP USB 3.0 ... | 4     | xhci_hcd   | 66ACB89125 |
| 8086:9ded | 17aa:3807 | Intel      | Cannon Point-LP USB 3.1 x... | 4     | xhci_pci   | C7DFFC3F2A |
| 8086:15d4 | 103c:8514 | Intel      | JHL6540 Thunderbolt 3 USB... | 3     | xhci_hcd   | 0CF9D0AFB9 |
| 8086:22b5 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 3     | xhci_hcd   | 9FAC88C07A |
| 8086:31a8 | 8086:7270 | Intel      | USB Controller               | 3     | xhci_hcd   | 991764DD3F |
| 8086:9d2f | 103c:80d1 | Intel      | Sunrise Point-LP USB 3.0 ... | 3     | xhci_hcd   | FD3B38A3F5 |
| 8086:9d2f | 103c:827f | Intel      | Sunrise Point-LP USB 3.0 ... | 3     | xhci_hcd   | 1DB4A76555 |
| 8086:9d2f | 103c:84d8 | Intel      | Sunrise Point-LP USB 3.0 ... | 3     | xhci_hcd   | 9B4E7338B0 |
| 8086:9d2f | 17aa:2238 | Intel      | Sunrise Point-LP USB 3.0 ... | 3     | xhci_hcd   | 3504F119EA |
| 8086:9d2f | 17aa:3811 | Intel      | Sunrise Point-LP USB 3.0 ... | 3     | xhci_hcd   | 5B8D494C04 |
| 8086:9d2f | 17aa:3825 | Intel      | Sunrise Point-LP USB 3.0 ... | 3     | xhci_pci   | 6D14F41FBD |
| 8086:9d2f | 17aa:386a | Intel      | Sunrise Point-LP USB 3.0 ... | 3     | xhci_hcd   | 5A7A4AFFFB |
| 8086:9ded | 103c:8514 | Intel      | Cannon Point-LP USB 3.1 x... | 3     | xhci_hcd   | 0CF9D0AFB9 |
| 8086:9ded | 17aa:2292 | Intel      | Cannon Point-LP USB 3.1 x... | 3     | xhci_hcd   | 7C5B2D05AE |
| 8086:15d4 | 103c:8503 | Intel      | JHL6540 Thunderbolt 3 USB... | 2     | xhci_hcd   | F6ABCD9B4F |
| 8086:15db | 103c:8518 | Intel      | JHL6340 Thunderbolt 3 USB... | 2     | xhci_hcd   | 969C4C3BCB |
| 8086:9d2f | 1028:07aa | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | DFDC8C484F |
| 8086:9d2f | 1028:07eb | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | 7EB57A3809 |
| 8086:9d2f | 103c:827d | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | E9DECBC4FD |
| 8086:9d2f | 103c:827e | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | 28AF751D12 |
| 8086:9d2f | 103c:82c1 | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | A9E42C34F6 |
| 8086:9d2f | 103c:8313 | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | 22FE75A663 |
| 8086:9d2f | 103c:83c4 | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | 65B956E887 |
| 8086:9d2f | 103c:8503 | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | F6ABCD9B4F |
| 8086:9d2f | 17aa:2237 | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | 6AA622B728 |
| 8086:9d2f | 17aa:3805 | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | 941DF897AA |
| 8086:9d2f | 17aa:380b | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | C194639A17 |
| 8086:9d2f | 17aa:383e | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | 1681EDB0F6 |
| 8086:9d2f | 17aa:3861 | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | D16FC3AC03 |
| 8086:9d2f | 17aa:3864 | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | FC1E9BDE71 |
| 8086:9d2f | 17aa:506c | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | 225075209E |
| 8086:9d2f | 1ae0:006b | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | 7CCE37A416 |
| 8086:9ded | 103c:8518 | Intel      | Cannon Point-LP USB 3.1 x... | 2     | xhci_hcd   | 969C4C3BCB |
| 8086:a12f | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 2     | xhci_hcd   | 8CA313CDAD |
| 1022:15e0 | 103c:8497 | AMD        | Raven USB 3.1                | 1     | xhci_hcd   | D9AF75156B |
| 1022:15e0 | 103c:85de | AMD        | Raven USB 3.1                | 1     | xhci_hcd   | 70F1D3BF36 |
| 1022:15e1 | 103c:8497 | AMD        | Raven USB 3.1                | 1     | xhci_hcd   | D9AF75156B |
| 1022:15e1 | 103c:85de | AMD        | Raven USB 3.1                | 1     | xhci_hcd   | 70F1D3BF36 |
| 1022:7908 | 103c:81aa | AMD        | FCH USB EHCI Controller      | 1     | ehci_pci   | D103A0F533 |
| 1022:7908 | 103c:8311 | AMD        | FCH USB EHCI Controller      | 1     | ehci_pci   | EEE03F79BD |
| 1022:7908 | 17aa:3802 | AMD        | FCH USB EHCI Controller      | 1     | ehci_pci   | B9FC5DC357 |
| 1022:7914 | 103c:81aa | AMD        | FCH USB XHCI Controller      | 1     | xhci_hcd   | D103A0F533 |
| 1022:7914 | 103c:8311 | AMD        | FCH USB XHCI Controller      | 1     | xhci_hcd   | EEE03F79BD |
| 1022:7914 | 17aa:3802 | AMD        | FCH USB XHCI Controller      | 1     | xhci_hcd   | B9FC5DC357 |
| 1b21:1142 | 103c:8190 | ASMedia... | ASM1042A USB 3.0 Host Con... | 1     | xhci_hcd   | E9DECBC4FD |
| 1b73:1100 | 17ef:3067 | Fresco ... | FL1100 USB 3.0 Host Contr... | 1     | xhci_hcd   | 3AC5B5C4AD |
| 1b73:1100 | 17ef:3068 | Fresco ... | FL1100 USB 3.0 Host Contr... | 1     | xhci_hcd   | 3AC5B5C4AD |
| 8086:02ed | 1028:0950 | Intel      | Comet Lake PCH-LP USB 3.1... | 1     | xhci_hcd   | 20ABB6DE72 |
| 8086:02ed | 103c:866e | Intel      | Comet Lake PCH-LP USB 3.1... | 1     | xhci_hcd   | 8FF42ABD82 |
| 8086:02ed | 17aa:2292 | Intel      | Comet Lake PCH-LP USB 3.1... | 1     | xhci_hcd   | D6B3970321 |
| 8086:02ed | 17aa:3806 | Intel      | Comet Lake PCH-LP USB 3.1... | 1     | xhci_hcd   | A25721AA13 |
| 8086:02ed | 17aa:380a | Intel      | Comet Lake PCH-LP USB 3.1... | 1     | xhci_hcd   | 702DE7D41F |
| 8086:0f35 | 103c:802b | Intel      | Atom Processor Z36xxx/Z37... | 1     | xhci_pci   | 07B5ECDCCD |
| 8086:15c1 | 17aa:2294 | Intel      | JHL6240 Thunderbolt 3 USB... | 1     | xhci_hcd   | 167048774C |
| 8086:15d4 |           | Intel      | JHL6540 Thunderbolt 3 USB... | 1     | xhci_hcd   | 1510224C03 |
| 8086:15d4 | 103c:8438 | Intel      | JHL6540 Thunderbolt 3 USB... | 1     | xhci_hcd   | 7F01433E42 |
| 8086:15d4 | 144d:c812 | Intel      | JHL6540 Thunderbolt 3 USB... | 1     | xhci_hcd   | 3701BEE474 |
| 8086:15d4 | 17aa:1111 | Intel      | JHL6540 Thunderbolt 3 USB... | 1     | xhci_hcd   | A2C7E96A52 |
| 8086:15d4 | 8086:0000 | Intel      | JHL6540 Thunderbolt 3 USB... | 1     | xhci_hcd   | 8CA313CDAD |
| 8086:15db | 2222:1111 | Intel      | JHL6340 Thunderbolt 3 USB... | 1     | xhci_hcd   | 7E10A5E689 |
| 8086:15e9 | 1028:0950 | Intel      | JHL7540 Thunderbolt 3 USB... | 1     | xhci_hcd   | 20ABB6DE72 |
| 8086:15ec | 10c3:8519 | Intel      | JHL7540 Thunderbolt 3 USB... | 1     | xhci_pci   | D764EA82D5 |
| 8086:22b7 | 8086:7270 | Intel      | USB Synopsys Controller      | 1     |            | FAB48926D9 |
| 8086:5aa8 | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 1     | xhci_hcd   | F8913A087C |
| 8086:9ca6 | 103c:806c | Intel      | Wildcat Point-LP USB EHCI... | 1     | ehci_pci   | 462F2D5347 |
| 8086:9cb1 | 103c:802d | Intel      | Wildcat Point-LP USB xHCI... | 1     | xhci_hcd   | D9CA1DBE13 |
| 8086:9cb1 | 103c:806c | Intel      | Wildcat Point-LP USB xHCI... | 1     |            | 462F2D5347 |
| 8086:9cb1 | 103c:806e | Intel      | Wildcat Point-LP USB xHCI... | 1     | xhci_pci   | 62A9EF950E |
| 8086:9d2f | 1025:120d | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | BAE5A5C3DD |
| 8086:9d2f | 1028:077a | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 57D57D82FE |
| 8086:9d2f | 103c:804e | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 6F8FD31C2C |
| 8086:9d2f | 103c:80d0 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 97ED13A8C0 |
| 8086:9d2f | 103c:8143 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 49796C6747 |
| 8086:9d2f | 103c:81a1 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | C894E5633B |
| 8086:9d2f | 103c:81ad | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 84C8A9779B |
| 8086:9d2f | 103c:8251 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | C77AFE79C3 |
| 8086:9d2f | 103c:83ba | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 3743010FB5 |
| 8086:9d2f | 103c:8438 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 7F01433E42 |
| 8086:9d2f | 103c:8483 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 8B7A2D2A08 |
| 8086:9d2f | 103c:8484 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 1B466FC315 |
| 8086:9d2f | 103c:8487 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | C8C863DB3A |
| 8086:9d2f | 144d:c141 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 5B28F6FC87 |
| 8086:9d2f | 144d:c14c | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 6E023867E9 |
| 8086:9d2f | 152d:1147 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 7DA5C4A4FA |

### Wireless controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:7360 | 8086:0020 | Intel      | XMM7360 LTE Advanced Modem   | 2     |            | 7C5B2D05AE |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:694e | 1002:694e | AMD        | Polaris 22 XL [Radeon RX ... | 1     | amdgpu     | 07A9851CD6 |
| 10ec-b... |           | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 1     | rtwpci     | D6005821D4 |

