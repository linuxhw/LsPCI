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
   * [ Graphics card ](#graphics-card-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Non-essential instrumentation ](#non-essential-instrumentation-pci)
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
   * [ Usb controller ](#usb-controller-pci)

PCI Devices
-----------

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bluetooth (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1814:3298 | 1a3b:2987 | Ralink     | RT3290 Bluetooth             | 1     |            | 8D13B8BFE3 |

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2280 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 13    | iosf_mb... | 001551B002 |
| 8086:229c | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 13    | lpc_ich    | 001551B002 |
| 8086:22c8 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 13    | shpchp     | 001551B002 |
| 8086:22ca | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 13    | shpchp     | 001551B002 |
| 8086:22cc | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 11    | shpchp     | 001551B002 |
| 8086:5904 | 8086:2068 | Intel      | Xeon E3-1200 v6/7th Gen C... | 11    | skl_uncore | 64913D4FAA |
| 8086:9d10 | 8086:2068 | Intel      | Sunrise Point-LP PCI Expr... | 11    | pcieport   | 64913D4FAA |
| 8086:9d17 | 8086:2068 | Intel      | Sunrise Point-LP PCI Expr... | 11    | pcieport   | 64913D4FAA |
| 8086:9d4e | 8086:2068 | Intel      | Sunrise Point LPC Control... | 11    |            | 64913D4FAA |
| 8086:1604 | 8086:2057 | Intel      | Broadwell-U Host Bridge -OPI | 10    | bdw_uncore | C32D1045F9 |
| 8086:9c90 | 8086:2057 | Intel      | Wildcat Point-LP PCI Expr... | 10    | shpchp     | C32D1045F9 |
| 8086:9cc3 | 8086:2057 | Intel      | Wildcat Point-LP LPC Cont... | 10    | lpc_ich    | C32D1045F9 |
| 8086:1e10 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 9     | shpchp     | D6FE9DA999 |
| 8086:1e12 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 9     | shpchp     | D6FE9DA999 |
| 8086:1e14 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 9     | shpchp     | D6FE9DA999 |
| 8086:1e57 | 8086:7270 | Intel      | HM77 Express Chipset LPC ... | 9     | lpc_ich    | D6FE9DA999 |
| 8086:9c96 | 8086:2057 | Intel      | Wildcat Point-LP PCI Expr... | 9     | pcieport   | C32D1045F9 |
| 8086:9d15 | 8086:2068 | Intel      | Sunrise Point-LP PCI Expr... | 9     | pcieport   | 64913D4FAA |
| 104c:823e |           | Texas I... | XIO2213A/B/XIO2221 PCI Ex... | 8     | shpchp     | 3419AE2627 |
| 8086:1513 |           | Intel      | CV82524 Thunderbolt Contr... | 8     | pcieport   | 3419AE2627 |
| 8086:1547 | 2222:1111 | Intel      | DSL3510 Thunderbolt Contr... | 8     | shpchp     | D6FE9DA999 |
| 8086:9d84 | 8086:2074 | Intel      | Cannon Point-LP LPC Contr... | 8     |            | 23DC7C0455 |
| 8086:9db0 | 8086:2074 | Intel      | Cannon Point-LP PCI Expre... | 8     | pcieport   | 23DC7C0455 |
| 8086:9db6 | 8086:2074 | Intel      | Cannon Point-LP PCI Expre... | 8     | pcieport   | 23DC7C0455 |
| 8086:9db8 | 8086:2074 | Intel      | Cannon Point-LP PCI Expre... | 8     | pcieport   | 23DC7C0455 |
| 8086:9dbc | 8086:2074 | Intel      | Cannon Point-LP PCI Expre... | 8     | pcieport   | 23DC7C0455 |
| 8086:0151 | 106b:00ff | Intel      | Xeon E3-1200 v2/3rd Gen C... | 7     | pcieport   | D6FE9DA999 |
| 8086:0154 | 106b:00ff | Intel      | 3rd Gen Core processor DR... | 7     | ivb_uncore | D6FE9DA999 |
| 8086:1910 | 8086:2064 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 7     | skl_uncore | F68CFBE3F5 |
| 8086:1c10 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 7     | shpchp     | 3419AE2627 |
| 8086:1c12 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 7     | shpchp     | 3419AE2627 |
| 8086:1c14 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 7     | shpchp     | 3419AE2627 |
| 8086:1c49 | 8086:7270 | Intel      | HM65 Express Chipset LPC ... | 7     | lpc_ich    | 3419AE2627 |
| 8086:31d8 | 8086:2072 | Intel      | Gemini Lake PCI Express R... | 7     | pcieport   | 0ED8661BD0 |
| 8086:31da | 8086:2072 | Intel      | Gemini Lake PCI Express R... | 7     | pcieport   | 0ED8661BD0 |
| 8086:31e8 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 7     |            | 0ED8661BD0 |
| 8086:31f0 | 8086:2072 | Intel      | Gemini Lake Host Bridge      | 7     |            | 0ED8661BD0 |
| 8086:3ed0 | 8086:2074 | Intel      | 8th Gen Core Processor Ho... | 7     | skl_uncore | 23DC7C0455 |
| 8086:a110 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 7     | pcieport   | F68CFBE3F5 |
| 8086:a112 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 7     | pcieport   | F68CFBE3F5 |
| 8086:a114 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 7     | pcieport   | F68CFBE3F5 |
| 8086:a14e | 8086:2064 | Intel      | HM170 Chipset LPC/eSPI Co... | 7     |            | F68CFBE3F5 |
| 8086:a111 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 6     | pcieport   | F68CFBE3F5 |
| 104c:823e | 0000:0000 | Texas I... | XIO2213A/B/XIO2221 PCI Ex... | 5     | shpchp     | 4D008C616B |
| 8086:0a04 | 106b:0141 | Intel      | Haswell-ULT DRAM Controller  | 5     | hsw_uncore | BC577C8669 |
| 8086:156d |           | Intel      | DSL5520 Thunderbolt 2 Bri... | 5     | shpchp     | BC577C8669 |
| 8086:5af0 |           | Intel      | Celeron N3350/Pentium N42... | 5     |            | C7F97B95C4 |
| 8086:9c10 | 8086:7270 | Intel      | 8 Series PCI Express Root... | 5     | shpchp     | BC577C8669 |
| 8086:9c14 | 8086:7270 | Intel      | 8 Series PCI Express Root... | 5     | shpchp     | BC577C8669 |
| 8086:9c16 | 8086:7270 | Intel      | 8 Series PCI Express Root... | 5     | shpchp     | BC577C8669 |
| 8086:9c18 | 8086:7270 | Intel      | 8 Series PCI Express Root... | 5     | shpchp     | BC577C8669 |
| 8086:9c43 | 8086:7270 | Intel      | 8 Series LPC Controller      | 5     | lpc_ich    | BC577C8669 |
| 10de:0a82 |           | Nvidia     | MCP79 Host Bridge            | 4     |            | 191BB34391 |
| 10de:0aa0 | 10de:0000 | Nvidia     | MCP79 PCI Express Bridge     | 4     | shpchp     | 191BB34391 |
| 10de:0aab | 10de:cb79 | Nvidia     | MCP79 PCI Bridge             | 4     |            | 191BB34391 |
| 10de:0aae | 10de:cb79 | Nvidia     | MCP79 LPC Bridge             | 4     |            | 191BB34391 |
| 10de:0ac6 | 10de:0000 | Nvidia     | MCP79 PCI Express Bridge     | 4     | shpchp     | 191BB34391 |
| 10de:0ac7 | 10de:0000 | Nvidia     | MCP79 PCI Express Bridge     | 4     | shpchp     | 191BB34391 |
| 8086:1901 | 8086:2073 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 4     | pcieport   | 0E16D3F886 |
| 8086:1905 | 8086:2073 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 4     | pcieport   | 0E16D3F886 |
| 8086:1909 | 8086:2073 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 4     | pcieport   | 0E16D3F886 |
| 8086:5910 | 8086:2073 | Intel      | Xeon E3-1200 v6/7th Gen C... | 4     |            | 0E16D3F886 |
| 8086:5ad8 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 4     | shpchp     | C7F97B95C4 |
| 8086:5ad9 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 4     | shpchp     | C7F97B95C4 |
| 8086:5ada | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 4     | shpchp     | C7F97B95C4 |
| 8086:5ae8 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 4     | lpc_ich    | C7F97B95C4 |
| 8086:a110 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 4     | pcieport   | 0E16D3F886 |
| 8086:a114 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 4     | pcieport   | 0E16D3F886 |
| 8086:a152 | 8086:2073 | Intel      | HM175 Chipset LPC/eSPI Co... | 4     |            | 0E16D3F886 |
| 8086:0101 | 106b:00e6 | Intel      | Xeon E3-1200/2nd Generati... | 3     | pcieport   | 3419AE2627 |
| 8086:0101 | 106b:00f0 | Intel      | Xeon E3-1200/2nd Generati... | 3     | shpchp     | 9898EDBAF1 |
| 8086:0104 | 106b:00e6 | Intel      | 2nd Generation Core Proce... | 3     |            | 3419AE2627 |
| 8086:0104 | 106b:00f0 | Intel      | 2nd Generation Core Proce... | 3     |            | 9898EDBAF1 |
| 8086:0105 | 106b:00e6 | Intel      | Xeon E3-1200/2nd Generati... | 3     | pcieport   | 3419AE2627 |
| 8086:0105 | 106b:00f0 | Intel      | Xeon E3-1200/2nd Generati... | 3     | shpchp     | 9898EDBAF1 |
| 8086:156d | 0000:0000 | Intel      | DSL5520 Thunderbolt 2 Bri... | 3     | shpchp     | 0DD740DC8F |
| 8086:1904 | 8086:2063 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | skl_uncore | 97355011D7 |
| 8086:2448 |           | Intel      | 82801 Mobile PCI Bridge      | 3     |            | E78329BE05 |
| 8086:27a0 | 8086:7270 | Intel      | Mobile 945GM/PM/GMS, 943/... | 3     |            | E78329BE05 |
| 8086:27b9 | 8086:7270 | Intel      | 82801GBM (ICH7-M) LPC Int... | 3     | lpc_ich    | E78329BE05 |
| 8086:27d0 |           | Intel      | NM10/ICH7 Family PCI Expr... | 3     | pcieport   | E78329BE05 |
| 8086:27d2 |           | Intel      | NM10/ICH7 Family PCI Expr... | 3     | pcieport   | E78329BE05 |
| 8086:9d14 | 8086:2063 | Intel      | Sunrise Point-LP PCI Expr... | 3     | shpchp     | 97355011D7 |
| 8086:9d48 | 8086:2063 | Intel      | Sunrise Point-LP LPC Cont... | 3     |            | 97355011D7 |
| 8086:a111 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 3     | pcieport   | 0E8E75B0EB |
| 8086:a112 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 3     | pcieport   | 0E8E75B0EB |
| 8086:a118 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 3     | pcieport   | 0E16D3F886 |
| 1022:1510 | 1022:1510 | AMD        | Family 14h Processor Root... | 2     |            | 8D13B8BFE3 |
| 1022:1512 | 1022:1234 | AMD        | Family 14h Processor Root... | 2     | shpchp     | 8D13B8BFE3 |
| 1022:1700 |           | AMD        | Family 12h/14h Processor ... | 2     |            | 8D13B8BFE3 |
| 1022:1701 |           | AMD        | Family 12h/14h Processor ... | 2     |            | 8D13B8BFE3 |
| 1022:1702 |           | AMD        | Family 12h/14h Processor ... | 2     |            | 8D13B8BFE3 |
| 1022:1703 |           | AMD        | Family 12h/14h Processor ... | 2     | k10temp    | 8D13B8BFE3 |
| 1022:1704 |           | AMD        | Family 12h/14h Processor ... | 2     |            | 8D13B8BFE3 |
| 1022:1716 |           | AMD        | Family 12h/14h Processor ... | 2     |            | 8D13B8BFE3 |
| 1022:1718 |           | AMD        | Family 12h/14h Processor ... | 2     |            | 8D13B8BFE3 |
| 1022:1719 |           | AMD        | Family 12h/14h Processor ... | 2     |            | 8D13B8BFE3 |
| 8086:0151 | 106b:0101 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 2     | shpchp     | BD87D7D9AA |
| 8086:0154 | 106b:0101 | Intel      | 3rd Gen Core processor DR... | 2     | ivb_uncore | BD87D7D9AA |
| 8086:0bf3 |           | Intel      | Atom Processor D2xxx/N2xx... | 2     |            | 30F524BC82 |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:5229 | 8086:2068 | Realtek... | RTS5229 PCI Express Card ... | 11    | rtsx_pci   | 64913D4FAA |
| 10ec:522a | 8086:2074 | Realtek... | RTS522A PCI Express Card ... | 8     | rtsx_pci   | 23DC7C0455 |
| 10ec:5229 | 8086:2072 | Realtek... | RTS5229 PCI Express Card ... | 7     | rtsx_pci   | 0ED8661BD0 |
| 10ec:5229 | 8086:2067 | Realtek... | RTS5229 PCI Express Card ... | 4     | rtsx_pci   | C7F97B95C4 |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0aa3 | 10de:cb79 | Nvidia     | MCP79 Co-processor           | 4     | nvidia     | 191BB34391 |
| 10de:0d7a | 10de:cb89 | Nvidia     | MCP89 Co-Processor           | 1     |            | C2DA8438C2 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d3a | 8086:2068 | Intel      | Sunrise Point-LP CSME HEC... | 11    | mei_me     | 64913D4FAA |
| 8086:9cba | 8086:2057 | Intel      | Wildcat Point-LP MEI Cont... | 10    | mei_me     | C32D1045F9 |
| 8086:1e3a | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 9     | mei_me     | D6FE9DA999 |
| 8086:9de0 | 8086:2074 | Intel      | Cannon Point-LP MEI Contr... | 8     | mei_me     | 23DC7C0455 |
| 8086:1c3a | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 7     | mei_me     | 3419AE2627 |
| 8086:319a | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 7     | mei_me     | 0ED8661BD0 |
| 8086:a13a | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 7     | mei_me     | F68CFBE3F5 |
| 8086:5a9a |           | Intel      | Celeron N3350/Pentium N42... | 5     | mei_me     | C7F97B95C4 |
| 8086:9c3a | 8086:7270 | Intel      | 8 Series HECI #0             | 5     | mei_me     | BC577C8669 |
| 8086:a13a | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 4     | mei_me     | 0E16D3F886 |
| 8086:9d3a | 8086:2063 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | 97355011D7 |
| 8086:9d3a | 8086:2070 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | F1331B62E6 |
| 8086:a13a | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 2     | mei_me     | 2CBDC3AD17 |
| 8086:a13a | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 2     | mei_me     | 4C9A2AA59C |
| 8086:a2ba | 103c:82a5 | Intel      | 200 Series PCH CSME HECI #1  | 2     | mei_me     | 9D7BDB2727 |
| 8086:1c3a | 1734:11ba | Intel      | 6 Series/C200 Series Chip... | 1     | mei_me     | FC67594808 |
| 8086:1c3a | 19da:b202 | Intel      | 6 Series/C200 Series Chip... | 1     | mei_me     | F8F1E1681B |
| 8086:1e3a | 19da:a247 | Intel      | 7 Series/C216 Chipset Fam... | 1     | mei_me     | 3486F30CEE |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | mei_me     | 69BB2EE752 |
| 8086:8c3a | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 1     | mei_me     | 4E3E10AE15 |
| 8086:9c3a | 1458:5001 | Intel      | 8 Series HECI #0             | 1     | mei_me     | B590007CCF |
| 8086:9cba | 8086:2058 | Intel      | Wildcat Point-LP MEI Cont... | 1     | mei_me     | 4AB80B03C5 |
| 8086:a13a | 8086:1999 | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | 305342DF08 |

### Dma controller (eisa dma) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22c0 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 9     | dw_dmac... | 27537B5C01 |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2298 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 13    | mei_txe    | 001551B002 |
| 8086:2298 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | F6DDC974E1 |
| 8086:0f18 | 8086:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | F339ADE022 |
| 8086:2298 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | BD1F4F70F7 |
| 8086:2298 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | 6157F936DB |
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | 5C7849A72A |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 11c1:5901 | 11c1:5900 | LSI        | FW643 [TrueFire] PCIe 139... | 14    | firewir... | D6FE9DA999 |
| 104c:823f |           | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 8     | firewir... | 3419AE2627 |
| 11c1:5811 | 11c1:5811 | LSI        | FW322/323 [TrueFire] 1394... | 3     | firewir... | E78329BE05 |
| 11c1:5901 | c111:0159 | LSI        | FW643 [TrueFire] PCIe 139... | 1     | firewir... | 029708EAF4 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b1 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 13    | i915       | 001551B002 |
| 8086:3ea5 | 8086:2074 | Intel      | Iris Plus Graphics 655       | 8     | i915       | 23DC7C0455 |
| 8086:0166 | 106b:00ff | Intel      | 3rd Gen Core processor Gr... | 7     | i915       | D6FE9DA999 |
| 8086:193b | 8086:2064 | Intel      | Iris Pro Graphics 580        | 7     | i915       | F68CFBE3F5 |
| 8086:3185 | 8086:2072 | Intel      | UHD Graphics 605             | 6     | i915       | 0ED8661BD0 |
| 8086:5916 | 8086:2068 | Intel      | HD Graphics 620              | 6     | i915       | 34358089CA |
| 8086:1616 | 8086:2057 | Intel      | HD Graphics 5500             | 5     | i915       | 078CF691FD |
| 1002:694c | 8086:2073 | AMD        | Polaris 22 XT [Radeon RX ... | 4     | amdgpu     | 0E16D3F886 |
| 10de:0861 | 106b:00ae | Nvidia     | C79 [GeForce 9400]           | 4     | nouveau    | 191BB34391 |
| 8086:1626 | 8086:2057 | Intel      | HD Graphics 6000             | 4     | i915       | C32D1045F9 |
| 8086:5927 | 8086:2068 | Intel      | Iris Plus Graphics 650       | 4     | i915       | 64913D4FAA |
| 8086:5a85 | 8086:2067 | Intel      | HD Graphics                  | 4     | i915       | C7F97B95C4 |
| 1002:6741 | 106b:00e8 | AMD        | Whistler [Radeon HD 6630M... | 3     | radeon     | 9898EDBAF1 |
| 8086:0126 | 106b:00e6 | Intel      | 2nd Generation Core Proce... | 3     | i915       | 3419AE2627 |
| 8086:0a26 | 106b:0141 | Intel      | Haswell-ULT Integrated Gr... | 3     | i915       | 42A2D2DC72 |
| 8086:1926 | 8086:2063 | Intel      | Iris Graphics 540            | 3     | i915       | 97355011D7 |
| 8086:27a2 | 8086:7270 | Intel      | Mobile 945GM/GMS, 943/940... | 3     | i915       | E78329BE05 |
| 10de:1050 | 19da:2180 | Nvidia     | GF119M [GeForce GT 520M]     | 2     | nouveau    | 30F524BC82 |
| 10de:13b4 | 103c:82c0 | Nvidia     | GM107GLM [Quadro M620 Mob... | 2     | nvidia     | 2CBDC3AD17 |
| 10de:1c20 | 19da:2413 | Nvidia     | GP106M [GeForce GTX 1060 ... | 2     | nouveau    | 4C9A2AA59C |
| 8086:0166 | 106b:0101 | Intel      | 3rd Gen Core processor Gr... | 2     | i915       | BD87D7D9AA |
| 8086:0a2e | 106b:0141 | Intel      | Haswell-ULT Integrated Gr... | 2     | i915       | BC577C8669 |
| 8086:22b1 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 2     | i915       | F6DDC974E1 |
| 8086:5917 | 8086:2070 | Intel      | UHD Graphics 620             | 2     | i915       | F1331B62E6 |
| 8086:591b | 8086:2073 | Intel      | HD Graphics 630              | 2     | i915       | 0E16D3F886 |
| 1002:9802 | 19da:a183 | AMD        | Wrestler [Radeon HD 6310]    | 1     | radeon     | 037A3E45C7 |
| 1002:9808 | 19da:a261 | AMD        | Wrestler [Radeon HD 7340]    | 1     | radeon     | 8D13B8BFE3 |
| 10de:08a4 | 106b:00c0 | Nvidia     | MCP89 [GeForce 320M]         | 1     | nouveau    | C2DA8438C2 |
| 8086:0116 | 106b:00e7 | Intel      | 2nd Generation Core Proce... | 1     | i915       | 4D008C616B |
| 8086:0152 | 1734:11d7 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 1     | i915       | FC67594808 |
| 8086:0156 | 19da:2111 | Intel      | 3rd Gen Core processor Gr... | 1     | i915       | 3486F30CEE |
| 8086:0162 | 19da:b202 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 1     | i915       | F8F1E1681B |
| 8086:0412 | 19da:b220 | Intel      | Xeon E3-1200 v3/4th Gen C... | 1     | i915       | 4E3E10AE15 |
| 8086:0a16 | 1458:d000 | Intel      | Haswell-ULT Integrated Gr... | 1     | i915       | B590007CCF |
| 8086:0f31 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 1     | i915       | F339ADE022 |
| 8086:1616 | 8086:2058 | Intel      | HD Graphics 5500             | 1     | i915       | 4AB80B03C5 |
| 8086:162b | 8086:2057 | Intel      | Iris Graphics 6100           | 1     | i915       | 44CAA27AAD |
| 8086:1912 | 103c:82a5 | Intel      | HD Graphics 530              | 1     | i915       | 2350EA995C |
| 8086:1912 | 8086:0000 | Intel      | HD Graphics 530              | 1     | i915       | 305342DF08 |
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | i915       | 5C7849A72A |
| 8086:22b1 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 1     | i915       | BD1F4F70F7 |
| 8086:22b1 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | i915       | 6157F936DB |
| 8086:27a6 | 8086:7270 | Intel      | Mobile 945GM/GMS/GME, 943... | 1     |            | 5A02AA7966 |
| 8086:3184 | 8086:2072 | Intel      | UHD Graphics 605             | 1     | i915       | 94F2AA43B7 |
| 8086:5902 | 103c:82a5 | Intel      | HD Graphics 610              | 1     | i915       | 9D7BDB2727 |
| 8086:5926 | 8086:2068 | Intel      | Iris Plus Graphics 640       | 1     | i915       | A48C087C97 |
| 8086:5a85 | 19da:b325 | Intel      | HD Graphics                  | 1     | i915       | C08536440A |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics                  | 1     | i915       | 69BB2EE752 |
| 8086:a001 | 8086:4f4d | Intel      | Atom Processor D4xx/D5xx/... | 1     | i915       | FD127FD8BF |
| 8086:a001 | 8086:574d | Intel      | Atom Processor D4xx/D5xx/... | 1     | i915       | 4727851853 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d21 | 8086:2068 | Intel      | Sunrise Point-LP PMC         | 11    |            | 64913D4FAA |
| 8086:9def | 8086:2074 | Intel      | Cannon Point-LP Shared SRAM  | 8     |            | 23DC7C0455 |
| 8086:a121 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 7     |            | F68CFBE3F5 |
| 10de:0a88 |           | Nvidia     | MCP79 Memory Controller      | 4     |            | 191BB34391 |
| 10de:0a89 |           | Nvidia     | MCP79 Memory Controller      | 4     |            | 191BB34391 |
| 10de:0a98 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 4     |            | 191BB34391 |
| 10de:0aa4 |           | Nvidia     | MCP79 Memory Controller      | 4     |            | 191BB34391 |
| 8086:a121 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 4     |            | 0E16D3F886 |
| 8086:9d21 | 8086:2063 | Intel      | Sunrise Point-LP PMC         | 3     |            | 97355011D7 |
| 8086:9d21 | 8086:2070 | Intel      | Sunrise Point-LP PMC         | 2     |            | F1331B62E6 |
| 8086:a121 | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 2CBDC3AD17 |
| 8086:a121 | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 4C9A2AA59C |
| 8086:a2a1 | 103c:82a5 | Intel      | 200 Series/Z370 Chipset F... | 2     |            | 9D7BDB2727 |
| 10de:0d68 |           | Nvidia     | MCP89 Memory Controller      | 1     |            | C2DA8438C2 |
| 10de:0d69 |           | Nvidia     | MCP89 Memory Controller      | 1     |            | C2DA8438C2 |
| 10de:0d6d |           | Nvidia     | MCP89 Memory Controller      | 1     |            | C2DA8438C2 |
| 10de:0d6e |           | Nvidia     | MCP89 Memory Controller      | 1     |            | C2DA8438C2 |
| 10de:0d6f |           | Nvidia     | MCP89 Memory Controller      | 1     |            | C2DA8438C2 |
| 10de:0d70 |           | Nvidia     | MCP89 Memory Controller      | 1     |            | C2DA8438C2 |
| 10de:0d71 |           | Nvidia     | MCP89 Memory Controller      | 1     |            | C2DA8438C2 |
| 10de:0d72 |           | Nvidia     | MCP89 Memory Controller      | 1     |            | C2DA8438C2 |
| 10de:0d75 |           | Nvidia     | MCP89 Memory Controller      | 1     |            | C2DA8438C2 |
| 10de:0d7b |           | Nvidia     | MCP89 Memory Controller      | 1     |            | C2DA8438C2 |
| 8086:a121 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 305342DF08 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:1686 | 14e4:1686 | Broadco... | NetXtreme BCM57766 Gigabi... | 14    | tg3        | BC577C8669 |
| 10ec:8168 | 8086:2060 | Realtek... | RTL8111/8168/8411 PCI Exp... | 11    | r8169      | 001551B002 |
| 8086:15d8 | 8086:2068 | Intel      | Ethernet Connection (4) I... | 11    | e1000e     | 64913D4FAA |
| 8086:15a3 | 8086:2057 | Intel      | Ethernet Connection (3) I... | 10    | e1000e     | C32D1045F9 |
| 10ec:8168 | 19da:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 8     | r8169      | 4C9A2AA59C |
| 14e4:16b4 | 14e4:16b4 | Broadco... | NetXtreme BCM57765 Gigabi... | 8     | tg3        | 3419AE2627 |
| 8086:15be | 8086:2074 | Intel      | Ethernet Connection (6) I... | 8     | e1000e     | 23DC7C0455 |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 7     | r8169      | 5C7849A72A |
| 10ec:8168 | 8086:2072 | Realtek... | RTL8111/8168/8411 PCI Exp... | 7     | r8169      | 0ED8661BD0 |
| 8086:15b7 | 8086:2064 | Intel      | Ethernet Connection (2) I... | 7     | e1000e     | F68CFBE3F5 |
| 10de:0ab0 | 10de:cb79 | Nvidia     | MCP79 Ethernet               | 4     | forcedeth  | 191BB34391 |
| 8086:15b7 | 8086:0000 | Intel      | Ethernet Connection (2) I... | 4     | e1000e     | 0E16D3F886 |
| 10ec:8168 | 8086:2067 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | C7F97B95C4 |
| 11ab:4362 | 11ab:5321 | Marvell... | 88E8053 PCI-E Gigabit Eth... | 3     | sky2       | E78329BE05 |
| 8086:1570 | 8086:2063 | Intel      | Ethernet Connection I219-V   | 3     | e1000e     | 97355011D7 |
| 10ec:8168 | 103c:82a5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 9D7BDB2727 |
| 10ec:8168 | 1462:b120 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | F6DDC974E1 |
| 8086:156f | 8086:2070 | Intel      | Ethernet Connection I219-LM  | 2     | e1000e     | F1331B62E6 |
| 8086:15b7 | 103c:82c0 | Intel      | Ethernet Connection (2) I... | 2     | e1000e     | 2CBDC3AD17 |
| 10ec:8136 | 8086:0001 | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | FD127FD8BF |
| 10ec:8168 | 1458:e000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | B590007CCF |
| 10ec:8168 | 8086:d625 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 4727851853 |
| 14e4:16b0 | 106b:00f1 | Broadcom   | NetXtreme BCM57761 Gigabi... | 1     | tg3        | 029708EAF4 |
| 8086:15a2 | 8086:2058 | Intel      | Ethernet Connection (3) I... | 1     | e1000e     | 4AB80B03C5 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 16    | iwlwifi    | 4C9A2AA59C |
| 8086:24f3 | 8086:9010 | Intel      | Wireless 8260                | 10    | iwlwifi    | F68CFBE3F5 |
| 14e4:4331 | 106b:010e | Broadco... | BCM4331 802.11a/b/g/n        | 9     | wl         | D6FE9DA999 |
| 8086:095a | 8086:9010 | Intel      | Wireless 7265                | 9     | iwlwifi    | C32D1045F9 |
| 8086:24fd | 8086:9010 | Intel      | Wireless 8265 / 8275         | 9     | iwlwifi    | 64913D4FAA |
| 8086:9df0 | 8086:0034 | Intel      | Cannon Point-LP CNVi [Wir... | 8     | iwlwifi    | 23DC7C0455 |
| 8086:31dc | 8086:02a4 | Intel      | Wireless-AC 1550i Wireles... | 7     | iwlwifi    | 0ED8661BD0 |
| 14e4:4331 | 106b:00e4 | Broadco... | BCM4331 802.11a/b/g/n        | 6     | wl         | 3419AE2627 |
| 14e4:43a0 | 106b:013b | Broadco... | BCM4360 802.11ac Wireless... | 5     | wl         | BC577C8669 |
| 14e4:4328 | 106b:0090 | Broadco... | BCM4321 802.11a/b/g/n        | 4     | ssb        | 191BB34391 |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 4     | iwlwifi    | C7F97B95C4 |
| 168c:001c | 106b:0086 | Qualcom... | AR242x / AR542x Wireless ... | 3     | ath5k      | E78329BE05 |
| 8086:08b3 | 8086:0070 | Intel      | Wireless 3160                | 2     | iwlwifi    | 3486F30CEE |
| 8086:08b3 | 8086:8070 | Intel      | Wireless 3160                | 2     | iwlwifi    | 6157F936DB |
| 10ec:8179 | 1a3b:219a | Realtek... | RTL8188EE Wireless Networ... | 1     | rtl8188ee  | F6DDC974E1 |
| 10ec:8723 | 1a3b:2114 | Realtek... | RTL8723AE PCIe Wireless N... | 1     | rtl8723ae  | B590007CCF |
| 14e4:4353 | 106b:0093 | Broadco... | BCM43224 802.11a/b/g/n       | 1     | wl         | C2DA8438C2 |
| 1814:0781 | 1a3b:1059 | Ralink     | RT2790 Wireless 802.11n 1... | 1     | rt2800pci  | 037A3E45C7 |
| 1814:3290 | 1a3b:2b87 | Ralink     | RT3290 Wireless 802.11n 1... | 1     | rt2800pci  | 8D13B8BFE3 |
| 8086:0892 | 8086:0062 | Intel      | Centrino Wireless-N 135      | 1     | iwlwifi    | F8F1E1681B |
| 8086:0896 | 8086:5005 | Intel      | Centrino Wireless-N 130      | 1     | iwlwifi    | E907BA80AE |
| 8086:08b1 | 8086:4060 | Intel      | Wireless 7260                | 1     | iwlwifi    | 30F524BC82 |
| 8086:24f3 | 8086:0130 | Intel      | Wireless 8260                | 1     | iwlwifi    | EDB53070CD |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 1     | iwlwifi    | 242161EFFC |
| 8086:3165 | 8086:8010 | Intel      | Wireless 3165                | 1     | iwlwifi    | 69BB2EE752 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:4331 | 14e4:4331 | Broadco... | BCM4331 802.11a/b/g/n        | 5     | wl         | 3419AE2627 |
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 4     | iwlwifi    | F1331B62E6 |
| 8086:157b | 8086:0000 | Intel      | I210 Gigabit Network Conn... | 3     | igb        | 0E8E75B0EB |
| 8086:1503 | 1734:11d9 | Intel      | 82579V Gigabit Network Co... | 1     | e1000e     | FC67594808 |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a126 |           | Intel      | 100 Series/C230 Series Ch... | 1     | intel_t... | C263278BF1 |

### Performance counters (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27a3 |           | Intel      | 945GM/GU Chipset Hardware... | 3     |            | E78329BE05 |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:16bc | 14e4:0000 | Broadco... | BCM57765/57785 SDXC/MMC C... | 22    | sdhci_pci  | BC577C8669 |
| 8086:2296 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 9     | sdhci_pci  | 27537B5C01 |
| 8086:31cc | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 7     | sdhci_pci  | 0ED8661BD0 |
| 1217:8621 | 8086:2064 | O2 Micro   | SD/MMC Card Reader Contro... | 6     | sdhci_pci  | F68CFBE3F5 |
| 1217:8621 | 8086:2073 | O2 Micro   | SD/MMC Card Reader Contro... | 4     | sdhci_pci  | 0E16D3F886 |
| 8086:9d2d | 8086:2063 | Intel      | Sunrise Point-LP Secure D... | 3     | sdhci_pci  | 97355011D7 |
| 8086:2294 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 2     | sdhci_pci  | F6DDC974E1 |
| 8086:2294 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 2     | sdhci_pci  | 27537B5C01 |
| 1022:7806 | 19da:a261 | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | 8D13B8BFE3 |
| 8086:2294 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 1     | sdhci_pci  | BD1F4F70F7 |
| 8086:5acc | 19da:b325 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | C08536440A |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 69BB2EE752 |
| 8086:5ad0 |           | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | C08536440A |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22c6 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 9     | i2c_des... | 27537B5C01 |
| 8086:22c7 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 9     | i2c_des... | 27537B5C01 |
| 8086:9da4 | 8086:2074 | Intel      | Cannon Point-LP SPI Contr... | 8     |            | 23DC7C0455 |
| 8086:5ac8 |           | Intel      | Celeron N3350/Pentium N42... | 3     | pwm_lps... | C7F97B95C4 |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d3d | 8086:2070 | Intel      | Sunrise Point-LP Active M... | 2     | serial     | F1331B62E6 |
| 8086:a13d | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 2     | serial     | 2CBDC3AD17 |
| 8086:9cbd | 8086:2058 | Intel      | Wildcat Point-LP KT Contr... | 1     | serial     | 4AB80B03C5 |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d31 | 8086:2068 | Intel      | Sunrise Point-LP Thermal ... | 11    | intel_p... | 64913D4FAA |
| 8086:9df9 | 8086:2074 | Intel      | Cannon Point-LP Thermal C... | 8     | intel_p... | 23DC7C0455 |
| 8086:a131 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 7     | intel_p... | F68CFBE3F5 |
| 8086:5aac | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | C7F97B95C4 |
| 8086:5abc |           | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | C7F97B95C4 |
| 8086:5ac2 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | C7F97B95C4 |
| 8086:5ac4 |           | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | C7F97B95C4 |
| 8086:5ac6 |           | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | C7F97B95C4 |
| 8086:a127 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_l... | 0E16D3F886 |
| 8086:a131 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_p... | 0E16D3F886 |
| 8086:a160 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_l... | 0E16D3F886 |
| 8086:a161 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_l... | 0E16D3F886 |
| 8086:a162 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_l... | 0E16D3F886 |
| 8086:9d27 | 8086:2063 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 97355011D7 |
| 8086:9d31 | 8086:2063 | Intel      | Sunrise Point-LP Thermal ... | 3     | intel_p... | 97355011D7 |
| 8086:9d31 | 8086:2070 | Intel      | Sunrise Point-LP Thermal ... | 2     | intel_p... | F1331B62E6 |
| 8086:9d60 | 8086:2070 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_lpss | F1331B62E6 |
| 8086:9d61 | 8086:2070 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_lpss | F1331B62E6 |
| 8086:a131 | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_p... | 2CBDC3AD17 |
| 8086:a131 | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_p... | 4C9A2AA59C |
| 8086:a2b1 | 103c:82a5 | Intel      | 200 Series PCH Thermal Su... | 2     |            | 9D7BDB2727 |
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | proc_th... | 5C7849A72A |
| 8086:5a8c |           | Intel      | Dynamic Platform and Ther... | 1     | process... | 69BB2EE752 |
| 8086:a131 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | 305342DF08 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2292 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 13    | i2c_i801   | 001551B002 |
| 8086:9d23 | 8086:2068 | Intel      | Sunrise Point-LP SMBus       | 11    | i2c_i801   | 64913D4FAA |
| 8086:9ca2 | 8086:2057 | Intel      | Wildcat Point-LP SMBus Co... | 10    | i2c_i801   | C32D1045F9 |
| 8086:1e22 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 9     | i2c_i801   | D6FE9DA999 |
| 8086:9da3 | 8086:2074 | Intel      | Cannon Point-LP SMBus Con... | 8     | i2c_i801   | 23DC7C0455 |
| 8086:1c22 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 7     | i2c_i801   | 3419AE2627 |
| 8086:31d4 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 7     | i2c_i801   | 0ED8661BD0 |
| 8086:a123 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 7     | i801_smbus | F68CFBE3F5 |
| 8086:9c22 | 8086:7270 | Intel      | 8 Series SMBus Controller    | 5     | i2c_i801   | BC577C8669 |
| 10de:0aa2 | 10de:cb79 | Nvidia     | MCP79 SMBus                  | 4     | i2c_nfo... | 191BB34391 |
| 8086:5ad4 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 4     | i2c_i801   | C7F97B95C4 |
| 8086:a123 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 4     | i2c_i801   | 0E16D3F886 |
| 8086:27da | 8086:7270 | Intel      | NM10/ICH7 Family SMBus Co... | 3     | i2c_i801   | E78329BE05 |
| 8086:9d23 | 8086:2063 | Intel      | Sunrise Point-LP SMBus       | 3     | i2c_i801   | 97355011D7 |
| 8086:2292 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 2     | i2c_i801   | F6DDC974E1 |
| 8086:27da | 19da:a218 | Intel      | NM10/ICH7 Family SMBus Co... | 2     | i2c_i801   | 30F524BC82 |
| 8086:9d23 | 8086:2070 | Intel      | Sunrise Point-LP SMBus       | 2     |            | F1331B62E6 |
| 8086:a123 | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 2     | i2c_i801   | 2CBDC3AD17 |
| 8086:a123 | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 2     | i2c_i801   | 4C9A2AA59C |
| 8086:a2a3 | 103c:82a5 | Intel      | 200 Series/Z370 Chipset F... | 2     | i2c_i801   | 9D7BDB2727 |
| 1002:4385 | 19da:a183 | AMD        | SBx00 SMBus Controller       | 1     | i2c_pii... | 037A3E45C7 |
| 1022:780b | 19da:a261 | AMD        | FCH SMBus Controller         | 1     | i2c_pii... | 8D13B8BFE3 |
| 10de:0d79 | 10de:cb89 | Nvidia     | MCP89 SMBus                  | 1     |            | C2DA8438C2 |
| 8086:1c22 | 1734:11ba | Intel      | 6 Series/C200 Series Chip... | 1     |            | FC67594808 |
| 8086:1c22 | 19da:b202 | Intel      | 6 Series/C200 Series Chip... | 1     | i2c_i801   | F8F1E1681B |
| 8086:1e22 | 19da:a247 | Intel      | 7 Series/C216 Chipset Fam... | 1     | i2c_i801   | 3486F30CEE |
| 8086:2292 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 1     | i2c_i801   | BD1F4F70F7 |
| 8086:2292 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 6157F936DB |
| 8086:27da | 8086:4f4d | Intel      | NM10/ICH7 Family SMBus Co... | 1     | i2c_i801   | FD127FD8BF |
| 8086:27da | 8086:574d | Intel      | NM10/ICH7 Family SMBus Co... | 1     | i2c_i801   | 4727851853 |
| 8086:5ad4 | 19da:b325 | Intel      | Celeron N3350/Pentium N42... | 1     | i2c_i801   | C08536440A |
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     |            | 69BB2EE752 |
| 8086:8c22 | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 1     | i2c_i801   | 4E3E10AE15 |
| 8086:9c22 | 1458:5001 | Intel      | 8 Series SMBus Controller    | 1     | i2c_i801   | B590007CCF |
| 8086:9ca2 | 8086:2058 | Intel      | Wildcat Point-LP SMBus Co... | 1     | i2c_i801   | 4AB80B03C5 |
| 8086:a123 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     | i2c_i801   | 305342DF08 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2284 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 13    | snd_hda... | 001551B002 |
| 8086:160c | 8086:2057 | Intel      | Broadwell-U Audio Controller | 10    | snd_hda... | C32D1045F9 |
| 8086:9ca0 | 8086:2057 | Intel      | Wildcat Point-LP High Def... | 10    | snd_hda... | C32D1045F9 |
| 8086:9d71 | 8086:2068 | Intel      | Sunrise Point-LP HD Audio    | 10    | snd_hda... | 64913D4FAA |
| 8086:1e20 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 9     | snd_hda... | D6FE9DA999 |
| 8086:9dc8 | 8086:2074 | Intel      | Cannon Point-LP High Defi... | 8     | snd_hda... | 23DC7C0455 |
| 8086:1c20 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 7     | snd_hda... | 3419AE2627 |
| 8086:3198 | 8086:2072 | Intel      | Smart Sound Technology (I... | 7     | snd_hda... | 0ED8661BD0 |
| 8086:a170 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 7     | snd_hda... | F68CFBE3F5 |
| 8086:0a0c | 106b:0141 | Intel      | Haswell-ULT HD Audio Cont... | 5     | snd_hda... | BC577C8669 |
| 8086:9c20 | 8086:7270 | Intel      | 8 Series HD Audio Controller | 5     | snd_hda... | BC577C8669 |
| 10de:0ac0 | 10de:cb79 | Nvidia     | MCP79 High Definition Audio  | 4     | snd_hda... | 191BB34391 |
| 8086:5a98 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 4     | snd_hda... | C7F97B95C4 |
| 8086:a171 | 8086:2073 | Intel      | CM238 HD Audio Controller    | 4     | snd_hda... | 0E16D3F886 |
| 1002:aa90 | 0000:aa90 | AMD        | Turks HDMI Audio [Radeon ... | 3     | snd_hda... | 9898EDBAF1 |
| 1002:ab08 | 8086:2073 | AMD        | Polaris 22 HDMI Audio        | 3     | snd_hda... | 0E8E75B0EB |
| 8086:27d8 | 8384:7680 | Intel      | NM10/ICH7 Family High Def... | 3     | snd_hda... | E78329BE05 |
| 8086:9d70 | 8086:2063 | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | 97355011D7 |
| 10de:0e08 | 19da:2180 | Nvidia     | GF119 HDMI Audio Controller  | 2     | snd_hda... | 30F524BC82 |
| 10de:0fbc | 103c:82c0 | Nvidia     | GM107 High Definition Aud... | 2     | snd_hda... | 2CBDC3AD17 |
| 10de:10f1 |           | Nvidia     | GP106 High Definition Aud... | 2     | snd_hda... | 4C9A2AA59C |
| 8086:2284 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 2     | snd_hda... | F6DDC974E1 |
| 8086:27d8 | 19da:a218 | Intel      | NM10/ICH7 Family High Def... | 2     | snd_hda... | 30F524BC82 |
| 8086:9d71 | 8086:2070 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | F1331B62E6 |
| 8086:a170 | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 2     | snd_hda... | 2CBDC3AD17 |
| 8086:a170 | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 2     | snd_hda... | 4C9A2AA59C |
| 8086:a2f0 | 103c:82a5 | Intel      | 200 Series PCH HD Audio      | 2     | snd_hda... | 9D7BDB2727 |
| 1002:1314 | 1002:1314 | AMD        | Wrestler HDMI Audio          | 1     | snd_hda... | 8D13B8BFE3 |
| 1002:1314 | 19da:a183 | AMD        | Wrestler HDMI Audio          | 1     | snd_hda... | 037A3E45C7 |
| 1002:4383 | 19da:a125 | AMD        | SBx00 Azalia (Intel HDA)     | 1     | snd_hda... | 037A3E45C7 |
| 1002:ab08 | 8086:ab08 | AMD        | Polaris 22 HDMI Audio        | 1     | snd_hda... | 0E16D3F886 |
| 1022:780d | 19da:a261 | AMD        | FCH Azalia Controller        | 1     | snd_hda... | 8D13B8BFE3 |
| 10de:0d94 | 10de:cb89 | Nvidia     | MCP89 High Definition Audio  | 1     | snd_hda... | C2DA8438C2 |
| 8086:0a0c | 1458:5000 | Intel      | Haswell-ULT HD Audio Cont... | 1     | snd_hda... | B590007CCF |
| 8086:0c0c | 19da:b220 | Intel      | Xeon E3-1200 v3/4th Gen C... | 1     | snd_hda... | 4E3E10AE15 |
| 8086:160c | 8086:2058 | Intel      | Broadwell-U Audio Controller | 1     | snd_hda... | 4AB80B03C5 |
| 8086:1c20 | 1734:11b0 | Intel      | 6 Series/C200 Series Chip... | 1     | snd_hda... | FC67594808 |
| 8086:1c20 | 19da:b202 | Intel      | 6 Series/C200 Series Chip... | 1     | snd_hda... | F8F1E1681B |
| 8086:1e20 | 19da:a247 | Intel      | 7 Series/C216 Chipset Fam... | 1     | snd_hda... | 3486F30CEE |
| 8086:2284 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 1     | snd_hda... | BD1F4F70F7 |
| 8086:2284 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | snd_hda... | 6157F936DB |
| 8086:27d8 | 8086:d617 | Intel      | NM10/ICH7 Family High Def... | 1     | snd_hda... | FD127FD8BF |
| 8086:27d8 | 8086:d625 | Intel      | NM10/ICH7 Family High Def... | 1     | snd_hda... | 4727851853 |
| 8086:5a98 |           | Intel      | Celeron N3350/Pentium N42... | 1     | snd_hda... | C08536440A |
| 8086:5a98 | 1d09:0101 | Intel      | Celeron N3350/Pentium N42... | 1     | snd_hda... | 69BB2EE752 |
| 8086:8c20 | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 1     | snd_hda... | 4E3E10AE15 |
| 8086:9c20 | 1458:fa50 | Intel      | 8 Series HD Audio Controller | 1     | snd_hda... | B590007CCF |
| 8086:9ca0 | 8086:2058 | Intel      | Wildcat Point-LP High Def... | 1     | snd_hda... | 4AB80B03C5 |
| 8086:a170 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     | snd_hda... | 305342DF08 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22a3 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 13    | ahci       | 001551B002 |
| 8086:9d03 | 8086:2068 | Intel      | Sunrise Point-LP SATA Con... | 11    | ahci       | 64913D4FAA |
| 8086:9c83 | 8086:2057 | Intel      | Wildcat Point-LP SATA Con... | 10    | ahci       | C32D1045F9 |
| 8086:1e03 | 8086:7270 | Intel      | 7 Series Chipset Family 6... | 9     | ahci       | D6FE9DA999 |
| 8086:9dd3 | 8086:2074 | Intel      | Cannon Point-LP SATA Cont... | 8     | ahci       | 23DC7C0455 |
| 8086:31e3 | 8086:2072 | Intel      | SATA controller              | 7     | ahci       | 0ED8661BD0 |
| 8086:9c03 | 8086:7270 | Intel      | 8 Series SATA Controller ... | 5     | ahci       | BC577C8669 |
| 8086:a103 | 8086:2064 | Intel      | HM170/QM170 Chipset SATA ... | 5     | ahci       | F68CFBE3F5 |
| 8086:1c03 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 4     | ahci       | 3419AE2627 |
| 8086:5ae3 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 4     | ahci       | C7F97B95C4 |
| 10de:0ab9 | 10de:cb79 | Nvidia     | MCP79 AHCI Controller        | 3     | ahci       | 191BB34391 |
| 8086:9d03 | 8086:2063 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 97355011D7 |
| 8086:22a3 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 2     | ahci       | F6DDC974E1 |
| 8086:9d03 | 8086:2070 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | F1331B62E6 |
| 8086:a102 | 19da:b333 | Intel      | Q170/Q150/B150/H170/H110/... | 2     | ahci       | 4C9A2AA59C |
| 8086:a282 | 103c:82a5 | Intel      | 200 Series PCH SATA contr... | 2     | ahci       | 9D7BDB2727 |
| 1002:4391 | 19da:a183 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 037A3E45C7 |
| 1022:7801 | 19da:a261 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 8D13B8BFE3 |
| 10de:0d88 | 106b:cb89 | Nvidia     | MCP89 SATA Controller (AH... | 1     | ahci       | C2DA8438C2 |
| 8086:1c02 | 1734:11ba | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | FC67594808 |
| 8086:1c02 | 19da:b202 | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | F8F1E1681B |
| 8086:1e03 | 19da:a247 | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | 3486F30CEE |
| 8086:22a3 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 1     | ahci       | BD1F4F70F7 |
| 8086:22a3 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | ahci       | 6157F936DB |
| 8086:27c1 | 19da:a218 | Intel      | NM10/ICH7 Family SATA Con... | 1     | ahci       | 30F524BC82 |
| 8086:27c1 | 8086:574d | Intel      | NM10/ICH7 Family SATA Con... | 1     | ahci       | 4727851853 |
| 8086:27c5 | 8086:7270 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 1     | ahci       | 5A02AA7966 |
| 8086:5ae3 | 19da:b325 | Intel      | Celeron N3350/Pentium N42... | 1     | ahci       | C08536440A |
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | ahci       | 69BB2EE752 |
| 8086:8c02 | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | 4E3E10AE15 |
| 8086:9c03 | 1458:b002 | Intel      | 8 Series SATA Controller ... | 1     | ahci       | B590007CCF |
| 8086:9c83 | 8086:2058 | Intel      | Wildcat Point-LP SATA Con... | 1     | ahci       | 4AB80B03C5 |
| 8086:a102 | 8086:7270 | Intel      | Q170/Q150/B150/H170/H110/... | 1     | ahci       | 305342DF08 |
| 8086:a103 | 8086:2073 | Intel      | HM170/QM170 Chipset SATA ... | 1     | ahci       | B4342A4CAA |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1c01 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 3     | ata_pii... | 9898EDBAF1 |
| 8086:27df | 8086:7270 | Intel      | 82801G (ICH7 Family) IDE ... | 3     | pata_acpi  | E78329BE05 |
| 8086:27c4 | 8086:7270 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 2     | pata_acpi  | E78329BE05 |
| 1002:439c | 19da:a183 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | pata_at... | 037A3E45C7 |
| 1022:780c | 19da:a261 | AMD        | FCH IDE Controller           | 1     | pata_at... | 8D13B8BFE3 |
| 10de:0ab5 | 10de:cb79 | Nvidia     | MCP79 SATA Controller        | 1     | pata_ac... | 2C45E4CE2A |
| 8086:27c0 | 19da:a218 | Intel      | NM10/ICH7 Family SATA Con... | 1     | ata_pii... | E907BA80AE |
| 8086:27c0 | 8086:4f4d | Intel      | NM10/ICH7 Family SATA Con... | 1     | ata_pii... | FD127FD8BF |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 7     | nvme       | 23DC7C0455 |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 4     | nvme       | 64913D4FAA |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 3     | nvme       | A11552D6EC |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 2     | nvme       | 74EE338F16 |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 2     | nvme       | 0B66BDFEE9 |
| 1987:5007 | 1987:5007 | Phison ... | E7 NVMe Controller           | 1     | nvme       | 0E16D3F886 |
| 8086:2522 | 8086:3806 | Intel      | NVMe SSD Optane Series Co... | 1     | nvme       | BDA8F46AD6 |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 1     | nvme       | 0E8E75B0EB |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2822 | 103c:82c0 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 2CBDC3AD17 |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1911 | 8086:2068 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 11    |            | 64913D4FAA |
| 8086:1911 | 8086:2074 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 8     |            | 23DC7C0455 |
| 8086:1513 | 2222:1111 | Intel      | CV82524 Thunderbolt Contr... | 7     | shpchp     | 3419AE2627 |
| 8086:1911 | 8086:2064 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 7     |            | F68CFBE3F5 |
| 8086:156c |           | Intel      | DSL5520 Thunderbolt 2 NHI... | 5     | thunder... | BC577C8669 |
| 8086:1911 | 8086:2073 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | 0E16D3F886 |
| 8086:1911 | 19da:b333 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 4C9A2AA59C |
| 8086:1911 | 8086:2070 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | F1331B62E6 |
| 8086:15de | 2222:1111 | Intel      | Controller                   | 1     | thunder... | 958FE71380 |
| 8086:1911 | 8086:2015 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 305342DF08 |
| 8086:3190 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 1     |            | 94F2AA43B7 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d2f | 8086:2068 | Intel      | Sunrise Point-LP USB 3.0 ... | 11    | xhci_hcd   | 64913D4FAA |
| 8086:9cb1 | 8086:2057 | Intel      | Wildcat Point-LP USB xHCI... | 10    | xhci_hcd   | C32D1045F9 |
| 8086:1e26 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 9     | ehci_hc... | D6FE9DA999 |
| 8086:1e2d | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 9     | ehci_hc... | D6FE9DA999 |
| 8086:1e31 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 9     | xhci_pci   | D6FE9DA999 |
| 8086:9ca6 | 8086:2057 | Intel      | Wildcat Point-LP USB EHCI... | 9     | ehci_hc... | C32D1045F9 |
| 8086:9ded | 8086:2074 | Intel      | Cannon Point-LP USB 3.1 x... | 8     | xhci_hcd   | 23DC7C0455 |
| 8086:1c26 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 7     | ehci_pci   | 3419AE2627 |
| 8086:1c27 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 7     | uhci_hcd   | 3419AE2627 |
| 8086:1c2c | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 7     | uhci_hcd   | 3419AE2627 |
| 8086:1c2d | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 7     | ehci_pci   | 3419AE2627 |
| 8086:22b5 |           | Intel      | Atom/Celeron/Pentium Proc... | 7     | xhci_hcd   | 001551B002 |
| 8086:31a8 | 8086:2072 | Intel      | USB Controller               | 7     | xhci_hcd   | 0ED8661BD0 |
| 8086:a12f | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 7     | xhci_hcd   | F68CFBE3F5 |
| 8086:22b5 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 6     | xhci_pci   | 654561E17B |
| 8086:9c31 | 8086:7270 | Intel      | 8 Series USB xHCI HC         | 5     | xhci_hcd   | BC577C8669 |
| 10de:0aa5 | 10de:cb79 | Nvidia     | MCP79 OHCI USB 1.1 Contro... | 4     | ohci_hc... | 191BB34391 |
| 10de:0aa6 | 10de:cb79 | Nvidia     | MCP79 EHCI USB 2.0 Contro... | 4     | ehci_hc... | 191BB34391 |
| 10de:0aa7 | 10de:cb79 | Nvidia     | MCP79 OHCI USB 1.1 Contro... | 4     | ohci_hc... | 191BB34391 |
| 10de:0aa9 | 10de:cb79 | Nvidia     | MCP79 EHCI USB 2.0 Contro... | 4     | ehci_hc... | 191BB34391 |
| 1b21:2142 | 8086:2073 | ASMedia... | ASM2142 USB 3.1 Host Cont... | 4     | xhci_hcd   | 0E16D3F886 |
| 8086:5aa8 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 4     | xhci_hcd   | C7F97B95C4 |
| 8086:a12f | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 4     | xhci_hcd   | 0E16D3F886 |
| 1b21:1242 | 1b21:1242 | ASMedia... | ASM1142 USB 3.1 Host Cont... | 3     | xhci_pci   | 4C9A2AA59C |
| 8086:27c8 | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 3     | uhci_hcd   | E78329BE05 |
| 8086:27c9 | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 3     | uhci_hcd   | E78329BE05 |
| 8086:27ca | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 3     | uhci_hcd   | E78329BE05 |
| 8086:27cb | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 3     | uhci_hcd   | E78329BE05 |
| 8086:27cc | 8086:7270 | Intel      | NM10/ICH7 Family USB2 EHC... | 3     | ehci_pci   | E78329BE05 |
| 8086:9d2f | 8086:2063 | Intel      | Sunrise Point-LP USB 3.0 ... | 3     | xhci_pci   | 97355011D7 |
| 1b6f:7023 | 1b6f:7023 | Etron T... | EJ168 USB 3.0 Host Contro... | 2     | xhci_pci   | 30F524BC82 |
| 8086:15b5 | 2222:1111 | Intel      | DSL6340 USB 3.1 Controlle... | 2     | xhci_hcd   | F68CFBE3F5 |
| 8086:15db | 2222:1111 | Intel      | JHL6340 Thunderbolt 3 USB... | 2     | xhci_hcd   | 958FE71380 |
| 8086:22b5 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 2     | xhci_hcd   | F6DDC974E1 |
| 8086:27c8 | 19da:a218 | Intel      | NM10/ICH7 Family USB UHCI... | 2     | uhci_hcd   | 30F524BC82 |
| 8086:27c9 | 19da:a218 | Intel      | NM10/ICH7 Family USB UHCI... | 2     | uhci_hcd   | 30F524BC82 |
| 8086:27ca | 19da:a218 | Intel      | NM10/ICH7 Family USB UHCI... | 2     | uhci_hcd   | 30F524BC82 |
| 8086:27cb | 19da:a218 | Intel      | NM10/ICH7 Family USB UHCI... | 2     | uhci_hcd   | 30F524BC82 |
| 8086:27cc | 19da:a218 | Intel      | NM10/ICH7 Family USB2 EHC... | 2     | ehci_hc... | 30F524BC82 |
| 8086:9d2f | 8086:2070 | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | F1331B62E6 |
| 8086:a12f | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 2     | xhci_hcd   | 2CBDC3AD17 |
| 8086:a12f | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 2     | xhci_hcd   | 4C9A2AA59C |
| 8086:a2af | 103c:82a5 | Intel      | 200 Series/Z370 Chipset F... | 2     | xhci_hcd   | 9D7BDB2727 |
| 1002:4396 | 19da:a183 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 1     | ehci_hc... | 037A3E45C7 |
| 1002:4397 | 19da:a183 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1     | ohci_hc... | 037A3E45C7 |
| 1002:4399 | 19da:a183 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1     | ohci_hc... | 037A3E45C7 |
| 1022:7807 | 19da:a261 | AMD        | FCH USB OHCI Controller      | 1     | ohci_hc... | 8D13B8BFE3 |
| 1022:7808 | 19da:a261 | AMD        | FCH USB EHCI Controller      | 1     | ehci_hc... | 8D13B8BFE3 |
| 1022:7809 | 19da:a261 | AMD        | FCH USB OHCI Controller      | 1     | ohci_hc... | 8D13B8BFE3 |
| 1022:7812 | 19da:a261 | AMD        | FCH USB XHCI Controller      | 1     | xhci_pci   | 8D13B8BFE3 |
| 1033:0194 | ffff:ffff | NEC Com... | uPD720200 USB 3.0 Host Co... | 1     | xhci_hcd   | 037A3E45C7 |
| 10de:0d9c | 10de:cb89 | Nvidia     | MCP89 OHCI USB 1.1 Contro... | 1     | ohci_hc... | C2DA8438C2 |
| 10de:0d9d | 10de:cb89 | Nvidia     | MCP89 EHCI USB 2.0 Contro... | 1     | ehci_hc... | C2DA8438C2 |
| 12d8:400e | 12d8:400e | Pericom... | PI7C9X442SL USB OHCI Cont... | 1     | ohci_hc... | 029708EAF4 |
| 12d8:400f | 12d8:400f | Pericom... | PI7C9X442SL USB EHCI Cont... | 1     | ehci_hc... | 029708EAF4 |
| 1912:0015 | 19da:0194 | Renesas... | uPD720202 USB 3.0 Host Co... | 1     | xhci_pci   | F8F1E1681B |
| 1912:0015 | 19da:0198 | Renesas... | uPD720202 USB 3.0 Host Co... | 1     | xhci_pci   | 3486F30CEE |
| 8086:0f35 | 8086:0f35 | Intel      | Atom Processor Z36xxx/Z37... | 1     | xhci_hcd   | F339ADE022 |
| 8086:15db | 8086:2074 | Intel      | JHL6340 Thunderbolt 3 USB... | 1     | xhci_hcd   | 23DC7C0455 |
| 8086:1c26 | 1734:11ba | Intel      | 6 Series/C200 Series Chip... | 1     | ehci_pci   | FC67594808 |
| 8086:1c26 | 19da:b202 | Intel      | 6 Series/C200 Series Chip... | 1     | ehci_hc... | F8F1E1681B |
| 8086:1c2d | 1734:11ba | Intel      | 6 Series/C200 Series Chip... | 1     | ehci_pci   | FC67594808 |
| 8086:1c2d | 19da:b202 | Intel      | 6 Series/C200 Series Chip... | 1     | ehci_hc... | F8F1E1681B |
| 8086:1e26 | 19da:a247 | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci_hc... | 3486F30CEE |
| 8086:1e2d | 19da:a247 | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci_hc... | 3486F30CEE |
| 8086:22b5 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 1     | xhci_hcd   | BD1F4F70F7 |
| 8086:22b5 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | xhci_hcd   | 6157F936DB |
| 8086:22b5 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | xhci_hcd   | 5C7849A72A |
| 8086:27c8 | 8086:4f4d | Intel      | NM10/ICH7 Family USB UHCI... | 1     | uhci_hcd   | FD127FD8BF |
| 8086:27c8 | 8086:574d | Intel      | NM10/ICH7 Family USB UHCI... | 1     | uhci_hcd   | 4727851853 |
| 8086:27c9 | 8086:4f4d | Intel      | NM10/ICH7 Family USB UHCI... | 1     | uhci_hcd   | FD127FD8BF |
| 8086:27c9 | 8086:574d | Intel      | NM10/ICH7 Family USB UHCI... | 1     | uhci_hcd   | 4727851853 |
| 8086:27ca | 8086:4f4d | Intel      | NM10/ICH7 Family USB UHCI... | 1     | uhci_hcd   | FD127FD8BF |
| 8086:27ca | 8086:574d | Intel      | NM10/ICH7 Family USB UHCI... | 1     | uhci_hcd   | 4727851853 |
| 8086:27cb | 8086:4f4d | Intel      | NM10/ICH7 Family USB UHCI... | 1     | uhci_hcd   | FD127FD8BF |
| 8086:27cb | 8086:574d | Intel      | NM10/ICH7 Family USB UHCI... | 1     | uhci_hcd   | 4727851853 |
| 8086:27cc | 8086:4f4d | Intel      | NM10/ICH7 Family USB2 EHC... | 1     | ehci_hc... | FD127FD8BF |
| 8086:27cc | 8086:574d | Intel      | NM10/ICH7 Family USB2 EHC... | 1     | ehci_hc... | 4727851853 |
| 8086:5aa8 | 19da:b325 | Intel      | Celeron N3350/Pentium N42... | 1     | xhci_hcd   | C08536440A |
| 8086:5aa8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | xhci_hcd   | 69BB2EE752 |
| 8086:8c26 | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 1     | ehci_hc... | 4E3E10AE15 |
| 8086:8c2d | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 1     | ehci_hc... | 4E3E10AE15 |
| 8086:8c31 | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 1     | xhci_hcd   | 4E3E10AE15 |
| 8086:9c26 | 1458:5004 | Intel      | 8 Series USB EHCI #1         | 1     | ehci_hc... | B590007CCF |
| 8086:9c31 | 1458:5004 | Intel      | 8 Series USB xHCI HC         | 1     | xhci_pci   | B590007CCF |
| 8086:9ca6 | 8086:2058 | Intel      | Wildcat Point-LP USB EHCI... | 1     | ehci_hc... | 4AB80B03C5 |
| 8086:9cb1 | 8086:2058 | Intel      | Wildcat Point-LP USB xHCI... | 1     | xhci_pci   | 4AB80B03C5 |
| 8086:a12f | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     | xhci_pci   | 305342DF08 |

