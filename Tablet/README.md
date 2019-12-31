Most popular PCI devices in Tablets
===================================

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Tablets ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Multimedia controller ](#multimedia-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Non-vga unclassified device ](#non-vga-unclassified-device-pci)
   * [ Sd host controller ](#sd-host-controller-pci)
   * [ Serial bus controller ](#serial-bus-controller-pci)
   * [ Serial controller ](#serial-controller-pci)
   * [ Signal processing controller ](#signal-processing-controller-pci)
   * [ Smbus ](#smbus-pci)
   * [ Sound ](#sound-pci)
   * [ Storage/ata ](#storageata-pci)
   * [ Storage/nvme ](#storagenvme-pci)
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
| 8086:229c | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 40    | lpc_ich    | DEF82D03E0 |
| 8086:2280 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 37    | iosf_mb... | DEF82D03E0 |
| 8086:9d18 | 8086:7270 | Intel      | Sunrise Point-LP PCI Expr... | 31    | pcieport   | 85085D7FF6 |
| 8086:9d14 | 8086:7270 | Intel      | Sunrise Point-LP PCI Expr... | 25    | pcieport   | 85085D7FF6 |
| 8086:1904 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 20    | skl_uncore | 8132DC0ECA |
| 8086:9d48 | 8086:7270 | Intel      | Sunrise Point-LP LPC Cont... | 20    |            | 8132DC0ECA |
| 8086:0f1c | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 10    | lpc_ich    | 8E20344B02 |
| 8086:9d4e | 8086:7270 | Intel      | Sunrise Point LPC Control... | 10    |            | 85085D7FF6 |
| 8086:2280 | 17aa:3809 | Intel      | Atom/Celeron/Pentium Proc... | 8     | iosf_mb... | 069BD7BAEB |
| 8086:229c | 17aa:380a | Intel      | Atom/Celeron/Pentium Proc... | 8     | lpc_ich    | 069BD7BAEB |
| 8086:0f00 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 7     | iosf_mb... | 04807B451A |
| 8086:22c8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 7     | pcieport   | B276E5AAD5 |
| 8086:9d1b | 8086:7270 | Intel      | Skylake-U/Y PCIe Port #12    | 7     | pcieport   | DE5BC28564 |
| 8086:0a04 | 1414:0a04 | Intel      | Haswell-ULT DRAM Controller  | 6     | hsw_uncore | 2C6B301BC3 |
| 8086:2280 | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 6     | iosf_mb... | 53194E03EE |
| 8086:229c | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 6     | lpc_ich    | 53194E03EE |
| 8086:22c8 | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 6     | pcieport   | 53194E03EE |
| 8086:5914 | 8086:2015 | Intel      | Xeon E3-1200 v6/7th Gen C... | 6     | skl_uncore | 85085D7FF6 |
| 8086:9c43 | 1414:9c43 | Intel      | 8 Series LPC Controller      | 6     | lpc_ich    | 2C6B301BC3 |
| 8086:2280 | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 5     | iosf_mb... | 725940B944 |
| 8086:229c | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 5     | lpc_ich    | 725940B944 |
| 8086:22c8 | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 5     | pcieport   | 725940B944 |
| 8086:9d10 | 8086:7270 | Intel      | Sunrise Point-LP PCI Expr... | 5     | pcieport   | 85085D7FF6 |
| 8086:9d13 | 8086:7270 | Intel      | Sunrise Point-LP PCI Expr... | 5     | pcieport   | 591E3665B7 |
| 1002:4384 |           | AMD        | SBx00 PCI to PCI Bridge      | 4     |            | 8CBAB44CAE |
| 1002:439d | 1025:0577 | AMD        | SB7x0/SB8x0/SB9x0 LPC hos... | 4     |            | 8CBAB44CAE |
| 1022:1510 | 1022:1510 | AMD        | Family 14h Processor Root... | 4     |            | 8CBAB44CAE |
| 1022:1700 |           | AMD        | Family 12h/14h Processor ... | 4     |            | 8CBAB44CAE |
| 1022:1701 |           | AMD        | Family 12h/14h Processor ... | 4     |            | 8CBAB44CAE |
| 1022:1702 |           | AMD        | Family 12h/14h Processor ... | 4     |            | 8CBAB44CAE |
| 1022:1703 |           | AMD        | Family 12h/14h Processor ... | 4     | k10temp    | 8CBAB44CAE |
| 1022:1704 |           | AMD        | Family 12h/14h Processor ... | 4     |            | 8CBAB44CAE |
| 1022:1716 |           | AMD        | Family 12h/14h Processor ... | 4     |            | 8CBAB44CAE |
| 1022:1718 |           | AMD        | Family 12h/14h Processor ... | 4     |            | 8CBAB44CAE |
| 1022:1719 |           | AMD        | Family 12h/14h Processor ... | 4     |            | 8CBAB44CAE |
| 8086:0f00 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 4     | iosf_mb... | 3B331BB4AF |
| 8086:0f1c | 8086:0f1c | Intel      | Atom Processor Z36xxx/Z37... | 4     | lpc_ich    | 3B331BB4AF |
| 8086:2280 | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 4     | iosf_mb... | 838DD8C3AC |
| 8086:229c | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 4     | lpc_ich    | 838DD8C3AC |
| 8086:22c8 | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 4     | shpchp     | 838DD8C3AC |
| 8086:5904 | 8086:2015 | Intel      | Xeon E3-1200 v6/7th Gen C... | 4     | skl_uncore | 744DFFB47F |
| 8086:2280 | 1043:1c60 | Intel      | Atom/Celeron/Pentium Proc... | 3     | iosf_mb... | 5FCF1662DB |
| 8086:2280 | 17aa:38e3 | Intel      | Atom/Celeron/Pentium Proc... | 3     | iosf_mb... | B276E5AAD5 |
| 8086:229c | 1043:1c60 | Intel      | Atom/Celeron/Pentium Proc... | 3     | lpc_ich    | 5FCF1662DB |
| 8086:229c | 17aa:380d | Intel      | Atom/Celeron/Pentium Proc... | 3     | lpc_ich    | B276E5AAD5 |
| 8086:22c8 | 1043:1c60 | Intel      | Atom/Celeron/Pentium Proc... | 3     | pcieport   | 5FCF1662DB |
| 8086:5904 | 1028:07a4 | Intel      | Xeon E3-1200 v6/7th Gen C... | 3     | skl_uncore | 73B87C222F |
| 8086:5914 | 17aa:3821 | Intel      | Xeon E3-1200 v6/7th Gen C... | 3     | skl_uncore | 1DD80D33E5 |
| 8086:9d13 | 17aa:3838 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 1DD80D33E5 |
| 8086:9d14 | 1028:07a4 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 73B87C222F |
| 8086:9d15 | 17aa:3837 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 1DD80D33E5 |
| 8086:9d17 | 1028:07a4 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 73B87C222F |
| 8086:9d18 | 1028:07a4 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 73B87C222F |
| 8086:9d18 | 17aa:3836 | Intel      | Sunrise Point-LP PCI Expr... | 3     | pcieport   | 1DD80D33E5 |
| 8086:9d4e | 1028:07a4 | Intel      | Sunrise Point LPC Control... | 3     |            | 73B87C222F |
| 8086:9d4e | 17aa:3813 | Intel      | Sunrise Point LPC Control... | 3     |            | 1DD80D33E5 |
| 1022:1513 | 1022:1234 | AMD        | Family 14h Processor Root... | 2     | shpchp     | 8CBAB44CAE |
| 8086:0f00 | 1019:99a5 | Intel      | Atom Processor Z36xxx/Z37... | 2     | iosf_mb... | BA303FB8FF |
| 8086:0f00 | 17aa:3906 | Intel      | Atom Processor Z36xxx/Z37... | 2     | iosf_mb... | 3D33E96551 |
| 8086:0f00 | 17aa:390b | Intel      | Atom Processor Z36xxx/Z37... | 2     | iosf_mb... | 711C6B9CE4 |
| 8086:0f1c | 1019:99a5 | Intel      | Atom Processor Z36xxx/Z37... | 2     | lpc_ich    | BA303FB8FF |
| 8086:0f1c | 17aa:3906 | Intel      | Atom Processor Z36xxx/Z37... | 2     | lpc_ich    | 3D33E96551 |
| 8086:0f1c | 17aa:390b | Intel      | Atom Processor Z36xxx/Z37... | 2     | lpc_ich    | 711C6B9CE4 |
| 8086:0f48 | 1019:99a5 | Intel      | Atom Processor E3800 Seri... | 2     | pcieport   | BA303FB8FF |
| 8086:0f4a | 1019:99a5 | Intel      | Atom Processor E3800 Seri... | 2     | pcieport   | BA303FB8FF |
| 8086:1904 | 1025:111e | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | skl_uncore | 2D71938FC4 |
| 8086:2280 | 17aa:222a | Intel      | Atom/Celeron/Pentium Proc... | 2     | iosf_mb... | DF76656467 |
| 8086:590c | 152d:1182 | Intel      | Xeon E3-1200 v6/7th Gen C... | 2     | skl_uncore | 5D3C8DA69A |
| 8086:590c | 8086:590c | Intel      | Xeon E3-1200 v6/7th Gen C... | 2     | skl_uncore | EFCA370E75 |
| 8086:5ad7 |           | Intel      | Celeron N3350/Pentium N42... | 2     | pcieport   | 6DD31D6E80 |
| 8086:5ae8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | lpc_ich    | 6DD31D6E80 |
| 8086:5af0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     |            | 6DD31D6E80 |
| 8086:9c14 | 1414:9c14 | Intel      | 8 Series PCI Express Root... | 2     | pcieport   | F0C6CAD9AE |
| 8086:9d12 | 152d:1182 | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | 5D3C8DA69A |
| 8086:9d13 | 152d:1182 | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | 5D3C8DA69A |
| 8086:9d16 | 152d:1182 | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | 5D3C8DA69A |
| 8086:9d18 | 1025:111e | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | 2D71938FC4 |
| 8086:9d18 | 8086:9d18 | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcieport   | EFCA370E75 |
| 8086:9d48 | 1025:111e | Intel      | Sunrise Point-LP LPC Cont... | 2     |            | 2D71938FC4 |
| 8086:9d4b | 152d:1182 | Intel      | Skylake-U/Y LPC/eSPI Cont... | 2     |            | 5D3C8DA69A |
| 8086:9d4b | 8086:9d4b | Intel      | Skylake-U/Y LPC/eSPI Cont... | 2     |            | EFCA370E75 |
| 8086:0154 | 10f7:8338 | Intel      | 3rd Gen Core processor DR... | 1     | ivb_uncore | 68ECFC5409 |
| 8086:0154 | 1414:0154 | Intel      | 3rd Gen Core processor DR... | 1     | ivb_uncore | 34114C0F3A |
| 8086:0154 | 1b0a:017b | Intel      | 3rd Gen Core processor DR... | 1     | ivb_uncore | 5A97B2A1A7 |
| 8086:0f00 | 1019:980b | Intel      | Atom Processor Z36xxx/Z37... | 1     | iosf_mb... | E6816549A0 |
| 8086:0f00 | 1019:99a1 | Intel      | Atom Processor Z36xxx/Z37... | 1     | iosf_mb... | CF454DFC20 |
| 8086:0f00 | 103c:815d | Intel      | Atom Processor Z36xxx/Z37... | 1     | iosf_mb... | ED2994B570 |
| 8086:0f00 | 17aa:221b | Intel      | Atom Processor Z36xxx/Z37... | 1     | iosf_mb... | B1CB7238DA |
| 8086:0f00 | 17aa:221c | Intel      | Atom Processor Z36xxx/Z37... | 1     | iosf_mb... | 8E20344B02 |
| 8086:0f1c | 1019:99a1 | Intel      | Atom Processor Z36xxx/Z37... | 1     | lpc_ich    | CF454DFC20 |
| 8086:0f1c | 103c:815d | Intel      | Atom Processor Z36xxx/Z37... | 1     | lpc_ich    | ED2994B570 |
| 8086:0f48 | 1019:99a1 | Intel      | Atom Processor E3800 Seri... | 1     | pcieport   | CF454DFC20 |
| 8086:15da | 2222:1111 | Intel      | JHL6340 Thunderbolt 3 Bri... | 1     | shpchp     | 0B5AD4104E |
| 8086:1604 | 17aa:222b | Intel      | Broadwell-U Host Bridge -OPI | 1     | bdw_uncore | 5560D6A80E |
| 8086:190c | 1028:06e6 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | skl_uncore | EC07F9B3A7 |
| 8086:190c | 144d:c135 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | skl_uncore | D7B5599247 |
| 8086:190c | 19e5:3e00 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | skl_uncore | A76E9D9514 |
| 8086:1e10 | 10f7:8338 | Intel      | 7 Series/C216 Chipset Fam... | 1     | pcieport   | 68ECFC5409 |
| 8086:1e10 | 1b0a:017b | Intel      | 7 Series/C216 Chipset Fam... | 1     | pcieport   | 5A97B2A1A7 |
| 8086:1e12 | 1b0a:017b | Intel      | 7 Series/C210 Series Chip... | 1     | pcieport   | 5A97B2A1A7 |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:525a | 1028:07a4 | Realtek... | RTS525A PCI Express Card ... | 3     | rtsx_pci   | 73B87C222F |
| 10ec:5229 | 17aa:382e | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 1DD80D33E5 |
| 10ec:522a | 152d:1182 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 5D3C8DA69A |
| 10ec:522a | 103c:82cb | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | FDB567A59E |
| 10ec:525a | 1028:06e6 | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | EC07F9B3A7 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d3a | 8086:7270 | Intel      | Sunrise Point-LP CSME HEC... | 31    | mei_me     | 85085D7FF6 |
| 8086:9d3e |           | Intel      | Skylake-U/Y CSME: HECI #3    | 31    | mei_me     | 85085D7FF6 |
| 8086:9c3a | 8086:9c3a | Intel      | 8 Series HECI #0             | 4     | mei_me     | 2C6B301BC3 |
| 8086:9d3a | 1028:07a4 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | 73B87C222F |
| 8086:9d3a | 17aa:3850 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | 1DD80D33E5 |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | mei_me     | 6DD31D6E80 |
| 8086:9c3a | 1414:9c3a | Intel      | 8 Series HECI #0             | 2     | mei_me     | F0C6CAD9AE |
| 8086:9d3a | 1025:111e | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 2D71938FC4 |
| 8086:9d3a | 152d:1182 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 5D3C8DA69A |
| 8086:9d3a | 8086:9d3a | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | EFCA370E75 |
| 8086:1e3a | 10f7:8338 | Intel      | 7 Series/C216 Chipset Fam... | 1     | mei_me     | 68ECFC5409 |
| 8086:1e3a | 1414:1e3a | Intel      | 7 Series/C216 Chipset Fam... | 1     | mei_me     | 34114C0F3A |
| 8086:1e3a | 1b0a:017b | Intel      | 7 Series/C216 Chipset Fam... | 1     | mei_me     | 5A97B2A1A7 |
| 8086:9cba | 17aa:222b | Intel      | Wildcat Point-LP MEI Cont... | 1     | mei_me     | 5560D6A80E |
| 8086:9d3a | 1028:06e6 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | EC07F9B3A7 |
| 8086:9d3a | 103c:82cb | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | FDB567A59E |
| 8086:9d3a | 1043:1410 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 0B5AD4104E |
| 8086:9d3a | 144d:c135 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | D7B5599247 |
| 8086:9d3a | 144d:c14f | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 6D5B91C633 |
| 8086:9d3a | 19e5:3e00 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | A76E9D9514 |
| 8086:9d3e | 103c:82cb | Intel      | Skylake-U/Y CSME: HECI #3    | 1     |            | FDB567A59E |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 40    | mei_txe    | DEF82D03E0 |
| 8086:0f18 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 9     | mei_txe    | 8E20344B02 |
| 8086:2298 | 17aa:380a | Intel      | Atom/Celeron/Pentium Proc... | 8     | mei_txe    | 069BD7BAEB |
| 8086:2298 | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 6     | mei_txe    | 53194E03EE |
| 8086:2298 | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 5     | mei_txe    | 725940B944 |
| 8086:0f18 | 8086:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 3B331BB4AF |
| 8086:2298 | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 4     | mei_txe    | 838DD8C3AC |
| 8086:2298 | 1043:1c60 | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | 5FCF1662DB |
| 8086:2298 | 17aa:380c | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | B276E5AAD5 |
| 8086:0f18 | 1019:99a5 | Intel      | Atom Processor Z36xxx/Z37... | 2     | mei_txe    | BA303FB8FF |
| 8086:0f18 | 17aa:3906 | Intel      | Atom Processor Z36xxx/Z37... | 2     | mei_txe    | 3D33E96551 |
| 8086:0f18 | 17aa:390b | Intel      | Atom Processor Z36xxx/Z37... | 2     | mei_txe    | 711C6B9CE4 |
| 8086:0f18 | 1019:980b | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | E6816549A0 |
| 8086:0f18 | 1019:99a1 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | CF454DFC20 |
| 8086:0f18 | 103c:815d | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | ED2994B570 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 37    | i915       | DEF82D03E0 |
| 8086:1916 | 1414:0015 | Intel      | Skylake GT2 [HD Graphics ... | 9     | i915       | 93A6AC038F |
| 8086:22b0 | 17aa:3809 | Intel      | Atom/Celeron/Pentium Proc... | 8     | i915       | 069BD7BAEB |
| 8086:0f31 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 7     | i915       | 04807B451A |
| 8086:1916 | 1414:0014 | Intel      | Skylake GT2 [HD Graphics ... | 7     | i915       | DE5BC28564 |
| 8086:22b0 | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 6     | i915       | 53194E03EE |
| 8086:22b0 | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 5     | i915       | 725940B944 |
| 1002:9804 | 1025:0577 | AMD        | Wrestler [Radeon HD 6250]    | 4     | radeon     | 8CBAB44CAE |
| 8086:0a16 | 1414:0a16 | Intel      | Haswell-ULT Integrated Gr... | 4     | i915       | 2C6B301BC3 |
| 8086:0f31 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 4     | i915       | 3B331BB4AF |
| 8086:1926 | 1414:0015 | Intel      | Iris Graphics 540            | 4     | i915       | 8132DC0ECA |
| 8086:22b0 | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 4     | i915       | 838DD8C3AC |
| 8086:22b0 | 1043:1c60 | Intel      | Atom/Celeron/Pentium Proc... | 3     | i915       | 5FCF1662DB |
| 8086:22b0 | 17aa:38e3 | Intel      | Atom/Celeron/Pentium Proc... | 3     | i915       | B276E5AAD5 |
| 8086:5916 | 1028:07a4 | Intel      | HD Graphics 620              | 3     | i915       | 73B87C222F |
| 8086:5916 | 1414:0026 | Intel      | HD Graphics 620              | 3     | i915       | 744DFFB47F |
| 8086:5917 | 17aa:397a | Intel      | UHD Graphics 620             | 3     | i915       | 1DD80D33E5 |
| 10de:1c20 | 1414:0024 | Nvidia     | GP106M [GeForce GTX 1060 ... | 2     | nouveau    | A9A066D4B7 |
| 10de:1c8d | 1414:0024 | Nvidia     | GP107M [GeForce GTX 1050 ... | 2     | nouveau    | 85085D7FF6 |
| 8086:0f31 | 1019:99a5 | Intel      | Atom Processor Z36xxx/Z37... | 2     | i915       | BA303FB8FF |
| 8086:0f31 | 17aa:3906 | Intel      | Atom Processor Z36xxx/Z37... | 2     | i915       | 3D33E96551 |
| 8086:0f31 | 17aa:390b | Intel      | Atom Processor Z36xxx/Z37... | 2     | i915       | 711C6B9CE4 |
| 8086:1916 | 1025:111e | Intel      | Skylake GT2 [HD Graphics ... | 2     | i915       | 2D71938FC4 |
| 8086:22b0 | 17aa:222a | Intel      | Atom/Celeron/Pentium Proc... | 2     | i915       | DF76656467 |
| 8086:5917 | 1414:0027 | Intel      | UHD Graphics 620             | 2     | i915       | 85085D7FF6 |
| 8086:5917 | 1414:0028 | Intel      | UHD Graphics 620             | 2     | i915       | A9A066D4B7 |
| 8086:591e | 152d:1182 | Intel      | HD Graphics 615              | 2     | i915       | 5D3C8DA69A |
| 8086:591e | 8086:591e | Intel      | HD Graphics 615              | 2     | i915       | EFCA370E75 |
| 8086:0166 | 10f7:8338 | Intel      | 3rd Gen Core processor Gr... | 1     | i915       | 68ECFC5409 |
| 8086:0166 | 1414:0166 | Intel      | 3rd Gen Core processor Gr... | 1     | i915       | 34114C0F3A |
| 8086:0166 | 1b0a:017b | Intel      | 3rd Gen Core processor Gr... | 1     | i915       | 5A97B2A1A7 |
| 8086:0a16 | 1414:0005 | Intel      | Haswell-ULT Integrated Gr... | 1     | i915       | 7C5227AA3D |
| 8086:0a1e | 1414:0005 | Intel      | Haswell-ULT High Definiti... | 1     | i915       | F0C6CAD9AE |
| 8086:0f31 | 1019:980b | Intel      | Atom Processor Z36xxx/Z37... | 1     | i915       | E6816549A0 |
| 8086:0f31 | 1019:99a1 | Intel      | Atom Processor Z36xxx/Z37... | 1     | i915       | CF454DFC20 |
| 8086:0f31 | 103c:815d | Intel      | Atom Processor Z36xxx/Z37... | 1     | i915       | ED2994B570 |
| 8086:0f31 | 17aa:221b | Intel      | Atom Processor Z36xxx/Z37... | 1     | i915       | B1CB7238DA |
| 8086:0f31 | 17aa:221c | Intel      | Atom Processor Z36xxx/Z37... | 1     | i915       | 8E20344B02 |
| 8086:161e | 17aa:222b | Intel      | HD Graphics 5300             | 1     | i915       | 5560D6A80E |
| 8086:191e | 1028:06e6 | Intel      | HD Graphics 515              | 1     | i915       | EC07F9B3A7 |
| 8086:191e | 144d:c135 | Intel      | HD Graphics 515              | 1     | i915       | D7B5599247 |
| 8086:191e | 19e5:3e00 | Intel      | HD Graphics 515              | 1     | i915       | A76E9D9514 |
| 8086:22b0 | 1297:1008 | Intel      | Atom/Celeron/Pentium Proc... | 1     | i915       | 03137C3E6D |
| 8086:5916 | 1414:0027 | Intel      | HD Graphics 620              | 1     | i915       | 7B8D6F4557 |
| 8086:5916 | 144d:c14f | Intel      | HD Graphics 620              | 1     | i915       | 6D5B91C633 |
| 8086:5917 | 1414:0025 | Intel      | UHD Graphics 620             | 1     | i915       | DBF25F43EB |
| 8086:5917 | 1414:0026 | Intel      | UHD Graphics 620             | 1     | i915       | 591E3665B7 |
| 8086:591e | 1043:1410 | Intel      | HD Graphics 615              | 1     | i915       | 0B5AD4104E |
| 8086:591e | 1414:0026 | Intel      | HD Graphics 615              | 1     | i915       | 428581C02E |
| 8086:5926 | 103c:82cb | Intel      | Iris Plus Graphics 640       | 1     | i915       | FDB567A59E |
| 8086:5a84 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | i915       | 05764955D2 |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics 500              | 1     | i915       | 6DD31D6E80 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d21 | 8086:7270 | Intel      | Sunrise Point-LP PMC         | 31    |            | 85085D7FF6 |
| 8086:9d21 | 1028:07a4 | Intel      | Sunrise Point-LP PMC         | 3     |            | 73B87C222F |
| 8086:9d21 | 17aa:3853 | Intel      | Sunrise Point-LP PMC         | 3     |            | 1DD80D33E5 |
| 8086:9d21 | 1025:111e | Intel      | Sunrise Point-LP PMC         | 2     |            | 2D71938FC4 |
| 8086:9d21 | 152d:1182 | Intel      | Sunrise Point-LP PMC         | 2     |            | 5D3C8DA69A |
| 8086:9d21 | 8086:9d21 | Intel      | Sunrise Point-LP PMC         | 2     |            | EFCA370E75 |
| 8086:9d21 | 1028:06e6 | Intel      | Sunrise Point-LP PMC         | 1     |            | EC07F9B3A7 |
| 8086:9d21 | 103c:82cb | Intel      | Sunrise Point-LP PMC         | 1     |            | FDB567A59E |
| 8086:9d21 | 1043:1410 | Intel      | Sunrise Point-LP PMC         | 1     |            | 0B5AD4104E |
| 8086:9d21 | 144d:c135 | Intel      | Sunrise Point-LP PMC         | 1     |            | D7B5599247 |
| 8086:9d21 | 144d:c14f | Intel      | Sunrise Point-LP PMC         | 1     |            | 6D5B91C633 |
| 8086:9d21 | 19e5:3e00 | Intel      | Sunrise Point-LP PMC         | 1     |            | A76E9D9514 |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 36    | intel_a... | DEF82D03E0 |
| 8086:1919 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 31    | ipu3_imgu  | 85085D7FF6 |
| 8086:9d32 | 8086:7270 | Intel      | Skylake-U/Y Camera IO Hos... | 30    | ipu3_cio2  | 85085D7FF6 |
| 8086:22b8 | 17aa:3809 | Intel      | Atom/Celeron/Pentium Proc... | 8     | intel_a... | 069BD7BAEB |
| 8086:22b8 | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 6     | intel_a... | 53194E03EE |
| 8086:22b8 | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 5     | intel_a... | 725940B944 |
| 8086:22b8 | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 4     |            | 838DD8C3AC |
| 8086:9d32 |           | Intel      | Skylake-U/Y Camera IO Hos... | 4     | ipu3_cio2  | 2D71938FC4 |
| 8086:1919 | 1028:07a4 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | ipu3_imgu  | 73B87C222F |
| 8086:1919 | 17aa:382f | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     |            | 1DD80D33E5 |
| 8086:22b8 | 1043:1c60 | Intel      | Atom/Celeron/Pentium Proc... | 3     | intel_a... | 5FCF1662DB |
| 8086:22b8 | 17aa:38e3 | Intel      | Atom/Celeron/Pentium Proc... | 3     | intel_a... | B276E5AAD5 |
| 8086:9d32 | 1028:07a4 | Intel      | Skylake-U/Y Camera IO Hos... | 3     | ipu3_cio2  | 73B87C222F |
| 8086:9d32 | 17aa:380c | Intel      | Skylake-U/Y Camera IO Hos... | 3     | ipu3_cio2  | 1DD80D33E5 |
| 8086:0f38 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 2     |            | 0A96B79D5F |
| 8086:1919 | 1025:111e | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     |            | 2D71938FC4 |
| 8086:1919 | 152d:1182 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     |            | 5D3C8DA69A |
| 8086:1919 | 8086:1919 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | ipu3_imgu  | EFCA370E75 |
| 8086:22b8 | 17aa:222a | Intel      | Atom/Celeron/Pentium Proc... | 2     | intel_a... | DF76656467 |
| 8086:5a88 |           | Intel      | Celeron N3350/Pentium N42... | 2     |            | 6DD31D6E80 |
| 8086:9d32 | 8086:9d32 | Intel      | Skylake-U/Y Camera IO Hos... | 2     | ipu3_cio2  | EFCA370E75 |
| 8086:1919 | 1028:06e6 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | ipu3_imgu  | EC07F9B3A7 |
| 8086:1919 | 103c:82cb | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     |            | FDB567A59E |
| 8086:1919 | 144d:c135 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     |            | D7B5599247 |
| 8086:1919 | 144d:c14f | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | ipu3_imgu  | 6D5B91C633 |
| 8086:1919 | 19e5:3e00 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     |            | A76E9D9514 |
| 8086:22b8 | 1297:1008 | Intel      | Atom/Celeron/Pentium Proc... | 1     | intel_a... | 03137C3E6D |
| 8086:9d32 | 1028:06e6 | Intel      | Skylake-U/Y Camera IO Hos... | 1     | ipu3_cio2  | EC07F9B3A7 |
| 8086:9d32 | 103c:82cb | Intel      | Skylake-U/Y Camera IO Hos... | 1     | ipu3_cio2  | FDB567A59E |
| 8086:9d32 | 1043:1410 | Intel      | Skylake-U/Y Camera IO Hos... | 1     |            | 0B5AD4104E |
| 8086:9d32 | 144d:c135 | Intel      | Skylake-U/Y Camera IO Hos... | 1     | ipu3_cio2  | D7B5599247 |
| 8086:9d32 | 144d:c14f | Intel      | Skylake-U/Y Camera IO Hos... | 1     | ipu3_cio2  | 6D5B91C633 |
| 8086:9d32 | 19e5:3e00 | Intel      | Skylake-U/Y Camera IO Hos... | 1     | ipu3_cio2  | A76E9D9514 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8136 | 10ec:0123 | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | BA303FB8FF |
| 10ec:8168 | 1019:99fa | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 05F47D610A |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 11ab:2b38 | 0003:045e | Marvell... | 88W8897 [AVASTAR] 802.11a... | 13    | mwifiex... | 8132DC0ECA |
| 168c:0042 | 1a3b:2a51 | Qualcom... | QCA9377 802.11ac Wireless... | 12    | ath10k_pci | 5FCF1662DB |
| 8086:3165 | 8086:8010 | Intel      | Wireless 3165                | 10    | iwlwifi    | B276E5AAD5 |
| 11ab:2b38 | 0004:045e | Marvell... | 88W8897 [AVASTAR] 802.11a... | 7     | mwifiex... | DE5BC28564 |
| 11ab:2b38 | 0008:045e | Marvell... | 88W8897 [AVASTAR] 802.11a... | 5     | mwifiex... | 591E3665B7 |
| 11ab:2b38 | 0009:045e | Marvell... | 88W8897 [AVASTAR] 802.11a... | 3     | mwifiex... | 85085D7FF6 |
| 8086:095a | 8086:9010 | Intel      | Wireless 7265                | 3     | iwlwifi    | 5560D6A80E |
| 8086:24fd | 8086:0150 | Intel      | Wireless 8265 / 8275         | 3     | iwlwifi    | 73B87C222F |
| 8086:3165 | 8086:8110 | Intel      | Wireless 3165                | 3     | iwlwifi    | EFCA370E75 |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 3     | iwlwifi    | 1DD80D33E5 |
| 10ec:b723 | 10ec:b737 | Realtek... | RTL8723BE PCIe Wireless N... | 2     | rtl8723be  | BA303FB8FF |
| 11ab:2b38 | 0001:045e | Marvell... | 88W8897 [AVASTAR] 802.11a... | 2     | mwifiex... | F0C6CAD9AE |
| 11ab:2b38 | 0007:045e | Marvell... | 88W8897 [AVASTAR] 802.11a... | 2     | mwifiex... | A9A066D4B7 |
| 14e4:43ec | 105b:e095 | Broadco... | BCM4356 802.11ac Wireless... | 2     | brcmfmac   | DF76656467 |
| 168c:002b | 105b:e031 | Qualcom... | AR9285 Wireless Network A... | 2     | ath9k      | 8CBAB44CAE |
| 168c:003e | 105b:e09d | Qualcom... | QCA6174 802.11ac Wireless... | 2     | ath10k_pci | 2D71938FC4 |
| 168c:003e | 168c:3370 | Qualcom... | QCA6174 802.11ac Wireless... | 2     | ath10k_pci | 5D3C8DA69A |
| 11ab:2b38 | 0006:045e | Marvell... | 88W8897 [AVASTAR] 802.11a... | 1     | mwifiex... | DBF25F43EB |
| 14e4:43ec | 19e5:3100 | Broadco... | BCM4356 802.11ac Wireless... | 1     | brcmfmac   | A76E9D9514 |
| 168c:003e | 144d:c135 | Qualcom... | QCA6174 802.11ac Wireless... | 1     | ath10k_pci | D7B5599247 |
| 168c:003e | 144d:c14f | Qualcom... | QCA6174 802.11ac Wireless... | 1     | ath10k_pci | 6D5B91C633 |
| 8086:0887 | 8086:4062 | Intel      | Centrino Wireless-N 2230     | 1     | iwlwifi    | 5A97B2A1A7 |
| 8086:08b3 | 8086:8070 | Intel      | Wireless 3160                | 1     | iwlwifi    | CF454DFC20 |
| 8086:24f3 | 8086:0150 | Intel      | Wireless 8260                | 1     | iwlwifi    | EC07F9B3A7 |
| 8086:24f3 | 8086:8110 | Intel      | Wireless 8260                | 1     | iwlwifi    | 0B5AD4104E |
| 8086:24fd | 8086:9010 | Intel      | Wireless 8265 / 8275         | 1     | iwlwifi    | FDB567A59E |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:088e | 8086:4060 | Intel      | Centrino Advanced-N 6235     | 1     | iwlwifi    | 68ECFC5409 |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d35 | 8086:7270 | Intel      | Sunrise Point-LP Integrat... | 10    | intel_i... | 85085D7FF6 |
| 8086:22d8 | 103c:827c | Intel      | Integrated Sensor Solution   | 6     | intel_i... | 53194E03EE |
| 8086:22d8 | 1043:13a0 | Intel      | Integrated Sensor Solution   | 5     | intel_i... | 725940B944 |
| 8086:22d8 | 1043:1400 | Intel      | Integrated Sensor Solution   | 4     | intel_i... | 838DD8C3AC |
| 8086:22d8 | 1043:1c60 | Intel      | Integrated Sensor Solution   | 3     | intel_i... | 5FCF1662DB |
| 8086:9d35 | 1028:07a4 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 73B87C222F |
| 8086:9d35 | 17aa:3807 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 1DD80D33E5 |
| 8086:22d8 | 8086:7270 | Intel      | Integrated Sensor Solution   | 2     | intel_i... | DF76656467 |
| 8086:9d35 | 1025:111e | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 2D71938FC4 |
| 8086:9d35 | 152d:1182 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 5D3C8DA69A |
| 8086:9d35 | 1028:06e6 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | EC07F9B3A7 |
| 8086:9d35 | 103c:82cb | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | FDB567A59E |
| 8086:9d35 | 19e5:3e00 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | A76E9D9514 |
| 8086:9d35 | 8086:9d35 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 0B5AD4104E |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | sdhci_pci  | 6DD31D6E80 |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | sdhci_pci  | 6DD31D6E80 |
| 8086:9d2b | 8086:9d2b | Intel      | Skylake-U/Y SCC: eMMC        | 2     | sdhci_pci  | EFCA370E75 |
| 8086:9d2d | 8086:9d2d | Intel      | Sunrise Point-LP Secure D... | 2     | sdhci_pci  | EFCA370E75 |
| 8086:2295 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | sdhci_pci  | BEF5E99067 |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 6DD31D6E80 |
| 8086:9d2d | 144d:c14f | Intel      | Sunrise Point-LP Secure D... | 1     | sdhci_pci  | 6D5B91C633 |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:5ac8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | pwm_lpss   | 6DD31D6E80 |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d3d | 1028:07a4 | Intel      | Sunrise Point-LP Active M... | 3     | serial     | 73B87C222F |
| 8086:1e3d | 10f7:8338 | Intel      | 7 Series/C210 Series Chip... | 1     | serial     | 68ECFC5409 |
| 8086:9d3d | 1028:06e6 | Intel      | Sunrise Point-LP Active M... | 1     | serial     | EC07F9B3A7 |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d31 | 8086:7270 | Intel      | Sunrise Point-LP Thermal ... | 31    | intel_p... | 85085D7FF6 |
| 8086:9d60 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 31    | intel_l... | 85085D7FF6 |
| 8086:9d61 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 31    | intel_l... | 85085D7FF6 |
| 8086:9d63 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 30    | intel_l... | 85085D7FF6 |
| 8086:9d62 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 29    | intel_l... | 85085D7FF6 |
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 28    | process... | DEF82D03E0 |
| 8086:1903 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 11    | process... | 85085D7FF6 |
| 8086:9d27 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 11    | intel_l... | 85085D7FF6 |
| 8086:22dc | 7270:8086 | Intel      | Atom/Celeron/Pentium Proc... | 9     | process... | 4DA99A5639 |
| 8086:22dc | 17aa:3808 | Intel      | Atom/Celeron/Pentium Proc... | 8     | process... | 069BD7BAEB |
| 8086:22dc | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 6     | process... | 53194E03EE |
| 8086:1903 | 8086:1903 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 5     | process... | EFCA370E75 |
| 8086:22dc | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 5     | proc_th... | 725940B944 |
| 8086:9d27 | 8086:9d27 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | EFCA370E75 |
| 8086:22dc | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 4     | process... | 838DD8C3AC |
| 8086:1903 | 1028:07a4 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | process... | 73B87C222F |
| 8086:22dc | 1043:1c60 | Intel      | Atom/Celeron/Pentium Proc... | 3     | process... | 5FCF1662DB |
| 8086:22dc | 17aa:3809 | Intel      | Atom/Celeron/Pentium Proc... | 3     | process... | B276E5AAD5 |
| 8086:9d2a | 8086:9d2a | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 1DD80D33E5 |
| 8086:9d31 | 1028:07a4 | Intel      | Sunrise Point-LP Thermal ... | 3     | intel_p... | 73B87C222F |
| 8086:9d31 | 17aa:3842 | Intel      | Sunrise Point-LP Thermal ... | 3     | intel_p... | 1DD80D33E5 |
| 8086:9d60 | 1028:07a4 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 73B87C222F |
| 8086:9d60 | 17aa:3845 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 1DD80D33E5 |
| 8086:9d61 | 1028:07a4 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 73B87C222F |
| 8086:9d61 | 17aa:3840 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 1DD80D33E5 |
| 8086:9d62 | 1028:07a4 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 73B87C222F |
| 8086:9d62 | 17aa:380e | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 1DD80D33E5 |
| 8086:9d63 | 8086:9d63 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 1DD80D33E5 |
| 8086:1903 | 1025:111e | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | proc_th... | 2D71938FC4 |
| 8086:1903 | 152d:1182 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | process... | 5D3C8DA69A |
| 8086:22dc | 17aa:222a | Intel      | Atom/Celeron/Pentium Proc... | 2     | process... | DF76656467 |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_lpss | 6DD31D6E80 |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_lpss | 6DD31D6E80 |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_lpss | 6DD31D6E80 |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_lpss | 6DD31D6E80 |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_lpss | 6DD31D6E80 |
| 8086:9d27 | 152d:1182 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_l... | 5D3C8DA69A |
| 8086:9d31 | 1025:111e | Intel      | Sunrise Point-LP Thermal ... | 2     | intel_p... | 2D71938FC4 |
| 8086:9d31 | 152d:1182 | Intel      | Sunrise Point-LP Thermal ... | 2     | intel_p... | 5D3C8DA69A |
| 8086:9d31 | 8086:9d31 | Intel      | Sunrise Point-LP Thermal ... | 2     | intel_p... | EFCA370E75 |
| 8086:9d60 | 1025:111e | Intel      | Sunrise Point-LP Serial I... | 2     | intel_lpss | 2D71938FC4 |
| 8086:9d60 | 152d:1182 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_l... | 5D3C8DA69A |
| 8086:9d60 | 8086:9d60 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_l... | EFCA370E75 |
| 8086:9d61 | 1025:111e | Intel      | Sunrise Point-LP Serial I... | 2     | intel_lpss | 2D71938FC4 |
| 8086:9d61 | 152d:1182 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_l... | 5D3C8DA69A |
| 8086:9d61 | 8086:9d61 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_l... | EFCA370E75 |
| 8086:9d62 | 1025:111e | Intel      | Sunrise Point-LP Serial I... | 2     | intel_lpss | 2D71938FC4 |
| 8086:9d62 | 152d:1182 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_l... | 5D3C8DA69A |
| 8086:9d62 | 8086:9d62 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_l... | EFCA370E75 |
| 8086:9d63 | 152d:1182 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_l... | 5D3C8DA69A |
| 8086:9d64 | 152d:1182 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_l... | 5D3C8DA69A |
| 8086:9d66 | 152d:1182 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_l... | 5D3C8DA69A |
| 8086:0153 | 10f7:8338 | Intel      | 3rd Gen Core Processor Th... | 1     |            | 68ECFC5409 |
| 8086:0153 | 8086:2010 | Intel      | 3rd Gen Core Processor Th... | 1     |            | 5A97B2A1A7 |
| 8086:1603 | 17aa:222b | Intel      | Broadwell-U Processor The... | 1     | process... | 5560D6A80E |
| 8086:1903 | 1028:06e6 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | process... | EC07F9B3A7 |
| 8086:1903 | 103c:82cb | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | process... | FDB567A59E |
| 8086:1903 | 1043:1410 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | process... | 0B5AD4104E |
| 8086:1903 | 144d:c135 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | process... | D7B5599247 |
| 8086:1903 | 144d:c14f | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | process... | 6D5B91C633 |
| 8086:1903 | 19e5:3e00 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | process... | A76E9D9514 |
| 8086:1e24 | 10f7:8338 | Intel      | 7 Series/C210 Series Chip... | 1     |            | 68ECFC5409 |
| 8086:1e24 | 1b0a:017b | Intel      | 7 Series/C210 Series Chip... | 1     |            | 5A97B2A1A7 |
| 8086:5a8c |           | Intel      | Dynamic Platform and Ther... | 1     | process... | 6DD31D6E80 |
| 8086:5a8c | 8086:7270 | Intel      | Dynamic Platform and Ther... | 1     | proc_th... | 05764955D2 |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 6DD31D6E80 |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 6DD31D6E80 |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 6DD31D6E80 |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 6DD31D6E80 |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 6DD31D6E80 |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 6DD31D6E80 |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 6DD31D6E80 |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 6DD31D6E80 |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 6DD31D6E80 |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 6DD31D6E80 |
| 8086:9ca4 | 17aa:222b | Intel      | Wildcat Point-LP Thermal ... | 1     | intel_p... | 5560D6A80E |
| 8086:9d27 | 144d:c135 | Intel      | Sunrise Point-LP Serial I... | 1     | intel_l... | D7B5599247 |
| 8086:9d27 | 144d:c14f | Intel      | Sunrise Point-LP Serial I... | 1     | intel_l... | 6D5B91C633 |
| 8086:9d27 | 19e5:3e00 | Intel      | Sunrise Point-LP Serial I... | 1     | intel_l... | A76E9D9514 |
| 8086:9d28 | 19e5:3e00 | Intel      | Sunrise Point-LP Serial I... | 1     | intel_l... | A76E9D9514 |
| 8086:9d2a | 19e5:3e00 | Intel      | Sunrise Point-LP Serial I... | 1     | intel_l... | A76E9D9514 |
| 8086:9d31 | 1028:06e6 | Intel      | Sunrise Point-LP Thermal ... | 1     | intel_p... | EC07F9B3A7 |
| 8086:9d31 | 103c:82cb | Intel      | Sunrise Point-LP Thermal ... | 1     | intel_p... | FDB567A59E |
| 8086:9d31 | 1043:1410 | Intel      | Sunrise Point-LP Thermal ... | 1     | intel_p... | 0B5AD4104E |
| 8086:9d31 | 144d:c135 | Intel      | Sunrise Point-LP Thermal ... | 1     | intel_p... | D7B5599247 |
| 8086:9d31 | 144d:c14f | Intel      | Sunrise Point-LP Thermal ... | 1     | intel_p... | 6D5B91C633 |
| 8086:9d31 | 19e5:3e00 | Intel      | Sunrise Point-LP Thermal ... | 1     | intel_p... | A76E9D9514 |
| 8086:9d60 | 1028:06e6 | Intel      | Sunrise Point-LP Serial I... | 1     | intel_l... | EC07F9B3A7 |
| 8086:9d60 | 103c:82cb | Intel      | Sunrise Point-LP Serial I... | 1     | intel_l... | FDB567A59E |
| 8086:9d60 | 1043:1410 | Intel      | Sunrise Point-LP Serial I... | 1     | intel_l... | 0B5AD4104E |
| 8086:9d60 | 144d:c135 | Intel      | Sunrise Point-LP Serial I... | 1     | intel_l... | D7B5599247 |
| 8086:9d60 | 144d:c14f | Intel      | Sunrise Point-LP Serial I... | 1     | intel_l... | 6D5B91C633 |
| 8086:9d60 | 19e5:3e00 | Intel      | Sunrise Point-LP Serial I... | 1     | intel_l... | A76E9D9514 |
| 8086:9d61 | 1028:06e6 | Intel      | Sunrise Point-LP Serial I... | 1     | intel_l... | EC07F9B3A7 |
| 8086:9d61 | 144d:c135 | Intel      | Sunrise Point-LP Serial I... | 1     | intel_l... | D7B5599247 |
| 8086:9d61 | 144d:c14f | Intel      | Sunrise Point-LP Serial I... | 1     | intel_l... | 6D5B91C633 |
| 8086:9d61 | 19e5:3e00 | Intel      | Sunrise Point-LP Serial I... | 1     | intel_l... | A76E9D9514 |
| 8086:9d62 | 1028:06e6 | Intel      | Sunrise Point-LP Serial I... | 1     | intel_l... | EC07F9B3A7 |
| 8086:9d62 | 103c:82cb | Intel      | Sunrise Point-LP Serial I... | 1     | intel_l... | FDB567A59E |
| 8086:9d62 | 1043:1410 | Intel      | Sunrise Point-LP Serial I... | 1     | intel_l... | 0B5AD4104E |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9c22 | 1414:9c22 | Intel      | 8 Series SMBus Controller    | 6     | i801_smbus | 2C6B301BC3 |
| 8086:9d23 | 8086:7270 | Intel      | Sunrise Point-LP SMBus       | 5     | i801_smbus | 85085D7FF6 |
| 1002:4385 | 1025:0577 | AMD        | SBx00 SMBus Controller       | 4     | i2c_pii... | 8CBAB44CAE |
| 8086:9d23 | 1028:07a4 | Intel      | Sunrise Point-LP SMBus       | 3     | i2c_i801   | 73B87C222F |
| 8086:9d23 | 17aa:384f | Intel      | Sunrise Point-LP SMBus       | 3     | i801_smbus | 1DD80D33E5 |
| 8086:0f12 | 1019:99a5 | Intel      | Atom Processor E3800 Seri... | 2     |            | BA303FB8FF |
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     |            | 6DD31D6E80 |
| 8086:9d23 | 1025:111e | Intel      | Sunrise Point-LP SMBus       | 2     | i801_smbus | 2D71938FC4 |
| 8086:9d23 | 8086:9d23 | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | EFCA370E75 |
| 8086:0f12 | 1019:99a1 | Intel      | Atom Processor E3800 Seri... | 1     |            | CF454DFC20 |
| 8086:1e22 | 10f7:8338 | Intel      | 7 Series/C216 Chipset Fam... | 1     | i2c_i801   | 68ECFC5409 |
| 8086:1e22 | 1414:1e22 | Intel      | 7 Series/C216 Chipset Fam... | 1     | i2c_i801   | 34114C0F3A |
| 8086:1e22 | 1b0a:017b | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | 5A97B2A1A7 |
| 8086:9ca2 | 17aa:222b | Intel      | Wildcat Point-LP SMBus Co... | 1     | i2c_i801   | 5560D6A80E |
| 8086:9d23 | 1028:06e6 | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | EC07F9B3A7 |
| 8086:9d23 | 103c:82cb | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | FDB567A59E |
| 8086:9d23 | 1043:1410 | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | 0B5AD4104E |
| 8086:9d23 | 144d:c135 | Intel      | Sunrise Point-LP SMBus       | 1     |            | D7B5599247 |
| 8086:9d23 | 144d:c14f | Intel      | Sunrise Point-LP SMBus       | 1     |            | 6D5B91C633 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d70 | 8086:7270 | Intel      | Sunrise Point-LP HD Audio    | 20    | snd_hda... | 8132DC0ECA |
| 8086:9d71 | 8086:7270 | Intel      | Sunrise Point-LP HD Audio    | 11    | snd_hda... | 85085D7FF6 |
| 8086:9c20 | 1414:9c20 | Intel      | 8 Series HD Audio Controller | 6     | snd_hda... | 2C6B301BC3 |
| 1002:1314 | 1025:0577 | AMD        | Wrestler HDMI Audio          | 4     | snd_hda... | 8CBAB44CAE |
| 1002:4383 | 1025:0577 | AMD        | SBx00 Azalia (Intel HDA)     | 4     | snd_hda... | 8CBAB44CAE |
| 8086:0a0c | 8086:2010 | Intel      | Haswell-ULT HD Audio Cont... | 4     | snd_hda... | 2C6B301BC3 |
| 8086:9d71 | 1028:07a4 | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | 73B87C222F |
| 8086:9d71 | 17aa:3817 | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | 1DD80D33E5 |
| 8086:0a0c | 8086:0a0c | Intel      | Haswell-ULT HD Audio Cont... | 2     | snd_hda... | F0C6CAD9AE |
| 8086:0f04 | 1019:99fa | Intel      | Atom Processor Z36xxx/Z37... | 2     | snd_hda... | BA303FB8FF |
| 8086:22a8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 2     |            | E6EE947879 |
| 8086:9d70 | 1025:111e | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 2D71938FC4 |
| 8086:9d71 | 152d:1182 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 5D3C8DA69A |
| 8086:0f04 | 1019:99a6 | Intel      | Atom Processor Z36xxx/Z37... | 1     | snd_hda... | CF454DFC20 |
| 8086:160c | 17aa:222b | Intel      | Broadwell-U Audio Controller | 1     | snd_hda... | 5560D6A80E |
| 8086:1e20 | 10f7:8338 | Intel      | 7 Series/C216 Chipset Fam... | 1     | snd_hda... | 68ECFC5409 |
| 8086:1e20 | 1414:1e20 | Intel      | 7 Series/C216 Chipset Fam... | 1     | snd_hda... | 34114C0F3A |
| 8086:1e20 | 1b0a:0176 | Intel      | 7 Series/C216 Chipset Fam... | 1     | snd_hda... | 5A97B2A1A7 |
| 8086:5a98 | 1025:1209 | Intel      | Celeron N3350/Pentium N42... | 1     | snd_hda... | 05764955D2 |
| 8086:5a98 | 1c6c:122a | Intel      | Celeron N3350/Pentium N42... | 1     | snd_hda... | 6DD31D6E80 |
| 8086:9d70 | 144d:c135 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | D7B5599247 |
| 8086:9d70 | 19e5:3e00 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | A76E9D9514 |
| 8086:9d71 | 103c:82cb | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | FDB567A59E |
| 8086:9d71 | 1043:1410 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 0B5AD4104E |
| 8086:9d71 | 10ec:1082 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | EFCA370E75 |
| 8086:9d71 | 10ec:114a | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 70F839C5CB |
| 8086:9d71 | 144d:c14f | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 6D5B91C633 |
| 8086:9d72 | 1028:06e6 | Intel      | 300 Series Chipset Smart ... | 1     |            | EC07F9B3A7 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9c03 | 1414:9c03 | Intel      | 8 Series SATA Controller ... | 6     | ahci       | 2C6B301BC3 |
| 1002:4391 | 1025:0577 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 4     | ahci       | 8CBAB44CAE |
| 8086:9d03 | 17aa:384d | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 1DD80D33E5 |
| 8086:0f23 | 1019:99a5 | Intel      | Atom Processor E3800 Seri... | 2     | ahci       | BA303FB8FF |
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | ahci       | 6DD31D6E80 |
| 8086:9d03 | 1025:111e | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 2D71938FC4 |
| 8086:9d03 | 8086:9d03 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | EFCA370E75 |
| 8086:0f23 | 1019:99a1 | Intel      | Atom Processor E3800 Seri... | 1     | ahci       | CF454DFC20 |
| 8086:1e03 | 10f7:8338 | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | 68ECFC5409 |
| 8086:1e03 | 1414:1e03 | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | 34114C0F3A |
| 8086:1e03 | 1b0a:017b | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | 5A97B2A1A7 |
| 8086:9c83 | 17aa:222b | Intel      | Wildcat Point-LP SATA Con... | 1     | ahci       | 5560D6A80E |
| 8086:9d03 | 1028:06e6 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | EC07F9B3A7 |
| 8086:9d03 | 1043:1410 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 0B5AD4104E |
| 8086:9d03 | 144d:c135 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | D7B5599247 |
| 8086:9d03 | 144d:c14f | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 6D5B91C633 |
| 8086:9d03 | 19e5:3e00 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | A76E9D9514 |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 17    | nvme       | 8132DC0ECA |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 9     | nvme       | 6788279E04 |
| 1179:0113 | 1179:0001 | Toshiba... | BG3 NVMe SSD Controller      | 4     | nvme       | 5D3C8DA69A |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 3     | nvme       | 73B87C222F |
| 144d:a806 | 144d:a801 | Samsung... | Electronics Non-Volatile ... | 2     | nvme       | 591E3665B7 |
| 1c5c:1527 | 1c5c:1527 | SK Hynix   | Non-Volatile memory contr... | 2     | nvme       | 85085D7FF6 |
| 1179:010f | 1179:0001 | Toshiba... | NVMe Controller              | 1     | nvme       | 329795002B |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | Non-Volatile memory contr... | 1     | nvme       | DBF25F43EB |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 1     | nvme       | 744DFFB47F |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1911 | 8086:2015 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 20    |            | 8132DC0ECA |
| 8086:1911 | 8086:1911 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | EFCA370E75 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b5 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 39    | xhci_hcd   | DEF82D03E0 |
| 8086:9d2f | 8086:7270 | Intel      | Sunrise Point-LP USB 3.0 ... | 31    | xhci_hcd   | 85085D7FF6 |
| 8086:0f35 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 9     | xhci_hcd   | 8E20344B02 |
| 8086:22b5 | 17aa:3806 | Intel      | Atom/Celeron/Pentium Proc... | 8     | xhci_hcd   | 069BD7BAEB |
| 8086:22b7 | 8086:7270 | Intel      | USB Synopsys Controller      | 7     | dwc3_pci   | B67F6A8358 |
| 8086:22b5 | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 6     | xhci_hcd   | 53194E03EE |
| 8086:9c31 | 1414:9c31 | Intel      | 8 Series USB xHCI HC         | 6     | xhci_hcd   | 2C6B301BC3 |
| 8086:22b5 | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 5     | xhci_hcd   | 725940B944 |
| 1002:4396 | 1025:0577 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 4     | ehci_hcd   | 8CBAB44CAE |
| 1002:4397 | 1025:0577 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 4     | ohci_hcd   | 8CBAB44CAE |
| 8086:0f35 | 8086:0f35 | Intel      | Atom Processor Z36xxx/Z37... | 4     | xhci_pci   | 3B331BB4AF |
| 8086:22b5 | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 4     | xhci_hcd   | 838DD8C3AC |
| 8086:9c26 | 1414:9c26 | Intel      | 8 Series USB EHCI #1         | 4     | ehci_pci   | 2C6B301BC3 |
| 8086:0f37 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 3     | dwc3_pci   | 0A96B79D5F |
| 8086:22b5 | 1043:1c60 | Intel      | Atom/Celeron/Pentium Proc... | 3     | xhci_hcd   | 5FCF1662DB |
| 8086:22b5 | 17aa:380b | Intel      | Atom/Celeron/Pentium Proc... | 3     | xhci_hcd   | B276E5AAD5 |
| 8086:9d2f | 1028:07a4 | Intel      | Sunrise Point-LP USB 3.0 ... | 3     | xhci_hcd   | 73B87C222F |
| 8086:9d2f | 17aa:3851 | Intel      | Sunrise Point-LP USB 3.0 ... | 3     | xhci_hcd   | 1DD80D33E5 |
| 8086:0f35 | 1019:99a5 | Intel      | Atom Processor Z36xxx/Z37... | 2     | xhci_hcd   | 05F47D610A |
| 8086:0f35 | 17aa:3906 | Intel      | Atom Processor Z36xxx/Z37... | 2     | xhci_pci   | 3D33E96551 |
| 8086:0f35 | 17aa:390b | Intel      | Atom Processor Z36xxx/Z37... | 2     | xhci_hcd   | 711C6B9CE4 |
| 8086:5aa8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     | xhci_hcd   | 6DD31D6E80 |
| 8086:9d2f | 1025:111e | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | 2D71938FC4 |
| 8086:9d2f | 152d:1182 | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | 5D3C8DA69A |
| 8086:9d2f | 8086:9d2f | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | EFCA370E75 |
| 8086:0f34 | 1019:99a5 | Intel      | Atom Processor Z36xxx/Z37... | 1     | ehci_pci   | BA303FB8FF |
| 8086:0f35 | 1019:980b | Intel      | Atom Processor Z36xxx/Z37... | 1     | xhci_hcd   | E6816549A0 |
| 8086:0f35 | 1019:99a1 | Intel      | Atom Processor Z36xxx/Z37... | 1     | xhci_hcd   | CF454DFC20 |
| 8086:0f35 | 103c:815d | Intel      | Atom Processor Z36xxx/Z37... | 1     | xhci_hcd   | ED2994B570 |
| 8086:15db | 2222:1111 | Intel      | JHL6340 Thunderbolt 3 USB... | 1     | xhci_pci   | 0B5AD4104E |
| 8086:1e26 | 10f7:8338 | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci_pci   | 68ECFC5409 |
| 8086:1e26 | 1414:1e26 | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci_pci   | 34114C0F3A |
| 8086:1e26 | 1b0a:017b | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci_pci   | 5A97B2A1A7 |
| 8086:1e2d | 10f7:8338 | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci_pci   | 68ECFC5409 |
| 8086:1e2d | 1414:1e2d | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci_pci   | 34114C0F3A |
| 8086:1e2d | 1b0a:017b | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci_pci   | 5A97B2A1A7 |
| 8086:1e31 | 10f7:8338 | Intel      | 7 Series/C210 Series Chip... | 1     | xhci_hcd   | 68ECFC5409 |
| 8086:1e31 | 1414:1e31 | Intel      | 7 Series/C210 Series Chip... | 1     | xhci_hcd   | 34114C0F3A |
| 8086:1e31 | 1b0a:017b | Intel      | 7 Series/C210 Series Chip... | 1     | xhci_hcd   | 5A97B2A1A7 |
| 8086:22b5 |           | Intel      | Atom/Celeron/Pentium Proc... | 1     | xhci_hcd   | 4DA99A5639 |
| 8086:22b7 | 17aa:380a | Intel      | USB Synopsys Controller      | 1     | dwc3_pci   | 047598E3A4 |
| 8086:9cb1 | 17aa:222b | Intel      | Wildcat Point-LP USB xHCI... | 1     | xhci_hcd   | 5560D6A80E |
| 8086:9d2f | 1028:06e6 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | EC07F9B3A7 |
| 8086:9d2f | 103c:82cb | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | FDB567A59E |
| 8086:9d2f | 1043:201f | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_pci   | 0B5AD4104E |
| 8086:9d2f | 144d:c135 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | D7B5599247 |
| 8086:9d2f | 144d:c14f | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | 6D5B91C633 |
| 8086:9d2f | 19e5:3e00 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci_hcd   | A76E9D9514 |

