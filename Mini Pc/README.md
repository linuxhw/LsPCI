Most popular PCI devices in Mini Pcs
====================================

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Mini Pcs ](#pci-devices)
   * [ Bluetooth ](#bluetooth-pci)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Dma controller (eisa dma) ](#dma-controller-eisa-dma-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Firewire controller ](#firewire-controller-pci)
   * [ Generic system peripheral ](#generic-system-peripheral-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Iommu ](#iommu-pci)
   * [ Ipmi interface (kcs) ](#ipmi-interface-kcs-pci)
   * [ Ipmi smic interface ](#ipmi-smic-interface-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Multimedia ](#multimedia-pci)
   * [ Multimedia controller ](#multimedia-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Non-essential instrumentation ](#non-essential-instrumentation-pci)
   * [ Non-vga unclassified device ](#non-vga-unclassified-device-pci)
   * [ Performance counters ](#performance-counters-pci)
   * [ Sd host controller ](#sd-host-controller-pci)
   * [ Serial bus controller ](#serial-bus-controller-pci)
   * [ Serial controller ](#serial-controller-pci)
   * [ Signal processing controller ](#signal-processing-controller-pci)
   * [ Smbus ](#smbus-pci)
   * [ Sound ](#sound-pci)
   * [ Storage/ata ](#storageata-pci)
   * [ Storage/ide ](#storageide-pci)
   * [ Storage/nvme ](#storagenvme-pci)
   * [ Storage/raid ](#storageraid-pci)
   * [ System peripheral ](#system-peripheral-pci)
   * [ Tv card ](#tv-card-pci)
   * [ Unclassified device ](#unclassified-device-pci)
   * [ Usb controller ](#usb-controller-pci)
   * [ Others ](#others-pci)

PCI Devices
-----------

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bluetooth (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1814:3298 | 1a3b:2987 | Ralink     | RT3290 Bluetooth             | 3     |            | 121F403E29 |

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d84 | 8086:2074 | Intel      | Cannon Point-LP LPC Contr... | 116   |            | 7CA350189C |
| 8086:9db6 | 8086:2074 | Intel      | Cannon Point-LP PCI Expre... | 114   | pcieport   | 7CA350189C |
| 8086:9db8 | 8086:2074 | Intel      | Cannon Point-LP PCI Expre... | 114   | pcieport   | 7CA350189C |
| 8086:9dbc | 8086:2074 | Intel      | Cannon Point-LP PCI Expre... | 114   | pcieport   | 7CA350189C |
| 8086:9db0 | 8086:2074 | Intel      | Cannon Point-LP PCI Expre... | 113   | pcieport   | 7CA350189C |
| 8086:3ed0 | 8086:2074 | Intel      | 8th Gen Core Processor Ho... | 85    | skl_uncore | 7CA350189C |
| 8086:0f00 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 69    | iosf_mb... | DD7BEAC148 |
| 8086:0f1c | 8086:0f1c | Intel      | Atom Processor Z36xxx/Z37... | 69    | lpc_ich    | DD7BEAC148 |
| 8086:5904 | 8086:2068 | Intel      | Xeon E3-1200 v6/7th Gen C... | 58    | skl_uncore | 38D5C55BD7 |
| 8086:9d10 | 8086:2068 | Intel      | Sunrise Point-LP PCI Expr... | 58    | pcieport   | 38D5C55BD7 |
| 8086:9d4e | 8086:2068 | Intel      | Sunrise Point LPC Control... | 58    |            | 38D5C55BD7 |
| 8086:9d17 | 8086:2068 | Intel      | Sunrise Point-LP PCI Expr... | 56    | pcieport   | 38D5C55BD7 |
| 8086:9d15 | 8086:2068 | Intel      | Sunrise Point-LP PCI Expr... | 55    | pcieport   | 38D5C55BD7 |
| 8086:0284 | 8086:2081 | Intel      | Comet Lake PCH-LP LPC Pre... | 54    |            | 92AA2017B9 |
| 8086:02b5 | 8086:2081 | Intel      | Comet Lake PCH-LP PCIe Po... | 53    | pcieport   | 92AA2017B9 |
| 8086:02bc | 8086:2081 | Intel      | Comet Lake PCI Express Ro... | 52    | pcieport   | 92AA2017B9 |
| 8086:15e7 | 8086:2081 | Intel      | JHL7540 Thunderbolt 3 Bri... | 52    | pcieport   | 92AA2017B9 |
| 8086:02b0 | 8086:2081 | Intel      | Comet Lake PCI Express Ro... | 40    | pcieport   | 92AA2017B9 |
| 104c:823e |           | Texas I... | XIO2213A/B/XIO2221 PCI Ex... | 37    | shpchp     | 7EBB0672C0 |
| 8086:0f48 | 8086:0f48 | Intel      | Atom Processor E3800 Seri... | 36    | pcieport   | DD7BEAC148 |
| 8086:0f4a | 8086:0f4a | Intel      | Atom Processor E3800 Seri... | 36    | pcieport   | DD7BEAC148 |
| 8086:1604 | 8086:2057 | Intel      | Broadwell-U Host Bridge -OPI | 36    | bdw_uncore | 7E0F62D2FD |
| 8086:1e10 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 36    | pcieport   | 066B825941 |
| 8086:1e12 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 36    | pcieport   | 066B825941 |
| 8086:5af0 |           | Intel      | Celeron N3350/Pentium N42... | 36    |            | B9F5CB4E7C |
| 8086:9cc3 | 8086:2057 | Intel      | Wildcat Point-LP LPC Cont... | 36    | lpc_ich    | 7E0F62D2FD |
| 8086:0f4c | 8086:0f4c | Intel      | Atom Processor E3800 Seri... | 35    | pcieport   | DD7BEAC148 |
| 8086:0f4e | 8086:0f4e | Intel      | Atom Processor E3800 Seri... | 35    | pcieport   | DD7BEAC148 |
| 8086:1e14 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 35    | pcieport   | 066B825941 |
| 8086:1e57 | 8086:7270 | Intel      | HM77 Express Chipset LPC ... | 35    | lpc_ich    | 066B825941 |
| 8086:9c90 | 8086:2057 | Intel      | Wildcat Point-LP PCI Expr... | 35    | pcieport   | 7E0F62D2FD |
| 8086:1547 | 2222:1111 | Intel      | DSL3510 Thunderbolt Contr... | 34    | pcieport   | 066B825941 |
| 8086:5ae8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 34    | lpc_ich    | B2CC37B9AC |
| 8086:5af0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 34    |            | B2CC37B9AC |
| 8086:9c96 | 8086:2057 | Intel      | Wildcat Point-LP PCI Expr... | 34    | pcieport   | 7E0F62D2FD |
| 8086:2280 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 32    | iosf_mb... | 9E568EF477 |
| 8086:229c | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 32    | lpc_ich    | 9E568EF477 |
| 8086:22c8 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 32    | pcieport   | 9E568EF477 |
| 8086:22ca | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 32    | pcieport   | 9E568EF477 |
| 8086:9b51 | 8086:2081 | Intel      | Comet Lake-U v1 6c Host B... | 32    | skl_uncore | 92AA2017B9 |
| 8086:1901 | 8086:2073 | Intel      | 6th-10th Gen Core Process... | 31    | pcieport   | D186AF4EE3 |
| 8086:1905 | 8086:2073 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 31    | pcieport   | D186AF4EE3 |
| 8086:1909 | 8086:2073 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 31    | pcieport   | D186AF4EE3 |
| 8086:31d8 | 8086:2072 | Intel      | Gemini Lake PCI Express R... | 31    | pcieport   | 6872FA0523 |
| 8086:31da | 8086:2072 | Intel      | Gemini Lake PCI Express R... | 31    | pcieport   | 6872FA0523 |
| 8086:31e8 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 31    |            | 6872FA0523 |
| 8086:31f0 | 8086:2072 | Intel      | Gemini Lake Host Bridge      | 31    |            | 6872FA0523 |
| 8086:3ecc | 8086:2074 | Intel      | Coffee Lake Host Bridge/D... | 31    | skl_uncore | D340A44211 |
| 8086:5910 | 8086:2073 | Intel      | Xeon E3-1200 v6/7th Gen C... | 31    | skl_uncore | D186AF4EE3 |
| 8086:a110 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 31    | pcieport   | D186AF4EE3 |
| 8086:a114 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 31    | pcieport   | D186AF4EE3 |
| 8086:a152 | 8086:2073 | Intel      | HM175 Chipset LPC/eSPI Co... | 31    |            | D186AF4EE3 |
| 8086:15da | 8086:2074 | Intel      | JHL6340 Thunderbolt 3 Bri... | 30    | pcieport   | B4FB702E4A |
| 8086:22cc | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 30    | pcieport   | 9E568EF477 |
| 8086:5ada | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 29    | pcieport   | B9F5CB4E7C |
| 8086:5ae8 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 29    | lpc_ich    | B9F5CB4E7C |
| 8086:1513 |           | Intel      | CV82524 Thunderbolt Contr... | 28    | pcieport   | 7EBB0672C0 |
| 8086:a112 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 28    | pcieport   | D186AF4EE3 |
| 8086:5ad8 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 27    | pcieport   | B9F5CB4E7C |
| 8086:5ad9 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 27    | pcieport   | B9F5CB4E7C |
| 8086:a111 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 27    | pcieport   | D186AF4EE3 |
| 8086:1c10 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 26    | pcieport   | 7EBB0672C0 |
| 8086:1c12 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 26    | pcieport   | 7EBB0672C0 |
| 8086:1c14 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 26    | pcieport   | 7EBB0672C0 |
| 8086:1c49 | 8086:7270 | Intel      | HM65 Express Chipset LPC ... | 26    | lpc_ich    | 7EBB0672C0 |
| 8086:a118 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 26    | pcieport   | 16E2E1CD8A |
| 8086:229c | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 25    | lpc_ich    | CABBA2C402 |
| 8086:9d18 | 8086:2068 | Intel      | Sunrise Point-LP PCI Expr... | 25    | pcieport   | 38D5C55BD7 |
| 8086:2280 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 24    | iosf_mb... | CABBA2C402 |
| 8086:22c8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 24    | pcieport   | CABBA2C402 |
| 8086:0151 | 106b:00ff | Intel      | Xeon E3-1200 v2/3rd Gen C... | 21    | pcieport   | 066B825941 |
| 8086:0154 | 106b:00ff | Intel      | 3rd Gen Core processor DR... | 21    | ivb_uncore | 066B825941 |
| 8086:1910 | 8086:2064 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 21    | skl_uncore | D148D77A8C |
| 8086:a110 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 21    | pcieport   | D148D77A8C |
| 8086:a114 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 21    | pcieport   | D148D77A8C |
| 8086:a14e | 8086:2064 | Intel      | HM170 Chipset LPC/eSPI Co... | 21    |            | D148D77A8C |
| 8086:a112 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 20    | pcieport   | D148D77A8C |
| 8086:a111 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 19    | pcieport   | D148D77A8C |
| 1022:1700 |           | AMD        | Family 12h/14h Processor ... | 18    |            | 121F403E29 |
| 1022:1701 |           | AMD        | Family 12h/14h Processor ... | 18    |            | 121F403E29 |
| 1022:1702 |           | AMD        | Family 12h/14h Processor ... | 18    |            | 121F403E29 |
| 1022:1703 |           | AMD        | Family 12h/14h Processor ... | 18    | k10temp    | 121F403E29 |
| 1022:1704 |           | AMD        | Family 12h/14h Processor ... | 18    |            | 121F403E29 |
| 1022:1716 |           | AMD        | Family 12h/14h Processor ... | 18    |            | 121F403E29 |
| 1022:1718 |           | AMD        | Family 12h/14h Processor ... | 18    |            | 121F403E29 |
| 1022:1719 |           | AMD        | Family 12h/14h Processor ... | 18    |            | 121F403E29 |
| 8086:0a04 | 106b:0141 | Intel      | Haswell-ULT DRAM Controller  | 18    | hsw_uncore | 42B0868834 |
| 8086:156d |           | Intel      | DSL5520 Thunderbolt 2 Bri... | 18    | pcieport   | 42B0868834 |
| 8086:5ad8 |           | Intel      | Celeron N3350/Pentium N42... | 18    | pcieport   | B2CC37B9AC |
| 8086:9c10 | 8086:7270 | Intel      | 8 Series PCI Express Root... | 18    | pcieport   | 42B0868834 |
| 8086:9c14 | 8086:7270 | Intel      | 8 Series PCI Express Root... | 18    | pcieport   | 42B0868834 |
| 8086:9c16 | 8086:7270 | Intel      | 8 Series PCI Express Root... | 18    | pcieport   | 42B0868834 |
| 8086:9c18 | 8086:7270 | Intel      | 8 Series PCI Express Root... | 18    | pcieport   | 42B0868834 |
| 8086:9c43 | 8086:7270 | Intel      | 8 Series LPC Controller      | 18    | lpc_ich    | 42B0868834 |
| 1022:1452 |           | AMD        | Family 17h (Models 00h-1f... | 17    |            | DDEEE57DBD |
| 1022:15e8 |           | AMD        | Raven/Raven2 Device 24: F... | 17    |            | DDEEE57DBD |
| 1022:15e9 |           | AMD        | Raven/Raven2 Device 24: F... | 17    |            | DDEEE57DBD |
| 1022:15ea |           | AMD        | Raven/Raven2 Device 24: F... | 17    |            | DDEEE57DBD |
| 1022:15eb |           | AMD        | Raven/Raven2 Device 24: F... | 17    | k10temp    | DDEEE57DBD |
| 1022:15ec |           | AMD        | Raven/Raven2 Device 24: F... | 17    |            | DDEEE57DBD |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:522a | 8086:2074 | Realtek... | RTS522A PCI Express Card ... | 114   | rtsx_pci   | 7CA350189C |
| 10ec:5229 | 8086:2068 | Realtek... | RTS5229 PCI Express Card ... | 56    | rtsx_pci   | 38D5C55BD7 |
| 10ec:5229 | 8086:2072 | Realtek... | RTS5229 PCI Express Card ... | 31    | rtsx_pci   | 6872FA0523 |
| 10ec:5229 | 8086:2067 | Realtek... | RTS5229 PCI Express Card ... | 27    | rtsx_pci   | B9F5CB4E7C |
| 10ec:5229 | 10ec:5229 | Realtek... | RTS5229 PCI Express Card ... | 3     | rtsx_pci   | 45B14891D4 |
| 10ec:525a | 8086:3004 | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx_pci   | 93033ED87E |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0aa3 | 10de:cb79 | Nvidia     | MCP79 Co-processor           | 15    | nvidia     | F8B00A2F85 |
| 10de:0d7a | 10de:cb89 | Nvidia     | MCP89 Co-Processor           | 11    |            | 9ADEB0BD4E |
| 8086:1f18 | 8086:0000 | Intel      | Atom processor C2000 QAT     | 1     |            | C1D37659C1 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9de0 | 8086:2074 | Intel      | Cannon Point-LP MEI Contr... | 116   | mei_me     | 7CA350189C |
| 8086:9d3a | 8086:2068 | Intel      | Sunrise Point-LP CSME HEC... | 58    | mei_me     | 38D5C55BD7 |
| 8086:02e0 | 8086:2081 | Intel      | Comet Lake Management Eng... | 54    | mei_me     | 92AA2017B9 |
| 8086:1e3a | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 36    | mei_me     | 066B825941 |
| 8086:5a9a |           | Intel      | Celeron N3350/Pentium N42... | 36    | mei_me     | B9F5CB4E7C |
| 8086:9cba | 8086:2057 | Intel      | Wildcat Point-LP MEI Cont... | 36    | mei_me     | 7E0F62D2FD |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 34    | mei_me     | B2CC37B9AC |
| 8086:319a | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 31    | mei_me     | 6872FA0523 |
| 8086:a13a | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 31    | mei_me     | D186AF4EE3 |
| 8086:1c3a | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 26    | mei_me     | 7EBB0672C0 |
| 8086:a13a | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 21    | mei_me     | D148D77A8C |
| 8086:9c3a | 8086:7270 | Intel      | 8 Series HECI #0             | 18    | mei_me     | 42B0868834 |
| 8086:9d3a | 8086:2070 | Intel      | Sunrise Point-LP CSME HEC... | 14    | mei_me     | FA31D6F45C |
| 8086:9d3a | 8086:2063 | Intel      | Sunrise Point-LP CSME HEC... | 12    | mei_me     | 8747496A6B |
| 8086:a360 | 17aa:312d | Intel      | Cannon Lake PCH HECI Cont... | 12    | mei_me     | D66B009299 |
| 8086:319a | 1043:875e | Intel      | Celeron/Pentium Silver Pr... | 10    | mei_me     | 9D5F2807CE |
| 8086:5a9c |           | Intel      | Communication controller     | 9     |            | 23BDDBF63A |
| 8086:5a9e |           | Intel      | Communication controller     | 9     |            | 23BDDBF63A |
| 8086:319a | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 7     | mei_me     | 2048DCBA92 |
| 8086:a328 | 8086:7270 | Intel      | Cannon Lake PCH Serial IO... | 7     | intel_l... | D09823163E |
| 8086:a360 | 17aa:3135 | Intel      | Cannon Lake PCH HECI Cont... | 7     | mei_me     | B16B2D9BD5 |
| 8086:a360 | 8086:7270 | Intel      | Cannon Lake PCH HECI Cont... | 7     | mei_me     | D09823163E |
| 8086:9d3a | 8086:1999 | Intel      | Sunrise Point-LP CSME HEC... | 6     | mei_me     | D391C49614 |
| 8086:9cba | 8086:7270 | Intel      | Wildcat Point-LP MEI Cont... | 5     | mei_me     | 859A8D53F5 |
| 8086:9de0 | 17aa:314d | Intel      | Cannon Point-LP MEI Contr... | 5     | mei_me     | 032DB5DB0F |
| 8086:a13a | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 5     | mei_me     | A080CA6AD4 |
| 8086:a360 | 17aa:3136 | Intel      | Cannon Lake PCH HECI Cont... | 5     | mei_me     | 6F39F78FAC |
| 8086:1e3a | 19da:b211 | Intel      | 7 Series/C216 Chipset Fam... | 4     | mei_me     | EFBBD0C3F8 |
| 8086:8c3a | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 4     | mei_me     | FCAA602427 |
| 8086:9cba | 8086:2058 | Intel      | Wildcat Point-LP MEI Cont... | 4     | mei_me     | 6E19619F29 |
| 8086:a2ba | 103c:82a5 | Intel      | 200 Series PCH CSME HECI #1  | 4     | mei_me     | 08B98B6A88 |
| 8086:02e0 | 1043:87bd | Intel      | Comet Lake Management Eng... | 3     | mei_me     | 1C1741820B |
| 8086:5a9a | 8086:5a9a | Intel      | Celeron N3350/Pentium N42... | 3     | mei_me     | 161E6B136E |
| 8086:a13a | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 3     | mei_me     | 44430304D3 |
| 8086:a2ba | 103c:829a | Intel      | 200 Series PCH CSME HECI #1  | 3     | mei_me     | C326081D7D |
| 8086:06e0 | 103c:8710 | Intel      | Comet Lake HECI Controller   | 2     | mei_me     | B2A212246B |
| 8086:1c3a | 19da:b202 | Intel      | 6 Series/C200 Series Chip... | 2     | mei_me     | 4D23C29B62 |
| 8086:1e3a | 19da:a247 | Intel      | 7 Series/C216 Chipset Fam... | 2     | mei_me     | 4A3ACD7700 |
| 8086:319a | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 2     | mei_me     | E46F325CBA |
| 8086:5a9a | 8086:2080 | Intel      | Celeron N3350/Pentium N42... | 2     | mei_me     | 745C35E31C |
| 8086:5a9c | 8086:7270 | Intel      | Communication controller     | 2     |            | 1E3E739887 |
| 8086:5a9e | 8086:7270 | Intel      | Communication controller     | 2     |            | 1E3E739887 |
| 8086:8c3a | 103c:2145 | Intel      | 8 Series/C220 Series Chip... | 2     | mei_me     | 9C26D1B3DD |
| 8086:9c3a | 19da:b239 | Intel      | 8 Series HECI #0             | 2     | mei_me     | DCC5BDEF7D |
| 8086:9d3a | 103c:84f5 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | C7B3D1917B |
| 8086:9d3a | 1043:8694 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 847A813A2C |
| 8086:9de0 | 1043:8790 | Intel      | Cannon Point-LP MEI Contr... | 2     | mei_me     | 45389EF622 |
| 8086:9de0 | 17aa:314c | Intel      | Cannon Point-LP MEI Contr... | 2     | mei_me     | 0F66B49A44 |
| 8086:9de0 | 8086:2079 | Intel      | Cannon Point-LP MEI Contr... | 2     | mei_me     | 45B14891D4 |
| 8086:a0e0 | 8086:3004 | Intel      | Tiger Lake-LP Management ... | 2     | mei_me     | 93033ED87E |
| 8086:a13a | 1019:9bc6 | Intel      | 100 Series/C230 Series Ch... | 2     | mei_me     | 7101BAED7A |
| 8086:a13a | 8086:1999 | Intel      | 100 Series/C230 Series Ch... | 2     | mei_me     | D8B8CA1E48 |
| 8086:a328 | 19da:b411 | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | CF60BF6309 |
| 8086:a328 | 8086:2089 | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_lpss | 592FA60C7D |
| 8086:a360 | 103c:8458 | Intel      | Cannon Lake PCH HECI Cont... | 2     | mei_me     | 87E6E38B4A |
| 8086:a360 | 19da:b411 | Intel      | Cannon Lake PCH HECI Cont... | 2     | mei_me     | CF60BF6309 |
| 8086:a360 | 8086:2089 | Intel      | Cannon Lake PCH HECI Cont... | 2     | mei_me     | 592FA60C7D |
| 8086:02e0 | 8086:7270 | Intel      | Comet Lake Management Eng... | 1     | mei_me     | 64FFE9BE15 |
| 8086:06e0 | 103c:871a | Intel      | Comet Lake HECI Controller   | 1     | mei_me     | F74885CE0C |
| 8086:06e0 | 103c:8755 | Intel      | Comet Lake HECI Controller   | 1     |            | 334ABF8C53 |
| 8086:06e0 | 17aa:316e | Intel      | Comet Lake HECI Controller   | 1     | mei_me     | 7146ACBC96 |
| 8086:06e0 | 17aa:3172 | Intel      | Comet Lake HECI Controller   | 1     | mei_me     | 3E09AE8DEE |
| 8086:0f0a | 8086:0f0a | Intel      | Atom Processor Z36xxx/Z37... | 1     | 8250_lpss  | A968EF1DD8 |
| 8086:0f0c | 8086:0f0c | Intel      | Atom Processor Z36xxx/Z37... | 1     | 8250_lpss  | A968EF1DD8 |
| 8086:1c3a | 1734:11ba | Intel      | 6 Series/C200 Series Chip... | 1     | mei_me     | FC67594808 |
| 8086:1c3a | 19da:a217 | Intel      | 6 Series/C200 Series Chip... | 1     | mei_me     | 0909932423 |
| 8086:1e3a | 19da:a246 | Intel      | 7 Series/C216 Chipset Fam... | 1     | mei_me     | BD2FB45ED8 |
| 8086:1e3a | 1b0a:015b | Intel      | 7 Series/C216 Chipset Fam... | 1     | mei_me     | 7E54F1E784 |
| 8086:319a | 8086:319a | Intel      | Celeron/Pentium Silver Pr... | 1     | mei_me     | 5250CD21EF |
| 8086:8c3a | 19da:b206 | Intel      | 8 Series/C220 Series Chip... | 1     | mei_me     | 25982E107F |
| 8086:8c3a | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 1     | mei_me     | FF3CE414E4 |
| 8086:9c3a | 1458:5001 | Intel      | 8 Series HECI #0             | 1     | mei_me     | E6FEB379A4 |
| 8086:9c3a | 19da:b213 | Intel      | 8 Series HECI #0             | 1     | mei_me     | 2290F44E04 |
| 8086:9c3a | 19da:b248 | Intel      | 8 Series HECI #0             | 1     | mei_me     | D521E3AD79 |
| 8086:9cba | 19da:b282 | Intel      | Wildcat Point-LP MEI Cont... | 1     | mei_me     | D125ABF69E |
| 8086:9cba | 8086:9cba | Intel      | Wildcat Point-LP MEI Cont... | 1     | mei_me     | 1CAA0B4224 |
| 8086:9da8 | 8086:2075 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | 6FD8E8E647 |
| 8086:9de0 | 17aa:3144 | Intel      | Cannon Point-LP MEI Contr... | 1     | mei_me     | E64B1B05A0 |
| 8086:9de0 | 8086:2075 | Intel      | Cannon Point-LP MEI Contr... | 1     | mei_me     | 6FD8E8E647 |
| 8086:a0e0 | 8086:3003 | Intel      | Tiger Lake-LP Management ... | 1     | mei_me     | ABC31CEA35 |
| 8086:a0e0 | 8086:3013 | Intel      | Tiger Lake-LP Management ... | 1     | mei_me     | 66A02F462F |
| 8086:a13a | 15d9:0898 | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | 8658CA67D7 |
| 8086:a13b | 15d9:0898 | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | 8658CA67D7 |
| 8086:a2ba | 17aa:310b | Intel      | 200 Series PCH CSME HECI #1  | 1     | mei_me     | 84D63E297B |
| 8086:a2ba | 17aa:310c | Intel      | 200 Series PCH CSME HECI #1  | 1     | mei_me     | 60877665B6 |
| 8086:a328 | 8086:2088 | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | AECEFCDF3A |
| 8086:a360 | 103c:8457 | Intel      | Cannon Lake PCH HECI Cont... | 1     | mei_me     | C15E7F2A47 |
| 8086:a360 | 8086:2088 | Intel      | Cannon Lake PCH HECI Cont... | 1     | mei_me     | AECEFCDF3A |

### Dma controller (eisa dma) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22c0 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 18    | dw_dmac... | F084020240 |
| 8086:0f06 | 8086:0f06 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | A968EF1DD8 |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0f18 | 8086:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 70    | mei_txe    | DD7BEAC148 |
| 8086:2298 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 32    | mei_txe    | 9E568EF477 |
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 24    | mei_txe    | CABBA2C402 |
| 1022:15df | 1022:15df | AMD        | Family 17h (Models 10h-1f... | 23    | ccp        | 79EEA28A8B |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 13    |            | 5205C41BC5 |
| 8086:0f18 | 17aa:368d | Intel      | Atom Processor Z36xxx/Z37... | 9     | mei_txe    | CA54ECE919 |
| 8086:0f18 |           | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | A27BE7CA62 |
| 8086:0f18 | 19da:b219 | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 494AE0914E |
| 8086:2298 | 17aa:30dd | Intel      | Atom/Celeron/Pentium Proc... | 4     | mei_txe    | 0513ACEC04 |
| 8086:2298 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 4     | mei_txe    | 0D05B404DD |
| 1022:15df | 103c:872e | AMD        | Family 17h (Models 10h-1f... | 3     | ccp        | 7791A24770 |
| 1022:15df | 103c:8836 | AMD        | Family 17h (Models 10h-1f... | 3     | ccp        | DDEEE57DBD |
| 8086:0f18 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 3     | mei_txe    | EED35A825A |
| 8086:2298 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | FDE91E565C |
| 8086:2298 | 17aa:3637 | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | 442724EA6A |
| 8086:2298 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | 7F47BED9CF |
| 8086:0f18 | 1071:0730 | Intel      | Atom Processor Z36xxx/Z37... | 2     | mei_txe    | BE63E554C5 |
| 8086:2298 | 8086:2298 | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | 3AB4853FDD |
| 1022:15df | 103c:8523 | AMD        | Family 17h (Models 10h-1f... | 1     |            | BAB721D52E |
| 1022:15df | 103c:872c | AMD        | Family 17h (Models 10h-1f... | 1     |            | 0E48C94F83 |
| 1022:15df | 17aa:3181 | AMD        | Family 17h (Models 10h-1f... | 1     |            | A203CD8C57 |
| 8086:0f18 | 1028:07b9 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | F444E9914B |
| 8086:0f18 | 1071:0740 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | F2F4C5E23E |
| 8086:0f18 | 17aa:3688 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | A88328FDB9 |
| 8086:0f18 | 1d05:100f | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | 9569E1B79C |
| 8086:2298 | 1028:07c1 | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | 9F4F497293 |
| 8086:2298 | 1297:4033 | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | B31E28E55F |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 11c1:5901 | 11c1:5900 | LSI        | FW643 [TrueFire] PCIe 139... | 51    | firewir... | 066B825941 |
| 104c:823f |           | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 37    | firewir... | 7EBB0672C0 |
| 11c1:5811 | 11c1:5811 | LSI        | FW322/323 [TrueFire] 1394... | 14    | firewir... | C480910C6C |
| 11c1:5901 | c111:0159 | LSI        | FW643 [TrueFire] PCIe 139... | 3     | firewir... | 7EBB0672C0 |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1577 | 1022:1577 | AMD        | Family 15h (Models 60h-6f... | 13    |            | 5205C41BC5 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3ea5 | 8086:2074 | Intel      | CoffeeLake-U GT3e [Iris P... | 116   | i915       | 7CA350189C |
| 8086:0f31 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 69    | i915       | DD7BEAC148 |
| 8086:22b1 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 32    | i915       | 9E568EF477 |
| 8086:9bca | 8086:2081 | Intel      | Comet Lake UHD Graphics      | 32    | i915       | 92AA2017B9 |
| 8086:5a85 | 8086:2067 | Intel      | HD Graphics 500              | 29    | i915       | B9F5CB4E7C |
| 1002:694c | 8086:2073 | AMD        | Polaris 22 XT [Radeon RX ... | 26    | amdgpu     | D186AF4EE3 |
| 8086:591b | 8086:2073 | Intel      | HD Graphics 630              | 25    | i915       | D186AF4EE3 |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics 500              | 25    | i915       | B2CC37B9AC |
| 8086:5916 | 8086:2068 | Intel      | HD Graphics 620              | 23    | i915       | 5130ED8A73 |
| 8086:9b41 | 8086:2081 | Intel      | CometLake-U GT2 [UHD Grap... | 22    | i915       | DACE055942 |
| 8086:0166 | 106b:00ff | Intel      | 3rd Gen Core processor Gr... | 21    | i915       | 066B825941 |
| 8086:193b | 8086:2064 | Intel      | Iris Pro Graphics 580        | 21    | i915       | D148D77A8C |
| 8086:5926 | 8086:2068 | Intel      | Iris Plus Graphics 640       | 19    | i915       | 38D5C55BD7 |
| 8086:0126 | 106b:00e6 | Intel      | 2nd Generation Core Proce... | 17    | i915       | 406D34C768 |
| 8086:3185 | 8086:2072 | Intel      | GeminiLake [UHD Graphics ... | 17    | i915       | 6872FA0523 |
| 8086:1626 | 8086:2057 | Intel      | HD Graphics 6000             | 16    | i915       | 7E0F62D2FD |
| 8086:5927 | 8086:2068 | Intel      | Iris Plus Graphics 650       | 16    | i915       | 1BC6E7ACA3 |
| 10de:0861 | 106b:00ae | Nvidia     | C79 [GeForce 9400]           | 15    | nouveau    | F8B00A2F85 |
| 8086:0166 | 106b:0101 | Intel      | 3rd Gen Core processor Gr... | 14    | i915       | 1D52564CF8 |
| 8086:27a2 | 8086:7270 | Intel      | Mobile 945GM/GMS, 943/940... | 14    | i915       | C480910C6C |
| 8086:3184 | 8086:2072 | Intel      | GeminiLake [UHD Graphics ... | 14    | i915       | 032A268BA7 |
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 13    | i915       | EE3840CD1D |
| 8086:1616 | 8086:2057 | Intel      | HD Graphics 5500             | 12    | i915       | 3CFBEFF82F |
| 1002:1636 | 1043:87e7 | AMD        | Renoir                       | 11    | amdgpu     | 79EEA28A8B |
| 1002:9806 | 103c:17e2 | AMD        | Wrestler [Radeon HD 6320]    | 11    | radeon     | BF35F8C621 |
| 10de:08a4 | 106b:00c0 | Nvidia     | MCP89 [GeForce 320M]         | 11    | nouveau    | 9ADEB0BD4E |
| 8086:22b1 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 11    | i915       | CABBA2C402 |
| 8086:0a2e | 106b:0141 | Intel      | Haswell-ULT Integrated Gr... | 10    | i915       | 42B0868834 |
| 8086:3e92 | 17aa:312d | Intel      | CometLake-S GT2 [UHD Grap... | 10    | i915       | D66B009299 |
| 8086:5917 | 8086:2070 | Intel      | UHD Graphics 620             | 10    | i915       | FA31D6F45C |
| 8086:0f31 | 17aa:368d | Intel      | Atom Processor Z36xxx/Z37... | 9     | i915       | CA54ECE919 |
| 8086:3185 | 1043:875e | Intel      | GeminiLake [UHD Graphics ... | 9     | i915       | 9D5F2807CE |
| 1106:7122 | 1106:7122 | VIA Tec... | VX900 Graphics [Chrome9 HD]  | 8     |            | 15268C0CCC |
| 8086:0a26 | 106b:0141 | Intel      | Haswell-ULT Integrated Gr... | 8     | i915       | BCAEBBDED0 |
| 8086:162b | 8086:2057 | Intel      | Iris Graphics 6100           | 8     | i915       | FA8B6B861D |
| 1002:15dd | 17aa:3130 | AMD        | Raven Ridge [Radeon Vega ... | 7     | amdgpu     | DBFBDEA28F |
| 1002:6741 | 106b:00e8 | AMD        | Whistler [Radeon HD 6630M... | 7     | radeon     | 7EBB0672C0 |
| 8086:0f31 | 1027:2014 | Intel      | Atom Processor Z36xxx/Z37... | 7     | i915       | AD5481A5BC |
| 8086:1926 | 8086:2063 | Intel      | Iris Graphics 540            | 7     | i915       | EA5EDD6A1B |
| 8086:3e9b | 106b:0207 | Intel      | CoffeeLake-H GT2 [UHD Gra... | 7     | i915       | D09823163E |
| 8086:0f31 | 17aa:30b5 | Intel      | Atom Processor Z36xxx/Z37... | 6     | i915       | 538597F50A |
| 8086:5a84 | 8086:2212 | Intel      | Celeron N3350/Pentium N42... | 6     | i915       | 593A489E8D |
| 8086:5a85 | 19da:b325 | Intel      | HD Graphics 500              | 6     | i915       | 23BDDBF63A |
| 1002:9874 | 103c:8158 | AMD        | Wani [Radeon R5/R6/R7 Gra... | 5     | amdgpu     | 95BC62EF3F |
| 8086:1916 | 8086:2063 | Intel      | Skylake GT2 [HD Graphics ... | 5     | i915       | 8747496A6B |
| 8086:3e92 | 17aa:3135 | Intel      | CometLake-S GT2 [UHD Grap... | 5     | i915       | B16B2D9BD5 |
| 1002:15d8 | 17aa:3151 | AMD        | Picasso                      | 4     | amdgpu     | E57DFE6F39 |
| 1002:694e | 8086:2073 | AMD        | Polaris 22 XL [Radeon RX ... | 4     | amdgpu     | 3F3C2C6313 |
| 1002:98e4 | 17aa:312f | AMD        | Stoney [Radeon R2/R3/R4/R... | 4     | amdgpu     | 5205C41BC5 |
| 8086:0126 | 106b:00f0 | Intel      | 2nd Generation Core Proce... | 4     |            | 7EBB0672C0 |
| 8086:0156 | 19da:b211 | Intel      | 3rd Gen Core processor Gr... | 4     | i915       | EFBBD0C3F8 |
| 8086:0412 | 19da:b220 | Intel      | Xeon E3-1200 v3/4th Gen C... | 4     | i915       | FCAA602427 |
| 8086:0f31 | 19da:b219 | Intel      | Atom Processor Z36xxx/Z37... | 4     | i915       | 494AE0914E |
| 8086:0f31 | 8086:2212 | Intel      | Atom Processor Z36xxx/Z37... | 4     | i915       | EED35A825A |
| 8086:1616 | 8086:2058 | Intel      | HD Graphics 5500             | 4     | i915       | 6E19619F29 |
| 8086:22b1 | 17aa:30dd | Intel      | Atom/Celeron/Pentium Proc... | 4     | i915       | 0513ACEC04 |
| 8086:22b1 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 4     | i915       | 0D05B404DD |
| 8086:3e92 | 17aa:3136 | Intel      | CometLake-S GT2 [UHD Grap... | 4     | i915       | 6F39F78FAC |
| 8086:3ea0 | 17aa:314d | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 4     | i915       | 032DB5DB0F |
| 8086:5916 | 8086:2070 | Intel      | HD Graphics 620              | 4     | i915       | A03DE89D54 |
| 8086:5917 | 8086:2015 | Intel      | UHD Graphics 620             | 4     | i915       | D391C49614 |
| 1002:15d8 | 103c:8836 | AMD        | Picasso                      | 3     | amdgpu     | DDEEE57DBD |
| 1002:1636 | 103c:872e | AMD        | Renoir                       | 3     | amdgpu     | 7791A24770 |
| 1002:9802 | 19da:a191 | AMD        | Wrestler [Radeon HD 6310]    | 3     | radeon     | 121F403E29 |
| 1002:98e4 | 103c:8267 | AMD        | Stoney [Radeon R2/R3/R4/R... | 3     | amdgpu     | 3AA09CF72A |
| 10de:1050 | 19da:2180 | Nvidia     | GF119M [GeForce GT 520M]     | 3     | nouveau    | 49EF2577E1 |
| 10de:13b4 | 103c:82c0 | Nvidia     | GM107GLM [Quadro M620 Mob... | 3     | nvidia     | 44430304D3 |
| 10de:1c20 | 19da:2413 | Nvidia     | GP106M [GeForce GTX 1060 ... | 3     | nouveau    | 29DC0371D1 |
| 10de:1cb6 | 10de:1264 | Nvidia     | GP107GL [Quadro P620]        | 3     | nouveau    | B16B2D9BD5 |
| 8086:22b1 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 3     | i915       | FDE91E565C |
| 8086:22b1 | 17aa:3637 | Intel      | Atom/Celeron/Pentium Proc... | 3     | i915       | 442724EA6A |
| 8086:22b1 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 3     | i915       | 7F47BED9CF |
| 8086:27a6 | 8086:7270 | Intel      | Mobile 945GM/GMS/GME, 943... | 3     |            | AC61B9B105 |
| 8086:3185 | 1e50:8003 | Intel      | GeminiLake [UHD Graphics ... | 3     | i915       | 5250CD21EF |
| 8086:5a85 | 8086:2112 | Intel      | HD Graphics 500              | 3     | i915       | 1F796A44E6 |
| 8086:9b41 | 1043:87bd | Intel      | CometLake-U GT2 [UHD Grap... | 3     | i915       | 1C1741820B |
| 1002:6987 | 8086:2079 | AMD        | Lexa [Radeon 540X/550X/63... | 2     | amdgpu     | 45B14891D4 |
| 1002:9808 | 19da:a261 | AMD        | Wrestler [Radeon HD 7340]    | 2     | radeon     | 8C3CA64606 |
| 1002:9832 | 1002:0123 | AMD        | Kabini [Radeon HD 8330]      | 2     | radeon     | C6C5AE5CC4 |
| 10de:1cbb | 103c:8458 | Nvidia     | GP107GLM [Quadro P1000 Mo... | 2     | nvidia     | 87E6E38B4A |
| 8086:0116 | 106b:00e7 | Intel      | 2nd Generation Core Proce... | 2     | i915       | FC5B511989 |
| 8086:0166 | 19da:2111 | Intel      | 3rd Gen Core processor Gr... | 2     | i915       | 4A3ACD7700 |
| 8086:0412 | 103c:2145 | Intel      | Xeon E3-1200 v3/4th Gen C... | 2     | i915       | 9C26D1B3DD |
| 8086:1616 | 1e50:8002 | Intel      | HD Graphics 5500             | 2     | i915       | 003F5FF020 |
| 8086:162b | 1e50:8002 | Intel      | Iris Graphics 6100           | 2     | i915       | 7840462C30 |
| 8086:1912 | 8086:0000 | Intel      | HD Graphics 530              | 2     | i915       | D8B8CA1E48 |
| 8086:22b1 | 8086:22b1 | Intel      | Atom/Celeron/Pentium Proc... | 2     | i915       | 3AB4853FDD |
| 8086:3184 | 8086:2212 | Intel      | GeminiLake [UHD Graphics ... | 2     | i915       | 3CD7D7E119 |
| 8086:3185 |           | Intel      | GeminiLake [UHD Graphics ... | 2     | i915       | B215151D03 |
| 8086:3185 | 1028:080c | Intel      | GeminiLake [UHD Graphics ... | 2     | i915       | E46F325CBA |
| 8086:3e91 | 17aa:312d | Intel      | CoffeeLake-S GT2 [UHD Gra... | 2     | i915       | BDA0271439 |
| 8086:3e9b | 8086:2089 | Intel      | CoffeeLake-H GT2 [UHD Gra... | 2     | i915       | 592FA60C7D |
| 8086:3ea0 | 1043:8790 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 2     | i915       | 45389EF622 |
| 8086:3ea0 | 17aa:314c | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 2     | i915       | 0F66B49A44 |
| 8086:5912 | 103c:82a5 | Intel      | HD Graphics 630              | 2     | i915       | 08B98B6A88 |
| 8086:5912 | 8086:5912 | Intel      | HD Graphics 630              | 2     | i915       | 7101BAED7A |
| 8086:5916 | 103c:84f5 | Intel      | HD Graphics 620              | 2     | i915       | C7B3D1917B |
| 8086:5917 | 1043:8694 | Intel      | UHD Graphics 620             | 2     | i915       | 847A813A2C |
| 8086:5a85 | 1e50:8004 | Intel      | HD Graphics 500              | 2     | i915       | 161E6B136E |
| 8086:5a85 | 8086:2080 | Intel      | HD Graphics 500              | 2     | i915       | 745C35E31C |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 16    |            | DDEEE57DBD |
| 1022:1631 | 1022:1631 | AMD        | Renoir IOMMU                 | 15    |            | 0E48C94F83 |
| 1022:15d1 | 103c:8523 | AMD        | Raven/Raven2 IOMMU           | 1     |            | BAB721D52E |
| 8086:1f16 | 8086:0000 | Intel      | Atom processor C2000 RCEC    | 1     |            | C1D37659C1 |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816c | 1043:85b5 | Realtek... | RTL8111xP IPMI interface     | 10    |            | 79EEA28A8B |
| 10ec:816c | 17aa:3151 | Realtek... | RTL8111xP IPMI interface     | 4     |            | E57DFE6F39 |
| 10ec:816c | 103c:8523 | Realtek... | RTL8111xP IPMI interface     | 1     |            | BAB721D52E |
| 10ec:816c | 17aa:30fd | Realtek... | RTL8111xP IPMI interface     | 1     |            | 5F6F9A1C6C |
| 10ec:816c | 17aa:3181 | Realtek... | RTL8111xP IPMI interface     | 1     |            | A203CD8C57 |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816c | 17aa:3130 | Realtek... | RTL8111xP IPMI interface     | 7     |            | DBFBDEA28F |
| 10ec:816c | 10ec:8168 | Realtek... | RTL8111xP IPMI interface     | 4     | ipmi_si    | 924D89CD42 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9def | 8086:2074 | Intel      | Cannon Point-LP Shared SRAM  | 116   |            | 7CA350189C |
| 8086:9d21 | 8086:2068 | Intel      | Sunrise Point-LP PMC         | 58    |            | 38D5C55BD7 |
| 8086:02ef | 8086:2081 | Intel      | Comet Lake PCH-LP Shared ... | 54    |            | 92AA2017B9 |
| 8086:a121 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 31    |            | D186AF4EE3 |
| 8086:a121 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 21    |            | D148D77A8C |
| 10de:0a88 |           | Nvidia     | MCP79 Memory Controller      | 15    |            | F8B00A2F85 |
| 10de:0a89 |           | Nvidia     | MCP79 Memory Controller      | 15    |            | F8B00A2F85 |
| 10de:0a98 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 15    |            | F8B00A2F85 |
| 10de:0aa4 |           | Nvidia     | MCP79 Memory Controller      | 15    |            | F8B00A2F85 |
| 8086:9d21 | 8086:2070 | Intel      | Sunrise Point-LP PMC         | 14    |            | FA31D6F45C |
| 8086:9d21 | 8086:2063 | Intel      | Sunrise Point-LP PMC         | 12    |            | 8747496A6B |
| 8086:a36f | 17aa:312d | Intel      | Cannon Lake PCH Shared SRAM  | 12    |            | D66B009299 |
| 10de:0d68 |           | Nvidia     | MCP89 Memory Controller      | 11    |            | 9ADEB0BD4E |
| 10de:0d69 |           | Nvidia     | MCP89 Memory Controller      | 11    |            | 9ADEB0BD4E |
| 10de:0d6d |           | Nvidia     | MCP89 Memory Controller      | 11    |            | 9ADEB0BD4E |
| 10de:0d6e |           | Nvidia     | MCP89 Memory Controller      | 11    |            | 9ADEB0BD4E |
| 10de:0d6f |           | Nvidia     | MCP89 Memory Controller      | 11    |            | 9ADEB0BD4E |
| 10de:0d70 |           | Nvidia     | MCP89 Memory Controller      | 11    |            | 9ADEB0BD4E |
| 10de:0d71 |           | Nvidia     | MCP89 Memory Controller      | 11    |            | 9ADEB0BD4E |
| 10de:0d72 |           | Nvidia     | MCP89 Memory Controller      | 11    |            | 9ADEB0BD4E |
| 10de:0d75 |           | Nvidia     | MCP89 Memory Controller      | 11    |            | 9ADEB0BD4E |
| 10de:0d7b |           | Nvidia     | MCP89 Memory Controller      | 11    |            | 9ADEB0BD4E |
| 8086:a36f |           | Intel      | Cannon Lake PCH Shared SRAM  | 7     |            | D09823163E |
| 8086:a36f | 17aa:3135 | Intel      | Cannon Lake PCH Shared SRAM  | 7     |            | B16B2D9BD5 |
| 8086:9d21 | 8086:7270 | Intel      | Sunrise Point-LP PMC         | 6     |            | D391C49614 |
| 8086:9def | 17aa:314d | Intel      | Cannon Point-LP Shared SRAM  | 5     |            | 032DB5DB0F |
| 8086:a121 | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 5     |            | A080CA6AD4 |
| 8086:a36f | 17aa:3136 | Intel      | Cannon Lake PCH Shared SRAM  | 5     |            | 6F39F78FAC |
| 8086:a36f | 8086:7270 | Intel      | Cannon Lake PCH Shared SRAM  | 5     |            | 592FA60C7D |
| 8086:a2a1 | 103c:82a5 | Intel      | 200 Series/Z370 Chipset F... | 4     |            | 08B98B6A88 |
| 8086:02ef | 1043:87bd | Intel      | Comet Lake PCH-LP Shared ... | 3     |            | 1C1741820B |
| 8086:9def | 8086:7270 | Intel      | Cannon Point-LP Shared SRAM  | 3     |            | 45B14891D4 |
| 8086:a0ef |           | Intel      | Tiger Lake-LP Shared SRAM    | 3     |            | ABC31CEA35 |
| 8086:a121 | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 3     |            | 44430304D3 |
| 8086:a2a1 | 103c:829a | Intel      | 200 Series/Z370 Chipset F... | 3     |            | C326081D7D |
| 8086:06ef | 103c:8710 | Intel      | Comet Lake PCH Shared SRAM   | 2     |            | B2A212246B |
| 8086:9d21 | 103c:84f5 | Intel      | Sunrise Point-LP PMC         | 2     |            | C7B3D1917B |
| 8086:9d21 | 1043:8694 | Intel      | Sunrise Point-LP PMC         | 2     |            | 847A813A2C |
| 8086:9def | 1043:8790 | Intel      | Cannon Point-LP Shared SRAM  | 2     |            | 45389EF622 |
| 8086:9def | 17aa:314c | Intel      | Cannon Point-LP Shared SRAM  | 2     |            | 0F66B49A44 |
| 8086:a121 | 1019:9bc6 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 7101BAED7A |
| 8086:a121 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 2     |            | D8B8CA1E48 |
| 8086:a36f | 103c:8458 | Intel      | Cannon Lake PCH Shared SRAM  | 2     |            | 87E6E38B4A |
| 8086:02ef | 8086:7270 | Intel      | Comet Lake PCH-LP Shared ... | 1     |            | 64FFE9BE15 |
| 8086:06ef | 103c:871a | Intel      | Comet Lake PCH Shared SRAM   | 1     |            | F74885CE0C |
| 8086:06ef | 103c:8755 | Intel      | Comet Lake PCH Shared SRAM   | 1     |            | 334ABF8C53 |
| 8086:06ef | 17aa:316e | Intel      | Comet Lake PCH Shared SRAM   | 1     |            | 7146ACBC96 |
| 8086:06ef | 17aa:3172 | Intel      | Comet Lake PCH Shared SRAM   | 1     |            | 3E09AE8DEE |
| 8086:9def | 17aa:3144 | Intel      | Cannon Point-LP Shared SRAM  | 1     |            | E64B1B05A0 |
| 8086:a0ef | 8086:3013 | Intel      | Tiger Lake-LP Shared SRAM    | 1     |            | 66A02F462F |
| 8086:a121 | 15d9:0898 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 8658CA67D7 |
| 8086:a2a1 | 17aa:310b | Intel      | 200 Series/Z370 Chipset F... | 1     |            | 84D63E297B |
| 8086:a2a1 | 17aa:310c | Intel      | 200 Series/Z370 Chipset F... | 1     |            | 60877665B6 |
| 8086:a36f | 103c:8457 | Intel      | Cannon Lake PCH Shared SRAM  | 1     |            | C15E7F2A47 |

### Multimedia (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0f38 |           | Intel      | Atom Processor Z36xxx/Z37... | 1     |            | C4198C729C |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15e2 | 1022:15e2 | AMD        | Raven/Raven2/FireFlight/R... | 24    | snd_pci... | 79EEA28A8B |
| 8086:5a88 |           | Intel      | Celeron N3350/Pentium N42... | 7     |            | B2CC37B9AC |
| 8086:0f38 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 5     | intel_a... | 87E6D2F056 |
| 1022:15e2 | 103c:8523 | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | BAB721D52E |
| 109e:0878 |           | Brooktree  | Bt878 Audio Capture          | 1     |            | 10DB69DD6C |
| 8086:0f38 | 1027:2014 | Intel      | Atom Processor Z36xxx/Z37... | 1     | intel_a... | 029DA6FFCC |
| 8086:22b8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 49D8F9A43E |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:15be | 8086:2074 | Intel      | Ethernet Connection (6) I... | 115   | e1000e     | 7CA350189C |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 108   | r8169      | 161E6B136E |
| 8086:15d8 | 8086:2068 | Intel      | Ethernet Connection (4) I... | 57    | e1000e     | 38D5C55BD7 |
| 8086:0d4f | 8086:2081 | Intel      | Ethernet Connection (10) ... | 54    | e1000e     | 92AA2017B9 |
| 14e4:1686 | 14e4:1686 | Broadcom   | NetXtreme BCM57766 Gigabi... | 53    | tg3        | 066B825941 |
| 10ec:8168 | 19da:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 41    | r8169      | EB76FF1C3F |
| 14e4:16b4 | 14e4:16b4 | Broadcom   | NetXtreme BCM57765 Gigabi... | 37    | tg3        | 7EBB0672C0 |
| 8086:15a3 | 8086:2057 | Intel      | Ethernet Connection (3) I... | 36    | e1000e     | 7E0F62D2FD |
| 10ec:8168 | 8086:2072 | Realtek... | RTL8111/8168/8411 PCI Exp... | 31    | r8169      | 6872FA0523 |
| 8086:15b7 | 8086:0000 | Intel      | Ethernet Connection (2) I... | 31    | e1000e     | D186AF4EE3 |
| 10ec:8168 | 8086:2060 | Realtek... | RTL8111/8168/8411 PCI Exp... | 30    | r8169      | 9E568EF477 |
| 10ec:8168 | 8086:2067 | Realtek... | RTL8111/8168/8411 PCI Exp... | 28    | r8169      | B9F5CB4E7C |
| 8086:15b7 | 8086:2064 | Intel      | Ethernet Connection (2) I... | 21    | e1000e     | D148D77A8C |
| 10de:0ab0 | 10de:cb79 | Nvidia     | MCP79 Ethernet               | 15    | forcedeth  | F8B00A2F85 |
| 11ab:4362 | 11ab:5321 | Marvell... | 88E8053 PCI-E Gigabit Eth... | 14    | sky2       | C480910C6C |
| 8086:156f | 8086:2070 | Intel      | Ethernet Connection I219-LM  | 14    | e1000e     | FA31D6F45C |
| 10ec:8168 | 1043:8677 | Realtek... | RTL8111/8168/8411 PCI Exp... | 12    | r8169      | 9D5F2807CE |
| 8086:1570 | 8086:2063 | Intel      | Ethernet Connection I219-V   | 12    | e1000e     | 8747496A6B |
| 8086:15bc | 17aa:312d | Intel      | Ethernet Connection (7) I... | 12    | e1000e     | D66B009299 |
| 14e4:16b1 | 103c:17e2 | Broadcom   | NetLink BCM57781 Gigabit ... | 11    | tg3        | BF35F8C621 |
| 10ec:8168 | 1043:85b5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 10    | r8169      | 79EEA28A8B |
| 14e4:1692 | 14e4:9692 | Broadcom   | NetLink BCM57780 Gigabit ... | 8     | tg3        | 15268C0CCC |
| 10ec:8136 | 17aa:368d | Realtek... | RTL810xE PCI Express Fast... | 7     | r8169      | 462B8C10A5 |
| 10ec:8168 | 17aa:3130 | Realtek... | RTL8111/8168/8411 PCI Exp... | 7     | r8169      | DBFBDEA28F |
| 14e4:1686 | 106b:0099 | Broadcom   | NetXtreme BCM57766 Gigabi... | 7     | tg3        | D09823163E |
| 8086:15bb | 17aa:3135 | Intel      | Ethernet Connection (7) I... | 7     | e1000e     | B16B2D9BD5 |
| 10ec:8168 | 17aa:30b5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 6     | r8169      | 538597F50A |
| 10ec:8168 | 103c:8158 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8169      | 95BC62EF3F |
| 8086:15bb | 17aa:3136 | Intel      | Ethernet Connection (7) I... | 5     | e1000e     | 6F39F78FAC |
| 10ec:8168 | 103c:82a5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 08B98B6A88 |
| 10ec:8168 | 17aa:30dd | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 0513ACEC04 |
| 10ec:8168 | 17aa:312f | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 5205C41BC5 |
| 10ec:8168 | 17aa:314d | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 032DB5DB0F |
| 10ec:8168 | 17aa:3151 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | E57DFE6F39 |
| 10ec:8168 | 1b50:4606 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | A0C8ECBA6B |
| 10ec:8168 | 103c:8267 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 3AA09CF72A |
| 10ec:8168 | 103c:872e | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 7791A24770 |
| 10ec:8168 | 103c:8836 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8168      | DDEEE57DBD |
| 10ec:8168 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 6F659F9071 |
| 10ec:8168 | 1462:b120 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | FDE91E565C |
| 10ec:8168 | 17aa:3637 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | 442724EA6A |
| 14e4:16b0 | 106b:00f1 | Broadcom   | NetXtreme BCM57761 Gigabi... | 3     | tg3        | 7EBB0672C0 |
| 8086:0d4f | 1043:8672 | Intel      | Ethernet Connection (10) ... | 3     | e1000e     | 1C1741820B |
| 8086:15b7 | 103c:82c0 | Intel      | Ethernet Connection (2) I... | 3     | e1000e     | 44430304D3 |
| 8086:15bb | 8086:0000 | Intel      | Ethernet Connection (7) I... | 3     | e1000e     | 592FA60C7D |
| 8086:15be | 8086:0000 | Intel      | Ethernet Connection (6) I... | 3     | e1000e     | 45B14891D4 |
| 8086:15e3 | 103c:829a | Intel      | Ethernet Connection (5) I... | 3     | e1000e     | C326081D7D |
| 10ec:3000 | 1a56:3000 | Realtek... | Killer E3000 2.5GbE Contr... | 2     | r8169      | CF60BF6309 |
| 10ec:8136 | 8086:d626 | Realtek... | RTL810xE PCI Express Fast... | 2     | r8169      | E1F6C727D9 |
| 10ec:8168 | 1028:080c | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | E46F325CBA |
| 10ec:8168 | 103c:84f5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | C7B3D1917B |
| 10ec:8168 | 17aa:368d | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | CA54ECE919 |
| 168c:abcd |           | Qualcom... | Osprey Emulation Wireless... | 2     |            | 207FE36973 |
| 8086:0d4c | 103c:870f | Intel      | Ethernet Connection (11) ... | 2     | e1000e     | B2A212246B |
| 8086:153a | 103c:2145 | Intel      | Ethernet Connection I217-LM  | 2     | e1000e     | 9C26D1B3DD |
| 8086:15a2 | 8086:2058 | Intel      | Ethernet Connection (3) I... | 2     | e1000e     | AF5060B68B |
| 8086:15a3 | 8086:2058 | Intel      | Ethernet Connection (3) I... | 2     | e1000e     | 6E19619F29 |
| 8086:15bb | 103c:8458 | Intel      | Ethernet Connection (7) I... | 2     | e1000e     | 87E6E38B4A |
| 8086:15bc | 1043:8672 | Intel      | Ethernet Connection (7) I... | 2     | e1000e     | 45389EF622 |
| 8086:15bd | 17aa:314c | Intel      | Ethernet Connection (6) I... | 2     | e1000e     | 0F66B49A44 |
| 8086:15f3 | 8086:3004 | Intel      | Ethernet Controller I225-V   | 2     | igc        | 93033ED87E |
| 10ec:8136 | 1028:07b9 | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | F444E9914B |
| 10ec:8136 | 10ec:0123 | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | A90B05A0FB |
| 10ec:8136 | 10ec:8168 | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | EED35A825A |
| 10ec:8136 | 17aa:3688 | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | A88328FDB9 |
| 10ec:8168 | 1028:07c1 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 9F4F497293 |
| 10ec:8168 | 103c:8523 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | BAB721D52E |
| 10ec:8168 | 103c:872c | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 0E48C94F83 |
| 10ec:8168 | 1458:e000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | E6FEB379A4 |
| 10ec:8168 | 17aa:30fd | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 5F6F9A1C6C |
| 10ec:8168 | 17aa:3144 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | E64B1B05A0 |
| 10ec:8168 | 17aa:3181 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | A203CD8C57 |
| 10ec:8168 | 19da:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 90F8E7B807 |
| 10ec:8168 | 1b0a:015b | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 7E54F1E784 |
| 10ec:8168 | 1c6c:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | A27BE7CA62 |
| 10ec:8168 | 1d05:100f | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169, ... | 9569E1B79C |
| 14e4:1682 | 14e4:1682 | Broadcom   | NetXtreme BCM57762 Gigabi... | 1     | tg3        | B71EA2BEC1 |
| 1d6a:80b1 | 16b8:72e5 | Aquantia   | Ethernet controller          | 1     | atlantic   | D148D77A8C |
| 1d6a:87b1 | 1c7a:de2b | Aquantia   | AQC107 NBase-T/IEEE 802.3... | 1     | atlantic   | CFAD8B93A9 |
| 8086:0d4c | 103c:871a | Intel      | Ethernet Connection (11) ... | 1     | e1000e     | F74885CE0C |
| 8086:0d4c | 103c:8755 | Intel      | Ethernet Connection (11) ... | 1     |            | 334ABF8C53 |
| 8086:0d4c | 17aa:3172 | Intel      | Ethernet Connection (11) ... | 1     | e1000e     | 3E09AE8DEE |
| 8086:0d4d | 17aa:316e | Intel      | Ethernet Connection (11) ... | 1     | e1000e     | 7146ACBC96 |
| 8086:1039 | 8086:3013 | Intel      | 82801DB PRO/100 VE (LOM) ... | 1     | e100       | 4A3E3CD4EE |
| 8086:155a | 8086:0000 | Intel      | Ethernet Connection I218-LM  | 1     | e1000e     | FF3CE414E4 |
| 8086:156f | 8086:0000 | Intel      | Ethernet Connection I219-LM  | 1     | e1000e     | EFB03DB319 |
| 8086:15b7 | 1019:9bc6 | Intel      | Ethernet Connection (2) I... | 1     | e1000e     | 7101BAED7A |
| 8086:15b7 | 17aa:310b | Intel      | Ethernet Connection (2) I... | 1     | e1000e     | 84D63E297B |
| 8086:15b7 | 17aa:310c | Intel      | Ethernet Connection (2) I... | 1     | e1000e     | 60877665B6 |
| 8086:15bb | 103c:8457 | Intel      | Ethernet Connection (7) I... | 1     | e1000e     | C15E7F2A47 |
| 8086:15be | 17aa:314d | Intel      | Ethernet Connection (6) I... | 1     | e1000e     | 0F375027B9 |
| 8086:15f2 | 8086:3003 | Intel      | Ethernet Controller I225-LM  | 1     | igc        | ABC31CEA35 |
| 8086:15fb | 8086:3013 | Intel      | Ethernet Connection (13) ... | 1     | e1000e     | 66A02F462F |
| 8086:1f41 | 15d9:1f41 | Intel      | Ethernet Connection I354     | 1     | igb        | C1D37659C1 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9df0 | 8086:0034 | Intel      | Cannon Point-LP CNVi [Wir... | 123   | iwlwifi    | 7CA350189C |
| 8086:02f0 | 8086:0074 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 57    | iwlwifi    | 92AA2017B9 |
| 8086:24fd | 8086:9010 | Intel      | Wireless 8265 / 8275         | 55    | iwlwifi    | 38D5C55BD7 |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 54    | iwlwifi    | 9E568EF477 |
| 8086:095a | 8086:9010 | Intel      | Wireless 7265                | 35    | iwlwifi    | 7E0F62D2FD |
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 35    | iwlwifi    | D186AF4EE3 |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 33    | iwlwifi    | B9F5CB4E7C |
| 8086:31dc | 8086:02a4 | Intel      | Gemini Lake PCH CNVi WiFi    | 32    | iwlwifi    | 6872FA0523 |
| 8086:24f3 | 8086:9010 | Intel      | Wireless 8260                | 30    | iwlwifi    | D148D77A8C |
| 14e4:4331 | 106b:010e | Broadcom   | BCM4331 802.11a/b/g/n        | 27    | wl         | 066B825941 |
| 14e4:4331 | 14e4:4331 | Broadcom   | BCM4331 802.11a/b/g/n        | 25    | wl         | E334FAD2CC |
| 14e4:4331 | 106b:00e4 | Broadco... | BCM4331 802.11a/b/g/n        | 21    | wl         | 7EBB0672C0 |
| 14e4:43a0 | 106b:013b | Broadco... | BCM4360 802.11ac Wireless... | 18    | wl         | 42B0868834 |
| 8086:08b3 | 8086:0070 | Intel      | Wireless 3160                | 18    | iwlwifi    | EB76FF1C3F |
| 8086:3165 | 8086:8010 | Intel      | Wireless 3165                | 17    | iwlwifi    | 161E6B136E |
| 14e4:4328 | 106b:0090 | Broadco... | BCM4321 802.11a/b/g/n        | 15    | ssb        | F8B00A2F85 |
| 168c:001c | 106b:0086 | Qualcom... | AR242x / AR542x Wireless ... | 14    | ath5k      | C480910C6C |
| 8086:2723 | 8086:0084 | Intel      | Wi-Fi 6 AX200                | 14    | iwlwifi    | 0E48C94F83 |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 13    | iwlwifi    | FA31D6F45C |
| 14e4:4353 | 106b:0093 | Broadcom   | BCM43224 802.11a/b/g/n       | 11    | wl         | 9ADEB0BD4E |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 11    | iwlwifi    | 442724EA6A |
| 8086:31dc | 8086:0264 | Intel      | Gemini Lake PCH CNVi WiFi    | 11    | iwlwifi    | 2048DCBA92 |
| 10ec:b723 | 10ec:b723 | Realtek... | RTL8723BE PCIe Wireless N... | 8     | rtl8723be  | A0C8ECBA6B |
| 8086:08b3 | 8086:8070 | Intel      | Wireless 3160                | 8     | iwlwifi    | D125ABF69E |
| 14e4:4464 | 106b:07bf | Broadcom   | BCM4364 802.11ac Wireless... | 7     | brcmfmac   | D09823163E |
| 8086:2526 | 8086:0014 | Intel      | Wireless-AC 9260             | 7     | iwlwifi    | A203CD8C57 |
| 8086:3165 | 8086:8110 | Intel      | Wireless 3165                | 6     | iwlwifi    | 63E4DA1D94 |
| 8086:a370 | 8086:0030 | Intel      | Cannon Lake PCH CNVi WiFi    | 6     | iwlwifi    | 2FDE9F8D71 |
| 10ec:b723 | 17aa:b728 | Realtek... | RTL8723BE PCIe Wireless N... | 4     | rtl8723be  | 538597F50A |
| 14e4:4353 | 14e4:04d8 | Broadco... | BCM43224 802.11a/b/g/n       | 4     | wl         | AF1F6C2CD7 |
| 10ec:c821 | 17aa:c024 | Realtek... | RTL8821CE 802.11ac PCIe W... | 3     | 8821ce     | 42115A97AD |
| 1814:3290 | 1a3b:2b87 | Ralink     | RT3290 Wireless 802.11n 1... | 3     | rt2800pci  | 121F403E29 |
| 8086:0892 | 8086:0062 | Intel      | Centrino Wireless-N 135      | 3     | iwlwifi    | 4D23C29B62 |
| 8086:0896 | 8086:5005 | Intel      | Centrino Wireless-N 130      | 3     | iwlwifi    | 0909932423 |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 3     | iwlwifi    | 08B98B6A88 |
| 8086:24f3 | 8086:10b0 | Intel      | Wireless 8260                | 3     | iwlwifi    | 407F49A57D |
| 8086:31dc | 8086:0034 | Intel      | Gemini Lake PCH CNVi WiFi    | 3     | iwlwifi    | 9D5F2807CE |
| 8086:a370 | 8086:0034 | Intel      | Cannon Lake PCH CNVi WiFi    | 3     | iwlwifi    | C15E7F2A47 |
| 10ec:8179 | 1a3b:1d38 | Realtek... | RTL8188EE Wireless Networ... | 2     | rtl8188ee  | D999C674F1 |
| 10ec:b822 | 17aa:b023 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 2     | r8822be    | 9B61C385FD |
| 10ec:c822 | 17aa:c123 | Realtek... | RTL8822CE 802.11ac PCIe W... | 2     | rtw_8822ce | AFFF8115C5 |
| 14e4:4359 | 14e4:05e2 | Broadcom   | BCM43228 802.11a/b/g/n       | 2     | wl         | E96EEBB6D7 |
| 168c:002b | 1a3b:2c37 | Qualcom... | AR9285 Wireless Network A... | 2     | ath9k      | E51530BF37 |
| 168c:0034 | 11ad:6611 | Qualcom... | AR9462 Wireless Network A... | 2     | ath9k      | EED35A825A |
| 8086:08b1 | 8086:4060 | Intel      | Wireless 7260                | 2     | iwlwifi    | 1DBF853E7F |
| 8086:2723 | 1a56:1654 | Intel      | Wi-Fi 6 AX200                | 2     | iwlwifi    | CF60BF6309 |
| 8086:2723 | 8086:008c | Intel      | Wi-Fi 6 AX200                | 2     | iwlwifi    | 592FA60C7D |
| 8086:9df0 | 8086:0030 | Intel      | Cannon Point-LP CNVi [Wir... | 2     | iwlwifi    | 0F66B49A44 |
| 8086:a0f0 | 8086:0070 | Intel      | Wi-Fi 6 AX201                | 2     | iwlwifi    | ABC31CEA35 |
| 8086:a0f0 | 8086:0074 | Intel      | Wi-Fi 6 AX201                | 2     | iwlwifi    | 93033ED87E |
| 10ec:8171 | 10ec:8171 | Realtek... | RTL8191SEvA Wireless LAN ... | 1     | rtl8192se  | BE63E554C5 |
| 10ec:8178 | 10ec:8191 | Realtek... | RTL8192CE PCIe Wireless N... | 1     | rtl8192ce  | 9314D29F45 |
| 10ec:8179 | 10ec:0189 | Realtek... | RTL8188EE Wireless Networ... | 1     | rtl8188ee  | AD04BFF06F |
| 10ec:8179 | 10ec:8179 | Realtek... | RTL8188EE Wireless Networ... | 1     | rtl8188ee  | B31E28E55F |
| 10ec:8179 | 1a3b:219a | Realtek... | RTL8188EE Wireless Networ... | 1     | rtl8188ee  | F6DDC974E1 |
| 10ec:8723 | 10ec:0733 | Realtek... | RTL8723AE PCIe Wireless N... | 1     |            | 2F246CACD8 |
| 10ec:8723 | 1a3b:2114 | Realtek... | RTL8723AE PCIe Wireless N... | 1     | rtl8723ae  | E6FEB379A4 |
| 10ec:b723 | 103c:2231 | Realtek... | RTL8723BE PCIe Wireless N... | 1     | rtl8723be  | 268CC95CAD |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 1     |            | 4FBA2D817D |
| 10ec:c821 | 10ec:c821 | Realtek... | RTL8821CE 802.11ac PCIe W... | 1     |            | F71EFE50CF |
| 14e4:4312 | 1028:0007 | Broadco... | BCM4311 802.11a/b/g          | 1     | wl         | 5DB1994CAD |
| 14e4:4357 | 14e4:04da | Broadco... | BCM43225 802.11b/g/n         | 1     | wl         | D8DB035524 |
| 14e4:4359 | 103c:182c | Broadcom   | BCM43228 802.11a/b/g/n       | 1     | bcma       | 7265640CDC |
| 14e4:4359 | 103c:8088 | Broadco... | BCM43228 802.11a/b/g/n       | 1     | wl         | 9C630C8D83 |
| 14e4:4365 | 11ad:6655 | Broadcom   | BCM43142 802.11b/g/n         | 1     |            | 6C2688EBFC |
| 168c:0036 | 1028:020c | Qualcom... | QCA9565 / AR9565 Wireless... | 1     | ath9k      | 982F591B41 |
| 168c:0036 | 11ad:0642 | Qualcom... | QCA9565 / AR9565 Wireless... | 1     | ath9k      | A27BE7CA62 |
| 1814:0781 | 1a3b:1059 | Ralink     | RT2790 Wireless 802.11n 1... | 1     | rt2800pci  | 037A3E45C7 |
| 8086:06f0 | 8086:0070 | Intel      | Comet Lake PCH CNVi WiFi     | 1     | iwlwifi    | 3E09AE8DEE |
| 8086:06f0 | 8086:0074 | Intel      | Comet Lake PCH CNVi WiFi     | 1     | iwlwifi    | 334ABF8C53 |
| 8086:06f0 | 8086:02a4 | Intel      | Comet Lake PCH CNVi WiFi     | 1     | iwlwifi    | 7146ACBC96 |
| 8086:0887 | 8086:4062 | Intel      | Centrino Wireless-N 2230     | 1     | iwlwifi    | 4A3ACD7700 |
| 8086:08b1 | 8086:4070 | Intel      | Wireless 7260                | 1     | iwlwifi    | FF3CE414E4 |
| 8086:08b1 | 8086:4462 | Intel      | Wireless 7260                | 1     | iwlwifi    | 6F729D176B |
| 8086:08b1 | 8086:c070 | Intel      | Wireless 7260                | 1     | iwlwifi    | AF5060B68B |
| 8086:08b2 | 8086:4262 | Intel      | Wireless 7260                | 1     | iwlwifi    | 4C0B50F040 |
| 8086:24f3 | 8086:0130 | Intel      | Wireless 8260                | 1     | iwlwifi    | EDB53070CD |
| 8086:2723 | 8086:0080 | Intel      | Wi-Fi 6 AX200                | 1     | iwlwifi    | D4583B58FE |
| 8086:2723 | 8086:0088 | Intel      | Wi-Fi 6 AX200                | 1     | iwlwifi    | AECEFCDF3A |
| 8086:422c | 8086:1301 | Intel      | Centrino Advanced-N 6200     | 1     | iwlwifi    | 494DE74E34 |
| 8086:4232 | 8086:1201 | Intel      | WiFi Link 5100               | 1     | iwlwifi    | 9BE096319C |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:157b | 8086:0000 | Intel      | I210 Gigabit Network Conn... | 28    | igb        | D186AF4EE3 |
| 8086:1539 | 8086:0000 | Intel      | I211 Gigabit Network Conn... | 15    | igb        | 9B370AB285 |
| 8086:1533 | ffff:0000 | Intel      | I210 Gigabit Network Conn... | 11    | igb        | 592FA60C7D |
| 8086:1539 | 8086:2080 | Intel      | I211 Gigabit Network Conn... | 2     | igb        | 745C35E31C |
| 8086:1093 | 8086:0001 | Intel      | PRO/100 VM Network Connec... | 1     | e100       | 10DB69DD6C |
| 8086:10fe | 17aa:3605 | Intel      | 82552 10/100 Network Conn... | 1     | e100       | F077B2F98E |
| 8086:1502 | 8086:0000 | Intel      | 82579LM Gigabit Network C... | 1     | e1000e     | 2F246CACD8 |
| 8086:1503 | 1734:11d9 | Intel      | 82579V Gigabit Network Co... | 1     | e1000e     | FC67594808 |
| 8086:1521 | 15d9:0652 | Intel      | I350 Gigabit Network Conn... | 1     | igb        | 8658CA67D7 |
| 8086:1533 | 15bd:100a | Intel      | I210 Gigabit Network Conn... | 1     | igb        | 593A489E8D |
| 8086:1533 | 1ab6:0214 | Intel      | I210 Gigabit Network Conn... | 1     | igb        | E311FB0391 |
| 8086:1539 | 1297:4033 | Intel      | I211 Gigabit Network Conn... | 1     | igb        | B31E28E55F |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a126 |           | Intel      | 100 Series/C230 Series Ch... | 1     | intel_t... | C263278BF1 |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 106b:1801 | 106b:1801 | Apple      | T2 Bridge Controller         | 7     |            | D09823163E |
| 106b:1802 | 106b:1802 | Apple      | T2 Secure Enclave Processor  | 7     |            | D09823163E |
| 1022:15e6 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Non-S... | 2     | i2c_amd... | A203CD8C57 |
| 8086:a135 | 15d9:0898 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_i... | 8658CA67D7 |

### Performance counters (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27a3 |           | Intel      | 945GM/GU Chipset Hardware... | 14    |            | C480910C6C |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:16bc | 14e4:0000 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 90    | sdhci_pci  | 066B825941 |
| 17a0:9755 | 8086:2081 | Genesys... | GL9755 SD Host Controller    | 53    | sdhci_pci  | 92AA2017B9 |
| 1217:8621 | 8086:2073 | O2 Micro   | SD/MMC Card Reader Contro... | 31    | sdhci_pci  | D186AF4EE3 |
| 8086:31cc | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 31    | sdhci_pci  | 6872FA0523 |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 31    | sdhci_pci  | B2CC37B9AC |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 24    | sdhci_pci  | B2CC37B9AC |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 22    | sdhci_pci  | B2CC37B9AC |
| 1217:8621 | 8086:2064 | O2 Micro   | SD/MMC Card Reader Contro... | 19    | sdhci_pci  | D148D77A8C |
| 8086:2296 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 18    | sdhci_pci  | F084020240 |
| 8086:9d2d | 8086:2063 | Intel      | Sunrise Point-LP Secure D... | 11    | sdhci_pci  | 8747496A6B |
| 8086:5ad0 |           | Intel      | Celeron N3350/Pentium N42... | 9     | sdhci_pci  | 161E6B136E |
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 6     | sdhci_pci  | 2048DCBA92 |
| 8086:31d0 | 8086:7270 | Intel      | SD Host Controller           | 6     | sdhci_pci  | 2048DCBA92 |
| 8086:5acc | 19da:b325 | Intel      | Celeron N3350/Pentium N42... | 6     | sdhci_pci  | 23BDDBF63A |
| 8086:0f16 | 8086:0f16 | Intel      | Atom Processor Z36xxx/Z37... | 4     | sdhci_pci  | ED960141AA |
| 8086:0f50 |           | Intel      | Atom Processor E3800 Seri... | 4     | sdhci_pci  | DD7BEAC148 |
| 8086:0f16 | 19da:b219 | Intel      | Atom Processor Z36xxx/Z37... | 3     | sdhci_pci  | 494AE0914E |
| 8086:2294 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 3     | sdhci_pci  | FDE91E565C |
| 8086:2294 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 3     | sdhci_pci  | 0D05B404DD |
| 8086:5acc | 8086:5acc | Intel      | Celeron N3350/Pentium N42... | 3     | sdhci_pci  | 161E6B136E |
| 1022:7806 | 19da:a261 | AMD        | FCH SD Flash Controller      | 2     | sdhci_pci  | 8C3CA64606 |
| 8086:2294 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 2     | sdhci_pci  | C7D9257057 |
| 8086:2294 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 2     | sdhci_pci  | CABBA2C402 |
| 8086:2296 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 2     | sdhci_pci  | D3F96F55F3 |
| 8086:31cc | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 2     | sdhci_pci  | E46F325CBA |
| 8086:5aca | 8086:5aca | Intel      | Celeron N3350/Pentium N42... | 2     | sdhci_pci  | 161E6B136E |
| 8086:5acc | 8086:2080 | Intel      | Celeron N3350/Pentium N42... | 2     | sdhci_pci  | 745C35E31C |
| 8086:9d2b | 1043:8694 | Intel      | Skylake-U/Y SCC: eMMC        | 2     | sdhci_pci  | 847A813A2C |
| 1022:7806 | 19da:b218 | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | EB76FF1C3F |
| 1217:8520 | 1217:0002 | O2 Micro   | SD/MMC Card Reader Contro... | 1     |            | D125ABF69E |
| 8086:02c4 | 8086:7270 | Intel      | Comet Lake PCH-LP SCS1: eMMC | 1     | sdhci_pci  | 64FFE9BE15 |
| 8086:0f15 | 19da:b219 | Intel      | Atom Processor Z36xxx/Z37... | 1     | sdhci_pci  | 4BC48CCC62 |
| 8086:2295 | 1028:07c1 | Intel      | Atom/Celeron/Pentium Proc... | 1     | sdhci_pci  | 9F4F497293 |
| 8086:31cc | 8086:31cc | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | 5250CD21EF |
| 8086:5aca | 19da:b342 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 9A0C888104 |
| 8086:5acc | 19da:b342 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 9A0C888104 |
| 8086:5acc | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | EF4CBE2D05 |
| 8086:9dc4 | 8086:2075 | Intel      | 300 Series Chipset SD Hos... | 1     | sdhci_pci  | 6FD8E8E647 |
| 8086:9df5 | 8086:2075 | Intel      | BayHubTech Integrated SD ... | 1     | sdhci_pci  | 6FD8E8E647 |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9da4 | 8086:2074 | Intel      | Cannon Point-LP SPI Contr... | 116   |            | 7CA350189C |
| 8086:02a4 | 8086:2081 | Intel      | Comet Lake SPI (flash) Co... | 54    | intel_s... | 92AA2017B9 |
| 8086:02e8 | 8086:2081 | Intel      | Serial IO I2C Host Contro... | 54    | intel_l... | 92AA2017B9 |
| 8086:02ea | 8086:2081 | Intel      | Comet Lake PCH-LP LPSS: I... | 54    | intel_l... | 92AA2017B9 |
| 8086:5ac8 |           | Intel      | Celeron N3350/Pentium N42... | 23    | pwm_lps... | B9F5CB4E7C |
| 8086:22c6 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 18    | i2c_des... | F084020240 |
| 8086:22c7 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 18    | i2c_des... | F084020240 |
| 8086:a324 | 17aa:312d | Intel      | Cannon Lake PCH SPI Contr... | 12    |            | D66B009299 |
| 8086:5ac8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 7     | pwm_lpss   | 407F49A57D |
| 8086:a324 | 17aa:3135 | Intel      | Cannon Lake PCH SPI Contr... | 7     |            | B16B2D9BD5 |
| 8086:a324 | 8086:7270 | Intel      | Cannon Lake PCH SPI Contr... | 7     | intel_s... | D09823163E |
| 8086:9da4 | 17aa:314d | Intel      | Cannon Point-LP SPI Contr... | 5     |            | 032DB5DB0F |
| 8086:a324 | 17aa:3136 | Intel      | Cannon Lake PCH SPI Contr... | 5     |            | 6F39F78FAC |
| 8086:02a4 | 1043:87bd | Intel      | Comet Lake SPI (flash) Co... | 3     | intel_s... | 1C1741820B |
| 8086:02e8 | 1043:87bd | Intel      | Serial IO I2C Host Contro... | 3     | intel_l... | 1C1741820B |
| 8086:02e9 | 1043:87bd | Intel      | Comet Lake Serial IO I2C ... | 3     | intel_l... | 1C1741820B |
| 8086:06a4 | 103c:8710 | Intel      | Comet Lake PCH SPI Contro... | 2     |            | B2A212246B |
| 8086:9da4 | 1043:8790 | Intel      | Cannon Point-LP SPI Contr... | 2     |            | 45389EF622 |
| 8086:9da4 | 17aa:314c | Intel      | Cannon Point-LP SPI Contr... | 2     |            | 0F66B49A44 |
| 8086:9da4 | 8086:2079 | Intel      | Cannon Point-LP SPI Contr... | 2     |            | 45B14891D4 |
| 8086:9dc5 | 8086:2079 | Intel      | Cannon Point-LP Serial IO... | 2     | intel_lpss | 45B14891D4 |
| 8086:9de8 | 8086:2079 | Intel      | Cannon Point-LP Serial IO... | 2     | intel_lpss | 45B14891D4 |
| 8086:9de9 | 8086:2079 | Intel      | Cannon Point-LP Serial IO... | 2     | intel_lpss | 45B14891D4 |
| 8086:a0a4 | 8086:3004 | Intel      | Tiger Lake-LP SPI Controller | 2     | intel_spi  | 93033ED87E |
| 8086:a0e8 | 8086:3004 | Intel      | Tiger Lake-LP Serial IO I... | 2     | intel_lpss | 93033ED87E |
| 8086:a324 | 103c:8458 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 87E6E38B4A |
| 8086:a324 | 19da:b411 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | CF60BF6309 |
| 8086:a324 | 8086:2089 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 592FA60C7D |
| 8086:a368 | 19da:b411 | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | CF60BF6309 |
| 8086:a368 | 8086:2089 | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_lpss | 592FA60C7D |
| 8086:a369 | 19da:b411 | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | CF60BF6309 |
| 8086:a369 | 8086:2089 | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_lpss | 592FA60C7D |
| 10de:1ad9 | 1458:3ff9 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     | i2c_nvi... | 9A5A163CB3 |
| 10de:1ad9 | 3842:2068 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     | i2c_nvi... | 0B21150424 |
| 10de:1adb | 19da:1529 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     | i2c_nvi... | DDCFB58F4C |
| 10de:1adb | 19da:2529 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     | i2c_nvi... | CF60BF6309 |
| 8086:02a4 | 8086:7270 | Intel      | Comet Lake SPI (flash) Co... | 1     | intel_s... | 64FFE9BE15 |
| 8086:02e8 | 8086:7270 | Intel      | Serial IO I2C Host Contro... | 1     | intel_l... | 64FFE9BE15 |
| 8086:06a4 | 103c:871a | Intel      | Comet Lake PCH SPI Contro... | 1     |            | F74885CE0C |
| 8086:06a4 | 103c:8755 | Intel      | Comet Lake PCH SPI Contro... | 1     |            | 334ABF8C53 |
| 8086:06a4 | 17aa:316e | Intel      | Comet Lake PCH SPI Contro... | 1     | intel_s... | 7146ACBC96 |
| 8086:06a4 | 17aa:3172 | Intel      | Comet Lake PCH SPI Contro... | 1     |            | 3E09AE8DEE |
| 8086:0f08 | 8086:0f08 | Intel      | Atom Processor Z36xxx/Z37... | 1     | pwm_lps... | A968EF1DD8 |
| 8086:0f09 | 8086:0f09 | Intel      | Atom Processor Z36xxx/Z37... | 1     | pwm_lps... | A968EF1DD8 |
| 8086:9da4 | 17aa:3144 | Intel      | Cannon Point-LP SPI Contr... | 1     |            | E64B1B05A0 |
| 8086:9da4 | 8086:2075 | Intel      | Cannon Point-LP SPI Contr... | 1     |            | 6FD8E8E647 |
| 8086:9dc5 | 17aa:3144 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | E64B1B05A0 |
| 8086:9dc5 | 8086:2075 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | 6FD8E8E647 |
| 8086:9de8 | 17aa:3144 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | E64B1B05A0 |
| 8086:9de8 | 17aa:314d | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | F2BD66E51A |
| 8086:9de8 | 8086:2075 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | 6FD8E8E647 |
| 8086:9de9 | 17aa:3144 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | E64B1B05A0 |
| 8086:9de9 | 8086:2075 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | 6FD8E8E647 |
| 8086:a0a4 | 8086:3003 | Intel      | Tiger Lake-LP SPI Controller | 1     |            | ABC31CEA35 |
| 8086:a0a4 | 8086:3013 | Intel      | Tiger Lake-LP SPI Controller | 1     |            | 66A02F462F |
| 8086:a0e8 | 8086:3003 | Intel      | Tiger Lake-LP Serial IO I... | 1     | intel_l... | ABC31CEA35 |
| 8086:a0e8 | 8086:3013 | Intel      | Tiger Lake-LP Serial IO I... | 1     | intel_lpss | 66A02F462F |
| 8086:a0e9 | 8086:3003 | Intel      | Tiger Lake-LP Serial IO I... | 1     | intel_l... | ABC31CEA35 |
| 8086:a0e9 | 8086:3013 | Intel      | Tiger Lake-LP Serial IO I... | 1     | intel_lpss | 66A02F462F |
| 8086:a324 | 103c:8457 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | C15E7F2A47 |
| 8086:a324 | 8086:2088 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | AECEFCDF3A |
| 8086:a368 | 8086:2088 | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | AECEFCDF3A |
| 8086:a369 | 8086:2088 | Intel      | Cannon Lake PCH Serial IO... | 1     | intel_l... | AECEFCDF3A |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d3d | 8086:2070 | Intel      | Sunrise Point-LP Active M... | 11    | serial     | FA31D6F45C |
| 10ec:816a | 1043:85b5 | Realtek... | RTL8111xP UART #1            | 10    | serial     | 79EEA28A8B |
| 10ec:816b | 1043:85b5 | Realtek... | RTL8111xP UART #2            | 10    | serial     | 79EEA28A8B |
| 10ec:816a | 17aa:3130 | Realtek... | RTL8111xP UART #1            | 7     | serial     | DBFBDEA28F |
| 10ec:816b | 17aa:3130 | Realtek... | RTL8111xP UART #2            | 7     | serial     | DBFBDEA28F |
| 8086:a363 | 17aa:3135 | Intel      | Cannon Lake PCH Active Ma... | 6     | serial     | B16B2D9BD5 |
| 8086:a363 | 17aa:3136 | Intel      | Cannon Lake PCH Active Ma... | 5     | serial     | 6F39F78FAC |
| 10ec:816a | 10ec:8168 | Realtek... | RTL8111xP UART #1            | 4     | serial     | 924D89CD42 |
| 10ec:816a | 17aa:3151 | Realtek... | RTL8111xP UART #1            | 4     | serial     | E57DFE6F39 |
| 10ec:816b | 17aa:3151 | Realtek... | RTL8111xP UART #2            | 4     | serial     | E57DFE6F39 |
| 8086:a13d | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 3     | serial     | 44430304D3 |
| 8086:a2bd | 103c:829a | Intel      | 200 Series Chipset Family... | 3     | serial     | C326081D7D |
| 8086:06e3 | 103c:8710 | Intel      | Comet Lake Keyboard and T... | 2     | serial     | B2A212246B |
| 8086:8c3d | 103c:2145 | Intel      | 8 Series/C220 Series Chip... | 2     | serial     | 9C26D1B3DD |
| 8086:9de3 | 17aa:314c | Intel      | Cannon Point-LP Keyboard ... | 2     | serial     | 0F66B49A44 |
| 10ec:816a | 103c:8523 | Realtek... | RTL8111xP UART #1            | 1     |            | BAB721D52E |
| 10ec:816a | 17aa:30fd | Realtek... | RTL8111xP UART #1            | 1     | serial     | 5F6F9A1C6C |
| 10ec:816a | 17aa:3181 | Realtek... | RTL8111xP UART #1            | 1     | serial     | A203CD8C57 |
| 10ec:816b | 103c:8523 | Realtek... | RTL8111xP UART #2            | 1     |            | BAB721D52E |
| 10ec:816b | 10ec:8168 | Realtek... | RTL8111xP UART #2            | 1     |            | 5DD127A865 |
| 10ec:816b | 17aa:30fd | Realtek... | RTL8111xP UART #2            | 1     | serial     | 5F6F9A1C6C |
| 8086:06e3 | 103c:871a | Intel      | Comet Lake Keyboard and T... | 1     | serial     | F74885CE0C |
| 8086:06e3 | 17aa:3172 | Intel      | Comet Lake Keyboard and T... | 1     | serial     | 3E09AE8DEE |
| 8086:9cbd | 8086:2058 | Intel      | Wildcat Point-LP KT Contr... | 1     | serial     | 4AB80B03C5 |
| 8086:a0e3 | 8086:3003 | Intel      | Tiger Lake-LP Active Mana... | 1     | serial     | ABC31CEA35 |
| 8086:a0e3 | 8086:3013 | Intel      | Tiger Lake-LP Active Mana... | 1     | serial     | 66A02F462F |
| 8086:a13d | 1019:9bc6 | Intel      | 100 Series/C230 Series Ch... | 1     | serial     | 7101BAED7A |
| 8086:a2bd | 17aa:310c | Intel      | 200 Series Chipset Family... | 1     | serial     | 60877665B6 |
| 8086:a363 | 8086:2088 | Intel      | Cannon Lake PCH Active Ma... | 1     | serial     | AECEFCDF3A |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9df9 | 8086:2074 | Intel      | Cannon Point-LP Thermal C... | 116   | intel_p... | 7CA350189C |
| 8086:9d31 | 8086:2068 | Intel      | Sunrise Point-LP Thermal ... | 58    | intel_p... | 38D5C55BD7 |
| 8086:02f9 | 8086:2081 | Intel      | Comet Lake Thermal Subsytem  | 54    | intel_p... | 92AA2017B9 |
| 8086:5abc |           | Intel      | Celeron N3350/Pentium N42... | 32    | intel_l... | B9F5CB4E7C |
| 8086:5ac4 |           | Intel      | Celeron N3350/Pentium N42... | 32    | intel_l... | B9F5CB4E7C |
| 8086:5ac6 |           | Intel      | Celeron N3350/Pentium N42... | 32    | intel_l... | B9F5CB4E7C |
| 8086:a127 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 31    | intel_l... | D186AF4EE3 |
| 8086:a131 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 31    | intel_p... | D186AF4EE3 |
| 8086:a160 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 31    | intel_l... | D186AF4EE3 |
| 8086:a161 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 31    | intel_l... | D186AF4EE3 |
| 8086:a162 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 31    | intel_l... | D186AF4EE3 |
| 8086:5aac | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 29    | intel_l... | B9F5CB4E7C |
| 8086:5ac2 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 29    | intel_l... | B9F5CB4E7C |
| 8086:5a8c |           | Intel      | Atom/Celeron/Pentium Dyna... | 25    | process... | B2CC37B9AC |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 23    | intel_l... | B2CC37B9AC |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 23    | intel_l... | B2CC37B9AC |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 23    | intel_l... | B2CC37B9AC |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 23    | intel_l... | B2CC37B9AC |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 22    | intel_l... | B2CC37B9AC |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 22    | intel_l... | B2CC37B9AC |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 22    | intel_l... | B2CC37B9AC |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 22    | intel_l... | B2CC37B9AC |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 22    | intel_l... | B2CC37B9AC |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 22    | intel_l... | B2CC37B9AC |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 22    | intel_l... | B2CC37B9AC |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 22    | intel_l... | B2CC37B9AC |
| 8086:a131 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 21    | intel_p... | D148D77A8C |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 18    | intel_l... | B2CC37B9AC |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 17    | intel_l... | B2CC37B9AC |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 17    | intel_l... | B2CC37B9AC |
| 8086:9d31 | 8086:2070 | Intel      | Sunrise Point-LP Thermal ... | 14    | intel_p... | FA31D6F45C |
| 8086:9d60 | 8086:2070 | Intel      | Sunrise Point-LP Serial I... | 14    | intel_l... | FA31D6F45C |
| 8086:9d61 | 8086:2070 | Intel      | Sunrise Point-LP Serial I... | 14    | intel_l... | FA31D6F45C |
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 13    | process... | EE3840CD1D |
| 8086:9d27 | 8086:2063 | Intel      | Sunrise Point-LP Serial I... | 12    | intel_l... | 8747496A6B |
| 8086:9d31 | 8086:2063 | Intel      | Sunrise Point-LP Thermal ... | 12    | intel_p... | 8747496A6B |
| 1022:15e4 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Senso... | 11    | amd_mp2... | 79EEA28A8B |
| 8086:318c | 1043:875e | Intel      | Celeron/Pentium Silver Pr... | 10    | process... | 9D5F2807CE |
| 8086:a379 | 8086:7270 | Intel      | Cannon Lake PCH Thermal C... | 7     | intel_p... | D09823163E |
| 8086:9d31 | 8086:7270 | Intel      | Sunrise Point-LP Thermal ... | 6     | intel_p... | D391C49614 |
| 8086:1903 | 17aa:314d | Intel      | Xeon E3-1200 v5/E3-1500 v... | 5     | process... | 032DB5DB0F |
| 8086:31ac | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | 2048DCBA92 |
| 8086:31ae | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | 2048DCBA92 |
| 8086:31b0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | 2048DCBA92 |
| 8086:31b2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | 2048DCBA92 |
| 8086:31b4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | 2048DCBA92 |
| 8086:31b6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | 2048DCBA92 |
| 8086:31b8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | 2048DCBA92 |
| 8086:31ba | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | 2048DCBA92 |
| 8086:31c2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | 2048DCBA92 |
| 8086:31c4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | 2048DCBA92 |
| 8086:31c6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | 2048DCBA92 |
| 8086:9df9 | 17aa:314d | Intel      | Cannon Point-LP Thermal C... | 5     | intel_p... | 032DB5DB0F |
| 8086:a131 | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 5     | intel_p... | A080CA6AD4 |
| 8086:a2b1 | 103c:82a5 | Intel      | 200 Series PCH Thermal Su... | 4     |            | 08B98B6A88 |
| 8086:02f9 | 1043:87bd | Intel      | Comet Lake Thermal Subsytem  | 3     | intel_p... | 1C1741820B |
| 8086:318c | 8086:318c | Intel      | Celeron/Pentium Silver Pr... | 3     | process... | 5250CD21EF |
| 8086:318c | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | proc_th... | 8160A14928 |
| 8086:31bc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_lpss | 2048DCBA92 |
| 8086:31be | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_lpss | 2048DCBA92 |
| 8086:31c0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_lpss | 2048DCBA92 |
| 8086:31ee | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_lpss | 2048DCBA92 |
| 8086:5aac | 8086:5aac | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 161E6B136E |
| 8086:5aae | 8086:5aae | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 161E6B136E |
| 8086:5ab0 | 8086:5ab0 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 161E6B136E |
| 8086:5abe | 8086:5abe | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 161E6B136E |
| 8086:5ac0 | 8086:5ac0 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 161E6B136E |
| 8086:5ac2 | 8086:5ac2 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 161E6B136E |
| 8086:5aee |           | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 161E6B136E |
| 8086:a131 | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 3     | intel_p... | 44430304D3 |
| 8086:a2b1 | 103c:829a | Intel      | 200 Series PCH Thermal Su... | 3     |            | C326081D7D |
| 8086:06f9 | 103c:8710 | Intel      | Comet Lake PCH Thermal Co... | 2     |            | B2A212246B |
| 8086:1903 | 17aa:314c | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | process... | 0F66B49A44 |
| 8086:22dc |           | Intel      | Atom/Celeron/Pentium Proc... | 2     | proc_th... | 3AB4853FDD |
| 8086:31b4 | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_l... | E46F325CBA |
| 8086:31ba | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_l... | E46F325CBA |
| 8086:5a8c | 8086:5a8c | Intel      | Atom/Celeron/Pentium Dyna... | 2     | process... | 161E6B136E |
| 8086:5ab2 | 8086:5ab2 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 161E6B136E |
| 8086:5ab4 | 8086:5ab4 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 161E6B136E |
| 8086:5ab6 | 8086:5ab6 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 161E6B136E |
| 8086:5ab8 | 8086:5ab8 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 161E6B136E |
| 8086:5aba | 8086:5aba | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 161E6B136E |
| 8086:9d27 | 1043:8694 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_lpss | 847A813A2C |
| 8086:9df9 | 1043:8790 | Intel      | Cannon Point-LP Thermal C... | 2     | intel_p... | 45389EF622 |
| 8086:9df9 | 17aa:314c | Intel      | Cannon Point-LP Thermal C... | 2     | intel_p... | 0F66B49A44 |
| 8086:9df9 | 8086:2079 | Intel      | Cannon Point-LP Thermal C... | 2     | intel_p... | 45B14891D4 |
| 8086:a131 | 1019:9bc6 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_p... | 7101BAED7A |
| 8086:a131 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_p... | D8B8CA1E48 |
| 8086:a379 | 103c:8458 | Intel      | Cannon Lake PCH Thermal C... | 2     | intel_p... | 87E6E38B4A |
| 8086:a379 | 19da:b411 | Intel      | Cannon Lake PCH Thermal C... | 2     | intel_p... | CF60BF6309 |
| 8086:a379 | 8086:2089 | Intel      | Cannon Lake PCH Thermal C... | 2     | intel_p... | 592FA60C7D |
| 8086:02f9 | 8086:7270 | Intel      | Comet Lake Thermal Subsytem  | 1     | intel_p... | 64FFE9BE15 |
| 8086:06f9 | 103c:871a | Intel      | Comet Lake PCH Thermal Co... | 1     | intel_p... | F74885CE0C |
| 8086:06f9 | 103c:8755 | Intel      | Comet Lake PCH Thermal Co... | 1     |            | 334ABF8C53 |
| 8086:06f9 | 17aa:316e | Intel      | Comet Lake PCH Thermal Co... | 1     | intel_p... | 7146ACBC96 |
| 8086:06f9 | 17aa:3172 | Intel      | Comet Lake PCH Thermal Co... | 1     | intel_p... | 3E09AE8DEE |
| 8086:1903 | 103c:8755 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     |            | 334ABF8C53 |
| 8086:1903 | 17aa:316e | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | process... | 7146ACBC96 |
| 8086:1903 | 17aa:3172 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | process... | 3E09AE8DEE |
| 8086:1e24 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 1     |            | 2F246CACD8 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9da3 | 8086:2074 | Intel      | Cannon Point-LP SMBus Con... | 116   | i2c_i801   | 7CA350189C |
| 8086:9d23 | 8086:2068 | Intel      | Sunrise Point-LP SMBus       | 58    | i2c_i801   | 38D5C55BD7 |
| 8086:02a3 | 8086:2081 | Intel      | Comet Lake PCH-LP SMBus H... | 54    | i2c_i801   | 92AA2017B9 |
| 8086:0f12 | 8086:0f12 | Intel      | Atom Processor E3800 Seri... | 36    | i2c_i801   | DD7BEAC148 |
| 8086:1e22 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 36    | i2c_i801   | 066B825941 |
| 8086:9ca2 | 8086:2057 | Intel      | Wildcat Point-LP SMBus Co... | 36    | i2c_i801   | 7E0F62D2FD |
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 34    | i2c_i801   | B2CC37B9AC |
| 8086:2292 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 32    | i2c_i801   | 9E568EF477 |
| 8086:31d4 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 31    | i2c_i801   | 6872FA0523 |
| 8086:a123 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 31    | i2c_i801   | D186AF4EE3 |
| 8086:5ad4 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 29    | i2c_i801   | B9F5CB4E7C |
| 8086:1c22 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 26    | i2c_i801   | 7EBB0672C0 |
| 8086:a123 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 21    | i2c_i801   | D148D77A8C |
| 8086:9c22 | 8086:7270 | Intel      | 8 Series SMBus Controller    | 18    | i2c_i801   | 42B0868834 |
| 10de:0aa2 | 10de:cb79 | Nvidia     | MCP79 SMBus                  | 15    | i2c_nfo... | F8B00A2F85 |
| 8086:27da | 8086:7270 | Intel      | NM10/ICH7 Family SMBus Co... | 15    | i2c_i801   | C480910C6C |
| 8086:9d23 | 8086:2070 | Intel      | Sunrise Point-LP SMBus       | 14    | i2c_i801   | FA31D6F45C |
| 8086:9d23 | 8086:2063 | Intel      | Sunrise Point-LP SMBus       | 12    | i2c_i801   | 8747496A6B |
| 8086:a323 | 17aa:312d | Intel      | Cannon Lake PCH SMBus Con... | 12    | i2c_i801   | D66B009299 |
| 1002:4385 | 103c:17e2 | AMD        | SBx00 SMBus Controller       | 11    | i2c_piix4  | BF35F8C621 |
| 1022:790b | 1043:87e7 | AMD        | FCH SMBus Controller         | 11    | i2c_piix4  | 79EEA28A8B |
| 10de:0d79 | 10de:cb89 | Nvidia     | MCP89 SMBus                  | 11    |            | 9ADEB0BD4E |
| 8086:2292 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 11    | i2c_i801   | CABBA2C402 |
| 8086:31d4 | 1043:875e | Intel      | Celeron/Pentium Silver Pr... | 10    | i2c_i801   | 9D5F2807CE |
| 8086:0f12 | 17aa:368d | Intel      | Atom Processor E3800 Seri... | 9     | i2c_i801   | CA54ECE919 |
| 1022:790b | 17aa:3130 | AMD        | FCH SMBus Controller         | 7     | i2c_pii... | DBFBDEA28F |
| 8086:31d4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 7     | i2c_i801   | 2048DCBA92 |
| 8086:a323 | 17aa:3135 | Intel      | Cannon Lake PCH SMBus Con... | 7     | i2c_i801   | B16B2D9BD5 |
| 8086:a323 | 8086:7270 | Intel      | Cannon Lake PCH SMBus Con... | 7     | i2c_i801   | D09823163E |
| 8086:0f12 | 17aa:30b5 | Intel      | Atom Processor E3800 Seri... | 6     | i2c_i801   | 538597F50A |
| 8086:5ad4 | 19da:b325 | Intel      | Celeron N3350/Pentium N42... | 6     | i2c_i801   | 23BDDBF63A |
| 8086:9d23 | 8086:7270 | Intel      | Sunrise Point-LP SMBus       | 6     | i2c_i801   | D391C49614 |
| 1022:790b | 103c:8158 | AMD        | FCH SMBus Controller         | 5     | i2c_pii... | 95BC62EF3F |
| 8086:0f12 |           | Intel      | Atom Processor E3800 Seri... | 5     | i2c_i801   | A27BE7CA62 |
| 8086:9ca2 | 8086:7270 | Intel      | Wildcat Point-LP SMBus Co... | 5     | i2c_i801   | 859A8D53F5 |
| 8086:9da3 | 17aa:314d | Intel      | Cannon Point-LP SMBus Con... | 5     | i2c_i801   | 032DB5DB0F |
| 8086:a123 | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 5     | i801_smbus | A080CA6AD4 |
| 8086:a323 | 17aa:3136 | Intel      | Cannon Lake PCH SMBus Con... | 5     | i2c_i801   | 6F39F78FAC |
| 1022:790b | 17aa:312f | AMD        | FCH SMBus Controller         | 4     | i2c_pii... | 5205C41BC5 |
| 1022:790b | 17aa:3151 | AMD        | FCH SMBus Controller         | 4     | i2c_piix4  | E57DFE6F39 |
| 8086:0f12 | 19da:b219 | Intel      | Atom Processor E3800 Seri... | 4     | i2c_i801   | 494AE0914E |
| 8086:1e22 | 19da:b211 | Intel      | 7 Series/C216 Chipset Fam... | 4     | i2c_i801   | EFBBD0C3F8 |
| 8086:2292 | 17aa:30dd | Intel      | Atom/Celeron/Pentium Proc... | 4     | i2c_i801   | 0513ACEC04 |
| 8086:2292 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 4     | i2c_i801   | 0D05B404DD |
| 8086:8c22 | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 4     | i2c_i801   | FCAA602427 |
| 8086:9ca2 | 8086:2058 | Intel      | Wildcat Point-LP SMBus Co... | 4     | i2c_i801   | 6E19619F29 |
| 8086:a2a3 | 103c:82a5 | Intel      | 200 Series/Z370 Chipset F... | 4     | i2c_i801   | 08B98B6A88 |
| 1002:4385 | 19da:a191 | AMD        | SBx00 SMBus Controller       | 3     | i2c_piix4  | 121F403E29 |
| 1022:790b | 103c:8267 | AMD        | FCH SMBus Controller         | 3     | i2c_piix4  | 3AA09CF72A |
| 1022:790b | 103c:872e | AMD        | FCH SMBus Controller         | 3     | i2c_pii... | 7791A24770 |
| 1022:790b | 103c:8836 | AMD        | FCH SMBus Controller         | 3     | i2c_piix4  | DDEEE57DBD |
| 8086:02a3 | 1043:87bd | Intel      | Comet Lake PCH-LP SMBus H... | 3     | i2c_i801   | 1C1741820B |
| 8086:0f12 | 8086:7270 | Intel      | Atom Processor E3800 Seri... | 3     | i2c_i801   | EED35A825A |
| 8086:2292 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 3     | i2c_i801   | FDE91E565C |
| 8086:2292 | 17aa:3637 | Intel      | Atom/Celeron/Pentium Proc... | 3     | i2c_i801   | 442724EA6A |
| 8086:2292 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 3     | i2c_i801   | 7F47BED9CF |
| 8086:27da | 19da:a218 | Intel      | NM10/ICH7 Family SMBus Co... | 3     | i2c_i801   | 49EF2577E1 |
| 8086:5ad4 | 8086:5ad4 | Intel      | Celeron N3350/Pentium N42... | 3     | i2c_i801   | 161E6B136E |
| 8086:a123 | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 3     | i2c_i801   | 44430304D3 |
| 8086:a2a3 | 103c:829a | Intel      | 200 Series/Z370 Chipset F... | 3     | i2c_i801   | C326081D7D |
| 1022:780b | 19da:a261 | AMD        | FCH SMBus Controller         | 2     | piix4_s... | 8C3CA64606 |
| 8086:06a3 | 103c:8710 | Intel      | Comet Lake PCH SMBus Cont... | 2     |            | B2A212246B |
| 8086:0f12 | 1071:0730 | Intel      | Atom Processor E3800 Seri... | 2     | i2c_i801   | BE63E554C5 |
| 8086:1c22 | 19da:b202 | Intel      | 6 Series/C200 Series Chip... | 2     | i2c_i801   | 4D23C29B62 |
| 8086:1e22 | 19da:a247 | Intel      | 7 Series/C216 Chipset Fam... | 2     | i2c_i801   | 4A3ACD7700 |
| 8086:2292 | 8086:2292 | Intel      | Atom/Celeron/Pentium Proc... | 2     | i2c_i801   | 3AB4853FDD |
| 8086:27da | 8086:544b | Intel      | NM10/ICH7 Family SMBus Co... | 2     | i2c_i801   | E1F6C727D9 |
| 8086:31d4 | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 2     |            | E46F325CBA |
| 8086:5ad4 | 8086:2080 | Intel      | Celeron N3350/Pentium N42... | 2     | i2c_i801   | 745C35E31C |
| 8086:8c22 | 103c:2145 | Intel      | 8 Series/C220 Series Chip... | 2     | i2c_i801   | 9C26D1B3DD |
| 8086:9c22 | 19da:b239 | Intel      | 8 Series SMBus Controller    | 2     | i2c_i801   | DCC5BDEF7D |
| 8086:9d23 | 103c:84f5 | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | C7B3D1917B |
| 8086:9d23 | 1043:8694 | Intel      | Sunrise Point-LP SMBus       | 2     | i801_smbus | 847A813A2C |
| 8086:9da3 | 1043:8790 | Intel      | Cannon Point-LP SMBus Con... | 2     | i2c_i801   | 45389EF622 |
| 8086:9da3 | 17aa:314c | Intel      | Cannon Point-LP SMBus Con... | 2     | i2c_i801   | 0F66B49A44 |
| 8086:9da3 | 8086:2079 | Intel      | Cannon Point-LP SMBus Con... | 2     | i801_smbus | 45B14891D4 |
| 8086:a0a3 | 8086:3004 | Intel      | Tiger Lake-LP SMBus Contr... | 2     | i2c_i801   | 93033ED87E |
| 8086:a123 | 1019:9bc6 | Intel      | 100 Series/C230 Series Ch... | 2     | i2c_i801   | 7101BAED7A |
| 8086:a123 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 2     | i801_smbus | D8B8CA1E48 |
| 8086:a323 | 103c:8458 | Intel      | Cannon Lake PCH SMBus Con... | 2     |            | 87E6E38B4A |
| 8086:a323 | 19da:b411 | Intel      | Cannon Lake PCH SMBus Con... | 2     | i2c_i801   | CF60BF6309 |
| 8086:a323 | 8086:2089 | Intel      | Cannon Lake PCH SMBus Con... | 2     | i2c_i801   | 592FA60C7D |
| 1002:4385 | 19da:a183 | AMD        | SBx00 SMBus Controller       | 1     | i2c_pii... | 037A3E45C7 |
| 1002:4385 | 19da:a233 | AMD        | SBx00 SMBus Controller       | 1     | i2c_piix4  | 3ACC3E5A05 |
| 1022:780b | 19da:b208 | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | C6C5AE5CC4 |
| 1022:780b | 19da:b218 | AMD        | FCH SMBus Controller         | 1     | i2c_pii... | EB76FF1C3F |
| 1022:780b | 19da:b233 | AMD        | FCH SMBus Controller         | 1     | piix4_s... | F240F7B02F |
| 1022:790b | 103c:8523 | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | BAB721D52E |
| 1022:790b | 103c:872c | AMD        | FCH SMBus Controller         | 1     | i2c_pii... | 0E48C94F83 |
| 1022:790b | 17aa:30fd | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | 5F6F9A1C6C |
| 1022:790b | 17aa:3181 | AMD        | FCH SMBus Controller         | 1     | piix4_s... | A203CD8C57 |
| 1022:790b | 1854:0309 | AMD        | FCH SMBus Controller         | 1     | piix4_s... | DC014D0C85 |
| 8086:02a3 | 8086:7270 | Intel      | Comet Lake PCH-LP SMBus H... | 1     | i2c_i801   | 64FFE9BE15 |
| 8086:06a3 | 103c:871a | Intel      | Comet Lake PCH SMBus Cont... | 1     | i801_smbus | F74885CE0C |
| 8086:06a3 | 103c:8755 | Intel      | Comet Lake PCH SMBus Cont... | 1     |            | 334ABF8C53 |
| 8086:06a3 | 17aa:316e | Intel      | Comet Lake PCH SMBus Cont... | 1     | i2c_i801   | 7146ACBC96 |
| 8086:06a3 | 17aa:3172 | Intel      | Comet Lake PCH SMBus Cont... | 1     | i2c_i801   | 3E09AE8DEE |
| 8086:0f12 | 1028:07b9 | Intel      | Atom Processor E3800 Seri... | 1     |            | F444E9914B |
| 8086:0f12 | 1071:0740 | Intel      | Atom Processor E3800 Seri... | 1     |            | F2F4C5E23E |
| 8086:0f12 | 17aa:3688 | Intel      | Atom Processor E3800 Seri... | 1     | i2c_i801   | A88328FDB9 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9dc8 | 8086:2074 | Intel      | Cannon Point-LP High Defi... | 115   | snd_hda... | 7CA350189C |
| 8086:9d71 | 8086:2068 | Intel      | Sunrise Point-LP HD Audio    | 55    | snd_hda... | 38D5C55BD7 |
| 8086:02c8 | 8086:2081 | Intel      | Comet Lake PCH-LP cAVS       | 54    | snd_hda... | 92AA2017B9 |
| 8086:1e20 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 36    | snd_hda... | 066B825941 |
| 8086:9ca0 | 8086:2057 | Intel      | Wildcat Point-LP High Def... | 36    | snd_hda... | 7E0F62D2FD |
| 8086:160c | 8086:2057 | Intel      | Broadwell-U Audio Controller | 35    | snd_hda... | 7E0F62D2FD |
| 8086:2284 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 32    | snd_hda... | 9E568EF477 |
| 8086:3198 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 31    | snd_hda... | 6872FA0523 |
| 8086:a171 | 8086:2073 | Intel      | CM238 HD Audio Controller    | 31    | snd_hda... | D186AF4EE3 |
| 1002:ab08 | 8086:2073 | AMD        | Polaris 22 HDMI Audio        | 27    | snd_hda... | D186AF4EE3 |
| 8086:5a98 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 27    | snd_hda... | B9F5CB4E7C |
| 8086:0f04 | 8086:0f04 | Intel      | Atom Processor Z36xxx/Z37... | 26    | snd_hda... | 9B370AB285 |
| 8086:1c20 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 26    | snd_hda... | 7EBB0672C0 |
| 8086:a170 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 21    | snd_hda... | D148D77A8C |
| 8086:0a0c | 106b:0141 | Intel      | Haswell-ULT HD Audio Cont... | 18    | snd_hda... | 42B0868834 |
| 8086:9c20 | 8086:7270 | Intel      | 8 Series HD Audio Controller | 18    | snd_hda... | 42B0868834 |
| 10de:0ac0 | 10de:cb79 | Nvidia     | MCP79 High Definition Audio  | 15    | snd_hda... | F8B00A2F85 |
| 8086:5a98 |           | Intel      | Celeron N3350/Pentium N42... | 14    | snd_hda... | 161E6B136E |
| 8086:9d71 | 8086:2070 | Intel      | Sunrise Point-LP HD Audio    | 14    | snd_hda... | FA31D6F45C |
| 1002:15de | 1002:15de | AMD        | Raven/Raven2/Fenghuang HD... | 13    | snd_hda... | DBFBDEA28F |
| 8086:27d8 | 8384:7680 | Intel      | NM10/ICH7 Family High Def... | 13    | snd_hda... | ACE927A0C7 |
| 8086:a348 | 17aa:312d | Intel      | Cannon Lake PCH cAVS         | 12    | snd_hda... | D66B009299 |
| 1002:1314 | 103c:17e2 | AMD        | Wrestler HDMI Audio          | 11    | snd_hda... | BF35F8C621 |
| 1002:1637 | 1002:1637 | AMD        | Renoir Radeon High Defini... | 11    | snd_hda... | 79EEA28A8B |
| 1002:4383 | 103c:17e2 | AMD        | SBx00 Azalia (Intel HDA)     | 11    | snd_hda... | BF35F8C621 |
| 1022:15e3 | 1043:87bc | AMD        | Family 17h (Models 10h-1f... | 11    | snd_hda... | 79EEA28A8B |
| 10de:0d94 | 10de:cb89 | Nvidia     | MCP89 High Definition Audio  | 11    | snd_hda... | 9ADEB0BD4E |
| 8086:0f04 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 11    | snd_hda... | EED35A825A |
| 8086:2284 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 11    | snd_hda... | CABBA2C402 |
| 8086:5a98 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 11    | snd_hda... | 1F796A44E6 |
| 8086:9d70 | 8086:2063 | Intel      | Sunrise Point-LP HD Audio    | 11    | snd_hda... | 8747496A6B |
| 8086:3198 | 1043:871d | Intel      | Celeron/Pentium Silver Pr... | 10    | snd_hda... | 9D5F2807CE |
| 8086:0f04 | 17aa:368d | Intel      | Atom Processor Z36xxx/Z37... | 9     | snd_hda... | CA54ECE919 |
| 1002:aa90 | 0000:aa90 | AMD        | Turks HDMI Audio [Radeon ... | 7     | snd_hda... | 7EBB0672C0 |
| 1022:15e3 | 17aa:3130 | AMD        | Family 17h (Models 10h-1f... | 7     | snd_hda... | DBFBDEA28F |
| 106b:1803 | 106b:1884 | Apple      | Audio Device                 | 7     |            | D09823163E |
| 1106:3288 | 1106:3288 | VIA Tec... | VX900/VT8xxx High Definit... | 7     | snd_hda... | CEDC05FE9E |
| 8086:a348 | 17aa:3135 | Intel      | Cannon Lake PCH cAVS         | 7     | snd_hda... | B16B2D9BD5 |
| 8086:a348 | 8086:7270 | Intel      | Cannon Lake PCH cAVS         | 7     | snd_hda... | D09823163E |
| 8086:0f04 | 17aa:30b5 | Intel      | Atom Processor Z36xxx/Z37... | 6     | snd_hda... | 538597F50A |
| 8086:160c | 111e:10ec | Intel      | Broadwell-U Audio Controller | 6     | snd_hda... | 859A8D53F5 |
| 1002:9840 | 103c:8158 | AMD        | Kabini HDMI/DP Audio         | 5     | snd_hda... | 95BC62EF3F |
| 1022:157a | 103c:8158 | AMD        | Family 15h (Models 60h-6f... | 5     | snd_hda... | 95BC62EF3F |
| 8086:0f04 | 1b50:5709 | Intel      | Atom Processor Z36xxx/Z37... | 5     | snd_hda... | A27BE7CA62 |
| 8086:3198 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | snd_hda... | 2048DCBA92 |
| 8086:5a98 | 10ec:1128 | Intel      | Celeron N3350/Pentium N42... | 5     | snd_hda... | B2CC37B9AC |
| 8086:9ca0 | 8086:7270 | Intel      | Wildcat Point-LP High Def... | 5     | snd_hda... | 859A8D53F5 |
| 8086:9d71 | 8086:7270 | Intel      | Sunrise Point-LP HD Audio    | 5     | snd_hda... | D391C49614 |
| 8086:9dc8 | 17aa:314d | Intel      | Cannon Point-LP High Defi... | 5     | snd_hda... | 032DB5DB0F |
| 8086:a170 | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 5     | snd_hda... | A080CA6AD4 |
| 8086:a348 | 17aa:3136 | Intel      | Cannon Lake PCH cAVS         | 5     | snd_hda... | 6F39F78FAC |
| 1002:15b3 | 17aa:312f | AMD        | High Definition Audio Con... | 4     | snd_hda... | 5205C41BC5 |
| 1002:ab08 | 8086:ab08 | AMD        | Polaris 22 HDMI Audio        | 4     | snd_hda... | 122748D8A8 |
| 1022:157a | 17aa:312f | AMD        | Family 15h (Models 60h-6f... | 4     | snd_hda... | 5205C41BC5 |
| 1022:15e3 | 17aa:3151 | AMD        | Family 17h (Models 10h-1f... | 4     | snd_hda... | E57DFE6F39 |
| 8086:0c0c | 19da:b220 | Intel      | Xeon E3-1200 v3/4th Gen C... | 4     | snd_hda... | FCAA602427 |
| 8086:0f04 | 19da:b219 | Intel      | Atom Processor Z36xxx/Z37... | 4     | snd_hda... | 494AE0914E |
| 8086:160c | 8086:2058 | Intel      | Broadwell-U Audio Controller | 4     | snd_hda... | 6E19619F29 |
| 8086:1e20 | 19da:b211 | Intel      | 7 Series/C216 Chipset Fam... | 4     | snd_hda... | EFBBD0C3F8 |
| 8086:2284 | 17aa:30dd | Intel      | Atom/Celeron/Pentium Proc... | 4     | snd_hda... | 0513ACEC04 |
| 8086:2284 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 4     | snd_hda... | 0D05B404DD |
| 8086:5a98 | 10ec:0000 | Intel      | Celeron N3350/Pentium N42... | 4     | snd_hda... | B9140B8786 |
| 8086:8c20 | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 4     | snd_hda... | FCAA602427 |
| 8086:9ca0 | 8086:2058 | Intel      | Wildcat Point-LP High Def... | 4     | snd_hda... | 6E19619F29 |
| 8086:a2f0 | 103c:82a5 | Intel      | 200 Series PCH HD Audio      | 4     | snd_hda... | 08B98B6A88 |
| 1002:1314 | 19da:a191 | AMD        | Wrestler HDMI Audio          | 3     | snd_hda... | 121F403E29 |
| 1002:15b3 | 103c:8267 | AMD        | High Definition Audio Con... | 3     | snd_hda... | 3AA09CF72A |
| 1002:15de | 103c:8836 | AMD        | Raven/Raven2/Fenghuang HD... | 3     | snd_hda... | DDEEE57DBD |
| 1002:1637 | 103c:872e | AMD        | Renoir Radeon High Defini... | 3     | snd_hda... | 7791A24770 |
| 1002:4383 | 19da:a191 | AMD        | SBx00 Azalia (Intel HDA)     | 3     | snd_hda... | 121F403E29 |
| 1002:aae0 | 8086:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 3     | snd_hda... | 45B14891D4 |
| 1022:157a | 103c:8267 | AMD        | Family 15h (Models 60h-6f... | 3     | snd_hda... | 3AA09CF72A |
| 1022:15e3 | 103c:872e | AMD        | Family 17h (Models 10h-1f... | 3     | snd_hda... | 7791A24770 |
| 10de:0e08 | 19da:2180 | Nvidia     | GF119 HDMI Audio Controller  | 3     | snd_hda... | 49EF2577E1 |
| 10de:0fb9 | 10de:1264 | Nvidia     | GP107GL High Definition A... | 3     | snd_hda... | B16B2D9BD5 |
| 10de:0fbc | 103c:82c0 | Nvidia     | GM107 High Definition Aud... | 3     | snd_hda... | 44430304D3 |
| 10de:10f1 |           | Nvidia     | GP106 High Definition Aud... | 3     | snd_hda... | 29DC0371D1 |
| 8086:02c8 | 1043:87bc | Intel      | Comet Lake PCH-LP cAVS       | 3     | snd_hda... | 1C1741820B |
| 8086:0f28 | 8086:0f28 | Intel      | Atom Processor Z36xxx/Z37... | 3     |            | AD5481A5BC |
| 8086:2284 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 3     | snd_hda... | FDE91E565C |
| 8086:2284 | 17aa:3637 | Intel      | Atom/Celeron/Pentium Proc... | 3     | snd_hda... | 442724EA6A |
| 8086:2284 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 3     | snd_hda... | 7F47BED9CF |
| 8086:27d8 | 19da:a218 | Intel      | NM10/ICH7 Family High Def... | 3     | snd_hda... | 49EF2577E1 |
| 8086:5a98 | 10ec:111e | Intel      | Celeron N3350/Pentium N42... | 3     | snd_hda... | 1E917E7979 |
| 8086:a170 | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 3     | snd_hda... | 44430304D3 |
| 8086:a2f0 | 103c:829a | Intel      | 200 Series PCH HD Audio      | 3     | snd_hda... | C326081D7D |
| 1002:1314 | 1002:1314 | AMD        | Wrestler HDMI Audio          | 2     | snd_hda... | 8C3CA64606 |
| 1022:15e3 | 103c:8836 | AMD        | Family 17h (Models 10h-1f... | 2     | snd_hda... | DDEEE57DBD |
| 1022:780d | 19da:a261 | AMD        | FCH Azalia Controller        | 2     | snd_hda... | 8C3CA64606 |
| 10de:0fb9 | 103c:8458 | Nvidia     | GP107GL High Definition A... | 2     | snd_hda... | 87E6E38B4A |
| 8086:0a0c | 19da:b239 | Intel      | Haswell-ULT HD Audio Cont... | 2     | snd_hda... | C596469F40 |
| 8086:0c0c | 103c:2145 | Intel      | Xeon E3-1200 v3/4th Gen C... | 2     | snd_hda... | 9C26D1B3DD |
| 8086:0f04 | 1071:0730 | Intel      | Atom Processor Z36xxx/Z37... | 2     | snd_hda... | BE63E554C5 |
| 8086:1c20 | 19da:b202 | Intel      | 6 Series/C200 Series Chip... | 2     | snd_hda... | 4D23C29B62 |
| 8086:1e20 | 19da:a247 | Intel      | 7 Series/C216 Chipset Fam... | 2     | snd_hda... | 4A3ACD7700 |
| 8086:2284 | 1c6c:122a | Intel      | Atom/Celeron/Pentium Proc... | 2     | snd_hda... | 3AB4853FDD |
| 8086:27d8 | 8086:d626 | Intel      | NM10/ICH7 Family High Def... | 2     | snd_hda... | E1F6C727D9 |
| 8086:3198 | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 2     | snd_hda... | E46F325CBA |
| 8086:5a98 | 1c6c:122a | Intel      | Celeron N3350/Pentium N42... | 2     | snd_hda... | 63E4DA1D94 |
| 8086:5a98 | 1d09:0101 | Intel      | Celeron N3350/Pentium N42... | 2     | snd_hda... | 0B85289EF2 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9dd3 | 8086:2074 | Intel      | Cannon Point-LP SATA Cont... | 112   | ahci       | 7CA350189C |
| 8086:9d03 | 8086:2068 | Intel      | Sunrise Point-LP SATA Con... | 58    | ahci       | 38D5C55BD7 |
| 8086:02d3 | 8086:2081 | Intel      | Comet Lake SATA AHCI Cont... | 53    | ahci       | 92AA2017B9 |
| 8086:1e03 | 8086:7270 | Intel      | 7 Series Chipset Family 6... | 36    | ahci       | 066B825941 |
| 8086:9c83 | 8086:2057 | Intel      | Wildcat Point-LP SATA Con... | 35    | ahci       | 7E0F62D2FD |
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 34    | ahci       | B2CC37B9AC |
| 8086:0f23 | 8086:0f23 | Intel      | Atom Processor E3800 Seri... | 32    | ahci       | DD7BEAC148 |
| 8086:22a3 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 32    | ahci       | 9E568EF477 |
| 8086:31e3 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 31    | ahci       | 6872FA0523 |
| 8086:5ae3 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 29    | ahci       | B9F5CB4E7C |
| 8086:1c03 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 23    | ahci       | 7EBB0672C0 |
| 8086:9c03 | 8086:7270 | Intel      | 8 Series SATA Controller ... | 18    | ahci       | 42B0868834 |
| 8086:9d03 | 8086:2070 | Intel      | Sunrise Point-LP SATA Con... | 13    | ahci       | FA31D6F45C |
| 10de:0ab9 | 10de:cb79 | Nvidia     | MCP79 AHCI Controller        | 12    | ahci       | F8B00A2F85 |
| 8086:9d03 | 8086:2063 | Intel      | Sunrise Point-LP SATA Con... | 12    | ahci       | 8747496A6B |
| 8086:a352 | 17aa:312d | Intel      | Cannon Lake PCH SATA AHCI... | 12    | ahci       | D66B009299 |
| 1022:7901 | 1043:87e7 | AMD        | FCH SATA Controller [AHCI... | 11    | ahci       | 79EEA28A8B |
| 10de:0d88 | 106b:cb89 | Nvidia     | MCP89 SATA Controller (AH... | 11    | ahci       | 9ADEB0BD4E |
| 8086:22a3 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 11    | ahci       | CABBA2C402 |
| 8086:a103 | 8086:2064 | Intel      | HM170/QM170 Chipset SATA ... | 11    | ahci       | F24D65AFEC |
| 8086:31e3 | 1043:875e | Intel      | Celeron/Pentium Silver Pr... | 10    | ahci       | 9D5F2807CE |
| 1002:4390 | 103c:17e2 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 9     | ahci       | C70D710959 |
| 8086:0f23 | 17aa:368d | Intel      | Atom Processor E3800 Seri... | 9     | ahci       | CA54ECE919 |
| 8086:31e3 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 7     | ahci       | 2048DCBA92 |
| 8086:a103 | 8086:2073 | Intel      | HM170/QM170 Chipset SATA ... | 7     | ahci       | D186AF4EE3 |
| 8086:a352 | 17aa:3135 | Intel      | Cannon Lake PCH SATA AHCI... | 7     | ahci       | B16B2D9BD5 |
| 1022:7901 | 17aa:3130 | AMD        | FCH SATA Controller [AHCI... | 6     | ahci       | DBFBDEA28F |
| 8086:0f23 | 17aa:30b5 | Intel      | Atom Processor E3800 Seri... | 6     | ahci       | 538597F50A |
| 8086:5ae3 | 19da:b325 | Intel      | Celeron N3350/Pentium N42... | 6     | ahci       | 23BDDBF63A |
| 8086:9d03 | 8086:7270 | Intel      | Sunrise Point-LP SATA Con... | 6     | ahci       | D391C49614 |
| 1022:7901 | 103c:8158 | AMD        | FCH SATA Controller [AHCI... | 5     | ahci       | 95BC62EF3F |
| 1b4b:9215 | 1b4b:9215 | Marvell... | 88SE9215 PCIe 2.0 x1 4-po... | 5     | ahci       | ED960141AA |
| 8086:0f23 |           | Intel      | Atom Processor E3800 Seri... | 5     | ahci       | A27BE7CA62 |
| 8086:a102 | 19da:b333 | Intel      | Q170/Q150/B150/H170/H110/... | 5     | ahci       | A080CA6AD4 |
| 1022:7901 | 17aa:312f | AMD        | FCH SATA Controller [AHCI... | 4     | ahci       | 5205C41BC5 |
| 1022:7901 | 17aa:3151 | AMD        | FCH SATA Controller [AHCI... | 4     | ahci       | E57DFE6F39 |
| 8086:0f23 | 19da:b219 | Intel      | Atom Processor E3800 Seri... | 4     | ahci       | 494AE0914E |
| 8086:1e03 | 19da:b211 | Intel      | 7 Series Chipset Family 6... | 4     | ahci       | EFBBD0C3F8 |
| 8086:22a3 | 17aa:30dd | Intel      | Atom/Celeron/Pentium Proc... | 4     | ahci       | 0513ACEC04 |
| 8086:22a3 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 4     | ahci       | 0D05B404DD |
| 8086:8c02 | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 4     | ahci       | FCAA602427 |
| 8086:9c83 | 8086:2058 | Intel      | Wildcat Point-LP SATA Con... | 4     | ahci       | 6E19619F29 |
| 8086:9c83 | 8086:7270 | Intel      | Wildcat Point-LP SATA Con... | 4     | ahci       | 859A8D53F5 |
| 8086:a282 | 103c:82a5 | Intel      | 200 Series PCH SATA contr... | 4     | ahci       | 08B98B6A88 |
| 8086:a352 | 17aa:3136 | Intel      | Cannon Lake PCH SATA AHCI... | 4     | ahci       | 6F39F78FAC |
| 1002:4390 | 19da:a191 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 3     | ahci       | 121F403E29 |
| 1022:43eb | 103c:872e | AMD        | Starship/Matisse Chipset ... | 3     | ahci       | 7791A24770 |
| 1022:43eb | 103c:8836 | AMD        | Starship/Matisse Chipset ... | 3     | ahci       | DDEEE57DBD |
| 1022:7901 | 103c:8267 | AMD        | FCH SATA Controller [AHCI... | 3     | ahci       | 3AA09CF72A |
| 8086:02d3 | 1043:87bd | Intel      | Comet Lake SATA AHCI Cont... | 3     | ahci       | 1C1741820B |
| 8086:0f23 | 8086:7270 | Intel      | Atom Processor E3800 Seri... | 3     | ahci       | EED35A825A |
| 8086:22a3 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 3     | ahci       | FDE91E565C |
| 8086:22a3 | 17aa:3637 | Intel      | Atom/Celeron/Pentium Proc... | 3     | ahci       | 442724EA6A |
| 8086:22a3 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 3     | ahci       | 7F47BED9CF |
| 8086:27c5 | 8086:7270 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 3     | ahci       | AC61B9B105 |
| 8086:5ae3 | 8086:5ae3 | Intel      | Celeron N3350/Pentium N42... | 3     | ahci       | 161E6B136E |
| 1002:4391 | 103c:17e2 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 2     | ahci       | BF35F8C621 |
| 1b21:0625 | 1b21:1060 | ASMedia... | 106x SATA/RAID Controller    | 2     | ahci       | 37D4C2C91D |
| 8086:06d2 | 103c:8710 | Intel      | Comet Lake SATA AHCI Cont... | 2     | ahci       | B2A212246B |
| 8086:0f23 | 1071:0730 | Intel      | Atom Processor E3800 Seri... | 2     | ahci       | BE63E554C5 |
| 8086:1c02 | 19da:b202 | Intel      | 6 Series/C200 Series Chip... | 2     | ahci       | 4D23C29B62 |
| 8086:1e03 | 19da:a247 | Intel      | 7 Series Chipset Family 6... | 2     | ahci       | 4A3ACD7700 |
| 8086:27c1 | 19da:a218 | Intel      | NM10/ICH7 Family SATA Con... | 2     | ahci       | 49EF2577E1 |
| 8086:31e3 | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 2     | ahci       | E46F325CBA |
| 8086:5ae3 | 8086:2080 | Intel      | Celeron N3350/Pentium N42... | 2     | ahci       | 745C35E31C |
| 8086:8c02 | 103c:2145 | Intel      | 8 Series/C220 Series Chip... | 2     | ahci       | 9C26D1B3DD |
| 8086:9c03 | 19da:b239 | Intel      | 8 Series SATA Controller ... | 2     | ahci       | DCC5BDEF7D |
| 8086:9d03 | 103c:84f5 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | C7B3D1917B |
| 8086:9d03 | 1043:8694 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 847A813A2C |
| 8086:9dd3 | 1043:8790 | Intel      | Cannon Point-LP SATA Cont... | 2     | ahci       | 45389EF622 |
| 8086:a102 | 1019:9bc6 | Intel      | Q170/Q150/B150/H170/H110/... | 2     | ahci       | 7101BAED7A |
| 8086:a102 | 8086:7270 | Intel      | Q170/Q150/B150/H170/H110/... | 2     | ahci       | D8B8CA1E48 |
| 8086:a282 | 103c:829a | Intel      | 200 Series PCH SATA contr... | 2     | ahci       | C326081D7D |
| 8086:a353 | 19da:b411 | Intel      | Cannon Lake Mobile PCH SA... | 2     | ahci       | CF60BF6309 |
| 8086:a353 | 8086:2089 | Intel      | Cannon Lake Mobile PCH SA... | 2     | ahci       | 592FA60C7D |
| 1002:4390 | 19da:a233 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 3ACC3E5A05 |
| 1002:4391 | 19da:a183 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 037A3E45C7 |
| 1022:7800 | 19da:a261 | AMD        | FCH SATA Controller [IDE ... | 1     | ahci       | 8C3CA64606 |
| 1022:7801 | 19da:a261 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 8D13B8BFE3 |
| 1022:7801 | 19da:b208 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | C6C5AE5CC4 |
| 1022:7801 | 19da:b218 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | EB76FF1C3F |
| 1022:7801 | 19da:b233 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | F240F7B02F |
| 1022:7901 | 103c:8523 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | BAB721D52E |
| 1022:7901 | 17aa:30fd | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 5F6F9A1C6C |
| 1022:7901 | 1854:0309 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | DC014D0C85 |
| 1b21:0612 | 1b21:1060 | ASMedia... | ASM1062 Serial ATA Contro... | 1     | ahci       | F2F4C5E23E |
| 1b21:0622 | 1b21:1060 | ASMedia... | 106x SATA/RAID Controller    | 1     | ahci       | CFAD8B93A9 |
| 8086:02d3 | 8086:7270 | Intel      | Comet Lake SATA AHCI Cont... | 1     | ahci       | 64FFE9BE15 |
| 8086:06d2 | 103c:871a | Intel      | Comet Lake SATA AHCI Cont... | 1     | ahci       | F74885CE0C |
| 8086:06d2 | 103c:8755 | Intel      | Comet Lake SATA AHCI Cont... | 1     | ahci       | 334ABF8C53 |
| 8086:06d2 | 17aa:316e | Intel      | Comet Lake SATA AHCI Cont... | 1     | ahci       | 7146ACBC96 |
| 8086:0f23 | 1071:0740 | Intel      | Atom Processor E3800 Seri... | 1     | ahci       | F2F4C5E23E |
| 8086:0f23 | 17aa:3688 | Intel      | Atom Processor E3800 Seri... | 1     | ahci       | A88328FDB9 |
| 8086:0f23 | 1d05:100f | Intel      | Atom Processor E3800 Seri... | 1     | ahci       | 9569E1B79C |
| 8086:1c02 | 1734:11ba | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | FC67594808 |
| 8086:1c03 | 19da:a217 | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | 0909932423 |
| 8086:1e03 | 19da:a246 | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | BD2FB45ED8 |
| 8086:1e03 | 1b0a:015b | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | 7E54F1E784 |
| 8086:1f22 | 8086:7270 | Intel      | Atom processor C2000 AHCI... | 1     | ahci       | C1D37659C1 |
| 8086:1f32 | 8086:7270 | Intel      | Atom processor C2000 AHCI... | 1     | ahci       | C1D37659C1 |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27df | 8086:7270 | Intel      | 82801G (ICH7 Family) IDE ... | 14    | pata_acpi  | C480910C6C |
| 8086:27c4 | 8086:7270 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 11    | pata_acpi  | C480910C6C |
| 1106:9001 | 1106:9001 | VIA Tec... | VX900 Series Serial-ATA C... | 8     | pata_vi... | 15268C0CCC |
| 10de:0ab5 | 10de:cb79 | Nvidia     | MCP79 SATA Controller        | 4     | ahci, p... | BA999E7825 |
| 1002:439c | 19da:a191 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 3     | pata_at... | 121F403E29 |
| 8086:1c01 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 3     | ata_pii... | 9898EDBAF1 |
| 1022:780c | 19da:a261 | AMD        | FCH IDE Controller           | 2     | pata_at... | 8C3CA64606 |
| 8086:27c0 | 8086:544b | Intel      | NM10/ICH7 Family SATA Con... | 2     | ata_pii... | E1F6C727D9 |
| 1002:439c | 19da:a183 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | pata_at... | 037A3E45C7 |
| 1002:439c | 19da:a233 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | pata_at... | 3ACC3E5A05 |
| 1022:780c | 19da:b218 | AMD        | FCH IDE Controller           | 1     | pata_at... | EB76FF1C3F |
| 8086:0f21 | 17aa:368d | Intel      | Atom Processor E3800 Seri... | 1     | ata_pii... | E3D598C5CB |
| 8086:24cb | 8086:1977 | Intel      | 82801DB (ICH4) IDE Contro... | 1     | ata_piix   | 4A3E3CD4EE |
| 8086:27c0 | 19da:a140 | Intel      | NM10/ICH7 Family SATA Con... | 1     | pata_acpi  | 90F8E7B807 |
| 8086:27c0 | 19da:a218 | Intel      | NM10/ICH7 Family SATA Con... | 1     | ata_pii... | E907BA80AE |
| 8086:27c0 | 8086:7270 | Intel      | NM10/ICH7 Family SATA Con... | 1     | pata_acpi  | 6B9414B09F |
| 8086:27c4 | 8086:27c4 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 1     | pata_acpi  | 10DB69DD6C |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 110   | nvme       | FA31D6F45C |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 29    | nvme       | 7CA350189C |
| 2646:2263 | 2646:2263 | Kingsto... | A2000 NVMe SSD               | 11    | nvme       | D340A44211 |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 11    | nvme       | 08A78A5D61 |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 11    | nvme       | 38D5C55BD7 |
| 15b7:5006 | 15b7:5006 | Sandisk    | WD Black SN750 / PC SN730... | 10    | nvme       | 616E5444CA |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 9     | nvme       | 96ED551BEB |
| c0a9:2263 | c0a9:2263 | Micron/... | P1 NVMe PCIe SSD             | 9     | nvme       | 4176A10062 |
| 126f:2263 | 126f:2263 | Silicon... | SM2263EN/SM2263XT SSD Con... | 8     | nvme       | B8E9AC2EB7 |
| 106b:2005 | 106b:1800 | Apple      | ANS2 NVMe Controller         | 7     | nvme       | D09823163E |
| 144d:a809 | 144d:a801 | Samsung... | NVMe Controller              | 7     | nvme       | DDEEE57DBD |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/SN750 / PC ... | 6     | nvme       | 79C63E5CED |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 5     | nvme       | D148D77A8C |
| 1987:5008 | 1987:5008 | Phison ... | NVMe Storage Controller      | 5     | nvme       | 161445E905 |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 5     | nvme       | 66A02F462F |
| 1179:011a | 1179:0001 | Toshiba... | XG6 NVMe SSD Controller      | 4     | nvme       | 5205C41BC5 |
| 15b7:5009 | 15b7:5009 | Sandisk    | WD Blue SN550 NVMe SSD       | 4     | nvme       | D9CC78FCFF |
| 15b7:5005 | 15b7:5005 | Sandisk    | PC SN520 NVMe SSD            | 3     | nvme       | 3376399C24 |
| 1987:5016 | 1987:5016 | Phison ... | E16 PCIe4 NVMe Controller    | 3     | nvme       | AECEFCDF3A |
| 1c5c:1639 | 1c5c:1639 | SK Hynix   | Non-Volatile memory contr... | 3     | nvme       | BC5EFD9EB0 |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 3     | nvme       | 068E76C455 |
| 8086:2522 | 8086:3806 | Intel      | NVMe Optane Memory Series    | 3     | nvme       | 13353E2037 |
| 1022:b000 | 144d:a801 | AMD        | RAID Bottom Device           | 2     | nvme       | F2418E15EC |
| 10ec:5762 | 10ec:5762 | Realtek... | RTS5763DL NVMe SSD Contro... | 2     | nvme       | 847A813A2C |
| 10ec:5763 | 10ec:5763 | Realtek... | Realtek Non-Volatile memo... | 2     | nvme       | A03DE89D54 |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 2     | nvme       | FCFE6EF0D3 |
| 1987:5007 | 1987:5007 | Phison ... | E7 NVMe Controller           | 2     | nvme       | F9C39F6628 |
| 1987:5013 | 1987:5013 | Phison ... | PS5013 E13 NVMe Controller   | 2     | nvme       | 2E2F3EAEB6 |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | BC501 NVMe Solid State Dr... | 2     | nvme       | 36CC2B3CE6 |
| 1c5c:1627 | 1c5c:1627 | SK Hynix   | Non-Volatile memory contr... | 2     | nvme       | 232C90CE25 |
| 2646:5008 | 2646:5008 | Kingsto... | U-SNS8154P3 NVMe SSD         | 2     | nvme       | F359C98F49 |
| 8086:faf0 | 8086:390e | Intel      | Non-Volatile memory contr... | 2     | nvme       | 391F80AE12 |
| c0a9:540a | c0a9:540a | Micron/... | P2 NVMe PCIe SSD             | 2     | nvme       | DACE055942 |
| 1022:b000 | 15b7:5006 | AMD        | RAID Bottom Device           | 1     | nvme       | 0E48C94F83 |
| 10ec:5760 | 5760:10ec | Realtek... | Realtek Non-Volatile memo... | 1     | nvme       | 8ED3B0B386 |
| 126f:2260 | 126f:2260 | Silicon... | Non-Volatile memory contr... | 1     | nvme       | 400EFE971D |
| 126f:2262 | 126f:2262 | Silicon... | SM2262/SM2262EN SSD Contr... | 1     | nvme       | 275EDFBD40 |
| 1344:5405 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 1     | nvme       | AD99B098F1 |
| 144d:a80a | 144d:a801 | Samsung... | NVMe SSD Controller PM9A1... | 1     | nvme       | 93033ED87E |
| 14a4:22f1 | 1b4b:1093 | Lite-On... | M8Pe Series NVMe SSD         | 1     | nvme       | 0521601823 |
| 14a4:2300 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 1     | nvme       | D66B009299 |
| 14a4:23f1 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 1     | nvme       | 7A38C478BB |
| 15b7:5001 | 1b4b:1093 | Sandisk    | WD Black NVMe SSD            | 1     | nvme       | 2ED31BB0E7 |
| 15b7:5003 | 15b7:5003 | Sandisk    | WD Blue SN500 / PC SN520 ... | 1     | nvme       | 4D929C77F8 |
| 15b7:5011 | 15b7:5011 | Sandisk    | WD Black SN850               | 1     | nvme       | B5D3CAB487 |
| 1b85:6018 | 1b85:6018 | OCZ Tec... | RD400/400A SSD               | 1     | nvme       | 5F2AF32D67 |
| 1c5c:1339 | 1c5c:0000 | SK Hynix   | BC511                        | 1     | nvme       | 453436FD86 |
| 1c5c:174a | 1c5c:174a | SK Hynix   | NVMe SSD Controller          | 1     | nvme       | 77148ED0AA |
| 1cc4:17aa | 1cc4:1008 | Union M... | Non-Volatile memory contr... | 1     | nvme       | 4C26C41224 |
| 2646:2262 | 2646:2262 | Kingsto... | KC2000 NVMe SSD              | 1     | nvme       | 23C1513C53 |
| 8086:2522 | 8086:3810 | Intel      | NVMe Optane Memory Series    | 1     | nvme       | D0D875E1E5 |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2822 | 103c:82c0 | Intel      | SATA Controller [RAID mode]  | 3     | ahci       | 44430304D3 |
| 8086:282a | 8086:2074 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | D0D875E1E5 |
| 8086:2822 | 103c:8458 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 87E6E38B4A |
| 1022:43bd | 103c:872c | AMD        | FCH RAID Controller          | 1     |            | 0E48C94F83 |
| 8086:2822 | 103c:829a | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | E0FB7EA560 |
| 8086:282a | 19da:b248 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | D521E3AD79 |
| 8086:282a | 8086:2079 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 985AA77681 |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1911 | 8086:2074 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 116   |            | 7CA350189C |
| 8086:1911 | 8086:2068 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 58    |            | 38D5C55BD7 |
| 8086:1911 | 8086:2081 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 53    |            | 92AA2017B9 |
| 8086:15e8 | 8086:2081 | Intel      | JHL7540 Thunderbolt 3 NHI... | 52    | thunder... | 92AA2017B9 |
| 8086:1911 | 8086:2073 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 31    |            | D186AF4EE3 |
| 8086:1513 | 2222:1111 | Intel      | CV82524 Thunderbolt Contr... | 26    | thunder... | 7EBB0672C0 |
| 8086:1911 | 8086:2064 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 21    |            | D148D77A8C |
| 8086:156c |           | Intel      | DSL5520 Thunderbolt 2 NHI... | 18    | thunder... | 42B0868834 |
| 8086:1911 | 8086:2070 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 14    |            | FA31D6F45C |
| 8086:1911 | 17aa:312d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 12    |            | D66B009299 |
| 8086:3190 | 1043:875e | Intel      | Celeron/Pentium Silver Pr... | 10    |            | 9D5F2807CE |
| 8086:15eb | 8086:0000 | Intel      | JHL7540 Thunderbolt 3 NHI... | 7     | thunder... | D09823163E |
| 8086:1911 | 17aa:3135 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 7     |            | B16B2D9BD5 |
| 8086:1911 | 8086:2015 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 7     |            | D391C49614 |
| 8086:15d9 | 8086:2074 | Intel      | JHL6340 Thunderbolt 3 NHI... | 6     | thunder... | 4A94A9D35A |
| 8086:1911 | 17aa:3136 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 6F39F78FAC |
| 8086:1911 | 17aa:314d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 032DB5DB0F |
| 8086:15de | 2222:1111 | Intel      | JHL6340 Thunderbolt 3 Con... | 4     | thunder... | 78B5820785 |
| 8086:1911 | 19da:b333 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | 29DC0371D1 |
| 8086:1575 | 2222:1111 | Intel      | DSL6340 Thunderbolt 3 NHI... | 3     | thunder... | D148D77A8C |
| 8086:15eb | 8086:2088 | Intel      | JHL7540 Thunderbolt 3 NHI... | 3     | thunder... | 592FA60C7D |
| 8086:3190 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     |            | 3CD7D7E119 |
| 8086:1911 | 1019:9bc6 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 7101BAED7A |
| 8086:1911 | 17aa:314c | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 0F66B49A44 |
| 8086:1911 | 19da:b411 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | CF60BF6309 |
| 8086:1911 | 8086:2079 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 45B14891D4 |
| 8086:1911 | 8086:2089 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 592FA60C7D |
| 8086:3190 | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 2     |            | E46F325CBA |
| 8086:3190 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 2     |            | 4C465E5A03 |
| 8086:9a11 | 8086:3004 | Intel      | GNA Scoring Accelerator m... | 2     |            | 93033ED87E |
| 8086:1577 | 2222:1111 | Intel      | DSL6540 Thunderbolt 3 NHI... | 1     | thunder... | 40AEEA62F1 |
| 8086:15d2 | 8086:2073 | Intel      | JHL6540 Thunderbolt 3 NHI... | 1     | thunder... | 9A5A163CB3 |
| 8086:15d9 | 8086:0000 | Intel      | JHL6340 Thunderbolt 3 NHI... | 1     | thunder... | 42A1AEA9C7 |
| 8086:1911 | 17aa:3144 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | E64B1B05A0 |
| 8086:1911 | 17aa:316e | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 7146ACBC96 |
| 8086:1911 | 17aa:3172 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 3E09AE8DEE |
| 8086:1911 | 8086:2088 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | AECEFCDF3A |
| 8086:1911 | 8086:7270 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 64FFE9BE15 |
| 8086:1f15 | 8086:0000 | Intel      | Atom processor C2000 SMBu... | 1     |            | C1D37659C1 |
| 8086:3584 | 8086:1977 | Intel      | 82852/82855 GM/GME/PM/GMV... | 1     |            | 4A3E3CD4EE |
| 8086:3585 | 8086:1977 | Intel      | 82852/82855 GM/GME/PM/GMV... | 1     |            | 4A3E3CD4EE |
| 8086:5a11 | 8086:2075 | Intel      | System peripheral            | 1     |            | 6FD8E8E647 |
| 8086:9a11 | 8086:3003 | Intel      | GNA Scoring Accelerator m... | 1     |            | ABC31CEA35 |
| 8086:9a11 | 8086:3013 | Intel      | GNA Scoring Accelerator m... | 1     |            | 66A02F462F |

### Tv card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 109e:036e |           | Brooktree  | Bt878 Video Capture          | 1     | bttv       | 10DB69DD6C |

### Unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:5aa2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 2     |            | 685FD2AB95 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9ded | 8086:2074 | Intel      | Cannon Point-LP USB 3.1 x... | 116   | xhci_hcd   | 7CA350189C |
| 8086:0f35 | 8086:0f35 | Intel      | Atom Processor Z36xxx/Z37... | 65    | xhci_hcd   | 17E14439B8 |
| 8086:9d2f | 8086:2068 | Intel      | Sunrise Point-LP USB 3.0 ... | 58    | xhci_hcd   | 38D5C55BD7 |
| 8086:02ed | 8086:2081 | Intel      | Comet Lake PCH-LP USB 3.1... | 54    | xhci_hcd   | 92AA2017B9 |
| 8086:15e9 | 8086:2081 | Intel      | JHL7540 Thunderbolt 3 USB... | 52    | xhci_hcd   | 92AA2017B9 |
| 8086:1e26 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 36    | ehci_pci   | 066B825941 |
| 8086:1e2d | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 36    | ehci_pci   | 066B825941 |
| 8086:1e31 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 36    | xhci_hcd   | 066B825941 |
| 8086:9cb1 | 8086:2057 | Intel      | Wildcat Point-LP USB xHCI... | 35    | xhci_hcd   | 7E0F62D2FD |
| 8086:5aa8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 34    | xhci_hcd   | B2CC37B9AC |
| 8086:9ca6 | 8086:2057 | Intel      | Wildcat Point-LP USB EHCI... | 33    | ehci_pci   | 7E0F62D2FD |
| 1b21:2142 | 8086:2073 | ASMedia... | ASM2142 USB 3.1 Host Cont... | 31    | xhci_hcd   | D186AF4EE3 |
| 8086:31a8 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 31    | xhci_hcd   | 6872FA0523 |
| 8086:a12f | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 31    | xhci_hcd   | D186AF4EE3 |
| 8086:15db | 8086:2074 | Intel      | JHL6340 Thunderbolt 3 USB... | 30    | xhci_hcd   | B4FB702E4A |
| 8086:5aa8 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 29    | xhci_hcd   | B9F5CB4E7C |
| 8086:1c26 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 26    | ehci_pci   | 7EBB0672C0 |
| 8086:1c27 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 26    | uhci_hcd   | 7EBB0672C0 |
| 8086:1c2c | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 26    | uhci_hcd   | 7EBB0672C0 |
| 8086:1c2d | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 26    | ehci_pci   | 7EBB0672C0 |
| 8086:22b5 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 24    | xhci_hcd   | CABBA2C402 |
| 8086:22b5 |           | Intel      | Atom/Celeron/Pentium Proc... | 22    | xhci_hcd   | 9E568EF477 |
| 8086:a12f | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 21    | xhci_hcd   | D148D77A8C |
| 8086:9c31 | 8086:7270 | Intel      | 8 Series USB xHCI HC         | 18    | xhci_hcd   | 42B0868834 |
| 10de:0aa5 | 10de:cb79 | Nvidia     | MCP79 OHCI USB 1.1 Contro... | 15    | ohci_pci   | F8B00A2F85 |
| 10de:0aa6 | 10de:cb79 | Nvidia     | MCP79 EHCI USB 2.0 Contro... | 15    | ehci_pci   | F8B00A2F85 |
| 10de:0aa7 | 10de:cb79 | Nvidia     | MCP79 OHCI USB 1.1 Contro... | 15    | ohci_pci   | F8B00A2F85 |
| 10de:0aa9 | 10de:cb79 | Nvidia     | MCP79 EHCI USB 2.0 Contro... | 15    | ehci_pci   | F8B00A2F85 |
| 8086:27c8 | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 15    | uhci_hcd   | C480910C6C |
| 8086:27c9 | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 15    | uhci_hcd   | C480910C6C |
| 8086:27ca | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 15    | uhci_hcd   | C480910C6C |
| 8086:27cb | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 15    | uhci_hcd   | C480910C6C |
| 8086:27cc | 8086:7270 | Intel      | NM10/ICH7 Family USB2 EHC... | 15    | ehci_pci   | C480910C6C |
| 8086:9d2f | 8086:2070 | Intel      | Sunrise Point-LP USB 3.0 ... | 14    | xhci_hcd   | FA31D6F45C |
| 8086:9d2f | 8086:2063 | Intel      | Sunrise Point-LP USB 3.0 ... | 12    | xhci_hcd   | 8747496A6B |
| 8086:a36d | 17aa:312d | Intel      | Cannon Lake PCH USB 3.1 x... | 12    | xhci_hcd   | D66B009299 |
| 1002:4396 | 103c:17e2 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 11    | ehci_pci   | BF35F8C621 |
| 1002:4397 | 103c:17e2 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 11    | ohci_pci   | BF35F8C621 |
| 1022:1639 | 1043:87e7 | AMD        | Renoir USB 3.1               | 11    | xhci_hcd   | 79EEA28A8B |
| 104c:8241 | 103c:17e2 | Texas I... | TUSB73x0 SuperSpeed USB 3... | 11    | xhci_hcd   | BF35F8C621 |
| 10de:0d9c | 10de:cb89 | Nvidia     | MCP89 OHCI USB 1.1 Contro... | 11    | ohci_pci   | 9ADEB0BD4E |
| 10de:0d9d | 10de:cb89 | Nvidia     | MCP89 EHCI USB 2.0 Contro... | 11    | ehci_pci   | 9ADEB0BD4E |
| 1b21:1142 | 1043:85bf | ASMedia... | ASM1042A USB 3.0 Host Con... | 11    | xhci_hcd   | 79EEA28A8B |
| 10ec:816d | 1043:85b5 | Realtek... | RTL811x EHCI host controller | 10    | ehci_pci   | 79EEA28A8B |
| 8086:15db | 2222:1111 | Intel      | JHL6340 Thunderbolt 3 USB... | 10    | xhci_hcd   | 1761317692 |
| 8086:22b5 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 10    | xhci_pci   | 17889A968C |
| 8086:31a8 | 1043:875e | Intel      | Celeron/Pentium Silver Pr... | 10    | xhci_hcd   | 9D5F2807CE |
| 8086:0f34 | 8086:0f34 | Intel      | Atom Processor Z36xxx/Z37... | 9     | ehci_pci   | DD7BEAC148 |
| 8086:0f35 | 17aa:368d | Intel      | Atom Processor Z36xxx/Z37... | 9     | xhci_pci   | CA54ECE919 |
| 8086:0f37 | 8086:0f37 | Intel      | Atom Processor Z36xxx/Z37... | 9     | dwc3_pci   | 71CEC0648D |
| 1106:3038 | 1106:3038 | VIA Tec... | VT82xx/62xx/VX700/8x0/900... | 8     | uhci_hcd   | 15268C0CCC |
| 1106:3104 | 1106:3104 | VIA Tec... | USB 2.0 EHCI-Compliant Ho... | 8     | ehci_pci   | 15268C0CCC |
| 1b21:1242 | 1b21:1242 | ASMedia... | ASM1142 USB 3.1 Host Cont... | 8     | xhci_hcd   | A080CA6AD4 |
| 8086:15db | 8086:0000 | Intel      | JHL6340 Thunderbolt 3 USB... | 8     | xhci_hcd   | EC7F85C26E |
| 1022:15e0 | 17aa:3130 | AMD        | Raven USB 3.1                | 7     | xhci_hcd   | DBFBDEA28F |
| 1022:15e1 | 17aa:3130 | AMD        | Raven USB 3.1                | 7     | xhci_hcd   | DBFBDEA28F |
| 10ec:816d | 17aa:3130 | Realtek... | RTL811x EHCI host controller | 7     | ehci_pci   | DBFBDEA28F |
| 8086:15ec | 8086:0000 | Intel      | JHL7540 Thunderbolt 3 USB... | 7     | xhci_pci   | D09823163E |
| 8086:31a8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 7     | xhci_hcd   | 2048DCBA92 |
| 8086:a36d | 17aa:3135 | Intel      | Cannon Lake PCH USB 3.1 x... | 7     | xhci_hcd   | B16B2D9BD5 |
| 8086:a36d | 8086:7270 | Intel      | Cannon Lake PCH USB 3.1 x... | 7     | xhci_pci   | D09823163E |
| 1b21:2142 | 1b21:2142 | ASMedia... | ASM2142 USB 3.1 Host Cont... | 6     | xhci_hcd   | CF60BF6309 |
| 8086:0f35 | 17aa:30b5 | Intel      | Atom Processor Z36xxx/Z37... | 6     | xhci_hcd   | 538597F50A |
| 8086:5aa8 | 19da:b325 | Intel      | Celeron N3350/Pentium N42... | 6     | xhci_hcd   | 23BDDBF63A |
| 8086:9d2f | 8086:7270 | Intel      | Sunrise Point-LP USB 3.0 ... | 6     | xhci_hcd   | D391C49614 |
| 1022:7908 | 103c:8158 | AMD        | FCH USB EHCI Controller      | 5     | ehci_hc... | 95BC62EF3F |
| 1022:7914 | 103c:8158 | AMD        | FCH USB XHCI Controller      | 5     | xhci_pci   | 95BC62EF3F |
| 8086:0f35 |           | Intel      | Atom Processor Z36xxx/Z37... | 5     | xhci_hcd   | A27BE7CA62 |
| 8086:9ca6 | 8086:7270 | Intel      | Wildcat Point-LP USB EHCI... | 5     | ehci_pci   | 859A8D53F5 |
| 8086:9cb1 | 8086:7270 | Intel      | Wildcat Point-LP USB xHCI... | 5     | xhci_hcd   | 859A8D53F5 |
| 8086:9ded | 17aa:314d | Intel      | Cannon Point-LP USB 3.1 x... | 5     | xhci_hcd   | 032DB5DB0F |
| 8086:a12f | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 5     | xhci_hcd   | A080CA6AD4 |
| 8086:a36d | 17aa:3136 | Intel      | Cannon Lake PCH USB 3.1 x... | 5     | xhci_hcd   | 6F39F78FAC |
| 1022:15e0 | 17aa:3151 | AMD        | Raven USB 3.1                | 4     | xhci_hcd   | E57DFE6F39 |
| 1022:15e1 | 17aa:3151 | AMD        | Raven USB 3.1                | 4     | xhci_hcd   | E57DFE6F39 |
| 1022:7908 | 17aa:312f | AMD        | FCH USB EHCI Controller      | 4     | ehci_pci   | 5205C41BC5 |
| 1022:7914 | 17aa:312f | AMD        | FCH USB XHCI Controller      | 4     | xhci_hcd   | 5205C41BC5 |
| 1033:0194 | 19da:0194 | NEC Com... | uPD720200 USB 3.0 Host Co... | 4     | xhci_hcd   | 121F403E29 |
| 10ec:816d | 10ec:8168 | Realtek... | RTL811x EHCI host controller | 4     | ehci_pci   | 924D89CD42 |
| 10ec:816d | 17aa:3151 | Realtek... | RTL811x EHCI host controller | 4     | ehci_pci   | E57DFE6F39 |
| 1912:0015 | 19da:0194 | Renesas... | uPD720202 USB 3.0 Host Co... | 4     | xhci_hcd   | 4D23C29B62 |
| 1b6f:7023 | 1b6f:7023 | Etron T... | EJ168 USB 3.0 Host Contro... | 4     | xhci_pci   | 3ACC3E5A05 |
| 8086:0f35 | 19da:b219 | Intel      | Atom Processor Z36xxx/Z37... | 4     | xhci_hcd   | 494AE0914E |
| 8086:15d4 | 8086:2073 | Intel      | JHL6540 Thunderbolt 3 USB... | 4     | xhci_hcd   | D186AF4EE3 |
| 8086:1e26 | 19da:b211 | Intel      | 7 Series/C216 Chipset Fam... | 4     | ehci_hc... | EFBBD0C3F8 |
| 8086:1e2d | 19da:b211 | Intel      | 7 Series/C216 Chipset Fam... | 4     | ehci_hc... | EFBBD0C3F8 |
| 8086:22b5 | 17aa:30dd | Intel      | Atom/Celeron/Pentium Proc... | 4     | xhci_hcd   | 0513ACEC04 |
| 8086:22b5 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 4     | xhci_hcd   | 0D05B404DD |
| 8086:8c26 | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 4     | ehci_pci   | FCAA602427 |
| 8086:8c2d | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 4     | ehci_pci   | FCAA602427 |
| 8086:8c31 | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 4     | xhci_hcd   | FCAA602427 |
| 8086:9a13 |           | Intel      | Tiger Lake-LP Thunderbolt... | 4     | xhci_hcd   | ABC31CEA35 |
| 8086:9a1d | 2222:1111 | Intel      | Tiger Lake-LP Thunderbolt... | 4     | thunder... | ABC31CEA35 |
| 8086:9ca6 | 8086:2058 | Intel      | Wildcat Point-LP USB EHCI... | 4     | ehci_pci   | 6E19619F29 |
| 8086:9cb1 | 8086:2058 | Intel      | Wildcat Point-LP USB xHCI... | 4     | xhci_hcd   | 6E19619F29 |
| 8086:a2af | 103c:82a5 | Intel      | 200 Series/Z370 Chipset F... | 4     | xhci_hcd   | 08B98B6A88 |
| 1002:4396 | 19da:a191 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 3     | ehci_pci   | 121F403E29 |
| 1002:4397 | 19da:a191 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 3     | ohci_pci   | 121F403E29 |
| 1002:4399 | 19da:a191 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 3     | ohci_pci   | 121F403E29 |
| 1022:15e0 | 103c:8836 | AMD        | Raven USB 3.1                | 3     | xhci_pci   | DDEEE57DBD |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816e | 10ec:8168 | Realtek... | RealManage BMC               | 7     |            | 0E48C94F83 |
| 10ec:816e | 17aa:3181 | Realtek... | RealManage BMC               | 1     |            | A203CD8C57 |

