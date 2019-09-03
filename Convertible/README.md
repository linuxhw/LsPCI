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
| 1022:1452 |           | AMD        | Family 17h (Models 00h-1f... | 6     |            | 52036BD95B |
| 1022:15db | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 6     | pcieport   | 52036BD95B |
| 1022:15e8 |           | AMD        | Raven/Raven2 Device 24: F... | 6     |            | 52036BD95B |
| 1022:15e9 |           | AMD        | Raven/Raven2 Device 24: F... | 6     |            | 52036BD95B |
| 1022:15ea |           | AMD        | Raven/Raven2 Device 24: F... | 6     |            | 52036BD95B |
| 1022:15eb |           | AMD        | Raven/Raven2 Device 24: F... | 6     | k10temp    | 52036BD95B |
| 1022:15ec |           | AMD        | Raven/Raven2 Device 24: F... | 6     |            | 52036BD95B |
| 1022:15ed |           | AMD        | Raven/Raven2 Device 24: F... | 6     |            | 52036BD95B |
| 1022:15ee |           | AMD        | Raven/Raven2 Device 24: F... | 6     |            | 52036BD95B |
| 1022:15ef |           | AMD        | Raven/Raven2 Device 24: F... | 6     |            | 52036BD95B |
| 8086:2280 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 6     | iosf_mb... | FAB48926D9 |
| 8086:229c | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 6     | lpc_ich    | FAB48926D9 |
| 1022:15dc | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 5     | pcieport   | 52036BD95B |
| 8086:5904 | 103c:8486 | Intel      | Xeon E3-1200 v6/7th Gen C... | 5     | skl_uncore | 7DEF867A41 |
| 8086:9d15 | 103c:8486 | Intel      | Sunrise Point-LP PCI Expr... | 5     | pcieport   | 7DEF867A41 |
| 8086:9d4e | 103c:8486 | Intel      | Sunrise Point LPC Control... | 5     |            | 7DEF867A41 |
| 8086:9d15 | 103c:8488 | Intel      | Sunrise Point-LP PCI Expr... | 4     | shpchp     | 2F6DFEC51C |
| 8086:9d4e | 103c:8488 | Intel      | Sunrise Point LPC Control... | 4     |            | 2F6DFEC51C |
| 1022:15d0 | 17aa:380a | AMD        | Raven/Raven2 Root Complex    | 3     |            | 52036BD95B |
| 1022:15d3 | 1022:1453 | AMD        | Raven/Raven2 PCIe GPP Bri... | 3     | pcieport   | 52036BD95B |
| 1022:790e | 17aa:3819 | AMD        | FCH LPC Bridge               | 3     |            | 52036BD95B |
| 8086:15d3 | 2222:1111 | Intel      | JHL6540 Thunderbolt 3 Bri... | 3     | pcieport   | 3AC5B5C4AD |
| 8086:1904 | 103c:80d1 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | skl_uncore | FD3B38A3F5 |
| 8086:1904 | 17aa:380b | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | skl_uncore | 5B8D494C04 |
| 8086:5904 | 103c:830f | Intel      | Xeon E3-1200 v6/7th Gen C... | 3     |            | C4D6A7BC54 |
| 8086:5914 | 103c:83b9 | Intel      | Xeon E3-1200 v6/7th Gen C... | 3     | skl_uncore | 831911B060 |
| 8086:5914 | 103c:8488 | Intel      | Xeon E3-1200 v6/7th Gen C... | 3     | skl_uncore | 2F6DFEC51C |
| 8086:5ad7 |           | Intel      | Celeron N3350/Pentium N42... | 3     | pcieport   | E95114CACB |
| 8086:5ae8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | lpc_ich    | E95114CACB |
| 8086:5af0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     |            | E95114CACB |
| 8086:9d10 | 103c:80d1 | Intel      | Sunrise Point-LP PCI Expr... | 3     | shpchp     | FD3B38A3F5 |
| 8086:9d10 | 103c:83b9 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 831911B060 |
| 8086:9d11 | 103c:83b9 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 831911B060 |
| 8086:9d14 | 103c:80d1 | Intel      | Sunrise Point-LP PCI Expr... | 3     | shpchp     | FD3B38A3F5 |
| 8086:9d14 | 103c:83b9 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 831911B060 |
| 8086:9d14 | 17aa:3801 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 5B8D494C04 |
| 8086:9d15 | 103c:80d1 | Intel      | Sunrise Point-LP PCI Expr... | 3     | shpchp     | FD3B38A3F5 |
| 8086:9d15 | 17aa:3801 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 5B8D494C04 |
| 8086:9d18 | 103c:80d1 | Intel      | Sunrise Point-LP PCI Expr... | 3     | shpchp     | FD3B38A3F5 |
| 8086:9d18 | 103c:830f | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | C4D6A7BC54 |
| 8086:9d18 | 103c:83b9 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 831911B060 |
| 8086:9d18 | 103c:8488 | Intel      | Sunrise Point-LP PCI Expr... | 3     | shpchp     | 2F6DFEC51C |
| 8086:9d18 | 17aa:3809 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 5B8D494C04 |
| 8086:9d19 | 103c:830f | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | C4D6A7BC54 |
| 8086:9d48 | 103c:80d1 | Intel      | Sunrise Point-LP LPC Cont... | 3     |            | FD3B38A3F5 |
| 8086:9d4e | 103c:830f | Intel      | Sunrise Point LPC Control... | 3     |            | C4D6A7BC54 |
| 8086:9d4e | 103c:83b9 | Intel      | Sunrise Point LPC Control... | 3     |            | 831911B060 |
| 1022:157b |           | AMD        | Family 15h (Models 60h-6f... | 2     |            | B9FC5DC357 |
| 1022:157d |           | AMD        | Carrizo Audio Dummy Host ... | 2     |            | B9FC5DC357 |
| 1022:15d0 | 103c:8496 | AMD        | Raven/Raven2 Root Complex    | 2     |            | F720A735A8 |
| 1022:15d3 | 103c:8496 | AMD        | Raven/Raven2 PCIe GPP Bri... | 2     | pcieport   | F720A735A8 |
| 1022:790e | 103c:8496 | AMD        | FCH LPC Bridge               | 2     |            | F720A735A8 |
| 8086:15d3 |           | Intel      | JHL6540 Thunderbolt 3 Bri... | 2     | pcieport   | 3AC5B5C4AD |
| 8086:15d3 | 103c:8514 | Intel      | JHL6540 Thunderbolt 3 Bri... | 2     | pcieport   | 74DD313167 |
| 8086:15da | 2222:1111 | Intel      | JHL6340 Thunderbolt 3 Bri... | 2     | pcieport   | 7E10A5E689 |
| 8086:1901 | 1028:080d | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | pcieport   | 62AF0556D3 |
| 8086:31d8 | 8086:7270 | Intel      | Gemini Lake PCI Express R... | 2     | pcieport   | 56A7BF3D18 |
| 8086:31e8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     |            | 56A7BF3D18 |
| 8086:31f0 |           | Intel      | Gemini Lake Host Bridge      | 2     |            | 56A7BF3D18 |
| 8086:3e34 | 103c:8514 | Intel      | Coffee Lake HOST and DRAM... | 2     |            | 74DD313167 |
| 8086:5904 | 103c:827d | Intel      | Xeon E3-1200 v6/7th Gen C... | 2     | skl_uncore | AE7D79F749 |
| 8086:5904 | 103c:82c1 | Intel      | Xeon E3-1200 v6/7th Gen C... | 2     |            | A9E42C34F6 |
| 8086:5904 | 103c:8313 | Intel      | Xeon E3-1200 v6/7th Gen C... | 2     | skl_uncore | 22FE75A663 |
| 8086:5904 | 17aa:224e | Intel      | Xeon E3-1200 v6/7th Gen C... | 2     | skl_uncore | 3AC5B5C4AD |
| 8086:5904 | 17aa:3803 | Intel      | Xeon E3-1200 v6/7th Gen C... | 2     | skl_uncore | 941DF897AA |
| 8086:5910 | 1028:080d | Intel      | Xeon E3-1200 v6/7th Gen C... | 2     |            | 62AF0556D3 |
| 8086:5914 | 1028:07eb | Intel      | Xeon E3-1200 v6/7th Gen C... | 2     | skl_uncore | 7EB57A3809 |
| 8086:5914 | 103c:83c4 | Intel      | Xeon E3-1200 v6/7th Gen C... | 2     |            | 65B956E887 |
| 8086:5914 | 103c:84d8 | Intel      | Xeon E3-1200 v6/7th Gen C... | 2     | skl_uncore | A9BAF3BF1B |
| 8086:5914 | 1043:1c90 | Intel      | Xeon E3-1200 v6/7th Gen C... | 2     | skl_uncore | 7BBD1AB6FE |
| 8086:5914 | 17aa:3821 | Intel      | Xeon E3-1200 v6/7th Gen C... | 2     | skl_uncore | 83192A2228 |
| 8086:9d10 | 103c:827d | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | AE7D79F749 |
| 8086:9d10 | 103c:82c1 | Intel      | Sunrise Point-LP PCI Expr... | 2     | shpchp     | A9E42C34F6 |
| 8086:9d10 | 17aa:224e | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | 3AC5B5C4AD |
| 8086:9d10 | 17aa:384f | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | 83192A2228 |
| 8086:9d12 | 17aa:224e | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | 3AC5B5C4AD |
| 8086:9d14 | 103c:827d | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | AE7D79F749 |
| 8086:9d14 | 103c:82c1 | Intel      | Sunrise Point-LP PCI Expr... | 2     | shpchp     | A9E42C34F6 |
| 8086:9d14 | 103c:84d8 | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | A9BAF3BF1B |
| 8086:9d14 | 17aa:224e | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | 3AC5B5C4AD |
| 8086:9d14 | 17aa:3805 | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | 941DF897AA |
| 8086:9d14 | 17aa:3835 | Intel      | Sunrise Point-LP PCI Expr... | 2     | shpchp     | AC774199A8 |
| 8086:9d14 | 17aa:385b | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | 83192A2228 |
| 8086:9d15 | 1028:07eb | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | 7EB57A3809 |
| 8086:9d15 | 103c:827d | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | AE7D79F749 |
| 8086:9d15 | 103c:84d8 | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | A9BAF3BF1B |
| 8086:9d15 | 17aa:382f | Intel      | Sunrise Point-LP PCI Expr... | 2     | shpchp     | AC774199A8 |
| 8086:9d16 | 103c:82c1 | Intel      | Sunrise Point-LP PCI Expr... | 2     | shpchp     | A9E42C34F6 |
| 8086:9d16 | 1043:1c90 | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | 7BBD1AB6FE |
| 8086:9d17 | 103c:82c1 | Intel      | Sunrise Point-LP PCI Expr... | 2     | shpchp     | A9E42C34F6 |
| 8086:9d18 | 103c:827d | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | AE7D79F749 |
| 8086:9d18 | 103c:82c1 | Intel      | Sunrise Point-LP PCI Expr... | 2     | shpchp     | A9E42C34F6 |
| 8086:9d18 | 103c:8313 | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | 22FE75A663 |
| 8086:9d18 | 103c:83c4 | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | 65B956E887 |
| 8086:9d18 | 103c:84d8 | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | A9BAF3BF1B |
| 8086:9d18 | 17aa:224e | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | 3AC5B5C4AD |
| 8086:9d18 | 17aa:3805 | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | 941DF897AA |
| 8086:9d18 | 17aa:382a | Intel      | Sunrise Point-LP PCI Expr... | 2     | shpchp     | AC774199A8 |
| 8086:9d18 | 17aa:384b | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | 83192A2228 |
| 8086:9d19 | 103c:8313 | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | 22FE75A663 |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:5229 | 17aa:380d | Realtek... | RTS5229 PCI Express Card ... | 3     | rtsx_pci   | 5B8D494C04 |
| 10ec:522a | 103c:80d1 | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | FD3B38A3F5 |
| 10ec:522a | 103c:830f | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | C4D6A7BC54 |
| 10ec:525a | 103c:83b9 | Realtek... | RTS525A PCI Express Card ... | 3     | rtsx_pci   | 831911B060 |
| 10ec:5229 | 17aa:3832 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | AC774199A8 |
| 10ec:522a | 103c:827d | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | AE7D79F749 |
| 10ec:522a | 103c:8313 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 22FE75A663 |
| 10ec:522a | 103c:83c4 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 65B956E887 |
| 10ec:522a | 103c:8496 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | F720A735A8 |
| 10ec:525a | 1028:080d | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx_pci   | 62AF0556D3 |
| 10ec:525a | 103c:82c1 | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx_pci   | A9E42C34F6 |
| 10ec:525a | 103c:8514 | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx_pci   | 74DD313167 |
| 10ec:525a | 17aa:224e | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx_pci   | 3AC5B5C4AD |
| 10ec:5227 | 103c:802b | Realtek... | RTS5227 PCI Express Card ... | 1     | rtsx_pci   | 07B5ECDCCD |
| 10ec:5227 | 103c:802d | Realtek... | RTS5227 PCI Express Card ... | 1     | rtsx_pci   | D9CA1DBE13 |
| 10ec:5227 | 103c:81a1 | Realtek... | RTS5227 PCI Express Card ... | 1     | rtsx_pci   | C894E5633B |
| 10ec:5229 | 103c:81aa | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | D103A0F533 |
| 10ec:5229 | 103c:82e1 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | BE4128010B |
| 10ec:5229 | 17aa:3810 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | B9FC5DC357 |
| 10ec:5229 | 17aa:381b | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | A388F4B414 |
| 10ec:5229 | 17aa:381d | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | A295EE15E6 |
| 10ec:522a | 103c:806e | Realtek... | RTS522A PCI Express Card ... | 1     |            | 62A9EF950E |
| 10ec:522a | 103c:80d0 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 97ED13A8C0 |
| 10ec:522a | 103c:81ad | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 84C8A9779B |
| 10ec:522a | 103c:8251 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | C77AFE79C3 |
| 10ec:522a | 103c:8483 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 8B7A2D2A08 |
| 10ec:522a | 103c:8497 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 314C52C853 |
| 10ec:522a | 17aa:506c | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | DBA78E9C22 |
| 10ec:522a | 17aa:506d | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 0818236221 |
| 10ec:522a | 1854:0333 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 6D2724E820 |
| 10ec:525a | 1028:077a | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | 57D57D82FE |
| 10ec:525a | 103c:827f | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | 7E10A5E689 |
| 10ec:525a | 103c:83ba | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | 3743010FB5 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d3a | 103c:8486 | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | 7DEF867A41 |
| 8086:9d3a | 103c:8488 | Intel      | Sunrise Point-LP CSME HEC... | 4     | mei_me     | 2F6DFEC51C |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | mei_me     | E95114CACB |
| 8086:9d3a | 103c:80d1 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | FD3B38A3F5 |
| 8086:9d3a | 103c:830f | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | C4D6A7BC54 |
| 8086:9d3a | 103c:83b9 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | 831911B060 |
| 8086:9d3a | 17aa:3811 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | 5B8D494C04 |
| 8086:319a | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | mei_me     | 56A7BF3D18 |
| 8086:9d3a | 1028:07eb | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 7EB57A3809 |
| 8086:9d3a | 103c:827d | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | AE7D79F749 |
| 8086:9d3a | 103c:82c1 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | A9E42C34F6 |
| 8086:9d3a | 103c:8313 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 22FE75A663 |
| 8086:9d3a | 103c:83c4 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 65B956E887 |
| 8086:9d3a | 103c:84d8 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | A9BAF3BF1B |
| 8086:9d3a | 1043:1c90 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 7BBD1AB6FE |
| 8086:9d3a | 17aa:224e | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 3AC5B5C4AD |
| 8086:9d3a | 17aa:3805 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 941DF897AA |
| 8086:9d3a | 17aa:383e | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | AC774199A8 |
| 8086:9d3a | 17aa:3868 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 83192A2228 |
| 8086:9de0 | 103c:8514 | Intel      | Cannon Point-LP MEI Contr... | 2     | mei_me     | 74DD313167 |
| 8086:a13a | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 2     | mei_me     | 62AF0556D3 |
| 8086:5a9a | 17aa:3803 | Intel      | Celeron N3350/Pentium N42... | 1     | mei_me     | F8913A087C |
| 8086:5a9c | 17aa:3803 | Intel      | Communication controller     | 1     |            | F8913A087C |
| 8086:5a9e | 17aa:3803 | Intel      | Communication controller     | 1     |            | F8913A087C |
| 8086:9cba | 103c:802d | Intel      | Wildcat Point-LP MEI Cont... | 1     | mei_me     | D9CA1DBE13 |
| 8086:9cba | 103c:806c | Intel      | Wildcat Point-LP MEI Cont... | 1     | mei_me     | 462F2D5347 |
| 8086:9cba | 103c:806e | Intel      | Wildcat Point-LP MEI Cont... | 1     | mei_me     | 62A9EF950E |
| 8086:9d3a | 1028:077a | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 57D57D82FE |
| 8086:9d3a | 1028:07aa | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | BC69AFD822 |
| 8086:9d3a | 103c:80d0 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 97ED13A8C0 |
| 8086:9d3a | 103c:81a1 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | C894E5633B |
| 8086:9d3a | 103c:81ad | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 84C8A9779B |
| 8086:9d3a | 103c:8251 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | C77AFE79C3 |
| 8086:9d3a | 103c:827f | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 7E10A5E689 |
| 8086:9d3a | 103c:83ba | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 3743010FB5 |
| 8086:9d3a | 103c:8438 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 7F01433E42 |
| 8086:9d3a | 103c:8483 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 8B7A2D2A08 |
| 8086:9d3a | 103c:8487 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | C8C863DB3A |
| 8086:9d3a | 103c:8503 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | EC7FFC8F98 |
| 8086:9d3a | 1043:12e1 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 93A44B1518 |
| 8086:9d3a | 1043:14c0 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | FA7C5C4F64 |
| 8086:9d3a | 1043:14f0 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | F65847676C |
| 8086:9d3a | 1043:1c40 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 9565CCD6A2 |
| 8086:9d3a | 1043:1cf0 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 2C6BCC75CC |
| 8086:9d3a | 1043:1dc0 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 42FB487F36 |
| 8086:9d3a | 144d:c141 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 323C96D0DE |
| 8086:9d3a | 152d:1147 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 7DA5C4A4FA |
| 8086:9d3a | 17aa:3801 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | D838D80F49 |
| 8086:9d3a | 17aa:380d | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | A388F4B414 |
| 8086:9d3a | 17aa:3824 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | A295EE15E6 |
| 8086:9d3a | 17aa:383d | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | CE03C99485 |
| 8086:9d3a | 17aa:3861 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 67454C18A3 |
| 8086:9d3a | 17aa:504c | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 3C1A4327F5 |
| 8086:9d3a | 17aa:506c | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | DBA78E9C22 |
| 8086:9d3a | 17aa:506d | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 0818236221 |
| 8086:9d3a | 8086:9d3a | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | C3AA237F35 |
| 8086:9de0 | 1854:0333 | Intel      | Cannon Point-LP MEI Contr... | 1     | mei_me     | 6D2724E820 |
| 8086:a13a | 17aa:3809 | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | F445F1B326 |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 6     | mei_txe    | FAB48926D9 |
| 1022:15df | 17aa:3804 | AMD        | Family 17h (Models 10h-1f... | 3     |            | 52036BD95B |
| 1022:15df | 103c:8496 | AMD        | Family 17h (Models 10h-1f... | 2     |            | F720A735A8 |
| 1022:1578 | 103c:81aa | AMD        | Carrizo Platform Security... | 1     |            | D103A0F533 |
| 1022:1578 | 17aa:3802 | AMD        | Carrizo Platform Security... | 1     |            | B9FC5DC357 |
| 1022:15df | 103c:8497 | AMD        | Family 17h (Models 10h-1f... | 1     |            | 314C52C853 |
| 8086:0f18 | 103c:802b | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | 07B5ECDCCD |
| 8086:2298 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | BE4128010B |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 6     | i915       | FAB48926D9 |
| 8086:5917 | 103c:8486 | Intel      | UHD Graphics 620             | 5     | i915       | 7DEF867A41 |
| 8086:5917 | 103c:8488 | Intel      | UHD Graphics 620             | 4     | i915       | 2F6DFEC51C |
| 1002:15dd | 17aa:39ff | AMD        | Raven Ridge [Radeon Vega ... | 3     | amdgpu     | 52036BD95B |
| 8086:1916 | 103c:80d1 | Intel      | Skylake GT2 [HD Graphics ... | 3     | i915       | FD3B38A3F5 |
| 8086:5916 | 103c:830f | Intel      | HD Graphics 620              | 3     | i915       | C4D6A7BC54 |
| 8086:5917 | 103c:83b9 | Intel      | UHD Graphics 620             | 3     | i915       | 831911B060 |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics                  | 3     | i915       | E95114CACB |
| 1002:15dd | 103c:8496 | AMD        | Raven Ridge [Radeon Vega ... | 2     | amdgpu     | F720A735A8 |
| 1002:694e | 1028:080d | ATI Tec... | Polaris 22 XL [Radeon RX ... | 2     | amdgpu     | 62AF0556D3 |
| 10de:134d | 103c:82c1 | Nvidia     | GM108M [GeForce 940MX]       | 2     |            | A9E42C34F6 |
| 8086:1906 | 17aa:381d | Intel      | HD Graphics 510              | 2     | i915       | 4ACED2B19A |
| 8086:3ea0 | 103c:8514 | Intel      | UHD Graphics 620 (Whiskey... | 2     | i915       | 74DD313167 |
| 8086:5916 | 103c:827d | Intel      | HD Graphics 620              | 2     | i915       | AE7D79F749 |
| 8086:5916 | 103c:82c1 | Intel      | HD Graphics 620              | 2     | i915       | A9E42C34F6 |
| 8086:5916 | 103c:8313 | Intel      | HD Graphics 620              | 2     | i915       | 22FE75A663 |
| 8086:5916 | 17aa:224e | Intel      | HD Graphics 620              | 2     | i915       | 3AC5B5C4AD |
| 8086:5916 | 17aa:3801 | Intel      | HD Graphics 620              | 2     | i915       | 941DF897AA |
| 8086:5917 | 1028:07eb | Intel      | UHD Graphics 620             | 2     | i915       | 7EB57A3809 |
| 8086:5917 | 103c:83c4 | Intel      | UHD Graphics 620             | 2     | i915       | 65B956E887 |
| 8086:5917 | 103c:84d8 | Intel      | UHD Graphics 620             | 2     | i915       | A9BAF3BF1B |
| 8086:5917 | 1043:1c90 | Intel      | UHD Graphics 620             | 2     | i915       | 7BBD1AB6FE |
| 8086:5917 | 17aa:3803 | Intel      | UHD Graphics 620             | 2     | i915       | 83192A2228 |
| 8086:591b | 1028:080d | Intel      | HD Graphics 630              | 2     | i915       | 62AF0556D3 |
| 1002:15dd | 103c:8497 | AMD        | Raven Ridge [Radeon Vega ... | 1     | amdgpu     | 314C52C853 |
| 1002:6900 | 17aa:39bc | AMD        | Topaz XT [Radeon R7 M260/... | 1     | amdgpu     | A388F4B414 |
| 1002:9874 | 103c:81aa | AMD        | Wani [Radeon R5/R6/R7 Gra... | 1     | amdgpu     | D103A0F533 |
| 1002:98e4 | 17aa:3804 | AMD        | Stoney [Radeon R2/R3/R4/R... | 1     | amdgpu     | B9FC5DC357 |
| 10de:1346 | 103c:80d0 | Nvidia     | GM108M [GeForce 930M]        | 1     | nvidia     | 97ED13A8C0 |
| 10de:134d | 17aa:39ce | Nvidia     | GM108M [GeForce 940MX]       | 1     | nvidia     | 799D18044C |
| 10de:137a | 17aa:505a | Nvidia     | GM108GLM [Quadro K620M / ... | 1     | nvidia     | 3C1A4327F5 |
| 10de:174d | 103c:8487 | Nvidia     | GM108M [GeForce MX130]       | 1     | nouveau    | C8C863DB3A |
| 10de:174d | 103c:84d8 | Nvidia     | GM108M [GeForce MX130]       | 1     | nouveau    | 78EB27FFFA |
| 10de:1c8d | 17aa:39cb | Nvidia     | GP107M [GeForce GTX 1050 ... | 1     | nvidia     | F445F1B326 |
| 10de:1d10 | 103c:827f | Nvidia     | GP108M [GeForce MX150]       | 1     |            | 7E10A5E689 |
| 10de:1d10 | 103c:83ba | Nvidia     | GP108M [GeForce MX150]       | 1     |            | 3743010FB5 |
| 10de:1d12 | 1043:15ce | Nvidia     | GP108M [GeForce MX150]       | 1     | nvidia     | 864F436F16 |
| 8086:0f31 | 103c:802b | Intel      | Atom Processor Z36xxx/Z37... | 1     | i915       | 07B5ECDCCD |
| 8086:1616 | 103c:802d | Intel      | HD Graphics 5500             | 1     | i915       | D9CA1DBE13 |
| 8086:1616 | 103c:806c | Intel      | HD Graphics 5500             | 1     | i915       | 462F2D5347 |
| 8086:1616 | 103c:806e | Intel      | HD Graphics 5500             | 1     | i915       | 62A9EF950E |
| 8086:1916 | 103c:80d0 | Intel      | Skylake GT2 [HD Graphics ... | 1     | i915       | 97ED13A8C0 |
| 8086:1916 | 103c:81a1 | Intel      | Skylake GT2 [HD Graphics ... | 1     | i915       | C894E5633B |
| 8086:1916 | 144d:c141 | Intel      | Skylake GT2 [HD Graphics ... | 1     | i915       | 323C96D0DE |
| 8086:1916 | 17aa:505a | Intel      | Skylake GT2 [HD Graphics ... | 1     | i915       | 3C1A4327F5 |
| 8086:1921 | 17aa:39f2 | Intel      | HD Graphics 520              | 1     | i915       | 5B8D494C04 |
| 8086:22b1 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 1     | i915       | BE4128010B |
| 8086:3184 | 1e39:a001 | Intel      | UHD Graphics 605             | 1     | i915       | 56A7BF3D18 |
| 8086:3185 | 8086:2212 | Intel      | UHD Graphics 605             | 1     | i915       | 11EC0315D7 |
| 8086:3ea0 | 1854:0333 | Intel      | UHD Graphics 620 (Whiskey... | 1     | i915       | 6D2724E820 |
| 8086:5916 | 1028:07aa | Intel      | HD Graphics 620              | 1     | i915       | BC69AFD822 |
| 8086:5916 | 103c:81ad | Intel      | HD Graphics 620              | 1     | i915       | 84C8A9779B |
| 8086:5916 | 103c:8251 | Intel      | HD Graphics 620              | 1     | i915       | C77AFE79C3 |
| 8086:5916 | 1043:14c0 | Intel      | HD Graphics 620              | 1     | i915       | FA7C5C4F64 |
| 8086:5916 | 1043:14f0 | Intel      | HD Graphics 620              | 1     | i915       | F65847676C |
| 8086:5916 | 152d:1147 | Intel      | HD Graphics 620              | 1     | i915       | 7DA5C4A4FA |
| 8086:5916 | 17aa:3987 | Intel      | HD Graphics 620              | 1     | i915       | AC774199A8 |
| 8086:5916 | 17aa:3988 | Intel      | HD Graphics 620              | 1     | i915       | CE03C99485 |
| 8086:5916 | 17aa:39bc | Intel      | HD Graphics 620              | 1     | i915       | A388F4B414 |
| 8086:5916 | 17aa:39f3 | Intel      | HD Graphics 620              | 1     | i915       | A295EE15E6 |
| 8086:5916 | 8086:5916 | Intel      | HD Graphics 620              | 1     | i915       | C3AA237F35 |
| 8086:5917 | 103c:827f | Intel      | UHD Graphics 620             | 1     | i915       | 7E10A5E689 |
| 8086:5917 | 103c:83ba | Intel      | UHD Graphics 620             | 1     | i915       | 3743010FB5 |
| 8086:5917 | 103c:8438 | Intel      | UHD Graphics 620             | 1     | i915       | 7F01433E42 |
| 8086:5917 | 103c:8483 | Intel      | UHD Graphics 620             | 1     | i915       | 8B7A2D2A08 |
| 8086:5917 | 103c:8487 | Intel      | UHD Graphics 620             | 1     | i915       | C8C863DB3A |
| 8086:5917 | 1043:12e1 | Intel      | UHD Graphics 620             | 1     | i915       | 93A44B1518 |
| 8086:5917 | 1043:1c40 | Intel      | UHD Graphics 620             | 1     | i915       | 9565CCD6A2 |
| 8086:5917 | 1043:1dc0 | Intel      | UHD Graphics 620             | 1     | i915       | 42FB487F36 |
| 8086:5917 | 17aa:398e | Intel      | UHD Graphics 620             | 1     | i915       | D838D80F49 |
| 8086:5917 | 17aa:39ce | Intel      | UHD Graphics 620             | 1     | i915       | 799D18044C |
| 8086:5917 | 17aa:39ef | Intel      | UHD Graphics 620             | 1     | i915       | 67454C18A3 |
| 8086:5917 | 17aa:506c | Intel      | UHD Graphics 620             | 1     | i915       | DBA78E9C22 |
| 8086:5917 | 17aa:506d | Intel      | UHD Graphics 620             | 1     | i915       | 0818236221 |
| 8086:591b | 17aa:39cb | Intel      | HD Graphics 630              | 1     | i915       | F445F1B326 |
| 8086:591c | 103c:8503 | Intel      | UHD Graphics 615             | 1     | i915       | EC7FFC8F98 |
| 8086:591e | 1028:077a | Intel      | HD Graphics 615              | 1     | i915       | 57D57D82FE |
| 8086:591e | 1043:1cf0 | Intel      | HD Graphics 615              | 1     | i915       | 2C6BCC75CC |
| 8086:591e | 1ae0:2212 | Intel      | HD Graphics 615              | 1     | i915       | 5EA0111CED |
| 8086:5a85 | 17aa:39fb | Intel      | HD Graphics                  | 1     | i915       | F8913A087C |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15d1 | 17aa:3809 | AMD        | Raven/Raven2 IOMMU           | 3     |            | 52036BD95B |
| 1022:15d1 | 103c:8496 | AMD        | Raven/Raven2 IOMMU           | 2     |            | F720A735A8 |
| 1022:1577 | 103c:81aa | AMD        | Family 15h (Models 60h-6f... | 1     |            | D103A0F533 |
| 1022:1577 | 17aa:3806 | AMD        | Family 15h (Models 60h-6f... | 1     |            | B9FC5DC357 |
| 1022:15d1 | 103c:8497 | AMD        | Raven/Raven2 IOMMU           | 1     |            | 314C52C853 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d21 | 103c:8486 | Intel      | Sunrise Point-LP PMC         | 5     |            | 7DEF867A41 |
| 8086:9d21 | 103c:8488 | Intel      | Sunrise Point-LP PMC         | 4     |            | 2F6DFEC51C |
| 8086:9d21 | 103c:80d1 | Intel      | Sunrise Point-LP PMC         | 3     |            | FD3B38A3F5 |
| 8086:9d21 | 103c:830f | Intel      | Sunrise Point-LP PMC         | 3     |            | C4D6A7BC54 |
| 8086:9d21 | 103c:83b9 | Intel      | Sunrise Point-LP PMC         | 3     |            | 831911B060 |
| 8086:9d21 | 17aa:3811 | Intel      | Sunrise Point-LP PMC         | 3     |            | 5B8D494C04 |
| 8086:9d21 | 1028:07eb | Intel      | Sunrise Point-LP PMC         | 2     |            | 7EB57A3809 |
| 8086:9d21 | 103c:827d | Intel      | Sunrise Point-LP PMC         | 2     |            | AE7D79F749 |
| 8086:9d21 | 103c:82c1 | Intel      | Sunrise Point-LP PMC         | 2     |            | A9E42C34F6 |
| 8086:9d21 | 103c:8313 | Intel      | Sunrise Point-LP PMC         | 2     |            | 22FE75A663 |
| 8086:9d21 | 103c:83c4 | Intel      | Sunrise Point-LP PMC         | 2     |            | 65B956E887 |
| 8086:9d21 | 103c:84d8 | Intel      | Sunrise Point-LP PMC         | 2     |            | A9BAF3BF1B |
| 8086:9d21 | 1043:1c90 | Intel      | Sunrise Point-LP PMC         | 2     |            | 7BBD1AB6FE |
| 8086:9d21 | 17aa:224e | Intel      | Sunrise Point-LP PMC         | 2     | intel_p... | 3AC5B5C4AD |
| 8086:9d21 | 17aa:3805 | Intel      | Sunrise Point-LP PMC         | 2     |            | 941DF897AA |
| 8086:9d21 | 17aa:383d | Intel      | Sunrise Point-LP PMC         | 2     |            | AC774199A8 |
| 8086:9d21 | 17aa:386c | Intel      | Sunrise Point-LP PMC         | 2     |            | 83192A2228 |
| 8086:9def | 103c:8514 | Intel      | Cannon Point-LP Shared SRAM  | 2     |            | 74DD313167 |
| 8086:a121 | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 2     |            | 62AF0556D3 |
| 8086:9d21 | 1028:077a | Intel      | Sunrise Point-LP PMC         | 1     |            | 57D57D82FE |
| 8086:9d21 | 1028:07aa | Intel      | Sunrise Point-LP PMC         | 1     |            | BC69AFD822 |
| 8086:9d21 | 103c:80d0 | Intel      | Sunrise Point-LP PMC         | 1     |            | 97ED13A8C0 |
| 8086:9d21 | 103c:81a1 | Intel      | Sunrise Point-LP PMC         | 1     |            | C894E5633B |
| 8086:9d21 | 103c:81ad | Intel      | Sunrise Point-LP PMC         | 1     |            | 84C8A9779B |
| 8086:9d21 | 103c:8251 | Intel      | Sunrise Point-LP PMC         | 1     |            | C77AFE79C3 |
| 8086:9d21 | 103c:827f | Intel      | Sunrise Point-LP PMC         | 1     |            | 7E10A5E689 |
| 8086:9d21 | 103c:83ba | Intel      | Sunrise Point-LP PMC         | 1     |            | 3743010FB5 |
| 8086:9d21 | 103c:8438 | Intel      | Sunrise Point-LP PMC         | 1     |            | 7F01433E42 |
| 8086:9d21 | 103c:8483 | Intel      | Sunrise Point-LP PMC         | 1     |            | 8B7A2D2A08 |
| 8086:9d21 | 103c:8487 | Intel      | Sunrise Point-LP PMC         | 1     |            | C8C863DB3A |
| 8086:9d21 | 103c:8503 | Intel      | Sunrise Point-LP PMC         | 1     |            | EC7FFC8F98 |
| 8086:9d21 | 1043:12e1 | Intel      | Sunrise Point-LP PMC         | 1     |            | 93A44B1518 |
| 8086:9d21 | 1043:14c0 | Intel      | Sunrise Point-LP PMC         | 1     |            | FA7C5C4F64 |
| 8086:9d21 | 1043:14f0 | Intel      | Sunrise Point-LP PMC         | 1     |            | F65847676C |
| 8086:9d21 | 1043:1c40 | Intel      | Sunrise Point-LP PMC         | 1     |            | 9565CCD6A2 |
| 8086:9d21 | 1043:1cf0 | Intel      | Sunrise Point-LP PMC         | 1     |            | 2C6BCC75CC |
| 8086:9d21 | 1043:1dc0 | Intel      | Sunrise Point-LP PMC         | 1     |            | 42FB487F36 |
| 8086:9d21 | 144d:c141 | Intel      | Sunrise Point-LP PMC         | 1     |            | 323C96D0DE |
| 8086:9d21 | 152d:1147 | Intel      | Sunrise Point-LP PMC         | 1     |            | 7DA5C4A4FA |
| 8086:9d21 | 17aa:380b | Intel      | Sunrise Point-LP PMC         | 1     |            | A388F4B414 |
| 8086:9d21 | 17aa:3823 | Intel      | Sunrise Point-LP PMC         | 1     |            | A295EE15E6 |
| 8086:9d21 | 17aa:383f | Intel      | Sunrise Point-LP PMC         | 1     |            | CE03C99485 |
| 8086:9d21 | 17aa:3864 | Intel      | Sunrise Point-LP PMC         | 1     |            | 67454C18A3 |
| 8086:9d21 | 17aa:3866 | Intel      | Sunrise Point-LP PMC         | 1     |            | D838D80F49 |
| 8086:9d21 | 17aa:504c | Intel      | Sunrise Point-LP PMC         | 1     |            | 3C1A4327F5 |
| 8086:9d21 | 17aa:506c | Intel      | Sunrise Point-LP PMC         | 1     |            | DBA78E9C22 |
| 8086:9d21 | 17aa:506d | Intel      | Sunrise Point-LP PMC         | 1     |            | 0818236221 |
| 8086:9d21 | 1ae0:006b | Intel      | Sunrise Point-LP PMC         | 1     |            | 5EA0111CED |
| 8086:9d21 | 8086:9d21 | Intel      | Sunrise Point-LP PMC         | 1     |            | C3AA237F35 |
| 8086:9def | 1854:0333 | Intel      | Cannon Point-LP Shared SRAM  | 1     |            | 6D2724E820 |
| 8086:a121 | 17aa:380f | Intel      | 100 Series/C230 Series Ch... | 1     |            | F445F1B326 |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 6     | intel_a... | FAB48926D9 |
| 1022:15e2 | 103c:8496 | AMD        | Raven/Raven2/FireFlight/R... | 2     | snd_pci... | F720A735A8 |
| 1022:15e2 | 17aa:380b | AMD        | Raven/Raven2/FireFlight/R... | 2     |            | 52036BD95B |
| 8086:5a88 |           | Intel      | Celeron N3350/Pentium N42... | 1     |            | 6663E08482 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8136 | 103c:80d1 | Realtek... | RTL810xE PCI Express Fast... | 3     | r8169      | FD3B38A3F5 |
| 10ec:8168 | 17aa:3850 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 5B8D494C04 |
| 10ec:8168 | 103c:84d8 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | A9BAF3BF1B |
| 8086:15d8 | 17aa:224e | Intel      | Ethernet Connection (4) I... | 2     | e1000e     | 3AC5B5C4AD |
| 10ec:8136 | 103c:802b | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | 07B5ECDCCD |
| 10ec:8136 | 103c:806e | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | 62A9EF950E |
| 10ec:8168 | 103c:806c | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 462F2D5347 |
| 10ec:8168 | 103c:80d0 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 97ED13A8C0 |
| 10ec:8168 | 103c:8251 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | C77AFE79C3 |
| 10ec:8168 | 17aa:383f | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | F8913A087C |
| 10ec:8168 | 17aa:3848 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | A388F4B414 |
| 10ec:8168 | 17aa:3868 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | B9FC5DC357 |
| 14e4:1682 | 14e4:1682 | Broadco... | NetXtreme BCM57762 Gigabi... | 1     | tg3        | A462F23545 |
| 8086:156f | 17aa:504c | Intel      | Ethernet Connection I219-LM  | 1     | e1000e     | 3C1A4327F5 |
| 8086:15d7 | 17aa:506d | Intel      | Ethernet Connection (4) I... | 1     | e1000e     | 0818236221 |
| 8086:15d8 | 17aa:506c | Intel      | Ethernet Connection (4) I... | 1     | e1000e     | DBA78E9C22 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 11    | iwlwifi    | 65B956E887 |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 8     | 8821ce     | 2F6DFEC51C |
| 10ec:b822 | 103c:831b | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 6     | r8822be    | 314C52C853 |
| 8086:24fd | 8086:9010 | Intel      | Wireless 8265 / 8275         | 5     | iwlwifi    | 7F01433E42 |
| 168c:003e | 17aa:0827 | Qualcom... | QCA6174 802.11ac Wireless... | 4     | ath10k_pci | 941DF897AA |
| 168c:0042 | 17aa:4035 | Qualcom... | QCA9377 802.11ac Wireless... | 4     | ath10k_pci | 5B8D494C04 |
| 8086:24fd | 8086:8010 | Intel      | Wireless 8265 / 8275         | 4     | iwlwifi    | 7BBD1AB6FE |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 4     | iwlwifi    | 52036BD95B |
| 168c:0042 | 17aa:0901 | Qualcom... | QCA9377 802.11ac Wireless... | 3     | ath10k_pci | F8913A087C |
| 8086:2526 | 8086:0014 | Intel      | Wireless-AC 9260             | 3     | iwlwifi    | 83192A2228 |
| 8086:9df0 | 8086:0034 | Intel      | Cannon Point-LP CNVi [Wir... | 3     | iwlwifi    | 74DD313167 |
| 10ec:b723 | 103c:804c | Realtek... | RTL8723BE PCIe Wireless N... | 2     | rtl8723be  | 2DE25CD685 |
| 10ec:b822 | 17aa:b023 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 2     | r8822be    | 67454C18A3 |
| 168c:003e | 1a56:143a | Qualcom... | QCA6174 802.11ac Wireless... | 2     | ath10k_pci | 62AF0556D3 |
| 8086:095a | 8086:5410 | Intel      | Wireless 7265                | 2     | iwlwifi    | 7EB57A3809 |
| 8086:24f3 | 8086:0110 | Intel      | Wireless 8260                | 2     | iwlwifi    | F65847676C |
| 8086:24f3 | 8086:9010 | Intel      | Wireless 8260                | 2     | iwlwifi    | 323C96D0DE |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 2     | iwlwifi    | DBA78E9C22 |
| 8086:24fd | 8086:1130 | Intel      | Wireless 8265 / 8275         | 2     | iwlwifi    | 3AC5B5C4AD |
| 8086:3165 | 8086:8010 | Intel      | Wireless 3165                | 2     | iwlwifi    | 6663E08482 |
| 8086:3165 | 8086:8110 | Intel      | Wireless 3165                | 2     | iwlwifi    | E95114CACB |
| 8086:31dc | 8086:02a4 | Intel      | Wireless-AC 1550i Wireles... | 2     | iwlwifi    | 56A7BF3D18 |
| 10ec:b822 | 17aa:b024 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 1     | r8822be    | BC69AFD822 |
| 10ec:b822 | 1a3b:2950 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 1     |            | 9565CCD6A2 |
| 14e4:4365 | 103c:2230 | Broadco... | BCM43142 802.11b/g/n         | 1     | wl         | 07B5ECDCCD |
| 14e4:43ba | 1028:0020 | Broadco... | BCM43602 802.11ac Wireles... | 1     | brcmfmac   | C77AFE79C3 |
| 168c:0042 | 1a3b:2231 | Qualcom... | QCA9377 802.11ac Wireless... | 1     | ath10k_pci | 2C6BCC75CC |
| 8086:095a | 8086:9e10 | Intel      | Wireless 7265                | 1     | iwlwifi    | 5EA0111CED |
| 8086:24f3 | 8086:0130 | Intel      | Wireless 8260                | 1     | iwlwifi    | 3C1A4327F5 |
| 8086:24f3 | 8086:1130 | Intel      | Wireless 8260                | 1     | iwlwifi    | A295EE15E6 |
| 8086:24f3 | 8086:8010 | Intel      | Wireless 8260                | 1     | iwlwifi    | 42FB487F36 |
| 8086:24fd | 8086:0110 | Intel      | Wireless 8265 / 8275         | 1     | iwlwifi    | 93A44B1518 |
| 8086:24fd | 8086:8050 | Intel      | Wireless 8265 / 8275         | 1     | iwlwifi    | 57D57D82FE |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 1     | iwlwifi    | AC774199A8 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 7     | iwlwifi    | 7E10A5E689 |
| 10ec:d723 | 103c:8319 | Realtek... | RTL8723DE Wireless Networ... | 3     | rtl8723de  | C4D6A7BC54 |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d26 |           | Intel      | Skylake-U/Y Northpeak        | 4     | intel_t... | 97ED13A8C0 |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d35 | 103c:8486 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 7DEF867A41 |
| 8086:9d35 | 8086:9d35 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | C3AA237F35 |
| 8086:9d35 | 103c:8488 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 2F6DFEC51C |
| 1022:15e6 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Non-S... | 3     | i2c_amd... | 52036BD95B |
| 8086:9d35 | 103c:830f | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | C4D6A7BC54 |
| 8086:9d35 | 103c:83b9 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 831911B060 |
| 1022:15e4 | 103c:8496 | AMD        | Raven/Raven2/Renoir Senso... | 2     |            | F720A735A8 |
| 8086:9d35 | 1028:07eb | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 7EB57A3809 |
| 8086:9d35 | 103c:827d | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | AE7D79F749 |
| 8086:9d35 | 103c:82c1 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | A9E42C34F6 |
| 8086:9d35 | 103c:8313 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 22FE75A663 |
| 8086:9d35 | 103c:83c4 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 65B956E887 |
| 8086:9d35 | 103c:84d8 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | A9BAF3BF1B |
| 8086:9d35 | 1043:1c90 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 7BBD1AB6FE |
| 8086:9d35 | 17aa:224e | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 3AC5B5C4AD |
| 8086:a135 | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 2     | intel_i... | 62AF0556D3 |
| 1022:15e4 | 103c:8497 | AMD        | Raven/Raven2/Renoir Senso... | 1     |            | 314C52C853 |
| 8086:9d24 |           | Intel      | Skylake-U/Y SPI Controller   | 1     |            | 5EA0111CED |
| 8086:9d35 | 1028:077a | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 57D57D82FE |
| 8086:9d35 | 1028:07aa | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | BC69AFD822 |
| 8086:9d35 | 103c:81a1 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | C894E5633B |
| 8086:9d35 | 103c:81ad | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 84C8A9779B |
| 8086:9d35 | 103c:8251 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | C77AFE79C3 |
| 8086:9d35 | 103c:827f | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 7E10A5E689 |
| 8086:9d35 | 103c:83ba | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 3743010FB5 |
| 8086:9d35 | 103c:8438 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 7F01433E42 |
| 8086:9d35 | 103c:8483 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 8B7A2D2A08 |
| 8086:9d35 | 103c:8487 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | C8C863DB3A |
| 8086:9d35 | 103c:8503 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | EC7FFC8F98 |
| 8086:9d35 | 1043:1c40 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 9565CCD6A2 |
| 8086:9d35 | 144d:c141 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 323C96D0DE |
| 8086:9d35 | 152d:1147 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 7DA5C4A4FA |
| 8086:9d35 | 17aa:380d | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | D838D80F49 |
| 8086:9d35 | 17aa:504c | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 3C1A4327F5 |
| 8086:9d35 | 17aa:506c | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | DBA78E9C22 |
| 8086:9d35 | 17aa:506d | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 0818236221 |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d2d | 103c:8486 | Intel      | Sunrise Point-LP Secure D... | 5     | sdhci_pci  | 7DEF867A41 |
| 8086:9d2b | 103c:8488 | Intel      | Skylake-U/Y SCC: eMMC        | 4     | sdhci_pci  | 2F6DFEC51C |
| 8086:9d2d | 103c:8488 | Intel      | Sunrise Point-LP Secure D... | 4     | sdhci_pci  | 2F6DFEC51C |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | sdhci_pci  | E95114CACB |
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | sdhci_pci  | 56A7BF3D18 |
| 8086:31d0 | 8086:7270 | Intel      | SD Host Controller           | 2     | sdhci_pci  | 56A7BF3D18 |
| 8086:9d2d | 103c:84d8 | Intel      | Sunrise Point-LP Secure D... | 2     | sdhci_pci  | A9BAF3BF1B |
| 1217:8520 | 17aa:504c | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 3C1A4327F5 |
| 8086:5aca | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | F8913A087C |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 6663E08482 |
| 8086:5acc | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | F8913A087C |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 6663E08482 |
| 8086:9d2b | 1ae0:006b | Intel      | Skylake-U/Y SCC: eMMC        | 1     | sdhci_pci  | 5EA0111CED |
| 8086:9d2b | 8086:9d2b | Intel      | Skylake-U/Y SCC: eMMC        | 1     | sdhci_pci  | 2C6BCC75CC |
| 8086:9d2d | 103c:8487 | Intel      | Sunrise Point-LP Secure D... | 1     | sdhci_pci  | C8C863DB3A |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:5ac8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | pwm_lpss   | 6663E08482 |
| 8086:9da4 | 103c:8514 | Intel      | Cannon Point-LP SPI Contr... | 2     |            | 74DD313167 |
| 8086:9de8 | 103c:8514 | Intel      | Cannon Point-LP Serial IO... | 2     | intel_lpss | 74DD313167 |
| 8086:9de9 | 103c:8514 | Intel      | Cannon Point-LP Serial IO... | 2     | intel_lpss | 74DD313167 |
| 8086:9da4 | 1854:0333 | Intel      | Cannon Point-LP SPI Contr... | 1     |            | 6D2724E820 |
| 8086:9de8 | 1854:0333 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_lpss | 6D2724E820 |
| 8086:9de9 | 1854:0333 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_lpss | 6D2724E820 |
| 8086:9dea | 1854:0333 | Intel      | 8th Gen Intel Core Proces... | 1     | intel_lpss | 6D2724E820 |
| 8086:9deb | 1854:0333 | Intel      | 8th Gen Intel Core Proces... | 1     | intel_lpss | 6D2724E820 |
| 8086:9dfb | 8086:7270 | Intel      | 300 Series Chipset LPSS: ... | 1     | intel_lpss | 6D2724E820 |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d3d | 103c:827d | Intel      | Sunrise Point-LP Active M... | 2     | serial     | AE7D79F749 |
| 8086:9dfc | 103c:8514 | Intel      | Cannon Point-LP Integrate... | 2     | intel_i... | 74DD313167 |
| 8086:9d3d | 1028:07aa | Intel      | Sunrise Point-LP Active M... | 1     | serial     | BC69AFD822 |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 6     | process... | FAB48926D9 |
| 8086:1903 | 103c:8486 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 5     | process... | 7DEF867A41 |
| 8086:9d27 | 103c:8486 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 7DEF867A41 |
| 8086:9d31 | 103c:8486 | Intel      | Sunrise Point-LP Thermal ... | 5     | intel_p... | 7DEF867A41 |
| 8086:9d60 | 103c:8486 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 7DEF867A41 |
| 8086:9d61 | 103c:8486 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 7DEF867A41 |
| 8086:9d62 | 103c:8486 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 7DEF867A41 |
| 8086:1903 | 103c:8488 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 4     | process... | 2F6DFEC51C |
| 8086:9d27 | 103c:8488 | Intel      | Sunrise Point-LP Serial I... | 4     | intel_l... | 2F6DFEC51C |
| 8086:9d31 | 103c:8488 | Intel      | Sunrise Point-LP Thermal ... | 4     | intel_p... | 2F6DFEC51C |
| 8086:9d60 | 103c:8488 | Intel      | Sunrise Point-LP Serial I... | 4     | intel_l... | 2F6DFEC51C |
| 8086:9d61 | 103c:8488 | Intel      | Sunrise Point-LP Serial I... | 4     | intel_l... | 2F6DFEC51C |
| 8086:1903 | 103c:80d1 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | process... | FD3B38A3F5 |
| 8086:1903 | 103c:830f | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | process... | C4D6A7BC54 |
| 8086:1903 | 103c:83b9 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | proc_th... | 831911B060 |
| 8086:5a8c |           | Intel      | Dynamic Platform and Ther... | 3     | process... | E95114CACB |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | E95114CACB |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | E95114CACB |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | E95114CACB |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | E95114CACB |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | E95114CACB |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | E95114CACB |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | E95114CACB |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | E95114CACB |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | E95114CACB |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | E95114CACB |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | E95114CACB |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | E95114CACB |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | E95114CACB |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | E95114CACB |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | E95114CACB |
| 8086:9d27 |           | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 7BBD1AB6FE |
| 8086:9d27 | 103c:83b9 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_lpss | 831911B060 |
| 8086:9d29 |           | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 7BBD1AB6FE |
| 8086:9d29 | 103c:83b9 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_lpss | 831911B060 |
| 8086:9d31 | 103c:80d1 | Intel      | Sunrise Point-LP Thermal ... | 3     | intel_p... | FD3B38A3F5 |
| 8086:9d31 | 103c:830f | Intel      | Sunrise Point-LP Thermal ... | 3     | intel_p... | C4D6A7BC54 |
| 8086:9d31 | 103c:83b9 | Intel      | Sunrise Point-LP Thermal ... | 3     | intel_p... | 831911B060 |
| 8086:9d31 | 17aa:380b | Intel      | Sunrise Point-LP Thermal ... | 3     | intel_p... | 5B8D494C04 |
| 8086:9d60 | 103c:80d1 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | FD3B38A3F5 |
| 8086:9d60 | 103c:830f | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | C4D6A7BC54 |
| 8086:9d60 | 103c:83b9 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_lpss | 831911B060 |
| 8086:9d60 | 17aa:3811 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 5B8D494C04 |
| 8086:9d61 | 103c:80d1 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | FD3B38A3F5 |
| 8086:9d61 | 103c:830f | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | C4D6A7BC54 |
| 8086:9d61 | 17aa:3811 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 5B8D494C04 |
| 8086:1903 | 1028:07eb | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | process... | 7EB57A3809 |
| 8086:1903 | 1028:080d | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | process... | 62AF0556D3 |
| 8086:1903 | 103c:827d | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | proc_th... | AE7D79F749 |
| 8086:1903 | 103c:82c1 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | process... | A9E42C34F6 |
| 8086:1903 | 103c:8313 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | proc_th... | 22FE75A663 |
| 8086:1903 | 103c:83c4 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | process... | 65B956E887 |
| 8086:1903 | 103c:84d8 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | proc_th... | A9BAF3BF1B |
| 8086:1903 | 103c:8514 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | proc_th... | 74DD313167 |
| 8086:1903 | 1043:1c90 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | process... | 7BBD1AB6FE |
| 8086:1903 | 17aa:3801 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | proc_th... | 941DF897AA |
| 8086:1903 | 17aa:381c | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | process... | 83192A2228 |
| 8086:318c | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | process... | 56A7BF3D18 |
| 8086:31ac | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_l... | 56A7BF3D18 |
| 8086:31ae | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_l... | 56A7BF3D18 |
| 8086:31b0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_l... | 56A7BF3D18 |
| 8086:31b2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_l... | 56A7BF3D18 |
| 8086:31b4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_l... | 56A7BF3D18 |
| 8086:31b6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_l... | 56A7BF3D18 |
| 8086:31b8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_l... | 56A7BF3D18 |
| 8086:31ba | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_l... | 56A7BF3D18 |
| 8086:31bc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_l... | 56A7BF3D18 |
| 8086:31be | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_l... | 56A7BF3D18 |
| 8086:31c0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_l... | 56A7BF3D18 |
| 8086:31c2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_l... | 56A7BF3D18 |
| 8086:31c4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_l... | 56A7BF3D18 |
| 8086:31c6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_l... | 56A7BF3D18 |
| 8086:31ee | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_l... | 56A7BF3D18 |
| 8086:9d27 | 103c:84d8 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_lpss | A9BAF3BF1B |
| 8086:9d31 | 1028:07eb | Intel      | Sunrise Point-LP Thermal ... | 2     | intel_p... | 7EB57A3809 |
| 8086:9d31 | 103c:827d | Intel      | Sunrise Point-LP Thermal ... | 2     | intel_p... | AE7D79F749 |
| 8086:9d31 | 103c:82c1 | Intel      | Sunrise Point-LP Thermal ... | 2     | intel_p... | A9E42C34F6 |
| 8086:9d31 | 103c:8313 | Intel      | Sunrise Point-LP Thermal ... | 2     | intel_p... | 22FE75A663 |
| 8086:9d31 | 103c:83c4 | Intel      | Sunrise Point-LP Thermal ... | 2     | intel_p... | 65B956E887 |
| 8086:9d31 | 103c:84d8 | Intel      | Sunrise Point-LP Thermal ... | 2     | intel_p... | A9BAF3BF1B |
| 8086:9d31 | 1043:1c90 | Intel      | Sunrise Point-LP Thermal ... | 2     | intel_p... | 7BBD1AB6FE |
| 8086:9d31 | 17aa:224e | Intel      | Sunrise Point-LP Thermal ... | 2     | intel_p... | 3AC5B5C4AD |
| 8086:9d31 | 17aa:3804 | Intel      | Sunrise Point-LP Thermal ... | 2     | intel_p... | 941DF897AA |
| 8086:9d31 | 17aa:3830 | Intel      | Sunrise Point-LP Thermal ... | 2     | intel_p... | AC774199A8 |
| 8086:9d31 | 17aa:385a | Intel      | Sunrise Point-LP Thermal ... | 2     | intel_p... | 83192A2228 |
| 8086:9d60 | 1028:07eb | Intel      | Sunrise Point-LP Serial I... | 2     | intel_l... | 7EB57A3809 |
| 8086:9d60 | 103c:827d | Intel      | Sunrise Point-LP Serial I... | 2     | intel_lpss | AE7D79F749 |
| 8086:9d60 | 103c:82c1 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_l... | A9E42C34F6 |
| 8086:9d60 | 103c:8313 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_lpss | 22FE75A663 |
| 8086:9d60 | 103c:83c4 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_l... | 65B956E887 |
| 8086:9d60 | 103c:84d8 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_lpss | A9BAF3BF1B |
| 8086:9d60 | 1043:1c90 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_l... | 7BBD1AB6FE |
| 8086:9d60 | 17aa:3805 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_lpss | 941DF897AA |
| 8086:9d60 | 17aa:3837 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_l... | AC774199A8 |
| 8086:9d60 | 17aa:385f | Intel      | Sunrise Point-LP Serial I... | 2     | intel_l... | 83192A2228 |
| 8086:9d61 | 1028:07eb | Intel      | Sunrise Point-LP Serial I... | 2     | intel_l... | 7EB57A3809 |
| 8086:9d61 | 103c:827d | Intel      | Sunrise Point-LP Serial I... | 2     | intel_lpss | AE7D79F749 |
| 8086:9d61 | 103c:8313 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_lpss | 22FE75A663 |
| 8086:9d61 | 103c:83c4 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_l... | 65B956E887 |
| 8086:9d61 | 103c:84d8 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_lpss | A9BAF3BF1B |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d23 | 103c:8486 | Intel      | Sunrise Point-LP SMBus       | 5     | i2c_i801   | 7DEF867A41 |
| 8086:9d23 | 103c:8488 | Intel      | Sunrise Point-LP SMBus       | 4     | i2c_i801   | 2F6DFEC51C |
| 1022:790b | 17aa:3818 | AMD        | FCH SMBus Controller         | 3     | i2c_piix4  | 52036BD95B |
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | i801_smbus | E95114CACB |
| 8086:9d23 | 103c:80d1 | Intel      | Sunrise Point-LP SMBus       | 3     | i2c_i801   | FD3B38A3F5 |
| 8086:9d23 | 103c:830f | Intel      | Sunrise Point-LP SMBus       | 3     |            | C4D6A7BC54 |
| 8086:9d23 | 103c:83b9 | Intel      | Sunrise Point-LP SMBus       | 3     | i2c_i801   | 831911B060 |
| 8086:9d23 | 17aa:3811 | Intel      | Sunrise Point-LP SMBus       | 3     | i2c_i801   | 5B8D494C04 |
| 1022:790b | 103c:8496 | AMD        | FCH SMBus Controller         | 2     | i2c_piix4  | F720A735A8 |
| 8086:31d4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | i2c_i801   | 56A7BF3D18 |
| 8086:9d23 | 1028:07eb | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | 7EB57A3809 |
| 8086:9d23 | 103c:827d | Intel      | Sunrise Point-LP SMBus       | 2     | i801_smbus | AE7D79F749 |
| 8086:9d23 | 103c:82c1 | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | A9E42C34F6 |
| 8086:9d23 | 103c:8313 | Intel      | Sunrise Point-LP SMBus       | 2     | i801_smbus | 22FE75A663 |
| 8086:9d23 | 103c:83c4 | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | 65B956E887 |
| 8086:9d23 | 103c:84d8 | Intel      | Sunrise Point-LP SMBus       | 2     | i801_smbus | A9BAF3BF1B |
| 8086:9d23 | 1043:1c90 | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | 7BBD1AB6FE |
| 8086:9d23 | 17aa:224e | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | 3AC5B5C4AD |
| 8086:9d23 | 17aa:3805 | Intel      | Sunrise Point-LP SMBus       | 2     | i801_smbus | 941DF897AA |
| 8086:9d23 | 17aa:3840 | Intel      | Sunrise Point-LP SMBus       | 2     |            | AC774199A8 |
| 8086:9d23 | 17aa:3867 | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | 83192A2228 |
| 8086:9da3 | 103c:8514 | Intel      | Cannon Point-LP SMBus Con... | 2     | i801_smbus | 74DD313167 |
| 8086:a123 | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 2     |            | 62AF0556D3 |
| 1022:790b | 103c:81aa | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | D103A0F533 |
| 1022:790b | 103c:8497 | AMD        | FCH SMBus Controller         | 1     | piix4_s... | 314C52C853 |
| 1022:790b | 17aa:3802 | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | B9FC5DC357 |
| 8086:0f12 | 103c:802b | Intel      | Atom Processor E3800 Seri... | 1     | i2c_i801   | 07B5ECDCCD |
| 8086:2292 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 1     | i2c_i801   | BE4128010B |
| 8086:5ad4 | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 1     |            | F8913A087C |
| 8086:9ca2 | 103c:802d | Intel      | Wildcat Point-LP SMBus Co... | 1     | i2c_i801   | D9CA1DBE13 |
| 8086:9ca2 | 103c:806c | Intel      | Wildcat Point-LP SMBus Co... | 1     |            | 462F2D5347 |
| 8086:9ca2 | 103c:806e | Intel      | Wildcat Point-LP SMBus Co... | 1     | i2c_i801   | 62A9EF950E |
| 8086:9d23 | 1028:077a | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | 57D57D82FE |
| 8086:9d23 | 1028:07aa | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | BC69AFD822 |
| 8086:9d23 | 103c:80d0 | Intel      | Sunrise Point-LP SMBus       | 1     | i801_smbus | 97ED13A8C0 |
| 8086:9d23 | 103c:81a1 | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | C894E5633B |
| 8086:9d23 | 103c:81ad | Intel      | Sunrise Point-LP SMBus       | 1     |            | 84C8A9779B |
| 8086:9d23 | 103c:8251 | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | C77AFE79C3 |
| 8086:9d23 | 103c:827f | Intel      | Sunrise Point-LP SMBus       | 1     | i801_smbus | 7E10A5E689 |
| 8086:9d23 | 103c:83ba | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | 3743010FB5 |
| 8086:9d23 | 103c:8438 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 7F01433E42 |
| 8086:9d23 | 103c:8483 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 8B7A2D2A08 |
| 8086:9d23 | 103c:8487 | Intel      | Sunrise Point-LP SMBus       | 1     |            | C8C863DB3A |
| 8086:9d23 | 103c:8503 | Intel      | Sunrise Point-LP SMBus       | 1     |            | EC7FFC8F98 |
| 8086:9d23 | 1043:12e1 | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | 93A44B1518 |
| 8086:9d23 | 1043:14c0 | Intel      | Sunrise Point-LP SMBus       | 1     |            | FA7C5C4F64 |
| 8086:9d23 | 1043:14f0 | Intel      | Sunrise Point-LP SMBus       | 1     | i801_smbus | F65847676C |
| 8086:9d23 | 1043:1c40 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 9565CCD6A2 |
| 8086:9d23 | 1043:1cf0 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 2C6BCC75CC |
| 8086:9d23 | 1043:1dc0 | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | 42FB487F36 |
| 8086:9d23 | 144d:c141 | Intel      | Sunrise Point-LP SMBus       | 1     | i801_smbus | 323C96D0DE |
| 8086:9d23 | 152d:1147 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 7DA5C4A4FA |
| 8086:9d23 | 17aa:380b | Intel      | Sunrise Point-LP SMBus       | 1     |            | A388F4B414 |
| 8086:9d23 | 17aa:3823 | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | A295EE15E6 |
| 8086:9d23 | 17aa:383c | Intel      | Sunrise Point-LP SMBus       | 1     |            | CE03C99485 |
| 8086:9d23 | 17aa:3860 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 67454C18A3 |
| 8086:9d23 | 17aa:3862 | Intel      | Sunrise Point-LP SMBus       | 1     |            | D838D80F49 |
| 8086:9d23 | 17aa:504c | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | 3C1A4327F5 |
| 8086:9d23 | 17aa:506c | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | DBA78E9C22 |
| 8086:9d23 | 17aa:506d | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | 0818236221 |
| 8086:9d23 | 1ae0:006b | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | 5EA0111CED |
| 8086:9d23 | 8086:9d23 | Intel      | Sunrise Point-LP SMBus       | 1     |            | C3AA237F35 |
| 8086:9da3 | 1854:0333 | Intel      | Cannon Point-LP SMBus Con... | 1     | i801_smbus | 6D2724E820 |
| 8086:a123 | 17aa:3810 | Intel      | 100 Series/C230 Series Ch... | 1     |            | F445F1B326 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d71 | 103c:8486 | Intel      | Sunrise Point-LP HD Audio    | 5     | snd_hda... | 7DEF867A41 |
| 8086:9d71 | 103c:8488 | Intel      | Sunrise Point-LP HD Audio    | 4     | snd_hda... | 2F6DFEC51C |
| 1002:15de | 17aa:3803 | AMD        | Raven/Raven2/Fenghuang HD... | 3     | snd_hda... | 52036BD95B |
| 1022:15e3 | 17aa:380c | AMD        | Family 17h (Models 10h-1f... | 3     | snd_hda... | 52036BD95B |
| 8086:9d70 | 103c:80d1 | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | FD3B38A3F5 |
| 8086:9d70 | 17aa:3801 | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | 5B8D494C04 |
| 8086:9d71 | 103c:830f | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | C4D6A7BC54 |
| 8086:9d71 | 103c:83b9 | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | 831911B060 |
| 1002:15de | 103c:8496 | AMD        | Raven/Raven2/Fenghuang HD... | 2     | snd_hda... | F720A735A8 |
| 1022:15e3 | 103c:8496 | AMD        | Family 17h (Models 10h-1f... | 2     | snd_hda... | F720A735A8 |
| 8086:5a98 | 1c6c:122a | Intel      | Celeron N3350/Pentium N42... | 2     | snd_hda... | E95114CACB |
| 8086:9d71 | 1028:07eb | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 7EB57A3809 |
| 8086:9d71 | 103c:827d | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | AE7D79F749 |
| 8086:9d71 | 103c:82c1 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | A9E42C34F6 |
| 8086:9d71 | 103c:8313 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 22FE75A663 |
| 8086:9d71 | 103c:83c4 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 65B956E887 |
| 8086:9d71 | 103c:84d8 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | A9BAF3BF1B |
| 8086:9d71 | 1043:1c90 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 7BBD1AB6FE |
| 8086:9d71 | 17aa:224e | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 3AC5B5C4AD |
| 8086:9d71 | 17aa:3806 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 941DF897AA |
| 8086:9d71 | 17aa:3808 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | AC774199A8 |
| 8086:9d71 | 17aa:3831 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 83192A2228 |
| 8086:9dc8 | 103c:8514 | Intel      | Cannon Point-LP High Defi... | 2     | snd_hda... | 74DD313167 |
| 8086:a171 | 1028:080d | Intel      | CM238 HD Audio Controller    | 2     | snd_hda... | 62AF0556D3 |
| 1002:15b3 | 17aa:3802 | ATI Tec... | High Definition Audio Con... | 1     | snd_hda... | B9FC5DC357 |
| 1002:15b3 | 17aa:3804 | AMD        | High Definition Audio Con... | 1     | snd_hda... | B9FC5DC357 |
| 1002:15de | 103c:8497 | AMD        | Raven/Raven2/Fenghuang HD... | 1     | snd_hda... | 314C52C853 |
| 1002:9840 | 103c:81aa | AMD        | Kabini HDMI/DP Audio         | 1     | snd_hda... | D103A0F533 |
| 1022:157a | 103c:81aa | AMD        | Family 15h (Models 60h-6f... | 1     | snd_hda... | D103A0F533 |
| 1022:157a | 17aa:3802 | AMD        | Family 15h (Models 60h-6f... | 1     | snd_hda... | B9FC5DC357 |
| 1022:15e3 | 103c:8497 | AMD        | Family 17h (Models 10h-1f... | 1     | snd_hda... | 314C52C853 |
| 8086:0f04 | 103c:802b | Intel      | Atom Processor Z36xxx/Z37... | 1     | snd_hda... | 07B5ECDCCD |
| 8086:160c | 103c:802d | Intel      | Broadwell-U Audio Controller | 1     | snd_hda... | D9CA1DBE13 |
| 8086:160c | 103c:806c | Intel      | Broadwell-U Audio Controller | 1     | snd_hda... | 462F2D5347 |
| 8086:160c | 103c:806e | Intel      | Broadwell-U Audio Controller | 1     | snd_hda... | 62A9EF950E |
| 8086:2284 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 1     | snd_hda... | BE4128010B |
| 8086:22a8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | FAB48926D9 |
| 8086:3198 | 10ec:118e | Intel      | Smart Sound Technology (I... | 1     | snd_hda... | 56A7BF3D18 |
| 8086:3198 | 10ec:1190 | Intel      | Smart Sound Technology (I... | 1     | snd_hda... | 11EC0315D7 |
| 8086:5a98 | 10ec:11ca | Intel      | Celeron N3350/Pentium N42... | 1     | snd_hda... | 6663E08482 |
| 8086:5a98 | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 1     | snd_hda... | F8913A087C |
| 8086:9ca0 | 103c:806c | Intel      | Wildcat Point-LP High Def... | 1     | snd_hda... | 462F2D5347 |
| 8086:9ca0 | 103c:806e | Intel      | Wildcat Point-LP High Def... | 1     | snd_hda... | 62A9EF950E |
| 8086:9d70 | 103c:80d0 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 97ED13A8C0 |
| 8086:9d70 | 103c:81a1 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | C894E5633B |
| 8086:9d70 | 144d:c141 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 323C96D0DE |
| 8086:9d70 | 17aa:504c | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 3C1A4327F5 |
| 8086:9d71 | 1028:077a | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 57D57D82FE |
| 8086:9d71 | 1028:07aa | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | BC69AFD822 |
| 8086:9d71 | 103c:81ad | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 84C8A9779B |
| 8086:9d71 | 103c:8251 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | C77AFE79C3 |
| 8086:9d71 | 103c:827f | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 7E10A5E689 |
| 8086:9d71 | 103c:83ba | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 3743010FB5 |
| 8086:9d71 | 103c:8438 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 7F01433E42 |
| 8086:9d71 | 103c:8483 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 8B7A2D2A08 |
| 8086:9d71 | 103c:8487 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | C8C863DB3A |
| 8086:9d71 | 103c:8503 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | EC7FFC8F98 |
| 8086:9d71 | 1043:12e1 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 93A44B1518 |
| 8086:9d71 | 1043:14c0 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | FA7C5C4F64 |
| 8086:9d71 | 1043:14f0 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | F65847676C |
| 8086:9d71 | 1043:1b60 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 42FB487F36 |
| 8086:9d71 | 1043:1c40 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 9565CCD6A2 |
| 8086:9d71 | 1043:1cf0 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 2C6BCC75CC |
| 8086:9d71 | 152d:1147 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 7DA5C4A4FA |
| 8086:9d71 | 17aa:3801 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | A295EE15E6 |
| 8086:9d71 | 17aa:3804 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | A388F4B414 |
| 8086:9d71 | 17aa:3809 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | CE03C99485 |
| 8086:9d71 | 17aa:3828 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 67454C18A3 |
| 8086:9d71 | 17aa:3829 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | D838D80F49 |
| 8086:9d71 | 17aa:506c | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | DBA78E9C22 |
| 8086:9d71 | 17aa:506d | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 0818236221 |
| 8086:9d71 | 1ae0:006b | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_soc... | 5EA0111CED |
| 8086:9d71 | 8086:9d71 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | C3AA237F35 |
| 8086:9dc8 | 1854:0333 | Intel      | Cannon Point-LP High Defi... | 1     | snd_hda... | 6D2724E820 |
| 8086:a171 | 17aa:380e | Intel      | CM238 HD Audio Controller    | 1     | snd_hda... | F445F1B326 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d03 | 103c:8486 | Intel      | Sunrise Point-LP SATA Con... | 5     | ahci       | 7DEF867A41 |
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | ahci       | E95114CACB |
| 8086:9d03 | 103c:80d1 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | FD3B38A3F5 |
| 8086:9d03 | 103c:830f | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | C4D6A7BC54 |
| 8086:9d03 | 103c:8488 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 2F6DFEC51C |
| 8086:9d03 | 17aa:380d | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 5B8D494C04 |
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 2     | ahci       | 52036BD95B |
| 1022:7901 | 103c:8496 | AMD        | FCH SATA Controller [AHCI... | 2     | ahci       | F720A735A8 |
| 8086:31e3 | 8086:7270 | Intel      | SATA controller              | 2     | ahci       | 56A7BF3D18 |
| 8086:9d03 | 1028:07eb | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 7EB57A3809 |
| 8086:9d03 | 103c:8313 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 22FE75A663 |
| 8086:9d03 | 103c:83c4 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 65B956E887 |
| 8086:9d03 | 103c:84d8 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | A9BAF3BF1B |
| 8086:9d03 | 17aa:383b | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | AC774199A8 |
| 1022:7901 | 103c:8497 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 314C52C853 |
| 1022:7904 | 103c:81aa | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | D103A0F533 |
| 1022:7904 | 17aa:3804 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | B9FC5DC357 |
| 8086:5ae3 | 17aa:3803 | Intel      | Celeron N3350/Pentium N42... | 1     | ahci       | F8913A087C |
| 8086:9c83 | 103c:802d | Intel      | Wildcat Point-LP SATA Con... | 1     | ahci       | D9CA1DBE13 |
| 8086:9c83 | 103c:806c | Intel      | Wildcat Point-LP SATA Con... | 1     | ahci       | 462F2D5347 |
| 8086:9c83 | 103c:806e | Intel      | Wildcat Point-LP SATA Con... | 1     | ahci       | 62A9EF950E |
| 8086:9d03 | 103c:80d0 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 97ED13A8C0 |
| 8086:9d03 | 103c:81a1 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | C894E5633B |
| 8086:9d03 | 103c:81ad | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 84C8A9779B |
| 8086:9d03 | 103c:8251 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | C77AFE79C3 |
| 8086:9d03 | 103c:8483 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 8B7A2D2A08 |
| 8086:9d03 | 103c:8487 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | C8C863DB3A |
| 8086:9d03 | 1043:12e1 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 93A44B1518 |
| 8086:9d03 | 1043:14c0 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | FA7C5C4F64 |
| 8086:9d03 | 1043:14f0 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | F65847676C |
| 8086:9d03 | 1043:1c40 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 9565CCD6A2 |
| 8086:9d03 | 1043:1c90 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 7BBD1AB6FE |
| 8086:9d03 | 144d:c141 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 323C96D0DE |
| 8086:9d03 | 17aa:3810 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | A388F4B414 |
| 8086:9d03 | 17aa:3822 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | A295EE15E6 |
| 8086:9d03 | 17aa:504c | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 3C1A4327F5 |
| 8086:9d03 | 8086:9d03 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | C3AA237F35 |
| 8086:9dd3 | 1854:0333 | Intel      | Cannon Point-LP SATA Cont... | 1     | ahci       | 6D2724E820 |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 12    | nvme       | 74DD313167 |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 11    | nvme       | 3AC5B5C4AD |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 6     | nvme       | 7F01433E42 |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | Non-Volatile memory contr... | 4     | nvme       | 2F6DFEC51C |
| 1179:0113 | 1179:0001 | Toshiba... | BG3 NVMe SSD Controller      | 2     | nvme       | 52036BD95B |
| 1179:0115 | 1179:0001 | Toshiba... | XG4 NVMe SSD Controller      | 2     | nvme       | F445F1B326 |
| 1179:011a | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 2     | nvme       | 62AF0556D3 |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 2     | nvme       | 7DA5C4A4FA |
| 10ec:5762 | 10ec:5762 | Realtek... | Realtek Non-Volatile memo... | 1     | nvme       | BC69AFD822 |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 1     | nvme       | 941DF897AA |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/PC SN720 NV... | 1     | nvme       | 83192A2228 |
| 1c5c:1527 | 1c5c:1527 | SK Hynix   | Non-Volatile memory contr... | 1     | nvme       | 1510224C03 |
| 1cc4:2260 | 1cc4:2260 | Union M... | Non-Volatile memory contr... | 1     | nvme       | CE03C99485 |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:282a | 1028:077a | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 57D57D82FE |
| 8086:282a | 103c:8488 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 801D97EB08 |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:15d2 | 103c:8514 | Intel      | JHL6540 Thunderbolt 3 NHI... | 2     | thunder... | 74DD313167 |
| 8086:1911 | 17aa:224e | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 3AC5B5C4AD |
| 8086:1911 | 17aa:3804 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 941DF897AA |
| 8086:15d2 | 103c:8438 | Intel      | JHL6540 Thunderbolt 3 NHI... | 1     | thunder... | 7F01433E42 |
| 8086:15d2 | 103c:8503 | Intel      | JHL6540 Thunderbolt 3 NHI... | 1     | thunder... | EC7FFC8F98 |
| 8086:15d2 | 2222:1111 | Intel      | JHL6540 Thunderbolt 3 NHI... | 1     | thunder... | 3AC5B5C4AD |
| 8086:15d2 | 8086:0000 | Intel      | JHL6540 Thunderbolt 3 NHI... | 1     | thunder... | 62AF0556D3 |
| 8086:15d9 | 2222:1111 | Intel      | JHL6340 Thunderbolt 3 NHI... | 1     | thunder... | A462F23545 |
| 8086:1911 | 103c:8503 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | EC7FFC8F98 |
| 8086:1911 | 1043:12e1 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 93A44B1518 |
| 8086:1911 | 17aa:504c | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 3C1A4327F5 |
| 8086:1911 | 17aa:506d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 0818236221 |
| 8086:1911 | 1854:0333 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 6D2724E820 |
| 8086:1911 | 1ae0:006b | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 5EA0111CED |
| 8086:1911 | 8086:1911 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | C3AA237F35 |

### Unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:5aa2 | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | F8913A087C |
| 8086:5aa2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | 6663E08482 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d2f | 1043:201f | Intel      | Sunrise Point-LP USB 3.0 ... | 8     | xhci_hcd   | 7BBD1AB6FE |
| 8086:22b5 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 6     | xhci_pci   | FAB48926D9 |
| 8086:9d2f | 103c:8486 | Intel      | Sunrise Point-LP USB 3.0 ... | 5     | xhci_hcd   | 7DEF867A41 |
| 8086:9d2f | 103c:8488 | Intel      | Sunrise Point-LP USB 3.0 ... | 4     | xhci_hcd   | 2F6DFEC51C |
| 1022:15e0 | 17aa:3805 | AMD        | Raven USB 3.1                | 3     | xhci_hcd   | 52036BD95B |
| 1022:15e1 | 17aa:3806 | AMD        | Raven USB 3.1                | 3     | xhci_hcd   | 52036BD95B |
| 8086:5aa8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 3     | xhci_hcd   | E95114CACB |
| 8086:9d2f | 103c:80d1 | Intel      | Sunrise Point-LP USB 3.0 ... | 3     | xhci_hcd   | FD3B38A3F5 |
| 8086:9d2f | 103c:830f | Intel      | Sunrise Point-LP USB 3.0 ... | 3     | xhci_hcd   | C4D6A7BC54 |
| 8086:9d2f | 103c:83b9 | Intel      | Sunrise Point-LP USB 3.0 ... | 3     | xhci_hcd   | 831911B060 |
| 8086:9d2f | 17aa:3811 | Intel      | Sunrise Point-LP USB 3.0 ... | 3     | xhci_hcd   | 5B8D494C04 |
| 1022:15e0 | 103c:8496 | AMD        | Raven USB 3.1                | 2     | xhci_hcd   | F720A735A8 |
| 1022:15e1 | 103c:8496 | AMD        | Raven USB 3.1                | 2     | xhci_hcd   | F720A735A8 |
| 8086:15d4 | 103c:8514 | Intel      | JHL6540 Thunderbolt 3 USB... | 2     | xhci_hcd   | 74DD313167 |
| 8086:15d4 | 2222:1111 | Intel      | JHL6540 Thunderbolt 3 USB... | 2     | xhci_hcd   | 831911B060 |
| 8086:31a8 | 8086:7270 | Intel      | USB Controller               | 2     | xhci_hcd   | 56A7BF3D18 |
| 8086:9d2f | 1028:07eb | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | 7EB57A3809 |
| 8086:9d2f | 103c:827d | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | AE7D79F749 |
| 8086:9d2f | 103c:82c1 | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | A9E42C34F6 |
| 8086:9d2f | 103c:8313 | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | 22FE75A663 |
| 8086:9d2f | 103c:83c4 | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | 65B956E887 |
| 8086:9d2f | 103c:84d8 | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | A9BAF3BF1B |
| 8086:9d2f | 17aa:224e | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | 3AC5B5C4AD |
| 8086:9d2f | 17aa:3805 | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | 941DF897AA |
| 8086:9d2f | 17aa:383f | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | AC774199A8 |
| 8086:9d2f | 17aa:386a | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | 83192A2228 |
| 8086:9ded | 103c:8514 | Intel      | Cannon Point-LP USB 3.1 x... | 2     | xhci_hcd   | 74DD313167 |
| 8086:a12f | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 2     | xhci_hcd   | 62AF0556D3 |
| 1022:15e0 | 103c:8497 | AMD        | Raven USB 3.1                | 1     | xhci_hcd   | 314C52C853 |
| 1022:15e1 | 103c:8497 | AMD        | Raven USB 3.1                | 1     | xhci_hcd   | 314C52C853 |
| 1022:7908 | 103c:81aa | AMD        | FCH USB EHCI Controller      | 1     | ehci_pci   | D103A0F533 |
| 1022:7908 | 17aa:3802 | AMD        | FCH USB EHCI Controller      | 1     | ehci_pci   | B9FC5DC357 |
| 1022:7914 | 103c:81aa | AMD        | FCH USB XHCI Controller      | 1     | xhci_hcd   | D103A0F533 |
| 1022:7914 | 17aa:3802 | AMD        | FCH USB XHCI Controller      | 1     | xhci_hcd   | B9FC5DC357 |
| 1b21:1142 | 103c:8190 | ASMedia... | ASM1042A USB 3.0 Host Con... | 1     | xhci_hcd   | A462F23545 |
| 1b73:1100 | 17ef:3067 | Fresco ... | FL1100 USB 3.0 Host Contr... | 1     | xhci_hcd   | 3AC5B5C4AD |
| 1b73:1100 | 17ef:3068 | Fresco ... | FL1100 USB 3.0 Host Contr... | 1     | xhci_hcd   | 3AC5B5C4AD |
| 8086:0f35 | 103c:802b | Intel      | Atom Processor Z36xxx/Z37... | 1     | xhci_pci   | 07B5ECDCCD |
| 8086:15d4 |           | Intel      | JHL6540 Thunderbolt 3 USB... | 1     | xhci_hcd   | 1510224C03 |
| 8086:15d4 | 103c:8438 | Intel      | JHL6540 Thunderbolt 3 USB... | 1     | xhci_hcd   | 7F01433E42 |
| 8086:15d4 | 103c:8503 | Intel      | JHL6540 Thunderbolt 3 USB... | 1     | xhci_hcd   | EC7FFC8F98 |
| 8086:15d4 | 8086:0000 | Intel      | JHL6540 Thunderbolt 3 USB... | 1     | xhci_hcd   | 62AF0556D3 |
| 8086:15db | 2222:1111 | Intel      | JHL6340 Thunderbolt 3 USB... | 1     | xhci_hcd   | 7E10A5E689 |
| 8086:22b5 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 1     | xhci_pci   | BE4128010B |
| 8086:22b7 | 8086:7270 | Intel      | USB Synopsys Controller      | 1     |            | FAB48926D9 |
| 8086:5aa8 | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 1     | xhci_hcd   | F8913A087C |
| 8086:9ca6 | 103c:806c | Intel      | Wildcat Point-LP USB EHCI... | 1     | ehci_pci   | 462F2D5347 |
| 8086:9cb1 | 103c:802d | Intel      | Wildcat Point-LP USB xHCI... | 1     | xhci_hcd   | D9CA1DBE13 |
| 8086:9cb1 | 103c:806c | Intel      | Wildcat Point-LP USB xHCI... | 1     |            | 462F2D5347 |
| 8086:9cb1 | 103c:806e | Intel      | Wildcat Point-LP USB xHCI... | 1     | xhci_pci   | 62A9EF950E |
| 8086:9d2f | 1028:077a | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 57D57D82FE |
| 8086:9d2f | 1028:07aa | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | BC69AFD822 |
| 8086:9d2f | 103c:80d0 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 97ED13A8C0 |
| 8086:9d2f | 103c:81a1 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | C894E5633B |
| 8086:9d2f | 103c:81ad | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 84C8A9779B |
| 8086:9d2f | 103c:8251 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | C77AFE79C3 |
| 8086:9d2f | 103c:827f | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 7E10A5E689 |
| 8086:9d2f | 103c:83ba | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 3743010FB5 |
| 8086:9d2f | 103c:8438 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 7F01433E42 |
| 8086:9d2f | 103c:8483 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 8B7A2D2A08 |
| 8086:9d2f | 103c:8487 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | C8C863DB3A |
| 8086:9d2f | 103c:8503 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | EC7FFC8F98 |
| 8086:9d2f | 144d:c141 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 323C96D0DE |
| 8086:9d2f | 152d:1147 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 7DA5C4A4FA |
| 8086:9d2f | 17aa:380b | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | A388F4B414 |
| 8086:9d2f | 17aa:3825 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_pci   | A295EE15E6 |
| 8086:9d2f | 17aa:383e | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | CE03C99485 |
| 8086:9d2f | 17aa:3862 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 67454C18A3 |
| 8086:9d2f | 17aa:3864 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | D838D80F49 |
| 8086:9d2f | 17aa:504c | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_pci   | 3C1A4327F5 |
| 8086:9d2f | 17aa:506c | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | DBA78E9C22 |
| 8086:9d2f | 17aa:506d | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 0818236221 |
| 8086:9d2f | 1ae0:006b | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_pci   | 5EA0111CED |
| 8086:9d2f | 8086:9d2f | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | C3AA237F35 |
| 8086:9ded | 1854:0333 | Intel      | Cannon Point-LP USB 3.1 x... | 1     | xhci_hcd   | 6D2724E820 |
| 8086:a12f | 17aa:3807 | Intel      | 100 Series/C230 Series Ch... | 1     | xhci_hcd   | F445F1B326 |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:694e | 1002:694e | AMD        | Polaris 22 XL [Radeon RX ... | 1     | amdgpu     | 07A9851CD6 |

