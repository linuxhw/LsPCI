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
| 8086:9d84 | 8086:2074 | Intel      | Cannon Point-LP LPC Contr... | 130   |            | 7EEEAAA250 |
| 8086:9db8 | 8086:2074 | Intel      | Cannon Point-LP PCI Expre... | 128   | pcieport   | 7EEEAAA250 |
| 8086:9dbc | 8086:2074 | Intel      | Cannon Point-LP PCI Expre... | 128   | pcieport   | 7EEEAAA250 |
| 8086:9db0 | 8086:2074 | Intel      | Cannon Point-LP PCI Expre... | 127   | pcieport   | 7EEEAAA250 |
| 8086:9db6 | 8086:2074 | Intel      | Cannon Point-LP PCI Expre... | 127   | pcieport   | 7EEEAAA250 |
| 8086:3ed0 | 8086:2074 | Intel      | 8th Gen Core Processor Ho... | 92    | skl_uncore | 7EEEAAA250 |
| 8086:0f00 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 73    | iosf_mb... | 0D4AC42F55 |
| 8086:0f1c | 8086:0f1c | Intel      | Atom Processor Z36xxx/Z37... | 72    | lpc_ich    | 0D4AC42F55 |
| 8086:0284 | 8086:2081 | Intel      | Comet Lake PCH-LP LPC Pre... | 70    |            | 37E756FA81 |
| 8086:5904 | 8086:2068 | Intel      | Xeon E3-1200 v6/7th Gen C... | 70    | skl_uncore | 82B124D8C4 |
| 8086:9d10 | 8086:2068 | Intel      | Sunrise Point-LP PCI Expr... | 70    | pcieport   | 82B124D8C4 |
| 8086:9d4e | 8086:2068 | Intel      | Sunrise Point LPC Control... | 70    |            | 82B124D8C4 |
| 8086:02b5 | 8086:2081 | Intel      | Comet Lake PCH-LP PCIe Po... | 68    | pcieport   | 37E756FA81 |
| 8086:02bc | 8086:2081 | Intel      | Comet Lake PCI Express Ro... | 68    | pcieport   | 37E756FA81 |
| 8086:15e7 | 8086:2081 | Intel      | JHL7540 Thunderbolt 3 Bri... | 68    | pcieport   | 37E756FA81 |
| 8086:9d17 | 8086:2068 | Intel      | Sunrise Point-LP PCI Expr... | 68    | pcieport   | 82B124D8C4 |
| 8086:9d15 | 8086:2068 | Intel      | Sunrise Point-LP PCI Expr... | 67    | pcieport   | 82B124D8C4 |
| 8086:02b0 | 8086:2081 | Intel      | Comet Lake PCI Express Ro... | 53    | pcieport   | 37E756FA81 |
| 104c:823e |           | Texas I... | XIO2213A/B/XIO2221 PCI Ex... | 47    | shpchp     | 8E878489D3 |
| 8086:1e10 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 46    | pcieport   | 4D3FECA2AC |
| 8086:1e12 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 46    | pcieport   | 4D3FECA2AC |
| 8086:1e14 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 44    | pcieport   | 4D3FECA2AC |
| 8086:1547 | 2222:1111 | Intel      | DSL3510 Thunderbolt Contr... | 43    | pcieport   | 4D3FECA2AC |
| 8086:1604 | 8086:2057 | Intel      | Broadwell-U Host Bridge -OPI | 43    | bdw_uncore | 1B9BEEAF2D |
| 8086:1e57 | 8086:7270 | Intel      | HM77 Express Chipset LPC ... | 43    | lpc_ich    | B18B29EED7 |
| 8086:9c90 | 8086:2057 | Intel      | Wildcat Point-LP PCI Expr... | 42    | pcieport   | 1B9BEEAF2D |
| 8086:9cc3 | 8086:2057 | Intel      | Wildcat Point-LP LPC Cont... | 42    | lpc_ich    | 1B9BEEAF2D |
| 8086:5ae8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 41    | lpc_ich    | D831E8693D |
| 8086:5af0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 41    |            | D831E8693D |
| 8086:9b51 | 8086:2081 | Intel      | Comet Lake-U v1 6c Host B... | 41    | skl_uncore | 37E756FA81 |
| 8086:9c96 | 8086:2057 | Intel      | Wildcat Point-LP PCI Expr... | 41    | pcieport   | 1B9BEEAF2D |
| 8086:5af0 |           | Intel      | Celeron N3350/Pentium N42... | 39    |            | B1C4AF0594 |
| 8086:0f48 | 8086:0f48 | Intel      | Atom Processor E3800 Seri... | 38    | pcieport   | 0D4AC42F55 |
| 8086:3ecc | 8086:2074 | Intel      | Coffee Lake Host Bridge/D... | 38    | skl_uncore | D699FF84BA |
| 8086:0f4a | 8086:0f4a | Intel      | Atom Processor E3800 Seri... | 37    | pcieport   | D27D622754 |
| 8086:0f4c | 8086:0f4c | Intel      | Atom Processor E3800 Seri... | 37    | pcieport   | 0D4AC42F55 |
| 8086:0f4e | 8086:0f4e | Intel      | Atom Processor E3800 Seri... | 36    | pcieport   | D27D622754 |
| 8086:1513 |           | Intel      | CV82524 Thunderbolt Contr... | 35    | pcieport   | 8E878489D3 |
| 8086:1901 | 8086:2073 | Intel      | 6th-10th Gen Core Process... | 35    | pcieport   | 507FBFC464 |
| 8086:1905 | 8086:2073 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 35    | pcieport   | 507FBFC464 |
| 8086:1909 | 8086:2073 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 35    | pcieport   | 507FBFC464 |
| 8086:5910 | 8086:2073 | Intel      | Xeon E3-1200 v6/7th Gen C... | 35    | skl_uncore | 507FBFC464 |
| 8086:a110 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 35    | pcieport   | 507FBFC464 |
| 8086:a114 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 35    | pcieport   | 507FBFC464 |
| 8086:a152 | 8086:2073 | Intel      | HM175 Chipset LPC/eSPI Co... | 35    |            | 507FBFC464 |
| 8086:15da | 8086:2074 | Intel      | JHL6340 Thunderbolt 3 Bri... | 34    | pcieport   | 0C063B9772 |
| 8086:2280 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 34    | iosf_mb... | 127B977658 |
| 8086:229c | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 34    | lpc_ich    | 127B977658 |
| 8086:22c8 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 34    | pcieport   | 127B977658 |
| 8086:22ca | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 34    | pcieport   | 127B977658 |
| 8086:31da | 8086:2072 | Intel      | Gemini Lake PCI Express R... | 34    | pcieport   | C1F78B36E0 |
| 8086:31e8 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 34    |            | C1F78B36E0 |
| 8086:31f0 | 8086:2072 | Intel      | Gemini Lake Host Bridge      | 34    |            | C1F78B36E0 |
| 8086:1c10 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 33    | pcieport   | 8E878489D3 |
| 8086:1c12 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 33    | pcieport   | 8E878489D3 |
| 8086:1c14 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 33    | pcieport   | 8E878489D3 |
| 8086:1c49 | 8086:7270 | Intel      | HM65 Express Chipset LPC ... | 33    | lpc_ich    | 8E878489D3 |
| 8086:31d8 | 8086:2072 | Intel      | Gemini Lake PCI Express R... | 33    | pcieport   | C1F78B36E0 |
| 8086:0a04 | 106b:0141 | Intel      | Haswell-ULT DRAM Controller  | 32    | hsw_uncore | A790DE17AA |
| 8086:5ada | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 32    | pcieport   | B1C4AF0594 |
| 8086:5ae8 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 32    | lpc_ich    | B1C4AF0594 |
| 8086:9c10 | 8086:7270 | Intel      | 8 Series PCI Express Root... | 32    | pcieport   | A790DE17AA |
| 8086:9c14 | 8086:7270 | Intel      | 8 Series PCI Express Root... | 32    | pcieport   | A790DE17AA |
| 8086:9c16 | 8086:7270 | Intel      | 8 Series PCI Express Root... | 32    | pcieport   | A790DE17AA |
| 8086:9c18 | 8086:7270 | Intel      | 8 Series PCI Express Root... | 32    | pcieport   | A790DE17AA |
| 8086:9c43 | 8086:7270 | Intel      | 8 Series LPC Controller      | 32    | lpc_ich    | A790DE17AA |
| 8086:a112 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 32    | pcieport   | 507FBFC464 |
| 8086:22cc | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 31    | pcieport   | 127B977658 |
| 8086:9d18 | 8086:2068 | Intel      | Sunrise Point-LP PCI Expr... | 31    | pcieport   | 82B124D8C4 |
| 8086:a111 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 31    | pcieport   | 507FBFC464 |
| 8086:5ad8 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 30    | pcieport   | B1C4AF0594 |
| 8086:a118 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 30    | pcieport   | 507FBFC464 |
| 1022:1448 |           | AMD        | Renoir Device 24: Function 0 | 29    |            | 4BA408D68C |
| 1022:1449 |           | AMD        | Renoir Device 24: Function 1 | 29    |            | 4BA408D68C |
| 1022:144a |           | AMD        | Renoir Device 24: Function 2 | 29    |            | 4BA408D68C |
| 1022:144b |           | AMD        | Renoir Device 24: Function 3 | 29    | k10temp    | 4BA408D68C |
| 1022:144c |           | AMD        | Renoir Device 24: Function 4 | 29    |            | 4BA408D68C |
| 1022:144d |           | AMD        | Renoir Device 24: Function 5 | 29    |            | 4BA408D68C |
| 1022:144e |           | AMD        | Renoir Device 24: Function 6 | 29    |            | 4BA408D68C |
| 1022:144f |           | AMD        | Renoir Device 24: Function 7 | 29    |            | 4BA408D68C |
| 1022:1630 | 1022:1630 | AMD        | Renoir/Cezanne Root Complex  | 29    |            | 4BA408D68C |
| 1022:1632 |           | AMD        | Renoir PCIe Dummy Host Br... | 29    |            | 4BA408D68C |
| 1022:1635 | 1022:1635 | AMD        | Renoir Internal PCIe GPP ... | 29    | pcieport   | 4BA408D68C |
| 8086:156d |           | Intel      | DSL5520 Thunderbolt 2 Bri... | 29    | pcieport   | AE1729D840 |
| 8086:229c | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 29    | lpc_ich    | FD46C16BB7 |
| 8086:5ad9 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 29    | pcieport   | B1C4AF0594 |
| 8086:2280 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 28    | iosf_mb... | FD46C16BB7 |
| 8086:22c8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 28    | pcieport   | FD46C16BB7 |
| 8086:0151 | 106b:00ff | Intel      | Xeon E3-1200 v2/3rd Gen C... | 25    | pcieport   | B18B29EED7 |
| 8086:0154 | 106b:00ff | Intel      | 3rd Gen Core processor DR... | 25    | ivb_uncore | B18B29EED7 |
| 8086:1910 | 8086:2064 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 25    | skl_uncore | FA1CECCEE5 |
| 8086:a110 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 25    | pcieport   | FA1CECCEE5 |
| 8086:a14e | 8086:2064 | Intel      | HM170 Chipset LPC/eSPI Co... | 25    |            | FA1CECCEE5 |
| 8086:5ad8 |           | Intel      | Celeron N3350/Pentium N42... | 24    | pcieport   | D831E8693D |
| 8086:a114 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 24    | pcieport   | FA1CECCEE5 |
| 8086:a111 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 23    | pcieport   | FA1CECCEE5 |
| 8086:a112 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 23    | pcieport   | FA1CECCEE5 |
| 1022:1452 |           | AMD        | Family 17h (Models 00h-1f... | 21    |            | 5981A4A25B |
| 1022:15e8 |           | AMD        | Raven/Raven2 Device 24: F... | 21    |            | 5981A4A25B |
| 1022:15e9 |           | AMD        | Raven/Raven2 Device 24: F... | 21    |            | 5981A4A25B |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:522a | 8086:2074 | Realtek... | RTS522A PCI Express Card ... | 127   | rtsx_pci   | 7EEEAAA250 |
| 10ec:5229 | 8086:2068 | Realtek... | RTS5229 PCI Express Card ... | 68    | rtsx_pci   | 82B124D8C4 |
| 10ec:5229 | 8086:2072 | Realtek... | RTS5229 PCI Express Card ... | 33    | rtsx_pci   | C1F78B36E0 |
| 10ec:5229 | 8086:2067 | Realtek... | RTS5229 PCI Express Card ... | 30    | rtsx_pci   | B1C4AF0594 |
| 10ec:525a | 8086:3004 | Realtek... | RTS525A PCI Express Card ... | 8     | rtsx_pci   | 0279A35638 |
| 10ec:5229 | 10ec:5229 | Realtek... | RTS5229 PCI Express Card ... | 3     | rtsx_pci   | 45B14891D4 |
| 10ec:525a | 10ec:525a | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx_pci   | 7F8E6D2DA9 |
| 10ec:522a | 103c:815a | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | 7D65A83025 |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0aa3 | 10de:cb79 | Nvidia     | MCP79 Co-processor           | 19    | nvidia     | 8699437E9E |
| 10de:0d7a | 10de:cb89 | Nvidia     | MCP89 Co-Processor           | 14    |            | CFCED2BB90 |
| 8086:1f18 | 8086:0000 | Intel      | Atom processor C2000 QAT     | 2     |            | C1D37659C1 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9de0 | 8086:2074 | Intel      | Cannon Point-LP MEI Contr... | 130   | mei_me     | 7EEEAAA250 |
| 8086:02e0 | 8086:2081 | Intel      | Comet Lake Management Eng... | 70    | mei_me     | 37E756FA81 |
| 8086:9d3a | 8086:2068 | Intel      | Sunrise Point-LP CSME HEC... | 70    | mei_me     | 82B124D8C4 |
| 8086:1e3a | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 46    | mei_me     | 4D3FECA2AC |
| 8086:9cba | 8086:2057 | Intel      | Wildcat Point-LP MEI Cont... | 43    | mei_me     | 1B9BEEAF2D |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 41    | mei_me     | D831E8693D |
| 8086:5a9a |           | Intel      | Celeron N3350/Pentium N42... | 39    | mei_me     | B1C4AF0594 |
| 8086:a13a | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 35    | mei_me     | 507FBFC464 |
| 8086:319a | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 34    | mei_me     | C1F78B36E0 |
| 8086:1c3a | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 33    | mei_me     | 8E878489D3 |
| 8086:9c3a | 8086:7270 | Intel      | 8 Series HECI #0             | 32    | mei_me     | A790DE17AA |
| 8086:a13a | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 25    | mei_me     | FA1CECCEE5 |
| 8086:9d3a | 8086:2063 | Intel      | Sunrise Point-LP CSME HEC... | 15    | mei_me     | 38571FCFB9 |
| 8086:9d3a | 8086:2070 | Intel      | Sunrise Point-LP CSME HEC... | 14    | mei_me     | CBF00091FA |
| 8086:a360 | 17aa:312d | Intel      | Cannon Lake PCH HECI Cont... | 13    | mei_me     | ACBB96BA48 |
| 8086:319a | 1043:875e | Intel      | Celeron/Pentium Silver Pr... | 10    | mei_me     | 9D5F2807CE |
| 8086:5a9c |           | Intel      | Communication controller     | 9     |            | 23BDDBF63A |
| 8086:5a9e |           | Intel      | Communication controller     | 9     |            | 23BDDBF63A |
| 8086:319a | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 8     | mei_me     | 94025849E2 |
| 8086:9cba | 8086:7270 | Intel      | Wildcat Point-LP MEI Cont... | 8     | mei_me     | 0A76AC3FB8 |
| 8086:a0e0 | 8086:3004 | Intel      | Tiger Lake-LP Management ... | 8     | mei_me     | 0279A35638 |
| 8086:a360 | 17aa:3135 | Intel      | Cannon Lake PCH HECI Cont... | 8     | mei_me     | C43EF85B97 |
| 8086:9d3a | 8086:1999 | Intel      | Sunrise Point-LP CSME HEC... | 7     | mei_me     | 1219FB4CEF |
| 8086:a328 | 8086:7270 | Intel      | Cannon Lake PCH Serial IO... | 7     | intel_l... | D09823163E |
| 8086:a360 | 8086:7270 | Intel      | Cannon Lake PCH HECI Cont... | 7     | mei_me     | D09823163E |
| 8086:9de0 | 17aa:314d | Intel      | Cannon Point-LP MEI Contr... | 6     | mei_me     | BD2F6222E5 |
| 8086:a13a | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 6     | mei_me     | CC099348C2 |
| 8086:a360 | 17aa:3136 | Intel      | Cannon Lake PCH HECI Cont... | 6     | mei_me     | 2A2C128E48 |
| 8086:a2ba | 103c:829a | Intel      | 200 Series PCH CSME HECI #1  | 5     | mei_me     | 1F3D092233 |
| 8086:a328 | 8086:2089 | Intel      | Cannon Lake PCH Serial IO... | 5     | intel_l... | 2EB74A58D2 |
| 8086:a360 | 8086:2089 | Intel      | Cannon Lake PCH HECI Cont... | 5     | mei_me     | 2EB74A58D2 |
| 8086:02e0 | 1043:87bd | Intel      | Comet Lake Management Eng... | 4     | mei_me     | 7A01C63401 |
| 8086:1e3a | 19da:b211 | Intel      | 7 Series/C216 Chipset Fam... | 4     | mei_me     | EFBBD0C3F8 |
| 8086:8c3a | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 4     | mei_me     | FCAA602427 |
| 8086:9cba | 8086:2058 | Intel      | Wildcat Point-LP MEI Cont... | 4     | mei_me     | 6E19619F29 |
| 8086:a13a | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 4     | mei_me     | AC904E9BCB |
| 8086:a2ba | 103c:82a5 | Intel      | 200 Series PCH CSME HECI #1  | 4     | mei_me     | 08B98B6A88 |
| 8086:02e0 | 8086:7270 | Intel      | Comet Lake Management Eng... | 3     | mei_me     | 1155D58828 |
| 8086:319a | 8086:319a | Intel      | Celeron/Pentium Silver Pr... | 3     | mei_me     | C87DFAAC1F |
| 8086:5a9a | 8086:5a9a | Intel      | Celeron N3350/Pentium N42... | 3     | mei_me     | 9AA58951EA |
| 8086:a13a | 15d9:0898 | Intel      | 100 Series/C230 Series Ch... | 3     | mei_me     | 8D4CBF243D |
| 8086:a13a | 8086:1999 | Intel      | 100 Series/C230 Series Ch... | 3     | mei_me     | CA900F89D0 |
| 8086:a13b | 15d9:0898 | Intel      | 100 Series/C230 Series Ch... | 3     | mei_me     | 8D4CBF243D |
| 8086:06e0 | 103c:8710 | Intel      | Comet Lake HECI Controller   | 2     | mei_me     | B2A212246B |
| 8086:06e0 | 19da:b440 | Intel      | Comet Lake HECI Controller   | 2     | mei_me     | 57676DE735 |
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
| 8086:9da8 | 8086:2075 | Intel      | Cannon Point-LP Serial IO... | 2     | intel_lpss | D9AC661777 |
| 8086:9de0 | 1043:8790 | Intel      | Cannon Point-LP MEI Contr... | 2     | mei_me     | 45389EF622 |
| 8086:9de0 | 17aa:314c | Intel      | Cannon Point-LP MEI Contr... | 2     | mei_me     | 0F66B49A44 |
| 8086:9de0 | 8086:2075 | Intel      | Cannon Point-LP MEI Contr... | 2     | mei_me     | D9AC661777 |
| 8086:9de0 | 8086:2079 | Intel      | Cannon Point-LP MEI Contr... | 2     | mei_me     | 45B14891D4 |
| 8086:a0e0 | 8086:2090 | Intel      | Tiger Lake-LP Management ... | 2     | mei_me     | 7F8E6D2DA9 |
| 8086:a0e0 | 8086:3002 | Intel      | Tiger Lake-LP Management ... | 2     | mei_me     | 3738610B69 |
| 8086:a13a | 1019:9bc6 | Intel      | 100 Series/C230 Series Ch... | 2     | mei_me     | 7101BAED7A |
| 8086:a2ba | 17aa:3111 | Intel      | 200 Series PCH CSME HECI #1  | 2     | mei_me     | A89ECD0B5F |
| 8086:a328 | 19da:b411 | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | CF60BF6309 |
| 8086:a328 | 8086:2088 | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | 2AE39C4439 |
| 8086:a360 | 103c:8458 | Intel      | Cannon Lake PCH HECI Cont... | 2     | mei_me     | 87E6E38B4A |
| 8086:a360 | 19da:b411 | Intel      | Cannon Lake PCH HECI Cont... | 2     | mei_me     | CF60BF6309 |
| 8086:a360 | 8086:2088 | Intel      | Cannon Lake PCH HECI Cont... | 2     | mei_me     | 2AE39C4439 |
| 8086:06e0 | 103c:871a | Intel      | Comet Lake HECI Controller   | 1     | mei_me     | F74885CE0C |
| 8086:06e0 | 103c:8755 | Intel      | Comet Lake HECI Controller   | 1     |            | 334ABF8C53 |
| 8086:06e0 | 17aa:316e | Intel      | Comet Lake HECI Controller   | 1     | mei_me     | 7146ACBC96 |
| 8086:06e0 | 17aa:3172 | Intel      | Comet Lake HECI Controller   | 1     | mei_me     | 3E09AE8DEE |
| 8086:06e0 | 17aa:3307 | Intel      | Comet Lake HECI Controller   | 1     | mei_me     | D99E47E84D |
| 8086:0f0a | 8086:0f0a | Intel      | Atom Processor Z36xxx/Z37... | 1     | 8250_lpss  | A968EF1DD8 |
| 8086:0f0c | 8086:0f0c | Intel      | Atom Processor Z36xxx/Z37... | 1     | 8250_lpss  | A968EF1DD8 |
| 8086:1c3a | 1734:11ba | Intel      | 6 Series/C200 Series Chip... | 1     | mei_me     | FC67594808 |
| 8086:1c3a | 19da:a217 | Intel      | 6 Series/C200 Series Chip... | 1     | mei_me     | 0909932423 |
| 8086:1e3a | 19da:a246 | Intel      | 7 Series/C216 Chipset Fam... | 1     | mei_me     | BD2FB45ED8 |
| 8086:1e3a | 1b0a:015b | Intel      | 7 Series/C216 Chipset Fam... | 1     | mei_me     | 7E54F1E784 |
| 8086:228a | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | 8250_lpss  | 10C1838B9D |
| 8086:228c | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | 8250_lpss  | 10C1838B9D |
| 8086:4da8 | 1043:8813 | Intel      | Jasper Lake LPSS: UART Co... | 1     | intel_l... | 4EBA944D40 |
| 8086:4de0 | 1043:8813 | Intel      | Management Engine Interface  | 1     | mei_me     | 4EBA944D40 |
| 8086:8c3a | 19da:b206 | Intel      | 8 Series/C220 Series Chip... | 1     | mei_me     | 25982E107F |
| 8086:8c3a | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 1     | mei_me     | FF3CE414E4 |
| 8086:9c3a | 1458:5001 | Intel      | 8 Series HECI #0             | 1     | mei_me     | E6FEB379A4 |
| 8086:9c3a | 19da:b213 | Intel      | 8 Series HECI #0             | 1     | mei_me     | 2290F44E04 |
| 8086:9c3a | 19da:b248 | Intel      | 8 Series HECI #0             | 1     | mei_me     | D521E3AD79 |
| 8086:9cba | 19da:b282 | Intel      | Wildcat Point-LP MEI Cont... | 1     | mei_me     | 493278D567 |
| 8086:9cba | 8086:9cba | Intel      | Wildcat Point-LP MEI Cont... | 1     | mei_me     | 1CAA0B4224 |
| 8086:9de0 | 17aa:3144 | Intel      | Cannon Point-LP MEI Contr... | 1     | mei_me     | 8D0F1F5E39 |
| 8086:a0e0 | 8086:2091 | Intel      | Tiger Lake-LP Management ... | 1     | mei_me     | BD9CFC6A29 |
| 8086:a0e0 | 8086:3003 | Intel      | Tiger Lake-LP Management ... | 1     | mei_me     | ABC31CEA35 |
| 8086:a0e0 | 8086:3013 | Intel      | Tiger Lake-LP Management ... | 1     | mei_me     | 66A02F462F |
| 8086:a2ba | 103c:829e | Intel      | 200 Series PCH CSME HECI #1  | 1     | mei_me     | 0028753E4D |
| 8086:a2ba | 17aa:310b | Intel      | 200 Series PCH CSME HECI #1  | 1     | mei_me     | B6650A1B1C |
| 8086:a2ba | 17aa:310c | Intel      | 200 Series PCH CSME HECI #1  | 1     | mei_me     | 60877665B6 |
| 8086:a360 | 103c:8457 | Intel      | Cannon Lake PCH HECI Cont... | 1     | mei_me     | C15E7F2A47 |

### Dma controller (eisa dma) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22c0 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 19    | dw_dmac... | DCC1CCB590 |
| 8086:0f06 | 8086:0f06 | Intel      | Atom Processor Z36xxx/Z37... | 1     | dw_dmac... | A968EF1DD8 |
| 8086:2286 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 10C1838B9D |
| 8086:22c0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | dw_dmac... | 10C1838B9D |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0f18 | 8086:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 73    | mei_txe    | 0D4AC42F55 |
| 1022:15df | 1022:15df | AMD        | Family 17h (Models 10h-1f... | 36    | ccp        | 4BA408D68C |
| 8086:2298 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 34    | mei_txe    | 127B977658 |
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 28    | mei_txe    | FD46C16BB7 |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 15    |            | EDC6F2231B |
| 8086:0f18 | 17aa:368d | Intel      | Atom Processor Z36xxx/Z37... | 9     | mei_txe    | 4713CA77A1 |
| 1022:15df | 103c:872e | AMD        | Family 17h (Models 10h-1f... | 7     | ccp        | 137E91B812 |
| 8086:0f18 |           | Intel      | Atom Processor Z36xxx/Z37... | 6     | mei_txe    | 2882CF9963 |
| 1022:15df | 103c:8836 | AMD        | Family 17h (Models 10h-1f... | 4     | ccp        | DA34E7C710 |
| 8086:0f18 | 19da:b219 | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 34EFC38E50 |
| 8086:2298 | 17aa:30dd | Intel      | Atom/Celeron/Pentium Proc... | 4     | mei_txe    | 0513ACEC04 |
| 8086:2298 | 17aa:3637 | Intel      | Atom/Celeron/Pentium Proc... | 4     | mei_txe    | 9FC0FE4A5F |
| 8086:2298 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 4     | mei_txe    | 0D05B404DD |
| 8086:0f18 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 3     | mei_txe    | EED35A825A |
| 8086:2298 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 3     | mei_txe    | FDE91E565C |
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
| 11c1:5901 | 11c1:5900 | LSI        | FW643 [TrueFire] PCIe 139... | 64    | firewir... | 4D3FECA2AC |
| 104c:823f |           | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 47    | firewir... | 8E878489D3 |
| 11c1:5811 | 11c1:5811 | LSI        | FW322/323 [TrueFire] 1394... | 16    | firewir... | 68AD9FB8E9 |
| 11c1:5901 | c111:0159 | LSI        | FW643 [TrueFire] PCIe 139... | 3     | firewir... | 442224F9B2 |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1577 | 1022:1577 | AMD        | Family 15h (Models 60h-6f... | 15    |            | EDC6F2231B |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3ea5 | 8086:2074 | Intel      | CoffeeLake-U GT3e [Iris P... | 130   | i915       | 7EEEAAA250 |
| 8086:0f31 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 73    | i915       | 0D4AC42F55 |
| 8086:9bca | 8086:2081 | Intel      | Comet Lake UHD Graphics      | 41    | i915       | 37E756FA81 |
| 8086:22b1 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 34    | i915       | 127B977658 |
| 8086:5a85 | 8086:2067 | Intel      | HD Graphics 500              | 32    | i915       | B1C4AF0594 |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics 500              | 31    | i915       | D831E8693D |
| 1002:694c | 8086:2073 | AMD        | Polaris 22 XT [Radeon RX ... | 29    | amdgpu     | 507FBFC464 |
| 8086:9b41 | 8086:2081 | Intel      | CometLake-U GT2 [UHD Grap... | 29    | i915       | E4020A0558 |
| 8086:5916 | 8086:2068 | Intel      | HD Graphics 620              | 28    | i915       | 4A9E20C522 |
| 8086:591b | 8086:2073 | Intel      | HD Graphics 630              | 27    | i915       | AAEF52ACA2 |
| 8086:0166 | 106b:00ff | Intel      | 3rd Gen Core processor Gr... | 25    | i915       | B18B29EED7 |
| 8086:193b | 8086:2064 | Intel      | Iris Pro Graphics 580        | 25    | i915       | FA1CECCEE5 |
| 8086:5926 | 8086:2068 | Intel      | Iris Plus Graphics 640       | 25    | i915       | 82B124D8C4 |
| 1002:1636 | 1043:87e7 | AMD        | Renoir                       | 20    | amdgpu     | 4BA408D68C |
| 10de:0861 | 106b:00ae | Nvidia     | C79 [GeForce 9400]           | 19    | nouveau    | 8699437E9E |
| 8086:0126 | 106b:00e6 | Intel      | 2nd Generation Core Proce... | 19    | i915       | E3EA65A467 |
| 8086:0166 | 106b:0101 | Intel      | 3rd Gen Core processor Gr... | 19    | i915       | 4D3FECA2AC |
| 8086:0a2e | 106b:0141 | Intel      | Haswell-ULT Integrated Gr... | 19    | i915       | A790DE17AA |
| 8086:1616 | 8086:2057 | Intel      | HD Graphics 5500             | 18    | i915       | 1B9BEEAF2D |
| 8086:1626 | 8086:2057 | Intel      | HD Graphics 6000             | 17    | i915       | BAD1A02020 |
| 8086:3184 | 8086:2072 | Intel      | GeminiLake [UHD Graphics ... | 17    | i915       | C1F78B36E0 |
| 8086:3185 | 8086:2072 | Intel      | GeminiLake [UHD Graphics ... | 17    | i915       | C7B7542436 |
| 8086:5927 | 8086:2068 | Intel      | Iris Plus Graphics 650       | 17    | i915       | 14C78A00B9 |
| 8086:27a2 | 8086:7270 | Intel      | Mobile 945GM/GMS, 943/940... | 16    | i915       | 68AD9FB8E9 |
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 15    | i915       | FD46C16BB7 |
| 10de:08a4 | 106b:00c0 | Nvidia     | MCP89 [GeForce 320M]         | 14    | nouveau    | CFCED2BB90 |
| 1002:9806 | 103c:17e2 | AMD        | Wrestler [Radeon HD 6320]    | 13    | radeon     | E1E74F57A7 |
| 8086:0a26 | 106b:0141 | Intel      | Haswell-ULT Integrated Gr... | 13    | i915       | E4A3A40AB2 |
| 8086:22b1 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 13    | i915       | 10C1838B9D |
| 1002:6741 | 106b:00e8 | AMD        | Whistler [Radeon HD 6630M... | 12    | radeon     | 8E878489D3 |
| 8086:3e92 | 17aa:312d | Intel      | CometLake-S GT2 [UHD Grap... | 11    | i915       | ACBB96BA48 |
| 8086:5917 | 8086:2070 | Intel      | UHD Graphics 620             | 10    | i915       | CBF00091FA |
| 1002:15dd | 17aa:3130 | AMD        | Raven Ridge [Radeon Vega ... | 9     | amdgpu     | 5981A4A25B |
| 8086:0126 | 106b:00f0 | Intel      | 2nd Generation Core Proce... | 9     |            | 8E878489D3 |
| 8086:0f31 | 17aa:368d | Intel      | Atom Processor Z36xxx/Z37... | 9     | i915       | 4713CA77A1 |
| 8086:3185 | 1043:875e | Intel      | GeminiLake [UHD Graphics ... | 9     | i915       | 9D5F2807CE |
| 1106:7122 | 1106:7122 | VIA Tec... | VX900 Graphics [Chrome9 HD]  | 8     |            | 15268C0CCC |
| 8086:162b | 8086:2057 | Intel      | Iris Graphics 6100           | 8     | i915       | FA8B6B861D |
| 8086:1926 | 8086:2063 | Intel      | Iris Graphics 540            | 8     | i915       | 394340CB1A |
| 8086:9a49 | 8086:3004 | Intel      | TigerLake-LP GT2 [Iris Xe... | 8     | i915       | 0279A35638 |
| 1002:1636 | 103c:872e | AMD        | Renoir                       | 7     | amdgpu     | 137E91B812 |
| 8086:0f31 | 1027:2014 | Intel      | Atom Processor Z36xxx/Z37... | 7     | i915       | AD5481A5BC |
| 8086:1916 | 8086:2063 | Intel      | Skylake GT2 [HD Graphics ... | 7     | i915       | 38571FCFB9 |
| 8086:3e9b | 106b:0207 | Intel      | CoffeeLake-H GT2 [UHD Gra... | 7     | i915       | D09823163E |
| 8086:5a84 | 8086:2212 | Intel      | Celeron N3350/Pentium N42... | 7     | i915       | EB4D3C15D8 |
| 8086:0f31 | 17aa:30b5 | Intel      | Atom Processor Z36xxx/Z37... | 6     | i915       | 538597F50A |
| 8086:3e92 | 17aa:3135 | Intel      | CometLake-S GT2 [UHD Grap... | 6     | i915       | B41631FF89 |
| 8086:5a85 | 19da:b325 | Intel      | HD Graphics 500              | 6     | i915       | 23BDDBF63A |
| 1002:15d8 | 17aa:3151 | AMD        | Picasso                      | 5     | amdgpu     | 76152DDCE8 |
| 1002:694e | 8086:2073 | AMD        | Polaris 22 XL [Radeon RX ... | 5     | amdgpu     | 7657E986DA |
| 1002:9874 | 103c:8158 | AMD        | Wani [Radeon R5/R6/R7 Gra... | 5     | amdgpu     | 95BC62EF3F |
| 8086:27a6 | 8086:7270 | Intel      | Mobile 945GM/GMS/GME, 943... | 5     |            | 68AD9FB8E9 |
| 8086:3e92 | 17aa:3136 | Intel      | CometLake-S GT2 [UHD Grap... | 5     | i915       | 2A2C128E48 |
| 8086:3e9b | 8086:2089 | Intel      | CoffeeLake-H GT2 [UHD Gra... | 5     | i915       | 2EB74A58D2 |
| 8086:3ea0 | 17aa:314d | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 5     | i915       | BD2F6222E5 |
| 8086:5917 | 8086:2015 | Intel      | UHD Graphics 620             | 5     | i915       | 1219FB4CEF |
| 1002:15d8 | 103c:8836 | AMD        | Picasso                      | 4     | amdgpu     | DA34E7C710 |
| 1002:98e4 | 103c:8267 | AMD        | Stoney [Radeon R2/R3/R4/R... | 4     | amdgpu     | EDC6F2231B |
| 1002:98e4 | 17aa:312f | AMD        | Stoney [Radeon R2/R3/R4/R... | 4     | amdgpu     | 5205C41BC5 |
| 10de:13b4 | 103c:82c0 | Nvidia     | GM107GLM [Quadro M620 Mob... | 4     | nvidia     | AC904E9BCB |
| 8086:0156 | 19da:b211 | Intel      | 3rd Gen Core processor Gr... | 4     | i915       | EFBBD0C3F8 |
| 8086:0412 | 19da:b220 | Intel      | Xeon E3-1200 v3/4th Gen C... | 4     | i915       | FCAA602427 |
| 8086:0f31 | 19da:b219 | Intel      | Atom Processor Z36xxx/Z37... | 4     | i915       | 34EFC38E50 |
| 8086:0f31 | 8086:2212 | Intel      | Atom Processor Z36xxx/Z37... | 4     | i915       | EED35A825A |
| 8086:1616 | 8086:2058 | Intel      | HD Graphics 5500             | 4     | i915       | 6E19619F29 |
| 8086:22b1 | 17aa:30dd | Intel      | Atom/Celeron/Pentium Proc... | 4     | i915       | 0513ACEC04 |
| 8086:22b1 | 17aa:3637 | Intel      | Atom/Celeron/Pentium Proc... | 4     | i915       | 9FC0FE4A5F |
| 8086:22b1 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 4     | i915       | 0D05B404DD |
| 8086:3185 | 1e50:8003 | Intel      | GeminiLake [UHD Graphics ... | 4     | i915       | 995CC09B8D |
| 8086:5916 | 8086:2070 | Intel      | HD Graphics 620              | 4     | i915       | A03DE89D54 |
| 8086:9b41 | 1043:87bd | Intel      | CometLake-U GT2 [UHD Grap... | 4     | i915       | 7A01C63401 |
| 1002:9802 | 19da:a191 | AMD        | Wrestler [Radeon HD 6310]    | 3     | radeon     | 121F403E29 |
| 1002:9832 | 1002:0123 | AMD        | Kabini [Radeon HD 8330]      | 3     | radeon     | 514267F2D8 |
| 10de:1050 | 19da:2180 | Nvidia     | GF119M [GeForce GT 520M]     | 3     | nouveau    | 49EF2577E1 |
| 10de:1c20 | 19da:2413 | Nvidia     | GP106M [GeForce GTX 1060 ... | 3     | nouveau    | 29DC0371D1 |
| 10de:1cb6 | 10de:1264 | Nvidia     | GP107GL [Quadro P620]        | 3     | nouveau    | B16B2D9BD5 |
| 1a03:2000 | 15d9:0898 | ASPEED ... | ASPEED Graphics Family       | 3     | ast        | 8D4CBF243D |
| 8086:1616 | 1e50:8002 | Intel      | HD Graphics 5500             | 3     | i915       | 03E4B0BB3C |
| 8086:22b1 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 3     | i915       | FDE91E565C |
| 8086:22b1 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 3     | i915       | 7F47BED9CF |
| 8086:3185 |           | Intel      | GeminiLake [UHD Graphics ... | 3     | i915       | 94025849E2 |
| 8086:5a85 | 8086:2112 | Intel      | HD Graphics 500              | 3     | i915       | 1F796A44E6 |
| 8086:9b41 | 1e50:800b | Intel      | CometLake-U GT2 [UHD Grap... | 3     | i915       | 1155D58828 |
| 8086:a001 | 8086:544b | Intel      | Atom Processor D4xx/D5xx/... | 3     | i915       | 9DC27FC5BE |
| 1002:6987 | 8086:2079 | AMD        | Lexa [Radeon 540X/550X/63... | 2     | amdgpu     | 45B14891D4 |
| 1002:699f | 8086:2075 | AMD        | Lexa PRO [Radeon 540/540X... | 2     | amdgpu     | D9AC661777 |
| 1002:9806 | 19da:a233 | AMD        | Wrestler [Radeon HD 6320]    | 2     | radeon     | 87C89614B1 |
| 1002:9808 | 19da:a261 | AMD        | Wrestler [Radeon HD 7340]    | 2     | radeon     | 8C3CA64606 |
| 10de:1ba1 | 19da:1413 | Nvidia     | GP104M [GeForce GTX 1070 ... | 2     | nvidia     | CC099348C2 |
| 10de:1cbb | 103c:8458 | Nvidia     | GP107GLM [Quadro P1000 Mo... | 2     | nvidia     | 87E6E38B4A |
| 10de:1f15 | 8086:2090 | Nvidia     | TU106M [GeForce RTX 2060 ... | 2     | nvidia     | 7F8E6D2DA9 |
| 1a03:2000 | 15d9:0813 | ASPEED ... | ASPEED Graphics Family       | 2     | ast        | C1D37659C1 |
| 8086:0116 | 106b:00e7 | Intel      | 2nd Generation Core Proce... | 2     | i915       | 225237EC0F |
| 8086:0166 | 19da:2111 | Intel      | 3rd Gen Core processor Gr... | 2     | i915       | 4A3ACD7700 |
| 8086:0166 | 8086:2211 | Intel      | 3rd Gen Core processor Gr... | 2     | i915       | 04D1FD85D9 |
| 8086:0412 | 103c:2145 | Intel      | Xeon E3-1200 v3/4th Gen C... | 2     | i915       | 9C26D1B3DD |
| 8086:1616 | 1e51:8002 | Intel      | HD Graphics 5500             | 2     | i915       | 0A76AC3FB8 |
| 8086:162b | 1e50:8002 | Intel      | Iris Graphics 6100           | 2     | i915       | 7840462C30 |
| 8086:1912 | 103c:829a | Intel      | HD Graphics 530              | 2     | i915       | 1F3D092233 |
| 8086:1912 | 8086:0000 | Intel      | HD Graphics 530              | 2     | i915       | D8B8CA1E48 |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1631 | 1022:1631 | AMD        | Renoir/Cezanne IOMMU         | 29    |            | 4BA408D68C |
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 20    |            | 5981A4A25B |
| 8086:1f16 | 8086:0000 | Intel      | Atom processor C2000 RCEC    | 2     |            | C1D37659C1 |
| 1022:15d1 | 103c:8523 | AMD        | Raven/Raven2 IOMMU           | 1     |            | BAB721D52E |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816c | 1043:85b5 | Realtek... | RTL8111xP IPMI interface     | 16    |            | 9B5B350293 |
| 10ec:816c | 17aa:3151 | Realtek... | RTL8111xP IPMI interface     | 5     |            | 76152DDCE8 |
| 10ec:816c | 103c:8523 | Realtek... | RTL8111xP IPMI interface     | 1     |            | BAB721D52E |
| 10ec:816c | 17aa:30fd | Realtek... | RTL8111xP IPMI interface     | 1     |            | 5F6F9A1C6C |
| 10ec:816c | 17aa:3181 | Realtek... | RTL8111xP IPMI interface     | 1     |            | A203CD8C57 |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816c | 17aa:3130 | Realtek... | RTL8111xP IPMI interface     | 9     |            | 5981A4A25B |
| 10ec:816c | 10ec:8168 | Realtek... | RTL8111xP IPMI interface     | 7     | ipmi_si    | DFCA28CC5F |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9def | 8086:2074 | Intel      | Cannon Point-LP Shared SRAM  | 130   |            | 7EEEAAA250 |
| 8086:02ef | 8086:2081 | Intel      | Comet Lake PCH-LP Shared ... | 70    |            | 37E756FA81 |
| 8086:9d21 | 8086:2068 | Intel      | Sunrise Point-LP PMC         | 70    |            | 82B124D8C4 |
| 8086:a121 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 35    |            | 507FBFC464 |
| 8086:a121 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 25    |            | FA1CECCEE5 |
| 10de:0a88 |           | Nvidia     | MCP79 Memory Controller      | 19    |            | 8699437E9E |
| 10de:0a89 |           | Nvidia     | MCP79 Memory Controller      | 19    |            | 8699437E9E |
| 10de:0a98 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 19    |            | 8699437E9E |
| 10de:0aa4 |           | Nvidia     | MCP79 Memory Controller      | 19    |            | 8699437E9E |
| 8086:9d21 | 8086:2063 | Intel      | Sunrise Point-LP PMC         | 15    |            | 38571FCFB9 |
| 10de:0d68 |           | Nvidia     | MCP89 Memory Controller      | 14    |            | CFCED2BB90 |
| 10de:0d69 |           | Nvidia     | MCP89 Memory Controller      | 14    |            | CFCED2BB90 |
| 10de:0d6d |           | Nvidia     | MCP89 Memory Controller      | 14    |            | CFCED2BB90 |
| 10de:0d6e |           | Nvidia     | MCP89 Memory Controller      | 14    |            | CFCED2BB90 |
| 10de:0d6f |           | Nvidia     | MCP89 Memory Controller      | 14    |            | CFCED2BB90 |
| 10de:0d70 |           | Nvidia     | MCP89 Memory Controller      | 14    |            | CFCED2BB90 |
| 10de:0d71 |           | Nvidia     | MCP89 Memory Controller      | 14    |            | CFCED2BB90 |
| 10de:0d72 |           | Nvidia     | MCP89 Memory Controller      | 14    |            | CFCED2BB90 |
| 10de:0d75 |           | Nvidia     | MCP89 Memory Controller      | 14    |            | CFCED2BB90 |
| 10de:0d7b |           | Nvidia     | MCP89 Memory Controller      | 14    |            | CFCED2BB90 |
| 8086:9d21 | 8086:2070 | Intel      | Sunrise Point-LP PMC         | 14    |            | CBF00091FA |
| 8086:a0ef |           | Intel      | Tiger Lake-LP Shared SRAM    | 13    |            | 7F8E6D2DA9 |
| 8086:a36f | 17aa:312d | Intel      | Cannon Lake PCH Shared SRAM  | 13    |            | ACBB96BA48 |
| 8086:a36f | 8086:7270 | Intel      | Cannon Lake PCH Shared SRAM  | 9     |            | 2AE39C4439 |
| 8086:a36f | 17aa:3135 | Intel      | Cannon Lake PCH Shared SRAM  | 8     |            | C43EF85B97 |
| 8086:9d21 | 8086:7270 | Intel      | Sunrise Point-LP PMC         | 7     |            | 1219FB4CEF |
| 8086:a36f |           | Intel      | Cannon Lake PCH Shared SRAM  | 7     |            | D09823163E |
| 8086:9def | 17aa:314d | Intel      | Cannon Point-LP Shared SRAM  | 6     |            | BD2F6222E5 |
| 8086:a121 | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 6     |            | CC099348C2 |
| 8086:a36f | 17aa:3136 | Intel      | Cannon Lake PCH Shared SRAM  | 6     |            | 2A2C128E48 |
| 8086:a2a1 | 103c:829a | Intel      | 200 Series/Z370 Chipset F... | 5     |            | 1F3D092233 |
| 8086:02ef | 1043:87bd | Intel      | Comet Lake PCH-LP Shared ... | 4     |            | 7A01C63401 |
| 8086:9def | 8086:7270 | Intel      | Cannon Point-LP Shared SRAM  | 4     |            | D9AC661777 |
| 8086:a121 | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 4     |            | AC904E9BCB |
| 8086:a2a1 | 103c:82a5 | Intel      | 200 Series/Z370 Chipset F... | 4     |            | 08B98B6A88 |
| 8086:02ef | 8086:7270 | Intel      | Comet Lake PCH-LP Shared ... | 3     |            | 1155D58828 |
| 8086:a121 | 15d9:0898 | Intel      | 100 Series/C230 Series Ch... | 3     |            | 8D4CBF243D |
| 8086:a121 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 3     |            | CA900F89D0 |
| 8086:06ef | 103c:8710 | Intel      | Comet Lake PCH Shared SRAM   | 2     |            | B2A212246B |
| 8086:06ef | 8086:7270 | Intel      | Comet Lake PCH Shared SRAM   | 2     |            | 57676DE735 |
| 8086:9d21 | 103c:84f5 | Intel      | Sunrise Point-LP PMC         | 2     |            | C7B3D1917B |
| 8086:9d21 | 1043:8694 | Intel      | Sunrise Point-LP PMC         | 2     |            | 847A813A2C |
| 8086:9def | 1043:8790 | Intel      | Cannon Point-LP Shared SRAM  | 2     |            | 45389EF622 |
| 8086:9def | 17aa:314c | Intel      | Cannon Point-LP Shared SRAM  | 2     |            | 0F66B49A44 |
| 8086:a121 | 1019:9bc6 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 7101BAED7A |
| 8086:a2a1 | 103c:829e | Intel      | 200 Series/Z370 Chipset F... | 2     |            | 0028753E4D |
| 8086:a2a1 | 17aa:3111 | Intel      | 200 Series/Z370 Chipset F... | 2     |            | A89ECD0B5F |
| 8086:a36f | 103c:8458 | Intel      | Cannon Lake PCH Shared SRAM  | 2     |            | 87E6E38B4A |
| 8086:06ef | 103c:871a | Intel      | Comet Lake PCH Shared SRAM   | 1     |            | F74885CE0C |
| 8086:06ef | 103c:8755 | Intel      | Comet Lake PCH Shared SRAM   | 1     |            | 334ABF8C53 |
| 8086:06ef | 17aa:316e | Intel      | Comet Lake PCH Shared SRAM   | 1     |            | 7146ACBC96 |
| 8086:06ef | 17aa:3172 | Intel      | Comet Lake PCH Shared SRAM   | 1     |            | 3E09AE8DEE |
| 8086:06ef | 17aa:3307 | Intel      | Comet Lake PCH Shared SRAM   | 1     |            | D99E47E84D |
| 8086:4def | 1043:8813 | Intel      | Jasper Lake Shared SRAM C... | 1     |            | 4EBA944D40 |
| 8086:9def | 17aa:3144 | Intel      | Cannon Point-LP Shared SRAM  | 1     |            | 8D0F1F5E39 |
| 8086:a0ef | 8086:2091 | Intel      | Tiger Lake-LP Shared SRAM    | 1     |            | BD9CFC6A29 |
| 8086:a0ef | 8086:3013 | Intel      | Tiger Lake-LP Shared SRAM    | 1     |            | 66A02F462F |
| 8086:a2a1 | 17aa:310b | Intel      | 200 Series/Z370 Chipset F... | 1     |            | B6650A1B1C |
| 8086:a2a1 | 17aa:310c | Intel      | 200 Series/Z370 Chipset F... | 1     |            | 60877665B6 |
| 8086:a36f | 103c:8457 | Intel      | Cannon Lake PCH Shared SRAM  | 1     |            | C15E7F2A47 |

### Multimedia (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0f38 |           | Intel      | Atom Processor Z36xxx/Z37... | 1     |            | C4198C729C |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15e2 | 1022:15e2 | AMD        | Raven/Raven2/FireFlight/R... | 37    | snd_pci... | 4BA408D68C |
| 8086:5a88 |           | Intel      | Celeron N3350/Pentium N42... | 10    |            | D831E8693D |
| 8086:0f38 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 5     | intel_a... | 87E6D2F056 |
| 8086:22b8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 2     | intel_a... | 10C1838B9D |
| 1022:15e2 | 103c:8523 | AMD        | Raven/Raven2/FireFlight/R... | 1     | snd_pci... | BAB721D52E |
| 109e:0878 |           | Brooktree  | Bt878 Audio Capture          | 1     |            | 10DB69DD6C |
| 8086:0f38 | 1027:2014 | Intel      | Atom Processor Z36xxx/Z37... | 1     | intel_a... | 029DA6FFCC |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:15be | 8086:2074 | Intel      | Ethernet Connection (6) I... | 129   | e1000e     | 7EEEAAA250 |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 128   | r8169      | 1155D58828 |
| 14e4:1686 | 14e4:1686 | Broadcom   | NetXtreme BCM57766 Gigabi... | 76    | tg3        | A790DE17AA |
| 8086:0d4f | 8086:2081 | Intel      | Ethernet Connection (10) ... | 70    | e1000e     | 37E756FA81 |
| 8086:15d8 | 8086:2068 | Intel      | Ethernet Connection (4) I... | 69    | e1000e     | 82B124D8C4 |
| 14e4:16b4 | 14e4:16b4 | Broadcom   | NetXtreme BCM57765 Gigabi... | 47    | tg3        | 8E878489D3 |
| 10ec:8168 | 19da:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 43    | r8169      | 514267F2D8 |
| 8086:15a3 | 8086:2057 | Intel      | Ethernet Connection (3) I... | 43    | e1000e     | 1B9BEEAF2D |
| 8086:15b7 | 8086:0000 | Intel      | Ethernet Connection (2) I... | 35    | e1000e     | 507FBFC464 |
| 10ec:8168 | 8086:2072 | Realtek... | RTL8111/8168/8411 PCI Exp... | 34    | r8169      | C1F78B36E0 |
| 10ec:8168 | 8086:2060 | Realtek... | RTL8111/8168/8411 PCI Exp... | 31    | r8169      | 127B977658 |
| 10ec:8168 | 8086:2067 | Realtek... | RTL8111/8168/8411 PCI Exp... | 31    | r8169      | B1C4AF0594 |
| 8086:15b7 | 8086:2064 | Intel      | Ethernet Connection (2) I... | 25    | e1000e     | FA1CECCEE5 |
| 10de:0ab0 | 10de:cb79 | Nvidia     | MCP79 Ethernet               | 19    | forcedeth  | 8699437E9E |
| 10ec:8168 | 1043:85b5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 16    | r8169      | 9B5B350293 |
| 11ab:4362 | 11ab:5321 | Marvell... | 88E8053 PCI-E Gigabit Eth... | 16    | sky2       | 68AD9FB8E9 |
| 8086:1570 | 8086:2063 | Intel      | Ethernet Connection I219-V   | 15    | e1000e     | 38571FCFB9 |
| 8086:156f | 8086:2070 | Intel      | Ethernet Connection I219-LM  | 14    | e1000e     | CBF00091FA |
| 14e4:16b1 | 103c:17e2 | Broadcom   | NetLink BCM57781 Gigabit ... | 13    | tg3        | E1E74F57A7 |
| 8086:15bc | 17aa:312d | Intel      | Ethernet Connection (7) I... | 13    | e1000e     | ACBB96BA48 |
| 10ec:8168 | 1043:8677 | Realtek... | RTL8111/8168/8411 PCI Exp... | 12    | r8169      | 9D5F2807CE |
| 10ec:8168 | 17aa:3130 | Realtek... | RTL8111/8168/8411 PCI Exp... | 9     | r8169      | 5981A4A25B |
| 14e4:1692 | 14e4:9692 | Broadcom   | NetLink BCM57780 Gigabit ... | 8     | tg3        | 15268C0CCC |
| 8086:15bb | 17aa:3135 | Intel      | Ethernet Connection (7) I... | 8     | e1000e     | C43EF85B97 |
| 8086:15f3 | 8086:3004 | Intel      | Ethernet Controller I225-V   | 8     | igc        | 0279A35638 |
| 10ec:8136 | 17aa:368d | Realtek... | RTL810xE PCI Express Fast... | 7     | r8169      | 462B8C10A5 |
| 10ec:8168 | 103c:872e | Realtek... | RTL8111/8168/8411 PCI Exp... | 7     | r8169      | 137E91B812 |
| 14e4:1686 | 106b:0099 | Broadcom   | NetXtreme BCM57766 Gigabi... | 7     | tg3        | D09823163E |
| 8086:15bb | 8086:0000 | Intel      | Ethernet Connection (7) I... | 7     | e1000e     | 2AE39C4439 |
| 10ec:8168 | 17aa:30b5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 6     | r8169      | 538597F50A |
| 8086:15bb | 17aa:3136 | Intel      | Ethernet Connection (7) I... | 6     | e1000e     | 2A2C128E48 |
| 10ec:8168 | 103c:8158 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8169      | 95BC62EF3F |
| 10ec:8168 | 17aa:3151 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8169      | 76152DDCE8 |
| 10ec:8168 | 1b50:4606 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | r8169      | 2882CF9963 |
| 8086:15e3 | 103c:829a | Intel      | Ethernet Connection (5) I... | 5     | e1000e     | 1F3D092233 |
| 10ec:8168 | 103c:8267 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | EDC6F2231B |
| 10ec:8168 | 103c:82a5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 08B98B6A88 |
| 10ec:8168 | 103c:8836 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8168      | DA34E7C710 |
| 10ec:8168 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 04D1FD85D9 |
| 10ec:8168 | 17aa:30dd | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 0513ACEC04 |
| 10ec:8168 | 17aa:312f | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 5205C41BC5 |
| 10ec:8168 | 17aa:314d | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 032DB5DB0F |
| 10ec:8168 | 17aa:3637 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | r8169      | 9FC0FE4A5F |
| 8086:0d4f | 1043:8672 | Intel      | Ethernet Connection (10) ... | 4     | e1000e     | 7A01C63401 |
| 8086:15b7 | 103c:82c0 | Intel      | Ethernet Connection (2) I... | 4     | e1000e     | AC904E9BCB |
| 8086:15be | 8086:0000 | Intel      | Ethernet Connection (6) I... | 4     | e1000e     | D9AC661777 |
| 10ec:8136 | 8086:d626 | Realtek... | RTL810xE PCI Express Fast... | 3     | r8169      | 9DC27FC5BE |
| 10ec:8168 | 1462:b120 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | r8169      | FDE91E565C |
| 14e4:16b0 | 106b:00f1 | Broadcom   | NetXtreme BCM57761 Gigabi... | 3     | tg3        | 442224F9B2 |
| 10ec:3000 | 09a3:1028 | Realtek... | Killer E3000 2.5GbE Contr... | 2     | r8169      | 57676DE735 |
| 10ec:3000 | 1a56:3000 | Realtek... | Killer E3000 2.5GbE Contr... | 2     | r8169      | CF60BF6309 |
| 10ec:8168 | 1028:080c | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | E46F325CBA |
| 10ec:8168 | 103c:84f5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | C7B3D1917B |
| 10ec:8168 | 17aa:368d | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 4713CA77A1 |
| 168c:abcd |           | Qualcom... | Osprey Emulation Wireless... | 2     |            | 207FE36973 |
| 8086:0d4c | 103c:870f | Intel      | Ethernet Connection (11) ... | 2     | e1000e     | B2A212246B |
| 8086:153a | 103c:2145 | Intel      | Ethernet Connection I217-LM  | 2     | e1000e     | 9C26D1B3DD |
| 8086:15a2 | 8086:2058 | Intel      | Ethernet Connection (3) I... | 2     | e1000e     | AF5060B68B |
| 8086:15a3 | 8086:2058 | Intel      | Ethernet Connection (3) I... | 2     | e1000e     | 6E19619F29 |
| 8086:15b8 | 17aa:3111 | Intel      | Ethernet Connection (2) I... | 2     | e1000e     | A89ECD0B5F |
| 8086:15bb | 103c:8458 | Intel      | Ethernet Connection (7) I... | 2     | e1000e     | 87E6E38B4A |
| 8086:15bc | 1043:8672 | Intel      | Ethernet Connection (7) I... | 2     | e1000e     | 45389EF622 |
| 8086:15bd | 17aa:314c | Intel      | Ethernet Connection (6) I... | 2     | e1000e     | 0F66B49A44 |
| 8086:15be | 17aa:314d | Intel      | Ethernet Connection (6) I... | 2     | e1000e     | BD2F6222E5 |
| 8086:15e3 | 103c:829e | Intel      | Ethernet Connection (5) I... | 2     | e1000e     | 0028753E4D |
| 8086:15f2 | 8086:2090 | Intel      | Ethernet Controller I225-LM  | 2     | igc        | 7F8E6D2DA9 |
| 8086:15f2 | 8086:3002 | Intel      | Ethernet Controller I225-LM  | 2     | igc        | 3738610B69 |
| 8086:1f41 | 15d9:1f41 | Intel      | Ethernet Connection I354     | 2     | igb        | C1D37659C1 |
| 10ec:8136 | 1028:07b9 | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | F444E9914B |
| 10ec:8136 | 10ec:0123 | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | A90B05A0FB |
| 10ec:8136 | 10ec:8168 | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | EED35A825A |
| 10ec:8136 | 17aa:3688 | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | A88328FDB9 |
| 10ec:8168 | 1028:07c1 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 9F4F497293 |
| 10ec:8168 | 103c:8523 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | BAB721D52E |
| 10ec:8168 | 103c:872c | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 0E48C94F83 |
| 10ec:8168 | 1458:e000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | E6FEB379A4 |
| 10ec:8168 | 17aa:30fd | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 5F6F9A1C6C |
| 10ec:8168 | 17aa:3144 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 8D0F1F5E39 |
| 10ec:8168 | 17aa:3181 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | A203CD8C57 |
| 10ec:8168 | 19da:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 90F8E7B807 |
| 10ec:8168 | 1b0a:015b | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 7E54F1E784 |
| 10ec:8168 | 1c6c:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | A27BE7CA62 |
| 10ec:8168 | 1d05:100f | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169, ... | 9569E1B79C |
| 14e4:1682 | 14e4:1682 | Broadcom   | NetXtreme BCM57762 Gigabi... | 1     | tg3        | B71EA2BEC1 |
| 14e4:1687 | 103c:815a | Broadcom   | NetXtreme BCM5762 Gigabit... | 1     | tg3        | 7D65A83025 |
| 1d6a:80b1 | 16b8:72e5 | Aquantia   | Ethernet controller          | 1     | atlantic   | D148D77A8C |
| 1d6a:87b1 | 1c7a:de2b | Aquantia   | AQC107 NBase-T/IEEE 802.3... | 1     | atlantic   | CFAD8B93A9 |
| 8086:0d4c | 103c:871a | Intel      | Ethernet Connection (11) ... | 1     | e1000e     | F74885CE0C |
| 8086:0d4c | 103c:8755 | Intel      | Ethernet Connection (11) ... | 1     |            | 334ABF8C53 |
| 8086:0d4c | 17aa:3172 | Intel      | Ethernet Connection (11) ... | 1     | e1000e     | 3E09AE8DEE |
| 8086:0d4d | 17aa:316e | Intel      | Ethernet Connection (11) ... | 1     | e1000e     | 7146ACBC96 |
| 8086:0d4d | 17aa:3307 | Intel      | Ethernet Connection (11) ... | 1     | e1000e     | D99E47E84D |
| 8086:1039 | 8086:3013 | Intel      | 82801DB PRO/100 VE (LOM) ... | 1     | e100       | 4A3E3CD4EE |
| 8086:155a | 8086:0000 | Intel      | Ethernet Connection I218-LM  | 1     | e1000e     | FF3CE414E4 |
| 8086:156f | 8086:0000 | Intel      | Ethernet Connection I219-LM  | 1     | e1000e     | EFB03DB319 |
| 8086:15b7 | 1019:9bc6 | Intel      | Ethernet Connection (2) I... | 1     | e1000e     | 7101BAED7A |
| 8086:15b7 | 17aa:310b | Intel      | Ethernet Connection (2) I... | 1     | e1000e     | B6650A1B1C |
| 8086:15b7 | 17aa:310c | Intel      | Ethernet Connection (2) I... | 1     | e1000e     | 60877665B6 |
| 8086:15bb | 103c:8457 | Intel      | Ethernet Connection (7) I... | 1     | e1000e     | C15E7F2A47 |
| 8086:15f2 | 8086:3003 | Intel      | Ethernet Controller I225-LM  | 1     | igc        | ABC31CEA35 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9df0 | 8086:0034 | Intel      | Cannon Point-LP CNVi [Wir... | 137   | iwlwifi    | 7EEEAAA250 |
| 8086:02f0 | 8086:0074 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 75    | iwlwifi    | 37E756FA81 |
| 8086:24fd | 8086:9010 | Intel      | Wireless 8265 / 8275         | 67    | iwlwifi    | 82B124D8C4 |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 60    | iwlwifi    | 127B977658 |
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 43    | iwlwifi    | EDC6F2231B |
| 8086:095a | 8086:9010 | Intel      | Wireless 7265                | 42    | iwlwifi    | 1B9BEEAF2D |
| 8086:24f3 | 8086:9010 | Intel      | Wireless 8260                | 36    | iwlwifi    | FA1CECCEE5 |
| 8086:31dc | 8086:02a4 | Intel      | Gemini Lake PCH CNVi WiFi    | 36    | iwlwifi    | C1F78B36E0 |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 35    | iwlwifi    | B1C4AF0594 |
| 14e4:4331 | 14e4:4331 | Broadcom   | BCM4331 802.11a/b/g/n        | 32    | wl         | 7904F815ED |
| 14e4:43a0 | 106b:013b | Broadco... | BCM4360 802.11ac Wireless... | 32    | wl         | A790DE17AA |
| 14e4:4331 | 106b:00e4 | Broadco... | BCM4331 802.11a/b/g/n        | 30    | wl         | 8E878489D3 |
| 14e4:4331 | 106b:010e | Broadcom   | BCM4331 802.11a/b/g/n        | 30    | wl         | AD4E633055 |
| 8086:2723 | 8086:0084 | Intel      | Wi-Fi 6 AX200                | 24    | iwlwifi    | 9B5B350293 |
| 8086:3165 | 8086:8010 | Intel      | Wireless 3165                | 23    | iwlwifi    | 0A76AC3FB8 |
| 8086:08b3 | 8086:0070 | Intel      | Wireless 3160                | 20    | iwlwifi    | 514267F2D8 |
| 14e4:4328 | 106b:0090 | Broadco... | BCM4321 802.11a/b/g/n        | 19    | ssb        | 8699437E9E |
| 168c:001c | 106b:0086 | Qualcom... | AR242x / AR542x Wireless ... | 16    | ath5k      | 68AD9FB8E9 |
| 14e4:4353 | 106b:0093 | Broadcom   | BCM43224 802.11a/b/g/n       | 14    | wl         | CFCED2BB90 |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 14    | iwlwifi    | 17B2D3483A |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 12    | iwlwifi    | 8D0F1F5E39 |
| 8086:31dc | 8086:0264 | Intel      | Gemini Lake PCH CNVi WiFi    | 11    | iwlwifi    | 2048DCBA92 |
| 8086:a0f0 | 8086:0074 | Intel      | Wi-Fi 6 AX201                | 11    | iwlwifi    | 7F8E6D2DA9 |
| 10ec:b723 | 10ec:b723 | Realtek... | RTL8723BE PCIe Wireless N... | 8     | rtl8723be  | A0C8ECBA6B |
| 8086:08b3 | 8086:8070 | Intel      | Wireless 3160                | 8     | iwlwifi    | 493278D567 |
| 14e4:4464 | 106b:07bf | Broadcom   | BCM4364 802.11ac Wireless... | 7     | brcmfmac   | D09823163E |
| 8086:2526 | 8086:0014 | Intel      | Wireless-AC 9260             | 7     | iwlwifi    | A203CD8C57 |
| 8086:3165 | 8086:8110 | Intel      | Wireless 3165                | 7     | iwlwifi    | 401691DB3B |
| 8086:a370 | 8086:0030 | Intel      | Cannon Lake PCH CNVi WiFi    | 6     | iwlwifi    | B41631FF89 |
| 8086:24f3 | 8086:10b0 | Intel      | Wireless 8260                | 5     | iwlwifi    | CE81650620 |
| 10ec:b723 | 17aa:b728 | Realtek... | RTL8723BE PCIe Wireless N... | 4     | rtl8723be  | 538597F50A |
| 14e4:4353 | 14e4:04d8 | Broadco... | BCM43224 802.11a/b/g/n       | 4     | wl         | AF1F6C2CD7 |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 4     | iwlwifi    | 0028753E4D |
| 8086:2723 | 1a56:1654 | Intel      | Wi-Fi 6 AX200                | 4     | iwlwifi    | 57676DE735 |
| 8086:2723 | 8086:008c | Intel      | Wi-Fi 6 AX200                | 4     | iwlwifi    | D553BC172B |
| 10ec:c821 | 17aa:c024 | Realtek... | RTL8821CE 802.11ac PCIe W... | 3     | 8821ce     | FFDC0DC1D7 |
| 168c:002b | 1a3b:2c37 | Qualcom... | AR9285 Wireless Network A... | 3     | ath9k      | 87C89614B1 |
| 1814:3290 | 1a3b:2b87 | Ralink     | RT3290 Wireless 802.11n 1... | 3     | rt2800pci  | 121F403E29 |
| 8086:0892 | 8086:0062 | Intel      | Centrino Wireless-N 135      | 3     | iwlwifi    | 4D23C29B62 |
| 8086:0896 | 8086:5005 | Intel      | Centrino Wireless-N 130      | 3     | iwlwifi    | 0909932423 |
| 8086:31dc | 8086:0034 | Intel      | Gemini Lake PCH CNVi WiFi    | 3     | iwlwifi    | 9D5F2807CE |
| 8086:a370 | 8086:0034 | Intel      | Cannon Lake PCH CNVi WiFi    | 3     | iwlwifi    | C15E7F2A47 |
| 10ec:8179 | 1a3b:1d38 | Realtek... | RTL8188EE Wireless Networ... | 2     | rtl8188ee  | D999C674F1 |
| 10ec:b822 | 17aa:b023 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 2     | r8822be    | 9B61C385FD |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 2     |            | 137E91B812 |
| 10ec:c822 | 17aa:c123 | Realtek... | RTL8822CE 802.11ac PCIe W... | 2     | rtw_8822ce | AFFF8115C5 |
| 14e4:4359 | 103c:8088 | Broadco... | BCM43228 802.11a/b/g/n       | 2     | wl         | 7D65A83025 |
| 14e4:4359 | 14e4:05e2 | Broadcom   | BCM43228 802.11a/b/g/n       | 2     | wl         | E96EEBB6D7 |
| 168c:0034 | 11ad:6611 | Qualcom... | AR9462 Wireless Network A... | 2     | ath9k      | EED35A825A |
| 8086:06f0 | 8086:0074 | Intel      | Comet Lake PCH CNVi WiFi     | 2     | iwlwifi    | D99E47E84D |
| 8086:08b1 | 8086:4060 | Intel      | Wireless 7260                | 2     | iwlwifi    | 1DBF853E7F |
| 8086:2723 | 8086:0088 | Intel      | Wi-Fi 6 AX200                | 2     | iwlwifi    | 2AE39C4439 |
| 8086:9df0 | 8086:0030 | Intel      | Cannon Point-LP CNVi [Wir... | 2     | iwlwifi    | 0F66B49A44 |
| 8086:a0f0 | 8086:0070 | Intel      | Wi-Fi 6 AX201                | 2     | iwlwifi    | ABC31CEA35 |
| 10ec:8171 | 10ec:8171 | Realtek... | RTL8191SEvA Wireless LAN ... | 1     | rtl8192se  | BE63E554C5 |
| 10ec:8176 | 1a3b:2057 | Realtek... | RTL8188CE 802.11b/g/n WiF... | 1     | rtl8192ce  | 04D1FD85D9 |
| 10ec:8178 | 10ec:8191 | Realtek... | RTL8192CE PCIe Wireless N... | 1     | rtl8192ce  | 9314D29F45 |
| 10ec:8179 | 10ec:0189 | Realtek... | RTL8188EE Wireless Networ... | 1     | rtl8188ee  | AD04BFF06F |
| 10ec:8179 | 10ec:8179 | Realtek... | RTL8188EE Wireless Networ... | 1     | rtl8188ee  | B31E28E55F |
| 10ec:8179 | 1a3b:219a | Realtek... | RTL8188EE Wireless Networ... | 1     | rtl8188ee  | F6DDC974E1 |
| 10ec:8723 | 10ec:0733 | Realtek... | RTL8723AE PCIe Wireless N... | 1     |            | 2F246CACD8 |
| 10ec:8723 | 1a3b:2114 | Realtek... | RTL8723AE PCIe Wireless N... | 1     | rtl8723ae  | E6FEB379A4 |
| 10ec:b723 | 103c:2231 | Realtek... | RTL8723BE PCIe Wireless N... | 1     | rtl8723be  | 268CC95CAD |
| 10ec:b723 | 1a3b:2159 | Realtek... | RTL8723BE PCIe Wireless N... | 1     | rtl8723be  | 2882CF9963 |
| 10ec:c821 | 10ec:c821 | Realtek... | RTL8821CE 802.11ac PCIe W... | 1     |            | F71EFE50CF |
| 10ec:c822 | 1a3b:4210 | Realtek... | RTL8822CE 802.11ac PCIe W... | 1     | rtwpci     | C87DFAAC1F |
| 14e4:4312 | 1028:0007 | Broadco... | BCM4311 802.11a/b/g          | 1     | wl         | 5DB1994CAD |
| 14e4:4357 | 14e4:04da | Broadco... | BCM43225 802.11b/g/n         | 1     | wl         | D8DB035524 |
| 14e4:4359 | 103c:182c | Broadcom   | BCM43228 802.11a/b/g/n       | 1     | bcma       | 7265640CDC |
| 14e4:4365 | 11ad:6655 | Broadcom   | BCM43142 802.11b/g/n         | 1     |            | 6C2688EBFC |
| 168c:0036 | 1028:020c | Qualcom... | QCA9565 / AR9565 Wireless... | 1     | ath9k      | 982F591B41 |
| 168c:0036 | 11ad:0642 | Qualcom... | QCA9565 / AR9565 Wireless... | 1     | ath9k      | A27BE7CA62 |
| 168c:003e | 17aa:0827 | Qualcom... | QCA6174 802.11ac Wireless... | 1     | ath10k_pci | 5981A4A25B |
| 1814:0781 | 1a3b:1059 | Ralink     | RT2790 Wireless 802.11n 1... | 1     | rt2800pci  | 037A3E45C7 |
| 8086:06f0 | 8086:0070 | Intel      | Comet Lake PCH CNVi WiFi     | 1     | iwlwifi    | 3E09AE8DEE |
| 8086:06f0 | 8086:02a4 | Intel      | Comet Lake PCH CNVi WiFi     | 1     | iwlwifi    | 7146ACBC96 |
| 8086:0887 | 8086:4062 | Intel      | Centrino Wireless-N 2230     | 1     | iwlwifi    | 4A3ACD7700 |
| 8086:08b1 | 8086:4070 | Intel      | Wireless 7260                | 1     | iwlwifi    | FF3CE414E4 |
| 8086:08b1 | 8086:4462 | Intel      | Wireless 7260                | 1     | iwlwifi    | 6F729D176B |
| 8086:08b1 | 8086:c070 | Intel      | Wireless 7260                | 1     | iwlwifi    | AF5060B68B |
| 8086:08b2 | 8086:4262 | Intel      | Wireless 7260                | 1     | iwlwifi    | 4C0B50F040 |
| 8086:24f3 | 8086:0130 | Intel      | Wireless 8260                | 1     | iwlwifi    | EDB53070CD |
| 8086:24fd | 8086:0110 | Intel      | Wireless 8265 / 8275         | 1     | iwlwifi    | 4BA408D68C |
| 8086:2723 | 8086:0080 | Intel      | Wi-Fi 6 AX200                | 1     | iwlwifi    | D4583B58FE |
| 8086:2725 | 8086:0024 | Intel      | Wi-Fi 6 AX210/AX211/AX411... | 1     | iwlwifi    | 87E9A528F7 |
| 8086:422c | 8086:1301 | Intel      | Centrino Advanced-N 6200     | 1     | iwlwifi    | 494DE74E34 |
| 8086:4232 | 8086:1201 | Intel      | WiFi Link 5100               | 1     | iwlwifi    | 9BE096319C |
| 8086:4df0 | 8086:0034 | Intel      | Wi-Fi 6 AX201 160MHz         | 1     | iwlwifi    | 4EBA944D40 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:157b | 8086:0000 | Intel      | I210 Gigabit Network Conn... | 32    | igb        | 507FBFC464 |
| 8086:1533 | ffff:0000 | Intel      | I210 Gigabit Network Conn... | 18    | igb        | 2AE39C4439 |
| 8086:1539 | 8086:0000 | Intel      | I211 Gigabit Network Conn... | 18    | igb        | EB4D3C15D8 |
| 10ec:8125 | 1043:87d7 | Realtek... | RTL8125 2.5GbE Controller    | 5     | r8169      | 4BA408D68C |
| 8086:1521 | 15d9:0652 | Intel      | I350 Gigabit Network Conn... | 3     | igb        | 8D4CBF243D |
| 8086:1502 | 8086:0000 | Intel      | 82579LM Gigabit Network C... | 2     | e1000e     | 04D1FD85D9 |
| 8086:1539 | 8086:2080 | Intel      | I211 Gigabit Network Conn... | 2     | igb        | 745C35E31C |
| 8086:1093 | 8086:0001 | Intel      | PRO/100 VM Network Connec... | 1     | e100       | 10DB69DD6C |
| 8086:10fe | 17aa:3605 | Intel      | 82552 10/100 Network Conn... | 1     | e100       | F077B2F98E |
| 8086:1503 | 1734:11d9 | Intel      | 82579V Gigabit Network Co... | 1     | e1000e     | FC67594808 |
| 8086:1533 | 15bd:100a | Intel      | I210 Gigabit Network Conn... | 1     | igb        | 593A489E8D |
| 8086:1533 | 1ab6:0214 | Intel      | I210 Gigabit Network Conn... | 1     | igb        | E311FB0391 |
| 8086:1539 | 1297:4033 | Intel      | I211 Gigabit Network Conn... | 1     | igb        | B31E28E55F |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a126 |           | Intel      | 100 Series/C230 Series Ch... | 2     | intel_t... | CC099348C2 |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 106b:1801 | 106b:1801 | Apple      | T2 Bridge Controller         | 7     |            | D09823163E |
| 106b:1802 | 106b:1802 | Apple      | T2 Secure Enclave Processor  | 7     |            | D09823163E |
| 8086:a135 | 15d9:0898 | Intel      | 100 Series/C230 Series Ch... | 3     | intel_i... | 8D4CBF243D |
| 1022:15e6 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Non-S... | 2     | i2c_amd... | A203CD8C57 |

### Performance counters (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27a3 |           | Intel      | 945GM/GU Chipset Hardware... | 16    |            | 68AD9FB8E9 |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:16bc | 14e4:0000 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 123   | sdhci_pci  | A790DE17AA |
| 17a0:9755 | 8086:2081 | Genesys... | GL9755 SD Host Controller    | 68    | sdhci_pci  | 37E756FA81 |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 38    | sdhci_pci  | D831E8693D |
| 1217:8621 | 8086:2073 | O2 Micro   | SD/MMC Card Reader Contro... | 35    | sdhci_pci  | 507FBFC464 |
| 8086:31cc | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 34    | sdhci_pci  | C1F78B36E0 |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 30    | sdhci_pci  | D831E8693D |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 28    | sdhci_pci  | D831E8693D |
| 1217:8621 | 8086:2064 | O2 Micro   | SD/MMC Card Reader Contro... | 23    | sdhci_pci  | FA1CECCEE5 |
| 8086:2296 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 19    | sdhci_pci  | DCC1CCB590 |
| 8086:9d2d | 8086:2063 | Intel      | Sunrise Point-LP Secure D... | 14    | sdhci_pci  | 38571FCFB9 |
| 8086:5ad0 |           | Intel      | Celeron N3350/Pentium N42... | 9     | sdhci_pci  | 9AA58951EA |
| 8086:31d0 | 8086:7270 | Intel      | SD Host Controller           | 7     | sdhci_pci  | 94025849E2 |
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 6     | sdhci_pci  | 2048DCBA92 |
| 8086:5acc | 19da:b325 | Intel      | Celeron N3350/Pentium N42... | 6     | sdhci_pci  | 23BDDBF63A |
| 8086:0f16 | 8086:0f16 | Intel      | Atom Processor Z36xxx/Z37... | 4     | sdhci_pci  | ED960141AA |
| 8086:0f50 |           | Intel      | Atom Processor E3800 Seri... | 4     | sdhci_pci  | 34EFC38E50 |
| 8086:02c4 | 8086:7270 | Intel      | Comet Lake PCH-LP SCS1: eMMC | 3     | sdhci_pci  | 1155D58828 |
| 8086:0f16 | 19da:b219 | Intel      | Atom Processor Z36xxx/Z37... | 3     | sdhci_pci  | 34EFC38E50 |
| 8086:2294 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 3     | sdhci_pci  | FDE91E565C |
| 8086:2294 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 3     | sdhci_pci  | 0D05B404DD |
| 8086:2294 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 3     | sdhci_pci  | DCC1CCB590 |
| 8086:2294 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 3     | sdhci_pci  | 10C1838B9D |
| 8086:2296 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 3     | sdhci_pci  | 10C1838B9D |
| 8086:31cc | 8086:31cc | Intel      | Celeron/Pentium Silver Pr... | 3     | sdhci_pci  | C87DFAAC1F |
| 8086:5acc | 8086:5acc | Intel      | Celeron N3350/Pentium N42... | 3     | sdhci_pci  | 9AA58951EA |
| 1022:7806 | 19da:a261 | AMD        | FCH SD Flash Controller      | 2     | sdhci_pci  | 8C3CA64606 |
| 8086:31cc | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 2     | sdhci_pci  | E46F325CBA |
| 8086:5aca | 8086:5aca | Intel      | Celeron N3350/Pentium N42... | 2     | sdhci_pci  | 9AA58951EA |
| 8086:5acc | 8086:2080 | Intel      | Celeron N3350/Pentium N42... | 2     | sdhci_pci  | 745C35E31C |
| 8086:9d2b | 1043:8694 | Intel      | Skylake-U/Y SCC: eMMC        | 2     | sdhci_pci  | 847A813A2C |
| 8086:9dc4 | 8086:2075 | Intel      | 300 Series Chipset SD Hos... | 2     | sdhci_pci  | D9AC661777 |
| 8086:9df5 | 8086:2075 | Intel      | BayHubTech Integrated SD ... | 2     | sdhci_pci  | D9AC661777 |
| 1022:7806 | 19da:b218 | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | EB76FF1C3F |
| 1217:8520 | 1217:0002 | O2 Micro   | SD/MMC Card Reader Contro... | 1     |            | 493278D567 |
| 8086:0f15 | 19da:b219 | Intel      | Atom Processor Z36xxx/Z37... | 1     | sdhci_pci  | 4BC48CCC62 |
| 8086:2295 | 1028:07c1 | Intel      | Atom/Celeron/Pentium Proc... | 1     | sdhci_pci  | 9F4F497293 |
| 8086:4dc4 | 1043:8813 | Intel      | Jasper Lake SCS1: eMMC Co... | 1     | sdhci_pci  | 4EBA944D40 |
| 8086:5aca | 19da:b342 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 9A0C888104 |
| 8086:5acc | 19da:b342 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 9A0C888104 |
| 8086:5acc | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | EF4CBE2D05 |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9da4 | 8086:2074 | Intel      | Cannon Point-LP SPI Contr... | 130   |            | 7EEEAAA250 |
| 8086:02a4 | 8086:2081 | Intel      | Comet Lake SPI (flash) Co... | 70    | intel_s... | 37E756FA81 |
| 8086:02e8 | 8086:2081 | Intel      | Serial IO I2C Host Contro... | 70    | intel_l... | 37E756FA81 |
| 8086:02ea | 8086:2081 | Intel      | Comet Lake PCH-LP LPSS: I... | 70    | intel_l... | 37E756FA81 |
| 8086:5ac8 |           | Intel      | Celeron N3350/Pentium N42... | 25    | pwm_lps... | B1C4AF0594 |
| 8086:22c6 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 19    | i2c_des... | DCC1CCB590 |
| 8086:22c7 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 19    | i2c_des... | DCC1CCB590 |
| 8086:a324 | 17aa:312d | Intel      | Cannon Lake PCH SPI Contr... | 13    |            | ACBB96BA48 |
| 8086:5ac8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 10    | pwm_lpss   | EB4D3C15D8 |
| 8086:a0a4 | 8086:3004 | Intel      | Tiger Lake-LP SPI Controller | 8     | intel_spi  | 0279A35638 |
| 8086:a0e8 | 8086:3004 | Intel      | Tiger Lake-LP Serial IO I... | 8     | intel_l... | 0279A35638 |
| 8086:a324 | 17aa:3135 | Intel      | Cannon Lake PCH SPI Contr... | 8     |            | C43EF85B97 |
| 8086:a324 | 8086:7270 | Intel      | Cannon Lake PCH SPI Contr... | 7     | intel_s... | D09823163E |
| 8086:9da4 | 17aa:314d | Intel      | Cannon Point-LP SPI Contr... | 6     |            | BD2F6222E5 |
| 8086:a324 | 17aa:3136 | Intel      | Cannon Lake PCH SPI Contr... | 6     |            | 2A2C128E48 |
| 8086:a324 | 8086:2089 | Intel      | Cannon Lake PCH SPI Contr... | 5     |            | 2EB74A58D2 |
| 8086:a368 | 8086:2089 | Intel      | Cannon Lake PCH Serial IO... | 5     | intel_l... | 2EB74A58D2 |
| 8086:a369 | 8086:2089 | Intel      | Cannon Lake PCH Serial IO... | 5     | intel_l... | 2EB74A58D2 |
| 8086:02a4 | 1043:87bd | Intel      | Comet Lake SPI (flash) Co... | 4     | intel_s... | 7A01C63401 |
| 8086:02e8 | 1043:87bd | Intel      | Serial IO I2C Host Contro... | 4     | intel_l... | 7A01C63401 |
| 8086:02e9 | 1043:87bd | Intel      | Comet Lake Serial IO I2C ... | 4     | intel_l... | 7A01C63401 |
| 8086:02a4 | 8086:7270 | Intel      | Comet Lake SPI (flash) Co... | 3     | intel_s... | 1155D58828 |
| 8086:02e8 | 8086:7270 | Intel      | Serial IO I2C Host Contro... | 3     | intel_lpss | 1155D58828 |
| 10de:1adb | 8086:2090 | Nvidia     | TU106 USB Type-C UCSI Con... | 2     | i2c_nvi... | 7F8E6D2DA9 |
| 8086:06a4 | 103c:8710 | Intel      | Comet Lake PCH SPI Contro... | 2     |            | B2A212246B |
| 8086:06a4 | 19da:b440 | Intel      | Comet Lake PCH SPI Contro... | 2     | intel_s... | 57676DE735 |
| 8086:9da4 | 1043:8790 | Intel      | Cannon Point-LP SPI Contr... | 2     |            | 45389EF622 |
| 8086:9da4 | 17aa:314c | Intel      | Cannon Point-LP SPI Contr... | 2     |            | 0F66B49A44 |
| 8086:9da4 | 8086:2075 | Intel      | Cannon Point-LP SPI Contr... | 2     |            | D9AC661777 |
| 8086:9da4 | 8086:2079 | Intel      | Cannon Point-LP SPI Contr... | 2     |            | 45B14891D4 |
| 8086:9dc5 | 8086:2075 | Intel      | Cannon Point-LP Serial IO... | 2     | intel_lpss | D9AC661777 |
| 8086:9dc5 | 8086:2079 | Intel      | Cannon Point-LP Serial IO... | 2     | intel_lpss | 45B14891D4 |
| 8086:9de8 | 8086:2075 | Intel      | Cannon Point-LP Serial IO... | 2     | intel_lpss | D9AC661777 |
| 8086:9de8 | 8086:2079 | Intel      | Cannon Point-LP Serial IO... | 2     | intel_lpss | 45B14891D4 |
| 8086:9de9 | 8086:2075 | Intel      | Cannon Point-LP Serial IO... | 2     | intel_lpss | D9AC661777 |
| 8086:9de9 | 8086:2079 | Intel      | Cannon Point-LP Serial IO... | 2     | intel_lpss | 45B14891D4 |
| 8086:a0a4 | 8086:2090 | Intel      | Tiger Lake-LP SPI Controller | 2     | intel_s... | 7F8E6D2DA9 |
| 8086:a0a4 | 8086:3002 | Intel      | Tiger Lake-LP SPI Controller | 2     |            | 3738610B69 |
| 8086:a0e8 | 8086:2090 | Intel      | Tiger Lake-LP Serial IO I... | 2     | intel_l... | 7F8E6D2DA9 |
| 8086:a0e8 | 8086:3002 | Intel      | Tiger Lake-LP Serial IO I... | 2     | intel_l... | 3738610B69 |
| 8086:a0e9 | 8086:2090 | Intel      | Tiger Lake-LP Serial IO I... | 2     | intel_l... | 7F8E6D2DA9 |
| 8086:a0e9 | 8086:3002 | Intel      | Tiger Lake-LP Serial IO I... | 2     | intel_l... | 3738610B69 |
| 8086:a324 | 103c:8458 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 87E6E38B4A |
| 8086:a324 | 19da:b411 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | CF60BF6309 |
| 8086:a324 | 8086:2088 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 2AE39C4439 |
| 8086:a368 | 19da:b411 | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | CF60BF6309 |
| 8086:a368 | 8086:2088 | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | 2AE39C4439 |
| 8086:a369 | 19da:b411 | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | CF60BF6309 |
| 8086:a369 | 8086:2088 | Intel      | Cannon Lake PCH Serial IO... | 2     | intel_l... | 2AE39C4439 |
| 10de:1ad9 | 1458:3ff9 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     | i2c_nvi... | 9A5A163CB3 |
| 10de:1ad9 | 3842:2068 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     | i2c_nvi... | 0B21150424 |
| 10de:1adb | 1043:8784 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     |            | 2AE39C4439 |
| 10de:1adb | 19da:1529 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     | i2c_nvi... | DDCFB58F4C |
| 10de:1adb | 19da:2529 | Nvidia     | TU106 USB Type-C UCSI Con... | 1     | i2c_nvi... | CF60BF6309 |
| 8086:02ea | 8086:7270 | Intel      | Comet Lake PCH-LP LPSS: I... | 1     | intel_lpss | 1155D58828 |
| 8086:06a4 | 103c:871a | Intel      | Comet Lake PCH SPI Contro... | 1     |            | F74885CE0C |
| 8086:06a4 | 103c:8755 | Intel      | Comet Lake PCH SPI Contro... | 1     |            | 334ABF8C53 |
| 8086:06a4 | 17aa:316e | Intel      | Comet Lake PCH SPI Contro... | 1     | intel_s... | 7146ACBC96 |
| 8086:06a4 | 17aa:3172 | Intel      | Comet Lake PCH SPI Contro... | 1     |            | 3E09AE8DEE |
| 8086:06a4 | 17aa:3307 | Intel      | Comet Lake PCH SPI Contro... | 1     |            | D99E47E84D |
| 8086:0f08 | 8086:0f08 | Intel      | Atom Processor Z36xxx/Z37... | 1     | pwm_lps... | A968EF1DD8 |
| 8086:0f09 | 8086:0f09 | Intel      | Atom Processor Z36xxx/Z37... | 1     | pwm_lps... | A968EF1DD8 |
| 8086:22c2 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | i2c_des... | 10C1838B9D |
| 8086:22c3 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | i2c_des... | 10C1838B9D |
| 8086:22c4 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | i2c_des... | 10C1838B9D |
| 8086:22c6 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | i2c_des... | 10C1838B9D |
| 8086:22c7 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | i2c_des... | 10C1838B9D |
| 8086:4da4 | 1043:8813 | Intel      | JaserLake SPI (flash) Con... | 1     |            | 4EBA944D40 |
| 8086:4dab |           | Intel      | Jasper Lake LPSS: SPI Con... | 1     | intel_l... | 4EBA944D40 |
| 8086:4dc5 | 1043:8813 | Intel      | Jasper Lake LPSS: I2C Con... | 1     | intel_l... | 4EBA944D40 |
| 8086:4dc6 | 1043:8813 | Intel      | Jasper Lake LPSS: I2C Con... | 1     | intel_l... | 4EBA944D40 |
| 8086:4de8 | 1043:8813 | Intel      | Serial IO I2C Host Contro... | 1     | intel_l... | 4EBA944D40 |
| 8086:4dea | 1043:8813 | Intel      | Jasper Lake LPSS: I2C Con... | 1     | intel_l... | 4EBA944D40 |
| 8086:9da4 | 17aa:3144 | Intel      | Cannon Point-LP SPI Contr... | 1     |            | 8D0F1F5E39 |
| 8086:9dc5 | 17aa:3144 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | 8D0F1F5E39 |
| 8086:9de8 | 17aa:3144 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | 8D0F1F5E39 |
| 8086:9de8 | 17aa:314d | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | F2BD66E51A |
| 8086:9de9 | 17aa:3144 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | 8D0F1F5E39 |
| 8086:a0a4 | 8086:2091 | Intel      | Tiger Lake-LP SPI Controller | 1     |            | BD9CFC6A29 |
| 8086:a0a4 | 8086:3003 | Intel      | Tiger Lake-LP SPI Controller | 1     |            | ABC31CEA35 |
| 8086:a0a4 | 8086:3013 | Intel      | Tiger Lake-LP SPI Controller | 1     |            | 66A02F462F |
| 8086:a0e8 | 8086:3003 | Intel      | Tiger Lake-LP Serial IO I... | 1     | intel_l... | ABC31CEA35 |
| 8086:a0e8 | 8086:3013 | Intel      | Tiger Lake-LP Serial IO I... | 1     | intel_lpss | 66A02F462F |
| 8086:a0e9 | 8086:3003 | Intel      | Tiger Lake-LP Serial IO I... | 1     | intel_l... | ABC31CEA35 |
| 8086:a0e9 | 8086:3013 | Intel      | Tiger Lake-LP Serial IO I... | 1     | intel_lpss | 66A02F462F |
| 8086:a324 | 103c:8457 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | C15E7F2A47 |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816a | 1043:85b5 | Realtek... | RTL8111xP UART #1            | 16    | serial     | 9B5B350293 |
| 10ec:816b | 1043:85b5 | Realtek... | RTL8111xP UART #2            | 16    | serial     | 9B5B350293 |
| 8086:9d3d | 8086:2070 | Intel      | Sunrise Point-LP Active M... | 11    | serial     | CBF00091FA |
| 10ec:816a | 17aa:3130 | Realtek... | RTL8111xP UART #1            | 9     | serial     | 5981A4A25B |
| 10ec:816b | 17aa:3130 | Realtek... | RTL8111xP UART #2            | 9     | serial     | 5981A4A25B |
| 10ec:816a | 10ec:8168 | Realtek... | RTL8111xP UART #1            | 7     | serial     | DFCA28CC5F |
| 8086:a363 | 17aa:3135 | Intel      | Cannon Lake PCH Active Ma... | 7     | serial     | C43EF85B97 |
| 8086:a363 | 17aa:3136 | Intel      | Cannon Lake PCH Active Ma... | 6     | serial     | 2A2C128E48 |
| 10ec:816a | 17aa:3151 | Realtek... | RTL8111xP UART #1            | 5     | serial     | 76152DDCE8 |
| 10ec:816b | 17aa:3151 | Realtek... | RTL8111xP UART #2            | 5     | serial     | 76152DDCE8 |
| 8086:a2bd | 103c:829a | Intel      | 200 Series Chipset Family... | 5     | serial     | 1F3D092233 |
| 8086:a13d | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 4     | serial     | AC904E9BCB |
| 8086:06e3 | 103c:8710 | Intel      | Comet Lake Keyboard and T... | 2     | serial     | B2A212246B |
| 8086:8c3d | 103c:2145 | Intel      | 8 Series/C220 Series Chip... | 2     | serial     | 9C26D1B3DD |
| 8086:9de3 | 17aa:314c | Intel      | Cannon Point-LP Keyboard ... | 2     | serial     | 0F66B49A44 |
| 8086:a363 | 8086:2088 | Intel      | Cannon Lake PCH Active Ma... | 2     | serial     | 2AE39C4439 |
| 10ec:816a | 103c:8523 | Realtek... | RTL8111xP UART #1            | 1     |            | BAB721D52E |
| 10ec:816a | 17aa:30fd | Realtek... | RTL8111xP UART #1            | 1     | serial     | 5F6F9A1C6C |
| 10ec:816a | 17aa:3181 | Realtek... | RTL8111xP UART #1            | 1     | serial     | A203CD8C57 |
| 10ec:816b | 103c:8523 | Realtek... | RTL8111xP UART #2            | 1     |            | BAB721D52E |
| 10ec:816b | 10ec:8168 | Realtek... | RTL8111xP UART #2            | 1     |            | 5DD127A865 |
| 10ec:816b | 17aa:30fd | Realtek... | RTL8111xP UART #2            | 1     | serial     | 5F6F9A1C6C |
| 8086:06e3 | 103c:871a | Intel      | Comet Lake Keyboard and T... | 1     | serial     | F74885CE0C |
| 8086:06e3 | 17aa:3172 | Intel      | Comet Lake Keyboard and T... | 1     | serial     | 3E09AE8DEE |
| 8086:1e3d | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 1     | serial     | 04D1FD85D9 |
| 8086:9cbd | 8086:2058 | Intel      | Wildcat Point-LP KT Contr... | 1     | serial     | 4AB80B03C5 |
| 8086:a0e3 | 8086:3003 | Intel      | Tiger Lake-LP Active Mana... | 1     | serial     | ABC31CEA35 |
| 8086:a0e3 | 8086:3013 | Intel      | Tiger Lake-LP Active Mana... | 1     | serial     | 66A02F462F |
| 8086:a13d | 1019:9bc6 | Intel      | 100 Series/C230 Series Ch... | 1     | serial     | 7101BAED7A |
| 8086:a2bd | 103c:829e | Intel      | 200 Series Chipset Family... | 1     | serial     | 0028753E4D |
| 8086:a2bd | 17aa:310c | Intel      | 200 Series Chipset Family... | 1     | serial     | 60877665B6 |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9df9 | 8086:2074 | Intel      | Cannon Point-LP Thermal C... | 130   | intel_p... | 7EEEAAA250 |
| 8086:02f9 | 8086:2081 | Intel      | Comet Lake Thermal Subsytem  | 70    | intel_p... | 37E756FA81 |
| 8086:9d31 | 8086:2068 | Intel      | Sunrise Point-LP Thermal ... | 70    | intel_p... | 82B124D8C4 |
| 8086:5abc |           | Intel      | Celeron N3350/Pentium N42... | 35    | intel_l... | B1C4AF0594 |
| 8086:5ac4 |           | Intel      | Celeron N3350/Pentium N42... | 35    | intel_l... | B1C4AF0594 |
| 8086:5ac6 |           | Intel      | Celeron N3350/Pentium N42... | 35    | intel_l... | B1C4AF0594 |
| 8086:a127 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 35    | intel_l... | 507FBFC464 |
| 8086:a131 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 35    | intel_p... | 507FBFC464 |
| 8086:a160 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 35    | intel_l... | 507FBFC464 |
| 8086:a161 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 35    | intel_l... | 507FBFC464 |
| 8086:a162 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 35    | intel_l... | 507FBFC464 |
| 8086:5aac | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 32    | intel_l... | B1C4AF0594 |
| 8086:5ac2 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 32    | intel_l... | B1C4AF0594 |
| 8086:5a8c |           | Intel      | Atom/Celeron/Pentium Dyna... | 29    | process... | D831E8693D |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 29    | intel_l... | D831E8693D |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 29    | intel_l... | D831E8693D |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 29    | intel_l... | D831E8693D |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 29    | intel_l... | D831E8693D |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | intel_l... | D831E8693D |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | intel_l... | D831E8693D |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | intel_l... | D831E8693D |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | intel_l... | D831E8693D |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | intel_l... | D831E8693D |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | intel_l... | D831E8693D |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | intel_l... | D831E8693D |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | intel_l... | D831E8693D |
| 8086:a131 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 25    | intel_p... | FA1CECCEE5 |
| 1022:15e4 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Senso... | 21    | amd_sfh    | 4BA408D68C |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 21    | intel_l... | D831E8693D |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 20    | intel_l... | D831E8693D |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 20    | intel_l... | D831E8693D |
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 16    | process... | FD46C16BB7 |
| 8086:9d27 | 8086:2063 | Intel      | Sunrise Point-LP Serial I... | 15    | intel_l... | 38571FCFB9 |
| 8086:9d31 | 8086:2063 | Intel      | Sunrise Point-LP Thermal ... | 15    | intel_p... | 38571FCFB9 |
| 8086:9d31 | 8086:2070 | Intel      | Sunrise Point-LP Thermal ... | 14    | intel_p... | CBF00091FA |
| 8086:9d60 | 8086:2070 | Intel      | Sunrise Point-LP Serial I... | 14    | intel_l... | CBF00091FA |
| 8086:9d61 | 8086:2070 | Intel      | Sunrise Point-LP Serial I... | 14    | intel_l... | CBF00091FA |
| 8086:318c | 1043:875e | Intel      | Celeron/Pentium Silver Pr... | 10    | process... | 9D5F2807CE |
| 8086:9d31 | 8086:7270 | Intel      | Sunrise Point-LP Thermal ... | 7     | intel_p... | 1219FB4CEF |
| 8086:a379 | 8086:7270 | Intel      | Cannon Lake PCH Thermal C... | 7     | intel_p... | D09823163E |
| 8086:1903 | 17aa:314d | Intel      | Xeon E3-1200 v5/E3-1500 v... | 6     | process... | BD2F6222E5 |
| 8086:31c2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 6     | intel_lpss | 94025849E2 |
| 8086:31c4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 6     | intel_lpss | 94025849E2 |
| 8086:31c6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 6     | intel_lpss | 94025849E2 |
| 8086:9df9 | 17aa:314d | Intel      | Cannon Point-LP Thermal C... | 6     | intel_p... | BD2F6222E5 |
| 8086:a131 | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 6     | intel_p... | CC099348C2 |
| 8086:318c | 8086:318c | Intel      | Celeron/Pentium Silver Pr... | 5     | process... | C87DFAAC1F |
| 8086:31ac | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | 2048DCBA92 |
| 8086:31ae | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | 2048DCBA92 |
| 8086:31b0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | 2048DCBA92 |
| 8086:31b2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | 2048DCBA92 |
| 8086:31b4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | 2048DCBA92 |
| 8086:31b6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | 2048DCBA92 |
| 8086:31b8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | 2048DCBA92 |
| 8086:31ba | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_lpss | 2048DCBA92 |
| 8086:a2b1 | 103c:829a | Intel      | 200 Series PCH Thermal Su... | 5     |            | 1F3D092233 |
| 8086:a379 | 8086:2089 | Intel      | Cannon Lake PCH Thermal C... | 5     | intel_p... | 2EB74A58D2 |
| 8086:02f9 | 1043:87bd | Intel      | Comet Lake Thermal Subsytem  | 4     | intel_p... | 7A01C63401 |
| 8086:318c | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 4     | proc_th... | 94025849E2 |
| 8086:a131 | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 4     | intel_p... | AC904E9BCB |
| 8086:a2b1 | 103c:82a5 | Intel      | 200 Series PCH Thermal Su... | 4     |            | 08B98B6A88 |
| 8086:02f9 | 8086:7270 | Intel      | Comet Lake Thermal Subsytem  | 3     | intel_p... | 1155D58828 |
| 8086:31ac | 8086:31ac | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_lpss | C87DFAAC1F |
| 8086:31b2 | 8086:31b2 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_lpss | C87DFAAC1F |
| 8086:31bc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_lpss | 2048DCBA92 |
| 8086:31be | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_lpss | 2048DCBA92 |
| 8086:31c0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_lpss | 2048DCBA92 |
| 8086:31ee | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 3     | intel_lpss | 2048DCBA92 |
| 8086:5aac | 8086:5aac | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 9AA58951EA |
| 8086:5aae | 8086:5aae | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 9AA58951EA |
| 8086:5ab0 | 8086:5ab0 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 9AA58951EA |
| 8086:5abe | 8086:5abe | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 9AA58951EA |
| 8086:5ac0 | 8086:5ac0 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 9AA58951EA |
| 8086:5ac2 | 8086:5ac2 | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 9AA58951EA |
| 8086:5aee |           | Intel      | Celeron N3350/Pentium N42... | 3     | intel_l... | 9AA58951EA |
| 8086:a131 | 15d9:0898 | Intel      | 100 Series/C230 Series Ch... | 3     | intel_p... | 8D4CBF243D |
| 8086:a131 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 3     | intel_p... | CA900F89D0 |
| 8086:06f9 | 103c:8710 | Intel      | Comet Lake PCH Thermal Co... | 2     |            | B2A212246B |
| 8086:06f9 | 19da:b440 | Intel      | Comet Lake PCH Thermal Co... | 2     | intel_p... | 57676DE735 |
| 8086:1903 | 17aa:314c | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | process... | 0F66B49A44 |
| 8086:1e24 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 2     |            | 04D1FD85D9 |
| 8086:22dc |           | Intel      | Atom/Celeron/Pentium Proc... | 2     | proc_th... | 3AB4853FDD |
| 8086:31b4 | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_l... | E46F325CBA |
| 8086:31ba | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 2     | intel_l... | E46F325CBA |
| 8086:5a8c | 8086:5a8c | Intel      | Atom/Celeron/Pentium Dyna... | 2     | process... | 9AA58951EA |
| 8086:5ab2 | 8086:5ab2 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 9AA58951EA |
| 8086:5ab4 | 8086:5ab4 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 9AA58951EA |
| 8086:5ab6 | 8086:5ab6 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 9AA58951EA |
| 8086:5ab8 | 8086:5ab8 | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 9AA58951EA |
| 8086:5aba | 8086:5aba | Intel      | Celeron N3350/Pentium N42... | 2     | intel_l... | 9AA58951EA |
| 8086:9a0d |           | Intel      | Tigerlake Telemetry Aggre... | 2     | intel_pmt  | 7F8E6D2DA9 |
| 8086:9d27 | 1043:8694 | Intel      | Sunrise Point-LP Serial I... | 2     | intel_lpss | 847A813A2C |
| 8086:9df9 | 1043:8790 | Intel      | Cannon Point-LP Thermal C... | 2     | intel_p... | 45389EF622 |
| 8086:9df9 | 17aa:314c | Intel      | Cannon Point-LP Thermal C... | 2     | intel_p... | 0F66B49A44 |
| 8086:9df9 | 8086:2075 | Intel      | Cannon Point-LP Thermal C... | 2     | intel_p... | D9AC661777 |
| 8086:9df9 | 8086:2079 | Intel      | Cannon Point-LP Thermal C... | 2     | intel_p... | 45B14891D4 |
| 8086:a131 | 1019:9bc6 | Intel      | 100 Series/C230 Series Ch... | 2     | intel_p... | 7101BAED7A |
| 8086:a2b1 | 103c:829e | Intel      | 200 Series PCH Thermal Su... | 2     |            | 0028753E4D |
| 8086:a2b1 | 17aa:3111 | Intel      | 200 Series PCH Thermal Su... | 2     |            | A89ECD0B5F |
| 8086:a379 | 103c:8458 | Intel      | Cannon Lake PCH Thermal C... | 2     | intel_p... | 87E6E38B4A |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9da3 | 8086:2074 | Intel      | Cannon Point-LP SMBus Con... | 130   | i2c_i801   | 7EEEAAA250 |
| 8086:02a3 | 8086:2081 | Intel      | Comet Lake PCH-LP SMBus H... | 70    | i2c_i801   | 37E756FA81 |
| 8086:9d23 | 8086:2068 | Intel      | Sunrise Point-LP SMBus       | 70    | i2c_i801   | 82B124D8C4 |
| 8086:1e22 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 46    | i2c_i801   | 4D3FECA2AC |
| 8086:9ca2 | 8086:2057 | Intel      | Wildcat Point-LP SMBus Co... | 43    | i2c_i801   | 1B9BEEAF2D |
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 41    | i2c_i801   | D831E8693D |
| 8086:0f12 | 8086:0f12 | Intel      | Atom Processor E3800/CE27... | 38    | i2c_i801   | 0D4AC42F55 |
| 8086:a123 | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 35    | i2c_i801   | 507FBFC464 |
| 8086:2292 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 34    | i2c_i801   | 127B977658 |
| 8086:31d4 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 34    | i2c_i801   | C1F78B36E0 |
| 8086:1c22 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 33    | i2c_i801   | 8E878489D3 |
| 8086:5ad4 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 32    | i2c_i801   | B1C4AF0594 |
| 8086:9c22 | 8086:7270 | Intel      | 8 Series SMBus Controller    | 32    | i2c_i801   | A790DE17AA |
| 8086:a123 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 25    | i801_smbus | FA1CECCEE5 |
| 1022:790b | 1043:87e7 | AMD        | FCH SMBus Controller         | 20    | i2c_piix4  | 4BA408D68C |
| 10de:0aa2 | 10de:cb79 | Nvidia     | MCP79 SMBus                  | 19    | i2c_nfo... | 8699437E9E |
| 8086:27da | 8086:7270 | Intel      | NM10/ICH7 Family SMBus Co... | 17    | i2c_i801   | 68AD9FB8E9 |
| 8086:9d23 | 8086:2063 | Intel      | Sunrise Point-LP SMBus       | 15    | i2c_i801   | 38571FCFB9 |
| 10de:0d79 | 10de:cb89 | Nvidia     | MCP89 SMBus                  | 14    |            | CFCED2BB90 |
| 8086:9d23 | 8086:2070 | Intel      | Sunrise Point-LP SMBus       | 14    | i2c_i801   | CBF00091FA |
| 1002:4385 | 103c:17e2 | AMD        | SBx00 SMBus Controller       | 13    | i2c_piix4  | E1E74F57A7 |
| 8086:2292 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 13    | i2c_i801   | 10C1838B9D |
| 8086:a323 | 17aa:312d | Intel      | Cannon Lake PCH SMBus Con... | 13    | i2c_i801   | ACBB96BA48 |
| 8086:31d4 | 1043:875e | Intel      | Celeron/Pentium Silver Pr... | 10    | i2c_i801   | 9D5F2807CE |
| 1022:790b | 17aa:3130 | AMD        | FCH SMBus Controller         | 9     | i2c_pii... | 5981A4A25B |
| 8086:0f12 | 17aa:368d | Intel      | Atom Processor E3800/CE27... | 9     | i2c_i801   | 4713CA77A1 |
| 8086:31d4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 8     | i801_smbus | 94025849E2 |
| 8086:9ca2 | 8086:7270 | Intel      | Wildcat Point-LP SMBus Co... | 8     | i2c_i801   | 0A76AC3FB8 |
| 8086:a0a3 | 8086:3004 | Intel      | Tiger Lake-LP SMBus Contr... | 8     | i2c_i801   | 0279A35638 |
| 8086:a323 | 17aa:3135 | Intel      | Cannon Lake PCH SMBus Con... | 8     | i2c_i801   | C43EF85B97 |
| 1022:790b | 103c:872e | AMD        | FCH SMBus Controller         | 7     | i2c_piix4  | 137E91B812 |
| 8086:9d23 | 8086:7270 | Intel      | Sunrise Point-LP SMBus       | 7     | i2c_i801   | 1219FB4CEF |
| 8086:a323 | 8086:7270 | Intel      | Cannon Lake PCH SMBus Con... | 7     | i2c_i801   | D09823163E |
| 8086:0f12 |           | Intel      | Atom Processor E3800/CE27... | 6     | i2c_i801   | 2882CF9963 |
| 8086:0f12 | 17aa:30b5 | Intel      | Atom Processor E3800/CE27... | 6     | i2c_i801   | 538597F50A |
| 8086:5ad4 | 19da:b325 | Intel      | Celeron N3350/Pentium N42... | 6     | i2c_i801   | 23BDDBF63A |
| 8086:9da3 | 17aa:314d | Intel      | Cannon Point-LP SMBus Con... | 6     | i2c_i801   | BD2F6222E5 |
| 8086:a123 | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 6     | i2c_i801   | CC099348C2 |
| 8086:a323 | 17aa:3136 | Intel      | Cannon Lake PCH SMBus Con... | 6     | i2c_i801   | 2A2C128E48 |
| 1022:790b | 103c:8158 | AMD        | FCH SMBus Controller         | 5     | i2c_pii... | 95BC62EF3F |
| 1022:790b | 17aa:3151 | AMD        | FCH SMBus Controller         | 5     | i2c_piix4  | 76152DDCE8 |
| 8086:a2a3 | 103c:829a | Intel      | 200 Series/Z370 Chipset F... | 5     | i2c_i801   | 1F3D092233 |
| 8086:a323 | 8086:2089 | Intel      | Cannon Lake PCH SMBus Con... | 5     | i2c_i801   | 2EB74A58D2 |
| 1022:790b | 103c:8267 | AMD        | FCH SMBus Controller         | 4     | i2c_pii... | EDC6F2231B |
| 1022:790b | 103c:8836 | AMD        | FCH SMBus Controller         | 4     | i2c_piix4  | DA34E7C710 |
| 1022:790b | 17aa:312f | AMD        | FCH SMBus Controller         | 4     | i2c_pii... | 5205C41BC5 |
| 8086:02a3 | 1043:87bd | Intel      | Comet Lake PCH-LP SMBus H... | 4     | i2c_i801   | 7A01C63401 |
| 8086:0f12 | 19da:b219 | Intel      | Atom Processor E3800/CE27... | 4     | i2c_i801   | 34EFC38E50 |
| 8086:1e22 | 19da:b211 | Intel      | 7 Series/C216 Chipset Fam... | 4     | i2c_i801   | EFBBD0C3F8 |
| 8086:2292 | 17aa:30dd | Intel      | Atom/Celeron/Pentium Proc... | 4     | i2c_i801   | 0513ACEC04 |
| 8086:2292 | 17aa:3637 | Intel      | Atom/Celeron/Pentium Proc... | 4     | i2c_i801   | 9FC0FE4A5F |
| 8086:2292 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 4     | i2c_i801   | 0D05B404DD |
| 8086:8c22 | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 4     | i2c_i801   | FCAA602427 |
| 8086:9ca2 | 8086:2058 | Intel      | Wildcat Point-LP SMBus Co... | 4     | i2c_i801   | 6E19619F29 |
| 8086:a123 | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 4     | i2c_i801   | AC904E9BCB |
| 8086:a2a3 | 103c:82a5 | Intel      | 200 Series/Z370 Chipset F... | 4     | i2c_i801   | 08B98B6A88 |
| 1002:4385 | 19da:a191 | AMD        | SBx00 SMBus Controller       | 3     | i2c_piix4  | 121F403E29 |
| 8086:02a3 | 8086:7270 | Intel      | Comet Lake PCH-LP SMBus H... | 3     | i801_smbus | 1155D58828 |
| 8086:0f12 | 8086:7270 | Intel      | Atom Processor E3800/CE27... | 3     | i2c_i801   | EED35A825A |
| 8086:2292 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 3     | i2c_i801   | FDE91E565C |
| 8086:2292 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 3     | i2c_i801   | 7F47BED9CF |
| 8086:27da | 19da:a218 | Intel      | NM10/ICH7 Family SMBus Co... | 3     | i2c_i801   | 49EF2577E1 |
| 8086:27da | 8086:544b | Intel      | NM10/ICH7 Family SMBus Co... | 3     | i2c_i801   | 9DC27FC5BE |
| 8086:31d4 | 8086:31d4 | Intel      | Celeron/Pentium Silver Pr... | 3     | i2c_i801   | C87DFAAC1F |
| 8086:5ad4 | 8086:5ad4 | Intel      | Celeron N3350/Pentium N42... | 3     | i2c_i801   | 9AA58951EA |
| 8086:a123 | 15d9:0898 | Intel      | 100 Series/C230 Series Ch... | 3     | i2c_i801   | 8D4CBF243D |
| 8086:a123 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 3     | i2c_i801   | CA900F89D0 |
| 1002:4385 | 19da:a233 | AMD        | SBx00 SMBus Controller       | 2     | piix4_s... | 87C89614B1 |
| 1022:780b | 19da:a261 | AMD        | FCH SMBus Controller         | 2     | piix4_s... | 8C3CA64606 |
| 1022:780b | 19da:b233 | AMD        | FCH SMBus Controller         | 2     | piix4_s... | 514267F2D8 |
| 8086:06a3 | 103c:8710 | Intel      | Comet Lake PCH SMBus Cont... | 2     |            | B2A212246B |
| 8086:06a3 | 19da:b440 | Intel      | Comet Lake PCH SMBus Cont... | 2     | i2c_i801   | 57676DE735 |
| 8086:0f12 | 1071:0730 | Intel      | Atom Processor E3800/CE27... | 2     | i2c_i801   | BE63E554C5 |
| 8086:1c22 | 19da:b202 | Intel      | 6 Series/C200 Series Chip... | 2     | i2c_i801   | 4D23C29B62 |
| 8086:1e22 | 19da:a247 | Intel      | 7 Series/C216 Chipset Fam... | 2     | i2c_i801   | 4A3ACD7700 |
| 8086:1f3c | 8086:7270 | Intel      | Atom processor C2000 PCU ... | 2     | i2c_i801   | C1D37659C1 |
| 8086:2292 | 8086:2292 | Intel      | Atom/Celeron/Pentium Proc... | 2     | i2c_i801   | 3AB4853FDD |
| 8086:31d4 | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 2     |            | E46F325CBA |
| 8086:5ad4 | 8086:2080 | Intel      | Celeron N3350/Pentium N42... | 2     | i2c_i801   | 745C35E31C |
| 8086:8c22 | 103c:2145 | Intel      | 8 Series/C220 Series Chip... | 2     | i2c_i801   | 9C26D1B3DD |
| 8086:9c22 | 19da:b239 | Intel      | 8 Series SMBus Controller    | 2     | i2c_i801   | DCC5BDEF7D |
| 8086:9d23 | 103c:84f5 | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | C7B3D1917B |
| 8086:9d23 | 1043:8694 | Intel      | Sunrise Point-LP SMBus       | 2     | i801_smbus | 847A813A2C |
| 8086:9da3 | 1043:8790 | Intel      | Cannon Point-LP SMBus Con... | 2     | i2c_i801   | 45389EF622 |
| 8086:9da3 | 17aa:314c | Intel      | Cannon Point-LP SMBus Con... | 2     | i2c_i801   | 0F66B49A44 |
| 8086:9da3 | 8086:2075 | Intel      | Cannon Point-LP SMBus Con... | 2     | i801_smbus | D9AC661777 |
| 8086:9da3 | 8086:2079 | Intel      | Cannon Point-LP SMBus Con... | 2     | i801_smbus | 45B14891D4 |
| 8086:a0a3 | 8086:2090 | Intel      | Tiger Lake-LP SMBus Contr... | 2     | i2c_i801   | 7F8E6D2DA9 |
| 8086:a0a3 | 8086:3002 | Intel      | Tiger Lake-LP SMBus Contr... | 2     | i2c_i801   | 3738610B69 |
| 8086:a123 | 1019:9bc6 | Intel      | 100 Series/C230 Series Ch... | 2     | i2c_i801   | 7101BAED7A |
| 8086:a2a3 | 103c:829e | Intel      | 200 Series/Z370 Chipset F... | 2     | i2c_i801   | 0028753E4D |
| 8086:a2a3 | 17aa:3111 | Intel      | 200 Series/Z370 Chipset F... | 2     | i2c_i801   | A89ECD0B5F |
| 8086:a323 | 103c:8458 | Intel      | Cannon Lake PCH SMBus Con... | 2     |            | 87E6E38B4A |
| 8086:a323 | 19da:b411 | Intel      | Cannon Lake PCH SMBus Con... | 2     | i2c_i801   | CF60BF6309 |
| 8086:a323 | 8086:2088 | Intel      | Cannon Lake PCH SMBus Con... | 2     | i2c_i801   | 2AE39C4439 |
| 1002:4385 | 19da:a183 | AMD        | SBx00 SMBus Controller       | 1     | i2c_pii... | 037A3E45C7 |
| 1022:780b | 19da:b208 | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | C6C5AE5CC4 |
| 1022:780b | 19da:b218 | AMD        | FCH SMBus Controller         | 1     | i2c_pii... | EB76FF1C3F |
| 1022:790b | 103c:815a | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | 7D65A83025 |
| 1022:790b | 103c:8523 | AMD        | FCH SMBus Controller         | 1     | i2c_piix4  | BAB721D52E |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9dc8 | 8086:2074 | Intel      | Cannon Point-LP High Defi... | 127   | snd_hda... | 7EEEAAA250 |
| 8086:02c8 | 8086:2081 | Intel      | Comet Lake PCH-LP cAVS       | 70    | snd_hda... | 37E756FA81 |
| 8086:9d71 | 8086:2068 | Intel      | Sunrise Point-LP HD Audio    | 67    | snd_hda... | 82B124D8C4 |
| 8086:1e20 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 46    | snd_hda... | 4D3FECA2AC |
| 8086:9ca0 | 8086:2057 | Intel      | Wildcat Point-LP High Def... | 43    | snd_hda... | 1B9BEEAF2D |
| 8086:160c | 8086:2057 | Intel      | Broadwell-U Audio Controller | 42    | snd_hda... | 1B9BEEAF2D |
| 8086:a171 | 8086:2073 | Intel      | CM238 HD Audio Controller    | 35    | snd_hda... | 507FBFC464 |
| 8086:2284 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 34    | snd_hda... | 127B977658 |
| 8086:3198 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 34    | snd_hda... | C1F78B36E0 |
| 8086:1c20 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 33    | snd_hda... | 8E878489D3 |
| 8086:0a0c | 106b:0141 | Intel      | Haswell-ULT HD Audio Cont... | 32    | snd_hda... | A790DE17AA |
| 8086:9c20 | 8086:7270 | Intel      | 8 Series HD Audio Controller | 32    | snd_hda... | A790DE17AA |
| 1002:ab08 | 8086:2073 | AMD        | Polaris 22 HDMI Audio        | 31    | snd_hda... | 507FBFC464 |
| 8086:5a98 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 30    | snd_hda... | B1C4AF0594 |
| 8086:0f04 | 8086:0f04 | Intel      | Atom Processor Z36xxx/Z37... | 26    | snd_hda... | A346751093 |
| 8086:a170 | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 25    | snd_hda... | FA1CECCEE5 |
| 1002:1637 | 1002:1637 | AMD        | Renoir Radeon High Defini... | 21    | snd_hda... | 4BA408D68C |
| 10de:0ac0 | 10de:cb79 | Nvidia     | MCP79 High Definition Audio  | 19    | snd_hda... | 8699437E9E |
| 1022:15e3 | 1043:87bc | AMD        | Family 17h (Models 10h-1f... | 17    | snd_hda... | 9B5B350293 |
| 1002:15de | 1002:15de | AMD        | Raven/Raven2/Fenghuang HD... | 16    | snd_hda... | 5981A4A25B |
| 8086:27d8 | 8384:7680 | Intel      | NM10/ICH7 Family High Def... | 15    | snd_hda... | 68AD9FB8E9 |
| 10de:0d94 | 10de:cb89 | Nvidia     | MCP89 High Definition Audio  | 14    | snd_hda... | CFCED2BB90 |
| 8086:5a98 |           | Intel      | Celeron N3350/Pentium N42... | 14    | snd_hda... | 9AA58951EA |
| 8086:5a98 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 14    | snd_hda... | EB4D3C15D8 |
| 8086:9d70 | 8086:2063 | Intel      | Sunrise Point-LP HD Audio    | 14    | snd_hda... | 38571FCFB9 |
| 8086:9d71 | 8086:2070 | Intel      | Sunrise Point-LP HD Audio    | 14    | snd_hda... | CBF00091FA |
| 1002:1314 | 103c:17e2 | AMD        | Wrestler HDMI Audio          | 13    | snd_hda... | E1E74F57A7 |
| 1002:4383 | 103c:17e2 | AMD        | SBx00 Azalia (Intel HDA)     | 13    | snd_hda... | E1E74F57A7 |
| 8086:0f04 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 13    | snd_hda... | 0D4AC42F55 |
| 8086:2284 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 13    | snd_hda... | 10C1838B9D |
| 8086:a348 | 17aa:312d | Intel      | Cannon Lake PCH cAVS         | 13    | snd_hda... | ACBB96BA48 |
| 1002:aa90 | 0000:aa90 | AMD        | Turks HDMI Audio [Radeon ... | 12    | snd_hda... | 8E878489D3 |
| 8086:3198 | 1043:871d | Intel      | Celeron/Pentium Silver Pr... | 10    | snd_hda... | 9D5F2807CE |
| 1022:15e3 | 17aa:3130 | AMD        | Family 17h (Models 10h-1f... | 9     | snd_hda... | 5981A4A25B |
| 8086:0f04 | 17aa:368d | Intel      | Atom Processor Z36xxx/Z37... | 9     | snd_hda... | 4713CA77A1 |
| 8086:160c | 111e:10ec | Intel      | Broadwell-U Audio Controller | 9     | snd_hda... | 0A76AC3FB8 |
| 8086:5a98 | 10ec:1128 | Intel      | Celeron N3350/Pentium N42... | 8     | snd_hda... | D831E8693D |
| 8086:a0c8 | 8086:3004 | Intel      | Tiger Lake-LP Smart Sound... | 8     | snd_hda... | 0279A35638 |
| 8086:a348 | 17aa:3135 | Intel      | Cannon Lake PCH cAVS         | 8     | snd_hda... | C43EF85B97 |
| 1002:1637 | 103c:872e | AMD        | Renoir Radeon High Defini... | 7     | snd_hda... | 137E91B812 |
| 1022:15e3 | 103c:872e | AMD        | Family 17h (Models 10h-1f... | 7     | snd_hda... | 137E91B812 |
| 106b:1803 | 106b:1884 | Apple      | Audio Device                 | 7     |            | D09823163E |
| 1106:3288 | 1106:3288 | VIA Tec... | VX900/VT8xxx High Definit... | 7     | snd_hda... | CEDC05FE9E |
| 8086:9ca0 | 8086:7270 | Intel      | Wildcat Point-LP High Def... | 7     | snd_hda... | 0A76AC3FB8 |
| 8086:a348 | 8086:7270 | Intel      | Cannon Lake PCH cAVS         | 7     | snd_hda... | D09823163E |
| 8086:0f04 | 17aa:30b5 | Intel      | Atom Processor Z36xxx/Z37... | 6     | snd_hda... | 538597F50A |
| 8086:0f04 | 1b50:5709 | Intel      | Atom Processor Z36xxx/Z37... | 6     | snd_hda... | 2882CF9963 |
| 8086:3198 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 6     | snd_hda... | 94025849E2 |
| 8086:9d71 | 8086:7270 | Intel      | Sunrise Point-LP HD Audio    | 6     | snd_hda... | 1219FB4CEF |
| 8086:9dc8 | 17aa:314d | Intel      | Cannon Point-LP High Defi... | 6     | snd_hda... | BD2F6222E5 |
| 8086:a348 | 17aa:3136 | Intel      | Cannon Lake PCH cAVS         | 6     | snd_hda... | 2A2C128E48 |
| 1002:9840 | 103c:8158 | AMD        | Kabini HDMI/DP Audio         | 5     | snd_hda... | 95BC62EF3F |
| 1022:157a | 103c:8158 | AMD        | Family 15h (Models 60h-6f... | 5     | snd_hda... | 95BC62EF3F |
| 1022:15e3 | 17aa:3151 | AMD        | Family 17h (Models 10h-1f... | 5     | snd_hda... | 76152DDCE8 |
| 8086:5a98 | 10ec:0000 | Intel      | Celeron N3350/Pentium N42... | 5     | snd_hda... | D99861DA10 |
| 8086:a170 | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 5     | snd_hda... | A080CA6AD4 |
| 8086:a2f0 | 103c:829a | Intel      | 200 Series PCH HD Audio      | 5     | snd_hda... | 1F3D092233 |
| 8086:a348 | 8086:2089 | Intel      | Cannon Lake PCH cAVS         | 5     | snd_hda... | 2EB74A58D2 |
| 1002:15b3 | 103c:8267 | AMD        | High Definition Audio Con... | 4     | snd_hda... | EDC6F2231B |
| 1002:15b3 | 17aa:312f | AMD        | High Definition Audio Con... | 4     | snd_hda... | 5205C41BC5 |
| 1002:15de | 103c:8836 | AMD        | Raven/Raven2/Fenghuang HD... | 4     | snd_hda... | DA34E7C710 |
| 1002:aae0 | 8086:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 4     | snd_hda... | D9AC661777 |
| 1002:ab08 | 8086:ab08 | AMD        | Polaris 22 HDMI Audio        | 4     | snd_hda... | 122748D8A8 |
| 1022:157a | 103c:8267 | AMD        | Family 15h (Models 60h-6f... | 4     | snd_hda... | EDC6F2231B |
| 1022:157a | 17aa:312f | AMD        | Family 15h (Models 60h-6f... | 4     | snd_hda... | 5205C41BC5 |
| 1022:15e3 | 1043:8820 | AMD        | Family 17h (Models 10h-1f... | 4     | snd_hda... | 4BA408D68C |
| 10de:0fbc | 103c:82c0 | Nvidia     | GM107 High Definition Aud... | 4     | snd_hda... | AC904E9BCB |
| 8086:02c8 | 1043:87bc | Intel      | Comet Lake PCH-LP cAVS       | 4     | snd_hda... | 7A01C63401 |
| 8086:0c0c | 19da:b220 | Intel      | Xeon E3-1200 v3/4th Gen C... | 4     | snd_hda... | FCAA602427 |
| 8086:0f04 | 19da:b219 | Intel      | Atom Processor Z36xxx/Z37... | 4     | snd_hda... | 34EFC38E50 |
| 8086:160c | 8086:2058 | Intel      | Broadwell-U Audio Controller | 4     | snd_hda... | 6E19619F29 |
| 8086:1e20 | 19da:b211 | Intel      | 7 Series/C216 Chipset Fam... | 4     | snd_hda... | EFBBD0C3F8 |
| 8086:2284 | 17aa:30dd | Intel      | Atom/Celeron/Pentium Proc... | 4     | snd_hda... | 0513ACEC04 |
| 8086:2284 | 17aa:3637 | Intel      | Atom/Celeron/Pentium Proc... | 4     | snd_hda... | 9FC0FE4A5F |
| 8086:2284 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 4     | snd_hda... | 0D05B404DD |
| 8086:8c20 | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 4     | snd_hda... | FCAA602427 |
| 8086:9ca0 | 8086:2058 | Intel      | Wildcat Point-LP High Def... | 4     | snd_hda... | 6E19619F29 |
| 8086:a170 | 103c:82c0 | Intel      | 100 Series/C230 Series Ch... | 4     | snd_hda... | AC904E9BCB |
| 8086:a2f0 | 103c:82a5 | Intel      | 200 Series PCH HD Audio      | 4     | snd_hda... | 08B98B6A88 |
| 1002:1314 | 19da:a191 | AMD        | Wrestler HDMI Audio          | 3     | snd_hda... | 121F403E29 |
| 1002:4383 | 19da:a191 | AMD        | SBx00 Azalia (Intel HDA)     | 3     | snd_hda... | 121F403E29 |
| 1022:15e3 | 103c:8836 | AMD        | Family 17h (Models 10h-1f... | 3     | snd_hda... | DA34E7C710 |
| 10de:0e08 | 19da:2180 | Nvidia     | GF119 HDMI Audio Controller  | 3     | snd_hda... | 49EF2577E1 |
| 10de:0fb9 | 10de:1264 | Nvidia     | GP107GL High Definition A... | 3     | snd_hda... | B16B2D9BD5 |
| 10de:10f1 |           | Nvidia     | GP106 High Definition Aud... | 3     | snd_hda... | 29DC0371D1 |
| 8086:02c8 | 10ec:119e | Intel      | Comet Lake PCH-LP cAVS       | 3     | sof_aud... | 1155D58828 |
| 8086:0f28 | 8086:0f28 | Intel      | Atom Processor Z36xxx/Z37... | 3     |            | AD5481A5BC |
| 8086:2284 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 3     | snd_hda... | FDE91E565C |
| 8086:2284 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 3     | snd_hda... | 7F47BED9CF |
| 8086:27d8 | 19da:a218 | Intel      | NM10/ICH7 Family High Def... | 3     | snd_hda... | 49EF2577E1 |
| 8086:27d8 | 8086:d626 | Intel      | NM10/ICH7 Family High Def... | 3     | snd_hda... | 9DC27FC5BE |
| 8086:3198 | 10ec:119e | Intel      | Celeron/Pentium Silver Pr... | 3     | snd_hda... | C87DFAAC1F |
| 8086:5a98 | 10ec:111e | Intel      | Celeron N3350/Pentium N42... | 3     | snd_hda... | 1E917E7979 |
| 8086:a170 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 3     | snd_hda... | CA900F89D0 |
| 1002:1314 | 1002:1314 | AMD        | Wrestler HDMI Audio          | 2     | snd_hda... | 8C3CA64606 |
| 1002:1314 | 19da:a233 | AMD        | Wrestler HDMI Audio          | 2     | snd_hda... | 87C89614B1 |
| 1002:4383 | 19da:a233 | AMD        | SBx00 Azalia (Intel HDA)     | 2     | snd_hda... | 87C89614B1 |
| 1002:9840 | 1002:9840 | AMD        | Kabini HDMI/DP Audio         | 2     | snd_hda... | 514267F2D8 |
| 1022:780d | 19da:a261 | AMD        | FCH Azalia Controller        | 2     | snd_hda... | 8C3CA64606 |
| 1022:780d | 19da:b233 | AMD        | FCH Azalia Controller        | 2     | snd_hda... | 514267F2D8 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9dd3 | 8086:2074 | Intel      | Cannon Point-LP SATA Cont... | 126   | ahci       | 7EEEAAA250 |
| 8086:9d03 | 8086:2068 | Intel      | Sunrise Point-LP SATA Con... | 68    | ahci       | 82B124D8C4 |
| 8086:02d3 | 8086:2081 | Intel      | Comet Lake SATA AHCI Cont... | 67    | ahci       | 37E756FA81 |
| 8086:1e03 | 8086:7270 | Intel      | 7 Series Chipset Family 6... | 46    | ahci       | 4D3FECA2AC |
| 8086:9c83 | 8086:2057 | Intel      | Wildcat Point-LP SATA Con... | 42    | ahci       | 1B9BEEAF2D |
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 41    | ahci       | D831E8693D |
| 8086:0f23 | 8086:0f23 | Intel      | Atom Processor E3800 Seri... | 34    | ahci       | 0D4AC42F55 |
| 8086:22a3 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 34    | ahci       | 127B977658 |
| 8086:31e3 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 34    | ahci       | C1F78B36E0 |
| 8086:5ae3 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 32    | ahci       | B1C4AF0594 |
| 8086:9c03 | 8086:7270 | Intel      | 8 Series SATA Controller ... | 30    | ahci       | A790DE17AA |
| 8086:1c03 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 29    | ahci       | 8E878489D3 |
| 1022:7901 | 1043:87e7 | AMD        | FCH SATA Controller [AHCI... | 20    | ahci       | 4BA408D68C |
| 10de:0ab9 | 10de:cb79 | Nvidia     | MCP79 AHCI Controller        | 15    | ahci       | 8699437E9E |
| 8086:9d03 | 8086:2063 | Intel      | Sunrise Point-LP SATA Con... | 15    | ahci       | 38571FCFB9 |
| 10de:0d88 | 106b:cb89 | Nvidia     | MCP89 SATA Controller (AH... | 14    | ahci       | CFCED2BB90 |
| 8086:22a3 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 13    | ahci       | 10C1838B9D |
| 8086:9d03 | 8086:2070 | Intel      | Sunrise Point-LP SATA Con... | 13    | ahci       | CBF00091FA |
| 8086:a352 | 17aa:312d | Intel      | Cannon Lake PCH SATA AHCI... | 13    | ahci       | ACBB96BA48 |
| 8086:a103 | 8086:2064 | Intel      | HM170/QM170 Chipset SATA ... | 12    | ahci       | E7AEECFF98 |
| 1002:4390 | 103c:17e2 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 11    | ahci       | E1E74F57A7 |
| 8086:31e3 | 1043:875e | Intel      | Celeron/Pentium Silver Pr... | 10    | ahci       | 9D5F2807CE |
| 8086:0f23 | 17aa:368d | Intel      | Atom Processor E3800 Seri... | 9     | ahci       | 4713CA77A1 |
| 1022:7901 | 17aa:3130 | AMD        | FCH SATA Controller [AHCI... | 8     | ahci       | 5981A4A25B |
| 8086:31e3 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 8     | ahci       | 94025849E2 |
| 8086:a352 | 17aa:3135 | Intel      | Cannon Lake PCH SATA AHCI... | 8     | ahci       | C43EF85B97 |
| 1022:43eb | 103c:872e | AMD        | Starship/Matisse Chipset ... | 7     | ahci       | 137E91B812 |
| 8086:9c83 | 8086:7270 | Intel      | Wildcat Point-LP SATA Con... | 7     | ahci       | 0A76AC3FB8 |
| 8086:9d03 | 8086:7270 | Intel      | Sunrise Point-LP SATA Con... | 7     | ahci       | 1219FB4CEF |
| 8086:a0d3 | 8086:3004 | Intel      | Tiger Lake-LP SATA Contro... | 7     | ahci       | 0279A35638 |
| 8086:a103 | 8086:2073 | Intel      | HM170/QM170 Chipset SATA ... | 7     | ahci       | D186AF4EE3 |
| 8086:0f23 |           | Intel      | Atom Processor E3800 Seri... | 6     | ahci       | 2882CF9963 |
| 8086:0f23 | 17aa:30b5 | Intel      | Atom Processor E3800 Seri... | 6     | ahci       | 538597F50A |
| 8086:5ae3 | 19da:b325 | Intel      | Celeron N3350/Pentium N42... | 6     | ahci       | 23BDDBF63A |
| 8086:a102 | 19da:b333 | Intel      | Q170/Q150/B150/H170/H110/... | 6     | ahci       | CC099348C2 |
| 1022:7901 | 103c:8158 | AMD        | FCH SATA Controller [AHCI... | 5     | ahci       | 95BC62EF3F |
| 1022:7901 | 17aa:3151 | AMD        | FCH SATA Controller [AHCI... | 5     | ahci       | 76152DDCE8 |
| 1b4b:9215 | 1b4b:9215 | Marvell... | 88SE9215 PCIe 2.0 x1 4-po... | 5     | ahci       | ED960141AA |
| 8086:27c5 | 8086:7270 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 5     | ahci       | 68AD9FB8E9 |
| 8086:a352 | 17aa:3136 | Intel      | Cannon Lake PCH SATA AHCI... | 5     | ahci       | 2A2C128E48 |
| 8086:a353 | 8086:2089 | Intel      | Cannon Lake Mobile PCH SA... | 5     | ahci       | 2EB74A58D2 |
| 1022:43eb | 103c:8836 | AMD        | Starship/Matisse Chipset ... | 4     | ahci       | DA34E7C710 |
| 1022:7901 | 103c:8267 | AMD        | FCH SATA Controller [AHCI... | 4     | ahci       | EDC6F2231B |
| 1022:7901 | 17aa:312f | AMD        | FCH SATA Controller [AHCI... | 4     | ahci       | 5205C41BC5 |
| 8086:02d3 | 1043:87bd | Intel      | Comet Lake SATA AHCI Cont... | 4     | ahci       | 7A01C63401 |
| 8086:0f23 | 19da:b219 | Intel      | Atom Processor E3800 Seri... | 4     | ahci       | 34EFC38E50 |
| 8086:1e03 | 19da:b211 | Intel      | 7 Series Chipset Family 6... | 4     | ahci       | EFBBD0C3F8 |
| 8086:22a3 | 17aa:30dd | Intel      | Atom/Celeron/Pentium Proc... | 4     | ahci       | 0513ACEC04 |
| 8086:22a3 | 17aa:3637 | Intel      | Atom/Celeron/Pentium Proc... | 4     | ahci       | 9FC0FE4A5F |
| 8086:22a3 | 19da:b273 | Intel      | Atom/Celeron/Pentium Proc... | 4     | ahci       | 0D05B404DD |
| 8086:8c02 | 19da:b220 | Intel      | 8 Series/C220 Series Chip... | 4     | ahci       | FCAA602427 |
| 8086:9c83 | 8086:2058 | Intel      | Wildcat Point-LP SATA Con... | 4     | ahci       | 6E19619F29 |
| 8086:a282 | 103c:829a | Intel      | 200 Series PCH SATA contr... | 4     | ahci       | 1F3D092233 |
| 8086:a282 | 103c:82a5 | Intel      | 200 Series PCH SATA contr... | 4     | ahci       | 08B98B6A88 |
| 1002:4390 | 19da:a191 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 3     | ahci       | 121F403E29 |
| 8086:02d3 | 8086:7270 | Intel      | Comet Lake SATA AHCI Cont... | 3     | ahci       | 1155D58828 |
| 8086:0f23 | 8086:7270 | Intel      | Atom Processor E3800 Seri... | 3     | ahci       | EED35A825A |
| 8086:22a3 | 1462:b120 | Intel      | Atom/Celeron/Pentium Proc... | 3     | ahci       | FDE91E565C |
| 8086:22a3 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 3     | ahci       | 7F47BED9CF |
| 8086:31e3 | 8086:31e3 | Intel      | Celeron/Pentium Silver Pr... | 3     | ahci       | C87DFAAC1F |
| 8086:5ae3 | 8086:5ae3 | Intel      | Celeron N3350/Pentium N42... | 3     | ahci       | 9AA58951EA |
| 8086:a102 | 15d9:0898 | Intel      | Q170/Q150/B150/H170/H110/... | 3     | ahci       | 8D4CBF243D |
| 8086:a102 | 8086:7270 | Intel      | Q170/Q150/B150/H170/H110/... | 3     | ahci       | CA900F89D0 |
| 1002:4390 | 19da:a233 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 2     | ahci       | C95547D683 |
| 1002:4391 | 103c:17e2 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 2     | ahci       | BF35F8C621 |
| 1022:7801 | 19da:b233 | AMD        | FCH SATA Controller [AHCI... | 2     | ahci       | 514267F2D8 |
| 144d:a801 | 144d:a801 | Samsung... | Electronics SATA controller  | 2     | ahci       | E4A3A40AB2 |
| 1b21:0625 | 1b21:1060 | ASMedia... | 106x SATA/RAID Controller    | 2     | ahci       | 37D4C2C91D |
| 8086:06d2 | 103c:8710 | Intel      | Comet Lake SATA AHCI Cont... | 2     | ahci       | B2A212246B |
| 8086:06d2 | 19da:b440 | Intel      | Comet Lake SATA AHCI Cont... | 2     | ahci       | 57676DE735 |
| 8086:0f23 | 1071:0730 | Intel      | Atom Processor E3800 Seri... | 2     | ahci       | BE63E554C5 |
| 8086:1c02 | 19da:b202 | Intel      | 6 Series/C200 Series Chip... | 2     | ahci       | 4D23C29B62 |
| 8086:1e03 | 19da:a247 | Intel      | 7 Series Chipset Family 6... | 2     | ahci       | 4A3ACD7700 |
| 8086:1f22 | 8086:7270 | Intel      | Atom processor C2000 AHCI... | 2     | ahci       | C1D37659C1 |
| 8086:1f32 | 8086:7270 | Intel      | Atom processor C2000 AHCI... | 2     | ahci       | C1D37659C1 |
| 8086:27c1 | 19da:a218 | Intel      | NM10/ICH7 Family SATA Con... | 2     | ahci       | 49EF2577E1 |
| 8086:31e3 | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 2     | ahci       | E46F325CBA |
| 8086:5ae3 | 8086:2080 | Intel      | Celeron N3350/Pentium N42... | 2     | ahci       | 745C35E31C |
| 8086:8c02 | 103c:2145 | Intel      | 8 Series/C220 Series Chip... | 2     | ahci       | 9C26D1B3DD |
| 8086:9c03 | 19da:b239 | Intel      | 8 Series SATA Controller ... | 2     | ahci       | DCC5BDEF7D |
| 8086:9d03 | 103c:84f5 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | C7B3D1917B |
| 8086:9d03 | 1043:8694 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 847A813A2C |
| 8086:9dd3 | 1043:8790 | Intel      | Cannon Point-LP SATA Cont... | 2     | ahci       | 45389EF622 |
| 8086:9dd3 | 8086:2075 | Intel      | Cannon Point-LP SATA Cont... | 2     | ahci       | D9AC661777 |
| 8086:a0d3 | 8086:3002 | Intel      | Tiger Lake-LP SATA Contro... | 2     | ahci       | 3738610B69 |
| 8086:a102 | 1019:9bc6 | Intel      | Q170/Q150/B150/H170/H110/... | 2     | ahci       | 7101BAED7A |
| 8086:a282 | 17aa:3111 | Intel      | 200 Series PCH SATA contr... | 2     | ahci       | A89ECD0B5F |
| 8086:a353 | 19da:b411 | Intel      | Cannon Lake Mobile PCH SA... | 2     | ahci       | CF60BF6309 |
| 8086:a353 | 8086:2088 | Intel      | Cannon Lake Mobile PCH SA... | 2     | ahci       | 2AE39C4439 |
| 1002:4391 | 19da:a183 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 037A3E45C7 |
| 1002:4391 | 19da:a233 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 87C89614B1 |
| 1022:7800 | 19da:a261 | AMD        | FCH SATA Controller [IDE ... | 1     | ahci       | 8C3CA64606 |
| 1022:7801 | 19da:a261 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 8D13B8BFE3 |
| 1022:7801 | 19da:b208 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | C6C5AE5CC4 |
| 1022:7801 | 19da:b218 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | EB76FF1C3F |
| 1022:7901 | 103c:815a | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 7D65A83025 |
| 1022:7901 | 103c:8523 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | BAB721D52E |
| 1022:7901 | 1043:880a | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | CE3A7EA50E |
| 1022:7901 | 17aa:30fd | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 5F6F9A1C6C |
| 1022:7901 | 1854:0309 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | DC014D0C85 |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27df | 8086:7270 | Intel      | 82801G (ICH7 Family) IDE ... | 16    | pata_acpi  | 68AD9FB8E9 |
| 8086:27c4 | 8086:7270 | Intel      | 82801GBM/GHM (ICH7-M Fami... | 11    | pata_acpi  | C480910C6C |
| 1106:9001 | 1106:9001 | VIA Tec... | VX900 Series Serial-ATA C... | 8     | pata_vi... | 15268C0CCC |
| 10de:0ab5 | 10de:cb79 | Nvidia     | MCP79 SATA Controller        | 5     | ahci, p... | D65F9A48FD |
| 8086:1c01 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 4     | ata_pii... | 8DC468B83D |
| 1002:439c | 19da:a191 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 3     | pata_at... | 121F403E29 |
| 8086:27c0 | 8086:544b | Intel      | NM10/ICH7 Family SATA Con... | 3     | ata_pii... | 9DC27FC5BE |
| 1002:439c | 19da:a233 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 2     | pata_at... | 87C89614B1 |
| 1022:780c | 19da:a261 | AMD        | FCH IDE Controller           | 2     | pata_at... | 8C3CA64606 |
| 1002:439c | 19da:a183 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | pata_at... | 037A3E45C7 |
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
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 132   | nvme       | 7F8E6D2DA9 |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 33    | nvme       | BC9337F46E |
| 126f:2263 | 126f:2263 | Silicon... | SM2263EN/SM2263XT SSD Con... | 13    | nvme       | 1155D58828 |
| 2646:2263 | 2646:2263 | Kingsto... | A2000 NVMe SSD               | 13    | nvme       | FFDC0DC1D7 |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 13    | nvme       | D8F20BC651 |
| 15b7:5006 | 15b7:5006 | Sandisk    | WD Black SN750 / PC SN730... | 11    | nvme       | C43EF85B97 |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 11    | nvme       | AE39D6A5FC |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 11    | nvme       | 6A36C68267 |
| c0a9:2263 | c0a9:2263 | Micron/... | P1 NVMe PCIe SSD             | 9     | nvme       | 4176A10062 |
| 144d:a809 | 144d:a801 | Samsung... | NVMe SSD Controller 980      | 8     | nvme       | D99E47E84D |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/SN750 / PC ... | 8     | nvme       | 28CE3A6F8D |
| 106b:2005 | 106b:1800 | Apple      | ANS2 NVMe Controller         | 7     | nvme       | D09823163E |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 7     | nvme       | F86F736FC1 |
| 144d:a80a | 144d:a801 | Samsung... | NVMe SSD Controller PM9A1... | 7     | nvme       | 8ADD857C1A |
| 15b7:5009 | 15b7:5009 | Sandisk    | WD Blue SN550 NVMe SSD       | 6     | nvme       | 7A01C63401 |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 5     | nvme       | 507FBFC464 |
| 1987:5008 | 1987:5008 | Phison ... | NVMe Storage Controller      | 5     | nvme       | 161445E905 |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 5     | nvme       | 66A02F462F |
| c0a9:540a | c0a9:540a | Micron/... | P2 NVMe PCIe SSD             | 5     | nvme       | C294748851 |
| 1179:011a | 1179:0001 | Toshiba... | XG6 NVMe SSD Controller      | 4     | nvme       | 5205C41BC5 |
| 1987:5016 | 1987:5016 | Phison ... | E16 PCIe4 NVMe Controller    | 4     | nvme       | 507FBFC464 |
| 1c5c:1627 | 1c5c:1627 | SK Hynix   | Non-Volatile memory contr... | 4     | nvme       | B1DE952C4E |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 4     | nvme       | 74817FDCB8 |
| 126f:2262 | 126f:2262 | Silicon... | SM2262/SM2262EN SSD Contr... | 3     | nvme       | 0C063B9772 |
| 15b7:5005 | 15b7:5005 | Sandisk    | PC SN520 NVMe SSD            | 3     | nvme       | 3376399C24 |
| 15b7:5011 | 15b7:5011 | Sandisk    | WD Black SN850               | 3     | nvme       | DAAB62B41A |
| 1987:5013 | 1987:5013 | Phison ... | PS5013 E13 NVMe Controller   | 3     | nvme       | 4BA408D68C |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | BC501 NVMe Solid State Drive | 3     | nvme       | 7795BF0D95 |
| 1c5c:1639 | 1c5c:1639 | SK Hynix   | Non-Volatile memory contr... | 3     | nvme       | B41631FF89 |
| 2646:5008 | 2646:5008 | Kingsto... | U-SNS8154P3 NVMe SSD         | 3     | nvme       | 053EA52CD6 |
| 8086:2522 | 8086:3806 | Intel      | NVMe Optane Memory Series    | 3     | nvme       | 13353E2037 |
| 1022:b000 | 144d:a801 | AMD        | RAID Bottom Device           | 2     | nvme       | F2418E15EC |
| 10ec:5760 | 5760:10ec | Realtek... | Realtek Non-Volatile memo... | 2     | nvme       | 596EEA9169 |
| 10ec:5762 | 10ec:5762 | Realtek... | RTS5763DL NVMe SSD Contro... | 2     | nvme       | 847A813A2C |
| 10ec:5763 | 10ec:5763 | Realtek... | Realtek Non-Volatile memo... | 2     | nvme       | A03DE89D54 |
| 1987:5007 | 1987:5007 | Phison ... | E7 NVMe Controller           | 2     | nvme       | F9C39F6628 |
| 1b85:6018 | 1b85:6018 | OCZ Tec... | RD400/400A SSD               | 2     | nvme       | CC099348C2 |
| 1c5c:1339 | 1c5c:0000 | SK Hynix   | BC511                        | 2     | nvme       | DFCA28CC5F |
| 1c5c:174a | 1c5c:174a | SK Hynix   | Gold P31 SSD                 | 2     | nvme       | 5913CE5951 |
| 2646:2262 | 2646:2262 | Kingsto... | KC2000 NVMe SSD              | 2     | nvme       | 744AB63B06 |
| 2646:500e | 2646:500e | Kingsto... | SNVS2000G [NV1 NVMe PCIe ... | 2     | nvme       | FA1CECCEE5 |
| 8086:faf0 | 8086:390e | Intel      | Non-Volatile memory contr... | 2     | nvme       | 391F80AE12 |
| c0a9:5412 | c0a9:0100 | Micron/... | Non-Volatile memory contr... | 2     | nvme       | 3738610B69 |
| 1022:b000 | 15b7:5006 | AMD        | RAID Bottom Device           | 1     | nvme       | 0E48C94F83 |
| 1179:0115 | 1179:0001 | Toshiba... | XG4 NVMe SSD Controller      | 1     | nvme       | C78FC3BDF3 |
| 126f:2260 | 126f:2260 | Silicon... | Non-Volatile memory contr... | 1     | nvme       | 400EFE971D |
| 1344:5405 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 1     | nvme       | AD99B098F1 |
| 14a4:22f1 | 1b4b:1093 | Lite-On... | M8Pe Series NVMe SSD         | 1     | nvme       | 0521601823 |
| 14a4:2300 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 1     | nvme       | D66B009299 |
| 14a4:23f1 | 1b4b:1093 | Lite-On... | Non-Volatile memory contr... | 1     | nvme       | 7A38C478BB |
| 15b7:5001 | 1b4b:1093 | Sandisk    | WD Black NVMe SSD            | 1     | nvme       | 2ED31BB0E7 |
| 15b7:5003 | 15b7:5003 | Sandisk    | WD Blue SN500 / PC SN520 ... | 1     | nvme       | 4D929C77F8 |
| 15b7:5019 | 15b7:5019 | Sandisk    | Non-Volatile memory contr... | 1     | nvme       | E1C9DADB12 |
| 1cc4:17aa | 1cc4:1008 | Union M... | Non-Volatile memory contr... | 1     | nvme       | 4C26C41224 |
| 1cc4:17ab | 1cc4:1007 | Union M... | NVMe 256G SSD device         | 1     | nvme       | 2A2C128E48 |
| 1d79:2263 | 1d79:2263 |            | Non-Volatile memory contr... | 1     | nvme       | 9B65DA6FB7 |
| 1e0f:0001 | 1e0f:0001 | KIOXIA     | Non-Volatile memory contr... | 1     | nvme       | DA34E7C710 |
| 1e0f:0009 | 1e0f:0001 | KIOXIA     | NVMe SSD                     | 1     | nvme       | A1FFAD5B6D |
| 8086:2522 | 8086:3810 | Intel      | NVMe Optane Memory Series    | 1     | nvme       | D0D875E1E5 |
| c0a9:5403 | c0a9:1100 | Micron/... | NVMe Controller              | 1     | nvme       | 7EEEAAA250 |
| c0a9:5403 | c0a9:2100 | Micron/... | NVMe Controller              | 1     | nvme       | 7988A9C084 |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2822 | 103c:82c0 | Intel      | SATA Controller [RAID mode]  | 4     | ahci       | AC904E9BCB |
| 8086:282a | 8086:2074 | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | D0D875E1E5 |
| 8086:2822 | 103c:8458 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 87E6E38B4A |
| 8086:282a | 8086:2081 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 5913CE5951 |
| 1022:43bd | 103c:872c | AMD        | FCH RAID Controller          | 1     |            | 0E48C94F83 |
| 8086:2822 | 103c:829a | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | E0FB7EA560 |
| 8086:2822 | 103c:829e | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | 0028753E4D |
| 8086:282a | 19da:b248 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | D521E3AD79 |
| 8086:282a | 8086:2068 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 3A0E961B45 |
| 8086:282a | 8086:2079 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 985AA77681 |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1911 | 8086:2074 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 130   |            | 7EEEAAA250 |
| 8086:1911 | 8086:2068 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 70    |            | 82B124D8C4 |
| 8086:1911 | 8086:2081 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 69    |            | 37E756FA81 |
| 8086:15e8 | 8086:2081 | Intel      | JHL7540 Thunderbolt 3 NHI... | 68    | thunder... | 37E756FA81 |
| 8086:1911 | 8086:2073 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 35    |            | 507FBFC464 |
| 8086:1513 | 2222:1111 | Intel      | CV82524 Thunderbolt Contr... | 33    | thunder... | 8E878489D3 |
| 8086:156c |           | Intel      | DSL5520 Thunderbolt 2 NHI... | 29    | thunder... | AE1729D840 |
| 8086:1911 | 8086:2064 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 25    |            | FA1CECCEE5 |
| 8086:1911 | 8086:2070 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 14    |            | CBF00091FA |
| 8086:1911 | 17aa:312d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 13    |            | ACBB96BA48 |
| 8086:3190 | 1043:875e | Intel      | Celeron/Pentium Silver Pr... | 10    |            | 9D5F2807CE |
| 8086:1911 | 8086:2015 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 9     |            | CA900F89D0 |
| 8086:1911 | 17aa:3135 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 8     |            | C43EF85B97 |
| 8086:9a11 | 8086:3004 | Intel      | GNA Scoring Accelerator m... | 8     |            | 0279A35638 |
| 8086:15eb | 8086:0000 | Intel      | JHL7540 Thunderbolt 3 NHI... | 7     | thunder... | D09823163E |
| 8086:15eb | 8086:2088 | Intel      | JHL7540 Thunderbolt 3 NHI... | 7     | thunder... | 2AE39C4439 |
| 8086:15d9 | 8086:2074 | Intel      | JHL6340 Thunderbolt 3 NHI... | 6     | thunder... | 4A94A9D35A |
| 8086:1911 | 17aa:3136 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 6     |            | 2A2C128E48 |
| 8086:1911 | 17aa:314d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 6     |            | BD2F6222E5 |
| 8086:1911 | 19da:b333 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | CC099348C2 |
| 8086:1911 | 8086:2089 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 5     |            | 2EB74A58D2 |
| 8086:1575 | 2222:1111 | Intel      | DSL6340 Thunderbolt 3 NHI... | 4     | thunder... | E7AEECFF98 |
| 8086:15de | 2222:1111 | Intel      | JHL6340 Thunderbolt 3 Con... | 4     | thunder... | 78B5820785 |
| 8086:3190 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 4     |            | 94025849E2 |
| 8086:1911 | 8086:7270 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | 1155D58828 |
| 8086:1911 | 1019:9bc6 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 7101BAED7A |
| 8086:1911 | 17aa:314c | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 0F66B49A44 |
| 8086:1911 | 19da:b411 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | CF60BF6309 |
| 8086:1911 | 19da:b440 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 57676DE735 |
| 8086:1911 | 8086:2079 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 45B14891D4 |
| 8086:1911 | 8086:2088 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 2     |            | 2AE39C4439 |
| 8086:1f15 | 8086:0000 | Intel      | Atom processor C2000 SMBu... | 2     | i2c_ismt   | C1D37659C1 |
| 8086:3190 | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 2     |            | E46F325CBA |
| 8086:3190 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 2     |            | 4C465E5A03 |
| 8086:5a11 | 8086:2075 | Intel      | System peripheral            | 2     |            | D9AC661777 |
| 8086:9a11 | 8086:2090 | Intel      | GNA Scoring Accelerator m... | 2     |            | 7F8E6D2DA9 |
| 8086:9a11 | 8086:3002 | Intel      | GNA Scoring Accelerator m... | 2     |            | 3738610B69 |
| 8086:1577 | 2222:1111 | Intel      | DSL6540 Thunderbolt 3 NHI... | 1     | thunder... | 40AEEA62F1 |
| 8086:15d2 | 8086:2073 | Intel      | JHL6540 Thunderbolt 3 NHI... | 1     | thunder... | 9A5A163CB3 |
| 8086:15d9 | 8086:0000 | Intel      | JHL6340 Thunderbolt 3 NHI... | 1     | thunder... | 42A1AEA9C7 |
| 8086:1911 | 17aa:3144 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 8D0F1F5E39 |
| 8086:1911 | 17aa:316e | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 7146ACBC96 |
| 8086:1911 | 17aa:3172 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 3E09AE8DEE |
| 8086:1911 | 17aa:3307 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | D99E47E84D |
| 8086:3584 | 8086:1977 | Intel      | 82852/82855 GM/GME/PM/GMV... | 1     |            | 4A3E3CD4EE |
| 8086:3585 | 8086:1977 | Intel      | 82852/82855 GM/GME/PM/GMV... | 1     |            | 4A3E3CD4EE |
| 8086:4e11 | 1043:8813 | Intel      | System peripheral            | 1     |            | 4EBA944D40 |
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
| 8086:9ded | 8086:2074 | Intel      | Cannon Point-LP USB 3.1 x... | 130   | xhci_hcd   | 7EEEAAA250 |
| 8086:02ed | 8086:2081 | Intel      | Comet Lake PCH-LP USB 3.1... | 70    | xhci_hcd   | 37E756FA81 |
| 8086:9d2f | 8086:2068 | Intel      | Sunrise Point-LP USB 3.0 ... | 70    | xhci_hcd   | 82B124D8C4 |
| 8086:15e9 | 8086:2081 | Intel      | JHL7540 Thunderbolt 3 USB... | 68    | xhci_hcd   | 37E756FA81 |
| 8086:0f35 | 8086:0f35 | Intel      | Atom Processor Z36xxx/Z37... | 67    | xhci_hcd   | E70B15E489 |
| 8086:1e26 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 46    | ehci_pci   | 4D3FECA2AC |
| 8086:1e2d | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 46    | ehci_pci   | 4D3FECA2AC |
| 8086:1e31 | 8086:7270 | Intel      | 7 Series/C210 Series Chip... | 46    | xhci_hcd   | 4D3FECA2AC |
| 8086:9cb1 | 8086:2057 | Intel      | Wildcat Point-LP USB xHCI... | 42    | xhci_hcd   | 1B9BEEAF2D |
| 8086:5aa8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 41    | xhci_hcd   | D831E8693D |
| 8086:9ca6 | 8086:2057 | Intel      | Wildcat Point-LP USB EHCI... | 40    | ehci_pci   | 1B9BEEAF2D |
| 1b21:2142 | 8086:2073 | ASMedia... | ASM2142 USB 3.1 Host Cont... | 35    | xhci_hcd   | 507FBFC464 |
| 8086:a12f | 8086:2073 | Intel      | 100 Series/C230 Series Ch... | 35    | xhci_hcd   | 507FBFC464 |
| 8086:15db | 8086:2074 | Intel      | JHL6340 Thunderbolt 3 USB... | 34    | xhci_hcd   | 0C063B9772 |
| 8086:31a8 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 34    | xhci_hcd   | C1F78B36E0 |
| 8086:1c26 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 33    | ehci_pci   | 8E878489D3 |
| 8086:1c27 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 33    | uhci_hcd   | 8E878489D3 |
| 8086:1c2c | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 33    | uhci_hcd   | 8E878489D3 |
| 8086:1c2d | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 33    | ehci_pci   | 8E878489D3 |
| 8086:5aa8 | 8086:2067 | Intel      | Celeron N3350/Pentium N42... | 32    | xhci_hcd   | B1C4AF0594 |
| 8086:9c31 | 8086:7270 | Intel      | 8 Series USB xHCI HC         | 32    | xhci_hcd   | A790DE17AA |
| 8086:22b5 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 28    | xhci_hcd   | FD46C16BB7 |
| 8086:a12f | 8086:2064 | Intel      | 100 Series/C230 Series Ch... | 25    | xhci_hcd   | FA1CECCEE5 |
| 8086:22b5 |           | Intel      | Atom/Celeron/Pentium Proc... | 24    | xhci_hcd   | 127B977658 |
| 1b21:1142 | 1043:85bf | ASMedia... | ASM1042A USB 3.0 Host Con... | 21    | xhci_pci   | 4BA408D68C |
| 1022:1639 | 1043:87e7 | AMD        | Renoir/Cezanne USB 3.1       | 20    | xhci_pci   | 4BA408D68C |
| 10de:0aa5 | 10de:cb79 | Nvidia     | MCP79 OHCI USB 1.1 Contro... | 19    | ohci_pci   | 8699437E9E |
| 10de:0aa6 | 10de:cb79 | Nvidia     | MCP79 EHCI USB 2.0 Contro... | 19    | ehci_pci   | 8699437E9E |
| 10de:0aa7 | 10de:cb79 | Nvidia     | MCP79 OHCI USB 1.1 Contro... | 19    | ohci_pci   | 8699437E9E |
| 10de:0aa9 | 10de:cb79 | Nvidia     | MCP79 EHCI USB 2.0 Contro... | 19    | ehci_pci   | 8699437E9E |
| 8086:27c8 | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 17    | uhci_hcd   | 68AD9FB8E9 |
| 8086:27c9 | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 17    | uhci_hcd   | 68AD9FB8E9 |
| 8086:27ca | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 17    | uhci_hcd   | 68AD9FB8E9 |
| 8086:27cb | 8086:7270 | Intel      | NM10/ICH7 Family USB UHCI... | 17    | uhci_hcd   | 68AD9FB8E9 |
| 8086:27cc | 8086:7270 | Intel      | NM10/ICH7 Family USB2 EHC... | 17    | ehci_pci   | 68AD9FB8E9 |
| 10ec:816d | 1043:85b5 | Realtek... | RTL811x EHCI host controller | 16    | ehci_pci   | 9B5B350293 |
| 8086:9d2f | 8086:2063 | Intel      | Sunrise Point-LP USB 3.0 ... | 15    | xhci_hcd   | 38571FCFB9 |
| 10de:0d9c | 10de:cb89 | Nvidia     | MCP89 OHCI USB 1.1 Contro... | 14    | ohci_pci   | CFCED2BB90 |
| 10de:0d9d | 10de:cb89 | Nvidia     | MCP89 EHCI USB 2.0 Contro... | 14    | ehci_pci   | CFCED2BB90 |
| 8086:9a13 |           | Intel      | Tiger Lake-LP Thunderbolt... | 14    | xhci_pci   | 7F8E6D2DA9 |
| 8086:9a1d | 2222:1111 | Intel      | Tiger Lake-LP Thunderbolt... | 14    | thunder... | 7F8E6D2DA9 |
| 8086:9d2f | 8086:2070 | Intel      | Sunrise Point-LP USB 3.0 ... | 14    | xhci_hcd   | CBF00091FA |
| 1002:4396 | 103c:17e2 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 13    | ehci_pci   | E1E74F57A7 |
| 1002:4397 | 103c:17e2 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 13    | ohci_pci   | E1E74F57A7 |
| 104c:8241 | 103c:17e2 | Texas I... | TUSB73x0 SuperSpeed USB 3... | 13    | xhci_pci   | E1E74F57A7 |
| 8086:9a1b | 2222:1111 | Intel      | Tiger Lake-LP Thunderbolt... | 13    | thunder... | 7F8E6D2DA9 |
| 8086:a36d | 17aa:312d | Intel      | Cannon Lake PCH USB 3.1 x... | 13    | xhci_hcd   | ACBB96BA48 |
| 8086:15db | 2222:1111 | Intel      | JHL6340 Thunderbolt 3 USB... | 12    | xhci_hcd   | 053EA52CD6 |
| 8086:0f34 | 8086:0f34 | Intel      | Atom Processor Z36xxx/Z37... | 10    | ehci_pci   | 0D4AC42F55 |
| 8086:0f37 | 8086:0f37 | Intel      | Atom Processor Z36xxx/Z37... | 10    | dwc3_pci   | E70B15E489 |
| 8086:15db | 8086:0000 | Intel      | JHL6340 Thunderbolt 3 USB... | 10    | xhci_hcd   | 82B124D8C4 |
| 8086:22b5 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 10    | xhci_pci   | 17889A968C |
| 8086:31a8 | 1043:875e | Intel      | Celeron/Pentium Silver Pr... | 10    | xhci_hcd   | 9D5F2807CE |
| 1022:15e0 | 17aa:3130 | AMD        | Raven USB 3.1                | 9     | xhci_hcd   | 5981A4A25B |
| 1022:15e1 | 17aa:3130 | AMD        | Raven USB 3.1                | 9     | xhci_hcd   | 5981A4A25B |
| 10ec:816d | 17aa:3130 | Realtek... | RTL811x EHCI host controller | 9     | ehci_pci   | 5981A4A25B |
| 1b21:1242 | 1b21:1242 | ASMedia... | ASM1142 USB 3.1 Host Cont... | 9     | xhci_hcd   | CC099348C2 |
| 8086:0f35 | 17aa:368d | Intel      | Atom Processor Z36xxx/Z37... | 9     | xhci_pci   | 4713CA77A1 |
| 1106:3038 | 1106:3038 | VIA Tec... | VT82xx/62xx/VX700/8x0/900... | 8     | uhci_hcd   | 15268C0CCC |
| 1106:3104 | 1106:3104 | VIA Tec... | USB 2.0 EHCI-Compliant Ho... | 8     | ehci_pci   | 15268C0CCC |
| 8086:31a8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 8     | xhci_hcd   | 94025849E2 |
| 8086:9ca6 | 8086:7270 | Intel      | Wildcat Point-LP USB EHCI... | 8     | ehci_pci   | 0A76AC3FB8 |
| 8086:9cb1 | 8086:7270 | Intel      | Wildcat Point-LP USB xHCI... | 8     | xhci_pci   | 0A76AC3FB8 |
| 8086:a0ed | 8086:3004 | Intel      | Tiger Lake-LP USB 3.2 Gen... | 8     | xhci_pci   | 0279A35638 |
| 8086:a36d | 17aa:3135 | Intel      | Cannon Lake PCH USB 3.1 x... | 8     | xhci_hcd   | C43EF85B97 |
| 1022:1639 | 103c:872e | AMD        | Renoir/Cezanne USB 3.1       | 7     | xhci_pci   | 137E91B812 |
| 1022:43ef | 103c:872e | AMD        | USB Controller               | 7     | xhci_pci   | 137E91B812 |
| 10ec:816d | 10ec:8168 | Realtek... | RTL811x EHCI host controller | 7     | ehci_pci   | DFCA28CC5F |
| 1b21:2142 | 1b21:2142 | ASMedia... | ASM2142 USB 3.1 Host Cont... | 7     | xhci_hcd   | 1219FB4CEF |
| 8086:15d4 | 8086:2073 | Intel      | JHL6540 Thunderbolt 3 USB... | 7     | xhci_pci   | 507FBFC464 |
| 8086:15ec | 8086:0000 | Intel      | JHL7540 Thunderbolt 3 USB... | 7     | xhci_pci   | D09823163E |
| 8086:15ec | 8086:2088 | Intel      | JHL7540 Thunderbolt 3 USB... | 7     | xhci_pci   | 2AE39C4439 |
| 8086:9d2f | 8086:7270 | Intel      | Sunrise Point-LP USB 3.0 ... | 7     | xhci_hcd   | 1219FB4CEF |
| 8086:a36d | 8086:7270 | Intel      | Cannon Lake PCH USB 3.1 x... | 7     | xhci_pci   | D09823163E |
| 8086:0f35 |           | Intel      | Atom Processor Z36xxx/Z37... | 6     | xhci_pci   | 2882CF9963 |
| 8086:0f35 | 17aa:30b5 | Intel      | Atom Processor Z36xxx/Z37... | 6     | xhci_hcd   | 538597F50A |
| 8086:5aa8 | 19da:b325 | Intel      | Celeron N3350/Pentium N42... | 6     | xhci_hcd   | 23BDDBF63A |
| 8086:9ded | 17aa:314d | Intel      | Cannon Point-LP USB 3.1 x... | 6     | xhci_hcd   | BD2F6222E5 |
| 8086:a12f | 19da:b333 | Intel      | 100 Series/C230 Series Ch... | 6     | xhci_hcd   | CC099348C2 |
| 8086:a36d | 17aa:3136 | Intel      | Cannon Lake PCH USB 3.1 x... | 6     | xhci_hcd   | 2A2C128E48 |
| 1022:15e0 | 17aa:3151 | AMD        | Raven USB 3.1                | 5     | xhci_hcd   | 76152DDCE8 |
| 1022:15e1 | 17aa:3151 | AMD        | Raven USB 3.1                | 5     | xhci_hcd   | 76152DDCE8 |
| 1022:7908 | 103c:8158 | AMD        | FCH USB EHCI Controller      | 5     | ehci_hc... | 95BC62EF3F |
| 1022:7914 | 103c:8158 | AMD        | FCH USB XHCI Controller      | 5     | xhci_pci   | 95BC62EF3F |
| 10ec:816d | 17aa:3151 | Realtek... | RTL811x EHCI host controller | 5     | ehci_pci   | 76152DDCE8 |
| 1b6f:7023 | 1b6f:7023 | Etron T... | EJ168 USB 3.0 Host Contro... | 5     | xhci_pci   | 87C89614B1 |
| 8086:a2af | 103c:829a | Intel      | 200 Series/Z370 Chipset F... | 5     | xhci_hcd   | 1F3D092233 |
| 8086:a36d | 8086:2089 | Intel      | Cannon Lake PCH USB 3.1 x... | 5     | xhci_pci   | 2EB74A58D2 |
| 1022:15e0 | 103c:8836 | AMD        | Raven USB 3.1                | 4     | xhci_pci   | DA34E7C710 |
| 1022:15e1 | 103c:8836 | AMD        | Raven USB 3.1                | 4     | xhci_pci   | DA34E7C710 |
| 1022:43ef | 103c:8836 | AMD        | USB Controller               | 4     | xhci_pci   | DA34E7C710 |
| 1022:7908 | 103c:8267 | AMD        | FCH USB EHCI Controller      | 4     | ehci_pci   | EDC6F2231B |
| 1022:7908 | 17aa:312f | AMD        | FCH USB EHCI Controller      | 4     | ehci_pci   | 5205C41BC5 |
| 1022:7914 | 103c:8267 | AMD        | FCH USB XHCI Controller      | 4     | xhci_hcd   | EDC6F2231B |
| 1022:7914 | 17aa:312f | AMD        | FCH USB XHCI Controller      | 4     | xhci_hcd   | 5205C41BC5 |
| 1033:0194 | 19da:0194 | NEC Com... | uPD720200 USB 3.0 Host Co... | 4     | xhci_hcd   | 121F403E29 |
| 1912:0015 | 19da:0194 | Renesas... | uPD720202 USB 3.0 Host Co... | 4     | xhci_hcd   | 4D23C29B62 |
| 8086:02ed | 1043:87bd | Intel      | Comet Lake PCH-LP USB 3.1... | 4     | xhci_pci   | 7A01C63401 |
| 8086:0f35 | 19da:b219 | Intel      | Atom Processor Z36xxx/Z37... | 4     | xhci_hcd   | 34EFC38E50 |
| 8086:1e26 | 19da:b211 | Intel      | 7 Series/C216 Chipset Fam... | 4     | ehci_hc... | EFBBD0C3F8 |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:816e | 10ec:8168 | Realtek... | RealManage BMC               | 12    |            | 137E91B812 |
| 10ec:816e | 17aa:3181 | Realtek... | RealManage BMC               | 1     |            | A203CD8C57 |

