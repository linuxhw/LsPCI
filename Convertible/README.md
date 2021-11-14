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
| 1022:1632 |           | AMD        | Renoir PCIe Dummy Host Br... | 198   |            | 28B152BB19 |
| 1022:1635 | 1022:1635 | AMD        | Renoir Internal PCIe GPP ... | 198   | pcieport   | 28B152BB19 |
| 1022:1448 |           | AMD        | Renoir Device 24: Function 0 | 197   |            | 28B152BB19 |
| 1022:1449 |           | AMD        | Renoir Device 24: Function 1 | 197   |            | 28B152BB19 |
| 1022:144a |           | AMD        | Renoir Device 24: Function 2 | 197   |            | 28B152BB19 |
| 1022:144b |           | AMD        | Renoir Device 24: Function 3 | 197   | k10temp    | 28B152BB19 |
| 1022:144c |           | AMD        | Renoir Device 24: Function 4 | 197   |            | 28B152BB19 |
| 1022:144d |           | AMD        | Renoir Device 24: Function 5 | 197   |            | 28B152BB19 |
| 1022:144e |           | AMD        | Renoir Device 24: Function 6 | 197   |            | 28B152BB19 |
| 1022:144f |           | AMD        | Renoir Device 24: Function 7 | 197   |            | 28B152BB19 |
| 1022:1634 | 1022:1453 | AMD        | Renoir/Cezanne PCIe GPP B... | 193   | pcieport   | 28B152BB19 |
| 1022:1452 |           | AMD        | Family 17h (Models 00h-1f... | 124   |            | 3ADCB9ECF9 |
| 1022:15e8 |           | AMD        | Raven/Raven2 Device 24: F... | 124   |            | 3ADCB9ECF9 |
| 1022:15e9 |           | AMD        | Raven/Raven2 Device 24: F... | 124   |            | 3ADCB9ECF9 |
| 1022:15ea |           | AMD        | Raven/Raven2 Device 24: F... | 124   |            | 3ADCB9ECF9 |
| 1022:15eb |           | AMD        | Raven/Raven2 Device 24: F... | 124   | k10temp    | 3ADCB9ECF9 |
| 1022:15ec |           | AMD        | Raven/Raven2 Device 24: F... | 124   |            | 3ADCB9ECF9 |
| 1022:15ed |           | AMD        | Raven/Raven2 Device 24: F... | 124   |            | 3ADCB9ECF9 |
| 1022:15ee |           | AMD        | Raven/Raven2 Device 24: F... | 124   |            | 3ADCB9ECF9 |
| 1022:15ef |           | AMD        | Raven/Raven2 Device 24: F... | 124   |            | 3ADCB9ECF9 |
| 1022:15db | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 122   | pcieport   | 3ADCB9ECF9 |
| 1022:1630 | 1022:1630 | AMD        | Renoir/Cezanne Root Complex  | 91    |            | 65A49B7280 |
| 1022:790e | 1022:790e | AMD        | FCH LPC Bridge               | 70    |            | 65A49B7280 |
| 8086:a0bc |           | Intel      | PCI bridge                   | 67    | pcieport   | 1EC4861E97 |
| 1022:15dc | 1022:0000 | AMD        | Raven/Raven2 Internal PCI... | 60    | pcieport   | 0DFE108C69 |
| 8086:9a09 | 17aa:5089 | Intel      | 11th Gen Core Processor P... | 59    | pcieport   | 1EC4861E97 |
| 8086:9a14 | 17aa:5089 | Intel      | 11th Gen Core Processor H... | 59    |            | 1EC4861E97 |
| 8086:a082 | 17aa:5089 | Intel      | Tiger Lake-LP LPC Controller | 59    |            | 1EC4861E97 |
| 8086:9a27 | 17aa:5089 | Intel      | Tiger Lake-LP Thunderbolt... | 57    | pcieport   | 1EC4861E97 |
| 8086:9d14 | 17aa:3835 | Intel      | Sunrise Point-LP PCI Expr... | 44    | pcieport   | A2717638BE |
| 8086:9d15 | 17aa:382f | Intel      | Sunrise Point-LP PCI Expr... | 44    | pcieport   | A2717638BE |
| 8086:9d4e | 17aa:3803 | Intel      | Sunrise Point LPC Control... | 39    |            | A2717638BE |
| 1022:1630 | 103c:876e | AMD        | Renoir/Cezanne Root Complex  | 38    |            | 28B152BB19 |
| 1022:790e | 103c:876e | AMD        | FCH LPC Bridge               | 38    |            | 28B152BB19 |
| 8086:31e8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 38    |            | 4DBC03E904 |
| 8086:31d8 | 8086:7270 | Intel      | Gemini Lake PCI Express R... | 37    | pcieport   | 4DBC03E904 |
| 1022:1630 | 103c:876f | AMD        | Renoir/Cezanne Root Complex  | 34    |            | 5F67B298AB |
| 1022:790e | 103c:876f | AMD        | FCH LPC Bridge               | 34    |            | 5F67B298AB |
| 8086:5ae8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 34    | lpc_ich    | AA88177E76 |
| 8086:0284 | 17aa:3802 | Intel      | Comet Lake PCH-LP LPC Pre... | 33    |            | 6F6E5DAF18 |
| 8086:02b4 | 17aa:3803 | Intel      | Comet Lake PCI Express Ro... | 33    | pcieport   | 6F6E5DAF18 |
| 1022:15d3 | 1022:1453 | AMD        | Raven/Raven2 PCIe GPP Bri... | 32    | pcieport   | 6AF7A7F851 |
| 8086:2280 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 32    | iosf_mb... | 74FE90715F |
| 8086:229c | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 32    | lpc_ich    | 74FE90715F |
| 8086:5ad7 |           | Intel      | Celeron N3350/Pentium N42... | 32    | pcieport   | AA88177E76 |
| 8086:5af0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 32    |            | AA88177E76 |
| 8086:9b61 | 17aa:380a | Intel      | Comet Lake-U v1 4c Host B... | 30    | skl_uncore | 6F6E5DAF18 |
| 8086:15d3 | 2222:1111 | Intel      | JHL6540 Thunderbolt 3 Bri... | 26    | pcieport   | 3C5AC88729 |
| 8086:5914 | 103c:83b9 | Intel      | Xeon E3-1200 v6/7th Gen C... | 26    | skl_uncore | BBB2DB43B4 |
| 8086:9d10 | 103c:83b9 | Intel      | Sunrise Point-LP PCI Expr... | 26    | pcieport   | BBB2DB43B4 |
| 8086:9d11 | 103c:83b9 | Intel      | Sunrise Point-LP PCI Expr... | 26    | pcieport   | BBB2DB43B4 |
| 8086:9d14 | 103c:83b9 | Intel      | Sunrise Point-LP PCI Expr... | 26    | pcieport   | BBB2DB43B4 |
| 8086:9d18 | 103c:83b9 | Intel      | Sunrise Point-LP PCI Expr... | 26    | pcieport   | BBB2DB43B4 |
| 8086:9d4e | 103c:83b9 | Intel      | Sunrise Point LPC Control... | 26    |            | BBB2DB43B4 |
| 8086:15d3 | 103c:8514 | Intel      | JHL6540 Thunderbolt 3 Bri... | 25    | pcieport   | 211EF30EF4 |
| 8086:3482 | 17aa:3812 | Intel      | Ice Lake-LP LPC Controller   | 25    |            | 740EA7B2E9 |
| 8086:34b8 | 17aa:3810 | Intel      | Ice Lake-LP PCIe Port #1     | 25    | pcieport   | 740EA7B2E9 |
| 8086:34be | 17aa:3801 | Intel      | Ice Lake-LP PCIe Port #7     | 25    | pcieport   | 740EA7B2E9 |
| 8086:3e34 | 103c:8514 | Intel      | Coffee Lake HOST and DRAM... | 25    | skl_uncore | 211EF30EF4 |
| 8086:8a1d |           | Intel      | Ice Lake Thunderbolt 3 PC... | 25    | pcieport   | 138EC046F1 |
| 8086:9d84 | 103c:8514 | Intel      | Cannon Point-LP LPC Contr... | 25    |            | 211EF30EF4 |
| 8086:9db4 | 103c:8514 | Intel      | Cannon Point-LP PCI Expre... | 25    | pcieport   | 211EF30EF4 |
| 8086:9db7 | 8086:9db7 | Intel      | 300 Series Chipset PCIe P... | 25    | pcieport   | 4C9743CDD1 |
| 8086:9dba | 103c:8514 | Intel      | 300 Series Chipset PCIe P... | 25    | pcieport   | 211EF30EF4 |
| 8086:9dbc | 103c:8514 | Intel      | Cannon Point-LP PCI Expre... | 25    | pcieport   | 211EF30EF4 |
| 8086:34b0 | 17aa:380f | Intel      | Ice Lake-LP PCI Express R... | 24    | pcieport   | 740EA7B2E9 |
| 8086:5904 | 17aa:382b | Intel      | Xeon E3-1200 v6/7th Gen C... | 24    | skl_uncore | 4C8282BB42 |
| 8086:8a12 | 17aa:3807 | Intel      | Ice Lake-LP Processor Hos... | 24    | icl_uncore | 740EA7B2E9 |
| 1022:15d0 | 103c:85dd | AMD        | Raven/Raven2 Root Complex    | 23    |            | C4EA79E269 |
| 1022:15d3 | 103c:85dd | AMD        | Raven/Raven2 PCIe GPP Bri... | 23    | pcieport   | C4EA79E269 |
| 1022:790e | 103c:85dd | AMD        | FCH LPC Bridge               | 23    |            | C4EA79E269 |
| 8086:31f0 | 8086:7270 | Intel      | Gemini Lake Host Bridge      | 23    |            | E4FB415516 |
| 8086:3482 | 1028:08b0 | Intel      | Ice Lake-LP LPC Controller   | 23    |            | 138EC046F1 |
| 8086:34b7 | 1028:08b0 | Intel      | Ice Lake-LP PCI Express R... | 23    | pcieport   | 138EC046F1 |
| 8086:8a12 | 1028:08b0 | Intel      | Ice Lake-LP Processor Hos... | 23    | icl_uncore | 138EC046F1 |
| 8086:9d84 | 17aa:380c | Intel      | Cannon Point-LP LPC Contr... | 23    |            | 4C9743CDD1 |
| 8086:1904 | 17aa:2238 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 22    | skl_uncore | DD105BA06B |
| 8086:9d10 | 17aa:2238 | Intel      | Sunrise Point-LP PCI Expr... | 22    | pcieport   | DD105BA06B |
| 8086:9d12 | 17aa:2238 | Intel      | Sunrise Point-LP PCI Expr... | 22    | pcieport   | DD105BA06B |
| 8086:9d48 | 17aa:2238 | Intel      | Sunrise Point-LP LPC Cont... | 22    |            | DD105BA06B |
| 1022:15d0 | 17aa:380a | AMD        | Raven/Raven2 Root Complex    | 21    |            | 6AF7A7F851 |
| 1022:790e | 17aa:3819 | AMD        | FCH LPC Bridge               | 21    |            | 6AF7A7F851 |
| 8086:15d3 | 17aa:2292 | Intel      | JHL6540 Thunderbolt 3 Bri... | 21    | pcieport   | 8F10E30326 |
| 8086:34b0 | 1028:08b0 | Intel      | Ice Lake-LP PCI Express R... | 21    | pcieport   | 138EC046F1 |
| 8086:3e34 | 17aa:3808 | Intel      | Coffee Lake HOST and DRAM... | 21    | skl_uncore | 4C9743CDD1 |
| 8086:8a21 |           | Intel      | Ice Lake Thunderbolt 3 PC... | 21    | pcieport   | 138EC046F1 |
| 8086:9a23 | 8086:7270 | Intel      | Tiger Lake-LP Thunderbolt... | 21    | pcieport   | 7851B07853 |
| 8086:9d14 | 17aa:3856 | Intel      | Sunrise Point-LP PCI Expr... | 21    | pcieport   | 72617E5DD9 |
| 8086:9d18 | 17aa:382a | Intel      | Sunrise Point-LP PCI Expr... | 21    | pcieport   | A2717638BE |
| 8086:9d18 | 17aa:3844 | Intel      | Sunrise Point-LP PCI Expr... | 21    | pcieport   | 72617E5DD9 |
| 8086:9db0 | 17aa:380f | Intel      | Cannon Point-LP PCI Expre... | 21    | pcieport   | 4C9743CDD1 |
| 8086:5914 | 17aa:3821 | Intel      | Xeon E3-1200 v6/7th Gen C... | 20    | skl_uncore | A52209C9F2 |
| 8086:5914 | 17aa:382b | Intel      | Xeon E3-1200 v6/7th Gen C... | 20    | skl_uncore | A2717638BE |
| 8086:9d10 | 17aa:384f | Intel      | Sunrise Point-LP PCI Expr... | 20    | pcieport   | A52209C9F2 |
| 8086:9d18 | 17aa:384b | Intel      | Sunrise Point-LP PCI Expr... | 20    | pcieport   | A52209C9F2 |
| 8086:9d4e | 17aa:3814 | Intel      | Sunrise Point LPC Control... | 20    |            | 72617E5DD9 |
| 8086:9d4e | 17aa:3816 | Intel      | Sunrise Point LPC Control... | 20    |            | A52209C9F2 |
| 1022:15d0 | 103c:85de | AMD        | Raven/Raven2 Root Complex    | 19    |            | 3ADCB9ECF9 |
| 1022:15d3 | 103c:85de | AMD        | Raven/Raven2 PCIe GPP Bri... | 19    | pcieport   | 3ADCB9ECF9 |
| 1022:790e | 103c:85de | AMD        | FCH LPC Bridge               | 19    |            | 3ADCB9ECF9 |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:522a | 17aa:5089 | Realtek... | RTS522A PCI Express Card ... | 59    | rtsx_pci   | 1EC4861E97 |
| 10ec:522a | 17aa:380e | Realtek... | RTS522A PCI Express Card ... | 50    | rtsx_pci   | F07B9B77F5 |
| 10ec:5229 | 17aa:3832 | Realtek... | RTS5229 PCI Express Card ... | 44    | rtsx_pci   | A2717638BE |
| 10ec:522a | 103c:876e | Realtek... | RTS522A PCI Express Card ... | 38    | rtsx_pci   | 28B152BB19 |
| 10ec:522a | 103c:876f | Realtek... | RTS522A PCI Express Card ... | 34    | rtsx_pci   | 5F67B298AB |
| 10ec:525a | 103c:83b9 | Realtek... | RTS525A PCI Express Card ... | 26    | rtsx_pci   | BBB2DB43B4 |
| 10ec:525a | 103c:8514 | Realtek... | RTS525A PCI Express Card ... | 25    | rtsx_pci   | 211EF30EF4 |
| 10ec:522a | 103c:85dd | Realtek... | RTS522A PCI Express Card ... | 23    | rtsx_pci   | C4EA79E269 |
| 10ec:525a | 1028:08b0 | Realtek... | RTS525A PCI Express Card ... | 23    | rtsx_pci   | 138EC046F1 |
| 10ec:525a | 17aa:2238 | Realtek... | RTS525A PCI Express Card ... | 20    | rtsx_pci   | DD105BA06B |
| 10ec:522a | 103c:85de | Realtek... | RTS522A PCI Express Card ... | 19    | rtsx_pci   | 3ADCB9ECF9 |
| 10ec:522a | 103c:827d | Realtek... | RTS522A PCI Express Card ... | 18    | rtsx_pci   | 95D389BFE5 |
| 10ec:5229 | 17aa:380d | Realtek... | RTS5229 PCI Express Card ... | 16    | rtsx_pci   | 350D402895 |
| 10ec:522a | 103c:83c6 | Realtek... | RTS522A PCI Express Card ... | 16    | rtsx_pci   | 5174E188C0 |
| 10ec:522a | 103c:8497 | Realtek... | RTS522A PCI Express Card ... | 16    | rtsx_pci   | 0DFE108C69 |
| 10ec:522a | 103c:830f | Realtek... | RTS522A PCI Express Card ... | 15    | rtsx_pci   | 3286ED83B9 |
| 10ec:522a | 103c:8496 | Realtek... | RTS522A PCI Express Card ... | 15    | rtsx_pci   | DFB9789AF2 |
| 10ec:525a | 1028:077a | Realtek... | RTS525A PCI Express Card ... | 15    | rtsx_pci   | 8F7ADB6CD3 |
| 10ec:5229 | 17aa:381d | Realtek... | RTS5229 PCI Express Card ... | 14    | rtsx_pci   | AED568D94C |
| 10ec:522a | 103c:8735 | Realtek... | RTS522A PCI Express Card ... | 14    | rtsx_pci   | 4EE6C35B8F |
| 10ec:522a | 17aa:3809 | Realtek... | RTS522A PCI Express Card ... | 14    | rtsx_pci   | 740EA7B2E9 |
| 10ec:525a | 17aa:224e | Realtek... | RTS525A PCI Express Card ... | 14    | rtsx_pci   | 3C24D27D51 |
| 10ec:5260 | 1028:09ff | Realtek... | RTS5260 PCI Express Card ... | 14    | rtsx_pci   | 5B10037DA5 |
| 10ec:525a | 103c:83bb | Realtek... | RTS525A PCI Express Card ... | 13    | rtsx_pci   | BA09E3B76F |
| 10ec:5229 | 17aa:381b | Realtek... | RTS5229 PCI Express Card ... | 12    | rtsx_pci   | 5154E96ABE |
| 10ec:522a | 17aa:5078 | Realtek... | RTS522A PCI Express Card ... | 12    | rtsx_pci   | B946F364DB |
| 10ec:525a | 1028:080d | Realtek... | RTS525A PCI Express Card ... | 12    | rtsx_pci   | 27D7C254CC |
| 10ec:522a | 17aa:506d | Realtek... | RTS522A PCI Express Card ... | 11    | rtsx_pci   | 99C878CD5E |
| 10ec:5229 | 103c:82e1 | Realtek... | RTS5229 PCI Express Card ... | 10    | rtsx_pci   | AB13E942F9 |
| 10ec:5227 | 103c:81a1 | Realtek... | RTS5227 PCI Express Card ... | 9     | rtsx_pci   | B37CBA5DF4 |
| 10ec:522a | 103c:80d1 | Realtek... | RTS522A PCI Express Card ... | 9     | rtsx_pci   | 629D516666 |
| 10ec:522a | 103c:86b1 | Realtek... | RTS522A PCI Express Card ... | 9     | rtsx_pci   | F3B0D882C2 |
| 10ec:522a | 103c:86b2 | Realtek... | RTS522A PCI Express Card ... | 9     | rtsx_pci   | B054E02856 |
| 10ec:522a | 17aa:2237 | Realtek... | RTS522A PCI Express Card ... | 9     | rtsx_pci   | 24D1BD52CC |
| 10ec:525a | 103c:86f9 | Realtek... | RTS525A PCI Express Card ... | 9     | rtsx_pci   | 4967676215 |
| 10ec:522a | 103c:8484 | Realtek... | RTS522A PCI Express Card ... | 8     | rtsx_pci   | F3D65BB221 |
| 10ec:522a | 17aa:506c | Realtek... | RTS522A PCI Express Card ... | 8     | rtsx_pci   | B39CD022D3 |
| 10ec:522a | 17aa:5077 | Realtek... | RTS522A PCI Express Card ... | 8     | rtsx_pci   | B9971B685A |
| 10ec:525a | 103c:863f | Realtek... | RTS525A PCI Express Card ... | 8     | rtsx_pci   | 2A2CFDB7D4 |
| 10ec:5227 | 103c:802b | Realtek... | RTS5227 PCI Express Card ... | 7     | rtsx_pci   | 4E86625634 |
| 10ec:5227 | 103c:802d | Realtek... | RTS5227 PCI Express Card ... | 7     | rtsx_pci   | 0B68C3F5C3 |
| 10ec:522a | 103c:81ad | Realtek... | RTS522A PCI Express Card ... | 7     | rtsx_pci   | A6FF75E220 |
| 10ec:522a | 103c:87f4 | Realtek... | RTS522A PCI Express Card ... | 7     | rtsx_pci   | 6461BFC243 |
| 10ec:522a | 17aa:5061 | Realtek... | RTS522A PCI Express Card ... | 7     | rtsx_pci   | 16AC72B8EA |
| 10ec:525a | 1028:09cd | Realtek... | RTS525A PCI Express Card ... | 7     | rtsx_pci   | 20FA4B73D7 |
| 10ec:525a | 103c:8709 | Realtek... | RTS525A PCI Express Card ... | 7     | rtsx_pci   | 444E13B5ED |
| 10ec:5229 | 1025:1176 | Realtek... | RTS5229 PCI Express Card ... | 6     | rtsx_pci   | 566FA6B1D5 |
| 10ec:522a | 103c:8313 | Realtek... | RTS522A PCI Express Card ... | 6     | rtsx_pci   | 5D0F309968 |
| 10ec:522a | 103c:8483 | Realtek... | RTS522A PCI Express Card ... | 6     | rtsx_pci   | C48CB1FCCF |
| 10ec:522a | 17aa:3817 | Realtek... | RTS522A PCI Express Card ... | 6     | rtsx_pci   | 611C3C0C19 |
| 10ec:522a | 17aa:381e | Realtek... | RTS522A PCI Express Card ... | 6     | rtsx_pci   | 65A49B7280 |
| 10ec:525a | 1028:08e2 | Realtek... | RTS525A PCI Express Card ... | 6     | rtsx_pci   | ADF32CA36B |
| 10ec:525a | 103c:87f7 | Realtek... | RTS525A PCI Express Card ... | 6     | rtsx_pci   | E1D0678746 |
| 10ec:5229 | 103c:81aa | Realtek... | RTS5229 PCI Express Card ... | 5     | rtsx_pci   | 633D386331 |
| 10ec:522a | 103c:81a9 | Realtek... | RTS522A PCI Express Card ... | 5     | rtsx_pci   | 0BB3F77C75 |
| 10ec:522a | 103c:85e7 | Realtek... | RTS522A PCI Express Card ... | 5     | rtsx_pci   | 169477DE3F |
| 10ec:522a | 103c:87a9 | Realtek... | RTS522A PCI Express Card ... | 5     | rtsx_pci   | 96C4D24CAB |
| 10ec:522a | 103c:8825 | Realtek... | RTS522A PCI Express Card ... | 5     | rtsx_pci   | 24060045B4 |
| 10ec:525a | 1028:08b6 | Realtek... | RTS525A PCI Express Card ... | 5     | rtsx_pci   | B0722E1B57 |
| 10ec:525a | 103c:827f | Realtek... | RTS525A PCI Express Card ... | 5     | rtsx_pci   | BD5BDFD31F |
| 10ec:525a | 103c:86fa | Realtek... | RTS525A PCI Express Card ... | 5     | rtsx_pci   | 635BBB6F75 |
| 10ec:5229 | 17aa:3810 | Realtek... | RTS5229 PCI Express Card ... | 4     | rtsx_pci   | 6931FAE5CC |
| 10ec:522a | 103c:806e | Realtek... | RTS522A PCI Express Card ... | 4     | rtsx_pci   | A8AA7A1D17 |
| 10ec:522a | 103c:81a7 | Realtek... | RTS522A PCI Express Card ... | 4     | rtsx_pci   | BC77E670A5 |
| 10ec:522a | 103c:83c4 | Realtek... | RTS522A PCI Express Card ... | 4     | rtsx_pci   | 3F62C672FB |
| 10ec:522a | 103c:850c | Realtek... | RTS522A PCI Express Card ... | 4     | rtsx_pci   | EEC05D1BF9 |
| 10ec:522a | 103c:875b | Realtek... | RTS522A PCI Express Card ... | 4     | rtsx_pci   | 258D846B85 |
| 10ec:522a | 103c:8774 | Realtek... | RTS522A PCI Express Card ... | 4     | rtsx_pci   | 1E2B68B7D8 |
| 10ec:522a | 17aa:3811 | Realtek... | RTS522A PCI Express Card ... | 4     | rtsx_pci   | 358875FD3C |
| 10ec:525a | 1028:09c6 | Realtek... | RTS525A PCI Express Card ... | 4     | rtsx_pci   | F146E46238 |
| 10ec:525a | 1028:0a5b | Realtek... | RTS525A PCI Express Card ... | 4     | rtsx_pci   | 062C3B976F |
| 10ec:525a | 103c:82c1 | Realtek... | RTS525A PCI Express Card ... | 4     | rtsx_pci   | CF06BA276E |
| 10ec:525a | 103c:8518 | Realtek... | RTS525A PCI Express Card ... | 4     | rtsx_pci   | 64C5568456 |
| 10ec:525a | 103c:863e | Realtek... | RTS525A PCI Express Card ... | 4     | rtsx_pci   | B47C4EF32E |
| 10ec:5227 | 103c:804e | Realtek... | RTS5227 PCI Express Card ... | 3     | rtsx_pci   | B4E75E63FB |
| 10ec:5227 | 103c:804f | Realtek... | RTS5227 PCI Express Card ... | 3     | rtsx_pci   | 45BA0657F1 |
| 10ec:522a | 103c:8251 | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | DBD6D18C03 |
| 10ec:522a | 103c:82b7 | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | 3B8F11D2DB |
| 10ec:522a | 103c:8310 | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | D7D0DE8CF4 |
| 10ec:522a | 103c:850d | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | 987181B525 |
| 10ec:522a | 17aa:2294 | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | 3C03CE796F |
| 10ec:522a | 17aa:3813 | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | 998884BE70 |
| 10ec:522a | 17aa:3818 | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | 5B06944051 |
| 10ec:525a | 103c:83ba | Realtek... | RTS525A PCI Express Card ... | 3     | rtsx_pci   | FB88A217E9 |
| 10ec:525a | 103c:844f | Realtek... | RTS525A PCI Express Card ... | 3     | rtsx_pci   | 2668A6580A |
| 10ec:525a | 103c:86e5 | Realtek... | RTS525A PCI Express Card ... | 3     | rtsx_pci   | 54DDD1BAEA |
| 10ec:525a | 103c:8811 | Realtek... | RTS525A PCI Express Card ... | 3     | rtsx_pci   | 5E31F081A4 |
| 10ec:5229 | 103c:8074 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 71479C34B4 |
| 10ec:5229 | 103c:81a2 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 35DC79725B |
| 10ec:5229 | 10ec:5229 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | B227E694F7 |
| 10ec:5229 | 17aa:3801 | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 04E375292D |
| 10ec:522a | 103c:8143 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 03065735FF |
| 10ec:522a | 103c:81ac | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 235D55372B |
| 10ec:522a | 103c:8311 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 514D46C27F |
| 10ec:522a | 103c:8314 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 5CF089CFA1 |
| 10ec:522a | 103c:83c9 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 8BF489A0CB |
| 10ec:522a | 103c:85e6 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 0A7C046DCE |
| 10ec:522a | 103c:8824 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | DDC302E8F0 |
| 10ec:522a | 103c:8826 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | B0E2DE6BBE |
| 10ec:522a | 17aa:22ad | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 8E3E2A94C3 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a0e0 | 17aa:5089 | Intel      | Tiger Lake-LP Management ... | 59    | mei_me     | 1EC4861E97 |
| 8086:9d3a | 17aa:383e | Intel      | Sunrise Point-LP CSME HEC... | 44    | mei_me     | A2717638BE |
| 8086:319a | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 38    | mei_me     | 4DBC03E904 |
| 8086:02c7 | 17aa:3801 | Intel      | Comet Lake PCH-LP LPSS: U... | 33    | intel_lpss | 6F6E5DAF18 |
| 8086:02e0 | 17aa:3803 | Intel      | Comet Lake Management Eng... | 33    | mei_me     | 6F6E5DAF18 |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 32    | mei_me     | AA88177E76 |
| 8086:9d3a | 103c:83b9 | Intel      | Sunrise Point-LP CSME HEC... | 26    | mei_me     | BBB2DB43B4 |
| 8086:34e0 | 17aa:3801 | Intel      | Ice Lake-LP Management En... | 25    | mei_me     | 740EA7B2E9 |
| 8086:9de0 | 103c:8514 | Intel      | Cannon Point-LP MEI Contr... | 25    | mei_me     | 211EF30EF4 |
| 8086:9de0 | 17aa:3805 | Intel      | Cannon Point-LP MEI Contr... | 25    | mei_me     | 4C9743CDD1 |
| 8086:34e0 | 1028:08b0 | Intel      | Ice Lake-LP Management En... | 23    | mei_me     | 138EC046F1 |
| 8086:9d3a | 17aa:2238 | Intel      | Sunrise Point-LP CSME HEC... | 22    | mei_me     | DD105BA06B |
| 8086:9d3a | 17aa:3801 | Intel      | Sunrise Point-LP CSME HEC... | 21    | mei_me     | 72617E5DD9 |
| 8086:9d3a | 17aa:3868 | Intel      | Sunrise Point-LP CSME HEC... | 20    | mei_me     | A52209C9F2 |
| 8086:34e0 | 17aa:383a | Intel      | Ice Lake-LP Management En... | 18    | mei_me     | D1DD92D46E |
| 8086:02e0 | 17aa:3806 | Intel      | Comet Lake Management Eng... | 17    | mei_me     | 527CC99B36 |
| 8086:9d3a | 103c:827d | Intel      | Sunrise Point-LP CSME HEC... | 17    | mei_me     | 95D389BFE5 |
| 8086:9de0 | 17aa:2292 | Intel      | Cannon Point-LP MEI Contr... | 17    | mei_me     | D99F5CBFD2 |
| 8086:9d3a | 17aa:3811 | Intel      | Sunrise Point-LP CSME HEC... | 16    | mei_me     | 350D402895 |
| 8086:a0a8 | 17aa:381f | Intel      | Tiger Lake-LP Serial IO U... | 16    | intel_lpss | 7851B07853 |
| 8086:a0e0 | 1028:0a05 | Intel      | Tiger Lake-LP Management ... | 16    | mei_me     | 928665D302 |
| 8086:a0e0 | 17aa:383b | Intel      | Tiger Lake-LP Management ... | 16    | mei_me     | 7851B07853 |
| 8086:9d3a | 1028:077a | Intel      | Sunrise Point-LP CSME HEC... | 15    | mei_me     | 8F7ADB6CD3 |
| 8086:9d3a | 103c:830f | Intel      | Sunrise Point-LP CSME HEC... | 15    | mei_me     | 3286ED83B9 |
| 8086:9d3a | 103c:8486 | Intel      | Sunrise Point-LP CSME HEC... | 15    | mei_me     | 7E241B1F69 |
| 8086:9d3a | 17aa:3824 | Intel      | Sunrise Point-LP CSME HEC... | 15    | mei_me     | AED568D94C |
| 8086:a13a | 17aa:3809 | Intel      | 100 Series/C230 Series Ch... | 15    | mei_me     | C362C8CAFD |
| 8086:9d3a | 17aa:224e | Intel      | Sunrise Point-LP CSME HEC... | 14    | mei_me     | 3C24D27D51 |
| 8086:9d3a | 17aa:2259 | Intel      | Sunrise Point-LP CSME HEC... | 14    | mei_me     | 36DBFEF2B7 |
| 8086:9d3a | 17aa:3805 | Intel      | Sunrise Point-LP CSME HEC... | 14    | mei_me     | 82ACEB2458 |
| 8086:9d3a | 17aa:383d | Intel      | Sunrise Point-LP CSME HEC... | 14    | mei_me     | 9A20859E26 |
| 8086:a0e0 | 1028:09ff | Intel      | Tiger Lake-LP Management ... | 14    | mei_me     | 5B10037DA5 |
| 8086:02e0 | 17aa:5078 | Intel      | Comet Lake Management Eng... | 13    | mei_me     | 49DBAD6FDB |
| 8086:9d3a | 103c:827e | Intel      | Sunrise Point-LP CSME HEC... | 13    | mei_me     | CCA3E863F7 |
| 8086:a13a | 103c:83bb | Intel      | 100 Series/C230 Series Ch... | 13    | mei_me     | BA09E3B76F |
| 8086:02e0 | 103c:866e | Intel      | Comet Lake Management Eng... | 12    | mei_me     | 572D5CD292 |
| 8086:9d3a | 17aa:380d | Intel      | Sunrise Point-LP CSME HEC... | 12    | mei_me     | 5154E96ABE |
| 8086:a0e0 | 1028:09de | Intel      | Tiger Lake-LP Management ... | 12    | mei_me     | 224CE9A44D |
| 8086:a0e0 | 17aa:382c | Intel      | Tiger Lake-LP Management ... | 12    | mei_me     | 00AC329183 |
| 8086:a13a | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 12    | mei_me     | 27D7C254CC |
| 8086:9d3a | 103c:8488 | Intel      | Sunrise Point-LP CSME HEC... | 11    | mei_me     | 3AF23C8E87 |
| 8086:9d3a | 1043:1ab0 | Intel      | Sunrise Point-LP CSME HEC... | 11    | mei_me     | 06E7A51D6A |
| 8086:9d3a | 17aa:3860 | Intel      | Sunrise Point-LP CSME HEC... | 11    | mei_me     | F0DA92A413 |
| 8086:9d3a | 17aa:506d | Intel      | Sunrise Point-LP CSME HEC... | 11    | mei_me     | 99C878CD5E |
| 8086:9d3a | 103c:8438 | Intel      | Sunrise Point-LP CSME HEC... | 10    | mei_me     | AF74E3A1EA |
| 8086:a0e0 | 1028:09dd | Intel      | Tiger Lake-LP Management ... | 10    | mei_me     | 044E6AFDF4 |
| 8086:02e0 | 103c:86b1 | Intel      | Comet Lake Management Eng... | 9     | mei_me     | F3B0D882C2 |
| 8086:02e0 | 103c:86b2 | Intel      | Comet Lake Management Eng... | 9     | mei_me     | B054E02856 |
| 8086:34e0 | 103c:86f9 | Intel      | Ice Lake-LP Management En... | 9     | mei_me     | 4967676215 |
| 8086:9d3a | 103c:80d1 | Intel      | Sunrise Point-LP CSME HEC... | 9     | mei_me     | 629D516666 |
| 8086:9d3a | 103c:81a1 | Intel      | Sunrise Point-LP CSME HEC... | 9     | mei_me     | B37CBA5DF4 |
| 8086:9d3a | 17aa:2237 | Intel      | Sunrise Point-LP CSME HEC... | 9     | mei_me     | 24D1BD52CC |
| 8086:9d3a | 17aa:3846 | Intel      | Sunrise Point-LP CSME HEC... | 9     | mei_me     | E2C078E281 |
| 8086:9de0 | 1028:0894 | Intel      | Cannon Point-LP MEI Contr... | 9     | mei_me     | B07A0CF706 |
| 8086:9de0 | 103c:861f | Intel      | Cannon Point-LP MEI Contr... | 9     | mei_me     | 48CABEDB1E |
| 8086:02e0 | 1028:095d | Intel      | Comet Lake Management Eng... | 8     | mei_me     | E85575B823 |
| 8086:02e0 | 103c:863f | Intel      | Comet Lake Management Eng... | 8     | mei_me     | 2A2CFDB7D4 |
| 8086:319a |           | Intel      | Celeron/Pentium Silver Pr... | 8     | mei_me     | 17E78AF479 |
| 8086:9d3a | 103c:8484 | Intel      | Sunrise Point-LP CSME HEC... | 8     | mei_me     | F3D65BB221 |
| 8086:9d3a | 17aa:506c | Intel      | Sunrise Point-LP CSME HEC... | 8     | mei_me     | B39CD022D3 |
| 8086:9da8 | 1043:19d1 | Intel      | Cannon Point-LP Serial IO... | 8     | intel_lpss | DBBD7A332E |
| 8086:9de0 | 103c:85c4 | Intel      | Cannon Point-LP MEI Contr... | 8     | mei_me     | 7D9588F740 |
| 8086:9de0 | 1043:19d1 | Intel      | Cannon Point-LP MEI Contr... | 8     | mei_me     | DBBD7A332E |
| 8086:9de0 | 17aa:5077 | Intel      | Cannon Point-LP MEI Contr... | 8     | mei_me     | B9971B685A |
| 8086:02e0 | 1028:0950 | Intel      | Comet Lake Management Eng... | 7     | mei_me     | 6E2B3B5A7E |
| 8086:02e0 | 1028:09cd | Intel      | Comet Lake Management Eng... | 7     | mei_me     | 20FA4B73D7 |
| 8086:02e0 | 17aa:3809 | Intel      | Comet Lake Management Eng... | 7     | mei_me     | 611C3C0C19 |
| 8086:34e0 | 1025:141f | Intel      | Ice Lake-LP Management En... | 7     | mei_me     | 059B59E828 |
| 8086:9cba | 103c:802d | Intel      | Wildcat Point-LP MEI Cont... | 7     | mei_me     | 0B68C3F5C3 |
| 8086:9d3a | 103c:81ad | Intel      | Sunrise Point-LP CSME HEC... | 7     | mei_me     | A6FF75E220 |
| 8086:9d3a | 1043:14f0 | Intel      | Sunrise Point-LP CSME HEC... | 7     | mei_me     | E682AFBEDE |
| 8086:9d3a | 1043:1b00 | Intel      | Sunrise Point-LP CSME HEC... | 7     | mei_me     | 9FF68B8AD1 |
| 8086:9d3a | 1043:1dc0 | Intel      | Sunrise Point-LP CSME HEC... | 7     | mei_me     | 26CE6DC2B2 |
| 8086:9d3a | 17aa:5061 | Intel      | Sunrise Point-LP CSME HEC... | 7     | mei_me     | 16AC72B8EA |
| 8086:9de0 | 103c:857f | Intel      | Cannon Point-LP MEI Contr... | 7     | mei_me     | 465B51ACD4 |
| 8086:a0e0 | 1028:09df | Intel      | Tiger Lake-LP Management ... | 7     | mei_me     | 69D2B432F7 |
| 8086:a0e0 | 103c:8709 | Intel      | Tiger Lake-LP Management ... | 7     | mei_me     | 444E13B5ED |
| 8086:a0e0 | 103c:87f4 | Intel      | Tiger Lake-LP Management ... | 7     | mei_me     | 6461BFC243 |
| 8086:a0e0 | 17aa:3801 | Intel      | Tiger Lake-LP Management ... | 7     | mei_me     | 5B06944051 |
| 8086:a360 | 17aa:382c | Intel      | Cannon Lake PCH HECI Cont... | 7     | mei_me     | 4EEE4B94CB |
| 8086:02e0 | 17aa:2292 | Intel      | Comet Lake Management Eng... | 6     | mei_me     | 8F10E30326 |
| 8086:02e0 | 17aa:22be | Intel      | Comet Lake Management Eng... | 6     | mei_me     | 65033505B7 |
| 8086:5a9a | 17aa:3803 | Intel      | Celeron N3350/Pentium N42... | 6     | mei_me     | 4FD337BCA7 |
| 8086:5a9c | 17aa:3803 | Intel      | Communication controller     | 6     |            | 4FD337BCA7 |
| 8086:5a9e | 17aa:3803 | Intel      | Communication controller     | 6     |            | 4FD337BCA7 |
| 8086:9d3a | 1025:1176 | Intel      | Sunrise Point-LP CSME HEC... | 6     | mei_me     | 566FA6B1D5 |
| 8086:9d3a | 1028:07eb | Intel      | Sunrise Point-LP CSME HEC... | 6     | mei_me     | 765C6838B2 |
| 8086:9d3a | 103c:8313 | Intel      | Sunrise Point-LP CSME HEC... | 6     | mei_me     | 5D0F309968 |
| 8086:9d3a | 103c:8483 | Intel      | Sunrise Point-LP CSME HEC... | 6     | mei_me     | C48CB1FCCF |
| 8086:9d3a | 1043:1c90 | Intel      | Sunrise Point-LP CSME HEC... | 6     | mei_me     | AED32F7A4D |
| 8086:9d3a | 17aa:3861 | Intel      | Sunrise Point-LP CSME HEC... | 6     | mei_me     | 570666D7D6 |
| 8086:9de0 | 1028:089e | Intel      | Cannon Point-LP MEI Contr... | 6     | mei_me     | C52711AB47 |
| 8086:9de0 | 1028:08e2 | Intel      | Cannon Point-LP MEI Contr... | 6     | mei_me     | ADF32CA36B |
| 8086:a0e0 | 103c:87f7 | Intel      | Tiger Lake-LP Management ... | 6     | mei_me     | E1D0678746 |
| 8086:a0e0 | 17aa:3f86 | Intel      | Tiger Lake-LP Management ... | 6     | mei_me     | 14109EDFC9 |
| 8086:02e0 | 1028:0960 | Intel      | Comet Lake Management Eng... | 5     | mei_me     | 40A7A1942F |
| 8086:02e0 | 17aa:22ad | Intel      | Comet Lake Management Eng... | 5     | mei_me     | 50C28ABBA1 |
| 8086:319a | 1025:1316 | Intel      | Celeron/Pentium Silver Pr... | 5     | mei_me     | BAB6686973 |
| 8086:34e0 | 103c:86fa | Intel      | Ice Lake-LP Management En... | 5     | mei_me     | 635BBB6F75 |
| 8086:9d3a | 103c:81a9 | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | 0BB3F77C75 |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15df | 1022:15df | AMD        | Family 17h (Models 10h-1f... | 99    | ccp        | 65A49B7280 |
| 1022:15df | 103c:876e | AMD        | Family 17h (Models 10h-1f... | 38    | ccp        | 28B152BB19 |
| 1022:15df | 103c:876f | AMD        | Family 17h (Models 10h-1f... | 34    | ccp        | 5F67B298AB |
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 32    | mei_txe    | 74FE90715F |
| 1022:15df | 103c:85dd | AMD        | Family 17h (Models 10h-1f... | 23    | ccp        | C4EA79E269 |
| 1022:15df | 17aa:3804 | AMD        | Family 17h (Models 10h-1f... | 21    | ccp        | 6AF7A7F851 |
| 1022:15df | 103c:85de | AMD        | Family 17h (Models 10h-1f... | 19    | ccp        | 3ADCB9ECF9 |
| 1022:15df | 103c:83c6 | AMD        | Family 17h (Models 10h-1f... | 16    | ccp        | 5174E188C0 |
| 1022:15df | 103c:8497 | AMD        | Family 17h (Models 10h-1f... | 16    | ccp        | 0DFE108C69 |
| 1022:15df | 103c:8496 | AMD        | Family 17h (Models 10h-1f... | 15    | ccp        | DFB9789AF2 |
| 8086:2298 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 10    | mei_txe    | AB13E942F9 |
| 1022:15df | 103c:888a | AMD        | Family 17h (Models 10h-1f... | 9     | ccp        | ED20604458 |
| 1022:15df | 1028:09e3 | AMD        | Family 17h (Models 10h-1f... | 8     | ccp        | 58C4A6AD98 |
| 8086:0f18 | 103c:802b | Intel      | Atom Processor Z36xxx/Z37... | 7     | mei_txe    | 4E86625634 |
| 1022:1578 | 103c:81aa | AMD        | Carrizo Platform Security... | 5     |            | 633D386331 |
| 1022:15df | 1028:0a8c | AMD        | Family 17h (Models 10h-1f... | 5     | ccp        | 58E1FA994C |
| 1022:15df | 103c:87a9 | AMD        | Family 17h (Models 10h-1f... | 5     | ccp        | 96C4D24CAB |
| 1022:15df | 17aa:3824 | AMD        | Family 17h (Models 10h-1f... | 5     | ccp        | C977BD2115 |
| 1022:1578 | 17aa:3802 | AMD        | Carrizo Platform Security... | 4     |            | 6931FAE5CC |
| 1022:15df | 1028:090c | AMD        | Family 17h (Models 10h-1f... | 3     | ccp        | B6C573F5AA |
| 1022:1578 | 103c:8311 | AMD        | Carrizo Platform Security... | 2     |            | 514D46C27F |
| 1022:15df | 1025:1506 | AMD        | Family 17h (Models 10h-1f... | 2     | ccp        | D000862005 |
| 8086:2298 | 103c:8074 | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | 71479C34B4 |
| 8086:2298 | 103c:81a2 | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | 35DC79725B |
| 8086:2298 | 17aa:3801 | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | 04E375292D |
| 1022:1578 | 103c:81ab | AMD        | Carrizo Platform Security... | 1     |            | D98A9E0C48 |
| 1022:15df | 103c:8535 | AMD        | Family 17h (Models 10h-1f... | 1     | ccp        | 31CBD77D73 |
| 1022:15df | 103c:88c2 | AMD        | Family 17h (Models 10h-1f... | 1     | ccp        | 2552FC1A99 |
| 1022:15df | 17aa:3839 | AMD        | Family 17h (Models 10h-1f... | 1     | ccp        | B1BB1E8325 |
| 1022:15df | 17aa:383b | AMD        | Family 17h (Models 10h-1f... | 1     | ccp        | E7AB53C038 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:1636 | 17aa:3f1a | AMD        | Renoir                       | 64    | amdgpu     | F07B9B77F5 |
| 8086:9a49 | 17aa:5089 | Intel      | TigerLake-LP GT2 [Iris Xe... | 59    | i915       | 1EC4861E97 |
| 1002:1636 | 103c:876e | AMD        | Renoir                       | 38    | amdgpu     | 28B152BB19 |
| 1002:1636 | 103c:876f | AMD        | Renoir                       | 34    | amdgpu     | 5F67B298AB |
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 32    | i915       | 74FE90715F |
| 8086:9b41 | 17aa:3f12 | Intel      | CometLake-U GT2 [UHD Grap... | 30    | i915       | 6F6E5DAF18 |
| 8086:5917 | 103c:83b9 | Intel      | UHD Graphics 620             | 26    | i915       | BBB2DB43B4 |
| 8086:3ea0 | 103c:8514 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 25    | i915       | 211EF30EF4 |
| 1002:15d8 | 103c:85dd | AMD        | Picasso                      | 23    | amdgpu     | C4EA79E269 |
| 8086:3185 | 8086:2212 | Intel      | GeminiLake [UHD Graphics ... | 23    | i915       | E4FB415516 |
| 8086:1916 | 17aa:2238 | Intel      | Skylake GT2 [HD Graphics ... | 22    | i915       | DD105BA06B |
| 8086:8a52 | 1028:08b0 | Intel      | Iris Plus Graphics G7        | 22    | i915       | 138EC046F1 |
| 1002:15dd | 17aa:39ff | AMD        | Raven Ridge [Radeon Vega ... | 21    | amdgpu     | 6AF7A7F851 |
| 8086:5917 | 17aa:3803 | Intel      | UHD Graphics 620             | 20    | i915       | A52209C9F2 |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics 500              | 20    | i915       | 4BF1EEBDE1 |
| 1002:15d8 | 103c:85de | AMD        | Picasso                      | 19    | amdgpu     | 3ADCB9ECF9 |
| 8086:3ea0 | 17aa:39f4 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 18    | i915       | 4C9743CDD1 |
| 8086:5916 | 103c:827d | Intel      | HD Graphics 620              | 18    | i915       | 95D389BFE5 |
| 8086:8a52 | 17aa:3801 | Intel      | Iris Plus Graphics G7        | 18    | i915       | D1DD92D46E |
| 8086:3ea0 | 17aa:2292 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 17    | i915       | D99F5CBFD2 |
| 1002:15dd | 103c:83c6 | AMD        | Raven Ridge [Radeon Vega ... | 16    | amdgpu     | 5174E188C0 |
| 1002:15dd | 103c:8497 | AMD        | Raven Ridge [Radeon Vega ... | 16    | amdgpu     | 0DFE108C69 |
| 8086:9a49 | 17aa:3f1a | Intel      | TigerLake-LP GT2 [Iris Xe... | 16    | i915       | 7851B07853 |
| 1002:15dd | 103c:8496 | AMD        | Raven Ridge [Radeon Vega ... | 15    | amdgpu     | DFB9789AF2 |
| 1002:1636 | 103c:8735 | AMD        | Renoir                       | 15    | amdgpu     | 4EE6C35B8F |
| 8086:5916 | 103c:830f | Intel      | HD Graphics 620              | 15    | i915       | 3286ED83B9 |
| 8086:5917 | 103c:8486 | Intel      | UHD Graphics 620             | 15    | i915       | 7E241B1F69 |
| 8086:8a56 | 17aa:380d | Intel      | Iris Plus Graphics G1 (Ic... | 15    | i915       | E5251674C0 |
| 8086:9a49 | 1028:0a05 | Intel      | TigerLake-LP GT2 [Iris Xe... | 15    | i915       | 928665D302 |
| 8086:9b41 | 17aa:3806 | Intel      | CometLake-U GT2 [UHD Grap... | 15    | i915       | 527CC99B36 |
| 8086:5916 | 17aa:224e | Intel      | HD Graphics 620              | 14    | i915       | 3C24D27D51 |
| 8086:5916 | 17aa:3801 | Intel      | HD Graphics 620              | 14    | i915       | 82ACEB2458 |
| 8086:5916 | 17aa:3987 | Intel      | HD Graphics 620              | 14    | i915       | AD4AB3F1B6 |
| 8086:5917 | 17aa:2259 | Intel      | UHD Graphics 620             | 14    | i915       | 36DBFEF2B7 |
| 8086:9a49 | 1028:09ff | Intel      | TigerLake-LP GT2 [Iris Xe... | 14    | i915       | 5B10037DA5 |
| 1002:694e | 103c:83bb | AMD        | Polaris 22 XL [Radeon RX ... | 13    | amdgpu     | BA09E3B76F |
| 10de:1c8d | 17aa:39cb | Nvidia     | GP107M [GeForce GTX 1050 ... | 13    | nvidia     | D43D3C013C |
| 8086:5916 | 103c:827e | Intel      | HD Graphics 620              | 13    | i915       | CCA3E863F7 |
| 8086:5917 | 17aa:398e | Intel      | UHD Graphics 620             | 13    | i915       | 72617E5DD9 |
| 8086:591b | 103c:83bb | Intel      | HD Graphics 630              | 13    | i915       | BA09E3B76F |
| 8086:591b | 17aa:39cb | Intel      | HD Graphics 630              | 13    | i915       | D43D3C013C |
| 8086:9b41 | 17aa:5078 | Intel      | CometLake-U GT2 [UHD Grap... | 13    | i915       | 49DBAD6FDB |
| 1002:694e | 1028:080d | ATI Tec... | Polaris 22 XL [Radeon RX ... | 12    | amdgpu     | 27D7C254CC |
| 8086:5917 | 17aa:39ce | Intel      | UHD Graphics 620             | 12    | i915       | A2717638BE |
| 8086:591b | 1028:080d | Intel      | HD Graphics 630              | 12    | i915       | 27D7C254CC |
| 8086:9a49 | 1028:09de | Intel      | TigerLake-LP GT2 [Iris Xe... | 12    | i915       | 224CE9A44D |
| 8086:9a49 | 17aa:3803 | Intel      | TigerLake-LP GT2 [Iris Xe... | 12    | i915       | 00AC329183 |
| 8086:9b41 | 103c:866e | Intel      | CometLake-U GT2 [UHD Grap... | 12    | i915       | 572D5CD292 |
| 8086:5917 | 103c:8488 | Intel      | UHD Graphics 620             | 11    | i915       | 3AF23C8E87 |
| 8086:5917 | 17aa:506d | Intel      | UHD Graphics 620             | 11    | i915       | 99C878CD5E |
| 8086:591e | 1028:077a | Intel      | HD Graphics 615              | 11    | i915       | 8F7ADB6CD3 |
| 8086:22b1 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 10    | i915       | AB13E942F9 |
| 8086:5917 | 103c:8438 | Intel      | UHD Graphics 620             | 10    | i915       | AF74E3A1EA |
| 8086:5917 | 1043:1ab0 | Intel      | UHD Graphics 620             | 10    | i915       | 06E7A51D6A |
| 8086:8a52 | 17aa:380d | Intel      | Iris Plus Graphics G7        | 10    | i915       | 740EA7B2E9 |
| 8086:9a49 | 1028:09dd | Intel      | TigerLake-LP GT2 [Iris Xe... | 10    | i915       | 044E6AFDF4 |
| 1002:164c | 103c:888a | AMD        | Lucienne                     | 9     | amdgpu     | ED20604458 |
| 10de:174d | 17aa:39ce | Nvidia     | GM108M [GeForce MX130]       | 9     | nvidia     | A2717638BE |
| 10de:1d13 | 103c:86b2 | Nvidia     | GP108M [GeForce MX250]       | 9     | nvidia     | B054E02856 |
| 10de:1d16 | 17aa:3801 | Nvidia     | GP108M [GeForce MX330]       | 9     | nvidia     | 740EA7B2E9 |
| 8086:1916 | 103c:80d1 | Intel      | Skylake GT2 [HD Graphics ... | 9     | i915       | 629D516666 |
| 8086:1916 | 17aa:2237 | Intel      | Skylake GT2 [HD Graphics ... | 9     | i915       | 24D1BD52CC |
| 8086:3ea0 | 1028:0894 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 9     | i915       | B07A0CF706 |
| 8086:3ea0 | 103c:861f | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 9     | i915       | 48CABEDB1E |
| 8086:5916 | 17aa:39f3 | Intel      | HD Graphics 620              | 9     | i915       | 15C0F31B91 |
| 8086:5917 | 17aa:3802 | Intel      | UHD Graphics 620             | 9     | i915       | E2C078E281 |
| 8086:8a52 | 103c:86f9 | Intel      | Iris Plus Graphics G7        | 9     | i915       | 4967676215 |
| 8086:9b41 | 103c:86b1 | Intel      | CometLake-U GT2 [UHD Grap... | 9     | i915       | F3B0D882C2 |
| 8086:9b41 | 103c:86b2 | Intel      | CometLake-U GT2 [UHD Grap... | 9     | i915       | B054E02856 |
| 1002:1636 | 1028:09e3 | AMD        | Renoir                       | 8     | amdgpu     | 58C4A6AD98 |
| 10de:134d | 17aa:39ce | Nvidia     | GM108M [GeForce 940MX]       | 8     | nvidia     | 4C8282BB42 |
| 10de:1d10 | 103c:8484 | Nvidia     | GP108M [GeForce MX150]       | 8     | nvidia     | F3D65BB221 |
| 10de:1d13 | 103c:863f | Nvidia     | GP108M [GeForce MX250]       | 8     | nvidia     | 2A2CFDB7D4 |
| 8086:3ea0 | 103c:85c4 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 8     | i915       | 7D9588F740 |
| 8086:3ea0 | 17aa:5077 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 8     | i915       | B9971B685A |
| 8086:5917 | 103c:8484 | Intel      | UHD Graphics 620             | 8     | i915       | F3D65BB221 |
| 8086:5917 | 17aa:39fb | Intel      | UHD Graphics 620             | 8     | i915       | FC665EFEDD |
| 8086:5917 | 17aa:39fd | Intel      | UHD Graphics 620             | 8     | i915       | 9A20859E26 |
| 8086:5917 | 17aa:506c | Intel      | UHD Graphics 620             | 8     | i915       | B39CD022D3 |
| 8086:9b41 | 1028:095d | Intel      | CometLake-U GT2 [UHD Grap... | 8     | i915       | E85575B823 |
| 8086:9b41 | 103c:863f | Intel      | CometLake-U GT2 [UHD Grap... | 8     | i915       | 2A2CFDB7D4 |
| 1002:15d8 | 1043:1921 | AMD        | Picasso                      | 7     | amdgpu     | 87C26A2591 |
| 8086:0f31 | 103c:802b | Intel      | Atom Processor Z36xxx/Z37... | 7     | i915       | 4E86625634 |
| 8086:1616 | 103c:802d | Intel      | HD Graphics 5500             | 7     | i915       | 0B68C3F5C3 |
| 8086:1916 | 103c:81a1 | Intel      | Skylake GT2 [HD Graphics ... | 7     | i915       | B37CBA5DF4 |
| 8086:3e9b | 17aa:3f1a | Intel      | CoffeeLake-H GT2 [UHD Gra... | 7     | i915       | 4EEE4B94CB |
| 8086:3ea0 | 103c:857f | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 7     | i915       | 465B51ACD4 |
| 8086:5916 | 103c:81ad | Intel      | HD Graphics 620              | 7     | i915       | A6FF75E220 |
| 8086:5916 | 1043:14f0 | Intel      | HD Graphics 620              | 7     | i915       | E682AFBEDE |
| 8086:5916 | 17aa:5061 | Intel      | HD Graphics 620              | 7     | i915       | 16AC72B8EA |
| 8086:5917 | 1043:1dc0 | Intel      | UHD Graphics 620             | 7     | i915       | 26CE6DC2B2 |
| 8086:9a49 | 1028:09df | Intel      | TigerLake-LP GT2 [Iris Xe... | 7     | i915       | 69D2B432F7 |
| 8086:9a49 | 103c:8709 | Intel      | TigerLake-LP GT2 [Iris Xe... | 7     | i915       | 444E13B5ED |
| 8086:9b41 | 1028:0950 | Intel      | CometLake-U GT2 [UHD Grap... | 7     | i915       | 6E2B3B5A7E |
| 8086:9b41 | 1028:09cd | Intel      | CometLake-U GT2 [UHD Grap... | 7     | i915       | 20FA4B73D7 |
| 1002:164c | 17aa:3f96 | AMD        | Lucienne                     | 6     | amdgpu     | 65A49B7280 |
| 10de:134d | 17aa:39f4 | Nvidia     | GM108M [GeForce 940MX]       | 6     | nvidia     | AED568D94C |
| 10de:174d | 17aa:398c | Nvidia     | GM108M [GeForce MX130]       | 6     | nouveau    | EAA1882521 |
| 10de:1c94 | 1028:09df | Nvidia     | GP107M [GeForce MX350]       | 6     | nvidia     | 69D2B432F7 |
| 10de:1f91 | 17aa:3f1a | Nvidia     | TU117M [GeForce GTX 1650 ... | 6     | nouveau    | 5C409FA78E |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1631 | 1022:1631 | AMD        | Renoir/Cezanne IOMMU         | 91    |            | 65A49B7280 |
| 1022:1631 | 103c:876e | AMD        | Renoir/Cezanne IOMMU         | 38    |            | 28B152BB19 |
| 1022:1631 | 103c:876f | AMD        | Renoir/Cezanne IOMMU         | 34    |            | 5F67B298AB |
| 1022:15d1 | 103c:85dd | AMD        | Raven/Raven2 IOMMU           | 23    |            | C4EA79E269 |
| 1022:15d1 | 17aa:3809 | AMD        | Raven/Raven2 IOMMU           | 21    |            | 6AF7A7F851 |
| 1022:15d1 | 103c:85de | AMD        | Raven/Raven2 IOMMU           | 19    |            | 3ADCB9ECF9 |
| 1022:15d1 | 103c:83c6 | AMD        | Raven/Raven2 IOMMU           | 16    |            | 5174E188C0 |
| 1022:15d1 | 103c:8497 | AMD        | Raven/Raven2 IOMMU           | 16    |            | 0DFE108C69 |
| 1022:15d1 | 103c:8496 | AMD        | Raven/Raven2 IOMMU           | 15    |            | DFB9789AF2 |
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 11    |            | BCF877AA15 |
| 1022:1631 | 103c:888a | AMD        | Renoir/Cezanne IOMMU         | 9     |            | ED20604458 |
| 1022:1631 | 1028:09e3 | AMD        | Renoir/Cezanne IOMMU         | 8     |            | 58C4A6AD98 |
| 1022:1577 | 103c:81aa | AMD        | Family 15h (Models 60h-6f... | 5     |            | 633D386331 |
| 1022:1631 | 1028:0a8c | AMD        | Renoir/Cezanne IOMMU         | 5     |            | 58E1FA994C |
| 1022:1631 | 103c:87a9 | AMD        | Renoir/Cezanne IOMMU         | 5     |            | 96C4D24CAB |
| 1022:1631 | 17aa:3807 | AMD        | Renoir/Cezanne IOMMU         | 5     |            | C977BD2115 |
| 1022:1577 | 17aa:3806 | AMD        | Family 15h (Models 60h-6f... | 4     |            | 6931FAE5CC |
| 1022:1577 | 103c:8311 | AMD        | Family 15h (Models 60h-6f... | 2     |            | 514D46C27F |
| 1022:15d1 | 1025:1506 | AMD        | Raven/Raven2 IOMMU           | 2     |            | D000862005 |
| 1022:1577 | 103c:81ab | AMD        | Family 15h (Models 60h-6f... | 1     |            | D98A9E0C48 |
| 1022:15d1 | 103c:8535 | AMD        | Raven/Raven2 IOMMU           | 1     |            | 31CBD77D73 |
| 1022:1631 | 103c:88c2 | AMD        | Renoir/Cezanne IOMMU         | 1     |            | 2552FC1A99 |
| 1022:1631 | 17aa:3820 | AMD        | Renoir/Cezanne IOMMU         | 1     |            | B1BB1E8325 |
| 1022:1631 | 17aa:3822 | AMD        | Renoir/Cezanne IOMMU         | 1     |            | E7AB53C038 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a0ef | 17aa:5089 | Intel      | Tiger Lake-LP Shared SRAM    | 59    |            | 1EC4861E97 |
| 8086:9d21 | 17aa:383d | Intel      | Sunrise Point-LP PMC         | 44    |            | A2717638BE |
| 8086:02ef | 17aa:3805 | Intel      | Comet Lake PCH-LP Shared ... | 33    |            | 6F6E5DAF18 |
| 8086:9def | 8086:9def | Intel      | Cannon Point-LP Shared SRAM  | 33    |            | 4C9743CDD1 |
| 8086:9def |           | Intel      | Cannon Point-LP Shared SRAM  | 29    |            | 3C03CE796F |
| 8086:34ef |           | Intel      | Ice Lake-LP DRAM Controller  | 27    |            | 138EC046F1 |
| 8086:9d21 | 103c:83b9 | Intel      | Sunrise Point-LP PMC         | 26    |            | BBB2DB43B4 |
| 8086:34ef | 17aa:3803 | Intel      | Ice Lake-LP DRAM Controller  | 25    |            | 740EA7B2E9 |
| 8086:9def | 103c:8514 | Intel      | Cannon Point-LP Shared SRAM  | 25    |            | 211EF30EF4 |
| 8086:9d21 | 17aa:2238 | Intel      | Sunrise Point-LP PMC         | 22    |            | DD105BA06B |
| 8086:9d21 | 17aa:3866 | Intel      | Sunrise Point-LP PMC         | 21    |            | 72617E5DD9 |
| 8086:9d21 | 17aa:386c | Intel      | Sunrise Point-LP PMC         | 20    |            | A52209C9F2 |
| 8086:34ef | 17aa:3846 | Intel      | Ice Lake-LP DRAM Controller  | 18    |            | D1DD92D46E |
| 8086:9d21 | 103c:827d | Intel      | Sunrise Point-LP PMC         | 18    |            | 95D389BFE5 |
| 8086:9d21 | 17aa:3811 | Intel      | Sunrise Point-LP PMC         | 16    |            | 350D402895 |
| 8086:9def | 8086:7270 | Intel      | Cannon Point-LP Shared SRAM  | 16    |            | 71FB7C2C92 |
| 8086:a0ef | 1028:0a05 | Intel      | Tiger Lake-LP Shared SRAM    | 16    |            | 928665D302 |
| 8086:a0ef | 17aa:3847 | Intel      | Tiger Lake-LP Shared SRAM    | 16    |            | 7851B07853 |
| 8086:02ef | 17aa:3806 | Intel      | Comet Lake PCH-LP Shared ... | 15    |            | 527CC99B36 |
| 8086:9d21 | 1028:077a | Intel      | Sunrise Point-LP PMC         | 15    |            | 8F7ADB6CD3 |
| 8086:9d21 | 103c:830f | Intel      | Sunrise Point-LP PMC         | 15    |            | 3286ED83B9 |
| 8086:9d21 | 103c:8486 | Intel      | Sunrise Point-LP PMC         | 15    |            | 7E241B1F69 |
| 8086:9d21 | 17aa:3823 | Intel      | Sunrise Point-LP PMC         | 15    |            | AED568D94C |
| 8086:a121 | 17aa:380f | Intel      | 100 Series/C230 Series Ch... | 15    |            | C362C8CAFD |
| 8086:9d21 | 17aa:224e | Intel      | Sunrise Point-LP PMC         | 14    | intel_p... | 3C24D27D51 |
| 8086:9d21 | 17aa:2259 | Intel      | Sunrise Point-LP PMC         | 14    |            | 36DBFEF2B7 |
| 8086:9d21 | 17aa:3805 | Intel      | Sunrise Point-LP PMC         | 14    |            | 82ACEB2458 |
| 8086:9d21 | 17aa:383f | Intel      | Sunrise Point-LP PMC         | 14    |            | 9A20859E26 |
| 8086:a0ef | 1028:09ff | Intel      | Tiger Lake-LP Shared SRAM    | 14    |            | 5B10037DA5 |
| 8086:02ef | 17aa:5078 | Intel      | Comet Lake PCH-LP Shared ... | 13    |            | 49DBAD6FDB |
| 8086:9d21 | 103c:827e | Intel      | Sunrise Point-LP PMC         | 13    |            | CCA3E863F7 |
| 8086:a121 | 103c:83bb | Intel      | 100 Series/C230 Series Ch... | 13    |            | BA09E3B76F |
| 8086:02ef | 103c:866e | Intel      | Comet Lake PCH-LP Shared ... | 12    |            | 572D5CD292 |
| 8086:9d21 | 17aa:380b | Intel      | Sunrise Point-LP PMC         | 12    |            | 5154E96ABE |
| 8086:a0ef | 1028:09de | Intel      | Tiger Lake-LP Shared SRAM    | 12    |            | 224CE9A44D |
| 8086:a0ef | 17aa:3838 | Intel      | Tiger Lake-LP Shared SRAM    | 12    |            | 00AC329183 |
| 8086:a121 | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 12    |            | 27D7C254CC |
| 8086:9d21 | 103c:8488 | Intel      | Sunrise Point-LP PMC         | 11    |            | 3AF23C8E87 |
| 8086:9d21 | 1043:1ab0 | Intel      | Sunrise Point-LP PMC         | 11    |            | 06E7A51D6A |
| 8086:9d21 | 17aa:3863 | Intel      | Sunrise Point-LP PMC         | 11    |            | F0DA92A413 |
| 8086:9d21 | 17aa:506d | Intel      | Sunrise Point-LP PMC         | 11    |            | 99C878CD5E |
| 8086:9d21 | 103c:8438 | Intel      | Sunrise Point-LP PMC         | 10    |            | AF74E3A1EA |
| 8086:a0ef | 1028:09dd | Intel      | Tiger Lake-LP Shared SRAM    | 10    |            | 044E6AFDF4 |
| 8086:02ef | 103c:86b1 | Intel      | Comet Lake PCH-LP Shared ... | 9     |            | F3B0D882C2 |
| 8086:02ef | 103c:86b2 | Intel      | Comet Lake PCH-LP Shared ... | 9     |            | B054E02856 |
| 8086:34ef | 103c:86f9 | Intel      | Ice Lake-LP DRAM Controller  | 9     |            | 4967676215 |
| 8086:9d21 | 103c:80d1 | Intel      | Sunrise Point-LP PMC         | 9     |            | 629D516666 |
| 8086:9d21 | 103c:81a1 | Intel      | Sunrise Point-LP PMC         | 9     |            | B37CBA5DF4 |
| 8086:9d21 | 17aa:2237 | Intel      | Sunrise Point-LP PMC         | 9     |            | 24D1BD52CC |
| 8086:9d21 | 17aa:3849 | Intel      | Sunrise Point-LP PMC         | 9     |            | E2C078E281 |
| 8086:9def | 1028:0894 | Intel      | Cannon Point-LP Shared SRAM  | 9     |            | B07A0CF706 |
| 8086:9def | 103c:861f | Intel      | Cannon Point-LP Shared SRAM  | 9     |            | 48CABEDB1E |
| 8086:02ef | 1028:095d | Intel      | Comet Lake PCH-LP Shared ... | 8     |            | E85575B823 |
| 8086:02ef | 103c:863f | Intel      | Comet Lake PCH-LP Shared ... | 8     |            | 2A2CFDB7D4 |
| 8086:9d21 | 103c:8484 | Intel      | Sunrise Point-LP PMC         | 8     |            | F3D65BB221 |
| 8086:9d21 | 17aa:506c | Intel      | Sunrise Point-LP PMC         | 8     |            | B39CD022D3 |
| 8086:9def | 103c:85c4 | Intel      | Cannon Point-LP Shared SRAM  | 8     |            | 7D9588F740 |
| 8086:9def | 1043:19d1 | Intel      | Cannon Point-LP Shared SRAM  | 8     |            | DBBD7A332E |
| 8086:9def | 17aa:5077 | Intel      | Cannon Point-LP Shared SRAM  | 8     |            | B9971B685A |
| 8086:02ef | 1028:0950 | Intel      | Comet Lake PCH-LP Shared ... | 7     |            | 6E2B3B5A7E |
| 8086:02ef | 1028:09cd | Intel      | Comet Lake PCH-LP Shared ... | 7     |            | 20FA4B73D7 |
| 8086:02ef | 17aa:3803 | Intel      | Comet Lake PCH-LP Shared ... | 7     |            | 611C3C0C19 |
| 8086:34ef | 1025:141f | Intel      | Ice Lake-LP DRAM Controller  | 7     |            | 059B59E828 |
| 8086:34ef | 8086:7270 | Intel      | Ice Lake-LP DRAM Controller  | 7     |            | 2169C592D9 |
| 8086:9d21 | 103c:81ad | Intel      | Sunrise Point-LP PMC         | 7     |            | A6FF75E220 |
| 8086:9d21 | 1043:14f0 | Intel      | Sunrise Point-LP PMC         | 7     |            | E682AFBEDE |
| 8086:9d21 | 1043:1b00 | Intel      | Sunrise Point-LP PMC         | 7     |            | 9FF68B8AD1 |
| 8086:9d21 | 1043:1dc0 | Intel      | Sunrise Point-LP PMC         | 7     |            | 26CE6DC2B2 |
| 8086:9d21 | 17aa:5061 | Intel      | Sunrise Point-LP PMC         | 7     |            | 16AC72B8EA |
| 8086:9def | 103c:857f | Intel      | Cannon Point-LP Shared SRAM  | 7     |            | 465B51ACD4 |
| 8086:a0ef |           | Intel      | Tiger Lake-LP Shared SRAM    | 7     |            | 6461BFC243 |
| 8086:a0ef | 1028:09df | Intel      | Tiger Lake-LP Shared SRAM    | 7     |            | 69D2B432F7 |
| 8086:a0ef | 103c:8709 | Intel      | Tiger Lake-LP Shared SRAM    | 7     |            | 444E13B5ED |
| 8086:a0ef | 17aa:3801 | Intel      | Tiger Lake-LP Shared SRAM    | 7     |            | 5B06944051 |
| 8086:a36f | 17aa:3835 | Intel      | Cannon Lake PCH Shared SRAM  | 7     |            | 4EEE4B94CB |
| 8086:02ef | 17aa:2292 | Intel      | Comet Lake PCH-LP Shared ... | 6     |            | 8F10E30326 |
| 8086:02ef | 17aa:22be | Intel      | Comet Lake PCH-LP Shared ... | 6     |            | 65033505B7 |
| 8086:490e |           | Intel      | Mini CTA                     | 6     | intel_pmt  | 224CE9A44D |
| 8086:9d21 | 1025:1176 | Intel      | Sunrise Point-LP PMC         | 6     |            | 566FA6B1D5 |
| 8086:9d21 | 1028:07eb | Intel      | Sunrise Point-LP PMC         | 6     |            | 765C6838B2 |
| 8086:9d21 | 103c:8313 | Intel      | Sunrise Point-LP PMC         | 6     |            | 5D0F309968 |
| 8086:9d21 | 103c:8483 | Intel      | Sunrise Point-LP PMC         | 6     |            | C48CB1FCCF |
| 8086:9d21 | 1043:1c90 | Intel      | Sunrise Point-LP PMC         | 6     |            | AED32F7A4D |
| 8086:9d21 | 17aa:3864 | Intel      | Sunrise Point-LP PMC         | 6     |            | 570666D7D6 |
| 8086:9d21 | 1ae0:006b | Intel      | Sunrise Point-LP PMC         | 6     |            | CBC1BB3811 |
| 8086:9def | 1028:089e | Intel      | Cannon Point-LP Shared SRAM  | 6     |            | C52711AB47 |
| 8086:9def | 1028:08e2 | Intel      | Cannon Point-LP Shared SRAM  | 6     |            | ADF32CA36B |
| 8086:a0ef | 103c:87f7 | Intel      | Tiger Lake-LP Shared SRAM    | 6     |            | E1D0678746 |
| 8086:a0ef | 17aa:381d | Intel      | Tiger Lake-LP Shared SRAM    | 6     |            | 14109EDFC9 |
| 8086:02ef | 1028:0960 | Intel      | Comet Lake PCH-LP Shared ... | 5     |            | 40A7A1942F |
| 8086:02ef | 17aa:22ad | Intel      | Comet Lake PCH-LP Shared ... | 5     |            | 50C28ABBA1 |
| 8086:34ef | 103c:86fa | Intel      | Ice Lake-LP DRAM Controller  | 5     |            | 635BBB6F75 |
| 8086:9d21 | 103c:81a9 | Intel      | Sunrise Point-LP PMC         | 5     |            | 0BB3F77C75 |
| 8086:9d21 | 103c:827f | Intel      | Sunrise Point-LP PMC         | 5     | intel_p... | BD5BDFD31F |
| 8086:9d21 | 103c:8487 | Intel      | Sunrise Point-LP PMC         | 5     |            | CEBF94C181 |
| 8086:9d21 | 1043:14c0 | Intel      | Sunrise Point-LP PMC         | 5     |            | 84CEEEACF1 |
| 8086:9d21 | 17aa:504c | Intel      | Sunrise Point-LP PMC         | 5     |            | 4983586FE5 |
| 8086:9d21 | 8086:9d21 | Intel      | Sunrise Point-LP PMC         | 5     |            | BC5D045DEF |
| 8086:9def | 1028:0895 | Intel      | Cannon Point-LP Shared SRAM  | 5     |            | 5A60912D9F |
| 8086:9def | 1028:0896 | Intel      | Cannon Point-LP Shared SRAM  | 5     |            | 4D7F19A11A |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15e2 | 17aa:381b | AMD        | Raven/Raven2/FireFlight/R... | 64    | snd_pci... | F07B9B77F5 |
| 1022:15e2 | 103c:876e | AMD        | Raven/Raven2/FireFlight/R... | 38    | snd_pci... | 28B152BB19 |
| 1022:15e2 | 103c:876f | AMD        | Raven/Raven2/FireFlight/R... | 34    | snd_pci... | 5F67B298AB |
| 8086:22b8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 32    | intel_a... | 74FE90715F |
| 1022:15e2 | 103c:85dd | AMD        | Raven/Raven2/FireFlight/R... | 23    | snd_pci... | C4EA79E269 |
| 8086:8a19 | 1028:08b0 | Intel      | Image Signal Processor       | 23    |            | 138EC046F1 |
| 1022:15e2 | 103c:85de | AMD        | Raven/Raven2/FireFlight/R... | 19    | snd_pci... | 3ADCB9ECF9 |
| 1022:15e2 | 103c:8735 | AMD        | Raven/Raven2/FireFlight/R... | 15    | snd_pci... | 4EE6C35B8F |
| 1022:15e2 | 103c:888a | AMD        | Raven/Raven2/FireFlight/R... | 9     | snd_pci... | ED20604458 |
| 1022:15e2 | 17aa:380b | AMD        | Raven/Raven2/FireFlight/R... | 9     | snd_pci... | 381F6460B0 |
| 1022:15e2 | 1028:09e3 | AMD        | Raven/Raven2/FireFlight/R... | 8     | snd_pci... | 58C4A6AD98 |
| 8086:5a88 |           | Intel      | Celeron N3350/Pentium N42... | 7     |            | AA88177E76 |
| 1022:15e2 | 103c:8496 | AMD        | Raven/Raven2/FireFlight/R... | 6     | snd_pci... | 8D862A60C9 |
| 1022:15e2 | 17aa:3828 | AMD        | Raven/Raven2/FireFlight/R... | 6     | snd_pci... | 65A49B7280 |
| 1022:15e2 | 1028:0a8c | AMD        | Raven/Raven2/FireFlight/R... | 5     | snd_rn_... | 58E1FA994C |
| 1022:15e2 | 103c:87a9 | AMD        | Raven/Raven2/FireFlight/R... | 5     | snd_rn_... | 96C4D24CAB |
| 1022:15e2 | 1043:11f2 | AMD        | Raven/Raven2/FireFlight/R... | 5     | snd_pci... | 395433A65C |
| 1022:15e2 | 17aa:380e | AMD        | Raven/Raven2/FireFlight/R... | 5     | snd_pci... | C977BD2115 |
| 8086:9a19 | 1028:0a5b | Intel      | Multimedia controller        | 4     |            | 062C3B976F |
| 8086:9d32 |           | Intel      | CSI-2 Host Controller        | 4     | ipu3_cio2  | 6F018F175E |
| 1022:15e2 | 1025:1506 | AMD        | Raven/Raven2/FireFlight/R... | 2     | snd_pci... | D000862005 |
| 8086:1919 | 103c:8486 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | ipu3_imgu  | 4796134BF9 |
| 8086:1919 | 8086:1919 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | ipu3_imgu  | 6F018F175E |
| 1022:15e2 | 103c:8497 | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | C5914E5F87 |
| 1022:15e2 | 103c:88c2 | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | 2552FC1A99 |
| 1022:15e2 | 1043:1592 | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | 8E0A4F8E98 |
| 1022:15e2 | 17aa:383b | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_rn_... | B1BB1E8325 |
| 1022:15e2 | 17aa:383d | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | E7AB53C038 |
| 8086:9a19 | 3100:0001 | Intel      | Multimedia controller        | 1     |            | 1CFE27D3D1 |
| 8086:9d32 | 8086:9d32 | Intel      | CSI-2 Host Controller        | 1     |            | BC5D045DEF |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:15fc | 17aa:5089 | Intel      | Ethernet Connection (13) ... | 59    | e1000e     | 1EC4861E97 |
| 10ec:8168 | 17aa:3850 | Realtek... | RTL8111/8168/8411 PCI Exp... | 16    | r8169      | 350D402895 |
| 8086:156f | 17aa:2233 | Intel      | Ethernet Connection I219-LM  | 15    | e1000e     | E672E101F4 |
| 8086:1570 | 17aa:2233 | Intel      | Ethernet Connection I219-V   | 13    | e1000e     | 24D1BD52CC |
| 10ec:8168 | 17aa:3848 | Realtek... | RTL8111/8168/8411 PCI Exp... | 12    | r8169      | 5154E96ABE |
| 8086:0d4f | 17aa:5078 | Intel      | Ethernet Connection (10) ... | 12    | e1000e     | B946F364DB |
| 8086:15be | 17aa:2292 | Intel      | Ethernet Connection (6) I... | 10    | e1000e     | 1D4E30D33E |
| 10ec:8136 | 103c:80d1 | Realtek... | RTL810xE PCI Express Fast... | 9     | r8169      | 629D516666 |
| 8086:15d7 | 17aa:2259 | Intel      | Ethernet Connection (4) I... | 9     | e1000e     | 36DBFEF2B7 |
| 8086:15be | 17aa:5077 | Intel      | Ethernet Connection (6) I... | 8     | e1000e     | B9971B685A |
| 8086:15d7 | 17aa:224e | Intel      | Ethernet Connection (4) I... | 8     | e1000e     | 3C24D27D51 |
| 8086:15d7 | 17aa:506d | Intel      | Ethernet Connection (4) I... | 8     | e1000e     | 99C878CD5E |
| 10ec:8136 | 103c:802b | Realtek... | RTL810xE PCI Express Fast... | 7     | r8169      | 4E86625634 |
| 8086:15bd | 17aa:2292 | Intel      | Ethernet Connection (6) I... | 7     | e1000e     | D99F5CBFD2 |
| 8086:15d7 | 17aa:224f | Intel      | Ethernet Connection (4) I... | 7     | e1000e     | 16AC72B8EA |
| 8086:15d8 | 17aa:506c | Intel      | Ethernet Connection (4) I... | 7     | e1000e     | B39CD022D3 |
| 10ec:8168 | 17aa:383f | Realtek... | RTL8111/8168/8411 PCI Exp... | 6     | r8169      | 4FD337BCA7 |
| 8086:0d4f | 17aa:2292 | Intel      | Ethernet Connection (10) ... | 6     | e1000e     | 8F10E30326 |
| 8086:0d4f | 17aa:22be | Intel      | Ethernet Connection (10) ... | 5     | e1000e     | E40B11DCA2 |
| 8086:15d8 | 17aa:224e | Intel      | Ethernet Connection (4) I... | 5     | e1000e     | 737878ED56 |
| 10ec:8136 | 103c:806e | Realtek... | RTL810xE PCI Express Fast... | 4     | r8169      | A8AA7A1D17 |
| 10ec:8168 | 103c:84d8 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 03FE12C3CC |
| 10ec:8168 | 17aa:3868 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 6931FAE5CC |
| 8086:15be | 17aa:2294 | Intel      | Ethernet Connection (6) I... | 4     | e1000e     | 09DC5430DA |
| 8086:15d8 | 17aa:2259 | Intel      | Ethernet Connection (4) I... | 4     | e1000e     | FEEC038877 |
| 10ec:8168 | 1025:1198 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | A49C104EDA |
| 10ec:8168 | 103c:8251 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | DBD6D18C03 |
| 8086:0d4f | 17aa:22ad | Intel      | Ethernet Connection (10) ... | 3     | e1000e     | 50C28ABBA1 |
| 8086:156f | 17aa:504c | Intel      | Ethernet Connection I219-LM  | 3     | e1000e     | 4983586FE5 |
| 8086:15d8 | 17aa:506d | Intel      | Ethernet Connection (4) I... | 3     | e1000e     | 569A71C90A |
| 10ec:8136 | 103c:8074 | Realtek... | RTL810xE PCI Express Fast... | 2     | r8169      | 71479C34B4 |
| 10ec:8168 | 103c:8143 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 03065735FF |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 6B3E692B8E |
| 8086:0d4e | 17aa:22ad | Intel      | Ethernet Connection (10) ... | 2     | e1000e     | 18DF123A3F |
| 8086:1570 | 17aa:504c | Intel      | Ethernet Connection I219-V   | 2     | e1000e     | 8451A446B5 |
| 10ec:8168 | 1025:129f | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 0F6F9B0A03 |
| 10ec:8168 | 1025:1430 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | A5E2305F6F |
| 10ec:8168 | 103c:806c | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 462F2D5347 |
| 10ec:8168 | 103c:80cf | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 15B7980DAF |
| 10ec:8168 | 103c:80d0 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 97ED13A8C0 |
| 10ec:8168 | 103c:8252 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 593F2ADB26 |
| 10ec:8168 | 103c:86cf | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 33D5688BFC |
| 10ec:8168 | 144d:c14c | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 6E023867E9 |
| 10ec:8168 | 17aa:5058 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | C65BB14578 |
| 10ec:8168 | 17aa:506e | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 65846CBF2B |
| 14e4:1682 | 14e4:1682 | Broadcom   | NetXtreme BCM57762 Gigabi... | 1     | tg3        | 1C675DD7D7 |
| 8086:0d4e | 17aa:22be | Intel      | Ethernet Connection (10) ... | 1     | e1000e     | 65033505B7 |
| 8086:0d4e | 17aa:5078 | Intel      | Ethernet Connection (10) ... | 1     | e1000e     | 49DBAD6FDB |
| 8086:1533 | 1179:0001 | Intel      | I210 Gigabit Network Conn... | 1     | igb        | 49170BD478 |
| 8086:1533 | 1799:0098 | Intel      | I210 Gigabit Network Conn... | 1     | igb        | AC3DC845F8 |
| 8086:1533 | 1c7a:0019 | Intel      | I210 Gigabit Network Conn... | 1     | igb        | C28F77B8F1 |
| 8086:156f | 10cf:192c | Intel      | Ethernet Connection I219-LM  | 1     | e1000e     | 646D26ABF7 |
| 8086:15bd | 17aa:2294 | Intel      | Ethernet Connection (6) I... | 1     | e1000e     | 3C03CE796F |
| 8086:15bd | 1e26:001a | Intel      | Ethernet Connection (6) I... | 1     | e1000e     | 437C9D66AA |
| 8086:15d7 | 10cf:192c | Intel      | Ethernet Connection (4) I... | 1     | e1000e     | 2DE9720090 |
| 8086:15d7 | 17aa:506c | Intel      | Ethernet Connection (4) I... | 1     | e1000e     | E8A3DB75CB |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:b822 | 103c:831b | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 114   | rtwpci     | 3ADCB9ECF9 |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 95    | iwlwifi    | 45BA0657F1 |
| 8086:2723 | 8086:0084 | Intel      | Wi-Fi 6 AX200                | 77    | iwlwifi    | 4EE6C35B8F |
| 8086:9df0 | 8086:0034 | Intel      | Cannon Point-LP CNVi [Wir... | 73    | iwlwifi    | DBBD7A332E |
| 8086:a0f0 | 8086:0074 | Intel      | Wi-Fi 6 AX201                | 71    | iwlwifi    | 00AC329183 |
| 168c:003e | 17aa:0827 | Qualcom... | QCA6174 802.11ac Wireless... | 70    | ath10k_pci | A2717638BE |
| 8086:34f0 | 8086:0074 | Intel      | Ice Lake-LP PCH CNVi WiFi    | 69    | iwlwifi    | 4967676215 |
| 8086:24fd | 8086:9010 | Intel      | Wireless 8265 / 8275         | 64    | iwlwifi    | BBB2DB43B4 |
| 8086:02f0 | 8086:0074 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 63    | iwlwifi    | 2A2CFDB7D4 |
| 8086:a0f0 | 8086:0070 | Intel      | Wi-Fi 6 AX201                | 62    | iwlwifi    | 1EC4861E97 |
| 10ec:c822 | 103c:85f7 | Realtek... | RTL8822CE 802.11ac PCIe W... | 61    | rtw88_8... | 28B152BB19 |
| 10ec:c822 | 17aa:c123 | Realtek... | RTL8822CE 802.11ac PCIe W... | 59    | rtw88_8... | 65A49B7280 |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 50    | iwlwifi    | 06E7A51D6A |
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 48    | iwlwifi    | 9383081522 |
| 8086:a0f0 | 8086:4070 | Intel      | Wi-Fi 6 AX201                | 48    | iwlwifi    | 224CE9A44D |
| 168c:0042 | 17aa:0901 | Qualcom... | QCA9377 802.11ac Wireless... | 46    | ath10k_pci | 5154E96ABE |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 35    | 8821ce     | 5863FA858F |
| 8086:2526 | 8086:0014 | Intel      | Wireless-AC 9260             | 35    | iwlwifi    | 85B5F14102 |
| 8086:24fd | 8086:8010 | Intel      | Wireless 8265 / 8275         | 34    | iwlwifi    | 95D389BFE5 |
| 8086:02f0 | 8086:0034 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 32    | iwlwifi    | 527CC99B36 |
| 8086:9df0 | 8086:0030 | Intel      | Cannon Point-LP CNVi [Wir... | 31    | iwlwifi    | B9971B685A |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 28    | iwlwifi    | 72617E5DD9 |
| 8086:3165 | 8086:8010 | Intel      | Wireless 3165                | 25    | iwlwifi    | 02E94E7CD4 |
| 8086:24f3 | 8086:1130 | Intel      | Wireless 8260                | 24    | iwlwifi    | 24D1BD52CC |
| 10ec:b822 | 17aa:b023 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 23    | rtw88_8... | 557E4010C3 |
| 8086:02f0 | 8086:4070 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 23    | iwlwifi    | 6E2B3B5A7E |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 23    | iwlwifi    | AB13E942F9 |
| 8086:34f0 | 1a56:1651 | Intel      | Ice Lake-LP PCH CNVi WiFi    | 23    | iwlwifi    | 138EC046F1 |
| 8086:2723 | 8086:008c | Intel      | Wi-Fi 6 AX200                | 21    | iwlwifi    | 48CABEDB1E |
| 8086:24f3 | 8086:0130 | Intel      | Wireless 8260                | 20    | iwlwifi    | CFE1719EFB |
| 8086:9df0 | 8086:4234 | Intel      | Cannon Point-LP CNVi [Wir... | 20    | iwlwifi    | A5D699A294 |
| 8086:24fd | 8086:8050 | Intel      | Wireless 8265 / 8275         | 18    | iwlwifi    | D11804DA19 |
| 8086:9df0 | 8086:4030 | Intel      | Cannon Point-LP CNVi [Wir... | 18    | iwlwifi    | ADF32CA36B |
| 8086:24f3 | 8086:0110 | Intel      | Wireless 8260                | 17    | iwlwifi    | 84CEEEACF1 |
| 8086:02f0 | 8086:0030 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 16    | iwlwifi    | 8F10E30326 |
| 8086:02f0 | 8086:0070 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 15    | iwlwifi    | 50C28ABBA1 |
| 8086:7360 | 8086:0020 | Intel      | XMM7360 LTE Advanced Modem   | 15    | xmm7360    | 527CC99B36 |
| 8086:24fd | 8086:0130 | Intel      | Wireless 8265 / 8275         | 14    | iwlwifi    | 16AC72B8EA |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 14    | iwlwifi    | 03065735FF |
| 8086:31dc | 8086:02a4 | Intel      | Gemini Lake PCH CNVi WiFi    | 14    | iwlwifi    | 4DBC03E904 |
| 8086:a0f0 | 1a56:1651 | Intel      | Wi-Fi 6 AX201                | 14    | iwlwifi    | 5B10037DA5 |
| 8086:2723 | 8086:4080 | Intel      | Wi-Fi 6 AX200                | 13    | iwlwifi    | 58C4A6AD98 |
| 8086:3165 | 8086:8110 | Intel      | Wireless 3165                | 13    | iwlwifi    | 4BF1EEBDE1 |
| 168c:003e | 1a56:143a | Qualcom... | QCA6174 802.11ac Wireless... | 12    | ath10k_pci | 27D7C254CC |
| 8086:24f3 | 8086:8010 | Intel      | Wireless 8260                | 12    | iwlwifi    | 26CE6DC2B2 |
| 168c:003e | 11ad:0807 | Qualcom... | QCA6174 802.11ac Wireless... | 11    | ath10k_pci | 0D47CA8A0C |
| 168c:0042 | 17aa:4035 | Qualcom... | QCA9377 802.11ac Wireless... | 11    | ath10k_pci | 56E69DB298 |
| 8086:7360 | 103c:8337 | Intel      | XMM7360 LTE Advanced Modem   | 11    | xmm7360    | 48CABEDB1E |
| 10ec:c821 | 17aa:c024 | Realtek... | RTL8821CE 802.11ac PCIe W... | 10    | 8821ce     | 4D915AC887 |
| 168c:0042 | 11ad:08a6 | Qualcom... | QCA9377 802.11ac Wireless... | 10    | ath10k_pci | 97DFF84E2B |
| 8086:095a | 8086:5410 | Intel      | Wireless 7265                | 9     | iwlwifi    | FA3A8B9226 |
| 10ec:d723 | 103c:8319 | Realtek... | RTL8723DE Wireless Networ... | 8     | rtl8723de  | BDF169950D |
| 8086:02f0 | 8086:4234 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 8     | iwlwifi    | E85575B823 |
| 8086:3166 | 8086:4310 | Intel      | Dual Band Wireless-AC 316... | 8     | iwlwifi    | 350D402895 |
| 8086:31dc | 8086:0034 | Intel      | Gemini Lake PCH CNVi WiFi    | 8     | iwlwifi    | A5E2305F6F |
| 8086:9df0 | 8086:0000 | Intel      | Cannon Point-LP CNVi [Wir... | 8     | iwlwifi    | 5A60912D9F |
| 10ec:c821 | 10ec:c821 | Realtek... | RTL8821CE 802.11ac PCIe W... | 7     | rtw_8821ce | E4FB415516 |
| 8086:24fd | 8086:1130 | Intel      | Wireless 8265 / 8275         | 7     | iwlwifi    | 737878ED56 |
| 8086:a370 | 8086:0034 | Intel      | Cannon Lake PCH CNVi WiFi    | 7     | iwlwifi    | 4EEE4B94CB |
| 10ec:8852 | 103c:88e1 | Realtek... | RTL8852AE 802.11ax PCIe W... | 6     | rtw89pci   | ED20604458 |
| 10ec:b723 | 103c:804c | Realtek... | RTL8723BE PCIe Wireless N... | 6     | rtl8723be  | 71479C34B4 |
| 14e4:4365 | 103c:2230 | Broadcom   | BCM43142 802.11b/g/n         | 6     | wl         | 4E86625634 |
| 168c:0042 | 1a3b:2231 | Qualcom... | QCA9377 802.11ac Wireless... | 6     | ath10k_pci | 7F25CF70DD |
| 8086:095a | 8086:9e10 | Intel      | Wireless 7265                | 6     | iwlwifi    | CBC1BB3811 |
| 8086:02f0 | 8086:4030 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 5     | iwlwifi    | 40A7A1942F |
| 8086:06f0 | 8086:0074 | Intel      | Comet Lake PCH CNVi WiFi     | 5     | iwlwifi    | 66D71367C1 |
| 8086:24f3 | 8086:9010 | Intel      | Wireless 8260                | 5     | iwlwifi    | FCDC02AB43 |
| 8086:31dc | 8086:0264 | Intel      | Gemini Lake PCH CNVi WiFi    | 5     | iwlwifi    | B227E694F7 |
| 8086:34f0 | 8086:0234 | Intel      | Ice Lake-LP PCH CNVi WiFi    | 5     | iwlwifi    | E5251674C0 |
| 10ec:8852 | 17aa:4852 | Realtek... | RTL8852AE 802.11ax PCIe W... | 4     | rtw89pci   | E7AB53C038 |
| 8086:02f0 | 8086:02a4 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 4     | iwlwifi    | 611C3C0C19 |
| 8086:24fd | 8086:0150 | Intel      | Wireless 8265 / 8275         | 4     | iwlwifi    | 1BB17DC648 |
| 8086:2723 | 8086:0088 | Intel      | Wi-Fi 6 AX200                | 4     | iwlwifi    | 465B51ACD4 |
| 8086:2725 | 8086:0024 | Intel      | Wi-Fi 6 AX210/AX211/AX411... | 4     | iwlwifi    | F39DEDA45C |
| 8086:2725 | 8086:4020 | Intel      | Wi-Fi 6 AX210/AX211/AX411... | 4     | iwlwifi    | 062C3B976F |
| 8086:9df0 | 8086:42a4 | Intel      | Cannon Point-LP CNVi [Wir... | 4     | iwlwifi    | C52711AB47 |
| 8086:a0f0 | 8086:0234 | Intel      | Wi-Fi 6 AX201                | 4     | iwlwifi    | 5B06944051 |
| 14e4:43ec | 17aa:7006 | Broadco... | BCM4356 802.11ac Wireless... | 3     | brcmfmac   | 78CA0E0334 |
| 168c:003e | 1028:0310 | Qualcom... | QCA6174 802.11ac Wireless... | 3     | ath10k_pci | 91F3D918A0 |
| 168c:0042 | 1028:1810 | Qualcom... | QCA9377 802.11ac Wireless... | 3     | ath10k_pci | 8C30BDF3B8 |
| 8086:095a | 8086:9010 | Intel      | Wireless 7265                | 3     | iwlwifi    | B58CB2CFAB |
| 8086:24fd | 8086:0110 | Intel      | Wireless 8265 / 8275         | 3     | iwlwifi    | 2DE9720090 |
| 8086:2526 | 8086:0010 | Intel      | Wireless-AC 9260             | 3     | iwlwifi    | 6E5C30C5C5 |
| 8086:2723 | 8086:0080 | Intel      | Wi-Fi 6 AX200                | 3     | iwlwifi    | 4F8F955FAF |
| 8086:34f0 | 8086:4070 | Intel      | Ice Lake-LP PCH CNVi WiFi    | 3     | iwlwifi    | 889499B855 |
| 8086:a0f0 | 8086:0264 | Intel      | Wi-Fi 6 AX201                | 3     | iwlwifi    | 12CD034896 |
| 10ec:b723 | 103c:81c1 | Realtek... | RTL8723BE PCIe Wireless N... | 2     | rtl8723be  | 198A1829BB |
| 10ec:b822 | 1a3b:2950 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 2     | rtw_pci    | 18B4F9B58E |
| 168c:0042 | 1a3b:2251 | Qualcom... | QCA9377 802.11ac Wireless... | 2     | ath10k_pci | 45B1907784 |
| 8086:08b2 | 8086:c270 | Intel      | Wireless 7260                | 2     | iwlwifi    | 04E375292D |
| 8086:08b3 | 8086:8070 | Intel      | Wireless 3160                | 2     | iwlwifi    | 31942977C3 |
| 8086:7560 | 103c:8507 | Intel      | Wireless controller          | 2     |            | 2ECA85F866 |
| 8086:9df0 | 8086:02a4 | Intel      | Cannon Point-LP CNVi [Wir... | 2     | iwlwifi    | E47B0DD26C |
| 8086:a0f0 | 1a56:1652 | Intel      | Wi-Fi 6 AX201                | 2     | iwlwifi    | 8C3B4736CD |
| 8086:a370 | 8086:0030 | Intel      | Cannon Lake PCH CNVi WiFi    | 2     | iwlwifi    | 2668A6580A |
| 03f0:0a6c | 103c:877f |            | Wireless controller          | 1     |            | C58154679E |
| 105b:e0b0 | 105b:e0b0 | Foxconn... | Wireless controller          | 1     | mhi_pci... | 26F16E4312 |
| 10ec:8821 | 1a3b:2161 | Realtek... | RTL8821AE 802.11ac PCIe W... | 1     | rtl8821ae  | 8269E87811 |
| 10ec:b723 | 103c:8167 | Realtek... | RTL8723BE PCIe Wireless N... | 1     | rtl8723be  | 629D516666 |
| 10ec:b822 | 17aa:b024 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 1     | r8822be    | BC69AFD822 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1533 | 1ab6:0214 | Intel      | I210 Gigabit Network Conn... | 1     | igb        | B918F25E12 |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d26 |           | Intel      | Skylake-U/Y Northpeak        | 19    | intel_t... | 03065735FF |
| 8086:318e |           | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_t... | D11804DA19 |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d35 | 8086:9d35 | Intel      | Sunrise Point-LP Integrat... | 38    | intel_i... | 84CEEEACF1 |
| 8086:9d35 | 103c:83b9 | Intel      | Sunrise Point-LP Integrat... | 26    | intel_i... | BBB2DB43B4 |
| 1022:15e4 | 103c:85dd | AMD        | Raven/Raven2/Renoir Senso... | 23    | amd_sfh    | C4EA79E269 |
| 8086:9d35 | 17aa:2238 | Intel      | Sunrise Point-LP Integrat... | 22    | intel_i... | DD105BA06B |
| 1022:15e6 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Non-S... | 21    | i2c_amd... | 6AF7A7F851 |
| 8086:9d35 | 17aa:380d | Intel      | Sunrise Point-LP Integrat... | 21    | intel_i... | 72617E5DD9 |
| 1022:15e4 | 103c:85de | AMD        | Raven/Raven2/Renoir Senso... | 19    | amd_sfh    | 3ADCB9ECF9 |
| 8086:9d35 | 103c:827d | Intel      | Sunrise Point-LP Integrat... | 18    | intel_i... | 95D389BFE5 |
| 1022:15e4 | 103c:8497 | AMD        | Raven/Raven2/Renoir Senso... | 16    | pcie_mp... | 0DFE108C69 |
| 1022:15e4 | 103c:8496 | AMD        | Raven/Raven2/Renoir Senso... | 15    | amd_sfh    | DFB9789AF2 |
| 8086:9d35 | 1028:077a | Intel      | Sunrise Point-LP Integrat... | 15    | intel_i... | 8F7ADB6CD3 |
| 8086:9d35 | 103c:830f | Intel      | Sunrise Point-LP Integrat... | 15    | intel_i... | 3286ED83B9 |
| 8086:9d35 | 103c:8486 | Intel      | Sunrise Point-LP Integrat... | 15    | intel_i... | 7E241B1F69 |
| 8086:9d35 | 17aa:224e | Intel      | Sunrise Point-LP Integrat... | 14    | intel_i... | 3C24D27D51 |
| 8086:9d35 | 17aa:2259 | Intel      | Sunrise Point-LP Integrat... | 14    | intel_i... | 36DBFEF2B7 |
| 8086:9d35 | 103c:827e | Intel      | Sunrise Point-LP Integrat... | 13    | intel_i... | CCA3E863F7 |
| 8086:a135 | 103c:83bb | Intel      | 100 Series/C230 Series Ch... | 13    | intel_i... | BA09E3B76F |
| 8086:a135 | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 12    | intel_i... | 27D7C254CC |
| 8086:9d35 | 103c:8488 | Intel      | Sunrise Point-LP Integrat... | 11    | intel_i... | 3AF23C8E87 |
| 8086:9d35 | 1043:1ab0 | Intel      | Sunrise Point-LP Integrat... | 11    | intel_i... | 06E7A51D6A |
| 8086:9d35 | 17aa:506d | Intel      | Sunrise Point-LP Integrat... | 11    | intel_i... | 99C878CD5E |
| 8086:9d35 | 103c:8438 | Intel      | Sunrise Point-LP Integrat... | 10    | intel_i... | AF74E3A1EA |
| 8086:9d35 | 103c:81a1 | Intel      | Sunrise Point-LP Integrat... | 9     | intel_i... | B37CBA5DF4 |
| 8086:9d35 | 17aa:2237 | Intel      | Sunrise Point-LP Integrat... | 9     | intel_i... | 24D1BD52CC |
| 8086:9d35 | 103c:8484 | Intel      | Sunrise Point-LP Integrat... | 8     | intel_i... | F3D65BB221 |
| 8086:9d35 | 17aa:506c | Intel      | Sunrise Point-LP Integrat... | 8     | intel_i... | B39CD022D3 |
| 8086:9d24 |           | Intel      | Skylake-U/Y SPI Controller   | 7     |            | CBC1BB3811 |
| 8086:9d35 | 103c:81ad | Intel      | Sunrise Point-LP Integrat... | 7     | intel_i... | A6FF75E220 |
| 8086:9d35 | 17aa:5061 | Intel      | Sunrise Point-LP Integrat... | 7     | intel_i... | 16AC72B8EA |
| 8086:9d35 | 1028:07eb | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | 765C6838B2 |
| 8086:9d35 | 103c:8313 | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | 5D0F309968 |
| 8086:9d35 | 103c:8483 | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | C48CB1FCCF |
| 8086:9d35 | 1043:1c90 | Intel      | Sunrise Point-LP Integrat... | 6     | intel_i... | AED32F7A4D |
| 8086:9d35 | 103c:81a9 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 0BB3F77C75 |
| 8086:9d35 | 103c:827f | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | BD5BDFD31F |
| 8086:9d35 | 103c:8487 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | CEBF94C181 |
| 8086:9d35 | 17aa:504c | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 4983586FE5 |
| 8086:9d35 | 103c:81a7 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | BC77E670A5 |
| 8086:9d35 | 103c:82c1 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | CF06BA276E |
| 8086:9d35 | 103c:83c4 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 3F62C672FB |
| 8086:9d35 | 103c:8470 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 3AF4716969 |
| 8086:9d35 | 103c:84d8 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 03FE12C3CC |
| 1022:15e4 | 1028:090c | AMD        | Raven/Raven2/Renoir Senso... | 3     |            | B6C573F5AA |
| 8086:22d8 | 8086:7270 | Intel      | Integrated Sensor Solution   | 3     | intel_i... | 78CA0E0334 |
| 8086:9d35 | 1028:07aa | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 5492FDD780 |
| 8086:9d35 | 1028:07ec | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | FA3A8B9226 |
| 8086:9d35 | 1028:0878 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 91F3D918A0 |
| 8086:9d35 | 103c:804f | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 45BA0657F1 |
| 8086:9d35 | 103c:8251 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | DBD6D18C03 |
| 8086:9d35 | 103c:82b7 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 3B8F11D2DB |
| 8086:9d35 | 103c:8310 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | D7D0DE8CF4 |
| 8086:9d35 | 103c:83ba | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | FB88A217E9 |
| 8086:9d35 | 1043:1c40 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | BD57C16BE8 |
| 8086:9d35 | 144d:c162 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 5DA835E33E |
| 8086:9d35 | 17aa:380c | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 32B0895AB5 |
| 1022:15e4 | 1025:1506 | AMD        | Raven/Raven2/Renoir Senso... | 2     | amd_sfh    | D000862005 |
| 8086:9d35 |           | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | C34BCC095C |
| 8086:9d35 | 1028:0823 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | CCD587FDE5 |
| 8086:9d35 | 103c:8143 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 03065735FF |
| 8086:9d35 | 103c:81ac | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 235D55372B |
| 8086:9d35 | 103c:8314 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 5CF089CFA1 |
| 8086:9d35 | 103c:83c9 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 8BF489A0CB |
| 8086:9d35 | 103c:8503 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | F6ABCD9B4F |
| 8086:9d35 | 144d:c141 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | ADF6EF8A4C |
| 8086:9d35 | 103c:80cf | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 15B7980DAF |
| 8086:9d35 | 103c:80d1 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | EC722FBBFE |
| 8086:9d35 | 103c:8174 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 48C1B1144A |
| 8086:9d35 | 103c:8252 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 593F2ADB26 |
| 8086:9d35 | 103c:8300 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | BF9A3D1A33 |
| 8086:9d35 | 103c:8316 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 122A201FB4 |
| 8086:9d35 | 103c:83c5 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | AA7134D622 |
| 8086:9d35 | 103c:8420 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | B2253870F2 |
| 8086:9d35 | 103c:8491 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 8CE6E9CB36 |
| 8086:9d35 | 103c:853d | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 9383081522 |
| 8086:9d35 | 103c:8770 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 87199D7E85 |
| 8086:9d35 | 1043:1b40 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 0324B06288 |
| 8086:9d35 | 10cf:18d0 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 646D26ABF7 |
| 8086:9d35 | 10cf:1955 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 2DE9720090 |
| 8086:9d35 | 1179:0001 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 430A666F91 |
| 8086:9d35 | 144d:c14b | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | FCDC02AB43 |
| 8086:9d35 | 144d:c14c | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 6E023867E9 |
| 8086:9d35 | 144d:c157 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 70CA86BF4D |
| 8086:9d35 | 144d:c15f | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | ED50EF80EA |
| 8086:9d35 | 144d:c164 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 9DE6AF5079 |
| 8086:9d35 | 152d:1147 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 7DA5C4A4FA |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:31d0 | 8086:7270 | Intel      | SD Host Controller           | 38    | sdhci_pci  | 4DBC03E904 |
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 35    | sdhci_pci  | 4DBC03E904 |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 34    | sdhci_pci  | AA88177E76 |
| 1217:8621 | 17aa:39f6 | O2 Micro   | SD/MMC Card Reader Contro... | 22    | sdhci_pci  | 4C9743CDD1 |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 17    | sdhci_pci  | AA88177E76 |
| 8086:9d2d | 103c:8486 | Intel      | Sunrise Point-LP Secure D... | 15    | sdhci_pci  | 7E241B1F69 |
| 1217:8621 | 17aa:381b | O2 Micro   | SD/MMC Card Reader Contro... | 14    | sdhci_pci  | 426EAC3A94 |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 14    | sdhci_pci  | AA88177E76 |
| 8086:02f5 | 103c:866e | Intel      | Comet Lake PCH-LP SCS3       | 12    | sdhci_pci  | 572D5CD292 |
| 1217:8621 | 17aa:3817 | O2 Micro   | SD/MMC Card Reader Contro... | 11    | sdhci_pci  | A60117C096 |
| 8086:9d2b | 103c:8488 | Intel      | Skylake-U/Y SCC: eMMC        | 11    | sdhci_pci  | 3AF23C8E87 |
| 8086:9d2d | 103c:8488 | Intel      | Sunrise Point-LP Secure D... | 11    | sdhci_pci  | 3AF23C8E87 |
| 8086:9df5 | 103c:85c4 | Intel      | BayHubTech Integrated SD ... | 8     | sdhci_pci  | 7D9588F740 |
| 8086:02f5 | 1028:0950 | Intel      | Comet Lake PCH-LP SCS3       | 7     | sdhci_pci  | 6E2B3B5A7E |
| 1217:8621 | 17aa:3846 | O2 Micro   | SD/MMC Card Reader Contro... | 6     | sdhci_pci  | 17E78AF479 |
| 8086:31cc | 17aa:3801 | Intel      | Celeron/Pentium Silver Pr... | 6     | sdhci_pci  | 17E78AF479 |
| 8086:5aca | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 6     | sdhci_pci  | 4FD337BCA7 |
| 8086:9d2b | 1ae0:006b | Intel      | Skylake-U/Y SCC: eMMC        | 6     | sdhci_pci  | CBC1BB3811 |
| 1217:8520 | 17aa:504c | O2 Micro   | SD/MMC Card Reader Contro... | 5     | sdhci_pci  | 4983586FE5 |
| 1217:8621 | 17aa:383e | O2 Micro   | SD/MMC Card Reader Contro... | 5     | sdhci_pci  | 4EEE4B94CB |
| 17a0:9750 | 17a0:9750 | Genesys... | GL9750 SD Host Controller    | 5     | sdhci_pci  | 50C28ABBA1 |
| 8086:31cc | 1025:1316 | Intel      | Celeron/Pentium Silver Pr... | 5     | sdhci_pci  | BAB6686973 |
| 8086:5acc | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 5     | sdhci_pci  | 25A6945FC4 |
| 8086:9d2d | 103c:8487 | Intel      | Sunrise Point-LP Secure D... | 5     | sdhci_pci  | CEBF94C181 |
| 8086:9df5 | 103c:850e | Intel      | BayHubTech Integrated SD ... | 5     | sdhci_pci  | 0A3FF1EAD5 |
| 1217:8621 | 17aa:3828 | O2 Micro   | SD/MMC Card Reader Contro... | 4     | sdhci_pci  | 6E02E68ADE |
| 1217:8621 | 17aa:383b | O2 Micro   | SD/MMC Card Reader Contro... | 4     | sdhci_pci  | 14109EDFC9 |
| 8086:02f5 | 1028:0951 | Intel      | Comet Lake PCH-LP SCS3       | 4     | sdhci_pci  | 247867F57E |
| 8086:9d2d | 103c:84d8 | Intel      | Sunrise Point-LP Secure D... | 4     | sdhci_pci  | 03FE12C3CC |
| 8086:9df5 | 1028:0908 | Intel      | BayHubTech Integrated SD ... | 4     | sdhci_pci  | 81E2001F6C |
| 8086:9df5 | 103c:85c5 | Intel      | BayHubTech Integrated SD ... | 4     | sdhci_pci  | 03D484665D |
| 8086:9df5 | 103c:85c8 | Intel      | BayHubTech Integrated SD ... | 4     | sdhci_pci  | 1649B0B654 |
| 8086:9df5 | 103c:85cd | Intel      | BayHubTech Integrated SD ... | 4     | sdhci_pci  | E7DCDD4B39 |
| 8086:2294 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 3     | sdhci_pci  | D423BBA02B |
| 8086:31cc | 1028:081f | Intel      | Celeron/Pentium Silver Pr... | 3     | sdhci_pci  | D11804DA19 |
| 8086:5acc | 1043:1c80 | Intel      | Celeron N3350/Pentium N42... | 3     | sdhci_pci  | 7F25CF70DD |
| 8086:9d2d | 8086:9d2d | Intel      | Sunrise Point-LP Secure D... | 3     | sdhci_pci  | BC5D045DEF |
| 1217:8621 | 17aa:3814 | O2 Micro   | SD/MMC Card Reader Contro... | 2     | sdhci_pci  | 3C0A5BE140 |
| 8086:02f5 | 103c:8670 | Intel      | Comet Lake PCH-LP SCS3       | 2     | sdhci_pci  | 325235430E |
| 8086:02f5 | 103c:8671 | Intel      | Comet Lake PCH-LP SCS3       | 2     | sdhci_pci  | 0F145AD5EB |
| 8086:31cc | 1025:1293 | Intel      | Celeron/Pentium Silver Pr... | 2     | sdhci_pci  | 2A5DDF7BE8 |
| 8086:5aca | 103c:830d | Intel      | Celeron N3350/Pentium N42... | 2     | sdhci_pci  | 27DC03B58E |
| 8086:5acc | 1043:1d90 | Intel      | Celeron N3350/Pentium N42... | 2     | sdhci_pci  | C8D3F204E5 |
| 8086:5ad0 | 103c:830d | Intel      | Celeron N3350/Pentium N42... | 2     | sdhci_pci  | 27DC03B58E |
| 8086:9d2b |           | Intel      | Skylake-U/Y SCC: eMMC        | 2     | sdhci_pci  | C34BCC095C |
| 8086:9d2b | 8086:9d2b | Intel      | Skylake-U/Y SCC: eMMC        | 2     | sdhci_pci  | BC5D045DEF |
| 8086:9d2d |           | Intel      | Sunrise Point-LP Secure D... | 2     | sdhci_pci  | C34BCC095C |
| 8086:9df5 | 103c:85c6 | Intel      | BayHubTech Integrated SD ... | 2     | sdhci_pci  | CA868AA68C |
| 1217:8520 | 1e26:001c | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 437C9D66AA |
| 1217:8621 | 17aa:3818 | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | EC411DE2BB |
| 1217:8621 | 17aa:3837 | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | DE8ECBD462 |
| 17a0:9750 | 17aa:5078 | Genesys... | GL9750 SD Host Controller    | 1     | sdhci_pci  | 49DBAD6FDB |
| 8086:02f5 | 103c:866f | Intel      | Comet Lake PCH-LP SCS3       | 1     | sdhci_pci  | 63EBD660D8 |
| 8086:02f5 | 103c:8672 | Intel      | Comet Lake PCH-LP SCS3       | 1     | sdhci_pci  | 8E5E4CCD9B |
| 8086:02f5 | 103c:86ec | Intel      | Comet Lake PCH-LP SCS3       | 1     | sdhci_pci  | 483D4785B1 |
| 8086:02f5 | 8086:7270 | Intel      | Comet Lake PCH-LP SCS3       | 1     | sdhci_pci  | EE715DE644 |
| 8086:0f50 | 103c:802b | Intel      | Atom Processor E3800 Seri... | 1     | sdhci_pci  | 4E86625634 |
| 8086:31cc | 1025:129f | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | 0F6F9B0A03 |
| 8086:31cc | 1025:1430 | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | A5E2305F6F |
| 8086:31cc | 103c:84df | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | 5863FA858F |
| 8086:31cc | 103c:86cf | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | 33D5688BFC |
| 8086:31cc | 1043:1182 | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | DE1DE1FA76 |
| 8086:31cc | 17aa:506e | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | 65846CBF2B |
| 8086:31d0 | 103c:86cf | Intel      | SD Host Controller           | 1     | sdhci_pci  | 33D5688BFC |
| 8086:34c4 | 17aa:3801 | Intel      | Ice Lake-LP SD Host Contr... | 1     | sdhci_pci  | DE8ECBD462 |
| 8086:34f8 | 17aa:3801 | Intel      | Ice Lake-LP SD Controller    | 1     | sdhci_pci  | DE8ECBD462 |
| 8086:5acc | 1025:1148 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | C55FC9990D |
| 8086:5acc | 1025:1150 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 97DFF84E2B |
| 8086:5acc | 1043:1930 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | B6FC10EFA8 |
| 8086:5acc | 1043:1d60 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 45B1907784 |
| 8086:9d2b | 8086:7270 | Intel      | Skylake-U/Y SCC: eMMC        | 1     | sdhci_pci  | C78BE59C16 |
| 8086:9d2d | 103c:8491 | Intel      | Sunrise Point-LP Secure D... | 1     | sdhci_pci  | 8CE6E9CB36 |
| 8086:9dc4 | 8086:7270 | Intel      | 300 Series Chipset SD Hos... | 1     | sdhci_pci  | DC14D7EC63 |
| 8086:9df5 | 103c:850f | Intel      | BayHubTech Integrated SD ... | 1     | sdhci_pci  | 606B3CF160 |
| 8086:9df5 | 8086:7270 | Intel      | BayHubTech Integrated SD ... | 1     | sdhci_pci  | DC14D7EC63 |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a0a4 | 17aa:5089 | Intel      | Tiger Lake-LP SPI Controller | 59    | intel_s... | 1EC4861E97 |
| 8086:02a4 | 17aa:3804 | Intel      | Comet Lake SPI (flash) Co... | 33    | intel_s... | 6F6E5DAF18 |
| 8086:02c5 | 17aa:3802 | Intel      | Comet Lake Serial IO I2C ... | 33    | intel_lpss | 6F6E5DAF18 |
| 8086:02e8 | 17aa:3807 | Intel      | Serial IO I2C Host Contro... | 33    | intel_lpss | 6F6E5DAF18 |
| 8086:02e9 | 17aa:3802 | Intel      | Comet Lake Serial IO I2C ... | 33    | intel_lpss | 6F6E5DAF18 |
| 8086:9da4 | 8086:9da4 | Intel      | Cannon Point-LP SPI Contr... | 29    |            | 4C9743CDD1 |
| 8086:34a4 | 17aa:3804 | Intel      | Ice Lake-LP SPI Controller   | 25    | intel_s... | 740EA7B2E9 |
| 8086:34e8 | 17aa:3806 | Intel      | Ice Lake-LP Serial IO I2C... | 25    | intel_l... | 740EA7B2E9 |
| 8086:34e9 | 17aa:3801 | Intel      | Ice Lake-LP Serial IO I2C... | 25    | intel_l... | 740EA7B2E9 |
| 8086:9da4 | 103c:8514 | Intel      | Cannon Point-LP SPI Contr... | 25    |            | 211EF30EF4 |
| 8086:9de8 | 103c:8514 | Intel      | Cannon Point-LP Serial IO... | 25    | intel_l... | 211EF30EF4 |
| 8086:9de8 | 17aa:380b | Intel      | Cannon Point-LP Serial IO... | 25    | intel_l... | 4C9743CDD1 |
| 8086:9de9 | 103c:8514 | Intel      | Cannon Point-LP Serial IO... | 25    | intel_l... | 211EF30EF4 |
| 8086:9de9 | 17aa:3804 | Intel      | Cannon Point-LP Serial IO... | 25    | intel_l... | 4C9743CDD1 |
| 8086:9dea | 17aa:3802 | Intel      | 8th Gen Intel Core Proces... | 25    | intel_l... | 4C9743CDD1 |
| 8086:34a4 | 1028:08b0 | Intel      | Ice Lake-LP SPI Controller   | 23    | intel_s... | 138EC046F1 |
| 8086:34e8 | 1028:08b0 | Intel      | Ice Lake-LP Serial IO I2C... | 23    | intel_l... | 138EC046F1 |
| 8086:34e9 | 1028:08b0 | Intel      | Ice Lake-LP Serial IO I2C... | 23    | intel_l... | 138EC046F1 |
| 8086:34eb | 1028:08b0 | Intel      | Ice Lake-LP Serial IO I2C... | 23    | intel_l... | 138EC046F1 |
| 8086:34a4 | 17aa:3812 | Intel      | Ice Lake-LP SPI Controller   | 18    | intel_s... | D1DD92D46E |
| 8086:34e8 | 17aa:3840 | Intel      | Ice Lake-LP Serial IO I2C... | 18    | intel_l... | D1DD92D46E |
| 8086:34e9 | 17aa:3841 | Intel      | Ice Lake-LP Serial IO I2C... | 18    | intel_l... | D1DD92D46E |
| 8086:34ea | 17aa:3842 | Intel      | Ice Lake-LP Serial IO I2C... | 18    | intel_l... | D1DD92D46E |
| 8086:9da4 | 8086:7270 | Intel      | Cannon Point-LP SPI Contr... | 18    |            | 71FB7C2C92 |
| 8086:9da4 | 17aa:2292 | Intel      | Cannon Point-LP SPI Contr... | 17    |            | D99F5CBFD2 |
| 8086:9de8 | 17aa:2292 | Intel      | Cannon Point-LP Serial IO... | 17    | intel_l... | D99F5CBFD2 |
| 8086:9de9 | 17aa:2292 | Intel      | Cannon Point-LP Serial IO... | 17    | intel_l... | D99F5CBFD2 |
| 8086:a0a4 | 1028:0a05 | Intel      | Tiger Lake-LP SPI Controller | 16    |            | 928665D302 |
| 8086:a0a4 | 17aa:381b | Intel      | Tiger Lake-LP SPI Controller | 16    |            | 7851B07853 |
| 8086:a0ab | 17aa:3822 | Intel      | Tiger Lake-LP Serial IO S... | 16    | intel_lpss | 7851B07853 |
| 8086:a0e8 | 1028:0a05 | Intel      | Tiger Lake-LP Serial IO I... | 16    | intel_l... | 928665D302 |
| 8086:a0e8 | 17aa:3841 | Intel      | Tiger Lake-LP Serial IO I... | 16    | intel_lpss | 7851B07853 |
| 8086:a0e9 | 1028:0a05 | Intel      | Tiger Lake-LP Serial IO I... | 16    | intel_l... | 928665D302 |
| 8086:a0e9 | 17aa:3842 | Intel      | Tiger Lake-LP Serial IO I... | 16    | intel_lpss | 7851B07853 |
| 8086:02a4 | 17aa:3806 | Intel      | Comet Lake SPI (flash) Co... | 15    | intel_s... | 527CC99B36 |
| 8086:02e8 | 17aa:3806 | Intel      | Serial IO I2C Host Contro... | 15    | intel_l... | 527CC99B36 |
| 8086:02e9 | 17aa:3806 | Intel      | Comet Lake Serial IO I2C ... | 15    | intel_l... | 527CC99B36 |
| 8086:a0a4 | 1028:09ff | Intel      | Tiger Lake-LP SPI Controller | 14    |            | 5B10037DA5 |
| 8086:a0e8 | 1028:09ff | Intel      | Tiger Lake-LP Serial IO I... | 14    | intel_lpss | 5B10037DA5 |
| 8086:a0e9 | 1028:09ff | Intel      | Tiger Lake-LP Serial IO I... | 14    | intel_lpss | 5B10037DA5 |
| 8086:02a4 | 17aa:5078 | Intel      | Comet Lake SPI (flash) Co... | 13    | intel_s... | 49DBAD6FDB |
| 8086:02e8 | 17aa:5078 | Intel      | Serial IO I2C Host Contro... | 13    | intel_l... | 49DBAD6FDB |
| 8086:02a4 | 103c:866e | Intel      | Comet Lake SPI (flash) Co... | 12    | intel_s... | 572D5CD292 |
| 8086:02e8 | 103c:866e | Intel      | Serial IO I2C Host Contro... | 12    | intel_l... | 572D5CD292 |
| 8086:02e9 | 103c:866e | Intel      | Comet Lake Serial IO I2C ... | 12    | intel_l... | 572D5CD292 |
| 8086:a0a4 | 1028:09de | Intel      | Tiger Lake-LP SPI Controller | 12    | intel_spi  | 224CE9A44D |
| 8086:a0a4 | 17aa:3807 | Intel      | Tiger Lake-LP SPI Controller | 12    | intel_s... | 00AC329183 |
| 8086:a0e8 | 1028:09de | Intel      | Tiger Lake-LP Serial IO I... | 12    | intel_l... | 224CE9A44D |
| 8086:a0e8 | 17aa:3832 | Intel      | Tiger Lake-LP Serial IO I... | 12    | intel_lpss | 00AC329183 |
| 8086:a0e9 | 1028:09de | Intel      | Tiger Lake-LP Serial IO I... | 12    | intel_l... | 224CE9A44D |
| 8086:a0e9 | 17aa:3833 | Intel      | Tiger Lake-LP Serial IO I... | 12    | intel_lpss | 00AC329183 |
| 8086:a0ea | 17aa:3834 | Intel      | Tiger Lake-LP Serial IO I... | 12    | intel_lpss | 00AC329183 |
| 8086:a0eb | 17aa:3835 | Intel      | Tiger Lake-LP Serial IO I... | 12    | intel_lpss | 00AC329183 |
| 8086:a0a4 | 1028:09dd | Intel      | Tiger Lake-LP SPI Controller | 10    | intel_s... | 044E6AFDF4 |
| 8086:a0e8 | 1028:09dd | Intel      | Tiger Lake-LP Serial IO I... | 10    | intel_l... | 044E6AFDF4 |
| 8086:a0e9 | 1028:09dd | Intel      | Tiger Lake-LP Serial IO I... | 10    | intel_l... | 044E6AFDF4 |
| 8086:02a4 | 103c:86b1 | Intel      | Comet Lake SPI (flash) Co... | 9     | intel_spi  | F3B0D882C2 |
| 8086:02a4 | 103c:86b2 | Intel      | Comet Lake SPI (flash) Co... | 9     |            | B054E02856 |
| 8086:02e8 | 103c:86b1 | Intel      | Serial IO I2C Host Contro... | 9     | intel_l... | F3B0D882C2 |
| 8086:02e8 | 103c:86b2 | Intel      | Serial IO I2C Host Contro... | 9     | intel_l... | B054E02856 |
| 8086:02e9 | 103c:86b1 | Intel      | Comet Lake Serial IO I2C ... | 9     | intel_l... | F3B0D882C2 |
| 8086:02e9 | 103c:86b2 | Intel      | Comet Lake Serial IO I2C ... | 9     | intel_l... | B054E02856 |
| 8086:34a4 | 103c:86f9 | Intel      | Ice Lake-LP SPI Controller   | 9     | intel_s... | 4967676215 |
| 8086:34e8 | 103c:86f9 | Intel      | Ice Lake-LP Serial IO I2C... | 9     | intel_l... | 4967676215 |
| 8086:34e9 | 103c:86f9 | Intel      | Ice Lake-LP Serial IO I2C... | 9     | intel_l... | 4967676215 |
| 8086:9da4 | 1028:0894 | Intel      | Cannon Point-LP SPI Contr... | 9     |            | B07A0CF706 |
| 8086:9da4 | 103c:861f | Intel      | Cannon Point-LP SPI Contr... | 9     |            | 48CABEDB1E |
| 8086:9de8 | 1028:0894 | Intel      | Cannon Point-LP Serial IO... | 9     | intel_l... | B07A0CF706 |
| 8086:9de8 | 103c:861f | Intel      | Cannon Point-LP Serial IO... | 9     | intel_l... | 48CABEDB1E |
| 8086:9de9 | 1028:0894 | Intel      | Cannon Point-LP Serial IO... | 9     | intel_l... | B07A0CF706 |
| 8086:9de9 | 103c:861f | Intel      | Cannon Point-LP Serial IO... | 9     | intel_l... | 48CABEDB1E |
| 8086:02a4 | 1028:095d | Intel      | Comet Lake SPI (flash) Co... | 8     |            | E85575B823 |
| 8086:02a4 | 103c:863f | Intel      | Comet Lake SPI (flash) Co... | 8     |            | 2A2CFDB7D4 |
| 8086:02e8 | 1028:095d | Intel      | Serial IO I2C Host Contro... | 8     | intel_l... | E85575B823 |
| 8086:02e8 | 103c:863f | Intel      | Serial IO I2C Host Contro... | 8     | intel_l... | 2A2CFDB7D4 |
| 8086:02e9 | 1028:095d | Intel      | Comet Lake Serial IO I2C ... | 8     | intel_l... | E85575B823 |
| 8086:02e9 | 103c:863f | Intel      | Comet Lake Serial IO I2C ... | 8     | intel_l... | 2A2CFDB7D4 |
| 8086:9da4 | 103c:85c4 | Intel      | Cannon Point-LP SPI Contr... | 8     |            | 7D9588F740 |
| 8086:9da4 | 1043:19d1 | Intel      | Cannon Point-LP SPI Contr... | 8     |            | DBBD7A332E |
| 8086:9da4 | 17aa:5077 | Intel      | Cannon Point-LP SPI Contr... | 8     |            | B9971B685A |
| 8086:9dab | 1043:19d1 | Intel      | 8th Gen Intel Core Proces... | 8     | intel_lpss | DBBD7A332E |
| 8086:9de8 | 103c:85c4 | Intel      | Cannon Point-LP Serial IO... | 8     | intel_lpss | 7D9588F740 |
| 8086:9de8 | 1043:19d1 | Intel      | Cannon Point-LP Serial IO... | 8     | intel_lpss | DBBD7A332E |
| 8086:9de8 | 17aa:5077 | Intel      | Cannon Point-LP Serial IO... | 8     | intel_lpss | B9971B685A |
| 8086:9de9 | 103c:85c4 | Intel      | Cannon Point-LP Serial IO... | 8     | intel_lpss | 7D9588F740 |
| 8086:9de9 | 1043:19d1 | Intel      | Cannon Point-LP Serial IO... | 8     | intel_lpss | DBBD7A332E |
| 8086:9de9 | 17aa:5077 | Intel      | Cannon Point-LP Serial IO... | 8     | intel_lpss | B9971B685A |
| 8086:9dea | 17aa:5077 | Intel      | 8th Gen Intel Core Proces... | 8     | intel_lpss | B9971B685A |
| 8086:02a4 | 1028:0950 | Intel      | Comet Lake SPI (flash) Co... | 7     | intel_s... | 6E2B3B5A7E |
| 8086:02a4 | 1028:09cd | Intel      | Comet Lake SPI (flash) Co... | 7     |            | 20FA4B73D7 |
| 8086:02a4 | 17aa:3803 | Intel      | Comet Lake SPI (flash) Co... | 7     | intel_spi  | 611C3C0C19 |
| 8086:02c5 | 1028:09cd | Intel      | Comet Lake Serial IO I2C ... | 7     | intel_l... | 20FA4B73D7 |
| 8086:02e8 | 1028:0950 | Intel      | Serial IO I2C Host Contro... | 7     | intel_l... | 6E2B3B5A7E |
| 8086:02e8 | 1028:09cd | Intel      | Serial IO I2C Host Contro... | 7     | intel_l... | 20FA4B73D7 |
| 8086:02e8 | 17aa:3804 | Intel      | Serial IO I2C Host Contro... | 7     | intel_l... | 611C3C0C19 |
| 8086:02e9 | 1028:0950 | Intel      | Comet Lake Serial IO I2C ... | 7     | intel_l... | 6E2B3B5A7E |
| 8086:02e9 | 1028:09cd | Intel      | Comet Lake Serial IO I2C ... | 7     | intel_l... | 20FA4B73D7 |
| 8086:02e9 | 17aa:3803 | Intel      | Comet Lake Serial IO I2C ... | 7     | intel_l... | 611C3C0C19 |
| 8086:02ea | 17aa:3806 | Intel      | Comet Lake PCH-LP LPSS: I... | 7     | intel_l... | 611C3C0C19 |
| 8086:34a4 | 1025:141f | Intel      | Ice Lake-LP SPI Controller   | 7     | intel_s... | 059B59E828 |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a0fc | 17aa:5089 | Intel      | Tiger Lake-LP Integrated ... | 59    | intel_i... | 1EC4861E97 |
| 8086:02fc | 17aa:3804 | Intel      | Comet Lake Integrated Sen... | 33    | intel_i... | 6F6E5DAF18 |
| 8086:34fc | 17aa:380e | Intel      | Ice Lake-LP Integrated Se... | 25    | intel_i... | 740EA7B2E9 |
| 8086:9dfc | 103c:8514 | Intel      | Cannon Point-LP Integrate... | 25    | intel_i... | 211EF30EF4 |
| 8086:34fc | 1028:08b0 | Intel      | Ice Lake-LP Integrated Se... | 23    | intel_i... | 138EC046F1 |
| 8086:34fc | 17aa:384d | Intel      | Ice Lake-LP Integrated Se... | 18    | intel_i... | D1DD92D46E |
| 8086:9dfc | 17aa:2292 | Intel      | Cannon Point-LP Integrate... | 17    | intel_i... | D99F5CBFD2 |
| 8086:9d3d | 103c:827d | Intel      | Sunrise Point-LP Active M... | 16    | serial     | 95D389BFE5 |
| 8086:a0fc | 1028:0a05 | Intel      | Tiger Lake-LP Integrated ... | 16    | intel_i... | 928665D302 |
| 8086:a0fc | 17aa:3850 | Intel      | Tiger Lake-LP Integrated ... | 16    | intel_i... | 7851B07853 |
| 8086:02fc | 17aa:3806 | Intel      | Comet Lake Integrated Sen... | 15    | intel_i... | 527CC99B36 |
| 8086:a0fc | 1028:09ff | Intel      | Tiger Lake-LP Integrated ... | 14    | intel_i... | 5B10037DA5 |
| 8086:02fc | 17aa:5078 | Intel      | Comet Lake Integrated Sen... | 13    | intel_i... | 49DBAD6FDB |
| 8086:9dfc | 8086:7270 | Intel      | Cannon Point-LP Integrate... | 13    | intel_i... | 71FB7C2C92 |
| 8086:02fc | 103c:866e | Intel      | Comet Lake Integrated Sen... | 12    | intel_i... | 572D5CD292 |
| 8086:a0fc | 1028:09de | Intel      | Tiger Lake-LP Integrated ... | 12    | intel_i... | 224CE9A44D |
| 8086:a0fc | 17aa:3841 | Intel      | Tiger Lake-LP Integrated ... | 12    | intel_i... | 00AC329183 |
| 8086:a0fc | 1028:09dd | Intel      | Tiger Lake-LP Integrated ... | 10    | intel_i... | 044E6AFDF4 |
| 8086:02fc | 103c:86b1 | Intel      | Comet Lake Integrated Sen... | 9     | intel_i... | F3B0D882C2 |
| 8086:02fc | 103c:86b2 | Intel      | Comet Lake Integrated Sen... | 9     | intel_i... | B054E02856 |
| 8086:34fc | 103c:86f9 | Intel      | Ice Lake-LP Integrated Se... | 9     | intel_i... | 4967676215 |
| 8086:9dfc | 1028:0894 | Intel      | Cannon Point-LP Integrate... | 9     | intel_i... | B07A0CF706 |
| 8086:9dfc | 103c:861f | Intel      | Cannon Point-LP Integrate... | 9     | intel_i... | 48CABEDB1E |
| 8086:02fc | 1028:095d | Intel      | Comet Lake Integrated Sen... | 8     | intel_i... | E85575B823 |
| 8086:02fc | 103c:863f | Intel      | Comet Lake Integrated Sen... | 8     | intel_i... | 2A2CFDB7D4 |
| 8086:9dfc | 103c:85c4 | Intel      | Cannon Point-LP Integrate... | 8     | intel_i... | 7D9588F740 |
| 8086:9dfc | 1043:19d1 | Intel      | Cannon Point-LP Integrate... | 8     | intel_i... | DBBD7A332E |
| 8086:9dfc | 17aa:5077 | Intel      | Cannon Point-LP Integrate... | 8     | intel_i... | B9971B685A |
| 8086:02fc | 1028:0950 | Intel      | Comet Lake Integrated Sen... | 7     | intel_i... | 6E2B3B5A7E |
| 8086:02fc | 1028:09cd | Intel      | Comet Lake Integrated Sen... | 7     | intel_i... | 20FA4B73D7 |
| 8086:9d3d | 17aa:2259 | Intel      | Sunrise Point-LP Active M... | 7     | serial     | A3D7B44215 |
| 8086:9d3d | 17aa:5061 | Intel      | Sunrise Point-LP Active M... | 7     | serial     | 16AC72B8EA |
| 8086:9dfc | 103c:857f | Intel      | Cannon Point-LP Integrate... | 7     | intel_i... | 465B51ACD4 |
| 8086:a0fc | 1028:09df | Intel      | Tiger Lake-LP Integrated ... | 7     | intel_i... | 69D2B432F7 |
| 8086:a0fc | 103c:8709 | Intel      | Tiger Lake-LP Integrated ... | 7     | intel_i... | 444E13B5ED |
| 8086:a0fc | 103c:87f4 | Intel      | Tiger Lake-LP Integrated ... | 7     | intel_i... | 6461BFC243 |
| 8086:a0fc | 17aa:3801 | Intel      | Tiger Lake-LP Integrated ... | 7     | intel_i... | 5B06944051 |
| 8086:02fc | 17aa:2292 | Intel      | Comet Lake Integrated Sen... | 6     | intel_i... | 8F10E30326 |
| 8086:02fc | 17aa:22be | Intel      | Comet Lake Integrated Sen... | 6     | intel_i... | 65033505B7 |
| 8086:9d3d | 17aa:224e | Intel      | Sunrise Point-LP Active M... | 6     | serial     | B866426527 |
| 8086:9d3d | 17aa:506d | Intel      | Sunrise Point-LP Active M... | 6     | serial     | 99C878CD5E |
| 8086:9de3 | 17aa:2292 | Intel      | Cannon Point-LP Keyboard ... | 6     | serial     | D99F5CBFD2 |
| 8086:9dfc | 1028:089e | Intel      | Cannon Point-LP Integrate... | 6     | intel_i... | C52711AB47 |
| 8086:9dfc | 1028:08e2 | Intel      | Cannon Point-LP Integrate... | 6     | intel_i... | ADF32CA36B |
| 8086:a0fc | 103c:87f7 | Intel      | Tiger Lake-LP Integrated ... | 6     | intel_i... | E1D0678746 |
| 8086:02fc | 1028:0960 | Intel      | Comet Lake Integrated Sen... | 5     | intel_i... | 40A7A1942F |
| 8086:02fc | 17aa:22ad | Intel      | Comet Lake Integrated Sen... | 5     | intel_i... | 50C28ABBA1 |
| 8086:34fc | 103c:86fa | Intel      | Ice Lake-LP Integrated Se... | 5     | intel_i... | 635BBB6F75 |
| 8086:9d3d | 17aa:2238 | Intel      | Sunrise Point-LP Active M... | 5     | serial     | 6D60BDA741 |
| 8086:9de3 | 1028:08e2 | Intel      | Cannon Point-LP Keyboard ... | 5     | serial     | ADF32CA36B |
| 8086:9dfc | 1028:0895 | Intel      | Cannon Point-LP Integrate... | 5     | intel_i... | 5A60912D9F |
| 8086:9dfc | 1028:0896 | Intel      | Cannon Point-LP Integrate... | 5     | intel_i... | 4D7F19A11A |
| 8086:9dfc | 1028:08b6 | Intel      | Cannon Point-LP Integrate... | 5     | intel_i... | B0722E1B57 |
| 8086:9dfc | 103c:850e | Intel      | Cannon Point-LP Integrate... | 5     | intel_i... | 0A3FF1EAD5 |
| 8086:9dfc | 103c:85e7 | Intel      | Cannon Point-LP Integrate... | 5     | intel_i... | 169477DE3F |
| 8086:9dfc | 17aa:2294 | Intel      | Cannon Point-LP Integrate... | 5     | intel_i... | 3C03CE796F |
| 8086:a0fc | 103c:8825 | Intel      | Tiger Lake-LP Integrated ... | 5     | intel_i... | 24060045B4 |
| 8086:02e3 | 1028:09cd | Intel      | Comet Lake PCH-LP Keyboar... | 4     | serial     | E4ABE2A187 |
| 8086:02fc | 1028:0951 | Intel      | Comet Lake Integrated Sen... | 4     | intel_i... | 247867F57E |
| 8086:02fc | 1028:09c6 | Intel      | Comet Lake Integrated Sen... | 4     | intel_i... | F146E46238 |
| 8086:02fc | 103c:876d | Intel      | Comet Lake Integrated Sen... | 4     | intel_i... | CA10831A1E |
| 8086:02fc | 8086:7270 | Intel      | Comet Lake Integrated Sen... | 4     | intel_i... | 49B0F21555 |
| 8086:34fc | 103c:875b | Intel      | Ice Lake-LP Integrated Se... | 4     | intel_i... | 258D846B85 |
| 8086:34fc | 103c:8774 | Intel      | Ice Lake-LP Integrated Se... | 4     | intel_i... | 1E2B68B7D8 |
| 8086:9d3d | 103c:8438 | Intel      | Sunrise Point-LP Active M... | 4     | serial     | AF74E3A1EA |
| 8086:9dfc | 1028:0908 | Intel      | Cannon Point-LP Integrate... | 4     | intel_i... | 81E2001F6C |
| 8086:9dfc | 103c:850c | Intel      | Cannon Point-LP Integrate... | 4     | intel_i... | EEC05D1BF9 |
| 8086:9dfc | 103c:8518 | Intel      | Cannon Point-LP Integrate... | 4     | intel_i... | 64C5568456 |
| 8086:9dfc | 103c:8548 | Intel      | Cannon Point-LP Integrate... | 4     | intel_i... | A2F9CA954A |
| 8086:9dfc | 103c:85c5 | Intel      | Cannon Point-LP Integrate... | 4     | intel_i... | 03D484665D |
| 8086:9dfc | 103c:85c8 | Intel      | Cannon Point-LP Integrate... | 4     | intel_i... | 1649B0B654 |
| 8086:9dfc | 103c:85cd | Intel      | Cannon Point-LP Integrate... | 4     | intel_i... | E7DCDD4B39 |
| 8086:a0fc | 1028:0a5b | Intel      | Tiger Lake-LP Integrated ... | 4     | intel_i... | 062C3B976F |
| 8086:a37c | 103c:863e | Intel      | VROC Virtual Controller      | 4     | intel_i... | B47C4EF32E |
| 8086:02fc | 103c:86e5 | Intel      | Comet Lake Integrated Sen... | 3     | intel_i... | 54DDD1BAEA |
| 8086:06fc | 17aa:3801 | Intel      | 400 Series Chipset Family... | 3     | intel_i... | 783EE80F63 |
| 8086:9d3d | 1028:07aa | Intel      | Sunrise Point-LP Active M... | 3     | serial     | 5492FDD780 |
| 8086:9d3d | 103c:8470 | Intel      | Sunrise Point-LP Active M... | 3     | serial     | 3AF4716969 |
| 8086:9dfc | 1028:089f | Intel      | Cannon Point-LP Integrate... | 3     | intel_i... | DDC277B9F6 |
| 8086:9dfc | 1028:0907 | Intel      | Cannon Point-LP Integrate... | 3     | intel_i... | B6EB2D9514 |
| 8086:9dfc | 103c:850d | Intel      | Cannon Point-LP Integrate... | 3     | intel_i... | 987181B525 |
| 8086:9dfc | 103c:8637 | Intel      | Cannon Point-LP Integrate... | 3     | intel_i... | F30D3F55AD |
| 8086:a0fc | 103c:8811 | Intel      | Tiger Lake-LP Integrated ... | 3     | intel_i... | 5E31F081A4 |
| 8086:a0fc | 144d:c1a5 | Intel      | Tiger Lake-LP Integrated ... | 3     | intel_i... | F39DEDA45C |
| 8086:a37c | 103c:844f | Intel      | VROC Virtual Controller      | 3     | intel_i... | 2668A6580A |
| 8086:a37c | 17aa:3803 | Intel      | VROC Virtual Controller      | 3     | intel_i... | F1C4AE114C |
| 8086:02e3 | 1028:09c6 | Intel      | Comet Lake PCH-LP Keyboar... | 2     | serial     | F146E46238 |
| 8086:02e3 | 17aa:22ad | Intel      | Comet Lake PCH-LP Keyboar... | 2     | serial     | 18DF123A3F |
| 8086:02fc | 103c:8670 | Intel      | Comet Lake Integrated Sen... | 2     | intel_i... | 325235430E |
| 8086:02fc | 103c:8671 | Intel      | Comet Lake Integrated Sen... | 2     | intel_i... | 0F145AD5EB |
| 8086:02fc | 103c:8725 | Intel      | Comet Lake Integrated Sen... | 2     | intel_i... | C617B180A8 |
| 8086:34fc | 1028:09dc | Intel      | Ice Lake-LP Integrated Se... | 2     | intel_i... | 889499B855 |
| 8086:34fc | 1028:09e0 | Intel      | Ice Lake-LP Integrated Se... | 2     | intel_i... | E6123179C2 |
| 8086:34fc | 144d:c188 | Intel      | Ice Lake-LP Integrated Se... | 2     | intel_i... | 2169C592D9 |
| 8086:9de3 | 1028:08b6 | Intel      | Cannon Point-LP Keyboard ... | 2     | serial     | ADBA0A4782 |
| 8086:9de3 | 103c:861f | Intel      | Cannon Point-LP Keyboard ... | 2     | serial     | CE851E2475 |
| 8086:9dfc | 103c:85c6 | Intel      | Cannon Point-LP Integrate... | 2     | intel_i... | CA868AA68C |
| 8086:9dfc | 103c:85e6 | Intel      | Cannon Point-LP Integrate... | 2     | intel_i... | 0A7C046DCE |
| 8086:a0e3 | 1028:0a5b | Intel      | Tiger Lake-LP Active Mana... | 2     | serial     | 062C3B976F |
| 8086:a0fc | 1028:0a37 | Intel      | Tiger Lake-LP Integrated ... | 2     | intel_i... | C5856B1EA0 |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15e4 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Senso... | 99    | amd_sfh    | 65A49B7280 |
| 8086:9a03 | 17aa:5089 | Intel      | TigerLake-LP Dynamic Tuni... | 59    | process... | 1EC4861E97 |
| 8086:9d31 | 17aa:3830 | Intel      | Sunrise Point-LP Thermal ... | 44    | intel_p... | A2717638BE |
| 8086:9d60 | 17aa:3837 | Intel      | Sunrise Point-LP Serial I... | 44    | intel_l... | A2717638BE |
| 8086:9d61 | 17aa:3836 | Intel      | Sunrise Point-LP Serial I... | 44    | intel_l... | A2717638BE |
| 8086:9d62 | 17aa:3809 | Intel      | Sunrise Point-LP Serial I... | 44    | intel_l... | A2717638BE |
| 1022:15e4 | 103c:876e | AMD        | Raven/Raven2/Renoir Senso... | 38    | amd_sfh    | 28B152BB19 |
| 8086:318c | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 38    | process... | 4DBC03E904 |
| 8086:31ac | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 38    | intel_l... | 4DBC03E904 |
| 8086:31ae | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 38    | intel_l... | 4DBC03E904 |
| 8086:31b0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 38    | intel_l... | 4DBC03E904 |
| 8086:31b2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 38    | intel_l... | 4DBC03E904 |
| 8086:31b4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 38    | intel_l... | 4DBC03E904 |
| 8086:31b6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 38    | intel_l... | 4DBC03E904 |
| 8086:31b8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 38    | intel_l... | 4DBC03E904 |
| 8086:31ba | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 38    | intel_l... | 4DBC03E904 |
| 8086:31bc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 38    | intel_l... | 4DBC03E904 |
| 8086:31be | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 38    | intel_l... | 4DBC03E904 |
| 8086:31c0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 38    | intel_l... | 4DBC03E904 |
| 8086:31c2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 38    | intel_l... | 4DBC03E904 |
| 8086:31c4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 38    | intel_l... | 4DBC03E904 |
| 8086:31c6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 38    | intel_l... | 4DBC03E904 |
| 8086:31ee | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 38    | intel_l... | 4DBC03E904 |
| 1022:15e4 | 103c:876f | AMD        | Raven/Raven2/Renoir Senso... | 34    | amd_sfh    | 5F67B298AB |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 34    | intel_l... | AA88177E76 |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 34    | intel_l... | AA88177E76 |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 34    | intel_l... | AA88177E76 |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 34    | intel_l... | AA88177E76 |
| 8086:02f9 | 17aa:3804 | Intel      | Comet Lake Thermal Subsytem  | 33    | intel_p... | 6F6E5DAF18 |
| 8086:1903 | 17aa:3832 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 33    | process... | 6F6E5DAF18 |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 33    | intel_l... | AA88177E76 |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 33    | intel_l... | AA88177E76 |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 33    | intel_l... | AA88177E76 |
| 8086:5a8c |           | Intel      | Atom/Celeron/Pentium Dyna... | 31    | process... | AA88177E76 |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 30    | intel_l... | AA88177E76 |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 30    | intel_l... | AA88177E76 |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 30    | intel_l... | AA88177E76 |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 30    | intel_l... | AA88177E76 |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 30    | intel_l... | AA88177E76 |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 30    | intel_l... | AA88177E76 |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 30    | intel_l... | AA88177E76 |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 30    | intel_l... | AA88177E76 |
| 8086:9d66 | 17aa:3810 | Intel      | Sunrise Point-LP Serial I... | 29    | intel_l... | A52209C9F2 |
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 27    | process... | 74FE90715F |
| 8086:1903 | 103c:83b9 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 26    | process... | BBB2DB43B4 |
| 8086:9d27 | 103c:83b9 | Intel      | Sunrise Point-LP Serial I... | 26    | intel_l... | BBB2DB43B4 |
| 8086:9d29 | 103c:83b9 | Intel      | Sunrise Point-LP Serial I... | 26    | intel_l... | BBB2DB43B4 |
| 8086:9d31 | 103c:83b9 | Intel      | Sunrise Point-LP Thermal ... | 26    | intel_p... | BBB2DB43B4 |
| 8086:9d60 | 103c:83b9 | Intel      | Sunrise Point-LP Serial I... | 26    | intel_l... | BBB2DB43B4 |
| 8086:1903 | 103c:8514 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 25    | process... | 211EF30EF4 |
| 8086:1903 | 17aa:3829 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 25    | process... | 4C9743CDD1 |
| 8086:8a03 | 17aa:3809 | Intel      | Ice Lake Dynamic Platform... | 25    | process... | 740EA7B2E9 |
| 8086:9df9 | 103c:8514 | Intel      | Cannon Point-LP Thermal C... | 25    | intel_p... | 211EF30EF4 |
| 8086:9df9 | 17aa:380a | Intel      | Cannon Point-LP Thermal C... | 25    | intel_p... | 4C9743CDD1 |
| 8086:1903 | 17aa:2292 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 23    | process... | 8F10E30326 |
| 8086:8a03 | 1028:08b0 | Intel      | Ice Lake Dynamic Platform... | 23    | process... | 138EC046F1 |
| 8086:9d27 |           | Intel      | Sunrise Point-LP Serial I... | 23    | intel_lpss | 06E7A51D6A |
| 8086:9d31 | 17aa:2238 | Intel      | Sunrise Point-LP Thermal ... | 22    | intel_p... | DD105BA06B |
| 8086:1903 | 17aa:3819 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 21    | process... | 72617E5DD9 |
| 8086:9d29 |           | Intel      | Sunrise Point-LP Serial I... | 21    | intel_lpss | 06E7A51D6A |
| 8086:9d31 | 17aa:3854 | Intel      | Sunrise Point-LP Thermal ... | 21    | intel_p... | 72617E5DD9 |
| 8086:9d60 | 17aa:3859 | Intel      | Sunrise Point-LP Serial I... | 21    | intel_l... | 72617E5DD9 |
| 8086:9d61 | 17aa:3855 | Intel      | Sunrise Point-LP Serial I... | 21    | intel_l... | 72617E5DD9 |
| 8086:1903 | 17aa:381c | Intel      | Xeon E3-1200 v5/E3-1500 v... | 20    | process... | A52209C9F2 |
| 8086:9d31 | 17aa:385a | Intel      | Sunrise Point-LP Thermal ... | 20    | intel_p... | A52209C9F2 |
| 8086:9d60 | 17aa:385f | Intel      | Sunrise Point-LP Serial I... | 20    | intel_l... | A52209C9F2 |
| 8086:9d61 | 17aa:3857 | Intel      | Sunrise Point-LP Serial I... | 20    | intel_l... | A52209C9F2 |
| 8086:9d63 | 17aa:3809 | Intel      | Sunrise Point-LP Serial I... | 20    | intel_l... | A52209C9F2 |
| 8086:8a03 | 17aa:3802 | Intel      | Ice Lake Dynamic Platform... | 18    | process... | D1DD92D46E |
| 8086:9d31 | 103c:827d | Intel      | Sunrise Point-LP Thermal ... | 18    | intel_p... | 95D389BFE5 |
| 8086:9d60 | 103c:827d | Intel      | Sunrise Point-LP Serial I... | 18    | intel_l... | 95D389BFE5 |
| 8086:9d61 | 103c:827d | Intel      | Sunrise Point-LP Serial I... | 18    | intel_l... | 95D389BFE5 |
| 8086:9d62 | 103c:827d | Intel      | Sunrise Point-LP Serial I... | 18    | intel_l... | 95D389BFE5 |
| 8086:1903 | 103c:827d | Intel      | Xeon E3-1200 v5/E3-1500 v... | 17    | process... | 95D389BFE5 |
| 8086:9df9 | 17aa:2292 | Intel      | Cannon Point-LP Thermal C... | 17    | intel_p... | D99F5CBFD2 |
| 8086:1903 | 17aa:3808 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 16    | process... | 611C3C0C19 |
| 8086:9a03 | 1028:0a05 | Intel      | TigerLake-LP Dynamic Tuni... | 16    | process... | 928665D302 |
| 8086:9a03 | 17aa:3805 | Intel      | TigerLake-LP Dynamic Tuni... | 16    | process... | 7851B07853 |
| 8086:9a0d | 1028:0a05 | Intel      | Tigerlake Telemetry Aggre... | 16    | intel_pmt  | 928665D302 |
| 8086:9a0d | 17aa:380e | Intel      | Tigerlake Telemetry Aggre... | 16    | intel_pmt  | 7851B07853 |
| 8086:9d31 | 17aa:380b | Intel      | Sunrise Point-LP Thermal ... | 16    | intel_p... | 350D402895 |
| 8086:9d60 | 17aa:3811 | Intel      | Sunrise Point-LP Serial I... | 16    | intel_l... | 350D402895 |
| 8086:9d61 | 17aa:3811 | Intel      | Sunrise Point-LP Serial I... | 16    | intel_l... | 350D402895 |
| 8086:02f9 | 17aa:3806 | Intel      | Comet Lake Thermal Subsytem  | 15    | intel_p... | 527CC99B36 |
| 8086:1903 | 1028:077a | Intel      | Xeon E3-1200 v5/E3-1500 v... | 15    | process... | 8F7ADB6CD3 |
| 8086:1903 | 103c:830f | Intel      | Xeon E3-1200 v5/E3-1500 v... | 15    | process... | 3286ED83B9 |
| 8086:1903 | 103c:8486 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 15    | process... | 7E241B1F69 |
| 8086:1903 | 17aa:3806 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 15    | process... | 527CC99B36 |
| 8086:1903 | 17aa:3809 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 15    | process... | C362C8CAFD |
| 8086:9d27 | 103c:8486 | Intel      | Sunrise Point-LP Serial I... | 15    | intel_l... | 7E241B1F69 |
| 8086:9d27 | 17aa:381d | Intel      | Sunrise Point-LP Serial I... | 15    | intel_l... | AED568D94C |
| 8086:9d31 | 1028:077a | Intel      | Sunrise Point-LP Thermal ... | 15    | intel_p... | 8F7ADB6CD3 |
| 8086:9d31 | 103c:830f | Intel      | Sunrise Point-LP Thermal ... | 15    | intel_p... | 3286ED83B9 |
| 8086:9d31 | 103c:8486 | Intel      | Sunrise Point-LP Thermal ... | 15    | intel_p... | 7E241B1F69 |
| 8086:9d31 | 17aa:3819 | Intel      | Sunrise Point-LP Thermal ... | 15    | intel_p... | AED568D94C |
| 8086:9d60 | 1028:077a | Intel      | Sunrise Point-LP Serial I... | 15    | intel_l... | 8F7ADB6CD3 |
| 8086:9d60 | 103c:830f | Intel      | Sunrise Point-LP Serial I... | 15    | intel_l... | 3286ED83B9 |
| 8086:9d60 | 103c:8486 | Intel      | Sunrise Point-LP Serial I... | 15    | intel_l... | 7E241B1F69 |
| 8086:9d60 | 17aa:381d | Intel      | Sunrise Point-LP Serial I... | 15    | intel_l... | AED568D94C |
| 8086:9d61 | 1028:077a | Intel      | Sunrise Point-LP Serial I... | 15    | intel_l... | 8F7ADB6CD3 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:790b | 17aa:382e | AMD        | FCH SMBus Controller         | 64    | i2c_pii... | F07B9B77F5 |
| 8086:a0a3 | 17aa:5089 | Intel      | Tiger Lake-LP SMBus Contr... | 59    | i2c_i801   | 1EC4861E97 |
| 8086:9d23 | 17aa:3840 | Intel      | Sunrise Point-LP SMBus       | 44    | i2c_i801   | A2717638BE |
| 1022:790b | 103c:876e | AMD        | FCH SMBus Controller         | 38    | i2c_piix4  | 28B152BB19 |
| 8086:31d4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 38    | i2c_i801   | 4DBC03E904 |
| 1022:790b | 103c:876f | AMD        | FCH SMBus Controller         | 34    | i2c_piix4  | 5F67B298AB |
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 34    | i2c_i801   | AA88177E76 |
| 8086:02a3 | 17aa:3803 | Intel      | Comet Lake PCH-LP SMBus H... | 33    | i2c_i801   | 6F6E5DAF18 |
| 8086:9d23 | 103c:83b9 | Intel      | Sunrise Point-LP SMBus       | 26    | i2c_i801   | BBB2DB43B4 |
| 8086:34a3 | 17aa:3813 | Intel      | Ice Lake-LP SMBus Controller | 25    | i2c_i801   | 740EA7B2E9 |
| 8086:9da3 | 103c:8514 | Intel      | Cannon Point-LP SMBus Con... | 25    | i2c_i801   | 211EF30EF4 |
| 8086:9da3 | 17aa:3812 | Intel      | Cannon Point-LP SMBus Con... | 25    | i2c_i801   | 4C9743CDD1 |
| 1022:790b | 103c:85dd | AMD        | FCH SMBus Controller         | 23    | i2c_pii... | C4EA79E269 |
| 8086:34a3 | 1028:08b0 | Intel      | Ice Lake-LP SMBus Controller | 23    | i2c_i801   | 138EC046F1 |
| 8086:9d23 | 17aa:2238 | Intel      | Sunrise Point-LP SMBus       | 22    | i2c_i801   | DD105BA06B |
| 1022:790b | 17aa:3818 | AMD        | FCH SMBus Controller         | 21    | i2c_pii... | 6AF7A7F851 |
| 8086:9d23 | 17aa:3862 | Intel      | Sunrise Point-LP SMBus       | 21    | i2c_i801   | 72617E5DD9 |
| 8086:9d23 | 17aa:3867 | Intel      | Sunrise Point-LP SMBus       | 20    | i2c_i801   | A52209C9F2 |
| 1022:790b | 103c:85de | AMD        | FCH SMBus Controller         | 19    | i2c_piix4  | 3ADCB9ECF9 |
| 8086:34a3 | 17aa:3811 | Intel      | Ice Lake-LP SMBus Controller | 18    | i2c_i801   | D1DD92D46E |
| 8086:9d23 | 103c:827d | Intel      | Sunrise Point-LP SMBus       | 18    | i2c_i801   | 95D389BFE5 |
| 8086:9da3 | 17aa:2292 | Intel      | Cannon Point-LP SMBus Con... | 17    | i2c_i801   | D99F5CBFD2 |
| 1022:790b | 103c:83c6 | AMD        | FCH SMBus Controller         | 16    | i2c_piix4  | 5174E188C0 |
| 1022:790b | 103c:8497 | AMD        | FCH SMBus Controller         | 16    | piix4_s... | 0DFE108C69 |
| 8086:9d23 | 17aa:3811 | Intel      | Sunrise Point-LP SMBus       | 16    | i2c_i801   | 350D402895 |
| 8086:a0a3 | 1028:0a05 | Intel      | Tiger Lake-LP SMBus Contr... | 16    | i2c_i801   | 928665D302 |
| 8086:a0a3 | 17aa:381a | Intel      | Tiger Lake-LP SMBus Contr... | 16    | i2c_i801   | 7851B07853 |
| 1022:790b | 103c:8496 | AMD        | FCH SMBus Controller         | 15    | i2c_piix4  | DFB9789AF2 |
| 1022:790b | 103c:8735 | AMD        | FCH SMBus Controller         | 15    | i2c_piix4  | 4EE6C35B8F |
| 8086:02a3 | 17aa:3806 | Intel      | Comet Lake PCH-LP SMBus H... | 15    | i2c_i801   | 527CC99B36 |
| 8086:9d23 | 1028:077a | Intel      | Sunrise Point-LP SMBus       | 15    | i2c_i801   | 8F7ADB6CD3 |
| 8086:9d23 | 103c:830f | Intel      | Sunrise Point-LP SMBus       | 15    | i2c_i801   | 3286ED83B9 |
| 8086:9d23 | 103c:8486 | Intel      | Sunrise Point-LP SMBus       | 15    | i2c_i801   | 7E241B1F69 |
| 8086:9d23 | 17aa:3823 | Intel      | Sunrise Point-LP SMBus       | 15    | i2c_i801   | AED568D94C |
| 8086:a123 | 17aa:3810 | Intel      | 100 Series/C230 Series Ch... | 15    | i2c_i801   | C362C8CAFD |
| 8086:9d23 | 17aa:224e | Intel      | Sunrise Point-LP SMBus       | 14    | i2c_i801   | 3C24D27D51 |
| 8086:9d23 | 17aa:2259 | Intel      | Sunrise Point-LP SMBus       | 14    | i2c_i801   | 36DBFEF2B7 |
| 8086:9d23 | 17aa:3805 | Intel      | Sunrise Point-LP SMBus       | 14    | i2c_i801   | 82ACEB2458 |
| 8086:9d23 | 17aa:383c | Intel      | Sunrise Point-LP SMBus       | 14    | i2c_i801   | 9A20859E26 |
| 8086:a0a3 | 1028:09ff | Intel      | Tiger Lake-LP SMBus Contr... | 14    | i2c_i801   | 5B10037DA5 |
| 8086:02a3 | 17aa:5078 | Intel      | Comet Lake PCH-LP SMBus H... | 13    | i2c_i801   | 49DBAD6FDB |
| 8086:9d23 | 103c:827e | Intel      | Sunrise Point-LP SMBus       | 13    | i2c_i801   | CCA3E863F7 |
| 8086:a123 | 103c:83bb | Intel      | 100 Series/C230 Series Ch... | 13    | i801_smbus | BA09E3B76F |
| 8086:02a3 | 103c:866e | Intel      | Comet Lake PCH-LP SMBus H... | 12    | i2c_i801   | 572D5CD292 |
| 8086:9d23 | 17aa:380b | Intel      | Sunrise Point-LP SMBus       | 12    | i2c_i801   | 5154E96ABE |
| 8086:a0a3 | 1028:09de | Intel      | Tiger Lake-LP SMBus Contr... | 12    | i2c_i801   | 224CE9A44D |
| 8086:a0a3 | 17aa:3806 | Intel      | Tiger Lake-LP SMBus Contr... | 12    | i2c_i801   | 00AC329183 |
| 8086:a123 | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 12    | i2c_i801   | 27D7C254CC |
| 8086:9d23 | 103c:8488 | Intel      | Sunrise Point-LP SMBus       | 11    | i2c_i801   | 3AF23C8E87 |
| 8086:9d23 | 1043:1ab0 | Intel      | Sunrise Point-LP SMBus       | 11    | i801_smbus | 06E7A51D6A |
| 8086:9d23 | 17aa:385f | Intel      | Sunrise Point-LP SMBus       | 11    | i2c_i801   | F0DA92A413 |
| 8086:9d23 | 17aa:506d | Intel      | Sunrise Point-LP SMBus       | 11    | i2c_i801   | 99C878CD5E |
| 8086:2292 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 10    | i2c_i801   | AB13E942F9 |
| 8086:9d23 | 103c:8438 | Intel      | Sunrise Point-LP SMBus       | 10    | i2c_i801   | AF74E3A1EA |
| 8086:a0a3 | 1028:09dd | Intel      | Tiger Lake-LP SMBus Contr... | 10    | i2c_i801   | 044E6AFDF4 |
| 1022:790b | 103c:888a | AMD        | FCH SMBus Controller         | 9     | i2c_piix4  | ED20604458 |
| 8086:02a3 | 103c:86b1 | Intel      | Comet Lake PCH-LP SMBus H... | 9     | i2c_i801   | F3B0D882C2 |
| 8086:02a3 | 103c:86b2 | Intel      | Comet Lake PCH-LP SMBus H... | 9     | i2c_i801   | B054E02856 |
| 8086:34a3 | 103c:86f9 | Intel      | Ice Lake-LP SMBus Controller | 9     | i2c_i801   | 4967676215 |
| 8086:9d23 | 103c:80d1 | Intel      | Sunrise Point-LP SMBus       | 9     | i2c_i801   | 629D516666 |
| 8086:9d23 | 103c:81a1 | Intel      | Sunrise Point-LP SMBus       | 9     | i2c_i801   | B37CBA5DF4 |
| 8086:9d23 | 17aa:2237 | Intel      | Sunrise Point-LP SMBus       | 9     | i801_smbus | 24D1BD52CC |
| 8086:9d23 | 17aa:3848 | Intel      | Sunrise Point-LP SMBus       | 9     | i2c_i801   | E2C078E281 |
| 8086:9da3 | 1028:0894 | Intel      | Cannon Point-LP SMBus Con... | 9     | i2c_i801   | B07A0CF706 |
| 8086:9da3 | 103c:861f | Intel      | Cannon Point-LP SMBus Con... | 9     | i2c_i801   | 48CABEDB1E |
| 1022:790b | 1028:09e3 | AMD        | FCH SMBus Controller         | 8     | i2c_piix4  | 58C4A6AD98 |
| 1022:790b | 1043:1921 | AMD        | FCH SMBus Controller         | 8     | piix4_s... | BCF877AA15 |
| 8086:02a3 | 1028:095d | Intel      | Comet Lake PCH-LP SMBus H... | 8     | i2c_i801   | E85575B823 |
| 8086:02a3 | 103c:863f | Intel      | Comet Lake PCH-LP SMBus H... | 8     | i2c_i801   | 2A2CFDB7D4 |
| 8086:31d4 |           | Intel      | Celeron/Pentium Silver Pr... | 8     | i801_smbus | 17E78AF479 |
| 8086:9d23 | 103c:8484 | Intel      | Sunrise Point-LP SMBus       | 8     | i2c_i801   | F3D65BB221 |
| 8086:9d23 | 17aa:506c | Intel      | Sunrise Point-LP SMBus       | 8     | i2c_i801   | B39CD022D3 |
| 8086:9da3 | 103c:85c4 | Intel      | Cannon Point-LP SMBus Con... | 8     | i2c_i801   | 7D9588F740 |
| 8086:9da3 | 1043:19d1 | Intel      | Cannon Point-LP SMBus Con... | 8     | i801_smbus | DBBD7A332E |
| 8086:9da3 | 17aa:5077 | Intel      | Cannon Point-LP SMBus Con... | 8     | i2c_i801   | B9971B685A |
| 8086:02a3 | 1028:0950 | Intel      | Comet Lake PCH-LP SMBus H... | 7     | i2c_i801   | 6E2B3B5A7E |
| 8086:02a3 | 1028:09cd | Intel      | Comet Lake PCH-LP SMBus H... | 7     | i2c_i801   | 20FA4B73D7 |
| 8086:02a3 | 17aa:3816 | Intel      | Comet Lake PCH-LP SMBus H... | 7     | i2c_i801   | 611C3C0C19 |
| 8086:0f12 | 103c:802b | Intel      | Atom Processor E3800/CE27... | 7     | i2c_i801   | 4E86625634 |
| 8086:9ca2 | 103c:802d | Intel      | Wildcat Point-LP SMBus Co... | 7     | i2c_i801   | 0B68C3F5C3 |
| 8086:9d23 | 103c:81ad | Intel      | Sunrise Point-LP SMBus       | 7     | i2c_i801   | A6FF75E220 |
| 8086:9d23 | 1043:14f0 | Intel      | Sunrise Point-LP SMBus       | 7     | i2c_i801   | E682AFBEDE |
| 8086:9d23 | 1043:1b00 | Intel      | Sunrise Point-LP SMBus       | 7     | i801_smbus | 9FF68B8AD1 |
| 8086:9d23 | 1043:1dc0 | Intel      | Sunrise Point-LP SMBus       | 7     | i2c_i801   | 26CE6DC2B2 |
| 8086:9d23 | 17aa:5061 | Intel      | Sunrise Point-LP SMBus       | 7     | i2c_i801   | 16AC72B8EA |
| 8086:9da3 | 103c:857f | Intel      | Cannon Point-LP SMBus Con... | 7     | i2c_i801   | 465B51ACD4 |
| 8086:a0a3 | 1028:09df | Intel      | Tiger Lake-LP SMBus Contr... | 7     | i2c_i801   | 69D2B432F7 |
| 8086:a0a3 | 103c:8709 | Intel      | Tiger Lake-LP SMBus Contr... | 7     | i2c_i801   | 444E13B5ED |
| 8086:a0a3 | 103c:87f4 | Intel      | Tiger Lake-LP SMBus Contr... | 7     | i2c_i801   | 6461BFC243 |
| 8086:a0a3 | 17aa:3803 | Intel      | Tiger Lake-LP SMBus Contr... | 7     | i2c_i801   | 5B06944051 |
| 8086:a323 | 17aa:3805 | Intel      | Cannon Lake PCH SMBus Con... | 7     | i2c_i801   | 4EEE4B94CB |
| 1022:790b | 17aa:3841 | AMD        | FCH SMBus Controller         | 6     | i2c_pii... | 65A49B7280 |
| 8086:02a3 | 17aa:2292 | Intel      | Comet Lake PCH-LP SMBus H... | 6     | i2c_i801   | 8F10E30326 |
| 8086:02a3 | 17aa:22be | Intel      | Comet Lake PCH-LP SMBus H... | 6     | i2c_i801   | 65033505B7 |
| 8086:5ad4 | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 6     | i2c_i801   | 4FD337BCA7 |
| 8086:9d23 | 1025:1176 | Intel      | Sunrise Point-LP SMBus       | 6     | i2c_i801   | 566FA6B1D5 |
| 8086:9d23 | 1028:07eb | Intel      | Sunrise Point-LP SMBus       | 6     | i2c_i801   | 765C6838B2 |
| 8086:9d23 | 103c:8313 | Intel      | Sunrise Point-LP SMBus       | 6     | i801_smbus | 5D0F309968 |
| 8086:9d23 | 103c:8483 | Intel      | Sunrise Point-LP SMBus       | 6     | i2c_i801   | C48CB1FCCF |
| 8086:9d23 | 1043:1c90 | Intel      | Sunrise Point-LP SMBus       | 6     | i2c_i801   | AED32F7A4D |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:1637 | 1002:1637 | AMD        | Renoir Radeon High Defini... | 71    | snd_hda... | 65A49B7280 |
| 1022:15e3 | 17aa:381c | AMD        | Family 17h (Models 10h-1f... | 64    | snd_hda... | F07B9B77F5 |
| 8086:a0c8 | 17aa:5089 | Intel      | Tiger Lake-LP Smart Sound... | 59    | snd_hda... | 1EC4861E97 |
| 8086:9d71 | 17aa:3808 | Intel      | Sunrise Point-LP HD Audio    | 44    | snd_hda... | A2717638BE |
| 1002:1637 | 103c:876e | AMD        | Renoir Radeon High Defini... | 38    | snd_hda... | 28B152BB19 |
| 1022:15e3 | 103c:876e | AMD        | Family 17h (Models 10h-1f... | 38    | snd_hda... | 28B152BB19 |
| 1002:1637 | 103c:876f | AMD        | Renoir Radeon High Defini... | 34    | snd_hda... | 5F67B298AB |
| 1022:15e3 | 103c:876f | AMD        | Family 17h (Models 10h-1f... | 34    | snd_hda... | 5F67B298AB |
| 8086:02c8 | 17aa:3803 | Intel      | Comet Lake PCH-LP cAVS       | 33    | sof_aud... | 6F6E5DAF18 |
| 8086:9d71 | 103c:83b9 | Intel      | Sunrise Point-LP HD Audio    | 26    | snd_hda... | BBB2DB43B4 |
| 8086:34c8 | 17aa:3811 | Intel      | Ice Lake-LP Smart Sound T... | 25    | snd_hda... | 740EA7B2E9 |
| 8086:9dc8 | 103c:8514 | Intel      | Cannon Point-LP High Defi... | 25    | snd_hda... | 211EF30EF4 |
| 8086:9dc8 | 17aa:3814 | Intel      | Cannon Point-LP High Defi... | 25    | snd_hda... | 4C9743CDD1 |
| 1002:15de | 103c:85dd | AMD        | Raven/Raven2/Fenghuang HD... | 23    | snd_hda... | C4EA79E269 |
| 1022:15e3 | 103c:85dd | AMD        | Family 17h (Models 10h-1f... | 23    | snd_hda... | C4EA79E269 |
| 8086:34c8 | 1028:08b0 | Intel      | Ice Lake-LP Smart Sound T... | 23    | snd_hda... | 138EC046F1 |
| 8086:9d70 | 17aa:2238 | Intel      | Sunrise Point-LP HD Audio    | 22    | snd_hda... | DD105BA06B |
| 1002:15de | 17aa:3803 | AMD        | Raven/Raven2/Fenghuang HD... | 21    | snd_hda... | 6AF7A7F851 |
| 1022:15e3 | 17aa:380c | AMD        | Family 17h (Models 10h-1f... | 21    | snd_hda... | 6AF7A7F851 |
| 8086:9d71 | 17aa:3829 | Intel      | Sunrise Point-LP HD Audio    | 21    | snd_hda... | 72617E5DD9 |
| 8086:9d71 | 17aa:3831 | Intel      | Sunrise Point-LP HD Audio    | 20    | snd_hda... | A52209C9F2 |
| 1002:15de | 103c:85de | AMD        | Raven/Raven2/Fenghuang HD... | 19    | snd_hda... | 3ADCB9ECF9 |
| 1022:15e3 | 103c:85de | AMD        | Family 17h (Models 10h-1f... | 19    | snd_hda... | 3ADCB9ECF9 |
| 8086:34c8 | 17aa:382e | Intel      | Ice Lake-LP Smart Sound T... | 18    | snd_hda... | D1DD92D46E |
| 8086:9d71 | 103c:827d | Intel      | Sunrise Point-LP HD Audio    | 18    | snd_hda... | 95D389BFE5 |
| 8086:9dc8 | 17aa:2292 | Intel      | Cannon Point-LP High Defi... | 17    | snd_hda... | D99F5CBFD2 |
| 1002:15de | 103c:83c6 | AMD        | Raven/Raven2/Fenghuang HD... | 16    | snd_hda... | 5174E188C0 |
| 1002:15de | 103c:8497 | AMD        | Raven/Raven2/Fenghuang HD... | 16    | snd_hda... | 0DFE108C69 |
| 1022:15e3 | 103c:83c6 | AMD        | Family 17h (Models 10h-1f... | 16    | snd_hda... | 5174E188C0 |
| 1022:15e3 | 103c:8497 | AMD        | Family 17h (Models 10h-1f... | 16    | snd_hda... | 0DFE108C69 |
| 8086:5a98 | 1c6c:122a | Intel      | Celeron N3350/Pentium N42... | 16    | snd_hda... | 4BF1EEBDE1 |
| 8086:9d70 | 17aa:3801 | Intel      | Sunrise Point-LP HD Audio    | 16    | snd_hda... | 350D402895 |
| 8086:a0c8 | 1028:0a05 | Intel      | Tiger Lake-LP Smart Sound... | 16    | snd_hda... | 928665D302 |
| 8086:a0c8 | 17aa:3832 | Intel      | Tiger Lake-LP Smart Sound... | 16    | snd_hda... | 7851B07853 |
| 1002:15de | 103c:8496 | AMD        | Raven/Raven2/Fenghuang HD... | 15    | snd_hda... | DFB9789AF2 |
| 1002:1637 | 103c:8735 | AMD        | Renoir Radeon High Defini... | 15    | snd_hda... | 4EE6C35B8F |
| 1022:15e3 | 103c:8496 | AMD        | Family 17h (Models 10h-1f... | 15    | snd_hda... | DFB9789AF2 |
| 1022:15e3 | 103c:8735 | AMD        | Family 17h (Models 10h-1f... | 15    | snd_hda... | 4EE6C35B8F |
| 8086:02c8 | 17aa:3806 | Intel      | Comet Lake PCH-LP cAVS       | 15    | snd_hda... | 527CC99B36 |
| 8086:9d71 | 1028:077a | Intel      | Sunrise Point-LP HD Audio    | 15    | snd_hda... | 8F7ADB6CD3 |
| 8086:9d71 | 103c:830f | Intel      | Sunrise Point-LP HD Audio    | 15    | snd_hda... | 3286ED83B9 |
| 8086:9d71 | 103c:8486 | Intel      | Sunrise Point-LP HD Audio    | 15    | snd_hda... | 7E241B1F69 |
| 8086:9d71 | 17aa:3801 | Intel      | Sunrise Point-LP HD Audio    | 15    | snd_hda... | AED568D94C |
| 8086:a171 | 17aa:380e | Intel      | CM238 HD Audio Controller    | 15    | snd_hda... | C362C8CAFD |
| 8086:9d71 | 17aa:224e | Intel      | Sunrise Point-LP HD Audio    | 14    | snd_hda... | 3C24D27D51 |
| 8086:9d71 | 17aa:2259 | Intel      | Sunrise Point-LP HD Audio    | 14    | snd_hda... | 36DBFEF2B7 |
| 8086:9d71 | 17aa:3806 | Intel      | Sunrise Point-LP HD Audio    | 14    | snd_hda... | 82ACEB2458 |
| 8086:9d71 | 17aa:3809 | Intel      | Sunrise Point-LP HD Audio    | 14    | snd_hda... | 9A20859E26 |
| 8086:a0c8 | 1028:09ff | Intel      | Tiger Lake-LP Smart Sound... | 14    | snd_hda... | 5B10037DA5 |
| 8086:02c8 | 17aa:5078 | Intel      | Comet Lake PCH-LP cAVS       | 13    | snd_hda... | 49DBAD6FDB |
| 8086:9d71 | 103c:827e | Intel      | Sunrise Point-LP HD Audio    | 13    | snd_hda... | CCA3E863F7 |
| 8086:a171 | 103c:83bb | Intel      | CM238 HD Audio Controller    | 13    | snd_hda... | BA09E3B76F |
| 8086:02c8 | 103c:866e | Intel      | Comet Lake PCH-LP cAVS       | 12    | snd_hda... | 572D5CD292 |
| 8086:9d71 | 17aa:3804 | Intel      | Sunrise Point-LP HD Audio    | 12    | snd_hda... | 5154E96ABE |
| 8086:a0c8 | 1028:09de | Intel      | Tiger Lake-LP Smart Sound... | 12    | snd_hda... | 224CE9A44D |
| 8086:a0c8 | 17aa:381e | Intel      | Tiger Lake-LP Smart Sound... | 12    | snd_hda... | 00AC329183 |
| 8086:a171 | 1028:080d | Intel      | CM238 HD Audio Controller    | 12    | snd_hda... | 27D7C254CC |
| 8086:9d71 | 1043:1ab0 | Intel      | Sunrise Point-LP HD Audio    | 11    | snd_hda... | 06E7A51D6A |
| 8086:9d71 | 17aa:3827 | Intel      | Sunrise Point-LP HD Audio    | 11    | snd_hda... | F0DA92A413 |
| 8086:9d71 | 17aa:506d | Intel      | Sunrise Point-LP HD Audio    | 11    | snd_hda... | 99C878CD5E |
| 8086:2284 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 10    | snd_hda... | AB13E942F9 |
| 8086:9d71 | 103c:8438 | Intel      | Sunrise Point-LP HD Audio    | 10    | snd_hda... | AF74E3A1EA |
| 8086:9d71 | 103c:8488 | Intel      | Sunrise Point-LP HD Audio    | 10    | snd_hda... | 3AF23C8E87 |
| 8086:9d71 | 1043:1b60 | Intel      | Sunrise Point-LP HD Audio    | 10    | snd_hda... | 26CE6DC2B2 |
| 8086:a0c8 | 1028:09dd | Intel      | Tiger Lake-LP Smart Sound... | 10    | snd_hda... | 044E6AFDF4 |
| 1002:1637 | 103c:888a | AMD        | Renoir Radeon High Defini... | 9     | snd_hda... | ED20604458 |
| 1022:15e3 | 103c:888a | AMD        | Family 17h (Models 10h-1f... | 9     | snd_hda... | ED20604458 |
| 8086:02c8 | 103c:86b1 | Intel      | Comet Lake PCH-LP cAVS       | 9     | snd_hda... | F3B0D882C2 |
| 8086:02c8 | 103c:86b2 | Intel      | Comet Lake PCH-LP cAVS       | 9     | snd_hda... | B054E02856 |
| 8086:3198 | 10ec:1194 | Intel      | Celeron/Pentium Silver Pr... | 9     | snd_hda... | 468B5A689D |
| 8086:34c8 | 103c:86f9 | Intel      | Ice Lake-LP Smart Sound T... | 9     | snd_hda... | 4967676215 |
| 8086:9d70 | 103c:80d1 | Intel      | Sunrise Point-LP HD Audio    | 9     | snd_hda... | 629D516666 |
| 8086:9d70 | 103c:81a1 | Intel      | Sunrise Point-LP HD Audio    | 9     | snd_hda... | B37CBA5DF4 |
| 8086:9d70 | 17aa:2237 | Intel      | Sunrise Point-LP HD Audio    | 9     | snd_hda... | 24D1BD52CC |
| 8086:9d71 | 17aa:381c | Intel      | Sunrise Point-LP HD Audio    | 9     | snd_hda... | E2C078E281 |
| 8086:9dc8 | 1028:0894 | Intel      | Cannon Point-LP High Defi... | 9     | snd_hda... | B07A0CF706 |
| 8086:9dc8 | 103c:861f | Intel      | Cannon Point-LP High Defi... | 9     | snd_hda... | 48CABEDB1E |
| 1002:15de | 1002:15de | AMD        | Raven/Raven2/Fenghuang HD... | 8     | snd_hda... | BCF877AA15 |
| 1002:1637 | 1028:09e3 | AMD        | Renoir Radeon High Defini... | 8     | snd_hda... | 58C4A6AD98 |
| 1022:15e3 | 1028:09e3 | AMD        | Family 17h (Models 10h-1f... | 8     | snd_hda... | 58C4A6AD98 |
| 1022:15e3 | 1043:1921 | AMD        | Family 17h (Models 10h-1f... | 8     | snd_hda... | BCF877AA15 |
| 8086:02c8 | 1028:095d | Intel      | Comet Lake PCH-LP cAVS       | 8     | snd_hda... | E85575B823 |
| 8086:02c8 | 103c:863f | Intel      | Comet Lake PCH-LP cAVS       | 8     | snd_hda... | 2A2CFDB7D4 |
| 8086:3198 | 10ec:118e | Intel      | Celeron/Pentium Silver Pr... | 8     | snd_hda... | BB141F313D |
| 8086:9d71 | 103c:8484 | Intel      | Sunrise Point-LP HD Audio    | 8     | snd_hda... | F3D65BB221 |
| 8086:9d71 | 17aa:506c | Intel      | Sunrise Point-LP HD Audio    | 8     | snd_hda... | B39CD022D3 |
| 8086:9dc8 | 103c:85c4 | Intel      | Cannon Point-LP High Defi... | 8     | snd_hda... | 7D9588F740 |
| 8086:9dc8 | 1043:12e1 | Intel      | Cannon Point-LP High Defi... | 8     | snd_hda... | DBBD7A332E |
| 8086:9dc8 | 17aa:5077 | Intel      | Cannon Point-LP High Defi... | 8     | snd_hda... | B9971B685A |
| 8086:02c8 | 1028:0950 | Intel      | Comet Lake PCH-LP cAVS       | 7     | snd_hda... | 6E2B3B5A7E |
| 8086:02c8 | 1028:09cd | Intel      | Comet Lake PCH-LP cAVS       | 7     | snd_hda... | 20FA4B73D7 |
| 8086:02c8 | 17aa:3815 | Intel      | Comet Lake PCH-LP cAVS       | 7     | snd_hda... | 611C3C0C19 |
| 8086:0f04 | 103c:802b | Intel      | Atom Processor Z36xxx/Z37... | 7     | snd_hda... | 4E86625634 |
| 8086:160c | 103c:802d | Intel      | Broadwell-U Audio Controller | 7     | snd_hda... | 0B68C3F5C3 |
| 8086:3198 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 7     | snd_hda... | E4FB415516 |
| 8086:34c8 | 1025:141f | Intel      | Ice Lake-LP Smart Sound T... | 7     | snd_hda... | 059B59E828 |
| 8086:9d71 | 103c:81ad | Intel      | Sunrise Point-LP HD Audio    | 7     | snd_hda... | A6FF75E220 |
| 8086:9d71 | 1043:14f0 | Intel      | Sunrise Point-LP HD Audio    | 7     | snd_hda... | E682AFBEDE |
| 8086:9d71 | 17aa:5061 | Intel      | Sunrise Point-LP HD Audio    | 7     | snd_hda... | 16AC72B8EA |
| 8086:9dc8 | 103c:857f | Intel      | Cannon Point-LP High Defi... | 7     | snd_hda... | 465B51ACD4 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 58    | ahci       | F07B9B77F5 |
| 8086:31e3 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 38    | ahci       | 4DBC03E904 |
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 34    | ahci       | AA88177E76 |
| 8086:02d3 | 17aa:3802 | Intel      | Comet Lake SATA AHCI Cont... | 33    | ahci       | 6F6E5DAF18 |
| 8086:9d03 | 17aa:383b | Intel      | Sunrise Point-LP SATA Con... | 28    | ahci       | A2717638BE |
| 1022:7901 | 103c:876e | AMD        | FCH SATA Controller [AHCI... | 20    | ahci       | 03F587E7B9 |
| 8086:9dd3 | 17aa:3806 | Intel      | Cannon Point-LP SATA Cont... | 19    | ahci       | 4C9743CDD1 |
| 1022:7901 | 103c:876f | AMD        | FCH SATA Controller [AHCI... | 17    | ahci       | FBB923829D |
| 1022:7901 | 103c:83c6 | AMD        | FCH SATA Controller [AHCI... | 16    | ahci       | 5174E188C0 |
| 1022:7901 | 103c:8497 | AMD        | FCH SATA Controller [AHCI... | 16    | ahci       | 0DFE108C69 |
| 8086:9d03 | 17aa:380d | Intel      | Sunrise Point-LP SATA Con... | 16    | ahci       | 350D402895 |
| 1022:7901 | 103c:8496 | AMD        | FCH SATA Controller [AHCI... | 15    | ahci       | DFB9789AF2 |
| 8086:9d03 | 103c:830f | Intel      | Sunrise Point-LP SATA Con... | 15    | ahci       | 3286ED83B9 |
| 8086:9d03 | 17aa:3822 | Intel      | Sunrise Point-LP SATA Con... | 15    | ahci       | AED568D94C |
| 8086:9d03 | 103c:8486 | Intel      | Sunrise Point-LP SATA Con... | 14    | ahci       | 7E241B1F69 |
| 8086:9d03 | 17aa:2238 | Intel      | Sunrise Point-LP SATA Con... | 14    | ahci       | DD105BA06B |
| 8086:a103 | 103c:83bb | Intel      | HM170/QM170 Chipset SATA ... | 13    | ahci       | BA09E3B76F |
| 8086:9d03 | 17aa:3810 | Intel      | Sunrise Point-LP SATA Con... | 12    | ahci       | 5154E96ABE |
| 8086:9d03 | 1043:1ab0 | Intel      | Sunrise Point-LP SATA Con... | 11    | ahci       | 06E7A51D6A |
| 8086:9d03 | 103c:80d1 | Intel      | Sunrise Point-LP SATA Con... | 9     | ahci       | 629D516666 |
| 8086:9d03 | 103c:8488 | Intel      | Sunrise Point-LP SATA Con... | 9     | ahci       | 3AF23C8E87 |
| 1022:7901 | 1028:09e3 | AMD        | FCH SATA Controller [AHCI... | 8     | ahci       | 58C4A6AD98 |
| 1022:7901 | 1043:1921 | AMD        | FCH SATA Controller [AHCI... | 8     | ahci       | BCF877AA15 |
| 8086:9d03 | 103c:8484 | Intel      | Sunrise Point-LP SATA Con... | 8     | ahci       | F3D65BB221 |
| 8086:9d03 | 17aa:2237 | Intel      | Sunrise Point-LP SATA Con... | 8     | ahci       | 24D1BD52CC |
| 8086:02d3 | 1028:095d | Intel      | Comet Lake SATA AHCI Cont... | 7     | ahci       | E85575B823 |
| 8086:9d03 | 103c:81ad | Intel      | Sunrise Point-LP SATA Con... | 7     | ahci       | A6FF75E220 |
| 8086:9d03 | 1043:14f0 | Intel      | Sunrise Point-LP SATA Con... | 7     | ahci       | E682AFBEDE |
| 8086:9d03 | 1043:1b00 | Intel      | Sunrise Point-LP SATA Con... | 7     | ahci       | 9FF68B8AD1 |
| 8086:02d3 | 17aa:380a | Intel      | Comet Lake SATA AHCI Cont... | 6     | ahci       | 611C3C0C19 |
| 8086:31e3 | 17aa:3801 | Intel      | Celeron/Pentium Silver Pr... | 6     | ahci       | 17E78AF479 |
| 8086:5ae3 | 17aa:3803 | Intel      | Celeron N3350/Pentium N42... | 6     | ahci       | 4FD337BCA7 |
| 8086:9c83 | 103c:802d | Intel      | Wildcat Point-LP SATA Con... | 6     | ahci       | 0B68C3F5C3 |
| 8086:9d03 | 1025:1176 | Intel      | Sunrise Point-LP SATA Con... | 6     | ahci       | 566FA6B1D5 |
| 8086:9d03 | 1028:07eb | Intel      | Sunrise Point-LP SATA Con... | 6     | ahci       | 765C6838B2 |
| 8086:9d03 | 103c:8313 | Intel      | Sunrise Point-LP SATA Con... | 6     | ahci       | 5D0F309968 |
| 8086:9d03 | 103c:8483 | Intel      | Sunrise Point-LP SATA Con... | 6     | ahci       | C48CB1FCCF |
| 1022:7901 | 1028:0a8c | AMD        | FCH SATA Controller [AHCI... | 5     | ahci       | 58E1FA994C |
| 1022:7901 | 103c:8735 | AMD        | FCH SATA Controller [AHCI... | 5     | ahci       | 8C94839928 |
| 1022:7901 | 103c:87a9 | AMD        | FCH SATA Controller [AHCI... | 5     | ahci       | 96C4D24CAB |
| 1022:7901 | 1043:11f2 | AMD        | FCH SATA Controller [AHCI... | 5     | ahci       | 395433A65C |
| 1022:7904 | 103c:81aa | AMD        | FCH SATA Controller [AHCI... | 5     | ahci       | 633D386331 |
| 8086:31e3 | 1025:1316 | Intel      | Celeron/Pentium Silver Pr... | 5     | ahci       | BAB6686973 |
| 8086:9d03 | 103c:81a9 | Intel      | Sunrise Point-LP SATA Con... | 5     | ahci       | 0BB3F77C75 |
| 8086:9d03 | 1043:14c0 | Intel      | Sunrise Point-LP SATA Con... | 5     | ahci       | 84CEEEACF1 |
| 8086:9d03 | 17aa:504c | Intel      | Sunrise Point-LP SATA Con... | 5     | ahci       | 4983586FE5 |
| 8086:9dd3 | 1028:0895 | Intel      | Cannon Point-LP SATA Cont... | 5     | ahci       | 5A60912D9F |
| 8086:9dd3 | 1028:0896 | Intel      | Cannon Point-LP SATA Cont... | 5     | ahci       | 4D7F19A11A |
| 8086:9dd3 | 1043:1481 | Intel      | Cannon Point-LP SATA Cont... | 5     | ahci       | 52E5D3E16D |
| 8086:9dd3 | 1043:19d1 | Intel      | Cannon Point-LP SATA Cont... | 5     | ahci       | DBBD7A332E |
| 1022:7904 | 17aa:3804 | AMD        | FCH SATA Controller [AHCI... | 4     | ahci       | 6931FAE5CC |
| 8086:02d3 | 1028:0950 | Intel      | Comet Lake SATA AHCI Cont... | 4     | ahci       | 6E2B3B5A7E |
| 8086:9c83 | 103c:806e | Intel      | Wildcat Point-LP SATA Con... | 4     | ahci       | A8AA7A1D17 |
| 8086:9d03 | 103c:81a7 | Intel      | Sunrise Point-LP SATA Con... | 4     | ahci       | BC77E670A5 |
| 8086:9d03 | 103c:83c4 | Intel      | Sunrise Point-LP SATA Con... | 4     | ahci       | 3F62C672FB |
| 8086:9d03 | 103c:8487 | Intel      | Sunrise Point-LP SATA Con... | 4     | ahci       | CEBF94C181 |
| 8086:9d03 | 103c:84d8 | Intel      | Sunrise Point-LP SATA Con... | 4     | ahci       | 03FE12C3CC |
| 8086:9d03 | 1043:1c90 | Intel      | Sunrise Point-LP SATA Con... | 4     | ahci       | A294ADAC80 |
| 8086:9dd3 | 1028:089e | Intel      | Cannon Point-LP SATA Cont... | 4     | ahci       | C6692154A1 |
| 8086:9dd3 | 17aa:3803 | Intel      | Cannon Point-LP SATA Cont... | 4     | ahci       | 358875FD3C |
| 8086:02d3 | 1028:0951 | Intel      | Comet Lake SATA AHCI Cont... | 3     | ahci       | 247867F57E |
| 8086:02d3 | 1028:0960 | Intel      | Comet Lake SATA AHCI Cont... | 3     | ahci       | 40A7A1942F |
| 8086:31e3 | 1028:081f | Intel      | Celeron/Pentium Silver Pr... | 3     | ahci       | D11804DA19 |
| 8086:5ae3 | 1025:1198 | Intel      | Celeron N3350/Pentium N42... | 3     | ahci       | A49C104EDA |
| 8086:5ae3 | 1043:1c80 | Intel      | Celeron N3350/Pentium N42... | 3     | ahci       | 7F25CF70DD |
| 8086:9d03 | 1025:120d | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 50D4915C8A |
| 8086:9d03 | 1028:0878 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 91F3D918A0 |
| 8086:9d03 | 103c:804e | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | B4E75E63FB |
| 8086:9d03 | 103c:804f | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 45BA0657F1 |
| 8086:9d03 | 103c:81a1 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | CDA71D4B90 |
| 8086:9d03 | 103c:8251 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | DBD6D18C03 |
| 8086:9d03 | 103c:8310 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | D7D0DE8CF4 |
| 8086:9d03 | 1043:1c40 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | BD57C16BE8 |
| 8086:9d03 | 144d:c162 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 5DA835E33E |
| 8086:9d03 | 8086:9d03 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | BC5D045DEF |
| 8086:9dd3 | 1028:0908 | Intel      | Cannon Point-LP SATA Cont... | 3     | ahci       | 81E2001F6C |
| 8086:9dd3 | 103c:85cd | Intel      | Cannon Point-LP SATA Cont... | 3     | ahci       | 802426D52D |
| 8086:a353 | 103c:844f | Intel      | Cannon Lake Mobile PCH SA... | 3     | ahci       | 2668A6580A |
| 1022:7904 | 103c:8311 | AMD        | FCH SATA Controller [AHCI... | 2     | ahci       | 514D46C27F |
| 8086:02d3 | 17aa:3804 | Intel      | Comet Lake SATA AHCI Cont... | 2     | ahci       | 3C0A5BE140 |
| 8086:22a3 | 103c:8074 | Intel      | Atom/Celeron/Pentium Proc... | 2     | ahci       | 71479C34B4 |
| 8086:22a3 | 103c:81a2 | Intel      | Atom/Celeron/Pentium Proc... | 2     | ahci       | 35DC79725B |
| 8086:22a3 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 2     | ahci       | AB13E942F9 |
| 8086:22a3 | 17aa:3801 | Intel      | Atom/Celeron/Pentium Proc... | 2     | ahci       | 04E375292D |
| 8086:31e3 | 1025:1293 | Intel      | Celeron/Pentium Silver Pr... | 2     | ahci       | 2A5DDF7BE8 |
| 8086:5ae3 | 103c:830d | Intel      | Celeron N3350/Pentium N42... | 2     | ahci       | 27DC03B58E |
| 8086:5ae3 | 1043:1d90 | Intel      | Celeron N3350/Pentium N42... | 2     | ahci       | C8D3F204E5 |
| 8086:9d03 | 1025:112e | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 0D47CA8A0C |
| 8086:9d03 | 1025:1139 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 95AF4B8DC9 |
| 8086:9d03 | 1025:1234 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | A1AA63890A |
| 8086:9d03 | 1028:07ec | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | FA3A8B9226 |
| 8086:9d03 | 103c:8143 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 03065735FF |
| 8086:9d03 | 103c:81ac | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 235D55372B |
| 8086:9d03 | 103c:827d | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 9282890B2E |
| 8086:9d03 | 103c:8314 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 5CF089CFA1 |
| 8086:9d03 | 103c:83c9 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 8BF489A0CB |
| 8086:9d03 | 1043:1330 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 905BC0C0BC |
| 8086:9d03 | 1043:1480 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 7AD86811C5 |
| 8086:9d03 | 1043:18e0 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 442B55026A |
| 8086:9d03 | 1043:1b60 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 6570252E3E |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 345   | nvme       | F07B9B77F5 |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 96    | nvme       | 5174E188C0 |
| 1e0f:0001 | 1e0f:0001 | KIOXIA     | Non-Volatile memory contr... | 86    | nvme       | 138EC046F1 |
| 8086:0975 | 8086:8410 | Intel      | Non-Volatile memory contr... | 77    | nvme       | 224CE9A44D |
| 8086:0975 | 8086:8510 | Intel      | Non-Volatile memory contr... | 76    | nvme       | 224CE9A44D |
| 144d:a809 | 144d:a801 | Samsung... | NVMe SSD Controller 980      | 69    | nvme       | 6461BFC243 |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 67    | nvme       | 5F67B298AB |
| 15b7:5006 | 15b7:5006 | Sandisk    | WD Black SN750 / PC SN730... | 52    | nvme       | 00AC329183 |
| 1179:0113 | 1179:0001 | Toshiba... | BG3 NVMe SSD Controller      | 44    | nvme       | 63EBD660D8 |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 44    | nvme       | 8F7ADB6CD3 |
| 15b7:5003 | 15b7:5003 | Sandisk    | WD Blue SN500 / PC SN520 ... | 40    | nvme       | 799D37094F |
| 1c5c:1339 | 1c5c:0000 | SK Hynix   | BC511                        | 40    | nvme       | ADF32CA36B |
| 1c5c:1527 | 1c5c:1527 | SK Hynix   | PC401 NVMe Solid State Dr... | 39    | nvme       | EF7D0F49E1 |
| 1179:011a | 1179:0001 | Toshiba... | XG6 NVMe SSD Controller      | 35    | nvme       | 2A2CFDB7D4 |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | BC501 NVMe Solid State Drive | 35    | nvme       | 4A621D71B7 |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/SN750 / PC ... | 34    | nvme       | 36DBFEF2B7 |
| 1179:0115 | 1179:0001 | Toshiba... | XG4 NVMe SSD Controller      | 20    | nvme       | C155A04F38 |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 20    | nvme       | 27A8094D68 |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 16    | nvme       | 16AC72B8EA |
| 15b7:5008 | 15b7:5008 | Sandisk    | Non-Volatile memory contr... | 15    | nvme       | C977BD2115 |
| 1c5c:1627 | 1c5c:1627 | SK Hynix   | Non-Volatile memory contr... | 14    | nvme       | 4C9743CDD1 |
| 1cc4:6202 | 1cc4:1cc4 | Union M... | Non-Volatile memory contr... | 14    | nvme       | 5C44D97D66 |
| 1c5c:174a | 1c5c:174a | SK Hynix   | Gold P31 SSD                 | 11    | nvme       | 65A49B7280 |
| 1cc4:6203 | 1cc4:1cc4 | Union M... | Non-Volatile memory contr... | 11    | nvme       | 2B043D7A15 |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 11    | nvme       | 3C03CE796F |
| 1344:5405 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 10    | nvme       | D48766CB68 |
| 15b7:5004 | 15b7:5004 | Sandisk    | PC SN520 NVMe SSD            | 10    | nvme       | 40A7A1942F |
| 15b7:5007 | 15b7:5007 | Sandisk    | Non-Volatile memory contr... | 10    | nvme       | 062C3B976F |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 10    | nvme       | 740EA7B2E9 |
| 1344:5410 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 9     | nvme       | A5DA505B83 |
| 15b7:5005 | 15b7:5005 | Sandisk    | PC SN520 NVMe SSD            | 9     | nvme       | 72617E5DD9 |
| 15b7:5009 | 15b7:5009 | Sandisk    | WD Blue SN550 NVMe SSD       | 9     | nvme       | FA3A8B9226 |
| 1c5c:1639 | 1c5c:1639 | SK Hynix   | Non-Volatile memory contr... | 9     | nvme       | 928665D302 |
| c0a9:2263 | c0a9:2263 | Micron/... | P1 NVMe PCIe SSD             | 9     | nvme       | 0B7AE105E2 |
| 126f:2263 | 126f:2263 | Silicon... | SM2263EN/SM2263XT SSD Con... | 8     | nvme       | E1FD95E053 |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 8     | nvme       | 0DFE108C69 |
| 2646:500c | 2646:500c | Kingsto... | Technology Company Non-Vo... | 6     | nvme       | 395433A65C |
| 1987:5013 | 1987:5013 | Phison ... | PS5013 E13 NVMe Controller   | 5     | nvme       | 4D915AC887 |
| 2646:2263 | 2646:2263 | Kingsto... | A2000 NVMe SSD               | 5     | nvme       | 03D484665D |
| 126f:2262 | 126f:2262 | Silicon... | SM2262/SM2262EN SSD Contr... | 4     | nvme       | 0F145AD5EB |
| c0a9:540a | c0a9:540a | Micron/... | P2 NVMe PCIe SSD             | 4     | nvme       | 448FE0CF6A |
| 1344:5404 | 1344:1100 | Micron ... | Non-Volatile memory contr... | 3     | nvme       | C37F278D59 |
| 144d:a80a | 144d:a801 | Samsung... | NVMe SSD Controller PM9A1... | 3     | nvme       | C58154679E |
| 1cc4:5008 | 1cc4:5008 | Union M... | Non-Volatile memory contr... | 3     | nvme       | 010C424C33 |
| 1e95:9100 | 126f:2263 | Solid S... | Non-Volatile memory contr... | 3     | nvme       | 8C0EB7F583 |
| c0a9:5403 | c0a9:2100 | Micron/... | NVMe Controller              | 3     | nvme       | 211EF30EF4 |
| 10ec:5762 | 10ec:5762 | Realtek... | RTS5763DL NVMe SSD Contro... | 2     | nvme       | E6123179C2 |
| 14a4:2100 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 2     | nvme       | DEB206B64F |
| 17aa:0005 | 17aa:1005 | Lenovo     | Non-Volatile memory contr... | 2     | nvme       | A3D7B44215 |
| 1c5c:1284 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 2     | nvme       | BC2A228855 |
| 1cc1:33f3 | 1cc1:33f3 | ADATA T... | Non-Volatile memory contr... | 2     | nvme       | 82EB222C26 |
| 1cc4:6201 | 1cc4:1cc4 | Union M... | Non-Volatile memory contr... | 2     | nvme       | 3CD1B703C4 |
| 2646:5008 | 2646:5008 | Kingsto... | U-SNS8154P3 NVMe SSD         | 2     | nvme       | 2F463816D0 |
| 2646:500d | 2646:500d | Kingsto... | OM3PDP3 NVMe SSD             | 2     | nvme       | E898A5DA94 |
| 8086:0000 |           | Intel      | PROSet/Wireless WiFi Soft... | 2     | nvme       | 086EC09EE4 |
| c0a9:5412 | c0a9:0100 | Micron/... | Non-Volatile memory contr... | 2     | nvme       | 7AE9D7DB4C |
| 10ec:5763 | 10ec:5763 | Realtek... | Realtek Non-Volatile memo... | 1     | nvme       | A7D8B6A0DD |
| 144d:a806 | 144d:a801 | Samsung... | Electronics Non-Volatile ... | 1     | nvme       | 5F781E103C |
| 14a4:9100 | 126f:2263 | Lite-On... | NVMe Controller              | 1     | nvme       | 30F9D92510 |
| 15b7:5001 | 1b4b:1093 | Sandisk    | WD Black NVMe SSD            | 1     | nvme       | D666EADD11 |
| 17aa:0003 | 17aa:1003 | Lenovo     | Non-Volatile memory contr... | 1     | nvme       | B39CD022D3 |
| 1987:5008 | 1987:5008 | Phison ... | NVMe Storage Controller      | 1     | nvme       | CDEC5FA860 |
| 1987:5016 | 1987:5016 | Phison ... | E16 PCIe4 NVMe Controller    | 1     | nvme       | 8C3B4736CD |
| 1bb1:5012 | 1bb1:5012 | Seagate... | FireCuda 510 SSD             | 1     | nvme       | D4082453C1 |
| 1cc4:2260 | 1cc4:2260 | Union M... | Non-Volatile memory contr... | 1     | nvme       | CE03C99485 |
| 1dee:2262 | 1dee:1dee | Biwin S... | Non-Volatile memory contr... | 1     | nvme       | F8C5A69D8E |
| 2646:500e | 2646:500e | Kingsto... | SNVS2000G [NV1 NVMe PCIe ... | 1     | nvme       | 7E30E68A5F |
| 8086:2522 | 8086:3810 | Intel      | NVMe Optane Memory Series    | 1     | nvme       | 4AC8232839 |
| 8086:f1a7 | 8086:390c | Intel      | Non-Volatile memory contr... | 1     | nvme       | 6C6FB6B24A |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9a0b | 8086:0000 | Intel      | Volume Management Device ... | 21    | vmd        | 6461BFC243 |
| 8086:282a | 17aa:380e | Intel      | 82801 Mobile SATA Control... | 17    | ahci       | 4C8282BB42 |
| 8086:9a0b | 8086:7270 | Intel      | Volume Management Device ... | 15    | vmd        | 7851B07853 |
| 8086:9a0b | 1028:0a05 | Intel      | Volume Management Device ... | 13    | vmd        | D2819F7F94 |
| 8086:282a | 103c:866e | Intel      | 82801 Mobile SATA Control... | 12    | ahci       | 572D5CD292 |
| 8086:282a | 103c:86b1 | Intel      | 82801 Mobile SATA Control... | 9     | ahci       | F3B0D882C2 |
| 8086:282a | 103c:86b2 | Intel      | 82801 Mobile SATA Control... | 9     | ahci       | B054E02856 |
| 8086:282a | 103c:86f9 | Intel      | 82801 Mobile SATA Control... | 9     | ahci       | 4967676215 |
| 8086:9a0b | 1028:09ff | Intel      | Volume Management Device ... | 9     | vmd        | 7DFBA338B1 |
| 8086:282a | 103c:85c4 | Intel      | 82801 Mobile SATA Control... | 8     | ahci       | 7D9588F740 |
| 8086:282a | 103c:863f | Intel      | 82801 Mobile SATA Control... | 7     | ahci       | CF4506977A |
| 8086:9a0b | 1028:09dd | Intel      | Volume Management Device ... | 7     | vmd        | 74A262254D |
| 8086:9a0b | 1028:09de | Intel      | Volume Management Device ... | 7     | vmd        | 224CE9A44D |
| 8086:9a0b | 14c0:012d | Intel      | Volume Management Device ... | 6     | vmd        | 14109EDFC9 |
| 8086:282a | 103c:850e | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 0A3FF1EAD5 |
| 8086:282a | 103c:85e7 | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 169477DE3F |
| 8086:282a | 103c:86fa | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | 635BBB6F75 |
| 8086:282a | 17aa:3806 | Intel      | 82801 Mobile SATA Control... | 5     | ahci       | CD156B08D8 |
| 8086:9a0b | 1028:09df | Intel      | Volume Management Device ... | 5     | vmd        | 7F4D3749EC |
| 8086:9a0b | 103c:8825 | Intel      | Volume Management Device ... | 5     | vmd        | 24060045B4 |
| 8086:282a | 103c:850c | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | EEC05D1BF9 |
| 8086:282a | 103c:85c5 | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 03D484665D |
| 8086:282a | 103c:85c8 | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 1649B0B654 |
| 8086:282a | 103c:861f | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 48CABEDB1E |
| 8086:282a | 103c:875b | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 258D846B85 |
| 8086:282a | 103c:8774 | Intel      | 82801 Mobile SATA Control... | 4     | ahci       | 1E2B68B7D8 |
| 8086:9a0b | 1028:0a5b | Intel      | Volume Management Device ... | 4     | vmd        | 062C3B976F |
| 8086:02d7 | 1028:0950 | Intel      | Comet Lake PCH-LP SATA RA... | 3     | ahci       | 342D571232 |
| 8086:282a | 1028:07ec | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 0CB4C988DD |
| 8086:282a | 103c:8488 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 913C46A400 |
| 8086:282a | 103c:850d | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 987181B525 |
| 8086:282a | 1043:19d1 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | ACC6C11A97 |
| 8086:282a | 17aa:3836 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | D1DD92D46E |
| 8086:9a0b | 103c:8811 | Intel      | Volume Management Device ... | 3     | vmd        | 5E31F081A4 |
| 8086:02d7 | 1028:0960 | Intel      | Comet Lake PCH-LP SATA RA... | 2     | ahci       | F7AB576C61 |
| 8086:02d7 | 103c:86e5 | Intel      | Comet Lake PCH-LP SATA RA... | 2     | ahci       | B1F664E821 |
| 8086:02d7 | 1043:1c51 | Intel      | Comet Lake PCH-LP SATA RA... | 2     |            | C5079022A9 |
| 8086:282a | 1028:089e | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | C52711AB47 |
| 8086:282a | 1028:08b0 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | BF7F394D00 |
| 8086:282a | 1028:0907 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | CE0C672AEB |
| 8086:282a | 103c:8514 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 3204FA323C |
| 8086:282a | 103c:85c6 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | CA868AA68C |
| 8086:282a | 103c:85e6 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 0A7C046DCE |
| 8086:282a | 103c:8637 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | F30D3F55AD |
| 8086:282a | 103c:8670 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 325235430E |
| 8086:282a | 103c:8671 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 0F145AD5EB |
| 8086:9a0b | 1028:0a3f | Intel      | Volume Management Device ... | 2     | vmd        | CE071BC833 |
| 8086:9a0b | 103c:8824 | Intel      | Volume Management Device ... | 2     | vmd        | DDC302E8F0 |
| 8086:9a0b | 103c:8826 | Intel      | Volume Management Device ... | 2     | vmd        | B0E2DE6BBE |
| 8086:9a0b | 103c:8847 | Intel      | Volume Management Device ... | 2     | vmd        | C58154679E |
| 8086:02d7 | 1028:0951 | Intel      | Comet Lake PCH-LP SATA RA... | 1     |            | 1C83B9C63C |
| 8086:02d7 | 1028:09c6 | Intel      | Comet Lake PCH-LP SATA RA... | 1     |            | F146E46238 |
| 8086:02d7 | 1028:09da | Intel      | Comet Lake PCH-LP SATA RA... | 1     | ahci       | 2BE9BAE979 |
| 8086:06d7 | 103c:86e8 | Intel      | Comet Lake PCH-H RAID        | 1     | ahci       | 66D71367C1 |
| 8086:282a | 1025:120e | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | CF6164516E |
| 8086:282a | 1025:1419 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | C617717583 |
| 8086:282a | 1028:077a | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 57D57D82FE |
| 8086:282a | 1028:07aa | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | DFDC8C484F |
| 8086:282a | 1028:0823 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | CCD587FDE5 |
| 8086:282a | 1028:0894 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | B07A0CF706 |
| 8086:282a | 1028:089f | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 70A45F8830 |
| 8086:282a | 1028:0908 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 90E00A5174 |
| 8086:282a | 1028:095d | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 708D566327 |
| 8086:282a | 103c:8486 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 026067E41D |
| 8086:282a | 103c:8487 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | C9B7CA8930 |
| 8086:282a | 103c:850f | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 606B3CF160 |
| 8086:282a | 103c:85cd | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | E7DCDD4B39 |
| 8086:282a | 103c:863e | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | DF64AA5AA5 |
| 8086:282a | 103c:866f | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 63EBD660D8 |
| 8086:282a | 103c:8672 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 8E5E4CCD9B |
| 8086:282a | 103c:86ec | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 483D4785B1 |
| 8086:282a | 103c:8757 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 5B605BAD97 |
| 8086:282a | 1043:1b31 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | EE715DE644 |
| 8086:282a | 1043:1f61 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 3D10849F6E |
| 8086:282a | 17aa:3805 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | B2648D2B7C |
| 8086:282a | 17aa:380a | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | D9D123FF85 |
| 8086:282a | 17aa:380b | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 1681EDB0F6 |
| 8086:282a | 8086:7270 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | DC14D7EC63 |
| 8086:9a0b | 1025:1509 | Intel      | Volume Management Device ... | 1     | vmd        | 7AE9D7DB4C |
| 8086:9a0b | 1025:150a | Intel      | Volume Management Device ... | 1     | vmd        | 8C3B4736CD |
| 8086:9a0b | 1028:0a37 | Intel      | Volume Management Device ... | 1     | vmd        | 6B922F27D1 |
| 8086:9a0b | 103c:8720 | Intel      | Volume Management Device ... | 1     | vmd        | A3F6FA0AC9 |
| 8086:9a0b | 103c:8812 | Intel      | Volume Management Device ... | 1     | vmd        | CFAF6BB9AB |
| 8086:9a0b | 103c:88b4 | Intel      | Volume Management Device ... | 1     | vmd        | DA1B3EFFEA |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8a17 |           | Intel      | Ice Lake Thunderbolt 3 NH... | 65    | thunder... | 138EC046F1 |
| 8086:9a11 | 17aa:5089 | Intel      | GNA Scoring Accelerator m... | 59    |            | 1EC4861E97 |
| 8086:09ab |           | Intel      | System peripheral            | 52    |            | 224CE9A44D |
| 8086:1911 | 17aa:3869 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 33    |            | 6F6E5DAF18 |
| 8086:8a0d |           | Intel      | Ice Lake Thunderbolt 3 NH... | 28    | thunder... | 138EC046F1 |
| 8086:15d2 | 103c:8514 | Intel      | JHL6540 Thunderbolt 3 NHI... | 25    | thunder... | 211EF30EF4 |
| 8086:1911 | 17aa:385b | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 25    |            | 4C9743CDD1 |
| 8086:1911 | 17aa:2292 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 23    |            | 8F10E30326 |
| 8086:1911 | 17aa:2238 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 22    |            | DD105BA06B |
| 8086:15d2 | 17aa:2292 | Intel      | JHL6540 Thunderbolt 3 NHI... | 21    | thunder... | 8F10E30326 |
| 8086:09ab | ffff:ffff | Intel      | System peripheral            | 15    |            | 7851B07853 |
| 8086:1911 | 17aa:3806 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 15    |            | 527CC99B36 |
| 8086:1911 | 17aa:224e | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 14    |            | 3C24D27D51 |
| 8086:1911 | 17aa:2259 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 14    |            | 36DBFEF2B7 |
| 8086:1911 | 17aa:3804 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 14    |            | 82ACEB2458 |
| 8086:1911 | 17aa:5078 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 13    |            | 49DBAD6FDB |
| 8086:1911 | 103c:866e | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 12    |            | 572D5CD292 |
| 8086:15d2 | 2222:1111 | Intel      | JHL6540 Thunderbolt 3 NHI... | 11    | thunder... | A3D7B44215 |
| 8086:1911 | 17aa:506d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 11    |            | 99C878CD5E |
| 8086:15d2 | 103c:8438 | Intel      | JHL6540 Thunderbolt 3 NHI... | 10    | thunder... | AF74E3A1EA |
| 8086:15e8 | 1028:0950 | Intel      | JHL7540 Thunderbolt 3 NHI... | 9     | thunder... | 6E2B3B5A7E |
| 8086:15eb | 103c:861f | Intel      | JHL7540 Thunderbolt 3 NHI... | 9     | thunder... | 48CABEDB1E |
| 8086:1911 | 1028:0894 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 9     |            | B07A0CF706 |
| 8086:1911 | 103c:86b1 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 9     |            | F3B0D882C2 |
| 8086:1911 | 103c:86b2 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 9     |            | B054E02856 |
| 8086:1911 | 17aa:2237 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 9     |            | 24D1BD52CC |
| 8086:1911 | 17aa:3831 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 9     |            | E2C078E281 |
| 8086:09ab | 1028:09ff | Intel      | System peripheral            | 8     |            | 7DFBA338B1 |
| 8086:15e8 | 103c:863f | Intel      | JHL7540 Thunderbolt 3 NHI... | 8     | thunder... | 2A2CFDB7D4 |
| 8086:1911 | 1028:095d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 8     |            | E85575B823 |
| 8086:1911 | 103c:85c4 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 8     |            | 7D9588F740 |
| 8086:1911 | 1043:19d1 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 8     |            | DBBD7A332E |
| 8086:1911 | 17aa:5077 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 8     |            | B9971B685A |
| 8086:15d2 | 17aa:3801 | Intel      | JHL6540 Thunderbolt 3 NHI... | 7     | thunder... | 4EEE4B94CB |
| 8086:15eb | 1028:09cd | Intel      | JHL7540 Thunderbolt 3 NHI... | 7     | thunder... | 20FA4B73D7 |
| 8086:1911 | 1028:0950 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 7     |            | 6E2B3B5A7E |
| 8086:1911 | 1028:09cd | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 7     |            | 20FA4B73D7 |
| 8086:1911 | 17aa:3855 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 7     |            | 611C3C0C19 |
| 8086:1911 | 17aa:3867 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 7     |            | 4EEE4B94CB |
| 8086:1911 | 17aa:5061 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 7     |            | 16AC72B8EA |
| 8086:8a11 | 1025:141f | Intel      | System peripheral            | 7     |            | 059B59E828 |
| 8086:9a11 | 103c:8709 | Intel      | GNA Scoring Accelerator m... | 7     |            | 444E13B5ED |
| 8086:9a11 | 103c:87f4 | Intel      | GNA Scoring Accelerator m... | 7     |            | 6461BFC243 |
| 8086:09ab | 103c:8709 | Intel      | System peripheral            | 6     |            | 444E13B5ED |
| 8086:09ab | 103c:87f6 | Intel      | System peripheral            | 6     |            | E1D0678746 |
| 8086:09ab | 14c0:012d | Intel      | System peripheral            | 6     |            | 14109EDFC9 |
| 8086:15d2 | 1028:08e2 | Intel      | JHL6540 Thunderbolt 3 NHI... | 6     | thunder... | ADF32CA36B |
| 8086:15d2 | 17aa:22be | Intel      | JHL6540 Thunderbolt 3 NHI... | 6     | thunder... | 65033505B7 |
| 8086:15eb | 103c:857f | Intel      | JHL7540 Thunderbolt 3 NHI... | 6     | thunder... | 465B51ACD4 |
| 8086:1911 | 1028:089e | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 6     |            | C52711AB47 |
| 8086:1911 | 1028:08e2 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 6     |            | ADF32CA36B |
| 8086:1911 | 17aa:22be | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 6     |            | 65033505B7 |
| 8086:3190 | 17aa:3801 | Intel      | Celeron/Pentium Silver Pr... | 6     |            | 17E78AF479 |
| 8086:9a11 | 103c:87f7 | Intel      | GNA Scoring Accelerator m... | 6     |            | E1D0678746 |
| 8086:09ab | 103c:8825 | Intel      | System peripheral            | 5     |            | 24060045B4 |
| 8086:15bf | 17aa:2294 | Intel      | JHL6240 Thunderbolt 3 NHI... | 5     | thunder... | 3C03CE796F |
| 8086:15bf | 17aa:22ad | Intel      | JHL6240 Thunderbolt 3 NHI... | 5     | thunder... | 50C28ABBA1 |
| 8086:15e8 | 1028:0960 | Intel      | JHL7540 Thunderbolt 3 NHI... | 5     | thunder... | 40A7A1942F |
| 8086:1911 | 1028:0895 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 5A60912D9F |
| 8086:1911 | 1028:0896 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 4D7F19A11A |
| 8086:1911 | 1028:08b6 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | B0722E1B57 |
| 8086:1911 | 1028:0960 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 40A7A1942F |
| 8086:1911 | 103c:850e | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 0A3FF1EAD5 |
| 8086:1911 | 103c:85e7 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 169477DE3F |
| 8086:1911 | 1043:1481 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 52E5D3E16D |
| 8086:1911 | 1043:1541 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 8EFC8CAADA |
| 8086:1911 | 17aa:2294 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 3C03CE796F |
| 8086:1911 | 17aa:22ad | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 50C28ABBA1 |
| 8086:1911 | 17aa:3853 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 65567A1BE4 |
| 8086:1911 | 17aa:504c | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 4983586FE5 |
| 8086:1911 | 8086:1911 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | BC5D045DEF |
| 8086:3190 | 1025:1316 | Intel      | Celeron/Pentium Silver Pr... | 5     |            | BAB6686973 |
| 8086:9a11 | 103c:8825 | Intel      | GNA Scoring Accelerator m... | 5     |            | 24060045B4 |
| 8086:15d2 | 103c:8470 | Intel      | JHL6540 Thunderbolt 3 NHI... | 4     | thunder... | 3AF4716969 |
| 8086:15d9 | 1028:08b6 | Intel      | JHL6340 Thunderbolt 3 NHI... | 4     | thunder... | B0722E1B57 |
| 8086:15d9 | 103c:8518 | Intel      | JHL6340 Thunderbolt 3 NHI... | 4     | thunder... | 64C5568456 |
| 8086:15eb | 1028:09c6 | Intel      | JHL7540 Thunderbolt 3 NHI... | 4     | thunder... | F146E46238 |
| 8086:15eb | 103c:8548 | Intel      | JHL7540 Thunderbolt 3 NHI... | 4     | thunder... | A2F9CA954A |
| 8086:15eb | 103c:863e | Intel      | JHL7540 Thunderbolt 3 NHI... | 4     | thunder... | B47C4EF32E |
| 8086:15eb | 103c:876d | Intel      | JHL7540 Thunderbolt 3 NHI... | 4     | thunder... | CA10831A1E |
| 8086:1911 | 1028:0908 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | 81E2001F6C |
| 8086:1911 | 1028:0951 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | 247867F57E |
| 8086:1911 | 1028:09c6 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | F146E46238 |
| 8086:1911 | 103c:850c | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | EEC05D1BF9 |
| 8086:1911 | 103c:85c5 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | 03D484665D |
| 8086:1911 | 103c:85c8 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | 1649B0B654 |
| 8086:1911 | 103c:85cd | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | E7DCDD4B39 |
| 8086:1911 | 17aa:3851 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | C682421190 |
| 8086:1911 | 17aa:385e | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | 358875FD3C |
| 8086:9a11 | 1028:0a5b | Intel      | GNA Scoring Accelerator m... | 4     |            | 062C3B976F |
| 8086:15bf | 2222:1111 | Intel      | JHL6240 Thunderbolt 3 NHI... | 3     | thunder... | ED5EE6C4FD |
| 8086:15d9 | 2222:1111 | Intel      | JHL6340 Thunderbolt 3 NHI... | 3     | thunder... | BE8807E1C6 |
| 8086:15e8 | 103c:86e5 | Intel      | JHL7540 Thunderbolt 3 NHI... | 3     | thunder... | 54DDD1BAEA |
| 8086:15eb | 103c:8637 | Intel      | JHL7540 Thunderbolt 3 NHI... | 3     | thunder... | F30D3F55AD |
| 8086:15eb | 17aa:3835 | Intel      | JHL7540 Thunderbolt 3 NHI... | 3     | thunder... | 783EE80F63 |
| 8086:15eb | 17aa:383d | Intel      | JHL7540 Thunderbolt 3 NHI... | 3     | thunder... | F1C4AE114C |
| 8086:1911 | 1028:089f | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | DDC277B9F6 |
| 8086:1911 | 1028:0907 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | B6EB2D9514 |
| 8086:1911 | 103c:850d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | 987181B525 |
| 8086:1911 | 1043:1c51 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | 49B0F21555 |

### Unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:31a2 | 17aa:3801 | Intel      | Celeron/Pentium Silver Pr... | 6     | intel_i... | 17E78AF479 |
| 8086:5aa2 | 17aa:3804 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_i... | 4FD337BCA7 |
| 8086:31a2 | 1028:081f | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_i... | D11804DA19 |
| 8086:5aa2 | 1043:1c80 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_i... | 7F25CF70DD |
| 8086:5aa2 | 103c:830d | Intel      | Celeron N3350/Pentium N42... | 2     | intel_i... | 27DC03B58E |
| 8086:5aa2 | 1043:1d90 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_i... | C8D3F204E5 |
| 8086:31a2 | 103c:84fa | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_i... | 345648FE18 |
| 8086:31a2 | 103c:85ca | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_i... | 363C54D31F |
| 8086:31a2 | 103c:86cf | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_i... | 33D5688BFC |
| 8086:31a2 | 1043:1182 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_i... | DE1DE1FA76 |
| 8086:5aa2 | 1043:1930 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | B6FC10EFA8 |
| 8086:5aa2 | 1043:1d60 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | 45B1907784 |
| 8086:5aa2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | 6663E08482 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9a1b | 2222:1111 | Intel      | Tiger Lake-LP Thunderbolt... | 91    | thunder... | 224CE9A44D |
| 8086:9a13 |           | Intel      | Tiger Lake-LP Thunderbolt... | 87    | xhci_pci   | 224CE9A44D |
| 8086:9a1d | 2222:1111 | Intel      | Tiger Lake-LP Thunderbolt... | 80    | thunder... | 8C3B4736CD |
| 8086:a0ed |           | Intel      | Tiger Lake-LP USB 3.2 Gen... | 72    | xhci_pci   | 224CE9A44D |
| 1022:1639 | 17aa:3812 | AMD        | Renoir/Cezanne USB 3.1       | 64    | xhci_pci   | F07B9B77F5 |
| 8086:8a13 |           | Intel      | Ice Lake Thunderbolt 3 US... | 59    | xhci_hcd   | 138EC046F1 |
| 8086:9a13 | 17aa:5089 | Intel      | Tiger Lake-LP Thunderbolt... | 59    | xhci_pci   | 1EC4861E97 |
| 8086:a0ed | 17aa:5089 | Intel      | Tiger Lake-LP USB 3.2 Gen... | 59    | xhci_pci   | 1EC4861E97 |
| 8086:9d2f | 1043:201f | Intel      | Sunrise Point-LP USB 3.0 ... | 58    | xhci_hcd   | 84CEEEACF1 |
| 8086:9d2f | 17aa:383f | Intel      | Sunrise Point-LP USB 3.0 ... | 44    | xhci_hcd   | A2717638BE |
| 1022:1639 | 103c:876e | AMD        | Renoir/Cezanne USB 3.1       | 38    | xhci_hcd   | 28B152BB19 |
| 8086:31a8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 38    | xhci_hcd   | 4DBC03E904 |
| 8086:9a1b |           | Intel      | Tiger Lake-LP Thunderbolt... | 35    | thunder... | 00AC329183 |
| 1022:1639 | 103c:876f | AMD        | Renoir/Cezanne USB 3.1       | 34    | xhci_hcd   | 5F67B298AB |
| 8086:02ed | 17aa:380a | Intel      | Comet Lake PCH-LP USB 3.1... | 33    | xhci_hcd   | 6F6E5DAF18 |
| 8086:5aa8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 33    | xhci_hcd   | AA88177E76 |
| 8086:22b5 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 30    | xhci_hcd   | 74FE90715F |
| 8086:9d2f | 103c:83b9 | Intel      | Sunrise Point-LP USB 3.0 ... | 26    | xhci_hcd   | BBB2DB43B4 |
| 8086:15d4 | 103c:8514 | Intel      | JHL6540 Thunderbolt 3 USB... | 25    | xhci_hcd   | 211EF30EF4 |
| 8086:34ed | 17aa:3805 | Intel      | Ice Lake-LP USB 3.1 xHCI ... | 25    | xhci_pci   | 740EA7B2E9 |
| 8086:9ded | 103c:8514 | Intel      | Cannon Point-LP USB 3.1 x... | 25    | xhci_hcd   | 211EF30EF4 |
| 8086:9ded | 17aa:3807 | Intel      | Cannon Point-LP USB 3.1 x... | 25    | xhci_hcd   | 4C9743CDD1 |
| 8086:15d4 | 2222:1111 | Intel      | JHL6540 Thunderbolt 3 USB... | 24    | xhci_hcd   | 3C5AC88729 |
| 1022:15e0 | 103c:85dd | AMD        | Raven USB 3.1                | 23    | xhci_pci   | C4EA79E269 |
| 1022:15e1 | 103c:85dd | AMD        | Raven USB 3.1                | 23    | xhci_pci   | C4EA79E269 |
| 8086:34ed | 1028:08b0 | Intel      | Ice Lake-LP USB 3.1 xHCI ... | 23    | xhci_hcd   | 138EC046F1 |
| 8086:9a1d |           | Intel      | Tiger Lake-LP Thunderbolt... | 23    | thunder... | 00AC329183 |
| 8086:9d2f | 17aa:2238 | Intel      | Sunrise Point-LP USB 3.0 ... | 22    | xhci_hcd   | DD105BA06B |
| 1022:15e0 | 17aa:3805 | AMD        | Raven USB 3.1                | 21    | xhci_hcd   | 6AF7A7F851 |
| 1022:15e1 | 17aa:3806 | AMD        | Raven USB 3.1                | 21    | xhci_hcd   | 6AF7A7F851 |
| 8086:15d4 | 17aa:2292 | Intel      | JHL6540 Thunderbolt 3 USB... | 21    | xhci_hcd   | 8F10E30326 |
| 8086:9d2f | 17aa:3864 | Intel      | Sunrise Point-LP USB 3.0 ... | 21    | xhci_hcd   | 72617E5DD9 |
| 8086:9ded | 1043:201f | Intel      | Cannon Point-LP USB 3.1 x... | 21    | xhci_hcd   | DBBD7A332E |
| 8086:9d2f | 17aa:386a | Intel      | Sunrise Point-LP USB 3.0 ... | 20    | xhci_hcd   | A52209C9F2 |
| 1022:15e0 | 103c:85de | AMD        | Raven USB 3.1                | 19    | xhci_hcd   | 3ADCB9ECF9 |
| 1022:15e1 | 103c:85de | AMD        | Raven USB 3.1                | 19    | xhci_hcd   | 3ADCB9ECF9 |
| 8086:34ed | 17aa:3844 | Intel      | Ice Lake-LP USB 3.1 xHCI ... | 18    | xhci_hcd   | D1DD92D46E |
| 8086:8a13 | 17aa:380a | Intel      | Ice Lake Thunderbolt 3 US... | 18    | xhci_hcd   | D1DD92D46E |
| 8086:9d2f | 103c:827d | Intel      | Sunrise Point-LP USB 3.0 ... | 18    | xhci_hcd   | 95D389BFE5 |
| 8086:9ded | 17aa:2292 | Intel      | Cannon Point-LP USB 3.1 x... | 17    | xhci_hcd   | D99F5CBFD2 |
| 1022:15e0 | 103c:83c6 | AMD        | Raven USB 3.1                | 16    | xhci_hcd   | 5174E188C0 |
| 1022:15e0 | 103c:8497 | AMD        | Raven USB 3.1                | 16    | xhci_hcd   | 0DFE108C69 |
| 1022:15e1 | 103c:83c6 | AMD        | Raven USB 3.1                | 16    | xhci_hcd   | 5174E188C0 |
| 1022:15e1 | 103c:8497 | AMD        | Raven USB 3.1                | 16    | xhci_hcd   | 0DFE108C69 |
| 8086:9d2f | 17aa:3811 | Intel      | Sunrise Point-LP USB 3.0 ... | 16    | xhci_hcd   | 350D402895 |
| 1022:15e0 | 103c:8496 | AMD        | Raven USB 3.1                | 15    | xhci_hcd   | DFB9789AF2 |
| 1022:15e1 | 103c:8496 | AMD        | Raven USB 3.1                | 15    | xhci_hcd   | DFB9789AF2 |
| 1022:1639 | 103c:8735 | AMD        | Renoir/Cezanne USB 3.1       | 15    | xhci_pci   | 4EE6C35B8F |
| 8086:02ed | 17aa:3806 | Intel      | Comet Lake PCH-LP USB 3.1... | 15    | xhci_hcd   | 527CC99B36 |
| 8086:9d2f | 1028:077a | Intel      | Sunrise Point-LP USB 3.0 ... | 15    | xhci_hcd   | 8F7ADB6CD3 |
| 8086:9d2f | 103c:830f | Intel      | Sunrise Point-LP USB 3.0 ... | 15    | xhci_hcd   | 3286ED83B9 |
| 8086:9d2f | 103c:8486 | Intel      | Sunrise Point-LP USB 3.0 ... | 15    | xhci_hcd   | 7E241B1F69 |
| 8086:9d2f | 17aa:3825 | Intel      | Sunrise Point-LP USB 3.0 ... | 15    | xhci_hcd   | AED568D94C |
| 8086:a12f | 17aa:3807 | Intel      | 100 Series/C230 Series Ch... | 15    | xhci_hcd   | C362C8CAFD |
| 8086:9a13 | 1028:09ff | Intel      | Tiger Lake-LP Thunderbolt... | 14    | xhci_hcd   | 5B10037DA5 |
| 8086:9d2f | 17aa:224e | Intel      | Sunrise Point-LP USB 3.0 ... | 14    | xhci_hcd   | 3C24D27D51 |
| 8086:9d2f | 17aa:2259 | Intel      | Sunrise Point-LP USB 3.0 ... | 14    | xhci_hcd   | 36DBFEF2B7 |
| 8086:9d2f | 17aa:3805 | Intel      | Sunrise Point-LP USB 3.0 ... | 14    | xhci_hcd   | 82ACEB2458 |
| 8086:9d2f | 17aa:383e | Intel      | Sunrise Point-LP USB 3.0 ... | 14    | xhci_hcd   | 9A20859E26 |
| 8086:a0ed | 1028:09ff | Intel      | Tiger Lake-LP USB 3.2 Gen... | 14    | xhci_hcd   | 5B10037DA5 |
| 8086:02ed | 17aa:5078 | Intel      | Comet Lake PCH-LP USB 3.1... | 13    | xhci_hcd   | 49DBAD6FDB |
| 8086:9d2f | 103c:827e | Intel      | Sunrise Point-LP USB 3.0 ... | 13    | xhci_hcd   | CCA3E863F7 |
| 8086:a12f | 103c:83bb | Intel      | 100 Series/C230 Series Ch... | 13    | xhci_hcd   | BA09E3B76F |
| 8086:02ed | 103c:866e | Intel      | Comet Lake PCH-LP USB 3.1... | 12    | xhci_pci   | 572D5CD292 |
| 8086:9d2f | 17aa:380b | Intel      | Sunrise Point-LP USB 3.0 ... | 12    | xhci_hcd   | 5154E96ABE |
| 8086:a12f | 1028:080d | Intel      | 100 Series/C230 Series Ch... | 12    | xhci_hcd   | 27D7C254CC |
| 8086:9d2f | 103c:8488 | Intel      | Sunrise Point-LP USB 3.0 ... | 11    | xhci_hcd   | 3AF23C8E87 |
| 8086:9d2f | 17aa:3861 | Intel      | Sunrise Point-LP USB 3.0 ... | 11    | xhci_hcd   | F0DA92A413 |
| 8086:9d2f | 17aa:506d | Intel      | Sunrise Point-LP USB 3.0 ... | 11    | xhci_hcd   | 99C878CD5E |
| 8086:15d4 | 103c:8438 | Intel      | JHL6540 Thunderbolt 3 USB... | 10    | xhci_hcd   | AF74E3A1EA |
| 8086:22b5 | 103c:82e1 | Intel      | Atom/Celeron/Pentium Proc... | 10    | xhci_hcd   | AB13E942F9 |
| 8086:9d2f | 103c:8438 | Intel      | Sunrise Point-LP USB 3.0 ... | 10    | xhci_hcd   | AF74E3A1EA |
| 1022:1639 | 103c:888a | AMD        | Renoir/Cezanne USB 3.1       | 9     | xhci_pci   | ED20604458 |
| 8086:02ed | 103c:86b1 | Intel      | Comet Lake PCH-LP USB 3.1... | 9     | xhci_hcd   | F3B0D882C2 |
| 8086:02ed | 103c:86b2 | Intel      | Comet Lake PCH-LP USB 3.1... | 9     | xhci_hcd   | B054E02856 |
| 8086:15e9 | 1028:0950 | Intel      | JHL7540 Thunderbolt 3 USB... | 9     | xhci_pci   | 6E2B3B5A7E |
| 8086:15ec | 103c:861f | Intel      | JHL7540 Thunderbolt 3 USB... | 9     | xhci_pci   | 48CABEDB1E |
| 8086:34ed | 103c:86f9 | Intel      | Ice Lake-LP USB 3.1 xHCI ... | 9     | xhci_hcd   | 4967676215 |
| 8086:8a13 | 103c:86f9 | Intel      | Ice Lake Thunderbolt 3 US... | 9     | xhci_hcd   | 4967676215 |
| 8086:9d2f | 103c:80d1 | Intel      | Sunrise Point-LP USB 3.0 ... | 9     | xhci_hcd   | 629D516666 |
| 8086:9d2f | 103c:81a1 | Intel      | Sunrise Point-LP USB 3.0 ... | 9     | xhci_hcd   | B37CBA5DF4 |
| 8086:9d2f | 17aa:2237 | Intel      | Sunrise Point-LP USB 3.0 ... | 9     | xhci_hcd   | 24D1BD52CC |
| 8086:9d2f | 17aa:3847 | Intel      | Sunrise Point-LP USB 3.0 ... | 9     | xhci_hcd   | E2C078E281 |
| 8086:9ded | 1028:0894 | Intel      | Cannon Point-LP USB 3.1 x... | 9     | xhci_hcd   | B07A0CF706 |
| 8086:9ded | 103c:861f | Intel      | Cannon Point-LP USB 3.1 x... | 9     | xhci_pci   | 48CABEDB1E |
| 1022:15e0 | 1043:201f | AMD        | Raven USB 3.1                | 8     | xhci_hcd   | BCF877AA15 |
| 1022:15e1 | 1043:201f | AMD        | Raven USB 3.1                | 8     | xhci_hcd   | BCF877AA15 |
| 1022:1639 | 1028:09e3 | AMD        | Renoir/Cezanne USB 3.1       | 8     | xhci_pci   | 58C4A6AD98 |
| 8086:02ed | 1028:095d | Intel      | Comet Lake PCH-LP USB 3.1... | 8     | xhci_hcd   | E85575B823 |
| 8086:02ed | 103c:863f | Intel      | Comet Lake PCH-LP USB 3.1... | 8     | xhci_hcd   | 2A2CFDB7D4 |
| 8086:15d4 |           | Intel      | JHL6540 Thunderbolt 3 USB... | 8     | xhci_hcd   | A52209C9F2 |
| 8086:15e9 | 103c:863f | Intel      | JHL7540 Thunderbolt 3 USB... | 8     | xhci_hcd   | 2A2CFDB7D4 |
| 8086:5aa8 | 1043:201f | Intel      | Celeron N3350/Pentium N42... | 8     | xhci_hcd   | 3498F0A5DF |
| 8086:9d2f | 103c:8484 | Intel      | Sunrise Point-LP USB 3.0 ... | 8     | xhci_hcd   | F3D65BB221 |
| 8086:9d2f | 17aa:506c | Intel      | Sunrise Point-LP USB 3.0 ... | 8     | xhci_hcd   | B39CD022D3 |
| 8086:9ded | 103c:85c4 | Intel      | Cannon Point-LP USB 3.1 x... | 8     | xhci_hcd   | 7D9588F740 |
| 8086:9ded | 17aa:5077 | Intel      | Cannon Point-LP USB 3.1 x... | 8     | xhci_hcd   | B9971B685A |
| 8086:02ed | 1028:0950 | Intel      | Comet Lake PCH-LP USB 3.1... | 7     | xhci_pci   | 6E2B3B5A7E |
| 8086:02ed | 1028:09cd | Intel      | Comet Lake PCH-LP USB 3.1... | 7     | xhci_pci   | 20FA4B73D7 |
| 8086:02ed | 17aa:3801 | Intel      | Comet Lake PCH-LP USB 3.1... | 7     | xhci_hcd   | 611C3C0C19 |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:5228 | 103c:888a | Realtek... |                              | 9     | rtsx_pci   | ED20604458 |
| 1002:694e | 1002:694e | AMD        | Polaris 22 XL [Radeon RX ... | 1     | amdgpu     | 07A9851CD6 |
| 10ec:5228 | 103c:88b4 | Realtek... |                              | 1     | rtsx_pci   | DA1B3EFFEA |
| 10ec-b... |           | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 1     | rtwpci     | D6005821D4 |

