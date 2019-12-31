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
   * [ Ipmi smic interface ](#ipmi-smic-interface-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Multimedia controller ](#multimedia-controller-pci)
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
| 8086:9d84 | 8086:2074 | Intel      | Cannon Point-LP LPC Contr... | 21    |            | B039AEFD9E |
| 8086:9db0 | 8086:2074 | Intel      | Cannon Point-LP PCI Expre... | 21    | pcieport   | B039AEFD9E |
| 8086:9db6 | 8086:2074 | Intel      | Cannon Point-LP PCI Expre... | 21    | pcieport   | B039AEFD9E |
| 8086:9db8 | 8086:2074 | Intel      | Cannon Point-LP PCI Expre... | 21    | pcieport   | B039AEFD9E |
| 8086:9dbc | 8086:2074 | Intel      | Cannon Point-LP PCI Expre... | 21    | pcieport   | B039AEFD9E |
| 8086:5904 | 8086:2068 | Intel      | Xeon E3-1200 v6/7th Gen C... | 18    | skl_uncore | 145DFF2B67 |
| 8086:9d10 | 8086:2068 | Intel      | Sunrise Point-LP PCI Expr... | 18    | pcieport   | 145DFF2B67 |
| 8086:9d17 | 8086:2068 | Intel      | Sunrise Point-LP PCI Expr... | 18    | pcieport   | 145DFF2B67 |
| 8086:9d4e | 8086:2068 | Intel      | Sunrise Point LPC Control... | 18    |            | 145DFF2B67 |
| 8086:3ed0 | 8086:2074 | Intel      | 8th Gen Core Processor Ho... | 16    | skl_uncore | B039AEFD9E |
| 8086:9d15 | 8086:2068 | Intel      | Sunrise Point-LP PCI Expr... | 16    | pcieport   | 145DFF2B67 |
| 8086:2280 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 15    | iosf_mb... | 5D10E3F271 |
| 8086:229c | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 15    | lpc_ich    | 5D10E3F271 |
| 8086:22c8 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 15    | shpchp     | 5D10E3F271 |
| 8086:22ca | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 15    | shpchp     | 5D10E3F271 |
| 8086:22cc | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 13    | shpchp     | 5D10E3F271 |
| 8086:1e10 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 11    | pcieport   | 75E8A3936D |
| 8086:1e12 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 11    | pcieport   | 75E8A3936D |
| 8086:1604 | 8086:2057 | Intel      | Broadwell-U Host Bridge -OPI | 10    | bdw_uncore | 148534267A |
| 8086:1e14 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 10    | pcieport   | 75E8A3936D |
| 8086:1e57 | 8086:7270 | Intel      | HM77 Express Chipset LPC ... | 10    | lpc_ich    | 75E8A3936D |
| 8086:31d8 | 8086:2072 | Intel      | Gemini Lake PCI Express R... | 10    | pcieport   | BA6884F66B |
| 8086:31da | 8086:2072 | Intel      | Gemini Lake PCI Express R... | 10    | pcieport   | BA6884F66B |
| 8086:31e8 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 10    |            | BA6884F66B |
| 8086:31f0 | 8086:2072 | Intel      | Gemini Lake Host Bridge      | 10    |            | BA6884F66B |
| 8086:9c90 | 8086:2057 | Intel      | Wildcat Point-LP PCI Expr... | 10    | pcieport   | 148534267A |
| 8086:9cc3 | 8086:2057 | Intel      | Wildcat Point-LP LPC Cont... | 10    | lpc_ich    | 148534267A |
| 104c:823e |           | Texas I... | XIO2213A/B/XIO2221 PCI Ex... | 9     | shpchp     | E563DAD6EF |
| 8086:1547 | 2222:1111 | Intel      | DSL3510 Thunderbolt Contr... | 9     | pcieport   | 75E8A3936D |
| 8086:1901 | 8086:2073 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 9     | pcieport   | 275EDFBD40 |
| 8086:1905 | 8086:2073 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 9     | pcieport   | 275EDFBD40 |
| 8086:1909 | 8086:2073 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 9     | pcieport   | 275EDFBD40 |
| 8086:5910 | 8086:2073 | Intel      | Xeon E3-1200 v6/7th Gen C... | 9     | skl_uncore | 275EDFBD40 |
| 8086:9c96 | 8086:2057 | Intel      | Wildcat Point-LP PCI Expr... | 9     | pcieport   | 148534267A |
| 8086:a110 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 9     | pcieport   | 275EDFBD40 |
| 8086:a114 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 9     | pcieport   | 275EDFBD40 |
| 8086:a152 | 8086:2073 | Intel      | HM175 Chipset LPC/eSPI Co... | 9     |            | 275EDFBD40 |
| 8086:1513 |           | Intel      | CV82524 Thunderbolt Contr... | 8     | pcieport   | 3419AE2627 |
| 8086:1910 | 8086:2064 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 8     | skl_uncore | 071897D2C7 |
| 8086:a110 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 8     | pcieport   | 071897D2C7 |
| 8086:a112 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 8     | pcieport   | 071897D2C7 |
| 8086:a114 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 8     | pcieport   | 071897D2C7 |
| 8086:a14e | 8086:2064 | Intel      | HM170 Chipset LPC/eSPI Co... | 8     |            | 071897D2C7 |
| 8086:0151 | 106b:00ff | Intel      | Xeon E3-1200 v2/3rd Gen C... | 7     | pcieport   | D6FE9DA999 |
| 8086:0154 | 106b:00ff | Intel      | 3rd Gen Core processor DR... | 7     | ivb_uncore | D6FE9DA999 |
| 8086:0f00 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 7     | iosf_mb... | 9314D29F45 |
| 8086:1c10 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 7     | shpchp     | 3419AE2627 |
| 8086:1c12 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 7     | shpchp     | 3419AE2627 |
| 8086:1c14 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 7     | shpchp     | 3419AE2627 |
| 8086:1c49 | 8086:7270 | Intel      | HM65 Express Chipset LPC ... | 7     | lpc_ich    | 3419AE2627 |
| 8086:2280 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 7     | iosf_mb... | D999C674F1 |
| 8086:229c | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 7     | lpc_ich    | D999C674F1 |
| 8086:22c8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 7     | pcieport   | D999C674F1 |
| 8086:5ae8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 7     | lpc_ich    | 0BEDF4D656 |
| 8086:5af0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 7     |            | 0BEDF4D656 |
| 8086:a111 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 7     | pcieport   | 071897D2C7 |
| 8086:a111 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 7     | pcieport   | 275EDFBD40 |
| 8086:a112 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 7     | pcieport   | 275EDFBD40 |
| 8086:a118 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 7     | pcieport   | 275EDFBD40 |
| 8086:9d18 | 8086:2068 | Intel      | Sunrise Point-LP PCI Expr... | 6     | pcieport   | 145DFF2B67 |
| 104c:823e | 0000:0000 | Texas I... | XIO2213A/B/XIO2221 PCI Ex... | 5     | shpchp     | 4D008C616B |
| 10de:0a82 |           | Nvidia     | MCP79 Host Bridge            | 5     |            | EEA609467F |
| 10de:0aa0 | 10de:0000 | Nvidia     | MCP79 PCI Express Bridge     | 5     | shpchp     | EEA609467F |
| 10de:0aab | 10de:cb79 | Nvidia     | MCP79 PCI Bridge             | 5     |            | EEA609467F |
| 10de:0aae | 10de:cb79 | Nvidia     | MCP79 LPC Bridge             | 5     |            | EEA609467F |
| 10de:0ac6 | 10de:0000 | Nvidia     | MCP79 PCI Express Bridge     | 5     | shpchp     | EEA609467F |
| 10de:0ac7 | 10de:0000 | Nvidia     | MCP79 PCI Express Bridge     | 5     | shpchp     | EEA609467F |
| 8086:0a04 | 106b:0141 | Intel      | Haswell-ULT DRAM Controller  | 5     | hsw_uncore | BC577C8669 |
| 8086:0f1c | 8086:0f1c | Intel      | Atom Processor Z36xxx/Z37... | 5     | lpc_ich    | 9314D29F45 |
| 8086:156d |           | Intel      | DSL5520 Thunderbolt 2 Bri... | 5     | shpchp     | BC577C8669 |
| 8086:3ecc | 8086:2074 | Intel      | Coffee Lake Host Bridge/D... | 5     | skl_uncore | 0B6C8F302C |
| 8086:5af0 |           | Intel      | Celeron N3350/Pentium N42... | 5     |            | C7F97B95C4 |
| 8086:9c10 | 8086:7270 | Intel      | 8 Series PCI Express Root... | 5     | shpchp     | BC577C8669 |
| 8086:9c14 | 8086:7270 | Intel      | 8 Series PCI Express Root... | 5     | shpchp     | BC577C8669 |
| 8086:9c16 | 8086:7270 | Intel      | 8 Series PCI Express Root... | 5     | shpchp     | BC577C8669 |
| 8086:9c18 | 8086:7270 | Intel      | 8 Series PCI Express Root... | 5     | shpchp     | BC577C8669 |
| 8086:9c43 | 8086:7270 | Intel      | 8 Series LPC Controller      | 5     | lpc_ich    | BC577C8669 |
| 8086:9d4e | 8086:2070 | Intel      | Sunrise Point LPC Control... | 5     |            | 87F2F89679 |
| 8086:a11c | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 5     | pcieport   | 275EDFBD40 |
| 8086:15da | 2222:1111 | Intel      | JHL6340 Thunderbolt 3 Bri... | 4     | pcieport   | C00059FE69 |
| 8086:15da | 8086:2074 | Intel      | JHL6340 Thunderbolt 3 Bri... | 4     | pcieport   | B039AEFD9E |
| 8086:2448 |           | Intel      | 82801 Mobile PCI Bridge      | 4     |            | E3E276A6C9 |
| 8086:27a0 | 8086:7270 | Intel      | Mobile 945GM/PM/GMS, 943/... | 4     |            | E3E276A6C9 |
| 8086:27b9 | 8086:7270 | Intel      | 82801GBM (ICH7-M) LPC Int... | 4     | lpc_ich    | E3E276A6C9 |
| 8086:27d0 |           | Intel      | NM10/ICH7 Family PCI Expr... | 4     | pcieport   | E3E276A6C9 |
| 8086:27d2 |           | Intel      | NM10/ICH7 Family PCI Expr... | 4     | pcieport   | E3E276A6C9 |
| 8086:5914 | 8086:2070 | Intel      | Xeon E3-1200 v6/7th Gen C... | 4     | skl_uncore | 87F2F89679 |
| 8086:5ad8 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 4     | shpchp     | C7F97B95C4 |
| 8086:5ad9 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 4     | shpchp     | C7F97B95C4 |
| 8086:5ada | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 4     | shpchp     | C7F97B95C4 |
| 8086:5ae8 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 4     | lpc_ich    | C7F97B95C4 |
| 8086:9d12 | 8086:2070 | Intel      | Sunrise Point-LP PCI Expr... | 4     | pcieport   | A8A0EB4EEE |
| 1022:1700 |           | AMD        | Family 12h/14h Processor ... | 3     |            | 0A76049887 |
| 1022:1701 |           | AMD        | Family 12h/14h Processor ... | 3     |            | 0A76049887 |
| 1022:1702 |           | AMD        | Family 12h/14h Processor ... | 3     |            | 0A76049887 |
| 1022:1703 |           | AMD        | Family 12h/14h Processor ... | 3     | k10temp    | 0A76049887 |
| 1022:1704 |           | AMD        | Family 12h/14h Processor ... | 3     |            | 0A76049887 |
| 1022:1716 |           | AMD        | Family 12h/14h Processor ... | 3     |            | 0A76049887 |
| 1022:1718 |           | AMD        | Family 12h/14h Processor ... | 3     |            | 0A76049887 |
| 1022:1719 |           | AMD        | Family 12h/14h Processor ... | 3     |            | 0A76049887 |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:522a | 8086:2074 | Realtek... | RTS522A PCI Express Card ... | 21    | rtsx_pci   | B039AEFD9E |
| 10ec:5229 | 8086:2068 | Realtek... | RTS5229 PCI Express Card ... | 18    | rtsx_pci   | 145DFF2B67 |
| 10ec:5229 | 8086:2072 | Realtek... | RTS5229 PCI Express Card ... | 10    | rtsx_pci   | BA6884F66B |
| 10ec:5229 | 8086:2067 | Realtek... | RTS5229 PCI Express Card ... | 4     | rtsx_pci   | C7F97B95C4 |
| 10ec:5229 | 10ec:5229 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx_pci   | 6FD8E8E647 |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0aa3 | 10de:cb79 | Nvidia     | MCP79 Co-processor           | 5     | nvidia     | EEA609467F |
| 10de:0d7a | 10de:cb89 | Nvidia     | MCP89 Co-Processor           | 2     |            | E563DAD6EF |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9de0 | 8086:2074 | Intel      | Cannon Point-LP MEI Contr... | 21    | mei_me     | B039AEFD9E |
| 8086:9d3a | 8086:2068 | Intel      | Sunrise Point-LP CSME HEC... | 18    | mei_me     | 145DFF2B67 |
| 8086:1e3a | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 11    | mei_me     | 75E8A3936D |
| 8086:319a | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 10    | mei_me     | BA6884F66B |
| 8086:9cba | 8086:2057 | Intel      | Wildcat Point-LP MEI Cont... | 10    | mei_me     | 148534267A |
| 8086:a13a | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 9     | mei_me     | 275EDFBD40 |
| 8086:a13a | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 8     | mei_me     | 071897D2C7 |
| 8086:1c3a | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 7     | mei_me     | 3419AE2627 |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 7     | mei_me     | 0BEDF4D656 |
| 8086:5a9a |           | Intel      | Celeron N3350/Pentium N42... | 5     | mei_me     | C7F97B95C4 |
| 8086:9c3a | 8086:7270 | Intel      | 8 Series HECI #0             | 5     | mei_me     | BC577C8669 |
| 8086:9d3a | 8086:2070 | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | 87F2F89679 |
| 8086:9d3a | 8086:2063 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | 97355011D7 |
| 8086:a360 | 17aa:3135 | Intel      | Cannon Lake PCH HECI Cont... | 3     | mei_me     | 92903CF555 |
| 8086:a13a | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 2     | mei_me     | 2CBDC3AD17 |
| 8086:a13a | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 2     | mei_me     | 4C9A2AA59C |
| 8086:a2ba | 103c:829a | Intel      | 200 Series PCH CSME HECI #1  | 2     | mei_me     | E0FB7EA560 |
| 8086:a2ba | 103c:82a5 | Intel      | 200 Series PCH CSME HECI #1  | 2     | mei_me     | 9D7BDB2727 |
| 8086:a360 | 17aa:3136 | Intel      | Cannon Lake PCH HECI Cont... | 2     | mei_me     | 02ECA27578 |
| 8086:1c3a | 1734:11ba | Intel      | 6 Series/C200 Series Chip... | 1     | mei_me     | FC67594808 |
| 8086:1c3a | 19da:b202 | Intel      | 6 Series/C200 Series Chip... | 1     | mei_me     | F8F1E1681B |
| 8086:1e3a | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 1     | mei_me     | 9AFBFD107A |
| 8086:1e3a | 19da:a247 | Intel      | 7 Series/C216 Chipset Fam... | 1     | mei_me     | 3486F30CEE |
| 8086:1e3a | 19da:b211 | Intel      | 7 Series/C216 Chipset Fam... | 1     | mei_me     | 4C4D77145B |
| 8086:1e3a | 1b0a:015b | Intel      | 7 Series/C216 Chipset Fam... | 1     | mei_me     | 7E54F1E784 |
| 8086:319a | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 1     | mei_me     | 1C078E1FC5 |
| 8086:319a | 1043:875e | Intel      | Celeron/Pentium Silver Pr... | 1     | mei_me     | FE95B7E800 |
| 8086:319a | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | mei_me     | 6616869490 |
| 8086:8c3a | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 1     | mei_me     | 4E3E10AE15 |
| 8086:8c3a | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 1     | mei_me     | FF3CE414E4 |
| 8086:8cba | 1043:8534 | Intel      | 9 Series Chipset Family M... | 1     | mei_me     | B09664C500 |
| 8086:9c3a | 1458:5001 | Intel      | 8 Series HECI #0             | 1     | mei_me     | B590007CCF |
| 8086:9c3a | 19da:b239 | Intel      | 8 Series HECI #0             | 1     | mei_me     | 71373D2071 |
| 8086:9cba | 8086:2058 | Intel      | Wildcat Point-LP MEI Cont... | 1     | mei_me     | 4AB80B03C5 |
| 8086:9da8 | 8086:2075 | Intel      | 8th Gen Intel Core Proces... | 1     | intel_l... | 6FD8E8E647 |
| 8086:9de0 | 8086:2075 | Intel      | Cannon Point-LP MEI Contr... | 1     | mei_me     | 6FD8E8E647 |
| 8086:a13a | 1019:9bc6 | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | 5DD127A865 |
| 8086:a13a | 8086:1999 | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | 305342DF08 |
| 8086:a360 | 17aa:312d | Intel      | Cannon Lake PCH HECI Cont... | 1     | mei_me     | 8ED3B0B386 |

### Dma controller (eisa dma) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22c0 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 9     | dw_dmac... | C7D9257057 |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2298 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 15    | mei_txe    | 5D10E3F271 |
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 7     | mei_txe    | D999C674F1 |
| 8086:0f18 | 8086:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 6     | mei_txe    | DF450C0459 |
| 8086:2298 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | F6DDC974E1 |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 1     |            | 36CC2B3CE6 |
| 8086:0f18 |           | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | 64F64657D5 |
| 8086:0f18 | 1071:0730 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | BE63E554C5 |
| 8086:2298 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | BD1F4F70F7 |
| 8086:2298 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | 6157F936DB |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 11c1:5901 | 11c1:5900 | LSI        | FW643 [TrueFire] PCIe 139... | 16    | firewir... | 75E8A3936D |
| 104c:823f |           | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 9     | firewir... | E563DAD6EF |
| 11c1:5811 | 11c1:5811 | LSI        | FW322/323 [TrueFire] 1394... | 4     | firewir... | E3E276A6C9 |
| 11c1:5901 | c111:0159 | LSI        | FW643 [TrueFire] PCIe 139... | 1     | firewir... | 029708EAF4 |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1577 | 1022:1577 | AMD        | Family 15h (Models 60h-6f... | 1     |            | 36CC2B3CE6 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3ea5 | 8086:2074 | Intel      | Iris Plus Graphics 655       | 21    | i915       | B039AEFD9E |
| 8086:22b1 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 15    | i915       | 5D10E3F271 |
| 8086:5916 | 8086:2068 | Intel      | HD Graphics 620              | 10    | i915       | C00059FE69 |
| 8086:193b | 8086:2064 | Intel      | Iris Pro Graphics 580        | 8     | i915       | 071897D2C7 |
| 8086:3185 | 8086:2072 | Intel      | UHD Graphics 605             | 8     | i915       | BA6884F66B |
| 1002:694c | 8086:2073 | AMD        | Polaris 22 XT [Radeon RX ... | 7     | amdgpu     | 275EDFBD40 |
| 8086:0166 | 106b:00ff | Intel      | 3rd Gen Core processor Gr... | 7     | i915       | D6FE9DA999 |
| 8086:0f31 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 7     | i915       | 9314D29F45 |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics 500              | 6     | i915       | 0BEDF4D656 |
| 10de:0861 | 106b:00ae | Nvidia     | C79 [GeForce 9400]           | 5     | nouveau    | EEA609467F |
| 8086:1616 | 8086:2057 | Intel      | HD Graphics 5500             | 5     | i915       | 078CF691FD |
| 8086:591b | 8086:2073 | Intel      | HD Graphics 630              | 5     | i915       | 275EDFBD40 |
| 8086:5927 | 8086:2068 | Intel      | Iris Plus Graphics 650       | 5     | i915       | F9C39F6628 |
| 8086:1626 | 8086:2057 | Intel      | HD Graphics 6000             | 4     | i915       | 148534267A |
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 4     | i915       | 79E7DF4FDC |
| 8086:27a2 | 8086:7270 | Intel      | Mobile 945GM/GMS, 943/940... | 4     | i915       | E3E276A6C9 |
| 8086:5917 | 8086:2070 | Intel      | UHD Graphics 620             | 4     | i915       | 87F2F89679 |
| 8086:5a85 | 8086:2067 | Intel      | HD Graphics 500              | 4     | i915       | C7F97B95C4 |
| 1002:6741 | 106b:00e8 | AMD        | Whistler [Radeon HD 6630M... | 3     | radeon     | 9898EDBAF1 |
| 10de:1050 | 19da:2180 | Nvidia     | GF119M [GeForce GT 520M]     | 3     | nouveau    | 49EF2577E1 |
| 8086:0126 | 106b:00e6 | Intel      | 2nd Generation Core Proce... | 3     | i915       | 3419AE2627 |
| 8086:0166 | 106b:0101 | Intel      | 3rd Gen Core processor Gr... | 3     | i915       | 75E8A3936D |
| 8086:0a26 | 106b:0141 | Intel      | Haswell-ULT Integrated Gr... | 3     | i915       | 42A2D2DC72 |
| 8086:1926 | 8086:2063 | Intel      | Iris Graphics 540            | 3     | i915       | 97355011D7 |
| 8086:22b1 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 3     | i915       | D999C674F1 |
| 8086:5926 | 8086:2068 | Intel      | Iris Plus Graphics 640       | 3     | i915       | 145DFF2B67 |
| 1002:694e | 8086:2073 | AMD        | Polaris 22 XL [Radeon RX ... | 2     | amdgpu     | 532A0BFEBB |
| 10de:08a4 | 106b:00c0 | Nvidia     | MCP89 [GeForce 320M]         | 2     | nouveau    | E563DAD6EF |
| 10de:13b4 | 103c:82c0 | Nvidia     | GM107GLM [Quadro M620 Mob... | 2     | nvidia     | 2CBDC3AD17 |
| 10de:1c20 | 19da:2413 | Nvidia     | GP106M [GeForce GTX 1060 ... | 2     | nouveau    | 4C9A2AA59C |
| 8086:0a2e | 106b:0141 | Intel      | Haswell-ULT Integrated Gr... | 2     | i915       | BC577C8669 |
| 8086:22b1 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 2     | i915       | F6DDC974E1 |
| 8086:3184 | 8086:2072 | Intel      | UHD Graphics 605             | 2     | i915       | A06C7F57FE |
| 8086:3e92 | 17aa:3135 | Intel      | UHD Graphics 630 (Desktop)   | 2     | i915       | 92903CF555 |
| 8086:3e92 | 17aa:3136 | Intel      | UHD Graphics 630 (Desktop)   | 2     | i915       | 02ECA27578 |
| 1002:699f | 8086:2075 | AMD        | Lexa PRO [Radeon 540/540X... | 1     | amdgpu     | 6FD8E8E647 |
| 1002:9802 | 19da:a183 | AMD        | Wrestler [Radeon HD 6310]    | 1     | radeon     | 037A3E45C7 |
| 1002:9806 | 103c:17e2 | AMD        | Wrestler [Radeon HD 6320]    | 1     | radeon     | 0A76049887 |
| 1002:9808 | 19da:a261 | AMD        | Wrestler [Radeon HD 7340]    | 1     | radeon     | 8D13B8BFE3 |
| 1002:98e4 | 17aa:312f | AMD        | Stoney [Radeon R2/R3/R4/R... | 1     | amdgpu     | 36CC2B3CE6 |
| 1002:9998 | 1458:d000 | AMD        | Richland [Radeon HD 8370D]   | 1     | radeon     | A28492492A |
| 10de:13c0 | 1458:3672 | Nvidia     | GM204 [GeForce GTX 980]      | 1     | nvidia     | B09664C500 |
| 10de:13c2 | 3842:2974 | Nvidia     | GM204 [GeForce GTX 970]      | 1     | nvidia     | 9AFBFD107A |
| 10de:1402 | 3842:2951 | Nvidia     | GM206 [GeForce GTX 950]      | 1     | nvidia     | FF3CE414E4 |
| 10de:1cb6 | 10de:1264 | Nvidia     | GP107GL [Quadro P620]        | 1     | nouveau    | 92903CF555 |
| 1106:7122 | 1106:7122 | VIA Tec... | VX900 Graphics [Chrome9 HD]  | 1     |            | 0E6D540B44 |
| 8086:0116 | 106b:00e7 | Intel      | 2nd Generation Core Proce... | 1     | i915       | 4D008C616B |
| 8086:0152 | 1734:11d7 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 1     | i915       | FC67594808 |
| 8086:0156 | 19da:2111 | Intel      | 3rd Gen Core processor Gr... | 1     | i915       | 3486F30CEE |
| 8086:0156 | 19da:b211 | Intel      | 3rd Gen Core processor Gr... | 1     | i915       | 4C4D77145B |
| 8086:0156 | 1b0a:015b | Intel      | 3rd Gen Core processor Gr... | 1     | i915       | 7E54F1E784 |
| 8086:0162 | 19da:b202 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 1     | i915       | F8F1E1681B |
| 8086:0166 | 8086:2211 | Intel      | 3rd Gen Core processor Gr... | 1     | i915       | 2F246CACD8 |
| 8086:0412 | 19da:b220 | Intel      | Xeon E3-1200 v3/4th Gen C... | 1     | i915       | 4E3E10AE15 |
| 8086:0a06 | 19da:b239 | Intel      | Haswell-ULT Integrated Gr... | 1     | i915       | 71373D2071 |
| 8086:0a16 | 1458:d000 | Intel      | Haswell-ULT Integrated Gr... | 1     | i915       | B590007CCF |
| 8086:0f31 | 17aa:30b5 | Intel      | Atom Processor Z36xxx/Z37... | 1     |            | DF450C0459 |
| 8086:1616 | 8086:2058 | Intel      | HD Graphics 5500             | 1     | i915       | 4AB80B03C5 |
| 8086:162b | 8086:2057 | Intel      | Iris Graphics 6100           | 1     | i915       | 44CAA27AAD |
| 8086:1912 | 103c:829a | Intel      | HD Graphics 530              | 1     | i915       | E0FB7EA560 |
| 8086:1912 | 103c:82a5 | Intel      | HD Graphics 530              | 1     | i915       | 2350EA995C |
| 8086:1912 | 8086:0000 | Intel      | HD Graphics 530              | 1     | i915       | 305342DF08 |
| 8086:22b1 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 1     | i915       | BD1F4F70F7 |
| 8086:22b1 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | i915       | 6157F936DB |
| 8086:27a6 | 8086:7270 | Intel      | Mobile 945GM/GMS/GME, 943... | 1     |            | 5A02AA7966 |
| 8086:3184 | 8086:2212 | Intel      | UHD Graphics 605             | 1     | i915       | 6616869490 |
| 8086:3185 | 1028:080c | Intel      | UHD Graphics 605             | 1     | i915       | 1C078E1FC5 |
| 8086:3185 | 1043:875e | Intel      | UHD Graphics 605             | 1     | i915       | FE95B7E800 |
| 8086:3582 | 8086:1977 | Intel      | 82852/855GM Integrated Gr... | 1     | i915       | 2A979257AB |
| 8086:3e90 | 17aa:3135 | Intel      | Coffee Lake UHD Graphics 610 | 1     | i915       | 766E275813 |
| 8086:3e92 | 17aa:312d | Intel      | UHD Graphics 630 (Desktop)   | 1     | i915       | 8ED3B0B386 |
| 8086:5902 | 103c:82a5 | Intel      | HD Graphics 610              | 1     | i915       | 9D7BDB2727 |
| 8086:5912 | 103c:829a | Intel      | HD Graphics 630              | 1     | i915       | 5899271C55 |
| 8086:5912 | 8086:5912 | Intel      | HD Graphics 630              | 1     | i915       | 5DD127A865 |
| 8086:5916 | 8086:2070 | Intel      | HD Graphics 620              | 1     | i915       | A8A0EB4EEE |
| 8086:5a84 | 8086:2212 | Intel      | Celeron N3350/Pentium N42... | 1     | i915       | 10E448E7B6 |
| 8086:5a85 | 19da:b325 | Intel      | HD Graphics 500              | 1     | i915       | C08536440A |
| 8086:a001 | 17aa:3605 | Intel      | Atom Processor D4xx/D5xx/... | 1     | i915       | F077B2F98E |
| 8086:a001 | 8086:4f4d | Intel      | Atom Processor D4xx/D5xx/... | 1     | i915       | FD127FD8BF |
| 8086:a001 | 8086:574d | Intel      | Atom Processor D4xx/D5xx/... | 1     | i915       | 4727851853 |
| 8086:a002 | 17aa:3605 | Intel      | Atom Processor D4xx/D5xx/... | 1     |            | F077B2F98E |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816c | 10ec:8168 | Realtek... | Virtual IPMI                 | 1     | ipmi_si    | 5DD127A865 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9def | 8086:2074 | Intel      | Cannon Point-LP Shared SRAM  | 21    |            | B039AEFD9E |
| 8086:9d21 | 8086:2068 | Intel      | Sunrise Point-LP PMC         | 18    |            | 145DFF2B67 |
| 8086:a121 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 9     |            | 275EDFBD40 |
| 8086:a121 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 8     |            | 071897D2C7 |
| 10de:0a88 |           | Nvidia     | MCP79 Memory Controller      | 5     |            | EEA609467F |
| 10de:0a89 |           | Nvidia     | MCP79 Memory Controller      | 5     |            | EEA609467F |
| 10de:0a98 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 5     |            | EEA609467F |
| 10de:0aa4 |           | Nvidia     | MCP79 Memory Controller      | 5     |            | EEA609467F |
| 8086:9d21 | 8086:2070 | Intel      | Sunrise Point-LP PMC         | 5     |            | 87F2F89679 |
| 8086:9d21 | 8086:2063 | Intel      | Sunrise Point-LP PMC         | 3     |            | 97355011D7 |
| 8086:a36f | 17aa:3135 | Intel      | Cannon Lake PCH Shared SRAM  | 3     |            | 92903CF555 |
| 10de:0d68 |           | Nvidia     | MCP89 Memory Controller      | 2     |            | E563DAD6EF |
| 10de:0d69 |           | Nvidia     | MCP89 Memory Controller      | 2     |            | E563DAD6EF |
| 10de:0d6d |           | Nvidia     | MCP89 Memory Controller      | 2     |            | E563DAD6EF |
| 10de:0d6e |           | Nvidia     | MCP89 Memory Controller      | 2     |            | E563DAD6EF |
| 10de:0d6f |           | Nvidia     | MCP89 Memory Controller      | 2     |            | E563DAD6EF |
| 10de:0d70 |           | Nvidia     | MCP89 Memory Controller      | 2     |            | E563DAD6EF |
| 10de:0d71 |           | Nvidia     | MCP89 Memory Controller      | 2     |            | E563DAD6EF |
| 10de:0d72 |           | Nvidia     | MCP89 Memory Controller      | 2     |            | E563DAD6EF |
| 10de:0d75 |           | Nvidia     | MCP89 Memory Controller      | 2     |            | E563DAD6EF |
| 10de:0d7b |           | Nvidia     | MCP89 Memory Controller      | 2     |            | E563DAD6EF |
| 8086:a121 | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 2CBDC3AD17 |
| 8086:a121 | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 4C9A2AA59C |
| 8086:a2a1 | 103c:829a | Intel      | 200 Series/Z370 Chipset F... | 2     |            | E0FB7EA560 |
| 8086:a2a1 | 103c:82a5 | Intel      | 200 Series/Z370 Chipset F... | 2     |            | 9D7BDB2727 |
| 8086:a36f | 17aa:3136 | Intel      | Cannon Lake PCH Shared SRAM  | 2     |            | 02ECA27578 |
| 8086:9def | 8086:7270 | Intel      | Cannon Point-LP Shared SRAM  | 1     |            | 6FD8E8E647 |
| 8086:a121 | 1019:9bc6 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 5DD127A865 |
| 8086:a121 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 305342DF08 |
| 8086:a36f | 17aa:312d | Intel      | Cannon Lake PCH Shared SRAM  | 1     |            | 8ED3B0B386 |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:5a88 |           | Intel      | Celeron N3350/Pentium N42... | 1     |            | 0BEDF4D656 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:15be | 8086:2074 | Intel      | Ethernet Connection (6) I... | 21    | e1000e     | B039AEFD9E |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 19    | r8169      | D999C674F1 |
| 8086:15d8 | 8086:2068 | Intel      | Ethernet Connection (4) I... | 18    | e1000e     | 145DFF2B67 |
| 14e4:1686 | 14e4:1686 | Broadco... | NetXtreme BCM57766 Gigabi... | 15    | tg3        | 75E8A3936D |
| 10ec:8168 | 8086:2060 | Realtek... | RTL8111/8168/8411 PCI Exp... | 13    | r8169      | 5D10E3F271 |
| 10ec:8168 | 19da:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 10    | r8169      | 4C4D77145B |
| 10ec:8168 | 8086:2072 | Realtek... | RTL8111/8168/8411 PCI Exp... | 10    | r8169      | BA6884F66B |
| 8086:15a3 | 8086:2057 | Intel      | Ethernet Connection (3) I... | 10    | e1000e     | 148534267A |
| 14e4:16b4 | 14e4:16b4 | Broadco... | NetXtreme BCM57765 Gigabi... | 9     | tg3        | E563DAD6EF |
| 8086:15b7 | 8086:0000 | Intel      | Ethernet Connection (2) I... | 9     | e1000e     | 275EDFBD40 |
| 8086:15b7 | 8086:2064 | Intel      | Ethernet Connection (2) I... | 8     | e1000e     | 071897D2C7 |
| 10de:0ab0 | 10de:cb79 | Nvidia     | MCP79 Ethernet               | 5     | forcedeth  | EEA609467F |
| 8086:156f | 8086:2070 | Intel      | Ethernet Connection I219-LM  | 5     | e1000e     | 87F2F89679 |
| 11ab:4362 | 11ab:5321 | Marvell... | 88E8053 PCI-E Gigabit Eth... | 4     | sky2       | E3E276A6C9 |
| 10ec:8168 | 8086:2067 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | C7F97B95C4 |
| 8086:1570 | 8086:2063 | Intel      | Ethernet Connection I219-V   | 3     | e1000e     | 97355011D7 |
| 8086:15bb | 17aa:3135 | Intel      | Ethernet Connection (7) I... | 3     | e1000e     | 92903CF555 |
| 10ec:8168 | 103c:82a5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 9D7BDB2727 |
| 10ec:8168 | 1458:e000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | A28492492A |
| 10ec:8168 | 1462:b120 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | F6DDC974E1 |
| 8086:15b7 | 103c:82c0 | Intel      | Ethernet Connection (2) I... | 2     | e1000e     | 2CBDC3AD17 |
| 8086:15bb | 17aa:3136 | Intel      | Ethernet Connection (7) I... | 2     | e1000e     | 02ECA27578 |
| 8086:15e3 | 103c:829a | Intel      | Ethernet Connection (5) I... | 2     | e1000e     | E0FB7EA560 |
| 10ec:8136 | 8086:0001 | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | FD127FD8BF |
| 10ec:8168 | 1028:080c | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 1C078E1FC5 |
| 10ec:8168 | 1043:8677 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | FE95B7E800 |
| 10ec:8168 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 5DD127A865 |
| 10ec:8168 | 17aa:30b5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | DF450C0459 |
| 10ec:8168 | 17aa:312f | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 36CC2B3CE6 |
| 10ec:8168 | 1b0a:015b | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 7E54F1E784 |
| 10ec:8168 | 1b50:4606 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 64F64657D5 |
| 10ec:8168 | 8086:d625 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 4727851853 |
| 14e4:1682 | 14e4:1682 | Broadco... | NetXtreme BCM57762 Gigabi... | 1     | tg3        | B71EA2BEC1 |
| 14e4:1692 | 14e4:9692 | Broadco... | NetLink BCM57780 Gigabit ... | 1     | tg3        | 0E6D540B44 |
| 14e4:16b0 | 106b:00f1 | Broadcom   | NetXtreme BCM57761 Gigabi... | 1     | tg3        | 029708EAF4 |
| 14e4:16b1 | 103c:17e2 | Broadco... | NetLink BCM57781 Gigabit ... | 1     | tg3        | 0A76049887 |
| 168c:abcd |           | Qualcom... | Osprey Emulation Wireless... | 1     |            | 76C675CD98 |
| 8086:1039 | 8086:3013 | Intel      | 82801DB PRO/100 VE (LOM) ... | 1     | e100       | 2A979257AB |
| 8086:155a | 8086:0000 | Intel      | Ethernet Connection I218-LM  | 1     | e1000e     | FF3CE414E4 |
| 8086:15a1 | 1043:85c4 | Intel      | Ethernet Connection (2) I... | 1     | e1000e     | B09664C500 |
| 8086:15a2 | 8086:2058 | Intel      | Ethernet Connection (3) I... | 1     | e1000e     | 4AB80B03C5 |
| 8086:15bc | 17aa:312d | Intel      | Ethernet Connection (7) I... | 1     | e1000e     | 8ED3B0B386 |
| 8086:15be | 8086:0000 | Intel      | Ethernet Connection (6) I... | 1     | e1000e     | 6FD8E8E647 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9df0 | 8086:0034 | Intel      | Cannon Point-LP CNVi [Wir... | 20    | iwlwifi    | B039AEFD9E |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 18    | iwlwifi    | 5D10E3F271 |
| 8086:24fd | 8086:9010 | Intel      | Wireless 8265 / 8275         | 16    | iwlwifi    | 145DFF2B67 |
| 8086:24f3 | 8086:9010 | Intel      | Wireless 8260                | 11    | iwlwifi    | 071897D2C7 |
| 14e4:4331 | 106b:010e | Broadco... | BCM4331 802.11a/b/g/n        | 10    | wl         | 75E8A3936D |
| 8086:31dc | 8086:02a4 | Intel      | Wireless-AC 1550i Wireles... | 10    | iwlwifi    | BA6884F66B |
| 8086:095a | 8086:9010 | Intel      | Wireless 7265                | 9     | iwlwifi    | 148534267A |
| 14e4:4331 | 106b:00e4 | Broadco... | BCM4331 802.11a/b/g/n        | 6     | wl         | 3419AE2627 |
| 14e4:4328 | 106b:0090 | Broadco... | BCM4321 802.11a/b/g/n        | 5     | ssb        | EEA609467F |
| 14e4:43a0 | 106b:013b | Broadco... | BCM4360 802.11ac Wireless... | 5     | wl         | BC577C8669 |
| 168c:001c | 106b:0086 | Qualcom... | AR242x / AR542x Wireless ... | 4     | ath5k      | E3E276A6C9 |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 4     | iwlwifi    | C7F97B95C4 |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 4     | iwlwifi    | A8A0EB4EEE |
| 10ec:8179 | 1a3b:1d38 | Realtek... | RTL8188EE Wireless Networ... | 2     | rtl8188ee  | D999C674F1 |
| 14e4:4353 | 106b:0093 | Broadco... | BCM43224 802.11a/b/g/n       | 2     | wl         | E563DAD6EF |
| 8086:0896 | 8086:5005 | Intel      | Centrino Wireless-N 130      | 2     | iwlwifi    | 49EF2577E1 |
| 8086:08b3 | 8086:0070 | Intel      | Wireless 3160                | 2     | iwlwifi    | 3486F30CEE |
| 8086:08b3 | 8086:8070 | Intel      | Wireless 3160                | 2     | iwlwifi    | 6157F936DB |
| 8086:3165 | 8086:8010 | Intel      | Wireless 3165                | 2     | iwlwifi    | 0BEDF4D656 |
| 8086:31dc | 8086:0264 | Intel      | Wireless-AC 1550i Wireles... | 2     | iwlwifi    | FE95B7E800 |
| 8086:a370 | 8086:0030 | Intel      | Wireless-AC 9560 [Jeffers... | 2     | iwlwifi    | 02ECA27578 |
| 10ec:8171 | 10ec:8171 | Realtek... | RTL8191SEvA Wireless LAN ... | 1     | rtl8192se  | BE63E554C5 |
| 10ec:8178 | 10ec:8191 | Realtek... | RTL8192CE PCIe Wireless N... | 1     | rtl8192ce  | 9314D29F45 |
| 10ec:8179 | 1a3b:219a | Realtek... | RTL8188EE Wireless Networ... | 1     | rtl8188ee  | F6DDC974E1 |
| 10ec:8723 | 10ec:0733 | Realtek... | RTL8723AE PCIe Wireless N... | 1     |            | 2F246CACD8 |
| 10ec:8723 | 1a3b:2114 | Realtek... | RTL8723AE PCIe Wireless N... | 1     | rtl8723ae  | B590007CCF |
| 10ec:b723 | 10ec:b723 | Realtek... | RTL8723BE PCIe Wireless N... | 1     | rtl8723be  | 64F64657D5 |
| 10ec:c821 | 17aa:c024 | Realtek... | RTL8821CE 802.11ac PCIe W... | 1     |            | 36CC2B3CE6 |
| 168c:0030 | 168c:3116 | Qualcom... | AR93xx Wireless Network A... | 1     | ath9k      | B09664C500 |
| 168c:0034 | 11ad:6611 | Qualcom... | AR9462 Wireless Network A... | 1     | ath9k      | 1CB9AE56DF |
| 1814:0781 | 1a3b:1059 | Ralink     | RT2790 Wireless 802.11n 1... | 1     | rt2800pci  | 037A3E45C7 |
| 1814:3290 | 1a3b:2b87 | Ralink     | RT3290 Wireless 802.11n 1... | 1     | rt2800pci  | 8D13B8BFE3 |
| 8086:0892 | 8086:0062 | Intel      | Centrino Wireless-N 135      | 1     | iwlwifi    | F8F1E1681B |
| 8086:08b1 | 8086:4060 | Intel      | Wireless 7260                | 1     | iwlwifi    | 30F524BC82 |
| 8086:08b1 | 8086:4070 | Intel      | Wireless 7260                | 1     | iwlwifi    | FF3CE414E4 |
| 8086:24f3 | 8086:0130 | Intel      | Wireless 8260                | 1     | iwlwifi    | EDB53070CD |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 1     | iwlwifi    | 766E275813 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 9     | iwlwifi    | 8ED3B0B386 |
| 8086:157b | 8086:0000 | Intel      | I210 Gigabit Network Conn... | 8     | igb        | 275EDFBD40 |
| 14e4:4331 | 14e4:4331 | Broadco... | BCM4331 802.11a/b/g/n        | 5     | wl         | 3419AE2627 |
| 8086:10fe | 17aa:3605 | Intel      | 82552 10/100 Network Conn... | 1     | e100       | F077B2F98E |
| 8086:1502 | 1043:844e | Intel      | 82579LM Gigabit Network C... | 1     | e1000e     | 9AFBFD107A |
| 8086:1502 | 8086:0000 | Intel      | 82579LM Gigabit Network C... | 1     | e1000e     | 2F246CACD8 |
| 8086:1503 | 1734:11d9 | Intel      | 82579V Gigabit Network Co... | 1     | e1000e     | FC67594808 |
| 8086:1539 | 8086:0000 | Intel      | I211 Gigabit Network Conn... | 1     | igb        | 1CB9AE56DF |
| 8086:422c | 8086:1301 | Intel      | Centrino Advanced-N 6200     | 1     | iwlwifi    | 494DE74E34 |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a126 |           | Intel      | 100 Series/C230 Series Ch... | 1     | intel_t... | C263278BF1 |

### Performance counters (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27a3 |           | Intel      | 945GM/GU Chipset Hardware... | 4     |            | E3E276A6C9 |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:16bc | 14e4:0000 | Broadco... | BCM57765/57785 SDXC/MMC C... | 24    | sdhci_pci  | 75E8A3936D |
| 8086:31cc | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 10    | sdhci_pci  | BA6884F66B |
| 1217:8621 | 8086:2073 | O2 Micro   | SD/MMC Card Reader Contro... | 9     | sdhci_pci  | 275EDFBD40 |
| 8086:2296 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 9     | sdhci_pci  | C7D9257057 |
| 1217:8621 | 8086:2064 | O2 Micro   | SD/MMC Card Reader Contro... | 7     | sdhci_pci  | 071897D2C7 |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 7     | sdhci_pci  | 0BEDF4D656 |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | sdhci_pci  | 0BEDF4D656 |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | sdhci_pci  | 0BEDF4D656 |
| 8086:9d2d | 8086:2063 | Intel      | Sunrise Point-LP Secure D... | 3     | sdhci_pci  | 97355011D7 |
| 8086:2294 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 2     | sdhci_pci  | F6DDC974E1 |
| 8086:2294 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 2     | sdhci_pci  | C7D9257057 |
| 1022:7806 | 19da:a261 | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | 8D13B8BFE3 |
| 8086:2294 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 1     | sdhci_pci  | BD1F4F70F7 |
| 8086:31cc | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | 1C078E1FC5 |
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | 6616869490 |
| 8086:31d0 | 8086:7270 | Intel      | SD Host Controller           | 1     | sdhci_pci  | 6616869490 |
| 8086:5acc | 19da:b325 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | C08536440A |
| 8086:5ad0 |           | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | C08536440A |
| 8086:9dc4 | 8086:2075 | Intel      | 300 Series Chipset SD Hos... | 1     | sdhci_pci  | 6FD8E8E647 |
| 8086:9df5 | 8086:2075 | Intel      | BayHubTech Integrated SD ... | 1     | sdhci_pci  | 6FD8E8E647 |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9da4 | 8086:2074 | Intel      | Cannon Point-LP SPI Contr... | 21    |            | B039AEFD9E |
| 8086:22c6 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 9     | i2c_des... | C7D9257057 |
| 8086:22c7 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 9     | i2c_des... | C7D9257057 |
| 8086:5ac8 |           | Intel      | Celeron N3350/Pentium N42... | 3     | pwm_lps... | C7F97B95C4 |
| 8086:a324 | 17aa:3135 | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | 92903CF555 |
| 8086:a324 | 17aa:3136 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 02ECA27578 |
| 8086:9da4 | 8086:2075 | Intel      | Cannon Point-LP SPI Contr... | 1     |            | 6FD8E8E647 |
| 8086:9dc5 | 8086:2075 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | 6FD8E8E647 |
| 8086:9de8 | 8086:2075 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | 6FD8E8E647 |
| 8086:9de9 | 8086:2075 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | 6FD8E8E647 |
| 8086:a324 | 17aa:312d | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 8ED3B0B386 |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d3d | 8086:2070 | Intel      | Sunrise Point-LP Active M... | 5     | serial     | 87F2F89679 |
| 8086:a363 | 17aa:3135 | Intel      | Cannon Lake PCH Active Ma... | 3     | serial     | 92903CF555 |
| 8086:a13d | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 2     | serial     | 2CBDC3AD17 |
| 8086:a2bd | 103c:829a | Intel      | 200 Series Chipset Family... | 2     | serial     | E0FB7EA560 |
| 8086:a363 | 17aa:3136 | Intel      | Cannon Lake PCH Active Ma... | 2     | serial     | 02ECA27578 |
| 10ec:816a | 10ec:8168 | Realtek... | Virtual COM1                 | 1     |            | 5DD127A865 |
| 10ec:816b | 10ec:8168 | Realtek... | RealManage COM2              | 1     |            | 5DD127A865 |
| 8086:1e3d | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 1     | serial     | 9AFBFD107A |
| 8086:9cbd | 8086:2058 | Intel      | Wildcat Point-LP KT Contr... | 1     | serial     | 4AB80B03C5 |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9df9 | 8086:2074 | Intel      | Cannon Point-LP Thermal C... | 21    | intel_p... | B039AEFD9E |
| 8086:9d31 | 8086:2068 | Intel      | Sunrise Point-LP Thermal ... | 18    | intel_p... | 145DFF2B67 |
| 8086:a127 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 9     | intel_lpss | 275EDFBD40 |
| 8086:a131 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 9     | intel_p... | 275EDFBD40 |
| 8086:a160 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 9     | intel_lpss | 275EDFBD40 |
| 8086:a161 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 9     | intel_lpss | 275EDFBD40 |
| 8086:a162 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 9     | intel_lpss | 275EDFBD40 |
| 8086:a131 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 8     | intel_p... | 071897D2C7 |
| 8086:5a8c |           | Intel      | Dynamic Platform and Ther... | 7     | process... | 0BEDF4D656 |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | 0BEDF4D656 |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | 0BEDF4D656 |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | 0BEDF4D656 |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | 0BEDF4D656 |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | 0BEDF4D656 |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | 0BEDF4D656 |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | 0BEDF4D656 |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | 0BEDF4D656 |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | 0BEDF4D656 |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | 0BEDF4D656 |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | 0BEDF4D656 |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | 0BEDF4D656 |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | 0BEDF4D656 |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | 0BEDF4D656 |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | intel_l... | 0BEDF4D656 |
| 8086:9d31 | 8086:2070 | Intel      | Sunrise Point-LP Thermal ... | 5     | intel_p... | 87F2F89679 |
| 8086:9d60 | 8086:2070 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 87F2F89679 |
| 8086:9d61 | 8086:2070 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 87F2F89679 |
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 4     | process... | 79E7DF4FDC |
| 8086:5aac | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | C7F97B95C4 |
| 8086:5abc |           | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | C7F97B95C4 |
| 8086:5ac2 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | C7F97B95C4 |
| 8086:5ac4 |           | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | C7F97B95C4 |
| 8086:5ac6 |           | Intel      | Celeron N3350/Pentium N42... | 4     | intel_l... | C7F97B95C4 |
| 8086:9d27 | 8086:2063 | Intel      | Sunrise Point-LP Serial I... | 3     | intel_l... | 97355011D7 |
| 8086:9d31 | 8086:2063 | Intel      | Sunrise Point-LP Thermal ... | 3     | intel_p... | 97355011D7 |
| 8086:a131 | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_p... | 2CBDC3AD17 |
| 8086:a131 | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_p... | 4C9A2AA59C |
| 8086:a2b1 | 103c:829a | Intel      | 200 Series PCH Thermal Su... | 2     |            | E0FB7EA560 |
| 8086:a2b1 | 103c:82a5 | Intel      | 200 Series PCH Thermal Su... | 2     |            | 9D7BDB2727 |
| 8086:1e24 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 1     |            | 2F246CACD8 |
| 8086:318c | 1043:875e | Intel      | Celeron/Pentium Silver Pr... | 1     |            | FE95B7E800 |
| 8086:31b4 | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 1C078E1FC5 |
| 8086:31ba | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 1C078E1FC5 |
| 8086:8c24 | 8086:7270 | Intel      | 8 Series Chipset Family T... | 1     | intel_p... | FF3CE414E4 |
| 8086:9df9 | 8086:2075 | Intel      | Cannon Point-LP Thermal C... | 1     | intel_p... | 6FD8E8E647 |
| 8086:a131 | 1019:9bc6 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | 5DD127A865 |
| 8086:a131 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     | intel_p... | 305342DF08 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9da3 | 8086:2074 | Intel      | Cannon Point-LP SMBus Con... | 21    | i801_smbus | B039AEFD9E |
| 8086:9d23 | 8086:2068 | Intel      | Sunrise Point-LP SMBus       | 18    | i2c_i801   | 145DFF2B67 |
| 8086:2292 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 15    | i2c_i801   | 5D10E3F271 |
| 8086:1e22 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 11    | i2c_i801   | 75E8A3936D |
| 8086:31d4 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 10    | i2c_i801   | BA6884F66B |
| 8086:9ca2 | 8086:2057 | Intel      | Wildcat Point-LP SMBus Co... | 10    | i2c_i801   | 148534267A |
| 8086:a123 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 9     | i801_smbus | 275EDFBD40 |
| 8086:a123 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 8     | i801_smbus | 071897D2C7 |
| 8086:1c22 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 7     | i2c_i801   | 3419AE2627 |
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 7     | i2c_i801   | 0BEDF4D656 |
| 10de:0aa2 | 10de:cb79 | Nvidia     | MCP79 SMBus                  | 5     | i2c_nfo... | EEA609467F |
| 8086:9c22 | 8086:7270 | Intel      | 8 Series SMBus Controller    | 5     | i2c_i801   | BC577C8669 |
| 8086:9d23 | 8086:2070 | Intel      | Sunrise Point-LP SMBus       | 5     | i2c_i801   | 87F2F89679 |
| 8086:27da | 8086:7270 | Intel      | NM10/ICH7 Family SMBus Co... | 4     | i2c_i801   | E3E276A6C9 |
| 8086:5ad4 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 4     | i2c_i801   | C7F97B95C4 |
| 8086:2292 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 3     | i2c_i801   | D999C674F1 |
| 8086:27da | 19da:a218 | Intel      | NM10/ICH7 Family SMBus Co... | 3     | i2c_i801   | 49EF2577E1 |
| 8086:9d23 | 8086:2063 | Intel      | Sunrise Point-LP SMBus       | 3     | i2c_i801   | 97355011D7 |
| 8086:a323 | 17aa:3135 | Intel      | Cannon Lake PCH SMBus Con... | 3     | i2c_i801   | 92903CF555 |
| 10de:0d79 | 10de:cb89 | Nvidia     | MCP89 SMBus                  | 2     |            | E563DAD6EF |
| 8086:0f12 | 8086:0f12 | Intel      | Atom Processor E3800 Seri... | 2     | i801_smbus | 9314D29F45 |
| 8086:2292 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 2     | i2c_i801   | F6DDC974E1 |
| 8086:a123 | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 2     | i2c_i801   | 2CBDC3AD17 |
| 8086:a123 | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 2     | i2c_i801   | 4C9A2AA59C |
| 8086:a2a3 | 103c:829a | Intel      | 200 Series/Z370 Chipset F... | 2     | i2c_i801   | E0FB7EA560 |
| 8086:a2a3 | 103c:82a5 | Intel      | 200 Series/Z370 Chipset F... | 2     | i2c_i801   | 9D7BDB2727 |
| 8086:a323 | 17aa:3136 | Intel      | Cannon Lake PCH SMBus Con... | 2     | i2c_i801   | 02ECA27578 |
| 1002:4385 | 103c:17e2 | AMD        | SBx00 SMBus Controller       | 1     | i2c_piix4  | 0A76049887 |
| 1002:4385 | 19da:a183 | AMD        | SBx00 SMBus Controller       | 1     | i2c_pii... | 037A3E45C7 |
| 1022:780b | 1022:780b | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | A28492492A |
| 1022:780b | 19da:a261 | AMD        | FCH SMBus Controller         | 1     | i2c_pii... | 8D13B8BFE3 |
| 1022:790b | 17aa:312f | AMD        | FCH SMBus Controller         | 1     | i2c_pii... | 36CC2B3CE6 |
| 8086:0f12 |           | Intel      | Atom Processor E3800 Seri... | 1     | i2c_i801   | 64F64657D5 |
| 8086:0f12 | 1071:0730 | Intel      | Atom Processor E3800 Seri... | 1     | i2c_i801   | BE63E554C5 |
| 8086:0f12 | 17aa:30b5 | Intel      | Atom Processor E3800 Seri... | 1     | i2c_i801   | DF450C0459 |
| 8086:1c22 | 1734:11ba | Intel      | 6 Series/C200 Series Chip... | 1     |            | FC67594808 |
| 8086:1c22 | 19da:b202 | Intel      | 6 Series/C200 Series Chip... | 1     | i2c_i801   | F8F1E1681B |
| 8086:1e22 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | 9AFBFD107A |
| 8086:1e22 | 19da:a247 | Intel      | 7 Series/C216 Chipset Fam... | 1     | i2c_i801   | 3486F30CEE |
| 8086:1e22 | 19da:b211 | Intel      | 7 Series/C216 Chipset Fam... | 1     | i2c_i801   | 4C4D77145B |
| 8086:1e22 | 1b0a:015b | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | 7E54F1E784 |
| 8086:2292 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 1     | i2c_i801   | BD1F4F70F7 |
| 8086:2292 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 6157F936DB |
| 8086:24c3 | 8086:1977 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | i2c_i801   | 2A979257AB |
| 8086:27da | 17aa:3605 | Intel      | NM10/ICH7 Family SMBus Co... | 1     |            | F077B2F98E |
| 8086:27da | 8086:4f4d | Intel      | NM10/ICH7 Family SMBus Co... | 1     | i2c_i801   | FD127FD8BF |
| 8086:27da | 8086:574d | Intel      | NM10/ICH7 Family SMBus Co... | 1     | i2c_i801   | 4727851853 |
| 8086:31d4 | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 1     |            | 1C078E1FC5 |
| 8086:31d4 | 1043:875e | Intel      | Celeron/Pentium Silver Pr... | 1     |            | FE95B7E800 |
| 8086:31d4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     |            | 6616869490 |
| 8086:5ad4 | 19da:b325 | Intel      | Celeron N3350/Pentium N42... | 1     | i2c_i801   | C08536440A |
| 8086:8c22 | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 1     | i2c_i801   | 4E3E10AE15 |
| 8086:8c22 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 1     | i2c_i801   | FF3CE414E4 |
| 8086:8ca2 | 1043:8534 | Intel      | 9 Series Chipset Family S... | 1     | i2c_i801   | B09664C500 |
| 8086:9c22 | 1458:5001 | Intel      | 8 Series SMBus Controller    | 1     | i2c_i801   | B590007CCF |
| 8086:9c22 | 19da:b239 | Intel      | 8 Series SMBus Controller    | 1     | i2c_i801   | 71373D2071 |
| 8086:9ca2 | 8086:2058 | Intel      | Wildcat Point-LP SMBus Co... | 1     | i2c_i801   | 4AB80B03C5 |
| 8086:9da3 | 8086:2075 | Intel      | Cannon Point-LP SMBus Con... | 1     |            | 6FD8E8E647 |
| 8086:a123 | 1019:9bc6 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 5DD127A865 |
| 8086:a123 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     | i2c_i801   | 305342DF08 |
| 8086:a323 | 17aa:312d | Intel      | Cannon Lake PCH SMBus Con... | 1     |            | 8ED3B0B386 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9dc8 | 8086:2074 | Intel      | Cannon Point-LP High Defi... | 21    | snd_hda... | B039AEFD9E |
| 8086:9d71 | 8086:2068 | Intel      | Sunrise Point-LP HD Audio    | 17    | snd_hda... | 145DFF2B67 |
| 8086:2284 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 15    | snd_hda... | 5D10E3F271 |
| 8086:1e20 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 11    | snd_hda... | 75E8A3936D |
| 8086:160c | 8086:2057 | Intel      | Broadwell-U Audio Controller | 10    | snd_hda... | 148534267A |
| 8086:3198 | 8086:2072 | Intel      | Smart Sound Technology (I... | 10    | snd_hda... | BA6884F66B |
| 8086:9ca0 | 8086:2057 | Intel      | Wildcat Point-LP High Def... | 10    | snd_hda... | 148534267A |
| 8086:a171 | 8086:2073 | Intel      | CM238 HD Audio Controller    | 9     | snd_hda... | 275EDFBD40 |
| 8086:a170 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 8     | snd_hda... | 071897D2C7 |
| 1002:ab08 | 8086:2073 | AMD        | Polaris 22 HDMI Audio        | 7     | snd_hda... | 275EDFBD40 |
| 8086:1c20 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 7     | snd_hda... | 3419AE2627 |
| 10de:0ac0 | 10de:cb79 | Nvidia     | MCP79 High Definition Audio  | 5     | snd_hda... | EEA609467F |
| 8086:0a0c | 106b:0141 | Intel      | Haswell-ULT HD Audio Cont... | 5     | snd_hda... | BC577C8669 |
| 8086:5a98 |           | Intel      | Celeron N3350/Pentium N42... | 5     | snd_hda... | 749D18335F |
| 8086:9c20 | 8086:7270 | Intel      | 8 Series HD Audio Controller | 5     | snd_hda... | BC577C8669 |
| 8086:9d71 | 8086:2070 | Intel      | Sunrise Point-LP HD Audio    | 5     | snd_hda... | 87F2F89679 |
| 8086:27d8 | 8384:7680 | Intel      | NM10/ICH7 Family High Def... | 4     | snd_hda... | E3E276A6C9 |
| 8086:5a98 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 4     | snd_hda... | C7F97B95C4 |
| 1002:aa90 | 0000:aa90 | AMD        | Turks HDMI Audio [Radeon ... | 3     | snd_hda... | 9898EDBAF1 |
| 10de:0e08 | 19da:2180 | Nvidia     | GF119 HDMI Audio Controller  | 3     | snd_hda... | 49EF2577E1 |
| 8086:2284 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 3     | snd_hda... | D999C674F1 |
| 8086:27d8 | 19da:a218 | Intel      | NM10/ICH7 Family High Def... | 3     | snd_hda... | 49EF2577E1 |
| 8086:9d70 | 8086:2063 | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | 97355011D7 |
| 8086:a348 | 17aa:3135 | Intel      | Cannon Lake PCH cAVS         | 3     | snd_hda... | 92903CF555 |
| 1002:ab08 | 8086:ab08 | AMD        | Polaris 22 HDMI Audio        | 2     | snd_hda... | 187506C88F |
| 10de:0d94 | 10de:cb89 | Nvidia     | MCP89 High Definition Audio  | 2     | snd_hda... | E563DAD6EF |
| 10de:0fbc | 103c:82c0 | Nvidia     | GM107 High Definition Aud... | 2     | snd_hda... | 2CBDC3AD17 |
| 10de:10f1 |           | Nvidia     | GP106 High Definition Aud... | 2     | snd_hda... | 4C9A2AA59C |
| 8086:0f04 | 8086:0f04 | Intel      | Atom Processor Z36xxx/Z37... | 2     | snd_hda... | 9314D29F45 |
| 8086:2284 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 2     | snd_hda... | F6DDC974E1 |
| 8086:a170 | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 2     | snd_hda... | 2CBDC3AD17 |
| 8086:a170 | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 2     | snd_hda... | 4C9A2AA59C |
| 8086:a2f0 | 103c:829a | Intel      | 200 Series PCH HD Audio      | 2     | snd_hda... | E0FB7EA560 |
| 8086:a2f0 | 103c:82a5 | Intel      | 200 Series PCH HD Audio      | 2     | snd_hda... | 9D7BDB2727 |
| 8086:a348 | 17aa:3136 | Intel      | Cannon Lake PCH cAVS         | 2     | snd_hda... | 02ECA27578 |
| 1002:1314 | 1002:1314 | AMD        | Wrestler HDMI Audio          | 1     | snd_hda... | 8D13B8BFE3 |
| 1002:1314 | 103c:17e2 | AMD        | Wrestler HDMI Audio          | 1     | snd_hda... | 0A76049887 |
| 1002:1314 | 19da:a183 | AMD        | Wrestler HDMI Audio          | 1     | snd_hda... | 037A3E45C7 |
| 1002:15b3 | 17aa:312f | AMD        | High Definition Audio Con... | 1     | snd_hda... | 36CC2B3CE6 |
| 1002:4383 | 103c:17e2 | AMD        | SBx00 Azalia (Intel HDA)     | 1     | snd_hda... | 0A76049887 |
| 1002:4383 | 19da:a125 | AMD        | SBx00 Azalia (Intel HDA)     | 1     | snd_hda... | 037A3E45C7 |
| 1002:9902 | 1458:a002 | AMD        | Trinity HDMI Audio Contro... | 1     | snd_hda... | A28492492A |
| 1002:aae0 | 8086:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 1     | snd_hda... | 6FD8E8E647 |
| 1022:157a | 17aa:312f | AMD        | Family 15h (Models 60h-6f... | 1     | snd_hda... | 36CC2B3CE6 |
| 1022:780d | 1458:a002 | AMD        | FCH Azalia Controller        | 1     | snd_hda... | A28492492A |
| 1022:780d | 19da:a261 | AMD        | FCH Azalia Controller        | 1     | snd_hda... | 8D13B8BFE3 |
| 10de:0fb9 | 10de:1264 | Nvidia     | GP107GL High Definition A... | 1     | snd_hda... | 92903CF555 |
| 10de:0fba | 3842:2951 | Nvidia     | GM206 High Definition Aud... | 1     | snd_hda... | FF3CE414E4 |
| 10de:0fbb | 1458:3672 | Nvidia     | GM204 High Definition Aud... | 1     | snd_hda... | B09664C500 |
| 10de:0fbb | 3842:2974 | Nvidia     | GM204 High Definition Aud... | 1     | snd_hda... | 9AFBFD107A |
| 1106:3288 | 1106:3288 | VIA Tec... | VT8237A/VT8251 HDA Contro... | 1     | snd_hda... | 0E6D540B44 |
| 8086:0a0c | 1458:5000 | Intel      | Haswell-ULT HD Audio Cont... | 1     | snd_hda... | B590007CCF |
| 8086:0a0c | 19da:b239 | Intel      | Haswell-ULT HD Audio Cont... | 1     | snd_hda... | 71373D2071 |
| 8086:0c0c | 19da:b220 | Intel      | Xeon E3-1200 v3/4th Gen C... | 1     | snd_hda... | 4E3E10AE15 |
| 8086:0f04 | 1071:0730 | Intel      | Atom Processor Z36xxx/Z37... | 1     | snd_hda... | BE63E554C5 |
| 8086:0f04 | 17aa:30b5 | Intel      | Atom Processor Z36xxx/Z37... | 1     | snd_hda... | DF450C0459 |
| 8086:0f04 | 1b50:5709 | Intel      | Atom Processor Z36xxx/Z37... | 1     | snd_hda... | 64F64657D5 |
| 8086:160c | 8086:2058 | Intel      | Broadwell-U Audio Controller | 1     | snd_hda... | 4AB80B03C5 |
| 8086:1c20 | 1734:11b0 | Intel      | 6 Series/C200 Series Chip... | 1     | snd_hda... | FC67594808 |
| 8086:1c20 | 19da:b202 | Intel      | 6 Series/C200 Series Chip... | 1     | snd_hda... | F8F1E1681B |
| 8086:1e20 | 1043:8415 | Intel      | 7 Series/C216 Chipset Fam... | 1     | snd_hda... | 9AFBFD107A |
| 8086:1e20 | 19da:a247 | Intel      | 7 Series/C216 Chipset Fam... | 1     | snd_hda... | 3486F30CEE |
| 8086:1e20 | 19da:b211 | Intel      | 7 Series/C216 Chipset Fam... | 1     | snd_hda... | 4C4D77145B |
| 8086:1e20 | 1b0a:015b | Intel      | 7 Series/C216 Chipset Fam... | 1     | snd_hda... | 7E54F1E784 |
| 8086:2284 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 1     | snd_hda... | BD1F4F70F7 |
| 8086:2284 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | snd_hda... | 6157F936DB |
| 8086:27d8 | 17aa:3605 | Intel      | NM10/ICH7 Family High Def... | 1     | snd_hda... | F077B2F98E |
| 8086:27d8 | 8086:d617 | Intel      | NM10/ICH7 Family High Def... | 1     | snd_hda... | FD127FD8BF |
| 8086:27d8 | 8086:d625 | Intel      | NM10/ICH7 Family High Def... | 1     | snd_hda... | 4727851853 |
| 8086:3198 | 1028:080c | Intel      | Smart Sound Technology (I... | 1     | snd_hda... | 1C078E1FC5 |
| 8086:3198 | 1043:871d | Intel      | Smart Sound Technology (I... | 1     | snd_hda... | FE95B7E800 |
| 8086:3198 | 8086:7270 | Intel      | Smart Sound Technology (I... | 1     | snd_hda... | 6616869490 |
| 8086:5a98 | 10ec:111e | Intel      | Celeron N3350/Pentium N42... | 1     | snd_hda... | 0BEDF4D656 |
| 8086:5a98 | 1d09:0101 | Intel      | Celeron N3350/Pentium N42... | 1     | snd_hda... | 69BB2EE752 |
| 8086:5a98 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | snd_hda... | 10E448E7B6 |
| 8086:8c20 | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 1     | snd_hda... | 4E3E10AE15 |
| 8086:8c20 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 1     | snd_hda... | FF3CE414E4 |
| 8086:8ca0 | 1043:860b | Intel      | 9 Series Chipset Family H... | 1     | snd_hda... | B09664C500 |
| 8086:9c20 | 1458:fa50 | Intel      | 8 Series HD Audio Controller | 1     | snd_hda... | B590007CCF |
| 8086:9c20 | 19da:b239 | Intel      | 8 Series HD Audio Controller | 1     | snd_hda... | 71373D2071 |
| 8086:9ca0 | 8086:2058 | Intel      | Wildcat Point-LP High Def... | 1     | snd_hda... | 4AB80B03C5 |
| 8086:9dc8 | 8086:2075 | Intel      | Cannon Point-LP High Defi... | 1     | snd_hda... | 6FD8E8E647 |
| 8086:a170 | 1019:9bc6 | Intel      | 100 Series/C230 Series Ch... | 1     | snd_hda... | 5DD127A865 |
| 8086:a170 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     | snd_hda... | 305342DF08 |
| 8086:a348 | 17aa:312d | Intel      | Cannon Lake PCH cAVS         | 1     | snd_hda... | 8ED3B0B386 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9dd3 | 8086:2074 | Intel      | Cannon Point-LP SATA Cont... | 21    | ahci       | B039AEFD9E |
| 8086:9d03 | 8086:2068 | Intel      | Sunrise Point-LP SATA Con... | 18    | ahci       | 145DFF2B67 |
| 8086:22a3 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 15    | ahci       | 5D10E3F271 |
| 8086:1e03 | 8086:7270 | Intel      | 7 Series Chipset Family 6... | 11    | ahci       | 75E8A3936D |
| 8086:31e3 | 8086:2072 | Intel      | SATA controller              | 10    | ahci       | BA6884F66B |
| 8086:9c83 | 8086:2057 | Intel      | Wildcat Point-LP SATA Con... | 10    | ahci       | 148534267A |
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 7     | ahci       | 0BEDF4D656 |
| 8086:9c03 | 8086:7270 | Intel      | 8 Series SATA Controller ... | 5     | ahci       | BC577C8669 |
| 8086:9d03 | 8086:2070 | Intel      | Sunrise Point-LP SATA Con... | 5     | ahci       | 87F2F89679 |
| 8086:a103 | 8086:2064 | Intel      | HM170/QM170 Chipset SATA ... | 5     | ahci       | 071897D2C7 |
| 8086:1c03 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 4     | ahci       | 3419AE2627 |
| 8086:5ae3 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 4     | ahci       | C7F97B95C4 |
| 10de:0ab9 | 10de:cb79 | Nvidia     | MCP79 AHCI Controller        | 3     | ahci       | 191BB34391 |
| 8086:22a3 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 3     | ahci       | D999C674F1 |
| 8086:9d03 | 8086:2063 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 97355011D7 |
| 8086:a352 | 17aa:3135 | Intel      | Cannon Lake PCH SATA AHCI... | 3     | ahci       | 92903CF555 |
| 10de:0d88 | 106b:cb89 | Nvidia     | MCP89 SATA Controller (AH... | 2     | ahci       | E563DAD6EF |
| 8086:0f23 | 8086:0f23 | Intel      | Atom Processor E3800 Seri... | 2     | ahci       | 9314D29F45 |
| 8086:22a3 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 2     | ahci       | F6DDC974E1 |
| 8086:27c1 | 19da:a218 | Intel      | NM10/ICH7 Family SATA Con... | 2     | ahci       | 49EF2577E1 |
| 8086:a102 | 19da:b333 | Intel      | Q170/Q150/B150/H170/H110/... | 2     | ahci       | 4C9A2AA59C |
| 8086:a103 | 8086:2073 | Intel      | HM170/QM170 Chipset SATA ... | 2     | ahci       | 532A0BFEBB |
| 8086:a282 | 103c:82a5 | Intel      | 200 Series PCH SATA contr... | 2     | ahci       | 9D7BDB2727 |
| 8086:a352 | 17aa:3136 | Intel      | Cannon Lake PCH SATA AHCI... | 2     | ahci       | 02ECA27578 |
| 1002:4390 | 103c:17e2 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 0A76049887 |
| 1002:4391 | 19da:a183 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 037A3E45C7 |
| 1022:7801 | 1458:b002 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | A28492492A |
| 1022:7801 | 19da:a261 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 8D13B8BFE3 |
| 1022:7901 | 17aa:312f | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 36CC2B3CE6 |
| 8086:0f23 |           | Intel      | Atom Processor E3800 Seri... | 1     | ahci       | 64F64657D5 |
| 8086:0f23 | 1071:0730 | Intel      | Atom Processor E3800 Seri... | 1     | ahci       | BE63E554C5 |
| 8086:0f23 | 17aa:30b5 | Intel      | Atom Processor E3800 Seri... | 1     | ahci       | DF450C0459 |
| 8086:1c02 | 1734:11ba | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | FC67594808 |
| 8086:1c02 | 19da:b202 | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | F8F1E1681B |
| 8086:1e02 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 1     | ahci       | 9AFBFD107A |
| 8086:1e03 | 19da:a247 | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | 3486F30CEE |
| 8086:1e03 | 19da:b211 | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | 4C4D77145B |
| 8086:1e03 | 1b0a:015b | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | 7E54F1E784 |
| 8086:22a3 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 1     | ahci       | BD1F4F70F7 |
| 8086:22a3 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | ahci       | 6157F936DB |
| 8086:27c1 | 17aa:3605 | Intel      | NM10/ICH7 Family SATA Con... | 1     | ahci       | F077B2F98E |
| 8086:27c1 | 8086:574d | Intel      | NM10/ICH7 Family SATA Con... | 1     | ahci       | 4727851853 |
| 8086:27c5 | 8086:7270 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 1     | ahci       | 5A02AA7966 |
| 8086:31e3 | 1028:080c | Intel      | SATA controller              | 1     | ahci       | 1C078E1FC5 |
| 8086:31e3 | 1043:875e | Intel      | SATA controller              | 1     | ahci       | FE95B7E800 |
| 8086:31e3 | 8086:7270 | Intel      | SATA controller              | 1     | ahci       | 6616869490 |
| 8086:5ae3 | 19da:b325 | Intel      | Celeron N3350/Pentium N42... | 1     | ahci       | C08536440A |
| 8086:8c02 | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | 4E3E10AE15 |
| 8086:8c02 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | FF3CE414E4 |
| 8086:8c82 | 1043:8534 | Intel      | 9 Series Chipset Family S... | 1     | ahci       | B09664C500 |
| 8086:9c03 | 1458:b002 | Intel      | 8 Series SATA Controller ... | 1     | ahci       | B590007CCF |
| 8086:9c03 | 19da:b239 | Intel      | 8 Series SATA Controller ... | 1     | ahci       | 71373D2071 |
| 8086:9c83 | 8086:2058 | Intel      | Wildcat Point-LP SATA Con... | 1     | ahci       | 4AB80B03C5 |
| 8086:9dd3 | 8086:2075 | Intel      | Cannon Point-LP SATA Cont... | 1     | ahci       | 6FD8E8E647 |
| 8086:a102 | 1019:9bc6 | Intel      | Q170/Q150/B150/H170/H110/... | 1     | ahci       | 5DD127A865 |
| 8086:a102 | 8086:7270 | Intel      | Q170/Q150/B150/H170/H110/... | 1     | ahci       | 305342DF08 |
| 8086:a282 | 103c:829a | Intel      | 200 Series PCH SATA contr... | 1     | ahci       | 5899271C55 |
| 8086:a352 | 17aa:312d | Intel      | Cannon Lake PCH SATA AHCI... | 1     | ahci       | 8ED3B0B386 |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27df | 8086:7270 | Intel      | 82801G (ICH7 Family) IDE ... | 4     | pata_acpi  | E3E276A6C9 |
| 8086:1c01 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 3     | ata_pii... | 9898EDBAF1 |
| 8086:27c4 | 8086:7270 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 3     | pata_acpi  | E3E276A6C9 |
| 10de:0ab5 | 10de:cb79 | Nvidia     | MCP79 SATA Controller        | 2     | ahci, p... | EEA609467F |
| 1002:439c | 19da:a183 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | pata_at... | 037A3E45C7 |
| 1022:780c | 19da:a261 | AMD        | FCH IDE Controller           | 1     | pata_at... | 8D13B8BFE3 |
| 1106:9001 | 1106:9001 | VIA Tec... | VX900 Serial ATA Controller  | 1     | pata_vi... | 0E6D540B44 |
| 8086:24cb | 8086:1977 | Intel      | 82801DB (ICH4) IDE Contro... | 1     | ata_pii... | 2A979257AB |
| 8086:27c0 | 19da:a218 | Intel      | NM10/ICH7 Family SATA Con... | 1     | ata_pii... | E907BA80AE |
| 8086:27c0 | 8086:4f4d | Intel      | NM10/ICH7 Family SATA Con... | 1     | ata_pii... | FD127FD8BF |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 20    | nvme       | B039AEFD9E |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 7     | nvme       | 275EDFBD40 |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 3     | nvme       | A11552D6EC |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 3     | nvme       | 145DFF2B67 |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 2     | nvme       | 74EE338F16 |
| 1987:5007 | 1987:5007 | Phison ... | E7 NVMe Controller           | 2     | nvme       | F9C39F6628 |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | Non-Volatile memory contr... | 2     | nvme       | 36CC2B3CE6 |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 2     | nvme       | 0B66BDFEE9 |
| c0a9:2263 | c0a9:2263 | Micron/... | P1 NVMe PCIe SSD             | 2     | nvme       | C96E6BC37C |
| 10ec:5760 | 5760:10ec | Realtek... | Realtek Non-Volatile memo... | 1     | nvme       | 8ED3B0B386 |
| 1179:011a | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 1     | nvme       | 02ECA27578 |
| 126f:2262 | 126f:2262 | Silicon... | Non-Volatile memory contr... | 1     | nvme       | 275EDFBD40 |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/PC SN720 NV... | 1     | nvme       | 92903CF555 |
| 2646:5008 | 2646:5008 | Kingsto... | Non-Volatile memory contr... | 1     | nvme       | 34958E67EC |
| 8086:2522 | 8086:3806 | Intel      | NVMe SSD Optane Series Co... | 1     | nvme       | BDA8F46AD6 |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2822 | 103c:82c0 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 2CBDC3AD17 |
| 8086:2822 | 103c:829a | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | E0FB7EA560 |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1911 | 8086:2074 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 21    |            | B039AEFD9E |
| 8086:1911 | 8086:2068 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 18    |            | 145DFF2B67 |
| 8086:1911 | 8086:2073 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 9     |            | 275EDFBD40 |
| 8086:1911 | 8086:2064 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 8     |            | 071897D2C7 |
| 8086:1513 | 2222:1111 | Intel      | CV82524 Thunderbolt Contr... | 7     | shpchp     | 3419AE2627 |
| 8086:156c |           | Intel      | DSL5520 Thunderbolt 2 NHI... | 5     | thunder... | BC577C8669 |
| 8086:1911 | 8086:2070 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 87F2F89679 |
| 8086:15de | 2222:1111 | Intel      | Controller                   | 3     | thunder... | C00059FE69 |
| 8086:1911 | 17aa:3135 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | 92903CF555 |
| 8086:1911 | 17aa:3136 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 02ECA27578 |
| 8086:1911 | 19da:b333 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 4C9A2AA59C |
| 8086:3190 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 2     |            | 4C465E5A03 |
| 8086:15d9 | 8086:2074 | Intel      | JHL6340 Thunderbolt 3 NHI... | 1     | thunder... | B71EA2BEC1 |
| 8086:1911 | 1019:9bc6 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 5DD127A865 |
| 8086:1911 | 17aa:312d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 8ED3B0B386 |
| 8086:1911 | 8086:2015 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 305342DF08 |
| 8086:3190 | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 1     |            | 1C078E1FC5 |
| 8086:3190 | 1043:875e | Intel      | Celeron/Pentium Silver Pr... | 1     |            | FE95B7E800 |
| 8086:3190 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     |            | 6616869490 |
| 8086:3584 | 8086:1977 | Intel      | 82852/82855 GM/GME/PM/GMV... | 1     |            | 2A979257AB |
| 8086:3585 | 8086:1977 | Intel      | 82852/82855 GM/GME/PM/GMV... | 1     |            | 2A979257AB |
| 8086:5a11 | 8086:2075 | Intel      | System peripheral            | 1     |            | 6FD8E8E647 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9ded | 8086:2074 | Intel      | Cannon Point-LP USB 3.1 x... | 21    | xhci_hcd   | B039AEFD9E |
| 8086:9d2f | 8086:2068 | Intel      | Sunrise Point-LP USB 3.0 ... | 18    | xhci_hcd   | 145DFF2B67 |
| 8086:1e26 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 11    | ehci_hc... | 75E8A3936D |
| 8086:1e2d | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 11    | ehci_hc... | 75E8A3936D |
| 8086:1e31 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 11    | xhci_hcd   | 75E8A3936D |
| 8086:31a8 | 8086:2072 | Intel      | USB Controller               | 10    | xhci_hcd   | BA6884F66B |
| 8086:9cb1 | 8086:2057 | Intel      | Wildcat Point-LP USB xHCI... | 10    | xhci_hcd   | 148534267A |
| 1b21:2142 | 8086:2073 | ASMedia... | ASM2142 USB 3.1 Host Cont... | 9     | xhci_hcd   | 275EDFBD40 |
| 8086:9ca6 | 8086:2057 | Intel      | Wildcat Point-LP USB EHCI... | 9     | ehci_pci   | 148534267A |
| 8086:a12f | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 9     | xhci_hcd   | 275EDFBD40 |
| 8086:22b5 |           | Intel      | Atom/Celeron/Pentium Proc... | 8     | xhci_hcd   | 5D10E3F271 |
| 8086:a12f | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 8     | xhci_hcd   | 071897D2C7 |
| 8086:1c26 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 7     | ehci_pci   | 3419AE2627 |
| 8086:1c27 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 7     | uhci_hcd   | 3419AE2627 |
| 8086:1c2c | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 7     | uhci_hcd   | 3419AE2627 |
| 8086:1c2d | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 7     | ehci_pci   | 3419AE2627 |
| 8086:22b5 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 7     | xhci_pci   | 76DC5FD237 |
| 8086:22b5 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 7     | xhci_hcd   | D999C674F1 |
| 8086:5aa8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 7     | xhci_hcd   | 0BEDF4D656 |
| 10de:0aa5 | 10de:cb79 | Nvidia     | MCP79 OHCI USB 1.1 Contro... | 5     | ohci_hc... | EEA609467F |
| 10de:0aa6 | 10de:cb79 | Nvidia     | MCP79 EHCI USB 2.0 Contro... | 5     | ehci_hc... | EEA609467F |
| 10de:0aa7 | 10de:cb79 | Nvidia     | MCP79 OHCI USB 1.1 Contro... | 5     | ohci_hc... | EEA609467F |
| 10de:0aa9 | 10de:cb79 | Nvidia     | MCP79 EHCI USB 2.0 Contro... | 5     | ehci_hc... | EEA609467F |
| 8086:0f35 | 8086:0f35 | Intel      | Atom Processor Z36xxx/Z37... | 5     | xhci_hcd   | 9314D29F45 |
| 8086:9c31 | 8086:7270 | Intel      | 8 Series USB xHCI HC         | 5     | xhci_hcd   | BC577C8669 |
| 8086:9d2f | 8086:2070 | Intel      | Sunrise Point-LP USB 3.0 ... | 5     | xhci_hcd   | 87F2F89679 |
| 8086:15db | 2222:1111 | Intel      | JHL6340 Thunderbolt 3 USB... | 4     | xhci_hcd   | C00059FE69 |
| 8086:15db | 8086:2074 | Intel      | JHL6340 Thunderbolt 3 USB... | 4     | xhci_hcd   | B039AEFD9E |
| 8086:27c8 | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 4     | uhci_hcd   | E3E276A6C9 |
| 8086:27c9 | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 4     | uhci_hcd   | E3E276A6C9 |
| 8086:27ca | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 4     | uhci_hcd   | E3E276A6C9 |
| 8086:27cb | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 4     | uhci_hcd   | E3E276A6C9 |
| 8086:27cc | 8086:7270 | Intel      | NM10/ICH7 Family USB2 EHC... | 4     | ehci_pci   | E3E276A6C9 |
| 8086:5aa8 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 4     | xhci_hcd   | C7F97B95C4 |
| 1b21:1242 | 1b21:1242 | ASMedia... | ASM1142 USB 3.1 Host Cont... | 3     | xhci_pci   | 4C9A2AA59C |
| 1b6f:7023 | 1b6f:7023 | Etron T... | EJ168 USB 3.0 Host Contro... | 3     | xhci_pci   | 49EF2577E1 |
| 8086:27c8 | 19da:a218 | Intel      | NM10/ICH7 Family USB UHCI... | 3     | uhci_hcd   | 49EF2577E1 |
| 8086:27c9 | 19da:a218 | Intel      | NM10/ICH7 Family USB UHCI... | 3     | uhci_hcd   | 49EF2577E1 |
| 8086:27ca | 19da:a218 | Intel      | NM10/ICH7 Family USB UHCI... | 3     | uhci_hcd   | 49EF2577E1 |
| 8086:27cb | 19da:a218 | Intel      | NM10/ICH7 Family USB UHCI... | 3     | uhci_hcd   | 49EF2577E1 |
| 8086:27cc | 19da:a218 | Intel      | NM10/ICH7 Family USB2 EHC... | 3     | ehci_hc... | 49EF2577E1 |
| 8086:9d2f | 8086:2063 | Intel      | Sunrise Point-LP USB 3.0 ... | 3     | xhci_pci   | 97355011D7 |
| 8086:a36d | 17aa:3135 | Intel      | Cannon Lake PCH USB 3.1 x... | 3     | xhci_hcd   | 92903CF555 |
| 10de:0d9c | 10de:cb89 | Nvidia     | MCP89 OHCI USB 1.1 Contro... | 2     | ohci_hc... | E563DAD6EF |
| 10de:0d9d | 10de:cb89 | Nvidia     | MCP89 EHCI USB 2.0 Contro... | 2     | ehci_hc... | E563DAD6EF |
| 1912:0015 | 19da:0194 | Renesas... | uPD720202 USB 3.0 Host Co... | 2     | xhci_pci   | 4C4D77145B |
| 8086:15b5 | 2222:1111 | Intel      | DSL6340 USB 3.1 Controlle... | 2     | xhci_hcd   | 071897D2C7 |
| 8086:22b5 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 2     | xhci_hcd   | F6DDC974E1 |
| 8086:a12f | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 2     | xhci_hcd   | 2CBDC3AD17 |
| 8086:a12f | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 2     | xhci_hcd   | 4C9A2AA59C |
| 8086:a2af | 103c:829a | Intel      | 200 Series/Z370 Chipset F... | 2     | xhci_hcd   | E0FB7EA560 |
| 8086:a2af | 103c:82a5 | Intel      | 200 Series/Z370 Chipset F... | 2     | xhci_hcd   | 9D7BDB2727 |
| 8086:a36d | 17aa:3136 | Intel      | Cannon Lake PCH USB 3.1 x... | 2     | xhci_hcd   | 02ECA27578 |
| 1002:4396 | 103c:17e2 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 1     | ehci_pci   | 0A76049887 |
| 1002:4396 | 19da:a183 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 1     | ehci_hc... | 037A3E45C7 |
| 1002:4397 | 103c:17e2 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1     | ohci_pci   | 0A76049887 |
| 1002:4397 | 19da:a183 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1     | ohci_hc... | 037A3E45C7 |
| 1002:4399 | 19da:a183 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1     | ohci_hc... | 037A3E45C7 |
| 1022:7807 | 1458:5004 | AMD        | FCH USB OHCI Controller      | 1     | ohci_pci   | A28492492A |
| 1022:7807 | 19da:a261 | AMD        | FCH USB OHCI Controller      | 1     | ohci_hc... | 8D13B8BFE3 |
| 1022:7808 | 1458:5004 | AMD        | FCH USB EHCI Controller      | 1     | ehci_pci   | A28492492A |
| 1022:7808 | 19da:a261 | AMD        | FCH USB EHCI Controller      | 1     | ehci_hc... | 8D13B8BFE3 |
| 1022:7809 | 1458:5004 | AMD        | FCH USB OHCI Controller      | 1     | ohci_pci   | A28492492A |
| 1022:7809 | 19da:a261 | AMD        | FCH USB OHCI Controller      | 1     | ohci_hc... | 8D13B8BFE3 |
| 1022:7812 | 19da:a261 | AMD        | FCH USB XHCI Controller      | 1     | xhci_pci   | 8D13B8BFE3 |
| 1022:7814 | 1458:5004 | AMD        | FCH USB XHCI Controller      | 1     | xhci_hcd   | A28492492A |
| 1022:7908 | 17aa:312f | AMD        | FCH USB EHCI Controller      | 1     | ehci_pci   | 36CC2B3CE6 |
| 1022:7914 | 17aa:312f | AMD        | FCH USB XHCI Controller      | 1     | xhci_hcd   | 36CC2B3CE6 |
| 1033:0194 | ffff:ffff | NEC Com... | uPD720200 USB 3.0 Host Co... | 1     | xhci_hcd   | 037A3E45C7 |
| 104c:8241 | 103c:17e2 | Texas I... | TUSB73x0 SuperSpeed USB 3... | 1     | xhci_hcd   | 0A76049887 |
| 104c:8241 | 1b0a:015b | Texas I... | TUSB73x0 SuperSpeed USB 3... | 1     | xhci_hcd   | 7E54F1E784 |
| 10ec:816d | 10ec:8168 | Realtek... | Realtek USB Controller       | 1     | ehci_pci   | 5DD127A865 |
| 1106:3038 | 1106:3038 | VIA Tec... | VT82xx/62xx UHCI USB 1.1 ... | 1     | uhci_hcd   | 0E6D540B44 |
| 1106:3104 | 1106:3104 | VIA Tec... | USB 2.0                      | 1     | ehci_pci   | 0E6D540B44 |
| 12d8:400e | 12d8:400e | Pericom... | PI7C9X442SL USB OHCI Cont... | 1     | ohci_hc... | 029708EAF4 |
| 12d8:400f | 12d8:400f | Pericom... | PI7C9X442SL USB EHCI Cont... | 1     | ehci_hc... | 029708EAF4 |
| 1912:0014 | ffff:ffff | Renesas... | uPD720201 USB 3.0 Host Co... | 1     | xhci_hcd   | 9AFBFD107A |
| 1912:0015 | 19da:0198 | Renesas... | uPD720202 USB 3.0 Host Co... | 1     | xhci_pci   | 3486F30CEE |
| 1b21:1142 | 103c:8190 | ASMedia... | ASM1042A USB 3.0 Host Con... | 1     | xhci_hcd   | B71EA2BEC1 |
| 8086:0f34 | 8086:0f34 | Intel      | Atom Processor Z36xxx/Z37... | 1     | ehci_pci   | CF866CE735 |
| 8086:0f35 |           | Intel      | Atom Processor Z36xxx/Z37... | 1     | xhci_hcd   | 64F64657D5 |
| 8086:0f35 | 1071:0730 | Intel      | Atom Processor Z36xxx/Z37... | 1     | xhci_hcd   | BE63E554C5 |
| 8086:0f35 | 17aa:30b5 | Intel      | Atom Processor Z36xxx/Z37... | 1     | xhci_hcd   | DF450C0459 |
| 8086:1c26 | 1734:11ba | Intel      | 6 Series/C200 Series Chip... | 1     | ehci_pci   | FC67594808 |
| 8086:1c26 | 19da:b202 | Intel      | 6 Series/C200 Series Chip... | 1     | ehci_hc... | F8F1E1681B |
| 8086:1c2d | 1734:11ba | Intel      | 6 Series/C200 Series Chip... | 1     | ehci_pci   | FC67594808 |
| 8086:1c2d | 19da:b202 | Intel      | 6 Series/C200 Series Chip... | 1     | ehci_hc... | F8F1E1681B |
| 8086:1e26 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci_pci   | 9AFBFD107A |
| 8086:1e26 | 19da:a247 | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci_hc... | 3486F30CEE |
| 8086:1e26 | 19da:b211 | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci_hc... | 4C4D77145B |
| 8086:1e26 | 1b0a:015b | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci_pci   | 7E54F1E784 |
| 8086:1e2d | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci_pci   | 9AFBFD107A |
| 8086:1e2d | 19da:a247 | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci_hc... | 3486F30CEE |
| 8086:1e2d | 19da:b211 | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci_hc... | 4C4D77145B |
| 8086:1e2d | 1b0a:015b | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci_pci   | 7E54F1E784 |
| 8086:1e31 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 1     | xhci_hcd   | 9AFBFD107A |
| 8086:22b5 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 1     | xhci_hcd   | BD1F4F70F7 |
| 8086:22b5 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | xhci_hcd   | 6157F936DB |
| 8086:24c2 | 8086:1977 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | uhci_hcd   | 2A979257AB |
| 8086:24c4 | 8086:1977 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | uhci_hcd   | 2A979257AB |

